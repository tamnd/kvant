---
id: 1970-9-resheniya-8a9c9911
issue: kvant_1970_9
year: 1970
number: "9"
title: '[Lời giải các bài toán M6—M7; F8—F11]'
rubric: zadachnik-kvanta
page_first: 52
page_last: 59
page_labels: 50, 51, 52, 53, 55, 56, 57
tag: 0QT0
lang: vi
source: kvant_digital
extraction: vision
content_sha256: 6b253874051e03c48326305086a82d70ed893618b5008c3b95095904071386ee
prompt_sha256: 3ec6b8aabd9b98576af76503cd8a2902b9f5d18e01ee867dfb1228f59c6d52d8
translated_from: content/ru/1970/09/articles/10_resheniya-8a9c9911.md
source_content_sha256: 8d8802e7032396fdee1833f6ee62baca2e1e09489bedcbd17311c6d493757a33
translation_model: gpt-5.6-terra
translation_run: vi-codex-2026-10-31
---

⟦folio 50⟧

M6. Trước mặt bạn là một chiếc đồng hồ. Có bao nhiêu vị trí của các kim mà không thể xác định thời gian nếu không biết kim nào là kim giờ, kim nào là kim phút?
(Cho rằng có thể xác định chính xác vị trí của mỗi kim, nhưng không thể theo dõi chuyển động của các kim.)

Đáp số. Có 132 vị trí như vậy. Nói cách khác, có 66 cặp vị trí của các kim sao cho trong mỗi cặp, một vị trí nhận được từ vị trí kia bằng cách đổi kim giờ thành kim phút và kim phút thành kim giờ (như ở hình 1); dĩ nhiên, không xét những vị trí mà hướng của kim giờ và kim phút trùng nhau: trong các trường hợp đó thời gian được xác định duy nhất.

Lời giải và e. Chúng tôi đã nhận được nhiều lời giải khác nhau cho bài toán này. Sau đây là một vài lời giải. Đây là lời giải phổ biến nhất.

Ta sẽ coi mặt đồng hồ được chia thành 12 phần. Xét một vị trí nào đó của các kim đang nói đến trong điều kiện. Giả sử một kim ở vị trí $x$, kim kia ở vị trí $y$; ở đây $0 \leq x < 12$, $0 \leq y < 12$. Nếu coi kim thứ nhất là kim giờ, còn kim thứ hai là kim phút, thì phải có đẳng thức

$$x = a + \frac{5y}{60},$$

(1)

Hình 1.

⟦folio 51⟧

Hình 2.

trong đó $a$ — số giờ nguyên, $0 \leqslant a \leqslant 11$.
Tương tự, nếu kim thứ nhất là kim phút, còn kim thứ hai là kim giờ, thì
$$y = b + \frac{5x}{60},$$

trong đó $b$ — số nguyên, $0 \leqslant b \leqslant 11$.
Hệ gồm hai đẳng thức (1) và (2) có thể thay bằng hệ tương đương:

$$\begin{cases}
12x = 12a + y, \\
12y = 12b + x, \\
143x = 12(b + 12a),
\end{cases}$$

$$\begin{cases}
x = 12 \cdot \frac{b + 12a}{143}, \\
y = 12 \cdot \frac{a + 12b}{143}.
\end{cases}$$

Ở đây $0 \leqslant a \leqslant 11, 0 \leqslant b \leqslant 11$ là các số nguyên. Mỗi cặp $(x, y)$ thỏa mãn hệ này là một nghiệm của nó. Có tất cả $12^2 = 144$ cặp. Rõ ràng cần loại trường hợp $x = y$, tức là $a = b$. Còn lại 132.

Hai trong số đó — tương ứng với $a = 2, b = 5$ và $a = 5, b = 2$ — được biểu diễn trên hình 1 (rõ ràng, việc thay $a$ bằng $b$ và $b$ bằng $a$ tương ứng với việc đổi các mũi tên).

Một lời giải rất trực quan được học sinh lớp 10 S. Pozdnyakov (thành phố Vilnius) gửi đến. Đây là lập luận của em.

Đặt vị trí của kim phút $y$ là một hàm của vị trí kim giờ $x$. Đồ thị của hàm này $x \rightarrow y$ được vẽ màu xanh lam trên hình 2. Đồ thị này là tập hợp mọi vị trí của các kim $(x, y)$ có thể gặp trên mặt đồng hồ. Ta quan tâm đến những cặp $(x, y)$ mà cặp $(y, x)$ cũng thuộc tập hợp này. Nhưng điểm $(y, x)$ là điểm đối xứng với $(x, y)$ qua đường phân giác của góc $xOy$. Trên hình 2 tập hợp các điểm đối xứng với các điểm của hệ này được đánh dấu màu đỏ *).

Còn lại là tìm số giao điểm của các đoạn màu xanh và màu đỏ (không kể các điểm nằm trên đường phân giác $x = y$). Dễ thấy rằng có 132 điểm như vậy, tức là 66 cặp điểm đối xứng qua đường phân giác.

Và cuối cùng, còn một cách nữa, không cần đến bất kỳ công cụ toán học nào.

Đặt cạnh đồng hồ của chúng ta (bên phải) một chiếc khác, tưởng tượng, chạy nhanh hơn đúng 12 lần. Cho cả hai chiếc đồng hồ cùng lúc chỉ 12 giờ; khi đó kim giờ của đồng hồ bên phải luôn trùng với kim phút của đồng hồ bên trái. Rõ ràng, những vị trí «không phân biệt được» của các kim mà ta quan tâm chính xác là những lúc kim giờ của đồng hồ bên trái trùng với kim phút của đồng hồ bên phải, chạy nhanh (hãy nghĩ xem vì sao!). Vậy điều đó sẽ xảy ra bao nhiêu lần? Trong 144 vòng mà kim phút của đồng hồ bên phải quay được trong thời gian kim giờ của đồng hồ «bình thường» quay một vòng, trên

*) Tác giả viết rằng tập hợp «đỏ» là «đồ thị của hàm ngược với hàm $x \rightarrow y$ của chúng ta». Điều này không hoàn toàn đúng: rõ ràng hàm của chúng ta không có hàm ngược trên toàn bộ đoạn $0 \leqslant x \leqslant 12$, vì ở đây mỗi $y$ tương ứng với nhiều (cụ thể là mười hai) $x$ khác nhau. Có thể nói như sau: ta xét hàm $x \rightarrow y$ trên mỗi đoạn $0 \leqslant x < 1, 1 \leqslant x < 2, \dots, 11 \leqslant x < 12$, lấy hàm ngược của từng hàm này và dựng đồ thị cho từng hàm. Khi đó ta thực sự nhận được tập hợp «đỏ», gồm `devenaudami` đồ thị! (Xem định nghĩa hàm ngược trong «Kvant» số 1, tr. 32—33.)

⟦folio 52⟧

mỗi vòng quay sẽ có một lần trùng hợp (kể cả điểm đầu của vòng quay thứ nhất); trong đó cần loại trừ 12 trường hợp khi cả bốn kim đều trùng nhau, — còn lại 132.

**M7.** a, b, c — các cạnh của một tam giác.

Chứng minh rằng $\frac{a}{b+c-a} + \frac{b}{c+a-b} + \frac{c}{a+b-c} \geq 3$.

Lời giải. Bài toán này có khá nhiều lời giải. Chúng tôi sẽ đưa ra một trong những lời giải ngắn nhất. Ta chỉ cần bất đẳng thức quen thuộc từ chương trình phổ thông
$$\frac{m}{n} + \frac{n}{m} \geq 2,$$
(1)

trong đó $m > 0, n > 0$.

Đặt:
$$b + c - a = x,$$
$$c + a - b = y,$$
$$a + b - c = z.$$

Nhận thấy rằng
$$x > 0, y > 0, z > 0;$$
(3)
điều này suy ra từ việc $a, b, c$ là các cạnh của một tam giác, và mỗi cạnh nhỏ hơn tổng hai cạnh kia (đáng tiếc, từ các thư gửi đến tòa soạn có thể thấy rằng đa số người giải bài toán thậm chí không nghĩ đến việc họ dùng ở đâu giả thiết $a, b, c$ là các cạnh của một tam giác).

Từ (2) suy ra rằng
$$a = \frac{y+z}{2}, \quad b = \frac{x+z}{2}, \quad c = \frac{x+y}{2};$$

do đó bất đẳng thức ban đầu có thể viết lại như sau:
$$\frac{y+z}{2x} + \frac{x+z}{2y} + \frac{x+y}{2z} \geq 3.$$

Biến đổi vế trái của (4) và sử dụng (1) và (3), ta được
$$\frac{y+z}{2x} + \frac{x+z}{2y} + \frac{x+y}{2z} =
= \frac{1}{2} \left[ \left( \frac{y}{x} + \frac{x}{y} \right) + \left( \frac{z}{x} + \frac{x}{z} \right) +
\left( \frac{z}{y} + \frac{y}{z} \right) \right] \geq \frac{1}{2} (2 + 2 + 2) = 3,
$$
điều phải chứng minh.

Lưu ý rằng tương tự cũng có thể chứng minh bất đẳng thức tổng quát hơn:
$$\frac{x_1}{x_2 + x_3 + \dots + x_n - x_1} +
\frac{x_2}{x_3 + x_4 + \dots + x_n + x_1 - x_2} + \dots +
\frac{x_{n-1}}{x_n + x_1 + x_2 + \dots + x_{n-2} - x_{n-1}} +
\frac{x_n}{x_1 + x_2 + \dots + x_{n-1} - x_n} \geq \frac{n}{n-2},$$

trong đó mọi mẫu số đều dương.

Cuối cùng, lưu ý rằng từ bất đẳng thức đã chứng minh trực tiếp suy ra một sự kiện hình học. Gọi $R$ là bán kính đường tròn ngoại tiếp tam giác, còn $r$ là bán kính đường tròn nội tiếp tam giác đó. Đã biết rằng
$$R = \frac{abc}{4S}, \quad r = \frac{S}{p},$$
(5)

$$S = \sqrt{p(p-a)(p-b)(p-c)},$$

trong đó $S$ là diện tích tam giác, còn $p$ là nửa chu vi của nó. Từ (2) suy ra rằng
$$p - a = \frac{x}{2},$$
$$p - b = \frac{y}{2},$$
$$p - c = \frac{z}{2}.$$

Bây giờ, sử dụng (5) và (6), ta được
$$\frac{R}{2r} = \frac{abcp}{8S^2} = \frac{abcp}{8p(p-a)(p-b)(p-c)} =
= \frac{abc}{(a+b-c)(b+c-a)(c+a-b)} =
= \frac{(x+y)(y+z)(z+x)}{8xyz} =
= \frac{1}{4} \left[ 1 + \left( \frac{y+z}{2x} + \frac{x+z}{2y} + \frac{x+y}{2z} \right) \right].$$

Lưu ý rằng trong ngoặc tròn ở vế phải của đẳng thức cuối cùng là vế trái của bất đẳng thức (4). Dùng nó, ta được
$$\frac{R}{2r} \geq 1,$$
tức là $R \geq 2r$.

Vậy, bán kính của đường tròn ngoại tiếp tam giác không nhỏ hơn đường kính của đường tròn nội tiếp nó. Hãy thử chứng minh điều này hoàn toàn bằng hình học (điều đó khó hơn nhiều).

⟦folio 53⟧

Hình 3

F7. Thanh ngang $O_1A$ dài $l$ quay quanh trục thẳng đứng $O_1$ (hình 3). Trên trục gắn vào đầu thanh $A$ có lắp một bánh xe bán kính $r$. Trục của bánh xe nằm ngang và tạo với thanh $O_1A$ một góc $\alpha$. Bánh xe quay không ma sát trên trục và lăn trên mặt đất. Ma sát giữa bánh xe và mặt đất lớn. Bánh xe sẽ quay bao nhiêu vòng khi thanh $O_1A$ quay một vòng quanh trục thẳng đứng?

Lời giải. Bài toán được giải dễ nhất nếu lập luận như người quan sát ngồi ở đầu $A$ của thanh $O_1A$ sẽ lập luận. Nếu vận tốc góc quay của thanh $O_1A$ so với mặt đất bằng $\Omega$, thì người quan sát sẽ nói rằng trong hệ tọa độ của mình thanh đứng yên, còn mặt đất quay quanh trục $O_1$ với vận tốc góc bằng $\Omega$, theo hướng ngược với hướng quay của thanh so với mặt đất. Vận tốc của điểm trên mặt đất mà bánh xe chạm vào có độ lớn $v = \Omega l$ và vuông góc với thanh $O_1A$. Phân tích vận tốc này thành hai thành phần: $v_1 = v \cos \alpha$ và $v_2 = v \sin \alpha$, tương ứng song song và vuông góc với mặt phẳng bánh xe. Rõ ràng, vì ma sát của bánh xe với đất lớn, nên điểm của bánh xe mà nó chạm đất chuyển động so với điểm $A$, và do đó so với trục bánh xe, với vận tốc $v_1$. Điều đó có nghĩa là bánh xe quay quanh trục với vận tốc góc $\omega = \frac{v_1}{r} = \Omega \frac{l}{r} \cos \alpha$.

Hình 4.

Tỉ số các góc quay của thanh và bánh xe quanh các trục của chúng bằng tỉ số các vận tốc góc quay của thanh và bánh xe. Vì vậy, khi thanh $O_1A$ quay một vòng quanh trục $O_1$, bánh xe sẽ quay $n = \frac{\omega}{\Omega} = \frac{l}{r} \cos \alpha$ vòng quanh trục của nó.

F8. Một thanh dài $AB$ có lỗ ren ở đầu được vặn vào một vít thẳng đứng (hình 4). Thả thanh ra. Ma sát giữa vít và thanh không đáng kể. Thanh sẽ chuyển động như thế nào sau khi nó tuột khỏi vít?

Lời giải. Vào thời điểm thanh tuột khỏi vít, vận tốc của khối tâm (trọng tâm) của nó sẽ có cả thành phần thẳng đứng lẫn thành phần nằm ngang. Vì từ thời điểm đó lực duy nhất tác dụng lên thanh là trọng lực, nên khối tâm của thanh sẽ chuyển động theo một parabol — quỹ đạo của một vật ném xiên với vận tốc ban đầu bằng vận tốc chuyển động của khối tâm thanh tại thời điểm nó tuột khỏi vít. Nhưng vào thời điểm thanh tuột khỏi vít, các điểm khác nhau của thanh có các vận tốc nằm ngang khác nhau. Vì vậy thanh còn sẽ quay trong mặt phẳng nằm ngang quanh khối tâm.

⟦folio 55⟧

Ta tìm quy luật biến đổi biên độ dao động của vật nặng. Độ biến thiên năng lượng của hệ khi vật nặng chuyển động bằng công của lực ma sát, vì vậy, dùng công thức năng lượng của lò xo biến dạng $W = \frac{k(\Delta x)^2}{2}$, có thể viết rằng

$$\frac{k y_n^2}{2} - \frac{k x_n^2}{2} = F_{\text{тр}}(y_n + x_n)$$

và

$$\frac{k x_n^2}{2} - \frac{k y_n^2}{2} = F_{\text{тр}}(x_n + y_n+1).$$

Chia hai vế của phương trình thứ nhất cho $y_n + x_n$, ta được $y_n - x_n = 2 \frac{F_{\text{тр}}}{k}$. Tương tự, từ phương trình thứ hai ta được $x_n - y_n+1 = 2 \frac{F_{\text{тр}}}{k}$. Cộng các phương trình thu được, ta tìm được rằng

$$y_n - y_n+1 = 4 \frac{F_{\text{тр}}}{k}$$

(9)

Nhưng $\frac{F_{\text{тр}}}{k} = a$, vì vậy $y_0 - y_1 = y_1 - y_2 = \dots = y_n - y_{n+1} = 4 a$. (10)

Biên độ dao động của vật trong mỗi chu kì giảm đi một đại lượng như nhau, bằng 4a. Thay vào công thức (7) hiệu $y_0 - y_1$ bằng hiệu bằng nó $y_n - y_{n+1}$, ta được $\frac{y_n - y_{n+1}}{y_0} = 0,07$, tức là trong mỗi chu kì biên độ dao động của vật giảm đi $0,07 y_0 = 1,4$ cm. Sau $n$ dao động, nó bằng $y_n = y_0 - n \cdot 0,07 y_0$. Đồng thời, như ta đã nói, biên độ dao động của vật không thể nhỏ hơn $a$. Vì, theo các công thức (7) và (10), $4a = y_0 - y_1 = 0,07 y_0 = 1,4$ cm, nên $a = 0,35$ cm.

Từ điều kiện $y_n \geq a$ hay $20(1 - 0,07n) \geq 0,35$ ta được $n \leq 14,04$. $n$ là số nguyên. Vì vậy vật sẽ thực hiện 14 dao động toàn phần.

Vì $y_{14} = 20(1 - 0,07 \cdot 14) = 0,4$ cm, tức là $y_{14} > a$, nên vật nằm ngoài miền giữa các điểm $A$ và $B$. Do đó lực căng tác dụng lên vật lớn hơn lực ma sát, và vật sẽ thực hiện thêm một phần dao động, dừng lại ở khoảng cách $y$ so với điểm $O$. Hơn nữa vật không thể tới điểm $O$. Khi chuyển động sang trái, vị trí cân bằng của nó là điểm $B$, và vật không thể lệch khỏi điểm $B$ một khoảng lớn hơn $y_{14} - a \approx 0,5$ cm.

Giả sử quãng đường mà vật đi được cho đến khi dừng lại bằng $y_{14} - y$. Năng lượng của hệ tại điểm mà vật dừng lại bằng $\frac{k y_n^2}{2}$. Đặt hiệu năng lượng của hệ bằng công của lực ma sát, ta được phương trình $\frac{k y_{14}^2}{2} - \frac{k y_n^2}{2} = F_{\text{тр}}(y_{14} - y)$. Chia phương trình này cho hiệu khác không $y_{14} - y$, ta được $ky_{14} + ky = 2F_{\text{тр}}$. Từ đó $y = 2 \frac{F_{\text{тр}}}{k} - y_{14} = 2a - y_{14} = 0,3$ cm.

Ф10. Từ bốn lò xo dây mảnh có điện trở $10 \text{ om}$, $20 \text{ om}$, $30 \text{ om}$ và $40 \text{ om}$, được tính để tỏa công suất không quá $2 \text{ om}$ trên mỗi lò xo, hãy ghép một bộ đun có công suất lớn nhất có thể, nếu có một nguồn điện với suất điện động $20 \text{ b}$ và điện trở trong $20 \text{ om}$?

Lời giải. Trước hết, hãy chứng minh rằng trong mạch ngoài tỏa ra công suất càng lớn khi điện trở tải càng gần với điện trở trong của nguồn.

Dòng điện trong mạch, gồm nguồn có suất điện động $\varepsilon$ và điện trở trong $r$ mắc nối tiếp, cùng tải có điện trở $R$, bằng $\frac{\varepsilon}{R + r}$. Vì vậy công suất tỏa ra trên tải là $W = \frac{\varepsilon^2}{(R + r)^2} R$.

Hãy vẽ đồ thị sự phụ thuộc của $W$ vào điện trở tải $R$. Khi $R = 0$, $W = 0$; khi $R \rightarrow \infty$ có thể bỏ qua $r$ so với $R$ trong mẫu số của phân số. Khi đó $W \approx \frac{\varepsilon^2 R}{R^2} = \frac{\varepsilon^2}{R}$.

Tức là khi $R$ lớn ($R \gg r$), đồ thị phụ thuộc của $W$ vào $R$ là một hyperbol, tiệm cận trục $R$. Vì hàm $W(R)$ liên tục, bằng không khi $R = 0$ và giảm khi $R \rightarrow \infty$, nên nó phải có một cực đại. Ta tìm nó.

⟦folio 56⟧

Biểu thức $\frac{\varepsilon^2 R}{(R + r)^2}$ đạt cực đại khi biểu thức nghịch đảo $\frac{(R + r)^2}{\varepsilon^2 R}$ đạt cực tiểu. Nhưng $\frac{(R + r)^2}{\varepsilon^2 R} = \frac{1}{\varepsilon^2} \times \frac{R^2 + 2Rr + r^2}{R} = \frac{2}{\varepsilon^2} r + \frac{1}{\varepsilon^2} \left( R + \frac{r^2}{R} \right)$.

Biểu thức này đạt cực tiểu khi biểu thức $R + \frac{r^2}{R}$ đạt cực tiểu.

Vì $R + \frac{r^2}{R} \geq 2\sqrt{R \cdot \frac{r^2}{R}}$ (mối liên hệ giữa trung bình cộng và trung bình nhân của hai số $R$ và $\frac{r^2}{R}$), nên $R + \frac{r^2}{R} \geq 2r$. Do đó, giá trị nhỏ nhất của tổng $R + \frac{r^2}{R}$ bằng 2r và đạt được khi $r = R$.

Vậy, công suất tỏa ra trên tải là lớn nhất khi $R = r$. Đồ thị phụ thuộc $W(R)$ được chỉ ra ở hình 6. Từ đồ thị thấy rằng $W(R)$ càng lớn khi $R$ càng gần $r$. Điều này có nghĩa là cần ghép các dây xoắn thành một bộ đốt có điện trở càng gần 20 ôm càng tốt. Không thể chỉ dùng dây xoắn có điện trở 20 ôm, vì khi đó trên nó sẽ tỏa ra công suất $W = \left( \frac{\varepsilon}{R + r} \right)^2 R = 5 \text{ ом}$, trong khi mỗi dây xoắn chỉ được tính để tỏa công suất không quá 2 ôm.

Trong tất cả các sơ đồ ghép dây xoắn có thể có, sơ đồ tốt nhất được trình bày ở hình 7. Điện trở của bộ đốt như vậy bằng 20 ôm, công suất tỏa ra trong bộ đốt là $W = \left( \frac{20}{20 + 20} \right)^2 20 = 5 \text{ ом}$. Không khó để tính rằng công suất lớn nhất tỏa ra trên dây xoắn có điện trở 20 ôm và bằng 1,8 ôm.

L. Voronov từ thành phố Yaroslavl đã gửi một lời giải rất hay cho bài toán này. Trong phần phụ lục của lời giải, ông đã phân tích vấn đề hiệu suất của thiết bị điện phụ thuộc thế nào vào điện trở tải.

Vì công suất do nguồn cung cấp bằng $\varepsilon I = \frac{\varepsilon^2}{R + r}$, còn công suất có ích, như ta đã nhận được, bằng $\frac{\varepsilon^2 R}{(R + r)^2}$, nên nếu ký hiệu tỉ số $\frac{R}{r}$ là $\alpha$, ta được biểu thức sau cho hiệu suất $\eta$:

$$\eta = \frac{R}{R + r} = \frac{\alpha}{1 + \alpha}.$$

Hiệu suất lớn khi điện trở tải lớn, khi trong mạch có dòng điện nhỏ. Với $\alpha = 0, \eta = 0$; với $\alpha \rightarrow \infty, \eta \rightarrow 1$. Với $\alpha = 1$, khi trong bộ phận đốt nóng tỏa ra công suất cực đại, $\eta = 0,5$ (50%). Khi đó, dĩ nhiên, ngay trong bản thân nguồn cũng tỏa ra công suất bằng như trong bộ phận đốt nóng. Nguồn trở thành một cái bếp.

⟦folio 57⟧

Hình 8.

Khi tăng hiệu suất của thiết bị, ta đồng thời làm giảm công suất có ích tỏa ra trong tải.

F11. Ba thùng được đổ đầy nước và đặt ở các độ cao khác nhau (hình 8). Từ mỗi thùng có các ống dẫn lên trên, nối với nhau. Các ống cũng được đổ đầy nước. Nước sẽ chảy theo các ống về đâu nếu đồng thời mở các khóa $K_1$, $K_2$ và $K_3$?

Lời giải. Hệ ống sẽ hoạt động như một xi phông. Từ thùng trên, nước sẽ chảy sang thùng giữa và thùng dưới. Ngoài ra, từ thùng giữa nước sẽ chảy sang thùng dưới. Vì tốc độ chảy của nước qua xi phông tỉ lệ với hiệu độ cao mực nước trong các bình, nên trong trường hợp mực nước ở thùng giữa gần với mực nước ở thùng dưới hơn là với mực nước ở thùng trên, thì nước từ thùng trên sẽ chảy vào thùng giữa nhiều hơn nước từ thùng giữa chảy xuống thùng dưới. Trong trường hợp này, cả thùng dưới lẫn thùng giữa đều sẽ được đổ đầy. Nếu mực nước ở thùng giữa gần với mực nước ở thùng trên hơn là với mực nước ở thùng dưới, thì chỉ thùng dưới được đổ đầy do nước chảy ra từ thùng trên và thùng giữa.

Việc đăng ký tạp chí vật lý-toán học phổ thông “Kvant” vẫn tiếp tục. Được tính trước hết cho học sinh lớp 7—10, tạp chí cũng sẽ bổ ích đối với giáo viên, đặc biệt là những người phụ trách các câu lạc bộ hoặc các giờ học tự chọn về vật lý hay toán học, cũng như đối với mọi người yêu toán học và vật lý.

Nội dung chủ yếu của tạp chí là “trường vật lý-toán học”, tức là các tài liệu giúp hiểu rõ hơn vật lý và toán học, học cách vận dụng các khoa học này để nghiên cứu những hiện tượng và quá trình khác nhau mà ta gặp trong thực tế, học giải bài toán.

Trong tạp chí, bạn đọc sẽ tìm thấy nhiều bài toán. Trong đó có những bài toán được ra trong các kỳ thi tuyển sinh vào các trường đại học khác nhau, những bài toán được đề nghị trong các kỳ thi olympic và những bài toán đơn giản là thú vị.

Các ghi chép mô tả dụng cụ và thí nghiệm vật lý sẽ giúp bạn đọc tự tiến hành và kiểm tra thí nghiệm vật lý.

Tạp chí sẽ đăng trên các trang của mình những bài viết có tính chất tổng quan, kể về những thành tựu của khoa học và những vấn đề còn chờ được giải quyết, những câu chuyện về các nhà khoa học và lời kể của chính các nhà khoa học về việc “làm khoa học” như thế nào, về cách xuất hiện các khám phá khoa học.

Tạp chí sẽ thường xuyên thông báo tin tức khoa học, đăng các bài phê bình sách—những sách đã xuất bản và những sách mới đang chuẩn bị xuất bản.

Những mục quan trọng của tạp chí là Sách bài toán của “Kvant”, Phòng thí nghiệm của “Kvant”, “Thực hành cho thí sinh”, “Câu lạc bộ toán học”.

Các tác giả chủ yếu của tạp chí là những nhà khoa học Xô viết và nước ngoài nổi tiếng, những cán bộ khoa học trẻ và các nhà giáo. Tạp chí cũng sẽ dành các trang của mình cho học sinh để mô tả dụng cụ và thí nghiệm, giải thích những vấn đề và bài toán thú vị.

Nhiều tài liệu được viết để bạn đọc làm việc nghiêm túc với cây bút chì trong tay.

Đặt báo bắt đầu từ ngày 1 tháng 9. Giá một số 30 cô-pếch. Giá đặt báo một năm 3 rúp 60 cô-pếch. Khi đặt báo, ghi chỉ số của chúng tôi 70465.
