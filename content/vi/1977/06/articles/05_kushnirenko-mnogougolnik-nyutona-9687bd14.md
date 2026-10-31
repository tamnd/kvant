---
id: 1977-6-kushnirenko-mnogougolnik-nyutona-9687bd14
issue: kvant_1977_6
year: 1977
number: "6"
title: Đa giác Newton
authors:
  - Кушниренко А. Г.
rubric: osnovnye-stati
rubric_sub: Основные статьи
page_first: 21
page_last: 26
page_labels: 19-24
tag: AK6D
lang: vi
source: kvant_digital
extraction: vision
content_sha256: aaf4b3203dc3296490af867502d95a23eb6ffdb834430ef1cda5df1649d14b52
prompt_sha256: draft-1
translated_from: content/ru/1977/06/articles/05_kushnirenko-mnogougolnik-nyutona-9687bd14.md
source_content_sha256: 2dbf0dfe14bc2841a4c740adc44fc137f10fe3a8a88c78b8ab53302dc89094bd
translation_model: draft
translation_run: vi-draft-2026-10-31
translation_quality: draft
---

⟦folio 19⟧

"Vai trò chức năng của nghiên cứu của Newton trong sự phát triển của phân tích vô hạn đã được biết đến. Hầu hết các ý tưởng của ông đã được xem xét trong các tác phẩm của các tác giả sau này, thường không lưu giữ tên của Newton hoặc phương pháp ký hiệu của ông. Nhưng trong toán học hiện đại, có nhiều phương pháp và kết quả mang tính chất cụ thể hơn mang tên Newton. Ý nghĩa của chúng chỉ được bộc lộ trong một thời đại rất muộn, khi quá trình toán học tổng quát cho phép đánh giá tầm quan trọng của kết quả này hay kết quả khác của Newton, một phần được viết dưới dạng một thay thế nhỏ. Trong số đó KẾT QUẢ LÀ “đa giác” của Newton, hay như người ta thường gọi, “hình bình hành…” của Newton.

N. G. Chebogarev

Một đặc tính quan trọng của đa thức một biến là bậc của nó. Biết mức độ, bạn có thể nói rất nhiều về một đa thức mà không cần biết các hệ số của nó. Ví dụ, một đa thức bậc lẻ luôn có nghiệm thực, số nghiệm thực của đa thức không vượt quá bậc của nó, v.v.

Khái quát hóa đơn giản và quan trọng nhất của khái niệm bậc của đa thức $P(x, y)$ trong hai biến $x, y$ sẽ là cái gọi là bậc đầy đủ của đa thức trong các biến $x, y$. Tuy nhiên, một cách khái quát hóa tinh tế hơn về khái niệm bậc của đa thức hai biến không phải là một con số, mà là một thứ phức tạp hơn - cụ thể là một đa giác trên mặt phẳng.

Trong bài viết này, chúng ta sẽ liên kết mỗi đa thức hai biến với một đa giác trên mặt phẳng. Thiết kế này chủ yếu chịu ảnh hưởng của nhà toán học và vật lý người Anh Isaac Newton; Kể từ thế kỷ 18, đa giác này đã được gọi là “đa giác Newton”. Đa giác Newton, một đa thức hai biến, thu hẹp khoảng cách giữa đại số và hình học. Giao thông ở nơi này đã không hề giảm bớt trong 300 năm qua và trong những năm gần đây nó trở nên đặc biệt căng thẳng. Rõ ràng một địa điểm có thể di chuyển theo hai hướng khác nhau - và đa giác của Newton hữu ích theo hai cách. Xem một đa giác trên mặt phẳng là đa giác Newton của một đa thức nào đó, chúng ta có thể sử dụng các tính chất đại số của đa thức cho đa giác hình học lời giải bài toán. Ngược lại, các tính chất hình học của đa giác Newton giúp giải được đa thức bài toán. Hai ví dụ về việc sử dụng đa thức Newton trong nghiên cứu đa thức được thảo luận chi tiết trong § 2 và § 3. Các ví dụ về việc sử dụng đa thức trong nghiên cứu đa giác thành phố phức tạp hơn và chúng ta sẽ không đi sâu vào chúng.

⟦folio 20⟧

§ 1. Đa giác Newton là gì
Sơ đồ Newton đa thức hai biến

Hãy nhớ lại rằng số hạng một năm trong các biến độc lập $x$ và $y$ là một hàm có dạng $x^m y^n$, trong đó $m$ và $n$ là các số nguyên không âm và đa thức trong $x$ và $y$ với hệ số thực được gọi là hàm $P(x, y)$ cho bởi công thức
$$P(x, y) = a_1 O_1 + a_2 O_2 + \dots + a_k O_k,$$
(1)
trong đó $a_1, a_2, \dots, a_k$ là các số thực và $O_1, O_2, \dots, O_k$ là các số riêng biệt theo cặp trong cùng một năm *). Nếu trong công thức (1) hệ số $a_i$ khác 0 thì $O_i$ một năm được cho là được đưa vào đa thức $P(x, y)$. Ví dụ: đa thức $2 + 3y - \sqrt{2}x^3y^2$ bao gồm các số hàng năm 1, $y$ và $x^3y^2$, nhưng đa thức $P(x, y) \equiv 0$ không bao gồm bất kỳ số năm nào. Thật thuận tiện khi biểu diễn số hàng năm có trong đa thức $P(x, y)$ bằng các điểm trên mặt phẳng tọa độ: chúng ta đánh dấu điểm $M(m_0; n_0)$ trên mặt phẳng này nếu số năm $x^{m_0}y^{n_0}$ được bao gồm trong đa thức $P(x, y)$. Sau đó, với mỗi đa thức khác 0 $P(x, y)$, chúng ta liên kết một tập hữu hạn trên mặt phẳng $Omn$ - chúng ta sẽ biểu thị nó $D(P)$ - mô tả trực quan các tập hợp một năm có trong $P(x, y)$. Chúng ta sẽ gọi một điểm trên mặt phẳng mà cả hai tọa độ đều là số nguyên là điểm nguyên. Đối với bất kỳ đa thức $P$ nào, tập hợp $D(P)$ chỉ bao gồm các điểm nguyên nên sẽ rất thuận tiện khi vẽ nó trên giấy ca rô. Ví dụ, đa thức
$$P(x, y) = xy - y^3 + 3x^2y^2 + 0,5x^4 - 2x^3y^4.$$
(2)
được hiển thị trong Hình 1. Cần nhấn mạnh rằng các giá trị của các hệ số khác 0 của đa thức $P$ không được tính đến dưới bất kỳ hình thức nào khi xây dựng đa thức $D(P)$. Tập hợp này thường được gọi là * sơ đồ Newton của đa thức $P$.

Một lời cảnh báo. Chúng ta không nên nhầm lẫn mặt phẳng số $R^2$, mặt phẳng xử lý định nghĩa của đa thức $P$, với mặt phẳng tọa độ $Omn$, trên đó chúng ta vẽ sơ đồ Newton của đa thức $P$. Các điểm của những mặt phẳng này có bản chất khác nhau.

Newton đã định nghĩa "sơ đồ Newton" như thế nào

Newton cũng ghi chú các đa thức có trong đa thức của các biến $x, y$ trên giấy ca-rô. Newton đã tự mình vẽ tờ giấy như vậy và không đánh dấu các góc của ô mà đánh dấu toàn bộ ô. Đây là cách ông mô tả những công trình xây dựng này trong một bức thư gửi cho một trong những đồng nghiệp của mình.

“...Để hiểu rõ hơn về quy tắc này, tôi sẽ trình bày nó trong sơ đồ sau. Vẽ một góc vuông $BAC$, các cạnh $BA$ và $AC$ được chia thành các phần bằng nhau và khôi phục đường vuông góc, diện tích góc được chia thành các hình vuông hoặc hình bình hành bằng nhau, được đánh dấu bằng kích thước của các chữ cái $x$ và $y$ nội tiếp trong đó (xem Hình 2). đã cho, hãy đánh dấu các hình bình hành bằng một số ký hiệu tương ứng với tất cả các số hạng của nó…”

*) Biến độc lập $x$ và $y$ lấy giá trị trong tập số thực; Do đó, hàm $P(x, y)$ có ​​mặt phẳng số là miền định nghĩa và trục số là đa thức của các giá trị.

⟦folio 21⟧

Ở đây chúng ta đang nói về việc xây dựng một “sơ đồ Newton”, và sau đó Newton mô tả việc xây dựng một “đa giác Newton” (chúng tôi tiếp tục phần trích dẫn đã dịch):

“... và áp thước cho hai hoặc, đôi khi ngẫu nhiên, cho một số điểm tương đồng được đánh dấu theo cách này, trong đó một điểm thấp nhất trong cột $AB$ ở bên trái, điểm còn lại nằm trên thước ở bên phải, và tất cả những điểm còn lại, không chạm vào thước, đều ở trên nó…”

Làm thế nào để chúng ta xác định đa giác của Newton
Chúng ta thấy rằng Newton áp dụng thước đo cho đa giác $\Delta(P)$, thỏa mãn hai điều kiện:
(I) Có ít nhất hai điểm $\Delta(P)$ rơi trên thước.
(II) Bộ $\Delta(P)$ nằm trên một mặt của thước.

Xét bao lồi của đa giác $\Delta(P)$, tức là đa giác lồi nhỏ nhất chứa tất cả các điểm $\Delta(P)$. Chúng ta sẽ ký hiệu đa giác này bằng $F(P)$ và gọi nó là đa giác Newton của đa thức $P(x, y)$. Đa giác Newton của đa thức (2) được thể hiện trên Hình 3. Mối liên hệ của đa giác $F(P)$ với phương pháp áp dụng thước kẻ của Newton là hoàn toàn rõ ràng. Nếu bạn áp dụng thước cho bất kỳ cạnh nào của đa giác Newton thì các tính chất (I) và (II) sẽ được đáp ứng. Ngược lại, nếu áp dụng thước cho đa giác $\Delta(P)$ sao cho (I) và (II) thỏa mãn, thì thước nhất thiết phải đi dọc theo một trong các cạnh của đa giác $F(P)$.

Cơm. 3.

Một số bài tập đơn giản về đa giác Newton

Để làm quen với định nghĩa đa giác Newton, người đọc cần đáp ứng các điều kiện sau:

1. Vẽ sơ đồ Newton và đa giác Newton cho các đa thức: $x, x + y, 1 + x + xy, x^2 + x^2y + x^5y^7 + x^{10}, (1 + x + x^3)(1 + y^4)^{*}$.
2. Chứng minh rằng $F(\lambda P) = F(P)$ cho $\lambda \neq 0$. Chứng minh rằng $\Delta(P_1 + P_2) \subset \Delta(P_1) \cup \Delta(P_2)$. Có đúng là $F(P_1 + P_2) = F(P_1) \cup F(P_2)$ không?
3. Đặt $Q(x, y) = P(x^a, y^b)$, trong đó $a$ và $b$ là các số tự nhiên. Các đa giác $F(P)$ và $F(Q)$ có liên quan với nhau như thế nào?
4. Đưa ra định nghĩa về sơ đồ Newton và đa giác Newton cho đa thức ba biến.

Đương nhiên họ sẽ hỏi, đa giác Newton liên hệ như thế nào với tích các đa thức với đa giác Newton cộng lại? Hóa ra thao tác mà bạn cần bán với $F(P_1)$ và $F(P_2)$ để nhận được $F(P_1 \cdot P_2)$ đã được nghiên cứu kỹ về hình học và có một tên đặc biệt: tổng Minkowski.

5. Chứng minh rằng $F(P_1 \cdot P_2) = F(P_1) + F(P_2)$, trong đó “+” là tổng Minkowski (xem bài viết của N. Vasiliev “Bổ sung các số liệu”, «Kvant», 1976, số 4).

Tính chất này của đa giác Newton khái quát hóa tính chất nổi tiếng của bậc của đa thức: khi đa thức thay đổi thì bậc của chúng cộng lại. Chính đặc tính này đã giúp sử dụng các đa thức ở lời giải của hình học thuần túy bài toán.

§ 2. Tại sao Newton lại gặp phải “đa giác Newton”?

Newton đã giải phương trình $P(x, y) = 0$, trong đó $P$ là đa thức trong $x, y$. Bằng giải pháp, anh ấy hiểu được biểu thức chính xác hoặc gần đúng của $y$ đến $x$. Như thông lệ vào thời đó, Newton không giải thích phương pháp của mình bằng những thuật ngữ chung chung mà tìm kiếm nó bằng những ví dụ cụ thể. Hãy tiếp tục trích dẫn được dịch sang § 1:

“...Sau đó lấy tất cả các số hạng của phương trình có trong các trò chơi song song do thước chạm vào và tìm từ chúng giá trị cần thu được. Vì vậy, nếu bạn cần xác định nghiệm

*) Hai ví dụ đầu tiên cho thấy đa giác Newton của đa thức $P(x, y)$ có thể không phải là đa giác thực, tức là nó có thể trùng với một điểm hoặc một đoạn.

⟦folio 22⟧

phương trình

$$y^6 - 5xy^5 + \frac{x^3}{a} y^4 - 7aaxxyy + 6a^3x^3 + bbx^4 = 0,$$

(3)

sau đó, như chúng ta thấy (xem Hình 2), tôi biểu thị các hình bình hành tương ứng với các số hạng của phương trình này bằng dấu hoa thị. Sau đó, tôi áp thước $DE$ vào phần thấp nhất của hình bình hành được đánh dấu ở cột đầu tiên bên trái và xoay thước sang bên phải cho đến khi nó đi qua bất kỳ một hoặc nhiều hình bình hành được đánh dấu khác nhau. Đồng thời, tôi thấy thước sẽ chạm vào những vị trí chứa các số hạng $x^3$, $xxyy$ và $y^6$. Vì vậy tôi sẽ đặt chúng lại với nhau thành một phương trình

$$y^6 - 7aaxxyy + 6a^3x^3 = 0$$

(mà, nếu bạn thích, thì tôi đặt $y = u\sqrt{ax}$, dẫn đến $u^6 - 7uu + 6 = 0$) và từ đó tôi tìm thấy $y$, có các giá trị chẵn, cụ thể là:

$$+ \sqrt{ax}, - \sqrt{ax}, + \sqrt{2ax}, - \sqrt{2ax}...$$

Newton giải thích chi tiết rằng lời giải được tìm thấy không chính xác mà là gần đúng (càng chính xác thì $x$ và $y$ càng gần bằng 0). Anh ấy cũng chỉ ra cách thu được lời giải chính xác bằng cách thêm một số hữu hạn hoặc vô hạn số hạng hiệu chỉnh vào lời giải đã tìm thấy. Do thiếu chỗ nên chúng tôi sẽ không trích dẫn những cách diễn đạt tương ứng trong các tác phẩm của Newton.

Phương pháp giải gần đúng của Newton cho phương trình $P(x, y) = 0$ đối với $x$ và $y$ nhỏ là gì?

Nói một cách tổng quát, phương pháp của Newton có thể được giải thích (phần nào đó bằng sơ đồ) như sau.

Để $x$ và $y$ đủ nhỏ, chúng tôi muốn giải phương trình (đính kèm) $P(x, y) = 0$ (hoặc vẽ một tập hợp gần đúng $P(x, y) = 0$). Đặt $\gamma$ là cạnh của đa giác $F(P)$ “đối diện với gốc tọa độ” (các cạnh như vậy được đánh dấu màu đỏ trong Hình 4). Ta ký hiệu bằng $P_\gamma(x, y)$ tổng của các năm được lấy với hệ số cũ, nằm trong $P(x, y)$ và tương ứng với các điểm $\gamma$. Đặt hệ số góc của cạnh $\gamma$ bằng $-k$, trong đó $k > 0$. Đưa $y = ux^{\frac{1}{k}}$ vào phương trình $P_\gamma(x, y) = 0$, chúng ta thu được phương trình $x^l Q(u) = 0$, trong đó $Q$ là một số đa thức trong $u$. Giả sử $u_1, u_2, \dots$ là nghiệm khác 0 của $Q$.

Khi đó $y_1 = u_1x^{\frac{1}{k}}, y_2 = u_2x^{\frac{1}{k}}, \dots$ là nghiệm chính xác của phương trình $P_\gamma(x, y) = 0$ và nghiệm gần đúng của phương trình $P(x, y) = 0$. Cũng đoàn kết lời giải trên tất cả các cạnh “không đối diện” $\gamma$ của đa giác $F(P)$, chúng ta thu được tất cả các nghiệm gần đúng không tầm thường*) của phương trình $P(x, y) = 0$ cho nhỏ $x$ và $y$. Việc chứng minh cụm từ cuối cùng và thậm chí cả lời giải thích về ý nghĩa chính xác của nó sẽ đưa chúng ta đi quá xa. Mục tiêu chính của chúng tôi là hướng dẫn người đọc tìm nghiệm gần đúng của phương trình $P(x, y) = 0$ (hoặc, tương tự, vẽ xấp xỉ tập $P(x, y) = 0$) cho $x$ và $y$ nhỏ.

Học cách làm việc với đa giác của Newton

Trong đa giác Newton, đa thức (2) có các cạnh $\gamma_1$ và $\gamma_2$ hướng về 0 (Hình 4). Hãy bắt đầu từ phía $\gamma_1$: $P_{\gamma_1} = xy + 0,5x^4$. Việc thay thế $y = ux^3$ sẽ đưa phương trình $P_{\gamma_2} = 0$ về dạng $x^4(u + 0,5) = 0$, do đó $y = -0,5x^3$. Tiếp theo, $P_{\gamma_2} = xy - y^3$; thay thế $y = ux^{1/2}$ mang phương trình $P_{\gamma_2} = 0$ về dạng $x^{3/2}(u - u^3) = 0$, từ đó $y = -\sqrt{x}$ và $y = +\sqrt{x}$. Tuy nhiên, hai lời giải cuối cùng có thể

*) Tên tầm thường lời giải có dạng $x = 0$ hoặc $y = 0$.

Cơm. 4.

⟦folio 23⟧

nhưng kết hợp: $x = y^2$. Vì vậy, chúng ta đã thu được điều đó đối với $x$ và $y$ nhỏ, phương trình $P(x, y) = 0$, trong đó $P$ được tính theo công thức (2), có hai lời giải gần đúng: $y = -0,5x^3$ và $x = y^2$. (Không có lời giải cố định trong trường hợp này, vì $P$ không chia hết cho $x$ hoặc $y$.) Hình dạng của lời giải gần đúng được hiển thị trong Hình 5. Bản vẽ tương tự cho $x$ nhỏ và $y$ có thể được coi là bản vẽ gần đúng của bộ $P(x, y) = 0$.

Các quyền dưới 6. Giải gần đúng phương trình $x^5y + x^3y^2 - 3x^2y^3 + xy^4 + y^7 + 2x^4y^2 + 3x^6y^3 - x^5y^5 + x^6y^6 + 7x^2y^8 = 0$ cho $x$ nhỏ và $y$ (xem Hình 6).

Newton cũng chỉ ra một phương pháp có thể giải phương trình $P(x, y) = 0$ cho $x$ và $y$ rất lớn.

Giấy phép dưới 7. Tìm ra cách sử dụng đa giác Newton để giải (xấp xỉ) phương trình $P(x, y)$ cho $x$ và $y$ rất lớn.

§ 3. Số lời giải của hệ hai phương trình có hai ẩn số và đa giác Newton
Định lý Bezout
Xét hệ hai phương trình có hai ẩn số $x, y$:

$$\begin{cases} P(x, y) = 0, \\ Q(x, y) = 0, \end{cases}$$

(4)

Cơm. 5.

Cơm. 6.

trong đó $P$ và $Q$ là các đa thức có hệ số thực. Nếu $P$ và $Q$ là đa thức bậc một *), thì số lời giải của hệ (4) là vô hạn hoặc không vượt quá 1. Nếu $P$ là đa thức bậc một và $Q$ là đa thức bậc $N$, thì dễ thấy, số lời giải của hệ thống (4) là vô hạn hoặc không vượt quá $2 \cdot N$. Sau những ví dụ này, người đọc sẽ không ngạc nhiên về cách hình thành một định lý đã nổi tiếng ở thế kỷ trước.

Định lý Bezout. Nếu $P$ là đa thức bậc $M$ và $Q$ là đa thức bậc $N$ thì số lời giải của hệ (4) là vô hạn hoặc không vượt quá $M \cdot N$.

Có thể củng cố định lý Bezout không?
Nói chung, điều đó là không thể: số $M \cdot N$ trong công thức của định lý Bezout không thể được thay thế bằng một số nhỏ hơn cho bất kỳ $M$ và $N$ nào, vì có những ví dụ về các hệ có chính xác $M \cdot N$ lời giải (ví dụ: hệ $(x - 1)(x - 2) \cdot \dots \cdot (x - M) = (y - 1)(y - 2) \cdot \dots \cdot (y - N) = 0$).

Tuy nhiên, trong nhiều trường hợp thực tế, định lý Bezout rõ ràng đã đánh giá quá cao số lời giải của hệ (4).

Ví dụ. $P = a + bx + cx^2y^2, Q = d + ey + fx^2y^2$. Định lý Bezout phát biểu rằng nếu số lời giải của một hệ $P = Q = 0$ là hữu hạn thì không vượt quá 16. Trong khi đó, giải trực tiếp hệ này dễ dàng suy ra nếu số lời giải hữu hạn thì không vượt quá 4.

Ví dụ này và các ví dụ phức tạp khác dẫn đến ý tưởng tổng quát hóa định lý Bezout. Rõ ràng là trong trường hợp này chúng ta phải thay thế khái niệm bậc của đa thức bằng một khái niệm phức tạp hơn có tính đến đầy đủ tính chất của đa thức. Như *) Chúng ta hãy nhớ lại rằng bậc của đa thức (đôi khi được gọi là bậc đầy đủ) là mức lớn nhất của số $m + n$ trong tất cả các năm $x^m y^n$ có trong đa thức.

⟦folio 24⟧

THEO SỰ TỔNG HỢP CỦA BẰNG ĐỘ NHƯ VẬY, CHÚNG TÔI SẼ TẠO RA ĐA NĂNG CỦA HỆ THỐNG NOOMON.

Gọi $D(P)$ là sơ đồ Newton của đa thức $P$ và $D(Q)$ là sơ đồ Newton của đa thức $Q$. Hãy đặt $D = D(P) \cup D(Q)$. D là tập hữu hạn trên mặt phẳng $Omn$. Điểm $M(m_0; n_0)$ thuộc về $D$ nếu cùng năm $x^{m_0}y^{n_0}$ xuất hiện với hệ số khác 0 ở ít nhất một trong các đa thức $P$ và $Q$. Một lần nữa, bằng $F$ chúng ta biểu thị bao lồi của tập hợp $D$, tức là đa giác lồi nhỏ nhất trong mặt phẳng $Omn$ chứa tất cả các điểm $D$. Chúng ta sẽ gọi đa giác $F$ là đa giác Newton của hệ (4). (Nếu trong ví dụ của chúng ta, các hệ số $a, b, \dots, f$ của đa thức $P$ và $Q$ khác 0, thì tập $D$ và đa giác $F$ của hệ (4) giống như trong Hình 7, a, 6.)

Có thể sử dụng một số đặc điểm của đa giác $F$ để ước tính từ phía trên số lời giải của hệ (4) không?

Đáp số câu hỏi này được trả lời bởi những người sau đây

Định lý 1. Số thực không đầy đủ lời giải của hệ (4) là vô hạn hoặc không vượt quá số thực thỏa mãn đa giác Newton của hệ này (lời giải $(x_0; y_0)$ của hệ (4) được gọi là không hiệu quả nếu $x_0 \neq 0$ và $y_0 \neq 0$).

Định lý 1 thuộc về tác giả bài viết này. Bằng chứng của nó là gián tiếp: một định lý được chứng minh lần đầu tiên trong đó không sử dụng diện tích của đa giác $F$ mà sử dụng các đặc điểm khác của nó - cụ thể là số điểm nguyên trong đa giác $F$ và trong “đa giác kép” 2F. Do đó, khi làm việc với đa giác Newton, các câu hỏi hình học thú vị nảy sinh liên quan đến các điểm nguyên trong đa giác. Thậm chí còn nhiều câu hỏi thú vị hơn liên quan đến máy đo nói dối của Newton. Tất cả điều này được thảo luận chi tiết trong bài viết “Các điểm tích phân trong đa giác và khối đa diện” («Kvant», 1977, số 4).

Có thể cải thiện Định lý 1 không?

Định lý 1 đưa ra ước tính tốt cho số lời giải trong trường hợp đa giác $F(P)$ và $F(Q)$ trùng nhau hoặc đủ gần (nếu không thì ước tính quá nhóm: hãy xem xét hệ thống $x^n + y^{n+1} = y^n + y^{n+1} = 0$). Để có được ước tính chính xác hơn, bạn cần xem xét riêng $D(P)$ và $D(Q)$ về cách thực hiện việc này. N. Bernistein, người đã khái quát Định lý 1 như sau.

Định lý 2. Giả sử $A$ là đa giác Newton của đa thức $P$, $B$ là đa giác Newton của đa thức $Q$ và $C$ là đa giác Newton của đa thức $P \cdot Q$. Khi đó số lời giải chưa hoàn chỉnh của hệ (4) là vô hạn hoặc không vượt quá số $S(C) - S(A) - S(B)$. (Ở đây $S$ biểu thị diện tích của đa giác tương ứng.)

Đa giác $C$ không gì khác hơn là tổng Minkowski của các đa giác $A$ và $B$, và đối với số $S(C) - S(A) - S(B)$ có một tên đặc biệt về mặt hình học: diện tích hỗn hợp của đa giác $A$ và $B$ (xem Bài tập 5 và bài viết của N. Vasiliev được trích dẫn ở đó).

Bài tập 8. Áp dụng Định lý 1 cho đa thức (2) và các đa thức ở Bài tập 1.

9. Sử dụng định lý Bezout và Định lý 1, hãy ước tính số lời giải của hệ $x^3 + y^4 = axy + bx^2y^2 + cx^3y^2 + dx^4y^3$ cho $a \neq 0$ và $d \neq 0$.

10. Tổng quát hóa Định lý 1 cho trường hợp hệ ba phương trình đại số với ba ẩn số $x, y, z$.

VĂN HỌC

1. Isaac Newton, Công trình toán học. Phương pháp cố định và chuỗi vô hạn với ứng dụng của nó đối với các nhà phê bình hình học. Bản dịch từ tiếng Latin của D. Morduchai-Voltovsky, ONTI, 1937, tr. 33-34.

2. Isaac Newton, Bức thư thứ hai của Newton gửi Oldenburg, sẽ được báo cáo cho Leibniz. Ngày 24 tháng 10 năm 1976, Ibid., tr. 251-252.

3. N. G. Chebotarev, Tác phẩm sưu tầm. T. 3. “Đa giác Newton” và vai trò của nó trong sự phát triển hiện đại của toán học,” Nhà xuất bản Viện Hàn lâm Khoa học Liên Xô, M.-L., 1950, trang 47-80.
