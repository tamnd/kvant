---
id: 1990-2-resheniya-zadach-m1181-m1185-f1193-f1197-6ef8ca90
issue: kvant_1990_2
year: 1990
number: "2"
title: Lời giải bài toán M1181—M1185; F1193—F1197
rubric: zadachnik-kvanta
rubric_sub: Задачник «Кванта»
page_first: 35
page_last: 42
page_labels: 33, 34, 36, 37, 38, 39, 40
lang: vi
source: kvant_digital
extraction: vision
content_sha256: 3efa9b7c3a00b213c37d840e3192108f64b3bf37c2f77b2c6cd5bc31eebddeb8
prompt_sha256: draft-1
translated_from: content/ru/1990/02/articles/10_resheniya-zadach-m1181-m1185-f1193-f1197-6ef8ca90.md
source_content_sha256: 9a0834e7886b0d22ef6933e4e1ce28fa0740de91491c6cde74330f417c64ae5f
translation_model: draft
translation_run: vi-draft-gaps-2026-11-01
translation_quality: draft
---

⟦folio 33⟧

---
running_head:
folio:
---

Lời giải bài toán
M1181 — M1185, F1193 — F1197

Hãy tô màu các trường bảng như trong hình. Vì có chính xác một quân cờ trên mỗi đường ngang nên có 4 quân cờ trên ô màu đỏ và vàng. Tương tự, trên ô xanh và vàng cũng có 4 quân. Do đó, số trên ô màu đỏ giống như số trên ô màu xanh và tổng số của chúng là số chẵn. Nhưng các ô màu đỏ và xanh là các ô màu đen của màu cờ vua ban đầu.

B. Tùy tiện

M1182. Ở một số loài hoa hồng có n ≥3 con sáo và khoảng cách giữa các con sáo là khác nhau. Mỗi người trong số họ có một con sáo vàng. Tại mỗi thời điểm, một số con rời bỏ đàn sáo của mình và bay đến chỗ những con khác, thế là trong mỗi con sáo lại có một con sáo. Hơn nữa, nếu khoảng cách giữa mỗi cặp chim sáo nhỏ hơn khoảng cách giữa các cặp chim sáo kia (một con sáo có thể được tính theo các cặp khác nhau), thì sau chuyến bay, khoảng cách giữa cặp chim sáo đầu tiên sẽ lớn hơn khoảng cách giữa cặp chim sáo thứ hai. Trong điều kiện nào điều này là có thể?

Đáp số: với n=3.
Hãy để chúng tôi chứng minh rằng bất kỳ con sáo nào vẫn ở nguyên vị trí hoặc đổi chỗ cho những con chim sáo khác.

Để chim sáo từ chim sáo $A_1$ bay đến $A_2$, từ $A_2$ đến $A_3$, v.v. Số lượng chim sáo là hữu hạn, do đó, trong chuỗi $A_1, A_2, A_3$, ... các lần lặp lại bắt đầu và $A_1$ sẽ được lặp lại trước (nếu, chẳng hạn, $A_3$ xuất hiện lại, thì ngay trước đó sẽ có $A_2$ và trước $A_2$—$A_1$, tức là $A_1$ lại xảy ra sớm hơn). Giả sử rằng $A_i \neq A_1$ tại $1 < i \leq k$, $A_{k+1} = A_1$ và khoảng cách nhỏ nhất trong các khoảng cách $A_1A_2, A_2A_3, ..., A_kA_1$ là, chẳng hạn, $A_1A_2$. Từ thực tế là $A_1A_2$ nhỏ hơn tất cả các khoảng cách khác $A_iA_{i+1}$, dẫn đến điều kiện là $A_2A_3$ lớn hơn tất cả các khoảng cách khác $A_iA_{i+1}$, và do đó $A_3A_4$ nhỏ hơn tất cả các khoảng cách khác $A_iA_{i+1}$, tức là $A_3A_4 = A_1A_2$. Nhưng tất cả các khoảng cách $A_iA_j$ đều khác nhau, do đó $A_3 = A_1$. Nói cách khác, nếu con sáo đã rời khỏi con sáo $A_1$, thì nó sẽ đổi chỗ cho con sáo từ $A_2$.

Hình 1.
Hình 2.

⟦folio 34⟧

---
running_head:
folio:
---

Nếu $n \geq 4$, thì rõ ràng là bạn có thể chọn 4 chuồng chim, các chuyến bay giữa chúng được sắp xếp theo một trong những cách được hiển thị ở hình 1. Trong mọi trường hợp, khoảng cách giữa các con sáo $A$ và $B$, $C$ và $D$ không thay đổi sau chuyến bay, trong khi theo điều kiện, khoảng cách nhỏ hơn sẽ trở nên lớn.

Đối với trường hợp $n=3$ một ví dụ được đưa ra trong hình 2.
A. Berzins, V. Dubrovsky

M1183. Mỗi em trong số bảy em nhỏ đến quán kem 3 lần vào ngày Chủ nhật. Được biết, cả hai đều gặp nhau ở gần ki-ốt. Chứng minh rằng tại một số điểm có ba số nhỏ gặp nhau tại đó cùng một lúc.

Đặt câu bài toán sai và đặt $\Delta_1, \Delta_2, \dots, \Delta_n$ là khoảng thời gian không giao nhau trong đó có hai con chó nhỏ ở gần ki-ốt. Tại thời điểm đầu tiên của mỗi khoảng thời gian $\Delta_2, \Delta_3, \dots, \Delta_n$, ít nhất một anh chàng nhỏ bé tiếp cận ki-ốt, tại thời điểm đầu tiên của khoảng thời gian $\Delta_1$ - một trong hai (nếu đã có một anh chàng nhỏ bé ở gần ki-ốt) hoặc hai (nếu không bao giờ có một anh chàng nhỏ nào ở gần ki-ốt). Do đó, tổng số $s$ số lượt đến ki-ốt của cả bảy cửa hàng nhỏ không nhỏ hơn $n+1$. Vì chỉ từ 7 con nhỏ có thể tạo thành $7 \cdot 6/2=21$ các cặp khác nhau, và tùy theo điều kiện mà cứ hai con nhỏ gặp nhau tại ki-ốt, $n \geq 21$. Vì vậy, $s \geq 22$. Mặt khác, $s=7 \cdot 3=21$. Sự mâu thuẫn.

A. Anjan

M1184. Trên tất cả các cạnh của một terazdrade tùy ý, một điểm được chọn. Qua mỗi điểm nằm trên các cạnh xuất phát từ một đỉnh, chúng ta vẽ một mặt phẳng. Chứng minh rằng nếu ba trong số chúng tiếp xúc với quả cầu nội tiếp thì mặt phẳng thứ tư tiếp xúc với quả cầu nội tiếp.

Hãy xem xét terazdr $ABCD$ và lấy các điểm $K, L, M, P, Q, T$ trên các cạnh của nó, như minh họa trong hình. Để máy bay $KMP, MLT$ và $LKQ$ chạm vào quả bóng được ghi trong terastron, và để máy bay $PTQ$ không chạm vào quả bóng này. Giả sử, nhằm mục đích định nghĩa, quả bóng nội tiếp cắt mặt phẳng $PTQ$. Chúng ta hãy vẽ qua $PQ$ một mặt phẳng tiếp xúc với quả bóng nội tiếp và biểu thị bằng $T_1$ giao điểm của mặt phẳng này với cạnh $DC$.

Xét khối đa diện lồi (bát diện) $KMLPQTT_1$. Để thuận tiện, hãy tô màu các mặt $KMP, MLT, LKM$ và $PQT_1$ màu đen, các mặt còn lại sẽ trống màu trắng. Các mặt không thuộc bề mặt của terazdra $ABCD$ được sơn màu đen, trong khi các mặt thuộc bề mặt $ABCD$ có màu trắng. Lưu ý rằng không có cặp mặt đen nào có cạnh chung. Đối với mặt trắng, có một ngoại lệ: cạnh $T_1T$ chung của hai mặt trắng. Tất cả các mặt của khối bát diện của chúng ta đều chạm vào một quả bóng. Hãy lấy một điểm tiếp tuyến trên mỗi mặt và nối nó với tất cả các đỉnh của mặt này. Mỗi mặt sẽ được chia thành các hình tam giác. Trong trường hợp này, mỗi tam giác màu đen tương ứng với một tam giác màu trắng bằng nhau ở mặt liền kề, có một cạnh chung với nó. Các hình tam giác màu trắng có một ngoại lệ - một cặp hình tam giác màu trắng bằng nhau ở cạnh $T_1T$.

⟦folio 36⟧

---
running_head:
folio:
---

trận đấu $s$; trên hình của chúng tôi, điều này đã xảy ra vào lúc $n = 5$.

2) Từ dữ liệu của phương trình, ngay lập tức suy ra rằng $x_1 = x_n$, $x_2 = x_{n-1}$, $x_3 = x_{n-2}$, ...: trên thực tế, từ cái đầu tiên và cái cuối cùng, rõ ràng là $x_1 = x_n = 1/s$, từ cái thứ hai và áp chót - rằng $x_1 + x_2 = 1/(s - x_1) = 1/(s - x_n) = x_{n-1} + x_n$, tức là $x_2 = x_{n-1}$, v.v. Sự đối xứng này hiển thị ngay lập tức từ hình 1, vì hyperbola của đối xứng với phần đầu của bisserris $y = s - x$.

Nhận xét thứ hai cho phép chúng ta viết ngắn gọn lời giải cho $n$ nhỏ.

a) $n = 3$. Sau đó $s = 2x_1 + x_2 = x_1 + s_1$. Từ phương trình $x_1(x_1 + s_1) = 1$, $s_1^2 = 1$ ta tìm được $s_1 = 1$, $x_1^2 + x_1 - 1 = 0$, từ đâu (kể từ $x_1 > 0$)

$$x_1 = \frac{\sqrt{5} - 1}{2}, x_2 = 1 - x_1 = \frac{3 - \sqrt{5}}{2}, x_3 = x_1.$$

6) $n = 4$. Sau đó $s = 2x_1 + 2x_2 = 2s_1$. Từ phương trình $2x_1s_1 = 1$, $s_1(2s_1 - x_1) = 1$ ta tìm được $2s_1^2 = 1 + x_1s_1 = 3/2$, $s_1 = \sqrt{3}/2$, từ đâu

$$x_1 = \frac{\sqrt{3}}{3}, x_2 = \frac{\sqrt{3}}{2} - \frac{\sqrt{3}}{3} = \frac{\sqrt{3}}{6}, x_3 = x_2, x_4 = x_1.$$

Lưu ý rằng trong trường hợp $n = 2$ đáp số được tìm thấy ngay lập tức:

$$2x_1^2 = 1, x_1 = x_2 = \sqrt{2}/2.$$

Đối với những người sành hình học, những con số này gợi lên ý tưởng rằng các số ngẫu nhiên $n = 2$, $n = 3$ và $n = 4$ bằng cách nào đó có liên quan đến các góc tương ứng $45^\circ$, $36^\circ$ và $30^\circ$. Trên thực tế, chúng ta sẽ thấy (xem hình 2) rằng với bất kỳ $n$ nào cũng có hệ lời giải liên kết với góc $\alpha = 180^\circ/(n + 2)$. Từ nhận xét đầu tiên, lời giải này là duy nhất.

Hãy dựng một tam giác đều $A_0OA_n$ với các cạnh $A_0O = OA_n = 1$ và các góc $\alpha = 180^\circ/(n + 2)$ ở đáy; dựa trên $A_0A_n$, chúng tôi đánh dấu các điểm $A_1, A_2, ..., A_{n-1}$ sao cho các đoạn $A_0A_1, A_1A_2, ..., A_{n-1}A_n$ có thể nhìn thấy được từ đỉnh $O$ ở các góc bằng nhau $\alpha$. Hãy để chúng tôi chứng minh rằng độ dài của các đoạn này $x_1, x_2, ..., x_n$ thỏa mãn hệ thống của chúng tôi. Thật thuận tiện khi vẽ một tia OP khác đi qua điểm $O$, song song với $A_0A_n$ ($\angle POA_0 = \alpha$). Các tam giác $A_0OA_k$ và $A_nA_{k-1}O$ giống nhau ($\angle A_0 = \angle A_n = \alpha$, $\angle A_0OA_k = k\alpha = \angle POA_{k-1} = \angle OA_{k-1}A_n$), với các cạnh $A_0O = 1$ và $A_0A_k = x_1 + ... + x_k$ của tam giác thứ nhất tương ứng với các cạnh $A_{k-1}A_n = x_k + ... + x_n$ và $OA_n = 1$ của tam giác thứ hai, từ đó ta thu được phương trình

$$(x_1 + ... + x_k)(x_k + ... + x_n) = 1.$$

Vậy sự tồn tại của lời giải được chứng minh. Sử dụng định lý sin, dễ dàng thu được các công thức rõ ràng: vì $OA_0 = 1$,

$$\angle A_0OA_k = k\alpha, \angle A_0A_kO = 180^\circ - \angle POA_k = 180^\circ - (k + 1)\alpha,$$

từ $\Delta OA_{k-1}A_k$ và $\Delta OA_0A_k$ chúng ta nhận được.

⟦folio 37⟧

---
running_head:
folio:
---

$$\frac{x_k}{\sin \alpha} = \frac{OA_k}{\sin k\alpha}, \frac{OA_k}{\sin \alpha} = \frac{1}{\sin (k+1)\alpha},$$
Ở đâu:
$$x_k = \frac{\sin^2 \alpha}{\sin k\alpha \sin (k+1)\alpha} \quad (k=1, 2, ..., n; \alpha = \frac{\pi}{n+2}).$$

Cụ thể, với $n=10$ chúng ta có $\alpha = \frac{\pi}{12}$; với các số $\sin k\alpha$ cho $k=1, 2, ..., 6$ bằng $\sqrt{\frac{1}{2} - \frac{\sqrt{3}}{4}}, \frac{1}{2}, \frac{\sqrt{2}}{2}, \frac{\sqrt{3}}{2}, \sqrt{\frac{1}{2} + \frac{\sqrt{3}}{4}}, 1$ tương ứng (và có kích thước, $\sin (12-k)\alpha = \sin k\alpha$). Thay thế các giá trị này vào công thức chung, chúng ta thu được đáp số, được chỉ định ở lề.

N. Vasiliev, V. Protasov

F1193. Trong không gian có một khối lập phương. Lúc này mặt ABCD nằm ngang (hình 1), vận tốc của các điểm A và B hướng thẳng đứng xuống dưới và bằng modulo v. Biết vận tốc của điểm C lúc này là modulo 2v. Tốc độ tối đa mà các hình khối khác có thể có tại thời điểm này là bao nhiêu?

Xét điểm C. Dễ dàng báo cáo rằng tại một thời điểm nhất định, vectơ vận tốc của điểm này là thẳng đứng (điều này suy ra từ thực tế là cả thành phần tịnh tiến và thẳng đứng của vận tốc của điểm C đều thẳng đứng). Trong trường hợp này, vectơ vận tốc của điểm C có thể hướng lên trên (trường hợp a) và hướng xuống dưới (trường hợp 6).

Hãy bắt đầu với trường hợp a). Hiển nhiên có một điểm trên đường thẳng BC có vận tốc tại một thời điểm cho trước bằng 0. Thật vậy, nếu thành phần tịnh tiến của vận tốc của tất cả các điểm trong khối lập phương bằng v và hướng xuống dưới, thì thành phần thẳng đứng của điểm C bằng 3v và hướng thẳng đứng lên trên. Khi đó, cách điểm B một khoảng $a/3$, trong đó $a$ là chiều dài cạnh của hình lập phương, sẽ có một điểm O, thành phần thẳng đứng của vận tốc của nó bằng v và hướng lên trên. Do đó, tổng vận tốc của điểm O tại thời điểm cho trước bằng không. Điểm này được gọi là tâm quay trao đổi. Nhưng nếu điểm O không chuyển động tại một thời điểm nhất định thì điểm có khoảng cách tối đa với điểm O sẽ có tốc độ tối đa. Rõ ràng điểm E thỏa mãn điều kiện này. Từ
$$\frac{v_E}{v_C} = \frac{OE}{OC} \quad \text{и} \quad OE = \sqrt{a^2 + \left(\frac{2}{3} a\right)^2} = \frac{\sqrt{13}}{3} a,$$
chúng tôi nhận được
$$v_E = v_C \frac{OE}{OC} = v \sqrt{13} \approx 3,6v.$$

⟦folio 38⟧

---
running_head:
folio:
---

Trong trường hợp 6) tâm quay tức thời của mặt BCEF - điểm $O'$ (xem hình 2) - nằm bên ngoài cạnh BC một khoảng $BO' = a$ về bên phải điểm B. Điểm E lại sẽ có tốc độ cực đại, và

$$v_E = v_C \frac{O'E}{O'C} = 2v \frac{\sqrt{a^2 + (2a)^2}}{2a} = v\sqrt{5} \approx 2,2v.$$

Như vậy, với cả hai hướng có thể có của vectơ vận tốc của điểm C, giá trị cực đại của vận tốc sẽ có các điểm của khối lập phương nằm trên cạnh song song với đường thẳng AB và đi qua đỉnh E.

S. Krotov

F1194. Ống mao dẫn được làm bằng hai ống thủy tinh mỏng có đường kính trong $d_1$ và $d_2$ (xem hình). Trong đó có một lượng lớn nước có khối lượng M. Mao dẫn Koeda được đặt theo chiều ngang nếu chất lỏng “leo” vào phần mỏng và khi nó được lắp theo chiều dọc - nếu nước chảy ra khỏi nó. Trong những điều kiện nào sẽ có một phần ở ống dày và một phần ở ống mỏng nằm giữa trục mao dẫn và ống thẳng đứng? Hệ số căng bề mặt của nước σ, mật độ của nước Q. Việc làm ướt được coi là hoàn thành.

Giá trị lớn nhất của góc giữa trục mao quản và phương thẳng đứng tương ứng với trường hợp hầu hết tất cả các giọt nước đều đọng lại ở phần mỏng của mao quản. Trong trường hợp này, chiều dài cột nước

$$l_{\max} = \frac{M}{\rho \pi d_2^2/4},$$

và chiều cao của nó

$$h_{\max} = l_{\max} \cos \alpha_{\max}.$$

Khi đó điều kiện cân bằng sẽ là đẳng thức

$$p_{\text{атм}} - \frac{4\sigma}{d_1} = p_{\text{атм}} - \frac{4\sigma}{d_2} + \rho g l_{\max} \cos \alpha_{\max},$$

nó đến từ đâu?

$$\alpha_{\max} = \arccos \frac{\pi \sigma d_2}{Mg} \left(1 - \frac{d_2}{d_1}\right).$$

Giá trị nhỏ nhất của góc giữa trục mao quản và trục thẳng đứng sẽ tương ứng với trường hợp thực tế

⟦folio 39⟧

---
running_head:
folio:
---

Hầu như toàn bộ giọt nằm ở phần rộng của mao mạch. Tương tự như phần trước, chúng tôi tìm thấy

$$\alpha_{\min} = \arccos \frac{\pi \sigma d_1}{Mg} \left( \frac{d_1}{d_2} - 1 \right).$$

A. Zilberman

F1195. Một ống thẳng đứng có chiều cao $H=1$ m và diện tích mặt cắt ngang $S=50$ cm$^2$ hở ở cả hai đầu. Một lò sưởi có công suất $N=100$ W được lắp ở đáy ống. Tốc độ dòng chảy đi lên sẽ được thiết lập trong đường ống là bao nhiêu? Giả sử rằng lò sưởi không đốt cháy mặt cắt ngang của đường ống. Áp suất khí quyển $p_0=1$ atm, nhiệt độ bên ngoài là nhiệt độ phòng. Nhiệt mol của không khí ở một thể tích không đổi là $C_V=2,5$ R, trong đó $R$ là hằng số khí phổ quát.

Rõ ràng, sự nóng lên dẫn đến giảm mật độ không khí và lực Archimedean tác dụng lên không khí nóng sẽ nâng nó lên trên, tức là một luồng không khí đi lên xảy ra trong đường ống.

Chia bài toán thành hai phần.

1) Đặt mật độ không khí trong ống $\rho$, mật độ không khí xung quanh $p_0$ ($\rho < p_0$). Tốc độ chuyển động đều của không khí trong ống sẽ là bao nhiêu?

Chúng ta biểu thị áp suất ở đầu trên của đường ống (xem hình) $p_0$. Khi đó, ở gần đầu dưới, áp suất bên trong đường ống sẽ là $p_0 + \rho gH$ và bên ngoài $p_0 + \rho gH > p_0 + \rho gH$. Hóa ra là ở gần lỗ đáy của đường ống, áp suất có tốc độ bằng 0 bị hút vào đường ống, tại đó áp suất của nó giảm xuống và tốc độ tăng đến một giá trị nhất định $v$. Hãy tìm nó bằng phương trình Bernoulli:

$$\rho \frac{v^2}{2} + p = \text{const},$$ hoặc $$\frac{\rho v^2}{2} + p_0 + \rho gH = p_0 + \rho gH,$$

chúng ta lấy nó từ đâu

$$v = \sqrt{2 \frac{\rho_0 - \rho}{\rho}} gH.$$

2) Biết công suất của lò sưởi $N$, ta tìm được tỉ số $(\rho_0 - \rho)/\rho$.

Luồng không khí $\rho vS$ (khối lượng trên một đơn vị thời gian) hoặc $\frac{\rho}{M} vS$ (lượng chất trên một đơn vị thời gian) đi qua lò sưởi. Sự gia nhiệt xảy ra ở áp suất không đổi, vì vậy

$$N = \frac{\rho}{M} vSC_p \Delta T,$$

trong đó $C_p = C_V + R = 7/2$ R và $\Delta T$ bằng chênh lệch nhiệt độ bên trong đường ống (sau lò sưởi) và bên ngoài. Ở áp suất không đổi và ở $\Delta T/T \ll 1$

$$\frac{\rho_0 - \rho}{\rho} = - \frac{\Delta \rho}{\rho} \approx \frac{\Delta T}{T}.$$

Như vậy,

$$v^2 = 2 \frac{\rho_0 - \rho}{\rho} gH = 2 \frac{\Delta T}{T} gH = \frac{2NMgH}{T\rho vSC_p},$$

hoặc

$$v^3 = \frac{2NMgH}{T\rho SC_p} = \frac{2NgHR}{pSC_p} = \frac{4}{7} \frac{NgH}{pS} \approx \frac{4}{7} \frac{NgH}{p_0S}.$$

(Tiếp theo trang 42)

⟦folio 40⟧

---
running_head:
folio:
---

Tôi không tự tiêm
Tôi khẳng định rằng
chỉ một cái nhìn
để được công nhận
quang phổ mang lại
cơ hội
F. Talbot
