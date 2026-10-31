---
id: 1970-1-kolmogorov-chto-takoe-funktsiya-fa7fa494
issue: kvant_1970_1
year: 1970
number: "1"
title: chức năng là gì
authors:
  - Колмогоров А. Н.
rubric: osnovnye-stati
page_first: 29
page_last: 38
page_labels: 27-36
lang: vi
source: kvant_digital
extraction: vision
content_sha256: ba2bc11be75c79c8b980c5ac3754c05d7fd01df5ffa5de4a433a88aa62b059be
prompt_sha256: draft-1
translated_from: content/ru/1970/01/articles/07_kolmogorov-chto-takoe-funktsiya-fa7fa494.md
source_content_sha256: 7f487960b6dea9cf61443221bafdc4b86fa65d5887aaeec1ed4e83d5c8a71ed6
translation_model: draft
translation_run: vi-draft-gaps-2026-10-31
translation_quality: draft
---

⟦folio 27⟧

---
running_head:
folio:
---

A. N. KOLMOGOROV

Bài viết này tuyên bố hiện đại
hiểu biết chung về từ “chức năng”.
Bài viết không phải để dễ đọc:
nó đòi hỏi người đọc phải chú ý đến từng từ,
mặc dù nó không đòi hỏi bất kỳ kiến ​​thức đặc biệt nào,
ngoài trung học.
Điều này cũng có nghĩa
rằng người đọc biết cách xử lý từ ngữ
"tập hợp" và "phần tử của tập hợp".

1. GIỚI THIỆU

Đối với câu hỏi “Chức năng là gì?” Học sinh thường trả lời: “Một hàm có thể được xác định bằng bảng, đồ thị hoặc công thức”. Rõ ràng là điều này không chắc chắn. Nhưng những học sinh né tránh việc đưa ra một định nghĩa rõ ràng và ngay lập tức chuyển sang mô tả cách viết các hàm không hoàn toàn sai. Toán học không thể bắt đầu bằng các định nghĩa. Khi tôi đưa ra định nghĩa về một khái niệm nhất định, chắc chắn chúng ta sẽ sử dụng một số khái niệm khác trong chính định nghĩa này. Cho đến khi chúng ta hiểu được ý nghĩa của bất kỳ khái niệm nào, chúng ta sẽ không đi đến đâu và không thể hình thành một định nghĩa duy nhất. Do đó, việc trình bày bất kỳ lý thuyết toán học nào đều bắt đầu bằng việc một số khái niệm cơ bản được chấp nhận mà không cần định nghĩa. Bằng cách sử dụng chúng, người ta có thể xây dựng định nghĩa cho các khái niệm tùy ý hơn nữa.

Làm thế nào để mọi người truyền đạt cho nhau sự hiểu biết của họ về ý nghĩa của các khái niệm cơ bản? Không có cách nào khác để làm rõ điều này hơn là làm rõ bằng các ví dụ và với sự trợ giúp của mô tả chi tiết về đặc điểm thuộc tính của sự vật đang được xác định. Những mô tả này có thể không hoàn toàn rõ ràng chi tiết và lúc đầu có thể không đầy đủ. Nhưng dần dần từ chúng, ý nghĩa của khái niệm hiện lên đủ rõ ràng. Đây là cách chúng ta tiếp cận khái niệm hàm số, coi nó là một trong những khái niệm toán học cơ bản không có định nghĩa hình thức.

[Đúng, sau này người ta sẽ nói rằng một hàm không gì khác hơn là ánh xạ của tập hợp này lên tập hợp khác (miền định nghĩa của hàm lên tập hợp các giá trị của nó). Nhưng ở đây từ hiển thị chỉ đơn giản là từ đồng nghĩa với từ chức năng. Đây là hai tên cho cùng một khái niệm. Việc giải thích một từ bằng một từ khác có ý nghĩa tương đương không thể thay thế được định nghĩa về khái niệm mà nó thể hiện.]

⟦folio 28⟧

Ví dụ 1. Chúng ta sẽ giả sử rằng các chữ cái $x$ và $y$ là viết tắt của số thực. Dấu $\sqrt{1-x^2}$ sẽ được coi là dấu để trích xuất đối số của căn bậc hai. Bình đẳng

$$y = \sqrt{1-x^2}$$

chỉ ra rằng các điều kiện được đáp ứng

$$x^2 \leq 1, \quad y \geq 0, \quad x^2 + y^2 = 1.$$

Các điểm có tọa độ thỏa mãn các điều kiện này tạo thành hình bán nguyệt, được biểu thị bằng đường màu đỏ trong Hình 1.

Hình 1 làm rõ các sự kiện sau đây mà bạn có thể chứng minh hoàn toàn bằng đại số:

1) công thức (1) cho phép mọi $x$ thỏa mãn điều kiện

$$-1 \leq x \leq 1,$$

tính $y$ tương ứng, thỏa mãn bất đẳng thức (4), tương ứng với ít nhất một $x$ như vậy, mà theo công thức (1) tương ứng với $y$ đã cho.

Chúng ta có thể nói rằng công thức (1) chỉ định ánh xạ từ tập hợp số $x$ thỏa mãn bất đẳng thức (3) đến tập hợp số $y$ thỏa mãn bất đẳng thức (4). Các nhà toán học thường (đặc biệt là gần đây) sử dụng mũi tên để biểu thị ánh xạ. Ánh xạ mà chúng ta quan tâm có thể được viết bằng một mũi tên như thế này:

$$x \rightarrow \sqrt{1-x^2}.$$

Ví dụ:

$$\begin{align*}
-1 &\rightarrow \sqrt{1-(-1)^2} = 0, \\
-\frac{4}{5} &\rightarrow \sqrt{1-(-\frac{4}{5})^2} = \frac{3}{5}, \\
\frac{3}{5} &\rightarrow \sqrt{1-(\frac{3}{5})^2} = \frac{4}{5}, \\
0 &\rightarrow \sqrt{1-0^2} = 1.
\end{align*}$$

Lưu ý: ánh xạ được chỉ định đầy đủ nếu

a) cho tập hợp $E$, được hiển thị,

b) đối với mỗi phần tử $x$ của tập hợp $E$ này có một phần tử $y$ mà phần tử $x$ được ánh xạ.

Cơm. 1.

Cơm. 2.

⟦folio 29⟧

Tập hợp tất cả các giá trị của $y$ được ký hiệu bằng chữ cái $M$. Ví dụ 1, $E$ là tập hợp các số thỏa mãn điều kiện (3) và $M$ là tập hợp các số thỏa mãn điều kiện (4) *).

Ví dụ 2. Quy tắc

1) $x \to \sqrt{x^2}$,
2) $x \to \begin{cases} x, \text{ если } x \geqslant 0, \\ -x, \text{ если } x < 0 \end{cases}$

xác định ánh xạ tương tự

$$x \to |x|$$

(7)

số thực $x$ trên mô hình của chúng (giá trị tuyệt đối) $|x|$ (Hình 2).

Ánh xạ (7) hiển thị tập hợp tất cả các số thực

$$R = (-\infty, \infty)$$

cho nhiều người

$$R_+ = (0, \infty)$$

số thực không âm.

Thay vì ánh xạ từ, bạn có thể nói hàm và viết ánh xạ (5) như thế này:

$$f(x) = \sqrt{1-x^2},$$

(8)

và hiển thị (7) là như thế này:

$$f(x) = |x|.$$

(9)

Các giá trị riêng phần của hàm (8), được liệt kê trong công thức (6), khi đó sẽ được viết dưới dạng sau:

$$f(-1) = 0, \quad f\left(-\frac{4}{5}\right) = \frac{3}{5}, \quad f\left(\frac{3}{5}\right) = \frac{4}{5}, \quad f(0) = 1.$$

Miền xác định của hàm (9) là tập hợp tất cả các số thực $R$. Tập hợp các giá trị của nó là tập hợp $R_+$ các số thực không âm.

Ví dụ 3. Petya, Kolya, Sasha và Volodya sống trong phòng ký túc xá. Trong tháng 2, họ đặt lịch hoạt động sau:

| | 1 | 2 | 3 | 4 | 5 | 6 | 7 | 8 | 9 | 10 | 11 | 12 | 13 | . . . | 28 |
| :--- | :--- | :--- | :--- | :--- | :--- | :--- | :--- | :--- | :--- | :--- | :--- | :--- | :--- | :--- | :--- | :--- |
| Petya | ■ | | | | ■ | | | | ■ | | | | ■ | | . . . | |
| Kolya | ■ | | | | ■ | | | | ■ | | | | | | . . . | |
| Sasha | ■ | | | | ■ | | | | ■ | | | | | | . . . | |
| Volodya | ■ | | | ■ | | | | ■ | | | | | | | . . . | |

*) Một tập hợp có thể được ký hiệu bằng bất kỳ chữ cái nào. Ở đây chúng tôi lấy các chữ cái $E$ (từ từ trong tiếng Pháp - set) và $M$ (tiếng Đức - Menge; tình cờ từ tiếng Nga “set” bắt đầu bằng cùng một chữ cái). Nhưng điều này là không cần thiết: ​​trong ví dụ tiếp theo, chúng ta sẽ biểu thị tập hợp số thực, theo thông lệ, bằng chữ cái $R$ (gel Pháp - thực, thực).

⟦folio 30⟧

Sự giống nhau của bảng này với đồ thị hàm số quen thuộc với bạn trong khóa học đại số ở trường là điều đáng chú ý ngay lập tức. Liệu sự tương tự này có ý nghĩa logic chính xác? Các chàng trai ở đây đã thiết lập ánh xạ từ tập hợp này sang tập hợp khác chưa, nghĩa là họ đã xác định được chức năng nào đó chưa? Và không phải họ đã vẽ đồ thị của hàm này sao? (Hãy chú ý đến biểu thức hàng ngày “thiết lập đồ thị của hàm số”!)

2. KHÁI NIỆM CHUNG VỀ CHỨC NĂNG

Dễ dàng nhận thấy rằng ở ví dụ 3, một sĩ quan trực nào đó được phân công cho mỗi ngày trong số 28 ngày của tháng Hai. Nói cách khác, nhiều ngày trong tháng Hai được thể hiện ở nhiều chàng trai, chia sẻ trách nhiệm với nhau. Chúng ta có thể đồng ý rằng chữ x là viết tắt của bất kỳ ngày nào trong tháng 2 và y=f(x) là viết tắt của người trực vào ngày x. Không có lý do gì để từ chối hiển thị

ngày x→y = nhân viên trực ngày x

ở bên phải gọi nó là một hàm và viết ánh xạ này như thế này:

y=f(x).

Chúng ta sẽ gọi bất kỳ ánh xạ f a tập E nào lên tập M là một hàm có miền định nghĩa E và một tập hợp các giá trị M.

Đừng quên rằng khi chúng ta nói về việc ánh xạ f từ tập E sang tập M, chúng ta muốn nói rằng y=f(x) được xác định cho mọi x từ E và

Ánh xạ E tới M

Ánh xạ E tới M

chỉ với x từ tập hợp này và giá trị y của hàm f nhất thiết phải thuộc tập hợp M và mỗi y từ tập hợp M này là giá trị của hàm f đối với ít nhất một giá trị của đối số x.

Nếu chỉ biết rằng các giá trị của hàm f nhất thiết thuộc về tập M, nhưng không nói rằng mọi phần tử của tập hợp này là giá trị của hàm f, thì chúng ta nói rằng hàm ánh xạ miền định nghĩa E của nó vào tập M hoặc ánh xạ f là ánh xạ của tập E vào tập M.

Vì vậy, cần phân biệt chặt chẽ ý nghĩa của các biểu thức

"ánh xạ tới tập M"
“ánh xạ tới tập M”*).

*) Cũng lưu ý rằng mọi ánh xạ “trên” cũng có thể được gọi là ánh xạ “trong”, nhưng không phải ngược lại.

⟦folio 31⟧

Ví dụ như về hình ảnh

$$x \rightarrow |x|$$

chúng ta có thể nói rằng đó là bản đồ của $R$ đến $R$, nhưng chúng ta không thể nói rằng đó là “bản đồ của $R$ đến $R$”.

Từ quan điểm logic thuần túy, trường hợp đơn giản nhất là trường hợp miền định nghĩa của hàm là hữu hạn. Rõ ràng là một hàm có miền bao gồm các phần tử $n$ không thể nhận nhiều hơn $n$ các giá trị khác nhau. Do đó, các hàm xác định trên các tập hữu hạn thực hiện ánh xạ các tập hữu hạn lên các tập hữu hạn. Những hình ảnh như vậy là một trong những đối tượng nghiên cứu một phần quan trọng của toán học - tính toán (xem bài toán 8, 11, 18, 19).

Ví dụ 4. Xét các hàm có nhiều miền định nghĩa

$$M = \{A, B\}$$

gồm hai chữ cái $A$ và $B$ và có giá trị thuộc cùng một tập hợp, tức là các hình ảnh của tập hợp $M$ vào chính nó.

Chỉ có bốn chức năng như vậy. Hãy gán chúng vào các bảng theo cách sau:

| $x$ | $f_1(x)$ | $f_2(x)$ | $f_3(x)$ | $f_4(x)$ |
| :--- | :--- | :--- | :--- | :--- |
| $A$ | $A$ | $B$ | $A$ | $B$ |
| $B$ | $A$ | $B$ | $B$ | $A$ |

Các hàm $f_1$ và $f_2$ là các hằng số, tức là các hằng số: tập hợp các giá trị của mỗi hàm này bao gồm một phần tử duy nhất.

Các hàm $f_3$ và $f_4$ ánh xạ tập hợp $M$ vào chính nó. Hàm $f_3$ có thể được tính theo công thức

$$f_3(x) = x.$$

Đây là một khái niệm hình ảnh: mỗi phần tử của tập hợp $E$ được xử lý riêng lẻ.

Để hoàn thành việc làm rõ ý nghĩa của chính khái niệm “chức năng”, vẫn cần chú ý đến thực tế là việc lựa chọn các chữ cái để biểu thị một “biến độc lập”, tức là một phần tử xử lý tùy ý và một “biến phụ thuộc”, tức là một phần tử tùy ý của một tập hợp các giá trị, hoàn toàn không tồn tại. bài viết

$$x \rightarrow \sqrt{x}, \quad \xi \rightarrow \sqrt{\xi}, \quad y \rightarrow \sqrt{y},$$

$$f(x) = y = \sqrt{x}, \quad f(\xi) = \eta = \sqrt{\xi}, \quad f(y) = x = \sqrt{y}$$

xác định hàm tương tự $f$, xử lý một số không âm thành căn bậc hai số học của nó. Sử dụng bất kỳ mục nào trong số này, chúng tôi sẽ nhận được

$$f(1) = 1, \quad f(4) = 2, \quad f(9) = 3$$

vân vân.

⟦folio 32⟧

3. CHỨC NĂNG ĐẢO NGƯỢC

Chức năng

$$y = f(x)$$

được gọi là *có thể đảo ngược*), nếu mỗi giá trị phải mất một -
lần duy nhất. Đây là các hàm $f_3(x)$ và $f_4(x)$ từ ví dụ 4. Các hàm
$f_1(x)$ và $f_2(x)$ của Ví dụ 4 và các chức năng của Ví dụ 1, 2 và 3 là vô cơ.

Để chứng minh rằng bất kỳ hàm số nào là không thuận nghịch, chỉ cần chỉ ra
lấy hai giá trị bất kỳ của đối số $x_1 \neq x_2$ mà

$$f(x_1) = f(x_2).$$

Trong ví dụ 3, chỉ cần lưu ý rằng Petya trực cả ngày 1 và ngày 5 là đủ.
Tháng 2. Do đó, hàm của ví dụ 3 là không thể đảo ngược.

Ví dụ 5. Hàm $f$

$$x \xrightarrow{f} y = -\sqrt{x}$$

có thể đảo ngược. Nó được xác định trên tập $R_+$ các số không âm. Đa-
cử chỉ ý nghĩa của nó là vô số

$$R_- = (-\infty, 0]$$

mọi số không dương. Cho bất kỳ $y$ nào từ tập $R_-$, người ta có thể tìm thấy
tương ứng với $x$ theo công thức $x = y^2$.

Chức năng $g$

$$y \xrightarrow{g} x = y^2$$ tại $y \leqslant 0$

Có các hàm *nghịch đảo* với hàm $f$. Nó ánh xạ tập hợp $R_-$ tới tập hợp $R_+$. Như đã đề cập, không có sự lựa chọn chữ cái nào để biểu thị biến độc lập và biến phụ thuộc. Các hàm $f$ và $g$ có thể được viết là

$$f(x) = -\sqrt{x}$$ cho $x \geqslant 0$, $g(x) = x^2$ cho $x \leqslant 0$.

Hình 3 hiển thị đồ thị của các hàm nghịch đảo lẫn nhau $f$ và $g$.

Cơm. 3.

Cơm. 4.

*) Nguồn gốc của tên sẽ trở nên rõ ràng sau: một hàm có thể đảo ngược nếu có nó
có một hàm nghịch đảo.

⟦folio 33⟧

Ví dụ 6. Hàm $f$ cho bởi bảng

$$\begin{array}{c|cccc}
x & A & B & B & \Gamma \\
y = f(x) & 3 & 1 & 2 & 5 & 4
\end{array},$$

được xác định bởi tập hợp năm chữ cái đầu tiên của bảng chữ cái tiếng Nga và tập hợp các giá trị của nó là tập hợp năm số tự nhiên đầu tiên. Hàm nghịch đảo $g$ được cho bởi bảng

$$\begin{array}{c|cccc}
x & 1 & 2 & 3 & 4 & 5 \\
y = g(x) & B & B & A & D & \Gamma
\end{array}.$$

Hình 4 thể hiện đồ thị của các hàm này.

Hãy đưa ra những định nghĩa chính xác. Đặt $f$ là ánh xạ từ tập hợp $E$ đến tập hợp $M$. Nếu với bất kỳ phần tử $y$ nào từ tập hợp $M$ có một và chỉ một phần tử

$$x = g(y)$$

đặt $E$ cho cái nào

$$f(x) = y,$$

thì ánh xạ $f$ là nghịch đảo và

$$y \rightarrow x$$

được gọi là ánh xạ nghịch đảo với ánh xạ $f^*$.

Ánh xạ có thể đảo ngược của $E$ đến $M$

Ánh xạ có thể đảo ngược của $E$ đến $M$

Do đó, tính khả nghịch của ánh xạ $f$ có nghĩa là nó có ánh xạ nghịch đảo $g$. Nghịch đảo của $f$ thường được ký hiệu là $f^{-1}$. Ví dụ, nếu

$$f(x) = x^3,$$

Cái đó

$$f^{-1}(x) = \sqrt[3]{x}.$$

Vì từ “hàm” chỉ đơn giản là từ đồng nghĩa với từ “ánh xạ”, do đó chúng tôi đã xác định ý nghĩa của biểu thức “hàm nghịch đảo”.

*) Các ánh xạ như vậy còn được gọi là ánh xạ một-một $E$ lên $M$.

⟦folio 34⟧

Cố gắng lặp lại những gì đã nói ở trên, sử dụng từ “ánh xạ” cùng với từ “chức năng”.

Rõ ràng miền của hàm nghịch đảo $f^{-1}$ là tập các giá trị của hàm $f$, và tập các giá trị $f^{-1}$ là miền của hàm $f$.

Hàm nghịch đảo của hàm nghịch đảo $f^{-1}$ là hàm gốc $f$:

$$(f^{-1})^{-1} = f.$$

Do đó, các hàm $f$ và $f^{-1}$ luôn nghịch đảo lẫn nhau.

Ví dụ 7. Có những hàm nghịch đảo của chính chúng. Những chức năng như vậy

a) $f(x) = x,$
b) $f(x) = \frac{1}{x},$
b) $f(x) = \frac{x}{x-1}$.

Kiểm tra nó ra! Đồ thị của các hàm này được cho trong Hình 5. Lưu ý rằng tất cả các đồ thị này đều đối xứng qua đường phân giác của hình vuông thứ nhất và thứ ba, tức là đường thẳng $y=x$.

Chúng ta hãy mô tả sơ đồ sự tương ứng giữa các loại ánh xạ khác nhau từ tập hợp $A$ đến tập hợp $B$ và $A$ với tập hợp $B$.

Chúng ta hãy nhớ lại một lần nữa rằng khái niệm chung nhất là khái niệm ánh xạ $A$ đến $B$. Nếu với cách ánh xạ như vậy, hình ảnh $A$ trùng với $B$, thì chúng ta nói về ánh xạ $A$ lên $B$.

⟦folio 35⟧

Ánh xạ khả nghịch còn được gọi là ánh xạ một-một. Bạn sẽ thường xuyên gặp thuật ngữ này trong sách. Nhưng thông thường người ta không nói về “chức năng một-một”. Vì chúng tôi coi các từ “hàm” và “ánh xạ” là đồng nghĩa, cùng với các từ “một-một”, chúng tôi đã chọn sử dụng các từ “hàm được ánh xạ” hoặc tương tự như vậy, “ánh xạ được ánh xạ”.

Gần đây, thuật ngữ tiếng Pháp đã trở nên phổ biến trong văn học của chúng ta:

1) ánh xạ của $A$ đến $B$ được người Pháp gọi là “tính từ” hoặc “tính từ”;
2) các ánh xạ $A$ đến $B$ được gọi là "nội xạ" hoặc "nội xạ";
3) ánh xạ ánh xạ $A$ lên $B$ được gọi là "bijective" hoặc "bijections" trong thuật ngữ tiếng Pháp.

Xin lưu ý rằng với thái độ thăm viếng đối với việc sử dụng các giới từ “in” và “on” thì những thuật ngữ chung chung như vậy là không cần thiết.

3 ADAC

Những câu hỏi rất dễ được đánh dấu bằng số 0, bằng cách trả lời câu hỏi này, bạn có thể kiểm tra xem mình có hiểu nội dung được viết trong trạng thái hay không. Khó hơn bài toán được đánh dấu bằng dấu hoa thị. Không cần thiết phải giải quyết tất cả.

1. Giới thiệu

1.0. Tìm miền xác định và tập giá trị của các hàm sau:

a) $y = f(x) = \frac{1}{x^2}$, 6) $y = f(x) = \sqrt{x^2 - 1}$.

2. Phần nguyên của số $x$ là số nguyên lớn nhất không vượt quá $x$. Toàn bộ phần $x$ đại diện cho $[x]$. Ví dụ,

$$[0] = 0, [7,5] = [7] = 7, [-0,3] = -1, [-\pi] = -4.$$

Hiệu $x - [x]$ được gọi là phần phân số của số $x$ và biểu thị $\{x\}$. Vẽ đồ thị của các hàm số sau và tìm miền xác định và tập giá trị của chúng:

a) $f_1(x) = [x]$, 6) $f_2(x) = \{x\}$, b) $f_3(x) = \{x\} - \frac{1}{2}$, r) $f_4(x) = \left| \{x\} - \frac{1}{2} \right|$,

$$d^*) f_5(x) = \left[ \frac{1}{x} \right], e^*) f_6(x) = \frac{1}{[x]}, j^*) f_7(x) = \left\{ \frac{1}{x} \right\}, 3^*) f_8(x) = \frac{1}{[x]}.$$

3*. Đối với mọi số tự nhiên $n$, chúng ta định nghĩa $s(n)$ là tổng các ước của số $n$ (không tính chính $n$). Ví dụ,

$$s(1) = 0, s(2) = 1, s(6) = 6, s(12) = 16, s(28) = 28, \dots$$

Chứng minh rằng $s(n)$ không nhận giá trị 2 và 5.

2. Chức năng

4.0. Hai tổng thể ($A$ và $B$) có thể chia sẻ hai phòng theo bốn cách:

Bạn có thể sắp xếp bao nhiêu cách: a) hai người trong ba phòng, b) ba người trong hai phòng, b) ba người trong hai phòng sao cho không có phòng nào trống?

⟦folio 36⟧

5. Tập hợp $M$ bao gồm ba phần tử và tập hợp $N$ bao gồm hai phần tử. Có bao nhiêu ánh xạ: a) ánh xạ $M$ đến $N$, b) ánh xạ $M$ đến $N$, c) ánh xạ $N$ đến $M$, d) ánh xạ $N$ đến $M$?

6. Có bao nhiêu số điện thoại có bảy chữ số? Số nào chỉ được tạo thành từ các số 0, 1, 2 và 3?

7. Chứng minh rằng có hơn một triệu hàm số chỉ nhận hai giá trị 0 và 1 và được xác định trên tập hai mươi số tự nhiên đầu tiên.

8. Tập hợp $M$ bao gồm các phần tử $m$ và tập hợp $N$ bao gồm các phần tử $n$. Có bao nhiêu hàm được xác định trên tập hợp $M$ với các giá trị lấy $N$?

Cũng lưu ý e. Nhiệm vụ 8, 11, 18, 19 lấy bài toán tổ hợp làm một trong những nhiệm vụ chính. Chúng tôi trình bày chúng ở đây để chỉ ra rằng tổ hợp có mối liên hệ đáng kể với các bộ phận và liên quan đến việc đếm số ánh xạ của một hoặc một loại tập hữu hạn khác thành các tập hữu hạn.

9. Có bao nhiêu cách xếp chỗ: a) hai người ngồi trên hai chiếc ghế, b) ba người ngồi trên ba chiếc ghế, c) sáu người ngồi trên sáu chiếc ghế?

10. Tập hợp $E$ bao gồm sáu phần tử. Chứng minh rằng có đúng 720 hàm mà $E$ vừa là miền xác định vừa là tập giá trị.

11. Ánh xạ của một tập hữu hạn lên chính nó được gọi là tập con lạ. Số lượng hoán vị khác nhau của một tập hợp chỉ phụ thuộc vào số phần tử của nó $n$ và được ký hiệu là $n!$. Cho thấy điều đó

$$1! = 1, \ 2! = 2, \ 3! = 6, \ 4! = 24, \ 5! = 120, \ 6! = 720.$$

Hãy chỉ ra phương pháp chung để tính $n$!

3. Hàm nghịch đảo

12.0. Hàm số nào sau đây nghịch đảo và hàm số nào không nghịch đảo?

$$f_1(x) = x^3, \ f_2(x) = x^4, \ f_3(x) = x^{17}, \ f_4(x) = x^{18}$$

13. Trong lớp, mỗi cặp không quá hai người ngồi. Chúng ta hãy xếp mỗi học sinh ngồi cạnh bàn của mình, và nếu học sinh đó ngồi một mình thì chính anh ta. Sự trở lại sẽ là gì?

14. Đặt mỗi từ trong tiếng Nga có một từ tương ứng, được viết bằng các chữ cái giống nhau nhưng theo thứ tự ngược lại (một từ là một chuỗi các chữ cái). Hàm này có nghịch đảo không? Nếu có, hàm nghịch đảo là gì?

15. Ánh xạ của một tập hữu hạn lên chính nó luôn khả nghịch. Cho ví dụ về ánh xạ không nghịch đảo của một tập hợp số tự nhiên lên chính nó.

16. Chín khách du lịch phải được bố trí trên ba chiếc thuyền. Có bao nhiêu cách họ có thể làm điều này nếu yêu cầu a) mỗi thuyền có ba người, b) không nhiều hơn bốn và không ít hơn hai người trên mỗi thuyền, b) có ít nhất một khách du lịch trên mỗi thuyền? (Thuyền có số: Số 1, Số 2, Số 3.)

17*. Nếu chủ nhà có sinh viên, thì thông lệ không thể nói một sinh viên một khách: nhiều khách lại phản ánh ngược lại ở nhiều sinh viên. Nếu chỉ có sáu học sinh trong phòng, có bao nhiêu cách xếp chỗ cho họ: a) một khách, b) hai khách, c) bốn, d) gót chân, e) sáu khách?

18*. Ánh xạ nghịch đảo của một tập hữu hạn $M$ sang một tập hữu hạn khác $N$ được gọi là vị trí (khách được “đặt” trên ghế). Số ánh xạ của tập $M$ vào tập $N$ chỉ phụ thuộc vào số phần tử $m$ của tập $M$ và số $n$ phần tử của tập $N$ và được ký hiệu là $A_m^n$. Cho thấy điều đó

$$A_1^1 = 1, \ A_2^1 = A_2^2 = 2, \ A_3^1 = 3, \ A_3^2 = A_3^3 = 6, \ A_1^2 = 90,$$

và quy tắc chung để tính $A_n^m$ được thiết lập. Chứng minh rằng nó luôn bằng $A_n^{n-1} = A_n^n$.

19*. Nhiệm vụ 16c có thể được hình thành một cách trừu tượng: có bao nhiêu ánh xạ của một tập hợp các phần tử thứ chín lên một tập hợp gồm ba phần tử. Đặt $D_n^m$ biểu thị số ánh xạ của một tập hợp các phần tử $n$ lên một tập hợp các phần tử $m$. Kiểm tra xem

$$D_3^2 = 6, \ D_4^2 = 12, \ D_4^3 = 36, \ D_n^n = n!$$

Hãy thử quy tắc chung để tính $D_n^m$ (khó hơn bài toán một chút so với bài toán 8, 11 và 18).

20*. Có bao nhiêu hàm được xác định trên một tập hợp gồm 28 phần tử, nhận mỗi giá trị trong số bốn giá trị P, K, C và B sáu lần?

bài toán này nói về số cách phân bổ công bằng nhiệm vụ trong tháng 2 giữa Petya, Kolya, Sasha và Volodya (ví dụ 3 ở trang 29).
