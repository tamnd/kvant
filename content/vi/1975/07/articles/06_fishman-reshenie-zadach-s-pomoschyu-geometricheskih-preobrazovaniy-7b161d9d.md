---
id: 1975-7-fishman-reshenie-zadach-s-pomoschyu-geometricheskih-preobrazovaniy-7b161d9d
issue: kvant_1975_7
year: 1975
number: "7"
title: Lời giải bài toán sử dụng các phép biến đổi hình học
authors:
  - Фишман В. М.
rubric: osnovnye-stati
page_first: 32
page_last: 37
page_labels: 30-35
tag: ZH4I
lang: vi
source: kvant_digital
extraction: vision
content_sha256: f4c703454078b49fc73b95b19f9c4c1fdcafe0334c139bc983ee85138c59a6b2
prompt_sha256: draft-1
translated_from: content/ru/1975/07/articles/06_fishman-reshenie-zadach-s-pomoschyu-geometricheskih-preobrazovaniy-7b161d9d.md
source_content_sha256: a1f0baee69c4a92892566bb3ee1db014cb44e54991a0be15baf303ad701cbadf
translation_model: draft
translation_run: vi-draft-2026-10-31
translation_quality: draft
---

⟦folio 30⟧

GIẢI QUYẾT VẤN ĐỀ VỚI SỰ GIÚP ĐỠ
HÌNH HỌC
CHUYỂN ĐỔI

Trong môn học hình học ở trường, các em thường gặp nhiều phép biến đổi hình học của mặt phẳng: phép tịnh tiến parapel, phép đối xứng, phép quay, phép biến đổi tương tự. Tầm quan trọng của các khái niệm này được chứng minh bằng việc khi chứng minh sự đồng dạng của các hình, người ta sử dụng các phép biến đổi hình học - chuyển vị. Tuy nhiên, các phép biến đổi hình học không chỉ được tìm thấy trong việc xây dựng các định nghĩa và trong việc chứng minh các định lý của trường phái; chúng được sử dụng cho lời giải nhiều loại hình học bài toán. Trong trường hợp này, các phép biến đổi không nhất thiết phải xuất hiện trực tiếp trong các công thức bài toán: thường xảy ra trường hợp công thức bài toán có bản chất hoàn toàn “tĩnh” và đơn giản và thanh lịch nhất lời giải hóa ra là “động”, về cơ bản sử dụng các phép biến đổi hình học khác nhau của các hình đã cho. Trong ghi chú này, chúng tôi sẽ thảo luận về cách bạn có thể học cách xem “động lực học” bên trong của phép đo phẳng bài toán.

Hiểu các phép biến đổi hình học

Hãy bắt đầu với định nghĩa về sự dịch chuyển.

Về giới hạn 1. Độ dịch chuyển là ánh xạ của một mặt phẳng lên chính nó, trong đó khoảng cách giữa các điểm được giữ nguyên.

Ta chứng minh định lý sau về chuyển vị:

Định lý 1. Có một và chỉ một chuyển động lấy các đỉnh A, B, C của tiền tố ABC chưa biểu diễn tương ứng với các đỉnh A1, B1, C1 của tiền thân tắc nghẽn A1B1C1 của nó.

Bằng chứng. Sự tồn tại của sự dịch chuyển như vậy xuất phát từ thực tế là các tam giác ABC và A1B1C1 bị tắc nghẽn. Hãy chứng minh rằng nó là duy nhất.

Gọi F là độ dịch chuyển nào đó của mặt phẳng sao cho F(A) = A1, F(B) = B1, F(C) = C1, và gọi X là một điểm tùy ý của mặt phẳng. Khi đó điểm F(X) phải ở các khoảng cách |XA|, |XB|, |XC| lần lượt từ các điểm A1, B1 và ​​C1.

Nhưng ba đường tròn có tâm tại các điểm A1, B1, C1 không nằm trên cùng một đường thẳng có nhiều nhất một điểm chung; Điều này có nghĩa là điểm F(X) được xác định duy nhất.

Bạn có quen thuộc với các loại chuyển động sau:

1. Chuyển giao song song.
(Sự truyền song song được xác định bằng cách xác định một điểm và ảnh của nó).

2. Bằng cách quay.
(Một góc quay được xác định bằng cách xác định tâm O, góc quay α và hướng quay; góc quay α được coi là nằm trong giới hạn 0° ≤ α ≤ 180°. Nhưng nếu bạn chọn bất kỳ hướng quay nào là dương và hướng ngược lại được coi là âm, thì phép quay hoàn toàn được xác định bằng cách xác định tâm và góc quay α của nó; góc quay được coi là một đỉnh có hướng, trị số của nó có thể là dương hoặc âm. Xoay với tâm O theo một góc α biểu thị

⟦folio 31⟧

$R_0^\alpha$. Bây giờ, bất kỳ góc quay nào cũng có thể được chỉ định bằng cách chỉ định tâm của nó và góc xoay $\alpha$, nằm trong $-180^\circ \leq \alpha \leq 180^\circ$. Nếu $\beta = \alpha + 360^\circ$, $n$, trong đó $n$ là số nguyên và $-180^\circ \leq \alpha \leq 180^\circ$ thì phép quay theo góc $\beta$ được gọi là phép quay $R^\alpha$.

3. Đối xứng trục.

(Đối xứng trục được xác định bằng cách xác định trục đối xứng - đường thẳng $l$.)

Cách dịch đơn giản nhất là ánh xạ nhận dạng của mặt phẳng, ánh xạ bất kỳ điểm nào $X$ lên chính nó; nó được biểu thị bằng chữ cái $E$, sau đó là $E(X) = X$. Ánh xạ nhận dạng được coi là một phép quay qua góc 0 quanh tâm $O$. Theo cách tương tự, chúng ta có thể coi ánh xạ giống hệt như một bản dịch song song về khoảng cách bằng 0. Ánh xạ nhận dạng là chuyển động duy nhất vừa xoay vừa dịch.

Đối với bất kỳ tâm $O$ nào, phép quay $180^\circ$ theo cả hai hướng trùng khớp và là đối xứng tâm (so với tâm quay $O$).

Có thể chứng minh rằng bất kỳ chuyển vị nào cũng là chuyển động tịnh tiến hoặc chuyển động quay song song hoặc là thành phần của chuyển động tịnh tiến hoặc chuyển động quay song song với một số đối xứng trục. Khái niệm về thành phần của hai phép biến đổi hình học sẽ rất quan trọng đối với chúng ta sau này, vì vậy chúng ta sẽ tìm hiểu chi tiết hơn về nó.

Đặt hai bản đồ đã cho $F$ và $G$ của một tập hợp nhất định $M$ lên chính nó. Tạo chúng một cách tuần tự, chúng ta thu được một ánh xạ mới $H$, ánh xạ $x \in M$ đến $H(x) = G(F(x))$. Ánh xạ mới $H$ này cũng là ánh xạ của tập hợp $M$ lên chính nó. Nó được gọi là thành phần của ánh xạ $F$ và $G$ và được ký hiệu là $G \circ F$.

Từ Định nghĩa 1, suy ra rằng thành phần của hai bản dịch bất kỳ (nghĩa là ánh xạ của mặt phẳng lên chính nó để bảo toàn khoảng cách giữa các điểm) lại là một sự dịch chuyển. Hãy chú ý đến thứ tự ghi: khi biểu thị thành phần $G \circ F$, chúng ta đặt bên phải ký hiệu của màn hình được thực hiện đầu tiên. Sự thay thế này rất có ý nghĩa; chúng ta sẽ thấy rằng thao tác thành phần nói chung là không thay đổi

phong phú - có các ánh xạ $F$ và $G$ cho $G \circ F \neq F \circ G$.

Bây giờ chúng ta hãy thử tìm hiểu xem thành phần của các ánh xạ mà chúng ta đã biết - chuyển vị - trong các trường hợp cụ thể là như thế nào.

Điểm đặc biệt trong thành phần của hai bản dịch song song là sự dịch chuyển - đây là một trong những lý do tại sao thành phần của các bản dịch song song (vectơ) được gọi là phép cộng của chúng; thành phần của ánh xạ không được gọi là phép cộng).

Trường hợp bố cục hai lượt thú vị hơn; Hãy chuyển nó cho anh ấy. Chúng ta sẽ cần các định nghĩa sau: điểm $X_0$ của tập hợp $M$ được gọi là điểm cố định của ánh xạ $G$ của tập hợp $M$ lên chính nó nếu $G(X_0) = X_0$.

Thuộc tính đặc trưng của lượt được mô tả.

Định lý 2. Chuyển vị không đồng nhất là chuyển động quay của một module và một module sữa khi nó có một module cố định duy nhất.

Bằng chứng. Sự cần thiết của điều kiện này là hiển nhiên: điểm cố định duy nhất quay về góc 0 là tâm quay.

Tính đủ Chúng ta xét một chuyển vị nhất định $F$ với một điểm cố định duy nhất $O$. Chúng ta hãy chọn một số điểm $A$, khác với $O$ và xem xét ảnh $B = F(A)$ của nó; điểm $B$ khác với $A$ và nằm trên đường tròn $(O; r)$ có tâm tại điểm $O$ và bán kính $r = |OA|$.

Nếu với bất kỳ điểm $A \widehat{AOB} = 180^\circ$ nào thì $F$ là một đối xứng đối với điểm $O$ và điều kiện đủ được chứng minh. Giả sử bây giờ tồn tại một điểm $A$ sao cho $\widehat{AOB} = \alpha \neq 180^\circ$. Xét điểm $F(B) = F^2(A)$ ($F^2$ là cách viết tắt của thành phần

⟦folio 32⟧

⟦figure⟧
Hình 1.

⟦figure⟧
Hình 2.

$F\circ F$). Vì chuyển động $F$ bảo toàn khoảng cách nên điểm $F(B)$ lại nằm trên đường tròn $(O;r)$ và khoảng cách giữa các điểm $F(B)$ và $B$ bằng khoảng cách giữa các điểm $B$ và $A$. Các điều kiện này được thỏa mãn bởi hai điểm: điểm $A$ và điểm $C$ của đường tròn $(O;r)$ sao cho $B\hat{O}C=\alpha$ (Hình 1). Nhưng nếu $F(B)=A$ thì trung điểm của đoạn $AB$ - điểm $D$ - là điểm cố định của phép biến đổi $F$: $F(D)=D$ (chứng minh!), và điều này mâu thuẫn với thực tế rằng điểm $O$ là điểm cố định duy nhất $F$. Điều này có nghĩa là $F(B)=C$ và chúng tôi đã chứng minh rằng độ dịch chuyển $F$, giống như $R_O^\alpha$, lấy các điểm $O$, $A$ và $B$, không nằm trên cùng một đường thẳng, lần lượt là các điểm $O$, $B$ và $C$. Từ Định lý 1 suy ra $F=R_O^\alpha$. Định lý đã được chứng minh.

Xét các phép quay $R_O^\alpha$ và $R_O^\beta$ có tâm chung $O$. Kết quả của sự tạo thành của chúng là sự quay quanh cùng một tâm $O$ một góc $\alpha+\beta$:
$$R_O^\beta\circ R_O^\alpha=R_O^{\alpha+\beta}.$$

(Để chứng minh đầy đủ công thức này cần phải phân tích một số trường hợp đặc biệt - hãy tự mình thực hiện việc này.)

Vì luôn có $\alpha+\beta=\beta+\alpha$ nên

$$R^\beta\circ R^\alpha=R^{\beta+\alpha}=R^{\alpha+\beta}=R^\alpha\circ R^\beta,$$

và thành phần của các vòng có tâm chung là giao hoán.

Bây giờ có hai lượt $R_{O_1}^{\alpha_1}$ và $R_{O_2}^{\alpha_2}$ với các tâm khác nhau
⟦column⟧
$O_1$ và $O_2$ và các góc $\alpha_1$ và $\alpha_2$ sao cho $\alpha_1$ và $\alpha_2$ cùng dấu (tức là các góc rẽ cùng hướng) và $|\alpha_1+\alpha_2|\neq 360^\circ$. Chúng tôi sẽ chỉ ra rằng trong trường hợp này bố cục $R_{O_2}^{\alpha_2}\circ R_{O_1}^{\alpha_1}$ của chúng là một phép quay qua góc $\alpha_1+\alpha_2$ và chúng tôi sẽ tìm ra tâm của phép quay này.

Để ngắn gọn, chúng ta hãy biểu thị phép quay $R_{O_1}^{\alpha_1}$ bằng $R_1$, phép quay $R_{O_2}^{\alpha_2}$ bằng $R_2$. Chúng ta cần tìm tất cả các điểm dịch chuyển cố định $R_2\circ R_1$.

Giả sử rằng một số điểm của mặt phẳng $A$ là điểm dịch chuyển cố định $R_2R_1$, tức là $R_2(R_1(A))=A$. Biểu thị điểm $R_1(A)$ bằng $B$, chúng ta thu được $R_2(B)=A$ đó. Từ đẳng thức này suy ra rằng điểm $O_2$ cách đều các điểm $A$ và $B$; nhưng vì $B=R_1(A)$, nên điểm $O_1$ cách đều các điểm $A$ và $B$; do đó, các điểm $A$ và $B=R_1(A)$ phải đối xứng với đường thẳng $O_1O_2$ (Hình 2).

Vì $A\hat{O}_1B=\alpha_1$ và các điểm $A$ và $B$ đối xứng với đường thẳng $O_1O_2$ nên điểm $A$ phải nằm trên đường thẳng $l_1$, đi qua điểm $O_1$ và biến đổi khi quay quanh điểm $O_1$ một góc $\alpha_1/2$ thành đường thẳng $O_1O_2$. Mặt khác, vì $B\hat{O}_2A=\alpha_2$ nên điểm $A$ cũng phải nằm trên đường thẳng $l_2$, trong đó đường thẳng $O_1O_2$ đi vào

⟦folio 33⟧

khi quay qua một góc $\alpha_2/2$ quanh điểm $O_2$. Theo giả định $\frac{|\alpha_1 + \alpha_2|}{2} \neq 180^\circ$, điều này có nghĩa là các đường thẳng $l_1$ và $l_2$ không song song, tức là chúng cắt nhau tại một điểm duy nhất - điểm $A$. Vì vậy, điểm $A$ giao điểm của đường $l_1$ và $l_2$ là điểm dịch chuyển cố định duy nhất $R_2 \circ R_1$. Từ Định lý 2, suy ra rằng chuyển vị $R_2 \circ R_1$ là phép quay quanh $A$. Hãy tìm góc quay này.

Để làm điều này, chỉ cần tìm hình ảnh của một điểm tùy ý khác với tâm $A$ bằng cách xoay $R_2 \circ R_1$ xung quanh $A$ là đủ. Cách thuận tiện nhất là lấy điểm $O_1$. Xoay $R_1$ để nó ở đúng vị trí và xoay $R_2$ di chuyển nó đến một điểm $C$ sao cho $|O_2O_1| = |O_2C|$ và $O_1\widehat{O}_2C = \alpha_2$ (Hình 2). Do đó, chuyển động của $R_2 \circ R_1$ là chuyển động quay quanh $A$ một góc $\widehat{O_1AC}$. Hãy tính góc này cho trường hợp $0^\circ < \alpha_1 + \alpha_2 < 360^\circ$ (Hình 2).

$$\widehat{CAO}_2 = O_2\widehat{AO}_1 = 180^\circ - \alpha_1/2 - \alpha_2/2,$$
$$O_1\widehat{AC} = 360^\circ - \widehat{CAO}_2 - O_2\widehat{AO}_1 = \alpha_1 + \alpha_2.$$

(Đối với trường hợp $-360^\circ < \alpha_1 + \alpha_2 < 0^\circ$ nên sử dụng)

Nhiệm vụ 3. Bố cục $R_{02}^{\alpha_2}$. $\circ R_{01}^{\alpha_1}$ của hai lượt $R_{01}^{\alpha_1}$ và $R_{02}^{\alpha_2}$ với các tâm khác nhau $O_1$ và $O_2$ và số phận của các lượt $\alpha_1$ và $\alpha_2$ tối đa hóa rằng $\alpha_1$ và $\alpha_2$ là ký hiệu một vùng $u$ $|\alpha_1 + \alpha_2| < 360^\circ$, là một vòng quay qua góc $\alpha_1 + \alpha_2$. Tâm quay này là điểm chuyển động của các đường thẳng $l_1$ và $l_2$, trong đó $l_1$ là đường thẳng đi qua điểm $O_1$ và biến đổi khi quay quanh điểm $O_1$ một góc $\alpha_1/2$ thành đường thẳng $O_1O_2$, và $l_2$ là đường thẳng tại đó nó chuyển thành đường thẳng $O_1O_2$ khi quay quanh điểm $O_2$ theo góc $\alpha_2/2$.

Lưu ý rằng nếu điều kiện 3 được đáp ứng thì thành phần $R_{01}^{\alpha_1}$.

Hình 3.

$\circ R_{02}^{\alpha_2}$ là phép quay theo góc $\alpha_1 + \alpha_2$ xung quanh $B$, đối xứng với điểm $A$ so với đường thẳng $O_1O_2$. Điều này chứng tỏ rằng thành phần của các vòng có tâm khác nhau không có tính chất giao hoán.

Bài tập 1. Chứng minh rằng tổ hợp của hai phép quay có tâm $O_1$, $O_2$ và các góc quay $\alpha_1$, $\alpha_2$ sao cho $\alpha_1$ và $\alpha_2$ là dấu một miền $u$ $|\alpha_1 + \alpha_2| = 360^\circ$ là dịch song song. Xây dựng bản dịch song song này cho $O_1$, $O_2$, $\alpha_1$. Thành phần của hai vòng quay như vậy có tính chất giao hoán không? (Gợi ý: bố cục khoảng cách đối xứng với hai điểm khác nhau.)

Nhiệm vụ 2. Tìm bố cục:
a) hai trục đối xứng;
b) tịnh tiến và quay song song.

Khám phá khả năng vận chuyển của thành phần của các loại chuyển động khác nhau.

Bài tập

Bây giờ chúng ta hãy thử áp dụng các kết quả thu được cho lời giải của một số vật thể phẳng bài toán.

Trước tiên chúng ta hãy xem xét điều này bài toán (nó sẽ giúp chúng ta sau này):

Trên mặt phẳng có hai hình vuông $A_1B_1A_2C_1$ và $A_2B_2A_3C_2$ có chung một đỉnh $A_2$ (xem Hình 3). Đặt $O_1$ và $O_2$ là tâm của các hình vuông, $B$ là trung điểm của đoạn $B_1B_2$, $C$ là trung điểm của đoạn $C_1C_2$. Chứng minh rằng $O_1BO_2C$ là hình vuông.

Tất nhiên, bài toán này có thể được giải mà không cần các phép biến đổi hình học, bằng cách tạo ra các cách xây dựng bổ sung và xem xét các tam giác dựng không ctor. Tuy nhiên, bài toán nói gì về "đúng"

⟦folio 34⟧

hình - hình vuông - gợi ý ý tưởng cố gắng áp dụng các phép biến đổi hình học cho lời giải của nó.

Lưu ý rằng xoay 90° quanh điểm $O_1$ sẽ di chuyển điểm $B_1$ đến điểm $A_2$ và xoay 90° quanh điểm $O_2$ sẽ di chuyển điểm $A_2$ tới điểm $B_2$. Theo Định lý 3, thành phần của hai phép quay này là phép quay 180°, tức là sự đối xứng tâm quanh một điểm nào đó. Vì kết quả của việc thực hiện tuần tự hai lượt này, điểm $B_1$ sẽ chuyển thành điểm $B_2$, nên bố cục của các lượt được xem xét sẽ đối xứng với một đoạn nhất định $B_1B_2$ - điểm $B$. Mặt khác, từ Định lý 3, suy ra rằng tâm hợp thành của hai phép quay này nằm ở giao điểm của hai đường thẳng lần lượt đi qua các điểm $O_1$ và $O_2$, hợp với đường thẳng $O_1O_2$ một góc 45°. Điều này có nghĩa là các đường thẳng này cắt nhau tại điểm $B$ và tam giác $O_1BO_2$ là tam giác đều và vuông ở đỉnh $B$. Tương tự, người ta chứng minh tam giác $O_1CO_2$ là tam giác đều, vuông tại đỉnh $C$. Sự kết hợp của hai tam giác này tạo thành bình phương $O_1BO_2C$, đó là điều chúng ta cần chứng minh.

Hai bài toán tiếp theo là bài toán M291 và M297 từ “Vấn đề «Kvant»” (xem «Kvant», 1974, số 911, 12). Lời giải trong số bài toán này, với sự trợ giúp của các phép biến đổi hình học, hóa ra không chỉ đơn giản và thanh lịch hơn mà còn có ý nghĩa hơn so với lời giải truyền thống, dựa trên các kỹ thuật nhân tạo khác nhau.

M291. Trên các cạnh $A_2A_3$, $A_3A_1$, $A_1A_2$ của tam giác $A_1A_2A_3$ các hình vuông có tâm $O_1$, $O_2$, $O_3$ nằm bên ngoài tam giác được dựng (Hình 4). Chứng minh rằng:

a) các đoạn $O_1O_2$ và $A_3O_3$ có chiều dài bằng nhau và vuông góc với nhau;
b) trung điểm của các đoạn $A_3A_1$, $O_1O_2$, $A_3A_2$ và $A_3O_3$ là các đỉnh của hình vuông;

Hình 4.

c) diện tích hình vuông này nhỏ hơn 8 lần diện tích hình vuông có tâm $O_3$.

Chúng ta hãy biểu thị bằng $B_1$ điểm giữa của đoạn $A_3A_2$ và $B_2$ là điểm giữa của đoạn $A_1A_3$. Áp dụng kết quả của bài toán trước đó cho các hình vuông có tâm $O_2$ và $O_3$, chúng ta thu được rằng tam giác $O_2B_1O_3$ là tam giác đều và có một góc vuông ở đỉnh $B_1$. Do đó, phép quay 90° quanh điểm $B_1$ sẽ biến đoạn $A_3O_3$ thành đoạn $O_1O_2$, điều này chứng tỏ câu a). Vì phép quay 90° quanh điểm $B_2$ lấy điểm $O_2$ đến điểm $A_3$, nên, áp dụng Định lý 3 cho thành phần của hai phép quay này (xung quanh các điểm $B_1$ và $B_2$), chúng ta thu được, như trong bài toán trước đó, rằng tam giác $B_2C_1B_1$, trong đó $C_1$ là điểm giữa của đoạn $A_3O_3$, là cạnh bằng một góc vuông ở đỉnh $C_1$. Tương tự, tam giác $B_2C_2B_1$, trong đó $C_2$ là trung điểm của đoạn $O_1O_2$, là tam giác đều và vuông tại đỉnh $C_2$, và khẳng định b) đã được chứng minh. Tuyên bố c) xuất phát từ thực tế là đường chéo $B_2B_1$ của hình vuông thu được là đường giữa của tam giác $A_1A_2A_3$ bằng một nửa kích thước cạnh $A_1A_2$ của hình vuông có tâm $O_3$.

M297. Có 12 điểm cho trên mặt phẳng, là các đỉnh của bốn hình vuông $A_1B_1A_2C_1$, $A_2C_2A_3B_2$, $A_3B_3A_4C_3$ và $A_4C_4A_1B_4$ (các đỉnh của mỗi hình vuông được liệt kê theo chiều kim đồng hồ, Hình 5). Chứng minh

⟦folio 35⟧

rằng $B_1B_2B_3B_4$ và $C_1C_2C_3C_4$ là các hình bình hành nối tiếp nhau, một trong số đó thu được từ hình bình hành kia bằng cách quay $90^\circ$ (các hình bình hành này có thể suy biến: các đỉnh của một trong hai hình bình hành trong trường hợp này nằm trên cùng một đường thẳng).

Gọi $D_1$ là trung điểm của đoạn $A_1A_3$, $D_2$ là trung điểm của đoạn $A_2A_4$.

Xem xét thành phần của hai phép quay tương ứng theo các góc $90^\circ$ (với tâm ở các đỉnh tương ứng của các hình vuông đã cho, xem Hình 5), như trước đây, chúng ta thu được rằng các tam giác $B_1D_1C_2$, $B_3D_1C_4$, $B_4D_1C_3$ và $B_2D_1C_1$ là các tam giác đều có một góc vuông ở đỉnh $D_1$.

Do đó, phép quay một góc $90^\circ$ quanh điểm $D_1$ sẽ biến tứ giác $B_1B_4B_3B_2$ thành tứ giác $C_2C_3C_4C_1$, điều này chứng tỏ chúng bằng nhau (đồng thời ta thu được rằng các đoạn $B_1B_3$ và $C_2C_4$ có chiều dài bằng nhau và vuông góc với nhau, đây là dạng tổng quát của câu a) bài toán M291 cho trường hợp một tứ giác tùy ý $A_1A_2A_3A_4$).

Chẳng hạn, vẫn còn phải chứng minh rằng tứ giác $B_1B_2B_3B_4$ là hình bình hành. Để làm điều này, hãy lưu ý rằng tất cả các hình tam giác $C_2D_2B_3$, $C_4D_2B_1$, $C_3D_2B_2$, $C_1D_2B_4$ đều đều có một góc vuông ở đỉnh

Hình 5.

xe buýt $D_2$. Điều này có nghĩa là phép quay một góc $90^\circ$ quanh điểm $D_2$ sẽ biến tứ giác $C_2C_3C_4C_1$ thành tứ giác $B_3B_2B_1B_4$. Thành phần của hai phép quay quanh điểm $D_1$ và $D_2$ theo các góc $90^\circ$ là một đối xứng trung tâm đối với một số $O_1$ và ánh xạ tứ giác $B_1B_4B_3B_2$ lên chính nó sao cho các đỉnh $B_1$ và $B_3$, $B_2$ và $B_4$ thay đổi ở một số điểm những nơi. Từ đó suy ra rằng tứ giác $B_1B_2B_3B_4$ đối xứng tâm, tức là hình bình hành, và đây là điều cần phải chứng minh.

Áp dụng Định lý 3 vào thành phần phép quay theo góc $90^\circ$ quanh điểm $D_1$ và $D_2$, ta cũng thu được tâm $O_1$ và $O_2$ của các hình bình hành $B_1B_2B_3B_4$ và $C_1C_2C_3C_4$, và trung điểm $D_1$ và $D_2$ của các đường chéo của tứ giác $A_1A_2A_3A_4$ là các đỉnh của hình vuông.

Câu này là sự tổng quát của câu b) bài toán M291 đối với trường hợp tứ giác tùy ý $A_1A_2A_3A_4$.

Bây giờ chứng minh rằng với điều kiện bài toán M297, trung điểm của dãy tứ giác $B_1C_2B_3C_4$ và $C_1B_4C_3B_2$ là các đỉnh của hình vuông. Tâm của các hình vuông này và hình vuông $D_1O_1D_2O_2$ trùng nhau và nằm ở tâm bãi của tứ giác $A_1A_2A_3A_4$.

Và cuối cùng, bài toán, được đề xuất vào năm 1961 tại loại thứ hai của Olympic Toán học XXIV Moscow. Sau đó, bài toán này chỉ được giải bởi hai người tham gia olimpida, cả hai đều sử dụng các phép biến đổi hình học. Telery, khi bạn đã thành thạo phép biến đổi hình học kỹ thuật, nó lời giải sẽ không gây nhiều khó khăn cho bạn.

Bài toán 3. Các điểm $A$ và $B$ chuyển động đều và có vận tốc góc bằng nhau dọc theo đường tròn $O_1$ và $O_2$ tương ứng (mũi tên công nghiệp). Chứng minh rằng đỉnh $C$ của tam giác đều $ABC$ cũng nhân đôi đều dọc theo một đường tròn nhất định.
