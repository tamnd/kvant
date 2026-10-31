---
id: 1980-2-resheniya-zadach-m551-m556-f563-f567-2a9a4ff0
issue: kvant_1980_2
year: 1980
number: "2"
title: Lời giải bài toán M551—M556; F563—F567
rubric: zadachnik-kvanta
rubric_sub: Задачник «Кванта»
page_first: 38
page_last: 44
page_labels: 36-42
tag: CA2F
lang: vi
source: kvant_digital
extraction: vision
content_sha256: cabec46f8a46bc30c62ffbf55e36b4928246d3e757cc93213aa70cdb4f1c1e00
prompt_sha256: draft-1
translated_from: content/ru/1980/02/articles/14_resheniya-zadach-m551-m556-f563-f567-2a9a4ff0.md
source_content_sha256: 0312f8de6a2f1b5a5f68859734d5eebb70f01dcd02c2a37f461669272aacf94c
translation_model: draft
translation_run: vi-draft-2026-10-31
translation_quality: draft
---

⟦folio 36⟧

Lời giải bài toán

M551. a) Số điểm nhỏ nhất cần đánh dấu bên trong một hình ngũ giác lồi là bao nhiêu để bên trong một tam giác bất kỳ có các đỉnh tại các đỉnh của hình ngũ giác chứa ít nhất một điểm được đánh dấu?
b) Câu hỏi tương tự cho một p-niềm vui lồi.

M552. a) Tìm ít nhất một cặp (p; q) số nguyên khác 0 sao cho các tam giác $x^2+px+q$ và $x^2+qx+p$ có ​​nghiệm nguyên.
b) Tìm tất cả các cặp như vậy (p; q).

Cùng giải quyết ngay nhé bài toán 6). Đáp số. $n-2$.

Rõ ràng là cần phải đặt ít nhất $n-2$ điểm, vì một $n$-giác có thể được cắt thành các hình tam giác $n-2$ và mỗi hình phải chứa một điểm. Hãy trình bày cách sắp xếp các điểm trong $n$-gon $A_0A_1...A_{n-1}$ nếu cần.

Chúng ta hãy đặt điểm $k$ thứ $B_k$ ($k=1, 2,...,n-2$) gần đỉnh $A_k$ bên trong góc $A_0A_kA_n$ (xem hình), chính xác hơn là tại giao điểm của góc này với nửa mặt phẳng giới hạn bởi đường thẳng $A_{k-1}A_{k+1}$ và chứa điểm $A_k$. Rõ ràng là tam giác $A_iA_kA_j$, trong đó $0 \leq i < k < j \leq n-1$, chứa điểm $B_k$: góc $A_iA_kA_j$ chứa góc $A_0A_kA_n$ và đường chéo $A_{k-1}A_{k+1}$ cắt các đoạn $A_iA_k$ và $A_kA_j$.

N. Vasiliev

Chúng ta sẽ giải ngay điểm 6). Gọi $x_1, x_2, y_1, y_2$ lần lượt là căn nguyên của các tam giác $x^2+px+q$ và $x^2+qx+p$. Theo định lý Vieta

$$x_1+x_2=-p, y_1+y_2=-q, x_1x_2=q, y_1y_2=p.$$

Chia tích của hai đẳng thức đầu tiên cho tích của hai đẳng thức còn lại ($pq \neq 0$), chúng ta thu được:

$$\left(\frac{1}{x_1}+\frac{1}{x_2}\right)\left(\frac{1}{y_1}+\frac{1}{y_2}\right)=1.$$

Không mất tính tổng quát, chúng ta có thể giả sử rằng $\left|\frac{1}{x_1}+\frac{1}{x_2}\right| \geq 1$ và $\left|\frac{1}{x_1}\right| \geq \frac{1}{2}$, tức là $|x_1| \leq 2$.

Có hai trường hợp có thể xảy ra: $|x_1|=1$ và $|x_1|=2$.

1°. Hãy để $|x_1|=1$. Khi đó từ bất đẳng thức $\left|\frac{1}{x_1}+\frac{1}{x_2}\right| \geq 1$ ta thu được $|x_2|=n$, trong đó $n \in \mathbb{N}$, $x_1x_2>0$. Từ đây, theo định lý Vieta, đối với tam giác thứ nhất ta thu được $p=\pm(n+1)$, $q=n$. Tam giác $x^2+nx-(n+1)$ có toàn bộ nghiệm cho tất cả $n \in \mathbb{N}$ và tam giác $x^2+nx+n+1$ chỉ có nghiệm nguyên cho $n=5$. Thật vậy, phân biệt của tam giác này $(n-2)^2-8$ phải là một hình vuông hoàn hảo: $(n-2)^2-8=b^2$, tức là $(n-2)^2-b^2=8$; do đó $(n-2-b)(n-2+b)=8$, và $n \in \mathbb{N}$ và $b \in \mathbb{N}$. Đó là lý do tại sao

$$\begin{cases} n-2-b=2 \\ n-2+b=4 \end{cases} \Rightarrow n=5.$$

2°. Hãy để $|x_1|=2$. Khi đó từ bất đẳng thức $\left|\frac{1}{x_1}+\frac{1}{x_2}\right| \geq 1$ suy ra $|x_2| \leq 2$. Trường hợp $|x_2|=1$, theo ký hiệu, là khoảng cách ở trên và trường hợp $|x_2|=2$ dẫn đến tham số $(4,4)$ và $(-4,4)$, tham số thứ hai không phù hợp (đa thức $x^2+4x-4$ không có nghiệm số nguyên).

⟦folio 37⟧

M553. Cho tam giác ABC và $|BC| < |AC| < |AB|$. Trên các mặt trăng BA và CA, các đoạn BD và CE cũng được đặt vào, tức là $|BD| = |CE| = |BC|$. Chứng minh rằng bán kính đường tròn ngoại tiếp tam giác ADE bằng khoảng cách giữa tâm đường tròn ngoại tiếp tam giác ABC và đường tròn ngoại tiếp tam giác ABC.

Gọi $O$ là tâm đường tròn ngoại tiếp tam giác ABC, $O_1$ là tâm đường tròn ngoại tiếp tam giác ADE, $K$ là tâm đường tròn ngoại tiếp tam giác $\triangle ABC$ (xem hình). Chúng ta cần chứng minh rằng $|KO| = |O_1A|$.

Hãy để $|BC| = |BD| = |CE| = a, |AC| = b, |AB| = c$.

Xét một đường tròn có tâm tại điểm $K$ bán kính $|KO|$. Hãy vẽ các hợp âm $[OM] \parallel [AC]$ và $[ON] \parallel [AB]$. Hãy chứng minh rằng các tam giác OMN và ADE có các góc bằng nhau ở đỉnh $O$ và $A$ thì bằng nhau.

Chúng ta thả từ tâm $O$ và $K$ các đường vuông góc $OO'$ và $KK'$ sang một bên $AB(L = [ON] \cap [KK'])$. Thật dễ dàng để kiểm tra điều đó

$$|AK'| = \frac{a+b+c}{2} - a = \frac{b+c-a}{2},$$

$$|O'K'| = |AK'| - |AO'| = \frac{b+c-a}{2} - \frac{c}{2} = \frac{b-a}{2},$$

$$|ON| = 2|OL| = 2|O'K'| = b - a = |AE|.$$

Có thể chứng minh theo cách tương tự rằng $|OM| = |AD|$.

Như vậy, hai tam giác OMN và ADE bằng nhau về hai cạnh và góc xen giữa. Vì vậy $|KO| = |O_1A|$.

S. Người giúp việc

M554. Số tự nhiên $n$ là tốt nếu cũng có các số tự nhiên $a_1, a_2, ..., a_k$ (không nhất thiết phải phân biệt), sao cho

$$a_1 + a_2 + ... + a_k = n$$

Được biết, mọi số từ 33 đến 73 đều tốt. Chứng minh rằng mọi số lớn hơn 73 đều tốt.

Tuyên bố bài toán ngay sau đó từ hai bổ đề:

1°. nếu số $n$ tốt thì $u$ $2n + 2$ là tốt;
2°. nếu số $n$ tốt thì $u$ $2n + 9$ là tốt.

Hãy chứng minh chúng.

Từ đẳng thức

$$n = a_1 + a_2 + ... + a_k,$$

$$\frac{1}{a_1} + \frac{1}{a_2} + ... + \frac{1}{a_k} = 1$$

nên

$$2n + 2 = 2a_1 + 2a_2 + ... + 2a_k + 2,$$

$$\frac{1}{2a_1} + \frac{1}{2a_2} + ... + \frac{1}{2a_k} + \frac{1}{2} = 1$$

— từ đó chứng minh $1^\circ$;

$$2n + 9 = 2a_1 + 2a_2 + ... + 2a_k + 3 + 6,$$

$$\frac{1}{2a_1} + \frac{1}{2a_2} + ... + \frac{1}{2a_k} + \frac{1}{3} + \frac{1}{6} = 1$$

- do đó chứng minh $2^\circ$.

Sử dụng $1^\circ$ và $2^\circ$, quy nạp rất mạnh (bắt đầu bằng $2 \cdot 36 + 2 = 74$ cho số chẵn $n$ và với $2 \cdot 33 + 9 = 75$ cho số lẻ $n$), chúng tôi chứng minh rằng bất kỳ số nào lớn hơn 73 đều tốt, đặc biệt, để kiểm tra tính đúng đắn của tiền đề được thể hiện trong điều kiện. Có thể dễ dàng chứng minh rằng $k^2$ luôn là số tốt và nếu $m$ và $n$ là số tốt thì $mn$ cũng là số tốt.

⟦folio 38⟧

4 = 2²
9 = 3²
10 = 2 • 1 + 8 = 4 • 1 + 6
11 = 3 • 1 + 8 = 6 • 1 + 5
16 = 4²
17 = 2 • 4 + 9 = 4 • 1 + 13
18 = 3 • 4 + 6
20 = 3 • 4 + 8
22 = 4 • 4 + 6
24 = 2 • 11 + 2
25 = 5²
26 = 2 • 9 + 8
27 = 2 • 9 + 9
28 = 2 • 10 + 8
29 = 2 • 10 + 9
30 = 2 • 11 + 8
31 = 2 • 11 + 9
32 = 2 + 3 + 9 + 18
33 = 3 • 9 + 6
34 = 2 • 16 + 2
35 = 3 • 9 + 8
36 = 4 • 9
37 = 2 + 5 + 10 + 10 + 10
38 = 3 • 10 + 8
39 = 3 • 11 + 6
40 = 4 • 10

M555. Khoảng cách giao lộ
a) hai;
b) ba
các hình trụ có cùng bán kính r, các trục của chúng vuông góc với nhau và đi qua một điểm. Giao điểm này có bao nhiêu mặt phẳng đối xứng? Khối lượng của nó là bao nhiêu?

Hình 1.

Hình 2.

Tốt. Ngoài ra, tương tự như cách thực hiện ở 1° và 2°, người ta kiểm tra rằng nếu n tốt thì các giá trị sau cũng tốt: 2n+8(8=4+4), 2n+20(20=4+8+8), 3n+6(6=3+3), 3n+8(8=2+6), 4n+6(6=2+4), 4n+13(13=3+4+6), 6n+5(5=2+3).

Sử dụng điều này, cũng như lựa chọn cách biểu diễn cho các số “không đủ”, dễ dàng chứng minh rằng các số 1, 4, 9, 10, 11, 16, 17, 18, 20, 22 và tất cả các số từ 24 đến 73 đều tốt (những cách chứng minh này sẽ ảnh hưởng đến các công thức ở lề).

Hãy suy nghĩ về cách bạn có thể kiểm tra xem các số 19, 21 và 23 có phải là số tốt hay không. Có lẽ những người trong Trường Tương ứng Lập trình của chúng tôi sẽ thấy hữu ích hơn khi viết một chương trình kiểm tra xem hệ thống có

$$\begin{cases} x_1 + \ldots + x_k = 23, \\ \frac{1}{x_1} + \ldots + \frac{1}{x_k} = 1 \end{cases}$$

lời giải trong số tự nhiên. (Nếu có lời giải thì chương trình phải in ít nhất một lời giải; nếu không, hãy in “0”.) Bạn có thể coi đây là phần bổ sung bài toán cho bài học lập trình tiếp theo; được phép, việc ước tính thời gian vận hành (số chu kỳ) cũng rất hữu ích và đảm bảo rằng thời gian đó càng ngắn càng tốt.

◆

a) Tiết diện cơ thể Ф của chúng ta theo mặt phẳng α₀ đi qua trục của các hình trụ (chúng ta sẽ giả sử rằng α₀ nằm ngang, Hình 1) là một hình vuông có cạnh 2r. Trên thực tế, vật Ф có rất nhiều năm mặt phẳng đối xứng giống như hình vuông Ф∩α₀: đây là mặt phẳng α₀ và bốn mặt phẳng α₀ vuông góc khác đi qua các trục đối xứng của hình vuông. Và tiết diện của vật Ф theo mặt phẳng ngang αₓ nên không có α₀ ở khoảng cách |x| ≤ r, là một hình vuông có cạnh dài $2\sqrt{r^2-x^2}$: mỗi hình trụ giao nhau với mặt phẳng này dọc theo một dải có chiều rộng $2\sqrt{r^2-x^2}$ (Hình 2, 3), và giao điểm của hai dải như vậy với các cạnh vuông góc với nhau sẽ tạo thành một hình vuông (Hình 2). Do đó thể tích của cơ thể chúng ta bằng

$$\int \limits_{-r}^{r} 4(r^2-x^2)dx = 8r^3 - 8r^3/3 = 16r^3/3,$$

Để tìm thể tích của vật F, không cần thiết phải tính tích phân. Chỉ cần lưu ý rằng tiết diện của một quả cầu có bán kính r (tất nhiên có thể treo trong vật Ф) theo mặt phẳng αₓ là một đường tròn có diện tích π(r²-x²). Do đó, tỉ số giữa thể tích cần tìm và thể tích của quả cầu bán kính r bằng 4/π. Do đó thể tích của vật Ф bằng 16r³/3 (thể tích của quả bóng là 4πr³/3).

b) Để tưởng tượng giao điểm Ψ của ba hình trụ, thuận tiện là xây dựng theo cách này: lấy một khối lập phương (có mặt chéo dài 2r, nghĩa là có cạnh r√2) và vẽ một bề mặt hình trụ đi qua bốn cạnh song song (Hình 4). Ψ có chín mặt phẳng đối xứng giống như hình lập phương. Trong các hình lập phương phía trên, ba bề mặt hình trụ sẽ giao nhau, và “phía trên” mỗi mặt sẽ có một culoy có hình dạng giống như phần của vật thể Ф nằm phía trên mặt phẳng α_r√2/2. Thể tích của một mái vòm bằng

$$\int \limits_{r\sqrt{2}/2} 4(r^2-x^2)dx = 4r^3 \left[ \left( 1 - \frac{\sqrt{2}}{2} \right) - \left( \frac{1}{3} - \frac{\sqrt{2}}{3\cdot4} \right) \right] = r^3 (8-5\sqrt{2})/3,$$

⟦folio 39⟧

Các cột vòm là $r^3(16 - 10\sqrt{2})$, hình lập phương $2r^3\sqrt{2}$ nên thể tích của vật chúng ta cần là $(16 - 8\sqrt{2})r^3 \approx 4,69r^3$ (thể tích của một quả cầu có bán kính $r$, tất nhiên có thể nội tiếp trong vật $\Psi$, bằng $4\pi r^3/3 \approx 4,18r^3$).

Bạn cũng có thể tính diện tích bề mặt của cơ thể $\Phi$ và $\Psi$. Để làm điều này, cần lưu ý rằng nếu một dải giấy có chiều rộng $2\pi$ được cuộn thành một ống hình trụ (bán kính 1), hình trụ này được cắt bằng một mặt phẳng nghiêng một góc $\pi/4$ với trục và tờ giấy lại được trải ra trên mặt phẳng thì cạnh của nó sẽ có dạng hình sin. Để tạo mô hình cơ thể bằng giấy $\Phi$, bạn cần lấy bốn “cánh hoa” có diện tích $2r^2\int_0^\pi \sin \varphi d\varphi = 4r^2$ mỗi cánh (Hình 5, a), sao cho tổng diện tích bề mặt của nó là $16r^2$ và một mô hình giấy của cơ thể $\Psi$ có thể được làm từ hai “cánh hoa” có diện tích $4r^2\int_0^\pi \sin \varphi d\varphi = (4-2\sqrt{2})r^2$ mỗi cánh (Hình 5, b), sao cho diện tích bề mặt của cơ thể $\Psi$ bằng $(48-24\sqrt{2})r^2$.

N. Vasiliev

M556. Có cần thiết phải dựng hai tam giác cân có các góc nhọn có cạnh bên bằng nhau và bán kính các đường tròn nội tiếp bằng nhau không?

Đáp số. Nói chung là không nhất thiết.

Đặt tam giác đều $ABC$ (Hình 1) $|AB| = |AC| = 1$, $\widehat{BAC} = 2\alpha$, $O$ là tâm của đường tròn nội tiếp, $r$ là bán kính của nó.

Để tính bán kính, chúng ta sử dụng công thức nổi tiếng $S = rp$, trong đó $S$ là diện tích của tam giác, $p$ là nửa chu vi của tam giác. Trong trường hợp của chúng tôi

$$S = \frac{1}{2} |AB| \cdot |AC| \sin 2\alpha = \frac{1}{2} \sin 2\alpha,$$

$$p = \frac{|AB| + |BC| + |AC|}{2} = 1 + \sin \alpha.$$

Như vậy,

$$r(\alpha) = \frac{S}{p} = \frac{1}{2} \cdot \frac{\sin 2\alpha}{1 + \sin \alpha}.$$

Tam giác $ABC$ theo điều kiện phải nhọn nên ta sẽ quan tâm đến các giá trị $\alpha$ thuộc khoảng $]0; \pi/4[$. Chúng ta cần tìm hiểu xem hàm $r = r(\alpha)$ trên $]0; \pi/4[$ có đơn điệu hay nó nhận một số giá trị nhất định hai lần trong khoảng này.

Chúng ta hãy nghiên cứu hàm $r$ bằng cách sử dụng một hàm tùy ý. Tính toán

⟦folio 40⟧

Lấy đạo hàm, ta được:

$$r'(\alpha) = \frac{1 - \sin \alpha - \sin^2 \alpha}{1 + \sin \alpha}$$

(hãy chắc chắn về điều này). Đánh đồng $r'(\alpha)$ với 0, chúng ta nhận được $\sin^2 \alpha + \sin \alpha - 1 = 0$,

và, vì $\alpha \in [0; \pi/4]$, $\sin \alpha = \frac{\sqrt{5} - 1}{2}$ hoặc $\arcsin \frac{\sqrt{5} - 1}{2} = \alpha_0 \approx 38.2^\circ$.

Dễ dàng nhận thấy rằng $r'(\alpha) > 0$ cho $0 < \alpha < \alpha_0$ và $r'(\alpha) < 0$ cho $\alpha_0 < \alpha < \pi/4$. Do đó, $r$ trả về ở $\alpha \in ]0; \alpha_0[$ và tiêu diệt ở $\alpha \in ]\alpha_0; \pi/4[$, tức là $\alpha_0$ là điểm cực đại của hàm $r$ (đồ thị gần đúng của nó được hiển thị trong Hình 2).

Bây giờ rõ ràng là bên trong khoảng $]0; \pi/4[$ có $a_1$ và $a_2$ mà $r(a_1) = r(a_2)$ (xem Hình 2).

A. Egorov

F563. Ở giữa ống khí áp có một cột không khí. Ở nhiệt độ $t_0 = 0^\circ C$ chiều dài của cột là $t_0 = 10$ cm. Độ dài của cột ở $t = 20^\circ C$ sẽ là bao nhiêu?

F564. Một ô tô di chuyển dọc theo khúc cua trên đường có bán kính $R$. Đột nhiên người lái xe nhìn thấy những người bẩn thỉu trên đường và bắt đầu giảm tốc độ. Ô tô sẽ đi được quãng đường bao nhiêu trước khi dừng lại nếu tốc độ của nó là $v_0$, hệ số ma sát của các bánh xe trên đường là $k$ và ô tô phanh với đội hình lớn nhất có thể?

Áp suất trong cột không khí bằng trọng lượng của cột chất lỏng phía trên không khí chia cho diện tích mặt cắt ngang của ống. Khi nhiệt độ thay đổi, cả chiều cao của cột chất lỏng và mật độ của nó sẽ thay đổi. Nhưng phần còn lại của số dư vẫn giữ nguyên. Trọng lượng của cột sẽ không đổi nên áp suất không khí sẽ không thay đổi. Do đó, tỷ số thể tích của cột không khí ở nhiệt độ $T = 293$ K và $T_0 = 273$ K bằng nhiệt độ tương đối, và do đó,

$$\frac{l}{l_0} = \frac{T}{T_0}.$$

Từ đây

$$l = l_0 \frac{T}{T_0} \approx 10.7 \text{ см.}$$

Ngoại lực duy nhất tác dụng lên ô tô trong mặt phẳng nằm ngang là lực ma sát. Vì bánh xe ô tô không trượt so với mặt đường nên đây là lực ma sát tĩnh. Lực này truyền cho ô tô một gia tốc $\vec{a}$ sao cho mô hình hình chiếu $\vec{a}$ lên bán kính vẽ tới điểm mà ô tô đang đứng bằng gia tốc hướng tâm $a_1 = v^2/R$; mô hình chiếu của $\vec{a}$ lên tiếp tuyến của đường là $a_2 = \sqrt{a^2 - a_1^2}$. Khả năng tăng tốc “tuyến tính” $\vec{a}_2$ giúp giảm tốc độ của xe. Theo điều kiện bài toán $a_2$ giữ nguyên không đổi và lớn nhất có thể. Tại thời điểm phanh $a_2 = \sqrt{a^2 - v_0^4/R^2}$. Giá trị này tối đa là $a = kg$ (giá trị ma sát tĩnh tối đa $kmg$).

Do đó, ô tô giảm tốc độ với gia tốc “tuyến tính” không đổi $a_2 = \sqrt{(kg)^2 - v_0^4/R^2}$. Quãng đường $l$ ô tô đi được đến điểm dừng là bằng

$$l = \frac{v_0^2}{2a_2} = \frac{v_0^2 R}{2 \sqrt{(kgR)^2 - v_0^4}}.$$

⟦folio 41⟧

F565. Hình vẽ được lấy từ công trình của Milliken, cho thấy sự phụ thuộc của điện áp làm chậm vào tần số ánh sáng trong các thí nghiệm sử dụng công thức:

$$hv = A + \frac{mv^2}{2},$$

trong đó $A$ là công năng của electron rời khỏi cực âm và $mv^2/2$ là động năng mà electron phát ra có. Điện áp cực đại giữa cực dương và cực âm mà tại đó electron vẫn có thể chạm tới cực dương là độ trễ

$$hv = A + U_3e.$$

Đối với hai tần số ánh sáng $v_1$ và $v$ chúng ta có thể viết:

$$hv_1 = A + U_{31}e, \quad hv_2 = A + U_{32}e.$$

Trừ đi thứ hai từ đẳng thức đầu tiên, chúng ta nhận được

$$h\Delta v = e\Delta U_3,$$

Ở đâu

$$\frac{h}{e} = \frac{\Delta U_8}{\Delta v}.$$

Xác định các giá trị tương ứng $\Delta U_3$ và $\Delta v$ từ đồ thị, ta thấy:

$$\frac{h}{e} \approx 4.10^{-15} \text{ B}\cdot\text{c}.$$

F566. Một nguyên tử chuyển động với tốc độ $v$ ($v \ll c$) phát ra một photon nghiêng một góc nhỏ a so với hướng chuyển động của nó. Chứng minh rằng nếu $\omega$ là tần số bức xạ của một nguyên tử ở trạng thái nghỉ, và $\omega$ là tần số của photon thì đối với ánh sáng khả kiến ​​$\frac{\omega_0 - \omega}{\omega} \approx \frac{v}{c}$ cos $\alpha$.

Do bức xạ photon, động lượng của nguyên tử, động năng và nội năng của nó thay đổi.

Theo định luật bảo toàn động lượng $mv = mv_1 + \vec{p}_\phi$ ($\vec{mv}_1$ là động lượng của nguyên tử sau bức xạ, $\vec{p}_\phi$ |= $\hbar\omega/c$ là động lượng của photon phát ra), tức là

$$(mv_1)^2 = (mv)^2 + \left(\frac{\hbar\omega}{c}\right)^2 - 2mv \frac{\hbar\omega}{c} \cos \alpha.$$

Theo định luật bảo toàn năng lượng

$$\frac{mv^2}{2} = \frac{mv_1^2}{2} + \hbar\omega + \Delta E$$

($\hbar\omega$ là năng lượng của photon phát ra, $\Delta E$ là độ biến thiên nội năng của nguyên tử).

Sự thay đổi $\Delta E$ nội năng của nguyên tử là sự thay đổi năng lượng của nguyên tử ban đầu đầu tiên sau khi phát ra một photon có năng lượng $\hbar\omega_0$. Sau khi bức xạ, nguyên tử, theo định luật bảo toàn động lượng, thu được động lượng $\vec{m}\vec{u}$ sao cho

⟦folio 42⟧

đó là $m\vec{u} + (\hbar\omega_0/c) = \vec{0}$ và $m\mu = \hbar\omega_0/c$. Vậy độ biến thiên nội năng.atoma, theo định luật bảo toàn năng lượng, bằng

$$\Delta E = - \left[ \hbar\omega_0 + \frac{(\hbar\omega_0)^2}{2mc^2} \right] = - \hbar\omega_0 \left( 1 + \frac{\hbar\omega_0}{2mc^2} \right)$$

($\Delta E < 0$, vì nguyên tử năng lượng bên trong đã giảm).

Thay giá trị $\Delta E$ vào (2) và loại trừ $v_1$ khỏi (1) và (2), chúng ta thu được:

$$\omega \left( 1 + \frac{\hbar\omega}{2mc^2} - \frac{v}{c} \cos \alpha \right) = \omega_0 \left( 1 + \frac{\hbar\omega_0}{2mc^2} \right).$$

Ở các tần số tương đối nhỏ $\omega$ và $\omega_0$ (theo thứ tự quang học), các giá trị $\hbar\omega/2mc^2$ và $\hbar\omega_0/2mc^2$ nhỏ hơn nhiều so với đơn vị. Bỏ qua các đại lượng này, từ (3) ta tìm được ở các góc nhỏ $\alpha$ (khi $\cos \alpha \approx 1$)

$$\frac{\omega - \omega_0}{\omega} \approx \frac{v}{c}.$$

F567. Hình 1 cho thấy sự phụ thuộc của dòng điện qua bóng đèn tự động vào điện áp trên nó. Bóng đèn được mắc vào mạch điện như hình 2. Tìm công suất do bóng đèn tỏa ra.

Để tìm công suất phát ra từ bóng đèn, bạn cần xác định điện áp đặt trên bóng đèn và cường độ dòng điện chạy qua nó.

Nếu điện áp chạy qua bóng đèn và chạy qua điện trở có điện trở $R_2$ là $U$ thì chạy qua điện trở có điện trở $R_1$ thì điện áp chạy qua $U - U$. Dòng điện chạy qua $R_1$ là $I_1 = (\mathcal{E} - U)/R_1$; dòng điện chạy qua $R_2$ bằng $I_2 = U/R_2$. Do đó, dòng điện chạy qua bóng đèn với hiệu điện thế $U$ bằng

$$I = I_1 - I_2 = \frac{\mathcal{E} - U}{R_1} - \frac{U}{R_2} = \frac{\mathcal{E}}{R_1} - U \left( \frac{1}{R_1} + \frac{1}{R_2} \right).$$

Bóng đèn chỉ sáng nếu các giá trị $U$ và $I$, quan hệ liên quan (*), tương ứng với một điểm trên đặc tính vôn kế của bóng đèn. Các giá trị này xác định điểm giao nhau của đồ thị của hàm $I = 5 - \frac{5}{6} U$ (chúng tôi đã thay thế các giá trị số trong (*)) bằng đặc tính vôn kế của bóng đèn. Sau khi xây dựng biểu đồ (xem Hình 1), chúng ta thấy: $U \approx 4,8$ B, $I \approx 1$ A.

Vậy công suất phát ra của bóng đèn là

$$P = IU \approx 4,8 \text{ Вт.}$$

I. Tiếng Slovodechkiy
