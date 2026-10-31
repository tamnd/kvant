---
id: 1983-9-mischenko-solovev-kvaternionyi-63d2f2cf
issue: kvant_1983_9
year: 1983
number: "9"
title: Đệ tứ
authors:
  - Мищенко А. С.
  - Соловьёв Ю. П.
rubric: osnovnye-stati
page_first: 12
page_last: 17
page_labels: 10, 12, 15
tag: "53E6"
lang: vi
source: kvant_digital
extraction: vision
content_sha256: 2235fddcd960797f33f858aeb1da3201de25282a694f60f8f1c98638d7e86ce3
prompt_sha256: draft-1
translated_from: content/ru/1983/09/articles/06_mischenko-solovev-kvaternionyi-63d2f2cf.md
source_content_sha256: 28ccf4314866eef9ef628861bd22c24f72e413467cff2592728804f25a9796ca
translation_model: draft
translation_run: vi-draft-2026-10-31
translation_quality: draft
---

⟦folio 10⟧

Đệ tứ

Tiến sĩ Vật lý và Toán học
A. S. MISHENKO,
Ứng viên Khoa học Vật lý và Toán học
Y. P. SOLOVIEV

Từ biên tập viên. NĂM CÁ NHÂN “Quait”
đã nói rất nhiều về những con số. Về số phức (số 2, tr. 16), về lịch sử của chúng (số 6, tr. 10), về cách biểu diễn số thực dưới dạng phân số nguyên (số 5, tr. 16 và số 6, tr. 26), về số đại số và số siêu việt (số 7, tr. 2).
Loạt bài này kết thúc bằng bài viết được xuất bản bên dưới (tuy nhiên, bài viết này không yêu cầu bạn phải làm quen với những bài trước). Nó đề cập đến các quaternion - các số chứa số phức và do đó chứa tất cả các số khác. Bạn sẽ tìm hiểu một chút về các ứng dụng của quaternion và về lịch sử tự do tạo ra chúng, điểm khởi đầu là mong muốn đưa cấu trúc đại số (cộng và quan trọng nhất là phép nhân) vào các đối tượng hình học (các tập hợp điểm khác nhau).

Làm thế nào để tạo số từ dấu chấm?

Nếu chúng ta đang nói về các điểm trên một đường thẳng thì điều đó thật đơn giản. Bằng cách chọn phần đầu của báo cáo (“số 0”) và thang đo theo hướng (“một”), bạn có thể thu được trục số từ một đường thẳng và từ đó biến mỗi điểm thành một số thực—tọa độ của nó (Hình 1).

Với các điểm trên một mặt phẳng thì khó khăn hơn. Bằng cách chọn phần đầu của báo cáo (“số 0”) và một cặp trục vuông góc, bạn có thể liên kết mỗi điểm trên mặt phẳng với một cặp tọa độ của nó (x; y). Để tạo ra mỗi cặp như vậy - một cặp đôi - một số, bạn cần học cách "cộng" và "nhân" các cặp đôi này, và sao cho các thuộc tính ghép của phép cộng và phép nhân được bảo toàn (luật giao hoán, kết hợp và phân phối, sự hiện diện của các phép toán nghịch đảo - phép chia và phép trừ).

Vì vậy, việc bổ sung là đơn giản. Việc thêm các cặp đôi dưới dạng vectơ là điều tự nhiên -

⟦folio 12⟧

Tích vectơ $v_3 = v_1 \times v_2$ của các vectơ khác 0 $v_1, v_2$ là vectơ vuông góc với mặt phẳng đi qua vectơ $v_1, v_2$, có hướng xác định theo quy tắc bàn tay phải” (Hình 3) và có độ dài $|v_1| \cdot |v_2|$.

$\sin(v_1, v_2)$. Cần lưu ý thêm rằng nếu vectơ $v_1, v_2$ được cho thuộc tính theo tọa độ trong hệ tọa độ hình chữ nhật:

$$v_1 = (\alpha_1; \beta_1; \gamma_1)$$
$$v_2 = (\alpha_2; \beta_2; \gamma_2),$$

Cái đó
$$v_1 \times v_2 = (\beta_1 \gamma_2 - \beta_2 \gamma_1; \gamma_1 \alpha_2 - \gamma_2 \alpha_1; \alpha_1 \beta_2 - \alpha_2 \beta_1).$$

(4)

Phép toán tích vectơ không phù hợp với Hamilton vì nó không có nghịch đảo. Ví dụ: nếu $v_1 = v_2 \neq 0$ thì góc $(v_1, v_2)$ giữa các vectơ này bằng 0. Điều này có nghĩa là độ dài của tích vectơ $v_3 = v_1 \times v_2$ bằng 0, nghĩa là bản thân vectơ $v_3$ bằng 0. Nếu phép chia cho một vectơ khác 0 luôn tồn tại thì chúng ta có $(v_1 \times v_2):v_2 = v_1 \neq 0$, trong khi $v_1 \times v_2 = 0$ và do đó $(v_1 \times v_2):v_2 \neq 0$. Kết quả mâu thuẫn cho thấy rằng phép chia cho $v_2$ là không thể.

Không thể không khơi dậy sự tôn trọng và ngưỡng mộ rằng, dù thất vọng và thất bại, Hamilton vẫn không từ bỏ hy vọng và trong mười năm, với sự kiên trì tội lỗi, đã cố gắng giải quyết vấn đề mà anh đặt ra cho mình. bài toán. Và mặc dù bài toán chưa bao giờ được giải quyết (và không thể giải quyết được - chúng tôi sẽ giải thích tại sao sau), mười năm làm việc không phải là vô ích. Một ngày đẹp trời năm 1843, Hamilton đột nhiên quyết định không sử dụng bộ ba (bộ ba số), mà là bộ bốn, hay như ông ngay lập tức gọi chúng là bộ tứ, để xác định phép nhân. Đây là cách nó sẽ xảy ra.

Sự cố ở Brogem Place

Trong một trong những bức thư gửi con trai mình, được viết bằng phong cách có phần cứng nhắc đặc trưng của thời đó, Hamilton nhớ lại: "Đó là ngày 16 tháng 10, thứ Hai, ngày diễn ra cuộc họp của Hội đồng Học viện Hoàng gia Ireland, nơi cha sẽ chủ trì. Cha đang cùng mẹ con đi đến đó dọc theo Kênh đào Hoàng gia, và mặc dù bà nói với cha bằng những cụm từ riêng biệt, cha gần như không nhận ra chúng, vì có điều gì đó đang tiềm ẩn trong tâm trí cha. Đột nhiên, mạch điện dường như đóng lại; một tia lửa lấp lánh đã có trước nhiều năm dài xác định suy nghĩ và công việc có định hướng của tôi - nếu nó xảy ra, hoặc công việc của người khác, nếu tôi có đủ ý thức để báo cáo khám phá của mình, tôi không thể cưỡng lại mong muốn dùng dao khắc trên tảng đá mềm của Brohemian đặt công thức cơ bản về các biểu tượng $i, j, k$,

$$i^2 = j^2 = k^2 = ijk = -1,$$

chứa lời giải vấn đề, nhưng tất nhiên, mục này đã bị xóa. Tuy nhiên, một đề cập lâu dài hơn vẫn còn được ghi lại trong Sách Hồ sơ của Hội đồng Học viện về ngày hôm đó, trong đó ghi rằng tôi đã xin phép và được phép báo cáo về các phần tư tại cuộc họp đầu tiên của phiên họp, được đọc vào thứ Hai ngày 13 tháng sau - tháng 11.

Định nghĩa của Quaternion

Quaternion là bộ bốn số thực $(x; y; u; v)$, có thể được viết thuận tiện là

$$q = x + yi + uj + vk,$$

⟦folio 15⟧

Khi nhân quaternions, tình hình phức tạp hơn. Nếu $q_1$ và $q_2$ là bậc bốn vô hướng thì tích của chúng $q_1 q_2$ cũng là bậc bốn vô hướng. Trong trường hợp $q_1 = x$ là một quaternion vô hướng và $q_2 = r$ là một vectơ quaternion thì tích $q_1 q_2 = x \cdot (y_i + uj + vk) = (xy)i + (xu)j + (xv)k$ là một vectơ quaternion và phép nhân trùng với phép nhân của vectơ $r$ trong không gian với số thực $x$.

Và cuối cùng, nếu cả hai quaternion đều là vector:

$$q_1 = r_1 = y_1 i + u_1 j + vk$$
$$q_2 = r_2 = y_2 i + u_2 j + v_2 k,$$

Cái đó

$$q_1 q_2 = -(y_1 y_2 + u_1 u_2 + v_1 v_2) + (u_1 v_2 - v_1 u_2) i + (v_1 y_2 - y_1 v_2) j + (y_1 u_2 - u_1 y_2) k.$$

Như có thể thấy từ công thức cuối cùng, phần vô hướng của tích $q_1 q_2$ bằng tích vô hướng $(r_1, r_2)$ của vectơ $r_1$ và $r_2$ có dấu ngược lại. Phần vectơ $q_1 q_2$ là người bạn cũ của chúng ta - tích vectơ $r_1 \times r_2$, được viết dưới dạng tọa độ (xem (4)).

Kết hợp tất cả các trường hợp đã xem xét, chúng ta thu được công thức chung để nhân bậc bốn. Nếu $q_1 = x_1 + r_1$ và $q_2 = x_2 + r_2$ thì

$$q_1 q_2 = (x_1 x_2 - r_1 \cdot r_2) + (x_1 r_2 + x_2 r_1 + r_1 \times r_2)$$

Còn sinh ba thì sao?

Tại sao Hamilton không tìm được cách thỏa đáng để nhân ba bộ ba? Không phải vì xây dựng không đầy đủ hoặc làm việc chăm chỉ - chúng tôi đã lưu ý ở trên rằng bài toán việc xây dựng “số ba chiều” không thể giải được. Thật vậy, người ta đã chứng minh rằng không có quy trình nhân điểm trong không gian thỏa mãn yêu cầu của chúng ta (tính kết hợp, tính phân phối đối với phép cộng theo tọa độ, khả năng chia thành các phần tử khác 0). Hơn nữa, hiện nay tất cả các trường hợp đều đã biết khi phép nhân như vậy có thể được thực hiện.

Như nhà toán học người Đức F. G. Frobenus (1849-1917) đã chứng minh, có ba trường hợp sau: chiều thứ nhất (số thực thông thường), chiều thứ hai (số phức) và chiều thứ tư (quaternions).

Chuyện gì xảy ra tiếp theo

Hamilton và sự phụ thuộc sau đó của ông vào quaternion. Người ta kỳ vọng rằng các quaternion sẽ tạo ra kết quả tương tự như số phức và thậm chí còn tốt hơn. Thật vậy, với sự trợ giúp của phép tính bậc bốn, các công thức có vẻ đẹp toán học hoàn hảo đã được phát hiện, mô tả một số hiện tượng vật lý quan trọng. Nhưng những hy vọng xa hơn về sự phát triển của phép tính đại số và phép tính bậc bốn hàm đã không thành hiện thực.

Đối với các quaternion, định lý chính của đại số về sự tồn tại nghiệm của một đa thức có hệ số quaternion không đúng, nhưng mặt khác, có một đa thức với các hệ số quaternion trong một biến mà bất kỳ quaternion nào cũng là nghiệm.

Sự lạc quan đã nhường chỗ cho sự hoài nghi. Vào đầu thế kỷ này, các nhà toán học không còn quan tâm đến quaternion. Nhưng thời gian trôi qua, các nhà vật lý vẫn kiên trì tìm kiếm các công thức toán học cho một số hiệu ứng liên quan đến cái gọi là spin của các hạt cơ bản. Các quaternion lấy lại được sự công nhận khi vai trò của chúng trong việc xây dựng các phép biến đổi hình học khác nhau của không gian được sử dụng trong vật lý lượng tử được hiểu rõ. Các tính chất hình học của quaternion là một chủ đề lớn đặc biệt mà chúng tôi hy vọng sẽ nói đến trong tương lai.
