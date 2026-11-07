---
id: 1992-6-resheniya-zadach-m1316-m1320-f1333-f1337-a72aad23
issue: kvant_1992_6
year: 1992
number: "6"
title: Lời giải bài toán M1316—M1320; F1333—F1337
rubric: zadachnik-kvanta
rubric_sub: Задачник «Кванта»
page_first: 26
page_last: 36
page_labels: 24, 26, 27, 28, 29, 31, 33, 34
lang: vi
source: kvant_digital
extraction: vision
content_sha256: ecdf4a3028a51d1c3effe59fc6679b78523d534cb3748ac161d419cfff77270a
prompt_sha256: draft-1
translated_from: content/ru/1992/06/articles/08_resheniya-zadach-m1316-m1320-f1333-f1337-a72aad23.md
source_content_sha256: bf36d002e5027ebea02ce7192c588757f56e77ebfc94744ca652f40e7a6b6b6a
translation_model: draft
translation_run: vi-draft-gaps-2026-11-07
translation_quality: draft
---

⟦folio 24⟧

Lời giải bài toán
M1316—M1220, F1333—F1337

M1316. Chứng minh rằng một cấp số cộng của các số tự nhiên khác nhau, không có số nào chứa chữ số c trong thiết kế của nó, tương ứng với a) với $c \neq 0$ không quá 72 số, b) với $c = 0$ không quá 80 số. Những đánh giá này có sẵn không?

Giả sử $a_1, a_2, \dots$ là một cấp số cộng vô hạn có số hạng đầu tiên $a_1$ và hiệu $d$ là các số tự nhiên.

Có một bài toán đơn giản để chứng minh: với bất kỳ chữ số c nào cũng tồn tại một số hạng trong cấp số cộng có ký hiệu chứa $c$. Chúng ta phải chứng minh một phát biểu tinh tế hơn: thuật ngữ như vậy có thể được tìm thấy trong số $a_1, \dots, a_{73}$ (tại $c \neq 0$) hoặc trong số $a_1, \dots, a_{81}$ (tại $c = 0$).

Nếu vị trí thứ $k$ bên phải số tự nhiên $N$ có chữ số $c$ thì phần dư của phép chia $N$ cho $10^k$ nằm trong khoảng $[c \cdot 10^{k-1}; (c+1) \cdot 10^{k-1})$.

⟦folio 26⟧

---
running_head:
folio:
---

Mặt khác, dãy số $l'_1, l'_2, l'_3, \dots$ không bị chặn (vì $l'_k = \frac{10^k}{(d, 10^k)} \geq \frac{10^k}{d}$ và số $d$ là hằng số). Đặc biệt, tồn tại $k$ sao cho $l'_k \geq 10$.

Gọi $k_0$ là số hạng nhỏ nhất của dãy thỏa mãn (2). Sau đó $l'_k_0 \leq 80$.

Thật vậy, nếu $k_0 = 1$ thì $l'_k_0 = l'_1 = \frac{10}{(d, 10)}$ $\leq 10 < 80$. Nếu $k_0 \geq 2$ thì $l'_k_0 = \frac{10^{k_0}}{(d, 10^{k_0})}$ $\leq \frac{10^{k_0}}{(d, 10^{k_0}-1)}$ $= 10 \cdot \frac{10^{k_0}-1}{(d, 10^{k_0}-1)} = 10l'_k_0 - 1 \leq 10 \cdot 8 = 80$ (vì từ $l'_k_0 - 1 < 10$ nên theo sau là $l'_k_0 - 1 \leq 8$).

Bây giờ chúng ta sẽ xem xét riêng các điểm a) và 6) bài toán.

a) Đặt $c \neq 0$. Chúng ta hãy xét phần dư của số hạng $l'_k_0$ đầu tiên của cấp số nhân khi chia cho $10^{k_0}$. Không ít hơn $\left[ \frac{l'_k_0}{10} \right]$ trong số chúng sẽ rơi vào khoảng $\left[ c \cdot 10^{k_0}-1 \right]$; $(c+1) \cdot 10^{k_0}-1)$, tức là, ít nhất $\left[ \frac{l'_k_0}{10} \right]$ trong số $l'_k_0$ thành viên đầu tiên của tiến trình có chữ số $c$ ở vị trí thứ $k_0$ bên phải. Không có nhiều hơn $l'_k_0 - \left[ \frac{l'_k_0}{10} \right] \leq 72$ thành viên khác (trung bình của $l'_k_0$) đầu tiên trong tiến trình.

6) Hãy để $c = 0$. Nếu $a_1 \geq 10^{k_0}-1$ thì trường hợp này không khác gì trường hợp $c \neq 0$. Nói chung, vì thông thường người ta không bắt đầu viết một số tự nhiên từ 0, nên bạn cần lưu ý rằng một số thành viên của cấp số có thể chứa ít hơn $k_0$ chữ số. Nếu $a_1 < 10^{k_0}-1$ thì hiệu $a_{l_k+1} - a_1 = l'_k_0 d = \frac{10^{k_0} \cdot d}{(d, 10^{k_0})}$ là bội số của $10^{k_0}$ và chữ số thứ $k$ tính từ bên phải của số $a_{l_k+1}$ bằng 0. Do đó, không thể viết nhiều hơn $l'_k_0 \leq 80$ số hạng của cấp số nhân mà không có số 0.

Tồn tại một cấp số gồm 72 (cho $c = 1, 2, \dots, 9$) và 80 (cho $c = 0$) các số tự nhiên khác nhau không chứa chữ số $c$. Ví dụ: cấp số cộng có chênh lệch là 125 và các số hạng đầu tiên bằng $c = 1, 2, \dots, 9$, 0, tương ứng là 22075, 3055, 4025, 5000, 6111, 7075, 8055, 9025, 10000, 111.

Điều thú vị là điều tương tự, nhưng dành cho trường hợp đặc biệt $c = 9$, bài toán, được phát minh bởi V. Bugaenko và được đề xuất tại Tour of Cities mùa thu (1991).

Đối với $c = 9$ có một lời giải đơn giản hơn, bản chất của nó như sau.

⟦folio 27⟧

---
running_head:
folio:
---

Giả sử các số hạng của cấp số $a_1, a_2, \dots, a_l$ không chứa số chín trong ký hiệu thập phân của chúng và hiệu $d$ của cấp số nhân là $10^{n-1} \leq d < 10^n$ đối với một số tự nhiên $n$. Sau đó, như dễ thấy, ở vị trí thứ $(n+2)$ bên phải, tất cả các thành viên của cấp số nhân đều có cùng chữ số hoặc không có chữ số. Điều thứ hai diễn ra trong $a_l < 10^{n+2}$ và chính điều này mà chúng tôi phục vụ, không vi phạm tính tổng quát của lý luận, chúng tôi sẽ hạn chế bản thân.

Tất cả các số hạng của cấp số nhân nằm trong sự hợp của 9 khoảng $[0; 88...8] \cup [10...0; 188...8] \cup \dots \cup [80...0; 88...8]$ (đầu bên phải của cấp số đầu tiên chứa $n$ chữ số, phần cuối của tất cả các cấp số khác chứa $(n+1)$ chữ số). Giả sử rằng $l \geq 73$. Khi đó, theo nguyên lý Dirichlet, một số cấp số nhân sẽ có ít nhất 9 số hạng của cấp số nhân. Nhưng điều sau chỉ có thể thực hiện được nếu

$$d \leq \frac{10^n - 1}{9},$$ nhỏ hơn chênh lệch giữa các đầu gần nhất của các tiến trình liền kề. Điều này dẫn đến mâu thuẫn với thực tế rằng $a_1, a_2, \dots, a_l$ là một cấp số cộng.

S. Tokarev

M1317. Với tam giác ABC bất kỳ, hãy chứng minh bất đẳng thức

$$\frac{1}{4} < \frac{IA \cdot IB \cdot IC}{l_A \cdot l_B \cdot l_C} \leq \frac{8}{27},$$

trong đó $I$ là tâm đường tròn nội tiếp, $l_A, l_B, l_C$ là độ dài các đường phân giác của tam giác ABC.

Đặt $AD = h_A$ và một điểm $F$ trên $AD$ sao cho $IF \perp AD$ (xem hình). Từ sự giống nhau của tam giác $AKD$ và $AIF$ ta có:

$$\frac{IA}{l_A} = \frac{h_A - r}{h_A}.$$ Sử dụng đẳng thức này dễ dàng chứng minh được rằng $$\frac{IA}{l_A} = \frac{b + c}{a + b + c}, \quad \frac{IB}{l_B} = \frac{a + c}{a + b + c}, \quad \frac{IC}{l_C} = \frac{a + b}{a + b + c}.$$

Từ bất đẳng thức Cauchy suy ra rằng

$$\frac{1}{3} \left( \frac{b + c}{a + b + c} + \frac{a + c}{a + b + c} + \frac{a + b}{a + b + c} \right) \geq$$

$$\geq \sqrt[3]{\frac{(a + b)(b + c)(c + a)}{(a + b + c)^3}}.$$

Kể từ đây,

$$\left( \frac{2}{3} \right)^3 \geq \frac{IA \cdot IB \cdot IC}{l_A \cdot l_B \cdot l_C}.$$

Hãy chứng minh bất đẳng thức

$$\frac{(b + c)(a + c)(a + b)}{(a + b + c)^3} > \frac{1}{4}.$$

Để dựng một tam giác từ các đoạn có độ dài $a, b, c$, cần phải (và dễ dàng chứng minh là đủ) phải thỏa mãn bất đẳng thức

$$(a + b - c)(a + c - b)(b + c - a) > 0.$$

⟦folio 28⟧

---
running_head:
folio:
---

Xét đa thức $P(x)$ có nghiệm là các số $a, b, c$: $P(x) = (x-a)(x-b)(x-c) = x^3 - px^2 + qx - r$, trong đó $p = a + b + c, q = ab + bc + ac, r = abc$.
Bất đẳng thức (1) cho:

$$-p^3 + 4pq - 8r > 0,$$

(*)

và bất đẳng thức bài toán được rút gọn về dạng: $-p^3 + 4pq - 4r > 0$ và ngay sau (*).

Lưu ý rằng ước tính cho SIZU theo số $\frac{1}{4}$ là chính xác: chỉ cần xét các tam giác có cạnh 1, 1, $x$ cho $x \rightarrow 0$ là đủ.

Cũng lưu ý rằng việc đưa đa thức vào lời giải này là không cần thiết: ​​nó chỉ đơn giản hóa việc viết các phép tính đơn giản và tự nhiên trong đó chỉ xuất hiện các số $a, b, c$.

Chúng ta cũng hãy lưu ý e. Giả sử bất đẳng thức (1) được thỏa mãn và không phải tất cả các dấu ngoặc đều dương. Sau đó, các số âm xuất hiện ở hai trong số chúng, ví dụ: $a+b-c<0, a+c-b<0$. Cộng các bất đẳng thức này, ta thu được: $2a<0$. Sự mâu thuẫn.

V. Người gửi

M1318. Cho một đồ thị liên thông có n cạnh. Chứng minh rằng các cạnh của nó có thể chứa các số từ 1 đến $n$ sao cho với mỗi đỉnh mà từ đó có ít nhất hai cạnh xuất hiện thì các số trên các cạnh này không có ước chung lớn 1. (Đồ thị là một hệ gồm các điểm có các cặp điểm không xoắn được nối với nhau bằng các cạnh. Một đồ thị được gọi là liên thông nếu dọc theo các cạnh của nó, người ta có thể đi từ đỉnh này sang đỉnh khác.)

Bắt đầu từ một số đỉnh $v_0$, chúng ta sẽ đi dọc theo các cạnh khác nhau của đồ thị, đánh số chúng liên tiếp 1, 2, ... $s$, miễn là có thể.

Kết quả là, nếu vẫn còn các cạnh không được đánh số, thì do tính liên thông của đồ thị, ít nhất một trong số chúng đi ra khỏi đỉnh mà chúng ta đã ghé thăm. Bắt đầu từ đỉnh này, chúng ta sẽ di chuyển dọc theo các cạnh không được đánh số, đánh số chúng liên tiếp $s+1, s+2, ...$ miễn là có thể.

Tiếp tục quá trình này, cuối cùng chúng ta sẽ thu được một số cách đánh số các cạnh của đồ thị. Hãy chứng minh rằng đó chính là thứ chúng ta đang tìm kiếm. Thật vậy, để có ít nhất hai cạnh xuất hiện từ một đỉnh $v$ nào đó. Nếu $v=v_0$ thì một trong các cạnh có số 1 và do đó, ước số chung lớn hơn của các số cạnh bắt nguồn từ $v$ là 1.

Nếu $v \neq v_0$ thì đặt số nhỏ nhất trong số các cạnh rời khỏi đỉnh $v$ bằng $r$. Điều này có nghĩa là lần đầu tiên chúng tôi đạt đến đỉnh $v$ chính xác dọc theo cạnh này ở bước thứ $r$ trong quy trình của chúng tôi. Vì tại thời điểm này vẫn còn các cạnh không được đánh số xuất hiện từ đỉnh $v$, nên một trong số chúng phải có số $r+1$. Ước chung lớn nhất của tập hợp số chứa $r$ và $r+1$ là 1.

V. Vasilov, A. Fomin

⟦folio 29⟧

---
running_head:
folio:
---

M1319. Cho tam giác ABC và điểm M bên trong tam giác đó. Chứng minh rằng có ít nhất một trong các góc MAB, MBC, MCA nhỏ hơn hoặc bằng 30°.

Giả sử điểm M bên trong tam giác ABC sao cho tất cả các góc tính từ điều kiện bài toán đều lớn hơn π/6. Khi đó nó nằm trong tam giác AED (xem hình 1).

Do đó, chỉ cần chứng minh rằng ∠ECA ≤ π/6 là đủ.

Hãy xem xét cấu hình hình 2, trong đó r₁=1, ∠BO₂M=π/3. Điểm A nằm trên đường thẳng l trong đường tròn tâm O₂, điểm M nằm trong tam giác ABC. Hãy chứng minh rằng trong những điều kiện này, các đoạn BM và O₁O₂ có một điểm chung.

Đừng để điều này xảy ra (xem hình 3).

Trên hình 3, đường thẳng MD tiếp tuyến với đường tròn tâm O₁.

Ta có: O₁C ⊥ l, tam giác O₁CM đều, các đoạn thẳng BM và O₁C cắt nhau. Vì góc BMm bằng π/6 nên đường thẳng m tiếp xúc với đường tròn tâm O₂ cắt l tại điểm của tia DC (hoặc m||l). Do đó điểm A chỉ có thể nằm trên tia này; Điều này có nghĩa là điểm M nằm ngoài tam giác ABC.

Chúng ta có: O₁O₂ ∩ BM ≠ ∅.

Với lời giải bài toán chỉ cần chứng minh rằng r₂ ≤ d(O₂, l). (Ở đây d(O₂, l) là khoảng cách từ điểm O₂ đến đường thẳng l.) Đặt d(O₂, l) ≥ d(O₁, l). Chúng ta có: r₂ = 2sin α,

d(O₂, l) = 1 + (cos α + √3/2)·2sin α)·cos (2π/3 - α) =

= 1/2 + 2sin² α ≥ 2sin α = r₂.

Trường hợp d(O₂, l) < d(O₁, l) được xử lý tương tự.

Quét. Một chứng minh đơn giản cũng thừa nhận khẳng định sau. Cho điểm M nằm trong tứ giác ABCD. Khi đó ít nhất một trong các góc MAB, MBC, MCD, MDA nhỏ hơn hoặc bằng π/4. Hãy tự mình chứng minh nhận định này.

V. Người gửi

⟦folio 31⟧

---
running_head:
folio:
---

phong trào không đến được ngày. Ở vị trí nào của tay cầm cổng thì hệ có thể cân bằng trong trường hợp này? Hãy xem xét đèn dây. Trenet có thể bị bỏ qua.

Hình 1.

Hình 2.

F1334. AVVG phẳng vuông mỏng được làm bằng đồng. Nó được gọi là các cạnh của đầu AB, duy trì nhiệt độ bằng 100 ° C, và các cạnh của ba đầu còn lại được làm mát, duy trì nhiệt độ bằng 0 ° C. Tìm nhiệt độ tại tâm của mặt phẳng.

Phải nói ngay rằng rất khó để giải quyết triệt để vấn đề bài toán này - việc tìm ra sự phân bố nhiệt độ trên một mặt phẳng (và đơn giản là không thể trong khuôn khổ chương trình học ở trường). Tuy nhiên, chúng ta chỉ cần tìm nhiệt độ tại một điểm và điểm này nằm rất tốt - ở trung tâm của bề mặt phẳng, nên vấn đề không phải là không gặp khó khăn.

Chúng ta hãy xây dựng một tuyên bố phụ trợ (rất thuận tiện): nếu ở nhiệt độ nhất định của các đầu trong mặt phẳng, sự phân bố nhiệt độ cân bằng được thiết lập và chúng ta tăng nhiệt độ của tất cả các đầu lên giá trị $\Delta t$, thì tất cả nhiệt độ cân bằng cũng sẽ tăng $\Delta t$.

Một tuyên bố khác (ít rõ ràng hơn nhiều - chúng ta sẽ phải suy nghĩ về nó): nếu chúng ta tăng nhiệt độ của các đầu theo các giá trị khác nhau $\Delta t_1$, $\Delta t_2$, $\Delta t_3$, $\Delta t_4$, thì sự tăng nhiệt độ tại một điểm nhất định, do các dòng nhiệt bổ sung đã phát sinh, sẽ bằng nhiệt độ cân bằng tại thời điểm này nếu nhiệt độ của các đầu là $\Delta t_1$, $\Delta t_2$, $\Delta t_3$, $\Delta t_4$.

Điều này cần phải được thảo luận. Thứ nhất, không hoàn toàn rõ ràng những gì chúng ta đã đạt được - xét cho cùng, phần phụ bài toán không có gì đơn giản hơn phần ban đầu (nhiệt độ của các đầu đã được cho trước và chúng ta cần tìm nhiệt độ ở trung tâm). Thực ra, bài toán này vẫn đơn giản hơn - bản thân chúng ta sẽ chọn $\Delta t_1$, ..., $\Delta t_4$ sao cho đáp số dễ đoán. Thứ hai, không phải quốc gia

⟦folio 33⟧

---
running_head:
folio:
---

Thay thế $\Delta\rho = \Delta p / v^2$ ở đây và tính đến $\Delta T / T \ll 1$, chúng ta tìm được
$$\frac{\Delta T}{T} = \frac{\Delta p}{p} \left( 1 - \frac{R T}{M v^2} \right) \approx 0.16 \frac{\Delta p}{p} = 1.6 \cdot 10^{-3}.$$
Vì vậy, $\Delta T \approx 0.5$ K.

R. Alexandrov

F1336. Một tụ điện phẳng, gồm hai bản tròn có diện tích $S$, đặt cách nhau một khoảng nhỏ $d$, được tích điện đến hiệu điện thế $U$. Một quả bóng nhỏ có khối lượng $m$ và điện tích $q$ được đặt ở cùng một khoảng cách $L$ tính từ cả hai bản. Quả bóng bị xỉn màu. Tăng tốc độ của nó ở thời điểm đầu tiên sau khi thả ra và tốc độ tối đa mà nó sẽ đạt được trong một khoảng thời gian dài. Coi khoảng cách $L$ lớn hơn nhiều lần kích thước của tụ điện. Đừng tính đến lực lượng.

Để các bản tụ được tích điện với điện tích $+Q$ và $-Q$ (xem hình). Sau đó
$$Q = CU = \varepsilon_0 SU / d$$
- quả cầu tích điện nằm ở xa và chúng ta đã bỏ qua ảnh hưởng của nó đến sự phân bố điện tích trên các bản. Xét $L \gg \sqrt{S}$ và $L \gg d$, ta tìm được lực tác dụng lên quả bóng từ tụ điện:
$$F_{\text{полн}} = 2F \sin \frac{\alpha}{2} \approx F \alpha \approx \frac{1}{4 \pi \varepsilon_0} \frac{Q q}{L^2} \frac{d}{L} = \frac{1}{4 \pi \varepsilon_0} \frac{q d}{L^3} \frac{\varepsilon_0 SU}{d} = \frac{1}{4 \pi} \frac{q SU}{L^3}.$$
Khi đó gia tốc ban đầu của quả bóng là
$$a = \frac{F_{\text{полн}}}{m} = \frac{qSU}{4\pi mL^3}.$$
Tại thời điểm quả bóng ở vị trí ban đầu - ở cùng một khoảng cách so với các bản tích điện có độ lớn bằng nhau và trái dấu, thì điện thế của trường tạo ra bởi các điện tích này bằng không. Ở một khoảng cách rất xa so với tụ điện (quả bóng sẽ bay đi sau một thời gian dài), điện thế cũng bằng không. Điều này có nghĩa là tốc độ cuối cùng của quả bóng sẽ bằng 0 - đầu tiên nó sẽ tăng tốc và sau đó giảm tốc.

Z. Rafailov

F1337. Khi nghiên cứu “hộp đen” của dòng điện xoay chiều, mạch điện ở hình 1 đã được sử dụng. Ví dụ: bộ tạo âm thanh ở tất cả các tần số đều bằng 1 V, máy đo milioblut hiển thị ở các tần số khác nhau được đưa ra trong bảng.

Đồ thị của dòng điện so với tần số có mức tối thiểu rõ ràng ở tần số $\approx 450$ Hz. Ví dụ, một mạch dao động song song (hình 2) có đặc điểm như vậy. Về nguyên tắc, có nhiều phương án có tính chất tương tự nhau, chúng tôi đã chọn phương án đơn giản nhất. Chúng ta hãy tìm tham số của các phần tử $r$, $C$, $L$ của đường viền và nếu lấy được số hợp lý thì chúng ta sẽ xem xét giải quyết bài toán.

Ở tần số cao nhất ($f \approx 2000$ Hz), trở kháng mạch $Z_{\text{обц}}$ thực tế xác định điều kiện

⟦folio 34⟧

---
running_head:
folio:
---

Bên trong hộp đen có thể chứa những gì? Tính toán các tham số của các phần tử của mạch được đề xuất cho bạn (cố gắng thực hiện mà không có các thiết bị kỳ lạ, dù sao thì sẽ không có ai tin tưởng giao chúng cho bạn - bạn sẽ làm hỏng chúng!).

$$U_0 = IZ_{0\mathrm{ii}} \approx I \sqrt{X_c^2 + R^2} = \frac{U}{R} \sqrt{X_c^2 + R^2}.$$

Từ đây chúng ta có được

$$X_c = R \sqrt{U_0^2 / U^2} - 1 \approx 700 \mathrm{Om},$$

tương ứng với điện dung của tụ điện

$$C = \frac{1}{2\pi f X_c} \approx 1,1 \cdot 10^{-7} \Phi = 0,11 \mathrm{mkF}.$$

Hãy để chúng tôi làm rõ đánh giá này một chút. Trên thực tế, điện dung điện trở nhỏ hơn 700 Ohms một chút (tức là điện dung lớn hơn một chút) và việc tăng tổng điện trở của “hộp” lên 700 Ohms sẽ cung cấp cho cuộn dây mục tiêu (ảnh hưởng của điện trở hoạt động $r$ trong trường hợp của chúng tôi là không đáng kể - từ giá trị hiện tại ở tần số 400 Hz, chúng tôi có thể kết luận rằng $r > 10$ kOhm). Sau khi đưa ra mức điều chỉnh (20-25%), chúng tôi ước tính công suất như sau:

$$C \approx 0,13 - 0,14 \mathrm{mkF}.$$

Độ tự cảm của cuộn dây trong trường hợp của chúng ta chỉ có thể được ước tính bằng giá trị của tần số cộng hưởng và ước tính tìm được cho điện dung:

$$L \approx \frac{1}{4\pi f_p^2 C} \approx 0,9 \mathrm{Гн}.$$

Các con số cho $C$ và $L$ hóa ra là hoàn toàn hợp lý, giờ đây có thể đưa ra một mạch hợp lý hơn - nó được hiển thị trong hình 3. Thực tế là cuộn cảm, ngay cả với lõi sắt từ, có điện trở khá cao $r_L$ đối với dòng điện một chiều và không cần phải tạo ra một điện trở đặc biệt có điện trở $r$. Giá trị của $r_L$ có thể được ước tính (rất gần đúng!) bằng giá trị của dòng điện ở tần số thấp nhất được sử dụng (200 Hz) - hóa ra là khoảng 200-400 Ohms.

Các số được đưa ra trong điều kiện bài toán rõ ràng đã được làm tròn, vì vậy việc cố gắng có được ước tính chính xác hơn là không có ý nghĩa. Trong thực tế, không cần thiết phải thực hiện các phép đo ở một số tần số cố định mà phải nghiên cứu điểm cộng hưởng chi tiết hơn nhiều.

A. Yashchikov
