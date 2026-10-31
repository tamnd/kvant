---
id: 1971-9-atamukas-kvadratnyiy-trehchlen-c7b06136
issue: kvant_1971_9
year: 1971
number: "9"
title: Tam thức bậc hai
authors:
  - Атамукас М. С.
rubric: praktikum-abiturienta
rubric_sub: Практикум абитуриента
page_first: 43
page_last: 48
page_labels: 41-46
tag: JMQM
lang: vi
source: kvant_digital
extraction: vision
content_sha256: 0bed7af5b89f1bd65351b7f3f0abdd48766157a00e968de6723c402bb787e8a6
prompt_sha256: 3ec6b8aabd9b98576af76503cd8a2902b9f5d18e01ee867dfb1228f59c6d52d8
translated_from: content/ru/1971/09/articles/08_atamukas-kvadratnyiy-trehchlen-c7b06136.md
source_content_sha256: 590b3ec0adb9053eb3eb4ffa9c54a377c5a76b9f500d14a488f10a10c5083a8f
translation_model: gpt-5.6-terra
translation_run: vi-codex-2026-10-31
---

⟦folio 41⟧

M. S. Atamukas

Tam thức bậc hai được gọi là đa thức bậc hai dạng tổng quát

$$ax^2 + bx + c, \quad a \neq 0.$$

Trong các kỳ thi tuyển sinh môn toán, những bài toán liên quan trực tiếp hoặc gián tiếp đến tam thức bậc hai được đưa ra khá thường xuyên. Điều đó cũng không có gì đáng ngạc nhiên — trong chương trình phổ thông, rất nhiều chỗ và thời gian được dành cho việc nghiên cứu phương trình bậc hai

$$ax^2 + bx + c = 0,$$

và tìm hiểu các tính chất của hàm số bậc hai

$$y = ax^2 + bx + c.$$

Hàm số này cũng gặp trong vật lý; chẳng hạn, khi mô tả chuyển động của một chất điểm được ném xiên so với phương ngang.

Học sinh, dĩ nhiên, biết rõ mọi công thức liên quan đến tam thức bậc hai, và cũng biết vẽ đồ thị của hàm số bậc hai — parabol. Tuy nhiên, khi phải giải một bài toán cụ thể, phần lớn thường cố gắng hành động thuần túy bằng phương pháp giải tích, chỉ dùng các công thức. Trong khi đó, rất thường việc sử dụng các lập luận hình học cho phép nhận được đáp án đơn giản hơn và nhanh hơn.

Chúng tôi sẽ chỉ ra bằng vài ví dụ rằng khi giải bài toán, việc đồng thời tư duy bằng cả ngôn ngữ đại số lẫn hình học quan trọng như thế nào.

Để kiểm tra xem bạn đã quen thuộc đến mức nào với các tính chất của tam thức bậc hai, trước hết hãy xét bài toán sau đây (bài này đã được đưa ra trong các kỳ thi vấn đáp ở Đại học Tổng hợp Moskva).

1. Trên hình 1 vẽ một số đồ thị của các tam thức bậc hai. Hình vẽ chỉ gần đúng, không chỉ tỉ lệ. Với mỗi parabol đó, hãy xác định dấu của các hệ số tương ứng $a, b$ và $c$.

Chẳng hạn, lấy parabol 4; nó là đồ thị của một hàm số bậc hai nào đó

$$f(x) = ax^2 + bx + c.$$

Vì các nhánh của parabol này hướng lên trên, nên hệ số $a > 0$. (Hãy chứng min-! Nhiều thí sinh giải thích điều này như sau: «Trong sách giáo khoa đã chứng-

⟦folio 42⟧

ra rằng nếu $a > 0$ thì parabol hướng lên trên». Lập luận như vậy có thuyết phục không?). Tiếp theo, hệ số $c$ bằng giá trị của hàm số $y$ tại điểm $x = 0$, tức là $c = f(0)$. Từ hình vẽ thấy rằng parabol 4 cắt nửa trục tung dương, do đó $c > 0$. Hoành độ đỉnh của parabol bằng $-\frac{b}{2a}$; từ hình vẽ rõ ràng rằng nó dương. Ta đã biết rằng $a > 0$, và do đó $b < 0$.

Đáp số: $a > 0$, $b < 0$, $c > 0$.

Các trường hợp còn lại, được trình bày ở hình 1, bạn đọc có thể tự xem xét.

Trong nhiều bài toán cần xác định sự biến thiên của hàm bậc hai $f(x) = ax^2 + bx + c$ trên khoảng đã cho $(\alpha, \beta)$, mô tả vị trí các nghiệm của tam thức này đối với điểm cố định $x = \gamma$ trên trục hoành, v.v. Trong những bài toán này, ngôn ngữ hình học làm cho các lập luận trở nên đơn giản và trực quan (mà vẫn hoàn toàn chặt chẽ!).

2. Trên trục hoành cho khoảng $\alpha < x < \beta$. Với những $a$, $b$ và $c$ nào thì phương trình

$$ax^2 + bx + c = 0, \ a \neq 0, \ b^2 - 4ac > 0$$

có đúng một nghiệm trong khoảng này?

Nói cách khác, cần выяснить với những $a$, $b$ và $c$ nào thì đồ thị hàm số $f(x) = ax^2 + bx + c$ cắt trục hoành trong khoảng $\alpha < x < \beta$ đúng một lần.

Nếu giải quyết vấn đề này bằng phương pháp giải tích, dùng các công thức nghiệm $x_1$ và $x_2$ của tam thức bậc hai, thì các điều kiện để chỉ một nghiệm nằm giữa các số $\alpha$ và $\beta$ được viết ra khá cồng kềnh. Cách tiếp cận hình học cho phép nhận được điều kiện này ngay và dưới dạng đơn giản.

Hãy hình dung đồ thị của tam thức thỏa mãn điều kiện nêu trong bài toán có thể có dạng như thế nào; rõ ràng, có thể có một trong bốn vị trí được trình bày trên hình 2. Hơn nữa, nhận thấy rằng trong mỗi trường hợp này, các giá trị của hàm số $f(x)$ tại các điểm $\alpha$ và $\beta$ có dấu trái nhau, tức là

$$f(\alpha)f(\beta) < 0,$$

hay, chi tiết hơn,

$$(a\alpha^2 + b\alpha + c)(a\beta^2 + b\beta + c) < 0.$$

Điều kiện này là cần và đủ để phương trình $ax^2 + bx + c = 0$ (với $a \neq 0, b^2 - 4ac > 0$) có đúng một nghiệm trên khoảng $(\alpha, \beta)$.

⟦folio 43⟧

Vậy là các đồ thị đã giúp ta tìm được điều kiện này. Chúng cũng gợi cho ta cách chứng minh rằng điều kiện này là cần và đủ.

Tính cần thiết. Giả sử phương trình có hai nghiệm $x_1$ và $x_2$ ($x_1 < x_2$), trong đó một nghiệm nằm trong khoảng $(\alpha, \beta)$, còn nghiệm kia nằm ngoài khoảng đó. Khi đó một trong hai số $\alpha, \beta$ nằm trong khoảng $(x_1, x_2)$, còn số kia nằm ngoài khoảng ấy. Nhưng trong sách giáo khoa phổ thông chứng minh rằng các giá trị của hàm số $f(x) = ax^2 + bx + c$ ở ngoài khoảng $(x_1, x_2)$ giữa hai nghiệm và các giá trị của hàm số ở trong khoảng này có dấu trái ngược nhau. Do đó, $f(\alpha) f(\beta) < 0$.

Điều đó là đủ. Giả sử các số $f(\alpha)$ và $f(\beta)$ có dấu khác nhau. Khi đó $b^2 - 4ac > 0$, phương trình $ax^2 + bx + c = 0$ có hai nghiệm $x_1$ và $x_2$, và các giá trị của hàm số bên trong khoảng $(x_1, x_2)$ và bên ngoài khoảng đó có dấu trái nhau. Vì vậy chỉ một trong hai số $\alpha, \beta$ nằm bên trong khoảng $(x_1, x_2)$. Nhưng điều này, đến lượt nó, có nghĩa là chỉ một trong hai số $x_1, x_2$ nằm bên trong khoảng $(\alpha, \beta)$.

Rõ ràng rằng hàm bậc hai

$$y = ax^2 + bx + c, \quad a \neq 0, \quad b^2 - 4ac = 0,$$

chỉ có một nghiệm $x_0 = -\frac{b}{2a}$, và nó nằm trong khoảng $(\alpha, \beta)$ nếu $\alpha < -\frac{b}{2a} < \beta$.

Hãy áp dụng các nhận xét vừa nêu để giải bài toán sau đây, lấy từ thực hành các kỳ thi vấn đáp.

3. Chứng minh rằng tam thức bậc hai

$$f(x) = (x - a)(x - b) + \lambda (x - c)(x - d)$$

có các nghiệm thực với mọi $\lambda$ thực, nếu biết rằng đúng một trong hai số $c, d$ nằm trong khoảng $(a, b)$, còn số kia nằm ngoài khoảng đó.

Quan sát đồ thị của các tam thức bậc hai khác nhau, dễ nhận thấy một tính chất quan trọng: các giá trị lớn nhất và nhỏ nhất của tam thức bậc hai trên đoạn $[\alpha, \beta]$ chỉ có thể đạt được tại ba điểm sau: tại điểm $x = -\frac{b}{2a}$, nếu dĩ nhiên nó thuộc đoạn $[\alpha, \beta]$; tại điểm $\alpha$; tại điểm $\beta$ (ở các đầu mút của đoạn). Hãy chứng minh điều này; ta sẽ giả sử rằng $a > 0$ (trường hợp $a < 0$ được xét tương tự).

Tách bình phương hoàn chỉnh từ tam thức bậc hai:

$$f(x) = ax^2 + bx + c = a \left( x + \frac{b}{2a} \right)^2 + c - \frac{b^2}{4a}.$$

Dùng cách viết này, không khó để chỉ ra rằng khi $a > 0$ hàm số $f(x)$ tại điểm $x = -\frac{b}{2a}$ có giá trị nhỏ nhất tuyệt đối bằng $c - \frac{b^2}{4a}$; trên khoảng $(-\infty, -\frac{b}{2a})$ giảm đơn điệu, còn trên khoảng $(-\frac{b}{2a}, \infty)$ tăng đơn điệu.

*) Tự kiểm tra rằng từ $f(\alpha) f(\beta) < 0$ suy ra $b^2 - 4ac > 0$.

⟦folio 44⟧

Vì vậy, nếu
$$\alpha \leq -\frac{b}{2a} \leq \beta,$$
thì hàm số $f(x)$ trên đoạn $[\alpha, \beta]$ nhận giá trị nhỏ nhất $c - \frac{b^2}{4a}$ tại điểm $-\frac{b}{2a}$ (xem đồ thị 1 trên hình 3).

Giá trị lớn nhất, do tính đơn điệu, đạt được tại một trong các đầu mút của khoảng.

Bây giờ giả sử điểm $-\frac{b}{2a}$ nằm ngoài đoạn $[\alpha, \beta]$ (xem đồ thị 2, 3 trên hình 3).

Khi đó đoạn $[\alpha, \beta]$ nằm trong một trong các khoảng đơn điệu, và vì thế giá trị nhỏ nhất đạt được ở một đầu của nó, còn giá trị lớn nhất — ở đầu kia.

Hãy thử bây giờ phát biểu điều kiện cần và đủ để phương trình bậc hai $ax^2 + bx + c = 0$ có hai nghiệm trên khoảng đã cho $\alpha < x < \beta$.

Tính chất đã nhận thấy của tam thức bậc hai sẽ giúp ta giải các bài toán sau.

4. (Đại học Tổng hợp Moskva, cơ khí, 1970). Với những giá trị nào của tham số $\alpha$ thì bất đẳng thức
$$\sin^6 x + \cos^6 x + \alpha \sin x \cos x \geq 0$$
đúng với mọi $x$?

Biến đổi vế trái của bất đẳng thức:
$$(\sin^2 x)^3 + (\cos^2 x)^3 + \alpha \sin x \cos x =$$
$$= (\sin^2 x + \cos^2 x) (\sin^4 x - \sin^2 x \cos^2 x + \cos^4 x) + \alpha \sin x \cos x =$$
$$= [(\sin^2 x + \cos^2 x)^2 - 3 \sin^2 x \cos^2 x] + \alpha \sin x \cos x =$$
$$= 1 - \frac{3}{4} \sin^2 2x + \frac{\alpha}{2} \sin 2x.$$

Đặt $\sin 2x$ là $y$; hiển nhiên, $-1 \leq y \leq 1$, hệ số của $y^2$ âm, vì vậy trên đoạn $[-1; 1]$ tam thức bậc hai $-\frac{3}{4} y^2 + \frac{\alpha}{2} y + 1$ đạt giá trị nhỏ nhất tại các đầu mút của đoạn.

Do đó, bất đẳng thức
$$-\frac{3}{4} y^2 + \frac{\alpha}{2} y + 1 \geq 0$$
đúng trên toàn bộ đoạn $[-1; 1]$ khi và chỉ khi tam thức không âm tại các đầu mút của đoạn:

$$\begin{cases} -\frac{3}{4} (-1)^2 + \frac{\alpha}{2} (-1) + 1 \geq 0, \\ -\frac{3}{4} \cdot 1^2 + \frac{\alpha}{2} 1 + 1 \geq 0 \end{cases}$$

nghĩa là $\alpha \leq \frac{1}{2}$ và $\alpha \geq -\frac{1}{2}$.

Đáp số: bất đẳng thức đã cho đúng với mọi $x$ khi $-\frac{1}{2} \leq \alpha \leq \frac{1}{2}$.

⟦folio 45⟧

Hình 4. Giá trị nhỏ nhất tại $t = t_0$.

Hình 5. Giá trị nhỏ nhất tại $t = t_0$.

5. (ĐHTH Leningrad, khoa toán-cơ, 1966). Tên lửa phải đi qua một đoạn đường bằng $H$. Nó bắt đầu chuyển động với vận tốc không đổi $v$ và tại bất kỳ thời điểm nào cũng có thể bật chuyển động bổ sung, tạo ra gia tốc không đổi $a$ ($a > 0$) và hoạt động cho đến hết quãng đường. Lượng nhiên liệu tiêu thụ trên đoạn đường chuyển động với vận tốc không đổi tỉ lệ với thời gian chuyển động, còn khi chuyển động bổ sung được bật thì tỉ lệ với bình phương thời gian, với các hệ số tỉ lệ tương ứng là $k_1$ và $k_2$ ($k_1, k_2 > 0$). Tên lửa phải chuyển động với chuyển động bổ sung được bật trong thời gian bao lâu để tổng lượng nhiên liệu tiêu thụ là nhỏ nhất?

Gọi $\tau$ là thời gian tên lửa chuyển động với vận tốc không đổi, $t$ là thời gian chuyển động khi bật chuyển động bổ sung, $A$ là lượng nhiên liệu tiêu thụ. Từ các phương trình:

$$H = v\tau + vt + \frac{at^2}{2}, \quad A = k_1\tau + k_2t^2$$

ta được

$$\tau = \frac{1}{v} \left( H - vt - \frac{at^2}{2} \right), \quad A = \left( k_2 - \frac{ak_1}{2v} \right) t^2 - k_1t + \frac{k_1H}{v}.$$

Nhận thấy rằng $0 \leq t \leq t_0$, trong đó $t_0$ là nghiệm dương của phương trình

$$H = vt + \frac{at^2}{2}, \quad t_0 = \frac{-v + \sqrt{v^2 + 2aH}}{a}.$$

(Đó là thời gian bay trong trường hợp chuyển động được включен ngay từ đầu.) Cần tìm giá trị nhỏ nhất của hàm số $A = A(t)$ (*), xác định trên đoạn $[0, t_0]$.

1) $k_2 - \frac{ak_1}{2v} < 0$. Đỉnh của parabol $A = A(t)$ có hoành độ

$$t^* = \frac{k_1}{2 \left( k_2 - \frac{ak_1}{2v} \right)} < 0.$$

Parabol được bố trí như chỉ ra trên hình 4. Giá trị nhỏ nhất tại $t = t_0$.

2) $k_2 - \frac{ak_1}{2v} = 0$; $A = -k_1t + \frac{k_1H}{v}$. Giá trị nhỏ nhất tại $t = t_0$ (hình 5).

3) $k_2 - \frac{ak_1}{2v} > 0$. Hoành độ đỉnh của parabol

$$t^* = \frac{vk_1}{2vk_2 - ak_1} > 0.$$

⟦folio 46⟧

Hình 6. Giá trị nhỏ nhất tại $t = t^*$.

Nếu $t^* \leq t_0$, thì giá trị nhỏ nhất đạt tại $t = t^*$ (hình 6).
Nếu $t^* \geq t_0$, thì giá trị nhỏ nhất đạt tại $t = t_0$ (hình 7).
Đáp số: Nếu $2vk_2 - ak_1 > 0$ và

$$\frac{vk_1}{2vk_2 - ak_1} \leq \frac{-v + \sqrt{v^2 + 2aH}}{a},$$

thì

$$t = \frac{vk_1}{2vk_2 - ak_1}.$$

Nếu $2vk_2 - ak_1 \leq 0$ hoặc $2vk_2 - ak_1 > 0$ và

$$\frac{vk_1}{2vk_2 - ak_1} > \frac{-v + \sqrt{v^2 + 2aH}}{a},$$

thì

$$t = \frac{-v + \sqrt{v^2 + 2aH}}{a}.$$

Bài tập

1. Chỉ ra các điều kiện để cả hai nghiệm của tam thức $f(x) = ax^2 + bx + c$ nhỏ hơn số đã cho $\alpha$.
2. Chỉ ra các điều kiện để số đã cho $\alpha$ nằm giữa các nghiệm của tam thức $f(x) = ax^2 + bx + c$.
3. (Đại học Quốc gia Moskva, ngành ngôn ngữ học cấu trúc, 1968). Tìm tất cả các giá trị của tham số $b$ để cả hai nghiệm của phương trình bậc hai $x^2 - 2bx - 1 = 0$ là thực và có giá trị tuyệt đối không vượt quá 2.
4. (Đại học Quốc gia Moskva, ngành vật lý, 1965). Tìm tất cả các giá trị $a$ để các phương trình $x^2 + x + a = 0$ là thực và lớn hơn $a$.
5. (Đại học Quốc gia Moskva, ngành sinh học, 1969). Tìm tất cả các giá trị $a$ để hệ

$$\begin{cases} x^2 + y^2 = a, \\ x - y = a \end{cases}$$

có nghiệm duy nhất.
6. Bán kính đáy của một hình nón tròn xoay là $R$, còn chiều cao là $H$. Xác định chiều cao của hình trụ nội tiếp trong hình nón này và có diện tích xung quanh lớn nhất.
7. (Đại học Tổng hợp Moskva, bộ môn ngôn ngữ học cấu trúc, 1969). Chỉ ra tất cả các nghiệm của phương trình $x^2 + 1 = \cos x$.
8. (Đại học Tổng hợp Moskva, khoa vật lý, 1964). Tìm tất cả các giá trị của $m$ sao cho biểu thức $x^2 + mx + m^2 + 6m$ âm với mọi giá trị của $x$ thỏa mãn các bất đẳng thức $1 < x < 2$.
9. (Đại học Tổng hợp Moskva, khoa vật lý, 1963). Một quả đạn bay ra từ khẩu pháo dưới góc $\alpha$ so với phương ngang với vận tốc $v_0$. Tại điểm cao nhất của quỹ đạo, nó nổ thành hai phần có khối lượng bằng nhau, và vận tốc của các phần ngay sau vụ nổ là nằm ngang và thuộc mặt phẳng quỹ đạo. Một nửa rơi xuống cách vị trí bắn một khoảng $S$. Xác định vị trí rơi của nửa thứ hai, nếu biết rằng nó rơi xa hơn nửa thứ nhất. Coi rằng chuyển động của quả đạn diễn ra trong không gian không có không khí.
