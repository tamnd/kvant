---
id: 1979-2-bekker-vostokov-ionin-2-adicheskie-chisla-bbf33021
issue: kvant_1979_2
year: 1979
number: "2"
title: số 2 adic
authors:
  - Беккер Б. М.
  - Востоков С. В.
  - Ионин Ю. И.
rubric: matematicheskiy-kruzhok
rubric_sub: Математический кружок
page_first: 28
page_last: 33
page_labels: 26-31
tag: GIF9
lang: vi
source: kvant_digital
extraction: vision
content_sha256: e12daf5920d6b56060cfcc542b5bae71be83757bc48f1ddd05aa5196cd9de8d4
prompt_sha256: draft-1
translated_from: content/ru/1979/02/articles/10_bekker-vostokov-ionin-2-adicheskie-chisla-bbf33021.md
source_content_sha256: 6b5fed7703c785ca23a2cf927e4ad34e31fa359462d47fa9963582235f97be89
translation_model: draft
translation_run: vi-draft-2026-10-31
translation_quality: draft
---

⟦folio 26⟧

số 2 adic

Nếu bạn được hỏi cái gì có thể được gọi là "khoảng cách giữa hai số hữu tỷ", thì sau khi suy nghĩ, có lẽ bạn nên trả lời đáp số: "khoảng cách giữa hai số nên được gọi là mô đun hiệu của chúng. Chúng ta thực hiện định nghĩa này một cách hợp lý - "khoảng cách" này thỏa mãn tất cả các tiên đề về khoảng cách (xem "Hình học 8", đoạn 132). Nhưng hóa ra khoảng cách giữa các số hữu tỷ thỏa mãn tất cả các tiên đề có thể được tính theo một cách khác Cách này đã được thực hiện bởi nhà toán học người Đức K. Hansel (1861-1941) - ông thậm chí còn nghĩ ra cả một loại khoảng cách như vậy. Một trong số đó sẽ được thảo luận trong bài viết này.

Nghiên cứu của Hansel hóa ra rất quan trọng đối với đại số và toán học nói chung, và khoảng cách của ông sẽ giúp chúng ta giải hai bài toán, thoạt nhìn, không liên quan gì đến khoảng cách nào cả.

khoảng cách 2 adic

Cho $a$ và $b$ là các số hữu tỉ. Nếu $a \neq b$ thì chúng ta biểu thị số $a-b$ là $a-b = 2^k \cdot \frac{m}{n}$, trong đó $m$ và $n$ là số lẻ và $k$ là số nguyên (dương, âm hoặc bằng 0). Khoảng cách 2 adic giữa các số $a$ và $b$, $a \neq b$, được gọi là số $\rho(a, b) = 1/2^k$. Nếu $a=b$ thì đặt $\rho(a, b) = 0$.

Chúng ta hãy nhớ lại các tiên đề về khoảng cách:

A1. $\rho(a, b) > 0$ nếu $a \neq b$ và $\rho(a, b) = 0$ nếu $a=b$.

A2. $\rho(a, b) = \rho(b, a)$.

A3. $\rho(a, c) \leqslant \rho(a, b) + \rho(b, c)$.

Thuộc tính A1 và A2 cho khoảng cách 2 adic, cũng như thuộc tính A3 trong trường hợp nếu trong số các số $a, b, c$ có những số bằng nhau, rất bằng nhau.

Hãy chứng minh tính chất A3 cho các số hữu tỉ khác nhau $a, b, c$. Đặt $a-b = 2^{k_1} \cdot \frac{m}{n_1}$, $b-c = 2^{k_2} \cdot \frac{m_2}{n_2}$, $a-c = 2^{k_3} \cdot \frac{m_3}{n_3}$, trong đó tất cả $m_i, n_i$ đều là số lẻ. Vì $a-c = (a-b) + (b-c)$ nên $k_3$ không nhỏ hơn số nhỏ hơn trong các số $k_1$ và $k_2$. Nhưng sau đó $\frac{1}{2^{k_3}}$ không vượt quá số lớn nhất trong số $\frac{1}{2^{k_1}}$ và $\frac{1}{2^{k_2}}$, và thậm chí còn hơn thế nữa $\frac{1}{2^{k_3}} \leqslant \frac{1}{2^{k_1}} + \frac{1}{2^{k_2}}$.

Vì vậy, chúng ta thấy rằng tất cả các tiên đề đều thỏa mãn, do đó $\rho$ thực sự có thể được gọi là khoảng cách.

Điều gì làm thay đổi khoảng cách này? Hóa ra nó làm thay đổi mức độ chia hết của một số hữu tỷ cho 2. Số càng chia hết cho 2 thì càng gần 0. Ví dụ: 8 gần 0 hơn 1/2; 16 gần 0 hơn 8; 480 gần 0 hơn 16; 384 gần bằng 0 hơn 480.

Trên thực tế, chúng ta đã chứng minh được rằng khoảng cách 2-adic có tính chất A3', mạnh hơn tính chất A3. A3'. Khoảng cách $\rho(a, c)$ không vượt quá khoảng cách lớn hơn $\rho(a, b)$ và $\rho(b, c)$.

Căng thẳng 1. Chứng minh rằng nếu $\rho(a, b) \neq \rho(b, c)$ thì $\rho(a, c)$ bằng số lớn nhất trong các số $\rho(a, b), \rho(b, c)$, và nếu $\rho(a, b) = \rho(b, c) \neq 0$ thì $\rho(a, c) < \rho(a, b)$.

Tính chất A3' dẫn tới những hệ quả thú vị. Cho ta biết rằng đường tròn 2 adic bán kính $r$ tâm $a$ (và một số hữu tỉ, $r$ là số thực dương) là tập hợp các số hữu tỉ $x$ thỏa mãn $\rho(a, x) < r$.

Căng thẳng 2. Chứng minh rằng nếu hai đường tròn 2 adic có giao điểm khác rỗng thì một trong hai đường tròn này chứa trong đường tròn kia.

⟦folio 27⟧

3. Chứng minh rằng đường tròn 2-Adic bán kính $r$ chứa vô số đường tròn 2-Adic rời rạc từng cặp có bán kính $r$.

Bằng cách tương tự với mô hình thông thường của một số, chúng ta xác định mô đun 2 adic $\|a\|$ của một số hữu tỷ $a$ là khoảng cách 2 adic từ số này đến 0: nếu $a = 2^k \frac{m}{n}$, trong đó $m$ và $n$ là số lẻ thì $\|a\| = \rho(0, a) = \left(\frac{1}{2}\right)^k$. Thật dễ dàng để thiết lập các thuộc tính sau của mô-đun 2-adic:

M1. $\|a\| > 0$ nếu $a \neq 0$ và $\|0\| = 0$.
M2. Nếu $\|a\| > \|b\|$ thì $\|a+b\| = \|a\|$, nếu $\|a\| = \|b\| \neq 0$ thì $\|a+b\| < \|a\|^*$.
M3. $\|ab\| = \|a\| \cdot \|b\|$.

Nhấn mạnh

4. Rút ra từ các thuộc tính M1–M3 các thuộc tính sau của mô-đun 2-adic:

a) $\|a\| = \|a\|$, b) nếu $\|a\| \neq \|b\|$, thì $\|a-b\| = \|a+b\|$.
5. Chứng minh rằng nếu $\|1-x\| < 1$ và $\|1-y\| < 1$ thì $\|1-xy\| < 1$.

Bài toán về một hình vuông

Hình 1 cho thấy một hình vuông được chia thành các hình tam giác tròn. Các hình vuông ở Hình 2 được chia thành các hình tam giác có diện tích bằng nhau. Trong mỗi ví dụ này, số lượng hình tam giác trong phân vùng là số chẵn.

Bài toán a. Chứng minh rằng không thể chia một hình vuông thành số lẻ các hình tam giác có diện tích bằng nhau.

Chúng ta hãy chọn hệ tọa độ trên mặt phẳng sao cho các đỉnh $O, A, B$ và $C$ của một hình vuông đã cho có tọa độ $O(0; 0), A(1; 0)$,

$\cdot$ Dù sao thì $\|a+b\| \leq \|a\| + \|b\|$.

$B(1; 1), C(0; 1)$. Giả sử hình vuông được chia thành $n$ hình tam giác có diện tích bằng nhau. Khi đó diện tích của mỗi hình tam giác trong phân vùng bằng $1/n$. Nếu $n$ là số lẻ thì $\|1/n\| = 1$ và nếu $n$ là số chẵn thì $\|1/n\| \geq 2$. Do đó, tính chẵn lẻ của $n$ sẽ được chứng minh nếu chúng ta thiết lập $\|1/n\| \geq 2$ đó.

Hãy xem xét một trường hợp đặc biệt. Đặt các đỉnh của các tam giác phân chia là các điểm có tọa độ hữu tỉ. Trong trường hợp này, mỗi đỉnh $(x; y)$ có thể được tô màu xanh lục, đỏ hoặc xanh lam theo quy tắc sau: nếu $\|x\| < 1$ và $\|y\| < 1$ thì điểm có màu xanh lục; nếu $\|x\| \geq \|y\|$ và $\|x\| \geq 1$ thì điểm đó có màu đỏ; nếu $\|x\| < \|y\|$ và $\|y\| \geq 1$ thì điểm đó có màu xanh lam (xem Hình 3). Chúng ta sẽ giả sử rằng không chỉ các đỉnh được tô màu mà còn tất cả các điểm hữu tỷ của mặt phẳng.

Bài tập 6. a) Chứng minh rằng nếu $P$ là điểm màu lục thì khi $\overrightarrow{PO}$ ($O$ là gốc tọa độ) cắt song song thì mỗi điểm màu giữ nguyên màu của nó.

6) Chứng minh rằng không có đường thẳng nào chứa điểm đủ ba màu.

Giả sử rằng một trong các hình tam giác trong phân vùng có tất cả các đỉnh có màu khác nhau (phụ lục đã chứng minh rằng một hình tam giác như vậy phải tồn tại). Đặt $K$ là đỉnh màu xanh lục của tam giác này.

Với giao điểm song song của $\overrightarrow{KO}$, bằng bài tập ba, chúng ta lại thu được một hình tam giác có các đỉnh có cả ba màu. Chúng ta hãy biểu thị bằng $L_1(x_1, y_1)$ đỉnh màu đỏ của tam giác thu được và $L_2(x_2, y_2)$ đỉnh màu xanh lam của nó (màu xanh lá cây

⟦folio 28⟧

đỉnh của tam giác này là điểm $O$). Vì tam giác $OL_1L_2$ thu được bằng cách dịch song song tam giác phân vùng nên diện tích của nó bằng $1/n$. Mặt khác, diện tích tam giác $OL_1L_2$ là $1/2|x_1y_2-x_2y_1|$. (Hãy tự chứng minh điều đó.)

Vì vậy, chúng ta có được đẳng thức $1/n=1/2|x_1y_2-x_2y_1|$. Bây giờ không khó để thiết lập bất đẳng thức $\left\|\frac{1}{n}\right\| \geq 2$. Thật vậy, vì $L_1$ là chấm đỏ và $L_2$ là chấm xanh lam, nên $\|x_1\| \geq \|y_1\|$, $\|x_2\| < \|y_2\|$.

Thay đổi các bất đẳng thức này, chúng ta nhận được $\|x_1\| \|y_2\| > \|x_2\| \|y_1\|$, và do đó, theo tính chất $M3$ $\|x_1y_2\| > \|x_2y_1\|$. Do tính chất $M2$ và bài tập 46) $\|x_1y_2\| = \|x_1y_2\|$. Ngoài ra, $\|x_1\| \geq 1$, $\|y_2\| \geq 1$, vậy $\|1/n\| = 2\|x_1\| \|y_2\| \geq 2$.

Để giải bài toán trong trường hợp tổng quát, chỉ cần chứng minh rằng mô hình 2-Adic có phần mở rộng của tập hợp tất cả các số thực là đủ, tức là có một hàm $x \rightarrow \|x\|$ được xác định trên tập hợp tất cả các số thực, có tính chất $M1-M3$ và trùng với mô hình 2-Adic trên tập hợp các số khác nhau. Chức năng như vậy của thực tế tồn tại, nhưng bằng chứng về sự tồn tại của nó đòi hỏi thành phố phải sử dụng các phương tiện phức tạp hơn những phương tiện mà chúng tôi có trong bài viết này.

phân hủy 2-adic

Như bạn đã biết, bất kỳ số tự nhiên nào cũng có thể được biểu diễn dưới dạng tổng lũy ​​thừa của 2. Ví dụ: $1000 = 2^3+2^5+2^6+2^7+2^8+2^9$. Sử dụng phép xét 2-adic, việc khai triển này có thể thu được như sau. Trước tiên, chúng ta tìm lũy thừa của 2 có cùng khoảng cách từ 0 đến số 1000. Tìm lũy thừa này $(2^3)$, trừ nó khỏi số 1000 để được số 2, có cùng khoảng cách với 0. Sau đó, chúng ta tìm lũy thừa của 2 có cùng khoảng cách với 0 với số $960 = 992-2^5$, v.v.

⟦folio 29⟧

Sử dụng lũy ​​thừa âm của 2, chúng ta có thể thu được các khai triển tương tự của các số hữu tỉ có dạng $\frac{m}{2^k}$, trong đó $m$, $k$ là các số tự nhiên. Ví dụ,

$$\frac{1477}{256} = \frac{1 + 2^2 + 2^8 + 2^7 + 2^8 + 2^{10}}{2^8} = 2^{-8} + 2^{-6} + 2^{-2} + 2^{-1} + 2^0 + 2^2.$$

Không có số hữu tỉ nào khác có thể được biểu diễn dưới dạng tổng lũy ​​thừa của hai, nhưng hóa ra những tổng như vậy có thể xấp xỉ bất kỳ số hữu tỉ nào một cách chính xác như mong muốn. Thật vậy, giả sử $a$ là một số hữu tỉ và $\|a\| = \frac{1}{2^{k_1}}$. Vì vậy $a_1 = a - 2^{k_1}$. Khi đó $a_1$ gần 0 hơn $a$ (xem bài tập 1).

Pozny là $a_1 = 0$ hoặc $\|a_1\| = \frac{1}{2^{k_2}}$, trong đó $k_2 > k_1$. Polya $a_2 = a_1 - 2^{k_2}$, chúng ta lại nhận được $a_2 = 0$ hoặc $\|a_2\| = \frac{1}{2^{k_3}}$, trong đó $k_3 > k_2$, v.v. Do đó, một số $a_s$ bằng 0 và khi đó $a$ là tổng lũy ​​thừa của hai: $a = 2^{k_1} + 2^{k_2} + \dots + 2^{k_s}$ hoặc tất cả $a_s$ đều khác 0, sau đó tổng có dạng $2^{k_1} + 2^{k_2} + \dots + 2^{k_s}$ gần đúng với số $a$ chính xác như mong muốn. Trong trường hợp này, thật thuận tiện khi giả sử rằng $a$ bằng tổng vô hạn $a = 2^{k_1} + 2^{k_2} + \dots + 2^{k_s} + \dots$.

Sự định nghĩa. Cho $x_1, x_2, \dots, x_n$ là một dãy số hữu tỉ. Chúng ta sẽ nói rằng số hữu tỉ $a$ bằng tổng vô hạn $x_1 + x_2 + \dots + x_n + \dots$ nếu phép xét 2 adic giữa số $a$ và tổng hữu hạn $S_n = x_1 + \dots + x_n$ tiến tới 0 vì $n$ tiến tới vô cùng, tức là

$$\lim_{n \to \infty} \rho(a, S_n) = 0.$$

Trong thực tế, nếu $\|q\| < 1$ thì tổng vô hạn $a + aq + aq^2 + \dots + aq^n + \dots$ được xác định và bằng $\frac{a}{1 - q}$.

Chúng tôi đã chứng minh rằng mọi số hữu tỷ đều có thể được biểu diễn dưới dạng tổng hữu hạn $2^{k_1} + 2^{k_2} + \dots + 2^{k_n}$ ($k_1 < k_2 < \dots < k_n$) hoặc dưới dạng tổng vô hạn $2^{k_1} + 2^{k_2} + \dots + 2^{k_n} + \dots$ ($k_i$ là số nguyên, $k_1 < k_2 < \dots$). Trong cả hai trường hợp, biểu diễn này, mà chúng ta gọi là phân tách 2-Adic của số $a$, có thể được viết là $\varepsilon_k 2^k + \varepsilon_{k+1} 2^{k+1} + \dots + \varepsilon_{k+n} 2^{k+n} + \dots$, trong đó $k$ là một số nguyên và mỗi số $\varepsilon_{k+1}, \varepsilon_{k+2}, \dots, \varepsilon_{k+n}, \dots$ bằng 0 hoặc 1, với $\varepsilon_k = 1$. Các số $\varepsilon_k, \varepsilon_{k+1}, \dots$ được gọi là chữ số 2 adic của số $\frac{p}{q}$. Không khó để chứng minh rằng mọi số hữu tỷ đều có một và chỉ một phân tích 2 adic.

Bài tập 8. Chứng minh rằng $-1 = 1 + 2 + 2^2 + 2^3 + \dots + 2^n + \dots$,

$$\frac{1}{6} = 2^{-1} + 1 + 2^2 + 2^4 + \dots + 2^{2n} + \dots$$

Theo Bài tập 8, các chữ số 2 adic - 1 tạo thành dãy 1, 1, 1, ..., và các chữ số 2 adic của số $\frac{1}{6}$ tạo thành dãy 1, 1, 0, 1, 0, 1, 0, 1, ... Cả hai dãy thu được đều tuần hoàn. Có thể chứng minh rằng với mọi số hữu tỉ $\frac{p}{q}$ thì dãy gồm 2 chữ số adic là tuần hoàn *).

Để làm điều này, hãy xem xét chuỗi số $a_1, a_2, \dots, a_n, \dots$ được xác định bởi các đẳng thức $\frac{p}{q} - \varepsilon_k 2^k = \frac{a_1}{q} 2^{k+1}, \frac{p}{q} - (\varepsilon_k 2^k + \varepsilon_{k+1} 2^{k+1}) = \frac{a_2}{q} 2^{k+2}, \dots,$

$$\frac{p}{q} - (\varepsilon_k 2^k + \varepsilon_{k+1} 2^{k+1}) + \varepsilon_{k+1} 2^{k+1} = \frac{a_2}{q} 2^{k+2}, \dots,$$

$$\frac{p}{q} - (\varepsilon_k 2^k + \varepsilon_{k+1} 2^{k+1}) + \varepsilon_{k+1} 2^{k+1} = \frac{a_2}{q} 2^{k+2}, \dots,$$

$$\frac{p}{q} - (\varepsilon_k 2^k + \varepsilon_{k+1} 2^{k+1}) + \varepsilon_{k+1} 2^{k+1} = \frac{a_2}{q} 2^{k+2}, \dots,$$

Bây giờ hãy lưu ý rằng phép phân tách 2-adic của số $\frac{p}{q}$ có thể thu được từ phép phân tách 2-adic của số $\frac{a_n}{q}$ bằng cách nhân mỗi số hạng với

*) Theo nghĩa tương tự, một Periodine là một phân số thập phân biểu diễn một số hữu tỉ: một Periodine bắt đầu từ một vị trí nhất định.

⟦folio 30⟧

phần mở rộng cuối cùng thành $2^{k+n}$ và thêm $\varepsilon_k 2^k + \varepsilon_{k+1} 2^{k+1} + \dots + \varepsilon_{k+n-1} 2^{k+n-1}$ vào tổng kết quả.

Do đó, tính tuần hoàn của dãy $\varepsilon_k, \varepsilon_{k+1}, \varepsilon_{k+2}, \dots$ sẽ được thiết lập nếu chúng ta chứng minh rằng trong dãy $a_1, a_2, \dots, a_n, \dots$ một số nào đó xuất hiện hai lần. Trên thực tế, dãy $a_1, a_2, \dots, a_n, \dots$ bị giới hạn và vì các số hạng của nó là số nguyên nên chắc chắn sẽ có các số bằng nhau trong số chúng. Giới hạn của dãy này được thiết lập bởi chuỗi bất đẳng thức sau:

$$|a_n| = \left| \frac{p}{2^{k+n}} \right| - \left( \frac{\varepsilon_k}{2^n} + \frac{\varepsilon_{k+1}}{2^{n-1}} + \dots \right)$$

$$\dots + \frac{\varepsilon_k}{2^{n-1}} + \dots + \frac{1}{2} \left| q \right| \leqslant \left| \frac{p}{2^{k+n}} \right| + \left( \frac{1}{2^n} + \frac{1}{2^{n-1}} + \dots + \frac{1}{2} \right) \left| q \right| \leqslant \left| \frac{p}{2^{k+n}} \right| + \left| q \right|.$$

U Pravanice 9. Sử dụng kết quả của Bài tập 7, chứng minh rằng nếu $\varepsilon_k, \varepsilon_{k+1}, \varepsilon_{k+2}, \dots$ là một dãy tuần hoàn gồm các chữ số 0 và 1, thì tổng vô hạn $\varepsilon_k 2^k + \varepsilon_{k+1} 2^{k+1} + \varepsilon_{k+2} 2^{k+2} + \dots$ là phân tích 2 adic của một số hữu tỷ.

số 2 adic

Ngoài các khai triển tuần hoàn xác định các số hữu tỷ, chúng ta cũng có thể xem xét các khai triển không đạo hàm, coi như chúng xác định một số số mới. Những số này, cùng với các số hữu tỷ, tạo thành tập hợp $Q_2$, có các phần tử được gọi là số 2 adic.

Các phần tử từ $Q_2$ có thể được thêm theo cặp và một biến. Đây là cách nó được thực hiện. Hãy để $\alpha = \varepsilon_k 2^k + \varepsilon_{k+1} 2^{k+1} + \dots$ Chúng ta hãy viết $\alpha$ như một phân số vô hạn: $\alpha = \varepsilon_k \dots \varepsilon_0, \varepsilon_1 \varepsilon_2 \dots$.

Nếu có hai số từ $Q_2$ được viết theo cách này, thì tổng (sản lượng) của chúng phải được tính theo cách tương tự như tổng (sản lượng) của hai phân số vô hạn, nhưng có phép chuyển từ trái sang phải. (Ví dụ: xem Hình 4.) Chúng tôi không thể đi sâu vào vấn đề này chi tiết hơn và mời người đọc tự kiểm tra xem tổng và tích của các phần tử từ $Q_2$ lại cho một phần tử từ $Q_2$ và rằng các phép toán này có các tính chất chung cho phép nhân và phép cộng: chúng thỏa mãn các luật giao hoán, tổ hợp và phân phối.

Mô hình 2-adic và mở rộng đến $Q_2$:

$$\sum_{n \to \infty} x_n = 0, \text{ мо существуют}$$

$$\lim_{n \to \infty} \sum_{k=1}^{n} x_k = 0.$$

Pravanica có 13. Chứng minh đủ điều kiện $\lim_{n \to \infty} \sum_{k=1}^{n} x_k = 0.$

14. Chứng minh rằng tổng $1 \cdot 1! + 2 \cdot 2! + \dots + n \cdot n! + \dots$ được xác định và tìm giá trị của nó.

15. Chứng minh rằng nếu $x \in Q_2$ và $\|x\| \leqslant \frac{1}{2}$ thì tổng $\frac{x}{1} + \frac{x^2}{2} + \dots + \frac{x^n}{n} + \dots$ được xác định.

logarit 2-adic

Cuối cùng, chúng ta sẽ tạo hình dạng tự nhiên hơn cho lời giải bài toán #434*.

Để làm điều này, hãy xem xét hàm $L(x) = \frac{x}{1} + \frac{x^2}{2} + \dots + \frac{x^n}{n} + \dots$ được xác định trên tập hợp số 2 adic $x$ có mô đun tối đa là $\frac{1}{2}$ (xem)

*) Để biết điều kiện của bài toán này, hãy xem «Kvant» số 12 cho năm 1977.

⟦folio 31⟧

Với lời giải bài toán М434в chỉ cần chứng minh rằng $L(2)=0$ là đủ. Hãy giới thiệu một hàm khác bằng công thức $\log x=-L(1-x)$. Đẳng thức $L(2)=0$ có nghĩa là $\log(-1)=0$. Hàm logarit (được gọi là logarit 2 adicek) có tính chất cơ bản của logarit: $\log(xy)=\log x+\log y$. Từ tính chất này dễ dàng suy ra đẳng thức $\log(-1)=0$. Thật vậy, $\log 1=\log(1\times 1)=\log 1+\log 1=2\log 1$, từ đâu $\log 1=0$. Mặt khác, $\log 1=(\log(-1)\times(-1))=\log(-1)+\log(-1)=2\log(-1)$ và do đó $\log(-1)=0$. Logarit 2 adicec trong tập số 2 adicec đóng vai trò giống như logarit thường trong tập số thực. Logarit 2-adicec xác định những số $x$ mà $\|x\|=1$, vì trong trường hợp này là $\|1-x\| \leqslant \frac{1}{2}$. (Đặc biệt, chúng tôi xác định $\log(-1)$.) Đẳng thức mà lời giải dựa trên bài toán M434 trong «Kvant», trong giới hạn vì $n$ tiến tới vô cùng, có dạng $L(2x-x^2)-2L(x)=0$. Sự đẳng thức này cũng là hệ quả của tính chất cơ bản của logarit. Thật vậy, $L(2x-x^2)=-\log(1-x)^2=-2\log(1-x)=2L(x)$.

Bạn có thể làm quen với việc chứng minh tính chất chính của logarit 2 adicec và một số tính chất khác của số 2 adicec trong cuốn 3. I. Borevich và I. R. Shafarvich “Lý thuyết số”. Ngoài logarit, còn có các hàm tuyệt vời khác của biến 2 adice. Tuy nhiên, một trong những hàm này là hàm mũ - hàm được xác định bởi đẳng thức

$$\exp x=1+x+\frac{x^2}{2}+\dots+\frac{x^n}{n!}+\dots$$

Bài tập 16. Chứng minh rằng hàm mũ được xác định trên tập hợp các số có 2 vị trí $x$ thỏa mãn điều kiện tương tự như tính chất hàm mũ: $\exp(x+y)=\exp x\cdot\exp y$, $\exp(\log x)=x$, $\log(\exp x)=x$. (Những đẳng thức này hợp lệ đối với các giá trị của các biến mà chúng được xác định.)

Giống như việc xem xét 2-adiceco đã được xác định, việc sử dụng số nguyên tố tùy ý $p$ người ta có thể xác định việc xem xét $p$-adicece. Hóa ra là tất cả các cân nhắc giữa các số khác nhau đều tương đương với cân nhắc tổng quát hoặc một trong các cân nhắc $p$-Adicek. Nhưng đây là một chủ đề cho một câu chuyện khác.

Ứng dụng

Tất cả những gì chúng ta phải làm là chứng minh sự tồn tại của một tam giác có các đỉnh đủ ba màu. Hãy để chúng tôi xây dựng và chứng minh một tuyên bố tổng quát hơn:

Chia hình vuông OABC thành nhiều hình tam giác. Giả sử rằng các hình tam giác ở giữa được chia thành một hình có các đỉnh có cả ba màu, tức là trong mỗi hình tam giác được chia có hai đỉnh cùng màu. Vì mỗi liên kết nằm trên đường viền của hình vuông OABC nằm trên cạnh của một tam giác chia và mỗi liên kết nằm trên cạnh của hai tam giác chia, nên từ thực tế là mỗi tam giác chia có hai đỉnh cùng màu, suy ra rằng có một số chẵn liên kết loại 3K trên đường viền của hình vuông. Mặt khác, trên đoạn OC và BC không có liên kết nào như vậy, trên đoạn OA có số liên kết chẵn. Một sự mâu thuẫn đã thu được.
