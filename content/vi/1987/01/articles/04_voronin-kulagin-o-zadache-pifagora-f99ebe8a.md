---
id: 1987-1-voronin-kulagin-o-zadache-pifagora-f99ebe8a
issue: kvant_1987_1
year: 1987
number: "1"
title: O bài toán Pythagoras
authors:
  - Воронин С. М.
  - Кулагин А. Г.
rubric: raznoe
page_first: 15
page_last: 16
page_labels: 13-14
tag: 48BZ
lang: vi
source: kvant_digital
extraction: vision
content_sha256: eb1607ad84740d348c682dc2cbac6a9b463d5027aa6cb167fc1e1442f749735b
prompt_sha256: draft-1
translated_from: content/ru/1987/01/articles/04_voronin-kulagin-o-zadache-pifagora-f99ebe8a.md
source_content_sha256: a0edeecbeba8694bac35d0edea42376d607b9e3fce324a2befd924acd0a20920
translation_model: draft
translation_run: vi-draft-2026-10-31
translation_quality: draft
---

⟦folio 13⟧

trông giống như
$$y = k(x + 1),$$
trong đó $k$ là độ dốc của đường thẳng.
Như vậy tọa độ của điểm $(x_2; y_2)$ sẽ thỏa mãn hệ phương trình
$$\begin{cases} x^2 + y^2 = 1, \\ y = k(x + 1). \end{cases}$$
Chúng ta hãy giải hệ này cho $x$ và $y$. Thay giá trị $y = k(x + 1)$ từ phương trình thứ hai vào phương trình thứ nhất của hệ, ta thu được
$$x^2 + k^2(x + 1)^2 = 1,$$
hoặc
$$(1 + k^2) \cdot x^2 + 2k^2 \cdot x + k^2 - 1 = 0.$$
Nếu $x$ thỏa mãn phương trình cuối thì $x$ là hoành độ của giao điểm của đường $y = k(x + 1)$ với đường tròn $K$, tức là $x = x_1 = -1$ hoặc $x = x_2$. Từ định lý Vieta suy ra rằng
$$x_1 + x_2 = -\frac{2k^2}{1 + k^2},$$
Ở đâu
$$x_2 = \frac{1 - k^2}{1 + k^2}.$$
Vì điểm $(x_2; y_2)$ nằm trên đường thẳng $y = k(x + 1)$ nên
$$y_2 = \frac{2k}{1 + k^2}.$$
Hai công thức cuối tương ứng với mỗi số $k$ có dấu chấm
$$(x_2; y_2) = \left(\frac{1 - k^2}{1 + k^2}; \frac{2k}{1 + k^2}\right),$$
nằm trên đường tròn $x^2 + y^2 = 1$. Ngược lại, mỗi điểm $(x; y) \neq (-1; 0)$ nằm trên đường tròn $K$ ứng với một và chỉ một giá trị của hệ số góc $k$:

$$k = \frac{y}{x + 1}.$$

Ở đây lưu ý rằng nếu $k$ là số hữu tỉ thì điểm $(x_2; y_2)$ được xác định theo công thức (6) và có tọa độ hữu tỉ, và ngược lại, nếu $x_2$ và $y_2$ là số hữu tỉ thì theo công thức (7) $k$ là số hữu tỉ. Như vậy,

sự tương ứng một-một được thiết lập giữa các điểm có tọa độ hữu tỉ của đường tròn bán kính đều (trừ điểm $(-1; 0)$) và các điểm hữu tỉ của đường thẳng thực.

Bằng cách buộc các đại lượng $k$ chạy qua tất cả các giá trị hữu tỉ của khoảng từ $-\infty$ đến $+\infty$, chúng ta sẽ liệt kê tất cả các điểm có tọa độ hữu tỉ trên đường tròn $K$ của một bán kính (ngoại trừ điểm $(-1; 0)$) và từ đó tìm ra tất cả các Pythagoras lời giải bài toán nguyên thủy.

Hãy trình bày các công thức tương ứng. Đặt $k = p/q, q > 0$, GCD $(p, q) = 1$. Khi đó từ công thức (6) suy ra rằng

$$\left(x_2; y_2\right) = \left(\frac{q^2 - p^2}{q^2 + p^2}; \frac{2pq}{q^2 + p^2}\right).$$

Về cơ bản chúng ta đã thu được công thức (*) một lần nữa! Để có được kết quả tương tự một cách chính xác, tất cả những gì bạn phải làm là mày mò một chút với bốn.

Trong trường hợp có các chẵn lẻ $p$ và $q$ khác nhau, công thức (**) tương ứng với bộ ba Pythagore nguyên thủy $(a, b, c) = (q^2 - p^2, 2pq, q^2 + p^2)$. Nếu $p$ và $q$ đều là số lẻ thì khi chuyển sang các biến mới $q_1 = (q + p)/2, p_1 = (q - p)/2$, GCD $(p, q) = 1$, chúng ta thu được $q^2 + p^2 = 2(q^2 + p^2), q^2 - p^2 = 4p_1q_1, 2pq = 2(q^2 - p^2)$. Sau khi giảm đi 2 in (**) ta được

$$\left(x_2; y_2\right) = \left(\frac{2q_1p_1}{q_1^2 + p_1^2}; \frac{q_1^2 - p_1^2}{q_1^2 + p_1^2}\right).$$

Lưu ý rằng công thức (8) khác với công thức (**) ở chỗ hoán vị của $x_2$ và $y_2$. Nếu hóa ra $p_1$ và $q_1$ đều là số lẻ thì chúng ta chuyển sang các biến $q_2 = (p_1 + q_1)/2, p_2 = (q_1 - q_1)/2$, GCD $(q_2, p_2) = 1$, v.v. Kết quả là chúng ta thu được công thức loại (**) hoặc công thức loại (8), trong đó $p_1$ và $q_1$ có số chẵn lẻ khác nhau, GCD $(p_2, q_2) = 1$. Do đó, lời giải nguyên thủy tương ứng với điểm hữu tỉ $(x_2; y_2) \neq (-1; 0)$ được cho bằng công thức loại (**) hoặc công thức loại (8), trong đó $p_1$ và $q_1$ là sự tương ứng một-một giữa nghiệm nguyên thủy của phương trình Pythagore và các điểm hữu tỉ của đường tròn $x^2 + y^2 = 1$ (không bao gồm điểm $(-1; 0)$) từ công thức (**) và (8) được theo sau bởi câu lệnh (*).

⟦folio 14⟧

Tham số hóa hợp lý của các phần hữu hạn

Để tìm điểm hữu tỉ nằm trên đường tròn có phương trình $x^2 + y^2 - 1 = 0$, ta rút ra công thức (6). Nó thiết lập sự tương ứng một-một giữa tham số $k$, tham số này nhận tất cả các giá trị thực có thể có và các điểm của đường tròn (ngoại trừ điểm $(-1; 0)$) và tọa độ $(x; y)$ của các điểm nằm trên đường tròn là các hàm hữu tỷ của $k$. Câu hỏi đặt ra là: liệu có thể xác định tương tự các điểm nằm trên các đường cong khác, ví dụ như trên một hình elip, parabol hay hyperbol không? (Elip, parabol và hyperbol là các phần hữu hạn; do đó có tên của phần này.)

Đối với đáp số câu hỏi này, hãy xem xét đường cong trong mặt phẳng được cho bởi phương trình $K(x, y) = 0$, trong đó $K(x, y)$ là đa thức bậc hai trong $x$ và trong $y$. Các điểm nằm trên một parabol, elip và hyperbol thỏa mãn kiểu tương ứng này. Đặt $(x_1; y_1)$ là một điểm cố định nào đó của đường cong như vậy. Chúng ta vẽ một đường thẳng đi qua điểm này với hệ số góc bằng $k$ (hình 3). Chúng ta sẽ tìm các điểm $(x; y)$ giao điểm của đường cong và đường thẳng. tọa độ $(x; y)$ của các điểm này thỏa mãn hệ phương trình
$$\begin{cases} K(x, y) = 0, \\ y - y_1 = k(x - x_1). \end{cases}$$

Giải hệ này cho $(x; y)$ theo cách tương tự như đã làm trước đó cho đường tròn, ta biểu thị tọa độ $(x_2; y_2)$ của giao điểm thứ hai

đường thẳng $y = y_1 + k(x - x_1)$ với đường cong $K$ thông qua tham số $k$. Thật dễ dàng để kiểm tra xem bạn có nhận được một biểu thức như
$$\left(x_2; y_2\right) = \left(\frac{A(k)}{C(k)}; \frac{B(k)}{C(k)}\right),$$
trong đó $A(k), B(k), C(k)$ là các đa thức bậc không lớn hơn 2 trong tham số $k$. Công thức này chỉ định tham số hóa hợp lý của đường cong $K$, tức là nó biểu thị tọa độ của một điểm trên đường cong thông qua các hàm hữu tỷ của một tham số $k$.

Công thức (***), giống như công thức (**), cho phép bạn tìm toàn bộ điểm trên đường cong $K$. Tuy nhiên, bây giờ chúng tôi quan tâm đến một ứng dụng khác - hoàn toàn bất ngờ - của công thức này mà chúng tôi sẽ tiếp tục.

Ứng dụng vào tính tích phân

Hóa ra những tích phân dường như vô vọng như
$$I = \int \frac{dx}{\sqrt{x^2 + 3x - 4}},$$
được thực hiện nếu chúng ta sử dụng tham số hóa hợp lý phù hợp với đường cong đã chọn. Cụ thể là, nếu trong trường hợp này chúng ta lấy đường cong
$$K(x, y) = y^2 - (x^2 + 3x - 4),$$
chú ý rằng điểm $(x_1; y_1) = (-4; 0)$ nằm trên đường cong
$$y(x) = \sqrt{x^2 + 3x - 4}$$
và xét tất cả các đường thẳng có thể
$$y = k(x + 4),$$
sau đó bạn nhận được tham số hóa sau (tự thực hiện các phép tính!):
$$\left(x; y\right) = \left(\frac{1 + 4k^2}{1 - k^2}; \frac{5k}{1 - k^2}\right).$$

Sau đó $dx = \frac{10k}{(1 - k^2)^2} dk$, và do đó (sau khi giảm) chúng ta nhận được
$$I = \int \frac{dx}{\sqrt{x^2 + 3x - 4}} = \int \frac{dx}{y(x)} = \int \frac{2dk}{1 - k^2}.$$

Tích phân cuối cùng dễ tính:
$$\int \frac{2dk}{1 - k^2} = \int \frac{dk}{1 - k} + \int \frac{dk}{1 + k} = \ln |1 + k| - \ln |1 - k| + C = \ln \left| \frac{1 + k}{1 - k} \right| + C.$$
