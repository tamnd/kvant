---
id: 1972-1-resheniya-1e5b2af5
issue: kvant_1972_1
year: 1972
number: "1"
title: Lời giải bài toán M77—M83; F89—F91
rubric: zadachnik-kvanta
rubric_sub: Задачник «Кванта»
page_first: 41
page_last: 51
page_labels: 39, 40, 41, 42, 43, 47, 48, 49
tag: 0KHK
lang: vi
source: kvant_digital
extraction: vision
content_sha256: 9b117bcfc4f92db4f64f17b1d63b8ffa963e1589d583ae680d754c685e6e17b3
prompt_sha256: draft-1
translated_from: content/ru/1972/01/articles/13_resheniya-1e5b2af5.md
source_content_sha256: 266ec7e4286ea75ebe387033c0ee5079efaf6c3cfe17d59493ed5935f0dafa3e
translation_model: draft
translation_run: vi-draft-2026-10-31
translation_quality: draft
---

⟦folio 39⟧

Lời giải

Trong số này, chúng tôi xuất bản lời giải bài toán M77—M83

M77

Độ dài hai cạnh của tam giác là 10 và 15. Chứng minh rằng phân giác của góc giữa chúng không lớn hơn 12.

Chúng tôi đã nhận được rất nhiều lời giải khác nhau trong số bài toán này từ độc giả. Chúng ta hãy chỉ đưa ra ba.

I. Hãy thực hiện $DE \parallel BC$ (Hình 1). Khi đó tam giác $CDE$ là đều, do đó $CE=ED=x$ và $x$ người ta có thể tìm thấy điểm tương đồng của tam giác $ABC$ và $ADE$:

$$\frac{15-x}{15} = \frac{x}{10}, \text{ поэтому } x=6 \text{ и } CD < CE + ED = 2x=12.$$

II. Theo tính chất đường phân giác $BD/DA = BC/CA = \frac{2}{3}$. Hãy vẽ $BK \perp CD$ và $DL \perp CD$ cho đến khi chúng giao nhau với cạnh $AC$ (Hình 2). Sau đó $AK=AC - KC=AC - BC=5$ và $KL/LA=BD/DA = \frac{2}{3}$, do đó $KL=2$ và $CD < CL=12.$

III. (Trong hai thống kê “Phương pháp diện tích” «Kvant» Số 12, 1971, trang 41). Đặt $\Rightarrow BCD = \Rightarrow ACD = \alpha$, sau đó (Hình 3) $S_{\triangle ACD} + S_{\triangle BCD} = S_{\triangle ABC} \langle = \rangle al \sin \alpha + bl \sin \alpha = ab \sin 2\alpha,$

hình 1. Hình 2. Hình 3.

⟦folio 40⟧

bởi vì

$$l = \frac{2ab}{a+b} \cos \alpha = \frac{2 \cdot 10 \cdot 15}{25} \cos \alpha = 12 \cos \alpha < 12.$$

(Nhiều người cũng sử dụng các công thức khác cho đường phân giác:

$$l^2 = ab - mn = ab - \frac{abc^2}{(a+b)^2} = \frac{4abp(p-c)}{(a+b)^2}.$$

Có thể sử dụng một trong hai phương pháp này để chứng minh rằng đường phân giác $l$ của một tam giác nằm giữa hai cạnh $a$ và $b$ không vượt quá $\frac{2ab}{a+b}$ (trung bình điều hòa của các số $a$ và $b$). Ước tính này là không thể cải thiện được: với bất kỳ $l < \frac{2ab}{a+b}$ nào, người ta có thể dựng một tam giác có các cạnh $a$ và $b$ và một đường phân giác $l$ giữa chúng (hãy đảm bảo điều này!).

Hãy thử chứng minh hai mệnh đề tổng quát hóa bài toán sau đây:

1) Nếu trong tam giác $ABC$, trong đó $BC = a, AC = b$, điểm $D$ chia cạnh $AB$ so với $BD : DA = m : n$, thì $\frac{|mb - na|}{m + n} < CD < \frac{mb + na}{m + n}$. (Trong bài toán $m : n = a : b$ của chúng tôi).

2) Nếu đoạn $CD$ chia góc $BCA$ cho $\Rightarrow BCD : \Rightarrow DCA = p : q$ thì $CD < \frac{(p+q)ab}{pa + qb}$. (Trong bài toán $p : q = 1$ của chúng tôi; ở đây để chứng minh bạn có thể sử dụng bổ đề sau: nếu $0 < \alpha < \beta < \pi$ thì $\frac{\sin \alpha}{\alpha} > \frac{\sin \beta}{\beta}$).

**M78**

Chứng minh rằng mọi số nguyên không âm đều có thể được biểu diễn dưới dạng $\frac{(x+y)^2 + 3x + y}{2}$, trong đó $x$ và $y$ là các số nguyên không âm và biểu diễn số ít là gì.

Chúng ta hãy biểu thị tổng $x+y$ bằng $s$ và viết lại công thức này như sau:

$$n = \frac{(x+y)^2 + 3x + y}{2} = \frac{s^2 + s}{2} + s.$$ (1)

Các điều kiện $x$ và $y$ là số nguyên, $x \geq 0$ và $y \geq 0$ tương đương với các điều kiện sau: $x$ và $s$ là số nguyên, $x \geq 0$, $s \geq x$. Đối với một $s$ nhất định, giá trị $x$ có thể nhận các giá trị sau: $0, 1, \ldots, s$; giá trị tương ứng $n$, được xác định theo công thức (1), nhận các giá trị sau: $\frac{s^2 + s}{2}$, $\frac{s^2 + s}{2} + 1$, $\ldots$, $\frac{s^2 + s}{2} + s$. Vì vậy, mỗi $s = 0, 1, 2, \ldots$ tương ứng với một phân đoạn gồm $s+1$ số nguyên không âm $n$. Lưu ý rằng số cuối cùng của phân đoạn tương ứng với $s$ nhỏ hơn chính xác một số so với số đầu tiên của phân đoạn tương ứng với $s+1$:

$$\left( \frac{s^2 + s}{2} + s + 1 \right) = \frac{(s+1)^2 + (s+1)}{2}.$$

Do đó, các phân đoạn cũng sẽ chứa tất cả các số nguyên không âm $n$ và mỗi $n$ chỉ thuộc một phân đoạn, tức là nó sẽ tương ứng với chính xác một cặp giá trị $s$ và $x$ (Hình 4).

Nhiệm vụ lời giải. Chúng tôi đã chứng minh rằng công thức (1) cho phép chúng tôi “nội tuyến” tất cả các điểm $(x, y)$ có tọa độ nguyên không âm với các số $n=0, 1, 2, \ldots$. Hình 5 cho thấy các số này được sắp xếp theo thứ tự như thế nào.

Đúng lời giải phép cộng A. Abdulaev, M. Bukhanov, A. Gritsoryan, A. Zaslavsky, M. Illarionov, N. Kortsenko,

⟦folio 41⟧

L. Knizhnerman, V. Lozinov, V. Krivitsky, G. Makarov, A. Martynov, M. Praeger, M. Perelmuter, M. Rozov, V. Servakh, A. Slinkin, E. Turkevich, A. Udaltsov, V. Faitelevich, G. Filkovsky, A. Chernyak, K. Shilov, I. Sharlinsky. Một số người chứng minh khẳng định bài toán bằng quy nạp chỉ ra rằng không phải lúc nào cũng có thể chuyển từ điểm $(x, y)$ sang $(x+1, y-1)$: nếu $y=0$ thì cần phải lấy $(0, x+1)$ làm điểm tiếp theo sau $(x, 0)$.

E. Turkevich đưa ra lời giải một công thức tương tự như (1), cho phép chúng ta liệt kê các tập hợp không phải gồm hai mà gồm $k$ số nguyên không âm $(x_1, x_2, \dots, x_k)$:

$$n = C_{s_k}^{k+k-1} + C_{s_{k-1}}^{k-1} + k-2 + \dots + + C_{s_1}^{1},$$

ở đâu $s_i = x_1 + x_2 + \dots + x_i$,

$$C_p^q = \frac{p(p-1)\dots(p-q+1)}{1\cdot2\cdot\dots\cdot q}.$$

Ví dụ: đối với $k=3$ công thức là

$$n = \frac{s_3(s_3+1)(s_3+2)}{6} + \frac{s_2(s_2+1)}{2} + s_1 = \frac{1}{6}[(x_1+x_2+x_3)^3 + 3(x_1+x_2+x_3)^2 + 3(x_1+x_2)^2 + 11x_1 + 5x_2 + 2x_3].$$

Cố gắng khái quát hóa bài toán theo hướng khác: tìm công thức thiết lập sự tương ứng giữa tất cả các điểm $(x, y)$ trên mặt phẳng có tọa độ nguyên và tất cả các số nguyên (hoặc số nguyên không âm) $n$. Có thể viết công thức này dưới dạng đa thức bậc hai $n=f(x, y)$, giống như công thức (1) không?

**M79**

Hai điểm $P$ và $Q$ chuyển động dọc theo hai đường thẳng cắt nhau với cùng vận tốc không đổi $v$. Chứng minh rằng tồn tại một điểm cố định $A$ trên mặt phẳng thì khoảng cách từ đó đến các điểm $P$ và $Q$ tại mọi thời điểm đều bằng nhau.

Gọi $O$ là giao điểm của những đường này; $P_0$ và $Q_0$ là vị trí của điểm tại thời điểm đó $t_0$, khi chúng ở cùng khoảng cách với điểm $O$ ($t_0$ chính xác là ở giữa thời điểm điểm này và điểm kia đi qua điểm $O$); $A$ là giao điểm của các đường vuông góc với các đường thẳng đã cho, được khôi phục lần lượt tại các điểm $P_0$ và $Q_0$.

**Hình 6.**

Hãy chứng minh rằng điểm $A$ cũng chính là điểm cố định có sự tồn tại khẳng định trong điều kiện.

Trường hợp đặc biệt khi điểm $P_0, Q_0$ (và $A$) trùng với $O$ là rất đặc biệt. Trong trường hợp tổng quát (Hình 6), rõ ràng là các tam giác $AP_0O$ và $AQ_0O$ bằng nhau, do đó $AP_0=AQ_0$. Đặt $P$ và $Q$ là vị trí của điểm tại thời điểm tùy ý $t$ (khác với $t_0$). Khi đó $PP_0=QQ_0$ (các điểm di chuyển với cùng tốc độ), các hình tam giác $PP_0A$ và $QQ_0A$ bằng nhau dọc theo hai cạnh, do đó $AP=AQ$.

Từ lời giải của chúng tôi, rõ ràng rằng trên thực tế, một tuyên bố mạnh hơn là đúng hơn sự bằng nhau về khoảng cách từ điểm $A$ đến các điểm tương ứng $P$ và $Q$: nếu bạn xoay một trong các đường đã cho quanh điểm $A$ (theo một góc $P_0AQ_0$) sao cho nó trùng với điểm kia, thì tại bất kỳ thời điểm nào điểm đó $P$ trùng với điểm tương ứng $Q$.

**M80**

Bảng $m \times n$ xử lý các số tùy ý. Cho phép đổi dấu đồng thời tất cả các số trong một cột hoặc tất cả các số trên một hàng. Chứng minh rằng bằng cách lặp lại thao tác này nhiều lần, bạn có thể thu được một bảng trong đó các số ở cột bất kỳ và tổng các số ở hàng bất kỳ đều không âm.

Chúng ta sẽ đổi dấu hàng hoặc cột, trong đó khi đổi dấu thì tổng các số trong bảng tăng lên. Do đó, điểm này và điểm kia đi qua điểm $O$; $A$ là giao điểm của các đường vuông góc với các đường thẳng đã cho, lần lượt được phục hồi tại các điểm $P_0$ và $Q_0$.

⟦folio 42⟧

các số ở mỗi hàng, mỗi cột không âm.

Có thể chứng minh rằng trên thực tế, bảng $m \times n$ luôn có thể bị bỏ qua bởi tối đa các thao tác $\frac{m+n}{2}$.

Đúng lời giải gửi bởi: V. Kopylov, E. Rodionov, I. Ivanov, M. Ilarionov, V. Krivitsky, A. Zhumadildaev, A. Chernyak, A. Volbereg, N. Kornienko, E. Turkevich.

M81

Một điểm tùy ý $P$ được lấy bên trong hình vuông $A_1A_2A_3A_4$. Từ đỉnh $A_1$ một đường vuông góc được thả xuống đường $A_2P$, từ đỉnh $A_2$ đến $A_3P$, từ $A_3$ đến $A_4$ đến $A_1P$. Chứng minh rằng cả bốn đường vuông góc (hoặc phần mở rộng của chúng) cắt nhau tại một điểm.

Hãy xoay hình vuông (Hình 7) quanh tâm của nó ở $90^\circ$ sao cho đỉnh $A_2$ đi đến $A_1$, $A_3$ đến $A_2$, $A_4$ đến $A_3$ và $A_4$. Khi đó, mỗi đường thẳng $A_2P$, $A_3P$, $A_4P$, $A_1P$ sẽ đi vào đường vuông góc tương ứng (cuối cùng sẽ chuyển thành $90^\circ$!), do đó, cả bốn đường vuông góc sẽ đi qua một điểm $P'$, điểm $P$ đi vào đó khi rẽ.

M82

Trên đường vành đai tự động có một số đường tự động giống hệt nhau. Được biết, nếu đổ hết xăng của những chiếc xe số tự động này vào một thì chiếc xe này

![Diagram](image)

Hình 7.

M83

Chứng minh rằng các số 1, 2,..., $n$ với mọi $n$ không thể chia thành hai nhóm sao cho tích các số trong nhóm này bằng tích các số trong nhóm kia.

Như nhiều độc giả đã nhận thấy, mệnh đề bài toán tuân theo định lý sau: với $n$

*) E. B. Dynkin, S. A. Molchanov, A. L. Rosenthal., Những nhà toán học đương thời. Số học và đại số, “Khoa học”, bộ sách bổ sung “Thư viện của Trường Vật lý và Toán học” tập. 3*, 1970.

⟦folio 43⟧

Bất kỳ $x > 1$ nào giữa $x$ và $2x$ đều chứa ít nhất một số nguyên tố. Chứng minh đầu tiên của định lý này (“thủ tục Bertrand”) do P. L. Chebyshev thu được, được mô tả trong «Kvant» Số 5, 1970.

Chúng ta hãy lấy số nguyên tố $p$ sao cho $\frac{n}{2} < p < n$. Nó chỉ có thể được bao gồm trong một nhóm số và không có gì có thể “cân bằng” nó, vì $2p > n$. Bây giờ khẳng định bài toán suy ra từ định lý về tính duy nhất của phân tích nhân tử.

Chúng tôi không nhận được Lời giải không sử dụng tuyến tiền liệt của Bertrand.

N. V. Vasiliev

Trong số này, chúng tôi xuất bản lời giải bài toán F89—F91

F89

Điện trường cường độ trong sóng điện từ có tần số $\omega = 2 \cdot 10^{16} \text{сек}^{-1}$, được điều chế về biên độ với tần số $\Omega = 2 \cdot 10^{15} \text{сек}^{-1}$, thay đổi theo thời gian theo định luật $E = a (1 + \cos \Omega t)$ cos $\omega t$, trong đó $a$ là một hằng số. Xác định năng lượng của các electron bị sóng này đánh bật ra khỏi các nguyên tử khí hydro có sự ion hóa năng lượng $W = 13,5 \text{яб}$.

Một nguyên tử hấp thụ ánh sáng đơn sắc có tần số $\omega$ theo các phần (lượng tử) năng lượng bằng $\hbar \omega$, trong đó $\hbar = 1,05 \cdot 10^{-27} \text{эрэ} \cdot \text{сек}$ là hằng số Planck chia cho $2\pi$.

Vì $E = a (1 + \cos \Omega t)$ cos $\omega t = a \cos \omega t + \frac{1}{2} a \cos [(\omega - \Omega) t] + \frac{1}{2} a \cos [(\omega + \Omega) t]$, sóng biến đổi biên độ của chúng ta là tổng của ba sóng đơn sắc có tần số $\omega$, $\omega_1 = \omega - \Omega$ và $\omega_2 = \omega + \Omega$. Lượng tử năng lượng tương ứng với các sóng này tương ứng với

$$W_1 = \hbar \omega = 1,05 \cdot 10^{-27} \cdot 2 \cdot 10^{16} = 2,1 \cdot 10^{-11} \text{эрэ},$$
$$W_2 = \hbar \omega_1 = 1,05 \cdot 10^{-27} \cdot 1,8 \cdot 10^{16} = 1,89 \times 10^{-11} \text{эрэ},$$
$$W_3 = \hbar \omega_2 = 1,05 \cdot 10^{-27} \cdot 2,2 \cdot 10^{16} = 2,31 \cdot 10^{-11} \text{эрэ}.$$

Đồng thời, năng lượng danh nghĩa của nguyên tử hydro là

$$W = 13,5 \text{яб} = 13,5 \cdot 1,6 \cdot 10^{-12} \text{эрэ} = 2,16 \times 10^{-11} \text{эрэ}.$$

Năng lượng này lớn hơn $W_1$ và $W_2$. Do đó, sóng thứ nhất và sóng thứ hai không thể làm thay đổi nguyên tử hydro. Chỉ có làn sóng thứ ba mới có thể làm được điều này. Năng lượng của các electron $W_9$ bị đánh bật ra khỏi nguyên tử hydro sẽ bằng giá trị $W_9 - W = 1,5 \times 10^{-12} \text{эрэ}.$

lời giải chính xác đã được gửi bởi $T$. Ros-mozueva (Kokand, Liên Xô Uzbek).

F90

Một khí lý tưởng có khối lượng $m$, nằm ở nhiệt độ $T$, được làm lạnh đẳng tích sao cho áp suất giảm $n$ lần. Khí sau đó nở ra ở áp suất không đổi. Ở trạng thái cuối cùng, nhiệt độ của nó bằng nhiệt độ ban đầu. Xác định công mà khí thực hiện. Trọng lượng phân tử của khí là $\mu$.

Sơ đồ quá trình được thể hiện trên Hình 8. Công mà khí thực hiện là $A = p_2 (V_2 - V_1)$. Vì điểm 1 và 3 nằm trên cùng một đường đẳng nhiệt nên $p_1 V_1 = p_2 V_2$ và $V_2 = V_1 \frac{p_1}{p_2}$.

Pozny

$$A = p_2 V_1 \left( \frac{p_2}{p_1} - 1 \right) = \frac{1}{n} p_1 V_1 (n - 1).$$

Nhưng $p_1 V_1 = \frac{m}{\mu} RT$ do đó

$$A = \frac{m}{\mu} RT \left( \frac{n - 1}{n} \right).$$

bài toán này hóa ra lại dễ dàng và lời giải chính xác của nó đã được hơn 70 độc giả của tạp chí chúng tôi gửi.

Hình 8.

⟦folio none⟧

Để cấp nguồn cho thiết bị, điện áp ở đầu vào của thiết bị phải được đặt chính xác nhất có thể. Để làm điều này, hai biến trở được sử dụng, được kết nối như trong Hình 9. Chiều dài của các biến trở là như nhau và điện trở của một trong số chúng lớn hơn điện trở của biến trở kia 10 lần. Tôi nên làm gì để đặt điện áp chính xác nhất có thể? Độ chính xác của việc đặt điện áp sẽ lớn hơn bao nhiêu lần so với trường hợp chỉ sử dụng một mạch điện?

Nên bật biến trở như thế nào nếu để cấp nguồn cho thiết bị, cần đặt không phải điện áp mà là dòng điện càng chính xác càng tốt?

Biến trở $R_1$ ít ảnh hưởng đến điện áp trên thiết bị. Do đó, rõ ràng là trước tiên bạn cần đặt điện áp trên thiết bị bằng điện trở $R_2$, sau đó điều chỉnh bằng biến trở $R_1$.

Thật vậy, nếu chiều dài của biến trở bằng $l$ và độ chính xác trong việc đặt biến trở là $\Delta l$ thì độ chính xác về điện trở của biến trở $R_2$ bằng $\Delta l \frac{R_2}{l} = \frac{\Delta l}{l} R_2$ và độ chính xác

Hình 9.

Hình 10.

Độ chính xác trong việc cài đặt điện trở của biến trở $R_1$ bằng $\frac{\Delta l}{l} R_1 = \frac{1}{10} \frac{\Delta l}{l} R_2$, tức là kém hơn 10 lần so với độ chính xác khi cài đặt điện trở của biến trở $R_2$. Do đó, với chiến thuật mà chúng ta đã nói đến, có thể chọn điện trở của các biến trở chính xác hơn gấp 10 lần so với khi chỉ sử dụng một điện trở $R_2$. Điện áp rơi trên các biến trở và điện áp rơi trên thiết bị sẽ được xác định chính xác hơn nhiều.

Vì không rõ trước chúng ta sẽ sai theo hướng nào khi cài đặt điện trở $R_2$, tức là chúng ta sẽ phải làm gì với sự trợ giúp của biến trở $R_1$ - tăng hoặc giảm điện trở, nên trước khi lắp động cơ biến trở $R_2$ $R_1$ chúng ta cần lắp biến trở cuối cùng.

Nếu chúng ta cần thiết lập chính xác nhất có thể không phải điện áp trên thiết bị mà là dòng điện chạy qua nó, thì trong trường hợp này, các biến trở phải được kết nối song song với thiết bị dưới dạng shunt và điểm chính trong trường hợp này sẽ là biến trở có điện trở thấp hơn: thông qua nó, hầu hết các điểm sẽ chảy qua.

Biến trở thứ hai có điện trở cao phải được kết nối song song với hồng cầu (Hình 10) và cài đặt hiện tại như sau: đầu tiên đặt thanh trượt biến trở $R_2$ cuối cùng, sau đó đặt dòng điện bằng biến trở $R_1$ và điều chỉnh nó bằng biến trở $R_2$.

Vì dòng điện chạy qua biến trở bằng $I = \frac{U}{R}$ nên nếu điện trở của biến trở được đặt không chính xác $\Delta R$ thì độ chính xác trong việc đặt điểm là $\Delta I = \frac{U}{R} - \frac{U}{R + \Delta R} = \frac{U}{R(R + \Delta R)} \approx \frac{U}{R^2} \Delta R$.

Sử dụng điện trở $R_1$, chúng ta sẽ có được độ chính xác khi đặt điểm bằng $\frac{U}{R_2} \frac{\Delta l}{l} = \frac{1}{10} \frac{U}{R_1} \frac{\Delta l}{l}$, tức là sẽ kém hơn 10 lần so với khi chỉ sử dụng biến trở $R_1$.

lời giải chính xác được gửi bởi A. Alexandrov (Glazov, UASSR), V. Kovalev (Kommunarsk, vùng Voroshilovgrad), A. Demidov (Moscow), N. Fedin (Omsk).

Tôi. Sh. Tiếng Slovodechkiy

⟦folio none⟧

Năm 1972, trên các trang «Kvant» việc xuất bản các tài liệu sẽ tiếp tục dưới sự chỉ đạo của “Thực hành dành cho người đăng ký”. Việc nhận được bức thư gửi cho ban biên tập cho thấy chuyên mục này đang được nhiều độc giả của tạp chí quan tâm sâu sắc. Chúng tôi rất biết ơn tất cả những người đã cho chúng tôi ý kiến ​​​​và đề xuất của họ.

Tất nhiên, không có cách nào để giải hết tất cả các câu hỏi có trong chương trình thi tuyển sinh môn toán và vật lý. Có, không cần phải làm như vậy - những vấn đề này đã được nghiên cứu ở trường và được thảo luận chi tiết trong sách giáo khoa của trường. Do đó, ấn bản văn bản của chúng tôi cũng bao gồm các chủ đề, ở dạng này hay dạng khác, thường được sử dụng nhiều nhất trong lời giải cạnh tranh bài toán và gây khó khăn cho người nộp đơn.

Ví dụ, chúng tôi đề xuất nói về các bài toán về sự kết hợp của các vật thể không gian, về các yêu cầu đối với định nghĩa toán học, về lời giải bài toán trong phép đo lập thể và cách sử dụng hợp lý hình vẽ trong các bài toán hình học. Trong vật lý, các bài báo sẽ được xuất bản liên quan đến các vấn đề như định luật bảo toàn động lượng, lời giải bài toán về các quá trình, các định luật hiện hành và những vấn đề khác.

Các vấn đề lý thuyết được xem xét trong các bài viết này đi kèm với việc phân tích các ví dụ cụ thể, thường được lấy từ các phiên bản của bài thi đầu vào. Ở cuối mỗi bài viết sẽ có một bài toán dành cho một lời giải độc lập để giúp người đọc kiểm tra tiến độ đọc những gì họ đọc. Những bài toán này cũng chủ yếu được lấy từ các phương án thi tuyển sinh những năm gần đây.

Cân nhắc mong muốn của nhiều độc giả, vì mục đích cung cấp thông tin, chúng tôi sẽ tiếp tục đưa vào các lựa chọn bài toán, đã được đưa ra trong các kỳ thi viết ở nhiều trường đại học khác nhau trong nước vào năm 1971. Việc làm quen với những tài liệu này sẽ cho phép thí sinh hình dung cụ thể bài thi viết mẫu là gì và thử sức mình với lời giải đặt bài toán trước trong một thời gian giới hạn (thường là 4 giờ). Ví dụ: bạn có thể đề nghị những người đăng ký trang thực hiện một “bài kiểm tra” độc lập bằng cách giải toàn bộ phương án trong 4 giờ và ghi lại. Việc đào tạo như vậy càng gần với điều kiện thi càng tốt, hóa ra lại đặc biệt hiệu quả. Chúng tôi chỉ lưu ý rằng bạn cần tham dự khóa học sau khi đã nghiên cứu kỹ các phần lý thuyết.

⟦folio 47⟧

2. Giải phương trình
$$\sqrt{5x-6} = x.$$
ODZ: $x \geqslant \frac{6}{5}$. Đối với các giá trị $x$ như vậy, cả hai vế của phương trình đều không âm. Do đó, theo Định lý 2 (chúng ta lấy ODZ làm tập $M$), chỉ những nghiệm của phương trình $5x-6 = x^2$ nằm trong ODZ mới là nghiệm của phương trình này. Vì các nghiệm $x_1=2, x_2=3$ của phương trình bậc hai này thỏa mãn bất đẳng thức $x \geqslant \frac{6}{5}$ nên cả hai đều là nghiệm của phương trình ban đầu. Và trong trường hợp này, việc kiểm tra các giá trị thu được bằng cách thay thế vào phương trình ban đầu là không cần thiết.

3. Giải phương trình
$$\sqrt{x^2-3} = \sqrt{x-1}.$$
ODZ được xác định bởi hệ bất đẳng thức
$$\begin{cases} x^2-3 \geqslant 0, \\ x-1 \geqslant 0, \end{cases}$$
từ đâu $x \geqslant \sqrt{3}$. Bằng cách bình phương cả hai vế của phương trình và sử dụng các công thức biến đổi căn thức, chúng ta thu được phương trình bậc hai $x^2-x-2=0$, từ đó $x_1=2, x_2=-1$. Odz chỉ xác định giá trị của $x_1=2$; nó là nghiệm duy nhất của phương trình ban đầu.

4. Giải phương trình
$$\sqrt{x+1} = 8-\sqrt{3x+1}.$$ (1)
ODZ: $x \geqslant -\frac{1}{3}$. Vế trái của phương trình này là dương (trong ODZ), nhưng vế phải có thể nhận cả giá trị dương và âm. Vì vậy, bạn không nên vội bình phương cả hai vế của phương trình - kết quả là có thể xuất hiện nghiệm.

Điều này rất dễ tránh - chỉ cần viết lại phương trình (1) ở dạng
$$\sqrt{x+1}+\sqrt{3x+1} = 8.$$
Ở đây cả hai vế đều không âm và việc bình phương sẽ không dẫn đến sự xuất hiện của lời giải được xây dựng. Do đó, nhiệm vụ trùng hợp với việc tìm nghiệm của phương trình thuộc ODZ
$$\sqrt{3x^2+4x+1} = 31-2x.$$ (2)

Một lần nữa chúng ta phải bình phương cả hai vế của phương trình này và một lần nữa chúng ta phải đối mặt với mối nguy hiểm tương tự - cấu trúc lời giải có thể xuất hiện (vế phải của phương trình (2) nhận giá trị của các biểu tượng khác nhau trong ODZ).

Một điều chúng tôi lưu ý là không có một giá trị nào của $x$ mà $31-2x < 0$ có thể dùng làm nghiệm của phương trình (2) (bất kỳ số dương nào cũng sẽ bằng số âm!). Nói cách khác, mọi nghiệm của phương trình (2) đều thỏa mãn bất đẳng thức $x \leqslant 31/2$; chúng ta chỉ quan tâm đến những nghiệm thỏa mãn điều kiện $x \geqslant -1/3$.

Do đó, chúng ta phải tìm các phương trình lời giải (2) thuộc khoảng $-\frac{1}{3} \leqslant x \leqslant 31/2$. Dựa vào Định lý 2, chúng ta có thể chắc chắn rằng trên khoảng này phương trình (2) tương đương với phương trình
$$3x^2+4x+1 = (31-2x)^2.$$
Chỉ có một nghiệm $x=8$ của phương trình bậc hai tốt nhất thỏa mãn điều kiện $-\frac{1}{3} \leqslant x \leqslant 31/2$; nó đóng vai trò là lời giải của phương trình (1). Việc kiểm tra bằng cách thay thế rõ ràng là không cần thiết.

5. Giải phương trình
$$\sqrt{x^2+x-5}+\sqrt{x^2+8x-4} = 5.$$ (3)
ODZ được định nghĩa là lời giải hệ bất đẳng thức
$$\begin{cases} x^2+x-5 \geqslant 0, \\ x^2+8x-4 \geqslant 0. \end{cases}$$
Tuy nhiên, chúng ta có thể không giải được hệ này, nhưng hãy nhớ rằng bất kỳ nghiệm nào của phương trình (3) đều phải thỏa mãn các bất đẳng thức tổng quát (4).

Tất nhiên, tất cả các điều kiện của Định lý 2 đều được thỏa mãn—chúng ta có thể bình phương phương trình (3) mà không sợ xuất hiện lời giải được xây dựng. Nhưng than ôi! Ở đất nước này hoạt động này

⟦folio 48⟧

không phù hợp. Bình phương cả hai vế của phương trình (3) và bạn sẽ thấy phương trình trở nên phức tạp như thế nào.

Sẽ thuận tiện hơn nhiều khi làm điều này: chúng ta viết lại phương trình (3) dưới dạng

$$\sqrt{x^2+x-5} = 5 - \sqrt{x^2+8x-4}$$

và bình phương cả hai phần của nó. Tất nhiên, bây giờ Định lý 2 không được áp dụng và sự biến đổi này có thể dẫn đến sự xuất hiện của các nghiệm được xây dựng. Do đó, chúng tôi sẽ cần phải kiểm tra - nó sẽ loại bỏ cấu trúc lời giải (nếu chúng xuất hiện).

Vì vậy, hãy bình phương cả hai vế của phương trình (5); chúng tôi nhận được

$$10\sqrt{x^2+8x-4} = 7x + 26.$$

Chúng tôi áp dụng lại các phép toán tương tự cho phương trình này. Nhưng trước tiên chúng ta lưu ý rằng tất cả các nghiệm của nó phải thỏa mãn điều kiện $7x+26 \geq 0$, tức là $x \geq -26/7$.

Kết quả là chúng ta đi đến phương trình

$$51x^2+436x-1076 = 0,$$

từ đâu $x_1=2, x_2=-\frac{538}{51}$. Lưu ý rằng $x_2 < -\frac{26}{7}$, vẫn phải kiểm tra giá trị của $x_1=2$ bằng cách thay thế trực tiếp vào phương trình ban đầu (3). Hóa ra nó là nghiệm của phương trình (3).

Xin lưu ý: trong lời giải chúng ta không cần giải hệ bất phương trình (4) mô tả OD của phương trình ban đầu.

Giới thiệu các ẩn số phụ

Việc giới thiệu thành công các ẩn số phụ trợ đôi khi giúp có thể đạt được lời giải nhanh hơn và dễ dàng hơn.

6. Giải phương trình

$$(x+5)(x-2)+3\sqrt{x(x+3)}=0.$$

Hãy viết lại phương trình như thế này:

$$x^2+3x-10+3\sqrt{x^2+3x}=0.$$

Có thể thấy rằng nếu ẩn số phụ là $y=\sqrt{x^2+3x}$ thì phương trình có dạng $y^2+3y-10=0$, do đó $y_1=-5, y_2=2$.

Bây giờ bài toán giảm xuống lời giải của phương trình $\sqrt{x^2+3} = -5$ và phương trình $\sqrt{x^2+3x} = 2$. Phương trình đầu tiên không có lời giải, nhưng từ phương trình thứ hai chúng ta thu được $x_1=-4, x_2=1$.

7. Giải phương trình

$$\sqrt{47-2x}+\sqrt{35+2x}=4.$$

Nâng cả hai vế của phương trình này lên lũy thừa 4 không hứa hẹn điều gì tốt đẹp. Nếu chúng ta đặt

$$y=\sqrt{47-2x}, z=\sqrt{35+2x},$$

thì phương trình (6) được viết lại như sau:

$$y+z=4.$$

Vì chúng ta đã giới thiệu hai hàm mới chưa biết, nên chúng ta cần tìm một phương trình khác liên quan đến $y$ và $z$. Để làm điều này, chúng ta nâng các đẳng thức (7) lên lũy thừa bậc bốn và lưu ý rằng $y^4+z^4=82$.

Vậy ta cần giải hệ phương trình

$$\begin{cases} y+z=4, \\ y^4+z^4=82; \end{cases}$$

nó có hai (thực) lời giải: $y_1=1, z_1=3; y_2=3, z_2=1$. Vẫn còn phải giải hệ (của hai phương trình với một phương trình chưa biết!)

$$\begin{cases} \sqrt{47-2x}=3, \\ \sqrt{35+2x}=1 \end{cases}$$

và hệ thống

$$\begin{cases} \sqrt{47-2x}=1, \\ \sqrt{35+2x}=3; \end{cases}$$

cái đầu tiên cho $x_1=-17$, cái thứ hai cho $x_2=23$.

Nhân cả hai vế của phương trình với một hàm

Đôi khi một phương trình vô tỉ có thể được giải khá nhanh nếu nhân cả hai vế với một hàm số được chọn đúng. Tất nhiên, khi nhân cả hai vế của phương trình với một hàm nào đó, kết cấu lời giải có thể xuất hiện hoặc kết quả này có thể trở thành số không

⟦folio 49⟧

chức năng*). Do đó, phương pháp đề xuất đòi hỏi phải nghiên cứu bắt buộc các giá trị kết quả.

8. Giải phương trình
$$\frac{1}{4} x = (\sqrt{1+x} - 1)(\sqrt{1-x} + 1).$$
(8)

Hãy nhân cả hai vế của phương trình với cùng một hàm $h(x) = \sqrt{1+x} + 1$. Biểu thức $\sqrt{1+x} + 1$ được gọi là liên hợp của biểu thức $\sqrt{1+x} - 1$. Có vẻ như mục đích của phép nhân như vậy rất rõ ràng: lợi dụng thực tế là tích của hai biểu thức liên hợp không còn chứa các căn thức.

Kết quả của phép nhân này và các phép biến đổi rất quan trọng, chúng ta đi đến phương trình

$$x(\sqrt{1+x} - 4\sqrt{1-x} - 3) = 0.$$

Nó có một nghiệm duy nhất $x=0$, vì phương trình $\sqrt{1+x} - 4\sqrt{1-x} - 3 = 0$ lời giải không có (hãy kiểm tra xem!).

Thay thế vào phương trình (8) cho thấy $x=0$ là một nghiệm. Mặt khác, bạn có thể thực hiện mà không cần thay thế: phương trình $h(x)$không biến mất ở đâu, và do đó nhân phương trình tổng quát (8) với hàm này không dẫn đến sự xuất hiện của lời giải được xây dựng.

9. Giải phương trình
$$\sqrt{2x^2+3x+5} + \sqrt{2x^2-3x+5} = 3x.$$ (9)

Nhân cả hai vế của phương trình với biểu thức
$$\sqrt{2x^2+3x+5} - \sqrt{2x^2-3x+5},$$
cách chia động từ cho biểu thức ở phía bên trái. Sau khi ước tính các phép biến đổi, chúng tôi thu được

$$x(\sqrt{2x^2+3x+5} - \sqrt{2x^2-3x+5}) = 2x.$$

*) Xem «Kvant» Số 5, 1970, trang 49-50.

Phương trình này có nghiệm $x=0$, nhưng giá trị này không thỏa mãn phương trình ban đầu (9). Do đó, chúng ta có thể giả sử rằng $x \neq 0$ và giảm cả hai vế của phương trình cuối cùng bằng $x$:

$$\sqrt{2x^2+3x+5} - \sqrt{2x^2-3x+5} = 2.$$ (10)

Cộng các phương trình (9) và (10), ta thu được phương trình.

$$2\sqrt{2x^2+3x+5} = 2 + 3x,$$

lời giải có vẻ không khó hơn. Nó có gốc $x=4$ (hãy chắc chắn về điều này!).

Việc kiểm tra cần thiết trong trường hợp này cho thấy giá trị này thỏa mãn phương trình (9).

Bài tập

Giải phương trình:

1. $$\sqrt{25-x} = 2 - \sqrt{9+x}.$$
2. $$\sqrt{x+2} - \sqrt{3x+2} = 0.$$
3. $$\frac{\sqrt{12+x}}{x} + \frac{\sqrt{12+x}}{12} = \frac{64}{3}\sqrt{x}.$$
4. $$\frac{(5-x)\sqrt{5-x} + (x-3)\sqrt{x-3}}{\sqrt{5-x} + \sqrt{x-3}} = 2.$$
5. $$\sqrt{x-2} + \sqrt{x+2} = 2.$$
6. $$\frac{\sqrt{x+4} + \sqrt{x-4}}{2} = x + \sqrt{x^2-16} - 6.$$
7. $$\sqrt{3\sqrt{4-4x+x^2}} + \sqrt{3\sqrt{49+14x+x^2}} = 3 + \sqrt{3\sqrt{14-5x-x^2}}.$$
8. (MSU, nhà vật lý, 1968.) Với mỗi số hoạt động $a$, hãy tìm tất cả các phương trình lời giải thực $x + \sqrt{x} = a$.
9. (MSU, nhà vật lý, 1968.) Với mỗi số hoạt động $a$, hãy tìm tất cả các phương trình lời giải thực $a\sqrt{1+x} + \frac{a}{x}\sqrt{1+x} = \sqrt{x}$.
