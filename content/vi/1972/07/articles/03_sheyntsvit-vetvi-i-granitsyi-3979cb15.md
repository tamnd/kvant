---
id: 1972-7-sheyntsvit-vetvi-i-granitsyi-3979cb15
issue: kvant_1972_7
year: 1972
number: "7"
title: Các nhánh và biên giới
authors:
  - Шейнцвит Р. П.
rubric: osnovnye-stati
page_first: 4
page_last: 7
page_labels: 2-5
tag: UYY0
lang: vi
source: kvant_digital
extraction: vision
content_sha256: 74a7beedb2606b1db05df7246ad86f88edb9fa9a04c17f49b69aaa058e023f6f
prompt_sha256: draft-1
translated_from: content/ru/1972/07/articles/03_sheyntsvit-vetvi-i-granitsyi-3979cb15.md
source_content_sha256: 84a63476d5da6d1143a407c48216cd6dd6f4ec0ec90dfca96f0ea51a5f2681a9
translation_model: draft
translation_run: vi-draft-2026-10-31
translation_quality: draft
---

⟦folio 2⟧

Hãy xem xét bài toán:
Có những mặt hàng trong kho (chẳng hạn như
dy - mỗi lần một cái), trọng lượng và chi phí
được chỉ ra trong bảng.

| Số seri | trọng lượng tính bằng cent-
nerah | Giá
(bằng rúp) |
| :--- | :--- | :--- |
| 1 | 11 | 120 |
| 2 | 7 | 140 |
| 3 | 6 | 60 |
| 4 | 5 | 80 |
| 5 | 12 | 160 |
| 6 | 9 | 110 |
| Tổng cộng | 50 | 670 |

Khả năng tải tự động là 3200 kk. Giá trị tối đa là bắt buộc để tổng giá trị của các mục được lấy càng cao càng tốt.

Rõ ràng, sẽ có lợi hơn nếu lấy những món đồ có trọng lượng nhẹ và giá trị cao.

Hãy để chúng tôi giới thiệu khái niệm đơn giá của một mặt hàng $d_i$, tức là giá của một tâm của mặt hàng $i$ tính bằng rúp: $d_1=10,9$; $d_2=20$; $d_3=10$; $d_4=16$; $d_5=13,3$; $d_6=12,2$.

Nếu bạn tải vào máy tự động các vật phẩm có giá trị cụ thể nhất - thứ hai, thứ tư, thứ năm và thứ sáu - thì tổng trọng lượng của chúng sẽ lớn hơn khả năng tải tự động ($7+15+12+9>32$).

Nếu chỉ lấy đồ thứ 2, thứ 4, thứ 5 thì xe bị thiếu tải 8 kk. Sau đó, bạn chỉ có thể chất thêm một món đồ thứ 3 nữa và tổng chi phí sẽ là 440 rúp, và xe sẽ bị thiếu tải 2 kk. Bạn có thể chắc chắn rằng không có cách nào tốt hơn để tải máy không?

Có thể sẽ có lợi hơn nếu để lại một trong những hạng mục có đơn giá cao hơn, nhưng liệu nó có làm tăng chi phí tổng thể khi sử dụng hết khả năng chuyên chở của máy không?

Như bạn có thể thấy, “yêu” bài toán rất khó giải quyết. Nhưng trong điều kiện thực tế, khi vấn đề thường không phải là về sáu mà là khoảng sáu mươi đối tượng, thì không thể giải quyết được nếu không được trang bị các phương pháp toán học. Hãy dịch bài toán sang ngôn ngữ toán học (như người ta nói, chúng tôi toán học hóa tình huống). Đặt $x_i=1$ nếu vật thứ $i$ được nhúng vào máy tự động và $x_i=0$ nếu không ($i=1, \dots, 6$). Khi đó, tổng giá trị của các vật phẩm được nạp tính bằng rúp là 120 $x_1+140 x_2+60 x_3+80 x_4+160 x_5+110 x_6$ và tổng trọng lượng của chúng tính bằng cent là 11 $x_1+7 x_2+6 x_3+5 x_4+12 x_5+9 x_6$.

Vì vậy, trừu tượng hóa từ tình huống “đời sống”, ta thu được số toán học bài toán: tìm các giá trị

⟦folio 3⟧

các biến $x_1, \dots, x_6$ (có thể là 0 hoặc 1), trong đó hàm
$$f(x_1, \dots, x_6) = 120x_1 + 140x_2 + 60x_3 + 80x_4 + 160x_5 + 110x_6$$
đạt đến mức tối đa nếu điều kiện (ràng buộc) được đáp ứng
$$11x_1 + 7x_2 + 6x_3 + 5x_4 + 12x_5 + 9x_6 \leq 32.$$ (1)

Hàm $f$ được gọi là hàm mục tiêu bài toán; nó được định nghĩa là tập hợp tất cả sáu số 0 và số 1 theo thứ tự (vectơ istime, mỗi thành phần của nó bằng 0 hoặc 1).

Tổng cộng, có $2^6 = 64$ vectơ như vậy và mỗi vectơ cung cấp một số cách để tải tự động hóa. Nhưng không phải phương thức tải nào trong số 64 phương thức tải này đều được chấp nhận: vector $(1,0,1,0,1,1)$ tương ứng với việc tải các mục thứ 1, 3, 5 và 6 vào máy, chỉ có tổng trọng lượng của chúng $(38 \mu)$ vượt quá giới hạn cho phép.

Việc gọi một vectơ là có thể chấp nhận được là điều đương nhiên nếu điều kiện (1) được thỏa mãn. Vì vậy, nghiệm bài toán là một vectơ khả thi giúp cực đại hóa hàm mục tiêu $f$.

Bây giờ giả sử mục đầu tiên được tải vào tự động hóa. Sau đó, $x_1 = 1$ và chúng tôi nhận được bài toán mới:

Tên của các biến $x_2, \dots, x_6^*)$ mà hàm tối đa $f_2(x_2, x_3, \dots, x_6) = 140x_2 + 60x_3 + 80x_4 + 160x_5 + 110x_6$ là đủ với điều kiện $7x_2 + 6x_3 + 5x_4 + 12x_5 + 9x_6 \leq 32$.

Nếu vật thứ 1 không được nhúng chìm, thì $x_1 = 0$ và chúng ta nhận được bài toán:

Tên của các biến $x_2, \dots, x_6$ làm cực đại hóa hàm $f(x_2, \dots, x_6) = 140x_2 + 60x_3 + 80x_4 + 160x_5 + 110x_6$ tuân theo điều kiện $7x_2 + 6x_3 + 5x_4 + 12x_5 + 9x_6 \leq 32$.

*) Các điều kiện $x_i = 0$ hoặc 1, được giả định trong toàn bộ chỉ số, chúng tôi không bị giới hạn cụ thể trong tương lai.

Do đó, một bài toán có 6 biến có thể rút gọn thành hai bài toán có 5 biến; những điều này lần lượt rút gọn thành bốn bài toán với 4 biến, v.v., để cuối cùng chúng ta nhận được 64 bài toán với mỗi bài một biến. Nhưng nếu cần phải giải một hệ thống như vậy, thì quá trình không biểu diễn là kiểm tra các điều kiện (1) cho mỗi trong số 64 vectơ có thể, đối với các vectơ có thể chấp nhận được, tính giá trị của hàm mục tiêu và chọn vectơ có giá trị lớn nhất, tức là, như người ta nói, giải bài toán “bằng cách tìm kiếm toàn diện”.

Nhưng còn trong trường hợp số lượng đối tượng (thành phần vectơ) lớn thì sao? Rốt cuộc, ngay cả với 20 món đồ, số lượng lựa chọn có thể vượt quá một triệu! Rõ ràng là phương pháp tìm kiếm toàn diện trong các bài toán thuộc loại này không phù hợp với hầu hết các ứng dụng.

Bây giờ chúng ta sẽ nói về một phương pháp cho phép, theo quy luật, giảm đáng kể số lượng các tùy chọn so sánh cần thiết để đạt được lời giải. Chúng tôi sẽ mô tả phương pháp này, được gọi là “phương pháp nhánh và giới hạn”, khi chúng tôi áp dụng nó cho bài toán của mình.

Quá trình chọn các mục để tải vào máy tự động có thể được mô tả dưới dạng biểu đồ $\textcircled{2}$ $^*$). Nút bắt đầu 0 tương ứng với tập $P$ của tất cả 64 vectơ tối đa. Từ nút

*) Xem bài viết của M. I. Bashmkov. "Mạng lưới so khớp và chuyển đổi" ở vị trí thứ 4 «Kvant» cho năm 1970. Tuy nhiên, những gì tiếp theo sẽ rõ ràng đối với những ai chưa đọc trang này.

⟦folio 4⟧

0 bắt đầu thẳng hàng với nút 1 và 2 (Hình 1). Nút 1 nằm ở bên phải và bên dưới nút 0. Nó tương ứng với các phương thức tải trong đó đối tượng thứ nhất nhất thiết phải được tải vào máy. Rõ ràng, nút 1 tương ứng với tập hợp con $P_1$ trong số 32 vectơ từ $P$ có $x_1=1$. Nút 2 nằm ở bên trái và bên dưới nút 0 và tương ứng với tập hợp con $P_2$ trong số 32 vectơ từ $P$ có $x_1=0$. Việc xây dựng thêm biểu đồ là rõ ràng. Hình 1 hiển thị biểu đồ sau hai bước phân nhánh.

Mỗi nút của biểu đồ tương ứng với một tập hợp con các vectơ từ $P$, có các thành phần không xoắn đã được cố định. Nếu việc xây dựng tập $P_1$ và $P_2$ được coi là bước phân nhánh đầu tiên (cấp đầu tiên của biểu đồ), thì ở bước $k$th ($k$cấp của biểu đồ), chúng ta sẽ nhận được $2^k$ nút, mỗi nút tương ứng với một tập hợp vectơ $2^8-k$ (tùy chọn tải tự động hóa). Các nút thu được ở bước phân nhánh thứ sáu biểu thị mỗi vectơ một vectơ, sao cho giá trị trung bình của các nút này được cho trước. Vì vậy, nếu việc phân nhánh được thực hiện hoàn toàn, thì bạn sẽ phải xây dựng một biểu đồ với số nút $1+2+4+\dots+64=127$.

Nhưng chúng tôi sẽ cố gắng hành động theo cách để phát hiện đồng thời các nút “không có triển vọng” mà từ đó các nhánh dẫn đến lời giải không thể xuất hiện. Chúng ta “cắt bỏ” những cành này càng sớm (cao), thì sau này chúng ta sẽ phải làm ít bạo lực hơn. Với mục đích này, chúng tôi gán 2 số cho mỗi nút (chúng tôi sẽ viết số này bên dưới nút). Phần trên cùng hiển thị tổng chi phí cao nhất có thể có (chi phí eranza) của các mặt hàng được lấy cho bất kỳ phương thức tải nào, được mô tả bằng vectơ của nút này. Con số bên dưới cho biết tổng số mục được phép dùng chung ở bước này là bao nhiêu (con số này bằng chênh lệch giữa khả năng chuyên chở của tự động hóa và trọng lượng của tất cả các mục đã được tải). Ví dụ: hãy tìm phần trên và phần dưới

Các số cho nút thứ nhất. Vì trong tất cả các tùy chọn tải tương ứng, mục đầu tiên nhất thiết phải được sử dụng nên số thấp hơn ở bước này là $32-11=21$. Ranh giới đang được xây dựng (số trên) bằng tổng của tất cả các đối tượng đang được xây dựng, vì chúng tôi vẫn chưa loại trừ khả năng chọn bất kỳ đối tượng nào trong số chúng. Do đó, số trên của nút thứ 1 là 670. Đối với nút thứ hai, số trên là 550 (670-120), vì mục đầu tiên không được lấy: số dưới ở đây là 32.

Gọi $P_i$ là trọng lượng của vật phẩm thứ $i$, $C_i$ giá của nó. Rõ ràng là khi di chuyển từ bất kỳ nút nào nằm ở cấp độ $i$ của biểu đồ, số trên không thay đổi và số dưới giảm $P_{i+1}$, trong khi khi di chuyển từ nút này sang trái, số dưới không thay đổi và số trên giảm $C_{i+1}$. Ở mỗi giai đoạn, chúng tôi sẽ xác định nút có số trên cùng là số nguyên nhất. Nếu hai nút có cùng số trên thì chúng ta sẽ chọn nút có số thấp hơn. Nếu trong quá trình phân nhánh, gặp phải một nút có số âm thấp hơn, điều này có nghĩa là với các phương thức tải tương ứng với nút này, quá trình tự động hóa sẽ bị quá tải và việc phân nhánh một nút như vậy không có ý nghĩa gì. Bằng cách phân nhánh theo phương pháp đã chỉ định, chúng ta sẽ đến một nút nằm ở cấp độ thứ sáu cuối cùng của biểu đồ, với số thấp hơn không âm.

Nút này tương ứng với một số phương pháp tải có thể chấp nhận được trong đó giá trị của hàm mục tiêu bằng số trên. Tất cả các nút không được phân nhánh có ít hơn nút này đều không có ý nghĩa đối với phân nhánh, vì số trên cùng không thể tăng khi phân nhánh. Có thể số trên cùng của nút được tìm thấy lớn hơn số của bất kỳ nút nào khác. Sau đó, nút này cho lời giải bài toán. Hình 2 cho thấy biểu đồ cuối cùng.

Việc xây dựng biểu đồ sẽ tiếp tục trong các giai đoạn sau (các con số sẽ giúp bạn làm quen

⟦folio 5⟧

số nút):

1) 0→1→3→5→7→9; 2) 6→11→13; 3) 8→15; 4) 2→17→19→21→23→25; 5) 12→27→29; 6) 4→31→33→35; 7) 10→37; 8) 20→39→41→43; 9) 22→45→47; 10) 32→49→51→53; 11) 14→55; 12) 34→57→59.

Việc phân nhánh thêm là vô ích vì nút 55 nằm ở cấp độ cuối cùng của biểu đồ và có số lượng cao nhất. Nút này cung cấp lời giải bài toán. Nó tương ứng với vectơ (1,1,0,1,0,1): bạn cần tải mục thứ 1, thứ 2, thứ 4 và thứ 6 vào máy. Trong trường hợp này, tổng chi phí (tối đa của hàm mục tiêu) là 450 rúp.

Trong quá trình xây dựng đồ thị, có trên 50% phương án không hứa hẹn đã bị “cắt bỏ”. Khi số lượng biến tăng lên, tỷ lệ các lựa chọn như vậy thường tăng lên.

Ngoài ra, quy trình có thể sử dụng phương pháp được mô tả cho lời giải tương tự như bài toán. Tất nhiên, bài toán của chúng tôi khá đơn giản: chỉ có 2 nhánh đi ra từ mỗi nút và không khó để tìm ra ranh giới (số trên và số dưới). Trong các bài toán khác, quá trình phân nhánh và giới hạn có thể phức tạp hơn và phụ thuộc vào kỹ năng cũng như trí thông minh của người giải nó. Đối với cường độ lao động của chính quy trình, các máy thực thi điện tử sẽ giải quyết. Những vấn đề như đang được xem xét thường được gọi là “vấn đề về ba lô” (thay súng máy bằng ba lô du lịch và khả năng mang theo của nó với khả năng mang theo tối đa của một khách du lịch đóng gói và đưa ra lựa chọn khó khăn trong số những món đồ “hoàn toàn cần thiết”).

Tất nhiên, bài toán những điều này không chỉ phải được quyết định trước kỳ nghỉ hoặc kỳ nghỉ. Xét cho cùng, việc lập kế hoạch hàng năm cho doanh nghiệp trong nhiều trường hợp cũng giống như bài toán về một chiếc ba lô. Rõ ràng là phương pháp phân nhánh và ràng buộc “có tác dụng” trong nhiều vấn đề lập kế hoạch kinh tế có tầm quan trọng lớn hơn đối với nền kinh tế quốc gia.
