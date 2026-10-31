---
id: 1981-5-resheniya-zadach-m636-m640-f647-f655-9321fcf9
issue: kvant_1981_5
year: 1981
number: "5"
title: Lời giải bài toán M636—M640; F647—F655
rubric: zadachnik-kvanta
rubric_sub: Задачник «Кванта»
page_first: 24
page_last: 31
page_labels: 22-29
tag: 1EJ7
lang: vi
source: kvant_digital
extraction: vision
content_sha256: c888eb4f0a593756832b2cbb939b3c78ee593aba6b64ea38f76191f140c96862
prompt_sha256: draft-1
translated_from: content/ru/1981/05/articles/10_resheniya-zadach-m636-m640-f647-f655-9321fcf9.md
source_content_sha256: 98ab2b3b955ea1f492961b7a83e7d5bf9e7b2a90d4edf27eabe9c8f7c0c414a0
translation_model: draft
translation_run: vi-draft-2026-10-31
translation_quality: draft
---

⟦folio 22⟧

Một chùm ánh sáng đi vào lớp. Ở những giá trị nào của góc α (xem Hình 4), chùm tia sẽ quay trở lại môi trường chiết quang hơn? Tại giá trị nào của góc α₀ thì khoảng cách giữa điểm vào và điểm ra của chùm tia là lớn nhất?

P. Kalutsin, học sinh lớp 10. (Moscow, làng số 444)

Lời giải bài toán

M636—M640; F647—F655

Tập {1, 2, 3, 5, 10, 20, 25, 50, 100} thỏa mãn điều kiện bài toán. Điều này có nghĩa là tập hợp bắt buộc chứa không quá chín phần tử. Hãy sắp xếp các phần tử của nó theo thứ tự tăng dần:

$$1 = k_1 < k_2 < \dots < k_n = 100, n \leqslant 9.$$

Vì $k_j \leqslant 2 \cdot k_{j-1}$ ($j=2, 3, \dots, n$), với bất kỳ $j$ nào chúng ta có $k_j \leqslant 2^{j-1}$. Đặt $r$ là chỉ số lớn nhất sao cho $k_r \neq 2k_{r-1}$. Sau đó $100 = k_n = 2^{n-r} \cdot k_r \leqslant 2^{n-r}(k_{r-1} + k_{r-2}) \leqslant 2^{n-r} \cdot 2(2^{r-2} + 2^{r-3}) = 3 \cdot 2^{n-3}$. Từ bất đẳng thức 100 $\leqslant 3 \cdot 2^{n-3}$ suy ra $n \geqslant 9$. Vì vậy, $n=9$ và tập hợp {1, 2, 3, 5, 10, 20, 25, 50, 100} là có thể loại trừ.

Lưu ý rằng có các bộ chín phần tử khác thỏa mãn điều kiện bài toán. Ví dụ: tập {1, 2, 4, 6, 10, 20, 30, 50, 100} cũng phù hợp.

Yu. Nesterenko

M637. Cho tam giác đều ABC. Một đường thẳng song song với đường thẳng AC cắt các đường thẳng AB, BC lần lượt tại M và P. Điểm D là tâm tam giác PMB, điểm E là trung điểm đoạn AP. Tính các góc của tam giác DEC.

Hình 1.

Hình 2.

Hình 3.

Hình 4.

⟦folio 23⟧

Hình 5.
Hình 6.
MỘT)
B=M=P=D
x=0
b)
x=1
Hình 7.
x=1
Hình 8.

M638. Một số ô của một tờ giấy ca rô vô hạn được tô màu đỏ, các ô còn lại màu xanh lam, sao cho mỗi hình chữ nhật gồm 6 ô có kích thước 2x3 chứa đúng hai ô màu đỏ. Một hình chữ nhật gồm 99 ô có kích thước 9x11 có thể chứa bao nhiêu ô màu đỏ?

Độ chính xác $D$ và $D_1$ là tâm của các tam giác $MBP$ và $M_1BP_1$ lần lượt nằm trên đoạn $MP_1$ và chia nó thành ba phần bằng nhau. Do đó, $D_1E_1$ là đường giữa trong tam giác $DP_1C$, $|D_1E_1| = \frac{1}{2}|DC| = |DE|$ và $[D_1E_1] \parallel [DC]$. Nhưng $[D_1E_1]$ thu được từ $[DE]$ bằng cách xoay 60°; do đó $EDC = 60^\circ$. Phần còn lại là hiển nhiên.

Thứ ba lời giải (đại số, nhưng hầu như không có phép tính).

Gọi 1 là độ dài cạnh của tam giác $ABC$, $x$ độ dài cạnh của tam giác $MBP$ (Hình 6). Tại $x=0$ và $x=1$ (xem Hình 7)

$$|DC|^2 - |DE|^2 - |EC|^2 = 0.$$ (1)

Đẳng thức (1) có thể được xác minh dễ dàng cho $x = \frac{1}{2}$ (Hình 8). Tại thời điểm này, chúng ta cần tăng nó lên một chút: hãy vẽ $(DH) \parallel (AB)$ và $(DF) \parallel (AC)$. Chúng ta có $|DH| = \frac{1}{3}, |HE| = \frac{1}{12}, |EK| = \frac{1}{4}, |DF| = \frac{1}{6}$ và mỗi góc $DHE, EKC$ và $DFC$ là 120°. Theo định lý cosin trong tam giác $DHE, EKC$ và $DFC$

$$|DE|^2 = \frac{1}{9} + \frac{1}{144} + \frac{1}{36} = \frac{21}{144}, |EC|^2 = \frac{1}{16} + \frac{1}{4} + \frac{1}{8} = \frac{63}{144}, |DC|^2 = \frac{1}{36} + \frac{4}{9} + \frac{1}{9} = \frac{84}{144},$$

từ đó theo sau (1).

Vế trái của sự tương ứng (1) là một tam giác vuông từ $x$ (bình phương độ dài các cạnh có thể được biểu thị từ các tam giác tương ứng bằng định lý cosine). Do những điều trên, tam giác này tại ba điểm ($x=0, x=\frac{1}{2}$ và $x=1$) biến mất. Điều này có nghĩa là nó cũng bằng không.

Do đó, (1) thỏa mãn với mọi $x$, nghĩa là với mọi $x$ tam giác $DEC$ là hình chữ nhật: $DEC = 90^\circ$.

Tương tự, người ta có thể kiểm tra xem một hình vuông có phải là hình tam giác hay không.

$$|DE|^2 - \frac{1}{4} \cdot |DC|^2$$ (2)

tại ba điểm ($x=0; \frac{1}{2}, 1$) cũng có giá trị bằng 0 và do đó thực tế cũng bằng 0. Vì vậy, $|DE| = \frac{1}{2}|DC|$, tức là, $CDE = 60^\circ$.

Một cái khác, thứ tư, lời giải dựa trên quan sát sau: tam giác $DPC$ được lấy từ tam giác $DKE$ bởi một phân nhóm trung tâm như vậy: thành phần của một phép quay qua một góc 60° với tâm $D$ và chuẩn bị với hệ số 2. Hãy thử viết lời giải này sao cho phù hợp cho cả ba trường hợp cùng một lúc (xem Hình 1, 2, 3).

L. Kuptsov

◆

Đáp số. Bất kỳ hình chữ nhật $9 \times 11$ nào cũng chứa 33 ô màu đỏ.

Bằng chứng. Hãy xem xét một ô màu đỏ tùy ý $K_0$ và xem xét một hình vuông $3 \times 3$ có tâm ở ô đó. Các ô liền kề với $K_0$ theo chiều ngang hoặc chiều dọc không thể có màu đỏ: ví dụ như trong Hình 1, ô $K$ có màu đỏ, thì trong hình chữ nhật bên phải hoặc bên trái $2 \times 3$ sẽ không còn ô màu đỏ nữa, do đó hình chữ nhật như vậy sẽ chỉ có một ô màu đỏ ($K_0$) - mâu thuẫn với các điều kiện. Vì vậy, các ô liền kề với $K_0$ thuộc về tiêu đề.

Tiếp theo, trong hình chữ nhật bên phải phải có ít nhất một ô màu đỏ - ví dụ trống sẽ là ô $K_1$, như trong Hình 2. Xét hình chữ nhật trên cùng và bên trái

⟦folio 24⟧

Hình 1. Hình 2.

Hình 3.

Hình 4.

M639. Trong tứ diện ABCD (AC) ⊥ (BC) và (AD) ⊥ (BD). Chứng minh rằng cosin của góc giữa hai đường thẳng AC và BD nhỏ hơn |CD|/|AB|.

M640. Số $x \in [0; 1]$ được viết dưới dạng phân số thập phân vô hạn. Bằng cách sắp xếp lại 5 chữ số đầu tiên sau dấu thập phân theo bất kỳ thứ tự nào, chúng ta nhận được một phân số thập phân vô hạn mới tương ứng với một số $x_1$. Bằng cách sắp xếp lại ký hiệu thập phân của số $x_1$ từ chữ số thứ 2 đến thứ 6 sau dấu thập phân, ta thu được ký hiệu thập phân của số $x_2$. Tổng quát, hình vuông thứ mười $2 \times 3$, từ điều kiện bài toán ta suy ra rằng ở góc của hình vuông $3 \times 3$, đối diện với ô $K_1$, cũng phải có một ô màu đỏ - $K$, và các ô màu đỏ trong hình vuông này nằm theo đường chéo. Xem xét các hình vuông như vậy có tâm trong các ô $K_1$ và $K$ và di chuyển các hình vuông này dọc theo “đường chéo màu đỏ”, từ phép tính trên, chúng ta thu được rằng toàn bộ hàng chéo $KK_0K_1$ bao gồm các ô màu đỏ và hai hàng chéo bên trên và bên dưới màu đỏ được tạo thành từ các ô màu xanh lam, như trong Hình 3. Lập luận tương tự (xem Hình 3), chúng ta thấy rằng hai ô tiếp theo (trên cùng và dưới cùng) và vì hình chữ nhật $9 \times 11$ có thể chia thành 9 hình vuông $3 \times 3$ và 3 hình chữ nhật $2 \times 3$, ta kết luận rằng trong hình chữ nhật $9 \cdot 3 + 3 \cdot 2 = 33$ này có các ô màu đỏ.

Dễ dàng nhận thấy cách tô màu Hình 4 thỏa mãn điều kiện bài toán. Hơn nữa, mỗi hình vuông $3 \times 3$ chứa chính xác ba ô màu đỏ và vì hình chữ nhật $9 \times 11$ có ​​thể được chia thành 9 hình vuông $3 \times 3$ và 3 hình chữ nhật $2 \times 3$ nên chúng ta kết luận rằng trong hình chữ nhật $9 \cdot 3 + 3 \cdot 2 = 33$ này có các ô màu đỏ.

Trong phần giải cấu trúc ở trên, chúng tôi đã chứng minh được nhiều hơn mức yêu cầu của các điều kiện bài toán—trên thực tế, chúng tôi đã mô tả tất cả các cách tô màu có thể có.

Hầu hết độc giả đã hiểu đúng: hình chữ nhật $9 \times 11$ có thể dễ dàng chia thành 16 hình chữ nhật $2 \times 3$, sau đó dải $1 \times 3$ sẽ vẫn còn. Từ điều kiện dễ thấy rằng dải này chỉ có thể chứa một ô màu đỏ, do đó chỉ có $16 \cdot 2 + 1 = 33$ ô màu đỏ trong toàn bộ hình chữ nhật. Sau đó, chỉ cần đưa ra một ví dụ về cách tô màu thỏa mãn điều kiện bài toán là đủ.

Lưu ý rằng trong bài toán này, không cần thiết phải tô màu toàn bộ mặt phẳng một cách điên cuồng - chúng ta có thể giới hạn tô màu 99 ô của hình chữ nhật $9 \times 11$.

A. Zemlyakov

Hãy vẽ $(BE) \parallel (CA)$ và $(AE) \parallel (CB)$ (xem hình). Cosin của góc giữa hai đường thẳng AC và BD là $|\cos DBE|$.

Mặt khác, tứ giác $ACBE$ là hình chữ nhật nên $|AB| = |CE|$ và $|CD|/|AB| = |CD|/|CE|$.

Lưu ý rằng các đỉnh của góc vuông $ACB, ADB, AEB$ nằm trên một hình cầu có đường kính $AB$. Đoạn $CE$ cũng chính là đường kính của hình cầu này nên góc $CDE$ là đường thẳng và $|CD|/|CE| = \cos DCE$. Bất đẳng thức cần tìm bây giờ có dạng $|\cos DBE| < \cos DCE$.

Gọi $R$ là bán kính của hình cầu và $r$ là bán kính của hình tròn do tiết diện hình cầu với mặt phẳng $BDE$. Vì mặt phẳng này không đi qua tâm hình cầu nên $r < R$ và từ các đẳng thức $2r \cdot \sin DBE = |DE| = 2R \cdot \sin DCE$ chúng ta thu được $\sin DBE > \sin DCE$. Vì vậy, $|\cos DBE| < |\cos DCE| = \cos DCE$.

Yu. Nesterenko

M640. Số $x \in [0; 1]$ được viết dưới dạng phân số thập phân vô hạn. Bằng cách sắp xếp lại 5 chữ số đầu tiên sau dấu thập phân theo bất kỳ thứ tự nào, chúng ta nhận được một phân số thập phân vô hạn mới tương ứng với một số $x_1$. Bằng cách sắp xếp lại ký hiệu thập phân của số $x_1$ từ chữ số thứ 2 đến thứ 6 sau dấu thập phân, ta thu được ký hiệu thập phân của số $x_2$. Nói chung, hình vuông thứ mười $2 \times 3$, từ điều kiện bài toán, chúng ta suy ra rằng ở góc trong các phần của các chữ số có số $10^n < k < 10^n + 5$ cho tất cả các số tự nhiên $n$: cùng với 1010 ở những vị trí này chúng ta đặt 1100. Các hạt của các chữ số từ số -

⟦folio 25⟧

ký hiệu của số $x_{k+1}$ có được bằng cách sắp xếp lại các số trong ký hiệu $x_k$ từ $(k+1)$ đến $(k+5)$ sau dấu thập phân.
a) Chứng minh rằng dù các số trên mỗi số được sắp xếp lại như thế nào thì dãy số $x_k$ luôn có giới hạn nào đó.
Hãy để chúng tôi biểu thị giới hạn này bằng $y$.
b) Tìm hiểu xem có thể thu được số vô tỉ $y$ từ số hữu tỉ $x$ bằng cách sử dụng quy trình được mô tả hay không.
b) Nghĩ ra một phân số $x$ mà quá trình này luôn dẫn đến các số vô tỷ, bất kể hoán vị của các chữ số của số năm trên mỗi dòng là bao nhiêu.

C) Đặt $y$ phân số $x$ ở các vị trí có số $10^n < k \leq 10^n+5$ đối với mọi tự nhiên $n$ là đơn vị, các số còn lại là số 0. Hãy chứng minh rằng khi không chuyển động thì phân số $x$ trở thành tuần hoàn. Giả sử điều ngược lại: với một số chuyển động tuần tự của các chữ số của số năm, thu được phân số tuần hoàn $y$. Lưu ý rằng khi di chuyển, số của một chữ số đã cho (số 0 hoặc số đơn vị) không thể giảm nhiều hơn số chẵn. Trong số các số từ số đầu tiên đến số $(10^n+5)$ sau dấu thập phân chỉ có $5n$ đơn vị, và do đã thay thế trước đó nên số của chúng ở phần này không thể tăng lên. Nếu trong chu kì của phân số $y$ có $p$ chữ số và trong số đó có $q>0$ đơn vị, thì với $n$ đủ lớn trong phần chữ số có số $1 \leq k \leq 10^n$ sẽ có ít nhất $q \cdot \left[ \frac{10^n-N}{p} \right]$ đơn vị, trong đó $N$ là số chữ số $y$, mà tính tuần hoàn bắt đầu. Do đó, chúng ta thu được bất đẳng thức $q \cdot \left[ \frac{10^n-N}{p} \right] \leq 5n$, điều này không đúng khi đạt được $n$ lớn. Do đó, người ta không thể, bắt đầu từ một nơi nào đó, chỉ có số không.

Bây giờ chúng ta sẽ chỉ ra rằng đối với bất kỳ chuyển động nào của phân số $x$, bất kỳ số chia nào tính từ dấu thập phân, đơn vị đều phải được giữ nguyên. Trong số các chữ số của phân số $x$ từ dấu thập phân thứ nhất đến dấu thập phân thứ $(10^n+1)$ có ​​một số số 0. Vì các số 0 ở xa dấu thập phân có các số bắt đầu bằng $10^n+6$ nên sau khi di chuyển chúng không thể rơi vào vùng được chỉ định; số lượng số 0 trên đó sẽ không tăng và số lượng số 1 tương ứng với nó sẽ không giảm. Do đó, các chữ số có số $10^n+1 \leq k \leq 10^n+5$ đơn vị trong phân số $x$ không thể di chuyển tất cả chúng sang bên phải - ít nhất một đơn vị phải nằm trong vùng từ chữ số đầu tiên đến chữ số thứ $(10^n+1)$. Mặt khác, chúng cũng không thể dịch sang phải hơn đến vị trí thứ tư, do đó, với bất kỳ $n$ nào trong phần chữ số có số $10^n-3 \leq k \leq 10^n+1$ thì phân số $y$ sẽ còn lại một đơn vị. Rõ ràng, điều này mâu thuẫn với thực tế là chu kỳ của phân số chỉ bao gồm số 0.

A. Zemlyakov

F647. Một giọt mưa lớn khiến những đám mây bay không có gió ở độ cao lớn hơn. Tại thời điểm gia tốc rơi bằng 7,5 m/s2 thì tốc độ của nó là 20 m/s. Gần đó, một giọt nước rơi với tốc độ không đổi $u$, tự động đập vào kính bên, để lại vết trên đó một góc $30^\circ$ so với phương thẳng đứng. Thanh tra GAN có phạt người lái xe chạy quá tốc độ nếu tốc độ cho phép tự động là 60 km/h không? Coi lực cản của không khí tỉ lệ thuận với tốc độ rơi.

♦

Hãy viết định luật thứ hai của Newton khi gia tốc rơi là $a=7,5$ m/s² và tốc độ là $v_1=20$ m/s:

$$ma=mg-kv_1^2,$$

trong đó $kv_1^2$ là giá trị của lực cản tại thời điểm này.

Ở gần mặt đất, giọt nước chuyển động với tốc độ không đổi $v_2$, do đó:

$$mg=kv_2^2.$$

Vì vết do một giọt nước để lại trên kính tạo một góc $\alpha=30^\circ$ với phương thẳng đứng nên tốc độ rơi và tốc độ của vật tự động $v$ có liên hệ với nhau bởi hệ thức

$$v=v_2tg\alpha.$$

Từ phương trình (1) - (3) ta tìm được tốc độ tự động:

$$v=\frac{v_1tg\alpha}{\sqrt{1-a/g}} \approx 23,8\text{ м/c} \approx 85,7\text{ км/ч}.$$

Tiền phạt thêm vào ngọn lửa.

B. Belonukin

⟦folio 26⟧

F648. Cấu trúc bản lề bao gồm ba hình thoi, các cạnh có tỷ lệ 3:2:1 (Hình 1). Đỉnh $A_3$ di chuyển theo hướng ngang với tốc độ $v_0$. Xác định vận tốc của các đỉnh $A_1, A_2, B_1$ tại thời điểm mọi công trình đều thẳng.

Hình 1.

Hình 2.

F649. Trong xô có hỗn hợp nước và đá. Khối lượng của hỗn hợp là 10 kg. Chiếc xô được mang vào phòng và họ ngay lập tức bắt đầu thay đổi nhiệt độ của hỗn hợp. Đồ thị kết quả của sự phụ thuộc $t(\tau)$ được hiển thị trong hình. Nhiệt độ riêng của nước $c_B = 4200$ J/(kg K) và nhiệt độ của nước đá $\lambda = 3,4 \cdot 10^5$ J/kg đã được biết. Xác định xem có bao nhiêu đá trong xô khi nó được mang vào phòng. Bỏ qua nhiệt dung của thùng.

F650. Để thu được điện áp, giá trị của điện áp này phụ thuộc ít vào nhiệt độ, người ta lắp ráp một mạch điện theo Hình 1. Các đặc tính vôn kế của diode D ở ba nhiệt độ môi trường khác nhau $t_1 = 125^\circ C$, $t_2 = 25^\circ C$, $t_3 = -60^\circ C$ được đưa ra.

Từ điều kiện bài toán suy ra rằng trong quá trình chuyển động của cấu trúc giữa các độ dài $l_1, l_2, l_3$ của các đoạn $A_0A_1, A_0A_2, A_0A_3$ sự tương ứng được duy trì

$$l_1:l_2:l_3 = 3:5:6.$$

Do đó, vận tốc của các điểm $A_1, A_2, A_3$ tương ứng

$$|\vec{v}_{A1}|:|\vec{v}_{A2}|:|\vec{v}_{A3}| = 3:5:6,$$

và do đó

$$|\vec{v}_{A1}| = \frac{v_0}{2}, |\vec{v}_{A2}| = \frac{5v_0}{6}.$$

Bây giờ chúng ta hãy xem xét chuyển động của liên kết giữa ($A_1B_2A_2C_2$) tại thời điểm các góc của cấu trúc vuông góc. Trong hệ thống báo cáo chuyển động với tốc độ $\vec{v}_{A1}$, tại thời điểm này tốc độ $\vec{v}'_{B2}$ của điểm $B_2$ hướng dọc theo cạnh $B_2A_2$; tốc độ của điểm $A_2$ hướng theo phương ngang và bằng

$$|\vec{v}'_{A2}| = |\vec{v}_{A2} - \vec{v}_{A1}| = \frac{v_0}{3}.$$

Từ trạng thái không hoạt động của thanh $B_2A_2$ ta có (Hình 2, a):

$$|\vec{v}'_{B2}| = |\vec{v}'_{A2}| \sin 45^\circ = \frac{v_0 \sqrt{2}}{6}.$$

Chúng ta sẽ tìm tốc độ của điểm $B_2$ so với hệ thống báo cáo đứng yên bằng định lý cosine (Hình 2, b):

$$|\vec{v}_{B2}|^2 = |\vec{v}_{A1}|^2 + |\vec{v}'_{B2}|^2 + 2 \frac{\sqrt{2}}{2} |\vec{v}_{A1}| |\vec{v}'_{B2}| = \frac{17}{36} v_0^2,$$

$$|\vec{v}_{B2}| = \frac{v_0}{6} \sqrt{17}.$$

S. Krotov

◆

Như có thể thấy từ biểu đồ, trong 50 phút đầu tiên, nhiệt độ của hỗn hợp không thay đổi và duy trì ở mức 0°C. Tất cả thời gian này, nhiệt mà hỗn hợp nhận được từ phòng được sử dụng để làm đá. Sau 50 phút, toàn bộ băng tan và nhiệt độ nước bắt đầu tăng lên. Trong 10 phút (từ $\tau_1 = 50$ phút đến $\tau_2 = 60$ phút), nhiệt độ tăng thêm $\Delta t = 2^\circ C$. Nhiệt lượng cung cấp cho nước từ phòng trong thời gian này bằng $q = c_B M \Delta t = 8,4 \cdot 10^4$ J ($M = 10$ kg - khối lượng của nước). Điều này có nghĩa là trong 50 phút đầu tiên của hỗn hợp, lượng nhiệt $Q = 5q = 42 \cdot 10^5$ J tỏa ra từ phòng. Nhiệt lượng này được sử dụng để kéo khối lượng $m$ của băng: $Q = \lambda m$. Như vậy,

$$m = \frac{Q}{\lambda} \approx 1,23 \text{ кг}.$$

A. Buzdin

◆

Diode được mắc nối tiếp với nguồn bằng các điện trở có điện trở $R_{06\mu}$ = $5,2 \cdot 10^3$ Ohm. Do đó, tại bất kỳ thời điểm nào (ở bất kỳ nhiệt độ nào) dòng điện trong mạch đều bằng

$$I = \frac{U - U_0}{R_{06\mu}}.$$

trong đó $U, U_0$ là các giá trị điện áp tại nguồn và tại diode tại một thời điểm nhất định.

⟦folio 27⟧

Chúng ta hãy vẽ đồ thị sự phụ thuộc $I(U_\pi)$ trong Hình 2 cho ba nhiệt độ khác nhau:

$$t_1 = +125^\circ C - U_{125} = 8,5 \text{ B}, \quad I_{125} = \frac{8,5 - U_{\pi,125}}{5,2} \text{ мА};$$

$$t_2 = +25^\circ C - U_{25} = 6 \text{ B}, \quad I_{25} = \frac{6 - U_{\pi,25}}{5,2} \text{ мА};$$

$$t_3 = -60^\circ C - U_{-60} = 3,875 \text{ B}, \quad I_{-60} = \frac{3,875 - U_{\pi,-60}}{5,2} \text{ мА}.$$

Giao điểm của các đồ thị này với đặc tính dòng điện-điện áp của diode (đối với nhiệt độ tương ứng) xác định các giá trị điện áp trên diode và dòng điện trong mạch ở nhiệt độ nhất định. Từ Hình 2, chúng tôi tìm thấy (tất nhiên là gần đúng):

$$U_{\pi,125} = 0,77 \text{ B}, \quad I_{125} = 1,48 \text{ мА};$$

$$U_{\pi,25} = 0,8 \text{ B}, \quad I_{25} = 1 \text{ мА};$$

$$U_{\pi,-60} = 3,875 \text{ B}, \quad I_{-60} = 0,58 \text{ мА}.$$

Tương ứng giá trị điện áp $U_{AB} = U_\pi + I \cdot 0,2$ (V) giữa các cực $A$ và $B$ —

$$U_{AB,125} = 1,07 \text{ B};$$

$$U_{AB,25} = 1 \text{ B};$$

$$U_{AB,-60} = 0,94 \text{ B}.$$

Như vậy, hệ số nhiệt độ đặc trưng cho sự thay đổi tương đối (tương đối $U_{AB,25}$) của điện áp $U_{AB}$ khi nhiệt độ thay đổi từ $-60^\circ C$ thành $+125^\circ C$ bằng

$$\alpha = \frac{\Delta U_{AB}}{\Delta t \cdot U_{AB,25}} \approx 7 \cdot 10^{-4} \text{ град}^{-1}.$$

So với hệ số nhiệt độ ban đầu $\alpha_0 = \frac{25 \cdot 10^{-3}}{6} \approx 4 \cdot 10^{-3} \text{ град}^{-1}$, giá trị thu được $\alpha$ nhỏ hơn khoảng 6 lần.

Hãy suy nghĩ về cách thay đổi điện trở của các điện trở để bù gần như hoàn toàn sự mất ổn định nhiệt độ của nguồn.

A. Zilberman

F651. Một câu chuyện khoa học viễn tưởng mô tả một tình huống khẩn cấp trong đó một phi hành gia có khối lượng $M = 100$ kg thấy mình ở khoảng cách $l = 100$ m với một con tàu có một cốc nước đóng băng. Đảm bảo sự thăng hoa (bốc hơi) của băng, phi hành gia quay trở lại tàu. Phương thức hoàn vốn này có thực tế không? Hãy ước tính xem phi hành gia sẽ mất bao lâu để quay trở lại tàu vũ trụ. Hãy xem xét rằng sự thăng hoa của băng xảy ra ở nhiệt độ không đổi $T = 272$ K. Áp suất hơi bão hòa ở nhiệt độ này là $p_H = 550$ Pa. Hằng số khí phổ quát là $R = 8,3 \times 10^3$ J/(kmol·K). Tự mình đặt kích thước của ly và khối lượng đá.

Nếu kính đóng chặt thì số phân tử rơi trên bề mặt băng trong một đơn vị thời gian sẽ bằng số phân tử thăng hoa trên bề mặt (cân bằng động); trong điều kiện này, áp suất hơi bão hòa $p_H$ thay đổi. Cả hai dòng khối lượng được chỉ định đều bằng nhau theo mô hình $\frac{1}{6} \rho_H \bar{v} S$ (kg/s), trong đó $\rho_H = p_H \mu/RT$ là mật độ của hơi bão hòa, $S$ là mật độ của bề mặt băng, $\mu$ là khối lượng mol của băng, $\bar{v} \approx \sqrt{3RT/μ}$ là tốc độ trung bình của các phân tử, hệ số nhân $1/6$ (hay chính xác hơn là $1/4$) sẽ tính đến hướng chuyển động “theo một trong sáu hướng có thể.” Khi kính mở ra, dòng phân tử bay đi vẫn như cũ nhưng không có phân tử quay trở lại; áp suất khủng khiếp là $1/2p_H$. Chúng ta hãy ước tính thời gian bay hơi hoàn toàn bằng cách thay khối lượng ban đầu của nước đá $m \approx 0,2$ kg, mật độ của thủy tinh $S \approx 30$ cm$^2$, $\mu = 18$ kg/kmol:

$$\tau \sim \frac{m}{\frac{1}{6} \rho_H \bar{v} S} \approx \frac{6m}{p_H S} \sqrt{\frac{RT}{3\mu}} \approx \frac{6 \cdot 0,2}{550 \cdot 3 \cdot 10^{-3}} \sqrt{\frac{8,3 \cdot 10^3 \cdot 272}{3 \cdot 18}} \approx 150 \text{ c}.$$

Lưu ý rằng do đó, thời gian bay hơi sẽ lâu hơn, vì xác suất để các phân tử bám trên bề mặt băng “dính” vào nó bằng cái gọi là hệ số ngưng tụ và tất nhiên là nhỏ hơn 1; Theo đó, một yếu tố phải được đưa vào dòng bay hơi, ít

⟦folio 28⟧

1. Hơn nữa, có lẽ không phải tất cả các phân tử sau khi bay hơi đều có thể bay đi ngay lập tức đến vô tận; Một số trong chúng có thể quay trở lại do va chạm ở pha hơi. Vì vậy, chúng tôi đã ước tính được thời gian bay hơi của sizu.

Trong khi băng đang bay hơi, gia tốc của phi hành gia là $a = p_H S/2M$. Trong thời gian này anh ta sẽ bay một quãng đường $L = a\tau^2/2 \approx 100\text{ m} = l$.

Xem xét tính chất gần đúng của các ước tính của chúng tôi, chúng tôi có thể nói rằng phi hành gia sẽ quay trở lại tàu trong thời gian $\gtrsim 100\text{ c}$.

A. Stasenko

F652. Mạch điện trong hình bao gồm hai điện trở giống hệt nhau $R_2 = R_3 = R$ và hai điện trở phi tuyến tính giống hệt nhau $R_1$ và $R_4$, đặc tính điện áp của chúng có dạng $U = \alpha I^2$, trong đó $\alpha$ là hệ số hằng số vĩnh cửu neotary. Ở hướng nào của nguồn điện $U_0$ thì dòng điện qua điện kế $\Gamma$ có bằng 0 không?

F653. Một số phần tử Z, được nối với pin có emf $\varepsilon = 10\text{ B}$ và điện trở trong $r = 10\text{ K}\Omega$, được nối với nguồn dòng điện bên ngoài như trong Hình 1. Đặc tính điện áp-điện áp của mạch như vậy được thể hiện trong Hình 2 (đường cong màu đen). Vẽ đặc tính vôn kế của phần tử Z.

Hình 1. Hình 2. $I_6(U)$

F654. Giá đỡ khối lượng M được đặt trên bàn chính. Một quả cầu khối lượng m được gắn vào một giá ba chân bằng một sợi dây mảnh có chiều dài l. Sợi chỉ bị lệch một góc nhỏ a và được thả ra (Hình 1). Narip

Cho dòng điện chạy qua một nhánh của mạch I. Vì cả hai điện trở tuyến tính và phi tuyến đều giống nhau nên dòng điện giống nhau chạy trong các nhánh của mạch. Điện áp của nguồn điện là

$$U_0 = IR + \alpha I^2.$$

Vậy qua điện kế bằng 0 khi điện thế của điểm A bằng điện thế của điểm B. Do đó

$$IR = \alpha I^2 \Rightarrow I = \frac{R}{\alpha}.$$

Thay giá trị dòng điện này vào phương trình (*), ta tìm được hướng của nguồn tại đó dòng điện qua điện kế bằng 0:

$$U_0 = 2 \frac{R^2}{\alpha}.$$

V. Skorovarov

Hãy xây dựng đặc tính đồng hồ đo điện áp của pin. Theo định luật Ohm đối với một mạch điện hoàn chỉnh, hướng $U_6$ trên pin và dòng điện $I_6$ chạy qua pin có liên hệ với nhau bởi

$$U_6 = \varepsilon - I_6 r.$$

Vì tế bào Z và pin được kết nối song song nên $U_6 = U_2 = U$ (U là hướng của nguồn bên ngoài).

Trong hình 2, đặc tính của đồng hồ đo điện áp của ắc quy là đường thẳng màu xanh.

Dòng điện $I_2$ chạy qua phần tử Z bằng hiệu đại số $I - I_6$. Để xây dựng đặc tính vôn kế của phần tử Z, với mỗi giá trị hướng cố định $U$, hãy tìm giá trị $I_2$ bằng cách trừ tọa độ $I_6$ của điểm tương ứng của đặc tính vôn kế $I_6(U)$ khỏi tọa độ của điểm tương ứng của đặc tính vôn kế của mạch điện.

Trong Hình 2, đặc tính điện áp $I_2(U)$ là đường cong màu đỏ.

V. Mozhaev

Ở một góc lệch nhỏ α, chuyển động của quả bóng khác rất ít so với phương ngang. Theo phương ngang, không có ngoại lực nào tác dụng lên hệ và động lượng của hệ (chính xác hơn là hình chiếu của động lượng lên trục hoành) không đổi - bằng 0. Do đó, khi bóng di chuyển, ống chân sẽ di chuyển theo hướng ngược lại

⟦folio 29⟧

tương ứng với biểu đồ tốc độ của shativa theo thời gian. Quả bóng va chạm với đế của shativa hoàn toàn đàn hồi.

Hình 1.
$$\begin{align*}
|AO|: |OB| &= m : M; \\
A'O'|: |O'B| &= m : M \\
A'O'| + |O'B| &= l
\end{align*}$$

$$\Rightarrow |O'B| = l \frac{M}{m+M}.$$

Hình 2. $\tau = \frac{\pi}{2} \sqrt{\frac{l}{g} \frac{M}{m+M}}$.

F655. Hiện nay, các cuộn dây điện từ có cuộn dây siêu dẫn được sử dụng. Những cuộn dây điện từ như vậy có thể tạo ra từ trường trong thời gian dài mà không tiêu tốn năng lượng. Tuy nhiên, nếu vì lý do nào đó mà một phần của cuộn dây điện từ mất đi đặc tính siêu dẫn thì sẽ xảy ra tai nạn. Tại khu vực này, một lượng lớn dòng điện sẽ được giải phóng và một vụ nổ sẽ xảy ra. Hãy nghĩ ra thiết bị đơn giản nhất để loại bỏ những tai nạn như vậy (đừng cố nghĩ ra bất kỳ mạch nào có rơle mở mạch - chúng sẽ không giúp ích gì).

bên; Các giá trị tuyệt đối $v$ và $u$ của vận tốc của cá mập và shativ (chính xác hơn là hình chiếu của vận tốc tương ứng trên trục hoành) có liên quan với nhau bởi mối quan hệ

$$mv = Mu.$$

Khối tâm của hệ (điểm $O$ trong Hình 1) đứng yên; Điều này có nghĩa là điểm $O'$ cũng vẫn cố định.

Như vậy, chuyển động của quả cầu là sự dao động của một nam châm với chiều dài của sợi dây

$$l' = |O'B| = l \frac{M}{m+M}$$

(xem hình 1). Tần số của dao động này là

$$\omega = \sqrt{\frac{g}{l'}} = \sqrt{\frac{g}{l} \frac{m+M}{M}};$$

tốc độ bóng -

$$v = v_M \sin \sqrt{\frac{g}{l}} \frac{m+M}{M} t,$$

trong đó $v_M = \omega x_M = \sqrt{\frac{g}{l}} \frac{m+M}{M} l \sin \alpha$ là giá trị tốc độ tối đa (theo ý kiến ​​​​của tôi), $x_M = l \sin \alpha$ là biên độ của hỗn hợp Shark.

Sử dụng hệ thức (*), chúng ta tìm được tốc độ của shativa:

$$u = \left( \frac{m}{M} \sqrt{\frac{g}{l}} \frac{m+M}{M} l \sin \alpha \right) \sin \sqrt{\frac{g}{l}} \frac{m+M}{M} t =$$

$$= u_M \sin \sqrt{\frac{g}{l}} \frac{m+M}{M} t.$$

Sau mỗi va chạm đàn hồi, hướng của vận tốc $v_M$ và $u_M$ bị đảo ngược (kiểm tra điều này).

Đồ thị vận tốc của tàu con thoi theo thời gian được thể hiện trên Hình 2.

A. Zilberman

◆

Cách đơn giản nhất để ngăn ngừa tai nạn khi bất kỳ bộ phận nào của cuộn dây được nối với kết nối siêu dẫn là đùa giỡn với cuộn dây. Trước đây, những dây dẫn lớn bằng đồng được sử dụng làm dây dẫn được đặt bên ngoài cuộn dây.

Hiện nay, cuộn dây siêu dẫn được chế tạo từ một bó sợi siêu dẫn mỏng được đặt trong một ma trận kim loại có độ dẫn điện và nhiệt cao - đồng hoặc nhôm. Khi kết nối siêu dẫn được thiết lập ở bất kỳ phần nào của cuộn dây, dòng điện sẽ chạy qua một dây dẫn bằng đồng lớn có điện trở thấp.

G. Myakshev
