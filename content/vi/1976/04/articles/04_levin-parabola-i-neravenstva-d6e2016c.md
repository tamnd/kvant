---
id: 1976-4-levin-parabola-i-neravenstva-d6e2016c
issue: kvant_1976_4
year: 1976
number: "4"
title: Parabol và bất đẳng thức
authors:
  - Левин В.
rubric: osnovnye-stati
page_first: 16
page_last: 20
page_labels: 14, 15, 16, 18
tag: 70UH
lang: vi
source: kvant_digital
extraction: vision
content_sha256: da62522840eced3327abadab76a238076a08fd752d2554dd15e27e3d42f814d6
prompt_sha256: draft-1
translated_from: content/ru/1976/04/articles/04_levin-parabola-i-neravenstva-d6e2016c.md
source_content_sha256: 8dfdce4c1d0101a47924301d5af41c652c0193f3c03324a2b61d04a02d585a8b
translation_model: draft
translation_run: vi-draft-2026-10-31
translation_quality: draft
---

⟦folio 14⟧

V. Levin

Parabol và bất đẳng thức

Tổ tiên của tất cả các bất đẳng thức giống hệt nhau là bình phương của bất kỳ số thực nào đều không âm: $x^2 \geq 0$. Thực tế này cũng có thể được xây dựng theo cách này: đồ thị của hàm $y = x^2$ (parabol) không vượt qua trục abscissa (Hình 1). Dấu bằng trong bất đẳng thức $x^2 \geq 0$ chỉ xảy ra tại $x = 0$ (parabol $y = x^2$ tiếp xúc với trục x tại gốc tọa độ).

Trong lưu ý này, chúng ta sẽ nói về cách xây dựng các bất đẳng thức phức tạp hơn dựa trên bất đẳng thức cơ bản này.

1. Xét tam thức bậc hai

$$y = Ax^2 + 2Bx + C, \quad A \neq 0;$$

đồ thị của nó cũng là một parabol. Hãy tìm điều kiện cần và đủ để thỏa mãn bất đẳng thức với mọi giá trị thực của $x$

$$Ax^2 + 2Bx + C \geq 0. \quad (1)$$

Những điều kiện này được tìm thấy rất dễ dàng. Đầu tiên, điều cần thiết là $A$ phải dương, vì đối với $A < 0$ luôn có các giá trị ​$x$ mà bất đẳng thức (1) không phụ thuộc (điều này tất nhiên là rõ ràng, từ thực tế là đối với $A < 0$ parabol hoặc cắt trục hoành hoặc mọi thứ đều nằm bên dưới trục). Lấy ví dụ: $x = x_0 = m + \sqrt{m^2 + m}$, trong đó $m$ được chọn

Hình 1.

⟦folio 15⟧

Hình 2.

$$AC = B^2, \text{ и именно при } x = -\frac{B}{A} \text{ (рис. 2 и 3).}$$

2. Hãy lấy số thực tùy ý

$$a_1, a_2, \dots, a_N; b_1, b_2, \dots, b_N; N \geqslant 1,$$

và một số $x$, rồi viết bất đẳng thức hiển nhiên sau:

$$(a_1x + b_1)^2 + (a_2x + b_2)^2 + \dots + (a_Nx + b_N)^2 \geqslant 0. \tag{3}$$

Nó có thể được viết lại thành $Ax^2 + 2Bx + C \geqslant 0,$

Ở đâu

$$A = a_1^2 + a_2^2 + \dots + a_N^2,$$

$$B = a_1b_1 + a_2b_2 + \dots + a_Nb_N,$$

$$C = b_1^2 + b_2^2 + \dots + b_N^2.$$

Giả sử rằng không phải tất cả $a_n$ ($n = 1, 2, \dots, N$) đều bằng 0. Sau đó chúng ta có thể phát biểu rằng $A > 0$.

Vì chúng ta biết rằng bất đẳng thức (3) phải đúng với mọi giá trị thực $x$, nên theo điều kiện $AC \geqslant B^2$, phải có

$$(a_1^2 + a_2^2 + \dots + a_N^2) \times (b_1^2 + b_2^2 + \dots + b_N^2) \geqslant (a_1b_1 + a_2b_2 + \dots + a_Nb_N)^2. \tag{4}$$

Rõ ràng, bất đẳng thức này đúng, với dấu bằng và khi $a_1 = a_2 = \dots = a_N = 0$, vì vậy chúng ta có thể loại bỏ yêu cầu rằng ít nhất một $a_n$ phải khác 0.

Bất đẳng thức (4) gọi là bất đẳng thức Cauchy (Augustin Louis Cauchy (1789–1857) – một nhà văn nổi tiếng người Pháp

⟦folio 16⟧

Hình 4.

thì bất đẳng thức Cauchy đơn giản nhất (5) được biểu diễn dưới dạng
$$|\vec{a}|^2 \cdot |\vec{b}|^2(\cos \alpha \cos \beta + \sin \alpha \sin \beta)^2 \leqslant \frac{|\vec{a}|^2 \cdot |\vec{b}|^2}{c_1^2}, \dots, \frac{|\vec{a}|^2 \cdot |\vec{b}|^2}{c_N^2}.$$
nghĩa là, $\cos^2\varphi \leqslant 1$, trong đó $\varphi = |\alpha - \beta|$ là góc giữa vectơ $\vec{a} = (a_1, a_2)$ và $\vec{b} = (b_1, b_2)$.

Trong trường hợp $N > 2$ tùy ý, bất đẳng thức (K) cũng có thể được viết là $\cos^2\varphi \leqslant 1$ bằng cách đặt góc $\varphi$ một cách thích hợp giữa hai vectơ $(a_1, a_2, \dots, a_N)$ và $(b_1, b_2, \dots, b_N)$ trong không gian $N$ chiều.

3. Bất đẳng thức Cauchy có rất nhiều ứng dụng. Chúng ta sẽ sử dụng nó để suy ra những bất đẳng thức khác phức tạp hơn một chút.

Xét hai dãy: dãy $a_1, a_2, \dots, a_N$ và dãy $c_1, c_2, \dots, c_N$ với các số hạng khác 0.

Theo bất đẳng thức (K) ta có
$$(a_1 + a_2 + \dots + a_N)^2 = \left(a_1 c_1 \cdot \frac{1}{c_1} + a_2 c_2 \cdot \frac{1}{c_2} + \dots + a_N c_N \cdot \frac{1}{c_N}\right)^2 \leqslant \left(a_1^2 c_1^2 + a_2^2 c_2^2 + \dots + a_N^2 c_N^2\right) \left(\frac{1}{c_1^2} + \frac{1}{c_2^2} + \dots + \frac{1}{c_N^2}\right).$$
Hãy đặt
$$\frac{1}{c_1^2} + \frac{1}{c_2^2} + \dots + \frac{1}{c_N^2} = C_N,$$
và viết bất đẳng thức (6) dưới dạng
$$(a_1 + a_2 + \dots + a_N)^2 \leqslant C_N \left(a_1^2 c_1^2 + a_2^2 c_2^2 + \dots + a_N^2 c_N^2\right).$$
(7)

Dấu bằng trong (7) đúng khi và chỉ nếu các chuỗi $a_1 c_1, a_2 c_2, \dots, a_N c_N$ và $\frac{1}{c_1}, \frac{1}{c_2}, \dots, \frac{1}{c_N}$ tỷ lệ thuận (dễ dàng thấy rằng điều này tương đương với các chuỗi tỷ lệ mạnh $a_1, a_2, \dots, a_N$ và $\frac{1}{c_1^2}, \frac{1}{c_2^2}, \dots, \frac{1}{c_N^2}$).

Hệ số $C_N$ trong bất đẳng thức (7) được gọi là hằng số bất đẳng thức *).

Các bất đẳng thức thú vị nhất thuộc loại (7) là những bất đẳng thức có hằng số nhỏ hơn một số nhất định $C$ với mọi $N$: $C_N < C$. Điều này sẽ đúng nếu có giới hạn

$$\lim_{N \to \infty} C_N = \lim_{N \to \infty} \left(\frac{1}{c_1^2} + \frac{1}{c_2^2} + \dots + \frac{1}{c_N^2}\right) = C,$$
nghĩa là, nếu một chuỗi vô hạn
$$\frac{1}{c_1^2} + \frac{1}{c_2^2} + \dots + \frac{1}{c_N^2} + \dots = \sum_{n=1}^{\infty} \frac{1}{c_n^2}$$
hội tụ đến tổng $C^*$.

Ví dụ. Hãy đặt $c_n = n$, $n = 1, 2, \dots, N$.

Khi đó bất đẳng thức (7) sẽ có dạng $(a_1 + a_2 + \dots + a_N)^2 \leqslant C_N \left(a_1^2 + 2^2 a_2^2 + 3^2 a_3^2 + \dots + N^2 a_N^2\right)$ (8)
với hằng số
$$C_N = 1 + \frac{1}{2^2} + \dots + \frac{1}{N^2}.$$

*) Một hằng số vì $C_N$ giống nhau đối với tất cả các chuỗi $a_1, a_2, \dots, a_N$.

**) Về giới hạn, xem bài viết của M. Gerver “20 bài toán về giới hạn”, “Quant”, 1974, số 3; về chuỗi vô hạn - một bài viết của cùng tác giả “Từ việc thay đổi vị trí của các số hạng ...”, “Quant”, 1974, số 9.

⟦folio 18⟧

trong đó $\alpha_n$ là các giá trị của góc giữa các đoạn $OM_{n-1}$ và $OM_n$, $n = 1, 2, \dots, N$.
Vì vậy, chúng ta có thể viết đẳng thức
$$t = \sqrt{t^2 + (n-1)^2} \quad \sqrt{t^2 + n^2} \sin \alpha_n$$
từ đó
$$\sin \alpha_n = \frac{t}{\sqrt{t^2 + (n-1)^2} \sqrt{t^2 + n^2}} > \frac{t}{t^2 + n^2},$$
đó là
$$\frac{t}{t^2 + n^2} < \sin \alpha_n, n = 1, 2, \dots, N.$$
Sau đó
$$C_N = \frac{t}{t^2 + 1} + \frac{t}{t^2 + 2^2} + \dots$$
$$\dots + \frac{t}{t^2 + N^2} < \alpha_1 + \alpha_2 + \dots$$
$$\dots + \alpha_N < \frac{\pi}{2},$$
và chúng ta nhận được sự bất bình đẳng
$$(a_1 + a_2 + \dots + a_N)^2 < \frac{\pi}{2} \left( tP + \frac{1}{t} Q \right),$$
hợp lệ cho mọi giá trị dương của $t$.

Hãy đặt $t = \sqrt{\frac{Q}{P}}$; với lựa chọn $tP + \frac{1}{t} Q = 2\sqrt{PQ}$ này, và chúng ta thu được bất đẳng thức Carlson thường được viết dưới dạng
$$(a_1 + a_2 + \dots + a_N)^4 < \pi^2 (a_1^2 + a_2^2 + \dots + a_N^2) (a_1^2 + 2^2 a_2^2 + \dots + N^2 a_N^2).$$

Bất đẳng thức này đúng với mọi $N \geqslant 1$; nó có thể được mở rộng thành chuỗi vô hạn. Trong bất đẳng thức này CONSTANTA $\pi^2$ —

*) Đạo hàm của bất đẳng thức Carlson được trình bày ở đây (ngoại trừ ước lượng cơ bản $C_N$) thuộc về nhà toán học nổi tiếng người Anh Godfrey Harold Hardy (1877-1947).

chính xác, nhưng chúng tôi không thể cung cấp một bằng chứng đơn giản về thực tế này.

Độ chính xác của hằng số thu được $\pi^2$ trong bất đẳng thức Carlon có nghĩa là ước lượng cơ bản ở trên $C_N$ xét về góc $\alpha_n$ không quá thô.

Bất đẳng thức Carlon có nhiều khái quát hóa. Chúng tôi chỉ trình bày hai trong số chúng mà không có bằng chứng (dấu hiệu $\Sigma$ có nghĩa là tổng theo $n$ từ 1 đến $N$ hoặc một chuỗi vô hạn, tức là tổng theo $n$ từ 1 đến $\infty$):
$$(\Sigma a_n)^6 < 54 (\Sigma a_n^2) (\Sigma na^2) (\Sigma n^2 a_n^2),$$
$$(\Sigma a_n)^15 < 300 000 (\Sigma a_n^3) \times (\Sigma na^3) (\Sigma n^2 a_n^3) (\Sigma n^4 a_n^3).$$

Trong những bất đẳng thức này, CONSTANTS 54 và theo đó, 300.000 là chính xác. Trong thực tế
1. Cho phép
$$a_1^2 + a_2^2 + \dots + a_n^2 = 1$$
$$b_1^2 + b_2^2 + \dots + b_n^2 = 1.$$
Trong giới hạn nào là ý nghĩa của biểu thức
$$a_1 b_1 + a_2 b_2 + \dots + a_n b_n?$$
2. Chứng minh rằng với mọi số dương $a_1, a_2, \dots, a_n$
$$(a_1 + a_2 + a_3 + \dots + a_k)^2 \leqslant k (a_1^2 + a_2^2 + \dots + a_k^2).$$
Khi nào sự bình đẳng được quan sát?
4. Chứng minh rằng với $a_1, \dots, a_k, b_1, \dots, b_k$ không âm:
$$\sqrt{a_1 b_1} + \sqrt{a_2 b_2} + \dots + \sqrt{a_k b_k} \leqslant \sqrt{a_1 + a_2 + \dots + a_k} \times \sqrt{b_1 + b_2 + \dots + b_k}.$$
5. Bất đẳng thức Holder.
Đặt $p > 1$ và $\frac{1}{p} + \frac{1}{q} = 1$ ($p$ và $q$ là các số hữu tỉ dương). Chứng minh rằng
$$a_1 b_1 + a_2 b_2 + \dots + a_k b_k \leqslant \left( a_1^p + a_2^p + \dots + a_k^p \right)^{\frac{1}{p}} \times \left( b_1^q + b_2^q + \dots + b_k^q \right)^{\frac{1}{q}}.$$
