---
id: 1988-8-vinnichenko-prostyie-chisla-matematicheskaya-statistika-i-evm-0e4ebf53
issue: kvant_1988_8
year: 1988
number: "8"
title: Số nguyên tố, thống kê toán học và... Máy tính
authors:
  - Винниченко А. П.
rubric: raznoe
page_first: 21
page_last: 24
page_labels: 19-22
tag: S34Z
lang: vi
source: kvant_digital
extraction: vision
content_sha256: 11a85779efed87d3ebd4d3fa5aa8a26ec387d0fcaf75d63b2fbf7e2a3decb25b
prompt_sha256: draft-1
translated_from: content/ru/1988/08/articles/05_vinnichenko-prostyie-chisla-matematicheskaya-statistika-i-evm-0e4ebf53.md
source_content_sha256: 1a9c2154c72be15896f12359d630a592613326660ff0e75f74bf11e6cdc7e84d
translation_model: draft
translation_run: vi-draft-2026-10-31
translation_quality: draft
---

⟦folio 19⟧

SỐ THỦ,
TOÁN HỌC
THỐNG KÊ VÀ... MÁY TÍNH

Ứng viên Khoa học Vật lý và Toán học
A. P. VINNICHENKO

Biên tập. Trong những năm gần đây, với sự phát triển về sức mạnh và tính sẵn có của máy tính, thí nghiệm, cho đến gần đây vẫn là lĩnh vực gần như không thể phân chia của vật lý, hóa học và các ngành khoa học tự nhiên khác, đã bắt đầu đóng một vai trò ngày càng tăng trong công việc của toán học. Các nhà toán học đã có thể xác định các giả thuyết mới dựa trên kết quả xử lý nhanh của máy tính các mảng khổng lồ. Đôi khi xuất hiện những mô hình gây tổn hại cho các cá nhân có thể đã được phát hiện từ “ngày xưa tốt đẹp”.
Trong phần ghi chú sau, bạn sẽ không tìm thấy một định lý hay bằng chứng nào. Ở đây chúng ta nói về một thí nghiệm về số nguyên tố, cho phép chúng ta đưa ra một đề xuất thú vị về sự phân bố của chúng. Có lẽ một trong những độc giả của chúng tôi sẽ có thể chứng minh hoặc bác bỏ nó.
Ngay cả người Hy Lạp cổ đại cũng nhìn thấy trong số nhiều số nguyên dương “các nguyên tử không thể phân chia”, tức là những con số không thể phân tách thành các thừa số nhỏ hơn và gọi chúng là “đơn giản”. Một số nguyên tố chỉ chia hết cho một và chính nó, còn tất cả các số khác đều được lấy từ các phần tử kirichki của thế giới này

chất độc

2*

19

⟦folio 20⟧

số bằng phép nhân. Sự bắt đầu của một dãy số nguyên tố là 2, 3, 5, 7, nhưng không có điểm kết thúc - số đơn giản nhất không tồn tại. Chúng tôi sẽ coi số nguyên tố chẵn duy nhất 2 là một "lỗi tự nhiên" và xem xét chuỗi bắt đầu từ 3. Hãy để chuỗi này tuân theo quy trình phân tích sự khác biệt*) - chúng tôi sẽ là sự khác biệt của hai số hạng lân cận:

$$\begin{align*}
3, & 5, 7, 11, 13, 17, 19, 23, 29, 31, 37 \\
2 & 2 4 2 4 2 4 2 4 2 6
\end{align*}$$

Sự khác biệt được lặp lại - có nhiều số hai, có số bốn và số sáu cũng xuất hiện. Nó giống như thể các điểm đang tung ra trên một con xúc xắc: hai, hai, bốn, lại hai... Thật là một ý tưởng dị giáo khi coi chuỗi xác định chặt chẽ này là kết quả đo của một số biến ngẫu nhiên và cố gắng xử lý chúng bằng phương pháp thống kê toán học.

Chúng ta lấy các số nguyên tố không vượt quá $N$ để xử lý; trong ví dụ (1) $N=40$. Trước hết, hãy viết theo thứ tự tăng dần tất cả các giá trị quan sát được $x_1=2, x_2=4, \dots$ của “biến ngẫu nhiên” của chúng ta (ví dụ (1) số lượng các giá trị này là $n=3$) và bên dưới nó - tần suất $\omega_1, \omega_2, \dots$ mà chúng xuất hiện (tức là tỷ lệ giữa số lần xuất hiện $x_i$ trên tổng số giá trị được quan sát, đối với chúng ta là 10):

$$\begin{align*}
1 & 4 & 9 & 16 & 25 & 36 \\
3 & 5 & 7 & 9 & 11 & \dots \\
2 & 2 & 2 & 2 & \dots ;
\end{align*}$$

tương ứng, $(x^2)^{n/2}=\text{const.}$

Tiếp theo, chúng tôi sẽ biên soạn một bảng “tần số tích lũy” $v_i=\omega_1+\omega_2+\dots+\omega_i$, tức là dưới mỗi giá trị $x_i$, chúng tôi sẽ viết tổng tần số của tất cả các giá trị không vượt quá $x_i$:

$$\begin{align*}
x_i & 2 & 4 & 6 \\
\omega_i & 0,5 & 0,3 & 0,2
\end{align*}$$

Chúng ta hãy vẽ kết quả của những phép tính này dưới dạng biểu đồ của hàm bước $F_N(x)$ (hình 1), được gọi là hàm phân phối thực nghiệm: $F_N(x)$ bằng tổng của $\omega_i$ trên tất cả $i$ sao cho $x_i \leqslant x$. Mục tiêu của chúng tôi là so sánh các biểu đồ của $F_N(x)$ với các $N$ khác nhau và cố gắng nắm bắt một số khuôn mẫu trong hành vi của chúng đối với $N \to \infty$. Đúng vậy, nếu bạn thực hiện việc này mà không có sự chuẩn bị thích hợp thì sẽ chẳng có điều gì tốt đẹp cả. Thực tế là càng ở xa, các số nguyên tố phổ biến càng nhiều và khoảng cách giữa chúng sẽ càng lớn. Do đó, các đồ thị $F_N$ với mức tăng $N$ sẽ lan sang bên phải. Để bù đắp cho sự tan chảy này, chúng tôi áp dụng cho họ một quy trình quen thuộc với chúng tôi trong tiểu thuyết trinh thám. Khi ghép các bức ảnh với các bức ảnh bằng xenlulo, dù chúng có mô tả cùng một tổng thể hay không, các nhà khoa học pháp y sẽ xác định hoặc giảm bớt chúng sao cho khoảng cách giữa các khung hình trong các bức chân dung thông thường trở nên giống nhau, rồi ghép chúng lại với nhau từng khung hình. Chúng ta sẽ làm điều gì đó tương tự với các hàm phân phối theo kinh nghiệm.

⟦folio 21⟧

Chúng ta hãy tính cho mỗi $N$ giá trị trung bình số học $\bar{x}$ của tất cả các giá trị quan sát được $x_i$, được gọi là giá trị trung bình. Thật dễ dàng để nhận thấy điều đó $\bar{x} = \sum_{i=1}^{n} x_i \omega_i$.

Giá trị này đặc trưng cho sự dịch chuyển của hàm phân phối theo chiều ngang. Số lượng thứ hai chúng ta cần là

$$\sigma_x = \sqrt{\sum_{i=1}^{n} (x_i - \bar{x})^2 \omega_i}$$

- gọi là độ lệch chuẩn. Nó đóng vai trò như thước đo độ phân tán của các giá trị quan sát được so với giá trị trung bình $\bar{x}$— $\sigma_x$ càng nhỏ thì các giá trị $x_i$ càng gần nhau. Trong trường hợp tương tự thám tử của chúng tôi, kích thước $\sigma_x$ tương ứng với kích thước của nhiếp ảnh gia. Hãy để chúng tôi đưa ra các giá trị của $\bar{x}$ và $\sigma_x$ cho các $N$ khác nhau.

| $N$ | 40 | $10^2$ | $10^3$ | $10^4$ | $10^5$ | $10^6$ |
| :--- | :--- | :--- | :--- | :--- | :--- | :--- |
| $\bar{x}$ | 3,40 | 4,10 | 5,98 | 8,12 | 10,42 | 12,73 |
| $\sigma_x$ | 1,56 | 1,84 | 3,54 | 5,86 | 8,02 | 10,28 |

Như người ta mong đợi, cả hai đặc điểm này đều tăng khi tăng $N$, điều này cho thấy đồ thị $F_N$ đang trải rộng. Để tránh việc định vị, chúng tôi di chuyển từng biểu đồ $x$ sang trái và tạo $\sigma_x$ lần cho trục tọa độ. Để thực hiện việc này, chúng ta thay thế các giá trị $x_i$ bằng các giá trị mới $y_i = (x_i - x)/\sigma_x$ và tính toán lại bảng tần số tích lũy:

| $y_i$ | $-0,90$ | $0,38$ | $1,67$ |
| :--- | :--- | :--- | :--- |
| $v_i$ | 0,50 | 0,80 | 1 |

Sử dụng bảng này, chúng ta sẽ vẽ đồ thị hàm phân phối $\bar{F}_N(y)$ của giá trị $y_i$ (hình 2). Dễ dàng nhận thấy giá trị trung bình và độ lệch chuẩn của giá trị $y_i$ đối với tất cả $N$ sẽ bằng 0 và 1. Chúng ta sẽ so sánh các biểu đồ $\bar{F}_N$ này. Tất nhiên, đối với $N$ lớn, công việc này phải được giao cho máy tính. Trong 20 phút làm việc, chúng tôi đã đạt được 300 nghìn thao tác mỗi giây, làm nổi bật các biểu đồ được hiển thị trong hình 3 (cho $N = 10^3$, $10^4$, $10^5$ và $10^6$). Có thực sự trông giống như những biểu đồ bước này đang tiến gần đến biểu đồ phẳng được vẽ bằng màu đen không? Đây là biểu đồ được gọi là phân bố hàm mũ

$$F(y) = \begin{cases} 1 - e^{-y-1} & \text{при } y \geq -1, \\ 0 & \text{при } y < -1 \end{cases}$$

với giá trị trung bình bằng 0 và độ lệch chuẩn đơn vị. Việc tính toán được thực hiện trên máy tính xác nhận giá trị quan trọng của chúng tôi. Liệu có đúng là tại $N \to \infty$ đồ thị của $\bar{F}_N(y)$ có xu hướng $F(y)$ hay không vẫn chưa được biết. Hiện tại đây chỉ là một giả thuyết. Tuy nhiên, giả thuyết được xác nhận cho tập hợp 78.497 số nguyên tố đầu tiên. Và công việc khổng lồ này đã được hoàn thành chỉ trong 20 phút!

Điều thú vị cần lưu ý là sự phân bố tương tự cũng được đưa ra bởi các khoảng giữa các tín hiệu lân cận trong luồng Poisson (xem phần cuối của bài viết “Sự phát sinh phân bố Poisson như thế nào”). Chúng ta có thể chỉ ra điều này bằng cách nhớ lại rằng, như được trình bày trong bài viết này, xác suất $P_0(t)$ không có tín hiệu nào đến trong thời gian $t$ là $e^{-\lambda t}$. Do đó, xác suất tín hiệu tiếp theo

⟦folio 22⟧

Bắt đầu từ thời điểm tùy ý $t_0$, nó sẽ xuất hiện cho đến thời điểm $t_0 + t$, bằng $1 - e^{-\lambda t}$. Sau khi dịch chuyển và độ dốc thích hợp, sẽ thu được hàm phân phối được cho bởi đẳng thức (2).

Bạn có thể thử khám phá tính chất khoảng cách giữa các số nguyên tố lân cận bằng cách sử dụng một số tính chất đã biết của chúng. Ví dụ: có một ước tính cho đại lượng $N$, lần đầu tiên được chứng minh bởi nhà toán học người Pháp J. Hadamard và nhà toán học người Bỉ S.-J. Vallée Poussin năm 1896: $\pi(N) \approx N/\ln N$. Chúng ta hãy xem xét cái gọi là số gần nguyên tố: nghiệm của phương trình $n_i/\ln n_i = i + 3, i = 1, 2, 3...$, số của chúng trong khoảng từ 1 đến $N$ là rất thuận tiện, cũng xấp xỉ bằng $N/\ln N$. Hãy viết ra $n_1, n_2, ..., n_6$ và áp dụng phân tích sự khác biệt:

$$8,61 \quad 12,71 \quad 17,00 \quad 21,47 \quad 26,10 \quad 30,87 \quad 4,10 \quad 4,29 \quad 4,47 \quad 4,63 \quad 4,77 \quad 0,19 \quad 0,18 \quad 0,16 \quad 0,14$$

Có thể thấy rằng khoảng cách giữa các giả nguyên tố lân cận $n_i$ và $n_{i+1}$ quay trở lại, nhưng càng ngày càng chậm khi $i$ tăng lên. Dựa trên quan sát này, hãy thử chứng minh rằng đối với các số chuẩn nguyên tố, hàm phân phối thực nghiệm là lồi xuống và do đó không thể trùng với hàm phân phối mũ. Do đó, giả thuyết của chúng tôi không thể được chứng minh chỉ bằng cách ước tính số $\pi(N)$. Nếu nó đúng thì bằng chứng của nó phải sử dụng một số sự kiện sâu sắc hơn.

Đơn hàng được chấp nhận...

(Để bắt đầu, xem trang 18)

Thông tin, lập trình

52. Samarsky A. A., Gulin A. V. Phương pháp số. 1 chà. 90k.

Các phương pháp số hiện đại lời giải được áp dụng bài toán, được thiết kế để sử dụng máy tính tốc độ cao, được trình bày. Lý thuyết nội suy, công thức bậc hai, xấp xỉ hàm số, phương pháp số của đại số, v.v. được xem xét.

90. Giới thiệu máy tính cá nhân Corvette. 95k.

Chứa mô tả về một trong những máy tính cá nhân đầu tiên ở nước ta, Corvette. Các tính năng của kiến ​​trúc máy tính, quy tắc sử dụng và phần mềm đều được xem xét.

128. Abramov S. A., Zima E. V. Nguyên tắc cơ bản của khoa học máy tính. 1 chà.

Chứa một bản trình bày có hệ thống về các khái niệm và phương pháp cơ bản của khoa học máy tính (công nghệ máy tính, lập trình, phương pháp số, sắp xếp và tìm kiếm). Những điều cơ bản về lập trình được trình bày trong Pascal.

129. Arsak J. Lập trình và định vị giọng nói. mỗi. từ fr. 90k.

Các phương pháp lập trình nhiều trò chơi ý nghĩa và khóa giọng nói bằng số, hàm hình học, v.v. đều được xem xét.

154. Novoseltsev V.N. Sinh vật trong thế giới công nghệ: khía cạnh điều khiển học. 70k.

Nó cho biết điều khiển học ngày nay cho phép chúng ta theo nhiều cách như thế nào để đưa ra một bức tranh hoàn chỉnh về các quá trình sống trong cơ thể.

155. Dyakov V.P. Sổ tay tính toán sử dụng máy tính vi mô. 1 chà. 20k.

Chứa mô tả về báo cáo hiện đại và máy tính vi mô nước ngoài, ngôn ngữ và lập trình cơ bản.

156. Pilshikov V.N. Tập hợp các điều khiển trên ngôn ngữ Pascal. 40k.

Bộ sưu tập này dựa trên cuốn sách “Bài tập bằng ngôn ngữ Pascal” mà chúng tôi sử dụng khi dạy lập trình cho sinh viên Khoa Toán tính toán và Điều khiển học tại Đại học Moscow.

159. Nikolov R., Sendova E. Sự khởi đầu của tin học: Transl. từ tiếng Bungari 60 k.

Kinh nghiệm dạy trẻ làm việc với máy tính cá nhân được phản ánh. Bạn sẽ có được những điều cơ bản khi học với máy tính ở chế độ hội thoại bằng ngôn ngữ LOGO.
