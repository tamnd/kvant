---
id: 1992-4-solovev-neopredelennyie-uravneniya-pervoy-stepeni-4ac145ec
issue: kvant_1992_4
year: 1992
number: "4"
title: Phương trình chưa xác định bậc một
authors:
  - Соловьёв Ю. П.
rubric: shkola-v-kvante
rubric_sub: Школа в «Кванте»
page_first: 44
page_last: 48
page_labels: 42-46
lang: vi
source: kvant_digital
extraction: vision
content_sha256: f2aea2902c92b923d066e750f70d575be63903c58e7b63f655e3439411631815
prompt_sha256: draft-1
translated_from: content/ru/1992/04/articles/15_solovev-neopredelennyie-uravneniya-pervoy-stepeni-4ac145ec.md
source_content_sha256: c60f09db37ce4bec96d5ba954b300a95dc53038bde0268d4e088a9f770208977
translation_model: draft
translation_run: vi-draft-gaps-2026-11-06
translation_quality: draft
---

⟦folio 42⟧

---
running_head:
folio:
---

Phương trình chưa xác định bậc một
Tiến sĩ Khoa học Vật lý và Toán học
Y. GIẢI QUYẾT

Sự tồn tại lời giải
Phương trình vô định bậc một có hai ẩn số là phương trình có dạng
$$ax + by = c,$$
(*)

trong đó $a, b$ và $c$ là các số từ một tập hợp nhất định (thực, hữu tỉ, số nguyên, v.v.) và $a$ và $b$ không bằng 0. Giải phương trình vô định (1) là bất kỳ cặp số nào ($\alpha; \beta$) thuộc một đồng nhất định
tính chất thỏa mãn phương trình.

Trước tiên chúng ta hãy tìm hiểu xem lời giải của phương trình này trông như thế nào trong trường hợp $a, b$ và $c$ là số thực. Hãy giải quyết nó cho bất kỳ điều gì chưa biết. Ví dụ: với $y$ chúng ta nhận được:

$$y = \frac{c - ax}{b}.$$

Biểu thức này cho thấy rằng $y$ phụ thuộc duy nhất vào $x$, trong khi bản thân $x$ có ​​thể hoàn toàn tùy ý. Do đó, nếu $a, b$ và $c$ là số thực thì phương trình (*) có tập vô hạn lời giải

$$(r; \frac{c - ar}{b}),$$

trong đó $r$ là số thực tùy ý.

Nếu $a, b$ và $c$ là các số hữu tỷ thì việc coi các phương trình lời giải hữu tỉ (*) là điều đương nhiên. Rõ ràng, chúng được tính theo cùng một công thức $(r; \frac{c - ar}{b})$, trong đó thời gian $r$ là một số hữu tỉ tùy ý.

Một trường hợp ý nghĩa và thú vị hơn nhiều là khi các hệ số $a, b$ và $c$ là số nguyên và cần phải tìm phương trình số nguyên lời giải (*). Bài toán tìm số nguyên lời giải có thể được phát biểu lại như sau: từ tập vô hạn các phương trình lời giải thực (*) chỉ chọn số nguyên. Rõ ràng là hạn chế như vậy làm giảm đáng kể con số lời giải.

Trước hết, chúng ta hãy tìm hiểu xem liệu phương trình vô định (*) bằng số nguyên có luôn luôn được giải hay không. Đáp số Hai định lý sau đây trả lời câu hỏi này.

Định lý 1. Nếu số hạng tự do của một phương trình vô định

$$ax + by = c$$

không chia hết cho ước chung nhất của các hệ số $a$ và $b$, gcd

⟦folio 43⟧

---
running_head:
folio:
---

Bằng chứng. Đặt $d = \text{НОД} (a; b)$, vì vậy $a = md, b = nd$, trong đó $m$ và $n$ là số nguyên. Khi đó phương trình của chúng ta có dạng
$$mdx + ndy = c,$$
hoặc
$$d(mx + ny) = c.$$

Giả sử có các số nguyên $x$ và $y$ thỏa mãn phương trình (*), ta thu được hệ số $c$ chia hết cho $d$. Kết quả mâu thuẫn chứng minh định lý.

Nếu cả ba hệ số $a, b$ và $c$ đều có một thừa số chung, thì bằng cách giảm nó, có thể biến các hệ số $a$ và $b$ có một thừa số chung, hoặc $a$ và $b$ là nguyên tố cùng nhau. Trong trường hợp đầu tiên, theo định lý trước, phương trình không có số nguyên lời giải. Trong trường hợp thứ hai chúng ta đi đến định lý sau.

Định lý 2. Nếu các hệ số $a$ và $b$ của phương trình vô định
$$ax + by = c$$
là các số nguyên tố cùng nhau thì phương trình có ít nhất một số nguyên lời giải.

Bằng chứng. Không mất tính tổng quát, chúng ta có thể giả sử rằng $a > 0$. Giải phương trình cho $x$, ta được
$$x = \frac{c - by}{a}.$$

Trước hết, chúng ta hãy chứng minh rằng nếu trong công thức này thay vì $y$ chúng ta thay thế các số tự nhiên thay đổi $a$, tức là các số 0, 1, 2, ..., $a - 1$ và chia mỗi lần, thì tất cả các số dư $a$ sẽ khác nhau. Trên thực tế, chúng ta hãy thay thế $y$ một số hai số $m_1$ và $m_2$, thay đổi $a$ (từ tập hợp 0, 1, 2, ..., $a - 1$). Kết quả ta được hai phân số
$$\frac{c - bm_1}{a} \text{ и } \frac{c - bm_2}{a}.$$

Thực hiện phép chia và ký hiệu các phần không đầy đủ cho $q_1$ và $q_2$, phần dư cho $r_1, r_2$, ta tìm được
$$\frac{c - bm_1}{a} = q_1 + \frac{r_1}{a}, \frac{c - bm_2}{a} = q_2 + \frac{r_2}{a}.$$

Giả sử số dư $r_1$ và $r_2$ bằng nhau. Sau đó, trừ đẳng thức thứ hai cho đẳng thức thứ nhất, chúng ta nhận được
$$\frac{c - bm_1}{a} - \frac{c - bm_2}{a} = q_1 - q_2,$$

hoặc
$$\frac{b(m_2 - m_1)}{a} = q_1 - q_2.$$

Vì $q_1 - q_2$ là số nguyên nên vế trái cũng phải là số nguyên. Vì vậy, $b(m_2 - m_1)$ phải chia hết cho $a$. Nhưng các số $b$ và $a$ là hai số nguyên tố cùng nhau nên $m_2 - m_1$ phải chia hết cho $a$, tức là hiệu của hai số tự nhiên, mỗi số nhỏ hơn $a$, phải chia hết cho $a$, điều này là không thể. Điều này có nghĩa là $r_1$ không thể bằng $r_2$, tức là tất cả số dư đều khác nhau.

Vì vậy, chúng ta có $a$ dư lượng tự nhiên khác nhau, nhỏ hơn $a$. Nhưng các số tự nhiên $a$ khác nhau không vượt quá $a$ chẳng qua là các số 0, 1, 2, ..., $a - 1$. Do đó, trong số các số dư chắc chắn sẽ có một và chỉ một bằng 0. Điều này có nghĩa là $y$, mà việc thay thế vào biểu thức $(c - by)/a$ cho số dư 0, biến $x = (c - by)/a$ thành một số nguyên. Vì vậy, nếu $a$ và $b$ là số nguyên tố cùng nhau thì phương trình (*) thực sự thừa nhận số nguyên lời giải, đó là điều chúng ta cần chứng minh.

Định lý 1 đã chứng minh ở trên phát biểu rằng điều kiện gcd $(a; b) = 1$ là điều kiện cần để giải được phương trình vô định (*) dưới dạng số nguyên. Định lý 2 phát biểu rằng điều kiện này là đủ.

Phương pháp đầu tiên lời giải

Định lý 2 đưa ra khả năng thực tế để tìm một cặp lời giải của một phương trình vô định trong số nguyên. Ví dụ, hãy cho phương trình
$$7x + 5y = 232.$$

⟦folio 44⟧

---
running_head:
folio:
---

Chúng tôi giải phương trình này đối với phương trình của ẩn số mà chúng tôi tìm thấy hệ số (modulo) nhỏ nhất, tức là trong trường hợp này đối với $y$:

$$y = \frac{232 - 7x}{5}.$$

Thay vì $x$, chúng ta thay các số tự nhiên nhỏ hơn 5 vào biểu thức này, tức là 0, 1, 2, 3, 4. Kết quả là chúng ta tìm thấy:

$$x = 0, \quad y = \frac{232}{5} = 46 \frac{2}{5},$$

$$x = 1, \quad y = \frac{232 - 7}{5} = 45.$$

Vì vậy, ta thu được một lời giải của phương trình này: $x = 1, y = 45$.

Bạn nên sử dụng ví dụ này về phương trình không xác định lời giải trong trường hợp hệ số của bất kỳ ẩn số nào có giá trị tuyệt đối không lớn.

Khi đã tìm thấy một cặp số nguyên lời giải thì rất dễ tìm thấy tất cả các số nguyên lời giải giống nhau.

Định lý 3. Phương trình bất định

$$ax + by = c,$$

trong đó $a$ và $b$ là các số nguyên tố cùng nhau, thừa nhận một tập hợp số nguyên vô hạn lời giải. Tất cả những lời giải này được đưa ra bởi các công thức

$$x = \alpha + bt, \quad y = \beta - at,$$

trong đó $(\alpha; \beta)$ là một số lời giải của phương trình (1), $a$ $t$ là một số nguyên tùy ý.

Bằng chứng. Vì theo điều kiện, cặp $(\alpha; \beta)$ là nghiệm của phương trình của chúng ta, nên việc thay $x = \alpha, y = \beta$ vào phương trình sẽ cho ta đẳng thức

$$a \mu + b \beta = c.$$

Trừ đi danh tính này khỏi phương trình của chúng tôi, chúng tôi có

$$a(x - \alpha) + b(y - \beta) = 0,$$

Ở đâu

$$x = \alpha + \frac{b(\beta - y)}{a}.$$

Để $x$ là số nguyên, điều cần thiết là $b(\beta - y)/a$ phải là số nguyên, nghĩa là để tích $b(\beta - y)$ chia hết cho $a$ mà không có số dư. Nhưng $a$ và $b$ là các số nguyên tố tương đối; do đó, để làm được điều này, điều cần thiết là $(\beta - y)/a$ bằng LOB với một số nguyên nào đó. Hãy biểu thị số nguyên này bằng $t$:

$$\frac{\beta - y}{a} = t.$$

Sau đó $y = \beta - at$ và do đó

$$x = \alpha + \frac{b(\beta - y)}{a} = \alpha + bt,$$

Q.E.D.

Cách thứ hai lời giải

Đầu tiên, chúng ta hãy xem xét một trường hợp đặc biệt. Giả sử rằng hệ số của một trong các ẩn số bằng một. Ví dụ, hãy xem xét phương trình

$$x + by = c.$$

Từ đây

$$x = c - by.$$

Đặt $y = 0$, chúng ta nhận được giá trị nguyên $x = c$ cho $x$. Do đó, một cặp phương trình lời giải có dạng $x = c, y = 0$. Tuy nhiên, các số nguyên lời giải được cho bởi các công thức

$$x = c + bt, \quad y = -t.$$

Tương tự, nếu hệ số $y$ bằng 1 thì mọi số nguyên lời giải đều được cho bởi công thức

$$x = t, \quad y = c - at.$$

Phương pháp chung lời giải của phương trình không xác định trong số nguyên dựa trên sự thay thế này. Trên thực tế, nếu chúng ta có thể rút gọn phương trình $ax + by = c$ thành một phương trình trong đó một trong các hệ số bằng 1, thì bài toán sẽ được giải. Nhưng khi $a$ và $b$ là các số nguyên tố tương đối thì việc rút gọn như vậy luôn có thể xảy ra. Ví dụ, hãy cho phương trình

$$17x - 37y = 55.$$

Chúng ta giải phương trình này cho ẩn số, có giá trị nhỏ hơn

⟦folio 45⟧

---
running_head:
folio:
---

hệ số mô đun, trong trường hợp này, liên quan đến $x$. chúng tôi nhận được
$$x = \frac{55 + 37y}{17}.$$
(1)

Chọn toàn bộ phần, chúng tôi thấy rằng
$$x = 3 + 2y + \frac{4 + 3y}{17}.$$

Biểu thức thu được cho $x$ bao gồm hai phần: $3 + 2y$, sẽ là số nguyên cho mọi số nguyên $y$ và phân số $(4 + 3y)/17$. Để $x$ là số nguyên, cần chọn các giá trị số nguyên $y$ sao cho $(4 + 3y)/17$ là số nguyên. Hãy đặt
$$\frac{4 + 3y}{17} = t,$$
trong đó $t$ là số nguyên tùy ý. Từ đẳng thức cuối cùng ta tìm được
$$3y - 17t = -4.$$ (2)

Chúng tôi giải phương trình này đối với ẩn số, có hệ số có độ lớn nhỏ hơn, tức là đối với $y$:
$$y = \frac{17t - 4}{3}.$$

Chọn toàn bộ phần, chúng tôi nhận được
$$y = 5t - 1 + \frac{2t - 1}{3}.$$

Để $y$ là số nguyên, cần chọn các giá trị số nguyên $t$ sao cho
$$\frac{2t - 1}{3} = t_1,$$
trong đó $t_1$ là số nguyên tùy ý. Sự bình đẳng cuối cùng mang lại
$$2t - 3t_1 = 1.$$ (3)

Làm tương tự như trước, chúng tôi tìm thấy
$$t = \frac{1 + 3t_1}{2} = t_1 + \frac{1 + t_1}{2}.$$

Để số $t$ là số nguyên, phải đáp ứng điều kiện sau:
$$\frac{1 + t_1}{2} = t_2,$$

trong đó $t_2$ là số nguyên tùy ý. Từ đẳng thức thu được suy ra rằng
$$t_1 - 2t_2 = -1.$$ (4)

Trong phương trình này, hệ số của một trong các ẩn số bằng một, và do đó chúng ta có thể giải được nó.

Vì vậy ta có dãy phương trình sau:
$$17x - 37y = 55,$$
$$3y - 17t = -4,$$
$$2t - 3t_1 = 1,$$
$$t_1 - 2t_2 = -1.$$

Từ phương trình (4) chúng ta thu được rằng
$$t_1 = 2t_2 - 1.$$

Một trong lời giải của phương trình này là
$$t_1 = -1, \quad t_2 = 0.$$

Thay giá trị kết quả $t_1$ vào phương trình (3), chúng ta tìm thấy $t = -1$; thay thế giá trị này $t$ vào phương trình (2), chúng ta thu được $y = -7$. Sau khi thay thế giá trị này của $y$ vào phương trình (1), chúng ta thấy rằng $x = -12$. Vì thế,
$$x = -12, \quad y = -7$$

là một trong lời giải phương trình đã cho. Công thức tổng quát lời giải dựa trên Định lý 3 sẽ có dạng
$$x = -12 - 37t, \quad y = -7 - 17t,$$

trong đó $t$ là một số tùy ý.

Hãy chứng minh rằng ví dụ lời giải của phương trình vô định mô tả ở trên luôn dẫn đến số nguyên lời giải. Thật vậy, chúng ta đã nhận được phương trình số nguyên sau:
1. phương trình này
$$17x - 37y = 55,$$
hoặc một phương trình có ẩn số $x$ và $y$ cùng các hệ số của chúng $a$ và $b$.
2. phương trình
$$3y - 17t = -4,$$
và nói chung là một phương trình có ẩn số $x$ và $t$ (nếu $|a| > |b|$) hoặc $y$ và $t$ (nếu $|a| < |b|$). các hệ số của nó là

⟦folio 46⟧

---
running_head:
folio:
---

$a$ (tương ứng với $b$) và phần dư $r_1$ khi $a$ chia cho $b$ (tương ứng với $b$ cho $a$).

3. phương trình
$$2t - 3t_1 = 1,$$

tức là một phương trình có ẩn số $t$ và $t_1$. Hệ số của nó là: số dư trước $r_1$ và số dư sau khi chia $a$ hoặc $b$ cho $r_1$.

4. phương trình
$$t_1 - 2t_2 = -1,$$

tức là một phương trình có ẩn số $t_1, t_2$. Các hệ số của nó là số dư trước $r_2$ và số dư khi chia $r_1$ cho $r_2$. Và vân vân.

Từ đó, chúng ta có thể thấy rằng quy trình lời giải được rút gọn thành chuỗi hành động diễn ra khi tìm ước số chung nhất (GCD $(a; b)$) của các số $a$ và $b$ bằng thuật toán Euclide. Nhưng các hệ số $a$ và $b$ là nguyên tố cùng nhau và do đó ước số chung nhất của chúng bằng 1. Do đó, tiếp tục chuỗi hành động đã chỉ định, chúng ta phải đạt được phần dư bằng 1, đây sẽ là hệ số của một trong các phương trình thu được. Do đó, bài toán được rút gọn thành trường hợp đặc biệt đã biết.

Các phương trình có nhiều ẩn số

Chúng ta hãy giới hạn việc xem xét trường hợp của một phương trình có ba ẩn số. Cho phép
$$ax + by + cz = d$$
một phương trình trong đó $a, b, c, d$ là số nguyên và không có số nào $a, b$ và $c$ bằng 0. Trước hết, điều cần thiết là các hệ số $a, b$ và $c$ không có hệ số chung đến mức sẽ không được đưa vào $d$, vì nếu không thì phương trình không thể giải được bằng số nguyên. Nếu các hệ số này có thừa số chung chứa trong $d$ thì nó sẽ bị loại bỏ bằng cách rút gọn. Kết quả là có thể xảy ra hai trường hợp:

1) trong ba hệ số $a, b$ và $c$ ít nhất là nguyên tố cùng nhau, chẳng hạn như trong các phương trình
$$12x + 11y + 15z = 141;$$

2) cứ hai hệ số đều có một thừa số chung, nhưng cả ba đều nguyên tố cùng nhau; chẳng hạn như phương trình $12x + 15y + 20z = 181$, trong đó GCD $(12; 15) = 3$, GCD $(12; 20) = 4$, GCD $(15; 20) = 5$.

Trường hợp đầu tiên. Cho $a$ và $b$ là các số nguyên tố cùng nhau. Di chuyển $cz$ sang bên phải và áp dụng nó vào phương trình
$$ax + by = d - cz$$

phương pháp lời giải phương trình có hai ẩn số, xem xét các đại lượng tạm thời đã biết. Kết quả là chúng ta sẽ tìm thấy
$$x = \alpha + bt, \quad y = \beta - at,$$

trong đó $\alpha$ và $\beta$ là đa thức bậc một đối với $z$. Cho các giá trị số nguyên tùy ý $z$ và $t$, chúng ta thu được tất cả các phương trình số nguyên lời giải (**).

Trường hợp thứ hai. Bây giờ giả sử không có cặp hệ số nguyên tố cùng nhau giữa các hệ số $a, b$ và $c$. Đặt $h = \text{НОД} (a; b)$ và $a', b'$ là đạo hàm riêng của $a, b$ chia cho $h$. Khi đó phương trình (**) sẽ có dạng
$$ha'x + hb'y + cz = d,$$
Ở đâu
$$a'x + b'y = \frac{d - cz}{h}.$$

Để vế trái là một số nguyên, điều cần thiết là $(d - cz)/h$ phải bằng một số nguyên $t$ nào đó. Kể từ đây,
$$a'x + b'y = t,$$
(5)
$$cz + ht = d.$$

Không có gcd $(a'; b') = 1$, và do đó phương trình (5) có số nguyên lời giải có dạng
$$x = \alpha + b't', \quad y = \beta - a't'$$,

(Cuối cùng xem trang 55)
