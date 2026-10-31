---
id: 1974-3-gerver-20-zadach-na-predelyi-cc0406dc
issue: kvant_1974_3
year: 1974
number: "3"
title: 20 bài toán đến giới hạn
authors:
  - Гервер М. Л.
rubric: matematicheskiy-kruzhok
rubric_sub: Математический кружок
page_first: 29
page_last: 33
page_labels: 27, 28, 30, 31
tag: QO67
lang: vi
source: kvant_digital
extraction: vision
content_sha256: c1763d370e07681a2c3956958ff0b9d7d97211ab192eec8164376f131523ab29
prompt_sha256: draft-1
translated_from: content/ru/1974/03/articles/14_gerver-20-zadach-na-predelyi-cc0406dc.md
source_content_sha256: e402d349b78a7ddafa566a63c103f1c2f1f4193d23a46a5fb4a817850baf4450
translation_model: draft
translation_run: vi-draft-2026-10-31
translation_quality: draft
---

⟦folio 27⟧

20 bài toán đến giới hạn

MP Gerver

Nhiều người có lẽ đã biết định nghĩa về giới hạn của một dãy: "Một số a được gọi là giới hạn của dãy $x_n$ nếu với bất kỳ $\varepsilon > 0$ nào có một $N$ sao cho với mọi $n > N...$. Nhưng cần nhớ là một chuyện, còn việc có thể xử lý nó một cách thoải mái, chứng minh các định lý mà không bị nhầm lẫn với tất cả những cái "có", "cho bất kỳ ai", v.v. con đường đến “toán cao hơn”, điều mà không chỉ học sinh mà cả học sinh cũng gặp khó khăn để vượt qua.

Nếu bạn giải được bài toán, được thu thập trong bài viết này - hoặc ít nhất là hiểu được lời giải của họ - thì việc phân tích toán học sâu hơn sẽ dễ dàng và thú vị hơn nhiều đối với bạn.

1. Chứng minh rằng với mọi số tự nhiên $n$
a) $\frac{1}{2 \cdot 3} + \frac{1}{3 \cdot 4} + \dots + \frac{1}{n(n+1)} = \frac{1}{2} \cdot \frac{n-1}{n+1}$;
b) $\frac{1}{n+1} + \frac{1}{n+2} + \dots + \frac{1}{2n} \geq \frac{1}{2}$.

Trong phần tiếp theo, chúng ta sẽ sử dụng chữ cái $n$ để chỉ biểu thị các số tự nhiên.

2. a) Chứng minh rằng bạn có thể tìm được $n$ sao cho $2^n > 10^{10}$.
b) Chứng minh rằng bạn có thể tìm thấy $k$ sao cho với mọi $n > k$ $1 + a)^n \geq 1 + na$ đều đúng.
b) Chứng minh rằng bạn có thể tìm thấy $k$ sao cho với mọi $n > k$ $10^n > n^{10}$ đều đúng.
d) Đặt $|q| < 1$. Chứng minh rằng bạn có thể tìm thấy $k$ sao cho với mọi $n > k$ $|q|^n < 10^{-10}$ đều đúng.
e) Có số dương nào mà với mọi $n$ nó nhỏ hơn $1/n$ không?

e) Đặt $|q| < 1$. Chứng minh rằng với mọi $\varepsilon > 0$ luôn tồn tại một $k$ sao cho với mọi $n > k$ $\left|q\right|^n < \varepsilon^*$ đều đúng.
g) Có thể tìm được $k$ sao cho với mọi $n > k$ và với mọi $\varepsilon > 0$ thì đẳng thức $\left(\frac{1}{2}\right)^n < \varepsilon$ đúng không?
Thế thì ee. So sánh 2e và 2g ta thấy trật tự từ là vật!
h) Đặt $s_n = \frac{1}{2} + \frac{1}{4} + \frac{1}{8} + \dots + \frac{1}{2^n}$. Chứng minh rằng với mọi $\varepsilon > 0$ luôn tồn tại một $k$ sao cho với mọi

*) $\varepsilon$ là một chữ cái Hy Lạp, đọc là: “episilon”, thường dùng để biểu thị các số dương nhỏ. Ý nghĩa chính xác của từ “số nhỏ” đã có sẵn - “nhỏ” nghĩa là gì: 0,01 hoặc $10^{-10}$? Vì vậy họ nói; “cho bất kỳ $\varepsilon > 0$” - nghĩa này thường là: “bất kể nó có thể nhỏ đến mức nào.” 1Liên quan đến bài toán người ta nói rất nhiều: ở giữa: đặt $\varepsilon = 0,01$, sau đó tìm $k$ sao cho với bất kỳ $n > k$ nào sẽ có $|q|^n < 0,01$; đặt $\varepsilon = 10^{-10}$, sau đó tìm một $k$ khác (lớn hơn) sao cho với bất kỳ $n$ nào lớn hơn $k$ mới này, sẽ có $|q|^n < 10^{-10}$; nói chung, với bất kỳ $\varepsilon > 0$ nào (dù nhỏ đến đâu), bạn có thể chọn $k$ (có thể rất lớn), sao cho với bất kỳ $n > k$ nào sẽ có $|q|^n < \varepsilon$.

⟦folio 28⟧

không có thật $n > k$
$$|s_n - 1| < \varepsilon.$$
Dãy số. Hãy viết một số số: $x_1$, sau đó là số khác: $x_2$, rồi đến số thứ ba: $x_3$, v.v.

Chúng ta sẽ được một dãy số
$$x_1, x_2, x_3, \dots, x_n, \dots$$
Số bên cạnh chữ cái $x$ cho biết vị trí của số đó trong chuỗi: $x_1$ - ở ngày 1, $x_2$ - ở ngày thứ 2, $\dots$, $x_n$ - ở $n$, $\dots$.

Nói tóm lại, nó được biểu thị bằng ký hiệu $\{x_n\}$. Tất nhiên, các chữ cái khác có thể được sử dụng để biểu thị các chuỗi: $\{s_n\}, \{y_n\}, \{z_n\}$, v.v.

Hãy viết ra hàng tá trình tự được sử dụng trong các nhiệm vụ sau:

(1) $1, \frac{1}{2}, \frac{1}{3}, \frac{1}{4}, \dots$

(2) $1, 0, \frac{1}{2}, 0, 0, \frac{1}{3}, 0, 0, 0, \frac{1}{4}, 0, 0, 0, 0, \dots$

(3) $\{s_n\}, s_n = \frac{1}{2} + \frac{1}{4} + \frac{1}{8} + \dots + \frac{1}{2^n}$.

(4) $\{y_n\}, y_n = \frac{1}{2} - \frac{1}{4} + \frac{1}{8} - \dots - \frac{(-1)^n}{2^n}$.

(5) $1, 1, 1, 1, \dots$.

(6) $1, -1, 1, -1, \dots$.

(7) $1, \frac{1}{2}, 1, \frac{1}{3}, 1, \frac{1}{4}, 1, \frac{1}{5}, \dots$.

(8) $1, -\frac{1}{2}, \frac{1}{3}, -\frac{1}{4}, \frac{1}{5}, -\frac{1}{6}, \dots$.

(9) $\frac{1}{1}, \frac{1}{1}, \frac{1}{2}, \frac{1}{1}, \frac{1}{3}, \frac{1}{1}, \dots, \frac{1}{9}, \frac{1}{1}, \frac{1}{10}, \frac{1}{2}, \frac{1}{11}, \frac{1}{2}, \dots, \frac{1}{99}, \frac{1}{2}, \frac{1}{100}, \frac{1}{3}, \dots$

(mẫu số của một phân số ở vị trí chẵn bằng số chữ số của mẫu số của phân số trước đó).

(10) $\frac{1}{2}, \frac{2}{1}, \frac{2}{3}, \frac{3}{2}, \frac{3}{4}, \frac{4}{3}, \frac{4}{5}, \frac{5}{4}, \dots$

Định nghĩa 1. Số $a$ được gọi là *giới hạn của dãy* $\{x_n\}$ nếu với bất kỳ $\varepsilon > 0$ nào tồn tại một $k$ sao cho với bất kỳ $n > k$ nào
$$|a - x_n| < \varepsilon.$$
Việc số $a$ là giới hạn của $\{x_n\}$ được viết như sau:
$$\lim_{n \to \infty} x_n = a$$
(đọc: “giới hạn của $x_n$ vì $n$ tiến tới vô cùng bằng $a$”) hoặc như thế này:
$$x_n \rightarrow a \text{ при } n \rightarrow \infty$$
(đọc: "$x_n$ có xu hướng $a$ vì $n$ có ​​xu hướng vô cùng"). Ở một số quốc gia, việc đề cập đến $n$, có xu hướng tiến tới vô cùng, bị lược bỏ và chỉ viết đơn giản:
$$\lim x_n = a \text{ при } x_n \rightarrow a.$$
Dãy số có giới hạn được gọi là *hội tụ*.

3. a) Mẫu bài toán 2e và 23 sử dụng Định nghĩa 1.

6) Chứng minh rằng 0 là giới hạn của dãy (1), (2), (8) và (9).

b) Tìm giới hạn của dãy (3), (4) và (10).

d) Chứng minh rằng 1 không phải là giới hạn của dãy (1).

d) Các dãy (5), (6) và (7) có giới hạn không?

e) Cho $x_n - n$ là một số hạng của dãy (9). Chỉ định $k$ sao cho bất đẳng thức $x_n < \frac{1}{2}$ đúng cho $n > k$.

g) Hai số khác nhau có thể là giới hạn của cùng một dãy không?

4. Đặt $\{x_n\}$ là một dãy tùy ý. Hãy viết ra một số

⟦folio 30⟧

Về giới hạn 4. Họ nói rằng dãy $\{x_n\}$ tiến tới vô cùng (được viết như sau: $x_n \to \infty$ cho $n \to \infty$) nếu với bất kỳ $C$ nào thì có một $k$ sao cho với bất kỳ $n > k$ $|x_n| > C$ nào.

7. Dãy số nào sau đây hướng tới vô cực và dãy số nào không bị giới hạn?

a) $x_n = n$, $6)$ $x_n = (-1)^n \cdot n$,
b) $x_n = n^{(-1)^n}$
g) $x_n = \begin{cases} n^2 \text{ при } n \text{ четном,} \\ \sqrt{n} \text{ при } n \text{ нечетном.} \end{cases}$

Về giới hạn 5. Số $a$ được gọi là *điểm giới hạn* của dãy $\{x_n\}$ nếu với bất kỳ $\varepsilon > 0$ nào và với bất kỳ $k$ nào cũng có một $n > k$ sao cho $|a - x_n| < \varepsilon$.

8. Chứng minh a) giới hạn của dãy hội tụ là điểm giới hạn của nó,
6) rằng nếu $x_n \to a$ và $b \neq a$ thì $b$ không phải là điểm giới hạn của $\{x_n\}$.
b) rằng nếu $a$ là điểm giới hạn của $\{x_n\}$ thì $\{x_n\}$ chứa dãy con hội tụ đến $a$.

9. Hãy nghĩ ra một dãy $\{x_n\}$ có điểm giới hạn là:
a) tất cả các số tự nhiên (và chỉ chúng),
b) tất cả các số $1/n$,
b) mọi số hữu tỉ.

10. a) Tìm một dãy thỏa mãn bài toán 9a mà không chứa bất kỳ số nguyên nào.
6) Cho $\{x_n\}$ thỏa mãn bài toán 96. Liệu 0 có thể không là điểm giới hạn của nó không?
b) Liệt kê tất cả các điểm giới hạn của dãy thỏa mãn bài toán 9b.

16 điều kiện. “Apu” trong tiếng Anh có nghĩa là “bất kỳ”, “Exist” có nghĩa là “tồn tại”. Các ký hiệu $\vee$ và $\exists$ - đảo ngược các chữ cái đầu tiên của các từ này - tương ứng:
“dành cho bất cứ ai” và “có cái gì đó ... cái đó.”
Hãy xem xét 16 điều kiện sau:

1) $\exists \varepsilon > 0 \exists k \exists n > k |x_n - a| < \varepsilon$,
2) $\exists \varepsilon > 0 \exists k \exists n > k |x_n - a| \geqslant \varepsilon$,
3) $\exists \varepsilon > 0 \exists k \forall n > k |x_n - a| < \varepsilon$,
4) $\exists \varepsilon > 0 \exists k \forall n > k |x_n - a| \geqslant \varepsilon$,
5) $\exists \varepsilon > 0 \forall k \exists n > k |x_n - a| < \varepsilon$,
6) $\exists \varepsilon > 0 \forall k \exists n > k |x_n - a| \geqslant \varepsilon$,
7) $\exists \varepsilon > 0 \forall k \forall n > k |x_n - a| < \varepsilon$,
8) $\exists \varepsilon > 0 \forall k \forall n > k |x_n - a| \geqslant \varepsilon$,
9) $\forall \varepsilon > 0 \exists k \exists n > k |x_n - a| < \varepsilon$,
10) $\forall \varepsilon > 0 \exists k \exists n > k |x_n - a| \geqslant \varepsilon$,
11) $\forall \varepsilon > 0 \exists k \forall n > k |x_n - a| < \varepsilon$,
12) $\forall \varepsilon > 0 \exists k \forall n > k |x_n - a| \geqslant \varepsilon$,
13) $\forall \varepsilon > 0 \forall k \exists n > k |x_n - a| < \varepsilon$,
14) $\forall \varepsilon > 0 \forall k \exists n > k |x_n - a| \geqslant \varepsilon$,
15) $\forall \varepsilon > 0 \forall k \forall n > k |x_n - a| < \varepsilon$,
16) $\forall \varepsilon > 0 \forall k \forall n > k |x_n - a| \geqslant \varepsilon$.

11. Điều kiện nào trong số này thể hiện các thuộc tính của một dãy đã quen thuộc với bạn (bị giới hạn, có $a$ làm giới hạn hoặc điểm giới hạn, có xu hướng tiến tới vô cùng) hoặc sự phủ định của các thuộc tính này? Ý nghĩa của các điều kiện còn lại là gì?

Về giới hạn 6. Dãy số $\{x_n\}$ được gọi là *đơn điệu* nếu một trong hai điều kiện được thỏa mãn:
1) $x_1 \leqslant x_2 \leqslant x_3 \leqslant \dots \leqslant x_n \leqslant \dots$,
2) $x_1 \geqslant x_2 \geqslant x_3 \geqslant \dots \geqslant x_n \geqslant \dots$.
Trong trường hợp đầu tiên, $\{x_n\}$ được gọi là *tăng*, trong trường hợp thứ hai - *giảm*.

12. a) Chứng minh rằng dãy bất kỳ đều chứa dãy con đơn điệu.
6) Chứng minh rằng điểm giới hạn của dãy đơn điệu chính là giới hạn của nó.
b) Chứng minh rằng mọi dãy giới hạn đơn điệu đều có giới hạn (đôi khi tính chất này của số thực được coi là tiên đề).
13. a) Chứng minh rằng mọi dãy bị chặn đều có ít nhất một điểm giới hạn.
6) Kiểm tra xem các câu 12c và 13a có tương đương nhau không: mỗi câu có thể được suy ra từ câu kia (vì vậy 13a cũng có thể được coi là một tiên đề).
14. a) Đặt $|q| < 1$, $s_n = 1 + q + \dots + q^{n-1}$. Chứng minh rằng dãy $\{s_n\}$ hội tụ và

⟦folio 31⟧

tìm giới hạn của nó.

6) Kiểm tra xem $|q| \geq 1$ chuỗi $\{s_n\}$ không có giới hạn.

15. Đặt $x_n \rightarrow a$, $y_n \rightarrow b$ tại $n \rightarrow \infty$. Chứng minh rằng sau đó

a) $x_n + y_n \rightarrow a + b$,
b) $x_n - y_n \rightarrow a - b$,
c) $x_n y_n \rightarrow ab$,
d) nếu $b \neq 0$ thì $x_n/y_n \rightarrow a/b$.

Quét. Trong số $y_n$ có thể có số 0, nhưng nếu $b \neq 0$ thì chỉ có (chứng minh điều này) một số hữu hạn: $\exists N \forall n > N y_n \neq 0$; chuỗi $x_n/y_n$ phụ thuộc vào giới hạn, do đó, đối với $n > N$.

e) Nếu $b = 0$, thì dãy $x_n/y_n$ (nếu được xác định) có thể không có giới hạn, có thể tiến tới bất kỳ số nào hoặc tiến tới vô cùng—cho ví dụ liên quan.

16. a) Chứng minh rằng nếu $x_n \geq 0$ với mọi $n$ và $x_n \rightarrow a$ với $n \rightarrow \infty$ thì $a \geq 0$.

6) Có thể nói rằng $\lim_{n \rightarrow \infty} x_n > 0$ nếu mọi thứ đều là $x_n > 0$?

b) Đặt $x_n \leq y_n \leq z_n$ và đặt $x_n \rightarrow a$ và $z_n \rightarrow a$ tại $n \rightarrow \infty$. Chứng minh rằng khi đó $y_n \rightarrow a$ cho $n \rightarrow \infty$.

17. a) Dãy số $\{x_n\}$ có tính chất sau: với mọi $\varepsilon > 0$ tồn tại một $k$ sao cho với mọi $n > k$ và mọi số tự nhiên $p$
$$|x_{n+p} - x_n| < \varepsilon.$$
Chứng minh rằng $\{x_n\}$ có giới hạn.

6) Chứng minh điều ngược lại: nếu $x_n$ là dãy hội tụ thì $\forall \varepsilon > 0 \exists k \forall n > k \forall p |x_{n+p} - x_n| < \varepsilon.$
b) Dãy số $\{x_n\}$ có tính chất sau: $\forall \varepsilon > 0 \exists k \forall n > k |x_{n+p} - x_n| < \varepsilon.$
$\{x_n\}$ có bắt buộc đối với tài sản không?

18. Hãy xây dựng dãy $\{x_n\}$ như sau: $|x_n| = 1/2^n$, chọn các dấu $x_1, x_2, x_3, \dots$ tùy ý. Tiếp theo chúng ta đặt $s_n = x_1 + \dots + x_n$.

a) Chứng minh dãy $\{s_n\}$ hội tụ.

6) Liệt kê tất cả các giá trị mà $\lim_{n \rightarrow \infty} s_n$ có thể nhận (khi các dấu $x_n$ được chọn theo đủ mọi cách khác nhau).

Phức tạp $\{x_n\}$. Cho đến đây chúng ta đã xem xét các dãy gồm các số thực.

Bây giờ đặt $x_n$ là số phức bất kỳ.

Định nghĩa về giới hạn trong trường hợp này về mặt nghĩa đen cũng giống như trước đây. Nhưng ý nghĩa hình học của nó lại khác: bất đẳng thức $|x_n - a| < \varepsilon$ bây giờ có nghĩa là $x_n$ nằm bên trong một đường tròn bán kính $\varepsilon$ với tâm là điểm $a$; Do đó, số $a$ đóng vai trò là giới hạn của $\{x_n\}$, nếu tất cả các đường tròn có tâm $a$ chỉ nằm ở số hữu hạn $\{x_n\}$.

19. a) Đặt $x_n = a_n + ib_n$. Dãy số $\{x_n\}$ hội tụ khi và chỉ khi dãy $\{a_n\}$ và $\{b_n\}$ hội tụ. Chứng minh điều đó.

6) Đặt $|x_n| = r_n$, lập luận $x_n = \alpha_n$. Có đúng là $\{x_n\}$ hội tụ khi và chỉ khi cả $\{r_n\}$ và $\{\alpha_n\}$ hội tụ?

20. Để dãy $\{x_n\}$ tiến về 0. Chúng ta xây dựng dãy $\{s_n\}$ như thế này:
$$s_1 = x_1, \quad s_2 = x_1 + x_2, \dots, \quad s_n = x_1 + x_2 + \dots + x_n, \dots$$
Tìm hiểu xem $\{s_n\}$ có thể có chính xác hai điểm giới hạn hay không:

a) nếu $x_n$ là số thực,
b) nếu $x_n$ là số phức (trong trường hợp này định nghĩa về điểm giới hạn theo nghĩa đen giống như trước).
