---
id: 2025-11-12-kostin-zadacha-shutka-6c53473e
issue: kvant_2025_11-12
year: 2025
number: 11-12
title: Bài toán-đùa
authors:
  - Костин С. В.
rubric: raznoe
page_first: 16
page_last: 26
page_labels: 14, 20, 22, 23, 24
lang: vi
source: kvant_digital
extraction: vision
content_sha256: 2faa155eda4271bb803567cb0a148d54967060ad0f366e69cc6a330267f7e152
prompt_sha256: draft-1
translated_from: content/ru/2025/11-12/articles/05_kostin-zadacha-shutka-6c53473e.md
source_content_sha256: c8704c1771db94e10c68402ad4f70b283d8f4b3eb0c918871363b57e1110f694
translation_model: draft
translation_run: vi-draft-gaps-2026-11-04
translation_quality: draft
---

⟦folio 14⟧

Vấn đề đùa
Sử dụng hai mặt phẳng, ba điểm trừ và bốn mặt phẳng
lấy số 2026 - con số của năm tới.
S. Kostmin

⟦folio none⟧

---
running_head:
folio:
---

Bước đầu tiên là hỏi về đa thức $x^{2027}$.
Phương trình $P(x) = x^{2027}$ phải có ít nhất một nghiệm thực, vì nghiệm của phương trình này là nghiệm của đa thức $x^{2027} - P(x)$ bậc lẻ. Đối với bước cuối cùng, chúng ta có thể chỉ định $a$ sao cho tại $x > a$ $P(x) < x^{2027}$ sẽ thỏa mãn (thực sự, vì $a$ chúng ta có thể lấy nghiệm tối đa của phương trình của mình).
Tương tự, ở bước thứ hai chúng ta hỏi về đa thức $-x^{2027}$. Đối với hai nước đi cuối cùng, chúng ta sẽ biết $M$ sao cho mọi $x > M$ $-x^{2027} < P(x) < x^{2027}$ đều thỏa mãn.
Sử dụng thông tin này, ở bước thứ ba, chúng ta sẽ chọn đa thức $Q$ sao cho phương trình $P(x) = Q(x)$ phụ thuộc sẽ có ít nhất 2026 nghiệm. Sau đó, sau khi các căn $x_1 < x_2 < ... < x_{2026} < ...$ này được trao cho chúng tôi, chúng tôi khôi phục $P$ làm đa thức bậc duy nhất $\leq 2025$ lấy giá trị $Q(x_i)$ tại điểm $x_i$.
(Một đa thức $P$ như vậy thực sự là duy nhất: nếu có một đa thức $P_1$ khác có tính chất này, thì đa thức $P - P_1$ cấp $\leq 2025$ khác 0 sẽ có ít nhất 2026 nghiệm - một mâu thuẫn.)
Khi chọn $Q$ chúng ta sẽ sử dụng một thực tế nổi tiếng sau: với mọi số $x_1 < x_2 < ... < x_n$ và $y_1 < y_2 < ... < y_n$ đều tồn tại một đa thức $R$ sao cho $R(x_i) = y_i$ cho mọi $i = 1, 2, ..., n$. (Đa thức $R$ như vậy có thể được xây dựng dưới dạng đa thức Lagrange tích phân; trên thực tế, có một đa thức bậc duy nhất như vậy $\leq n - 1$.)
Vì vậy, hãy mô tả cách chúng tôi sẽ chọn $Q$ (biết rằng với $x > M$ $-x^{2027} < P(x) < x^{2027}$ là thỏa mãn). Đặt $x_1 < x_2 < ... < x_{2027} -$ là bất kỳ số nào lớn hơn $M$; chúng ta cũng hãy đặt
$$y_i = (-1)^i x_i^{2027}$$ cho $i = 1, 2, ..., 2027$.
Đặt $Q$ sao cho $Q(x_i) = y_i$ cho tất cả các $x_i$ và $y_i$, $i = 1, 2, ..., 2027$ được chọn. Việc lựa chọn $y_i$ được thực hiện sao cho nếu $i$ chẵn thì $Q(x_i) > P(x_i)$ sẽ được thực thi và nếu $i$ là số lẻ thì $Q(x_i) < P(x_i)$ sẽ được thực thi. Sau đó, ở cuối mỗi tích phân $(x_i; x_{i+1})$ (trong đó $i = 1, 2, ..., 2026$ đa thức $P - Q$ nhận các giá trị khác dấu, và do đó (nhờ định lý giá trị khoảng cho các hàm liên tục), có nghiệm trên khoảng $(x_i; x_{i+1})$. Vì vậy, chúng ta đã chứng minh được điều cần thiết: phương trình $P(x) - Q(x) = 0$ (hoặc, tương đương, $P(x) = Q(x)$) có ít nhất 2026 gốc Như vậy, bài toán lời giải.
Có thể chứng minh rằng hai bước di chuyển sẽ không đủ để đảm bảo sự phục hồi của đa thức.
K. Sukhov, L. Shatunov

M2857*. Chúng ta đứng cùng một hàng với một hoa nhà thông thái, mỗi người chỉ nhìn thấy những người theo sau mình ở hàng sau, tôi. Cái đầu tiên chúng ta thấy, phần còn lại rất đơn giản, cái thứ hai chúng ta thấy mục nát và có màu sắc, và cái thứ ba chúng ta chỉ thấy có màu sắc. Ma quỷ có 100 chiếc mũ được đánh số từ 1 đến 100, hắn đội cho mỗi nhà thông thái một chiếc mũ và quay thêm 96 chiếc mũ. Sau đó, từng nhà thông thái (lần lượt: người đầu tiên, người thứ hai, v.v.) gọi lớn vào số, cố gắng khớp với số chiếc mũ của mình. Những con số được đề cập không nên lặp lại. Khi tất cả các nhà thông thái đã lên tiếng, họ cởi mũ ra và kiểm tra xem ai trong số họ đã thắng. Các nhà hiền triết có thể hành động để ít nhất ba trong số chúng được hoàn thành không?

Đáp số: họ có thể.
Xét một đồ thị hoàn chỉnh có 100 đỉnh, trong đó mỗi số mũ có thể được liên kết với một đỉnh. Các cạnh của biểu đồ hoàn chỉnh này có thể được hiển thị bằng 99 màu sao cho các cạnh của mỗi màu tạo thành một sự khớp hoàn chỉnh (tức là 50 cạnh không có đỉnh chung). Hãy để các nhà thông thái sửa màu xương sườn này trước.
Hãy để chúng tôi biểu thị bằng $a_1, a_2, a_3, a_4$ số mũ của nhà thông thái. Nhà hiền triết thứ nhất và thứ hai nhìn thấy số $a_3$ và $a_4$, nghĩa là họ biết màu của cạnh $a_3a_4$. Giả sử cạnh này có màu đỏ. Nhà hiền triết đầu tiên gọi số đỉnh $a'_1$, được nối bằng cạnh màu đỏ với đỉnh $a_2$ (và rất có thể ông ta sẽ không đoán được số của mình $a_1$). Người thứ hai nghe thấy số $a'_1$ và gọi tên số (thống nhất) của đỉnh nối với $a'_1$ bằng cạnh màu đỏ, từ đó đoán được số mong muốn $a_2$.

⟦folio 20⟧

---
running_head:
folio:
---

Hai điều kiện còn lại gọi là số $a_1'$ và $a_2$, rõ ràng là cạnh $a_3a_4$, giống như cạnh $a_1'a_2$, có màu đỏ. Nhà hiền triết thứ ba, nhìn thấy số $a_4$, gọi số $a_3$, sau đó, nhà hiền triết thứ tư, nghe thấy số $a_3$, gọi số $a_4$. Cả hai đều đoán đúng.

K. Kokhas, A. Lamyshev

F2861. Đúng trưa, từ bến A đến bến B, camera và tàu biển đã đến vị trí sông. Tốc độ của máy ảnh và thuyền so với mặt nước lần lượt là $v_1 = 40$ km/h và $v_2 = 25$ km/h. Tốc độ thay đổi của sông là $u = 5$ km/h. Khi camera đã quét sạch toàn bộ tuyến đường, một làn sương mù dày đặc rơi xuống sông, do đó thuyền trưởng quyết định không mạo hiểm và nhấn chìm đám sương mù. Máy ảnh tiếp tục di chuyển, ở vị trí khác và không di chuyển về phía bờ. Sự trôi dạt trong sương mù tiếp tục trong 30 phút cho đến khi sương mù tan. Sau đó, máy ảnh không thay đổi hướng chuyển động, tiếp tục di chuyển với tốc độ ban đầu so với mặt nước. Trong suốt thời gian này, Morristeem tiếp tục lái con thuyền trong tình trạng nguy hiểm và rủi ro của riêng mình mà không hề giảm tốc độ. Máy ảnh và thuyền đến bến B cùng lúc.
a) Máy ảnh và thuyền đi đến bến B lúc mấy giờ?
b) Khoảng cách tối đa (dọc theo dòng sông) giữa máy ảnh và thuyền trong quá trình chuyển động là bao nhiêu?

Chúng ta hãy đưa ra các ký hiệu sau: $t_1$ – thời gian chuyển động trước sương mù, $t$ – thời gian chuyển động trong sương mù, $t_2$ – thời gian chuyển động sau sương mù. Theo điều kiện bài toán, ta thu được hệ phương trình sau:

$$\begin{align*}
(v_1 + u)t_1 &= \frac{1}{3}(v_2 + u)(t_1 + t + t_2), \\
(v_1 + u)(t_1 + t_2) + ut &= (v_2 + u)(t_1 + t + t_2).
\end{align*}$$

Để đơn giản hóa việc tính toán, hãy thay thế các giá trị bằng số của tốc độ. Sau khi biến đổi đơn giản, hệ phương trình sẽ có dạng

$$\begin{align*}
7t_1 - 2t_2 &= 2t, \\
3t_1 - 3t_2 &= 5t.
\end{align*}$$

Giải hệ phương trình, ta tìm được

$$t_1 = \frac{16}{27}t, t_2 = \frac{29}{27}t.$$

Khi tính đến điều này, chúng tôi tìm thấy toàn bộ thời gian di chuyển từ bến tàu A đến bến tàu B:

$$T = t_1 + t + t_2 = \frac{8}{3}t = 80 \text{ мин} = 1 \text{ ч} 20 \text{ мин}.$$

Vì vậy, tàu cao tốc và thuyền sẽ đến Bến B lúc 13h20.

Lúc sương mù giăng trên sông thì khoảng cách giữa thuyền và thuyền là

$$s_1 = (v_1 - v_2)t_1 \approx 4,4 \text{ км},$$

và khi sương mù tan đi -

$$s_2 = v_2(t_1 + t) - v_1t_1 \approx 8,1 \text{ км}.$$

Như vậy, khoảng cách tối đa giữa thuyền và thuyền khi di chuyển là khoảng 8,1 km.

D. Podlesyany, A. Bychikov

F2862. Một hình nón khối lượng m có góc lệch 2α được cuộn từ một tờ giấy có hình dạng khu vực hành trình. Hình nón được đặt nằm ngang trên mặt bàn; tờ giấy sẽ không bị đuổi ra ngoài. Không có ma sát giữa tờ giấy và mặt bàn. Để hình nón không bị vỡ ra dưới tác dụng của lực mềm, một vài lực có độ lớn F hướng tiếp tuyến với chu vi của đáy hình nón tác dụng lên các mép giấy nằm trên đường cắt (xem hình). Sự phân bố khối lượng trên tấm sitai-me là đồng đều. Bỏ qua mọi tác dụng liên quan đến sự uốn, tìm giá trị của lực F.

Lời giải 1. Hãy áp dụng phương pháp dịch chuyển ảo: tưởng tượng hình nón hơi dốc. Vì năng lượng được bảo toàn nên ta có

$$\Delta A_F + \Delta A_N = \Delta W,$$

trong đó $\Delta A_F$ là công của các ngoại lực, $\Delta A_N$ là công của các phản lực hỗ trợ, và $\Delta W$ là độ biến thiên của thế năng. Phản lực bình thường của giá đỡ công trình là không hoàn hảo

⟦folio 22⟧

---
running_head:
folio:
---

khu vực bằng $\Delta\theta = 2\pi/n$, thì đối với $\Delta\theta$ nhỏ hình chiếu của lực bằng $F\Delta\theta$.
Vì hình nón và mỗi cung của nó đứng yên, nên chúng ta viết điều kiện cân bằng mô men cho một hình nón tùy ý so với trục đi qua đỉnh của hình nón và vuông góc với đường phân giác của góc ở tâm của nó:
$$\Delta m g \cdot \frac{2 R}{3} + F \Delta\theta \cdot H = \Delta N \cdot R.$$
Cuối cùng chúng tôi nhận được
$$F = \frac{m g}{6 \pi} \mathrm{tg} \alpha.$$
E. Kuznetsov

F2863. Ống hình chữ L được lấp đầy hoàn toàn bằng vết lõm, như thể hiện trong hình 1. Chiều dài của mỗi đoạn uốn ống

Hình 1

$L = p_0 / (3 \rho g)$, trong đó $p_0$ là áp suất khí quyển, $\rho$ là mật độ ruth, $g$ là gia tốc áp suất tự do. Ống bắt đầu chuyển động theo phương ngang với gia tốc tăng dần $a$. Diện tích phần ống $S$ nhỏ ($\sqrt{S} \ll L$). Áp suất hơi của ruthami có thể được xác nhận.
a) Xác định thể tích chảy ra khỏi ống khi gia tốc bằng $g$. Áp suất ở đầu bên trái của phần nằm ngang của ống tại thời điểm này là bao nhiêu?
b) Tính thể tích toàn phần của không khí trong ống với gia tốc 3g.
Cho sơ đồ phân bố hình của ruthami trong ống.
b) Trả lời các câu hỏi ở điểm b) đối với trường hợp $a = 4g$.

Một trong những cách để tìm lượng dòng chất lỏng là chuyển sang hệ thống báo cáo ống phi quán tính và đưa ra khả năng tăng tốc hiệu quả của áp suất tự do. Khi đó các mức áp suất bằng nhau trong bình vuông góc với $\vec{g}_{\exists\phi}$. Thủy ngân sẽ chảy qua đầu gối phải, điểm trên của nó sẽ tương ứng với áp suất khí quyển. Do dòng rutami chảy vào, mức độ rutami ở đầu gối trái sẽ trở nên rõ ràng. Hãy vẽ một đường vuông góc với $\vec{g}_{\exists\phi}$ (hình 2) từ điểm trên cùng của đầu gối phải. Giao điểm của đường này với đầu gối trái sẽ tương ứng với mức áp suất khí quyển ở đầu gối trái, tức là ranh giới giữa dòng sông và khí quyển. Có thể dễ dàng nhận thấy từ các thông điệp hình học rằng đường vẽ đi qua giao điểm của khuỷu thẳng đứng bên trái và phần nằm ngang của ống. Điều này có nghĩa là thể tích thủy ngân đổ ra khỏi ống trong trường hợp này bằng

$V_1 = SL$.

Hãy tính áp suất ở góc dưới bên trái của ống thông qua độ giảm áp suất ở phần nằm ngang bên trái của ống:

$p = p_0 - \rho a L = 3 \rho g L - \rho g L = 2 \rho L > 0$.

Lưu ý rằng việc tách các thanh ra khỏi góc ống ở vị trí này chỉ có thể xảy ra khi áp suất giảm xuống 0. Điều này có thể xảy ra khi đạt được gia tốc của ống

$a_{\kappa p} = \frac{p_0}{\rho L} = 3 g = a_2$.

Sau đó, khi ống tăng tốc từ $a_1 = g$ lên $a_2 = 3 g$, sự phân tách không xảy ra.

Nếu vượt quá gia tốc $a_1$, cột xương ở khuỷu ngang sẽ tách thành hai phần tại điểm nối với khuỷu thẳng đứng bên trái của ống. Khoang kết quả sẽ lấp đầy không khí. hình 3 hiển thị vị trí của các thanh trong ống khi tăng tốc $a_2$. Có thể dễ dàng tính toán về mặt hình học rằng chiều dài phần nằm ngang của ống chứa đầy không khí sẽ là

$l_2 = \frac{2}{3} L$.

⟦folio 23⟧

---
running_head:
folio:
---

Khi đó tổng thể tích không khí trong ống với gia tốc này là
$$V_{\text{в2}} = \left(L + l_2\right) S = \frac{5}{3} L S.$$
Khi gia tốc lớn hơn $a_2$, tay cầm sẽ tách ra khỏi đầu bên trái của ống.
Khi đạt gia tốc $a_3 = 4g$ ở phần nằm ngang bên trái của ống phải có một tay cầm dài như thế này
$$l_{\text{лев}} = \frac{p_0}{\rho a_3} = \frac{3\rho g L}{4\rho g} = \frac{3L}{4}.$$
Sẽ có chân không trong 1/4 còn lại của ống. Hãy tính tổng chiều dài của giá đỡ tay cầm ở phần nằm ngang của ống. Để làm điều này, chúng ta tìm chênh lệch áp suất giữa đầu trên bên phải của ống và đầu dưới bên trái:
$$p_0 = -\rho g L + \rho a_3 l_{\text{гор}} = -\rho g L + 4\rho g l_{\text{гор}}.$$
Do đó tổng chiều dài của tay cầm ở phần nằm ngang của ống sẽ là
$$l_{\text{гор}} = \frac{p_0 + \rho g L}{4\rho g} = \frac{3\rho g L + \rho g L}{4\rho g} = L.$$
Theo kết quả thu được, chúng ta có thể giả sử vị trí của tay cầm trong ống với gia tốc này như trong hình 4. Áp suất không khí ban đầu trên băng ghế nằm ngang là $p_0 = 3\rho g l$, và áp suất cuối cùng là $4\rho g l$. Theo định luật Boyle-Mariotte, chiều dài của cột không khí phải bằng
$$l_3 = \frac{p_0}{4g L} l_2 = \frac{3}{4} \frac{2}{3} L = \frac{L}{2}.$$
Tuy nhiên, ở vị trí đề xuất của tay cầm trong ống, chiều dài của cột không khí ở phần nằm ngang là $3L/4$ - có sự mâu thuẫn. Nếu chúng ta giả sử rằng với gia tốc $4g$, phân bố tay cầm hiển thị ở hình 4 đã được thiết lập, thì tay cầm ở phần nằm ngang của ống sẽ chia thành hai phần tại điểm nối của khuỷu thẳng đứng bên trái của ống với phần nằm ngang của nó. Do gia tốc của ống thay đổi dần dần nên quá trình bẻ thanh tay cầm ngang thành nhiều phần sẽ diễn ra liên tục. Sự phân bố của tay cầm trong ống, thỏa mãn tất cả các điều kiện được mô tả, được thể hiện ở hình 5.
Tổng chiều dài của lượng không khí giữa các giọt nước trong phần nằm ngang của ống là $l_{\text{мк}} = L/4$. Khi đó thể tích không khí trong ống sẽ là
$$V_{\text{3в}} = \left(l_3 + L + l_{\text{мк}}\right) S = \frac{7}{4} L S.$$
Xin lưu ý rằng khi tăng tốc thêm, thậm chí tăng nhẹ, vô lăng bắt đầu nhanh chóng tuột ra khỏi đầu gối phải. Hơn nữa, việc tăng nhẹ ở khuỷu thẳng đứng sẽ dẫn đến giảm áp suất của cột chất lỏng thẳng đứng, trong khi áp suất ở phần nằm ngang của ống sẽ không thay đổi.
Yu. Chernikov
F2864. Gương phản xạ của Newton là một gương tương tự của nhóm thị giác của Kenler. Gương cầu quân sự $M_1$ (hình 1), là một vật thể melextra-REFLECTOR, tạo thành hình ảnh thật của ánh sáng thiên đường trong mặt phẳng tiêu cự. Hình ảnh này được xem qua quận $L$, vai trò của quận này được thực hiện bởi ống kính của chính quận đó. Cũng có thể nhìn thấy một gương lặp phẳng $M_2$ tại hình. Chiếc gương làm chệch hướng ánh sáng hội tụ phản chiếu (từ gương chiến binh) sang một bên.

⟦folio 24⟧

---
running_head:
folio:
---

a) Gọi bán kính của gương cầu là R và tiêu cự của đường thẳng là F. Độ phóng đại góc của dụng cụ là bao nhiêu?
Gợi ý. Độ phóng đại góc γ của một thiết bị quang học dùng để quan sát các vật ở xa được gọi là tỷ lệ γ = α'/α, trong đó α' là góc mà vật được quan sát qua thị kính, α là góc nhìn bằng mắt thường khi nhìn.
b) Một trong những kính thiên văn lớn nhất thế giới của Đài quan sát vật lý thiên văn đặc biệt PAH (chế tạo theo sơ đồ Newton) có tiêu cự nhìn vật F = 300 m. Góc xoay tối đa cho phép của melescon φ_max là bao nhiêu do lựa chọn nền đài quan sát, tại đó độ phân giải của khuôn δ = 50 dòng/mm vẫn được sử dụng đầy đủ khi tạo hình các vật thể thiên văn? Khi hình thành, phim được đặt ở mặt phẳng tiêu điểm của vật thể bằng cách sử dụng độ phơi sáng mờ lên đến vài phút.
c) Cho kính thiên văn dao động với biên độ 10^-6 rad do một hàng từ đài quan sát của công trình xây dựng đi qua. Kích thước của ảnh trên phim sẽ là bao nhiêu nếu kích thước góc của nguồn là 10^-7 rad?

a) Khi quan sát một vật ở xa, thấu kính cho ảnh thật của nó trong mặt phẳng tiêu cự. Hình ảnh này được nhìn qua thị kính, như thể qua kính lúp. Nếu các mặt phẳng tiêu cự của thấu kính và thị kính trùng nhau, thì chùm tia tới song song sẽ biến thành chùm tia đi song song, nhưng nói chung, đi ở một góc khác với chùm tia chính.
