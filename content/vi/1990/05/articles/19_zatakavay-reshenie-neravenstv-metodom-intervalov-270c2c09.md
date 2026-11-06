---
id: 1990-5-zatakavay-reshenie-neravenstv-metodom-intervalov-270c2c09
issue: kvant_1990_5
year: 1990
number: "5"
title: Lời giải bất đẳng thức theo phương pháp khoảng
authors:
  - Затакавай В. В.
rubric: praktikum-abiturienta
rubric_sub: Практикум абитуриента
page_first: 65
page_last: 67
page_labels: 63-65
lang: vi
source: kvant_digital
extraction: vision
content_sha256: 373714c4415ac40bbf31a495bbc2a3955093754f663ac9580d0cde3a17a71520
prompt_sha256: draft-1
translated_from: content/ru/1990/05/articles/19_zatakavay-reshenie-neravenstv-metodom-intervalov-270c2c09.md
source_content_sha256: 6776b800ecbdd8d2803462daff8586e33f596bb3a7261c3435c9bb9fa208c60f
translation_model: draft
translation_run: vi-draft-gaps-2026-11-05
translation_quality: draft
---

⟦folio 63⟧

---
running_head:
folio:
---

Lời giải
sự bất bình đẳng
phương pháp
khoảng thời gian

Ứng viên khoa học sư phạm
B. KHÓA

Bài viết này dành cho học sinh trung học (lớp 10-11) và có thể được sử dụng để chuẩn bị cho kỳ thi tuyển sinh đại học.

Đối với các bất đẳng thức lời giải, hai cách tiếp cận tiêu chuẩn thường được sử dụng. Hãy xem xét chúng bằng cách sử dụng ví dụ về bất đẳng thức đơn giản

$$\frac{x-1}{x-2} > 0.$$

Bất đẳng thức này áp dụng cho hai hệ thống:

$$\begin{cases} x-1 > 0, \\ x-2 > 0 \end{cases}$$ hoặc $$\begin{cases} x-1 < 0, \\ x-2 < 0. \end{cases}$$

Từ hệ thống đầu tiên, chúng tôi nhận được $x > 2$ hoặc $(2; +\infty)$. Từ giây - $x < 1$ hoặc $(-\infty; 1)$. Lời giải của bất đẳng thức ban đầu: $(-\infty; 1) \cup (2; \infty)$.

Một phương pháp khác là phương pháp khoảng nổi tiếng. Ý tưởng của anh ấy rất đơn giản. Vì vậy, trong trường hợp này, tử số của phân số $\frac{x-1}{x-2}$, chuyển về 0 tại $x=1$, giữ lại dấu trừ ở nửa dòng $(-\infty; 1)$ và dấu cộng ở nửa dòng $(1; \infty)$.

Mẫu số của phân số, chuyển về 0 tại $x=2$, giữ lại dấu “trừ” ở nửa dòng $(-\infty; 2)$ và dấu “cộng” ở $(2; \infty)$. Như vậy, một phân số chỉ đổi dấu khi đi qua các điểm $x=1$ và $x=2$ và do đó giữ nguyên dấu này hoặc dấu khác

Hình 1.

⟦folio 64⟧

---
running_head:
folio:
---

tại mỗi ba khoảng thời gian:
$(-\infty; 1), (1; 2)$ và $(2; +\infty)$ (hình 1).

Với ví dụ đơn giản như vậy, có thể dễ dàng nhớ lại ý tưởng của phương pháp nghịch đảo nhưng không thể thấy được ưu điểm đáng chú ý nào của nó. Những bất đẳng thức phức tạp hơn lại là một vấn đề khác.

Ví dụ 1.

$$\frac{1}{x-1} + \frac{1}{x-2} \geq \frac{1}{x-3}.$$

Lời giải. Sau khi sắp xếp lại phân số $\frac{1}{x-3}$ sang vế trái và đưa về mẫu số chung, ta thu được:

$$\frac{x^2 - 6x + 7}{(x-1)(x-2)(x-3)} \geq 0.$$

Cách tiếp cận đầu tiên đối với lời giải của bất đẳng thức này - sử dụng hệ bất đẳng thức - dẫn đến việc xem xét một số lượng khá lớn của hệ. Phương pháp khoảng cách trong trường hợp này của thành phố là hợp lý hơn. Hàm $f(x) = \frac{x^2 - 6x + 7}{(x-1)(x-2)(x-3)}$ được xác định trên toàn bộ trục số ngoại trừ các “số 0” của mẫu số - điểm 1, 2, 3. Các số 0 của tử số là $3 - \sqrt{2}$ và $3 + \sqrt{2}$. Hãy đặt tên cho tất cả các điểm trên trục. Trên mỗi khoảng trong số sáu khoảng được hình thành, hàm $f(x)$ giữ lại một hoặc một dấu khác.

Đáp số thực ra là “vẽ” (hình 2), tất cả những gì còn lại là viết nó ra một cách cẩn thận.

Hình 2.

Đáp số: $(1; 3 - \sqrt{2}) \cup (2; 3) \cup [3 + \sqrt{2}; +\infty)$.

Trong ví dụ đang xem xét, các dấu trong các khoảng dấu hằng số của hàm số bị chéo. Tuy nhiên, tất nhiên, người ta không nên “khái quát hóa” rằng điều này sẽ luôn xảy ra.

Ví dụ 2.

$$\frac{(x+2)^2}{x-1} \geq 0.$$

Lời giải. Quy mô bất bình đẳng này là “quỷ quyệt”. Người ta thường giải như sau: vì $(x+2)^2 \geq 0$ với mọi $x$ nên dấu của phân số phụ thuộc vào dấu của mẫu số nên ta có $x > 1$. Sự mâu thuẫn của đáp số là rất nghiêm trọng: điểm cô lập $x = -2$ cũng thỏa mãn bất đẳng thức không đầy đủ. Phương pháp nghịch đảo, với tính chất “nhỏ gọn” của nó, giúp tránh được loại lỗi này ở mức độ lớn hơn (hình 3).

Hình 3.

Vẫn còn phải viết ra các khoảng và điểm mà tại đó hàm $f(x) = \frac{(x+2)^2}{x-1}$ nhận các giá trị không âm.

Đáp số: $\{-2\} \cup (1; +\infty)$.

Lưu ý rằng trong ví dụ này, khi truyền $x = -2$, dấu của hàm không thay đổi. Điều này là do “bội số” của số 0 của hàm số. Rõ ràng, nếu bội số của 0 là chẵn (trong trường hợp này bội số của 0 $x = -2$ là hai), thì dấu của hàm số không thay đổi khi đi qua một điểm như vậy; nếu bội số của 0 là số lẻ thì dấu của hàm số đổi ngược lại. Ở trường, theo quy định, các em tìm ra dấu của hàm số trên mỗi khoảng của hằng số. Điều này là hợp lý, nhưng trong quá trình thực hành các kỳ thi tuyển sinh, có những khoảng thời gian “bất tiện” trên thang đo: việc xác định dấu trên chúng gắn liền với những khó khăn trong tính toán. Do đó, việc tính đến bội số của nghiệm thường làm cho lời giải dễ dàng hơn.

Khả năng chấp nhận của phương pháp nghịch đảo không chỉ giới hạn ở việc giải các bất đẳng thức hữu tỉ. Phương pháp phổ quát dựa trên một tính chất khá rõ ràng của các hàm liên tục: “Nếu trên khoảng $(a; b)$ hàm $f(x)$ liên tục và không biến mất thì nó giữ nguyên dấu không đổi trên khoảng này”*).

Hãy xem xét thêm một vài ví dụ.

*) Ví dụ, xem sách giáo khoa “Đại số và sự khởi đầu của phân tích 9-10”, M.: Prosveshchenie, 1988, tr. 98.

⟦folio 65⟧

---
running_head:
folio:
---

$$\frac{\sqrt{2-x} + 4x - 3}{x} \geqslant 2.$$

Lời giải. Tên miền $x \leqslant 2$, $x \neq 0$. Ta rút gọn bất đẳng thức về dạng
$$\frac{\sqrt{2-x} + 2x - 3}{x} \geqslant 0.$$

Để tìm số 0 của tử số cần giải phương trình vô tỉ $\sqrt{2-x} = 3 - 2x$. Đối với lời giải phương trình vô tỉ, do bình phương, có thể phát sinh cách xây dựng lời giải cần phải loại bỏ (trong trường hợp này, $x = 1\frac{3}{4}$ là cách xây dựng lời giải).

Vậy tử số bằng 0 tại $x = 1$. Lời giải bất đẳng thức được trình bày ở hình 4.

Hình 4.

Đáp số: $(-\infty; 0) \cup [1; 2]$.
Ví dụ 4.
$$\frac{1}{3 + \sqrt{9-x^2}} + \frac{1}{3 - \sqrt{9-x^2}} > \frac{1}{x}.$$

Lời giải. Phạm vi định nghĩa được tìm thấy từ các điều kiện sau:
$$9 - x^2 \geqslant 0, 3 - \sqrt{9-x^2} \neq 0, x \neq 0, t. e. [-3; 0) \cup (0; 3].$$ Hơn nữa, trong trường hợp này, điều quan trọng là phải biết, vì đã ở giai đoạn chuẩn bị sau các phép biến đổi ước tính, biểu thức $\sqrt{9-x^2}$ biến mất và dẫn đến sự bất bình đẳng $\frac{6-x}{x^2} > 0$ có ​​các thành phố “rộng hơn” và khu vực xác định, và lời giải.

Bất đẳng thức Lời giải $\frac{6-x}{x^2} > 0$, cụ thể là $(-\infty; 0) \cup (0; 6)$, bị giới hạn bởi miền gốc, dẫn đến đáp số: $[-3; 0) \cup (0; 3]$.

Ví dụ 5.
$$\log_2 \sqrt{7-x} \cdot \log_{(x-1)} 4 \leqslant 2.$$

Lời giải. Miền định nghĩa được cho bởi các điều kiện $7-x > 0, x-1 > 0, x-1 \neq 1$, tức là $(1; 2) \cup (2; 7)$.

Ở giai đoạn chuẩn bị, chúng tôi nhận được:
$$\frac{\log_2 \sqrt{7-x}}{\log_4(x-1)} \leqslant 2,$$
và hơn thế nữa,
$$\frac{\log_2(7-x) - 2\log_2(x-1)}{\log_2(x-1)} \leqslant 0.$$

Bất đẳng thức cuối cùng, có tính đến miền định nghĩa được tìm thấy trước đó, tương đương với bất đẳng thức ban đầu.

Các số 0 của tử số được xác định từ phương trình
$$\log_2(7-x) = 2\log_2(x-1).$$

Tại lời giải của phương trình logarit, có nguy cơ thu được nghiệm xây dựng: $7-x=(x-1)^2$ hoặc $x^2-x-6=0$. Ở đây lời giải $x=3$ là nghiệm của phương trình logarit và lời giải $x=-2$ là nghiệm xây dựng, vì $-2-1=-3<0$.

Mẫu số 0 $x=2$.

hình 5 đại diện cho lời giải của bất đẳng thức ban đầu.

Hình 5.

Đáp số: $(1; 2) \cup [3; 7)$.
Ví dụ 6.
$$\log_{(x^2-2x+1)} (3-x) \leqslant 1.$$

Lời giải. Ví dụ này có một gợi ý “xảo quyệt”: bình phương đầy đủ của hiệu ở đáy logarit truyền đạt mong muốn loại bỏ hình vuông:
$$\frac{1}{2}\log_{|x-1|} (3-x) \leqslant 1.$$

Các bất đẳng thức logarit được xem xét có chứa dấu của mô hình có liên quan đến những khó khăn đã biết. Theo tôi, sẽ hợp lý hơn nếu giảm logarit về một số cơ số cụ thể, chẳng hạn như cơ số $e$ và sử dụng phương pháp tương tác.

Các điều kiện $x^2-2x+1 \neq 0, x^2-2x+1 \neq 1, 3-x > 0$ đưa ra các miền định nghĩa: $(-\infty; 0) \cup (0; 1) \cup (1; 2) \cup (2; 3).$
