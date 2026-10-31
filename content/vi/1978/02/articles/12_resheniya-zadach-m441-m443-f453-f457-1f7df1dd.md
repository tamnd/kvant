---
id: 1978-2-resheniya-zadach-m441-m443-f453-f457-1f7df1dd
issue: kvant_1978_2
year: 1978
number: "2"
title: Lời giải bài toán M441—M443; F453—F457
rubric: zadachnik-kvanta
rubric_sub: Задачник «Кванта»
page_first: 30
page_last: 35
page_labels: 28, 29, 31, 32, 33
tag: KWGJ
lang: vi
source: kvant_digital
extraction: vision
content_sha256: a289d2520e353079471b03e3721d51accb51d9469e9552acdfeebd229e0b2b5c
prompt_sha256: draft-1
translated_from: content/ru/1978/02/articles/12_resheniya-zadach-m441-m443-f453-f457-1f7df1dd.md
source_content_sha256: 4cb5a8a476689166bbdfab23567acdee17e903951de430bab922f381072c5515
translation_model: draft
translation_run: vi-draft-2026-10-31
translation_quality: draft
---

⟦folio 28⟧

Lời giải bài toán
M441 — M443; F453 — F457

M441. Lấy điểm P bên trong không gian 2n lồi. Một đường thẳng được vẽ qua mỗi đỉnh và điểm P. Hãy chứng minh rằng có một cạnh của đa giác mà không có đường thẳng nào có điểm chung (có lẽ ngoại trừ hai đầu của cạnh đó).

Cơm. 1.

Trong nội bộ, chúng ta nói rằng một đường thẳng cắt một cạnh của đa giác M nếu giao điểm của chúng không trùng với đỉnh của đa giác.

Có thể xảy ra hai trường hợp: 1) điểm P thuộc đường chéo AB nào đó của đa giác M; 2) điểm P không thuộc bất kỳ đường chéo nào của đa giác M.

Trong trường hợp thứ nhất, các đường thẳng PA và PB trùng với (AB) và không cắt bất kỳ cạnh nào của M, đồng thời các đường thẳng đi qua điểm P và 2n-2 đỉnh còn lại của M cắt nhau nhiều nhất 2n-2 cạnh. Do đó, ít nhất hai cạnh của đa giác M không cắt nhau bởi bất kỳ đường vẽ nào.

Bây giờ, giả sử P không nằm trên bất kỳ đường chéo nào của M. Chúng ta lấy đường chéo AB của đa giác M chia ranh giới của nó thành hai đường đứt đoạn n liên kết Γ1 và Γ2, và 2n-giác M thành hai lồi (n+1)-giác M1 và M2 (Hình 1). Giả sử P nằm trong M1; và gọi C là một đỉnh tùy ý của đa giác M2 (khác A và B). Vì M1 và M2 nằm ở các cạnh đối diện của (AB), P∈M1, C∈M2 và đa giác M là lồi nên các đường thẳng PC và AB cắt nhau tại một điểm nào đó K∈[AB] (xem Hình 1). Đường thẳng PC đi qua điểm trong của đa giác M1 và cắt đường biên của nó tại điểm K trên cạnh AB cắt đường biên của M1 tại một điểm khác không nằm trên AB, tức là cắt Γ1. Như vậy, đường thẳng bất kỳ đi qua các đỉnh Γ2 (trừ A và B) cắt đường biên của đa giác lồi M tại hai điểm: đỉnh Γ2 và một điểm nằm trên Γ1 (có thể trùng với đỉnh Γ1). Do đó, mọi đường thẳng đều không cắt các đoạn của đường gãy Γ2.

Bằng cách tương tự, người ta chứng minh rằng các đường thẳng AP và BP cũng không cắt các đoạn của đường đứt nét Γ2.

Vì vậy, n+1 đường thẳng cắt nhau ở tối đa n cạnh của đa giác M (liên kết của đường gãy Γ1). N-1 đường thẳng còn lại không thể cắt quá n-1 cạnh của đa giác M (liên kết của đường gãy Γ2). Do đó, ít nhất một cạnh (trong số các đường đứt nét Γ2) không bị cắt bởi bất kỳ đường thẳng nào vẽ qua điểm P và các đỉnh của đa giác M.

G. Gurevishch

Hãy viết lại tổng $a_1 + a_2 + a_3 + \dots + a_{p-1}$ như thế này:

$$(a_1 + a_{p-1}) + (a_2 + a_{p-2}) + \dots + (a_{\frac{p-1}{2}} + a_{\frac{p+1}{2}})$$

($p-1$ là số chẵn; trong tổng cuối cùng có biểu thức $\frac{p-1}{2}$ trong ngoặc đơn). Hãy xem xét một trong các biểu thức $a_i + a_{p-i}$, được đặt trong ngoặc. Thật dễ dàng để thấy điều đó

$$i^p + (p-i)^p = p^p - C_p^1 \cdot i \cdot p^{p-1} + \dots + C_p^{p-1} \cdot i^{p-1} \cdot p = p^2 l$$

— chia hết cho $p^2$ (vì $C_p^{p-1} = p$; $p > 2$, $1 \leq i \leq p-1$). Do đó $a_i + a_{p-i}$ chia hết cho $p^2$; và vì $a_i < p^2$, $a_{p-i} < p^2$, nên $a_i + a_{p-i} = p^2$ cho tất cả $i = 1, \dots, p-1$. Vì thế,

$$a_1 + a_2 + \dots + a_{p-1} = (a_1 + a_{p-1}) + \dots +$$

$$+ (a_{\frac{p-1}{2}} + a_{\frac{p+1}{2}}) = p^2 \cdot \frac{p-1}{2} = (p^3 - p^2)/2$$

đó là những gì đã được nêu.

S.Okhimin

⟦folio 29⟧

M443. Có một bảng gồm các ô $n \times n$, trong mỗi ô có giá trị ban đầu là 0. Được phép chọn ngẫu nhiên các số $n$, đứng ở các hàng khác nhau và các cột khác nhau và thông báo cho mỗi ô bằng 1.

a) Có thể lấy được bảng trong Hình 2 và 3 chỉ trong vài bước không?

b) Có thể lập được một bảng có các số phân biệt theo từng cặp không?

b) Có thể thu được loại bảng nào sau $T$ bước?

Cơm. 2.

| 1 | 2 | 3 | • • • | $n$ |
| :--- | :--- | :--- | :--- | :--- |
| 2 | 3 | 4 | • • • | 1 |
| 3 | 4 | 5 | • • • | 2 |
| • • | • • | • • | • • | • |
| • • | • • | • • | • • | • |
| $n$ | 1 | 2 | • • • | $n-1$ |

Cơm. 3.

| 1 | 2 | 3 | • • • | $n$ |
| :--- | :--- | :--- | :--- | :--- |
| 2 | 3 | 4 | • • • | $n+1$ |
| 3 | 4 | 5 | • • • | $n+2$ |
| • • | • • | • • | • • | • |
| • • | • • | • • | • • | • |
| $n$ | $n+1$ | $n+2$ | • • • | $2n-1$ |

Cơm. 4.

Dễ dàng có được bảng trong Hình 2 bằng cách cộng các bảng trong đó các đơn vị được xây dựng song song với đường chéo (Hình 4).

Bây giờ chúng ta hãy chuyển thẳng tới bài toán c). Trước hết, chúng tôi lưu ý rằng trong bảng $n \times n$, thu được từ 0 trong các bước $T$, tổng các số ở mỗi hàng và mỗi cột đều bằng nhau và bằng $T$. Lúc đầu, tất cả các tổng này đều bằng 0 và bằng cách thêm một vào các số $n$ ở các hàng khác nhau và các cột khác nhau của bảng, chúng ta thay đổi tất cả các tổng bằng nhau - chính xác là một cho mỗi số. Vì vậy, điều kiện để bằng tổng các số ở mỗi hàng và mỗi cột là thuộc tính cần thiết 3, không thể có được bằng cách biểu thị các phép biến đổi.

Hãy chứng minh rằng điều kiện bằng nhau của tổng theo hàng và cột cũng đủ. Khi làm như vậy, chúng ta sẽ dựa vào một bổ đề quan trọng như vậy. Cho một bảng $n \times n$ chứa đầy các số nguyên không âm, trong đó tổng các số ở hàng và cột bằng nhau (chúng ta sẽ gọi những bảng đó là ma thuật). Sau đó, nếu bảng này không bằng 0 thì nó có thể chứa một tập hợp các số $n$ nằm ở các hàng và cột khác nhau của bảng, mỗi số đều khác 0.

Bổ đề ngay lập tức cho thấy rằng bất kỳ bảng ma thuật nào cũng có thể thu được từ bảng số 0. Trong thực tế, giả sử tổng trên các hàng và cột là các số không âm, trong đó tổng các số trên các hàng và cột bằng nhau (chúng ta sẽ gọi những bảng như vậy là ma thuật). Sau đó, nếu bảng này không bằng 0 thì nó có thể chứa một tập hợp các số $n$ nằm ở các hàng và cột khác nhau của bảng, mỗi số đều khác 0.

Vì vậy, việc còn lại là chứng minh bổ đề. Chúng ta hãy xây dựng nó theo cách này: nếu trong số $n$ số tùy ý của bảng từ $n \times n$, nằm ở các hàng và cột khác nhau, có ít nhất một số 0, thì chúng ta sẽ lại chọn một tập hợp $n$ số 0 từ bảng này (từ các hàng khác nhau và các cột khác nhau), tính lại một từ mỗi số này và chuyển sang bảng ma thuật với tổng $T-2$ theo mỗi hàng và mỗi cột, v.v.; - trong $T$ bước, chúng ta sẽ nhận được một bảng có tổng bằng 0, tức là một bảng bằng 0. Di chuyển theo hướng ngược lại, chúng ta có thể thu được bảng gốc $M$ từ bảng 0.

Vì vậy, việc còn lại là chứng minh bổ đề. Chúng ta hãy xây dựng nó theo cách này: nếu trong số $n$ số tùy ý của bảng từ $n \times n$, nằm ở các hàng và cột khác nhau, có ít nhất một số 0, thì chúng ta sẽ lại chọn một tập hợp $n$ số 0 từ bảng này (từ các hàng khác nhau và các cột khác nhau), tính lại một từ mỗi số này và chuyển sang bảng ma thuật với tổng $T-2$ theo mỗi hàng và mỗi cột, v.v.; - trong $T$ bước, chúng ta sẽ nhận được một bảng có tổng bằng 0, tức là một bảng bằng 0. Di chuyển theo hướng ngược lại, chúng ta có thể thu được bảng gốc $M$ từ bảng 0.

Vì vậy, việc còn lại là chứng minh bổ đề. Chúng ta hãy xây dựng nó theo cách này: nếu trong số $n$ số tùy ý của bảng từ $n \times n$, nằm ở các hàng và cột khác nhau, có ít nhất một số 0, thì chúng ta sẽ lại chọn một tập hợp $n$ số 0 từ bảng này (từ các hàng khác nhau và các cột khác nhau), tính lại một từ mỗi số này và chuyển sang bảng ma thuật với tổng $T-2$ theo mỗi hàng và mỗi cột, v.v.; - trong $T$ bước, chúng ta sẽ nhận được một bảng có tổng bằng 0, tức là một bảng bằng 0. Di chuyển theo hướng ngược lại, chúng ta có thể thu được bảng gốc $M$ từ bảng 0.

⟦folio 31⟧

trong đó $x_1, x_2$ và $x_3$ là tọa độ ban đầu của các khối có khối lượng $m_1, m_2$ và $M$ so với nguồn gốc tùy ý của báo cáo.
Từ đây

$$l_0 = \frac{m_1}{m_1 + m_2} l.$$

I. Slobodetsky

Cơm. 7.

F454. Nếu đặt hướng $U_0 = 220$ V vào cuộn sơ cấp của máy biến áp không tiếp xúc thì hướng trên cuộn thứ cấp sẽ là $U_1 = 127$ V. Hướng $U$ sẽ là $U_0 = 220$ V theo hướng $R = 10$ Ohm nối với cuộn thứ cấp của máy biến áp này như thế nào? Điện trở hoạt động của cuộn sơ cấp của máy biến áp là $r_1 = 2$ Ohm, và cuộn thứ cấp là $r_2 = 1$ Ohm. Điện trở trong của máy tạo moka bằng 0.

Hãy để chúng tôi biểu thị giá trị hiệu quả của emf. cảm ứng xảy ra trong cuộn sơ cấp của máy biến áp không tiếp xúc thông qua $E_1$ và trong cuộn thứ cấp thông qua $E_2$. Rõ ràng là

$$\frac{E_1}{E_2} = \frac{n_1}{n_2} = k,$$

trong đó $n_1$ là số vòng dây ở cuộn sơ cấp, $n_2$ - ở cuộn thứ cấp và $k = n_1/n_2$ là hệ số biến đổi. Vì trong máy biến áp không phải bên ngoài

$$E_1 = U_0 \text{ и } E_2 = U_1,$$

Cái đó

$$k = \frac{E_1}{E_2} = \frac{U_0}{U_1} = \sqrt{3}.$$

Khi máy biến áp mang tải tức là điện trở $R$ được nối vào cuộn thứ cấp, dòng điện chạy qua cuộn sơ cấp

$$I_1 = \frac{U_0 - E_1'}{r_1},$$

và trên cuộn dây thứ cấp—

$$I_2 = \frac{E_2'}{R + r_2}.$$

Ở đây $E_1'$ và $E_2'$ là giá trị hiệu dụng của emf. cảm ứng ở cuộn sơ cấp và thứ cấp của máy biến áp có tải.

Hiệu suất của máy biến áp gần như bằng 1. Điều này có nghĩa là công suất ở cuộn sơ cấp của máy biến áp bằng công suất truyền vào mạch thứ cấp:

$$I_1 E_1' = I_2 E_2'.$$

Sau đó

$$\frac{I_2}{I_1} = \frac{E_1'}{E_2'} = k.$$

Hãy kết hợp các phương trình (1), (2) và (3) trong hệ thống:

$$\begin{align*}
I_1 &= \frac{U_0 - E_1'}{r_1} \\
I_2 &= \frac{E_2'}{R + r_2} \\
\frac{I_2}{I_1} &= k,
\end{align*}$$

Ở đâu

$$I_2 = \frac{k U_0}{r_1 + k^2 (R + r_2)},$$

Và

$$U_2 = I_2 R = \frac{k U_0 R}{r_1 + k^2 (R + r_2)} \approx 110 \text{ B}.$$

V. Skorovarov

⟦folio 32⟧

F455. Tổn thất điện năng trên đường dây truyền tải điện là 5% lượng điện năng mà hộ tiêu thụ nhận được. Bạn cần thay đổi điện áp ở đầu vào đường dây và điện trở của người tiêu dùng đối với mono như thế nào để với cùng một công suất mà người tiêu dùng nhận được, mức tiêu thụ trong đường dây giảm xuống 1%?

Công suất mà người tiêu dùng nhận được bằng

$$P = I_0^2 R = \frac{U_0^2}{(R + r)^2} R,$$

trong đó $I_0$ là dòng điện trong đường dây truyền tải điện, $r$ là điện trở đường dây, $R$ là điện trở của người tiêu dùng và $U_0$ là điện áp ở đầu vào đường dây. Sức mạnh này theo điều kiện phải không thay đổi. Kể từ đây,

$$\frac{U_0^2}{(R + r)^2} R = \frac{U_1^2}{(R_1 + r)^2} R_1,$$

trong đó $U_1$ là điện áp mới ở đầu vào đường dây và $R_1$ là điện trở mới của người tiêu dùng. Chúng ta hãy biểu thị bằng $\alpha$ tỷ lệ công suất bị mất trên dây so với công suất mà người tiêu dùng nhận được. Sau đó

$$\alpha_1 = \frac{I_0^2 r}{I_0^2 R} = \frac{r}{R} = 0.05, \quad \alpha_2 = \frac{r}{R_1} = 0.01.$$

Do đó $R = \frac{r}{\alpha_1}$ và $R_1 = \frac{r}{\alpha_2}$.

Kể từ đây,

$$\frac{R_1}{R} = \frac{\alpha_1}{\alpha_2} = 5,$$

$$\frac{U_1}{U_0} = \frac{R_1 + r}{R + r} \sqrt{\frac{R}{R_1}} =$$

$$= \frac{r \left(1 + \frac{1}{\alpha_1}\right)}{r \left(1 + \frac{1}{\alpha_2}\right)} \sqrt{\frac{\alpha_2}{\alpha_1}} = \frac{1 + \alpha_2}{1 + \alpha_1} \sqrt{\frac{\alpha_1}{\alpha_2}} \approx \sqrt{5}.$$

I. Slobodetsky

F456. Một con tàu vũ trụ cần đạt tốc độ tối thiểu bao nhiêu trên Trái đất để mono có thể đến được Mặt trời? Thời gian chuyến bay của con tàu tới Mặt trời sẽ là bao nhiêu?

Hãy tưởng tượng rằng một con tàu vũ trụ được phóng từ Trái đất, tốc độ của nó nhỏ hơn một chút so với tốc độ chuyển động ngược của Trái đất. Quỹ đạo của con tàu sẽ là một hình elip, tại một trong những tiêu điểm của nó là Mặt trời. Tốc độ ban đầu của con tàu so với Mặt trời càng thấp thì quỹ đạo của nó càng dài. Ở những giá trị nhất định của tốc độ này, con tàu đang chuyển động sẽ chạm vào bề mặt Mặt trời. Nói cách khác, độ cao của điểm cận nhật quỹ đạo của con tàu sẽ bằng Mặt trời. Bán kính của Mặt trời nhỏ hơn bán kính quỹ đạo Trái đất khoảng 200 lần, do đó dải nhỏ của quỹ đạo hình elip của tàu chạm vào Mặt trời nhỏ hơn nhiều so với dải lớn hơn. Để ước tính, chúng ta có thể giả định rằng mức tăng nhỏ đơn giản bằng 0. Với giả định này, quỹ đạo của con tàu biến thành một đường thẳng nối điểm phóng của con tàu với Mặt trời, tức là con tàu va vào Mặt trời, rơi tự do vào nó. Do đó, tại thời điểm ban đầu, tốc độ của con tàu so với Mặt trời phải bằng 0. Để điều kiện này được đáp ứng, con tàu phải giao tiếp trên Trái đất với tốc độ bằng giá trị abscyl với tốc độ nghịch đảo của Trái đất, nhưng hướng theo hướng ngược lại.

Bán kính quỹ đạo của Trái đất xấp xỉ $1,5 \cdot 10^{11}$ m, chu kỳ quay của Trái đất quanh Mặt trời là $\sim 3,15 \cdot 10^{7}$ s. Vì vậy tốc độ quỹ đạo của Trái Đất là

$$v = \frac{2\pi \cdot 1,5 \cdot 10^{11}}{3,15 \cdot 10^7} \approx 3 \cdot 10^4 \text{ м/с}.$$

Tốc độ này phải đạt được trên Trái đất (Hình 8).

Để xác định thời gian con tàu bay tới Mặt trời, hãy sử dụng định luật thứ ba của Kepler. Theo cái này

⟦folio 33⟧

Bình phương các chu kỳ quay của con tàu và Trái đất quanh Mặt trời có quan hệ với lập phương bán trục lớn của quỹ đạo của con tàu và Trái đất:

$$\frac{T^2_K}{T^2_3} = \frac{(R/2)^3}{R^3}$$

(R là bán kính quỹ đạo Trái Đất). Thời gian bay của một con tàu tới Mặt trời bằng một nửa thời gian nó quay quanh một quỹ đạo hình elip, tức là

$$t = \frac{T_K}{2} = \frac{1}{4\sqrt{2}} T_3 \approx 5.6 \cdot 10^6 \text{ с.}$$

A. Dozorov

F457. Hai tụ điện phẳng có bản giống nhau và có điện tích giống nhau. Khoảng cách giữa các bản tụ của tụ thứ nhất lớn gấp đôi so với tụ thứ hai. Năng lượng điện trường của hệ sẽ thay đổi như thế nào nếu tụ điện thứ hai được đặt giữa các bản của Mak thứ nhất, như trong Hình 9, a và 6?

Năng lượng điện trường của tụ điện tích điện bằng

$$W = \frac{\varepsilon_0 \varepsilon E^2}{2} V,$$

trong đó $\varepsilon_0$ là hằng số điện, $\varepsilon$ là hằng số điện môi của môi trường, $\vec{E}$ là hướng của điện trường và $V$ là thể tích bị điện trường chiếm giữ.

Hãy tìm năng lượng ban đầu $W_0$ của điện trường của hệ hai tụ điện không khí ($\varepsilon=1$). Vì điện tích trên các tụ điện bằng nhau nên hướng của điện trường trong tụ điện thứ nhất giống như trong tụ điện thứ hai. Chúng ta hãy biểu thị giá trị tuyệt đối của nó bằng $E_0$. Gọi thể tích của tụ thứ nhất lần lượt là $V_0$ và thể tích của tụ thứ hai lần lượt là $V_0/2$. Sau đó

$$W_0 = \frac{\varepsilon_0 E^2}{2} V_0 + \frac{\varepsilon_0 E^2}{2} \frac{V_0}{2} = \frac{3}{4} \varepsilon_0 E^2 V_0.$$

Sau khi các tụ điện được đặt lồng vào nhau, các giá trị tuyệt đối về hướng của điện trường giữa các bản sẽ trở nên khác nhau. Đối với trường hợp a) (Hình 9, a)

$$E_1 = E_3 = E_0, \quad E_2 = 2E_0.$$

Sự tương ứng sẽ thay đổi và năng lượng của hệ thống sẽ thay đổi:

$$W = \frac{\varepsilon_0 E^2}{2} (V_1 + V_3) + \frac{\varepsilon_0 E^2}{2} V_2 = \frac{5}{4} \varepsilon_0 E^2 V_0.$$

Từ đây

$$\frac{W}{W_0} = \frac{5}{3}.$$

Trong trường hợp b) (Hình 9, b)

$$E_1 = E_3 = E_0, \quad E_2 = 0.$$

Sau đó

$$W = \frac{\varepsilon_0 E^2}{2} (V_1 + V_3) = \frac{1}{4} \varepsilon_0 E^2 V_0,$$

Và

$$\frac{W}{W_0} = \frac{1}{3}.$$

S. Kozel
