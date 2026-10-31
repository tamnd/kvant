---
id: 1976-7-obschiy-vid-i-shema-schyotnoy-mashinyi-b-paskalya-663e5cca
issue: kvant_1976_7
year: 1976
number: "7"
title: Hình ảnh và sơ đồ tổng quát máy tính B. Pascal
rubric: smes
page_first: 2
page_last: 10
page_labels: 1, 4, 5, 6, 7, 8
tag: WY0R
lang: vi
source: kvant_digital
extraction: vision
content_sha256: e87e90b8e18689975dd9af0452d2d41cf2108fbcc8a9e468a07d2d27efd10d26
prompt_sha256: draft-1
translated_from: content/ru/1976/07/articles/02_obschiy-vid-i-shema-schyotnoy-mashinyi-b-paskalya-663e5cca.md
source_content_sha256: 7547cd568b6ab3ca5ea9012ca40ecf69f4a13f8a17b9d8d2dcc6c3a2194827e1
translation_model: draft
translation_run: vi-draft-2026-10-31
translation_quality: draft
---

⟦folio none⟧

Trang này hiển thị cái nhìn tổng quát và sơ đồ của một chiếc máy tính tổng được thiết kế bởi một trong những người quan trọng nhất trong lịch sử loài người - Blaise Pascal (1623-1662). Chân dung của anh ấy ở bên trái. Pascal, cuộc đời của ông, vô số thành tựu khoa học, khám phá, ý tưởng và phát minh đã được mô tả trong «Kvant» (1973, số 8, trang 4). Nó cũng kể về chiếc xe do anh ấy chế tạo (trang 10-11). Những người cùng thời với Pascal gọi nó là "bánh xe Pascal". Về máy tính, lịch sử phát minh ra chúng, cấu trúc (logic và vật lý) của máy tính hiện đại cũng như các ứng dụng của chúng được mô tả chi tiết trong cuốn sách giao nhau của R. S. Guter và Yu. L. Polunov “Những cỗ máy toán học” do nhà xuất bản “Prosveshcheniye” xuất bản năm 1975. Tôi khuyên bạn nên đọc nó. Bạn có thể tìm thấy lời giải cho cuốn sách này tại trang. 50 số này của tạp chí.

⟦folio 1⟧

Tổng biên tập
Viện sĩ I. K. Kikoin
Phó thứ nhất
tổng biên tập
Viện sĩ A. N. Kolmogorov

Tuyển tập biên soạn:
M. I. Bashmkov
S. T. Belyaev
V. G. Boltyansky
N. B. Vasiliev
Yu. N. Efremov
V. G. Zubov
P. L. Kapitsa
V. A. Kirillin
A. I. Klimanov
(nghệ sĩ chính)
S. M. Kozel
V. A. Leshkovtsev
(Phó tổng biên tập)
L. G. Makar-Limanov
A. I. Markushevich
N. A. Patrikeeva
I. S. Petrkov
N. Kh. Rozov
A. P. Savin
Tôi. Sh. Slobodetsky
M. L. Smolyansky
(Phó tổng biên tập)
Y. A. Smorodinsky
V. A. Fabricant
A. T. Tsvetkov
M. P. Shaskolskaya
S. I. Schwartzburg
A. I. Shirshov

biên tập:
V. N. Berezin
A. N. Vilenkin
I. N. Klumova
T. M. Makarova
(biên tập nghệ thuật)
T. S. Petrova
V. A. Tikhomirova
L. V. Chernova
(người quản lý biên tập)

TRONG PHÒNG:
2 B. Aleynikov, P. Buzitsky, M. Dubson. Phương pháp đơn giản
9 E. Ghazaryan, R. Sahakyan. Về một phương pháp lời giải bài toán trong tĩnh điện
14 A. Dozorov. Tại sao máy biến áp cần có lõi?

Phòng thí nghiệm «Kvant»
18 M. Đầu. nhân vật Gaidingar
vòng tròn toán học
21 E. Gottman. Bài toán để chứng minh
25 à. Ponarin. Tính diện tích
Bài toán Kvant
28 Bài toán M391—M395; F403—F407
30 Lời giải bài toán M351 — M353; F358 — F361

Xưởng của người nộp đơn
37 Đại học bang Donetsk
38 Viện Quản lý Moscow được đặt theo tên. S. Ordzhonikidze
39 Viện Dây điện và Cơ khí Moscow
40 Viện kỹ sư vận tải đường sắt Belarus
41 Học viện chính trị Donetsk
Học viện Chính trị 43 Mari mang tên. M. Gorky
43 Học viện Chính trị Yaroslavl
44 Học viện sư phạm quốc gia Moscow được đặt theo tên. V. I. Lênin
45 Học viện sư phạm khu vực Moscow được đặt theo tên. N. K. Krupskaya

X Olympic toàn Liên đoàn dành cho học sinh
48 V. Berezin, V. Tikhomirova. Olympic dành cho học sinh thành phố Moscow

Đánh giá, thư mục
50 E. Belaga. "Máy toán học"
51 L. Karmazina, N. Meller. "ALGOL 60"
52 I. Klumova, M. Smolyansky. Sách mới
«Kvant» cho học sinh nhỏ
54 Bài toán
55 A. Orlov. chủ đề Ponsk
58 Đáp số, gợi ý, lời giải
Hỗn hợp (tr. 47)

© Tòa soạn chính văn học vật lý và toán học của nhà xuất bản “Nuka”, «Kvant», 1976 200

⟦folio 4⟧

Lời giải $x_1^0, x_2^0, \ldots, x_n^0$ của hệ (1) được gọi là nghiệm chấp nhận được của OLP nếu các số $x_1^0, x_2^0, \ldots, x_n^0$ không âm. Chúng ta sẽ gọi giá trị tối ưu là chấp nhận được lời giải, biến hàm mục tiêu (2) về mức tối thiểu.

Một OPLP cụ thể có thể không có lời giải: hệ thống (1) có thể không nhất quán, tức là nó có thể không có lời giải chút nào; nó có thể là khớp, nhưng không có lời giải hợp lệ; cuối cùng, nó thậm chí có thể có lời giải có thể chấp nhận được, nhưng trong số chúng có thể không có giá trị tối ưu: hàm (2) có thể không bị giới hạn ở tập hợp lời giải có thể chấp nhận được. Tuy nhiên, tất cả những mô tả này sẽ chỉ hỗ trợ chúng ta trong những nhiệm vụ được phát minh đặc biệt; trong khả năng tự nhiên của thực tế bài toán lời giải, như một quy luật, tồn tại.

Giả sử rằng hệ (1) là nhất quán và các phương trình của nó độc lập tuyến tính, nghĩa là không phương trình nào có thể được suy ra từ các phương trình khác. Có thể chứng minh rằng khi đó $m \leq n$.

Trước tiên chúng ta hãy xem xét trường hợp số phương trình $m$ bằng số biến $n$. Trong đại số tuyến tính, người ta đã chứng minh rằng trong trường hợp này hệ (1) có duy nhất lời giải. Nếu lời giải này hợp lệ, nó sẽ tự động tối ưu.

Trường hợp quan tâm là khi $m < n$ (trong thực tế điều này tương ứng với khả năng lựa chọn các kế hoạch hành động khác nhau). Chúng ta hãy biểu thị $n - m$ bằng $k$. Trong đại số tuyến tính, người ta đã chứng minh rằng một số biến $m$ (chúng được gọi là biến cơ bản) có thể được biểu diễn dưới dạng các biến $k$ còn lại (chúng được gọi là biến tự do). Hệ (1) xét trường hợp tập vô hạn lời giải: cho các biến tự do các giá trị tùy ý và tính toán sự tương ứng của các biến cơ bản, mỗi lần chúng ta sẽ thu được một lời giải mới của hệ (1). Một số hệ thống lời giải (1) được gọi là *tham chiếu* nếu giá trị của ít nhất các biến $k$ bằng 0. Trong lý thuyết quy hoạch tuyến tính, người ta đã chứng minh rằng lời giải tối ưu là tham chiếu.

Từ định lý cuối cùng này, kế hoạch lời giải OZLP sau đây: bằng cách nào đó chúng ta chọn $k$ biến tự do; chúng tôi giải quyết hệ thống liên quan đến $m$ các biến cơ bản còn lại; đặt các biến tự do bằng 0, chúng ta tìm thấy tham chiếu lời giải; Chúng tôi tính toán giá trị tương ứng của hàm mục tiêu. Sau khi xem xét tất cả các khả năng chọn biến tự do, chúng ta sẽ thấy hàm mục tiêu nào trong số hỗ trợ lời giải sẽ lấy giá trị nhỏ nhất - đây sẽ là giá trị tối ưu mong muốn lời giải.

Đối với bài toán đơn giản, trong đó số lượng biến $n$ là không thể tin được, phương pháp lời giải này—tìm kiếm “mù”—về nguyên tắc là phù hợp. Tuy nhiên, trong các vấn đề nảy sinh trong thực tế, số lượng biến và số lượng hạn chế áp đặt $m$ thường rất lớn - lên tới hàng trăm, thậm chí hàng nghìn. Đối với bài toán việc liệt kê đơn giản như vậy thực tế là không thể: số cách có thể để chọn các biến tự do trở nên rất lớn!

Posmot trong lý thuyết quy hoạch tuyến tính, nhiều phương pháp khác nhau đã được phát triển cho phép chúng ta tìm ra lời giải tối ưu không phải bằng tìm kiếm “mù”, mà để mỗi lần lựa chọn biến tự do tiếp theo sẽ đưa chúng ta đến gần hơn với lời giải.

Phương pháp lâu đời nhất và nổi tiếng nhất trong số đó là *phương pháp đơn giản*, được nhà toán học người Mỹ J. Dantz tạo ra vào cuối những năm 40.

**Phương pháp đơn giản**

Ví dụ, hãy để các biến $k$ biến $x_1, x_2, \ldots, x_k$, và phần còn lại $m$ các biến được thể hiện thông qua

⟦folio 5⟧

họ:

$$\begin{align*}
x_{k+1} &= \alpha_{k+1,1} x_1 + \alpha_{k+1,2} x_2 + \\
&\quad + \dots + \alpha_{k+1,k} x_k + \beta_{k+1}, \\
x_{k+2} &= \alpha_{k+2,1} x_1 + \alpha_{k+2,2} x_2 + \\
&\quad + \dots + \alpha_{k+2,k} x_k + \beta_{k+2}, \\
x_n &= \alpha_{n,1} x_1 + \alpha_{n,2} x_2 + \\
&\quad + \dots + \alpha_{n,k} x_k + \beta_n.
\end{align*}$$

Đặt tất cả các biến tự do bằng 0, chúng ta thu được các hệ sau (1):

$$\begin{align*}
x_1^0 &= x_2^0 = \dots = x_k^0 = 0, \\
x_{k+1}^0 &= \beta_{k+1}, x_{k+2}^0 &= \beta_{k+2}, \dots \\
\dots, x_n^0 &= \beta_n.
\end{align*}$$

Nếu tất cả các số hạng tự do $\beta_{k+1}, \beta_{k+2}, \dots, \beta_n$ đều không âm thì lời giải (6) được chấp nhận.

Để kiểm tra xem nó có tối ưu hay không, chúng ta biểu thị hàm mục tiêu $L$ theo các biến tự do $x_1, x_2, \dots, x_k$, thay thế các biểu thức cho $x_{k+1}, x_{k+2}, \dots, x_n$ từ (5) thành (2):

$$L(x_1, x_2, \dots, x_n) = d_0 + d_1 x_1 + d_2 x_2 + \dots + d_k x_k.$$

Từ (6) suy ra $L(x_1^0, x_2^0, \dots, x_n^0) = d_0$. Hãy xem liệu chúng ta có thể giảm giá trị của hàm mục tiêu $L$ hay không bằng cách tăng giá trị của các biến tự do $x_1, x_2, \dots, x_k$ (chúng ta không thể giảm chúng, vì trong lời giải (6) chúng bằng 0 và chúng ta đang tìm kiếm một lời giải có thể chấp nhận được).

Nếu tất cả các hệ số $d_1, d_2, \dots, d_k$ trong đẳng thức (7) đều không âm, thì bằng cách tăng giá trị của các biến tự do, chúng ta sẽ giảm giá trị của hàm $L$, tức là chúng ta sẽ buộc tội lời giải. Trong trường hợp này, lời giải không phải là lựa chọn tối ưu cho chúng tôi.

Ví dụ: trong đẳng thức (7), hệ số $d_1$ âm. Nếu trong hệ thống (5) tất cả các hệ số của $x_1$ đều không âm, thì bất kỳ sự gia tăng nào về giá trị của biến $x_1$ sẽ khiến các giá trị của biến $x_{k+1}, x_{k+2}, \dots, x_n$ không âm và chúng ta sẽ không rời khỏi vùng chấp nhận được lời giải. Giá trị của hàm $L$ sẽ giảm không giới hạn. Do đó, trong trường hợp này cũng có các phương trình của hệ (5) trong đó hệ số tại $x_1$ âm. Đối với các biến ở vế trái của các phương trình này, việc tăng giá trị của biến $x_1$ được mô tả: nó có thể làm cho chúng âm.

Ví dụ: nếu $\alpha_{k+1,1} < 0$, thì rõ ràng giá trị của biến $x_1$ chỉ có thể giảm xuống $-\frac{\beta_{k+1}}{\alpha_{k+1,1}}$. (Đối với $x_1^0 = -\frac{\beta_{k+1}}{\alpha_{k+1,1}}$, $x_2^0 = \dots = x_k^0 = 0$ chúng ta nhận được $x_{k+1}^0 = 0$.)

Trung bình của các biến mô tả mức tăng giá trị của biến $x_1$, chúng tôi chọn biến có nhiều khả năng tiến đến 0 nhất, tức là biến mà mức tăng $-\frac{\beta_l}{\alpha_l,1}$ là ít nhất.

Đặt biến “bị đe dọa nhất” này là $x_r$.

Bây giờ chúng ta loại bỏ $x_1$ khỏi số lượng biến tự do và chuyển chúng cùng nhau sang nhóm biến tự do $x_r$, tức là chúng ta giải quyết hệ thống (1) đối với các biến cơ bản

$$x_1, x_{k+1}, \dots, x_{r-1}, x_{r+1}, \dots, x_n.$$

Sau đó, mọi thứ được lặp lại: đặt tất cả các biến miễn phí $x_2, \dots, x_k, x_r$ bằng 0, chúng ta tìm thấy lời giải tương ứng; Hãy biểu thị hàm mục tiêu $L$ theo các biến tự do mới; nếu tất cả các hệ số của các biến trong biểu thức kết quả

⟦folio 6⟧

Đối với $L$ không âm, lời giải tìm được là tối ưu; mặt khác, quá trình lựa chọn các biến cơ sở và cải thiện lời giải vẫn tiếp tục.

Thuật toán được mô tả được gọi là phương pháp đơn giản. (Bạn đọc có nhận thấy rằng trong phần trình bày thuật toán của chúng tôi còn lại một “lỗ hổng”: một khả năng không được xem xét?)

Hai ví dụ

Trước tiên chúng ta hãy xem xét trường phổ thông bài toán.

Bài toán 1. Ba người đi xe đạp muốn đến một hồ nước trong rừng cách nhà 20 km. Họ có một chiếc xe gắn máy hai chỗ ngồi có thể di chuyển với tốc độ 36 km/h. Mỗi người đi xe đạp có thể đi bộ với vận tốc 4 km/h. Tổ chức giao thông như thế nào để mọi người có thể đến hồ nhanh hơn? Thời gian ngắn nhất có thể thực hiện được việc này là bao lâu?

Rõ ràng, nhiều lần thay đổi hành khách trên biển không thể mang lại lợi ích về mặt thời gian so với một lần thay đổi duy nhất. Vì vậy, chúng ta sẽ lập kế hoạch tổ chức phong trào như sau: vào thời điểm ban đầu, một học sinh đồng thời rời khỏi nhà $\Delta$ để đến moredev và một học sinh thứ ba đi bộ. Tại điểm trung gian $T$ người điều khiển moreda thể hiện định nghĩa của mình $t_1 = t_2$.

Chúng ta cần tìm $x$ mà hàm $t = \max (t_1, t_2)$ có giá trị nhỏ nhất. Ngoài ra, chúng ta cần tìm giá trị của hàm $max (t_1, t_2)$ với $x$, tức là số ($\max (t_1, t_2)$). Từ Hình 2 (nó hiển thị biểu đồ của hàm $t_1(x)$ màu đỏ, hàm $t_2(x)$ màu đen và hàm $max (t_1, t_2)$ màu xanh lam), có thể thấy ngay rằng $x$ mong muốn được xác định từ phương trình $t_1 = t_2$.

Tuy nhiên, để minh họa phương pháp chung, chúng ta hãy đặt và giải bài toán đã cho dưới dạng lập trình tuyến tính bài toán. Chúng ta hãy định dạng lại nó theo cách này: tìm $t$ nhỏ nhất mà cả $t \geq t_1$ và $t \geq t_2$. Vì vậy, chúng ta cần tìm các giá trị không âm của các biến $x$ và $t$ thỏa mãn hệ bất đẳng thức

$$\begin{cases} t \geq \frac{x}{36} + \frac{20-x}{4}, \\ t \geq \frac{5}{9} + \frac{2}{45} x \end{cases}$$

⟦folio 7⟧

và thu nhỏ hàm $L$:
$$L(x, t) = 0 \cdot x + 1 \cdot t = t. \tag{9}$$
Chúng tôi có bài toán lập trình tuyến tính. Hãy giảm nó thành OZLP.
Hệ (8) tương đương với hệ
$$\begin{cases} 2x + 9t - 45 \geq 0, \\ -2x + 45t - 25 \geq 0. \end{cases} \tag{10}$$

Chúng ta hãy biểu thị $2x + 9t - 45$ bằng $y_1$, $-2x + 45t - 25$ bằng $y_2$. Sau đó $2x + 9t - 45 = y_1$, $-2x + 45t - 25 = y_2$ và $y_1 \geq 0, y_2 \geq 0$. Bây giờ chúng ta có thể xây dựng bài toán như sau: tìm các giá trị không âm của các biến $x, t, y_1, y_2$ thỏa mãn hệ phương trình
$$\begin{cases} 2x + 9t - y_1 = 45, \\ -2x + 45t - y_2 = 25 \end{cases} \tag{11}$$

và cực tiểu hóa hàm mục tiêu $L(x, t, y_1, y_2) = t$. Và đây đã là OZLP. Hãy giải quyết nó bằng phương pháp đơn giản.

Chúng ta hãy chọn $y_1$ và $y_2$ làm biến cơ bản (hệ (11) dễ giải nhất đối với chúng) và biểu thị chúng dưới dạng biến tự do $x, t$:
$$\begin{cases} y_1 = 2x + 9t - 45, \\ y_2 = -2x + 45t - 25. \end{cases} \tag{12}$$

Đặt các biến tự do bằng 0, ta thu được lời giải của hệ (12) và (11):
$$x^{(1)} = t^{(1)} = 0, y_1^{(1)} = -45, y_2^{(1)} = -25.$$
lời giải này không hợp lệ.

Bây giờ chúng ta chọn hai biến khác làm biến cơ sở, ví dụ $t$ và $y_2$. (Trong lý thuyết quy hoạch tuyến tính, có một phương pháp chỉ ra cách chọn các biến tự do mới sao cho tiến tới vùng chấp nhận được lời giải. Chúng tôi không trình bày phương pháp này ở đây.) Ta giải hệ (11) đối với chúng:
$$\begin{cases} t = -\frac{2}{9}x + \frac{1}{9}y_1 + 5, \\ y_2 = -12x + 5y_1 + 200. \end{cases} \tag{13}$$

Đặt các biến tự do bằng 0, ta thu được lời giải của hệ (13) và (11):
$$x^{(2)} = y_1^{(2)} = 0, t^{(2)} = 5, y_2^{(2)} = 200. \tag{14}$$

Lời giải (14) đã hợp lệ. Để kiểm tra xem nó có tối ưu hay không, chúng tôi biểu thị hàm mục tiêu $L$ theo các biến tự do $x$ và $y_1$. Từ (9) và (13)
$$L(x, t, y_1, y_2) = -\frac{2}{9}x + \frac{1}{9}y_1 + 5. \tag{15}$$

Giá trị của hàm mục tiêu $L$ trên lời giải (14) là 5.

Vì hệ số $x$ trong (15) âm nên lời giải (14) không tối ưu: bằng cách tăng giá trị của biến $x$, chúng ta sẽ giảm giá trị của hàm mục tiêu $L$.

Trong các phương trình tổng quát của hệ (13), các hệ số $x$ đều âm. Do đó, việc tăng giá trị của biến $x$ được mô tả cho cả $t$ và $y_2$. Sự gia tăng này có thể làm cho chúng tiêu cực. Từ phương trình đầu tiên của hệ (13), theo đó giá trị của biến $x$ có thể tăng lên $-5 / \left(-\frac{2}{9}\right) = \frac{45}{2} = 22 \frac{1}{2}$ (với giá trị này $x$ và với $y_1 = 0$ chúng ta thu được $t = 0$; khi tăng thêm $x$ giá trị của biến $t$ trở thành âm); từ giây - lên đến $-\frac{200}{12} = \frac{50}{3} = 16 \frac{2}{3}$. Do đó, khi giá trị của biến $x$ tăng lên, biến $y_2$ cũng sẽ về 0: nó ở vị trí “bị đe dọa nhiều hơn” so với $t$.

⟦folio 8⟧

Bây giờ chúng ta hãy loại bỏ $x$ khỏi số lượng biến tự do và chuyển nó sang nhóm biến tự do $y_2$, tức là giải quyết hệ thống (11) đối với các biến cơ sở $x$ và $t$:

$$\begin{cases}
x = \frac{5}{12} y_1 - \frac{1}{12} y_2 + \frac{50}{3}, \\
t = \frac{1}{54} y_1 + \frac{1}{54} y_2 + \frac{35}{27}.
\end{cases}$$

Đặt các biến tự do bằng 0, ta thu được lời giải của hệ (16) và (11):

$$y_1^{(3)} = y_2^{(3)} = 0, \quad x^{(3)} = \frac{50}{3}, \\
t^{(3)} = \frac{35}{27}.$$

Chúng ta hãy biểu thị hàm mục tiêu $L$ theo $y_1$ và $y_2$. Từ (9) và (16)

$$L(x, t, y_1, y_2) = \frac{1}{54} y_1 + \frac{1}{54} y_2 + \frac{35}{27}.$$

Giá trị của hàm mục tiêu $L$ trên lời giải (17) là $\frac{35}{27}$.

Vì tất cả các hệ số của các biến trong (18) đều không âm nên lời giải (17) là tối ưu. Vì vậy, bài toán lời giải: hành khách phải được thả ở khoảng cách $x^{(3)} = \frac{50}{3} = 16\frac{2}{3}$ (km); thời gian ngắn nhất để bạn có thể đến hồ là $t^{(3)} = \frac{35}{27} = 1\frac{8}{27}$ (giờ).

Bây giờ chúng ta hãy trình bày một bài toán thực tế điển hình, nó tự nhiên trở thành giống như bài toán của lập trình tuyến tính. Đây được gọi là “bài toán về chế độ ăn kiêng”, hoặc “bài toán về chế độ ăn kiêng”.

Nhiệm vụ 2. Giám đốc căng tin cần xây dựng thực đơn. Anh ta có 5 loại sản phẩm tùy ý sử dụng: bánh mì, rau, trái cây, thịt, cá.

Được biết, một kg bánh mì có giá $c_1$ rúp, một kg rau có giá $c_2$ rúp, v.v. Người ta cũng biết rằng một kg bánh mì chứa $a_{11}$ ke protein, $a_{12}$ ke chất béo và $a_{13}$ ke carbohydrate, v.v. (hàm lượng protein, chất béo và carbohydrate trong một kg của từng loại sản phẩm được chỉ ra trong bảng ở hình 3). Cần có một thực đơn tối đa để nó chứa ít nhất $b_1$k protein, ít nhất $b_2$k chất béo và ít nhất $b_3$k carbohydrate và chi phí của nó là tối thiểu.

Chúng ta hãy biểu thị bằng $x_1$ số lượng bánh mì sẽ có trong thực đơn, bằng $x_2$ số lượng rau, v.v. Tổng chi phí của thực đơn $L$ rõ ràng sẽ được biểu thị bằng đẳng thức

$$L(x_1, x_2, x_3, x_4, x_5) = \sum_{i=1}^{5} c_i x_i.$$

Những hạn chế về giá trị dinh dưỡng của thực đơn được thể hiện bằng hệ thống bất bình đẳng

$$\begin{cases}
a_{11}x_1 + a_{21}x_2 + a_{31}x_3 + a_{41}x_4 + \\
+ a_{51}x_5 \geq b_1, \\
a_{12}x_1 + a_{22}x_2 + a_{32}x_3 + a_{42}x_4 + \\
+ a_{52}x_5 \geq b_2, \\
a_{13}x_1 + a_{23}x_2 + a_{33}x_3 + a_{43}x_4 + \\
+ a_{53}x_5 \geq b_3.
\end{cases}$$

bài toán của chúng ta có dạng: tìm các giá trị không âm ​​của các biến $x_1, x_2, x_3, x_4, x_5$ thỏa mãn hệ bất phương trình (20) và cực tiểu hóa hàm $L$ từ (19). Đây là bài toán của lập trình tuyến tính.
