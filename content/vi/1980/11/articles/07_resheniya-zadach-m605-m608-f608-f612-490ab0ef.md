---
id: 1980-11-resheniya-zadach-m605-m608-f608-f612-490ab0ef
issue: kvant_1980_11
year: 1980
number: "11"
title: Lời giải bài toán M605—M608; F608—F612
rubric: zadachnik-kvanta
rubric_sub: Задачник «Кванта»
page_first: 23
page_last: 28
page_labels: 21-26
tag: 61XD
lang: vi
source: kvant_digital
extraction: vision
content_sha256: 30a56a1a330f9d06be328fc888e6273c141d29b1b7a19f7fa06cc466818a37d3
prompt_sha256: draft-1
translated_from: content/ru/1980/11/articles/07_resheniya-zadach-m605-m608-f608-f612-490ab0ef.md
source_content_sha256: 89f79ece3ac68abfd63564f902240d67c09253d239f24e120026b7be2d04e513
translation_model: draft
translation_run: vi-draft-2026-10-31
translation_quality: draft
---

⟦folio 21⟧

Lời giải bài toán

M605. Có 2n+1 điểm khác nhau được đánh dấu trên mặt phẳng. Chúng ta hãy đánh số chúng theo các số 1, 2, ..., 2n+1 và xem xét phép biến đổi sau của mặt phẳng R: đầu tiên, sự đối xứng được thực hiện đối với điểm đầu tiên, sau đó đối với điểm thứ hai, v.v., cho đến điểm thứ (2n+1).

a) Chứng minh rằng phép biến đổi R này có một “điểm cố định” duy nhất (một điểm ánh xạ vào chính nó).

Hãy xem xét tất cả các cách có thể để đặt tên cho tối đa 2n+1 điểm (theo số 1, 2, ..., 2n+1). Mỗi tên như vậy tương ứng với phép biến đổi riêng của mặt phẳng R và điểm cố định riêng của nó. Gọi F là tập hợp các điểm cố định của tất cả các phép biến đổi này.

6) Chỉ định tập F cho n=1.

c) Tập F có thể chứa tối đa bao nhiêu và bao nhiêu điểm tối thiểu với mỗi n=2, 3, ...?

Chúng tôi sửa một hệ tọa độ tùy ý.

Giả sử các điểm A(x; y) và A*(x*; y*) đối xứng với điểm A'(x'; y'). Khi đó x' = (x+x*)/2, y' = (y+y*)/2, từ đó x* = 2x' - x, y* = 2y' - y.

Như vậy, một điểm có tọa độ (x; y) đối xứng với một điểm có tọa độ (x'; y') sẽ đi vào một điểm có tọa độ (2x' - x; 2y' - y).

Với phép biến đổi R của chúng ta, một điểm có tọa độ (x; y) sẽ chuyển đến một điểm có tọa độ (-x+2x1 - 2x2+...+2x2n+1; y+2y1 - 2y2+...+2y2n+1), trong đó (x_i; y_i) là tọa độ của thứ i của 2n+1 điểm đã cho.

a) Đối với điểm cố định (x; y) của phép biến đổi R, các tọa độ này được xác định duy nhất từ ​​điều kiện

$$\begin{cases} -x+2x_1-2x_2+\dots+2x_{2n+1}=x, \\ -y+2y_1-2y_2+\dots+2y_{2n+1}=y \end{cases}$$

và bằng (x_1-x_2+\dots-x_{2n}+x_{2n+1}; y_1-y_2+\dots-y_{2n}+y_{2n+1}) hoặc

$$\left( \sum_{i=1}^{2n+1} (-1)^{i-1} x_i; \sum_{i=1}^{2n+1} (-1)^{i-1} y_i \right).$$

Mệnh đề a) đã được chứng minh.

6) Đầu tiên cho trước các điểm X1, X2, X3 không nằm trên cùng một đường thẳng. Nếu các điểm A1 sau các điểm đối xứng X1, X2, X3 được ánh xạ vào chính chúng (xem hình) thì X1, X2, X3 là trung điểm của các đoạn A1A2, A2A3, A3A1, trong đó A2 = S_{X1}(A1), A3 = S_{X2}(A2). Điều này có nghĩa là [A1X2], [A2X3], [A3X1] là các đường trung tuyến của tam giác A1A2A3 nên các điểm A1, A2, A3 có thể lấy được từ các điểm X1, X2, X3 có sẵn tâm O và hệ số (-2). Dễ dàng nhận thấy nếu cho các điểm X1, X2, X3 thẳng hàng thì đáp số cho kết quả có ý nghĩa tương tự.

c) Nhìn vào biểu thức (*), không khó để nói rằng trong tập F không có nhiều điểm hơn số cách tạo ra từ 2n+1 điểm cho trước n điểm có hoành độ trong biểu thức (*) sẽ đứng trước dấu trừ, nghĩa là không lớn hơn C2n+1. Rõ ràng, ước tính này là chính xác (ví dụ: lấy 2n+1 điểm trên cùng một dòng có tọa độ nguyên 1, 2, 2^2, ..., 22n).

Bây giờ chúng ta hãy ước tính số lượng điểm cố định. Chúng ta chiếu 2n+1 điểm này lên một đường thẳng sao cho không có hai điểm nào trùng nhau. Trên dòng này chúng ta nhập tọa độ và thay đổi các điểm theo thứ tự tọa độ tăng dần: x1 < x2 < ... < x2n+1. Hãy đặt n trừ trước n số đầu tiên và xét tổng - x1 - x2 - ... - xn + xn+1 + ... + x2n+1; nó sẽ tương ứng với một số điểm cố định từ tập F của chúng ta. Tiếp theo, chúng ta thực hiện thao tác sau: chọn một cặp số x_i và x_i+1 sao cho x_i đứng trước dấu trừ và x_i+1 đứng trước dấu cộng và thay đổi dấu của chúng (trong bước đầu tiên, ước tính là i=n). Mỗi thao tác như vậy dẫn đến một tổng tương ứng với một điểm cố định từ tập F và vì sau mỗi thao tác tổng giảm đi nên tất cả các điểm cố định này đều khác nhau. Chúng ta có thể thực hiện tất cả các thao tác như vậy (bất kể thứ tự của chúng) n(n+1), điều này đã mang lại cho chúng ta

⟦folio 22⟧

M606. Hàm $f$ sao cho đối với mọi $x$ $f(x+1)+f(x-1)=\sqrt{2}f(x)$ thực. Chứng minh rằng $f$ là hàm tuần hoàn.

M607. a) Cắt hình vuông thành các hình thang đều. b) Cắt một tam giác vuông đều thành hình thang đều. c) Chứng minh rằng mọi đa giác đều có thể cắt thành hình thang đều.

Hình 1.

Hình 2. Hình 3.

$n(n+1)+1$ điểm cố định. Điều này có nghĩa là có ít nhất $n(n+1)+1$ điểm trong $F$. Ví dụ: sẽ đạt được chính xác số điểm cố định này nếu chúng ta lại lấy $2n+1$ điểm trên một đường thẳng có tọa độ nguyên $-n$, $-(n-1)$, ..., $-1$, 0, 1, 2, ..., $n-1$, $n$. Với tất cả các cách có thể để đặt $n$ “trừ” trước một số trong số chúng, giá trị lớn nhất của tổng các số này là $2 \cdot (1+2+\dots+n)=n(n+1)$, giá trị nhỏ nhất là $-n(n+1)$ và tổng có thể nhận bất kỳ giá trị chẵn nào giữa các số $-n(n+1)$ và $n(n+1)$ - tổng giá trị $n(n+1)+1$.

I. Klumova, A. Talai

◆
Theo điều kiện, với mọi số thực $x$ đẳng thức
$$f(x+2)+f(x)=\sqrt{2}f(x+1)=\sqrt{2}(\sqrt{2}f(x)-f(x-1))=
=2f(x)-\sqrt{2}f(x-1),$$
đó là
$$f(x+2)=f(x)-\sqrt{2}f(x-1).$$
Pozny
$$f(x+4)=f(x+2)-\sqrt{2}f(x+1)=
=f(x)-\sqrt{2}(f(x-1)+f(x+1))=-f(x).$$
Kể từ đây,
$$f(x+8)=-f(x+4)=f(x)$$
với mọi $x \in \mathbb{R}$, vì vậy $f$ là hàm tuần hoàn có chu kỳ là 8.
Lưu ý rằng các hàm thỏa mãn phương trình ban đầu tồn tại, ví dụ: $f(x)=\sin \frac{\pi x}{4}$.

E. Turkevich

◆
Lưu ý rằng một tam giác đều có thể dễ dàng chia thành các hình thang đều (Hình 1); Vì vậy, chỉ cần đưa phân vùng về hình tam giác đều là đủ.
Bây giờ chúng tôi có thể cung cấp những điều sau cho bài toán của mình:
a) Các phân vùng được yêu cầu có thể chẳng hạn như trong Hình 2, 3.
b) Một tam giác vuông đối diện có thể được cắt, chẳng hạn như trong Hình 4 và 5. Mỗi cách chia này đưa ra những cách chia hình vuông mới.
Các cách khác để cắt những hình này được lấy từ điểm c).
b) Rõ ràng đa giác nào được chia thành đa giác lồi và đa giác lồi nào được cắt thành hình tam giác bởi các đường chéo xuất phát từ một đỉnh bất kỳ. Bất kỳ hình tam giác nào cũng có thể chia thành hai hình tam giác vuông có chiều cao giảm xuống một cạnh; cuối cùng, tam giác vuông nào có thể cắt thành hai tam giác đều nối cạnh huyền với đỉnh của góc vuông.
Pozny chỉ cần chứng minh khẳng định về tam giác đều tùy ý là đủ.
Để cho ngắn gọn, chúng ta sẽ gọi một tam giác đều có góc $\alpha$ ở đáy là “$\alpha$-tam giác”.
Hãy xem xét ba trường hợp.
1°. $30^\circ \leq \alpha < 60^\circ$. Việc cắt yêu cầu được thể hiện trong Hình 6.
2°. $0 < \alpha < 30^\circ$. Như có thể thấy trong Hình 7, nếu có thể cắt được tam giác $2\alpha$ thì tam giác $\alpha$ cũng có thể được cắt. Từ đây và từ 1°, chúng ta lần lượt thu được các tam giác đều cắt có các góc ở đáy
$15^\circ \leq \alpha < 30^\circ$, $7,5^\circ \leq \alpha < 15^\circ$, $3,75^\circ \leq \alpha < 7,5^\circ$...

⟦folio 23⟧

M608. Trên tờ giấy ca-rô (cạnh hình vuông 1) có vẽ một thanh p, các cạnh của thanh này nằm trên các đường lưới và có chiều dài lẻ.
a) Chứng minh rằng n chia hết cho 4.
b) Chứng minh rằng với n=100 thì diện tích của n-tay này nhất thiết phải là số lẻ. Tìm xem tính chẵn lẻ của diện tích đối với mỗi n.

Vì bất kỳ α, 0°<α<30° nào, rơi rất nhiều vào một trong các khoảng đã chỉ ra, nên chúng ta thu được điều đó với α<30° bất kỳ tam giác α nào cũng có thể bị cắt theo cách yêu cầu.

3°. 60°<α<90°. Việc chứng minh tương tự như trường hợp 2° (Hình 8). Rõ ràng, $\widehat{BAB'}=45^\circ-\frac{\alpha'}{2}<45^\circ$ ($B'$ là tâm đường tròn ngoại tiếp tam giác ABC), và do đó các tam giác BAB' và BCB' là "có thể cắt được".

Tiếp tục quá trình này cho các tam giác AB'C (điểm B''), AB''C, ..., rõ ràng sớm hay muộn chúng ta sẽ thu được một tam giác đều có góc đáy nhỏ hơn 60°.

V. Lev

◆ a) Hiển nhiên, đa giác này có số cạnh ngang bằng số cạnh dọc, vì các cạnh ngang và dọc cắt nhau. Điều này có nghĩa là n=2k, trong đó k là số cạnh dọc (hoặc ngang). Rõ ràng là tổng độ dài của các cạnh thẳng đứng là chẵn, vì chúng ta “đi xuống” một lượng bằng với khi chúng ta “đi lên”. Nhưng độ dài của mỗi đoạn là số lẻ; điều này có nghĩa là các cạnh thẳng đứng là số chẵn, tức là k=2m. Do đó n=4m chia hết cho 4.
b) Hãy giới thiệu hệ tọa độ sao cho trục Ox và Oy chứa cạnh dưới cùng và cạnh trái nhất của 4m-giác của chúng ta. Khi đó tọa độ các đỉnh của đa giác của chúng ta sẽ bằng nhau
$ (a_1; b_1), (a_2; b_1), (a_2; b_2), (a_3; b_2), (a_3; b_3), ..., (a_{2m-1}; b_{2m-1}),$
$ (a_{2m}; b_{2m-1}), (a_{2m}; b_{2m}), (a_1; b_2m),$
trong đó $a_i, b_i$ là số nguyên không âm và tất cả hiệu $a_{i+1}-a_i, b_{i+1}-b_i$ ($i=1, 2, ..., 2m$) đều là số lẻ; ở đây và bên dưới $a_{2m+1}=a_1, b_{2m+1}=b_1$. Có thể dễ dàng biểu thị diện tích S của đa giác thông qua các tọa độ này, biểu thị nó dưới dạng tổng và hiệu các diện tích của hình chữ nhật $|a_{i+1}-a_i| \times b_i$:

$$S = \left| \sum_{i=1}^{2m} (a_{i+1}-a_i) b_i \right|.$$

Vì tất cả hiệu $a_{i+1}-a_i$ đều là số lẻ nên tổng S có cùng tính chẵn lẻ với tổng $b_1+b_2+\dots+b_{2m}$. Các số chẵn lẻ của các số $b_1, b_2, ..., b_{2m}$ giao nhau (vì tất cả hiệu $b_{i+1}-b_i$ đều là số lẻ), nên tất cả tổng m $b_1+b_2, b_3+b_4, ..., b_{2m-1}+b_{2m}$

⟦folio 24⟧

F608. Một tàu vũ trụ có khối lượng $M=12$ t di chuyển quanh Mặt trăng theo quỹ đạo tròn ở độ cao $h=100$ km. Để chuyển sang quỹ đạo hạ cánh, bộ phận đẩy phản lực được bật trong thời gian ngắn. Tốc độ của khí rời khỏi phòng tắm nắng của tên lửa là $u = 10^4$ m/s. Bán kính của Mặt trăng là $R_\pi = 1,7 \cdot 10^3$ km, gia tốc tự do trên bề mặt Mặt trăng là $g_\pi = 1,7$ m/s².
1) Phải tiêu tốn bao nhiêu nhiên liệu để khi kích hoạt chuyển động phanh tại điểm A trên quỹ đạo tàu sẽ lao xuống Mặt Trăng tại điểm B (Hình 1)?
2) Trong phương án hạ cánh thứ hai, một xung được truyền tới tàu tại điểm A theo hướng tâm Mặt trăng để đưa tàu vào quỹ đạo chạm vào Mặt trăng tại điểm C (Hình 2). Cần tiêu thụ bao nhiêu nhiên liệu trong trường hợp này?

Hình 1.

Hình 2.

1) Khi một con tàu di chuyển quanh Mặt trăng theo quỹ đạo tròn, gia tốc hướng tâm của con tàu được truyền bởi lực hấp dẫn. Bởi vì

$$\frac{Mv^2}{R} = \gamma \frac{MM_\pi}{R^2},$$

trong đó $v$ là tốc độ của con tàu theo quỹ đạo tròn, $M_\pi$ là khối lượng của Mặt Trăng và $R = R_\pi + h$ là bán kính quỹ đạo của con tàu. Từ phương trình này chúng ta tìm thấy

$$v = \sqrt{\gamma \frac{M_\pi}{R}} = \sqrt{g_\pi \frac{R^2_\pi}{R}} \approx 1,65 \cdot 10^3 \text{ м/c.}$$

Sau khi thay đổi vận tốc của tàu tại điểm A, tàu sẽ chuyển động theo quỹ đạo hình elip. Chúng ta hãy ký hiệu lần lượt là $v_A$ và $v_B$ tốc độ của tàu tại các điểm A và B của quỹ đạo này. Theo định luật bảo toàn năng lượng

$$-\gamma \frac{M_\pi M_1}{R} + \frac{M_1 v_A^2}{2} = -\gamma \frac{M_\pi M_1}{R_\pi} + \frac{M_1 v_B^2}{2}$$

(1)

$-\gamma \frac{MM_\pi}{R}$ là thế năng của một vật có khối lượng $M$ chuyển động theo quỹ đạo tròn trong trường hấp dẫn của Mặt Trăng, $M_1$ là khối lượng của phương tiện lao xuống); theo định luật bảo toàn động lượng góc (hoặc, tương tự, theo định luật thứ hai của Kepler)

$$v_A R = v_B R_\pi.$$

(2)

Giải các phương trình (1) và (2) cùng nhau, ta tìm được

$$v_A = \sqrt{2\gamma \frac{M_\pi R_\pi}{(R_\pi + R)}} = v \sqrt{\frac{2R_\pi}{R + R_\pi}}.$$

Do đó, để chuyển từ quỹ đạo tròn sang quỹ đạo elip tại điểm A, tốc độ phải thay đổi bằng

$$\Delta v = v - v_A = v \left( 1 - \sqrt{\frac{2R_\pi}{R + R_\pi}} \right) = v \left( 1 - \sqrt{\frac{2R_\pi}{h + 2R_\pi}} \right) = v \left( 1 - \frac{1}{\sqrt{1 + \frac{h}{2R_\pi}}} \right) = v \frac{h}{4R_\pi} \approx 24 \text{ м/c.}$$

Vì hệ động lực hoạt động theo thời gian vòng tròn nên có thể giả sử động lượng của hệ “xe đổ bộ - nhiên liệu” được bảo toàn. Vì vậy, chúng ta có thể sử dụng định luật bảo toàn động lượng, cho

$$(M - m) \Delta v = mu,$$

trong đó $m$ là khối lượng của chất đẩy. Từ đây

$$m = \frac{\Delta v}{\Delta v + u} M \approx \frac{\Delta v}{u} M \approx 29 \text{ кг.}$$

2) Trong trường hợp thứ hai, tốc độ $v$ của tàu tại điểm A thay đổi theo giá trị $\Delta v$ và tốc độ $v_A$ trong quỹ đạo mới giống như $v_A^2 = v^2 + (\Delta v)^2$ (kể từ $\Delta v \perp v$).

Từ định luật bảo toàn năng lượng (một biểu thức tương tự như (1), với $v_B$ thay thế bằng $v_C$) và định luật bảo toàn động lượng góc ($v_A R = v_C R_\pi$) ta tìm được

$$\Delta v = \sqrt{g_\pi \frac{(R - R_\pi)^2}{R}} = \sqrt{g_\pi \frac{h^2}{R_\pi + h}} \approx 97 \text{ м/c.}$$

⟦folio 25⟧

Khối lượng nhiên liệu tiêu thụ trong trường hợp này bằng
$$m \approx \frac{\Delta v}{u} M \approx 116 \text{ кг}.$$
I. Slobodetsky

F609. Bộ phận được làm bằng nhôm được cân trên cân phân tích sử dụng đồng thau.zip. Trong một lần cân, không khí bên trong cân khô và trong lần cân kia thì ướt, áp suất hơi nước trong đó bằng $p_{B,\pi} = 15,2$ mmHg. Nghệ thuật. Áp suất bên ngoài ($p = 760$ mm Hg) và nhiệt độ ($t = 20^\circ C$) của không khí là như nhau trong cả hai trường hợp.
Khối lượng của bộ phận đó có thể được thay thế bằng bao nhiêu chênh lệch trong số đọc trên thang đo nếu giá trị màu của chúng là $m_0 = 0,1$ m? Mật độ nhôm $Q_1 = 2,7 \text{ e/cm}^3$, đồng thau $Q_2 = 8,5 \text{ e/cm}^3$.

Hãy viết các điều kiện cân bằng để cân trong không khí khô:
$$m_1 g - F_{A1} = m_2 g - F_{A2}.$$
Ở đây $m_1 = Q_1 V_1$ là khối lượng của bộ phận ($V_1$ là thể tích của nó); $m_2 = Q_2 V_2 g$ — khối lượng của các vật nặng ($V_2$ — thể tích của chúng); $F_{A1} = Q_{c,B} V_1 g$, $F_{A2} = Q_{c,B} V_2 g$ - Lực Archimedean lần lượt tác dụng lên bộ phận và trọng lượng từ phía không khí khô ($Q_{c,B}$ - mật độ không khí khô). Như vậy, ở trạng thái cân bằng khi lơ lửng trong không khí khô
$$(Q_1 - Q_{c,B}) V_1 - (Q_2 - Q_{c,B}) V_2 = 0.$$ (1)

Để có thể phát hiện được độ lệch của cân so với trạng thái cân bằng trong không khí ẩm (có cùng khối lượng vật nặng) cần phải đáp ứng các điều kiện sau:
$$(Q_1 - Q_{c,B}) V_1 - (Q_2 - Q_{c,B}) V_2 \geq m_0,$$ (2)

trong đó $Q_{c,B}$ là mật độ không khí ẩm.
TỪ (1) và (2) ta tìm được điều kiện mà khối lượng của bộ phận đó phải thỏa mãn:
$$m_1 = Q_1 V_1 \geq m_0 Q_1 \frac{Q_2 - Q_{c,B}}{(Q_{c,B} - Q_{c,B}) (Q_2 - Q_1)}.$$ (3)

Hãy biểu diễn các đại lượng $Q_{c,B}$ và $Q_{c,B}$ thông qua các tham số xác định trong điều kiện bài toán - $T = 293$ K, $p \approx 10^5$ Pa, $p_{B,\pi} \approx 2 \cdot 10^3$ Pa.

Từ phương trình trạng thái khí $pV = \frac{m}{M} RT$ suy ra rằng
$$Q_{c,B} = \frac{p_{c,B} M_{c,B}}{RT} = \frac{p M_{c,B}}{RT},$$
trong đó $M_{c,B} = 29 \cdot 10^{-3}$ kg/mol là khối lượng mol của không khí khô. Mật độ của không khí ẩm là
$$Q_{c,B} = Q'_{c,B} + Q_{c,\pi},$$
trong đó $Q'_{c,B}$ là mật độ không khí khô có trong thể tích $V$ của không khí ẩm; $Q_{c,\pi}$ là mật độ hơi nước có trong thể tích $V$ của không khí ẩm. Theo phương trình trạng thái khí
$$Q_{c,\pi} = \frac{p_{c,B} M_{c,B}}{RT},$$
$$Q'_{c,B} = \frac{(p - p_{c,B}) M_{c,B}}{RT},$$
trong đó $M_{B,\pi} = 18 \cdot 10^{-3}$ mg/mol là khối lượng mol của hơi nước, $(p - p_{c,B})$ là áp suất riêng phần của không khí khô trong thể tích $V$ của không khí ẩm. Như vậy,
$$Q_{c,B} = \frac{(p - p_{c,B}) M_{c,B}}{RT} \approx 43,2 \text{ г}.$$

V. Belonukin

F610. Trong thí nghiệm của Liên Xô-Pháp về vị trí quang học của Mặt trăng, bức xạ xung từ laser ruby ​​​​ở bước sóng $\lambda = 0,69$ µm được hướng bằng telexan có đường kính gương $D = 2,6$ m lên bề mặt mặt trăng. Một tấm phản xạ đã được lắp đặt trên Mặt trăng,

1) Độ chính xác của việc thiết lập trục quang của telexan được xác định bởi sự phân kỳ nhiễu xạ của chùm tia:
$$\delta \varphi \approx \frac{\lambda}{D} = 2,6 \cdot 10^{-7} \text{ рад} = 0,05''.$$
2) Bán kính của điểm sáng trên Mặt trăng là $\frac{\lambda}{D}$. Do đó, phần năng lượng laser chạm vào gương phản xạ là
$$K_1 = \frac{d^2}{4(L\lambda/D)^2} = \left(\frac{dD}{2\lambda L}\right)^2.$$

⟦folio 26⟧

hoạt động như một tấm gương lý tưởng có đường kính $d = 20$ cm, phản chiếu ánh sáng theo hướng ngược lại. Ánh sáng phản xạ được thu lại bởi cùng một kính viễn vọng và tập trung vào bộ tách sóng quang.

1) Trục quang học của kính thiên văn được đặt trong thí nghiệm này với độ chính xác bao nhiêu?

2) Bỏ qua sự mất mát ánh sáng trong bầu khí quyển Trái đất và trong kính thiên văn, hãy ước tính phần năng lượng ánh sáng laser sẽ được máy tách sóng quang phát hiện sau khi phản xạ từ Mặt trăng.

3) Mắt thường có thể phát hiện được xung ánh sáng phản xạ nếu độ nhạy của mắt bằng $n = 100$ lượng tử ánh sáng và năng lượng phát ra từ tia laser trong suốt xung bằng $W = 1$ J?

4) Đánh giá lợi ích thu được từ việc sử dụng tấm phản xạ. Giả sử rằng bề mặt của Mặt trăng tán xạ $\alpha = 10\%$ nadauce ánh sáng đồng đều thành một góc đặc $2\pi$ cf. Khoảng cách từ Trái đất đến Mặt trăng là $L = 380 \cdot 10^3$ km. Đường kính của màn hình laser được đặt thành $d_{3p} = 5$ mm. Hằng số Planck $h = 6,6 \cdot 10^{-34}$ J・s.

F611. Người nhào lộn, nằm trên bề mặt bên của hình trụ, nằm trên sàn rất gồ ghề, di chuyển qua các vị trí và di chuyển với tốc độ không đổi sang phải. Coi hệ số ma sát của ủng của người nhào lộn trên bề mặt hình trụ bằng $\mu$, hãy xác định góc giới hạn $\alpha$ có ​​thể tạo được khi bán kính thẳng đứng của hình trụ vẽ đến điểm đặt người nhào lộn. Lực ma sát giữa ủng của người nhào lộn và hình trụ sẽ như thế nào?

Các lực tác dụng lên người nhào lộn là lực hấp dẫn $\vec{mg}$, lực ma sát $\vec{F}_{\tau p}$ và phản lực pháp tuyến $\vec{N}$ (xem hình). Theo điều kiện bài toán người nhào lộn di chuyển với tốc độ không đổi. Do đó, theo định luật II Newton, tổng vectơ của các lực $\vec{mg}, \vec{F}_{\tau p}$ và $\vec{N}$ bằng 0. Chúng ta hãy viết điều kiện này dưới dạng hình chiếu trên trục $X$ và $Y$, hướng như trong hình (hệ tọa độ $XOY$ di chuyển sang phải với cùng tốc độ với người nhào lộn; gốc tọa độ trùng với điểm mà người nhào lộn nằm):

trong các hình chiếu lên trục $X$ —
$$mg \sin \alpha - F_{\tau p} = 0;$$

trong các hình chiếu lên trục $Y$ —
$$N - mg \cos \alpha = 0.$$

Xét $F_{\tau p} \leq \mu N$, từ (1) và (2) góc $\alpha = \alpha_0$ tìm được:

$$\alpha_0 = \arctg \mu.$$

Độ lớn của lực ma sát tại $\alpha = \alpha_0$ bằng
$$F = mg \sin \alpha_0 = mg \frac{\mu}{\sqrt{1 + \mu^2}}.$$

S. Krotov
