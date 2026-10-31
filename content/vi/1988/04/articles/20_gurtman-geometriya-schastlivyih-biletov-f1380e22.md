---
id: 1988-4-gurtman-geometriya-schastlivyih-biletov-f1380e22
issue: kvant_1988_4
year: 1988
number: "4"
title: Hình học của tấm vé “may mắn”
authors:
  - Гуртман Г. Н.
rubric: smes
page_first: 74
page_last: 74
page_labels: "72"
tag: LEMC
lang: vi
source: kvant_digital
extraction: vision
content_sha256: 5663d8b0004ac27a6f6ac300123a18026d84f56ed347b5768effc375203e6c4e
prompt_sha256: draft-1
translated_from: content/ru/1988/04/articles/20_gurtman-geometriya-schastlivyih-biletov-f1380e22.md
source_content_sha256: eeae882ac1245ba107cc1e7973d17504657852e58a5a8fda797ff170b8c2b1b1
translation_model: draft
translation_run: vi-draft-2026-10-31
translation_quality: draft
---

⟦folio 72⟧

các số tự nhiên liên tiếp nào
4. Các số 1, 2, 3,...,64 được đặt ngẫu nhiên vào các ô của bàn cờ. Chứng minh rằng có ít nhất ba hình vuông $2 \times 2$, tổng các số trong mỗi hình vuông lớn hơn 100.
5. Chứng minh rằng nếu $a, b, c$ là các cạnh của một tam giác tùy ý thì $a^2 + b^2 + c^2 < 2(ab + ac + bc)$.
6. Có bao nhiêu cặp song song, tất cả các mặt đều là hình thoi giống hệt nhau với một góc nhọn $a$? Tìm tỉ số thể tích của các dịch song song đó với nhỏ nhất.
Thông tin
1. Phát triển một thuật toán và viết (bằng bất kỳ ngôn ngữ lập trình nào) một chương trình chọn từ một chuỗi số nguyên tùy ý, đầu tiên là tất cả các số dương theo thứ tự tăng dần, sau đó là tất cả các số âm theo thứ tự giảm dần.
2. Xây dựng chương trình huấn luyện-điều khiển về chủ đề “Định luật Coulomb”. Thực hiện nó bằng bất kỳ ngôn ngữ lập trình nào.
3. Máy bán nước ngọt tự động có bộ vi xử lý tích hợp sẽ hoạt động như sau:
Người nhận xu có trách nhiệm thả một hoặc nhiều đồng xu có tổng mệnh giá từ 1 đến 6 kopecks. Sau đó, nhấn một trong ba nút: "Không có xi-rô - 1 kopeck", "Có xi-rô - 3 kopecks", "Với xi-rô đôi - 5 kopecks."
Máy xác định số tiền lẻ nhận được, nếu đủ sẽ phân xu vào các thùng thích hợp (đối với đồng 1, 2, 3 và 5 kopeck), đổ đầy nước vào ly, đưa tiền lẻ ra và trở về trạng thái ban đầu; Nếu không đủ tiền, máy sẽ trả lại.
Mô tả thuật toán hoạt động của bộ vi xử lý được tích hợp trong máy tự động. Viết (bằng bất kỳ ngôn ngữ lập trình nào) một chương trình thực hiện thuật toán này.
V. N. Serdeev

Hình học của tấm vé “may mắn”

Bài viết của V. G. Boltyansky “Chương trình vũ phu” («Kvant», số 1) thảo luận về bài toán xác định số vé “may mắn”, tức là các số có sáu chữ số trong đó tổng của ba chữ số đầu bằng tổng của các chữ số còn lại. bài toán này rút gọn thành việc đếm số số có ba chữ số với tổng các chữ số S. Từ mô tả thuật toán được đưa ra trong bài viết, hai chữ số đầu tiên của số $K$ và $L$ phải thỏa mãn các bất đẳng thức sau:
$$0 \leq K \leq 9, \quad 0 \leq L \leq 9, \quad K + L \leq S, \quad K + L \geq S - 9.$$
Lưu ý rằng bất đẳng thức cuối cùng trong chương trình của V. G. Boltyansky (xem trang 7) có một bất đẳng thức sai; Dòng 70 sẽ trông như thế này:
$$70 \text{ IF } K + L > S - 10 \text{ THEN } Q = Q + 1$$
Chúng ta đánh dấu trên mặt phẳng tọa độ $OKL$ các điểm có tọa độ $(K, L)$ thỏa mãn điều kiện ghi ở trên. Nếu $S \leq 9$ thì các điểm tương ứng tạo thành một hình tam giác (hình 1). Nếu $S > 9$ (nhưng $S$ không lớn hơn 17) là hình lục giác (hình 2). Xét số điểm "hợp lệ" $Q(S)$ là ok
$$S \quad 0 \quad 1 \quad 2 \quad 3 \quad 4 \quad 5 \quad 6 \quad 7 \quad 9 \quad 9 \quad 10 \quad 11 \quad 12 \quad 13$$
$Q(S) = Q(S - 1) + S + 1.$
Nếu $S > 9$ thì số điểm trong các hình tam giác phía dưới bên trái ($Q(S - 10)$) và phía trên bên phải ($Q(S - 17)$) phải được trừ vào tổng số 100 điểm của hình vuông.

Vì $Q(0) = 1$, chúng ta có thể xác định tuần tự $Q(1), Q(2), \dots, Q(9)$ và viết chúng ra bảng. Sử dụng các phần tử thu được, chúng tôi tính toán $Q(S)$ cho $S$ từ 10 đến 13 và điền vào bảng đến cuối.

Telery, theo thuật toán của V. G. Boltyansky, trả bình phương $Q(S)$ về bình phương, tính tổng các giá trị này và xóa kết quả. Đừng quên trừ 1 - không có vé số 000.000 - và ta được kết quả: số vé may mắn là 55.251. Những cân nhắc hình học đơn giản của hiện tại đã làm giảm việc tìm kiếm đến mức chúng tôi đã thực hiện mà không cần máy tính!

G. N. Gurtman
