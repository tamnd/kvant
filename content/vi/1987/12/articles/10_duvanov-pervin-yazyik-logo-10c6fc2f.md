---
id: 1987-12-duvanov-pervin-yazyik-logo-10c6fc2f
issue: kvant_1987_12
year: 1987
number: "12"
title: Biểu tượng ngôn ngữ
authors:
  - Дуванов А. А.
  - Первин Ю. А.
rubric: raznoe
rubric_sub: Разное
page_first: 40
page_last: 43
page_labels: 38-41
tag: 0CGP
lang: vi
source: kvant_digital
extraction: vision
content_sha256: 8bb1ff6b0e3461b0afadebb4b91c72f3f6b1facd14a525763850c00f46fbf1df
prompt_sha256: draft-1
translated_from: content/ru/1987/12/articles/10_duvanov-pervin-yazyik-logo-10c6fc2f.md
source_content_sha256: 06ad9f09150fb71b69255b277de9b8c52a2577a7002ef725479cf3960b1d0f71
translation_model: draft
translation_run: vi-draft-2026-10-31
translation_quality: draft
---

⟦folio 38⟧

Biểu tượng ngôn ngữ
Bài 3: Đệ quy, hàm

A. A. DUVANOV,
Yu. A. PERVIN

Mọi thứ trở lại bình thường
Thực hiện quy trình CIRCLE
(xem Bài 2 số cuối «Kvant»), Rùa sống hết một lượt và ở lại. Hãy tận hưởng việc xem cô ấy chạy trên màn hình hiển thị! Vì vậy, tôi muốn làm cho cô ấy quay đi quay lại. Đây là cách thực hiện:

ĐÂY LÀ MỘT CARUSEL :R
CIRCUM :R
CARUSEL :R
KẾT THÚC

Thủ tục này có mô tả không có đặc quyền: nó bao gồm lệnh gọi đến cùng một thủ tục. Một thủ tục gọi chính nó được gọi là đệ quy và lệnh gọi của nó được gọi là đệ quy. Bạn có thể gặp phải các phép đệ quy thường xuyên và bất ngờ ngay cả khi không học về khoa học máy tính. Các nghệ sĩ yêu thích hình-trò đùa: hình chiếu cảnh một con tritel đang xem màn hình TV, trên đó có thể nhìn thấy một con tritel đang nhìn vào màn hình... v.v. Một ví dụ về đệ quy “linterature” là một bài thơ hay về một linh mục nuôi một con chó.

Bằng cách gọi thủ tục đệ quy CARUSEL, bạn có thể thấy rằng nó không tốt lắm: nó khiến Rùa tội nghiệp phải chạy vòng quanh mà không dừng lại... trong khi xe đang chạy.

Để dừng Rùa được điều khiển bằng quy trình đệ quy, bạn phải tìm được số vòng đã hoàn thành và so sánh biến này với một giá trị nhất định. Nếu bạn lấy một biến có tên COUNTER làm bộ đếm vòng, bạn có thể theo dõi các vòng bằng lệnh

TẠO “BỘ ĐẾM: BỘ ĐẾM+1,
cần có trong phần mô tả quy trình CARUSEL ngay sau lệnh gọi CIRCLE : R (dường như bạn sẽ phải thực thi lệnh ngay từ đầu để chương trình dự định hoạt động chính xác

LÀM “ĐẾM 0;
Tại sao?).

Nhưng để so sánh hai giá trị, bạn cần một giá trị mới

⟦folio 39⟧

đội. Lệnh điều kiện có dạng điều kiện ECIF [lệnh list-1] [lệnh list-2]

Danh sách lệnh trong ngoặc vuông thể hiện một trong hai khả năng tiếp tục của chương trình: trong trường hợp khi các điều kiện được viết sau từ ECLI là đúng thì các lệnh trong danh sách đầu tiên sẽ được thực thi (và toàn bộ danh sách thứ hai bị bỏ qua!), và ngược lại, nếu các điều kiện sai thì danh sách đầu tiên sẽ bị bỏ qua và các lệnh trong danh sách thứ hai sẽ được thực thi. Một điều kiện (chính xác hơn là các điều kiện đơn giản) là hai biểu thức được kết nối bằng các dấu quan hệ “<”, “>”, “>=” (lớn hơn hoặc bằng), “<=” (nhỏ hơn hoặc bằng), “=”, “/=” (không bằng). Xác định một điều kiện theo cách này có thể đúng hoặc sai. Ví dụ: các điều kiện của lệnh ECLI: $R/2 > 3.14*2$ [CHUYỂN TIẾP 50] [BACK 50] đầu tiên độ đúng của điều kiện được tính theo giá trị hiện tại $R$, và nhận được phản hồi tích cực đáp số, gửi Rùa về phía trước, nếu không thì gửi nó về phía sau.

Sau đó, nếu điều kiện đúng, lệnh danh sách sẽ được thực thi và nếu điều kiện sai thì máy... không làm gì mà chỉ chuyển sang thực hiện lệnh chương trình tiếp theo, nếu có. Chúng tôi sẽ sử dụng mẫu lệnh này cho lời giải đã giao hàng bài toán, khiến Rùa dồn vào một vòng tròn chẳng hạn 17 lần. Để làm điều này, bạn cần viết mô tả quy trình

đây là một ĐI BỘ:$R$

CARUSEL:$R$

đây là CARUSEL:$R$
TRUNG TÂM:$R$

NẾU BỘ ĐẾM<17 [Băng chuyền:$R$]

Lần này, thủ tục CAROUEL, mặc dù vẫn là đệ quy, nhưng không được gọi mọi lúc mà chỉ khi giá trị của biến COUNTER không vượt quá 17. Lưu ý rằng trong quy trình WALK, cần phải đặt trước giá trị ban đầu của bộ đếm về 0. Một chương trình như vậy, sau khi hoàn thành công việc của mình, sẽ để lại biến COUNTER bằng 17. Các biến không phải là tham số của thủ tục và được sử dụng cả trong thủ tục và trong chương trình gọi nó dưới cùng một tên và có cùng giá trị được gọi là toàn cục (so sánh với định nghĩa của biến cục bộ ở cấp trước đó). Biến COUNTER trong ví dụ trước là biến toàn cục. Do đó, người lập trình phải biết rằng lệnh gọi thủ tục WALK có thể thay đổi giá trị của biến toàn cục COUNTER đã tồn tại trước lệnh gọi. Bạn có thể thoát khỏi giới hạn này bằng cách đặt COUNTER làm tham số thủ tục: tham số luôn cục bộ. Thủ tục này được mô tả

đây là CARUSEL :$R$ :COUNTER
CIRCUM:$R$
KIẾM “BỘ ĐẾM: BỘ ĐẾM+1”
ECIF: BỘ ĐẾM<17 [BĂNG TAY :$R$]
KẾT THÚC

Bây giờ thủ tục trả về WALK là không cần thiết. Gọi CARUSEL 50 0

cung cấp chuyển động gấp 17 lần trong một vòng tròn có bán kính 50. Chương trình không tránh khỏi việc gán giá trị ban đầu, nhưng giờ đây nó thực hiện điều này không phải dưới dạng một lệnh riêng biệt mà là giá trị được đặt của tham số thực.

Nhiệm vụ 1. Viết lại quy trình CAROUSEL để Rùa có thể chạy quanh bất kỳ số vòng tròn nào.

Trong bài học trước, chúng ta đã thấy rằng bất cứ khi nào biết số lượng hành động giống nhau được lặp lại, chúng ta có thể sử dụng lệnh REPEAT. Điều này có nghĩa là chúng tôi có thể thực hiện việc này trong hình 1.

⟦folio 40⟧

một nhiệm vụ đơn giản - Rùa đi vòng quanh vòng tròn.

Nhiệm vụ 2. Thay đổi lại chương trình CARUSEL, loại bỏ đệ quy và sử dụng lệnh vòng lặp.

"Đệ quy" hình trên trang. Chúng tôi sẽ không lập trình 38. Nhưng một phần của nó - hình chữ nhật bên trong hình chữ nhật (hình 1) - rất dễ truy vấn:

ĐÂY LÀ LẦN LẠI :SIDE
LẶP LẠI 2 [B: BÊN R 90 V
1.5 * :BÊN P 90]
NS V:BÊN / 2 P 90 V
1,5 * :BÊN / 2 L 90 RUR
KIẾM “BÊN:BÊN * 0,4
ĐỆ LẠI :SIDE
KẾT THÚC

Thói quen này sẽ vẽ các hình chữ nhật lồng nhau mà không dừng lại. Hình chữ nhật cuối cùng (nhưng có thể lặp lại vô tận!) Được vẽ với giá trị SIDE tối thiểu, tại đó điều kiện SIDE > 1 vẫn được thỏa mãn. Làm thế nào để dừng thủ tục?

Hình 2, a-z được thực hiện bằng thủ tục đệ quy SPIRAL với hai tham số.

Bài toán 3. Thực hiện theo mô tả quy trình SPIRAL, sao chép hình 2, a-z.

Thủ tục và chức năng

Hãy để chúng tôi giới thiệu khái niệm *đơn thuốc* như một mệnh lệnh nhất định được đưa ra cho một chiếc máy ở dạng mà nó có thể hiểu được. Chúng tôi sẽ gọi các hướng dẫn đó là FORWARD, buộc máy thực hiện một số hành động nhất định mà không tính toán kết quả, *lệnh* và cũng như “+”, tính toán các giá trị - *hoạt động*.

Tập hợp các lệnh đếm trong Logo tương đối nhỏ. Bằng cách mô tả các quy trình, chúng tôi thông báo các lệnh mới cho máy. Ví dụ: bạn có thể nhập lệnh
VUÔNG α
Tôi vẽ một hình vuông có cạnh α (α là một biểu thức số học). Để làm được điều này, chỉ cần biết mô tả trong bộ nhớ máy tính là đủ

Đây là hình vuông :A
LẶP LẠI 4 [TIẾP THEO :A QUYỀN 90]
KẾT THÚC

Khi thực hiện một lệnh (hoặc thủ tục), máy tính sẽ thực hiện một số hành động - di chuyển Rùa, hiển thị thông báo trên màn hình, tổ chức các lần lặp lại. Khi thực hiện thao tác ico, máy không chỉ thực hiện các hành động được quy định mà còn (đây là điều chính!) tạo ra kết quả là một giá trị duy nhất nhất định (tổng, hiệu, ...).

Chúng ta đã sử dụng các phép tính số học: cộng, trừ, nhân, chia. Đối với các phép tính toán học phức tạp hơn, cần có các phép tính tính giá trị của hàm. Trong Logo các phép toán cũng được viết dưới dạng tên α, (1)
trong đó “tên” là mã định danh hàm, α là biểu thức mà hàm hoạt động trên đó, tức là toán hạng của phép toán. Các hoạt động và hàm có thể có nhiều toán hạng.

Dưới đây là một số tên được dành riêng trong Logo để biểu thị các thành phần hàm: SIN - sin, COS - cosine, TAN - tangent, ARCTAN - arctigen, SQRT - căn bậc hai, RND - hàm tạo số ngẫu nhiên.

Ví dụ, biểu thức
$$\frac{\mathrm{tg} 2 + \sqrt{\sin a + 2}}{2}$$

sẽ chuyển sang Logo ở dạng
$$\frac{TAN 2 + SQRT(SIN :A + 2)}{2}.$$

Biểu thức RND có thể được sử dụng làm trường hợp các số ngẫu nhiên trong khoảng (0; N-1).

Đối với các thao tác quen thuộc “+”, “—”, “*”, “/”, Logo cũng cung cấp các tên: ADD cho “+”, TRỪ cho “—”, NHÂN cho “*”, CHIA cho “/”. Các phép toán này cũng có thể được viết dưới dạng (1) với hai tham số toán hạng:
tên αβ (α và β là các biểu thức số học).

⟦folio 41⟧

Do đó, biểu thức $x+1$ có thể viết dưới dạng
BỔ SUNG :x1
Để viết biểu thức (2) có một biểu thức tương đương:
PHẦN GẤP TÂN 2 SQRT
THÊM TỘI :A 2 2

(khoảng cách bên ngoài phù hợp với dạng ký hiệu (3) và (5)!). Việc ghi các biểu thức ở dạng (4), khi tên của thao tác được đặt trước toán tử, được gọi là *tiền tố*, trái ngược với cách ghi *infix* quen thuộc hơn, khi tên (dấu) của thao tác được đặt giữa toán tử. Ví dụ: $2+3$ là dạng ký hiệu trung tố,
BỔ SUNG 2 3 là dạng tiền tố của cách viết cùng một thao tác.

Bài 4. Viết lại biểu thức
$$\frac{\sqrt{\sin^2 a + \cos^2 a}}{a+1}$$

tới Logo, sử dụng mẫu ký hiệu tiền tố.

Hình thức của các thao tác viết (1) và (4) làm cho chúng có thể áp dụng rõ ràng cho các lệnh và lệnh gọi thủ tục. Tuy nhiên, chương trình ADD :A :B (cũng như :A+:B) sẽ gây nhầm lẫn trên máy tính - phải làm gì với kết quả thu được? Để tránh sai sót, hãy nhớ rằng các thao tác chỉ có thể được sử dụng trong biểu thức; Ví dụ:

![Diagram](image)

Quy trình LIMIT sử dụng hàm căn bậc hai tích hợp sẵn của Logo SQRT. Tuy nhiên, bạn có thể tạo các hàm của riêng mình trong Logo, giống như khi bạn mô tả các quy trình. Sự khác biệt duy nhất giữa mô tả hàm và mô tả quy trình là sự hiện diện bắt buộc của lệnh RETURN $\alpha$ trong mô tả hàm.

Kết quả là lệnh này trả về giá trị của biểu thức $\alpha$ cho chương trình gọi.

Vì vậy, mô tả hàm người dùng (do người lập trình tạo ra) có dạng

Hình 3. Hình 4.

Hình 5.
