---
id: 1984-5-voronin-kulagin-metod-proizvodyaschih-funktsiy-4d417cca
issue: kvant_1984_5
year: 1984
number: "5"
title: Phương pháp tạo hàm
authors:
  - Воронин С. М.
  - Кулагин А. Г.
rubric: raznoe
page_first: 14
page_last: 17
page_labels: 12-15
tag: ZM1X
lang: vi
source: kvant_digital
extraction: vision
content_sha256: 3f12fa6fac7a0a8ec680bd4c5e54f57eace5abeb1cbe71b53c577c17ebf39b6b
prompt_sha256: draft-1
translated_from: content/ru/1984/05/articles/06_voronin-kulagin-metod-proizvodyaschih-funktsiy-4d417cca.md
source_content_sha256: 55e36a807143af254d94175b3ac53af79e38b953351e3920bd956540dfb8af20
translation_model: draft
translation_run: vi-draft-2026-10-31
translation_quality: draft
---

⟦folio 12⟧

số cách để cân một tải trọng $k$ gam được xét theo trọng lượng!

Vì vậy, đối với lời giải, bài toán ban đầu vẫn được tính $A_k$. Và đây là một động thái bất ngờ khác của Euler. Anh ấy viết những điều rất hay

$$\begin{align*}
(1-z) (1+z) &= 1-z^2, \\
(1-z^2) (1+z^2) &= 1-z^4, \\
(1-z^4) (1+z^4) &= 1-z^8,
\end{align*}$$

và sau khi nhân và giảm với các thừa số chung anh ta nhận được

$$1-z (1+z) (1+z^2) (1+z^4) (1+z^8) \cdot \dots = 1,$$

nghĩa là, $(1-z) \alpha(z) = 1$, từ đâu

$$\alpha(z) = \frac{1}{1-z} = 1+z+z^2+z^3+z^4+\dots$$

(ở đây được viết công thức nổi tiếng về tổng của cấp số nhân*). So sánh (3) với (2) cho thấy rằng $A_k = 1$ đối với tất cả $k$, nghĩa là, bất kỳ tải nào của một số nguyên gam đều có thể được đặt ở các chữ số 1, 2, 4, ..., $2^m$, ... gam, theo một cách duy nhất.

Bài toán về cách phân vùng một số

Đây là cái mà Euler gọi là bài toán sau đây: tìm số nguyên dương lời giải của phương trình

$$x_1 + \dots + x_m = k,$$

(4)

thực phẩm $m$ và $k$ là các số tự nhiên cố định. Ở đây có một biểu hiện bất ngờ khác dẫn đến mục tiêu, đó là

$$\beta(z) = (1+z+z^2+z^3+z^4+\dots)^m.$$

Sau khi mở rộng dấu ngoặc đơn, $\beta(z)$ được viết là

$$\beta(z) = 1+B_1z+B_2z^2+B_3z^3+\dots$$

(6)

$B_k$ bằng bao nhiêu? Hãy thử tự trả lời câu hỏi này, hãy nhớ rằng $B_k$ là hệ số của $z^k$. Tất nhiên là có: hệ số $B_k$ bằng số cách chọn một chỉ báo số nguyên từ mỗi dấu ngoặc ở bên phải của (5), nghĩa là $B_k$ bằng số số nguyên dương lời giải của phương trình (4)!

Bài toán của Euler được rút gọn thành phép tính $B_k$.

Để làm điều này, hãy nhớ công thức cấp số nhân, bạn có thể viết

$$\beta(z) = (1-z)^{-m} = 1+B_1z+B_2z^2+B_3z^3+\dots$$

(7)

Phân biệt sự bình đẳng này

$$m(1-z)^{-m-1} = B_1+2B_2z+3B_3z^2+\dots$$

và thay thế $z=0$, chúng ta nhận được $B_1=m$.

*) Nếu $|z|<1$. Nhưng chúng ta sẽ quay lại vấn đề này sau.

Lấy đạo hàm một lần nữa và thay $z=0$ một lần nữa, ta được $B_2=m(m+1)/2$. Tiếp tục theo cách tương tự (nghĩa là tiếp tục các phương trình (7) $k$ lần và thay thế $z=0$), theo Euler, chúng ta thu được số lời giải của phương trình (4) ở dạng

$$B_k = \frac{m(m+1) \cdot \dots \cdot (m+k-1)}{n!}$$

Bài toán về trao đổi

Có bao nhiêu cách bạn có thể đổi một đồng rúp lấy tiền xu có mệnh giá 1, 2, 3, 5, 10 kopecks? bài toán này có thể được hình thành khác nhau: có bao nhiêu số nguyên không âm lời giải có phương trình

$$x_1+2x_2+3x_3+5x_4+10x_5=100?$$

Ở dạng tổng quát hơn, “bài toán về trao đổi” được phát biểu như sau: có bao nhiêu số nguyên không âm lời giải có phương trình

$$a_1x_1+a_2x_2+\dots+a_mx_m=n,$$

(8)

Điều gì sẽ xảy ra nếu $a_i$ là số nguyên dương và $n$ là số tự nhiên cố định?

Hãy xem xét biểu thức

$$\gamma(z) = (1+z^a_1+z^a_2+z^a_3+\dots) \times (1+z^a_2+z^a_2+z^a_3+\dots) \times (1+z^a_m+z^a_m+z^a_m+\dots) = 1+C_1z+C_2z^2+C_3z^3+\dots$$

Nếu hiểu lý luận trước đó, bạn sẽ nói ngay rằng số $C_n$ bằng số lời giải của phương trình (8). Nhưng làm thế nào để tìm thấy $C_n$? Sử dụng công thức tính tổng của cấp số nhân giảm vô hạn (ví dụ: $1+z^a_1+z^a_2+\dots=1/(1-z^a_1))$, bạn có thể biểu thị $\gamma(z)$ dưới dạng

$$\gamma(z) = \frac{1}{(1-z^a_1)(1-z^a_2)\dots(1-z^a_m)},$$

nhưng từ đây vẫn chưa rõ ngay làm thế nào để có được $C_n$ trong trường hợp chung. Tuy nhiên, công thức (9) đã đủ để tìm $C_n$ cho $n$ nhỏ.

Bài toán khoảng bốn hình vuông

Mọi số nguyên có thể được biểu diễn dưới dạng tổng của bốn bình phương các số nguyên không, và nếu có thì bằng bao nhiêu cách? Nói cách khác, phương trình có bao nhiêu số nguyên lời giải?

$$x_1^2+x_2^2+x_3^2+x_4^2=m,$$

(10)

thức ăn $m$ là một số tự nhiên nhất định?

bài toán này cần thiết hơn những cái trước, mặc dù nó cũng giống như chúng, tính toán các hệ số của một “đa thức vô hạn” nhất định. Cụ thể là đặt

⟦folio 13⟧

$$\delta(z) = \frac{1 + 2z + 2z^4 + 2z^9 + 2z^{16} + \dots}{1 + D_1z + D_2z^2 + D_3z^3 + \dots},$$

Dễ hiểu là số lời giải cần tìm của phương trình (10) bằng $D_m$. Vi phân $m$ lần và thay $z=0$, người ta có thể tìm thấy $D_m$ là

$$D_m = \frac{1}{m!} \frac{d^m}{dz^m} \left( \delta(z) \right) |_{z=0}$$

trong đó $\frac{d^m}{dz^m}$ biểu thị việc lấy đạo hàm theo thứ tự $m$ và ký hiệu $|_{z=0}$ có ​​nghĩa là tất cả $z$ cần được thay thế bằng 0. Đối với $m$ nhỏ, số $D_m$ có thể được tính bằng công thức này, nhưng nhìn chung việc này không dễ dàng. bài toán ban đầu từ lý thuyết số đã được giảm xuống còn một số bài toán từ phân tích, nhưng cái sau vẫn cần được giải!

Từ kết quả của nhà toán học người Đức K. G. Jacobi (1804-1851) đã đưa ra một công thức đáng chú ý cho $\delta(z)$

$$\delta(z) = 1 + 8 \sum_{m \neq 4k} \frac{mz^m}{1 - z^m},$$

điều này cũng được nhà toán học Ấn Độ S. Ramanujan (1887-1920) tiếp nhận. Từ đó ta suy ra phương trình (10) luôn giải được và tìm được số lời giải của phương trình này.

Thảo luận về phương pháp

Bây giờ chúng ta hãy cố gắng hiểu phương pháp chung bao gồm những gì, phương pháp này hoạt động hiệu quả đến mức đáng kinh ngạc trong các vấn đề được phân tích. Trong mỗi người trong số họ, một “biểu thức vô hạn” nhất định chứa chữ cái $z$ đã được xem xét (tích vô hạn của hai người - (1), lũy thừa hữu hạn của một tổng vô hạn - (5) và (11), tích của tổng vô hạn - (9)). Hơn nữa, biểu thức này được viết dưới dạng “đa thức vô hạn trong $z$”, tức là ở dạng

$$\alpha(z) = A_0 + A_1z + A_2z^2 + A_3z^3 + \dots + A_nz^n + \dots,$$

và hóa ra các hệ số $A_k$ đưa ra chìa khóa cho lời giải bài toán. Sau đó, có thể tính hệ số $A_k$ bằng cách thực hiện các phép toán khác nhau trên các biểu thức vô hạn: các phép tính số học được thực hiện trên chúng, chúng được vi phân, biến đổi theo công thức cấp số nhân...

Thật tự nhiên khi hỏi: chúng ta đang xem xét những biểu thức vô hạn nào và các hành động được thực hiện trên chúng có hợp pháp không? Tác giả của phương pháp này, Leonhard Euler, dường như không nghĩ nhiều về những vấn đề này - ông coi các biểu thức vô hạn như thể chúng là hữu hạn, và tất cả những gì quan trọng đối với ông là thu được kết quả. Trong khi đó, việc xử lý vô cực một cách bất cẩn lại tiềm ẩn nguy cơ mắc sai lầm.

Ví dụ tự phụ

Xét hai "đa thức vô hạn"

$$\alpha(z) = 1 - z + z^2 - z^3 + z^4 - \dots,$$

$$\beta(z) = -1 + z - z^2 + z^3 - z^4 + \dots$$

và đếm tổng vô hạn

$$S(z) = \alpha(z) + \beta(z) + \alpha(z) + \alpha(z) + \dots$$

Nếu chúng ta nhóm các số hạng trong $S(z)$ theo cặp, bắt đầu từ cặp đầu tiên, chúng ta sẽ nhận được

$$S(z) = [\alpha(z) + \beta(z)] + [\alpha(z) + \beta(z)] + \dots = \alpha(z) + 0 + 0 + \dots = \alpha(z)!$$

Không, nếu bạn nhóm khác nhau, bạn có thể nhận được

$$S(z) = \alpha(z) + [\beta(z) + \alpha(z)] + [\beta(z) + \alpha(z)] + \dots = \alpha(z) + 0 + 0 + \dots = \alpha(z)!$$

Và nếu bạn thay đổi thứ tự của các số hạng, bạn có thể đi đến một kết quả thậm chí còn lạ hơn, chẳng hạn như $S(z) = 17z^{17}$ (nghĩ về cách thực hiện điều này).

Có lẽ đã đến lúc đưa ra những định nghĩa chính xác về biểu thức vô hạn và tìm ra những phép toán nào là hợp pháp đối với chúng.

Chuỗi bằng cấp chính thức

Quyền hạn hình thức gần đó được gọi là biểu thức

$$\alpha(z) = a_0 + a_1z + a_2z^2 + \dots + a_nz^n + \dots,$$

trong đó $a_i$ là các số thực (các hệ số của chuỗi (12)) và $z$ là một ký hiệu đơn giản (biến dạng của chuỗi). Các nhà toán học còn cho rằng $\alpha(z)$ là hàm sinh của dãy hệ số $a_0, a_1, \dots, a_n, \dots$. Tuy nhiên, không nên nghĩ rằng trong trường hợp tổng quát mà chúng ta đang xem xét, $\alpha(z)$ là một hàm của biến $z$ theo nghĩa tổng quát. Khi chúng ta nói rằng $\alpha(z)$ là hàm sinh của chuỗi $a_0, a_1, \dots, a_n, \dots$, điều đó chỉ có nghĩa là $\alpha(z)$ là ký hiệu viết tắt của biểu thức hình thức ở phần đúng của (12).

Đối với những độc giả quen thuộc với khái niệm lũy thừa (giáo dục) của một chuỗi, cần nhấn mạnh rằng chuỗi chính thức (12) có thể được xem xét (đối với một số $z$ hoặc thậm chí đối với tất cả $z$), nhưng đồng thời sự bình đẳng (12) vẫn hợp pháp: xét cho cùng, $\alpha(z)$ không biểu thị tổng của chuỗi cho một giá trị nhất định $z$, mà chính là chuỗi chính thức.

Nhà toán học xuất sắc người Đức K. Weierstrass (1815-1897), người đã phát triển và đặt lũy thừa của chuỗi trên một cơ sở logic khác, chỉ xem xét chuỗi lũy thừa giảm dần, và chỉ trích Euler vì đã phạm những mánh khóe với “đa thức vô hạn”. Lý thuyết đại số hiện đại của chuỗi lũy thừa hình thức mà chúng ta đề cập ở đây đã được đáp ứng, tuy nhiên, về bản chất, nó gần với cách tiếp cận “ngây thơ” của Euler hơn là cấu trúc của lý thuyết phân tích của Weierstrass.

Chuỗi lũy thừa chính thức có thể được cộng và nhân. Hãy để, ngoài chuỗi $\alpha(x)$ (xem (12)), được cung cấp một biểu thức chính thức

⟦folio 14⟧

loạt điện
$$\beta(z) = b_0 + b_1z + b_2z^2 + \dots + b_nz^n + \dots$$
(13)

Khi đó tổng và tích của các chuỗi này được xác định bằng công thức tự nhiên:
$$\alpha(z) + \beta(z) = (a_0 + b_0) + (a_1 + b_1)z + \dots + (a_n + b_n)z^n + \dots,$$
$$\alpha(z) \cdot \beta(z) = a_0b_0 + (a_1b_0 + a_2b_1)z + (a_0b_2 + a_1b_1 + a_2b_0)z^2 + \dots$$
(14)
(các hành động này được thực hiện theo các quy tắc tương tự như các quy tắc thông thường để cộng và nhân các đa thức hữu hạn). Nhân tiện, xin lưu ý rằng đa thức thông thường có thể được coi là trường hợp đặc biệt của chuỗi lũy thừa hình thức - một chuỗi danh nghĩa trong đó tất cả các hệ số, bắt đầu từ một số, đều bằng 0. Trong trường hợp này, tất nhiên, phép cộng và phép nhân thông thường của các đa thức sẽ trùng với phép cộng và phép nhân của chúng dưới dạng chuỗi lũy thừa hình thức.

Hơn nữa, chuỗi quyền lực chính thức có thể được phân hóa và nội hóa. Theo định nghĩa
$$\frac{d}{d(z)} (\alpha(z)) = (\alpha(z))' = a_1 + 2a_2z + 3a_3z^2 + \dots + na_nz^{n-1} + \dots,$$
$$\int \alpha(z) = \int_0^z \alpha(x)dx = a_0z + \frac{a_1}{2}z^2 + \frac{a_2}{3}z^3 + \dots + \frac{a_n}{n+1}z^{n+1} + \dots$$

Đối với phép cộng và nhân chuỗi vô hạn được xác định theo cách này, các tính chất tương tự như số hoặc đa thức sẽ được thỏa mãn. Cụ thể là các luật giao hoán, tổ hợp và phân phối sẽ được thỏa mãn.

Giống như một số nguyên, bạn có thể trừ bất kỳ chuỗi nào khác khỏi chuỗi hình thức bất kỳ và lại thu được chuỗi lũy thừa hình thức. Phép chia trong miền chuỗi lũy thừa hình thức không phải lúc nào cũng thực hiện được, cũng như việc chia hai số nguyên không phải lúc nào cũng thực hiện được. Ví dụ: bạn không thể thực hiện việc đó trên số 0, nghĩa là bạn có thể thực hiện việc đó trên một hàng
$$0 = 0 + 0 \cdot z + 0 \cdot z^2 + \dots + 0 \cdot z^n + \dots$$
Không thể chia các “đơn vị”, tức là một chuỗi
$$1 = 1 + 0 \cdot z + 0 \cdot z^2 + \dots + 0 \cdot z^n + \dots$$
mỗi hàng
$$z = 0 + 1 \cdot z + 0 \cdot z^2 + \dots + 0 \cdot z^n + \dots$$

Thật vậy, giả sử có một chuỗi
$$\alpha(z) = a_0 + a_1z + a_2z^2 + \dots,$$
mà $\alpha(z) \cdot z = 1$, hoặc,
$$\left(a_0 + a_1z + a_2z^2 + \dots\right) \times \left(0 + 1 \cdot z + 0 \cdot z^2 + \dots\right) = 1 + 0 \cdot z + 0 \cdot z^2 + \dots$$

Nhưng từ công thức (14), ta suy ra $a_0 \cdot 0 = 1$, điều này chắc chắn là không thể.

Tương tự, người ta có thể chứng minh rằng $\alpha(z) = a_0 + a_1z + a_2z^2 + \dots$ chia hết cho $z^n$ khi và chỉ khi $a_0 = a_1 = a_2 = \dots = a_{n-1} = 0$.

Thật dễ dàng để kiểm tra xem 1 có chia hết cho $\alpha(z)$ nếu chỉ $a_0 \neq 0$ và các hệ số thu được theo một loạt các định nghĩa duy nhất.

Ví dụ, chúng ta hãy tìm kết quả của việc chia “đơn vị” cho chuỗi 1-z. Hãy để $(1-z)(a_0 + a_1z + a_2z^2 + \dots) = 1 + 0 \cdot z + 0z^2 + \dots$

Sau đó, mở ngoặc và đánh đồng hệ số cho cùng lũy ​​thừa $z$, ta thu được hệ đẳng thức
$$1 \cdot a_0 = 1, a_1 - a_0 = 0, a_2 - a_1 = 0, \dots, a_n - a_{n-1} = 0, \dots,$$
$a_0 = a_1 = \dots = a_n = \dots = 1$ đến từ đâu, tức là
$$\frac{1}{1-z} = 1 + z + z^2 + z^3 + \dots + z^n + \dots$$

Chúng tôi đã sử dụng công thức này (xem (3) ở trên và ghi chú ở trang 10) dưới một cái tên khác; ở đây công thức này là một đẳng thức thực sự cho chuỗi lũy thừa hình thức (và điều kiện $|z| < 1$ không liên quan gì đến nó).

Tổng và sản phẩm vô hạn

Trong lời giải bài toán khi bắt đầu nghiên cứu có vô số tác phẩm; tổng vô hạn cũng không kém phần hữu ích (đặc biệt, chuỗi lũy thừa hình thức có thể được coi là tổng vô hạn các chữ số). Để tránh nhầm lẫn, chúng tôi đưa ra các định nghĩa cần thiết về các khái niệm này.

Giả sử $\alpha_1(z), \alpha_2(z), \dots, \alpha_k(z), \dots$ là một chuỗi lũy thừa hình thức (cụ thể là các đa thức). Chúng ta muốn định nghĩa một tổng vô hạn và một tích vô hạn:
$$\left(\alpha_1(z)\right) + \left(\alpha_2(z)\right) + \dots + \left(\alpha_k(z)\right) + \dots,$$
(15)
$$\left(\alpha_1(z)\right) \cdot \left(\alpha_2(z)\right) \cdot \dots \cdot \left(\alpha_k(z)\right) \cdot \dots$$
(16)

theo cách tương tự như trên, nghĩa là bằng cách mở ngoặc và đưa những thứ tương tự

⟦folio 15⟧

các thành viên nhé. Tuy nhiên, định nghĩa như vậy không phù hợp trong trường hợp tổng quát. Thật vậy, ví dụ, nếu trong một “tích vô hạn”

$$(1+z)(1+z) \cdot \dots \cdot (1+z) \cdot \dots$$

Chúng ta bắt đầu mở dấu ngoặc và thêm những cái tương tự, chúng ta sẽ thấy ngay rằng hệ số, chẳng hạn như ở $z^2$, tăng lên và tiếp tục tăng khi chúng ta mở dấu ngoặc. Ví dụ này về cơ bản khác với công việc được phân tích trước đó

$$(1+z)(1+z^2)(1+z^4) \cdot \dots$$

$$\dots \cdot (1+z^{2m}) \cdot \dots$$

trong đó các hệ số ban đầu được thiết lập và thay đổi dần dần, do trong ngoặc “xa” không có đơn thức nào có biến hình thức ở mức “thấp”.

Vì vậy, tổng vô hạn (15) và tích vô hạn (16) chỉ được xác định nếu các hệ số ổn định khi mở ngoặc và đưa các số hạng tương tự - giống như chuỗi lũy thừa hình thức với các hệ số thu được theo cách này.

Định nghĩa chính xác của "ổn định" là thế này: với mọi số tự nhiên $d$ đều có một số tự nhiên $n$ sao cho đối với $n \geq N$ chuỗi $a_n(z)$ không chứa $z$ lũy thừa nhỏ hơn $d$.

Điều này kết thúc chuyến tham quan ngắn gọn của chúng ta vào lý thuyết chuỗi lũy thừa hình thức. Chúng tôi khuyên người đọc nên ngừng đọc tại thời điểm này, quay lại các ví dụ ở đầu bài viết và đảm bảo rằng họ không thực hiện các thủ thuật phức tạp với đa thức vô hạn mà hoàn toàn hợp pháp với chuỗi lũy thừa hình thức.

Tạo hàm

Một độc giả sâu sắc khi phân tích các ví dụ ở đầu bài viết có thể nhận thấy rằng sự thành công của phương pháp gắn liền với khả năng viết hàm sinh của chuỗi lũy thừa hình thức $a(z)$ ở dạng thu gọn. Vì vậy, ví dụ: hàm tạo của chuỗi 1, 1, 1, ... có thể được viết là $1/(1-z)$ hoặc

$$\frac{1}{1-z} = 1+z+z^2+\dots+z^n+... \tag{17}$$

Bắt đầu từ sự tương ứng này, người ta có thể thu được nhiều hàm sinh cụ thể khác. Ví dụ: nhân cả hai vế của (17) với $z$ và lấy đạo hàm, ta được

$$\left( \frac{z}{1-z} \right)' = 1+2z+3z^2+\dots+(n+1)z^n+... \tag{18}$$

Điều này có nghĩa là hàm $(z(1-z))' = 1/(1-z)^2$ đang tạo cho chuỗi 1, 2, 3, 4, ....

Nhân với $z$ và lấy đạo hàm lần nữa, ta được

$$\frac{1+z}{(1-z)^3} = 1+2^2z+3^2z^2+\dots+(n+1)^2z^n+... \tag{19}$$

Chúng tôi đã tìm thấy một biểu thức rõ ràng cho hàm tạo của chuỗi $1^2, 2^2, 3^2, 4^2$, ...

Những độc giả thành thạo trong việc chia đa thức với một “góc” có thể thu được sự tương ứng (19) theo một cách khác, cụ thể là bằng cách chia đa thức $1+z$ cho đa thức $1-3z+3z^2-z^3$.

Bắt đầu lại từ (17), nhưng bây giờ lấy tích phân, ta được

$$\int_0^z \frac{dx}{1-x} = \int_0^1 dx + \int_0^z xdx + \dots + \int_0^z x^ndx + \dots,$$

$$-\ln(1-z) = z + \frac{z^2}{2} + \frac{z^3}{3} + \dots$$

Ta thấy hàm sinh của dãy 1, 1/2, 1/3, ... sẽ là hàm $-\ln(1-z)/z$.

Chúng ta hãy giới hạn ở những ví dụ này và chuyển sang các vấn đề được giải quyết bằng phương pháp sinh hàm.

Bài toán

1. Chứng minh rằng mọi số nguyên dương đều có thể biểu diễn bằng ký hiệu kép một cách duy nhất.

Gợi ý. Hãy so sánh bài toán này với bài toán cân.

2. Chứng minh rằng mọi số nguyên dương đều có thể được biểu diễn dưới dạng ký hiệu thập phân một cách duy nhất.*

Gợi ý. Sử dụng sự tương ứng (chứng minh điều đó):

$$\left( 1+z+z^2+\dots+z^9 \right) \cdot \left( 1+z^{10}+z^{20}+...+z^{90} \right) \times \left( 1+z^{100}+z^{200}+...z^{900} \right) \cdot \dots = 1+z+z^2+z^3+\dots=1/(1-z).$$

3. Chứng minh rằng mọi số nguyên dương là tổng của các số hạng dương khác nhau. (Ví dụ: đối với số 6, có các cách chẵn có $6=1+5=2+4=1+2+3$ và $1+5=3+3=1+1+1+3=1+1+1+1+1+1$.)

(Cuối cùng xem trang 52)

*) Việc bạn biết sự thật này từ lớp một không thể coi là sự biện minh toán học cho tính đúng đắn của nó!
