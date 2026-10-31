---
id: 1986-3-rozhdestvenskiy-hlebutin-programmirovanie-na-mikrokalkulyatore-vetvlenie-i-tsikl-1e2df95b
issue: kvant_1986_3
year: 1986
number: "3"
title: 'Lập trình trên máy vi tính: phân nhánh và lặp'
authors:
  - Рождественский В. В.
  - Хлебутин С. Г.
rubric: raznoe
rubric_sub: Разное
page_first: 47
page_last: 49
page_labels: 45-47
tag: NRUB
lang: vi
source: kvant_digital
extraction: vision
content_sha256: 424fc1920ff4509a05065089357a7792214204088916fe80d8ec5c8716c717b8
prompt_sha256: draft-1
translated_from: content/ru/1986/03/articles/16_rozhdestvenskiy-hlebutin-programmirovanie-na-mikrokalkulyatore-vetvlenie-i-tsikl-1e2df95b.md
source_content_sha256: b6c380b4b6ce5d8c1b12f2e17fe65c59e0f3240a9d8258effbe38e50cdd69436
translation_model: draft
translation_run: vi-draft-2026-10-31
translation_quality: draft
---

⟦folio 45⟧

Lập trình trên máy vi tính: phân nhánh và lặp

V. V. ROZHDESTVENSKY,
S. G. KHLEBUTIN

Ghi chú này chủ yếu dành cho học sinh lớp chín đang học khóa học “Cơ bản về Công nghệ Thông tin và Máy tính” và có quyền truy cập vào máy tính vi mô có thể lập trình.

Trong số trước «Kvant» Tôi nói về cách các chương trình đơn giản nhất được viết bằng ngôn ngữ thuật toán giáo dục có thể được “dịch thành mã của máy tính vi mô có thể lập trình”, tức là các chương trình đó có thể được tự động chuyển đổi thành danh sách các lệnh cho máy tính vi mô (xem bài viết của L. F. Sternberg “Lập trình trên máy vi tính: các chương trình đơn giản nhất”). Ở đây chúng tôi tiếp tục câu chuyện này. Chúng ta đang nói về việc dịch hai cấu trúc chính của ngôn ngữ thuật toán: phân nhánh và lặp. Bài thuyết trình được thực hiện liên quan đến máy tính vi mô Elektronka MK-54, nhưng với những thay đổi nhỏ, nó có thể được gắn vào các mẫu máy tính lập trình trong nước khác.

Trước hết, hãy xem máy tính hoạt động như thế nào ở chế độ tự động, tức là khi chương trình được thực thi mà không có sự can thiệp của con người. Để kiểm soát việc lựa chọn lệnh từ bộ nhớ, một ô đặc biệt gọi là bộ đếm địa chỉ được sử dụng.

Ô này có thể chứa bất kỳ địa chỉ bộ nhớ chương trình nào.

Nếu bạn nhấn phím C/P ở chế độ tự động, thao tác này sẽ yêu cầu máy tính bắt đầu vận hành tự động. Điều này có nghĩa là máy tính sẽ phân tích nội dung của ô nhớ chương trình mà bộ đếm địa chỉ trỏ tới, thực hiện thao tác này hoặc thao tác khác và thay đổi nội dung của bộ đếm địa chỉ. Những hành động như vậy được gọi là chu kỳ chương trình. Thực hiện liên tục các chu kỳ, chương trình sẽ đếm cho đến khi gặp lệnh STOP.

Nếu không có hoạt động chuyển tiếp nào trong chương trình thì trong quá trình thực hiện một chu kỳ xung nhịp, giá trị của bộ đếm địa chỉ sẽ tăng thêm một. Các hoạt động chuyển tiếp được thiết kế đặc biệt để thay đổi nội dung của bộ đếm địa chỉ cho thiết bị của chúng ta. Lệnh nhảy hoạt động như thế nào?

Hãy xem xét các lệnh BP và Fx∨0, trong đó ∨ biểu thị một trong các dấu của phép toán so sánh: <, =, ≥, ≠. Để các lệnh này hoạt động, cần sử dụng hai ô nhớ: một ô để lưu mã lệnh và ô tiếp theo để lưu một số địa chỉ.

Hoạt động của lệnh BP được thực hiện như sau: máy tính đặt vào bộ đếm địa chỉ địa chỉ mà chúng ta đã ghi vào ô tiếp theo của mã BP.

Lệnh Fx∨0 thực hiện như sau: nếu điều kiện x∨0 được thỏa mãn thì nội dung cũ của bộ đếm địa chỉ sẽ tăng thêm hai; nếu điều kiện không được thỏa mãn thì địa chỉ từ ô bên cạnh mã lệnh Fx∨0 sẽ được đặt trong bộ đếm địa chỉ.

Ví dụ 1. Hãy theo dõi sự thay đổi của bộ đếm địa chỉ trong quá trình thực thi luồng của chương trình sau (xem bảng bên dưới).

⟦folio 46⟧

Vì vậy, chúng tôi thấy rằng sự hiện diện của các thao tác nhảy có thể phá vỡ chuỗi tự nhiên (theo thứ tự địa chỉ) của lệnh và đây chính xác là điều cần thiết khi lập trình các cấu trúc “vòng lặp” và “nhánh”.

Thiết kế “chu kỳ”
Trong ngôn ngữ thuật toán, cấu trúc như vậy trông như thế này:
trong khi điều kiện
nc
loạt
kts
Để tạo điều kiện thuận lợi cho việc chuyển đổi cấu trúc “chu trình” sang ngôn ngữ máy tính, chúng tôi sẽ viết nó dưới một dạng hơi khác, cụ thể là:
Tạm biệt
v ∨ 0
loạt
kts
Ở đây v là biểu thức tranh luận, ∨ là một trong những dấu hiệu so sánh được mô tả ở trên.
Chúng tôi đề xuất sơ đồ sau để chuyển toán tử vòng lặp từ ngôn ngữ thuật toán sang ngôn ngữ máy tính (ở đây X biểu thị đỉnh của ngăn xếp):

Lưu ý rằng lệnh K NOP (không hoạt động), mặc dù nó không đòi hỏi bất kỳ hành động nào, nhưng rất thuận tiện cho việc thiết lập sự tương ứng giữa các từ khóa (tạm biệt, kts). ngôn ngữ thuật toán và các lệnh máy tính, đồng thời cũng giúp việc tuân theo logic của chương trình trở nên dễ dàng hơn. Căn chỉnh các bản ghi theo chiều dọc thuận tiện cho việc tìm địa chỉ nhảy và đọc chương trình.

Ví dụ 2. Hãy xây dựng chương trình tính m=n!

Trong ngôn ngữ thuật toán giáo dục, chương trình trông như thế này:

alg giai thừa (số nguyên m, n)
tranh cãi
độ phân giải
bắt đầu nguyên vẹn
đầu vào n
m:=1
i:=1
trong khi tôi<n
nc
i:=i+1
m:=m*i
kts
đầu ra m

lừa đảo
Xin lưu ý rằng chúng tôi đã chèn hai lệnh bổ sung vào nội dung chương trình (đầu vào và đầu ra) - chúng giúp việc dịch thuật dễ dàng hơn.
Chương trình bây giờ có thể được phát sóng. Đầu tiên, chúng ta mô tả vị trí lưu trữ của các biến dưới dạng bảng.

Biến n m i
Bộ nhớ RgO Rg1 Rg2

Chương trình được hiển thị trông như thế này:

Địa chỉ Lệnh Mã
00 C/P 50
01 X→PO 40
02 1 01
03 X→P1 41
04 1 01
05 X→P2 42
06 K NOP 54
07 P→X2 62
08 P→X0 60
09 - 11
10 F x<0 5C
11 22 22
12 P→X2 62
13 1 01
14 + 10
15 X→P2 42
16 P→X1 61
17 P→X2 62
18 X 12
19 X→P1 41
20 BP 51
21 06 06
22 K NOP 54
23 P→X1 61
24 C/P 50

⟦folio 47⟧

Thiết kế phân nhánh
Trong ngôn ngữ thuật toán, cấu trúc này được viết như sau:
nếu có điều kiện
rồi tập 1
nếu không thì tập 2
Tất cả
Để thuận tiện cho việc dịch sang ngôn ngữ máy tính, chúng tôi sẽ viết nó như thế này:
Nếu như
v ∨ 0
tập 1
nếu không thì
tập 2
Tất cả
Chúng tôi đưa ra sơ đồ dịch thuật sau:

Đối với toán tử nhánh “rút gọn” (nếu... thì... tất cả), sơ đồ dịch thuật có thể như sau:

Ví dụ 3. Hãy xây dựng chương trình tìm số lớn hơn của hai số a và b.

Trong ngôn ngữ thuật toán, chương trình này có thể được viết như sau (như trên, để dễ dịch chúng tôi đã giới thiệu thêm các lệnh đầu vào và đầu ra):

giá thầu alg (điều a, b, y)
apr a, b
độ phân giải

sự khởi đầu
nhập a, b
nếu a ≥ b
thì y := a
ngược lại y := b
Tất cả
đầu ra y

lừa đảo
Hãy viết địa chỉ của các biến dưới dạng bảng:

Biến a b y
Bộ nhớ Rg a Rg b Rg 0

Chương trình phát sóng như sau:

Địa chỉ Lệnh Mã Ngôn ngữ thuật toán
00 C/P 50
01 X→Pa 4-
02 C/P 50
03 X→Пb 4L
04 KNOP 54
05 P→Ha 6-
06 P→Xb 6L
07 — 11
08 F x ≥ 0 59
09 14 14
10 P→Ha 6-
11 X→P0 40
12 BP 51
13 17 17
14 KNOP 54
15 P→Xb 6L
16 X→P0 40
17 KNOP 54
18 P→X0 60
19 C/P 50

Tóm lại, chúng tôi lưu ý rằng các sơ đồ dịch thuật có thể tốt hơn hoặc kém hơn, nhưng chính sự hiện diện của chúng cho phép việc dịch thuật được thực hiện tự động và hầu như không có lỗi. Vì vậy, nếu một chương trình bằng ngôn ngữ thuật toán được viết chính xác thì việc đưa nó vào máy tính không hề khó khăn chút nào.

Sửa đổi
Trong số đầu tiên «Kvant» của năm nay, một hoạt động được phép thực hiện theo các điều kiện bài toán 2 của tùy chọn I ở trang 52. Bất đẳng thức trong các điều kiện phải được đọc như sau: log $\frac{1}{4} - 3x$ > 0.
