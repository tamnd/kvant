---
id: 2025-3-kohas-podkoryitov-predel-sinusa-7b52448d
issue: kvant_2025_3
year: 2025
number: "3"
title: Giới hạn sin
authors:
  - Кохась К. П.
  - Подкорытов А.
rubric: osnovnye-stati
page_first: 13
page_last: 19
page_labels: 13, 15, 17
lang: vi
source: kvant_digital
extraction: vision
content_sha256: 781b7340e1a43f108570749878237b9a168dead66b58306a2839004e240d92cf
prompt_sha256: draft-1
translated_from: content/ru/2025/03/articles/03_kohas-podkoryitov-predel-sinusa-7b52448d.md
source_content_sha256: 841ab2510a0f9cee0498826b54f0463507765bcdf1ecc265e9350b0969bed0d4
translation_model: draft
translation_run: vi-draft-gaps-2026-11-03
translation_quality: draft
---

⟦folio none⟧

---
running_head:
folio:
---

K.KOKHAS, A.PODKORYTOV

CHÚNG TÔI TIN TƯỞNG VÀO SỰ BIẾT
người đọc cảm thấy thoải mái với con số $\pi$ và với
khái niệm giới hạn của dãy số.
Chúng tôi quan tâm đến câu hỏi: liệu có một
một số giới hạn $x > 0$ $\lim_{n \to +\infty} \sin(x^n)$?
Chúng tôi tin chắc rằng độc giả sẽ nói ngay điều gì
giới hạn này bằng nếu $x \in (0;1]$. Chúng tôi là
Hãy cùng thảo luận về trường hợp $x > 1$ tại đây.

Hãy bắt đầu với một điều tốt, nổi tiếng và đơn giản
cốt truyện mới.

Câu 1. Trình tự có
$\{\sin n\}$ giới hạn ở $n \to +\infty$?

Đáp số không đồng tính - không có. Nhưng bằng chứng là
bằng chứng về thực tế này không hoàn toàn rõ ràng
dễ thấy. Hãy tìm ra nó.

Định lý 1. Dãy số $\{\sin n\}$
không có giới hạn.

Bằng chứng. Chúng ta sẽ chỉ dựa vào định nghĩa của sin và định nghĩa
giới hạn. Chúng ta hãy dựng một đường tròn bán kính đơn vị trên mặt phẳng tọa độ với
tập trung tại điểm gốc và đánh dấu trên
đó là điểm $S$ có tọa độ $(1;0)$. Hãy để $\varphi$ –
góc dương tùy ý (đối với
trường hợp chính của chúng tôi: $\varphi = 1, 2, 3, \dots$).
Hãy vẽ dọc theo đường tròn ngược chiều kim đồng hồ
$y$
$2$
$\sin 1$
$3$
$\sin 3$
$\cos 1$
$6$
$\sin 4$
$5$

Hình 1. Định nghĩa sin và cos
mũi tên hú của cung $ST$ có chiều dài $\varphi$ (hình 1), vì vậy
rằng tọa độ của điểm $T$ là $(\sin \varphi, \cos \varphi)$.

DOI: https://doi.org/10.4213/kvant20250302

Các điểm của đường tròn được xác định một cách tự nhiên
sử dụng cùng tọa độ $\varphi$, $\varphi \in [0;2\pi]$. Hãy chia vòng tròn của chúng ta thành ba phần
(hình 2): Bắc Cực $\frac{\pi}{4} \leq \varphi \leq \frac{3\pi}{4}$, Nam Cực $\frac{5\pi}{4} \leq \varphi \leq \frac{7\pi}{4}$ và Vùng nhiệt đới (phần này của vùng xung quanh
ity, bao gồm hai cái khác). Lưu ý rằng
độ dài của các cung phổ biến - Bắc Cực và
Nam Cực – bằng $\frac{\pi}{2}$. Vì mục đích của chúng tôi
Điều quan trọng là chúng lớn hơn 1.

Chúng ta sẽ dựng các cung có độ dài trên một đường tròn
chúng ta là 1, 2, 3,…, đặt chúng ra xa điểm $S$,
và điểm cuối của các cung này sẽ được chỉ định bởi cùng một
số tự nhiên (xem hình 1). Uwe-
bằng cách xác định vị trí $n$, chúng ta di chuyển từ điểm $n$ đến
điểm $n + 1$, di chuyển dọc theo đường tròn
ngược chiều kim đồng hồ 1. Thực hiện
những bước như vậy, chúng tôi sẽ thực hiện nhiều hơn nữa
và những vòng quay mới quanh tâm vòng tròn,
và trên mỗi cuộc cách mạng ít nhất một
một điểm nguyên sẽ rơi trên cung Bắc Cực và ít nhất một điểm nguyên sẽ rơi trên cung Nam Cực.
Đối với những điểm như vậy, giá trị tội lỗi $n$ hoặc lớn hơn
lớn hơn $\sin \frac{\pi}{4} = \frac{\sqrt{2}}{2} \approx 0,7$ hoặc nhỏ hơn $-\frac{\sqrt{2}}{2}$.

Bây giờ thật dễ dàng để xác minh rằng trình tự
hoạt động với thuộc tính như vậy không thể
có một giới hạn. Thật vậy, hãy nói

⟦folio 13⟧

---
running_head:
folio:
---

chứa phần này, sau đó chúng ta quan tâm đến phần nào của cuộc cách mạng cuối cùng, chưa hoàn chỉnh, được thực hiện vào cuối phần này. Những hành động này hoàn toàn giống với thao tác chia có số dư, chỉ khác là chúng ta chia cho một số không nguyên (và số không nguyên - cho $2\pi$). Khi thực hiện những hành động này, chúng ta sẽ sử dụng ký hiệu lý thuyết số, ví dụ: $(6 \mod 2\pi) \approx -0,28$, $(132 \mod 2\pi) \approx 0,0531$, v.v.

Do đó, dãy các điểm $\{n\}$ dày đặc khắp nơi trên đường tròn đơn vị, dãy $\{n \mod 2\pi\}$ dày đặc khắp mọi nơi trên khoảng $[0;2\pi]$, và dãy $\{\sin n\}$ dày đặc khắp mọi nơi trên khoảng $[-1;1]$.

Chúng tôi mời người đọc tự kiểm tra và giải thích lý do tại sao các chuỗi $\{\sin \sqrt{n}\}, \{\sin \left(n + \frac{1}{n}\right)\}, \{\sin \ln n\}$ không có giới hạn.

Bây giờ chúng ta hãy thực hiện một nhiệm vụ phức tạp hơn và giảm đáng kể chuỗi tất cả các số.

Câu 2: Dãy số $\{\sin \left(n^2\right)\}$ có giới hạn không?

Đáp số lại âm tính. Đầu tiên, chúng ta sẽ xác minh điều này một cách “thủ công”, theo ý tưởng tương tự như trong chứng minh Định lý 1. Sau đó (xem Định lý 4 và hệ quả của nó) việc thu được các kết quả kiểu này sẽ được tự động hóa.

Định lý 2. Dãy số $\{\sin \left(n^2\right)\}$ không có giới hạn.

Bằng chứng. Chúng tôi sẽ theo dõi vị trí của các điểm $n^2$ trên đường tròn hoặc, nếu là góc, các điểm $x_n = n^2 \mod 2\pi$. Từ

$$\left(n + 1\right)^2 = n^2 + 2n + 1,$$
$$\left(n + 2\right)^2 = \left(n + 1\right)^2 + 2n + 3,$$

điểm $x_{n+1}$ thu được bằng cách xoay điểm $x_n$ theo góc $\varphi = (2n + 1) \mod 2\pi$ và điểm $x_{n+2}$ thu được bằng cách xoay điểm $x_{n+1}$ theo góc $\varphi + 2 = (2n + 3) \mod 2\pi$. Bằng cách sử dụng Quan sát, chúng ta luôn có thể tìm thấy số $n$ có góc lớn đến mức nào, trong đó số $2n + 1$ nằm trên cung $2\left[\frac{\pi}{6}; \frac{\pi}{3}\right]$

Hình 4. Chọn $n$. Dây màu đỏ bao bọc một cung có độ lớn $\varphi = (2n + 1) \mod 2\pi$, dây màu xanh lam – một cung có độ lớn $\varphi + 2 = (2n + 3) \mod 2\pi$ của đường tròn của chúng ta (hình 4). Khi đó, điểm $x_{n+1}$ thu được bằng cách xoay điểm $x_n$ theo góc $\varphi \in \left[\frac{\pi}{6}; \frac{\pi}{3}\right]$ và $x_{n+2}$ thu được bằng cách xoay $x_{n+1}$ theo góc $\varphi + 2 \in \left[\frac{\pi}{6} + 2; \frac{\pi}{3} + 2\right] \approx \left[\frac{5}{2}; 3\right]$. Nếu bây giờ chúng ta đi dọc theo đường tròn ngược chiều kim đồng hồ từ điểm $x_{n+2}$ tới điểm $x_n$ thì chúng ta sẽ phải vẽ các cung có chiều dài không nhỏ hơn $2\pi - \varphi - (\varphi + 2) > 2\pi - \frac{\pi}{3} - \left(\frac{\pi}{3} + 2\right) > 2$ (tại hình 5 cung này được đánh dấu màu xanh lá cây).

Hình 5. Tam giác $x_n x_{n+1} x_{n+2}$ luôn rộng vì các cạnh của nó chịu các cung có chiều dài không nhỏ hơn $\pi/6$.

Ngược lại, chúng ta giả sử rằng giới hạn $\lim_{n \to +\infty} \sin \left(n^2\right)$ tồn tại và bằng $l$. Hãy sử dụng định nghĩa của giới hạn: với $\varepsilon = \frac{1}{10}$ tồn tại một số $N$,

$^2$ Một câu đố nhỏ dành cho người đọc. Chúng ta đã học cách tìm một điểm trên cung đã cho tương ứng với một số chia hết cho 6. Nhưng làm thế nào để tìm một điểm tương ứng với một số lẻ?

⟦folio none⟧

---
running_head:
folio:
---

Hình 6. Sin nằm lân cận điểm $a$. Các đường chấm ngang được vẽ ở độ cao $a \pm 1/10$

bắt đầu từ đó, tức là với $n > N$, bất đẳng thức $\left| \sin \left( n^2 \right) - l \right| < \frac{1}{10}$ đúng. Nói một cách đơn giản, đối với tất cả $n$ lớn, các số $x_n = n^2$, $x_{n+1} = (n+1)^2$ và $x_{n+2} = (n+2)^2$ phải ở đâu đó trên các cánh tay nhìn thấy được (hình 6). Nhưng đối với những giá trị của $n$ mà chúng ta đã thảo luận liên quan đến hình 5, điều này là không thể, vì tam giác $x_n x_{n+1} x_{n+2}$ không thể thực sự hẹp. Sự mâu thuẫn. Định lý đã được chứng minh.

Không có gì lạ khi một dãy không có giới hạn nhưng hoạt động khá đơn giản. Đặc biệt, điều này sẽ xảy ra nếu nó được “dán lại với nhau” từ nhiều chuỗi có giới hạn khác nhau. Ví dụ: $x_n = (-1)^n$. Đối với dãy này $\lim_{k \to +\infty} x_{2k} = 1$ nếu chúng ta chỉ xem xét số chẵn $n$ và $\lim_{k \to +\infty} x_{2k+1} = -1$ nếu chúng ta chỉ xem xét số lẻ $n$. Trong trường hợp tổng quát, ta chấp nhận định nghĩa này.

Điều hành. Cho dãy $\{x_n\}$. Chúng ta hãy chọn khả năng của một dãy số tự nhiên $n_1 < n_2 < n_3 < \ldots$ và xem xét các thành viên của dãy với các số đã chọn:

$$x_{n_1}, x_{n_2}, x_{n_3}, \ldots$$

Chúng ta nhận được một dãy con của dãy $x_n$. Nó có thể được coi là một chuỗi độc lập trong đó số hạng đầu tiên bằng $x_{n_1}$, số hạng thứ hai bằng $x_{n_2}$, v.v. Chuỗi mới này được chỉ định như sau: $\{x_n\}$. Nếu nó có giới hạn $\lim_{k \to +\infty} x_n = l$ thì số $l$ được gọi là giới hạn từng phần của dãy $x_n$.

Không khó để thấy rằng nếu một dãy $\{x_n\}$ có một tập hữu hạn các giới hạn từng phần $L = \{l_1, l_2, \ldots, l_m\}$, thì nó có đặc tính là nó tuân theo một giới hạn nhất định. Cụ thể, với bất kỳ $\varepsilon > 0$ nào cũng có một số $N$ sao cho với mỗi $n > N$ ít nhất một trong các bất đẳng thức đúng:

$$|x_n - l_1| < \varepsilon, \ldots, |x_n - l_m| < \varepsilon$$

(đối với $\varepsilon$ nhỏ chỉ một trong số chúng được thỏa mãn).

Bất kỳ chuỗi nào cũng có thể được chia thành $m$ chuỗi con, mỗi chuỗi có xu hướng giới hạn riêng. Nói cách khác, các số hạng của dãy như vậy có thể được viết dưới dạng

$$x_n = \varphi_n + \varepsilon_n, \text{ где } \varphi_n \in L, \varepsilon_n \rightarrow 0.$$

Sự tồn tại của giới hạn chuỗi là một thuộc tính rất mạnh. Một dãy thực tùy ý, thậm chí là một dãy hữu hạn, không nhất thiết phải có giới hạn. Hơn nữa, nó đáng để thay thế vì, theo định lý Bolzano-Weierstrass, đã được chứng minh trong một quá trình phân tích toán học tiêu chuẩn, mọi chuỗi thực bị chặn đều có ít nhất một giới hạn từng phần. Mặt khác, tập hợp các giới hạn thực hiện từng phần có thể là vô hạn. Ví dụ, người đọc có thể chứng minh định lý sau.

**Định lý 3.** Nếu $A$ và $B$ là số thực $u$ thì quan hệ $\frac{A}{\pi}$ là vô tỷ, thì dãy $\{\sin (An + B)\}$ là Lomp ở mọi nơi trên khoảng $[-1;1]$.

Cụ thể, bất kỳ số nào trong khoảng $[-1;1]$ đều là giới hạn một phần của chuỗi $\{\sin n\}$.

Nhân tiện, xin lưu ý rằng khi nghiên cứu các giới hạn từng phần của một dãy có dạng $\{\sin x_n\}$, sự hiện diện của sin trong công thức không quan trọng lắm, toàn bộ vấn đề nằm ở các tính chất của dãy $\{x_n \mod 2\pi\}$.

⟦folio 15⟧

---
running_head:
folio:
---

Mỗi giới hạn từng phần $l$ của chuỗi $\{\sin x_n\}$ tương ứng với một hoặc hai giới hạn từng phần của chuỗi $\{x_n \mod 2\pi\}$: đây là arcsin $l$ và $\pi - \arcsin l$ (giới hạn từng phần có thể là cả hai số này hoặc chỉ một). Do đó, nếu chúng ta hiểu hành vi của dãy $\{x_n \mod 2\pi\}$, thì bằng cách nào đó chúng ta sẽ có thể chuyển sang hàm sin.

Hãy đưa ra một ví dụ khác về việc sử dụng giới hạn từng phần.

**Định lý 4. Giả sử $p(x) = \alpha x^k + \beta x^{k-1} + \dots$ là nhiều năm có hệ số cao nhất $\alpha$ vô số với số $\pi$ (tỷ lệ $\frac{\alpha}{\pi}$ là vô tỷ). Khi đó dãy $\{p(n) \mod 2\pi\}$ có vô số giới hạn từng phần.

**Chứng minh.** Giả sử ngược lại, dãy $\{p(n) \mod 2\pi\}$ chỉ có hữu hạn các giới hạn riêng phần, ta ký hiệu nó là $m$, $m \in \mathbb{N}$. Khi đó, chuỗi $\{\tilde{p}(n) \mod 2\pi\}$, trong đó $\tilde{p}(x) = p(x) - p(x-1)$, có nhiều nhất $m^2$ giới hạn từng phần (chúng ta chỉ quan tâm rằng số của chúng là hữu hạn). Hơn nữa, đa thức $\tilde{p}(x)$ có bậc 1 nhỏ hơn $p(x)$ và hệ số dẫn đầu của nó vẫn vô lượng với $\pi$. Lặp lại lập luận này nhiều lần, chúng ta đi đến chuỗi $\{An + B \mod 2\pi\}$, chỉ có một số hữu hạn các giới hạn từng phần, mặc dù phân số $\frac{A}{\pi}$ là vô tỷ. Nhưng, như chúng ta biết từ Định lý 3, điều này là không thể. Định lý đã được chứng minh.

**Hệ quả tất yếu.** Đối với mọi đa thức neopostorio $p(n)$ có hệ số dãy số nguyên $\{p(n) \mod 2\pi\}$ và $\{\sin p(n)\}$ thì có vô số giới hạn từng phần.

**Câu hỏi 3.** Với $x > 1$ dãy $\{\sin(x^n)\}$ nào có giới hạn?

Than ôi, chúng tôi sẽ không thể trả lời câu hỏi này; chúng tôi sẽ chỉ chia sẻ một số tin nhắn. Bước đầu tiên, chúng ta hãy loại bỏ sin một lần nữa và xem xét chuỗi $\{x^n \mod 2\pi\}$.

Năm 1935, Yu. Koksa đã chứng minh (xem [2]) rằng với hầu hết tất cả $x > 1$, chuỗi $\{x^n \mod 2\pi\}$ luôn dày đặc trên $[0; 2\pi]$.

Do đó $x^n$ các điểm của khoảng này gần nhau vô số lần. Những từ “gần như tất cả” là một thuật ngữ; Không đi sâu vào ý nghĩa của nó, giả sử rằng kết quả của Coxa không loại trừ sự tồn tại của $x$ mà dãy $\{x^n \mod 2\pi\}$ vẫn có giới hạn (nhưng $x$ như vậy rất hiếm).

Tuy nhiên, chúng ta hãy chứng minh rằng đối với $x > 1$ hợp lý thì chuỗi $\{x^n \mod 2\pi\}$ và với nó $\{\sin(x^n)\}$ là không có giới hạn. Điều này chứng minh định lý sau [1, bài toán I.3.8 d].

**Định lý 5. Với mọi hữu tỉ $Q > 1$ tập giới hạn từng phần của dãy $\{Q^n \mod 2\pi\}$ là vô hạn.

**Chứng minh.** Lập luận bằng phản chứng, chúng ta giả sử rằng tập các giới hạn riêng phần của dãy $\{Q^n \mod 2\pi\}$ là hữu hạn. Sau đó

$$Q^n = 2\pi k_n + \varphi_n + \varepsilon_n,$$

(1)

trong đó $k_n \in \mathbb{N}$, $\varepsilon_n \rightarrow 0$ và $\varphi_n$ là một trong các giới hạn từng phần của chuỗi $\{Q^n \mod 2\pi\}$. Từ

$$Q^{n+1} = 2\pi k_{n+1} + \varphi_{n+1} + \varepsilon_{n+1},$$

rõ ràng là thế

$$0 = 2\pi(Qk_n - k_{n+1}) + (Q\varphi_n - \varphi_{n+1}) + (Q\varepsilon_n - \varepsilon_{n+1}).$$

Sau khi viết số $Q$ dưới dạng phân số $Q = \frac{p}{q}$, trong đó $p, q \in \mathbb{N}$, $p > q$, chúng ta thu được tất cả $n$ các đẳng thức

$$0 = 2\pi(pk_n - qk_{n+1}) + (p\varphi_n - q\varphi_{n+1}) + (p\varepsilon_n - q\varepsilon_{n+1}).$$

Để ngắn gọn, chúng ta hãy ký hiệu các biểu thức trong ngoặc: đặt $K_n = pk_n - qk_{n+1}$ là một số nguyên nhất định, $\psi_n = p\varphi_n - q\varphi_{n+1}$ một đại lượng chỉ lấy một số hữu hạn các giá trị và cuối cùng, đặt $\delta_n = p\varepsilon_n - q\varepsilon_{n+1}$. Rõ ràng là $\delta_n \rightarrow 0$ tại $n \rightarrow +\infty$. Trong ký hiệu này, các đẳng thức cuối cùng được viết dưới dạng

$$0 = 2\pi K_n + \psi_n + \delta_n \quad (n \in \mathbb{N}).$$

⟦folio 17⟧

---
running_head:
folio:
---

(chúng tôi sẽ sử dụng thêm bộ ba được sử dụng ở đây khi ước tính mức độ chênh lệch). Theo định nghĩa, khoảng $[a^2; b^2]$ chứa một khoảng có dạng $[2\pi m_1 + p; 2\pi m_1 + q]$, trong đó $m_1 \in \mathbb{N}$. Đặt $[a_1; b_1] \subset [a; b]$ là một khoảng sao cho
$$a_1^2 = 2\pi m_1 + p \text{ и } b_1^2 = 2\pi m_1 + q.$$
Rõ ràng là $(y^2 \bmod 2\pi) \in [p; q]$ dành cho tất cả $y \in [a_1; b_1]$. Từ bất đẳng thức (4), suy ra độ dài của khoảng $[a_1^3; b_1^3]$ không nhỏ hơn $2\pi$:
$$b_1^3 - a_1^3 \geq a_1 \left(b_1^2 - a_1^2\right) = a_1 (q - p) \geq 2\pi.$$
Điều này có nghĩa là đối với một số $m_2 \in \mathbb{N}$ khoảng $[a_1^3; b_1^3]$ chứa một khoảng có dạng $[2\pi m_2 + p; 2\pi m_2 + q]$. Đặt $[a_2; b_2] \subset [a_1; b_1]$ là một khoảng sao cho
$$a_2^3 = 2\pi m_2 + p, \quad b_2^3 = 2\pi m_2 + q.$$
Rõ ràng là $(y^3 \bmod 2\pi) \in [p; q]$ dành cho tất cả $y \in [a_2; b_2]$. Do bất đẳng thức (2) nên độ dài của khoảng $[a_2^4; b_2^4]$ không nhỏ hơn $2\pi$:
$$b_2^4 - a_2^4 \geq a_2 \left(b_2^3 - a_2^3\right) \geq \geq a_2 (q - p) \geq a (q - p) \geq 2\pi.$$
Tiếp tục xây dựng bằng quy nạp, ta thu được dãy các khoảng dương $\{[a_k; b_k]\}$. Điểm yêu cầu được lấy từ giao điểm của họ. Định lý đã được chứng minh.
Định lý này thật đáng thất vọng, tôi sẽ nói thế nào đây, vì nó không mang tính xây dựng. Số lượng yêu cầu tồn tại nhưng được đưa ra bởi một cấu trúc phức tạp. Hãy thử trình bày nó!
Hãy thử. Nhưng chúng ta vẫn cần làm suy yếu bài toán – hãy loại bỏ số $\pi$. Chia cho $2\pi$ với số dư vẫn là một phép toán kỳ lạ. Dễ dàng thực hiện hơn nhiều với phần còn lại của... 1! Vâng, vâng, đây là một hoạt động nổi tiếng $\deltaробная чась числа$. Để đề cập đến trường hợp của các phân đoạn khác, chúng tôi xem xét một câu hỏi tổng quát hơn - về hành vi của chuỗi $\{ \xi x^n \bmod 1 \}$ với hệ số cố định $\xi$. Ví dụ: nếu bạn đã học được điều gì đó về cùng một chuỗi tại $\xi = \frac{1}{2\pi}$ thì bạn sẽ ngay lập tức dự đoán kết quả tương tự cho chuỗi $\{ x^n \bmod 2\pi \}$. Nhưng chúng ta sẽ không đi theo hướng này, mà đi khắp nơi $\xi = 1$.

Hãy để chúng tôi trình bày số $R$ mà một phần chuỗi trước đó $\{ R^n \bmod 1 \}$ lấp đầy toàn bộ phân đoạn [0;1]. Đây sẽ vừa là minh họa cho Định lý 6 (chính xác hơn là tương tự của nó cho $\xi = 1$ và chỉ cho khoảng $[p; q] = [0; 1]$) vừa là kết quả của Kokstma. Và bản thân ví dụ này cũng có trong tác phẩm [3] của T. Vidyaraghavan năm 1941.

**Định lý 7. Cho $R$ là nghiệm dương lớn nhất của đa thức**

$$P(x) = x^4 - x^3 - x^2 - x + 1.$$
Sau đó, chuỗi $\{ R^n \bmod 1 \}$ hoàn thành vào [0;1].

**Chứng minh.** Đa thức có tính phản xạ, tức là có tính chất $P(x) = x^4 P\left(\frac{1}{x}\right)$.

Pozny có thể dễ dàng phân tích nó:

$$P(x) = \left( x^2 - \frac{\sqrt{13} + 1}{2} x + 1 \right) \left( x^2 + \frac{\sqrt{13} - 1}{2} x + 1 \right).$$

Tam thức bình phương trong ngoặc đầu tiên có nghiệm thực $x_1 = R \approx 1,722$ và $x_2 = \frac{1}{R} \approx 0,58$. Tam thức bình phương trong ngoặc thứ hai có hai nghiệm hoàn chỉnh $x_3$ và $x_4$. Chúng đại diện cho một cặp số liên hợp đầy đủ (vì đa thức là số thực) và đồng thời $x_3 = 1/x_4$ (vì đa thức là số thực). Đối với Poseny, các nghiệm $x_3$ và $x_4$ bằng 1 về mô đun và có thể viết là

$$x_3 = \cos \varphi + i \sin \varphi \text{ и } x_4 = \cos \varphi - i \sin \varphi.$$

Chúng ta hãy kiểm tra xem góc $\varphi$ có vô tỉ với $\pi$ hay không. Thật vậy, giả sử rằng $\varphi = \frac{k}{m} \cdot \pi$. Khi đó các số $x_3$ và $x_4$ là nghiệm của đa thức $G(x) = x^{2m} - 1$, còn $x_1$ và $x_2$ không phải là nghiệm của $G(x)$, vì $|x_1|, |x_2| \neq 1$. Điều này có nghĩa là ước số chung nhất của đa thức $P(x)$ và $G(x)$ là tam thức bậc hai $x^2 + \frac{\sqrt{13} - 1}{2} x + 1$. Nhưng nó không thể
