---
id: 1991-11-kiryuhin-iv-vsesoyuznaya-olimpiada-shkolnikov-po-informatike-4805d524
issue: kvant_1991_11
year: 1991
number: "11"
title: Kỳ thi Olympic Tin học toàn đoàn lần thứ IV dành cho học sinh
authors:
  - Кирюхин В. М.
rubric: olimpiady
rubric_sub: Олимпиады
page_first: 67
page_last: 69
page_labels: 65-67
lang: vi
source: kvant_digital
extraction: vision
content_sha256: 8a1713d6ac4f805b631375f236a1d66b4eb08fcbfec7abd8ad789fcd41fd3832
prompt_sha256: draft-1
translated_from: content/ru/1991/11/articles/21_kiryuhin-iv-vsesoyuznaya-olimpiada-shkolnikov-po-informatike-4805d524.md
source_content_sha256: 1223992ce4e1e318122bb34b66214868b239394f98db4630000516eb5106724e
translation_model: draft
translation_run: vi-draft-gaps-2026-11-06
translation_quality: draft
---

⟦folio 65⟧

---
running_head:
folio:
---

IV Tổng cộng
Olympic học sinh
theo thông tin

Ứng viên khoa học kỹ thuật
V. KIRYUKHIN

Theo thông tin, năm nay, chặng cuối cùng của Olympic toàn học dành cho học sinh lần thứ IV diễn ra từ ngày 17 đến 24/4 tại Vishkek, thủ đô của những người lao động tài nguyên ở Kyrgyzstan. Lần này, 87 học sinh từ 11 nhóm nguồn lực, cũng như các thành phố Moscow, St. Petersburg và Vishkek (với tư cách là thành phố đăng cai Thế vận hội) đã tham gia Thế vận hội. Tổng cộng có 16 đội đại diện cho các chuyên gia tài nguyên và các quốc gia khác nhau trong khu vực. Như mọi khi, đội lớn nhất là đội RSFSR - 26 người. Thành phần tối thiểu có thể có (3 người tham gia) được đại diện bởi các đội đến từ Kazakhstan, Kyrgyzstan, Latvia, Moldova và Turkmenistan.

Kyrgyzstan chào đón các vận động viên Olympic bằng vẻ đẹp độc đáo. Tất cả các chàng trai ngay lập tức cảm thấy rằng họ được chào đón những vị khách ở đây. Và thậm chí có lúc mặt trời cũng mỉm cười chào đón, chúc thành công trong cuộc thi khó khăn này.

Buổi khai trương diễn ra trong rạp chiếu phim đầy màu sắc. Ban tổ chức đã làm mọi cách để truyền tải đến khán giả hương vị dân tộc vốn có của tài nguyên và tạo tâm trạng vui vẻ cho toàn bộ thời gian diễn ra Thế vận hội.

Như trước đây, Olympida được thực hiện theo hai loại, cả hai loại đều dựa trên máy tính. Một nửa số người tham gia đã chọn máy tính cá nhân IBM PC và nửa còn lại chọn Yamaha.

Zhior Toàn bộ Olympic được lãnh đạo bởi Viện sĩ Viện Hàn lâm Khoa học Kyrgyzstan, chuyên gia tài nguyên V.P. Zhivoglyadov. Ban giám khảo có quyền biểu quyết bao gồm đại diện của tất cả các công nhân khai thác tài nguyên tham gia, cũng như các thành phố Moscow và St. Petersburg. Gói bài toán dành cho Olympida được chuẩn bị bởi một ủy ban khoa học do Thành viên tương ứng của Viện Hàn lâm Khoa học Liên Xô F. L. Chernousko đứng đầu, và trước mỗi vòng thi, ban giám khảo Olympida đã chọn một gói bài toán từ gói này. Các nhiệm vụ có nhiều cấp độ, cho phép cả những người tham gia rất mạnh và những người ít chuẩn bị hơn có thể chứng tỏ bản thân. Điều đáng chú ý là vấn đề được okskapy đề xuất bài toán - nó yêu cầu các anh chàng không chỉ thể hiện khả năng tạo ra một thuật toán và một chương trình khả thi mà còn phải định dạng vấn đề được đặt ra.

Hãy trình bày điều kiện bài toán.

Nhiệm vụ Itura
(tác giả A. Grudev, F. Chernousko)

Một bộ điều khiển robot được xác định trên mặt phẳng tọa độ, bao gồm hai liên kết được kết nối tuần tự, có độ dài là L1 và L2. Liên kết bản lề thứ nhất được cố định tại gốc tọa độ, bản lề thứ hai được nối với bản lề thứ nhất. Ở cuối liên kết thứ hai cài đặt máy khoan. Robot được điều khiển bằng cách xoay các liên kết ở khớp thứ nhất và khớp thứ hai với vận tốc góc, giá trị tuyệt đối của chúng không vượt quá chiều rộng lần lượt là $\omega$1 và $\omega$2 (pad/c). Liên kết thứ hai có thể xoay tương đối so với liên kết thứ nhất.

Robot được thiết kế để khoan có trách nhiệm. Tọa độ các điểm khoan: (x1; y1), (x2; y2), ..., (xN; yN).

Tại thời điểm ban đầu, liên kết thứ nhất hướng dọc theo dải dương OX và liên kết thứ hai tạo thành một góc A, cách xa trục OX ngược chiều kim đồng hồ. Thời gian thực hiện thao tác khoan có trách nhiệm là cố định và bằng P.

Bạn cần tạo một chương trình:

a) đưa ra chuỗi số điểm khoan bất kỳ và thời gian cần thiết cho việc này;

b) tạo ra một chuỗi các điểm khoan được chỉ định trong thời gian hoạt động ngắn nhất có thể của robot và chính thời gian này;

b) trong một khoảng thời gian nhất định (0, T), chọn số lượng máy khoan chịu trách nhiệm tối đa và xuất ra chuỗi của chúng.

Ứng dụng

1) Tất cả dữ liệu đầu vào là số nguyên.

2) Chương trình phải nhập dữ liệu ban đầu từ file đầu vào (A:ROBOT.DAT) hoặc từ bàn phím theo dạng tuần tự: L1, L2, $\omega$1, $\omega$2, A, T, P, N, x1, y1, ..., xN, yN.

Vòng nhiệm vụ II
(tác giả I. Volkov)

Nhiều từ khác nhau $A=(a1, a2, ..., ak)$, $k \leq 10$ được đưa ra. Trong số các từ có rất nhiều

⟦folio 66⟧

---
running_head:
folio:
---

$A$, một văn bản được mã hóa được biên soạn - một chuỗi các từ được viết không có dấu cách. Các từ là những chuỗi không trống, không nhiều hơn các chữ cái Latinh voscal và có thể xuất hiện trong văn bản với số lần tùy ý. Cần phải giải mã văn bản, tức là chia nó thành các từ thuộc tập hợp $A$. Trong văn bản được giải mã, các từ phải được phân tách bằng dấu cách.

Viết chương trình có:
a) xác định xem đối với một tập hợp $A$ nhất định có văn bản nào có thể được giải mã theo nhiều cách hay không;
b) nếu văn bản đó tồn tại, thì sẽ loại trừ số lượng từ tối thiểu khỏi tập hợp $A$ để bất kỳ văn bản nào có thể được giải mã một cách rõ ràng và in các từ bị loại trừ (nếu tập hợp bị loại trừ đó không phải là từ duy nhất thì sẽ hiển thị tất cả các tùy chọn);
b) đối với văn bản đã nhập, hãy giải mã nó bằng bộ đầu vào ban đầu $A$ và nếu không có cách giải mã duy nhất thì sẽ hiển thị tất cả các tùy chọn.

Trình tự các thao tác vào/ra:
— đầu vào của bộ $A$:
“nhập k”〈К〉
“nhập a1”〈a1〉
“nhập ak”〈ak〉
- đầu ra tin nhắn:
“tồn tại một văn bản có thể giải mã được một cách mơ hồ”
hoặc
“không tồn tại”
- nếu văn bản tồn tại thì thông báo sẽ xuất ra:
“vứt đi”〈danh sách từ〉
— nhập văn bản dài không quá bốn mươi ký tự vào biểu mẫu:
“tekst”〈tekst〉
- đầu ra của kết quả giải mã:
〈tekst〉→〈văn bản được giải mã〉.

Ví dụ
1) $A=(B, C)$ - mọi văn bản đều được giải mã rõ ràng.
2) $A=(B, C, BC)$ - có một văn bản có thể được giải mã theo hai cách:
BBC→B BC
hoặc
BBC→В В С.
Zhorny đã được tối ưu hóa cùng với hoa hồng kiểm tra công việc của người tham gia và xếp hạng từng loại bài toán dựa trên 100 điểm. Khi đánh giá kết quả, tôi tính đến khả năng chính thức hóa nhiệm vụ được đề xuất của học sinh, khả năng thuật toán hóa, tức là phát triển thuật toán tốt nhất và chứng minh độ tin cậy của nó, khả năng lập trình thuật toán kết quả bằng một trong các hệ thống lập trình: BASIC, Turbo-Pascal, Turbo-C. Nhân tiện, hầu hết học sinh đều lập trình bằng Pascal.

Trong số hai bài toán được đề xuất tối ưu hóa, bài toán thuộc loại đầu tiên hóa ra là khó nhất. Với lời giải của cô ấy, điều quan trọng là phải xác định các điểm không thể tiếp cận, cho biết nhu cầu di chuyển robot từ vị trí này sang vị trí khác và cũng chứng minh nhu cầu tìm kiếm toàn diện để có được đáp số chính xác. Ngoài ra, bài toán này còn cung cấp một số phương pháp phỏng đoán thú vị giúp tăng đáng kể hiệu quả của thuật toán trong việc xác định sự kết hợp của dữ liệu đầu vào.

Thật không may, không có sinh viên tối ưu hóa nào có thể giải quyết đầy đủ bài toán này. Kết quả tốt nhất ở đây được thêm bởi A. Guzeev từ Perm (56 điểm), D. Zhukov từ Moscow (56 điểm) và S. Gershtein từ Yekaterinburg (52 điểm). Chỉ 30% học sinh nhận được 20 điểm trở lên cho điều này bài toán - hóa ra, nhiều người tham gia chỉ đơn giản là có kỹ năng toán và vật lý kém, điều này không cho phép họ bắt đầu phát triển thuật toán lời giải bài toán.

Bài toán của loại thứ hai dễ tiếp cận hơn để chính thức hóa và do đó kết quả tốt hơn. Số điểm tối đa - 72 - đã được nhận cho bài toán này bởi A. Sukhanov từ St. Petersburg. D. Uvarov từ Novokuznets và A. Skovortsov từ Yubileiny, vùng Dnepropetrovsk mỗi người nhận được 52 điểm.

Tất nhiên, kết quả tương đối kém mà những người tham gia đạt được với lời giải bài toán tối ưu hóa này có thể được giải thích một phần bởi sự phức tạp của chúng. Tuy nhiên, chúng tôi sẽ không giới hạn bản thân chỉ với lời giải thích này. Thứ nhất, mức độ khó bài toán tương ứng với mức tối ưu hóa quốc tế và có lẽ sẽ sai nếu chúng tôi hạ mức này xuống thấp hơn. Thứ hai, về mặt lý thuyết, nhiều người tham gia đã tìm ra ý tưởng đúng cho lời giải của mỗi bài toán. Không có đủ thời gian để thực hiện. Tất cả điều này cho thấy khả năng trí tuệ của đa số người tham gia là khá cao, nhưng việc thiếu thực hành cần thiết khi làm việc với máy tính cá nhân đã không cho phép họ đưa những ý tưởng hiện có của mình đi đến kết luận hợp lý,

⟦folio 67⟧

---
running_head:
folio:
---

t. đ. có được các chương trình khả thi.
Bất chấp mọi khó khăn, những ngày tháng thành tựu trôi qua nhanh chóng, đã đến lúc tổng kết thành quả. Như mọi khi, có rất nhiều giải thưởng khác nhau dành cho các thí sinh đoạt giải Olympic, ngoài ra, mỗi người tham gia còn nhận được một món quà lưu niệm từ ban tổ chức.
Năm nay, lần đầu tiên, kết quả được tổng hợp riêng ở hai hạng mục: lớp 8-10 và lớp 11. Người có thành tích tốt nhất trên bảng xếp hạng chung tại Olympic này là A. Sukhanov (122 điểm), người đã nhận được huy chương là máy tính cá nhân Corvette. Theo sau anh là A. Guzeev (90 điểm) và D. Uvarov (89 điểm). Giống như các kỳ Olympic trước, học sinh St. Petersburg đã dẫn đầu trong phần thi đồng đội. Thật ngạc nhiên khi trong số giải thưởng còn có các cô gái - A. Pratusevich và A. Kosov-
skaya lần lượt nhận được bằng cấp hai và cấp ba.
Căn cứ kết quả kỳ Olympic vừa qua, ban giám khảo đã đề cử A. Sukhanov và D. Kim vào danh sách thí sinh tham dự Olympic quốc tế năm nay. Để chuẩn bị cho Olympic quốc tế tiếp theo, sẽ được tổ chức vào năm 1992 tại Đức, tất cả học sinh thuộc các lớp chưa tốt nghiệp đã nhận được bằng cấp một và cấp hai đều được đưa vào làm ứng cử viên cho đội tuyển quốc gia Liên Xô. Họ sẽ được mời tham gia trại huấn luyện mùa đông sẽ được tổ chức vào năm tới.
Cuối cùng, tôi muốn cảm ơn ban tổ chức Olympic, những người đã làm mọi cách có thể để tổ chức một cuộc thi phức tạp về mặt kỹ thuật như vậy, đồng thời chúc tất cả những người tham gia thành công hơn nữa trong lĩnh vực khoa học máy tính đầy khó khăn.
