---
id: 1980-2-vaguten-sopryazhennyie-chisla-8a46eaee
issue: kvant_1980_2
year: 1980
number: "2"
title: số liên hợp
authors:
  - Вагутен Н.
rubric: matematicheskiy-kruzhok
rubric_sub: Математический кружок
page_first: 28
page_last: 33
page_labels: 26, 28, 29, 30, 31
tag: 23LY
lang: vi
source: kvant_digital
extraction: vision
content_sha256: e4fbac87a58c6a057faf1f8794d1c99b760f0afc6004a32ccd34e3197ae2eae1
prompt_sha256: draft-1
translated_from: content/ru/1980/02/articles/10_vaguten-sopryazhennyie-chisla-8a46eaee.md
source_content_sha256: b885f798700a8cb8eeb774054181a25b6237201c2c555d529864a38f089532a8
translation_model: draft
translation_run: vi-draft-2026-10-31
translation_quality: draft
---

⟦folio 26⟧

vòng tròn toán học

N. Vaeuten

Cách chia số

Bạn có thể đọc bài viết này (hoặc tiến hành một bài học vòng tròn toán học dựa trên nó) theo nhiều cách khác nhau. Cách đơn giản nhất là phân tích cú pháp lời giải bài toán được đề xuất trong đó, bỏ qua phần in nhỏ, sau đó củng cố các kỹ thuật đã trình bày, khâu lại các bài tập gợi ý ở cuối bài. Nhưng nếu bạn quan tâm đến cái này cái kia bài toán hoặc bộ bài toán, bạn có thể làm khác: đọc kỹ văn bản đặt sau nó dưới dạng chữ in nhỏ và sử dụng tài liệu bổ sung do tác giả chỉ ra để hiểu sâu hơn bản chất của các vấn đề được nêu ra.

Người đọc có lẽ ngay từ cái nhìn đầu tiên đã nhận ra các bài toán hình học khó bài toán, được giải ngay lập tức bằng cách thay thế một điểm đã cho bằng một điểm khác, đối xứng với điểm đó so với một đường thẳng nào đó. Thông điệp đối xứng cũng rất quan trọng trong đại số.

Trong bài viết này, chúng ta sẽ xem xét một số tình huống trong đó việc thay thế một số dạng $a+b\sqrt{d}$ bằng liên hợp $a-b\sqrt{d}$ của nó sẽ rất hữu ích. Chúng ta sẽ thấy thủ thuật đơn giản này - thay đổi dấu trước dấu xuyên tâm - giúp ích như thế nào trong lời giải nhiều loại đại số và phân tích bài toán - từ các đánh giá và phép biến đổi chưa thực hiện được cho đến bài thi olympid khó bài toán và những phát minh tài tình của những người viết bài thi cạnh tranh.

Hầu hết các ví dụ của chúng tôi có thể đóng vai trò là người làm quen đầu tiên với các lý thuyết toán học toàn cầu (ở một số nơi, chúng tôi chỉ ra các bài báo và sách để tiếp tục làm quen). Trong số bài toán có trong bài viết, hai là từ Bài toán Kvant và một số là từ thư của những độc giả đã trải nghiệm cảm giác hài lòng với các thủ thuật với radial và iron và chia sẻ chúng với những người khác.

Các cặp số liên hợp xuất hiện khá tự nhiên khi chúng ta giải phương trình bậc hai không lấy nghiệm phân biệt: chẳng hạn phương trình $\lambda^2-\lambda-1=0$ có một cặp nghiệm “liên hợp”: $\lambda_1=\frac{1-\sqrt{5}}{2}$ và $\lambda_2=\frac{1+\sqrt{5}}{2}$. Chúng ta sẽ quay lại vấn đề này sau, nhưng hãy bắt đầu với những ví dụ thuộc loại khác: giải quyết vấn đề “chuyển khoản”...

⟦folio 28⟧

(tất nhiên ở đây chúng ta may mắn: hiệu của các bình phương $(2n+1)^2-4n(n+1)$ bằng 1)
$$\leq \frac{1}{(2\sqrt{n}+\sqrt{n})(2n+2n)} = \frac{1}{16n\sqrt{n}}.$$

Lưu ý rằng ước tính này cũng rất chính xác. Nhưng tốt hơn hết là bạn nên xác minh điều này (và nói chung là nghiên cứu hành vi của một hàm với các đa giác) không sử dụng các phép biến đổi đại số mà bằng phương pháp phân tích - thay thế biến $n$ bằng $h$ $1/n$ và sử dụng công thức Taylor $\sqrt{1+h} = 1+h/2 - h^2/8 + \dots$ (Xem [6]).

Thay thế phẳng bằng dấu trừ

Chúng ta đã nói về việc sử dụng tính đối xứng trong các bài toán hình học. Một dạng đối xứng trong đại số là thay mặt phẳng bằng dấu trừ.

Do đó, nếu bất kỳ biểu thức nào từ $\sqrt{d}$ bằng $p+q\sqrt{d}$ và chúng ta thay thế $\sqrt{d}$ bằng $-\sqrt{d}$ trong toàn bộ biểu thức này, thì điều tự nhiên là kỳ vọng rằng biểu thức mới sẽ bằng số liên hợp $p-q\sqrt{d}$. Chúng ta sẽ sử dụng trường hợp đặc biệt hiển nhiên sau đây của tính chất này ($a$ và $b$ là hợp lý, $\sqrt{d}$ thì không):

$$(a+b\sqrt{d})^n = p+q\sqrt{d} \Rightarrow (a-b\sqrt{d})^n = p-q\sqrt{d}.$$

5. Chứng minh rằng phương trình

$$(x+y\sqrt{5})^4+(z+t\sqrt{5})^4 = 2+\sqrt{5}$$

không có lời giải trong các số hữu tỉ $x, y, z, t$.

Tất nhiên, bạn có thể tìm tổng riêng của các số hạng ở vế trái không chứa $\sqrt{5}$ (nó phải bằng 2) và riêng hệ số $\sqrt{5}$ (nó phải bằng 1). Nhưng phải làm gì với hệ thống cồng kềnh vẫn chưa rõ ràng. Thay vào đó, hãy sử dụng (4) và thay dấu phẳng trước $\sqrt{5}$ bằng dấu trừ!

$$(x-y\sqrt{5})^4+(z-t\sqrt{5})^4 = 2-\sqrt{5}.$$

Có một số không âm ở bên trái, một số âm ở bên phải.

6. Chứng minh rằng có vô số cặp số tự nhiên $(x; y)$ mà $x^2$ khác $2y^2$ 1:

$$|x^2-2y^2| = 1.$$

Bạn có thể dễ dàng tìm thấy một số cặp có $(x; y)$ nhỏ bằng cách chọn lọc: đó là $(1; 2)$, $(3; 2)$, $(7; 5)$, $(17; 12)$, ... (Hình 1). Làm thế nào để tiếp tục bộ này? Có thể viết ra công thức tổng quát cho lời giải này không?

Cơm. 1. Liệu những hyperbol này có thể được mã hóa thông qua vô số nút thắt của tờ giấy ca-rô không?

Số $1+\sqrt{2}$ sẽ giúp chúng ta tìm được đáp số cho những câu hỏi này. Một mẫu cho phép bạn nhận được lời giải $(x; y)$ hoàn toàn mới, biểu thị trong bảng:

$$\begin{array}{c|c|c|c|c|c}
n & (1+\sqrt{2})^n & x_n & y_n & x_n^2-2y_n^2 & (1-\sqrt{2})^n \\
1 & 1+\sqrt{2} & 1 & 1 & 1-2=-1 & 1-\sqrt{2} \\
2 & 3+2\sqrt{2} & 3 & 2 & 9-8=1 & 3-2\sqrt{2} \\
3 & 7+5\sqrt{2} & 7 & 5 & 49-50=-1 & 7-5\sqrt{2} \\
4 & 17+12\sqrt{2} & 17 & 12 & 289-288=1 & 17-12\sqrt{2} \\
5 & 41+29\sqrt{2} & 41 & 29 & 1681-1682=-1 & 41-29\sqrt{2} \\
\dots & \dots & \dots & \dots & \dots & \dots \\
\end{array}$$

Dòng thứ sáu sẽ là gì?

Có thể thấy hệ số $x_n, y_n$ trong số $x_n+y_n\sqrt{2} = (1+\sqrt{2})^n$ sẽ cho ra cặp mong muốn. Bảng số liên hợp sẽ giúp chứng minh điều này (chúng ta lại sử dụng (4)):

$$x_n-y_n\sqrt{2} = (1-\sqrt{2})^n.$$

Thay đổi hai đẳng thức cuối, ta được

$$x_n^2-2y_n^2 = (1+\sqrt{2})^n(1-\sqrt{2})^n = \\
= ((1+\sqrt{2})(1-\sqrt{2}))^n = (-1)^n,$$

và biểu thức mà chúng ta quan tâm lần lượt bằng 1 hoặc - 1. Cộng và trừ hai đẳng thức giống nhau này, chúng ta thu được một biểu thức rõ ràng cho $x_n$ và $y_n$:

$$x_n = ((1+\sqrt{2})^n + (1-\sqrt{2})^n)/2$$

$$y_n = ((1+\sqrt{2})^n - (1-\sqrt{2})^n)/2\sqrt{2}.$$

⟦folio 29⟧

Có thể trong lời giải cái này bài toán về số nguyên, làm mà không có số vô tỷ $1 + \sqrt{2}$ Và $1 - \sqrt{2}$? Bây giờ đã biết đáp số, chúng ta có thể dễ dàng biểu diễn $(x_{n+1}; y_{n+1})$ qua cặp trước $(x_n; y_n)$ từ $x_{n+1} + y_{n+1}\sqrt{2} = (x_n + y_n\sqrt{2}) (1 - \sqrt{2})$ chảy ra

$$x_{n+1} = x_n + 2y_n, \quad y_{n+1} = x_n + y_n.$$ (6)

Trước mối quan hệ tái diễn này, rõ ràng là có thể đồng ý về một số giải pháp đầu tiên và sau đó kiểm tra xem

$$|x_n^2 - 2y_n^2| = |x_{n+1}^2 - 2y_{n+1}^2|.$$

Bằng cách thêm điều kiện ban đầu $x_1 = 1, y_1 = 1$, từ đây (bằng quy nạp), chúng ta có thể kết luận rằng $|x_n^2 - 2y_n^2| = 1$ với mọi $n$. Hơn nữa, bằng cách biểu thị $(x_n; y_n)$ ngược qua $(x_{n+1}; y_{n+1})$, “phương pháp giảm dần” ([8]), chúng ta có thể chứng minh rằng chuỗi tìm được có đầy đủ tất cả các phương trình lời giải (5) trong số tự nhiên $(x; y)$. Bất kỳ “phương trình Pell” $x^2 - dy^2 = c$ nào cũng có thể được giải theo cách tương tự (và bất kỳ phương trình bậc hai nào dưới dạng số nguyên $x, y$ đều có thể áp dụng cho phương trình thuộc loại tính chất này), nhưng phương trình ban đầu có thể có một số chuỗi được giải ([7]).

Mối quan hệ lặp lại loại (6) phát sinh không chỉ trong lý thuyết số mà còn trong các vấn đề khác nhau về phân tích và lý thuyết xác suất. Dưới đây là một ví dụ điển hình về tổ hợp bài toán thuộc loại này (nó đã được đề xuất ở lần tối ưu hóa quốc tế gần đây nhất ở London):

7(M595). Ở trên cùng $A$ của vosmtsuolnika bên phải có một con ếch. Từ bất kỳ đỉnh nào của đỉnh đó, ngoại trừ đỉnh $E$, đối diện $A$, nó có thể đi đến bất kỳ đỉnh nào trong hai đỉnh lân cận. Khi ở $E$, con ếch dừng lại và ở lại đó. Tìm đồng

Số $e_m$ cách khác nhau mà một con ếch có thể đi từ trên $A$ đến $E$ với chính xác $m$ lần nhảy.

Nếu bạn tô màu lần lượt các đỉnh của nút nhảy bằng màu đen và trắng (Hình 2), thì ngay lập tức bạn sẽ thấy rõ rằng $c_{2k-1} = 0$ đối với bất kỳ $k$ nào: màu của các đỉnh thay đổi sau mỗi lần nhảy. Chúng ta hãy biểu thị bằng $a_n$ và $c_n$ số cách mà một con ếch có thể, trong $2n$ nhảy, lần lượt đi từ đỉnh $A$ đến đỉnh $A$ và đến một trong các đỉnh $C$ (từ các thông điệp đối xứng, rõ ràng là ở mỗi đỉnh, được chỉ định trong hình bằng chữ cái $C$, bạn có thể nhận được số cách giống nhau). Cách kiểm tra dễ dàng (xem Hình 2a, b, c, f)),

$$a_1 = 2, \quad c_1 = 1;$$

$$a_{n+1} = 2a_n + 2c_n,$$

$$c_{n+1} = a_n + 2c_n.$$ (7)

Và con số chúng ta quan tâm $e_{2n}$ bằng nhau, rất nhiều, $2c_{n-1}$ (Hình 2d).

Làm cách nào chúng ta có thể tìm được công thức rõ ràng cho $a_n$ và $c_n$? Chúng ta hãy viết mối quan hệ truy hồi (7) như sau:

$$a_{n+1} + c_{n+1}\sqrt{2} = (a_n + c_n\sqrt{2}) (2 + \sqrt{2})$$ (8)

và - tất nhiên như bạn đã chứng minh - cũng như thế này:

$$a_{n+1} - c_{n+1}\sqrt{2} = (a_n - c_n\sqrt{2}) (2 + \sqrt{2}).$$ (9)

Từ đây, bằng quy nạp, thu được (7),

Cơm. 2. a) Chỉ có một cách để đi từ $A$ đến $C$ trong hai lần nhảy: $c_1 = 1$.

b) Có hai cách để đi từ $A$ đến $A$ trong hai lần nhảy: $a_1 = 2$.

c) $A$ có thể đạt được từ $C$ bằng hai cách

⟦folio 30⟧

Chúng tôi rạng rỡ:

$$a_n + c_n \sqrt{2} = (2 + \sqrt{2})^{n-1} (a_1 + c_1 \sqrt{2}) = (2 + \sqrt{2})^n;$$

$$a_n - c_n \sqrt{2} = (2 - \sqrt{2})^{n-1} (a_1 - c_1 \sqrt{2}) = (2 - \sqrt{2})^n.$$

Do đó, $c_n = [(2 + \sqrt{2}) - (2 - \sqrt{2})^n] : 2\sqrt{2}$ và vì $e_{2n} = 2c_{n-1}$, cuối cùng chúng ta nhận được

$$e_{2n} = [(2 + \sqrt{2})^{n-1} - (2 - \sqrt{2})^{n-1}] / \sqrt{2}; \quad e_{2n-1} = 0.$$

Bài toán lời giải. Chỉ chưa rõ làm thế nào trong bài toán này (và trong bài toán 6 trước đó) có thể đạt được các công thức chứa $\pm \sqrt{2}$ - trong bài toán giải pháp là về số nguyên! (Đối với những người tham gia và độc giả của Olympida, «Kvant» bài toán 7 đã trở nên dễ dàng hơn nhờ cách diễn đạt chỉ ra đáp số - «Kvant», 1979, Số 11, M595).

Tuy nhiên, “số liên hợp” sẽ xuất hiện hoàn toàn tự động nếu chúng ta biết phần đầu của đại số tuyến tính (xem [12]) và áp dụng các quy tắc chuẩn của khoa học này cho lời giải của phương trình (7). Các quy tắc này trước tiên đề xuất tìm ra những cấp số nhân nào ($a_n = a_0 \lambda^n$, $c_n = c_0 \lambda^n$) thỏa mãn mối quan hệ truy hồi cho trước. Các giá trị mà tiến trình cũng tồn tại - chúng được gọi là giá trị đặc trưng hoặc giá trị riêng - được xác định từ một phương trình nhất định (nó còn được gọi là đặc tính). Đối với (7), phương trình đặc tính có dạng $\lambda^2 + 2 - 4\lambda = 0$, nghiệm của nó chỉ là $2 + \sqrt{2}$ và $2 - \sqrt{2}$. Với những nghiệm này, chúng ta có thể thu được bất kỳ mối quan hệ lặp lại lời giải nào dưới dạng “kết hợp tuyến tính” của các cấp số nhân tương ứng ([11]). “Điều kiện ban đầu” (trong trường hợp của chúng tôi là $a_1 = 2$, $c_1 = 1$) xác định duy nhất lời giải mà chúng tôi cần.

Không thể tin được rằng ngay cả các dãy số nguyên hồi quy đơn giản nhất, trong đó các phương trình đặc trưng là bậc hai với các hệ số nguyên (ví dụ giống nhau (6) và (7) hoặc dãy Fibonacci 1, 1, 2, 3, 5, 8,..., $\Phi_{n+1} = \Phi_n + \Phi_{n-1}$ - xem [9], [10]), được biểu thị dưới dạng hàm của số, sử dụng các mống mắt vuông “được sắp xếp”.

Lưu ý rằng các số đặc trưng lớn xác định tốc độ tăng trưởng của chuỗi: đối với $n$ lớn trong bài toán $7e_n \approx (2 + \sqrt{2})^n / \sqrt{2}$. Bạn cũng có thể nói theo cách này: $\lim_{n \to \infty} (e_{n+1}/e_n) = 2 + \sqrt{2}$.

Đối với bài toán 6, chúng tôi thấy điều gì đó tương tự:

$$\lim_{n \to \infty} (x_n/y_n) = \sqrt{2}$$ - cho thấy cả hai số $x_n$ và $y_n$ đối với $n$ lớn thực tế bằng nhau. Chúng tôi thấy sự mở rộng thú vị của thực tế này trong bài toán tiếp theo với một số lượng lớn các lần chiếu sáng được “sắp xếp”.

Chúng tôi thay đổi tất cả các dấu hiệu một

8 (M520). Đặt $(1 + \sqrt{2} \Phi' \sqrt{3})^n = q_n + r_n \sqrt{2} + s_n \sqrt{3} + t_n \sqrt{6}$, trong đó $q_n, r_n, s_n$ và $t_n$ là số nguyên. Tìm giới hạn $\lim_{n \to \infty} r_n/q_n$, $\lim_{n \to \infty} s_n/q_n$, $\lim_{n \to \infty} t_n/q_n$.

Tất nhiên, ở đây chúng ta có thể biểu thị $(q_{n+1}; r_{n+1}; s_{n+1}; t_{n+1})$ dưới dạng $(q_n; r_n; s_n; t_n)$, dẫn đến $q_{n+1} + r_{n+1} \sqrt{2} + s_{n+1} \sqrt{3} + t_{n+1} \sqrt{6} = (1 + \sqrt{2} + \sqrt{3}) (q_n + r_n \sqrt{2} + s_n \sqrt{3} + t_n \sqrt{6}) = (1 + \sqrt{2} + 3)^n$.

Không khó để biết người khác sẽ như thế nào. Chúng ta hãy xem xét, cùng với số $\lambda_1 = 1 + \sqrt{2} + \sqrt{3}$ này, ba số "sắp xếp" nữa: $\lambda_2 = 1 - \sqrt{2} + \sqrt{3}$, $\lambda_3 = 1 + \sqrt{2} - \sqrt{3}$, $\lambda_4 = 1 - \sqrt{2} - \sqrt{3}$.

Chúng ta có thể biểu thị $q_n, r_n, s_n, t_n$ dưới dạng $\lambda_1, \lambda_2, \lambda_3, \lambda_4$:

$$q_n = (\lambda_1^2 + \lambda_2^2 + \lambda_3^2 + \lambda_4^2) / 4,$$

$$r_n = (\lambda_1^2 - \lambda_2^2 + \lambda_3^2 - \lambda_4^2) / 4\sqrt{2},$$

$$s_n = (\lambda_1^2 + \lambda_2^2 - \lambda_3^2 - \lambda_4^2) / 4\sqrt{3},$$

$$t_n = (\lambda_1^2 - \lambda_2^2 - \lambda_3^2 + \lambda_4^2) / 4\sqrt{6}.$$

Bây giờ hãy lưu ý rằng $\lambda_1 > |\lambda_2|$, $\lambda_1 > |\lambda_4|$. Hãy nghĩ về $\lim_{n \to \infty} r_n/q_n = \lim_{n \to \infty} s_n/q_n = 1/\sqrt{6}$.

Chúng ta đã nói ở trên rằng các số liên hợp $a \pm b\sqrt{d}$ phát sinh dưới dạng nghiệm của phương trình bậc hai với các hệ số nguyên. Liên quan đến nhiệm vụ cuối cùng, mong muốn này:

9. Viết phương trình với các hệ số nguyên, một trong các nghiệm của nó bằng $1 + \sqrt{2} + \sqrt{3}$.

Người ta nghi ngờ rằng cùng với số $λ_1$ này, phương trình có hệ số nguyên cũng được thỏa mãn bởi các liên hợp, mà trong lời giải trước bài toán chúng ta đã ký hiệu là $\lambda_2, \lambda_3, \lambda_4$. Phương trình cần tìm có thể được viết như sau:

$$(x - \lambda_1)(x - \lambda_2)(x - \lambda_3)(x - \lambda_4) = 0;$$

đó là

$$(x - 1 - \sqrt{2} - \sqrt{3})(x - 1 + \sqrt{2} - \sqrt{3}) \times (x - 1 - \sqrt{2} + \sqrt{3}) \times (x - 1 + \sqrt{2} + \sqrt{3}) = 0;$$

⟦folio 31⟧

sau khi biến đổi chúng ta nhận được

$$((x-1)^2-5-2\sqrt{6}) (x-1)^2-5+2\sqrt{6}) = 0,$$
$$(x^2-2x-4)^2-24 = 0,$$
$$x^4-4x^3-4x^2-16x-8 = 0.$$

Đây chính xác là phương trình hóa ra là một phương trình đặc trưng nếu chúng ta áp dụng phương trình được đề cập ở phần in nhỏ trên trang. 30 lý thuyết tổng quát để nghiên cứu phép biến đổi tuyến tính ($q_n; r_n; s_n; t_n) \rightarrow (q_{n+1}; r_{n+1}; s_{n+1}; t_{n+1}$) trong bài toán trước đó. Cũng lưu ý rằng chúng ta thực sự đã thu được một phương trình bậc tối thiểu (có lưu ý đến các hệ số) với nghiệm $\lambda_1 = 1 + \sqrt{2} + \sqrt{3}$. Hãy thử chứng minh điều đó!

tuần tự đại số

Chúng ta đã xem xét một số ví dụ liên quan đến các vấn đề ranh giới trong đại số, phép tính và lý thuyết số. (Mỗi hướng mà chúng tôi đã vạch ra có thể được dành cho một bài viết chi tiết hơn trong «Kvant»!) Để kết luận, chúng tôi cũng sẽ chỉ ra cách bạn có thể nhìn nhận các nhân vật chính của bài viết - “số liên hợp” - từ quan điểm đại số thuần túy.

Giả sử rằng chúng ta có một tập hợp các số $P$ (hoặc biểu thức có chữ cái hoặc một số phần tử khác) mà từ đó chúng ta có thể thực hiện các phép tính số học phù hợp với các quy tắc số học chung. Tập hợp như vậy được gọi là *field* (để biết định nghĩa chính xác, hãy xem danh sách ở trang 18); các trường dạng, ví dụ, số hữu tỉ và số thực. Giả sử, nếu phương trình $x^2-d=0$ không thể giải được trong trường $P$, thì chúng ta có thể mở rộng nó bằng cách xem xét các phần tử có dạng $p+q\sqrt{d}$, trong đó $p, q \in P$ và $\sqrt{d}$ là một ký hiệu mới, khi nhân với chính nó sẽ cho ra $d$, tức là $\sqrt{d}\sqrt{d}=d$, sao cho $(p+q\sqrt{d})(p'+q'\sqrt{d})=(pp'+qq'd)+(pq'+qp')\sqrt{d}$. Cấu trúc này, cho $d=2$ và $d=-1$, được mô tả chi tiết trong bài viết của S. Ashmanov trong số này «Kvant». Trong trường hợp thứ hai, tức là với $d=-1$, chúng ta mở rộng trường số thực và thu được số phức. Chúng tôi sẽ quay lại với họ trong số tiếp theo «Kvant».

Trường mới $P_1$—phần mở rộng hình vuông của trường $P$—có một ánh xạ thú vị $\lambda=p+q\sqrt{d} \rightarrow \lambda=p-q\sqrt{d}$ (một loại “đối xứng đại số”) được gọi là *tải*, với các thuộc tính sau:

1°. Tất cả các phần tử của trường cũ $P$ đều được chuyển sang chính chúng;
2°. Tất cả các đẳng thức chứa các phép toán số học được giữ nguyên trong ánh xạ này:

$$\lambda+\mu=\bar{\lambda}+\mu; \quad \lambda\mu=\lambda \cdot \mu.$$

Ánh xạ này là một phần của trường hợp được gọi là *tự đẳng cấu Galois* của phần mở rộng $P_1$ của trường $P$.

Trong Vấn đề 8 và 9, chúng ta đã thấy ví dụ về phần mở rộng “kép”—việc thêm $\sqrt{2}$ và sau đó $\sqrt{3}$—dẫn đến một trường có số lượng lớn Galois tự động: ngoài các điểm của ánh xạ hành động, đã có ba điểm trong số đó $(\sqrt{2} \rightarrow -\sqrt{2}, \sqrt{3} \rightarrow \sqrt{3}, \sqrt{2} \rightarrow \sqrt{2}, \sqrt{3} \rightarrow -\sqrt{3})$ và “tương tác” của chúng được sắp xếp theo cách giống như trong tập hợp các điểm tự căn chỉnh của một hình chữ nhật.

Hóa ra là nghiệm của bất kỳ phương trình đại số nào cũng có thể được thêm vào trường chính. Tự động cấu hình của một lĩnh vực mới xuất hiện - một trong những nhánh đại số đẹp nhất của thế kỷ 19-20, lý thuyết Galois, đặc biệt, cho phép nghiên cứu câu hỏi về khả năng giải được của một phương trình ở dạng căn ([13], [14]).

Chúng tôi sẽ kết thúc bài viết này bằng một bộ bài toán, về cơ bản là phần tiếp theo của các chủ đề đã được đề cập nhưng đôi khi yêu cầu thông báo mới và chúng tôi sẽ cung cấp danh sách tài liệu tham khảo.

Bài tập

1. Cái nào lớn hơn: $\sqrt{1979} + \sqrt{1980}$ hay $\sqrt{1978} + \sqrt{1981}$?
2. Hãy tìm điều đó cho mọi điều tích cực $x$
$$|\sqrt{x^2+1}-x-1/2x| < 1/8x^3.$$
3. Vẽ đồ thị hàm số $y=\sqrt{x^2-1}$ và chứng minh rằng với $|x| \ge 1$
$$0 < |x| - \sqrt{x^2-1} < 1/|x|.$$
4. Trong công thức $\sqrt{2}=1+\frac{1}{\sqrt{2}+1}$, chúng ta thay thế $\sqrt{2}$ ở bên phải (trong mẫu số), sử dụng cùng một công thức:
$$\sqrt{2}=1+\frac{1}{2+\frac{1}{\sqrt{2}+1}}.$$
Trong công thức này, một lần nữa thay đổi $\sqrt{2}$ thấp hơn thành $1+\frac{1}{\sqrt{2}+1}$, v.v. $n$ lần. Nếu bây giờ chúng ta đổi thành 1 hoặc 2, chúng ta sẽ có hai số hữu tỉ $p_n, q_n$. Chứng minh rằng $\sqrt{2}$ nằm giữa chúng và $\lim_{n \to \infty} q_n=\sqrt{2}$. (Không phải chúng ta sẽ nhúng số này vào một trong bài toán sao?)
5. Chứng minh rằng các phương trình a) $x^2-3y^2=1$, b) $x^2-3y^2=2$ có tập vô hạn lời giải là số nguyên.
6. Chứng minh rằng hàm $y=\ln(\sqrt{1+x^2}+x)$ là số lẻ và vẽ đồ thị.
7. a) Chứng minh rằng với mọi số tự nhiên $n$
