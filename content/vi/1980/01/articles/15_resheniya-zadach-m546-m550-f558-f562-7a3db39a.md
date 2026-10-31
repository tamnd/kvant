---
id: 1980-1-resheniya-zadach-m546-m550-f558-f562-7a3db39a
issue: kvant_1980_1
year: 1980
number: "1"
title: Lời giải bài toán M546—M550; F558—F562
rubric: zadachnik-kvanta
rubric_sub: Задачник «Кванта»
page_first: 35
page_last: 41
page_labels: 33, 37, 38, 39
tag: WCEA
lang: vi
source: kvant_digital
extraction: vision
content_sha256: 1be49df25899961f5fc146e6638ffc53ba2e8f9a155941bb1c0958f2d2beb6ec
prompt_sha256: draft-1
translated_from: content/ru/1980/01/articles/15_resheniya-zadach-m546-m550-f558-f562-7a3db39a.md
source_content_sha256: df77c25bc7b7e696da3b1e7c80968ea8a313225a1d54388cc90006a3cf646200
translation_model: draft
translation_run: vi-draft-2026-10-31
translation_quality: draft
---

⟦folio 33⟧

M546. Từ một điểm M tùy ý của đường tròn ngoại tiếp hình chữ nhật, ta kẻ các đường vuông góc MP và MQ với hai cạnh đối diện của nó và vuông góc MR và MT với phần kéo dài của hai cạnh kia. Chứng minh rằng các đường thẳng PR và QT vuông góc, khác, khác, khác. Và giao điểm của chúng thuộc các đường chéo của đường thẳng.

M547. Để phương trình $\frac{1}{x} - \frac{1}{y} = \frac{1}{n}$, trong đó $n$ là số tự nhiên, có lời giải duy nhất trong các số tự nhiên $x$, $y$ thì điều cần và đủ là $n$ là số nguyên tố. Chứng minh điều đó.

Chúng ta hãy biểu thị bằng $M_1$ và $P_1$ giao điểm của các đoạn $MT$ và $MP$ với đường tròn đã cho (xem hình). Vì các góc $MMP_1$ và $ADC$ là góc vuông nên các góc $M_1AP_1$ và $AM_1C$ cũng là góc vuông và tứ giác $AP_1CM_1$ là hình chữ nhật. Mặt khác, tứ giác $AM_1TQ$ và $ARPP_1$ là hình bình hành (các cặp đoạn thẳng $M_1T$, $AQ$ và $AR$, $PP_1$ song song và có chiều dài bằng nhau). Pozny $(AM_1) \parallel (TE)$ và $(AP_1) \parallel (RP)$. Theo sau đó là $(TE) \perp (RP)$.

Câu thứ hai bài toán $(E \in (AC))$ tương đương với việc quan sát các số hạng thẳng $AP_1CM_1$ và $AGEF$. Hãy chứng tỏ rằng chúng thực sự đã bị tẩy trắng.

Trên thực tế, tất cả các góc được đánh dấu trên hình đều bằng nhau; hãy để chúng có độ lớn bằng $a$. Sau đó, nếu $|AM_1| = a$ và $|CM_1| = b$ thì $|AF| = |AR| \sin a = |PP_1| \sin a = |CP_1| \sin^2 a = a \sin^2 a$ và tương tự $|AG| = b \sin^2 a$, tức là $\frac{|AM_1|}{|CM_1|} = \frac{|AF|}{|FE|}$.

Pozny $E \in [AC]$.

I. Klumova

◆ Từ phương trình $\frac{1}{x} - \frac{1}{y} = \frac{1}{n}$ suy ra $\frac{1}{x} > \frac{1}{n}$, tức là $x < n$. Do đó, nếu $n = 1$ thì trong số tự nhiên không có lời giải. Đặt $n \neq 1$, sau đó đặt $x = n - i$, $0 < i < n$ và $\frac{1}{n - i} - \frac{1}{n} = \frac{1}{y}$. Do đó $y = \frac{n(n - i)}{i}$. Tuy nhiên, lời giải (trong số tự nhiên) luôn ở đó: nó thu được bằng $i = 1: x = n - 1, y = n(n - 1)$.

Bây giờ đặt $n$ là số nguyên tố và $i > 1$. Khi đó các số $n$ và $i$ là nguyên tố cùng nhau và các số $n - i$ và $i$ cũng nguyên tố cùng nhau, và do đó các số $n(n - i)$ và $i$ cũng nguyên tố cùng nhau (ví dụ: hãy thuyết phục bạn về điều này bằng cách xem xét tổng $n(n - i) + ni$. Poznym, nếu $n$ là số nguyên tố, và $i > 1$, chúng ta nhận được $y = \frac{n(n - i)}{i} \notin \mathbb{N}$. Điều này có nghĩa là đối với $n$ đơn giản thì cần phải có $i = 1$ và phương trình của chúng ta chỉ có lời giải.

Nếu $n$ là hợp số: $n = n_1n_2$, thì khi đặt, ví dụ: $i = n_1$, chúng ta thu được, ngoài lời giải, $x = n - 1$, $y = n(n - 1)$, một nữa: $x = n - n_1$, $y = n_2(n - n_1)$. Điều này hoàn toàn chứng minh nhận định bài toán.

A. Dantselyan

◆ Hãy giải ngay điểm c) bài toán. Để làm điều này, trước hết hãy tạo:

Có $n$ điểm trên vòng tròn. Qua tâm của $n - 2$ như vậy, một đường thẳng được vẽ từ chúng, vuông góc với dây cung, nối các điểm còn lại. Chứng minh rằng mọi đường thẳng như vậy đều đi qua một điểm.

Nhưng tâm của những điểm $k$ đó là gì? Chúng ta hãy đưa ra một định nghĩa: tâm của $k$ điểm $A_1, A_2, \dots, A_k$ là một điểm $G$ sao cho

$$\overrightarrow{GA_1} + \overrightarrow{GA_2} + \dots + \overrightarrow{GA_k} = \overrightarrow{0}.$$

⟦folio 37⟧

đi xe đạp, màu xanh - đi bộ. Hình này làm nổi bật biểu đồ chuyển động của một trong các xe rời đi $A$ và một trong các xe rời đi $A$ (các đường đứt nét $AC_3D_3B$ và $AA_2B_3B$). Từ đồ thị có thể thấy thời gian để mỗi xe chuyển động là $t_{\min}$.

Trường hợp $m=2$, $n=3$ được minh họa trên Hình 2: đồ thị chuyển động của vận tốc đầu tiên được thể hiện bằng màu tối; đỏ - thứ hai và đen - ERO thứ ba.

S. Krotov

F558. Một quả bóng nhỏ, nặng bay qua một lỗ bên trong quả cầu chính có cùng khối lượng, đi cách tâm quả cầu một khoảng $R/2$ ($R$ là bán kính của quả cầu). Sau khi bóng đi vào, lỗ sẽ tự động đóng lại. Giả sử va chạm giữa quả bóng và quả cầu là đàn hồi tuyệt đối, hãy tìm quỹ đạo của quả bóng và tâm của quả cầu trong hệ thống báo cáo mà quả cầu ban đầu được đào. Xác định các thông số của các quỹ đạo này và đánh dấu trên chúng những điểm xảy ra va chạm.

Hình 1.

Hình 2.

Hình 3.

Cho quả bóng bay vào lỗ với tốc độ $\vec{v}$ so với hệ thống báo cáo quả cầu được đào lần đầu tiên. Rõ ràng là mọi chuyển động sẽ xảy ra trong mặt phẳng nơi vectơ $\vec{v}$ và tâm của hình cầu nằm.

Khối lượng của quả bóng và quả cầu bằng nhau nên khối tâm của hệ sẽ chuyển động với vận tốc $\vec{v}/2$ dọc theo một đường thẳng nằm trong cùng một mặt phẳng và cách tâm quả cầu một khoảng $R/4$. Vì không có ngoại lực tác dụng lên hệ nên chuyển động của khối tâm sẽ không thay đổi ngay cả khi có bất kỳ va chạm nào trong hệ.

Theo điều kiện bài toán, các va chạm là đàn hồi tuyệt đối và các bề mặt nhẵn. Điều này có nghĩa là hình chiếu tiếp tuyến của vận tốc của quả bóng so với quả cầu không đổi, nhưng hình chiếu bình thường đổi dấu sang ngược lại. Do đó, với mỗi lần va chạm, mô hình vectơ vận tốc của quả bóng so với quả cầu không thay đổi và giữ nguyên bằng $|\vec{v}|$, đồng thời góc tới và góc phản xạ bằng nhau. Quỹ đạo của quả bóng so với quả cầu có dạng tam giác đều treo ở cạnh $R\sqrt{3}$ (màu đỏ trên Hình 1) và khoảng thời gian giữa các lần va chạm liên tiếp bằng $R\sqrt{3}/|\vec{v}|$.

Khối tâm của hệ so với quả cầu chuyển động với tốc độ bằng một nửa và quỹ đạo của nó cũng là một tam giác đều, nhưng từ cạnh $R\sqrt{3}/2$ (thể hiện bằng màu đen trong Hình 1).

Bây giờ chúng ta hãy xem xét một hệ thống báo cáo chuyển động lũy ​​tiến, trong đó không phải hình cầu đứng yên mà là khối tâm của hệ thống. Vận tốc của quả bóng và tâm quả cầu trong hệ này có độ lớn giống nhau, bằng $|\vec{v}|/2$ và chuyển động xảy ra dọc theo quỹ đạo được mô tả bằng màu tương ứng trong Hình 2 và 3.

Tóm lại, vẫn phải đi đến hệ thống ban đầu của báo cáo, trong đó quả cầu ban đầu được đào, quả bóng chuyển động với tốc độ $\vec{v}$, và khối tâm vẫn chuyển động với tốc độ $\vec{v}/2$ (Hình 4). Để chuyển đổi như vậy, cần phải thêm vectơ $\vec{v}/2$ vào tất cả các vectơ vận tốc được hiển thị trong Hình 2 và 3. Hóa ra là trước va chạm đầu tiên (sau “số 0”, hình tam giác, thứ sáu, $3n$th), quả bóng chuyển động với tốc độ có độ lớn bằng $|\vec{v}|$ và hướng song song với tốc độ (và quỹ đạo) của tâm khối, và xảy ra sự bất đồng $R\sqrt{3}$. Quả cầu sẽ tích lũy trong khoảng thời gian này.

Sau va chạm thứ nhất (thứ tư, thứ bảy,..., thứ $(3n+1)$), vectơ vận tốc của quả bóng hướng một góc $-\pi/3$ với vectơ vận tốc của khối tâm và có độ lớn bằng

⟦folio 38⟧

Trước va chạm thứ hai, quả bóng đi được quãng đường $R\sqrt{3}/2$. Tốc độ tương ứng của quả cầu hướng một góc $\pi/6$ với cùng một vectơ và mô hình của nó bằng $|\vec{v}|\sqrt{3}/2$. Quả cầu di chuyển theo đường $3R/2$.

Sau va chạm thứ hai (thứ năm, thứ tám,..., $(3n+2)$th), vectơ vận tốc của quả bóng và khối tâm tạo thành một góc $\pi/3$ và bằng $|\vec{v}|/2$ theo mô hình. Đường đi của quả bóng giống nhau, tức là $R\sqrt{3}/2$. Tốc độ cuối cùng của quả cầu lúc này là $\pi/6$, mô hình tốc độ $|\vec{v}|\sqrt{3}/2$, đường đi $3R/2$.

Sau đó, hình ảnh lặp lại, tức là giữa lần va chạm thứ ba và thứ tư, quả cầu lại kết thúc và quả bóng chuyển động với tốc độ $\vec{v}$, v.v.

B. Bukhovtsev

F559. Theo lý thuyết của Bethe, chu trình carbon của các phản ứng nhiệt hạch của sao bao gồm các phản ứng sau:

$$p + ^{12}C \rightarrow ^{13}N + \gamma,$$
$$^{13}N \rightarrow ^{13}C + e^{+} + v,$$
$$p + ^{13}C \rightarrow ^{14}N + \gamma,$$
$$p + ^{14}N \rightarrow ^{15}O + \gamma,$$
$$^{15}O \rightarrow ^{15}N + e^{+} + v,$$
$$p + ^{15}N \rightarrow ^{12}C + ^{4}He.$$

Bắt đầu năng lượng được giải phóng trong quá trình hình thành nốt ruồi của cơ thể.

Chu trình Bethe dẫn đến một nhân gel được hình thành từ bốn proton:

$$4p \rightarrow ^{4}He + 2e^{+} + 3\gamma + 2v.$$

Bằng cách tính năng lượng của các phần bên trái và bên phải bằng công thức $E = mc^2$, chúng ta tìm thấy năng lượng giải phóng trong quá trình tổng hợp một hạt nhân của nguyên tử gel ($m_p = 1,6724 \cdot 10^{27}$ kg, $m_{He} = 6,6439 \cdot 10^{27}$ kg, $m_{e} = 0,9108 \cdot 10^{30}$ kg, $c = 3 \cdot 10^8$ m/s):

$$E_{выд} = (4m_p - m_{He} - 2m_{e})c^2 = 0,3951 \cdot 10^{-11}$$ J.

Khi một mol gel được hình thành, năng lượng được giải phóng

$$W = E_{выд}N_A \approx 2,4 \cdot 10^9$$ kJ

(ở đây $N_A \approx 6 \cdot 10^{23}$ mol $^1$ là số Avogadro).

F560. Một tia phẳng vô hạn có độ dày $d_0$ kéo dài phần gật đầu trên mặt phẳng (Hình 1). Tốc độ của tia là $\vec{v}$, mật độ của nó là $\rho$. Máy bay phản lực lao vào dòng nào?

Chúng ta hãy biểu thị bằng $d_1$ và $d_2$ độ dày của các tia được hình thành (Hình 2) và bằng $\vec{v}_1$ và $\vec{v}_2$ vận tốc của chúng. Vì cùng một khối lượng chất lỏng đi qua tiết diện của tia rơi thứ nhất trong một giây cũng như đi qua tiết diện của cả hai tia hình thành, nên

$$\rho d_0 v = \rho d_1 v_1 + \rho d_2 v_2$$

(1)

(ở đây $v, v_1$ và $v_2$ là số mol của tốc độ tương ứng).

Chúng ta hãy chọn cái gọi là ống dòng chất lỏng (nó được hiển thị màu trong Hình 2) và xem xét phần của nó giữa các phần $I$ và $II$. Trong một thời gian ngắn $\Delta t$ cùng một khối chất lỏng chảy qua tiết diện $I$ trong diện tích $\Delta s$ và qua tiết diện $II$ trong diện tích $\Delta s_1$.

$$\Delta m = \rho \Delta s v \Delta t = \rho \Delta s_1 v_1 \Delta t.$$

Sự thay đổi động năng của khối chất lỏng này bằng công $A$ của các lực áp suất $\vec{F}$ và $\vec{F}_1$. Nếu khi đi qua $I$ thì công là dương, thì khi đi qua $II$ thì công là âm, do đó

$$A = F v \Delta t - F_1 v_1 \Delta t = p \Delta s v \Delta t - p_1 \Delta s_1 v_1 \Delta t,$$

trong đó $F$ và $F_1$ là số mol của lực áp, còn $p$ và $p_1$ lần lượt là áp suất trong các phần $I$ và $II$.

Nhưng áp suất ở cả tia bên trái và bên phải đều bằng áp suất trong tia rơi xuống (tất cả các tia đều có bề mặt phẳng tự do và áp suất trong chúng bằng áp suất khí quyển), tức là $p = p_1$. Bên cạnh đó,

$$\Delta s v \Delta t = \Delta s_1 v_1 \Delta t = \frac{\Delta m}{\rho}.$$

⟦folio 39⟧

Như vậy,

$$A = p \frac{\Delta m}{\rho} - p \frac{\Delta m}{\rho} = 0,$$

và độ biến thiên động năng của khối lượng $\Delta m$ của chất lỏng bằng 0, tức là $v_1 = v$. Bằng cách tương tự, có thể chứng minh rằng $v_2 = v$. Do đó, từ đẳng thức (1) chúng ta thu được

$$d_0 = d_1 + d_2.$$

(2)

Vì không có ngoại lực theo phương ngang tác dụng lên chất lỏng nên hình chiếu động lượng của chất lỏng theo phương ngang phải không đổi:

$$mv \cos \alpha = m_1 v_1 - m_2 v_2,$$

trong đó $m \sim d_0$, $m_1 \sim d_1$, $m_2 \sim d_2$ và $v = v_1 = v_2$. Kể từ đây,

$$d_0 \cos \alpha = d_1 - d_2.$$

(3)

Từ đẳng thức (2) và (3) ta thu được

$$d_1 = d_0 \cos^2 \frac{\alpha}{2} \quad \text{и} \quad d_2 = d_0 \sin^2 \frac{\alpha}{2}.$$

◆ a) Lực tác dụng dọc theo đường xích đạo lên phần dưới của bộ đồ tắm bằng trọng lượng của một cột nước phía trên bán cầu trên (Hình 1). Thể tích của cột này bằng thể tích của hình trụ có bán kính $R$ và chiều cao $H$ không có thể tích của bán cầu có bán kính $R$ nên mô hình trọng lượng nước bằng

$$P = \rho g \left( H \pi R^2 - \frac{2}{3} \pi R^3 \right).$$

Lực căng mà đường may của bộ đồ tắm phải chịu được bằng

$$\sigma_a = \frac{P}{2 \pi R} = \frac{1}{2} \rho g \left( HR - \frac{2}{3} R^2 \right).$$

b) Ở khoảng cách bằng hai mặt phẳng nhỏ có diện tích $\Delta s$ mỗi mặt, nằm ở khoảng cách $h$ phía trên và phía dưới tâm hình cầu (Hình 2). Mặt phẳng phía trên chịu tác dụng của một lực $\overrightarrow{F_1}$, mô hình của lực này là $F_1 = \rho g (H - h) \Delta s$. Hình chiếu của lực này lên mặt phẳng ngang bằng

$$F_1 \cos \alpha = \rho g (H - h) \Delta s \cos \alpha.$$

Lực $\overrightarrow{F_2}$ tác dụng lên mặt phẳng dưới, mô hình của nó $F_2 = \rho g (H + h) \Delta s$ và hình chiếu lên mặt phẳng ngang bằng

$$F_2 \cos \alpha = \rho g (H + h) \Delta s \cos \alpha.$$

Tổng của các phép chiếu này không phụ thuộc vào $h$ và bằng

$$2 \rho g H \Delta s \cos \alpha.$$

Nhưng $\Delta s$ cos $\alpha$ là hình chiếu của mặt phẳng $\Delta s$ lên mặt phẳng thẳng đứng. Theo đó, tổng của $F$ lực chiếu theo phương ngang tác dụng lên toàn bộ bán cầu phải bằng tích của $2 \rho g H$ với một nửa tiết diện phẳng của bán cầu đi qua đường kính thẳng đứng:

$$F = 2 \rho g H \frac{1}{2} \pi R^2 = \rho g H \pi R^2.$$

Lực căng mà đường may của bộ đồ tắm phải chịu được bằng

$$\sigma_a \approx \sigma_6 = \frac{1}{2} \rho g HR = 10^8 \text{ H/m}.$$
