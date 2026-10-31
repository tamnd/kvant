---
id: 1989-12-kiryuhin-i-mezhdunarodnaya-olimpiada-po-informatike-7cd3837c
issue: kvant_1989_12
year: 1989
number: "12"
title: I Olympic tin học quốc tế
authors:
  - Кирюхин В. М.
rubric: olimpiady
rubric_sub: Олимпиады
page_first: 66
page_last: 67
page_labels: 64-65
tag: CHJV
lang: vi
source: kvant_digital
extraction: vision
content_sha256: fab7772ea8fe343f82c6c34bed8fb0d5b07d20fc7ecb12b8c16d102f3eb6b202
prompt_sha256: draft-1
translated_from: content/ru/1989/12/articles/16_kiryuhin-i-mezhdunarodnaya-olimpiada-po-informatike-7cd3837c.md
source_content_sha256: c5d45dbc59ffb2ca15f87664978e7cf8b6f519ad72157c7209719d94fd43cf33
translation_model: draft
translation_run: vi-draft-2026-10-31
translation_quality: draft
---

⟦folio 64⟧

I Olympic quốc tế về khoa học máy tính

Ứng viên khoa học kỹ thuật
V. M. KIRYUKHIN

Năm nay, theo lời giải UNESCO thông qua vào ngày 24 tháng 9 năm 1987, Olympic Tin học Quốc tế lần I đã diễn ra. Olympic được tổ chức từ ngày 15 đến ngày 20 tháng 5 tại Cộng hòa Nhân dân Bulgaria, tại thành phố Pravets, trùng với đại hội quốc tế lần thứ ba “Trẻ em trong thời đại thông tin”.
Mười ba quốc gia (Bulgaria, Hungary, Việt Nam, Đông Đức, Hy Lạp, Zimbabwe, Trung Quốc, Cuba, Ba Lan, Liên Xô, Đức, Tiệp Khắc và Nam Tư) đã cử học sinh có độ tuổi không quá 19 tuổi tham dự Olympic Tin học quốc tế lần thứ nhất. Theo quy định của Olympic, mỗi đội có thể bao gồm tối đa học sinh trope. Tất cả các nước, ngoại trừ Hungary và Nam Tư, đều tận dụng quyền này. Các đội đến từ Hungary và Nam Tư có hai đại diện tham gia; Hai đội đến từ Bulgaria với tư cách là nước tổ chức đã tham gia Thế vận hội. Ngoài ra, ngoài đội tuyển quốc gia Liên Xô, đội Pereslavl-Zalessky và đội của Đại sứ quán Liên Xô tại Pháp cũng nhận được lời mời tham gia Olympic.
Thành phần của đội Liên Xô được xác định dựa trên kết quả của trại huấn luyện mùa xuân diễn ra vào đầu tháng 5 tại Trung tâm Thanh niên của Ủy ban Trung ương Komsomol “Olympian” ở Khimki và Olympic Tin học toàn Liên đoàn lần thứ II. Kết quả là, đất nước chúng ta có đại diện tại Bulgaria bởi Ilya Dogolyatsky và Lev Novik, học sinh trường số 239 ở Leningrad, và Andris Chaipyatis, học sinh trường số 28 ở Kaunas. Trưởng nhóm là tác giả của bài viết này.

Thế vận hội được tổ chức trong một vòng. Tại cuộc họp, ban giám khảo quốc tế, do Giáo sư P. Kenderov (NRB) đứng đầu và cũng bao gồm lãnh đạo của tất cả các đội, đã chọn một trong sáu bài toán được chuẩn bị trước. bài toán này đã được đề xuất cho lời giải cho tất cả những người tham gia.

Bài toán TÔI CỦA TÔI
Cho một dãy gồm 2N ô. Hai cái liền kề trống và phần còn lại chứa ký hiệu N-1 A và N-1 ký hiệu B.
Ví dụ cho N=5:

A | B | B | A | A | B | TRONG

Quy tắc di chuyển: nội dung của hai ô không trống liền kề bất kỳ có thể được di chuyển sang các ô trống mà vẫn giữ nguyên thứ tự của chúng.

Mục tiêu: Sử dụng các quy tắc chuyển động, đạt được cấu hình trong đó tất cả các ký hiệu A nằm ở bên trái của tất cả các ký hiệu B. Vị trí của các ô trống sau khi di chuyển không quan trọng.

Bài tập. Viết chương trình có:
1) nhập cấu hình ban đầu từ bàn phím dưới dạng một chuỗi ký hiệu A, B và số 0 cho các ô trống, đồng thời mô phỏng các chuyển động;
2) đối với một cấu hình ban đầu nhất định, hãy xác định ít nhất một kế hoạch di chuyển có thể đạt được mục tiêu hoặc báo cáo rằng không có kế hoạch nào như vậy tồn tại (đầu ra phải chứa cấu hình ban đầu, cấu hình trung gian sau mỗi bước và cấu hình cuối cùng);
3) tìm một phương án nào đó đạt đến số nguyên với số bước tối thiểu.

Kết quả: Cung cấp ít nhất một lời giải cho ví dụ trên.

Bốn giờ được phân bổ cho lời giải bài toán. Mỗi người tham gia được cung cấp một máy tính cá nhân “Pravets-16” với các thiết bị ngoại vi thích hợp. Họ cũng được phép sử dụng máy tính cá nhân của họ trong quá trình lời giải bài toán, và nhóm của Cộng hòa Liên bang Đức và Đại sứ quán Liên Xô tại Pháp đã làm việc trên công nghệ nomykomotechnics được cung cấp cho họ.

Mỗi người tham gia Olympic có quyền, khi thực hiện một nhiệm vụ, làm việc với bất kỳ hệ thống phần mềm nào có trong phần mềm cá nhân

⟦folio 65⟧

máy tính: C, Pascal, BASIC, Logo, v.v. Vì khi chọn bài toán tối ưu, có tính đến tính độc lập của nó với kiến ​​​​trúc của một máy tính cá nhân cụ thể nên không cần sử dụng các gói phần mềm chuyên dụng.

Sau khi hoàn thành lời giải tối ưu hóa bài toán của từng cái, có tính đến tính độc lập của nó với kiến ​​​​trúc của một máy tính cá nhân cụ thể, nhu cầu sử dụng các gói phần mềm chuyên dụng và kết quả thực thi nó thu được bằng máy tính cá nhân, cũng như đĩa mềm với phiên bản mới nhất của chương trình, văn bản nguồn và kết quả kiểm tra.

Việc kiểm tra lời giải được thực hiện bởi các thành viên trong ban điều phối và trưởng nhóm. Việc tổng kết cuối cùng được thực hiện tại cuộc họp của ban giám khảo quốc tế.

Trong quá trình xác minh bài toán, các chương trình đã được thử nghiệm với sự tham gia của bốn thành viên chuyên trách của ủy ban điều phối và trưởng nhóm. Việc tổng kết cuối cùng được thực hiện tại cuộc họp của ban giám khảo quốc tế.

Việc kiểm tra lời giải được thực hiện bởi các thành viên trong ban điều phối và trưởng nhóm. Việc tổng kết cuối cùng được thực hiện tại cuộc họp của ban giám khảo quốc tế.

Trong quá trình xác minh, các chương trình bài toán đã được thử nghiệm với sự tham gia của bốn thành viên chuyên trách của ủy ban điều phối và trưởng nhóm. Việc tổng kết cuối cùng được thực hiện tại cuộc họp của ban giám khảo quốc tế.

Các chương trình tối ưu hóa chiến thắng cũng đã được thử nghiệm ở mức $N > 5$ để đánh giá thêm tính hiệu quả của thuật toán, mặc dù điều này không hoàn toàn dễ dàng đối với các thành viên ban giám khảo quốc tế.

Lời giải mỗi cái đều tính đến việc tối ưu hóa trong quá trình thực hiện các điểm riêng lẻ bài toán cho điểm tương ứng ở 10, 40 và 40 điểm. Ban giám khảo đã để lại 10 điểm theo ý của mình để khuyến khích lời giải ban đầu, lập trình kỹ thuật và thiết kế chương trình, v.v.

Khi đánh giá nhiệm vụ đầu tiên, 10 điểm bắt đầu cho việc tổ chức nhập dữ liệu chính xác và có kiểm tra tính chính xác của dữ liệu nguồn. Đối với lần thứ hai, việc tìm ra ít nhất một phương án được cho điểm 15 hoặc 20 điểm nếu tìm thấy tất cả các phương án; 20 điểm khác được thưởng khi hiển thị thông báo vắng mặt lời giải. Đối với nhiệm vụ thứ ba, 15 điểm được trao cho sự hiện diện trong chương trình với nỗ lực giảm thiểu số bước và
