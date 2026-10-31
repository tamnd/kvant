---
id: 1983-8-resheniya-zadach-m801-m805-f813-f817-d4478c4a
issue: kvant_1983_8
year: 1983
number: "8"
title: Lời giải bài toán M801—M805; F813—F817
rubric: zadachnik-kvanta
rubric_sub: Задачник «Кванта»
page_first: 52
page_last: 57
page_labels: 50-55
tag: AJ22
lang: vi
source: kvant_digital
extraction: vision
content_sha256: 9a1b4d451d99a25a8914bb28cf824a188fecd99827a36d0a34457e3b69848c85
prompt_sha256: draft-1
translated_from: content/ru/1983/08/articles/15_resheniya-zadach-m801-m805-f813-f817-d4478c4a.md
source_content_sha256: 91383e6c037e7d5f10c8575cddd15a527c54b68d1237384629694c98b1fa51eb
translation_model: draft
translation_run: vi-draft-2026-10-31
translation_quality: draft
---

⟦folio 50⟧

P832*. Một khung siêu dẫn hình vuông không biến dạng có cạnh $a$ được đặt nằm ngang trong một từ trường không đều có cảm ứng trong không gian được cho bởi
$$B_x = -kx, B_y = 0, B_z = kz + B_0.$$
The mass of the frame is $m$, its inductivity is $L$. At the initial moment the centre of the frame is at the origin with sides parallel to the $X$ and $Y$ axes. How will the frame move after it is released and where will it be after time $t$?
O. Yu. Nikishina

Lời giải bài toán

M801—M805; F813—F817

Lưu ý phần nguyên của số $a \geqslant 1$ bằng số số tự nhiên nhỏ hơn hoặc bằng $a$. Cụ thể là $[\sqrt{n}] + [\sqrt[3]{n}] + \dots + [\sqrt[n]{n}] = [\log_2 n] + [\log_3 n] + \dots + [\log_n n]$ ($[x]$ nghĩa là phần nguyên của số $x$).

Vế phải được xử lý tương tự: $[\log_m n] - 1$ là số tự nhiên $x \geqslant 2$ sao cho $x \leqslant \log_m n$, tức là $m^x \leqslant n$. Đó là lý do tại sao
$$([\log_2 n] - 1) + ([\log_3 n] - 1) + \dots + ([\log_n n] - 1) = N$$
(đối với $m > n$, $y \geqslant 2$ thì bất đẳng thức $m^y \leqslant n$ rõ ràng là không đúng).

Vì vậy, cả hai vế đẳng thức của chúng ta đều bằng $N + n - 1$.
V. V. Kasil

M802. Trên các cạnh AB và BC của tam giác ABC, cũng như ở các cạnh trung tâm, các tam giác vuông APB và BQC có các góc ở đỉnh bằng nhau $B$ được dựng bên ngoài nó. Tìm các mặt lồi của tam giác PQK, trong đó $K$ là trung điểm của cạnh AC.

Đáp số: $\hat{P} = \hat{Q} = \beta, \hat{K} = 180^\circ - 2\beta$.

bài toán này thuộc về một nhóm khá lớn bài toán, trong đó các hình tam giác (hoặc đa giác khác) có hình dạng nhất định được xem xét, được xây dựng trên các cạnh của một hình tam giác (hoặc đa giác) khác; Có lẽ nổi tiếng nhất trong số đó là cái gọi là “bài toán Napoleon” - để chứng minh rằng tâm của các tam giác vuông dựng trên các cạnh của một tam giác tùy ý bên ngoài nó tạo thành một tam giác vuông. Nói chung, những bài toán này có thể được giải bằng cách sử dụng thành phần biến đổi mặt phẳng.

Hãy xem xét hai phép biến đổi phân chia (Hình 1):
$$F_p = H_p^k \circ R_p^{90},$$ trong đó $k = |PB|:|PA|$, là thành phần của phép quay $R_p^{90}$ quanh $P$ nhân $90^\circ$ và được chuẩn bị với tâm $P$ và hệ số $k$ và $F_q = H_q^k \circ R_q^{90}$ (các phép biến đổi như vậy được gọi là hình học phép quay hoặc phân chia xoắn ốc). Thành phần của chúng $F = F_q \circ F_p$ giữ nguyên điểm $K$ (điều này giải thích sự lựa chọn của các phép biến đổi như vậy; chúng tôi sẽ đưa ra bằng chứng sau). Đặt $F_p(K) = K_1$ (Hình 2), sau đó đặt $F_q(K_1) = K$. Các hình tam giác $KPK_1, KQK_1$ và APB được ghép với nhau thành các tam giác vuông có cùng tỷ lệ hai chân ($|KP|:|PK_1| = |KQ|:|QK_1| = k = |PA|:|PB|$). Và vì $KK_1$ là cạnh huyền chung của các tam giác $KPK_1$ và $KQK_1$ nên chúng bằng nhau nên $|KP| = |KQ|$. Vì vậy, $\hat{PKQ} = 360^\circ - 2\cdot 90^\circ - 2\beta$, $\hat{KPQ} = \hat{KQP} = (180^\circ - (180^\circ - 2\beta))/2 = \beta$.

Còn phải chứng minh rằng $K$ là điểm cố định trong phép biến đổi của phân khu $F$. Lưu ý các thuộc tính sau của $F$:

⟦folio 51⟧

1) $F$ - độ dịch chuyển (vì hệ số tương tự $F$ bằng $k \cdot \frac{1}{k} = 1$);

2) Khi chuyển động $F$ thì tia nào cũng chuyển hướng ngược lại (với tomathety thì hướng của tia được bảo toàn; khi quay thì tia nào cũng quay một góc bằng góc quay nên tổng góc quay của tia bất kỳ khi biến đổi $F$ đều bằng $90^\circ + 90^\circ = 180^\circ$);

3) $F(A) = C$ ($F_P(A) = B$ theo lựa chọn $F_P$ và $F_Q(B) = C$ vì $BQC = 90^\circ$ và $|QC|:|QB| = |PA|:|PB| = 1/k$).

Điều này ngụ ý rằng $F$ là đối xứng tâm của $Z_K$ với tâm $K$ và đặc biệt là $F(K) = K$.

Hãy thử phương pháp tương tự để giải “bài toán Napoleon”.

V. N. Dubrovsky

M803. Tổng của hai số hữu tỷ $x$ và $y$ là số tự nhiên, tổng nghịch đảo của chúng $1/x$ và $1/y$ cũng là số tự nhiên. $x$ và $y$ có thể là gì?

Đáp số: $(x, y) = (1, 1), (1/2, 1/2), (2, 2)$. Hãy biểu diễn các số $x$ và $y$ dưới dạng phân số tối giản: $x = \frac{a}{b}, y = \frac{c}{d}$. Khi đó $x + y = \frac{ad + bc}{bd}$ là một số tự nhiên. Do đó, $ad + bc$ chia hết cho $b$ và vì $a$ và $b$ là các số nguyên tố cùng nhau nên $d$ chia hết cho $b$. Mặt khác, $ad + bc$ chia hết cho $d$, vì vậy $b$ chia hết cho $d$. Theo sau đó là $b = \pm d$. Tương tự, $\frac{1}{x} + \frac{1}{y} = \frac{ad + bc}{ac}$ là số tự nhiên nên $a = \pm c$. Vì vậy, $x = y$ hoặc $x = -y$. Trường hợp thứ hai là không thể, vì theo điều kiện $x + y \ge 1$. Trong trường hợp đầu tiên, $x + y = 2x = 2a/b$ và $2/x = 2b/a$ là số tự nhiên. nghĩa là, $a$ và $b$ là ước của 2 và $a/b > 0$. Do đó, $a/b = 1/1 = 1$, hoặc $a/b = 1/2$, hoặc $a/b = 2/1 = 2$.

A. P. Savin

M804. Điểm $O$ là trung điểm trục của một hình trụ tròn vuông, $A$ và $B$ là các điểm đối xứng đường kính trên đường tròn đáy dưới của hình trụ, $C$ là một điểm nào đó trên đường tròn đáy trên không nằm trong mặt phẳng $OAB$. Chứng minh rằng tổng hai góc của một tam giác $OABC$ (có đỉnh $O$) là 2π.

Đặt $D$ là một điểm trên đường tròn của đáy trên của hình trụ, đối xứng đường kính với điểm $C$ (Hình 1). Chúng ta chứng minh rằng các góc tam giác $OABC, OBCD, OCDA$ và $ODAB$ có chung một đỉnh $O$ là bằng nhau. Vì ba góc này có chung một cạnh ($OA, OB, OC$ hoặc $OD$) và tổng các góc nhị diện của chúng ở cạnh đó là rất indo, bằng 2π, nên tổng của tất cả 12 góc nhị diện của chúng là $4 \cdot 2\pi = 8\pi$. Do đó, tổng các góc nhị diện của mỗi góc, đặc biệt là góc $OABC$, bằng $8\pi/4 = 2\pi$.

Để chứng minh sự bằng nhau của các góc tam diện này, hãy lưu ý rằng các cạnh đối diện của tam giác $ABCD$ theo cặp bằng nhau ($|AB| = |CD|$ như đường kính của các đường tròn đồng dạng và các cạnh $AC$ Và $BD$, và cả $AD$ Và $BC$ đối xứng lẫn nhau so với hình trụ; (xem hình 1). Và kể từ thời điểm $O$ cách đều tất cả các đỉnh của tam giác $\triangle OAB \cong \triangle OCD, \triangle OAC \cong \triangle OBD$ Và $\triangle OAD \cong \triangle OBC$. Do đó, các góc tam diện đang xét có sự tương ứng của các góc phẳng bằng nhau và do đó bằng nhau. Tính đồng thời của các góc tam diện cũng có thể được chứng minh rõ ràng bằng cách thay thế các đường thẳng nối trung điểm của các cạnh $AC$ Và $BD$, và cả $AD$ Và $BC$, giống như dilinda thông thường, là các trục đồng dạng của tam giác $ABCD$.

Tứ diện $ABCD$ với các mặt bằng nhau sẽ giúp chúng ta giải được bài toán, có nhiều tính chất đáng chú ý. Có một danh sách lớn các thuộc tính của nó trong bài viết của V. E. Matizen ở «Kvant» số 6 cho năm nay.

I. K. Zhuk

⟦folio 52⟧

M805*. a) Trên các cạnh BC, CA, AB của tam giác ABC lần lượt chọn các điểm A₁, B₁, C₁ sao cho các đoạn AA₁, BB₁ và CC₁ cắt nhau tại một điểm. Chứng minh rằng S₁A₁B₁C₁ ₁ABC/4.

6) Trên các mặt BCD, CDA, BDA, ABC của tam giác ABC, lần lượt chọn các điểm A₁, B₁, C₁, D₁ sao cho các đoạn AA₁, BB₁, CC₁, DD₁ cắt nhau tại một điểm. Chứng minh rằng V₁A₁B₁C₁ ₁ABCD/27.

Cơm. 1.

Cơm. 2.

Cơm. 3.

Trước hết, chúng ta sẽ chứng minh một số bổ đề đơn giản nhưng rất hữu ích về mối quan hệ giữa diện tích hình tam giác và thể tích của tứ diện.

(1) Nếu đường thẳng MM₁ cắt đường thẳng KL tại điểm P (Hình 1), thì

$$S_{KLM}: S_{KLM_1} = |MP|: |M_1P|.$$

Điều này suy ra từ đẳng thức hiển nhiên hₘ:hₘ₁ = |MP|: |M_1P|, trong đó hₘ và hₘ₁ là chiều cao của các tam giác KLM và KLM₁.

(2) Nếu điểm L₁ và M₁ nằm trên đường thẳng KL và KM (Hình 2), thì

$$S_{KLM}: S_{KL_1M_1} = \frac{|KL| \cdot |KM|}{|KL_1| \cdot |KM_1|}.$$

Thật vậy, S_{KLM}: S_{KL_1M_1} = (S_{KLM}: S_{KL_1M}) \cdot (S_{KL_1M}: S_{KL_1M_1}) = (|KL|: |KL_1|) \cdot (|KM|: |KM_1|) do (1).

(3) Nếu đường thẳng NN₁ cắt mặt phẳng KLM tại điểm P thì

$$V_{KLMN}: V_{KLMN_1} = |NP|: |N_1P|.$$

(Chứng minh tương tự (1).)

(4) Nếu các điểm L₁, M₁, N₁ nằm trên các đường thẳng KL, KM, KN thì

$$V_{KLMN}: V_{KL_1M_1N_1} = \frac{|KL| \cdot |KM| \cdot |KN|}{|KL_1| \cdot |KM_1| \cdot |KN_1|}$$

(Chứng minh tương tự với (2).)

Hãy đi thẳng tới lời giải bài toán.

a) Gọi O là giao điểm của các đoạn AA₁, BB₁ và CC₁; S, Sₐ, Sₑ và Sₒ là diện tích của các tam giác ABC, OBC, OCA và OAB (Hình 3). Khi đó theo (1)

$$\frac{|OA|}{|OA_1|} = \frac{|AA_1| - |OA_1|}{|OA_1|} = \frac{S}{S_A} - 1 = \frac{S - S_A}{S_A}.$$

Mối quan hệ tương tự được giữ cho các phân đoạn BB₁ và CC₁. Như vậy,

$$\frac{|OA_1|}{|OA_1|} = \frac{S_A}{S - S_A}, \frac{|OB_1|}{|OB_1|} = \frac{S_B}{S - S_B}, \frac{|OC_1|}{|OC_1|} = \frac{S_C}{S - S_C}.$$

Chia thể tích của $\triangle A_1B_1C_1$ thành ba hình tam giác theo các đoạn OA₁, OB₁ và OC₁ rồi ước tính diện tích của từng hình tam giác một cách riêng biệt.

Có hiệu lực (2)

$$S_{OA_1B_1} = S_{OAB} \cdot \frac{|OA_1| \cdot |OB_1|}{|OA| \cdot |OB|} = S_C \cdot \frac{S_A S_B}{(S - S_A)(S - S_B)} = \frac{S_A S_B S_C}{(S - S_A)(S - S_B)(S - S_C)}.$$

$$\cdot (S - S_C) = k \cdot (S - S_C).$$

Cộng đẳng thức này với các đẳng thức tương tự của tam giác OB₁C₁ và OC₁A₁, chúng ta thu được:

$$S_{A_1B_1C_1} = k((S - S_C) + (S - S_A) + (S - S_B)) = 2kS.$$ (*)

Để ước tính k, chúng ta viết “bất đẳng thức về phương tiện” cho Sₐ và Sₑ, Sₑ và Sₒ, Sₒ và Sₐ:

$$\sqrt{S_A S_B} \leq \frac{S_A + S_B}{2}, \sqrt{S_B S_C} \leq \frac{S_B + S_C}{2}, \sqrt{S_C S_A} \leq \frac{S_C + S_A}{2}$$

và các biến của chúng:

$$S_A S_B S_C \leq (S_A + S_B)(S_B + S_C)(S_C + S_A)/8 = (S - S_C)(S - S_A)(S - S_B)/8.$$ (*)

Do đó k 1/8 và S₁A₁B₁C₁ ≤ S₁ABC/4.

6) Chúng tôi sẽ chỉ đưa ra một phác thảo chung về bằng chứng - nó lặp lại cách lập luận ở điểm a) gần như từng chữ.

Gọi O là giao điểm của các đoạn này, V, Vₐ, Vₑ, Vₒ và Vₒ là thể tích của tam giác ABCD, OBCD, OCDA, ODAB và OABC (Hình 4). Bổ đề người dùng (3)

⟦folio 53⟧

F813. Ba thanh bản lề không trọng lượng có chiều dài a, mỗi thanh bản lề ở các điểm A và B nằm trên cùng một phương ngang (xem hình); $|AB|=2a$. Vào khớp treo C một vật có khối lượng m. Với lực nhỏ nhất tác dụng lên bản lề D thì thanh giữa sẽ giữ ở vị trí nằm ngang?

F814. Một quả cầu bán kính R nằm trên mặt phẳng nằm ngang nhẵn của xe. Xe bắt đầu di chuyển với tốc độ $v_0$. Bắt đầu chiếu ngang tốc độ của quả bóng tại thời điểm nó chạm sàn.

và (4) (thay vì (1) và (2) ở phần a)), dễ dàng chứng minh được $V_{A1B1C1D1} = 3kV$,
(xem (*)), ở đâu
$$k = \frac{V_A V_B V_C V_D}{(V - V_A)(V - V_B)(V - V_C)(V - V_D)}.$$

Biến "bất bình đẳng về phương tiện" cho cả bốn hàng bao gồm các số $V_A, V_B, V_C$ và $V_D$:
$$\sqrt[3]{V_A V_B V_C} \leq \frac{1}{3} (V_A + V_B + V_C) = \frac{1}{3} \Pi V - V_D), \dots, \text{ получим}$$
(cf. (**)), tức là $k \leq 1/81$, và do đó $V_{A1B1C1D1} \leq V_{ABCD}/27$.

R. P. Ushakov

◆
Vì khớp C ở trạng thái cân bằng nên tổng các lực tác dụng lên nó bằng 0. Vì vậy (xem hình),
$$(m + m_\omega)g \sin \alpha = T_2 \cos \alpha,$$
(1)
trong đó $m_\omega$ là khối lượng của bản lề. Từ điều kiện cân bằng của bản lề D và điều kiện thanh ngang ở giữa suy ra
$$T_2 \cos \alpha = F \cos \beta + m_\omega g \sin \alpha.$$ (2)
Từ (1) và (2) chúng ta thu được
$$F = \frac{T_2 \cos \alpha - m_\omega g \sin \alpha}{\cos \beta} = \frac{mg \sin \alpha}{\cos \beta} \geq mg \sin \alpha.$$
Do đó, lực tối thiểu $\vec{F}_{\min}$ mà tại đó thanh giữa giữ ở vị trí nằm ngang có giá trị tuyệt đối bằng $mg \sin \alpha = mg/2$ và hướng vuông góc với thanh BD.

S. K. Strokov

Hãy đưa ra một lời giải khác trong số bài toán này, do độc giả A.P. Zubatkin gửi.

Các ngoại lực tác dụng lên hệ gồm: phản lực tác dụng vào các điểm A và B tính từ phía “trần”, bằng $|\vec{T}_1|$ và $|\vec{T}_3|$ tương ứng và hướng dọc theo các thanh AC và BD; lực hấp dẫn $m_\omega g$ tác dụng lên bản lề; lực $mg$, bằng trọng lượng của tải; lực $\vec{F}$ tác dụng lên bản lề D. Vì hệ ở trạng thái cân bằng nên tổng mômen của tất cả các lực tác dụng lên bản lề bất kỳ phải bằng 0. Hãy viết điều kiện này cho điểm O (xem hình):
$$mg a \sin \alpha + m_\omega g a \sin \alpha = Fa \cos \beta + m_\omega g a \sin \alpha.$$
Từ đây
$$F = \frac{mg \sin \alpha}{\cos \beta} \Rightarrow F_{\min} = mg \sin \alpha = mg/2, \vec{F} \perp [BD].$$

◆
Chúng ta hãy xem xét chuyển động của một quả bóng trong hệ quy chiếu chuyển động với tốc độ $\vec{v}_0$. Trong hệ thống này, quả bóng di chuyển với tốc độ $v_0$. Từ thời điểm tâm quả bóng ở ngay trên mép xe và cho đến thời điểm tâm quả bóng văng ra, nó chuyển động dọc theo một đường tròn bán kính R với tâm là điểm tiếp xúc (trong khi quả bóng không quay quanh tâm của chính nó). Hãy tìm góc α (xem hình) tại thời điểm tách hai vật. Để làm điều này, chúng ta sẽ sử dụng định luật bảo toàn năng lượng và định luật thứ hai của Newton.
Gọi u là vận tốc của tâm quả bóng tại thời điểm tách ra. Sau đó
$$\frac{mu^2}{2} = \frac{mv_0^2}{2} + mgR(1 - \cos \alpha) \quad (m - масса шара)$$

⟦folio 54⟧

(định luật bảo toàn năng lượng),
$$\frac{mu^2}{R} = mg \cos \alpha$$

(Định luật II Newton). Từ (1) và (2) ta tìm được
$$\cos \alpha = \frac{1}{3} \left( \frac{v_0^2}{gR} + 2 \right), u = \sqrt{\frac{1}{3} \left( v_0^2 + 2gR \right)}.$$
Vì $\cos \alpha \leq 1$, rõ ràng ở $v_0^2 \geq gR$ sự phân tách sẽ xảy ra ngay tại thời điểm tâm của quả bóng ở trên điểm cực trị của xe và hình chiếu nằm ngang của tốc độ của quả bóng $u_r$ khi rơi xuống sàn sẽ bằng 0. Nếu $v_0^2 < gR$ thì
$$u_r = v_0 - u \cos \alpha = v_0 - \frac{1}{3Rg} \sqrt{\frac{1}{3} \left( v_0^2 + 2gR \right)^3}.$$
A. R. Zilberman

F815. Đầu dưới của mao quản có bán kính $r=0,2$ mm và chiều dài $l=8$ cm được ngâm trong nước, nhiệt độ của nó không đổi và bằng $0^\circ C$. Nhiệt độ ở đầu trên của mao quản là $t_0=100^\circ C$. Sự phụ thuộc nhiệt độ của hệ số sức căng bề mặt $\sigma(t)$ của nước được cho trong bảng. Nước sẽ dâng lên trong mao mạch đến độ cao nào? Độ dẫn điện của mao quản lớn hơn nhiều so với độ dẫn điện của nước trong đó; trao đổi cơ thể với ảnh hưởng xung quanh có thể được bỏ qua.

◆ Gọi $x$ là chiều cao của cột nước trong mao quản. Nhiệt độ của mao quản và do đó của nước ở độ cao này rõ ràng là
$$t_x = t_0 \frac{x}{l}.$$
Nước trong mao quản được giữ lại nhờ sức căng bề mặt. Nếu $\sigma(t_x)$ là hệ số căng bề mặt ở nhiệt độ $t_x$ thì
$$x = \frac{2\sigma(t_x)}{\varrho g r},$$
trong đó $\varrho$ là mật độ của nước. Từ đây là
$$\sigma(t_x) = \frac{\varrho g r x}{2} = \frac{\varrho g r l t_x}{2 t_0}.$$
Nhiệt độ $t_x$ ở mức nước dâng tối đa

<table><thead><tr><th>$t,^\circ C$</th><th>$\sigma, \frac{\text{mH}}{M}$</th></tr></thead><tbody><tr><td>0</td><td>76</td></tr><tr><td>20</td><td>73</td></tr><tr><td>50</td><td>67</td></tr><tr><td>90</td><td>60</td></tr></tbody></table>

⟦folio 55⟧

F816. Trong mạch như hình vẽ, điện trở của các điện trở bằng nhau và bằng $R = 60$ Ohm thì điốt là lý tưởng. Một cục pin tạo ra điện áp $U = 12$ V sẽ được nối với các điểm $A$ và $B$ trong thời gian $t_1 = 1$ s. Sau đó, đặt dải vào các vị trí, nối pin với mạch điện trong thời gian $t_2 = 5$ s. Tìm nhiệt lượng tỏa ra trong mạch.

Điều kiện bài toán không cho biết dải nào kết nối pin với các điểm $A$ và $B$ trong thời gian $t_1$, vì vậy hãy xem xét hai tùy chọn kết nối khả thi.

1) Đầu tiên, pin “phẳng” được nối với điểm $A$, còn pin “âm” được nối với điểm $B$. Vì các điốt là lý tưởng nên điện trở của chúng bằng 0 và cả ba điện trở được mắc song song với nhau. Tổng điện trở của mạch là $R_1 = R/3 = 20$ ohms. Trong thời gian $t_1$ lượng nhiệt sẽ toả ra trong mạch

$$Q_1 = \frac{U^2}{R_1} t_1 = 7,2 \text{ Дж.}$$

Khi dải được đặt vào các vị trí, không có dòng điện chạy qua điốt và cả ba điện trở đều được mắc nối tiếp. Tổng điện trở của mạch bằng $R_2 = 3R = 180$ Ohm. Trong thời gian $t_2$ lượng nhiệt sẽ toả ra trong mạch

$$Q_2 = \frac{U^2}{R_2} t_2 = 4 \text{ Дж.}$$

Tổng lượng khí thải trong chuỗi nhiệt bằng $Q = Q_1 + Q_2 = 11,2 \text{ Дж.}$.

2) Nếu đầu tiên, điểm trừ của pin được kết nối với điểm $A$ và điểm phẳng của pin được kết nối với điểm $B$, thì

$$Q_1' = \frac{U^2}{3R} t_1 \approx 0,8 \text{ Дж.}$$

$$Q_2' = \frac{3U^2}{R} t_2 \approx 36 \text{ Дж.}$$

$$Q' = Q_1' + Q_2' \approx 36,8 \text{ Дж.}$$

L. II. Bakanina

F817. Hình vẽ thể hiện sự phụ thuộc của chiết suất $n$ vào tọa độ. Một chùm ánh sáng đơn sắc hẹp chiếu vào mặt phân cách giữa môi trường $I$ và $II$. Ánh sáng đi vào môi trường III theo góc nào?

Từ định luật khúc xạ, giá trị $n(x) \cdot \sin \alpha_x$ không đổi dọc theo quỹ đạo của tia (ở đây $\alpha_x$ là góc tới của tia trên mặt phân cách, tương ứng với tọa độ $x$). Vì chiết suất ban đầu giảm trong môi trường thứ hai nên góc tới $\alpha_x$ sẽ tăng khi quỹ đạo tiến đến ranh giới, tương ứng với tọa độ $x_1$. Trong trường hợp này, các tiếp tuyến của đường truyền tia sẽ tiến tới phương thẳng đứng. Nếu góc tới trong môi trường thứ hai đạt $90^\circ$ thì chùm tia sẽ không thoát ra khỏi môi trường này. Nếu góc tới nhỏ hơn $90^\circ$ ngay cả tại ranh giới có tọa độ $x_1$, trong đó giá trị $n(x_1)$ là nhỏ nhất thì chùm tia sẽ chuyển từ môi trường II sang môi trường III.

Giả sử ở một góc tới ban đầu nào đó $\alpha_0$ ($\alpha_0$ là góc tới trên mặt phân cách giữa môi trường $I$ và $II$), góc tới của chùm tia trên ranh giới $x_1$ đạt $90^\circ$. Sau đó

$$n_1 \sin \alpha_0 = n(x_1) \cdot \sin 90^\circ \Rightarrow \sin \alpha_0 = \frac{1,2}{1,4} \approx 0,86, \alpha_0 \approx 60^\circ.$$

Do đó, ở góc $\alpha \geq \alpha_0$, tia sáng sẽ không thể truyền vào môi trường III. Ở góc $0 \leq \alpha < 60^\circ$ một tia sáng truyền vào môi trường III.

V. V. Mozhaev
