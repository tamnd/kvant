---
id: 1987-3-krutogin-mk-problemyi-obscheniya-52eab07e
issue: kvant_1987_3
year: 1987
number: "3"
title: 'MK: vấn đề giao tiếp'
authors:
  - Крутогин Д. Г.
rubric: raznoe
page_first: 16
page_last: 19
page_labels: 14-17
tag: AXO4
lang: vi
source: kvant_digital
extraction: vision
content_sha256: fa7bbf84e87ff4682f7e9a3f0cd472f93d4ea5ebcdb3f23094083e47f8e5c5d4
prompt_sha256: draft-1
translated_from: content/ru/1987/03/articles/04_krutogin-mk-problemyi-obscheniya-52eab07e.md
source_content_sha256: 69fd699b2f3559cfe0f1c2143ff15d2bcc02ee6b7728aebcd687802829e54c2c
translation_model: draft
translation_run: vi-draft-2026-10-31
translation_quality: draft
---

⟦folio 14⟧

MK:
VẤN ĐỀ GIAO TIẾP
(Hành trình qua máy vi tính)

Ứng viên Khoa học Kỹ thuật D. G. KRUTOGIN

Trong số trước, chúng tôi đã đưa MK đi dạo quanh thành phố, xem xét toàn cảnh thành phố và giới thiệu cư dân của thành phố, tạm trú và lâu dài. Bây giờ là lúc nhìn vào quy hoạch thành phố để đánh giá cao cấu trúc của nó. Trong sơ đồ (hình 1), bạn có thể thấy năm quận lớn được kết nối với nhau. Chúng ta sẽ đi qua chúng theo thứ tự sau: vùng thiết bị đầu vào (IDU) và thiết bị đầu ra (UD), vùng bộ nhớ truy cập ngẫu nhiên (RAM), thiết bị lưu trữ chỉ đọc

⟦folio 15⟧

(ROM) và cuối cùng là khu vực bộ vi xử lý (MP). Tấm thị thực trong ảnh là một tinh thể máy vi tính thật, được phóng đại gấp 10 lần. Đây là cách nó trông độc lập cho đến khi quá trình sản xuất mạch và đặt nó vào hộp hoàn tất. Việc chỉ ra ranh giới của các vùng không phải là điều dễ dàng, đặc biệt vì không gian trống trên chip gần như vô hình. Vì vậy, sẽ thuận tiện hơn cho chúng ta khi di chuyển theo kế hoạch. Và bây giờ chúng ta hãy đi...

Khu vực trạm tridiati

Trong kế hoạch (hình 1) của visa có trung tâm tiếp nhận khách du lịch, hoặc hệ thống thiết bị đầu vào (IDS) (nhắc lại rằng khách du lịch ở MK là những từ máy được ghép thành các chương trình - đoàn). Các phái đoàn từ các quốc gia khác nhau đến đây, trong khu vực UVV, sử dụng nhiều phương tiện giao thông khác nhau. Ví dụ: từ bàn phím hiển thị, từ đầu ghi băng bộ nhớ ngoài (VRAM) *), từ màn hình hiển thị hoặc từ cảm biến bên ngoài. Do đó, khu vực trên không là tập hợp của một số trạm hoặc cảng **).

No UVV không chỉ là một nhà ga mà còn là một văn phòng du lịch mẫu mực của thành phố chúng ta, cũng như hải quan, cắt bỏ những từ, cụm từ hoặc lệnh trong chương trình không chính xác hoặc không được chấp nhận. Các thiết bị đầu vào được đón tiếp các đoàn du lịch, kiểm tra giấy tờ nhập cảnh và cung cấp cho họ người phiên dịch và người đi cùng (địa chỉ). Cuối cùng, các thiết bị tương tự cũng giám sát khách du lịch trong thành phố trong thời gian họ lưu trú.

Vì vậy: bài toán đầu vào đầu tiên, ngay cả trước khi phân tích và dịch thuật, là dỡ bỏ phương tiện vận chuyển đã vận chuyển các chương trình đến thành phố, tức là dòng đầu vào thông tin. Để thực hiện việc này, bạn cần ghi lại các tín hiệu nhận được (hiện tại chỉ ghi âm mà không xử lý) bằng ngôn ngữ mà chúng được gửi. Ban đầu, các cổng đầu vào thực hiện việc ghi các từ của chương trình nguồn. Trên thực tế, chúng là những khối RAM nhỏ dài một từ máy, tức là các thanh ghi. Mỗi thanh ghi được trang bị một khối các phần tử logic *) - một bộ đệm, đảm bảo kết nối một thanh ghi trống với các dòng thông tin bên ngoài và một thanh ghi đã đầy với bộ vi xử lý. Bộ vi xử lý thăm dò định kỳ các cổng đầu vào và tải lại các từ chứa trong đó vào RAM, sau đó các cổng sẵn sàng ghi một từ mới.

Ai là người chỉ huy cuộc diễu hành?

Cần lưu ý rằng UVV tham gia tích cực vào tất cả các hoạt động này, nhưng nhân vật chính là bộ vi xử lý. Dưới sự điều khiển của chương trình đầu vào (được lưu trữ

*) Thiết bị của nhà đăng ký đã được xem xét trong phần PEVT ở «Kvant» số 4 cho năm 1986; thiết kế các phần tử logic - trong «Kvant» số 2 năm 1986.

**) Ở đây từ “port” không chỉ là hình ảnh văn học mà còn là một thuật ngữ kỹ thuật. Đây là tên được đặt cho bộ phận của vi mạch trong vùng UVV hoặc UVV cung cấp cho MK của nó các thiết bị bên ngoài.

⟦folio 16⟧

ở ROM) anh hợp tác với UVV, tiếp đón các đoàn khách du lịch.

Nói chung, chúng ta hãy lưu ý rằng khi xem xét hoạt động của máy tính, việc phân biệt giữa phần cứng (ví dụ: cổng thực, đầu ra đầu vào, ô nhớ, v.v.) và phần mềm luôn hữu ích, tức là những hành động được thực hiện bởi các phần tử riêng lẻ của vi điều khiển, được hỗ trợ bởi một số chương trình nhất định điều khiển máy ở các giai đoạn hoạt động khác nhau.

Bot trước mặt bạn là một chiếc máy tính đã tắt. Bây giờ bạn nhấn nút "Bật"... sao? Máy phải thực hiện những hành động gì để chuẩn bị vận hành, chuẩn bị cho đầu vào của chương trình người dùng? Ai kiểm soát nó cho đến khi bạn vào chương trình của mình? Đáp số: chương trình ROM độc quyền có tên là "màn hình". Nó được ưu tiên ngay sau khi máy “đánh thức”. MP được hồi sinh nhưng chưa được nạp đạn dường như đang gửi câu hỏi đến mọi đầu: "Phải làm gì? Phải làm gì?" Và chương trình giám sát là chương trình đầu tiên phản hồi: “chuẩn bị đầu vào, xóa RAM, gọi chương trình đầu vào, chỉ định cổng nào đang mở (từ cổng nào) đầu vào sẽ theo sau…” Sau đó, trình soạn thảo sẽ từ bỏ lệnh của chương trình đầu vào và sau khi đầu vào hoàn tất, màn hình sẽ ra lệnh cho MP bắt đầu sử dụng các chương trình của người dùng. Bot đây là một chương trình quan trọng - montor! Và ngoài màn hình, MK còn có thêm một số chương trình tiện ích.

Chúng ta lại nói những ngôn ngữ khác nhau

bài toán tiếp theo được thực hiện trên đầu vào là dịch văn bản chương trình người dùng sang ngôn ngữ máy. Bot ở đây chúng ta quay lại cuộc trò chuyện về người dịch. Các dịch giả sống ngay trong thành phố, trong khu vực PZU. Đây là những chương trình tiện ích đặc biệt được gọi là dịch giả (để dịch). Có nhiều dịch giả khác nhau: một người giống phiên dịch đồng thời hơn, những người khác giống dịch giả văn học hơn.

Bộ đồng bộ hóa (hoặc trình biên dịch-thông dịch) dịch một lệnh tiếp theo và gửi nó ở dạng không được trình bày để thực thi. Văn bản đã dịch không được lưu trữ trong bộ nhớ của trình thông dịch đồng thời, vì vậy khi làm việc lại từ cùng một chương trình và cùng một lệnh, trình biên dịch-thông dịch lại thực hiện công việc tương tự. Nhưng đôi khi anh ấy đột nhiên từ chối dịch; điều này có nghĩa là chương trình nguồn chứa biểu thức không chính xác. Trình thông dịch không thể dịch lỗi; nó không có trong “từ điển” của nó. Sau đó, một thông báo lỗi được gửi đến các thiết bị đầu ra (OUD), thậm chí về bản chất của lỗi.

Các dịch giả văn học (hoặc người biên dịch-biên dịch) làm việc đáng tin cậy hơn. Ra lệnh bằng lệnh, họ viết lại chương trình gốc sang ngôn ngữ của máy vi tính và chiếm nó trong RAM của nó. Khi kết thúc công việc này, bản tương tự hoàn chỉnh của chương trình gốc sẽ được lưu trữ trong RAM, nhưng bằng ngôn ngữ máy. Sau khi hoàn thành công việc, trình dịch chương trình này đã sẵn sàng để sử dụng, bao gồm cả việc lặp lại nhiều lần.

Dịch giả nào cần thiết hơn và tốt hơn? Cả hai đều cần thiết. Đối với công nghệ có máy móc, làm việc ở chế độ đối thoại sẽ thuận tiện hơn khi có thông dịch viên; nó cho phép bạn chỉnh sửa và thay đổi bất kỳ lệnh nào ở bất kỳ đâu trong chương trình. Đối với MK, trình thông dịch thuận tiện hơn vì nó cần ít RAM hơn (để ghi) và bộ nhớ vĩnh viễn (để lưu trữ “từ điển”). Đối với các phép tính dài và lặp đi lặp lại trên một chương trình lớn và phức tạp, trình biên dịch sẽ thuận tiện hơn vì nó hoạt động nhanh hơn nhiều.

Không có kiểm tra và không có lỗi

bài toán tiếp theo của khu vực tiếp nhận là chương trình tái định cư. Với mục đích này, một bộ khách sạn có tên RAM được sử dụng - điền vào hoạt động của thiết bị. Chúng tôi sẽ đề cập đến vấn đề này sau, nhưng bây giờ chúng tôi lưu ý rằng các từ lệnh và từ toán hạng cần được phân bổ trong các thẻ khác nhau của vùng RAM. Như đã đề cập trước đó, từ “quan điểm” của máy, chúng không thể phân biệt được và nếu chúng bị nhầm lẫn trong quá trình thực hiện chương trình thì việc sử dụng chương trình sẽ bị gián đoạn. Để có thể dễ dàng tìm thấy lệnh hoặc toán hạng vào đúng thời điểm, hãy đặt đầu vào cung cấp tất cả các từ được giải quyết bằng địa chỉ và địa chỉ

⟦folio 17⟧

bạn cần phải ghi nhớ nó, ghi nó vào một loại sổ “địa chỉ”. Sau đó, máy không còn hoạt động với các từ như vậy nữa mà với các địa chỉ. Ví dụ: gửi nội dung của ô số 95 của RAM tới MP (ví dụ: chúng tôi đã phân bổ các ô có số từ 000 đến 199 cho các lệnh). Một ví dụ khác: so sánh nội dung của ô số 286 với số 0 và nhập số lớn hơn vào ô số 286.

Và cuối cùng, các văn phòng du lịch nơi tiếp nhận điều phối thứ tự lưu trú của du khách trong thành phố và đặt các dịch vụ phù hợp. Đồng ý rằng để tính hai phương trình ngắn được viết bằng năm ký tự, ví dụ:

$$c = a + b, \\
c = tg a^b$$

- công việc chuẩn bị hoàn toàn khác sẽ được yêu cầu. Ở quy mô cuộc sống thành thị, bài toán đầu tiên đơn giản như mua một tờ báo, thứ hai giống như tổ chức một lễ hội múa dân gian. Ở đây bạn cần tìm các chương trình (ở đâu? trong ROM) để tính các hàm lũy thừa, sau đó là các tiếp tuyến của một đối số tùy ý. Nhưng nếu du khách muốn tham dự lễ hội thì phải tổ chức, đây là điều kiện làm việc của thành phố chúng tôi - một trung tâm du lịch.

Các thiết bị đầu ra, nằm trong sơ đồ bên cạnh các thiết bị đầu vào, thực hiện nhiều chức năng phức tạp, nhưng tất nhiên là theo thứ tự ngược lại. Họ chuyển đổi các từ máy - kết quả tính toán - thành dạng thân thiện với người tiêu dùng (dưới dạng bảng, đồ thị, văn bản, cảnh báo âm thanh hoặc thậm chí cả lời nói) và cung cấp tín hiệu điều khiển cho thiết bị đầu ra thích hợp: màn hình, thiết bị in, máy tạo âm thanh mô phỏng giọng nói.

Hơn nữa, thiết bị đầu ra là một chỉ báo kỹ thuật số gồm bảy bộ đơn giản (hình 2), sau đó để điều khiển nó ở đầu ra của MK phải có một mạch logic chứa khoảng một trăm bóng bán dẫn. Và trên màn hình của một máy tính đơn giản thường có ít nhất 5-8 chỉ báo như vậy, và thậm chí trên đồng hồ điện tử cũng có ít nhất bốn chỉ báo.

Vì vậy, chúng tôi đã làm quen với nhiệm vụ của hai quận của thành phố MK, nhưng trên đường đi
