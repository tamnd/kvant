---
id: 1971-12-novikov-metod-ploschadey-fcba28d8
issue: kvant_1971_12
year: 1971
number: "12"
title: Phương pháp diện tích
authors:
  - Новиков И. Д.
rubric: praktikum-abiturienta
rubric_sub: Практикум абитуриента
page_first: 43
page_last: 48
page_labels: 41-46
tag: E30X
lang: vi
source: kvant_digital
extraction: vision
content_sha256: ff7d2190f5508d60e0eaf636f028e193c4e03779952385d70872a27a288d0ea9
prompt_sha256: draft-1
translated_from: content/ru/1971/12/articles/09_novikov-metod-ploschadey-fcba28d8.md
source_content_sha256: 755d1fe537be7c22e90f01e39efa4ec139f396fb416e17b91ac6188746039d9c
translation_model: draft
translation_run: vi-draft-2026-10-31
translation_quality: draft
---

⟦folio 41⟧

Nghệ thuật giải các bài toán hình học phần nào gợi nhớ đến trioki hoặc lozonist - đôi khi, ngay cả khi biết lời giải bài toán, thật khó hiểu làm sao người ta có thể nghĩ ra nó. Hầu hết mọi hình học có phần khó khăn bài toán đều yêu cầu một cách tiếp cận riêng. Nhưng tôi muốn có một phương pháp chung lời giải, phương pháp này cũng sẽ cho phép tôi “phiêu lưu” lời giải đến cùng mà không cần tính toán một cách rõ ràng.

Thật không may, không có phương pháp phổ quát như vậy. Nhưng có những kỹ thuật được áp dụng cho nhiều vấn đề. Chúng tôi sẽ xem xét một trong số họ.

Hãy bắt đầu với một bài toán rất đơn giản, chúng ta sẽ giải theo hai cách.

Cơm. 1. AC = 2, BC = 3, ⇒ ACD = ⇒ DCB = = 45°.

Bài toán 1. Tìm CD bicsectrix của tam giác vuông ACB có hai chân AC = = 2 và BC = 3 (Hình 1).

Lời giải I. Theo định lý Pythagore AB = √AC² + BC² = √13. Theo tính chất bicsectrix của góc của tam giác bên trong nó

$$\frac{AD}{BD} = \frac{AC}{BC}.$$

Từ đẳng thức AD + DB = √13 ta thu được AD = \frac{2}{5} √13. Tiếp theo, dễ dàng tìm được cosin của góc A:

$$\cos A = \frac{AC}{AB} = \frac{2}{\sqrt{13}}.$$

Vẫn còn áp dụng định lý cosin để xác định cạnh CD của tam giác ACD:

$$CD^2 = AC^2 + AD^2 - 2AC \cdot AD \cos A = \frac{72}{25}, CD = \frac{6}{5} \sqrt{2}.$$

Lời giải II. Hãy tính diện tích tam giác ACB theo nhiều cách khác nhau. Một mặt, S△ACB = \frac{1}{2} AC \cdot BC = 3. Mặt khác,

$$S△ACB = S△ACD + S△DCB = \frac{1}{2} AC \cdot CD \sin 45^\circ + \frac{1}{2} BC \cdot CD \sin 45^\circ = \frac{5 \sqrt{2}}{4} CD.$$

⟦folio 42⟧

Đánh đồng phần của hai biểu thức đã cho cho $S_{\Delta ACB}$, chúng ta thu được $CD = \frac{6}{5}\sqrt{2}$.

lời giải thứ hai rõ ràng là ngắn hơn và đơn giản hơn. Hơn nữa, nó dễ dàng dẫn đến mục tiêu trong một tình huống tổng quát hơn. Để xác minh điều này, hãy tự mình tìm hiểu xem cả hai lời giải này thay đổi như thế nào nếu

Bài tập 2. Tìm phân giác $CD$ của $C$ của tam giác $ACB$ nếu $AC=b$, $BC=a$, $\Rightarrow ACB=\alpha$. (Nói: $CD = \frac{2ab}{a+b}\cos \frac{\alpha}{2}$)

Tuy nhiên, ưu điểm chính của lời giải thứ hai là tính “độc đáo” về mặt tư tưởng của nó. Trong lời giải đầu tiên, một “chuỗi” các phần tử tam giác nhất định được xây dựng: mỗi phần tử của chuỗi này được tính toán dựa trên dữ liệu bài toán và các phần tử khác đã được tìm thấy. Phần tử cuối cùng của chuỗi là số lượng mong muốn (trong trường hợp này là đường phân giác $CD$). Đồng thời, vẫn chưa rõ ngay phần tử nào sẽ cần thiết khi xác định giá trị mong muốn, tức là phần tử nào phải được tính toán trước.

Trong lời giải thứ hai đối với đại lượng cần tìm, chúng ta thu được phương trình bằng cách viết biểu thức tính diện tích tam giác theo các phần tử đã biết và mong muốn của tam giác. Ví dụ này - so sánh các biểu thức khác nhau về diện tích của một hình tam giác - hóa ra rất hiệu quả. Tại sao lại đặc biệt dành cho khu vực này? Thực tế là mặt phẳng của một tam giác được thể hiện khá đơn giản thông qua sự kết hợp khác nhau của các phần tử của tam giác này.

Trước khi đưa ra những ví dụ sau đây, chúng ta hãy nhớ lại những biểu thức quan trọng nhất trong số những biểu thức này. Đầu tiên, hãy thống nhất về ký hiệu. Trong tam giác $ABC$:

$a, b, c$ - các cạnh, góc đối diện $A, B$ và $C$ tương ứng;

$h_a, h_b, h_c$ — chiều cao, $m_a, m_b, m_c$ — đường trung tuyến, $l_a, l_b, l_c$ — đường phân giác tương ứng;

$r$ — bán kính của đường tròn nội tiếp;

$R$—bán kính của đường tròn ngoại tiếp;

$p$ - nửa chu vi;

$S$ là các tam giác phẳng $ABC$.

Cơm. 2. Về tâm của đường tròn nội tiếp.

Các công thức mà chúng tôi sẽ sử dụng được viết bằng ký hiệu này như sau:

$$S = \frac{ah_a}{2},$$

$$S = \frac{ab \sin C}{2},$$

$$S = \frac{a^2 \sin B \sin C}{2 \sin A},$$

$$S = \frac{abc}{4R},$$

$$S = \sqrt{p(p-a)(p-b)(p-c)},$$

$$S = pr.$$

Tất cả những mối quan hệ này đã được biết từ khóa học ở trường, vì vậy chúng tôi sẽ không chứng minh chúng một cách chi tiết mà sẽ chỉ giới hạn trong một vài nhận xét. Để suy ra công thức (3) và (4) từ (2), bạn có thể sử dụng định lý sin:

$$\frac{a}{\sin A} = \frac{b}{\sin B} = \frac{c}{\sin C} = 2R.$$

Công thức (5) (công thức Heron) đôi khi thuận tiện hơn khi sử dụng ở dạng chuyển đổi:

$$S = \frac{1}{4} \times \sqrt{2a^2b^2 + 2a^2c^2 + 2b^2c^2 - a^4 - b^4 - c^4}.$$

Công thức (6) có thể dễ dàng thu được từ đẳng thức rất giống (Hình 2):

$$S_{\Delta ABC} = S_{\Delta AOB} + S_{\Delta BOC} + S_{\Delta COA}.$$

Bây giờ chúng ta hãy xem xét thêm một vài bài toán. Trong mỗi phương pháp đó, việc áp dụng phương pháp tính diện tích sẽ tạo ra một lời giải ngắn và được phát âm.

⟦folio 43⟧

Bài 3. Trong tam giác đều cạnh a lấy một điểm M tùy ý. Tìm tổng khoảng cách từ điểm này đến các cạnh của tam giác.

Lời giải. Cần tìm tổng độ dài các đường vuông góc MP, MQ và MR (Hình 3) lần lượt hạ từ điểm M xuống các cạnh AB, BC và CA. Nếu chúng ta nối điểm M với các đỉnh của tam giác thì rõ ràng là $S_{\Delta ABC} = S_{\Delta AMB} + S_{\Delta BMC} + S_{\Delta CMA}$. Sử dụng công thức tính diện tích tam giác đều $S_{\Delta ABC} = \frac{a^2 \sqrt{3}}{4}$ và thay công thức đó (bằng công thức (1)).

$$S_{\Delta AMB} = \frac{1}{2} a \cdot MP,$$

$$S_{\Delta BMC} = \frac{1}{2} a \cdot MQ,$$

$$S_{\Delta CMA} = \frac{1}{2} a \cdot MR,$$

chúng tôi ngay lập tức nhận được đáp số:

$$MP + MQ + MR = \frac{a \sqrt{3}}{2}.$$

Bài 4. Đường thẳng AD chia tam giác ABC thành hai. Chứng minh rằng bán kính r của đường tròn nội tiếp tam giác ABC nhỏ hơn tổng bán kính $r_1$ và $r_2$ của đường tròn nội tiếp tam giác ABD và ACD.

Lời giải. Gọi CD và CE là các tia đang xét trong điều kiện làm việc (Hình 5). Rõ ràng là $S_{\Delta ABC} = S_{\Delta ACD} + S_{\Delta DCB} = S_{\Delta ACE} + S_{\Delta ECB}$.

Chúng ta hãy sử dụng công thức (2), có tính đến $ACD = DCE = ECB = \frac{\alpha}{3}$:

$$\frac{AC \cdot DC \sin \frac{\alpha}{3}}{2} + \frac{DC \cdot BC \sin \frac{2\alpha}{3}}{2} = \frac{AC \cdot EC \sin \frac{2\alpha}{3}}{2} + \frac{EC \cdot BC \sin \frac{\alpha}{3}}{2}.$$

⟦folio 44⟧

Cơm. 5.

Từ đây ta có ngay

$$\frac{DC}{EC} = \frac{AC \sin \frac{2\alpha}{3} + BC \sin \frac{\alpha}{3}}{AC \sin \frac{\alpha}{3} + BC \sin \frac{2\alpha}{3}}$$

$$= \frac{2 \cos \frac{\alpha}{3} + 3}{6 \cos \frac{\alpha}{3} + 1}$$

Đây là một ví dụ về bài toán khó hơn. Mặc dù trong đó bạn chỉ cần “giải tam giác”, tức là xác định các cạnh của nó bằng ba phần tử đã biết, nhưng không thể thu được lời giải theo cách thông thường - sử dụng các định lý về sin và cosin.

Bài 6. Gọi tên tam giác ABC nếu $h_a=6$, $r=2$, $R=5$.

Lời giải và e. Chúng ta hãy sử dụng các công thức (1), (4), (5) và (6) và viết hệ phương trình sau cho các cạnh chưa biết $a, b, c$

$$\begin{cases} S = 3a, \\ S = \frac{abc}{20}, \\ S = \frac{1}{4} \sqrt{(a+b+c)(b+c-a)} \times \sqrt{(a+c-b)(a+b-c)}, \\ S = a+b+c. \end{cases}$$

Đánh đồng các quy tắc của các phần của phương trình đầu tiên và cuối cùng, chúng ta thu được $b+c=2a$. Đánh đồng các quy tắc cho các phần của phương trình thứ nhất và thứ hai, chúng ta thu được $bc=60$. Cuối cùng, đánh đồng các quy tắc cho các phần của phương trình thứ nhất và thứ ba, chúng ta thu được (sau khi bình phương) rằng

$$144a^2 = (a+b+c)(b+c-a) \times (a+c-b) \times (a+b-c) = [(b+c)^2-a^2] \times [a^2-(b-c)^2] = [(b+c)^2-a^2] \times [a^2-(b+c)^2+4bc] = (4a^2-a^2) \times (a^2-4a^2+240) = 3a^2 (240-3a^2).$$

Do đó, để xác định $a$ ta thu được phương trình

$$144a^2 = 3a^2 (240-3a^2),$$

từ đâu $a=8$. Từ hệ phương trình $b+c=16$, $bc=60$ giờ đây dễ dàng tìm được hai cặp giá trị $b$ và $c$ (hai đáp số):

$$a = 8, b = 6, c = 10 или a = 8, b = 10, c = 6,$$

đó là các định nghĩa hình học của tam giác odin (đến mức chỉ định các cạnh $b$ và $c$).

Trong ví dụ này, đặc điểm chính của phương pháp diện tích đặc biệt rõ ràng - từ một bài toán hình học, nó “tạo ra” một đại số, giảm mọi thứ xuống lời giải của một số hệ phương trình.

Nhiệm vụ 7. (MSU, nhà vật lý, 1966) Chứng minh rằng nếu độ dài các cạnh của một tam giác tạo thành một phép tính số học

⟦folio 45⟧

Cơm. 6a.

đường cắt metische, tâm của đường tròn nội tiếp trong tam giác này và giao điểm của đường trung tuyến của nó nằm trên một đường thẳng song song với cạnh giữa của tam giác.

Lời giải. Giả sử các cạnh của tam giác ABC có dạng sao cho $a \leq b \leq c$. Sau đó theo điều kiện bài toán $a+c=2b$. Đặt $O$ là tâm của đường tròn nội tiếp và $M$ là điểm giao nhau của các đường trung tuyến $AA_1$, $BB_1$ và $CC_1$ (Hình 6a).

Đầu tiên, chúng ta rút ra một tính chất hữu ích của điểm $M$ giao điểm của đường trung tuyến của tam giác $ABC$. Trong hình 6b, tam giác ABC được chia bởi các đường trung tuyến thành 6 tam giác nhỏ hơn. Diện tích của mỗi hình bằng $\frac{1}{6}$ diện tích của toàn bộ tam giác $ABC$. Điều này rất dễ chứng minh: sử dụng

Cơm. 66.

công thức (1), viết đẳng thức
$$S_{\triangle BB_1C} = \frac{1}{2} S_{\triangle ABC}, B_1M = \frac{1}{3} BB_1,$$
$$S_{\triangle MCB_1} = \frac{1}{3} S_{\triangle BB_1C} = \frac{1}{6} S_{\triangle ABC}.$$

Diện tích các hình tam giác còn lại có thể tìm tương tự.

Bây giờ chúng ta hãy tìm độ dài của đường vuông góc $MM'$ hạ từ điểm $M$ sang cạnh $AC$:
$$\frac{1}{3} S_{\triangle ABC} = S_{\triangle AMC} = \frac{1}{2} MM' \cdot AC =$$
$$= \frac{1}{2} MM' \cdot b, \frac{1}{3} S_{\triangle ABC} = \frac{1}{3} rp =$$
$$= \frac{1}{3} r \left( \frac{a+b+c}{2} \right) = \frac{1}{3} r \left( \frac{2b+b}{2} \right) =$$
$$= \frac{1}{2} rb,$$

từ đâu $MM'=r$, tức là $MO \parallel AC$.

Phương pháp diện tích thường tỏ ra thuận tiện ở từng giai đoạn lời giải lập thể bài toán.

Bài tập 8. (MSU, cơ chế, 1969) Một hình chóp nội tiếp trong một quả cầu, các cạnh bên bằng c. Đế của nó là một mặt phẳng hình chữ nhật, các cạnh của nó được nối với nhau bằng các cung $\alpha$ và $\beta$ radian trong các phần của quả bóng bằng các mặt phẳng của các mặt bên. Xác định bán kính của hình cầu ngoại tiếp.

Lời giải (Hình 7). Vì góc nội tiếp thay đổi một nửa

⟦folio 46⟧

không có vòng cung nào mà nó nằm trên đó,
Cái đó
$$\Rightarrow DQC = \frac{\alpha}{2}, \Rightarrow AQD = \frac{\beta}{2}.$$

Pozny $DC = 2c \sin \frac{\alpha}{4}$, $AD = 2c \sin \frac{\beta}{4}$.

Chúng ta hãy xem xét tiết diện của quả bóng theo mặt phẳng $AQC$. Vì tâm của quả bóng nằm trong mặt phẳng này (chứng minh đi!), nên bán kính của quả bóng bằng bán kính $R$ của đường tròn ngoại tiếp tam giác $AQC$. Nhưng $AQ = QC = c$ và $AC = 2c \sqrt{\sin^2 \frac{\alpha}{4} + \sin^2 \frac{\beta}{4}}$ (giống như đường chéo của hình chữ nhật $ABCD$). Do đó, để xác định bán kính $R$, chỉ cần sử dụng các biểu thức tính diện tích tam giác $AQC$ bằng các công thức (4) và (5).

Kết quả của các phép biến đổi hiển nhiên, chúng ta thu được đáp số:

$$R = \frac{c}{\sqrt{2 \left( \cos \frac{\alpha}{2} + \cos \frac{\beta}{2} \right)}}.$$

Phương pháp diện tích cũng thuận tiện để sử dụng trong các bài toán cần tìm các loại ước lượng khác nhau cho các đại lượng hình học.

Bài toán 9. Tỷ lệ giữa bán kính của một hình tròn được mô tả trong một tam giác vuông với chiều cao giảm đi một đơn vị có thể thay đổi trong giới hạn nào?

Lời giải. Nếu $c$ là cạnh huyền của tam giác vuông $ABC$ thì chúng ta có thể viết (xem công thức (1) và (6)):

$$\frac{ch_c}{2} = pr, \text{откуда} \frac{r}{h_c} = \frac{c}{2p}.$$

Vì vậy cần đánh giá mối quan hệ

$$\frac{c}{2p} = \frac{c}{a + b + c} = \frac{1}{\frac{a}{c} + \frac{b}{c} + 1} = \frac{1}{\sin A + \sin B + 1}.$$

Vì $A + B = 90^\circ$ thì

$$\sin A + \sin B + 1 = \sin A + \cos A + 1 = \sqrt{2} \cos (45^\circ - A) + 1.$$

Góc nhọn $A$ của tam giác vuông có thể có giá trị bất kỳ trong khoảng từ 0 đến 90^\circ. Do đó, góc $45^\circ - A$ nhỏ hơn trong phạm vi từ $-45^\circ$ đến $+45^\circ$, có thể dễ dàng thu được từ các tính chất của cosin, trong khi $2 < \sqrt{2} \cos (45^\circ - A) + 1 \leqslant 1 + \sqrt{2}$.

Do đó, trong bất kỳ tam giác vuông nào, lời giải vô định của nhiều bài toán luôn đúng. Tất nhiên, nó không thay thế tất cả các phương pháp khác, nhưng nó là một cách tiếp cận không nên quên khi tiếp cận lời giải cái này hay cái kia bài toán.

Bài tập

1. Tìm trung tuyến $m_a$ của tam giác, giá trị cạnh của nó $a, b, c$.
2. Chứng minh rằng trong một tam giác tùy ý

$$\frac{1}{r} = \frac{1}{h_a} + \frac{1}{h_b} + \frac{1}{h_c}.$$

3. (MSU, Khoa Kinh tế, 1969). Trong tam giác nhọn $ABC$ cho trước: $AB = c$ vẽ từ đỉnh $B$ đường trung tuyến $BD = m$. Góc $BDA$ nhọn và bằng $B$. Tính diện tích tam giác $ABC$.
4. (MSU, Khoa Tâm lý học, 1969). Cho một tam giác vuông đều. Chứng minh rằng bán kính của đường tròn tiếp xúc với cạnh huyền và phần kéo dài của các cạnh huyền bằng tổng cạnh huyền và bán kính của đường tròn mô tả trong tam giác.
5. Biết rằng trong tam giác $ABC$:

$$S_{\triangle ABC} = 16, m_a = 6, m_b = 4.$$

Chứng minh rằng các đường trung tuyến $m_a$ và $m_b$ vuông góc với nhau.
6. Chứng minh rằng tổng khoảng cách từ một điểm tùy ý nằm trong một tam giác đều các cạnh đến cạnh của tam giác này nằm giữa điểm nhỏ nhất và điểm thấp nhất.

7. Đáy $ABCD$ của đường thẳng $ABCDA_1B_1C_1D_1$ (trong đó $AA_1, BB_1, CC_1, DD_1$ là các cạnh bên) là hình thoi ở cạnh $a$ và một góc nhọn $φ$, đồng thời chiều cao của đường thẳng là $h$. Tìm khoảng cách từ đỉnh $B_1$ đến đường chéo $A_1D$ của mặt bên $ADD_1A_1$.
