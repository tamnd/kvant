---
id: 1986-12-galperin-korlyukov-binarnyiy-algoritm-eeb74fbf
issue: kvant_1986_12
year: 1986
number: "12"
title: Thuật toán nhị phân
authors:
  - Гальперин Г. А.
  - Корлюков А. В.
rubric: raznoe
rubric_sub: Разное
page_first: 42
page_last: 43
page_labels: 40-41
tag: MPKG
lang: vi
source: kvant_digital
extraction: vision
content_sha256: 1a2d9b13ae821bf903e7223ad83d794cd0ba522871ee7c78185ff47f48ee73fd
prompt_sha256: draft-1
translated_from: content/ru/1986/12/articles/13_galperin-korlyukov-binarnyiy-algoritm-eeb74fbf.md
source_content_sha256: 18f8acb2c4da033c5326c1703d6d32c14c07a16da3867c9f4ae7974ec317803c
translation_model: draft
translation_run: vi-draft-2026-10-31
translation_quality: draft
---

⟦folio 40⟧

Thuật toán nhị phân

Ứng viên Khoa học Vật lý và Toán học
G. A. GALPERIN,
Tiến sĩ Vật lý và Toán học
A. V. KORLYUKOV

Thuật toán của Euclid để tìm ước số chung lớn nhất (GCD) của hai số được trình bày trong cuốn sách tiếp theo của cuốn Elements (khoảng năm 300 trước Công nguyên). Nhiều học giả cho rằng đó là cách giải thích thuật toán do Evdkocom đề xuất (khoảng năm 375 trước Công nguyên). Bằng cách này hay cách khác, thuật toán Euclide có thể được gọi là “ông nội” của tất cả các thuật toán, vì đây là thuật toán không tầm thường đầu tiên còn tồn tại cho đến ngày nay *. Có lẽ phần này có thể mô tả các phương pháp tính toán lời giải của một số hệ phương trình bậc hai có hai ẩn số, xuất hiện trước Euclid một thiên niên kỷ rưỡi. Tuy nhiên, chúng không nổi bật so với thuật toán Euclide vì chúng không chứa phép lặp và vì chúng được bắt nguồn từ các phương pháp đại số hiện đại.

Như đã nêu trong bài báo được trích dẫn trong danh sách, "Hầu hết các thuật toán cổ xưa theo thời gian đã bị các thuật toán mới hơn loại bỏ khỏi thực tiễn tính toán. Thuật toán Euclid tránh phần này chủ yếu do tính đơn giản của nó." Điều đáng ngạc nhiên hơn là mặc dù thuật toán Euclide đáng kính được sử dụng cho các bảng trụ, nhưng nó (như sẽ được trình bày bên dưới) không phải lúc nào cũng là cách tốt nhất để tìm GCD!

Khoảng năm 1962, Roland Silver và John Terzan đã phát hiện ra một thuật toán hoàn toàn khác để tìm GCD, chủ yếu phù hợp với số học kép. Thuật toán “nhị phân” mới này không cần các lệnh yêu cầu (như trong thuật toán Euclide) thực hiện một hành động, chứ đừng nói đến một hành động có phần còn lại. Dựa trên các phép trừ, thuật toán nhị phân cũng kiểm tra xem một số có phải là số chẵn hay không và dịch chuyển biểu diễn kép của số chẵn sang phải (từ đó thực hiện giảm một nửa).

Thuật toán nhị phân được thực hiện rất đơn giản trên máy tính vi mô và điều này khác với thuật toán Euclide. Lưu ý rằng việc thực hiện thuật toán Euclide trên máy tính vi mô rất khó: khó khăn chính là thiếu các phép chia có phần dư là hai số nguyên. Chẳng hạn, trong số 300 chương trình được đưa ra trong sách tham khảo của V.P. Dyakonov*) không có thuật toán Euclide. Chúng ta cũng hãy lưu ý rằng không có chỉ định nào được chấp nhận rộng rãi trong trường cho phần còn lại của phân chia; Có lẽ vì lý do này mà trong SGK tin học lớp 9, khi viết thuật toán Euclid người ta đề xuất thay phép chia bằng số dư bằng phép trừ tuần tự.

Chúng ta hãy chuyển sang phần mô tả thuật toán nhị phân để tìm ước chung lớn nhất của hai số nguyên. Nó dựa trên ba đặc tính đánh giá sau của GCD:

1. GCD (2m, 2n)=2·GCD (m, n).
2. GCD (2m, 2n+1)=GCD (m, 2n+1).
3. GCD (m, n)=GCD (m−n, n). Theo định nghĩa của GCD, GCD (m, n)=GCD (n, m), GCD (−m, n)=GCD (m, n), GCD (0, 0)=0, GCD (m, 0)=|m|. Từ các thuộc tính 1 - 3, ngay lập tức thu được một thuật toán, chúng ta sẽ mô tả bằng lời, giải thích nó bằng ví dụ tìm gcd của các số 40,902 và 24,140.

Giả sử chúng ta cần tìm gcd(m₀, n₀); hãy biểu thị nó d. Theo thuộc tính 1, trước tiên chúng ta chọn lũy thừa lớn nhất của hai 2ᵉ, chia cả m₀ và n₀, cũng như số d (đối với các số 40,902 và 24,140, ​​​​k=1 và 2ᵉ=2). Hãy giảm m₀ và n₀ xuống 2ᵉ lần và nhớ số 2ᵉ. Chúng ta nhận được hai số (20,451 và 12,070), một trong số đó (hoặc cả hai) là số lẻ (số 20,451 của chúng ta là số lẻ) và gcd của những số này là d₁=d/2ᵉ. Sau đó, nếu một trong các số này là số chẵn (12.070), thì chia nó cho lũy thừa tối đa có thể có của hai, để lại số thay đổi thứ hai và kết quả là chúng ta nhận được hai số lẻ m và n

*) Để biết thêm thông tin về thuật toán Euclide, xem bài viết của S. A. Abramov năm «Kvant», 1985, số 11, tr. 44.

⟦folio 41⟧

(20,451 và 6,035) với gcd (m, n) = d₁. Sau những thao tác này, chúng tôi đã đạt đến bài toán chỉ tìm GCD cho các số lẻ. Với lời giải của nó, chúng tôi sử dụng thuộc tính 3. Chúng tôi trừ số nhỏ hơn khỏi số lớn (20451-6035 = 14 416) mà không thay đổi GCD = d₁ và vì hiệu của các số lẻ luôn là số chẵn nên chúng tôi áp dụng thuộc tính 2: chúng tôi giảm chênh lệch này bằng lũy ​​thừa tối đa của hai (trong ví dụ là 2²), một lần nữa thu được số lẻ (901). Sau đó, chúng ta lại sử dụng thuộc tính 3 (6035-901=5134) và một hoặc nhiều lần thuộc tính 2 (5134:2=2567), do đó, lại sử dụng thuộc tính 3 và 2, v.v. (2567—901=1666→833→901—833=68→17→833—17=816→51→51—17=34→17). Sau mỗi thao tác, GCD không thay đổi nhưng ít nhất một số trong cặp giảm đi. Do đó, tại một số điểm, cả hai số sẽ bằng nhau; rõ ràng là cả hai sẽ bằng d₁ tại thời điểm này. Sau đó, gcd mong muốn (m₀, n₀) được tính bằng tích của các số 2ᵏ và d₁. (Đối với các số của chúng tôi GCD (40902, 24140)=2·17=34.)

Trong thuật toán nhị phân đã cho, chỉ sử dụng các phép tính trừ và chia cho 2. Cách thứ hai đặc biệt đơn giản nếu m và n được viết trong hệ thống số kép.

Trong ngôn ngữ thuật toán giáo dục, thuật toán này có thể được viết như sau*):

alg nhị phân (số nguyên m, n, k, r, s, d)
apr m, n
độ phân giải d
bắt đầu r:=0, s:=0
trong khi m≠n
vẫn chưa m chẵn
cũng không m:=m/2
r:=r+1
kts
miễn là n chẵn
cũng không n:=n/2
s:=s+1
kts
k:=min {r, s, k}
trong khi m>n
cũng không phải m:=m-n
kts
trong khi n>m
cũng không n:=n-m
kts
d:=2ᵏ·m

lừa đảo

*) Nếu k không được xác định thì khi tìm min {r, s, k} ta giả sử min {r, s, k} = min(r, s). Thủ thuật nhỏ này cho phép bạn xác định k một lần và mãi mãi: khi r và s tăng thêm, nó không thay đổi.

Chương trình này có thể dễ dàng dịch sang ngôn ngữ Robik hoặc Basic hoặc dịch sang mã cho máy tính vi mô có thể lập trình như BZ-34 (xem «Kvant», 1986, Số 2, 3).

Hãy xem cách tổ chức các phép tính bằng thuật toán nhị phân trên máy tính chung (không lập trình được). Cho các số nguyên dương m và n; việc tính toán d=gcd(m, n) sau đó được chia thành các bước sau.

1. Chúng tôi gửi số m đến chỉ báo và chia nó làm đôi k₁ lần (k₁ ≥0) cho đến khi nhận được số lẻ m₁.
2. Chúng ta gửi số n đến chỉ báo (đồng thời m₁ được chuyển sang ô nhớ) và chia đôi k₂ lần (k₂ ≥0) cho đến khi nhận được số lẻ.
3. Nếu các số trong bộ nhớ và trên chỉ báo bằng nhau thì số trên chỉ báo sẽ được nhân đôi k lần, trong đó k=min {k₁, k₂}; số kết quả là d.
4. Nếu số trên chỉ báo nhỏ hơn số trong bộ nhớ thì chúng ta hoán đổi chúng.
5. Hãy thực hiện phép trừ.
6. Chia số trên chỉ báo làm đôi cho đến khi thu được số lẻ và quay lại bước 3.

Điều đáng ngạc nhiên là ngay cả khi tìm thủ công GCD của hai số có nhiều chữ số (ví dụ: số có bốn chữ số), tính ưu việt của thuật toán nhị phân so với thuật toán Euclide vẫn được thể hiện. Cần ít hơn và thực tế không có lỗi tính toán: xét cho cùng, thuật toán Euclide chỉ cần một số lượng rút gọn, nhưng mỗi lần lặp được thực hiện đơn giản hơn nhiều - không có bước chia nào cả. Sự đơn giản này cho phép bạn tiết kiệm đáng kể thời gian khi tìm GCD, như có thể thấy trong ví dụ sau.

Thuật toán Euclid
GCD (40902, 24140)=34
