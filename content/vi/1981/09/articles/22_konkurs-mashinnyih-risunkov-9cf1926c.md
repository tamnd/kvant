---
id: 1981-9-konkurs-mashinnyih-risunkov-9cf1926c
issue: kvant_1981_9
year: 1981
number: "9"
title: Cuộc thi vẽ máy
rubric: raznoe
rubric_sub: Разное
page_first: 57
page_last: 58
page_labels: 55-56
tag: Z9WV
lang: vi
source: kvant_digital
extraction: vision
content_sha256: 1277b2361a810ddb2be3be8ab5f1faf627efadff8ff2dbb73de77fe7c16622f7
prompt_sha256: draft-1
translated_from: content/ru/1981/09/articles/22_konkurs-mashinnyih-risunkov-9cf1926c.md
source_content_sha256: a1a4fb42f6c498aa53c2aa4805b97f0536bca719ef4068b7bb818d1637250e0b
translation_model: draft
translation_run: vi-draft-2026-10-31
translation_quality: draft
---

⟦folio 55⟧

Dữ liệu - bộ*). Ngôn ngữ Pascal đã được chọn để nghiên cứu sơ bộ các vấn đề sau «Kvant».

Người đọc có thể làm quen kỹ hơn với các ngôn ngữ được thảo luận trong bài viết này trong tài liệu sau: Pervin Yu. A. “Các nguyên tắc cơ bản của Fortran” (M., “Nauka”, 1973).
Lavrov S. S. “Ngôn ngữ lập trình phổ quát (Algol-60)” (M., “Nauka”, 1972).

*) Thanh kiếm, dần trở nên có trách nhiệm, đã tận dụng tính mới này - xem «Kvant», 1980, số 3, ZShP, bài 8.

Cuộc thi
máy móc
bản vẽ

Các biên tập viên của tạp chí «Kvant» và Trung tâm Máy tính Chi nhánh Siberia của Viện Hàn lâm Khoa học Liên Xô đang công bố một cuộc thi dành cho bức vẽ đẹp nhất được thực hiện trên máy tính sử dụng hệ thống đồ họa máy tính.

Học sinh, sinh viên các trường dạy nghề có thể tham gia cuộc thi.

Các bản vẽ, đồ trang trí, nhóm đường cong toán học, hình ảnh bề mặt, v.v. thực tế hoặc cách điệu có thể được gửi tham gia cuộc thi. Các bức vẽ phải là bản gốc (sự lặp lại của các bức vẽ được xuất bản trên tạp chí của chúng tôi không được chấp nhận cho cuộc thi) và sở thích toán học phải được kết hợp với giá trị tự nhiên trong đồ trang trí và hoa văn.

Bản vẽ phải kèm theo bản in đầy đủ của chương trình, bình luận chi tiết về nó, giải thích ý tưởng toán học và thứ tự hoạt động của chương trình, thông tin chi tiết về tác giả (tác giả) - họ, tên, họ hàng, số trường và lớp, địa chỉ nhà đầy đủ.

Những học sinh không có quyền truy cập độc lập vào máy tính có không gian đồ thị có thể gửi các chương trình xây dựng bản vẽ kèm theo một đoạn trích gần đúng. Các chương trình có thể được thực thi trong Rapier, Pascal hoặc Algol bằng hệ thống Spar (xem «Kvant», 1980, Số 1, trang 56) hoặc trong Fortran bằng hệ thống đồ họa được mô tả bên dưới. Âm lượng của chương trình không quá 100 toán tử, kích thước hình ảnh không nhỏ hơn 100×100 mm và không quá 300×300 mm.

Kiểm tra kỹ chương trình theo cách thủ công trước khi gửi dự thi: các lỗi trong bài dự thi sẽ không được sửa.

Tất cả các phần của cuộc thi (bao gồm cả sinh viên của Trường Lập trình Phóng viên và phim của trường) phải gửi tác phẩm của mình chậm nhất là ngày 15 tháng 11 năm 1981 tại địa chỉ: 630090, Novosibirsk, 90, Trung tâm Máy tính Chi nhánh Siberia của Viện Hàn lâm Khoa học Liên Xô, Nhóm Thông tin Trường học, để tham gia cuộc thi.

Chúng tôi chúc bạn may mắn! Chúng tôi đang chờ đợi bản vẽ và chương trình!

Dành cho người mới bắt đầu ở Fortran
Để truy cập hệ thống đồ họa từ chương trình Fortran, bạn phải tuân theo các quy tắc sau:

1. Khi bắt đầu chương trình phải có câu lệnh CALL SBROS khởi đầu và trước khi hoàn thành logic của nó phải có câu lệnh CALL STR.

2. Đối với chuyển động thẳng của bút đến các điểm xác định, toán tử CALL LINX(X,Y) được sử dụng, trong đó X,Y là tọa độ của điểm tính bằng mm; nếu tắt bút, một nét vẽ lạnh sẽ được thực hiện; nếu nó bị tắt, một đoạn sẽ được rút ra. Bạn có thể bật và tắt bút vào đúng thời điểm bằng cách sử dụng toán tử CALL PERO và CALL VP.

3. Để vẽ các đoạn “có đầu tự do”, bạn cũng có thể gọi mô-đun GỌI OTREZ (XN, YN, XK, YK),

⟦folio 56⟧

trong đó các tham số là tọa độ điểm đầu và điểm cuối của đoạn; Mô hình này tự bật bút ở điểm bắt đầu của đoạn và bật bút sau khi vẽ.

4. Có thể vẽ toàn bộ một vòng tròn bằng toán tử CALL OKR (XC, YC, R), trong đó XC, YC là tọa độ tâm, R là bán kính và bút cũng được bật và bật tự động. Có thể rút ra một người bạn bằng cách viết dòng GỌI OKRI (XC, YC, R, ALF, DALF); ở đây ALF là góc ở tâm ban đầu, DALF là đỉnh góc của cung có dấu xác định hướng đi ngang. Tất nhiên, kích thước góc được tính bằng độ, mặc dù độ không được đo. Sau khi vẽ một vòng cung, bút không bật lên; nếu cần, nó có thể được kích hoạt bởi nhà điều hành CALL VP; bút tự động bật khi bắt đầu vòng cung; nếu nó được bật trước khi truy cập mô-đun này, một đoạn bổ sung sẽ được vẽ từ điểm được xử lý đến đầu cung.

5. Để tạo một bản vẽ có hai màu trở lên hoặc nhiều độ dày đường kẻ, hãy sử dụng toán tử CALL NPERA (N), trong đó N có thể lấy các giá trị 0,1,2,3. Toán tử này không tự bật bút mà chỉ ghi nhớ nên sử dụng bút nào tiếp theo. Ngòi chính được coi là ngòi số 0; nó thực thi bản vẽ nếu toán tử thay đổi bút không có trong chương trình.

Đã có một số chương trình con đã bị loại bỏ cho phép bạn vẽ nhiều hình ảnh khác nhau; các phép tính cần thiết, hành động logic, một hoặc hai chương trình con có thể được tự chuẩn bị bằng Fortran. Các đường cong biểu thị một chuỗi các đoạn nhỏ; Mô hình LINX có thể hoạt động theo vòng lặp.

Nói chung, chương trình không được dài hơn 60-100 câu lệnh, nó phải bao gồm ngoại hình - loại bút nào nên được cài đặt, kích thước dự kiến ​​của bản vẽ, vị trí ban đầu của bút (nhưng tương ứng với điểm gốc của hệ tọa độ).

Ví dụ: đây là chương trình vẽ đơn giản (tất nhiên, bản vẽ như vậy không phù hợp cho một cuộc thi):

DIMENSION X (1Ø), Y (1Ø)
CALL SBROS
DO 1 K=1,9
CALL LINX (X (K), Y (K))
CALL PERO
CALL VP
DATA X/2Ø., 1Ø., 1Ø., 5Ø., 5Ø., 4Ø., 2Ø., 3Ø., 3Ø./, Y/36., 26, 8., 26., 36., 36., 26., 8./
CALL OTREZ (3Ø., 26, 5Ø., 26.)
CALL NPERA (1)
CALL OKR (2Ø., 26., 5.)
CALL LINX (15., 8.)
CALL PERO
CALL OKR 1(2Ø., 7., 5., 18Ø., —18Ø.)
CALL LINX (25., 8.)
CALL VP
CALL STP
END

Hơn thế nữa. Đối với máy dòng EC, số 0 phải được gạch bỏ.
