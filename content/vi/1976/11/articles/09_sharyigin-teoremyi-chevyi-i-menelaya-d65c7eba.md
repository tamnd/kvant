---
id: 1976-11-sharyigin-teoremyi-chevyi-i-menelaya-d65c7eba
issue: kvant_1976_11
year: 1976
number: "11"
title: Định lý Ceva và Menelaus
authors:
  - Шарыгин И. Ф.
rubric: matematicheskiy-kruzhok
rubric_sub: Математический кружок
page_first: 24
page_last: 31
page_labels: 22, 24, 25, 26, 27, 28, 29
tag: 7DBD
lang: vi
source: kvant_digital
extraction: vision
content_sha256: e4f5ec327a02df8781c2a350e25609bea190c0338dc08cce6d3eddfe59eacab9
prompt_sha256: draft-1
translated_from: content/ru/1976/11/articles/09_sharyigin-teoremyi-chevyi-i-menelaya-d65c7eba.md
source_content_sha256: 248dcaa44178532f04d32ae4e049eb2dd0a2f95d1f9291419f2508f358d94c6d
translation_model: draft
translation_run: vi-draft-2026-10-31
translation_quality: draft
---

⟦folio 22⟧

Hình học bắt đầu bằng một hình tam giác. Tham khảo sách giáo khoa hình học ở trường, chúng ta sẽ thấy rằng các định lý có ý nghĩa đầu tiên liên quan cụ thể đến tam giác. Tất cả những cái trước chỉ là tiên đề, định nghĩa hoặc hệ quả đơn giản nhất của chúng. Vào buổi bình minh của sự xuất hiện, kế hoạch này về cơ bản là “hình học của một hình tam giác”.

“Hình học tam giác” có thể tự hào về những định lý mang tên Euler, Toricelli và Leibniz. Vào đầu thế kỷ 19 và 20, nhờ có số lượng lớn các công trình dành cho hình tam giác, thậm chí cả một phần của phép đo phẳng đã được hình thành, được gọi là “Hình học mới của Tam giác”. Nhiều tác phẩm trong số này hiện nay có vẻ chưa được liệt kê đầy đủ và không hoàn hảo; Thuật ngữ được sử dụng trong đó chỉ được viết một nửa và chỉ được tìm thấy trong bách khoa toàn thư. Tuy nhiên, một số định lý của “Hình học mới” vẫn tiếp tục tồn tại cho đến ngày nay. Hai định lý như vậy - của Cheva và Menelaus' - sẽ được thảo luận trong bài viết này *).

Các định lý của Ceva và Menelaus có thể được gọi là định lý "kép": chúng được xây dựng tương tự nhau (với mỗi định lý xuất hiện trong hai lĩnh vực) và đã được chứng minh, chúng có thể hoán đổi cho nhau cho lời giải bài toán. Các định lý của Cheva và Menelaus hóa ra đặc biệt hữu ích trong những trường hợp cần “làm rõ mối quan hệ” giữa điểm và đường thẳng - ví dụ, để chứng minh rằng ba đường thẳng nào đó cắt nhau tại một điểm, ba điểm nằm trên cùng một đường thẳng, v.v.

*) Bất kỳ ai muốn làm quen với hình học của một tam giác một cách chi tiết hơn có thể tham khảo cuốn sách “Hình học mới của một tam giác” của S. I. Zetel (M., Uchpedgiz, 1962).

⟦folio 24⟧

Cơm. 2.

Bằng chứng. Trước tiên, hãy kiểm tra xem $R$ và $R^*$ có cùng dấu hay không. Có thể dễ dàng xác minh rằng việc thay đổi hướng của một trong các vectơ $a, b, c, a_1, b_1, c_1$ sẽ không làm thay đổi giá trị $R^*$ ($\omega, \omega_1$), vì vậy bạn có thể chọn hướng của từng vectơ theo một cách nhất định; ví dụ: chúng ta có thể coi vectơ $a, b, c, a_1, b_1, c_1$ trùng hướng với vectơ $\overrightarrow{BC}, \overrightarrow{CA}, \overrightarrow{AB}, \overrightarrow{AA_1}, \overrightarrow{BB_1}$ và $\overrightarrow{CC_1}$ (Hình 2). Trong trường hợp này, mỗi phân số trong số ba phân số có trong biểu thức $R(\Delta, \Delta_1)$ đều có cùng dấu với phân số tương ứng có trong biểu thức $R^*$ ($\omega, \omega_1$). Ví dụ, phân số

$$\left\{ \frac{\overrightarrow{AC_1}}{\overrightarrow{C_1B}} \right\} \text{ и } \frac{\sin \theta (\overrightarrow{b}, \overrightarrow{c_1})}{\sin \theta (\overrightarrow{a}, \overrightarrow{c_1})}$$

sẽ dương nếu điểm $C_1$ nằm giữa các điểm $A$ và $B$ và được in dấu trong trường hợp ngược lại (Hình 3 và 2).

Vẫn còn phải chứng minh rằng $|R(\Delta, \Delta_1)| = |R^*(\omega, \omega_1)|$. chúng tôi có

$$\left\{ \frac{\overrightarrow{AC_1}}{\overrightarrow{C_1B}} \right\} = \frac{S_{\Delta ACC_1}}{S_{\Delta BCC_1}} = \frac{1/2 |AC| \cdot |CC_1| \cdot |\sin \theta (\overrightarrow{b}, \overrightarrow{c_1})|}{1/2 |BC| \cdot |CC_1| \cdot |\sin \theta (\overrightarrow{a}, \overrightarrow{c_1})|} = \times \frac{|AC|}{|BC|} \cdot \frac{|\sin \theta (\overrightarrow{b}, \overrightarrow{c_1})|}{|\sin \theta (\overrightarrow{a}, \overrightarrow{c_1})|},$$

$$\left\{ \frac{\overrightarrow{BA_1}}{\overrightarrow{A_1C}} \right\} = \frac{|AB|}{|AC|} \cdot \frac{\sin \theta (\overrightarrow{c}, \overrightarrow{a_1})|}{|\sin \theta (\overrightarrow{b}, \overrightarrow{a_1})|},$$

$$\left\{ \frac{\overrightarrow{CB_1}}{\overrightarrow{B_1A}} \right\} = \frac{|BC|}{|AB|} \cdot \frac{\sin \theta (\overrightarrow{a}, \overrightarrow{b_1})|}{|\sin \theta (\overrightarrow{c}, \overrightarrow{b_1})|}.$$

Cơm. 3.

Biến đổi ba đẳng thức này, ta được $|R(\Delta, \Delta_1)| = |R^*(\omega, \omega_1)|$. Bổ đề đã được chứng minh.

Trong phần tiếp theo, chúng ta sẽ cần một đẳng thức theo trực tiếp từ định nghĩa của $R^*(\omega, \omega_1)$:

$$R^*(\omega, \omega_1) = \frac{1}{R^*(\omega_1, \omega)}. \tag{4}$$

Bây giờ chúng ta hãy xây dựng các định lý của Ceva và Menelaus.

Định lý Ceva. Để các đường $AA_1, BB_1$ và $CC_1$ cắt nhau tại một điểm thì điều cần thiết và đủ là đẳng thức

$$R(\Delta, \Delta_1) = 1, \tag{5}$$

hoặc sự bình đẳng tương đương

$$R^*(\omega, \omega_1) = 1. \tag{5'}$$

Định lý Menelaus. Để các điểm $A_1, B_1, C_1$ nằm trên cùng một đường thẳng thì điều cần và đủ là đẳng thức

$$R(\Delta, \Delta_1) = -1, \tag{6}$$

hoặc sự bình đẳng tương đương

$$R^*(\omega, \omega_1) = -1. \tag{6'}$$

Chứng minh định lý Ceva

Sự cần thiết. Để các đường $AA_1, BB_1, CC_1$ cắt nhau tại một điểm. Hãy chứng minh rằng điều kiện (5) và (5') được thỏa mãn.

*) Biểu thức $R^*(\omega_1, \omega)$ được lấy từ biểu thức $R^*(\omega, \omega_1)$ của các vectơ tương hỗ $a$ và $a_1$, $b$ và $b_1$, $c$ và $c_1$.

⟦folio 25⟧

Cơm. 4a.

Lưu ý rằng nếu các đường $AA_1$, $BB_1$ và $CC_1$ cắt nhau tại một điểm thì cả ba điểm $A_1$, $B_1$ và $C_1$ đều nằm trên các cạnh của tam giác $ABC$ hoặc một trong các điểm nằm trên cạnh của tam giác và hai điểm còn lại nằm trên phần kéo dài của các cạnh tương ứng. Trong trường hợp đầu tiên, tất cả các phân số khác có trong biểu thức $R(\Delta, \Delta_1)$ đều dương và trong trường hợp thứ hai, một trong ba phân số có trong $R(\Delta, \Delta_1)$ là dương và hai phân số còn lại là âm, do đó, một lần nữa biểu thức $R(\Delta, \Delta_1)$ (và do đó $R^*(\omega, \omega_1)$ - xem bổ đề) lớn hơn 0. Bây giờ chúng ta hãy chứng minh rằng $|R^*(\omega, \omega_1)| = 1$ (vì $R^*(\omega, \omega_1) > 0$ nên $R^*(\omega, \omega_1)$ bằng một). Chúng ta hãy biểu thị điểm giao nhau của các đường $AA_1$, $BB_1$ và $CC_1$ bằng $D$ (Hình 4a). Áp dụng định lý sin, ta có

$$\frac{\sin \theta \vec{b}, \vec{c}_1}{\sin \theta \vec{b}, \vec{a}_1} = \frac{|DA|}{|DC|},$$

$$\frac{\sin \theta \vec{c}, \vec{a}_1}{\sin \theta \vec{c}, \vec{b}_1} = \frac{|DB|}{|DA|},$$

$$\frac{\sin \theta \vec{a}, \vec{b}_1}{\sin \theta \vec{a}, \vec{c}_1} = \frac{|DC|}{|DB|}.$$

Thay đổi các đẳng thức này, ta thấy rằng $|R^*(\omega, \omega_1)| = 1$. Như vậy sự cần thiết đã được chứng minh.

Tính đầy đủ Chứng minh được kiểm chứng đầy đủ bằng phương pháp

Cơm. 46.

"bằng sự mâu thuẫn." Giả sử rằng $R(\Delta, \Delta_1) (= R(\omega, \omega_1)) = 1$, nhưng các đường $AA_1$, $BB_1$ và $CC_1$ không đi qua một điểm (Hình 46). Chúng ta hãy biểu thị điểm giao nhau của đường $AA_1$ và $BB_1$ bằng $D_1$ và bằng $C'_1$ điểm giao nhau của đường $AB$ và $CD_1$. Vì các đường $AA_1$, $BB_1$ và $CC_1$ cắt nhau tại một điểm,

$$\left\{ \frac{\overrightarrow{AC}_1}{\overrightarrow{C'_1}B} \right\} \cdot \left\{ \frac{\overrightarrow{BA}_1}{\overrightarrow{A_1}C} \right\} \cdot \left\{ \frac{\overrightarrow{CB}_1}{\overrightarrow{B_1}A} \right\} = 1.$$

Nhưng theo điều kiện

$$\left\{ \frac{\overrightarrow{AC}_1}{\overrightarrow{CB}_1} \right\} \cdot \left\{ \frac{\overrightarrow{BA}_1}{\overrightarrow{A_1}C} \right\} \cdot \left\{ \frac{\overrightarrow{CB}_1}{\overrightarrow{B_1}A} \right\} = 1,$$

Ở đâu

$$\left\{ \frac{\overrightarrow{AC}_1}{\overrightarrow{CB}_1} \right\} = \left\{ \frac{\overrightarrow{AC}_1}{\overrightarrow{CB}_1} \right\}.$$

Vì cả điểm $C_1$ và điểm $C'_1$ đều nằm trên đường thẳng $AB$ nên điểm $C_1$ và $C'_1$ trùng nhau. Định lý Ceva đã được chứng minh.

Chứng minh định lý Menelaus

Sự cần thiết. Được biết, các điểm $A_1$, $B_1$ và $C_1$ nằm trên cùng một đường thẳng. Cần phải chứng minh đẳng thức (6) và (6′).

Một lần nữa lưu ý rằng nếu các điểm $A_1$, $B_1$ và $C_1$ nằm trên cùng một đường thẳng thì chúng đều nằm trên các phần mở rộng $BC$, $AC$ và $AB$ của tam giác.

⟦folio 26⟧

Cơm. 5.

biệt danh $ABC$ hoặc hai trong số các điểm $A_1, B_1, C_1$ nằm ở các cạnh tương ứng và điểm thứ ba nằm tiếp tục. Trong cả hai trường hợp, biểu thức $R(\Delta, \Delta_1)$ sẽ âm (hãy đảm bảo điều này). Bây giờ chúng ta hãy chứng minh rằng nếu các điểm $A_1, B_1, C_1$ nằm trên cùng một đường thẳng thì $|R(\Delta, \Delta_1)| = 1$ (vì $R(\Delta, \Delta_1) < 0$ nên sẽ tuân theo $R(\Delta, \Delta_1) = -1$).

Chúng ta hãy vẽ một đường thẳng song song với $AC$ qua điểm $B$ và biểu thị điểm giao nhau của nó với đường $B_1A_1C_1$ bằng $D$ (Hình 5).

Sử dụng sự tương tự, dễ dàng có được

$$\left\{ \frac{\overrightarrow{CA_1}}{\overrightarrow{A_1B}} \right\} = \frac{|B_1C|}{|BD|}, \quad \left\{ \frac{\overrightarrow{BC_1}}{\overrightarrow{C_1A}} \right\} = \frac{|BD|}{|AB_1|}.$$

Bằng cách cộng đẳng thức tiếp theo $$\frac{\overrightarrow{AB_1}}{\overrightarrow{B_1C}} = \frac{|AB_1|}{|B_1C|}$$ và biến cả ba đẳng thức đó, chúng ta thu được $|R(\Delta, \Delta_1)| = 1$ đó. Sự cần thiết của các điều kiện của định lý Menelaus đã được chứng minh.

Việc chứng minh tính đủ điều kiện (6) và (6') của định lý Menelaus được thực hiện tương tự như chứng minh tính đủ điều kiện (5) và (5') của định lý Ceva.

Phần nào theo sau

Việc đưa vào xây dựng các định lý của Ceva và Menelaus về hai điều kiện tương đương (5) và (5'), (6) và (6') được thực hiện không chỉ nhằm tạo thuận lợi cho việc chứng minh -

chứng minh các định lý này. Trong một số vấn đề, việc sử dụng một trong các điều kiện hóa ra lại thuận tiện, trong những vấn đề khác - điều kiện khác. Hãy chắc chắn điều này bằng cách cố gắng tự mình chứng minh nhận định sau.

Phát biểu 1. Nếu ba đường thẳng đi qua các đỉnh của một tam giác cắt nhau tại một điểm thì các đường thẳng đối xứng với chúng qua các đường phân giác tương ứng của tam giác cũng cắt nhau tại một điểm. Nếu ba đường thẳng cắt các cạnh đối diện của một tam giác tại ba điểm nằm trên cùng một đường thẳng thì các đường thẳng đối xứng với chúng qua các bissertric tương ứng cũng cắt các cạnh đối diện của tam giác tại ba điểm nằm trên cùng một đường thẳng.

Nếu nhớ lại đẳng thức (4), chúng ta có thể dễ dàng chứng minh được điều đó.

Phát biểu 2. Nếu ba đường thẳng đi qua các đỉnh A, B và C của tam giác ABC song song với các cạnh $B_1C_1, A_1C_1$ và $A_1B_1$ của tam giác $A_1B_1C_1$ cắt nhau tại một điểm thì các đường thẳng đi qua các đỉnh A, $B_1$ và $C_1$ của tam giác $A_1B_1C_1$ song song với các cạnh BC, AC và AB của tam giác ABC cũng cắt nhau tại một điểm. Nếu các đường thẳng cắt các cạnh tương ứng của tam giác ABC tại ba điểm nằm trên cùng một đường thẳng thì đây cũng là trường hợp các đường thẳng đi qua các đỉnh của tam giác $A_1B_1C_1$ song song với BC, AC và AB (Hình 6, 7).

Hãy tự mình chứng minh điều đó

Phát biểu 3. Nếu các đường thẳng đi qua các đỉnh A, B và C của tam giác ABC vuông góc với các cạnh $B_1C_1, A_1C_1$ và $A_1B_1$ của tam giác $A_1B_1C_1$ cắt nhau tại một điểm thì các đường thẳng kẻ từ các đỉnh A, $B_1$ và $C_1$ của tam giác $A_1B_1C_1$ với các đường thẳng BC, AC và AB cũng vuông góc

⟦folio 27⟧

cắt nhau tại một điểm. Nếu điểm đầu tiên của các đường thẳng cắt các cạnh tương ứng của tam giác ABC tại ba điểm nằm trên cùng một đường thẳng thì các đường thẳng đi qua các đỉnh của tam giác $A_1B_1C_1$ vuông góc với các cạnh của tam giác ABC sẽ cắt các cạnh tương ứng của tam giác $A_1B_1C_1$ tại ba điểm nằm trên cùng một đường thẳng (Hình 8, 9).

Chúng ta hãy lấy thêm hai ví dụ về việc sử dụng các cạnh của tam giác $A_1B_1C_1$ vuông góc với các cạnh của tam giác ABC, cắt các cạnh tương ứng của tam giác $A_1B_1C_1$ tại ba điểm nằm trên cùng một đường thẳng.

Bằng chứng. Chúng ta hãy biểu thị các điểm giao nhau của các đường được đề cập trong các điều kiện bằng các chữ cái K, L và M tương ứng. Chúng ta sẽ giả sử rằng các dòng $A_1A_2$ và $A_4A_5$ $A_2A_3$ và $A_5A_6$ $A_3A_4$ và $A_6A_1$ nằm trên cùng một đường thẳng.

Bằng chứng. Chúng ta hãy biểu thị các điểm giao nhau của các đường được đề cập trong các điều kiện bằng các chữ cái K, L và M tương ứng. Chúng ta sẽ giả sử rằng các dòng $A_1A_2$ và $A_4A_5$ $A_2A_3$ và $A_5A_6$ $A_3A_4$ và $A_6A_1$ nằm trên cùng một đường thẳng.

Hãy tạo bảng sau:

| A | K | $A_1$ | $A_2$ | B |
| :--- | :--- | :--- | :--- | :--- |
| B | $A_4$ | M | $A_3$ | C |
| C | $A_5$ | $A_6$ | L | A |

Các chữ cái ở mỗi hàng và mỗi cột của bảng này tương ứng với các điểm nằm trên cùng một đường thẳng.

Vì các điểm K, $A_4$ và $A_5$ cùng nằm trên các cạnh AB, BC và CA của tam giác ABC nên điều kiện (6) phải được thỏa mãn, đó là:

$$\begin{align*}
\frac{\overrightarrow{AK}}{\overrightarrow{KB}} &\cdot \frac{\overrightarrow{BA}_4}{\overrightarrow{A}_4C} \cdot \frac{\overrightarrow{CA}_5}{\overrightarrow{A}_5A} = -1.
\end{align*}$$

Tương tự như vậy

$$\begin{align*}
\frac{\overrightarrow{AA}_1}{\overrightarrow{A}_1B} &\cdot \frac{\overrightarrow{BM}}{\overrightarrow{MC}} \cdot \frac{\overrightarrow{CA}_6}{\overrightarrow{A}_6A} = 1,
\end{align*}$$

⟦folio 28⟧

Vì các điểm $A_1, A_2, A_5$ và $A_6$ nằm trên cùng một đường tròn và điểm $A$ là giao điểm của các đường $A_1A_2$ và $A_5A_6$ nên $|AA_1| \cdot |AA_2| = |AA_5| \cdot |AA_6|$. Chúng ta hãy xác định cho các vectơ thẳng hàng $\overrightarrow{AA_i}$ và $\overrightarrow{AA_j}$ giá trị $\{\overrightarrow{AA_i} \cdot \overrightarrow{AA_j}\}$, bằng tích độ dài của các vectơ $\overrightarrow{AA_i}$ và $\overrightarrow{AA_j}$, được lấy bằng dấu “+” nếu các vectơ $\overrightarrow{AA_i}$ và $\overrightarrow{AA_j}$ được kết nối và bằng dấu “-” nếu chúng có hướng ngược nhau. Khi đó chúng ta có thể viết lại đẳng thức cuối cùng dưới dạng ký hiệu mới như sau:
$$\{\overrightarrow{AA_1} \cdot \overrightarrow{AA_2}\} = \{\overrightarrow{AA_5} \cdot \overrightarrow{AA_6}\} =
\{A_5A \cdot A_6A\}.$$ (10)

Tương tự như vậy
$$\{\overrightarrow{BA_4} \cdot \overrightarrow{BA_3}\} = \{\overrightarrow{A_1B} \cdot \overrightarrow{A_2B}\},$$ (11)
$$\{\overrightarrow{CA_5} \cdot \overrightarrow{CA_6}\} = \{\overrightarrow{A_4C} \cdot \overrightarrow{A_3C}\}.$$ (12)

Các đẳng thức biến đổi (7) - (9) có tính đến các đẳng thức (10 - (12) và thực tế là, theo định nghĩa, chẳng hạn, $$\frac{\overrightarrow{BA_4}}{\overrightarrow{A_4C}} \cdot \frac{\overrightarrow{BA_3}}{\overrightarrow{A_3C}} =
\frac{\overrightarrow{BA_4} \cdot \overrightarrow{BA_3}}{\overrightarrow{A_4C} \cdot \overrightarrow{A_3C}}$$, chúng tôi nhận được $$\frac{\overrightarrow{AK}}{\overrightarrow{KB}} \times
\times \left\{\frac{\overrightarrow{BM}}{\overrightarrow{MC}}\right\} \cdot \frac{\overrightarrow{CL}}{\overrightarrow{LA}} = -1$$, mà theo định lý

Menelaus có nghĩa là các điểm $K, L$ và $M$ cùng thuộc một đường thẳng.

Trường hợp đường $A_1A_2, A_3A_4$ và $A_5A_6$ cắt nhau tại một điểm (và do đó không tạo thành tam giác $ABC$), bạn có thể tự phân tích.

Hình 10–12 cho thấy ba trường hợp khác nhau về vị trí của các điểm $A_1, ..., A_6$. Tất nhiên, họ không cạn kiệt mọi khả năng.

Và kết luận - một hậu quả nữa.

Phát biểu 5. Cho hai tiếp tuyến $AM$ và $AN$ với đường tròn và hai phần được vẽ từ điểm $A$, đưa ra ngoài đường tròn, và gọi $P$ và $Q$ là giao điểm của đường tròn với phần đầu tiên và các điểm $K$

⟦folio 29⟧

u L - từ thứ hai. Khi đó các đường thẳng PK, QL và MN cắt nhau tại một điểm.

Chứng minh (Hình 13).
Hãy áp dụng định lý Ceva cho tam giác KLM. Lưu ý rằng các đường thẳng PK, QL và MN cắt nhau tại một điểm nếu thỏa mãn đẳng thức

$$\frac{\sin \widehat{LMN}}{\sin \widehat{NMK}} \cdot \frac{\sin \widehat{KLQ}}{\sin \widehat{QLM}} \cdot \frac{\sin \widehat{MKP}}{\sin \widehat{PKL}} = 1. \quad (13)$$

Tất cả các góc xuất hiện trong biểu thức cuối cùng đều nội tiếp trong một đường tròn nhất định; sin của các góc này tỷ lệ thuận với độ dài của dây cung mà chúng phụ thuộc (ví dụ: sin $\widehat{LMN} = \frac{|LN|}{2R}$, trong đó R là bán kính của hình tròn). Do đó, đẳng thức (13) tương đương với đẳng thức sau:

$$\frac{|LN|}{|NK|} \cdot \frac{|KQ|}{|QM|} \cdot \frac{|MP|}{|PL|} = 1. \quad (13')$$

Hãy chứng minh rằng (13') thực sự thỏa mãn. Từ sự đồng dạng của các tam giác AMP và AMQ, ta thu được $\frac{|PM|}{|MQ|} = \frac{|AM|}{|AQ|}$.

Từ sự đồng dạng của các tam giác APL và AQK $$\frac{|KQ|}{|PL|} = \frac{|AQ|}{|AL|},$$ và cuối cùng, từ sự đồng dạng của các tam giác ALN và ANK $$\frac{|LN|}{|NK|} = \frac{|AL|}{|AM|}.$$ Nhân ba đẳng thức cuối, ta thu được (13).

Lưu ý: Từ Câu 5, với sự trợ giúp của thước kẻ, một tiếp tuyến có thể được vẽ qua một điểm cho trước bên ngoài đường tròn. Phương pháp xây dựng được thể hiện trong Hình 14.

Bài tập
1. Chứng minh rằng: a) Các đường phân giác của các góc ngoài của một tam giác cắt các đường thẳng,

Cơm. 10.

Cơm. 11.

Cơm. 12.

Cơm. 13.

Cơm. 14.
