---
id: 1975-1-lopshits-funktsionalnyie-uravneniya-1401bd9c
issue: kvant_1975_1
year: 1975
number: "1"
title: Phương trình hàm
authors:
  - Лопшиц А. М.
rubric: osnovnye-stati
page_first: 32
page_last: 37
page_labels: 30-35
tag: YMR9
lang: vi
source: kvant_digital
extraction: vision
content_sha256: aed11384ba930f125d2ed5cb494f05f07d64626ab6aa62bf102b9545f2b78381
prompt_sha256: draft-1
translated_from: content/ru/1975/01/articles/09_lopshits-funktsionalnyie-uravneniya-1401bd9c.md
source_content_sha256: 1ff2952722a800f417005a853b241ef3340e5fde6d37c8524023d10f86ff9465
translation_model: draft
translation_run: vi-draft-2026-10-31
translation_quality: draft
---

## Phương trình hàm
A. M. Lopshitz

Trước khi bắt đầu đọc bài viết này, bạn cần đảm bảo rằng bạn đã hiểu rõ khái niệm toán học quan trọng về “hàm”. Vì vậy, chúng tôi khuyên bạn nên đọc bài viết của A. N. Kolmogorov \*) và những trang sách giáo khoa phổ thông giới thiệu và giải thích khái niệm này.

Chúng ta hãy nhớ lại rằng để chỉ định hàm của một đối số thực, các giá trị của nó cũng là số thực (chúng ta sẽ chỉ xem xét các hàm như vậy trong bài viết của chúng ta), bạn nên: 1) trước hết chỉ ra “miền định nghĩa của nó”, nghĩa là chỉ ra tập hợp các số thực mà từ đó các giá trị $x$ của đối số sẽ được chọn và 2) xây dựng quy tắc rõ ràng theo đó đối với mỗi giá trị đó $x$ số thực tương ứng sẽ được xây dựng - nó được gọi là: giá trị của hàm tương ứng với giá trị đã chọn của đối số. Nếu bất kỳ hàm nào được biểu thị bằng, chẳng hạn như $Ф$, thì giá trị mà nó cần cho giá trị đối số đã chọn $x$ được biểu thị là $Ф(x)$.

Sẽ rất hữu ích khi đặt tên cho mỗi chức năng (mỗi quy tắc) đang được xem xét. Vì vậy, ví dụ, một hàm có miền định nghĩa là tập hợp tất cả các số thực và quy tắc xây dựng giá trị của các hàm tương ứng với định nghĩa

---
\*) «Kvant», 1970, Số 1 và 2.

⟦folio 30⟧

⟦column⟧

với giá trị $x$ của đối số, giá trị này được nhân với một số thực cố định $a$, được gọi là *hàm đồng nhất tuyến tính*.

Chính chức năng này sẽ là nhân vật chính của bài viết của chúng tôi.

**1. Hàm đồng nhất tuyến tính là hàm cộng**

Trong số các hàm khác nhau được nghiên cứu trong toán học, người đọc chắc chắn nhận thấy một hàm nổi bật so với các hàm còn lại vì tính đơn giản đặc biệt của nó - hàm $Л_a$ này được xác định cho tất cả các giá trị thực của đối số $x$ và các giá trị của nó được xác định bởi công thức

$$Л_a(x) = ax$$

(trong đó $a$ là một số thực đã cho). Chúng tôi gọi nó là: *hàm đồng nhất tuyến tính*. Nó được tìm thấy trong tất cả các vấn đề vật lý (và không chỉ vật lý) trong đó các đại lượng tỷ lệ được nghiên cứu.

Quan sát của giáo viên cho thấy rằng học sinh cảm nhận rất rõ một trong những tính chất của nó, tốt đến mức chúng thường (thậm chí quá thường xuyên!) gán nó cho những chức năng khác phức tạp hơn. Trên thực tế, bạn đọc sinh viên có để ý rằng một số bạn cùng lớp khi bắt đầu nghiên cứu các hàm lượng giác đều tin rằng sin của tổng hai góc bằng tổng

sin của những góc này là gì? Bản chất của sai lầm “trẻ con” này là một học sinh, khi đã làm quen với một số hàm mới—hãy gọi nó là $\Phi$—có xu hướng tin rằng nó phải có tính chất “đơn giản” sau:

$$\Phi(x_1 + x_2) = \Phi(x_1) + \Phi(x_2). \qquad (1)$$

Một hàm đồng nhất tuyến tính thực sự (kiểm tra!) có đặc tính này, nhưng than ôi, các hàm khác được nghiên cứu ở trường *không có nó*.

Bất kỳ hàm nào có thuộc tính được biểu thị bằng đẳng thức (1) đều được gọi là hàm *cộng*. Có thể dễ dàng kiểm tra xem hàm *tuyến tính không đồng nhất*, tức là hàm $G$, được xác định cho bất kỳ giá trị thực nào của đối số theo công thức

$$G(x) = ax + b \qquad (b \neq 0),$$

không còn là chất phụ gia; theo cách tương tự, các hàm được xác định cho bất kỳ giá trị nào của đối số $x$, các giá trị của chúng được xác định theo các quy tắc sau, không có tính chất cộng:

$$x \to ax^2 + bx + c,$$
$$x \to \frac{1}{x^2 + a^2},$$

và rất nhiều tính năng khác.

Người đọc sẽ hỏi liệu có ít nhất một hàm cộng của một đối số thực khác với một hàm đồng nhất tuyến tính hay không.

Anh ấy sẽ nhận được Đáp số cho câu hỏi này nếu không quá lười đọc kỹ bài viết ngắn này.

**2. Nghiên cứu hàm cộng tùy ý**

1. Nếu hàm $\Phi$ có thuộc tính (1), thì dễ dàng kiểm tra xem nó cũng có thuộc tính sau:

$$\Phi(x_1 + x_2 + x_3) =$$
$$= \Phi(x_1) + \Phi(x_2) + \Phi(x_3). \quad (1'),$$

Thật vậy, do tính chất (1)

⟦column⟧

chúng tôi có

$$\Phi(x_1 + x_2 + x_3) = \Phi((x_1 + x_2) + x_3) =$$
$$= \Phi(x_1 + x_2) + \Phi(x_3) =$$
$$= \Phi(x_1) + \Phi(x_2) + \Phi(x_3).$$

Người đọc sẽ không khó để chứng minh rằng

$$\Phi(x_1 + x_2 + \ldots + x_n) =$$
$$= \Phi(x_1) + \Phi(x_2) + \ldots + \Phi(x_n) \qquad (1'')$$

(tất nhiên bạn sẽ phải sử dụng phương pháp quy nạp toán học).

Công thức $(1'')$ hàm ý đẳng thức

$$\Phi(nx) = n\Phi(x) \qquad (2)$$

($n$ là số dương *số nguyên* tùy ý).

Vì đẳng thức (2) hợp lệ với mọi giá trị $x$, nên chúng ta đặt $x$ bằng $\frac{m}{n} y$ ($m$ và $n$ là số nguyên dương). chúng tôi nhận được

$$\Phi(my) = n\Phi\left(\frac{m}{n} y\right).$$

Sử dụng lại đẳng thức (2), ta được

$$m\Phi(y) = n\Phi\left(\frac{m}{n} y\right),$$

đó là

$$\Phi\left(\frac{m}{n} y\right) = \frac{m}{n} \Phi(y). \qquad (2')$$

Vì vậy, chúng tôi tin rằng nếu hàm $\Phi$ là hàm cộng, thì với bất kỳ số hữu tỉ dương nào $\alpha = \frac{m}{n}$ đẳng thức đúng

$$\Phi(\alpha x) = \alpha\Phi(x) \qquad (3)$$

(bất kể số thực $x$ là bao nhiêu!).

Mối quan hệ đáng chú ý này mang lại cho chúng ta *khả năng tính toán cho bất kỳ hàm cộng tính nào $\Phi$ giá trị của nó cho bất kỳ giá trị hữu tỉ dương nào $x$ của đối số, nếu chỉ một trong các giá trị của nó được đưa ra - cụ thể là giá trị cần có khi đối số bằng một.*

Thực tế, đặt $x$ bằng một trong (3), ta thu được

$$\Phi(\alpha) = \alpha\Phi(1). \qquad (4)$$

⟦folio 31⟧

⟦folio 32⟧

2. Không kém phần ngạc nhiên là *công thức (4) để tính các giá trị của bất kỳ hàm cộng Ф nào có thể áp dụng cho tất cả các giá trị hữu tỷ của đối số* (và không chỉ cho các giá trị dương của nó).

a) Trước hết, hãy đảm bảo rằng

$$\Phi(0) = 0\Phi(1),$$

đó là, cái gì

$$\Phi(0) = 0.$$

Thật vậy, do tính cộng của hàm $\Phi$ nên đẳng thức đúng

$$\Phi(x + 0) = \Phi(x) + \Phi(0),$$

đó là

$$\Phi(x) = \Phi(x) + \Phi(0)$$

và do đó

$$\Phi(0) = 0. \qquad (5)$$

b) Hơn nữa, do tính cộng của hàm $\Phi$ nên ta có

$$\Phi(x) + \Phi(-x) =$$
$$= \Phi(x + (-x)) = \Phi(0)$$

từ đâu (nhờ (5))

$$\Phi(-x) = -\Phi(x) \qquad (6)$$

(bất kể giá trị thực của $x$ có thể là bao nhiêu!).

Vì vậy, chúng tôi tin chắc rằng *bất kỳ hàm cộng nào cũng là hàm số lẻ*.

Bây giờ chúng ta đã có thể chứng minh rằng công thức (4) phù hợp để tính các giá trị của hàm cộng và cho các giá trị hữu tỉ *âm* của đối số.

Đặt $\beta$ là một số hữu tỉ âm nào đó; khi đó, nhờ vào (6),

$$\Phi(\beta) = -\Phi(-\beta). \qquad (7)$$

Ở đây $(-\beta)$ đã là số hữu tỉ dương nên ta có thể sử dụng công thức (4)

$$\Phi(-\beta) = (-\beta)\,\Phi(1).$$

Thay thế mối quan hệ cuối cùng vào (7), chúng ta thu được

$$\Phi(\beta) = \beta\Phi(1),$$

đó là điều chúng tôi muốn chứng minh.

### 3. Chức năng không bị giới hạn từ phía trên

“Đây là đáp số cho câu hỏi được đặt ra ở cuối đoạn đầu tiên của phần này

⟦column⟧

bài viết, người đọc sẽ nói: không có hàm cộng nào ngoài hàm tuyến tính thuần nhất!”

Không, điều đó không đúng!

Suy cho cùng, chúng ta chỉ chứng minh được công thức (4) cho các giá trị hữu tỉ $x$. Chúng tôi không có lý do gì để sử dụng nó để tính các giá trị của hàm cộng tính $\Phi$ cho $x$, chẳng hạn như bằng $\sqrt{2}$.

Do đó, không có gì đáng ngạc nhiên khi các nhà toán học tiếp tục kiên trì tìm kiếm một hàm cộng tính khác với hàm đồng nhất tuyến tính.

Thật sự rất khó để tìm thấy một tính năng như vậy! Rốt cuộc, chúng ta đã thấy rằng các giá trị của nó (nếu nó tồn tại!) Phải trùng với các giá trị của một số hàm đồng nhất tuyến tính $x \to xa$, nói một cách đại khái là “gần như” cho tất cả $x$: mặc dù các số hữu tỷ không làm cạn kiệt tập hợp tất cả các số thực, nhưng trên thực tế, chúng đủ cho lời giải bài toán gần đúng với bất kỳ mức độ chính xác nào.

Một ví dụ về hàm số này được nhà toán học người Đức Hamel \* xây dựng vào năm 1905).

Nhưng thật không may, trong bài viết này, chúng tôi sẽ không thể giới thiệu cho người đọc ví dụ này - ngay cả khi chúng tôi đi chệch khỏi cách trình bày toán học nghiêm ngặt. Lý luận của Hamel độc đáo đến mức chỉ có thể hiểu đầy đủ nó bằng các kỹ năng và văn hóa toán học có được nhờ nghiên cứu toán học lâu dài. Do đó, chúng tôi lưu ý ở đây chỉ một thuộc tính quan trọng của hàm do Hamel xây dựng: *trong số các giá trị mà nó lấy một giá trị được chọn tùy ý*

---

\*) Bài viết của Hamel được đăng trên tạp chí Matematiche Annalen ở tập 60, tr. 454-462, 1905

Chúng tôi không biết bất kỳ bản trình bày nào về kết quả này của Hamel bằng tiếng Nga.

*khoảng* $(p,\ q)$ (*tức là tại* $p \leqslant x \leqslant q$), *có một số lớn hơn bất kỳ số dương tùy ý nào.*

Hàm như vậy được gọi là *không bị chặn từ phía trên* trên khoảng $(p,\ q)$.

Một ví dụ về hàm không bị giới hạn ở trên, chẳng hạn như trong khoảng $(-1,\ 1)$, là hàm $H$, được xác định bởi công thức $H(x) = \dfrac{1}{x}$ cho các giá trị của đối số không bằng 0 và lấy giá trị 0 cho $x = 0$ (Hình 1). Một ví dụ khác là hàm được xác định bởi công thức

$$P(x) = \frac{1}{(x-p)(x-q)}$$

cho $x \neq p$ và $x \neq q$ và lấy giá trị 0 cho $x = p$ và $x = q$.

Hàm này không bị giới hạn trên trên bất kỳ khoảng nào chứa điểm $p$ hoặc điểm $q$ (ví dụ: xem Hình 2).

Tuy nhiên, trong cả hai ví dụ này đều có một khoảng trong đó các hàm này vẫn bị chặn từ trên xuống (một hàm được gọi là bị chặn từ trên xuống trong một khoảng nhất định nếu các giá trị mà nó lấy trong khoảng này vẫn nhỏ hơn một số số được xác định trước). Nhưng hàm Hamel, như chúng ta đã nói, không bị giới hạn ở trên bởi bất kỳ (tuy nhiên)

⟦column⟧

nhưng trong một khoảng nhỏ!). Điều này làm cho khám phá của Hamel trở nên thú vị hơn: ông không chỉ xây dựng một ví dụ về hàm cộng không tuyến tính mà còn đưa các hàm vào toán học có đặc tính “lạ” (đối với nhận thức thị giác): chúng không bị giới hạn ở trên trong bất kỳ khoảng nào.

Bây giờ chúng ta hãy bỏ qua việc xem xét các hàm “*lạ*” như vậy và tìm kiếm một *hàm cộng*, *bị chặn từ phía trên ít nhất trong một khoảng*.

**4. Hàm cộng tính được giới hạn từ trên trên ít nhất một khoảng**

1. Giả sử hàm cộng $\Phi$ được giới hạn từ phía trên trong khoảng $(p,\ p+s)$, trong đó $s$ là một số dương nào đó. Dễ dàng nhận thấy rằng $\Phi$ cũng bị chặn ở trên trên khoảng $(0,\ s)$.

Thật vậy, giả sử $x$ là số dương bất kỳ không lớn hơn $s$ thì số $p + x$ nằm trong khoảng $(p,\ p+s)$ và do đó, $\Phi(p+x)$ nhỏ hơn một số đã cho $M$; do tính cộng $\Phi$,

$$\Phi(p) + \Phi(x) < M$$

và do đó

$$\Phi(x) < M - \Phi(p)$$

với mọi giá trị $x$ nằm trong khoảng $(0,\ s)$.

⟦figure⟧
Cơm. 1.

⟦figure⟧
Cơm. 2.

3 Lượng tử số 1

⟦folio 33⟧

⟦folio 34⟧

2. Bây giờ chúng ta hãy xem xét một hàm mới $G$, giá trị của hàm này đối với giá trị tùy ý $x$ của đối số sẽ được tính bằng công thức

$$G\,(x) = \Phi\,(x) - \frac{\Phi\,(s)}{s}\,x. \qquad (8)$$

Hàm $G\,(x)$ cũng được giới hạn từ phía trên trên khoảng $(0,\ s)$: giá trị của nó trên khoảng này nhỏ hơn $M' = M - \Phi(p) + |\,\Phi\,(s)\,|$.

3. Rõ ràng (xem (8)) là hàm $G$ là hàm cộng và hàm $G\,(s) = 0$. Đó là lý do tại sao

$$G\,(x + s) = G\,(x) + G(s) = G\,(x)$$

và do đó số $s$ *dấu chấm* của hàm $G$!

Do đó, giá trị mà hàm $G$ lấy cho một giá trị nào đó của đối số $x$ bằng với giá trị mà nó lấy cho một giá trị nào đó của đối số trong khoảng $(0,\ s)$, và do đó nó nhỏ hơn $M'$, tức là, $G(x) < M'$ đối với bất kỳ giá trị nào $x$.

4. Bây giờ chúng ta đã có thể chứng minh nhận định - có lẽ gây bất ngờ cho người đọc:

*Mọi giá trị của hàm $G$ đều bằng 0.*

Chúng tôi sẽ làm điều này “bằng sự mâu thuẫn”. Giả sử với bất kỳ giá trị dương $x_0$ nào của đối số $x$, nhỏ hơn $s$ thì giá trị tương ứng $G(x_0)$ khác 0, $G(x_0) \neq 0$.

Khi đó, do tính cộng của hàm $G$ nên ta có (xem công thức (4))

$$G\,(\alpha x_0) = \alpha\,G(x_0).$$

Chọn $\alpha$ sao cho

$$\alpha G\,(x_0) > M',$$

chúng tôi sẽ nhận được

$$G\,(\alpha x_0) > M'.$$

Và điều này mâu thuẫn với thực tế là $G(x) < M'$ với mọi $x$. Do đó, giả định của chúng tôi là không chính xác và $G\,(x_0) = 0$ đối với bất kỳ giá trị nào của $x_0$ nằm trong khoảng $(0,\ s)$. Xét rằng hàm $G\,(x)$ có một khoảng thời gian $s$, chúng ta đi đến kết luận rằng

$$G\,(x) = 0 \qquad (9)$$

với bất kỳ giá trị nào của $x$.

⟦column⟧

5. Bây giờ quay lại định nghĩa (8) của hàm $G$, nhờ vào (9), chúng ta thu được rằng

$$\Phi\,(x) = ax \quad \left(\text{где } a = \frac{\Phi\,(s)}{s}\right).$$

Có lẽ bạn đọc đã đoán trước được kết quả này. Đây là công thức bằng lời của nó: *nếu một hàm cộng được giới hạn từ phía trên trên ít nhất một khoảng (thậm chí nhỏ tùy ý), thì đó là hàm đồng nhất tuyến tính!*

**5. Phương trình hàm**

Kết quả này cũng có thể được phát biểu như sau:

Bài toán - *tìm một hàm $\Phi$ được xác định cho bất kỳ giá trị thực nào của đối số và có thuộc tính mà đối với mọi giá trị $x$ và $y$ của đối số thì đẳng thức đúng*

$$\Phi(x + y) = \Phi(x) + \Phi(y) \qquad (10)$$

có rất nhiều lời giải. Và ngay cả khi chúng ta chỉ tìm những lời giải $\Phi$ của *phương trình* này được giới hạn từ phía trên - ít nhất là trong một khoảng nào đó - thì vẫn sẽ có rất nhiều lời giải. Nhưng bất kỳ lời giải nào như vậy đều là một hàm đồng nhất tuyến tính, nghĩa là một hàm có dạng

$$x \to ax$$

($a$ là một số thực).

Cần phải nói rằng bài toán này thường được hình thành như sau:

*Tìm hàm $\Phi$ thỏa mãn phương trình hàm số (10).*

Bài toán, trong đó bạn cần tìm một hàm có một số thuộc tính cụ thể, hiếm khi được tìm thấy trong trường học, nhưng thường được xem xét trong toán học và đóng một vai trò quan trọng trong đó. Đây là một cái khác như thế này bài toán:

*Tìm một hàm $G$ có thuộc tính cho mọi giá trị $x$ và $y$ của đối số (tất nhiên thuộc miền định nghĩa của hàm tìm kiếm $G$ đúng*

⟦folio 35⟧

*bình đẳng*
$$G(x + y) = G(x) + G(y) + p, \qquad (11)$$
*trong đó* $p$ - *một số đã cho.*

Người đọc có thể dễ dàng kiểm tra; chức năng là gì
$$x \to ax - p$$
là giải pháp của cô ấy. Thật hấp dẫn khi tìm hiểu xem có lời giải nào khác không?

bài toán này cũng thú vị: giải phương trình hàm
$$H(x + 2y) + H(x) = 2H(x + y). \qquad (12)$$
Dễ dàng kiểm chứng rằng hàm
$$x \to ax + b$$
($a$ và $b$ là các số tùy ý) là nghiệm của phương trình (12). Có lời giải nào khác không?

Các nhà toán học xuất sắc trong quá khứ - và trong số đó như Euler, Gauss, Cauchy, Abel, Lobachevsky, Weierstrass, Darbu, Gilbert - thường tìm đến các phương trình hàm và sử dụng chúng cho lời giải nhiều câu hỏi quan trọng. Nghiên cứu có hệ thống về phương trình hàm được Koshy bắt đầu - vào năm 1821, ông xuất bản Khóa học phân tích \*) (ông dạy khóa học này tại Viện Bách khoa Paris). Trong đó, ông đã nghiên cứu chi tiết (nhưng vẫn chưa đầy đủ) phương trình hàm (10) được xem xét trong bài viết của chúng tôi—bây giờ nó được gọi là “phương trình hàm Cauchy”; phương trình này đặc biệt thường được sử dụng trong các lý thuyết toán học khác nhau. Cùng với đó, Cauchy còn xét các phương trình hàm sau:
$$\Phi(x + y) = \Phi(x)\Phi(y),$$
$$G(xy) = G(x)G(y),$$
$$H(xy) = H(x) + H(y).$$

Người đọc chắc chắn sẽ có thể tìm thấy “thương” lời giải của các phương trình này. Việc tìm thấy tất cả lời giải cho mỗi người trong số họ sẽ khó khăn hơn nhiều. Chúng tôi hy vọng sẽ nói về điều này trong một bài viết khác.

---
\*) A. C a u c h y, Cours d'analyse de l'Ecole polytechnique 1. Analyse algebreque, V (Paris, 1821).

3\*

⟦column⟧

## Logic bắt đầu từ đâu?

*(Kết thúc. Xem phần đầu ở trang 24)*

4) *Hàm ý* của các mệnh đề $A$ và $B$ (ký hiệu là $A \supset B$, đọc là “$A$ ngụ ý $B$”, hoặc “Từ $A$ theo sau $B$”, hoặc “Nếu $A$ thì $B$”) là sai nếu *tiền đề* $A$ là đúng và *kết luận* $B$ là sai và đúng trong mọi trường hợp còn lại:

| $A$ | $B$ | $A \supset B$ |
|---|---|---|
| Và | Và | Và |
| Và | tôi | tôi |
| tôi | Và | Và |
| tôi | tôi | Và |

5) *Sự tương đương* của các câu $A$ và $B$ ($A \sim B$ đọc “$A$ tương đương với $B$”) là đúng nếu $A$ và $B$ có cùng giá trị chân lý và sai nếu giá trị chân lý của $A$ và $B$ khác nhau:

| $A$ | $B$ | $A \sim B$ |
|---|---|---|
| Và | Và | Và |
| Và | tôi | tôi |
| tôi | Và | tôi |
| tôi | tôi | Và |

Tất nhiên, bản thân những định nghĩa này khá đơn giản và dễ nhớ. Nhưng họ đặt ra một số câu hỏi mà không có đáp số thì việc thảo luận thêm về chủ đề này sẽ hoàn toàn vô nghĩa. Ví dụ, tại sao chúng ta định nghĩa và đặt tên cho các hoạt động này theo cách này mà không phải cách khác? Nói cách khác, mối liên hệ giữa tất cả các bảng này và ý nghĩa “thông thường” của những từ nổi tiếng như “không”, “và”, “hoặc”, “nên” là gì? Đâu là lý do để coi những hoạt động này là “thiết yếu”? Những hoạt động logic (không cơ bản) nào khác đang có và có thể có? Và, nói đúng ra, điều gì là “hợp lý” ở họ? Hiện tại, chúng tôi sẽ giới hạn bản thân trong lời khuyên: hãy tự mình suy nghĩ về tất cả những câu hỏi này.
