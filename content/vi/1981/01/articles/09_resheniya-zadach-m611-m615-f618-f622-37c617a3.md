---
id: 1981-1-resheniya-zadach-m611-m615-f618-f622-37c617a3
issue: kvant_1981_1
year: 1981
number: "1"
title: Lời giải bài toán M611—M615; F618—F622
rubric: zadachnik-kvanta
rubric_sub: Задачник «Кванта»
page_first: 30
page_last: 34
page_labels: 28, 29, 31, 32
tag: JXXY
lang: vi
source: kvant_digital
extraction: vision
content_sha256: cfff9ce3cc502cbf3afddcf1bd11b0588bd597c3c1bc4760990b94321203a211
prompt_sha256: draft-1
translated_from: content/ru/1981/01/articles/09_resheniya-zadach-m611-m615-f618-f622-37c617a3.md
source_content_sha256: f3ec660cbfca09844f8de1c10b534533b46637f60ba477db7888118c5b1c4423
translation_model: draft
translation_run: vi-draft-2026-10-31
translation_quality: draft
---

⟦folio 28⟧

Lời giải bài toán
M611—M615; F618—F622

M611. Trên dây AB của đường tròn tâm O lấy một điểm M tùy ý. Qua các điểm A, M và O vẽ đường tròn cắt đường tròn thứ nhất tại các điểm A và C. Chứng minh rằng $|MB| = |MC|$.

Hãy để $\widehat{ABC} = \beta$. Sau đó, $\widehat{AOC} = 2\beta$, vì $\widehat{ABC}$ và $\widehat{AOC}$ lần lượt được ghi và các góc ở tâm dựa trên cùng một cung AC của đường tròn đã cho (màu đen - xem hình).

Mặt khác, $\widehat{AMC}$ và $\widehat{AOC}$ là các góc nội tiếp chắn bởi cùng một cung AC của đường tròn dựng nên (màu xanh) (nằm trong đường tròn không đen). Vì vậy $\widehat{AMC} = 2\beta$.

$AMC$ là góc ngoài của tam giác MBC. Vì vậy, $\widehat{MCB} = \widehat{AMC} - \widehat{MBC} = \beta$. Từ $\widehat{MCB} = \widehat{AMC}$ theo sau $|MB| = |MC|$.

lời giải này phù hợp (không giống như một số lời giải do độc giả gửi) cho bất kỳ vị trí nào của điểm M trên [AB], ngoại trừ khi M trùng với trung điểm của dây AB. Trong trường hợp cuối cùng này, vòng tròn màu xanh lam chạm vào vòng tròn màu đen, điểm A và C hợp nhất và đẳng thức $|MB| = |MC|$ chuyển thành đẳng thức $|MB| = |MA|$.

Hãy suy nghĩ xem liệu tuyên bố đã được chứng minh có còn đúng hay không nếu M được lấy tiếp theo đoạn AB.

N. Vasiliev

M612. Dãy số tự nhiên tăng dần ($a_n$) sao cho $a_{n+1} \leq 10a_n$. Chứng minh rằng nếu tất cả các số $a_n$ được viết cạnh nhau (không có dấu cách hoặc dấu phẩy) thì dãy số thu được sẽ không tuần hoàn.

Giả sử rằng chúng ta có một chuỗi các chữ số tuần hoàn và độ dài của dấu chấm (số chữ số trong đó) bằng T. Dễ dàng thấy rằng số $a_{n+1}$ có thể “dài” hơn số $a_n$ không quá một chữ số (và tất nhiên là không ngắn hơn). Vì chuỗi ($a_n$) đang quay trở lại nên nó chứa các số có độ dài bất kỳ lớn hơn độ dài của $a_1$. Do đó, trong đó có sai số $a_m$, độ dài của số đó $kT$ là bội số của dấu chấm (xem hình). Các chữ số $kT$ đầu tiên của $a_{m+1}$ phải khớp với các chữ số của $a_m$, vì vậy $a_{m+1}$ có thêm một chữ số ($a_{m+1} > a_m$) và nó phải có số 0 ($10a_m \geq a_{m+1}$). Nhưng khi đó chữ số đầu tiên trong mục $a_m$ bằng 0, điều này tất nhiên là không thể.

Lưu ý rằng nếu điều kiện $a_{n+1} \leq 10a_n$ được thay thế bằng điều kiện yếu hơn một chút: $a_{n+1} \leq 10a_n + 1$ hoặc $a_{n+1} \leq (10 + \varepsilon)a_n$, trong đó $\varepsilon$ là một số dương tùy ý, thì chuỗi chữ số thu được có thể tuần hoàn.

I. Klumova

M613. Trên các cạnh của tam giác ABC, dựng các tam giác đồng dạng ADB, BEC và CFA ($|AD|/|DB| = = |BE|/|EC| = = |CF|/|FA| = k$, $ADB = BEC = CFA = \alpha$) ra bên ngoài. Chứng minh rằng a) Trung điểm các đoạn AC, DC, BC và EF là các đỉnh của hình bình hành; b) hình bình hành này có hai số nguyên gọi là a và tỉ số độ dài các cạnh bằng k.

Chúng ta biểu thị bằng $\vec{a}'$ vectơ thu được từ vectơ $\vec{a}$ bằng cách quay một góc a ngược chiều kim đồng hồ. (Đã biết rằng $(k\vec{a})' = k\vec{a}'$ với mọi số $k$, $(\vec{a} + \vec{b})' = \vec{a}' + \vec{b}'$, và nói chung, với mọi số hạng, $(\vec{a} + \vec{b} + \dots + \vec{c})' = \vec{a}' + \vec{b}' + \dots + \vec{c}'$.) Hãy giới thiệu các vectơ $\vec{DA} = \vec{a}$, $\vec{EB} = \vec{b}$, $\vec{FC} = \vec{c}$ (xem hình).

Theo điều kiện $\vec{DB} = \frac{1}{k}\vec{a}'$, $\vec{EC} = \frac{1}{k}\vec{b}'$, $\vec{FA} = \frac{1}{k}\vec{c}'$.

Vì $\vec{AD} + \vec{DB} + \vec{BE} + \vec{EC} + \vec{FC} + \vec{FA} = 0$, $\vec{a} + \frac{1}{k}\vec{a}' - \vec{b} + \frac{1}{k}\vec{b}' - \vec{c} + \frac{1}{k}\vec{c}' = 0$, tức là $\vec{a} + \vec{b} + \vec{c} = \frac{\vec{a}' + \vec{b}' + \vec{c}'}{k} = \frac{1}{k} (\vec{a} + \vec{b} + \vec{c})'$.

Biểu thị $\vec{a} + \vec{b} + \vec{c}$ bằng $\vec{u}$, chúng ta thu được $\vec{u} - \frac{1}{k}\vec{u}' = 0$. (*)

Vì các vectơ $\vec{u}$ và $\vec{u}'$ không thẳng hàng ($\alpha \neq 0$ và $\alpha \neq 2\pi$), nên có thể bằng (*) khi $\vec{u} = \vec{0}$. Vì vậy $\vec{a} + \vec{b} + \vec{c} = \vec{0}$.

⟦folio 29⟧

Hơn nữa, vì $Q$ là phần giữa của $[DC]$ và $P$ là phần giữa của $[AC]$ (xem hình), $\overrightarrow{QP} = \frac{1}{2} \vec{a}$. Tương tự như $\overrightarrow{QR} = \frac{1}{2} \overrightarrow{DB}$. Từ $(PQ) \parallel (AD)$ và $(QR) \parallel (BD)$ nó theo sau $PQR = \alpha$.

Cuối cùng,

$$\overrightarrow{RS} = \overrightarrow{RC} + \overrightarrow{CF} + \overrightarrow{FS} = \frac{1}{2} \overrightarrow{BC} - \vec{c} + \frac{1}{2} \overrightarrow{FE} =$$

$$= \frac{1}{2} \left( -\vec{b} + \frac{1}{k} \vec{b}' \right) - \vec{c} + \frac{1}{2} \left( \vec{c} - \frac{1}{k} \vec{b}' \right) = -\frac{\vec{b} + \vec{c}}{2} = \frac{\vec{a}}{2} = \overrightarrow{QP}$$

Như vậy, tứ giác $PQRS$ là hình bình hành có góc $PQR$ bằng $\alpha$ và tỉ số độ dài các cạnh $|PQ|/|RQ| = |AD|/|DB| = k$.

L. Kuptsov

**M614. Với mỗi số tự nhiên $n$, gọi $S(n)$ biểu thị tổng các chữ số của tất cả các số tự nhiên từ 1 đến $n$ (theo ký hiệu thập phân):

$S(1) = 1, S(2) = 3, S(3) = 6, \dots, S(9) = 45, S(10) = 46, S(11) = 48, S(12) = 51, \dots$

a) Tìm $S(100)$.

b) Chứng minh rằng $S(10^k - 1) = 45k \cdot 10^{k-1}(*)$ với mọi $k = 1, 2, \dots$

c) Chứng minh rằng với hai số tự nhiên $\overrightarrow{ab}$

$$S(\overrightarrow{ab}) = 5a^2 + ab + 41a + b(b+1)/2.$$

f) Tìm công thức tương tự cho số có ba chữ số.

e) Tính tổng $S(1980)$.

Chúng ta hãy rút ra công thức tổng quát cho $S(\overrightarrow{a_k a_{k-1} \dots a_1})$. Hãy biểu thị tổng này dưới dạng các số hạng $a_k + 1$, tính toán riêng cho các số có chữ số thứ $k$ lần lượt là 0, 1, ..., $a_k - 1$ và $a_k$.

Các thuật ngữ $a_k$ đầu tiên rất rõ ràng: trong chúng, không có hạn chế nào được áp đặt đối với các chữ số có chữ số nhỏ hơn $k$. Nếu chữ số thứ $k$ bằng $b$ (và $0 \leq b \leq a_k - 1$), thì tổng các chữ số của tất cả các số đó sẽ bằng $10^{k-1} \cdot b + S(10^{k-1} - 1)$ (phần đóng góp của chữ số thứ $k$ và của các chữ số còn lại tương ứng). Thuật ngữ thứ $(a_k + 1)$ (khi chữ số thứ $k$ chứa chữ số $a_k$) trông như thế này: $a_k \cdot (\overrightarrow{a_{k-1} \dots a_1} + 1) + S(\overrightarrow{a_{k-1} \dots a_1})$ (một lần nữa phần đóng góp của chữ số thứ $k$ và các chữ số còn lại tương ứng).

Được rồi, cuối cùng với $S(\overrightarrow{a_k \dots a_1})$ chúng tôi nhận được

$$S(\overrightarrow{a_k \dots a_1}) = a_k \cdot (\overrightarrow{a_{k-1} \dots a_1} + 1) + S(\overrightarrow{a_{k-1} \dots a_1}) +$$

$$+ 10^{k-1}(0 + 1 + \dots + (a_k - 1)) + a_k \cdot S(10^{k-1} - 1) =$$

$$= a_k \cdot (\overrightarrow{a_{k-1} \dots a_1} + 1) + S(\overrightarrow{a_{k-1} \dots a_1}) + 5 \cdot 10^{k-2}a_k(a_k - 1) +$$

$$+ a_k \cdot S(10^{k-1} - 1).$$

Vẫn còn phải tính $S(10^{k-1} - 1)$. Nếu chúng ta sử dụng công thức đã dẫn xuất, chúng ta sẽ nhận được

$$S(10^{k-1} - 1) = 9 \cdot 10^{k-2} + S(10^{k-2} - 1) + 5 \cdot 10^{k-3} \cdot 9 \cdot 8 +$$

$$+ 9 \cdot S(10^{k-2} - 1) = 10 \cdot S(10^{k-2} - 1) + 45 \cdot 10^{k-2}.$$

Nếu chúng ta coi nó đã được chứng minh rằng

$$S(10^{k-2} - 1) = 45(k - 2) \cdot 10^{k-3},$$

chúng ta có được công thức

$$S(10^{k-1} - 1) = 45(k - 1) \cdot 10^{k-2},$$

Chỉ cần chứng minh (*) (xem mục 6) điều kiện của $k = 1$ là đủ.

Ta có $S(10 - 1) = 45 \cdot 1 \cdot 10^\circ = 45$ - công thức (*) đúng. Vì vậy, $S(10^k - 1) = 45k \cdot 10^{k-1}$ - chúng tôi đã chứng minh được tuyên bố 6) bài toán.

Đối với hai giá trị này mang lại

$$S(\overrightarrow{a_2 a_1}) = a_2(a_1 + 1) + S(a_1) + 5a_2(a_2 - 1) +$$

$$+ 45a_2 = a_2(5a_2 + a_1 + 41) + \frac{a_1(a_1 + 1)}{2} -$$

- xem điểm trong bài toán.

Đối với số có ba chữ số

$$S(\overrightarrow{a_3 a_2 a_1}) = a_3((\overrightarrow{a_2 a_1} + 1) + 900 + 50(a_3 - 1)) + S(\overrightarrow{a_2 a_1}) =$$

$$= a_3(50a_3 + \overrightarrow{a_2 a_1} + 851) + a_2(5a_2 + a_1 + 41) + \frac{a_1(a_1 + 1)}{2}.$$

(Cụ thể là $S(100) = 901$).

Cuối cùng,

$$S(1980) = 980 + 1 + 45 \cdot 3 \cdot 10^2 + S(980) =$$

$$= 13500 + 981 + 9(450 + 80 + 851) + 8(40 + 41) = 27558.$$

I. Klumova

⟦folio 31⟧

chúng tôi nói $F = 10$ cm. Điểm được trộn ở khoảng cách $h = 5$ cm trong mặt phẳng vuông góc với trục quang chính. Cần dịch chuyển thấu kính bao nhiêu và đến đâu để vùng chọn điểm sáng trở về vị trí cũ?

chuyển động theo hướng ngược lại với hướng chuyển động của điểm.

Khi di chuyển điểm $A$ đến điểm $A'$, quang tâm của thấu kính phải dịch chuyển từ điểm $O$ đến điểm $O'$ sao cho các điểm $A', B, O'$ nằm trên cùng một đường thẳng. Ở vị trí mới của thấu kính, trục quang $N'N'$ của nó phải song song với đường thẳng $NN$.

Từ hình vẽ cho thấy khoảng cách $x$ mà tại đó quang tâm của thấu kính phải trộn đều thỏa mãn điều kiện

$$\frac{x}{h} = \frac{f}{d-f} \Rightarrow x = \frac{hf}{d-f}.$$

Chúng tôi tìm thấy giá trị không có trọng số $f$ bằng cách sử dụng công thức thấu kính phân kỳ:

$$\frac{1}{d} - \frac{1}{f} = -\frac{1}{F} \Rightarrow f = \frac{dF}{d+F}.$$

Như vậy,

$$x = \frac{hF}{d} = 1,25 \text{ см.}$$

A. Izerenin, S. Manida, V. Saulit

F620. Nếu bạn đặt một vật có khối lượng lớn hơn $m$ vào giữa bàn vuông thì chân bàn sẽ bị gãy. Tìm một tập hợp các điểm trên bàn để bạn có thể đặt một vật có khối lượng $m/2$ mà không sợ làm vỡ bàn.

Để ngăn các chân bàn bị gãy, lực tác dụng lên mỗi chân không được lớn hơn $m/4$ (điều này tuân theo điều kiện bài toán). Chúng ta hãy xem lực $f_1$ tác dụng lên chân $I$ (Hình 1), khi có một tải trọng $m/2$ đặt lên bàn tại một điểm có tọa độ $x, y$ (điểm $I$ được lấy làm gốc tọa độ).

Gọi $f_2, f_3, f_4$ lần lượt là các lực tác dụng lên chân $II, III, IV$. Rõ ràng rằng tác dụng của các lực $f_1$ và $f_2$ tương đương với tác dụng của lực $f_{1-2} = f_1 + f_2$ tác dụng tại điểm $A$ có tọa độ {0; $y$} và tác dụng của các lực $f_3$ và $f_4$ tương đương với tác dụng của lực $f_{3-4} = f_3 + f_4$ tác dụng tại điểm $B$ có tọa độ { $l$; $y$} (chiều dài cạnh bàn là $l$). Viết các điều kiện cân bằng vào bảng:

$$f_{1-2} + f_{3-4} = \frac{mg}{2},$$

$$f_{1-2} x = f_{3-4} (l - x).$$

Từ đây

$$f_1 + f_2 = f_{1-2} = \frac{mg}{2} \frac{l-x}{l}.$$

Mặt khác, $f_1 y = f_2 (l - y)$, từ đâu

$$f_1 = f_2 \frac{l-y}{y}.$$

Từ (1) và (2) ta tìm được

$$f_1 = \frac{mg}{2} \frac{(l-x)(l-y)}{l^2}.$$

Để chân không bị gãy phải đáp ứng các điều kiện sau:

$$f_1 = \frac{mg}{2} \frac{(l-x)(l-y)}{l^2} < \frac{mg}{4},$$

nghĩa là tải trọng $m/2$ có thể đứng tại một điểm có tọa độ liên hệ với các hệ thức

$$y > l \left(1 - \frac{l}{2(l-x)}\right).$$

Đồ thị hàm số $y(x) = l \left(1 - \frac{l}{2(l-x)}\right)$ chỉ hiển thị

⟦folio 32⟧

F621. Ném phần cuối của sợi chỉ vào ống cuộn có hình ngôi sao vào tường (xem hình). Sợi chỉ được kéo với tốc độ không đổi v. Tâm của ống quay chuyển động với tốc độ bao nhiêu vào thời điểm sợi chỉ tạo một góc a với phương thẳng đứng? Bán kính ngoài của cuộn dây là R, bán kính trong là r.

Nếu kéo sợi chỉ như hình vẽ thì suốt chỉ sẽ lăn sang phải, đồng thời quay theo chiều kim đồng hồ xung quanh chuyển động và tốc độ tuyến tính của chuyển động quay với vận tốc góc ω theo phương của sợi chỉ bằng v:

$$v_0 \sin \alpha - \omega r = v$$

(v₀ là mô đun của tốc độ mong muốn). Do cuộn dây không trượt dọc theo mặt ngang nên tổng các hình chiếu của vận tốc tương ứng tại điểm C bằng 0:

$$v_0 - \omega R = 0.$$

Các phương trình kết quả cho

$$v_0 = v \frac{R}{R \sin \alpha - r}.$$

Rõ ràng, khi R \sin \alpha = r (điều này tương ứng với trường hợp các điểm A, B và C nằm trên cùng một đường thẳng), biểu thức của v₀ sẽ mất đi ý nghĩa. Cũng lưu ý rằng biểu thức tìm được mô tả chuyển động của cuộn dây cả về bên phải (khi điểm B ở bên trái đường thẳng AC và R \sin \alpha > r) và bên trái (khi điểm B ở bên phải đường thẳng AC và R \sin \alpha < r).

S. Krotov

F622. Khi nào và bao nhiêu lần độ ẩm không khí tuyệt đối (mật độ không khí) trong nubre ở nhiệt độ t₁ = 0°C và độ ẩm 95% hoặc trong nyula ở t₂ = 35°C và độ ẩm 40%, nếu áp suất hơi bão hòa ở t₁ = 0°C là p₁ = 6 10²Pa và ở t₂ = 35°C thì p₂ = 5,5 × 10³Pa?

Áp suất hơi nước ở độ ẩm tương đối α bằng

$$p = \alpha p_H,$$

trong đó p_H là áp suất hơi bão hòa ở nhiệt độ nhất định. Chúng ta tìm mật độ hơi nước (độ ẩm tuyệt đối) từ phương trình trạng thái khí:

$$pV = \frac{m}{\mu} RT \Rightarrow \varrho = \frac{m}{V} = \frac{\mu p}{RT} = \frac{\mu a p_H}{RT}.$$

Tỷ lệ mật độ hơi nước q₂/q₁ trong 0 và trong nyubre trong các điều kiện xác định (α₂ = 0,4, T₂ = 308 K, p_H₂ = p₂ = 5,5 10³Pa, α₁ = 0,95, T₁ = 273 K, p_H₁ = p₁ = 6 10²Pa) bằng

$$\frac{q_2}{q_1} = \frac{\alpha_2 p_2}{\alpha_1 p_1} \cdot \frac{T_1}{T_2} \approx 3,4.$$

Do đó, ở nyubr khô (độ ẩm 40%) lượng hơi nước trong không khí cao gấp 3,4 lần so với nyubr thô (độ ẩm 95%).

V. Belonukkin
