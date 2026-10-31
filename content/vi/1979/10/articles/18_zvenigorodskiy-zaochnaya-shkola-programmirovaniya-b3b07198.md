---
id: 1979-10-zvenigorodskiy-zaochnaya-shkola-programmirovaniya-b3b07198
issue: kvant_1979_10
year: 1979
number: "10"
title: Trường lập trình tương ứng
authors:
  - Звенигородский Г. А.
rubric: raznoe
rubric_sub: Разное
page_first: 56
page_last: 58
page_labels: 54-56
tag: 2IO4
lang: vi
source: kvant_digital
extraction: vision
content_sha256: 8899b3f6821a754b0beeab27c456f4a67f34b6c931ccab2f552e6d5d6dc81fa8
prompt_sha256: draft-1
translated_from: content/ru/1979/10/articles/18_zvenigorodskiy-zaochnaya-shkola-programmirovaniya-b3b07198.md
source_content_sha256: b3d06dba08c6bb2554aca318a161e1fcd2cbf628d2652b17c1435fe3e693b363
translation_model: draft
translation_run: vi-draft-2026-10-31
translation_quality: draft
---

⟦folio 54⟧

Trường lập trình tương ứng

Bài 3: Làm việc với trí nhớ. Tên và ý nghĩa của chúng.

Thủ tục

Khi soạn một chương trình bằng các ngôn ngữ lập trình lớn, bao gồm Robik, sẽ thuận tiện khi tưởng tượng bộ nhớ của máy tính hoặc robot như một tập hợp các khối riêng biệt (Hình 1), trong mỗi khối đó bạn có thể lưu trữ một chương trình riêng biệt (hoặc một phần của nó), một số, một dòng văn bản (hãy nhớ nhiệm vụ 2.4 của bài học trước - «Kvant», 1979, Số 9, trang 57) hoặc bất cứ thứ gì khác. Tên của khối bộ nhớ (để cho ngắn gọn nó được gọi đơn giản là tên; khi mô tả một số ngôn ngữ, các từ khác được dùng với nghĩa tương tự: mã định danh) ​​có thể được mô tả bằng sơ đồ cú pháp sau:

Hãy giải mã sơ đồ này:

Tên bắt đầu bằng một chữ cái, theo sau là một số chữ cái và số ngẫu nhiên theo thứ tự ngẫu nhiên. Tập hợp các giá trị của trường biến Digit được mô tả ở Bài 2; đối với trường Chữ cái, chúng tôi đưa ra định nghĩa bằng lời nói: giá trị của trường này có thể là bất kỳ chữ cái nào trong bảng chữ cái tiếng Nga hoặc tiếng Latinh.

Ví dụ về tên:
A15, CÁ SẤU, TỐC ĐỘ, V, LI, Q06P7, ALPHA

Một vài ví dụ về lỗi thường gặp khi viết tên: 6A12B (không bắt đầu bằng một chữ cái). AB-1 (dấu gạch nối “-” không phải là chữ cái hoặc số).

TÊN KHỐI (đây không phải là một tên mà là hai tên) 'A5' (dấu nháy đơn không phải là một chữ cái).

Ví dụ: nếu số 15 được đặt trong khối bộ nhớ có tên A thì tên A được cho là được gán giá trị 15.

Bạn có thể đọc ý nghĩa của một cái tên bao nhiêu lần tùy thích, nhưng nếu chúng ta gán một ý nghĩa mới cho cái tên này thì cái tên cũ sẽ bị mất vĩnh viễn. Ngôn ngữ Robik có một số mệnh đề cho phép bạn gán ý nghĩa cho tên. Đơn giản nhất trong số này là quy định phân công. Sơ đồ cú pháp cho lệnh này được hiển thị trong bảng của nó ở trang. 56 của tạp chí này. Trong trường biến, "biểu thức" có thể là số, văn bản hoặc tên, như được chỉ định trong cùng một bảng thuộc tính.

Hãy xem xét một số ví dụ về bài tập:
GIÁ TRỊ 5 TÊN CHUYỂN A;

Cơm. 1

⟦folio 55⟧

Gán CHUỖI GIÁ TRỊ
TÊN A;
GIÁ TRỊ 9,81 Gán
TĂNG TỐC ĐƯỢC GỌI;
8 CHỈ ĐỊNH TÊN A5;
BÀI A5;
GIÁ TRỊ CỦA BÀI A5;

Hãy xem tất cả những ví dụ này bao gồm những gì trong sơ đồ!

Ký hiệu viết tắt được sử dụng trong ba ví dụ cuối tiện lợi và gọn gàng hơn ký hiệu đầy đủ, nhưng trước tiên, chúng tôi khuyên bạn nên sử dụng ký hiệu đầy đủ để ghi nhớ ý nghĩa của đơn thuốc.

Nếu giá trị của trường biến “biểu thức” ở phía bên trái của đơn thuốc được gán, tức là ở bên trái của từ ASSIGN, có một số hoặc văn bản, thì chính số này hoặc văn bản này sẽ được gán cho tên; được chỉ ra ở bên phải. Nếu một tên được sử dụng làm biểu thức thì giá trị của tên này sẽ được gán.

Hãy thử theo dõi nội dung của các khối bộ nhớ thay đổi như thế nào khi các hướng dẫn trên được thực hiện tuần tự. Để làm điều này, chúng ta nên vẽ một bảng các giá trị tên. Sau khi thực hiện nhiệm vụ đầu tiên, bảng này sẽ trông như thế này:

| Tên | nghĩa |
| :--- | :--- |
| A | 5 |

Nói cách khác, tên A lúc này có giá trị là 5. Sau lần gán thứ hai, tên A sẽ nhận được giá trị mới. Cái cũ sẽ bị mất đi không thể cứu vãn được. Trong bảng chúng tôi mô tả nó như thế này:

| Tên | nghĩa |
| :--- | :--- |
| A | 'ĐƯỜNG KẺ' |

Sẽ thuận tiện nhất khi chỉ định các bảng như vậy bằng phấn trên bảng đen, xóa các giá trị cũ và nhập giá trị mới. Các biểu thức “xóa khỏi bộ nhớ” và “ghi vào bộ nhớ” truyền tải rõ ràng bản chất của những gì đã xảy ra.

Sau khi hoàn thành ba hướng dẫn sau, bảng sẽ trông như thế này:

| Tên | nghĩa |
| :--- | :--- |
| A | 'ĐƯỜNG KẺ' |
| tăng tốc | 9.81 |
| A5 | 'A' |

Bây giờ chúng ta hãy theo dõi việc thực hiện hướng dẫn cuối cùng:

GIÁ TRỊ CỦA BÀI A5;

Phía bên trái của đơn thuốc có một cái tên, nghĩa là chúng ta cần sử dụng ý nghĩa của nó.

Giá trị này sẽ được đặt tên là A5 cùng với văn bản cũ 'A'. Sau phép gán này, bảng sẽ có dạng sau:

| Tên | nghĩa |
| :--- | :--- |
| A | 'ĐƯỜNG KẺ' |
| tăng tốc | 9.81 |
| A5 | 'A' |

Giá trị của trường “biểu thức” “hoạt động” theo cách tương tự trong lệnh PRINT, sơ đồ cú pháp được đưa ra trong bảng của nó: nếu biểu thức là một tên thì giá trị của tên này sẽ được in. (Hãy nhớ rằng tên, không giống như văn bản, không thể bắt đầu bằng dấu nháy đơn.) Ví dụ: thực hiện lệnh PRINT 5, A, A, A, 'A', '', 'A5', '-', A5, 'ALL', dòng này sẽ xuất hiện trên terminal:

⟦folio 56⟧

5STROKASTROKASTROKAA A5-STROKAVSE

Xin lưu ý rằng văn bản được in không có dấu nháy đơn!
Nhiệm vụ 3.1. Hãy để chúng tôi thấy rằng chúng tôi liên kết máy tính với chương trình:
5 PHẦN A;
'A' Gán cho;
MỘT PHẦN CHO C;
IN 'B =', B, 'C =', C;

Bây giờ là lúc tìm ra cách người ta có thể ghi nhớ một chương trình hoặc một phần của chương trình đó vào bộ nhớ máy tính để không phải gõ lại tất cả các hướng dẫn mỗi lần.

Một chương trình hoặc một phần của chương trình có tên được gọi là thủ tục; Các thủ tục được thiết kế để lưu trữ trong bộ nhớ máy tính.

Để máy tính ghi nhớ chương trình (đặt vào bộ nhớ), bạn cần:
1. Nhập lệnh NHỚ THỦ TỤC và cho biết tên của thủ tục này.
2. Liệt kê tất cả các hướng dẫn có trong quy trình, chỉ ra mỗi hướng dẫn bằng một số sê-ri (số tự nhiên).

3. Loại đơn thuốc KẾT THÚC THỦ TỤC MÔ TẢ.

Sơ đồ cú pháp “Ghi nhớ quy trình” được hiển thị trong bảng riêng của nó (bây giờ hãy bỏ qua phần của sơ đồ này được đánh dấu màu xanh lam).

Ví dụ: chương trình dành cho robot RD-1 được biên soạn trong bài học đầu tiên có thể được ghi nhớ dưới tên CHANGE bằng cách sử dụng chuỗi hướng dẫn sau:

HÃY NHỚ THỦ TỤC THAY ĐỔI;
10 MỞ CỬA SỔ;
20 LÀM ƯỚT GIẢI;
30 XÓA KHỎI BẢNG;
60 NGỒI XUỐNG;
40 ĐÓNG CỬA SỔ;
HOÀN THÀNH MÔ TẢ THỦ TỤC;

Để một thủ tục được lưu trong bộ nhớ bắt đầu thực thi, nó phải được gọi bằng cách sử dụng lệnh CALL PROCEDURE, cấu trúc của thủ tục này được hiển thị trong bảng của nó.

Phân công:
THỂ HIỆN KHÔNG MỤC ĐÍCH Gán CHO TÊN Tên
NHỚ THỦ TỤC Tên thủ tục
tên tham số số tự nhiên quy định
KẾT THÚC MÔ TẢ THỦ TỤC

Gọi thủ tục:
THỦ TỤC GỌI Tên THỂ HIỆN
Sửa chữa thủ tục:
Tên THỦ TỤC ĐÚNG
quy định về số tự nhiên
KẾT THÚC THỂ HIỆN
Dấu ấn:
THỂ HIỆN IN
Tên
