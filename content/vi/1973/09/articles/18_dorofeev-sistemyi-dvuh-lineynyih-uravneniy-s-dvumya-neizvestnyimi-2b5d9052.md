---
id: 1973-9-dorofeev-sistemyi-dvuh-lineynyih-uravneniy-s-dvumya-neizvestnyimi-2b5d9052
issue: kvant_1973_9
year: 1973
number: "9"
title: Hệ hai phương trình tuyến tính với hai ẩn số
authors:
  - Дорофеев Г. В.
rubric: praktikum-abiturienta
rubric_sub: Практикум абитуриента
page_first: 65
page_last: 69
page_labels: 63-67
tag: PQL5
lang: vi
source: kvant_digital
extraction: vision
content_sha256: 69e059e0a665b3a266113e945d593ceacee87cb52a711deb24642c40a2d40a28
prompt_sha256: draft-1
translated_from: content/ru/1973/09/articles/18_dorofeev-sistemyi-dvuh-lineynyih-uravneniy-s-dvumya-neizvestnyimi-2b5d9052.md
source_content_sha256: 2db3ebbad99c476662d5b1e358262d61ad69d9dcf8aa717e523b287249c56f89
translation_model: draft
translation_run: vi-draft-2026-10-31
translation_quality: draft
---

⟦folio 63⟧

Khi chuẩn bị cho kỳ thi tuyển sinh môn toán, các ứng viên tương lai thường tập trung hầu hết sự chú ý của họ vào lời giải bài toán, đặc biệt là những điểm được đưa ra trong các kỳ thi năm trước tại trường đại học mà họ đã chọn. Và họ dành ít thời gian hơn cho việc chuẩn bị lý thuyết. Nhiều người thậm chí còn để lại lý thuyết "để sau", hy vọng rằng họ có thể thành thạo nó trong vài ngày giữa kỳ thi viết và vấn đáp. Tất nhiên, sự thiên vị “thực tế” như vậy không tự biện minh được.

Trước hết, thực tế là trong các kỳ thi vấn đáp, việc chuẩn bị lý thuyết của ứng viên được kiểm tra rất chuyên sâu, ở tất cả những điểm tinh tế có trong bất kỳ lý thuyết toán học nào. Và tất nhiên, tất cả các loại “cạm bẫy” trong việc chứng minh các định lý chỉ cần được nhìn thấy trước nhưng cũng phải học cách tránh. Nhưng - và tất nhiên, đây là điều quan trọng nhất - lý thuyết chính xác là cần thiết cho lời giải bài toán. Tất nhiên, có bài toán có ​​thể được giải bằng cách sử dụng một số mẫu hoặc thuật toán, ngay cả khi bạn có ý tưởng mơ hồ nhất về lý thuyết. Tuy nhiên, có rất ít bài toán như vậy và rất khó để hiểu những ví dụ phức tạp hơn, không mang tính giảng dạy nếu không có kiến ​​thức lý thuyết phù hợp.

Một trong những điểm quan trọng và khó nhất đối với thí sinh trong chương trình thi tuyển sinh môn toán là lời giải hệ hai phương trình tuyến tính có hai ẩn số. Người ta có thể ngay lập tức đưa ra phản đối: làm sao có thể giải quyết được một hệ thống như vậy? Không có gì có thể đơn giản hơn. Bạn cần biểu thị y theo x từ một phương trình, thay thế nó vào phương trình thứ hai, tìm x và sau đó là y. Và thực sự, mọi thứ sẽ rất đơn giản nếu tôi quyết định chỉ giải các hệ thống cụ thể bằng các hệ số số. Tuy nhiên, trong thực tế - cả trong các bài toán “huấn luyện” và trong các nhiệm vụ mà hệ thống được sử dụng như một bộ máy phụ trợ - cần phải xem xét các hệ thống có hệ số chữ cái, tức là có tham số. Và đây đã là một điều kiện quan trọng bài toán. Và nói chung, lời giải bài toán có tham số là gót chân Achilles của nhiều đặc điểm.

Về lý thuyết, trường hợp tổng quát nhất được xem xét khi hệ thống có các hệ số tùy ý và lời giải của hệ thống đó là lời giải bài toán với sáu tham số! Tuy nhiên, việc nắm vững lý thuyết này đóng vai trò đảm bảo cho việc áp dụng đúng đắn nó trong các trường hợp cụ thể.

Hãy bắt đầu lại từ đầu, nghĩa là với các định nghĩa. Hệ hai phương trình tuyến tính hai ẩn số là gì? Thật không may, định nghĩa được đưa ra trong sách giáo khoa*) lại không chính xác lắm. Thực tế là từ “set” khi áp dụng cho một phương trình gần đây đã không còn đồng nghĩa với các từ “set”, “on-

*) Xem E. S. Kochetkov, E. S. Kochetkova “Đại số và các hàm cơ bản”, phần I, § 26.

⟦folio 64⟧

boron”, nhưng mang một ý nghĩa khác, chẳng hạn như thuật ngữ “hệ phương trình” và “tập hợp các phương trình” có ý nghĩa hoàn toàn khác nhau.

Cụ thể, nếu có một số phương trình, thì chúng được cho là tạo thành một hệ thống nếu cần tìm các giá trị của ẩn số mà tất cả các phương trình này đều thỏa mãn. Nếu bạn cần tìm các giá trị của ẩn số mà ít nhất một trong các phương trình này thỏa mãn, thì họ nói rằng các phương trình này tạo thành một tập hợp. Do đó, một số phương trình tạo thành một hệ hoặc tập hợp tùy thuộc vào tập hợp bài toán.

Những lập luận này áp dụng cho các hệ phương trình tùy ý, không nhất thiết phải tuyến tính. Vì vậy, chúng ta thấy rằng ngay cả cách tiếp cận để xác định một hệ gồm hai phương trình tuyến tính với hai ẩn số cũng đòi hỏi phải có sự suy nghĩ cẩn thận sơ bộ.

Khi thi vấn đáp, bạn có thể đưa ra định nghĩa sau: hệ hai phương trình tuyến tính với hai ẩn số x, y được gọi là hệ phương trình có dạng

$$\begin{align*}
a_1x + b_1y &= c_1, \\
a_2x + b_2y &= c_2,
\end{align*}$$

thức ăn $a_1, b_1, c_1, a_2, b_2, c_2$ - số tùy ý (thực, hoặc thậm chí phức tạp - tại sao không?).

Trong định nghĩa này, và điều quan trọng cần nhấn mạnh là, một hệ gồm hai phương trình với hai ẩn số được phân biệt như một trường hợp đặc biệt của khái niệm tổng quát—một hệ gồm k phương trình với n ẩn số. Trong trường hợp này, không nhất thiết phải đưa ra định nghĩa chung về hệ phương trình, nhưng bạn cần biết nó (ví dụ, ở dạng đã chỉ ra trước đó) và nếu cần, có thể xây dựng nó.

Một nhược điểm chung của người nộp đơn là khi đưa ra định nghĩa đúng, người nộp đơn sẽ bị lạc khi xem xét các trường hợp đặc biệt “lạ”, chẳng hạn như

$$\begin{align*}
2x + y &= 5 \\
2x + y &= 5 \\
x + y &= 1 \\
x + y &= 2.
\end{align*}$$

Chúng ta thường nghe rằng trong trường hợp thứ nhất chỉ có một phương trình, trong trường hợp thứ hai chỉ có một phương trình chưa biết, và phương trình thứ ba “hoàn toàn không tồn tại”. Trong khi đó, cả ba hệ thống sẽ thỏa mãn định nghĩa này, trong đó không có phép toán nào trên các hệ số x, y và các số hạng tự do.

Tình huống này đôi khi gây ra sự phản kháng về mặt tâm lý: tại sao lại cần phải xem xét những hệ thống vô lý như vậy? Tuy nhiên, chúng ta hãy nhớ một lần nữa rằng các hệ thống có tham số thường được giải và đối với các giá trị nhất định của tham số, hầu hết các trường hợp “không tự nhiên” đều có thể xảy ra.

Lời giải hệ hai phương trình tuyến tính với hai ẩn số được thảo luận chi tiết trong sách giáo khoa của trường Kochetkovs. Tuy nhiên, cần lưu ý rằng người nộp đơn thường không thể đưa ra một công thức thu gọn và chứng minh tương ứng của định lý chính về các hệ lời giải thuộc loại đang được xem xét. Chúng tôi cũng lưu ý rằng trong bảng kết quả được đưa ra trong sách giáo khoa của Kochetkovs (§ 33), trường hợp tất cả các hệ số của ẩn số bằng 0 sẽ bị bỏ qua. Bất chấp tất cả sự “không tự nhiên” rõ ràng của trường hợp này, nó có thể trở thành sự thật (hãy nhớ các tham số!) Và do đó nên được đưa vào danh sách kết quả.

Định lý cơ bản này có thể được phát biểu như sơ đồ sau.

Định lý. Cho hệ phương trình dưới cùng

$$\begin{align*}
a_1x + b_1y &= c_1, \\
a_2x + b_2y &= c_2.
\end{align*}$$

Hãy giới thiệu ký hiệu sau:

$$\Delta = \begin{vmatrix}
a_1 & b_1 \\
a_2 & b_2
\end{vmatrix} = a_1b_2 - a_2b_1,$$

$$\Delta_x = \begin{vmatrix}
c_1 & b_1 \\
c_2 & b_2
\end{vmatrix} = c_1b_2 - c_2b_1,$$

$$\Delta_y = \begin{vmatrix}
a_1 & c_1 \\
a_2 & c_2
\end{vmatrix} = a_1c_2 - a_2c_1.$$

⟦folio 65⟧

Toeda

$$\frac{\Delta = 0}{\downarrow \Delta} \rightarrow \text{система определения*}$$

(chấm),

$$\frac{\Delta_x = \Delta_y = 0}{\downarrow \Delta} \rightarrow \text{система несовместная,}$$

$$\frac{a_1 = b_1 = a_2 = b_2}{\downarrow \Delta} \rightarrow \text{система неопределения (прямая),}$$

$$\frac{c_1 = c_2 = 0}{\downarrow \Delta} \rightarrow \text{система несовместная (плоскость).}$$

Sơ đồ này nên được hiểu như sau. Trước hết, câu hỏi được đặt ra: $\Delta = 0$? Nếu không, hệ thống định nghĩa (có một lời giải); nếu có thì câu hỏi sẽ được đặt ra: $\Delta_x = \Delta_y = 0$? Nếu không thì hệ thống không tương thích; nếu có thì chúng ta sẽ hỏi câu hỏi tiếp theo, v.v. Các từ “điểm”, “đường thẳng”, “mặt phẳng” chỉ cách giải thích hình học của trường hợp tương ứng.

Cần lưu ý thêm rằng trong trường hợp đầu tiên $x = \frac{\Delta_x}{\Delta}$, $y = \frac{\Delta_y}{\Delta}$ và trong trường hợp thứ ba (nghĩa là khi $\Delta = \Delta_x = \Delta_y = 0$, nhưng không phải tất cả các hệ số của ẩn số đều bằng 0), hệ thống tương đương với một phương trình - phương trình trong đó có hệ số khác 0.

Công thức này giúp dễ dàng suy ra các điều kiện cần và điều kiện đủ thuộc loại này: hệ là mô hình xác định và mô hình khi $\Delta \neq 0$; hệ thống không nhất quán với mô hình và mô hình molko khi $\Delta = 0$, nhưng $\Delta_x \neq 0$ hoặc $\Delta_y \neq 0$ hoặc tất cả các hệ số của ẩn số đều bằng 0 và ít nhất một trong các số hạng tự do không bằng 0.

*) Thật không may, sách giáo khoa không chứa các thuật ngữ “định nghĩa” và “không định nghĩa” về một hệ thống. Một hệ thống được gọi là xác định nếu nó có chính xác một lời giải và không xác định nếu nó có nhiều hơn một lời giải. Những điều khoản này thuận tiện cho việc sử dụng, nhưng tất nhiên là không bắt buộc.

Chúng ta hãy xem xét một số ví dụ điển hình về việc áp dụng định lý này.

Bài toán 1 (MSU, Khoa Địa lý, 1970). Tại giá trị nào của tham số a thì hệ phương trình

$$\begin{cases} ax - 4y = a + 1, \\ 2x + (a + 6)y = a + 3 \end{cases}$$

không có lời giải?

Chúng tôi xin lưu ý ngay rằng điều kiện về tính không tương thích của hệ thống nêu trên có phần phức tạp và trong thực tế, người ta thường không nên áp dụng điều kiện này “trong mọi trường hợp” mà chỉ làm việc với các điều kiện không tương thích cần thiết $\Delta = 0$. Điều này cho phép chúng ta không đếm các định thức $\Delta_x$ và $\Delta_y$.

Chúng tôi có: $\Delta = a^2 + 6a + 8$; do đó, $\Delta = 0$ tại $a = -2$ và tại $a = -4$. Thay $a_1 = -2$ vào hệ này, ta thu được hệ

$$\begin{cases} -2x - 4y = -1, \\ 2x + 4y = 1, \end{cases}$$

rõ ràng (hoặc dựa trên trường hợp thứ ba của định lý), có vô số lời giải. Với $a_2 = -4$ chúng ta có hệ thống

$$\begin{cases} -4x - 4y = -3, \\ 2x + 2y = -1, \end{cases}$$

điều này rõ ràng là không nhất quán (hoặc dựa trên trường hợp thứ hai của định lý).

Đáp số: $a = -4$.

Bài toán 2 (MSU, Khoa Sinh học, 1970). Các số $a, b, c$ được cho là một hệ phương trình,

$$\begin{cases} ax - by = 2a - b, \\ (c + 1)x + cy = 10 - a + 3b \end{cases}$$

có vô số lời giải, và $x = 1$, $y = 3$ là một trong số lời giải này. Tìm các số $a, b, c$.

Chúng ta hãy lưu ý ngay rằng trong phương trình thứ hai của hệ, với không $c$, các hệ số của ẩn số đồng thời chuyển sang 0. Do đó, đối với hệ này, trường hợp thứ ba của định lý xảy ra. Các định thức $\Delta, \Delta_x, \Delta_y$ ở đây trông khá cồng kềnh và để đơn giản hóa các phép tính, trước tiên chúng ta sẽ sử dụng các điều kiện bổ sung bài toán. Vì cặp số $x = 1$,

⟦folio 66⟧

$$y = 3 \text{ является решением системы, то } \begin{cases} a - 3b = 2a - b, \\ c + 1 + 3c = 10 - a + 3b. \end{cases}$$

Do đó $a = -2b, c = (5b + 9)/4$. Tiếp theo chúng ta tìm thấy: $\Delta = ac + bc + b = (-5b^2 - 5b)/4 = 0$, từ đâu $b_1 = 0, b_2 = -1$. Sau đó $a_1 = 0, c_1 = \frac{9}{4}; a_2 = 2, c_2 = 1$.

Trong hai trường hợp này, người ta cũng thu được các hệ thống sau:

$$\begin{cases} 0x + 0y = 0, \\ \frac{13}{4}x + \frac{9}{4}y = 10, \\ 2x + y = 5, \\ 2x + y = 5. \end{cases}$$

Cả hai hệ đều thỏa mãn điều kiện bài toán.

Đáp số: $a_1 = 0, b_1 = 0, c_1 = \frac{9}{4}; a_2 = 2, b_2 = -1, c_2 = 1$.

Bài toán 3. Tại giá trị nào của hệ thống $a$

$$\begin{cases} (a^2 - 1)x + (a + 1)y = a^2 - 2, \\ (a + 1)x + 2ay = 2a + 1 \end{cases}$$

chúng ta có vô số lời giải không?

Định thức của hệ này là $\Delta = 2a^3 - a^2 - 4a - 1$ và chúng ta không có công thức cho lời giải của phương trình $2a^3 - a^2 - 4a - 1 = 0$ *. Vì vậy, điều quan trọng là phải sử dụng toàn bộ định lý chính. Hệ thống không chắc chắn khi và chỉ khi $\Delta = \Delta_x = \Delta_y = 0$, nhưng không phải tất cả các hệ số của ẩn số đều bằng 0 hoặc tất cả các hệ số của hệ thống đều bằng 0. Tuy nhiên, các hệ số của $y$ không thể đồng thời trở thành 0, vì vậy vẫn chỉ xét trường hợp đầu tiên.

*) Đúng, bạn có thể nhận thấy rằng phương trình này có nghiệm $a = -1$. Biết một nghiệm của phương trình bậc ba, chúng ta có thể phân tách vế trái của phương trình thành thừa số tuyến tính (loại $x - x_0$, trong đó $x_0$ là nghiệm được tìm thấy) và một đa thức bậc hai, mà chúng ta biết cách tìm các nghiệm của nó. Bằng cách tìm nghiệm của phương trình theo cách này, chúng ta có thể giải các hệ thu được. Tuy nhiên, chúng tôi sẽ cung cấp đơn giản hơn lời giải bài toán.

chúng tôi có

$$\Delta_x = \begin{cases} a^2 - 2 & a + 1 \\ 2a + 1 & 2a \end{cases} = 2a^3 - 2a^2 - 7a - 1.$$

Nếu các phương trình $\Delta = 0$ và $\Delta_x = 0$ có một nghiệm chung $a_0$, thì trừ số thứ hai từ phương trình đầu tiên, chúng ta nhận được $a_0^2 + 3a_0 = 0$, do đó $a_0$ là 0 hoặc -3, nhưng cả hai số này đều không phải là nghiệm của phương trình $\Delta = 0$, vì vậy chúng ta gặp mâu thuẫn.

Do đó, phương trình $\Delta = 0$ và $\Delta_x = 0$ không có nghiệm chung và do đó hệ này không thể xác định được.

Đáp số: với không $a$ thì hệ có vô số lời giải.

Bây giờ hãy xem xét một số bài toán, các điều kiện của chúng không trùng với hệ phương trình.

Bài toán 4. Chứng minh rằng nếu phương trình

$$ax^2 + bx + c = 0$$

và $px^2 + qx + r = 0$ có gốc chung thì $(ar - cp)^2 = (aq - bp) (br - cq)$.

Giả sử các phương trình này có nghiệm chung $x_0$. Khi đó hệ phương trình

$$\begin{cases} au + bv = -c, \\ pu + qv = -r \end{cases}$$

có lời giải $u = x_0^2, v = x_0$, và đẳng thức cần chứng minh có dạng $\Delta_v^2 = \Delta \cdot \Delta_u$. Nếu định thức $\Delta$ của hệ (1) khác 0, thì chúng ta sửa Cramer và tìm lời giải duy nhất:

$$x_0^2 = \frac{\Delta_u}{\Delta}, \quad x_0 = \frac{\Delta_v}{\Delta}.$$

Do đó $\frac{\Delta_u}{\Delta} = \frac{\Delta_v^2}{\Delta^2}$, do đó $\Delta_v^2 = \Delta \cdot \Delta_u$, đó là điều cần chứng minh.

Nếu $\Delta = 0$, thì hệ (1), không nhất quán, là không xác định, và do đó, trong đó $\Delta_x = \Delta_y = 0$, tức là đẳng thức đang được chứng minh lại được thỏa mãn.

Những người muốn có thể thử chứng minh đẳng thức cần thiết của vô thời hạn

⟦folio 67⟧

và so sánh lời giải của bạn với cái đã cho.

Bài 5. Trong điều kiện nào có thể kiểm tra đồ thị parabol của một tam giác vuông đi qua ba điểm có các hoành độ khác nhau theo từng cặp?

Những điểm này nằm trên đồ thị của hàm $y = ax^2 + bx + c$ khi và chỉ khi hệ phương trình nhất quán

$$\begin{cases} ax_1^2 + bx_1 + c = y_1, \\ ax_2^2 + bx_2 + c = y_2, \\ ax_3^2 + bx_3 + c = y_3 \end{cases}$$

với ẩn số $a, b, c$ và tham số $x_i, y_i$ ($i = 1, 2, 3$).

Hệ thống (2) có ba ẩn số và do đó lý thuyết của chúng tôi không thể áp dụng trực tiếp cho nó. Tuy nhiên, loại trừ $c$ chưa biết khỏi hệ thống này, chúng ta thu được một hệ thống có hai ẩn số:

$$\begin{cases} a(x_1^2 - x_2^2) + b(x_1 - x_2) = \\ a(x_1^2 - x_3^2) + b(x_1 - x_3) = \end{cases}$$

Nếu hệ (3) nhất quán thì rõ ràng hệ (2) sẽ nhất quán (điều ngược lại cũng đúng).

Định thức của hệ (3) dễ dàng tính được:

$$\Delta = \begin{cases} x_1^2 - x_2^2 & x_1 - x_2 \\ x_1^2 - x_3^2 & x_1 - x_3 \end{cases} = (x_1 - x_2)(x_1 - x_3)(x_2 - x_3).$$

Các số $x_1, x_2, x_3$ đều khác nhau, do đó, $\Delta \neq 0$, tức là hệ (3) và cùng với nó là hệ (2), có một lời giải duy nhất. Do đó, đồ thị của hàm có dạng $y = ax^2 + bx + c$ luôn đi qua ba điểm có các hoành độ khác nhau theo từng cặp.

Tuy nhiên, để hàm số này là đồ thị của tam giác vuông thì phải có $a \neq 0$, tức là trong hệ (3)

$$\Delta_a = \begin{cases} y_1 - y_2 & x_1 - x_2 \\ y_1 - y_3 & x_1 - x_3 \end{cases} \neq 0.$$

Do đó, trong quá trình lời giải chúng ta thu được các phát biểu sau: nếu ba điểm có các hoành độ phân biệt theo cặp thì

$$\begin{cases} y_1 - y_2 & x_1 - x_2 \\ y_1 - y_3 & x_1 - x_3 \end{cases} = 0$$

chúng nằm trên cùng một đường thẳng;

$$\begin{cases} y_1 - y_2 & x_1 - x_2 \\ y_1 - y_3 & x_1 - x_3 \end{cases} \neq 0$$

chúng nằm trên cùng một parabol.

Ngoài ra, thông qua ba điểm bất kỳ có các hoành độ riêng biệt từng cặp không nằm trên cùng một đường thẳng, người ta có thể kiểm tra parabol duy nhất $y = ax^2 + bx + c$.

Nhấn mạnh

1. Liệu một hệ gồm hai phương trình tuyến tính với hai ẩn số có thể bằng nhau lời giải không?

2. Sự khác biệt giữa nghiệm của phương trình $x = 1$ và nghiệm của hệ là gì

$$\begin{cases} x + 0y = 1, \\ x + 0y = 1 \end{cases}$$

3. (MSU, Binofak, 1969). Tìm tất cả các giá trị của $a$ mà hệ phương trình

$$\begin{cases} 2x + (9a^2 - 2)y = 3a, \\ x + y = 1 \end{cases}$$

không có lời giải.

4. (MSU, Khoa Địa lý, 1970). Tại giá trị nào của tham số $a$ thì hệ phương trình

$$\begin{cases} 2x + ay = a + 2, \\ (a + 1)x + 2ay = 2a + 4 \end{cases}$$

có vô số lời giải?

5. (MSU, Binofak, 1970). Các số $a$ và $b$ sao cho hệ phương trình

$$\begin{cases} a^2x - ay = 1 - a, \\ bx + (3 - 2b)y = 3 + a \end{cases}$$

có một lời giải $x = 1, y = 1$. Tìm $a$ và $b$.

6. Chúng ta có thể biểu diễn những số hoàn chỉnh nào dưới dạng $\frac{c + di}{c - di}$?

7. Giải hệ phương trình

$$\begin{cases} 2x^3y = 5, \\ 3x^8y = 12 \end{cases}$$

8. Trong những điều kiện nào thì các điểm $(x_1, y_1)$ và $(x_2, y_2)$ nằm trên đồ thị có dạng parabol $y = x^2 + px + q$?

9. Giải hệ phương trình

$$\begin{cases} ax + y + z = 1, \\ x + ay + z = 1, \\ x + y + az = 1 \end{cases}$$

10. Đối với $a$ thì các điểm có tọa độ $(-1, -3 - a), (3, 3a + 1), (4 - a, 2a + 2)$ nằm trên cùng một đường thẳng?
