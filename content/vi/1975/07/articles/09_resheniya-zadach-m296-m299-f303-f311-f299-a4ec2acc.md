---
id: 1975-7-resheniya-zadach-m296-m299-f303-f311-f299-a4ec2acc
issue: kvant_1975_7
year: 1975
number: "7"
title: Lời giải bài toán M296—M299; F303—F311, F299
rubric: zadachnik-kvanta
rubric_sub: Задачник «Кванта»
page_first: 44
page_last: 52
page_labels: 42-50
tag: 9HEV
lang: vi
source: kvant_digital
extraction: vision
content_sha256: a59dcd94392fab9a699a8496da1c9dc0ebe6de0bfb1b0dde7da05a47c0b28509
prompt_sha256: draft-1
translated_from: content/ru/1975/07/articles/09_resheniya-zadach-m296-m299-f303-f311-f299-a4ec2acc.md
source_content_sha256: 85d50e5657a08c416736a1f8cf603910259b29ddccadc8daa1eb1dd34c4156d9
translation_model: draft
translation_run: vi-draft-2026-10-31
translation_quality: draft
---

⟦folio 42⟧

⟦rubric⟧
Lời giải bài toán

## Lời giải bài toán
M296 — M299; F303 — F311, F299

**M296.** Một bảng n × n chứa n2 số có tổng không âm. Chứng minh rằng bạn có thể sắp xếp lại các cột của bảng sao cho tổng n số theo đường chéo đi từ dưới bên trái lên trên bên phải không âm.

⟦figure⟧
Hình 1.

**M299.**\*) Để làm gì n có thể đặt một n-giác đều trên một tờ giấy thành một đường thẳng sao cho tất cả các đỉnh đều nằm trên các đường thẳng đó? (Các đường thẳng là các đường thẳng song song có khoảng cách bằng nhau.)

⟦column⟧

Hãy gọi phép biến đổi bảng này là *dịch chuyển theo chu kỳ*: cột đầu tiên được chuyển đến vị trí của cột thứ 2, cột thứ 2 được chuyển đến vị trí của cột thứ 3, . . . , cuối cùng, cái cuối cùng, thứ n - thay cho cái thứ nhất. Hãy biểu thị bằng $s_0$ tổng các số nằm trên đường chéo của bảng (trong các ô màu đỏ trong Hình 1), bằng $s_1$ - tổng các số sẽ rơi trên đường chéo sau một phép dịch chuyển theo chu kỳ (trong các ô màu xanh), bằng $s_2$ - tổng các số sẽ rơi trên đường chéo nếu phép dịch chuyển theo chu kỳ được lặp lại một lần nữa (trong các ô màu vàng) và nói chung, bằng $s_k$ - tổng các số sẽ rơi trên đường chéo nếu phép dịch chuyển theo chu kỳ được lặp lại một lần nữa (trong các ô màu vàng) rơi trên đường chéo nếu phép dịch chuyển tuần hoàn được thực hiện k lần. Rõ ràng tổng của tất cả các số trong bảng bằng

$$s = s_0 + s_1 + \ldots + s_{n-1},$$

bởi vì nếu bạn thực hiện dịch chuyển theo chu kỳ 0, 1, . . . , n - 1 lần thì trong thời gian này mỗi số trong bảng sẽ nằm trên đường chéo đúng một lần (và nếu thực hiện n lần thì sẽ được cách sắp xếp ban đầu).

Theo điều kiện, s không âm, do đó, một số $s_k$ phải không âm. Sau khi thực hiện phép dịch tuần hoàn k lần, chúng ta thu được hoán vị cần thiết của các cột.

◆

Giả sử rằng chúng ta đã đặt được một hình n-gon thông thường trên giấy có dòng kẻ. Gọi O là tâm của đa giác này. Chúng ta hãy xoay mặt phẳng qua một góc $360°/n$ với tâm tại điểm O và vẽ cả đường thẳng song song trước đó và mới (kết quả sau khi quay) trong một bản vẽ (Hình 2; không cần phải vẽ n-giác hai lần, vì nó thẳng hàng với chính nó sau một phép quay như vậy). Bây giờ mỗi đỉnh của n-giác nằm ở giao điểm của hai đường lưới, tức là n-giác được đặt sao cho tất cả các đỉnh của nó rơi vào các nút của một mạng nhất định; nhưng, như đã được chứng minh trong bài viết của A. A. Egorov “Lưới và đa giác đều” («Kvant», 1974, Số 12), điều này chỉ có thể xảy ra với n=3,4 hoặc 6.

Như vậy, chỉ với n này mới có thể đặt một n-giác thông thường trên giấy có dòng kẻ.

N. B. Vasiliev

⟦figure⟧
Hình 2.

---
*) Lời giải bài toán M297 có trong ghi chú của V. M. Fishman “Lời giải bài toán sử dụng các phép biến đổi hình học”, bài toán M298 - trong ghi chú của V. N. Vaguten “Đóng phân số”, sẽ được xuất bản vào «Kvant» Số 8, 1975.

⟦folio 43⟧

**F303.** *Một nguồn sáng điểm nằm ở một khoảng cách nào đó dưới một thấu kính thu mỏng (Hình 3). Nên lắp gương phẳng ở đâu và như thế nào để một chùm ánh sáng song song ló ra khỏi thấu kính theo hướng mũi tên chỉ? Xây dựng đường đi của tia.*

⟦column⟧

Gọi $F'F''$ là tiêu cự của thấu kính. Chúng ta hãy vẽ một trục quang phụ $AA'$ song song với hướng được chỉ định bởi mũi tên (xem Hình 3). Nếu nguồn sáng nằm trong mặt phẳng tiêu cự của thấu kính tại điểm $S'$ giao điểm của nó với trục $AA'$, thì thấu kính sẽ thu các tia của nó thành một chùm tia song song hướng dọc theo trục $AA'$, tức là một chùm ánh sáng song song phát ra từ thấu kính theo hướng chỉ bởi mũi tên.

Trong trường hợp của chúng ta, nguồn của thấu kính sẽ là ảnh của nguồn $S$ trong gương phẳng. Để hình ảnh này

⟦figure⟧
Hình 3.

ở điểm $S'$, gương phải đặt ở giữa đoạn $SS'$ vuông góc với nó. Đường đi của tia được minh họa trên Hình 3.

◆

**F304.** *Máy bơm cung cấp khối lượng $m$ nước mỗi giờ lên độ cao $H$ thông qua một đường ống có đường kính $d$. Công suất của máy bơm $N$ là bao nhiêu? Có thể cung cấp khối lượng $m$ nước mỗi giờ lên độ cao $H$ bằng máy bơm có công suất thấp hơn không?*

⟦figure⟧
Hình 4.

⟦column⟧

Trong thời gian $\Delta t$, máy bơm cung cấp một khối nước $m\Delta t$ lên độ cao $H$, thực hiện công $A$ bằng độ biến thiên cơ năng của nước. Vì nước bên dưới không có động năng và máy bơm “đẩy” nó qua đường ống với một tốc độ nhất định $v$, nên

$$A = \frac{(m\Delta t)v^2}{2} + (m\Delta t)gH.$$

Do đó, công suất bơm là $N = \dfrac{mv^2}{2} + mgH$.

Hãy tìm tốc độ $v$. Trong thời gian $\Delta t$, một lượng nước $V = v\Delta t\dfrac{\pi d^2}{4}$ đi qua mặt cắt ngang của một ống có diện tích $S = \dfrac{\pi d^2}{4}$, khối lượng của nó bằng $v\Delta t\dfrac{\pi d^2}{4}\rho$ ($\rho$ là mật độ của nước). Mặt khác, khối lượng này bằng $m\Delta t$, tức là $v\dfrac{\pi d^2}{4}\rho = m$, do đó $v = \dfrac{4m}{\pi d^2\rho}$.

Như vậy công suất bơm

$$N = \frac{8m^3}{\pi^2 d^4\rho^2} + mgH.$$

Có thể cung cấp cùng một khối lượng nước mỗi giờ cho cùng một độ cao $H$ bằng cách sử dụng máy bơm có công suất thấp hơn không? Từ biểu thức cho $N$, rõ ràng là đường kính của ống $d$ càng lớn thì công suất bơm cần thiết càng ít.

Nhưng bạn có thể giảm lượng điện năng cần thiết mà không thay đổi giá trị của các tham số được chỉ định trong điều kiện bài toán. Hãy cắt toàn bộ phần trên của ống ở một độ cao nhất định $h \ll H$. Để nước chảy ra khỏi phần còn lại của đường ống

⟦folio 44⟧

với tốc độ nào đó $u$ (xem Hình 4).

Công suất bơm cần thiết cho việc này là $N' = \frac{mu^2}{2}$ (vì $h \ll H$, thế năng $mgh$ bị bỏ qua). Để nước dâng lên độ cao $H$ thì tốc độ của nước khi ra khỏi đường ống phải không nhỏ hơn $u = \sqrt{2gH}$. Do đó, có thể cung cấp một khối lượng nước $m$ mỗi giờ lên độ cao $H$ bằng máy bơm có công suất

$$N' = m \frac{u^2}{2} = mgH < N.$$

F305. Một mao quản thủy tinh hình chữ L có bán kính $r$, được làm ướt hoàn toàn bằng nước, được hạ xuống bình chứa nước (Hình 5). Sự phụ thuộc của hệ số hàm lượng nước bề mặt vào nhiệt độ được thể hiện trên Hình 6. Toàn bộ nước sẽ bị dịch chuyển khỏi bình trong khoảng nhiệt độ nào nếu $r=0,1$ mm, $h=14,1$ cm $uH=15$ cm? Bỏ qua độ dày của tấm kính.

Để nước chảy ra khỏi bình qua mao quản, trước hết nước phải dâng lên dọc theo khuỷu tay phải của mao quản đến mặt cắt ngang của nó. Tại thời điểm ban đầu, độ cao dâng lên phải bằng $h$ và ở cuối, khi gần như toàn bộ nước đã chảy ra khỏi bình, chất lỏng sẽ dâng lên độ cao $h+l$, trong đó $l$ là chiều cao của mực nước ban đầu trong bình. Điều này có thể thực hiện được nếu hệ số sức căng bề mặt $\sigma$ sao cho chiều cao của nước dâng lên trong mao quản có bán kính $r$ không nhỏ hơn $h+l$, tức là

$$\frac{2\sigma}{\rho gr} > h+l,$$ hoặc $\sigma > \frac{1}{2} \rho gr (h+l).$

Khi dâng lên đầu gối phải, nước tràn vào đầu gối trái, ở cuối hình thành một sụn lồi và có thể chứa một cột nước nhất định. Nước ở phần trên của mao quản (từ mặt cắt ngang đến mực nước trong bình) cân bằng nên các lực bổ sung dưới mặt khum phải giữ một cột nước có độ cao $H+l$ ở thời điểm ban đầu và độ cao $H$ ở thời điểm cuối cùng. Bán kính của sụn khớp không được nhỏ hơn bán kính của mao mạch $r$, nghĩa là áp suất bổ sung dưới sụn khớp không thể lớn hơn $\frac{2\sigma}{r}$. Do đó, nước sẽ chảy ra khỏi mao quản nếu áp suất hydro tăng trưởng lớn hơn áp suất bổ sung, nghĩa là

$$\rho g (H+l) > \frac{2\sigma}{r},$$ hoặc $\sigma < \frac{1}{2} \rho gr (H+l).$

Do đó, nước sẽ chảy ra khỏi bình qua mao quản nếu

$$\frac{1}{2} \rho gr (h+l) < \sigma < \frac{1}{2} \rho gr (H+l),$$

hoặc

$$\frac{1}{2} \rho gr h < \sigma < \frac{1}{2} \rho gr H.$$

Để chuyển từ phạm vi giá trị hệ số sức căng bề mặt sang phạm vi nhiệt độ, chúng ta sử dụng biểu đồ như Hình 6. Từ biểu đồ cho thấy rõ sự phụ thuộc của $\sigma$ vào $T$ là tuyến tính, nghĩa là

$$\sigma = \sigma_0 + \alpha T,$$

ở đâu $\sigma_0 = 76 \text{ дин/cм}$. Do đó, ở nhiệt độ $T=20^{\circ}\text{C}$ $\sigma = 73 \text{ дин/cм}$,

⟦folio 45⟧

$$73 \text{ дин/см} = 76 \text{ дин/см} + \alpha \cdot 20 \text{град},$$
Ở đâu
$$\alpha = -0{,}15 \text{ дин/(см} \cdot \text{град)}.$$

Các giá trị biên của phạm vi $\sigma$ là

$$\sigma_{\min} = \frac{1}{2}\rho g r h = 70{,}5 \text{ дин/см},$$

$$\sigma_{\max} = \frac{1}{2}\rho g r H = 75 \text{ дин/см}.$$

Bây giờ hãy viết phương trình (*) cho nhiệt độ $T_{\max}$ và $T_{\min}$, tương ứng với các giá trị $\sigma_{\min}$ và $\sigma_{\max}$:
$$70{,}5 = 76 - 0{,}15\,T_{\max},$$
$$75 = 76 - 0{,}15\,T_{\min}.$$
Từ đây
$$T_{\max}\approx 36{,}7°C \quad \text{и} \quad T_{\min}\approx 6{,}7°C.$$

Vì vậy, toàn bộ nước sẽ chảy ra khỏi bình qua mao quản nếu
$$6{,}7°C < T < 36{,}7°C.$$

⟦figure⟧
Hình 7.

F306. Hình 7 thể hiện sơ đồ của một oát kế nhiệt $(r_1 \ll r,\ r_1 \ll R_{\mathrm{н}})$. Một sợi dây mỏng $AB$, được làm nóng bởi dòng điện, được ném qua một khối được kéo lên bởi một lò xo. Có một mũi tên gắn vào khối sẽ quay khi bạn xoay khối. Chứng minh rằng độ quay của mũi tên thiết bị tỉ lệ thuận với dòng điện $P$ tiêu thụ bởi tải $(R_{\mathrm{н}})$.

Hãy xem xét rằng: 1) lượng nhiệt mà dây nóng tỏa ra môi trường tỷ lệ thuận với chênh lệch nhiệt độ giữa dây và môi trường; 2) sự thay đổi điện trở của các đoạn dây $AB$ do độ giãn dài và sự thay đổi nhiệt độ của chúng là không đáng kể.

⟦figure⟧
Hình 8.

⟦column⟧

◆

Góc quay của con trỏ thiết bị tỷ lệ thuận với chênh lệch độ giãn dài của các phần dây $AC$ và $CB$. Các phần mở rộng này được xác định bởi dòng điện chạy qua các phần tương ứng.

Ta biểu thị bằng $I_0$ dòng điện chạy qua tải $R_{\mathrm{н}}$ và nối với nó là dòng điện $I_1$ và $I_2$ chạy qua các phần $CB$ và $AC$. Chúng ta hãy vẽ lại mạch điện để nối oát kế, như trong Hình 8. Vì điện trở của dây nhỏ hơn nhiều so với điện trở $r$ nên chúng ta sẽ giả sử rằng điện trở của các phần $AC$ và $CB$ của dây này được bao gồm trong các giá trị $r$, sao cho điện trở của các phần mạch $DC$ và $KC$ bằng $r$.

Vì điện áp ở điện trở $R_{\mathrm{н}}$ và ở điện trở $r$ của phần $KC$ bằng nhau nên

$$I_0 R_{\mathrm{н}} = I_1 r, \quad \text{или} \quad I_1 = I_0 \frac{R_{\mathrm{н}}}{r}.$$

Dòng điện $I_2 = \dfrac{U_{DC}}{r}$, trong đó $U_{DC}$ là điện áp tại phần $DC$. Nó bằng $U_{DC} = U_{KC} + I_3 r_1$, trong đó $U_{KC} = I_0 R_{\mathrm{н}}$ và

$$I_3 = I_0 + I_1 = I_0\left(1 + \frac{R_{\mathrm{н}}}{r}\right).$$

Sau đó

$$I_2 = I_0\left(\frac{R_{\mathrm{н}} r_1}{r^2} + \frac{r_1}{r} + \frac{R_{\mathrm{н}}}{r}\right).$$

Bây giờ chúng ta hãy xem độ giãn dài của dây có liên quan như thế nào với dòng điện chạy qua dây này. Ở trạng thái cân bằng nhiệt, lượng nhiệt tỏa ra trong dây bằng lượng nhiệt truyền vào môi trường:
$$I^2 R = k\Delta t,$$
trong đó $\Delta t$ là chênh lệch nhiệt độ giữa dây và môi trường, $R$ là điện trở của một nửa dây và $k$ là hệ số tỷ lệ. Mặt khác, sự tăng chiều dài của dây xảy ra theo quy luật
$$l = l_0(1 + \alpha\Delta t),$$
trong đó $\alpha$ là hệ số giãn nở nhiệt của dây. Từ hai đẳng thức cuối cùng

$$\Delta l = l_0\alpha\Delta t = \frac{I^2 R}{k} l_0 \alpha = k_1 I^2$$

⟦folio 46⟧

$\left(k_1 = l_0 \alpha \frac{R}{k}\right)$, tức là chiều dài của dây dẫn tỉ lệ với bình phương cường độ dòng điện. Điều này có nghĩa là phần mở rộng của phần $CB$ của hệ thống dây điện là $\Delta l_1 \sim I_1^2$ và phần $AC$ của hệ thống dây điện là $\Delta l_2 \sim I_2^2$.

Do đó, góc quay của kim dụng cụ, liên quan đến sự khác biệt giữa các phần mở rộng $AC$ và $CB$, tỷ lệ thuận với giá trị
$$I_2^2 - I_1^2 = I_0^2 \left( \frac{r_1^2}{r^2} + \frac{r_1^2}{r^2} \frac{R_H^2}{r^2} + 2 \frac{r_1^2}{r^2} \frac{R_H}{r} + 2 \frac{r_1}{r} \frac{R_H^2}{r^2} + 2 \frac{R_H}{r} \frac{r_1}{r} \right).$$

Vì $r_1 \ll r$, nên $\frac{r_1}{r} \ll 1$ và các số hạng thứ nhất, thứ hai và thứ ba có thể bị bỏ qua so với bốn và thứ năm. Ngoài ra, để việc đấu nối oát kế hầu như không ảnh hưởng đến điện áp ở tải thì $r$ phải lớn hơn $R_H$ rất nhiều. Điều này có nghĩa là $\frac{R_H}{r} \ll 1$ và $\left(\frac{R_H}{r}\right)^2 \ll \frac{R_H}{r}$, vì vậy bốn số hạng có thể bị bỏ qua so với số hạng thứ năm. Kết quả là chúng tôi nhận được
$$I_2^2 - I_1^2 = 2 I_0^2 R_H \frac{r_1}{r^2} = 2 \frac{r_1}{r^2} P,$$

nghĩa là chênh lệch $I_2^2 - I_1^2$ tỷ lệ thuận với công suất do tải giải phóng. Do đó, sự khác biệt về độ dài của các đoạn dây và theo đó, góc quay của mũi tên thiết bị tỷ lệ thuận với dòng điện mà tải tiêu thụ.

$\blacksquare$

Chúng ta hãy quan sát vật thể tại điểm $O$ (Hình 9), nhìn mặt phẳng tại điểm $A$ và nghe âm thanh do mặt phẳng phát ra tại thời điểm mặt phẳng ở điểm $B$. Chúng ta hãy biểu thị bằng $t$ thời gian mà âm thanh từ điểm $B$ phải được định vị, sau đó là $BO = ct$ và $BA = vt$. Từ tam giác vuông $AOK$
$$tg\varphi = \frac{KB + BA}{KO} = tg\alpha + \frac{vt}{ct \cos\alpha}. \tag{1}$$

Bằng cách bình phương đẳng thức (1), biểu thị $tg\varphi - tg\alpha$ cho $x$ và tính đến $\cos\alpha = \frac{1}{\sqrt{1 + tg^2\alpha}}$, chúng ta thu được
$$x^2 - 2 \frac{tg\varphi}{1 - \frac{c^2}{v^2}} x + \frac{1}{\cos^2 \varphi \left(1 - \frac{c^2}{v^2}\right)} = 0. \tag{2}$$

Từ đây
$$x_{1,2} = \frac{tg\varphi}{1 - \frac{c^2}{v^2}} \pm \sqrt{\frac{tg^2\varphi}{\left(1 - \frac{c^2}{v^2}\right)^2} - \frac{i}{\cos^2 \varphi \left(1 - \frac{c^2}{v^2}\right)}} \tag{3}$$

Hơn nữa, phương trình (1) chỉ được thỏa mãn bởi các giá trị dương $x$.

Trước tiên chúng ta hãy xem xét trường hợp tốc độ của máy bay $v$ nhỏ hơn tốc độ âm thanh $c$. Vì $c^2/v^2 > 1$, nên $x_1 > 0$ và $x_2 < 0$, tức là chỉ có một giá trị $x = x_1$ là phù hợp. Mặt phẳng “nhìn thấy” chỉ đơn giản là tụt hậu so với mặt phẳng nhìn thấy được.

⟦folio 47⟧

Thú vị lời giải trong trường hợp máy bay siêu thanh ($v > c$). Phương trình (2) chỉ có nghiệm thực cho $\cos \phi < \frac{c}{v}$ và cả hai nghiệm ($tg\phi > 0$) đều dương cùng một lúc. Điều này có nghĩa là gì? Hãy xem xét điều này chi tiết hơn.

Hình 11.

Điểm nào trên quỹ đạo của máy bay là nguồn phát ra sóng âm hình cầu. Đường bao của các mặt sóng là một bề mặt hữu hạn (Hình 10), chuyển động về phía trước với tốc độ máy bay $v$. Người được quan sát sẽ nghe thấy âm thanh lần đầu tiên vào thời điểm người đó đi đến điểm $O$

Hình 12.

từ các mặt sóng. Nếu mặt phẳng lúc này đang ở điểm $A_0$, thì người quan sát sẽ nghe thấy âm thanh truyền về phía mình từ điểm $B_0$ (Hình 11). Từ Hình 11 có thể thấy rằng $\sin \alpha_0 = \cos \phi_0 = \frac{ct}{vt} = \frac{c}{v}$. Khi máy bay di chuyển ra xa, góc $\phi$ tăng và $\cos \phi$ giảm (do đó, thực sự, người ta nghe thấy máy bay ở các góc $\phi$ sao cho $\cos \phi \leq \frac{c}{v}$).

Bắt đầu từ thời điểm này, mặt trước của sóng âm do máy bay phát ra ở hai điểm khác nhau trên quỹ đạo của nó sẽ đến điểm $O$ (Hình 12). Tại thời điểm mặt phẳng ở điểm $A$, người quan sát sẽ nghe thấy âm thanh do mặt phẳng phát ra tại các điểm $B_1$ và $B_2$ (góc $\alpha_1$ và $\alpha_2$ được xác định từ công thức (3)), tức là lúc này hai mặt sóng đi qua điểm $O$. Do đó, khi máy bay di chuyển ra khỏi điểm $A_0$, người quan sát sẽ thấy rằng hai nguồn âm thanh đang chuyển động theo các hướng khác nhau từ điểm $B_0$.

⟦folio 48⟧

F308. Máy đo áp suất là một tờ giấy có vết dầu mỡ trên đó. Tấm này được đặt giữa hai nguồn ánh sáng thận. Cường độ sáng của một nguồn $I_1 = 20$ sv, cường độ sáng của nguồn khác $I_2$ sẽ phải được xác định. Để thực hiện việc này, trước tiên hãy chọn khoảng cách $l_1$ và $l_2$ nguồn từ tờ mặt nạ để bọt không nổi bật trên nền giấy khi nhìn từ phía của nguồn đầu tiên. Hóa raLOB đó $l_2 = 2l_1$. Sau đó, các khoảng cách $l_1$ và $l_2$ được chọn sao cho bọt không nổi bật trên nền giấy khi nhìn từ phía của nguồn thứ hai. Hóa raLOB đó $l_1' = l_2' = l$. Xác định cường độ sáng của nguồn thứ hai.

Tấm được đặt vuông góc với đường nối các nguồn.

Podd với Kazka. Mỗi phần của giấy có thể được đặc trưng bởi độ truyền qua và độ phản xạ ánh sáng của nó.

Vết bẩn không nổi bật trên nền giấy nếu các luồng ánh sáng $\Phi_\pi$ và $\Phi_6$, tương ứng với đơn vị diện tích của vết bẩn và giấy sạch cũng như sự tiếp xúc với mắt quan sát được, là như nhau. Giấy và giấy phản xạ và truyền ánh sáng chiếu vào chúng một cách khuếch tán, nghĩa là đều theo mọi hướng. Do đó, điều rất quan trọng là thông lượng ánh sáng $\Phi_\pi$ và $\Phi_6$ lần lượt tỷ lệ thuận với độ chiếu sáng của tờ giấy $E_\pi$ và độ chiếu sáng của tờ giấy $E_6$.

Nếu bạn nhìn vào điểm từ phía của nguồn thứ nhất, thì độ chiếu sáng của điểm đó là tổng độ rọi do các tia tới từ nguồn thứ nhất và đi qua điểm $-E_2 = \alpha_\pi \frac{I_2}{l_2^2}$ ($\alpha_\pi$ là hệ số truyền qua của điểm):

$$E_\pi = E_1 + E_2 = r_\pi \frac{I_1}{l_1^2} + \alpha_\pi \frac{I_2}{l_2^2}.$$

Tương tự, nếu hệ số phản xạ ánh sáng của các vùng giấy trong là $r_6$ và hệ số truyền qua của các vùng này là $\alpha_6$ thì độ chiếu sáng của vùng giấy sạch sẽ bằng

$$E_6 = r_6 \frac{I_1}{l_1^2} + \alpha_6 \frac{I_2}{l_2^2}.$$

Đánh đồng $E_\pi$ và $E_6$, ta thu được phương trình

$$r_\pi \frac{I_1}{l_1^2} + \alpha_\pi \frac{I_2}{l_2^2} = r_6 \frac{I_1}{l_1^2} + \alpha_6 \frac{I_2}{l_2^2},$$

hoặc, cho rằng $l_2 = 2l_1$,

$$4r_\pi I_1 + \alpha_\pi I_2 = 4r_6 I_1 + \alpha_6 I_2.$$

Theo cách tương tự, chúng ta có thể thu được các điều kiện chiếu sáng cho giấy và giấy sạch cho trường hợp thứ hai, khi giấy được nhìn từ phía của nguồn thứ hai:

$$\alpha_\pi \frac{I_1}{l_1^2} + r_\pi \frac{I_2}{l_2^2} = \alpha_6 \frac{I_1}{l_1^2} + r_6 \frac{I_2}{l_2^2}.$$

Vì trong trường hợp này $l'_1 = l'_2$, nên

$$\alpha_\pi I_1 + r_\pi I_2 = \alpha_6 I_1 + r_6 I_2.$$

Hai phương trình (2) và (4) gồm năm ẩn số; không thể xác định được tất cả chúng. Tuy nhiên, một trong số chúng có thể được tìm thấy, cụ thể là $I_2$. Để làm điều này, chúng ta giao nhau trong phương trình (2) các số hạng chứa $I_1$ vào vế trái của phương trình và các số hạng chứa $I_2$ vào vế phải. chúng tôi nhận được

$$4I_1(r_\pi - r_6) = I_2(\alpha_6 - \alpha_\pi).$$

Chúng ta hãy xây dựng tương tự từ phương trình (4):

$$I_1(\alpha_6 - \alpha_\pi) = I_2(r_\pi - r_6).$$

Bây giờ đã xác định được mối quan hệ $\frac{\alpha_6 - \alpha_\pi}{r_\pi - r_6}$ từ phương trình (5) và thay nó vào phương trình (6), chúng ta thu được

$$\frac{4I_1}{I_2} = \frac{I_2}{I_1},$$ hoặc $I_2 = 2I_1 = 40$ st.

⟦folio 49⟧

F309. Con rắn bò được nửa đường vào một ống hẹp cố định nằm trên máy bay. Nửa đường nối của con rắn ngọ nguậy tùy ý dọc theo mặt phẳng. Coi con rắn là một cuộn phim mỏng, đồng đều có chiều dài $l$, hãy tìm xem tâm mềm của toàn bộ con rắn có thể nằm ở khu vực nào.

Hình 13.

Trọng tâm của nửa con rắn nằm trong ống nằm cách mép ống một khoảng $\frac{l}{4}$. Tọa độ của nó $(x_1, y_1)$ bằng nhau (Hình 13)

$$x_1 = -\frac{l}{4} \text{ и } y_1 = 0.$$

Trọng tâm của nửa sau của con rắn ngoằn ngoèo tùy ý dọc theo mặt phẳng có thể đặt tại bất kỳ điểm nào bên trong đường tròn bán kính $\frac{l}{4}$ có tâm là gốc tọa độ, tức là tọa độ của nó $(x_2, y_2)$ thỏa mãn bất đẳng thức

$$x_2^2 + y_2^2 \leq \left(\frac{l}{4}\right)^2.$$

Vì khối lượng của cả hai phần của con rắn bằng nhau nên tọa độ trọng tâm của toàn bộ con rắn được xác định theo hệ thức sau:

$$x_\mu = \frac{x_1 + x_2}{2} = \frac{x_2}{2} - \frac{l}{8}, \quad y_\mu = \frac{y_1 + y_2}{2} = \frac{y_2}{2}.$$

Từ những đẳng thức này, chúng ta biểu thị $x_2$ và $y_2$ theo $x_\mu$ và $y_\mu$:

$$x_2 = 2x_\mu + \frac{l}{4}, \quad y_2 = 2y_\mu.$$

Thay các giá trị này vào bất đẳng thức (*), ta được

$$\left(2x_\mu + \frac{l}{4}\right)^2 + 4y_\mu^2 \leq \left(\frac{l}{4}\right)^2, \quad \text{или} \quad \left(x_\mu + \frac{l}{8}\right)^2 + y_\mu^2 \leq \left(\frac{l}{8}\right)^2.$$

Điều này có nghĩa là trọng tâm của toàn bộ con rắn có thể nằm ở bất kỳ điểm nào trong vòng tròn bán kính $\frac{l}{8}$ với tâm có tọa độ là $x = -\frac{l}{8}$ và $y = 0$ (trong Hình 13 vòng tròn này được bảo vệ).

F310. Các đầu của lò xo được cố định. Làm thế nào, nếu không thả các đầu của lò xo, bạn có thể biến dạng nó để lò xo có xu hướng a) rút ngắn lại sau quá trình xử lý này?

Trước tiên chúng ta hãy xem xét một lò xo lỏng lẻo và làm biến dạng nó, tức là kéo căng hoặc nén nó. Về mặt định lượng, biến dạng có thể được đặc trưng bởi độ lớn của biến dạng tuyệt đối $\Delta l = |l - l_0|$ ($l_0$ là chiều dài của lò xo ở trạng thái không biến dạng) hoặc giá trị của biến dạng tương đối $\frac{\Delta l}{l_0}$. Điều gì xảy ra với lò xo sau khi ngoại lực ngừng tác dụng? Hóa ra có thể xảy ra hai trường hợp: hoặc biến dạng biến mất hoàn toàn (lò xo khôi phục lại chiều dài của nó), hoặc nó vẫn còn một phần, tức là dẫn đến biến dạng dư (chiều dài của lò xo không được phục hồi). Trong trường hợp đầu tiên, biến dạng được gọi là đàn hồi, và trong trường hợp thứ hai - dẻo. Điều gì quyết định biến dạng đó là đàn hồi hay dẻo? Kinh nghiệm cho thấy rằng bản chất của biến dạng trước hết phụ thuộc vào độ lớn của biến dạng (cũng như vào vật liệu của lò xo và vào trạng thái của vật liệu này - vào nhiệt độ của nó, quá trình xử lý trước đó, v.v.). Ở những biến dạng tương đối nhỏ, lò xo có tính đàn hồi, nghĩa là nó khôi phục hoàn toàn hình dạng và kích thước sau khi các đầu của nó được thả ra. Nếu biến dạng tương đối lớn thì lò xo trở nên dẻo và xuất hiện biến dạng dư. Chiều dài của lò xo lớn hơn $l_0$ nếu lò xo bị kéo giãn và nhỏ hơn $l_0$ nếu lò xo bị hớt đi. Hãy sử dụng các tính chất này của lò xo cho lời giải bài toán.

⟦folio 50⟧

Chúng ta hãy lấy lò xo được cố định ở hai đầu bằng cuộn dây, gần đầu này của lò xo hơn đầu kia và di chuyển cuộn dây này đến đầu kia của lò xo. Tuy nhiên, một phần của lò xo bị giãn ra và phần còn lại bị cuộn lại. Trong trường hợp này, biến dạng tuyệt đối $\Delta l$ của chúng sẽ giống nhau, nhưng biến dạng tương đối của chúng sẽ khác nhau. Biến dạng tương đối $\frac{\Delta l}{l_{01}}$ của phần ngắn của lò xo sẽ ​​lớn hơn biến dạng tương đối $\frac{\Delta l}{l_{02}}$ của phần dài của lò xo:

$$\frac{\Delta l}{l_{01}} > \frac{\Delta l}{l_{02}}.$$

Điều này có nghĩa là cũng có thể khớp $\Delta l, l_{01}$ và $l_{02}$, sao cho phần dài của lò xo vẫn biến dạng đàn hồi, còn phần ngắn vẫn dẻo. Sau khi “xử lý” như vậy, chiều dài của phần dài (đã được cuộn) vẫn giữ nguyên và chiều dài của phần ngắn (đã được kéo căng) sẽ tăng lên. Chiều dài của toàn bộ lò xo ở trạng thái chưa định hình cũng sẽ tăng lên. Do đó, lò xo gắn ở hai đầu sẽ có xu hướng dài ra.

Tương tự, nếu coi một cuộn lò xo bị xoắn về một đầu gần của lò xo và đồng thời tác dụng ngoại lực sao cho phần dài (căng) của lò xo là đàn hồi, phần biến dạng ngắn (dốc) là linh hoạt thì lò xo sau khi gia công sẽ có xu hướng ngắn lại.

♦

Vì từ trường thay đổi theo thời gian nên xuất hiện lực điện động trong mạch điện. cảm ứng $E$. Cường độ dòng điện cảm ứng trong mạch bằng

$$I = \frac{E}{R},$$

trong đó $R$ là điện trở vòng lặp. Điện trở vòng lặp $R = \rho \frac{l}{s}$. Rõ ràng là $m = dls$. Từ đây

$$s = \frac{m}{ld} \text{ и } R = \rho \frac{d}{m} l^2,$$

nghĩa là điện trở của vòng lặp tỷ lệ với bình phương chiều dài của vòng dây.

E.m.f. cảm ứng được kích thích trong mạch bằng

$$E = \frac{\Delta \Phi}{\Delta t} = \frac{\Delta B}{\Delta t} S = kS,$$

trong đó $S$ là diện tích được bao phủ bởi đường viền. E.m.f. $E$ diện tích càng lớn $S$. Với một chiều dài đường viền cho trước, diện tích hình tròn được bao phủ bởi đường viền có diện tích lớn nhất. Vì vậy, E. d.s. tối đa nếu đường viền là một hình tròn. Chúng ta hãy biểu thị bán kính của hình tròn này bằng $r$, sau đó

$$S = \pi r^2 \text{ и } E = k\pi r^2.$$

Trong trường hợp này

$$l = 2\pi r \text{ и } R = \rho \frac{4\pi^2 r^2}{m}.$$

Pozny cuối cùng

$$I = \frac{E}{R} = \frac{km}{4\pi\rho d}.$$

Đây là dòng điện tối đa trong mạch.

Tôi. Sh. Slobodetsky
