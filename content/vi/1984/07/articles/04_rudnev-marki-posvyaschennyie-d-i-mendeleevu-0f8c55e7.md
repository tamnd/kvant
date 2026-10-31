---
id: 1984-7-rudnev-marki-posvyaschennyie-d-i-mendeleevu-0f8c55e7
issue: kvant_1984_7
year: 1984
number: "7"
title: Tem dành riêng cho D. I. Mendeleev
authors:
  - Рудов В. А.
rubric: raznoe
rubric_sub: Разное
page_first: 10
page_last: 15
page_labels: 8, 13
tag: MATO
lang: vi
source: kvant_digital
extraction: vision
content_sha256: ea4ae7b9c1ddbd4268c9d04fec4ce84556d72ab3d09f91beb11e2ff9a611dfa1
prompt_sha256: draft-1
translated_from: content/ru/1984/07/articles/04_rudnev-marki-posvyaschennyie-d-i-mendeleevu-0f8c55e7.md
source_content_sha256: 7ced247b473b4fa83ac9a7e829d50893233106485b677e8f1cb04d409bca83eb
translation_model: draft
translation_run: vi-draft-2026-10-31
translation_quality: draft
---

⟦folio 8⟧

do sự phân hạch tự phát của hạt nhân nặng. Tuy nhiên, có những đề xuất về mặt lý thuyết cho rằng hạt nhân của các nguyên tố có điện tích 114 và 126 có thể khá ổn định nên có lẽ chúng ta sẽ thấy

Góc sưu tầm

Con tem dành riêng cho
D. I. Mendeleev

Chi nhánh Liên Xô liên tục dành tặng nhiều tấm biển bưu chính khác nhau cho nhà khoa học xuất sắc người Nga Dmitry Ivanovich Mendeleev. Bốn con tem đầu tiên được phát hành vào năm 1934, nhân kỷ niệm 100 năm ngày sinh của D. I. Mendeleev. Một trong số đó mô tả tượng đài của nhà khoa học vĩ đại, được dựng lên vào năm 1932 tại Leningrad. Thương hiệu này được bao gồm trong lựa chọn của chúng tôi.

Vào tháng 8 năm 1951, một loạt 16 con tem được phát hành dành riêng cho các nhà khoa học xuất sắc của Nga. Ở giữa chúng ta thấy một con tem màu xanh có chân dung của D.I. Mendeleev. Con tem tiếp theo có chân dung của ông trên phông nền là tòa nhà Đại học Leningrad được phát hành vào năm 1957 nhân kỷ niệm 10 năm ngày mất của nhà khoa học. Năm 1969, nhân kỷ niệm 100 năm hệ thống tuần hoàn, một con tem mới được phát hành có chân dung của Mendeleev và một bưu phẩm có bản fax của một trong những biến thể đầu tiên của hệ thống tuần hoàn.

Lựa chọn của chúng tôi cũng bao gồm một con tem của Cộng hòa Nhân dân Ba Lan dành riêng cho D. I. Mendeleev.

V. Rudov

8

⟦folio 13⟧

thế cờ và sau đó phần nào trả lời câu hỏi liệu Trắng có thắng ở đó hay không.

Có lẽ bạn đã đồng ý tại sao việc này vẫn chưa được thực hiện. Việc xây dựng được mô tả chỉ có thể thực hiện được từ quan điểm trừu tượng toán học. Thực sự không thể thực hiện được nó do số lượng lớn tất cả các thế cờ. Nó đã được chứng minh rằng có một động thái tối ưu ở mọi vị trí. Tuy nhiên, không có cách nào ngắn gọn (ví dụ, một công thức) để tìm ra nó.

Nhưng tất nhiên, điều này không thể thực hiện được trên thực tế, không phải đối với tất cả các vị trí mà chỉ đối với một phần - ví dụ: đối với một số trò chơi kết thúc?

Trò chơi kết thúc từng phần nhỏ

Sử dụng phương pháp sóng ngược, tác giả có thể dạy máy tính chơi trò chơi cuối cùng “vua, hậu và tốt chống lại vua và hậu” (KFP-KF), với điều kiện là quân tốt trắng nằm trên ô g7 và “vua, quân và quân tốt chống lại vua và quân” ​​(KLP-KR) *) với bất kỳ vị trí nào của quân tốt. Cỗ máy tàn cuộc này không chỉ chơi giỏi hơn con người mà còn di chuyển tối ưu ở mọi vị trí. Do đó, các trò chơi có kết quả thấp có thể được phân tích chính xác trên máy tính.

Tuy nhiên, việc phân tích như vậy hoàn toàn không dễ thực hiện, bởi vì độ phức tạp của nó nằm ở giới hạn khả năng của máy tính hiện đại. Vì vậy, trong tàn cuộc KLP-KL cần phải xem xét khoảng một tỷ vị trí. Và nếu ghi lại từng vị trí

*) Công việc cuối cùng được thực hiện bởi một nhóm lớn dưới sự lãnh đạo của V.L. Arlazarov.

chỉ dành một vài “bit” (ký tự 0 hoặc 1 trong bộ nhớ máy), khi đó nhiều vị trí sẽ chỉ chiếm bộ nhớ của máy (cả “RAM” và “bên ngoài”). Do đó, để phân tích máy các trò chơi có kết quả nhỏ trong các ứng dụng hiện đại, một số kỹ thuật đặc biệt nhằm mục đích sử dụng tiết kiệm tài nguyên máy tính. Chúng tôi sẽ chỉ tập trung ngắn gọn vào một trong những kỹ thuật này (phân rã), sử dụng ví dụ về trò chơi kết thúc KLP-KL.

Chúng ta hãy nhớ rằng máy bài toán là thứ hạng của đồ thị Δ của tất cả các vị trí, xảy ra lỗi khi dỡ kết thúc KLP-KL. Tất nhiên, số vị trí trong Δ lớn hơn số vị trí KLP-KL (ví dụ đổi quân xe đưa chúng ta đến tàn cuộc KP-K, quân hậu cho KFL-KL, v.v.), nhưng con số này ít hơn đáng kể so với các vị trí ở cột Γ của toàn bộ ván cờ. Hơn nữa, bản thân đồ thị Δ có thể được chia thành nhiều phần (phân vùng này được hiển thị trong Hình 4). Bản chất của phương pháp phân rã là xếp hạng các phần này một cách riêng biệt. Kỹ thuật này đạt được mục tiêu vì các kết nối giữa các bộ phận không quá phức tạp: một phần, chúng không tạo thành các chu trình định hướng *) (xem Hình 4). Đồ thị như vậy được gọi là không có chu kỳ.

Bài toán 2. Chứng minh rằng các đỉnh của đồ thị hàm mũ có thể được đánh số sao cho bất kỳ cung nào cũng đi từ đỉnh có số cao hơn đến đỉnh có số nhỏ hơn.

Vì vậy, việc nghiên cứu đồ thị Δ được rút gọn thành nghiên cứu về một loạt các tàn cuộc; tuy nhiên, một số vẫn còn lớn.

*) Điều này có nghĩa là bạn không thể rời khỏi bất kỳ đỉnh nào và di chuyển theo hướng mũi tên để quay lại đỉnh đó.

Sơ đồ tàn cuộc, lỗi phát sinh từ các vị trí như KLP-KL khi trạng thái của quân cờ thay đổi (bằng cách bắt hoặc thăng cấp một con tốt). Để thuận tiện, một số tàn cuộc đã được lược bỏ mà không ảnh hưởng đến việc nghiên cứu tàn cuộc chính KLP-KL.
