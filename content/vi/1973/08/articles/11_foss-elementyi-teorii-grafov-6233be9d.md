---
id: 1973-8-foss-elementyi-teorii-grafov-6233be9d
issue: kvant_1973_8
year: 1973
number: "8"
title: Các yếu tố của lý thuyết đồ thị
authors:
  - Фосс В.
rubric: raznoe
page_first: 57
page_last: 61
page_labels: 55-59
tag: OOGN
lang: vi
source: kvant_digital
extraction: vision
content_sha256: 22b193f6a6121fa61951fa546b4145dece23c48671eb2410ab916b50b8df4a9b
prompt_sha256: draft-1
translated_from: content/ru/1973/08/articles/11_foss-elementyi-teorii-grafov-6233be9d.md
source_content_sha256: f899575134e8e5702765ac3ef7546db3fba20898b5bd32936fd927d1bdda5bf2
translation_model: draft
translation_run: vi-draft-2026-10-31
translation_quality: draft
---

⟦folio 55⟧

Các yếu tố của lý thuyết đồ thị

Nền tảng của ngành toán học gọi là lý thuyết đồ thị được đặt trong một trong những tác phẩm của Leonhard Euler, xuất bản năm 1736, nhưng lý thuyết đồ thị chỉ trở nên đặc biệt quan trọng trong những thập kỷ gần đây *).

"đồ thị" là gì?

Trước khi định nghĩa khái niệm này, chúng ta hãy xem xét một vài ví dụ.

Ví dụ 1. Đội 6 tham gia thi đấu bóng chuyền: $M_1$, $M_2$, $M_3$, $M_4$, $M_5$, $M_6$. Mỗi người trong số họ gặp nhau, kết quả của các trận đấu được thể hiện trong bảng.

| $M_i$ | Đội đã thắng | Đội đã thua |
| :--- | :--- | :--- |
| $M_1$ | $M_2$, $M_3$, $M_4$ | $M_5$, $M_6$ |
| $M_2$ | $M_3$, $M_4$, $M_5$, $M_6$ | $M_1$ |
| $M_3$ | $M_4$, $M_5$, $M_6$ | $M_1$, $M_2$ |
| $M_4$ | — | $M_1$, $M_2$, $M_3$, $M_5$, $M_6$ |
| $M_5$ | $M_1$, $M_4$, $M_6$ | $M_2$, $M_3$ |
| $M_6$ | $M_1$, $M_4$ | $M_2$, $M_3$, $M_5$ |

Trong Hình 1, mỗi lệnh $M_i$ được chỉ định bởi lũy thừa tương ứng

W. Voß. "Atz der Graphentheorie". "Alpha" số 6, 1972 và số 1, 1973. A.Ya dịch và xử lý. Halamizer.

*) Số này đăng một bài khác về đồ thị (xem trang 49).

⟦folio 56⟧

mochiki. Tương tự như vậy, công thức cấu trúc của benzen (Hình 4a) có thể được biểu diễn bằng sơ đồ gồm các đường và các thùy (Hình 46).

Ví dụ 4. Việc kết nối các đỉnh và cạnh của đa giác thông thường có thể được mô tả dễ dàng bằng sơ đồ bao gồm các thùy và đường thẳng (Hình 5).

Trong những ví dụ này, sơ đồ được tạo thành từ các điểm và đường nối chúng là đồ thị. Bây giờ chúng ta hãy đưa ra định nghĩa về khái niệm “đồ thị”.

Định nghĩa 1. Chúng ta nói rằng một biểu đồ được đưa ra nếu dữ liệu:

1) một số tập hữu hạn X có các phần tử được biểu diễn bằng điểm; những yếu tố này có thể biểu thị con người, đồ vật, sự kiện, trạng thái, v.v.;

2) một số tập U gồm các cặp có thứ tự hoặc không có thứ tự (a, b), với a∈X, b∈X; mỗi cặp tương tự tương ứng với sơ đồ các đường (kết nối) kết nối các điểm a và b (nếu cặp được sắp xếp theo thứ tự thì hướng của kết nối được biểu thị bằng một mũi tên).

Trong trường hợp này, điểm a và b có thể có nhiều kết nối. Nếu đối với một cặp (a, b) nhất định có r(r > 1) kết nối như vậy thì chúng được phân biệt bằng cách sử dụng các chỉ số, ví dụ: (a, b)₁, (a, b)₂, ..., (a, b)ₙ.

Các tập X và U xác định đồ thị G = [X, U]. Một đồ thị được gọi là có hướng nếu các phần tử của tập U là các cặp điểm có thứ tự (xem Hình 1) và ngược lại là vô hướng (xem Hình 2, 3, 4).

Các phần tử của tập X được gọi là các đỉnh của đồ thị, các phần tử của tập U được gọi là các cạnh hoặc các cạnh của đồ thị G.

Điểm a và b được gọi là điểm cuối của cạnh (a, b) hoặc cạnh (a, b)ᵢ.

Cần nhấn mạnh rằng các hình vẽ thuộc các loại khác nhau có thể biểu diễn cùng một đồ thị nếu cứ hai điểm tương ứng được nối bằng cùng một số cạnh (hoặc có hướng bằng nhau).

⟦folio 57⟧

Bạn). Hình 6 hiển thị các hình ảnh khác nhau của cùng một biểu đồ.

Tiếp theo, cần xác định thêm hai khái niệm quan trọng hơn và đưa ra một số nhận xét chung. Sau đó, có thể xây dựng và chứng minh một định lý đơn giản nhưng rất quan trọng (Định lý 1).

Định nghĩa 2. Hai đỉnh được gọi là liên thông nếu chúng được nối bởi một cạnh. Một đỉnh được gọi là tiếp giáp với một cạnh nếu nó đóng vai trò là điểm cuối của cạnh đó.

Định nghĩa 3. Nếu một đỉnh cho trước liên tiếp với đúng r cạnh trong G thì r được gọi là liên của đỉnh đã cho trong G.

Vì vậy, ví dụ, trong Hình 2, đỉnh A có kết nối 4, đỉnh D có kết nối 2 và các đỉnh còn lại có kết nối 1.

Trong phần tiếp theo, khi dùng biểu đồ, chúng ta sẽ hiểu là đồ thị vô hướng; Khi xem xét đồ thị có hướng, chúng tôi sẽ nêu rõ điều này mỗi lần.

Chúng tôi không xem xét thêm các cạnh của dạng (a, a), nghĩa là chúng tôi loại trừ *vòng* khỏi việc xem xét (xem Hình 7a).

Ngược lại, có những đỉnh trong đồ thị không liên quan đến bất kỳ cạnh nào. Các đỉnh như vậy được gọi là cô lập.

Chúng ta sẽ chỉ xem xét các đồ thị hữu hạn chứa một tập hữu hạn các đỉnh và một tập hữu hạn các cạnh.

Định nghĩa 4. Đồ thị G được gọi là đơn nếu nó không chứa các cạnh kép, nghĩa là hai đỉnh bất kỳ trong G được nối với nhau nhiều nhất một cạnh (có hai cạnh trong Hình 76).

Bây giờ hãy thử giải một số bài toán.

Bài 1. Trên một mặt phẳng cho n đường tròn vẽ các số 1, 2, . . . , N. Đồ thị G = [X, U] được xác định như sau: X = {1, 2, . . . , n} và (i, j)∈U khi và chỉ khi đường tròn thứ i và thứ j có ít nhất một điểm chung. Xây dựng đồ thị G cho các đường tròn thứ chín như trong Hình 8.

Nhiệm vụ 2. Đồ thị G được gọi là đầy đủ nếu mỗi hai đỉnh được nối bởi một và chỉ một cạnh (Hình 9 thể hiện đồ thị n hoàn chỉnh với n=3, 4 và 5). Một đồ thị n đầy đủ có bao nhiêu cạnh?

Bài 3. Hình 10a và 106 có thể hiện cùng một đồ thị không? Hình 10c và 10d?

Nhiệm vụ 4. Xác định tính liên thông của các đỉnh của từng đồ thị trên Hình 5.

Một số định lý và ứng dụng của chúng

Định lý 1. Cho |X| = n — số đỉnh, |U| — số cạnh u

⟦folio 58⟧

$s_1, s_2, \dots, s_n$ — kết nối của các đỉnh của đồ thị $G = [X, U]$. Sau đó
$$\sum_{i=1}^{n} s_i = 2 |U|,$$
Có lẽ tổng số kết nối của tất cả các đỉnh của đồ thị $G$ gấp đôi số cạnh của nó.

Bằng chứng. Hãy thay thế mỗi cạnh bằng hai nửa (Hình 11). Khi đó mỗi nửa cạnh sẽ có một và chỉ một đỉnh tới. Nếu một đỉnh $a_i \in X$ có kết nối $s_i$, thì nó ngẫu nhiên với $s_i$ một nửa các cạnh; Điều này có nghĩa là tổng $\sum_{i=1}^{n} s_i$ bằng số tất cả các nửa hoặc bằng nhau, gấp đôi số cạnh.

Giữa các biểu đồ được hiển thị trong Hình 2 và Hình 36, có thể thấy một điểm khác biệt cơ bản. Trong đồ thị ở Hình 36, mỗi đỉnh được kết nối (bằng các cạnh) với nhau; trong biểu đồ ở Hình 2, các đỉnh $E$ và $F$ không được kết nối với các đỉnh $A$, $B$, $C$, $D$. Để làm rõ sự khác biệt này

$$\text{Pic. 12.}$$

Để làm được điều đó, cần phải đưa ra các định nghĩa 5-9.

Định nghĩa 5. $(a_1, a_2) \times (a_2, a_3)(a_3, a_4) \dots (a_{n-1}, a_n)$ được gọi là dãy các cạnh. Ở đây, $a_i$ biểu thị các đỉnh và $(a_i, a_j)$ biểu thị các cạnh. Một chuỗi các cạnh được gọi là đóng nếu $a_n = a_1$, nếu không thì nó được gọi là mở.

Định nghĩa 6. Dãy các cạnh trong đó mỗi cạnh của đồ thị $G$ xuất hiện nhiều nhất một lần được gọi là số nguyên *).

Hơn thế nữa. Các đỉnh giống nhau có thể xuất hiện nhiều lần trong một chuỗi.

Định nghĩa 7. Một số nguyên mở mà mỗi đỉnh xuất hiện nhiều nhất một lần được gọi là rỗng.

Định nghĩa 8. Một tổng thể đóng trong đó mỗi đỉnh xuất hiện nhiều nhất một lần được gọi là col **).

Vì vậy, ví dụ, trong biểu đồ ở Hình 12
$$(a_1, a_2)(a_2, a_3)(a_3, a_8)(a_8, a_9) \times (a_9, a_3)(a_3, a_7)(a_7, a_4)(a_4, a_6) \times (a_6, a_5)(a_5, a_4)(a_4, a_7)(a_7, a_3) \times (a_3, a_9)(a_9, a_8)(a_8, a_3)(a_3, a_2)$$
— một chuỗi các cạnh không trống;
$$(a_1, a_2)(a_2, a_3)(a_3, a_8)(a_8, a_9) \times (a_9, a_3)(a_3, a_7)$$ — chuỗi các cạnh;
$$(a_3, a_7)(a_7, a_4)(a_4, a_3)$$ - kolcho;
$$(a_1, a_2)(a_2, a_3)(a_3, a_7)(a_7, a_4) \times (a_4, a_5)$$ là đường nối đỉnh $a_1$ với đỉnh $a_5$.

Định nghĩa 9. Đồ thị $G$ trong đó cứ hai đỉnh $a_i$ và $a_j$ được nối với nhau bởi ít nhất một đường đi được gọi là liên thông.

*) Theo định nghĩa 5, một số nguyên có thể mở hoặc đóng.

**) Một colcho tốt hơn một trong các hoán vị tuần hoàn khác của các cạnh (ví dụ: (1, 2) (2, 3) (3, 1) và (2, 3) (3, 1) (1, 2)) sẽ được coi là giống hệt nhau. (Прим. перев.)

⟦folio 59⟧

Một biểu đồ bị ngắt kết nối bao gồm ít nhất hai thành phần được kết nối.

Vì vậy, ví dụ, các đồ thị ở Hình 13 c, d, e, f không liên kết với nhau và lần lượt gồm 2, 2, 4, 3 thành phần.

Có lẽ sự phong phú của các định nghĩa và ghi chú đã khiến người đọc cảm thấy nhàm chán. Thật không may, chúng hoàn toàn cần thiết để hiểu sâu hơn.

Câu nói sau đây có vẻ xa lạ với bạn không:

Số người, trong số đó có số bạn bè là số lẻ là số chẵn?

Sử dụng định lý mà chúng ta đang tiến hành, không khó để chứng minh nhận định này.

Định lý 2. Trong mọi liên kết của đồ thị G, số đỉnh có liên kết lẻ là số chẵn.

Bằng chứng. Chúng ta hãy biểu thị tổng khả năng kết nối của các đỉnh “lẻ” (nghĩa là tổng các số hạng x lẻ trong công thức (*)) bằng Σ₁ và tổng khả năng kết nối của các đỉnh “chẵn” (nghĩa là tổng các số hạng chẵn trong (*)) bằng Σ₂. Khi đó theo Định lý 1

$$\Sigma_1 + \Sigma_2 = \sum_{i=1}^{|X|} s_i = 2 |U|,$$

Ở đâu

$$\Sigma_1 = 2 |U| - \Sigma_2. \quad (*)$$

Số 2 |U| và Σ₂, và do đó hiệu của chúng, nằm ở vế phải của đẳng thức (**), là số chẵn và sau đó ở vế trái (tổng các số hạng lẻ là Σ₁) là số chẵn. Tiếp theo, thật dễ dàng để chứng minh (bằng phản chứng) rằng số số hạng (lẻ!) trong tổng này là số chẵn. Định lý đã được chứng minh.

Chúng tôi để người đọc giải quyết bài toán sau đây.

Nhiệm vụ 5. Bảy người bạn đang đi nghỉ đã đồng ý rằng mỗi người sẽ gửi bưu thiếp cho ba người khác.

Phải chăng mỗi người trong số họ sẽ nhận được bưu thiếp từ chính những người bạn mà chính họ viết thư?

Bài 6. Có đồ thị nào có 6 đỉnh có khả năng kết nối là 2, 3, 3, 4, 4, 4 không?

Bài 7. Có đồ thị đơn giản (chứa nhiều hơn một đỉnh) sao cho không có hai nút nào có cùng kết nối không?

Bài toán 8. Cho G là một đồ thị đơn (hữu hạn), mỗi đỉnh của nó có một kết nối g. Chứng minh rằng 2 |U| = g |X|.

Trong «Kvant» Số 3, 1973 trên trang. 4 có lỗi đánh máy. Câu cuối cùng ở cột bên trái sẽ như thế này: Đây không quá M lần

$$M = \lg e = 0,43429$$

tốc độ thay đổi tương đối của y với sự thay đổi của t:

$$\frac{1}{y} \lim_{\Delta t \to 0} \frac{\Delta y}{\Delta t} = \frac{y'}{y} = \ln \frac{\lg a}{M}.$$
