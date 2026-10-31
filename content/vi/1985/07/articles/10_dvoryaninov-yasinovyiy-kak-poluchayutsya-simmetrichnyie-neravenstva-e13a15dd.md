---
id: 1985-7-dvoryaninov-yasinovyiy-kak-poluchayutsya-simmetrichnyie-neravenstva-e13a15dd
issue: kvant_1985_7
year: 1985
number: "7"
title: Làm thế nào để có được bất đẳng thức đối xứng
authors:
  - Дворянинов С. В.
  - Ясиновый Э. А.
rubric: matematicheskiy-kruzhok
rubric_sub: Математический кружок
page_first: 35
page_last: 38
page_labels: 33-36
tag: M72N
lang: vi
source: kvant_digital
extraction: vision
content_sha256: 32db1d6a34bc7f8be4bd1b33ab60c5fdaca23a41f8f42c8c6410c2052703e71b
prompt_sha256: draft-1
translated_from: content/ru/1985/07/articles/10_dvoryaninov-yasinovyiy-kak-poluchayutsya-simmetrichnyie-neravenstva-e13a15dd.md
source_content_sha256: 2ecc0e7be04f5b48d586250e3deee13f6398c0fbc7d0d1cdd4f5d55d447b2ca1
translation_model: draft
translation_run: vi-draft-2026-10-31
translation_quality: draft
---

⟦folio 33⟧

Làm thế nào để có được bất đẳng thức đối xứng

Ứng viên Khoa học Vật lý và Toán học
S. V. DVORYANINOV,
Ứng viên khoa học sư phạm
E. A. YASINOVY

Trong nhiều bài toán đại số và giải tích, trong các kỳ thi Olympic toán và đôi khi trong các kỳ thi, có bài toán, trong đó bạn cần chứng minh bất đẳng thức với nhiều biến. Đơn giản nhất trong số đó có sẵn cho học sinh lớp 5-6. Nhiều nhà thống kê, đánh giá và chuyên khảo toán học tập trung vào các phương pháp chứng minh khác nhau và các định lý tổng quát về bất đẳng thức thay thế. Rất nhiều bài viết về bất đẳng thức đã được tích lũy trong danh mục “Vòng tròn toán học” của chúng tôi.

Ghi chú này mô tả định lý Muirhead về các bất đẳng thức liên quan đến đa thức đối xứng có dạng đặc biệt (tổng của tất cả các đa thức cùng năm có thể có cùng số mũ). Định lý này, được chứng minh vào năm 1903, đáng chú ý không chỉ vì tính tổng quát và tính hữu hạn của nó, mà còn vì thực tế là các khái niệm tổ hợp nảy sinh liên quan đến nó (“Sơ đồ trẻ” và sự so sánh của chúng - “đa số hóa”) sau khi xuất hiện một cách tự nhiên trong các nhánh khác nhau của toán học lý thuyết và ứng dụng đang phát triển tích cực trong thời gian gần đây.

Giới thiệu

Chúng ta sẽ giải quyết các bất đẳng thức loại này:

$$x^2 + y^2 \geq 2xy,$$
(1)
$$x^5 + y^5 \geq x^3y^2 + y^3x^2,$$
(2)
$$x^2 + y^2 + z^2 \geq xy + yz + zx,$$
(3)
$$x^3 + y^3 + z^3 \geq 3xyz,$$
(4)

$$x^2y^2 + y^2z^2 + z^2x^2 \geq x^2yz + y^2xz + z^2xy,$$
(5)
$$x^4 + y^4 + z^4 + w^4 \geq 4xyzw.$$
(6)

Những bất đẳng thức này có giá trị với tất cả các giá trị không âm của các chữ cái có trong chúng. Đối với trường hợp hai biến, cũng dễ dàng chứng minh các bất đẳng thức bằng cách nhóm các số hạng và phân tích chúng thành nhân tử. Ví dụ, chúng ta hãy chứng minh rằng với mọi bất đẳng thức x và y không âm (2) đều đúng. Để làm điều này, hãy xem xét sự khác biệt

$$x^5 + y^5 - x^3y^2 - y^3x^2 = x^3(x^2 - y^2) - y^3(x^2 - y^2) = (x^3 - y^3)(x^2 - y^2).$$

Sau đó, tích rõ ràng là không âm; cả hai dấu ngoặc không nhỏ hơn 0 đối với $x \geq y \geq 0$ và không lớn hơn 0 đối với $y \geq x \geq 0$.

Vollee khó đạt được chứng minh đối xứng của bất đẳng thức bằng vương miện hoặc một số lượng lớn biến. Hãy để chúng tôi chứng minh ý tưởng chung bằng cách sử dụng một ví dụ (5). Ở đây thật thuận tiện để gạch chéo tất cả các số hạng ở vế trái của bất đẳng thức, nhân chúng với 2 và tập hợp chúng thành ba nhóm:

$$x^2(y^2 - 2yz + z^2) + y^2(x^2 - 2xz + z^2) + z^2(x^2 - 2xy + y^2) = x^2(y - z)^2 + y^2(x - z)^2 + z^2(x - y)^2 \geq 0.$$

Bài tập 1. Chứng minh bất đẳng thức (1), (3) và (6).

Để học cách chứng minh tất cả các loại bất đẳng thức loại này và xây dựng một định lý tổng quát, bạn cần làm quen với các khái niệm mới không âm. Bây giờ chúng ta sẽ mô tả chúng.

Sự đối xứng của đơn thức

Chúng ta hãy có một số biến không âm - để định nghĩa, ba biến x, y và z. Ngoài ra, chúng ta hãy cho một tập hợp gồm các số nguyên không âm như nhau, $\alpha = (k; j; i)$, trong đó $k \geq j \geq i$; Hãy gọi chúng là một chỉ báo. Hãy vẽ một bảng gồm ba hình vuông và viết chỉ số tương ứng vào góc trên bên phải của mỗi hình. Chúng ta đặt ba chữ cái x, y, z vào các ô vuông này và nhìn vào bảng, viết đơn thức $x^k y^j z^i$. Bây giờ trong cùng một bảng, chúng ta thêm các biến vào một bảng khác

⟦folio 34⟧

Theo thứ tự; chẳng hạn, chúng ta thu được đơn thức sau $y^k x^j z^i$, v.v. (hình 1).
(Không khó để đếm xem chúng ta sẽ nhận được bao nhiêu đơn thức khác nhau. Bạn có thể đặt bất kỳ chữ cái nào trong ba chữ cái $x, y, z$ vào hình vuông đầu tiên - điều này mang lại ba tùy chọn; trong hình vuông thứ hai - bất kỳ chữ cái nào trong số hai chữ cái còn lại, vì vậy có tổng cộng các tùy chọn $3 \cdot 2 = 6$.) Sau đó cộng tất cả các đơn thức đã viết; đa thức kết quả trong ba biến $x, y, z$ sẽ được ký hiệu là $T_{(k,j,i)}(x,y,z)$, hoặc $T_u(x,y,z)$, hoặc đơn giản là $T_u$ (T - từ từ “bảng”). Như người ta nói, đa thức này sẽ “đối xứng”; nó không thay đổi với bất kỳ hoán vị nào của biến. Bậc của mỗi đơn thức của nó là $s=k+j+i$.

Ví dụ,

$$T_{(2;1;0)}(x, y, z) = x^2 y + y^2 x + z^2 x + x^2 z + z^2 y;$$

$$T_{(3;1;1)}(\dot{x}, y, z) = x^3 y z + y^3 x z + z^3 x y + x^3 z y + y^3 z x + z^3 y x;$$

$$T_{(2;2;2)}(x, y, z) = 6 x^2 y^2 z^2.$$

Hai ví dụ cuối cho thấy rằng khi có số mũ bằng nhau, các số hạng tương tự có thể được thêm vào đa thức $T_u$ và viết ngắn hơn.

Nếu bộ chỉ báo $\alpha = (\alpha_1, \alpha_2, \dots, \alpha_n)$ bao gồm $n$ số thì bạn cần vẽ một bảng có $n$ hình vuông và lấy $n$ biến $x_1, x_2, \dots, x_n$. Hơn nữa, trong đa thức $T_u(x_1, \dots, x_n)$ sẽ có $n! = 1 \cdot 2 \cdot \dots \cdot n$ đơn thức trước khi rút gọn các đơn thức tương tự.

Vì vậy, đối với mỗi bộ số nguyên $\alpha = (\alpha_1; \alpha_2; \dots; \alpha_n)$, trong đó $\alpha_1 \geqslant \alpha_2 \geqslant \alpha_3 \geqslant \dots \geqslant \alpha_n \geqslant 0$ tương ứng với đa thức $T_u$ là sự “đối xứng” của một đơn thức với số mũ $\alpha_1, \alpha_2, \dots, \alpha_n$.

Chúng tôi sẽ mô tả mỗi bộ $\alpha$ như vậy dưới dạng một bậc thang gồm $n$ bước: chiều cao của mỗi bước bằng chỉ báo tương ứng, chiều rộng là một. Thật thuận tiện khi vẽ một cái thang như vậy trên giấy ca rô; tổng số ô - “gạch” $1 \times 1$, trong đó có bậc thang, bằng $s = \alpha_1 + \dots + \alpha_n$ - bậc của đa thức $T_u$. hình 2 hiển thị các bậc thang tương ứng với một số đa thức $T_u$ gặp phải trong các bất đẳng thức của chúng ta.

Tên khoa học của những bậc thang này, rất hữu ích trong các bài toán tổ hợp, đại số và giải tích khác nhau, là “Biểu đồ trẻ” (xem [3]).

Bài tập 2. Viết các đa thức $T_u$ và vẽ các bậc thang tương ứng của chúng cho các tập hợp sau $\alpha$: (3, 2); (3, 2, 1); (3, 3, 0, 0); (4, 1, 1, 0); (5, 0, 0, 0, 0); (1, 1, 1, 1, 1).

So sánh sơ đồ Young

hình 3 hiển thị các cặp bậc thang tương ứng với các bất đẳng thức (1)–(6) từ phần giới thiệu. Chúng ta thấy rằng đa thức lớn hơn trong hai đa thức tương ứng với bậc thang lớn hơn: đa thức thứ hai, phẳng hơn, có thể thu được từ đa thức thứ nhất bằng cách nối nhiều kippei với bên phải - xuống (xem hình 4). Chúng ta hãy trình bày chính xác hơn ý nghĩa của từ “lớn hơn” ở đây, trước tiên là đối với cầu thang ba bậc.

Đặt $\alpha = (\alpha_1; \alpha_2; \alpha_3)$ và $\beta = (\beta_1; \beta_2; \beta_3)$ là hai tập hợp số nguyên có cùng tổng $s = \alpha_1 + \alpha_2 + \alpha_3 = \beta_1 + \beta_2 + \beta_3; \alpha_1 \geqslant \alpha_2 \geqslant \alpha_3 \geqslant 0$ và $\beta_1 \geqslant \beta_2 \geqslant \beta_3 \geqslant 0$. Chúng tôi sẽ giả định rằng $\alpha > \beta$ (và tối đa hóa $\beta$), nếu điều kiện sau được thỏa mãn:

$\beta$ có thể nhận được từ $\alpha$ bằng cách tiếp tục nhiều lần (có thể

⟦folio 35⟧

Chỉ có một phần giữa các bộ - điều đó xảy ra là hai bộ có tổng bằng nhau không thể so sánh được (xem bài tập 6).

Bài tập

3. Kiểm tra xem các cặp biểu đồ Young trên hình 3 có thỏa mãn các điều kiện (*) và (**) hay không.

4. Chứng minh điều kiện (*) và (**) tương đương (nghĩa là nếu bất đẳng thức (**) thỏa mãn thì tập β có thể thu được từ α “bằng cách đổ gạch” và ngược lại).

5. Vẽ tất cả các bậc thang bằng s=4 viên gạch theo thứ tự giảm dần, bắt đầu từ dốc nhất (4;0;0;0) và kết thúc bằng phẳng nhất (1;1;1;1); tương tự đối với thang 5 viên gạch.

6. a) Kiểm tra xem các biểu đồ Young (4;1;1) và (3;3;0) có thể so sánh được không – cả hai biểu đồ này đều không tối đa hóa biểu đồ kia. Có tập hợp nào khác có tổng bằng 6 không?

6) Tìm tất cả các cặp tập hợp như vậy với s=7.

**Định lý Muirhead**

Bây giờ mọi thứ đã sẵn sàng để hình thành định lý chính.

Đặt α=(α1;α2;...;αn) và β=(β1;β2;...;βn) là hai bộ chỉ tiêu có tổng bằng nhau. Nếu α>β thì với mọi x1, x2, ..., xn không có tổ chức
Tα(x1, x2, ..., xn)>Tβ(x1, x2, ..., xn).
Ngược lại, nếu bất đẳng thức như vậy đúng thì α>β.

Chúng tôi sẽ không đưa ra cách chứng minh mang tính công thức cho định lý ở dạng tổng quát (có thể tìm thấy nó trong sách [1], [2] - cuốn thứ hai hoàn toàn dành cho các phiên bản khác nhau của mối quan hệ “cực đại hóa”, các ứng dụng và khái quát hóa của nó), mà thay vào đó chúng tôi sẽ mô tả các ý chính của nó và chứng minh chúng bằng các ví dụ cụ thể.

Chứng minh phần thứ hai của định lý—sự cần thiết của điều kiện α>β—suy ra từ một thực tế đơn giản là trong hai đa thức trong một biến t (có hệ số dẫn đầu dương), đối với các giá trị lớn của t thì giá trị nào có bậc càng lớn thì lớn hơn (xem Bài tập 8).

Chứng minh tính thỏa mãn của điều kiện α>β dựa trên hai ý tưởng. Đầu tiên là “đổ gạch”: hai tập hợp α>β có thể được nối bằng một số nguyên các tập hợp sao cho các tập hợp lân cận trong số nguyên này chỉ khác nhau hai vị trí, sao cho từ mỗi tập hợp này sang tập hợp tiếp theo có thể di chuyển, “đổ một viên gạch” từ bước này sang bước khác trên thang tương ứng. Thứ hai là “nhóm đối xứng”: hiệu của đa thức cho các tập lân cận có thể được viết dưới dạng tổng (trên tất cả các tham số x, y) của các nhóm giống hệt nhau có dạng
(xp+r yq+p r xq−p r yq+p r)Z
(xem hình 5), trong đó Z là tích của các biến còn lại tương ứng với các chỉ số giống nhau trong các tập lân cận. Lần cuối cùng bạn-

⟦folio 36⟧

Hình 5.

sự phân rã được phân hủy thành một tập hợp và, như dễ thấy, đối với $p > q$, $r \geq 0$, nó không âm. (Kiểm tra!)
Tất cả điều này sẽ trở nên rõ ràng đối với những người cẩn thận, viết ra tất cả các tính toán một cách chi tiết, phân tích một số ví dụ. Chúng tôi sẽ cung cấp cho hai.

Bất đẳng thức giữa trung bình số học và trung bình hình học của ba số không âm

$$\frac{a_1 + a_2 + a_3}{3} \geq \sqrt[3]{a_1 a_2 a_3}$$

sau khi thiết kế lại $a_1 = x^3$, $a_2 = y^3$, $a_3 = z^3$ biến thành bất đẳng thức (4), đã được đề cập ở trên. Hãy để chúng tôi chứng minh điều đó bằng phương pháp của Muirhead. Xét hình 4 a), ta thấy cần chứng minh hai bất đẳng thức:

$$T_{(3; 0; 0)}(x, y, z) \geq \geq T_{(2; 1; 0)}(x, y, z)$$

Hãy xem xét điều đầu tiên trong số đó và tạo nên sự khác biệt

$$R_1 = T_{(3; 0; 0)}(x, y, z) - T_{(2; 1; 0)}(x, y, z) = 2(x^3 + y^3 + z^3) - x^2y - y^2z - z^2x - x^2z - y^2x - z^2y.$$

Bây giờ chúng ta hãy nhóm các số hạng thành bốn theo nguyên tắc sau: với mỗi cặp biến, một nhóm bao gồm các số hạng trong đó chỉ số của các biến này thay đổi từ (3, 0) thành (2, 1) (và chỉ số tổng thể trong các bộ ở đây 0 nằm ở vị trí cuối cùng). chúng tôi nhận được

$$R_1 = (y^3 + z^3 - y^2z) + (x^3 + y^3 - x^2y - y^2x) + (z^3 + x^3 - z^2x - x^2z) = (y^2 - z^2)(y - z) + (x^2 - y^2)(x - y) + (z^2 - x^2)(z - x) \geq 0$$

với mọi số không âm $x, y, z$.

Bây giờ hãy chứng minh bất đẳng thức thứ hai

$$R_2 = T_{(2; 1; 0)}(x, y, z) - T_{(1; 1; 1)}(x, y, z) = x^2y + y^2z + z^2x + x^2z + y^2z - 6xyz.$$

Ở đây, trong số mũ, đơn vị chung đứng ở vị trí thứ hai và (2; 0) biến thành (1, 1). Theo điều này, chúng tôi nhận được:

$$R_2 = x(y^2 + z^2 - 2yz) + y(z^2 + x^2 - 2zx) + z(y^2 + z^2 - 2yz) = x(y - z)^2 + y(z - x)^2 + z(x - y)^2 \geq 0.$$

Điều này chứng tỏ sự bất đẳng thức (4).

Lời giải bài toán M762.

Trong bài toán này (từ “Bài toán Kvant Số 9, 1982) cần phải chứng minh bất đẳng thức cho $a, b, c$ dương

$$a + b + c \leq \frac{a^2 + b^2}{2c} + \frac{b^2 + c^2}{2a} + \frac{c^2 + a^2}{2b} \leq \frac{a^3}{bc} + \frac{b^3}{ca} + \frac{c^3}{ab}.$$

Người đọc đã đề xuất một số phương pháp khác nhau cho lời giải của họ. Một trong số đó là phương pháp Muirhead (chúng tôi hy vọng sẽ quay lại với những người khác ở một trong các số sau «Kvant»). Bằng cách nhân các bất đẳng thức này với 2abc, chúng ta rút gọn chúng về dạng “Mirhead” sau:

$$2(a^4 + b^4 + c^4) \geq \geq a^3b + b^3a + b^3c + c^3a + a^3c,$$

$$a^3b + b^3a + b^3c + c^3a + a^3c \geq 2(a^2bc + b^2ac + c^2ab).$$

Các sơ đồ Young tương ứng được hiển thị trong hình 4, 6. Sự khác biệt giữa bên trái và bên phải của mỗi bất đẳng thức có thể được viết, như trên, dưới dạng tổng của ba nhóm bốn năm. Để tiết kiệm chỗ, chúng ta sẽ chỉ viết một nhóm - hai nhóm còn lại có được bằng cách thay thế chữ cái $a, b, c$ bằng $b, c, a$ và $c, a, b$.

Chứng minh (7):

$$(a^4 + b^4 - a^3b - b^3a) + \dots = (a^3 - b^3)(a - b) + \dots \geq 0.$$

Chứng minh (8):

$$(a^3b + c^3b - a^2cb - c^2ab) + \dots = b(a^2 - c^2)(a - c) + \dots \geq 0.$$

Như vậy, bài toán M762 đã được giải quyết.

Thêm một vài bài tập và bài toán để khám phá

7. Viết tất cả các bất đẳng thức Muirhead cho đa thức bậc 4.

8. a) Đặt $T_{(a_1; a_2; a_3)}(x, y, z) \geq T_{(\beta_1; \beta_2; \beta_3)}(x, y, z)$ với mọi số không âm $x, y, z$. Chứng minh rằng khi đó bất đẳng thức (**) được thỏa mãn. (Chỉ ra. Xét một số trường hợp: $x = y = z = t; x = y = t, z = 1; x = t, y = z = 1$ và so sánh bậc của các đa thức thu được từ $t$.)

9. Chứng minh các bất đẳng thức sau (với $x, y, z, v, w$ không âm):

a) $x^4y^2z + y^4x^2z + z^4yx^2 + x^4z^2y + z^4x^2y \geq 2(x^3y^2z + y^3z^2x + z^3x^2y^2);$

b) $x^5 + y^5 + z^5 \geq x^2y^2z + y^2z^2x + z^2x^2y;$

b) $x^3 + y^3 + z^3 + v^3 \geq xyz + xyv + xzv + yzv.$

10. Suy ra từ các bất đẳng thức định lý Muirhead cho số trung bình số học và hình học $n$ các số không âm.

Bạn cần phải hạ bao nhiêu “viên gạch” để chuyển từ một tập hợp $(n, 0, 0, \dots, 0)$ gồm $n$ số sang một tập hợp (1, 1, ..., 1)?

11. Hình thành và chứng minh định lý Muirhead cho mọi số mũ không âm (không nhất thiết là số nguyên).

12. Đối với một số tập hợp số mũ (có tổng chẵn $s$), bất đẳng thức thảo luận trong định lý Muirhead là đúng với tất cả, không chỉ với các giá trị không âm của các biến. Hãy cố gắng mô tả tất cả các trường hợp như vậy.

Văn học

1. Hardy G. G., Littelwood D. E., Polina G. Bất bình đẳng - M.: IL, 1948.
2. Marshall A., Olkin I. Bất bình đẳng: lý thuyết tối đa hóa và các ứng dụng của nó. - M.: Mir, 1983.
3. Olympic toán tương ứng (bài toán 5-9). - M.: Nauka, 1981.
