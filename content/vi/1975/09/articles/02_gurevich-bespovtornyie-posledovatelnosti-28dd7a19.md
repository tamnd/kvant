---
id: 1975-9-gurevich-bespovtornyie-posledovatelnosti-28dd7a19
issue: kvant_1975_9
year: 1975
number: "9"
title: Trình tự lặp lại
authors:
  - Гуревич Г. А.
rubric: osnovnye-stati
page_first: 9
page_last: 13
page_labels: 7-11
tag: 5QQU
lang: vi
source: kvant_digital
extraction: vision
content_sha256: e80302f4c6472bea7357acfdfc44a6a1418200b2e09a22c2ed8d4472979dd24a
prompt_sha256: draft-1
translated_from: content/ru/1975/09/articles/02_gurevich-bespovtornyie-posledovatelnosti-28dd7a19.md
source_content_sha256: c20b40cfe6d2c2e1647a77273c630894a3a97f856a7c97d8866bffdb3573ee28
translation_model: draft
translation_run: vi-draft-2026-10-31
translation_quality: draft
---

⟦folio 7⟧

Trình tự lặp lại

G. A. Gurevich

Trình tự Arshon

Hãy gọi một chuỗi các chữ số là *chuỗi lặp lại* nếu nó chứa ít nhất một cặp nhóm chữ số giống hệt nhau. Ví dụ: các chuỗi 1, 2, 3, 4, 2, 3, 4, 2, 1 và 1, 2, 2, 7, 6, 2, 7, 6, 8 được lặp lại, nhưng các chuỗi 4, 2, 1, 2, 3, 4, 2, 3 và 3, 2, 3, 1, 2, 7 không được lặp lại. Chúng ta sẽ gọi các chuỗi không lặp lại là *không lặp lại*. Đặt B(n) biểu thị tập hợp các chuỗi có độ dài n và |B(n)| - số của họ.

Bằng trực giác thì rõ ràng: dãy số càng dài thì càng có nhiều khả năng nó chứa hai nhóm số giống hệt nhau đứng cạnh nhau. Và trên thực tế, nếu bạn viết ra một chuỗi đủ dài một cách khoa học thì rất có thể chuỗi này sẽ được lặp lại.

Hãy để chúng tôi cung cấp cho tuyên bố này một ý nghĩa chính xác.

Bài 1. Chứng minh rằng với mọi số ε > 0, có thể xác định n sao cho trong số tất cả các chuỗi có độ dài n thì tỷ lệ các chuỗi không lặp lại sẽ nhỏ hơn ε, tức là $$\frac{|\text{Б}(n)|}{10^n} < \varepsilon.$$

Dễ dàng chứng minh rằng mọi dãy có độ dài lớn hơn ba, gồm hai chữ số 1 và 2, đều lặp lại.

Tuy nhiên, từ ba chữ số khác nhau đã có thể tạo ra một chuỗi góc cạnh, không lặp lại.

Thực tế này đã được chứng minh vào năm 1937 bởi nhà toán học Liên Xô S. E. Arshon, người đã đề xuất một phương pháp quy nạp để xây dựng các chuỗi không lặp lại như sau.

Chúng ta hãy biểu thị bằng $K_1$ chuỗi không lặp lại 1, 2, 3. Giả sử rằng chuỗi không lặp lại $K_n$ đã được xây dựng. Trình tự $K_{n+1}$ thu được từ nó như thế này.

Nếu số $n+1$ là số chẵn và vị trí thứ $n+1$ trong dãy $K_n$ là 1 thì dãy $K_n$ được gán một bộ ba chữ số 3, 2, 1; nếu nó có giá 2 thì bộ ba là 1, 3, 2; nếu nó có giá 3 thì bộ ba là 2, 1, 3.

Nếu số $n+1$ là số lẻ và vị trí thứ $n+1$ trong dãy $K_n$ là 1 thì bộ ba 1, 2, 3 sẽ được thêm vào dãy $K_n$; nếu nó có giá 2 thì bộ ba là 2, 3, 1; nếu nó có giá 3 thì bộ ba là 3, 1, 2.

Một phần,

$$K_2 = 1, 2, 3, 1, 3, 2$$
($n = 2$ là số chẵn và vị trí thứ hai trong $K_1$ là 2),

$$K_3 = 1, 2, 3, 1, 3, 2, 3, 1, 2, 3, 2, 1$$
($n = 3$ là số chẵn và vị trí thứ ba trong $K_2$ là 3),

$$K_4 = 1, 2, 3, 1, 3, 2, 3, 1, 2, 3, 2, 1$$
($n = 4$ là số chẵn và vị trí thứ tư trong $K_3$ là 1), v.v.

Bằng chứng về sự không lặp lại của các chuỗi thu được bằng phương pháp của Arshon là khá đáng tin cậy.

⟦folio 8⟧

Nó cồng kềnh và chúng tôi sẽ không trình bày ở đây *).

Bây giờ chúng ta hãy thử ước tính số $|B(n)|$ của các chuỗi không lặp lại có độ dài $n$ (gồm mười chữ số). Nếu chúng ta có thể chỉ ra rằng với bất kỳ số nguyên dương nào $n$ thì số này lớn hơn 0, thì chúng ta sẽ có một bằng chứng khác—không còn mang tính xây dựng—về sự tồn tại của các chuỗi không lặp lại dài tùy ý. Trên thực tế, bây giờ chúng ta sẽ rút ra bất đẳng thức mạnh hơn đáng kể $|B(n)| > 8^n$, (1)

Bằng cách này, chúng ta sẽ không chỉ chứng minh sự tồn tại của các chuỗi không lặp lại có độ dài tùy ý mà còn đưa ra giới hạn dưới đủ tốt cho số lượng của chúng.

Bài toán M310

Bây giờ chúng ta hãy nhớ bài toán M310 từ “Bài toán Kvant - xem «Kvant» số 2 cho năm 1975.

Chứng minh rằng trong số $n$ chữ số có nhiều hơn $8^n$ châm ngôn; trong ký hiệu thập phân của hợp số, không có nhóm chữ số nào (cụ thể là không có chữ số nào) xuất hiện hai lần liên tiếp.

Rõ ràng lời giải bài toán M310 bao hàm việc chứng minh bất đẳng thức (1). Đầu tiên chúng ta sẽ chứng minh một số bất đẳng thức phụ trợ, chúng sẽ có ích cho chúng ta sau này.

Bất bình đẳng phụ trợ. Giả sử rằng tất cả các chuỗi có độ dài $n$ không lặp lại đã được viết ra — tổng cộng có $|B(n)|$ phần và chúng tôi muốn viết ra tất cả các chuỗi có độ dài không lặp lại $n+1$.

Chúng ta hãy lấy một chuỗi tùy ý $a_1, a_2, \dots, a_n$ từ tập hợp $B(n)$. Hãy viết số mười mới như sau - độ dài $n+1$:

$$a_1, a_2, \dots, a_n, 0, a_1, a_2, \dots, a_n, 1, a_1, a_2, \dots, a_n, 9.$$

Chúng tôi thực hiện việc này với tất cả các chuỗi từ bộ $B(n)$. Chúng tôi có được một tập hợp các trình tự nhất định; hãy biểu thị nó bằng $B^*(n+1)$. Trong số các chuỗi của tập hợp $B^*(n+1)$, chúng tôi chọn những chuỗi có hai chữ số giống nhau ở cuối. Chúng tôi biểu thị tập hợp các chuỗi như vậy bằng $B_1(n+1)$. Tương tự, bằng $B_2(n+1)$, chúng ta biểu thị tập hợp các chuỗi như vậy từ $B^*(n+1)$ kết thúc bằng cùng một chuỗi con có độ dài $i$ hai lần liên tiếp. Vì tất cả các chuỗi của $B^*(n+1)$ đều có độ dài $n+1$, nên $i=n_1$ tối đa mà tập hợp $B_i(n+1)$ không trống là $\left[\frac{n+1}{2}\right]$.

Tất cả các chuỗi thuộc bộ $B_1(n+1), B_2(n+1), \dots, B_{n_1}(n+1)$ đều được lặp lại. Hãy chứng minh rằng các chuỗi không khớp này đã bị cạn kiệt bởi các chuỗi lặp lại của tập hợp $B^*(n+1)$ và tập hợp $B^*(n+1)$ chứa tất cả các chuỗi có độ dài không lặp lại có độ dài $n+1$.

Do đó, nếu từ tập $B^*(n+1)$ chúng ta xóa tất cả các chuỗi thuộc tập $B_i(n+1), i=1, 2, \dots, n_1$ thì chúng ta thu được tập $B(n+1)$. Kể từ đây,

$$|B(n+1)| \geq |B^*(n+1)| - |B_1(n+1)| - |B_2(n+1)| - \dots - |B_{n_1}(n+1)|.$$ (2)

⟦folio 9⟧

Bằng cách xây dựng tập hợp $B^* (n+1)$, chúng ta có: $|B^* (n+1)| = 10 \cdot |B(n)|$ và chúng ta chỉ cần ước tính số phần tử của mỗi tập hợp $B_i (n+1)$. Hóa ra $|B_i (n+1)| \leq |B (n+1-i)|$. (3)

Từ bất đẳng thức (2) và (3) suy ra một bất đẳng thức quan trọng mà chúng ta gọi là phụ trợ: $|B (n+1)| > 10 \cdot |B(n)| - (|B(n)| + |B(n-1)| + \dots + |B(1)|)$. (4)

Vì vậy, ta cần chứng minh bất đẳng thức (3).

Vắng mặt nhẹ

Giả sử $A$ và $B$ là hai tập hữu hạn và chúng ta muốn biết tập nào có nhiều phần tử hơn. Điều đầu tiên bạn nghĩ đến là đếm số phần tử của tập hợp $A$ và tập hợp $B$, sau đó so sánh các số kết quả. Nhưng nếu một tập hợp chứa nhiều phần tử hoặc có phần nào đó “khó tính” trong thiết kế, thì việc tính toán số phần tử của nó có thể khá khó khăn. Và không còn rõ phải làm gì nếu các tập hợp $A$ và $B$ là vô hạn. Hóa ra có một cách phổ quát cho phép bạn so sánh các tập hợp thậm chí vô hạn. Hãy mô tả phương pháp này bằng một ví dụ.

Gọi $A$ là tập hợp học sinh được đưa đến rạp hát, và $B$ là tập hợp các địa điểm trong rạp hát. Hãy để học sinh ngồi vào chỗ của chúng. Nếu vẫn còn chỗ trống thì $|B| > |A|$. Nếu tất cả các chỗ đã hết chỗ và một số học sinh không có chỗ thì $|A| > |B|$. Và cuối cùng, nếu hóa ra tất cả các địa điểm đều đã kín chỗ và tất cả học sinh đã được thông báo, thì $|A| = |B|$.

Phương pháp được mô tả ở trên là gì? Chúng tôi đã gán các phần tử của tập hợp $A$ cho các phần tử của tập hợp $B$. Nếu các phần tử của tập hợp $A$ là phần tử cạn kiệt đầu tiên thì $|B| \geqslant |A|$ và nếu các phần tử của tập hợp $B$ là phần tử cạn kiệt đầu tiên thì $|A| \geqslant |B|$. Điều quan trọng là các phần tử khác nhau từ $A$ phải khớp với các phần tử khác nhau từ $B$ (chúng tôi không cho phép một học sinh học các địa điểm cùng một lúc) và ngược lại, các phần tử khác nhau từ $B$ tương ứng với các phần tử khác nhau từ $A$ (chúng tôi không cho phép mỗi học sinh chiếm một vị trí cùng một lúc). Sự tương ứng này được gọi là có giá trị cd.

Chứng minh bất đẳng thức (3)

Bây giờ chúng ta hãy thử thiết lập sự tương ứng một-một giữa các tập hợp $B_i (n+1)$ và một phần của tập hợp $B (n+1-i)$ ($i=1,2,\dots,n_1$). Hãy nhớ lại rằng các chuỗi từ bộ $B_i (n+1)$ có dạng $a_1, a_2, \dots, a_l, b_1, b_2, \dots, b_i, b_1, b_2, \dots, b_{i-1}$ - không dây. Điều này có nghĩa là chuỗi $a_1, a_2, \dots, a_l, b_1, b_2, \dots, b_i$ cũng không dây. Chúng ta hãy liên kết chuỗi (5) từ bộ $B_i (n+1)$ với chuỗi $a_1, a_2, \dots, a_l, b_1, b_2, \dots, b_i$ từ bộ $B (n+1-i)$:

$a_1, a_2, \dots, a_l, b_1, b_2, \dots, b_i, b_1, b_2, \dots, b_i$

Rõ ràng, sự tương ứng này là một đối một và với mỗi chuỗi từ $B_i (n+1)$ có một chuỗi tương ứng từ $B (n+1-i)$. Điều này có nghĩa là $|B_i (n+1)| \leqslant |B (n+1-i)|$ và bất đẳng thức (3), và do đó (4), đã được chứng minh.

Lời giải bài toán M310

Bây giờ chúng ta hãy chứng minh (bằng quy nạp theo $n$) một bất đẳng thức khác:

$|B (n+1)| > 8 \cdot |B (n)|$; (6)

⟦folio 10⟧

rõ ràng là chúng ta cần bất đẳng thức (1); nó theo sau nó, vì
$$|\beta(n)| > 8 \cdot |\beta(n-1)| > 8^2 \cdot |\beta(n-2)| > \dots > 8^{n-1} \cdot |\beta(1)|,$$
và $|\beta(1)| = 10$.

Cơ sở cảm ứng. $n = 1$.
$$|\beta(2)| > 8 \cdot |\beta(1)|,$$
kể từ $|\beta(1)| = 10$ và $|\beta(2)| = 90$.

Bước cảm ứng. Giả sử nó đã được chứng minh rằng
$$|\beta(n)| > 8 \cdot |\beta(n-1)|,$$
$$|\beta(n-1)| > 8 \cdot |\beta(n-2)|,$$
$$|\beta(2)| > 8 \cdot |\beta(1)|;$$

ta cần chứng minh bất đẳng thức (6).
Từ bất đẳng thức (7) suy ra rằng
$$|\beta(n)| > 8^i \cdot |\beta(n-i)|,$$
hoặc
$$|\beta(n-i)| < \frac{|\beta(n)|}{8^i},$$
$$i = 1, 2, \dots, n-1.$$

Chúng ta hãy thay thế các ước tính tìm được (7') cho $|\beta(n-i)|$, $i = 1, 2, \dots, (n-1)$ thành bất đẳng thức (4); chúng tôi nhận được
$$\beta(n+1)| > 10 \cdot |\beta(n)| - |\beta(n)| \cdot \left(1 + \frac{1}{8} + \dots + \frac{1}{8^{n-1}}\right).$$

Bởi vì
$$1 + \frac{1}{8} + \dots + \frac{1}{8^{n-1}} < 2,$$
thì $|\beta(n+1)| > 8 \cdot |\beta(n)|$.

Bây giờ chúng ta hãy xây dựng một số bài toán.

2. Xây dựng một chuỗi không dây sao cho khi bạn thêm bất kỳ số nào vào cuối chuỗi đó, bạn sẽ luôn nhận được một chuỗi lặp lại.

3. Sử dụng dãy số S. E. Arshon, chứng minh sự tồn tại của dãy số dài có góc cạnh gồm các số 1 và 2 không có ba nhóm số liền kề giống hệt nhau.

4. Chứng minh rằng với mọi số tự nhiên $n$ dãy không dây có độ dài $n$ gồm bốn chữ số 1, 2, 3, 4 đều lớn hơn $2^n$.

Từ bài toán 4, nó tồn tại dưới dạng góc của một chuỗi không dây dài gồm bốn chữ số khác nhau. S. E. Arshon đã chỉ ra rằng trên thực tế, sự tồn tại của một chuỗi không dây có độ dài bất kỳ là đủ ngay cả đối với ba chữ số.

Chuỗi không dây vô tận

Vì vậy, chúng tôi đã chứng minh được sự tồn tại của chuỗi không dây dài có góc cạnh. Trong phần này chúng ta sẽ chứng minh sự tồn tại của một chuỗi không dây vô tận (lưu ý rằng chuỗi đầu tiên chưa bao hàm chuỗi thứ hai).

Bài tập 5. Chứng minh rằng nếu có ít nhất một dãy không dây vô tận thì có vô số dãy như vậy.

Đặt $B$ biểu thị tập hợp tất cả các chuỗi không dây hữu hạn. Vì tập hợp $B$ là vô hạn và có số hữu hạn các chữ số khác nhau (tổng cộng là 10), nên có ít nhất một chữ số mà tập hợp vô hạn của $B$ bắt đầu. Hãy biểu thị số này bằng $a_1$. Hãy xóa khỏi $B$ những chuỗi không bắt đầu bằng số $a_1$. Chúng ta thu được một tập hợp vô hạn $B^{(1)}$. Tương tự, có một chữ số $a_2$ đứng ở vị trí thứ hai trong vô số dãy $B^{(1)}$. Chúng ta hãy xóa khỏi $B^{(1)}$ những chuỗi có chữ số thứ hai khác với $a_2$. Chúng ta nhận được một tập hợp vô hạn $B^{(2)}$, v.v.

Bây giờ chúng ta hãy xem xét dãy vô hạn $a_1, a_2, \dots$; Hãy chứng minh rằng nó là không dây.

Để làm được điều này, chúng ta chỉ cần chứng minh rằng với mọi số tự nhiên $n$ thì dãy hữu hạn không dây là $a_1, a_2, \dots, a_n$. Nhưng theo cách xây dựng, tất cả các chuỗi của tập hợp $B^{(n)}$ đều bắt đầu bằng chuỗi $a_1, a_2, \dots, a_n$ và tập hợp $B^{(n)}$ là tập hợp con của tập hợp

⟦folio 11⟧

va B, và do đó tất cả các chuỗi từ B^{(n)} đều không lặp lại. Bất kỳ phần đầu nào của chuỗi không lặp lại đều là chuỗi không lặp lại.

Bài toán 6. Chứng minh rằng trong số các phân số thập phân vô hạn thứ mười một bất kỳ, bạn có thể chọn hai phân số có cùng các chữ số với vô số chữ số.

Khái quát hóa

Chúng ta hãy biểu thị bằng chữ P đặc tính “là một chuỗi không lặp lại”. Khi đó mệnh đề vừa chứng minh có cấu trúc như sau:

Hậu quả tiền đề

Có một dãy dài tùy ý có tính chất P

Có một dãy vô hạn có tính chất P

Liệu tuyên bố này có đúng không nếu chúng ta giả sử rằng P là thuộc tính tùy ý của dãy số? Nói chung là không. Hãy đưa ra một ví dụ: coi tính chất “là một dãy hữu hạn”. Rõ ràng là có những chuỗi hữu hạn có độ dài tùy ý, nhưng không có thứ gọi là chuỗi hữu hạn vô hạn.

Bây giờ chúng ta hãy lưu ý rằng, khi chứng minh sự tồn tại của một chuỗi vô hạn không lặp lại, chúng ta chỉ dựa vào hai sự kiện sau đây, dẫn trực tiếp từ định nghĩa về chuỗi không lặp lại.

1°. Mọi phần đầu của dãy có thuộc tính P cũng có thuộc tính này.

2°. một dãy vô hạn có phần đầu dài tùy ý có tính chất P cũng có tính chất này.

Về giới hạn. Thuộc tính tùy ý của dãy số thỏa mãn điều kiện 1°

và 2°, chúng tôi gọi đó là tài sản di truyền.

Ví dụ: thuộc tính “không chứa số 3”, “chỉ gồm các số 1, 2, 3”, “bắt đầu bằng số 7” là thuộc tính di truyền, nhưng thuộc tính “chứa vô số số 4”, “kết thúc bằng số 7” không phải là thuộc tính di truyền.

Định lý. Cho P là tài sản di truyền tùy ý. Khi đó, nếu có các dãy dài tùy ý có tính chất P thì cũng tồn tại một dãy vô hạn có tính chất này.

Chúng ta sẽ không tập trung vào việc chứng minh định lý này vì nó hoàn toàn lặp lại chứng minh đã đưa ra ở đoạn trước.

Ứng dụng

Hãy xem xét các dãy số gồm có ba chữ số: 1, 2, 3. Hãy đặt một số dãy số (có độ dài từ hai chữ số trở lên) là bị cấm. Được biết, tất cả các chuỗi bị cấm đều có độ dài khác nhau.

Chúng ta hãy làm cho các chuỗi không chứa các chuỗi bị cấm là chính xác.

Chúng ta hãy quay lại “Sách Vấn đề «Kvant» - tới Vấn đề M300 (xem «Kvant» Số 12 cho năm 1974).

Từ câu lệnh bài toán M300 suy ra có các dãy đều đặn dài tùy ý. Bây giờ chúng ta hãy lưu ý rằng tính chất “là một dãy đều đặn” luôn là một thuộc tính kế thừa (có thể chứng minh được!) Điều này có nghĩa là phát biểu về sự tồn tại của các dãy chính quy có độ dài tùy ý có thể được thay thế bằng một phát biểu mạnh hơn - về sự tồn tại của một dãy số chính quy vô hạn, và phát biểu bài toán M300 là phát biểu về sự tồn tại của một từ vô hạn không có sự kết hợp các chữ cái bị cấm.
