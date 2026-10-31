---
id: 1982-8-pervin-odnazhdyi-vecherom-v-seme-programmista-c5de1e53
issue: kvant_1982_8
year: 1982
number: "8"
title: Một buổi tối trong gia đình lập trình viên
authors:
  - Первин Ю. А.
rubric: raznoe
rubric_sub: Разное
page_first: 62
page_last: 64
page_labels: 60, 62
tag: C9YW
lang: vi
source: kvant_digital
extraction: vision
content_sha256: a92747a4f20019e699f9e3caeba064e83440aab95e8bde11254614bab915f371
prompt_sha256: draft-1
translated_from: content/ru/1982/08/articles/17_pervin-odnazhdyi-vecherom-v-seme-programmista-c5de1e53.md
source_content_sha256: 9d03b6d6b154c2ca323ed611c9b2a6280e2653631893415338d1f53c3a6a422b
translation_model: draft
translation_run: vi-draft-2026-10-31
translation_quality: draft
---

⟦folio 60⟧

Một buổi tối trong gia đình lập trình viên

Lập trình viên Ferstov có bốn người con - Nadya, Timur, Egor và Dina. Họ đều quan tâm đến lập trình. Vào buổi tối được đề cập, bố nhìn vào phòng trẻ em.

- Bạn có muốn tách rời vấn đề này về lập trình không?
- Nghiên cứu về lập trình? - các bạn đồng thanh hỏi. - Những thứ như vậy có tồn tại không?
- Tất nhiên là có. Đây là những chương trình nhỏ có chứa một số thủ thuật. Lời giải việc này bao gồm việc biên dịch một chương trình theo một chủ đề nhất định hoặc tìm kiếm một lỗi được giấu cẩn thận hoặc kiểm tra hành động của một chương trình được tạo sẵn. Đây chính xác là những gì tôi muốn cung cấp cho bạn. Trong chương trình có các biến i: số nguyên;
mảng m[1:2] : int;
i ← 1; m[1] ← 4; m[2] ← 5;
zilch(m[i]);
bạn thấy lệnh gọi thủ tục zilch, thủ tục này có quy trình mô tả sau đây zilch(x:int);
m[i] ← m[i] + 1;
i ← i + 1;
x ← x - 1
kết thúc;
Vui lòng xác định những giá trị m[1] và m[2] sẽ nhận được nhờ chương trình này.
- Chỉ thế thôi à?
- Tất cả.
- Nhưng nó rất đơn giản...
Người cha không có thời gian để trả lời. Điện thoại reo.

- Ferstov đang nghe đây!
Ở đầu dây bên kia, có người đang vội kể về những sự kiện mới nhất trong phòng thí nghiệm của Ferstov. Mặt anh nghiêm túc.
- Khỏe. Tôi sẽ đến đó bây giờ. Hãy tìm ra nó.
“Các bạn,” anh ấy nói với bọn trẻ, “Tôi sẽ chạy đến Trung tâm Máy tính đúng giờ.” Có lỗi trong quá trình vận chuyển của tôi. Tôi sẽ tìm, sửa và quay lại ngay. Trong lúc chờ đợi, hãy giúp đỡ về việc lập trình.
Và trước khi bọn trẻ kịp đặt câu hỏi với anh, Ferstov đã chạy lên cầu thang, vừa cài cúc áo khoác vừa đi. Các chàng trai bắt đầu thảo luận về nhiệm vụ.
- Đây là loại ngôn ngữ nước nào? - Nadia nói. — Đối với Pascal thì điều đó không quá tệ: tất cả các từ khóa đều là tiếng Nga. Và không phải Rapier - hãy nhìn những mũi tên buồn cười làm sao.
“Không có gì phải ngạc nhiên cả,” Yegor sáng suốt trả lời. - Có nhiều ngôn ngữ khác nhau. Mặc dù có những ký hiệu bất thường ở đây nhưng mọi thứ đều rõ ràng: mũi tên từ phải sang trái là một phép gán giống như trong Pascal, chỉ được ký hiệu khác; Một nhị phân giữa các số nguyên trong dấu ngoặc vuông phân tách giới hạn thay đổi chỉ số trong mảng. Vì vậy hãy bắt tay vào công việc ngay thôi.
Mọi người đều tự trang bị cho mình một cây bút chì và giấy, và trong một thời gian, sự im lặng như kinh doanh ngự trị.
- Sẵn sàng! - Timur là người đầu tiên hét lên. - m[1] bằng 3, và m[2] bằng 5.
“Không có loại nào cả,” chị gái Nadya phản đối, “cả hai số lượng, m[1] và m[2] đều bằng năm.”
“Cả hai bạn đều sai,” Yegor nói. — Đáp số như thế này: m[1] = 4, m[2] = 5.
Cô út Dina hơi rụt rè trước uy quyền của chị gái và các anh, lặng lẽ nói:
— Và tôi nhận được m[1] = 5, m[2] = 4.
May mắn thay, bố thực sự đã trở lại nhanh chóng. Những đứa trẻ ngay lập tức vây quanh anh ta, tranh giành nhau để đưa ra lời giải của mình.
“Hãy sắp xếp mọi việc theo thứ tự,” báo cáo đề xuất. - Nào, anh cả, bắt đầu!

⟦folio 62⟧

chương trình đứng $m[i]$. Vào thời điểm tuyên bố cuối cùng của thủ tục $n_{uuik}i=2$, và; do đó, câu lệnh cuối cùng của thủ tục sẽ được thực thi như sau:

$$m[2] \leftarrow m[2] - 1.$$

Và vì $m[2]$ được đặt ở đầu $m[2]=5$, nên sau khi hoàn thành quy trình và toàn bộ chương trình $m[2]=4$.

Với $m[1]$ thì khá đơn giản: đã được đặt ở đầu chương trình $m[1]=4$, giá trị này được tăng thêm 1 nhờ hành động của câu lệnh đầu tiên của quy trình $n_{uuik}$.

Những lời giải thích được viết ra, bọn trẻ im lặng nhìn nhau: “Bố sẽ thưởng cho một đứa!”

- Làm tốt lắm các bạn! Bạn đã làm rất tốt. Bạn không sao cả. Thực tế là bạn không biết gì về ngôn ngữ mà chương trình được viết và do đó, phương thức truyền tham số được phép trong ngôn ngữ này. Nhân tiện, ngôn ngữ như vậy không tồn tại trên thực tế: Tôi đã phát minh ra nó đặc biệt cho ban quản lý của chúng tôi. Và trong mỗi lần triển khai các ngôn ngữ hiện có, một hoặc nhiều cách truyền tham số được phép luôn được xác định. Do đó, trong Rapier quen thuộc, các tham số từ chương trình gọi đến các thủ tục được gọi chỉ có thể được truyền theo giá trị. Và trong ngôn ngữ ALGOL-60, tôi cũng sử dụng phương pháp này bằng cách viết (đôi khi còn gọi là chuyển theo tên). Hơn nữa, việc chuyển bằng chính tả được coi là trong ALGOL là cách giao tiếp tự nhiên nhất giữa các thủ tục, do đó, việc chuyển bằng chính tả được giả định cho các tham số được truyền “theo mặc định”. Và trong những trường hợp cần sử dụng tính năng truyền theo giá trị, trước tên của các tham số được truyền khi mô tả chúng trong thủ tục ALGOL-60 được gọi, phải viết từ khóa `value` (giá trị).

Trong một ngôn ngữ như Algol-$W$, trong số một số ngôn ngữ có thể chấp nhận được, phương pháp mà Timur sử dụng là phương pháp truyền đạt giá trị kết quả. Các tham số được truyền cho một thủ tục theo cách này được đánh dấu trong tiêu đề của nó bằng từ khóa `value-result` (giá trị-kết quả). Ví dụ, Forteran cho phép phương thức truyền tham số theo địa chỉ (hoặc đôi khi được gọi là truyền tham số).

Trong Pascal, các tham số thường được truyền theo giá trị (mà “theo mặc định” không được ghi chú cụ thể theo bất kỳ cách nào) và khi sử dụng truyền theo tham chiếu - truyền một biến tham số, trước tên của các tham số tương ứng, cần phải viết các từ `var` trong tiêu đề của mô tả quy trình. Đọc về nó trong Bài học 20 của Trường Viết mã. Và nếu bạn muốn tìm hiểu thêm về các phương pháp truyền tham số khác nhau, thì tôi sẽ giới thiệu cho bạn, chẳng hạn như cuốn sách của T. Prat “Ngôn ngữ lập trình: Phát triển và triển khai,” do nhà xuất bản Mir xuất bản năm 1979. Bạn sẽ tìm thấy nó trên kệ phía trên bàn làm việc của tôi.

Tôi phải nói với bạn rằng sự đa dạng của kết quả bạn nhận được không chỉ được giải thích bằng các cách truyền tham số khác nhau. Sau đó, khi tham số là một biến đơn giản (và không được lập chỉ mục, như trong ví dụ của chúng ta), tất cả các phương thức sẽ cho cùng một kết quả. Và chỉ những cấu trúc dữ liệu phức tạp mới được truyền theo những cách khác nhau theo những cách khác nhau.

Hãy tóm tắt. Trước khi lập trình truy cập vào các thủ tục, bạn cần biết phương pháp truyền tham số nào được phép trong ngôn ngữ đã chọn (và thậm chí có thể thay đổi lựa chọn ngôn ngữ dựa trên phương thức truyền mà bạn thích); bạn cũng cần biết các quy tắc định dạng phương thức truyền tải tương ứng trong ngôn ngữ. Thông thoáng?

“Tôi hiểu rồi,” Nadya trả lời thay mọi người. Phần còn lại theo sách

Và Yegor đã nói những lời hoàn toàn ra lệnh cho cha mình:

- Bạn biết không: Tôi cũng sẽ nghĩ ra cái này cho bạn về lập trình. Về thủ tục đệ quy!

- Tốt lắm, đi thôi. Chỉ có cái mới này là dành cho ngày mai. Hôm nay muộn rồi.
