---
id: 1986-1-levinshteyn-simin-elementarnyie-logicheskie-operatsii-79356fa6
issue: kvant_1986_1
year: 1986
number: "1"
title: Các phép toán logic cơ bản
authors:
  - Левинштейн М. Е.
  - Симин Г. С.
rubric: raznoe
rubric_sub: Разное
page_first: 46
page_last: 47
page_labels: 44-45
tag: 9CMH
lang: vi
source: kvant_digital
extraction: vision
content_sha256: 1852cca8d56a439cd49c285c325ee7246d64bce873dd662258303a62caf97c29
prompt_sha256: draft-1
translated_from: content/ru/1986/01/articles/16_levinshteyn-simin-elementarnyie-logicheskie-operatsii-79356fa6.md
source_content_sha256: 27329a3b25528a2101c04577e9da0e54fb60c6d263b0a475f501a00ee2da84d0
translation_model: draft
translation_run: vi-draft-2026-10-31
translation_quality: draft
---

⟦folio 44⟧

v. Các phép toán logic cơ bản

Tiến sĩ Khoa học Vật lý và Toán học M. E. LEVINSHTEIN, Ứng viên Khoa học Vật lý và Toán học G. S. SIMIN

Trong các ghi chú trước của phần này (xem «Kvant», 1985, số 9-12), chúng tôi đã xem xét cấu trúc, nguyên lý hoạt động và phương pháp chế tạo bóng bán dẫn - nền tảng của máy tính hiện đại. Để hiểu cách các hành động xử lý được thực hiện trong máy tính với sự trợ giúp của bóng bán dẫn, hôm nay chúng ta cần nói về các hoạt động logic cơ bản.

...Bạn bước vào tiền sảnh của một tòa nhà 16 tầng hiện đại. Trước mặt bạn là cửa của hai thang máy và một nút bấm duy nhất trên tường. Bạn nhấn nó và từ màn hình ánh sáng phía trên cửa, bạn sẽ thấy một trong những thang máy bắt đầu đi xuống về phía bạn như thế nào. Trên đường đi, căn nhà gỗ bị bỏ hoang - tiếng cửa đóng mở vang lên - có người bước vào thang máy. Cabina tiếp tục lái xe. Cuối cùng, cửa thang máy mở ra. Ai đó bước ra... Tất cả điều này truyền cảm hứng đến mức nó thực tế không thu hút được sự chú ý.

Bây giờ hãy tưởng tượng bạn là một kỹ sư phải thiết kế một mạch điện tử điều khiển chuyển động của thang máy. Mạch này phải giải được tập bài toán.

"Nếu các cabin không có người và chỉ nhấn một nút thì cabin gần tầng nhất định sẽ được chỉ định. Nếu có các cabin trên cùng một tầng, hãy chọn cabin tiêu thụ ít năng lượng hơn."

“Nếu có một hành khách trong cabin và anh ta nhấn nút cho một tầng nhất định, và một nút cũng được nhấn ở tầng khác, và thang máy không đi lên mà đi xuống, và thang máy thứ hai không có người, hoặc nếu cũng có một hành khách trong thang máy thứ hai…”

Hãy thử tưởng tượng toàn bộ bộ logic bài toán có thể được đặt trước một mạch điện tử 16 tầng và hai thang máy, bạn sẽ thấy rằng ngay cả một “bộ xử lý” đơn giản như vậy cũng phải có khả năng giải quyết những vấn đề rất khó khăn.

Nếu bạn cố gắng thiết kế một bộ xử lý như vậy, sớm muộn gì bạn cũng sẽ bị thuyết phục về những điều sau. Khi vẽ một mạch logic, bạn nên quên một lúc về các thuộc tính của thiết bị đóng vai trò là cơ sở cơ bản của bộ xử lý của bạn và giả sử rằng bạn có sẵn các ô logic cơ bản - các mạch cơ bản, khả năng thực hiện các chức năng logic “VÀ”, “KHÔNG”, “HOẶC”.

Chức năng của bộ xử lý cần được thiết kế càng phức tạp thì phương pháp này càng hiệu quả. Đối với một máy tính phải giải quyết bài toán phức tạp hơn hàng nghìn lần so với thiết bị điều khiển thang máy, chỉ có điều nó là hợp lý.

Tất nhiên, không thể quên hoàn toàn các thuộc tính của cơ sở dữ liệu. Sớm hay muộn, nhiều câu hỏi sẽ nảy sinh, lời giải trong số đó được xác định chính xác bởi các tham số của phần tử cụ thể đó - rơle điện từ, bóng bán dẫn, công tắc, v.v. - trên đó các mạch logic được xây dựng. Làm thế nào để so sánh nhanh các ô logic? Họ có sức mạnh gì

Những ý tưởng đầu tiên về việc tạo ra một máy tính kỹ thuật số tự động có thể lập trình đã được phát triển cách đây hơn 150 năm. Họ thuộc về Anh giáo C. Babidge, một người có khả năng phi thường, người có những ý tưởng đi trước thời đại nhiều năm. Trong 30 năm, bắt đầu từ năm 1812, Babyju đã làm việc để chế tạo một chiếc máy như vậy. “Cơ sở cơ bản” của cỗ máy của Babage là bánh xe “kỹ thuật số” với số răng khác nhau. Các bộ phận của máy Babage được lưu giữ trong bảo tàng khoa học ở London. (Bạn có thể đọc thêm về Ch. Babidge trong «Kvant», 1985, số 10 trong bài “Lịch sử ra đời của máy tính.”)

⟦folio 45⟧

Cơ sở của đại số này, hiện được gọi là “Boolean”, là bất kỳ đại lượng nào chỉ nhận hai giá trị: “có” - “không”, “0” - “1”, “bật” - “tắt”, v.v.

Mối quan hệ cơ bản và sâu sắc giữa đại số Boolean và bản chất kép của các phần tử điện quan trọng đã được thiết lập bởi nhà toán học nổi tiếng người Mỹ J. von Neumann. Ý tưởng của Neumann đã đặt nền móng cho các máy tính đồng nhất, bao gồm một số lượng lớn các phần tử mạch logic giống hệt nhau hoạt động theo nguyên tắc kép. Neumann đã chứng minh rằng bằng cách sử dụng các mạch “NOT”, “OR”, “AND”, có thể tạo ra tất cả các thành phần chính của máy tính.

Đóng góp lớn cho lý thuyết đại số của automata là của nhà toán học nổi tiếng Liên Xô V. M. Glishkov. Ông đã thu được những kết quả quan trọng trong lý thuyết về máy tự động số, trong lĩnh vực ứng dụng công nghệ máy tính và trong việc phát triển các phương pháp mới để chế tạo máy tính nhỏ.

Các phép toán đại số Boolean

Phép cộng logic
$$C = A + B \quad (A \text{ и } B)$$

Phép nhân logic
$$C = A \cdot B \quad (A \text{ и } B)$$

Phủ định logic
$$B = \bar{A} \quad (\text{не } A)$$

Mạch logic tương ứng

A+B
mạch "HOẶC"

A B
Sơ đồ “Tôi”

MỘT
MỘT
kế hoạch "KHÔNG"

Bảng các phép toán logic.

tiêu thụ? Một mạch logic có giá bao nhiêu? Nó được bảo vệ khỏi nhiễu đáng tin cậy đến mức nào? Vân vân.

Nhưng trong khi thiết kế logic của quy trình, bạn không cần phải suy nghĩ về tất cả những vấn đề này. Mạch logic được xây dựng bằng cách sử dụng các ô logic như “AND”, “OR”, “NOT” là mạch phổ biến; nó không phụ thuộc vào phần tử nào mà các ô logic được triển khai.

Các ô logic là gì?

Đây là các mạch điện tử, ở đầu vào và đầu ra mà hướng chỉ có thể nhận hai giá trị được xác định đầy đủ. Một trong những giá trị này được gọi là số 0 logic, giá trị thứ hai được gọi là giá trị logic. Hai giá trị hướng này lần lượt biểu thị là $U^0$ và $U'$ (“0” và “1”).

Các ô logic OR (mạch cộng logic) có hai hoặc nhiều đầu vào và một đầu ra. Nếu ít nhất một trong các đầu vào nhận được tín hiệu “1”, thì “1” cũng xuất hiện ở đầu ra. Ký hiệu mạch OR được hiển thị ở hàng đầu tiên của bảng phép toán logic. Đầu vào của mạch được ký hiệu bằng các chữ cái $A$ và $B$. Tín hiệu đầu ra được chỉ định $(A + B)$.

Các ô logic AND (mạch nhân logic) cũng có một đầu ra và hai hoặc nhiều đầu vào. Tín hiệu “1” xuất hiện ở đầu ra ô khi và chỉ khi tín hiệu “1” cũng hoạt động ở tất cả các đầu vào ô. Nếu ít nhất một trong các đầu vào có tín hiệu “0” thì tín hiệu “0” được đặt thành đầu ra.

Các ô logic NOT (còn gọi là bộ biến tần hoặc mạch phủ định logic) có một đầu vào và một đầu ra. Nếu tín hiệu “1” được cấp cho đầu vào, thì “0” sẽ xuất hiện ở đầu ra và ngược lại, nếu tín hiệu “0” được cấp cho đầu vào thì đầu ra được đặt thành “1”.

Các phép toán logic cộng, nhân và phủ định tuân theo các quy tắc nhất định được thiết lập bởi cái gọi là đại số logic hoặc đại số Boolean.

Bằng cách chỉ thao tác các phép toán logic “VÀ”, “HOẶC”, “KHÔNG” (đôi khi ở những tổ hợp rất phức tạp), hóa ra có thể thực hiện bất kỳ hành động nào cho phép máy tính chấp nhận lời giải, quản lý, xử lý thông tin, v.v.

Chúng ta sẽ xem xét các ví dụ về các mạch logic đơn giản nhất được xây dựng trên bóng bán dẫn trong bài viết tiếp theo trong phần của chúng tôi.
