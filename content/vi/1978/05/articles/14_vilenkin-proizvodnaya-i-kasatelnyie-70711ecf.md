---
id: 1978-5-vilenkin-proizvodnaya-i-kasatelnyie-70711ecf
issue: kvant_1978_5
year: 1978
number: "5"
title: Đạo hàm và tiếp tuyến
authors:
  - Виленкин А. Н.
rubric: praktikum-abiturienta
rubric_sub: Практикум абитуриента
page_first: 46
page_last: 48
page_labels: 44-46
tag: JL9J
lang: vi
source: kvant_digital
extraction: vision
content_sha256: 782c06cfc85eb822413b29e26f50ec863a15ce3876b01f0af35bf25de9f72bcd
prompt_sha256: draft-1
translated_from: content/ru/1978/05/articles/14_vilenkin-proizvodnaya-i-kasatelnyie-70711ecf.md
source_content_sha256: bff1bc0d014a4dbb62f6296d709e44730740714a576066762f93470ea64e966a
translation_model: draft
translation_run: vi-draft-2026-10-31
translation_quality: draft
---

⟦folio 44⟧

A. Vilenkin

Đạo hàm và tiếp tuyến

Mặc dù trong khóa học toán ở trường chỉ có một đoạn dành cho tiếp tuyến của đồ thị hàm số (xem “Đại số và sự khởi đầu của phân tích,” lớp 9, đoạn 52), vào năm 1977, tại kỳ thi tuyển sinh đại học (đối với chương trình “A”), nhiều bài toán liên quan đến chủ đề này đã được đưa ra. Lời giải Hầu hết chúng đều dựa trên việc sử dụng phương trình
$$y = f'(x_0) \cdot x + (f(x_0) - f'(x_0)) \cdot x_0$$
 tiếp tuyến với đồ thị của hàm $y = f(x)$ tại điểm có hoành độ $x_0$ (Hình 1). Thú vị hơn bài toán dựa trên thực tế là hệ số góc $k$ của tiếp tuyến, một mặt, bằng tiếp tuyến của góc $\varphi$ giữa tiếp tuyến và trục hoành, mặt khác, bằng giá trị tùy ý $f'(x_0)$. Chúng ta hãy xem xét một số loại như vậy bài toán *).

Tìm phương trình tiếp tuyến

Ví dụ 1 (MEIS, 1977). Phương trình quốc gia tiếp tuyến của đồ thị hàm số $f(x) = 4 - x^2$ tại các giao điểm của điểm này mà tại đó $f = 0$, vì vậy để tìm $x_0$ người ta phải giải phương trình $4 - x_0^2 = 0$. Sau đó, với mỗi giá trị của $x_0$, phương trình tiếp tuyến có thể được viết theo cách chuẩn. Hãy làm điều này, có tính đến $f'(x) = -2x$.

a) $x_0 = 2$; $f(2) = 0$, $f'(2) = -4$, phương trình tiếp tuyến $y = -4x + 8$;
b) $x_0 = -2$; $f(-2) = 0$, $f'(-2) = 4$, phương trình tiếp tuyến $y = 4x + 8$.

Tìm k và góc

Ví dụ 2 (MISI, 1977). Mỗi mẫu có trục x tiếp xúc với parabol $y = x^2 - 4x - 17$, được xét nghiệm trong nước tiểu có trục x $x_0 = 2,5$?

Ở đây, góc của một đường thẳng với trục $Ox$ có nghĩa là giá trị của góc không có trên trục $Ox$ với đường thẳng này ngược chiều kim đồng hồ (xem “Đại số 6”, đoạn 52, “Hình học 8”, đoạn 98 và “Đại số và sự khởi đầu của phân tích”, lớp 10, tài liệu ôn tập, đoạn 8). Vì chúng ta được cho $f$ và $x_0$, chúng ta có thể tìm thấy $k = f'(x_0)$, và từ đó có được góc mong muốn $\varphi$, vì tiếp tuyến của góc tạo bởi đường thẳng với trục $Ox$ bằng hệ số góc của đường thẳng này: $tg\varphi = k$ và $\varphi = \arctg k$ tại $k \geq 0$ và $\varphi = \pi + \arctg k$ tại $k < 0$ (Hình 2).

Trong ví dụ này, $f'(x) = 2x - 4$, $k = f'(2,5) = 1$, $tg\varphi = 1$, $\varphi = \pi/4$.

Ví dụ 3. Tên các phương trình tiếp xúc với đồ thị của hàm số $f(x) = x^3 - 4x^2 + 3x + 1$, xét nghiệm trong nước tiểu có hoành độ $0$ và $1$.

Ở đây sàng không phải là về góc của một đường thẳng với trục $Ox$ mà là về góc của hai đường thẳng. Do đó, chúng ta hãy nhớ lại rằng phương trình của hai đường thẳng giao nhau được gọi là giá trị góc nhỏ hơn được xác định bởi đường thẳng này (xem “Hình học 9”, § 24), tức là góc $\alpha$ giữa hai đường thẳng luôn nằm trong $0 \leq \alpha \leq \pi/2$.

Trong ví dụ này, $f'(x) = 3x^2 - 8x + 3$ và đối với tiếp tuyến đầu tiên, chúng ta có $x_0 = 0$, $f(0) = 1$, $f'(0) = 3$, $k_1 = tg\varphi_1 = 3$, $\varphi_1 = \arctg 3$, phương trình tiếp tuyến là $y = 3x + 1$ và đối với tiếp tuyến thứ hai $x_0 = 1$, $f(1) = 1$, $f'(1) = -2$, $k_2 = tg\varphi_2 = -2$, $\varphi_2 = \pi - \arctg 2$, phương trình tiếp tuyến $y = -2x + 3$. Sau đó, bằng cách vẽ gần đúng (Hình 3), bạn có thể dễ dàng tìm được góc $\alpha = \pi - \arctg 2 - \arctg 3$.

⟦folio 45⟧

No, it's not clear what you're asking for. It looks like a list of equations or formulas.
Chúng ta hãy đọc lại dòng đầu tiên: "Nhưng liệu góc này có phải là góc mong muốn không, tức là có đúng là $\alpha \leq \pi/2$, hay nên có một góc $\pi - \alpha$? Có vẻ như góc $\alpha$ là góc mong muốn (vì arctg $2 > \pi/4$ và arctg $3 > \pi/4$), nhưng bây giờ chúng ta sẽ hành động khác."
Dòng thứ hai: “Hãy suy ra công thức tổng quát về góc giữa hai đường thẳng $y = k_1x + b_1$ Và $y = k_2x + b_2$. Trước hết, chúng ta lưu ý rằng trong quá trình dịch song song, các góc không thay đổi, do đó góc mong muốn $\alpha$ bằng góc giữa hai đường thẳng $y = k_1x$ Và $y = k_2x$ (chúng được lấy từ dữ liệu bằng cách chuyển $\overrightarrow{CO}$). Gọi góc giữa các đường thẳng này và trục $Ox$ bình đẳng $\varphi_1$ Và $\varphi_2$ (Hình 4). Khi đó dễ dàng tìm được độ lớn của một trong các góc bên của đường thẳng đã cho: $|\varphi_2 - \varphi_1|$ (phải đặt biển báo mẫu vì chúng tôi không biết góc nào $\varphi_2$, $\varphi_1$ hơn). Góc mong muốn là một trong các góc $|\varphi_2 - \varphi_1|$, $\pi - |\varphi_2 - \varphi_1|$, không vượt quá $\pi/2$."
Dòng thứ ba: "Hóa ra việc lấy tiếp tuyến của các góc này là thuận tiện, vì theo công thức rút gọn"
Dòng thứ tư: "tg ($\pi - |\varphi_2 - \varphi_1|$) = -tg|$\varphi_2 - \varphi_1$| (nếu $|\varphi_2 - \varphi_1| \neq \pi/2$) và nếu $|\varphi_2 - \varphi_1| > \pi/2$ thì"
The fifth line: "tg $\alpha =$ tg ($\pi - |\varphi_2 - \varphi_1|$) ="
The sixth line: "= -tg|$\varphi_2 - \varphi_1$| = |tg|$\varphi_2 - \varphi_1$| |="
The seventh line: "= |tg($\varphi_2 - \varphi_1$)|"
Dòng thứ tám: "(vì tg là hàm lẻ); nếu $|\varphi_2 - \varphi_1| < \pi/2$, thì"
Dòng thứ chín: "tg $\alpha =$ tg|$\varphi_2 - \varphi_1$|, cũng bằng |tg($\varphi_2 - \varphi_1$)|."
Dòng thứ mười: "Như vậy, công thức tg $\alpha$ = |tg($\varphi_2 - \varphi_1$)| đúng trong mọi trường hợp. Nhắc lại công thức tiếp tuyến hiệu của hai góc, ta có:"
The eleventh line: "tg $\alpha$ = |$\frac{k_2 - k_1}{1 + k_2k_1}$|."
Dòng thứ mười hai: "Lưu ý rằng sự phân bố quá mức của hai đường thẳng cũng dễ dàng được phát hiện bởi hệ số góc của chúng: nếu $|\varphi_2 - \varphi_1| = \pi/2$ thì $\varphi_2 = \varphi_1 + \pi/2$ hoặc $\varphi_2 = \varphi_1 - \pi/2$, và trong cả hai trường hợp tg $\varphi_2 = -$ tg $\varphi_1 = -\frac{1}{tg\varphi_1}$"
Dòng thứ mười ba: "(nếu các biểu thức này được xác định), đó là tg $\varphi_2 \cdot$ tg $\varphi_1 = -1$ và ở dạng hệ số góc"
The fourteenth line: "$k_2k_1 = -1$."
Dòng thứ mười lăm: "Điều này phù hợp với những gì có trong công thức"
Dòng thứ mười sáu: "các phương trình với nội dung trong công thức"

Picture 1:
$$\begin{align*}
y &= f(x) \\
M_0(x_0, f(x_0))
\end{align*}$$

Picture 2:
$$k > 0, \varphi = \arctg k; k < 0, \varphi = \pi + \arctg k.$$

Picture 3:
$$\begin{align*}
y &= kx + b \\
M_1 \\
M_2
\end{align*}$$

Picture 4:
$$\begin{align*}
y &= kx + b \\
M_1 \\
M_2
\end{align*}$$

⟦folio 46⟧

tg α phần bên phải không được xác định nếu $k_1 k_2 + 1 = 0$.

Có một trường hợp khác khi hai đường thẳng vuông góc - nếu phương trình của các đường thẳng này có dạng $y = b$, $x = a$. Trong trường hợp này, $k_1 = 0$ và $k_2$ không tồn tại, vì đường thẳng $x = a$ song song với trục tọa độ.

Trong ví dụ 3, chúng tôi nhận được:

$$\text{tg} \alpha = \left| \frac{-2 - 3}{1 - 6} \right| = 1, \quad \alpha = \frac{\pi}{4}.$$

Hãy so sánh đáp số này với cái ở trên!

Xác định điểm đồ thị dọc theo tiếp tuyến

Trong một số bài toán, một số điều kiện về tiếp tuyến được cho dưới dạng này hay dạng khác và yêu cầu tìm các điểm tiếp tuyến.

Ví dụ 4. Tên trên đồ thị của hàm số $f(x) = 3x^3 - 4x^2 + 1$ là lũy thừa, tiếp tuyến tạo bởi trục Ox giếng $\pi/4$.

Để góc tiếp tuyến với trục Ox bằng $\pi/4$ thì hệ số góc của tiếp tuyến phải bằng 1. Nhưng $k = f'(x_0)$, tức là chúng ta cần giải phương trình $f'(x_0) = 1$, tức là $9x_0^2 - 8x_0 = 1$. Từ đó, sử dụng công thức nghiệm của phương trình bậc hai $x_0 = 1$ hoặc $x_0 = -1/9$. Tại các điểm này $f(1) = 0$, $f(-1/9) = 230/243$. Điều này có nghĩa là có hai điểm bắt buộc: $M_1(-1/9; 230/243)$ và $M_2(1; 0)$, điểm này phù hợp trên biểu đồ của hàm này (Hình 5).

Ví dụ 5. Tiếp tuyến của hàm số $f(x) = x^2$ tại điểm nào

a) song song với đường thẳng $2x - y + 1 = 0$;

b) vuông góc với một đường thẳng?

a) Như đã biết (xem “Đại số 6”, đoạn 52), hai đường thẳng song song nếu hệ số góc bằng nhau. Phương trình của đường thẳng này có thể được viết dưới dạng $y = 2x + 1$, biểu thị rằng $k = 2$. Đối với tiếp tuyến $k = f'(x_0)$, vì vậy chúng ta cần giải phương trình $f'(x_0) = 2$, tức là $2x_0 = 2$, do đó $x_0 = 1$. Điều này có nghĩa là tiếp tuyến phải được vẽ tại điểm $M_1(1; 1)$ (Hình 6). Kiểm tra cho thấy phương trình của tiếp tuyến này là $y = 2x - 1$.

6) Chúng ta hãy sử dụng thực tế là các đường thẳng $y = k_1 x + b_1$ và $y = k_2 x + b_2$ vuông góc nếu $k_1 k_2 = -1$. Trong ví dụ này, $k_1 = 2$, do đó, $k_2 = -1/k_1 = -1/2$, và từ phương trình $2x_0 = -1/2$, chúng ta tìm thấy $x_0 = -1/4$. Điều này tương ứng với điểm $M_2(-1/4; 1/16)$ và phương trình tiếp tuyến là $y = -1/2 x - 1/16$. “Hình học” của ví dụ này được thể hiện rõ ràng trong Hình 6.

Ví dụ 6 (MSU, Khoa Tâm lý học, 1977). Trên đồ thị của hàm $\frac{1}{3} x^3 - 2x^2 - 22x - 28$, hãy tìm tất cả các điểm sao cho các tiếp tuyến của đồ thị tại các điểm này cắt các bán trục dương, cắt các đoạn có độ dài bằng nhau khỏi chúng.

Vẽ tiếp tuyến tại điểm $M_0(x_0; f(x_0))$. Khi đó phương trình của nó có dạng

$$y = \left(x_0^2 - 4x_0 - 22\right) \cdot x - \frac{2}{3} x_0^3 + 2x_0^2 - 28.$$

Không có đường thẳng $y = kx + b$ nào cắt các bán trục dương cắt các đoạn có độ dài bằng nhau, chỉ tại $k = -1$ và $b > 0$ (b≠ 0, vì
