---
id: 1980-7-evm-na-olimpiade-5fa392b2
issue: kvant_1980_7
year: 1980
number: "7"
title: Máy tính tại Thế vận hội
rubric: raznoe
rubric_sub: Разное
page_first: 33
page_last: 37
page_labels: 31, 32, 34, 35
tag: N98R
lang: vi
source: kvant_digital
extraction: vision
content_sha256: 511c6d3e6e9b36c52a3981e8f7a17e622197f8a90c23ed0c8f15aa00c83a60b4
prompt_sha256: draft-1
translated_from: content/ru/1980/07/articles/11_evm-na-olimpiade-5fa392b2.md
source_content_sha256: 80473de9113fda7a008c54e760b06d4b0fae98afb0161d9ce7bbbed7cb99659b
translation_model: draft
translation_run: vi-draft-2026-10-31
translation_quality: draft
---

⟦folio 31⟧

Máy tính tại Olympic

Các ứng dụng thể thao của máy tính rất rộng rãi - từ phân tích thống kê kết quả của một giải vô địch bóng đá đến vẽ sơ đồ phòng thủ và tấn công, từ lập lịch thi đấu cho một giải đấu bóng rổ đến xử lý kết quả theo dõi trạng thái tâm sinh lý của các vận động viên, từ dự đoán kết quả của các trận đấu thể thao đến soạn thảo các giao thức cho các trận đấu quyền anh.

Tại Thế vận hội Olympic XXII ở Moscow, máy tính sẽ là thành viên đầy đủ của Ban tổ chức, ban giám khảo và trung tâm báo chí.

Phần “Nghệ thuật lập trình” của số Olympic «Kvant» trình bày câu chuyện về hai bài toán Olympic thông thường được giải bằng máy tính đi đầu trong các trận đấu thể thao - tại bàn giám khảo trong khu vực khóa của sân vận động và trên đường đấu kiếm. Dưới đây là các thuật toán của hai bài toán liên quan đến việc xử lý các tài liệu vận hành về điều kiện thể thao. Các thuật toán này đã từng được lập trình bằng Cobol và BASIC - những ngôn ngữ lập trình quen thuộc với một số độc giả của chúng tôi, nhưng trong mọi trường hợp, vẫn chưa được mô tả trên các trang của Trường Lập trình Tương ứng Lượng tử.

Chúng tôi đề xuất tạo một chương trình cho từng thuật toán này bằng ngôn ngữ Rapier, ngôn ngữ quen thuộc với người đọc «Kvant» từ các bài 5-8 của Trường Lập trình Tương ứng («Kvant», 1980, Số 1-3). Bạn có thể gửi các chương trình của mình đến cùng địa chỉ mà bạn viết thư cho Trường Truyền thông.

Robik và Rapier mà bạn đã học trong các bài học của Trường Tương tác, là các ngôn ngữ lập trình tương tác: bạn có thể soạn, chạy và sửa các chương trình bằng các ngôn ngữ này trực tiếp từ bảng điều khiển đầu cuối.

Trong các ví dụ về chương trình được đưa ra trong các bài học của Trường Tương tác, giả định rằng tác giả của chương trình, hoặc trong mọi trường hợp, một người dùng quen thuộc với ngôn ngữ lập trình liên quan, đang làm việc tại thiết bị đầu cuối. Các bài báo đăng trên số này nói về các chương trình được sử dụng bởi trọng tài và vận động viên, tức là những người dùng, theo quy định, không quen với lập trình.

Vì vậy, cuộc đối thoại phải được tổ chức để người dùng không phải suy nghĩ về bài tập, lệnh gọi thủ tục và các tính năng khác của chương trình. Nếu trong khi chương trình đang chạy, bạn cần tìm hiểu ý nghĩa của một tên nào đó từ người dùng, thì bạn phải sử dụng hàm INPUT tiêu chuẩn. Ví dụ, nếu trong một quá trình nào đó người vận hành

NHẬP(0)→HỌ;

sau đó lời mời đối thoại sẽ xuất hiện trên màn hình đầu cuối - biểu tượng “-” và máy sẽ đợi người dùng gõ văn bản mong muốn trên bàn phím. Văn bản này sẽ được coi là kết quả của hàm, nghĩa là nó sẽ được gán tên HỌ.

Nếu số 0 được chỉ định làm tham số của hàm INPUT, như trong ví dụ trên, thì trên các trang của chương trình Trường Tương ứng Lượng tử, văn bản sẽ được xem xét, tức là các dòng được thêm vào nó ở bên phải và bên trái. Ví dụ: nếu người dùng trong đáp số trong lời mời đã nhập từ IVANOV thì giá trị của tên SURNAME sẽ là văn bản 'IVANOV' và nếu người dùng nhập 510, giá trị của tên sẽ là văn bản '510'.

Trong trường hợp bạn cần hỏi người dùng một số mà sau đó bạn sẽ thực hiện một số phép tính số học, tham số

⟦folio 32⟧

Hàm ENTER phải là một chứ không phải bằng 0.

Hãy đưa ra một ví dụ về một quy trình nhỏ sử dụng chức năng INPUT và nhật ký cuộc đối thoại của người dùng với máy tính khi thực hiện quy trình này.

Giả sử bạn cần điền họ, số điện thoại cũ và tên quốc gia. Thật thuận tiện khi điền thông tin về từng phần dưới dạng một bộ dữ liệu và thông tin về tất cả các phần tạo thành các bộ dữ liệu như vậy. Hãy đặt tên cho bộ này là LIST. Trong ví dụ bên dưới, văn bản được máy in có phông chữ màu đỏ.

KỶ LỤC PHẦN TRĂM;
<* *> -> DANH SÁCH;
PRINT('CHÈN SỐ NGƯỜI THAM GIA');
NHẬP (1) -> SỐ; 1 -> BỘ ĐẾM;
TẠM BIỆT BỘ ĐẾM = <SỐ::
IN('HỌ CỦA NGƯỜI THAM GIA');
NHẬP (0) -> HỌ;
IN('SỐ BẮT ĐẦU');
IN('Quốc gia'); NHẬP(0) ->

QUỐC GIA;
BỘ ĐẾM+1 —> BỘ ĐẾM;
— DANH SÁCH+<*<HỌ, SỐ.
QUỐC GIA>*>—DANH SÁCH;
TẤT CẢ
KSC:
GHI CHÚ:
NÊU SỐ LƯỢNG NGƯỜI THAM GIA
—3
HỌ CỦA NGƯỜI THAM GIA
— IVANOV
SỐ BẮT ĐẦU
—15
QUỐC GIA
—Liên Xô
HỌ CỦA NGƯỜI THAM GIA
— LEROY
SỐ BẮT ĐẦU
—17
QUỐC GIA
-PHÁP

Kết quả là sẽ hình thành một bộ DANH SÁCH: <*< IVANOV, 15, Liên Xô>, <LEROY, 17, PHÁP>*>

Xin lưu ý rằng ở đây chúng tôi không hiển thị ví dụ về chương trình in danh sách các trang web. Lập trình các phép tính đẹp, “có định dạng” là khá nghiêm túc bài toán, điều này sẽ được xem xét trong các bài học Trường Tương ứng của chương trình vào «Kvant» sau kỳ nghỉ hè. Nhưng tất nhiên, điều này không ngăn cản bạn cố gắng tìm cách hiển thị đẹp mắt các danh sách, bảng và giao thức.

Vì vậy, hãy cố gắng áp dụng kiến ​​thức của bạn về Rapra và các quy tắc nhập liệu đã được dạy cho bạn ngày hôm nay. Độc giả gửi chương trình thể thao hay nhất sẽ được tặng quà lưu niệm Olympic.

Giới thiệu các tác giả phát biểu hôm nay trong chuyên mục “Nghệ thuật lập trình”:

Yu. A. Pervin, ứng cử viên khoa học kỹ thuật, nhà nghiên cứu cao cấp tại Trung tâm Máy tính của Chi nhánh Siberia của Viện Hàn lâm Khoa học Liên Xô, giám khảo của thể loại cộng hòa trong môn điền kinh, đã viết về những bước nhảy cao;

Ilona Lapushonok, sinh viên năm thứ ba tại Viện Vật lý và Công nghệ Moscow, thành viên câu lạc bộ đấu kiếm Siberia “Victoria”, nói về đấu kiếm; Cô đã thực hiện một chương trình dành cho khách du lịch của câu lạc bộ khi cô đang học lớp 10 tại 130 trường học ở Novosibirsk.

⟦folio 34⟧

Danh sách vận động viên được kêu gọi thử sức có thể không đầy đủ: theo quy định, một số vận động viên có thể vượt qua độ cao ban đầu.

Nếu người tham gia được gọi không thành công trong lần thử, trọng tài sẽ đánh dấu “—”, dấu này được chương trình ghi lại ở những vị trí được cung cấp để đánh dấu kết quả của lần thử tương ứng ở độ cao này.

Một nỗ lực không thành công sẽ được trọng tài đánh dấu bằng cách nhập biểu tượng “×”. Nếu “×” có cùng độ cao nghĩa là người tham gia đã không vượt qua được độ cao này và kết thúc cuộc thi (thông tin này được lưu trong bộ nhớ của máy

Điều này được chuyển đổi thành dấu sau “.”).

Nếu người tham gia từ bỏ một hoặc hai lần thử còn lại và di chuyển chúng lên độ cao tiếp theo, thì ở độ cao tiếp theo, anh ta có thể nhận được dấu “.” sau, tương ứng, hai hoặc một nudacc. Kết quả một vận động viên hoàn thành cuộc thi được coi là chiều cao cao nhất mà anh ta đạt được. Dấu dịch vụ "." (“kết thúc”) cho phép máy tính chỉ mời những người tham gia tiếp tục cuộc thi nhảy (họ không có dấu “.”). Sau khi hoàn thành tất cả các lần nhảy, trước khi đếm kết quả hãy đánh dấu "." phải được xóa đi.

Nỗ lực thành công - chinh phục độ cao - trọng tài dùng nước đánh dấu biểu tượng “√”.

Cấu trúc dữ liệu có thể được mô tả dễ dàng, vì vậy hãy sử dụng biểu mẫu giao thức (xem bảng). Người anh hùng trong cuốn tiểu thuyết của I. Ilf và E. Petrov “Con bê vàng” có thể tham gia một cuộc thi ở thành phố như vậy. Tất nhiên, kết quả thể thao thấp hơn đáng kể so với kết quả Olympic: xét cho cùng, cả O. Bender rất năng động và A. Koreiko chu đáo, người quan tâm đến hình thức thể thao của mình, đều không từng tuyên bố giành huy chương Olympic. Chương trình này, được biên soạn theo các thông số kỹ thuật đã định, có thể phục vụ thành công như nhau

Nghị định thư của cuộc thi nhảy cao trong giờ giải lao ở Chernomorsk
Sân vận động Olympus, ngày 19 tháng 7 năm 1980

| KHÔNG. | Họ của người tham gia | Số bắt đầu | Câu lạc bộ thể thao | Kết quả |
| :--- | :--- | :--- | :--- | :--- |
| 1. | Ptiburdukov | 114 | Pegasus | X X V X X V X V |
| 2. | máy uốn cong | 116 | linh dương | — — — X V V V |
| 3. | Lokhankin | 117 | Lời của quạ | — — — V V V |
| 4. | Berlaga | 118 | Hercules | V V V V X X V X X X |
| 5. | Borisholsky | 122 | Hercules | V V V X X V X X X |
| 6. | Bomze | 123 | Hercules | X V X X X X X X |
| 7. | Koreiko | 124 | Hercules | V V X X V X X X |
| 8. Panikovsky | 127 | linh dương | X X V V V V V |
| 9. Giggenshivili | 128 | Lời của quạ | V V V V X X V X X |

Trưởng ban giám khảo cuộc thi
A. Balaganov

⟦folio 35⟧

Sống cả trường chuyển trường và Thế vận hội Olympic.

Để mô tả dữ liệu, sẽ rất hữu ích khi sử dụng các khái niệm được giới thiệu bằng ngôn ngữ Rapier («Kvant», 1980, Số 2). Một vài khuyến nghị:

— Kết quả của mỗi người tham gia ở cùng một độ cao, nghĩa là thông tin về việc anh ta hoàn thành, nói chung, ba lần thử, được biểu diễn dưới dạng một bộ dữ liệu

" CHIỀU CAO, 'THỬ'"

ở đây HEIGHT là giá trị (tính bằng cm) của chiều cao bên dưới thanh và 'ATTEMPTS' là một chuỗi gồm ba ký tự; ý nghĩa của các ký tự này có thể là dấu “×”, “√”, “—” hoặc dấu cách; nếu THỬ chỉ chứa thông tin về một hoặc hai lần thử (ví dụ: độ cao đã được lấy trong lần thử đầu tiên, do đó, không cần phải chính xác hoặc đánh dấu đúng vị trí cho các lần thử còn lại của độ cao này), thì một khoảng trắng sẽ được viết thay cho các lần thử còn lại, ví dụ:

<190, '××√'>, <195, '√—'>, <200, '——'>

(ký hiệu “—” là hình ảnh của một không gian không đáng kể).

— Tổng số kết quả của một người tham gia được biểu thị bằng một bộ có tên là KẾT QUẢ và các phần tử của nó là các kết quả riêng lẻ.

— Mỗi dòng của giao thức là thông tin về một người tham gia; chúng tạo thành một bộ dữ liệu gọi là NGƯỜI THAM GIA:

<№, HỌ, SỐ BẮT ĐẦU, CÂU LẠC BỘ THỂ THAO, KẾT QUẢ, KẾT QUẢ TỐT NHẤT, ĐỊA ĐIỂM>

- Tập hợp các bộ dữ liệu PARTICIPANT tạo thành một tập hợp có tên PROTOCOL, trên thực tế, nó đại diện cho kết quả của chương trình - đây là một tập hợp được in dưới dạng một bảng hoàn chỉnh.

— Bộ PARTICIPANT chỉ cần thiết để tạo ra kết quả cuối cùng; đối với giai đoạn trung gian phải bổ sung thêm thông tin về người tham gia

a) chuỗi một ký tự DỊCH VỤ MARK, các giá trị của nó có thể là “.”, “!”, “*” hoặc khoảng trắng.

6) giá trị nguyên SỐ LƯỢNG THẤT BẠI,

c) giá trị số nguyên TỔNG SỐ LƯỢNG THỬ;
hai giá trị cuối cùng được sử dụng trong chương trình khi áp dụng quy tắc 3 và 4 để phân bổ địa điểm.

Hãy thử tạo một chương trình trên Rapila xử lý các giao thức cho các cuộc thi nhảy cao và bao gồm ba phần (không đồng đều):

1) nhập phần cố định của giao thức - số sê-ri, tên và số bắt đầu của người tham gia, liên kết câu lạc bộ của họ;

2) nhập kết quả cuộc thi - điền vào phần trung tâm của giao thức;

3) phân bổ người tham gia theo địa điểm - điền vào các cột cuối cùng của giao thức.

Để lập trình phần thứ hai của chương trình, sẽ rất hữu ích khi phân tích bản in các đoạn hội thoại giữa giám khảo và máy tính diễn ra tại các cuộc thi của chúng tôi (tin nhắn của anh ấy được gõ màu đỏ để nhận dạng):

— 175
PTIBURDUKOV NHẢY SỐ 114
"PEGASUS"
LẦN THỬ ĐẦU TIÊN
SẴN SÀNG BERLAGA số 118

— ×
BERLAGA NHẢY SỐ 118
"HERCULES"
LẦN THỬ ĐẦU TIÊN
SẴN SÀNG
BORISOHLEBSKY số 122

— √

...
GIGIENISHVILI NHẢY
№ 128
"TỪ QUÁ"
LẦN THỨ BA

— ×
NGƯỜI THAM GIA GIGIENISHVILI
№ 128
CUỘC THI KẾT THÚC
