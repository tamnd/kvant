---
id: 1989-10-resheniya-zadach-m1161-m1164-f1173-f1177-91d1db8b
issue: kvant_1989_10
year: 1989
number: "10"
title: Lời giải bài toán M1161—M1164; F1173—F1177
rubric: zadachnik-kvanta
rubric_sub: Задачник «Кванта»
page_first: 32
page_last: 38
page_labels: 30-36
tag: 89L0
lang: vi
source: kvant_digital
extraction: vision
content_sha256: 1273ffbac3675b8d491f4669da028b671aeb9f6caccba46fb3ff71ed9c76bb00
prompt_sha256: draft-1
translated_from: content/ru/1989/10/articles/07_resheniya-zadach-m1161-m1164-f1173-f1177-91d1db8b.md
source_content_sha256: 465cf1b8b2b906668af6606ceadee59801b63e1bf26c142f4669fbf59cb3f3dc
translation_model: draft
translation_run: vi-draft-2026-10-31
translation_quality: draft
---

⟦folio 30⟧

Lời giải bài toán
M1161 — M1164, F1173 — F1177

M1161. Trong hầu hết các trường hợp, 10 quả bóng được thực hiện. Chứng minh rằng nếu đặt 9 quả bóng vào đó thì chắc chắn sẽ có chỗ cho quả thứ mười (tức là tâm của 9 quả bóng sẽ nằm trên một lưới tam giác).

Lấy đường kính của quả bóng bằng 1. Bài toán tương đương như sau: Chứng minh rằng nếu 9 điểm $K_1, K_2, ..., K_9$, khoảng cách theo cặp giữa chúng ít nhất bằng 1, đặt trong một tam giác đều cạnh 3 thì chúng nhất thiết phải nằm ở các đỉnh của một mạng tam giác có cạnh 1 (trong 9 trên 10 điểm đen trên hình). Đủ để chứng minh rằng 6 (hoặc 7) điểm $K_i$ nằm trong hình lục giác màu đỏ và chúng nhất thiết phải nằm ở các đỉnh hoặc ở tâm của nó $O$ - xét cho cùng, trong mỗi tam giác góc có cạnh 1 (không phải ở cạnh màu đỏ) chỉ có thể có một trong các điểm $K_i$, và nếu có một điểm khác $K_j$ ở cạnh màu đỏ của nó, thì $K_i$ nằm ở đỉnh của tam giác lớn.

Rõ ràng là nếu một trong 6 điểm $K_i$ bên trong hình lục giác trùng với $O$ thì các điểm còn lại nằm ở các đỉnh. Nếu tất cả chúng đều khác với $O$, thì các đoạn $OK_i$ được vẽ tại các điểm này sẽ tạo thành các góc $60^\circ$ với nhau (nếu $\angle K_iOK_j < 60^\circ$, $OK_i \leq 1$, $OK_j \leq 1$, thì $K_iK_j < 1$) và $OK_i = 1$.

Rõ ràng, thực tế sau đây cũng đúng: nếu bạn loại bỏ một quả bóng khỏi 1+2+...+$n=n(n+1)/2$ quả bóng được đặt gần trong một hộp hình tam giác, thì phần còn lại nhất thiết sẽ nằm trong một lưới tam giác - vì vậy quả bóng đã bị loại bỏ có thể được đặt lại vào vị trí cũ.

N. P. Dolbin

M1162. Tìm tất cả các phương trình số nguyên lời giải
$$x^3 - 13x \cdot y + y^3 = 13.$$

Hãy giới thiệu các biến mới $s = x + y$ và $t = xy$. Khi đó phương trình sẽ có dạng $s^3 - 3st - 13t = 13$, hoặc
$$t = \frac{s^3 - 13}{3s + 13},$$
(*)

và do đó
$$27t = \frac{27s^3 - 13 \cdot 27}{3s + 13} = 9s^2 - 39s + 169 - \frac{13^3 + 13 \cdot 27}{3s + 13}.$$

Từ đây ta suy ra rằng số 3s+13 phải là ước của số 2548=13·196. Hơn nữa, vì $s^2 - 4t = (x - y)^2 \geq 0$, nên
$$s^2 - 4 \frac{s^3 - 13}{3s + 13} = \frac{3s^3 + 13s^2 - 4s^3 + 52}{3s + 13} \geq 0$$
và, do đó,
$$\frac{s^2(13 - s) + 52}{3s + 13} \geq 0.$$

Do đó, chúng ta có $s \leq 13$ và $s \geq -4$ (nếu không thì giá trị của phân số là âm). Do đó, 3s+13 nằm trong khoảng 1 khi chia cho 3. Số 2548 = 2 2 7 7 13 có bảy ước như vậy: 1, 4, 7,

⟦folio 31⟧

13, 28, 49, 52. Chúng lần lượt cho các giá trị của $s$: $-4, -3, -2, 0, 5, 12, 13$ và các giá trị của $t$ (từ phương trình (*)): $-77, -10, -3, -1, 4, 35, 42$. Giải quyết từng cặp hệ thống này

$$\begin{cases} x+y=s, \\ xy=t \end{cases}$$

- để làm điều này, chỉ cần tìm nghiệm của phương trình bậc hai $z^2-sz+t=0$, - chúng ta có 7 cặp lời giải (7; 5), (7; 6), (7; -11), (1; -3), (1; -1), (1; 4), (-5; 2). Đương nhiên, tôi sẽ chỉ ra tính đối xứng của phương trình ban đầu đối với $x$ và $y$ các số theo cặp có thể hoán đổi cho nhau, sao cho phương trình có tổng cộng 14 lời giải. Nhìn chung, dễ dàng nhận thấy phương trình $x^3-kxy+y^3=m$ đối với số nguyên $k$, $m$ có số hữu hạn lời giải trong số nguyên nếu $k^3+27m \neq 0$. Lưu ý rằng phương trình

$$x^3-kxy+y^3=k$$

luôn có tiêu chuẩn lời giải (1; -1) và nếu $k=2p+1$ thì cũng có lời giải $(p; p+1)$. Tuy nhiên, theo một số nghĩa, hệ số $k=13$ gần như "duy nhất": tất cả các giá trị hợp lệ của $s$ (được ánh xạ bởi bất đẳng thức $s^2-4t \geq 0$) dẫn đến phương trình bậc hai có số nguyên lời giải. Người ta có thể nhận thấy một thuộc tính tương đối đơn giản khác của phương trình (***), có thể được tìm thấy trong ví dụ này: nếu $(a; b)$ và $(a; c)$ - lời giải của một phương trình đã cho, thì cặp $(a; -b-c)$ - lời giải của phương trình này (điều này dễ dàng suy ra từ định lý Vieta).

D. V. Fomin

M1163. Cherenakha rời điểm $A$ và đến điểm $B$, di chuyển theo một quỹ đạo tùy ý với tốc độ tùy ý. Theo sau nó, một Cherenakh thứ hai xuất hiện từ điểm $A$, tại mỗi thời điểm, điểm này di chuyển theo hướng của chiếc lông vũ (với tốc độ tùy ý) và cuối cùng cũng đến điểm $B$. Chứng minh rằng let, bị cuống thứ hai ăn (vào thời điểm cả hai đều đạt $B$), không vượt quá đường đi của chiếc lông vũ.

Giả sử tại thời điểm $t$ Cherenakh thứ nhất đã đi qua con đường $L(t)$, Cherenakh thứ hai - $P(t)$ và khoảng cách giữa chúng tại thời điểm này là $D(t)$. Hãy để chúng tôi chứng minh rằng theo thời gian số lượng

$$f(t)=L(t)-P(t)-D(t)$$

không giết, tức là $f(t) \geq f(t')$ với $t > t'$. Từ đây, tuyên bố bài toán sẽ tuân theo: để con cherenach thứ nhất bắt đầu chuyển động ở $t=0$, và con thứ 2 kết thúc ở $t=T$, sau đó là $f(0)=0$, $D(T)=0$ và nếu $f(T)=L(T)-P(T) \geq f(0)$ thì $L(T) \geq P(T)$.

Phát biểu chính về $f(t)$ có thể được chứng minh theo nhiều cách khác nhau. (Ví dụ: sử dụng một quỹ đạo tùy ý.) Khó khăn bắt nguồn từ thực tế là trong bài toán nó quyết định về quỹ đạo tùy ý và tốc độ tùy ý. Chúng ta sẽ giải quyết khó khăn này bằng cách này: chúng ta sẽ thay thế quỹ đạo của cành giâm bằng các đường đứt quãng gần chúng.

Đặt $M_i$ là vị trí của cherenach thứ nhất tại thời điểm $t_i=i\tau$, $\tau=T/n$ ($i=0, 1, ..., n$; $M_0=A$, $M_n=B$); $u_i$ là tốc độ của Cherenakh thứ 2 tại thời điểm $t_i$. Giả sử rằng Cherenakh thứ nhất trong khoảng thời gian giữa $t_i$ và $t_{i+1}$ đi qua đoạn $M_iM_{i+1}$ và lần thứ 2 đi qua đoạn $N_iN_{i+1}$ có độ dài $u_i\tau$, hướng đến điểm $M_i$ (hình 1;

⟦folio 32⟧

Chúng tôi tin rằng $u_0 = 0$, $N_0 = N_1 = A$; nếu $u_i \tau \geq M_i N_i$ thì $N_{i+1} = M_i$). Giả sử trong quá trình chuyển động này dọc theo các đường đứt đoạn tại thời điểm $t_i$ các đường $L^*(t_i)$, $P^*(t_i)$ đã đi qua và ở khoảng cách $D^*(t_i)$ với nhau. (Trên mỗi khoảng $[t_i, t_{i+1}]$, chúng tôi coi các hàm này là tuyến tính.) Hãy đặt $f^*(t) = L^*(t) - P^*(t) - D^*(t)$. Bởi vì (xem hình 2)

$$D^*(t_i) = N_i M_i, L^*(t_{i+1}) = L^*(t_i) + M_i M_{i+1},$$
$$P^*(t_{i+1}) = P^*(t_i) + N_i N_{i+1}, D^*(t_{i+1}) = N_{i+1} M_{i+1},$$

chúng tôi nhận được

$$f^*(t_{i+1}) - f^*(t_i) = M_i M_{i+1} - N_i N_{i+1} + M_{i+1} N_{i+1} - N_i M_i = N_{i+1} M_i + M_i M_{i+1} - N_{i+1} M_{i+1} \geq 0.$$

Vì vậy, hàm số $f^*(t)$ không giảm. Theo đó, $f(t)$ không giảm: đối với $n$ đủ lớn, các đường gãy $M_0 M_1 \dots M_n$ và $N_0 N_1 \dots N_n$ sẽ càng gần quỹ đạo càng tốt và hàm $L^*$, $P^*$ và $D^*$, $f^*$ - tương ứng với các hàm $L$, $P$, $D$ và $f$, và nếu kết quả là $f(t) > f(t')$ đối với một số $t > t'$, thì nó phải là $f(t_{i+1}) > f(t_i)$ đối với một số $i$ (đối với $n$ đủ lớn).

S. Yu. Orvekov, A. Kh. Thần

**M1164. Số tự nhiên $n$ được gọi là số hoàn hảo nếu nó bằng tổng các ước của nó nhỏ hơn $n$ (ví dụ: $28 = 1 + 2 + 4 + 7 + 14$). Chứng minh rằng một số hoàn hảo lẻ (nếu tồn tại) không thể chia hết cho 3, 5 và 7 cùng một lúc.**

Gọi $n = p_1^{k_1} \dots p_r^{k_r}$ là phân tích của số $n$ thành thừa số nguyên tố. Khi đó tổng $S(n)$ các ước của nó, bao gồm 1 và $n$, bằng $(1 + p_1 + \dots + p_1^{k_1})(1 + p_2 + \dots + p_2^{k_2}) \dots (1 + p_r + \dots + p_r^{k_r})$. (*)

Vì $n$ là hoàn hảo, $S(n) - n = n$, tức là $S(n) = 2n$. Nếu $n$ và tất cả các thừa số nguyên tố $p_1, p_2, \dots, p_r$ của nó là số lẻ thì trong tích (*) một trong các tổng trong ngoặc là số chẵn và các tổng còn lại là số lẻ. Đặt $k_1 = 2m + 1$, sau đó

$$1 + p_1 + \dots + p_1^{2m + 1} = (1 + p_1)(1 + p_1^2 + \dots + p_1^{2m}).$$

$p_1 \neq 3$ và $p_1 \neq 7$ (nếu không thì $S(n)$ chia hết cho 4). Nếu số trung bình $p_1, p_2, p_3, \dots, p_r$ xảy ra là 3, 5 và 7 và $p_1$ khác với 3 và 7 thì

$$\frac{S(n)}{n} \geq \left(1 + \frac{1}{p_1}\right)\left(1 + \frac{1}{p_2} + \frac{1}{p_2^2}\right) \dots \left(1 + \frac{1}{p_r} + \frac{1}{p_r^2}\right) \geq$$

$$\geq \left(1 + \frac{1}{5}\right)\left(1 + \frac{1}{3} + \frac{1}{9}\right)\left(1 + \frac{1}{7} + \frac{1}{49}\right) =$$

$$= \frac{6 \cdot 13 \cdot 57}{5 \cdot 9 \cdot 49} > 2.$$

Điều này mâu thuẫn với đẳng thức $S(n) = 2n$.

V. V. Shabunin

**F1173. Chiều dài không đều, bao gồm một số lượng lớn va-**

Khi bạn đi vào “vòng chết”, tốc độ của tàu giảm dần. Nó đạt giá trị thấp nhất $v$, khi “vòng lặp” được lấp đầy hoàn toàn với thành phần (và sau đó

⟦folio 33⟧

onov, lao với tốc độ không đổi dọc theo đường ray nằm ngang, rồi hú vào một “vòng chết” (hình 1). Chiều dài tàu L, bán kính vòng R (R lớn hơn đáng kể so với kích thước của toa xe, nhưng L>2πR). Nó sẽ di chuyển với tốc độ ban đầu là bao nhiêu và vượt qua quá trình chuyển đổi để trong quá trình chuyển động không có một ô tô nào dừng lại trên đường ray?

Hình 1.

Hình 2.

Hình 3.

sẽ không thay đổi). Chúng ta hãy viết định luật bảo toàn năng lượng cho khoảnh khắc này và những khoảnh khắc ban đầu:

$$\frac{Mv_0^2}{2} = \frac{Mv^2}{2} + \left( M \frac{2\pi R}{L} \right) gR,$$

(1)

Trong đó M là khối lượng của toàn bộ đoàn tàu, v₀ là tốc độ ban đầu của nó, M(2πR/L) là khối lượng của các toa tàu nằm trong “vòng”, R là chiều cao khối tâm của chúng.

Khi ô tô tiếp xúc với đường ray thì có một phản lực từ phía bên của đường ray tác dụng lên ô tô. Điểm cao nhất của “vòng” tương ứng với lực phản ứng thấp nhất. Trong trường hợp giới hạn, phản lực bằng không. Trong trường hợp này, rơ moóc (hình 2) chịu tác dụng của lực hấp dẫn mg (m là khối lượng của rơ moóc) và lực căng T từ khớp nối với hai rơ moóc liền kề. Hợp lực của các lực này hướng thẳng đứng xuống dưới và truyền cho xe một gia tốc hướng tâm cần thiết v2/R:

$$2T(\alpha/2) + mg = mv^2/R.$$

Ở đây, chúng tôi đã dạy về độ nhỏ của góc α=l/R, tại đó có thể nhìn thấy một vận chuyển có chiều dài l từ tâm của “vòng chết” và thay thế sin của góc nhỏ bằng một góc đối xứng. Cũng lưu ý rằng m=(l/L)M=(αR/L)M (nếu chúng ta bỏ qua khoảng cách giữa các xe). Khi đó phương trình trước có thể được viết là

$$T + \frac{R}{L}Mg = M\frac{v^2}{L}.$$

(2)

Bây giờ chúng ta hãy tìm lực căng T. Hãy xem phần đoàn tàu đi vào “vòng chết” (hình 3). Đặt thành phần của máy trộn trong một khoảng cách nhỏ là Δx thì lực T đã thực hiện công A=TΔx. Nhưng vì tốc độ của đoàn tàu không thay đổi nên công này phải bằng độ biến thiên thế năng của một đoạn đoàn tàu có chiều dài Δx và khối lượng Δm=(M/L)Δx, tăng lên độ cao 2R (xem hình 3). Vì thế,

$$T\Delta x = 2\frac{M}{L}\Delta xRg,$$

và T = \frac{2MRg}{L}.

(3)

Kết hợp các đẳng thức (1) - (3) trong hệ ta tìm được vận tốc ban đầu của đoàn tàu:

$$v_0 = \sqrt{Rg(3+4\pi R/L)}.$$

A. I. Buzdin

F1174. Trong một khối nước sốt có thể tích V = 1 lít có m = 0,01 g nguyên chất ở nhiệt độ T = 300 K. Hãy quan sát một trong các phân tử. Bao nhiêu lần nó sẽ chạm vào thành trên của nước sốt trong thời gian t=1 phút?

Nếu thời gian được chỉ định trong nhiệm vụ đủ dài (cần kiểm tra điều này), thì tất cả các phân tử sẽ va chạm với thành nước sốt đã chọn với tần suất như nhau. Khi đó số lần truy cập cần thiết

$$n_{уд} = \frac{n_{уд обш}}{N},$$

trong đó n_{tổng số nhịp} là tổng số lần chạm vào tường, N là số lượng phân tử trong nước sốt.

⟦folio 34⟧

Để ước tính $n_{yd}$ chúng ta tiến hành như sau. Chúng ta hãy biểu thị diện tích bức tường bằng $S$ ($S=(\sqrt[3]{V})^2$) và nồng độ phân tử bằng $n$ ($n=N/V$). Rõ ràng là theo thời gian $t$ tất cả những phân tử nằm cách nó một khoảng $\bar{v}_x t$ sẽ va vào tường ($\bar{v}_x$ là giá trị trung bình của các phân tử tương ứng với các thành phần vận tốc) và di chuyển về phía tường, tức là.

$$n_{yd} = \frac{1}{2} n \bar{v}_x t S.$$

Bây giờ hãy đánh giá $\bar{v}_x$:

$$\bar{v}_x = \sqrt{\bar{v}_x^2} = \sqrt{\frac{1}{3} v^2} = \sqrt{\frac{RT}{M}},$$

trong đó $R=8,31$ J/(mol K) là hằng số khí phổ quát, $M=4 \cdot 10^{-3}$ kg/mol là khối lượng mol của helium.

Vì vậy, cuối cùng chúng tôi nhận được

$$n_{yd} = \frac{n \bar{v}_x t S}{2N} = \frac{1}{2V} \sqrt{\frac{RT}{M}} t V^{2/3} = \frac{\sqrt{RT/M} t}{2V^{1/3}} \approx 2,5 \cdot 10^5.$$

Nói cách khác, nếu không tính đến các phân tử va chạm với nhau thì $n_{yd} = (v_x t)/(2a)$, trong đó $2a=2V^{1/3}$ là đường đi của phân tử “từ trần này đến trần khác”.

Bây giờ chúng ta cần chứng minh mô hình đã chọn. Để làm điều này, hãy ước tính chiều dài tự do của một phân tử, tức là khoảng cách trung bình mà một phân tử di chuyển giữa hai lần va chạm với các phân tử khác:

$$\lambda \approx \frac{V/N}{\pi d^2} = \frac{1}{\pi d^2 n},$$

trong đó $d \sim 10^{-10}$ m là đường kính của các phân tử. Trong điều kiện bình thường, 1 m$^3$ chất khí bất kỳ đều chứa $\approx 2,7 \cdot 10^{25}$ phân tử. Do đó, $\lambda \approx 10^{-6}$ m và độ dịch chuyển trung bình của một phân tử trong thời gian $t$ bằng

$$\bar{x} = \sqrt{\lambda v_x t} \approx 1 \text{ м},$$

lớn hơn đáng kể so với kích thước của tàu. Điều này có nghĩa là việc khuấy trộn thực sự có hiệu quả “làm đồng đều” các phân tử.

A. R. Zilberman

F1175. UFO bay trên Trái đất với tốc độ không đổi, rất cao $v$. Tốc độ nào sẽ được ghi lại bởi các mẫu mặt đất của trạm theo dõi tại thời điểm hướng tới vật thể tạo một góc $\varphi$ với phương thẳng đứng (hình 1)?

Giả sử thời gian $t$ trôi qua từ lúc UFO bay gần đến điểm quan sát $A$ (hình 2) đến thời điểm này (đến điểm $B$), và thời điểm này vắng mặt theo đồng hồ cố định, chúng ta đang ở điểm $B$. Chúng ta hãy biểu thị độ cao của UFO trên Trái đất bằng $l$. Khi đó đường đi của vật từ $A$ đến $B$ là

$$vt = l \ tg \ \varphi.$$

Quan sát và nhìn thấy một vật phát sáng tại điểm $B$ muộn hơn một chút (do tốc độ truyền ánh sáng $c$) và đồng hồ của nó sẽ hiển thị thời gian

⟦folio 35⟧

F1176. Các điện tích +Q và –Q có khối lượng M được gắn vào một chùm không trọng lượng có chiều dài 2L, có thể quay không ma sát quanh một trục thẳng đứng. Dưới ách, dọc theo phần tiếp theo của trục quay, có một lưỡng cực nhỏ - điện tích +q và -q cách nhau 2a (a≪L). Tại thời điểm ban đầu ách ở trạng thái cân bằng ổn định (hình 1).
a) Lưỡng cực gây ra chuyển động quay với vận tốc góc ω. Tại thời điểm ω nào thì chùm tia sẽ “đồng hành” với chuyển động quay của lưỡng cực?
b) Dipole đứng yên. Đối với những khoảng thời gian dao động nhỏ này, thiết bị lái.

$$t_1 = t + \frac{l/\cos \varphi}{c}.$$

(2)

Rõ ràng, tốc độ của UFO thay đổi vật thể quan sát được bằng

$$v_1 = \frac{dx}{dt_1} = \frac{dx}{dt} \frac{dt}{dt_1} = \frac{v}{dt_1}.$$

Từ sự bình đẳng (2)

$$\frac{dt_1}{dt} = 1 + \frac{l \sin \varphi}{c \cos^2 \varphi} \frac{d\varphi}{dt},$$

và từ sự bình đẳng (1)

$$\frac{d\varphi}{dt} = \frac{v \cos^2 \varphi}{l},$$

Có thể tốc độ tìm kiếm cuối cùng bằng

$$v_1 = \frac{v}{1 + \frac{v}{c} \sin \varphi}.$$

S. S. Krotov

F1176. Các điện tích +Q và –Q có khối lượng M được gắn vào một chùm không trọng lượng có chiều dài 2L, có thể quay không ma sát quanh một trục thẳng đứng. Dưới ách, dọc theo phần tiếp theo của trục quay, có một lưỡng cực nhỏ - điện tích +q và -q cách nhau 2a (a≪L). Tại thời điểm ban đầu ách ở trạng thái cân bằng ổn định (hình 1).
a) Lưỡng cực gây ra chuyển động quay với vận tốc góc ω. Tại thời điểm ω nào thì chùm tia sẽ “đồng hành” với chuyển động quay của lưỡng cực?
b) Dipole đứng yên. Đối với những khoảng thời gian dao động nhỏ này, thiết bị lái.

a) Hãy chuyển sang hệ thống báo cáo phi quán tính gắn với điôp. Trong hệ này, gông tại thời điểm ban đầu quay với vận tốc góc ω. Nó sẽ “đồng hành cùng” dioplom nếu năng lượng của nó không đủ để thực hiện một cuộc cách mạng hoàn chỉnh. Nói cách khác, nếu năng lượng ban đầu của nó nhỏ hơn năng lượng ở điểm bất lợi nhất:

$$2 \frac{M(L\omega)^2}{2} + 2 \left( -\frac{Qq}{4\varepsilon_0(L-a)} + \frac{Qq}{4\varepsilon_0(L+a)} \right) < \quad < 2 \left( -\frac{Qq}{4\varepsilon_0(L+a)} + \frac{Qq}{4\varepsilon_0(L-a)} \right).$$

Kết quả là chúng tôi nhận được

$$\frac{M(L\omega)^2}{2} < 2 \frac{Qq}{4\varepsilon_0} \left( \frac{1}{L-a} - \frac{1}{L+a} \right) = 2 \frac{Qq}{4\varepsilon_0} \frac{2a}{L^2-a^2} \approx \frac{Qqa}{\varepsilon_0 L^2},$$

Ở đâu

$$\omega < \frac{1}{L} \sqrt{\frac{2Qqa}{\varepsilon_0 M}}.$$

6) Chúng ta hãy đặt khoảng cách giữa độ lệch của ách với vị trí cân bằng một góc nhỏ α (hình 2). Mỗi điện tích của chùm tia chịu tác dụng của lực từ mỗi điện tích của lưỡng cực. Vì L≪α, chúng ta có thể giả sử rằng mô đun của tất cả các lực đều giống nhau và bằng F=Qq/(4\varepsilon_0 L^2), và vai của chúng bằng αα. Chúng ta hãy viết phương trình chuyển động của tay lái (một phương trình tương tự như định luật thứ hai của Newton về chuyển động tịnh tiến của một vật):

$$2ML^2\alpha'' = -4 \frac{Qq}{4\varepsilon_0 L^2} \alpha\alpha,$$

⟦folio 36⟧

Pis. 1.

F1177. Mạch dao động gồm một cuộn dây có độ tự cảm $L = 1$ Gi và điện trở $R = 1$ Ohm và một tụ điện có điện dung $C = 1$ µF. Tụ điện không lý tưởng - điện trở cách điện $R_x$ của nó là hữu hạn. Tại giá trị nào $R_x$ trong cuộn dây tỏa ra dưới dạng nhiệt lượng bằng 1/3 năng lượng ban đầu của mạch?

Hình 1.

Hình 2.

HÃY GIẢI QUYẾT CÂU HỎI VỀ GIẢM GIÁ MẠCH, trước tiên không tính đến tổn hao trong tụ điện (hình 1). Nếu chúng ta coi sự dao động của dòng điện trong cuộn dây là sóng hài thì trong khoảng thời gian đó tổn hao trong cuộn dây sẽ là

$$\Delta W = \frac{I_0^2 R}{2} T,$$

trong đó $I_0$ là biên độ dòng điện trong cuộn dây, $T = 2\pi\sqrt{LC}$ là chu kỳ dao động. Năng lượng mạch tối đa là $W = \frac{LI_0^2}{2}$.

Sau đó $$\frac{\Delta W}{W} = \frac{I_0^2 RT}{LI_0^2} = 2\pi R \sqrt{\frac{C}{L}}.$$

Trong trường hợp của chúng tôi

$$\frac{\Delta W}{W} \approx 6 \cdot 10^{-3} \ll 1,$$

nghĩa là những rung động thực sự có thể được coi là hài hòa.

Lưu ý rằng kết quả sẽ không thay đổi ngay cả khi tính đến tổn thất bổ sung trong tụ điện, theo điều kiện bài toán, chỉ lớn gấp đôi tổn thất trong cuộn dây. Vì vậy, trong trường hợp này (hình2) tổn hao trong cuộn dây là

$$\Delta W_2 = \frac{I_0^2 R}{2} T,$$

tổn thất trong tụ điện -

$$\Delta W_2 = \frac{U_0^2}{2R_x} T,$$

trong đó $U_0$ là biên độ điện áp trên tụ điện. Xét rằng $\Delta W_2 = 2\Delta W_1$ và $$\frac{LI_0^2}{2} = \frac{CU_0^2}{2},$$ chúng ta nhận được

$$\frac{U_0^2}{2R_x} = \frac{CU_0^2 R}{L},$$

sự phản kháng đến từ đâu

$$R_x = \frac{L}{2CR} = 5 \cdot 10^5 \text{ Ом.}$$

Z. A. Rafailov
