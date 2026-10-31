---
id: 1981-4-sefibekov-o-ploschadi-mnogougolnika-c3d86c35
issue: kvant_1981_4
year: 1981
number: "4"
title: Về diện tích của đa giác
authors:
  - Сефибеков С. Р.
rubric: matematicheskiy-kruzhok
rubric_sub: Математический кружок
page_first: 22
page_last: 23
page_labels: 20-21
tag: 7UJI
lang: vi
source: kvant_digital
extraction: vision
content_sha256: 31fa01d038da05741b321be1b64bac8f29fa70e5c376e07b5b38347071be62df
prompt_sha256: draft-1
translated_from: content/ru/1981/04/articles/07_sefibekov-o-ploschadi-mnogougolnika-c3d86c35.md
source_content_sha256: 4084bb0f455f7b6ea28c85371c33751972d96747ace7e634e202602dc17890cb
translation_model: draft
translation_run: vi-draft-2026-10-31
translation_quality: draft
---

⟦folio 20⟧

6) * Kiểm tra xem khi chuyển đổi mặt phẳng $(x; y) \rightarrow (x'; y')$, trong đó
$$x' = x \cos \varphi - y \sin \varphi,$$
$$y' = x \sin \varphi + y \cos \varphi,$$
Diện tích của đa giác không thay đổi. (Phép biến đổi này là phép quay một góc φ quanh gốc tọa độ.)
c) Tương tự đối với phép biến đổi $x' = kx, y' = y/k$ (k là số cố định); Đây được gọi là ngã rẽ khác nhau.
d) Diện tích thay đổi bao nhiêu lần trong quá trình biến đổi $x' = ax + by, y' = cx + dy$? (Đáp số. Hệ số này giống nhau đối với tất cả các đa giác; nó bằng môđun của định thức $\left| \begin{array}{cc} a & b \\ c & d \end{array} \right|$.)
13. Công thức (2) cũng đúng với đa giác nhỏ. Để chứng minh điều đó, thuận tiện sử dụng bổ đề sau: Giả sử MP là một tia phát ra từ một điểm M nhất định. Nếu M nằm trong một không phải đa giác thì khi đi vòng quanh đa giác ngược chiều kim đồng hồ, chúng ta sẽ cắt tia MP một số chẵn lần (bằng nhau - từ phải sang trái và từ trái sang phải); nếu điểm M nằm bên trong đa giác thì - số lần lẻ (từ phải sang trái - thêm một lần nữa).
14. Hãy để đa giác được cắt bởi một đường tuyến tính gãy thành hai phần. Kiểm tra xem diện tích được xác định theo công thức (2) cho mỗi phần có bằng biểu thức (2) cho toàn bộ đa giác hay không.
Thực tế này (aditivity), cùng với kết quả của bài tập 3 và 12 a), 6) (bất biến của các phép tịnh tiến tương đối, tính đối xứng và phép quay) cho phép lấy số (2) làm xác định diện tích của đa giác.
15. Đặt tất cả các cạnh của đa giác $A_1B_1A_2B_2...A_mB_m$ là $A_k(a_k; b_k), B_k(a_k+1; b_k), k=1, ..., m$, với $B_m(a_1; b_m)$. Viết công thức diện tích của một đa giác như vậy.

Cơm. 5. Các con số cho biết đa giác đi bao nhiêu lần (có tính đến hướng) xung quanh vectơ của mỗi mảnh.

nikka. Hãy kiểm tra để tìm hình lục giác có các đỉnh $(-1; 0), (2; 0), (2; 5), (3; 5), (3; 7), (-1; 7)$. (Công thức này hữu ích với chúng tôi trong lời giải bài toán M608 - xem «Kvant», 1980, Số 11.)
16. Tìm ra công thức (2) cho bất kỳ điểm $n$ nào của mặt phẳng $A_1, A_2, ..., A_n$.
Đáp số như sau: để đường đứt nét khép kín $A_1A_2...A_n$ chia mặt phẳng thành $r$ một phần diện tích $S_1, ..., S_r$; thì vế phải của công thức (2) bằng tổng $k_1S_1 + ... + k_rS_r$, trong đó số nguyên $k_j$ biểu thị số vòng quay của đường đứt nét $A_1A_2...A_n$ của vectơ $j$ của mảnh tạo ra (và các vòng quay ngược chiều kim đồng hồ được coi là dương, các vòng quay theo chiều kim đồng hồ được coi là âm, xem Hình 5).

S. Sefibekov

Về diện tích của đa giác

Bài viết của N. Vaguten thảo luận về công thức tính diện tích đa giác và các ứng dụng của nó. Một bằng chứng khác của công thức này được đưa ra trong ghi chú được công bố dưới đây.

Đối với diện tích của $S_n$ $n$-gon $A_1A_2...A_n$ công thức đúng
$$S_n = \frac{1}{2} \left| (x_1y_2 + x_2y_3 + ... + x_ny_1) - (y_1x_2 + y_2x_3 + ... + y_nx_1) \right|,$$
trong đó $(x_1; y_1), (x_2; y_2), ..., (x_n; y_n)$ là tọa độ các đỉnh $A_1, A_2, ..., A_n$.

Chứng minh công thức (2) trước tiên cho tam giác vuông có hai cạnh song song với các trục tọa độ (Hình 1), sau đó cho tam giác có một trong các cạnh song song với một trong các trục tọa độ (Hình 2), sau đó cho trường hợp tổng quát (Hình 3).

Nếu bạn đã giải quyết được bài toán này đến cùng, bạn sẽ có một chút thời gian để giải quyết vấn đề tiếp theo.

⟦folio 21⟧

Cơm. 1.

Cơm. 5.

Bài 2. Chứng minh công thức (1) cho tứ giác lồi.
Gợi ý. Chia hình tứ giác thành hai hình tam giác (sử dụng đường chéo - xem Hình 4) và áp dụng bài toán 1.

Bài 3. Chứng minh công thức (1) cho tay n lồi.
Gợi ý. Sử dụng phương pháp quy nạp toán học, biểu diễn đường bao n lồi $A_1A_2A_3...A_n$ đã cho dưới dạng sự kết hợp của đường bao $(n - 1)$ $A_2A_3...A_n$ và hình tam giác $A_1A_2A_3$ (Hình 5). Đối với những độc giả chưa quen với phương pháp quy nạp toán học, chúng tôi khuyên bạn nên giải bài toán 3 cho $n = 5$.

Bây giờ chúng ta chuyển sang đa giác tùy ý (không nhất thiết phải lồi) sau đây.

Bài 4. Chứng minh công thức (1) cho tứ giác tùy ý.
Nhiệm vụ 5*. Chứng minh công thức (1) cho n-dự trữ tùy ý.
Gợi ý. Chứng minh rằng trong không gian n bất kỳ có thể vẽ được một đường chéo nằm hoàn toàn bên trong nó và áp dụng phương pháp quy nạp toán học.

Cơm. 2.

Cơm. 3.

Cơm. 4.
