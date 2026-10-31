---
id: 1977-8-zadachi-nashih-chitateley-c5038fa1
issue: kvant_1977_8
year: 1977
number: "8"
title: Bài toán độc giả của chúng tôi
rubric: smes
page_first: 58
page_last: 58
page_labels: "56"
tag: 8KYT
lang: vi
source: kvant_digital
extraction: vision
content_sha256: 2792412d4e2b8912baeab55ffca6bb983f202c06c80fabaa6116d4ffbb474b34
prompt_sha256: draft-1
translated_from: content/ru/1977/08/articles/14_zadachi-nashih-chitateley-c5038fa1.md
source_content_sha256: 15a1bd5fbed3f0870c824450f7f17c7b008cfd1aac376c990fec8d46f747982b
translation_model: draft
translation_run: vi-draft-2026-10-31
translation_quality: draft
---

⟦folio 56⟧

gốc cây. Câu hỏi về mã nào sẽ nhận được trong trường hợp này có liên quan đến các bài toán lý thuyết số.

Mã và số liệu thống kê
Chúng tôi đã xem xét nhiều loại mật mã khác nhau liên quan đến các phép tính số học trên các số chữ cái. Tất cả các mật mã này đều có một nhược điểm đáng kể - mỗi chữ cái biến thành cùng một ký tự, bất kể chữ cái này xuất hiện ở đâu trong chữ cái. Để giải mã các mã như vậy, có thể sử dụng các phương pháp thống kê toán học. Mỗi chữ cái trong bảng chữ cái tiếng Nga và ký tự khoảng trắng tương ứng với một tần suất nhất định mà chúng (trung bình) xuất hiện trong các văn bản dài:

| "không gian" | 0,175 | R | 0,040 | TÔI | 0,018 | X | 0,009 |
| :--- | :--- | :--- | :--- | :--- | :--- | :--- | :--- |
| VỀ | 0,090 | TRONG | 0,038 |Y | 0,016 |VÀ | 0,007 |
| CÔ ẤY | 0,072 | L | 0,035 |Z | 0,016 |Yu | 0,006 |
| MỘT | 0,062 | ĐẾN | 0,028 |b,b0,014 |Sh | 0,006 |
| VÀ | 0,062 | M | 0,026 |B | 0,014 |C | 0,004 |
| T | 0,053 | D | 0,025 |G | 0,013 |SCH | 0,003 |
| N | 0,053 | P | 0,023 |H | 0,012 |E | 0,003 |
| VỚI | 0,045 | bạn | 0,021 |Y | 0,010 |F | 0,002 |

Do đó, bạn có thể lấy thông điệp đang được giải mã, đếm tần suất xuất hiện cho mỗi dấu hiệu và trên cơ sở đó đánh giá ý nghĩa của dấu hiệu này. Ví dụ, dấu hiệu xuất hiện thường xuyên nhất có nhiều khả năng trở thành
trắng Chà, nếu không phải là khoảng trắng thì có lẽ là “O” (chữ này đứng ở vị trí thứ hai). Bạn cũng có thể nghiên cứu sự kết hợp của các ký tự lân cận - hầu hết toàn bộ hàng có chữ cái nguyên âm đều có một phụ âm. Hơn nữa, trong một văn bản ngắn, bạn có thể dễ dàng tách các dấu hiệu phụ âm khỏi các dấu hiệu nguyên âm. Những thông báo như vậy giúp việc giải mã dễ dàng hơn chỉ bằng cách thay thế các chữ cái bằng dấu hiệu.

Mật mã dựa trên việc sắp xếp lại các chữ cái trong tin nhắn theo quy tắc này hay quy tắc khác cũng tương đối dễ giải.

Để mã được “theo sách”, số mã có nghĩa là số dòng và chữ trên một trang cụ thể của một cuốn sách nhất định và số trang có thể thay đổi tùy theo ngày tin nhắn được viết. Trong trường hợp này, nếu không biết cuốn sách nào là cơ sở cho việc mã hóa thì rất khó tiết lộ bí mật của mật mã.

Ngày nay, máy tính điện tử được sử dụng để soạn thảo và giải mã. Trong Chiến tranh thế giới thứ hai, khi chưa có máy tính, các máy mã hóa cơ học được sử dụng để mã hóa và giải mã. Nhà toán học và logic học xuất sắc người Anh Alan Thjoring, một trong những người tạo ra cái gọi là lý thuyết thuật toán, đã đóng một vai trò lớn hơn trong việc làm sáng tỏ mật mã mà các nhà mật mã phát xít sử dụng sau đó.

Bài tập
độc giả của chúng tôi

1. Hàm $f$ được xác định và liên tục trên toàn bộ trục số. Người ta biết về chức năng này rằng nếu $x_2 - x_1$ là số phân vùng thì $f(x_2) - f(x_1)$ là số phân vùng. Chứng minh rằng $f(x) = kx + b$ và $k$ chia hết.

2. Có bốn số tự nhiên có tổng bằng tích của chúng không?

S. Sefibekov (làng Kashkent, Dag ASSR)

3. Các đường chéo được vẽ trong một khối lập phương (bên trong khối lập phương và trên tất cả các mặt). Có bao nhiêu cách chọn một cặp đoạn thẳng vuông góc với nhau trong số 16 đoạn thẳng?

B. Fedomov (Petrozavodsk)
