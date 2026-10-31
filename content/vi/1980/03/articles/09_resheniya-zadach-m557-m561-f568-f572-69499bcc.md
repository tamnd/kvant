---
id: 1980-3-resheniya-zadach-m557-m561-f568-f572-69499bcc
issue: kvant_1980_3
year: 1980
number: "3"
title: Lời giải bài toán M557—M561; F568—F572
rubric: zadachnik-kvanta
rubric_sub: Задачник «Кванта»
page_first: 30
page_last: 37
page_labels: 28-35
tag: 0U9H
lang: vi
source: kvant_digital
extraction: vision
content_sha256: 6a7d85ce28c90ebf9f10ed0936dbbb6e12838ba7bbde0952338b9875d3a2a4bb
prompt_sha256: draft-1
translated_from: content/ru/1980/03/articles/09_resheniya-zadach-m557-m561-f568-f572-69499bcc.md
source_content_sha256: 486cf43cd1eb10840c79fd61df7262c928e3a39f76f069b2d53c241290ccb2cf
translation_model: draft
translation_run: vi-draft-2026-10-31
translation_quality: draft
---

⟦folio 28⟧

Lời giải bài toán
M557—M561; F568—F572

M557. Cho n trong các cặp số nguyên tố lớn hơn 1 và nhỏ hơn (2n-1)². Chứng minh rằng trong số đó chắc chắn sẽ có số nguyên tố.

Mệnh đề bài toán sẽ được chứng minh bằng phản chứng. Giả sử rằng tất cả các số $a_1, a_2, \dots, a_n$ đã cho là hợp số. Chúng ta hãy liên kết với mỗi số đó ước số nguyên tố tối thiểu của nó: $a_i \rightarrow q_i$. Hãy để $q = \max_{1 \leq i \leq n} \{q_i\}$. thì $q \geq p_n$, trong đó $p_n$ là số nguyên tố n-e (vì các số $a_1, \dots, a_n$ là số nguyên tố chung theo cặp).

Chỉ thị trên $k$ dễ dàng chứng minh bất đẳng thức $p_k \geq 2k - 1$. (Thật vậy, nó đúng với $p_2 = 3$. Khi đó $p_{k+1} \geq p_k + 2$ cho $k \geq 2$.) Do đó $q \geq 2n - 1$. Do đó, đối với $a_j$ mà $q_j = q$,

$$a_j \geq q_j^2 \geq (2n-1)^2$$

- một sự mâu thuẫn. Điều này có nghĩa là trong số những số này chắc chắn sẽ có số nguyên tố.

A. Kolotov

M558. Có $k > 1$ khu vực màu đen trong vòng tròn, bất kỳ khu vực nào trong số đó nhỏ hơn $180^\circ / (k^2 - k + 1)$. Chứng minh rằng đường tròn có thể quay quanh tâm O sao cho tất cả các cung đen đều đi vào phần trắng của đường tròn.

Hình 1.

Đặt hai vòng tròn được gấp lại với nhau, trên một trong số đó có r cung màu đen với các góc ở tâm $a_1, a_2, \dots, a_r$, mặt khác - s các cung màu xanh lam có các góc $\beta_1, \beta_2, \dots, \beta_s$ (Hình 1). Chúng ta hãy cố gắng tìm những điều kiện phù hợp để có thể xoay vòng tròn có các phần màu xanh lam theo một góc sao cho $\varphi$ ($0 < \varphi < 2\pi$) sao cho không có phần màu xanh nào giao nhau với các phần màu đen.

Thật thuận tiện khi đánh dấu các góc quay $\varphi$ trên một vòng tròn đặc biệt $c$ có chiều dài $2\pi$ với điểm 0 (không) cho trước trên đó. “Hãy rẽ” bài toán khác đi. Hãy đánh dấu ở $c$ tất cả các góc bị cấm $\varphi$ - những góc đó, khi quay qua, bán kính màu xanh nào đó trùng với bán kính màu đen nào đó. Mỗi cặp (khu vực màu đen có góc $a_i$, khu vực màu xanh lam có góc $\beta_j$) đưa ra một khoảng bị cấm $\varphi$ có độ dài $a_i + \beta_j$. Do đó, nếu cái gì là $a_i < \pi/k$, cụ thể, nếu cái gì là $a_i < \pi/k^2$. Cũng có thể chứng minh nhận định cho các cung có góc $a_i < \gamma = \pi / (k^2 - k + 1)$, nhưng trong trường hợp này, chúng ta có thể tinh chỉnh ước tính

*) Tổng $\sum_{i,j} \text{ произвольных } i = 1, 2, \dots, r, j = 1, 2, \dots, s$.

Hình 2.

⟦folio 29⟧

chiều dài của tập hợp “bị cấm”. Tất cả các khoảng “bị cấm” tương ứng với các tham số của các phần phù hợp ($\alpha_i, \alpha_i$) được chứa trong một khoảng có độ dài $2\gamma$ với tâm $O$. Và tổng tất cả các giá trị khác của góc cấm

$$\sum_{i,j,i \neq j} (\alpha_i + \alpha_j) = 2(k-1)\sum_i \alpha_i$$

biến $2(k-1)k\gamma = 2\pi - 2\gamma$, vì vậy trong trường hợp này có giá trị “không bị cấm” $\varphi$.

Bài toán lời giải, nhưng câu hỏi đặt ra là liệu giới hạn cho $\alpha_i$ cũng có thể được nâng lên hay không? Tuyên bố bài toán, nói chung, không đúng nếu các góc của tất cả các cung $k$ được coi là có độ lớn bằng $\gamma = \pi/(k^2-k+1)$. Các ví dụ bác bỏ cho $k=2, 3, 4, 5$ rất thú vị (Hình 2): các điểm màu đỏ - điểm cuối của các đường phân giác của các cung - phải nằm ở $k$ các đỉnh của một giác đều ($k^2-k+1$), được chọn sao cho với bất kỳ $m=1, 2, ..., k^2-k$ nào cũng có một cặp điểm màu đỏ giữa các cạnh $m$ (theo hướng này hay hướng khác dọc theo đường tròn) ($k^2-k+1$)-gon. Kiểm tra xem “bộ bị cấm” có phải là tất cả $\varphi \in [0; 2\pi]$ hay không.

bài toán bản thân nó là tổ hợp: để làm gì $k$ chúng ta có thể sắp xếp $k$ các điểm đỏ trên một vòng tròn có chiều dài $2C_k^2+1=k^2-k+1$ sao cho với bất kỳ $m=1, 2, ..., k^2-k$ nào cũng có một cặp điểm đỏ giữa đó $m$ các cạnh của một ($k^2-k+1$)-giác được đặt (theo hướng này hay hướng khác dọc theo đường tròn). Kiểm tra xem “bộ bị cấm” có phải là $\varphi \in [0; 2\pi]$ hay không.

bài toán bản thân nó là tổ hợp: để làm gì $k$ chúng ta có thể sắp xếp $k$ các điểm đỏ trên một vòng tròn có chiều dài $2C_k^2+1=k^2-k+1$ sao cho với bất kỳ $m=1, 2, ..., k^2-k$ nào cũng có một cặp điểm đỏ giữa đó $m$ các cạnh của một ($k^2-k+1$)-giác được đặt (theo hướng này hay hướng khác dọc theo đường tròn). Kiểm tra xem “bộ bị cấm” có phải là $\varphi \in [0; 2\pi]$ hay không.

Hãy để một số $k$ một bộ màu đỏ $\Pi_0$ tồn tại. Sau đó, $\Pi_0$ và hình ảnh $\Pi_m$ ($m=1, 2, ..., k^2-k$) của nó, khi được xoay theo góc $m\gamma, \gamma=\pi/(k^2-k+1)$, có các thuộc tính sau:

1°. Đối với bất kỳ $i \neq j$ giao điểm $\Pi_i \cap \Pi_j$ bao gồm một điểm.

2°. Hai điểm bất kỳ trong tập hợp $\Pi = \bigcup_m \Pi_m$ (các đỉnh của ($k^2-k+1$)-giác) đều thuộc về chính xác một trong $\Pi_m$.

3°. Có bốn điểm của tập hợp $\Pi$ không chứa trong một $\Pi_i$.

Tập $\Pi$ với hệ tập con $\Pi_m \subset \Pi$ như vậy được gọi là mặt phẳng xạ ảnh hữu hạn*). Được biết, mặt phẳng xạ ảnh hữu hạn tồn tại với $k=p^r+1$, trong đó $p$ là số nguyên tố, $r$ là số tự nhiên (ví dụ: $k=3, 4, 5, 6, 8, 9$) và không tồn tại nếu $k=7, 15$; Rõ ràng rồi; bây giờ trong trường hợp sau không thể có ví dụ bác bỏ trong bài toán M558 (vì vậy, ví dụ, đối với bảy cung có góc $\pi/43$ tuyên bố của cô ấy là đúng). Nhưng đối với $k=10$, vấn đề vẫn chưa thể được giải quyết ngay cả khi có sự trợ giúp của máy tính.

Lưu ý rằng không cần phải có mặt phẳng xạ ảnh hữu hạn và không cần phải đánh số các điểm “theo chu kỳ” như vậy, trong đó các đường thẳng $\Pi_m$ được lấy từ nhau bằng hai số - yêu cầu bổ sung này có thể giúp dễ dàng chứng minh sự vắng mặt của các “mặt phẳng tuần hoàn” như vậy đối với một số $k$. (Lưu ý rằng tất cả các mặt phẳng xạ ảnh trên một trường hữu hạn gồm $p^r$ phần tử đều có cách đánh số tuần hoàn như vậy; hãy xem điều này trong chương “Tập sai phân” trong sách của M. Hall.)

N. Vasiliev, G. Galperin, V. Proizvolov

*) Chúng tôi đã gặp trong «Kvant» rằng bài toán, khác nhau về nội dung, ảnh hưởng đến khái niệm này - ví dụ: xem bài toán M5, («Kvant», 1970, Số 1) và M335 («Kvant», 1975, Số 7). Số $n=k-1$ được gọi là "bậc" của mặt phẳng xạ ảnh; ở đây $k=n+1$ là số điểm trên “đường” $\Pi_n$ (và số “đường” đi qua một điểm cho trước; những con số này luôn giống nhau đối với tất cả các điểm và “đường”). Để biết thông tin về các mặt phẳng xạ ảnh hữu hạn, xem cuốn sách “Đại số hình học” của E. Artin (M., “Nauka”, 1969) và cuốn sách “Combinatorics” của M. Hall (M., “Mir”, 1970).

⟦folio 30⟧

M559. Chứng minh rằng nếu $x, y, z$ là độ dài một cạnh của một tam giác thì

$$\left| \frac{x}{y} + \frac{y}{z} + \frac{z}{x} \right| - \frac{y}{x} - \frac{z}{y} - \frac{x}{z} < 1.$$

Thật thuận tiện để phân tích vế trái:

$$B = \left| \frac{x}{y} + \frac{y}{z} + \frac{z}{x} \right| = \frac{\left| z \left( x^2 - y^2 \right) + x \left( y^2 - z^2 \right) \right|}{xyz} = \frac{\left| (y-z) \left( z-x \right) \left( x-y \right) \right|}{xyz}.$$

$B < 1$ vì $|y-z| < x$, $|z-x| < y$ và $|x-y| < z$.

Bạn không thể giảm điểm 1: ví dụ với $x = \varepsilon$, $y = 1 + \varepsilon^2$, $z = 1 + \varepsilon$ ($\varepsilon$ là số dương nhỏ) $B$ sẽ lớn hơn $(1-\varepsilon)^3$.

V. Người gửi

M560. Có một lỗ ở đáy hộp. Cần phải tạo một nắp lồi có diện tích nhỏ nhất, ở bất kỳ vị trí nào mà lỗ ở đáy hộp sẽ được đóng lại. Giải quyết bài toán này nếu:

a) đáy hộp là hình vuông $4 \times 4$, và có lỗ như Hình 1.

b) đáy hộp là hình vuông $n \times n$ ($n$ là số lẻ) và lỗ nằm ở giữa (Hình 2).

Hình 1.

Hình 2.

Hình 3.

14 ở dạng hình bát giác lồi, bao gồm các hình vuông và hình tam giác trên (được đánh dấu ở Hình 3), luôn bao phủ hình vuông $A_1$. Vì vậy, nó là một ngoại lệ.

6) Giả sử rằng chúng ta có một màn trập lồi, ở bất kỳ vị trí nào ở dưới cùng của hộp $n \times n$ lỗ $A$ được đóng hoàn toàn.

Hãy xem xét hình chữ nhật nhỏ nhất $P$ có các cạnh song song với các cạnh của hình vuông, chứa cửa chớp của chúng ta. Đặt kích thước của nó là $(n-x) \times (n-y)$. Song song với việc di chuyển $P$ cùng với nắp, có thể dễ dàng đảm bảo rằng tất cả các hình chữ nhật thu được bằng cách di chuyển ô $A$ đến khoảng cách không quá $x$ trái-phải và $y$ từ trên xuống phải được nắp che; Độ dài các cạnh của hình chữ nhật này là $u = 1+x$, $v = 1+y$. Ngoài ra, mỗi bên của $P$ phải có điểm flapper; do đó, bộ giảm chấn phải bao gồm ít nhất bốn hình tam giác nữa (Hình 4) với tổng diện tích là $(n-u-x)v/2 + (n-v-y)u/2$. Vậy diện tích giảm chấn cũng không kém

$$uv + (n-u-x)v/2 + (n-v-y)u/2 = (n-x)(1+y)/2 + (n-y)(1+x)/2 = n + x(n-y-1)/2 + y(n-x-1)/2 \geq n.$$

(rõ ràng là $x$ và $y$ thậm chí không vượt quá $(n-1)/2$).

Hình 5 hiển thị hình $M$, luôn bao phủ hình vuông trung tâm $A$. Diện tích của nó rõ ràng là

⟦folio 31⟧

Hình 5.

M561. Hai hình tam giác $A_0B_0C_0$ và $A_1B_1C_1$, có diện tích là $S_0$ và $S_1$, được sắp xếp sao cho các tia $A_0B_0$ và $A_1B_1$, $B_0C_0$ và $B_1C_1$, $C_0A_0$ và $C_1A_1$ song song nhưng ngược chiều nhau. Tìm diện tích tam giác có các đỉnh tại trung điểm của các đoạn $A_0A_1$, $B_0B_1$, $C_0C_1$.

Hình 1.

Hình 2.

Hình 3.

bằng $n$, nghĩa là mức tối thiểu có thể. Vì vậy, đây là rào cản mong muốn.

Lưu ý rằng trong lời giải người ta không sử dụng cạnh của hình vuông $n$ là số nguyên, chỉ có $n > 1$ là quan trọng.

Sẽ rất thú vị khi giải bài toán này cho các cặp hình khác; ví dụ, khá hợp lý khi nếu “lỗ” và “đáy hộp” là các đường tròn đồng tâm có bán kính $r$ và $R$, thì rào chắn lồi của diện tích nhỏ nhất là hình lồi nhỏ nhất chứa hình tròn nhỏ hơn và đường kính của hình tròn lớn hơn (có diện tích là $2r\sqrt{R_2-r^2}+2r^2\arcsin r/R$).

V. Batyrev

◆ Đáp số. Khu vực bắt buộc

$$S = \left( \frac{\sqrt{S_0}-\sqrt{S_1}}{2} \right)^2.$$ (1)

Từ điều kiện bài toán suy ra các tam giác $A_0B_0C_0$ và $A_1B_1C_1$ đã được chuẩn bị (Hình 1), và hệ số chuẩn bị là âm và bằng mô đun

$$k = \frac{|A_1B_1|}{|A_0B_0|} = \frac{|B_1C_1|}{|B_0C_0|} = \frac{|C_1A_1|}{|C_0A_0|} = \frac{\sqrt{S_1}}{\sqrt{S_0}}.$$

Hãy để $O$ là trung tâm của sự sẵn sàng này, tức là

$$\overrightarrow{OA}_1 = -k\overrightarrow{OA}_0, \overrightarrow{OB}_1 = -k\overrightarrow{OB}_0, \overrightarrow{OC}_1 = -k\overrightarrow{OC}_0.$$

Khi đó, nếu $A, B, C$ lần lượt là trung điểm của các đoạn $A_0A_1$, $B_0B_1$, $C_0C_1$ thì

$$\overrightarrow{OA} = (\overrightarrow{OA}_0 + \overrightarrow{OA}_1)/2 = \overrightarrow{OA}_0(1-k)/2$$

và tương tự

$$\overrightarrow{OB} = \overrightarrow{OB}_0(1-k)/2, \quad \overrightarrow{OC} = \overrightarrow{OC}_0(1-k)/2.$$

Do đó, tam giác $ABC$ được khớp với tam giác $A_0B_0C_0$ và hệ số modulo bằng $\frac{|1-k|}{2}$; Đó là lý do tại sao

$$\frac{\sqrt{S}}{\sqrt{S_0}} = \frac{|1-k|}{2} = \frac{|1-\sqrt{\frac{S_1}{S_0}}|}{2} = \frac{\sqrt{S_0}-\sqrt{S_1}}{2\sqrt{S_0}}.$$

Từ đó suy ra công thức (1).

Lưu ý $1^\circ$. Hình tam giác $A_0B_0C_0$ và $A_1B_1C_1$ có ​​thể nằm trong các mặt phẳng song song; mặt phẳng của tam giác $ABC$ cũng sẽ song song với chúng. Tất cả các giải thích trên và đáp số (1) vẫn có hiệu lực.

$2^\circ$. lời giải của chúng tôi có liên quan chặt chẽ với một thực tế hữu ích như vậy: đoạn $AB$, nối trung điểm của các đường chéo $A_0A_1$ và $B_0B_1$ của hình thang với các đáy $A_0B_0$ và $A_1B_1$, song song với các đáy và có chiều dài bằng nửa hiệu độ dài của chúng (Hình 2).

$3^\circ$. Đặt các điểm $A_t, B_t, C_t$ chia các đoạn $A_0A_1$, $B_0B_1$, $C_0C_1$ theo cùng một tỷ lệ đã cho; hãy để, ví dụ,

$$\frac{\overrightarrow{A_0A_t}}{\overrightarrow{A_0A_1}} = \frac{\overrightarrow{B_0B_t}}{\overrightarrow{B_0B_1}} = \frac{\overrightarrow{C_0C_t}}{\overrightarrow{C_0C_1}} = t.$$

Khi đó diện tích $S_t$ của tam giác $A_tB_tC_t$ sẽ được biểu thị bằng công thức (1) (tương ứng với tia $t = 1/2$). Hãy nghĩ về điều gì xảy ra với $t = \frac{\sqrt{S_0}}{\sqrt{S_0}+\sqrt{S_1}}$.

$4^\circ$. Việc dữ liệu bài toán là hình tam giác là không đáng kể; hình tam giác có thể được thay thế

⟦folio 32⟧

Hình 4.

F568. Khi mục tiêu phía trước bị bắn phá bằng proton có năng lượng ít nhất 1,88 MeV, phản ứng hạt nhân có thể xảy ra

$$7\text{Li} + p \rightarrow 7\text{Be} + n.$$

Với năng lượng bao nhiêu của proton tạo ra trong phản ứng, neutron có thể bay lùi khỏi mục tiêu phía trước?

chúng ta là những nhân vật khác, được tạo sẵn so với một trung tâm nào đó $O$. Chính xác hơn: cho điểm $O$ và điểm $A_0$ mô tả một số đường cong khép kín không tự cắt bao quanh hình có diện tích $S_0$ (xem Hình 3).

Đồng thời, điểm $A_1$, được xác định bởi vectơ $\overrightarrow{OA}_1 = -k \cdot \overrightarrow{OA}_0$, $k = \sqrt{S_1/S_0}$, mô tả một đường cong khác (bao gồm hình diện tích $S_1$). Khi đó, trung điểm $A$ của đoạn $A_0A_1$ sẽ mô tả một đường cong bao quanh hình diện tích (1). Tương tự, điểm $A_t$ sao cho $\overrightarrow{A_0A_t} = t\overrightarrow{A_0A_1}$ (tức là $\overrightarrow{OA_t} = t\overrightarrow{OA_0} + (1-t)\overrightarrow{OA_1} = (t-k+kt)\overrightarrow{OA_0}$; $t$ là một số cố định) sẽ mô tả một đường cong bao quanh một hình có diện tích được xác định theo công thức (2).

$$S_{KLMNPQ} = \left( \frac{\sqrt{S_0} + \sqrt{S_1}}{2} \right)^2.$$

(xem công thức (1))*).

L. Kuptsov

Theo định luật bảo toàn năng lượng và động lượng

$$E_p = E_{\text{Be}} + E_n + Q,$$

(1)

$$\vec{p}_p = \vec{p}_{\text{Be}} + \vec{p}_n,$$

(2)

trong đó $E_p$, $E_{\text{Be}}$, $E_n$ lần lượt là năng lượng của proton, hạt nhân berili và neutron, $\vec{p}_p$, $\vec{p}_{\text{Be}}$, $\vec{p}_n$ là động lượng của các hạt này. Ở năng lượng proton $E_p = E_0 = 1,88$ MeV, tổng năng lượng $E$ của hạt nhân berili và neutron là tối thiểu. Hãy tìm cô ấy.

Để làm điều này, hãy xem xét quá trình trong hệ thống báo cáo, chuyển động với tốc độ của khối tâm của hệ proton - hạt nhân lithium. Trong hệ thống này, một proton và một hạt nhân lithium chuyển động hướng về nhau. Ở năng lượng tối thiểu có thể có của các hạt tương tác (hạt nhân proton và lithium), năng lượng của hạt nhân berili và neutron hình thành trong quá trình phản ứng bằng 0 - những hạt này ở trạng thái nghỉ.

Bây giờ chúng ta hãy chuyển sang hệ thống báo cáo trong đó mục tiêu lithium bất động. Trong hệ thống này, hạt nhân berili và neutron, được hình thành do sự bắn phá mục tiêu bằng một proton có năng lượng $E_p = E_0$, chuyển động như một hạt nhân với tốc độ bằng tốc độ khối tâm của hệ hạt nhân proton-lithium. Tổng năng lượng của chúng $E$, theo định luật bảo toàn năng lượng, được xác định bởi đẳng thức

$$E_0 = E + Q,$$

(1')

và tổng động lượng $\vec{p}$ của chúng, theo định luật bảo toàn động lượng, bằng

$$\vec{p} = \vec{p}_0$$

(2')

($\vec{p}_0$ là động lượng của một proton có năng lượng $E_0$). Xét rằng động lượng của một hạt và năng lượng của nó có liên hệ với nhau bởi hệ thức $p = |\vec{p}| = \sqrt{2mE}$ ($E = \frac{mv^2}{2} = \frac{(mv)^2}{2m} = \frac{p^2}{2m}$), chúng ta có thể viết lại đẳng thức (2') như sau:

$$\sqrt{2mE_0} = \sqrt{2(m+M)E}$$

(ở đây $m$ biểu thị khối lượng của proton và khối lượng neutron, $M$ khối lượng của lithium và khối lượng của hạt nhân berili). Từ đây xuất hiện $E = \frac{m}{m+M} E_0$. Thay thế giá trị này vào (1'), để

*) Lưu ý biên tập. Tôi nói về những công thức khái quát sâu rộng trong bài “Gia đình song song $n$-giác” («Kvant», 1974, số 11).

⟦folio 33⟧

đi giá trị $Q$:

$$Q = \frac{M}{m+M} E_0.$$

Như vậy, ở năng lượng proton $E_p > E_0$, chúng ta có thể viết định luật bảo toàn năng lượng (1) như sau:

$$E_p = E_{\text{Be}} + E_n + \frac{M}{m+M} E_0.$$

(3)

Nếu sự hình thành là kết quả của phản ứng, neutron bay trở lại từ mục tiêu đã ném thì định luật bảo toàn động lượng (2) có thể viết như sau:

$$p_p = p_{\text{Be}} - p_n (p = |\vec{p}|),$$

hoặc

$$\sqrt{2mE_p} = \sqrt{2ME_{\text{Be}}} - \sqrt{2mE_n}.$$

(4)

Từ đẳng thức (4) ta tìm được

$$E_{\text{Be}} = \frac{m}{M} (E_p + E_n + 2\sqrt{E_p E_n})$$

và thay thế giá trị này vào (3). Kết quả là chúng tôi nhận được

$$E_p = E_n + \frac{m}{M} (E_p + E_n + 2\sqrt{E_p E_n}) + \frac{M}{m+M} E_0.$$

Từ đẳng thức cuối cùng, rõ ràng $E_p$ là tối thiểu tại $E_n = 0$. Đồng thời

$$E_p = \frac{M^2}{M^2 - m^2} E_0 \approx 1,92 \text{ (МэВ)}.$$

Như vậy, ở $E_p \approx 1,92 \text{ МэВ}$ neutron sinh ra trong phản ứng sẽ kết thúc. Ở $E_p > 1,92 \text{ МэВ}$ neutron có thể bay lùi khỏi mục tiêu đã sử dụng.

I. Slobodetsky

◆ Hãy để chúng tôi biểu thị bằng $\tau_1$ thời gian làm nóng nước ($\tau_1 = 2$ phút). Từ định luật bảo toàn năng lượng suy ra rằng

$$W\tau_1 = cm (t_2 - t_1) + Q_1,$$

(*)

trong đó $m$ là khối lượng nước, $Q_1$ là tổn thất năng lượng liên quan đến quá trình truyền nhiệt trong không gian xung quanh. $Q_1$ tỉ lệ thuận với thời gian $t_1$ và sự chênh lệch nhiệt độ giữa nước và môi trường.

Khi còn nước (khi tắt hệ thống sưởi), năng lượng giải phóng ra không gian xung quanh bằng

$$Q_2 = cm \Delta t,$$

trong đó $\Delta t = 1^\circ\text{C}$ là sự thay đổi nhiệt độ nước theo thời gian $\tau_2 = 1$ phút. Vì chênh lệch nhiệt độ giữa nước và môi trường thay đổi một chút, nhưng $\tau_2 = 0,5\tau_1$, $Q_2 = 0,5Q_1$, nên

$$Q_1 = 2Q_2 = 2cm \Delta t.$$

Thay biểu thức này cho $Q_1$ vào đẳng thức (*), ta thu được

$$W\tau_1 = cm (t_2 - t_1 + 2\Delta t).$$

Từ đây

$$m = \frac{W\tau_1}{c(t_2 - t_1 + 2\Delta t)} \approx 1,8 \text{ кг}.$$

E. Surkov

◆ Hãy vẽ đồ thị sự phụ thuộc $\varphi(x)$. Biểu đồ cho thấy lúc đầu điện thế âm, sau đó bắt đầu tăng. Nó cực tiểu ở $x = 1$ mm, $\varphi_{\text{min}} = 1$ V. Điều này có nghĩa là lúc đầu (ở mức nhỏ $x$), trong khi điện thế giảm, điện trường khi một electron chuyển động sẽ thực hiện công âm và biến thành electron chuyển động. Ở $x > 1$ mm, khi điện thế bắt đầu tăng, trường

⟦folio 34⟧

Rakh, f - tính bằng vôn). Khoảng cách giữa cực âm và dị thường d = 10 mm. Tọa độ x trùng với khoảng cách đến cực âm. Xác định động năng tối thiểu mà một electron từ bề mặt Katoda có thể chạm tới cực dương. Gia tốc cực đại của electron khi đi tới anot là bao nhiêu?

$$W_{\min} = e\varphi_{\min} = 1 \text{ эВ.}$$

Gia tốc của electron được xác định bởi lực tác dụng lên electron, tức là cường độ trường. Do đó, gia tốc của electron đạt cực đại tại điểm mà tại đó điện áp cực đại là electron, hướng ngược lại với điện trường.

Vì $\Delta\varphi = E\Delta x$,

$$E = \frac{\Delta\varphi}{\Delta x} = \frac{(x + \Delta x)^2 - 2(x + \Delta x) - (x^2 - 2x)}{\Delta x} = \frac{2x\Delta x + (\Delta x)^2 - 2\Delta x}{\Delta x}.$$

Đối với $\Delta x$ nhỏ chúng ta có thể bỏ qua $\Delta x^2$, vì vậy

$$E(x) = 2x - 2 \quad (x - \text{в мм}, E - \text{в В/мм}).$$

Trường được hướng từ cực âm đến cực âm ở $x < 1$ mm và từ cực dương đến cực âm ở $x > 1$ mm. Vì điện tích của electron âm nên lực tác dụng lên electron có hướng ngược chiều với từ trường.

Vì vậy, điện áp là một trường tĩnh điện tỷ lệ với tọa độ. Nó đạt cực đại ở $x = d$ và bằng $E_{\max} = 18 \text{ В/мм}$. Do đó, tại $x = d$ gia tốc của electron là cực đại và bằng

$$a = \frac{F}{m} = \frac{eE}{m} \approx 3.2 \cdot 10^{15} \text{ м/c}^2.$$

♦

1) Chúng ta hãy lấy chiều dòng điện chạy qua các điện trở như trên Hình 1 và ký hiệu $U$ chiều giữa các điểm $A$ và $B$. Sau đó

$$U = -\mathcal{E}_1 + I_1R_1, \quad (1)$$

$$U = \mathcal{E}_2 + I_2R_2, \quad (2)$$

$$U = -\mathcal{E}_3 + I_3R_3, \quad (3)$$

$$U = \mathcal{E}_4 + I_4R_4. \quad (4)$$

Vì tổng dòng điện đến điểm $B$ bằng 0 (điện tích không tích lũy tại điểm $B$), nên

$$I_1 + I_2 + I_3 + I_4 = 0. \quad (5)$$

Từ hệ phương trình (1)–(5) không khó để tìm được điểm và hướng $U$. Để làm điều này, hãy thay thế vào phương trình (1)–(4) các giá trị đã biết của emf (tính bằng volt) và điện trở (tính bằng ohm):

$$U = -1 + I_1,$$

$$U = 2 + 2I_2,$$

$$U = -3 + 3I_3,$$

$$U = 4 + 4I_4,$$

$$I_1 + I_2 + I_3 + I_4 = 0.$$

Giải hệ này, ta tìm được

$$U + \frac{1}{2}U + \frac{1}{3}U + \frac{1}{4}U = 0 \Rightarrow U = 0.$$

Pozny

$$I_1 = 1\text{ А}; I_2 = -1\text{ А}; I_3 = 1\text{ А}; I_4 = -1\text{ А}.$$

(Dòng điện $I_2$ và $I_4$ ngược chiều với mũi tên.) Nếu cắt dây tại các điểm $A$ và $B$ thì

$$-\mathcal{E}_1 + I_1R_1 = \mathcal{E}_2 + I_2R_2,$$

$$I_1' + I_2' = 0,$$

Vì thế

$$I_1' = 1\text{ А}, I_2' = -1\text{ А};$$

⟦folio 35⟧

tương tự

$$\frac{\delta h_1}{\Delta h_2} = \left( \frac{r_2}{r_1} \right)^3$$

Vì lập phương của bán kính tỉ lệ với khối lượng của hạt nên

$$\frac{\Delta h_1}{\Delta h_2} = \frac{m_2}{m_1}$$

($m_1, m_2$ là khối lượng của các hạt gummigut có bán kính lần lượt là $r_1$ và $r_2$).

Sự thay đổi mật độ oxy trong khí quyển theo độ cao cũng tương tự như sự thay đổi số lượng hạt keo theo độ cao. Từ Hình 2 cho thấy mật độ oxy giảm khi độ cao thay đổi $\Delta H = 5,5$ km. Đó là lý do tại sao

$$\frac{\Delta h_1}{\Delta H} = \frac{m}{m_1},$$

trong đó $m$ là khối lượng của một phân tử oxy. Từ đây

$$m = m_1 \frac{\Delta h_1}{\Delta H} = \frac{4}{3} \pi r_1^3 q_r \frac{\Delta h_1}{\Delta H} \approx 5,8 \cdot 10^{-26} \text{ кг}.$$

I. Slobodetsky
