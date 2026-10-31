---
id: 1976-10-kolmogorov-gruppyi-preobrazovaniy-cecc366c
issue: kvant_1976_10
year: 1976
number: "10"
title: Nhóm chuyển đổi
authors:
  - Колмогоров А. Н.
rubric: osnovnye-stati
page_first: 4
page_last: 6
page_labels: 2, 4
tag: SM6R
lang: vi
source: kvant_digital
extraction: vision
content_sha256: 9ded8b4772578ae4e4ecaaaf9bc8ae445f392b9afcca13afb43e339eb2ad52fe
prompt_sha256: draft-1
translated_from: content/ru/1976/10/articles/03_kolmogorov-gruppyi-preobrazovaniy-cecc366c.md
source_content_sha256: 73df56adcea2b2207a24ca33db2414d0a7d9c9a27785de4c7066609423d40cd5
translation_model: draft
translation_run: vi-draft-2026-10-31
translation_quality: draft
---

⟦folio 2⟧

NHÓM CHUYỂN ĐỔI

Mục đích bài viết ngắn của tôi là làm cho nội dung bài báo “Nhóm” đã xuất bản của L. Sadovsky và M. Arshinov trở nên dễ tiếp cận hơn và kết nối nó với sách giáo khoa phổ thông mới.

Theo chương trình học mới, học sinh lớp 5 được làm quen với khái niệm “sắp xếp một tập hợp thành một tập hợp”. Ở lớp sáu, các em được làm quen với khái niệm “ánh xạ khả nghịch” (theo một thuật ngữ khác, quen thuộc với nhiều độc giả «Kvant», “ánh xạ một-một”).

Mọi bản đồ khả nghịch đều có một bản đồ nghịch đảo. Ví dụ: phép quay $R_0^{70^\circ}$ quanh điểm $O$ theo $70^\circ$ ngược chiều kim đồng hồ (Hình 1) có ánh xạ nghịch đảo là phép quay quanh điểm $O$ theo $70^\circ$, nhưng theo chiều kim đồng hồ. Trong sách giáo khoa hình học mới, phép quay này được ký hiệu là $R_0^{-70^\circ}$ (xoay quanh điểm $O$ bằng âm $70^\circ$).

Trong các lớp tiếp theo và cuối cùng, học sinh được làm quen với khái niệm “bố cục trưng bày”. Ví dụ, chúng ta hãy xem xét hai chuyển động của mặt phẳng, nghĩa là hai ánh xạ của mặt phẳng lên chính nó để bảo toàn khoảng cách. Là chuyển vị đầu tiên, chúng ta lấy đối xứng trục $S_x$ với trục $x$ và đối xứng thứ hai - đối xứng trục $S_y$ với trục $y$, vuông góc với trục $x$ (Hình 2). Điều gì xảy ra nếu bạn thực hiện tuần tự hai ánh xạ này: đầu tiên là $S_x$ và sau đó là $S_y$?

Điểm $P$ có đối xứng $S_x$ sẽ đi vào điểm $P_1$, đối xứng với trục $x$, và với đối xứng $S_y$ của điểm $P_1$, nó sẽ đi vào điểm $P_2$. Câu trên có thể viết dưới dạng đẳng thức

$$P_2 = S_y(S_x(P)).$$

Mặt khác, điểm $P_2$ có thể được lấy trực tiếp từ điểm $P$ bằng cách sử dụng đối xứng trung tâm $Z_0$ với tâm $O$ là giao điểm của các đường $x$ và $y$:

$$P_2 = Z_0(P).$$

Hãy tự chứng minh rằng với mọi điểm $P$ của mặt phẳng

$$S_y(S_x(P)) = Z_0(P)$$

(như đã nói, giả định rằng các đường $x$ và $y$ vuông góc và cắt nhau tại điểm $O$).

⟦folio 4⟧

Bằng cách giải bài toán 2 và 3, bạn chứng minh được rằng tập hợp $G_1$ có các thuộc tính (1) và (2) theo định nghĩa của nhóm biến đổi, nghĩa là $G_1$ là nhóm biến đổi mặt phẳng.

Một thực tế tổng quát hơn có thể được chứng minh: tập $G_\Phi$ tất cả các chuyển vị của mặt phẳng; ánh xạ bất kỳ hình đã cho nào $\Phi$ lên chính nó là một nhóm biến đổi mặt phẳng. Chứng minh không khó (làm đi!). Nhóm $G_\Phi$ được gọi là nhóm hình đối xứng $\Phi$.

Từ bảng thành phần của bộ $G_1$ chúng ta thấy rằng thành phần của các chuyển động không phải lúc nào cũng có thể định vị lại được:

$$S_{(OA)} \circ S_{(OB)} = R_0^{-120^\circ} \neq R_0^{120^\circ} = S_{(OB)} \circ S_{(OA)}.$$

Tuy nhiên, có thể chứng minh rằng phép toán hợp thành biến đổi tập hợp $M$ luôn có tính chất kết hợp:

$$F_3 \circ (F_2 \circ F_1) = (F_3 \circ F_2) \circ F_1$$

(hãy thử cái này).

Bảng 1

| $\circ$ | $E$ | $S_{(OA)}$ | $S_{(OB)}$ | $S_{(OC)}$ | $R_0^{120^\circ}$ | $R_0^{-120^\circ}$ |
| :--- | :--- | :--- | :--- | :--- | :--- | :--- |
| $E$ | $E \circ E = E$ | $E \circ S_{(OA)} = S_{(OA)}$ | $E \circ S_{(OB)} = S_{(OB)}$ | $E \circ S_{(OC)} = S_{(OC)}$ | $E \circ R_0^{120^\circ} = R_0^{120^\circ}$ | $E \circ R_0^{-120^\circ} = R_0^{-120^\circ}$ |
| $S_{(OA)}$ | $S_{(OA)} \circ E = S_{(OA)}$ | $S_{(OA)} \circ S_{(OA)} = E$ | $S_{(OA)} \circ S_{(OB)} = R_0^{-120^\circ}$ | | | |
| $S_{(OB)}$ | | $S_{(OB)} \circ S_{(OA)} = R_0^{120^\circ}$ | | | | |
| $S_{(OC)}$ | | | | | | |
| $R_0^{120^\circ}$ | | | | | | |
| $R_0^{-120^\circ}$ | | | | | | |
