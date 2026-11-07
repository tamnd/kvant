---
id: 1992-3-zatakavay-reshaem-sistemyi-uravneniy-7b96c5ce
issue: kvant_1992_3
year: 1992
number: "3"
title: Giải hệ phương trình
authors:
  - Затакавай В. В.
rubric: praktikum-abiturienta
rubric_sub: Практикум абитуриента
page_first: 50
page_last: 55
page_labels: 48, 49, 51, 52, 53
lang: vi
source: kvant_digital
extraction: vision
content_sha256: eb1670aead9784c1ed0b93909a65d9185e999af2c8a9fec5c95ee667bf5fb132
prompt_sha256: draft-1
translated_from: content/ru/1992/03/articles/15_zatakavay-reshaem-sistemyi-uravneniy-7b96c5ce.md
source_content_sha256: 3033981afbe2826abd60c4a0705420fd39b716975a4256f70779050943b836c7
translation_model: draft
translation_run: vi-draft-gaps-2026-11-06
translation_quality: draft
---

⟦folio 48⟧

---
running_head:
folio:
---

Đây là đường chuyền đi từ điểm (từ bên trong)
Đây là đường chuyền đi từ điểm (bên ngoài)

Nguyên tắc nghiên cứu hệ thống điều khiển
Ứng viên khoa học sư phạm
B. KHÓA

Trong bài viết này, chúng tôi sẽ giúp học sinh phân loại các hệ thống quản lý khác nhau gặp phải khi thực hành các kỳ thi tuyển sinh và đưa ra lời khuyên về lời giải của chúng.

Với hệ thống lời giải, điều quan trọng nhất là có thể giảm nó xuống một hệ thống chắc chắn có thể giải quyết được. Trong trường hợp này, một số kỹ thuật tiêu chuẩn mặc quần áo lời giải thường hữu ích. Phổ biến nhất trong số đó là thay thế các biến*).

Ví dụ 1.
$$\begin{cases} \frac{2}{2x-y} + \frac{3}{x-2y} = \frac{1}{2}, \\ \frac{2}{2x-y} - \frac{1}{x-2y} = \frac{1}{18}. \end{cases}$$

Với sự trợ giúp của $\frac{1}{2x-y} = u$, $\frac{1}{x-2y} = v$ hệ thống này trở nên tuyến tính:
$$\begin{cases} 2u + 3v = \frac{1}{2}, \\ 2u - v = \frac{1}{18}. \end{cases}$$

Giải quyết xong, chúng ta có được
$$u = \frac{1}{12}, v = \frac{1}{9}.$$

Quay lại các biến cũ và thực hiện các phép biến đổi rất sâu rộng, tiếp cận hệ thống điều khiển tuyến tính
$$\begin{cases} 2x - y = 12, \\ x - 2y = 9. \end{cases}$$

lời giải của cô ấy không nên làm cho nó khó khăn hơn nữa.

Đáp số: (5; -2).

Ví dụ 2.
$$\begin{cases} (x+y)^2 - 4(x+y) = 45, \\ (x-y)^2 - 2(x-y) = 3. \end{cases}$$

*)Ở đây chúng ta sẽ bỏ qua các cuộc thảo luận về sự tương đương của các phép biến đổi và chuyển đổi, ngụ ý rằng chúng được thực hiện.

⟦folio 49⟧

---
running_head:
folio:
---

Rõ ràng là mỗi phương trình của hệ đều là phương trình bậc hai: phương trình thứ nhất đối với $(x+y)$, phương trình thứ hai đối với $(x-y)$. Trong trường hợp này, đây là cơ sở để thay đổi các biến: $x+y=u$, $x-y=v$. Giải phương trình bậc hai của $u$ và $v$, ta thu được $u_1=-5$, $u_2=9$ và $v_1=-1$, $v_2=3$.

Bây giờ hệ thống ban đầu được chia thành bốn tuyến tính:

$$\begin{cases}
x+y=-5, & x+y=-5, \\
x-y=-1, & x-y=3, \\
x+y=9, & x+y=9, \\
x-y=-1, & x-y=3.
\end{cases}$$

Hơn nữa lời giải được thực hiện trên thực tế.

Đáp số: $(-3; -2); (-1; -4); (4; 5); (6; 3)$.

Nghệ thuật thay đổi các biến số là xem sự thay đổi nào có ý nghĩa nhất và sẽ dẫn đến thành công nhanh hơn. Trong trường hợp này, chúng tôi khuyên bạn nên tuân thủ các quy tắc sau: thay thế ngay khi có cơ hội; chỉ quay lại các biến cũ sau khi tất cả các phép biến đổi đã được thực hiện với các biến mới (nghĩa là sau khi nhận được kết quả cuối cùng liên quan đến các biến mới).

Trong ví dụ 1 và 2, sự thay thế rất mạnh mẽ, dường như nó tự diễn ra. Sự thay thế có ý nghĩa không kém trong hệ thống khi một trong các phương trình (hoặc một số) là tổng đại số của các biểu thức tương tác.

Ví dụ 3

$$\begin{cases}
\frac{x+y}{x-y} + \frac{x-y}{x+y} = \frac{10}{3}, \\
x^2-y^2=12.
\end{cases}$$

Ở đây thật thuận tiện khi xem xét phương trình đầu tiên của hệ và thực hiện thay thế $\frac{x+y}{x-y}=z$. Phương trình sẽ có dạng

$$z+\frac{1}{z}=\frac{10}{3},$$

từ đâu $z_1=3$, $z_2=\frac{1}{3}$.

Bây giờ hệ thống được chia thành hai phần sau:

$$\begin{cases}
\frac{x+y}{x-y}=3, & \text{и} \\
x^2-y^2=12,
\end{cases}$$

vốn đã dễ giải quyết.

Đáp số: $(-4; -2); (-4; 2); (4; -2); (4; 2)$.

Tuy nhiên, trong nhiều trường hợp, một sự thay thế thuận tiện không phải là điều tốt. Một nhóm lớn các hệ thống như vậy (thường gặp trong các kỳ thi ứng dụng) được gọi là hệ thống đối xứng (hoặc đối xứng).

Hãy nhớ lại rằng một hệ được gọi là đối xứng nếu việc thay thế $x$ bằng $y$ và $y$ bằng $x$ không làm thay đổi từng phương trình của nó.

Đối với hệ thống đối xứng lời giải, có một sự thay thế tiêu chuẩn:

$$x+y=u, xy=v.$$

Ví dụ 4.

$$\begin{cases}
x^2+y^2-x-y=102, \\
xy+x+y=69.
\end{cases}$$

Hãy để $x+y=u, xy=v$. Để biểu thị $x^2+y^2$ dưới dạng các biến mới, $x+y=u$ phải bình phương.

Chúng ta có $x^2+2xy+y^2=u^2$, từ đó $x^2+y^2=u^2-2v$.

Chúng tôi nhận được hệ thống

$$\begin{cases}
u^2-2v^2-u=102, \\
u+v=69.
\end{cases}$$

lời giải của cô ấy rất không. chúng tôi nhận được

$$\begin{cases}
u=15, \\
v=54 \end{cases}$$

Cặp số cuối cùng không dẫn đến lời giải thực khi quay lại các biến cũ.

Đáp số: $(6; 9); (9; 6)$.

Có một nhóm hệ phương trình phổ biến khác mà lời giải yêu cầu quy ước tiêu chuẩn. Đây là những hệ thống có dạng

$$\begin{cases}
a_1x^2+b_1xy+c_1y^2=d_1, \\
a_2x^2+b_2xy+c_2y^2=d_2.
\end{cases}$$

⟦folio 51⟧

---
running_head:
folio:
---

$$xy^2 - 11xy - 18 = 0.$$

Nguồn gốc của nó là số 9 và 2.

Kết quả là hệ thống chia thành hai:

$$\begin{cases} xy = 9, \\ 3x^2y^2 + x^2 - 3xy - 7 = 0 \end{cases}$$

Và

$$\begin{cases} xy = 2, \\ 3x^2y^2 + x^2 - 3xy - 7 = 0. \end{cases}$$

Điều đầu tiên trong số chúng tỏ ra không nhất quán, điều thứ hai dẫn đến phương trình $x^2 = 1$.

Đáp số: $(-1; -2); (1; 2)$.

Sử dụng ví dụ lời giải của hệ thống này, chúng tôi chỉ trình bày một ví dụ về loại bỏ những ẩn số. Công bằng mà nói, phải nói rằng một độc giả tinh ý sẽ thấy một sự thay thế rất tốt trong hệ thống này: $xy = u$, $x^2 = v$, nhưng quyết định thế nào là vấn đề sở thích.

Ví dụ 8.

$$\begin{cases} xy + 24 = \frac{x^3}{y}, \\ xy - 6 = \frac{y^2}{x}. \end{cases}$$

Mong muốn tự nhiên để loại trừ $xy$ khỏi hệ thống nhóm sẽ chỉ tạo điều kiện cho lời giải. Ở đây tốt hơn là nhân các phương trình. Sau đó, chúng tôi thu được $xy = 8$ đó và hệ thống có dạng

$$\begin{cases} xy = 8, \\ \frac{y^3}{x} = 2. \end{cases}$$

Đáp số: $(-4; -2); (4; 2)$.

Thông thường, nên loại bỏ tuần tự các phần tử chưa biết theo một dạng "trường học" khác: biểu thị bất kỳ ẩn số nào từ một phương trình dưới dạng các ẩn số còn lại và thay thế nó vào các phương trình khác của hệ thống.*

*)Thuật ngữ “trường học” ở đây được sử dụng với ý nghĩa là trong toán học phổ thông, loại phương pháp loại trừ tuần tự các biến này được coi là một phương pháp độc lập của hệ lời giải - một phương pháp thay thế.

Ví dụ 9.

$$\begin{cases} 4x^2 + 4x - y^2 = -1, \\ 4x^2 - 3xy + y^2 = 1. \end{cases}$$

Từ phương trình đầu tiên của hệ ta có

$$y^2 = 4x^2 + 4x + 1,$$

tức là $y^2 = (2x + 1)^2$, mở

$$y = 2x + 1$$ hoặc $y = -2x - 1$.

lời giải xa hơn là hiển nhiên.

Đáp số: $(-0,5; 0); (0; -1); (0; 1)$.

Ví dụ 10.

$$\begin{cases} y^4 + 19 = x + y, \\ \sqrt{x} + \sqrt{x + 2y} = \sqrt{2}. \end{cases}$$

Có vẻ như không có cách nào để sử dụng kỹ thuật được thảo luận ở đây, tuy nhiên, bằng cách bình phương phương trình thứ hai hai lần, chúng ta nhận được

$$x = \frac{(1 - y)^2}{2}$$ . Bây giờ chúng ta hãy quay lại phương trình đầu tiên. chúng tôi có

$$y^4 - 10y^2 + 9 = 0.$$

Các số $\pm 1, \pm 3$ là nghiệm của phương trình hai phương trình thu được, nhưng nghiệm $\pm 3$ không thỏa mãn điều kiện ban đầu.

Đáp số: $(0; 1); (2; -1)$.

Với hệ phương trình lời giải, người ta không được quên các phép tính đại số sơ cấp cực kỳ phức tạp, điều này có thể thực hiện được với sự trợ giúp của một số phép biến đổi nhất định (nhóm, đặt thừa số chung ra khỏi ngoặc, sử dụng công thức nhân viết tắt, v.v.), để đơn giản hóa cả bản thân hệ đã cho và quá trình không được biểu diễn lời giải.

Vì vậy, trong ví dụ 9 và 10, các công thức nhân rút gọn đã giúp ích cho chúng ta. Như ví dụ 9, trong lời giải của nó, chúng ta có thể sử dụng một phương trình khác: cộng cả hai phương trình, chúng ta nhận được

$$8x^2 + 4x - 3xy = 0.$$

Bây giờ hãy lấy hệ số chung ra khỏi ngoặc:

$$x(8x + 4 - 3y) = 0.$$

⟦folio 52⟧

---
running_head:
folio:
---

Kết quả là hệ thống chia thành hai:
$$\begin{cases} x = 0, \\ 4x^2 + 4x - y^2 = -1 \end{cases}$$
Và
$$\begin{cases} y = \frac{8x + 4}{3}, \\ 4x^2 + 4x - y^2 = -1. \end{cases}$$
Việc giải chúng không khó nhưng việc lựa chọn phương pháp lời giải của hệ 9 tùy thuộc vào người đọc.
Hãy xem xét thêm một vài ví dụ.

Ví dụ 11.
$$\begin{cases} y^4 + xy^2 - 2x^2 = 0, \\ x + y = 6. \end{cases}$$
Một sự thay thế rõ ràng (chúng ta biểu thị một số biến từ phương trình thứ hai và thay thế nó vào phương trình thứ nhất) không dẫn đến một kết quả tốt, vì chúng ta thu được một phương trình bậc bốn, lời giải thành công của phương trình này là rất có vấn đề.
Hãy biến đổi phương trình đầu tiên:
$$(y^2 - x)(y^2 + 2x) = 0.$$
Sau đó, hệ thống này chia thành hai:
$$\begin{cases} y^2 - x = 0, \\ x + y = 6 \end{cases}$$
Và
$$\begin{cases} y^2 + 2x = 0, \\ x + y = 6. \end{cases}$$
Hệ thống thứ hai không có lời giải.
Cộng cả hai phương trình trước, chúng ta thu được phương trình bậc hai
$$y^2 + y - 6 = 0.$$
Đáp số: (4; 2); (9; -3).

Ví dụ 12.
$$\begin{cases} 10x^2 + 5y^2 - 2xy - 38x - 6y + 41 = 0, \\ 3x^2 - 2y^2 + 5xy - 17x - 6y + 20 = 0. \end{cases}$$
Lời giải hệ thống này đòi hỏi kỹ năng và trực giác. Hãy nhân phương trình thứ hai với -2 và cộng nó với phương trình thứ nhất. chúng tôi nhận được
$$4x^2 + 9y^2 - 12xy - 4x + 6y + 1 = 0,$$
hoặc
$$(2x - 3y)^2 - 2(2x - 3y) + 1 = 0.$$
Ở đây cũng vậy, thật dễ dàng để thấy bình phương đầy đủ của hiệu. chúng tôi có
$$(2x - 3y - 1)^2 = 0.$$
Hệ thống tuy phức tạp nhưng lại đơn giản theo phương pháp lời giải:
$$\begin{cases} 10x^2 + 5y^2 - 2xy - 38x - 6y + 41 = 0, \\ 2x - 3y - 1 = 0. \end{cases}$$
Chúng tôi thấy rằng nó thực sự đòi hỏi “kỹ năng và trực giác”: không thể thống nhất về cách biến đổi các phương trình sao cho sự đơn giản hóa rất thuận tiện xảy ra. Tuy nhiên, đối với lời giải các hệ tương tự, có một ví dụ tiêu chuẩn: người ta phải coi một trong các phương trình là quan hệ bậc hai của một ẩn số. Trong trường hợp này, hãy coi phương trình đầu tiên là phương trình bậc hai $x$. chúng tôi có
$$10x^2 - 2(y + 19)x + 5y^2 - 6y + 41 = 0.$$
Hãy tính phân biệt của nó:
$$\frac{D}{4} = -49(y - 1)^2.$$
Phương trình bậc hai có nghiệm thực tại $D \geqslant 0$, có nghĩa là bất đẳng thức $-49(y - 1)^2 \geqslant 0$ phải được thỏa mãn, điều này chỉ có thể thực hiện được ở $y = 1$. Bây giờ thay thế giá trị này $y$ vào bất kỳ phương trình nào trong số này, chúng ta nhận được $x = 2$.
Đáp số: (2; 1).
Bây giờ hãy áp dụng phương pháp này trong một tình huống khác.
Ví dụ 13.
$$\begin{cases} x^2 - 6y^2 - xy - 2x + 11y = 3, \\ x^2 + y^2 = 5. \end{cases}$$
Coi phương trình đầu tiên của hệ là phương trình bậc hai $x$:
$$x^2 - (y + 2)x - 6y^2 + 11y - 3 = 0.$$
Trong trường hợp này, $D = (5y - 4)^2$ có nghĩa là $x_1 = 3y - 1$, $x_2 = 3 - 2y$.
Hệ thống được chia thành hai:
$$\begin{cases} x = 3y - 1, \\ x^2 + y^2 = 5 \end{cases}$$
Đáp số: (-2,2; -0,4); (-1; 2); (2; 1); (2,2; 0,4).

⟦folio 53⟧

---
running_head:
folio:
---

Chúng tôi đã cố gắng cung cấp cho người đọc một loạt các số nguyên tố và phương pháp lời giải của tất cả các hệ đại số có thể có. Đúng, chúng tôi chưa đề cập đến các hệ phương trình như lượng giác, hàm mũ và logarit, nhưng lý do của chúng lời giải vẫn giữ nguyên, chỉ thêm tính đặc hiệu của các hàm tương ứng.

Mặc dù thực tế là một số hệ thống lời giải sử dụng các phương pháp tiêu chuẩn, nhưng hầu hết chúng đều yêu cầu một cách tiếp cận riêng lẻ. Nhưng ngay cả trong những tình huống tiêu chuẩn, bạn cũng cần phải suy nghĩ và tìm kiếm con đường tối ưu lời giải.

Ví dụ 14.
$$\begin{cases} x\sqrt{y} + y\sqrt{x} = 6, \\ x^2y + y^2x = 20. \end{cases}$$

Hệ thống này đối xứng, và tất nhiên, nó có thể được giải bằng cách thay thế tiêu chuẩn. Tuy nhiên, việc thay thế $x\sqrt{y} = u$, $y\sqrt{x} = v$ cho phép bạn đi đến kết quả chính xác nhanh hơn nhiều.

Đáp số: (1; 4); (4; 1).

Ví dụ 15.
$$\begin{cases} x^2 - 5xy + 3y^2 = 17, \\ 2x^2 - 7xy + 4y^2 = 26. \end{cases}$$

Hệ thống này là tiêu chuẩn - nó được rút gọn thành một phương trình đồng nhất (so sánh với ví dụ 5). Tuy nhiên, ở đây dễ dàng nhận thấy rằng nếu chúng ta trừ phương trình thứ nhất khỏi phương trình thứ hai, chúng ta sẽ nhận được bình phương hoàn chỉnh của hiệu:
$$x^2 - 2xy + y^2 = 9,$$
Ở đâu
$$x - y = 3$$ hoặc $x - y = -3$.

Hãy tự mình mang theo lời giải của hệ thống này để hoàn thành.

Đáp số: (-5; -8); (-2; 1); (2; -1); (5; 8).

Tóm lại, tôi muốn đưa ra một lời khuyên.

Trong hệ thống lời giải, cũng như trong thể thao, những người luyện tập sẽ đạt được thành thạo. Vì vậy - hãy quyết định! Càng nhiều càng tốt.
