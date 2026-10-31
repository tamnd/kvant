---
id: 1973-2-vaguten-chisla-cnk-mnogochlenyi-posledovatelnosti-6d842221
issue: kvant_1973_2
year: 1973
number: "2"
title: Số C_n^k, đa thức, dãy
authors:
  - Вагутен В. Н.
rubric: osnovnye-stati
page_first: 29
page_last: 34
page_labels: 27-32
tag: WEA5
lang: vi
source: kvant_digital
extraction: vision
content_sha256: a5089e528f7190ce4e225c9a6e2f09e405394e6ad96041827e31d5874638dffb
prompt_sha256: draft-1
translated_from: content/ru/1973/02/articles/07_vaguten-chisla-cnk-mnogochlenyi-posledovatelnosti-6d842221.md
source_content_sha256: 33c13a6eb39ad91f30cbc5e0c1681727c040b26fd1acea92251da62a900a4cc6
translation_model: draft
translation_run: vi-draft-2026-10-31
translation_quality: draft
---

⟦folio 27⟧

Số $C_n^k$, đa thức, dãy
(nhiều cách tiếp cận một bài toán)
V. N. Vagumen

Chúng ta hãy nhớ lại một bài toán từ “Bài toán «Kvant», lời giải cơ bản được viết bằng «Kvant» Số 12 cho năm 1972.

M138. Chứng minh rằng nếu $m$ và $n$ là số hạng của số $1 < m < n$ thì

$$\sum_{k=1}^{n} (-1)^k k^m C_k^k = 0,$$

$C_k^k$ của nó là các hệ số sinh học.

Những cách chứng minh khác nhau về những điểm này sẽ là cơ hội tốt để chúng tôi giới thiệu với bạn đọc một số khái niệm và sự kiện toán học quan trọng chưa có trong chương trình học ở trường (vi phân hữu hạn, công thức nội suy cho đa thức, đa thức tùy ý, chuỗi lũy thừa của số mũ). Theo các định nghĩa và lý thuyết trong mỗi đoạn văn, người đọc sẽ bắt gặp dòng chữ “bây giờ chúng ta hãy quay lại bài toán của mình”, theo sau là một lời giải bài toán M138 mới.

Việc chứng minh các định lý có thể được bỏ qua, nhưng tốt hơn là nên phân tích chúng, mặc dù điều này không dễ thực hiện vì chúng được viết rất ngắn gọn.

Giới thiệu. Hệ số sinh học và công thức bài toán

Chúng tôi liệt kê một số thuộc tính của số $C_n^k$. Mỗi thuộc tính 0,1-0,3 có thể được lấy để xác định những con số này.

0,1. $C_n^k$ — hệ số đa thức

$$(a + x)^n = C_n^0 a^n + C_n^1 a^{n-1} x + \dots + C_n^k a^{n-k} x^k + \dots + C_n^n x^n.$$

0,2. $C_n^0 = 1; C_n^n = 1$; cho mỗi $k = 1,2, \dots, n - 1$

$$C_n^k = C_{n-1}^{k-1} + C_{n-1}^k.$$

0,3. Đối với tất cả $n$ và $k$ ($0 \leqslant k \leqslant n$)

$$C_n^k = \frac{n(n-1)\dots(n-k+1)}{1 \cdot 2 \cdot \dots \cdot k},$$ hoặc $C_n^k = \frac{n!}{k!(n-k)!},$

ở đâu $m! = 1 \cdot 2 \cdot 3 \dots m; \quad 0! = 1! = 1$.

Bài tập 0. a) Tìm các số $C_n^k$ cho mọi $n$ từ 1 đến 10, sử dụng từng định nghĩa 0,1, 0,2, 0,3. b) In 0,2 từ 0,1, sử dụng tokdev $(a + x)^n = (a + x)^{n-1}(a + x)$. b) Rút ra 0,3 từ 0,2, sử dụng quy nạp toán học

⟦folio 28⟧

tsini (nghĩa là kiểm tra xem nếu công thức (3) đúng với $n-1$ thì nó cũng đúng với $n$).
d) Kiểm tra xem $C_n^k = C_n^{n-k}$.

Đa thức $a + x$ đôi khi được gọi là “nhị thức” (bin giống như double), công thức (1) là công thức của “nhị thức Newton” và các số $C_n^k$ là “hệ số nhị thức”.

Chúng ta đặt $a$ bằng 1 trong đẳng thức (1). Chúng tôi có được

$$(1 + x)^n = C_n^0 + C_n^1 x + \dots + C_n^k x^k + \dots + C_n^n x^n.$$

Thay $x = -1$ vào đây, ta được

$$C_n^0 - C_n^1 + C_n^2 - \dots + (-1)^k C_n^k + \dots + (-1)^n C_n^n = 0.$$

Hóa ra, ngoài sự tương ứng (5), các đẳng thức sau đây cũng đúng với các số $C_n^k$:

$$- C_n^1 + 2 C_n^2 - 3 C_n^3 + \dots + (-1)^n n C_n^n = 0,$$
$$- C_n^1 + 2^2 C_n^2 - 3^2 C_n^3 + \dots + (-1)^n n^2 C_n^n = 0,$$
$$- C_n^1 + 2^{n-1} C_n^2 - 3^{n-1} C_n^3 + \dots + (-1)^n n^{n-1} C_n^n = 0.$$

Chính những đẳng thức này cần được chứng minh trong bài toán M138; chúng sẽ được thảo luận ở cuối mỗi đoạn văn.

Trong tương lai, chúng tôi sẽ thường sử dụng ký hiệu ngắn về số lượng bằng biểu tượng $\Sigma$. Ví dụ, công thức (1) có thể được viết ngắn gọn như sau:

$$(a + x)^n = \sum_{k=0}^{k=n} C_n^k a^{n-k} x^k,$$
công thức (4) $-(1 + x)^n = \sum_{k=0}^{k=n} C_n^k x^k,$
đẳng thức (5) $-\sum_{k=0}^{k=n} (-1)^k C_n^k = 0$ và cuối cùng là đẳng thức (6), cần được chứng minh trong bài toán M138 -

$$\sum_{k=1}^{k=n} (-1)^k k^m C_n^k = 0$$

cho mọi $m < n$ tự nhiên.

§ 1. Dãy số và sai phân hữu hạn

Cho tập hợp các số nguyên không âm 0, 1, 2, 3... có hàm $f$. Điều này có nghĩa là trình tự được đưa ra

$$f(0), f(1), f(2), f(3), \dots$$

Tất nhiên, nếu từ mỗi thành viên của chuỗi $f$, ngoại trừ thành viên đầu tiên, chúng ta trừ đi thành viên trước của chuỗi, thì chúng ta thu được một chuỗi mới - một chuỗi khác biệt

$$f(1) - f(0), f(2) - f(1), f(3) - f(2), \dots$$

Chúng ta hãy biểu thị hàm tương ứng bằng $\Delta f$: $\Delta f(0) = f(1) - f(0);$
$\Delta f(1) = f(2) - f(1);$ $\Delta f(2) = f(3) - f(2) \dots$

Nếu chúng ta thực hiện thao tác tương tự - chuyển đổi từ $f$ sang $\Delta f$ - với chuỗi $\Delta f$, thì chúng ta sẽ có được chuỗi

$$f(2) - 2f(1) + f(0), f(3) - 2f(2) + f(1), \dots$$

Hãy biểu thị nó bằng $\Delta^2 f$.

⟦folio 29⟧

Chuỗi này được gọi là chuỗi sai phân thứ hai của $f$. Hãy làm rõ lại một lần nữa, chúng ta nhận được chuỗi khác biệt thứ ba - $\Delta^3 f$:

$$f(3) - 3f(2) + 3f(1) - f(0), f(4) - 3f(3) + 3f(2) - f(1), \dots$$

và vân vân.

Như vậy, theo định nghĩa

$$\Delta^{n+1}f(x) = \Delta^n f(x + 1) - \Delta^n f(x).$$

(7)

(Hãy nhớ rằng đối số $x$ của các hàm $f$, $\Delta f$, $\Delta^2 f$, ... nhận các giá trị nguyên không âm: $x = 0, 1, 2, \dots$).

Ví dụ đầu tiên, hãy xem xét hàm hằng $f$:

$$f(0) = f(1) = f(2) = \dots = a.$$

Đối với nó, chuỗi khác biệt $\Delta f$ rõ ràng sẽ chỉ bao gồm các số 0. Hãy viết ngắn gọn như thế này: $\Delta f \equiv 0$ (với tất cả $x$).

Đương nhiên, các chuỗi $\Delta^2 f$, ..., $\Delta^n f$ cũng sẽ chỉ bao gồm các số 0, tức là $\Delta^n f \equiv 0$.

Nếu $f$ là hàm tuyến tính: $f(x) = ax + b$, tức là nếu dãy được biểu thị bằng cấp số cộng $b, a + b, 2a + b, 3a + b, \dots$, thì tất cả các số hạng của dãy $\Delta f$ sẽ bằng cùng một số $a$. Do đó $\Delta^2 f \equiv 0$.

Nếu $f$ là tam thức bậc hai $f(x) = ax^2 + bx + c$ thì $\Delta f$ là hàm tuyến tính (từ số $x$):

$$\Delta f(x) = f(x + 1) - f(x) = a(x + 1)^2 + b(x + 1) + c - ax^2 - bx - c = 2ax + b.$$

Khi đó $\Delta^2 f$ là hàm hằng: $\Delta^2 f = 2a$. Do đó $\Delta^3 f = 0$ và tất nhiên là $\Delta^n f = 0$ cho tất cả $n > 2$.

Chúng tôi không có quyền 1. a) Đặt $f(x) = x^3$. Tìm $\Delta f$, $\Delta^2 f$, $\Delta^3 f$, ... 6) Câu hỏi tương tự nếu $f(x) = 2^x$.

Những quan sát của chúng tôi được tóm tắt trong hai định lý sau đây.

1.1. Số $\Delta^n f(x)$ được biểu thị thông qua giá trị của hàm $f$ theo công thức

$$\Delta^n f(x) = C_n^0 f(x + n) - C_n^1 f(x + n - 1) + \dots + (-1)^n C_n^n f(x) =$$

$$= \sum_{k=0}^{k=n} (-1)^k C_n^k f(x + n - k).$$

1.2. Nếu $f(x)$ là đa thức bậc $m < n$ thì $\Delta^n f = 0$.

Cả hai mệnh đề 1.1 và 1.2 đều có thể được chứng minh bằng quy nạp trên $n$. Đối với $n = 1, 2, 3$ chúng tôi đã kiểm tra chúng. Giả sử chúng đúng với $n$, chúng ta chứng minh chúng cho $n+1$.

1.1. Sử dụng (7), (8) và (2), chúng tôi thu được

$$\Delta^{n+1}f(x) = \Delta^n f(x + 1) - \Delta^n f(x) =$$

$$= C_n^0 f(x + n + 1) - C_n^1 f(x + n) + \dots + (-1)^n C_n^n f(x) - C_n^0 f(x + n) + \dots + (-1)^n C_n^n f(x) =$$

$$= C_n^0 f(x + n + 1) - C_n^1 f(x + n) + \dots + (-1)^n C_n^n f(x + n) + (-1)^n \times C_n^n f(x).$$

1.2. Hãy để $f(x) = a_0 + a_1 x + \dots + a_j x^j + \dots + a_m x^m$. Đẳng thức $m$ của chúng ta (chúng tuân theo (4))

$$(x + 1)^j - x^j = C_j^1 x^{j-1} + C_j^2 x^{j-2} + \dots + C_j^{j-1} x + 1$$

(ở đây $j = 1, 2, \dots, m$). Chúng ta hãy nhân chúng tương ứng với các hệ số $a_j$ và cộng chúng lại. Chúng ta nhận được: ở bên trái $\Delta f(x) = f(x + 1) - f(x)$, ở bên phải - một đa thức nhất định ở $g(x)$ bậc không cao hơn $m - 1$. Nếu $m < n$ thì $m - 1 < n - 1$ và theo giả thuyết quy nạp $\Delta^{n-1}g = 0$. Vì vậy, $\Delta^n f = \Delta^{n-1} (\Delta f) = \Delta^n g = 0$.

⟦folio 30⟧

Bây giờ chúng ta hãy quay lại bài toán của chúng ta.

Đẳng thức (6'), theo 1.1. Tôi biết chính xác rằng $\Delta^n f(0) = 0$ dành cho hàm $f(x) = x^m$ và điều này diễn ra trực tiếp từ Tuyên bố 1.2.

Bài toán 1. Đặt $f(x) = a + a_1x + \dots + a_nx^n$. Tìm $\Delta^n f$. Sử dụng kết quả này hãy tính tổng

$$\sum_{k=0}^{k=n} (-1)^k k^n C_n^k.$$

Bài toán 2. Chứng minh rằng tồn tại $\Delta^{n+1} f(x) = 0$ với mọi $x$ thì $f(x)$ là đa thức bậc nhiều nhất $n$.

Bài toán 3. Tìm tất cả các chuỗi $f$ trong đó $\Delta f(x) = \lambda f(x)$, trong đó $\lambda$ là một số nào đó.

§ 2. Đa thức và công thức nội suy

Biết rằng qua hai điểm ta vẽ được một đường thẳng. Nói cách khác, nếu cho hai cặp số $(\alpha_0, \beta_0), (\alpha_1, \beta_1)$ và $\alpha_0 \neq \alpha_1$, thì sẽ tồn tại một đa thức bậc duy nhất không cao hơn đa thức bậc $P(x) = ax + b$ đầu tiên sao cho $P(\alpha_0) = \beta_0$ và $P(\alpha_1) = \beta_1$.

Thực tế này được tóm tắt như sau.

Cho $n + 1$ các số khác nhau $\alpha_0, \alpha_1, \dots, \alpha_n$ và $n + 1$ các số $\beta_0, \beta_1, \dots, \beta_n$. Khi đó các khẳng định sau đây là đúng.

2.1. Tồn tại một đa thức $P$ bậc không lớn hơn $n$ sao cho

$$P(\alpha_i) = \beta_i \quad (\text{для всех } i = 0,1,\dots,n).$$

2.2. Đa thức $P$ được xác định duy nhất.

Để chứng minh 2.1, chỉ cần tưởng tượng một đa thức như vậy là đủ. Để làm điều này, trước tiên hãy xem xét các đa thức

$$D_k(x) = \frac{(x - \alpha_0)(x - \alpha_1)\dots(x - \alpha_{k-1})(x - \alpha_{k+1})\dots(x - \alpha_n)}{(\alpha_k - \alpha_0)(\alpha_k - \alpha_1)\dots(\alpha_k - \alpha_{k-1})(\alpha_k - \alpha_{k+1})\dots(\alpha_k - \alpha_n)}$$

(vào tử số và mẫu số của đa thức $n$). Rõ ràng là vậy

$$D_k(\alpha_i) = \begin{cases} 1, \text{ если } i = k; \\ 0, \text{ если } i \neq k. \end{cases}$$

Bây giờ chúng ta hãy nhân $D_k(x)$ với số $\beta_k$ và cộng tất cả các đa thức này. Để có được một đa thức

$$P(x) = \sum_{k=0}^{k=n} \beta_k D_k(x)$$

mọi đẳng thức (9) đều được thỏa mãn.

Để chứng minh 2.2, ta cần hai định lý quan trọng về nghiệm của đa thức.

2.3. Nếu một đa thức

$$f(x) = a_0 + a_1x + \dots + a_nx^n$$

độ không cao hơn $n + 1$ của các nghiệm khác nhau thì đa thức này bằng 0, tức là $a_0 = a_1 = a_2 = \dots = a_n = 0$.

2.4. (“Định lý Bezout.”) Nếu $\alpha$ là nghiệm của đa thức $f(x)$, thì đa thức $f(x)$ chia hết cho $x - \alpha$, tức là

$$f(x) = (x - \alpha)g(x),$$

thực phẩm $g(x)$ là một đa thức nhất định.

⟦folio 31⟧

Chứng minh 2.4. Hãy viết $n$ điểm $(x^j - \alpha^j) = (x - \alpha)(x^{j-1} + x^{j-2}\alpha + \ldots + \alpha^{j-2}x + \alpha^{j-1})$, $(j=1, 2, \ldots, n)$, nhân chúng tương ứng với các hệ số $a_j$ rồi cộng tất cả các điểm này lại. Chúng ta thu được một công thức hợp lệ cho mọi đa thức (12) và mọi số $\alpha$:

$$f(x) - f(\alpha) = (x - \alpha)g(x),$$

trong đó $g(x)$ là một đa thức nào đó. Cụ thể, nếu $f(\alpha)=0$, chúng ta thu được (13).

Chứng minh 2.3. Chúng ta hãy tiến hành quy nạp trên $n$. Vì $n=1$ Mệnh đề 2.3 là hiển nhiên. Hãy chứng minh rằng nếu nó đúng với $n-1$ thì nó cũng đúng với $n$. Đặt $\alpha_0, \alpha_1, \ldots, \alpha_n$ là nghiệm của đa thức (12). Khi đó, theo 2.4:

$$f(x) = (x - \alpha_n)g(x),$$

hơn nữa, đa thức $g(x)$ có bậc nhiều nhất là $n-1$ và có $n$ nghiệm khác nhau $\alpha_0, \alpha_1, \ldots, \alpha_{n-1}$. Theo giả thuyết quy nạp, $g(x)$ bằng 0; từ (14) suy ra $f(x)$ cũng bằng 0.

Chứng minh 2.2. Giả sử $p_1$ và $p_2$ là hai đa thức, với mỗi đẳng thức (9) đều đúng. Khi đó hiệu của chúng thỏa mãn các điều kiện của Định lý 2.3 (đa thức $f(x) = p_1(x) - p_2(x)$) bậc không cao hơn $n+1$ căn $\alpha_0, \alpha_1, \ldots, \alpha_n$ và do đó bằng 0, tức là $p_1(x) = p_2(x)$.

Vì vậy, chúng ta đã chứng minh được rằng qua $n+1$ điểm $(\alpha_0, \beta_0), (\alpha_1, \beta_1), \ldots, (\alpha_n, \beta_n)$ chúng ta có thể chứng minh được một đường cong duy nhất có dạng

$$y = f(x) = a_0 + a_1x + \ldots + a_nx^n,$$

và thậm chí còn cung cấp một công thức cho phép bạn viết ngay đa thức cần thiết. Công thức (11) này được gọi là công thức tích phân Laerang.

Bài tập 2. a) Tìm một tam giác vuông biết tại các điểm 2, 3, 5 có các giá trị tương ứng là 7, 11, 13. 6) Tìm một đa thức bậc không lớn hơn 4, đồ thị của tam giác đó đi qua các điểm $(-2, -7), (-1, 0), (0, 1), (1, 2), (2, 9)$.

Hãy quay trở lại bài toán của chúng tôi. Chúng ta hãy xây dựng một đa thức bậc nhiều nhất là $n$, mà tại các điểm $\alpha_k = k(k=0, 1, 2, \ldots, n)$ thuộc giá trị của $\beta_k = k^m$ tương ứng. Từ công thức (11), suy ra đa thức này bằng $\sum_{k=0}^{k=n} k^mD_k(x)$, trong đó

$$D_k(x) = \frac{x(x-1)\ldots(x-k+1)(x-k-1)\ldots(x-n)}{k(k-1)\ldots1(-1)(-2)\ldots(k-n)}.$$

Rõ ràng hệ số $x^n$ của đa thức (15) bằng

$$\frac{1}{k(k-1)\ldots1(-1)(-2)\ldots(k-n)} = (-1)^{k-n} \frac{1}{k!(n-k)!} = \frac{(-1)^n}{n!} (-1)^k C_n^k,$$

Về cơ bản hệ số $x^n$ của đa thức $P(x)$ bằng

$$(1/n!) (-1)^n \sum_{k=0}^{k=n} (-1)^k k^m C_n^k.$$

Mặt khác, rõ ràng đa thức $P(x)$ đơn giản là $x^m$, bởi vì $m < n$. Do đó, hệ số của $x^n$ $P(x)$ bằng 0.

Bài 4. Chứng minh tập hợp số $y_0, y_1, \ldots, y_n$ thỏa mãn điều kiện: “với mọi đa thức $f(x)$ bậc không lớn hơn $n-1$ đẳng thức

$$\sum_{k=0}^{k=n} f(k)y_k = 0»,$$

khi và chỉ khi $y_k = t(-1)^k C_n^k$, trong đó $t$ là một số nào đó.

⟦folio 32⟧

Nhiệm vụ 5 (khái quát hóa). Chứng minh rằng nếu các số $\alpha_0, \alpha_1, \dots, \alpha_n$ phân biệt từng cặp thì hệ phương trình

$$y_0 + y_1 + \dots + y_n = 0,$$
$$\alpha_0 y_0 + \alpha_1 y_1 + \dots + \alpha_n y_n = 0,$$
$$\alpha_0^2 y_0 + \alpha_1^2 y_1 + \dots + \alpha_n^2 y_n = 0,$$
$$\alpha_0^{n-1} y_0 + \alpha_1^{n-1} y_1 + \dots + \alpha_n^{n-1} y_n = 0$$

có lời giải bộ số

$$y_k = \frac{t}{(\alpha_k - \alpha_1)(\alpha_h - \alpha_2) \dots (\alpha_k - \alpha_{k-1})(\alpha_h - \alpha_{k+1}) \dots (\alpha_h - \alpha_n)}$$

($k=0, 1, \dots, n+1$), trong đó $t$ là một số tùy ý và không có lời giải nào khác.

§ 3. Đạo hàm đa thức và bội nghiệm

Đặt $f(x)$ là đa thức bậc $n$:

$$f(x) = a_0 + a_1 x + a_2 x^2 + \dots + a_{n-1} x^{n-1} + a_n x^n = \sum_{k=0}^{k=n} a_k x^k.$$

Khi đó theo định nghĩa một đa thức bậc $n-1$

$$f'(x) = a_1 + 2 a_2 x + \dots + (n-1) a_{n-1} x^{n-2} + n a_n x^{n-1} = \sum_{k=1}^{k=n} ka_k x^{k-1}$$

được gọi là đa thức tùy ý $f(x)$. Tuyên bố sau đây hóa ra là đúng.

3.1. Nếu đa thức $f(x)$ chia hết cho $(x - \alpha)^{m+1}$ thì đa thức $f'(x)$ chia hết cho $(x - \alpha)^m$. Nói cách khác, nếu số $\alpha$ là nghiệm của bội số $m+1$ của đa thức $f(x)$, thì $\alpha$ là nghiệm của bội số ít nhất là $m$ của đa thức $f'(x)$.

Chứng minh 3.1. chúng tôi sử dụng bổ đề này.

3.2. Nếu $f(x) = (x - \alpha)g(x)$ thì

$$f'(x) = g(x) + (x - \alpha)g'(x).$$

(16)

Chứng minh 3.2. Nếu $g(x) = b_{n-1} x^{n-1} + \dots + b_1 x + b_0$, thì không khó để kiểm tra, sử dụng định nghĩa của một đa thức tùy ý, cả bên phải và bên trái của đẳng thức (16) đều bằng nhau

$$(b_0 - b_1 \alpha) + 2 (b_1 - b_2 \alpha) x + \dots + (n-1) (b_{n-2} - b_{n-1} \alpha) x^{n-2} + n b_{n-1} x^{n-1}.$$

Chứng minh 3.1 được chứng minh bằng indykation sử dụng $m$. Hãy kiểm tra 3.1 để tìm $m=1$. Nếu $f(x)$ chia hết cho $(x - \alpha)^2$ thì $f(x) = (x - \alpha) g(x)$, trong đó $g(x)$ chia hết cho $(x - \alpha)$ và, như có thể thấy từ (16), $f'(x)$ cũng chia hết cho $(x - \alpha)$.

Chứng minh 3.1 đúng với $m-1$ thì nó cũng đúng với $m$. Giả sử $f(x)$ chia hết cho $(x - \alpha)^{m+1}$. Khi đó $f(x) = (x - \alpha) g(x)$, trong đó $g(x)$ chia hết cho $(x - \alpha)^m$ và từ (16) suy ra rằng $f'(x)$ chia hết cho $(x - \alpha)^m$ ($g'(x)$ chia hết cho $(x - \alpha)^{m-1}$ theo đề xuất indyktion).

Bài tập 3. a) Đa thức $x^3 - x^2 - 8x + 12$ có bội nghiệm không?

6) Tìm $a, b$ và $c$ sao cho đa thức $x^3 + ax^2 + bx + c$ chia hết cho $(x+1)^2$.

Bây giờ chúng ta hãy quay lại bài toán của chúng ta. Đẳng thức (6') có nghĩa chính xác là đa thức $f_m(x) = \sum_{k=0}^{k=n} k^m C_k^n x^{k-1}$ có số $x = -1$ làm gốc của nó.

Chúng ta hãy chứng minh một phát biểu mạnh hơn: đa thức $x f_m(x)$ có số $(-1)$ là nghiệm của bội số $n-m$, tức là nó chia hết cho $(x+1)^{n-m}$ (nếu $m < n$).

Đối với $xf_0(x) = \sum_{k=0}^{k=n} C_k^n x^k = (1+x)^n$ điều này rất thuận tiện. Đối với $0 < m < n$, chúng tôi thực hiện indykation trên $m$. Cho $xf_{m-1}(x)$ có số $(-1)$ là bội số gốc
