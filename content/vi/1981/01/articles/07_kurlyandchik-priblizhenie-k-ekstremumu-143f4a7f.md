---
id: 1981-1-kurlyandchik-priblizhenie-k-ekstremumu-143f4a7f
issue: kvant_1981_1
year: 1981
number: "1"
title: Tiếp cận một cực trị
authors:
  - Курляндчик Л. Д.
rubric: matematicheskiy-kruzhok
rubric_sub: Математический кружок
page_first: 23
page_last: 27
page_labels: 21, 22, 24, 25
tag: LMZA
lang: vi
source: kvant_digital
extraction: vision
content_sha256: 09df48cef04312dedd04b563290be3b5e94fd6646a1e8765cb327cf36682ffb8
prompt_sha256: draft-1
translated_from: content/ru/1981/01/articles/07_kurlyandchik-priblizhenie-k-ekstremumu-143f4a7f.md
source_content_sha256: d454b2177b9cc0f3141cf06c88e10cde3ffaa9845d4f5f7deae8cf38992dc5dd
translation_model: draft
translation_run: vi-draft-2026-10-31
translation_quality: draft
---

⟦folio 21⟧

L. Kurlyandik

Tiếp cận một cực trị

Khái niệm tùy ý mà bạn học ở trường cung cấp một cách đơn giản để tìm giá trị lớn nhất và nhỏ nhất của hàm $y=f(x)$ của một biến duy nhất $x$. Tuy nhiên, trong các bài toán đôi khi cần tìm giá trị lớn nhất hoặc nhỏ nhất của biểu thức, tùy thuộc vào một số biến. Các phương pháp liên quan đến việc sử dụng tùy ý ở đây phức tạp hơn nhiều và không được nghiên cứu ở trường, vì vậy các phương pháp cơ bản lời giải như bài toán có giá trị lớn hơn. Một trong những phương pháp này, được đề xuất vào năm 1884 bởi nhà toán học người Đức R. Sturm, gần như được thảo luận trong bài báo.

Hãy bắt đầu với hai bài toán.

Bài toán 1. Trong số n từ ghi trong hình tròn cho trước, n từ nào có diện tích lớn nhất?

Bài toán 2. Tổng của n số bằng 1. Tại giá trị nào của các số này thì tổng bình phương của chúng có giá trị nhỏ nhất có thể?

Hình 1 và 2 hiển thị dép xỏ ngón ABC, với $|AB| > |BC|$. Hãy xem điều gì sẽ xảy ra với diện tích của tam giác này nếu không thay đổi vị trí của các điểm A và C, chúng ta di chuyển điểm B dọc theo cung AC sao cho độ dài các cạnh AB và BC gần nhau, tức là hiệu của chúng giảm đi. Đặt điểm $B'$ trên cung AC sao cho $|AB'| = |CB|$. Để so sánh độ dài cạnh AB và BC, bạn cần thay điểm B bằng điểm bất kỳ của BB' còn lại. Đồng thời, chiều dài đường cao BH của tam giác ABC sẽ tăng lên và do đó diện tích của nó sẽ tăng lên.

Quan sát này cho thấy rằng n-pleaser không đều không phải là nghiệm của bài toán 1. Thật vậy, nếu $|AB|$ và $|BC|$ là các cạnh kề không bằng nhau của n-pleaser này (Hình 2), thì bằng cách thay đỉnh B bằng một số điểm của BB' khác, chúng ta sẽ tăng diện tích của tam giác ABC và thu được một n-pleaser nội tiếp có diện tích lớn hơn.

Đến bài toán 2, chúng ta hãy tìm hiểu điều gì sẽ xảy ra với tổng bình phương của hai số nếu chúng ta hợp nhất các số này mà tổng của chúng không thay đổi. Đặt $a, b$ là các số đã cho, $a < b$ và đặt $0 < \varepsilon < b - a$. Sau đó

$$(a + \varepsilon)^2 + (b - \varepsilon)^2 = a^2 + b^2 - 2\varepsilon(b - a - \varepsilon) < a^2 + b^2.$$

Chúng ta thấy rằng tổng bình phương đã giảm. Quan sát này cho thấy rằng một tập hợp gồm n số (có tổng bằng 1), trong đó có hai số khác nhau, không phải là nghiệm của bài toán 2. Thật vậy, bằng cách hợp nhất các số không bằng nhau, chúng ta sẽ giảm tổng bình phương của chúng mà không thay đổi tổng của tất cả các số.

⟦folio 22⟧

Có vẻ như bài toán 1 và 2 lời giải: nghiệm của bài toán 1 là một $n$-giác đều nội tiếp trong một đường tròn cho trước và nghiệm của bài toán 2 là tập hợp các số $(1/n, 1/n, \dots, 1/n)$. Trên thực tế, tất cả những gì đã được chứng minh cho đến nay là không có $n$-gon nào khác ngoài số thông thường là nghiệm của bài toán 1 hoặc một tập hợp các số $n$ ngoài $(1/n, 1/n, \dots, 1/n)$ là nghiệm của bài toán 2. Nhưng một khả năng logic khác vẫn chưa được khám phá: không có $n$-gon là nghiệm bài toán 1, không có tập hợp số $n$ nào là lời giải cho bài toán 2. Việc chứng minh sự tồn tại của một đối tượng toán học với một thuộc tính cho trước thường khá khó khăn. Nhưng lời giải mọi bài toán đều được đơn giản hóa nếu biết khả năng đáp số và đây chính xác là trường hợp trong Vấn đề 1 và 2.

Lời giải bài toán 1.

Hãy chứng minh rằng diện tích của $n$-giác bất kỳ nội tiếp trong một đường tròn cho trước không lớn hơn diện tích của $n$-giác đều nội tiếp trong đường tròn này. (Điều này chỉ có nghĩa là $n$-gon đều là nghiệm của bài toán 1; trong lập luận trước chúng ta chỉ chứng minh rằng $n$-gon bất quy tắc không phải là nghiệm.)

Lưu ý rằng nếu chúng ta thay thế đỉnh $B$ của $n$-giác nội tiếp bằng điểm $B'$ (Hình 2), chúng ta thu được một $n$-giác nội tiếp có cùng diện tích, khác với đa giác ban đầu theo thứ tự hai cạnh liền kề. Sau khi thực hiện thao tác này nhiều lần nếu cần, chúng ta có thể hoán đổi hai cạnh bất kỳ của một $n$-giác nội tiếp mà không làm thay đổi diện tích của nó.

Cho $P$ là một $n$-giác không chính quy nội tiếp trong một đường tròn cho trước. Cạnh nhỏ nhất của $n$-gon này phụ thuộc một cung có đỉnh góc nhỏ hơn $360^\circ/n$ và cạnh dài nhất phụ thuộc một cung lớn hơn $360^\circ/n$. Chúng ta hãy sắp xếp lại các cạnh của $n$-gon sao cho các cạnh lớn nhất và nhiều nhất liền kề nhau. Trong Hình 3 đây là các cạnh $AB$ và $BC$. Chúng ta hãy vẽ trên cung $AC$ cung $AB_1$, đỉnh góc của nó bằng $360^\circ/n$. Thay thế đỉnh $B$ bằng điểm $B_1$, chúng ta thu được một $n$-gon $P_1$ nội tiếp, có diện tích lớn hơn $n$-gon $P$.

Hơn nữa, đa giác $P_1$ có ít nhất một cạnh đối diện với một cung có độ lớn $360^\circ/n$, tức là bằng cạnh của hình $n$-gon nội tiếp thông thường. Nếu đa giác $P_1$ không đều, thì sau khi thực hiện thao tác được mô tả với nó, chúng ta sẽ đi đến một $n$-giác $P_2$ nội tiếp có diện tích lớn hơn, trong đó có ít nhất một cạnh nữa bằng cạnh của một $n$-giác nội tiếp thông thường. Sau một số hữu hạn bước, chúng ta đến một $n$-giác nội tiếp và do đó diện tích của nó lớn hơn diện tích của đa giác $P$.

Lời giải bài toán 2.

Giả sử tổng của các số $a_1, a_2, \dots, a_n$ bằng 1. Nếu không phải tất cả các số này đều bằng nhau thì số nhỏ nhất trong số chúng nhỏ hơn 1/n và số lớn nhất lớn hơn 1/n. Hãy để $a_1 < 1/n, a_2 > 1/n$. Bằng cách thay thế số $a_1$ bằng 1/n và số $a_2$ bằng $a_1 + a_2 - 1/n$, chúng ta “tiến gần hơn” $a_1$ và $a_2$ mà không thay đổi tổng của chúng và do đó, làm giảm tổng bình phương. Như vậy, chúng ta sẽ được một tập hợp số mới có tổng bằng 1 và tổng bình phương của các số trong tập hợp này nhỏ hơn tổng bình phương của các số trong tập hợp ban đầu. Hơn nữa, tập hợp mới chứa ít nhất một số bằng 1/n. Nếu không phải tất cả các số trong tập hợp này đều bằng 1/n, thì sau khi thực hiện thao tác được mô tả với nó, chúng ta sẽ thu được một tập hợp có tổng bằng 1, nhưng thậm chí nhỏ hơn tổng các bình phương, trong đó vẫn còn ít nhất một số bằng 1/n. Sau một số hữu hạn bước, chúng ta thu được một tập hợp $(1/n, 1/n, \dots, 1/n)$ với tổng các bình phương nhỏ hơn tập hợp ban đầu. Do đó, tập hợp số $(1/n, 1/n, \dots, 1/n)$ là nghiệm của bài toán 2.

Nếu đối với một số tùy ý $S$ trong số các tập hợp $n$ các số $a_1, a_2, \dots, a_n$ có ​​tổng $S$, chúng ta tìm kiếm một số trong đó tổng các bình phương của các số hạng tối thiểu, thì lý do trên sẽ dẫn chúng ta đến tập hợp $(\frac{S}{n}, \frac{S}{n}, \dots, \frac{S}{n})$. Do đó, đối với các số tùy ý $a_1, a_2, \dots, a_n$ áp dụng như sau:

⟦folio 24⟧

Thật vậy, nếu không phải tất cả các số đã cho đều bằng nhau thì số nhỏ nhất trong số đó nhỏ hơn $A$ và số lớn nhất lớn hơn $A$. Giả sử $a_1 < A, a_2 > A$. Bằng cách thay thế $a_1$ bằng $A$ và $a_2$ bằng $a_1 + a_2 - A$, chúng ta sẽ jinx chúng trong khi vẫn giữ nguyên tổng của những con số này. Trong trường hợp này, trung bình số học $A$ sẽ không thay đổi, nhưng trung bình hình học $\Gamma$ sẽ tăng (xem phôi I). Nếu có các số không bằng nhau trong bộ số mới thì chúng ta thực hiện thao tác tương tự. Vì mỗi bước sẽ tăng số lượng số bằng $A$, nên sau một số bước hữu hạn, tất cả các số sẽ trở thành bằng nhau và chúng ta sẽ đạt được một tập hợp mà trung bình số học bằng trung bình hình học. Vì ở mỗi bước, nó chỉ đơn giản là trung bình hình học và trung bình số học không thay đổi, nên trong bộ số ban đầu, trung bình số học lớn hơn trung bình hình học.

Bài tập 1. Dùng phôi I, tìm 25 số hạng tự nhiên $n_1, n_2, \dots, n_{25}$ cần chia thành số 1981 sao cho tích $n_1! n_2! \dots n_{25}$ nhỏ nhất.

Bài 2. Dùng phôi II chứng minh đẳng thức của các số dương $a_1, a_2, \dots, a_n$ và số tự nhiên $k$

$$\frac{a_1^k + a_2^k + \dots + a_n^k}{n} \geq \left( \frac{a_1 + a_2 + \dots + a_n}{n} \right)^k.$$

Sử dụng Mệnh đề III, bây giờ chúng ta sẽ chứng minh đẳng thức mang tên nhà khoa học nổi tiếng thế kỷ 18 Christine Huygen: nếu $x_1, x_2, \dots, x_n$ là các số dương thì

$$\left( 1 + x_1 \right) \left( 1 + x_2 \right) \dots \left( 1 + x_n \right) \geq \geq \left( 1 + \sqrt[n]{x_1 x_2 \dots x_n} \right)^n.$$

Khi các số dương $a$ và $b$ hợp nhất với một tích cố định, tổng $a + b$ giảm, nghĩa là tích $(1 + a)(1 + b)$, bằng $1 + ab + a + b$, cũng giảm.

Hãy đặt $\Gamma = \sqrt[n]{x_1 x_2 \dots x_n}$. Nếu trung bình của các số $x_1, x_2, \dots, x_n$ không bằng nhau thì số nhỏ nhất trong số đó nhỏ hơn $\Gamma$ và số lớn nhất lớn hơn $\Gamma$. Thay thế $x_1$ bằng $\Gamma$ và $x_2$ bằng $\frac{x_1 x_2}{\Gamma}$. Đồng thời, $x_1$ và $x_2$ sẽ bảo quản sản phẩm và do đó

*) bài toán này đã được trình bày tại Olympic Toán học hạng nặng lần thứ XII. Vào «Kvant», 1979, số 7, lời giải của nó được nêu, khác với những gì được thảo luận trong bài viết.

⟦folio 25⟧

được đặt bên trong đoạn $[a; b]$. Cuối cùng, chúng ta sẽ đi đến tình huống trong đó mọi số $x_1, x_2, \dots, x_n$, có lẽ ngoại trừ một số, sẽ bằng $a$ hoặc $b$.

Vế trái của bất đẳng thức bây giờ có thể được coi là hàm của một biến được xác định trên khoảng $[a; b]$. Chứng minh rằng hàm này lấy giá trị lớn nhất ở một đầu của đoạn $[a; b]$ và kiểm tra xem giá trị này có vượt quá vế phải của bất đẳng thức hay không.

Bài tập

3. Hình $n$-giác nào nội tiếp hình bán nguyệt cho trước (sao cho một cạnh trùng với đường kính) có diện tích lớn nhất?

4. Chứng minh rằng trung bình cộng của các tam giác có diện tích cho trước sẽ có tam giác đồng dạng có chu vi nhỏ nhất.

5. Tìm hiểu cách tích số $(1 + \frac{1}{a}) (1 + \frac{1}{b})$ hoạt động khi hợp nhất các số dương $a$ và $b$.

Chứng minh rằng nếu tổng các số dương $x_1, x_2, \dots, x_n$ bằng 1 thì

$$(1 + \frac{1}{x_1}) (1 + \frac{1}{x_2}) \dots (1 + \frac{1}{x_n}) \geq (n+1)^n.$$

6. Tìm hiểu cách hoạt động của tổng $(a + \frac{1}{a})^2 + (b + \frac{1}{b})^2$ khi các số dương $a$ và $b$ hợp nhất.

Chứng minh rằng nếu tổng các số dương $x_1, x_2, \dots, x_n$ bằng 1 thì

$$(x_1 + \frac{1}{x_1})^2 + (x_2 + \frac{1}{x_2})^2 + \dots + (x_n + \frac{1}{x_n})^2 \geq \frac{(n^2+1)^2}{n}.$$

7. Nghiên cứu hành vi của phân số $(1-a)(1-b)/ab$ khi hợp nhất các số dương nhỏ hơn 1 $a$ và $b$ có ​​tổng bằng 1.

Chứng minh rằng nếu tổng các số dương $x_1, x_2, \dots, x_n$ bằng 1 thì

$$(1-x_1)(1-x_2) \dots (1-x_n)/x_1x_2 \dots x_n \geq (n-1)^n.$$

8. Nghiên cứu hành vi của tổng $\frac{1}{1+a} + \frac{1}{1+b}$ đối với tích cố định của các số dương $a$ và $b$.

Chứng minh các bất đẳng thức:

a) nếu các số $x_1, x_2, \dots, x_n$ lớn hơn 1 thì

$$\frac{1}{1+x_1} + \frac{1}{1+x_2} + \dots + \frac{1}{1+x_n} \geq \frac{n}{1+\sqrt[n]{x_1x_2 \dots x_n}}.$$

6) nếu số dương $x_1, x_2, \dots, x_n$ nhỏ hơn 1 thì

$$\frac{1}{1+x_1} + \frac{1}{1+x_2} + \dots + \frac{1}{1+x_n} \leq \frac{n}{1+\sqrt[n]{x_1x_2 \dots x_n}}.$$

9. Các số $a, \beta, \gamma, \delta$ thuộc khoảng $]0; \frac{\pi}{2}[\, a+\beta+\gamma+\delta=\pi$. Chứng minh rằng $tg\alpha+tg\beta+tg\gamma+tg\delta \geq 4$.

10. Các số dương $a, \beta, \gamma, \delta$ sao cho $a+\beta+\gamma+\delta=\pi$. Chứng minh rằng $\sin\alpha\sin\beta\sin\gamma\sin\delta \leq \frac{1}{4}$.

11. a) $a, b, c, d$ là các số dương. Chứng minh bất đẳng thức

$$\sqrt{\frac{a^2+b^2+c^2+d^2}{4}} \geq \sqrt{\frac{abc+abd+acd+bcd}{4}}.$$

6) $x_1, x_2, \dots, x_n$ là số dương, $k$ là số tự nhiên, $k \geq 2$. Chứng minh bất đẳng thức

$$\sqrt{\frac{x_1^k+x_2^k+\dots+x_n^k}{n}} \geq \sqrt{\frac{x_1x_2\dots x_n}{n}}.$$

12. Những $n$ số $x_1, x_2, \dots, x_n$ nào nên đứng giữa các số dương $a$ và $b$ ($a<b$) để tạo thành phân số

$$\frac{(a+x_1)(x_1+x_2)(x_2+x_3)\dots(x_n+1+x_n)(x_n+b)}{x_1x_2\dots x_n}$$

lấy giá trị nhỏ nhất có thể?

13. Tổng của một số số không âm là 3 và tổng bình phương của các số này lớn hơn 1. Chứng minh rằng từ những số này có thể chọn được ba số có tổng lớn hơn 1.
