---
id: 2024-11-12-resheniya-zadach-m2806-m2809-f2813-f2816-6ff48fdb
issue: kvant_2024_11-12
year: 2024
number: 11-12
title: Lời giải bài toán M2806—M2809; F2813—F2816
rubric: zadachnik-kvanta
rubric_sub: Задачник «Кванта»
page_first: 22
page_last: 30
page_labels: 20-28
tag: D51Y
lang: vi
source: kvant_digital
content_sha256: 62fa9c7f5d9da11ff23bb80b5d77b44c9b8c9b5380087dd3ea50877a90448a85
prompt_sha256: draft-1
translated_from: content/ru/2024/11-12/articles/05_resheniya-zadach-m2806-m2809-f2813-f2816-6ff48fdb.md
source_content_sha256: 97d4757641827ce5368f7452d00ebded38b15ca86654b8230cf33ac4afd57c92
translation_model: draft
translation_run: vi-draft-gaps-2026-11-03
translation_quality: draft
---

⟦folio 20⟧

Lời giải bài toán M2806–M2809, F2813–F2816

⟦column⟧

M2806. Có thể vẽ một đường gãy 20 khâu khép kín trên một mặt phẳng và đánh số các liên kết của nó bằng các số 1, 2, 3, ..., 20 theo thứ tự truyền tải sao cho với mỗi số nguyên dương i = 1, 2, 3, ..., 10 liên kết có số i và 10+i cắt nhau và không cắt các liên kết còn lại?

Đáp số: không thể được. Giả sử điều ngược lại và đặt $A_{1} A_{2}$ ... $A_{20}$ là đường đứt nét đã cho. Gọi A là giao điểm của liên kết $A_{1} A_{2}$ và $A_{11} A_{12}$. Suy ra từ điều kiện 10 mắt xích đầu tiên của đường đứt nét không có điểm chung, trừ hai đầu cuối thì ta có một đường đứt nét khép kín không tự giao nhau $AA_{2} A_{3} A_{4}$... $A_{11} A$, tạm gọi đây là đường đứt nét C (hình 1). Đồng thời

⟦figure⟧

Hình 1

các đỉnh $A_{1}$ và $A_{12}$ sẽ đồng thời ở bên trong hoặc đồng thời bên ngoài đường viền C. Hơn nữa, liên kết $A_{12} A_{13}$ cắt đường viền C đúng một lần, có nghĩa là các đỉnh $A_{12}$ và $A_{13}$ nằm ở các phần khác nhau của mặt phẳng so với đường viền C: một ở bên trong, một ở bên ngoài. Chúng ta suy luận tương tự với các cặp đỉnh $A_{13}$ và $A_{14}, A_{14}$ và $A_{15}$, …, $A_{20}$ và $A_{1}$. Hóa ra $A_{12}, A_{14}$, …, $A_{20}$ nằm ở một phần của mặt phẳng so với đường viền C, và $A_{13}, A_{15}$, …, $A_{19}, A_{1}$ – ở một phần khác. Nhưng điều này mâu thuẫn với kết luận trước đây của chúng tôi rằng $A_{1}$ và $A_{12}$ nằm trong cùng một phần của mặt phẳng đối với C. Điều này hoàn thành lời giải. Đây là sơ đồ của một lời giải khác. Chúng ta hãy sử dụng định lý nổi tiếng sau đây về cách tô màu các miền (thực ra nó khái quát hóa các khái niệm “bên ngoài” và “bên trong” cho các đường đứt nét tự giao nhau).

⟦folio 21⟧

---
running_head:
folio:
---

Định lý. Vẽ một số đường đứt nét khép kín trên mặt phẳng sao cho tập hợp các giao điểm và giao điểm đó là hữu hạn (tức là các đường gãy tạo thành một đồ thị phẳng trong đó mũi tên của mỗi đỉnh là tâm). Khi đó, các vùng trên đó mặt phẳng được chia có thể được tô màu đen và trắng sao cho các vùng có đoạn ranh giới chung được tô màu khác nhau.

Hãy quay lại bài toán và giả sử rằng đường gãy $A_1 \dots A_{20}$, được thảo luận trong các điều kiện, tồn tại. Chúng ta hãy sử dụng cách tô màu của vùng theo định lý. Chúng ta hãy bắt đầu đi qua đường đứt nét, bắt đầu từ liên kết đầu tiên $A_1 A_2$ từ điểm $A$ của giao điểm của các liên kết $A_1 A_2$ và $A_{11} A_{12}$.

Trong quá trình đi vòng quanh, chúng ta sẽ bắt gặp các điểm giao nhau của liên kết thứ 2 và 12, liên kết thứ 3 và 13, v.v. Chúng ta bắt đầu đi bộ sao cho vùng màu đen nằm ở phía bên phải so với hướng di chuyển $\overrightarrow{AA_2}$ (hình 2). Lưu ý sau khi qua nút giao tự ngã tình huống lại ngược lại: nếu vùng đen nằm về phía bên phải so với hướng thì sau khi đi qua nút giao tự ngã tiếp theo, vùng đen sẽ ở phía bên trái và ngược lại. Sau đó, sau khi vượt qua điểm $A$, điểm tự giao nhau thứ 11, vùng màu đen lại nằm ở bên phải hướng. Nhưng nút giao thứ 11 lại là điểm $A$. Hóa ra sau khi vượt qua điểm $A$ một lần nữa, vùng màu đen nằm ở bên phải hướng chuyển động $\overrightarrow{AA_{12}}$, điều này là không chính xác. Sự mâu thuẫn.

Không khó để giải bài bài toán tổng quát về đường đứt liên kết $(2n)$ trong đó chỉ có cặp liên kết $i$ và $i + n$ ($i=1, 2, \dots, n$) giao nhau. Hơn nữa, $n$ dẫn đến mâu thuẫn, như trên với $n=10$. Đối với $n \geq 3$ lẻ, thật dễ dàng để xây dựng một ví dụ và xác minh rằng các đường đứt quãng như vậy có tồn tại.

Để kết luận, chúng tôi lưu ý rằng bài toán này thực sự là một trường hợp đặc biệt của mệnh đề sau, được gọi là định lý Gauss (ví dụ, xem bài viết của S. Tabachnikov “Trên các đường cong phẳng” trong «Kvant» Số 11-12 năm 1988, bài tập 11):

Giả sử một đường đứt nét khép kín có tập hợp hữu hạn các điểm giao nhau của các cặp liên kết. Zanuterum (một cách tùy tiện) những lời chế nhạo này. Tiếp theo, chúng ta sẽ đi vòng quanh đường đứt nét và viết ra số lượng các điểm giao nhau một cách tuần tự theo thứ tự chúng gặp trong quá trình truyền tải. Kết quả là một dãy số trong đó mỗi số xuất hiện hai lần. Khi đó trong dãy giữa hai số giống nhau bất kỳ sẽ có một số nguyên.

I. Efremov, P. Kozhevnikov

M2807. Các số tự nhiên $a, b$ và theo suy nghĩ của chúng ta thì $a^2 + b^2 + c^2 + u a^3 + b^3 + c^3$ đều chia hết cho $a + b + c$. Ngoài ra, GCD $(a + b + c, 6) = 1$. Chứng minh rằng $a^5 + b^5 + c^5$ chia hết cho $(a + b + c)^2$.

Với mọi số nguyên không âm $k$ chúng ta biểu thị $p_k = a^k + b^k + c^k$. Cụ thể là $p_0 = 3$, $p_1 = a + b + c$. Ta cần chứng minh rằng $p_5$ chia hết cho $p_1^2$.

Hãy viết lại đẳng thức
$p_1^2 = (a + b + c)^2 = (a^2 + b^2 + c^2) -$
$-2(ab + bc + ca) = p_2 - 2(ab + bc + ca)$.

Vì theo điều kiện, $p_2$ chia hết cho $p_1$, nên $2(ab + bc + ca)$ cũng chia hết cho $p_1$; và vì $p_1$ nguyên tố cùng nhau với 2 nên $(ab + bc + ca)$ chia hết cho $p_1$.

Hãy sử dụng phần mở rộng
$a^3 + b^3 + c^3 - 3abc =$
$= (a + b + c)(a^2 + b^2 + c^2 - ab - bc - ca)$.

Chúng ta thấy rằng $p_3 - 3abc$ chia hết cho $p_1$ và vì $p_3$ chia hết cho $p_1$ nên chúng ta thu được điều đó

⟦folio 22⟧

---
running_head:
folio:
---

và $3abc$ chia hết cho $p_1$. Theo điều kiện bài toán,
3 nguyên tố cùng nhau với $p_1$ nên $abc$ chia hết cho $p_1$.

Vì vậy, chúng ta đã thu được rằng mỗi biểu thức $s_1 = p_1 = a + b + c$, $s_2 = ab + bc + ca$, $s_3 = abc$ đều chia hết cho $p_1$. (Các biểu thức $s_1, s_2, s_3$ được gọi là hàm đối xứng cơ bản của $a, b, c$.)

Sau đó, chúng ta sử dụng đẳng thức $p_4 = s_1p_3 - s_2p_2 + 3s_3p_1$ (có thể xác minh trực tiếp). Ta thấy rằng mỗi số hạng ở vế phải đều chia hết cho $p_1^2$, nghĩa là $p_4$ chia hết cho $p_1^2$.

Hơn nữa, từ đẳng thức $p_5 = s_1p_4 - s_2p_3 + 3s_3p_2$ (cũng có thể được xác minh trực tiếp), cũng suy ra rằng $p_5$ chia hết cho $p_1^2$, hoàn thành lời giải.

Lưu ý rằng lời giải có thể thu được theo những cách khác, chẳng hạn như bằng cách biểu thị $p_5$ một cách rõ ràng dưới dạng các hàm đối xứng cơ bản. Các công thức mà chúng tôi sử dụng trong lời giải là trường hợp đặc biệt của cái gọi là điểm Newton kết nối các hàm đối xứng $p_i$ và $s_j$ của ba biến $a, b, c$. Chúng ta có thể tiếp tục trình tự các điểm $p_k = s_1p_{k-1} - s_2p_{k-2} + 3s_3p_{k-3}$ (cho $k = 6, 7, \dots$) và chỉ ra rằng trong các điều kiện bài toán $p_{3m}, p_{3m-1}$ và $p_{3m-2}$ được chia cho $p_1^m$ cho tất cả $m = 1, 2, \dots$.

A. Antropov, A. Golovanov,
P. Kozhevnikov

M2808. Một số người tham gia chỉ trích những người khác và mỗi người đều có ít nhất một người bạn. Mỗi người tham gia giải đấu được phát một chiếc áo phông có ghi số của những người khác trong giải đấu trên đó. Chứng minh rằng mặc dù một người tham gia có trung bình cộng các số viết trên áo của người khác nhưng nó không nhỏ hơn trung bình cộng của các số trên tất cả các áo.

Số người tham gia là 1, 2, ..., $N$ và số người tham gia $i$ trống, số người còn lại là $n_i$ (tức là trên áo phông của anh ấy có ghi $n_i$).

Chúng ta hãy đặt $s_i = \frac{n_t + \dots}{n_i}$, trong đó tổng ở tử số được lấy trên tất cả các phần $t$ là bạn của $i$. Giả sử điều ngược lại: mỗi $s_i$ nhỏ hơn mức trung bình của các số còn lại: $s_i < \frac{n_1 + n_2 + \dots + n_N}{N}$. Sau đó, tổng hợp tất cả các phần $i$, chúng ta nhận được rằng $S = s_1 + s_2 + \dots + s_N$ nhỏ hơn $2E = n_1 + n_2 + \dots + n_N$, vì vậy $E$ là số các phần khác (tức là $E$ là số cạnh trong biểu đồ các phần khác của chúng ta). Sắp xếp lại các số hạng trong tổng $S$, chúng ta thấy rằng $S$ bằng tổng của dấu ngoặc $\left(\frac{n_t}{n_i} + \frac{n_i}{n_t}\right)$ trên tất cả các tham số $i - t$.

Mỗi khung như vậy ít nhất là 2 (là tổng các số dương nghịch đảo của nó) và vì số các số khác là $E$ nên chúng ta nhận được $S \geq 2E$. Nhưng điều này mâu thuẫn với bất đẳng thức đã được thiết lập trước đó $S < E$.

P. Kozhevnikov

M2809. Các điểm $M$ và $N$ được chọn lần lượt trên các cạnh $AC$ và $BC$ của tam giác $ABC$ sao cho $AM = BC$ và $CM = BN$ (xem hình). Đặt $O$ là giao điểm của các đoạn $AN$ và $BM$. Tìm góc $ACB$ biết rằng nó lớn gấp đôi góc $AOM$.

Lời giải bài toán được đưa ra trong bài viết “Các biến thể theo chủ đề của một hình học bài toán”.

F2813. Trong một cái bình, tôi đặt một tảng băng có khối lượng $m_\pi$ và đổ đầy một phần nước có khối lượng $m_B$. Sơ đồ (hình 1) hiển thị các khu vực biểu thị trạng thái cuối cùng của lượng chứa trong bình tùy thuộc vào nhiệt độ của một miếng băng $t_\pi \in [-100^\circ C; 0^\circ C]$ và nhiệt độ của các phần nước $t_B \in [0^\circ C; 100^\circ C]$. Được biết, trong khoảng $[-100^\circ C; 0^\circ C]$ nhiệt độ riêng của băng phụ thuộc vào nhiệt độ của nó theo định luật $c_\pi(t_\pi) = c + \alpha t_\pi$, trong đó $c = 2100$ J/(kg °C), $t_\pi$ là nhiệt độ băng tính bằng độ C và $\alpha$ là một giá trị không đổi nào đó. Nhiệt độ riêng của nước là $2c = 4200$ J/(kg °C) và nhiệt độ nóng chảy riêng của nước đá là $\lambda = 336$ kJ/kg = 2cT, trong đó $T = 80^\circ C$. Mười sức chứa của tàu và phòng phấn vẫn còn.

⟦folio 23⟧

---
running_head:
folio:
---

1) Xác định $\alpha$ và $\gamma = m_{\pi}/m_B$.
2) Mục đích chất lượng là một sơ đồ tương tự về trạng thái cuối cùng của lượng chứa trong bình tùy thuộc vào nhiệt độ của một tảng băng $t_{\pi} \in [-100^\circ C; 0^\circ C]$ và nhiệt độ của một phần nước $t_B \in [0^\circ C; 100^\circ C]$, đối với khối lượng băng và nước bằng nhau $m_{\pi} = m_B$. Hãy chỉ ra các điểm đặc trưng trên sơ đồ.

1) Đường trên sơ đồ phân chia trạng thái "băng" và "hỗn hợp nước và băng" tương ứng với băng tại điểm nóng chảy $0^\circ C$. Hãy để chúng tôi rút ra phương trình của dòng này. Lượng nhiệt mà nước tỏa ra khi duy trì cho đến $0^\circ C$ và kết tinh là
$$Q_{\text{отд}} = 2cm_Bt_B + m_B\lambda.$$
Nhiệt dung riêng trung bình của nước đá khi đun nóng từ $t_{\pi}$ đến $0^\circ C$ là
$$c_{\text{cp}} = \frac{c + (c + \alpha t_{\pi})}{2} = c + \frac{\alpha t_{\pi}}{2}.$$
Khi đó lượng nhiệt cần thiết để làm nóng băng đến $0^\circ C$ là
$$Q_{\text{получ}} = c_{\text{cp}}m_{\pi}(-t_{\pi}) = -\left(c + \frac{\alpha t_{\pi}}{2}\right)m_{\pi}t_{\pi}.$$
Vì không có sự mất nhiệt nên
$$Q_{\text{отд}} = Q_{\text{получ}}.$$
Sử dụng ký hiệu $\gamma = m_{\pi}/m_B$ và $\lambda = 2cT$, chúng ta thu được sự phụ thuộc cần thiết:
$$t_B(t_{\pi}) = -T - \frac{\gamma t_{\pi}}{2} - \frac{\alpha \gamma t_{\pi}^2}{4c}.$$

Thay các điểm $(-95; 80)$ và $(-55; 20)$ vào phương trình này, trong đó đường phân chia hàng hóa rơi vào các nút của lưới tọa độ, ta thu được
$$\gamma = 4,0, \alpha = 7,0 \text{ Дж}/\left(\kappa \Gamma \cdot (\deg C)^2\right).$$
2) Xem hình 2.
D.Rubtsov

F2814. Một hình nón cụt, rắn, thẳng, không dẫn điện được tích điện dọc theo bề mặt bên, do đó mật độ điện tích bề mặt của nó phụ thuộc vào khoảng cách đến đỉnh O của toàn bộ hình nón là $\sigma(x) = A/x$, trong đó $A$ là hằng số cực đã biết. Các đáy của hình nón cụt được tích điện đồng đều với mật độ bề mặt $\sigma_1$ và $\sigma_2$ (xem hình). Độ dài của đường sinh và góc dương của khoảng cách của hình nón, hình nón cụt bổ sung cho toàn bộ, bằng $l$ và $\alpha = 30^\circ$ tương ứng, độ dài đường sinh của hình nón cụt là $l$.

⟦folio 24⟧

---
running_head:
folio:
---

1) Đặt $\sigma_1 = -\sigma_2 = \sigma_0$, trong đó $\sigma_0$ là đại lượng đã biết. Tìm vectơ định hướng $\vec{E}_O$ tại điểm O.
Cuối cùng, một kênh nhỏ được khoan để điện tích âm thử nghiệm $-q(q > 0)$ có thể di chuyển ồ ạt dọc theo trục đối xứng của hình nón mà không cần giả vờ. Hơn nữa, $\sigma_1 = \sigma_2 = \sigma_0$ là đúng.
2) Chứng minh rằng tồn tại vị trí cân bằng của điện tích thử nghiệm không phụ thuộc vào giá trị $\sigma_0$. Tìm vị trí cân bằng này. Với đáp số, hãy xem xét từ điểm đó đến điểm O.
3) Ở giá trị nào của $\sigma_0$ thì vị trí cân bằng tìm được sẽ ổn định? Để biết các giá trị tương ứng với trạng thái cân bằng ổn định, hãy tìm chu kỳ dao động nhỏ của điện tích thử trong vòng tròn vị trí cân bằng.
Ghi chú. Hình nón được cố định, khả năng cách điện của hình nón thành công $\varepsilon = 1$, khẳng định ảnh hưởng của trọng lực và hiện tượng từ tính.

1) Hãy chia bề mặt bên thành các vòng và bắt đầu tích phân:
$$E_1 = \int_1^{2l} k \frac{2\pi x \sin \alpha}{x^2} \frac{A}{x} \cos \alpha \cdot dx = \frac{\sqrt{3} A}{8 \varepsilon_0} \int_1^{2l} \frac{1}{x^2} dx = \frac{\sqrt{3}}{16} \frac{A}{\varepsilon_0 l}.$$
Tổng hướng từ các cơ sở $E_2$ bằng không. Sau đó
$$E_O = E_1 = \frac{\sqrt{3}}{16} \frac{A}{\varepsilon_0 l}.$$
2) Khoảng cách từ vị trí cân bằng $F$ đến điểm O là
$$OF = \frac{2\sqrt{3}}{3} l.$$
3) Vị trí cân bằng ổn định trong trường hợp
$$\sigma_0 < \frac{A}{2l},$$
và chu kỳ dao động bằng
$$T = \frac{8\pi}{3} \sqrt{\frac{2}{\sqrt{3}} \frac{m\varepsilon_0 l}{q} \left(\frac{A}{l} - 2\sigma_0\right)^{-1}},$$
trong đó $q$ là phí thử nghiệm.
G. Rastorguev

F2815. Mạch điện được biểu diễn bằng một memrahedron, trong hai cạnh giả tạp của nó có lông vũ và nguồn lý tưởng thứ hai của điện áp không đổi với EMF $\varepsilon_1$ và $\varepsilon_2$ của điện áp tương ứng dọc theo trục đối xứng của hình nón. Tiếp theo, $\sigma_1 = \sigma_2 = \sigma_0$ là đúng.

EMF đáng kể được tạo ra bởi một trong các điện trở được biết đến:
$\varepsilon_1 = 6$ B, $\varepsilon_2 = 12$ B,
$R_2 = 3$ Ôm. Độ lớn của dòng điện qua nguồn lông vũ bằng $I_1 = 1$ A và không thay đổi khi điều chỉnh cực tính của nguồn nối này. Độ lớn của dòng điện chạy qua nguồn thứ hai với cực tính được chỉ định trên hình bằng $I_2 = 2$ A. Có thể xác định được điện trở của các dây được kết nối.

1) Độ lớn của lực moka thông qua nguồn thứ hai sẽ là bao nhiêu nếu cực của nguồn thứ nhất thay đổi?
2) Tìm độ lớn của lực moka qua nguồn thứ hai để loại bỏ khỏi mạch; b) thay thế nguồn thứ nhất bằng một dây nhảy có điện trở bằng 0.
3) Điện trở của các điện trở $R_1$, $R_3$ và $R_4$ là bao nhiêu?

1) Hãy sử dụng phương pháp xếp chồng hiện tại. Chúng ta sẽ tìm cường độ dòng điện trong các nhánh của mạch điện như sự chồng chất của cường độ dòng điện chạy trong các nhánh này dưới tác động của một nguồn, với điều kiện là nguồn kia, do tính lý tưởng của nó, được thay thế bằng một bộ nhảy lý tưởng. Hãy để jumper thay thế nguồn thứ hai. Ta biểu thị cường độ dòng điện chạy qua lông vũ và nguồn thứ hai bằng $I_{11}$ và $I_{21}$ tương ứng với hình 2. Sau đó, khi tính đến cực tính

⟦folio 25⟧

---
running_head:
folio:
---

kết nối của nguồn thứ nhất, hướng của dòng điện $I_{11}$ sẽ thay đổi ngược lại và cường độ dòng điện sẽ không thay đổi. Bây giờ hãy thay thế nguồn đầu tiên bằng một jumper. Chúng ta hãy biểu thị cường độ dòng điện chạy qua nguồn thứ nhất và thứ hai lần lượt là $I_{12}$ và $I_{22}$ (hình 3). Nếu cường độ dòng điện $I_{12}$ khác 0 thì việc duy trì giá trị của tổng dòng điện qua nguồn đầu tiên khi thay đổi cực tính của nó là không thể. Điều này có nghĩa là cường độ hiện tại $I_{1}$ bằng không. Điều này chỉ có thể thực hiện được nếu ghế được cân bằng. Khi đó chúng ta có sự tương ứng sau đây giữa các điện trở:
$$\frac{R_1}{R_2} = \frac{R_3}{R_4}.$$
Lưu ý rằng điều kiện này cũng là điều kiện để cân bằng vị trí mà nguồn đầu tiên được kết nối khi nguồn thứ hai được thay thế bằng jumper $CD$. Điều này có nghĩa là dòng điện $I_{21}$ cũng bằng 0. Từ đó, chúng ta có thể kết luận rằng cường độ dòng điện chạy qua nguồn thứ nhất và thứ hai chỉ được xác định bởi giá trị EMF của nguồn tương ứng và cực tính của các kết nối của chúng. Do đó, cường độ dòng điện $I'_2$ chạy qua nguồn thứ hai khi cực tính của kết nối của nguồn thứ nhất thay đổi bằng
$$I'_2 = I_2 = 2 \text{ A}.$$
2) Độ lớn của dòng điện $I_{2a}$ và $I_{26}$ trong trường hợp a) và b) lần lượt sẽ được xác định bởi điện trở của nơi nối với các cực $C$ và $D$ của nguồn thứ hai:
$$I_{2a} = \frac{\varepsilon_2}{r_a}, I_{26} = \frac{\varepsilon_2}{r_6}.$$
Vì trang web được cân bằng nên việc loại bỏ jumper $AB$ sẽ không làm thay đổi điện trở của trang web giữa các nút $C$ và $D$. Khi đó điện trở của điểm $r_a$ và $r_6$ sẽ bằng nhau và bằng điện trở của nguồn tương đương
$$r_0 = \frac{R_2 R_4}{R_2 + R_4} + \frac{R_1 R_3}{R_1 + R_3},$$
được tìm thấy tại lời giải của điểm đầu tiên, tức là $I_{2a} = I_{26}$. Vì $I_2 = \varepsilon_2/r_0$ thì
$$I_{2a} = I_{26} = I_2 = 2 \text{ A}.$$
3) Cường độ dòng điện $I_1$ và $I_2$ lần lượt chạy qua nguồn thứ nhất và thứ hai được xác định bằng biểu thức
$$\varepsilon_1 = I_1 \left( \frac{R_1 R_2}{R_1 + R_2} + \frac{R_3 R_4}{R_3 + R_4} \right),$$
$$\varepsilon_2 = I_2 \left( \frac{R_2 R_4}{R_2 + R_4} + \frac{R_1 R_3}{R_1 + R_3} \right).$$
Hãy để chúng tôi giới thiệu hai ký hiệu: $R_1 = kR_2, R_4 = \alpha R_2$. Sau đó $R_3 = \alpha kR_2$ và với cường độ hiện tại $I_1$ và $I_2$ chúng ta có
$$I_1 = \frac{\varepsilon_1}{R_2} \frac{1+k}{k(1+\alpha)}, I_2 = \frac{\varepsilon_2}{R_2} \frac{1+\alpha}{\alpha(1+k)},$$
$$I_1 I_2 = \frac{\varepsilon_1 \varepsilon_2}{R_2^2 \alpha k}, \alpha k = \frac{\varepsilon_1 \varepsilon_2}{I_1 I_2 R_2^2} = 4.$$
Lưu ý rằng từ điều kiện bài toán nó tuân theo
$$\frac{\varepsilon_1}{I_1} = \frac{\varepsilon_2}{I_2}.$$
Từ sự tương ứng này và các biểu thức của $I_1$ và $I_2$ chúng ta thu được
$$\frac{\alpha(1+k)}{1+\alpha} = \frac{k(1+\alpha)}{1+k}, \alpha(1+k)^2 = k(1+\alpha)^2,$$
$$\alpha + 2\alpha k + k^2\alpha = k + 2\alpha k + \alpha^2k,$$
$$\alpha + 4k = k + 4\alpha, \alpha = k.$$
Cho rằng $\alpha k = 4$, chúng ta có $k = \alpha = 2$. Sau đó
$$R_1 = R_4 = 2R_2 = 6 \text{ Om}, R_3 = 4R_2 = 12 \text{ Om}.$$
A. Apollonsky

F2816. Trong một khuôn dày làm bằng vật liệu cứng không dẫn điện, vuông góc với bề mặt, người ta khoan một đường kính nhỏ, độ sâu của nó nhỏ hơn litma mạnh (hình 1). Một đầu của sợi dây đàn hồi có hệ số độ cứng được gắn vào “đáy” của vật cản

⟦folio 26⟧

---
running_head:
folio:
---

tic. Chiều dài của dây thun không bị biến dạng trong monostim bằng độ sâu của lỗ. Một hạt có khối lượng m, mang điện tích dương q, được gắn vào đầu kia của sợi dây cao su. Plyma nằm ngang trong vùng mềm mại. Bề mặt của plasma mịn màng. Một từ trường đều được đặt vuông góc với các mặt phẳng bề mặt, vectơ cảm ứng của nó hướng ngược lại với vectơ gia tốc của áp suất tự do. Độ lớn của cảm ứng từ trường bằng B. Khi tính toán cao su, hạt được trộn dọc theo các bề mặt của tấm ở khoảng cách $r_0$ tính từ trục của lỗ và bằng một cú đấm, tạo cho nó một tốc độ cao su vuông góc từ tính, sao cho hạt chuyển động theo hình tròn.
1) Xác định tốc độ góc chuyển động của hạt khi nó quay theo chiều kim đồng hồ và ngược chiều kim đồng hồ (nếu bạn quan sát chuyển động của nó từ trên xuống).
Lực tác dụng lên hạt cũng phụ thuộc vào tốc độ của nó một cách tuyến tính. Do đó, nếu có hai định luật chuyển động khác nhau $\vec{r}_1(t)$ và $\vec{r}_2(t)$, mô tả các chuyển động nhất định của hạt, thì phương trình $\vec{r}(t) = \alpha \vec{r}_1(t) + \beta \vec{r}_2(t)$ đối với bất kỳ hằng số α và β nào thường mô tả định luật thực hiện vật lý chuyển động của hạt này dưới tác động của cùng một lực (xét cho cùng, tốc độ và gia tốc của hạt tại bất kỳ thời điểm nào sẽ được mô tả bằng các châm ngôn kết hợp giống nhau).
Ví dụ, nếu một hạt được thả ra từ cùng vị trí ban đầu như ở điểm 1 mà không có tốc độ ban đầu, thì định luật chuyển động của nó có thể được tìm thấy do sự áp đặt (chồng chất) của các định luật y học được nghiên cứu ở điểm này.
2) Khoảng cách tối thiểu mà hạt tiếp cận trục của lỗ sau khi bị gặm mà không có tốc độ ban đầu từ khoảng cách $r_0$ tính từ lỗ là bao nhiêu?
3) Sau bao nhiêu thời gian t, sau khi lấy hạt ra, chúng ta sẽ thấy mình ở khoảng cách $r_0$ tính từ trục của lỗ?
4) Hình ảnh quỹ đạo hạt của trường hợp $q^2 B^2 / (mk) = 1/2$. Sẽ mất bao lâu sau khi hạt được lấy ra lần đầu tiên để chúng ta trở lại điểm xuất phát?

1) Phương trình chuyển động của hạt trên dây đàn hồi trong từ trường $\vec{B}$ có dạng
$$m\vec{a} = -k\vec{r} + q[\vec{v} + \vec{B}],$$
tức là nó là một phương trình tuyến tính và đồng nhất theo định luật chuyển động $\vec{r}(t)$. Khi chuyển động dọc theo một đường tròn bán kính $r_0$, gia tốc hướng tâm của hạt được tạo ra bởi lực đàn hồi của dây cao su và lực Lorentz, tùy theo hướng quay mà lực Lorentz hướng vào tâm vòng tròn hoặc hướng ra xa tâm vòng tròn. Điều này có nghĩa là vận tốc góc của hạt được tìm thấy từ phương trình
$$m\omega^2 r_0 = kr_0 \pm qB\omega r_0,$$
$$\omega^2 = \pm \frac{qB}{m}\omega - \frac{k}{m} = 0.$$
Tiếp theo, chúng tôi giới thiệu các ký hiệu $\Omega = \frac{qB}{2m}$ và $\omega_0^2 = \frac{k}{m}$. Sau đó, chọn một nghiệm dương cho mỗi trường hợp, chúng ta đi đến kết luận rằng khi quay theo chiều kim đồng hồ độ lớn của vận tốc góc
$$\omega_1 = \sqrt{\omega_0^2 + \Omega^2} + \Omega = \sqrt{\frac{k}{m} + \frac{q^2 B^2}{4m^2}} + \frac{qB}{2m},$$
và khi quay ngược chiều kim đồng hồ
$$\omega_2 = \sqrt{\omega_0^2 + \Omega^2} - \Omega = \sqrt{\frac{k}{m} + \frac{q^2 B^2}{4m^2}} - \frac{qB}{2m} < \omega_1.$$
2) Gọi $\vec{r}_1(t)$ là định luật chuyển động của một hạt quay dọc theo một vòng tròn bán kính $r_0$ theo chiều kim đồng hồ và $\vec{r}_2(t)$ là định luật chuyển động của một hạt quay dọc theo vòng tròn đó ngược chiều kim đồng hồ. Mô-đun tốc độ di chuyển của hạt trong các chuyển động này khác nhau: $|\vec{v}_1| = \omega_1 r_0$ và $|\vec{v}_2| = \omega_2 r_0$. Nếu chúng ta viết sự chồng chất của các định luật chuyển động này dưới dạng
$$\vec{r}(t) = \frac{\omega_2}{\omega_1 + \omega_2}\vec{r}_1(t) + \frac{\omega_1}{\omega_1 + \omega_2}\vec{r}_2(t),$$
khi đó, phù hợp với tính tuyến tính và tính đồng nhất của phương trình chuyển động, định luật này cũng thỏa mãn phương trình chuyển động. Có thể dễ dàng xác định các điều kiện ban đầu mà nó tương ứng: vì $\vec{r}_1(0) = \vec{r}_2(0) = \vec{r}_0$ và đối với các hướng quay khác nhau $|\vec{v}_1(0)| = \omega_1 r_0 = \frac{\omega_1}{\omega_2}|\vec{v}_2(0)|$, thì $\vec{r}(0) = \vec{r}_0$ và $\vec{v}(0) = 0$. Vì vậy, theo

⟦folio 27⟧

---
running_head:
folio:
---

định luật kết quả mô tả chuyển động của một hạt được phóng mà không có tốc độ ban đầu từ khoảng cách $r_0$ tính từ lỗ và vectơ tọa độ của hạt đó có thể được tìm thấy bất cứ lúc nào dưới dạng tổng của vectơ $\frac{\omega_2}{\omega_1 + \omega_2} \vec{r}_1(t)$ có độ dài không đổi $\frac{\omega_2}{\omega_1 + \omega_2} r_0$, quay với vận tốc góc $\omega_1$ theo chiều kim đồng hồ và vectơ $\frac{\omega_1}{\omega_1 + \omega_2} \vec{r}_2(t)$ có độ dài không đổi $\frac{\omega_1}{\omega_1 + \omega_2} r_0$, quay với vận tốc góc $\omega_2$ ngược chiều kim đồng hồ từ cùng vị trí ban đầu (hình 2). Lưu ý rằng góc giữa các vectơ này tại thời điểm $t$ bằng $\varphi(t) = (\omega_1 + \omega_2) t$. Do đó, theo định lý tiền xu, tại thời điểm này khoảng cách từ hạt đến lỗ thỏa mãn phương trình
$$r^2(t) = \left( \frac{\omega_2}{\omega_1 + \omega_2} r_0 \right)^2 + \left( \frac{\omega_1}{\omega_1 + \omega_2} r_0 \right)^2 + 2 \frac{\omega_2}{\omega_1 + \omega_2} r_0 \frac{\omega_1}{\omega_1 + \omega_2} r_0 \cos \left( (\omega_1 + \omega_2) t \right).$$
Có nghĩa,
$$r(t) = \frac{r_0}{\omega_1 + \omega_2} \sqrt{\omega_1^2 + \omega_2^2 + 2\omega_1\omega_2 \cos \left( (\omega_1 + \omega_2) t \right)}.$$
Do đó, tần số thay đổi theo chu kỳ trong khoảng cách từ hạt đến vị trí cân bằng bằng $\omega_1 + \omega_2 = 2\sqrt{\omega_0^2 + \Omega^2}$, lấy giá trị tối thiểu
$$r_{\min} = \frac{\omega_1 - \omega_2}{\omega_1 + \omega_2} r_0 = \frac{\Omega}{\sqrt{\omega_0^2 + \Omega^2}} r_0$$
khoảng cách mất một lúc
$$t_n = \frac{\pi}{\sqrt{\omega_0^2 + \Omega^2}} \left( n + \frac{1}{2} \right),$$ ở đâu $n = 0, 1, 2, \dots$.

Lưu ý rằng để tìm $r_{\min}$ không cần thiết phải nghiên cứu định luật thay đổi khoảng cách $r(t)$: chỉ cần hiểu rằng khoảng cách từ hạt đến lỗ là tối thiểu khi các vectơ của các vectơ “thành phần” của sự chồng chất của chúng ta hướng ngược nhau. Khi đó rõ ràng là $r_{\min}$ bằng hiệu của mô hình của họ.

3) Từ công thức cho $r(t)$, rõ ràng khoảng cách tối đa từ hạt đến lỗ bằng khoảng cách ban đầu: $r_{\max} = r_0$, và nó đạt được tại thời điểm đó
$$t'_n = \frac{\pi}{\sqrt{\omega_0^2 + \Omega^2}} n,$$ ở đâu $n = 0, 1, 2, \dots$.

Như bạn có thể thấy, lần đầu tiên sau khi phát hành, điều này sẽ xảy ra vào thời điểm đó
$$\tau = \frac{\pi}{\sqrt{\omega_0^2 + \Omega^2}}.$$

4) Với sự tương ứng của các tham số như vậy, $\Omega^2 = \omega_0^2/8$, do đó, $\omega_1 = \omega_0\sqrt{2}$ và $\omega_2 = \omega_0/\sqrt{2}$. Điều này có nghĩa là tỷ lệ vận tốc góc là $\omega_1: \omega_2 = 2:1$, tức là chuyển động tổng quát là tuần hoàn và quỹ đạo hóa ra là khép kín. Trong trường hợp này
$$\vec{r}(t) = \frac{1}{3}\vec{r}_1(t) + \frac{2}{3}\vec{r}_2(t),$$
độ dài của các vectơ có tổng cho $\vec{r}(t)$ bằng $r_0/3$ và $2r_0/3$, và định luật thay đổi khoảng cách trông như sau:
$$r(t) = \frac{r_0}{3}\sqrt{5 + 4\cos(3\omega_2 t)}.$$
Rõ ràng rằng chu kỳ chuyển động là bội số chung nhỏ nhất của chu kỳ của hai thành phần chuyển động, trong trường hợp của chúng ta bằng chu kỳ nhỏ hơn tần số $\omega_2$. Vì vậy, lần đầu tiên sau khi được thả ra, hạt sẽ tự tìm đến điểm xuất phát của thời gian.
$$T_1 = \frac{2\pi}{\omega_2} = \frac{2\pi\sqrt{2}}{\omega_0} = 2\pi\sqrt{\frac{2m}{k}},$$
và khoảng thời gian thay đổi khoảng cách từ lỗ
$$T = \frac{2\pi}{\omega_1 + \omega_2} = \frac{2\pi\sqrt{2}}{3\omega_0} = \frac{1}{3}T_1.$$

⟦folio 28⟧

KVANT 2024/Số. 12-11

Do đó, trong một khoảng thời gian chuyển động, hạt đạt khoảng cách tối đa $r_{0}$ ba lần và khoảng cách tối thiểu $r_{0} 3$ ba lần. Do đó, quỹ đạo cho một vòng quay hoàn toàn quanh trục của lỗ đi ba lần từ một vòng tròn có bán kính $r_{0}$ đến một vòng tròn có bán kính $r_{0} 3$ và ngược lại, và gần các điểm chung có vòng tròn lớn hơn, hạt sẽ di chuyển dọc theo bán kính (quỹ đạo chạm vào bán kính), tại các điểm chung có vòng tròn nhỏ hơn, tốc độ hướng tâm của hạt trở thành 0 với vận tốc góc khác 0 - hạt di chuyển vuông góc với bán kính và quỹ đạo của nó chạm vào vòng tròn nhỏ hơn tại các điểm chung. Sử dụng thông tin này, có thể mô tả khá chính xác loại quỹ đạo (hình 3). A. Apolonsky, K. Parfenov
