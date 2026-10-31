---
id: 1978-2-zazelo-mnozhestva-znacheniy-chislovyih-funktsiy-7f039538
issue: kvant_1978_2
year: 1978
number: "2"
title: Tập hợp các giá trị của hàm số
authors:
  - Зазело А.
rubric: praktikum-abiturienta
rubric_sub: Практикум абитуриента
page_first: 51
page_last: 52
page_labels: 49-50
tag: A2VQ
lang: vi
source: kvant_digital
extraction: vision
content_sha256: 325d4a262fb1a05e092d552a6a1402ce61784df9aeea2e91524e23c46df025b0
prompt_sha256: draft-1
translated_from: content/ru/1978/02/articles/19_zazelo-mnozhestva-znacheniy-chislovyih-funktsiy-7f039538.md
source_content_sha256: ac676888f2cf4174fffd1bc61f4de9c89379201237d4b00a340a487223b65a6d
translation_model: draft
translation_run: vi-draft-2026-10-31
translation_quality: draft
---

⟦folio 49⟧

Tập hợp các giá trị của hàm số

Hãy nhớ rằng tập hợp các giá trị $E(f)$ của hàm số $f$ được gọi là tập hợp tất cả $a \in \mathbb{R}$ mà tồn tại ít nhất một $x \in D(f)$ sao cho $f(x) = a$. Chúng ta có thể nói khác đi: $E(f)$ bao gồm những $a$ mà phương trình $f(x) = a$ có ít nhất một lời giải. Trong những trường hợp đơn giản, phương trình này có thể được kiểm tra và từ đó tìm thấy $E(f)$.

Ví dụ 1. Tìm tập giá trị hàm

$$f(x) = \frac{2x}{1+x^2}.$$

Phương trình $f(x) = a$ được viết lại thành $ax^2 - 2x + a = 0$; với $a = 0$ nó được thỏa mãn bởi $x = 0$ và trong trường hợp $a \neq 0$ chúng ta có một phương trình bậc hai có lời giải chỉ dành cho những $a$ mà phân biệt đối xử của nó không âm: $D = 4 - 4a^2 \geq 0$, tức là $a^2 \leq 1$ hoặc $a \in [-1; 1]$ (và $a \neq 0$). Vậy phương trình $f(x) = a$ có lời giải khi và chỉ nếu $a \in [-1; 1]$, nên $E(f) = [-1; 1]$. Lưu ý rằng đồng thời chúng tôi đã tìm thấy các giá trị nhỏ nhất và lớn nhất của hàm $f$ - $\min f = -1$, $\max f = 1$.

Nhiệm vụ 1-3. Tìm tập hợp các giá trị của các hàm đã chỉ định, cũng như các giá trị nhỏ nhất và nhỏ nhất của chúng (trong trường hợp chúng tồn tại).

1. a) $\frac{2x}{1+x}$; 6) $\frac{1}{1+x^2}$; 8) $\frac{1}{1-x^2}$.
2. a) $\pi^x - 3$; 6) $\log_2 x + \log_x 2$;
b) $tg x + ctg x$.
3. a) $\cos^2 x + \cos 2x$; 6) $\sin x \cdot \cos x$;
b) $\sin^4 x + \cos^4 x$.

Trong một số trường hợp, việc chú ý tập hợp các giá trị của hàm cho trước là

hướng tới việc nghiên cứu hàm bậc hai trên một khoảng cụ thể. Để tránh sai sót, việc vẽ đồ thị của hàm bậc hai này là rất hữu ích.

Ví dụ 2. Tìm tập giá trị hàm

$$f(x) = 2\cos x + \cos 2x.$$

Chúng ta hãy viết lại $f(x)$ ở dạng $f(x) = 2\cos x + 2\cos^2 x - 1 = 2z^2 + 2z - 1$, trong đó $z$ biểu thị hàm $\cos x$. Vì $z \in [-1; 1]$, vẫn còn phải tìm ra tập giá trị của hàm bậc hai $g(z) = 2z^2 + 2z - 1$ trên khoảng $[-1; 1]$. Đồ thị của hàm số $g(z)$ là một parabol có đỉnh trùng với hoành độ $z_0 = -1/2$ (giải thích), các nhánh của nó hướng lên trên. Chúng ta có: $g(z_0) = -3/2$, $g(-1) = -1$, $g(1) = 3$. Nếu chúng ta vẽ đồ thị của một tam thức bậc hai, thì rõ ràng tập hợp các giá trị $g$ trên đoạn $[-1; 1]$ (hoặc tập hợp các giá trị $a$ mà phương trình $g(z) = a$ có ít nhất một nghiệm $z \in [-1; 1]$) là phân đoạn $[-3/2; 3]$. Do đó, tập hợp các giá trị của hàm $f(x) = 2\cos x + \cos 2x$ là đoạn $[-3/2; 3]$. Quay lại chúng tôi đã tìm thấy $\min f = -3/2$ và $\max f = 3$.

Nhiệm vụ 4-5. Bằng cách kiểm tra các giá trị gần đúng của các hàm bậc hai trên các khoảng tương ứng, chúng ta sẽ tìm thấy tập hợp các giá trị của các hàm sau, cũng như các giá trị nhỏ nhất và nhỏ nhất của chúng.

4. a) $6\cos x + \cos 2x$; 6) $\sin x + \cos 2x$.
5. a) $4x - 2x^2 + 3$; 6) $4\sin x - 2\sin x + 2$.

Trong trường hợp không có nhiều giá trị của hàm có dạng

$$f(x) = A\cos x + B\sin x$$

bạn có thể biểu diễn cos $x$ và sin $x$ theo $t = tg(x/2)$ (xem “Đại số và Các phần tử” 10”, đoạn 91) và sau đó kiểm tra phương trình thu được (đối với $t$ nó sẽ là phương trình bậc hai).

Tuy nhiên, nó được thực hiện nhanh hơn và dễ dàng hơn theo cách này:

$$A\cos x + B\sin x = \sqrt{A^2 + B^2} \times \left( \frac{A}{\sqrt{A^2 + B^2}} \cos x + \frac{B}{\sqrt{A^2 + B^2}} \sin x \right);$$

bởi vì

$$\left( \frac{A}{\sqrt{A^2 + B^2}} \right)^2 + \left( \frac{B}{\sqrt{A^2 + B^2}} \right)^2 = 1,$$

⟦folio 50⟧

tồn tại một giá trị $\alpha$ sao cho
$$\cos \alpha = \frac{A}{\sqrt{A^2 + B^2}}, \sin \alpha = \frac{B}{\sqrt{A^2 + B^2}}$$
(giải thích) và do đó
$$A \cos x + B \sin x = \sqrt{A^2 + B^2} \left( \cos x \cos \alpha + \sin x \sin \alpha \right) = \sqrt{A^2 + B^2} \cos (x - \alpha)$$.

Do đó, tập hợp các giá trị của hàm $f(x) = A \cos x + B \sin x$ là phân đoạn $[-\sqrt{A^2 + B^2}, \sqrt{A^2 + B^2}]$ và điều tương tự cũng áp dụng cho hàm có dạng $A \cos \omega x + B \sin \omega x$, trong đó $\omega \neq 0$.

Nhiệm vụ 6. Chỉ định tập hợp giá trị cho các hàm sau:

a) $\cos x - \sin x + 1; 6)$ $3 \cos \frac{x}{2} + 4 \sin \frac{x}{2};$
b) $\cos^2 x - \sin x \cos x$.

Trên thực tế, trong tất cả các ví dụ được phân tích và các bài toán đã cho lời giải, các phương trình $f(x) = a$ có thể được viết ra một cách rõ ràng, tức là phương trình $f(x) = a$ với tham số $a$ được “giải” (rút gọn thành các phương trình tuyến tính, bậc hai hoặc đơn giản, hàm mũ, logarit và lượng giác). Nhờ đó, giá trị nhỏ nhất và lớn nhất của các hàm đang xét được tìm thấy mà không cần sử dụng hàm tùy ý (hơn nữa, nghiên cứu sử dụng hàm tùy ý ở đây thường sẽ cồng kềnh hơn so với nghiên cứu đại số). Trong trường hợp phương trình $f(x) = a$ không được gửi cho người không chủ trì lời giải (“không giải được”), thì việc thực hiện theo cách ngược lại mà chúng tôi sẽ mô tả bây giờ là hợp lý.

Ví dụ 3. (Điều này bài toán được lấy từ “Các lựa chọn gần đúng cho kỳ thi tuyển sinh môn toán tại các trường đại học năm 1977”, «Kvant», 1977, số 6, trang 89). Hãy tìm tập giá trị của hàm

$$f(x) = \sin x \cdot \cos 2x$$

Ký hiệu $\sin x = z$, ta có thể viết: $f(x) = g(z) = z (1 - 2z^2) = z - 2z^3$. Như ví dụ 2, thuộc tính bài toán để tìm tập hợp các giá trị của hàm $g$ trên đoạn $[-1; 1]$. Lưu ý rằng phương trình là $g(z) = a - кубическое$ và chúng ta không thể giải nó. Chúng ta hãy tìm giá trị nhỏ nhất và lớn nhất của hàm $g$ trên đoạn $[-1; 1]$. Thực hiện theo sơ đồ chung để nghiên cứu hàm số trên một đoạn (xem “Đại số và Phân tích cơ bản 9”, đoạn 59), chúng ta tìm thấy các điểm tới hạn của hàm: $g'(z) = 1 - 6z^2 = 0$ tại $z^2 = 1/6$, tức là $z = \pm \sqrt{1/6}$; cả hai điểm tới hạn đều thuộc đoạn $[-1; 1]$ và các giá trị của hàm trong chúng như sau:

$$g(\sqrt{1/6}) = \sqrt{6}/9, g(-\sqrt{1/6}) = -\sqrt{6}/9.$$

So sánh các giá trị này với các giá trị ở cuối đoạn - với $g(-1) = 1$ và $g(1) = 1$ - ta được: $\min(z - 2z^3) = -1, \max(z - 2z^3) = 1.$

Vì hàm $g$ luôn không liên tục nên đương nhiên nó sẽ kết luận rằng $g$ nhận bất kỳ giá trị nào giữa giá trị nhỏ nhất và giá trị lớn nhất, tức là $E(g) = E(f) = [-1; 1]$. Để chứng minh điều này, chúng ta sẽ sử dụng một định lý quan trọng về tập hợp các giá trị của hàm đơn điệu liên tục:

nếu hàm $F$ không gián đoạn và tăng (hoặc giảm) trên khoảng $[a; b]$, thì tập hợp các giá trị mà hàm $F$ lấy trên khoảng này cũng là một khoảng: $[F(a); F(b)]$ (hoặc $[F(b); F(a)]$ nếu $F$ giảm).

Định lý này ở dạng công thức tổng quát và đầy đủ hơn được đưa ra trong đoạn 84 của sách giáo khoa “Đại số và Giải tích cơ bản 10” (không có chứng minh). Quay trở lại hàm của chúng ta, chúng ta thấy rằng $g$ tăng trên đoạn $[-\sqrt{1/6}; \sqrt{1/6}]$ và giảm trên các đoạn $[-1; -\sqrt{1/6}], [\sqrt{1/6}, 1]$.

Theo định lý cuối cùng, các tập $g$ trên các đoạn này sẽ có các đoạn tương ứng là $[-\sqrt{6}/9; \sqrt{6}/9], [-\sqrt{6}/9; 1]$ và $[-1; \sqrt{6}/9]$;

liên kết của chúng đưa ra tập hợp các giá trị của hàm $g$ trên toàn bộ khoảng $[-1; 1] - E(g) = [-1; 1]$.

Nhiệm vụ 7-8. Tìm tập hợp các giá trị của các hàm đã chỉ định.

7. $x^3 - 6x^2 + 9x$ nếu: a) $x \in [2; 4]$; b) $x \in [-2; 2]$.

8. a) $\cos x \cdot \sin 2x$; b) $\sin x + \sin 3x$.

Bài 9. Thể tích của hình nón có ma trận độ dài 1 dm có thể thay đổi trong giới hạn nào?

Bài 10. Diện tích toàn phần của hình trụ có thể tích 1 dm2 có thể bị giới hạn trong giới hạn nào?
