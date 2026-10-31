---
id: 1979-7-resheniya-zadach-m517-m519-f526-f530-f532-23c7fbb7
issue: kvant_1979_7
year: 1979
number: "7"
title: Lời giải bài toán M517—M519; F526, F530—F532
rubric: zadachnik-kvanta
rubric_sub: Задачник «Кванта»
page_first: 26
page_last: 34
page_labels: 24, 25, 27, 28, 29, 30, 31, 32
tag: QMC1
lang: vi
source: kvant_digital
extraction: vision
content_sha256: 1fcff185fd2656450d89503305c01d8b23974f9e58eafd92f472d2eb8db6eb6c
prompt_sha256: draft-1
translated_from: content/ru/1979/07/articles/06_resheniya-zadach-m517-m519-f526-f530-f532-23c7fbb7.md
source_content_sha256: 219b2b0def20f0214126e982df2dd2d44bdb0b813dad4673a25478859a4dc994
translation_model: draft
translation_run: vi-draft-2026-10-31
translation_quality: draft
---

⟦folio 24⟧

F587. Một vật dẫn có khối lượng $M$ và chiều dài $l$ được treo vào chất điện môi ở hai đầu của nó bằng hai lò xo không trọng lượng dẫn điện giống hệt nhau có hệ số độ cứng chung $k$. Một tụ điện emkosti $C$ được nối với đầu trên của lò xo. Toàn bộ cấu trúc treo trong một từ trường đều có cảm ứng $\vec{B}$, vuông góc với mặt phẳng tính từ vị trí cân bằng và được thả ra. Xác định chuyển động tiếp theo của dây dẫn trong mặt phẳng thẳng đứng. Bỏ qua điện trở, độ tự cảm và điện dung của dây dẫn. (10)

D. Futorsky

Lời giải bài toán

M517—M519; F526, F530—F532.

Chúng ta cần bổ đề đơn giản sau: cho các hình tam giác $ABC_1$ và $ABC_2$ có đáy chung $[AB]$ có ​​chiều dài $R$; người mẫu

1) nếu các đỉnh $C_1$ và $C_2$ nằm đối diện nhau của $[AB]$ thì

$$S_{ABC_1} + S_{ABC_2} \leq \frac{1}{2} R \cdot |C_1C_2| \quad (\text{рис. 1, a})$$

2) nếu các đỉnh $C_1$ và $C_2$ nằm cùng phía với $[AB]$ thì

$$|S_{ABC_1} - S_{ABC_2}| \leq \frac{1}{2} R \cdot |C_1C_2| \quad (\text{рис. 1, 6})$$

Hãy tự mình chứng minh bổ đề này.

Bây giờ chúng ta hãy chuyển sang lời giải bài toán. Giả sử $A_1A_2 \dots A_n$ là một $n$-giác nội tiếp trong một vòng tròn tâm $O$; $B_1B_2 \dots B_n$ là $n$-gon thứ hai (có đỉnh tại các điểm được đánh dấu), với $B_1 \in [A_1A_2]$, $B_2 \in [A_2A_3]$, v.v.; gọi $P$ là chu vi của nó. Xét các tam giác $OA_1B_1$, $OB_1A_2$, $OA_2B_2$, ..., $OB_nA_1$. Nếu tâm của hình tròn $O$ thuộc đa giác $A_1A_2 \dots A_n$, thì các hình tam giác này không chồng lên nhau theo cặp và sự kết hợp của chúng tạo thành đa giác $A_1A_2 \dots A_n$ (Hình 2), do đó diện tích $S$ của đa giác $A_1A_2 \dots A_n$ bằng tổng diện tích của các hình tam giác này. Theo bổ đề, diện tích của hai tam giác có đáy chung $[OA_k]$ không vượt quá
ý kiến ​​$\frac{1}{2} |OA_k| \cdot |B_{k-1}B_k| = \frac{1}{2} R \cdot |B_{k-1}B_k|$ (chúng tôi tin rằng
tất nhiên là $B_0 = B_n$), vậy nên

$$S = (S_{OB_1A_2} + S_{OA_2B_2}) + \dots + (S_{OB_nA_1} + S_{OA_1B_1}) \leq \frac{1}{2} R (|B_1B_2| + \dots + |B_nB_1|) = \frac{1}{2} RP, \quad (1)$$

từ đâu $P \geq 2S/R$.

Nếu tâm $O$ nằm trong đa giác $A_1A_2 \dots A_n$, chẳng hạn ở các cạnh đối diện của dây cung $A_nA_1$ (Hình 3), thì diện tích của các hình tam giác $OA_nB_n$ và $OB_nA_1$ được bao gồm trong tổng tạo thành diện tích $S$, với dấu trừ:

$$S = (S_{OB_1A_2} + S_{OA_2B_2}) + \dots + (S_{OB_n-1A_n} - S_{OA_nB_n}) + (S_{OA_1B_1} - S_{OB_nA_1}).$$

Áp dụng lại bổ đề, ta thu được bất đẳng thức cần tìm.

⟦folio 25⟧

Để kết luận, chúng tôi lưu ý rằng nếu các cạnh $B_{k-1}B_k$ của đa giác $B_1B_2 \dots B_n$ vuông góc với bán kính tương ứng $OA_k$, thì bất đẳng thức (1) trở thành đẳng thức, sao cho trong trường hợp này đa giác $B_1B_2 \dots B_n$ có chu vi nhỏ nhất có thể có $2S/R$. Chúng tôi mời độc giả sử dụng điều này để chứng minh rằng tam giác $B_1B_2B_3$, nội tiếp một tam giác nhọn $A_1A_2A_3$, có chu vi tối thiểu bằng moeda và molko moreda, khi $B_i$ ($i=1, 2, 3$) là đáy của chiều cao của tam giác $A_1A_2A_3$.

V. Dubrovsky

**Cơm. 3.**

**M518. Các số $x_1, x_2, \dots, x_n$ thuộc đoạn $[a; b]$ và $0 < a < b$. Bằng chứng về sự bất đẳng thức**

$$\left( x_1 + x_2 + \dots + x_n \right) \times \left( \frac{1}{x_1} + \frac{1}{x_2} + \dots + \frac{1}{x_n} \right) \leq \frac{(a+b)^2}{4ab} n^2.$$

**Cơm. 4.**

**Cơm. 5.**

Trước tiên chúng ta hãy phác thảo ý tưởng hình học của một trong những bằng chứng ngắn nhất.

Xét trên mặt phẳng $Oxy$ $n$ các điểm $\left( x_i; \frac{1}{x_i} \right)$, $i = 1, 2, \dots, n$. Những điểm này nằm trên hyperbola $y = \frac{1}{x}$ và theo điều kiện $a \leq x_i \leq b$. Điểm $M^*(x^*; y^*)$ có tọa độ $x^* = \frac{x_1 + x_2 + \dots + x_n}{n}, y^* = \frac{\frac{1}{x_1} + \frac{1}{x_2} + \dots + \frac{1}{x_n}}{n}$ (1)

— trọng tâm $n$ của các điểm vật chất giống hệt nhau $\left( x_i; \frac{1}{x_i} \right)$. Do đó, nó thuộc về một hình lồi được giới hạn bởi hai hyperbol và một đoạn thẳng có các đầu tại các điểm $A\left( a; \frac{1}{a} \right)$ và $B\left( b; \frac{1}{b} \right)$ (Hình 4).

Tích $x^*y^*$ là diện tích của hình chữ nhật được tô bóng trong Hình 4 - giá trị lớn nhất là đủ khi điểm $M^*$ rơi vào giữa đoạn $AB$. Thật vậy, rõ ràng là nếu $(x^*; y^*)$ không nằm trên $[AB]$, thì diện tích có thể tăng lên bằng cách di chuyển điểm $M^*$ lên đoạn $AB$. Và đối với điểm $(x; y)$ của đoạn này $y$ là hàm tuyến tính của $x$, do đó, diện tích $s(x)=xy$ là tam thức bình phương của $x$. Vì $s(x)$ có ​​cùng giá trị ở $x=a$ và $x=b$ $s(a)=s(b)=1$ và $s(0)=0$ (Hình 5), nên đạt được mức tối đa $s(x)$ sau đĩa $x=a$ và $x=b$ - tại $x=\frac{a+b}{2}$, $y=\frac{1}{2}\left(\frac{1}{a}+\frac{1}{b}\right)$.

Do đó $x^*y^* \leq \frac{a+b}{2} \cdot \frac{\frac{1}{a}+\frac{1}{b}}{2} = \frac{(a+b)^2}{4ab}$ là điều cần chứng minh.

Điều duy nhất cần biện minh mang tính toán học hơn là thực tế là “trọng tâm”—điểm có tọa độ (1)—nằm trên cùng một đoạn $AB$. Lưu ý rằng phương trình của đường thẳng $AB$ có dạng $aby+x=a+b$ (kiểm tra xem các điểm $A$ và $B$ có nằm trên đường thẳng này không), vì vậy bước chính của chứng minh của chúng ta là bất đẳng thức

$$aby^*+x^* \leq a+b.$$ (2)

Bây giờ mọi người đã sẵn sàng đưa ra cách chứng minh ngắn gọn (mà chúng ta có thể tự giới hạn): cho mỗi $i$

$$\frac{ab}{x_i} + x_i \leq a+b,$$ (3)

vì $(x-a) (x-b) \leq 0$ là dành cho $x \in [a; b]$. Slu-

⟦folio 27⟧

Nếu $\alpha \in I$ thì cũng $\frac{1}{\alpha} \in I$. Đặt $\gamma > 1$ là phần cuối đúng của đoạn đơn này. Khi đó $\gamma - 1$ là đầu bên trái của nó và phải là $\gamma - 1 = \frac{1}{\gamma}$. Từ đó, chúng ta thấy rằng $\gamma = \frac{\sqrt{5} + 1}{2}$ (con số này được gọi là “phần vàng”). Khoảng cách là $(i, j)$ sao cho $\frac{i}{j} = \alpha \in ]\gamma - 1; \gamma[$ (Hình 6) và $\frac{i}{j} \neq 1$. Giả sử rằng $i > j$; thì $\alpha \in ]\gamma - 1; \gamma[$. Trong tình huống này, người chơi chỉ có một nước đi $(i, j) \rightarrow (i - j, j)$, trong đó

$$\alpha' = \frac{i - j}{j} = \frac{i}{j} - 1 = \alpha - 1 < \gamma - 1,$$

nghĩa là, nước đi đơn lẻ này sẽ dẫn đến một tình huống có quan hệ $\alpha'$ nằm ngoài tích phân $]\gamma - 1; \gamma[$. Ngoài ra, trò chơi không kết thúc ở nước đi này.

Bây giờ đặt $\frac{m}{n} = \alpha \notin ]\gamma - 1; \gamma[$ và $\frac{m}{n} \notin Z$ (trường hợp khi quan hệ $\frac{m}{n}$ là số nguyên được mô tả ở trên); chúng ta hãy đặt, để chắc chắn, $m > n$. Có một $k \in Z$ sao cho $\frac{m}{n} - k \in ]\gamma - 1; \gamma[$, vì vậy sau khi di chuyển $(m, n) \rightarrow (m - kn, n)$, chúng ta nhận được tình huống có tỷ lệ nằm trong tích phân $]\gamma - 1; \gamma[$ và không bằng một (vì $m/n \notin Z$).

Từ đây chúng ta có được chiến lược chiến thắng cho người mới bắt đầu trò chơi. Nếu $\frac{m}{n} \in Z$, thì anh ta thắng ở nước đi đầu tiên. Nếu $\frac{m}{n} \notin Z$ và $\frac{m}{n} \notin ]\gamma - 1; \gamma[$, thì với mỗi nước đi, anh ta sẽ thêm một thuộc tính sao cho mối quan hệ $\frac{m_k}{n_k}$ rơi vào tích phân $]\gamma - 1; \gamma[$, sau đó đối thủ của anh ta có thể thực hiện một nước đi duy nhất, lại dẫn đến tình huống có quan hệ nằm ngoài tích phân đã chỉ định. Rõ ràng là cuối cùng người mới bắt đầu chơi. Trong Hình 7, các chấm đỏ tương ứng với các tình huống thắng $(m, n)$, các chấm đen tương ứng với các tình huống thua.

Do đó, phát biểu 6) bài toán đúng với mọi $\alpha > \gamma$ ($\gamma = \frac{\sqrt{5} + 1}{2}$).

A. Slinko

Với lời giải điều này bài toán, như trường hợp thường xảy ra không chỉ trong toán học cơ bản mà còn trong nghiên cứu toán học trên máy chủ, “đoán” đáp số đã giúp chúng tôi rất nhiều: tại một số điểm, chúng tôi giả định rằng tất cả các điểm không nguyên hữu tỉ của một số tích phân có độ dài đơn vị đều bị mất và sau đó chúng tôi nhanh chóng thêm nghiên cứu vào cuối. Nhưng trong bài toán này, người ta có thể thực hiện mà không cần bước bổ sung như vậy: số $\gamma$ xuất hiện trong đó một cách tự nhiên từ lý do sau. Như đã lưu ý, tất cả các điểm thua đều thuộc về tích phân $]1/2; 2[$. Cũng dễ dàng nói rằng nếu điểm $x \in ]1; 2[$ thua (thắng) thì điểm $x - 1$ là thắng (thua). Do đó, tất cả các điểm của tích phân $]1; 3/2[$ đều bị mất và chúng ta chỉ cần xét các điểm của tích phân $]3/2; 2[$. Giả sử điểm $x \in ]3/2; 2[$ là điểm thua. Khi đó điểm $x - 1$ và $1/(x - 1)$ thắng và $1/(x - 1)$ nhỏ hơn 1.

⟦folio 28⟧

Vì vậy, $1/(x-1)-1=(2-x)/(x-1)$ là điểm thua. Vì vậy, nếu điểm $x \in ]3/2; 2[$ là thua thì điểm $(2-x)/(x-1)$ cũng là điểm thua. Hãy vẽ đồ thị của hàm $(x-1)/(2-x)$ (Hình 8). Hình 8 minh họa cách sử dụng điểm $x$ để tìm điểm $(x-1)/(2-x)$. Trong quá trình biến đổi $x \rightarrow (x-1)/(2-x)$ có một điểm cố định - nghiệm của phương trình $x^2-x-1=0$, thuộc khoảng $]3/2; 2[$ (đây là số $\gamma$). Có thể dễ dàng chứng minh rằng nếu một điểm nằm ở bên phải điểm $\gamma$ thì phép biến đổi và (sự lặp lại) của phép biến đổi của chúng ta sớm hay muộn sẽ đưa nó vượt quá điểm 2. (Một trong những sơ đồ chứng minh khả thi được thể hiện trên Hình 9: tiếp tuyến của góc nghiêng của đường thẳng màu đen đi qua điểm cố định $(\gamma; \gamma^2-\gamma-1)$ bằng 2, và tiếp tuyến của đường cong $(x-1)/(2-x)$ là một vòng tròn - hãy chắc chắn về điều này.)
Do đó, tất cả các điểm từ khoảng $]\gamma; 2[$ đều thắng và do đó, tất cả các điểm từ khoảng $]\gamma; \infty[$ và $0; \gamma^{-1}]$ đều thắng. Tương tự, nếu chúng ta giả định rằng một số điểm trong khoảng $]3/2; \gamma[$ là điểm thắng, thì bằng cách tăng điểm đó, chúng ta sẽ nhận được một điểm từ khoảng $]1; 3/2[$, có nghĩa là tất cả các điểm trong khoảng $]1; \gamma[$ đều là điểm thua. Tất nhiên, lời giải này cồng kềnh hơn. Tuy nhiên, nó cũng tôn trọng hơn!

F526. Đặt các thành cách nhiệt nóng chảy của bình và nhiệt kế được hút chân không đến áp suất $p=10^{-5}$ atm (ở nhiệt độ phòng). Dung tích của bình là 1 lít, diện tích bề mặt của bình là $S=600\text{ cm}^2$. Ước tính thời gian trà ở nhiệt độ tối đa từ $90^\circ\text{C}$ đến $70^\circ\text{C}$. Dung tích nước $c=4,2 \cdot 10^3$ J/(sq.K); hằng số khí phổ quát $R=8,3$ J/(K mol). Tôi biết cách phớt lờ tôi khi tắc đường.

Nhiệt được loại bỏ khỏi thành trong của bình (từ trà) bởi các phân tử khí còn sót lại trong khoang giữa thành trong và thành ngoài của bình. Đây là lý do tại sao họ tắt các bức tường để khí còn lại ở đó không tạo thành môi trường dẫn nhiệt liên tục, nghĩa là để các phân tử di chuyển giữa các bức tường mà không va chạm với nhau.

Chúng ta sẽ giả sử rằng sau khi va chạm với bức tường, phân tử trung bình có năng lượng tỷ lệ thuận với nhiệt độ của bức tường. Sau khi loại bỏ khỏi thành ngoài, động năng của chuyển động tịnh tiến của phân tử là $\varepsilon_1 \sim 3/2$ $kT_K$, trong đó $T_K$ là nhiệt độ phòng; sau khi tháo nó ra khỏi thành trong $\varepsilon_2 \sim 3/2$ $kT'$, trong đó $T'$ là nhiệt độ của trà. Nhiệt độ này luôn thay đổi. Tuy nhiên, sự đảo ngược của thay đổi $T'$ không phải là VELik ($\Delta T=363\text{K} - 343\text{K} = 20\text{K}$). Do đó, để đánh giá, chúng ta có thể giả sử rằng $\varepsilon_1 \sim 3/2$ $kT_C$, trong đó $T_C=353\text{K}$ là giá trị trung bình của nhiệt độ tường nóng.

Do đó, mỗi phân tử khi được tách ra khỏi thành nóng sẽ “lấy” năng lượng từ trà

$$\Delta \varepsilon \sim 3/2 k (T_C - T_K).$$

Số lượng phân tử chứa trong một bức tường nóng trong một đơn vị thời gian tỷ lệ thuận với $1/2 n |v_x| S$, trong đó $n$ là mật độ của các phân tử khí, $|v_x|$ là vận tốc phân tử trung bình của các phân tử trên trục $OX$ vuông góc với bức tường. Số phân tử va vào tường đúng lúc $\Delta t$,

$$N \sim 1/2 n |v_x| S \Delta t.$$

Những phân tử này sẽ lấy năng lượng từ trà

$$\Delta E = N \Delta \varepsilon \sim 3/4 n |v_x| Sk (T_C - T_K) \Delta t.$$

Rõ ràng, năng lượng này bằng độ biến thiên $\Delta U$ của nội năng của trà trong khoảng thời gian $\Delta t$: $\Delta E = \Delta U$. Bởi vì

$$\Delta U = Mc\Delta T,$$

trong đó $\Delta T$ là sự thay đổi nhiệt độ của trà,

$$3/4 n |v_x| Sk (T_C - T_K) \Delta t \sim Mc\Delta T.$$

Từ đây

$$\Delta t \sim \frac{4Mc\Delta T}{3n |v_x| Sk (T_C - T_K)}.$$

⟦folio 29⟧

Giả sử rằng $\sqrt{v_x} \sim \sqrt{RT_K/\mu}$ và tính đến $n = p/k T_K$ (điều này suy ra từ phương trình Mendeleev-Clapeyron), cuối cùng chúng ta tìm thấy:

$$\Delta t \sim \frac{4Mc\Delta T \sqrt{\mu T_K}}{3p(T_c - T_k)S\sqrt{R}}.$$

Thay thế các giá trị số ($M = 1$ kg, $\Delta T = 20$ K, $T_K = 293$ K, $p = 1$ Pa, $\mu = 29.10^{-3}$ kg/mol, v.v.), chúng ta thu được $\Delta t \sim 3.10^4$ với $\sim 10$ h.

A. Stasenko

F530. Trong sơ đồ hiển thị ở Hình 10, $\%_0 > \%_1$. Xác định điện tích mà pin sẽ đọc và điện trở của viên sỏi bằng không. Diode là lý tưởng (điện trở thuận của nó bằng 0, điện trở ngược của nó là vô cùng); Tụ điện không được tích điện trước khi đóng công tắc.

Cơm. 10.

Chúng ta sẽ giả sử rằng diode bắt đầu dẫn dòng điện khi điện thế ở cực dương lớn hơn điện thế ở cực âm. Trong trường hợp này, điện trở của diode sẽ bằng 0 và điện áp rơi trên nó cũng sẽ bằng 0.

Hãy xem xét quá trình xảy ra trong mạch sau khi đóng phím $K$, theo từng giai đoạn.

1. Dòng điện chạy qua cuộn cảm $L$ tích điện cho tụ điện. Ở một giá trị nhất định của dòng điện $I_1$, tụ điện được tích điện đến điện áp $\%_1$. Điện tích của tụ điện $q_1 = C\%_1$, năng lượng của tụ điện $W_1 = C\%_1^2/2$, năng lượng của từ trường của cuộn cảm $LI_1^2/2$. Công mà pin thực hiện lúc này là $A = q_1\%_1$.

2. Mặc dù điện áp trên pin $\%_1$ và trên tụ điện bằng nhau nhưng tụ điện vẫn tiếp tục tích điện - do năng lượng của từ trường của cuộn cảm. Ở một giá trị nhất định của dòng điện $I_0$, tụ điện được tích điện đến điện áp $\%_0$. Điện tích của tụ điện $q_0 = C\%_0$, năng lượng của tụ điện $W_0 = C\%_0^2/2$, năng lượng của từ trường của cuộn cảm $LI_0^2/2$.

Công mà pin thực hiện $\%_1$ trong giai đoạn 1 và 2 là $A_1 = q_0\%_1 = C\%_0\%_1$.

3. Từ thời điểm điện áp trên tụ trở thành $\%_0$, dòng điện bắt đầu chạy qua diode vào pin $\%_0$. Điện áp trên tụ không thay đổi kể từ thời điểm này, năng lượng của nó giữ nguyên bằng $W_0 = C\%_0^2/2$.

Do đó, năng lượng $LI_0^2/2$, có độ tự cảm trong từ trường, bắt đầu giảm - nó thực hiện công chuyển điện tích sang pin $\%_0$.

4. Năng lượng của từ trường của cuộn cảm bằng không. Năng lượng của tụ vẫn là $W_0 = C\%_0^2/2$. Một số lần sạc $Q$ truyền qua pin $\%_0$. Năng lượng pin $\%_0$ tăng $\Delta W = Q\%_0$.

Trong giai đoạn 3 và 4, pin $\%_1$ đã thực hiện công việc $A_2 = Q\%_1$.

Vì vậy, trong toàn bộ quá trình, pin $\%_1$ đã thực hiện công việc sau:

$$A_{\%_1} = A_1 + A_2 = C\%_0\%_1 + Q\%_1.$$

Công việc này chuyển sang truyền năng lượng của $W_0 = C\%_0^2/2$ tới tụ điện $C$ và tăng năng lượng của pin $\%_0$ lên $\Delta W = Q\%_0$. Theo định luật bảo toàn năng lượng

$$A_{\%_1} = W_0 + \Delta W,$$

*) Vì $\sqrt{v_x^2} = \frac{1}{3} \sqrt{v^2} = \frac{1}{3} \frac{3RT_K}{\mu}$ nên $\sqrt{v_x^2} = \sqrt{\frac{RT_K}{\mu}}$.

Mặc dù $\sqrt{v_x^2} \neq |v_x|$, tuy nhiên $\sqrt{v_x^2} \sim \sqrt{v_x^2}$. Do đó, chúng tôi sẽ giả định rằng $\sqrt{v_x^2} \sim \sqrt{\frac{RT_K}{\mu}}$.

⟦folio 30⟧

$$C_0^2 E_1 + Q E_1 = \frac{C_0^2}{2} + Q E_0.$$

Từ đây là $Q$ chảy qua pin $E_0$:

$$Q = \frac{C_0^2 (2 E_1 - E_0)}{2 (E_0 - E_1)}.$$

Và không. Từ kết quả thu được, rõ ràng rằng điện tích sẽ chảy qua pin $E_0$ chỉ khi $E_1 < E_0 < 2 E_1$. Nếu $E_0 > 2 E_1$, thì tụ điện sẽ không tích điện tới điện áp $E_0$. Nói cách khác, điện áp tối đa mà tụ điện có thể được sạc trong mạch như trong Hình 11 là $2 E_0$.

Đặt ở một mức dòng điện $I$ nào đó thì điện áp trên tụ điện là $U$, điện tích của nó là $q = CU$. Từ định luật bảo toàn năng lượng $q E = CU E$ = $\frac{LI^2}{2} + \frac{CU^2}{2}$ tìm được

$$\frac{LI^2}{2} = \frac{CU}{2} (2 E - U).$$

Quá trình nạp tụ sẽ dừng khi dòng điện trong mạch bằng 0. Trong trường hợp này, như có thể thấy, $U = U_{\max} = 2 E$.

V. Skorovarov

F531. Mạch nước phun có thể được coi là các hồ chứa ngầm lớn chứa đầy nước ngầm và được làm nóng bởi bề mặt trái đất (Hình 12). Lối ra từ chúng đến bề mặt trái đất là qua một con kênh hẹp, trong thời kỳ “yên tĩnh” gần như chứa đầy nước. Xem xét rằng thời kỳ “hoạt động” bắt đầu khi chúng ta đổ đầy nước vào hồ chứa dưới lòng đất và trong quá trình phun trào, kênh chứa đầy hơi nước màu trắng đục thoát ra ngoài, chúng ta có thể ước tính phần nước mà hồ chứa nóng lên trong một vụ phun trào một vùng. Độ sâu kênh $h = 90$ m; nhiệt độ nước $\lambda = 2,26 \cdot 10^6$ J/kg; nhiệt độ nước $c = 4,2 \cdot 10^3$ J/(kg K). Sự phụ thuộc của áp suất nước bão hòa vào nhiệt độ được thể hiện trên Hình 13.

Cơm. 12.

Cơm. 13.

⟦folio 31⟧

(M là khối lượng hơi thoát ra) ta tìm được

$$\frac{\Delta M}{M} \approx \frac{c(t-t_0)}{\lambda} \approx 0,15.$$

lời giải đã cho là ước tính vì nó không tính đến một số yếu tố mà trong thực tế có thể thay đổi một chút kết quả thu được. Ví dụ, với lời giải, việc cung cấp nước cho cơ thể từ các tầng nóng trong thời kỳ “hoạt động” không được tính đến, cũng như việc đưa các phần nước mới vào bể chứa thông qua các kênh ngầm trong quá trình phun trào.

S. Kozel

F532. Chất làm mềm là một thanh nhẹ có chiều dài l có tải trọng khối lượng M ở cuối. Gắn vào đầu kia của thanh là một ống lót hình trụ nhẹ a có bán kính trong r đặt trên trục thẳng đứng b (Hình 14). Hệ số ma sát giữa ống lót và trục xe là μ. Xác định góc lệch của thanh so với phương thẳng đứng ở vị trí cân bằng.

Cơm. 14.

Cơm. 15.

Rõ ràng, khi trục b quay ngược chiều kim đồng hồ, tải trọng M dịch chuyển sang bên phải đường thẳng O'O đi qua tâm trục. Trong trường hợp này, điểm A (Hình 15), tại đó ống bọc từ tiếp xúc với trục, được dịch chuyển từ điểm trên cùng của trục theo hướng ngược lại với hướng quay của trục. Hãy thể hiện nó.

Khi một nam châm ở trạng thái cân bằng thì tổng mômen của các lực tác dụng lên nó bằng không. Lực từ bị tác dụng bởi lực hấp dẫn $\vec{P} = \vec{Mg}$ tác dụng lên tải trọng M, phản lực pháp tuyến của trục N và lực ma sát trượt $\vec{F}_{TP}$ tác dụng lên ống lót A. Các mô men của các lực $\vec{N}$ và $\vec{F}_{TP}$ đối với điểm A bằng 0. Do đó, mômen lực $\vec{P}$ đối với điểm này phải bằng 0. Điều này có nghĩa là điểm A phải nằm trên đường tác dụng của lực $\vec{P}$, tức là nó phải dịch chuyển sang phải tính từ điểm trên cùng của trục.

Lưu ý rằng ngay cả với hệ số ma sát μ góc lớn, tải trọng M ở trạng thái cân bằng không thể lệch khỏi phương thẳng đứng O'O một khoảng lớn hơn bán kính r của ống bọc a. Điều này có thể được nhìn thấy từ Hình 15.

Chúng ta hãy tìm góc α xác định vị trí của điểm A. Vì khi nam châm cân bằng, tổng vectơ các lực $\vec{F}_{TP}$ và $\vec{N}$ hướng thẳng đứng lên trên (tổng các lực $\vec{F}_{TP}$, $\vec{N}$ và $\vec{P}$ phải bằng 0), nên

$$\mathrm{tg} \alpha = \frac{F_{TP}}{N} = \frac{\mu N}{N} = \mu$$

($F_{TP}$, N là mô đun của $\vec{F}_{TP}$ và $\vec{N}$).

Bây giờ chúng ta hãy tìm góc φ mà thanh nam châm tạo với O'O thẳng đứng ở vị trí cân bằng. Như có thể thấy từ Hình 15,

$$\sin \varphi = \frac{|OB|}{r+l} = \frac{r \sin \alpha}{r+l}.$$

Xem xét rằng

$$\sin \alpha = \frac{\text{tg} \alpha}{\sqrt{1 + \text{tg}^2 \alpha}} = \frac{\mu}{\sqrt{1 + \mu^2}},$$

chúng tôi tìm thấy (xem (1))

$$\sin \varphi = \frac{r}{r+l} \frac{\mu}{\sqrt{1 + \mu^2}}.$$

Xin lưu ý rằng độ lớn của góc lệch từ chỉ được xác định bởi giá trị của hệ số ma sát và kích thước của thanh và ống lót và không phụ thuộc vào khối lượng của tải trọng M và tốc độ quay của trục.

Trong trường hợp giới hạn μ = 0, công thức (2) cho φ = 0, nghĩa là khi không có khay thì nam châm sẽ ở vị trí thẳng đứng ở trạng thái cân bằng. Với sự gia tăng sức mạnh của tre, đó là

⟦folio 32⟧

là $\mu \rightarrow \infty$, tập hợp $\mu/\sqrt{1+\mu^2}$ tiến tới một và phạm tội $\varphi \rightarrow r/(r+l)$. Điều này có nghĩa là độ lớn độ lệch của tải $M$ sang phải so với phương thẳng đứng $O'O$ (tức là độ dài của đoạn $OB$ trong Hình 15) có xu hướng $r$ (xem (1)).

Điều đáng chú ý là một ma trận như vậy, nếu bị mất cân bằng, sẽ hoạt động không đáng kể. Khi trục quay đủ nhanh, lực ma sát trượt tác dụng lên ống lót theo bất kỳ hướng chuyển động nào của ma trận sẽ hướng về chuyển động quay của trục và chỉ dẫn đến sự dịch chuyển vị trí trung bình một góc $\varphi$ so với phương thẳng đứng.

Lưu ý rằng có thêm một vị trí cân bằng của ma trận trên trục quay - vị trí trong đó tải trọng $M$ nằm phía trên trục và thanh lệch từ phương thẳng đứng sang phải một cùng một góc $\varphi$. Nhưng vị trí cân bằng này, dễ dàng nhận thấy, là không ổn định.

Nếu trục mà ống lót ma trận được lắp được cố định bất động (không quay), thì nhờ lực ma sát tĩnh, giá trị của nó có thể nhận bất kỳ giá trị nào từ 0 đến $\mu N$, ma trận có thể ở trạng thái cân bằng ở bất kỳ vị trí nào lệch khỏi phương thẳng đứng trong phạm vi hình quạt với một góc $\varphi$, được xác định theo cùng một công thức (2). Đây được gọi là vùng trì trệ (Hình 16). Nếu bạn làm chệch hướng matrik một góc lớn hơn giới hạn (lớn hơn $\varphi$) và thả nó ra, thì sau khi thực hiện một phép chia dao động có phần dao động với biên độ, matrik sẽ vẫn ở đâu đó bên trong vùng trì trệ. Việc dừng ma trận có thể xảy ra tại bất kỳ điểm nào trong vùng đình trệ, tùy thuộc vào các điều kiện ban đầu. Thật thú vị khi lưu ý rằng khu vực vị trí cân bằng tương tự cũng tồn tại đối với ma trận “ngược dòng” trên một trục cố định.

E. Butnikov, A. Bykov, A. Kondratov.

(Để bắt đầu, xem trang 20)

S. Guzov (Lviv) 26; V. Jaloyan (làng Urtsadzor, Cộng hòa Xã hội chủ nghĩa Xô viết Armenia) 16, 19a), 21, 24; O. Dimitriev (Saratov) 16a), 21, 23a), 26, 28, 30a); V. Dobrov (Angarsk) 28, 30a); S. Dovbysh (Moscow) 16, 18, 19, 21; E. Dyuzhikova (Arkhangelsk) 16a); I. Elishevich (Chernigov) 21; A. Ermodin (Petrozavodsk) 21, 22, 26, 28, 29; I. Zverovich (Minsk) 16a); E. Zimanov (Alma-Ata) 21, 22, 25; T. Zozrabyan (làng Delaris, Cộng hòa Xã hội chủ nghĩa Xô viết Armenia) 26; M. Ibraemov (Shusha) 16a), 27; P. Ivanov (Villyuysk) 26; O. Izhboldin (Leningrad) 16a), 6), 21-24, 26-30; R. Izmailov (Baku) 16, 18, 19, 21-29; F. Kabdykairov (Alma-Ata) 18, 19a), 21, 26, 28; S. Kaazan (Leningrad) 16, 21; A. Kaazarman (Beloretsk) 26; S. Kalashnikov (Ryazan) 16a), 6); A. Kanel (Moscow) 21, 23, 24, 26, 28, 30a); V. Kanterman (Vilnius) 16a); A. Kaplan (Sumgant) 16, 18, 19a), 21, 22, 24, 26-28, 30a); G. Karadulin (Yerevan) 16, 18, 19a), 21, 22, 24-28, 29a); A. Kelarev (Sverdlovsk) 16, 19, 21, 23, 26-29, 30a); I. Kechov (Sukhumin) 16a); S. Kodan (Leningrad) 28; G. Kokov (Tbilisi) 26; A. Koldatsov (Tbilisi) 26, 28; S. Koleva (NRB) 18; A. Kolmytsev (Angarsk) 30a); Yu. Kordyukov (Moscow) 26, 27, 30a); A. King (Tashkent) 166), 22, 23; S. Kochemov (p/o Druzhba, Lãnh thổ Krasnodar) 21, 24; O. Kravets (Voronezh) 16a), 26-28, 30a); V. Krikukhin (Makhachkala) 26; S. Krilov (Veliky Ustog) 28; I. Krikov (Ivan-

(Tiếp theo trang 43)
