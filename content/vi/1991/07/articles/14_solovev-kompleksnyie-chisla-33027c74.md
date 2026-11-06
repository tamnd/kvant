---
id: 1991-7-solovev-kompleksnyie-chisla-33027c74
issue: kvant_1991_7
year: 1991
number: "7"
title: số phức
authors:
  - Соловьёв Ю. П.
rubric: shkola-v-kvante
page_first: 49
page_last: 55
page_labels: 47, 49, 50, 51, 52, 53
lang: vi
source: kvant_digital
extraction: vision
content_sha256: 4fb669cf3a70258fd31cfbdaf87862afc405b29bb145f85dc39ce941aa1fabd2
prompt_sha256: draft-1
translated_from: content/ru/1991/07/articles/14_solovev-kompleksnyie-chisla-33027c74.md
source_content_sha256: 78904b3e41ba58650dfdb72a26edd0bdd52696331fc8a8f11f8693baa9d23161
translation_model: draft
translation_run: vi-draft-gaps-2026-11-06
translation_quality: draft
---

⟦folio 47⟧

---
running_head:
folio:
---

Matematika 9 — 11
số phức
Tiến sĩ Khoa học Vật lý và Toán học
Y. SOLOVIEV

Ngay từ thời cổ đại, với lời giải bài toán, được viết bằng ngôn ngữ hiện đại dưới dạng phương trình bậc hai, các nhà toán học đã phải đối mặt với những tình huống cần phải rút ra nghiệm từ số âm. Trong những trường hợp như vậy, bài toán được coi là không thể quyết định được. Tuy nhiên, lời giải trong các căn thức của phương trình bậc ba, được các nhà toán học Illyan tìm ra vào nửa đầu thế kỷ XVI, đã dẫn đến việc biểu diễn nghiệm thực của phương trình dưới dạng căn bậc hai của số âm. Điều này buộc các nhà toán học phải làm việc với những con số mới, áp dụng cho chúng những quy luật hoạt động giống như những con số thực tuân theo.

Hãy xem xét bài toán lấy căn bậc hai của số âm $\sqrt{-a}$. Vì bình phương của một số thực luôn dương nên bài toán như vậy là không thể xảy ra trong phạm vi số thực. Chúng tôi cần một số số mới:

$$\sqrt{-a} = \sqrt{a} \cdot \sqrt{-1} = \sqrt{a} \cdot i,$$

trong đó $i = \sqrt{-1}$, $i^2 = -1$ là ký hiệu của một số mới, không có thực, được gọi là đơn vị tối thiểu.

Số của mẫu

$$a + bi,$$

trong đó $a$ và $b$ là số thực, gọi là số phức; số $a$ được gọi là phần thực và số $b$ được gọi là phần tối thiểu. Tại $a = 0$ số phức trở thành số nhỏ nhất $bi$; với $b = 0$ ta được số $a + 0i$, được coi là số thực $a$.

Số phức có dạng $z = a + bi$ và $z = a - bi$ được gọi là liên hợp, số phức có dạng $a + bi$ và $-a - bi$ được gọi là số đối nhau. Tập hợp số phức thường được ký hiệu là $C$.

Điều kiện để xét số phức $a + bi$ và $c + di$ bằng nhau khi và chỉ khi $a = c$ và $b = d$.

Từ định nghĩa này, suy ra rằng số phức $a + bi$ bằng 0 khi và chỉ khi $a = 0$ và $b = 0$. Trên thực tế, số thực 0 có thể được biểu diễn dưới dạng số phức là $0 + 0i$. Dựa trên định nghĩa, đẳng thức $a + bi = 0 + 0i$ sẽ chỉ đúng nếu đáp ứng $a = 0$ và $b = 0$.

Lưu ý rằng đối với số phức, người ta không thống nhất được cái nào được coi là lớn hơn cái kia.

cách nói
1. Tìm $x$ và $y$ để biết

$$(2x + 3y) + (x - y)i = 2 + (2x + y)i.$$

2. Tìm số phức, số đối và liên hợp của số

a) $2 + i$; 6) $1 + i$.

3. Những số phức nào trùng với tính chất liên hợp của chúng? Đối diện?

⟦folio 49⟧

---
running_head:
folio:
---

$$a + bi = (x + yi)^2 = (x^2 - y^2) + 2xyi,$$
tức là
$$x^2 - y^2 = a, 2xy = b.$$

Do đó, bài toán rút gọn thành việc tìm lời giải thực của hệ thống này. Bằng cách bình phương cả hai phương trình rồi cộng chúng, chúng ta nhận được $(x^2 + y^2)^2 = a^2 + b^2; x^2 + y^2 = \sqrt{a^2 + b^2},$ (chỉ lấy nghiệm dương vì $x^2 + y^2 > 0$). Bây giờ từ phương trình
$$x^2 + y^2 = \sqrt{a^2 + b^2}, x^2 - y^2 = a$$
chúng tôi tìm thấy
$$x^2 = \frac{\sqrt{a^2 + b^2} + a}{2}, y^2 = \frac{\sqrt{a^2 + b^2} - a}{2}.$$

Đối với $x$ và $y$, mỗi giá trị chúng ta có hai giá trị, tạo ra bốn kết hợp $(x; y)$, tuy nhiên, từ các điều kiện $xy = b/2$, dấu của sản phẩm $xy$ phải trùng với dấu của số $b$; điều này chỉ mang lại hai cặp giá trị $(x; y)$, tức là hai gốc:

$$\sqrt{a + bi} =$$
$$= \pm \left( \sqrt{\frac{\sqrt{a^2 + b^2} + a}{2}} + i \sqrt{\frac{\sqrt{a^2 + b^2} - a}{2}} \right),$$
$$b > 0,$$
$$\sqrt{a + bi} =$$
$$= \pm \left( \sqrt{\frac{\sqrt{a^2 + b^2} + a}{2}} - i \sqrt{\frac{\sqrt{a^2 + b^2} - a}{2}} \right),$$
$$b < 0.$$

Bài tập 6. Tính toán
a) $\sqrt{1 + i}$; 6) $\sqrt{3 + 4i}$;
b) $\sqrt{4 - 3i}$;
d) $\sqrt{\cos \alpha + i \sin \alpha}$ ($0 < \alpha < \pi$);
e) $\sqrt{\cos 2\alpha - i \sin 2\alpha}$.

Lời giải phương trình bậc hai
Người ta biết rằng không phải mọi phương trình bậc hai đều có thể giải được bằng số thực; điều kiện để có thể giải được là tính không âm của phân biệt đối xử $D = b^2 - 4ac$ của nó. Trong các tổ hợp số, ngoại lệ này biến mất. Nếu $D < 0$ thì lời giải của phương trình bậc hai được tìm bằng công thức
$$x_{1,2} = \frac{-b \pm \sqrt{|D|} \cdot i}{2a}.$$

Nói cách khác, bất kể hệ số $a, b$ và $c$ của phương trình bậc hai là bao nhiêu
$$ax^2 + bx + c = 0,$$
 lời giải của nó được tìm thấy theo công thức
$$x_{1,2} = \frac{-b \pm \sqrt{b^2 - 4ac}}{2a}.$$

Cũng lưu ý rằng công thức này cho phép bạn giải phương trình bậc hai với hệ số phức tạp $a, b, c$. Suy cho cùng, chúng ta đã biết căn bậc hai của bất kỳ số phức nào.

Bài tập
7. Giải phương trình bậc hai
a) $x^2 + 2x + 2 = 0$;
b) $x^2 + (1 + i)x + i = 0$;
b) $ix^2 - 2x + 1 = 0.$

8. Tìm tất cả các nghiệm của phương trình (phức tạp)
a) $x^3 = 1$;
b) $x^4 = -1$;
b) $x^4 + x^2 + 1 = 0.$

Giải thích hình học của số phức

Từ “phức tạp” được dịch từ tiếng Latin có nghĩa là “tổng hợp”, “phức tạp”. Mặc dù thực tế là thao tác với số phức không khó hơn số thực, nhưng cho đến đầu thế kỷ 19, số phức vẫn được coi là một đối tượng rất phức tạp, đen tối và gần như thần bí. Với sự bền bỉ đáng được sử dụng tốt hơn, cân nặng là một cuộc đấu tranh lâu dài giữa các bên và đối thủ về số lượng “tối thiểu”. Phản đối chính của những người phản đối là như sau: biểu thức có dạng $a + bi$ là vô nghĩa, vì $i$ không phải là một số thực và do đó hoàn toàn không phải là một số; do đó $i$ không thể nhân với số thực.

⟦folio 50⟧

---
running_head:
folio:
---

Để đặt lý thuyết số phức trên một nền tảng vững chắc, cần phải có một cấu trúc rõ ràng về chúng, tốt nhất là cấu trúc hình học. Mong muốn có được sự hiện thực hóa hình học của một tập hợp số phức không phải là ngẫu nhiên, nếu chúng ta nhớ rằng đối với chúng ta, tập hợp số thực không thể tách rời khỏi một “đường thẳng thực” với một điểm cố định trên đó biểu thị số 0 và với một thang đo cố định được xác định bởi vị trí của số 1.

Lần đầu tiên, một biểu diễn hình học của các hành động trên các số phức được nhà khảo sát trẻ em K. Vesel đưa ra vào năm 1799 và, độc lập với ông, bởi nhà toán học người Pháp J. Arganov vào năm 1806. Tuy nhiên, nó chỉ nhận được sự công nhận rộng rãi vào những năm ba mươi, nhiều thế kỷ sau công trình của nhà toán học người Đức F. Gauss và nhà toán học người Anh W. Hamilton. Ý tưởng giải thích hình học của số phức là chúng được biểu diễn không phải bằng các điểm trên một đường thẳng, giống như số thực, mà bằng các điểm trên một mặt phẳng.

Vì vậy, hãy xây dựng một tập hợp có các phần tử là các điểm của mặt phẳng và phép cộng và nhân các điểm sẽ tuân theo tất cả các quy tắc hoạt động với số thực.

Chúng ta hãy chọn hệ tọa độ trực tiếp trong mặt phẳng với trục hoành $x$ và trục tọa độ $y$. Chúng ta hãy biểu thị bằng $(a; b)$ điểm có hoành độ $a$ và tọa độ $b$. Đối với điểm $(a; b)$ và $(c; d)$ chúng ta xác định tổng và tích theo quy tắc:

$$
(a; b) + (c; d) = (a + c; b + d),
$$

$$
(a; b) \cdot (c; d) = (ac - bd; ad + bc).
$$

Việc xác minh trực tiếp dễ dàng chứng minh rằng phép cộng và nhân điểm có tính chất giao hoán và kết hợp:

$$
(a; b) + (c; d) = (c; d) + (a; b),
$$

$$
((a; b) + (c; d)) + (e; f) = (a; b) + ((c; d) + (e; f)),
$$

$$
(a; b) \cdot (c; d) = (c; d) \cdot (a; b),
$$

$$
((a; b) \cdot (c; d)) \cdot (e; f) =
= (a; b) \cdot ((c; d) \cdot (e; f)).
$$

Luật phân phối cũng được thỏa mãn:

$$
((a; b) + (c; d)) \cdot (e; f) =
= (a; b) \cdot (e; f) + (c; d) \cdot (e; f).
$$

Điểm (1; 0) đóng vai trò là đơn vị, tức là đối với bất kỳ điểm nào $(a; b)$

$$
(a; b) \cdot (1; 0) = (1; 0) \cdot (a; b) = (a; b).
$$

Và cuối cùng, với bất kỳ điểm $(a; b) \neq (0; 0)$ nào cũng có một điểm duy nhất $(x; y)$ sao cho

$$
(a; b) \cdot (x; y) = (1; 0).
$$

Hãy chứng minh tính chất cuối cùng. Hãy lấy một số điểm khác 0 $(a; b)$ (điều này đặc biệt có nghĩa là $a^2 + b^2 > 0$). Chúng ta cần tìm một điểm $(x; y)$ sao cho $(a; b) \cdot (x; y) = (1; 0)$. Nhưng

$$
(a; b) \cdot (x; y) = (ax - by; ay + bx).
$$

Từ đó ta thu được hệ phương trình

$$
ax - by = 1, ay + bx = 0.
$$

Giải hệ phương trình cho $x$ và $y$, ta tìm được

$$
x = \frac{ac + bd}{a^2 + b^2}, y = \frac{ad - bc}{a^2 + b^2}.
$$

Điều này đã chứng minh tất cả mọi thứ.

Vì vậy, chúng ta đã biến các điểm trong mặt phẳng thành một tập hợp số, tức là một tập hợp có các phép cộng và phép nhân trong đó tất cả các tính chất cộng và nhân của các số thực tổng quát đều đúng. Các số thực có trong tập hợp này là các điểm có dạng $(a; 0)$. Thực ra, việc cộng và nhân các điểm như vậy chỉ đơn giản là cộng và nhân các số thực:

$$
(a; 0) + (c; 0) = (a + c; 0),
$$

$$
(a; 0) \cdot (c; 0) = (ac; 0).
$$

⟦folio 51⟧

---
running_head:
folio:
---

Bây giờ hãy lấy điểm (0; 1). Hãy xem điều gì sẽ xảy ra nếu chúng ta bình phương nó, tức là nhân tổng với chính mình:
$(0; 1)^2 = (0; 1) \cdot (0; 1) = (-1; 0)$.
Do đó, $(0, 1)^2$ là một số thực - 1. Điều này có nghĩa là điểm (0, 1) có thể được hiểu là đơn vị tối thiểu $i$, từ đó loại bỏ bức màn thần bí khỏi nó. Cuối cùng, bất kỳ điểm $(a; b)$ nào cũng có thể được biểu diễn dưới dạng
$(a; b) = (a; 0) + (0; b) = (a; 0) + (b; 0) \cdot (0; 1)$.
Nếu $(a; 0)$ và $(b; 0)$ được biểu thị là số nguyên tố bởi $a$ và $b$ và $(0, 1)$ bởi $i$, thì chúng ta nhận được
$(a; b) = a + bi$.
tức là bây giờ biểu thức công thức $a + bi$ đã trở thành một cơ sở vững chắc - nó chỉ là một điểm có tọa độ $(a; b)$ trên mặt phẳng với các phép toán cộng (1) và nhân (2) ở trên.
Ngoài giá trị lý thuyết thuần túy, việc triển khai hình học của số phức còn có ý nghĩa thực tiễn quan trọng - với sự trợ giúp của nó, số phức có thể được biểu diễn dưới dạng lượng giác, thuận tiện trong nhiều ứng dụng.
Bài tập
9. Vẽ các số phức $2 + i, 1 + i, -1 - i, -3 - 2i$ dưới dạng các điểm trên mặt phẳng.
10. Chứng minh rằng tổng $z_1 + z_2$ của các số phức $z_1$ và $z_2$ được biểu thị bằng đỉnh thứ tư của hình bình hành có hai cạnh kề nhau là các đoạn nối các điểm $z_1$ và $z_2$ với điểm $O$.
11. Điểm $z_1, z_2, z_3$ là các đỉnh của tam giác trên mặt phẳng. Viết số biểu thị trọng tâm của tam giác này.

Dạng lượng giác của số phức

Ta xét hệ tọa độ $xOy$ trên mặt phẳng thẳng. Đặt điểm $P$ đại diện cho số phức $z = a + bi$ (hình 1).
Chúng ta hãy biểu thị khoảng cách $OP$ từ điểm $P$ đến gốc tọa độ bằng $r$ và bằng $\varphi$ góc (xem hình 1) được tạo bởi tia $OP$ với hướng dương của trục $Ox$ và vắng mặt ngược chiều kim đồng hồ $(0 < \varphi < 2\pi)$. (Tại hình 1, các góc $\varphi$ được hiển thị cho các trường hợp khác nhau về vị trí của điểm $P$.)
Từ định nghĩa của hàm lượng giác, suy ra rằng
$a = r \cos \varphi, b = r \sin \varphi$,

Hình 1.

⟦folio 52⟧

---
running_head:
folio:
---

$$z = r(\cos \varphi + i \sin \varphi).$$

Đây là dạng lượng giác của số phức. Đại lượng $OP = r$ được gọi là modum của số phức $z$ và được ký hiệu là $|z|$, còn độ lớn của góc $\varphi$ là đối số chính của số $z$ và được ký hiệu là arg $z$.

Vì $OP$ là cạnh huyền của tam giác nguyên $OAP$, nên
$$|z| = r = \sqrt{a^2 + b^2},$$
$$\arg z = \left\{ \begin{array}{l} \arccos \frac{a}{\sqrt{a^2 + b^2}} \text{ при } b \geqslant 0; \\ 2\pi - \arccos \frac{2}{\sqrt{a^2 + b^2}} \text{ при } b < 0. \end{array} \right.$$

Từ các công thức này, suy ra rằng $|z|$ được xác định duy nhất và bằng 0 khi và chỉ khi $z = 0$.

Đối số chính cho $z = 0$ không được xác định. Đối với $z \neq 0$, mọi góc khác với arg $z$ bởi một số hạng là bội số của $2\pi$ được gọi là đối số của $z$.

Ví dụ: vì arg $i = \frac{\pi}{2}$, nên tất cả các đối số của số $i$ đều có dạng $\frac{\pi}{2} + 2k\pi$. Tương tự, arg là $(-1) = \pi$ và tất cả các đối số khác là số $\pi(2k + 1)$.

Bài tập.
12. Tìm $|z|$ và lập luận $z$ nếu
a) $z = -2$; 6) $z = 1 + i$; b) $z = -1 - i$; c) $z = -i$; d) $z = 1 - i\sqrt{3}$; e) $z = -3 - 4i$.

13. Viết dạng lượng giác của các số
a) 1; 6) -1; b) 12 + 5i; c) 12 - 5i; d) -12 - 5i; e) $\sin \alpha + i \cos \alpha$ ($0 < \alpha < \pi$).

14. Chứng minh rằng khoảng cách giữa các điểm $z_1$ và $z_2$ là $|z_1 - z_2|$. Sử dụng công cụ này để vẽ các điểm trên mặt phẳng mà
a) $|z - i| = 1$; 6) $|z - 1| = |z + 1|$; b) $|z - i| = |iz - 1|$; c) $1 \leqslant |z - i| \leqslant 2$.

15. Vẽ các điểm trên mặt phẳng để
a) arg $iz = \pi/4$; b) arg $(iz - 1) = \pi/3$.

Tất cả các phép toán đại số với số phức được cho ở dạng lượng giác đều tuân theo các quy tắc giống như với số phức được cho ở dạng đại số. Việc cộng và trừ các số phức sẽ dễ dàng và thuận tiện hơn khi chúng được cho dưới dạng đại số và nhân chia dưới dạng lượng giác.

Định lý 1. Khi nhân một số hữu hạn số phức, modi của chúng sẽ chuyển đổi và các đối số cộng lại.

Bằng chứng. Hãy giới hạn bản thân ở hai yếu tố; trường hợp tổng quát có thể dễ dàng thu được bằng quy nạp. Vậy ta phải chứng minh rằng
$$(r_1(\cos \varphi_1 + i \sin \varphi_1)) \cdot (r_2(\cos \varphi_2 + i \sin \varphi_2)) = (r_1 r_2)(\cos (\varphi_1 + \varphi_2) + i \sin (\varphi_1 + \varphi_2)).$$

Nhưng
$$(\cos \varphi_1 + i \sin \varphi_1)(\cos \varphi_2 + i \sin \varphi_2) = (\cos \varphi_1 \cos \varphi_2 - \sin \varphi_1 \sin \varphi_2) + i(\cos \varphi_1 \sin \varphi_2 + \sin \varphi_1 \cos \varphi_2) = \cos (\varphi_1 + \varphi_2) + i \sin (\varphi_1 + \varphi_2),$$
từ đó có sự bình đẳng không chủ tọa (3). Vì $r_1 \geqslant 0, r_2 \geqslant 0$ ngụ ý rằng $r_1 r_2 \geqslant 0$, nên $r_1 r_2$ là mô đun và $\varphi_1 + \varphi_2$ là đối số của tích của hai số đã cho. Định lý đã được chứng minh.

Từ định lý này, suy ra rằng tích của số phức $z$ với số phức $a$ thu được từ điểm $z$ như sau: bạn cần xoay tia $Oz$ theo góc $\alpha = \arg a$ ngược chiều kim đồng hồ rồi lấy tia thu được một điểm cách xa $O$ một khoảng $|a| \cdot |z|$ (hình 2). Nói cách khác, phép biến đổi mặt phẳng lấy điểm vạn năng $z$ về điểm $az$ là

⟦folio 53⟧

---
running_head:
folio:
---

tích của phép quay theo góc $\alpha$ và sự chuẩn bị có hệ số $|a|$ và tâm $O$.

Bài tập 16. Chứng minh các đẳng thức sau

a) $|z|^2 = zz'$; 6) $\frac{z_1}{z_2} = \frac{z_1\bar{z}_2}{|z_2|^2}$;

b) $|z_1 + z_2| \leqslant |z_1| + |z_2|$ (tìm ra tại đó $z_1$ và $z_2$ sẽ bằng nhau);

d) $|z_1 + z_2|^2 + |z_1 - z_2|^2 = 2(|z_1|^2 + |z_2|^2)$.

Ý nghĩa hình học của điều này là gì?

Định lý 2. Khi chia số phức, mô đun của chúng được chia và các đối số bị trừ.

Chi tiết hơn,

$$\frac{r_1(\cos \varphi_1 + i \sin \varphi_1)}{r_2(\cos \varphi_2 + i \sin \varphi_2)} = \frac{r_1}{r_2}(\cos (\varphi_1 - \varphi_2) + i \sin (\varphi_1 - \varphi_2))$$.

Bằng chứng. Chuyển đổi một phân số

$$\frac{r_1(\cos \varphi_1 + i \sin \varphi_1)}{r_2(\cos \varphi_2 + i \sin \varphi_2)},$$

nhân tử số và mẫu số của nó với $\cos \varphi_2 - i \sin \varphi_2$. Kết quả là chúng tôi nhận được

$$\frac{r_1}{r_2} \cdot \frac{(\cos \varphi_1 + i \sin \varphi_1)(\cos \varphi_2 - i \sin \varphi_2)}{(\cos \varphi_2 + i \sin \varphi_2)(\cos \varphi_2 - i \sin \varphi_2)}$$.

Vì $i^2 = -1$ nên mẫu số của phân số thứ hai là $\cos^2 \varphi_2 + \sin^2 \varphi_2 = 1$. Tử số có thể được viết như sau:

$$(\cos \varphi_1 + i \sin \varphi_1)(\cos (-\varphi_2) + i \sin (-\varphi_2))$$.

Áp dụng quy tắc nhân, ta được

$$\cos (\varphi_1 - \varphi_2) + i \sin (\varphi_1 - \varphi_2)$$,

Q.E.D.

Khi các thừa số trùng nhau, Định lý 1 mang lại cái gọi là công thức Myabra

$$(r_1(\cos \varphi + i \sin \varphi))^n = r^n(\cos n\varphi + i \sin n\varphi).$$

Định lý 3. Cho $z$ là số phức và $n$ là số tự nhiên. Trong tập hợp số phức, biểu thức $\sqrt[n]{z}$ cho $z = 0$ có một giá trị duy nhất - 0 và đối với $z \neq 0$ - nó có các giá trị khác nhau. Nếu như

$$z = r(\cos \varphi + i \sin \varphi),$$

thì các giá trị này được tìm thấy theo công thức

$$\sqrt[n]{z} = \sqrt[n]{r} \left( \cos \frac{\varphi + 2\pi k}{n} + i \sin \frac{\varphi + 2\pi k}{n} \right),$$

$k = 0, 1, \dots, n - 1$.

Bằng chứng. Vì $0^n = 0$ và từ $z^n = 0$ nên suy ra $z = 0$.

Hãy để nó bây giờ

$$z = r(\cos \varphi + i \sin \varphi) \neq 0.$$

Ký hiệu $\rho$ và $\alpha$ là mô hình và đối số tương ứng của nghiệm, ta có

$$\sqrt[n]{r(\cos \varphi + i \sin \varphi)} = \rho(\cos \alpha + i \sin \alpha).$$

Do đó, theo công thức Myabra

$$r(\cos \varphi + i \sin \varphi) = \rho^n(\cos n\alpha + i \sin n\alpha).$$

Vì vậy, họ phải tuân thủ

$$\rho^n = r, n\alpha = \varphi + 2k\pi,$$

Ở đâu

$$\rho = \sqrt[n]{r}, \alpha = \frac{\varphi + 2k\pi}{n},$$

tức là

$$\sqrt[n]{z} = \sqrt[n]{r} \left( \cos \frac{\varphi + 2k\pi}{n} + i \sin \frac{\varphi + 2k\pi}{n} \right).$$

Chúng ta sẽ nhận được bao nhiêu giá trị khác nhau? Dễ dàng nhận thấy rằng nếu chúng ta thay thế các giá trị $k = 0, 1, 2, \dots, n - 1$ vào công thức cuối cùng, tất cả các giá trị thu được của gốc sẽ khác nhau, vì đối số của chúng sẽ khác nhau. Với $k = n$ chúng tôi nhận được

$$\frac{\varphi + 2\pi n}{n} = \frac{\varphi}{n} + 2\pi,$$

và gốc sẽ bằng nhau

$$\sqrt[n]{r} \left( \cos \left( \frac{\varphi}{n} + 2\pi \right) + i \sin \left( \frac{\varphi}{n} + 2\pi \right) \right) =$$

$$\sqrt[n]{r} \left( \cos \frac{\varphi}{n} + \sin \frac{\varphi}{n} \right),$$
