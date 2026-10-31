---
id: 1987-11-lobkovskiy-matematicheskie-uzoryi-na-ploskosti-f12a4e59
issue: kvant_1987_11
year: 1987
number: "11"
title: Các mô hình toán học trên mặt phẳng
authors:
  - Лобковский А. Э.
rubric: raznoe
rubric_sub: Разное
page_first: 23
page_last: 23
page_labels: "21"
tag: FRPB
lang: vi
source: kvant_digital
extraction: vision
content_sha256: 27247be5dc02b3f12de1af82c5818bbb7501e8886aafc1aae87b31654a302454
prompt_sha256: draft-1
translated_from: content/ru/1987/11/articles/08_lobkovskiy-matematicheskie-uzoryi-na-ploskosti-f12a4e59.md
source_content_sha256: 686f700797f4c1297dd01a6448e66f45725efa71f20a21821a44054ac1bdeaf5
translation_model: draft
translation_run: vi-draft-2026-10-31
translation_quality: draft
---

⟦folio 21⟧

Các mô hình toán học trên mặt phẳng

A.E.LOVKOVSKY

Gần đây, trong toán học ứng dụng đã xuất hiện công trình liên quan đến việc nghiên cứu các mẫu xuất hiện trên màn hình hiển thị nếu mỗi điểm của mặt phẳng được tô màu này hay màu khác theo một quy tắc nhất định. Quy tắc tô màu có thể rất đa dạng.

Thuật toán được thảo luận ở đây đơn giản đến mức một lập trình viên mới vào nghề có thể dễ dàng thực hiện nó trên máy tính. Nó trông như thế này: đối với một điểm trong mặt phẳng $(x; y)$, các giá trị $c = [f(x, y)]$ được tính toán, trong đó $f(x, y)$ là hàm tọa độ đã chọn và dấu ngoặc vuông biểu thị phần nguyên của số; nếu số $c$ là số lẻ thì chấm được tô lên, nếu số chẵn thì không.

Toàn bộ mặt phẳng sau đó sẽ được chia thành các vùng hữu hạn một chiều. Kích thước của vùng giảm dần theo khoảng cách từ điểm gốc. Do đó, trên máy tính có kích thước của một điểm trên màn hình có thể lớn hơn kích thước của khu vực đó, không phải lúc nào cũng có thể khôi phục chính xác hình ảnh thật. Trên thực tế, trong thuật toán của chúng tôi, toàn bộ mặt phẳng được chia thành các ô và mỗi ô được sơn cùng màu với tâm của nó. Do đó, nếu có một số khu vực khác nhau trên lãnh thổ của ô, thì hình kết quả sẽ khác với khu vực thực. Bằng cách giảm kích thước ô, tức là tăng tỷ lệ hình ảnh, chúng tôi cải thiện độ chính xác của việc tái tạo. Chương trình Cơ bản tương ứng cho màn hình $X \times Y$ trông như thế này:

10 INPUT $S$
20 FOR $x=0$ TO $X$
30 FOR $y=0$ TO $Y$
40 IF (INT($f(x, y)/S$)) mod 2=1 THEN PLOT $(x, y)$
50 NEXT $y$
60 NEXT $x$
Vai trò của tỷ lệ ở đây được thể hiện bởi số lượng $S$.

Trong các hình ảnh hiển thị ở trang thứ hai của trang bìa, bạn sẽ thấy các mẫu thu được với các $S$ khác nhau cho $f(x, y) = x^2 + y^2$ (hình 1, ​​​​a-e), $f(x, y) = xy$ (hình 2, a-e), $f(x, y) = x^2 - y^2$ (hình 3, a-e).

Tính tuần hoàn rõ rệt, có thể thấy ở mức $S$ nhỏ trong tất cả các biểu đồ, thật kỳ lạ, lại là một chi phí cho phương pháp tái tạo của chúng tôi. Dấu chấm trên tất cả các thẻ bằng $S$ đối với $S$ chẵn và $2S$ đối với lẻ. Hãy chứng minh điều này bằng ví dụ $f(x, y) = x^2 + y^2$. Thật vậy, màu sắc của điểm

$$\begin{align*}
(x_1; y_1) &= (x + kS; y + lS) \\
(k, l) &= \text{целые числа}
\end{align*}$$

được xác định bởi biểu thức:

$$\frac{x_1^2 + y_1^2}{S} = \frac{(x + kS)^2 + (y + lS)^2}{S} = \frac{x^2 + y^2}{S} + S(2k + 2l + k^2S + l^2S).$$

Có thể thấy rằng phần phân số của các số $(x_1^2 + y_1^2)/S$ và $(x^2 + y^2)/S$ trùng khớp với nhau, và do đó, đối với $S$ chẵn, màu của điểm $(x_1; y_1)$ (tức là tính chẵn lẻ của biểu thức $[(x_1^2 + y_1^2)/S]$) trùng với màu của điểm $(x; y)$ đối với bất kỳ $k$ và $l$ nào, và đối với lẻ $S$ chỉ dành cho $k$ và $l$ có cùng chẵn lẻ. Chúng tôi đề nghị chứng minh cho người đọc thấy rằng khoảng thời gian này là ngắn nhất.

Trong tất cả các biểu đồ được trình bày, số $S$ là số chẵn. Bạn có thể tự mình nhận thấy rằng nếu $S$ lẻ thì các vòng tròn màu đen và trắng sẽ có màu đen.

Người ta có thể không ngừng ngưỡng mộ sự đa dạng nảy sinh từ một phương pháp xây dựng hình có vẻ nguyên thủy như vậy. Đối với $f(x, y) = x^2 + y^2$, ngoài một họ đường tròn rõ rệt có chu kỳ $T$, người ta có thể thấy nhiều họ đường tròn khác (hơn 10) ít tương phản hơn nằm ở các nút của một mạng hình vuông có chu kỳ $T/2, T/3, T/4, T/5, T/7, T/9$ và thậm chí $T/11$. Sẽ rất thú vị khi trả lời các câu hỏi sau: tại sao các vòng tròn “thứ cấp” lại xuất hiện, chu kỳ của mạng tinh thể của chúng là bao nhiêu (nếu chúng tuần hoàn), v.v.

Tất cả những điều trên cũng áp dụng cho các biểu đồ $c$ $f(x, y) = xy$ và $f(x, y) = x^2 - y^2$, với sự khác biệt là trong những hình này, chúng ta thấy các họ hyperbol.

Tóm lại, tôi xin chúc người đọc thành công với bài toán tương tác này, thử nghiệm với các $f(x, y)$ khác nhau, chẳng hạn như $x^3 + y^3$ hoặc arctg $(x + y)$.
