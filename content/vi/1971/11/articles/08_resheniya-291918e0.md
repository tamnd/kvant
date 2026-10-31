---
id: 1971-11-resheniya-291918e0
issue: kvant_1971_11
year: 1971
number: "11"
title: Lời giải bài toán M70—M73; F79—F82
rubric: zadachnik-kvanta
rubric_sub: Задачник «Кванта»
page_first: 28
page_last: 36
page_labels: 26-34
tag: AZFB
lang: vi
source: kvant_digital
extraction: vision
content_sha256: 77d97f750e51867e952070e58a7d4c5fdb2594d4c79938a8d97d9cafc701b567
prompt_sha256: draft-1
translated_from: content/ru/1971/11/articles/08_resheniya-291918e0.md
source_content_sha256: 80e96e1f08f3a4f0944de1269a59fe58d575212f36a9a6fca2c527936bf59ce8
translation_model: draft
translation_run: vi-draft-2026-10-31
translation_quality: draft
---

⟦folio 26⟧

Trong số này, chúng tôi xuất bản lời giải bài toán M70—M73

M70

Cho $l_1, l_2, \dots, l_n$ là một số đường thẳng trong mặt phẳng, trong đó có hai đường thẳng cắt nhau. Chứng minh rằng có thể, và theo một cách duy nhất, chọn từng đường thẳng này tại điểm $X_1, X_2, \dots, X_n$ sao cho phân phối lại được khôi phục tại điểm $X_i$ cho đường $l_i$ đi qua điểm $X_{i+1}$ (với tất cả $i=1, 2, \dots, n-1$) và phân phối lại được khôi phục thành $l_n$ tại điểm $X_n$ đi qua điểm $X_1$.

Cố gắng xây dựng và chứng minh một định lý tương tự trong không gian.

bài toán này cũng có thể được hình thành như sau. Giả sử $p_i$ là ánh xạ gán cho mỗi điểm $M$ (trên mặt phẳng) hình chiếu của nó lên đường thẳng $l_i$, tức là $p_i(M)$ là cơ sở của phân phối lại được thả từ điểm $M$ xuống đường thẳng $l_i$. Cần chứng minh rằng trên đường thẳng $l_1$ tồn tại một điểm duy nhất $X_1$ sao cho sau ánh xạ $n$

$$X_1 \xrightarrow{p_n} X_n \xrightarrow{p_{n-1}} X_{n-1} \xrightarrow{p_{n-2}} \dots$$

biến thành chính nó.

Đối với một điểm tùy ý $X$ của đường $l_1$ biểu thị qua $f(X)$ điểm trên đường $l_1$ mà nó đi qua

$$X$$ sau ánh xạ $n$ $p_n, p_{n-1}, \dots, p_1$ (Hình 1); nó được viết như thế này:

$$f = p_1 \circ p_2 \circ \dots \circ p_n.$$

Hãy chọn gốc và hướng trên mỗi dòng của chúng ta $l_i$, nghĩa là chúng ta sẽ biến mỗi dòng thành một trục số (chúng ta chọn cùng một đơn vị tỷ lệ trên tất cả các dòng). (Chúng tôi xác định một điểm (trên một đường) và số tương ứng của nó—tọa độ của nó—để các bản đồ $p_1, p_2, \dots, p_n$ và $f$ giờ đây có thể được coi là các hàm

⟦folio 27⟧

Mỗi số được gán một số mới.

Hãy để chúng tôi chứng minh rằng ánh xạ $f$ là tuyến tính: $f(x) = ax + b$.

Để làm được điều này, chỉ cần chứng minh ba khẳng định hiển nhiên sau đây là đủ.

(1) Nếu $l$ và $l'$ là hai đường thẳng và $p : l \rightarrow l'$ là bản đồ liên kết từng điểm với hình chiếu của nó lên $l'$, thì $p$ là bản đồ tuyến tính.

(2) Nếu $p_1$ và $p_2$ là bản đồ tuyến tính thì $p_1^\circ p_2$ cũng vậy.

(3) Nếu $p_1, p_2, \dots, p_n$ là bản đồ tuyến tính thì $f = p_1^\circ p_2^\circ \dots p_n^\circ$ cũng là bản đồ tuyến tính.

Rõ ràng (3) suy ra từ (2) bằng quy nạp. Kiểm tra (2): nếu $p_1(x) = a_1x + b_1$ và $p_2(x) = a_2x + b_2$ thì $(p_1^\circ p_2)(x) = p_1(p_2(x)) = a_1a_2x + (a_1b_2 + b_1)$. Để chứng minh (1), hãy kiểm tra công thức này:

$$p(x) = x \cos \alpha + c,$$

trong đó $\alpha$ là góc giữa hướng dương của trục $Ox$ và $O'x'$, $c$ là tọa độ của điểm $p(O)$ trong hệ thống $Ox'$ (Hình 2; cũng xem xét trường hợp khi các đường thẳng $l$ và $l_1$ song song).

Bây giờ với lời giải bài toán, đủ để chỉ ra rằng phương trình tuyến tính $x = ax + b$ có ​​lời giải và chỉ có một. Nếu không phải như vậy (nghĩa là nếu không có lời giải hoặc nhiều hơn một), thì $a = 1$. Hãy để chúng tôi chứng minh rằng điều này không thể xảy ra. Lưu ý rằng với mỗi phép chiếu $p_k$: $l_{k+1} \rightarrow l_k$ khoảng cách giữa hai điểm bất kỳ không tăng:

$$|p_k(x) - p_k(x')| \leq |x - x'|,$$

và nếu các đường $l_{k+1}$ và $l_k$ không song song thì sẽ giảm đi rất nhiều. Suy ra điều đó đối với hai điểm bất kỳ $x$ và $x'$

$$|f(x) - f(x')| < |x - x'|.$$

Nhưng nếu $a = 1$, tức là nếu $f(x) = x + b$, thì $f$ bảo toàn khoảng cách giữa hai điểm bất kỳ (nó chỉ dịch chuyển tất cả chúng một khoảng $b$). Chúng tôi có một sự mâu thuẫn. Bằng chứng là hợp pháp.

Bài toán M70 và lời giải của chúng ta đã được thiết lập lại mà không có bất kỳ thay đổi nào đối với trường hợp các đường thẳng không nằm trên một mặt phẳng mà nằm trong không gian (các đường ở giữa của chúng cũng có thể giao nhau). Trong trường hợp này, $p_k$ có nghĩa là phép chiếu lên đường $l_k$ trong không gian: một ánh xạ tương ứng với từng điểm mà đáy của đường vuông góc thả từ điểm này lên đường $l_k$.

Hình 2. Ánh xạ gán mỗi điểm trên một đường thẳng hình chiếu của nó lên một đường thẳng khác được viết dưới dạng hàm tuyến tính.

Hình 3. Điểm $X_1$, đối với $f(X_1) = X_1$, trên thực tế có thể dễ dàng tìm ra phương pháp xấp xỉ liên tiếp: bắt đầu từ một điểm tùy ý $X$, hạ đường vuông góc với các đường thẳng đã cho và tìm đường vuông góc liên tiếp sau mỗi “chu kỳ” của điểm $X' = f(X)$ $X'' = f(X')$, v.v. Không khó để chứng minh rằng các khoảng cách $|X - X_1|, |X' - X_1|, |X'' - X_1|$, ... tạo thành một cấp số nhân giảm vô hạn với giá trị $|a| < 1$, do đó bằng cách lặp lại việc xây dựng nhiều lần, chúng ta có thể tìm thấy vị trí của điểm $X_1$ với bất kỳ độ chính xác nào. Một phương pháp tương tự rất hữu ích để tìm các phương trình lời giải có dạng $f(X) = X$; nó sẽ được áp dụng khi hàm $f$ giảm khoảng cách giữa hai điểm bất kỳ. Trong trường hợp của chúng ta, khi $f$ là một hàm tuyến tính, có thể tìm thấy chính xác lời giải của phương trình $f(X) = X$ (hãy nghĩ về cách tìm điểm $X_1$ nếu biết $X, X'$ và $X''$).

⟦folio 28⟧

Có một khả năng khái quát hóa khác:
cùng nhau nhìn vào các mặt phẳng thẳng. Có thể
chẳng hạn, hãy chứng minh thực tế sau: nếu dữ liệu $n$
các mặt phẳng trong không gian, trong đó
 có ba đường cắt nhau tại một điểm
thì điều đó là có thể và theo cách duy nhất
chọn trên mỗi mặt phẳng này
điểm $X_k$ ($k=1, \dots, n$) sao cho
ndikulier, được khôi phục tại điểm $X_k$ để đồng-
mặt phẳng tương ứng đi qua
điểm $X_{k+1}$ (và $X_{n+1}=X_1$). Giờ thì đã rồi
$f=p_1 \cdot p_2 \dots p_n$ sẽ là ánh xạ tuyến tính
mặt phẳng với mặt phẳng và tọa độ sẽ được viết như sau: $f(x, y)=$ $(x', y')$, trong đó $x'=a_1x+b_1y+c_1$, $y'=a_2x+b_2y+c_2$.

Chứng minh rằng nếu hệ phương trình
$$\begin{cases} x=a_1x+b_1y+c_1, \\ y=a_2x+b_2y+c_2 \end{cases}$$
không có lời giải hoặc có nhiều hơn một
lời giải (điều này xảy ra nếu $(a_1-1)(b_2-1)−a_2b_1=0$), thì hệ thống $x=a_1x+b_1y$, $y=a_2x+b_2y$ có lời giải $(x_0, y_0)$, khác với $(0,0)$ và ánh xạ $f$ không thay đổi sự khác biệt
đứng giữa các điểm $(0,0)$ và $(x_0, y_0)$, điều này không thể xảy ra trong bài toán của chúng tôi.

Nanmore đầy đủ lời giải bài toán tại-
Slania F. Schmidel từ Moscow, Yu. Obolonkov từ Voronezh, M. Rozov từ Minsk.

M71

Một bảng hình chữ nhật gồm $m$ hàng và $n$ cột chứa đầy các số. Hãy sắp xếp lại các số ở mỗi dòng theo thứ tự tăng dần. Chứng minh rằng nếu sau đó bạn sắp xếp lại các số ở mỗi cột theo thứ tự tăng dần thì ở mỗi hàng chúng vẫn xuất hiện theo thứ tự tăng dần.

Hãy suy nghĩ về điều gì sẽ xảy ra nếu bạn hành động theo một thứ tự khác: trong bảng ban đầu, trước tiên hãy sắp xếp lại các số theo thứ tự tăng dần trong các cột, sau đó là trong các hàng: kết quả sẽ giống như bảng trong trường hợp đầu tiên hay một bảng khác?

Hãy xem xét một bảng trong đó các số trong mỗi hàng theo thứ tự tăng dần và chứng minh rằng nếu $l<r$ thì số lớn nhất trong cột thứ $r$ (chúng ta ký hiệu là $b$) không nhỏ hơn số lớn nhất trong cột thứ $l$ (chúng ta ký hiệu là $a$). Thật vậy, số tại giao điểm của đường có $a$ và cột $r$ không nhỏ hơn $a$ (vì các số trong đường thẳng theo thứ tự tăng dần).

Tương tự, người ta có thể chứng minh rằng số lớn thứ $k$ (tính từ số lớn nhất trong cột $r$-cột $(b_k)$) không nhỏ hơn số lớn nhất thứ $k$ trong cột $l$

⟦folio 29⟧

Các bảng khác nhau được đọc. Để xác minh điều này, chỉ cần đưa ra một ví dụ là đủ (Hình 5).

Đã quyết định đúng bài toán P. Ayulov, A. Brevdo, L. Brauzinsky, G. Vysotskaya, S. Grigoryan, A. Gordenko, I. Jabbarov, A. Kleyin, A. Kmizhnerman, I. Kochubeevsky, G. Levin, M. Preezer, E. Skryt, A. Slinkin, A. Chernyak và những người khác. Ngoài lời giải, còn có nhiều cái khác gần gũi với chúng ta trong đó quá trình cảm ứng được thực hiện; Trong một số công trình, người ta đã chứng minh rằng có thể sắp xếp lại từng cột liên tiếp để các số luôn xuất hiện trong các hàng theo thứ tự tăng dần.

N. B. Vasiliev

M72

Giải phương trình
$$\sqrt[3]{1-x} + \sqrt[3]{1+x} = p,$$
(1)
trong đó $p$ là số thực tùy ý.

Nỗ lực ngây thơ lời giải: lập phương cả hai vế của phương trình
$$2 + 3\sqrt[3]{1-x^2}\left(\sqrt[3]{1-x} + \sqrt[3]{1+x}\right) = p^3$$
(2)
và thay thế ở đây đẳng thức ban đầu (1):
$$2 + 3p\sqrt[3]{1-x^2} = p^3.$$ (3)
Bây giờ thật dễ dàng tìm thấy $x$:
$$x = \pm \sqrt{1 - \left(\frac{p^3 - 2}{3p}\right)^3}.$$ (4)
Chúng tôi đã được gửi nhiều lá thư trong đó đáp số này đã được nhận (theo cách này và cách khác). Cũng có khá nhiều chữ cái trong đó việc tìm thấy một tập hợp các giá trị $p$ mà công thức (4) có ý nghĩa là đúng:
$$p = -1, \quad 0 < p \leq 2.$$
Một số người thậm chí còn nhận thấy rằng nên loại bỏ giá trị $p = -1$ vì giá trị $x = 0$ được đưa ra bởi công thức $p$ là không phù hợp. Nhưng người ta chưa chứng minh được rằng với mọi $p$, $0 < p \leq 2$ thì giá trị $x$ cho bởi công thức (4) đều là nghiệm. (Thông thường, cách chứng minh như vậy chỉ là một phép thử, nhưng ở đây nó rất khó thực hiện.) Và điều này phải được chứng minh, vì không phải tất cả các phép biến đổi được thực hiện ở trên đều tương đương: phương trình (2) không tương đương với (3). Để thấy điều này, hãy thay thế $x = 0$, $p = -1$ trong (2) và (3). Bình đẳng (3) sẽ trở về chỗ cũ, nhưng (2) thì không. Vì vậy, những phát biểu trong các chữ cái cho rằng phép biến đổi này tương đương là không chính xác. (Thật vậy: hãy thử suy ra (2) từ (3). Bạn sẽ phải sử dụng đẳng thức (1), điều kiện bài toán, nhưng điều này không thể thực hiện được, vì đây chính xác là điều cần phải chứng minh.) Nếu đúng như vậy thì có thể xây dựng các nghiệm khác.

Chúng ta hãy xem xét chi tiết hơn các phép biến đổi mà chúng ta đã thực hiện đối với phương trình. Chúng ta hãy ký hiệu $\sqrt[3]{1-x} = u$ và $\sqrt[3]{1+x} = v$ cho ngắn gọn.

Từ phương trình.
$$u + v = p$$
chúng tôi đã chuyển sang phương trình
$$u^3 + v^3 + 3uv(u + v) = p^3$$
(2)
sử dụng một phép biến đổi tương đương (nâng đối tượng thành khối). Bước tiếp theo là thay thế $p$ cùng với $u + v$ và đi đến phương trình
$$u^3 + v^3 + 3uvp = p^3,$$
(3)
mà chúng tôi sẽ viết như thế này:
$$u^3 + v^3 - p^3 + 3uvp = 0,$$
$$(u + v)^3 - p^3 - 3uv(u + v - p) = 0.$$
Hãy áp dụng công thức tính hiệu của hai lập phương rồi đặt $(u + v - p)$ ra khỏi ngoặc:
$$(u + v - p)(u^2 + v^2 + p^2 + up + pv - uv) = 0.$$ (3')
Vì vậy, chúng ta đã viết được phương trình (3) dưới dạng (3'), từ đó dễ dàng tìm ra lý do tại sao nó không tương đương với (2). Rõ ràng là vế trái của (3') bằng 0 khi có ít nhất một dấu ngoặc đơn bằng 0:
1) $u + v - p = 0,$
2) $u^2 + v^2 + p^2 + up + pv - uv = 0.$

⟦folio 30⟧

Sự bình đẳng đầu tiên là phương trình ban đầu của chúng tôi. Điều này có nghĩa là toàn bộ cấu trúc lời giải được kết nối với cấu trúc thứ hai và chúng ta cần tìm hiểu khi nào nó được thực thi. Nhân nó với 2, bạn có thể viết nó như thế này:

$$(u+p)^2+(v+p)^2+(u-v)^2=0.$$

Đẳng thức này chỉ đúng với $u=v=-p$.

Áp dụng vào phương trình của chúng ta:

$$\sqrt[3]{1-x}=\sqrt[3]{1+x}=-p.$$

Điều này có nghĩa là $x=0$ cho $p=-1$ là gốc duy nhất được xây dựng. Tất cả các nghiệm khác cho bởi công thức (4) của $0<p\leqslant2$ đều thỏa mãn phương trình (1).

Chúng ta hãy viết lại các đẳng thức mà chúng ta đã thiết lập thành công (đối với đối xứng, chúng ta thay thế $p$ bằng $-w$):

$$u^3+v^3+w^3-3uvw=(u+v+w)(u^2+v^2+w^2-uw-vw-uv),$$

$$2(u^2+v^2+w^2-uw-vw-uv)=$$

$$=(u-v)^2+(v-w)^2+(w-u)^2.$$

Chúng thường hữu ích trong việc chứng minh các bất đẳng thức và trong các vấn đề khác.

**M73**

Trên một tờ vé số, bạn cần đánh dấu 8 ô trên 64. Xác suất mà sau khi rút thăm mà 8 ô trên 64 ô cũng được chọn (và chúng tôi coi tất cả các khả năng như vậy đều có xác suất như nhau), thì hóa ra chính xác là 4 ô được đoán? 5 ô?...tất cả 8 ô?

Như đã biết, 8 trong số 64 ô có thể được chọn theo $C_{64}^8=\frac{64!}{8!56!}$ cách ($n!$ là tích của tất cả các số nguyên từ 1 đến $n$) $^*$). Tất cả những phương pháp này đều đáng tin cậy như nhau. Do đó, xác suất để nhận được một cách cụ thể bất kỳ là $1/C_{64}^8$. Bây giờ chúng ta cần tính toán thời gian mà trường hợp đó hóa ra chính xác là $k$ ô ($0\leqslant k\leqslant8$). Số trường hợp như vậy bằng số cách

$^*$) Ví dụ, hãy xem bài viết của N. Ya. Vilenkin “Tổ hợp” trong «Kvant» Số 1, 1971.

Hình 6. Hồng cầu là người chiến thắng; 8 ô chúng tôi đã chọn được đánh dấu bằng dấu chéo. Trong hình này $k=2$, $8-k=6$.

các phương pháp trong đó $k$ ô được chọn từ 8 ô được đánh dấu và $8-k$ từ 56 ô không được đánh dấu. Do đó nó bằng $C_{8}^k\cdot C_{56}^{8-k}$. Để tìm thời gian mong muốn $f_k$ - xác suất đoán chính xác $k$ ô, bạn cần nhân xác suất của một phương pháp với số này. chúng tôi nhận được

$$f_k=\frac{C_{8}^k\cdot C_{56}^{8-k}}{C_{8}^4}.$$

Như vậy, xác suất đoán được 0,1, ..., 8 ô tương ứng là các ô tương ứng.

$$f_0=\frac{C_{8}^0\cdot C_{56}^8}{C_{8}^4},$$

$$f_1=\frac{C_{8}^1\cdot C_{56}^7}{C_{8}^4}, \dots, f_8=\frac{C_{8}^8\cdot C_{56}^0}{C_{8}^4}.$$

Tổng của chín số này tất nhiên bằng một.

Chính thức là bài toán lời giải, nhưng từ quan điểm thực tế thì điều này vẫn chưa đúng. Tôi muốn tưởng tượng cơ hội đoán được một số ô cụ thể sẽ lớn đến mức nào nếu chúng ta mua và điền vào mười tờ vé số. Để làm điều này, bạn cần biểu diễn gần đúng những số này dưới dạng phân số thập phân. Điều này có thể được thực hiện bằng cách sử dụng thước trượt; ví dụ, sử dụng trực tiếp công thức (1). Đây là những gì A. Zlomnik từ thành phố Zhukovsky đã làm. Chúng tôi sẽ mô tả một phương pháp khác, có vẻ như đối với chúng tôi, một phương pháp đơn giản hơn.

⟦folio 31⟧

Hình 7. Các số $f_k$ được hiển thị ở đây – xác suất đoán $k$ ô ($k = 0, 1, 2, \dots, 8$). Tại $k \geq 4$ giá trị $f_k$ rất gần bằng 0.

Trước tiên, hãy tính tỷ lệ của số thứ $(k+1)$ của các số này với số thứ $k$:

$$\frac{f_{k+1}}{f_k} = \frac{C_8^{k+1} \cdot C_{56}^{8-k-1}}{C_{64}^8} : \frac{C_8^k \cdot C_{56}^{8-k}}{C_{64}^8} = \frac{(8-k)^2}{(k+1)(48+k+1)}$$

một phần,

$$\frac{f_1}{f_0} = \frac{64}{49} \approx 1.31; \quad \frac{f_2}{f_1} = \frac{49}{100};$$

$$\frac{f_3}{f_2} = \frac{12}{51} \approx 0.235; \quad \frac{f_4}{f_3} = \frac{25}{208} \approx 0.12;$$

$$\frac{f_5}{f_4} \approx 0.06; \dots$$

Bằng cách tính tỷ lệ $f_2, f_3, f_4$ đến $f_0$ với hai chữ số thập phân:

$$\frac{f_2}{f_0} = 0.64; \quad \frac{f_3}{f_0} \approx 0.15; \quad \frac{f_4}{f_0} = 0.02.$$

Rõ ràng là $f_5/f_0 < 0.02 \cdot 0.12$ và, đối với mức đã chọn, chính xác $f_5, f_6, f_7, f_8$ bằng 0. Chúng ta có thể lập một phương trình

$$f_0(1+1,31+0,64+0,15+0,02)=1,$$

từ đâu $f_0 \approx 0.32$. Hiện đang tìm kiếm $f_1, f_2, f_3, f_4$:

$$f_1 \approx f_0 \cdot 1.31 \approx 0.42; \quad f_2 \approx f_0 \cdot 0.64 \approx 0.20;$$

$$f_3 \approx f_2 \cdot 0.24 \approx 0.047; \quad f_4 \approx f_3 \cdot 0.12 \approx 0.0056.$$

Vì vậy, nếu bạn điền vào mười vé, thì những vé trung bình rất có thể sẽ là những vé đoán được 0, 1, 2 và có lẽ là 3 ô; Xác suất đoán được 4 ô trở lên là rất thấp. Bằng cách nhân $f_4$ với $\frac{f_5}{f_4} \approx 0.06$, v.v., có thể thu được giá trị gần đúng của $f_5, f_6, f_7, f_8$. Một phần, $f_8 \approx 2 \cdot 10^{-10}$. Điều này có nghĩa là để có cơ hội thực sự đoán được hết 8 ô, bạn cần phải điền vài chục tỷ vé.

Sử dụng phương pháp tính gần đúng mà chúng tôi đã áp dụng, có thể chỉ ra rằng nếu số ô $N$ trên tờ vé số lớn hơn nhiều so với số ô $m$ cần loại bỏ và $m$ đủ lớn thì xác suất đoán được $k$ ô của xấp xỉ là bằng

$$f_k = \frac{C_m^k C_{N-m}^m}{C_N^m} \approx \frac{\mu^k \cdot e^{-\mu}}{k!},$$

trong đó $\mu = \frac{m^2}{N-2m}$ và $e \approx 2.718\dots$ là một số không đổi ($\pi$), vì vậy chúng ta cần sử dụng thực tế là $1+x+\frac{x^2}{2}+\frac{x^3}{3!}+\dots = e^x$ cho bất kỳ $x$ nào).

A. L. Toom

Trong số này, chúng tôi xuất bản lời giải bài toán F79—F82

F79

Mực nước vào thuyền trùng với mực nước trong hồ. Mực nước sẽ cao hơn ở đâu nếu bạn ném một khúc gỗ xuống thuyền?

Khi hạ khúc gỗ xuống thuyền, thuyền sẽ lao xuống hồ, bạn sẽ nhận thêm một lượng nước $\Delta V = \frac{m}{\rho}$ ($m$ là khối lượng khúc gỗ, $\rho$ là khối lượng riêng của nước). Mặt khác, vì khúc gỗ nổi trong nước nên mực nước trong thuyền sẽ thay đổi giống như nó sẽ thay đổi nếu nước có khối lượng bằng khối lượng khúc gỗ và thể tích bằng thể tích phần ngâm trong khúc gỗ, tức là $V = \frac{m}{\rho}$, được thêm vào thuyền. (Chúng ta có thể nhẩm lấy khúc gỗ ra và đổ đầy nước vào nước thu được, nhưng mực nước trong thuyền sẽ không thay đổi.) Cùng một lượng nước cũng chảy ra khỏi thuyền khi ném khúc gỗ vào đó. Vì vậy, mực nước trong thuyền sẽ bằng mực nước trong thuyền.

⟦folio 32⟧

mực nước trong hồ thấp nếu độ dày của thành thuyền không đáng kể, và sẽ cao hơn một chút so với mực nước trong hồ nếu thành thuyền dày.

lời giải chính xác được gửi bởi R. Khasnumdinov (làng Oktyabrsky BASSR), A. Zisman (Pskov), I. Vidorovich (Simferopol), O. Masliok (Novomirgorod, vùng Kirovograd), V. Rudko (Kyiv), A. Smarchenko (làng Petropavlovsk, vùng Dnepropetrovsk), A. Demidov (Moscow), L. Bratsensky (Frunze), F. Tukhvatullin (Tashkent), N. Shishkin (Nalchik), N. Filippov (Leningrad), N. Sidorov (Moscow).

Tôi. Sh. Slobodetsky

F80

Một con xúc xắc được ném dọc theo một mặt phẳng nghiêng một góc β so với hướng đi xuống (Hình 8). Tìm tốc độ chuyển động ổn định của hình lập phương nếu hệ số ma sát của nó o mặt phẳng k = tanα, trong đó α là góc nghiêng của mặt phẳng k so với đường chân trời.

Khối lập phương chịu tác dụng của trọng lực P = mg, phản lực pháp tuyến N = mg cosα và lực ma sát F_tp (Hình 8).

Chúng ta hãy xem xét các thành phần của lực dọc theo mặt phẳng. Xuống bên cạnh

Hình 8.

độ dốc xuống nhanh nhất (trục y) chịu ảnh hưởng của thành phần trọng lực F = mg sinα; theo hướng ngược với tốc độ, lực ma sát F_tp = kN = kmg cosα tác dụng. Theo điều kiện, k = tanα nên F_tp = tanα kmg cosα = mg sinα = F.

Do đó, bài toán có nghĩa là xem xét chuyển động của khối lập phương dưới tác dụng của hai lực có độ lớn bằng nhau. Một trong số chúng luôn hướng theo tốc độ của khối lập phương, cái còn lại dọc theo trục y.

Hình 9.

Giả sử tại một thời điểm nào đó tốc độ v tạo một góc φ với trục y (Hình 9). Gia tốc tiếp tuyến (hướng tiếp tuyến với quỹ đạo) a của hình lập phương được xác định bởi lực F_tp = F và hình chiếu F cosφ của lực F về cùng một phương:

$$a = \frac{F + F \cos \varphi}{m}.$$

Gia tốc a_y (dọc theo trục y) được xác định bởi lực F và hình chiếu F_tp cosφ của lực F_tp lên trục y. Dễ dàng thấy rằng độ lớn của gia tốc này bằng gia tốc tiếp tuyến:

$$a_y = \frac{F + F_tp \cos \varphi}{m} = \frac{F + F \cos \varphi}{m} = a.$$

Do đó, tốc độ thay đổi độ lớn của vận tốc mặt phẳng a = \frac{\Delta v}{\Delta t} và tốc độ thay đổi độ lớn của thành phần lực dọc theo trục y a_y = \frac{\Delta v_y}{\Delta t} là như nhau. Nhưng nếu tốc độ thay đổi theo thời gian của hai đại lượng là như nhau thì bản thân các đại lượng này chỉ khác nhau một hằng số không phụ thuộc vào thời gian. Chúng ta hãy biểu thị hằng số này bằng V. Khi đó tại bất kỳ thời điểm nào v = v_y + V.

Bạn có thể tìm hằng số V bằng cách thay thế các giá trị v và v_y vào công thức này

⟦folio 33⟧

tại thời điểm khối lập phương chuyển động ban đầu ($v=v_0$, $v_y=v_0 \cos \beta$):

$$v_0 = v_0 \cos \beta + V.$$

Từ đây

$$V = v_0 (1 - \cos \beta).$$

Kể từ đây,

$$v = v_y + v_0 (1 - \cos \beta),$$

Ở đâu

$$v_y = v \cos \varphi.$$

Sau một thời gian đủ dài, thành phần “ngang” của vận tốc của khối lập phương sẽ giảm về 0. Khối lập phương sẽ di chuyển xuống dọc theo trục $y$. Ở trạng thái giới hạn này $\varphi = \pi$, tức là $\cos \varphi = -1$; $v_y = -v$.

Để có tốc độ ổn định $v$ chúng ta có thể viết phương trình

$$v = -v + v_0 (1 - \cos \beta).$$

Từ đây

$$v = v_0 \frac{1 - \cos \beta}{2} = v_0 \sin^2 \frac{\beta}{2}.$$

Biết rằng $a=a_y$, bài toán cũng có thể giải được bằng đồ họa. Thật vậy, nếu sự thay đổi $\Delta v$ của tổng tốc độ bằng với sự thay đổi $\Delta v_y$ thì dễ dàng tìm được các giá trị

$$v = v_0 \frac{1 - \cos \beta}{2} = v_0 \sin^2 \frac{\beta}{2}.$$

Biết rằng $a=a_y$, bài toán cũng có thể giải được bằng đồ họa. Thật vậy, nếu sự thay đổi $\Delta v$ của tổng tốc độ bằng với sự thay đổi $\Delta v_y$ thì dễ dàng tìm được các giá trị

$$v = v_0 \frac{1 - \cos \beta}{2} = v_0 \sin^2 \frac{\beta}{2}.$$

Để sau thời gian $\Delta t$ thành phần $v_y$ của tốc độ của khối thay đổi thành $\Delta v_y$ và tổng tốc độ - thành $\Delta v = \Delta v_y$. Do đó, sau thời gian $\Delta t$ vectơ $v_0$ sẽ $\Delta v$ ngắn hơn và giá trị hình chiếu của nó lên trục $y$ thay đổi một lượng như nhau.

Qua điểm $B$ nằm dưới điểm $A$ (điểm cuối của vectơ $v_0$) đến đoạn $\Delta v_y = \Delta v$, chúng ta vẽ một đường ngang $BC$. Với bán kính $AB$ bằng $\Delta v_y = \Delta v$, hãy vẽ các cung $BD$ từ điểm $A$ cũng như từ tâm. Điểm $D$ sẽ đánh dấu độ dài của vectơ mới $v = v_0 - \Delta v$. Với bán kính $OD$ bằng $v = v_0 - \Delta v$, hãy vẽ một cung $DC$ từ điểm $O$ cũng như từ tâm. Điểm $C$ giao điểm của các cung với đường $BC$ là điểm cuối của vectơ mong muốn $OC$, bằng $v$.

Việc xây dựng này có thể được thực hiện trong bất kỳ khoảng thời gian nào $\Delta t$. Nó cho thấy vectơ vận tốc $v$ của khối lập phương có gia tốc và tiến đến trục $y$ (Hình 11). Từ hình vẽ cho thấy rõ rằng trong trường hợp giới hạn

$$v + v_0 \cos \beta = v_0 - v.$$

Từ đây

$$v = \frac{v_0 (1 - \cos \beta)}{2} = v_0 \sin^2 \frac{\beta}{2}.$$

lời giải chính xác được gửi bởi P. Belykov (Moscow).

B. B. Bukhovtsev

⟦folio 34⟧

F81

Hiện nay, các cuộn dây điện từ có cuộn dây siêu dẫn được sử dụng. Những cuộn dây điện từ như vậy có thể tạo ra từ trường trong thời gian dài mà không tiêu tốn năng lượng. Tuy nhiên, nếu bất kỳ phần nào của cuộn dây mất đi đặc tính siêu dẫn thì sẽ xảy ra tai nạn. Ở khu vực này, nhiều colic Tella sẽ được giải phóng và một vụ nổ sẽ xảy ra.

Hãy nghĩ ra thiết bị đơn giản nhất để ngăn ngừa những tai nạn như vậy.

Sơ đồ có rơle không phù hợp - thời gian so sánh của chúng quá dài. Một vụ nổ sẽ xảy ra trước chuyến đi tiếp sức. Do đó, lối thoát duy nhất là làm đoản mạch nút điện từ tới điện trở. Đây là cách họ thường làm điều đó. Dây điện từ được gia cố bằng đồng. Nếu mất đi tính siêu dẫn, phần ứng sẽ đóng vai trò như một bộ đệm để dòng điện xuất hiện và sự giải phóng cơ thể sẽ được phân bổ khắp mạch điện.

lời giải chính xác được gửi bởi S. Chernikov (Semipalatinsk). N. Efimov (Voronezh), V. Skvortsov (Leningrad).

F82

Tìm điều kiện để không có dòng điện chạy qua điện trở $r$ nối tại các điểm $A$ và $B$ của mạch điện như hình 12.

Vì vậy, nó sẽ không vượt qua ngưỡng kháng cự $r$ nếu hiệu điện thế giữa các điểm $A$ và $B$ bằng không. Chúng ta coi thế năng của điểm $F$ bằng 0. thì thế năng của điểm $C$ bằng $E_1$, và thế năng của điểm $D$ bằng $E_2$. Dòng điện $I = \frac{E_1}{r_1 + r_3}$ chạy qua điện trở $r_1$,

Hình 12.

và do đó độ sụt điện áp trên điện trở $r_1$ bằng $U_1 = Ir_1 = E_1 \frac{r_1}{r_1 + r_3}$, và điện thế của điểm $A$ bằng

$$\varphi_A = E_1 - E_1 \frac{r_1}{r_1 + r_3} = E_1 \frac{r_3}{r_1 + r_3}.$$

Tương tự, ta tìm thế của điểm $B$:

$$\varphi_B = E_2 \frac{r_4}{r_2 + r_4}.$$

Từ điều kiện $\varphi_A = \varphi_B$ ta thu được

$$E_1 \frac{r_3}{r_3 + r_1} = E_2 \frac{r_4}{r_2 + r_4}.$$

Đây là điều kiện chung cho việc không có điểm xuyên qua lực cản $r$. Nó cũng bao gồm trường hợp rất đối xứng $r_1 = r_2$, $r_3 = r_1$ và $E_1 = E_2$.

Tôi. Sh. Slobodetsky
