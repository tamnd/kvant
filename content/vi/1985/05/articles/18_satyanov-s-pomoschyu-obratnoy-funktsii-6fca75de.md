---
id: 1985-5-satyanov-s-pomoschyu-obratnoy-funktsii-6fca75de
issue: kvant_1985_5
year: 1985
number: "5"
title: Sử dụng hàm nghịch đảo
authors:
  - Сатьянов П. Г.
rubric: shkola-v-kvante
page_first: 36
page_last: 38
page_labels: 34-36
tag: VBS0
lang: vi
source: kvant_digital
extraction: vision
content_sha256: 8460416cc0a575a72577ce4134164b552f7e89d76b456c59304d119cf0aa78cb
prompt_sha256: draft-1
translated_from: content/ru/1985/05/articles/18_satyanov-s-pomoschyu-obratnoy-funktsii-6fca75de.md
source_content_sha256: e6ee95742c568a747d9781af4ba53003806ccbfdd572ead446dbed2783f61c10
translation_model: draft
translation_run: vi-draft-2026-10-31
translation_quality: draft
---

⟦folio 34⟧

Toán 10

Sử dụng hàm nghịch đảo

Ở trường, tích phân được tính bằng công thức Newton-Leibniz. Cách tính tích phân theo cách này

$$I_1 = \int_0^1 \arcsin x \, dx,$$

bạn cần biết nguyên hàm của hàm $\arcsin x$, nhưng bạn không biết điều đó. Cuộc sống thế nào?

Chúng ta hãy chuyển sang ý nghĩa hình học của tích phân: tích phân là diện tích. Cụ thể, $I_1$ là diện tích của vùng được bao quanh bởi hình 1 màu xanh lam. Chúng ta hãy tìm diện tích này là hiệu giữa diện tích của hình chữ nhật tương ứng và diện tích $\sigma_1$ của “vùng màu vàng”. Vì đồ thị của hàm $\arcsin x$ là đồ thị “đảo ngược” (thu được bằng cách đối xứng quanh đường $y=x$) của hàm $\sin x$, nên diện tích $\sigma_1$ bằng diện tích dưới hình sin $x=\sin y$ trong vùng thay đổi $y$ từ 0 đến $\frac{\pi}{2}$:

$$\sigma_1 = \int_0^{\frac{\pi}{2}} \sin y \, dy = -\cos y \Big|_0^{\frac{\pi}{2}} = 1.$$

Vì vậy, $I_1 = \frac{\pi}{2} - 1$.

Bây giờ chúng ta tính tích phân

$$I_2 = \int_a^b \ln x \, dx \quad (1<a<b).$$

Chúng ta hãy nhìn lại hình (hình 2). Lần này "diện tích màu xanh" $I_2$ bằng diện tích của "hình chữ nhật lớn" trừ đi diện tích của "hình chữ nhật nhỏ" và diện tích $\sigma_2$ của "khu vực màu vàng". Đồ thị hàm số $\ln x$ là đồ thị “ngược” của hàm nghịch đảo $e^x$, do đó $\sigma_2$ là diện tích nằm dưới đồ thị hàm số $x=e^y$ trong vùng biến đổi $y$ từ $\ln a$ đến $\ln b$:

$$\sigma_2 = \int_a^b e^y \, dy = e^y \Big|_a^b = b-a.$$

⟦folio 35⟧

Vì vậy, $I_2 = b \cdot \ln b - a \times \ln a - (b - a) = b \cdot \ln \frac{b}{e} - a \cdot \ln \frac{a}{e}$.

Chúng ta đã hai lần biểu thị vô số của một hàm nào đó (arcsin $x$, ln $x$) dưới dạng vô số của hàm nghịch đảo ($\sin x, e^x$).

$$\ln x \text{ и } e^x - \text{ взимно-образные функции. Но arcsin } x \text{ и sin } x - \text{ не взимно-образные функции (sin } x - \text{ не обратная функция); взимно-образными являются arcsin } x \text{ и sin } x, \text{ рассматриваемый на отрезке } \left[ -\frac{\pi}{2}; \frac{\pi}{2} \right], \text{ или, как говоря математики, } cy\text{ значение функции sin } x \text{ на отрезок } \left[ -\frac{\pi}{2}; \frac{\pi}{2} \right].$$

Điều này không thể được thực hiện trong trường hợp chung? Ví dụ: nếu đồ thị của hàm $f$ có dạng giống như trên hình 3 và hàm $g$ là nghịch đảo của $f$ trên $[a; b]$, thì từ hình 3

$$\int_a^b f(x)dx = b \cdot f(b) - a \cdot f(a) - \int_a^b g(y)dy. \quad (1)$$

Không, nếu đồ thị của hàm $f$ có dạng như trong Hình 4, a hoặc 4, 6 thì đẳng thức (1) không thể thu được từ hình. Liệu nó có còn đúng không? Nếu đúng thì chứng minh thế nào?

Không rõ cách chứng minh đẳng thức (1) cho một khoảng. Hãy thử chứng minh phát biểu tương ứng về sai phân thứ nhất. Lưu ý ở (1) $b$ đến $x$:

$$\int_a^b f(t)dt =$$

$$= x \cdot f(x) - a \cdot f(a) - \int_a^b g(y)dy \quad (2)$$

(để đơn giản, chúng tôi cũng thay thế biến nội bộ hóa $x$ bằng $t$; các giá trị bên trong rất độc lập với chỉ định của biến nội bộ hóa:

$$\int_a^b f(x)dx = \int_a^b f(t)dt = \int_a^b f(z)dz = \dots).$$

Như đã biết, hàm $\int_a^b f(t)dt$ là nguyên hàm của hàm liên tục $f$ (“Đại số và Nguyên tắc Phân tích 9-10”, bài toán 1046). Do đó, nếu đẳng thức (2) đúng thì hàm

$$x \cdot f(x) - a \cdot f(a) - \int_a^b g(y)dy,$$

hoặc, cái gì giống nhau, khác với nó bởi một hằng số hàm

$$\Phi(x) = x \cdot f(x) - \int_a^b g(y)dy, \quad (3)$$

cũng sẽ là nguyên hàm của $f$.

Để kiểm tra xem điều này có đúng hay không, chúng ta cần lấy đạo hàm vế phải của đẳng thức (3). Do đó, chúng tôi yêu cầu hàm $f$ phải khả vi.

Hàm $\int_a^b g(y)dy$, nằm ở vế phải của đẳng thức (3), là sự kết hợp của hàm $z = f(x)$ và hàm $\int_a^b g(y)dy$. Bởi vì

$$\left( \int_a^b g(y)dy \right)' = g(z), \quad (4)$$

theo quy luật phân biệt thành phần

$$\left( \int_a^b g(y)dy \right)' = g(f(x)) \cdot f'(x).$$

Vì hàm $g$ là nghịch đảo của $f$, $g(f(x)) = x$. Kể từ đây,

$$\left( \int_a^b g(y)dy \right)' = x \cdot f'(x).$$

Posetom

⟦folio 36⟧

Xét Định lý 1, sử dụng công thức Newton-Leibniz, chúng ta thu được

$$\int_{a}^{b} f(x)dx = \Phi(x) \Big|_{a}^{b} =$$

$$= [x \cdot f(x) - \int_{a}^{x} g(y)dy] \Big|_{a}^{b} =$$

$$= b \cdot f(b) - \int_{a}^{b} g(y)dy -$$

$$- a \cdot f(a) + \int_{a}^{b} g(y)dy =$$

$$= b \cdot f(b) - a \cdot f(a) - \int_{a}^{b} g(y)dy,$$

Q.E.D.

Ví dụ: hàm $y = \frac{1}{1+\sqrt{x}}$ khả vi và khả nghịch bởi ]0; +∞[ (hình 5). Dễ dàng tính được rằng nghịch đảo của nó sẽ là hàm $x = \left(\frac{1}{y} - 1\right)^2 (0 < y \leq 1)$. Đó là lý do tại sao

$$\int_{0}^{1} \frac{dx}{1+\sqrt{x}} = \frac{1}{2} - \int_{1}^{1/2} \left(\frac{1}{y} - 1\right)^2 dy =$$

$$= \frac{1}{2} + \int_{1/2}^{1} \left(\frac{1}{y} - 1\right)^2 dy =$$

$$= \frac{1}{2} + \int_{1/2}^{1} \left(\frac{1}{y^2} - \frac{2}{y} + 1\right)dy =$$

$$= \frac{1}{2} + \left(-\frac{1}{y} - 2 \ln y + y\right) \Big|_{1/2}^{1} = 2 \ln \frac{e}{2}.$$

Mục đích chính của bài viết này là cho thấy việc tạo một bản vẽ và tích hợp các khái niệm hình học tương tự có thể hữu ích như thế nào (cố gắng “mở” công thức (1) mà không cần vẽ!). Để diễn giải những câu nói nổi tiếng của Caesar, ý tưởng này có thể được diễn đạt như sau: “Đã vẽ, đã cưa, đã chứng minh!”

Bài tập.
2. Tìm nguyên hàm trên [1; +∞[ cho hàm $a) y = \sqrt{x^2 - 1} + x, 6) y = \sqrt{x^2 - 1}$.
3. Tính a) $\int_{-1}^{0} \arcsin \sqrt{x} dx,$ b) $\int_{0}^{1} \sqrt{\frac{x}{x+1}} dx$.

P. G. SATYANOV
