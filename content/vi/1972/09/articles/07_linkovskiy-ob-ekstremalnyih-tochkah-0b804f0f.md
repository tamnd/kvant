---
id: 1972-9-linkovskiy-ob-ekstremalnyih-tochkah-0b804f0f
issue: kvant_1972_9
year: 1972
number: "9"
title: Về điểm cực trị
authors:
  - Линковский Ж. Б.
rubric: matematicheskiy-kruzhok
rubric_sub: Математический кружок
page_first: 37
page_last: 37
page_labels: "35"
tag: Y98L
lang: vi
source: kvant_digital
extraction: vision
content_sha256: a3b1788ac25cf6d4aa76d9a2574d1e3eaf61813b014543e27a0b168ca1a910ae
prompt_sha256: draft-1
translated_from: content/ru/1972/09/articles/07_linkovskiy-ob-ekstremalnyih-tochkah-0b804f0f.md
source_content_sha256: 253d1dc7683051616e20e805c5ab97cc75f6e29c5ad734a68ceaea128eca3d7d
translation_model: draft
translation_run: vi-draft-2026-10-31
translation_quality: draft
---

⟦folio 35⟧

Về thùy cực
Zh.B.Pinkovsky

Điểm cực trị là điểm mà tại đó một hàm số nào đó đạt giá trị lớn nhất hoặc lớn nhất của nó. Dễ dàng chứng minh rằng giao điểm của các đường trung tuyến của một tam giác có tính chất sau: với nó tổng bình phương khoảng cách đến các đỉnh của tam giác là nhỏ nhất. Trong bài viết này, chúng tôi sẽ trình bày một bằng chứng hoàn toàn cơ bản về sự khái quát hóa thực tế này.

Giả sử có $n$ điểm trên mặt phẳng dữ liệu. Chúng ta hãy giới thiệu hệ tọa độ Descartes trên mặt phẳng với các trục $Ox$, $Oy$ và ký hiệu các điểm này như sau: $A_1(x_1, y_1)$, $A_2(x_2, y_2)$, ..., $A_n(x_n, y_n)$ (Hình 1). Hãy lấy bất kỳ điểm $M(x, y)$ nào trên mặt phẳng. Dễ dàng tìm được bình phương khoảng cách từ điểm $M$ đến điểm $A_i$ bằng định lý Pythagore (Hình 2): $d_i^2 = (x - x_i)^2 + (y - y_i)^2$. Tổng các khoảng cách bình phương từ $M$ đến các điểm $A_1$, $A_2$, ..., $A_n$ trông như thế này:

$$D = d_1^2 + d_2^2 + \dots + d_n^2 = (x - x_1)^2 + (y - y_1)^2 + (x - x_2)^2 + (y - y_2)^2 + \dots + (x - x_n)^2 + (y - y_n)^2.$$

Hãy mở ngoặc và biểu thị $D$ dưới dạng tổng của các đa thức từ $x$ và $y$:

$$D = nx^2 - 2x(x_1 + x_2 + \dots + x_n) + (x_1^2 + x_2^2 + \dots + x_n^2) + ny^2 - 2y(y_1 + y_2 + \dots + y_n) + (y_1^2 + y_2^2 + \dots + y_n^2).$$

Kết quả là tổng của hai đa thức, một đa thức chỉ phụ thuộc vào $x$:

$$P(x) = nx^2 - 2x(x_1 + x_2 + \dots + x_n) + (x_1^2 + x_2^2 + \dots + x_n^2),$$

thứ hai chỉ phụ thuộc vào $y$:

$$Q(y) = ny^2 - 2y(y_1 + y_2 + \dots + y_n) + (y_1^2 + y_2^2 + \dots + y_n^2)$$

và $D = P(x) + Q(y)$. Chúng tôi lưu ý rằng $x$ và $y$ là độc lập, do đó $D$ đạt giá trị tối đa đối với $x$, trong đó $P(x)$ là nhỏ nhất và đối với $y$, trong đó $Q(y)$ là nhỏ nhất. Nhưng $P(x)$ và $Q(y)$ là đa thức bậc hai (có hệ số hơi dài). Đồ thị của hàm $P(x)$ sẽ là một parabol (Hình 3), các nhánh của nó hướng lên trên ($n > 0$), giá trị nhỏ nhất $u = P(x)$ đạt được tại $x$, bằng hoành độ của đỉnh parabol. Từ đây, dễ dàng tìm thấy giá trị của $x$ trong đó $P(x)$ là tối thiểu: $x = \frac{x_1 + x_2 + \dots + x_n}{n}$.

Tọa độ $y$ (từ $Q(y)$) được tìm tương tự: $y = \frac{y_1 + y_2 + \dots + y_n}{n}$.

Chúng tôi xin trình bày với bạn đọc cách giải bài toán sau.

1. Chứng minh tọa độ giao điểm của các đường trung tuyến của tam giác với các đỉnh $A_1(x_1, y_1), A_2(x_2, y_2), A_3(x_3, y_3)$ như sau:

$$x = \frac{x_1 + x_2 + x_3}{3}, \quad y = \frac{y_1 + y_2 + y_3}{3}.$$

2. Điểm Torricelli là một điểm trong tam giác có tổng khoảng cách đến đỉnh của tam giác là nhỏ nhất. Chứng minh rằng từ điểm Torricelli, các cạnh của tam giác nhìn thấy được ở các góc $120^\circ$.
