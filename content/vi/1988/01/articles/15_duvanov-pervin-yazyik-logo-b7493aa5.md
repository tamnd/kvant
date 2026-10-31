---
id: 1988-1-duvanov-pervin-yazyik-logo-b7493aa5
issue: kvant_1988_1
year: 1988
number: "1"
title: Biểu tượng ngôn ngữ
authors:
  - Дуванов А. А.
  - Первин Ю. А.
rubric: raznoe
rubric_sub: Разное
page_first: 53
page_last: 56
page_labels: 51-54
tag: XSHH
lang: vi
source: kvant_digital
extraction: vision
content_sha256: 0fed0095ea6b0c916e1597da8e156773ceda4de699f3a9a917706b55dfef2dd9
prompt_sha256: draft-1
translated_from: content/ru/1988/01/articles/15_duvanov-pervin-yazyik-logo-b7493aa5.md
source_content_sha256: c623e1e50e0f76c39d585841df4e930b941160e53b7358fcff55fb0f955d7efe
translation_model: draft
translation_run: vi-draft-2026-10-31
translation_quality: draft
---

⟦folio 51⟧

Biểu tượng ngôn ngữ
A. A. DUVANOV, Y. A. PERVIN

Bài học 4:
Cấu trúc dữ liệu trong Logo

Ngôn ngữ thuật toán và logo
Những độc giả nghiên cứu thông tin ở trường có thể so sánh ngôn ngữ thuật toán được mô tả trong sách giáo khoa và ngôn ngữ họ biết từ Logo «Kvant». Có thể dễ dàng nhận thấy sự tương đồng của cả hai ngôn ngữ ở công cụ đồ họa, lệnh điều kiện và lệnh gán. Mối quan hệ giữa các chu kỳ trong Logo và ngôn ngữ thuật toán phức tạp hơn. Có thể dễ dàng chuyển từ vòng lặp FOR trong ngôn ngữ thuật toán sang vòng lặp REPEAT. Do đó, bạn có thể tính thể tích của một “kim tự tháp” được tạo thành từ nhiều bánh xe bằng vòng lặp FOR:

V:=0
ĐỐI VỚI R OT 10 ĐẾN 50 BƯỚC 10
NC
V:=V+3.14*R**2*H
CC

Điều này được lập trình trong Logo như thế này:
LÀM” V 0
LẶP LẠI 5
[DO” V CỘNG NHÂN NHÂN R R H 3,14 V]

Nhưng chu trình BYE, tồn tại trong ngôn ngữ thuật toán, không có sự tương tự trực tiếp trong Logo. Trong vòng lặp như vậy, điều kiện luôn được viết sau từ WHILE. Điều kiện này là chìa khóa mở lối vào phần thân vòng lặp: nếu điều kiện đúng thì các lệnh vòng lặp sẽ được thực thi và điều kiện sẽ được kiểm tra lại; nếu điều kiện bị vi phạm, máy sẽ tiến hành thực hiện lệnh theo chu trình. Sách giáo khoa về khoa học máy tính cung cấp thuật toán tính GCD bằng vòng lặp WHILE. Để thực hiện các hành động trong Logo được lặp lại không phải với số lần cố định mà tùy thuộc vào

⟦folio 52⟧

một số điều kiện (bao gồm một biến), bạn cần sử dụng tài nguyên. Sử dụng sự hỗ trợ này để hoàn thành nhiệm vụ tiếp theo của bạn.

Bài toán 1. Viết vào Logo một hàm tính gcd của hai số.

Điểm giống nhau chính giữa ngôn ngữ thuật toán và Logo là khả năng soạn thảo các mô tả về một hành động phức tạp từ những mô tả đơn giản hơn. Những mô tả như vậy trong Logo được gọi là *thủ tục* và trong ngôn ngữ thuật toán - thuật toán phụ trợ. Các khái niệm về *chức năng* trong các ngôn ngữ phổ biến cũng gần giống nhau.

Tuy nhiên, điều quan trọng là vẫn khác biệt. Một điểm khác biệt đó là cách trả về giá trị hàm cho chương trình gọi. Trong Logo, hãy sử dụng lệnh *RETURN α* để thực hiện việc này. Nó kết thúc việc thực thi hàm và trả về giá trị của biểu thức α cho chương trình. Không có trình quay lui đặc biệt nào trong ngôn ngữ thuật toán. Hàm thoát sau khi lệnh cuối cùng được thực thi. Kết quả là nó trả về giá trị của một biến đặc biệt VALUE, có cùng kiểu với kiểu hàm.

Hầu hết các ngôn ngữ lập trình đều có khả năng biểu diễn và xử lý các giá trị bằng chữ, như chúng được gọi trong ngôn ngữ thuật toán. Trong Logo có một tên đơn giản cho kiểu thực thi này - “word”. Một từ là một chuỗi có thứ tự hữu hạn các ký tự không phải khoảng trắng. Từ trong chương trình được thể hiện dưới dạng thói quen, không được tính vào số ký tự từ. Từ này có thể trống - không có một ký tự nào trong một từ như vậy, ký hiệu của nó là một dấu ngoặc kép, theo sau là dấu cách (trong ngôn ngữ thuật toán, một biến theo nghĩa đen hóa ra là một cặp dấu ngoặc kép). Ví dụ về từ Logo: “NADIA - có 4 chữ cái trong một từ, “U - một ký hiệu riêng biệt được coi là một từ bao gồm một ký hiệu này; "1918-1988 - từ có 9 ký tự.

Những từ ban đầu được sử dụng để thể hiện tên biến. Với lệnh *MAKE "CAGE 1* biến *CELL* nhận giá trị 1. Lệnh *MAKE "CAGE" "ELEPHANT* tạo ra giá trị của biến *CAGE* của từ *ELEPHANT*. Trong ngôn ngữ thuật toán, lệnh cuối cùng sẽ có dạng: *CAGE:="ELEPHANT"*

Những từ khác nhau như vậy!

Hãy tưởng tượng cuộc trò chuyện giữa hai cậu bé. Seryozha nói:

- *ABBA* là tên tôi đặt cho những chú chó của mình.

Anton nói: “Đó là một cái tên buồn cười, nhưng bạn đánh vần nó như thế nào?”

- “ABBA” như thế này: đầu tiên là “A”, sau đó là “B”, một “B” khác và cuối cùng lại là “A”.

- Cô ấy có biết tên mình không? – Anton muốn biết.

Seryozha vui vẻ thể hiện khả năng của chú chó của mình:

- Tất nhiên rồi! *ABBA*! Cô ấy đây rồi!

Ba lần trong cuộc trò chuyện này, từ *ABBA* được sử dụng và mỗi lần với một vai trò khác nhau. *ABBA* là tên của một con chó; "ABBA" là một từ là một chuỗi các chữ cái theo thứ tự chuỗi; *ABBA*! - đây là hiệu lệnh con chó lập tức trở về nhà. Trong ngôn ngữ nói, cách sử dụng từ khác nhau có thể được đánh dấu bằng ngữ điệu. Nếu một cuộc trò chuyện như vậy cần được ghi lại, thì để phân biệt các vai trò khác nhau của từ, sẽ cần có một ký hiệu đặc biệt - dấu chấm câu.

Trong Logo, mọi thứ hoàn toàn giống nhau. Để xác định nghĩa của các từ ví dụ được sử dụng trong chương trình, cũng có các quy tắc cú pháp:

⟦folio 53⟧

- một dấu kép được đặt trước tên của một đại lượng để biểu thị giá trị của đại lượng này tại thời điểm hiện tại; so: MARK là giá trị của biến MARK;

- dấu ngoặc kép được đặt trước một từ là một chuỗi ký tự; theo vị trí của từ đó trong lệnh (theo ngữ cảnh), ý nghĩa của từ được chỉ định sẽ được đánh giá; Vì vậy, trong lệnh gán MAKE "CELL" các từ ở vị trí cuối cùng - "EPLEPHANT có dấu ngoặc kép ở đầu - là chữ 常数ta, và các từ ở vị trí trước - "CELL - là tên của biến CELL; so sánh lệnh MAKE "CAGE:ELEPHANT", trong đó biến CAGE nhận giá trị mà biến có tên ELEPHANT có;

— các lệnh gọi thủ tục và hàm (cũng như các lệnh và thao tác) không được đặt trước dấu ngoặc kép hoặc dấu ngoặc kép; ký hiệu CAGE : ELEPHANT có nghĩa là gọi thủ tục CAGE với tham số ELEPHANT.

Hãy bắt đầu xử lý danh sách

Các lập trình viên thường sử dụng thuật ngữ "dữ liệu". Thuật ngữ này có thể được coi là đồng nghĩa với khái niệm “thông tin”. Thông tin được xử lý bằng máy có thể được tổ chức theo nhiều cách khác nhau. Đây là các ký tự đơn hoặc tập hợp hữu hạn được sắp xếp của chúng - các từ hoặc một nhóm từ được sắp xếp - một danh sách hoặc một số cách phức tạp hơn khác để kết hợp các ký tự, từ và danh sách. Thông tin được tổ chức theo cách này hay cách khác được gọi là cấu trúc dữ liệu.

Trong ngôn ngữ thuật toán, mỗi cấu trúc dữ liệu phải được đặt một tên đặc biệt - một loại giá trị - nat, thing, lit, v.v. Không có mô tả về các loại trong Logo, nhưng mỗi cấu trúc của ngôn ngữ thuật toán đều có những cấu trúc tương tự riêng trong Logo. Để biểu thị một bảng và các cấu trúc dữ liệu phức tạp hơn, Logo sử dụng danh sách, danh sách này mở rộng khái niệm về giá trị dạng bảng trong ngôn ngữ thuật toán.

Danh sách xử lý yêu cầu các thao tác hoàn toàn khác so với tính toán tranh luận. Giả sử bạn cần điền vào bộ nhớ máy tính thông tin về học sinh của lớp - danh sách thông tin của từng học sinh. Để làm việc với cấu trúc như vậy, sẽ rất hữu ích khi có các thao tác cho phép bạn thêm, xóa, tìm và thay đổi các thành phần danh sách.

Lựa chọn phần tử đầu tiên của cấu trúc - FIRST α (hoặc PRV α). Đối số của thao tác này là các từ hoặc một danh sách, kết quả là phần tử đầu tiên (cấu trúc. Ví dụ:

PRV "LOGO = "L,
PRV [ngôn ngữ LẬP TRÌNH LOGO]=
= "LOGO

Cấu trúc không có phần tử đầu tiên - NGOẠI TRỪ α ĐẦU TIÊN (hoặc KPRV α). Đối số của thao tác này là các từ hoặc một danh sách, kết quả là phần tử cuối cùng (cấu trúc. Ví dụ:

KPRV "LOGO ="OGO
KPRV [ngôn ngữ LẬP TRÌNH LOGO] =
[Ngôn ngữ lập trình]

Phần tử (cấu trúc) cuối cùng là LAST α (hoặc PSL α). Đối số của thao tác này là các từ hoặc một danh sách, kết quả là phần tử cuối cùng (cấu trúc. Ví dụ:

PSL "LOGO ="OGO
PSL [ngôn ngữ LẬP TRÌNH LOGO] =
[Ngôn ngữ lập trình]

Cấu trúc không có phần tử cuối cùng - NGOẠI TRỪ α CUỐI CÙNG (hoặc KSSL α). Đối số của thao tác là các từ hoặc một danh sách, kết quả là một cấu trúc không có phần tử cuối cùng. Ví dụ,

CPSL "LOGO = "ĐĂNG NHẬP
KPSL [ngôn ngữ LẬP TRÌNH LOGO] =
[Ngôn ngữ LẬP TRÌNH LOGO]

Bao gồm một phần tử ở đầu (cấu trúc - INITIAL αβ (hoặc INTO αβ). Đối số đầu tiên - chúng tôi bao gồm phần tử, đối số thứ hai - chúng tôi thay đổi (cấu trúc. Ví dụ:

BAN ĐẦU "L" "OGO = "LOGO
TOP "LOGO [NGÔN NGỮ LẬP TRÌNH] =
[Ngôn ngữ LẬP TRÌNH LOGO]

Bao gồm một phần tử ở cuối (cấu trúc - TẠI THE END αβ (hoặc ВКОН αβ). Đối số đầu tiên là bao gồm

⟦folio 54⟧

phần tử, thứ hai là một cấu trúc có thể thay đổi. Ví dụ,

VKON "O" LOG = "LOGO
VKON "LẬP TRÌNH [Ngôn ngữ LOGO] = [Ngôn ngữ LẬP TRÌNH LOGO]

Xác định chiều dài của một cấu trúc là LENGTH α. Đối số của thao tác này là một từ hoặc một danh sách; kết quả là số phần tử trong cấu trúc. Ví dụ,

CHIỀU DÀI "LOGO" = 4
CHIỀU DÀI [NGÔN NGỮ LẬP TRÌNH LOGO] = 3
CHIỀU DÀI [[BÚT 3] [SÁCH 2] [BÚT 5]] = 3

Để phân tích cấu trúc dữ liệu trong Logo, ngoài những cấu trúc đã nhập trước đó, các loại điều kiện cấu trúc sau đây được sử dụng:

Con số? TỪ? DANH SÁCH? TRỐNG?

Những điều kiện này kiểm tra xem cấu trúc là số, từ, danh sách hay trống.

Vì vậy, dữ liệu về học sinh lớp được lưu trữ dưới dạng danh sách:

LỚP=
[[IVANOV PETYA POLEVAYA 35 17]
[DANILOV SASHA PUSHKINA 58 2]
...]

Bạn cần lập danh sách tên của tất cả học sinh trong lớp. Chúng ta sẽ lấy “hồ sơ” của Ivanov từ danh sách LỚP bằng thao tác PRV :CLASS:

[IVANOV PETYA TRƯỞNG TRƯỞNG 35 17]

Từ danh sách này, chúng ta lại cần phần tử đầu tiên:

PRV PRV :LỚP = "IVANOV"

Chúng tôi sẽ thu thập họ trong danh sách FAM:

KIẾM "FAM VKON PRV PRV :CLASS :FAM

(1)

Lệnh (1) xóa danh sách FAM theo một phần tử. Từ IVANOV được thêm vào cuối. Còn Petrov thì sao? Rất đơn giản: bạn cần rút gọn danh sách LỚP:

KIẾM "LỚP KPRV: LỚP

(2)

và thực hiện lại lệnh (1). Tiếp theo là gì? Mọi thứ được lặp lại: lệnh (1) được theo sau bởi lệnh (2), v.v., cho đến khi hết toàn bộ danh sách LỚP. Đây là mô tả của chức năng được yêu cầu trông như thế nào:

ĐÂY LÀ HỌ:LỚP:FAM
ĐỘ DÀI LẶP LẠI: LỚP
[Làm "FAM VKON PRV PRV
:LỚP :FAM
KIẾM "LỚP KPRV: LỚP
]
TRỞ LẠI :FAM
KẾT THÚC

Sau khi biên soạn một mô tả như vậy, chúng tôi có được danh sách họ mong muốn bằng lệnh:

XUẤT HỌ TÊN: LỚP []

(3)

Hàm được xây dựng không phải là hàm duy nhất giải được bài toán đã cho. Chúng tôi có thể cung cấp một phiên bản đệ quy của nó:

ĐÂY LÀ HỌ:LỚP:FAM
NẾU TRỐNG? :CLASS [TRẢ LẠI :FAM]
KIẾM "FAM VKON PRV PRV :CLASS :FAM
TRẢ LẠI HỌ KPRV :CLASS :FAM
KẾT THÚC

Đây là lệnh:

NẾU TRỐNG? :CLASS [TRẢ LẠI :FAM ]
đảm bảo rằng quá trình đệ quy kết thúc khi danh sách LỚP đã hết. Đội:

LÀM NÓ. "FAM VKON PRV PRV :LỚP :FAM

thêm một tên khác vào danh sách FAM. Đội:

TRẢ LẠI HỌ KPRV :CLASS :FAM

thực hiện lệnh gọi đệ quy đến hàm LAST NAME với danh sách LỚP rút gọn.

Nhiệm vụ 2 và 3. Viết hai phiên bản của hàm ADDRESS (đệ quy và có lệnh lặp), dựa trên họ sẽ cung cấp giá trị là địa chỉ của học sinh. Ví dụ: kết quả của đầu ra ĐỊA CHỈ: LỚP "IVANOV" phải là danh sách [POLEVAYA 35 17] và kết quả của đầu ra ĐỊA CHỈ: LỚP "DANILOV" phải là danh sách [PUSHKINA 58 2].

Hàm này sẽ cung cấp khả năng gọi thông báo [NO SUCH STUDENT] trong trường hợp họ sai.

Bài 4. Viết hàm tính số từ trong một danh sách. Rõ ràng là hàm LENGTH tiêu chuẩn không phải lúc nào cũng tương đương chính xác. Ví dụ: số phần tử trong danh sách [[VASYA PETYA] KOLYA] là hai, trong khi số lượng từ là ba.

Chú ý! Đọc thêm về quy trình vận hành của 3ShP trên trang. 47.
