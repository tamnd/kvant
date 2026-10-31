---
id: 1987-11-duvanov-pervin-yazyik-logo-068ce3a0
issue: kvant_1987_11
year: 1987
number: "11"
title: Biểu tượng ngôn ngữ
authors:
  - Дуванов А. А.
  - Первин Ю. А.
rubric: raznoe
rubric_sub: Разное
page_first: 44
page_last: 47
page_labels: 42-45
tag: KET6
lang: vi
source: kvant_digital
extraction: vision
content_sha256: 67afc92bd0f3dc54b59c441131ca405da08b0d44ecab333e4d19632cd62b9484
prompt_sha256: draft-1
translated_from: content/ru/1987/11/articles/18_duvanov-pervin-yazyik-logo-068ce3a0.md
source_content_sha256: daea37dfd21fce9016acfc89ca6a07cf289a8ae7cf6a51ab5b2fcb87907d7047
translation_model: draft
translation_run: vi-draft-2026-10-31
translation_quality: draft
---

⟦folio 42⟧

Biểu tượng ngôn ngữ
Bài 2: Học viện Cherenash

A. A. DUVANOV, Y. A. PERVIN

Logo số học.
Tất nhiên, máy tính phải có khả năng tính toán. Chúng ta có thể gõ lệnh FORWARD 10+20 trên bàn phím. Máy sẽ cộng 10+20 và đưa Rùa về phía trước 30 bước. Trong tất cả các lệnh đã nhập trước đó, các biểu thức số học có thể được sử dụng cùng với một số bước hoặc độ quay cụ thể. Máy sẽ thực hiện các hành động được chỉ định trong đó, làm tròn kết quả đến số nguyên gần nhất và sử dụng số này làm tham số lệnh. Vì vậy, động tác của người thực hiện sẽ giống hệt nhau khi thực hiện lệnh
TRỞ LẠI (100+20)/5 và TRỞ LẠI 24
PHẢI 30—200/(2+3) và PHẢI —10
TRÁI 20/3 và TRÁI 7.

Trong ngôn ngữ Logo, các ký hiệu sau được dùng làm dấu hiệu của các phép tính số học:

+ hoạt động bổ sung;
- phép trừ;
* phép nhân;
/ hoạt động phân chia.

Như thường lệ, dấu ngoặc đơn dùng để kiểm soát thứ tự các hành động. Các biểu thức phải được "kéo dài" thành một chuỗi: (2+7)/5 và không cho phép các mục nhập "nhiều tầng" như $\frac{2+7}{5}$. Hạn chế này là do trên bàn phím máy tính, tất cả các ký hiệu của một biểu thức chỉ có thể được gõ một cách tuần tự. Tất cả các dấu hiệu trong một biểu thức số học phải được xác định rõ ràng. Viết Forward (3+7)(40+30) sẽ buộc máy nhận ra:
KHÔNG RÕ RÀNG NÓ LÀ GÌ (3+7)(40+30)
Chính xác bạn nên viết: FORWARD (3+7)*(40+30). Phân số thập phân trong Logo được viết như bình thường nhưng dùng dấu chấm thay cho dấu phẩy để phân tách phần phân số.

Cherenakha làm trung gian cho các mệnh lệnh:
TIẾN 2*(48+3)/2. 5 và TIẾN 40
PHẢI 180/3. 14 và PHẢI 57

Tất cả những điều này, không hoàn toàn khắc sâu, việc ghi lại chính xác các biểu thức số học không liên quan gì đến

⟦folio 43⟧

đối với chính chủ đề lập trình và chỉ liên quan đến sự không hoàn hảo của các máy móc hiện tại, nhưng vì điều này, chúng trở nên vô cùng cần thiết khi việc thiết lập một chương trình cho một máy tính thực sự là cần thiết.

Vì máy tính có thể đếm nên việc nó hiển thị kết quả tính toán trên màn hình là điều đương nhiên. Để buộc máy in ra màn hình kết quả của phép chia 25 cho 4, bạn chỉ cần gõ lệnh:
VIẾT 25/4

Khi thực hiện lệnh, máy tính hiển thị kết quả ra màn hình: 6.25. Xin lưu ý, không làm tròn! Thực tế là chỉ có các tham số của lệnh buộc Rùa di chuyển mới được làm tròn. Và trên thực tế, đơn vị chuyển động chính là số “bước” - các điểm trên màn hình, phải là số nguyên. Máy đã có thể tính toán (và đưa ra) kết quả với độ chính xác rất cao.

Bài toán 1 (dành cho luyện viết biểu thức). a) Viết lệnh BACK không có dấu thao tác, thực hiện các thao tác tương tự như lệnh BACK (42*5/7—15)/7; b) Cho máy tính biểu thức số học

$$\frac{5}{6} \left( \frac{21}{0,56} + \frac{6}{19} \cdot 21,31 \right).$$

Những cái tên rất cần thiết

... Tên bạn tôi là Valentina. Đó không phải là một cái tên đẹp sao?
...Mèo con! Feropont, mèo, lại đây.
... Đại lượng gọi là x không thể nhận giá trị bằng 0 khi nó là mẫu số của phân số 1/x.
Tên đóng vai trò như một phương tiện thuận tiện để xác định con người, động vật, đồ vật, có thể hiểu được, biểu hiện, tức là để làm nổi bật một đối tượng cụ thể trong số những đối tượng khác cùng loại với nó. Trong ngôn ngữ lập trình, tên được gọi là định danh. Giống như trong toán học, chúng đại diện cho các biến. Mã nhận dạng trong Logo có thể là một từ tùy ý, chẳng hạn như x1, SIDE hoặc VASYA. Mã định danh, giống như lối tắt, đặt một vùng nhất định trong bộ nhớ máy tính nơi lưu trữ giá trị của biến. Để phân biệt khi nào chúng ta đang nói về một vùng bộ nhớ được đặt tên và khi nào về nội dung của nó, trong Logo, trong trường hợp đầu tiên, dấu ngoặc kép được đặt trước mã định danh biến và trong trường hợp thứ hai là dấu hai chấm. Vì vậy, mục “X” có nghĩa là tên của biến X và mục :X là giá trị của biến này.

Trong Logo có một lệnh DO đặc biệt, được gọi là lệnh gán, với lệnh này bạn có thể gán giá trị cho các biến. Ví dụ, khi thực hiện lệnh DO, "X :X+1" sẽ làm cho giá trị của biến X tăng lên 1, do đó X sẽ có giá trị 2.

Vì vậy, lệnh gán có ba phần: từ DO (từ khóa) bắt buộc, mã định danh biến và biểu thức. Lệnh này trước tiên đánh giá biểu thức đối số. Nếu nó chứa các biến thì các giá trị này từ vùng bộ nhớ tương ứng sẽ được thay thế vào biểu thức. Kết quả của phép tính trở thành một biến, mã định danh của nó nằm ngay sau từ DO. Đây là một ví dụ:

⟦folio 44⟧

Hình 2.

Bài 2. Viết chương trình tính thể tích của nhà chứa máy bay như hình vẽ hình 1.

Khi làm phép tính và thắc mắc về tên, chúng tôi hoàn toàn áp đảo Rùa của mình, chú rùa vẽ rất khéo léo… nếu được điều khiển đúng cách. Hãy dạy Rùa vẽ một “kim tự tháp” như vậy (hình 2).

Vấn đề lời giải bằng cách gọi thủ tục PYRAMID, mô tả của nó có dạng

Một biến mà không gian bộ nhớ được phân bổ cho từng biến khác nhau tại thời điểm một thủ tục được gọi được gọi là biến cục bộ của thủ tục đó. Các tham số hình thức của một thủ tục trong Logo là các biến cục bộ.

Một số thủ tục dưới đây sử dụng các tham số hình thức; điều này không được mô tả cho chương trình gọi các thủ tục này. Thật vậy, các tham số hình thức là cục bộ, có nghĩa là, bị chiếm dụng trong quá trình thực thi, một số bộ nhớ sẽ được giải phóng khi hoàn thành và có thể được sử dụng dưới bất kỳ tên nào (kể cả cùng tên) trong các thủ tục khác. Do đó, định dạng cục bộ cho phép bạn phân phối việc biên dịch một chương trình phức tạp, bao gồm cả nội dung văn bản cần thiết của các lập trình viên. Trong ví dụ sau

đây là A :X :Y
TIẾN :X PHẢI :Y TIẾN :X END
LÀM T 45
Đ :T :T*2
các biến X, Y là chính thức và các biểu thức :T và :T*2 là các tham số thực tế của thủ tục A. Tương ứng

⟦folio 45⟧

Mối quan hệ giữa tham số hình thức và tham số thực tế là vị trí: tham số hình thức đầu tiên tương ứng với tham số thực tế đầu tiên, tham số thứ hai tương ứng với tham số thực tế thứ hai, v.v.

Bây giờ chúng ta hãy quay lại phần mồi của chúng ta. Đây là Pramide
CHỮ NHẬT 80
HP V 10 P 90 V 20 L 90 R
HÌNH CHỮ NHẬT 40
NR V 10 P 90 V 10 L 90 R
HÌNH CHỮ NHẬT 20 (1)
NR V 10 P 90 V 5 L 90 R
HÌNH CHỮ NHẬT 10
KẾT THÚC

Bài toán 3. Trong chương trình (1), lệnh gọi thủ tục RECTANGLE được lặp lại bốn lần, mặc dù với một tham số thực tế khác nhưng thường xuyên thay đổi. Sau khi phân tích các mẫu của chương trình, hãy viết mô tả quy trình với tham số PRAMID:BASE, trong đó lệnh gọi thủ tục RECTANGLE sẽ được thực hiện bên trong vòng lặp. Đề xuất ít nhất hai lựa chọn cho thủ tục này. Giải thích cái nào và tại sao bạn nghĩ là tốt hơn. Sử dụng chương trình của bạn để vẽ cơ số 120.

Các lập trình viên luôn cố gắng, bất cứ khi nào có thể, làm cho chương trình của họ trở nên phổ biến.

Bài toán 4. Mở rộng khả năng của chương trình trước bằng cách mô tả quy trình vẽ một nắp có chiều cao vòng tùy ý. Sử dụng chương trình mới của bạn, vẽ hình, bao gồm hai con mồi (hình 3).

Đa giác đều

Vẽ các đa giác đều có ba, bốn, năm, ... cạnh (hình 4), dễ dàng nhận thấy với khả năng về số cạnh, hình ngày càng trở nên “tròn” hơn. Trên một hình lục giác đều, nó đã được thực hiện giống hệt như trên một bánh xe, nếu nó đủ nhỏ (hình 5)!

Góc của $n$-gon thông thường là 180-360/$n$ độ. Điều này có nghĩa là Cherenakha sau khi vẽ mỗi bên phải quay thêm một góc bằng 360/$n$ độ. Dưới đây là mô tả về quy trình xây dựng một $n$-gon chính quy tùy ý:

Đây là ĐÚNG : $N$ :SIDE
LẶP LẠI : $N$ :SIDE R 360/$N$

GỌI
ĐÚNG 4 100
sẽ vẽ một hình vuông có cạnh 100 lên màn hình và gọi
ĐÚNG 8 20
là một hình 360 cạnh đều có cạnh 20. Cuối cùng, hình của một hình 360 cạnh đều có cạnh 1 là một thử thách
ĐÚNG 360 1

Đây là sự hiện diện của một vòng tròn gần đúng do Cherenakha tạo ra, không thể quay một góc nhỏ hơn 1 độ và di chuyển khoảng cách nhỏ hơn 1 bước ốc sên. Chiều dài của vòng tròn này là 360 bước và bán kính là $R = 360/2 \pi$, tức là khoảng 57 bước. Bán kính của nó có thể tăng lên nếu cạnh được mở rộng khi sử dụng quy trình RIGHT. Nhưng bạn chỉ có thể giảm bán kính bằng cách giảm số cạnh của đa giác.

Bài toán 5. Đưa ra quy trình CIRCLE với một tham số RADIUS. Nó sẽ rút ra khả năng của một bán kính nhất định. Vị trí của Cherenakhi trên màn hình được sử dụng làm tâm của vòng tròn mà người biểu diễn phải quay lại sau khi hoàn thành bản vẽ.
