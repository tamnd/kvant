---
id: 1980-2-zvenigorodskiy-zaochnaya-shkola-programmirovaniya-c37b497b
issue: kvant_1980_2
year: 1980
number: "2"
title: Trường lập trình tương ứng
authors:
  - Звенигородский Г. А.
rubric: raznoe
rubric_sub: Разное
page_first: 55
page_last: 56
page_labels: 53-54
tag: V4AC
lang: vi
source: kvant_digital
extraction: vision
content_sha256: cb7726c962648f6c3ac6a939fec7220d8a0f873c58a034f52fdde7da9413e24e
prompt_sha256: draft-1
translated_from: content/ru/1980/02/articles/20_zvenigorodskiy-zaochnaya-shkola-programmirovaniya-c37b497b.md
source_content_sha256: 704ad5af7b1d51101a8bc860e7fd70823976bc0192acca7be3a34da5ec9b5293
translation_model: draft
translation_run: vi-draft-2026-10-31
translation_quality: draft
---

⟦folio 53⟧

Trường lập trình tương ứng

Bài 6: Mô tả và gọi các thủ tục trên Rapier

Trong bài học này, chúng ta tiếp tục nghiên cứu ngôn ngữ lập trình giáo dục và sản xuất Rapier, bắt đầu từ bài học thứ năm («Kvant», số 1).

Mô tả quy trình trong Rapier được xác định theo sơ đồ sau:

Tiêu đề theo sau các câu lệnh được phân tách bằng dấu chấm phẩy.

Dưới đây là ví dụ về mô tả quy trình trên Rapier:

PERC CHỌN A B; A+B->C; A*B->D;
NẾU C>D THÌ C->D KHÁC D->C TẤT CẢ;
KSC;

Có hai cách để gọi một thủ tục trong Rapier. Sử dụng phương pháp đầu tiên, bạn nên viết tên của thủ tục làm biểu diễn tiếp theo và đặt dấu ngoặc nhọn sau tên đó. Nếu quy trình có các tham số thì các giá trị của chúng được liệt kê cách nhau bằng dấu phẩy bên trong các dấu ngoặc này, chẳng hạn như trong Robik:

CHỌN(10,X+5);

Nếu không có tham số thì vẫn cần có dấu ngoặc đơn trong phương thức gọi này:

CÀI LẠI ( );

Nếu một thủ tục có nhiều nhất một tham số thì có thể gọi thủ tục đó theo cách thứ hai: bằng cách đặt dấu chấm trước tên thủ tục. Giá trị của tham số, nếu có, được chỉ định trước dấu chấm:

CÀI LẠI; 5. VÒNG TRÒN;

Mô tả bắt đầu bằng từ PERC (thay vì từ NHỚ THỦ TỤC trong Robik), theo sau là tên của thủ tục. Sau đó, tên tham số sẽ được liệt kê, nếu cần. Chúng cách nhau bằng khoảng trống; Ở đây không cần đến dấu ngoặc đơn và dấu phẩy được sử dụng trong Robik.

Theo sau điều này có thể là một mũi tên =>, sau đó một tên khác được chỉ định - cái gọi là tên kết quả. Trong bài học này chúng ta sẽ xem xét các thủ tục không sử dụng tên kết quả. Vì vậy, chúng ta sẽ hoãn việc phân tích cách xây dựng này cho đến bài học tiếp theo.

Từ PROC, tên thủ tục, tham số và tên kết quả tạo thành cái gọi là tiêu đề thủ tục. Sau đó

Rapier cung cấp một số lượng lớn các thủ tục tiêu chuẩn có thể được gọi trong bất kỳ chương trình nào. Đặc biệt, chúng bao gồm thủ tục PRINT, có thể có bất kỳ số lượng tham số nào. Kết quả của việc sử dụng quy trình này là các giá trị của tất cả các tham số sẽ được in trên một dòng mới, gần nhau (giống như trong lệnh PRINT bằng ngôn ngữ Robik). Tất cả các quy trình của hệ thống đồ họa Shpag, được mô tả trong bài viết của A. Salikhova và N. Sokolova trên số trước của tạp chí, cũng là tiêu chuẩn.

Hãy xem xét một số ví dụ:

1°. Giả sử chúng ta cần viết chương trình trên Rapier bằng cách sử dụng

⟦folio 54⟧

Dựa trên các quy trình của hệ thống Lời nói, đây là hình ảnh của robot:

MÃ 211500000055 KHÓI 61M5 TẤM 7
NGÀY 22/06/79 63 GIỜ 19/49/31

Tất nhiên, điều này có thể được thực hiện chỉ bằng cách sử dụng tia và dây dẫn. Tuy nhiên, trong trường hợp này chương trình sẽ khá lớn. Nó có thể giảm đi đáng kể nếu chúng ta thay thế hình đó được lặp lại nhiều lần trong hình - một hình chữ nhật. Vì vậy, chỉ cần mô tả quy trình TRỰC TIẾP một lần và sau đó vẽ bất kỳ hình chữ nhật mong muốn nào là đủ. Quy trình bên dưới có bốn tham số: X, Y, B và D, X và Y là tọa độ của góc dưới bên trái, B là chiều cao và D là chiều dài của hình chữ nhật:

PERC TRỰC TIẾP X Y TRONG D;
P(X;Y); L(X+D,Y); L(X+D; Y+B);
L(X,Y+B); L(X,Y); KSC;

Bây giờ chương trình vẽ có thể được viết rất đơn giản:
P(50,50); TRỰC TIẾP(10,10,30,30);
TRỰC TIẾP(20,15,5,10); TRỰC TIẾP(23,23,4,4);
TRỰC TIẾP(15,30,5,7); TRỰC TIẾP(28,30,5,7);
TRỰC TIẾP(17,31,3,3); TRỰC TIẾP(30,31,3,3);
.KẾT THÚC;

2°. bài toán tiếp theo là lấp đầy kích thước 100 x 100 mm bằng lưới hình chữ nhật với bước 5 mm theo chiều dọc và chiều ngang (ví dụ: lưới như vậy có thể đóng vai trò là lưới tọa độ). Thật thuận tiện khi sử dụng vòng lặp ở đây:
P(100.100); 5—>A; KHI A=<100::
P(A,0); L(A,100); P(0,A); L(100,A),
A+5—>A TẤT CẢ; .KẾT THÚC;

3°. Một ví dụ khác về việc sử dụng vòng lặp là in bảng cửu chương:
2—>A; 2—>B;
IN('BẢNG NHÂN'),
KHI A=<10:: KHI B=<10::
