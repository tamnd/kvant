---
id: 1976-3-lyahovskiy-logarifmicheskie-i-pokazatelnyie-4c15dea7
issue: kvant_1976_3
year: 1976
number: "3"
title: Logarit và hàm mũ...
authors:
  - Ляховский В. А.
rubric: praktikum-abiturienta
rubric_sub: Практикум абитуриента
page_first: 53
page_last: 59
page_labels: 51-57
tag: 9PON
lang: vi
source: kvant_digital
extraction: vision
content_sha256: af96460ac886089493a7ca22318cfb0962d9ebd2994fda29d827314ebee0b917
prompt_sha256: draft-1
translated_from: content/ru/1976/03/articles/13_lyahovskiy-logarifmicheskie-i-pokazatelnyie-4c15dea7.md
source_content_sha256: 2e81988cde222178e973e38a7c313fb0694ff720c57c08b9ad878c31eb2567e7
translation_model: draft
translation_run: vi-draft-2026-10-31
translation_quality: draft
---

⟦folio 51⟧

Logarit và hàm mũ...

Hầu hết các bài tập toán được đưa ra trong các kỳ thi đại học mang tính cạnh tranh đều liên quan đến các phương trình lời giải và bất đẳng thức.

Đối với những phương pháp đơn giản nhất, chẳng hạn như đối với phương trình bậc hai và hệ phương trình tuyến tính, có các phương pháp chung lời giải. Trong hầu hết các trường hợp, không có quy tắc nào cho phép giải phương trình bằng cách thực hiện tuần tự các phép tính số học và các phép tính cơ bản trên các hệ số của phương trình. Do đó, khi nghiên cứu, ví dụ, các phương trình và bất đẳng thức hàm mũ và logarit, chỉ xem xét các kỹ thuật từng phần lời giải.

phương trình

Khi lời giải phương trình được sử dụng rộng rãi để biến đổi cả hai vế của một phương trình đã cho.

Về giới hạn 1. Nếu tất cả các nghiệm của một phương trình đều là nghiệm của phương trình khác thì phương trình thứ hai được gọi là hệ quả của phương trình thứ nhất.

Về giới hạn 2. Hai phương trình được gọi là tương đương (tương đương) từ một tập giá trị nào đó của ẩn số nếu chúng có cùng nghiệm, với

thuộc tập hợp này, nghĩa là nếu mỗi tập hợp đó là hệ quả của tập hợp kia.

Điều tự nhiên là chỉ áp dụng các phép biến đổi trong đó mỗi phương trình tiếp theo tương đương với phương trình trước đó về khoảng cách giữa chúng (dưới đây, trừ khi có quy định khác, chúng tôi muốn nói đến tập hợp tất cả các số thực). Khi đó lời giải của phương trình cuối cùng cũng sẽ là nghiệm của phương trình ban đầu.

Tuy nhiên, phương pháp lời giải này không phải lúc nào cũng thực hiện được. Nếu không, hãy thay thế phương trình bằng một hệ quả không tương đương, rồi kiểm tra các nghiệm để xem liệu có bất kỳ nghiệm nào được xây dựng trong số chúng hay không.

Trước hết chúng ta hãy nhắc lại một số định lý cơ bản.

Định lý 1. Với $a > 0, a \neq 1$, phương trình $a^{f(x)} = a^{\varphi(x)}$ tương đương với phương trình $f(x) = \varphi(x)$.

Định lý 2. Với $a > 0, a \neq 1$ phương trình $\log_a f(x) = \log_a \varphi(x)$ tương đương với bất kỳ hệ nào

$$\begin{cases} f(x) = \varphi(x), \\ f(x) > 0, \\ \varphi(x) > 0. \end{cases}$$

Lưu ý rằng nếu việc xây dựng các nghiệm chỉ xuất hiện do việc mở rộng phạm vi các giá trị cho phép (APV) của ẩn số, thì bạn có thể tách chúng khỏi các nghiệm của phương trình ban đầu bằng cách kiểm tra xem chúng có được đưa vào APV hay bằng cách thay thế trực tiếp chúng vào phương trình ban đầu hoặc thành một phương trình tương đương với phương trình ban đầu. Nếu các nghiệm phụ có thể xuất hiện không phải do sự giãn nở của ODZ thì cần kiểm tra bằng cách thay thế vào phương trình ban đầu hoặc vào phương trình trung gian mà tại đó lời giải các nghiệm này có thể xuất hiện.

Nhiệm vụ 1 (Viện Kỹ sư Vận tải Đường sắt Novosibirsk, 1974). Giải phương trình

$$9\sqrt{x^2-2x}-x-1=2.$$

⟦folio 52⟧

Nhận thấy rằng
$$9\sqrt{x^2-2x}-x=3^2(\sqrt{x^2-2x}-x),
3\sqrt{x^2-2x}-x-1=\frac{1}{3}\cdot 3\sqrt{x^2-2x}-x,
$$
đặt $3\sqrt{x^2-2x}-x=t$, chúng ta thu được phương trình $3t^2-7t-6=0$, có nghiệm $t_1=3$ và $t_2=-\frac{2}{3}$. Căn bậc hai không cho lời giải của phương trình ban đầu, vì phạm vi của hàm số mũ là tập hợp tất cả các số dương. Do đó, phương trình ban đầu nằm trong phạm vi các giá trị được chấp nhận của phương trình tương đương chưa biết $3\sqrt{x^2-2x}-x=3^1$, và phương trình sau, dựa trên Định lý 1, cho phương trình vô tỷ

Cơm. 1.
Cơm. 2.
Cơm. 3.

$$\sqrt{x^2-2x}=x+1.$$

Bằng cách bình phương cả hai vế, chúng ta tìm được $x=-0,25$. Vì khi cả hai vế của phương trình được nâng lên lũy thừa chẵn, các nghiệm ngoại lai có thể xuất hiện nên việc xác minh là cần thiết và chỉ ở giai đoạn này. Việc thay thế giá trị tìm được của $x$ vào phương trình vô tỉ cho thấy rằng nó thỏa mãn giá trị đó và do đó, thỏa mãn phương trình ban đầu.

Trong hầu hết các trường hợp ngẫu nhiên, khó khăn chính lời giải của phương trình logarit hoặc hàm mũ là biến đổi phương trình ban đầu cho đến khi có thể áp dụng Định lý 1 hoặc 2. Nhưng khi làm như vậy, người ta phải theo dõi cẩn thận sự thay đổi trong OD. Thiếu điểm này thường dẫn đến sai sót trong lời giải.

Vì vậy, ví dụ, bằng cách sử dụng công thức logarit
$$\log_a xy=\log_a x+\log_a y,$$
$$\log_a \frac{x}{y}=\log_a x-\log_a y,$$
$$\log_a x^p=p\log_a x,$$
Người nộp đơn thường quên rằng ODZ bên trái và bên phải của họ không trùng nhau.

Thật vậy, các quy tắc phần khớp (1) và (2) được xác định cho các giá trị $x>0$ và $y>0$. Bất đẳng thức này được thỏa mãn bởi tọa độ của điểm lấp đầy góc tọa độ thứ nhất (Hình 1). Đồng thời, vế trái của sự tương ứng (1) và (2) có ý nghĩa khi dấu $x$ và $y$ trùng nhau.

Do đó, chẳng hạn, khi di chuyển từ biểu thức $\log_a xy$ sang biểu thức $\log_a x+\log_a y$, ODZ tồn tại (ở góc tọa độ thứ ba) và điều này có thể dẫn đến mất lời giải.

Vế phải của đẳng thức (3) chỉ được xác định cho $x>0$ và ODZ của vế trái phụ thuộc vào số mũ $p$. Nếu $p$ là một số nguyên thì vế trái của đẳng thức (3) cũng có ý nghĩa đối với âm $x$. Do đó, việc chuyển từ biểu thức $\log_a x^p$ sang biểu thức $p\log_a x$ cũng có thể dẫn đến mất lời giải.

⟦folio 53⟧

Các ví dụ tốt nhất về công thức logarit có dạng này:

$$\log_a xy = \log_a |x| + \log_a |y|,$$
(1a)
$$\log_a \frac{x}{y} = \log_a |x| - \log_a |y|,$$
(2a)

$$\log_a x^p = p \log_a |x| (p - \text{четное}).$$
(3a)

Bây giờ vế phải của công thức (1a) và (2a) được xác định tại $x \neq 0$ và $y \neq 0$. Các điều kiện này được thỏa mãn bởi tất cả các điểm của mặt phẳng tọa độ, ngoại trừ các điểm nằm trên trục (Hình 3) và khi chuyển từ biểu thức $\log_a xy$ sang biểu thức $\log_a |x| + \log_a |y|$ ODZ của ẩn số không tồn tại mà mở rộng (so sánh Hình 2 và Hình 3). Khả năng mất lời giải bị loại trừ, nhưng việc xây dựng rễ có thể xuất hiện. Và trong đẳng thức (3a) ODZ của bên phải và bên trái trùng nhau: $x \neq 0$.

Cách thứ hai để tránh thay đổi ODZ là chuyển từ một phương trình sang một hệ hoặc tập phương trình tương đương (bất đẳng thức). Như vậy, phương trình $\log_a \frac{x}{y} = c$ tương đương với tập phương trình $\log_a x - \log_a y = c$, $\log_a (-x) - \log_a (-y) = c$.

Bài 2. Giải phương trình

$$\lg (x + 10) + \frac{1}{2} \lg x^2 = 2 - \lg 4.$$

ODZ của người chưa biết: $x > -10, x \neq 0$. Vì $\frac{1}{2} \lg x^2 = \lg |x|$, chúng ta rút gọn phương trình về dạng $\lg (x + 10) + \lg |x| + \lg 4 = 2$, từ đó $\lg [4 |x| (x + 10)] = \lg 100$. Theo Định lý 2, phương trình cuối cùng tương đương với:

$$4 |x| (x + 10) = 100$$

(vì $100 > 0$, bất đẳng thức đúng). Xét hai trường hợp và giải phương trình tương ứng:

a) $x > 0, x^2 + 10x - 25 = 0$,
b) $-10 < x < 0, x^2 + 10x + 25 = 0$, ta tìm được hai nghiệm: $x_1 = -5 + 5\sqrt{2}, x_2 = -5$.

Thông thường lời giải phương trình hoặc hệ phương trình có thể được đơn giản hóa bằng cách đưa vào các biến mới.

Bài toán 3 (Trường Cao đẳng Kỹ thuật Thực vật tại ZIL, 1974). Giải phương trình

$$\left( \sqrt{7 + \sqrt{48}} \right)^x + \left( \sqrt{7 - \sqrt{48}} \right)^x = 14.$$

Hãy biểu thị $\left( \sqrt{7 + \sqrt{48}} \right)^x = u$, $\left( \sqrt{7 - \sqrt{48}} \right)^x = v$. Sau đó hệ thống

$$\left\{ \begin{array}{l} u + v = 14, \\ uv = 1 \end{array} \right.$$

tại $u > 0, v > 0$ sẽ tương đương với phương trình ban đầu. Cô ấy lời giải:

$$u_1 = 7 + \sqrt{48}, v_1 = 7 - \sqrt{48};$$
$$u_2 = 7 - \sqrt{48}, v_2 = 7 + \sqrt{48}.$$

Hãy viết $u_2$ và $v_2$ dưới dạng này: $u_2 = (7 + \sqrt{48})^{-1}, v_2 = (7 - \sqrt{48})^{-1}$. Quay lại biến ban đầu, chúng ta tìm thấy $x_1 = 2, x_2 = -2$.

Phương trình có dạng $[f(x)]^{\phi(x)} = [g(x)]^{h(x)}$ thường được giải bằng Định lý 2 về việc lấy logarit của phương trình về một cơ số nào đó.

Bài toán 4 (Viện Địa chất Mátxcơva, 1975). Giải phương trình

$$x^{\lg^2 x^2 - 3\lg x - 4,5} = 10^{-2\lg x}.$$

ODZ của người chưa biết: $x > 0$. Với ý nghĩ này, phương trình ban đầu tương đương với phương trình

$$\lg \left( x^{\lg^2 x^2 - 3\lg x - 4,5} \right) = \lg \left( 10^{-2\lg x} \right),$$

mà bằng cách thay thế $\lg x = t$ trùng với lập phương: $t (8t^2 - 6t - 5) = 0$ với các nghiệm $t_1 = 0, t_2 = 1, 25$ và $t_3 = -0, 5$. Quay lại biến ban đầu, chúng ta tìm thấy: $x_1 = 1, x_2 = 10\sqrt[4]{10}$ và $x_3 = \sqrt[10]{10}$.

Vấn đề 5 (Đại học bang Novosibirsk, 1974). Giải hệ phương trình

$$\left\{ \begin{array}{l} (x + y)^{\frac{1}{x-y}} = 2\sqrt{3}, \\ (x + y) \cdot 2^{y-x} = 3. \end{array} \right.$$

⟦folio 54⟧

Từ phương trình thứ hai suy ra $x + y > 0$. Do đó, tiếp tục gieo vần ở cơ số 2 và đặt $\log_2(x + y) = u$, $x - y = v$, ta được hệ
$$\begin{cases} \frac{u}{v} = 1 + 0, 5 \log_2 3, \\ u - v = \log_2 3, \end{cases}$$

trên bộ $x + y > 0$ tương đương với bộ ban đầu. Thay thế giá trị của $u$ từ phương trình thứ nhất vào phương trình thứ hai, chúng ta tìm thấy $v = 2$ và sau đó là $u = \log_2 12$. Quay trở lại các biến ban đầu và thế năng, chúng ta nhận được
$$\begin{cases} x - y = 2, \\ x + y = 12, \end{cases}$$

từ đâu $x = 7$, $y = 5$.

Lưu ý rằng việc sử dụng nhận dạng logarit cơ bản $a^{\log_a f(x)} = f(x)$ trong quá trình lời giải có thể dẫn đến sự xuất hiện của lời giải được xây dựng do sự mở rộng của ODZ.

Bài toán 6 (MIPT, 1975). Giải phương trình
$$9^{\log_3(1 - 2x)} = 5x^2 - 5$$.

Hãy biến đổi vế trái của phương trình, có tính đến các đặc tính và đồng nhất thức logarit cơ bản của bậc: $9^{\log_3(1 - 2x)} = (3^2)^{\log_3(1 - 2x)} = [3^{\log_3(1 - 2x)}]^2 = (1 - 2x)^2$. Phương trình $(1 - 2x)^2 = 5x^2 - 5$ là hệ quả không tương đương với phương trình ban đầu. Thật vậy, căn bậc nhất $x_1 = -2 - \sqrt{10}$ của nó thỏa mãn phương trình ban đầu, vì nó được bao gồm trong ODZ và căn bậc hai được xây dựng $x_2 = -2 + \sqrt{10}$ xuất hiện do việc mở rộng ODZ khi thay thế biểu thức $9^{\log_3(1 - 2x)}$, có ý nghĩa ở $x < 0,5$, với biểu thức $(1 - 2x)^2$, được xác định cho bất kỳ giá trị nào của đối số.

Bài toán 7 (MIPT, 1974; MAI, 1975). Giải phương trình
$$\log_3(\log_2 x - 9) = 2 + \log_3(1 - 4 \log_2 x)$$.

Vì $2 + \log_3(1 - 4 \log_2 x) = \log_3[9(1 - 4 \log_2 x)]$ nên theo lý thuyết
Rem 2 bất đẳng thức ban đầu tương đương với hệ
$$\begin{cases} \log_2 x - 9 = 9(1 - 4 \log_2 x), \\ \log_2 x - 9 > 0. \end{cases}$$

Vì $\log_2 x = t$ nên ta thu được hệ
$$\begin{cases} t^2 - 18t + 72 = 0, \\ t > 9, \end{cases}$$

lời giải từ đó $t = 12$, từ đó $x = 4096$. Lưu ý rằng nếu chúng ta giới hạn phương trình từ một hệ hỗn hợp không có bất đẳng thức thì nghiệm được xây dựng $x = 64$ sẽ xuất hiện.

Bài toán 8 (MSU, Khoa Địa lý, 1972; cao đẳng kỹ thuật thực vật tại ZIL, 1974). Giải hệ phương trình
$$\begin{cases} 2\log_4 x^2 + \log_0.2 y^3 = -1, \\ 2\log_4 x^4 - \log_0.2 y = 5. \end{cases}$$

Trong vùng giá trị chấp nhận được của ẩn số, được xác định bởi điều kiện $x \neq 0$ và $y > 0$, hệ thống này tương đương với hệ thống
$$\begin{cases} 4\log_4 |x| + 3\log_0.2 y = -1, \\ 8\log_4 |x| - \log_0.2 y = 5, \end{cases}$$

tương đối tuyến tính $\log_4 |x|$ và $\log_0.2 y$. Hệ thống này có lời giải $\log_4 |x| = 0,5$, $\log_0.2 y = -1$ duy nhất, từ đó $x = \pm 2$, $y = 5$. Nếu bỏ qua dấu của mô hình thì lời giải (-2; 5) sẽ bị mất khi lấy logarit.

Đôi khi, việc sử dụng công thức $b^{\log_a c} = c^{\log_a b}$ sẽ rất hữu ích, công thức này hợp lệ cho các giá trị dương $a$, $b$ và $c$ cũng như cho $a \neq 1$. Thật sự,
$b^{\log_a c} = (a^{\log_a b})^{\log_a c} = (a^{\log_a c})^{\log_a b} = c^{\log_a b}$

Bài toán 9 (Viện khai thác mỏ Moscow, 1975). Giải phương trình
$$5^{\lg x} = 50 - x^{\lg 5}$$.

Hãy tìm ODZ: $x > 0$. Dựa trên công thức đã xem xét $x^{\lg 5} = 5^{\lg x}$, do đó phương trình ban đầu bằng phương trình đơn lẻ $2 \cdot 5^{\lg x} = 50$, từ đó $5^{\lg x} = 5^2$, $\lg x = 2$, $x = 100$.

⟦folio 55⟧

Phương trình hàm mũ và logarit cũng có thể xuất hiện ở lời giải “kiểm tra” bài toán.

Bài toán 10 (Viện Công nghệ Điện tử Moscow, 1975). Tìm $x$ và $y$ nếu biết rằng $xy$, $x^x$ và $\frac{1}{y}$ là các số hạng liên tiếp của một quá trình hình học, $a$ log$_x(y+1)$, $-0.5$ và $\log_x(2-y)$ là một quá trình số học.

Điều kiện bài toán có thể được viết là
$$\begin{cases} x^{2x} = xy \cdot \frac{1}{y}, \\ \log_x(y+1) + \log_x(2-y) = -1. \end{cases}$$

Lời giải của hệ thống này, hãy tìm ra thứ xứng đáng nhất. Đáp số: $x = 0,5$; $y = 1$.

Bài toán 11 (LSU, Khoa Tâm lý học, 1970). Giải phương trình
$$\log_{\sqrt{2-x^2}}(2x^2+a) = 4.$$

Đây là một phương trình có tham số. Để giải nó có nghĩa là chỉ ra những giá trị nào của tham số lời giải tồn tại và chúng là gì. Đối với lời giải các phương trình như vậy, việc kiểm tra tính tương đương của phương trình đóng vai trò đặc biệt quan trọng vì việc xác minh thường khó khăn.

Đặt $x^2 = t$, chúng ta rút gọn phương trình về dạng
$$\log_{\sqrt{2-t}}(2t+a) = 4.$$

Phương trình cuối cùng tương đương với phương trình ban đầu (có thể thay đổi $x^2 = t$) cho $t \geq 0$. Trong ODZ, chúng tôi xác định các tương ứng $2-t > 0$, $2-t \neq 1$, $2t+a > 0$, nó tương đương với phương trình $2t+a=(2-t)^2$, có gốc $t_1=3+\sqrt{5+a}$, $t_2=3-\sqrt{5+a}$. Những gốc này tồn tại ở $a \geq -5$. Gốc $t_1$ không được bao gồm trong ODZ tại bất kỳ $a$ nào và gốc $t_2$ được bao gồm tại $-4 < a < -1$ và $a > -1$. Bất bình đẳng $t_2 \geq 0$ giữ nguyên cho $a \leq 4$ (kiểm tra!). Quay trở lại biến ban đầu, chúng ta nhận được:
$$x = \pm \sqrt{3-\sqrt{5+a}}$$

tại $-4 < a < -1$, $-1 < a \leq 4$; với phần còn lại $a$ lời giải không.

Bất bình đẳng

Các định nghĩa cơ bản cần thiết cho các bất đẳng thức lời giải gần như giống với định nghĩa tương ứng cho phương trình. Mọi điều đã nói ở trên về các phép biến đổi làm thay đổi ODZ cũng đúng với bất đẳng thức. Tuy nhiên, bất đẳng thức lời giải có những đặc điểm riêng và đòi hỏi phải có kiến ​​thức tốt về các tính chất của các hàm chứa trong chúng. Đặc biệt, phải nhớ rằng các tính chất của hàm số mũ và hàm logarit là khác nhau đối với các cơ số lớn hơn hoặc nhỏ hơn một: đối với $a > 1$, hàm $y = a^x$ và $y = \log_a x$ tăng đơn điệu, và đối với $0 < a < 1$, hàm $y = a^x$ và $y = \log_a x$ giảm đơn điệu.

Các định lý quan trọng rút ra từ những tính chất này.

Định lý 3. Bất đẳng thức $a^{f(x)} < a^{\varphi(x)}$ với $0 < a < 1$ tương đương với bất đẳng thức $f(x) > \varphi(x)$, và với $a > 1$ tương đương với bất đẳng thức $f(x) < \varphi(x)$.

Định lý 4. Bất đẳng thức $\log_a f(x) < \log_a \varphi(x)$ cho $0 < a < 1$ tương đương với hệ bất đẳng thức
$$\begin{cases} f(x) > \varphi(x), \\ \varphi(x) > 0, \\ a \neq 1 \text{ и } a > 1 \end{cases}$$

Bất đẳng thức dạng $\log_a f(x) > c$ và $a^{f(x)} > d$ ($d > 0$); cùng nhau > có thể đứng $\leq$, <, <=) có thể được đưa về dạng được xem xét trong Định lý 3 và 4 bằng cách sử dụng các công thức $c = \log_a a^c$ và $d = a^{\log_a d}$.

Bài toán 12 (Viện Dệt May Moscow, 1974). Giải bất đẳng thức
$$3^{2x+5} \leq 3^{x+2} + 2.$$

Lưu ý rằng $3^{2x+5} = 3 \cdot 3^{2(x+2)}$. Bằng cách đặt $3^{x+2} = t(t > 0)$, tiếp nhận vào

⟦folio 56⟧

bất bình đẳng $3t^2 - t - 2 \leqslant 0$. Nó thỏa mãn $-\frac{2}{3} \leqslant t \leqslant 1$. Bất đẳng thức $3x^2 \geqslant -\frac{2}{3}$ đúng với mọi số thực $x$. Chúng ta biểu diễn 1 dưới dạng $3^0$, sau đó từ bất đẳng thức $3x^2 \leqslant 3^0$ theo Định lý 3, chúng ta tìm thấy $x \leqslant -2$.

Đối với các bất đẳng thức hàm mũ và logarit lời giải, phương pháp tích phân thường được sử dụng.

Bài toán 13 (Viện khai thác mỏ Moscow, 1975). Giải bất đẳng thức
$$\log_2^4 x - \log_0.5^2 \frac{x^3}{8} + 9 \log_2 \frac{32}{x^2} <
< 4\log_0.5^2 x.$$
ODZ của bất đẳng thức có dạng $x > 0$. Lưu ý rằng trong ODZ
$$\log_0.5 \frac{x^3}{8} = \log_2 \frac{8}{x^3} = 3(1 - \log_2 x),$$
$$\log_2 \frac{32}{x^2} = 5 - 2\log_2 x,$$
$$\log_0.5 x = -\log_2 x,$$
Về mặt bất đẳng thức ban đầu tương đương với bất đẳng thức sau:
$$\log_2^4 x - 13 \log_2^2 x + 36 < 0.$$
Đặt $\log_2 x = t$, sau khi phân tích nhân tử ta thu được bất đẳng thức $(t + 3)(t + 2)(t - 2)(t - 3) < 0$. lời giải của anh ấy (xem Hình 4): $-3 < t < -2$, $2 < t < 3$. Hãy quay lại biến ban đầu: $-3 < \log_2 x < -2$, $2 < \log_2 x < 3$, từ đó: $0,125 < x < 0,25$ và $4 < x < 8$.

Bài toán 14 (Viện Kỹ thuật Điện tử Moscow, 1974). Giải bất đẳng thức
$$0,3^{\log_0.25 \log_2 \frac{3x+6}{x^2+2}} > 1.$$
Theo Định lý 3, bất đẳng thức này
$$\log_0.25 \log_2 \frac{3x+6}{x^2+2} < 0,$$
và cái cuối cùng của bất đẳng thức $\log_2 \frac{3x+6}{x^2+2} > 1$, từ đó $\frac{3x+6}{x^2+2} > 2$. Nhân cả hai vế với $x^2 + 2$ (biểu thức này dương với mọi số thực $x$), chúng ta nhận được $2x^2 - 3x - 2 < 0$ hoặc $2(x+0,5)(x-2) < 0$, do đó $-0,5 < x < 2$.

Đối với các bất đẳng thức lời giải chứa tham số hoặc ẩn số trong cơ số logarit hoặc lũy thừa, cần xem xét riêng tích phân $(0; 1)$ và $(1; +\infty)$ của giá trị cơ sở.

Bài toán 15 (Viện trắc địa Moscow, Kỹ sư chụp ảnh trên không và bản đồ, 1975). Giải bất đẳng thức
$$(x^2 - x + 2)^{\log_0.6 \frac{2x-3}{x+1}} > 1.$$
Vì cơ số bậc $x^2 - x + 2$ dương với mọi giá trị thực $x$ (kiểm tra!), nên bất đẳng thức này tương đương với tổng của hệ
$$\left\{ \begin{array}{l l} x^2 - x + 2 < 1, \\ \log_0.6 \frac{2x-3}{x+1} < 0, \\ \log_0.6 \frac{2x-3}{x+1} > 0. \end{array} \right.$$
Trong tập hợp các số thực, bất đẳng thức $x^2 - x + 2 < 1$ không có lời giải và bất đẳng thức $x^2 - x + 2 > 1$ thỏa mãn mọi $x$ (chứng minh đi!). Do đó, hệ lời giải không có và bất đẳng thức thứ hai không có
$$\log_0.6 \frac{2x-3}{x+1} > 0, \text{ т. е. } 0 < \frac{2x-3}{x+1} < 1.$$

Cơm. 5.

⟦folio 57⟧

Chuyển đổi những bất bình đẳng này vào hệ thống
$$\begin{cases} (x+1)(x-1,5)>0, \\ (x+1)(x-4)<0, \end{cases}$$

Hãy giải nó bằng phương pháp tích phân (Hình 5). Đáp số: $1.5<x<4$.

Cuối cùng, hãy xem xét các bất đẳng thức lời giải với một tham số.
Bài toán 16 (MNET, 1975). Tìm tất cả các giá trị của tham số $a$ mà bất đẳng thức
$$\log_{a+x}[x(a-x)]<\log_{a+x}x$$
có ít nhất một lời giải.

Trong vùng giá trị cho phép của ẩn số $x$ và tham số $a$, ta xác định điều kiện $x>0, a+x>0, a-x>0, a+x\neq1$, bất đẳng thức tương đương như sau: $$\log_{a+x}(a-x)<0.$$

Bất đẳng thức sau đây, có tính đến ODZ, tương đương với tập hợp hai hệ bất đẳng thức:

$$\begin{cases} x>0, \\ x>-a, \\ x<a, \\ a+x>1, \\ a-x<1, \end{cases}$$

Chúng ta vẽ các đường thẳng $x=0, x=-a, x=a, x=1-a$ và $x=a-1$ trong hệ tọa độ thẳng (Hình 6). Mỗi đường thẳng chia mặt phẳng tọa độ thành hai nửa mặt phẳng, trong đó một nửa mặt phẳng thỏa mãn bất đẳng thức tương ứng, còn ở nửa mặt phẳng kia và trên chính đường thẳng đó không thỏa mãn. Ối-
