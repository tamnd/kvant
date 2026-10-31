---
id: 1986-7-dorofeev-kak-raspolozhenyi-korni-trehchlenov-32c2f6be
issue: kvant_1986_7
year: 1986
number: "7"
title: Các nghiệm của tam thức nằm ở đâu?
authors:
  - Дорофеев Г. В.
rubric: praktikum-abiturienta
rubric_sub: Практикум абитуриента
page_first: 47
page_last: 51
page_labels: 45-49
tag: NJRM
lang: vi
source: kvant_digital
extraction: vision
content_sha256: 5d9fda621828fbc90035d2740db8f59468d13daef1bc3ec438632b7626456a85
prompt_sha256: draft-1
translated_from: content/ru/1986/07/articles/14_dorofeev-kak-raspolozhenyi-korni-trehchlenov-32c2f6be.md
source_content_sha256: 18be7bc5aa3ab24cd06a0cbd77716483858a583c89a9c741cb3ec07b795ad859
translation_model: draft
translation_run: vi-draft-2026-10-31
translation_quality: draft
---

⟦folio 45⟧

Các nghiệm của tam thức nằm ở đâu?

Tiến sĩ Khoa học Vật lý và Toán học
G. V. DOROFEEV

Bài viết này dành cho lời giải bài toán, trong đó bằng cách này hay cách khác, câu hỏi được đặt ra về vị trí tương đối của các nghiệm (thường là vô tỷ) của hai tam thức vuông. Về nội dung toán học, những bài toán này khá đơn giản, nhưng xét từ góc độ tính toán, hầu hết chúng đều có những khó khăn nghiêm trọng. Ví dụ, hãy thử trả lời một câu hỏi.

Với giá trị nào của a là nghiệm của phương trình

$$x^2 + \frac{8}{a}x - 2a = 0 \quad \text{и} \quad x^2 + \frac{6}{a}x - a = 0$$

Các biến có khác nhau không (nghĩa là giữa hai nghiệm của một phương trình có đúng một nghiệm của phương trình kia)?

Bạn sẽ thấy rằng việc tính nghiệm của các tam thức này đòi hỏi phải so sánh chúng một cách tỉ mỉ với nhau đối với các giá trị khác nhau của tham số a.

Đồng thời, từ việc xem xét đồ họa, rõ ràng là nghiệm của hai tam thức vuông f(x) và g(x) có hệ số dương giống nhau tại x² (và các phân số dương) thay đổi khi và chỉ khi giao điểm của đồ thị của các hàm f(x) và g(x) nằm sau trục hoành. Trong ngôn ngữ đại số, điều này có nghĩa là tổng giá trị của các hàm f(x) và g(x) là âm. Trong trường hợp của chúng ta, f(x) = g(x) ⇔ x = \frac{a^2}{2} và f\left(\frac{a^2}{2}\right) = \frac{a^4}{4} + 2a; do đó các điều kiện bài toán thỏa mãn các bất đẳng thức lời giải a^4 + 8a < 0 hoặc -2 < a < 0.

Ví dụ này cho thấy vị trí tương đối của các nghiệm của hai tam thức vuông phụ thuộc vào hành vi của chúng tại điểm x₀, trong đó các tam thức này thuộc cùng một giá trị (điều quan trọng là điểm x₀ là điểm duy nhất!).

Sáu tiêu chí
cho những dịp khác nhau
vị trí gốc pas

Giả sử các tam thức bậc hai f(x) = ax² + px + q và g(x) = ax² + rx + s có hai nghiệm phân biệt (x₁, x₂ và x₃, x₄, tương ứng, x₁ > x₂,

⟦folio 46⟧

Hình 1.

Hình 2.

Hình 3.

Hình 4.

Hình 5.

Hình 6.

$x_3 > x_4$), $y(f(x))$ và $g(x)$ không có gốc chung và $p \neq r$. Đặt $x_0$ là nghiệm (duy nhất) của phương trình $f(x) = g(x)$. Khi đó khẳng định sau đây là đúng:

1. $x_2 < x_1 < x_4 < x_3 \Leftrightarrow \Leftrightarrow (f(x_0) > 0, f'(x_0) > 0, g'(x_0) < 0)$;
2. $x_2 < x_4 < x_1 < x_3 \Leftrightarrow \Leftrightarrow (f(x_0) < 0, f'(x_0) > g'(x_0))$;
3. $x_2 < x_4 < x_3 < x_1 \Leftrightarrow \Leftrightarrow (f(x_0) > 0, g'(x_0) [f'(x_0) - g'(x_0)] > 0)$;
4. $x_4 < x_2 < x_1 < x_3 \Leftrightarrow \Leftrightarrow (f(x_0) < 0, f'(x_0) [g'(x_0) - f'(x_0)] > 0)$;
5. $x_4 < x_2 < x_3 < x_1 \Leftrightarrow \Leftrightarrow (f(x_0) < 0, f'(x_0) < g'(x_0))$;
6. $x_4 < x_3 < x_2 < x_1 \Leftrightarrow \Leftrightarrow (f(x_0) > 0, f'(x_0) < 0, g'(x_0) > 0)$.

Các tuyên bố được liệt kê được minh họa trong Hình 1-6. Nếu bạn quên cách diễn đạt của một tiêu chí nào đó, đó không phải là vấn đề lớn: bạn luôn có thể khôi phục tiêu chí đó và sử dụng các bản vẽ sau. Cũng dễ dàng nhận thấy rằng tiêu chí 4, 5, 6 được lấy từ tiêu chí 3, 2, 1 với các biến $f(x)$ và $g(x)$ hoán đổi cho nhau (điều này cũng có thể thấy được khi so sánh hình tương ứng). Vì vậy, chúng ta sẽ chỉ chứng minh ba tiêu chí đầu tiên.

Chúng ta sẽ cần các tính chất nổi tiếng (rất hữu ích) sau đây của tam thức bậc hai:

nếu $f(x)$ là một tam thức bậc hai có hệ số dẫn đầu dương và phân biệt, $x_1$ và $x_2$ là nghiệm của nó và $x_0$ là một giá trị nào đó của biến, thì

$x_0 < x_2 < x_1 \Leftrightarrow (f(x_0) > 0, f'(x_0) < 0)$;
$x_2 < x_1 < x_0 \Leftrightarrow (f(x_0) > 0, f'(x_0) > 0)$;
$x_2 < x_0 < x_1 \Leftrightarrow f(x_0) < 0$,

(xem hình 7).

Hãy để bây giờ $h(x) = f(x) - g(x)$. Dễ dàng nhận thấy $h(x)$ là hàm tuyến tính khác với hằng số ($p \neq r$). Vì vậy, nó có tính đơn điệu (giảm hoặc tăng). Điều này có nghĩa là nếu đối với một số $a < b$ thì bất đẳng thức $h(a) < h(b)$ (hoặc $h(a) > h(b)$) đúng, thì đối với bất kỳ $c < d$ nào thì bất đẳng thức $h(c) < h(d)$ (hoặc $h(c) > h(d)$) đúng.

⟦folio 47⟧

Bằng chứng tiêu chí 1

Sự cần thiết (⇒). Hãy để $x_2 < x_1 < x_4 < x_3$. Sau đó $f(x_4) > 0$, $h(x_4) = f(x_4) - g(x_4) = f(x_4) > 0$. Tương tự như vậy $g(x_1) > 0$, và do đó $h(x_1) < 0$.

Từ bất đẳng thức $x_1 < x_4$ và $h(x_1) < h(x_4)$ ta thu được $h(x)$ là hàm tăng.

Vì $h(x_0) = 0$, chúng ta có $h(x_1) < h(x_0) < h(x_4)$, do đó $x_1 < x_0 < x_4$. Vì vậy, cả hai nghiệm $f(x)$ đều nhỏ hơn $x_0$, do đó $f(x_0) > 0$, $f'(x_0) > 0$. Tương tự, cả hai nghiệm $g(x)$ đều lớn hơn $x_0$, do đó $g'(x_0) < 0$. Sự cần thiết của tiêu chí 1 đã được chứng minh. Đủ rồi (⇔). Đặt $f(x_0) > 0$, $f'(x_0) > 0$, $g'(x_0) < 0$. Từ hai bất đẳng thức đầu tiên, suy ra rằng cả hai nghiệm $f(x)$ đều nhỏ hơn $x_0$, và từ các bất đẳng thức $g(x_0) > 0$, $g'(x_0) < 0$, cả hai nghiệm $g(x)$ đều lớn hơn $x_0$, và do đó $x_2 < x_1 < x_0 < x_4 < x_3$.

Bằng chứng tiêu chí 2

Sự cần thiết (⇒). Hãy để $x_2 < x_4 < x_1 < x_3$. Khi đó $f(x_4) < 0$, $g(x_1) < 0$, vì vậy $h(x_4) < 0 < h(x_1)$, và vì $x_4 < x_1$, chúng ta thấy rằng $h(x)$ là hàm tăng. Do đó, $h'(x) > 0$ đối với bất kỳ $x$ nào, cụ thể là $h'(x_0) > 0$, từ đó $f'(x_0) > g'(x_0)$.

Mặt khác, từ điều kiện $h(x_4) < h(x_1)$, chúng ta thu được $x_4 < x_0 < x_1$, do đó $x_2 < x_0 < x_1$, từ đó $f'(x_0) > g'(x_0)$.

Mặt khác, từ điều kiện $h(x_4) < h(x_1)$, chúng ta thu được $x_4 < x_0 < x_1$, do đó $x_2 < x_0 < x_1$, từ đó $f'(x_0) > g'(x_0)$.

Đủ rồi (⇔). Đặt $f(x_0) < 0$, $f'(x_0) > g'(x_0)$. Khi đó $h'(x_0) > 0$ và vì $h'(x)$ là hàm hằng, $h'(x) > 0$ với mọi $x$, tức là $h(x)$ là hàm tăng.

Từ điều kiện $f(x_0) = g(x_0) < 0$, chúng ta thu được $x_2 < x_0 < x_1$, $x_4 < x_0 < x_3$ và vì $h(x)$ trả về, $0 = h(x_0) < h(x_1)$, $h(x_4) < h(x_0) = 0$, từ đó $g(x_1) = f(x_1) - h(x_1) < 0$, $f(x_4) = h(x_4) + g(x_4) < 0$;

do đó, $x_4 < x_1 < x_3$, $x_2 < x_4 < x_1$, tức là $x_2 < x_4 < x_1 < x_3$.

Bằng chứng về tiêu chí 3

Sự cần thiết (⇒). Hãy để $x_2 < x_4 < x_3 < x_1$. Sau đó $g(x_1) > 0$, $g(x_2) > 0$, từ đó $h(x_1) < 0$, $h(x_2) < 0$, và do đó, trên khoảng $[x_2; x_1]$ hàm tuyến tính $h(x)$ không biến mất, do đó $x_0 < x_2 < x_1$ hoặc $x_0 < x_2 < x_1$.

Nếu $x_0 < x_2 < x_1$ thì $x_0$ nằm trong khoảng giảm dần của ba số hạng chung nên $f'(x_0) < 0$, $g'(x_0) < 0$. Ngoài ra, $h(x_0) > h(x_2)$, vì vậy $h(x)$ là hàm giảm, $h'(x) < 0$ với mọi $x$ và đặc biệt là $h'(x_0) < 0$, tức là $f'(x_0) - g'(x_0) < 0$. Do đó tích số $g'(x_0)|f'(x_0) - g'(x_0)|$ là dương.

Trường hợp $x_2 < x_1 < x_0$ cũng được xử lý tương tự.

Đủ rồi (⇔). Đặt $f(x_0) > 0$ và trước tiên giả sử rằng $g'(x_0) > 0$, $f'(x_0) - g'(x_0) > 0$. Khi đó cả hai nghiệm $g(x)$ đều nhỏ hơn $x_0$, tức là $x_4 < x_3 < x_0$. Ngoài ra, $h(x)$ là hàm trả về, vì vậy $h(x_4) < x_3 < h(x_0)$, do đó $f(x_4) < 0$, $f(x_3) < 0$. Do đó, $x_2 < x_4 < x_1$, $x_2 < x_3 < x_1$, tức là $x_2 < x_4 < x_1 < x_3$.

Trường hợp $g'(x_0) < 0$, $f'(x_0) - g'(x_0) < 0$ xử lý tương tự.

Lời giải bất bình đẳng

Việc áp dụng các tiêu chí đã được chứng minh trong nhiều trường hợp giúp đơn giản hóa các bất đẳng thức lời giải. Sau đó, chuyển sang các ví dụ cụ thể, biểu thức $f'(x_0) - g'(x_0)$ thực sự hoạt động

Hình 8.

cổ ở tiêu chí 2-5, bằng chênh lệch $p - r$. Vì vậy, trong thực tế chẳng hạn, sẽ thuận tiện hơn khi sử dụng tiêu chí 2 ở dạng $(f(x_0) < 0, p > r)$.

Bây giờ chúng ta hãy giải một số bất đẳng thức.

1. $(x^2 + 13x - 49)(x^2 + 14x - 50) > 0$. Ký hiệu $f(x) = x^2 - 13x - 49$, $g(x) = x^2 + 14x - 50$, chúng ta dễ dàng tìm được $x_0 = 1$, $f(1) = -35$, và vì $13 < 14$ (xem tiêu chí 5) nên gốc của ba số hạng này có quan hệ với nhau bởi các bất đẳng thức $x_4 < x_2 < x_3 < x_1$. Áp dụng phương pháp tích phân (xem «Kvant», số 12, 1985, trang 18 và hình 8), ta tìm được lời giải của bất đẳng thức này: $x < x_4$, $x_2 < x < x_3$, $x > x_1$, hoặc viết ra nghiệm, $x < -7 - 3\sqrt{11}, -\frac{13 + \sqrt{365}}{2} < x < -7 + 3\sqrt{11}, x > \frac{\sqrt{365} - 13}{2}$.

2. $(x^2 + 6x - 11) < -2x^2 - 13x + 24$. Chúng ta hãy viết lại bất đẳng thức này dưới dạng $2x^2 + 13x - 24 < x^2 + 6x - 11 < -2x^2 - 13x + 24$.

Do đó, chúng ta phải giải hệ bất đẳng thức $f(x) < 0$, $g(x) < 0$, trong đó

$$f(x) = 3x^2 + 21x - 39,$$

$$g(x) = 3x^2 + 19x - 35$$

(chúng ta sẽ nhân ba số $f(x)$ với 3 để cân bằng các hệ số dẫn đầu $f(x)$ và $g(x)$).

Chúng ta có: $x_0 = 2$, $f(2) > 0$, $g'(2) > 0$, $p - r > 0$ và (xem tiêu chí 3) $x_2 < x_4 < x_3 < x_1$. Do đó, nghiệm của hệ $f(x) < 0$, $g(x) < 0$, và do đó của bất đẳng thức ban đầu, là giá trị $x_4 < x < x_3$, tức là $-\frac{19 + \sqrt{781}}{2} < x < \frac{\sqrt{781} - 19}{2}$.

3. $(x^2 + 6x - 11) \leq |2x^2 + 13x - 26|$.

Vì cả hai vế của bất đẳng thức đều không âm, nên sau khi bình phương nó có thể được viết là $(x^2 + 6x - 11)^2 \leq (2x^2 + 13x - 26)^2$, và bằng cách chuyển mọi thứ sang vế phải và phân tích hiệu các bình phương, chúng ta thu được bất đẳng thức $f(x)g(x) \geq 0$, trong đó

⟦folio 48⟧

Hình 9.

$$f(x) = 3x^2 + 21x - 45,$$
$$g(x) = 3x^2 + 19x - 37.$$

Sau đó $x_0 = 4$, $f(4) > 0$, $g'(4) > 0$, $p - r > 0$ và một lần nữa theo tiêu chí 3 $x_2 < x_4 < x_3 < x_1$. Áp dụng phương pháp tích phân, ta thu được lời giải của bất đẳng thức ban đầu (xem hình 9):

$$x \leq -\frac{7 + \sqrt{109}}{2}, -\frac{19 + \sqrt{805}}{6} \leq x \leq \frac{\sqrt{805} - 19}{6}, x \geq \frac{\sqrt{109} - 7}{2}.$$

4. $$\frac{x^2 - x - 4}{4 - |3x^2 - 2x - 7|} \leq 0.$$

Hãy nhân cả hai vế của bất đẳng thức này với biểu thức dương $(4 + |3x^2 - 2x - 7|)^{-1}$. Đã nhân tử hóa hiệu của các bình phương thành mẫu số, sau khi đơn giản hóa chúng ta thu được bất đẳng thức

$$\frac{x^2 - x - 4}{(3x^2 - 2x - 3)(3x^2 - 2x - 11)} \geq 0.$$

Đặt $f(x) = 3x^2 - 3x - 12$, $g(x) = 3x^2 - 2x - 3$, $h(x) = 3x^2 - 2x - 11$, chúng ta sẽ tìm ra vị trí tương đối của rễ $x_{1,2}, x_{3,4}, x_{5,6}$.

Các hệ số cho $x y$ của trilen $g(x)$ và $h(x)$ bằng nhau nên tiêu chí của chúng tôi không áp dụng được. Tuy nhiên, tình huống này thậm chí còn đơn giản hóa lời giải. Thật vậy, $h(x) = g(x) - 8$, vậy $h(x_{3,4}) = g(x_{3,4}) - 8 = -8 < 0$, và do đó các nghiệm $g(x)$ nằm giữa các nghiệm $h(x)$, tức là

$$x_6 < x_4 < x_3 < x_5.$$

Đối với ba thấu kính $f(x)$ và $g(x)$, chúng ta có $x_0 = -9$, $f(-9) > 0$, $f'(-9) < 0$, $g'(-9) < 0$, $-3 < -2,$

$$x_2 < x_4 < x_3 < x_1.$$

Do đó, $x_6 < x_2 < x_4 < x_3 < x_5$, và do đó, bất đẳng thức lời giải (xem hình 10) là:

$$x < \frac{1 - \sqrt{34}}{3}, \frac{1 - \sqrt{17}}{2} \leq x < \frac{1 - \sqrt{10}}{3},$$

$$\frac{1 + \sqrt{10}}{3} < x < \frac{1 + \sqrt{34}}{3}, x \geq \frac{1 + \sqrt{17}}{2}.$$

5. $(x^2 + 2x + 4 - a)(x^2 - 2x - a) < 0.$

Hãy đặt $f(x) = x^2 + 2x + 4 - a$, $g(x) = x^2 - 2x - a$. Lưu ý rằng nếu phân biệt của một trong các trilen này là âm thì trilen này dương với tất cả $x$ và với các giá trị tương ứng của $a$ thì bất đẳng thức này là bậc hai. Những trường hợp được coi là đại diện cho độc giả và chúng tôi sẽ giả định rằng cả hai trường hợp phân biệt đối xử đều dương tính, đúng với $a > 3$. Sau đó, $f(x)$ và $g(x)$, mỗi cái có hai gốc khác nhau $x_{1,2}$ và $x_{3,4}$. Trong trường hợp này, $x_0 = -1$, $f(-1) = 3 - a < 0$, $2 > -2$ và theo tiêu chí 2 $x_2 < x_4 < x_1 < x_3$. Do đó, với $a > 3$ nghiệm của bất đẳng thức này là (xem hình 11)

$$-1 - \sqrt{a - 3} < x < 1 - \sqrt{a + 1},$$

$$-1 + \sqrt{a - 3} < x < 1 + \sqrt{a + 1}.$$

Hoàn thành bất đẳng thức lời giải có tính đến các giá trị “đặc biệt” của tham số $a = 3$ và $a = -1$ (khi một trong các phân biệt đối xử bằng 0) được viết là: cho $a \leq -1$ lời giải không; với $-1 < a < 3$ chúng ta nhận được $1 - \sqrt{a + 1} < x < 1 + \sqrt{a + 1}$; với $a > 3$ chúng ta nhận được $-1 - \sqrt{a - 3} < x < 1 - \sqrt{a + 1},$

$$-1 + \sqrt{a - 3} < x < 1 + \sqrt{a + 1}.$$

6. Tại giá trị nào của a thì hệ bất đẳng thức

$$2x^2 - 3ax - 9 \leq 0, x^2 + ax - 2 \geq 0$$

có lời giải?

Lưu ý rằng mỗi trilen vuông

$$f(x) = 2x^2 - 3ax - 9$$

Và

$$g(x) = 2x^2 + 2ax - 4$$

có hai gốc khác nhau, và

$$f(x) \leq 0 \Leftrightarrow x_2 \leq x \leq x_1,$$

$$g(x) \geq 0 \Leftrightarrow x \leq x_4$$ hoặc $x \geq x_3$.

⟦folio 49⟧

Để một hệ nhất định có lời giải thì điều cần và đủ là đoạn $[x_2; x_1]$ phải có ít nhất một điểm chung với một trong các tia $|-\infty; x_4|$ và $[x_3; +\infty]$. Điều này đúng (không tính đến khả năng có các nghiệm trùng nhau) trong tất cả các tiêu chí của chúng tôi ngoại trừ tiêu chí thứ tư: hệ thống không có lời giải khi và chỉ khi $x_4 < x_2 < x_1 < x_3$.

Vì $f(x) = g(x) \Leftrightarrow ax = -1$, nên với $a \neq 0$ chúng ta có $x_0 = -\frac{1}{a}$,

$$f\left(-\frac{1}{a}\right) = \frac{2}{a^2} - 6, \quad f'\left(-\frac{1}{a}\right) = -\frac{4}{a} - 3a,$$

$$g'\left(-\frac{1}{a}\right) = -\frac{4}{a} + 2a$$

và theo tiêu chí 4 thì hệ bất đẳng thức phải được thỏa mãn

$$2 - 6a^2 > 0, \quad -\left(\frac{4}{a} + 3a\right) 5a > 0.$$

Có thể dễ dàng xác minh rằng hệ thống này không có lời giải, do đó không có giá trị "xấu" $a \neq 0$, nghĩa là đối với bất kỳ $a \neq 0$ nào hệ thống này có lời giải. Vì tại $a = 0$ nó cũng có lời giải nên nghiệm của bài toán 6 đều là các giá trị của $a$.

7. Với những giá trị nào của a thì tập lời giải của hệ bất đẳng thức $x^2 + 2x + a + 1 \geq 0, x^2 + x + 2a - 1 \leq 0$ đại diện cho một đoạn có độ dài 1? Phân biệt trilen

$$f(x) = x^2 + 2x + a + 1 \quad \text{и} \quad g(x) = x^2 + x + 2a - 1$$

lần lượt bằng $-4a$ và $5 - 8a$, do đó với $a > 5/8$ hệ đã cho không có lời giải và với $0 < a < 5/8$ nó tương đương với bất đẳng thức $g(x) \leq 0$ và được thỏa mãn trên khoảng $[x_4; x_3]$. Từ điều kiện

$$x_3 - x_4 = 1 \Leftrightarrow \sqrt{5 - 8a} = 1 \Leftrightarrow a = 1/2$$

và vì $0 < 1/2 < 5/8$, chúng ta thấy rằng $a = 1/2$ là nghiệm của bài toán.

Tại $a = 0$ và tại $a = 5/8$ nghiệm của hệ là nghiệm tương ứng tại $x_1 - x_2 = 1$, từ đó tìm thấy $a = -1$. Đáp số: $a = -1$ và $a = 1/2$.

Lưu ý rằng tiêu chí 1-6 không áp dụng cho trường hợp trilene $f(x)$ và $g(x)$ có chung một gốc. Trong thực tế, theo quy luật, tốt hơn nên coi các trường hợp trùng khớp gốc riêng biệt là "đặc biệt".

Bài tập.
Giải các bất đẳng thức:

1. $|x^2 + 10x + 5| < |2x^2 + 21x + 8|$.
2. $|x - a| < 3x - x^2 - 1$.
3. $16a^3x^4 - 8a^2x^2 + 16x + a - 4 \geq 0$ ($a > 0$).
4. Giải hệ bất phương trình $3x^2 + 2kx - k - 1 \leq 0$ ($k = 1, 2, \dots, 10$).
