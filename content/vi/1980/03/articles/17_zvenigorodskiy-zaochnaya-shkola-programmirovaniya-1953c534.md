---
id: 1980-3-zvenigorodskiy-zaochnaya-shkola-programmirovaniya-1953c534
issue: kvant_1980_3
year: 1980
number: "3"
title: Trường lập trình tương ứng
authors:
  - Звенигородский Г. А.
rubric: raznoe
rubric_sub: Разное
page_first: 50
page_last: 54
page_labels: 48, 50, 51, 52
tag: DFKN
lang: vi
source: kvant_digital
extraction: vision
content_sha256: 4a6b0a4f299d91f90d5e69696024e3c66d064eab8561c4711544d8f8507ffc12
prompt_sha256: draft-1
translated_from: content/ru/1980/03/articles/17_zvenigorodskiy-zaochnaya-shkola-programmirovaniya-1953c534.md
source_content_sha256: ac00f557c2a00bcaebfe967195039cf9becfb5b890f19667b7a56b467de820a1
translation_model: draft
translation_run: vi-draft-2026-10-31
translation_quality: draft
---

⟦folio 48⟧

Trường lập trình tương ứng

Bài 7: Hàm, đồ thị, local và text trên Rapier

Hàm và đồ thị

Trong Bài 6 («Kvant», Số 2), chúng tôi đã nghiên cứu mô tả các quy trình bằng ngôn ngữ Rapier. Đồng thời, chúng tôi chỉ xem xét những quy trình trong đó tên kết quả không được chỉ định. Tuy nhiên, sơ đồ cú pháp cung cấp một phiên bản mô tả thủ tục sử dụng tên kết quả. Bây giờ chúng ta sẽ giải quyết các thủ tục như vậy.

Một thủ tục có mô tả chứa tên kết quả được gọi là hàm trong ngôn ngữ Rapier. Giá trị của hàm là giá trị được gán cho tên kết quả (tức là tên theo sau dấu =>) sau khi sử dụng hàm. Nói chung, giá trị này phụ thuộc vào giá trị của các tham số được chỉ định trong tiêu đề thủ tục.

Đầu tiên chúng ta hãy xem máy tính làm gì khi lần đầu tiên nó được mô tả một chức năng. Ví dụ: nếu chương trình nói:

PERC QUÁT X => RES;
2*X! 2—5*X+10 —> RES; KSC;

Máy tính sẽ chọn một khối bộ nhớ, trao quyền chủ động cho nó.

Bây giờ hãy xem máy sẽ gọi hàm được lưu trong bộ nhớ như thế nào. Điều quan trọng cần nhớ là, không giống như thủ tục thông thường, lệnh gọi hàm có thể xảy ra trong một biểu thức. Ví dụ: nếu trong cùng một chương trình có những quy định như vậy:

28.5 — > A;
5*(A+KBAT(2)) — > C;

Đầu tiên máy tính sẽ ghi số 28,5 vào khối bộ nhớ có tên A (nghĩa là nó sẽ gán cho tên A giá trị 28,5). Để đáp ứng yêu cầu thứ hai, máy tính phải cộng giá trị của biểu thức A và KBAT(2). Máy tính sẽ chỉ đọc phần đầu tiên trong khối bộ nhớ có tên A. Biểu thức thứ hai là lệnh gọi hàm. Để tìm ra giá trị của nó, máy tính phải tìm mô tả của hàm này trong bộ nhớ, gán nó làm tham số (trong trường hợp của chúng tôi, tham số X sẽ được gán giá trị 2), thực thi tất cả các toán tử và đọc giá trị của tên kết quả. Dễ dàng tính toán rằng tên RES sẽ nhận giá trị 8. Số này sẽ được dùng làm giá trị của biểu thức KBAT(2). Cuối cùng tên C sẽ nhận được giá trị 182,5.

Cũng có thể có các biểu thức phức tạp hơn với các hàm: KBAT(2+KBAT(1*(-KBAT(2))))

Nhiệm vụ 7.1. Tính giá trị của biểu thức này.

Ngôn ngữ Rapier có các chức năng tiêu chuẩn SIN (X), COS (X), EXP (X), LN (X), ARCTAN (X) và một số chức năng khác. Giá trị của hàm mũ EXP(X) sẽ là $e^X$, trong đó $e \approx 2.71828$, từ ARCTAN biểu thị arctigen, LN biểu thị logarit tự nhiên. Học sinh lớp sáu và lớp bảy vẫn chưa

⟦folio 50⟧

chương trình:
5.21*3 —> A; 2*A—> B;
QUCUBE (2)-> C;
IN('A=', A, 'B=', B, C=', C);

Chắc hẳn anh ấy sẽ rất bất ngờ khi máy tính in ra:
A=4 B=8 C=8,
suy cho cùng thì anh ấy muốn gán những ý nghĩa hoàn toàn khác nhau cho cái tên A và B!

Để tránh những rắc rối như vậy, bạn có thể khai báo các tên được sử dụng trong quy trình bằng cách sử dụng câu lệnh sau (dấu hiệu “biểu thị khoảng trống):

Ví dụ: quy trình QACUBE có khai báo tên sẽ trông như thế này:
PERC VACUBE X=>Y;
TÊN A'B;
X!2—> A; X!3—> B;
NẾU A>B ĐẾN A—>Y KHÁC B—>Y TẤT CẢ; KSC;

Tên được khai báo chỉ được biết trong thủ tục và không ảnh hưởng đến các phần khác của chương trình. Điều này trước hết có nghĩa là sau khi sử dụng quy trình, bạn không thể đọc được ý nghĩa của những tên này. Thứ hai, nếu có những tên khác có cùng chỉ định trong chương trình thì ý nghĩa của chúng sẽ không thay đổi khi sử dụng quy trình. Ví dụ: nếu chương trình trên được sử dụng với phiên bản mới của quy trình QUACUBE thì máy tính sẽ in
A=15.63 B=31.26 C=8,
tức là chính xác những gì lập trình viên thứ hai cần.

Các tham số thủ tục và tên kết quả có cùng thuộc tính với tên khai báo nên không cần khai báo.

Các tên chỉ được biết trong một thủ tục được gọi là cục bộ (nghĩa là cục bộ, nội bộ)

những cái tên. Nếu một thủ tục phải được sử dụng nhiều lần trong một chương trình lớn, thì tất cả các tên trong đó phải được đặt cục bộ - khi đó sẽ không có sự trùng hợp ngẫu nhiên trong các chỉ định tên. Đây là cách tất cả các thủ tục và chức năng tiêu chuẩn được tổ chức.

Làm việc với văn bản

Nếu theo dõi tốt từ "bảo vệ" thì kết quả sẽ là "vội vàng".

Các biểu thức ngôn ngữ Rapier có thể không chỉ bao gồm các con số mà còn cả văn bản, cũng như tên có ý nghĩa là văn bản. Tất nhiên, các phép tính số học thông thường - cộng, trừ, nhân, chia, v.v. - không được áp dụng cho chúng. Đồng thời, có các thao tác đặc biệt để làm việc với văn bản:

1. Ghép nối (“dán”) văn bản. Thao tác này được biểu thị bằng dấu +, giống như phép cộng. Ví dụ: sau khi làm theo hướng dẫn 'IL'—>A; 'MÃ'—>B;
'KPO'+B+A—>C;

giá trị của tên C sẽ là văn bản 'CROCODILE'.

2. Xác định độ dài của văn bản, nghĩa là số lượng ký tự trong đó. Hoạt động này được biểu thị bằng dấu ≠. Ví dụ:
≠ 'Cá Sấu'—>A;
'THỎ'—>B;
≠ B+≠ 'SÓC'—>K;
IN('A=', A,'K=', K);

theo chương trình này máy tính sẽ in:
A=8 K=11

3. Cắt bỏ một phần văn bản. Đây có lẽ là thao tác thú vị nhất trên văn bản. Nó có thể được mô tả bằng sơ đồ này:

Giá trị của tên phải là văn bản và giá trị của biểu thức trong ngoặc vuông phải là số tự nhiên. Những con số này được coi là khởi đầu và

⟦folio 51⟧

các ký hiệu cuối cùng của khu vực thể hiện. Nếu một biểu thức được chỉ định trong ngoặc đơn thì một ký tự có số tương ứng sẽ được biểu thị. Ví dụ: hãy thực hiện các bài tập sau:
'Cá Sấu'—>K; 'DOE'—>L;
'CÚ'—>C;
'CÂY'—>E;

thì giá trị của biểu thức K [4:6] sẽ là văn bản 'CODE', giá trị của biểu thức L [2] sẽ là văn bản 'A' và giá trị của biểu thức K [4:5] + K[2:3] + C[3:4] sẽ là văn bản 'COW'.

Nhiệm vụ 7.5. Tìm giá trị của một biểu thức
S[1] + L[2] + K[2] + K[6] + E[1:2] + L[4] + E[3:4]

Các biểu thức trên văn bản cũng có thể được sử dụng trong điều kiện câu. Ví dụ: hãy thử mô tả một hàm có tham số là văn bản và kết quả là chữ cái định lượng 'A' trong văn bản này:
THƯ PERC TEK=>RES;
TÊN SỐ;
0—>RES; 1—>SỐ;
SỐ TẠM BIỆT=<(≠TEK)::
NẾU TEK [SỐ]='A' TOP+1—>RES ALL;
SỐ +1—>SỐ;
TẤT CẢ;
KSC;

Thao tác cắt một phần văn bản, không giống như hầu hết các thao tác khác, có thể được sử dụng ở bên phải mũi tên gán. Bằng cách này, bạn có thể thay đổi ý nghĩa của từng chữ cái và từng phần văn bản. Ví dụ: giả sử ý nghĩa của tên K là văn bản 'CROCODILE'. Rồi sau bài tập 'I'—>K[3]

giá trị của tên này sẽ là văn bản 'CRACKODIL' và sau lần gán tiếp theo
K[1:3] ≥K[4:6];

giá trị của tên này sẽ là văn bản 'QRAKRAIL'.

Nhiệm vụ 7.6. “Chỉnh sửa văn bản 'GUARD' để nó thành 'HURRAH'.

Bài 8: Set và tuple trên Rappier

Trong bài viết về Trường hè toàn thế giới lần thứ IV dành cho lập trình viên trẻ («Kvant», 1979, số 2), chúng tôi đã viết lý do tại sao cần có tập hợp, bộ dữ liệu và các loại dữ liệu phức tạp khác. Bài học thứ tám của trường tương ứng được dành để mô tả các phương tiện làm việc với các tập hợp và bộ dữ liệu trong ngôn ngữ Rappier.

Chỉ định một bộ

Ý nghĩa của bất kỳ tên nào trong ngôn ngữ Rappira, kết hợp với số, văn bản và mô tả quy trình, có thể là các cấu trúc dữ liệu phức tạp: bộ và bộ dữ liệu.

Bộ này được biểu thị bằng dấu ngoặc nhọn có dấu hoa thị: “* và *”. Bên trong dấu ngoặc, tất cả các phần tử của tập hợp được liệt kê, phân tách bằng dấu phẩy. Ví dụ: sau khi hoàn thành đơn hàng
"*1, 'Lập trình viên trẻ', 2, 'Lượng tử'*"—>A;
ý nghĩa của tên A sẽ trở thành một tập hợp. Các phần tử của bộ này là các số 1 và 2 và các dòng chữ 'LẬP TRÌNH TRẺ' và 'QUANTUM'.

Bất cứ điều gì có thể là ý nghĩa của một cái tên trong Rappier cũng có thể là một phần tử của một bộ. Một phần, các phần tử của một tập hợp có thể là các tập hợp khác:
“*1, 2, “*4, 5, VĂN BẢN*””—>B;

Trong ví dụ này, giá trị của tên B là một tập hợp gồm ba phần tử: hai số và một tập hợp.

Nếu một tên hoặc một biểu thức phức tạp hơn được chỉ định trong danh sách các phần tử của tập hợp thì giá trị của biểu thức đó sẽ trở thành một phần tử của tập hợp; ví dụ: sau khi hoàn thành một đơn đặt hàng
5—>A; 10—>V;
'HƯỚNG DẪN'—>S;
«*A, 4, 40*A+B, C[5]+
C[3:4]*»—>A;

ý nghĩa của tên A sẽ được đặt
"*5, 4, 210, 'HURRAH'*"
Nhiệm vụ 8.1. Giá trị của tên A và B sau khi thực hiện sẽ là bao nhiêu

⟦folio 52⟧

Chương trình Nenya:
'Cá Sấu' + " + 'GENE' -> A;
= A -> B;
(*A[(B+1)/2-3] + A[(B-1)/2+1] +
A[≠A-1] + A[3] + A[B] +
A[6] + A[2], A[4] + A[11] +
A[2*3] + A[8/4], A[2*2+2] +
A[1+1] + A[B] + A[4:5] +
A[B-1]*) -> A;
(*A, B+1, B+10*) -> B;

Đặt so sánh và kiểm tra thành viên
Các tập hợp và tên của chúng có thể được sử dụng trong các điều kiện (trong câu tuần hoàn và câu điều kiện).
Đặc biệt, hai bộ có thể được so sánh bằng dấu =. Như bạn đã biết từ một khóa học toán ở trường, hai tập hợp được coi là bằng nhau nếu chúng bao gồm các phần tử giống nhau, bất kể thứ tự các phần tử này được liệt kê như thế nào: tập hợp
(*'KHÔNG BIẾT', 'GRUM',
'ZNAYKA'*),
(*'ZNAYKA', 'KHÔNG BIẾT',
'CÀ CẮM'*)

bằng nhau, nhưng các bộ (*1, 2, 3*) và (*1 (*2, 3*)*) không bằng nhau.
Thủ tục PRINT in tập hợp ở dạng giống như nó được viết trong chương trình (nghĩa là tất cả các phần tử được in trong dấu ngoặc nhọn có dấu hoa thị cách nhau bằng dấu phẩy, trong khi văn bản sẽ được in không có dấu ngoặc kép). Thứ tự các phần tử khi in có thể tùy ý nên không thể tưởng tượng trước được, chẳng hạn bộ QUARTET trong nhiệm vụ 8.2 dưới đây có được in ra là (*DONKEY, GOAT, MONKEY, BEAR*)

hoặc
(*GẤU, LỪA, DÊ, KHỈ*)

hoặc một cái gì đó khác.

Nhiệm vụ 8.2. Máy ghi chú gì khi dùng chương trình như thế này:
(*1, 2*) -> X; (*'MONKEY', 'DONKLE', 'DÊ', 'GẤU'*) -> KBAPTET; (*X, KBAPTET*) ->

MIX1; (**KBAPTET, (*1+1, 1*), KBAPTET*) -> HỖN HỢP2; NẾU MIX1 = MIX2 THÌ IN ('BẤT CỨ BẠN NGỒI...')
ELSE IN ('2*2=4') TẤT CẢ;
NẾU KBAPTET = MIXTURE2 ĐỂ IN ('TỪ THAY ĐỔI NƠI CỦA CÔNG TY') ELSE IN ('SẢN PHẨM KHÔNG THAY ĐỔI') TẤT CẢ;

Điều kiện để một phần tử thuộc một tập hợp được viết bằng từ khóa IZ, tương ứng với ký hiệu ∈ trong ký hiệu toán học tổng quát. Ví dụ, điều kiện

'GẤU' TỪ KBAPTET

sẽ chỉ đúng nếu trong số các phần tử của tập hợp KBAPTET có văn bản 'BEAR'.

Đặt hoạt động
Hoạt động hợp của một tập hợp được ký hiệu trong Rapier bằng dấu +, và giao của một tập hợp được ký hiệu bằng dấu *. Ví dụ theo chương trình (*17, 1, 8, 27, 36, 5*) -> THÔNG BÁO; (*5, 25, 11, 17, 35, 4*) -> LƯU HÀNH2; IN('UNION=', CIRCULATION1 + CIRCULATION2); IN('INTERSECTION=', CIRCULATION1 * CIRCULATION2); Máy tính sẽ in:

ĐOÀN =
= (*17, 1, 5, 25, 11, 36, 27, 4, 35, 8*) GIAO TẮC = (*5, 17*)

Dấu - biểu thị sự khác biệt của tập hợp: tất cả các phần tử có trong tập thứ hai đều bị xóa khỏi tập thứ nhất; ví dụ theo chương trình:

(*'Sư tử', 'WOLF', 'FOX', 'HARE'*) -> (*'SQUIRREL', 'HARE', 'RABBIT'*) -> Predator; IN (NGƯỢC THỰC VẬT);

sẽ được in:

(** SÓI, CÁO, SƯ TỬ*)

Số phần tử của một tập hợp được biểu thị bằng dấu ≠, như đối với văn bản. Ví dụ: các phần tử giống hệt nhau trong một tập hợp chỉ được tính một lần, do đó phần tử của tập hợp đó

(*'Cá Sấu', 'GENA'*),
(*1, 1, 2, 1, 2, 1+1, 1, 1, 3-1, 3-2*)
bằng nhau và bằng 2.
