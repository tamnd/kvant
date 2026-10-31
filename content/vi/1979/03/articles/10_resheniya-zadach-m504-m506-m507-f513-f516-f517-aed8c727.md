---
id: 1979-3-resheniya-zadach-m504-m506-m507-f513-f516-f517-aed8c727
issue: kvant_1979_3
year: 1979
number: "3"
title: Lời giải bài toán M504, M506, M507; F513, F516, F517
rubric: zadachnik-kvanta
rubric_sub: Задачник «Кванта»
page_first: 36
page_last: 41
page_labels: 34-39
tag: E2WJ
lang: vi
source: kvant_digital
extraction: vision
content_sha256: 0b63b21a3a83d943521ebf47d1f69b43244288975b0b081017f0032840f4b974
prompt_sha256: draft-1
translated_from: content/ru/1979/03/articles/10_resheniya-zadach-m504-m506-m507-f513-f516-f517-aed8c727.md
source_content_sha256: d246add8c37575fd96b1ee545269351ceccdc4ed4e2398d59530cc3e9770fadf
translation_model: draft
translation_run: vi-draft-2026-10-31
translation_quality: draft
---

⟦folio 34⟧

Lời giải bài toán
M504, M506, M507; F513, F516, F517

M504. Trên bàn cờ gồm $n \times n$ ô có $k$ các plimka có kích thước $2 \times 1$ được đặt và không thể đặt plimka thứ $(k+1)$ mà không di chuyển các plimka hiện có. Chứng minh rằng không còn nhiều hơn $a) (n^2+n+1)/3$ ô trống;
$b) (n^2+2)/3$;
$c) n^2/3$.

Có thể có được ước tính mạnh mẽ hơn nữa cho một số $n$ không?

Hình 1.

Hình 2.

Cái lồng này phải được tự do

Hình 3.

Hình 4.

Để có $x$ ô tự do.

a) Chúng ta hãy liên kết từng ô trống không nằm ở chiều ngang phía trên của bảng với một ô “che phủ” nó từ phía trên (Hình 1). Rõ ràng là mỗi ô được liên kết với tối đa một ô (vì vậy số ô trống không nằm trên chiều ngang trên cùng của bảng nhiều nhất là một số ô $\frac{n^2-x}{2}$ được bố trí như đã nêu trong bài toán). Đặt $x_1$ ô trống ở phía trên cùng của bảng; thì $x_1 \leq \frac{n+1}{2}$. Chúng ta có $x-x_1 \leq \frac{n^2-x}{2}$, tức là

$$3x \leq n^2+2x_1 \leq n^2+n+1,$$

Ở đâu

$$x \leq (n^2+n+1)/3.$$

6) Ta ký hiệu bằng $x_1$ số ô trống bên trong bảng, bằng $x_2$ số ô trống ở viền bảng, không tính các ô góc; cuối cùng, bằng $x_3$ chúng ta biểu thị số ô góc trống của bảng. Sau đó $x=x_1+x_2+x_3$. Bằng $y_1$ chúng ta biểu thị số l và tok nằm ngay bên trong bảng; đến $y_2$—số lượng ô kéo dài đến các cạnh của bảng trong ít nhất một hình vuông; thì $y_1+y_2 = \frac{n^2-x}{2}$.

Hãy tính xem một ô trống có bao nhiêu khoảng trắng - đường viền của nó là plimka. Một mặt, có $4x_1+3x_2+2x_3$ trong số đó. Mặt khác, vì các ô được xếp theo cách không thể thêm một ô duy nhất nên không có nhiều hơn $4y_1+3y_2$ các cặp này (mỗi ô đối diện với các cạnh của bảng có viền không quá một hình vuông thứ ba và mỗi ô có đường viền bên trong bảng không quá bốn). Pozny

$$4x_1+3x_2+2x_3 \leq 4y_1+3y_2.$$

Vì hai ô trống trên ranh giới bảng được ngăn cách bằng một ô, nên chúng ta có

$$x_2+x_3 \leq y_2.$$

Cộng các bất đẳng thức (1) và (2), ta thu được

$$4x_1+4x_2+3x_3 \leq 4(y_1+y_2),$$

hoặc

$$x-\frac{1}{4}x_3 \leq \frac{n^2-x}{2}.$$

Nhưng $x_3 \leq 4$; có nghĩa là $x \leq \frac{n^2-x}{2} + 1$ hoặc $3x \leq n^2+2$, do đó $x \leq (n^2+2)/3$.

c) Lưu ý rằng nếu bất đẳng thức (1) là nghiêm ngặt thì chúng ta thu được điều chúng ta cần ở điểm c): bất đẳng thức nghiêm ngặt $x < \frac{n^2-x}{2} + 1$ tương đương như sau:

$$x \leq \frac{n^2-x}{2}, \text{откуда } x \leq \frac{n^2}{3}.$$

Pozny, nếu chúng ta giả sử rằng $x > \frac{n^2}{3}$, thì trong mọi trường hợp, mỗi ô phải liền kề với số lượng ô trống tối đa. Đặc biệt, cạnh nào của quân cờ có chiều dài 1 không vừa với mép bàn cờ thì phải liền kề

⟦folio 35⟧

Tế bào miễn phí. Do đó, các ô phải được sắp xếp thành “hàng” (Hình 2) và các “hàng” không được tiếp giáp nhau cũng như không giao nhau, vì trong cả hai trường hợp, hình ảnh hiển thị trong Hình 3 sẽ xuất hiện - cho đến khi chạm đến mép. Điều này có nghĩa là tất cả các “hàng” phải song song, điều này chỉ có thể thực hiện được khi $n$ chia hết cho 3. Trong trường hợp này, số ô là $n^2/3$ (ví dụ tương ứng được hiển thị trong Hình 4). Vì vậy, đối với bảng $n \times n$, trong đó $n=3k$, ước tính $\frac{n^2}{3}$ là chính xác.

S. Fomin

Không mất tính tổng quát, chúng ta có thể giả sử rằng $0 < a \leq b \leq c \leq d$. Cộng thêm ba bất đẳng thức
$$a(a-b)(a-c)(a+2d) \geq 0,$$
$$a(a-b)(a+2c)(a-d) \geq 0,$$
$$a(a+2b)(a-c)(a-d) \geq 0,$$
chúng tôi nhận được
$$3a^4 - 3a^2(bc + bd + cd) + 6abcd \geq 0,$$
hoặc
$$a^4 - a^2(bc + bd + cd) + 2abcd \geq 0.$$

Mặt khác, sự bất bình đẳng
$$b^4 + c^4 + d^4 - a^2(b^2 + c^2 + d^2 - bc - bd - cd) - b^2c^2 - b^2d^2 - c^2d^2 \geq 0$$
tương đương với tiếp theo
$$[(b+c)^2 - a^2](b-c)^2 + [(b+d)^2 - a^2](b-d)^2 + [(c+d)^2 - a^2](c-d)^2 \geq 0.$$

Cộng các bất đẳng thức (1) và (2), ta thu được mệnh đề bài toán.
Hãy đưa lời giải vào bài toán này và sử dụng phân tích toán học. Chúng ta cần ước lượng hình học sau đây
Bổ đề. Nếu hàm $f$ không âm tùy ý tại mỗi điểm của vòng lặp $[x_0; +\infty[$ thì nó không giảm trên vòng lặp này.
Lưu ý rằng nếu bất kỳ hai số $a, b, c, d$ nào trùng nhau thì chứng minh bất đẳng thức là đúng. Trên thực tế, chúng ta hãy chỉ đạo, $a = d$. thì bất đẳng thức của chúng ta có thể được viết lại như sau:
$$a^4 + 2(bc - b^2 - c^2)a^2 + b^4 + c^4 - b^2c^2 \geq 0.$$

Vế trái của bất đẳng thức (3) là tam thức bậc hai đối với $a^2$ với phân biệt không dương $-2bc(b-c)^2$, do đó (3) đúng.

Bây giờ chúng ta viết lại bất đẳng thức cần tìm dưới dạng này:
$$d^4 - (a^2 + b^2 + c^2)d^2 + 2abcd + a^4 + b^4 + c^4 - a^2b^2 - a^2c^2 - b^2c^2 \geq 0$$

và coi vế trái của (4) là hàm của $d$; Hãy biểu thị hàm này bằng $f$. Ta cần chứng minh rằng $f(d) \geq 0$ cho $d \geq c$ (và $0 < a \leq b \leq c$). Chúng tôi có:
$$f'(d) = 4d^3 - 2(a^2 + b^2 + c^2)d + 2abc,$$
vậy $f'(c) = 2c^3 - 2(a^2 + b^2)c + 2abc \geq 0 (0 < a \leq b \leq c)$.
Kế tiếp,
$$f''(d) = 12d^2 - 2(a^2 + b^2 + c^2) \geq 0$$

tại $0 < a \leq b \leq c$. Do đó, theo Bổ đề $f'(d) \geq f'(c) \geq 0$ cho $d \geq c$. Sử dụng thực tế là $f(c) \geq 0$ (xem nhận xét ở trên) và $f'(d) \geq 0$ cho $d \geq c$, và áp dụng lại bổ đề, chúng ta thu được bất đẳng thức $f(d) \geq 0$ cho $d \geq c$, đây chính là điều cần thiết.

Một khái quát hóa thú vị về bất đẳng thức này được phát minh bởi F. Schleöfer (Ryazan): với mọi $a_1, \dots, a_n$
$(n-1)(a_1^2 + a_2^2 + \dots + a_n^2) + n\sqrt{a_1^2 \cdot a_2^2 \cdot \dots \cdot a_n^2} \geq (a_1 + a_2 + \dots + a_n)^2$.

Đối với $n=4$, $a_1=a^2$, $a_2=b^2$, $a_3=c^2$, $a_4=d^2$, chúng tôi thu được tuyên bố về bài toán của mình.

V. Senderov, E. Turkevich

⟦folio 36⟧

M507. Giả sử $a_1 < a_2 < \dots < a_n < 2n$ là một dãy hữu hạn các số tự nhiên ($n \ge 6$).
a) Hãy chứng minh rằng
$$\min [a_i, a_j] \leq 6 \left( \left[ \frac{n}{2} \right] + 1 \right),$$
$[a_j, a_j]$ cũng có nghĩa là bội số chung nhỏ nhất của các số $a_i$ và $a_j$, và mức tối thiểu được lấy trên tất cả các tham số của các số $a_i, a_j$.
b) Hãy chứng minh rằng
$$\max (a_i, a_j) > \frac{38n}{147} - c,$$
khác $c$ không phụ thuộc vào $n$ và $(a_i, a_j)$ có ​​nghĩa là ước số chung nhỏ nhất của $a_i$ và $a_j$.
Không thể cải thiện các ước tính trong bài toán a) và b) (chúng ta có thể thay thế hệ số 6 bằng hệ số nhỏ hơn và $\frac{38}{147} - \text{большим}$).

Dưới đây chúng ta sẽ chứng minh một phát biểu tổng quát hơn. Hãy để $a_1 < a_2 < \dots < a_n \leq 2n$.
a) Hãy chứng minh rằng chúng ta yêu cầu bất đẳng thức đúng với $n \ge 5$. Giả sử trong số các phần tử của dãy $a_1, a_2, \dots, a_n$ có một số $a \leq n$. Nếu số 2a cũng thuộc dãy này thì
$$\min [a_i, a_j] \leq [a, 2a] = 2a \leq 2n \leq 6 \left( \left[ \frac{n}{2} \right] + 1 \right),$$
mang lại lời giải bài toán. Nếu 2a không thuộc dãy thì chúng ta xóa số $a$ khỏi chuỗi đó và thay thế bằng 2a. Rõ ràng là $\min [a_i, a_j]$ đối với chuỗi mới không kém gì chuỗi ban đầu. Áp dụng lý luận tương tự cho từng phần tử $a \leq n$, cuối cùng chúng ta sẽ đi đến chuỗi $n + 1, n + 2, \dots, 2n$ và
$$\min [a_i, a_j]$$ đối với chuỗi này không nhỏ hơn mức tối thiểu tương ứng đối với bất kỳ chuỗi nào khác mà từ đó nó thu được, đặc biệt là đối với chuỗi ban đầu.
Bây giờ chúng ta hãy chứng minh rằng với dãy $n + 1, n + 2, \dots, 2n$ tại $n \ge 5$ đẳng thức
$$n + 1 \leq a < b \leq 2n$$
Và
$$[a, b] = 6k + 6 = 6 \left( \left[ \frac{n}{2} \right] + 1 \right).$$

Bây giờ, hãy kiểm tra xem với bất kỳ cặp số $c, d$ nào thỏa mãn điều kiện $n + 1 \leq c < d \leq 2n$ thì bất đẳng thức $[c, d] \geq 6 \left( \left[ \frac{n}{2} \right] + 1 \right)$ đúng. Thật vậy, $[c, d] = pd = qc$, ở đâu $q > p > 1$. Trong trường hợp này, $p = 2$ và $q \ge 3$ hoặc $q \ge 4$. Trong trường hợp đầu tiên, $c$ là số chẵn, do đó $c \ge 2 \left( \left[ \frac{n}{2} \right] + 1 \right)$ và $[c, d] = qc \ge 3c \ge 6 \left( \left[ \frac{n}{2} \right] + 1 \right)$. Trong trường hợp thứ hai $[c, d] = qc \ge 4 (n + 1) \ge 6 \left( \left[ \frac{n}{2} \right] + 1 \right)$. Điều này hoàn thành việc chứng minh khẳng định a).

6) Hãy xem xét bài toán tổng quát hơn: đặt $a_1 < a_2 < \dots < a_k \leq B$ là một dãy số tự nhiên; Hãy thử ước tính cường độ của $max (a_i, a_j)$. Nghịch đảo bài toán rất hữu ích cho việc này: đặt $A, B$ là số dương (không nhất thiết phải là số nguyên); xác định $k$ tối đa mà tại đó có một dãy $k$ số tự nhiên riêng biệt $a_1, a_2, \dots, a_k$ tối đa sao cho
(1) phần tử nào của chuỗi không vượt quá $B$;
(2) $(a_i, a_j) \leq A$ cho bất kỳ phần tử riêng biệt nào $a_i, a_j$.
Chúng tôi sẽ biểu thị số lượng tối đa này bằng $k (A, B)$. Đối với lời giải bản gốc bài toán bạn cần chọn $A$ sao cho $k (A, 2n)$ gần bằng $n$. Thật vậy, nếu với mỗi $A$
$$k (A, 2n) < n,$$
thì với bất kỳ chuỗi nào $a_1 < a_2 < \dots < a_n \leq 2n$ sẽ có
$$max (a_i, a_j) > A;$$
nếu $k (A, 2n) \ge n$ thì tồn tại một dãy $a_1 < a_2 < \dots < a_n \leq 2n$ sao cho
$$max (a_i, a_j) \leq A.$$
Đặt $a_1, \dots, a_k$ là dãy thỏa mãn điều kiện (1) và (2). Nếu phần tử $a_i$ nào đó của dãy này có ước số $d > A$ không giống với $a_i$ thì theo điều kiện (2) $d$ không phải là một phần tử của dãy. Sau đó, thay thế

⟦folio 37⟧

$a_i$ bằng $d$, chúng ta thu được một chuỗi mới có cùng độ dài, cũng thỏa mãn điều kiện (1) và (2). Tiến hành theo cách tương tự, cuối cùng chúng ta sẽ thu được một chuỗi trong đó không có phần tử nào có ước số riêng lớn hơn $A$. Chúng tôi gọi một chuỗi như vậy là không thể rút gọn.

Bây giờ chúng ta hãy xem xét tập hợp $M$ của tất cả các số tự nhiên không vượt quá $B$ và không có ước số thực sự lớn hơn $A$. M là một dãy bất khả quy thỏa mãn các điều kiện (1) và (2), và mọi dãy bất khả quy khác đều chứa trong $M$. Do đó, rõ ràng là $k(A, B)$ đơn giản bằng số phần tử $M$.

Để đếm số phần tử của tập hợp $M$, chúng ta tính riêng số lượng 4 phần tử, số phần tử lẻ chia hết cho 3, v.v. Chính xác hơn là đặt $M_2$ gồm cả 4 phần tử của tập hợp $M$, $M_3$ gồm cả 4 phần tử của $M$ chia hết cho 3, $M_5$ gồm cả 4 phần tử $M$, chia hết cho 5, nhưng không chia hết cho 2 hoặc 3. Và nói chung, đối với bất kỳ số nguyên tố $p$ nào, tập hợp $M_p$ bao gồm các phần tử của tập hợp $M$ chia hết cho $p$ và không có thừa số nguyên tố nào nhỏ hơn $p$.

Hãy đếm số phần tử của tập hợp $M_p$. Bất kỳ phần tử nào từ $M_p$ đều có dạng $pc$, trong đó $c \leqslant A$ (vì $M$ là tập tối giản), $pc \leqslant B$ và $c$ không có thừa số nguyên tố nào nhỏ hơn $p$. Nếu $pA \leqslant B$ thì có thể bỏ qua điều kiện $pc \leqslant B$ và số phần tử $M_p$ bằng số phần tử tự nhiên $c \leqslant A$ không có thừa số nguyên tố nhỏ hơn $p$ (chúng ta sẽ biểu thị số đó bằng $m_p(A)$). Nếu $pA > B$ thì số phần tử $M_p$ bằng $m_p\left(\frac{B}{p}\right)$ và không vượt quá $m_p(A)$.

Hãy để chúng tôi sửa một số nguyên tố $p$. Nói chung, các bộ $M_2, M_3, M_5, \dots, M_p$ không làm cạn kiệt các bộ $M$. Chúng ta hãy biểu thị bằng $N$ tập hợp tất cả các phần tử còn lại của $M$. Chúng không có ước số giữa các số 2, 3, 5, ..., $p$ nên số của chúng không vượt quá số $m_q(B)$, trong đó $q$ là số nguyên tố tiếp theo sau $p$. Như vậy,

$$k(A, B) \leqslant m_2(A) + m_3(A) + \dots + m_p(A) + m_q(B).$$

Nếu $pA \leqslant B < qA$, thì bất đẳng thức này chuyển thành đẳng thức. Thật vậy, rõ ràng là mỗi $M_r$ chứa chính xác $m_r(A)$ phần tử. Mặt khác, mọi số $c \leqslant B$, không có ước số nhỏ hơn $q$, do đó không có ước số nào lớn hơn $A$ (nếu $c = df$, trong đó $d > A$ và $c \leqslant B < qA$, thì $f < q$), và do đó được bao gồm trong $N$; do đó $N$ chứa phần tử $m_q(B)$.

Bây giờ chúng ta hãy bắt đầu ước tính các số có dạng $m_r(C)$. Thứ nhất, $m_2(C)$ bằng số tự nhiên $l \leqslant C$, nghĩa là bằng $[C]$ và khác $C$ nhỏ hơn 1. Tiếp theo, $m_3(C) = m_2(C) - m_2\left(\frac{C}{2}\right)$ (số tất cả $l \leqslant C$ nhỏ hơn 1, thì $m_3(C)$ khác với $C$ $\left(1 - \frac{1}{2}\right)$ bởi ít hơn 2).

Lập luận theo cách tương tự, chúng ta nhận được rằng nếu $p$ và $q(p < q)$ là hai số nguyên tố lân cận thì $m_q(C) = m_p(C) - m_p\left(\frac{C}{p}\right)$, từ đó cho thấy $m_q(C)$ khác với số $C\left(1 - \frac{1}{2}\right)\left(1 - \frac{1}{3}\right) \dots \dots \left(1 - \frac{1}{p}\right)$ nhỏ hơn $2^{i-1}$, trong đó $i$ là số của số nguyên tố $q$. Nói cách khác, biểu thị bằng $Z_q$ tích của tất cả các số có dạng

⟦folio 38⟧

$$\left(1 - \frac{1}{r}\right),$$
trong đó $r$ là số nguyên tố nhỏ hơn $q$ (và đặt $Z_2 = 1$), ta có

$$|m_q(C) - C \cdot Z_q| < 2^{i-1}$$

($i$ là số của số nguyên tố $q$). Do đó, các ước tính sau đây đúng với số $k(A, B)$:

$$k(A, B) \leq m_2(A) + \ldots + m_p(A) + m_q(B) < A(Z_2 + Z_3 + \ldots + Z_p) + B \cdot Z_q + 1 + 2 + \ldots + 2^{i-1} = A(Z_2 + \ldots + Z_p) + B \cdot Z_q + (2^i - 1);$$

nếu $pA \leq B \leq qA$ thì

$$k(A, B) = m_2(A) + \ldots + m_p(A) + m_q(B) > A(Z_2 + \ldots + Z_p) + B \cdot Z_q - (2^i - 1).$$

(3)

Bây giờ chúng ta hãy quay lại bài toán ban đầu và tìm hiểu xem $A$ $k(A, 2n) < n$ là gì. Để làm được điều này, chỉ cần giải $A$ bất đẳng thức

$$A(1 + Z_3 + \ldots + Z_p) + 2n \cdot Z_q + (2^i - 1) \leq n.$$

Lấy $p$ bằng 3,5 hoặc 7, ta được tương ứng:

$$A \leq \frac{2}{9}n - \frac{14}{3}, \quad A \leq \frac{14}{55}n - \frac{90}{11},$$

$$A \leq \frac{38}{147}n - \frac{310}{21}.$$

Tại $p = 7$ có hệ số nhỏ $\frac{38}{147}$, hệ số lớn nhất trong ba hệ số. Lấy $p \geq 11$ là vô nghĩa, vì $11 \cdot \frac{38}{147}n \geq 2n$, và các bất đẳng thức cho $k(A, 2n)$ sẽ kém chính xác hơn. Vì vậy, chúng tôi đã chứng minh rằng với $n \geq 2$ cho bất kỳ chuỗi nào $a_1 < a_2 < \ldots < a_n \leq 2n$

$$\max(a_i, a_j) > \frac{38}{147}n - \frac{310}{21}.$$

Để chứng minh hệ số $\frac{38}{147}$ không thể bị thay đổi, ta lấy $A = \frac{38}{147}n + \frac{310}{21}$. Khi đó tại $n \geq 543$ sẽ có $7A \leq 2n < 11A$, và sử dụng bất đẳng thức (3), chúng ta thu được $k(A, 2n) \geq n$. Do đó, với $n \geq 543$ luôn có một dãy $a_1 < a_2 < \ldots < a_n \leq 2n$ mà

$$\max(a_i, a_j) \leq \frac{38}{147}n + \frac{310}{21}.$$

Nếu ước tính $m_r(C)$ một cách cẩn thận, chúng ta có thể thu được các bất đẳng thức chính xác hơn: với $n \geq 2$ cho bất kỳ chuỗi nào $a_1 < a_2 < \ldots < a_n \leq 2n$

$$\max(a_i, a_j) \geq \frac{38}{147}n - \frac{73}{49};$$

và ngoài ra còn có một dãy $a_1 < a_2 < \ldots < a_n \leq 2n$ mà

$$\max(a_i, a_j) \leq \frac{38}{147}n + \frac{73}{49}.$$

(điều đáng chú ý là hằng số $\frac{73}{49}$ trong các bất đẳng thức này không thể giảm được nữa).

D. Bernishtein

⟦folio 39⟧

F513. Vào một ngày nắng đẹp, khi Mặt trời ở đường chân trời, hãy lên một màn hình nhẵn, ở bên phải, trên bức tường trắng, vuốt thẳng các mép của một miếng bìa cứng. Nếu đồng hồ được đưa đến tấm bìa cứng bằng một ngón tay, như trong Hình 5, thì trên màn hình, tôi sẽ chỉ ngón tay ra khỏi tấm bìa cứng và lau khô ngón tay thứ hai. Hãy thực hiện thí nghiệm này và giải thích kết quả của nó.

Không thể sử dụng khái niệm nhiễu xạ để mô tả hiện tượng này vì kích thước của vân nhiễu xạ ở những khoảng cách như vậy là nhỏ.

Lời giải bài toán chỉ dành cho người lớn khi chúng ta tính đến việc Mặt trời không phải là nguồn ánh sáng chính xác mà có kích thước góc hữu hạn.

Để hiểu bóng sắp tới xuất hiện như thế nào, hãy tham khảo Hình 6.

Vì Mặt trời, với tư cách là nguồn sáng, có một số kích thước góc (khoảng nửa độ), nên bóng của tất cả các vật thể trong một ngày nắng đều được đặt. Kích thước của cạnh của bóng phụ thuộc vào khoảng cách từ vật thể đến bề mặt nơi quan sát thấy bóng. Mặc dù trong thí nghiệm trên, có vẻ như rìa bóng của một vật thể được xác định rõ ràng, nhưng thực tế không phải vậy. Ngoài vùng bóng đầy đủ, còn có vùng bóng một phần. Khi một ngón tay đến gần một vật thể, chặn một phần tia rơi vào vùng nửa tối, một bóng đang tới sẽ xuất hiện trên màn hình. Sự hợp nhất của bóng và bóng đối diện với chuyển động đi xuống tiếp theo của ngón tay xảy ra ở viền của vùng nửa tối và phần được chiếu sáng của màn hình.

Bằng cách đo khoảng cách giữa vật thể và màn hình, giữa ngón tay và vật thể, cũng như kích thước của bóng tới phía trước bóng trực tiếp, chúng ta có thể ước tính kích thước góc của Mặt trời dựa trên những cân nhắc hình học đơn giản.

G. Solovyanok

Hình 5.

F516. Một đĩa nặng bán kính R lăn trên hai sợi dây không dãn quấn quanh nó. Các đầu tự do của sợi chỉ được cố định (Hình 7). Các luồng liên tục được tham gia khi đĩa di chuyển. Tại một số thời điểm, tốc độ của đĩa là $\omega$ và tốc độ giữa các luồng là $\alpha$. Tốc độ của tâm đĩa lúc này là bao nhiêu?

Chúng ta hãy xem xét chuyển động của các điểm $c$ và $d$, tại đó chúng chạm vào đĩa, trong một hệ tọa độ có gốc trùng với điểm $O$, trong đó tâm của đĩa nằm, khi góc giữa các ren là $\alpha$ và các trục $OX$ và $OY$ tạo một góc $\alpha$ với nhau và song song với các ren (Hình 7). Trong hệ tọa độ này (như trong bất kỳ hệ tọa độ cố định nào), vận tốc của điểm $c$ và $d$ lần lượt bằng nhau

$$v_c = v_0 + v_{c0}, \quad v_d = v_0 + v_{d0}.$$

trong đó $v_0$ là tốc độ của tâm đĩa, $v_{c0}$ và $v_{d0}$ là vận tốc của các điểm $c$ và $d$ so với tâm của đĩa. Rõ ràng là $|v_{c0}| = |v_{d0}|$, và ở tốc độ góc quay của đĩa $\omega$

$$|v_{c0}| = |v_{d0}| = \omega R = u.$$

Từ điều kiện không giãn của các sợi dây, suy ra rằng, khi chúng tạo thành một góc $\alpha$, các hình chiếu $v_{dx}$ và $v_{cy}$ của vận tốc $v_d$ và $v_c$ trên trục $OX$ và $OY$ bằng 0:

$$v_{dx} = v_{0x} - u = 0, \quad v_{cy} = v_{0y} - u = 0.$$

Từ đây

$$v_{0x} = v_{0y} = u.$$

Điều này có nghĩa là vectơ $v_0$ của tốc độ tâm đĩa có hướng
