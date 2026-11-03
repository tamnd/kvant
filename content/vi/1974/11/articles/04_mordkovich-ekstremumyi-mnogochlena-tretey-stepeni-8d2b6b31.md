---
id: 1974-11-mordkovich-ekstremumyi-mnogochlena-tretey-stepeni-8d2b6b31
issue: kvant_1974_11
year: 1974
number: "11"
title: Cực trị của đa thức bậc ba
authors:
  - Мордкович А. Г.
rubric: osnovnye-stati
page_first: 10
page_last: 12
page_labels: 8-10
tag: NU4P
lang: vi
source: kvant_digital
extraction: vision
content_sha256: 6f35b9bb14cfad6a53c102743bb2f56792e7cc9a3760dea74468b4a54db94508
prompt_sha256: draft-1
translated_from: content/ru/1974/11/articles/04_mordkovich-ekstremumyi-mnogochlena-tretey-stepeni-8d2b6b31.md
source_content_sha256: e2a2f8ee39b85c52880236241828a4a73a75c81e1abfc889cb4ea6e20ee5e849
translation_model: draft
translation_run: vi-draft-2026-11-03
translation_quality: draft
---

⟦folio 8⟧

Cực trị của đa thức bậc ba

Bài viết này là bài thứ tư trong loạt bài viết về hàm bậc ba và phương trình *) Sẽ tập trung vào việc tìm điểm cực đại và cực tiểu của hàm $y = ax^3 + bx^2 + cx + d$

Đầu tiên chúng ta cùng xem hàm $y = ax^2 + bx + c$ (1)
$(a \neq 0)$. Đặt $x = \alpha$ là nghiệm của hàm (1). Đồ thị của hàm số này trông như thế nào trong một lân cận khá nhỏ của điểm $x = \alpha$?

Có bốn trường hợp có thể xảy ra ở đây - chúng được trình bày trong Hình 1-4. Trong trường hợp thứ nhất và thứ hai, chúng ta nói rằng hàm số đơn điệu tại điểm $x = \alpha$ (trong trường hợp đầu tiên nó tăng, trong trường hợp thứ hai nó tắt). Trong trường hợp thứ ba và thứ tư, hàm số được cho là có cực trị tại điểm $x = \alpha$

*) Xem các bài: V. G. Yankelevich, vụ 《Irreducible》, 《Kvant》, 1971, số 11; O. A. Zhautykov, Đồ thị sự kiện tứ giác, 《Kvant》, 1972, số 6; O. A. Zhautykov, Về ranh giới của nghiệm của phương trình bậc ba, 《Kvant》, 1973, số 12.

(trong trường hợp thứ ba - tối thiểu, trong trường hợp thứ tư - tối đa)*.

Sự khác biệt cơ bản giữa trường hợp thứ nhất và thứ hai so với trường hợp thứ ba và thứ tư là gì? Thực tế là trong hai trường hợp đầu tiên, hàm đổi dấu khi đi qua điểm $x = \alpha$ (ví dụ: trong trường hợp đầu tiên $y < 0$ tại $x < \alpha$ và $y > 0$ tại $x > \alpha$;

*) Đôi khi người ta nói rằng một hàm có cực trị cục bộ (cực đại, cực tiểu). 《Địa phương》có nghĩa là “cục bộ”: ở một số vùng lân cận của điểm $x = \alpha$, các giá trị của hàm không vượt quá $f(\alpha)$, mặc dù “xa” so với điểm $x = \alpha$ các giá trị $f(x)$ có thể vượt quá $f(\alpha)$. Theo thuật ngữ mà chúng tôi đã sử dụng (xem thêm B. E. Weitz, I. T. Demidov, Đại số và phần đầu của phân tích, lớp 9, sách giáo khoa chuyên nghiệp do học giả A. N. Kolmogorov biên tập, § 69), một hàm số có thể có nhiều cực đại và cực tiểu, được định nghĩa là các khái niệm cục bộ.

Hình 1. Hình 2. Hình 3. Hình 4.

⟦folio 9⟧

ở đây, các giá trị của $x$ được chọn đủ gần điểm $x = \alpha$) và trong hai trường hợp cuối, hàm không đổi dấu khi đi qua điểm $x = \alpha$.

Hãy thử tìm điều kiện cần và đủ để điểm $x = \alpha$ nghiệm của đa thức $y = ax^2 + bx + c$ là điểm cực trị. Chúng ta hãy biến đổi hàm (1) thành dạng

$$y = a (x - \alpha)(x - \beta)$$

($\alpha$ và $\beta$ là nghiệm của một tam giác vuông; hãy thử chứng minh rằng nếu $x = \alpha$ là nghiệm của hàm số (1) thì nó có thể được biểu diễn dưới dạng trong đó $\beta$ là số thực).

Nếu $\alpha \neq \beta$, thì trong một lân cận đủ nhỏ của điểm $x = \alpha$ (tại $|x - \alpha| < |\alpha - \beta|$), biểu thức $a (x - \beta)$ giữ nguyên dấu, nghĩa là hàm $y = a (x - \alpha) \times (x - \beta)$ đổi dấu khi đi qua điểm $x = \alpha$. Trong trường hợp này không có cực trị. Nếu $\alpha = \beta$, thì chúng ta nhận được $y = a (x - \alpha)^2$; hàm này không đổi dấu khi đi qua điểm $x = \alpha$.

Vì vậy, căn bậc ba của một tam giác vuông là điểm cực trị của mô hình và số mol của mô hình khi căn bậc này gấp đôi.

Tổng quát hóa kết quả thu được như sau:

Định lý 1. Để điểm $x = \alpha$ là điểm cực trị của hàm số $y = ax^2 + bx + c$ thì điều cần và đủ là tồn tại một số lớn nhất $m$ mà đa thức $ax^2 + bx + c - m$ có nghiệm kép $x = \alpha$.

Để chứng minh định lý này, chỉ cần biết điểm $x = \alpha$ khi và chỉ khi hàm $y = f(x) - m$, trong đó $m = f(\alpha)$, có cực trị tại điểm này.

Kết quả này được sử dụng trong thực tế.

Ví dụ 1. Tìm điểm cực trị của hàm số

$$y = ax^2 + bx + c.$$

Hãy chọn các số $\alpha, m$ sao cho đồng nhất thức

$$ax^2 + bx + c - m = a (x - \alpha)^2.$$

Chúng tôi có

$$ax^2 + bx + c - m = ax^2 - 2a\alpha x + a\alpha^2.$$

Nhưng hai đa thức cũng bằng nhau khi và chỉ khi các hệ số của chúng bằng nhau với cùng lũy ​​thừa; do đó ta được hệ phương trình

$$\begin{cases} -2a\alpha = b, \\ a\alpha^2 = c - m, \end{cases}$$

từ đó nó nằm

$$\alpha = -\frac{b}{2a}, \quad m = \frac{4ac - b^2}{4a}.$$

Vì vậy, $x = -\frac{b}{2a}$ là điểm cực trị của hàm $y = ax^2 + bx + c$ (và điểm cực đại cục bộ, nếu $a > 0$, và cực tiểu cục bộ, nếu $a < 0$).

Bây giờ chúng ta hãy nhìn vào chức năng

$$y = ax^3 + bx^2 + cx + d.$$

Dưới đây chúng tôi sẽ chứng minh rằng có thể xây dựng và chứng minh một định lý tương tự như Định lý 1. Nhưng trước tiên chúng tôi sẽ chứng minh một số kết quả phụ trợ.

Bổ đề. Cho một đa thức bậc $y = ax^3 + bx^2 + cx + d$ ($a \neq 0$) và lấy $x = \alpha$ là nghiệm thực của nó. Sau đó

$$ax^3 + bx^2 + cx + d = a (x - \alpha)(x^2 + px + q),$$

$p$ và $q$ cũng là một số số thực.

Bằng chứng. Trong điều kiện $a\alpha^3 + b\alpha^2 + c\alpha + d = 0$.

Sau đó

$$ax^3 + bx^2 + cx + d = (ax^3 + bx^2 + cx + d) - (a\alpha^3 + b\alpha^2 + c\alpha + d) = a (x^3 - \alpha^3) + b (x^2 - \alpha^2) + c (x - \alpha) = (x - \alpha) [ax^2 + (a\alpha + b) x + (a\alpha^2 + b\alpha + c)] = a (x - \alpha)(x^2 + px + q),$$

Ở đâu

$$p = \frac{a\alpha + b}{a}, \quad q = \frac{a\alpha^2 + b\alpha + c}{a}.$$

⟦folio 10⟧

Bây giờ chúng ta thử tìm điều kiện cần và đủ để điểm $x = \alpha$ nghiệm của đa thức (2) là điểm cực trị của hàm số $y = ax^3 + bx^2 + cx + d$.

Hãy sử dụng công thức (3). Nếu $x = \alpha$ không phải là nghiệm của tam thức bình phương $x^2 + px + q$, thì trong một lân cận đủ nhỏ của điểm $x = \alpha$ tam thức này giữ nguyên dấu và do đó hàm $y = a(x - \alpha)(x^2 + px + q)$ đổi dấu khi đi qua điểm $x = \alpha$. Điều tương tự cũng xảy ra khi $x = \alpha$ là căn bậc hai của một tam thức, tức là $x^2 + px + q = (x - \alpha)^2$ và do đó $y = a(x - \alpha)^3$. Trong các trường hợp được xem xét, không có cực trị. Và chỉ trong một trường hợp, hàm số không đổi dấu khi truyền điểm $x = \alpha$ - khi $x = \alpha$ là căn bậc một của tam thức bình phương, tức là $x^2 + px + q = (x - \alpha)(x - \beta)$, hoặc, giống nhau, $x = \alpha$ là căn bậc hai của đa thức (2), tức là

$$y = a(x - \alpha)^2(x - \beta),$$

ở đâu $\alpha \neq \beta$.

Vì vậy, nghiệm của một đa thức có bậc là điểm cực trị và nốt ruồi của nó khi nghiệm này gấp đôi.

Kết quả thu được được tóm tắt như sau:

Định lý 2. Để điểm $x = \alpha$ là điểm cực trị của hàm số $y = ax^3 + bx^2 + cx + d$, điều cần và đủ là tồn tại bất kỳ số $m$ nào mà đa thức $P(x) = ax^3 + bx^2 + cx + d$ có nghiệm kép $x = \alpha$, tức là

$$P(x) = a(x - \alpha)^2(x - \beta),$$

(4)

thức ăn $\alpha \neq \beta$.

Định lý 3 (điều kiện đủ để đạt cực đại và cực tiểu). Giả sử hàm $y = ax^3 + bx^2 + cx + d$ có cực trị tại điểm $x = \alpha$ và $m$ là giá trị của hàm tại điểm $x = \alpha$. Hãy biểu diễn đa thức $P(x) = ax^3 + bx^2 + cx + d$ dưới dạng (4). Khi đó, nếu $a(\beta - \alpha) > 0$ thì $x = \alpha$ là điểm tối đa; nếu $a(\beta - \alpha) < 0$ thì $x = \alpha$ là điểm tối thiểu.

Bằng chứng. Nếu $a > 0$ và $\alpha < \beta$, thì trong vùng lân cận của điểm $x = \alpha$, không chứa điểm $x = \beta$ (hình 5), chúng ta có $P(x) \leq 0$, tức là $y \leq m$. Điều này có nghĩa là $x = \alpha$ là điểm tối đa. Nếu $a < 0$ và $\alpha > \beta$ thì cũng đạt được điểm tối đa. Kết hợp hai trường hợp này, ta thấy rằng nếu $a(\beta - \alpha) > 0$ thì tại điểm $x = \alpha$ hàm $y$ có ​​cực đại. Phần thứ hai của định lý được chứng minh theo cách tương tự.

Ví dụ 2. Xét hàm số cực trị

$$y = x^3 - 3x^2 - 9x + 5$$

(5)

và âm mưu nó.

Hãy thử chọn các số $m$, $\alpha$, $\beta$ sao cho đồng nhất thức $x^3 - 3x^2 - 9x + 5 - m = (x - \alpha)^2 \times (x - \beta)$ giữ nguyên (và $\alpha \neq \beta$). Do đó $x^3 - 3x^2 - 9x + 5 - m = x^3 - (\beta + 2\alpha)x^2 + (2\alpha\beta + \alpha^2)x - \alpha^2\beta$. Để tìm các giá trị của $m$, $\alpha$, $\beta$ ta nhận được hệ phương trình:

$$\begin{align*}
\alpha_1 &= -1, \quad \beta_1 &= 5, \quad m_1 &= 10; \\
\alpha_2 &= 3, \quad \beta_2 &= -3, \quad m_2 &= -22.
\end{align*}$$

Hình 5.
