---
id: 1974-8-torondzhadze-bendukidze-krivyie-peano-507e9795
issue: kvant_1974_8
year: 1974
number: "8"
title: Đường cong đậu phộng
authors:
  - Торонджадзе М. С.
  - Бендукидзе А. Д.
rubric: osnovnye-stati
page_first: 15
page_last: 18
page_labels: 13-16
tag: 91QG
lang: vi
source: kvant_digital
extraction: vision
content_sha256: da8fd826aba0904a7855868246dc57c5393116ab0b3e51a65be726fe23beba97
prompt_sha256: draft-1
translated_from: content/ru/1974/08/articles/02_torondzhadze-bendukidze-krivyie-peano-507e9795.md
source_content_sha256: 423750f3ae5e5cd5c9c44df81889c8bddc1a9b852cf030a8ede0f1fdef7b3ffb
translation_model: draft
translation_run: vi-draft-2026-10-31
translation_quality: draft
---

⟦folio 13⟧

Từ ngày 26 tháng 3 đến ngày 30 tháng 3 năm 1974, hội nghị khoa học lần thứ hai của sinh viên Trường Trung học Nội trú Vật lý và Toán học Tbilisi mang tên V. M. Komarov đã diễn ra tại Tbilisi. Tại hội nghị này, nữ sinh người Georgia Medea Toronjadze đã đọc một báo cáo “Peano Curves”, được chuẩn bị dưới sự lãnh đạo của A.D. Bendukidze. Báo cáo được trình bày dưới dạng một bài báo mà chúng tôi trình bày để độc giả chú ý. Nó nói về cách một số đường nhất định được phân phối và về đường cong mà đường cong này phải được thay đổi. Bạn sẽ tìm thấy các đường được xác định cuối cùng (chính xác hơn là kích thước của tập hợp chính xác) trong bài viết của Viện sĩ P. S. Aleksandrov (xem trang 3).

Một dòng là gì?

Có lẽ, nhiều người trong số những người được hỏi câu hỏi này sẽ nhún vai bối rối và trả lời: "Đường nét? Vâng, rất đơn giản! Hãy chạy đầu bút chì được gọt sắc nét trên tờ giấy và bạn sẽ có được một đường kẻ."

Có vẻ như họ đúng, bởi vì khi nói về một đường thẳng, chúng ta thực sự tưởng tượng ra một thứ gì đó trông giống như một nét vẽ cao và mảnh, chẳng hạn như trên một tờ giấy.

Và họ sẽ không đúng! Lý do rất đơn giản: họ không được xác định mà phải xác định gợi ý về những gì nên được hiểu là một đường thẳng. Tuy nhiên, khó có thể đổ lỗi cho họ, vì việc đưa ra một định nghĩa toán học chính xác về một đường không phải là điều dễ dàng như thoạt nhìn. Các nhà toán học phải mất khoảng 2200 năm mới làm được điều này!

Người đầu tiên cố gắng xác định đường này là nhà toán học người Pháp René De-

Medea Toronjadze đọc báo cáo “Đường cong Peano” tại hội nghị sinh viên các trường nội trú vật lý và toán học ở Tbilisi

⟦folio 14⟧

tên của chúng thỏa mãn một số phương trình có dạng $F(x, y) = 0$.

Đây là một định nghĩa khá chung chung và tốt về các đường nét. Nó tốt ở chỗ nó có thể chuyển việc nghiên cứu các đường thẳng sang nghiên cứu phương trình $F(x, y) = 0$ xác định nó. Nhưng sau này hóa ra thường thì hàm $F(x, y)$ có dạng khá phức tạp.

Ví dụ: nếu một đường tròn có bán kính $R$ được cho bởi phương trình

$$x^2 + y^2 - R^2 = 0$$

(ở đây $F(x, y) = x^2 + y^2 - R^2$), thì đường xoắn ốc Archimedes không thể được xác định bằng một phương trình đơn giản như vậy. Đường xoắn ốc Archimedes là một đường cong được mô tả bởi một điểm chuyển động đều dọc theo một tia, đồng thời điểm này quay đều quanh một điểm cố định (Hình 1). Đường cong này dễ nghiên cứu về mặt hình học hơn mà không cần dùng đến phương trình.

Định nghĩa của Descartes còn có một nhược điểm nữa: nếu bạn không áp đặt bất kỳ hạn chế nào lên dạng của hàm $F(x, y)$, thì bất kỳ tập hợp nào trên mặt phẳng theo Descartes đều là tuyến tính (chỉ cần định nghĩa hàm $F(x, y)$ như sau: trên một tập hợp các cặp $(x, y)$ cho trước, hàm này bằng 0, tại tất cả các điểm khác của mặt phẳng $F(x, y) = 1$). Ví dụ, một hình vuông theo Descartes là một “đường thẳng”, nó được cho bởi phương trình

$$|x| + |x-1| + |y| + |y-1| - 2 = 0$$

đây là chức năng

$$F(x, y) = |x| + |x-1| + |y| + |y-1| - 2$$

tiếp tục liên tục!

Vào nửa sau thế kỷ 19, một nhà toán học người Pháp khác, Camille Jordan (1838–1922), đã phát triển khái niệm đường thẳng do Descartes đề xuất. Jordan định nghĩa đường phẳng là tập hợp các điểm trong mặt phẳng có tọa độ là $x$ và $y$ cho bởi các phương trình

$$x = \varphi(t), y = \psi(t)$$

food $\varphi(t)$ và $\psi(t)$ là các hàm liên tục trên khoảng [0, 1].

Hình 1.

Bây giờ phương pháp xác định đường này được gọi là tham số (với tham số $t$).

Ví dụ: phương trình tham số của đường tròn bán kính $R$ là

$$x = R \cos 2\pi t, \quad y = R \sin 2\pi t.$$

Đường xoắn ốc Archimedes (chính xác hơn là một phần của nó) được cho bởi các phương trình đơn giản

$$x = vt \cos \omega t, \quad y = vt \sin \omega t.$$

Đôi khi, dường như cuối cùng người ta đã tìm ra một định nghĩa thành công về đường thẳng, trong đó hình vuông chắc chắn sẽ không rơi vào “đường thẳng”. Cho dù nó thế nào đi chăng nữa!

Năm 1890, nhà toán học người Ý Giuseppe Peano (1858-1932) đã xây dựng một ví dụ về đường cong chạy quanh tất cả các điểm của hình vuông, đồng thời thỏa mãn định nghĩa về đường thẳng của Jordan! Sau đó, các ví dụ khác về những “đường” tương tự đã được tìm thấy. Bây giờ các “đường” còn được gọi là “đường cong Peano”. Chúng tôi sẽ trình bày cách xây dựng một trong các đường cong Peano ở cuối bài viết.

Đường cong Peano cho thấy định nghĩa của Jordan quá rộng. Thật khó để xem xét một đường cong tuyến tính lấp đầy toàn bộ hình vuông. Đồng thời, nó quá hẹp - về cơ bản là Linney, nó không phù hợp với định nghĩa này.

⟦folio 15⟧

Vậy tench là gì? Trong trường hợp đường thẳng, câu trả lời đáp số cuối cùng cho câu hỏi này được đưa ra bởi một trong những nhà toán học vĩ đại nhất cuối thế kỷ 19 - đầu thế kỷ 20, Georg Cantor (1845-1918). Không dừng lại ở việc xây dựng chính xác định nghĩa này, chúng tôi trình bày một ví dụ thú vị về các cantor đường thẳng, được xây dựng bởi người dùng nổi tiếng Waszlaw Sierpinski.

Hãy lấy một hình vuông. Hãy chia nó thành hai hình vuông tắc nghẽn và loại bỏ các điểm bên trong của hình vuông trung tâm khỏi nó. Chúng tôi chia mỗi hình trong số tám hình vuông còn lại thành hai hình vuông tắc nghẽn và trong mỗi hình vuông đó, chúng tôi lại loại bỏ các điểm bên trong của hình vuông trung tâm. Tiếp tục quá trình này vô thời hạn, chúng ta sẽ thu được giá trị cần thiết. Nó được gọi là tấm thảm Sierpinski (trang đầu tiên của trang bìa hiển thị hình vẽ thu được khi chế tạo tấm thảm Sierpinski sau bước thứ ba). Xin lưu ý rằng cho dù các điểm còn lại (tấm thảm Sierpinski) gần đến mức nào thì vẫn có một điểm bị ném ra khỏi hình vuông ban đầu.

Vào những năm 20 của thế kỷ chúng ta, nhà toán học tài năng P. S. Uryso đã khái quát định nghĩa của Cantor và đưa ra định nghĩa chung về các đường *).

Xây dựng đường cong Peano

1. Gọi σ là đoạn đơn vị [0,1]. Hãy chia nó thành bốn phân đoạn tắc nghẽn:

$$\sigma_{1}^{(1)} = \left[ 0, \frac{1}{4} \right], \quad \sigma_{2}^{(1)} = \left[ \frac{1}{4}, \frac{1}{2} \right], \quad \sigma_{3}^{(1)} = \left[ \frac{1}{2}, \frac{3}{4} \right], \quad \sigma_{4}^{(1)} = \left[ \frac{3}{4}, 1 \right].$$

*) Điều này được mô tả chi tiết trong bài viết của Viện sĩ P. S. Alexandrov “Pavel Samulovich Uryson” (xem trang 3). Xem thêm A. S. Parkhomenko “Đường là gì”, M., Gostekhidat, 1954.

Hãy gọi những phân đoạn này là phân đoạn của lần chạy đầu tiên. Chia mỗi đoạn thành bốn đoạn tắc nghẽn, chúng ta thu được 16 đoạn của lần chạy thứ hai $\sigma_{i}^{(2)}$ ($i = 1, 2, \dots, 16$). Tiếp tục quá trình phân chia, chúng ta thu được các đoạn vết thương thứ ba, thứ tư và lớn. Trong trường hợp này, các đoạn của vết thương thứ $r$ sẽ trông như sau:

$$\sigma_{i}^{(r)} = \left[ \frac{i - 1}{4^r}, \frac{i}{4^r} \right] \quad (i = 1, 2, \dots, 4^r).$$

Bây giờ chúng ta hãy lấy một số điểm $t_0 \in \sigma$.

Nếu nó không trùng với điểm phân chia nào thì có đúng một đoạn của mỗi vết thương chứa nó. Hãy để $\sigma_{i}^{(1)}, \sigma_{i}^{(2)}, \sigma_{i}^{(3)}, \dots$ như thế. Chúng ta hãy ứng với điểm $t_0$ bằng một dãy vô hạn các số tự nhiên $i_1, i_2, i_3, \dots$ và viết nó như sau:

$$t_0 = (i_1, i_2, i_3, \dots).$$

Ví dụ. $1/3 = (2, 6, 22, 85, \dots)$.

Nếu điểm $t_0$ trùng với bất kỳ điểm phân chia nào, tức là có dạng $m/4^n$, thì bắt đầu từ các đoạn của vết thương thứ $n$ nó sẽ chứa hai đoạn liền kề của mỗi vết thương. Chúng ta hãy liên kết với nó hai dãy số tự nhiên ($i_1, i_2, i_3, \dots$), trong đó $1 \leq i_1 \leq 4$, $4i_k - 3 \leq i_{k+1} \leq 4i_k$. Ngược lại, mỗi chuỗi như vậy xác định một điểm duy nhất của đoạn $\sigma$ (chứng minh điều đó!).

2. Chúng ta hãy thực hiện một cách xây dựng tương tự cho hình vuông đơn vị Q. Chia nó thành bốn hình vuông tắc nghẽn, chúng ta thu được các bình phương của lần chạy đầu tiên: $Q_{1}^{(1)}, Q_{2}^{(1)}, Q_{3}^{(1)}, Q_{4}^{(1)}$. Chia mỗi ô vuông này thành bốn ô vuông tắc nghẽn sẽ cho ra ô vuông rana thứ hai, v.v. Nói chung, chia mỗi ô vuông của lần chạy thứ $r$ $Q_{i}^{(r)}$ thành bốn ô tắc nghẽn sẽ mang lại bốn ô vuông của lần chạy thứ $(r+1)$: $Q_{4i+1}^{(r+1)}, Q_{4i+1}^{(r+1)}, Q_{4i+1}^{(r+1)}, Q_{4i+1}^{(r+1)}$ ($i = 1, 2, \dots, 4^r$). Ta đánh số các ô vuông sao cho:

1) ô vuông đầu tiên của bất kỳ lần chạy nào đều chứa điểm (0, 0);

2) có thể từ hình vuông $Q_{i}^{(r)}$ bỏ qua hình vuông liên tiếp $Q_{4i+1}^{(r+1)}, Q_{4i+1}^{(r+1)}, Q_{4i+1}^{(r+1)}, Q_{4i+1}^{(r+1)}$ và thoát ra trong hình vuông $Q_{i+1}^{(r)}$, chỉ giao nhau với các cạnh (chứ không phải các đỉnh!) của hình vuông rana $(r+1)$.

⟦folio 16⟧

Hình 2.

Chúng tôi mời người đọc chứng minh rằng việc đánh số như vậy luôn có thể thực hiện được. Hình 2 cho thấy các ô vuông của ba hàng đầu tiên, với đường đứt nét màu đỏ biểu thị đường đi dọc theo các ô vuông được đánh số (bắt đầu từ ô vuông phía dưới bên trái).

Tiếp tục lý luận, chúng tôi tin rằng với mỗi điểm $(x_0, y_0)$ hình vuông $Q$ có thể được gán cho một hoặc một số (bao nhiêu?) dãy số tự nhiên, chúng tôi viết nó như thế này:

$$(x_0, y_0) = [i_1, i_2, i_3, \dots]$$
$$(1 \leq i_1 \leq 4, 4i_k - 3 \leq i_k + 1 \leq 4i_k).$$

Ví dụ: $(1/3, 1/3) = [1, 3, 9, \dots]$;
$(1/2, 1/3) = [1, 3, 10, \dots] = [1, 14, 56, \dots]$;
$(1/2, 1/2) = [1, 3, 11, \dots] = [2, 8, 32, \dots] = [3, 9, 33, \dots] = [4, 14, 54, \dots].$

Và ở đây chúng ta có thể chứng minh rằng mỗi chuỗi như vậy xác định một điểm duy nhất $(x_0, y_0)$ từ $Q$.

3. Viết các điểm của đoạn $\sigma$ và hình vuông $Q$ dưới dạng chuỗi vô hạn các số tự nhiên giúp có thể ánh xạ $\sigma$ lên $Q$.

Thật vậy, đường đi $t_0$ là một điểm tùy ý $\sigma$ và

$$t_0 = (i_1, i_2, i_3, \dots).$$

Chuỗi cuối cùng xác định duy nhất điểm $(x_0, y_0)$, tương ứng với chuỗi $[i_1, i_2, i_3, \dots]$. Ngay cả khi $t_0$ được biểu thị dưới dạng hai chuỗi thì cả hai chuỗi đều dẫn đến cùng một điểm $(x_0, y_0)$. Điều này dễ chứng minh nếu chúng ta tính đến độ dài các cạnh của hình vuông có xu hướng bằng 0 khi thứ hạng của chúng tăng lên. Vì vậy, mỗi $t_0$ tương ứng với một $(x_0, y_0)$.

Bây giờ, đặt điểm $(x_0, y_0) \in Q$ là tùy ý và $[i_1, i_2, i_3, \dots]$ là một trong những biểu diễn của điểm này. Lấy $t_0 = (i_1, i_2, i_3, \dots)$, chúng tôi đảm bảo rằng trong ánh xạ của mình, mỗi điểm của hình vuông $Q$ tương ứng với ít nhất một điểm của đoạn $\sigma$. Điều này có nghĩa là $\sigma$ được ánh xạ tới $Q$. Lưu ý rằng ánh xạ này không phải là ánh xạ một-một; không ánh xạ $Q$ tương ứng với hai, những điểm đó hoặc thậm chí bốn điểm $\sigma$.
