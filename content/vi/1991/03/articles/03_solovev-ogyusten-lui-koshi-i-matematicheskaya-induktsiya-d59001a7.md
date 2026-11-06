---
id: 1991-3-solovev-ogyusten-lui-koshi-i-matematicheskaya-induktsiya-d59001a7
issue: kvant_1991_3
year: 1991
number: "3"
title: Augustin Louis Cauchy và quy nạp toán học
authors:
  - Соловьёв Ю. П.
rubric: osnovnye-stati
page_first: 15
page_last: 16
page_labels: 13-14
lang: vi
source: kvant_digital
extraction: vision
content_sha256: 058713a4e4a58962d22d95e2fc36ad5137bc79ba51bc7296a2c54f7e9f5b5a80
prompt_sha256: draft-1
translated_from: content/ru/1991/03/articles/03_solovev-ogyusten-lui-koshi-i-matematicheskaya-induktsiya-d59001a7.md
source_content_sha256: 86fafd5bbe02ce1b27659e76d97ff1b8d2db42a7cf73964a9faabc1e3e22a067
translation_model: draft
translation_run: vi-draft-gaps-2026-11-06
translation_quality: draft
---

⟦folio 13⟧

---
running_head:
folio:
---

THÁNG 8
LOUIS CAUCHY VÀ
TOÁN HỌC
cảm ứng

Tiến sĩ Khoa học Vật lý và Toán học
Y. GIẢI QUYẾT

Trung bình số học của các số dương không nhỏ hơn trung bình hình học của chúng:

$$\frac{x_1+x_2+\ldots+x_n}{n} \geq \sqrt[n]{x_1x_2\ldots x_n}.$$

Giá trị đẳng thức này thuộc về nhà toán học người Pháp O. Cauchy, được xuất bản vào năm 1821. Kể từ đó, theo truyền thống, nó được coi là một trong những bất đẳng thức số khó nhất. Trong suốt một thế kỷ rưỡi, hàng chục bằng chứng khác nhau về sự bất đẳng thức này đã xuất hiện. Truyền thống này được bắt đầu bởi chính Cauchy. Bằng chứng của ông mất vài trang tính toán phức tạp. Tôi mời độc giả làm quen với cách chứng minh đơn giản nhất mà tôi biết. Theo tôi, nó vừa đẹp vừa đáng trân trọng. Nhưng trước tiên chúng ta cần phải trình bày lại một chút bất đẳng thức Cauchy.

Tại sao phải định dạng lại bài toán giống nhau? Các nhà toán học thông thường biết rằng hoạt động này hoàn toàn không vô dụng như vẻ ngoài của nó... Những bằng chứng đơn giản về các định lý phức tạp thường bao gồm nhiều cách tái lập.

Trước hết, trong bất đẳng thức của chúng ta, căn bậc $n$ đáng sợ ở vế phải cộng lại. Hãy chia cả hai phần cho nó. Đơn vị sẽ vẫn ở bên phải và dấu vết sẽ là giá trị trung bình số học của các số.

$$y_1 = \frac{x_1}{\sqrt[n]{x_1x_2\ldots x_n}}, \ldots, y_n = \frac{x_n}{\sqrt[n]{x_1x_2\ldots x_n}}.$$

⟦folio 14⟧

---
running_head:
folio:
---

Trong điều kiện
$$y_1 > 0, \dots, y_n > 0,$$
$$y_1 y_2 \dots y_n = 1$$

cần phải chứng minh rằng
$$\frac{y_1 + y_2 + \dots + y_n}{n} \geqslant 1.$$ (*)

Bây giờ hãy nghĩ về chỉ mục toán học. Chúng ta sẽ từng bước chứng minh bất đẳng thức Cauchy, mỗi lần tăng $n$ lên một. Đối với $n = 1$ điều đó là hiển nhiên (và biến thành một đẳng thức nghiêm ngặt). Giả sử rằng chúng ta đã chứng minh được bất đẳng thức cho một số $n$. Vì vậy, bây giờ chúng ta cần xuất nó cho $n + 1$.

Bước chỉ định
Cần phải chứng minh rằng nếu
$$z_1 > 0, \dots, z_n > 0, z_{n+1} > 0,$$
$$z_1 z_2 \dots z_n z_{n+1} = 1,$$
thì $z_1 + \dots + z_n + z_{n+1} \geqslant n + 1$. Chúng ta hãy sử dụng bất đẳng thức (*) mà chúng ta coi là đã được chứng minh cho các số $n$. Hãy để $y_1 = z_1, \dots, y_{n-1} = z_{n-1}, y_n = z_n, z_{n+1}$. Khi đó cả hai điều kiện đều được thỏa mãn
$$y_1 > 0, \dots, y_n > 0,$$
$$y_1 y_2 \dots y_n = 1,$$

Và chúng ta giả sử rằng bất đẳng thức $y_1 + \dots + y_n \geqslant n$ đã được chứng minh, tức là
$$z_1 + z_2 + \dots + z_{n-1} + z_n \cdot z_{n+1} \geqslant n.$$

Lưu ý rằng cho đến nay chúng ta chỉ quan tâm đến việc cải cách. Nhưng bằng chứng ở đâu? Đây rồi.

Nếu cần, chúng tôi sẽ thay đổi kích thước các số $z_1, \dots, z_{n+1}$ sao cho $z_n > 1, z_{n+1} < 1$ hài lòng. (Rõ ràng là nếu các số $z_i$ không đồng thời bằng 1, thì trong số chúng có hai số như vậy.) Bây giờ trong công thức cuối cùng, chúng ta lưu ý tích của $z_n \cdot z_{n+1}$ với tổng $z_n + z_{n+1}$. Để làm điều này, chúng ta cần chỉ ra rằng $z_n + z_{n+1} \geqslant z_n \cdot z_{n+1} + 1$ hoặc $z_n + z_{n+1} - z_n \cdot z_{n+1} - 1 \geqslant 0$.

Hãy phân tích vế trái:
$$z_n (1 - z_{n+1}) - (1 - z_{n+1}) = (z_n - 1) (1 - z_{n+1}) \geqslant 0.$$

Sau đó, bất đẳng thức hiển nhiên vì $z_n > 1, z_{n+1} < 1$. Bằng chứng là hợp pháp.

Và bây giờ là một vài lời về bằng chứng này. Chỗ duy nhất chưa hoàn thiện là lựa chọn số $z_n, z_{n+1}$. Nói chung, các công thức tái lập cơ bản và quy nạp toán học đã có tác dụng với chúng tôi.

uốn khúc
(Xem phần đầu ở trang 11)

3. Nhiều hình trung bình có thể được tìm thấy trong tác phẩm cuối cùng của Anri Poincaré “Về một định lý hình học”, trong đó ông cố gắng chứng minh với sự trợ giúp của chúng rằng việc xử lý một chiếc nhẫn thành chính nó, bảo toàn diện tích và dịch chuyển các đường tròn biên ασ theo các hướng khác nhau, có ít nhất hai điểm cố định. Định lý Poincaré được Bircroft chứng minh vào năm 1913 bằng một phương pháp khác, nhưng việc khái quát hóa nó thành ánh xạ của một hình cầu có các điểm điều khiển đã được Y. M. Elishberr chứng minh vào năm 1978 bằng cách sử dụng trung bình-drov (số điểm cố định, tính với bội số, không nhỏ hơn 2g+2, trong đó $g$ là số điểm điều khiển).

Các định lý sau đây cũng tuân theo lý thuyết mức giảm trung bình:

(1) Một đường cong khép kín chính không tự cắt bất khả quy trên mặt phẳng xạ ảnh có ít nhất ba điểm giao nhau.

(2) Một đường cong phẳng kín có ít nhất 4 đỉnh (điểm cực trị của độ cong).

(3) Gọi đoạn sông giữa hai nơi là dương nếu số nơi tiếp theo (dọc theo đường cao tốc) lớn hơn. Chứng minh rằng số điểm vượt sông không nhỏ hơn số biển báo bảo toàn trong dãy biển báo đoạn (trung bình-ds có 4 vị trí trên hình 2 có các dãy (+++), (+ -), (- +)).
