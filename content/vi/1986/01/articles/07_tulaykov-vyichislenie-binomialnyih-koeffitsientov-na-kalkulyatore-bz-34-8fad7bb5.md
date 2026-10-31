---
id: 1986-1-tulaykov-vyichislenie-binomialnyih-koeffitsientov-na-kalkulyatore-bz-34-8fad7bb5
issue: kvant_1986_1
year: 1986
number: "1"
title: Tính hệ số nhị thức trên máy tính BZ-34
authors:
  - Тулайков А. И.
rubric: smes
page_first: 25
page_last: 25
page_labels: "23"
tag: RZKD
lang: vi
source: kvant_digital
extraction: vision
content_sha256: 3bd0a596f15e2d8e99d5c00d09d8493ffe5df1e40cae4d6a2cf95dab5c95fea4
prompt_sha256: draft-1
translated_from: content/ru/1986/01/articles/07_tulaykov-vyichislenie-binomialnyih-koeffitsientov-na-kalkulyatore-bz-34-8fad7bb5.md
source_content_sha256: 30fbe21ac83a92332dbff30341653dcfd0d3b328b03cb3593cd9cbb6b355fccb
translation_model: draft
translation_run: vi-draft-2026-10-31
translation_quality: draft
---

⟦folio 23⟧

lũy thừa và rút gọn các thuật ngữ tương tự, nghĩa là tổng xác suất đảo chữ của từ kkkzz.

Điều thú vị là trường hợp “2 đỏ, 3 vàng” và “2 đỏ, 2 vàng và 1 xanh” đều có xác suất như nhau.

$$\frac{5!}{2!3!} \left( \frac{1}{2} \right)^3 \left( \frac{1}{3} \right)^2 = \frac{5!}{2!2!1!} \left( \frac{1}{2} \right)^2 \left( \frac{1}{3} \right)^2 \left( \frac{1}{6} \right) = \frac{5}{36}.$$

(Đây là những sự kết hợp có khả năng xảy ra nhất của 5 quả ớt với xác suất mà chúng tôi đã chọn.)

Nhiệm vụ

18. Tất cả ba cạnh của khối lập phương 6x6x6 phát ra từ đỉnh A đều được chia theo tỷ lệ 3:2:1, tính từ đỉnh A và các mặt phẳng song song với các cạnh được vẽ qua các điểm phân chia, cắt khối lập phương thành 21 mảnh (hình 5).

a) Có bao nhiêu khối trong số chúng sẽ là khối 3x2x1?

b) Còn bao nhiêu miếng nữa và sẽ có mấy miếng? Khối lượng của họ là gì?

b) Có mối liên hệ nào giữa vấn đề này và vấn đề hạt tiêu không?

19. Máy tạo ra các hạt 6 hạt bằng cách chọn ngẫu nhiên chúng từ một đống lớn các hạt màu đen, trắng, đỏ và xanh, dịch chuyển theo tỷ lệ 1:2:3:4. Xác suất trong một môi trường như vậy là gì

a) tất cả các hạt đều có màu xanh;

b) mọi thứ đều có cùng màu;

b) sẽ không có một hạt màu đỏ nào;

d) Sẽ có những hạt có đủ bốn màu?

d) Bạn sẽ gặp loại bánh mì nào thường xuyên nhất?

e) Tỉ lệ các hạt trong một đống lớn là bao nhiêu để tìm được những hạt phổ biến nhất có 2 hạt đỏ, 2 hạt đen, một hạt trắng và một hạt xanh?

20. Gọi xác suất để chiếc bánh sandwich rơi có bơ và visa khác nhau là 3/4. Một sự kiện ngẫu nhiên đã xảy ra: một chiếc khay có bảy chiếc bánh sandwich bị lật úp. Xác suất để chính xác k bánh mỳ sẽ có bơ (với mỗi k=0, 1, 2, ..., 7) là bao nhiêu?

Tăng lũy ​​thừa (p+q)^7 và trừ đi mỗi năm ở p=3/4, q=1/4. Bạn có thể sử dụng máy vi tính để tính các hệ số. (Xem Phụ lục.)

Hệ số sinh học

Ở trên, chúng ta hầu như không đề cập đến trường hợp đơn giản và quan trọng nhất của hai chữ cái. Các hệ số của đa thức (a+b)^n có ký hiệu đặc biệt là C^k_n và công thức (a+b)^n = C^0_n a^n + C^1_n a^{n-1} b + ... + C^n_n b^n

được gọi là công thức sinh học của Newton. Chúng ta biết rằng C^k_n - số từ có n chữ cái, bao gồm k chữ cái và n-k chữ a - có thể được tìm thấy bằng công thức

$$C^k_n = \frac{n!}{(n-k)! k!} = \frac{n(n-1)...(n-k+1)}{k!}.$$

Ví dụ,

$$(a+b)^4 = a^4 + 4a^3 b + 6a^2 b^2 + 4ab^3 + b^4,$$

bởi vì

$$C^0_4 = C^4_4 = \frac{4!}{4!0!} = 1,$$

$$C^1_4 = C^4_3 = \frac{4!}{3!1!} = 4,$$

$$C^2_4 = \frac{4!}{2!2!} = 6.$$

Các hệ số sinh học - số C^k_n - phát sinh trong nhiều bài toán khác nhau về sinh học, đại số, hình học, phân tích toán học và lý thuyết xác suất. Chúng được kết nối bằng các nhận dạng đa thức màu đỏ; ví dụ: từ đẳng thức C^k_n + C^k_{n-1} = C^k_{n+1} (xem bài toán 5), suy ra rằng đối với mọi n và k tự nhiên, 0≤k<n,

$$C^k_n + C^k_{n+1} + ... + C^k_n = C^k_{n+1}.$$

(với k=1 đây là công thức mà chúng tôi sử dụng để bắt đầu bài viết). Những con số đáng chú ý này sẽ được thảo luận chi tiết hơn ở một trong những số tiếp theo của tạp chí.

Văn học

1. V. A. Uspensky. Tam giác Pascal. M.: Nauka, 1979.

2. M. I. Bashmkov, V. M. Bekker, V. M. Golkhovoy. Bài tập toán: Đại số và giải tích. M.: Nauka, 1982.— (Sê-ri: Biblutechka «Kvant», số 22)

3. A. N. Kolmogorov, I. G. Zhurbenko, A. V. Prokorov. Giới thiệu lý thuyết xác suất. M.: Nauka, 1982.— (Sê-ri: Biblutechka «Kvant», số 23)

4. D. Knut. Nghệ thuật lập trình máy tính. M.: Mir, 1976, tập. 1.

5. F. Người bán hàng nhiều nhất. Năm mươi xác suất giải trí bài toán với các giải pháp. M.: Nauka, 1985.

Phụ lục: Tính hệ số sinh khối bằng máy tính B3-34.

Đối với n lớn, việc tính toán hệ số sinh học theo cách thủ công là một việc rất khó khăn bài toán. Dưới đây là chương trình dành cho máy tính B3-34*), chương trình này cho phép bạn tính các hệ số C^k_n cho bất kỳ n≤334 nào và tất cả k<n (trong trường hợp này, thu được giá trị gần đúng đáp số cho n<28; với n lớn, chương trình cho giá trị gần đúng đáp số**)).

*) Những sửa đổi nhỏ cho phép chương trình được điều chỉnh phù hợp với các mẫu MK-54 và MK-61.

**) Giới hạn trên là 28 đối với n và độ chính xác của các giá trị gần đúng của các hệ số của đa thức cao hơn so với chương trình trong sách tham khảo nổi tiếng của V.P. Dyacon và A.N. Tsvetkov và V.A. Epanchnikov. (Lưu ý ped.)
