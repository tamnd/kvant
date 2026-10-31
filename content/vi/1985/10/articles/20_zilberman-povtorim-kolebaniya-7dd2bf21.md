---
id: 1985-10-zilberman-povtorim-kolebaniya-7dd2bf21
issue: kvant_1985_10
year: 1985
number: "10"
title: Hãy lặp lại những rung động
authors:
  - Зильберман А. Р.
rubric: praktikum-abiturienta
rubric_sub: Практикум абитуриента
page_first: 50
page_last: 53
page_labels: 48-51
tag: KVTB
lang: vi
source: kvant_digital
extraction: vision
content_sha256: 586034384a09fc84117e134c171af35e61228c1e5ab056f795d7350fcbed3021
prompt_sha256: draft-1
translated_from: content/ru/1985/10/articles/20_zilberman-povtorim-kolebaniya-7dd2bf21.md
source_content_sha256: c1b79c24ae83a6678c9e53d696e70ac94fcd01570e9289d6ad365bc723105f44
translation_model: draft
translation_run: vi-draft-2026-10-31
translation_quality: draft
---

⟦folio 48⟧

Hãy lặp lại những rung động

A. R. ZILBERMAN

Dao động xảy ra trong một hệ được đưa ra khỏi trạng thái cân bằng ổn định. Trong nhiều trường hợp quan trọng trong thực tế, nếu lực trở về vị trí cân bằng phụ thuộc tuyến tính vào sự trộn thì thu được dao động điều hòa. Thông thường đây là những biến động “nhỏ”, khi sự cân bằng bị xáo trộn một chút.

Ví dụ đơn giản nhất là các dao động của ma trận toán học ở các góc lệch nhỏ so với phương thẳng đứng. Một ví dụ khác là sự dao động của một tải dưới tác dụng của lực đàn hồi của lò xo khi không có lực khác. Điều thú vị là các dao động hóa ra là điều hòa, ngay cả khi chúng không nhỏ - miễn là lò xo tuân theo điều kiện (định luật Hooke) $F=-kx$, trong đó $x$ là độ giãn dài của lò xo (độ dịch chuyển của tải khỏi vị trí cân bằng), $k$ là độ cứng của lò xo, $F$ là lực đàn hồi của lò xo.

Hãy xem xét ví dụ này chi tiết hơn. Cho vật nặng vào một lò xo nằm ngang, đầu thứ hai của lò xo được cố định và đặt trên một mặt phẳng nằm ngang nhẵn. Phương trình định luật II Newton đối với tải trọng có dạng

$$mx''=-kx,$$

hoặc

$$x''+\frac{k}{m}x=0$$

(1)

(ở đây $m$ là khối lượng của tải trọng, $x''$ là gia tốc của nó, chính xác hơn là hình chiếu của gia tốc lên trục hoành $X$). Giải pháp cho phương trình như vậy là hàm

$$x=x_m \cos(\sqrt{\frac{k}{m}}t+\varphi_0)=$$

$$=x_m \cos(\omega_0 t+\varphi_0),$$

(2)

trong đó $x_m$ là biên độ, $\omega_0=\sqrt{k/m}$ là tần số riêng, $\varphi_0$ là pha dao động đầu tiên. Tần số được xác định bởi các tham số của hệ dao động $(k$ và $m)$, đồng thời biên độ và pha ban đầu phụ thuộc vào cách hệ thống được đưa ra khỏi trạng thái cân bằng một cách chính xác, nghĩa là các khoảnh khắc ban đầu của thời gian $t_0=0$ được xác định:

$$x_0=x(t_0)=x_m \cos(\sqrt{\frac{k}{m}}t+\varphi_0)=$$

$$=x_m \cos \varphi_0,$$

$$v_0=v(t_0)=x'(t_0)=$$

$$=-x_m \sqrt{\frac{k}{m}} \sin(\sqrt{\frac{k}{m}}t_0+\varphi_0)=$$

$$=-x_m \sqrt{\frac{k}{m}} \sin \varphi_0.$$

Chia phương trình thứ hai cho phương trình thứ nhất, chúng ta tìm thấy $\varphi_0$:

$$tg \varphi_0=-\sqrt{\frac{m}{k}} \frac{v_0}{x_0}, \varphi_0=\arctg\left(-\sqrt{\frac{m}{k}} \frac{v_0}{x_0}\right).$$

Cách dễ nhất để tìm giá trị $x_m$ là loại trừ các hàm lượng giác bằng phương pháp bình phương và cộng phương trình thông thường:

$$x_0^2+\frac{m}{k}v_0^2=x_m^2, \quad x_m=\sqrt{x_0^2+\frac{m}{k}v_0^2}.$$

Bạn có thể đặt tọa độ $x(t_1)$ và $x(t_2)$ làm khoảnh khắc thời gian “thuận tiện” $t_1$ và $t_2$ hoặc tốc độ $v(t_1)$ và $v(t_2)$ hoặc tọa độ $x(t_1)$ và tốc độ $v(t_2)$, v.v. Điều quan trọng là không có khoảnh khắc thời gian $t_1$ và $t_2$ cách nhau bởi một số nguyên các nửa chu kỳ.

Như vậy, khi biết phương trình chuyển động của hệ (phương trình (2)) và hai dữ liệu bổ sung, chúng ta sẽ mô tả đầy đủ chuyển động. Điều tương tự cũng có thể nói, chẳng hạn, về chuyển động có gia tốc theo trọng lực - gia tốc bằng cách xác định các lực, và cùng với tọa độ và tốc độ ban đầu, điều này cho phép chúng ta biết hoàn toàn mọi thứ về chuyển động đó.

Các phương trình tương tự như phương trình (1) thu được trong nhiều bài toán dao động—bạn chỉ cần chọn biến đúng. Hãy để chúng tôi minh họa điều này bằng một số điều kiện bài toán về tải trọng bên ngoài.

⟦folio 49⟧

Nhiệm vụ 1. Tải trọng - một chiếc cốc cân có khối lượng $M$ - làm tăng độ cứng bên ngoài $k$, và xảy ra dao động khi một vật nặng có khối lượng $m$ được đặt vào cốc (nó đi theo đường $h$ trước khi va chạm và dính vào cốc). Mô tả chuyển động của cốc.

Chúng ta hãy hướng trục tọa độ $X$ và chọn gốc tọa độ 0 như trong hình 1. Xét rằng lúc đầu chiếc cốc ở trạng thái cân bằng, chúng ta viết

$$Mg - k(l - l_0) = 0$$

($l$ là chiều dài của lò xo có cốc treo, $l_0$ là không có cốc treo). Khi lệch $x$ so với vị trí ban đầu, khi vật nặng đã dính vào cốc thì phương trình chuyển động của hệ sẽ là:

$$(M + m)g - k(l - l_0 + x) = (M + m)x''.$$

Mở ngoặc và tính đến phương trình đầu tiên, chúng ta nhận được

$$x'' + \frac{k}{M + m}x = \frac{mg}{M + m}.$$

Phương trình này rất giống với phương trình (1), chỉ có phần bên phải can thiệp - nó không bằng 0. Rõ ràng là tại sao điều này lại xảy ra: chúng ta đã lấy gốc tọa độ sai vị trí, bởi vì vị trí cân bằng của chiếc cốc nặng hơn đã di chuyển xuống dưới một khoảng $\Delta x = mg/k$. Nếu chúng ta giới thiệu một biến mới

$$x_1 = x - \Delta x = x - \frac{mg}{k},$$

thì phương trình của $x_1$ sẽ gần giống như (1):

$$x_1'' + \frac{k}{M + m}x_1 = 0$$

(hãy nhớ rằng với sự thay đổi biến như vậy, các biến tùy ý từ $x_1$ cũng giống như từ $x$).

Chúng tôi sẽ không quyết định ở đây bài toán

Hình 1.

Hình 2.

Cuối cùng, chúng ta đã làm được việc chính - chúng ta đã thu được phương trình dao động. Từ đó ta tìm được ngay tần số dao động:

$$\omega_0 = \sqrt{\frac{k}{M + m}}.$$

Để mô tả đầy đủ chuyển động của hệ, trước tiên bạn phải giải bài toán về tác động không đàn hồi của tải lên cốc, sau đó tìm biên độ và pha ban đầu của dao động. Hãy tự mình thực hiện việc này (đáp số được đưa ra ở cuối số báo trên trang 59).

Tần số dao động điều hòa của hệ thống cũng có thể được tìm thấy từ các thông điệp năng lượng. Hãy chỉ ra điều này bằng ví dụ về mạch dao động lý tưởng (không tổn hao).

Chúng ta hãy biểu thị bộ tải tối đa (biên độ dao động của tải) bằng $q_m$ và dòng điện cực đại qua cuộn dây (biên độ dao động của dòng điện) bằng $I_m$. Dòng điện là tải tùy ý đầu tiên của các bản theo thời gian, do đó đối với các dao động điều hòa thì hệ thức này có giá trị

$$I_m = q_m\omega_0.$$

Tại thời điểm tải tối đa ($q = q_m$), dòng điện bằng 0 và tại $i = I_m$ tải biến mất về 0. Chúng ta hãy tìm năng lượng của mạch tại thời điểm đã chỉ định và đánh đồng chúng:

$$\frac{q_m^2}{2C} = \frac{LI_m^2}{2},$$

hoặc $$\frac{q_m^2}{2C} = \frac{Lq_m^2\omega_0^2}{2},$$

trong đó $C$ là điện dung của tụ điện, $L$ là độ tự cảm của cuộn dây. Từ đây

$$\omega_0 = \frac{1}{\sqrt{LC}}.$$

Để biết ví dụ về ứng dụng phương pháp phân giải năng lượng, hai bài toán.

Bài 2. Tìm chu kỳ dao động thẳng đứng của một tải trọng có khối lượng $m$ trong hệ như hình hình 2. Xét khối lượng của khối $M$ tập trung ở trục của nó. Lò xo có độ cứng $k$, sợi dây không giãn.

Chúng ta hãy đánh đồng năng lượng của hệ ở vị trí cân bằng và ở vị trí cực trị, khi tốc độ của tải bằng không. Nhưng trước tiên, hãy tĩnh lặng một chút. Biểu thị chiều dài của lò xo không dãn bằng $l_0$ và chiều dài của nó ở vị trí cân bằng bằng $l$, ta viết

$$k(l - l_0) = Mg + 2mg$$

(xuống khối, tác động làm đổ mồ hôi của các sợi bằng trọng lượng của tải).

⟦folio 50⟧

Đặt chuyển vị cực đại của trục khối đi xuống so với vị trí cân bằng là $x_m$, khi đó tổng năng lượng của hệ ở vị trí cực đại

$$W_1 = \frac{k(l-l_0+x_m)^2}{2} - Mgx_m - mg(2x_m).$$

Biểu thị vận tốc của trục khối khi đi qua vị trí cân bằng qua $v_m$, ta tìm được biểu thức tính tổng năng lượng của hệ lúc này:

$$W_2 = \frac{k(l-l_0)^2}{2} + \frac{1}{2} Mv_m^2 + \frac{1}{2} m(2v_m)^2.$$

Đối với dao động điều hòa trong trường hợp này $v_m = x_m\omega_0$. Do đó, cân bằng năng lượng $W_1$ và $W_2$, sau những phép biến đổi đơn giản, chúng ta thu được

$$\frac{kx_m^2}{2} = \frac{Mx_m^2\omega_0^2}{2} + 2mx_m^2\omega_0^2,$$

Ở đâu

$$\omega_0 = \sqrt{\frac{k}{M+4m}}.$$

bài toán này cũng có thể được giải quyết bằng cách phân bổ khối lượng khác nhau trong khối; để làm điều này, bạn chỉ cần cộng năng lượng quay của nó với năng lượng chuyển động tịnh tiến của khối. Ví dụ, nếu khối lượng $M$ không tập trung vào trục mà phân bố dọc theo một đường tròn bán kính $r$ có ​​tâm là trục thì động năng tổng cộng

$$W_k = \frac{Mv^2}{2} + \frac{M(vr/R)^2}{2},$$

trong đó $R$ là bán kính của khối.

Nhiệm vụ 3. Sử dụng hệ thống phân loại tự quy nạp. Cuộn cảm $L$ được nối với pin có điện áp $U_0$ (hình 3) ​​và khi dòng điện đạt giá trị $I_0$ thì mạch sẽ mở. Song song đó, cuộn dây nối khe hở tia lửa điện $P$ (“ngắn mạch bugi”), khe hở tia lửa điện này sẽ xuất hiện khi đạt đến điện áp $U(U \gg U_0)$. Thông số quan trọng nào chúng ta chưa đặt? Hệ thống sẽ hoạt động ở mối quan hệ nào giữa tất cả các tham số?

Một thông số quan trọng ở đây là điện dung $C$ (tụ điện $C$ trong sơ đồ được mắc song song với bộ chống sét). Nó bao gồm điện dung khe hở tia lửa, điện dung giữa các dây cung cấp và điện dung giữa các vòng dây.

Hãy thực hiện phép tính. Nếu không có khe hở tia lửa điện thì sẽ xuất hiện dao động trong mạch gồm một cuộn dây và một tụ điện, trong đó điện áp cực đại trên tụ đạt được khi cuộn dây cũng bằng 0. Điện áp này có thể được tìm thấy từ định luật bảo toàn năng lượng:

$$\frac{LI_0^2}{2} = \frac{CU_m^2}{2}, \quad U_m = I_0 \sqrt{\frac{L}{C}}.$$

Chữ số sẽ bỏ qua với điều kiện $U \leq U_m$, tức là

$$U \leq I_0 \sqrt{\frac{L}{C}}, \quad I_0 \geq U \sqrt{\frac{C}{L}}.$$

Có một sự tinh tế trong bài toán này. Công tắc dù được thiết kế như thế nào cũng không thể hoạt động ngay lập tức. Trong quá trình mở, điện trở hoạt động của mạch thay đổi từ 0 (lúc đầu) đến giá trị rất lớn (khi mạch hở) và nhiệt sinh ra trong mạch. Ở đây một lần nữa điện trở quan trọng $T = 2\pi/\omega_0 = 2\pi \sqrt{L/C}$, khi đó có thể khẳng định lượng nhiệt thoát ra so với năng lượng tích trữ trong cuộn dây.

Đôi khi một phương trình “dao động” sẽ xuất hiện trong các bài toán rõ ràng không dao động. Hãy xem một ví dụ.

Nhiệm vụ 4. Một khối đơn mỏng có chiều dài $l$ trước tiên trượt dọc theo một bàn ngang Eladian, sau đó rơi trên một mặt phẳng gồ ghề có hệ số ma sát $u$. Khối dừng lại, đã phân hủy ở nửa chừng. Tìm vận tốc ban đầu của xe và thời gian phanh.

Đặt một phần của khối có chiều dài $x < l/2$ trên một bề mặt gồ ghề. Giả sử các phản lực pháp tuyến phân bố đều dọc theo khối, ta tìm được lực ma sát:

$$F_{\text{тр}} = -\mu mg \frac{x}{l}$$

và gia tốc của khối:

$$a = x'' = \frac{F_{\text{тр}}}{m} = -\mu g \frac{x}{l}.$$

Chúng ta có một phương trình quen thuộc

$$x'' + \frac{\mu g}{l} x = 0.$$

⟦folio 51⟧

Phanh bắt đầu tại thời điểm $x=0$ và kết thúc ở tốc độ $v=0$, tương ứng với đúng 1/4 chu kỳ “dao động”; do đó thời gian phanh

$$\tau = \frac{1}{4} T = \frac{1}{4} \frac{2\pi}{\omega_0} = \frac{\pi}{2} \sqrt{\frac{l}{\mu g}}.$$

Tất nhiên, sẽ không có dao động thực sự - khối sẽ không bị đẩy lùi sau khi dừng lại (trong trường hợp không bị trượt, lực tremiya sẽ giảm về 0).

Bây giờ thật dễ dàng để viết biểu thức cho tọa độ $x$:

$$x = \frac{l}{2} \sin \sqrt{\frac{\mu g}{l}} t \quad (\text{при } 0 \leq t \leq \tau)$$

và về tốc độ $v$:

$$v = x' = \frac{l}{2} \sqrt{\frac{\mu g}{l}} \cos \sqrt{\frac{\mu g}{l}} t$$

(tại $0 \leq t \leq \tau$).

Từ đây ta tìm được vận tốc ban đầu

$$v = v (t=0) = \frac{1}{2} \sqrt{\mu g l}.$$

bài toán này có thể được sử dụng bằng cách tăng tốc độ sao cho toàn bộ khối được cắt vào phần gồ ghề của bàn - sau đó sau khi phanh “điều hòa”, phanh bình thường sẽ xảy ra. Bí quyết là bây giờ phần “hài hòa” sẽ không còn chiếm 1/4 thời lượng nữa mà ít hơn. Tự tính thời gian phanh tại $v_0 = 2\sqrt{\mu g l}$ (đáp số được cho ở trang 59).

Bây giờ chúng ta hãy thảo luận về bài toán về dao động tắt dần yếu trong mạch.

Bài toán 5. Một cuộn dây điện cảm $L=1$ Gi, có điện trở hoạt động $R=1$ Ohm và một tụ điện có công suất $C=1$ uF tạo thành một mạch dao động. Tại một số thời điểm, hướng tới tụ điện là $U_1=0,1$ V và dòng điện đạt cực đại. Dòng điện này là gì? Tìm giá trị gần đúng của tổn thất năng lượng trong mạch trong một chu kỳ. Sau khoảng thời gian nào điện tích trên tụ bằng không?

Gợi ý: do trục động cơ không đồng đều nên xảy ra va chạm - một lần trong mỗi vòng quay của trục. Sự cộng hưởng được mô tả ở đây.

3. Tại một số điểm trong mạch hiển thị ở hình 4, phím $K$ bị đóng. Vẽ đồ thị của $U_c(t), I_{L1}(t)$ và $I_{L2}(t)$. Điốt được coi là lý tưởng.
