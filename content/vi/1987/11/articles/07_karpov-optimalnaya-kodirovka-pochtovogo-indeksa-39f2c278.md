---
id: 1987-11-karpov-optimalnaya-kodirovka-pochtovogo-indeksa-39f2c278
issue: kvant_1987_11
year: 1987
number: "11"
title: Mã hóa mã bưu chính tối ưu
authors:
  - Карпов Я. Ю.
rubric: raznoe
rubric_sub: Разное
page_first: 21
page_last: 22
page_labels: 19-20
tag: ZP92
lang: vi
source: kvant_digital
extraction: vision
content_sha256: 830ef92bb563a4bc79851c9591f456110eb9f8ed49c59a62fa040f86ca02dd9e
prompt_sha256: draft-1
translated_from: content/ru/1987/11/articles/07_karpov-optimalnaya-kodirovka-pochtovogo-indeksa-39f2c278.md
source_content_sha256: 22ed19f88d860a6aaf16e745685738177827c0d3f01589c2b372c13dd1a2bb88
translation_model: draft
translation_run: vi-draft-2026-10-31
translation_quality: draft
---

⟦folio 19⟧

TOÁN HỌC
CÔNG VIỆC CỦA TRẺ EM

Dưới đây là hai bài viết ngắn được viết bởi học sinh lớp 10 Yaroslav Karpov từ Leningrad (trường số 239) và Alexander Lobkovsky từ Chernogodovka, vùng Moscow (trường số 82) về các chủ đề hiện đại khác nhau. Chúng thống nhất với nhau bởi thực tế là cả hai bài báo đều là “toán học máy tính”: trong đó, lý luận toán học chỉ có thể thu được những quan sát thú vị sau khi kết nối với máy tính.

Mã hóa mã bưu chính tối ưu

Y. Y. KARPOV

Tôi phải đối mặt với một câu hỏi: tại sao chính xác bộ số này (hình 1) lại được sử dụng trên phong bì—xét cho cùng, những bảng mã này có thể được thay thế bằng những bảng mã khác. Hãy xem chúng ta có thể nghĩ ra bao nhiêu bộ khác nhau (Bảng 1). Tổng số 2×4×3×2×2×2×3×2=1152 tùy chọn.

Để hiển thị những bộ tốt nhất, trước tiên chúng ta phải chọn tiêu chí mà chúng ta sẽ so sánh các bộ đó. Như bạn đã biết, mã số sử dụng trên phong bì được kiểm tra bằng máy. Vì vậy, tiêu chí về tính tối ưu của một tập hợp phải chính xác là với tập hợp này máy sẽ mắc ít lỗi hơn trong việc sắp xếp so với các tập hợp khác.

Để mô tả các cách mã hóa khác nhau của các số, chúng tôi giới thiệu thuật ngữ - khoảng cách giữa hai bảng mã. Khoảng cách phải thỏa mãn các điều kiện sau:

1) Khoảng cách giữa hai bảng mã càng lớn thì khả năng máy sẽ nhầm lẫn bảng mã này với bảng mã khác càng ít.

2) Khoảng cách từ mã hóa $A$ đến mã hóa $B$ phải bằng khoảng cách từ mã hóa $B$ đến mã hóa $A$.

Những điều kiện này thỏa mãn khoảng cách Hamming. Trong trường hợp của chúng tôi, đây là số lượng ký tự “không khớp” trong bảng mã, tức là số lượng ký tự không khớp.

Ví dụ: Tìm khoảng cách giữa bảng mã 5 ​​và 2 (hình 2). Khoảng cách giữa các bảng mã này là 5, vì các bảng mã này có 5 ô không khớp.

Chúng ta hãy biểu thị bằng $p$ xác suất lỗi cơ bản, tức là xác suất để máy nhầm que với “chống dính” hoặc ngược lại. Khi đó xác suất nhận đúng một cây gậy là $1-p$.

Ví dụ: chúng ta hãy tìm xác suất chấp nhận số 6 là 0 (hình 3). Để làm được điều này, máy cần hiểu chính xác 8 que và hai khoảng trống và một que được chấp nhận là khoảng trống. Xác suất của sự kiện này là $p(1-p)^{8}$.

Nói chung, với khoảng cách tự động của bất kỳ chữ số nào, xác suất để chữ số này bị nhầm với chữ số khác là bằng $p^{\gamma}(1-p)^{\alpha-\gamma}$, trong đó $\gamma$ là khoảng cách giữa hai bảng mã Hamming này.

Với khoảng cách tự động của một chữ số cụ thể $i$, xác suất nó bị nhầm với bất kỳ chữ số nào khác là bằng

$$\sum_{j=i}^{n} p^{\gamma,j}(1-p)^{n-\gamma},$$

trong đó $r_{i,j}$ là khoảng cách giữa các chữ số $i$ và $j$.

⟦folio 20⟧

Giả sử rằng tất cả các số đều xuất hiện như nhau ở bất kỳ vị trí nào. Khi đó xác suất trung bình của việc nhận dạng sai một chữ số là bằng

$$P = \frac{1}{10} \sum_{i=0}^{9} \sum_{j=0}^{p_{j,i,j}} (1-p)^{9-r_{j,i,j}}.$$

Chúng ta sẽ sử dụng độ tin cậy này làm tiêu chí cho chất lượng của bộ: nó càng thấp thì bộ càng “tốt”.

Bảng liệt kê tất cả 1152 tùy chọn mã dựa trên tiêu chí này được lấy trên máy tính ES-1035. Chương trình tìm kiếm được viết bằng Fortran. Trong chương trình, tất cả các biến thể của bản ghi chữ số được mã hóa dưới dạng mảng gồm 1 và 0, theo nguyên tắc sau (hình 4): nếu trong bản ghi chữ số có một que ở một vị trí nhất định, thì khi mã hóa ở vị trí có số được chỉ ra trong sơ đồ, 1 sẽ được viết, nếu không thì 0.

Ví dụ: Hãy mã hóa số 2, cho ở dạng tổng quát (như trên phong bì):

$$0, 1, 0, 0, 1, 1, 0, 0, 1.$$

Các tùy chọn mã hóa cho số $i$ được viết trong ma trận $ki$, trong đó số hàng là 9 và số cột trùng với số lượng tùy chọn mã hóa.

Đối với mỗi giá trị của xác suất lỗi cơ bản $p$, tất cả 1152 biến thể của bộ đã được sắp xếp, chất lượng của chúng được đánh giá bằng công thức (*) và những biến thể tốt nhất và tốt thứ hai đã được chọn. Để làm điều này, một ma trận khoảng cách được hình thành cho mỗi tập hợp, được rút ra từ tập hợp tốt nhất. Vì mỗi mã hóa 8 và 0 chỉ có một tùy chọn nên các số này không được sắp xếp thông suốt và không tham gia vào đầu ra.

Các kết quả sau đây đã thu được. Với mức độ tin cậy của sai số cơ bản trong

$$0 < p \leq 0,3$$

Mã hóa thực tế hóa ra giống với mã được sử dụng trên phong bì (xem hình 1). Vì xác suất lỗi thực tế của máy nhận dạng ở bưu điện hiển nhiên nằm trong giới hạn này nên bộ này là quan trọng nhất.

Chất lượng tốt thứ hai trong phạm vi này là bộ được hiển thị ở hình 5. Bộ thứ hai chỉ khác với bộ thứ nhất ở hai chỗ và xác suất xảy ra lỗi với bộ này không lớn hơn nhiều so với bộ tốt nhất.

Tại $p=0,4$ các bộ này được hoán đổi.

Khi độ tin cậy tăng lên 0,5, tất cả các độ tin cậy đều bằng nhau, do đó rất có thể tất cả các bộ sẽ trở nên giống nhau.

Tất nhiên, tôi sẽ chấp nhận nếu chương trình của tôi xác định được một bộ khác với bộ được chấp nhận tại bưu điện: khi đó tôi có thể đề nghị thay thế bộ được chấp nhận bằng bộ của tôi - một bộ tốt hơn.

Than ôi! Có lẽ, khi bộ tối ưu được chọn ở bưu điện, việc tối ưu hóa bài toán cũng được quyết định giống như tôi đã làm.

Biên tập. Kèm theo các tài liệu được xuất bản ở trên, Y. Karpov đã đính kèm bản in của chương trình (ở Fortran) thực hiện các thuật toán được mô tả trong bài viết. Các bản in đưa ra ý tưởng về văn hóa lập trình khá cao của tác giả bài viết. Họ có những lời nhận xét rõ ràng để làm cho chương trình dễ đọc. Tuy nhiên, việc thiếu không gian cũng như sự lựa chọn ngôn ngữ không may (Fortran không được đưa vào khóa học khoa học máy tính của trường) không cho phép chúng tôi xuất bản phần tài liệu này.

Chúng tôi yêu cầu tác giả của các bài viết dành cho việc sử dụng máy tính tìm kiếm danh sách của họ; Điều mong muốn là các chương trình được viết bằng BASIC (hoặc Rappa).
