---
id: 1972-1-smyishlyaev-primenenie-neravenstva-bunyakovskogo-koshi-k-resheniyu-nekotoryih-zadach-4eddf0cd
issue: kvant_1972_1
year: 1972
number: "1"
title: Áp dụng bất đẳng thức Bunyakovsky–Cauchy cho lời giải của một số bài toán
authors:
  - Смышляев В. К.
rubric: matematicheskiy-kruzhok
rubric_sub: Математический кружок
page_first: 35
page_last: 37
page_labels: 33-35
tag: JGDA
lang: vi
source: kvant_digital
extraction: vision
content_sha256: 5717ce1439051bc9b94d88d8a6450f6ba626074159da7403588712c3a00d3140
prompt_sha256: draft-1
translated_from: content/ru/1972/01/articles/10_smyishlyaev-primenenie-neravenstva-bunyakovskogo-koshi-k-resheniyu-nekotoryih-zadach-4eddf0cd.md
source_content_sha256: 9b976d943064d630a31970e004510ea330f1ab265b10352048963699184178c8
translation_model: draft
translation_run: vi-draft-2026-10-31
translation_quality: draft
---

⟦folio 33⟧

Đối với lời giải nhiều bài toán toán học, cái gọi là bất đẳng thức Bunyakovsky-Cauchy được áp dụng

$$\sum_{i=1}^{n} a_i b_i \leq \sqrt{\sum_{i=1}^{n} a_i^2} \cdot \sqrt{\sum_{i=1}^{n} b_i^2} \quad (a_i > 0, b_i > 0).$$

Đầu tiên chúng ta hãy đưa ra một chứng minh nhỏ nhưng rất đơn giản về bất đẳng thức này. Giả sử $$\sqrt{\sum_{i=1}^{n} a_i^2} = A, \quad \sqrt{\sum_{i=1}^{n} b_i^2} = B.$$ Khi đó ta cần chứng minh rằng

$$\frac{\sum_{i=1}^{n} a_i b_i}{AB} \leq 1.$$

Sử dụng bất đẳng thức $xy \leq \frac{1}{2}(x^2+y^2)$, chúng ta viết số nguyên sau:

$$\frac{\sum_{i=1}^{n} a_i b_i}{AB} = \sum_{i=1}^{n} \left(\frac{a_i}{A} \cdot \frac{b_i}{B}\right) \leq$$

$$\leq \sum_{i=1}^{n} \frac{1}{2} \left[ \left(\frac{a_i}{A}\right)^2 + \left(\frac{b_i}{B}\right)^2 \right] = \frac{1}{2} \left( \frac{1}{A^2} \sum_{i=1}^{n} a_i^2 + \frac{1}{B^2} \sum_{i=1}^{n} b_i^2 \right) = 1.$$

Điều này hàm ý sự bất bình đẳng (*). Như đã biết, sự bình đẳng đạt được khi

$$\frac{a_1}{A} = \frac{b_1}{B}, \quad \frac{a_2}{A} = \frac{b_2}{B}, \dots, \quad \frac{a_n}{A} = \frac{b_n}{B},$$

tức là khi

$$\frac{a_1}{b_1} = \frac{a_2}{b_2} = \dots = \frac{a_n}{b_n}.$$

Bây giờ chúng ta hãy chỉ ra cách áp dụng bất đẳng thức (*).

⟦folio 34⟧

1. Tìm giá trị lớn nhất của hàm số
$$y = a \sin x + b \cos x$$
$$\left(a > 0, b > 0, 0 < x < \frac{\pi}{2}\right).$$

Lời giải. Do bất đẳng thức (*) ta có
$$y = a \sin x + b \cos x \leqslant \sqrt{a^2 + b^2} \cdot \sqrt{\sin^2 x + \cos^2 x} = \sqrt{a^2 + b^2}.$$
Đạt được giá trị lớn nhất trong điều kiện
$$\frac{a}{b} = \frac{\sin x}{\cos x},$$ tức là khi
$$tg x = \frac{a}{b}.$$

2. Máy biến áp loại biến đổi phải được thiết kế sao cho lõi sắt hình chữ thập của nó lấp đầy càng nhiều khoang bên trong của cuộn dây càng tốt. Kích thước mặt cắt ngang của lõi như trong hình sẽ là bao nhiêu nếu bán kính của cuộn dây là $R$?
Lời giải. Đặt $\Rightarrow AOB = \alpha$, sau đó
$$\frac{1}{4} S = y^2 - (y - x)^2 = 2xy - x^2 = R^2 \left(2 \sin \alpha \cos \alpha - \sin^2 \alpha\right).$$
Do đó $S = 2R^2 \left(2 \sin 2\alpha + \cos 2\alpha - 1\right)$. Hãy sử dụng bất đẳng thức (*):
$$S \leqslant 2R^2 \left(\sqrt{2^2 + 1^2} \cdot \sqrt{\sin^2 2\alpha + \cos^2 2\alpha} - 1\right) = 2R^2 \left(\sqrt{5} - 1\right).$$
Do đó, $S_{\max} = 2R^2 \left(\sqrt{5} - 1\right)$ đạt được tại
$$\frac{\sin 2\alpha}{\cos 2\alpha} = \frac{2}{1},$$ từ đâu $\alpha = \frac{1}{2}$ arctg 2.

3. Xét ba cặp số thực $(a_1, b_1), (a_2, b_2), (a_3, b_3)$. Chứng minh rằng tồn tại một tam giác có cạnh $a = \sqrt{(a_2 - a_3)^2 + (b_2 - b_3)^2}, \quad b = \sqrt{(a_3 - a_1)^2 + (b_3 - b_1)^2}, \quad c = \sqrt{(a_1 - a_2)^2 + (b_1 - b_2)^2}$.
Lời giải. Để $a, b$ và $c$ là các cạnh của một tam giác, cần phải thỏa mãn các bất đẳng thức $a + b > c, b + c > a, a + c > b$, mỗi bất đẳng thức đều tương đương với bất đẳng thức Bunyakovsky-Cauchy. Thật vậy, sự tương ứng $a + b \geqslant c$ tương đương với bất đẳng thức $2ab \geqslant c^2 - a^2 - b^2$ hoặc $2 \sqrt{(a_2 - a_3)^2 + (b_2 - b_3)^2} \cdot \sqrt{(a_3 - a_1)^2 + (b_3 - b_1)^2} \geqslant (a_1 - a_2)^2 + (b_1 - b_2)^2 - (a_2 - a_3)^2 - (b_2 - b_3)^2 - (a_3 - a_1)^2 - (b_3 - b_1)^2 = 2 \left[ (a_3 - a_1) (a_2 - a_3) + (b_3 - b_1) (b_2 - b_3) \right]$, giảm đi 2 ta thu được bất đẳng thức (*). Sự bình đẳng chỉ đạt được nếu các số $a_3 - a_1, b_3 - b_1$ tỷ lệ thuận với các số $a_2 - a_3, b_2 - b_3$; kiểm tra xem trong trường hợp này các đỉnh của tam giác có phải nằm trên cùng một đường thẳng hay không.
Có thể chứng minh theo cách tương tự rằng $a + c \geqslant b, b + c \geqslant a$. Điều này có nghĩa là tồn tại một hình tam giác có cạnh $a, b, c$, mặc dù nó có thể suy biến thành một đoạn. Bạn có thể dựng tam giác này về mặt hình học - trong hệ tọa độ Descartes, các đỉnh của nó phải được đặt tại các điểm có tọa độ $(a_1, b_1), (a_2, b_2), (a_3, b_3)$.

⟦folio 35⟧

Bài tập

1. Tìm giá trị lớn nhất của hàm số
   a) $y = a \sin x + b \sin \left( \frac{\pi}{3} + x \right) + c \sin \left( \frac{\pi}{3} - x \right) \left( a > 0, b > 0, c > 0, 0 < x < \frac{\pi}{3} \right)$;
   b) $z = a \sin (x + y) + b \sin (x - y) + c \sqrt{\cos 2x \cdot \cos 2y}$
      $(a > 0, b > 0, c > 0, 0 < x < \frac{\pi}{4}, 0 < y < \frac{\pi}{4})$;
   c) $u = a \cos x + b \cos y + c \cos z + d \sqrt{2 \cos x \cos y \cos z}$, trong đó $a, b, c, d$ là các số dương, $x, y, z$ là các góc còn lại của tam giác;
   d) $u = a \sin x + b \sin y + c \sin z + d \sin t + e \sqrt{2 \cos (x + y) \cdot \cos (y + z) \cdot \cos (z + x)}$, trong đó $a, b, c, d, e$ là số dương, $x + y + z + t = 2\pi$;
   e) $y = \frac{(a_1 x_1 + a_2 x_2 + \cdots + a_n x_n)^2}{x_1^2 + x_2^2 + \cdots + x_n^2}$ $(a_i > 0, x_i > 0)$.

2. Tìm giá trị lớn nhất và lớn nhất của hàm $u = \sum_{i=1}^{n} x_i y_i$, nếu biết $\sum_{i=1}^{n} x_i^2 \leq a^2$, $\sum_{i=1}^{n} y_i^2 \leq b^2$ và $a$ và $b$ là các số dương.

3. Chứng minh bất đẳng thức
   $$\sum_{i=1}^{n} \sqrt{x_i y_i} \leq \sqrt{\sum_{i=1}^{n} x_i} \sqrt{\sum_{i=1}^{n} y_i},$$
   trong đó tất cả $x_i$ và $y_i$ đều là số dương.

4. Chứng minh bất đẳng thức
   $$\left( \sum_{i=1}^{n} \sqrt{a_i b_i} \right)^2 \leq \sum_{i=1}^{n} a_i x_i \sum_{i=1}^{n} \frac{b_i}{x_i},$$
   trong đó tất cả $a_i, b_i, x_i$ đều là số dương.

5. Chứng minh bất đẳng thức
   $$\sum_{i=1}^{n} x_i y_i \sum_{i=1}^{n} \frac{x_i}{y_i} \geq \left( \sum_{i=1}^{n} x_i \right)^2,$$
   trong đó tất cả $x_i, y_i$ đều là số dương.

6. Một quả cầu có bán kính $R$ có hình trụ có bề mặt hoàn chỉnh nhất. Bán kính và chiều cao của nó là bao nhiêu?
7. Bên trong một tam giác, một điểm nhất định nằm sao cho tổng bình phương khoảng cách từ điểm đó đến cạnh của tam giác là nhỏ nhất. Hãy biểu diễn những khoảng cách này bằng độ dài các cạnh của tam giác và tìm điểm này.
8*) Diện tích các mặt của tam giác là $S_1, S_2, S_3$ và $S_4$. Điểm $M$ nằm bên trong tam giác với khoảng cách $h_1, h_2, h_3$ và $h_4$ (tương ứng) tính từ các mặt.
   a) Tại vị trí nào của điểm $M$ tổng
      $$\frac{S_1}{h_1} + \frac{S_2}{h_2} + \frac{S_3}{h_3} + \frac{S_4}{h_4}$$

có ý nghĩa nhất?
6) Chứng minh rằng mọi tam giác đều có ít nhất một điểm $M$ sao cho tổng (*) nhỏ nhất. Tìm xem có thể có bao nhiêu điểm như vậy.

*) bài toán này được gửi bởi độc giả G. Hovhannitsan của chúng tôi từ Yerevan.
