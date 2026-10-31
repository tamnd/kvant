---
id: 1987-11-bolibruh-uroev-shabunin-reshenie-sistem-trigonometricheskih-uravneniy-1fae2db9
issue: kvant_1987_11
year: 1987
number: "11"
title: Lời giải hệ phương trình lượng giác
authors:
  - Болибрух А. А.
  - Уроев В. М.
  - Шабунин М. И.
rubric: praktikum-abiturienta
rubric_sub: Практикум абитуриента
page_first: 48
page_last: 51
page_labels: 46-49
tag: XXRY
lang: vi
source: kvant_digital
extraction: vision
content_sha256: c559397116523d02abcb8dbdd72cd064dd1180419ec8da79576a88db829037e8
prompt_sha256: draft-1
translated_from: content/ru/1987/11/articles/19_bolibruh-uroev-shabunin-reshenie-sistem-trigonometricheskih-uravneniy-1fae2db9.md
source_content_sha256: e91de4415ab15b8e3c218a33b9c2ab8949e4c282e7d086e5d075058bddb6fa34
translation_model: draft
translation_run: vi-draft-2026-10-31
translation_quality: draft
---

⟦folio 46⟧

Lời giải hệ phương trình lượng giác

Ứng viên Khoa học Vật lý và Toán học
A. A. BOLIBRUKH,
Ứng viên Khoa học Vật lý và Toán học
V. M. UROEV,
Giáo sư M. I. SHABUNIN

Trong lưu ý này, sử dụng các ví dụ bài toán được đề xuất trong các năm thi tuyển sinh khác nhau tại MIPT (viết và nói), một số phương pháp của hệ phương trình lượng giác lời giải được đưa ra.

Chúng ta hãy nhớ lại các định nghĩa áp dụng cho bất kỳ hệ thống nào, không nhất thiết phải lượng giác. Nếu mọi lời giải của một hệ thống đều là nghiệm của hệ thống khác thì hệ thứ hai được gọi là “hậu quả” của hệ thứ nhất. Nếu hệ thứ nhất là hệ quả của hệ thứ hai và hệ thứ hai là hệ quả của hệ thứ nhất thì những hệ thống đó được gọi là tương đương.

Chúng ta hãy chỉ ra một số phép biến đổi của hệ thống, nhờ đó chúng ta thu được các hệ thống tương đương với hệ thống ban đầu.

1. Bất kỳ phương trình nào của hệ đều có thể được thay thế bằng một phương trình tương đương.

2. Bất kỳ phương trình nào của hệ đều có thể được thay thế bằng một phương trình thu được bằng cách cộng phương trình đã cho vào một phương trình khác của hệ.

3. Giá trị của ẩn số, tìm được từ một số phương trình của hệ, có thể được thay thế vào bất kỳ phương trình nào khác của cùng hệ.

4. Bạn có thể thêm một phương trình vào hệ thống là hệ quả của hệ thống này.

5. Nếu một hệ chứa phương trình $f \cdot g = 0$, trong đó hàm $f$ và $g$ được xác định trên cùng một tập hợp thì nó tương đương với tập hợp của hai hệ, trong đó phương trình $f \cdot g = 0$ được thay thế bằng phương trình $f = 0$ và hệ kia bằng phương trình $g = 0$.

Khi tiếp cận hệ phương trình lượng giác lời giải, trước tiên nên kiểm tra xem liệu có thể biểu diễn vô thời hạn một trong các ẩn số theo các ẩn số khác từ bất kỳ phương trình nào của hệ hay không.

Bài toán 1 (MIPT, 1983). Giải hệ phương trình
$$\begin{cases} tg x + tg y = 1 - tg x \cdot tg y, \\ \sin 2y - \sqrt{2} \sin x = 1. \end{cases}$$

Lời giải e. Hệ thống bên dưới chỉ có ý nghĩa trong trường hợp khi các hàm $tg x$ và $tg y$ được xác định, tức là.

⟦folio 47⟧

có những điều kiện
$$\cos x \neq 0, \cos y \neq 0.$$ (3)

Chúng ta hãy nhìn vào phương trình đầu tiên. Sẽ là tự nhiên khi chia cả hai phần cho 1 - tg x · tg y và sử dụng công thức tính tang của tổng. Khi đó phương trình (1) có thể được viết lại thành
$$\text{tg}(x + y) = 1;$$ (4)
nhưng đồng thời chúng ta có thể mất các hệ thống lời giải (1), (2), mà
$$1 - \text{tg} x \cdot \text{tg} y = 0.$$ (5)
Tuy nhiên, dễ dàng kiểm chứng được hệ (1), (2), (5) không có lời giải. Trên thực tế, nếu có lời giải của hệ này, thì từ phương trình (1) nó sẽ suy ra tan x + tan y = 0. Nhưng khi đó phương trình (5) sẽ có dạng 1 + tan² y = 0, và do đó, nó sẽ không có lời giải.

Như vậy, hệ ban đầu ở điều kiện (3) tương đương với hệ (2), (4).

Từ phương trình (4) chúng ta tìm thấy x + y = π/4 + πn, tức là
$$y = \pi/4 + \pi n - x, \ n \in \mathbb{Z}.$$ (6)
Bây giờ hãy thay biểu thức tìm được của y vào phương trình (2) của hệ ban đầu:
$$\sin(\pi/2 - 2x + 2\pi n) - \sqrt{2} \sin x = 1.$$
Phương trình thu được được rút gọn về dạng sin x (2 sin x + √2) = 0, từ đó
a) sin x = 0, x = πm, m ∈ Z,
6) sin x = -√2/2,
x = (-1)^{k+1}π/4 + πk, k ∈ Z.
Sử dụng công thức (6) chúng ta xác định được các giá trị tương ứng của y. Đối với dãy a)
$$y = \pi/4 + \pi(n - m), \ n, m \in \mathbb{Z};$$ (7)
cho loạt 6)
$$y = \pi/4 - (-1)^{k+1}π/4 + π(n - k), \ n, k \in \mathbb{Z}.$$ (8)
Các giá trị (x, y) từ công thức (7) thỏa mãn điều kiện (3). Loạt (8) yêu cầu nghiên cứu bổ sung. Nếu sin x = -√2/2 thì cos x ≠ 0, nên bất đẳng thức thứ nhất của phương trình (3) phụ thuộc hoàn toàn. Bất đẳng thức thứ hai cos y ≠ 0 không phải lúc nào cũng thỏa mãn.

Nếu k là số chẵn, tức là k = 2p, trong đó p ∈ Z, thì công thức (8) cho y = π/2 + π(n - 2p). Đối với các giá trị này của y, điều kiện (3) không được thỏa mãn. Nếu k là số lẻ, tức là k = 2p - 1, trong đó p ∈ Z thì y = π(n - 2p + 1) và điều kiện (3)
nhật ký. Các giá trị tương ứng của x được tìm bằng công thức 6): x = -3π/4 + 2πp.
Đáp số: (πm; π/4 + π(n - m)), (-3π/4 + 2πp; π(n - 2p + 1)), m, n, p ∈ Z.

Các tham số số nguyên có trong mục nhập hệ thống lời giải không thể được chỉ định bằng một chữ cái. Điều này có nghĩa là chúng được chỉ định để đảm nhận các giá trị giống nhau, trong khi trên thực tế, chúng đảm nhận tất cả các giá trị giống nhau - giống hoặc khác nhau.

Trong phần tiếp theo, k, l, m, n, p, r, s, t, trừ khi có quy định khác, lấy tất cả các giá trị nguyên.

Bài toán 2. Giải hệ phương trình
$$\begin{cases} \sin x \cdot \cos y = -1/2, \\ \cos x \cdot \sin y = 1/2. \end{cases}$$ (9)

Lời giải. Cộng các phương trình của hệ (9), rồi trừ phương trình thứ nhất khỏi phương trình thứ hai, chúng ta thu được hệ tương đương với hệ (9):
$$\begin{cases} \sin(x + y) = 0, \\ \sin(y - x) = 1, \end{cases}$$

vị trí tuần tự ở đâu
x + y = πn, y - x = π/2 + 2πk,
x = π(n/2 - k - 1/4),
y = π(n/2 + k + 1/4).

Đáp số: (π(n/2 - k - 1/4); π(n/2 + k + 1/4)).

Giống như hệ (9), bạn có thể giải bất kỳ hệ nào có dạng
$$\begin{cases} \sin x \cdot \sin y = a, \\ \cos x \cdot \cos y = b. \end{cases}$$

Các hệ thống như vậy bao gồm, ví dụ, các hệ thống
$$\begin{cases} \sin x \cdot \sin y = a, \\ \text{tg} x \cdot \text{tg} y = b, \\ \sin x \cdot \cos y = a, \\ \text{tg} x \cdot \text{ctg} y = b. \end{cases}$$

Nếu một hệ thống chỉ chứa hai tổ hợp hàm lượng giác hoặc có thể giảm xuống còn một, thì bằng cách chỉ định các tổ hợp hàm này là ẩn số mới, chúng ta có thể giảm hệ thống ban đầu thành hệ thống đại số.

Bài toán 3. Giải hệ phương trình
$$\begin{cases} \cos x - \sin x = 1 + \cos y - \sin y, \\ 3 \sin 2x - 2 \sin 2y = 3/4. \end{cases}$$ (10)

Lời giải. Chúng ta hãy sử dụng danh tính
$$(\sin x - \cos x)^2 = 1 - \sin 2x$$ và biểu thị

⟦folio 48⟧

cos x - sin x = u, cos y - sin y = v;
(11)

Sau đó
sin 2x = 1 - u², sin 2y = 1 - v²,
và hệ (10) sẽ được rút gọn về hệ đại số
$$\begin{cases} u = 1 + v, \\ 3u^2 - 2v^2 = 1/4. \end{cases}$$

Hệ thống (12) có hai lời giải:
$$u_1 = -9/2, v_1 = -11/2 \text{ и } u_2 = 1/2, v_2 = -1/2.$$
Trước tiên chúng ta hãy xem xét các giá trị của $u_1, v_1$. Trở lại các biến ban đầu, sử dụng công thức (11) ta thu được:
$$\begin{cases} \cos x - \sin x = -9/2, \\ \cos y - \sin y = -11/2. \end{cases}$$

Nhưng phương trình đầu tiên của hệ (13) không có lời giải, vì cos x - sin x = $\sqrt{2}$ cos $(x + \pi/4)$ $\geqslant -\sqrt{2} > -9/2$.

Do đó, hệ (13) không có lời giải.

Bây giờ chúng ta hãy xem xét các giá trị của $u_2$ và $v_2$. Một lần nữa, sử dụng công thức (11), chúng ta thu được
$$\begin{cases} \cos x - \sin x = 1/2, \\ \cos y - \sin y = -1/2. \end{cases}$$

Đối với phương trình đầu tiên chúng ta tìm thấy
$$\cos x \cdot 1/\sqrt{2} - \sin x \cdot 1/\sqrt{2} = 1/2\sqrt{2}, \cos(x + \pi/4) = 1/2\sqrt{2}, x + \pi/4 = \pm \arccos(1/2\sqrt{2}) + 2\pi n, x = -\pi/4 \pm \arccos(1/2\sqrt{2}) + 2\pi n.$$
Theo cách tương tự chúng ta có được
$$y = -\pi/4 \pm \arccos(-1/2\sqrt{2}) + 2\pi n.$$
Vì vậy, chúng tôi tìm thấy lời giải sau của hệ thống ban đầu:
$$(-\pi/4 \pm \arccos(1/2\sqrt{2}) + 2\pi n; -\pi/4 \pm \arccos(-1/2\sqrt{2}) + 2\pi n)$$
(các dấu hiệu được chọn độc lập với nhau).

Trong một số trường hợp, hệ thống có thể được đưa về dạng
$$\begin{cases} \sin x = f(y), \\ \cos x = g(y), \end{cases}$$

từ đó, nhờ điểm lượng giác chính $\sin^2 x + \cos^2 x = 1$, chúng ta thu được phương trình $f^2(y) + g^2(y) = 1$, chỉ chứa một ẩn số.

Nếu hệ thu gọn về dạng
$$\begin{cases} \text{tg} x = f(y), \\ \text{ctg} x = g(y), \end{cases}$$

thì ẩn số $x$ bị loại trừ bởi các biến của phương trình: tg $x \cdot \text{ctg} x = 1$, từ đó $f(y) \cdot g(y) = 1$.

Với những cách làm như vậy lời giải cần theo dõi cẩn thận để không làm mất lời giải và không thu được người lạ lời giải.

Bài toán 4 (MIPT, 1978). Giải hệ phương trình
$$\begin{cases} 4 \sin x - 2 \sin y = 3, \\ 2 \cos x - \cos y = 0. \end{cases}$$

Lời giải. Hệ (15) có thể rút gọn về dạng (14). Do đó, chúng ta thu được hệ thống tương đương
$$\begin{cases} \sin x = 3/4 + 1/2 \cdot \sin y, \\ \cos x = 1/2 \cdot \cos y. \end{cases}$$

Bằng cách bình phương phương trình của hệ (16) theo số hạng và cộng, chúng ta thu được phương trình là hệ quả của hệ (16):
$$1 = \frac{9}{16} + \frac{3}{4} \sin y + \frac{1}{4} \cos^2 y,$$
hoặc
$$\sin y = 1/4,$$

Ở đâu
$$y = (-1)^n \arcsin 1/4 + \pi n.$$
Từ phương trình đầu tiên của hệ (16) xét đến (17) ta tìm được $x = 7/8$, $x = (-1)^m \arcsin 7/8 + \pi m.$

Vì tại lời giải của hệ (15) cấu trúc lời giải có thể xuất hiện (thao tác bình phương đã được sử dụng), cần phải thực hiện lựa chọn bằng cách thay thế các giá trị tìm thấy (18), (19) vào phương trình thứ hai của hệ thống này.

Dễ dàng nhận thấy rằng đối với $m$ và $n$ chẵn trong các công thức (18), (19) thì các giá trị tương ứng của cos $x$ và cos $y$ là dương, còn đối với $m$ và $n$ lẻ thì các giá trị này là âm. Như vậy, |cos $x| = \sqrt{1 - \sin^2 x} = \sqrt{15}/8, |\cos y| = \sqrt{15}/4$, để thỏa mãn phương trình thứ hai của hệ (16) chỉ cần các giá trị của cos $x$ và cos $y$ trùng nhau. Từ đây chúng ta có được
$$\begin{cases} x = \arcsin \frac{7}{8} + 2\pi k, \\ y = \arcsin \frac{1}{4} + 2\pi l, \end{cases}$$

$$x = -\arcsin \frac{7}{8} + (2k + 1)\pi,$$
$$y = -\arcsin \frac{1}{4} + (2l + 1)\pi.$$

Cả hai chuỗi kết quả (20) có thể được kết hợp và đáp số được viết dưới dạng sau.

⟦folio 49⟧

Đáp số:

$$((-1)^p \arcsin \frac{7}{8} + \pi p),$$
$$((-1)^p \arcsin \frac{1}{4} + \pi (p + 2r)).$$

Với các hệ lượng giác lời giải, bước đầu tiên thường rất khó để tìm ra “chìa khóa” dẫn đến lời giải bài toán. Không có khuyến nghị chung có thể được đưa ra ở đây. Chúng tôi chỉ có thể khuyên bạn nên thử áp dụng các phép biến đổi như vậy của phương trình hệ thống dẫn đến xuất hiện các hàm lượng giác của một đối số hoặc ít nhất là không làm tăng số lượng hàm với các đối số khác nhau.

Bài toán 5 (MIPT, 1982). Giải hệ phương trình

$$\begin{cases}
3 \cos 3x = \sin (x + 2y), & (21) \\
3 \sin (2x + y) = -\cos 3y.
\end{cases}$$

Lời giải. Nếu chúng ta biểu diễn các số hạng của phương trình dưới dạng sin và cosin của các đối số $x$ và $y$, chúng ta sẽ có một hệ khá phức tạp. Vì vậy, nên chọn một phương pháp khác lời giải.

Lưu ý rằng tổng các đối số cosin trong phương trình hệ thống, bằng $3x + 3y$, trùng với tổng các đối số sin. Khi tính đến điều này, chúng ta hãy sắp xếp lại các phương trình của hệ (21) theo chiều ngang, tức là nhân vế trái của một phương trình với vế phải của phương trình kia. Ta thu được phương trình $-\cos 3x \cos 3y = \sin (x + 2y) \sin (2x + y)$, (22) là hệ quả của hệ (21).

Chúng ta hãy lưu ý trong phương trình (22) tích của các hàm lượng giác với các tổng tương ứng (hiệu); chúng ta thu được sau khi áp dụng tương tự cos $(x - y)$ + cos $(3x - 3y) = 0$, do đó có 2 cos $(x - y) \cdot \cos (2x - 2y) = 0$. Phương trình này được chia thành hai phương trình:

$$\cos (x - y) = 0, \quad (23)$$
$$\cos (2x - 2y) = 0. \quad (24)$$

Do đó, hệ (21) bằng tổng của hệ (21), (23) và (21), (24).

a) Từ phương trình (23) suy ra $x = y + \pi/2 + \pi n$. (25)

Thay $x$ từ (25) vào hệ (21), ta thu được:

$$3 \cos (3y + 3\pi/2 + 3\pi n) = \sin (3y + \pi/2 + \pi n), \quad 3 \sin (3y + \pi + 2\pi n) = -\cos 3y.$$

Cả hai phương trình của hệ này đều được rút gọn về dạng 3 sin $3y = \cos 3y$, từ đó $y = \frac{1}{3} \arctg \frac{1}{3} + \frac{\pi m}{3}$. Từ (25) tìm được các giá trị tương ứng của $x$.

6) Bây giờ chúng ta xét hệ (21), (24). Từ phương trình (24) chúng ta tìm thấy $x = y + \pi/4 + \pi k/2$. Thay thế giá trị này vào hệ thống (21), chúng ta thu được:

$$3 \cos (3y + 3\pi/4 + 3\pi k/2) = \sin (3y + \pi/4 + \pi k/2), \quad 3 \sin (3y + \pi/2 + \pi k) = -\cos 3y.$$

Tiếp theo, chúng ta sẽ sử dụng công thức rút gọn. Từ phương trình thứ hai của hệ (26), suy ra $\cos 3y = 0$, tức là $y = \pi/6 + \pi p/3$. Thay giá trị này vào phương trình đầu tiên, chúng ta nhận được

$$3 \cos (\pi p + \pi/2 + 3\pi/4 + 3\pi k/2) = \sin (\pi p + 3\pi/4 + \pi k/2), \quad \text{откуда } (3(-1)^k + 1) \sin (3\pi/4 + \pi k/2) = 0.$$

Đẳng thức cuối cùng không được thỏa mãn cho bất kỳ mục đích nào $k$, do đó hệ thống (26) không nhất quán và trong trường hợp 6) lời giải thì không.

Đáp số:

$$\left( \frac{1}{3} \arctg \frac{1}{3} + \frac{\pi}{2} + \frac{\pi m}{3} + \pi n; \frac{1}{3} \arctg \frac{1}{3} + \frac{\pi m}{3} \right).$$

Trận chiến

Giải hệ phương trình:

1 (MIPT, 1982).

$$\begin{cases}
tg y - tg x = 1 + tg x \cdot tg y, \\
\cos 2 y + \sqrt{3} \cos 2x = -1.
\end{cases}$$

2 (MIPT, 1978).

$$\begin{cases}
6 \cos x + 4 \cos y = 5, \\
3 \sin x + 2 \sin y = 0.
\end{cases}$$

3 (MIPT, 1982).

$$\begin{cases}
2 \cos (3x + y) = \sin (x - y), \\
2 \sin (x + y) = \cos (3x - y).
\end{cases}$$

4 (MIPT, 1982).

$$\begin{cases}
\sin (2x + y) + \sin (2x - y) = \sqrt{2} \cos y, \\
tg (x + \pi/8) + \cos y = tg^2 y.
\end{cases}$$

5 (MIPT, 1981).

$$\begin{cases}
\cos 2y + 1/2 = (\cos y - 1/2) (1 + 2 \sin 2x), \\
\sin y (tg^3 x + ctg^3 x) = 3 ctg y.
\end{cases}$$

6 (MIPT, 1976).

$$\begin{cases}
\sin^2 x + \cos y \cdot \sin x = \cos 2y, \\
\cos 2x + \sin 2y = \sin^2 y + 3 \cos y \cdot \sin x.
\end{cases}$$

7 (MIPT, 1978).

$$\begin{cases}
\sqrt{1 + \sin x \cdot \sin y} = \cos x, \\
2 \sin x \cdot ctg y + 1 = 0.
\end{cases}$$

8 (MIPT, 1986).

$$\begin{cases}
tg x \cdot \sin y + 2 ctg x \cos y = \sqrt{5/2}, \\
2 ctg x \cdot \sin y - tg x \cdot \cos y = \sqrt{5/2}.
\end{cases}$$

9 (MIPT, 1982), Tìm tất cả các hệ phương trình lời giải

$$\begin{cases}
tg x \cdot \sin y + 2 ctg x \cdot \cos y = \sqrt{5/2}, \\
2 ctg x \cdot \sin y - tg x \cdot \cos y = \sqrt{5/2}.
\end{cases}$$
