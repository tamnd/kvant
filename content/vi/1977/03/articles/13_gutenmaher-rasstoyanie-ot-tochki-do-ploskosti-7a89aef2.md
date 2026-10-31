---
id: 1977-3-gutenmaher-rasstoyanie-ot-tochki-do-ploskosti-7a89aef2
issue: kvant_1977_3
year: 1977
number: "3"
title: Khoảng cách từ điểm tới mặt phẳng
authors:
  - Гутенмахер В. Л.
rubric: po-stranitsam-shkolnyh-uchebnikov
rubric_sub: По страницам школьных учебников
page_first: 40
page_last: 41
page_labels: 38-39
tag: KY12
lang: vi
source: kvant_digital
extraction: vision
content_sha256: d7de4252053cec6bb0c46bd505f1b54c6f68042edfb3cf8d1d6cbe7f80bb1fb5
prompt_sha256: draft-1
translated_from: content/ru/1977/03/articles/13_gutenmaher-rasstoyanie-ot-tochki-do-ploskosti-7a89aef2.md
source_content_sha256: fca9d8c596f91f2b96ee674d575ce1fe36d0df7a029d85f3b3a35d4d9cdeed7c
translation_model: draft
translation_run: vi-draft-2026-10-31
translation_quality: draft
---

⟦folio 38⟧

V. Gutenmacher

Khoảng cách từ điểm tới mặt phẳng

Có một số bài toán trong sách giáo khoa Hình học 10 yêu cầu bạn tìm khoảng cách từ một điểm cho trước đến một mặt phẳng cho trước. Thật kỳ lạ, những bài toán này lại gây ra một số khó khăn cho học sinh (mặc dù thực tế là một trong những bài toán này - Số 28, trang 10 - đã được giải quyết trong văn bản). Vì vậy, chúng tôi sẽ nói về vấn đề này chi tiết hơn một chút.

Công thức mới

Đặt $A(x_0; y_0; z_0)$ là một điểm trong không gian tọa độ $Oxyz$ và $\alpha$ là mặt phẳng được xác định bởi phương trình $ax+by+cz+d=0$. Khoảng cách $\rho(A, \alpha)$ từ điểm $A$ đến mặt phẳng $\alpha$ được tính theo công thức

$$\rho(A, \alpha) = \frac{|ax_0+by_0+cz_0+d|}{\sqrt{a^2+b^2+c^2}}.$$

Công thức này có thể được mô tả như sau:

Cần thay tọa độ của điểm $A$ vào biểu thức $ax+by+cz+d$ thay cho các biến $x, y, z$. Lấy mô đun của số kết quả và chia cho số $\sqrt{a^2+b^2+c^2}$.

Đạo hàm của công thức

Đạo hàm của công thức (*) về cơ bản lặp lại lời giải bài toán Số 28 ở trang 28. 10-11 SGK “Hình học 10”.

Chúng ta thả từ điểm $A(x_0; y_0; z_0)$ giới hạn xuống mặt phẳng $\alpha$, cho bởi phương trình $ax+by+cz+d=0$; gọi $B$ là giao điểm của phần tràn này với mặt phẳng $\alpha$; thì $|AB|$ là khoảng cách từ $A$ đến $\alpha$ (xem hình). Chúng ta hãy biểu thị bằng $(x_1; y_1; z_1)$ tọa độ của điểm $B$; Sau đó

$$\overrightarrow{AB} = \overrightarrow{OB} - \overrightarrow{OA} = (x_1-x_0; y_1-y_0; z_1-z_0),$$

Ở đâu

$$|AB| = |\overrightarrow{AB}| = \sqrt{(x_1-x_0)^2 + (y_1-y_0)^2 + (z_1-z_0)^2}.$$

Vì vectơ $\overrightarrow{AB}$ vuông góc với mặt phẳng $\alpha$ nên nó thẳng hàng với vectơ $\vec{n}$ có ​​tọa độ $(a; b; c)$.

Điều này có nghĩa là có một số $p$ sao cho

$$\overrightarrow{AB} = p \cdot \vec{n}.$$

(1)

Từ đẳng thức này suy ra rằng

$$x_1-x_0 = p \cdot a, \quad y_1-y_0 = p \cdot b, \quad z_1-z_0 = p \cdot c.$$

(2)

Như vậy,

$$|AB| = \sqrt{p^2a^2 + p^2b^2 + p^2c^2} = |p| \cdot \sqrt{a^2 + b^2 + c^2}.$$

Tất cả những gì còn lại là tìm số $|p|$. Vì điểm $B$ thuộc mặt phẳng $\alpha$ nên $ax_1+by_1+cz_1+d=0$. Vì $x_1=x_0+pa, y_1=y_0+pb, z_1=z_0+pc$ (xem phần tương ứng (2)), với $p$ ta thu được phương trình

$$a(x_0+pa) + b(y_0+pb) + c(z_0+pc) + d=0,$$

từ đó $|p|$ được tìm thấy:

$$|p| = \frac{|ax_0+by_0+cz_0+d|}{a^2+b^2+c^2}.$$

⟦folio 39⟧

Thay thế giá trị tìm được $|p|$ vào giá trị tương ứng (3), chúng ta thu được công thức mong muốn:

$$\rho(A, \alpha) = |AB| = \frac{|ax_0 + by_0 + cz_0 + d|}{\sqrt{a^2 + b^2 + c^2}}.$$

Công thức (*) cho phép bạn dễ dàng giải bất kỳ bài toán nào để tính khoảng cách từ một điểm đến một mặt phẳng. Hãy đưa ra một vài ví dụ.

Bài tập
Bài toán 1 (*). Tìm khoảng cách từ điểm $A(-1; 3; 0)$ đến mặt phẳng $\alpha$ cho bởi phương trình $x - 3y - 2z + 5 = 0$.

Lời giải. Áp dụng công thức (*) ta có:

$$\rho(A, \alpha) = \frac{|-1 - 3\cdot3 - 2\cdot0 + 5|}{\sqrt{1 + 3^2 + 2^2}} = \frac{|-5|}{\sqrt{14}} = \frac{5}{\sqrt{14}}.$$

Bài toán 2**). Tính khoảng cách từ gốc đến mặt phẳng $2x + 3y - 6z + 14 = 0$.

Lời giải. Chúng ta cần tìm khoảng cách từ điểm $A(0; 0; 0)$. Áp dụng công thức (*) ta có:

$$\rho(A, \alpha) = \frac{|2\cdot0 + 3\cdot0 - 6\cdot0 + 14|}{\sqrt{2^2 + 3^2 + 6^2}} = \frac{14}{7} = 2.$$

Bài toán 3. Tính khoảng cách giữa các mặt phẳng $\alpha$ và $\beta$ cho theo phương trình tương ứng:

$$3x + 2y + 4z + 11 = 0$$

Và

$$9x + 6y + 12z - 5 = 0.$$

Chia cả hai vế của phương trình thứ hai cho 3, ta thấy các mặt phẳng $\alpha$ và $\beta$: $3x + 2y + 4z + 11 = 0$ và $3x + 2y + 4z - \frac{5}{3} = 0$ song song với nhau.

Lấy điểm bất kỳ $A(x_0; y_0; z_0)$ thuộc mặt phẳng $\beta$: đặt, ví dụ: $x_0 = y_0 = 0$, sau đó $z_0 = \frac{5}{12}$.

*) Đây là bài toán Số 298.1) từ sách giáo khoa “Hình học 10”. Có một lỗi đánh máy trong sách giáo khoa—được đưa ra đáp số không chính xác.
**) Đây là bài toán Số 29.2) từ cùng một cuốn sách giáo khoa.

Dễ hiểu là khoảng cách giữa các mặt phẳng $\alpha$ và $\beta$ bằng số $\rho(A, \alpha)$, trong đó $A = \left(0; 0; \frac{5}{12}\right)$. Áp dụng công thức (*), ta có

$$\rho(\alpha, \beta) = \rho(A, \alpha) = \frac{|3\cdot0 + 2\cdot0 + 4\cdot\frac{5}{12} + 11|}{\sqrt{3^2 + 2^2 + 4^2}} = \frac{38}{3\sqrt{29}}.$$

Quét. Trong trường hợp tổng quát, khoảng cách giữa các mặt phẳng song song $\alpha$ và $\beta$:

$$ax + by + cz + d_1 = 0$$

Và

$$ax + by + cz + d_2 = 0$$

được tìm thấy bởi công thức

$$\rho(\alpha, \beta) = \frac{|d_1 - d_2|}{\sqrt{a^2 + b^2 + c^2}}.$$

Suy ra công thức (**) bằng cách lặp lại lời giải bài toán 3.

Tóm lại, chúng tôi cung cấp cho bạn một số bài toán.

Bài tập 1. Tính khoảng cách từ điểm $A(1; 1; 1)$ đến mặt phẳng $x + y + z = 0$.

2. Tính khoảng cách từ điểm $A(1; 2; 3)$ đến mặt phẳng $x + y + z - 6 = 0$.

3. Tìm khoảng cách từ điểm $A(x_0; y_0; 0)$ đến mặt phẳng $ax + by + d = 0$.

4. Tìm phương trình của mặt phẳng nằm cách mặt phẳng $x + y + z = 0$ một khoảng 1.

5. Biết rằng trong một tam giác paramid mọi góc phẳng ở đỉnh đều là góc vuông. Tìm độ dài chiều cao của nó nếu độ dài các cạnh bên của nó là $a, b$ và $c$.
