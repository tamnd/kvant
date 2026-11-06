---
id: 1990-4-mozhaev-perehodnyie-protsessyi-v-elektricheskih-tsepyah-002e21f7
issue: kvant_1990_4
year: 1990
number: "4"
title: Các quá trình quá độ trong mạch điện
authors:
  - Можаев В. В.
rubric: praktikum-abiturienta
rubric_sub: Практикум абитуриента
page_first: 66
page_last: 72
page_labels: 64-70
lang: vi
source: kvant_digital
extraction: vision
content_sha256: d09f63b5ed6f373599b31c1c5136b27d01f1481416c0db603bcc6b7e5c8012bf
prompt_sha256: draft-1
translated_from: content/ru/1990/04/articles/16_mozhaev-perehodnyie-protsessyi-v-elektricheskih-tsepyah-002e21f7.md
source_content_sha256: 17dec3e05e9a4c5539b794e202a235b24ac17e4903bac259c34c53e95095b485
translation_model: draft
translation_run: vi-draft-gaps-2026-11-05
translation_quality: draft
---

⟦folio 64⟧

---
running_head:
folio:
---

Chuyển tiếp
quá trình
trong điện
dây chuyền
Ứng viên Khoa học Vật lý và Toán học
V. MOZHAEV

Khi một mạch điện đóng hoặc mở hoặc các thông số của nó thay đổi, hệ thống sẽ chuyển từ trạng thái cài đặt này sang trạng thái khác. Chúng ta sẽ gọi những gì xảy ra trong một mạch nhất định trong quá trình chuyển đổi này là quá trình chuyển đổi.

Chúng ta sẽ xem xét các mạch điện trong đó các nguồn EMF không đổi hoạt động.

Trạng thái ổn định có thể là Cố định hoặc Không cố định. Trong trường hợp đầu tiên, dòng điện, điện tích và điện áp trong tất cả các phần tử của mạch không đổi theo thời gian. Trong trường hợp ở chế độ đứng yên, dòng điện trong mạch hoặc, ví dụ, điện tích trên tụ điện định kỳ thay đổi theo thời gian, tức là hệ thống ở chế độ dao động. Rõ ràng, điều này chỉ có thể xảy ra khi không có sự tiêu tán năng lượng trong hệ thống (tức là tiêu tán một phần năng lượng dưới dạng nhiệt). Khi có tổn thất, hệ thống sẽ luôn chuyển sang trạng thái Đã thiết lập cố định

Theo quy định, trong hầu hết bài toán được cung cấp cho người nộp đơn, chúng ta đang nói về các điều kiện đã được thiết lập

⟦folio 65⟧

---
running_head:
folio:
---

Bây giờ chúng ta chuyển sang xem xét các ví dụ cụ thể.

Bài toán 1. Có mạch đơn giản nhất: một nguồn EMF không đổi $E_0$ và một điện áp ở dạng điện trở có điện trở $R$ (hình 1). Tìm sự phụ thuộc của dòng điện trong mạch theo thời gian sau khi đóng công tắc $K$.

Hãy viết định luật Ohm cho mạch này tại một thời điểm tùy ý sau khi đóng phím:

$$E_0 = I(t)R.$$

Lời giải của phương trình này có dạng

$$I(t) = E_0/R = \text{const.}$$

Vì vậy, trong mạch tại bất kỳ thời điểm nào sau khi đóng phím, nó không đổi và bằng $E_0/R$, tức là trong hệ thống tức thời, chế độ Đứng yên được thiết lập. Trong thực tế, ngay cả trong một hệ thống lý tưởng hóa như vậy (trong trường hợp hoàn toàn không có điện cảm và điện trở trong mạch), thời gian cần thiết để đạt đến chế độ đứng yên sẽ mặc dù rất nhỏ nhưng không bằng 0, gắn liền với tốc độ phân rã hữu hạn của sóng điện từ. Nhưng định luật Ohm đối với mạch kín “không biết” về điều này và không thể mô tả các chế độ tốc độ trong đó điều này phải được tính đến. Và tất nhiên, chúng tôi sẽ không xem xét chúng.

Bài toán 2. Mạch điện gồm một điện trở có điện trở $R$ và một tụ điện có điện trở $C$ (hình 2). Điện áp trên tụ điện thay đổi như thế nào theo thời gian?

Hãy áp dụng định luật Ohm cho trường hợp này:

$$E_0 = U(t) + I(t)R,$$

trong đó $U(t)$ là điện áp trên tụ điện tại một thời điểm tùy ý (sau khi đóng công tắc $K$) và $I(t)$ là dòng điện trong mạch. Sử dụng kết nối $I(t) = \Delta(CU)/\Delta t$, chúng ta viết định luật Ohm dưới dạng

$$RC \frac{\Delta U(t)}{\Delta t} + U(t) = E_0.$$

Phương trình này mô tả sự phụ thuộc của điện áp vào tụ điện tại bất kỳ thời điểm nào sau khi đóng công tắc $K$. Hãy giới thiệu một biến mới $U^*(t) = U(t) - E_0$, khi đó định luật Ohm sẽ như sau:

$$\frac{\Delta U^*(t)}{\Delta t} = -\frac{1}{RC} U^*(t).$$

Loại phương trình này mô tả nhiều quá trình nổi tiếng, ví dụ, sự phân rã phóng xạ của hạt nhân, sự phụ thuộc của tốc độ của vật thể vào thời gian khi một lực cản tác dụng lên vật thể, tỷ lệ thuận với tốc độ của vật thể, tức là những quá trình trong đó tốc độ thay đổi theo thời gian của một giá trị nhất định tỷ lệ thuận với giá trị này tại một thời điểm nhất định. Trong trường hợp của chúng tôi, tốc độ thay đổi $U^*(t)$ tỷ lệ thuận với chính giá trị này với hệ số tỷ lệ - $1/(RC)$. Dấu trừ có nghĩa là $U^*(t)$ sẽ tắt theo thời gian. Chúng tôi trình bày ở đây lời giải một phương trình như vậy, nhưng chỉ nhằm mục đích giáo dục:

$$U^*(t) = Ae^{-t/(RC)},$$

trong đó $A$ là hằng số nào đó được tìm thấy từ các điều kiện ban đầu. Tại thời điểm đóng chìa khóa $K$ điện áp trên tụ bằng:

$$U(0) = 0, \text{ следовательно, } U^*(0) = U(0) - E_0 = -E_0 \text{ и } A = -E_0.$$

Sự phụ thuộc cuối cùng của điện áp vào tụ điện theo thời gian sẽ là:

$$U(t) = E_0(1 - e^{-t/(RC)}).$$

⟦folio 66⟧

---
running_head:
folio:
---

hình 3 hiển thị biểu đồ tương ứng.

Theo sự phụ thuộc thu được, điện tích của tụ điện sẽ kéo dài vô tận và hướng tới tụ điện chỉ có thể bằng suất điện động nguồn $E_0$ trong tương lai gần. Nhưng tất cả điều này áp dụng cho một sơ đồ lý tưởng hóa trong đó các tham số của nó ($E_0$, $R$ và $C$) là các giá trị không đổi hoàn toàn và không phụ thuộc vào thời gian. Trên thực tế, tất cả chúng đều “thở”, tức là chúng thay đổi theo thời gian, chẳng hạn như do nhiệt độ môi trường không ổn định. Điều này dẫn đến sự biến dạng mạnh của sự phụ thuộc thu được $U(t)$ trong vùng có giá trị lớn $t(t \gg RC)$, tức là khi hướng tới tụ điện không còn khác nhiều so với $E_0$. Do đó, với mọi giá trị hữu hạn của $R$ và $C$, thời gian sạc luôn hữu hạn và hoàn toàn được xác định bởi giá trị $RC$, gọi là hằng số thời gian. Giá trị của hằng số này càng thấp thì quá trình sạc sẽ xảy ra càng nhanh và ngược lại.

Bài 3. Máy tạo khoảng cách chứa một điện trở có điện trở $R$ và một cuộn cảm $L$ (hình 4). Tìm sự phụ thuộc của dòng điện trong mạch theo thời gian sau khi đóng công tắc $K$.

Định luật Ohm cho một mạch đã cho có dạng

$$E_0 - L \frac{\Delta I(t)}{\Delta t} = I(t)R.$$

Hãy giới thiệu một biến mới $I^*(t) = I(t) - E_0/R$ và nhận

$$\frac{\Delta I^*(t)}{\Delta t} = -\frac{R}{L} I^*(t).$$

Đây là một phương trình đã quen thuộc với chúng ta; chúng tôi tìm kiếm nó lời giải ở dạng

$$I^*(t) = Ae^{-Rt/L},$$

trong đó $A$ là hằng số nào đó được tìm thấy từ các điều kiện ban đầu. Tại thời điểm đóng chìa khóa $K$, dòng điện trong mạch bằng 0: $I(0) = 0$; do đó $I^*(0) = I(0) - E_0/R = -E_0/R$ và $A = -E_0/R$. Sau đó

$$I(t) = \frac{E_0}{R}(1 - e^{-Rt/L}).$$

Chúng ta thu được sự phụ thuộc $I(t)$, hoàn toàn giống với sự phụ thuộc $U(t)$ trong trường hợp trước. Thời gian cố định để đạt đến chế độ Đứng yên trong trường hợp này bằng $\tau = L/R$ - $R$ càng nhỏ thì hệ thống càng đạt đến trạng thái ổn định và khi $R$ có xu hướng về 0, $\tau$ có xu hướng vô cực. Tại $R = 0$ định luật Ohm có dạng

$$E_0 - L \frac{\Delta I(t)}{\Delta t} = 0,$$

và lời giải của phương trình này là

$$I(t) = \frac{E_0}{L} t,$$

tức là dòng điện trong mạch sẽ tăng tuyến tính theo thời gian và sẽ không thể đạt đến chế độ Đứng yên. Trong thực tế, sự gia tăng dòng điện sẽ bị hạn chế bởi nguồn dự trữ năng lượng hữu hạn của nguồn. hình 5 hiển thị biểu đồ $I(t)$ cho một số giá trị cuối cùng $L/R$.

Bài toán 4. Kết nối song song của cuộn cảm $L$ và điện trở $R$ được nối thông qua công tắc $K$ với pin có suất điện động $E$ và điện trở trong $r$ (hình 6). Tại thời điểm ban đầu, phím $K$ mở và không có dòng điện trong mạch. Điện tích nào sẽ chạy qua điện trở sau khi đóng công tắc? Bỏ qua điện trở của cuộn dây. Vẽ tranh

⟦folio 67⟧

---
running_head:
folio:
---

Đồ thị cường độ dòng điện qua điện trở và cường độ dòng điện qua cuộn dây theo thời gian.
Đặt tại một thời điểm tùy ý sau khi công tắc $K$ đóng, dòng điện $I_R(t)$ chạy qua điện trở $R$ và dòng điện $I_L(t)$ chạy qua cuộn cảm $L$ (xem hình 6). Rõ ràng, dòng điện của pin bằng tổng dòng điện $I_R(t) + I_L(t)$. Hãy chọn hai trái ngược đóng và viết định luật Ohm cho mỗi trái đó. Đối với mạch bao quanh pin và điện trở, chúng ta có thể viết
$$\mathcal{E} = I_R(t)R + (I_R(t) + I_L(t))r. \tag{1}$$

Một phương trình tương tự cho một bộ đếm chứa một cuộn dây và một điện trở sẽ có dạng
$$L \frac{\Delta I_L(t)}{\Delta t} = I_R(t)R. \tag{2}$$

Tại thời điểm ban đầu, ngay sau khi đóng phím $K(t=0)$, dòng điện là $I_L(0)=0$. Từ phương trình đầu tiên (phương trình này cũng đúng với $t=0$), suy ra rằng dòng điện chạy qua điện trở ngay sau khi đóng công tắc bằng $I_R(0) = \mathcal{E}/(R+r)$. Biết bản thân các điểm, chúng ta có thể tìm thấy tốc độ thay đổi của chúng tại thời điểm ban đầu
$$\frac{\Delta I_L}{\Delta t} \bigg|_{t=0} \neq \frac{\Delta I_R}{\Delta t} \bigg|_{t=0}.$$

Từ phương trình (2) suy ra rằng
$$L \frac{\Delta I_L}{\Delta t} \bigg|_{t=0} = I_R(0)R = \frac{\mathcal{E}}{R+r} > 0,$$
nghĩa là dòng điện qua cuộn dây tăng theo thời gian. Vì $\mathcal{E}$ không phụ thuộc vào thời gian nên theo phương trình (1) rằng
$$\frac{\Delta I_R(t)}{\Delta t} (R+r) + \frac{\Delta I_L(t)}{\Delta t} r=0,$$
và tại thời điểm $t=0$

$$\frac{\Delta I_R}{\Delta t} \bigg|_{t=0} = -\frac{\Delta I_L}{\Delta t} \frac{r}{R+r} = -\frac{\mathcal{E}R}{(R+r)^2L} < 0$$

- dòng điện qua điện trở giảm với một tốc độ hữu hạn.

Hệ thống bị mất điều hòa nên nó có xu hướng chuyển sang trạng thái đứng yên nào đó. Cả hai phương trình đều thỏa mãn điểm dừng lời giải
$$I_R=0, I_L=\mathcal{E}/r.$$

Do đó, dòng điện qua điện trở giảm và tiệm cận có xu hướng bằng 0, còn dòng điện qua cuộn dây tăng và có xu hướng về giá trị $\mathcal{E}/r$. Các phần phụ thuộc $I_R(t)$ và $I_L(t)$ được hiển thị trong hình 7.

Để tìm tổng điện tích $Q_R$ chạy qua điện trở, chúng ta viết lại phương trình (2) dưới dạng
$$L \Delta I_L(t)=RI_R(t)\Delta t.$$

Ở đây $I_R(t)\Delta t$ là điện tích $\Delta Q_R$ chạy qua điện trở trong khoảng thời gian ngắn $\Delta t$; kể từ đây,
$$L \Delta I_L(t)=R\Delta Q_R.$$

Như có thể thấy từ phương trình này, mối quan hệ giữa độ biến thiên của dòng điện qua cuộn dây và điện tích chạy qua điện trở không phụ thuộc vào thời gian, tức là, nó không đổi trong bất kỳ khoảng thời gian nào. Trong toàn bộ quá trình thiết lập trạng thái ổn định
$$L(I_L(\infty)-I_L(0))=RQ_R.$$

Có tính đến thực tế là $I_L(\infty)=\mathcal{E}/r$, tổng điện tích chạy qua điện trở sẽ bằng
$$Q_R = \frac{\mathcal{E}L}{Rr}.$$

Nhiệm vụ 5. Một mạch dao động gồm một cuộn cảm $L$, một tụ điện $C$ và một diode lý tưởng $D$ (hình 8) được nối qua các công tắc $K$ trong một thời gian $t$ với một nguồn EMF không đổi $\mathcal{E}$, sau đó ngắt kết nối. Tìm sự phụ thuộc của tụ điện vào thời gian sau khi đóng công tắc. Trình bày sự phụ thuộc này bằng đồ họa. Bỏ qua điện trở trong của nguồn và điện trở của cuộn dây.

⟦folio 68⟧

---
running_head:
folio:
---

Sau khi đóng phím $K$ trong quá trình đó, có thể viết được thời điểm $t$ đối với mạch chứa nguồn và cuộn dây, theo định luật Ohm

$$E - L \frac{\Delta I_L(t)}{\Delta t} = 0.$$

Vì dòng điện ban đầu là $I_L(0) = 0$ nên sự phụ thuộc của dòng điện $I_L(t)$ qua cuộn cảm sẽ có dạng

$$I_L(t) = \frac{E}{L} t,$$

tức là dòng điện được định hướng tuyến tính theo thời gian và sau thời gian $\tau$ sẽ bằng nhau

$$I_L(\tau) = \frac{E}{L} \tau.$$

Vì vậy, thông qua diode, rõ ràng là tất cả thời gian này nó sẽ bằng 0.

Xét mạch điện chứa một cuộn dây, một diode và một tụ điện sau khi công tắc $K$ đóng (sau một thời gian $\tau$). Định luật Ohm cho bộ đếm này trông như thế này:

$$-L \frac{\Delta I_K}{\Delta t} = U(t),$$

trong đó $I_K$ là dòng điện trong mạch (xem hình 8) và $U(t)$ là điện áp trên tụ điện. Có tính đến kết nối $I_K = \Delta(CU)/\Delta t = CU'$ phương trình của contrar này được rút gọn về dạng

$$U'' + \frac{1}{LC} U = 0.$$

Phương trình này mô tả các dao động điều hòa trong mạch, do đó chúng ta tìm lời giải của phương trình này ở dạng

$$U(t) = A \cos \omega_0 t + B \sin \omega_0 t,$$

trong đó $A$ và $B$ là hằng số và $\omega_0 = 1/\sqrt{LC}$. Chúng ta sẽ tính thời gian kể từ thời điểm phím $K$ được đóng lại. Ở điện áp $t = 0$ trên tụ điện $U(0) = 0,$

từ đó nó theo sau $A = 0$. Mặt khác, từ điều kiện ban đầu $I_K(0) = I_L(\tau) = \mathcal{E} \tau/L$, $I_K(0) = C \frac{\Delta U}{\Delta t} \bigg|_{t=0} = B \omega_0 C$; do đó $B = \mathcal{E} \tau/(\mathcal{LC} \omega_0) = \mathcal{E} \tau \omega_0$. Chúng tôi nhận được kết quả cuối cùng

$$U(t) = \mathcal{E} \tau \omega_0 \sin \left( \frac{1}{\sqrt{LC}} t \right).$$

Nhưng điều này không đúng ở bất kỳ thời điểm nào mà chỉ đúng trong khoảng $0 \leq t \leq T/4$, trong đó $T = 2\pi \sqrt{LC}$. Ở $t > T/4$, điện áp trên tụ sẽ không đổi và bằng $\mathcal{E} \tau \omega_0$. Đồ thị của $U(t)$ được hiển thị trong hình 9.

Bài toán 6. Trong mạch điện ở hình 10, tại thời điểm ban đầu, các công tắc $K_1$ và $K_2$ mở và tụ điện không được tích điện. Đầu tiên, phím $K_1$ được đóng lại. Tại thời điểm điện áp trên tụ điện bằng tổng sức điện động của pin $E_1$ và $E_2$, công tắc $K_2$ đóng. Sau bao lâu sau khi đóng chìa khóa $K_2$ dòng điện qua cuộn dây sẽ tăng gấp 3 lần? Đọc độ tự cảm của cuộn dây đã cho $L$, công suất tụ điện $C$ và tỷ số $E_2/E_1 = 0,8$. Yêu cầu tất cả các tổn thất ohmic.

Sau khi đóng công tắc $K_1$ ta có mạch kín chứa nguồn, cuộn dây và tụ điện thứ nhất. Định luật Ohm cho một mạch điện tại một thời điểm tùy ý có dạng

$$E_1 - LC U_C'' = U_C,$$

trong đó $U_C$ là điện áp trên tụ điện. Hãy giới thiệu một biến mới $U_C^* = U_C - E_1$, khi đó phương trình ban đầu có thể viết dưới dạng

⟦folio 69⟧

---
running_head:
folio:
---

Như đã đề cập, phương trình loại này mô tả các dao động điều hòa:
$$U_c^* + \frac{1}{LC} U_c^* = 0.$$

Trong đó $A$ và $B$ là các hằng số được tìm thấy từ các điều kiện ban đầu và $\omega_0 = 1/\sqrt{LC}$. Ngay sau khi đóng chìa khóa $K_1$ $U_c(0) = 0$, $U_c^*(0) = -E_1$. Ngoài ra, $U_c'(0) = U_c^*'(0) = 0$ từ điều kiện dòng điện bằng 0 tại thời điểm ban đầu. Từ đây bạn có thể tìm thấy các hằng số $A$ và $B$: $A = 0$, $B = -E_1$. Sự phụ thuộc của điện áp vào tụ theo thời gian sẽ có dạng
$$U_c(t) = E_1(1 - \cos \omega_0 t).$$

Sự phụ thuộc này và sự phụ thuộc thời gian của dòng điện $(I(t))$ trong mạch được thể hiện ở hình 11.

Có hai thời điểm trong mỗi chu kỳ dao động khi $U_c(\tau_1) = U_c(\tau_2) = E_1 + E_2 = 1,8E_1$. Thật dễ dàng để tìm thấy sức mạnh hiện tại tại những thời điểm này - hoặc từ sự phụ thuộc
$$I(t) = CU_c' = C E_1 \omega_0 \sin \omega_0 t = E_1 \sqrt{C/L} \sin \omega_0 t,$$
hoặc từ định luật bảo toàn năng lượng: công của nguồn với EMF $E_1 \cdot 1,8E_1$ làm tăng năng lượng của tụ điện $C(1,8E_1)^2/2$ và năng lượng của từ trường của cuộn dây $LI_L^2(t)/2$. Trong cả hai trường hợp
$$I(\tau_1) = 0,6E_1 \sqrt{\frac{C}{L}}, a I(\tau_2) = -0,6E_1 \sqrt{\frac{C}{L}}.$$

Sau khi đóng phím $K_2$, định luật Ohm đối với vòng kín chứa nguồn thứ hai và cuộn dây có dạng

$$U_c, I$$

Lời giải của phương trình này:
$$I_L(t) = I_L(0) + \frac{E_2 t}{L},$$

trong đó thời gian $t$ vắng mặt kể từ thời điểm đóng chìa khóa $K_2$. Đối với trường hợp đầu tiên, khi khóa $K_2$ bị đóng sau một thời gian $\tau_1$ sau khi đóng phím $K_1$,
$$I_L(\tau_1) = I_L(0) = -0,6E_1 \sqrt{\frac{C}{L}}.$$

Dấu trừ phản ánh thực tế rằng cùng một dòng điện $I_L(\tau_1)$ chạy qua cuộn dây, đối với mạch chứa nguồn và tụ điện thứ nhất, chạy theo hướng “tác dụng” của EMF $E_1$ (từ “+” đến “-”), và đối với mạch chứa nguồn và cuộn dây thứ hai, nó chạy ngược lại EMF $E_2$. Một thời gian $t_1$ sau khi đóng cửa $K_2$
$$I_L(t_1) = 3 \cdot 0,6E_1 \sqrt{\frac{C}{L}} = -0,6E_1 \sqrt{\frac{C}{L}} + 0,8E_1 t_1,$$
Ở đâu
$$t_1 = 3 \sqrt{LC}.$$

Trong trường hợp thứ hai, khi khóa $K_2$ đóng sau thời gian $\tau_2$ sau khi đóng phím $K_1$,
$$I_L(0) = I_L(\tau_2) = 0,6E_1 \sqrt{\frac{C}{L}}.$$

Rồi sau thời gian $t_2$ sau khi đóng cửa $K_2$
$$I_L(t_2) = 3 \cdot 0,6E_1 \sqrt{\frac{C}{L}} = 0,6E_1 \sqrt{\frac{C}{L}} + 0,8E_1 t_2.$$

⟦folio 70⟧

---
running_head:
folio:
---

Do đó, đối với trường hợp thứ hai, cường độ dòng điện tăng lên gấp 3 lần theo thời gian.
$$t_2 = \frac{3}{2} \sqrt{LC}.$$

Bài tập
1. Trong mạch như hình hình 12, tại thời điểm ban đầu phím K mở

Danh sách độc giả gửi đúng lời giải

(Để bắt đầu, xem trang 39)

Novets) 78, 80, 82, 85-89, 91; P. Bolotskikh (Gubkin) 88-90, 92; R. Butchko (Chernivtsi) 78—82, 85, 86, 88, 89, 92; V. Bykov (Kolomna) 81, 82; G. Vazhenin (Sverdlovsk) 78-80, 85-87; G. Veigas (Vilnius) 78, 80, 81, 88, 89; A. Vikol (Nerongri) 80, 82, 85-90; A. Vlasov (Leningrad) 88, 89; A. Voronin (Stary Oskol) 88, 89; O. Vorotnikova (Krasnoisk) 79, 86, 89; G. Vyzon (Moscow) 78, 79, 81, 85, 86, 89, 92; V. Vysotsky (Kyiv) 79, 81, 82, 85-87, 89-91; K. Galichesky (Severodvinsk) 78-82, 85-92; A. Gvozdev (Riga) 89; E. Gendin (Kyiv) 78—82, 85; M. Grekhova (Yaroslavl) 81; A. Grichuk (làng Mokhro, vùng Brest) 78—80, 82, 85, 86, 89, 91; A. Gritsan (Novosibirsk) 91; D. Graznykh (Chelyabinsk) 78, 81, 85-92; V. Gubin (Tashkent) 81, 82; O. Gusar (Kanev) 80, 82, 85, 89, 92; R. Guskov (Mỏ vùng Rostov) 86; Yu. Ruột (Rivne) 78—80, 82, 85, 88—90, 92; A. Davletov (Alma-Ata) 79, 80, 82, 89; A. Danilenko (Kyiv) 82; S. Demba (Stary Oskol) 87, 89; N. Demchik (Zdolbunov) 78, 80, 86, 88, 91, 92; S. Dergachi (làng Malinovka BashASSR) 81; O. Dzyubenko (Kyiv) 85; S. Dobrovolsky (Dnepropetrovsk) 78—80, 82, 85, 87, 88; A. Dovank (Kyiv) 80; M. Dorokhov (làng Chernogolovka, vùng Moscow) 79, 80, 82; 85-87, 89, 91; M. Drukhinin (Moscow) 78-82; 85, 87; A. Dubovik (Wrest) 78; D. Dushamov (Shavat) 88; D. Egorov (Pavlovo, vùng Gorky) 80; Yu. Eroshenko (khu định cư Priyutovo, BashASSR) 82; P. Zhavrid (Minsk) 79-81; A. Zhuk (Rivne) 78—80, 82, 85—90, 92; O. Zhumantsev (Shavat) 89; I. Zhuravleev (Stary Oskol) 89; A. Zborovsky (Stolin) 79; V. Zelevinsky (Novosibirsk) 88, 89; M. Zelenfroid (Bobruisk) 78, 80-82, 85-87, 89, 92; V. Zlobov (Stary Oskol) 88, 89; F. Ibraimov (Baku) 78, 81, 82, 88-92; D. Ivanov (Smolensk) 79, 82; N. Ichchenko (Kyiv) 87;

N. Ilet (Chernivtsi) 79; A. Kalashnikov (Kyiv) 78—80, 82; M. Kalinovsky (khu định cư Trudovoye, vùng Primorsky) 79, 80, 82, 85, 88, 89; T. Kalita (Kyiv) 78—80, 82, 85, 89; K. Kalozhny (Odeska) 80; A. Karpenko (Brest) 78, 81, 82, 85; A. Karpenko (Brest) 78, 81, 82, 85, 87; I. Katsman (Kyiv) 79, 82, 89; S. Kelman (Alma-Ata) 78-80, 82, 85, 87-90; Zh. Kitaeva (Chernigov) 79; K. Kladko (Kharkov) 79-82, 88; E. Klimchuk (Kuznetsovsk) 78, 79, 81, 82, 85, 86, 89, 92; M. Kovalev (Gubkin) 82, 88-92; I. Kovalets (Rivne) 85, 90, 92; S. Koval (Gomel) 78-81, 85, 88-90, 92; V. Kovalsky (Kyiv) 79, 81, 82, 85; T. Kovaluchk (Kyiv) 79, 81; M. Kolpkov (làng Pochet, vùng Krasnoyarsk) 78-82, 85, 87-90; D. Kolvakh (Ordzhonikidze) 87; D. Komisarenko (Vinnitsa) 78—82, 86; E. Konovalov (Kyiv) 78, 80-82; Y. Konteevsky (Kaushany) 78, 79; V. Konyshin (Rostov) 78; I. Korel (Novosibirsk) 89; V. Korolev (Moscow) 79; A. Koronovsky (Saratov) 80; V. Korchazin (Krasnoarmeysk, vùng Moscow) 88, 89, 91; S. Kostyuk (Kolomna) 85, 86; S. Kotkovsky (Chernivtsi) 80; Yu. Kravachts (làng Knyazhpol, vùng Levovo) 85, 86; N. Kronsky (Gorky) 78, 79; V. Kutuzov (Riga) 78—81, 85, 87, 89, 90, 92; A. Labunets (Odeska) 85; A. Lempert (làng Chernogolovka, vùng Moscow) 78, 79, 81, 82, 85-87, 89-92; A. Lyanin (Moscow) 78, 85, 88, 89; V. Makarov (Kirovsoe) 89; I. Markaren (Baku) 81; D. Massino (Tashkent) 78-82; Yu. Matonin (Volsk) 80-82, 85, 87-92; I. Matsko (Kyiv) 79—82, 88, 89, 92; V. Merker (Stary Oskol) 89; R. Mizok (Rivne) 78—80, 82, 85—92; O. Miroshinchenko (Lutsk) 78-82; A. Mikhovich (Mogilev) 85, 87; A. Mshchenin (Kropotkin) 82; E. Mitsenko (Chernivtsi) 78-82, 85-92; A. Mukhin (Severodvinsk) 89, 90; V. Mytko (Leningrad) 85, 86, 89, 90, 92; T. Nasardikov (Grozny) 80; I. Nemirovskaya (Kyiv) 79, 80, 85, 89; D. Ometsinsky (Kyiv) 78-82, 85-87; A. Orlovsky (Kramatorsk) 78, 79; K. Palamaruk (Phần kết xem trang 75)
