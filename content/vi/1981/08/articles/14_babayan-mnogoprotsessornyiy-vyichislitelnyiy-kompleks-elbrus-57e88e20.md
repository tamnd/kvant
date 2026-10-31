---
id: 1981-8-babayan-mnogoprotsessornyiy-vyichislitelnyiy-kompleks-elbrus-57e88e20
issue: kvant_1981_8
year: 1981
number: "8"
title: Tổ hợp điện toán đa bộ xử lý "Elbrus"
authors:
  - Бабаян Б. А.
rubric: raznoe
rubric_sub: Разное
page_first: 56
page_last: 59
page_labels: 54, 55, 57
tag: YFZ2
lang: vi
source: kvant_digital
extraction: vision
content_sha256: e23ba2e200c94c604c0f25a109da3eaa20aa48ec74733c4fae86de7bcb7f6580
prompt_sha256: draft-1
translated_from: content/ru/1981/08/articles/14_babayan-mnogoprotsessornyiy-vyichislitelnyiy-kompleks-elbrus-57e88e20.md
source_content_sha256: 43ee56a673f88818e339fea86e53a0a2c662a4bd0a4d2ee544150efa029ba8b1
translation_model: draft
translation_run: vi-draft-2026-10-31
translation_quality: draft
---

⟦folio 54⟧

Nghệ thuật lập trình

B. Babayan

Tổ hợp điện toán đa bộ xử lý "Elbrus"

Bài viết này nói về máy tính mới của Liên Xô. Giống như bất kỳ máy tính nào, nó có bộ xử lý («Kvant», 1980, số 5) và bộ nhớ («Kvant», 1980, số 4). Hay đúng hơn, thậm chí là một thiết bị lưu trữ toàn màu đen: hoạt động rất nhanh, nhưng dung lượng bộ nhớ tương đối nhỏ, nằm trong chính bộ xử lý; bộ nhớ chính; “bộ nhớ ngoài” chậm. Thông tin từ bộ nhớ ngoài đi vào bộ nhớ chính bằng các quy trình vào/ra đặc biệt.

Hệ thống mô-đun

Vì vậy bây giờ tất cả các thiết bị đều là máy tính. Sự khác biệt giữa Elbrus là nó được chia thành các bộ phận (thiết bị) được kết nối với nhau tương đối lỏng lẻo, được gọi là mô-đun. Ví dụ về các mô hình: bộ xử lý, bộ nhớ chính, thiết bị đầu vào/đầu ra, v.v. Các mô hình này được đặc trưng bởi một số lượng nhỏ các kết nối bên ngoài và khả năng thay thế lẫn nhau tốt. Theo quy định, các mô-đun được kết nối với nhau theo nguyên tắc “mỗi mô-đun với nhau”, nghĩa là mỗi mẫu bộ xử lý được kết nối với từng mẫu bộ nhớ chính, v.v.

Một tổ chức như vậy có nhiều lợi thế. Thứ nhất, nó sử dụng một số mô hình quay đơn khác nhau, bạn có thể có được các máy tính khác nhau với hiệu suất khác nhau; tăng số lượng mo-

⟦folio 55⟧

thổi, bạn có thể tăng dần sức mạnh của máy. Thứ hai, nếu bất kỳ mẫu xe nào trong xe bị hỏng, điều này sẽ chỉ dẫn đến tốc độ của xe bị giảm tạm thời vì các mẫu xe khác vẫn tiếp tục hoạt động. Thứ ba, bằng cách tập hợp nhiều mô hình tương tự vào một hệ thống, chúng ta có thể có được một chiếc máy tính toán nhanh hơn đáng kể so với trường hợp thông thường.

Do đó, hệ thống Elbrus có thành phần rất thay đổi. Nếu không thực hiện các biện pháp phòng ngừa thích hợp, các chương trình sẽ phải được viết lại mỗi khi trạng thái thay đổi. Ví dụ, đây có thể là trường hợp nếu chương trình chứa địa chỉ của ô nhớ từ một mô hình đã bị hỏng. Để ngăn điều này xảy ra, ở Elbrus, ngoài việc triển khai bộ nhớ thông thường, còn có bộ nhớ ảo hoặc toán học. Đây không còn là một thiết bị có thể thực hiện được nằm ở một vị trí nhất định trên máy mà là một khái niệm hấp dẫn bao gồm một tập hợp các số chỉ địa chỉ của “các ô toán học” (đối với Elbrus, đây là các số từ 0 đến $2^{33} \approx 4 \cdot 10^9$). Chính những địa chỉ này được sử dụng khi chương trình chạy và việc dịch chúng sang địa chỉ của các ô thực được thực hiện tự động bằng cách sử dụng các bảng đặc biệt. Do đó, nếu thành phần của máy thay đổi thì bề mặt của các bảng này sẽ thay đổi, nhưng các chương trình vẫn không thay đổi.

Dung lượng bộ nhớ ảo lớn hơn đáng kể so với dung lượng RAM trong máy thực. Các bảng ban đầu được chuyển để lưu trữ thông tin hiện không cần thiết vào bộ nhớ ngoài, ghi chú thực tế này vào các bảng.

Để thuận tiện cho chương trình

Một "Elbrus" màu đen thậm chí còn quan trọng hơn là sự chú ý của nó đến các vấn đề lập trình. Các nhà phát triển đã cố gắng làm cho chiếc máy này trở nên thuận tiện cho chương trình. Và những vấn đề trong lĩnh vực lập trình hiện nay rất nghiêm trọng. Vào cuối những năm 60, họ thậm chí còn bắt đầu nói về cuộc khủng hoảng lập trình.

Thực tế là trong hơn 30 năm tồn tại của công nghệ máy tính, các phương pháp sản xuất máy tính đã tiến bộ theo thời gian, nhưng việc sản xuất một chương trình (lập trình) vẫn chủ yếu là lao động thủ công. Có rất nhiều chương trình cần được phát triển đến nỗi có vẻ như không còn xa nữa khi hầu hết mọi người có học thức đều sẽ lập trình. Ngoài ra, có nhiều thuật toán hữu ích có thể được thực thi bởi các máy tính hiện đại, nhưng đơn giản là không thể lập trình được do kích thước lớn và độ phức tạp của các chương trình tương ứng.

Một trong những phương pháp nổi tiếng hỗ trợ lập trình được gọi là ngôn ngữ cấp cao (Algol, Pascal, Rapier, v.v.). Ngôn ngữ cấp cao về cơ bản là các máy trừu tượng do các lập trình viên hình thành và triển khai trên các máy thực bằng chương trình. Các chương trình đặc biệt được gọi là trình dịch sẽ dịch các chương trình từ ngôn ngữ cấp cao sang ngôn ngữ máy.

Trong Elbrus, rất nhiều điều đã được thực hiện để giúp dịch các chương trình từ các ngôn ngữ cấp cao trở nên dễ dàng và nhanh chóng, đồng thời giúp các chương trình hoạt động nhanh chóng và chiếm ít dung lượng bộ nhớ. Ví dụ, đây là hệ thống lệnh không có địa chỉ, được mô tả trong bài viết “Máy ba địa chỉ, một địa chỉ và ... không có địa chỉ” («Kvant», 1981, Số 4).

Teri

Điều rất quan trọng, từ quan điểm của chương trình, là phải chú ý đến các vấn đề lập trình. Các nhà phát triển đã cố gắng làm cho chiếc máy này trở nên thuận tiện cho chương trình. Và các vấn đề trong lĩnh vực lập trình vẫn đang tiếp diễn, bất chấp những phát triển gần đây trong lĩnh vực lập trình.

⟦folio 57⟧

Bảo vệ bộ nhớ Elbrus dựa trên việc sử dụng thẻ.

Thông tin địa chỉ chứa mô tả về các vùng bộ nhớ cụ thể cần thiết cho một bài toán nhất định và được trang bị cho các chuyên gia, được gọi là `deckrintopom`.

Nếu bài toán chỉ có bộ giải mã mô tả các khu vực riêng của nó, thì trong lời giải, bài toán này không thể được thêm vào các khu vực khác, tức là vi phạm biện pháp bảo vệ. Trong Elbrus, bảo mật không chỉ được thực hiện giữa các nhiệm vụ mà còn giữa các phần riêng lẻ của cùng một bài toán. Những phần như vậy được gọi là `процедурами`.

Sẽ rất thuận tiện khi gỡ lỗi các quy trình độc lập với nhau và sau đó kết hợp chúng thành một chương trình lớn. Phương pháp lập trình này, được Elbrus hỗ trợ về phần cứng, ban đầu nhờ các quy trình được tạo sẵn trong máy, thường được gọi là `modульным`. Nó cũng làm cho việc lập trình trở nên rất dễ dàng.

Trên Elbrus, tất cả các chương trình chỉ được viết bằng ngôn ngữ cấp cao, bao gồm cả các hệ thống chương trình phức tạp nhất, chẳng hạn như hệ điều hành và phương tiện truyền tải. Trước đây, các chương trình này thường được viết bằng ngôn ngữ máy thực tế.

Vẫn nhanh

Sự thuận tiện trong lập trình là khía cạnh quan trọng nhất của hệ thống Elbrus,

*) Về tốc độ, Elbrus-2 mười bộ xử lý vượt quá một trong những máy nội địa hiện đại mạnh mẽ nhất BESM-6 khoảng 100 lần.
