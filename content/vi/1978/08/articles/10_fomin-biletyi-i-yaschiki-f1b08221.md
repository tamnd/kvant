---
id: 1978-8-fomin-biletyi-i-yaschiki-f1b08221
issue: kvant_1978_8
year: 1978
number: "8"
title: Vé và hộp
authors:
  - Фомин С. В.
rubric: raznoe
rubric_sub: Разное
page_first: 46
page_last: 48
page_labels: 44-46
tag: Z5UL
lang: vi
source: kvant_digital
extraction: vision
content_sha256: 386cba7b7417646b921a1d6d78888395dedcaee2737bab1bf0367d8b4469d82c
prompt_sha256: draft-1
translated_from: content/ru/1978/08/articles/10_fomin-biletyi-i-yaschiki-f1b08221.md
source_content_sha256: 9ecb63663755b100b05dd9b7861988eedfb67562d576c9c8da21105d73999807
translation_model: draft
translation_run: vi-draft-2026-10-31
translation_quality: draft
---

⟦folio 44⟧

S. Fomin

Vé và hộp

Trong ghi chú này, bài toán đã được giải quyết, đề xuất vào năm 1977 tại cuộc thi (nghiên cứu) loại XI Olympic Toán toàn liên bang lần thứ hai. bài toán này đã được đặt trong “Bài tập cho Kvanta” («Kvant», 1977, Số 9, M465). Chúng ta hãy nhớ lại công thức của nó.

Có một nghìn vé có số 000, 001, ..., 999 và một trăm ô có số 00, 01, ..., 99. Vé được cắt và đặt vào ô, nếu số ô có thể lấy được từ số của vé này bằng cách gạch bỏ một trong các số. Chứng minh rằng

a) bạn có thể đặt tất cả các vé vào 50 hộp;
b) không thể phân phối tất cả vé vào ít hơn 40 hộp;
b) không thể phân phối tất cả vé vào ít hơn 50 hộp.

Giả sử có 10^k vé có số k chữ số từ 00...0 đến 99...9. Vé được cắt giảm xuống
đặt nó vào hộp, số lượng có thể lấy được từ số phiếu này; gạch bỏ một trong các số. Chứng minh rằng

1. Hàm F(k,N)

Hãy bắt đầu với một câu hỏi thoạt nhìn không liên quan đến nhiệm vụ của chúng ta.

Cho k và N là hai số tự nhiên. Hãy xem xét tất cả các tập hợp k số nguyên không âm có thể có, tổng của chúng bằng N. Đối với mỗi tập hợp như vậy, chúng ta tìm tổng bình phương của các số có trong nó (Hình 1). Chúng tôi biểu thị số tiền nhỏ nhất trong số này bằng F(k, N). Đặt nó tương ứng với tập A = {a₁, a₂, ..., aₖ}.

Bổ đề. Mỗi chữ số trong tập hợp A khác nhau không quá 1.

Bằng chứng. Hãy giả sử điều ngược lại. Giả sử a₂ > a₁ + 1. Xét tập A' = {a₁ + 1, a₂ - 1, a₃, ..., aₖ}.

Từ

$$\left( a_1 + 1 \right)^2 + \left( a_2 - 1 \right)^2 = a_1^2 + a_2^2 - 2 \left( a_2 - a_1 \right) < a_1^2 + a_2^2,$$

tổng bình phương của các số trong tập A' nhỏ hơn tổng bình phương của A. Điều ngược lại thu được chứng tỏ bổ đề.

Bây giờ đã rõ cách tính F(k,N). Bạn cần chia N cho k có số dư và chọn k số sao cho mỗi số bằng thương hoặc lớn hơn thương số 1 và tổng các số này bằng N.

Hình 2 thể hiện bảng giá trị hàm F(k,N) cho k và N nhỏ.

Giải thích "hình học" của F (k, N) là gì? Để đơn giản, cho k = 3. Khi đó bài toán tìm F(k, N) có thể được hiểu như sau: tìm trong tam giác ABC xác định trong không gian các phương trình x₁ + x₂ + x₃ = N và các bất đẳng thức x₁ ≥ 0,

⟦folio 45⟧

Hình 2.

$x_2 \geq 0, x_3 \geq 0$ (Hình 3), lũy thừa $M$ với tọa độ nguyên, khoảng cách ít nhất so với gốc tọa độ $O$ (tổng các bình phương mà chúng ta quan tâm không gì khác hơn bình phương khoảng cách từ điểm $O$ đến $M$). Đương nhiên, chúng ta cần đưa điểm này về đáy của phân phối lại hạ từ $O$ xuống mặt phẳng của tam giác $ABC$, tức là đến điểm $\left(\frac{N}{3}; \frac{N}{3}; \frac{N}{3}\right)$.

Đối với $k > 3$ có thể mở rộng tương tự bằng cách sử dụng khái niệm không gian $k$ chiều.

Hãy xem xét cách giải thích khác của $F(k, N)$. Đặt $k = 2$ để đơn giản. Khi đó, các tập hợp đang xem xét có dạng $|a, N - a|(a - \text{целое неотрицательное})$ và chúng ta phải đối mặt với bài toán việc tìm giá trị nhỏ nhất của hàm $x \rightarrow x^2 + (N - x)^2$ được xác định trên tập hợp các số nguyên từ intervala $[0, N]$. Hàm này là một hàm tam thức bậc hai; mức tối thiểu đạt được tại điểm $x = \frac{N}{2}$. Do đó, $F(2, N)$ bằng $\frac{N^2}{2}$ hoặc $\frac{N^2 + 1}{2}$ tùy thuộc vào tính chẵn lẻ của $N$ (Hình 4).

Đối với $k > 2$ người ta cần xem xét hàm tương ứng của các biến $k - 1$ và tìm mức tối thiểu của nó.

2. Lời giải bài toán a) và b)

Hãy sắp xếp tất cả các hộp theo dạng hình vuông $10 \times 10$, như trong Hình 5, $a$. Trong Hình 5, $b$ hình vuông $Q_0$ này được vẽ theo hình thức quen thuộc với chúng ta; Giả sử rằng mỗi ô của nó là một hộp có số tương ứng. Hãy đánh số các hàng và cột của hình vuông này bằng các số từ 1 đến 9. Vì tất cả các số ở điều kiện bài toán đều bằng nhau nên các hàng và cột của hình vuông $Q_0$ có thể được sắp xếp lại.

Chúng ta cần chọn một số ô nhất định và bỏ tất cả vé vào các ô này. Hãy đồng ý tô các ô tương ứng với các ô đã chọn là $Q_0$. Đặt số lượng ô tối thiểu

⟦folio 46⟧

HIỆN TẠI, cụ thể là $n_0$, được tô bóng ở dòng 0; chúng ta có thể coi đây là những ô $n_0$ đầu tiên của dòng. Bây giờ chúng ta hãy tạo khoảng cách cho hình vuông $Q_1$ thu được từ $Q_0$ bằng cách gạch bỏ các hàng $n_0$ đầu tiên và các cột $n_0$ đầu tiên (Hình 6). Hãy chứng minh rằng tất cả các ô $Q_1$ phải được tô bóng. Để làm điều này, hãy lấy các hộp được đánh số $xy$, trong đó $x \geq n_0$, $y \geq n_0$. Nó phải bao gồm vé $0xy$: không thể đặt nó trong các hộp $0x$ và $0y$, vì các ô tương ứng không được điền vào. Điều này có nghĩa là ô có số $xy$ phải được tô bóng cho tất cả $x \geq n_0$, $y \geq n_0$.

Sau chủ đề, có bao nhiêu ô được tô màu trong hình vuông $Q_0$ của chúng ta. Trong mỗi dòng của hình chữ nhật $\Pi_0$ (xem Hình 6), ít nhất $n_0$ ô được tô bóng. Trong $Q_1$ tất cả các ô $(10-n_0)^2$ đều được tô bóng. Do đó, ít nhất $n_0^2 + (10-n_0)^2$ ô được tô màu trong $Q_0$. Tổng nhỏ nhất trong số này là $F(2, 10)$ 50. Vì vậy, trong mọi trường hợp, ít nhất 50 ô được tô màu $Q_0$. Mặt khác, năm mươi ô có ghi các số trong Hình 7 là đủ: bằng cách gạch bỏ một số trong số mỗi vé sao cho còn lại hai số chẵn lẻ giống nhau, chúng ta sẽ đặt vé này vào ô tương ứng. Hai tin nhắn này hoàn thành lời giải điểm a) và b) bài toán.

3. Lời giải bài toán d)

Bây giờ hãy đặt vé là $k$ chữ số. Chúng ta sẽ giả định rằng chúng ta không có 10 chữ số mà là $N$, trong đó $N$ là một số tự nhiên tùy ý (như thể

chúng tôi đã áp dụng hệ thống số $N$-ary).

Đường vuông $Q_0$ bây giờ đánh số các số từ 0 đến $N-1$; do đó, trong $Q_0$ tổng cộng $N^2$ tế bào.

Như trước đây, chúng ta sẽ giả sử rằng ở hàng 0 có các ô được điền $n_0$ và ở bất kỳ hàng nào khác không có ít hơn $n_0$. Chúng ta hãy xây dựng hình vuông $Q_1$ theo cách tương tự. Hãy thực hiện với $Q_1$ giống như cách chúng ta đã làm với $Q_0$ - chúng ta chọn hàng trong đó có số ô được tô bóng ít nhất (đặt đây là hàng đầu tiên, tức là hàng có số $n_0$ trong ô vuông ban đầu), biểu thị số ô được tô bóng trong đó bằng $n_1$ và loại bỏ những ô đầu tiên từ $Q_1$ $n_1$ hàng và cột, chúng ta có được một hình vuông $Q_2$. Chúng ta sẽ xây dựng với nó theo cách tương tự, v.v., cho đến hình vuông $Q_{k-2}$ (Hình 8). Primogolniki tương tự như $\Pi_0$ sẽ được ký hiệu là

Hình 7.
