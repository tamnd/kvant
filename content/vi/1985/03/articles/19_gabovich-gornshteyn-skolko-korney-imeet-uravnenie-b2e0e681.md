---
id: 1985-3-gabovich-gornshteyn-skolko-korney-imeet-uravnenie-b2e0e681
issue: kvant_1985_3
year: 1985
number: "3"
title: Phương trình có bao nhiêu nghiệm?
authors:
  - Габович И. Г.
  - Горнштейн П. И.
rubric: praktikum-abiturienta
rubric_sub: Практикум абитуриента
page_first: 45
page_last: 48
page_labels: 43, 44, 46
tag: LJ5F
lang: vi
source: kvant_digital
extraction: vision
content_sha256: da2195214f922d7da2cf4dea2f703613b510133d75f81d608c61f30378a7a4e9
prompt_sha256: draft-1
translated_from: content/ru/1985/03/articles/19_gabovich-gornshteyn-skolko-korney-imeet-uravnenie-b2e0e681.md
source_content_sha256: eaf9370ee3c1e4cd759a58324b4312a3fa321ffe3257ea2eef3f13fee06d209b
translation_model: draft
translation_run: vi-draft-2026-10-31
translation_quality: draft
---

⟦folio 43⟧

Phương trình có bao nhiêu nghiệm?

I. G. GABOVICH,
P.I.GORNITEIN

Trong các kỳ thi đại học nâng cao, các ví dụ thường được đưa ra để xác định xem một phương trình đã cho có bao nhiêu nghiệm. Lưu ý rằng trong các ví dụ này, thường chỉ cần tìm số lượng nghiệm chứ không phải bản thân các nghiệm.

Một câu hỏi phân tích khó hơn liên quan đến phương trình chứa tham số. Trong trường hợp này, người ta đề xuất xác định giá trị nào của tham số mà phương trình đã cho có một, hai hoặc số nghiệm hữu hạn khác.

Lời giải những ví dụ như vậy được gửi trong bài viết này.

Ví dụ 1 (KSU, Cơ học và Toán học, 1981). Phương trình có bao nhiêu nghiệm?
$$x^2 - 2x - \log_2|1-x| = 3?$$
(1)

Lời giải. Chúng ta hãy viết lại phương trình (1) dưới dạng
$$x^2 - 2x - 3 = \log_2|x - 1|.$$
(2)

Rõ ràng là (2) ⇔ (1). Cũng lưu ý rằng dấu của biểu thức dưới dấu hoành độ có thể được đổi thành ngược lại.

Số nghiệm của phương trình (2) bằng số giao điểm của đồ thị hàm số là vế trái và vế phải của phương trình (2). Đồ thị của các hàm số này (hình 1) cắt nhau tại bốn điểm ($A, B, C$ và $D$). Do đó, phương trình (2), và do đó phương trình tương đương (1), có nghiệm chẵn (bằng hoành độ của các điểm giao nhau).

Ví dụ 2 (MSU, VMK, 1980). Tại giá trị nào của tham số a phương trình thực hiện
$$(a+1)x^2 - ax + (a-3) = 0$$
(3)
có nhiều nhất một gốc thực sự?

Lời giải. 1) Đặt $a \neq -1$. Khi đó phương trình (3) là bậc hai và có nhiều nhất một nghiệm thực nếu $D \leqslant 0$, tức là
$$a^2 - 4(a+1)(a-3) \leqslant 0 \Leftrightarrow 3a^2 - 8a - 12 \geqslant 0.$$
(4)

Tam thức bình phương $3a^2 - 8a - 12$ có nghiệm: $a_1 = (4-2\sqrt{13})/3$ và $a_2 = (4+2\sqrt{13})/3$. Rõ ràng là $a_2 > -1$. Hãy để chúng tôi chứng minh rằng $a_1 < -1$:
$$-1 - (4-2\sqrt{13})/3 = (2\sqrt{13} - 7)/3 = (\sqrt{52} - 7)/3 > 0;$$
điều này có nghĩa là $a_1 < -1$.

Do đó, nghiệm của (4) sẽ là gộp các khoảng:
$$] -\infty; (4-2\sqrt{13})/3] \cup \cup[(4+2\sqrt{13})/3; \infty[.$$
2) Tại $a = -1$, phương trình (3) chuyển thành phương trình bậc một: $x - 4 = 0$, có một nghiệm thực.

Vì vậy, chúng tôi nhận được đáp số sau:
$$a \in ] -\infty; (4-2\sqrt{13})/3] \cup \cup\{-1\} \cup [(4+2\sqrt{13})/3; \infty[.$$
Ví dụ 3 (MIEM, 1982). Giải phương trình
$$|2x+2| = ax^2 + 4$$
(5)
và xác định các giá trị của $a$ mà nó có lời giải duy nhất.

Lời giải. Phương trình (5) tương đương với một bộ gồm hai hệ hỗn hợp:
$$\begin{cases} x < -1; \\ -2x - 2 = ax^2 + 4; \\ x \geqslant -1; \\ 2x + 2 = ax^2 + 4; \end{cases} \Leftrightarrow \begin{cases} x < -1; \\ ax^2 + 2x + 6 = 0; \\ x \geqslant -1; \\ ax^2 - 2x + 2 = 0. \end{cases}$$

⟦folio 44⟧

Khi tính đến $x \neq 0$, chúng ta thu được sự phụ thuộc $a=f(x)$, có các biểu thức tương tự khác nhau trên mỗi khoảng được sắp xếp:

$$a = (-2x - 6)/x^2 = f_1(x) \text{ при } x < -1 \text{ и } a = (2x - 2)/x^2 = f_2(x) \text{ при } x \geq -1.$$

Hãy vẽ đồ thị sự phụ thuộc này trong hệ tọa độ $xOa$ (hình 2). Đồ thị của hàm $f_1(x)$ và $f_2(x)$ lần lượt là các đường cong màu xanh lam và đỏ “đặc”. Sự kết hợp của những đường này là đồ thị $a=f(x)$. (Các đường cong chấm màu xanh lam và đỏ là đồ thị biểu thị sự phụ thuộc của $f_1(x)$ và $f_2(x)$ bên ngoài các khoảng mà chúng được rasterized. Các đường chấm chấm này được tìm thấy bên dưới khi chọn lời giải.) Các đường cong màu xanh lam và đỏ giao nhau tại điểm có tọa độ $(-1; -4)$.

Việc kiểm tra các hàm $f_1(x)$ và $f_2(x)$ cho thấy (như cũng có thể thấy trong hình 2) rằng $\max f_1(x) = f_1(-6) = \frac{1}{6}$ và $\max f_2(x) = f_2(2) = \frac{1}{2}$.

Trục hoành của các điểm tại đó đường thẳng song song với trục $Ox$ cắt đường liền nét là nghiệm của phương trình (5).

Từ hình đã cho và các nhận xét ở trên, suy ra phương trình (5) có:

a) Với $a \in ]-\infty; -4]$ có hai lời giải: $x_{1,2} = (1 \pm \sqrt{1-2a})/a$, được xác định từ phương trình

$$ax^2 - 2x + 2 = 0.$$

6) Tại $a \in ]-4; 0[$ có hai lời giải: $x_1 = (-1 + \sqrt{1-6a})/a$ và $x_2 = (1 - \sqrt{1-2a})/a$

Bàn

| Ý nghĩa của $a$ | Số lời giải | Lời giải |
| :--- | :--- | :--- |
| $a \in ]-\infty; -4]$ | hai | $x_{1,2} = (1 \pm \sqrt{1-2a})/a$ |
| $a \in ]-4; 0[$ | hai | $x_1 = (-1 + \sqrt{1-6a})/a; x_2 = (1 - \sqrt{1-2a})/a$ |
| $a=0$ | hai | $x_1 = -3$ và $x_2 = 1$ |
| $a \in ]0; 1/6[$ | bốn | $x_{1,2} = (-1 \pm \sqrt{1-6a})/a; x_{3,4} = (1 \pm \sqrt{1-2a})/a$ |
| $a=1/6$ | ba | $x_1 = -6; x_{2,3} = 6 \pm 2\sqrt{6}$ |
| $a \in ]1/6; 1/2[$ | hai | $x_{1,2} = (1 \pm \sqrt{1-2a})/a$ |
| $a=1/2$ | một | $x=2$ |
| $a \in ]1/2; \infty[$ | 0 | - |

⟦folio 46⟧

]1; ∞[, tức là khi
$$0 < a < a_m,$$
(12)

phương trình (11) có ba nghiệm. Điều này là do đối với các giá trị $a$ được chỉ ra trong (12), đường thẳng $y = ax$ cắt đồ thị của hàm $f(x)$ tại ba điểm: tại một điểm - một nhánh của đường cong trên khoảng ]0; 1[ và tại hai điểm - trên khoảng ]1; ∞[. Trục hoành của những điểm này sẽ là nghiệm của phương trình (11).

Có vẻ như đối với dương nhỏ $a$ thì đường thẳng $y = ax$ sẽ cắt nhánh của đồ thị hàm $f(x)$ trên khoảng ]1; ∞[ chỉ tại một điểm có trục hoành gần bằng một điểm. Nhưng ý kiến ​​​​này là sai. Người ta biết rằng khi $x$ tăng lên, hàm lũy thừa tăng nhanh theo logarit (“Đại số và Nguyên tắc Phân tích 9-10” 1980, đoạn 70, trang 214). Do đó, đối với bất kỳ $a > 0$ và bất kỳ giá trị hoành độ nhỏ nào, đường thẳng $y = ax$ sẽ cắt nhánh $f(x)$ hai lần tương ứng với khoảng ]1; ∞[.

Bây giờ chúng ta hãy xác định giá trị nào $a$ đường thẳng $y = ax$ chạm vào nhánh được đề cập.

Gọi $A(x_0, y_0)$ là điểm tiếp tuyến. Sau đó, giá trị mong muốn $a$ được tìm thấy từ hệ thống
$$\begin{cases} f(x_0) = g_a(x_0), \\ f'(x_0) = g'_a(x_0) \end{cases}$$ hoặc $$\begin{cases} \ln x_0 = ax_0, \\ \frac{1}{x_0} = a, \end{cases}$$

từ đâu $x_0 = 1/a$; $\ln(1/a) = 1 \Rightarrow a = e^{-1}$.

Vì vậy, $a_m = e^{-1}$. Do đó, với $a \in ]0; e^{-1}$[ phương trình (10) có ba nghiệm.

Các ví dụ được thảo luận trong bài viết có nội dung khác nhau. Trong lời giải một số chúng tôi đã sử dụng đồ thị để rõ ràng, trong khi một số khác chỉ được giải quyết bằng phương pháp phân tích.

Đồng thời, khi đã làm quen với các giải pháp được đưa ra, bạn đã có được một số kỹ năng mà bạn có thể áp dụng trong lời giải các ví dụ tương tự khác và đặc biệt là những ví dụ được đưa ra trong bài tập.

Bài tập
1 (MSU, Khimak, 1982). Với giá trị nào của tham số $p$ phương trình
$$(x - p)^2 \cdot [p(x - p)^2 - p - 1] = -1$$ có nhiều nghiệm dương hơn nghiệm âm không?
2 (LSU, Toán., 1979). Phương trình có bao nhiêu nghiệm?
$$(x + 2)e^{-x/2} - x^4/6 - x^8/20 = x^2 + 1$$

3 (NSU, cơ học, 1977). Xác định những giá trị nào của $a$ thì phương trình $\log_2(x + 1) = 1/2$ có một lời giải duy nhất.
4 (LSU, Toán., 1980). Với giá trị nào của tham số $a$ phương trình
$$\sin x \cdot \cos 2x \cdot \sin 3x = a$$ có chính xác hai nghiệm trên đoạn $[\pi/4; \pi/2]$?
5 (MSU, VMK, 1980). Với giá trị nào của tham số $a$ phương trình
$$(3a - 1)x^2 + 2ax + 3a - 2 = 0$$ có hai gốc thực không?
6 (MSU, cơ học, 1980). Với giá trị nào của tham số $a$ phương trình
$$4^{-|x - a|} \cdot \log_3(x^2 - 2x + 3) + 2^{-x^2 + 2x} \times \log_1/3(2|x - a| + 2) = 0$$ có chính xác ba gốc riêng biệt không?
7 (MSU, địa chất tổng quát, 1979). Tìm tất cả các giá trị của $a$ mà phương trình
$$x^2 + 6x/(\sqrt{\sin a} + 9\sqrt{3}/\cos a + 36) = 0$$ có một đĩa đơn lời giải.
8 (Đại học bang Ural, toán học, 1981). Với giá trị nào của tham số $a$ phương trình
$$\log_{\sqrt{ax - 6}}(2x^2 - 3x + 2) = 2\log_{ax - 6}(x^2 + 2x - 4)$$ có một lời giải không?
9 (MSU, Khimak, 1980). Tìm tất cả các giá trị như vậy của $k$, với mỗi giá trị đó số lời giải tương ứng với $x$ của phương trình
$$2x^3 + 6x = (3^6k - 9)\sqrt{2^8k - 1/6} - (3k - 1)^2 \cdot 12^x$$ không nhỏ hơn số lời giải so với phương trình $y$
$$3(5y^2 - k^4) - 2y = 2k^2(6y - 1).$$
10 (MEPhI, 1980). Tìm giá trị của $c$ mà phương trình
$$2\log_7(cx - 2) = \log_7(-x^2 - 9x - 18)$$ chỉ có một lời giải.
11 (MIEM, 1980). Tìm tất cả các phương trình lời giải cho $a = 1$
$$\sin(2(x - \pi)) - \sin(3x - \pi) = a \sin x$$ nằm trên đoạn $[0; \pi/2]$ và tìm ra những giá trị nào mà phương trình có lời giải duy nhất trên đoạn này.
12 (LETI, 1982). Cho một hàm $y = f(x)$, trong đó
$$f(x) = x^2 + x + 9/(x^2 + x + 1).$$ Với những giá trị nào thì $f(x) = a$ có 4 nghiệm?
13 (LETI, 1982). Phương trình có bao nhiêu nghiệm?
$$\log_2\sin x = x^2 - 36?$$
14 (LETI, 1982). Với những giá trị nào của $a$ phương trình
$$\sqrt{x + a} = x$$ có 2 gốc không?
15 (MISiS, 1983). Tại $a$ phương trình
$$|x + 2| - |2x + 8| = a^2$$ có một lời giải không?
16 (MISiS, 1983). Với những giá trị nào của tham số $a$ thì phương trình $|x^2 - 6x + 8| + |x^2 - 6x + 5| = a$ có nhiều hơn ba lời giải?
17 (MSU, VMK, 1983). Với mọi $a$, hãy giải phương trình
$$(x + 2)(x + 4) + 5(x + 2)\sqrt{\frac{x + 4}{x + 2}} = (a + 2)(a - 3).$$
