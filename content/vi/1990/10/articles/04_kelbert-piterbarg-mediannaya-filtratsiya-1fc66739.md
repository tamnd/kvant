---
id: 1990-10-kelbert-piterbarg-mediannaya-filtratsiya-1fc66739
issue: kvant_1990_10
year: 1990
number: "10"
title: Lọc trung vị
authors:
  - Кельберт М. Я.
  - Питербарг Л.
rubric: osnovnye-stati
page_first: 10
page_last: 15
page_labels: 8, 12, 13
lang: vi
source: kvant_digital
extraction: vision
content_sha256: 3c1c8ce73245325adcee2a1f4e4380850e03976128d852536932c759b887e35f
prompt_sha256: draft-1
translated_from: content/ru/1990/10/articles/04_kelbert-piterbarg-mediannaya-filtratsiya-1fc66739.md
source_content_sha256: 580ea2bb945c50a563f6201e05607e95fe7a7816d18a3cfcfd1f10764b93db5c
translation_model: draft
translation_run: vi-draft-gaps-2026-11-05
translation_quality: draft
---

⟦folio 8⟧

---
running_head:
folio:
---

TRUNG BÌNH
LỌC
Ứng viên Khoa học Vật lý và Toán học
M. KELEVERT,
Tiến sĩ Khoa học Vật lý và Toán học
L. PITERSBARG

8

⟦folio 12⟧

---
running_head:
folio:
---

số chiều rộng $2k+1$ không chứa một đoạn đơn điệu có chiều dài $k+1$, thì các số $x_n$ chỉ có thể nhận hai giá trị ​​(tín hiệu nhị phân).

Vì vậy, tình huống “nghịch lý” của ví dụ 2 chỉ nảy sinh đối với tín hiệu nhị phân.

Xử lý hình ảnh

Ngày nay, mối quan tâm đến việc lọc trung vị trước hết là do vấn đề xử lý các bức ảnh về bề mặt Trái đất và các thiên thể thu được từ không gian. Việc chụp bốn bức ảnh thường bị cản trở bởi mây, trong trường hợp này được coi là nhiễu. Tất nhiên, nếu một phần đáng kể của vật thể bị mây che phủ thì không có quy trình toán học nào có thể giúp khôi phục lại đường viền thực sự của nó. Nhưng nếu mây hiếm khi xảy ra thì bộ lọc trung vị sẽ có tác dụng giải cứu.

Chia một bức ảnh đen trắng thành các ô vuông nhỏ và ghép nó với một bảng số hình chữ nhật có mức độ sáng $x_{ij}$ trong mỗi ô vuông. Bây giờ, cùng với các hình ảnh, chúng ta đang xử lý một bảng số. Và bạn có thể áp dụng quy trình lọc trung vị cho chúng. Nó được thực hiện như thế này. Hãy chọn một số hình dạng (hình tròn, hình vuông, hình chữ thập, cọc, v.v.) - nó được gọi là cửa sổ bộ lọc - và áp dụng nó cho hình ảnh. Giá trị độ sáng ở giữa cửa sổ được thay thế bằng giá trị trung bình của các số $x_{ij}$ cho tất cả các điểm có trong cửa sổ này.

Ví dụ: đặt $x_{ij}$ bằng 100 nếu $i$ và $j$ đều chia hết cho 10 và bằng 0 nếu ngược lại. Kiểm tra xem sau khi lọc trung vị, hình ảnh đó sẽ chỉ bao gồm các số 0. Điều này có nghĩa là khi xử lý ảnh thật, các điểm rất tối và rất sáng sẽ biến mất. Điều này có thể được nhìn thấy trong bức ảnh chụp một trong những khu vực của Pamirs, được chụp bởi

Hình 1.

⟦folio 13⟧

---
running_head:
folio:
---

Noah từ tàu vũ trụ Soyuz. Trong bức ảnh đầu tiên, không có mô tả, có thể thấy rõ những đốm đen trên lớp phủ tuyết. Và trong hình ảnh thứ hai, thu được sau khi lọc trung vị, những điểm này biến mất.

Lọc hình ảnh trung bình có đặc tính quan trọng từ quan điểm thực tế là duy trì ranh giới rõ ràng của các vật thể đen và trắng. Ví dụ: hãy lấy hình ảnh đơn giản nhất: hình vuông màu đen trên nền trắng. Giá trị độ sáng tại các điểm của hình vuông là 1 và bên ngoài nó - 0 (hình 1). Với bộ lọc trung vị có cửa sổ ở dạng hình vuông $3 \times 3$, kết quả sẽ là một hình vuông với các điểm góc bị ném ra ngoài và nếu cửa sổ có dạng hình chữ thập từ một điểm của một điểm thì hình vuông màu đen sẽ bất biến.

Bài tập 12. Trên hình 2 có năm cửa sổ và bên dưới chúng có năm hình ảnh. Kiểm tra xem tất cả các hình ảnh có bất biến không.

Tóm lại, chúng tôi lưu ý rằng khái niệm lọc trung vị chỉ quan trọng đối với các tín hiệu rời rạc (tức là các chuỗi số), mà còn đối với tín hiệu liên tục (tức là một hàm xác định trên một trục số hoặc trên một số đoạn của nó). Chúng tôi sẽ không đưa ra định nghĩa chính xác - nếu muốn, bạn có thể tự mình nghĩ ra một định nghĩa; Giả sử rằng quá trình lọc như vậy có đặc tính chính là lọc rời rạc: nó phá hủy các “ngoại lệ” trong khi vẫn giữ được hình thức chung của tín hiệu.

Hình 2.

là các biến thể liên quan đến lọc trung vị với các cửa sổ tương ứng.

Như trong trường hợp một chiều, bộ lọc trung vị loại bỏ thành công các mẫu lớn hiếm gặp và thiết bị trượt loại bỏ các lỗi xen kẽ nhỏ. Nếu có sai số lớn thì thiết bị trượt sẽ có hại vì khi “bôi nhọ” lỗi sẽ tạo ra các đốm xám trên ảnh.

Bài tập 13. Đưa hình ảnh trên hình 3 vào bộ lọc trung vị với các cửa sổ có dạng hình vuông $3 \times 3$ và hình chữ thập gồm 5 ô, cũng như một thiết bị trượt có cùng cửa sổ. Màu xanh lam phản hồi với tín hiệu cường độ là 2, màu đỏ là 0 và màu trắng là +2.

Gợi ý: Lần đầu tiên bạn lọc, hình ảnh sẽ biến mất.

Tóm lại, chúng tôi lưu ý rằng khái niệm lọc trung vị chỉ quan trọng đối với các tín hiệu rời rạc (tức là các chuỗi số), mà còn đối với tín hiệu liên tục (tức là một hàm xác định trên một trục số hoặc trên một số đoạn của nó). Chúng tôi sẽ không đưa ra định nghĩa chính xác - nếu muốn, bạn có thể tự mình nghĩ ra một định nghĩa; Giả sử rằng quá trình lọc như vậy có đặc tính chính là lọc rời rạc: nó phá hủy các “ngoại lệ” trong khi vẫn giữ được hình thức chung của tín hiệu.
