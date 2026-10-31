---
id: 1982-10-resheniya-zadach-m739-m745-f748-f757-4cf0addc
issue: kvant_1982_10
year: 1982
number: "10"
title: Lời giải bài toán M739—M745; F748—F757
rubric: zadachnik-kvanta
rubric_sub: Задачник «Кванта»
page_first: 31
page_last: 44
page_labels: 29, 30, 32, 33, 34, 35, 36, 37, 38, 39, 40, 41, 42
tag: S02R
lang: vi
source: kvant_digital
extraction: vision
content_sha256: 21635d14f57ac5c8dd0953ee60f1a5b8fff4e9ade70ce7b0c8cd296c28b4e725
prompt_sha256: draft-1
translated_from: content/ru/1982/10/articles/08_resheniya-zadach-m739-m745-f748-f757-4cf0addc.md
source_content_sha256: 2f4dc73101d6bbfd7f97fa4a581b28148d2c9e055d27398e33b7c997a88c5e87
translation_model: draft
translation_run: vi-draft-2026-10-31
translation_quality: draft
---

⟦folio 29⟧

Lời giải bài toán

M739 — M745; F748 — F757

M739. Chứng minh rằng với mọi giá trị của $x$ mà vế trái có nghĩa thì đẳng thức đúng

$$\begin{align*}
tg x + tg \left( x + \frac{\pi}{3} \right) + \\
+ tg \left( x + \frac{2\pi}{3} \right) &: \begin{align*}
tg x \times \\
\times tg \left( x + \frac{\pi}{3} \right) \times \\
\times tg \left( x + \frac{2\pi}{3} \right) \end{align*}
= -3;
\end{align*}$$

$$\begin{align*}
tg x + tg \left( x + \frac{\pi}{n} \right) + \dots \\
\dots + tg \left( x + \frac{(n-1)\pi}{n} \right) &: \begin{align*}
tg x \cdot tg \left( x + \frac{\pi}{n} \right) \times \dots \\
\dots \times tg \left( x + \frac{(n-1)\pi}{n} \right) \end{align*}
= c_n
\end{align*}$$

thức ăn $n$ là số lẻ, $n > 0$, $c_n$ là hằng số (tùy thuộc vào $n$).
c) Tìm $c_n$ cho mọi số lẻ $n$.

a) Đặt $tg x = z$, $tg(\pi/3) = \sqrt{3} = t$, sau đó đặt $tg(2\pi/3) = -t$. Sử dụng công thức tính tang của tổng, chúng ta thu được (tại $zt \neq \pm 1$)

$$\begin{align*}
tg x + tg \left( x + \frac{\pi}{3} \right) + tg \left( x + \frac{2\pi}{3} \right) &= \frac{z + \frac{z+t}{1-zt} + \frac{z-t}{1+zt}}{z \cdot \frac{z+t}{1-zt} \cdot \frac{z-t}{1+zt}} = \\
&= \frac{z (1-z^2 t^2) + 2z + 2zt^2}{z (z^2-t^2)} = \frac{-3z^3 + 9z}{z^3 - 3z} = -3.
\end{align*}$$

6) Sử dụng các công thức rút gọn $tg(x+\pi) = -tg(\pi-x) = tg x$ và số lẻ $n$, dễ dàng chứng minh được cả tử số và mẫu số của phân số

$$f(x) = \frac{tg x + tg \left( x + \frac{\pi}{n} \right) + \dots + tg \left( x + \frac{n-1}{n}\pi \right)}{tg x \cdot tg \left( x + \frac{\pi}{n} \right) \cdot \dots \cdot tg \left( x + \frac{n-1}{n}\pi \right)} = c_n$$

chuyển về 0 tại cùng các điểm của khoảng [0; $\pi$ [: 0, $\frac{\pi}{n}$, $\frac{2\pi}{n}$, ..., $\frac{n-1}{n}$ $\pi$ (và mất ý nghĩa - “chuyển sang vô cực” - cũng tại các điểm tương tự $\frac{\pi}{2n}$, $\frac{3\pi}{2n}$, ..., $\frac{2n-1}{2n}$ $\pi$, điểm mà chúng tôi tiếp tục loại trừ khỏi xem xét). Hãy đặt $tg x = z$, $tg \pi/k = t_k$ ($k=0, 1, \dots, n-1$). Tử số và mẫu số của phân số $f(x)$ có ​​thể được biểu diễn bằng cách thay thế $tg(x+\pi/k/n)$ bằng $(z+t_k)/(1-zt_k)$ dưới dạng tỷ số của các đa thức từ $z$:

$$z + \frac{z+t_1}{1-zt_1} + \dots + \frac{z+t_{n-1}}{1-zt_{n-1}} = \frac{S_1(z)}{R(z)},$$

$$z \cdot \frac{z+t_1}{1-zt_1} \cdot \dots \cdot \frac{z+t_{n-1}}{1-zt_{n-1}} = \frac{S_2(z)}{R(z)},$$

trong đó $R(z) = (1-zt_1) \dots (1-zt_{n-1})$ và cả hai đa thức $S_1(z)$ và $S_2(z)$ đều có bậc $n$ và có cùng nghiệm $t_0=0$, $t_1$, $t_2$, ..., $t_{n-1}$. Thực tế là phân số $f(x)$, tức là $S_1(z)/S_2(z)$, là một hằng số được suy ra ngay từ bổ đề sau:

Bổ đề. Nếu một đa thức $az^n + bz^{n-1} + \dots + d = p(z)$ bậc $n$ có $n$ nghiệm phân biệt $z_0$, $z_1$, ..., $z_{n-1}$, thì thực tế nó chỉ bằng $a(z-z_0)(z-z_1) \dots (z-z_{n-1})$.

Chứng minh bổ đề có thể được chứng minh bằng quy nạp theo bậc $n$ của đa thức $p(z)$. Đối với $n=1$ rõ ràng là: $az+b=a(z-z_0)$, trong đó $z_0=-b/a$. Cho $p(z)$ là đa thức bậc $n+1$ với hệ số cao nhất $a$ và nghiệm $z_0$, $z_1$, ..., $z_{n-1}$. Khi đó $p(z)=p(z)-p(z_n)=az^n+bz^{n-1}+\dots+d-(az_n^n+bz^{n-1}+\dots+d)=a(z^n-z_n^n)+b(z^{n-1}-z_n^n)+\dots=(z-z_n)^q(z)$, trong đó $q(z)$ là đa thức bậc mới với hệ số dẫn đầu $a$ và nghiệm $z_0$, $z_1$, ..., $z_{n-1}$. Theo giả thuyết quy nạp $p(z)=(z-z_0)\cdot a(z-z_0)(z-z_1)$. $\dots(z-z_{n-1})=a(z-z_0)(z-z_1)\dots(z-z_{n-1})$, tức là phát biểu của bổ đề cũng đúng với đa thức bậc $n+1$. (Bằng chứng sử dụng đẳng thức

$$z^k-a^k=(z-a)(z^{k-1}+z^{k-2}a+\dots+z a^{k-2}+a^{k-1}),$$

từ đó rõ ràng rằng $z^k-a^k$ chia hết cho $z-a$.

c) Tìm hằng số $c_n$ cho bất kỳ (lẻ) $n$ nào có độ khó đáng kể. Đáp số: $c_n=(-1)^{\frac{n-1}{2}}n$, tức là $c_3=-3$, $c_5=5$, $c_7=-7$, v.v. Tất cả các giải pháp mà chúng tôi đã đề cập đều sử dụng các thông điệp liên quan đến nghiệm của đa thức.

⟦folio 30⟧

Hằng số $c_n$ có thể được lấy dưới dạng tỷ số giữa các hệ số cao nhất của đa thức $S_1(z)$ và $S_2(z)$. Đối với hệ số đầu tiên, hệ số dẫn đầu là $t_1 t_2 \dots t_{n-1}$, đối với hệ số thứ hai là 1, do đó, $c_n = t_1 t_2 \dots t_{n-1}$. Không khó để tìm ra dấu của tích $t_1 t_2 \dots t_{n-1}$: giữa các tiếp tuyến $t_k = \text{tg} \pi k/n$ bằng $(n-1)/2$ âm (và $t_{n-k} = -t_k$). Một số độc giả đã nhận thấy rằng tích $|t_1 t_2 \dots t_{n-1}|$ có thể được biểu thị dưới dạng tỷ lệ $Q'_n(0)/P_{n-1}(0)$, trong đó $Q_n(x)$ và $P_{n-1}(x)$ là các đa thức Chebyshev được xác định bởi các điều kiện $Q_n(2 \cos \varphi) = 2 \cos n\varphi$, $P_{n-1}(2 \cos \varphi) = \frac{\sin n\varphi}{\sin \varphi}$ (xem bài viết của N. Vasiliev và A. Zelevinsky trong «Kvant», 1982, số 4, trang 17*).

Hãy đưa ra một lý do tương tự nhưng trực tiếp hơn.

Lưu ý rằng $\text{tg} nx$ biến mất tại các điểm 0, $\frac{\pi}{n}, \frac{2\pi}{n}, \dots, \frac{n-1}{n}$ và có thể được biểu thị dưới dạng tỷ lệ $s_n(z)/r_n(z)$ của hai đa thức trong $\text{tg} x = z$; bằng quy nạp, dựa vào công thức

$$\sum_{k=0}^{m} \text{tg}^2 \frac{k\pi}{2m+1} = \frac{m(2m-1)}{3};$$

$$\sum_{k=0}^{m-1} \text{tg} \frac{(4k+1)\pi}{4m} = m;$$

$$\sum_{k=0}^{2m-1} \text{tg} \left(x + \frac{k\pi}{2m}\right) = -\frac{2m}{\text{tg} 2mx};$$

$$\sum_{k=0}^{2m} \text{tg} \left(x + \frac{k\pi}{2m+1}\right) = (2m+1) \cdot \text{tg} (2m+1)x;$$

$$\sum_{k=0}^{2m} \text{tg} \left(x + \frac{k\pi}{2m+1}\right) = (-1)^m \cdot \text{tg} (2m+1)x;$$

$$\sum_{k=0}^{n-1} \sin \left(x + \frac{k\pi}{n}\right) = \frac{1}{2^{n-1}} \sin nx.$$

Hằng số $c_n$ có thể được lấy dưới dạng tỷ số giữa các hệ số cao nhất của đa thức $S_1(z)$ và $S_2(z)$. Đối với hệ số đầu tiên, hệ số dẫn đầu là $t_1 t_2 \dots t_{n-1}$, đối với hệ số thứ hai là 1, do đó, $c_n = t_1 t_2 \dots t_{n-1}$. Không khó để tìm ra dấu của tích $t_1 t_2 \dots t_{n-1}$: giữa các tiếp tuyến $t_k = \text{tg} \pi k/n$ bằng $(n-1)/2$ âm (và $t_{n-k} = -t_k$). Một số độc giả đã nhận thấy rằng tích $|t_1 t_2 \dots t_{n-1}|$ có thể được biểu thị dưới dạng tỷ lệ $Q'_n(0)/P_{n-1}(0)$, trong đó $Q_n(x)$ và $P_{n-1}(x)$ là các đa thức Chebyshev được xác định bởi các điều kiện $Q_n(2 \cos \varphi) = 2 \cos n\varphi$, $P_{n-1}(2 \cos \varphi) = \frac{\sin n\varphi}{\sin \varphi}$ (xem bài viết của N. Vasiliev và A. Zelevinsky trong «Kvant», 1982, số 4, trang 17*).

Trong trường hợp này, đa thức $s_n(z)$ phải có $n$ nghiệm $t_0=0, t_1, \dots, t_{n-1}$ và do đó, theo bổ đề, bằng

$$s_n = e_n z (z-t_1) \dots (z-t_{n-1}) = e_n z^n + \dots + e_n t_1 \dots t_{n-1} z.$$

So sánh (1) và (2), ta được $t_1 t_2 \dots t_{n-1} = e_n n$.

Hãy đưa ra một cách khác để tìm $c_n$. Chúng ta hãy thay thế giá trị $x = \pi/4n$ vào nhận dạng $f(x) = c_n$. Sử dụng các công thức rút gọn $\text{tg} \left(\frac{\pi}{2} - x\right) = \text{tg} \left(\frac{3\pi}{2} - x\right) = 1/\text{tg} x$, không khó để chứng minh rằng tích các tiếp tuyến của các góc $\frac{\pi}{4n}, \frac{5\pi}{4n}, \dots, \frac{(4n-3)\pi}{4n}$ nằm ở mẫu số bằng $(-1)^{\frac{n-1}{2}}$.

Bạn có thể tìm tổng trong tử số dựa trên thực tế là với tất cả các góc $\text{tg} nx = 1$ này và sử dụng công thức (1) (về cơ bản, đó là tìm tổng này sau bài toán M100 - xem «Kvant», 1972, Số 12; một số sự tương ứng giữa các hàm lượng giác thuộc loại này và các hệ quả thú vị từ chúng được phân tích trong cuốn sách bởi A. M. Yaglom và I. M. Yaglom “Non-Zelematrinye bài toán trong bài thuyết trình ở cấp tiểu học” (M., GTTI, 1954), bài toán 130-145).

V. Alekseev, A. Egorov

**M740. Seryozha đổ một ít hạt kê vào chảo hình trụ và hỏi dì Lida hàng xóm của mình: "Bạn cần đổ bao nhiêu nước để có được món cháo ngon?" - “Rất đơn giản,” đáp số-**

a), 6). Chúng ta sẽ giả sử rằng kê lấp đầy một phần nào đó của chảo mà không có khoảng trống, giống như chất lỏng.

Đặt bán kính của một cái chảo hình trụ là $R$, và đổ thật nhiều hạt kê vào sao cho nó dâng lên độ cao $H$

*) Hơn nữa, $Q'_n(x) = nP_{n-1}(x) = |t_1 \dots t_{n-1}| \cdot P_{n-1}(x)$ với tất cả $x$.

⟦folio 32⟧

M742. Trên a) một đường tròn, b) một hình cầu có bán kính 1 có n điểm. Chứng minh rằng tổng bình phương của các khoảng cách theo cặp giữa chúng không lớn hơn $n^2$.

M743. Có N thành phố trong cả nước. a) Có sự liên lạc trực tiếp giữa hai thành phố bất kỳ bằng máy bay hoặc tàu thủy. Chứng minh rằng bằng cách chỉ sử dụng một loại phương tiện giao thông, bạn có thể đi từ bất kỳ thành phố nào đến bất kỳ thành phố nào khác (có thể bằng chuyển tuyến). b) Có sự liên lạc trực tiếp giữa hai thành phố bất kỳ bằng máy bay, tàu hỏa hoặc tàu thủy. Chứng minh rằng bạn có thể chọn ít nhất N/2 thành phố và một trong ba phương thức vận tải để khi sử dụng một trong số chúng, bạn có thể đi từ bất kỳ thành phố nào đã chọn đến bất kỳ thành phố nào đã chọn khác. c) Cho ví dụ chứng minh trong câu b) không thể thay số N/2 bằng số có tính tổng quát hơn.

Hình 1.

a), b) Gọi $O$ là tâm của một đường tròn (hình cầu) nhất định, $X_1, X_2, \dots, X_n$ là các điểm đã cho, $\vec{x}_i = \vec{O}X_i$ ($i=1, 2, \dots, n$), $s$ là tổng bình phương của khoảng cách theo cặp giữa các điểm. Sau đó, kể từ $|X_iX_j|^2 = (\vec{x}_j - \vec{x}_i)^2$,

$$2s = (\vec{x}_1 - \vec{x}_1)^2 + (\vec{x}_1 - \vec{x}_2)^2 + \dots + (\vec{x}_1 - \vec{x}_n)^2 +$$

$$+ (\vec{x}_2 - \vec{x}_1)^2 + (\vec{x}_2 - \vec{x}_2)^2 + \dots + (\vec{x}_2 - \vec{x}_n)^2 + \dots +$$

$$+ (\vec{x}_n - \vec{x}_1)^2 + (\vec{x}_n - \vec{x}_2)^2 + \dots + (\vec{x}_n - \vec{x}_n)^2 =$$

$$= 2n(\vec{x}_1^2 + \vec{x}_2^2 + \dots + \vec{x}_n^2) -$$

$$-2[(\vec{x}_1\vec{x}_1 + \vec{x}_1\vec{x}_2 + \dots + \vec{x}_1\vec{x}_n) + (\vec{x}_2\vec{x}_1 + \vec{x}_2\vec{x}_2 + \dots +$$

$$\dots + \vec{x}_2\vec{x}_n) + \dots + (\vec{x}_n\vec{x}_1 + \vec{x}_n\vec{x}_2 + \dots + \vec{x}_n\vec{x}_n)] =$$

$$= 2n(\vec{x}_1^2 + \vec{x}_2^2 + \dots + \vec{x}_n^2) - 2\vec{x} \cdot \vec{x},$$

ở đâu $\vec{x} = \vec{x}_1 + \vec{x}_2 + \dots + \vec{x}_n$. Do đó, $s = n^2 - |\vec{x}|^2 \leq n^2$, và sự bình đẳng đạt được khi và chỉ khi $\vec{x}_1 + \vec{x}_2 + \dots + \vec{x}_n = \vec{0}$.

Công thức thu được cho tổng bình phương các khoảng cách theo cặp giữa các điểm $X_i$ là một công thức Lagrange rất đặc biệt cho cái gọi là “mômen quán tính” của một hệ có khối lượng chính xác. Bạn có thể đọc thêm thông tin về mômen quán tính, công thức Lagrange và ứng dụng của chúng trong hình học trong các bài viết của M. Balk và N. Grigoriev “Cơ học giúp hình học” («Kvant», 1973, Số 11) và Z. Skopets “Khoảng cách giữa tâm của hai hệ điểm” («Kvant», 1975, Số 3).

V. Prasolov

♦

a) Mệnh đề có thể được chứng minh dễ dàng bằng quy nạp theo $N$. Đối với hai thành phố thì điều đó là hiển nhiên. Hãy để chúng tôi chứng minh điều đó cho $N+1$ thành phố, giả sử rằng nó đúng với $N$ thành phố.

Giả sử $\Gamma$ là một trong các thành phố $N+1$, thì các thành phố $N$ còn lại được kết nối bằng một phương thức vận tải, ví dụ như đường thủy, theo giả thuyết cảm ứng. Nếu ít nhất một trong những thành phố $N$ này có kết nối trực tiếp với thành phố $\Gamma$, thì mọi thứ đều rõ ràng. Mặt khác, những thành phố này được kết nối bằng máy bay với thành phố $\Gamma$, và do đó với bất kỳ thành phố nào khác trong số đó (với chuyển tuyến tại $\Gamma$).

b) Biểu thức lại bài toán như sau:

Cho $N$ điểm, mỗi điểm được kết nối bằng các đoạn màu đỏ, đen hoặc đen. Chúng ta sẽ nói rằng một số điểm này tạo thành một kết nối màu đỏ (xanh lam hoặc đen) nếu chúng có thể được bỏ qua bằng cách chỉ nhìn vào các đoạn màu đỏ (xanh lam hoặc đen). Dễ dàng chứng minh rằng có thể chọn được một liên kết chứa nhiều điểm hơn $A$ và $C \cup D$ cũng là một liên kết đen. Vì số điểm trong liên kết $A = A_0 \cup C$ và $B = B_0 \cup C$ không nhỏ hơn trong liên kết $C \cup D$ nên tập $A_0$ và $B_0$ không trống. Do đó, tất cả dữ liệu $N$ điểm được chia thành hai gói $A_0 \cup B_0$ và $C \cup D$. Tuy nhiên, trong số này phải chứa ít nhất $N/2$ điểm và điều này mâu thuẫn với thực tế là số điểm trong liên kết tối đa $A$ nhỏ hơn $N/2$.

Kết quả mâu thuẫn chứng minh 6).

⟦folio 33⟧

c) Chúng ta hãy xây dựng một ví dụ về tập hợp các điểm $N=4k$ với các đoạn gồm ba màu nối chúng lại, trong đó số điểm trong kết nối tối đa chính xác là $N/2$. (Đối với $N=4k+r$ với $r=1$, 2, 3, cấu trúc tương tự, nhưng kích thước tối đa của kết nối sẽ bằng $[N/2]+1$ và có thể chứng minh rằng trong những trường hợp này, có thể tìm thấy kết nối có kích thước này trong tập hợp.)

Hãy chia tất cả các điểm thành 4 nhóm $A_0, B_0, C$ và $D$ với $k$ điểm trong mỗi nhóm. Chúng ta hãy kết nối bằng các đoạn màu đen tất cả các điểm của tập hợp $A_0$ với tất cả các điểm $B_0$ và tất cả các điểm $C$ với tất cả các điểm $D$. Tương tự, chúng ta nối các điểm của tập hợp $A_0$ và $C$, $B_0$ và $D$ với các đoạn màu đỏ, $A_0$ và $D$, $B_0$ và $C$ với các đoạn màu xanh lam (Hình 2 thể hiện trường hợp $k=2$). Trong mỗi nhóm trong số bốn nhóm, các phân đoạn có thể được vẽ tùy ý - hai điểm bất kỳ của bất kỳ tập hợp $A_0, B_0, C$ và $D$ nào đã được kết nối bằng các đường đứt nét của mỗi màu trong số ba màu.

Dễ dàng nhận thấy rằng với cách tô màu các đoạn như vậy, hai nhóm bất kỳ trong bốn nhóm tạo thành một liên kết có số điểm lớn nhất bằng $2k=N/2$.

L. Kurlyandchik

**M744***. Một tam giác đồng dạng $A_1B_1C_1$ nội tiếp thành tam giác $ABC$ (các đỉnh $\hat{A}_1, \hat{B}_1, \hat{C}_1$ của các phần có kích thước bằng $\hat{A}, \hat{B}, \hat{C}$ lần lượt nằm trên các đoạn BC, CA và AB). Gọi $A_0, B_0, C_0$ là giao điểm của các đường $BB_1$ và $CC_1, AA_1$ và $CC_1, BB_1$ và $AA_1$. Chứng minh rằng sáu đường tròn ngoại tiếp tam giác $ABC_0, BCA_0, ACB_0, A_1B_1C_0, A_1C_1B_0, B_1C_1A_0$ cắt nhau tại một điểm.

**Hình 1.**

**Hình 2.**

lời giải bài toán tự nhiên lớn nhất dựa trên thực tế là tất cả 6 vòng tròn đang được xem xét đều đi qua điểm cố định của phép biến đổi độ tương tự biến $\Delta ABC$ thành $\Delta A_1B_1C_1$ tương tự của nó. Điều quan trọng đối với chúng tôi là chỉ có một sự chuyển đổi như vậy. (Thật vậy, giả sử có hai phép biến đổi tương tự, $\Pi$ và $\Pi_1$, lấy $\Delta ABC$ thành $\Delta A_1B_1C_1$. Sau đó, phép biến đổi tương tự $F=\Pi^{-1}\circ \Pi$ giữ nguyên các điểm $A$, $B$ và $C$ (ví dụ: $F(A)=\Pi^{-1}(\Pi(A))=\Pi^{-1}(A_1)=A$). Do đó, nó suy ra rằng $F$ là giao điểm và hơn nữa là một phép biến đổi đồng nhất. Do đó, phép biến đổi $\Pi^{-1}$ là nghịch đảo của $\Pi$, tức là $\Pi=\Pi_1$.

Bây giờ chúng ta hãy chia các vòng tròn đang được xem xét thành ba cặp: $ABC_0$ và $A_1B_1C_0, BCA_0$ và $B_1C_1A_0, CAB_0$ và $C_1A_1B_0$. Lấy bất kỳ cặp nào trong số này, ví dụ: hình tròn $S$ và $S_1$, ngoại tiếp các hình tam giác $ABC_0$ và $A_1B_1C_0$. Họ có điểm chung $C_0$; lấy $O$ là điểm chung thứ hai của chúng (xem Hình 1; nếu chúng chạm nhau, đặt $O=C_0$). Chúng tôi sẽ chỉ ra rằng có một phép biến đổi tương tự khiến điểm $O$ giữ nguyên và chỉ có điểm đó, và một phép biến đổi từ $\Delta ABC$ thành $\Delta A_1B_1C_1$. Vì các cặp đường tròn $S$ và $S_1$ có thể được thay thế bằng một trong hai cặp còn lại và sẽ thu được cùng một phép biến đổi tương tự, nên cả ba cặp đường tròn phải có một điểm chung, đó là điều chúng ta cần.

Vì vậy, bây giờ hãy để $O \neq C_0$; Chúng ta hãy biểu thị tâm của các vòng tròn $S$ và $S_1$ bằng $Q$ và $Q_1$. Thực hiện xoay tuần tự $R_0^\circ$ quanh điểm $O$ theo một góc $\varphi=QOQ_1$ theo hướng (ngược chiều kim đồng hồ trong hình) và chuẩn bị $H_0^\circ$ với tâm $O$ và hệ số $k=|OQ_1|:|OQ|$, ta thu được phép biến đổi tương tự $\Pi=H_0^\circ \circ R_0^\circ$, biến điểm $Q$ thành $Q_1$. Trong trường hợp này, điểm $O$ (và chỉ nó) giữ nguyên vị trí và vòng tròn $S$ biến thành một vòng tròn có tâm $Q_1$, đi qua điểm $O: \Pi(S)=S_1$. Hãy chứng minh rằng $\Pi$ là phép biến đổi mà chúng ta cần, tức là $\Pi(\Delta ABC)=\Delta A_1B_1C_1$.

Lưu ý rằng các điểm $A$ và $A_1$ nằm ở hai phía đối diện của đường $OC_0$, và do đó nằm trên hai vòng tròn $OC_0$ “bên ngoài” $S$ và $S_1$ (Hình 2). Do đó, góc $OAC_0$ có độ lớn bằng dòng chảy của góc ở tâm $\theta QC_0$, tức là $\theta AA_1=\theta QQ_1$, và tương tự, $\theta A_1A=OQ_1Q$. Vì vậy, $\Delta OAA_1 \sim \Delta OQQ_1$. Mặt khác, $\Delta OQQ_1 \sim \Delta OAA'$, trong đó $A'=\Pi(A)$, vì theo định nghĩa, các phép biến đổi là $\Pi, AOA'=\varphi=QOQ_1$ và $|OA'|=k=|OQ_1|:|OQ|$. Vì vậy, các tam giác $OAA_1$ và $OAA'$ giống nhau và có cạnh chung $OA$, do đó các điểm $A_1$ và $A'$ bằng nhau hoặc đối xứng với $(OA)$ và vì chúng nằm trên đường tròn $S_1, A_1=A'=\Pi(A)$.

⟦folio 34⟧

M745. a) Cho một dãy số ($d_n$) sao cho $|d_n| \leq 1$ ($n=1, 2, \dots$). Chứng minh rằng có thể chọn dãy ($s_n$) từ các số $+1$ và $-1$ sao cho với mọi $n$
$$|d_1s_1 + d_2s_2 + \dots + d_ns_n| \leq 1.$$
6) Cho một chuỗi gồm ba số ($a_n, b_n, c_n$) sao cho $|a_n| \leq 1, |b_n| \leq 1, |c_n| \leq 1$ và $a_n + b_n + c_n = 0$ ($n=1, 2, \dots$). Dựa vào đó, một chuỗi mới gồm ba ($x_n, y_n, z_n$) được xây dựng, trong đó $x_0 = y_0 = z_0 = 0$ và mỗi bộ ba ($x_n, y_n, z_n$) tại $n \geq 1$ được lấy từ bộ ba ($x_{n-1}, y_{n-1}, z_{n-1}$) trước đó bằng cách thêm vào $x_{n-1}$ một trong các số $a_n, b_n, c_n$ mà chúng tôi chọn, cho $y_{n-1}$ - một số khác, cho $z_{n-1}$ - một phần ba. Có phải luôn luôn có thể đảm bảo rằng tất cả các số $x_n, y_n, z_n$ không lớn hơn 1 về giá trị tuyệt đối hoặc ít nhất bị giới hạn bởi một số nội dung?
c) Tìm các câu hỏi tương tự về dãy bốn số.

Hình 1.

Một bằng chứng tương tự được đưa ra là $B_1 = \Pi(B)$. Cuối cùng, hãy để $C' = \Pi(C)$. Như trên, từ sự giống nhau của các tam giác $A_1B_1C' = \Pi(\triangle ABC)$, $ABC$ và $A_1B_1C_1$ suy ra các điểm $C_1$ và $C'$ trùng nhau hoặc đối xứng với ($A_1B_1$). Nhưng các điểm $C$ và $O$ nằm cùng một phía của $(AB)$, nên ảnh $C'$ và $O$ của chúng phải nằm cùng một phía của $(A_1B_1)$, và do đó, $\Pi(C) = C_1^*$).

Nếu các vòng tròn $S$ và $S_1$ chạm vào nhau, thì dễ dàng nhận thấy, dưới dạng phép biến đổi $\Pi$, chúng ta nên lấy hình có tâm $O = C_0$. Trong trường hợp này, các hình tam giác $ABC$ và $A_1B_1C_1$ đang được chuẩn bị, có thể may khi $A_1, B_1$ và $C_1$ là trung điểm của cạnh của tam giác $ABC$ và $A_0 = B_0 = C_0$ là điểm giao nhau của các đường trung tuyến của nó.

D. Izak, V. Dubrovsky

♦
a) Đặt $u_n = s_1d_1 + \dots + s_nd_n$. Các số $s_1, s_2, \dots$ có thể chọn lần lượt như sau: $s_1$ - tùy ý; giả sử $s_1, s_2, \dots, s_n$ đã được chọn sao cho $|u_k| \leq 1$ cho tất cả $k = 1, \dots, n$, thì $s_{n+1}$ được lấy bằng $-1$ nếu các số $u_n$ và $d_{n+1}$ có cùng dấu và $+1$ nếu chúng khác nhau. Thông điệp hoàn toàn rõ ràng mà chúng tôi đang sử dụng ở đây sẽ hữu ích trong tương lai, vì vậy chúng tôi xây dựng nó dưới dạng bổ đề:

Bổ đề. Nếu hai số có dấu khác nhau và mỗi modulo không vượt quá $M$ thì tổng modulo của chúng không vượt quá $M$.

Bổ đề này áp dụng cho các số $u_n$ và $s_{n+1}d_{n+1}$ (trong trường hợp này là $M = 1$).

6) Chúng ta sẽ gọi một bộ ba số là bình thường nếu tổng của chúng bằng 0 và mỗi số không vượt quá modulo 1. Hãy chứng minh rằng chúng ta có thể “cộng” từng bộ ba ($a_n, b_n, c_n$), sắp xếp lại các số trong đó sao cho bộ ba ($x_n, y_n, z_n$) là chuẩn tắc với mọi $n$. Để làm điều này, chỉ cần thay thế nếu bộ ba $(x, y, z)$ và $(a, b, c)$ bình thường, $x \geq y \geq z$ và $a \leq b \leq c$, thì bộ ba $(x+a, y+b, z+c)$ cũng bình thường. Trên thực tế, vì $ax \leq 0$ và $cz \leq 0$, đối với tổng các số cực trị, các bất đẳng thức $|a+x| \leq 1$ và $|c+z| \leq 1$ được thỏa mãn bởi bổ đề (cho $M = 1$), và các số trung bình modulo không lớn hơn 1/2 (nếu $x \leq y \leq z$, thì $x+2y \leq x+y+z=0$, do đó $y \leq -x/2 \leq 1/2$; tương tự, người ta chứng minh rằng $y \geq -1/2$ và $|b| \leq 1/2$).

Bài 6) có cách giải thích hình học màu đỏ. Giữa các bộ ba số có tổng bằng 0 và các điểm trên mặt phẳng, có thể thiết lập sự tương ứng bằng cách sử dụng “hệ tọa độ” trên mặt phẳng, bao gồm ba trục $Ox, Oy$ và $Oz$, tạo các góc với nhau có độ lớn $120^\circ$; trong trường hợp này, mỗi điểm $P$ tương ứng với tọa độ $x, y$ và $z$ của các hình chiếu của nó lên các trục này (xem Hình 1). Vì tổng của vectơ đơn vị $e_x, e_y$ và $e_z$ là 0, $x+y+z = OP \cdot e_x + OP \cdot e_y + OP \cdot e_z = OP \cdot (e_x + e_y + e_z = 0)$. Các điều kiện $|x| \leq 1$, $|y| \leq 1$ và $|z| \leq 1$ xác định ba sọc có chiều rộng 2, vuông góc với các trục; giao điểm của chúng là hình lục giác như trong Hình 1.

Bây giờ chúng tôi có thể gửi lời giải của mình. Hoán vị của hai số trong một bộ ba, tức là hai tọa độ, tương ứng với tính đối xứng của hình lục giác so với các trục $Ox, Oy, Oz$, và hai bộ ba “có thứ tự ngược nhau” $(x, y, z), x \geq y \geq z$ và $(a, b, c), a \leq b \leq c$ là hai vectơ nằm đối diện - đỏ và xanh - tứ giác (xem Hình 1). Tổng của chúng luôn nằm bên trong lục giác nên nếu dịch theo phép đối xứng

*) Có thể thiết lập sự trùng khớp của các điểm $A'$ và $A_1$, $C'$ và $C_1$, dựa trên thông điệp rõ ràng rằng hướng đi qua các đỉnh của các tam giác $OAA'$ và $OAA_1$, cũng như các tam giác $A_1B_1C_1$ và $A_1B_1C_1$, phải giống nhau. Tuy nhiên, nếu bạn cũng thực hiện một phép giải cấu trúc nghiêm ngặt, không tham khảo bản vẽ và thậm chí chỉ xác định chính xác “hướng truyền tải” thì khá khó khăn.

⟦folio 35⟧

vectơ $(a_n, b_n, c_n)$ thành một tứ giác đối diện với vectơ $(x_{n-1}, y_{n-1}, z_{n-1})$ nằm, trước khi thêm chúng, chúng ta sẽ luôn ở bên trong hình lục giác.

Chúng ta cũng hãy lưu ý rằng với sự lựa chọn thích hợp của hệ tọa độ $OXYZ$ trong không gian, cùng một hình lục giác sẽ là một phần của khối lập phương $\{|X| \leq 1, |Y| \leq 1, |Z| \leq 1\}$ theo mặt phẳng $X+Y+Z=0$ (xem Hình 2). Trong trường hợp này, tọa độ của bất kỳ điểm nào trên mặt phẳng lục giác trong hệ $Oxyz$ và $OXYZ$ sẽ trùng nhau.

c) Ở đây không thể khẳng định rằng tất cả các số sẽ có modulo không quá 1, như ví dụ về hai tứ giác $(1; 1; -1; -1)$ và $(1/3; 1/3; 1/3; -1)$ cho thấy: trong số các tổng theo cặp của chúng chắc chắn xuất hiện số 4/3=1+1/3. Tuy nhiên, trong quá trình cộng các tứ giác “sắp xếp lại”, thu được các số không vượt quá một hằng số nhất định; Để chứng minh điều này, sẽ thuận tiện hơn khi thay thế các điều kiện mà các số không vượt quá modulo 1 bằng các điều kiện khác sẽ được bảo toàn trong một phép toán như vậy. Đây là một điều kiện như vậy:

(*) tất cả các số bốn và theo cặp cách nhau không quá 2 (nghĩa là chênh lệch giữa số lớn nhất và số nhỏ nhất không quá 2). Hãy để chúng tôi chứng minh rằng nếu hai bộ tứ $x_1 \geq x_2 \geq x_3 \geq x_4$ và $a_1 \leq a_2 \leq a_3 \leq a_4$ thỏa mãn điều kiện này thì bộ tứ $(x_1+a_1, x_2+a_2, x_3+a_3, x_4+a_4)$ cũng thỏa mãn điều kiện này. Hãy để $1 \leq j < k \leq 4$. thì hiệu $(x_j+a_j) - (x_k+a_k) = (x_j-x_k) + (a_j-a_k)$ modulo không vượt quá 2, vì các số $x_j-x_k$ và $a_j-a_k$ có dấu khác nhau và không có modulo 2 (bổ đề phần a) cho $M=2$. Vì vậy, chúng tôi đã chứng minh rằng có thể cộng bốn số (có thể mỗi lần sắp xếp lại chúng) để các điều kiện (*) được bảo toàn. Cần lưu ý rằng trong bốn số có tổng bằng 0 thỏa mãn điều kiện này, số modulo lớn nhất không vượt quá 3/2; trên thực tế, chẳng hạn, hãy để $x_1>3/2$, sau đó $x_k \geq \frac{3}{2} - \frac{1}{2} - \frac{1}{2} - \frac{1}{2} = 0$; người ta cũng chứng minh tương tự rằng các số $x_j$ không thể nhỏ hơn - 3/2.

Đối với $m$-số có $m \geq 5$, tình huống tương tự như đối với bốn: $m$-số thu được từ một chuỗi các bộ $m$ số nhất định, modulo không quá 1, phù hợp bằng cách hoán vị các số trong tập hợp và phép cộng, sẽ thỏa mãn điều kiện (*); Hơn nữa, nếu tổng của mỗi bộ bằng 0 thì tất cả các số modulo sẽ không vượt quá 2-2/m.

Hình 3 thể hiện cách diễn giải hình học của bài toán c). Thay vì ba trục trên mặt phẳng đi từ tâm của một tam giác đều đến các đỉnh của nó, bạn cần lấy 4 trục trong không gian hướng đến các đỉnh của một tứ diện đều từ tâm của nó. Vì tổng các vectơ hợp nhất của các trục này bằng 0 nên mỗi điểm trong không gian được gán bốn số có tổng bằng 0, bao gồm tọa độ các hình chiếu của điểm này trên trục $Ox_1, Ox_2, Ox_3, Ox_4$. Điều kiện $|x_i| \leq 1$ xác định trong không gian một lớp có độ dày 2, được bao bọc giữa các mặt phẳng vuông góc với trục $Ox_i$; giao điểm của bốn lớp như vậy là một khối bát diện (Hình 3, a). Điều kiện (*) xác định một “hình thoi” trong không gian—một hình 12 mặt đều, tất cả các mặt đều là hình thoi (Hình 3, b)*.

Cố gắng đưa ra cách giải thích hình học của lời giải bài toán c).

N. Vasiliev

*) Khối đa diện này được thay thế bằng thực tế là các bản sao giống hệt của nó có thể được sử dụng để bao phủ toàn bộ không gian mà không có khoảng trống (ví dụ, xem cuốn sách của G. Steinhaus “Kính vạn hoa toán học” (M., “Nauka”, 1981, trang 95). Điều gây tò mò là tâm của các ô chứa đầy như vậy đồng thời đóng vai trò là tâm của các quả bóng tạo thành lớp sàng dày đặc nhất, được đề cập trong danh sách tới lời giải bài toán M740.

⟦folio 36⟧

F748. Một khối lập phương nhỏ trượt dọc theo một thanh sắt xoắn ốc có hình chữ nhật, được cắt trên bề mặt bên trong của một hình trụ rỗng dài vô tận (Hình 1). Bán kính đáy của hình trụ là R, trục vít là h và hệ số ma sát trượt là μ. Tìm tốc độ ổn định của khối lập phương. (Kích thước của khối lập phương và độ sâu của bàn ủi nhỏ hơn R rất nhiều.)

Hình 1.

Đối với lời giải bài toán, việc “mở” hình trụ là thuận tiện. Quỹ đạo của khối khi quét là thẳng, nghiêng một góc α so với đường chân trời (Hình 2).

Khối lập phương chuyển động với tốc độ ổn định khi tổng các hình chiếu của các lực tác dụng lên khối lên phương của đường nghiêng bằng không. Hãy viết ra những điều kiện sau:

$$mg \sin \alpha - \mu mg \cos \alpha - \mu \frac{mv_{\perp}^2}{R} = 0.$$

Ở đây $mg \sin \alpha$ là hình chiếu của lực hấp dẫn, $\mu mg \cos \alpha$ là hình chiếu của lực ma sát lên “đáy” của bàn ủi, $\mu \frac{mv_{\perp}^2}{R}$ là hình chiếu của lực ma sát lên thành bên của bàn ủi (lực này bằng μN, trong đó N là phản lực pháp tuyến từ thành bên, truyền cho khối lập phương gia tốc hướng tâm $\frac{v_{\perp}^2}{R} = \frac{v^2 \cos^2 \alpha}{R}$, tức là $N = \frac{mv^2 \cos^2 \alpha}{R}$). Từ biểu thức (*), xét sin α = $\frac{2\pi R}{\sqrt{4\pi^2 R^2 + h^2}}$ và cos α = $\frac{2\pi R}{\sqrt{4\pi^2 R^2 + h^2}}$, ta tìm được vận tốc ổn định của khối lập phương:

$$v = \sqrt{Rg \sqrt{1 + \left(\frac{h}{2\pi R}\right)^2 \left(\frac{h}{2\pi R}\mu - 1\right)}}.$$

(Từ biểu thức thu được, rõ ràng khối lập phương sẽ chuyển động dọc theo bàn ủi với điều kiện μ < $\frac{h}{2\pi R}$.)

R. Enfijan

F749. Một đĩa lớn đang được sửa chữa quanh một trục thẳng đứng với vận tốc góc Ω. Một đĩa có bán kính r khối lượng m được hạ xuống từ phía trên, trục của đĩa hướng thẳng đứng (Hình 1). Khoảng cách giữa các trục của các đĩa là d (d > r). Hệ số ma sát giữa các bề mặt của đĩa là μ. Xác định vận tốc góc không đổi của đĩa nhỏ. Phải tác dụng mômen lực nào lên trục của đĩa lớn để tốc độ hồi phục của nó không đổi? Không có ma sát trong các trục.

Hãy xem đĩa nhỏ sẽ chuyển động như thế nào ngay sau khi tiếp xúc với đĩa lớn.

Chúng ta hãy chọn hai phần nhỏ giống hệt nhau của một đĩa nhỏ, nằm trên cùng một đường kính đối xứng với tâm của đĩa. Trong Hình 2, các điểm A1 và A2 là trọng tâm của các mặt cắt đó. Tại thời điểm các đĩa tiếp xúc (khi đĩa nhỏ vẫn còn hoạt động xong), vận tốc $\vec{v}_1$ và $\vec{v}_2$ của các điểm của đĩa lớn tiếp xúc với các điểm A1 và A2 của đĩa nhỏ có hướng như trên Hình 2 (|\vec{v} _1| = |\vec{v} _2| = Ω |OA_1| = Ω |OA_2|). Rõ ràng là dọc theo các vectơ $\vec{v}_1$ và $\vec{v}_2$ các lực ma sát $\vec{F}_1$ và $\vec{F}_2$ sẽ có hướng tại thời điểm tiếp xúc, tác dụng từ phía đĩa lớn trong diện tích A1 và A2 của đĩa nhỏ (|\vec{F__1| = |\vec{F__2|). Vì các lực $\vec{F}_1$ so với trục của đĩa nhỏ (l1 trong Hình 2) nhỏ hơn lực $\vec{F}_2$ (l2 trong Hình 2), nên tổng mômen của lực $\vec{F}_1$ và $\vec{F}_2$ sẽ làm xoắn đĩa nhỏ theo hướng xử lý của đĩa lớn.

⟦folio 37⟧

Sau khi kiểm tra các cặp phần tương tự của đĩa nhỏ, chúng tôi đi đến kết luận rằng ngay sau khi chạm vào, đĩa nhỏ bắt đầu xoắn theo hướng quay của đĩa lớn.

Let at some instant of time the angular velocity of the small disk become equal to $\omega$. The speeds of sections $A_1$ and $A_2$ will be equal to the correspondence of $\vec{v}_1$ and $\vec{v}_2$ and $|\vec{v}_1| = |\vec{v}_2| = \omega r$, where $r = |O'A_1| = |O'A_2|$ (Fig. 3). Ma sát mạnh $F_1'$ và $F_2'$ tác dụng lên các vùng này sẽ có hướng dọc theo vectơ $(\vec{v}_1 - \vec{v}_1')$ (tốc độ tương đối của điểm đĩa lớn chạm vào điểm $A_1$) và $(\vec{v}_2 - \vec{v}_2')$ (tốc độ tương đối của điểm đĩa lớn chạm vào điểm $A_2$). Rõ ràng là mômen của cặp lực $F_1'$ và $F_2'$ sẽ làm quay đĩa nhỏ (tức là vận tốc góc của đĩa sẽ thay đổi) nếu $|\vec{v}'| = |\vec{v}'| < \frac{B_1 B_2}{2} = \Omega r$ (xem Hình 3; để tiện so sánh, các vectơ “liên quan” đến điểm $A_2$ cắt nhau tại điểm $A_1$).

Thus, while $\omega < \Omega$, there is a non-zero moment of friction forces that spins the small disk. Tại $\omega = \Omega$, vận tốc tương đối của các phần $A_1$ và $A_2$ hướng vuông góc với đoạn $OO'$ (dọc theo đoạn $A_1 C$ trong Hình 3), và mô men của lực ma sát so với trục của đĩa nhỏ bằng không. Consequently, in the future the small disk will rotate at the set angular speed $\Omega$.

Ở $\omega = \Omega$, tất cả các lực ma sát tác dụng lên các phần giống hệt nhau khác nhau của đĩa nhỏ sẽ có độ lớn tuyệt đối và hướng theo cùng một hướng - vuông góc với đoạn $OO'$. Theo định luật III Newton, tổng hợp lực của toàn bộ lực ma sát tác dụng lên đĩa lớn sẽ tác dụng lên điểm đĩa lớn chạm vào tâm $O'$ của đĩa nhỏ và bằng $\mu m g$. To compensate for the braking moment of this force, a moment of force must be applied to the axis of the large disk

$$M = \mu m g.$$

S. Krotov

F750*. Khi chiều của phần tử E thay đổi thì dòng điện chạy qua nó thay đổi như hình 1. Chiều của phần tử E sẽ thay đổi như thế nào theo thời gian nếu đưa nó vào mạch điện như hình 2 (các thông số mạch được chỉ ra trong hình)? What minimum resistance can a resistor be connected in parallel to element E so that the direction does not remain constant?

Các biên tập viên xin lỗi vì bản vẽ không chính xác được đưa ra trong điều kiện bài toán V. «Kvant» Xếp thứ 4 năm nay (Hình 4 tr. 26).

Hãy xem xét hoạt động của mạch điện kể từ thời điểm nó được bật. Tại thời điểm bật, dòng điện qua cuộn dây và phần tử E bằng 0; trong trường hợp này, hướng tới phần tử cũng bằng 0 và toàn bộ hướng của pin được áp vào cuộn dây. Dòng điện qua cuộn dây (và qua phần tử) bắt đầu tăng. Khi nó đạt đến giá trị $I_1 = 5$ mA, xảy ra hiện tượng nhảy hướng tới phần tử - với dòng điện cố định 5 mA (tok qua cuộn dây không thể thay đổi đột ngột), hướng trên nó ngay lập tức tăng lên $U_1 = 0,8$ V (xem Hình 1). Trong trường hợp này, hướng của cuộn dây đổi dấu ($U_1 > \varepsilon$) và do đó, dòng điện bắt đầu giảm. Tương tự, khi dòng điện giảm xuống giá trị $I_2 = 0,5$ mA, sẽ lại có sự chuyển hướng sang phần tử - nó sẽ giảm gần như xuống $U_2 \approx 0$ và mọi thứ bắt đầu lại từ đầu.

Hãy tính thời gian gần đúng $\tau_1$ để dòng điện tăng từ $I_0 = 0$ lên $I_1 = 5$ mA và thời gian $\tau_2$ để dòng điện giảm từ $I_1 = 5$ mA xuống $I_2 = 0,5$ mA. Vì hướng của phần tử thay đổi ít khi dòng điện tăng từ 0 đến $I_1$, nên chúng ta sẽ giả sử rằng hướng trung bình của cuộn dây trong thời gian $\tau_1$ bằng

$$U_{\kappa 1} \approx 0,2 - 0,1/2 = 0,15 \text{ B}.$$

Tương tự, hướng trung bình của cuộn dây trong thời gian $\tau_2$ sẽ được coi là bằng

$$U_{\kappa 2} \approx \frac{0,8 + 0,6}{2} - 0,2 = 0,5 \text{ B}.$$

⟦folio 38⟧

Khi dòng điện tăng
$$LI' = U_{к1}, \quad I' = \frac{\Delta I}{\tau_1} = \frac{I_1 - I_0}{\tau_1} = \frac{I_1}{\tau_1}.$$
Từ đây chúng ta tìm thấy $\tau_1$:
$$\tau_1 = \frac{LI_1}{U_{к1}} = \frac{10 \cdot 10^{-3} \cdot 5 \cdot 10^{-3}}{15 \cdot 10^{-2}} \approx 0.33 \cdot 10^{-3} \text{ c}.$$
Khi dòng điện giảm
$$LI' = U_{к2}, \quad |I'| = \frac{|I_2 - I_1|}{\tau_2},$$
Ở đâu
$$\tau_2 = \frac{L(I_1 - I_2)}{U_{к2}} = \frac{10 \cdot 10^{-3} \cdot 4,5 \cdot 10^{-3}}{5 \cdot 10^{-1}} = 9 \cdot 10^{-5} \text{ c}.$$
Đồ thị sự thay đổi điện áp trên phần tử E theo thời gian được thể hiện trên Hình 3.

Hãy kết nối một điện trở song song với phần tử. Để điện áp trên phần tử không đổi (nghĩa là tồn tại dao động), điều cần thiết là đặc tính dòng điện-điện áp “tổng” (phần tử + điện trở) phải chứa ít nhất một phần nhỏ trong đó điện áp giảm khi dòng điện tăng (nói đúng ra, tại điểm $U = \mathcal{E}$). Sau khi xây dựng đặc tính cho điện trở ($I = U/R$) và đặc tính “tổng” (bạn tự làm việc này), chúng ta sẽ tìm điện trở tối thiểu mà tại đó điện áp trên phần tử không đổi: $R_{\min} \approx 100 \text{ Om}$.

(Lưu ý rằng sự phụ thuộc $I(U)$, như trong Hình 1, có một thiết bị được sử dụng rộng rãi - một diode đường hầm. Mạch trong Hình 2 là mạch chung của một bộ tạo xung dựa trên một diode đường hầm.)

3. Rafaylov

F751. Một vòng mỏng có bán kính $R$ được đặt trên một hình trụ rất thô có bán kính $r$, nằm ngang (Hình 1). Tìm chu kỳ dao động của vòng trong mặt phẳng thẳng đứng.

Hình 1.

Hình 2.

Để cái vòng lệch khỏi vị trí cân bằng sao cho vectơ bán kính của điểm $A$—điểm mà cái vòng chạm vào hình trụ ở vị trí cân bằng (Hình 2)—tạo một góc nhỏ $\varphi_0$ với phương thẳng đứng. Năng lượng mà vòng có được tại thời điểm lệch tối đa bằng
$$E_0 = Mg(R - r)(1 - \cos \varphi_0)$$
trong đó $M$ là khối lượng của vòng. If you let go of the hoop, it begins to oscillate. In this case, at any moment of time, the total energy of the hoop will be equal to $E_0$.

Nếu góc lệch của vectơ bán kính $OA$ so với phương thẳng đứng bằng $\varphi$ thì thế năng của vòng bằng $E_\pi = Mg(R - r)(1 - \cos \varphi)$ và động năng của nó bằng $E_\kappa = 2 \cdot \frac{M}{2} ((R - r)\varphi')^2$ (chúng ta đã dạy rằng động năng của một vòng, tốc độ tâm bằng $(R - r)\varphi'$, trong đó $\varphi'$ là tốc độ thay đổi của góc $\varphi$, là tổng năng lượng chuyển động của vòng ở giữa và bằng năng lượng quay của nó (vì không bị trượt) quanh tâm). Do đó, tổng năng lượng của vòng là
$$E = E_\pi + E_\kappa = Mg(R - r)(1 - \cos \varphi) + M((R - r)\varphi')^2.$$
Theo định luật bảo toàn năng lượng $E = E_0$, đó là
$$Mg(R - r)(1 - \cos \varphi) + M((R - r)\varphi')^2 = Mg(R - r)(1 - \cos \varphi_0).$$

$$g(R - r)\sin \varphi \cdot \varphi' + 2(R - r)^2\varphi' \varphi'' = 0,$$
hoặc, vì góc $\varphi$ nhỏ bé và tội lỗi $\varphi \approx \varphi$,
$$\varphi'' = -\frac{g}{2(R - r)}\varphi.$$

⟦folio 39⟧

Biểu thức này mô tả các dao động điều hòa có tần số bằng $\omega = \sqrt{g/2(R-r)}$.

$$T = 2\pi \sqrt{\frac{2(R-r)}{g}}.$$

K. Serdeev

F752. Ở khoảng cách $L_1 = 5$ m tính từ một đường thu mỏng có tiêu cự $F = 10$ cm có một mặt phẳng thẳng đứng được chiếu sáng đồng đều $\Pi$. Giữa các đường thẳng và mặt phẳng cách đường thẳng $L_2 = 1$ m có một mặt phẳng thẳng đứng của mặt phẳng khoang rung $l = 5$ cm, trong đó tạo ra một lỗ có đường kính $d = 1$ cm (tâm lỗ nằm trên trục quang chính của đường thẳng). Đường đi sẽ trông như thế nào trên màn hình E, đặt một đường thẳng ở bên phải của nó trong mặt phẳng tiêu điểm? (Các bức tường bên trong của lỗ không phản chiếu ánh sáng.)

Một “màng chắn” bất thường không nằm sát ống kính sẽ ảnh hưởng đáng kể đến hình ảnh - hóa ra đó là một điểm được chiếu sáng không đều. Kích thước của vùng sáng ở trung tâm điểm được xác định bởi hai yếu tố: đường kính của vùng hoàn toàn không bị cản trở của bức tường (mặt phẳng $\Pi$) - nó bằng đường kính $d$ của lỗ - và thực tế là màn hình không nằm trong mặt phẳng của hình ảnh sắc nét - mặt phẳng này nằm cách đường thẳng một khoảng

$$f = \frac{L_1F}{L_1-F} = \frac{500 \cdot 10}{500-10} \approx 10,2 \text{ см.}$$

$$d_1 = d \frac{F}{L_1} = 1 \cdot \frac{10}{500} = 0,02 \text{ см} = 0,2 \text{ мм.}$$

Do yếu tố thứ hai, hình ảnh bị “bẩn”; mức độ “bôi nhọ” phụ thuộc vào đường kính đường $D$. Kỹ thuật ước lượng $D = 2$ xem thì hình ảnh của một điểm trên tường trên màn hình trong mặt phẳng tiêu điểm cùng với điểm đó sẽ là một hình tròn có đường kính

$$d_2 = D \frac{F'-F}{F'} = 2 \frac{10,2-10}{10} = 0,04 \text{ см} = 0,4 \text{ мм.}$$

Như vậy, đường kính của điểm sáng ở giữa ảnh sẽ xấp xỉ 0,6 mm.

Nếu đường thẳng có đường kính lớn thì tổng kích thước của vết sẽ được xác định bằng khoảng cách từ trục của đường thẳng đến những điểm vẫn nhìn thấy được qua điểm khác biệt. Rõ ràng là các lỗ vào và ra của dihdder chặn hoàn toàn các tia từ một điểm trên tường nằm ở khoảng cách lớn hơn

$$r \approx (L_1-L_2) \frac{d}{l} = (500-100) \frac{1}{5} = 80 \text{ см.}$$

Khi đó chỗ đó sẽ có đường kính

$$d_3 \approx 2r \frac{F}{L_1} = 2 \cdot 80 \cdot \frac{10}{500} = 3,2 \text{ см,}$$

và độ chiếu sáng của nó sẽ giảm từ mức tối đa ở vòng tròn trung tâm xuống 0 về phía các cạnh (càng xa trục thì phần quang thông càng bị chặn bởi diferm và góc tới của tia sáng càng tăng).

Để những điều trên là đúng, bạn cần phải có một thấu kính có đường kính $D' \approx 2r \cdot \frac{L_2}{L_1-L_2} = 40 \text{ см.}$. Vì trên thực tế, thấu kính có đường kính đáng kể nên kích thước của điểm lớn được xác định bởi đường kính của đường thẳng và kích thước lỗ vào của màng chắn. Thấu kính nhận tia sáng từ những điểm nằm bên trong đường tròn bán kính $r_1 \approx \frac{L_1-L_2}{L_2} \left( \frac{D}{2} + \frac{d}{2} \right)$. Đối với $D = 2$ cm $r_1 \approx 6$ cm và đường kính tối đa của điểm trên màn hình là

$$d_4 = 2r_1 \frac{F}{L_1} \approx 2 \cdot 6 \cdot \frac{10}{500} \approx 0,24 \text{ см} = 2,4 \text{ мм.}$$

A. Zilberman

F753. Hình 1 thể hiện sự phụ thuộc của điện áp nguồn vào dòng điện

⟦folio 40⟧

erzik. Tìm công suất cực đại có thể thu được từ hiệu điện thế. Điện áp ở điện trở nào? Tại sao một nguồn năng lượng như vậy lại có thể xuất hiện và làm thế nào sự phụ thuộc đó $U(I)$ có thể được triển khai trên thực tế?

Hình 1.

Hình 2

EMF và điện trở trong, chỉ “hoạt động” trong phạm vi giá trị nhất định $U$ và $I$. Từ đồ thị ta xác định:

ở phần $I - \mathcal{E}_1 = U_1(0) = 6$ B,

$$r_1 = \frac{6 \text{ B}}{0,3 \text{ A}} = 20 \text{ Om};$$

ở phần $II - \mathcal{E}_{II} = U_{II}(0) = 3$ B,

$$r_{II} = \frac{3 \text{ B}}{0,6 \text{ A}} = 5 \text{ Om}.$$

Công suất được giải phóng tới điện áp có điện trở $R$ bằng

$$W_R = I^2 R = \frac{\mathcal{E}_2^2 R}{(R + r)^2}.$$

Từ điều kiện $W'_R = 0$ ta tìm được giá trị lớn nhất ở $R$ $W_R$:

$$W'_R = \frac{\mathcal{E}_2^2}{(R + r)^2} - \frac{2 \mathcal{E}_2^2 R}{(R + r)^3} = 0,$$ hoặc $1 - \frac{2R}{R + r} = 0,$

nơi chúng tôi nhận được $R = r$.

Vì vậy, trong phần $I$ và $II$ công suất cực đại được phân bổ cho các điện áp có điện trở bằng giá trị tương ứng

$$R_1 = r_1 = 20 \text{ Om}, \quad R_{II} = r_{II} = 5 \text{ Om}.$$

Điểm trùng khớp trong chuỗi phải bằng nhau

$$I_1 = \frac{\mathcal{E}_1}{R_1 + r_1} = 0,15 \text{ A}, \quad I_{II} = \frac{\mathcal{E}_{II}}{R_{II} + r_{II}} = 0,3 \text{ A}.$$

Cả hai điểm làm việc đều nằm trên các phần tương ứng và do đó, trên mỗi phần đó, công suất điện áp tối đa thực sự được cung cấp.

Công suất tối đa tương ứng bằng nhau

$$W_1 = I_1^2 R_1 = 0,45 \text{ Вт}, \quad W_{II} = I_{II}^2 R_{II} = 0,45 \text{ Вт}.$$

Hình 2 cho thấy một mạch đơn giản cung cấp sự phụ thuộc $U(I)$ trong mạch như trong Hình 1 (chúng tôi coi diode là lý tưởng). Điều thú vị cần lưu ý là với những thay đổi đáng kể về giá trị của điện áp điện trở, công suất trên điện áp hầu như không thay đổi. Điều này có thể rất thuận tiện cho người bán buôn đo nhiệt lượng. Hãy tự suy nghĩ xem đường cong phụ thuộc của $U$ vào $I$ phải như thế nào để hiệu điện thế không phụ thuộc vào giá trị của $R_H$.

A. Zilberman

F754. Con kiến ​​chạy từ tổ kiến ​​theo một đường thẳng sao cho tốc độ của nó tỉ lệ nghịch với khoảng cách đến tâm tổ kiến. Tại thời điểm con kiến ​​đang ở điểm $A$ cách tâm ổ kiến ​​$l_1 = 1$ m thì tốc độ của nó là $v_1 = 2$ cm/s. Con kiến ​​sẽ mất bao lâu để chạy từ điểm $A$ đến điểm $B$, nằm cách tâm ổ kiến ​​$l_2 = 2$ m?

Tốc độ của kiến ​​không thay đổi tuyến tính theo thời gian. Do đó, tốc độ trung bình trên các phần khác nhau của đường đi là khác nhau và chúng tôi không thể sử dụng các công thức đã biết về tốc độ trung bình cho lời giải.

Sử dụng đường đi của kiến, chúng ta chia từ điểm $A$ đến điểm $B$ thành các phần nhỏ đi qua những khoảng thời gian bằng nhau $\Delta t$. Sau đó $\Delta t = \frac{\Delta l}{v_{cp}(\Delta l)}$, trong đó $v_{cp}(\Delta l)$ là tốc độ trung bình trên đoạn này $\Delta l$. Công thức này gợi ý ý tưởng về lời giải bài toán: biểu đồ naissum của đại lượng $\frac{1}{v_{cp}(\Delta l)}$ so với $l$ trên đường đi từ điểm $A$ đến điểm $B$. Đồ thị này là một đoạn thẳng (xem hình). Quả được bảo vệ trong hình dưới phần này có số lượng bằng với thời gian độc quyền. Hãy tính toán nó:

$$S = \frac{1/v_1 + 1/v_2}{2} \left(l_2 - l_1\right) = \left(\frac{1}{2v_1} + \frac{1}{2v_1} \frac{l_2}{l_1}\right) \left(l_2 - l_1\right) = \frac{l_2^2 - l_1^2}{2v_1 l_1}$$

⟦folio 41⟧

(kể từ $\frac{1}{v_2} = \frac{1}{v_1} \frac{l_2}{l_1}$).

Như vậy, con kiến ​​sẽ chạy từ điểm $A$ đến điểm $B$ đúng lúc

$$T = \frac{4-1}{2 \cdot 2 \cdot 10^{-2} \cdot 1} = 75 \text{ с}.$$

S. Krotov

F755. Vệ tinh là một quả cầu cứng nhẹ có bán kính $R = 1$ m và khối lượng $M = 1$ kg, chứa đầy không khí ở áp suất $p = 10^{-3}$ atm và nhiệt độ $T = 300$ K. Tuy nhiên, theo thời gian, hai nhóm mở ra trong thành của quả cầu, nằm cách nhau một khoảng bằng bán kính của quả cầu. Khu vực bang hội $S_1 = 10^{-4} \text{ cm}^2$ và $S_2 = 2 \cdot 10^{-4} \text{ cm}^2$. Tính độ lớn độ lệch của vệ tinh so với đường quỹ đạo trong thời gian $\tau = 100$ s.

Trước khi clan mở ra, áp suất bên trong quả cầu là $p$. Nó là kết quả của sự điều khiển của các phân tử từ bức tường và mỗi phân tử truyền một xung $2mv_\perp$ vào tường, trong đó $v_\perp$ là giá trị tuyệt đối của hình chiếu vận tốc của phân tử vuông góc với tường. Sau khi mở clan, mỗi phân tử chỉ mang xung lực $mv_\perp$ trên “bề mặt” của phản ứng. Do đó, các lực $F_1 = \frac{p}{2} S_1$ và $F_2 = \frac{p}{2} S_2 = pS_1$, hướng dọc theo bán kính, sẽ tác dụng lên quả cầu. Chiếu các lực này lên trục $OX$ và $OY$, ta thấy các hình chiếu $F_x$ và $F_y$ bằng lực tác dụng của các lực này (xem hình):

$$F_x = F_1 \cos 30^\circ + F_2 \cos 30^\circ = \frac{3}{2} pS_1 \cos 30^\circ,$$

$$F_y = -F_1 \sin 30^\circ + F_2 \sin 30^\circ = \frac{1}{2} pS_1 \sin 30^\circ.$$

Như vậy, kết quả của lực chiếu tác dụng lên quả cầu có giá trị tuyệt đối bằng nhau

$$F = \sqrt{F_x^2 + F_y^2} = \sqrt{\frac{7}{4}} pS_1$$

và hướng một góc $\alpha$ với trục $OX$ sao cho

$$tg \alpha = \frac{F_y}{F_x} = \frac{tg 30^\circ}{3}.$$

Tác dụng của lực này sẽ dẫn đến gia tốc đều cho chuyển động của quả cầu, điều này dễ dàng tính được nếu trong khoảng thời gian $T$ khối không khí bên trong quả cầu và áp suất thay đổi không đáng kể. Hãy ước tính sự thay đổi về khối lượng.

Số lượng phân tử chuyển động trong một đơn vị thời gian qua một đơn vị diện tích bề mặt của hình cầu có độ lớn bằng $\frac{1}{6} nv$ (chiều - $m^{-2} c^{-1}$), trong đó $n$ là số lượng phân tử trên một đơn vị thể tích, $v$ là tốc độ trung bình chuyển động của Tellan của các phân tử. Trong thời gian $T$ một khối lượng sẽ chảy qua hai nhánh với tổng diện tích $3S_1$

$$\Delta m \sim m \cdot \frac{1}{6} nv \cdot 3S_1 \tau = \frac{1}{2} qv S_1 \tau,$$

trong đó $q \approx 10^{-3}$ kg/m$^3$, $v \approx 500$ m/s. Thay thế dữ liệu bằng số, chúng ta tìm thấy $\Delta m \sim \frac{5}{2} \cdot 10^{-7}$ kg. Khối lượng ban đầu của không khí là $m_0 = \frac{4}{3} \pi R^3 q \approx 4 \cdot 10^{-3}$ kg. Vì vậy, $\Delta m \ll m_0$.

Giả sử khối lượng không khí và áp suất không đổi, ta tìm hình chiếu gia tốc và độ dịch chuyển của quả cầu trên trục $OX$ và $OY$:

$$a_x = \frac{F_x}{M + m_0} \approx \frac{F_x}{M},$$

$$x = \frac{a_x \tau^2}{2} \approx \frac{F_x}{2M} \tau^2 = \frac{3}{4M} pS_1 \cos 30^\circ \tau^2 = \frac{3\sqrt{3}}{8} \cdot 10^{-2} \text{ m},$$

$$y = \frac{a_y \tau^2}{2} \approx \frac{F_y}{2M} \tau^2 = \frac{1}{4M} pS_1 \sin 30^\circ \tau^2 = \frac{1}{8} \cdot 10^{-2} \text{ m}.$$

A. Stasenko

⟦folio 42⟧

F756. Một bình có thể tích $V=2$ l chứa $m=2$ g hydro và một ít nước. Áp suất trong bình là $p_1=17$ atm. Bình được làm nóng đến mức áp suất trong bình tăng lên $p_2=26$ atm. Bao nhiêu nước bay hơi? Nhiệt độ ban đầu và nhiệt độ cuối cùng là bao nhiêu?
Gợi ý. Sử dụng bảng sự phụ thuộc của áp suất hơi nước bão hòa vào nhiệt độ.

Bài toán là cách giải quyết dễ dàng nhất bằng đồ họa.

Tổng áp suất $p(T)$ trong bình là tổng áp suất của hơi nước bão hòa $p_H(T)$ và áp suất của hydro $p_B(T)$. Theo phương trình Mendeleev-Clapeyron, $p_B(T) = \frac{m_B}{\mu_B V} RT = \frac{2 \cdot 10^{-3}}{2 \cdot 10^{-3} \cdot 2 \cdot 10^{-3}} \cdot 8,3 \cdot T = 4,15 \cdot 10^3 \cdot T$ Pa.

Bằng cách tính $p_B(T)$ cho hai giá trị của $T$ - ví dụ:
$$T = 373 \text{ K} - p_B \approx 15,5 \cdot 10^5 \text{ Pa},$$
$$T = 453 \text{ K} - p_B \approx 18,8 \cdot 10^5 \text{ Pa},$$

— hãy xây dựng biểu đồ $p_B(T)$ (xem hình). Sau khi có được bảng được chỉ định trong điều kiện bài toán, chúng ta xây dựng biểu đồ $p_H(T)$. “Cộng” đồ thị $p_B(T)$ và $p_H(T)$, chúng ta xây dựng đồ thị áp suất trong bình dưới dạng hàm của nhiệt độ. Từ biểu đồ kết quả $p(T)$ (xem hình), chúng ta tìm được nhiệt độ ban đầu và nhiệt độ cuối cùng trong bình:
$$p_1 = 17 \cdot 10^5 \text{ Pa} - T_1 \approx 380 \text{ K},$$
$$p_2 = 26 \cdot 10^5 \text{ Pa} - T_2 \approx 440 \text{ K}.$$

Hãy tìm khối lượng nước bay hơi. Coi hơi nước là một loại khí lý tưởng, chúng tôi xác định áp suất $p_H1$ ban đầu và $p_H2$ cuối cùng của hơi nước trong bình. Để làm điều này, chúng tôi sẽ sử dụng các biểu đồ kết quả. Ở $T_1=380$ K, áp suất hydro là $p_{B1} \approx 15,5 \cdot 10^5$ Pa và
$$p_{H1} = p_1 - p_{B1} \approx 1,5 \cdot 10^5 \text{ Pa}.$$
Tại $T_2=440$ K $p_{B2} \approx 18 \cdot 10^5$ Pa và
$$p_{H2} = p_2 - p_{B2} \approx 8 \cdot 10^5 \text{ Pa}.$$

Hãy viết các phương trình trạng thái của hơi nước tại $p_{H1}$, $T_1$ và $p_{H2}$, $T_2$:
$$p_{H1} V = \frac{m_{n1}}{\mu_n} RT_1, \quad p_{H2} V = \frac{m_{n2}}{\mu_n} RT_2,$$

trong đó $m_{n1}, m_{n2}$ là khối lượng hơi ban đầu và cuối cùng trong bình. Từ đây ta tìm được khối lượng nước bay hơi:
$$\Delta m_n = m_{n2} - m_{n1} = \frac{\mu_n V}{R} \left( \frac{p_{H2}}{T_2} - \frac{p_{H1}}{T_1} \right) =$$
$$= \frac{18 \cdot 10^{-3} \cdot 2 \cdot 10^{-3}}{8,3} \left( \frac{8}{440} - \frac{1,5}{380} \right) \cdot 10^5 \approx 6 \cdot 10^{-3} \text{ кг.}$$

A. Buedin

F757. Để thu được những giọt nước có kích thước đồng đều, người ta sử dụng một ống dẫn chứa một bình chứa lớn chứa đầy nước. Chất lỏng chảy ra khỏi thủ đô khi pornium di chuyển chậm trong bể chứa. Ở bên ngoài, ở đầu tự do của mao quản, một phần tử áp điện được gắn vào, nối với máy phát âm thanh và truyền rung động đến dòng nước. Khi biên độ dao động đạt đến biên độ lớn hơn, tia sẽ vỡ thành những giọt hoàn toàn giống nhau. Tìm bán kính của giọt nước nếu đường kính của ống là $d = 0,2$ mm, tốc độ của chất lỏng chảy là $v = 2$ m/s, tần số dao động của âm thanh là $v = 1000$ Hz.

Khi xảy ra rung động cơ học (âm thanh), hình dạng của tia chảy ra khỏi thủ đô sẽ hơi gợn sóng, như thể hiện trong hình. Nó sẽ tương tự trong trường hợp không có phần tử áp điện - trong trường hợp này, bề mặt của máy bay phản lực bị “nhiễu loạn” bởi cạnh của thủ đô. Dưới tác động của siêu âm, các rung động ở phần cuối của thủ đô tất nhiên sẽ “làm xáo trộn” dòng phản lực mạnh hơn. Do đó, nó sẽ “bằng” sớm hơn khi không có phần tử áp điện. Nhưng trong mọi trường hợp, biên độ của nếp gấp có thể được coi là nhỏ so với bán kính của tia. Vì vậy, trong các tính toán dưới đây, chúng ta sẽ giả sử gần đúng hình dạng của tia là hình trụ. Bán kính của tia sẽ bằng bán kính của giọt nước.

Thật tự nhiên khi cho rằng thể tích của một giọt được xác định bởi lượng chất lỏng chảy ra khỏi mao quản trong một chu kỳ dao động âm thanh:
$$\frac{\pi d^2}{4} v T = \frac{4}{3} \pi R^3.$$
Xét rằng $T=1/v$, chúng tôi tìm thấy:
$$R^3 = \frac{3}{16} \frac{v d^2}{v}, \quad R = \sqrt[3]{\frac{3}{16} \frac{v d^2}{v}}.$$
