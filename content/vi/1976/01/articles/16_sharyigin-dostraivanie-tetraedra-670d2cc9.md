---
id: 1976-1-sharyigin-dostraivanie-tetraedra-670d2cc9
issue: kvant_1976_1
year: 1976
number: "1"
title: Hoàn thành tứ diện
authors:
  - Шарыгин И. Ф.
rubric: praktikum-abiturienta
rubric_sub: Практикум абитуриента
page_first: 63
page_last: 66
page_labels: 61-64
tag: HEZN
lang: vi
source: kvant_digital
extraction: publisher
content_sha256: 3fe65d22208ea01325bb26859c51bc385c1ef17dc4bed9b2bbdd70db807399b3
prompt_sha256: draft-1
translated_from: content/ru/1976/01/articles/16_sharyigin-dostraivanie-tetraedra-670d2cc9.md
source_content_sha256: bca0e7262a55b22b39b7beba3bfc2f5b92489d7c3ec4d129591dd4a0543c1796
translation_model: draft
translation_run: vi-draft-2026-10-31
translation_quality: draft
---

## Hoàn thành tứ diện

Một trong những kỹ thuật hay có thể được sử dụng với lời giải hình học bài toán là thay thế hình hình học đang được nghiên cứu bằng hình khác, theo một nghĩa nào đó, thuận tiện hơn. Vì vậy, ví dụ, nếu trong điều kiện bài toán có ​​một tam giác trong đó đường trung tuyến được vẽ, thì việc hoàn thành tam giác này thành hình bình hành thường rất hữu ích, kéo dài đường trung tuyến đến một khoảng bằng chính nó. Bài viết này thảo luận về một số bài toán về một hình chóp tam giác - một khối tứ diện - mà hóa ra là có thể giải được bằng cách xây dựng khối tứ diện này thành một khối đa diện khác (thường là một hình bình hành).

Cách đầu tiên để hoàn thiện kim tự tháp thành hình bình hành được thể hiện trong Hình 1. Đây $AA_1BD$ là kim tự tháp này và các mặt phẳng của các mặt $DCC_1D_1$, $CBB_1C_1$ và $A_1B_1C_1D_1$ của hình bình hành đi qua một đỉnh của kim tự tháp và song song với mặt của hình chóp đối diện với đỉnh này.

Bài toán 1. (Mục a) bài toán đã được đưa ra trong kỳ thi tuyển sinh tại Khoa Cơ học và Toán học của Đại học Tổng hợp Moscow.) *Cho một hình chóp tam giác $AA_1BD$, trong đó các cạnh $AA_1$, $AB$ và $AD$ vuông góc với nhau và độ dài của chúng lần lượt bằng nhau $a$, $b$, $c$.*

1. *Chứng minh rằng đỉnh $A$ của hình chóp, giao điểm của các đường trung tuyến của mặt $A_1BD$ và tâm của hình cầu ngoại tiếp cùng nằm trên một đường thẳng.*
2. *Tìm bán kính của hình cầu ngoại tiếp kim tự tháp này.*

Chúng ta hãy xây dựng kim tự tháp $AA_1BD$ thành một hình bình hành (hình chữ nhật!), như trong Hình 1. Sau đó, quả bóng bao quanh kim tự tháp này đồng thời là một quả bóng ngoại tiếp cho toàn bộ hình bình hành. Bán kính của quả bóng này bằng một nửa đường chéo của hình bình hành, cụ thể là $\dfrac12\sqrt{a^2+b^2+c^2}$, đây là đáp số ở điểm b).

⟦figure⟧
Hình 1

Để chứng minh khẳng định ở điểm a), hãy xem xét hình chữ nhật $AA_1C_1C$ (chúng tôi khuyên bạn nên tạo một bản vẽ riêng cho nó). Tâm $O$ của quả bóng nằm trên đường chéo $AC_1$, đường trung tuyến $A_1O_1$ của tam giác $A_1BD$ cắt $AC_1$ tại điểm $M$ và nếu chúng ta chứng minh rằng $\dfrac{|A_1M|}{|MO_1|}=2$ thì điều này có nghĩa rằng $M$ là giao điểm của các đường trung tuyến của tam giác $A_1BD$; Như vậy ta sẽ chứng minh khẳng định ở điểm a). Từ sự giống nhau của tam giác $A_1C_1M$ và $AO_1M$ suy ra:
$$
\dfrac{|A_1M|}{|MO_1|}=\dfrac{|A_1C_1|}{|AO_1|}=2,
$$
Q.E.D.

Một cách phổ biến khác để xây dựng một tứ diện thành một hình bình hành như sau. Chúng ta vẽ một mặt phẳng đi qua mỗi cạnh của tứ diện song song với cạnh đối diện. Những mặt phẳng này sẽ giới hạn một hình bình hành nhất định (Hình 2), các đường chéo của các mặt của nó sẽ là các cạnh của tứ diện ban đầu.

⟦figure⟧
Hình 2

Một lời khuyên thực tế nhỏ: sẽ thuận tiện hơn khi bắt đầu vẽ bằng hình ảnh một đường ống song song.

Bài toán 2. *Tìm bán kính của một quả bóng chạm vào tất cả các cạnh của một tứ diện đều có chiều dài cạnh là $a$.*

Như có thể dễ dàng nhận thấy trong Hình 2, hình bình hành được xây dựng theo cách được mô tả sẽ là một khối lập phương có cạnh $\dfrac a{\sqrt2}$; quả bóng được ghi trong khối này sẽ là quả bóng mong muốn. Đáp số: $\dfrac a{2\sqrt2}$.

Phương pháp đầu tiên được đề xuất để hoàn thiện một tứ diện thành một hình bình hành là thuận tiện khi các góc phẳng được cho tại một trong các đỉnh của tứ diện (đặc biệt nếu chúng đều thẳng), phương pháp thứ hai được sử dụng trong các bài toán xuất hiện các cạnh cắt nhau của tứ diện.

Bài toán 3. *Độ dài của hai cạnh giao nhau của tứ diện là $a$, hai cạnh giao nhau còn lại là $b$ và hai cạnh còn lại là $c$. Tìm khoảng cách giữa tâm của một quả cầu nội tiếp trong một tứ diện và tâm của một quả cầu chạm vào một trong các mặt của tứ diện đó và phần kéo dài của các mặt còn lại.*

Trong Hình 3, $ABCD$ là một tứ diện cho trước và hình bình hành bị giới hạn bởi các mặt phẳng đi qua các cạnh của tứ diện song song với các cạnh đối diện. Vì các đường chéo của mỗi mặt bằng các cạnh đối diện của tứ diện, bằng nhau theo điều kiện, nên tất cả các mặt của hình bình hành đều là hình chữ nhật và bản thân hình bình hành đó là hình chữ nhật.

⟦figure⟧
Hình 3

Tâm của quả bóng nội tiếp trong tứ diện $ABCD$ trùng với giao điểm của các đường chéo của hình bình hành (chứng minh!), và tâm của quả bóng chạm vào mặt $DCB$ của tứ diện (từ kết quả sau đây cho thấy rằng đáp số không phụ thuộc vào việc chọn mặt) và phần kéo dài của các mặt còn lại của nó trùng với đỉnh $L$ của song song (nó cách đều các mặt $DCB$ và $ACD$ - để chứng minh, hãy xem xét kim tự tháp $B'LCD$, trong đó $|B'L|=|LB|$, bằng kim tự tháp $BLCD$; các điểm $A$, $D$, $B'$ và $C$ nằm trong cùng một mặt phẳng; $L$ cách đều các mặt phẳng $DCB$ và $ACB$, $DCB$ và $ADB$).

Điều này có nghĩa là khoảng cách được đề cập trong điều kiện bài toán bằng một nửa chiều dài đường chéo của hình bình hành. Chúng ta hãy biểu thị bằng $x$, $y$, $z$ độ dài của các cạnh của hình bình hành (xem Hình 3). Sử dụng định lý Pythagore, chúng ta thu được hệ gồm ba phương trình:
$$
\left\{\begin{array}{l}
x^2+y^2=a^2,\\
x^2+z^2=b^2,\\
y^2+z^2=c^2,
\end{array}\right.
$$
thêm vào đó, chúng tôi thấy rằng $$
\dfrac{|AL|}2=\dfrac12\sqrt{x^2+y^2+z^2}=\dfrac12\sqrt{\dfrac{a^2+b^2+c^2}2}.
$$

Bài toán 4. *Phần tứ diện bởi một mặt phẳng song song với hai cạnh giao nhau của nó và cách đều các cạnh này có diện tích $S$. Khoảng cách giữa các cạnh giao nhau này của tứ diện là $h$. Tìm thể tích của tứ diện.*

⟦figure⟧
Hình 4

Cho $ABCDA_1B_1C_1D_1$ là một hình bình hành được giới hạn bởi các mặt phẳng đi qua các cạnh của tứ diện song song với các cạnh đối diện (Hình 4). Khi đó thể tích của khối tứ diện $A_1BC_1D$ bằng thể tích của hình bình hành trừ đi thể tích của bốn hình chóp tam giác (một trong số chúng $A_1ABD$), thể tích của mỗi hình chóp bằng $\dfrac16$ thể tích của hình bình hành (tại sao?). Vì vậy, $V_{\text{тетр}}=\dfrac13V_{\text{пар}}$. Đặt các cạnh giao nhau được đề cập trong điều kiện là $A_1C_1$ và $BD$, và $KLMN$ là phần của hình bình hành được tạo bởi mặt phẳng đi qua các trung điểm $AA_1$, $BB_1$, $CC_1$ và $DD_1$. Khi đó các đỉnh của phần được đề cập trong điều kiện sẽ là trung điểm của các cạnh của hình bình hành $KLMN$. Do đó, diện tích hình bình hành $KLMN$ bằng $2S$ và bằng diện tích đáy $ABCD$ của hình bình hành. Bây giờ chúng ta hãy tìm thể tích của hình bình hành và tứ diện:
$$
V_{\text{тетр}}=\dfrac13V_{\text{пар}}=\dfrac23Sh.
$$

Sử dụng bài toán vừa giải, không khó để chứng minh tính đúng đắn của *công thức Simpson*, được dùng để tính thể tích của khối đa diện thuộc loại đặc biệt.

Cho một khối đa diện, tất cả các đỉnh của nó nằm trên hai mặt phẳng song song cách nhau một khoảng $h$. Gọi $S_1$ là diện tích của một mặt nằm trong một mặt phẳng, $S_2$ diện tích của một mặt nằm trong mặt phẳng thứ hai và $S_{\text{ср}}$ là diện tích mặt cắt ngang của một khối đa diện bởi một mặt phẳng nằm cách mỗi mặt phẳng này một khoảng $\dfrac h2$. Khi đó công thức tính thể tích của khối đa diện là đúng:
$$
V=\dfrac h6(S_1+S_2+4S_{\text{ср}}).
$$

Để chứng minh điều này, hãy kiểm tra xem công thức này có đúng không nếu khối đa diện là tứ diện, sau đó chia một khối đa diện tùy ý, các đỉnh của chúng nằm trên hai mặt phẳng song song, thành tứ diện có các đỉnh nằm trong cùng một mặt phẳng: diện tích các mặt của các khối tứ diện nằm trong một mặt phẳng sẽ có tổng bằng $S_1$, các diện tích nằm trong mặt phẳng thứ hai sẽ có tổng bằng $S_2$ và tổng diện tích các mặt cắt trung bình của tứ diện bằng $S_{\text{ср}}$ của khối đa diện.

Để kết luận, chúng tôi đưa ra một ví dụ bài toán, trong đó việc hoàn thành khối tứ diện không phải thành hình song song mà thành hình lăng trụ tam giác sẽ thuận tiện hơn.

Bài toán 5. *Trong một tứ diện, diện tích của hai mặt là $S_1$ và $S_2$, góc nhị diện giữa chúng là $\alpha$, diện tích của hai mặt còn lại là $Q_1$ và $Q_2$, góc giữa chúng là $\beta$. Chứng minh rằng*
$$
S_1^2+S_2^2-2S_1S_2\cos\alpha=Q_1^2+Q_2^2-2Q_1Q_2\cos\beta.
$$

⟦figure⟧
Hình 5

Trước tiên chúng ta hãy chứng minh rằng nếu diện tích một mặt của hình lăng trụ tam giác là $S$ thì hai mặt còn lại có diện tích $S_1$ và $S_2$, và góc nhị diện giữa chúng là $\alpha$, thì $$
S_1^2+S_2^2-2S_1S_2\cos\alpha=S^2.
$$

Trên thực tế, giả sử mặt phẳng $ABC$ (Hình 5) vuông góc với các cạnh bên của lăng kính, $\angle BAC=\alpha$. Chúng ta hãy viết định lý cosin cho tam giác $ABC$
$$
|BC|^2=|AB|^2+|AC|^2-2|AB|\cdot|AC|\cos\alpha.
$$
Vẫn còn nhân đẳng thức cuối cùng với $l^2$, trong đó $l$ là chiều dài của cạnh bên của lăng kính.

Bây giờ chúng ta chuyển sang lời giải bài toán 5. Giả sử $ABCD$ là tứ diện đã cho, $S_{\triangle ABD}=S_1$, $S_{\triangle ADC}=S_2$, $S_{\triangle ABC}=Q_1$, $S_{\triangle DBC}=Q_2$, góc nhị diện ở cạnh $AD$ là $\alpha$, và ở cạnh $BC$ - $\beta$. Chúng ta hãy xem xét một hình lăng trụ tam giác có đáy $ABC$, một trong các cạnh bên của nó là $AD$ (Hình 6). Ta hãy biểu thị bằng $S$ diện tích hình bình hành $BB_1C_1C$, thì theo công thức ta vừa chứng minh
$$
4S_1^2+4S_2^2-8S_1S_1\cos\alpha=S^2,
$$
Hơn nữa, $S$ có thể được biểu thị dễ dàng thông qua độ dài của các cạnh $BC$ và $AD$ và góc $\phi$ giữa chúng: $S=|AD|\cdot|BC|\sin\phi$.

⟦figure⟧
Hình 6

Nếu chúng ta xem xét một hình lăng trụ tam giác khác có đáy $ACD$ và cạnh bên $BC$, chúng ta nhận được
$$
4Q_1^2+4Q_2^2-8Q_1Q_2\cos\beta=S^2.
$$
Điều này ngụ ý tuyên bố bài toán 5.

### Bài tập

1. Chứng minh rằng tổng bình phương độ dài các cạnh của một tứ diện bằng 4 lần tổng bình phương khoảng cách giữa trung điểm các cạnh cắt của nó.
2. (MSU, Khoa Vật lý, 1964.) Cho một tứ diện $ABCD$. Chứng minh rằng các cạnh $AD$ và $BC$ của nó vuông góc với nhau khi và chỉ khi đẳng thức đúng
$$
|AB|^2+|DC|^2=|AC|^2+|DB|^2.
$$
3. Độ dài hai cạnh đối diện của tứ diện bằng $a$, độ dài hai cạnh đối diện còn lại bằng $b$, hai cạnh còn lại bằng $c$. Tìm thấy
thể tích của khối tứ diện này;
bán kính của hình cầu ngoại tiếp nó.
4. Độ dài của hai cạnh đối diện của tứ diện là $a$ và $a_1$, góc giữa chúng là $\alpha$, độ dài của hai cạnh còn lại lần lượt là $b$ và $b_1$, góc giữa chúng là $\beta$ và cuối cùng, độ dài của hai cạnh còn lại là $c$ và $c_1$, góc giữa chúng $\gamma$ $\Big(\alpha$, $\beta$, $\gamma\le\dfrac\pi2\Big)$
Chứng minh rằng một trong các số $aa_1\cos\alpha$, $bb_1\cos\beta$, $cc_1\cos\gamma$ bằng tổng của hai số còn lại.
Tìm các góc $\alpha$, $\beta$ và $\gamma$, cho trước $a$, $a_1$, $b$, $b_1$, $c$, $c_1$.
