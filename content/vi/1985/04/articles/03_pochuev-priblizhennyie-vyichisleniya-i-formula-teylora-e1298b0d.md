---
id: 1985-4-pochuev-priblizhennyie-vyichisleniya-i-formula-teylora-e1298b0d
issue: kvant_1985_4
year: 1985
number: "4"
title: Tính toán gần đúng và công thức Taylor
authors:
  - Почуев В. Р.
rubric: osnovnye-stati
page_first: 5
page_last: 8
page_labels: 3-6
tag: WYMX
lang: vi
source: kvant_digital
extraction: vision
content_sha256: 117808ba323881ae2deccddc2e667e792a2b6a4aebb0047d4d4193a5e94ea7aa
prompt_sha256: draft-1
translated_from: content/ru/1985/04/articles/03_pochuev-priblizhennyie-vyichisleniya-i-formula-teylora-e1298b0d.md
source_content_sha256: 6f90894a8bcaf2351829917c23315e71bf8bed67701d8b20e46004b7b4b7cd84
translation_model: draft
translation_run: vi-draft-2026-10-31
translation_quality: draft
---

⟦folio 3⟧

Tính toán gần đúng và công thức Taylor

V. R. POCHUEV

Bài viết này bắt đầu bằng các phép thay thế đơn giản về các phép tính số học gần đúng, điều này đương nhiên dẫn đến công thức thay thế của Taylor. Đặc biệt, công thức này được thiết lập theo phương pháp của trường, sau đó được sử dụng để tính gần đúng các giá trị của hàm.

Hai ví dụ để khởi động

Giả sử chúng ta cần tính tích

$$p = 1,03 \times 2,01$$

với độ chính xác 0,001. Việc tính toán như thế này là điều đương nhiên

$$p = (1 + 0,03) \cdot (2 + 0,01) \approx 2 + 0,06 + 0,01 = 2,07.$$

Ở đây chúng ta đã bỏ qua bốn số hạng $0,01 \times 0,03 = 0,0003$, vì nó kém hơn độ chính xác quy định.

Ký hiệu được sử dụng sẽ trở nên rõ ràng hơn nếu bạn biểu thị số 0,01 bằng $x$. Khi đó phép tính của chúng ta chỉ đơn giản là phép tính hàm số (đa thức)

$$f(x) = (1 + 3x)(2 + x) = 2 + 7x + 3x^2$$

khi giá trị là $x = 0,01$ hoặc $p = f(0,01)$. Khi viết đẳng thức gần đúng $f(x) \approx 2 + 7x$, chúng ta bỏ qua số hạng bậc cao hơn (thứ hai) $3x^2$.

Hãy xem xét một ví dụ phức tạp hơn một chút: hãy tính tích với độ chính xác 0,01

$$q = 2,12 \times 1,97.$$

Bây giờ ký hiệu số 0,1 bằng $x$, ta thấy rằng tính $q$ tức là tìm giá trị của hàm

$$g(x) = (2 + x + 2x^2)(2 - 3x^2)$$

tại $x = 0,1$. Mở ngoặc, chúng ta nhận được

$$g(x) = 4 + 2x - 2x^2 - 3x^3 - 6x^4.$$

Có thể bỏ qua các số hạng có $x^3$ và $x^4$ vì tại $x = 0,1$, $x^3 = 0,001$ và $x^4 = 0,0001$ nằm ngoài độ chính xác yêu cầu là 0,01. Vì thế,

$$q = g(0,1) \approx 4 + 2(0,1) - 2(0,1)^2 = 4,18.$$

Hãy phân tích hành động của chúng tôi

Sự thành công của các phép tính dựa trên thực tế là tích mong muốn $p$ (hoặc $q$) gần với số chính xác $A$ và sau đó được biểu thị dưới dạng giá trị của một số hàm $f(x)$ cho $x$ nhỏ, với $f(0)$ bằng $A$.

Vì vậy, trong ví dụ đầu tiên, ước tính sơ bộ cho $p \approx 1 \cdot 2 = 2 = A_1$ và độ lệch của hệ số com so với một và hai là nhỏ. Tương tự, trong ví dụ thứ hai, ước tính sơ bộ cho $q \approx 2 \cdot 2 = 4 = A_2$, và một lần nữa độ lệch của hệ số com so với hai là nhỏ. Trong mỗi

⟦folio 4⟧

Trong trường hợp thứ hai, độ lệch của các hệ số này được đo bằng “đơn vị x”, trong đó $x$ là 0,01 và trong trường hợp thứ hai - bằng `các “đơn vị x” khác, trong đó $x'$ là 0,1.

Tiếp theo, hàm đã chọn $f(x)$ (hoặc $g(x)$) được chia thành hai phần - hiện có và phụ:

$$f(x) = f_1(x) + f_2(x), \quad f_1(x) = 2 + 7x, \quad f_2(x) = 3x^2, \quad g(x) = g_1(x) + g_2(x), \quad g_1(x) = 4 + 2x - 2x^2, \quad g_2(x) = -3x^3 - 6x^4,$$

trong đó các phần thiết yếu $f_1(x)$ (và $g_1(x)$) là đa thức bậc một và bậc hai, biểu thị kết quả với độ chính xác cần thiết, còn $f_2$ và $g_2$ là không đáng kể.

Hãy giới thiệu biểu tượng “khoảng nhỏ”

Trong các trường hợp được xem xét trong phân tích toán học, công thức ghi ngắn hơn và biểu cảm hơn sau đây thường được sử dụng:

$$f(x) = 2 + 7x + o(x), \quad g(x) = 4 + 2x - 2x^2 + o(x^2).$$

Ở đây ký hiệu $o(x)$ (đọc “khoảng nhỏ từ $x$”) biểu thị một số hàm của $x$ (chúng tôi không quan tâm đến dạng chính xác của nó), có xu hướng về 0 nhanh hơn $x$, nghĩa là, sao cho

$$\lim_{x \to 0} \frac{o(x)}{x} = 0.$$

Tương tự, $o(x^2)$ là một hàm nào đó của $x$ có xu hướng về 0 nhanh hơn $x^2$, tức là

$$\lim_{x \to 0} \frac{o(x^2)}{x^2} = 0.$$

Tổng quát $o(x^n)$, cho $n \ge 1$, là ký hiệu cho hàm của $x$ có ​​thuộc tính sau:

$$\lim_{x \to 0} \frac{o(x^n)}{x^n} = 0.$$

Bằng cách sử dụng các tính chất số học của các giới hạn (xem Đại số và phần đầu của phân tích 9-10, các đoạn văn), có thể dễ dàng thiết lập các quy tắc sau đây cho phép bạn chuyển đổi các biểu thức phức tạp chứa o nhỏ thành các biểu thức đơn giản hơn:

(a) $o(x^n) + o(x^n) = o(x^n)$,
(b) $x \cdot o(x^n) = o(x^{n+1})$,
(c) $x^{n+1} = o(x^n)$, v.v.
(Ví dụ: để đặt (a),

$$\begin{align*}
\lim_{x \to 0} \frac{o(x^n)}{x^n} &= 0.
\end{align*}$$

cần chứng minh rằng tổng của hai hàm số, mỗi hàm số đều có xu hướng bằng 0, bản thân nó cũng có xu hướng bằng 0; và điều này ngay lập tức tuân theo quy tắc về tổng các giới hạn.)

Hãy rút ra một số công thức gần đúng

Hãy sử dụng các ký hiệu $o(x)$, $o(x^2)$, ... và các thuộc tính của chúng để rút ra một số công thức hữu ích cho các phép tính gần đúng.

Ví dụ 1. Hãy chứng minh công thức:

$$(1+x)^3 = 1 + 3x + o(x).$$

(Thuật ngữ $o(x)$ cho chúng ta biết rằng công thức này có thể được sử dụng nếu bình phương $x$ có thể bị bỏ qua trong các phép tính của chúng ta.)

Bằng chứng. Sử dụng công thức tính tổng khối

$$(1+x)^3 = 1 + 3x + 3x^2 + x^3,$$

nhưng $x^2 = o(x)$ (quy tắc (d)); $3x^2 = o(x)$ (quy tắc (b)); $x^3 = o(x)$ (quy tắc (d), (c)). Đó là lý do tại sao

$$(1+x)^3 = 1 + 3x + o(x) + o(x) = 1 + 3x + o(x).$$

Vì vậy, chúng ta có thể viết với độ chính xác 0,01:

$$(1,012)^3 \approx 1 + 3 \cdot 0,012 = 1,036.$$

Ví dụ 2. Hãy chứng minh công thức:

$$\frac{1}{1-q} = 1 + q + q^2 + \dots + q^n + o(q^n).$$

Bằng chứng được đưa ra ngay sau đây từ một cách tiếp cận dễ kiểm chứng

$$\frac{1}{1-q} = 1 + q + q^2 + \dots + q^n + \frac{q^{n+1}}{1-q}.$$

Chúng ta hãy sử dụng công thức (2) để tính gần đúng phân số $r = 201/203$. Biểu diễn phân số này dưới dạng

$$r = \frac{1 + \frac{1}{200}}{1 + \frac{3}{200}},$$

chúng ta hãy xem xét chức năng

$$h(x) = \frac{1+x}{1+3x}; \quad h\left(\frac{1}{200}\right) = h(0,005) = r.$$

Lấy (2) $n=2$, $q=-3x$; Sau đó

$$\frac{1}{1+3x} = 1 - 3x + 9x^2 + o(x^2),$$

⟦folio 5⟧

$$h(x) = \frac{1}{1+3x} = 1 - 2x + 6x^2 + o(x^2).$$

Vì vậy, $r = h(0,005) \approx 1 - 0,01 + 0,000150 = 0,990150$.

Bài tập

1. Viết và thiết lập công thức cho $(1+x)^7$ với độ chính xác $o(x^2)$.
2. Viết và thiết lập công thức cho $1/(1+q)$ với độ chính xác $o(q^n)$.

Tính toán gần đúng các căn thức

Khi tính toán gần đúng các căn thức, chúng ta sẽ phân biệt giữa trường hợp “tốt” và trường hợp “xấu”. Trong trường hợp “tốt”, dưới dấu căn bậc hai có một số hơi khác so với số bình phương hoàn hảo; số được tính $\lambda$ có dạng $\sqrt{a^2 + a^2}$, trong đó $a$ nhỏ so với $a^2$. Để minh họa trường hợp này, hãy xem xét ví dụ sau.

Ví dụ 3. Hãy tìm giá trị gần đúng của căn bậc $\lambda = \sqrt{99}$.

Hãy biểu thị $\lambda$ là
$$\lambda = \sqrt{100-1} = 10\sqrt{1-0,01}$$
và xét hàm $r(x) = \sqrt{1+x}$ sao cho $\lambda = 10r(-0,01)$. Giả sử rằng đối với $x$ nhỏ có một công thức gần đúng
$$r(x) = a + bx + cx^2 + o(x^2).$$

(3) Tìm $a, b$ và $c$. Trước hết, hướng $x$ về 0, chúng ta thu được: $a = 1$. Bây giờ hãy bình phương cả hai vế của đẳng thức (3):
$$1 + x = a^2 + 2abx + (b^2 + 2ac)x^2 + o(x^2).$$

Đánh đồng các hệ số của cùng lũy ​​thừa $x$ ở cả hai vế của đẳng thức cuối cùng, chúng ta thu được $a^2 = 1; 2ab = 1; b^2 + 2ac = 0$. Xét rằng $a = 1$, chúng ta tìm thấy: $b = 1/2; c = -1/8$. Vì thế,
$$\sqrt{1+x} = 1 + \frac{1}{2}x - \frac{1}{8}x^2 + o(x^2).$$

(4) Như vậy,
$$\lambda = 10r(-0,01) \approx 10(1-0,005 - 0,0000125) = 10(0,9949875) = 9,949875.$$

Bây giờ chúng ta hãy chỉ ra cách hành động trong một trường hợp “xấu”. Như một minh họa, chúng ta hãy nhìn vào

Ví dụ 4. Hãy tìm giá trị gần đúng của căn bậc $\mu = \sqrt{2}$.

Rõ ràng là công thức (4) mà chúng tôi tìm thấy, mang lại $\sqrt{2}$ cho $x = 1$, hoàn toàn không phù hợp để tính căn thức, vì $x$ không nhỏ và chúng tôi không thể tính được rằng các số hạng ở vế phải của (4) giảm nhanh chóng. Để tạo ra một trường hợp “tốt”, chúng ta chọn hai hình vuông hoàn chỉnh có tỷ lệ là 2. Các hình vuông đó chẳng hạn là 25 và 49. Sau đó
$$\mu = \sqrt{2} = \frac{7}{5} \sqrt{\frac{50}{49}} = \frac{7}{5} v.$$
Phép tính $v$ đã là một trường hợp “tốt”, vì bên dưới dấu căn có một số gần bằng 1 (một hình vuông hoàn hảo). Hãy viết $v$ dưới dạng:
$$v = (1-0,02)^{-\frac{1}{2}}$$
và xét hàm $S(x) = 1/\sqrt{1+x}$. Sau đó $v = S(-0,02)$. Chúng ta hãy lại giả sử rằng có một công thức có dạng
$$S(x) = a + bx + cx^2 + o(x^2).$$
Hướng $x$ về 0, chúng ta thu được $a = 1$. Chúng ta bình phương cả hai vế và nhân với mẫu số,
$$1 = (1+x)(a^2 + 2abx + (b^2 + 2ac)x^2 + o(x^2)),$$
$$1 = a^2 + (a^2 + 2ab)x + (b^2 + 2ab + 2ac) \times x^2 + o(x^2).$$
Chúng ta đánh đồng các hệ số của cùng lũy ​​thừa $x$ ở cả hai vế của đẳng thức cuối cùng, chúng ta nhận được $a^2 = 1, a^2 + 2ab = 0, b^2 + 2ab + 2ac = 0$. Xét rằng $a = 1$, chúng ta tìm thấy: $b = -1/2; c = 3/8$. Vì thế,
$$\frac{1}{\sqrt{1+x}} = 1 - \frac{1}{2}x + \frac{3}{8}x^2 + o(x^2).$$

Như vậy,
$$\mu = \sqrt{2} = (7/5)S(-0,02) \approx 1,4(1+0,01+0,00015) = 1,41421.$$
Công thức Taylor cho đa thức Cho một đa thức bậc $n$:
$$p(x) = a_0 + a_1x + a_2x^2 + ... + a_nx^n$$
Khi đó công thức sau giữ nguyên:
$$p(x) = p(0) + p'(0)x + \frac{1}{2!}p''(0)x^2 + ... + \frac{1}{n!}p^{(n)}(0)x^n,$$

⟦folio 6⟧

trong đó $p^{(n)}$ biểu thị hàm đạo hàm bậc $n$ $p$ và ký hiệu $n!$ (đọc là “en giai thừa”) được giải mã như sau: $n! = 1 \cdot 2 \cdot 3 \cdot \dots \cdot n$.

Ví dụ: tại $n = 2$, $p(x) = a_0 + a_1x + a_2x^2$, do đó $p'(x) = 2a_2x + a_1$, $p''(x) = 2a_2$, do đó, $p'(0) = a_1$, $p''(0) = 2a_2$ và do đó, thực sự,

$$p(x) = p(0) + p'(0)x + \frac{1}{2}p''(0)x^2 = a_0 + a_1x + a_2x^2.$$

Trong trường hợp tổng quát, công thức (6) được kiểm tra trực tiếp. Tôi khuyên người đọc đừng lười biếng và hãy tiếp tục kiểm tra này, bắt đầu “khởi động” với trường hợp $n = 3$.

Công thức Taylor cho hàm số

Sử dụng quy tắc (6) và (d), công thức (6) có thể được viết lại thành

$$p(x) = p(0) + p'(0)x + \frac{p''(0)x^2}{2} + \dots + \frac{p^{(n-1)}(0)}{(n-1)!}x^{n-1} + o(x^{n-1}).$$

Công thức này hữu ích cho các phép tính gần đúng khi $x^n$ không đáng kể. Tuy nhiên, chúng ta quan tâm đến nó ở đây vì một lý do khác: hóa ra công thức này không chỉ đúng với đa thức $p(x)$, mà còn đúng với các hàm tùy ý $f(x)$ (miễn là chúng có $f'(x)$, $f''(x)$, ..., $f^{(n+1)}(x)$ tùy ý bao gồm $n+1$). Thư từ

$$f(x) = f(0) + f'(0)x + \frac{f''(0)}{2}x^2 + \dots + \frac{f^{(n)}(0)}{n!}x^n + o(x^n)$$

được gọi là công thức Taylor (hoặc Maclaurin) theo tên hai hệ số toán học người Anh thế kỷ 17-18, mặc dù về bản chất nó cũng được Newton biết đến. Chúng ta sẽ không chứng minh công thức này ở dạng tổng quát nhưng cũng sẽ thu được các khai triển bằng cách sử dụng các phương pháp đơn giản hơn, như chúng ta đã làm trước đó.

Công thức Taylor
cho các hàm hữu tỷ phân số (phương pháp hệ số không xác định)

Phân số hữu tỉ là bất kỳ hàm nào biểu diễn

xử lý dưới dạng tỉ số của hai đa thức. Chúng ta hãy xem một ví dụ cụ thể về cách thu được khai triển Taylor cho các hàm như vậy.

Ví dụ 5. Sử dụng công thức Taylor, chúng ta mở rộng hàm lên $o(x^3)$

$$f(x) = \frac{1+x}{1+x+x^2}.$$

Cách đầu tiên. Xét hàm $g(x) = \frac{1}{1+x+x^2}$. Hãy giới thiệu một biến mới $t = x+x^2$. Sử dụng công thức (2), trong đó $q = -t$, chúng ta có thể viết

$$g(x) = \frac{1}{1+t} = 1-t+t^2-t^3+o(t^3) = 1-(x+x^2)+(x+x^2)^2-(x+x^2)^3 + o(x^3) = 1-x+x^3+o(x^3).$$

Vì thế,

$$f(x) = (1+x)(1-x+x^3+o(x^3)) = 1-x^2+x^3+o(x^3).$$

Phương pháp thứ hai (phương pháp hệ số không xác định). Cho phép

$$f(x) = \frac{1+x}{1+x+x^2} = a+bx+cx^2 + dx^3 + o(x^3)$$

Hãy nhân cả hai vế với mẫu số:

$$1+x = (1+x+x^2)(a+bx+cx^2+dx^3 + o(x^3))$$

$$1+x = a+(a+b)x+(a+b+c)x^2 + (b+c+d)x^3+o(x^3).$$

Chúng ta đánh đồng các hệ số của cùng lũy ​​thừa $x$ ở cả hai vế của đẳng thức cuối cùng, chúng ta nhận được $a=1, a+b=1; a+b+c=0; b+c+d=0$. Do đó, $a=1, b=0, c=-1, d=1$, và chúng ta đi đến kết quả tương tự.

Công thức Taylor
cho các hàm lượng giác

Mục tiêu của chúng tôi là chứng minh công thức sau mà không sử dụng công thức Taylor tổng quát (7).

$$\sin x = x - \frac{x^3}{3!} + \frac{x^5}{5!} + o(x^5),$$

$$\cos x = 1 - \frac{x^2}{2!} + \frac{x^4}{4!} + o(x^4).$$
