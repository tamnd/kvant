---
id: 1981-4-vaguten-formula-ploschadi-5e6826df
issue: kvant_1981_4
year: 1981
number: "4"
title: công thức diện tích
authors:
  - Вагутен Н.
rubric: matematicheskiy-kruzhok
rubric_sub: Математический кружок
page_first: 19
page_last: 21
page_labels: 17-19
tag: BY2X
lang: vi
source: kvant_digital
extraction: vision
content_sha256: 616e33c78b68482663241a87489d9b583661bf9cbe69fa3842fd22943d1ceb54
prompt_sha256: draft-1
translated_from: content/ru/1981/04/articles/06_vaguten-formula-ploschadi-5e6826df.md
source_content_sha256: 5812822130cbbe528ec6c38317cb9c656168da519680c30e27d3189d2c8940e3
translation_model: draft
translation_run: vi-draft-2026-10-31
translation_quality: draft
---

⟦folio 17⟧

vòng tròn toán học

N. Vaguten

công thức diện tích

Trong bài viết này, chúng ta sẽ thảo luận về một công thức hữu ích biểu thị diện tích của một đa giác theo tọa độ các đỉnh của nó. Khi chuẩn bị bài viết, A. Startsev đã được sử dụng, thêm vào «Kvant» vào năm 1970 (khi tác giả vẫn còn là một cậu học sinh).

sự kết hợp nho

Chúng ta hãy cho một đa giác nằm trong hình vuông dương $x > 0, y > 0$ và cũng lồi. Phần bên trong của các đỉnh ngược chiều kim đồng hồ là: $A_1(x_1; y_1), A_2(x_2; y_2)$, ..., như trong Hình 1, trong đó số đỉnh là $n = 5$. Chúng ta thả các đường vuông góc $A_1H_1, A_2H_2$, ..., $A_nH_n$ từ tất cả các đỉnh đến trục $x$; độ dài của chúng là $y_1, y_2, ..., y_n$.

Diện tích của quả nho $A_kH_kH_{k+1}A_{k+1}$ bằng modulo của sản phẩm $(y_k+y_{k+1})(x_k-x_{k+1})/2$. Tích này dương cho $x_k > x_{k+1}$ và âm cho $x_k < x_{k+1}$ (ở đây $k$ là một trong các số 1, 2, ..., $n$ và số $n+1$ theo sau $n$ phải được thay thế bằng 1). Đáng chú ý, hóa ra tổng của tất cả $n$ các tích cùng loại như vậy hoàn toàn bằng diện tích của đa giác $A_1A_2...A_n$.

Ví dụ, đối với hình ngũ giác trong Hình 1 tính từ gót chân sản phẩm

$$\frac{(y_1+y_2)(x_1-x_2)}{2}, \frac{(y_2+y_3)(x_2-x_3)}{2}, \frac{(y_3+y_4)(x_3-x_4)}{2}, \frac{(y_4+y_5)(x_4-x_5)}{2}, \frac{(y_5+y_1)(x_5-x_1)}{2}$$

tri, tương ứng với các cạnh trên (màu xanh), là dương và hai, tương ứng với các cạnh dưới (màu đỏ), là âm; Bằng cách trừ tổng diện tích của các hình thang màu đỏ khỏi tổng diện tích của các hình thang màu xanh, chúng ta tìm được diện tích của hình ngũ giác.

Tổng kết quả có thể được đơn giản hóa phần nào bằng cách giảm tích $x_1y_1, x_2y_2$, ..:

$$S = \frac{(y_1+y_2)(x_1-x_2)}{2} + \frac{(y_2+y_3)(x_2-x_3)}{2} + \frac{(y_3-y_4)(x_3-x_4)}{2} + \frac{(y_4+y_5)(x_4-x_5)}{2} + \frac{(y_5+y_1)(x_5-x_1)}{2} = \frac{(x_1y_2-x_2y_1) + (x_2y_3-x_3y_2) + ... + (x_5y_1-x_1y_5)}{2}.$$

1. Suy ra công thức tính diện tích hình lồi $n$-giác cho mọi $n$.

Công thức cơ bản

Vậy diện tích $S$ của hình lồi $n$-giác có các đỉnh $A_k(x_k; y_k)$, $k = 1, 2, ..., n$ bằng

$$\frac{1}{2} \left[ (x_1y_2-x_2y_1) + (x_2y_3-x_3y_2) + ... + (x_ny_1-x_1y_n) \right].$$

Biểu thức $ad-bc$ phổ biến trong toán học đến mức một ký hiệu đặc biệt $|a|^2 b|^2$ và tên “định thức” đã được sử dụng cho nó.

Cơm. 1.

⟦folio 18⟧

Cơm. 2. Tích của các số nối với nó bằng một đoạn được lấy bằng dấu + và màu đỏ - bằng dấu -.

bậc hai"; Sử dụng các định thức như vậy, công thức diện tích có thể được viết gọn hơn:

$$S = \frac{\left| x_1 x_2 \right| + \left| x_2 x_3 \right| + \ldots + \left| x_n x_1 \right|}{2}.$$

(Để điền công thức (1), Hình 2 là thuận tiện. Lưu ý rằng công thức (1) giả định rằng các đỉnh được đánh số ngược chiều kim đồng hồ.)

2. Kiểm tra xem nếu bạn đánh số các đỉnh theo thứ tự ngược lại theo chiều kim đồng hồ thì mỗi dấu ngoặc đơn tương ứng với một cạnh cụ thể của đa giác: $A_1 A_2$, $A_2 A_3$, ..., $A_n A_1$, đổi dấu. Hiệu ứng tương tự sẽ xảy ra nếu bạn đặt các ký hiệu trục tùy chỉnh vào các vị trí - thay đổi hướng của mặt phẳng.

Để không phải lo lắng về hướng này hay hướng khác trong việc đánh số các đỉnh, bạn có thể đặt dấu mô đun cùng với dấu ngoặc vuông trong công thức (1). Công thức kết quả

$$S = \frac{1}{2} \left| \sum_{k=1}^{n} \left(x_k y_{k+1} - x_{k+1} y_k\right) \right|$$

thích hợp cho bất kỳ dịp nào. (Hãy nhớ lại rằng $y_{n+1}$ và $x_{n+1}$ nên được thay thế bằng $y_1$ và $x_1$.)

Lưu ý rằng cho đến nay chúng ta đã coi tất cả tọa độ của các đỉnh của đa giác là dương và bản thân đa giác đó là lồi. Sẽ rất đáng thất vọng và ngạc nhiên nếu công thức của chúng ta hóa ra chỉ đúng với một giả định bổ sung như vậy. May mắn thay, điều này không xảy ra: công thức này đúng cho mọi đa giác trên mặt phẳng. Chúng ta sẽ thảo luận cách chứng minh điều đó cho đa giác không lồi bên dưới, trong Bài tập 13 (xem thêm ghi chú của S. Sefibkov ở trang 20). Bây giờ chúng ta sẽ loại bỏ giả định rằng đa giác nằm bên trong góc $x > 0$, $y > 0$.

3. Kiểm tra xem vế phải của công thức (2) không thay đổi nếu:

a) thay thế mỗi $x_k$ bằng $x_k + a$;
b) thay thế mỗi $y_k$ bằng $y_k + b$.

Chúng ta có thể chuyển song song bất kỳ đa giác $A_1 A_2 \ldots A_n$ nào sang một số vectơ $(a; b)$ vào góc $x > 0$, $y > 0$. Trong trường hợp này, tọa độ các đỉnh của nó thay đổi, nhưng diện tích của nó - phần bên trái của công thức (2) cũng như phần bên phải của công thức này - đều không thay đổi. Vì đẳng thức (2) đúng khi thu được đa giác có tọa độ đỉnh dương nên nó cũng đúng với đa giác ban đầu $A_1 A_2 \ldots A_n$.

4. Sử dụng công thức (2), tính diện tích các hình tứ giác có đỉnh:
a) $(0; 0), (0; 1), (1; 0), (1; 1)$;
b) $(0; 0), (-1; 1), (2; 3), (1; 2)$;
b) $(0; 5), (3; 0), (0; -4), (2; 0)$. Kiểm tra đáp số bằng cách tìm khu vực này theo cách khác.

5. a) Viết công thức tính diện tích tam giác có đỉnh $(0; 0), (a; b), (c; d)$.
b) Trong điều kiện nào thì ba điểm $(x_1; y_1), (x_2; y_2)$ và $(x_3; y_3)$ cùng nằm trên một đường thẳng?

Kết hợp tam giác
Công thức chính (2) có thể được rút ra theo cách khác - sao cho ý nghĩa hình học của mỗi thuật ngữ $(x_k y_{k+1} - x_{k+1} y_k)/2$ sẽ rõ ràng (lưu ý rằng nó chỉ bao gồm tọa độ của hai điểm lân cận $A_k$ và $A_{k+1}$). Chúng ta vẫn có thể giả định rằng $x_k > 0$, $y_k > 0$.

Hóa ra biểu thức $(x_k y_{k+1} - x_{k+1} y_k)/2$ bằng $OA_k A_{k+1}$ theo mô hình tam giác và là dương nếu đoạn $OA_k+1$ tạo một góc lớn hơn với trục $x$ so với $OA_k$ và âm nếu nhỏ hơn.

6. Đặt $B(x_1; y_1)$ và $C(x_2; y_2)$ là hai điểm có tọa độ dương và $y_1/x_1 < y_2/x_2$. Khi đó diện tích hình bình hành $OBDC$ (Hình 3) bằng $x_1 y_2 - x_2 y_1$.

Bây giờ rõ ràng là tổng của các số hạng $n$ $(x_k y_{k+1} - x_{k+1} y_k)/2$ sẽ cho diện tích cần thiết của $n$-gon (xem Hình 4): từ tổng diện tích của các hình tam giác màu đen, chúng ta trừ tổng diện tích của các hình tam giác màu đỏ - chúng ta đã gặp phải sự trùng hợp thành công này của các dấu hiệu trong cuộc thảo luận về hình thang).

7. Kiểm tra xem ý nghĩa hình học của biểu thức $x_1 y_2 - x_2 y_1$ đối với các điểm $B(x_1; y_1)$, $C(x_2; y_2)$ với tọa độ của bất kỳ dấu hiệu nào là

⟦folio 19⟧

Cơm. 3.

diện tích định hướng của hình bình hànhOBDC, được xây dựng trên các vectơ $\vec{OB}$ và $\vec{OC}$*): diện tích của OBDC được lấy bằng dấu “cộng” nếu hướng $\vec{OC}$ được lấy từ hướng $\vec{OB}$ bằng cách quay ngược chiều kim đồng hồ (ở một góc không quá 180°) và “trừ” nếu theo chiều kim đồng hồ.

Bổ sung bài toán và nhận xét
Để kết luận, chúng tôi đề xuất chứng minh thêm một số phát biểu liên quan đến công thức tính diện tích đa giác, các chứng minh và khái quát hóa của nó.

8. Đối với hai vectơ $\vec{b} = \vec{OB}$, $\vec{c} = \vec{OC}$ trên mặt phẳng, chúng ta sẽ biểu thị diện tích định hướng của hình bình hànhOBDC (Bài tập 7) bằng $\vec{b} \wedge \vec{c}$.

Sau đó, với mọi vectơ $\vec{a}, \vec{b}, \vec{c}$ và bất kỳ số $\lambda$ nào, các đẳng thức sau giữ nguyên:
$$1^0. \vec{a} \wedge \vec{b} = -(\vec{b} \wedge \vec{a}).$$
$$2^0. \lambda \vec{a} \wedge \vec{b} = \vec{a} \wedge (\lambda \vec{b}) = \lambda (\vec{a} \wedge \vec{b}).$$
$$3^0. \vec{a} \wedge \vec{b} = 0$$ nếu và chỉ khi các vectơ $\vec{a}$ và $\vec{b}$ thẳng hàng.
$$4^0. \vec{a} \wedge (\vec{b} + \vec{c}) = \vec{a} \wedge \vec{b} + \vec{a} \wedge \vec{c}.$$

Đại lượng $\vec{a} \wedge \vec{b}$ đôi khi được gọi là tích tự do của các vectơ $\vec{a}$ và $\vec{b}$.

9. Tìm tọa độ các điểm $A, B$ giao điểm của đường thẳng $ax + by + c = 0$ với các trục tọa độ ($a \neq 0, b \neq 0$) và diện tích tam giác $ABM_0$, trong đó $M_0(x_0; y_0)$, rút ​​ra công thức tính khoảng cách từ điểm $M_0$ đến đường thẳng này:

$$|ax_0 + by_0 + c| / \sqrt{a^2 + b^2}.$$

10. a) Cho các đỉnh $A_1, A_2, \dots, A_n$ của đa giác chuyển động dọc theo một mặt phẳng thẳng và đều (mỗi đỉnh có tốc độ không đổi). Chứng minh diện tích đa giác $A_1A_2\dots A_n$ thay đổi

$$\sum \begin{matrix} x_i x_j x_k \\ y_i y_j y_k \\ z_i z_j z_k \end{matrix} = x_1 y_2 z_3 - x_1 y_3 z_2 + x_2 y_3 z_1 - x_2 y_1 z_3 + x_3 y_1 z_2 - x_3 y_2 z_1.$$

trên tất cả gam $\Delta A_i A_j A_k$ của nó, trong đó $A_i(x_i; y_i; z_i)$ là đỉnh của đa giác và “định thức tam giác” được tính theo công thức

$$\begin{matrix} x_1 x_2 x_3 \\ y_1 y_2 y_3 \\ z_1 z_2 z_3 \end{matrix} = x_1 y_2 z_3 - x_1 y_3 z_2 + x_2 y_3 z_1 - x_2 y_1 z_3 + x_3 y_1 z_2 - x_3 y_2 z_1.$$

Hơn nữa, mỗi định thức phải được viết ra bằng cách nhìn mặt $A_i A_j A_k$ từ điểm $(0; 0; 0)$: tọa độ các đỉnh của các mặt nhìn thấy được là theo chiều kim đồng hồ, các mặt không nhìn thấy được là ngược chiều kim đồng hồ.

12. a) Kiểm tra bằng công thức (2) rằng với tiếng ầm ầm $k$ thì diện tích tăng $k^2$ lần và với sự đối xứng $(x; y) \rightarrow (-x; y), (x; y) \rightarrow (x; -y), (x; y) \rightarrow (-x; -y)$ thì diện tích không thay đổi.

*) Xem thêm bài viết của A. Lopshitz “Các vùng của hình định hướng” («Kvant», 1978, số 3).

2*
