---
id: 1981-1-konkurs-rabot-po-programmirovaniyu-b5312a6f
issue: kvant_1981_1
year: 1981
number: "1"
title: Cuộc thi lập trình
rubric: raznoe
rubric_sub: Разное
page_first: 54
page_last: 57
page_labels: 52, 54, 55
tag: EKTO
lang: vi
source: kvant_digital
extraction: vision
content_sha256: 41d8256257596884ccd44cde06987888656db1aa824fc98570aea44ceab30fc2
prompt_sha256: draft-1
translated_from: content/ru/1981/01/articles/17_konkurs-rabot-po-programmirovaniyu-b5312a6f.md
source_content_sha256: 2fca978e8f104bdfb0d5b3c689fa870e04a3c3996553cf5654267a8bb663c89a
translation_model: draft
translation_run: vi-draft-2026-10-31
translation_quality: draft
---

⟦folio 52⟧

ăn số học, bài toán. Việc coi một chiếc máy như một máy đo số học siêu mạnh là một quan niệm sai lầm phổ biến của nhiều người mới bắt đầu với Fortran hoặc BASIC. Máy tính là một công cụ phổ biến để xử lý tất cả các loại thông tin tượng trưng - đồ họa, văn bản, điều khiển. Và chỉ trong các ứng dụng một phần (không phải đồ sộ nhất) của máy tính, chúng mới thực sự tham gia vào việc tính toán các biểu thức số học. Người đọc thường xuyên và chú ý «Kvant», rõ ràng, đã nhận thấy ý tưởng này nghe có vẻ thực tế như thế nào trên các trang của phần “Nghệ thuật lập trình”.

Cuộc thi lập trình

Trung tâm Máy tính của Chi nhánh Siberia của Viện Hàn lâm Khoa học Liên Xô và các biên tập viên của tạp chí «Kvant» công bố một cuộc thi về các tác phẩm lập trình.

Việc tham gia cuộc thi có thể bao gồm các trường tương ứng của chương trình, trường trung học và trường dạy nghề. Mỗi tác phẩm phải có

1) thông tin ngắn gọn về các tác giả (họ, tên, họ viết tắt, địa chỉ nhà đầy đủ, trường, lớp, thời gian và địa điểm tôi học lập trình);
2) mô tả công việc (tuyên bố bài toán, giải thích phương pháp của nó lời giải, nhận xét về chương trình, kết quả thu được);
3) chương trình văn bản và tính toán máy (nếu có tính toán).

Bài dự thi phải được gửi chậm nhất là ngày 15 tháng 4 đến địa chỉ: 630090, Novosibirsk, 90, prosp. Khoa học 6, Trung tâm Máy tính SB Viện Hàn lâm Khoa học Liên Xô, Khoa Tin học, Cuộc thi-81.

Những người chiến thắng cuộc thi sẽ nhận được lời mời tham gia Trường học lập trình viên trẻ mùa hè VI. Đánh giá về các tác phẩm thú vị nhất sẽ được công bố trên tạp chí của chúng tôi.

Mười bài toán để áp dụng tùy ý

(Để bắt đầu, xem trang 37)

Bài toán 10. Hình 10 là đồ thị vận tốc v của một điểm chuyển động thẳng. Thu được đồ thị này, hãy xác định thời điểm t khi gia tốc a của điểm này bằng 3 m/s2.

Gợi ý. Vẽ tiếp tuyến của đồ thị vận tốc với góc

tìm hệ số bằng 3. Tìm hoành độ của các điểm tiếp tuyến.

Hình 10.

⟦folio 54⟧

Bảng cho mỗi hành tinh hiển thị tên, bán kính (tính bằng km), khoảng cách đến Mặt trời (tính bằng ml. km), số lượng vệ tinh, cũng như thành phần của khí quyển, được chỉ định bằng cách sử dụng một bộ - danh sách tên các loại khí. Tất cả thông tin này tạo thành bối cảnh của đối tượng tương ứng - một phần tử của bộ HỆ THỐNG MẶT TRỜI.

Nếu bây giờ GAZ được coi là một dấu hiệu trong thành phần của khí quyển và tổng số các phần tử còn lại trong bộ dữ liệu của các hành tinh được coi là bối cảnh, thì trong các ký hiệu này, thật dễ dàng để lập trình bài toán 7 (a, d) Lập trình Olympic («Kvant», 1980, Số 3): từ tập hợp các hành tinh của Hệ Mặt trời, hãy chọn những hành tinh có bầu khí quyển chứa carbon dioxide:
<**> —> RES;
cho CÁC HÀNH TINH từ HỆ THỐNG MẶT TRỜI ::
NẾU'CARBON DIOXIDE'
TỪ HÀNH TINH[5] ĐẾN TỪ HÀNH TINH[5]
ĐẾN RES+HÀNH TINH—> RES
TẤT CẢ;
TẤT CẢ;

Chương trình bắt đầu bằng cách gửi một tập trống tới REZ; ở REZ một tập hợp các kết quả dần dần được hình thành. Lưu ý rằng khi giải bài toán này, chúng ta sẽ không cần truy cập vào các phần tử riêng lẻ của tập hợp. Không có thứ tự liệt kê các phần tử trong tập hợp (1).

Trong chương trình này, nhiều kết quả được lưu trữ trong bộ nhớ của máy tính. Nếu bạn muốn in kết quả, bạn có thể sử dụng toán tử in định dạng, sơ đồ cú pháp của nó trông như sau:

Ở đây, biểu thức-1 là biểu thức có giá trị (số hoặc văn bản) sẽ được in và giá trị của biểu thức-2 là số ký tự được in.

Như vậy, việc in bảng các hành tinh được thực hiện theo một chu trình:
CHO X TỪ RES::
IN (X[1]:12,X[2]:6,
X[3]:3,X[4]:2,X[5]:50)
TẤT CẢ;

(giải thích cách chọn số ký tự cần in ở đây). Điều đáng nói là một dòng chứa 128 ký tự, nhiều hơn mức đúng đối với các thiết bị in máy tính hiện đại.

Chỉ cần nói thêm rằng bảng in phải luôn có tiêu đề. Nhưng việc in tiêu đề không khó: theo quy luật, tiêu đề chỉ có một dòng.

Nhiệm vụ 12.1. Mô tả nhóm học sinh trong lớp của bạn, gợi ý rằng mỗi học sinh đều biết thông tin: họ, giới tính, năm sinh, huy hiệu GTO bắt đầu. Viết chương trình in

a) tập hợp tất cả nữ sinh trong lớp;
b) tập hợp tất cả các ký hiệu của lớp GTO.

Nhưng nếu bạn cần tìm tất cả những cô gái đã đạt tiêu chuẩn để nhận huy hiệu GTO thì sao? Một điều lời giải ngay lập tức thu hút sự chú ý của bạn: viết hai quy trình, một trong số đó, dựa trên tập hợp học sinh trong lớp, tạo và để lại trong bộ nhớ tập GIRL, và quy trình thứ hai (đã được viết ở lời giải bài toán 12.1) chọn một biểu tượng từ tập hợp này. (Tuy nhiên, thứ tự hoạt động của hai quy trình như vậy có thể đảo ngược: đầu tiên, huy hiệu được chọn và sau đó các cô gái được chọn trong số đó.)

Nhiều ngôn ngữ lập trình (bao gồm cả Rapier) cung cấp khả năng đạt được chỉ trong một lần “vượt qua”. Những khả năng này được cung cấp bởi cái gọi là điều kiện phức tạp. Điều kiện phức tạp là tập hợp một số điều kiện (quen thuộc với người đọc «Kvant», ví dụ: từ câu lệnh điều kiện hoặc toán tử vòng lặp Rapier), được kết nối bằng các phép toán logic và (phép nhân logic) hoặc (phép cộng logic) và NOT (phủ định). Việc kết hợp các điều kiện đơn giản thành một điều kiện phức tạp không được thực hiện một cách tùy tiện mà theo những quy tắc nhất định có thể được chỉ định bằng sơ đồ.

⟦folio 55⟧

Tất nhiên, trong sơ đồ cú pháp này, một điều kiện có thể được thay thế bằng một điều kiện phức tạp.

Người đọc «Kvant» có thể đã từng gặp các toán tử logic AND, OR, NOT. Các toán tử AND và OR được áp dụng cho hai toán hạng và phép toán NOT được áp dụng cho một toán hạng. Giá trị của toán hạng và kết quả của cả ba phép tính là hai giá trị khác nhau: đúng và sai, hoặc “+” và “—”, hoặc (đặc biệt thuận tiện cho việc biểu diễn trong máy) 0 và 1. Đối với các phép toán AND, OR và NOT, có một biểu diễn dạng bảng đơn giản (tên A và B chỉ ra các điều kiện của toán hạng).

AIB AIB

Các phép toán AND, OR, NOT có thể được áp dụng cho các điều kiện (cũng có thể lấy các giá trị đúng và sai). Như vậy, (X>2) AND (X<5) có nghĩa là X rơi vào khoảng số 2;5[, và điều kiện NOT(GIRL OR (NOT ICON AND BOY)) chọn tập hợp tất cả các bé trai “thể thao”. Điều kiện phức tạp tương tự có thể được diễn đạt đơn giản hơn - BOY và BADGE. Bạn có thể đọc về cách biến đổi các điều kiện phức tạp trong cuốn sách của Yu. A. Shikhanovich “Nhập môn Toán học Hiện đại” (M. “Nauka”, 1965).

Nhiệm vụ 12.2. Sử dụng các điều kiện phức tạp, xây dựng quy trình để chọn từ một bộ LỚP tất cả các nam sinh năm 1965 đạt tiêu chuẩn cấp huy hiệu GTO. In bảng kết quả một cách hài lòng.

Các bộ phim khiêu dâm do cxx được coi là (SOLAR_SYSTEM, CLASS,...) được dùng làm biểu diễn máy của các bảng hai chiều: một thay đổi - các hàng là các bộ dữ liệu (hành tinh, sinh viên, ...) và thay đổi thứ hai - các cột là các phần tử hình thành các bộ dữ liệu (bán kính của các hành tinh, giới tính của học sinh, ...). Bây giờ sẽ không khó để làm quen với các bảng ba chiều. Trong cuộc sống hàng ngày, một bảng ba chiều chẳng hạn là một cuốn sách, trên mỗi trang có một bảng hai chiều “rõ ràng”, kích thước yêu cầu của bảng đó là số trang. Do đó, các bảng Bradis, được mọi học sinh biết đến, cũng có thể được mô tả dưới dạng một tập hợp các bộ dữ liệu bao gồm một giá trị số (ngữ cảnh) và ba đặc điểm tương ứng với nó - TRANG, HÀNG, CỘT.

Tìm giá trị ở cột thứ ba và hàng thứ năm ở trang thứ hai trong bảng đó để xác định ngữ cảnh có đặc điểm thỏa mãn điều kiện phức tạp (TRANG-2) AND (ROW-5) AND (COLUMN-3).

Nhiệm vụ 12.3. Tạp chí tháng Giêng của lớp gồm 8 trang, mỗi trang một trang cho mỗi môn - tiếng Nga, văn, toán, vật lý, hóa học, địa lý, ngoại ngữ, thể dục. Trang nhật ký bao gồm các dòng, trên mỗi dòng có ghi tên học sinh và có khoảng trống cho 18 bài đánh giá - một bài cho mỗi ngày. Hãy mô tả nhật ký lớp học của bạn trong tháng 1 và tạo một chương trình in bảng gồm những học sinh đạt điểm xuất sắc ở ít nhất một môn học vào ngày 28 tháng 1.

Và cuối cùng là những câu hỏi cuối cùng:

Nhiệm vụ 12.4. Mô tả một tình huống trong thực tế hàng ngày trong đó việc biểu diễn thông tin trong bảng bốn chiều có thể hữu ích. Làm thế nào để bạn gán một bảng như vậy cho một máy? Làm thế nào để tìm một phần tử trong bảng như vậy?

Yu. Pervin, N. Yunerman
