---
id: 1991-3-alekseev-kurlyandchik-summa-minimumov-i-minimum-summyi-4eb277f4
issue: kvant_1991_3
year: 1991
number: "3"
title: Số tiền tối thiểu và số tiền tối thiểu
authors:
  - Алексеев Р.
  - Курляндчик Л. Д.
rubric: matematicheskiy-kruzhok
rubric_sub: Математический кружок
page_first: 51
page_last: 53
page_labels: 49, 51
lang: vi
source: kvant_digital
extraction: vision
content_sha256: 989fffb2621032f934d3cb2f8626b2ca1e0a6e1a150d1d41063a0e26ac129dd8
prompt_sha256: draft-1
translated_from: content/ru/1991/03/articles/16_alekseev-kurlyandchik-summa-minimumov-i-minimum-summyi-4eb277f4.md
source_content_sha256: d44734c71d310315eace7ed1bc3e7f2c04120a36de3509418ad32267b4a4db3d
translation_model: draft
translation_run: vi-draft-gaps-2026-11-06
translation_quality: draft
---

⟦folio 49⟧

Số tiền tối thiểu và số tiền tối thiểu

R. ALEXEEV,
L. KURLYANDCHIK

Bài viết này sẽ thảo luận về một phương pháp chung mà bạn có thể chứng minh nhiều bất đẳng thức quan trọng. Ý tưởng ban đầu rất đơn giản. Hai hàm tùy ý $f(x)$ và $g(x)$, được xác định, chẳng hạn, trên một số đoạn $[a,b]$, đạt cực tiểu (nói chung) tại các điểm khác nhau (hình 1). Bất bình đẳng là công bằng

$$\min f(x)+\min g(x) \leqslant \min (f(x)+g(x)).$$

Hình 1.

⟦folio 51⟧

---
running_head:
folio:
---

6) $(a_1^p + \ldots + a_n^p)^p \cdot (b_1^q + \ldots + b_n^q)^q \geq a_1 b_1 + \ldots + a_n b_n$ nếu $p > 0$, $q > 0$ là các số giống với $\frac{1}{p} + \frac{1}{q} = 1$ (Bất đẳng thức Hölder).

Lời giải. Như thường lệ, chúng ta hãy xem các hàm $n$
$$f_1(x; y) = a_1 x + b_1 y,$$
$$f_n(x; y) = a_n x + b_n y.$$

Điều quan trọng nhất là chọn đúng bộ mà chúng ta xem xét chức năng của mình. Rốt cuộc, hàm của chúng ta được xác định trên mặt phẳng và chúng ta có thể tìm thấy cực tiểu trên bất kỳ hình nào!

a) Xét một đường tròn bán kính 1 có tâm ở gốc (hình 2). Hàm tuyến tính hình học $f(x; y) = ax + by$ có nghĩa là gì? Đây là tích vô hướng của các vectơ có tọa độ $(a; b)$ và $(x; y)$. Nhưng tích vô hướng là tích của độ dài của vectơ và coisine của góc giữa chúng. Cosin của góc là tối thiểu đối với các vectơ thẳng hàng và độ dài của vectơ $(x; y)$ không thay đổi nếu phần cuối của vectơ nằm trên đường tròn. Điều này có nghĩa là đạt được mức tối thiểu của hàm $f(x; y)$ trên một vectơ có tọa độ $(x_0; y_0)$, thẳng hàng $(a; b)$ (hình 3). Một vectơ như vậy bằng $(x_0; y_0) = \left( \frac{a}{\sqrt{a^2 + b^2}}; \frac{b}{\sqrt{a^2 + b^2}} \right)$ và tích vô hướng bằng $(x_0; y_0) \cdot (a; b) = \sqrt{a^2 + b^2}$.

Vì vậy, trong trường hợp đường tròn
$$\min (ax + by) = \sqrt{a^2 + b^2}.$$

Bây giờ chúng ta không mất gì để chứng minh bất đẳng thức a). Ở bên trái, nó chứa các giá trị tối thiểu của hàm $f_1, \ldots, f_n$

Hình 3.
trên vòng tròn và bên phải là tổng nhỏ nhất của chúng.

6) Chúng ta hãy lấy một tập hợp bao gồm các điểm $(x; y)$ mà
$$x^{\frac{1}{p}} \cdot y^{\frac{1}{q}} = 1.$$

Chúng ta hãy tìm giá trị nhỏ nhất của hàm $f(x; y) = ax + by$ trên tập hợp này. Tất nhiên, chúng tôi có thể giải quyết vấn đề này không đơn giản bằng bài toán phân tích (và khuyên độc giả nên thử làm điều này), nhưng may mắn thay, kho kiến ​​​​thức tích lũy của chúng tôi cho phép chúng tôi tránh được điều này. Hãy sử dụng bất đẳng thức b) từ Bài tập 3:

$$ax + by = \frac{1}{p} \cdot pax + \frac{1}{q} \cdot qby \geqslant \frac{1}{p} \cdot (qby)^{\frac{1}{q}} = (pa)^{\frac{1}{p}} \cdot (qb)^{\frac{1}{q}}.$$

Kiểm tra xem bất đẳng thức có đạt được không nếu $\frac{x}{y} = \frac{b}{a}$. Vì vậy, giá trị tối thiểu của hàm $f(x; y)$ trên tập hợp của chúng ta bằng $(pa)^{\frac{1}{p}} \cdot (qb)^{\frac{1}{q}}$. Nếu chúng ta đặt $a = \frac{c^p}{p}$, $b = \frac{d^q}{q}$ (tức là chúng ta lấy hàm tuyến tính $\frac{c^p}{p} x + \frac{d^q}{q} y$), thì mức tối thiểu này hóa ra bằng cd. Chà, điều gì sẽ xảy ra nếu chúng ta làm tương tự với từng chức năng của mình $f_1, \ldots, f_n$:

$$a_1 = \frac{c^p}{p}, b_1 = \frac{d^q}{q}, \ldots,$$

$$..., a_n = \frac{c^p}{p}, b_n = \frac{d^q}{q},$$

thì ta thu được bất đẳng thức Hölder!

Bây giờ hãy so sánh bất đẳng thức Cauchy-Bunyakovsky với bất đẳng thức

(Về phần kết xem trang 55)
