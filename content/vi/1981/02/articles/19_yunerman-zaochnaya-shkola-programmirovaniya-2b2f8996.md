---
id: 1981-2-yunerman-zaochnaya-shkola-programmirovaniya-2b2f8996
issue: kvant_1981_2
year: 1981
number: "2"
title: Trường lập trình tương ứng
authors:
  - Юнерман Н. А.
rubric: raznoe
rubric_sub: Разное
page_first: 56
page_last: 58
page_labels: 54-56
tag: K0WP
lang: vi
source: kvant_digital
extraction: vision
content_sha256: bc05da0609b68b845bc5d62cf6707521205b81d22cabdc2faa09d6c867b14039
prompt_sha256: draft-1
translated_from: content/ru/1981/02/articles/19_yunerman-zaochnaya-shkola-programmirovaniya-2b2f8996.md
source_content_sha256: c1da58971069e865e8e21aa94ee6d7e7a6fc724d3eabf4d36ca7cd511dbf42bb
translation_model: draft
translation_run: vi-draft-2026-10-31
translation_quality: draft
---

⟦folio 54⟧

Trường lập trình tương ứng

Bài 13: Xấp xỉ phương trình lời giải trên máy tính

Từ khóa học toán ở trường, bạn đã làm quen với các phương trình tuyến tính và bậc hai, gốc của chúng có thể được tìm thấy bằng cách sử dụng các công thức mà bạn đã biết. Có những công thức như vậy cho các phương trình lời giải bậc ba và bậc bốn. Nhưng phương trình được hứa hẹn có lũy thừa bậc năm trở lên không thể giải được bằng căn thức: lời giải những phương trình như vậy (trong trường hợp tổng quát) không thể được biểu thị thông qua các hệ số sử dụng các phép toán số học và trích rút căn*). Bài toán càng trở nên phức tạp hơn nếu chúng ta xét các phương trình phi đại số**). Trong trường hợp này, không thể tìm thấy các biểu thức rõ ràng cho nghiệm, với một số ngoại lệ hiếm hoi. Nhưng điều này có nghĩa là những phương trình như vậy không thể giải được?

Thông thường, để tìm nghiệm của phương trình phát sinh tại lời giải trong hầu hết các bài toán áp dụng, không cần phải có công thức chính xác. Thông thường, đối với bài toán như vậy, chỉ cần đạt được đáp số với một mức độ chính xác nhất định là đủ. Do đó, điều quan trọng là có thể sử dụng phương pháp này hoặc phương pháp khác để tính nghiệm của phương trình với độ chính xác cần thiết. Mục đích của một số phương pháp cho phương trình lời giải gần đúng đã được biết. Bài học này được dành để mô tả một số trong số họ.

Hãy xem xét một trong số chúng bằng ví dụ lời giải bài toán 26 Olympic lập trình («Kvant», 1980, Số 3): đặt F1(M) là một hàm được mô tả trên Rapier với một tham số (M). Chúng ta cần tìm và in ra tất cả các nghiệm nguyên của phương trình F1(M) = 0 nằm trên đoạn [0; 100].

Hầu hết những người tham gia Thế vận hội đều hoàn thành tốt nhiệm vụ này. Thật vậy, thuật toán lời giải của nó rất đơn giản. Trước tiên, hãy tính F1(M) cho M = 0. Nếu kết quả bằng 0 thì số 0 là nghiệm của phương trình này. Bây giờ, hãy tìm giá trị F1(M) ​​​​cho M = 1 và so sánh lại giá trị kết quả với 0. Tính tuần tự các giá trị của F1(M) cho tất cả các số nguyên M ∈ [0; 100], chúng ta sẽ tìm những giá trị mà F1(M) = 0. ​​Các giá trị này của M là nghiệm của phương trình F1(M) = 0. Lưu ý rằng trong trường hợp này, các giá trị chính xác của nghiệm đã được tìm thấy.

Việc thực hiện thuật toán này được gửi tới bất kỳ học sinh nào có khả năng tìm ra ý nghĩa của các biểu thức và so sánh chúng với số 0. Nhưng sẽ mất bao lâu để thực hiện phương trình lời giải theo cách này “bằng tay”? Điều gì sẽ xảy ra nếu vế trái của phương trình khá phức tạp và đoạn mà bạn cần tìm lời giải lớn? Đây là nơi công nghệ máy tính đến với sự trợ giúp của con người. Kiểm tra xem chương trình sau có in tất cả các phương trình số nguyên lời giải F1(M) = 0 từ đoạn [0; 100] và số lượng của chúng tích lũy trong bộ đếm gốc COUNTERCOR.

PRINT('GIẢI PHÁP TRÊN [0; 100]');
0->M; 0->BỘ ĐẾM;
TẠM BIỆT = <100::
NẾU F1(M) = 0 ĐẾN
IN(M);
BỘ ĐẾM+1 -> BỘ ĐẾM
TẤT CẢ;
1+M -> M
TẤT CẢ;
NẾU BỘ ĐẾM = 0 ĐẾN
IN('KHÔNG CÓ RỐC') TẤT CẢ;

Điều gì sẽ xảy ra nếu bạn cần tổ chức tìm kiếm lời giải được yêu cầu trên các phân đoạn khác nhau? Trong trường hợp này thì thuận tiện

⟦folio 55⟧

mô tả một quy trình có hai tham số BEGINNING và CON, tổ chức tìm kiếm tất cả các số nguyên lời giải của phương trình F1(M)=0 trên khoảng [NACH; CON].

BẮT ĐẦU TÌM KIẾM PERC;
IN('GIẢI PHÁP TRÊN [',
BẮT ĐẦU,'',CON,']');
BẮT ĐẦU—>M; 0—>BỘ ĐẾM;
TẠM BIỆT=<CON::
NẾU F1(M)=0 ĐỂ IN(M);
ĐẾM+1—>ĐẾM TẤT CẢ;
M+1—>M
TẤT CẢ;
NẾU BỘ ĐẾM = 0 ĐẾN
IN('KHÔNG CÓ RỐC') TẤT CẢ;
KSC;

Nhiệm vụ 13.1. Tạo chương trình tìm kiếm tất cả các số nguyên lời giải của phương trình X³—10X²—27X+36=0 trên các khoảng [−10; 0], [1; 100].

* Nhiệm vụ 13.2. Tạo một chương trình sẽ tìm tất cả các cặp số nguyên có dạng (X; Y), là nghiệm của phương trình 2Y—X²=4, nếu X ∈ [−50; 25], Y ∈ [100; 300].

Trước khi chuyển sang phần mô tả các phương pháp khác của phương trình lời giải, chúng ta sẽ thực hiện một số phép thay thế. Chúng ta sẽ giả sử các hàm đang được xem xét là liên tục, nghĩa là có đồ thị tuyến tính không có điểm ngắt*. Ngoài ra, chúng tôi sử dụng từ việc xem xét trường hợp đồ thị của hàm số chạm vào trục OX ở một phía (Hình 1). Khi đó dễ dàng nhận thấy **) rằng

1°. Nếu phương trình F(X) = 0 có N nghiệm khác nhau trên một khoảng nhất định thì đồ thị của hàm F cũng cắt trục OX trên khoảng này N lần (Hình 2,a).

2°. Nếu ở cuối đoạn [A; B] của hàm F lấy các giá trị khác dấu thì phương trình F(X)=0 có số nghiệm lẻ trên đoạn này (Hình 2,a), và nếu cùng dấu thì phương trình có số nghiệm chẵn (Hình 2,b,c). Lưu ý rằng trong trường hợp sau có thể không có nghiệm (0 cũng là số chẵn!).

Bạn có thể kiểm tra dấu của y F(A) và F(B) giống hay khác nhau một cách đơn giản: nếu tích F(A)·F(B) khác nhau thì F(A) và F(B) khác dấu, còn nếu dương thì chúng có cùng dấu.

Phương pháp phân chia theo vị trí

Chúng ta sẽ tìm nghiệm của phương trình F(X)=0 trên khoảng [A; B] với độ chính xác 0,001. Chúng ta sẽ giả sử rằng C là nghiệm của phương trình trong khoảng 0,001 nếu |F(C)|<0,001. (Lưu ý rằng Rapier có hàm tiêu chuẩn ABS(X) tính toán mô đun của biểu thức X.)

Tất nhiên, |F(C)|<0,001 không có nghĩa là F(C)=0; do đó "gốc của phương trình chính xác đến 0,01"

*) Định nghĩa chính xác về tính liên tục, không bắt buộc ở đây, có thể được đọc trong sách hướng dẫn “Đại số và sự khởi đầu của phân tích 9-10”, đoạn 13.
**) Chúng tôi sẽ không cung cấp bằng chứng.

⟦folio 56⟧

Hình 3.
không nhất thiết phải là gốc.
Hãy xem xét trường hợp khi có chính xác một nghiệm của phương trình trên đoạn này (để cô lập một đoạn như vậy, có các phương pháp đặc biệt; một trong số chúng sẽ được thảo luận dưới đây) và các số F(A) và F(B) có các giá trị khác nhau. Đối với định nghĩa, giả sử F(A) < 0, F(B) > 0 (Hình 3). Trung điểm của đoạn [A; B] có hoành độ C = (A + B)/2. Hãy tính |F(C)| và so sánh nó với 0,001. Nếu hóa ra |F(C)| < 0,001 thì C là số cần tìm. Nếu |F(C)| ≥ 0,001, ta tiến hành như sau: từ các đoạn [A; C] , [C; B] chọn cái ở cuối mà hàm F lấy giá trị của các ký hiệu khác nhau; Bây giờ chúng ta hãy biểu thị nó bằng [A; B]. Đảm bảo rằng đoạn mong muốn có thể được chọn bằng câu sau:
IF F(C)*F(B) < 0 TO C -> A ELSE C -> B ALL;
Do xây dựng, đối với phân khúc mới [A; B] tương ứng công bằng F(A) < 0, F(B) > 0. Người đọc có thể đã quyết định phải làm gì tiếp theo. Chúng ta hãy xem xét lại phần giữa của đoạn [A; B], ta tính giá trị của hàm F trong đó rồi so sánh

Hình 5.
mô đun của giá trị này là 0,001. Nếu giá trị mới của C thỏa mãn điều kiện |F(C)| < 0,001 thì đây là con số mong muốn. Ngược lại, lại từ hai đoạn [A; C] và [C; B] bạn cần chọn cái ở cuối mà hàm F nhận giá trị của các ký hiệu khác nhau. Quá trình được mô tả phải được tiếp tục cho đến khi tìm thấy số lượng mong muốn.

Một độc giả chú ý có thể nhận thấy rằng phương pháp này không phải lúc nào cũng cho kết quả đáp số như mong muốn: trường hợp đã lấy được gốc “giả” ở bước đầu tiên được hiển thị trong Hình 4.

Nhiệm vụ 13.3. Chiếu lời giải phương trình X³ + 3X - 1 = 0 trên khoảng [A; B] với độ chính xác EPSILON bằng phương pháp chia polyvine.

Phương pháp quay lui
Chúng ta hãy xem xét lại bài toán việc tìm kiếm nghiệm của phương trình F(X) = 0 với độ chính xác 0,001 trên khoảng [A; B], nhưng lần này chúng ta sẽ không đưa ra bất kỳ giả định nào về sự hiện diện của nghiệm trên đoạn thẳng.
Xét đoạn [A; A + H], trong đó H là số “nhỏ” tùy ý

Hình 4.
Hình 6.
