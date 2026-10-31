---
id: 1989-2-zilberman-statika-bc6cc913
issue: kvant_1989_2
year: 1989
number: "2"
title: Tĩnh học
authors:
  - Зильберман А. Р.
rubric: praktikum-abiturienta
rubric_sub: Практикум абитуриента
page_first: 64
page_last: 67
page_labels: 62, 63, 65
tag: WM53
lang: vi
source: kvant_digital
extraction: vision
content_sha256: 9001dd24fd3efd993df2fbdaaae4b03db208e10fa8a89ed0e2af018a23b8a0a0
prompt_sha256: draft-1
translated_from: content/ru/1989/02/articles/17_zilberman-statika-bc6cc913.md
source_content_sha256: d9a1de04010ffa06a935c5ec24551b00092d6b33719f7001f71cfed8c0a882c5
translation_model: draft
translation_run: vi-draft-2026-10-31
translation_quality: draft
---

⟦folio 62⟧

Stapika

A. R. ZILBERMAN

Trong các bài toán của phần này, các điều kiện cân bằng của vật thể được nghiên cứu. Thông thường, những điều kiện này được sử dụng để tìm lực trong hệ đang nghiên cứu.

Chúng ta hãy nhớ lại các điều kiện để cân bằng của một vật: tổng các lực tác dụng lên vật từ các vật khác phải bằng 0 và tổng mô men của các lực này đối với một điểm bất kỳ cũng phải bằng 0.

Ở đây câu hỏi có thể được đặt ra ngay lập tức: liệu chúng ta có đạt được nhiều điểm cân bằng như mong muốn hay không bằng cách đánh đồng tổng mômen lực tương đối với các điểm khác nhau bằng 0, tức là liệu chúng ta sẽ không nhận được nhiều đẳng thức hơn số chưa biết? Hóa ra là không có cơ sở cho vô cực - đối với một hệ 丝, tổng của nó bằng 0 (và chúng ta lại giải quyết vấn đề này một lần nữa), tổng mômen bằng nhau đối với bất kỳ điểm nào, vì vậy sẽ không có phương trình “phụ”.*)

Đầu tiên, chúng ta hãy xem xét một bài toán rất đơn giản.

Bài toán 1. Một thanh thẳng có chiều dài $L=1$ m và khối lượng $M=200$ kg được treo ở hai đầu trên một lực căng thẳng đứng ba (hình 1). Tìm lực căng của chúng nếu trọng tâm của dầm ở khoảng cách $L_1=0,3$ m tính từ một đầu của nó.

Rõ ràng là nếu các dây cáp còn nguyên vẹn thì chùm tia ở trạng thái cân bằng. Hãy viết phương trình lực:

$$T_1 + T_2 - Mg = 0.$$ (1)

Có hai đại lượng chưa biết - $T_1$ và $T_2$. Điều này có nghĩa là chúng ta cần thêm một phương trình nữa. Chúng ta có được nó bằng cách viết phương trình cho khoảnh khắc丝. Khoảnh khắc có thể liên quan đến bất kỳ điểm nào - chúng ta chọn điểm này sao cho phương trình của hệ phương trình.

*) Bạn có thể đọc thêm về điều này trong bài “Lực tác dụng ngang nhau - làm sao tìm được?”, đăng trên tạp chí số 11-12 năm ngoái.

⟦folio 63⟧

Sẽ thuận tiện nếu coi nó là sự tiếp nối đường hành động của một (và nếu có thể, thì một số) lực lượng chưa xác định. Trong trường hợp của chúng tôi, chúng tôi có thể lấy một trong các đầu của chùm tia - sang phải, trái:
$$MgL_1 - T_1L = 0.$$

Giải hệ phương trình (1) và (2), ta thu được
$$T_1 = Mg(L - L_1)/L = 1,4 \cdot 10^3\text{H},$$
$$T_2 = MgL_1/L = 0,6 \cdot 10^3\text{H}.$$

Xin lưu ý: thay vì phương trình (1), người ta có thể lấy phương trình mô men đối với đầu kia của chùm tia thì có thể viết ngay đáp số. Hãy cố gắng tự mình chứng minh khả năng lựa chọn phương trình như vậy.

Và một lưu ý nữa: nếu dây cáp chỉ giãn ra một chút thì trên thực tế, chùm tia sẽ vẫn nằm ngang và do đó, lời giải của chúng ta sẽ vẫn có tác dụng. Nếu vậy, thì nhìn chung chúng ta có quyền tránh kéo căng các dây cáp (nghĩa là chúng ta có thể coi chúng là không thể kéo dài được). Tuy nhiên, điều xảy ra là ngay cả những biến dạng rất nhỏ cũng có thể dẫn đến sự phân bố lại lực đáng kể trong hệ, khi đó không thể tránh khỏi những biến dạng đó. Những trường hợp như vậy không khó nhận biết; chúng ta sẽ xem xét một ví dụ về hệ thống như vậy sau.

Bài 2. Phần nghiêng của cửa sổ (đoạn) có thể xoay quanh trục hoành O (hình 2). Mảnh vỡ được bao phủ và giữ theo chiều ngang bằng một sợi dây căng, tạo một góc a với phương thẳng đứng. Điểm bám của dây cách trục một khoảng L, trọng tâm của dây cách trục một khoảng L₁. Khối lượng của pharagm là M. Tìm độ lớn và hướng của phản lực trong trục.

Cách dễ nhất là tìm hình chiếu của các phản lực Q₁ và Q₂. Các đẳng thức sau đây đúng với chúng:
$$Q_1 - Mg = 0, \quad Q_2 - T = 0.$$
Vẫn còn phải tìm cáp T. Chúng ta hãy viết phương trình mô men quanh trục O:
$$TL\cos\alpha - MgL_1\sin\alpha = 0,$$
Ở đâu
$$T = Mg \frac{L_1tg\alpha}{L}.$$
Sau đó
$$Q_1 = Mg, \quad Q_2 = Mg \frac{L_1tg\alpha}{L}.$$
Trên thực tế, chúng tôi đã quyết định bài toán - chúng tôi đã tìm thấy dự án của lực mong muốn Q. Nhưng hướng của nó có thể được chỉ ra ngay từ đầu: nó phải “nhìn” vào điểm giao nhau của đường tác dụng của các lực $\vec{T}$ và $\vec{Mg}$ (hình 3). Trên thực tế, liên quan đến điểm này, cả lực $\vec{T}$ lẫn lực $\vec{Mg}$ đều không tạo ra mômen, có nghĩa là lực còn lại $\vec{Q}$, nếu bằng nhau, sẽ hướng vào đó.

Xin lưu ý rằng phản lực trên trục không hướng dọc theo pharagm. Điều này là do thực tế là phragm có trọng lượng. Đối với một thanh không trọng lượng có bản lề ở hai đầu, các lực ở các trục sẽ hướng dọc theo thanh (nếu không tác dụng thêm lực nào lên thanh, ngoại trừ các lực ở các trục).

Bài 3. Một tam giác có các góc 30° và 60° được làm bằng các thanh cứng nhẹ được gắn chặt ở hai đầu bằng bản lề. Một vật có khối lượng M=2 kg được treo lơ lửng như hình hình 4. Tìm biến dạng của thanh. Diện tích mặt cắt ngang của thanh S=0,5 cm², mô đun đàn hồi E=5 \cdot 10^6 \text{H/m}^2. Chiều dài thanh lớn L=0,2 m. Tránh uốn cong các thanh.

⟦folio 65⟧

Phương trình lực và mô men:
$$T_1 + T_2 + T_3 = Mg,$$
$$Mg L_1 - T_2 \frac{L}{2} - T_3 L = 0.$$

Giả sử các biến dạng là đàn hồi, ta viết:
$$T_1: T_2: T_3 = \Delta l_1: \Delta l_2: \Delta l_3.$$

Phương trình cuối cùng bổ sung cho các điều kiện cân bằng, rõ ràng là không đủ cho lời giải này bài toán (các hệ thống như vậy được gọi là tĩnh không xác định, nghĩa là cần có các phương trình bổ sung). Bây giờ chúng ta có một hệ thống:
$$\begin{cases}
T_1 + T_2 + T_3 = Mg, \\
T_2 + 2T_3 = 2Mg \frac{L}{L}, \\
2T_2 = T_1 + T_3.
\end{cases}$$

Từ đây là
$$T_1 = Mg \left( \frac{5}{6} - \frac{L_1}{L} \right) = \frac{8}{15} Mg,$$
$$T_2 = \frac{1}{3} Mg,$$
$$T_3 = Mg \left( \frac{L_1}{L} - \frac{1}{6} \right) = \frac{2}{15} Mg.$$

Đây là ví dụ đã thảo luận ở trên: nếu các dây cáp không thể co giãn được thì chỉ cần kéo dây ở giữa lâu hơn một chút là đủ - và toàn bộ tải trọng sẽ đổ lên các dây bên ngoài, và nếu nó ngắn hơn một chút thì tải trọng ở cáp bên phải sẽ biến mất. Rõ ràng là trong bài toán này không thể bỏ qua độ đàn hồi của dây cáp. Nhưng ngay cả khi chúng ta quên nó, bản thân bài toán sẽ khiến chúng ta thiếu phương trình.

Các phương trình tĩnh học rất thuận tiện; có lẽ đó là lý do tại sao tỏi tây của họ sẽ được sử dụng ngay cả khi không có sự cân bằng (có nghĩa là không thể sử dụng được). Ví dụ: bài toán được biết đến rộng rãi về độ lớn truyền trong một vòng tròn và cần phải tìm góc mà độ lớn của khoảng cách

vợ phải cúi xuống để không bị ngã (điều này bài toán có trong nhiều vấn đề, kể cả trong vấn đề ở trường - trong ấn bản năm 1983 là số 279). Đáp số đưa ra ở đó tất nhiên là đúng nhưng giải thế nào cho đúng?

Lý do sau đây thường được sử dụng là lời giải. Phản lực, gồm các thành phần là phản lực bình thường $N$ và lực ma sát $F_{tr}$, phải hướng dọc theo cơ thể sao cho đi qua trọng tâm, nếu không độ lớn sẽ bị mất đi. Rõ ràng là lập luận này chỉ đơn giản là sự phát biểu lại phương trình mô men đối với khối tâm. Nhưng không có sự cân bằng, tổng lực không bằng 0, tại sao chúng ta lại có phương trình mô men?

Hóa ra là trong những trường hợp khi vật đứng yên so với một hệ quy chiếu chuyển động với gia tốc (như trong trường hợp này), phương trình mô men có thể được viết, nhưng chỉ liên quan đến một điểm duy nhất - tâm khối lượng. Cơ sở lý luận cho “công thức nấu ăn lời giải” này vượt ra ngoài phạm vi chương trình giảng dạy ở trường (nhưng có liên quan đến phần “Hệ quy chiếu phi quán tính”). Chúng ta hãy tha thứ cho tác giả của câu đố trong đó câu đố này và câu đố tương tự bài toán được đặt vì một mong muốn vô tội - bây giờ chúng ta biết phải làm gì trong những trường hợp như vậy.

Bài tập
1. Hệ thống cứng bao gồm các thanh ánh sáng giống hệt nhau được gắn chặt bằng bản lề (hình 9). Tìm lực căng ở các thanh 1, 2, 3 và 4. Các thanh này co lại hay to ra?
2. Thang gồm có hai nửa, được gắn chặt ở phía trên bằng bản lề (hình 10). Khối lượng của một nửa là $M_1$, nửa còn lại là $M_2$. Thang được mở một góc $\alpha$ và đặt trên sàn, đồng thời để ngăn nó “lò ra xung quanh”, hai đầu dưới của nửa thang được buộc lại với nhau bằng vít. Tìm lực căng của sợi dây. Sàn nhà mịn màng.
