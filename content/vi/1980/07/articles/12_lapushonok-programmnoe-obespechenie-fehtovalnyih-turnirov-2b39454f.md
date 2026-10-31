---
id: 1980-7-lapushonok-programmnoe-obespechenie-fehtovalnyih-turnirov-2b39454f
issue: kvant_1980_7
year: 1980
number: "7"
title: Phần mềm giải đấu đấu kiếm
authors:
  - Лапушонок И.
rubric: raznoe
rubric_sub: Разное
page_first: 38
page_last: 39
page_labels: 36-37
tag: 1XOT
lang: vi
source: kvant_digital
extraction: vision
content_sha256: be32921078a4dd7152d277864712576dff91ed4218f6c3b5b3573f387ea11117
prompt_sha256: draft-1
translated_from: content/ru/1980/07/articles/12_lapushonok-programmnoe-obespechenie-fehtovalnyih-turnirov-2b39454f.md
source_content_sha256: 69373ecc3c5d9120ffc799811371ed649756ab23143da07b03cf566c2d365270
translation_model: draft
translation_run: vi-draft-2026-10-31
translation_quality: draft
---

⟦folio 36⟧

I. Lapushonok

Phần mềm tham quan đấu kiếm

Trong đấu kiếm hiện đại, tất cả những người tham gia được chia thành các nhóm ban đầu (đạn), trong đó họ chiến đấu với nhau theo thứ tự đã thiết lập. Trong một viên đạn có thể có từ năm đến mười người, và điều mong muốn là tất cả các viên đạn đều có số lượng vận động viên bằng nhau. Vị trí của người tham gia nhóm được xác định bởi số trận thắng và trong trường hợp số trận thắng bằng nhau - theo hệ số $k$:

$$k = \frac{\text{нанесенные уколи}}{ \text{полученные уколи}}$$

Việc xác định số lượng người tham gia cá nhân từ mỗi nhóm (thường là 3 hoặc 4) sẽ chuyển sang giai đoạn tiếp theo. Ở giai đoạn tiếp theo, những người tham gia lại được chia thành các viên đạn (nếu có hơn mười người tham gia) và chiến đấu lại. Khi chặng tiếp theo có ít hơn 10 người, chặng đó được tuyên bố là tài chính và người chiến thắng ở chặng đó được tuyên bố là người chiến thắng giải đấu.

Phần mềm đấu kiếm tiên tiến bao gồm các quy trình sau:

- tính toán các biến thể có thể có của đạn (PULLKA);
— nhập tên của những người tham gia và ghi lại họ vào tập hợp (NGƯỜI THAM GIA);
— phân bổ tên của người tham gia theo nhóm (NHÓM);
- xác định thứ tự các trận đánh cho từng viên đạn và ghi lại kết quả của các trận chiến này trong đoàn xe (SCOUNT);
— đếm số chiến thắng của mỗi người tham gia và cuối cùng là vị trí trong nhóm (ĐIỂM);
— ban hành một giao thức bản tin (PROTOCOL);

- ghi lại những người tham gia giai đoạn tiếp theo trong tập hợp (STEP);
— quy trình kiểm soát KIỂM SOÁT bằng quy trình GIÁN ĐOẠN (đánh lại).

Hệ thống tương tác. Ban đầu nó được viết bằng BASIC. Chúng tôi đề nghị người đọc lặp lại các chương trình này trên Rapier.

Việc kiểm soát tiến độ và việc đưa các quy trình theo trình tự yêu cầu được thực hiện bằng quy trình QUẢN LÝ.

BÁN CHÍNH THỨC Chương trình này có thể được mô tả như thế này:

QUẢN LÝ QUY TRÌNH;
. NGƯỜI THAM GIA;
1—> KÝ;
KHI ĐĂNG NHẬP > = 0::
.BULLET; .NHÓM;
DÀNH CHO TẤT CẢ CÁC NHÓM::
.KIỂM TRA; .ĐIỂM; GIAO THỨC
TẤT CẢ;
NẾU SỐ LƯỢNG NGƯỜI THAM GIA <10
SAU ĐÓ KÝ —1—> KÝ
NẾU KHÁC .STAGE
TẤT CẢ
TẤT CẢ;
KIỂM TRA NHU CẦU
THỦ TỤC GIÁN ĐOẠN CUỘC GỌI
KSC;

Ở đây chỉ có hai nơi không trang trọng (theo quan điểm của Rapier). Chúng được in nghiêng. Đầu tiên, đây là dòng FOR ALL GROUPS::

nghĩa là việc thực hiện bắt buộc, lặp đi lặp lại cả ba thủ tục ĐẾM, ĐIỂM và GIAO THỨC tiếp theo cho tất cả các viên đạn cùng cấp; bài toán của bạn là thực hiện đơn thuốc không chính thức này bằng cách sử dụng các phương tiện Rapier mà bạn biết.

Thứ hai là dòng KIỂM TRA SỰ CẦN GỌI GIÁN ĐOẠN THỦ TỤC

Sẽ không khó để bạn mở rộng sang mô tả có định dạng về các điều kiện của toán tử IF, có tính đến thủ tục GIÁN ĐOẠN bắt đầu hoạt động nếu 2-4 người tham gia (bất kỳ cặp nào trong số họ, ba hoặc thậm chí bốn) có số trận thắng bằng nhau và tỷ lệ cược bằng nhau.

Ngoài ra, trong phần mô tả quy trình KIỂM SOÁT có vẻ cần phải cụ thể. SỐ LƯỢNG THAM GIA được chuyển nhượng được ban giám khảo nhập vào đầu chương trình (trong thủ tục NGƯỜI THAM GIA) và chỉ được thay đổi (giảm) trong quá trình ĐẾM. SIGN được chuyển dùng để sửa dấu đầu dòng gia đình.

Thủ tục NGƯỜI THAM GIA được sử dụng để ban đầu nhập và điền tên của những người tham gia. Chúng được nhập từ thiết bị đầu cuối theo thứ tự được thiết lập bằng cách rút thăm (đối với người lập trình

⟦folio 37⟧

điều quan trọng là thứ tự trong danh sách những người tham gia phải được biết chính xác vào thời điểm nó được nhập vào bộ nhớ). Quy trình NHÓM chọn thành phần của viên đạn từ những người tham gia được ghi lại. Ví dụ: dấu đầu tiên sẽ bao gồm những người tham gia có họ đã được nhập, chẳng hạn như các số 1, 7, 13, 19, 25, 31, 37. Trước khi dấu đầu dòng bắt đầu, một bản in sẽ được đưa ra - số và họ của những người tham gia. Ví dụ:

Viên đạn 1
Số 1 IVANOV D.
Số 2 VOLKOV I.
Số 3 KUZNETSOV M.
Số 4 LEBEDEV A.
Số 5 LVIV V.

Nibolie quan tâm đến các thủ tục KÉO, ĐIỂM và ĐIỂM, vì chúng phản ánh đặc thù của các giải đấu đấu kiếm. POOL hiển thị các tùy chọn có thể có để chia người tham gia thành các dấu đầu dòng. Một ví dụ về máy đưa ra quy trình này:

CÓ NHIỀU NGƯỜI THAM GIA GIẢI ĐẤU?
— 43
6 NGƯỜI TRONG MỖI 6 NHÓM VÀ 7 NGƯỜI TRONG MỖI 1 NHÓM.
7 NGƯỜI TRONG MỖI 5 NHÓM VÀ 8 NGƯỜI TRONG MỖI 1 NHÓM.
5 NGƯỜI TRONG MỖI 5 NHÓM VÀ 6 NGƯỜI TRONG MỖI 3 NHÓM.

Ở đây thẩm phán chỉ nhập một số - 43.

SCORE hiển thị bảng thứ tự trận đấu cho từng viên đạn. Ngoài ra, thủ tục này còn trực tiếp quy định việc bắt đầu trận chiến, triệu tập những người tham gia lên đường, thông báo trận chiến tiếp theo, nhận kết quả và ghi vào đoàn xe. Bộ dữ liệu tương tự cũng sử dụng ĐIỂM trong quy trình để tính toán số trận thắng, tỷ lệ cược và vị trí.

Dưới đây là bản in bảng các trận đấu và diễn biến của giải đấu cùng với bản ghi kết quả và trong quá trình đó là ĐIỂM, tính toán số trận thắng, tỷ lệ cược và vị trí.

Dưới đây là bản in bảng các trận đấu và diễn biến của giải đấu cùng với bản ghi kết quả và trong quá trình đó là ĐIỂM, tính toán số trận thắng, tỷ lệ cược và vị trí.

THỨ TỰ CHIẾN ĐẤU CHO 5 NGƯỜI THAM GIA 1-2, 3-4, 5-1, 2-3, 5-4, 1-3, 2-5, 4-1, 3-5, 4-2,*)
ĐỐI VỚI TÀU 1-2 SẴN SÀNG 3-4
KẾT QUẢ?
— 3,5
ĐỐI VỚI TÀU 3—4 SẴN SÀNG 5—1
KẾT QUẢ?
— 5,0
...**)
CẶP CUỐI CÙNG 4-2
KẾT QUẢ?
— 5,3

Giao thức được soạn thảo dựa trên kết quả của dấu đầu dòng này được hiển thị trong bảng.

Người tham gia Số 1 2 3 4 5 P NU PU M
Ivanov D. 1 * 3 5 2 0 1 10 19 5
Volkov I. 2 5 * 5 3 1 2 14 21 3
Kuznetsov M. 3 4 3 * 5 1 1 13 15 4
Lebedev A. 4 5 5 0 * 3 2 13 15 2
Lvov V. 5 5 5 5 * 4 20 5 1

P - số trận thắng
NU - số lần tiêm đã tiêm
PU - số lượng mũi tiêm nhận được
M - địa điểm

*) Thực ra máy tính in các số này thành một cột không có dấu phẩy.
**) Ở đây, tương tự, máy tính in kết quả trận đấu của bảy cặp nữa.
