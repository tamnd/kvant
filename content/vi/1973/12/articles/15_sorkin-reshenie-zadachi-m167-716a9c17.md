---
id: 1973-12-sorkin-reshenie-zadachi-m167-716a9c17
issue: kvant_1973_12
year: 1973
number: "12"
title: '[Lời giải bài toán M167]'
authors:
  - Соркин Ю. И.
rubric: smes
page_first: 50
page_last: 50
page_labels: "48"
tag: RUAT
lang: vi
source: kvant_digital
extraction: vision
content_sha256: 053d566d67488c8f8d7edaf527a147c19abf041f835f4229fa4294954cf2635f
prompt_sha256: draft-1
translated_from: content/ru/1973/12/articles/15_sorkin-reshenie-zadachi-m167-716a9c17.md
source_content_sha256: 578a39ba0d29516add9a34bff65197bd70cb95b5a834311fd0e0b6536942496c
translation_model: draft
translation_run: vi-draft-2026-10-31
translation_quality: draft
---

⟦folio 48⟧

cách hiển thị đầu vào và đầu ra của từng phần tử trên bảng mặt trước dưới dạng ổ cắm.

Chúng được kết nối với nhau bằng dây có nắp.

Đây là một ví dụ về kebol bài toán, có thể giải bằng đa giác.

Bài toán. Để thực hiện hệ thống nâng tạ, người ta đã lên kế hoạch làm một biểu ngữ có dòng chữ “TRỌNG LƯỢNG ĐƯỢC ĐÚNG ĐÚNG”. Dòng chữ này phải được treo nếu các giám khảo A (ông là thẩm phán cấp cao), B và C đưa ra kết luận rằng trọng lượng đã được lấy một cách chính xác. Họ báo cáo lời giải của mình bằng cách nhấn một nút (bằng cách này, họ gửi cảnh “1” đến máy điều khiển ánh sáng của chất truyền). Việc chuyển tải phải được hoàn thành trong hai trường hợp nữa, đó là nếu hai giám khảo (một trong số họ nhất thiết phải là cấp trên) đồng ý rằng trọng lượng được lấy chính xác. Bất kỳ sự phân phối ý kiến ​​nào khác của thẩm phán đều không được khiến người phạm tội bị đình chỉ.

Rõ ràng là máy phải có ba đầu vào sẽ nhận tín hiệu từ ban giám khảo và một đầu ra sẽ tạo ra tín hiệu để bật bộ phát đáp.

Thật dễ dàng để có được cấu trúc công thức của máy tự động:

$$X = ABC + \bar{ABC} + AB\bar{C}$$

(1)

Thật vậy, bộ phát đáp phải được bật nếu cả ba hoặc hai người trong số họ (và nhất thiết phải là một trong những người kép - người cao cấp) gửi tín hiệu “1”.

Hãy sử dụng thông tin từ bài viết của L.L. Tsinman mà chúng tôi đã đề cập và biến đổi công thức (1):

$$X = ABC + \bar{ABC} + AB\bar{C} = AB + AC = A(B + C).$$

Sử dụng công thức này, bạn nên xây dựng sơ đồ chức năng của máy. Bạn sẽ nhận được sơ đồ như trong Hình 3.

Hãy đảm bảo điều này bằng cách xem xét tất cả các lựa chọn của lời giải giám khảo. Tuy nhiên, một trong các tùy chọn được hiển thị trong Hình 4.

Hãy đưa ra một số bài toán cho việc thiết kế mạch tại “Địa điểm kiểm tra cấu trúc logic”.

1. Sơ đồ của máy “Trọng tài thể thao” được thiết kế ở trên sẽ thay đổi như thế nào nếu tấm biểu ngữ “cân đúng” phải được treo với sự đồng ý của hai trong số ba trọng tài làm việc?

2. Vẽ sơ đồ chức năng từ các phần tử logic được mô tả “VÀ”, “HOẶC”, “KHÔNG” của máy tự động có thể thêm bất kỳ hai số kép có một chữ số nào (máy tự động như vậy được gọi là máy tự động lấy vật chất).

3. Vẽ sơ đồ chức năng của phép nhân hai số có hai chữ số.

4. Vẽ sơ đồ chức năng để bạn có thể theo dõi tính hợp lệ của các giá trị trong logic toán học của các công thức của A. de Moggan:

$$\overline{A} + B = \bar{A}\bar{B},$$
$$\bar{AB} = \bar{A} + \bar{B}.$$

Độc giả của chúng tôi, học sinh lớp 8 Yura Sorkin, đã gửi cho chúng tôi một lời giải bài toán (xem «Kvant» Số 6, 1973)

Dễ dàng thấy rằng có vô số số

$$a(1+d)^m$$

(*)

tại $m = 1, 2, 3, ...$ có cùng thừa số nguyên tố trong khai triển của từng số đó, và cũng rõ ràng (sử dụng máy đo sinh học của Newton) rằng tất cả các số (*) đều là số hạng của một cấp số cộng cho trước với số hạng đầu tiên $a$ và hiệu $d$.
