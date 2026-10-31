---
id: 1988-6-efremovich-chto-takoe-nepreryivnost-fd822ffc
issue: kvant_1988_6
year: 1988
number: "6"
title: tính liên tục là gì
authors:
  - Ефремович В. А.
rubric: raznoe
page_first: 24
page_last: 26
page_labels: 22-24
tag: HK7P
lang: vi
source: kvant_digital
extraction: vision
content_sha256: 2d9768085bbe99da9eec1ab421a5c76f5647d5e188ebf51a4a7b6cc6896a097a
prompt_sha256: draft-1
translated_from: content/ru/1988/06/articles/04_efremovich-chto-takoe-nepreryivnost-fd822ffc.md
source_content_sha256: 23bcd77c67caa72884784d13e5cee023ed60e65f34122a0c7a245cb38e7cdece
translation_model: draft
translation_run: vi-draft-2026-10-31
translation_quality: draft
---

⟦folio 22⟧

TIẾP TỤC LÀ GÌ

Tiến sĩ Khoa học Vật lý và Toán học
V. A. EFREMOVICH

Đây là một khái niệm cơ bản trong toán học. Nó thuộc về cái được gọi là hình học định tính, tức là một phần của hình học hoàn toàn không bị giao cắt bởi các khái niệm có tính chất đo lường (khoảng cách, độ dài, thể tích, ...). Bất chấp điều này (hoặc có lẽ vì điều này?), toàn bộ tòa nhà phân tích toán học và gần như toàn bộ hình học đều đứng trên đó.

Những khái niệm này đã được các nhà toán học thời cổ đại sở hữu (ở mức độ trực quan), nhưng định nghĩa chính xác chỉ được đưa ra vào nửa đầu thế kỷ 19, được thay thế bởi nhà toán học người Pháp O. Cauchy (1787-1857). Để làm rõ định nghĩa này, chúng ta cần

Khái niệm chung về hàm

Khái niệm về chức năng đã trải qua một số khái quát hóa quan trọng. Lúc đầu, chỉ các hàm số của một đối số số mới được xem xét, ví dụ: $x^3$, Тg $x$, $e^x$, và hơn nữa, được chỉ định bởi một hoặc một biểu thức phân tích khác. Sau này hóa ra cái sau không tồn tại. Điều quan trọng duy nhất là mỗi giá trị của đối số $x$ tương ứng với giá trị số riêng của hàm. Hàm liên tục được biểu thị bằng một đường cong liên tục thu được bằng cách di chuyển bút chì mà không nhấc nó lên khỏi giấy (trên hình 1 - hàm liên tục, trên hình 2 - không liên tục).

Tiếp theo, chúng ta có thể xem xét các hàm số của đối số chính xác, ví dụ: nhiệt độ hoặc áp suất khí quyển tại các điểm khác nhau trong không gian. Một ví dụ khác. Mảnh đất bằng phẳng phủ đầy tuyết; thì chiều cao $h$ của lớp tuyết phủ tại mỗi điểm $p$ là giá trị của một số hàm: $h=f(p)$. Nếu tọa độ $x$, $y$ được đặt trên trang web, mỗi điểm sẽ nhận được “tên” riêng: $p=(x, y)$ và hàm $f$ được đề cập có thể được viết như sau: $f(p)=f(x, y)$. Đó là hàm một biến điểm $p$, hoặc là hàm hai biến số $x$, $y$. Đồ thị của hàm này là bề mặt tuyết.

Cuối cùng, người ta có thể xem xét (trường hợp tổng quát nhất) hàm chính xác của đối số chính xác, tức là ánh xạ $f: X \rightarrow Y$ của hàm số $X$ vào hàm $Y$. Đây là sự biểu diễn của một hàm không gian trên một bản vẽ phẳng, ví dụ, hình chiếu trực giao của một vật thể lên một mặt phẳng. Bức tranh hoặc bức ảnh của bất kỳ nghệ sĩ nào cũng có thể được xem dưới dạng một hàm (tức là một bản đồ), trong đó mỗi điểm $x$ được mô tả tương ứng với điểm $x'$ của hình ảnh. Trong trường hợp này, $x'=f(x)$ được gọi là ảnh của điểm $x$. Các nghệ sĩ chủ yếu quan tâm đến chức năng hiển thị như vậy. Đặc biệt có giá trị là sự đóng góp của Đại Leonardo da Vinci (1452-1519), một trong những nghệ sĩ đầu tiên sáng lập ra lý thuyết toán học về phối cảnh.

Tính liên tục

Khái niệm chung nhất về các hàm ánh xạ giúp có thể hình dung đầy đủ và đồng thời mang tính toán học chặt chẽ.

Hình 1.
Hình 2.

⟦folio 23⟧

giải thích khái niệm liên tục. Để làm điều này, trước tiên hãy xem xét một ví dụ trong đó xảy ra sự gián đoạn, tức là vi phạm tính liên tục.

Giả sử $X$ là một sợi dây cao su để đóng gói thuốc, một mô hình thô của một hình tròn. Giả sử rằng trong quá trình biến dạng, nó đột ngột bị gãy ở một điểm nào đó $a$. Nó có nghĩa là gì? Một số phần của nó $B$, liền kề bằng $a$, tức là nằm cách $a$ bằng 0 (chúng ta viết $B\delta a$), sau dấu ngắt (chúng ta sẽ ký hiệu là $B'$) hóa ra không gần với $a'$ (vị trí mới của điểm $a$ - xem hình 3). Vì vậy, ngắt tại điểm $a$ là sự kiện trong đó một phần của $B$, gần với $a$ ($B\delta a$), trở nên không gần với vị trí mới $a'$ của điểm $a$: $B\delta a$, mà là $B'\delta a'$. Theler hiểu định nghĩa sau:

Ánh xạ $f$: $X \rightarrow Y$ được cho là liên tục tại điểm $a \in X$ nếu mọi phần $B \subset X$ gần với $a$ sau khi ánh xạ đi đến vị trí $B'$ gần với $a' = f(a)$, tức là.

$$B\delta a \Rightarrow B'\delta a'.$$

Ký hiệu $B\delta a$ có ý nghĩa chính xác: đối với mọi giá trị dương nhỏ tùy ý $\varepsilon$ trong hình $B$ có một điểm $x$ sao cho $xa < \varepsilon$ (ở đây $xa$ là khoảng cách từ $x$ đến $a$; từ nay trở đi, bằng $pq$ chúng ta biểu thị khoảng cách từ $p$ đến $q$). Tương tự, $A\delta B$ có nghĩa là trong các hình $A$, $B$ có các điểm $x \in A$, $y \in B$ sao cho $xy < \varepsilon$ cho mọi điểm dương $\varepsilon$. Lưu ý rằng hai đường thẳng e của một điểm không thể gần nhau theo nghĩa này: nếu $a \neq b$, thì $a\beta b$ (sau đây gọi là $ab = 10^{-100}$).*

Định nghĩa này tương đương với định nghĩa Cauchy cổ điển:

Ánh xạ $f$: $X \rightarrow Y$ liên tục tại điểm $a \in X$ nếu với mọi $\varepsilon > 0$ có một $a > 0$ sao cho $xa < \alpha$ ngụ ý $x'a' < \varepsilon$ (ở đây $a' = f(a)$, $x' = f(x))$.

Sự tương đương của hai định nghĩa được chứng minh ở phần cuối của ghi chú của chúng tôi.

Nếu một hàm số liên tục tại mọi điểm $x \in X$ thì nói rằng nó liên tục trên toàn bộ tập hợp $X$.

Định nghĩa này, cùng với định nghĩa của Cauchy, không dễ hiểu rõ ràng. Bản thân Cauchy đã thay đổi đã nhiều lần phạm sai lầm, vô tình thay thế yêu cầu về tính liên tục bằng một yêu cầu mạnh mẽ hơn - cái mà ngày nay gọi là tính liên tục đều. Lò xo này là một phần quan trọng của trường hợp liên tục, và chúng ta sẽ tập trung vào nó.

Tính liên tục thống nhất

Ánh xạ $f$: $X \rightarrow Y$ được gọi là liên tục đều trên $X$ nếu có hai phần gần nhau $A$, $B \subset X$ đi đến $f$ để đóng các phần $A'$, $B' \subset Y$, tức là $A\delta B \Rightarrow A'\delta B'$.

Bài tập. Hiển thị gì

$$tg: \left( -\frac{\pi}{2}; \frac{\pi}{2} \right) \rightarrow R$$

không liên tục đều trên $(-\pi/2; \pi/2)$. (Ở đây khó tìm thấy $A$, $B$ cần thiết sao cho $A\delta B$, nhưng $A'\delta B'$: đây là hai chuỗi điểm, ví dụ: ảnh nghịch đảo của tập hợp $A' = \{1, 3, ...\}$, $B' = \{2, 4, ...\}$, $A'\delta B'$.)

Có một sự khác biệt cơ bản giữa các khái niệm về tính liên tục và tính liên tục thống nhất. Đầu tiên là dựa trên khoảng cách giữa một điểm và một tập hợp, thứ hai là khoảng cách giữa hai tập hợp đề cập đến cấu trúc liên kết và khoảng cách giữa một tập hợp đề cập đến sự gần gũi về mặt hình học, một khoa học “tinh tế” hơn cấu trúc liên kết. Để hiểu sự khác biệt này, chúng ta hãy chỉ đưa ra một ví dụ. Từ quan điểm tôpô, một nhánh của hyperbol và đường tiệm cận của nó không thể được phân biệt với một cặp đường thẳng song song (bất kỳ điểm nào của hyperbol đều không gần với đường tiệm cận của nó).

*) Định nghĩa về độ gần được đưa ra ở đây được tác giả bài viết này đề xuất lần đầu tiên vào năm 1936. Khái niệm độ gần có thể được định nghĩa theo phương pháp tiên đề, không cần sử dụng khoảng cách và toàn bộ cấu trúc liên kết có thể được xây dựng trên cơ sở của nó. (Hơn nữa, biên tập.)

⟦folio 24⟧

Otte!), trong khi hai cặp đối tượng này không giống nhau về hình học tiệm cận (tiệm cận gần với hyperbola!).

Chứng minh sự tương đương của các định nghĩa về tính liên tục

Giả sử ánh xạ $f: X \rightarrow Y$ liên tục tại điểm $a$ theo Cauchy, trong đó $X, Y$ là các số xác định khoảng cách giữa các điểm, có tính chất chung. Sau đó, với mỗi $\varepsilon > 0$ có một số dương $\alpha = \alpha(\varepsilon)$, tùy thuộc vào $\varepsilon$, sao cho $ax < \alpha$ ngụ ý $a'x' < \varepsilon$. Đặt phần $B \subset X$ gần với $a$; điều này có nghĩa là với mọi $\alpha > 0$ trong $B$ đều có một điểm $x$ sao cho $ax < \alpha$. Nếu $\alpha = \alpha(\varepsilon)$ thì $a'x' < \varepsilon$ và vì $\varepsilon$ nhỏ tùy ý nên $B' = f(B)$ gần bằng $a' = f(a)$ ($B\delta a \Rightarrow b'\delta a'$).

Ngược lại, giả sử rằng $f$ thỏa mãn định nghĩa đầu tiên về tính liên tục.

Số và hàm
(Xem phần đầu ở trang 12)

Nó suy ra từ đẳng thức (9) và $PQ' : Q$. Nhưng vì $(P, Q) = 1$, nên $Q' : Q$. Vì vậy, bậc $Q$ không được cao hơn bậc $Q'$. Điều thứ hai chỉ có thể xảy ra nếu $Q$ là một hằng số. Từ (9) cũng suy ra rằng $P$ là một hằng số. Nhưng $r_0 = P/Q$ là một hằng số. Khi xây dựng $r_0$, đẳng thức (8) có dạng $nr_0 = 0$, $r_0 \neq 0$. Và vì $n \geq 1$, đẳng thức này mâu thuẫn. Định lý đã được chứng minh.

Bài tập 11. a) Chứng minh tính siêu việt của hàm số
$y = \sin x; y = \sqrt{e^x} + 1$.

6) Cho ví dụ về hàm số siêu việt $f$ và $g$ sao cho $f + g, fg, f(g(x))$ không siêu việt.

b) Chứng minh rằng nếu $f$ và $g$ là hàm siêu việt thì ít nhất một trong các hàm $f + g$ và $fg$ cũng siêu việt.

Ở cuối § 2, chúng tôi đã cố gắng tìm ra mối liên hệ nào đó giữa tính vô tỷ của một hàm và tính vô tỷ của các giá trị của nó - và đã thất bại hoàn toàn. Sau đó, có lẽ sẽ không còn ai tìm kiếm mối liên hệ giữa tính siêu việt của một hàm số và tính siêu việt của các giá trị của nó nữa. Cuối cùng, để loại bỏ mọi nghi ngờ, chỉ cần xem xét hàm có đồ thị được hiển thị trong hình 5. Tuy nhiên, hàm siêu việt này không chỉ lấy các giá trị đại số mà thậm chí cả các giá trị hữu tỉ cho tất cả các giá trị hữu tỉ $x$ (tự mình chứng minh các thuộc tính được liệt kê của hàm này).
