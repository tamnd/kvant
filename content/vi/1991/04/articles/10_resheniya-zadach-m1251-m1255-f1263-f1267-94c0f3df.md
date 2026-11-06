---
id: 1991-4-resheniya-zadach-m1251-m1255-f1263-f1267-94c0f3df
issue: kvant_1991_4
year: 1991
number: "4"
title: Lời giải bài toán M1251—M1255; F1263—F1267
rubric: zadachnik-kvanta
rubric_sub: Задачник «Кванта»
page_first: 27
page_last: 35
page_labels: 25-33
lang: vi
source: kvant_digital
extraction: vision
content_sha256: f06e802f628703485d48057c1f78ec3daff9f5d2746816cb3f12150c00bbdb1d
prompt_sha256: draft-1
translated_from: content/ru/1991/04/articles/10_resheniya-zadach-m1251-m1255-f1263-f1267-94c0f3df.md
source_content_sha256: da0b1849cf8b7003667a887d40b24ab118effeb6f18e667e98bd1515c32baa46
translation_model: draft
translation_run: vi-draft-gaps-2026-11-06
translation_quality: draft
---

⟦folio 25⟧

Lời giải bài toán
M1251 — M1255, F1263 — F1267

Đáp số: điểm cần tìm $M$ nằm trên bissertrix của góc và $AM=AP=AQ$ (A là đỉnh của góc; hình 1) - những điều kiện này cho phép chúng ta dựng $M$ theo một cách rất đặc biệt.

Chúng ta sẽ bắt đầu với các điểm tùy ý $M$, $P$ và $Q$, trong đó tổng $PM+MQ$ được đưa ra và trong một số bước, chúng ta sẽ di chuyển chúng để có được vị trí được chỉ ra trong đáp số và diện tích $APMQ$ sẽ tăng lên ở mỗi bước (chính xác hơn là không giảm).

1°. Hãy thay thế hình tứ giác $APMQ$ và làm cho nó lồi (nếu ban đầu nó nhỏ).

Để thực hiện việc này, hãy thay thế $M$ bằng điểm $M'$, đối xứng $M$ so với điểm giữa của đoạn $PQ$. Rõ ràng là $M'$ nằm bên trong góc (và thậm chí bên trong hình bình hành $APA'Q$; hình 2), $PM+MQ=PM'+M'Q$, và diện tích của tứ giác tăng lên.

2°. Cố định $\Delta PQM$ và di chuyển nó vào trong góc sao cho $AP=AQ$.

Sẽ thuận tiện hơn khi chia không phải tam giác mà là đỉnh của góc $A$, bảo toàn các giá trị của nó, tức là dọc theo cung của đường tròn $PAQ$ (hình 3). Khu vực $\Delta APQ$ trở nên quan trọng nhất.

3°. Chúng ta hãy di chuyển $M$ song song với $PQ$ tới bissertrix của góc $A$ và chuẩn bị toàn bộ hình từ tâm

⟦folio 26⟧

---
running_head:
folio:
---

rum $A$ để giá trị đã cho của tổng $PM + MQ$ (hình 4) được khôi phục.

Với sự dịch chuyển $M$, diện tích $APMQ$ không thay đổi, nhưng tổng khoảng cách $PM$ và $MQ$, nói chung, sẽ giảm. (Hãy nhớ rằng đạt được giá trị nhỏ nhất của $PM + MQ$ đối với các điểm $M$ trên một đường nhất định $m$ khi $PM$ và $MQ$ tạo các góc bằng nhau $c$ $m$, vì $PM + MQ = P'M + MQ$, trong đó điểm $P'$ đối xứng $P$ so với $m$.) Do đó, với tính đồng nhất tiếp theo của diện tích $APMQ$ chỉ có thể tăng lên.

Cần lưu ý rằng “deltoid” $APMQ$ thu được sau bước $3^0$ bao gồm hai hình tam giác bằng nhau $APM$ và $AQM$, trong đó đáy: $PM = QM = (PM + QM)/2$ và góc ở đỉnh: $\angle PAM = \angle QAM = \angle A/2$ đã biết. Và chúng ta đã thấy (bước $2^0$) rằng trong những điều kiện này, diện tích của tam giác sẽ lớn nhất khi nó là tam giác đều, tức là khi $AP = AM = AQ$.

N. Vasiliev, V. Senderov

M1252. Cho $a$ và $n$ là các số tự nhiên. Chứng minh rằng số phân số tối giản thích hợp có giá trị $a^n - 1$ chia hết cho $n$.

Đặt $x = x_n x_{n-1} \dots x_1$ là bản ghi của số $x < a^n - 1$ trong hệ thống số ở cơ số $a$, tức là $x = x_n \cdot a^{n-1} + x_{n-1} \cdot a^{n-2} + \dots + x_1 \cdot a^0$, trong đó $0 \leqslant x_i \leqslant a-1$, $i=1, \dots, n$ (bản ghi có thể bắt đầu bằng số 0). Hãy chứng minh rằng nếu $x$ nguyên tố cùng nhau với số $A = a^n - 1$ thì tất cả các số thu được bằng phép hoán vị tuần hoàn của các chữ số trong ký hiệu $a$-ary $x$) đều nguyên tố cùng nhau với $A$ và $2$) là khác nhau. (Từ đó, tất cả các số như vậy được chia thành các nhóm không giao nhau, mỗi nhóm có $n$ phần, có nghĩa là số của chúng chia hết cho $n$.)
1) Hãy kiểm tra xem khi sắp xếp lại chữ số $a$-ary $x_n$ đầu tiên của số $x$ về cuối từ thì kết quả có đơn giản với $A$ số đó không:
$$x_{n-1} \dots x_1 x_n = x_n x_{n-1} \dots x_1 0 - x_1 0 \dots 00 + x_1 = ax - x_1 (a^n - 1) = ax - Ax_1$$
số này nguyên tố chung với $A$, vì $a$ và $x$ nguyên tố chung với $A$.
2) Giả sử rằng bằng cách sắp xếp lại các chữ số theo chu kỳ, số ban đầu $x$ đã thu được, tức là.

⟦folio 27⟧

---
running_head:
folio:
---

$$x = x_n \dots x_1 = x_k x_{k-1} \dots x_1 x_n \dots x_{k+1}.$$

Sau đó
$$x(a^k - 1) = x_k \dots x_1 x_n \dots x_{k+1} \cdot a^k - x_n \dots x_1 = x_k \dots x_1 \cdot a^n - x_k \dots x_1 = x_k \dots x_1 \cdot A.$$

Nhưng $x$ và $A$ là nguyên tố cùng nhau, do đó, $a^k - 1$ chia hết cho $A = a^n - 1$, tức là $k = n$, và hoán vị của chúng ta giống nhau. (Có thể chứng minh một cách không biểu diễn rằng nếu ký hiệu $x$ biến thành chính nó trong một hoán vị tuần hoàn không mong muốn, thì nó bao gồm một nhóm các chữ số được lặp lại nhiều lần và sau đó $x$, rất/không, không nguyên tố cùng nhau với $a^n - 1 = (a - 1) \cdot 11 \dots 1.$)

K. Kokhas

M1253*. Một đa giác lồi $M$ được vẽ trên mặt phẳng, được chia thành nhiều đa giác lồi - một “bản đồ” của một số “quốc gia”. Chúng ta sẽ nói rằng một bản đồ như vậy được hiện thực hóa trong không gian nếu nó là hình chiếu của một “nắp lồi”, tức là nếu có một đa giác lồi trong đó một trong các mặt là $M$ và hình chiếu của các mặt còn lại lên mặt phẳng của mặt $M$ là quốc gia của bản đồ này (và có lẽ cả các cạnh $M$).
a) Xây dựng ví dụ về bản đồ từ các hình tam giác không cho phép thực hiện trong không gian.
Chứng minh rằng bản đồ thừa nhận thực hiện lồi trong mỗi dịch vụ sau:
b) tất cả các quốc gia đều là các tam giác nhọn, b) mỗi quốc gia là một đa giác nội tiếp chứa tâm của một đường tròn ngoại tiếp bên trong chính nó.

M1254. Một hình chữ nhật gồm $m \times n$ ô được vẽ trên giấy ca rô,

Từ ngữ bài toán M1253 đã đặt ra một số câu hỏi khó hiểu đối với một số độc giả. Đây là một công thức chính xác hơn; Hạn nộp hồ sơ lời giải kéo dài đến ngày 15 tháng 6 năm 1991.

(Công thức này có thể hiểu là các cạnh của “nắp” liền kề với các cạnh của đa giác, nghĩa là khối đa diện không có các mặt cạnh “thẳng đứng”; trong trường hợp này, câu 6) và c) rất/không sai. Tuy nhiên, sẽ rất thú vị nếu có được các điều kiện cần hoặc đủ cho “khả năng thực hiện được” theo nghĩa hẹp hơn này.)

⟦folio 28⟧

---
running_head:
folio:
---

$m \ge n > 1$. Chứng minh rằng có thể cắt thành bốn ô có dạng chữ L khi và chỉ khi mn chia hết cho 8.

cắt thành hình chữ L từ 4 ô. Khi đó số của các hình này là $N = mn/4$. Tuy nhiên, trong số các số - giả sử, số hàng $m$ là số chẵn. Hãy tô màu các đường xen kẽ màu trắng và đen. Mỗi hình D gồm 4 ô chứa một hoặc ba ô màu đen. Vì tổng số ô đen $mn/2 = 2N$ là số chẵn nên số $N$ phải là số chẵn (nếu không tổng của $N$ số hạng bằng 1 hoặc 3 sẽ là số lẻ). Vì $mn/4$ là số chẵn nên mn chia hết cho 8.

Để chứng minh điều đó về bản chất, bạn chỉ cần đảm bảo rằng mình có thể cắt được hình chữ nhật $3 \times 8$ (xem hìnhok). Thực tế là bất kỳ hình chữ nhật nào có dạng $8k \times n$, trong đó $n$ là số lẻ, có thể được tạo thành từ các hình chữ nhật $3 \times 8$ và $2 \times 4$, và một hình chữ nhật $m \times n$, trong đó $m$ và $n$ là số chẵn, có thể được chia thành các hình chữ nhật $2 \times 4$. Rõ ràng, cái sau được cắt thành hai “chữ G”.

N. Vasiliev, V. Ginzburg

M1255. Gọi $h$ là chiều cao nhỏ nhất của khối tứ diện, $d$ là khoảng cách nhỏ nhất giữa hai cạnh giao nhau của nó. Chứng minh bất đẳng thức $1/2 < d/h < 3/2$.

Hãy xem xét một hình song song được mô tả xung quanh một tứ diện nhất định $T$, như được hiển thị trong hìnhok 1. Chiều cao $h_i$ ($i = 1, 2, 3, 4$) của tứ diện và khoảng cách $d_k$ ($k = 1, 2, 3$) giữa các cạnh đối diện của nó có thể được biểu thị bằng thể tích $V$ của hình bình hành, diện tích các mặt của nó và diện tích diện tích các mặt của tứ diện. Thật vậy, đại lượng $d_k$ là chiều cao của hình bình hành, do đó, $V = d_k \cdot S_k$, trong đó $S_k$ là diện tích các mặt tương ứng của nó. Mặt khác, tứ diện $T$ thu được từ một hình bình hành bằng cách cắt bỏ bốn tứ diện, mỗi khối rõ ràng có thể tích là $V/6$. Do đó, thể tích của tứ diện bằng $(1 - 4/6)V = V/3$, và do đó $V = h_i \cdot s_i$, trong đó $s_i$ là diện tích của mặt tứ diện vuông góc với chiều cao $h_i$, $i = 1, 2, 3, 4$. Vì thế,

$$h_i = V/s_i, \quad d_k = V/S_k.$$

Với mục đích định nghĩa, đặt $h_1 = h$ và $d_1 = d$ lần lượt là số lượng nhỏ nhất trong các đại lượng $h_i$ và $d_k$. Hãy xem xét một trong bốn tứ diện bổ sung cho $T$ dọc theo diện tích mặt $s_1$. Diện tích của ba mặt còn lại của nó bằng $S_1/2, S_2/2$ và $S_3/2$ và tổng của chúng lớn hơn $s_1$, vì các hình chiếu của chúng lên mặt $s_1$ che phủ hoàn toàn mặt đó:

$$s_1 < (S_1 + S_2 + S_3)/2 \leq 3S_1/2$$

($S_1$ là diện tích nhỏ nhất trong các diện tích $S_k$). Từ đây

$$d_1 < 3h_1/2.$$

Bây giờ chúng ta hãy chứng minh rằng

$$2S_1 < (s_1 + s_2 + s_3 + s_4),$$

từ đây sẽ suy ra rằng $S_1 < 2s_1$ ($s_1$ là diện tích nhỏ nhất trong các diện tích $s_i$), tức là $h_1 < 2d_1$. Để làm điều này, hãy xem xét đường viền của một tứ diện bằng một mặt phẳng song song với

⟦folio 29⟧

---
running_head:
folio:
---

bụi bẩn mới của khu vực $S_1$ song song và bằng nhau-
ở xa họ (hình 1, 2). Thật dễ dàng để xem nó là gì
hình bình hành $\Pi$ có các cạnh song song
đường chéo của các mặt này và bằng một nửa chiều dài của chúng. Đó là lý do tại sao
diện tích adb của nó là $S_1/2$. Bây giờ chúng ta hãy nhìn vào bốn
than paramid với đỉnh ở trung tâm của một trong những
những mặt này và phần đế $\Pi$ (hình 2). Diện tích các mặt bên của nó rõ ràng bằng $s_i/4$, $i=1, 2, 3, 4$ và tổng của chúng lớn hơn diện tích của đáy, tức là.

$$S_1/2 < (s_1 + s_2 + s_3 + s_4)/4,$$

Q.E.D.

Những bất đẳng thức đã được chứng minh về diện tích có thể được tính toán
dẫn từ các đẳng thức nối các vectơ $\bar{s}_1, \bar{s}_2, \bar{s}_3, \bar{s}_4$, có độ dài bằng diện tích $s_i$ của các mặt của tứ diện, phân bố lại tương ứng với các mặt và trên-
cai trị bên ngoài khối tứ diện và các vectơ tương tự
$S_1, \bar{s}_2, \bar{s}_3, \bar{s}_4 = -\bar{s}_1, S_5 = -\bar{s}_2, \bar{s}_6 = -\bar{s}_3$ cho đường ống song song. Cụ thể là, nếu các mặt của tứ diện và cạnh
llelepiped được đánh số sao cho cạnh chung là thứ $i$ và
Mặt thứ 4 của tứ diện là đường chéo của mặt $i$
song song ($i=1, 2, 3$), sau đó $\bar{s}_i + \bar{s}_4 = \bar{s}_i$. (Chứng minh điều này bằng cách xét phép chiếu trực giao dọc theo
cạnh này.) Đặc biệt từ đây, nó suy ra rằng
$$S_1 < s_1 + s_4$$ và tương tự, $S_4 = S_1 < s_2 + s_3$, tức là
$$S_1 < (s_1 + s_2 + s_3 + s_4)/2.$$

Mặt khác, cộng ba đẳng thức $\bar{s}_i + \bar{s}_4 = \bar{s}_i$ và xét đến $\bar{s}_1 + \bar{s}_4 + \bar{s}_2 + \bar{s}_3 = \bar{S}_1 + \bar{S}_4 = 0$, ta được: $2\bar{s}_1 = \bar{S}_1 + \bar{S}_2 + \bar{S}_3$. Cái này
đẳng thức đưa ra ước tính $s_1 < (S_1 + S_2 + S_3) 2$.

V. Dubrovsky, A. Skopenkov

F1263. Khi tên lửa tăng tốc, khối lượng của nó giảm. Ở tốc độ tên lửa, động năng của nó sẽ cực đại nếu mức tiêu thụ nhiên liệu không đổi? Tốc độ của chất khí so với tên lửa là $v_0$, tốc độ ban đầu của tên lửa bằng không. Razzon được tạo ra ở xa Trái đất nên có thể bỏ qua ảnh hưởng của trọng lực.

Tại thời điểm động năng của tên lửa $E_k = Mv/2$, trong đó $M$ là khối lượng, $v$ là tốc độ tên lửa, đạt cực đại thì đạo hàm thời gian của nó bằng 0:

$$E_k' = \frac{1}{2}(M \cdot v^2)' = \frac{1}{2}M' \cdot v^2 + \frac{1}{2}M \cdot 2vv' = 0,$$

hoặc

$$v = -2\frac{M}{M'}v' = 2\frac{M}{M'}v'.$$

Vì $M' = \mu$ là mức tiêu thụ nhiên liệu, theo điều kiện không đổi, nên chúng ta thấy rằng tốc độ của tên lửa $v$, tương ứng với động năng cực đại của nó, phụ thuộc vào gia tốc của tên lửa $a = v'$ tại thời điểm này. Hãy tìm anh ấy.

Hãy chọn một khoảng thời gian rất ngắn $\Delta t$ và viết định luật bảo toàn động lượng (xem hình):

$$\mu \Delta t(v - v_0) + (M - \mu \Delta t)(v + \Delta v) = Mv.$$

Sau một số phép biến đổi, có tính đến $\mu \Delta t \ll M$, chúng ta thu được

$$a = \frac{\Delta v}{\Delta t} = \frac{\mu}{M}v_0.$$

⟦folio 30⟧

---
running_head:
folio:
---

Vậy tốc độ cần thiết bằng
$$= 2 \frac{M}{\mu} v' = 2 v_0.$$
D. Alexandrov

F1264. Tính đường kính, khối lượng, chiều dài dây tóc vonfram của một bóng đèn điện 220V, 100W. Nhiệt độ làm việc của dây tóc là 2700°C. Ở nhiệt độ này, điện trở suất của vonfram là $\rho = 90 \cdot 10^{-6}$ Ohm cm và công suất bức xạ trên một đơn vị bề mặt của sợi dây là $W = 153$ W/cm². Mật độ của vonfram gấp 19 lần mật độ của nước. Hãy xem xét rằng sợi chỉ được làm từ dây tròn.

Đặt sợi chỉ có bán kính $R$ và chiều dài $l$. Sau đó sự phản kháng của cô ấy
$$r = \rho \frac{l}{S} = \rho \frac{l}{\pi R^2}.$$
Mặt khác, công suất của bóng đèn là $P = U^2/r$, từ đó
$$r = \frac{U^2}{P}.$$
Vì vậy, chúng tôi nhận được sự tương ứng
$$\frac{U^2}{P} = \rho \frac{l}{\pi R^2}.$$ (1)
Toàn bộ năng lượng được bức xạ từ bề mặt dây tóc, do đó
$$P = W 2 \pi R l.$$ (2)
Chia tương ứng (1) cho tương ứng (2), ta tìm được
$$\frac{U^2}{P^2} = \frac{\rho}{2 \pi^2 R^3 W} \Rightarrow R^3 = \frac{\rho P^2}{2 \pi^2 W U^2}.$$
Do đó bán kính của sợi dây
$$R = \sqrt[3]{\frac{\rho P^2}{2 \pi^2 W U^2}} = 0,018 \text{ mm},$$
đường kính của nó
$$d = 2 R = 0,036 \text{ mm},$$
chiều dài sợi
$$l = \frac{P}{2 \pi R W} = 57 \text{ cm},$$
khối lượng của nó
$$m = D \pi R^2 l = 19 D_B \pi R^2 l = 0,011 \text{ г.}$$
M. Tsypin

F1265*. Trong từ trường đều, electron chuyển động theo quỹ đạo tròn. Cảm ứng từ trường diễn ra chậm (trong thời gian nhiều

Lực Lorentz tác dụng lên electron từ từ trường, truyền gia tốc hướng tâm cho electron. Theo định luật II Newton,
$$\frac{mv^2}{R} = evB,$$

⟦folio 31⟧

---
running_head:
folio:
---

chúng ta lấy nó từ đâu
$$\frac{mv}{R} = eB.$$ (*)

Sự thay đổi chậm của từ trường dẫn đến các đại lượng $B$, $R$ và $v$ bắt đầu phụ thuộc vào thời gian, mặc dù sự tương ứng (*) vẫn được thỏa mãn.

Từ trường thay đổi tạo ra một điện trường có hướng bằng
$$E_{\text{инд}} = \frac{\mathcal{E}_{\text{инд}}}{2\pi R} = \frac{\pi R^2 \frac{\Delta B}{\Delta t}}{2\pi R}.$$

Trường này tạo ra lực
$$F_{\text{инд}} = eE_{\text{инд}}.$$

Công mà lực này thực hiện trong thời gian ngắn $\Delta t$ bằng độ biến thiên động năng của electron:
$$\frac{1}{2} Rev \cdot \Delta B = \Delta \left( \frac{mv^2}{2} \right) \approx mv \cdot \Delta v,$$

trong đó sự thay đổi tốc độ sẽ bằng
$$\Delta v \approx \frac{Re}{2m} \cdot \Delta B.$$

Mặt khác, từ thư (*)
$$v = \frac{eBR}{m} = \Delta v \approx \frac{e}{m} (\Delta B \cdot R + B \cdot \Delta R).$$

Vì vậy, chúng tôi nhận được
$$\frac{1}{2} R \cdot \Delta B \approx \Delta B \cdot R + B \cdot \Delta R \Rightarrow B \cdot \Delta R + \frac{1}{2} \Delta B \cdot R = 0 \Rightarrow \Delta B \cdot R + 2B \cdot \Delta R = 0 \Rightarrow \Delta B \cdot R^2 + 2B \cdot R \Delta R = 0 \Rightarrow \Delta (BR^2) = 0.$$

Điều này có nghĩa là khi từ trường thay đổi thì giá trị $BR^2$ vẫn giữ nguyên. Do đó, việc tăng cảm ứng từ trường lên ba lần sẽ dẫn đến bán kính quỹ đạo của electron giảm $\sqrt{3}$ lần.

M. Tsypin

F1266. Hai quả cầu kim loại có bán kính $R$, mỗi quả được đặt cách xa nhau một khoảng lớn và được nối với nhau bằng một dây dẫn rất mỏng, trong khe hở có nối một cuộn dây cảm ứng $L$. Một điện tích được đặt trên một trong các quả cầu. Sau bao lâu điện tích của quả cầu này giảm đi một nửa?

Khi đặt một điện tích $Q$ lên một trong các quả cầu, nó sẽ thu được điện thế
$$\varphi_0 = \frac{Q}{4\pi F_0 R}.$$

Vì lúc đầu không có điện tích trên quả cầu thứ hai (dòng điện tích tức thời sẽ không xảy ra, nếu không thì dòng điện qua cuộn dây sẽ vô cùng lớn, điều này là không thể xảy ra), nên điện thế của nó bằng không. Do có sự chênh lệch điện thế giữa các quả cầu nên một dòng điện sẽ xuất hiện trong cuộn dây cảm ứng, thay đổi theo công thức

⟦folio 32⟧

---
running_head:
folio:
---

Sau bao lâu điện tích sẽ trở lại như lúc đầu?

$$LI' = U.$$

Người ta cho rằng hệ thống này tương đương với một mạch dao động - các quả cầu đóng vai trò là các tấm tụ điện. Nhưng sự khác biệt giữa mạch điện như vậy và mạch điện thông thường là tổng điện tích của tụ điện ở đây không bằng 0, điều này dẫn đến sự thay đổi điện dung hiệu dụng của nó. Hãy tìm cô ấy.

Chúng ta hãy biểu thị điện tích $Q$ trên quả cầu thứ nhất tại thời điểm ban đầu dưới dạng tổng của $+Q/2$ và $+Q/2$, và điện tích bằng 0 trên quả cầu thứ hai là $+Q/2$ và $-Q/2$. Trong trường hợp này, hiệu điện thế giữa các điện tích $+Q/2$ trên cả hai quả cầu bằng 0 và so với các điện tích còn lại $+Q/2$ và $-Q/2$ (tổng của chúng bằng 0) thì nó bằng $U_{\max} = \varphi_0$. Do đó, điện tích hiệu dụng của tụ điện chạy giữa các quả cầu là $Q_{\alpha\phi} = Q/2$ và

$$C_{\alpha\phi} = \frac{Q_{\alpha\phi}}{U_{\max}} = 2\pi\varepsilon_0R.$$

Vì độ tự cảm của cuộn dây là $L$ nên trong mạch xuất hiện dao động với chu kì

$$T = 2\pi\sqrt{LC_{\alpha\phi}} = 2\pi\sqrt{2\pi\varepsilon_0RL}.$$

Rõ ràng, đây là thời điểm mà sau đó điện tích trên quả cầu thứ nhất sẽ trở lại như lúc đầu (hình 1).

Bây giờ có thể dễ dàng tìm được thời gian sau đó điện tích của quả cầu thứ nhất sẽ giảm đi một nửa. Thật vậy, tại thời điểm này, điện tích trên cả hai quả cầu phải bằng $+Q/2$ và hướng giữa các quả cầu sẽ bằng không. Điều này có nghĩa là thời điểm mong muốn tương ứng với một phần tư chu kỳ dao động:

$$\tau = \frac{T}{4} = \frac{\pi}{2}\sqrt{2\pi\varepsilon_0RL}.$$

Lưu ý rằng bài toán này có thể được giải theo cách hình thức hơn. Gọi $q_2$ là điện tích truyền sang quả cầu thứ hai tại thời điểm $t$ (hình 2). thì điện tích của quả cầu thứ nhất sẽ là $q_1 = Q - q_2$. Trong trường hợp này, hướng của cuộn dây bằng với hiệu điện thế được tạo ra bởi các điện tích trên các quả cầu:

$$U = \varphi_1 - \varphi_2 = \frac{q_1}{4\pi\varepsilon_0R} - \frac{q_2}{4\pi\varepsilon_0R} = \frac{Q/2 - q_2}{2\pi\varepsilon_0R}.$$

Ta viết định luật biến thiên của dòng điện qua cuộn dây: $LI' = U$, hoặc, vì $I = q'_2$,

$$Lq'_2' = \frac{Q/2 - q_2}{2\pi\varepsilon_0R}.$$

Hãy chuyển sang biến $q_3 = Q/2 - q_2$ và chúng ta nhận được

$$q'_3' = -\frac{1}{2\pi\varepsilon_0RL}q_3.$$

Đây là phương trình dao động điều hòa có chu kỳ $T = 2\pi\sqrt{2\pi\varepsilon_0RL}$. Điện tích trên quả cầu thứ nhất chỉ khác điện tích $q_3$ một lượng không đổi, nghĩa là nó dao động cùng chu kỳ.

A. Vytsko

⟦folio 33⟧

---
running_head:
folio:
---

F1267. Một nguồn điểm của hạt alpha phát ra chúng đồng đều theo mọi hướng. Ở khoảng cách 10 cm so với nguồn, đặt một tấm nhựa quang có kích thước 20x20 cm; sau 10 giây extocycline, 200 dấu vết của các hạt bị mắc kẹt xuất hiện trên đó. Nguồn phát ra bao nhiêu hạt mỗi giờ?

Điểm đặt nguồn được đặt ở vị trí rất tốt: nó nằm ở trung tâm của khối lập phương, một trong các mặt của nó là nhựa quang. Điều này có nghĩa là trong 10 giây nguồn phát ra 6 200 = 1200 hạt. Sau đó trong một giờ anh ta sẽ phát ra

$$N = 1200 \cdot 3600 / 10 = 432000 \text{ частиц.}$$

Tuy nhiên điều này đáp số không hoàn toàn chính xác. Thực tế là trong quá trình phân rã phóng xạ, các hạt được phát ra một cách hỗn loạn, nên chúng ta đáp số có tính chất đánh giá. Hãy tự suy nghĩ xem nó sẽ tốt như thế nào lời giải, nếu điều kiện bao gồm một số nhỏ hơn đáng kể 200, ví dụ 10.
