---
id: 1972-11-varpahovskiy-mashina-uchitsya-raspoznavat-0d0a7746
issue: kvant_1972_11
year: 1972
number: "11"
title: Máy học cách nhận biết
authors:
  - Варпаховский А. С.
rubric: osnovnye-stati
page_first: 20
page_last: 22
page_labels: 18, 20
tag: H4M0
lang: vi
source: kvant_digital
extraction: vision
content_sha256: abc53fe87ba1f64ffc094c9b65007f188bec071096a2bfe0ef727583836a45a7
prompt_sha256: draft-1
translated_from: content/ru/1972/11/articles/06_varpahovskiy-mashina-uchitsya-raspoznavat-0d0a7746.md
source_content_sha256: 31b20b3684b09a125ba15fa773479c8f2f9abef7e5633f9abce7c7f8b4d9595b
translation_model: draft
translation_run: vi-draft-2026-10-31
translation_quality: draft
---

⟦folio 18⟧

Như bạn, rất indo, đã biết, đối với lời giải bất kỳ bài toán nào trên máy tính điện tử (máy tính), máy cần “thông báo” dữ liệu ban đầu lời giải và chương trình hành động cần thực hiện trên dữ liệu này *). Sau khi nhận được thông tin như vậy, máy tính sẽ thực hiện các hành động được đề xuất trên dữ liệu (“suy nghĩ”) và kết quả là nhận được lời giải mong muốn.

Máy tính ngày nay đã học cách “suy nghĩ” rất tốt, nhưng vẫn cực kỳ chậm trong việc tiếp nhận (“đọc”) những thông tin sơ bộ cần thiết: chúng giống như một học sinh lớp một học giỏi số học nhưng lại kém xa về đọc.

Mỗi máy tính đều được xây dựng từ một số lượng “phần tử” nhất định (rất lớn!) Có thể ở hai trạng thái khác nhau; Để rõ ràng, bạn có thể tưởng tượng từng phần tử như một bóng đèn, được tắt (trạng thái 0) hoặc bật (trạng thái 1). Vì vậy, mọi thứ được truyền tới máy trước tiên phải được “dịch” sang ngôn ngữ của số không và số một. Bất kỳ thông tin nào - có thể là tập hợp số, hệ thống điều khiển hoặc thế cờ - đều được “ghi” vào máy dưới dạng chuỗi số 0 và số 1 phù hợp. Để lưu trữ và ghi lại những thông tin cần thiết, trước tiên máy tính phải chuyên dùng một thiết bị - bộ nhớ. Bộ nhớ máy tính là một tập hợp các ô bao gồm một số phần tử nhất định, mỗi ô (ví dụ: sáu). Trong bất kỳ ô nào, bạn có thể viết bất kỳ chuỗi số 0 và số 1 nào (số lượng các chuỗi khác nhau như vậy là 2⁶=64).

Ví dụ: giả sử máy cần “nói” số 19. Để làm điều này, trước tiên số 19 được gán một mã nhất định dưới dạng một chuỗi các số 0 và số 1: 010011 *). Sau đó, mã này được áp dụng cho một loại băng đặc biệt (băng đục lỗ): các lỗ được đục lỗ vào đúng vị trí trên băng này. Cuối cùng, băng được đưa vào một máy, theo các lỗ trên băng, máy sẽ chuyển đổi các phần tử của ô được phân bổ để ghi một số nhất định sang trạng thái cần thiết. Quá trình này được mô tả sơ đồ trong Hình 1.

Có thể dễ dàng tưởng tượng để sản xuất ra một cuộn băng cần bao nhiêu thời gian, quy trình này tốn nhiều công sức như thế nào khi máy cần truyền nhiều dữ liệu hơn. Làm cách nào chúng ta có thể đơn giản hóa và tự động hóa việc truyền dữ liệu đến máy? Không thể cung cấp cho máy thông tin cần thiết ở dạng chung (chẳng hạn như ở dạng văn bản được hướng dẫn), để lại mã hóa cho chính máy? Về nguyên tắc, tất nhiên là có thể. Nhưng đối với điều này

*) Ví dụ, hãy xem các bài viết của R. S. Guter “Máy móc có thể làm gì” («Kvant» Số 5, 1970) và “Ngôn ngữ con người và ngôn ngữ của máy móc” («Kvant» Số 10, 1971).

⟦folio 20⟧

Hình 3.

trong 10 ô nhớ liên tiếp, như trong Hình 3.

Tất cả các giai đoạn khác đều được nhập vào bộ nhớ của máy theo cách tương tự. Trong quá trình đọc, mỗi chữ cái được đọc đều được kiểm tra trình tự ở tất cả các giai đoạn. Khi kiểm tra ở giai đoạn tiếp theo, máy so sánh nội dung của từng ô (có màu hoặc không có màu của ô này) với trạng thái của phần tử tương ứng của ô nhớ và đếm tổng số “khác biệt”. Sau khi so sánh tất cả các công đoạn, máy chọn công đoạn có số chênh lệch nhỏ nhất; mã của chữ cái đã chọn sẽ được chuyển sang ô nhớ tiếp theo và máy sẽ tiến hành đọc chữ cái tiếp theo.

Việc đọc cơ học phông chữ được xác định trước này khá đáng tin cậy, mặc dù không thể loại trừ sai sót ngay cả trong trường hợp này. Chẳng hạn, không khó để tưởng tượng rằng chữ “C” có thể, do nhiều bất thường khác nhau, hóa ra “gần” với giai đoạn của chữ “o” hơn là giai đoạn của chính nó. Những khó khăn khác liên quan đến việc nhập chữ in hoa và dấu chấm câu (dấu chấm, dấu phẩy, v.v.).

Sự bất tiện chính của hệ thống đọc này là tính không linh hoạt của nó: nếu bạn thay đổi phông chữ một chút, cách đọc sẽ không còn chính xác nữa. Điều này xảy ra bởi vì với phương pháp đọc này, máy tính phân biệt các chữ cái không phải bằng những đặc điểm đặc trưng về hình dạng của chúng mà bằng cách viết cụ thể của chúng. Chữ “O” từ một phông chữ khác có thể khác biệt đáng kể so với giai đoạn một về sự tương ứng giữa các phần của nó: hẹp hơn, có đường cong lớn hơn, v.v. Số lượng khác biệt (khi so sánh với chữ cái bước “O”) khi đó trở nên rất lớn và máy có thể “nhầm lẫn” chữ “O” với một số chữ cái khác. Do đó, khi chuyển sang phông chữ khác, máy phải đưa ra các giai đoạn mới, buộc máy phải “học” lại bảng chữ cái mỗi lần.

Tất nhiên, điều mong muốn là buộc máy phải nhận dạng chính xác các chữ cái chỉ bằng cấu trúc, cấu trúc của chúng - sao cho ngay cả những khác biệt đáng kể về sự tương ứng của các phần của chữ cái cũng không ảnh hưởng đến kết quả đọc. Tuy nhiên, ở đây có những khó khăn chính, đặc biệt được thể hiện rõ ràng khi đọc văn bản viết tay. Ví dụ, ngay cả cùng một người cũng viết chữ “a” khác nhau trong những trường hợp khác nhau, chưa kể những trường hợp khác nhau. Và nếu một người, khi chia nhỏ bất kỳ văn bản nào, sử dụng đến sự trợ giúp của nhiều kết nối ngữ nghĩa, logic và ngữ pháp, thì nói chung, cỗ máy hỗ trợ đó chỉ dựa vào “tầm nhìn” của nó một cách không cần thiết và đúng đắn.

Để tưởng tượng những vấn đề nảy sinh ở đây và cách người ta có thể tiếp cận chúng lời giải, chúng ta hãy xem một ví dụ đơn giản về văn bản viết tay được viết bằng mã Morse. Trong trường hợp này luôn có hai ký tự: “dấu chấm” và “dấu gạch ngang” (không tính các loại khoảng cách có độ dài khác nhau giữa các ký tự và nhóm ký tự). Khó khăn chính là một số “dấu chấm” trong một “Morzis” có thể dài hơn các “dấu gạch ngang” không có bát phân trong một “dấu gạch ngang” khác. Vì lý do này, trước tiên không thể tạo ra một biểu diễn chính xác bằng máy: tất cả các dấu hiệu có độ dài nhỏ hơn một số l nhất định phải được coi là dấu chấm, tất cả các dấu hiệu khác - dấu gạch ngang. Tuy nhiên, có thể làm cho nó dựa trên một văn bản đủ dài của một mã Morse, máy sẽ tự xác định số ranh giới l như vậy. Xét cho cùng, mọi Morse đều có độ dài bằng tất cả
