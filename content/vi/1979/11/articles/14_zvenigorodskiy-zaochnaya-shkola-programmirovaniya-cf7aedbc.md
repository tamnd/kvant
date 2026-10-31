---
id: 1979-11-zvenigorodskiy-zaochnaya-shkola-programmirovaniya-cf7aedbc
issue: kvant_1979_11
year: 1979
number: "11"
title: Trường lập trình tương ứng
authors:
  - Звенигородский Г. А.
rubric: raznoe
rubric_sub: Разное
page_first: 46
page_last: 49
page_labels: 44-47
tag: FSNL
lang: vi
source: kvant_digital
extraction: vision
content_sha256: fbb99875a6b4f661ac996ab89d783a5ac1f8dc420061b1365b943981ea446bd3
prompt_sha256: draft-1
translated_from: content/ru/1979/11/articles/14_zvenigorodskiy-zaochnaya-shkola-programmirovaniya-cf7aedbc.md
source_content_sha256: 5ee79857822cdc7596987408e2c7018d8ef08d996f7c0043390d52399e4ef030
translation_model: draft
translation_run: vi-draft-2026-10-31
translation_quality: draft
---

⟦folio 44⟧

Trường lập trình tương ứng

Bài 4: Các quy tắc nghệ thuật của ngôn ngữ Robik.
Quy định có điều kiện và theo chu kỳ.
Thủ tục có tham số

Trong ngôn ngữ Robik, bạn có thể thực hiện các phép tính số học trên các con số. Với mục đích này, các từ quy định THÊM và TRỪ được dự định, sơ đồ cú pháp của chúng được đưa ra trong bảng riêng của chúng (tr. 47). Ý nghĩa của những tiền kinh thánh này quá rõ ràng nên chúng tôi sẽ không mô tả chi tiết công việc của chúng mà chỉ giới hạn trong một ví dụ nhỏ: CỘNG 5 VÀO 10 VÀ Gán A; TRỪ 3 TỪ A VÀ GIAO CHO B; THÊM A VỚI B VÀ Gán cho B;
IN 'A-', A, 'B-', B;
Chương trình này sẽ in dòng sau:

$$A = 15B = 27$$

Nhiều người có thể ngạc nhiên vì sự vắng mặt của các phép tính nhân và chia trong các quy tắc giữa của ngôn ngữ. Vấn đề là Robik là một ngôn ngữ học tập và việc tạo ra các thủ tục nhân và chia các số là một bài tập học tập tuyệt vời.

Nhiệm vụ 4.1. Mô tả các thủ tục làm tăng giá trị và phân chia các quy tắc trung bình của ngôn ngữ. Và nhiều khi chúng ta gán cùng một tên cho kết quả.

Một trong những mệnh lệnh quan trọng nhất trong bất kỳ ngôn ngữ lập trình nào là mệnh lệnh có điều kiện, cấu trúc của nó được mô tả trong bảng riêng của nó.

Gặp phải phần mô tả trước có điều kiện trong văn bản của chương trình, trước hết máy tính sẽ kiểm tra các điều kiện:

nó hoặc là sai. Nếu điều kiện đúng thì chỉ có dòng lệnh sau từ TO mới được sử dụng. Nếu điều kiện sai thì chỉ có mệnh đề xuất hiện sau từ ELSE mới được sử dụng (nếu từ này không có trong mệnh đề, thì nếu điều kiện sai, mệnh đề có điều kiện sẽ bị bỏ qua trong trường hợp này).

Ví dụ: nếu giá trị của tên A và B là một số số thì hãy viết trước NẾU A LỚN HƠN B ĐỂ IN A ELSE IN B; sẽ in số lớn hơn trong số này (nếu các số bằng nhau thì số thứ hai sẽ được in, nếu không thì trùng với số thứ nhất).

Nhiệm vụ về một robot bò

Robot RO-1 phải kiểm tra độ bền của các mối nối trên tuyến đường sắt mới. Khi phát hiện khớp nối bị lỗi, robot phải báo cáo việc này cho người điều khiển trực tại trạm. RO-1 phải thực hiện toàn bộ ngôn ngữ quy định của Robik. Ngoài ra, SPR của nó bao gồm quy định sau:

$$\text{ПРОЕХАТЬ} \quad \text{натуральное число}$$

và danh sách các điều kiện có thể chấp nhận được bổ sung thêm hai điều kiện:

$$\text{СТЫК НЕИСПРАВЕН} \quad \text{К}$$

$$\text{ВПЕРЕДИ ТУПИК} \quad \text{К}$$

Khoảng cách giữa các khớp là 24 mét. Nhánh kết thúc trong ngõ cụt. Trước khi bắt đầu công việc, robot sẽ lắp đặt tại khớp đầu tiên của nhánh đang được kiểm tra. Hãy tạo một chương trình.

Giải pháp.

HÃY NHỚ QUY TRÌNH KIỂM TRA;
10 NẾU KHỚP LỖI KHAI THÁC IN 'PHÁT HIỆN KHỚP LỖI';
20 ĐI 24 M;
30 KIỂM TRA THỦ TỤC CUỘC GỌI;
HOÀN THÀNH MÔ TẢ THỦ TỤC;
KIỂM TRA THỦ TỤC CUỘC GỌI;

Hãy xem cách chạy chương trình này. Chúng ta sẽ giả định rằng mối nối thứ nhất và thứ hai hoạt động tốt, còn mối nối thứ ba có vấn đề. Khi

⟦folio 45⟧

Chúng ta sẽ gọi thủ tục CHECK lần đầu tiên, robot sẽ bắt đầu thực thi toán tử số 10. Đây là toán tử có điều kiện nên PO-1 trước tiên sẽ kiểm tra các điều kiện:

KHỚP LỖI LỖI

Như chúng ta đã thỏa thuận, mối nối đầu tiên còn tốt nên điều kiện này là sai và không cần phải lật lại mọi thứ. Đối với ngã ba thứ hai, có thể sử dụng được, mọi thứ sẽ được lặp lại chính xác, nhưng ở ngã ba thứ ba, điều kiện trong câu lệnh thứ mười trở thành đúng và dòng chữ xuất hiện trên màn hình của thiết bị đầu cuối được lắp đặt tại nhà ga:

KHUYẾN CÁO LỖI ĐƯỢC PHÁT HIỆN

Sau đó, robot sẽ lại đi đến người điều khiển thứ 20, di chuyển thêm 24 mét nữa và bắt đầu lại từ đầu. Mọi người đều ổn. Tuy nhiên, vẫn còn một câu hỏi chưa rõ ràng: robot sẽ lặp lại quy trình này trong bao lâu? Đánh giá theo chương trình - ad infinitum. Tất nhiên, trên thực tế, nhánh cây sẽ kết thúc ở đâu đó và robot sẽ đi vào ngõ cụt. Nhưng đây là tình huống khẩn cấp. Chúng ta hãy cố gắng ngăn chặn điều đó: đối với điều này, điều rất quan trọng là các câu lệnh 20 và 30 chỉ được thực thi trong trường hợp không có bế tắc phía trước. Ví dụ: nếu phát hiện bế tắc, bạn có thể in thông báo sau cho người điều hành nhiệm vụ:

ĐƯỜNG DÂY ĐÃ KIỂM TRA. RO-1 HOÀN THIỆN CÔNG VIỆC

Nào, hãy thử viết một chương trình như thế này:

NHỚ KIỂM TRA;
10 NẾU KHỚP LỖI LỖI IN ' KHUYẾN CÁO LỖI ĐƯỢC PHÁT HIỆN';
20 NẾU CÓ KẾT THÚC Ở PHÍA TRƯỚC THÌ IN 'DÒNG'

ĐÃ KIỂM TRA. RO-1 HOÀN THÀNH. NẾU KHÔNG THÌ...
DỪNG LẠI!! Chính xác thì ELSE là gì?

Rốt cuộc, nếu phía trước không có ngõ cụt, chúng ta cần thực hiện hai câu lệnh cùng một lúc: lái xe 24 mét và gọi thủ tục KIỂM TRA, và xét theo sơ đồ, sau các từ TO và OTHERWISE chỉ có thể có một câu.

Tuy nhiên, có một giải pháp: chúng ta sẽ mô tả một thủ tục mới bao gồm hai toán tử này và sau từ ELSE, chúng ta sẽ chỉ đơn giản đặt nó vào lệnh gọi của thủ tục này:

HÃY NHỚ ĐƯỜNG SẮT;
10 CUỘN 24 M;
20: KIỂM TRA;
HOÀN THÀNH;
NHỚ KIỂM TRA;
10 NẾU KHỚP LỖI LỖI IN ' KHUYẾN CÁO LỖI ĐƯỢC PHÁT HIỆN';
20 NẾU CÓ KHÓA CHẾT PHÍA TRƯỚC ĐỂ IN 'DÒNG ĐƯỢC KIỂM TRA. RO-1 HOÀN THÀNH. KHÁC: ĐƯỜNG SẮT;
HOÀN THÀNH;
:BÀI KIỂM TRA;

Hãy làm phức tạp nhiệm vụ: giả sử robot phải in số lượng khớp bị lỗi mỗi lần. Ví dụ: kiểm tra xem chương trình này có phù hợp với việc này không:

GIÁ TRỊ 1 TÊN CHỈ ĐỊNH H;
HÃY NHỚ ĐƯỜNG SẮT;
10 CUỘN 24 M;
20 BỔ SUNG 1 VỚI N VÀ Gán TÊN CHO N;
30: KIỂM TRA;
HOÀN THÀNH;
NHỚ KIỂM TRA;
10 NẾU KHỚP LỖI THÌ IN 'SỐ KHỚP',H, 'BỊ LỖI'.
20 NẾU CÓ KHÓA CHẾT PHÍA TRƯỚC ĐỂ IN 'DÒNG ĐƯỢC KIỂM TRA. RO-1 HOÀN THÀNH. KHÁC: ĐƯỜNG SẮT;
HOÀN THÀNH;
:BÀI KIỂM TRA;

Nhiệm vụ 4.2. Robot PO-1 cũng phải kiểm tra xã hội

⟦folio 46⟧

Tất cả các khớp đều nằm trên một nhánh mới. Sau khi phát hiện khớp bị lỗi, robot phải cho biết số lượng và khoảng cách đến khớp đó (tính bằng mét). Sau khi hoàn thành việc kiểm tra, bạn cần đặt khớp khi nhân hai số tự nhiên theo dạng sau:

NHỚ TÀI KHOẢN;
10 THÊM 1 VÀO MF VÀ Gán cho MF;
20 THÊM A VỚI PR VÀ Gán PR;
30 NẾU ĐẾM BẰNG THÌ IN PR: ĐẾM ELSE;
HOÀN THÀNH;
NHỚ NHÂN;
10 0 CHỈ ĐỊNH MF;
20 0 CHỈ PR;
30 NẾU ĐẾM BẰNG SAU ĐÓ IN Ngược lại: COUNT;
HOÀN THÀNH;

Quy trình này nhân giá trị của tên A và B và in sản phẩm. Kiểm tra điều này với các ví dụ cụ thể.

Chúng tôi đã gặp nhiều chương trình trong đó cần phải lặp lại việc thực hiện một hoặc nhiều hướng dẫn nhiều lần. Điều này không phải ngẫu nhiên: chính những hành động lặp đi lặp lại như vậy nên nên giao phó cho automata, do đó, trong số bài toán được giải quyết trên máy tính, sự lặp lại xảy ra rất thường xuyên.

Cho đến cxx, chúng tôi đã tổ chức các hành động lặp lại bằng cách sử dụng các điều kiện của toán tử và lệnh gọi thủ tục: một thủ tục lặp lại được gọi chính nó cho đến khi so sánh thành công. Tuy nhiên, trong Robik và hầu hết các ngôn ngữ khác có một hướng dẫn đặc biệt để tổ chức lặp lại - hướng dẫn Tuần hoàn (xem sơ đồ tương ứng - trang 47).

Cách thức hoạt động của cấu trúc này là mệnh đề sau từ REPEAT sẽ được sử dụng đi sử dụng lại miễn là điều kiện vẫn đúng. Nói cách khác, máy hoạt động với đơn thuốc này như sau: đầu tiên, như trong điều kiện của đơn thuốc, nó được kiểm tra thành công. Nếu sai thì lệnh sẽ không được thực thi.

Nếu điều kiện đúng thì lệnh theo sau từ REPEAT sẽ được thực thi, sau đó nó được kiểm tra lại thành công. Nếu nó vẫn đúng thì đơn thuốc lại được thực hiện - và cứ như vậy cho đến khi điều kiện được cô đọng lại. Nếu và khi nó không sai (và đây là trường hợp nếu chương trình được viết không chính xác), thì máy sẽ thực hiện đi thực hiện lại các hướng dẫn cho đến khi nó tắt hoặc gặp sự cố - một tình huống khó chịu gọi là vòng lặp sẽ phát sinh. Chúng ta sẽ gặp các ví dụ trong các bài học sau.

Bằng cách sử dụng toán tử tuần hoàn, phép thử nhân có thể được viết tinh tế hơn một chút:

NHỚ TÀI KHOẢN;
10 THÊM 1 VÀO MF VÀ Gán cho MF;
20 THÊM A VỚI PR VÀ Gán PR;
HOÀN THÀNH;
NHỚ NHÂN;
10 CHỈ MF;
20 CHUYỂN PR;
30 ĐẾN KHI ĐẾM LẶP LẠI ÍT HƠN :COUNT;
40 IN IN:
HOÀN THÀNH;

Tuy nhiên, quy trình này cũng có nhược điểm đáng kể: nó chỉ ghi đè giá trị của tên A và B. Để ghi đè giá trị của tên khác hoặc chỉ hai số, chúng phải được thêm vào tên A và B.

Điều này là không đủ nếu bạn sử dụng cơ chế tham số. Tham số là các tên được liệt kê trong ngoặc đơn sau tên thủ tục trong chỉ thị NHỚ (xem sơ đồ Ghi nhớ Thủ tục ở #10, trang 57). Ý nghĩa của những tên này được liệt kê trong cùng dấu ngoặc khi chọn quy trình. Ví dụ, nếu mô tả

⟦folio 47⟧

Phép cộng:
THÊM biểu thức C
VÀ Gán tên;
ĐẾN

Phép trừ:
biểu thức TRỪ biểu thức TỪ biểu thức
VÀ Gán tên;
ĐẾN

Ưu đãi có điều kiện:
Điều kiện IF TO mệnh đề vô điều kiện
KHÁC câu K

Ưu đãi theo chu kỳ:
Điều kiện BYE LẶP LẠI câu K

Tình trạng:
NHIỀU HƠN BÌNH ĐẲNG KHÔNG BẰNG

Những lời ăn xin THỎ bắt đầu như thế này:
NHỚ THỎ (A, B, C);
thì khi gọi thủ tục này chúng ta có thể viết:

GỌI THỎ PROSTER
(10, 'ĐUÔI', NOM);

Trong trường hợp này, tên A sẽ có giá trị 10, tên B sẽ có giá trị 'TAIL' và tên C sẽ có cùng giá trị với tên NOM.

Hãy thử mô tả lại thủ tục NHÂN - lần này sử dụng các tham số (thủ tục COUNT không thay đổi):

NHỚ NHÂN (A, B);
10 0 CHỈ ĐỊNH MF;
20 0 CHỈ PR;
30 ĐẾN KHI ĐẾM LẶP LẠI ÍT HƠN: COUNT;
40 PR IN;
HOÀN THÀNH;

Bây giờ, để độ biến thiên là 47 và 34, chỉ cần viết:
NHÂN(47, 34);
Và gọi thủ tục tương tự để lại

nhân giá trị của tên T và K sẽ như thế này:
: NHÂN (T, K);

Nhiệm vụ 4.3. Mô tả quá trình CASE với hai tham số. Thủ tục phải in cả hai và phần còn lại của phép chia tham số thứ nhất cho tham số thứ hai, chẳng hạn như khi gọi
:DEL(28,5);
Máy tính sẽ in:
ĐỊNH LƯỢNG=5, CÒN LẠI=3

Nhiệm vụ 4.4. Mô tả quy trình GCD với hai tham số để tính ước chung nhất của hai số tự nhiên (xem «Kvant», 1970, số 9, trang 48).

Vì vậy, chúng ta đã làm quen với cấu trúc cơ bản của ngôn ngữ Robik. Tất nhiên, đây là một ngôn ngữ mang tính giáo dục, đơn giản hóa, bạn không thể viết một chương trình lớn trong đó, nhưng các khái niệm như toán tử và chỉ thị, giá trị, thủ tục và tham số, điều kiện, toán tử và vòng lặp, lệnh gán và in sẽ rất hữu ích cho chúng ta khi nghiên cứu các ngôn ngữ hữu ích và thú vị hơn.

G. Zvenitsorodsky
