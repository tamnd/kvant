---
id: 1985-11-abramov-samyiy-znamenityiy-algoritm-d8d7742e
issue: kvant_1985_11
year: 1985
number: "11"
title: Thuật toán nổi tiếng nhất
authors:
  - Абрамов С. А.
rubric: raznoe
rubric_sub: Разное
page_first: 46
page_last: 48
page_labels: 44-46
tag: 3RZO
lang: vi
source: kvant_digital
extraction: vision
content_sha256: e913f438d7a3f498ce5ef5dc25c384f980fed8d1e62ee77bc9d1de33435c2647
prompt_sha256: draft-1
translated_from: content/ru/1985/11/articles/19_abramov-samyiy-znamenityiy-algoritm-d8d7742e.md
source_content_sha256: 7ac6736602d20b5f6323cba2ebd95222a6a7461dcd42d4a9e0667133b10871f2
translation_model: draft
translation_run: vi-draft-2026-10-31
translation_quality: draft
---

⟦folio 44⟧

Thuật toán nổi tiếng nhất

Các bài viết trước trong phần này đã cung cấp các ví dụ mở rộng về thuật toán và nói về các nguyên tắc chung để viết chúng bằng ngôn ngữ thuật toán. Ở đây tác giả đã trình bày chi tiết về một thuật toán duy nhất - đây là một trong những thuật toán toán học cổ xưa nhất và có lẽ là nổi tiếng nhất.

Tiến sĩ Vật lý và Toán học
S. A. ABRAMOV

Trong Euclid's Elements, một thuật toán được đưa ra để tìm ước số lớn nhất (GCD) của các số nguyên không âm, dựa trên các tính chất sau của đại lượng này. Đặt $f$ và $g$ đồng thời là các số nguyên không âm khác 0 và đặt $f \geq g$. Sau đó, nếu $g=0$ thì gcd $(f,g)=f$ và nếu $g \neq 0$ thì đối với các số $f, g$ và $r$, trong đó $r$ là phần dư của phép chia $f$ cho $g$, đẳng thức gcd $(f,g)=\text{НОД}(g,r)$ đúng: với mọi số nguyên $a$ các số $f$ và $g$ có cùng ước chung với các số $g, f-ag$ và phần còn lại $r$ là một số có dạng $f-ag$.

Áp dụng thuật toán Euclidean cho các số $f$ và $g$ bao gồm việc thực hiện một loạt các bước lần lượt từng bước, mỗi bước bắt đầu bằng việc kiểm tra xem số thứ hai có bằng 0 hay không. Nếu không bằng nhau thì phần dư của phép chia số thứ nhất cho số thứ hai được tính, sau đó số thứ nhất được thay thế bằng số thứ hai và số thứ hai bằng phần dư được tính toán và quá trình chuyển sang bước tiếp theo sẽ diễn ra. Nếu số thứ hai bằng 0 thì mọi phép tính sẽ dừng lại và số đầu tiên được khai báo là giá trị GCD.

Vì vậy, khi tính GCD (39,15), nó chuyển từ cặp số này sang cặp số khác theo trình tự sau: (39,15), (15,9), (9,6), (6,3), (3,0). Chúng tôi nhận được GCD (39,15) = 3.

Số dư luôn nhỏ hơn số chia và dãy số nguyên không âm giảm dần không thể là vô hạn. Do đó, việc áp dụng thuật toán Euclide sẽ kết thúc ở một số bước do số dư tiếp theo sẽ bằng 0.

Bài tập 1. Tìm GCD (21042, 18921).
Nhiệm vụ 2. Hủy bỏ hoàn toàn phân số được viết là $\underbrace{3\dots3}_{n}$ và giá trị được viết là $-3\dots3, m>n$.

***

Hầu hết các thuật toán cổ xưa theo thời gian đã bị loại bỏ khỏi máy tính.

⟦folio 45⟧

thực hành thực tế các thuật toán mới hơn. Thuật toán Euclid tránh được phần này chủ yếu do tính phân tích của nó. Giá trị của GCD(f,g) có thể được tính theo nhiều cách, chẳng hạn như sử dụng thuật toán tầm thường sau: nếu $g=0$, thì lấy giá trị $f$ làm GCD(f,g), nếu không thì chọn từ các số $g,g-1,...,1$ của số đầu tiên, khi chia cho $f$ ngắn hơn và $g$ cho số dư bằng 0. Tuy nhiên, giống như các thuật toán tương tự khác, thuật toán cuối cùng quá lãng phí. Ví dụ: trong trường hợp nguyên tố cùng nhau $f$ và $g$, nó yêu cầu phép chia $2g$. Bây giờ chúng ta hãy kiểm tra số phép chia mà thuật toán Euclide yêu cầu và chỉ ra rằng đối với các giá trị lớn $g$ thì nó tồn tại nhỏ hơn $2g$. Chúng ta sẽ xem xét trình tự của tất cả các số dư được tính toán trong quá trình thực hiện thuật toán Euclide. Sẽ rất hữu ích khi biểu thị các số ban đầu không phải bằng $f,g$ mà bằng $f_0,f_1$ (chúng tôi giả định rằng $f_0>f_1$). Chúng tôi biểu thị số dư khác 0 thu được bằng $f_2,...,f_n$ và thương số khi chia $f_0$ cho $f_1,f_1$ cho $f_2,...,f_{n-1}$ cho $f_n$ cho $a_1,a_2,...,a_n$:

$$\begin{align*}
f_0 &= a_1f_1 + f_2, \\
f_1 &= a_2f_2 + f_3 \\
\cdots \\
f_{n-2} &= a_{n-1} + f_n, \\
f_{n-1} &= a_nf_n;
\end{align*}$$

ở đây GCD($f_0,f_1$)=$f_n$. Số dư luôn nhỏ hơn số chia nên $f_0>f_1>f_2>...>f_n>0$. Kết quả là mỗi thương số $a_1,...,a_n$ lớn hơn hoặc bằng một.

Bổ đề 1. Với $i=1,2,...,n-2$ bất đẳng thức $f_i>2f_{i+2}$ đúng.

Bằng chứng. $f_i = a_{i+1}f_{i+1} + f_{i+2} \geq f_{i+1} + f_{i+2} > 2f_{i+2}$.

Bổ đề 2. Cho $k$ là một số tự nhiên sao cho việc áp dụng thuật toán Euclide cho $f_0,f_1$ không kết thúc sau $2k$ phép chia (tức là $f_{2k+1} \geq 1$). Sau đó $f_1>2^k$.

Bằng chứng. Sử dụng Bổ đề 1, chúng ta có được

$$f_1 > 2f_3 > 4f_5 > ... > 2^k f_{2k+1} \geq 2^k.$$

Định lý. Số phép chia mà thuật toán Euclide yêu cầu không vượt quá $2[\log_2 f_1]+2^*$.

Bằng chứng. Theo Bổ đề 2, nếu $k$ là một số tự nhiên thỏa mãn $f_1 \leq 2^k$ thì số đó

$$\begin{align*}
p - a_{i+1}s) + f_1(q - a_{i+1}t) = f_{i+2}.
\end{align*}$$

Vì vậy, đối với lời giải bài toán (2) cần áp dụng thuật toán Euclide cho $f$ và $g$, xét ở mỗi bước áp dụng, ngoài hai số đã xét trước còn có thừa số $p,q$ và $s,t$ tương ứng với các số này. Ở bước đầu tiên, với tư cách là số nhân, đồng

⟦folio 46⟧

tương ứng với số ban đầu $f$ và $g$ thì lấy 1,0 và 0,1. Để thực hiện phép chia và nhận được phần $a$ và một phần dư, nếu phần dư không bằng 0, trước khi chuyển sang bước tiếp theo, hãy tính bằng các công thức $p - as$, $q - at$ các thừa số tương ứng để lấy phần dư. Phần dư cuối cùng khác 0 và các thừa số tương ứng của nó $u$ và $v$ sẽ thỏa mãn (2).

Trong quá trình áp dụng thuật toán này cho $f = 39$, $g = 15$ số dư 9 được tính tuần tự; 6; 3; 0 và các số nhân tương ứng 1, -2; -1,3; 2, -5. Vì vậy, $39 \cdot 2 + 15 \cdot (-5) = 3 = \text{НОД}(39,15)$.

Bây giờ hãy lưu ý rằng thuật toán có thể được thay đổi để số lượng thao tác mà nó yêu cầu giảm gần một lần rưỡi: trong hai số $u$ và $v$, chỉ cần tính $v$ cùng với $\text{НОД}(f,g)$, sau đó xác định $u$ bằng công thức $u = (\text{НОД}(f,g) - gv)/f$. Đối với $f = 39$, $g = 15$ chúng ta có thể đặt $u = (3 - 15 \times (-5))/39 = 2$.

Bài 4. Chứng minh rằng nếu các số $x$, $y$ cho phương trình lời giải (3) thì tất cả lời giải đều được mô tả bởi công thức $x = x + l't$, $y = y - k't$, trong đó $k' = k/\text{НОД}(k,l)$, $l' = l/\text{НОД}(k,l)$, $t = 0$, $\pm 1$, $\pm 2$.

Bài toán 5. Sử dụng các công thức được viết trong bài toán 4, hãy mô tả một thuật toán cho phép bạn kiểm tra xem phương trình (3) có lời giải là số nguyên không âm hay không và nếu có, thì nó cho phép bạn xây dựng một lời giải như vậy.

***

Các phép chia liên tiếp có phần dư, tương ứng với sơ đồ (1), cũng tạo thành cơ sở của thuật toán phân số nguyên, cho phép người ta thu được các giá trị gần đúng rất thú vị của số $f_1/f_0$. Một phân số tiếp tục (hữu hạn) là một biểu thức có dạng

$$\frac{1}{b_1 + \frac{1}{b_2} + \dots + \frac{1}{b_k}}$$

trong đó $b_1, \dots, b_k$ là số tự nhiên. Phân số tiếp theo (5) được viết ngắn gọn là $[b_1, b_2, \dots, b_k]$. Vì $f_0 = a_1 f_1 + f_2$, chúng ta có

$$\frac{f_1}{f_0} = \frac{1}{f_0} = \frac{1}{a_1 + f_2}$$

Tiếp theo, chúng ta biến đổi $f_2$ theo cách tương tự, v.v. Cuối cùng, chúng ta nhận được $f_1/f_0 = [a_1, a_2, \dots, a_n]$. Ngoài ra, chúng ta sẽ xem xét các phân số nguyên $[a_1], [a_1, a_2], \dots, [a_1, \dots, a_{n-1}]$, các giá trị của chúng được gọi là *phân số gật đầu* của số $f_1/f_2$. Chúng ta hãy biểu thị dạng tối giản của các phân số thích hợp bằng $p_1/q_1, \dots, p_{n-1}/q_{n-1}$. Chúng tôi trình bày các tính chất gần đúng sau của số $f_1/f_0$ bằng các phân số phù hợp mà không cần chứng minh:

a) $$\frac{f_1}{f_0} - \frac{p_i}{q_i} < \frac{1}{q_i^2}, \quad i = 1, 2, \dots, n - 1$$

b) Nếu đối với một số phân số $u/v$ và phân số phù hợp $p_i/q_i$, $i \leqslant i \leqslant n - 1$,

$$\left| \frac{f_1}{f_0} - \frac{u}{v} \right| < \left| \frac{f_1}{f_0} - \frac{p_i}{q_i} \right|,$$

thì $v > q_i$.

Dễ dàng nhận thấy các phân số thích hợp cho số 15/39 (dạng tối giản của nó là 5/13) là 1/2, 1/3, 2/5. Hiệu giữa số tối giản và phân số này lần lượt bằng -3/26, 2/39, -1/65.

Thuộc tính a), b) được sử dụng trong lời giải nhiều loại bài toán thực tế khác nhau, yêu cầu lựa chọn một số không nguyên cho trước của một xấp xỉ tốt ở dạng phân số có giá trị tương đối nhỏ. Một ví dụ là bài toán tính toán một bộ truyền bánh răng gồm hai bánh răng. Số truyền phải gần với giá trị được chỉ định và số răng của mỗi bánh răng không được vượt quá giới hạn quy định nhất định.

Bài 6. Một năm Trái Đất có 365,242199 ngày. Tìm các phân số thích hợp của số $\frac{242199}{1000000}$. Phân số nào sau đây xác định quy luật luân phiên giữa năm đơn giản và năm hiệu quả cao trong lịch hiện đại?

Bài 7. Viết các thuật toán sau dưới dạng chương trình bằng ngôn ngữ thuật toán trong SGK (xem thêm bài của A. P. Ershov ở số trước):

a) thuật toán tầm thường để tính GCD;

b) Thuật toán Euclide tính GCD;

c) thuật toán lời giải cho phương trình số nguyên có dạng $kx + ly = m$;

d) thuật toán biểu diễn tỷ lệ $f_0/f_1$ dưới dạng phân số liên tục.

***

Thuật toán Euclid cũng cho phép các khái quát hóa khác, đặc biệt, được sử dụng trong phép tính gần đúng các số vô tỷ và trong tính toán gcd của đa thức. Vì vậy, trong thực tiễn tính toán hiện đại, dựa trên việc sử dụng máy tính điện tử, đã có một ứng dụng của thuật toán này đã có từ 2300 năm trước.
