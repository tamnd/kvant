---
id: 1992-10-solovev-predel-posledovatelnosti-5bc3aef3
issue: kvant_1992_10
year: 1992
number: "10"
title: Giới hạn trình tự
authors:
  - Соловьёв Ю. П.
rubric: shkola-v-kvante
rubric_sub: Школа в «Кванте»
page_first: 45
page_last: 51
page_labels: 43-49
lang: vi
source: kvant_digital
extraction: vision
content_sha256: bdce556c1296322752a65a82d657cbfa7aa0ad525e5ed5807e880c0cb1eca8d5
prompt_sha256: draft-1
translated_from: content/ru/1992/10/articles/14_solovev-predel-posledovatelnosti-5bc3aef3.md
source_content_sha256: 7174b3676fdd66ddbf24027a4671ddf4479367098a9e12550109c88e2e289d40
translation_model: draft
translation_run: vi-draft-gaps-2026-11-07
translation_quality: draft
---

⟦folio 43⟧

---
running_head:
folio:
---

Giới hạn
trình tự
Tiến sĩ Khoa học Vật lý và Toán học
Y. SOLOVIEV

Các khái niệm và phát biểu cơ bản

Cho mỗi số tự nhiên $n$ liên kết với một số thực $a_n$. Tập hợp các số $\{a_n\}$, trong đó $n=1,2,...$, được gọi là dãy số hoặc đơn giản là dãy số; mỗi số $a_n$ được gọi là một phần tử hoặc thành viên của chuỗi này và $n$ là số của nó.

Dãy số là trường hợp đặc biệt của hàm, cụ thể dãy là hàm được xác định trên tập hợp số tự nhiên và lấy các giá trị trong tập hợp số thực.

Làm thế nào để thiết lập một dãy số? Tự nhiên nhất là phương pháp phân tích, trong đó chỉ ra rõ ràng những hành động nào cần được thực hiện trên số $n$ để thu được số hạng tổng quát của dãy $a_n=f(n)$.

Ví dụ về các biện pháp
1. Tiếp theo
$$1, \frac{1}{2}, \frac{1}{3}, \frac{1}{4},...$$

có một số hạng chung $a_n=\frac{1}{n}$.

2. Tiếp theo
$$1, -1, 1, -1, 1, -1, ...$$

được cho bằng $a_n=(-1)^{n+1}$ hoặc $a_n=\sin \frac{(2n-1)\pi}{2}$.

Một cách phổ biến khác để xác định trình tự là phương pháp lặp lại. Anh ta nêu tên những hành động cần thực hiện đối với các thành viên đã được tính toán của trình tự

⟦folio 44⟧

---
running_head:
folio:
---

để có được học kỳ tiếp theo - $a_{n+1}$; Ngoài ra, một số thuật ngữ đầu tiên phải được chỉ định (tùy thuộc vào tính chất của sự phụ thuộc) - cái gọi là dữ liệu ban đầu.

Ví dụ về các biện pháp
1. Cấp số cộng được xác định bởi sự phụ thuộc lặp lại
$$a_{n+1} = a_n + d, n = 1, 2, 3, \dots$$
với dữ liệu ban đầu $a_1 = a$.
Trình tự này trông giống như
$$a, a + d, a + 2d, \dots, a + (n-1)d, \dots$$
2. Dãy số Fibonacci được xác định bởi điều kiện
$$a_{n+1} = a_n + a_{n+1}, n = 1, 2, \dots$$
và dữ liệu ban đầu $a_1 = 1, a_2 = 1$.
Trình tự trông giống như
$$1, 1, 2, 3, 5, 8, 13, 21, 34, \dots$$
Trình tự này có thể thu được ở dạng tương tự:
$$a_n = \frac{1}{\sqrt{5}} \left\{ \left( \frac{1+\sqrt{5}}{2} \right)^n - \left( \frac{1-\sqrt{5}}{2} \right)^n \right\},$$
$$n = 1, 2, \dots$$
Dãy số $\{a_n\}$ được gọi là
a) bị chặn ở trên nếu tất cả các số hạng của nó nhỏ hơn cùng một số $M: a_n < M, n = 1, 2, 3, \dots$
b) bị giới hạn, nếu nó bị giới hạn cả trên và dưới:
$$m < a_n < M, n = 1, 2, 3, \dots$$
Bây giờ hãy xây dựng định nghĩa chính của chúng tôi.
Một số a được gọi là giới hạn của dãy $\{a_n\}$ nếu với bất kỳ $\varepsilon > 0$ nào người ta có thể chỉ định một số $N$ sao cho với mọi số $n \geq N$ thì bất đẳng thức đúng
$$|a_n - a| < \varepsilon.$$
Đồng thời họ viết
$$\lim_{n \to \infty} a_n = a$$ hoặc
$$a_n \longrightarrow a.$$
Dãy số có giới hạn gọi là dãy hội tụ.
Bây giờ chúng ta giới thiệu các dãy có giới hạn là vô cùng. Những chuỗi như vậy được gọi là vô cùng lớn và được định nghĩa như sau:
Dãy $\{a_n\}$ được gọi là vô cùng lớn nếu với bất kỳ số $\varepsilon$ nào cũng tồn tại một số $N$ sao cho bất đẳng thức $|a_n| > \varepsilon$ đúng với mọi $n \geq N$.
Nếu trình tự sao cho $a_n > \varepsilon$ thì chúng ta viết $\lim_{n \to \infty} a_n = +\infty$, nhưng nếu $a_n > -\varepsilon$ thì chúng ta sử dụng ký hiệu $\lim_{n \to \infty} a_n = -\infty$. Trong mọi trường hợp, chuỗi $\{a_n\}$ được cho là có giới hạn vô hạn bằng $+\infty$ hoặc $-\infty$.
Cơ sở để tính toán các giới hạn thực sự là bốn định lý sau.
Định lý 1. Nếu dãy $\{a_n\}$ và $\{b_n\}$ có giới hạn:
$$\lim_{n \to \infty} a_n = a, \lim_{n \to \infty} b_n = b,$$ thì dãy $\{a_n + b_n\}$ cũng có giới hạn
$$\lim_{n \to \infty} (a_n + b_n) = a + b.$$
Định lý 2. Với cùng giả thiết, dãy $\{a_n - b_n\}$ có giới hạn
$$\lim_{n \to \infty} (a_n - b_n) = a - b.$$
Định lý 3. Với cùng giả thiết, dãy $\{a_n b_n\}$ có giới hạn
$$\lim_{n \to \infty} a_n b_n = ab.$$
Định lý 4. Với cùng giả định và điều kiện bổ sung $b \neq 0$, dãy $\{a_n / b_n\}$ có giới hạn
$$\lim_{n \to \infty} \frac{a_n}{b_n} = \frac{a}{b}.$$
Rất thường xuyên, Định lý 1 được phát biểu ngắn gọn: “Giới hạn của tổng bằng tổng của các giới hạn” và được viết dưới dạng
$$\lim_{n \to \infty} (a_n + b_n) = \lim_{n \to \infty} a_n + \lim_{n \to \infty} b_n,$$
và các điều kiện của định lý được ngụ ý. Dấu vết thay thế tương tự áp dụng cho Định lý 2-4.

⟦folio 45⟧

---
running_head:
folio:
---

Chứng minh của cả bốn định lý ít nhiều giống nhau nên chúng ta sẽ chỉ chứng minh Định lý 1.

Bằng chứng. Chúng ta được biết rằng với $n$ đủ lớn thì độ lệch $|a_n - a|$ và $|b_n - b|$ trở nên nhỏ một cách thích hợp. Cần phải chứng minh điều tương tự đối với sai lệch

$$|(a_n + b_n) - (a + b)|.$$

Theo tính chất giá trị tuyệt đối ta có:

$$|(a_n + b_n) - (a + b)| = |(a_n - a) + (b_n - b)| \leqslant |a_n - a| + |b_n - b|$$

Cho một số $\varepsilon > 0$. Khi đó chúng ta có thể chọn $N_1$ sao cho $n > N_1$

$$|a_n - a| < \frac{\varepsilon}{2},$$

và $N_2$ như vậy tại $n > N_2$

$$|b_n - b| < \frac{\varepsilon}{2}.$$

Trong trường hợp này, biểu thị bằng $N$ phần lớn các số $N_1$ và $N_2$, ta sẽ có cho $n > N$

$$|(a_n + b_n) - (a + b)| \leqslant |a_n - a| + |b_n - b| < \frac{\varepsilon}{2} + \frac{\varepsilon}{2} = \varepsilon,$$

Q.E.D.

Bây giờ chúng ta hãy giới thiệu định nghĩa sau đây. Dãy số $\{a_n\}$ được gọi là không giảm (không tăng) nếu với mỗi $n = 1, 2, \dots$ bất đẳng thức $a_n \leqslant a_{n+1}$ (tương ứng, bất đẳng thức $a_n \geqslant a_{n+1}$) đúng. Dãy số không tăng và không giảm được gọi là dãy đơn điệu. Nếu tất cả các bất đẳng thức nêu trên là nghiêm ngặt thì dãy được gọi là tăng (giảm). Ví dụ: chuỗi $\left\{\frac{1}{n^2}\right\}$ tiêu diệt, chuỗi $\{n\}$ tăng lên và chuỗi $\left\{\sin \frac{\pi n}{2}\right\}$ không đơn điệu.

Trong lý thuyết giới hạn, tính chất sau của số thực, thường được coi là tiên đề, là rất quan trọng.

Tiên đề Bolshano-Weierstrass. Mọi dãy không giảm (không tăng) đều có một giới hạn - hữu hạn nếu nó bị chặn từ trên (từ dưới) và vô hạn, bằng $+\infty$ ($-\infty$) nếu nó bị chặn từ trên (tương ứng từ dưới).

Trong một khóa học giải tích, người ta đã chứng minh rằng tiên đề Bolshano-Weierstrass tương đương với mỗi phát biểu sau:

nếu một chuỗi vô hạn các đoạn được xây dựng trên một trục số sao cho mỗi đoạn tiếp theo là đoạn trước đó thì tất cả các đoạn đều có ít nhất một điểm chung;

Mỗi số thực có thể được viết dưới dạng phân số vô hạn (định kỳ hoặc không tuần hoàn) và mỗi phân số như vậy tương ứng với một số thực nhất định.

Nếu một trong những mệnh đề này được coi là một tiên đề thì mệnh đề thứ hai và tiên đề Bolshano-Weierstrass sẽ trở thành những định lý có thể được chứng minh.

Định lý 5. Từ bất kỳ dãy số nào chứa một tập hợp số vô hạn, chúng ta có thể chọn một dãy số khác có xu hướng tiến tới một giới hạn hữu hạn hoặc vô hạn nào đó.

Bằng chứng. Nếu một dãy số nhất định $\{a_n\}$ chỉ chứa một tập hợp hữu hạn các số không vượt quá $a_1$ thì nó nhất thiết phải chứa một tập hợp vô hạn các số lớn hơn $a_1$. Để giải quyết một trường hợp cụ thể, chúng tôi sẽ giả sử rằng chuỗi của chúng tôi chứa vô số số lớn hơn $a_1$. Đặt một trong số chúng là $a_{r_1}$. Có thể trong số các số theo sau nó sẽ có số $a_{r_2} > a_{r_1}$, trong số các số theo sau $a_{r_2}$ sẽ có số $a_{r_3} > a_{r_2}$, v.v. Nếu chúng ta tiếp tục lựa chọn các số này vô thời hạn, thì từ chuỗi này sẽ xuất hiện một chuỗi, theo tiên đề Bolshano-Weierstrass, có giới hạn hữu hạn hoặc vô hạn.

⟦folio 46⟧

---
running_head:
folio:
---

Nếu không, bạn sẽ gặp một số $a_{r_i}$ không vượt quá bất kỳ số nào theo sau nó; từ đó làm nổi bật dãy số cuối cùng

$$a_1 < a_{r_1} < a_{r_2} < \dots < a_{r_i}.$$

Trong số các số theo sau $a_{r_i}$, theo giả định, sẽ lại có vô số số lớn hơn $a_1$, nhưng không lớn hơn $a_{r_i}$. Bắt đầu từ một trong số chúng, chẳng hạn như $a_{s_1}$, chúng ta soạn, giống như chuỗi trước, một chuỗi tăng dần, giống như chuỗi đầu tiên, sẽ tiếp tục vô tận (và sau đó định lý sẽ được chứng minh) hoặc sẽ kết thúc ở một số $a_{s_j}$, không vượt quá bất kỳ số nào tiếp theo, nhưng bản thân nó sẽ không lớn hơn $a_{r_i}$. Như vậy sẽ thu được một dãy số hữu hạn mới

$$a_1 < a_{s_1} < a_{s_2} < \dots < a_{s_j}, a_{r_i} \geq a_{s_j}.$$

Tiếp tục làm như vậy, ta được dãy chuỗi

$$a_1 < a_{r_1} < a_{r_2} < \dots < a_{r_i}, a_1 < a_{s_1} < a_{s_2} < \dots < a_{s_j}, a_1 < a_{t_1} < a_{t_2} < \dots < a_{t_k},$$

......

Trong trường hợp này, hoặc chúng ta tiến tới một dãy có vô số số hạng tăng dần (và định lý sẽ được chứng minh), hoặc chúng ta thu được một dãy gồm vô số số hạng không tăng

$$a_{r_i} \geq a_{s_j} \geq a_{t_k} \geq \dots,$$

mà theo tiên đề Bolshano-Weierstrass, có giới hạn hữu hạn, vì tất cả chúng đều lớn hơn $a_1$.

Định lý 6. Cho $\{a_n\}$ và $\{b_n\}$ là hai dãy có các tính chất sau:

1) nếu từ $\{a_n\}$ một chuỗi $\{a_{r_i}\}$ được chọn, có xu hướng tiến tới giới hạn $a$, thì theo chuỗi $\{b_{r_i}\}$ có xu hướng tiến tới giới hạn nào đó $b$;

2) các giá trị khác nhau của giới hạn a tương ứng với các giá trị khác nhau của giới hạn $b$.

Khi đó, nếu $\{b_n\}$ có một giới hạn nhất định thì $u \{a_n\}$ cũng có một giới hạn nhất định.

Bằng chứng. Hãy tranh luận bằng sự mâu thuẫn. Thật vậy, nếu dãy $\{a_n\}$ không có một giới hạn nhất định, thì chúng ta có thể phân biệt với nó những dãy con có các giới hạn khác nhau $a$, tương ứng với sự tồn tại của một giá trị nhất định của giới hạn đối với $\{b_n\}$.

Định lý 7. Nếu $\{a_n\}$ là một dãy $u \{b_n\}$ nào đó là một dãy không biên tăng vô hạn thì

$$\lim_{n \to \infty} \frac{a_n}{b_n} = \lim_{n \to \infty} \frac{a_n - a_{n-1}}{b_n - b_{n-1}},$$

(1)

trong câu tồn tại giới hạn thứ hai.

Bằng chứng. Hãy biểu thị bằng $l$ giới hạn ở vế phải của đẳng thức (1). Khi đó có thể tìm được một số $N$ sao cho $n > N$ luôn luôn bằng

$$\left| \frac{a_n - a_{n-1}}{b_n - b_{n-1}} - l \right| < \frac{\varepsilon}{2}.$$

Nói cách khác, mọi phân số

$$\frac{a_{N+1} - a_N}{b_{N+1} - b_N}, \frac{a_{N+2} - a_{N+1}}{b_{N+2} - b_{N+1}}, \dots, \frac{a_n - a_{n-1}}{b_n - b_{n-1}}$$

chứa giữa $l - \frac{\varepsilon}{2}$ và $l + \frac{\varepsilon}{2}$. Đồng thời, vì tất cả các giá trị đều dương nên chúng ta sẽ có

$$\left| \frac{a_n - a_N}{b_n - b_N} - l \right| < \frac{\varepsilon}{2}.$$

Chúng ta lấy $N$ đủ lớn để không chỉ bất đẳng thức cuối cùng đúng mà còn bất đẳng thức $b_N > 0$, điều này luôn có thể xảy ra, bởi vì theo điều kiện $\{b_n\}$ tăng vô hạn. Trên cơ sở tương tự, với $N$ cố định, bạn có thể chọn $n$ sao cho số $\frac{\varepsilon}{2} b_n$ vượt quá giá trị tuyệt đối của số $a_N - lb_N$ và sau đó, khi $n$ tăng lên, luôn lớn hơn số cuối cùng. Bây giờ nhận thấy rằng

⟦folio 47⟧

---
running_head:
folio:
---

$$\frac{a_n}{b_n} - l = \frac{a_N - lb_N}{b_n} + \left(1 - \frac{b_N}{b_n}\right) \left(\frac{a_n - a_N}{b_n - b_N} - l\right),$$

chúng tôi trực tiếp tìm thấy điều đó
$$\left| \frac{a_n}{b_n} - l \right| < \varepsilon,$$ tức là $$\lim \frac{a_n}{b_n} = l.$$

Hệ quả 1. Nếu một dãy số nào đó tiến tới một giới hạn hữu hạn thì trung bình số học và trung bình hình học của n số hạng đầu tiên của nó có xu hướng tiến đến cùng một giới hạn.

Thật vậy, dựa vào định lý cuối cùng ta có
$$\lim_{n \to \infty} \frac{a_1 + a_2 + \dots + a_n}{n} = \lim_{n \to \infty} a_n,$$
(2)
với giả định tồn tại giới hạn ở vế phải.

Dưới đây chúng ta sẽ thấy (ví dụ $3^\circ$ của phần tiếp theo) rằng
$$\lim_{n \to \infty} (\log_b a_n) = \log_b \lim_{n \to \infty} a_n).$$

Xem xét điều này đã được chứng minh và thay thế $a_n$ trong đẳng thức trước đó bằng $\log_b a_n$, chúng ta thu được
$$\lim_{n \to \infty} (\log_b \sqrt[n]{a_1 a_2 \dots a_n}) = \lim_{n \to \infty} (\log_b a_n),$$
Ở đâu
$$\lim_{n \to \infty} \sqrt[n]{a_1 a_2 \dots a_n} = \lim_{n \to \infty} a_n,$$
(3)
với giả định rằng giới hạn ở vế phải của đẳng thức tồn tại.

Hệ quả 2. Nếu trong một dãy $\{a_n\}$ nhất định thì quan hệ $\frac{a_n}{a_{n-1}}$ tiến tới một giới hạn hữu hạn nhất định, thì $\sqrt[n]{a_n}$ cũng hướng đến giới hạn tương tự.

Thật vậy, người ta chỉ cần thay $a_n$ trong đẳng thức (3) bằng $\frac{a_n}{a_{n-1}}$ để có được
$$\lim_{n \to \infty} \sqrt[n]{a_1 \cdot \frac{a_2}{a_1} \cdot \frac{a_3}{a_2} \dots \cdot \frac{a_n}{a_{n-1}}} = \lim_{n \to \infty} \frac{a_n}{a_{n-1}},$$
tức là
$$\lim_{n \to \infty} \sqrt[n]{a_n} = \lim_{n \to \infty} \frac{a_n}{a_{n-1}} \left(= \lim_{n \to \infty} \frac{a_{n+1}}{a_n}\right).$$

Ví dụ tính toán giới hạn
1°. Cho ta một số dương $a$ và cần tìm giới hạn $a^n$ khi $n$ tiến tới vô cùng. Đối với $a=1$ chúng ta luôn có $a^n=1$. Đối với $a<1$, chúng ta có $a^n=a^{n-1} \cdot a < a^{n-1}$, tức là dãy $\{a^n\}$ giảm đơn điệu và do đó, nhờ tiên đề Bolzano-Weierstrass, phải có xu hướng đến giới hạn hữu hạn $l \geq 0$. Nhưng từ đẳng thức $a^n=a^{n-1} \cdot a$ khi đi đến giới hạn thì nó tuân theo $l=la$, tức là $(a-1)l=0$, từ đó $l=0$. Tại $a>1$ chúng ta có $a^n=a^{n-1} \cdot a > a^{n-1}$. Điều này có nghĩa là dãy $\{a_n\}$, phát sinh đơn điệu với $n$, phải có xu hướng đến giới hạn hữu hạn hoặc vô hạn; nhưng giới hạn này không thể hữu hạn, vì nó phải là một số dương $l$, và đẳng thức trước đó khi chuyển đến giới hạn sẽ cho $l=la$, từ đó $l=0$. Vì thế,

$$\lim_{n \to \infty} a^n = \begin{cases} 0 \text{ при } a < 1, \\ 1 \text{ при } a = 1, \\ +\infty \text{ при } a > 1. \end{cases}$$

2°. Giả sử rằng $\lim_{n \to \infty} a_n = a$ tồn tại và đặt $b$ là một số dương nhất định. Hãy tìm giới hạn của dãy $\{b^{a_n}\}$. Trước tiên, chúng ta hãy giả sử rằng $b$ nhỏ hơn một và biểu thị bằng $a_n$ giá trị tuyệt đối của $a_n-a$: $a_n=|a_n-a|$. Nếu bạn được cho một số dương nhỏ $\varepsilon$, thì dựa trên ví dụ trước, bạn có thể tìm thấy một số $m$ sao cho $(1-\varepsilon)^m$ nhỏ hơn $b$. Không thay đổi $m$, hiện tại chúng tôi chọn $n$ sao cho $a_n$ nhỏ hơn $1/m$ và giữ nguyên như vậy khi $n$ xuất hiện xa hơn (điều này có thể xảy ra vì $\lim_{n \to \infty} a_n=0$).

Sau đó chúng ta sẽ có
$$1-b^{a_n} < 1-(1-\varepsilon)^{m a_n} < 1-(1-\varepsilon)=\varepsilon.$$
Từ đây chúng ta có được điều đó
$$\lim_{n \to \infty} b^{a_n} = 1,$$
và do đó, $\lim_{n \to \infty} b^{a_n} = b^a$, tức là $\lim_{n \to \infty} b^{a_n} = b^{\lim_{n \to \infty} a_n}.$

⟦folio 48⟧

---
running_head:
folio:
---

Với $b > 1$ chúng ta có thể viết
$$\lim_{n \to \infty} b^a_n = \frac{1}{\lim_{n \to \infty} b^{-a_n}} = \frac{1}{b^{-a}} = b^a.$$

3°. Giả sử dãy $\{a_n\}$ tiến tới giới hạn $a$ thì ta tìm được giới hạn của dãy $\{\log_b a_n\}$. Hãy đặt $\log_b a_n = c_n$. Sau đó $a_n = b^{c_n}$. Nếu $\{c_n\}$ tiến tới giới hạn $c$ thì theo Ví dụ 2°, dãy $\{a_n\}$ tiến tới giới hạn $b^a$. Do đó (theo Định lý 6) điều ngược lại cũng đúng - nếu có giới hạn $\{a_n\}$ thì cũng có giới hạn $\{c_n\}$, và
$$a = b^c, \quad c = \log_b a.$$
Kể từ đây,
$$\lim_{n \to \infty} (\log_b a_n) = \log_b \left( \lim_{n \to \infty} a_n \right).$$

4°. Đặt các chuỗi $\{a_n\}$, $a_n > 0$ và $\{b_n\}$ lần lượt hướng tới giới hạn $a$ và $b$. Hãy tìm giới hạn của dãy $\{a_n^b_n\}$. Poling $c_n = a_n^{b_n}$, chúng tôi có
$$\log_2 c_n = b_n \log_2 a_n,$$
Ở đâu
$$\lim_{n \to \infty} \log_2 c_n = \log_2 \lim_{n \to \infty} c_n = b \log_2 a = \log_2 a^b.$$
Kể từ đây,
$$\lim_{n \to \infty} a_n^{b_n} = \left( \lim_{n \to \infty} a_n \right)^{\lim_{n \to \infty} b_n}.$$

5°. Bây giờ chúng ta hãy kiểm tra trình tự $\left\{ \left(1 + \frac{1}{n}\right)^n \right\}$.

Trước hết hãy chứng minh một số bất đẳng thức. Giả sử $x_1, x_2, x_3, \dots$ là một số số dương nhỏ hơn 1. Hãy biểu thị bằng $s_{n, r}$ tổng các tích của $n$ các số đầu tiên của một dãy cho trước bằng $r$ thừa số trong mỗi số:
$$s_{n, 1} = x_1 + x_2 + \dots + x_n,$$
$$s_{n, 2} = x_1 x_2 + x_1 x_3 + \dots + x_1 x_n + \dots + x_{n-1} x_n,$$
$$s_{n, n} = x_1 x_2 x_3 \dots x_n.$$
Từ quy tắc nhân các đa thức suy ra
$$\left(1 - x_1\right)\left(1 - x_2\right) \dots \left(1 - x_n\right) = 1 - s_{n, 1} + s_{n, 2} - \dots + (-1)^r \Theta s_{n, r} - x_{n+1} + x_{n+1} s_{n, 1} - \dots + (-1)^r x_{n+1} \times s_{n, r-1} + (-1)^r \Theta x_{n+1} s_{n, r}.$$
Nhận thấy rằng
$$s_{n+1, r} = s_{n, r} + x_{n+1} s_{n, r-1},$$
chúng tôi tìm thấy
$$\left(1 - x_1\right)\left(1 - x_2\right) \dots \left(1 - x_{n+1}\right) = 1 - s_{n+1, 1} + s_{n+1, 2} - \dots + (-1)^r \Theta s_{n, r} - x_{n+1} + x_{n+1} s_{n, 1} - \dots + (-1)^r x_{n+1} \times s_{n, r-1} + (-1)^r \Theta x_{n+1} s_{n, r}.$$
Giá trị trong ngoặc được ước lượng là dương và không vượt quá, đó là điều cần chứng minh.
Một phần, từ công thức (6) cho $x_1 = x_2 = \dots = x_n = x$ và $r = 1$, suy ra $(1 - x)^n > 1 - nx,$
vì trong trường hợp này $s_{n, 1} = nx$. Bây giờ chúng ta hãy sử dụng công thức

⟦folio 49⟧

---
running_head:
folio:
---

(6) và (7) để phân tích chuỗi $a_n = \left(1 + \frac{1}{n}\right)^n$. Từ công thức (7) cho $x = \frac{1}{n^2}$ suy ra rằng
$$\left(1 - \frac{1}{n^2}\right)^n > 1 - \frac{1}{n}, \text{ т. е.}$$
$$\left(1 + \frac{1}{n}\right)^n > \left(1 - \frac{1}{n}\right)^{1-n}.$$
Lưu ý thêm rằng
$$\left(1 - \frac{1}{n}\right)^{1-n} = \left(\frac{n}{n-1}\right)^{n-1} =$
$$= \left(1 + \frac{1}{n-1}\right)^{n-1},$$
(8)
получаем
$$a_n = \left(1 + \frac{1}{n}\right)^n > \left(1 + \frac{1}{n-1}\right)^{n-1} = a_{n-1}.$$
Стою быть, последовательность $\{a_n\}$ монотно возвращает. Но по той же формуле (6)
$$\left(1 - x\right)^n > 1 - \frac{n}{1}x +$
$$+ \frac{n(n-1)}{1 \cdot 2}x^2 - \frac{n(n-1)(n-2)}{1 \cdot 2 \cdot 3}x^3$$
и, в частности, при $x = \frac{1}{n}$
$$\left(1 - \frac{1}{n}\right)^n > \frac{n^2-1}{3n^2} =$
$$= \frac{1}{3}\left(1 - \frac{1}{n}\right)\left(1 + \frac{1}{n}\right) > \frac{1}{3}\left(1 - \frac{1}{n}\right).$$
Và từ đây, sử dụng đẳng thức (8), ta tìm được rằng
$$\left(1 - \frac{1}{n}\right)^{n-1} > \frac{1}{3}, \left(1 + \frac{1}{n-1}\right)^{n-1} < 3.$$
Do đó, chúng ta thấy rằng các số hạng $a_n = \left(1 + \frac{1}{n}\right)^n$, đơn điệu trở lại cùng với $n$, không thể vượt quá số 3. Do đó, dãy $a_n = \left(1 + \frac{1}{n}\right)^n$ có ​​xu hướng đi đến một giới hạn hữu hạn. Giới hạn này được ký hiệu là $e$. Trong các khóa học phân tích toán học, người ta đã chứng minh rằng số $e$ là số vô tỷ và hơn nữa là số siêu việt, tức là nó không phải là gốc của bất kỳ đẳng thức đại số nào với

hệ số mục tiêu. Khá gần đúng bằng nhau
$e \approx 2,718281828459045.$

Bài toán dành cho độc lập lời giải

Tính toán sơ bộ sau:
1. $\lim_{n \to \infty} \frac{n^2 + n + 1}{(n+1)^2}$;
2. $\lim_{n \to \infty} \frac{\sqrt{n^2 + 2}}{n+2}$;
3. $\lim_{n \to \infty} \frac{\sqrt{n^2 + 1} + \sqrt{n}}{4\sqrt{n^3 + n} - n}$;
4. $\lim_{n \to \infty} \left(\frac{1 + 2 + 3 + \dots + n}{n+2} - \frac{n}{2}\right)$;
5. $\lim_{n \to \infty} \frac{1 - 2 + 3 - \dots - 2n}{\sqrt{n^2 + 1}}$;
6. $\lim_{n \to \infty} \frac{1}{n}\left(\left(a + \frac{1}{n}\right)^2 + \left(a + \frac{2}{n}\right)^2 + \dots + \left(a + \frac{n-1}{n}\right)^2\right)$;
7. $\lim_{n \to \infty} \frac{1 \cdot 2 + 2 \cdot 3 + \dots + n(n+1)}{n^3}$;
8. $\lim_{n \to \infty} \left(\sqrt{n^2 + 1} - \sqrt{n^2 - 1}\right)$;
9. $\lim_{n \to \infty} \left(\sqrt{n^2 + n + 1} - \sqrt{n^2 - n + 1}\right)$;
10. $\lim_{n \to \infty} n\left(\sqrt{n^2 + 1} - n\right)$;
11. $\lim_{n \to \infty} \left(n^{\frac{4}{3}} - \left(n^2 - 1\right)^{\frac{2}{3}}\right).$
