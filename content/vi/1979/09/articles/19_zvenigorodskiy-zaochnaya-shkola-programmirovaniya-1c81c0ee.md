---
id: 1979-9-zvenigorodskiy-zaochnaya-shkola-programmirovaniya-1c81c0ee
issue: kvant_1979_9
year: 1979
number: "9"
title: Trường lập trình tương ứng
authors:
  - Звенигородский Г. А.
rubric: raznoe
rubric_sub: Разное
page_first: 54
page_last: 59
page_labels: 52, 53, 54, 55, 57
tag: RFIH
lang: vi
source: kvant_digital
extraction: vision
content_sha256: a2986c1ef52095ba25b21de6c716c9ac9bddff758f7d96f4c61f851a85c3e51a
prompt_sha256: draft-1
translated_from: content/ru/1979/09/articles/19_zvenigorodskiy-zaochnaya-shkola-programmirovaniya-1c81c0ee.md
source_content_sha256: c5b4aad025a878f4e62fad4ebce8e7849ed55b7a4635a36ba72c244d39ba639d
translation_model: draft
translation_run: vi-draft-2026-10-31
translation_quality: draft
---

⟦folio 52⟧

Luật lập trình.
Quy tắc viết đơn thuốc bằng ngôn ngữ Robik
Trường lập trình tương ứng

Bài 1

Các chương trình được viết bằng hầu hết các ngôn ngữ lập trình hiện đại bao gồm các câu lệnh riêng biệt - giống như các văn bản bằng ngôn ngữ “con người” thông thường. Hầu hết độc giả «Kvant» có lẽ nhớ rằng hầu hết mọi giới từ trong tiếng Nga đều có thể được phân thành một trong ba nhóm lớn: giới từ trần thuật, giới từ nghi vấn và giới từ cảm thán. Sẽ thuận tiện hơn cho Ham khi coi giới từ được gọi là câu phát biểu, câu hỏi và mệnh đề. Chúng ta có thể nói rằng một câu hỏi là một mệnh đề có thể được trả lời. Ví dụ về các câu hỏi:

Anh ta là người như thế nào, cái gã khốn nạn này? Có thật là rất tức giận không? Có phải anh ta đang đi theo tiếng còi? Và nếu vậy thì tại sao? Anh ấy có thích heo con không? Và anh ấy yêu họ như thế nào?

Một mệnh đề là một mệnh đề mà khi hỏi nó đúng hay sai thì có ý nghĩa. Ví dụ:

Winnie the Pooh sống tốt trên thế giới!
2+2=4.

Con mèo Matroskin không thể trả lời điện thoại, nó đang rất bận, nó đang nằm trên bếp.

Đơn thuốc là một đề xuất mà bạn có thể đặt câu hỏi: thực hiện nó như thế nào? Ví dụ:

Hãy gọi Kota Matrosin vào điện thoại!

Nâng mí mắt của tôi lên!

Đừng mở miệng, Heo con, nếu không xà phòng sẽ lọt vào đó.

Xin vui lòng cho tôi biết bây giờ là mấy giờ rồi.

Có một giai thoại được biết đến rộng rãi về một nhà vật lý nổi tiếng, sau khi có một bài giảng xuất sắc, đã hỏi nhân viên của mình xem họ có câu hỏi gì không.

Một trong những người có mặt nói: “Tôi không hiểu làm thế nào bạn có được công thức này.

Giảng viên trả lời: “Đây là một câu khẳng định, không phải một câu hỏi”. - Bạn có câu hỏi nào không?

Trong hầu hết các ngôn ngữ lập trình, một giới từ độc lập cũng có thể là một giới từ: nếu một robot cần được giao một nhiệm vụ (và theo định nghĩa, một chương trình là thức ăn của robot hoặc máy tính), thì mỗi giới từ phải sao cho có thể sử dụng theo đúng nghĩa đen - nó phải là một mệnh đề.

Bạn có thể nói với robot:

- Hãy nhớ rằng 2+2=4.

Không nên nói với anh ấy:

2+2=4.

Đơn giản là anh ta sẽ không biết phải làm gì với một tuyên bố như vậy.

Một tuyên bố ngắn gọn về quy tắc này được gọi là luật lập trình đầu tiên:

Chương trình bao gồm các quy định.

Rõ ràng, để biên dịch các chương trình thực tế cho các robot hoặc máy tính cụ thể, việc nhớ công thức của định luật thứ nhất là chưa đủ, mặc dù tầm quan trọng của nó: bạn cũng cần biết những quy định nào mà những robot và máy móc cụ thể này phải sử dụng và những quy tắc này được viết theo những quy tắc nào.

Hướng dẫn dành cho bất kỳ thiết bị máy tính nào phải liệt kê các hướng dẫn có thể được sử dụng bởi các thiết bị này. Danh sách như vậy được gọi là hệ thống quy định (viết tắt là SPR).

Vì vậy: hệ thống mệnh lệnh là tập hợp các mệnh lệnh mà robot hoặc máy tính hiểu và có thể sử dụng.

Ví dụ: một hệ thống quy định cho robot RD-1, có thể sử dụng

⟦folio 53⟧

vào mỗi giờ nghỉ học, trách nhiệm của lớp trưởng có thể như sau:

Hệ thống viết trước RD-1

MỞ CỬA SỔ; ƯỚT GIẢI;
ĐÓNG CỬA SỔ; XÓA KHỎI BẢNG;
NGỒI XUỐNG;

Với các hệ thống viết trước, có mối liên hệ với quy tắc quan trọng nhất, được gọi là luật lập trình thứ hai:

Trong các chương trình dành cho bất kỳ robot và máy tính nào, bạn có thể sử dụng những đơn thuốc đó và chỉ những đơn thuốc đó có trong hệ thống đơn thuốc của chúng.

Một vài lời về các quy tắc ngữ pháp. May mắn thay, trong các ngôn ngữ lập trình, có ít ngôn ngữ này hơn nhiều so với ngôn ngữ tiếng Nga, nhưng chúng phải được tuân thủ rất nghiêm ngặt. Máy tính giữ chân người giáo viên nghiêm khắc nhất, và một dấu phẩy bị thiếu có thể phá hỏng công việc của một chương trình lớn và đẹp đẽ một cách vô vọng.

Robot hoặc máy tính có thể được dạy một hoặc nhiều ngôn ngữ lập trình. Trong trường hợp này, các tập lệnh trước của ngôn ngữ này (ngôn ngữ) sẽ được thêm vào SPR của chúng.

Quy tắc chung là viết trước bắt đầu trên một dòng mới.

2. Cuối phần viết trước có dấu chấm phẩy (;).

1. Mỗi đơn thuốc bắt đầu trên một dòng mới.

2. Cuối phần viết trước có dấu chấm phẩy (;).

*) Ngôn ngữ Robik được mô tả ở đây là phiên bản rút gọn của ngôn ngữ Robik-3, được sử dụng để dạy học sinh tại các trường Kharkov và Novosibirsk cho các chương trình trẻ.

Người đọc chú ý có thể ngạc nhiên vì thiếu quy tắc viết hoa. Điều này được giải thích một cách đơn giản: để máy tính hoặc robot sử dụng tính năng viết trước, nó phải được gõ trên các phím của thiết bị đầu cuối hoặc thiết bị tương tự khác và các chữ cái trên bàn phím chỉ được viết hoa; do đó, người ta hoàn toàn không quan tâm đến những bức thư sẽ được viết trên tạp chí; ở đây chúng ta sẽ viết chúng bằng chữ in hoa và chữ cái, nhưng khi hoàn thành nhiệm vụ của mình, chữ viết trước có thể được viết theo quy tắc của tiếng Nga: chữ cái đầu tiên là chữ in hoa, sau đó là chữ thường.

Bây giờ, khi đã biết các quy tắc chung để viết mệnh đề bằng ngôn ngữ Robik, chúng ta có thể soạn chương trình đầu tiên cho robot RD-1 được mô tả ở trên, chương trình này phải được xóa khỏi đế và kiểm tra lớp trong giờ giải lao.

Ví dụ về bot của một chương trình đúng:

MỞ CỬA SỔ;
ƯỚT GIẢI;
XÓA KHỎI BẢNG;
ĐÓNG CỬA SỔ;
NGỒI XUỐNG;

Nhiệm vụ 1.1. Trong số các ví dụ dưới đây có các yêu cầu bộ nhớ chính xác và tất cả các lỗi trong các chương trình khác đều được liệt kê.

Chương trình A
1. XÓA KHỎI BẢNG;
2. ƯỚT GIẢI;
3. MỞ CỬA SỔ;
4. ĐÓNG CỬA SỔ;
5. NGỒI XUỐNG;

Chương trình B
ƯỚT GIẢI;
MỞ CỬA SỔ;
XÓA KHỎI BẢNG;

⟦folio 54⟧

ĐÓNG CỬA SỔ;
NGỒI XUỐNG;

Chương trình C
MỞ CỬA SỔ;
ƯỚT GIẢI;
LAU TỪ BẢNG;
QUÉT SÀN;
NGỒI TẠI BÀN LÀM VIỆC CỦA BẠN;

Chương trình D
MỞ CỬA SỔ;
ƯỚT GIẢI;
NGỒI XUỐNG;

Chương trình E
ƯỚT GIẢI
XÓA KHỎI BẢNG
NGỒI XUỐNG

Hãy thử tưởng tượng RD-1 sẽ sử dụng chương trình của chúng ta như thế nào. Giả sử robot đang ngồi ở bàn trong lớp học và thiết bị đầu cuối Videoton-340 được lắp đặt ở bàn bên cạnh. Robot bắt đầu đối thoại. Ngay khi bạn nhấn nút chuyển, thông báo đầu tiên của nó sẽ xuất hiện trên màn hình terminal:
XIN CHÀO! TÔI LÀ ROBOT RD-1!
TÔI SẴN SÀNG LÀM VIỆC!
Sau đó, robot hiển thị dấu hoa thị (*), nghĩa là nó đã sẵn sàng nhận đơn thuốc đầu tiên. Chúng tôi đang tuyển dụng

MỞ CỬA SỔ;
Sau dấu chấm phẩy, nhấn phím “ETX” (đây là tên viết tắt của từ tiếng Anh “end of text” - cuối văn bản). Robot đọc dòng trên màn hình terminal và bắt đầu sử dụng nó: đứng dậy khỏi vị trí, đi đến cửa sổ, v.v. Khi đơn hàng được thực hiện, robot sẽ dừng lại và dấu hoa thị sẽ xuất hiện lại trên màn hình. Và cứ như vậy cho đến hết chương trình.

Nếu hệ thống quy định nhỏ thì việc đánh số các quy định thường thuận tiện và sử dụng những con số này để quản lý toàn bộ văn bản với nhau. Chúng tôi sẽ gọi các lệnh hướng dẫn được bảo vệ như vậy. Và hệ thống chỉ dẫn biến thành hệ thống mệnh lệnh. Ví dụ, chúng tôi đưa ra hệ thống chỉ huy của xe tự hành Kibik:

Văn bản hướng dẫn lệnh

1 LÁI XE 100 MÉT
2 Rẽ PHẢI
3 Rẽ TRÁI
0 HOÀN THÀNH CÔNG VIỆC

Không giống như yêu cầu của ngôn ngữ Robik, các lệnh như vậy có thể được viết trên một dòng. Ký hiệu chương trình nhỏ gọn nhưng khó hiểu: 1113113112111211211211211210.

Nhiệm vụ 1.2. Trên một tờ giấy có kích thước 10 x 10 cm, vẽ đường đi mà Kibik đã đi khi sử dụng chương trình này, nếu tọa độ tốt nhất nằm ở góc dưới bên trái, trục song song với các cạnh của tờ giấy, tỷ lệ là 1: 10000 (1 cm là 100 m), và tại thời điểm ban đầu Kibik đang ở một điểm có tọa độ (800, 500) (tính bằng mét) và hướng lên trên, m. đ. dọc theo chiều dương của trục thứ tự.

Điều quan trọng cần lưu ý là các lượt được Kibik thực hiện ngay tại chỗ và bên phải và bên trái do anh ấy xác định liên quan đến hướng chuyển động của anh ấy.

Nhiệm vụ 1.3. Xác định xem Kibik đang thực hiện chương trình nào nếu đường đi của anh ấy là cực đại, như trong Hình 6*). Các điều kiện ban đầu là như nhau, con số giảm đi một nửa.

Hình 6.

*) Hình 6 được vẽ bằng máy vẽ của hệ thống Shpar (chúng ta sẽ nói về hệ thống này ở một trong các vấn đề sau). Học sinh lớp 3-4 A. Ershov, S. Pustoshilov và A. Filatova từ Trường Lập trình viên Trẻ Novosibirsk được cho đáp số cho nhiệm vụ 1.3; do đó đáp số họ đã biên soạn một chương trình cho hệ thống đồ họa của Shpar, theo đó Hình 6 được vẽ ra, tức là tác phẩm của Kibik đã được “mô hình hóa”.

⟦folio 55⟧

Hệ thống kê đơn linh hoạt, sơ đồ cú pháp và trường biến

Bài 2

Đối với các máy tính và robot đa năng có hệ thống hướng dẫn lớn, đối tượng hướng dẫn của chúng có tầm quan trọng rất lớn. Cho đến nay, chúng ta đã thiết lập SPR một cách “cứng”: bằng cách liệt kê trực tiếp tất cả các hướng dẫn được phép. Rõ ràng đây không phải là cách tốt nhất: việc xác định các tập hợp lớn một cách cứng nhắc là bất tiện hoặc không thể thực hiện được. Không thể mô tả theo cách này, ví dụ, ngay cả việc cộng các số nguyên tùy ý. Rốt cuộc, đối với mỗi cặp số được thêm vào, phải cung cấp một đơn thuốc riêng trong SPR.

Tuy nhiên, qua môn toán, chúng ta biết rằng phép liệt kê không phải là cách duy nhất để định nghĩa một tập hợp. Thông thường hơn, một mô tả “linh hoạt” được sử dụng: một công thức hoặc quy tắc được viết cho phép người ta lấy tất cả các phần tử của một tập hợp hoặc kiểm tra xem một đối tượng không phải tác nhân có thuộc tập hợp này hay không. Bài học thứ hai dành cho một trong những cách mô tả DSS “linh hoạt” - sơ đồ cú pháp.

Sơ đồ cú pháp là một quy tắc để xây dựng một đơn thuốc, được đưa ra dưới dạng đồ họa. Sơ đồ cho thấy những bộ phận nào có thể được sử dụng để xây dựng một đơn thuốc và các bộ phận này nên được sắp xếp theo thứ tự nào. Sơ đồ cú pháp bao gồm các trường riêng lẻ được kết nối bằng các mũi tên. Mỗi trường như vậy (thường là một từ, số hoặc ký hiệu) là một phần của đơn thuốc và các mũi tên hiển thị thứ tự các phần này có thể được kết nối. Mỗi sơ đồ có điểm bắt đầu, ký hiệu là H và điểm kết thúc, ký hiệu là K.

Để có được các quy tắc kê đơn bằng sơ đồ cú pháp, bạn cần kiểm tra

bất kỳ đường dẫn nào từ điểm bắt đầu đến điểm kết thúc, di chuyển nghiêm ngặt theo hướng mũi tên và viết thành một hàng tất cả các trường gặp dọc theo đường dẫn này. Ví dụ: sơ đồ cú pháp cho mục nhập Kibik, được mô tả ở cuối bài học đầu tiên, có thể trông như thế này:

CHƯƠNG TRÌNH 2

Xin lưu ý rằng sơ đồ thứ hai mô tả hai hướng dẫn cùng một lúc: rẽ phải và rẽ trái. Vì có hai cách để đi từ điểm bắt đầu đến điểm kết thúc nên chương trình sẽ chọn tùy chọn cần sử dụng trong từng trường hợp cụ thể.

Một cách khác để có được các quy định khác nhau từ một sơ đồ là sử dụng các trường biến đổi.

Trường biến là một phần của sơ đồ mà khi biên dịch chương trình phải được thay thế bằng một văn bản khác từ một tập hợp không được chỉ định. Trên sơ đồ cú pháp, các trường biến được biểu thị bằng hình bầu dục, các từ và ký tự cần được viết lại chính xác vào văn bản chương trình (cái gọi là rửa sau trường) được biểu thị bằng một hình chữ nhật.

Ví dụ: trong DSS của một trong các robot, sơ đồ sau có thể xuất hiện:

CHƯƠNG TRÌNH 3

⟦folio 57⟧

Nhiệm vụ 2.4. Một trường biến được mô tả bằng sơ đồ sau:

ĐỀ ÁN 6

Ở đây, ký tự là một chữ cái, số hoặc bất kỳ ký hiệu nào có sẵn trên bàn phím đầu cuối, ngoại trừ dấu anostrophe (').

Văn bản ví dụ:
'ĐÂY LÀ VĂN BẢN ĐÚNG'
Cho bốn ví dụ về văn bản đúng và xác định xem sơ đồ có cho phép văn bản trống hay không'

Nhiệm vụ 2.5. Số thực trường biến trong ngôn ngữ Robik được mô tả bằng sơ đồ:

ĐỀ ÁN 7

(Trong các ngôn ngữ lập trình, người ta thường tách phần nguyên khỏi phần phân số bằng dấu chấm chứ không phải dấu phẩy, như trong toán học ở trường.) Số thực nào sau đây được lấy từ sơ đồ này:
5.3—52.0 10.00000+50—54. +2,11/25.
Cho bốn ví dụ về ký hiệu đúng cho số thực trong Robik.

Nhiệm vụ 2.6. Vẽ sơ đồ đồng bộ mô tả dạng toán học tổng quát của cách viết số thực. Xin lưu ý rằng trong toán học, số nguyên là trường hợp đặc biệt của số thực, nhưng trong Robik thì không phải vậy: các số không có phần phân số không nên được viết bằng sơ đồ.

Nhiệm vụ 2.7. Vẽ sơ đồ cho trường biến trong Robik có giá trị có thể là số nguyên hoặc số thực.

Nhiệm vụ 2.8. Hệ thống của robot Kibik-2 theo quy định được mô tả bằng sơ đồ:

CHƯƠNG TRÌNH 8

Kibik-2 tọa lạc tại điểm A (800, 500) và được triển khai dọc theo hướng dương của trục tọa độ. Anh ta phải ghé thăm các điểm: B (800, 800), C (300, 200), D (925, 931) và quay lại điểm A.

Sau khi tiếp cận điểm tiếp theo, Kibik-2 sẽ hiển thị thông báo về điều này trên thiết bị đầu cuối, ví dụ:
'TÔI ĐẾN ĐIỂM A'
Tạo một chương trình.

G. Zvenitsgorodsky
