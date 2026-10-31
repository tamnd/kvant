---
id: 1975-2-vahovskiy-ryivkin-kogda-pomogayut-grafiki-494459e0
issue: kvant_1975_2
year: 1975
number: "2"
title: Khi đồ thị giúp ích
authors:
  - Ваховский Е. Б.
  - Рывкин А. А.
rubric: praktikum-abiturienta
rubric_sub: Практикум абитуриента
page_first: 45
page_last: 50
page_labels: 43-48
tag: WIUH
lang: vi
source: kvant_digital
extraction: vision
content_sha256: 89f75390ad557dbb4b99763c4f1c5803a8d33d0748f9ccc0ce947dfeab3fca38
prompt_sha256: draft-1
translated_from: content/ru/1975/02/articles/13_vahovskiy-ryivkin-kogda-pomogayut-grafiki-494459e0.md
source_content_sha256: 3c11b55e3507d58175ef924989f111167fb43fd509697504818e9541abde4769
translation_model: draft
translation_run: vi-draft-2026-10-31
translation_quality: draft
---

⟦folio 43⟧

Thật vậy, không có tài liệu nào quen thuộc với người nộp đơn hơn những câu hỏi liên quan đến việc nghiên cứu tam thức bậc hai. Không một giám khảo nào nghi ngờ rằng mọi sinh viên vào đại học sẽ dễ dàng giải được phương trình bậc hai, ghi nhớ định lý Vieta và giải được bất đẳng thức bậc hai. Và, tuy nhiên, việc thực hành các kỳ thi ứng dụng hết lần này đến lần khác đề cập đến chủ đề này và thí sinh không phải lúc nào cũng đạt được thành công. Họ thất vọng vì mong muốn sử dụng thông tin bề nổi và với sự giúp đỡ của họ để dịch bài toán sang ngôn ngữ trang trọng càng nhanh càng tốt. Tuy nhiên, con đường lời giải này không phải lúc nào cũng tối ưu.

Việc trình bày bằng đồ họa về các điều kiện bài toán thường hữu ích hơn. Nó giúp bạn có thể xem xét tất cả các điều kiện cùng nhau và tìm ra phương pháp đơn giản nhất lời giải.

Hãy thể hiện điều này bằng các ví dụ.

Bài toán 1. Với những giá trị thực nào $x_1$ và $x_2$ thì phương trình

$$x^2 - 2x - a^2 + 1 = 0$$

nằm giữa nghiệm $x_1'$ và $x_2'$ của phương trình

$$x^2 - 2(a+1)x + a(a-1) = 0?$$

Chúng ta cần tìm tất cả $a$ sao cho các giá trị tương ứng của chúng $x_1$, $x_2$, $x_1'$ và $x_2'$ thỏa mãn các bất đẳng thức số nguyên

$$x_1' < x_1 \leqslant x_2' < x_2'.$$

Nơi tự nhiên để bắt đầu là cố gắng giải các phương trình này và viết lại các bất đẳng thức số nguyên bài toán tương đương cho tham số chưa biết $a$.

Các nghiệm của phương trình thứ nhất là $x_1,2 = 1 \pm a$, các nghiệm của phương trình thứ hai là $x_1',2 = a + 1 \pm \sqrt{3a+1}$.

Vì không rõ số $1-a$ hoặc $1+a$ nào lớn hơn nên chúng tôi xem xét hai trường hợp. Nếu $1-a \leqslant 1+a$ thì bài toán giảm về hệ thống: $x_1' < 1-a$, $x_2' > 1+a$. Nếu $1+a < 1-a$, thì chúng ta nhận được một hệ thống khác: $x_1' < 1+a$, $x_2' > 1-a$.

Ptak sẽ có thể giải được một tập hợp gồm hai hệ bất đẳng thức vô tỷ. Hãy tự mình thực hiện việc này và so sánh nó với giải pháp khác bài toán mà chúng tôi sẽ trình bày ngay bây giờ.

Đặt $f(x)$ và $g(x)$ tương ứng với vế trái của phương trình thứ nhất và thứ hai. Đồ thị của hàm số $y = f(x)$ và $y = g(x)$ là các parabol được tạo thành bởi các nhánh đi lên. Chúng ta hãy biểu thị bằng $x_1$ và $x_2$ các nghiệm của phương trình $f(x) = 0$, và bằng $x_1'$ và $x_2'$ các nghiệm của phương trình $g(x) = 0$. Đối với mọi người, $x \in (x_1', x_2')$ sẽ là $g(x) < 0$. Nếu $x_1' < x_1 < x_2' < x_2'$ thì $g(x_1) < 0$ và $g(x_2) < 0$. Điều ngược lại cũng đúng: nếu $g(x_1) < 0$ và $g(x_2) < 0$ thì $x_1' < x_1 < x_2' < x_2'$. Như vậy, bài toán rút gọn về lời giải của hệ bất đẳng thức

$$\begin{cases} g(x_1) < 0, \\ g(x_2) < 0. \end{cases}$$

Thay $x_1,2 = 1 \pm a$ vào $g(x)$, ta thu được hệ

$$\begin{cases} (1-a)^2 - 2(a+1)(1-a) + a(a-1) < 0, \\ (1+a)^2 - 2(a+1)(1-a) + a(a-1) < 0. \end{cases}$$

⟦folio 44⟧

Giải nó, ta tìm được $-\frac{1}{4} < a < 1$.

Cần lưu ý rằng phép biến đổi bài toán như vậy là phù hợp nếu các biểu thức cho $x_1$ và $x_2$ đủ đơn giản.

Tuy nhiên, việc truy cập biểu đồ không phải lúc nào cũng suôn sẻ và dễ dàng như trong ví dụ vừa thảo luận.

Đây là một ví dụ khác.

Bài toán 2 (MAI, 1970). Với giá trị thực nào của tham số m thì nghiệm của phương trình $(1+m)x^2-3mx+4m=0$ sẽ tuân theo các điều kiện $2 < x < 5$?

Hãy để chúng tôi kể lại ở đây lời giải bài toán, do một người nộp đơn đề xuất. Đồ thị của tam thức bậc hai có thể có các nhánh lên hoặc xuống tùy thuộc vào dấu của hệ số tại $x^2$. Trong cả hai trường hợp, các giá trị của tam thức bậc hai $f(2)$ và $f(5)$ sẽ cùng dấu, tức là $f(2) \cdot f(5) > 0$. Tuy nhiên, các nghiệm $x_1$ và $x_2$ có thể nằm ở cả bên trái của 2 hoặc cả hai ở bên phải của 5. Trong cả hai trường hợp, $f(2) \cdot f(5)$ sẽ lớn hơn 0, nhưng hoành độ của đỉnh của parabol $x_0$ nằm ngoài đoạn [2,5]. Vì vậy, chúng tôi yêu cầu nó phải nằm trong phân khúc này. Vẫn còn phải viết ra rằng phương trình này có nghiệm thực sự và rút gọn lời giải bài toán thành lời giải hệ bất đẳng thức

$$\begin{cases} f(2) \cdot f(5) > 0, \\ 2 < x_0 < 5, \\ D \geq 0. \end{cases}$$

Lý do trên không phải là không có cơ sở, nhưng thật không may, nó cho thấy sự thiếu chính xác. Việc thay thế bài toán ban đầu bằng hệ thống (1) không thể được coi là hợp lý. Đối với một tam thức bậc hai tùy ý $f(x)$ thì điều đó đơn giản là không đúng (xem Hình 1). Nhưng ngoài ra, có thể hệ số $x^2$ tiến về 0, khi đó đồ thị của hàm số sẽ là một đường thẳng.

Để có được lời giải bài toán gọn gàng, bạn cần tìm cách đảm bảo giải quyết hết mọi tình huống có thể xảy ra. Với mục đích này, thật thuận tiện khi tìm hệ số $x^2$. Nó có thể là âm, bằng 0 hoặc dương.

Khi $1+m=0$, tức là $m=-1$, phương trình trở thành $3x-4=0$. Gốc $x=4/3$ của nó không thỏa mãn điều kiện bài toán; nó không nằm giữa 2 và 5.

Hình 1.

Nếu $1+m \neq 0$ thì vế trái của phương trình là tam thức bậc hai và đồ thị của nó là parabol. Vì tam thức phải có nghiệm thực, nên $D \geq 0$, tức là $9m^2-16m(m+1) \geq 0$. Do đó $0 \geq m \geq -16/7$.

Bây giờ chúng ta hãy lợi dụng thực tế là trục hoành của các đỉnh của parabol phải nằm giữa các gốc của nó, tức là $2 < \frac{3m}{2(m+1)} < 5$.

Chúng tôi đã phát hiện ra rằng $m < 0$, và do đó số lượng $\frac{3m}{2(m+1)}$ sẽ chỉ dương với $m+1 < 0$. Như vậy, trường hợp các nhánh của parabol hướng lên trên không cần xét đến. Chúng ta hãy giải bất đẳng thức thu được và tìm thấy rằng

$$-4 < m < -\frac{10}{7}.$$

⟦folio 45⟧

So sánh nó với ràng buộc đầu tiên trên $m$, chúng ta nhận được $-16/7 \leq m < -10/7$. Biểu đồ parabol của chúng ta cho các giá trị $m$ như vậy được hiển thị trong Hình 2. Các nhánh của nó hướng xuống dưới và các nghiệm sẽ nằm trong khoảng $(2, 5)$ khi và chỉ khi $f(2) < 0$ và $f(5) < 0$, tức là $4+2m < 0$, $25+14m < 0$.

Do đó $m < -2$. Cuối cùng $-16/7 \leq m < -2$.

Bài toán 3 (MAI, 1970). Với những giá trị thực nào $k$ là một trong những hệ thống lời giải thực
$$\begin{cases} x+y=2(k+1), \\ xy=k^2+3k-1 \end{cases}$$
thỏa mãn điều kiện $|x| < 1$, $|y| > 1$?

Cùng với hệ (2), (3), việc xét phương trình bậc hai tương ứng là điều đương nhiên
$$z^2-2(k+1)z+k^2+3k-1=0.$$ (4)
Nó có liên quan chặt chẽ với hệ thống này, lời giải trong số đó có được bằng cách sử dụng các nghiệm $z_1$ và $z_2$ của phương trình (4):
$$(z_1, z_2), (z_2, z_1).$$
Thật dễ dàng để định dạng lại bài toán cho phương trình (4): với thực tế $k$ là một trong những nghiệm thực của phương trình (4) nằm trong khoảng $(-1, 1)$ và nghiệm còn lại nằm ngoài khoảng này.

Vì tam thức bậc hai (4) phải có hai nghiệm thực khác nhau nên $D > 0$ và đồ thị của vế trái của phương trình (4) là một parabol giao nhau $z$ tại hai điểm khác nhau $z_1$ và $z_2$ ($z_1 < z_2$).

Điều kiện bài toán chỉ được thỏa mãn bằng cách sắp xếp các nghiệm của tam thức bình phương khi một trong số chúng nằm trong khoảng $(-1, 1)$ và cái còn lại nằm ngoài khoảng này (Hình 3). Nếu chúng ta dịch điều này sang ngôn ngữ công thức, chúng ta sẽ có được các hệ thống sau:

$$\begin{cases} z_1 < -1, \\ -1 < z_2 < 1; \end{cases}$$

Những khó khăn thuần túy về mặt kỹ thuật nảy sinh với lời giải của họ là lớn đến mức không thể giải thích được. Nghiên cứu bức tranh hình học có thể cho chúng ta biết một cách tiếp cận ít rườm rà hơn. Dễ dàng nhận thấy rằng parabol nằm theo một trong những cách được minh họa trong Hình 3 khi và chỉ khi các giá trị của đa thức $f(z)$, đứng ở phía bên trái của (4), tại các điểm $-1$ và $1$ có các biểu tượng khác nhau, tức là
$$f(-1)f(1) < 0.$$ (6)

Thật vậy, hãy để giá trị $k$ thỏa mãn điều kiện bài toán. Khi đó phương trình (4) có hai nghiệm thực. Nếu một trong các nghiệm trùng với $-1$ hoặc $1$, thì vế trái của bất đẳng thức (6) biến mất. Hãy để chúng tôi loại trừ các tùy chọn này khỏi việc xem xét thêm.

Bây giờ chúng ta hãy biên soạn một bảng giá trị $f(-1)f(1)$ cho các trường hợp có thể xảy ra về sự bằng nhau về vị trí $z_1$ và $z_2$ so với khoảng $(-1, 1)$ ($z_1 < z_2$)

Vì tất cả các phương án có thể đã được sử dụng hết nên chúng ta đồng thời thiết lập sự cần thiết và điều kiện đủ (6). Nó vẫn còn phải được quyết định

⟦folio 46⟧

bất bình đẳng
$(k^2+5k+2)(k^2+k-2) < 0,$
hoặc
$$\left( k + \frac{V_{17}+5}{2} \right) \left( k + \frac{V_{17}-5}{2} \right) \times (k+2)(k-1) < 0.$$
Đáp số:
$$-\frac{V_{17}+5}{2} < k < -2,$$
$$\frac{V_{17}-5}{2} < k < 1.$$
Bài toán 4 (MSU, Cơ học và Toán học, 1971). Tìm tất cả các giá trị của $\alpha$ mà hệ bất phương trình
$$\begin{cases} x^2+2x+\alpha \leqslant 0, \\ x^2-4x-6\alpha \leqslant 0 \end{cases}$$
có một lời giải.
Bất đẳng thức (7) và (8) chỉ có thể có lời giải nếu các biệt thức $D_1$ và $D_2$ ở vế trái của chúng không âm.
Hãy bắt đầu với trường hợp $D_1 = 0$, tức là $\alpha = 1$. Bất đẳng thức (7) khi đó có dạng $(x+1)^2 \leqslant 0$ và chỉ có lời giải $x = -1$. Đối với các giá trị tìm được của $x$ và $\alpha$, bất đẳng thức (8) được thỏa mãn. Do đó, $\alpha_1 = 1$ là một trong những trường hợp ngoại lệ đối với các giá trị $\alpha$.
Bây giờ đặt $D_2 = 0$, tức là $\alpha = -\frac{2}{3}$. lời giải bất đẳng thức duy nhất (8) cho $\alpha = -\frac{2}{3}$ sẽ là $x = 2$; bất đẳng thức (7) đối với $\alpha$ và $x$ này không được thỏa mãn.
Bây giờ chúng ta có thể giả sử rằng $D_1 > 0$ và $D_2 > 0$. Để một hệ thống nhất định có một lời giải duy nhất, điều cần thiết và đủ là các tích phân $[x_1, x_2]$ và $[x'_1, x'_2]$ lời giải có một điểm chung duy nhất. Điều này có thể xảy ra ở $x'_2 = x_1$ hoặc $x_2 = x'_1$.
Đồ thị ở phía bên trái của (7) là một parabol từ đỉnh abscissa $x_0 = -1$, và đồ thị ở phía bên trái (8) là một parabol từ đỉnh abscissa $x'_0 = 2$.

Hình 4.
Do đó, nếu $\alpha$ thỏa mãn điều kiện bài toán thì các parabol nằm chính xác như trên Hình 4. Do đó, khả năng duy nhất còn lại là $x_2 = x'_1$, tức là $-1 + \sqrt{1-\alpha} = 2 - \sqrt{4+6\alpha}$. Giải phương trình vô tỉ này, chúng ta tìm ra nghiệm duy nhất của nó $\alpha = 0$ (giá trị $\alpha = \frac{48}{49}$, cũng có thể thực hiện được trong quá trình lời giải - nghiệm được xây dựng). Vì vậy, $\alpha = 0$.
Đáp số: 0; 1.
Bài toán 5 (NSU, Cơ học và Toán học, 1968). Với mỗi thực là một môi trường của tất cả các thùy của mặt phẳng, các tọa độ comorbix $x$, $y$ thỏa mãn hệ bất đẳng thức
$$\begin{cases} y - 2x \geqslant 0, \\ -x^2 + 2ax - a^2 + a + 1 - y \geqslant 0, \end{cases}
$$
Các thùy nhỏ nhất có tọa độ cao nhất là $y$.
Ta viết lại hệ dưới dạng
$$\begin{cases} y \geqslant f(x), \\ y \leqslant \varphi(x), \end{cases}$$
ở đâu $f(x) = 2x$ và $\varphi(x) = -x^2 + 2ax - a^2 + a + 1$. Đồ thị của đường cong $y = \varphi(x)$ là một parabol được hình thành bởi các nhánh đi xuống và tất cả các điểm thỏa mãn bất đẳng thức (10) đều nằm không cao hơn parabol này. Vì với mỗi $a$, chúng ta quan tâm đến lời giải của hệ có thứ tự lớn nhất, nên bất đẳng thức (10) có thể được thay thế bằng phương trình $y = \varphi(x)$.

⟦folio 47⟧

Đồ thị $y = f(x)$ là đường thẳng đi qua gốc tọa độ và mọi điểm trên mặt phẳng thỏa mãn bất đẳng thức (9) đều không thấp hơn đường thẳng này. Như vậy, với mỗi $a$ phải tìm được một điểm của parabol $y = \varphi(x)$ nằm không thấp hơn đường thẳng $y = 2x$ và có thứ tự lớn nhất. Có hai trường hợp có thể xảy ra về vị trí tương đối của parabol và một đường thẳng: đỉnh của parabol không nằm thấp hơn đường thẳng $y = 2x$, hoặc nó nằm dưới đường thẳng này (xem Hình 5). Trong trường hợp đầu tiên, nghiệm bài toán sẽ là điểm $(x_0, y_0)$, là đỉnh của parabol, trong trường hợp thứ hai - điểm $(x_1, y_1)$, tọa độ của nó thỏa mãn đồng thời phương trình của đường thẳng và parabol. Phương trình của parabol giúp bạn dễ dàng tìm được tọa độ đỉnh của nó: $x = a$, $y = a + 1$. Chúng ta thấy rằng tất cả các đỉnh của parabol $y = \varphi(x)$ tại

Hình 5.

Hình 6.

các giá trị khác nhau của tham số $a$ nằm trên đường $y = x + 1$ và ngược lại, mỗi điểm $(x_0, y_0)$ của đường $y = x + 1$ tương ứng với một parabol $y = \varphi(x)$, có đỉnh trong đó - chỉ cần lấy $a = x_0$. Hãy vẽ các đường thẳng $y = x + 1$ và $y = 2x$ trên một biểu đồ (Hình 6). Giao điểm của hai đường này là điểm (1, 2). Tại $a \leqslant 1$ đường $y = x + 1$ sẽ nằm phía trên đường $y = 2x$ và nghiệm của bài toán sẽ là điểm $(a, a + 1)$. Nếu $a > 1$ thì nghiệm là điểm $(x, y)$, thỏa mãn hệ
$$\begin{cases} y - 2x = 0, \\ -x^2 + 2ax - a^2 + a + 1 - y = 0; \end{cases}$$
do đó $y = 2x$ và $x^2 - 2(a - 1)x + a^2 - a - 1 = 0$.

Phương trình có hai nghiệm thực khi $D = 2 - a \geqslant 0$, tức là $a \leqslant 2$. Trong đó, điều kiện bài toán được thỏa mãn bởi điều kiện lớn hơn:
$$x_2 = a - 1 + \sqrt{2 - a}.$$
Đáp số: tại $a \leqslant 1$, $x = a$, $y = a + 1$, tại
$$1 \leqslant a \leqslant 2, x = a - 1 + \sqrt{2 - a},$$
$$y = 2(a - 1) + 2\sqrt{a - 1},$$
tại $a > 2$ lời giải không.

Tuy nhiên, “định dạng” lời giải không phải lúc nào cũng tốn nhiều công sức hơn. Nếu không thì nó phù hợp hơn đồ họa.

Bài toán 6 (MAI, 1971). Với giá trị thực nào của $m$ thì bất đẳng thức
$$x^2 - 2mx + 2|x - m| + 2 < 0$$
có ít nhất một lời giải?
Chúng ta hãy biến đổi bất đẳng thức này về dạng
$$(x - m)^2 + 2|x - m| + 2 - m^2 < 0,$$
hoặc
$$\begin{cases} y^2 + 2y + 2 - m^2 < 0, \\ y \geqslant 0, \end{cases}$$

⟦folio 48⟧

ở đâu $y = |x - m|$. Hệ (11), (12) có ít nhất một lời giải khi và chỉ nếu phân biệt bên trái của (9) không âm và nghiệm lớn hơn $y_2$ không nằm bên trái số 0:

$$\begin{cases} m^2 - 1 \geq 0, \\ -1 + \sqrt{m^2 - 1} \geq 0, \\ m^2 \geq 1, \\ m^2 \geq 2. \end{cases}$$

nghĩa là, $\begin{cases} m^2 \geq 1, \\ m^2 \geq 2. \end{cases}$

Đáp số: $m \leq -\sqrt{2}, m \geq \sqrt{2}$.

Vì vậy, chúng ta thấy rằng trong chuỗi bài toán việc sử dụng biểu diễn đồ họa của tam thức bậc hai là rất thuận tiện. Cách tiếp cận này có thể hữu ích cho những chứng nghiện khác; nó giúp khám phá một con đường đơn giản và ý nghĩa hơn lời giải. Tuy nhiên, tất cả các đối số liên quan đến đồ thị chỉ có thể trở thành một phần của lời giải nếu chúng được thực hiện ở dạng tổng quát nhất. Trong các bài toán với tham số, bạn nên đặc biệt cẩn thận về kiểu phụ thuộc, vì đối với một số giá trị của tham số, hình thức của biểu đồ có thể thay đổi đáng kể (trong ví dụ 2, chúng ta đã thấy rằng với $m = -1$ đồ thị của tam thức bậc hai sẽ không phải là parabol mà là một đường thẳng). Việc sử dụng đồ thị ở lời giải bài toán bản thân nó không phải là mục đích cuối cùng, điều này đã được xác nhận rõ ràng trong ví dụ cuối cùng. Trước hết, bạn cần phân tích cẩn thận tất cả các tính năng của một bài toán cụ thể, suy nghĩ về cách sử dụng hợp lý nhất các điều kiện của nó - điều này có thể giúp bạn tìm ra lời giải thuận tiện nhất.

Bài tập
1. (MAI, 1970). Với giá trị thực nào của $a$ thì các số 1 và $a$ được chứa giữa các số $x_1$ và $y_1$, trong đó hệ thống $(x_1, y_1)$ - lời giải

$$\begin{cases} x + y - 1 = 2a, \\ 2xy = a^2 - a. \end{cases}$$

2. (MAI, 1970). Tìm tất cả các giá trị thực của $m$ mà nghiệm của phương trình

$$x^2 - 2(m - 1)x + 2m + 1 = 0$$

sẽ có các dấu hiệu khác nhau và mỗi modulo bốn.

3. (MAI, 1970). Tìm tất cả các giá trị thực của $m$ mà nghiệm của phương trình

$$(m - 1)\log_3^2(x - 2) - 2(m + 1)\log_3(x - 2) + m - 3 = 0$$

cậu bé ba.

4. (MSU, Cơ học và Toán học, 1971). Tìm tất cả các giá trị của $\alpha$ mà lời giải của hệ thống

$$\begin{cases} x^2 + 6x + 7 + \alpha \leq 0, \\ x^2 + 4x + 7 \leq 4\alpha. \end{cases}$$

tạo thành một khoảng (đoạn) khép kín có độ dài bằng một.

5. (MSU, kinh tế, điều khiển học, 1971). Tìm số hạng nhỏ nhất của dãy

$$a_n = 2n^2 - 24n + 69 - \frac{9}{(3n - 22)^2 + 3}(n = 1, 2, 3, \dots)$$

6. (MSU, nhà vật lý, 1964). Tìm tất cả các giá trị thực của $m$ thỏa mãn đẳng thức $mx^2 - 4x + 3m + 1 > 0$ với mọi giá trị dương của $x$.

7. (MAI, 1971). Tìm tất cả các giá trị thực của $a$ thỏa mãn đẳng thức $\frac{ax - a - \frac{1}{4}}{ax - 1} < 0$ với mọi giá trị dương của $x > -2$.

8. (MSU, nhà vật lý, 1968). Tìm tất cả các giá trị của tham số $a$ mà cả hai nghiệm của tam thức bình phương $x^2 - ax + 2$ đều là số thực và nằm trong khoảng từ 0 đến 3 (không bao gồm các giá trị cực trị).

9. (MSU, nhà vật lý, 1965). Tìm tất cả các giá trị của $a$ mà nghiệm của phương trình $x^2 + x + a = 0$ lớn hơn $a$.

10. (MSU, Cơ học và Toán học, 1966). Tìm tất cả các giá trị của $a$ mà với tất cả $x$, số modulo một không vượt quá đẳng thức $2x^2 - 4a^2x - a^2 + 1 > 0$.
