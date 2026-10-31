---
id: 1983-7-meledin-zadachi-otsenki-2d361f29
issue: kvant_1983_7
year: 1983
number: "7"
title: Bài toán-điểm
authors:
  - Меледин Г. В.
rubric: shkola-v-kvante
rubric_sub: Школа в «Кванте»
page_first: 28
page_last: 33
page_labels: 26, 27, 28, 29, 31
tag: DP6C
lang: vi
source: kvant_digital
extraction: vision
content_sha256: 4c91f99354fa583a7155c8247ebd6ea0aa2e896174fbebcecfe6b3601fb8ae4e
prompt_sha256: draft-1
translated_from: content/ru/1983/07/articles/04_meledin-zadachi-otsenki-2d361f29.md
source_content_sha256: e6bb31bd1ef48dec42ec6bd9213345f2ce32fc388b1c5566c07adf6e0d57221c
translation_model: draft
translation_run: vi-draft-2026-10-31
translation_quality: draft
---

⟦folio 26⟧

Nhiệm vụ đánh giá

Ứng viên Khoa học Vật lý và Toán học
G. V. MELEDIN

Trong cuộc đời mỗi người đều có những đánh giá: liệu mình có thể đến đó kịp thời không, liệu mình có đủ tiền không, cần bao lâu để điều chỉnh bộ điều chỉnh đồng hồ, cần bao nhiêu để giữ tải, v.v.

Trong hoạt động của một nhà nghiên cứu, việc đánh giá là cần thiết về mặt chuyên môn. Ứng dụng thô, ước tính theo bậc độ lớn là một giai đoạn gần như bắt buộc trong việc chuẩn bị thí nghiệm, thiết kế hệ thống lắp đặt và phát triển lý thuyết. Họ không thể thiếu trong quá trình thảo luận về những ý tưởng và dự án mới. Đôi khi các ước tính đề xuất đường dẫn của lời giải bài toán chính xác, giúp thiết lập ranh giới của phạm vi của lời giải chính xác và hiểu những thay đổi nào sẽ được yêu cầu khi thiết lập và lời giải bài toán bên ngoài khu vực này.

Khả năng điều chỉnh cùng với trực giác rất quan trọng trong công việc sáng tạo. Vì vậy, không phải ngẫu nhiên mà gần đây các bài tập đánh giá bắt đầu xuất hiện trong các kỳ thi tuyển sinh đại học. Ví dụ, trong vài năm nay, mọi phiên bản của bài thi viết vật lý dành cho ứng viên vào Khoa Vật lý của Đại học Bang Novosibirsk đều có điểm bài toán. Trong công thức của bài toán như vậy không có hoặc hầu như không có giá trị số của các đại lượng vật lý cần thiết cho lời giải; Người ta cho rằng mọi người đều có thể tự chọn và đặt chúng.

Công thức vật lý của bài toán, việc lựa chọn và xây dựng mô hình vật lý đơn giản nhất của hiện tượng là giai đoạn quan trọng nhất nhưng đồng thời cũng khó khăn của việc ước tính lời giải bài toán. Cần phải lựa chọn chính xác các thông số vật lý có ý nghĩa nhất đối với bài toán, xác định tính chất vật lý của nó và bỏ qua các thông số ít ảnh hưởng đến hiện tượng khô xen kẽ. Để thiết lập mối quan hệ giữa các tham số khác nhau, việc sử dụng đúng các định luật và định nghĩa vật lý cơ bản là điều cần thiết. Đôi khi bạn có thể giới hạn bản thân trong những định nghĩa không quá nghiêm ngặt hoặc cách giải thích định tính về các định luật vật lý.

Trước khi chuyển sang nhiệm vụ cụ thể, chúng tôi sẽ đưa ra hai nhận xét nhỏ. Trước tiên, hãy cùng thống nhất về ý nghĩa chính xác của cụm từ “thứ tự ước tính cường độ”. Hai giá trị số của bất kỳ đại lượng vật lý nào được coi là khác nhau theo một bậc độ lớn nếu tỷ lệ của chúng xấp xỉ bằng 10, hai bậc độ lớn nếu nó bằng 10², v.v. Theo quan điểm này, số 89 nên được coi là một số có bậc 102 và số 15 - có bậc 10. Ví dụ, nếu hai giá trị khác nhau 1,3 lần, thì chúng phải được coi là đại lượng của cùng một bậc. Điều tương tự cũng áp dụng cho trường hợp có chênh lệch 2,3 hoặc thậm chí 5 lần. Với ước tính sơ bộ cũng không có sự khác biệt so với kết quả chính xác.

Thứ hai, điều kiện về ký hiệu. Cùng với dấu bằng “=” hoặc dấu bằng gần đúng “≈” chúng ta sẽ sử dụng dấu “~”. Rõ ràng nó được dùng để ghi lại sự tỉ lệ của hai đại lượng. Chúng ta sẽ sử dụng ký hiệu này để biểu thị sự bằng nhau về độ lớn, từ đó nhấn mạnh rằng các hệ số tỷ lệ không thứ nguyên trong các công thức của chúng ta là các số có thứ tự thống nhất. Một lần nữa, chúng tôi nhấn mạnh rằng sự khác biệt giữa hệ số “thực” và “ước tính” nhiều lần là không đáng kể đối với hệ số của chúng tôi.

⟦folio 27⟧

Bây giờ hãy xem xét một số ước tính bài toán tương đối đơn giản. Hầu hết đều được lấy từ kỳ thi tuyển sinh vào Khoa Vật lý của NSU.

Hãy bắt đầu với bài toán, trong đó vật lý là một môn học rõ ràng và bạn chỉ cần lựa chọn một cách khôn ngoan các giá trị cụ thể của các đại lượng vật lý tương ứng.

Bài toán 1. Ước tính áp lực của bút bi lên giấy khi viết.

Để ước tính như vậy, hãy sử dụng áp suất không xác định: $p = F/S$. Bây giờ chúng ta cần suy nghĩ xem các giá trị số của lực và diện tích có trong định nghĩa này là gì. Mỗi dòng mà chúng ta vẽ trên giấy khi viết bao gồm các điểm riêng lẻ. Điểm có thể coi là một đường tròn có đường kính bằng chiều rộng bên trái $d$ còn lại trên tờ giấy: $S = \pi d^2/4$. Hơn nữa, $d \sim 0,2$ mm (điều này khá hợp lý). Chúng tôi cũng sẽ đánh giá mức tăng $F$ áp dụng cho tay cầm “bằng mắt”: nó không vượt quá trọng lượng của bàn tay, nhưng chắc chắn lớn hơn trọng lượng của tay cầm. Hãy lấy $F \sim 1$ N. Sau đó

$$p = \frac{F}{S} \sim \frac{4F}{\pi d^2} \sim 3 \cdot 10^7 \text{ Pa}.$$

Để biết nó nhiều hay ít, việc so sánh giá trị thu được với một số giá trị khác là rất hữu ích. Giả sử trên bàn có một vật nặng 1kg. Đường kính ở đáy của nó khoảng 4 cm nên trọng lượng tác dụng một áp suất khoảng $8 \cdot 10^3$ Pa lên bàn. Điều này có nghĩa là khi viết bằng tay bi, áp lực lên tờ giấy lớn hơn hàng nghìn lần áp lực của một quả cân nặng đặt trên bàn.

Bài toán 2. Ước tính tốc độ dòng hơi thoát ra từ vòi của ấm đun nước đang sôi.

Đặt công suất của lò sưởi là $W$ và nhiệt dung riêng của sự hóa hơi nước là $L$. Hãy để chúng tôi giới thiệu thêm một tham số nữa—tỷ lệ công suất $\eta$ góp phần hình thành hơi nước. Khi đó $\eta W/L$ là khối lượng hơi nước hình thành trong mỗi đơn vị thời gian. Rõ ràng, lượng hơi nước được tạo thành bao nhiêu thì lượng hơi thoát ra khỏi ấm cũng như vậy:

$$\frac{\eta W}{L} = \varrho v S.$$

Ở đây $\varrho$ là mật độ hơi nước trong quá trình đun sôi, $v$ là tốc độ dòng hơi nước, $S$ là diện tích mặt cắt ngang của vòi ấm. Theo định luật Mendeleev-Clapeyron, mật độ hơi là $\varrho = p\mu/(RT)$, trong đó $p$ là áp suất, $\mu$ là khối lượng mol của nước, $R$ là hằng số khí phổ quát, $T$ là nhiệt độ hơi nước. Cuối cùng chúng tôi nhận được

$$v = \frac{\eta W}{L\varrho S} = \frac{\eta WRT}{Lp\mu S}.$$

Nếu công suất lò sưởi là $W \sim 1$ kW, $\eta \sim 0,5$, $S \sim 1$ cm$^2$, $T \sim 373$ K, $p \sim 10^5$ Pa (vì áp suất hơi bão hòa tại điểm sôi bằng áp suất khí quyển) và các giá trị không đổi bằng nhau, tương ứng với $R = 8,3$ J/(kg K), $L = 4,2$ kJ/kg và $\mu = 18 \cdot 10^{-3}$ kg/mol thì

$$v \sim 2 \text{ м/с}.$$

Bài toán 3. Hãy ước tính xem ngày nắng đẹp trời sáng hơn đêm trăng tròn bao nhiêu lần.

Trước hết, chúng tôi lưu ý rằng Mặt trăng chỉ phản chiếu ánh sáng từ Mặt trời chiếu vào nó. Hãy giả sử

⟦folio 28⟧

Về cơ bản, độ sáng do Mặt trời tạo ra trên Trái đất và trên Mặt trăng là gần như nhau và bằng $E_C$. Năng lượng ánh sáng $E_C \pi R^2$ chạm vào Mặt Trăng (ở đây $R$ là bán kính của Mặt Trăng). Mặt trăng tạo ra sự chiếu sáng trên Trái đất $E_\pi = E_C \pi R^2 k / (2\pi l^2)$, trong đó $k$ là hệ số phản xạ ánh sáng từ bề mặt Mặt trăng, $l$ là khoảng cách từ Mặt trăng đến Trái đất (chúng tôi giả định rằng Mặt trăng “tỏa” ánh sáng phản xạ một cách đồng đều trong một góc đặc bằng một nửa góc tối đa). Bây giờ hãy tìm tỷ lệ chiếu sáng:

$$\frac{E_C}{E_\pi} = \frac{2}{k} \left( \frac{l}{R} \right)^2 = \frac{8}{k} \left( \frac{2R}{l} \right)^{-2},$$

trong đó $2R/l$ là kích thước góc của Mặt trăng, có độ lớn bằng 0,01 radian.

Hãy lấy $k \sim 0,2$, rồi cuối cùng

$$E_C/E_\pi \sim 4 \cdot 10^5.$$

Bài toán 4. Ước tính quả lựu đạn sẽ đi được bao xa nếu vận động viên ném nó từ cự ly đang chạy.

Giả sử khi một quả lựu đạn bay đi, nó sẽ đạt độ cao tối đa $H$. Khi đó thời gian bay của lựu đạn là $2\sqrt{2H/g}$. Nếu tại thời điểm ban đầu hình chiếu ngang của tốc độ lựu đạn tăng $v$ và hình chiếu dọc thực tế không thay đổi, thì thời gian bay sẽ không thay đổi và tầm bay sẽ tăng thêm $l = 2v\sqrt{2H/g}$.

Sẽ hợp lý khi xem xét $H \sim 5$ m và $v \sim 8$ m/s (ví dụ: hãy nhớ rằng những người chạy nước rút chạy một quãng đường hàng trăm mét trong thời gian khoảng 10-12 giây); do đó $l \sim 20$ m.

Kết quả ước tính là khá hợp lý.

Bài toán 5. Ước tính thời gian phóng điện của một quả cầu kim loại tích điện nối với Trái đất thông qua một điện trở có điện trở đã biết.

Gọi điện thế của quả bóng tích điện là $\varphi$ và điện tích $Q = C\varphi$, trong đó $C = 4\pi\varepsilon_0a$ là dung tích của quả bóng ($a$ là bán kính của quả bóng). Sau khi kết nối với Trái đất, cả điện thế và điện tích của quả bóng sẽ bằng không. Trong quá trình phóng điện, dòng điện $I$ xuất hiện trong mạch, tất nhiên dòng điện này sẽ thay đổi theo thời gian, nhưng với mục đích đánh giá, chúng ta sẽ bỏ qua yếu tố này. Sau đó chúng tôi nhận được

$$I \sim \frac{Q}{t} \sim \frac{\varphi}{R},$$

trong đó $R$ là điện trở, $t$ là thời gian phóng điện. Từ đây

$$t \sim \frac{QR}{\varphi} = CR = 4\pi\varepsilon_0aR.$$

Tại $a \sim 1$ m, $R \sim 1$ MΩ và $\varepsilon_0 = 8,85 \cdot 10^{-12} \Phi/\text{м}$

$$t \sim 10^{-4} \text{ с.}$$

Ở Ya. I. Trong “Vật lý giải trí” của Perelman có một câu chuyện mang tên “Dry Out of the Water”. Nó bắt đầu như thế này: “Đặt đồng xu lên một cái đĩa phẳng lớn, đổ lượng nước vừa đủ để

⟦folio 29⟧

phủ đồng xu và mời khách cầm trực tiếp bằng tay mà không bị ướt ngón tay.

Điều tưởng chừng như không thể bài toán này được giải quyết khá đơn giản với sự trợ giúp của một chiếc ly và một mảnh giấy đang cháy. Đốt mảnh giấy, đặt nóng vào trong ly rồi nhanh chóng đặt ngược tờ giấy lên một chiếc đĩa gần đồng xu. Tờ giấy sẽ bay ra ngoài, ly sẽ bốc khói trắng và sau đó toàn bộ nước từ đĩa sẽ tự tụ lại dưới đó. Tất nhiên, đồng xu sẽ vẫn ở nguyên vị trí và trong một phút nữa, khi nó khô, bạn sẽ có thể nhặt nó lên mà không bị ướt ngón tay.”

Hãy giải quyết bài toán này liên quan đến câu chuyện này.

Bài toán 6. Ước tính nhiệt độ tối thiểu mà kính phải được làm nóng để sau khi nguội, tất cả nước từ tấm sẽ xuất hiện trong đó.

Trước tiên chúng ta hãy giải chính xác bài toán (theo chiều kim đồng hồ, trong khuôn khổ một số giả định mà chúng ta sẽ nói đến sau). Khi đưa tấm thủy tinh lên mặt nước, áp suất không khí trong đó bằng áp suất khí quyển $p_a$, còn nhiệt độ của nó $T_x$ thì không xác định được. Khi thủy tinh nguội đi và một khối nước $m$ rơi vào đó thì áp suất không khí trong đó sẽ là $p$, nhiệt độ của thủy tinh sẽ bằng nhiệt độ $T$ của không khí xung quanh và thể tích sẽ giảm theo lượng không khí trong nước, tức là thủy tinh sẽ bằng $(S_l - m/Q)$, trong đó $S$ và $l$ là diện tích mặt cắt ngang của kính và chiều cao của nó, $Q$ là mật độ của nước. Theo định luật Mendeleev-Clapeyron,

$$\frac{p_a S_l}{T_x} = \frac{p S (l - m/(\varrho S))}{T}.$$

Từ điều kiện cân bằng của một cột nước suy ra $pS + mg = p_aS$, thì

$$T_x = T \frac{1}{1 - \frac{mg}{p_a S}} \frac{1}{1 - \frac{m}{\varrho l S}}.$$

Bây giờ chúng ta hãy chỉ ra những giả định ngầm mà chúng ta đã đưa ra cho lời giải. Chúng ta giả định rằng nhiệt độ của không khí trong kính trùng với nhiệt độ của các vách kính; rằng kính được đặt từ từ trên mặt nước, sao cho áp suất ban đầu trong nó trùng với áp suất khí quyển; rằng áp suất của hơi nước trong thủy tinh có thể bỏ qua; hiệu ứng vốn là không đáng kể.

Điều thú vị là công thức thu được cho $T_x$ có tính đến sự thay đổi áp suất (do cột nước đi vào ly gây ra) và tính đến sự thay đổi thể tích không khí trong ly nước dưới dạng các thành phần độc lập. Vì vậy, ảnh hưởng của chúng có thể được nghiên cứu riêng biệt.

Hãy biến đổi người sống chung đầu tiên từ phía bên phải của công thức đã chỉ ra:

$$\frac{1}{1 - \frac{mg}{p_a S}} = \frac{1}{1 - \frac{p_{BO}}{p_a}} \approx 1 + \frac{p_{BO}}{p_a}.$$

Áp suất khí quyển tương ứng với áp suất của cột nước cao 10 m, và trong trường hợp của chúng ta rõ ràng là chiều cao của cột nước đổ vào cốc không thể vượt quá chiều cao của cốc, tức là khoảng 10 cm, vì vậy sẽ hợp lý khi bỏ qua áp suất của cột nước và coi hệ số này xấp xỉ bằng đơn vị:

$$\frac{1}{1 - \frac{mg}{p_a S}} \approx 1.$$

Người sống chung thứ hai có liên quan đến sự thay đổi thể tích nước trong ly. Thể tích của nước và thể tích của cốc không còn chênh lệch nhiều như áp suất nên không thể bỏ qua thể tích của nước.

Như vậy,

$$T_x \approx \frac{T}{1 - \frac{m}{\varrho l S}}.$$

⟦folio 31⟧

Nhiệm vụ 8. Ước tính thời gian sau đó bạn sẽ nghe thấy điều này sau một tia sét, nếu bạn biết rằng sét đã đánh vào một cái cây cách bạn khoảng 3 km.

Vì ánh sáng truyền đi với tốc độ $\approx 3 \cdot 10^5$ km/s nên sẽ xuất hiện tia sét sau khoảng thời gian $\sim 10^{-5}$ s. Âm thanh truyền đi lâu hơn nhiều. Hãy thử ước tính tốc độ truyền dao động âm thanh trong không khí. Hãy sử dụng phương pháp thứ nguyên cho việc này.

Rõ ràng là tốc độ $v$ của âm thanh phụ thuộc vào các thông số đặc trưng cho môi trường này. Gọi đây là áp suất $p$ và mật độ $\rho$ đối với không khí. Giả sử bây giờ $v \sim p^x \rho^y$,

trong đó $x$ và $y$ là số lần hiển thị không xác định. Nếu một công thức như vậy thực sự tồn tại thì kích thước của cạnh trái và phải của nó tất nhiên phải giống nhau.

Điều kiện về thứ nguyên của đại lượng vật lý $A$ được ký hiệu là [A].

Sau đó

$$v = m \cdot c^{-1},$$

$$p = \Pi a = \kappa \Gamma \cdot m^{-1} \cdot c^{-2},$$

$$\rho = \kappa \Gamma \cdot m^{-3},$$

và chúng ta có thể viết

$$m \cdot c^{-1} = (\kappa \Gamma \cdot m^{-1} \cdot c^{-2})^x (\kappa \Gamma \cdot m^{-3})^y.$$

Sự bình đẳng này được duy trì với điều kiện

$$x + y = 0,$$

$$-x - 3y = 1,$$

$$-2x = -1.$$

Từ đây

$$x = \frac{1}{2} \text{ и } y = -\frac{1}{2},$$

theo tư thế chúng tôi nhận được

$$v \sim \sqrt{\frac{p}{\rho}}.$$

Hệ số bằng số trong công thức này không thể được xác định từ các thông báo thứ nguyên. Giả sử rằng nó thuộc thứ tự một (nói chung, điều này cần được kiểm tra bằng cách nào đó).

Để ước tính tốc độ của âm thanh, áp suất không khí được áp dụng cho áp suất khí quyển bình thường: $p \sim 1$ atm $\sim 10^5$ Pa, và mật độ không khí sẽ được coi bằng mật độ trong điều kiện bình thường: $\rho \sim 1,3$ kg/m³. Khi đó tốc độ âm thanh

$$v \sim \sqrt{\frac{p}{\rho}} \sim 300 \text{ м/c},$$

và thời gian sau đó tình trạng sấm sét được quan sát,

$$t \sim \frac{3 \cdot 10^3 \text{ м}}{300 \text{ м/c}} \sim 10 \text{ с}.$$

Thời gian này dài hơn sáu bậc độ lớn so với thời gian truyền ánh sáng, điều này hoàn toàn hợp lý xét theo quan điểm kinh nghiệm sống của chúng ta.

Cuối cùng, một số ước tính bài toán khác được đề xuất. Trước đó, không cần nhìn vào đáp số, hãy tự mình lấy những ước tính cần thiết.

Thử thách phản ánh

1. Ước tính áp suất khí quyển sẽ thay đổi như thế nào nếu nước trong đại dương bốc hơi.
2. Hãy ước tính tốc độ chiếc dù rơi xuống khi chiếc dù mở ra.
3. Hãy ước tính mật độ trung bình của Mặt Trời.
4. Hãy ước tính xem nó sẽ tự động thực hiện bao nhiêu vòng (lộn nhào), tự do rơi xuống vực thẳm dài hàng km với tốc độ tối đa.
5. Đánh giá sự thành công của một vận động viên trong cú ném bóng.
6. Tính lực căng của xích xe đạp khi lên dốc.
7. Hãy ước tính tốc độ di chuyển của một giọt nước nếu khi chạm vào một bức tường đứng yên, nó tạo ra một áp suất trung bình cỡ $10^6$ Pa.
8. Hãy ước tính lực căng của dây đai an toàn giữ người trên xe số tự động nếu xe số tự động đang di chuyển với tốc độ khoảng 30 km/h và va chạm với cột, khiến xe số tự động bị lõm sâu khoảng 30 cm.
9. Hãy ước tính khoảng cách giữa mực nước đại dương trên thế giới và tâm Trái đất ở cực và xích đạo sẽ là bao xa.
10. Ước tính khoảng cách một người mặc quần áo sáng màu khi đi vào rừng thông sẽ bị mất tầm nhìn. (Không có bụi rậm.)
