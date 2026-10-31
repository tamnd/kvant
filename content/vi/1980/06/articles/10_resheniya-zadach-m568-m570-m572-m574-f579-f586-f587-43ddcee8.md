---
id: 1980-6-resheniya-zadach-m568-m570-m572-m574-f579-f586-f587-43ddcee8
issue: kvant_1980_6
year: 1980
number: "6"
title: Lời giải bài toán M568, M570—M572, M574; F579, F586, F587
rubric: zadachnik-kvanta
rubric_sub: Задачник «Кванта»
page_first: 22
page_last: 29
page_labels: 20, 21, 23, 24, 26, 27
tag: U3O8
lang: vi
source: kvant_digital
extraction: vision
content_sha256: 16fd2ea5e181d8799df7e0ab4588e3191e2918e4fb6848e452be19a770000ee8
prompt_sha256: draft-1
translated_from: content/ru/1980/06/articles/10_resheniya-zadach-m568-m570-m572-m574-f579-f586-f587-43ddcee8.md
source_content_sha256: 006203e37c185d5512be2c0eacc91e74d96855799cb787afd25007180c42cfb7
translation_model: draft
translation_run: vi-draft-2026-10-31
translation_quality: draft
---

⟦folio 20⟧

M568. Thiết kế tứ giác lồi ABCD cắt nhau tại điểm O. Chứng minh rằng
a) Nếu bán kính đường tròn nội tiếp các tam giác AOB, BOC, COD và DOA bằng nhau thì ABCD là hình thoi;
b) Nếu bán kính đường tròn nội tiếp các tam giác ABC, BCD, CDA và DAB bằng nhau thì ABCD là hình chữ nhật.

Hình 1.

Hình 2.

Hình 3.

Gọi $r$ là bán kính, $O_1$ và $O_2$ là tâm của các đường tròn nội tiếp tam giác AOB và COD; $P, Q, R, S$ là điểm tiếp tuyến của các đường tròn này với các cạnh AO, BO, CO, DO của các tam giác này (Hình 1).

Trước hết ta chứng minh tứ giác ABCD là hình bình hành. Để làm điều này, chỉ cần chứng minh rằng các đường chéo AC và BD của nó được chia đôi bởi điểm O.

Hãy giả sử rằng đây không phải là trường hợp. Ví dụ: đặt $|AO| > |OC|$. Chúng ta sẽ chứng minh rằng bất đẳng thức này bao hàm các bất đẳng thức $|BO| < |OD|$ và $|BO| > |OD|$, điều này không thể xảy ra.

Từ bất đẳng thức $|AO| > |OC|$ suy ra $|AP| > |CR|$, vì $|OP| = |OR|$; từ $|O_1P| = |O_2R|$ theo sau $O_1AP < O_2CR$ và do đó $BAO < DCO$. Do đó, $ABO > CDO$ và $BQ < DS|$, nhưng điều đó có nghĩa là $|BO| < |OD|$.

Lặp lại lý luận trên cho các tam giác BOC và AOD (Hình 2; bạn tự làm), chúng ta thu được $DAO < BCO$, do đó $ODA > CBO$, và do đó, $|DS_1| < |BQ_1|$, tức là $|BO| > |OD|$.

Mâu thuẫn thu được chứng tỏ rằng $|AO| = |OC|$. Nó cũng được chứng minh rằng $|BO| = |OD|$. Vậy tứ giác ABCD là hình bình hành.

Từ sự bằng nhau về diện tích của các tam giác AOB và BOC (chúng ta sử dụng công thức nổi tiếng $S = pr$), chúng ta thu được

$$\frac{1}{2}r(|AO| + |OB| + |AB|) = \frac{1}{2}r(|OC| + |OB| + |BC|),$$

từ đó $|BC| = |AB|$, tức là tứ giác ABCD là hình thoi.

6) Đầu tiên là lời giải. Gọi (Hình 3) $A_1$ và $A_2$, $B_1$ và $B_2$, $C_1$ và $C_2$, $D_1$ và $D_2$ là các điểm tiếp tuyến của các đường tròn nội tiếp các tam giác ABD, ABC, BCD, CDA, tính từ cạnh của tứ giác ABCD; $O_1, O_2, O_3, O_4$ là tâm của các vòng tròn này; $P, Q, R, S$ — điểm tiếp tuyến của các đường tròn với đường chéo AC và BD; $r$ - bán kính hình tròn.

Đầu tiên, chúng ta sẽ chứng minh một sự thật thú vị: đối với một tứ giác lồi tùy ý ABCD, độ dài các đoạn thẳng giữa các điểm tiếp tuyến nằm trên các cạnh đối diện của tứ giác bằng nhau, tức là $|A_1B_2| = |C_1D_2|$ và $|B_1C_2| = |A_2D_1|$.

Trước tiên chúng ta hãy đảm bảo rằng Hình 3 là “chính xác”, nghĩa là vị trí của các điểm tiếp tuyến trên các cạnh của tứ giác đúng như trong Hình 3.

Ví dụ, hãy xem xét các tam giác ABD và ACD và chứng minh rằng điểm $A_2$ nằm gần điểm $A$ hơn điểm $D_1$.

Để làm được điều này, chỉ cần chứng minh rằng $|AA_2| + |DD_1| < |AD|$ là đủ.

Thật dễ dàng để thấy điều đó

$$|AA_2| = \frac{|AB| + |AD| - |BD|}{2}$$

$$|DD_1| = \frac{|AD| + |CD| - |AC|}{2}$$

Cộng các đẳng thức này, ta được

$$|AA_2| + |DD_1| = |AD| + \frac{|AB| + |CD| - |BD| - |AC|}{2}$$

Nhưng $|AB| + |CD| < |BD| + |AC|$ (chứng minh điều đó!) và do đó

$$|AA_2| + |DD_1| < |AD|$$

Bây giờ chúng ta chứng minh rằng $|A_2D_1| = |B_1C_2|$ và $|D_2C_1| = |A_1B_2|$.

⟦folio 21⟧

Sử dụng tính chất của các đoạn tiếp tuyến (Hình 3), chúng ta thu được

$$|BD| = |BP| + |PD| = |BA_1| + |DA_2| =
= |BB_2| + |A_1B_2| + |DD_1| + |A_2D_1|.$$ (1)

Ở phía bên kia,

$$|BD| = |BR| + |RD| = |BB_1| + |B_1C_2| + |DD_2| + |D_2C_1| =
= |BB_2| + |B_1C_2| + |DD_1| + |D_2C_1|.$$ (2)

Đánh đồng biểu thức (1) và (2), ta thu được

$$|A_1B_2| + |A_2D_1| = |B_1C_2| + |D_2C_1|.$$ (3)

Thực hiện các phép tính chính xác cho đường chéo AC, ta thu được

$$|A_2D_1| + |D_2C_1| = |A_1B_2| + |B_1C_2|.$$ (4)

Cộng các đẳng thức (3) và (4) ta được

$$|A_2D_1| = |B_1C_2|.$$

Vì vậy, cũng $|D_2C_1| = |A_1B_2|$.

Cho đến nay chúng ta chưa sử dụng đẳng thức bán kính của các đường tròn nội tiếp nên kết quả thu được vẫn đúng cho một tứ giác lồi tùy ý.

Bây giờ hãy hoàn thành lời giải bài toán.

Vì tâm của các đường tròn cách đều nhau so với các cạnh tương ứng nên chúng ta thu được $(O_1O_2) \parallel (AB)$ và $(O_3O_4) \parallel (CD)$; và vì $|O_1O_2| = |A_1B_2|$ và $|O_3O_4| = |C_1D_2|$, chúng ta nhận được $|O_1O_2| = |O_3O_4|$.

Tương tự, $|O_2O_3| = |O_1O_4|$ và do đó, tứ giác $O_1O_2O_3O_4$ là hình bình hành, và vì các cạnh của tứ giác ABCD song song với hình bình hành nên tứ giác ABCD cũng là hình bình hành.

Cân bằng biểu thức diện tích các tam giác ABD và ABC, ta thu được

$$\frac{1}{2} r (|AB| + |BD| + |AD|) = \frac{1}{2} r (|CD| + |AD| + |AC|),$$

từ đâu $|BD| = |AC|$.

Do đó, các đường chéo của hình bình hành ABCD có độ dài bằng nhau nên ABCD là hình chữ nhật.

Thứ hai lời giải. Như trong lời giải đầu tiên, trước tiên chúng ta sẽ chứng minh rằng tứ giác ABCD là hình bình hành.

Để làm điều này, hãy vẽ các đường thẳng đi qua các điểm B và D, song song với cạnh AC (Hình 4) và đặt các đoạn BB' và DD' có độ dài $|AC|$ lên chúng ở một phía của đường thẳng BD.

Tứ giác BB'DD' hiển nhiên là hình bình hành. Dễ dàng nhận thấy các tam giác BCB', B'CD', CD'D lần lượt bằng các tam giác ABC, ABD và ACD nên bán kính các đường tròn nội tiếp các tứ giác mà hình bình hành được chia cho các đoạn CB, CB', CD và CD' đều bằng nhau.

Chứng minh điểm C trùng với điểm E giao điểm đường chéo của hình bình hành BB'D'D'.

Trên thực tế, nếu không phải như vậy thì điểm C thuộc về một trong các tam giác mà hình bình hành được chia cho các đường chéo của nó (trong Hình 4 đây là tam giác DED'). Trong trường hợp này, bán kính của đường tròn nội tiếp tam giác DED' sẽ lớn hơn r và bán kính của đường tròn nội tiếp tam giác BEB' sẽ nhỏ hơn r, điều này mâu thuẫn với sự đồng dạng của các tam giác DED' và BEB'.

Như vậy, điểm C trùng với giao điểm E của đường chéo hình bình hành BB'D'D' nên $[DC] \parallel [AB]$ và $[AD] \parallel [BC]$, tức là tứ giác ABCD là hình bình hành.

Để hoàn thành lời giải này, chỉ cần kiểm tra lý do đã được thực hiện ở cuối lời giải đầu tiên là đủ.

A. Egorov

⟦folio 23⟧

M571. Dãy số giảm dần $(x_n)$ của các số dương sao cho đối với mọi số tự nhiên $n$
$$\frac{x_1}{1} + \frac{x_2}{2} + \frac{x_3}{3} + \dots + \frac{x_n}{n} < 3.$$

Chúng ta sẽ chứng minh một phát biểu mạnh mẽ hơn: cho dãy số tự nhiên bất kỳ $n$
$$\frac{x_1}{1} + \frac{x_2}{2} + \frac{x_3}{3} + \dots + \frac{x_n}{n} < 2.$$
Thật vậy, vì $x_i > 0$,
$$\sum_{k=1}^{n} \frac{x_k}{k} \leq \sum_{k=1}^{(n+1)^2-1} \frac{x_k}{k} = \sum_{k=1}^{n} \sum_{m=k^2}^{(k+1)^2-1} \frac{x_m}{m}.$$
Vì trình tự $(x_n)$ là trình tự giết chóc,
$$\sum_{k=1}^{n} \frac{x_k}{k} \leq \sum_{k=1}^{n} x_k^2 \left( \sum_{m=k^2}^{k^2+k-1} \frac{1}{m} + \sum_{m=k^2+k}^{k^2+2k} \frac{1}{m} \right) \leq$$
$$\leq \sum_{k=1}^{n} x_k^2 \left( \frac{k}{k^2} + \frac{k+1}{k^2+k} \right) = 2 \sum_{k=1}^{n} \frac{x_k^2}{k} \leq 2,$$
đó là những gì được yêu cầu.

Ước tính 2 đã không thể cải thiện được: chúng tôi mời độc giả tự mình chứng minh rằng với bất kỳ $c < 2$ nào, người ta có thể tìm thấy một dãy số dương sao cho với bất kỳ số nguyên dương nào $n$
$$\sum_{k=1}^{n} \frac{x_k^2}{k} \leq 1 \text{ и } \sum_{k=1}^{n} \frac{x_k}{k} > c.$$

3. Chanturia

⟦folio 24⟧

M572. Chuột túi nhảy dọc theo mặt phẳng tọa độ $x \geq 0$, $y \geq 0$ Oxy theo cách sau: từ điểm $(x; y)$ chuột túi có thể nhảy đến điểm $(x+1; y-1)$ hoặc tới điểm $(x-5; y+7)$ và nhảy. Từ điểm ban đầu nào $(x; y)$ một con chuột túi không thể nhảy đến một điểm cách điểm xuất phát lớn hơn 1000? Vẽ tập hợp tất cả các điểm như vậy $(x; y)$ và tìm diện tích của nó.

![Graph](image)

M574. Chuỗi hữu hạn $a_1, a_2, \dots, a_n$ của các số 0 và 1 phải thỏa mãn điều kiện sau: với mọi số nguyên $k$ từ 0 đến $n-1$, tổng $a_1 a_{k+1} + a_2 a_{k+2} + \dots + a_n - k a_n$ là số lẻ. a) Nghĩ ra trình tự cho $n=25$. b) Chứng minh rằng dãy như vậy tồn tại với một số $n>1000$.

Một công thức khác của bài toán M574:
Tìm một dãy $e_1 < e_2 < \dots < e_i$ các số tự nhiên sao cho mỗi số từ 1 đến $e_i - e_1$ có thể được biểu diễn dưới dạng hiệu $e_j - e_i$ của một số số này theo một số cách lẻ.

Đáp số là một “tam giác bước” $T$ (xem hình): nó chứa hai khoảng ranh giới nửa kín $[0; A], [0; B]$ (trong đó $A$ và $B$ lần lượt là các điểm có tọa độ (5; 0) và (0; 5), nhưng không chứa bất kỳ điểm ranh giới nào khác (điểm của mười đoạn giới hạn “bước”). Diện tích của nó rõ ràng là 15.

Thứ nhất, đủ để chứng minh rằng một con kangaroo không thể rời khỏi “tam giác” $T$, và thứ hai, rằng từ các điểm còn lại của góc $x \geq 0, y \geq 0$ nó có thể di chuyển ra xa điểm gốc nhất có thể. Điều đầu tiên rất rõ ràng: khi tìm thấy $T$, con kangaroo chỉ có thể thực hiện các bước nhảy thuộc loại (1; -1), và do đó không thể tránh khỏi việc rơi vào trục $Ox$. Để chứng minh khẳng định thứ hai, hãy lưu ý rằng sự kết hợp của bước nhảy (1; -1) và một bước nhảy (-5; 7) sẽ cho ra “bước nhảy” (0; 2); do đó, một con kangaroo nằm trong khu vực $M_1 = \{(x; y) | x \geq 0, y \geq 5\}$ sẽ dễ dàng chạy thẳng lên trên, lặp lại sự kết hợp sáu lần nhảy này nhiều lần. Nếu kangaroo ở trong khu vực $M_2 = \{(x; y) | x \geq 1, 5 > y \geq 4\}$, sau đó bốn lần nhảy (1; -1) và một lần nhảy (-5; 7), kangaroo sẽ rơi vào khu vực $M_1$, từ đó nó có thể chạy trốn. Tương tự, tìm thêm bốn lần nhảy của “khu vực thoát hiểm” $M_3, M_4, M_5, M_6$

$$M_6 = \{(x; y) | x \geq 5 - k, k + 1 > y \geq k\}, k = 3, 2, 1, 0.$$

A. Sosinsky

Đầu tiên là lời giải. Thật dễ dàng để đưa ra chuỗi bốn số sau: $A_1 = 1101$. Để tạo chuỗi 25 số mong muốn, chúng tôi sử dụng $A_1$ ba lần và phân tách $A_1$ bằng các số 0 như sau:
$$A_2 = 1101 000 1101 00000000 1101.$$

Cấu trúc này có thể được tiếp tục thêm: nếu dãy $A = (a_1, a_2, \dots, a_n)$ thỏa mãn các điều kiện thì dãy

$$B = \begin{bmatrix} A & 00...0 & A & 00...0 & A \\ n & n-1 & n & 3n-2 & n \end{bmatrix},$$

bao gồm ba bộ $A$ và hai bộ số 0 cũng thỏa mãn điều đó.

Chúng ta hãy chứng minh một thực tế tổng quát hơn: cùng với các dãy $A = (a_1, a_2, \dots, a_n)$ và $C = (c_1, c_2, \dots, c_m)$, dãy $B$ có ​​độ dài $(2n-1)(m-1)+n$ từ $m$ “khối” thỏa mãn các điều kiện xác định:

$$B = \begin{bmatrix} a_1 c_1, & a_2 c_1, & \dots, & a_n c_1, & 0, 0, \dots, 0, \\ a_1 c_2, & a_2 c_2, & \dots, & a_n c_2, & 0, 0, \dots, 0, \\ \dots & \dots & \dots & \dots & \dots \\ a_1 c_m-1, & a_2 c_m-1, & \dots, & a_n c_m-1, & 0, 0, \dots, 0, \\ a_1 c_m, & a_2 c_m, & \dots, & a_n c_m \end{bmatrix};$$

ở đây khối thứ $j$ lặp lại chuỗi $A$ nếu $c_j = 1$ và 0 nếu $c_j = 0$.

Đặt $k = (2n-1) q+r$ là một số nguyên, trong đó $q=0; r=0, 1, \dots, n-1$ hoặc $-n < r < n, 0 < q < m$ (q và r là số nguyên). Sau đó, khi chuỗi $B$ được chuyển sang $k$ vị trí, khối thứ $j$ $(a_1 c_j, a_2 c_j, \dots, a_n c_j)$ sẽ chỉ giao nhau với khối $(j+q)-m$ của chuỗi ban đầu và có độ dịch chuyển là $r$ đơn vị trong chỉ mục

⟦folio 26⟧

M574 sẽ đạt được nếu chuỗi 0 và 1 nằm trên một vòng tròn và yêu cầu rằng với bất kỳ k nào thì tổng tích từng cặp của các mục tiêu cách nhau tại k là số lẻ. Nếu bạn đạt được kết quả cho việc này bài toán, hãy viết thư cho chúng tôi về điều đó.

F579. Trong mạch như hình, $R_1 = 10$ Ohm, $R_2 = 20$ Ohm, $R_3 = 15$ Ohm, chẳng hạn, trong mạng điện xoay chiều $U = 10$ V. Xác định công suất phân bổ cho các điện trở có điện trở $R_2$ và $R_3$.

![Circuit diagram](image)

Khi sử dụng diode dòng điện xoay chiều $T$, diode đóng và dòng điện xoay chiều $I = \frac{U}{R_1 + R_2}$ chạy qua điện trở $R_2$. Trong thời gian $T/2$ năng lượng được giải phóng trên điện trở $R_2$

$$W' = I^2 R_2 \frac{T}{2} = \frac{U^2 R_2 T}{2(R_1 + R_2)^2}.$$

Diode hữu ích thứ hai được mở. Tổng điện trở của các điện trở $R_2$ và $R_3$ mắc song song là $R_0 = \frac{R_2 R_3}{R_2 + R_3}$. Ví dụ: các điện trở này bằng $U_0 = \frac{U}{R_1 + R_0} R_0$.

Trong khoảng thời gian hữu ích này, năng lượng tương ứng được phân bổ cho các điện trở $R_2$ và $R_3$

$$W'' = U_0^2 R_2 \frac{T}{2} = \frac{U^2 R_0 T}{2(R_1 + R_0)^2},$$

$$W_3 = U_0^2 R_3 \frac{T}{2} = \frac{U^2 R_0 T}{2(R_1 + R_0)^2}.$$

Công suất trung bình được phân bổ cho điện trở $R_2$ và $R_3$ trong toàn bộ thời gian bằng công suất tương ứng

$$N_2 = \frac{W' + W''}{T} = \frac{U^2 R_2}{2(R_1 + R_2)^2} + \frac{U^2 R_0}{2R_2(R_1 + R_0)^2},$$

$$N_3 = \frac{W_3}{T} = \frac{U^2 R_0}{2R_3(R_1 + R_0)^2}.$$

Thay các giá trị số của đại lượng $U, R_1, R_2, R_3$, ta tìm được

$$N_2 \approx 1,6 \text{ Вт}, \quad N_3 \approx 0,7 \text{ Вт}.$$

G. Kotkin

F586. Bình chứa được bảo vệ được mở ra với độ chân không cao. Khí lý tưởng đơn nguyên tử bao quanh bình có nhiệt độ $T_0$. Tại một thời điểm nào đó, vòi được mở và bình chứa đầy khí. Khí sẽ có nhiệt độ bao nhiêu $T$ trong bình ngay sau khi đổ đầy?

Để hiểu nhiệt độ thay đổi như thế nào khi bình chứa đầy khí, cần xem xét nguồn gốc của sự biến đổi năng lượng. Khi mở vòi, một phần khí được đẩy vào bình dưới tác dụng của áp suất của khí xung quanh. Nhờ hoạt động của các lực này, khí thoát vào bình thu được động năng của chuyển động cực đại có hướng - nó đi vào bình dưới dạng dòng. Khi nó gặp thành bình và luồng khí đã đi vào bình, tia định hướng sẽ yếu đi và cuối cùng tiêu tan. Trong trường hợp này, động năng của chuyển động có trật tự của khí trong chip được chuyển thành nội năng, tức là năng lượng của chuyển động nhiệt hỗn loạn của các phân tử của nó.

Tất cả điều này xảy ra nhanh đến mức có thể bỏ qua sự trao đổi nhiệt của khí đi vào bình với khí và thành bình xung quanh. Vì vậy, đối với toàn bộ quá trình đang được xem xét

⟦folio 27⟧

Định luật nhiệt động thứ nhất có dạng: công $A$ của lực ép của bình xung quanh lên chất khí đi vào bình bằng độ biến thiên nội năng $\Delta U$ của chất khí đi vào:
$$A = \Delta U.$$

Khi đổ đầy một bình sơ tán nhỏ, áp suất và nhiệt độ trong khí quyển xung quanh không thay đổi. Do đó, để tìm công $A$ hãy tưởng tượng rằng bình đã sơ tán của chúng ta ở bên trong một hình trụ lớn có một pít-tông chuyển động được (xem hình). Xi lanh chứa đầy khí có nhiệt độ $T_0$; áp suất khí trong xi lanh $p_0$. Quá trình làm đầy bình tương ứng với chuyển động của piston sang phải ở áp suất không đổi $p_0$. Lớp tác động ở bên trái trên pít-tông thực hiện công $p_0V_0$, trong đó $V_0$ là thể tích “bị dịch chuyển” khi pít-tông chuyển động. Công này sẽ bằng sự giao thoa của công của các ngoại lực lên chất khí đổ vào bình, vì nội năng của khí không đi vào bình không đổi. Chúng ta hãy chú ý đến thực tế là thể tích $V_0$ không trùng với thể tích bên trong của bình chứa đầy, vì nhiệt độ $T$ của khí vào bình khác với $T_0$.

Sử dụng phương trình trạng thái của khí lý tưởng, công $A$ có thể được biểu thị dưới dạng nhiệt độ $T_0$ và lượng khí $v$ đi vào bình:

$$A = p_0V_0 = vRT_0.$$

Độ biến thiên nội năng $\Delta U$ của khí đi vào bình bằng

$$\Delta U = v \times \frac{3}{2}R(T - T_0).$$

Thay các biểu thức (2) và (3) vào phương trình của định luật nhiệt động thứ nhất (1), ta thu được

$$T = \frac{5}{3}T_0.$$

Do đó, nhiệt độ của khí nạp vào bình đã sơ tán cao hơn nhiệt độ của khí xung quanh bình. Lưu ý rằng kết quả thu được không phụ thuộc vào thể tích của bình hoặc áp suất $p_0$. Nhiệt độ của khí trong bình cũng không phụ thuộc vào việc bình có được đổ đầy đến cuối hay không cho đến khi áp suất trong bình bằng áp suất khí ngoài môi trường, hoặc van được đóng bằng nhau.

E. Butikov, A. Bykov, A. Kondratev

F587. Một dây dẫn có khối lượng $M$ và chiều dài $l$ được treo vào chất điện môi ở hai đầu của nó bằng hai lò xo vĩnh cửu dẫn điện giống hệt nhau có hệ số độ cứng chung $k$. Một tụ điện $C$ được nối với đầu trên của lò xo. Toàn bộ cấu trúc dâng lên trong một từ trường đều có cảm ứng $B$, vuông góc với mặt phẳng của cấu trúc.

Dây dẫn được dịch chuyển trong mặt phẳng thẳng đứng khỏi vị trí cân bằng và được thả ra. Xác định chuyển động tiếp theo của dây dẫn trong mặt phẳng thẳng đứng. Điện trở, độ tự cảm và điện dung của dây dẫn là giả tạo.

Hãy hướng trục tọa độ $X$ theo chiều dọc xuống dưới; Chúng ta sẽ lấy vị trí cân bằng của thanh làm gốc tọa độ (xem hình. ok).

Gọi $x_0$ là độ dài của mỗi lò xo ở vị trí này. Theo định luật P của Newton

$$Mg - kx_0 = 0.$$

Khi thanh di chuyển khỏi vị trí cân bằng thì lực không đổi nhưng lực đàn hồi thay đổi. Do đó, sau khi thả thanh ra, nó bắt đầu chuyển động với gia tốc về phía vị trí cân bằng. Vì chuyển động này xảy ra trong từ trường nên một lực điện động cảm ứng $\mathcal{E} = Bvl$ xuất hiện trong thanh, trong đó $v = \dot{x}$ tốc độ của thanh thay đổi theo Q, thời gian. Dòng điện xuất hiện trong mạch và tụ điện. Vì điện trở của lò xo dẫn điện bằng 0 nên hướng về phía tụ điện là $\mathcal{E}$ và điện tích $q$ của tụ điện là $\mathcal{C}\mathcal{E} = CBvl$. Do đó cường độ dòng điện trong mạch tại thời điểm bất kỳ bằng

$$i = \dot{q} = C\dot{\mathcal{E}} = CB\dot{v}l = CB\ddot{x}l.$$

Một thanh mang dòng điện đặt trong từ trường chịu tác dụng của một lực $F$
