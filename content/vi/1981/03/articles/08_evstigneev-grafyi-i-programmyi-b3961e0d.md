---
id: 1981-3-evstigneev-grafyi-i-programmyi-b3961e0d
issue: kvant_1981_3
year: 1981
number: "3"
title: Đồ thị và chương trình
authors:
  - Евстигнеев В.
rubric: matematicheskiy-kruzhok
rubric_sub: Математический кружок
page_first: 20
page_last: 24
page_labels: 18-22
tag: 7P1K
lang: vi
source: kvant_digital
extraction: vision
content_sha256: d08bd391c195948bc99f85aa7de166ac5922d81598de6f62ef6aa7ed241b0603
prompt_sha256: draft-1
translated_from: content/ru/1981/03/articles/08_evstigneev-grafyi-i-programmyi-b3961e0d.md
source_content_sha256: c1367c57fdb488e3e573f2a51bb9ca43690887b6d8361812a5fe64f468bab2f7
translation_model: draft
translation_run: vi-draft-2026-10-31
translation_quality: draft
---

⟦folio 18⟧

V. Evstgenev

Đồ thị và chương trình

Lý thuyết đồ thị hình thành như một nhánh độc lập của toán học vào giữa những năm 1930 và tiếp tục phát triển mạnh mẽ cho đến ngày nay. Sự quan tâm lớn đến lý thuyết đồ thị ngày nay chủ yếu dựa trên những ứng dụng rộng rãi và hiệu quả của nó vào việc thiết kế và phân tích các hệ thống phức tạp có nhiều bản chất khác nhau: mạng lưới giao thông, mạch điện, mạch điện tử, hệ thống cơ học, phản ứng hóa học, hệ thống điều khiển, nhóm xã hội và tập thể, v.v.

Trong bài học câu lạc bộ toán học này, chúng ta sẽ xem xét một số chương trình lập trình bài toán sử dụng đồ thị.

Đồ thị và đồ thị có hướng

Biểu đồ là một tập hợp các phần tử, trong đó một số cặp phần tử được chọn. Do đó, đồ thị $G$ được xác định bởi hai bộ:

$$G = (X, U);$$

trạng thái đầu tiên là từ các phần tử có tính chất tùy ý (chúng được gọi là các đỉnh) và trạng thái thứ hai là từ tất cả các cặp đỉnh được chọn. Nếu mỗi cặp phân biệt được sắp xếp theo thứ tự thì đồ thị $G$ được gọi là đồ thị có hướng hoặc oreraf, các cặp được gọi là Duems; họ nói rằng cung $(x, y)$ hướng từ đầu $x$ đến cuối $y$ và viết

$$U \ni u = (x, y).$$

Trong trường hợp này, họ cũng nói rằng cung vừa bắt nguồn (rời khỏi) từ $x$ vừa đi vào (đi vào) $y$. Một sơ đồ được mô tả trên một mặt phẳng dưới dạng các điểm được nối với nhau bằng các cung có mũi tên (Hình 1). Trong hình này lưu ý rằng cung đi ra từ đỉnh $x_3$ đi vào nó; một vòng cung như vậy được gọi là một netley.

Nếu các cặp $(x, y)$ không được sắp xếp thì chúng được gọi là các cạnh, các đỉnh của cạnh $u = \{x, y\}$ được gọi là các điểm cuối và bản thân đồ thị $G = (X, U)$ được gọi là đồ thị vô hướng hoặc đồ thị protego. Một ví dụ về đồ thị như vậy – còn được gọi là đồ thị Peterson – được hiển thị trong Hình 2.

Đồ thị của chương trình này

Ví dụ: đặt phần dưới cùng của chương trình $P$ ở dạng sơ đồ khối (“Đại số 8”, đoạn 50). Hãy liên kết mỗi khối với một đỉnh đồ thị và nối các đỉnh theo trình tự hành động (được biểu thị bằng các mũi tên) trong sơ đồ khối. Đồ thị thu được được gọi là phép chiếu $P$ hoặc đồ thị $p$.

Bài tập 1. Vẽ đồ thị $p$ tương ứng với sơ đồ khối phần mềm phân loại bóng như Hình 3.

Nếu chương trình $P$ được viết bằng bất kỳ ngôn ngữ thuật toán nào,

Cơm. 1.

Cơm. 2.

⟦folio 19⟧

thì nó cũng có thể được liên kết với một số đồ thị $p$: mỗi toán tử được liên kết với một đỉnh, hai đỉnh $a$ và $b$ được kết nối bởi một $(a, b)$ khác, nếu điều khiển được chuyển từ toán tử được biểu thị bằng đỉnh $a$ sang toán tử được biểu thị bằng đỉnh $b$.

Một ví dụ khác về biểu đồ $p$ được hiển thị trong Hình 4. Lưu ý hai đỉnh đặc biệt: $x_{0d}$ ($s$) (tương ứng với đầu vào chương trình), từ đó không có cung nào đi vào và $b_{1x0d}$ ($t$) (tương ứng với đầu ra của chương trình), từ đó không có cung nào phát ra.

Trên một đồ thị $p$ cho trước $G = (X, U)$ (và nói chung trên bất kỳ đồ thị nào) thường được coi là một đường đi nếu các đỉnh của nó không được lặp lại, một đường viền nếu $a = b$ và một đường dẫn đơn giản nếu $a = b$, nhưng không có sự lặp lại các đỉnh nào khác. Vì vậy, trong Hình 4, đường dẫn $(x_1, x_3, x_6, t)$ là một đường dẫn đơn giản, $(x_1, x_4, x_6, x_3, x_6, t)$ không phải là một đường dẫn đơn giản, $(x_3, x_6, x_3)$ là một đường dẫn đơn giản, $(x_3, x_6, x_3, x_6, x_3)$ là một đường dẫn, nhưng không đơn giản, $(x_2, x_7, x_6)$ thậm chí không phải là một đường dẫn.

Cơm. 3.

Cơm. 4.

Bài tập 2. Liệt kê tất cả các đường đơn giản và tất cả các đường viền đơn giản của đồ thị $p$ được xây dựng theo lời giải của Bài tập 1.

Có phải mọi con đường đều dẫn đến Rome?

Trong biểu đồ $p$ tương ứng với một chương trình được viết hay, “tất cả các con đường đều dẫn đến Rome”, nghĩa là, bất kỳ con đường nào bắt đầu từ $s$ đều có thể được tiếp tục cho đến khi thoát ra $t$, đánh dấu sự kết thúc của chương trình. Do đó, đồ thị $p$ được gọi một cách tự nhiên là *thông thường* nếu bất kỳ đỉnh nào nằm trên một đường đi (không nhất thiết phải là một đường đơn giản) dẫn từ $s$ đến $t$.

Tất nhiên, tính chính xác của biểu đồ $p$ vẫn chưa đảm bảo chương trình hoạt động thành công: nếu nó có ít nhất một đường viền mà từ đó không có cung nào xuất hiện, thì chương trình có thể đi vào một vòng lặp, tức là nó quay dọc theo đường viền này. Nhưng vì không có thuật toán chung nào kiểm tra tính đúng đắn của chương trình (chúng ta sẽ nói về vấn đề này trong «Kvant» vào lúc khác), điều quan trọng là ít nhất phải kiểm tra tính đúng đắn của biểu đồ $p$.

Làm cách nào để kiểm tra tính hợp lệ của biểu đồ $p$? Trong những trường hợp đơn giản, việc này có thể dễ dàng được thực hiện thủ công.

Bài tập 3. Kiểm tra tính đúng đắn của đồ thị $p$ của chương trình phân loại bóng (xem Bài tập 1). Đảm bảo rằng biểu đồ $p$ trong Hình 5 không chính xác, tìm “ngõ cụt”, “đường viền ngõ cụt” và “đường viền không thể tiếp cận”.

Ví dụ, trong các trường hợp phức tạp, trong các chương trình lớn hiện đại, việc kiểm tra thủ công quá tốn công sức và không đáng tin cậy - phải nhờ đến sự trợ giúp của máy tính. Vì vậy, cần có những thuật toán phù hợp cho mục đích này. Chúng tôi sẽ xây dựng Bài toán về việc xây dựng các thuật toán như vậy dưới dạng ba bài tập (4-6) và đối với bài tập đầu tiên, chúng tôi sẽ đề xuất lời giải.

⟦folio 20⟧

Cơm. 5.

Bài tập 4. Tìm tất cả các đường dẫn đơn giản kết nối đầu vào của đồ thị $p$ với đầu ra của nó.

Một trong những thuật toán đẹp nhất cho lời giải này bài toán dựa trên sự sắp xếp tuần tự các đỉnh của biểu đồ $p$. Hình 6 thể hiện ứng dụng của nó đối với đồ thị $p$ của Hình 4. Ở mỗi bước, một trong các đỉnh $x \in X$ (khác với $s$ và $t$) bị BỊ LÊN; Cùng với các đường dẫn đơn giản nối các đỉnh liền kề với $x$ và đi qua $x$, một cung mới được xây dựng (bên cạnh đó ghi tên của đỉnh bị loại bỏ). Các vòng lặp phát sinh trong quá trình này sẽ bị loại bỏ. Kết quả là một tập hợp các cung nối $s$ với $t$, hơn nữa, trên mỗi cung này các đỉnh được viết liên tiếp, qua đó có thể tìm ra các thuật toán giải các điều khiển 5, 6. Chúng có thể được viết dưới dạng biểu đồ luồng, dạng bảng (“Đại số 8”, trang 49) hoặc đối với sinh viên ZShP, bằng ngôn ngữ Rapier.

Bài tập 5*. Tìm tất cả các đường viền đơn giản của đồ thị $p$.

Bài tập 6*. Xây dựng một hệ thống các đường dẫn (không nhất thiết phải đơn giản) kết nối đầu vào của đồ thị $p$ với đầu ra của nó, bao gồm tất cả các đỉnh của đồ thị $p$. Xây dựng một hệ thống như vậy với số lượng đường dẫn tối thiểu.

Orgraph của một biểu thức số học

Khi tính các biểu thức số học trên máy tính theo thứ tự ngẫu nhiên, khi có nhiều biểu thức này và khá cồng kềnh, dữ liệu ban đầu và kết quả trung gian của phép tính có thể chiếm một lượng bộ nhớ máy tính lớn đến mức không thể chấp nhận được; như các lập trình viên nói, “chương trình làm tắc nghẽn RAM của máy”. Làm thế nào để đối phó với điều này? Đây là lúc lý thuyết đồ thị ra tay giải cứu.

Hóa ra là với mỗi biểu thức số học người ta có thể liên kết

CÁCH ĐƠN GIẢN:

$s x_1 x_3 x_6 t$
$s x_1 x_4 x_6 t$
$s x_2 x_7 t$
$s x_2 x_5 x_7 t$

Cơm. 6.

⟦folio 21⟧

tạo một sơ đồ thuộc loại đặc biệt. Ví dụ, với biểu thức
$$((a+b) \cdot (c-d)) / (g+f) + h = L$$
bạn có thể kết nối biểu đồ được hiển thị trong Hình 7. Nếu các chữ cái không được lặp lại trong công thức, những biểu đồ đó có một tên đặc biệt. Cây thứ tự (cây có hướng) là một đồ thị trong đó một đỉnh được chọn - gốc của cây thứ tự và từ bất kỳ đỉnh nào khác của cây thứ tự chỉ có một đường dẫn đến gốc. Không có đường đi từ gốc đến bất kỳ đỉnh nào.

Vì vậy, trong ví dụ của chúng tôi (xem Hình 7), một thứ tự có gốc $L$ được hiển thị. Các đỉnh $a, b, c, d, f, g, h$ được gọi là tính được.

Bài tập 7. Xây dựng biểu thức thứ tự
$$\frac{\sqrt{x+y}}{z^2+5at+7k} + \frac{b+c}{r} = L.$$

Quay lại Hình 7, hãy tưởng tượng rằng các thao tác riêng lẻ được thực hiện tại thời điểm được hiển thị bằng các đường thẳng đứng màu đỏ. Sau đó, bộ nhớ sẽ lưu tối đa 6 số cùng một lúc. Đúng, con số này có thể giảm xuống còn 4 nếu số $g, f$ có trong bộ nhớ tại thời điểm $t=2$ (thay vì $t=1$).

Liệu có thể mô tả biểu thức của chúng ta theo một trật tự tiết kiệm hơn nữa (theo nghĩa này) không?

Hãy kéo một con lạc đà qua lỗ kim

Xét thang thời gian rời rạc $t=1, 2, 3, \dots$. Hãy để quá trình tính toán được tổ chức theo cách mà các ô nhớ được lấp đầy (dữ liệu ban đầu được nhập, kết quả trung gian được tính toán được ghi, v.v.) tại các thời điểm nguyên và duy trì trong một số khoảng thời gian của thang đo đã chọn. Khi nội dung của một ô được sử dụng, nó sẽ được giải phóng. Chúng ta cũng giả sử rằng tại mỗi thời điểm chỉ có một ô nhớ được gửi đi. Điều kiện cuối cùng cho phép bạn đánh số các đỉnh theo thứ tự tương ứng,

Ý tưởng xây dựng các ngăn xếp đơn hàng, có phần nêm nhỏ, được A.P. Ershov đưa ra vào năm 1958 và hóa ra lại cực kỳ hữu ích. Đối với bài toán phức tạp, cũng có thể tạo kiểu hẹp, điều này vừa phải để chuẩn bị cho việc luồn lạc đà qua lỗ kim!

⟦folio 22⟧

treo thì chuyển sang bước 4, nếu không thì chuyển sang bước 5.

Bước 4. Ở cột thứ hai có 0, ở cột thứ ba - x. (Vì vậy chúng tôi đặt $p(x) = 0, q(x) = x$.) Chuyển sang bước 3.

Bước 5. Gọi $y_1, y_2, \dots, y_k$ là thứ tự các đỉnh ngay trước x, được sắp xếp sao cho $p(y_1) \geq p(y_2) \geq \dots \geq p(y_k)$. Chúng tôi sẽ tìm thấy
$$p(x) = \max_{1 \leq s \leq k} \{p(y_s) + s - 1\}$$
$$q(x) = q(y_1)q(y_2) \dots q(y_k)x,$$
và nhập các giá trị tìm thấy vào cột thứ hai và thứ ba của hàng được đề cập. Hãy chuyển sang bước 3.

Cơm. 8.

Cơm. 9.

Bây giờ chúng ta sẽ mô tả một trong các thuật toán để xây dựng các cấu trúc như vậy, được gọi là *thuật toán Redrzejewski*.

Bước 1. Hãy xây dựng một bảng có n hàng và ba cột, trong đó n là số đỉnh thứ tự.

Bước 2. Hãy điền vào cột đầu tiên của bảng từ dưới lên trên, đặt gốc $x_0$ của thứ tự ở hàng thấp nhất, sau đó theo thứ tự tùy ý của các tiền nhiệm, miễn là thứ tự tính toán không bị vi phạm ở bất kỳ đâu (nghĩa là phải lấy mọi dữ liệu cần thiết cho thao tác tiếp theo trước khi thực hiện).

Trong phần tiếp theo, chúng tôi sẽ sử dụng $p(x)$ và $q(x)$ để biểu thị các mục trong cột thứ hai và thứ ba của dòng bắt đầu bằng chữ x. Các giá trị của hàm $p$ sẽ là số, hàm $q$ sẽ là dãy các chữ cái. Hãy để r dòng đầu tiên được điền vào.

Bước 3. Chúng ta bắt đầu điền dòng tiếp theo (những dòng trước đã được điền); chúng ta hãy biểu thị chữ cái đầu tiên của nó bằng x. Nếu đỉnh x là

Lặp lại các bước 3-5 cho đến khi toàn bộ bảng được lấp đầy. Sau đó, ở dòng cuối cùng trong cột thứ hai, chúng ta nhận được chiều rộng của xếp chồng, nghĩa là $p(x_0) = W(Y, T)$, và ở dòng thứ ba - xếp chồng theo thứ tự T, nếu các đỉnh trong dãy $q(x_0)$ được xếp từ trái sang phải.

Bảng thu được bằng cách áp dụng thuật toán Redrzejewski cho thứ tự trong Hình 7 được hiển thị trong Hình 8 và thứ tự “xếp chồng” được hiển thị trong Hình 9.

Bài tập 9. Áp dụng thuật toán Regjewski theo thứ tự thu được ở Bài tập 7.
