---
id: 1972-5-resheniya-387820c5
issue: kvant_1972_5
year: 1972
number: "5"
title: Lời giải bài toán M101—M105; F116—F122
rubric: zadachnik-kvanta
rubric_sub: Задачник «Кванта»
page_first: 29
page_last: 37
page_labels: 27, 28, 29, 30, 32, 33, 34, 35
tag: RV6C
lang: vi
source: kvant_digital
extraction: vision
content_sha256: c62cac174e6ed3a59e57d57c19374973f1b7dc8cd66b5c7012ba0722f64ac64b
prompt_sha256: draft-1
translated_from: content/ru/1972/05/articles/08_resheniya-387820c5.md
source_content_sha256: ad8b83304d95a4541af609e32f97a619d17450593a8bbf5d88f128a159393e8a
translation_model: draft
translation_run: vi-draft-2026-10-31
translation_quality: draft
---

⟦folio 27⟧

GIẢI PHÁP

Trong số này, chúng tôi xuất bản lời giải bài toán M101—M105.

M101

Một loại virus xâm nhập vào một khuẩn lạc gồm $n$ vi khuẩn. Trong phút đầu tiên, nó tiêu diệt một vi khuẩn, sau đó virus phân chia thành hai vi khuẩn mới, đồng thời mỗi vi khuẩn còn lại cũng phân chia thành hai vi khuẩn mới. Phút tiếp theo, hai loại vi-rút xuất hiện tiêu diệt hai vi khuẩn, sau đó cả vi-rút và tất cả các vi khuẩn khác lại phân chia, v.v.

Thuộc địa này dự kiến ​​​​sẽ tồn tại vô thời hạn hay cuối cùng nó sẽ bị diệt vong?

Dễ dàng kiểm tra được số lượng vi khuẩn, virus sẽ thay đổi theo thời gian theo quy luật sau:

| Thời gian (phút) | Số lượng virus | Số lượng vi khuẩn |
| :--- | :--- | :--- |
| 0 | 1 | $n$ |
| 1 | 2 | $2(n-1)$ |
| 2 | $2^2$ | $2^2(n-2)$ |
| 3 | $2^3$ | $2^3(n-3)$ |
| ... | ... | ... |
| $t$ | $2^t$ | $2^t(n-t)$ |
| $t+1$ | $2^{t+1}$ | $2^{t+1}(n-t-1)$ |
| ... | ... | ... |

Từ đây rõ ràng là ở $t=n$ số lượng vi khuẩn sẽ về 0 - khuẩn lạc sẽ chết.

Chúng tôi đã nhận được khoảng 80 lá thư có giải pháp cho bài toán này và một lá thư đưa ra đáp số không chính xác.

M102

Một tập hợp trên mặt phẳng bao gồm một số điểm hữu hạn có tính chất sau: với hai điểm bất kỳ $A$ và $B$ thì tồn tại một điểm $C$ được đặt sao cho tam giác $ABC$ là đều.

Một tập hợp như vậy có thể chứa bao nhiêu điểm?

Hãy chứng minh rằng một tập hợp như vậy chỉ có thể chứa ba điểm (tất nhiên giả sử nó chứa nhiều hơn một điểm).

Chúng ta hãy biểu thị tập hợp này bằng chữ cái $\Gamma$.

Cho $A$ và $B$ là hai điểm của tập hợp $\Gamma$, khoảng cách giữa chúng gọi là $d$, điểm $P$ phải nằm trong một đường tròn bán kính $d$ có tâm $A$. Theo cách tương tự, nó phải nằm bên trong các vòng tròn bán kính $d$ với tâm $B$ và $C$. Do đó, tập hợp $\Gamma$ không vượt ra ngoài phần chung của các vòng tròn này - “tam giác” đường cong $T$ (Hình 1).

Hơn nữa, cùng với các điểm $P$ và $A$, tập hợp $\Gamma$ phải thuộc một trong hai điểm $Q$ và $R$ - các đỉnh của tam giác đều $APQ$ và $APR$, tức là các điểm thu được từ $P$ bằng cách quay $60^\circ$ (trong hướng này hay hướng khác) xung quanh $A$ (Hình 2).

Để điểm $Q$ nằm bên trong $T$ thì điểm $P$ cần phải nằm trong ranh giới của “cánh hoa” vàng $AB$; Thật vậy, nếu bạn xoay hình tam giác $T$ quanh điểm $A$ bằng $60^\circ$ ngược chiều kim đồng hồ, thì thùy sẽ chỉ $AB$ và chỉ có điều chúng sẽ không vượt ra ngoài

⟦folio 28⟧

T. Tương tự như vậy, để điểm $R$ nằm bên trong $T$ thì điểm $P$ phải nằm trong “cánh hoa” màu xanh lam $AC$. Vì vậy, chúng ta đã chứng minh rằng mọi điểm $P$ tập $\Gamma$ đều phải nằm trong tập $T_A$, gồm hai cánh hoa màu xanh $AB$ và $AC$ có một đỉnh chung $A$. Nhưng theo cách tương tự, người ta chứng minh rằng $\Gamma$ nằm trong tập $T_B$ (Hình 3) và $T_C$ (Hình 4), và phần chung của ba tập hợp $T_A, T_B$ và $T_C$ chỉ bao gồm ba điểm $A, B$ và $C$. Do đó, không có điểm nào khác $P$ có thể thuộc tập $\Gamma$.

Đúng lời giải bài toán bổ sung A. Blyukhin (Klimovsk, vùng Kemerovo), N. Chernov (Krivoy Rog), Sh. Slepoy và E. Turkevichi (Chernivtsi), A. Merkuryev (Leningrad), M. Rozov (Minsk), A. Glushko và V. Korshenko (Voronezh) và những người khác.

Trong lời giải của chúng tôi, chúng tôi chỉ sử dụng thực tế là trong tập hợp $\Gamma$, chúng tôi có thể chỉ định hai điểm, khoảng cách giữa chúng là tối đa. Đối với tập $\Gamma$, bao gồm một số hữu hạn các điểm, điều này tất nhiên là đúng. Tuy nhiên, phát biểu bài toán vẫn đúng nếu chúng ta áp đặt điều kiện yếu hơn lên tập $\Gamma$—điều kiện bị chặn. Đối với lời giải bài toán cần phải cân nhắc bổ sung trong trường hợp này; chúng có thể được xác minh dễ dàng bởi những người biết các khái niệm ban đầu về cấu trúc liên kết của các tập hợp chính xác trên mặt phẳng, chẳng hạn như trong tập sách: N. Steenrod và W. Chinn “Những khái niệm đầu tiên về cấu trúc liên kết” (“Thế giới”, loạt bài nổi tiếng “Toán học hiện đại”). Lưu ý rằng điều kiện giới hạn không thể bị bỏ qua.

**M103**

Khám phá xem hệ thống điều khiển có bao nhiêu lời giải

$$\begin{cases} x^2 + y^2 + xy = a, \\ x^2 - y^2 = b, \end{cases}$$

trong đó $a$ và $b$ là một số số thực.

Hãy chuyển sang các biến mới bằng cách sử dụng các công thức

$$\begin{cases} x + y = u, \\ x - y = v, \end{cases}$$

đó là

$$\begin{cases} x = \frac{u + v}{2}, \\ y = \frac{u - v}{2}. \end{cases}$$

Sau đó, dữ liệu này trong điều kiện hệ thống sẽ được ghi như thế này:

$$\begin{cases} 3u^2 + v^2 = 4a, \\ uv = b. \end{cases}$$

Rõ ràng, theo công thức (1), mỗi nhạt $(x, y)$ tương ứng với một cặp $(u, v)$ và với mỗi nhạt $(u, v)$ có ​​một cặp $(x, y)$, vì vậy chúng ta cần tìm hiểu xem có bao nhiêu lời giải $(u, v)$ cho các giá trị khác nhau của tham số $a$ và hệ thống $b$ (2). (Rõ ràng ngay rằng đối với $a < 0$ không có lời giải, đối với $a = 0$ và $b \neq 0$ - cũng vậy, và đối với $a = b = 0$ chỉ có lời giải $u = v = 0$, nhưng điều này không thể được ghi nhận, vì lý luận sâu hơn của chúng tôi phù hợp cho những trường hợp này.

Chúng ta hãy trừ và cộng vào phương trình thứ nhất của hệ (2) phương trình thứ hai nhân với $2\sqrt{3}$.

Chúng tôi nhận được hệ thống sau:

$$\begin{cases} (\sqrt{3}u - v)^2 = 4a - 2\sqrt{3}b, \\ (\sqrt{3}u + v)^2 = 4a + 2\sqrt{3}b \end{cases}$$

hệ thống tương đương (2). [Hãy suy nghĩ về cách suy ra (2) từ (3)]. Rõ ràng là mỗi bộ giá trị $\sqrt{3}u - v$ và $\sqrt{3}u + v$ thu được từ (3) tương ứng với một hệ thống lời giải $(u, v)$. Cần phải tính đến rằng (trong miền số thực) phương trình $z^2 = c$ có hai lời giải: $z_1 = \sqrt{c}$, $z_2 = -\sqrt{c}$ nếu $c > 0$, một $z = 0$ nếu $c = 0$ và không có lời giải nếu $c < 0$.

Đáp số. Lời giải tồn tại khi và chỉ nếu các bất đẳng thức được thỏa mãn

$$-2a \leq b\sqrt{3} \leq 2a,$$

Trong Hình 1-4, các khu vực có màu xanh lam được giới hạn bởi hai vòng tròn khác có bán kính $d = AB$ có tâm tại các điểm $A, B$ hoặc $C$. Kiểm tra xem các khu vực này chỉ giao nhau tại các điểm $A, B$ và $C$.

⟦folio 29⟧

Cơm. 5. Bằng cách xoay $45^\circ$ theo chiều kim đồng hồ, hình này tạo ra Hình 6 (nhưng ở tỷ lệ khác).

Hơn nữa, nếu nó có cấu trúc bất đẳng thức (“ít hơn”) thì lời giải bốn; nếu một trong số chúng trở thành đẳng thức thì hai, nếu nó (điều này chỉ có thể thực hiện được nếu $a = b = 0$), thì có một điều.

Nhiều độc giả đã gửi lời giải tới bài toán này đưa ra kết quả này (thường ở dạng hơi khác một chút), cũng như các công thức rõ ràng cho hệ thống lời giải. Chúng không khó để có được từ các tính toán của chúng tôi, nhưng chúng khá cồng kềnh và chúng tôi sẽ không trình bày chúng, đặc biệt vì điều này không bắt buộc trong các điều kiện. Thay vào đó, chúng tôi hướng đến cách giải thích hình học của phương trình hệ thống: phương trình đầu tiên xác định một hình elip, phương trình thứ hai chỉ định một hyperbol. Hyperbola màu đỏ trong Hình 5 và 6 tương ứng với các giá trị của tham số $a$ và $b$ khi các đường cong giao nhau (bốn lời giải), màu xanh lam - khi hyperbola chạm vào hình elip (hai lời giải).

Một số độc giả cũng đã tiến hành nghiên cứu trường hợp hệ lời giải nằm trong miền số đầy đủ. Và ở đây lý luận của chúng ta cho phép chúng ta đưa ra ngay đáp số: trong các số đầy đủ $(x, y)$ hệ thống có bốn, hai hoặc một lời giải, nếu trong hai đẳng thức $2a = b\sqrt{3}$, $2a = -b\sqrt{3}$, tương ứng, bằng 0, một hoặc hai là đúng.

M104

Bên trong tam giác $ABC$ có hai điểm $P$ và $Q$ sao cho các đoạn $AP$ và $AQ$ tạo thành các góc bằng nhau với phân giác của góc $A$ của tam giác, các đoạn $BP$ và $BQ$ tạo thành các góc bằng nhau với phân giác của góc $B$.

Chứng minh rằng các đoạn $CP$ và $CQ$ tạo thành các góc bằng nhau với phân giác của góc $C$ (Hình 7).

⟦folio 30⟧

CHÚNG TÔI SẼ NHẬN ĐƯỢC

$$\sin(C - \gamma_1) \sin\gamma_2 = \sin(C - \gamma_2) \sin\gamma_1$$ hoặc
$$\sin C \sin(\gamma_1 - \gamma_2) = 0.$$

Vì $0 < C < \pi$ và $-\pi < \gamma_1 - \gamma_2 < \pi$, nên nó dẫn đến $\gamma_1 = \gamma_2$.

V.N. Berezin (Moscow) đã báo cáo một lời giải thuần túy hình học khác.

Cho $P_A, P_B$ và $P_C$ là các điểm đối xứng với các điểm $P$ đối với các cạnh $BC$, $AC$ $AB$ của tam giác $ABC$. Lưu ý rằng để đoạn $AQ$ tạo các góc bằng $\Rightarrow PAC = \alpha$ và $\Rightarrow PAB = A - \alpha$ với các đoạn $AB$ và $AC$ thì điều cần và đủ là nó tuân theo bissertice của góc $P_BAP_C$ (Hình 8).

Vì $AP_B = AP_C$, điều kiện này cũng có thể được phát biểu như sau: điểm $Q$ phải nằm trên đường vuông góc vẽ qua giữa đoạn $P_BP_C$. Bây giờ còn phải chứng minh rằng nếu $Q$ nằm trên đường vuông góc kẻ qua trung điểm của các đoạn $P_BP_C$ và $P_CP_A$ thì $Q$ cũng nằm trên đường vuông góc kẻ qua trung điểm của đoạn $P_BP_C$. Điều này là hiển nhiên: các điểm $P_A, P_B, P_C$ không nằm trên cùng một đường thẳng và $Q$ là tâm của đường tròn ngoại tiếp tam giác $P_AP_BP_C$ (Hình 9).

Tất nhiên, có thể chứng minh theo cách tương tự rằng $P$ là tâm của đường tròn ngoại tiếp tam giác $Q_AQ_BQ_C$, trong đó $Q_A, Q_B, Q_C$ là các điểm đối xứng với $Q$ đối với cạnh của tam giác $BC, CA, AB$. Ánh xạ $P \rightarrow Q$ giống như nghịch đảo của nó. Với ánh xạ này, tâm của đường tròn nội tiếp sẽ đi vào chính nó, tâm của đường tròn nội tiếp và giao điểm của các đường cao sẽ đi vào nhau (hãy kiểm tra xem!).

**M105**

Tổng các chữ số của một số sau khi nhân với 8 có thể giảm: $75 \cdot 8 = 600$ - tổng các chữ số là $7 + 5 = 12$, nhưng trở thành 6. Tuy nhiên, nó không thể giảm quá 8 lần. Chứng minh điều đó.

Nói cách khác, chứng minh rằng với mọi số tự nhiên $N$

$$\frac{S(8N)}{S(N)} \geq \frac{1}{8},$$

trong đó $S(A)$ là tổng các chữ số của số $A$ (theo ký hiệu thập phân).

Với những số tự nhiên nào khác $k$ có số dương $c_k$ sao cho mọi số tự nhiên $N$

$$\frac{S(kN)}{S(N)} \geq c_k?$$

Tìm giá trị tốt nhất cho $c_k$.

Đầu tiên lưu ý rằng $S(8 \cdot 125) = S(1000) = 1$.

Chúng ta sẽ cần các thuộc tính sau của hàm $S(N)$:

1. $S(A + B) \leq S(A) + S(B)$;
2. $S(A_1 + A_2 + \dots + A_n) \leq S(A_1) + S(A_2) + \dots + S(A_n)$;
3. $S(nA) \leq nS(A)$;
4. $S(AB) \leq S(A)S(B)$.

Để bị thuyết phục về tính hợp lệ của phần $1^\circ$ của bạn, chỉ cần tưởng tượng rằng các số $A$ và $B$ cộng lại thành một “cột”. Thuộc tính $2^\circ$ thu được từ $1^\circ$ bằng quy nạp đơn giản. $3^\circ$ là một sluagh riêng tư $2^\circ$.

Nếu bạn tưởng tượng rằng $A$ có thể được đặt trên $B$ trong một “cột” và áp dụng $3^\circ$ cho mỗi chữ số của số $B$, bạn sẽ nhận được $4^\circ$.

Bây giờ dễ dàng chứng minh được bất đẳng thức cần tìm: $S(N) = S(1000N) = S(125 \cdot 8N) \leq S(125)S(8N) = 8S(8N)$, tức là

$$\frac{S(8N)}{S(N)} \geq \frac{1}{8}.$$

Cách lập luận tương tự cũng áp dụng cho mọi số $k = 2^{2^q}5^q$. Hãy để chúng tôi biểu thị bằng $c_k$ số $\frac{1}{S(2^q5^r)}$. Hãy chứng minh rằng với mọi $N$ $\frac{S(kN)}{S(N)} \geq c_k$ (với $N = 2^{2^q}5^r$ bất đẳng thức này trở thành đẳng thức, vì

⟦folio none⟧

$$S(kN) = S(10^{r+q}) = 1$$. Đối với bất kỳ $N$
$$S(N) = S(10^{r+q}N) \leq S(2^q 5^r) S(kN) = \frac{1}{c_k} S(kN),$$
Q.E.D.

Bây giờ chúng ta hãy chứng minh rằng đối với các số $k$ có dạng $Q2^r 5^q$, trong đó $Q$ là nguyên tố cùng nhau với 10, thì tỷ lệ $S(KN)/S(N)$ có thể nhỏ hơn bất kỳ $\varepsilon > 0$ nào đã cho, tức là số dương cần thiết $c_k$ không tồn tại.

Chúng ta cần bổ đề sau: có một số $10^m-1$ (gồm $m$ số chín), được thực hiện trên $Q$. Dễ dàng chứng minh bằng cách sử dụng “nguyên nhân Dirichlet” *). Xét số dư khi chia cho $Q$ số

$$\begin{array}{c}
9 \\
99 \\
999 \\
9999 \\
\cdots
\end{array}$$

Một số hai trong số chúng trùng nhau và hiệu của các số tương ứng được chia cho $Q$:

*) Xem bài viết của A. I. Orlov trong «Kvant» Số 7, 1971.

Trong số này, chúng tôi xuất bản lời giải bài toán F116—F122.

F116

Nếu nhiệt độ của không khí trong xi lanh như trong Hình 10 là $T_0(T_0 > 0^\circ C)$ thì nó sẽ duy trì ở nhiệt độ $\frac{T_0}{2}$ trong khoảng $\tau = 30$ giây. Piston bắt đầu chuyển động ra vào với tần số nào đó. Trong trường hợp nào thì lượng băng hình thành xung quanh xi lanh nhiều hơn sau 50 hành trình piston, nếu chúng được tạo ra: a) trong 1 phút; b) trong 1 giờ; c) trong 30 ngày?

Tốc độ thay đổi nhiệt độ không khí trong xi lanh tỷ lệ thuận với nhiệt độ của chính nó. Điều này có nghĩa là nhiệt độ thay đổi theo cấp số nhân $T = T_0 e^{-\alpha t}$ ($\alpha$ là hệ số, $t$ là thời gian) (xem «Kvant» số 1).

Rõ ràng, nếu các khoảng thời gian đã chọn $t$ tạo thành một cấp số cộng có hiệu $\tau$, tức là $t=n\tau$, thì nhiệt độ khí tạo thành một cấp số nhân có giá trị $e^{-\alpha t}$. Điều này có thể dễ dàng kiểm chứng bằng cách viết công thức tính sự phụ thuộc của nhiệt độ khí vào thời gian dưới dạng

$$\frac{T}{T_0} = \left(e^{-\alpha t}\right)^n.$$

Tại $n=1$ $\frac{T}{T_0} = \frac{1}{2}$. Điều này có nghĩa là $e^{-\alpha t} = \frac{1}{2}$ và $\frac{T}{T_0} = \left(\frac{1}{2}\right)^n$.

Theo đó, trong một bình có pít-tông đứng yên, nhiệt độ của khí sẽ giảm một nửa sau mỗi 30 giây.

Nếu một piston thực hiện 50 hành trình trong 1 phút thì một hành trình được thực hiện trong 1,2 giây. Thời gian này ngắn so với thời gian đặc trưng của quá trình truyền nhiệt - 30 giây. Do đó, nhiệt lượng toả ra khi thể tích khí giảm không có thời gian tiêu tán và sẽ gần như bị mất đi khi thể tích tăng.

⟦folio 32⟧

Cơm. 11.

ma khí. Do đó, trong trường hợp này, chuyển động của piston sẽ không làm thay đổi tốc độ tan băng.

Cũng rõ ràng rằng ngay cả với 50 hành trình của pít-tông, trong 30 ngày, băng sẽ tan chảy theo cách tương tự như khi nó tan chảy khi một pít-tông đứng yên. Bây giờ thời gian thực hiện một hành trình của piston là quá dài so với thời gian mà gần như toàn bộ băng sẽ tan chảy và nhiệt độ nước sẽ bằng 0 ° C.

Nếu piston thực hiện 50 hành trình trong 1 giờ thì một hành trình được thực hiện trong 1,2 phút. Nhờ đó, vật được giải phóng trong quá trình khí sụp đổ sẽ có thời gian làm tan băng. Trong trường hợp này, lượng băng sẽ tan chảy nhiều hơn so với khi piston đứng yên.

lời giải chính xác cho bài toán này được gửi bởi M. Flerov (Moscow) và M. Weinhacher (Krivoy Por).

F117

Họ thường đi bộ dọc theo con đường đã được khảo sát, bước những bước nhỏ. Một người nên đi bộ bao nhiêu bước mà không sợ bị ngã nếu chiều dài chân của người đó là 1 mét và hệ số ma sát của đế giày trên đường là 0,1?

Đặt chiều rộng bước là 2x (Hình 11). Khi một người nhấc một chân lên, toàn bộ trọng lượng của người đó sẽ dồn vào chân kia. Khi đó phản lực của trái đất N bằng mg (m là khối lượng của một người). Điều này có nghĩa là lực ma sát cực đại F_TP có thể tác dụng lên chân một người mà không làm nó trượt bằng kmg. Hợp lực N và lực ma sát F_TP hướng vào trọng tâm của người, nghĩa là gần như dọc theo chân và tạo thành một góc α với phương thẳng đứng:

$$\frac{F_{ТР}}{N} = \text{tg} \alpha.$$

Posetom

$$\text{tg} \alpha = \frac{kmg}{mg} = k,$$

Nhưng

$$\sin \alpha = \frac{x}{l}.$$

Kể từ đây,

$$x = l \sin \alpha = l \frac{\text{tg} \alpha}{\sqrt{1 + \text{tg}^2 \alpha}} \approx 0, 1 l = 10 \text{ cm}).$$

Chiều rộng của bậc thang mà người đi bộ có thể bước là 20 cm.

bài toán này hóa ra là dễ nhất. lời giải đúng của cô đã được hơn 50 độc giả gửi.

F118

Buồng đốt của động cơ phản lực nhận được khối lượng m hydro mỗi giây và lượng oxy cần thiết để đốt cháy hoàn toàn. Đầu ra lời giải vòi phun S. Áp suất tại phần này P, nhiệt độ tuyệt đối T. Xác định lực đẩy động cơ F.

Hãy tìm khối lượng hơi nước tạo thành khối lượng m của hydro trong quá trình đốt cháy. Hãy viết phương trình phản ứng đốt cháy hydro

$$2\text{H}_2 + \text{O}_2 = 2\text{H}_2\text{O}.$$

Từ phương trình phản ứng, chúng ta có thể kết luận rằng hai phân tử hydro kết hợp với một phân tử oxy. Kết quả là hai phân tử hơi nước. Điều này có nghĩa là quá trình đốt cháy một oxy của hydro cần một nửa oxy của oxy và phản ứng tạo ra một oxy của nước. Khi đốt cháy n = \frac{m}{\mu_B} hydro oxy, sẽ thu được cùng một lượng hydro oxy (μ_B = 2 kE/kmol - khối lượng của một hydro oxy). Do đó, khi đốt cháy một khối lượng m hydro thì khối lượng thu được là M = \frac{m}{\mu_B} \mu_\pi = \frac{18}{2} m = 9 m hơi nước (μ_\pi = 18 kE/kmol - khối lượng của một hơi oxy). Khối hơi nước này bay ra khỏi vòi phun động cơ trong một giây. Vì biết diện tích vòi phun ra của động cơ nên ta có thể tìm được vận tốc v của khí ra khỏi vòi phun. Trong một giây, một lượng hơi nước V = vS sẽ thoát ra khỏi vòi phun động cơ. Nếu mật độ hơi bằng p thì khối lượng của thể tích hơi này sẽ bằng vSр, do đó M = ρSv.

Do đó v = \frac{M}{\rho S} = \frac{9m}{\rho S}.

Công thức này bao gồm mật độ hơi. Chúng tôi không biết điều đó, nhưng chúng tôi biết áp suất hơi nước và nhiệt độ của nó. Viết phương trình Clapeyron–Mendeleev PV = \frac{m}{\mu_\pi} RT (R là hằng số khí), chúng ta thấy rằng mật độ hơi bằng

$$\rho = \frac{m}{V} = \frac{P \mu_\pi}{RT} \text{ и } v = \frac{9mRT}{P \mu_\pi S}.$$

Vì trong thời gian Δt, khối lượng hơi MΔt được đẩy ra khỏi vòi, nơi truyền xung lực MΔtv, nên khí bị tác động lên.

⟦folio 33⟧

$$F_1 = \frac{M \Delta t v}{\Delta t} = M v.$$

Một lực có cùng độ lớn nhưng ngược chiều tác dụng lên động cơ. Tổng lực tác dụng lên động cơ (tức là lực đẩy của động cơ) bằng tổng phản lực $F_1$ và lực ép tĩnh $F_2 = p S$, tức là

$$F = M v + p S = 81 \frac{m^2 R T}{p \mu_\pi S} + p S = \frac{9}{2} \frac{m^2 R T}{p S} + p S.$$

Thông thường, vòi phun của động cơ phản lực được thiết kế sao cho áp suất $p$ của khí thoát ra khỏi vòi phun thấp. Do đó, số hạng thứ hai trong biểu thức lực đẩy của động cơ nhỏ so với số hạng thứ nhất và có thể bỏ qua trong tính toán.

Đúng lời giải gửi bởi: V. Kuusk (Rzhev); P. Sereev (Grozny), L. Smushekevich (Magnitogorsk), I. Sidorov (Moscow), S. Araslanova (N-Ivkino, vùng Kirov), D. Fushman (Chernovtsy), E. Dolgov (Moscow), Y. Imin (Rechnitsa, vùng Gomel), V. Katenov (Moscow), G. Simonenkov (Kauns), V. Belov (Vologda), N. Fedin (Omsk), M. Fedin (Alushta), V. Kulits (Ivanovo, vùng Brest), S. Chernikov (Semipalatinsk), V. Korotkikh (Novokuznetsk), O. Zaumyslova (Moscow), Yu. Polyansky (Zelenodolsk TASSR), A. Redchenko (làng Novopetrovka, huyện Belopolsky, vùng Sumy), S. Bozhevolny (stanitsa Kopanskaya, vùng Krasnoarsskaya), Y. Lurie (Grozny), E. Shakhnovich (vùng Kalinin), L. Bratsinsky (Frunze), Y. Shashkov (Shigri, vùng Kursk), A. Udaltsov (Kalinerrad, vùng Moscow), A. Gordienko (làng Poltavenskoye, vùng Krasnoarssk), V. Boyarishinov (Kolomna), A. Smirnov (Gorky), A. Mamula (làng Dybintsy, vùng Kyiv).

F119

Một tấm matnik $AB$ với một quả bóng có khối lượng $M$ được treo vào một tấm matnik $BC$ với một quả bóng có khối lượng $m$ (Hình 12). Điểm $A$ dao động theo phương nằm ngang với chu kỳ $T$. Tìm độ dài của sợi chỉ $BC$ nếu biết rằng sợi $AB$ luôn ở vị trí thẳng đứng.

Vì sợi dây $AB$ vẫn thẳng đứng nên không có lực ngang nào tác dụng lên quả bóng có khối lượng $M$ trong quá trình hệ chuyển động. Điều này có nghĩa là lực ngang không tác dụng lên hệ gồm hai quả bóng, $M$ và $m$, và các quả bóng phải chuyển động sao cho khối tâm của chúng không chuyển động theo hướng nằm ngang. Do đó, một quả bóng có khối lượng $m$ chuyển động như thể nó được gắn vào một sợi dây có chiều dài $x$, trong đó $x$ là khoảng cách từ quả bóng đến tâm khối lượng của hệ.

Cơm. 12.

Chúng tôi. Chu kỳ dao động của một matnik như vậy bằng $2\pi \sqrt{\frac{x}{g}}$. Khoảng thời gian này rất dài, bằng dao động của điểm $A$, tức là $T$:

$$T = 2\pi \sqrt{\frac{x}{g}}.$$

Bây giờ chúng ta hãy tìm $x$. Vị trí khối tâm của hệ thống định vị hoàn toàn giống với vị trí của trọng tâm:

$$xm = (l - x)M.$$

Từ đây

$$x = l \frac{M}{m + M}.$$

Thay biểu thức này cho $x$ vào công thức (1), chúng ta thu được

$$T = 2\pi \sqrt{\frac{l}{g} \cdot \frac{M}{m + M}}.$$

Từ đây

$$l = \frac{T^2 g}{4\pi^2} \cdot \frac{m + M}{M}.$$

Đúng lời giải bài toán đã gửi; L. Bratsinsky (Frunze), V. Korotkikh (Novokuznetsk), M. Premer (Tomsk), N. Fedin (Omsk), L. Smushekevich (Magnitogorsk), Y. Lurie (Grozny), P. Sereev (Grozny), E. Dolgov (Moscow).

F120

Một vận động viên trượt băng trên đường băng phải cố gắng quay càng gần mép trong càng tốt. Người đi xe đạp trên đường dành cho xe đạp rẽ càng xa mép trong càng tốt. Làm thế nào chúng ta có thể giải thích sự khác biệt này trong chuyển động của một vận động viên trượt băng và một vận động viên đua xe đạp khi rẽ? Cấu hình đường đi được hiển thị trong Hình 13.

Gia tốc hướng tâm được truyền cho vận động viên trượt băng bằng lực ma sát trên băng $F_{ТP} = kN$, trong đó $N$ là lực áp suất pháp tuyến của vận động viên trượt băng trên băng (Hình 14). Vì người trượt ván không di chuyển theo phương thẳng đứng

⟦folio 34⟧

hướng, lực $N$ có độ lớn bằng lực hấp dẫn $mg$ tác dụng lên người trượt băng. Do đó $F_{TP} = kmg$ và $\frac{mv^2}{R} = kmg$.

Do đó $v = \sqrt{kgR}$.

Khi rẽ, vận động viên trượt băng đi được quãng đường $\pi R$. Thời gian $t$ để rẽ là

$$t = \pi \sqrt{\frac{R}{kg}}.$$

(1)

Bán kính của vòng tròn mà vận động viên trượt băng di chuyển càng lớn thì thời gian quay càng lâu. Mặc dù việc tăng mức độ quay làm tăng tốc độ tối đa của vận động viên trượt băng, nhưng khoảng cách mà anh ta đi được thậm chí còn tăng hơn nữa. Tốc độ tỷ lệ thuận với $\sqrt{R}$ và khoảng cách tỷ lệ thuận với $R$. Đó là lý do tại sao vận động viên trượt băng cố gắng thực hiện lượt đi càng gần giờ nghỉ càng tốt.

Bây giờ hãy xem xét chuyển động của một người đi xe đạp trên đường nghiêng. Gia tốc hướng tâm được truyền cho nó bằng tổng các thành phần nằm ngang của lực ma sát $F_{TP}$ và lực $N$ của phản lực đỡ (Hình 15):

$$F_{TP} \cos \alpha + N \sin \alpha = \frac{mv^2}{R}.$$

(2)

Vì người đi xe đạp tóc không chuyển động theo hướng thẳng đứng nên tổng các thành phần thẳng đứng của tất cả các lực tác dụng lên người đi xe đạp tóc bằng 0:

$$N \cos \alpha - F \sin \alpha - mg = 0.$$

(3)

Từ phương trình (2) và (3), tính đến $F_{TP} = kN$, chúng ta tìm được tốc độ tối đa mà người đi xe đạp tóc có thể di chuyển:

$$v_1 = \sqrt{gR \frac{k + tg\alpha}{1 - ktg\alpha}}.$$

Tốc độ này không chỉ phụ thuộc vào bán kính của vòng tròn mà còn phụ thuộc vào góc nghiêng của đường ray với đường chân trời. Với biên dạng đường ray thể hiện trong hình, góc nghiêng sẽ thay đổi. Ở $\alpha = \arctg (1/k)$ tốc độ chuyển động của người đi xe đạp tóc có thể là bất kỳ *).

Thời gian cần thiết để một người đi xe đạp tóc đi qua một khúc cua có bán kính $R$ bằng

$$t_1 = \frac{\pi R}{v_1} = \pi \sqrt{\frac{R}{g} \cdot \frac{1 - ktg\alpha}{k + tg\alpha}}.$$

Nếu người đi xe đạp tóc rẽ xa hơn khỏi mép, thì không chỉ bán kính rẽ mà còn cả góc $\alpha$ của đường đua so với đường chân trời cũng thay đổi. Điều này làm giảm thời gian quay.

Các biên tập viên đã nhận được rất nhiều lời giải cho bài toán này. Nanmore đầy đủ và chứng minh lời giải được thêm bởi E. Dollov (Moscow), V. Belov (Vologda), S. Bozhevolny (stanitsa Kopanskaya, Lãnh thổ Krasnodar), A. German (Voronezh), A. Buzai (Izyaslav, vùng Khmelnitsky, Ukraina SSR), A. Boyavsky (Gomel), D. Fushman (Chernivtsi) và P. Sereev (Groznyy).

F121

Trong một bình kín, một khối băng có khối lượng $M$ nổi trong nước, trong đó có một viên chì có khối lượng $m$ nổi. Cần phải truyền nhiệt bao nhiêu để viên bắt đầu chìm? Mật độ của chì là $\rho_c = 11,3 \text{ e/cm}^3$, mật độ của băng là $\rho_\pi = 0,9 \text{ e/cm}^3$, nhiệt nóng chảy của băng là $\lambda = 80 \text{ кал/с}$. Nhiệt độ của nước trong bình là $0^\circ\text{C}$.

Không nhất thiết phải làm tan hết đá để hạt bắt đầu chìm xuống. Sẽ là đủ nếu mật độ trung bình của băng và hạt bằng với mật độ của nước. Nếu khối lượng băng còn lại ký hiệu là $M_1$ thì điều kiện để viên bắt đầu chìm sẽ được viết như sau:

$$\frac{M_1 + m}{V} = \rho_B.$$

Nhưng thể tích $V$ của nước đá và viên nhỏ bằng tổng thể tích của chúng, tức là $\frac{M_1}{\rho_\pi} + \frac{m}{\rho_c}$.

*) Tốc độ của người đi xe đạp tóc trong trường hợp này sẽ được xác định bởi sức mạnh, sự phát triển và lực cản.

⟦folio 35⟧

Pozny $M_1 + m = \rho_B \left( \frac{M_1}{\rho_\pi} + \frac{m}{\rho_c} \right)$.

Từ đây

$$M_1 = m \frac{(\rho_c - \rho_B) \rho_\pi}{(\rho_B - \rho_\pi) \rho_c} = 8,2m.$$

Khối lượng băng phải tăng lên

$$\Delta M = M - M_1 = M - 8,2m.$$

Điều này đòi hỏi một lượng nhiệt

$$Q = \lambda \Delta M = \lambda (M - 8,2m).$$

lời giải đúng của bài toán này với khoảng 40 độc giả.

F122

Ba vật có khối lượng $m_1, m_2$ và $m_3$ có thể trượt dọc theo mặt phẳng nằm ngang mà không ma sát (Hình 16), và $m_1 \gg m_2$ và $m_3 \gg m_2$. Xác định tốc độ tối đa mà hai vật thể bên ngoài có thể đạt được nếu tại thời điểm ban đầu chúng tích lũy và vật thể ở giữa có tốc độ $v$. Các tác động được coi là hoàn toàn đàn hồi.

Sự va chạm của một vật có khối lượng $m_2$ với các vật có khối lượng $m_1$ và $m_3$ sẽ tiếp tục cho đến khi tốc độ của nó nhỏ hơn tốc độ của một trong các vật $m_1$ hoặc $m_3$. Nhưng trong trường hợp này, động lượng và năng lượng của một vật có khối lượng $m_2$ sẽ nhỏ hơn nhiều so với động lượng và năng lượng của các vật thể này (vì $m_1 \gg m_2$ và $m_3 \gg m_2$) và, viết định luật bảo toàn năng lượng và động lượng, chúng ta không thể tính đến năng lượng và động lượng
