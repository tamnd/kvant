---
id: 1991-11-resheniya-zadach-m1286-m1290-f1298-f1302-6d56a4cb
issue: kvant_1991_11
year: 1991
number: "11"
title: Lời giải bài toán M1286—M1290; F1298—F1302
rubric: zadachnik-kvanta
rubric_sub: Задачник «Кванта»
page_first: 22
page_last: 28
page_labels: 20-26
lang: vi
source: kvant_digital
extraction: vision
content_sha256: a3c46403fddb7958dff18386861c328eb9f16b5f118fdc274d89038b36705d1c
prompt_sha256: draft-1
translated_from: content/ru/1991/11/articles/06_resheniya-zadach-m1286-m1290-f1298-f1302-6d56a4cb.md
source_content_sha256: 88c2a046f870b14712689bd5f6f2b8538f9d40912201df40678c34652032c93c
translation_model: draft
translation_run: vi-draft-gaps-2026-11-06
translation_quality: draft
---

⟦folio 20⟧

---
running_head:
folio:
---

Lời giải bài toán

M1286. Đại hội sẽ có sự tham dự của 100 đại biểu, mỗi người biết nhiều ngoại ngữ. Được biết, ba người bất kỳ có thể nói chuyện với nhau mà không cần sự giúp đỡ của người khác. Chứng minh rằng có thể bố trí các đại biểu trong 50 phòng đôi để những người ở cùng phòng có thể nói chuyện được với nhau.

1
2
4
3

M1287. Trong hình bình hành ABCD, đường chéo AC lớn hơn đường chéo BD. Điểm M trên đường chéo AC còn có nghĩa là một đường tròn có thể ngoại tiếp tứ giác BCMD. Chứng minh rằng BD là tiếp tuyến chung của đường tròn ngoại tiếp các tam giác ABM và ADM.

M1288. Chứng minh rằng số $235^2 + 972^2$ là hợp số.

Ta hãy chứng minh bằng quy nạp một phát biểu tổng quát hơn về 2n đại biểu và n phòng đôi, n ≥ 2.

Việc mô tả tình huống dưới dạng đồ thị là điều đương nhiên - một hệ thống các điểm (đại diện cho các đại biểu), một số cặp được kết nối bằng một cạnh (cụ thể là các cặp đại biểu có thể nói chuyện với nhau).

Đối với 4 đại biểu (n=2), tuyên bố được xác minh bởi một lực lượng vũ phu nào đó. Nếu 1, 2, 3, 4 là đại biểu (các đỉnh của đồ thị), mỗi người trong số họ có thể nói chuyện với ít nhất một trong số những người còn lại, nhưng đồng thời họ không thể ở trong hai phòng đôi với các điều kiện đáp ứng (tức là đồ thị thiếu một trong các cạnh 12 hoặc 34, cũng như một trong các cạnh 13 hoặc 24 và cạnh 14 hoặc 23), thì khả năng duy nhất còn lại là trường hợp tương ứng với đồ thị gồm ba cạnh nổi lên từ một đỉnh (xem hình), mâu thuẫn với các điều kiện.

Sự chuyển đổi từ n sang n+1 rất rõ ràng. Giả sử rằng tuyên bố được chứng minh cho 2n đại biểu và chứng minh nó cho 2n+2. Bạn có thể chọn bất kỳ cặp nào trong số họ biết ngôn ngữ chung và xếp họ vào cùng một phòng. Và 2n đại biểu còn lại, theo giả định quy nạp, có thể ở trong n phòng với điều kiện bài toán.

D. Fomin

Để chứng minh nhận xét này cho đường tròn ngoại tiếp tam giác ABM, chỉ cần kiểm tra sự bằng nhau của các góc MBD và BAM là đủ. Nhưng vì tứ giác BCMD treo trong một đường tròn nên $\angle BAM = \angle MOD = \angle MBD$. Đối với vòng tròn còn lại, chứng minh tương tự.

D. Fomin

Số tiền này bằng $1000009 = 3^2 + 1000^2$. Hãy để chúng tôi chứng minh thực tế chung này. Nếu một số m có dạng 4k+1 (k là số tự nhiên) có thể biểu diễn dưới dạng tổng của hai bình phương theo ít nhất hai cách khác nhau thì m là hợp số.

Cho phép

$$m = x^2 + y^2 = u^2 + v^2,$$

trong đó chúng ta có thể coi các số x>u là số lẻ và y<v là số chẵn. Khi đó ước số chung nhất của số

⟦folio 21⟧

---
running_head:
folio:
---

$x - u$ và $v - y$ là số chẵn; hãy biểu thị nó $2d$. Cho phép
$x = u - 2da$, $v = y - 2db$, (2)

trong đó $a$ và $b$ là nguyên tố cùng nhau. Thay thế biểu thức (2) thành
(1), chúng tôi thu được sau khi giảm
$au + da^2 = by + db^2 = abc$. (3)

Con số này chia hết cho $a$ và $b$, và do đó cũng chia hết cho tích của chúng.
tiến hành; Chúng tôi ký hiệu thương số là $c$. Như vậy, như sau từ (3), $u = bc - ad$, $y = ac - bd$, từ đó
$x = u + 2ad = bc + ad$ (ở đây $a$, $b$, $c$, $d$ là một số số tự nhiên) và
$m = x^2 + y^2 = (bc + ad)^2 + (ac - bd)^2 = (a^2 + b^2)(c^2 + d^2)$.

Thực hiện các phép tính này cho những số này, không khó để tìm ra khai triển tương ứng cho số $10^6 + 9$.

Một phát biểu mạnh mẽ hơn có thể được chứng minh: số $m = 4k + 1$ là số nguyên tố khi và chỉ khi nó có thể được biểu diễn theo một cách duy nhất dưới dạng tổng của hai bình phương. Euler lưu ý rằng tiêu chí này thuận tiện cho việc kiểm tra tính nguyên tố của số lớn (việc tìm kiếm các số cần thiết sẽ giảm đi nếu bạn sử dụng thông tin về số dư mà hình vuông có thể tạo ra khi chia cho số nhỏ*).

N. Vasiliev, D. Fomin

M1289. Tổng của các số nguyên $a_1, a_2, ..., a_n$ (viết dọc theo một vòng tròn) bằng 1. Với mỗi $k$ từ 1 đến $n$, chúng ta sử dụng $N_k$ để biểu thị số tổng dương trong số các tổng $n$ (bắt đầu bằng $a_k$):

$a_k, a_k + a_{k+1}, ..., a_k + a_{k+1} + ... + a_n + a_1 + ... + a_{k-1}$.

Chứng minh rằng tất cả $N_k$ đều khác nhau.

Chúng ta sẽ giả sử rằng các số $a_1, a_2, ..., a_n$ được viết dưới dạng điểm $A_1, A_2, ..., A_n$ nằm theo chiều kim đồng hồ trên đường tròn. Điều kiện là điểm $A_k$ cực đại hóa điểm $A_j$ và viết nó là $A_k > A_j$, nếu tổng của tất cả các số từ $a_k$ đến $a_{j-1}$ theo chiều kim đồng hồ là dương. (Tất nhiên dưới $a_0$ là khái niệm $a_n$.) Khi đó từ điều kiện tổng các số $a_1, a_2, ..., a_n$ bằng 1, suy ra hai tính chất sau:

1) Nếu $A_k > A_j$ và $A_j > A_i$ thì $A_k > A_i$. (Ở đây chỉ có trường hợp được mô tả trong hình cần giải thích, khi $A_k A_j$ và $A_j A_i$ kia chồng lên nhau. Trong trường hợp này, tổng các số trên cung này và cung kia không nhỏ hơn $1 + 1 = 2$, trên toàn đường tròn tổng bằng -1, do đó tổng các số trên cung $A_k A_i$ không nhỏ hơn 1.)
2) Đối với hai điểm bất kỳ $A_k$ và $A_j$, $A_k > A_j$ hoặc $A_j > A_k$.

Cần lưu ý rằng $N_k$ là số điểm mà điểm $A_k$ tối đa hóa. Theo sau đó tất cả những con số này là khác nhau. Trên thực tế, nếu $A_k > A_j$ và $A_j$ tối đa hóa $N_j$ của một số điểm, thì $A_k$, theo tính chất 2), tối đa hóa tất cả các điểm này và ít nhất một điểm nữa - $A_j$, do đó, $N_k > N_j$.

D. Fomin

* Ví dụ, thông tin chi tiết hơn về điều này được viết trong cuốn sách tuyệt vời “Bách khoa toàn thư về đại số cơ bản và giải tích” của G. Weber, Nhà xuất bản Toán học, Odessa, 1906.

⟦folio 22⟧

---
running_head:
folio:
---

M1290. Một tờ giấy hình vuông đã tẩy xóa có khổ 8x8 được xếp bằng 14 đường thẳng thành 64 ô 1x1 và được gấp ngẫu nhiên theo các đường này thành tập sách nhỏ có khổ 1x1 (trong tổng số 64 tờ). Các trang sách được đánh số theo thứ tự 1, 2,..., 64 rồi lại mở ra. Gọi p là chênh lệch lớn nhất về số lượng các ô lân cận (giáp bên). Giá trị nhỏ nhất có thể có của p ở lần gấp nào nó đạt được?

F1298. Một quả bóng nặng được ném lên trên với tốc độ $v_0$. Xét lực kéo tỷ lệ thuận với vận tốc của quả bóng, hãy tìm khoảng thời gian sau đó quả bóng sẽ rơi đến điểm được ném đi. Ở tốc độ $v_0$ lực cản là $F = \alpha v_0 \gg mg$ (ở đây $\alpha$ là hệ số tỷ lệ, $m$ là khối lượng của quả bóng).

Đáp số: Giá trị nhỏ nhất có thể có của $p$ là 15 và đạt được bằng cách gấp đàn accordion trước theo một hướng rồi theo hướng kia.

Hãy để chúng tôi chứng minh rằng với bất kỳ lần gấp nào, anh ta sẽ tìm thấy hai ô liền kề có số lượng chênh lệch ít nhất là 15.

Mỗi đoạn trong số 14 đoạn có chiều dài 8, hình vuông được chia thành các ô, khi gấp lại sẽ biến thành một đoạn (có cùng chiều dài hoặc ngắn hơn); Một số đoạn có thể trùng khớp hoàn toàn và sau đó sẽ được gấp lại với nhau.

Chúng ta hãy xem xét một đoạn neoctor có chiều dài 8, khi gấp lại sẽ biến thành một đoạn có chiều dài 1, dọc theo đó việc gấp cuối cùng được thực hiện - khi tập sách 2x1 được gấp thành một ô 1x1; Hơn nữa, chúng tôi chọn đoạn “màu đỏ” này để ở bên này và bên kia có các điểm trên hình vuông nằm trước nếp gấp cuối cùng trong hai ô khác nhau của cuốn sách 2x1. Hãy xem xét 8 cặp ô vuông được phân tách bằng một đoạn màu đỏ (tại hình chúng được nối với nhau bằng đầu). Ở lần gấp cuối cùng, mỗi cặp này đều vi phạm: giữa các trang tương ứng sẽ có ít nhất 14 trang khác, do đó sự khác biệt về số lượng của chúng ít nhất là 15.

N. Vasiliev

Chúng ta biểu thị độ cao nâng tối đa của quả bóng là $h$. Theo điều kiện bài toán, ma sát thẳng đứng lớn nên ta giả sử rằng sự rơi sẽ xảy ra với tốc độ ổn định

$$v_{yct} = mg/\alpha$$

và thời gian rơi

$$\tau_{пад} = \frac{h}{v_{yct}} = \frac{h\alpha}{mg}.$$

Khi chuyển động lên trên, quả bóng chịu tác dụng của lực hấp dẫn không đổi và lực cản thay đổi. Do đó, gia tốc của quả bóng bằng $a = g + \alpha v/m$ và hướng xuống dưới. Giả sử tại một thời điểm nào đó tốc độ của quả bóng bằng $v_i$. Khi đó những gia tăng nhỏ của tốc độ và độ dịch chuyển sẽ tương ứng

$$\Delta v_i = a_i \Delta t_i = g \Delta t_i + \frac{\alpha v_i}{m} \Delta t_i,$$

$$\Delta h_i = v_i \Delta t_i.$$

⟦folio 23⟧

---
running_head:
folio:
---

Tổng hợp từng sự tương ứng, chúng ta nhận được

$$\sum \Delta v_i = v_0 = g \sum \Delta t_i + \frac{\alpha}{m} \sum v_i \Delta t_i,$$

$$\sum \Delta h_i = h = \sum v_i \Delta t_i,$$

hoặc

$$v_0 = g \sum \Delta t_i + \frac{\alpha}{m} h,$$

thời gian tăng ở đâu?

$$\tau_{\text{подд}} = \sum \Delta t_i = \frac{v_0}{g} - \frac{\alpha h}{mg}.$$

Rồi cuối cùng chúng ta sẽ tìm thấy

$$\tau_{\text{обшт}} = \tau_{\text{подд}} + \tau_{\text{падд}} = \frac{v_0}{g}.$$

Kết quả là một đáp số thú vị: nếu độ nhớt đủ cao thì thời gian tăng-giảm không còn phụ thuộc vào độ nhớt và chính xác bằng một nửa thời gian tăng-giảm khi không có lực cản. Trên thực tế, không có gì đáng ngạc nhiên ở đây - khi độ nhớt tăng lên thì chiều cao nâng sẽ giảm đi.

A. Andrianov

F1299. Một quả bóng đen có bán kính $r=1$ m được treo trên một sợi dây mỏng dài $l=1$ m. Toàn bộ hệ thống được đặt trong một ống thủy tinh chân không có argon ở áp suất $p_0=0,1$ Pa. Quả bóng được chiếu sáng bằng một chùm ánh sáng nằm ngang, mật độ dòng năng lượng trong đó bằng $w_0 = 100$ J/(m$^2$·s). Tính độ lệch của quả cầu so với vị trí cân bằng dưới tác dụng của ánh sáng. Bỏ qua độ dẫn điện của quả cầu. Hãy tính đến việc một vật đen tuyệt đối, được nung nóng đến nhiệt độ tuyệt đối $T$, phát ra các đơn vị bề mặt trên một đơn vị thời gian năng lượng bằng $\sigma T^4$, trong đó $\sigma=5,67 \cdot 10^{-8}$ W/(m$^2$·K$^4$). Nhiệt độ khí trong ống không đổi và bằng $T_0=293$ K. Khối lượng mol của argon là $M=0,04$ kg/mol, mật độ của quả cầu là $\rho=1$ g/cm$^3$.

Ánh sáng chiếu vào quả bóng từ một phía sẽ làm nó nóng lên một lượng nhất định $\Delta T$ ($\Delta T \ll T_0$). Quả bóng không dẫn nhiệt nên năng lượng tới trước tiên sẽ chuyển thành bức xạ và thứ hai là trao đổi nhiệt với khí xung quanh.

Công suất tiêu tán của bức xạ trên một đơn vị diện tích bề mặt là

$$W_1 = \sigma (T_0 + \Delta T)^4 - \sigma T_0^4 \approx 4 \sigma T_0^3 \Delta T.$$

Nếu $N$ phân tử khí va chạm với một đơn vị bề mặt của quả bóng trong một giây và $\Delta W$ năng lượng tỏa ra ở mỗi lần va chạm, thì tổng công suất sẽ được truyền vào môi trường

$$W_2 = N \Delta W.$$

Cho 1/6 tổng số phân tử chuyển động trên bề mặt quả bóng có cùng vận tốc $v = \sqrt{3RT_0/M}$, và nồng độ phân tử trong bình là $n = p_0/(kT_0)$. Sau đó (hãy tạo giới hạn trên)

$$\Delta W = \frac{3}{2} k (T_0 + \Delta T) - \frac{3}{2} k T_0 = \frac{3}{2} k \Delta T,$$

$$W_2 = \frac{1}{6} nv \Delta W = \frac{1}{4} \frac{p_0 v \Delta T}{T_0}$$

Và

$$\frac{W_2}{W_1} = \frac{1/4 p_0 \Delta T \sqrt{3RT_0/M/T_0}}{4 \sigma T_0^3 \Delta T} \approx 0,01.$$

⟦folio 24⟧

---
running_head:
folio:
---

Vì vậy, chúng ta thấy rằng chúng ta có thể bỏ qua sự trao đổi nhiệt với chất khí và giả sử rằng tất cả năng lượng tới chỉ được sử dụng để tái bức xạ. Đó là lý do tại sao

$$\Delta T = \frac{W_{\text{пост}}}{4\sigma T_0^3} = \frac{w_0 \pi r^2}{4\sigma T_0^3} = 17,5 \text{ К}.$$

Áp suất khí trên phần được chiếu sáng của quả bóng lớn hơn trên phần không được chiếu sáng, vì các nguyên tử trong quá trình va chạm thu được tốc độ trung bình lớn hơn và do đó mang đi xung lực lớn hơn:

$$p = nkT_{\text{эфф}} = nk(T_0 + (\Delta T))/2,$$

$$\Delta p = p - p_0 = nk \frac{\Delta T}{2} = \frac{p_0 \Delta T}{2T_0}.$$

Lực ép tác dụng lên quả bóng bằng

$$F = \Delta p \pi r^2,$$

lực hấp dẫn -

$$mg = \frac{4}{3}\rho r^3,$$

độ lệch của quả bóng khỏi vị trí cân bằng của nó -

$$x = l \frac{F}{\sqrt{m^2 g^2 + F^2}} \approx 0,2 \text{ мм.}$$

A. Semenov

F1300. Người ta biết rằng khi đưa một quả cầu dẫn không tích điện vào điện trường một dây, trường định hướng $E_0$ của trường định hướng lớn hơn điểm A (hình 1) hóa ra bằng $3E_0$, và lớn hơn điểm B bằng 0. Xác định hướng của trường điểm lớn B. Tìm tổng điện tích cảm ứng trên bán cầu BAB. Bán kính hình cầu R.

Có một số cách để lời giải điều này bài toán. Chúng ta sẽ xem xét một trong số chúng ở đây.

Đầu tiên, hãy tìm sự phân bố điện tích trên quả cầu. Chúng ta hãy biểu thị mật độ điện tích bề mặt gần điểm A bằng $\sigma_0$ và tìm sự phụ thuộc góc của $\sigma(\alpha)$ ở dạng $\sigma(\alpha) = \sigma_0 f(\alpha)$ (hình 2). Do tính đối xứng nên hàm $f(\alpha)$ là chẵn, tức là $f(\alpha) = f(-\alpha)$. Hãy sử dụng nguyên tắc chồng chất - hãy tưởng tượng trường $\vec{E}_0$ (hình 3) là tổng của hai trường một dòng $\vec{E}_1$ và $\vec{E}_2 (E_1 = E_2)$. Chúng ta hãy biểu thị mật độ điện tích gần điểm A theo điện tích gây ra bởi các trường $\vec{E}_1$ và $\vec{E}_2$:

$$\sigma_A = \sigma_0 = \sigma(\vec{E}_1) + \sigma(\vec{E}_2) = \sigma_0 \frac{E_1}{E_0} f(\alpha) + \sigma_0 \frac{E_2}{E_0} f(\alpha).$$

Ở đây, chúng tôi đã lợi dụng thực tế là hằng số $\sigma_0$ trong phân phối $\sigma(\alpha)$ tỷ lệ thuận với trường bên ngoài:

$$\frac{\sigma_0(E_0)}{E_0} = \frac{\sigma_0(E_1)}{E_1} = \frac{\sigma_0(E_2)}{E_2}.$$

⟦folio 25⟧

---
running_head:
folio:
---

$$E_1 = E_2 = E_0 / (2 \cos \alpha),$$
Có nghĩa,
$$f(\alpha) = \cos \alpha.$$

Bây giờ hãy tìm giá trị của $\sigma_0$. Để làm điều này, hãy xem xét một vùng chịu tải nhỏ trên quả cầu, bao gồm cả điểm $A$. Nếu bạn đến rất gần nó, nó sẽ biến thành một vật thể quen thuộc - một mặt phẳng chịu tải vô hạn, tạo ra một trường dây đơn hướng $\sigma_0 / (2\varepsilon_0)$, hướng theo cả hai hướng so với mặt phẳng. Bên trong hình cầu trường bằng 0, bên ngoài vùng lân cận của điểm $A$ nó bằng $3E_0$. Đi qua phần chúng tôi đã chọn sẽ có bước nhảy trường $3E_0$, có nghĩa là
$$\frac{\sigma_0}{2\varepsilon_0} - \left( -\frac{\sigma_0}{2\varepsilon_0} \right) = 3E_0 \Rightarrow \sigma_0 = 3\varepsilon_0 E_0.$$

Lưu ý rằng mật độ tải tại điểm $B$ bằng - $\sigma_0$ (điều này có thể thấy được từ tính đối xứng: tuy nhiên, điều này cũng tuân theo công thức chúng ta thu được cho hàm $f(\alpha)$). Do đó, trường gần điểm này giống như điểm gần $A$, chỉ có điều nó hướng không phải từ quả cầu mà hướng về phía quả cầu. Vì vậy, hướng mong muốn của trường

$$\vec{E}_B = \vec{E}_A = 3\vec{E}_0.$$

Tất cả những gì còn lại là tìm toàn bộ tải $BAB$. Chia nó thành các vòng mỏng - một trong số chúng được nhìn thấy trên hình 4. Điện tích của vòng này bằng
$$\Delta Q = \sigma_0 \cos \alpha \cdot \Delta S = \sigma_0 \cos \alpha \cdot 2\pi R \sin \alpha \cdot R\Delta \alpha.$$

Thay thế giá trị $\sigma_0$ vào đây và tính tổng các tải trọng (intergal hóa ra khá đơn giản, nhưng nếu bạn không muốn đếm, hãy thử biểu thị diện tích hình chiếu của chốt này lên mặt phẳng đi qua tâm hình cầu và vuông góc với $\vec{E}_0$), ta được
$$Q = 3\pi \varepsilon_0 R^2 E_0.$$

V. Mozhaev

Rõ ràng từ điều kiện là trong trường hợp đầu tiên, trường chỉ được tạo ra bởi cuộn dây được kết nối với mạng. Từ thông trong cuộn dây này bằng
$$\Phi_1 = LI_1,$$

trong đó $L$ là độ tự cảm của cuộn dây, $I_1$ là dòng điện trong nó. Rõ ràng, từ thông trong cuộn dây thứ ba cũng tỷ lệ với dòng điện $I_1$, tức là.
$$\Phi_3 \sim I_1,$$ hoặc $$\Phi_3 = MI_1,$$

trong đó $M$ là hệ số, thường được gọi là tương tác của cuộn dây. Khi đó với tỉ số chiều của cuộn dây ta thu được
$$\frac{U_3}{U_1} = \frac{\Phi'_3}{\Phi'_1} = \frac{\Phi_3}{\Phi_1} = \frac{M}{L} = \frac{1}{2}.$$

Trong trường hợp thứ hai, có dòng điện trong hai cuộn dây - một cuộn dây nối vào mạng và một cuộn dây ngắn mạch. Đó là lý do tại sao

⟦folio 26⟧

---
running_head:
folio:
---

nick là lý tưởng, độ thấm từ của lõi không thay đổi ở các giá trị cảm ứng từ khác nhau.

hãy viết ra

$$\Phi_1^* = LI_1^* + MI_2^*,
\Phi_3^* = MI_1^* + MI_2^*,
\Phi_2^* = MI_1^* + LI_2^* = 0$$

(vì điện trở mạch thấp).
Từ đây chúng ta có được

$$I_2^* = -I_1^* \frac{M}{L}$$

Và

$$\frac{U_3^*}{U_1^*} = \frac{\Phi_3^*}{\Phi_1^*} = \frac{MI_1^* + MI_2^*}{LI_1^* + MI_2^*} = \frac{M - M^2/L}{L - M^2/L} = \frac{M}{L} \frac{1 - M/L}{1 - M^2/L^2} = \frac{M}{L} \frac{1}{1 + M/L} = \frac{1}{3}.$$

Do đó, vôn kế lúc này sẽ hiển thị điện áp nguồn.

A. Andrianov

F1302. Một vật có khối lượng M tựa vào tường, vuông góc với tường chịu một lực thay đổi theo định luật điều hòa $F = F_0 \cos \omega t$. Một lò xo không có lò xo được đặt giữa thân và tường. Độ cứng của nó phải bằng bao nhiêu để biên độ của lực tác dụng lên tường khác $F_0$ hệ số 3?

Đây là bài toán tổng quát để tính dao động cưỡng bức. Lời giải - phương trình dao động của tải trọng với tần số của lực cưỡng bức (xem hình):

$$x = A \cos (\omega t + \varphi),$$

trong đó $A$ là biên độ, $\varphi$ là độ lệch pha của dao động cưỡng bức.

Theo định luật II Newton,

$$F_0 \cos \omega t - kx = Ma,$$

hoặc

$$F_0 \cos \omega t - kA \cos (\omega t + \varphi) = -M \omega^2 A \cos (\omega t + \varphi).$$

Có thể thấy rằng độ lệch pha $\varphi$ bằng 0 hoặc $\pi$. Trong cả hai trường hợp, biên độ của slya $T = kx$ có ​​thể được viết dưới dạng

$$T_{\max} = kx_{\max} = \frac{F_0}{|1 - M \omega^2 / k|}.$$

Chúng tôi quan tâm đến các giá trị $k$ mà $T_{\max} = 3F_0$ và $T_{\max} = 1/3F_0$, vì vậy chúng tôi viết

$$1 - \frac{M \omega^2}{k_1} = \frac{1}{3} \Rightarrow k_1 = 3/2 M \omega^2,$$

$$\frac{M \omega^2}{k_2} - 1 = \frac{1}{3} \Rightarrow k_2 = 3/4 M \omega^2,$$

$$\frac{M \omega^2}{k_3} - 1 = 3 \Rightarrow k_3 = 1/4 M \omega^2.$$

I. Vorobiev
