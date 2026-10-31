---
id: 1986-9-kovalenko-mikroprotsessor-izmeryaet-800e3b4b
issue: kvant_1986_9
year: 1986
number: "9"
title: Bộ vi xử lý đo...
authors:
  - Коваленко М. Д.
rubric: raznoe
page_first: 23
page_last: 24
page_labels: "22"
tag: HZYQ
lang: vi
source: kvant_digital
extraction: vision
content_sha256: 254d0f97f3b3d5dae9787614837dbc175882a6838ad284749603d970d86ef707
prompt_sha256: draft-1
translated_from: content/ru/1986/09/articles/07_kovalenko-mikroprotsessor-izmeryaet-800e3b4b.md
source_content_sha256: 5eb2c2bcd29b5ca2f6979e08257debaf53ebfe96a8cb7e500346137b01df07dc
translation_model: draft
translation_run: vi-draft-2026-10-31
translation_quality: draft
---

⟦folio none⟧

Bộ vi xử lý đo...

MD KOVALENKO

Bạn có thể sử dụng thiết bị nào để đo nhiệt độ của gà đông lạnh? Tất nhiên, với một nhiệt kế! Rạch một đường trên thân thịt, nhét nhiệt kế vào, đợi một chút... Và nếu việc này cần được thực hiện nhanh chóng và không làm hỏng bài thuyết trình? Bạn hỏi, những câu hỏi này có liên quan gì đến chủ đề thống kê? Điều trực tiếp nhất mà người đọc có thể kiểm chứng là làm quen với các thiết bị nhiệt kế của thời đại vi xử lý.

Hãy bắt đầu với cảm biến nhiệt độ. Để đo nhanh, nhiệt kế được chế tạo dưới dạng một chiếc kim rỗng, có thể cắm vào thân thịt mà gần như không làm hỏng thân thịt. Một cảm biến được đặt bên trong kim rỗng - một dây kim loại, điện trở của nó nằm trong một phạm vi nhỏ nhiệt độ cấm trên dây; bạn có thể sử dụng biểu mẫu này để tính nhiệt độ. Nhanh? Không hẳn vậy, ngay cả khi anh ấy có một chiếc máy tính vi mô trong tay. Việc sử dụng bộ vi xử lý cho phép bạn tăng tốc đáng kể quá trình đo.

Sơ đồ khối đơn giản của nhiệt kế vi xử lý được hiển thị ở hình. Bộ vi xử lý (MP) là một mạch điện tử tính toán và điều khiển có vai trò cơ bản tương tự như vai trò của não trong cơ thể động vật. Về mặt cấu trúc, một MP chứa mười nghìn bóng bán dẫn là một vi mạch. MP hoạt động với các con số, do đó, tín hiệu tương tự không liên tục hoặc như người ta nói, từ cảm biến (điện áp) phải đến đầu vào MP được chuyển đổi sang dạng kỹ thuật số. Công việc này được thực hiện bởi bộ chuyển đổi tương tự sang số (ADC). Nhiệt kế vi xử lý chứa các thiết bị lưu trữ (3U) gồm hai loại: hoạt động (03U) và cố định (P3U). Ở 03U, các con số và chương trình có thể được viết và đọc thoải mái, nhưng sau khi tắt nguồn, toàn bộ nội dung của 03U sẽ bị xóa. Trong P3U, thông tin chỉ được ghi một lần nhưng được lưu trữ “mãi mãi”.

Nhiệt kế hoạt động như thế nào? Trước đây, trong quá trình hiệu chuẩn, các hệ số hằng số a và b được xác định và ghi lại trong P3U. MP hoạt động

*) Cảm biến như vậy được gọi là nhiệt kế điện trở và hiếm khi được sử dụng. Thông thường người ta sử dụng cặp nhiệt điện hoặc cảm biến bán dẫn, nhưng điều này ít ảnh hưởng đến nguyên lý đo.

⟦folio 22⟧

theo một chương trình cũng được ghi trong ROM. Chương trình là một chuỗi các lệnh bước mà MP thực hiện từng bước một với tốc độ hàng nghìn hoặc thậm chí hàng triệu bước mỗi giây. Một chương trình đo nhiệt độ có điều kiện có thể giống như thế này (do chương trình, mỗi bước trong số này thực hiện một số lệnh):

Bước 1. Gọi các số $a$ và $b$ từ ROM.

Bước 2. Nhập số từ ADC vào MP (số này là giá trị điện áp $U$).

Bước 3. Tính nhiệt độ bằng công thức $t=(U-a)/b$ (kết quả được ghi vào RAM).

Bước 4. Hiển thị số được ghi trong RAM trên màn hình kỹ thuật số.

Bước 5: Chuyển sang Bước 2. Chương trình này sẽ hiển thị giá trị nhiệt độ trên màn hình với hàng nghìn giá trị mỗi giây. Bây giờ chúng ta có thể tìm ra nhiệt độ của cái nhanh (đây là danh sách!). Trong thực tế, tần số này được giảm đi nhiều lần để dễ quan sát. (Bạn có thể thấy một hình ảnh tương tự trên màn hình cân điện tử.)

Hãy xem xét một ví dụ phức tạp hơn - một vôn kế kỹ thuật số được chế tạo bởi MP. Sơ đồ khối của nó gần giống như sơ đồ khối của nhiệt kế. Giả sử chúng ta quan tâm đến sự dao động điện áp trong mạng. Bạn cần tìm hiểu tần suất trong 1 giờ, giá trị điện áp hiệu dụng vượt quá 210-230 V. Bạn có thể giải quyết bài toán này như thế này: lấy một vôn kế kỹ thuật số thông thường có thiết bị đọc kỹ thuật số (DLC) và chạy vôn kế để đo trong khoảng thời gian 1 giây. Trong một giờ, chúng ta sẽ nhận được một cuộn băng giấy dài 3-4 m với 3600 con số và với sự kiên nhẫn, chúng ta sẽ bắt đầu đếm số trên đó nằm ngoài khoảng 210-230 V. Bạn có muốn làm loại công việc này không? Khắc nghiệt. Vì vậy, hãy làm cho MP hoạt động! Để làm điều này, hãy tạo một chương trình (như trong ví dụ đầu tiên, đây là các điều kiện của chương trình):

Bước 1. Xóa các ô bộ nhớ RAM bằng các số (địa chỉ) $N_1$ và $N_2$, tức là viết số 0 cho chúng.

Bước 2. Đo giá trị hiệu dụng của điện áp mạng $U$.

Bước 3. Nếu $U<210$ hoặc $U>230$, sau đó thêm một vào nội dung của ô bộ nhớ có địa chỉ $N_1$.

Bước 4. Nếu $210≤U≤230$, thì thêm một vào nội dung của ô bộ nhớ có địa chỉ $N_2$.

Bước 5. Đợi 1 giây.

Bước 6. Chuyển sang bước 2.

Do hoạt động của chương trình này, ô RAM có địa chỉ $N_1$ sẽ tích lũy số lượng kết quả đo vượt quá giới hạn 210-230 V và trong ô $N_2$ số lượng kết quả đo nằm trong khoảng này. Dữ liệu này có thể được hiển thị liên tục trên màn hình kỹ thuật số, do đó chỉ cần dừng chương trình 1 giờ sau khi bắt đầu và nhìn vào màn hình để biết tần suất điện áp nguồn dao động. Bạn có thể đo một chương trình và làm cho chương trình đó tự dừng sau khi hoàn thành một số phép đo được chỉ định.

“Menu” của vôn kế vi xử lý thường chứa các chương trình thập phân: xử lý thống kê kết quả đo, tìm kiếm giá trị cực đại và cực tiểu của điện áp giữa các Trái đất, phân tích công thức tín hiệu định kỳ, v.v. Các chương trình này có thể chứa hàng trăm bước, được viết bằng ROM nên không cần phải tự tạo chương trình để làm việc với thiết bị. Bạn chỉ cần làm quen với mục đích của 2-3 chục kopka.

Hai ví dụ đơn giản nhất này cho thấy việc sử dụng rất nhiều thiết bị do bộ vi xử lý tạo ra: chúng không tạo ra dữ liệu sơ cấp “thô” mà là dữ liệu đã xử lý, tức là được liệt kê trong các giá trị cuối cùng. Việc sử dụng các thiết bị như vậy sẽ giúp người dân tiết kiệm nhiều hơn sức lao động và tăng năng suất của họ. Tuy nhiên, ứng dụng hữu ích nhất của MP được thể hiện trong các hệ thống điều khiển trong đó có phản hồi, tức là sự xuất hiện của MP trên đối tượng được điều khiển. Các hệ thống như vậy bao gồm, ví dụ, robot công nghiệp. Nhưng đây là một chủ đề để phát triển đặc biệt. Trong thời gian chờ đợi, khi mua gà đông lạnh tại cửa hàng, bạn đừng quên đánh giá nhé. Nếu vấn đề nhẹ nhàng thì tất nhiên mọi thứ đều rõ ràng mà không cần MP.
