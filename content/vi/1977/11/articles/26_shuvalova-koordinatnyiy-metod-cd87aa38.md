---
id: 1977-11-shuvalova-koordinatnyiy-metod-cd87aa38
issue: kvant_1977_11
year: 1977
number: "11"
title: Phương pháp tọa độ
authors:
  - Шувалова Э. З.
rubric: praktikum-abiturienta
rubric_sub: Практикум абитуриента
page_first: 84
page_last: 89
page_labels: 82, 83, 84, 85, 87
tag: LSJZ
lang: vi
source: kvant_digital
extraction: vision
content_sha256: b5e513a1b1cd5c57480aff6e16b30381124ab0c2681ffba6612805fa7267e58d
prompt_sha256: draft-1
translated_from: content/ru/1977/11/articles/26_shuvalova-koordinatnyiy-metod-cd87aa38.md
source_content_sha256: e471c0b168391903cfaab6aac9461731a4d9b1beffa855fed99020038487af3e
translation_model: draft
translation_run: vi-draft-2026-10-31
translation_quality: draft
---

⟦folio 82⟧

E. Shuvalova

Phương pháp tọa độ

Đại số vectơ và phương pháp tọa độ, có trong chương trình giảng dạy toán học mới ở trường học, là một công cụ mạnh mẽ cho lời giải nhiều bài toán hình học, và trên hết vì chúng không yêu cầu xem xét các cấu hình hình học phức tạp. Các phương pháp này biến dạng hình học bài toán thành dạng đại số, thường dễ giải hơn dạng hình học ban đầu. Mọi kỹ sư đều phải nắm vững phương pháp tọa độ, và do đó đặc biệt chú ý đến tầm quan trọng của phương pháp tọa độ trong các kỳ thi đầu vào các ngành kỹ thuật.

Chương trình thi tuyển sinh đại học môn toán (xem “Quant”, 1977, số 2) quy định “thí sinh phải… sử dụng được các phương pháp đại số và khởi đầu phân tích ở lời giải hình học bài toán” (khoản 8 chuyên mục “Kỹ năng cơ bản”).

Những câu hỏi này là chủ đề của bài viết này.

1. Tính góc

Bài toán 1. Cho giá trị hai góc phẳng của một phần tử tam diện:

(Kết thúc. Xem trang 77--81 để biết phần mở đầu.)
nghiêng về phía chân trời
α = β = arctg μ.

Để kết luận, chúng tôi mời độc giả tự mình giải đường dẫn bài toán như một bài tập. Chúng tôi khuyên bạn nên đặc biệt chú ý đến ý nghĩa của một số bài tập nhất định có trong điều kiện bài toán.

Bài tập

1. Nam tước Munchausen khi bay lên Mặt trăng đã sử dụng khẩu pháo có chiều dài nòng L = 600 m. Để gửi một viên đạn vào không gian quốc tế, anh ta cần truyền đạt tốc độ |v| = 12 km/s. Xác định lực mà Nam tước Munchausen ép lên viên đạn dicho nằm bên trong viên đạn nếu khối lượng m = 80 kg. Giả sử đạn trong pháo chuyển động với cùng tốc độ (Hình 9). Hệ số ma sát của tải trọng trên bề mặt bằng

⟦folio 83⟧

Hình 1.

$$\overrightarrow{BD}_1 = \overrightarrow{BA} + \overrightarrow{AD} + \overrightarrow{DD}_1 = (a; -b, c),$$
$$\overrightarrow{A}_1D = \overrightarrow{A}_1A + \overrightarrow{AD} = (a; 0; -c).$$
Từ đây chúng tôi nhận được:

$$\cos \left( \overrightarrow{BD}_1, \overrightarrow{A}_1D \right) = \frac{\overrightarrow{BD}_1 \cdot \overrightarrow{A}_1D}{|BD_1| \cdot |A_1D|} = \frac{a^2 - c^2}{\sqrt{a^2 + b^2 + c^2} \sqrt{a^2 + c^2}}.$$

Vì góc giữa hai đường thẳng là giá trị nhỏ hơn của các góc được xác định bởi những đường thẳng này (xem “Hình học 9”, § 24), nên tại $a^2 - c^2 \geq 0$ góc mong muốn bằng $\arccos \frac{a^2 - c^2}{\sqrt{a^2 + b^2 + c^2} \sqrt{a^2 + c^2}}$ và tại $a^2 - c^2 < 0$ nó bằng $\pi - \arccos \frac{a^2 - c^2}{\sqrt{a^2 + b^2 + c^2} \sqrt{a^2 + c^2}}$.

Cho công thức

$$\pi - \arccos t = \arccos (-t)$$

đáp số có thể được viết như sau:

$$\left( \overrightarrow{BD}_1, \overrightarrow{A}_1D \right) =$$

μ. Lực căng chỉ thay đổi bao nhiêu lần nếu hệ số ma sát giảm đi một nửa?

3. Tên lửa cất cánh thẳng đứng hướng lên trên dưới tác động của khí hình thành trong quá trình đốt cháy nhiên liệu và phát ra với tốc độ $|\vec{v}| = 1000$ m/s so với mặt đất. Tên lửa sẽ tăng lên độ cao tối đa bao nhiêu nếu nó di chuyển trong $\Delta t = 2$ s, và bỏ qua tỷ số giữa khối lượng khí cháy và khối lượng của tên lửa trong quá trình cất cánh và lực cản của không khí.

4. Một người lính cứu hỏa giữ một cái vòi nghiêng một góc $\alpha = 30^\circ$ so với phương ngang. Tốc độ dòng nước từ vòi là $G = 50$ kg/s. Tốc độ của nước thoát ra là $|\vec{v}| = 20$ m/s. Lực của lính cứu hỏa tác dụng lên sàn tăng lên bao nhiêu?

5. Hình 10 thể hiện một hệ gồm hai vật có khối lượng $m_1 = 2$ kg và $m_2 = 3$ kg, được nối với nhau bằng một sợi dây không hòa tan, ném qua một khối cố định và chuyển động được. Tại thời điểm ban đầu vật thứ nhất nằm trên mặt phẳng nghiêng có chiều dài $L = 3$ m, hợp với đường chân trời một góc $\alpha = 30^\circ$. Sau bao lâu vật này chạm tới mép mặt phẳng nghiêng nếu hệ số ma sát trên mặt phẳng nghiêng là $\mu = 0,25$? Bỏ qua ma sát trong các khối cũng như khối lượng của các khối và sợi dây.

⟦folio 84⟧

Hình 3.

(vì điểm $M$ nằm trên đường thẳng $AD_1$ khi và chỉ khi các vectơ $\overrightarrow{AM}$ và $\overrightarrow{AD_1}$ thẳng hàng và tương tự đối với điểm $N$). Bây giờ chúng ta hãy tìm $\overrightarrow{MN} = \overrightarrow{MA} + \overrightarrow{AD} + \overrightarrow{DN}$ và viết ra các điều kiện về độ vuông góc của vectơ $\overrightarrow{MN}, \overrightarrow{AD_1}$ và $\overrightarrow{MN}, \overrightarrow{DC_1}$; điều này mang lại cho chúng ta hai phương trình mà từ đó chúng ta tìm thấy $\alpha$ và $\beta$, sau đó là độ dài của vectơ $\overrightarrow{MN}$.

Hãy thực hiện các tính toán cần thiết:

$$\overrightarrow{MN} = \overrightarrow{MA} + \overrightarrow{AD} + \overrightarrow{DN} = -\overrightarrow{AM} + \overrightarrow{AD} + \overrightarrow{DN} = -\alpha \cdot \overrightarrow{AD_1} + \overrightarrow{AD} + \beta \cdot \overrightarrow{DC_1} = (\beta \alpha; a(1-\alpha); a(\beta-\alpha)).$$

Viết tích vô hướng $\overrightarrow{MN} \cdot \overrightarrow{AD_1}$ và $\overrightarrow{MN} \cdot \overrightarrow{DC_1}$ trong tọa độ và cho chúng bằng 0 (điều kiện vuông góc của hai vectơ), ta thu được hệ

$$\begin{cases} a^2(1-\alpha) + a^2(\beta-\alpha) = 0, \\ a^2\beta + a^2(\beta-\alpha) = 0, \end{cases}$$

Ở đâu

$$\begin{cases} 1 + \beta - 2\alpha = 0, \\ 2\beta - \alpha = 0, \\ \alpha = \frac{2}{3}, \beta = \frac{1}{3}. \end{cases}$$

Hiện nay

$$\overrightarrow{MN} = \left( \frac{a}{3}; \frac{a}{3}; -\frac{a}{3} \right),$$

$$|\overrightarrow{MN}| = \frac{a^2}{9} + \frac{a^2}{9} + \frac{a^2}{9} = \frac{a\sqrt{3}}{3}.$$

Bài 4. Trong không gian, cho hai vòng $AM$ và $BK$ không nằm trong cùng một mặt phẳng và tạo thành một góc $\pi/2$ với nhau; đoạn $AB$ là đường vuông góc chung của chúng. Trên tia $AM$ và

⟦folio 85⟧

3. Bài toán cho các phần

Thông thường, trong những bài toán như vậy, bạn cần tìm mặt cắt ngang của khối đa diện theo mặt phẳng (tức là hình dạng và diện tích của nó). Mặt cắt tạo ra một đa giác, các đỉnh của nó là giao điểm của mặt phẳng cắt với các cạnh của khối đa diện, và các cạnh là các đoạn thẳng mà mặt phẳng cắt cắt các mặt của khối đa diện.

Cần nhớ lại rằng mặt phẳng cắt giao với các mặt phẳng song song dọc theo các đường song song - điều này thường hữu ích với lời giải bài toán, chẳng hạn như trên mặt cắt của khối lập phương. Khi tính diện tích mặt cắt ngang, một công thức hữu ích liên hệ diện tích của một hình với diện tích hình chiếu của nó $S_{\pi p} = S_{\phi \pi r} \cdot \cos \varphi$ (xem “Hình học 10”, § 50). Thông thường, công thức này cho phép bạn không tìm thấy phần đó mà ngay lập tức đưa ra diện tích của nó.

Bài toán 5. Hình dạng và diện tích mặt cắt ngang của hình lập phương $ABCD_1B_1C_1D_1$ có mặt phẳng cạnh 1 đi qua đỉnh $A$, điểm giữa của cạnh $BC$ và tâm của mặt $CDD_1C_1$.

Hãy xây dựng hệ tọa độ chữ nhật như hình 5. Phương trình mặt phẳng cắt là phương trình tổng quát của mặt phẳng có dạng

$$ax + by + cz + d = 0.$$

Mối liên hệ giữa các hệ số $a, b, c, d$ có thể được tìm thấy từ điều kiện các điểm $A(0; 0; 0), E(1; 1/2; 0)$ (giữa cạnh $BC$) và $M(1/2; 1; 1/2)$ (tâm của cạnh $CDD_1C_1$) nằm trong mặt phẳng này, tức là tọa độ của các điểm này phải thỏa mãn phương trình của mặt phẳng. Từ đây ta có hệ thống

$$\begin{cases} a \cdot 0 + b \cdot 0 + c \cdot 0 + d = 0, \\ a \cdot 1 + b \cdot \frac{1}{2} + c \cdot 0 + d = 0, \\ a \cdot \frac{1}{2} + b \cdot 1 + c \cdot \frac{1}{2} + d = 0. \end{cases}$$

Hình chiếu của phần $AEFG$ lên mặt phẳng $ABCD$ là tứ giác $AECD$, có diện tích là $3/4$. Do đó, cosin của góc của mặt phẳng $AEFG$ và $ABCD$ bằng giá trị abcylot của cosin của góc giữa các vectơ vuông góc với các mặt phẳng này, ví dụ $\vec{n}_1 = (1; -2; 3)$ và $\vec{n}_2 = \overrightarrow{AA}_1 = (0; 0; 1)$ (xem “Hình học 10”, § 46, bài toán 43), do đó

$$\cos \varphi = \frac{|\overrightarrow{n}_1 \cdot \overrightarrow{n}_2|}{|\overrightarrow{n}_1| \cdot |\overrightarrow{n}_2|} = \frac{|1 \cdot 0 - 2 \cdot 0 + 3 \cdot 1|}{\sqrt{1^2 + 2^2 + 3^2}} = \frac{3}{\sqrt{14}}.$$

⟦folio 87⟧

| $OO_1$|, $|O_1A|$ và $|O_1B|$ sẽ được thực thi tự động, vì $|O_1O_2| \perp (OAB)$ và $O_2$ là tâm của tam giác $OAB$, điều kiện thứ hai là $\cos((SAB), \hat{OAB}) = \cos \varphi$ ở dạng tọa độ.

Dễ dàng tìm được phương trình mặt phẳng $SAB$ có dạng

$$\frac{s}{\sqrt{3}} \cdot x + s \cdot y + a \cdot z - a \cdot s = 0,$$

Hơn nữa, vectơ $\vec{n}_1 = \left( \frac{s}{\sqrt{3}}; s; a \right)$ vuông góc với mặt phẳng này và vectơ $\vec{n}_2 = (0; 0; 1)$ vuông góc với mặt phẳng $OAB$. Bây giờ chúng ta nhận được hai phương trình:

$$\sqrt{\frac{a^2}{12} + \frac{a^2}{4}} + (h - s)^2 = \sqrt{\frac{a^2}{12} + \frac{a^2}{4}} + h^2,$$

$$\frac{a}{\sqrt{\frac{s^2}{3} + s^2 + a^2}} = \cos \varphi.$$

Từ phương trình thứ hai chúng ta tìm thấy

$$s = \frac{\sqrt{3}}{2} a \mathrm{tg} \varphi,$$

và sau đó từ lần đầu tiên

$$h = \frac{\sqrt{3}}{4} a \mathrm{tg} \varphi.$$

Hiện nay

$$R^2 = |OO_1|^2 = \frac{a^2 (16 + 9 \mathrm{tg}^2 \varphi)}{48}$$

Và

$$S_{\text{cф}} = 4\pi R^2 = \frac{\pi a^2 (16 + 9 \mathrm{tg}^2 \varphi)}{12}.$$

Bài 8. Dựa vào tham số của các hình dịch vụ có cạnh $a$.

Hình 7.

Hai góc hai fer ở các cạnh của đáy là góc vuông, hai góc còn lại bằng $\varphi$. Tìm bán kính của hình cầu được ghi trong tham số.

Chúng ta hãy xây dựng một hệ tọa độ hình chữ nhật, như trong Hình 8. Tâm $O_1$ của hình cầu phải được loại bỏ khỏi tất cả các mặt của paramid, đặc biệt, khỏi các mặt phẳng tọa độ, ở khoảng cách $r$—bán kính của hình cầu, do đó tọa độ của nó có dạng $O_1(r; r; r)$. Mặt phẳng $SBC$ chứa các điểm $B(a; a; 0)$, $C(0; a; 0)$ và $S(0; 0; a \mathrm{tg} \varphi)$, ta tìm được phương trình:

$$\mathrm{tg} \varphi \cdot y + z - a \mathrm{tg} \varphi = 0.$$

Một mặt, khoảng cách từ điểm $O_1$ đến mặt phẳng $SBC$ phải bằng $r$; mặt khác có thể biểu diễn qua tọa độ của điểm $S$, $B$, $C$: vectơ $\vec{O_1Q}$ vuông góc với mặt phẳng $SBC$ ($Q \in (SBC)$), thẳng hàng với vectơ $\vec{n} = (0; \mathrm{tg} \varphi; 1)$ (tọa độ của vectơ $n$ được tìm từ phương trình của mặt phẳng $SBC$), do đó

$$\vec{O_1Q} = h \cdot \vec{n} = (0; h \mathrm{tg} \varphi; h).$$

Bây giờ, khi biết tọa độ của điểm $O_1$ thì tìm được mặt phẳng $SBC$ (tức là tọa độ của điểm $Q$ thỏa mãn phương trình của mặt phẳng $SBC$):

$$\mathrm{tg} \varphi (h \mathrm{tg} \varphi + r) + h + r - a \mathrm{tg} \varphi = 0,$$

Ở đâu

$$h = (a \mathrm{tg} \varphi - r - r \mathrm{tg} \varphi) \cos^2 \varphi,$$

$$|O_1Q| = |h| \cdot |\vec{n}| = (a \mathrm{tg} \varphi - r - r \mathrm{tg} \varphi) \cos^2 \varphi \cdot \frac{1}{\cos \varphi} = (a \mathrm{tg} \varphi - r - r \mathrm{tg} \varphi) \cos \varphi$$

Hình 8.
