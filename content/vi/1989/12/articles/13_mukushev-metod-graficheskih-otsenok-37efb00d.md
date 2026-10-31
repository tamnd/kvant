---
id: 1989-12-mukushev-metod-graficheskih-otsenok-37efb00d
issue: kvant_1989_12
year: 1989
number: "12"
title: Phương pháp đánh giá đồ họa
authors:
  - Мукушев Б. А.
rubric: praktikum-abiturienta
rubric_sub: Практикум абитуриента
page_first: 54
page_last: 58
page_labels: 52-56
tag: SET2
lang: vi
source: kvant_digital
extraction: vision
content_sha256: d497fe8ca2720fc6da310426753963cb197e8e8d44c5be3bde908bffb7e3e3a8
prompt_sha256: draft-1
translated_from: content/ru/1989/12/articles/13_mukushev-metod-graficheskih-otsenok-37efb00d.md
source_content_sha256: b037b061a486b0569bc111e8f48a4b36eb5f6c90b5eccfc3a4f74eda99155478
translation_model: draft
translation_run: vi-draft-2026-10-31
translation_quality: draft
---

⟦folio 52⟧

Phương pháp đánh giá đồ họa

V. A. MUKUSHEV

Có nhiều phương pháp khác nhau để nghiên cứu các hiện tượng và quá trình vật lý. Một trong số đó là phương pháp đánh giá đồ họa. Nó cũng áp dụng cho lời giải thể chất cụ thể bài toán.

Phương pháp đồ họa một mặt làm cho các giai đoạn khác nhau lời giải bài toán trở nên rõ ràng, mặt khác giúp đánh giá nhanh kết quả lời giải, điều này đặc biệt quan trọng trong trường hợp phân tích lời giải rườm rà hoặc khi không thể thực hiện được.

Vì phương pháp đồ họa là phương pháp tính gần đúng nên kết quả không chính xác. Tuy nhiên, độ chính xác luôn có thể được tăng lên bằng cách sử dụng bảng, máy tính vi mô và máy tính. Bằng cách xây dựng các biểu đồ thích hợp, bạn có thể nhanh chóng nhận được kết quả gần đúng và kiểm tra xem nó thực tế đến mức nào và liệu nó có ý nghĩa vật lý hay không.

bài toán được đề xuất trong bài viết khó có thể được đưa ra trong các kỳ thi tuyển sinh của các trường đại học, mặc dù bạn chắc chắn có thể gặp phải bài toán gần với chúng, có một lời giải phân tích rườm rà.

Bài toán 1. Đồ chơi “Vanka-Vstanka” (hình 1) được đặt trên một bậc thang cố định có bán kính R. Mặt dưới của đồ chơi có hình cầu bán kính r, trọng tâm của đồ chơi - điểm C - nằm ở giữa bán kính của hình cầu. Đồ chơi có thể bị lệch một góc tối đa bao nhiêu β_max để nó trở về vị trí ban đầu nếu R/r=4?

⟦folio 53⟧

Ví dụ: khi đồ chơi lệch sang bên phải, trọng tâm sẽ dịch chuyển (xem hình 1). Nếu đồng thời nó ở bên trái phương thẳng đứng $AB$, đi qua điểm tựa $A$ thì mômen trọng trường sẽ đưa đồ chơi về vị trí cân bằng. Nếu trọng tâm ở bên phải $AB$, đồ chơi sẽ rơi.

Chúng ta hãy biểu thị $\alpha$ là góc quay của đồ chơi, $\beta$ là góc quay của bán kính $O'A$. Các $LA$ và $KA$ khác bằng nhau (không trượt), tức là $\alpha r = \beta R$, do đó $\alpha = \beta \frac{R}{r}$.

Từ tam giác $OAB$ ta có

$$\frac{OB}{\sin \beta} = \frac{AO}{\sin (\pi - \alpha - \beta)} = \frac{r}{\sin (\alpha + \beta)} = \frac{r}{\sin (\beta (1 + R/r))},$$

hoặc

$$OB = \frac{r \sin \beta}{\sin (\beta (R/r + 1))}.$$

Đồ chơi sẽ trở về vị trí ban đầu nếu $OC = \frac{1}{2} r > OB$, tức là.

$$\frac{1}{2} r > \frac{r \sin \beta}{\sin (\beta (R/r + 1))},$$

hoặc, có tính đến mối quan hệ $R/r = 4$, $\sin 5\beta > 2 \sin \beta$.

Để tìm góc giới hạn $\beta_{\max}$, ta phải giải phương trình lượng giác

$$\sin 5\beta_{\max} = 2 \sin \beta_{\max}.$$

Để làm điều này, chúng ta sẽ xây dựng đồ thị của hàm $y = \sin 5\beta$ và $y = 2 \sin \beta$ và từ giao điểm của các đồ thị này (hình 2), chúng ta sẽ tìm thấy

$$\beta_{\max} \approx 0,42 \text{ рад} \approx 23,9^\circ.$$

Điều này có nghĩa là tại $-23,9^\circ < \beta < 23,9^\circ$ đồ chơi trở về vị trí ban đầu.

Bài toán 2. Trên một khối lập phương có khối lượng $m$, nằm trên bề mặt chính, được nối với tường bằng một lò xo, một khối lập phương thứ hai có khối lượng $M$ (hình 3) chạm vào bên phải. Một tác động hoàn toàn đàn hồi xảy ra, sau đó khối thứ nhất bắt đầu dao động. Phần nào của thời kỳ bình sẽ trôi qua cho đến thời điểm này

$$Mv_0 = mv_1 + Mv_2, \quad \frac{Mv_0^2}{2} = \frac{mv_1^2}{2} + \frac{Mv_2^2}{2},$$

Ở đâu

$$v_1 = v_0 \frac{2}{1 + \gamma}, \quad v_2 = v_0 \frac{1 - \gamma}{1 + \gamma}.$$

⟦folio 54⟧

Sau va chạm, khối thứ hai sẽ chuyển động đều và tọa độ của nó sẽ thay đổi theo thời gian theo quy luật

$$x_2 = v_2 t = v_0 \frac{1-\gamma}{1+\gamma} t.$$

Khối lập phương đầu tiên bắt đầu dao động theo định luật

$$x_1 = x_m \sin \omega t.$$

Tần số hài

$$\omega = \sqrt{\frac{k}{m}},$$

trong đó $k$ là độ cứng của lò xo. Ta tìm biên độ dao động $x_m$ từ định luật bảo toàn năng lượng:

$$\frac{m v_1^2}{2} = \frac{k x_m^2}{2} \Rightarrow x_m = \frac{v_1}{\omega} = \frac{2 v_0}{(1+\gamma) \omega}.$$

Như vậy,

$$x_1 = \frac{2 v_0}{(1+\gamma) \omega} \sin \omega t.$$

Lần va chạm thứ hai của các hình khối sẽ xảy ra với điều kiện $x_1 = x_2$, tức là.

$$\frac{2 v_0}{(1+\gamma) \omega} \sin \omega t = v_0 \frac{1-\gamma}{1+\gamma} t.$$

Từ đây

$$2 \sin \omega t = (1-\gamma) \omega t,$$

hoặc

$$2 \sin \left(2 \pi \frac{t}{T}\right) = (1-\gamma) 2 \pi \frac{t}{T},$$

trong đó $T = 2 \pi/\omega$ là chu kỳ dao động, $t/T$ là tần số mong muốn của chu kỳ.

Hãy biểu thị nó bằng $\pi t/T = z$. Khi đó phương trình trước có dạng

$$\sin 2z = (1-\gamma) z.$$

Với $\gamma = 1/2$ chúng tôi nhận được

$$\sin 2z = \frac{z}{2}.$$

Chúng ta hãy vẽ đồ thị của các hàm $y = \sin 2z$ và $y = z/2$ (hình 4) và từ giao điểm của chúng, chúng ta tìm thấy

$$z \approx 1,24$$ vui mừng, $\pi \frac{t}{T} \approx 1,24$, $\frac{t}{T} \approx 0,39$.

Nếu $m \ll M$, tức là $\gamma \to 0$, thì chúng ta thu được phương trình

$$\sin 2z = z.$$

Giải pháp của anh ấy sẽ là (xem hình 4)

$$z \approx 0,95$$ vui mừng, hoặc $\frac{t}{T} \approx 0,30$.

Sự va chạm thứ hai của các khối sẽ không xảy ra nếu tọa độ của chúng không còn trùng nhau, nghĩa là nói theo ngôn ngữ đồ thị, nếu đường thẳng biểu thị tọa độ của khối thứ hai theo thời gian không cắt hình sin lần thứ hai. Điều này tương ứng với tất cả các đường thẳng xuất phát từ điểm $O$ và vị trí của vùng được che chắn giữa các đường $I$ và $II$. Dòng $I$ tương ứng với trường hợp $m/M \to \infty$ (khối lượng của khối sự cố rất nhỏ). Vẫn còn phải tìm $\gamma$ cho đường thẳng $II$—tiếp tuyến với hình sin. Như có thể thấy từ hình 4, dòng này tương ứng với giá trị $z \approx 2,24$ rad. Từ đây

$$\gamma = 1 - \frac{\sin 2z}{z} \approx 1,44.$$

Vì vậy, để không xảy ra va chạm thứ hai thì điều kiện phải được thỏa mãn

$$1,44 < \gamma < \infty.$$

Bài toán 3. Bơm piston thu được một lượng không khí nhất định sau mỗi lần xoay. Khi bơm không khí ra khỏi bình, máy bơm thực hiện bốn chuyển động lắc. Áp suất ban đầu bên trong bình bằng áp suất khí quyển $p_0$. Sau đó, máy bơm này bắt đầu đưa không khí từ khí quyển vào bình và cũng thực hiện bốn lần xoay. Đồng thời, áp suất trong bình tăng lên

⟦folio 55⟧

gấp 2 lần so với khí quyển. Tìm sự tương ứng giữa thể tích làm việc của máy bơm và thể tích của bình.

Khi bơm không khí ra khỏi bình sau lần bơm đầu tiên, áp suất trong bình sẽ bằng nhau

$$p_1 = p_0 \frac{V}{V + V_0},$$

trong đó $V$ là thể tích của bình, $V_0$ là thể tích làm việc của bơm piston; sau cú vung thứ hai -

$$p_2 = p_1 \frac{V}{V + V_0} = p_0 \left( \frac{V}{V + V_0} \right)^2$$

v.v. Sau bốn lần dao động, áp suất trong bình sẽ là

$$p' = p_0 \left( \frac{V}{V + V_0} \right)^4.$$

Khi không khí được bơm vào bình sau bốn lần lắc, áp suất được thiết lập trong bình

$$p = p' + \frac{4p_0V_0}{V} = p_0 \left( \left( \frac{V}{V + V_0} \right)^4 + 4 \frac{V_0}{V} \right) = p_0 \left( \left( \frac{1}{1 + V_0/V} \right)^4 + 4 \frac{V_0}{V} \right).$$

Mặt khác, theo điều kiện bài toán $p = 2p_0$.

Chúng ta thu được phương trình

$$2p_0 = p_0 \left( \frac{1}{1 + V_0/V} \right)^4 + 4 \frac{V_0}{V}),$$

hoặc

$$2 - 4x = \left( \frac{1}{1 + x} \right)^4,$$

ở đâu $x = V_0/V$. Hãy xây dựng đồ thị hàm số (hình 5)

$$y = 2 - 4x \text{ и } y = \frac{1}{(1 + x)^4}$$

và từ giao điểm của chúng, chúng ta tìm thấy

$$x \approx 0,44, \text{ т. е. } \frac{V_0}{V} \approx 0,44.$$

Bài 4. Để xác định điện dung của tụ điện chưa biết $C_x$, mạch điện ở hình 6 đã được lắp ráp. Điện dung của tụ điện $C_o$ đã biết. Tụ điện $C_o$ sử dụng phím $K_1$ sử dụng phím $K_2$ hóa ra là $U_4$. Vì dòng điện qua miliampe là lẻ nên dễ dàng thiết lập được điều đó

$$\frac{U_2}{R_2} = \frac{U_4}{R_1},$$

trong đó $U_2$ là điện áp rơi trên điện trở $R_2$. Ở phía bên kia,

$$U_2 = U_0 - U_4.$$

⟦folio 56⟧

Từ đây

$$\frac{U_4}{U_0} = \frac{R_1}{R_1 + R_2}.$$

Ban đầu tụ điện $C_x$ có điện tích $q_x = C_x U_0$. Ở lần đầu tiên $K_1$ đến vị trí 3, điện tích này được phân bổ giữa $C_x$ và $C_0$, và điện áp trên các tụ điện chung trở nên bằng nhau

$$U_1 = \frac{q_x}{C_x + C_0} = \frac{C_x U_0}{C_x + C_0}.$$

Sau khi nghiêng $K_2$ sang vị trí 5, tụ điện $C_0$ phóng điện hoàn toàn và điện tích vẫn còn trên tụ $C_x$

$$q_1 = C_x U_1 = \frac{C_x^2 U_0}{C_x + C_0}.$$

Sau lần nghiêng thứ hai $K_2$ đến vị trí 4, điện áp trên tụ trở thành

$$U_2 = \frac{q_1}{C_x + C_0} = U_0 \left( \frac{C_x}{C_x + C_0} \right)^2,$$

và sau bốn khuynh hướng -

$$U_4 = U_0 \left( \frac{C_x}{C_x + C_0} \right)^4.$$

Hãy ký hiệu $\beta = C_x / (C_x + C_0)$ thì

$$\frac{U_4}{U_0} = \beta^4.$$

Sau khi hoán đổi các điện trở và lặp lại toàn bộ quá trình, bạn có thể viết một phương trình tương tự như phương trình (1) và (2):

$$\frac{U_3}{U_0} = \frac{R_2}{R_1 + R_2},$$

$$\frac{U_3}{U_0} = \beta^3,$$

trong đó $U_3$ là điện áp trên tụ $C_x$ sau ba lần đảo ngược $K_2$. Từ phương trình (1) và (3) chúng ta thu được

$$\frac{U_4}{U_0} + \frac{U_3}{U_0} = \frac{R_1}{R_1 + R_2} + \frac{R_2}{R_1 + R_2} = 1,$$

Có nghĩa,

$$\beta^4 + \beta^3 = 1.$$

Hãy vẽ đồ thị hàm số (hình 7)

$$y = \beta^4 \text{ и } y = 1 - \beta^3$$

và từ giao điểm của chúng, chúng ta tìm thấy

$$\beta \approx 0,82.$$

Rồi cuối cùng

$$C_x = \frac{\beta}{1 - \beta} C_0 \approx \frac{0,82}{1 - 0,82} \times 100 \text{ мкФ} \approx 450 \text{ мкФ}.$$

Bài tập

1. Một sợi dây quấn quanh một đĩa đứng yên có bán kính $r$ tạo thành hình bán nguyệt (hình 8). Một đầu của sợi chỉ được cố định tại điểm $A$, một vật nặng được gắn vào đầu thứ hai của sợi chỉ, được giữ ở điểm $B$ (các điểm $A$ và $B$ nằm trên cùng một phương thẳng đứng). Tại một thời điểm nào đó vật nặng được thả ra khi tiếp xúc với đĩa khi vật nặng đạt đến vị trí cao nhất? Thứ ba là lơ là.

2. Một doxa nằm trên một nửa hình tròn cố định có bán kính $R$ (hình 9). Độ dày Doxy $h$, chiều dài $2l$, $R = h$. Góc tối đa ($\varphi_{\pi p}$) có thể ngắt kết nối doxa khỏi vị trí nằm ngang để nó trở về trạng thái ban đầu? Độ ma sát cao. Giả sử rằng nửa thanh trượt nằm trên một mặt phẳng nằm ngang vô hạn và $2l/R = 4$, hãy tìm hiểu xem doxa có trở lại trạng thái ban đầu ở độ lệch tối đa so với vị trí nằm ngang hay không.
