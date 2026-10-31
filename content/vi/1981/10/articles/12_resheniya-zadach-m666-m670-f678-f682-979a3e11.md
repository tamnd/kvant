---
id: 1981-10-resheniya-zadach-m666-m670-f678-f682-979a3e11
issue: kvant_1981_10
year: 1981
number: "10"
title: Lời giải bài toán M666—M670; F678—F682
rubric: zadachnik-kvanta
rubric_sub: Задачник «Кванта»
page_first: 36
page_last: 41
page_labels: 34-39
tag: 7DG3
lang: vi
source: kvant_digital
extraction: vision
content_sha256: c9a398970e251e392f0407e08d91a03e7a6a566e4970d1af677b167193465652
prompt_sha256: draft-1
translated_from: content/ru/1981/10/articles/12_resheniya-zadach-m666-m670-f678-f682-979a3e11.md
source_content_sha256: 3066c9d59770feab5bb06b1bd81b11d68548abfc256cae363d3b5f343902bbfe
translation_model: draft
translation_run: vi-draft-2026-10-31
translation_quality: draft
---

⟦folio 34⟧

Lời giải bài toán

M666. Chứng minh rằng bội số chung nhỏ nhất của $a_1 < a_2 < ... < a_n$ là $A$. Khi đó hiển nhiên $\frac{A}{a_1} > \frac{A}{a_2} > ... > \frac{A}{a_n}$ là các số tự nhiên. Do đó $\frac{A}{a_1} \geq n$, do đó $A \geq n a_1$.

Ước tính này là chính xác. Thật vậy, nếu $a_1 = \frac{n!}{n-1}$, $a_2 = \frac{n!}{n-1}$, ..., $a_n = n!$, thì $A = n! = n \cdot a_1$.

A. Razborov

M667. Dựng tam giác ABC nếu biết góc nhỏ nhất $\hat{A}$ và các đoạn có độ dài $d = |AB| - |BC|$ và $e = |AC| - |BC|$.

Trên các cạnh của góc $\hat{A}$ này, chúng ta tắt các đoạn AD có độ dài $d$ và AE có độ dài $e$ đã cho. Telery cũng cần tìm điểm B và C trên các cạnh này (phía sau điểm D và E), tức là $|BD| = |BC| = |CE|$.

Để làm điều này, trước tiên chúng ta xây dựng một hình đã sẵn sàng cho tứ giác BCED cần thiết. Để thực hiện điều này (Hình 1), chúng ta hãy vẽ trên đường thẳng AD (trên một tia không chứa A) một đoạn DB1 có độ dài bất kỳ $q$, sau đó chúng ta cắt song song tia [DE] với một vectơ $\vec{q}$ có cùng độ dài $q$, hướng song song với [AE], sau đó trên tia thu được $l$, chúng ta đánh dấu một điểm $C_1$, tại đó $|B_1C_1| = q$. Rõ ràng tứ giác $B_1C_1E_1D$ đồng dạng với tứ giác BCED cần tìm. Bây giờ vẽ một đường thẳng song song với $B_1E_1$ qua điểm E, ta tìm được điểm B; sau đó vẽ một đường thẳng song song với $B_1C_1$ qua điểm B, ta tìm được điểm C. (Dễ dàng nhận thấy mọi công trình luôn được đáp ứng, và theo một cách duy nhất.)

Đây là một lời giải khác - một cái không sử dụng phương pháp tương tự. Nếu $O$ là tâm của đường tròn nội tiếp tam giác ABC thì các tam giác BOD, BOC và COE mang tính xây dựng (Hình 2). Tất cả các góc lệch ở đỉnh O đều bằng $90^\circ + \hat{A}/2$. Do đó $D\hat{OE} = 90^\circ - 3\hat{A}/2$ (đại lượng này dương tại $\hat{A} < 60^\circ$). Telery, ta có thể dựng điểm O là giao điểm của phân giác của góc A và phần hồn của đoạn có hai đầu D, E, kết hợp với một góc nội tiếp có độ lớn $90^\circ - 3\hat{A}/2$ (cung đỏ ở Hình 2). Khi đó vẽ các tia OB và OC theo các góc cần thiết thành các đoạn DO và EO, ta tìm được hai đỉnh của tam giác ABC.

Cuối cùng, bài toán có thể được giải và tính toán: độ dài của đoạn mong muốn $x = |BD| = |BC| = |CE|$ được tìm thấy từ phương trình bậc hai

$$x^2 = (x+d)^2 + (x+e)^2 - 2(x+d)(x+e) \cos \hat{A},$$

sau đó, đoạn được yêu cầu có thể được tạo (dựa trên $d, e$ và $\hat{A}$) bằng la bàn và thước kẻ, kết hợp các phương pháp dựng đã biết bằng cách sử dụng các đoạn có độ dài $p$ và $q$ và góc $\alpha$ của các đoạn có độ dài $p$ cos $\alpha$, $p \pm q$, $\sqrt{pq}$, $\sqrt{p^2 \pm q^2}$. Điều thú vị là nghiệm âm của phương trình này còn có ý nghĩa hình học: nó xác định vị trí của một điểm khác $B_2 \in [DA)$, $C_2 \in [EA)$, mà tại đó $|B_2D| = |B_2C_2| = |C_2E|$.

N. Vasiliev

M668. Trình tự $(x_i)$ được xác định bởi các điều kiện $x_1 = 1$, $x_2 = 0$, $x_3 = 2$, $x_{n+1} = x_{n-2} + 2x_{n-1}$. Chứng minh rằng với bất kỳ

Đặt $m$ là số tự nhiên bất kỳ. Thay vì dãy $(x_i)$, hãy xem xét dãy $(\bar{x}_i)$ gồm các số dư khi chia $x_i$ cho $m$.

Từ định nghĩa của dãy $(x_i)$, với mọi số $\bar{x}_i$, $\bar{x}_{i+1}$ và $\bar{x}_{i+2}$ người ta có thể duy nhất

⟦folio 35⟧

số tự nhiên $m$ có hai số hạng liền kề của dãy này, mỗi số hạng chia hết cho $m$.

Thật vậy, vì số lượng số hạng của dãy là vô hạn và số lượng rãnh từ tập hợp số {0, 1, 2, ..., $m-1$} không lớn hơn $m^3$ nên nó sẽ tìm thấy hai rãnh khớp $\bar{x}_i, \bar{x}_{i+1}, \bar{x}_{i+2}$ và $\bar{x}_{i+T}, \bar{x}_{i+T+1}, \bar{x}_{i+T+2}$. Nhưng vì các số của bộ ba thứ nhất được xác định duy nhất bởi các số của bộ ba thứ hai, nên nói chung với mọi $k$ các đẳng thức $\bar{x}_{k+T}=\bar{x}_k, \bar{x}_{k+T+1}=\bar{x}_{k+1}, \bar{x}_{k+T+2}=\bar{x}_{k+2}$ ($T$ là chu kì của dãy) sẽ đúng.

Vì $\bar{x}_0=\overline{x}_3-2x_1=0, \bar{x}_{-1}=\overline{x}_2-2x_0=0, \bar{x}_{iT-1}=0$ và $\bar{x}_{iT}=0$ cho bất kỳ $l$ nào. Qua đó chúng ta đã chứng minh được rằng có vô số cặp số hạng liền kề của dãy ($x_i$), mỗi cặp số đó chia hết cho $m$.

Thật thú vị khi lưu ý mối liên hệ giữa chuỗi ($x_j$) và chuỗi Fibonacci ($f_i$): $f_1=1, f_2=2, ..., f_{n+2}=f_{n+1}+f_n$ tại $n \geqslant 1$. Dãy Fibonacci cũng có thể được tiếp tục cao hơn: $f_{n-1}=f_{n+1}-f_n$, do đó $f_0=1, f_{-1}=0$, v.v. Thật dễ dàng để kiểm tra rằng $x_i=f_{i-2}+(-1)^{i-1}$. Do đó, với bất kỳ số tự nhiên $m$ nào trong dãy ($f_i+(-1)^{i-1}$), có vô số cặp số hạng liền kề chia hết cho $m$. Đồng thời, hai số Fibonacci liền kề bất kỳ đều là số nguyên tố cùng nhau*.

G. Kozlov

**M669. Tứ giác ABCD nội tiếp trong một đường tròn. Chứng minh rằng a) đoạn thẳng nối hai đoạn AB và CD vuông góc với đoạn nối hai đoạn BC và AD; b) Tâm các đường tròn nội tiếp các tam giác ABC, BCD, CDA và DAB là các đỉnh của đường thẳng.**

a) Vì $NMP=\frac{1}{4}(BC+CD)=\frac{1}{2}\hat{A}, MNQ=\frac{1}{4}(AB+AD)=\frac{1}{2}\hat{C}$ (Hình 1), $NMP+MNQ=\frac{1}{2}(\hat{A}+\hat{C})=90^\circ$, nội tiếp của tam giác ABC, BCD, CDA và DAB tương ứng sẽ mở ra (Hình 2).

Các tam giác BMN và MO$_1N$ bằng nhau nên $|BN|=|NO_1|$. Tương tự như vậy, $|CN|=|NO_2|$. Nhưng $|BN|=|CN|$; do đó, tam giác $O_1NO_2$ là tam giác đều, trong đó $[NQ]$ là bissertrix. Vì vậy $[NQ] \perp [O_1O_2]$; có nghĩa là $[O_1O_2] \parallel [MP]$.

**Hình 1.**

**Hình 2.**

Tương tự, người ta chứng minh được $[O_3O_4] \parallel [MP]$ và $[O_1O_4] \parallel [NQ] \parallel [O_2O_3]$. Vậy tứ giác $O_1O_2O_3O_4$ là hình chữ nhật.

I. Tiếng Đức, K. Malkhasyan

* (Để biết các tính chất thú vị về tính chia hết của các số Fibonacci, xem cuốn sách “Các số Fibonacci” của N. N. Vorobyov (Loạt bài “Bài giảng phổ biến về toán học”, M., “Nauka”, 1978).

⟦folio 36⟧

M670. a) Cho một số điểm, một số cặp điểm được nối bằng đường thẳng (điểm của các cặp điểm đó được gọi là được nối bởi chúng). Số lượng kết nối tại mỗi điểm là số lẻ. Tại thời điểm ban đầu, tất cả các điểm được tô bằng hai màu - đỏ và xanh. Sau đó, cứ sau mỗi phút, các điểm được tô màu lại theo quy tắc sau: mỗi điểm trong đó phần lớn các kết nối có một màu khác với nó sẽ thay đổi màu của nó; nếu không thì màu sắc của nó sẽ được giữ nguyên. Chứng minh rằng sẽ đến một thời điểm mà tại đó một số điểm không đổi màu nhưng có một số điểm sẽ thay đổi theo từng phút. b) Liệu câu phát biểu này có còn đúng nếu không giả định rằng mỗi điểm có số lẻ kết nối?

Hình 1.

Hình 2.

Chúng ta hãy gọi đoạn $X'_i X''_j$ nối các điểm của hệ thống kép là một cạnh đa dạng nếu các đầu $X'_i$ và $X''_j$ của nó có màu khác nhau. Hãy chứng minh rằng nếu tại thời điểm tiếp theo có ít nhất một điểm có cạnh đa dạng, thì số cạnh đa dạng của hệ thống quân sự sẽ có dạng ... $P_{t-1}, P_t, P_{t-1}, P_t, \dots$, (Hình 3), và đây chính xác là điều cần được chứng minh trong nhiệm vụ.

Hình 3.

Chúng ta hãy gọi đoạn $X'_i X''_j$ nối các điểm của hệ thống kép là một cạnh đa dạng nếu các đầu $X'_i$ và $X''_j$ của nó có màu khác nhau. Hãy chứng minh rằng nếu tại thời điểm tiếp theo, có ít nhất một điểm có cạnh đa dạng, thì số cạnh đa dạng của hệ sẽ có dạng ... $P_{t-1}, P_t, P_{t-1}, P_t, \dots$, (Hình 3), và đây chính xác là điều cần được chứng minh trong nhiệm vụ.

⟦folio 37⟧

F678. Một khẩu pháo bắn từ dưới chỗ nấp nghiêng một góc α so với phương ngang (Hình 1). Súng đặt ở điểm A cách chân hầm trú ẩn (điểm B) một khoảng l. Vận tốc ban đầu của đạn là $|\vec{v}_0|$.
Giả sử quỹ đạo của viên đạn nằm trong mặt phẳng hình vẽ, hãy xác định tầm bay tối đa.

Hình 1.

Trong tất cả các quỹ đạo có thể có của đạn, chúng tôi chọn quỹ đạo chạm vào nơi trú ẩn. Chúng ta hãy xem xét chuyển động của một viên đạn trong một hệ tọa độ có các trục hướng như trong Hình 2. Trong hệ thống này, hình chiếu “ngang” (dọc theo trục OX) của vận tốc ban đầu của viên đạn bằng $v_{0x} = v_0$ cos ($\varphi - \alpha$) và phép chiếu “thẳng đứng” (dọc theo trục OY) bằng $v_{0y} = v_0 \sin (\varphi - \alpha)$, Ở đâu $\varphi$ - góc tạo bởi vectơ vận tốc ban đầu của viên đạn với đường chân trời.

Điểm C, tại đó quỹ đạo của đạn chạm vào nơi trú ẩn, xác định độ cao tối đa $h'$ của việc nâng đạn lên trên “đường chân trời”, bằng nhau, như có thể thấy trong Hình 2, $l \sin \alpha$. Tại thời điểm này, hình chiếu toàn bộ tốc độ $\vec{v}$ của viên đạn lên trục

Hình 2.

$OY$ bằng 0 và
$$h' = v_{0y}^2 / 2g'$$,
trong đó $g' = g \cos \alpha$ là “gia tốc trọng trường” trong hệ $XOY$ (hình chiếu của vectơ $\vec{g}$ lên “phương thẳng đứng” $OY$). Vì vậy, $v_{0y}^2 = 2g' h' \Rightarrow v_0^2 \sin^2 (\varphi - \alpha) = 2(g \cos \alpha) (l \sin \alpha)$.

Đặc biệt, từ đây, theo điều kiện bài toán $2g l \sin \alpha \cdot \cos \alpha = g l \sin 2\alpha > v_0^2$, thì không có quỹ đạo đạn nào chạm vào nơi trú ẩn và phạm vi bay tối đa $L_{\max}$ sẽ dành cho một viên đạn được phóng theo góc $\varphi = \pi/4$ so với đường chân trời; đồng thời $L_{\max} = v_0^2/g$.

Nếu theo các điều kiện trên đáp ứng được sự tương ứng $v_0^2 \geqslant g l \sin 2\alpha$ thì để quỹ đạo chạm vào nắp, đạn phải được phóng theo một góc
$$\varphi_{\kappa c} = \alpha + \arcsin \frac{\sqrt{g l \sin 2\alpha}}{v_0}$$.

Nếu theo điều kiện trên, bất đẳng thức
$$\frac{v_0^2}{v_0^2 + 2g l} \leqslant \sin 2\alpha$$,
lần lượt có nghĩa là $\varphi_{\kappa c} \geqslant \pi/4$ (cho tôi xem!), sau đó là góc khởi hành của đạn với tầm bay tối đa $\varphi_{\beta} = \pi/4$ và $L_{\max} = v_0^2/g$. Nếu theo điều kiện trên, bất đẳng thức nghịch đảo
$$\frac{v_0^2}{v_0^2 + 2g l} > \sin 2\alpha$$,
điều đó có nghĩa là $\varphi_{\kappa c} < \pi/4$, thì

⟦folio 38⟧

$$L_{\max} = \frac{v_0^2}{g} \sin 2\varphi_b = \frac{v_0^2}{g} \sin 2 \left( \alpha + \arcsin \frac{\sqrt{g l} \sin 2\alpha}{v_0} \right).$$

S. Krotov

F679. Một sợi dây zeroch không giãn có mật độ tuyến tính q và chiều dài L được ném qua khối sao cho chiều dài một vùng của các đầu treo bằng $l(l < L/2)$. Khối nằm trên trục ngang là một vòng mỏng có khối lượng m và bán kính r đặt trên các kim đan nhẹ (xem hình). Hệ được giữ ở trạng thái nghỉ rồi thả ra. Tìm lực ép lên trục tại thời điểm đầu tiên. Có rất ít va chạm giữa trục và khối.

Ba lực tác dụng lên hệ khối + dây: phản lực $\vec{R}$ trong trục của khối và lực trọng lượng $m\vec{g}$ và $M\vec{g}$ ($M = \rho L$ là khối lượng của sợi dây). Theo định luật thứ ba của Newton, lực $\vec{N}$ của áp suất lên trục khối có giá trị tuyệt đối bằng $|\vec{R}|$.

Viết phương trình chuyển động của khối tâm của hệ dưới dạng hình chiếu trên trục $OX$ và $OY$ (xem hình):

$$\begin{align*}
(M + m)g &= R_x = (M + m)A_x, \\
R_y &= (M + m)A_y
\end{align*}$$

($A_x$ và $A_y$ là hình chiếu của gia tốc khối tâm). Vì dây không giãn và không trượt trên vật nên gia tốc của tất cả các điểm của dây và vật tại thời điểm đầu tiên sẽ bằng giá trị tuyệt đối (tốc độ ban đầu của hệ bằng 0 và các điểm của dây nằm trên vòng chưa thu được thành phần gia tốc hướng tâm).

Gia tốc $\vec{A}$ của khối tâm của hệ có liên quan đến gia tốc $\vec{a}_i$ của tất cả các điểm $i$ của nó theo hệ thức

$$M\vec{A} = \sum_i m_i \vec{a}_i,$$

trong đó $M$ là khối lượng của hệ, $m_i$ là khối lượng của điểm $i$ của nó. Chúng ta hãy viết mối quan hệ này cho hệ thống của mình dưới dạng hình chiếu trên trục $OX$ và $OY$.

Trong phép chiếu trên trục $OX$

$$-M_{AC}a + M_{BD}a = (M + m)A_x,$$

vì tổng đóng góp của tất cả các sản phẩm $M_{i(AB)}\vec{a}_i$ (từ các điểm dây nằm trên phần $AB$) và $m_i\vec{a}_i$ (từ các điểm vòng) trong các hình chiếu lên trục $OX$ bằng 0; điều này rõ ràng từ các tin nhắn của Symmetrine. Trong phép chiếu lên trục $OY$, chỉ có tích $M_{i(AB)}\vec{a}_i$ đóng góp. Để tìm hình chiếu lên trục $OY$ của vectơ $\sum_i M_{i(AB)}\vec{a}_i$, chúng ta phải tính tổng các vectơ $M_{i(AB)}\vec{a}_i$, có tính đến việc tại mỗi điểm gia tốc hướng tiếp tuyến với vòng (hãy nhớ rằng vận tốc ban đầu bằng 0). Tổng kết này (tự làm) sẽ dẫn chúng ta đến kết quả sau:

$$\frac{2}{\pi} M_{AB}a = (M + m)A_y.$$

Chúng ta hãy thay thế các biểu thức thu được cho $(M + m)A_x$ và $(M + m)A_y$ thành (*) và tìm $R_x$ và $R_y$:

$$R_x = (M + m) \left( g - \frac{M_{BD} - M_{AC}}{M + m} a \right),$$

$$R_y = \frac{2}{\pi} M_{AB}a.$$

Để xác định gia tốc $a$, chúng ta viết phương trình chuyển động của từng phần riêng lẻ của hệ:

$$M_{BD}g - T_B = M_{BD}a,$$

$$T_A - M_{AC}g = M_{AC}a,$$

$$T_B - T_A = (M_{AB} + m)a,$$

trong đó $\vec{T}_A$ và $\vec{T}_B$ là lực căng của dây tại các điểm $A$ và $B$ (xem hình). (Để thu được phương trình cuối cùng, hãy xem xét chuyển động của từng phần của sợi dây trong tiết diện $AB$ và vòng dây.) Từ các phương trình này, người ta tìm thấy:

$$a = \frac{M_{BD} - M_{AC}}{M + m} g.$$

Như vậy,

$$R_x = (M + m) \left( g - \frac{(M_{BD} - M_{AC})^2}{(M + m)^2} g \right),$$

⟦folio 39⟧

$$R_y = \frac{2}{\pi} M_{AB} \frac{M_{BD} - M_{AC}}{M + m} g.$$

Do đó, hình chiếu của lực $\vec{N}$ áp suất lên trục tại thời điểm đầu tiên là bằng nhau

$$-N_x = (\varrho L + m) \left( 1 - \frac{(L - \pi r - 2l)^2 \varrho^2}{(L \varrho + m)^2} \right) g,$$

$$-N_y = 2r \varrho \frac{(L - \pi r - 2l) \varrho}{L \varrho + m} g.$$

M. Efroimsky

F680. Một vòng mỏng có bán kính $R$ có thể được sửa chữa bằng một thanh tròn $A$, song song với trục của vòng (xem hình). Vòng được gắn một vòng đệm nhỏ $B$ có khối lượng $m$, vòng đệm này có thể di chuyển dọc theo vòng mà không có ma sát. Cái vòng cùng với quả bóng nói chung bị lệch khỏi vị trí cân bằng một góc $\varphi_0$ và được thả ra. Xác định sự phụ thuộc của lực tương tác giữa quả bóng và vòng vào góc $\varphi$ tạo bởi vectơ bán kính OA với phương thẳng đứng.

Hãy xem xét sự chuyển động của hai hệ thống:

hệ I - một vòng đệm được treo trên một sợi có chiều dài $2R$ (ma trận toán học); khối lượng máy giặt $m$;

hệ II - một vòng có bán kính $R$ với vòng đệm có khối lượng $m$ được gắn vào nó ở điểm thấp nhất.

Chúng ta làm lệch hệ khỏi vị trí cân bằng một góc $\varphi_0$ rồi thả nó ra. Do định luật bảo toàn năng lượng nên hệ sẽ dao động điều hòa với biên độ bằng nhau. Chúng ta hãy so sánh tốc độ mà các quả bóng sẽ có (trên sợi chỉ và trên vòng) ở một góc lệch so với phương thẳng đứng bằng $\varphi$.

Từ định luật bảo toàn năng lượng cho hệ I -

$$mg \cdot 2R(1 - \cos \varphi_0) = mg \cdot 2R(1 - \cos \varphi) + \frac{mv^2}{2},$$

cho hệ thống II -

$$mg \cdot 2R(1 - \cos \varphi_0) + Mg(R + R(1 - \cos \varphi_0)) = mg \cdot 2R(1 - \cos \varphi) + Mg(R + R(1 - \cos \varphi)) + \frac{m(v')^2}{2} + 2\frac{M\left(\frac{v'}{2}\right)^2}{2}$$

(M là khối lượng của vòng, $v'$ là tốc độ của quả bóng, $v'/2$ là tốc độ tâm của vòng, $2M\left(\frac{v'}{2}\right)^2/2$ là động năng của vòng) tìm được

$$v^2 = 4Rg(\cos \varphi - \cos \varphi_0),$$

$$(v')^2 = 4Rg(\cos \varphi - \cos \varphi_0).$$

Chúng tôi thấy điều đó $v = v'$. Do đó, trong các hệ thống đang được xem xét, quỹ đạo chuyển động của các quả bóng và vận tốc tức thời của các quả bóng trùng nhau (nhân tiện, từ đây, tính đồng bộ của các dao động của hệ thống I và II diễn ra). Vì vậy, các điều kiện tức thời của vòng đệm là như nhau. Do đó, ở giá trị tuyệt đối, giá trị tức thời của lực tương tác giữa vòng và vòng đệm cố định trên nó sẽ đúng bằng giá trị tức thời tương ứng của lực căng của sợi chỉ $T(\varphi)$ của ma trận toán học có chiều dài $2R$. Hãy tìm $T(\varphi)$.

Hãy viết phương trình chuyển động của quả cầu trên sợi dây:

$$T(\varphi) - mg \cos \varphi = \frac{mv^2}{2R}.$$

Thay thế kết quả lời giải $v^2$, chúng ta tìm thấy $T(\varphi)$:

$$T(\varphi) = mg(3 \cos \varphi - 2 \cos \varphi_0).$$

Do đó, lực tác dụng từ cái vòng lên quả bóng gắn vào nó bất cứ lúc nào cũng hướng về tâm của cái vòng. Và điều này có nghĩa là nếu chúng ta đưa hệ thống đưa ra trong nhiệm vụ ra khỏi vị trí cân bằng, thì khi chuyển động xa hơn, quả bóng sẽ luôn bị che chắn so với vòng, bất kể nó có được cố định trên nó hay không. Do đó, lực tương tác giữa quả bóng và vòng bằng

$$N(\varphi) = mg(3 \cos \varphi - 2 \cos \varphi_0).$$

D. Belov
