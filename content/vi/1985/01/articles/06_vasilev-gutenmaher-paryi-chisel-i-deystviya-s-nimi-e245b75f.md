---
id: 1985-1-vasilev-gutenmaher-paryi-chisel-i-deystviya-s-nimi-e245b75f
issue: kvant_1985_1
year: 1985
number: "1"
title: Các cặp số và phép tính với chúng
authors:
  - Васильев Н. Б.
  - Гутенмахер В. Л.
rubric: matematicheskiy-kruzhok
rubric_sub: Математический кружок
page_first: 21
page_last: 26
page_labels: 19-24
tag: HH1D
lang: vi
source: kvant_digital
extraction: vision
content_sha256: d901105f8616d3afae56eae0dac097c7cc2724598a1b738e810fdec7577ef7fd
prompt_sha256: draft-1
translated_from: content/ru/1985/01/articles/06_vasilev-gutenmaher-paryi-chisel-i-deystviya-s-nimi-e245b75f.md
source_content_sha256: 0383909d75b630b1d933be0e11ef0566b10080d78310c209ded62cec868496f7
translation_model: draft
translation_run: vi-draft-2026-10-31
translation_quality: draft
---

⟦folio 19⟧

Các cặp số và phép tính với chúng

Ứng viên Khoa học Vật lý và Toán học
N. V. VASILIEV,
Ứng viên Khoa học Vật lý và Toán học
V. L. GUTENMACHER

Nội dung bài viết này chủ yếu dành cho học sinh lớp một. Tuy nhiên, chúng tôi cũng khuyên dùng nó cho học sinh trung học. Bài viết đề cập đến cách giải phương trình hai biến số nguyên. Về vấn đề này, các quy tắc khác nhau để nhân các cặp số đã được xem xét, bao gồm cả phép nhân số phức.

1. Phương trình $ax - by = c$
bằng số nguyên
Xét phương trình
$$8x - 5y = 19.$$

Lấy phương trình này làm ví dụ, chúng ta sẽ trình bày phương pháp lời giải trên các phương trình tuyến tính số nguyên có dạng $ax - by = c$ với các số nguyên $a, b$ và $c$.

Vì $8 \cdot 3 - 5 \cdot 1 = 19$ nên cặp số $x = 3, y = 1$ là nghiệm của phương trình ban đầu. Chúng tôi đã tìm thấy lời giải này bằng cách lựa chọn đơn giản.

Bây giờ chúng ta hãy chỉ ra cách, khi có một lời giải, chúng ta có thể viết ra tất cả các lời giải khác (có vô số các số đó). Trừ đẳng thức $8 \cdot 3 - 5 \cdot 1 = 19$ khỏi phương trình $8x - 5y = 19$, chúng ta thu được $8(x - 3) - 5(y - 1) = 0$ hoặc $x - 3 = 5(y - 1)/8$. Từ đẳng thức cuối cùng, rõ ràng số $x - 3$ sẽ là số nguyên khi và chỉ khi $y - 1$ chia hết cho 8, tức là $y - 1 = 8n$, trong đó $n$ là số nguyên nào đó. Thay $y - 1 = 8n$ vào tử số của phân số $5(y - 1)/8$ và giảm đi 8, ta được $x - 3 = 5n$.

Do đó, tất cả các số nguyên lời giải của phương trình ban đầu có thể được viết dưới dạng sau:

$$\begin{cases} x = 3 + 5n, \\ y = 1 + 8n, \end{cases}$$

hoặc $(x/y) = \frac{3}{1} + n\frac{5}{8}$;

ở đây $n$ là số nguyên bất kỳ.

Loại ký hiệu thứ hai sẽ được giải thích chi tiết trong đoạn tiếp theo, nhưng bây giờ chúng tôi lưu ý rằng cùng một phương pháp tạo ra công thức cho tất cả các số nguyên lời giải của bất kỳ phương trình nào $ax - by = c$ (trong đó $a$ và $b$ là các số nguyên tố cùng nhau):

$$(x/y) = \left( \frac{x_0}{y_0} \right) + n\left( \frac{b}{a} \right),$$

trong đó $(x_0; y_0)$ là một trong các số nguyên bất kỳ của nó lời giải.

Đối với lời giải được đề xuất dưới đây bài toán, người ta phải ghi nhớ những điểm sau. Nếu các số nguyên $a$ và $b$ có ước chung (trừ 1 và -1), thì chúng ta phải chia tất cả các phương trình số nguyên cho ước số chung nhất của chúng. Trong trường hợp $c$ không chia hết cho nó, phương trình rõ ràng không có số nguyên lời giải, và trong trường hợp nó chia hết, thì tồn tại lời giải - bạn chỉ cần chọn một lời giải và viết tất cả phần còn lại bằng công thức (*).

Đối với mọi số $a$ và $b$, có một phương pháp chung để tìm một phương trình lời giải: phương pháp này dựa trên thuật toán Euclide (xem [1] và [5]).

Nhiệm vụ và

1. Các phương trình sau có lời giải ở dạng số nguyên: a) $7x - 5y = 0$; b) $7x - 5y = 1$; b) $15x - 9y = 6$; d) $39x - 63y = 47$?

Nếu phương trình có lời giải, hãy chỉ ra một trong số chúng và viết ra tất cả lời giải của nó bằng công thức tổng quát.

2. Có bao nhiêu lời giải trong số tự nhiên (số nguyên dương) $x, y$ có các phương trình: a) $19x + 85y = 1985$; b) $7x + 5y = 99$?

3*. Máy tạo ra các vết màu xanh trên một cuộn băng dài 2 m tính từ điểm bắt đầu cứ sau 7 cm và các dấu màu đỏ cũng ở điểm bắt đầu cứ sau 5 cm. Bao nhiêu lần vạch sáng và vạch đỏ cách nhau 1 cm?

2. Các cặp số

Nếu phương trình có một biến $x$ biểu thị các số riêng lẻ thì phương trình có hai biến $x$ và $y$ đã là cặp số. Trong đoạn trước, chúng tôi đã chỉ ra cách từ một phương trình lời giải số nguyên $ax - by = c$ để thu được tất cả lời giải còn lại: bạn cần thêm vào một trong các lời giải của nó - một cặp số $(x_0; y_0)$ - một cặp số $(b; a)$, nhân với một số nguyên. Bây giờ chúng ta sẽ đưa ra ý nghĩa chính xác của việc cộng các cặp số và nhân chúng với các số.

Để rõ ràng hơn, chúng ta viết các cặp số $(x; y)$ dưới dạng cột $(x/y)$; và bản thân các số $x$ và $y$ sẽ lần lượt được gọi là thành phần thứ nhất và thứ hai của một cặp (cột) nhất định. (Không cần cột $(x/y)$ với phân số $\frac{x}{y}$!)

⟦folio 20⟧

Hai số nhiều như vậy được coi là bằng nhau khi và chỉ khi các thành phần của chúng bằng nhau:

$$\binom{x_1}{y_1} = \binom{x_2}{y_2},$$

chỉ khi $\begin{cases} x_1 = x_2, \\ y_1 = y_2. \end{cases}$

Thêm hai rất nhiều có nghĩa là thêm các thành phần của chúng:

hãy để $u = \binom{x_1}{y_1}, v = \binom{x_2}{y_2},$

thì $u + v = \binom{x_1 + x_2}{y_1 + y_2}$.

Vì việc thay đổi vị trí của các số hạng không làm thay đổi tổng của các số: $a + b = b + a$, nên có thể nói điều tương tự về rất nhiều số: $u + v = v + u$. Đối với rất nhiều người, quy tắc $(u + v) + w = u + (v + w)$ cũng đúng.

Nhân rất nhiều $u$ với số $k$ có nghĩa là nhân cả hai thành phần của nó với $k$:

nếu $u = \binom{x}{y},$ thì $ku = \binom{kx}{ky}$.

Một vai trò đặc biệt, tương tự như vai trò của số 0 đối với các số, được đóng bởi số 0 $\binom{0}{0}$ đối với các số. Nếu điều này không gây nhầm lẫn thì nó cũng được ký hiệu là “0”. Với mọi số $u$ đẳng thức $u + 0 = u$ đều đúng.

Có vẻ tự nhiên khi giới thiệu phép nhân như sau:

$$\binom{x_1}{y_1} \binom{x_2}{y_2} = \binom{x_1 x_2}{y_1 y_2}.$$

Đối với phép nhân như vậy, tất cả các tính chất tương tự đều được đáp ứng như đối với phép nhân số: 1) $uv = vu$, 2) $u(vw) = (uv)w$, 3) $(u + v)w = uw + vw$. Rất nhiều người đóng vai “một” $e = \binom{1}{1}$.

Nhưng không giống như các con số, việc chia cho số 0 không phải lúc nào cũng thực hiện được. Ví dụ: nếu $u = \binom{1}{0}$ thì không có nhiều $v$ bằng $uv = e$.

Ở cuối bài viết, chúng ta sẽ làm quen với các quy tắc khác, hóa ra, cũng tự nhiên và có ý nghĩa hơn để nhân các cặp số:

$$\binom{x_1}{y_1} \binom{x_2}{y_2} = \binom{x_1 x_2 - y_1 y_2}{x_1 y_2 + x_2 y_1}.$$

Quy tắc này có thể thay thế được vì nó luôn thực hiện được phép toán nghịch đảo - chia cho 0.

Một cặp số $(x; y)$, được viết không nhiều mà viết thành một dòng, thường được dùng để biểu thị tọa độ của một điểm trên mặt phẳng tọa độ $Oxy$. Phương pháp tọa độ cho phép chúng ta kết nối đại số với hình học. Vì vậy, ví dụ, phương trình $ax - by = c$ tương ứng với một đường thẳng trên mặt phẳng tọa độ và số nguyên lời giải của phương trình này tương ứng với các điểm có tọa độ nguyên (Hình 1). Sử dụng các quy tắc cộng các cặp số và nhân chúng với một số, bạn có thể viết công thức tính tọa độ của một điểm trên một đường thẳng, ví dụ: nếu $A = (x_1; y_1), B = (x_2; y_2)$ là hai điểm thì điểm đó

$$C = \frac{1}{2} \left( (x_1; y_1) + (x_2; y_2) \right) =$$

$$= \left( \frac{x_1 + x_2}{2}; \frac{y_1 + y_2}{2} \right)$$

— phần giữa của đoạn $AB$.

Nhiệm vụ và
4. Rất nhiều dữ liệu

$$u = \binom{7}{-1}, v = \binom{-2}{5}, w = \binom{1}{3}.$$

Tìm các số sau: a) $2u$; b) $2u - v$; b) $u + 2v - 3w$.

5. Tìm các số $x$ và $y$ thỏa mãn đẳng thức

$$x \binom{-7}{-1} + y \binom{-2}{5} = \binom{1}{3}.$$

So sánh kết quả với 4c).

6. a) Gọi các điểm đã cho là $A = (7; -1)$ và $B = (-2; 5)$. Tìm tọa độ của điểm $C = (x; y)$ sao cho $B$ là trung điểm của đoạn $AC$. 6) Tìm tọa độ của các điểm $D$ và $E$, chia đoạn $AB$ thành ba phần bằng nhau.

3. Phương trình $x^2 - dy^2 = 1$ trong số nguyên

Trong đoạn đầu tiên, chúng tôi đã chỉ ra cách, bắt đầu từ một phương trình lời giải $ax - by = c$, chúng ta có thể thu được và viết một chuỗi vô hạn của lời giải của nó. Chúng ta sẽ nhận được kết quả tương tự cho phương trình $x^2 - dy^2 = 1$, trong đó $d$ là số tự nhiên không phải là số chính phương. Nhưng điều này sẽ đòi hỏi phương pháp phức tạp hơn của riêng bạn. Chúng ta sẽ chứng minh điều đó bằng cách sử dụng ví dụ về phương trình

$$x^2 - 2y^2 = 1.$$

Phương trình này có rất lời giải (1; 0) và (-1; 0). Rõ ràng là nếu $(x; y)$ là các phương trình lời giải thì $(-x; y), (x; -y)$ và $(-x; -y)$ cũng là lời giải. Do đó, chúng ta có thể hạn chế chỉ tìm kiếm tích cực (tự nhiên) lời giải. Đây là hai lời giải: (3; 2), (17; 12) - cái xa nhất trong

⟦folio 21⟧

Khó thăng tiến ở Nhật Bản.

Con số chơi $\sqrt{2}$ hóa ra lại là một trợ giúp bất ngờ ở đây. Người dùng, sử dụng danh tính $a^2 - b^2 = (a + b)(a - b)$, chúng tôi phân tích vế trái của phương trình $x^2 - 2y^2 = 1$

$(x + y\sqrt{2}) (x - y\sqrt{2}) = 1$

và thay thế lời giải đầu tiên của chúng ta bằng số tự nhiên $x = 3, y = 2$:

$(3 + 2\sqrt{2}) (3 - 2\sqrt{2}) = 1.$

Hóa ra là lời giải thứ hai có thể đạt được nếu sử dụng nhận dạng $(a + b)^2 = a^2 + 2ab + b^2$, chúng ta bình phương số $3 + 2\sqrt{2}$ (hoặc $3 - 2\sqrt{2}$):

$(3 + 2\sqrt{2})^2 = 9 + 12\sqrt{2} + 8 = 17 + 12\sqrt{2},$

$(3 - 2\sqrt{2})^2 = 9 - 12\sqrt{2} + 8 = 17 - 12\sqrt{2}.$

Cặp (17; 12) là lời giải thứ hai. Hãy kiểm tra điều này như sau. Hãy bình phương cả hai vế của đẳng thức đúng (2):

$(3 + 2\sqrt{2})^2 (3 - 2\sqrt{2})^2 = 1$

và chúng tôi nhận được

$(17 + 12\sqrt{2}) (17 - 12\sqrt{2}) = 1$, hoặc

$17^2 - 2 \cdot 12^2 = 1.$

Bạn có thể nhận được lời giải mới tiếp theo bằng cách lập phương số $3 + 2\sqrt{2}$:

$(3 + 2\sqrt{2})^3 = (3 + 2\sqrt{2})^2 (3 + 2\sqrt{2}) = 99 + 70\sqrt{2}.$

Theo cách tương tự, chúng ta thu được $(3 - 2\sqrt{2})^3 = 99 - 70\sqrt{2}$. Vì $(3 + 2\sqrt{2})^3 (3 - 2\sqrt{2})^3 = 1$ nên ta có $(99 + 70\sqrt{2}) (99 - 70\sqrt{2}) = 99^2 - 70^2 \cdot 2 = 1$, tức là $(99; 70)$ cũng là lời giải của phương trình $x^2 - 2y^2 = 1.$

Bây giờ, có lẽ, cách để có được lời giải mới đã rõ ràng - chúng ta phải tiếp tục nâng $3 + 2\sqrt{2}$ lên lũy thừa, nghĩa là nếu

$(3 + 2\sqrt{2})^n = x_n + y_n\sqrt{2},$

trong đó $x_n$ và $y_n$ là các số tự nhiên thì cặp $(x_n; y_n)$ là nghiệm của phương trình $x^2 - 2y^2 = 1$. Có thể chứng minh rằng phương pháp này cho tất cả lời giải của nó dưới dạng số tự nhiên.

Bây giờ chúng ta hãy xem xét các phương trình tổng quát hơn có dạng này:

$x^2 - dy^2 = 1,$

trong đó $d$ là số tự nhiên không phải là số chính phương.

Hóa ra tất cả lời giải của nó trong số tự nhiên đều thu được bằng cùng một phương pháp. Hãy đoán ít nhất là lời giải $(x_0; y_0)$ và nâng số $x_0 + y_0\sqrt{d}$ lên lũy thừa $n$:

$(x_0 + y_0\sqrt{d})^n = x_n + y_n\sqrt{d}.$

(Giải pháp nhỏ nhất là lời giải $(x_0; y_0)$ sao cho đối với bất kỳ lời giải $(x; y)$ nào khác thì bất đẳng thức $x_0 + y_0\sqrt{d} < x + y\sqrt{d}$ đúng.)

Đối với mọi số $d$ đều có phương pháp chung để tìm số tự nhiên nhỏ nhất lời giải, dựa trên việc phân tách số thành phân số nguyên (xem [1] và [2]).

Nhiệm vụ 1.

7*. Tìm số chẵn lời giải trong các số tự nhiên của phương trình: a) $x^2 - 3y^2 = 1$; b) $x^2 - 5y^2 = 1$; b) $x^2 - 2y^2 = -1$.

8*. Chứng minh rằng

$x_n = \frac{1}{2} ((3 + 2\sqrt{2})^n + (3 - 2\sqrt{2})^n),$

$y_n = \frac{1}{2\sqrt{2}} ((3 + 2\sqrt{2})^n - (3 - 2\sqrt{2})^n) -$

các số nguyên thỏa mãn phương trình $x^2 - 2y^2 = 1$, a) với $n = 1, 2, 3, 6$ với mọi số tự nhiên $n$.

9. Tìm tất cả các phương trình số nguyên lời giải $x^2 - 4y^2 = 13$.

10*. Chứng minh rằng phương trình $x^2 - 3y^2 = -1$ không có lời giải ở dạng số nguyên.

4. Số có dạng $p + q\sqrt{2}$

Chúng ta hãy chú ý đến một tình huống thú vị là các số có dạng $p + q\sqrt{2}$ với số không đồng nhất $p$ và $q$ có ​​thể được liên kết một cách tự nhiên với một cặp số $(p; q)$. Hơn nữa, sự bằng nhau của hai số $p_1 + q_1\sqrt{2} = p_2 + q_2\sqrt{2}$ xảy ra khi và chỉ khi $\binom{p_1}{q_1} = \binom{p_2}{q_2}$.

Thật vậy, đặt $p_1 + q_1\sqrt{2} = p_2 + q_2\sqrt{2}$ và $q_1 \neq q_2$; thì hóa ra $\sqrt{2}$ bằng số $(p_1 - p_2)/(q_2 - q_1)$, nhưng điều này là sai. Do đó, đẳng thức $q_1 = q_2$ phải được giữ; nhưng sau đó từ đẳng thức $p_1 + q_1\sqrt{2} = p_2 + q_2\sqrt{2}$ ta thu được ngay $p_1 = p_2$ đó.

⟦folio 22⟧

Quy tắc cộng số $p_1 + q_1\sqrt{2}$ và $p_2 + q_2\sqrt{2}$ tương tự như đối với stolniki:
$$p_1 + q_1\sqrt{2} + (p_2 + q_2\sqrt{2}) = (p_1 + p_2) + (q_1 + q_2)\sqrt{2},$$
$$\binom{p_1}{q_1} + \binom{p_2}{q_2} = \binom{p_1 + p_2}{q_1 + q_2}.$$

Bây giờ các số biến $p_1 + q_1\sqrt{2}$ và $p_2 + q_2\sqrt{2}$:
$$p_1 + q_1\sqrt{2}(p_2 + q_2\sqrt{2}) = (p_1 + p_2) + (q_1 + q_2)\sqrt{2}.$$
Kết quả là, chúng ta thu được một số có dạng giống nhau và thu được quy tắc nhân mới cho các số có số phức hữu tỉ $p_1, q_1, p_2, q_2$:
$$\binom{p_1}{q_1}\binom{p_2}{q_2} = \binom{p_1 p_2 + 2 q_1 q_2}{p_1 q_2 + p_2 q_1}.$$

(3)

Nếu bạn tuân theo quy tắc này, bạn có thể viết lời giải phép nhân $x^2 - 2y^2 = 1$ như thế này:
$$\binom{x_n}{y_n} = \binom{3}{2}^n$$ (tự cân stolnik $n$ lần).

Đối với quy tắc (3), tính chất chung của phép nhân được thỏa mãn; vai trò của một người ở đây do stolnik $\binom{1}{0}$ đảm nhận, vì nó tương ứng với số $1 = 1 + 0\sqrt{2}$.

Sự đối xứng thú vị trong tập hợp các số như vậy giúp ích rất nhiều khi thao tác với các số $p + q\sqrt{2}$: mỗi số $a = p + q\sqrt{2}$ tương ứng với số $\bar{a} = p - q\sqrt{2}$, gọi là liên hợp với $a$. (Đối với stolnik, sự chuyển đổi sang liên hợp chỉ đơn giản là sự thay đổi dấu $y$ của thành phần thứ hai.)

Hoạt động ghép nối có các thuộc tính sau:
$$\bar{a} + \bar{b} = \bar{a} + \bar{b}, \bar{a}\bar{b} = \bar{a}\bar{b}, \bar{a} = a.$$

Nhưng điều quan trọng nhất là tích của liên hợp $(p + q\sqrt{2})(p - q\sqrt{2}) = p^2 - 2q^2$ không còn chứa $\sqrt{2}$; $\bar{a}\bar{b}$ là một số hữu tỉ. Điều này cho phép bạn chia các số có dạng $p + q\sqrt{2}$ cho nhau, từ đó thu được một số có cùng dạng. Để chia $\beta$ cho $a$, chỉ cần nhân $\beta$ với $\bar{a}$ và chia kết quả cho $\bar{a}\bar{b}$.

Chúng ta đã sử dụng các tham số của số liên hợp cho phép nhân lời giải $x^2 - 2y^2 = 1$. Chúng ta biểu diễn vế trái $x^2 - 2y^2$ là tích của hai số liên hợp
$$a = x + y\sqrt{2}, \bar{a} = x - y\sqrt{2}.$$

Bây giờ chúng ta lấy hai số $a = x_1 + y_1\sqrt{2}$ và $\beta = x_2 + y_2\sqrt{2}$ và liên hợp của chúng $\bar{a} = x_1 - y_1\sqrt{2}$ và $\bar{b} = x_2 - y_2\sqrt{2}$. Hãy cùng ngắm nhìn sản phẩm $\alpha\bar{a}\beta\bar{b}$. Thực hiện phép tính theo một thứ tự nhất định - đầu tiên là $\bar{a}\bar{b}$, sau đó là $\beta\bar{b}$ và sau đó là $(\alpha\bar{a})(\beta\bar{b})$ - chúng ta nhận được:
$$\alpha\bar{a}\beta\bar{b} = (x_1^2 - 2y_1^2)(x_2^2 - 2y_2^2).$$

(4)

Nếu chúng ta tính tích tương tự $\alpha\bar{a}\beta\bar{b}$ theo một thứ tự khác, thì chúng ta sẽ nhận được
$$\alpha\bar{b} = (x_1x_2 + 2y_1y_2) + (x_1y_2 + x_2y_1)\sqrt{2},$$
$$\bar{a}\bar{b} = (x_1x_2 + 2y_1y_2) - (x_1y_2 + x_2y_1)\sqrt{2},$$
$$\alpha\bar{a}\beta\bar{b} = (x_1x_2 + 2y_1y_2)^2 = 2(x_1y_2 + x_2y_1)^2.$$

(5)

Từ các đẳng thức (4) và (5) chúng ta cũng thu được $(x_1^2 - 2y_1^2)(x_2^2 - 2y_2^2) = (x_1x_2 + 2y_1y_2)^2 - 2(x_1y_2 + x_2y_1)^2.$

Điều này cũng dẫn đến một mối liên hệ thú vị giữa các nghiệm số nguyên của phép nhân có dạng tổng quát hơn $x^2 - 2y^2 = c$.

Nếu cặp số nguyên $(x_1; y_1)$ thỏa mãn đẳng thức $x_1^2 - 2y_1^2 = c_1$ và cặp số nguyên $(x_2; y_2)$ thỏa mãn đẳng thức $x_2^2 - 2y_2^2 = c_2$ thì cặp số nguyên $(x_1x_2 + 2y_1y_2; x_1y_2 + x_2y_1)$ là nghiệm của phép nhân $x^2 - 2y^2 = c_1c_2$.

Mọi điều nói về số có dạng $a + b\sqrt{2}$ cũng đúng với số có dạng $a + b\sqrt{d}$, trong đó $d$ là số nguyên tố (hoặc số tự nhiên, không chia hết cho bình phương). Đặc biệt, nó còn đúng với $d = -1$; Nhận dạng kết quả sẽ đóng một vai trò trung tâm trong điểm tiếp theo.

Bài toán
11. Sắp xếp lại các số $(2 - \sqrt{3})(7 - 4\sqrt{3})(2 + \sqrt{3})(7 + 4\sqrt{3})$.

12. Chia các số được mô tả từ số vô tỉ ở mẫu số
a) $\frac{9 + 4\sqrt{5}}{9 - 4\sqrt{2}}$; b) $\frac{p_1 + q_1\sqrt{d}}{p_2 + q_2\sqrt{d}}$.

13*. Chứng minh rằng tích của các số có dạng $x^2 + 5y^2$, trong đó $x$ và $y$ là số nguyên, lại là một số cùng loại. Tìm tất cả các số như vậy nhỏ hơn 100.

5. Bản sắc và thành phần đáng chú ý của Vieta

Hai cặp số bất kỳ $(a_1; b_1)$ và $(a_2; b_2)$ đều được kết nối bởi nhận dạng sau, được Diophantus biết đến:
$$a_1^2 + b_1^2)(a_2^2 + b_2^2) = (a_1a_2 - b_1b_2)^2 + (a_1b_2 + a_2b_1)^2.$$

Nó thu được từ đẳng thức (8) cho $d = -1$ và thường được sử dụng trong đại số và lý thuyết số. Ở đây chúng ta sẽ thảo luận về một ứng dụng khác của nó: một phương pháp thú vị cho phép bạn thu được từ hai tam giác vuông một tam giác vuông mới có cạnh huyền bằng tích cạnh huyền của chúng.

Lấy một tam giác vuông có các hình vuông $a_1, b_1$ và cạnh huyền $c_1$ và một tam giác khác có các hình vuông $a_2, b_2$ và cạnh huyền $c_2$. Vì theo định lý Pythagore
$$a_1^2 + b_1^2 = c_1^2$$ và $a_2^2 + b_2^2 = c_2^2,$
điều tương tự (9) có thể được viết như sau:
$$(c_1c_2)^2 = (a_1a_2 - b_1b_2)^2 + (a_1b_2 + a_2b_1)^2.$$

⟦folio 23⟧

Từ đẳng thức này, rõ ràng tồn tại một tam giác vuông với các hình vuông $|a_1a_2-b_1b_2|$, $a_1b_2+a_2b_1$ và cạnh huyền $c_1c_2$. Rõ ràng, điều này lần đầu tiên được chú ý vào thế kỷ 16 bởi nhà toán học người Pháp Francois Viète (xem [7]), vì vậy hãy gọi phương pháp thu được một tam giác vuông mới từ hai tam giác vuông này là “Thành phần của Viète”.

Chúng ta hãy xem xét hai tam giác vuông giống hệt nhau có hình vuông $m, n$ và đặt $a_1=a_2=n$, $b_1=b_2=m$ làm đồng dạng (9). chúng tôi nhận được

$$(m^2+n^2)^2=(m^2-n^2)^2+(2mn)^2.$$

Chúng ta thấy rằng bố cục của Vieta tạo ra một tam giác vuông mới với các hình vuông $|m^2-n^2|$, $2mn$ và cạnh huyền $m^2+n^2$. Điều thú vị là tất cả các tam giác vuông có các cạnh nguyên (nguyên tố cùng nhau) $a, b$, $c$ - còn được gọi là “bộ ba Pythagore” - có thể thu được bằng cách sử dụng các công thức này

$$c=m^2+n^2, a=m^2-n^2, b=2mn, (10)$$

trong đó $m$ và $n$ là các số tự nhiên (nguyên tố cùng nhau) có số chẵn lẻ khác nhau, $m>n$.

Điều quan trọng nhất là khi Vieta ghép hai tam giác vuông thì thu được một tam giác vuông mới (Hình 2), góc so với hình vuông $a_1b_2+a_2b_1$ bằng tổng $\varphi+\psi$ của các góc $\varphi$ và $\psi$ của các tam giác ban đầu so với các hình vuông $b_1$ và $b_2$ (nếu $\varphi+\psi<90^\circ$; nếu $\varphi+\psi>90^\circ$ thì góc này bằng $180^\circ-(\varphi+\psi)$). Như vậy, thành phần của Vieta có thể được cho một số hình học. Thành phần Vieta của hai tam giác vuông là tam giác vuông có cạnh huyền $c_1c_2$. Rõ ràng, điều này lần đầu tiên được chú ý vào thế kỷ 16 bởi nhà toán học người Pháp Francois Viète (xem [7]), vì vậy hãy gọi phương pháp thu được một tam giác vuông mới từ hai tam giác vuông này là “Thành phần của Viète”.

Chúng ta hãy xem xét hai tam giác vuông giống hệt nhau có hình vuông $m, n$ và đặt $a_1=a_2=n$, $b_1=b_2=m$ làm đồng dạng (9). chúng tôi nhận được

$$(m^2+n^2)^2=(m^2-n^2)^2+(2mn)^2.$$

Chúng ta thấy rằng bố cục của Vieta tạo ra một tam giác vuông mới với các hình vuông $|m^2-n^2|$, $2mn$ và cạnh huyền $m^2+n^2$. Điều thú vị là tất cả các tam giác vuông có các cạnh nguyên (nguyên tố cùng nhau) $a, b$, $c$ - còn được gọi là “bộ ba Pythagore” - có thể thu được bằng cách sử dụng các công thức này

$$c=m^2+n^2, a=m^2-n^2, b=2mn, (10)$$

trong đó $m$ và $n$ là các số tự nhiên (nguyên tố cùng nhau) có số chẵn lẻ khác nhau, $m>n$.

Điều quan trọng nhất là khi Vieta ghép hai tam giác vuông thì thu được một tam giác vuông mới (Hình 2), góc so với hình vuông $a_1b_2+a_2b_1$ bằng tổng $\varphi+\psi$ của các góc $\varphi$ và $\psi$ của các tam giác ban đầu so với các hình vuông $b_1$ và $b_2$ (nếu $\varphi+\psi<90^\circ$; nếu $\varphi+\psi>90^\circ$ thì góc này bằng $180^\circ-(\varphi+\psi)$). Như vậy, thành phần của Vieta có thể được cho một số hình học. Việc ghép hai tam giác vuông của Vieta tạo ra đường thẳng mới nhất của tam giác có đỉnh $a, b, c$.

Bài tập

14. Trên một chiếc bàn clipart được mô tả ở Babylon cổ đại vào khoảng năm 1500 trước Công nguyên. e., trong số các tam giác Pythagore khác, số sau được chỉ ra: 4961, 6480, 8161. Nó tương ứng với $m$ và $n$ nào trong công thức (10)?

15*. Tìm cos $75^\circ$ bằng phép ghép Vieta cho hai tam giác vuông có góc $30^\circ$ và $45^\circ$.

16. Trong tam giác Pythagore, trên các cạnh 5, 12, 13 và 7, 24, 25, cạnh huyền lớn hơn một cạnh huyền 1 đơn vị.

a) Tìm thêm hai tam giác Pythagore như vậy.

b) Tìm công thức tổng quát về các cạnh của các tam giác đó.

b) Xác định trong số đó các tam giác có cạnh huyền là hình vuông (như tam giác 7, 24, 25 = 5²).

6. Số phức $a+bi$

Trong các đoạn trước, bằng cách sử dụng các số hiển thị $a+b\sqrt{d}$, chúng ta đã đạt đến đẳng thức (8), điều này hóa ra đúng với mọi $d$. Sau đó, chúng tôi đặt danh tính $d=-1$ vào đây; đồng thời, bản thân các biểu thức $a+b\sqrt{d}=a+b\sqrt{-1}$ đã mất đi ý nghĩa vì không có $\sqrt{-1}$ trong số các số - xét cho cùng, bình phương của bất kỳ số nào cũng là số không âm. Tuy nhiên, hóa ra nên sử dụng số “tối thiểu” mới, bình phương của số này bằng -1. Nó được biểu thị bằng chữ cái $i$ (từ tiếng Latin tưởng tượng - của tôi, tưởng tượng).

Biểu thức có dạng $a+bi$, trong đó $a$ và $b$ là các số phổ biến, được gọi là số phức. Theo định nghĩa, hai số phức bằng nhau khi và chỉ khi các thành phần của chúng bằng nhau:

⟦folio 24⟧

$a_1 + b_1 i = a_2 + b_2 i$ chỉ khi $a_1 = a_2$ và $b_1 = b_2$.

Phép cộng và nhân số phức $a + bi$ được thực hiện giống như cách chúng được thực hiện với các số có dạng $a + b\sqrt{2}$ với các số hữu tỉ $a$ và $b$. Tuy nhiên, ở đây $a$ và $b$ có thể là bất kỳ số nào và $i^2 = -1$. Kết quả của các thao tác này là chúng ta lại thu được biểu thức có dạng $a + bi$:

$$(a_1 + b_1 i) + (a_2 + b_2 i) = (a_1 + a_2) + (b_1 + b_2) i,$$
$$(a_1 + b_1 i)(a_2 + b_2 i) = (a_1 a_2 - b_1 b_2) + (a_1 b_2 + a_2 b_1) i.$$

Bây giờ chúng ta thấy phép nhân (1) của rất nhiều số mà chúng ta đã chỉ ra ở đoạn 2 đến từ đâu. Phép nhân này về cơ bản đã được thảo luận ở đoạn trước - vì Vieta là thành phần của hai tam giác vuông có chân $(a_1; b_1)$ và $(a_2; b_2)$.

Một vai trò đặc biệt được đóng bởi số phức bằng 0 $0 = 0 + 0i$, đơn vị $1 = 1 + 0i$ và đơn vị trừ $i = 0 + 1i$. Lưu ý rằng nếu bất kỳ thành phần nào $a$ hoặc $b$ của số phức $a + bi$ bằng 0 thì phần tương ứng của số phức sẽ bị bỏ qua khi viết.

Trong thế giới số phức, người ta có thể chia cho bất kỳ số nào khác 0 $0 = 0 + 0i$. Khi tính thương của hai số, thuận tiện là nhân cả hai số này bằng cách chia số $c - di$ với phép chia $z = c + di$:

$$\frac{a + bi}{c + di} = \frac{(a + bi)(c - di)}{(c + di)(c - di)} = \left( \frac{ac + bd}{c^2 + d^2} \right) + \left( \frac{bc - ad}{c^2 + d^2} \right) i.$$

Số phức lần đầu tiên xuất hiện trong đại số, trong các bài toán về lời giải phương trình đại số của tam giác và bậc cao hơn. Tuy nhiên, ứng dụng của số phức bao gồm hầu hết các lĩnh vực chính của toán học và vật lý - hình học, lý thuyết số, phân tích toán học và lý thuyết xác suất, tính toán các mục đích điện, thủy động lực học và cơ học lượng tử.

Ta thu được số phức dưới dạng cặp số thực, xác định phép nhân theo quy tắc (1), thỏa mãn các điều kiện tự nhiên - giao hoán, kết hợp, phân phối. Điều đáng quan tâm đối với toán học là việc phân loại bài toán của tất cả các cặp như vậy. Hóa ra tất cả chúng đều phù hợp với sơ đồ chung: các cặp $(x, y)$ được viết dưới dạng “số phức tổng quát hóa” $x + yj$ và $j^2$ trong phép tính được thay thế bằng $r + sj (r, s$ - số cố định, xem bài toán 19); ở đây có thể có ba người hầu khác nhau về cơ bản (mà những người khác có thể được giảm bớt):

$$(1) j^2 = 1$$

(quy tắc $j^2 = 2$ mà chúng tôi đã nghiên cứu chi tiết thuộc loại này); (2) $j^2 = 0$ (thật kỳ lạ, quy tắc nhân tương ứng được viết cho các cột):

$$\left( \frac{x_1}{y_1} \right) \left( \frac{x_2}{y_2} \right) = \left( \frac{x_1 x_2}{x_1 y_2 + x_2 y_1} \right)$$

là sự đảo ngược quy tắc cộng phân số

$$\frac{y_1}{x_1} + \frac{y_2}{x_2} = \frac{y_1 x_2 + x_2 y_1}{x_1 x_2}$$

và cuối cùng (3) $j^2 = -1$ là số phức thực.

Nhiệm vụ và

17. Chúng ta sẽ biểu thị số phức $x + iy$ bằng điểm $(x; y)$ trên mặt phẳng tọa độ. Đặt $u = 1 - i$, $v = -2 + 5i$. Tìm a) $u$; 6) $v$; b) $uv$; d) $u/v$ và vẽ tất cả các số này trên mặt phẳng tọa độ.

18. Đặt $z = \frac{1 + i}{\sqrt{2}}$, $w = \frac{1 - i \sqrt{3}}{2}$. Tìm a) $z^2, z^4, z^8$; 6) $w^2, w^3, w^6, w^2 + w + 1$.

19*. Cho $r$ và $s$ là hai số cố định. Chúng ta hãy định nghĩa phép nhân trên các cặp số (tất cả, không chỉ số hữu tỷ) theo công thức

$$\left( \frac{x_1}{y_1} \right) \cdot \left( \frac{x_2}{y_2} \right) = \left( \frac{x_1 x_2 + ry_1 y_2}{x_1 y_2 + x_2 y_1} \right).$$

(Quy tắc này tương ứng với phép nhân “số phức tổng quát” $x + jy$, trong đó $j^2 = r + sj$.) a) Kiểm tra xem phép nhân này có thỏa mãn các tính chất cơ bản 1) - 3) từ điểm 2 hay không. b) Cặp $e$ nào đóng vai trò đơn vị? b) Với $r$ và $s$, với bất kỳ cặp $u$ nào khác ngoài $0 = \left( \begin{array}{c} 0 \\ 0 \end{array} \right)$, có $v$ sao cho $uv = e$ không? r) Với $r$ và $s$ nào có cặp $u \neq 0$ sao cho $u^2 = 0$? 20. Ta định nghĩa phép nhân các cặp số $(a; b)$ như sau: mỗi cặp số $(a; b)$ tương ứng với một hàm tuyến tính $u(t) = at + b$, và tích $(a_1; b_1)$ với $(a_2; b_2)$ tương ứng với thành phần của hàm $u_1(t) = a_1 t + b_1$ và $u_2(t) = a_2 t + b_2$, tức là thay thế số thứ nhất thành số thứ hai $u_2(u_1(t)) = a_2(a_1 t + b_1) + b_2 = a_2 a_1 t + a_2 b_1 + b_2$, hoặc

$$\left( \begin{array}{c} a_1 \\ b_1 \end{array} \right) \left( \begin{array}{c} a_2 \\ b_2 \end{array} \right) = \left( \begin{array}{c} a_1 a_2 \\ a_2 b_1 + b_2 \end{array} \right).$$

Định luật nào sau đây áp dụng cho phép nhân này: $uv = vu$, $(uv)w = u(vw)$, $u(v + w) = uv + uw$, $(u + v)w = uw + wv$?

Danh sách tài liệu bổ sung

1. Phương trình Gelfond A. O. Lời giải trong số nguyên. M.: Nauka, 1983. - (Bài giảng toán phổ thông, số 8).
2. Nesterenko Yu. V., Nikshin E. M. Tiểu luận về phân số nguyên. Kvant, 1983, số 5, 6.
3. Vaguten N. Số liên hợp. Kvant, 1980, số 2.
4. Ashmanov S. Số và đa thức. Kvant, 1980, số 2.
5. Đại số toán học tương ứng. M.: Nauka, 1981.
6. Pontryagin L. S. Số phức. Kvant, 1982, số 4.
7. Bashmkova I. G. Sự hình thành đại số. M.: Kiến thức, 1979.
