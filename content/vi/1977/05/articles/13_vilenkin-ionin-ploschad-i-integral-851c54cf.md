---
id: 1977-5-vilenkin-ionin-ploschad-i-integral-851c54cf
issue: kvant_1977_5
year: 1977
number: "5"
title: Diện tích và tích phân
authors:
  - Виленкин А. Н.
  - Ионин Ю. И.
rubric: po-stranitsam-shkolnyh-uchebnikov
rubric_sub: По страницам школьных учебников
page_first: 32
page_last: 36
page_labels: 30-34
tag: DNDN
lang: vi
source: kvant_digital
extraction: vision
content_sha256: 560c6f6f4c13228ca99a8f892ffa7b6e450b703a4725c2753a3aff36edd89c37
prompt_sha256: draft-1
translated_from: content/ru/1977/05/articles/13_vilenkin-ionin-ploschad-i-integral-851c54cf.md
source_content_sha256: cb171571682ad124f9e2df7fdf500815f322895cea91cbc7427b7223de85ac04
translation_model: draft
translation_run: vi-draft-2026-10-31
translation_quality: draft
---

⟦folio 30⟧

Diện tích và tích phân

Từ bài viết “Về các khái niệm diện tích và thể tích” của V. Boltyansky đăng trên số này, bạn đã biết về định nghĩa và các phương pháp tính diện tích khác nhau. Phổ biến nhất trong số đó là việc sử dụng phép tính tích phân. Phương pháp này sẽ được thảo luận trong bài viết này (dành cho học sinh lớp 10). Nhưng trước tiên, chúng tôi khuyên bạn nên xem lại sách giáo khoa “Đại số và phần đầu của phép phân tích 10” và xem lại các đoạn 97-102 và bảng nguyên hàm ở trang 1. 219.

Diện tích là một phần không thể thiếu

Hãy xem xét hình thang cong trong Hình 1. Hình này được giới hạn bởi đồ thị của hàm số không âm liên tục $y = f(x)$, được xác định trên đoạn $[a; b]$, các đường thẳng $x = a, x = b$ và trục x $y = 0$. Diện tích của nó $S$ bằng

$$F(b) - F(a),$$

trong đó $F$ là một nguyên hàm nào đó của hàm $f$ (“Đại số và Nguyên tắc Phân tích 10”, trang 100). Nhắc lại định nghĩa của tích phân (“Đại số và Na-

đầu phân tích 10”, đoạn 101), công thức tính diện tích có thể viết lại như sau:

$$S = \int_{a}^{b} f(x) dx.$$

Ví dụ 1. Diện tích lớn nhất của hình bị giới hạn bởi trục x, đường thẳng $x = -1, x = 1$ và đồ thị của hàm số $y = 1 - x^2$ (Hình 2), do đó, theo công thức (1), diện tích của nó

$$S = \int_{-1}^{1} (1 - x^2) dx.$$

Vì nguyên hàm của hàm $f(x) = 1 - x^2$ là hàm

$$F(x) = x - \frac{x^3}{3},$$

Cái đó

$$S = \left( x - \frac{x^3}{3} \right) \bigg|_{-1}^{1} = \frac{4}{3}.$$

Bạn thấy rằng trong ví dụ này chúng ta không phải dùng đến bất kỳ thủ thuật nào; đối với lời giải bài toán hóa ra chỉ cần sử dụng các công thức làm sẵn là đủ. Nhưng điều này không phải luôn luôn như vậy.

tính thích ứng

Thuộc tính diện tích `addumивности` giúp giải các bài toán phức tạp hơn bài toán trong việc tính diện tích. Nó “cho phép” chia một hình đã cho thành nhiều phần và tính diện tích của toàn bộ hình đó bằng tổng diện tích của các phần này.

Hình 1.

Hình 2.

⟦folio 31⟧

Ví dụ 2. Tìm diện tích hình được giới hạn bởi các đường thẳng $y = x$, $y = 1/x$, $y = 0$, $x = e$.

Hình này (Hình 3) có thể được coi là một hình thang phi tuyến cong, bị giới hạn bởi trục hoành, các đường thẳng $x = 0$ và $x = e$ và đồ thị của các hàm nằm trên đoạn [0; 1] bằng $x$ và trên khoảng [1; $e$] bằng $1/x$. Tuy nhiên, không thể viết một phép biến đổi cho hàm như vậy.

Chúng ta sẽ chia riêng hình thang phi tuyến được cho bởi đường cong $x = 1$ thành hai phần (Hình 3). Diện tích của chúng được tìm thấy ngay lập tức bằng công thức (1):

$$S_1 = \int_0^1 x dx, \quad S_2 = \int_1^e \frac{1}{x} dx.$$

Vì phép biến đổi cho hàm $f_1(x) = x$ là hàm $F_1(x) = x^2/2$ và phép biến đổi cho hàm $f_2(x) = 1/x$ là (cho $x > 0$) hàm $F_2(x) = \ln x$, nên

$$S_1 = \int_0^1 x dx = \frac{x^2}{2} \bigg|_0^1 = \frac{1}{2},$$

$$S_2 = \int_1^e \frac{1}{x} dx = \ln x \bigg|_1^e = 1,$$

và bởi tính chất của độ bám dính diện tích

$$S = S_1 + S_2 = 1 + \frac{1}{2} = \frac{3}{2}.$$

bất biến

Đối với các bài toán phức tạp hơn, một tính chất khác của diện tích sẽ hữu ích, gọi là bất biến dịch chuyển tương đối: các hàm đồng dạng có diện tích bằng nhau.

Ví dụ 3. Tìm diện tích hình được giới hạn bởi đường thẳng

$$y = \sqrt{x}, \quad y = 2, \quad x = 0.$$

⟦folio 32⟧

Tính chất aditivity và bất biến của diện tích không chỉ giúp bạn dễ dàng tìm diện tích của hình thang cong mà còn cho phép bạn tìm diện tích của các hình phức tạp hơn, chẳng hạn như những diện tích được giới hạn bởi đồ thị của các hàm nhất định và từ trên xuống, cũng như diện tích màu xanh lam của “hình thang hai đường cong”.

Ví dụ 4. Tìm diện tích của hình được giới hạn bởi các đường thẳng $y = x^2 + 2, y = 1 - x^2, x = 0, x = 1$.

Một hình thang cong được giới hạn bởi các đường thẳng $x = 0, x = 1, y = 0$ (trục x) và đồ thị của hàm $y = 1 - x^2$ bổ sung hình này cho một hình thang cong được giới hạn bởi các đường thẳng $x = 0, x = 1, y = 0$ và đồ thị của hàm $y = x^2 + 2$ (Hình 6, a). Nói cách khác, số cho trong các điều kiện có thể coi là hiệu giữa hai hình thang cong (Hình 6, b, θ). Vì thế diện tích

$$S = \int_0^1 (x^2 + 2) dx - \int_0^1 (1 - x^2) dx = \left( \frac{x^3}{3} + 2x \right) \bigg|_0^1 - \left( x - \frac{x^3}{3} \right) \bigg|_0^1 = \frac{7}{3} - \frac{2}{3} = \frac{5}{3}.$$

Lý do này có thể được khái quát dễ dàng như sau.

Đặt $f$ và $g$ là hai hàm liên tục được xác định trên khoảng $[a; b]$ và đặt bất đẳng thức $f(x) \geq g(x)$ giữ cho tất cả $x \in [a; b]$.

Khi đó diện tích của hình được giới hạn bởi đồ thị của hàm $y = f(x), y = g(x)$ và các đường thẳng $x = a, x = b$ (Hình 7) bằng

$$S = \int_a^b f(x) dx - \int_a^b g(x) dx.$$

Và vì hiệu giữa các khoảng của hai hàm số (trên cùng một đoạn) bằng khoảng cách với hiệu của chúng (“Đại số và điểm bắt đầu phân tích 10”, trang 106), nên biểu thức cho $S$ có thể được viết như sau:

$$S = \int_a^b (f(x) - g(x)) dx. \tag{2}$$

Nếu $g(x) \geq 0$ tại $x \in [a; b]$, thì công thức (2) được rút ra theo cách tương tự như trong ví dụ 4. Nếu tại một số điểm $g(x) < 0$, thì chúng ta thêm vào cả hai hàm cùng một hằng số $k$, mà chúng ta chọn lớn đến mức đồ thị của hàm $y = f(x) + k$ và $y = g(x) + k$ nằm phía trên hoành độ (Hình 8). Hình trong Hình 7 được lấy từ hình trong Hình 8 bằng phép dịch song song và do đó cũng có diện tích. Công thức (2) được áp dụng cho hình trên Hình 8:

$$S = \int_a^b \left[ (f(x) + k) - (g(x) + k) \right] dx.$$

Nhưng

$$(f(x) + k) - (g(x) + k) = f(x) - g(x).$$

Từ đây chúng ta thu được công thức (2) cho hình trong Hình 7.

Nếu đồ thị của các hàm liên tục $f$ và $g$, được xác định trên đoạn $[a; b]$, giao nhau và ở các vị trí $f(x) > g(x)$ và ở các vị trí $g(x) > f(x)$ (Hình 9), thì

⟦folio 33⟧

Cấu trúc của hàm giới hạn bởi đồ thị của hàm $f$ và $g$ và các đường $x = a$, $x = b$ bằng

$$S = \int_{a}^{b} |f(x) - g(x)| \, dx. \tag{3}$$

Công thức này tổng quát hóa công thức (2) (bạn tự chứng minh nhé).

Ví dụ 5. Tìm diện tích $S$ của hàm chứa giữa các dòng $y = x^3 - 3x$ và $y = x$.

Các đường này giao nhau tại các điểm có tọa độ $(-2; -2)$, $(0; 0)$ và $(2; 2)$ (Hình 10), với $(x^3 - 3x) - x = x^3 - 4x$ và $|x^3 - 4x| = x^3 - 4x$ tại $-2 \leq x \leq 0$, $|x^3 - 4x| = 4x - x^3$ tại $0 \leq x \leq 2$. Do đó, theo công thức (3)

$$S = \int_{-2}^{2} |(x^3 - 3x) - x| \, dx =$$

$$= \int_{-2}^{2} |x^3 - 4x| \, dx = \int_{-2}^{0} (x^3 - 4x) \, dx +$$

$$+ \int_{0}^{2} (4x - x^3) \, dx = \left( \frac{x^4}{4} - 2x^2 \right) \bigg|_{-2}^{0} +$$

$$+ \left( 2x^2 - \frac{x^4}{4} \right) \bigg|_{0}^{2} = 4 + 4 = 8.$$

Nhận thấy rằng funkra trong Hình 10 là đối xứng với gốc tọa độ, chúng ta có thể thu được lời giải ngắn hơn của bài toán này:

$$S = 2 \int_{0}^{2} |(x^3 - 3x) - x| \, dx =$$

$$= 2 \int_{0}^{2} |x^3 - 4x| \, dx = 2 \int_{0}^{2} (4x - x^3) \, dx =$$

$$= 2 \cdot \left( 2x^2 - \frac{x^4}{4} \right) \bigg|_{0}^{2} = 2 \cdot 4 = 8.$$

Tính tích phân

Cho đến nay chúng ta đã sử dụng phép tính tích phân cho lời giải hình học bài toán - phép tính diện tích. Bây giờ chúng ta áp dụng thông điệp hình học vào việc tính tích phân.

Ví dụ 6. Tính tích phân

$$\int_{0}^{1} \sqrt{1 - x^2} \, dx.$$

Đồ thị của hàm số $y = \sqrt{1 - x^2}$ xác định trên đoạn $[0; 1]$ là một phần tư đường tròn bán kính 1 s

⟦folio 34⟧

Hình 11.

trung tâm tại điểm gốc (Hình 11),
Do đó $\int_0^1 \sqrt{1-x^2} \, dx$ là một phần tư đường tròn phẳng có bán kính 1 nên khoảng này bằng $\pi/4$.

Ví dụ 7. Tìm nguyên hàm của hàm số $f$ có thể cho theo công thức

$$F(x) = \int_a^x f(t) \, dt$$

(“Đại số và sự khởi đầu của phân tích 10”, đoạn 102).

Trong trường hợp này, hãy đặt $a = 1$, sau đó chúng ta cần tính khoảng

$$F(x) = \int_1^x \ln t \, dt.$$

Nếu $x > 1$, thì khoảng này bằng diện tích của hàm, được đánh dấu màu đỏ trong Hình 12. Chúng ta hãy phản ánh nó so với đường thẳng $y = t$; sau đó nó sẽ được hiển thị trong một hàm (Hình 13), được giới hạn bởi các đường thẳng $t = 0, t = \ln x$ và đồ thị của hàm $y = x$ và $y = e^t$ (hàm nghịch đảo của $y = \ln t$). Diện tích của hàm này theo công thức (3) bằng

$$\int_0^{\ln x} |e^t - x| \, dt.$$

Vì $e^t \leq x$ là $0 \leq t \leq \ln x$ nên ta có

$$F(x) = \int_1^x \ln t \, dt = \int_0^{\ln x} (x - e^t) \, dt = (xt - e^t) \bigg|_0^{\ln x} = x \ln x - x + 1.$$

Dạng tổng quát của nguyên hàm của hàm $f(x) = \ln x$ với $x \geq 1$ như sau:

$$F(x) = x(\ln x - 1) + C,$$

trong đó $C$ là hằng số tùy ý. Bằng cách lấy đạo hàm của hàm $F$, chúng ta có thể xác minh rằng nó là nguyên hàm thực sự của hàm $f$ và của $x \in ]0; 1]$.

Chu trình Carnot

Trong sách giáo khoa vật lý ở trường, công thức tính hiệu suất là Chu trình Carnot được đưa ra không có đạo hàm. Nhưng sử dụng phép tính tích phân thì việc rút ra công thức này không quá khó.

Để làm điều này, hãy tính công do 1 mol khí thực hiện trong chu trình Carnot. Chúng ta hãy nhớ lại rằng khi thể tích đáng kể đối với nó thay đổi từ $V_1$ thành $V_2$, chất khí thực hiện công bằng về mặt số với diện tích của hình thang cong giới hạn bởi đồ thị của hàm số $p(V)$, trục $OV$ và các đường thẳng $V = V_1$, $V = V_2$ (“Vật lý 9”, đoạn 21), tức là tích phân

$$\int_0^{V_1} p(V) \, dV.$$

Chu trình Carnot (Hình 14) bao gồm bốn phần (về chu trình Carnot, xem «Kvant», 1977, số 1).

Ở phần $ab$ sẽ có sự giãn nở đẳng nhiệt của khí từ thể tích $V_1$ đến thể tích $V'_1$ ở nhiệt độ không đổi
