---
id: 1974-7-resheniya-zadach-m231-m235-f238-f242-025319ff
issue: kvant_1974_7
year: 1974
number: "7"
title: Lời giải bài toán M231—M235; F238—F242
rubric: zadachnik-kvanta
rubric_sub: Задачник «Кванта»
page_first: 40
page_last: 49
page_labels: 38, 39, 40, 41, 42, 43, 44, 46, 47
tag: E6L3
lang: vi
source: kvant_digital
extraction: vision
content_sha256: 3c883dd9bf759fa95fb98f614312f4b84fe12eb0bcd39d6c42df2a6062a4bed7
prompt_sha256: draft-1
translated_from: content/ru/1974/07/articles/12_resheniya-zadach-m231-m235-f238-f242-025319ff.md
source_content_sha256: 0d71b36ba443c5ad2fa9108387aa2be49591bcd2e5a100b3a9efb4018ef87028
translation_model: draft
translation_run: vi-draft-2026-10-31
translation_quality: draft
---

⟦folio 38⟧

Lời giải bài toán

M231. Tìm tất cả lời giải trong các số tự nhiên của phương trình
$$n^x + n^y = n^z.$$
Rõ ràng, $n$ phải có ít nhất hai. Đếm $x \leq y \leq z$, ta viết lại phương trình dưới dạng
$$n^{z-x} - n^y-x = 1.$$ (*)
Nếu chúng ta giả sử rằng $y$ hoàn toàn lớn hơn $x$ thì từ (*) sẽ suy ra rằng đơn vị chia hết cho $n$ ($n \geq 2$); nhưng điều này không đúng, có nghĩa là $y = x$. Khi tính đến sự bình đẳng này, chúng tôi có được:
$$n^{z-x} = 2,$$
từ đâu $n = 2$, $z - x = 1$.
Vì vậy, phương trình này có tập hợp vô hạn lời giải số tự nhiên: $n = 2$, $y = x$, $z = x + 1$, $x$ - bất kỳ số tự nhiên nào.
R. Yegoryan.

M232. a) Chứng minh rằng với một tập hợp hữu hạn các điểm trên mặt phẳng có tính chất là ba điểm bất kỳ trong tập hợp này đều là đỉnh của một tam giác đa giác không suy biến, người ta luôn có thể thêm một điểm nữa để tính chất này được bảo toàn.
b) Phát biểu tương tự có đúng với tập vô hạn điểm trên một mặt phẳng không?

a) Lưu ý rằng đối với các điểm $A$ và $B$, điểm $C$ nằm ngoài đường thẳng $AB$ và nằm ngoài dải tạo bởi các đường vuông góc với đường thẳng $AB$ tại các điểm $A$ và $B$, tạo thành từ các điểm $A$ và $B$ một tam giác tù không số ít (xem hình 1). Với mỗi cặp điểm từ một tập hợp hữu hạn cho trước, chúng ta dựng một dải và một đường thẳng theo Hình 1. Một số hữu hạn các dải có chiều rộng hữu hạn và các đường thẳng, rất indo, sẽ không bao phủ toàn bộ mặt phẳng, do đó, có một điểm tạo thành một tam giác tù với mỗi cặp điểm từ một tập hợp cho trước, đó là điều ta cần chứng minh.
b) Đáp số: nói chung là không phải bên phải hay bên trong.
Hãy lấy ví dụ sau. Khoảng cách là một tập hợp bao gồm một điểm hình bán nguyệt không có đường kính một đầu (Hình 2). Thật dễ dàng để biết một bộ là gì

⟦folio 39⟧

Cơm. 6.

thỏa mãn điều kiện bài toán. Hãy để chúng tôi chứng minh rằng không thể thêm một điểm nào vào nó (điều này gần như rất indo). Trong thực tế, nếu một điểm nằm bên trong hình bán nguyệt trên đường kính của nó (Hình 3, điểm X), thì luôn có thể tìm được điểm C trên hình bán nguyệt sao cho tam giác ACX nhọn. Điều tương tự cũng đúng với tất cả các điểm nằm trong không phải hình bán nguyệt hoặc bên trong nhưng nằm ngoài đường kính của nó (Hình 4, các điểm X' và X''; các điểm tương ứng B', C' và B''', C'' được chọn "đủ gần"). Nếu điểm được chọn trên đường kính không phải hình bán nguyệt (Hình 5, điểm M), thì sẽ xảy ra sự đảo ngược - trong Hình 5, các điểm M, N, K nằm trên cùng một đường thẳng.

P. S. Pankov

M233. Ở cuối đoạn có viết hai đơn vị. Điểm nằm giữa chúng là tổng của chúng - số 2. Khi đó điểm giữa của hai số liền kề là tổng của chúng và lớn nhất là 1973 lần. Số 1973 sẽ được viết bao nhiêu lần?

Hãy viết ra các dòng số trong một hàng tạo thành từ bước tiếp theo - tổng cộng là 1973 dòng (Hình 6). Hãy lấy một cái bàn nào đó. Chúng ta hãy thử tìm xem số n xuất hiện ở hàng thứ n của bảng này bao nhiêu lần (rõ ràng là ở mỗi hàng tiếp theo - với một số lớn hơn n - số n sẽ xuất hiện chính xác với số lần như trong hàng thứ n: tất cả các số tạo mới sẽ lớn hơn n).

Chúng ta sẽ nói rằng bảng của chúng ta chứa một cặp số tự nhiên (a, b) nếu các số a và b nằm cạnh nhau trên cùng một dòng, với b ở bên phải a. Hãy chứng minh khẳng định sau:

Nếu 1973 là đơn giản (kiểm tra!). Vì vậy nó xảy ra 1972 lần.

N. B. Vasiliev

⟦folio 40⟧

M234. Cho một hình vuông có cạnh 1. Bốn phần được cắt ra khỏi nó - bốn hình tam giác, mỗi hình có hai cạnh chạy dọc theo các cạnh của hình vuông và chiếm 1/3 chiều dài của chúng. Với kết quả là 8-vui lòng, điều tương tự có thể được thực hiện: từ mỗi đỉnh, cắt một hình tam giác, hai cạnh của nó bằng 1/3 cạnh tương ứng của 8-vui lòng, v.v. Kết quả là một chuỗi các đa giác (mỗi đa giác có trong đa giác trước đó). Chúng ta hãy tìm diện tích của các hình là giao điểm của tất cả các đa giác này (nghĩa là được hình thành bởi các điểm thuộc tất cả các đa giác).

Chúng ta hãy biểu thị bằng $M_0$ hình vuông ban đầu và $M_1, M_2, M_3, \dots$ các đa giác thu được từ $M_0$ bằng cách cắt liên tiếp các góc. Cũng thuận tiện khi xem xét đa giác $N_h$, các đỉnh của nó là trung điểm của cạnh $M_h$ ($k = 0, 1, 2, \dots$).

Đặt $A$ là một đỉnh tùy ý của đa giác $M_h$, và $B$ và $C$ là các đỉnh lân cận của nó. Để thu được đa giác $M_h+1$ từ đa giác $M_h$, cần phải cắt một hình tam giác $B_2AC_2$ khỏi mỗi đỉnh $A$ của đa giác $M_h$ (xem Hình 8) sao cho các điểm $B_2$ và $C_2$ lần lượt chia các đoạn $[AB]$ và $[AC]$ theo tỷ lệ 1:2. Đặt $B_1$ và $C_1$ là trung điểm của các đoạn $[AB]$ và $[AC]$, tức là các đỉnh liền kề của đa giác $N_h$; Sau đó

$$\begin{align*}
|AC_2| &= \frac{2}{3}|AC_1|, \\
|AB_2| &= \frac{2}{3}|AB_1|.
\end{align*}$$

Khi di chuyển từ đa giác $N_h$ sang đa giác $N_{h+1}$, các điểm $B_1$ và $C_1$ vẫn là các đỉnh của nó nhưng không còn liền kề nữa: một đỉnh mới $A_1$—giữa đoạn $[B_2C_2]$—xuất hiện giữa chúng. Do đó, đa giác $N_{h+1}$ được lấy từ đa giác $N_h$ bằng cách thêm một hình tam giác loại $B_1A_1C_1$ vào mỗi cạnh của nó $[B_1C_1]$.

Cơm. 8.

⟦folio 41⟧

Nó bắt đầu từ phần trước bằng cách dốc xuống điểm $a$ $4\frac{1}{2}$ lần. Như vậy, điểm $a$ là điểm chung duy nhất của tất cả các đoạn thẳng này. (Có thể viết ra các công thức chính xác cho $x_h$ và $y_h$: $x_h = \frac{5}{7} - \left(\frac{2}{9}\right)^k \times \frac{3}{14}$, $y_h = \frac{5}{7} + \left(\frac{2}{9}\right)^k \cdot \frac{2}{7}$; nhưng chúng tôi không gặp chúng. Tất nhiên, người đọc quen với khái niệm giới hạn của một dãy số nhận thấy rằng $a$ là giới hạn chung của các dãy $x_h$ và $y_h$; về bản chất, đây chính xác là những gì chúng ta có đã chứng minh.) Từ đây chúng ta đã suy ra rằng diện tích của hình mong muốn $M$ (là giao điểm của tất cả các đa giác $M_h$) bằng $a$; thực sự, $M$ được chứa trong bất kỳ $M_h$ nào và chứa bất kỳ $N_h$ nào (chứng minh điều đó!)*); do đó, diện tích $M$ phải nằm trong khoảng từ $x_h$ đến $y_h$ (đối với tất cả $k$) và yêu cầu này được đáp ứng bởi một số duy nhất: $a = \frac{5}{7}$.

Có thể giải quyết bài toán này mà không cần đưa vào các đa giác $N_h$, chỉ sử dụng sự tương ứng xác định chuỗi $y_0 = 1$, $y_1 = \frac{5}{9}$, $y_2$, $y_3$, ...

$$y_h - y_{k+1} = \frac{1}{9} (y_h - y_{k-1}).$$

Trong trường hợp này, diện tích $M$ được tính là giới hạn của diện tích $M_h$ (chuỗi $(y_h - y_{k-1})$ là một cấp số nhân giảm vô hạn).

*) Số này là một thực tế lý thuyết tập hợp: nếu $M_h \supset M_{k+1} \supset N_{k+1} \supset N_h$ cho mỗi $k = 0, 1, 2, \dots$ và $M = \bigcap_k M_h$ thì $M \supset N_h$.

A. Zelensky (Shakhtersk) đã khái quát hóa bài toán M234 cho trường hợp khi các đoạn cấu thành $\frac{1}{p}$ của cạnh này bị cắt khỏi mỗi cạnh, trong đó $p$ là bất kỳ số nào lớn hơn 2. Diện tích thu được trong trường hợp này là $\frac{p^2 - 2p + 2}{p^2 - 2p + 4}$; với $p = 3$ chúng ta nhận được đáp số $\frac{5}{7}$.

C. Konyazin

M235. Một con sư tử đang chạy dọc theo sân khấu của một rạp xiếc hình tròn có bán kính 10 m. Di chuyển dọc theo một đường đứt đoạn, anh chạy được 30 km. Chứng minh rằng tổng tất cả các góc mà nó quay là $\alpha_1, \dots, \alpha_{k-1}$ (tổng cộng $k$ đoạn và $k-1$ phép quay). Hãy tưởng tượng chuyển động của con sư tử như sau.

Chúng ta hãy biểu thị các đoạn mà sư tử đi qua $x_1, x_2, \dots, x_h$ và các góc mà sư tử quay cùng lúc với $\alpha_1, \dots, \alpha_{k-1}$ (tổng cộng có $k$ đoạn và $k-1$ quay). Hãy tưởng tượng chuyển động của con sư tử như sau.

Cho sư tử chạy đoạn $AA_1 = x_1$. Chúng ta hãy xoay vectơ của nó (tức là vectơ của điểm $A_1$) theo góc $\alpha_1$ sao cho đoạn $x_2$ hóa ra là phần tiếp theo của đoạn $x_1$. Sau khi con sư tử chạy qua đoạn $A_1 A_2 = x_2$, chúng ta xoay vectơ đấu trường của nó một góc $\alpha_2$ để đoạn $x_3$ trở thành phần tiếp theo của đoạn $x_2$, v.v. Khi đó sư tử sẽ chạy theo một đường thẳng và bao phủ đoạn $AA_k = 30000(m)$, trong đó $A$ là điểm bắt đầu và $A_k$ là điểm kết thúc.

Hãy cùng theo dõi chuyển động của tâm đấu trường - điểm $O$. Đầu tiên, điểm $O$ quay vectơ của điểm $A_1$ theo góc $\alpha_1$, sau đó quay vectơ của điểm $A_2$ theo góc $\alpha_2$, v.v. Mỗi lần tâm của đấu trường $O$ cách tâm quay không quá 10 $m$, vì tâm quay là con sư tử nằm bên trong đấu trường. Do đó, trong lần quay đầu tiên, điểm $O$ sẽ di chuyển không quá $\alpha_1 \cdot 10(m)$, trong lần quay thứ hai - không quá $\alpha_2 \cdot 10(m)$, v.v. ($\alpha_1, \dots, \alpha_{k-1}$ được đo bằng radian). Tất cả các điểm $O$ di chuyển

Cơm. 10.

⟦folio 42⟧

Cơm. 11.

không quá $(\alpha_1 + \dots + \alpha_{k-1}) \cdot 10(m)$, tức là
$$O'O'' \leq (\alpha_1 + \dots + \alpha_{k-1}) \cdot 10(m)$$
(xem Hình 11 - ở đây $O'$ là vị trí ban đầu, $O''$ là vị trí cuối cùng của điểm $O$).

Vì $O'A \leq 10(m)$, $O''A_k \leq 10(m)$ và $AA_k = 30000(m)$, nên $O'O'' \geq 29980(m)$. Từ đây
$$\alpha_1 + \dots + \alpha_{k-1} \geq \frac{O'O''}{10} \geq 2998(m)$$

I. N. Bernishtein

F238. Có hai dây vuông làm bằng cùng một vật liệu. Mặt cắt ngang của một dây là $a_1 = 1$ mm, và mặt kia là $a_2 = 4$ mm. Để làm nóng chảy sợi dây đầu tiên, phải có dòng điện $I_1 = 10$ a chạy qua. Hỏi dòng điện chạy qua dây thứ hai bằng bao nhiêu để làm nóng chảy nó?

Chứng tỏ rằng lượng vật thoát ra môi trường trong 1 s tỷ lệ thuận với chênh lệch nhiệt độ giữa dây dẫn với môi trường và diện tích bề mặt của dây và hệ số tỷ lệ thuận với độ lệch của cả hai dây.

Nếu dây ở trạng thái cân bằng nhiệt với môi trường (nhiệt độ của nó không thay đổi), thì lượng điện năng được giải phóng trong dây khi dòng điện chạy qua trong một đơn vị thời gian sẽ bằng lượng điện năng được giải phóng trong môi trường xung quanh. Nếu dòng điện tăng đến mức dây bắt đầu nóng chảy, lượng điện năng bổ sung được giải phóng bởi dòng điện sẽ nóng chảy. Vì vậy, chúng ta cần tìm dòng điện tương ứng với nhiệt độ nóng chảy của dây.

Số vật thể được cắt bằng sợi dây trong một đơn vị thời gian bằng $Q_1 = k S_1 \Delta T = 4ka_1 l \Delta T$ và $Q_2 = k S_2 \Delta T = 4ka_2 l \Delta T$, trong đó $k$ là hệ số tỷ lệ

⟦folio 43⟧

hướng vuông góc với tốc độ $v$ của điểm và có giá trị tuyệt đối bằng $\frac{v^2}{R}$, trong đó $R$ là bán kính của đường tròn này. Do đó, rõ ràng là chúng ta có thể xác định $R$ nếu chúng ta biết tốc độ của điểm $v$ và gia tốc của nó $a$ theo hướng vuông góc với tốc độ này.

Đầu tiên, chúng ta hãy tìm vận tốc của các điểm $A$ và $B$ so với Trái đất. Ví dụ, điều này có thể được thực hiện bằng cách cộng vận tốc tuyến tính của các điểm trong hệ tọa độ gắn với tâm bánh xe và chuyển động tịnh tiến song song với mặt phẳng nằm ngang, với tốc độ chuyển động của hệ tọa độ này, tức là với tốc độ của tâm bánh xe so với mặt phẳng. Bạn có thể sử dụng một phương pháp ít xâm lấn hơn, đơn giản hơn nhiều. Tại thời điểm chúng ta đang xem xét, điểm $C$ chạm vào mặt phẳng, bất động so với mặt phẳng và chúng ta có thể giả sử rằng toàn bộ bánh xe quay so với điểm này (tâm quay tức thời). Vận tốc góc quay của tất cả các điểm của bánh xe so với tâm quay tức thời là như nhau và bằng nhau, đặc biệt, với tốc độ góc quay của tâm bánh xe:

$$\omega = \frac{v_0}{r}$$

($v_0$ là tốc độ tâm bánh xe). Điều này có nghĩa là tốc độ của điểm $B$, vuông góc với đoạn $BC$, bằng

$$v_B = \omega \cdot BC = \frac{v_0}{r} BC.$$

Từ tam giác $BCD$ rõ ràng là $BC = 2r \cos \frac{\alpha}{2}$. Kể từ đây,

$$v_B = 2v_0 \cos \frac{\alpha}{2}.$$

Tương tự, vận tốc của điểm $A$ $v_A$ vuông góc với $AC$ bằng giá trị tuyệt đối

$$v_A = \omega \cdot AC = 2v_0 \cos \frac{\pi}{4} = v_0 \sqrt{2}.$$

Bây giờ chúng ta hãy tìm gia tốc của các điểm $B$ và $A$, vuông góc với vận tốc của các điểm này. Tổng gia tốc của các điểm này hiển nhiên là gia tốc hướng tâm $a_\mu$ trong hệ tọa độ gắn với tâm bánh xe. Thật vậy, vì bánh xe chuyển động tương đối so với một mặt phẳng đều, nên gia tốc của một điểm của bánh xe trong hệ tọa độ liên kết với mặt phẳng trùng với gia tốc của chúng trong hệ tọa độ chuyển động tịnh tiến với tâm của bánh xe. Do đó, gia tốc hướng tâm của các điểm

$$A$$ và $B$ hướng về tâm bánh xe và có giá trị tuyệt đối bằng $a_\mu \cdot A = a_\mu \cdot B = \frac{v_0^2}{r}$.

Gia tốc của các điểm $A$ và $B$, vuông góc với vận tốc $v_A$ và $v_B$, là hình chiếu của gia tốc $a_\mu \cdot A$ và $a_\mu \cdot B$ theo hướng vuông góc với $v_A$ và $v_B$. Chúng bằng với những cái tương ứng.

$$a_A = a_\mu \cdot A \cos \frac{\pi}{4} = \frac{v_0^2}{2r} \sqrt{2},$$

$$a_B = a_\mu \cdot B \cos \frac{\alpha}{2} = \frac{v_0^2}{r} \cos \frac{\alpha}{2}.$$

Như vậy, tại thời điểm này các điểm $A$ và $B$ đang chuyển động theo đường tròn, bán kính của nó được xác định từ sự tương ứng

$$\frac{v_A^2}{R_A} = \frac{v_0^2}{2r} \sqrt{2}$$

và $$\frac{v_B^2}{R_B} = \frac{v_0^2}{r} \cos \frac{\alpha}{2},$$

hoặc

$$\frac{(v_0 \sqrt{2})^2}{R_A} = \frac{v_0^2}{2r} \sqrt{2}$$

và $$\frac{(2v_0 \cos \frac{\alpha}{2})^2}{R_B} =$$

$$= \frac{v_0^2}{r} \cos \frac{\alpha}{2}.$$

Từ đây

$$R_A = 2r \sqrt{2}$$ và $$R_B = 4r \cos \frac{\alpha}{2}.$$

F240. Đầu dò bóng bay có vỏ không thể mở rộng đã nâng lên độ cao tối đa và tạo thành một bình nhỏ, ép rằng ở độ cao tối đa, mật độ không khí $\rho$ giết chết độ cao một cách đồng đều với các giá trị $\delta = 1,2 \cdot 10^{-2}$ $\rho$ cứ sau $h = 100$ m.

Trước hết, chúng ta sẽ chứng minh rằng quả bóng thực sự dao động. Có hai lực tác dụng lên nó: lực hấp dẫn $mg$ và lực Archimedean nổi $F_B$. Cả hai lực đều hướng theo phương thẳng đứng nhưng ngược chiều nhau. Rõ ràng ở vị trí cân bằng

$$mg = F_B,$$

trong đó $m$ là khối lượng của quả bóng, $F_B = \rho Vg$ ($V$ là thể tích của quả bóng).

Nếu do một số vật ngẫu nhiên mà quả bóng chuyển động khỏi vị trí cân bằng thì độ lớn của lực nổi sẽ thay đổi. Hơn nữa, khi di chuyển quả bóng lên $F_B$

*) Vì bánh xe lăn không trượt nên tốc độ quay tuyến tính của tất cả các điểm trên vành bánh xe bằng tốc độ chuyển động tịnh tiến của tâm bánh xe.

⟦folio 44⟧

giảm đi và khi trộn lẫn vào nhau thì tăng lên. Như vậy, trong cả hai trường hợp sẽ xuất hiện một lực bằng nhau, bằng độ biến thiên của lực nổi và hướng về vị trí cân bằng. Hãy tìm độ lớn của nó.

Để quả bóng chuyển động khỏi vị trí cân bằng ở $x$. Vì mật độ không khí thay đổi đồng đều theo độ cao nên

$$\frac{\Delta \rho}{\delta} = \frac{x}{h},$$

trong đó $\Delta \rho$ là sự thay đổi mật độ không khí ở độ cao $x$. Sau đó

$$\Delta F_B = -\Delta \rho Vg = \frac{-\delta Vg}{h} x$$

(dấu trừ cho biết lực $\Delta F_B$ luôn hướng về vị trí cân bằng).

Ta thấy rằng một lực bằng nhau tác dụng lên quả bóng hướng về vị trí cân bằng và tỷ lệ thuận với độ lệch của quả bóng so với vị trí cân bằng. Điều này có nghĩa là quả bóng thực hiện một dao động điều hòa, tương tự như các dao động của tải trọng bên ngoài (với $F = kx$). Vai trò của hệ số độ cứng lò xo trong trường hợp này được thể hiện bởi các đại lượng

$$k' = \frac{\delta Vg}{h}.$$

Chu kỳ dao động của quả bóng bằng

$$T = 2\pi \sqrt{\frac{m}{k'}} = 2\pi \sqrt{\frac{mh}{\delta Vg}}.$$

Vì $m = \rho \cdot V$ thì

$$T = 2\pi \sqrt{\frac{h\rho}{\delta g}} = 2 \cdot 3,14 \sqrt{\frac{100 \cdot \rho}{1,2 \cdot 10^{-2} \rho \cdot 10}} \approx 180$$ (giây).

F241. Một vòng khối lượng $m$ có thể trượt dọc theo một thanh có chiều dài $L$. Sức mạnh của yêu sách giữa anh ta là $F$. Xác định tốc độ tối thiểu $v_0$ thanh cần truyền để nó xuyên qua bình nếu bình bị vỡ trước.

Thí nghiệm được thực hiện trong môi trường không trọng lực.

Bài toán lời giải hoàn toàn giống với bài toán bài toán F228 (xem «Kvant», 1974, số 5). Đó là lý do tại sao

$$v_0 = \sqrt{2LF \frac{M + m}{Mm}},$$

trong đó $M$ là khối lượng của thanh.

F242. Camera obscura là một hộp hình chữ nhật có một lỗ tròn trên một trong các bức tường của nó. Độ chiếu sáng của hình ảnh Colnca, thu được trên bức tường đối diện của máy ảnh - màn hình, đầu vào nada khi di chuyển từ tâm hình ảnh ra rìa bằng bán kính 0,9 của hình ảnh. Độ sáng ở bức tường phía trước của máy ảnh lớn hơn độ sáng ở giữa ảnh bao nhiêu lần?

Mỗi điểm của hình ảnh Coln được chiếu sáng không phải bởi toàn bộ Coln mà chỉ bởi phần của nó có thể nhìn thấy được từ điểm này trong một góc nhỏ được giới hạn bởi lỗ mở của camera lỗ kim. Vì khẩu độ máy ảnh nhỏ và Colnce ở rất xa nên chúng ta có thể giả sử rằng góc đặc này là như nhau đối với tất cả các điểm của ảnh Colnce. Rõ ràng là độ chiếu sáng của điểm ảnh Colnc tỷ lệ thuận với mặt phẳng Colnc nhìn thấy được từ điểm này.

Sự thay đổi độ sáng của hình ảnh là do khi một điểm di chuyển ra khỏi tâm ảnh, phần Cột chiếu sáng điểm này sẽ tiến đến rìa của Cột và khi phần “đi” ra ngoài rìa của Cột, diện tích của nó sẽ giảm. Độ chiếu sáng của ảnh của một điểm giảm đi một nửa khi diện tích vùng Coln “chiếu sáng” điểm đó giảm đi một nửa. Trong trường hợp này, như có thể thấy trong Hình 13, tại thời điểm này, một chùm tia đi từ mép cột và đi qua tâm của lỗ buồng. Điều này cho phép bạn tìm góc nhìn thấy Colnce từ điểm trên bức tường phía trước của máy ảnh lỗ kim:

$$\frac{\alpha}{2} \approx tg \frac{\alpha}{2} = \frac{0,9R}{l},$$

trong đó $l$ là chiều dài của máy ảnh lỗ kim. Góc, hình. 13.

⟦folio 46⟧

P. Katsylo (Moscow) 16, 26-29; P. Kirsanov (Moscow) 26; L. Klimenok (Moscow) 27; M. Kobozev (Kyiv) 21, 22, 27; V. Kobiletsky (Baku) 16, 18, 20, 26, 27; A. Kolodin (Kolomya, vùng Ivano-Frankivsk) 21, 22, 24, 26, 27; S. Kolyada (Kyiv) 16, 21, 22, 24, 27, 30; L. Konytkovsky (Luninets, vùng Brest) 27; S. Kortsunov (Monino, vùng Moscow) 16, 17; V. Kostmanyan (Baku) 27; S. Kostmena (Chelyabinsk) 27; A. Komanov (làng Tsalka, GSSR) 27; L. Kofman (Tallinn) 16; I. Kryukov (Old Sambir, vùng Lviv) 21, 22; N. Kudrin (Kolomna, vùng Moscow) 27; A. Kukushi (Kyiv) 26, 27, 30; A. Kumakhov (s. II Lesen KBASSR) 27; A. Kurlyandik (Vilnius) 26, 27; A. Kutyrkin (Penza) 21, 22; S. Lapasikov (Oboyan, vùng Kursk) 26, 28, 30; M. Levin (Vitebsk) 17, 18, 27; M. Levin (Tallinn) 23; S. Lifsts (Kharkov) 16, 21; Yu. Loban (Evpatoria) 26, 27; M. Lyubi (Kharkov) 16, 19-23, 25-27, 29, 30; S. Lyapin (Petrikov, vùng Gomel) 16, 17, 21, 27; G. Mavzimov (làng Srednie Chelny TASSR) 27; M. Malyan (Yerevan) 27; A. Makariev (Lvov) 16-18, 20-22, 24, 26-29; S. Makarov (Saratov) 26-28; S. Malinsky (Poltava) 21—24, 27, 28, 30; G. Mamedov (Baku) 27; A. Markov (Moscow) 26, 27, 29; S. Melnik (Kharkov) 16, 18, 20—26, 28, 29; A. Mekhovich (Vladivostok) 27; V. Milman (Minsk) 26, 27; A. Miroshinchenko (Kharkov) 18; Yu. Mikhailov (Leningrad) 21-23; L. Mikhlin (Kursk) 16, 18, 20-22, 27-30; A. Morozov (Novosibirsk) 21; Yu. Muranov (Moscow) 21; G. Mustafaev (Sizan Az. Liên Xô) 27; K. Mkhitaryan (Yerevan) 16-22, 25-28; A. Navasardi (Yerevan) 27; Yu. Neretin (Moscow) 26, 27; N. Nechemayev (Leningrad) 16, 20-23, 25-28, 30; A. Nikolaev (Moscow) 20; I. Novikov (Kuibyshev) 16, 18, 21, 23-25, 27-30; S. Okhitin (Orenburg) 16, 20, 26-28; I. Panin (Sự thờ ơ) 16, 20-23, 26, 27; E. Pasike (Kharkov) 26, 27; V. Pelinenko (Voronezh) 26-29; O. Pechersky (Ordzhonnikdze) 16; Yu. Pinelis (Kzyl-Orda) 16-18, 20, 26, 27, 29, 30; M. Polovinnik (Mena, vùng Chernigov) 16; A. Ponosov (Perm) 21, 22, 24-30; V. Porzein (Rostov-on-Don) 18, 21, 24, 27, 30; R. Portnoy (Chernivtsi) 21, 27, 29, 30; D. Potsshivili (Tbilis) 27; V. Prasolov (Voroshilovgrad) 26, 27, 29; Yu. Promas (Cahul MSSR) 18, 23, 27; S. Putintsev (Kemerovo) 16, 18, 20, 22, 23, 25-28; L. Rabinovich (Tula) 21-23, 25-30; A. Razulev (Klin, vùng Moscow) 18, 20—23, 25, 27; A. Rashkovsky (Kharkov) 26, 27; A. Reznikov (Kyiv) 16, 21, 22, 26, 27; A. Reptsein (Kramatorsk, vùng Donetsk) 16, 18-21; G. Rodin (Leningrad) 21, 23; R. Rozhkov (Moscow) 26, 27; F. Rozhkov (Ryazan) 26, 27; M. Rozhkova (Kyiv) 18; E. Romanovsky (Kyiv) 26-28, 30; V. Rubaevsky (Kyiv) 20, 21, 27, 28; N. Rundkovist (Sverdlovsk) 16; A. Rybkov (Murom)

⟦folio 47⟧

Dưới đây là danh sách độc giả đã gửi lời giải bài toán F223—F242. Hầu hết tất cả độc giả đều giải đúng Bài toán F223 và F233; lời giải đúng trong số bài toán còn lại đã được thêm vào (số in đậm sau họ là hai chữ số cuối của số đã giải bài toán):

N. Abramenko (Mogilev) 30, 36, 38, 40; D. Azov (Chelyabinsk) 38; S. Akmertsev (Moscow) 28, 34; A. Amelchenko (Magnitogorsk) 25, 32, 36, 37; I. Ankudinov (Nalchik) 34, 36, 37; P. Antsferov (Fatezh) 34, 36, 38, 39, 40; V. Bakurov (Novosibirsk) 25, 28, 29, 32, 34, 36, 38, 40; A. Baraov (Moscow) 24, 28, 34, 40; A. Barsukov (Pyatigorsk) 28, 39; R. Basyrov (D. Karakityany Tat. ASSR) 28, 38, 40; M. Belkin (Pinsk) 24—29, 30, 32, 34, 36, 38—41; A. Belusov (Moscow) 28, 30, 32, 34; V. Bellev (Moscow) 28, 38, 40, 41; V. Benkhan (Kalinin) 37; S. Berezin (Kimry) 38; Yu. Blyakher (Dushanbe) 28; L. Bozemolov (Odessa) 33, 41; S. Borozdin (Novgorod) 25, 28, 29, 32; A. Braslavets (Novosibirsk) 34—36, 38, 40; I. Bramovskaya (Novosibirsk) 24; J. Buchinskas (quận Shilbsky Lit. SSS) 34, 36, 38-40; I. Vandakurov (Leningrad) 28; S. Vasiliev (Leningrad) 22, 38-40; I. Vinyar (Oregev) 28, 38; A. Voletsov (Sverdlovsk) 36; P. Volokhov (làng Criulani Mold. SSS) 40; A. Voskanyan (Yerevan) 24, 25, 28, 29, 34, 36; R. Gabdulin (Kazan) 37; D. Gabrilyan (Belaya Kalitva) 40; V. Gavrilok (Minsk) 40, 41; M. Gazda (làng Klevan, vùng Rivne) 24-27; V. Galtsev (Orenburg) 38; A. Galochenko (Kharkov) 29, 30, 32, 34, 36; S. Garkusha (TASHKENT) 40; A. Tiếng Đức (Voronezh) 25; S. Hertz (Khust) 32, 40; R. Girdyanis (Vilnos) 40, 41; Yu. Gladyo (Ternovol) 24; L. Glazman (Kharkov) 25, 26, 29, 30, 34-38; 40, 41; A. Gririev (Grozny) 28; A. Griebere (Chisinau) 29, 40; S. Grishin (Vyazyvam) 36; M. Gulyansky (Magnitogorsk) 25, 30, 32, 38; A. Gurevich (Minsk) 25, 26, 28—32, 38, 40, 41; S. Davtyan (Oktemberyan) 34, 36, 38, 40, 41; A. Davydov (Magnitogorsk) 25, 29—32, 34, 36; S. Darkembaev (Alma-Ata) 26; S. Demidov (làng Sosnovka, vùng Vologda) 36; O. Denisov (Baku) 37; Yu. Dokuaev (Leningrad) 28-30, 38; N. Dubrovsky (Omsk) 38-41; R. Yegoryan (Yerevan) 25, 28, 31; G. Erkhanpetyan (Yerevan) 29, 31, 32; K. Zhakunbekov (làng Barshatas, vùng Semipalatinsk) 40; V. Zhelezov (làng Oktyabrsky, vùng Amur) 36, 38, 40; V. Zhuk (Grozny) 27-29, 31, 32, 36, 38-41; S. Zazovsky (Novomoskovsk) 38; M. Zaks (Perm) 40; S. Zenovich (TASHKENT) 40; E. Zubko (Ivanov-Frankivsk) 25, 28, 29, 32, 34, 38, 40; V. Ivanov (Zheleznodorozhny) 28; V. Nenatev (Volgograd) 24-27; A. Izmailov (Baku) 34, 40; A. Ilkun (Zelenodolsk) 25, 38, 40; A. Kazkov (Rudny) 24; S. Kalyaev (Sosnovy Bor) 38; V. Kanzova (Deproederzhinsk) 24, 26; V. Karlin (quận Volokolamsky, khu vực Moscow) 24; V. Kachman (Mytschits) 38; M. Kachanovsky (làng Vishnevchi, vùng Brest) 24, 25; V. Kovalevsky (Vitebsk) 24; L. Koran (Leningrad) 40; Y. Koran (Glazov) 24, 25, 32, 40; S. Korneev (Novokuznetsk) 25-27; S. Korshunov (làng Monno, vùng Moscow) 24, 25, 38, 40, 41; L. Kofman (Tallinn) 24, 34, 40; I. Kotsearova (Rybinsk) 28; G. Koyava (Tskhinvali) 32, 36, 38; S. Krivonos (Dnepropetrovsk) 24, 25; I. Kryukov (Stayy Sambir) 28; N. Kudrin (Kolomna) 38, 40, 41; A. Kudryashov (Saratov) 36; V. Kuzmin (Grozny) 24, 40; P. Kuzmin (Ulan-Ude) 28-32; A. Kumanov (Frunze) 24; A. Kumiliumarov (vùng Khorezm, SSS của Uzbekistan) 27, 27; I. Kutsik (Yaroslavl) 28, 30, 31, 36, 40, 41; R. Kucharov (vùng Khorezm. SSS của Uzbekistan) 28, 32; Yu. Lavrov (trạm Kanevskaya, vùng Krasnodar) 32, 40; A. Levitas (Kyiv) 36; A. Lektsinov (Mỏ) 24, 28; A. Lukyanov (Dubovsky) 36; P. Lyedenov (làng Kizhinga) 40; A. Lvov (Saratov) 28; S. Lyapin (p/o Blokorovich, vùng Zhytomyr) 24; V. Mazalov (Siauliai) 36, 40; M. Mashil (Yerevan) 24; A. Makartsev (Livov) 24, 34, 36-38, 40; A. Makarov (Kharkov) 36; S. Makarov (Saratov) 24, 26, 38-40; S. Maksimov (Alma-Ata) 37; G. Mamedov (Baku) 34—38, 40; Yu. Markin (Kharkov) 38; A. Markov (Moscow) 38, 42; S. Melnik (Kharkov) 24, 28, 32, 38, 40, 41; E. Mett (Leningrad) 36, 38, 40; L. Mirodoshvili (Tbilisi) 38-40; A. Molotkov (p/o Kubinka, vùng Moscow) 36, 38, 40; V. Momkovsky (Kyiv) 34; R. Musin (làng Nikitino, vùng Orenburg) 24; R. Nazarudlov (Sterlitamak) 28, 29; I. Nikitin (Leningrad) 29; I. Nikitin (Severomorsk) 28; A. Nikolaev (Moscow) 24, 26, 28, 29, 31-32, 34, 36, 38-41; G. Odanisan (V. Artashat Arm. SSS) 36; A. Okun (Odesca) 28; S. Omelchenko (Zaporozhye) 36; S. Ochuntsin (Perm) 38, 40; R. Ospanov (Bayram-Ali) 25, 28, 31, 32; S. Ostrovskaya (Kharkov) 34, 38; A. Parovichnikov (Obninsk) 24; Yu. Perfilyev (Saratov) 36, 40; Yu. Pinelis (Kzyl-Orda) 24, 26, 28-30, 40-42; K. Piraminsky (Chisinau) 36, 40; O. Povalyaev (Podolsk) 24, 34, 36, 38-40; A. Poedulya (Ufa) 24, 34, 36; M. Polikarpov (Moscow) 24, 35, 36, 38, 40; V. Polyakovsk (Petropavlovsk) 37; A. Polyyansky (Chelyabinsk) 34; S. Polyarush (Zhabinka) 40; V. Prasolov (Voroshilovgrad) 31; V. Razin (Belorets) 38; A. Reznikov (Kyiv) 24; A. Remeev (TASHKENT) 33, 34, 36, 38-40; S. Rendzink (Stry) 34, 36, 37; V. Reshetnyak (Kyiv) 34, 40, 41; A. Reshetnyak (Kyiv) 34, 40, 41; Y. Ryapisov (Lomonosov) 25, 38, 40; Sh. Samtsev (quận Dangara của Taj. SSS) 28, 29; V. Sviridov (vùng Soronezh) 39; R. Sereev (làng Perebrodye, vùng Vitebsk) 38; V. Sergeanov (làng Sredne-Belyaya
