---
id: 1989-12-kakoy-den-nedeli-6255f58a
issue: kvant_1989_12
year: 1989
number: "12"
title: Ngày nào trong tuần?
rubric: kvant-dlya-mladshih-shkolnikov
rubric_sub: «Квант» для младших школьников
page_first: 38
page_last: 41
page_labels: 36-39
tag: QTZ8
lang: vi
source: kvant_digital
extraction: vision
content_sha256: 1055348bfcee28fedcb67d0046295548eecd212b9650fcbf20040983e24c616d
prompt_sha256: draft-1
translated_from: content/ru/1989/12/articles/08_kakoy-den-nedeli-6255f58a.md
source_content_sha256: c4ee501e2d7cc6fd8dc6369a40ea0674568c032b922a25c49ca4397dfbcbc02e
translation_model: draft
translation_run: vi-draft-2026-10-31
translation_quality: draft
---

⟦folio 36⟧

NGÀY NÀO
TUẦN?

Người đọc tất nhiên biết ngày sinh của ông: năm, tháng, ngày. Còn ngày trong tuần thì sao? Có lẽ đó là thứ Tư, hoặc có thể là thứ Bảy hoặc thứ Hai? Bài viết này giải thích cách trả lời câu hỏi này mà không cần nhờ đến sự trợ giúp của lịch cũ.

Hãy kết thúc những ngày

Để làm điều này, chúng ta chỉ cần gán số 1 cho một ngày nào đó và đánh số các ngày tiếp theo theo thứ tự: số 2, số 3, v.v. Ngày nào được lấy làm ngày đầu tiên, không quan trọng, nó trống chẳng hạn.

Ngày 1 tháng 1 năm thứ nhất.
Khi đó ngày 2 tháng 1 của năm thứ nhất sẽ nhận số 2, ngày 3 tháng 1 của năm thứ nhất - số 3, v.v., ngày 31 tháng 1 của năm thứ nhất sẽ nhận số 31, ngày 1 tháng 2 - ngày số 32, ngày 1 tháng 3 - ngày số 60 (tháng 2 năm thứ nhất có 28 ngày, vì năm đó không phải là năm nhuận). Có tổng cộng 365 ngày trong Năm 1, vì vậy ngày 1 tháng 1 của Năm 2 sẽ là ngày #366, ngày 1 tháng 1 của Năm 3 sẽ là ngày # 731, ngày 1 tháng 1 của Năm 4 sẽ là ngày # 1096 và ngày 1 tháng 1 của Năm 5 sẽ là ngày # 1462 (Năm 4 có 366 ngày). Như vậy, mỗi ngày sẽ nhận được số riêng.

Làm thế nào để tìm ra ngày trong tuần, biết số ngày?

Ví dụ, ngày thứ một triệu trong tuần là ngày nào? Chúng tôi chưa thể trả lời câu hỏi này. Nhưng nếu chúng ta biết ngày trong tuần tương ứng với một ngày với một số nào đó, thì chúng ta có thể xác định ngày trong tuần tương ứng với một ngày với bất kỳ số nào khác. Hãy nói

Bài viết dựa trên tài liệu do Tiến sĩ Khoa học Vật lý và Toán học N. M. Veskin gửi cho người biên tập và một chương trong cuốn sách của O. Ore “Lời mời đến Lý thuyết Số” (M.: Nauka, Thư viện «Kvant», 1980).

⟦folio 37⟧

Zhem, ngày thứ 100.000. Từ ngày đó đến ngày thứ một triệu, 1.000.000-100.000=900.000 ngày sẽ trôi qua. Hãy chia 900.000 cho 7 với số dư: 900.000 = 128.571 7 + 3, nghĩa là số tuần và ba ngày nữa phải trôi qua giữa các ngày được đề cập. Số tuần hoàn toàn không quan trọng đối với chúng tôi, chỉ có ba ngày này mới quan trọng. Cụ thể, nếu ngày thứ 100.000 là Thứ Hai thì ngày thứ 1.000.000 là Thứ Năm, nếu ngày thứ 100.000 là Thứ Ba thì ngày thứ 1.000.000 là Thứ Sáu, v.v.

Bây giờ chương trình hành động đã rõ ràng. Đầu tiên, chúng tôi xác định số lượng mỗi ngày mà ngày trong tuần được chúng tôi biết đến. Công việc này có thể được thực hiện một lần và mãi mãi. Sau đó, chúng tôi xác định số ngày mà chúng tôi quan tâm. Bằng cách so sánh hai số nhận được, chúng tôi xác định ngày trong tuần tương ứng với thứ hai.ngày - như đã giải thích ở trên.

Làm thế nào để tìm số ngày?

Hãy để chúng tôi quan tâm

ngày thứ k của tháng thứ m năm thứ n.

Như bạn đã biết, có năm nhuận và không nhuận. Năm không nhuận có 365 ngày, năm không nhuận có 366 ngày. Thứ nhất, năm không nhuận là những năm có số không chia hết cho 4 và thứ hai là những năm có số chia hết cho 100 nhưng không chia hết cho 400. (Như vậy, năm 2000 sẽ là năm nhuận, nhưng năm 1900 không phải là năm nhuận, không giống như năm 1904. Điều khoản này phân biệt "lịch Gregorian" hoặc "kiểu mới", với "lịch Julian" hoặc "kiểu cũ". Chúng ta sẽ nói nhiều hơn về phong cách cũ và mới bên dưới.)

Hãy quay trở lại ngày được đề cập. Sau ngày số 1, tức là ngày 1 tháng 1 của năm thứ nhất, N-1 năm, m-1 tháng và k-1 ngày đã trôi qua. Gọi N-1 năm trung bình là N₁ năm nhuận và N₂ năm không nhuận. Sau đó, chúng ta sẽ nghĩ xem N₁ và N₂ bằng bao nhiêu, nhưng bây giờ chúng ta sẽ viết rằng những năm này có 366N₁+365N₂ ngày. Số ngày trong ngày thứ nhất, ...,

Chúng tôi biểu thị tháng thứ 12 bằng a₁, …, a₁₂. Do đó, a₁=a₃=a₅=a₇=a₈=a₁₀=a₁₂=31, a₄=a₆=a₉=a₁₁=30 và a₂=29 hay 28, tùy thuộc vào năm thứ N là năm nhuận hay năm không nhuận. Vì vậy số ngày của chúng tôi là

366N₁+365N₂+a₁+...+aₙ-1+k.

Bây giờ hãy tìm N₁ và N₂. Hãy tưởng tượng N-1 ở dạng 100P+R, trong đó 0<R<99 (nếu N-1 là số có bốn chữ số, như đã hứa trong thực tế, thì P và R là các số nhị phân được viết dưới dạng hai chữ số đầu và hai chữ số cuối của số N-1). Tiếp theo, chia P và R cho 4 với số dư: P=4p+q, R=4r+s (0<q<3, 0<s<3). Trước năm của chúng tôi là P bảng đầy đủ. Mỗi năm có 99 năm, các số không chia hết cho 100, trong đó có 24 năm nhuận và 75 năm không nhuận. Trong số P năm có số chia hết cho 100 thì có p năm nhuận và P−p=3p+q năm không nhuận. Cuối cùng, từ R của những năm gần đây có r năm nhuận và R−r=3r+s năm không nhuận. Vì thế,

N₁=24P+p+r=97p+24q+r,
N₂=75P+3p+q+3r+s=303p+
+76q+3r+s.

Công thức cuối cùng cho số ngày của chúng tôi là:

366(97p+24q+r)+365(303p+76q+
+3r+s)+a₁+...+aₙ-1+k=
=146 097p+36 524q+1461r+365s+
+a₁+...+aₙ-1+k.

⟦folio 38⟧

Ví dụ: hãy để dữ liệu chúng tôi quan tâm
Ngày 1 tháng 3 năm 1989.
Cho ngày này $P=19, R=88, p=4, q=3, r=22, s=0, m=3, a_1=31, a_2=28, k=1$, và con số của nó là 726.162.

Ta chỉ cần số dư khi chia cho 7

Số ngày chỉ khiến chúng tôi quan tâm với độ chính xác của bất kỳ số nào chia hết cho 7 (vì ngày chỉ khiến chúng tôi quan tâm đến một số nguyên tuần). Do đó, cần lưu ý rằng 146.097 = 20.871 7 chia hết cho 7, do đó số hạng đầu tiên trong tổng của chúng ta có thể đơn giản bị loại bỏ. Hơn nữa, 36,524=5217·7+5 nên cùng với hệ số 36,524 ta có thể lấy 5; theo cách tương tự, 1461 và 365 cộng lại chúng ta có thể lấy 5 và 1. Số tiền khổng lồ của chúng ta sẽ biến thành
$$5(q+r)+s+a_1+\dots+a_{m-1}+k,$$
Ngoài ra, đối với $a_1,\dots,a_{12}$, các giá trị 28, 29, 30, 31 có thể được thay thế dễ dàng bằng số dư của phép chia cho 7, tức là các giá trị 0, 1, 2, 3, tương ứng. Sau đó, vào ngày 1 tháng 3 năm 1989, số của chúng tôi sẽ được thay thế bằng số
$$5(3+22)+0+3+0+1=129,$$
có cùng số dư khi chia cho 7 làm số ngày của chúng ta (thực tế, việc kiểm tra cho thấy rằng đối với các số tổng quát số dư này là 3). Nhân tiện, phần tốn thời gian nhất của phép tính cuối cùng là tìm tổng $a_1+\dots+a_{m-1}$, hay đúng hơn là phần còn lại khi chia số tiền này cho 7. Phần dư này phụ thuộc vào $m$ và liệu năm đó có phải là năm nhuận hay không. Sẽ rất hợp lý khi tính toán nó một lần và ghi lại kết quả vào Bảng 1.

Ví dụ: tổng tương ứng với tháng 8 của năm nhuận là 31+29+31+30+31+30+31, số dư của nó khi chia cho 7 sẽ bằng số dư 3+1+3+2+3+2+3=17, tức là bằng 3; điều này được ghi lại trong Bảng 1.

Bây giờ hãy nhìn vào lịch và chắc chắn rằng ngày 1 tháng 3 năm 1989 là Thứ Tư. Ở trên, chúng ta phát hiện ra rằng phần dư của phép chia số của ngày hôm nay cho 7 bằng 3. Điều này có nghĩa là nếu phần dư của phép chia số trong ngày cho 7 bằng 3 thì ngày đó là Thứ Tư. So khớp, nếu số dư là 4, 5, 6, 0, ..., thì ngày đó là Thứ Năm, Thứ Sáu, Thứ Bảy, Chủ Nhật, .... Như bạn thấy, chúng ta đã hơi may mắn: phần còn lại khi chia số kết quả cho 7 chỉ đơn giản bằng số của ngày trong tuần:

1 - Thứ Hai 4 - Thứ Năm
2 - Thứ Ba 5 - Thứ Sáu
3 — Thứ Tư 6 — Thứ Bảy
0 - Chủ nhật.

(May mắn là ngày đầu tiên chúng tôi lấy một cách khoa học - ngày 1 tháng 1 năm thứ nhất - hóa ra lại là một ngày muộn. Nếu không có điều này, chúng tôi đã phải sửa đổi máu cho công thức cuối cùng.) Bây giờ chúng ta có thể viết công thức cuối cùng.

Công thức
Hãy xem xét

$$k-й день m-го месяца N-го года.$$
Chúng ta hãy biểu thị bằng $R$ bằng hai giá trị số được tạo thành từ hai chữ số cuối của số $N-1$ và bằng $P$ số được tạo thành từ các chữ số còn lại của số $N-1$. Tiếp theo, chia các số $P$ và $R$ có số dư là 4: $P=4p+q, R=4r+s$. Sau đó chúng ta tìm số

$$D=5(q+r)+s+b+k,$$

Bảng 1

⟦folio 39⟧

trong đó $b$ phụ thuộc vào vị trí và “năm nhuận” của năm $N$ và được tìm thấy từ Bảng 1. Phần dư khi chia số $D$ cho 7 là số ngày trong tuần.

Ví dụ. Cuộc chiến tranh vệ quốc vĩ đại bắt đầu vào ngày 22 tháng 6 năm 1941. Hôm đó là ngày thứ mấy trong tuần? Ta tính: $P=19=4\cdot 4+3$, $R=40=4\cdot 10+0$, $b=4$ (năm không nhuận),

$$D=5(3+10)+0+4+22=91,$$

Số dư khi chia số $D$ cho 7 là 0. Vậy hôm đó là Chủ nhật.

Phong cách cũ và phong cách mới

Phương pháp xác định năm nhuận được nêu ở tr. 37, được giới thiệu vào thế kỷ 16; Trước đó, tất cả những năm có số chia hết cho 4 đều được coi là năm nhuận. Nhu cầu điều chỉnh là do chu kỳ quay của Trái đất quanh Mặt trời thực tế là ít hơn vài phút so với 365 $\frac{3}{4}$ ngày. Vì vậy, theo thời gian, năm mới đã đến gần mùa xuân, nếu không có sự đổi mới thì đến năm 12.000 đã đến đúng thời điểm hoa giọt tuyết nở rộ. Ở Nga, phong cách mới chỉ được giới thiệu vào tháng 1 năm 1918. Vì vậy, nhiều sự kiện lịch sử thường được gọi theo phong cách cũ.

Sự khác biệt giữa phong cách cũ và phong cách mới xuất phát từ việc phong cách cũ có từ

Bảng 2

| Ngày (kiểu mới, bao gồm) | Số ngày mà phong cách mới đi trước phong cách cũ |
| :--- | :--- |
| 13 tháng 3 năm 1900 - 13 tháng 3 năm 2100 | 13 |
| 12 tháng 3 năm 1800 - 12 tháng 3 năm 1900 | 12 |
| 11 tháng 3 năm 1700 - 11 tháng 3 năm 1800 | 11 |
| 10 tháng 3 năm 1500 - 10 tháng 3 năm 1700 | 10 |
| 9 tháng 3 năm 1400 - 9 tháng 3 năm 1500 | 9 |
