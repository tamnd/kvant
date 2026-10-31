---
id: 1978-4-resheniya-zadach-m446-m448-f462-f466-17d7d74c
issue: kvant_1978_4
year: 1978
number: "4"
title: Lời giải bài toán M446—M448; F462—F466
rubric: zadachnik-kvanta
rubric_sub: Задачник «Кванта»
page_first: 30
page_last: 35
page_labels: 28, 29, 31, 32, 33
tag: 2W0E
lang: vi
source: kvant_digital
extraction: vision
content_sha256: 139fe9336e1a39d2b42ec7ff6d29690772553949cd75b0d1c7bdb2769fb121d3
prompt_sha256: draft-1
translated_from: content/ru/1978/04/articles/11_resheniya-zadach-m446-m448-f462-f466-17d7d74c.md
source_content_sha256: 8ba8ea64040881e232b2d2f99713bb6f47c5bebf440c8c70b7e10b25d34deb82
translation_model: draft
translation_run: vi-draft-2026-10-31
translation_quality: draft
---

⟦folio 28⟧

M446. Một hình tròn có chiều dài 1 lăn từ bên ngoài dọc theo một hình tròn có chiều dài $\sqrt{2}$. Tại thời điểm ban đầu, điểm tiếp xúc của vòng tròn được đánh dấu bằng một vạch sơn. Khi lăn, các điểm sơn của tôi và vòng tròn bên ngoài khác được sơn bởi nước tiểu mà chúng tiếp xúc. Có bao nhiêu điểm khác nhau của vòng tròn cố định sẽ bị bẩn khi vòng tròn chuyển động quay được 100 vòng quanh vòng tròn cố định?

Hình 1.

Trước tiên chúng ta hãy tìm hiểu xem sẽ để lại bao nhiêu vết đỏ trên vòng tròn cố định $a$ (chiều dài $\sqrt{2}$) nhân với điểm màu đỏ đầu tiên $B$ của vòng tròn di động $b$ (chiều dài 1) trong $n$ vòng quay.

Hãy lăn vòng tròn $b$ dọc theo một đường thẳng. Sau đó (nếu chúng ta lấy điểm màu đỏ đầu tiên trên dòng làm phần đầu của báo cáo $O$), dấu vết của điểm $B$ sẽ rơi vào các điểm có tọa độ nguyên không âm (Hình 1). Bây giờ chúng ta cuộn đường thẳng quanh vòng tròn $a$, bắt đầu từ điểm $O$. Mỗi vòng quay tương ứng với một đoạn thẳng có độ dài $\sqrt{2}$. Rõ ràng là các điểm màu đỏ khác nhau của đường thẳng sẽ đi vào các điểm khác nhau của đường tròn $a$, vì đẳng thức $k_1 - k_2 = m \sqrt{2}$ đối với số nguyên $m, k_1 \neq k_2$ là không thể (số $\sqrt{2}$ là số vô tỷ). Như vậy, trong $n$ vòng quay đầu tiên, điểm $B$ sẽ để lại dấu vết $[n \sqrt{2}] + 1$: đó chính xác là số điểm nguyên trên đoạn $[0; n \sqrt{2}]$.

Bây giờ chúng ta hãy thử xem xét tất cả các dấu vết còn sót lại trên vòng tròn này và vòng tròn kia. Thoạt nhìn

có vẻ như số lượng của chúng tăng theo cấp số nhân tùy thuộc vào số vòng quay $n$: sau mỗi vòng quay, mặt phẳng trung bình của các điểm (số điểm trên một đơn vị chiều dài) trả về khoảng hai lần - sau cùng, dấu vết của các điểm từ một vòng tròn khác được thêm vào các chấm đỏ trên mỗi vòng tròn. Tuy nhiên, giả định này hóa ra hoàn toàn không chính xác: không có điểm màu đỏ nào khác xuất hiện trên vòng tròn $a$, ngoại trừ những điểm trong đó điểm đầu tiên $B!$ rơi vào. Thật vậy, một số chấm trống $B' \in b$ có màu khi chúng tiếp xúc với chấm đỏ $A' \in a$. Vì $A'$ có màu đỏ nên điểm đầu tiên $B$ đã tiếp xúc với nó. Rõ ràng là, khi trở thành màu đỏ, $B'$ sẽ chạm vào các điểm tương tự (khoảng cách từ $A'$ ở khoảng cách 1, 2, ... theo hướng quay) trong đó $B$ đã chạm vào sau khi tiếp xúc với $A'$.

Theo cách tương tự, có thể chứng minh rằng sẽ không có điểm nào xuất hiện trên vòng tròn $b$, ngoại trừ những điểm bị bao phủ bởi điểm đỏ đầu tiên $A \in a$, do đó sau $n$ vòng quay trên vòng tròn $b$ chấm đỏ thứ $(n+1)$ sẽ xuất hiện.

Vì vậy, số lượng chấm đỏ không tăng theo cấp số nhân mà chỉ theo quy luật tuyến tính $[n \sqrt{2}] + 1$.

N. Vasiliev

M447. Trong tam giác nhọn $ABC$, các đoạn $BO$ và $CO$ (ede $O$ là tâm của đường tròn bị bỏ qua) được kéo dài cho đến khi chúng cắt nhau tại các điểm $D$ và $E$ với các đường thẳng $AC$ và $AB$ của tam giác. Hóa ra là $BDE = 50^\circ$ và $CED = 30^\circ$. Bạn có thể tìm các góc của tam giác $ABC$ bằng định lý sin. Hãy đặt $EBD = \varphi$. Sau đó $OEB = 100^\circ - \varphi$, $ABC = \varphi + 40^\circ$, $ACB = 90^\circ - \varphi$,

28

⟦folio 29⟧

$OCD = 50^\circ - \varphi, ODC = \varphi + 50^\circ;$ do đó $0^\circ < \varphi < 50^\circ$.
Từ các tam giác $ODE, OBE$ và $OCD$ ta tìm được:

$$\frac{\sin 50^\circ}{\sin 30^\circ} = \frac{|OE|}{|OD|} = \frac{|OE|}{|OB|} \cdot \frac{|OC|}{|OD|} = \frac{\sin OBE}{\sin OEB} \cdot \frac{\sin ODC}{\sin OCD} =$$

$$= \frac{\sin \varphi \sin (\varphi + 50^\circ)}{\sin (100^\circ - \varphi) \sin (50^\circ - \varphi)} = 2 \sin 50^\circ,$$

Phương trình mà chúng ta phải tìm $\varphi$ ($0^\circ < \varphi < 50^\circ$):

$$\frac{\sin \varphi \sin (\varphi + 50^\circ)}{\sin (100^\circ - \varphi) \sin (50^\circ - \varphi)} = 2 \sin 50^\circ,$$

tương đương sau:

$$2 \sin 50^\circ (\cos 50^\circ - \cos (150^\circ - 2 \varphi)) =$$

$$= \cos 50^\circ - \cos (50^\circ + 2 \varphi),$$

$$\sin 20^\circ - \sin (2 \varphi - 40^\circ) + 2 \sin 50^\circ \cos (2 \varphi + 30^\circ) = 0,$$

$$\cos (\varphi - 10^\circ) \sin (30^\circ - \varphi) + \sin 50^\circ \sin (60^\circ - 2 \varphi) = 0,$$

$$\sin (30^\circ - \varphi) (\cos (\varphi - 10^\circ) + 2 \sin 50^\circ \cos (30^\circ - \varphi)) = 0.$$

Vì $\cos(\varphi - 10^\circ)$ và $\cos(\varphi - 30^\circ)$ dương tại $0^\circ < \varphi < 50^\circ$ nên phương trình cuối cùng có một nghiệm duy nhất $\varphi = 30^\circ$.

Do đó $A\widehat{BC} = 70^\circ, A\widehat{CB} = 60^\circ$.

Tiếp theo, $B\widehat{EC} = 70^\circ \Rightarrow |CE| = |CB|; \quad O\widehat{DC} = 80^\circ \Rightarrow \Rightarrow |CD| = |CO|; \quad A\widehat{DE} = 50^\circ \Rightarrow |EA| = |ED|$.

Độ dài bằng nhau mà bạn muốn đặt thành bài toán cho bạn biết tam giác $ABC$ phải có những góc nào. Nhưng ngay cả khi biết đáp số, cũng khó có thể suy ra lượng giác lời giải nêu trên. Thay vào đó, chúng ta có thể tranh luận theo cách khác.

Trước hết, hãy lưu ý rằng các điều kiện $OED = 30^\circ, ODE = 50^\circ$ xác định duy nhất đáp số. Thật vậy (Hình 3), nếu trên một đường tròn có tâm $O$, chúng ta bao quanh các điểm $B$ và $C$ sao cho $B\widehat{OC} = 100^\circ$ và di chuyển điểm $A$ dọc theo cung $B'\ C'$ (cung đối xứng $BC$) từ điểm $B'$ đến điểm $C'$, thì điểm $D \in [B'\ O]$ sẽ di chuyển đến gần $O$ và $E \in [OC']$ sẽ di chuyển ra xa $O$; trong trường hợp này, giá trị của góc $ODE$ sẽ tăng và góc $OED$ sẽ giảm; Điều này có nghĩa là chỉ ở một vị trí $A$ các đại lượng này mới có thể nhận các giá trị được yêu cầu ($50^\circ$ và $30^\circ$).

Bây giờ chúng ta cần chứng minh rằng một tam giác có các góc $A = 50^\circ, B = 70^\circ, C = 60^\circ$ thỏa mãn các điều kiện, nghĩa là tất cả các góc đều như trong Hình 4. Điều này rõ ràng đối với các góc, các góc còn lại không được tô bóng. Việc chứng minh rằng các góc màu đỏ có các giá trị được chỉ định sẽ khó khăn hơn một chút (chỉ cần làm điều này đối với một trong các góc). Chúng ta hãy đưa ra hai bằng chứng.

1°. Chỉ cần kiểm tra $DE - \text{биссектриса угла } ADB$ là đủ:

$$\frac{|AE|}{|EB|} = \frac{|AE|}{|EC|} \cdot \frac{|EC|}{|EB|} = \frac{\sin 20^\circ \sin 70^\circ}{\sin 50^\circ \sin 40^\circ} =$$

$$= \frac{2 \sin 20^\circ \cos 20^\circ}{2 \sin 50^\circ \sin 40^\circ} = \frac{\sin 30^\circ}{\sin 50^\circ} = \frac{|AD|}{|DB|}$$.

Ở đây chúng ta lại sử dụng định lý sin. Đây là một bằng chứng hình học thuần túy.

2°. Tam giác $ECB$ có tính đối xứng vì $C\widehat{EB} = C\widehat{BE}$. Giả sử $K$ là một điểm đối xứng với điểm $O$ so với trục này (Hình 5). Khi đó tam giác $KCD$ bằng $(|KC| = |OC| = |DC| = a, K\widehat{CD} = 60^\circ)$, và do đó $|KD| =$

⟦folio 31⟧

F462. Nếu bộ điều chỉnh nhiệt điện tử được đặt ở vị trí “nylon”, tiện ích của tôi sẽ bật định kỳ ở $\tau_1 = 10$ giây và tắt ở $\tau_2 = 40$ giây. Đồng thời, bề mặt của tiện ích được làm nóng đến nhiệt độ $t_1 = 100^\circ C$. Nếu bộ điều chỉnh nhiệt được đặt ở vị trí “vỗ tay”, tiện ích của tôi định kỳ bật ở $\tau_1 = 20$ giây và tắt ở $\tau_2 = 30$ giây. Xác định nhiệt độ đã thiết lập $t_2$ của bề mặt tiện ích ở vị trí này của bộ điều chỉnh nhiệt. Cụ thể là, tiện ích đã bật sẽ hoạt động ở nhiệt độ nào $t_3$ nếu bộ điều chỉnh nhiệt bị hỏng.
Giả sử rằng việc loại bỏ phấn tỷ lệ thuận với nhiệt độ và không khí xung quanh. Nhiệt độ phòng $t_0 = 20^\circ C$.

F463. Hai tảng băng đang chuyển động với tốc độ ngẫu nhiên có cùng giá trị tuyệt đối, một tảng về phía bắc, một tảng băng về phía tây. Đúng là tại bất kỳ thời điểm nào trên cả hai tảng băng đều có thể sắp xếp đồng hồ sao cho vận tốc của hai đầu kim giây so với Trái đất sẽ bằng nhau và đối với mỗi thời điểm chỉ có một cách sắp xếp như vậy. Xác định quãng đường di chuyển của tảng băng mỗi ngày nếu chiều dài mỗi kim giây là 1 cm. Các mặt đồng hồ được đặt theo chiều ngang.

Gọi $P$ là lực phóng ra trong thanh sắt. Rồi đến lúc $\tau_1$ năng lượng sẽ được giải phóng trong đó
$$W_1 = P\tau_1.$$
Trong thời gian $\tau_1 + \tau_2$ utigot giải phóng năng lượng
$$W_2 = \alpha (t_1 - t_0) (\tau_1 + \tau_2),$$
trong đó $\alpha$ là hệ số tỷ lệ.
Ở nhiệt độ bàn ủi ổn định $W_1 = W_2$:
$$P\tau_1 = \alpha (t_1 - t_0) (\tau_1 + \tau_2).$$
(1)

Tương tự như vậy, ở chế độ khi bộ điều chỉnh nhiệt được đặt ở vị trí “bông”,
$$P\tau'_1 = \alpha (t_2 - t_0) (\tau'_1 + \tau'_2).$$
(2)

Thay giá trị $P$ từ (1) vào (2), ta tìm được $t_2$:
$$t_2 = \frac{\tau'_1}{\tau_1} \frac{(t_1 - t_0)(\tau_1 + \tau_2)}{\tau'_1 + \tau'_2} + t_0 = 180^\circ C.$$
Sử dụng các phép tính và phép tính tương tự, chúng ta tìm thấy $t_3$:
$$t_3 = 420^\circ C.$$
V. Skorovarov

Tốc độ $v$ của đầu mũi tên so với Trái đất bằng tổng vectơ của tốc độ của tảng băng $v_1$ và tốc độ $v_2$ của đầu mũi tên so với tảng băng.

Gọi vectơ $\vec{OA}$ trong Hình 9 là tốc độ của tảng băng; vectơ $\vec{AB'}$, $\vec{AB''}$, $\vec{AB'''}$ là tốc độ của đầu bàn tay so với tảng băng đối với một số hướng đồng hồ. Khi đó các vectơ $\vec{OB'}$, $\vec{OB''}$, $\vec{OB'''}$ lần lượt là vận tốc của đầu mũi tên so với Trái đất.

Rõ ràng là với tất cả các hướng có thể có của vectơ $\vec{AB}$ ($\vec{AB'}$, $\vec{AB''}$, ...), quỹ tích hình học của các điểm $B$ ($B'$, $B''$, ...) là một hình cầu (có vị trí nằm ngang của đồng hồ - hình tròn) với tâm là điểm $A$. Các vận tốc có thể có $v$ trong một “không gian vận tốc” như vậy được mô tả tương ứng tại điểm $O$ và kết thúc tại điểm $B$ trên hình cầu (hoặc hình tròn). Cấu trúc của tảng băng thứ hai khác nhau bằng cách xoay vectơ tốc độ của tảng băng thêm $90^\circ$.

Hình 9.

Hình 10.

⟦folio 32⟧

Sửa đổi

Ở «Kvant» Số 3, do lỗi của nhà in nên hình vẽ của lời giải bài toán M445 (xem trang 35, Hình 8) bị sao chép không chính xác. Bản vẽ sẽ trông như thế này:

Hình 10 cho thấy cấu trúc của hai tảng băng cùng một lúc. Các vectơ $\overrightarrow{OA}$ và $\overrightarrow{OA'}$ là tốc độ của tảng băng, còn các vòng tròn $S$ và $S'$ là vị trí hình học của các đầu của vectơ $\vec{v}$ và $\vec{v}'$ với sự tương ứng khác nhau giữa các giá trị tốc độ của tảng băng và các đầu mũi tên. Nếu vận tốc ở hai đầu mũi tên quá nhỏ thì các đường tròn $(S_1$ và $S_1')$ không có điểm chung và vận tốc $\vec{v}$ và $\vec{v}'$ không thể bằng nhau đối với bất kỳ hướng nào của đồng hồ. Vòng tròn $S_3$ và $S_3'$ tương ứng với trường hợp hướng không phải là duy nhất.

Điều kiện bài toán tương ứng với tình huống được biểu thị bằng các đường tròn tiếp tuyến $S_2$ và $S_2'$. Như có thể thấy từ hình, trong trường hợp này là $\left| \vec{v} \right| = \left| \vec{v}_2 \right|$ và tốc độ của tảng băng $\left| \vec{v}_1 \right| = \left| \vec{v}_2 \right| V^2$. Kim giây quay một vòng trong 60 giây, do đó, tốc độ đầu kim của nó là $\left| \vec{v}_2 \right| = 2\pi l/60 \approx 0,105$ cm/s ($l=1$ cm là chiều dài của kim giây). Đối với tốc độ của tảng băng, chúng ta thu được $\left| \vec{v}_1 \right| \approx 0,15$ cm/s≈130 m/ngày.

V. Belonukkin

F464. Hình 11 cho thấy hai vòng khép kín: ABBA và ABCA. Cả hai chu trình đều được thực hiện với thời gian đơn nguyên lý tưởng.

1) Cho biết chúng tôi nhận được phần nào của chu kỳ và phần nào chúng tôi cung cấp menlo.
2) Chu trình nào có hiệu suất cao hơn? Bao nhiêu lần?

Hãy xem xét chu trình ABC. Từ sơ đồ $pV$, rõ ràng là $T_B > T_B > T_A$. Do đó, ở đoạn AB và BV khí nhận khí và ở đoạn BA khí được thoát ra. Trong trường hợp này, ở phần AB, khí được làm nóng mà không sinh công ($\Delta V=0$), còn trong phần BV và BA, khí thực hiện công bằng (độ biến thiên nội năng của khí trong mỗi chu kỳ bằng 0)

$$A_1 = Q_{AB} + Q_{BB} + Q_{BA} \quad (Q_{BA} < 0).$$

Như vậy, trong chu trình ABBA

$$\eta_1 = \frac{A_1}{Q_{AB} + Q_{BB}}.$$

Hãy xem xét chu trình ABGA. Từ sơ đồ $pV$ cho thấy rõ rằng $T_B > T_G > T_A$, sao cho ở phần AB khí nhận được Tello, còn ở phần BG và GA nó thoát ra. Ở phần HA khí có tác dụng

$$A_2 = Q_{AB} + Q_{BG} + Q_{GA} \quad (Q_{BG}, Q_{GA} < 0),$$

Vì thế

$$\eta_2 = \frac{A_2}{Q_{AB}}.$$

Hãy so sánh các giá trị của $\eta_1$ và $\eta_2$. Từ sơ đồ $pV$, rõ ràng rằng $A_1 = A_2$ (vì công thực hiện trên mỗi chu kỳ về mặt số lượng bằng diện tích của hình được giới hạn bởi biểu đồ chu trình), do đó

$$\frac{\eta_1}{\eta_2} = \frac{Q_{AB}}{Q_{AB} + Q_{BB}},$$

và vì $Q_{AB} + Q_{BB} > Q_{BA}$, nên $\eta_2 > \eta_1$.

Hãy tính tỉ số $\frac{\eta_1}{\eta_2}$. Để làm điều này, chúng tôi tìm $Q_{AB}$, $Q_{BB}$ và $Q_{AB}$.

Theo sơ đồ $pV$ $Q_{AB} = \Delta U_{AB}$, trong đó $\Delta U_{AB}$ là độ biến thiên nội năng của khí trong tiết diện AB. Đối với một mol khí lý tưởng đơn nguyên tử $\Delta U_{AB} = \frac{3}{2}R \times (T_B - T_A)$. Từ phương trình trạng thái khí ta tìm được $T_B = \frac{2p_0V_0}{R}$, $T_A = \frac{p_0V_0}{R}$. Như vậy,

⟦folio 33⟧

$$Q_{AB} = \Delta U_{AB} = \frac{3}{2} R \left( \frac{2 p_0 V_0}{R} - \frac{p_0 V_0}{R} \right) = \frac{3}{2} p_0 V_0.$$

Tại phần $BB$ $Q_{BB} = \Delta U_{BB} + A_{BB}$, nơi

$$\Delta U_{BB} = \frac{3}{2} R (T_B - T_B) =$$

$$= \frac{3}{2} R \left( \frac{2 p_0 3 V_0}{R} - \frac{2 p_0 V_0}{R} \right) = 6 p_0 V_0$$

(cho một nốt ruồi),

$$A_{BB} = 2 p_0 2 V_0 = 4 p_0 V_0.$$

Như vậy,

$$Q_{BB} = 6 p_0 V_0 + 4 p_0 V_0 = 10 p_0 V_0,$$

$$Q_{AB} + Q_{BB} = 11,5 p_0 V_0.$$

Nhưng $Q_{AB} = -Q_{BA}$,

$$Q_{BA} = A_1 - (Q_{AB} + Q_{BB}) =$$

$$= p_0 V_0 - 11,5 p_0 V_0 = -10,5 p_0 V_0,$$

Vì thế

$$Q_{AB} = 10,5 p_0 V_0.$$

Vì thế,

$$\frac{\eta_1}{\eta_2} = \frac{Q_{AB}}{Q_{AB} + Q_{BB}} = \frac{10,5}{11,5} \approx \frac{21}{23}.$$

A. Zilberman

F465. Trong máy phát điện cao áp, các điện tích được truyền bằng lenti điện môi và tích điện cho điện cực điện cao áp có bán kính $R = 1,5$ m (Hình 12). Ước tính giá trị điện áp và điện áp tối đa có thể thu được từ máy phát điện như vậy nếu tốc độ của dây đai là $v = 20$ m/s và chiều rộng của nó là $l = 1$ m. Có thể xảy ra sự cố khi điện áp trường điện là $E_0 = 30$ kV/cm.

Điện thế cực đại mà điện cực hình cầu cao áp của máy phát điện có thể được tích điện được xác định bởi cường độ điện của không khí: điện áp điện trường gần bề mặt điện cực không thể vượt quá giá trị $E_0 = 30$ kV/cm, tại đó xảy ra sự cố, tức là

$$E_{\max} = E_0.$$

Do đó, điện thế tối đa có thể có trên mỗi điện cực là

$$\varphi_{\max} = E_{\max} R = E_0 R = 4,5 \cdot 10^6 \text{ B}.$$

(Sự tương ứng này tuân theo định luật Coulomb và từ biểu thức của thế trường Coulomb.)

Dòng điện tối đa có thể thu được từ máy phát điện cũng được xác định bởi cường độ điện của không khí. Chúng ta hãy biểu thị bằng $\sigma$ mật độ bề mặt của điện tích được truyền bởi lenthium. Khi đó điện áp gần bề mặt của lenthium là $E = \frac{\sigma}{2\varepsilon_0}$. Giá trị này không được vượt quá $E_0$. Do đó, mật độ điện tích bề mặt tối đa có thể có trên băng bằng

$$\sigma_{\max} = 2\varepsilon_0 E_0.$$

Dòng điện tối đa rõ ràng bằng điện tích tối đa được truyền bởi lenti trên một đơn vị thời gian, nghĩa là

$$I_{\max} = \sigma_{\max} lv = 2\varepsilon_0 E_0 lv \approx 10^{-3} \text{ A}.$$

Tính toán trên cho thấy tại sao máy phát tĩnh điện phải lớn.

S. Kozel
