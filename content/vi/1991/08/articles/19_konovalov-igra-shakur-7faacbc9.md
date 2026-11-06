---
id: 1991-8-konovalov-igra-shakur-7faacbc9
issue: kvant_1991_8
year: 1991
number: "8"
title: trò chơi Shakur
authors:
  - Коновалов С. П.
rubric: igry-i-golovolomki
rubric_sub: Игры и головоломки
page_first: 72
page_last: 75
page_labels: 70-73
lang: vi
source: kvant_digital
extraction: vision
content_sha256: 8612e3501a1eb77a1ab9a65c95978f1953e3d29447c86d89022e4c83774ee0bc
prompt_sha256: draft-1
translated_from: content/ru/1991/08/articles/19_konovalov-igra-shakur-7faacbc9.md
source_content_sha256: 22634e047f37376cb43e1dad5010138a3a4f6b7e14bd9c42f1e7a0f943882945
translation_model: draft
translation_run: vi-draft-gaps-2026-11-06
translation_quality: draft
---

⟦folio 70⟧

---
running_head:
folio:
---

trò chơi Shakur
S. KONOVALOV

Trong một trong những số báo của trang cờ vua Quaenta, bài toán đã được đưa ra, trong đó tại một thời điểm nào đó bàn cờ sẽ lật ngược. Điều này đã thay đổi hướng di chuyển của quân tốt và do đó dẫn đến một vị trí khác. Một ý nghĩ tự nhiên về toán học nảy sinh: hãy xem xét một phiên bản của trò chơi trong đó việc biến đổi không gian cờ vua sẽ là một nước đi thực sự. Một cách triển khai ý tưởng này có thể được thực hiện trên khối Rubik - khối cờ vua Rubik, hay gọi tắt là shakur.

Trò chơi sẽ có tính chất hời hợt (theo nghĩa hình học), “bàn cờ” gồm 54 ô. Ở mỗi đỉnh của hình lập phương có ba ô, vì vậy chúng ta sẽ không thể giữ nguyên màu chung của Thứ Sáu và sẽ coi bảng là một điểm (màu trắng) và các quân cờ có màu đỏ và đen (hình 1).

Chúng ta hãy hồi sinh các quân cờ (tất cả ngoại trừ những con tốt mà chúng ta chưa gặp, vì hôm nay chúng ta sẽ xem xét loại trò chơi đơn giản nhất - chiếu tướng của vua đen đơn độc). Một quân (vua, hậu, xe, giám mục hoặc hiệp sĩ) có thể di chuyển từ ô A đến ô B nếu trong một số diễn biến của xúc xắc, quân cờ có thể đi từ A đến B theo luật cờ chung, nhưng chúng ta sẽ cấm quân tượng di chuyển từ ô này sang ô khác nếu chúng có một cạnh chung. Chúng ta sẽ tạo một ngoại lệ tương tự cho các nước đi chéo của quân hậu, nếu không những quân này sẽ quá mạnh.

Để giúp người đọc làm quen với hình dạng bàn cờ của chúng tôi dễ dàng hơn, chúng tôi khuyên bạn nên tạo một bộ mảnh shakur, bao gồm khối Rubik và các mảnh nhãn dán được làm bằng băng dính.

Hình 1.

Hình 2.

⟦folio 71⟧

---
running_head:
folio:
---

Các nước đi đơn giản nhất (và theo đó là sự phát triển) của quân và vua (hình 2). Trong tương lai, trong các bản vẽ, chúng tôi sẽ đánh dấu bằng dấu chấm các trường trên các mặt "hiển thị" mà hình có thể truy cập được.
Đối với con voi, nếu nó không chiếm ô vuông trung tâm hoặc góc của khuôn mặt thì các trường bị đứt sẽ tạo thành hai kinh tuyến chéo giao nhau ở hai cực đối cực. hình 3 cho thấy hai con voi nằm ở hai cực như vậy và có quỹ đạo giống hệt nhau.
Bài toán 1. Vẽ đường phát triển của khối lập phương để xác định một kinh tuyến chuyển động của quân tượng $C_1$ từ vị trí trên hình 3.
Khả năng của quân tượng nằm ở ô vuông trung tâm hoặc góc của khuôn mặt được thể hiện ở hình 4.
Bài toán 2. Kiểm tra xem trong một vài nước đi quân tượng có thể đi từ bất kỳ ô nào trên bàn cờ đến bất kỳ ô nào khác không. Quân tượng có thể đi được bao nhiêu nước đi từ ô 1 đến ô 2 (xem hình 4)?
Bài toán 3. Phân tích tính chất của quân hậu.
Ngay trên bàn cờ tướng, các hiệp sĩ cũng nổi bật với những chiêu thức quỷ quyệt; trên xúc xắc, nước đi của họ thậm chí còn bất ngờ hơn (xem hình 5).
Lưu ý rằng theo cách được mô tả, có thể xác định chuyển động của các hình trên bề mặt của khối ca rô có các mặt có kích thước $n \times n$ chứ không chỉ $3 \times 3$.

Hình 4.
Hình 5.
Hình 3.
Hình 6.

⟦folio 72⟧

---
running_head:
folio:
---

Trên một bảng như vậy, bạn có thể giải tổng quát bài toán bằng các chuyển động “chủ động” của các quân cờ. Ví dụ, chứng minh rằng vua đỏ và xe có thể giao phối với vua đen đơn độc; vị trí cuối cùng có thể giống như ở hình 6.

Thật tò mò rằng việc chuyển sang quân xe, vốn đủ tối thiểu để đánh bại một vị vua đơn độc trên bàn cờ chung, hóa ra lại là đủ khi chết! Điều bất ngờ hơn nữa là trên khối lập phương $3 \times 3$, bạn có thể nghĩ ra các vị trí giao phối trong đó các vị vua ở phe mạnh nhất bao gồm hai quân tượng, một quân tượng và một hiệp sĩ, hai hiệp sĩ - một lần nữa giống như trên bàn cờ chung.

hình 7 hiển thị vị trí mờ; biểu tượng $\infty$ trong một hình vuông của bàn cờ có nghĩa là quân tượng đang ở trên một hình vuông phản trường ở xa và như chúng ta biết, một quân tượng kép như vậy hoạt động như thể nó đang ở trong hình vuông được nhìn thấy. Từ hình 8 rõ ràng, cùng với vua đỏ, các quân tượng vô hình đã cắt đứt mọi đường thoát của vua đen, và một trong số họ còn tuyên bố chiếu - chiếu trên bàn cờ.

Hãy để chúng tôi trình bày mà không bình luận thêm một vài tư thế giao phối nữa.

Ở vị trí hình 9, chúng ta sẽ không thể xoay khối lập phương sao cho tất cả các hình đều nằm trên các mặt nhìn thấy được. Vua đỏ nằm ở cạnh dưới vô hình của khối lập phương, một phần của nó được mô tả dưới dạng bản quét.

Có thể tiếp tục cân nhắc việc “lộ” nước cờ

⟦folio 73⟧

---
running_head:
folio:
---

trên khối lập phương và giải bài toán tương ứng, nhưng chúng ta có một mục tiêu khác trong ghi chú này - sử dụng khả năng phạm vi của khối Rubik.
Chúng ta gọi hai vị trí là tương thích nếu một vị trí có thể đạt được từ vị trí kia bằng cách xoay các mặt của khối lập phương.
Ví dụ: vị trí được mô tả tại hình 6 tương thích với vị trí tại hình 10.
Bây giờ, cuối cùng chúng ta cũng có thể sắp xếp các điều kiện của trò chơi Shakur: từ sự sắp xếp nhất định của các quân đỏ và đen, bằng cách xoay các mặt của khối lập phương, chúng ta có thể đạt được một vị trí tương thích với nó mà vua đen sẽ bị chiếu tướng trên bàn cờ.
Lời giải như vậy bài toán sẽ bao gồm hai phần: đầu tiên bạn cần nghĩ ra vị trí giao phối, sau đó lấy nó bằng cách thực hiện các động tác xoay.

Nhấn mạnh rằng các quân cờ sẽ chỉ di chuyển cùng với bàn cờ.
Đối với những người muốn nghĩ ra bài toán, chúng tôi lưu ý rằng với số lượng lớn quân đen, vai trò của họ sẽ gấp đôi: họ có thể tiêu diệt các đòn tấn công của quân đỏ, nhưng họ cũng có thể hạn chế khả năng di chuyển của quân đen của chính mình.
Giống như trong một thể thức cờ vua thông thường, có thể đưa ra các hạn chế về số lần đi/xoay (“chiếu tướng trong hai nước đi”), nhưng chúng tôi sẽ không làm điều này.
Để kết luận, chúng tôi cung cấp cho độc giả thêm bốn bài toán (hình 11) với cùng một nhiệm vụ phác thảo: tìm ra chiến thắng trong trò chơi Shakur, tức là, ghép vua đen bằng các phép quay của khối Rubik (không có hình nào trên các khuôn mặt vô hình).

Nhiệm vụ 4.

Nhiệm vụ 5.

Hình 11.

Nhiệm vụ 6.

Nhiệm vụ 7.
