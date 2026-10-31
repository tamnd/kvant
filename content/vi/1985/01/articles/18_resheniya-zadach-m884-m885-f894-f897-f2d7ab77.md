---
id: 1985-1-resheniya-zadach-m884-m885-f894-f897-f2d7ab77
issue: kvant_1985_1
year: 1985
number: "1"
title: Lời giải bài toán M884, M885; F894—F897
rubric: zadachnik-kvanta
rubric_sub: Задачник «Кванта»
page_first: 47
page_last: 52
page_labels: 45-50
tag: UR8E
lang: vi
source: kvant_digital
extraction: vision
content_sha256: e0a266d3ac317268d53d38918bc1822e824c6ae2574e7564c91b2dde9901c301
prompt_sha256: draft-1
translated_from: content/ru/1985/01/articles/18_resheniya-zadach-m884-m885-f894-f897-f2d7ab77.md
source_content_sha256: 5e7d673b062898cb85afa82ef515fc654c726eb2fc15769cea185b3c55bfb476
translation_model: draft
translation_run: vi-draft-2026-10-31
translation_quality: draft
---

⟦folio 45⟧

mirror, the lens and the object are enclosed in a case made of translucent plastic (Fig. 2). This system generates two images of the object and an image of the lens. Both images of the object have the same size, independently of the distance between the lens and the object. What is the enlargement of the lens' image?

E. P. Kuznetsov

Lời giải bài toán

M884, M885; F894—F897

Lời giải dựa trên việc xem xét sau: nếu $A(a; f(a))$ và $B(b; f(b))$ là hai điểm trên đồ thị của một hàm (Hình 1), thì hình chữ nhật $\Pi(A, B)$ có đường chéo $AB$ bao phủ phần của đồ thị từ $A$ đến $B$ và diện tích của nó $S$ thỏa mãn bất đẳng thức $2\sqrt{S} \leq l+h$, trong đó $l=b-a$ là chiều dài đáy của nó và $h=f(b)-f(a)$ là chiều cao của nó; bất đẳng thức này về cơ bản là bất đẳng thức về trung bình tranh luận và trung bình hình học $\sqrt{lh} \leq (l+h)/2$.

Việc xem xét này có thể được sử dụng theo hai cách. Chúng ta hãy tạm thời giả định rằng $f(0) = 0$, $f(1) = 1$.

1) Chúng ta hãy mở rộng hàm $f$ đến toàn bộ giá trị dương để nó vẫn liên tục và đơn điệu (ví dụ: chúng ta có thể đặt $f(x) = x$ với $x > 1$). Đặt $A_0$ là điểm bắt đầu của đồ thị (có tọa độ $(0; 0)$). Chúng ta cũng xét các điểm $A_1, ..., A_m$ trên đồ thị sao cho diện tích hình chữ nhật $\Pi(A_{i-1}; A_i)$, $i=1, 2, ..., n$ bằng $1/n^2$; sự tồn tại của những điểm như vậy rõ ràng xuất phát từ tính liên tục và đơn điệu của các hàm số $f$. Đối với mỗi hình chữ nhật này, tổng chiều dài đáy và chiều cao không nhỏ hơn $2\sqrt{1/n^2}=2/n$, do đó tổng tọa độ của điểm $A_n$ (bằng, tương ứng với tổng chiều dài đáy của tất cả các hình chữ nhật và tổng chiều cao của chúng) không nhỏ hơn 2. Do đó, ít nhất một trong các tọa độ này không nhỏ hơn 1, nghĩa là hình chữ nhật $n$ được dựng bao phủ phần đồ thị.

2) Chúng ta hãy chọn các điểm $B_0, B_1, ..., B_n$ trên đồ thị của hàm $f$, bắt đầu từ $B_0$ $(0; 0)$, sao cho tổng chiều dài đáy và chiều cao của mỗi hình chữ nhật $\Pi(B_{i-1}, B_i)$, $i=1, ..., n$ bằng $2/n$. (Dễ dàng nhận thấy $B_i$ là giao điểm của đường $y=2i/n-x$ với đồ thị, cụ thể $B_n$ là điểm cuối của đồ thị - điểm $(1; 1)$; xem Hình 2.) Do ước tính trên nên diện tích mỗi hình chữ nhật không vượt quá $1/n^2$. Phóng to chúng nếu cần thiết để diện tích của chúng bằng nhau

⟦folio 46⟧

1/n², chúng tôi nhận được phạm vi bảo hiểm cần thiết.

Nếu f(0) > 0 hoặc f(1) < 1, chúng ta bổ sung vào biểu đồ các đoạn thẳng đứng nối điểm (0; 0) với điểm đầu (0; f(0)) và (1; 1) với điểm cuối (1; f(1)) (Hình 3). Bạn sẽ có một đường cong liên tục nối các điểm (0; 0) và (1; 1), theo đó cả hai cách giải thích trên có thể được áp dụng thực tế mà không cần thay đổi.

Ví dụ tương tự cho phép phát biểu bài toán đối với bất kỳ hàm f nào (có thể không liên tục): tại các điểm gián đoạn, đồ thị được bù với một đường cong liên tục bằng một đoạn (đoạn màu đỏ trong Hình 4). Tuy nhiên, sự biện minh chặt chẽ trong trường hợp này có phần nằm ngoài phạm vi chương trình giảng dạy của trường.

N. B. Vasiliev,
V. N. Dubrovsky,
S. Yu. Orevkov

**M885*. Với mỗi số tự nhiên n, chúng ta biểu thị bằng p(n) số phần của n thành tổng các phần tử tự nhiên (các phân vùng chỉ khác nhau về thứ tự của các phần tử được coi là giống hệt nhau). Tập hợp các phân vùng số trong một phân vùng nhất định được gọi là phân tích cú pháp của nó.

a) Chứng minh rằng tổng q(n) của các phân số của tất cả các phân số của số n bằng 1 + p(1) + p(2) + ... + p(n-1).

b) Chứng minh rằng tổng này không lớn hơn √2n p(n).

4-4
4-3+1 ↔ 1-1
4-2+2 ↔ 2-2
4-2+1+1 ↔ 2-1+1
4-1+3 ↔ 3-3
4-1+2+1 ↔ 3-2+1
4-1+1+1+1 ↔ 3-1+1+1

a) Phép chia số n cho tổng các số hạng tự nhiên gọi là phép chia số hạng nếu một số hạng tách khỏi các số hạng còn lại (được gạch chân); Chúng tôi sẽ coi các phân vùng bị dịch chuyển, chỉ xuất sắc theo thứ tự của các phân khu, là giống hệt nhau. (Hình bên trái hiển thị tất cả các phân vùng offset của số 4; những phân vùng được chọn được hiển thị màu đỏ.) Lưu ý rằng nếu k là độ phân tán của một số phân vùng (không offset), thì có thể lấy được k phân vùng offset từ phân vùng này. Do đó, tổng số phân vùng offset của n bằng q(n). Mặt khác, nếu từ bất kỳ phân vùng nào bị loại bỏ, ngoại trừ phân vùng gồm một phần tử duy nhất, phần tử gạch chân bị loại bỏ thì kết quả sẽ là một phân vùng có số nào đó nhỏ hơn n. Và ngược lại, nếu m < n, thì từ bất kỳ phân vùng nào của số m, người ta có thể khôi phục duy nhất phân vùng offset của số n: cần thêm triệu n-m vào phân vùng của số m và gạch chân nó (hình vẽ thể hiện sự tương ứng một-một giữa các phân vùng offset của số 4, ngoại trừ phân vùng 4 = 4 và phân vùng của các số nhỏ hơn 4). Nhưng số cách phân chia của các số nhỏ hơn n lại bằng p(1) + p(2) + ... + p(n-1). Do đó, q(n) - 1 = p(1) + p(2) + ... + p(n-1).

Nói cách khác, ý tưởng của lời giải này có thể được phát biểu như sau: nếu k với mỗi phân vùng p(1) + p(2) + ... + p(n-1) của các số m = 1, 2, ..., n-1, chúng ta thêm một số hạng n-m, thì chúng ta sẽ nhận được mỗi phân vùng của số n (ngoại trừ trival n=n) gấp nhiều lần độ lan rộng của nó.

6) Nó đủ để chứng minh rằng sự phân chia bất kỳ phân số n thành tổng các số triệu tự nhiên không vượt quá √2n. Hãy chứng minh nhận định này. Đặt a₁, ..., aₙ là tất cả các thuật ngữ riêng biệt có trong một số phân vùng (có phân tích cú pháp k) và 0 < a₁ < ... < aₙ. Sau đó, một mặt,

⟦folio 47⟧

$$a_1 + a_2 + \dots + a_k \leq n, \text{ а, с другой стороны, } a_1 \geq 1, \quad a_2 \geq 2, \quad \dots, \quad a_k \geq k \quad (\text{действительно, } a_1 \geq 1; \quad a_2 > a_1 \geq 1, \quad \text{следовательно, } a_2 \geq 2; \quad a_3 > a_2 \geq 2, \quad \text{следовательно, } a_3 \geq 3, \quad \text{и т. д.}).$$
Vì vậy $n \geq a_1 + a_2 + \dots + a_k \geq 1 + 2 + \dots + k = k(k+1)/2 \geq k^2/2$, tức là $k \leq \sqrt{2n}$.

S. Yu. Orevkov

F894. Trong một trong các dự án, người ta dự định sử dụng cánh buồm mặt trời có diện tích $S=1$ km$^2$ cho các chuyến bay của tàu vũ trụ trong Hệ Mặt trời. Cánh buồm mở ra khi phương tiện di chuyển quanh Mặt trời theo quỹ đạo Trái đất, bán kính của nó là $R_3=1,5\cdot 01^8$ km. Với chuyển động xa hơn, cánh buồm liên tục được định hướng vuông góc với tia nắng mặt trời, áp suất của nó trong quỹ đạo trái đất là $p=10^{-5}$ Pa.
1) Nó có thể bay khỏi Hệ Mặt trời với khối lượng bao nhiêu?
2) Với khối lượng tối đa bao nhiêu thì phương tiện có thể đi tới quỹ đạo của Sao Hỏa có bán kính là $R_M=2,3\cdot 10^8$ km? Ảnh hưởng hấp dẫn của Trái đất và các hành tinh khác không được tính đến.
Tích của khối lượng Mặt trời và hằng số hấp dẫn $M_C G=1,3\cdot 10^{11}$ km$^3/c^2$.

◆ Khi cánh buồm mặt trời được triển khai, lực căng mặt trời và lực ép của tia mặt trời tác dụng lên thiết bị. Đánh giá kết quả của các lược đồ này -

$$F_{\varphi} = G \frac{M_C m}{R_3^2} - p S = G \frac{M_C m}{R_3^2} - \frac{G m R_3^2 p S}{G m R_3^2} = G \frac{(M_C - p SR_3^2/G m) m}{R_3^2}.$$

Chúng ta thấy rằng áp suất của các tia mặt trời dường như làm giảm độ lớn lực căng của thiết bị đối với Mặt trời - lực này hóa ra giống như khi Mặt trời không có khối lượng $M_C$, nhưng có khối lượng hiệu dụng nhỏ hơn một chút bằng

$$M_{\varphi} = M_C - \frac{p SR_3^2}{G m}.$$

Sử dụng khối lượng hiệu dụng đã giới thiệu, chúng ta có thể giải thêm bài toán mà không tính đến áp suất của tia mặt trời.

Tổng năng lượng của tàu vũ trụ trong trường biên của một vật thể có khối lượng $M_{\varphi}$ —

$$E = \frac{mv^2}{2} - G \frac{m M_{\varphi}}{R}.$$

Theo định luật bảo toàn năng lượng, năng lượng này tại bất kỳ điểm nào trên quỹ đạo của tàu vũ trụ phải bằng

$$E = \frac{mv^2}{2} - G \frac{m M_{\varphi}}{R_3},$$

trong đó $v_3$ là tốc độ mà phương tiện đạt được tại thời điểm mở cánh buồm ở khoảng cách $R_3$ tính từ Mặt trời. Chúng ta sẽ tìm tốc độ này từ phương trình chuyển động của bộ máy trên quỹ đạo Trái đất dưới tác dụng của lực Mặt trời:

$$\frac{mv^2}{R_3} = G \frac{m M_C}{R_3^2} \Rightarrow v_3 = \sqrt{G \frac{M_C}{R_3}}.$$

Như vậy,

$$E = G \frac{m}{R_3} \left( \frac{M_C}{2} - M_{\varphi} \right) = G \frac{m}{R_3} \left( \frac{p SR_3^2}{G m} - \frac{M_C}{2} \right).$$

Thiết bị có thể bay khỏi hệ mặt trời nếu $E \geq 0$, tức là được cung cấp

$$\frac{p SR_3^2}{G m} - \frac{M_C}{2} \geq 0.$$

Từ đây bộ máy được đặt

⟦folio 48⟧

Có lẽ:

$$m \leq \frac{2pSR_3^2}{GM_C} \approx 3,46 \cdot 10^3 \text{ кг.}$$

Với khối lượng lớn hơn, thiết bị sẽ chuyển động theo quỹ đạo khép kín.

Để quỹ đạo của thiết bị chạm vào quỹ đạo của Sao Hỏa với khối lượng nhất định $m_1$. (Trong tất cả các khối lượng có thể có $m$, tại đó thiết bị đạt đến quỹ đạo của Sao Hỏa (vượt qua nó), $m_1$ là khối lượng lớn nhất.) Trong trường hợp này, quỹ đạo của thiết bị là một hình elip, trục chính của nó bằng $R_3+R_M$ (xem hình). Tại các điểm tiếp xúc, vận tốc của xe vuông góc với vectơ bán kính của xe.

Theo định luật bảo toàn năng lượng

$$\frac{m_1v_3^2}{2} - G \frac{m_1M_3\phi}{R_3} = \frac{m_1v_2^2}{2} - G \frac{m_1M_3\phi}{R_M} \Rightarrow v_3^2 - v_M^2 = 2GM_3\phi \left( \frac{1}{R_3} - \frac{1}{R_M} \right).$$

Theo định luật thứ hai của Kepler

$$v_3R_3 = v_MR_M \Rightarrow v_M = v_3 \frac{R_3}{R_M}.$$

Thay biểu thức này cho $v_M$ vào (*) và tính đến $v_3 = \sqrt{G \frac{M_C}{R_3}}$, sau một số phép biến đổi, chúng ta thu được:

$$2M_3\phi R_M = M_C(R_M + R_3),$$

hoặc

$$2 \left( M_C - \frac{pSR_3}{Gm} \right) R_M = M_C(R_M + R_3).$$

Từ đây chúng ta tìm được khối lượng tối đa $m_1$ của thiết bị mà tại đó thiết bị có thể chạm tới quỹ đạo của Sao Hỏa

$$m_1 = \frac{2pSR_3^2}{GM_C} \frac{R_M}{R_M-R_3} \approx 10^4 \text{ кг.}$$

V. A. Danilin

F895. Một trong những truyền thuyết về nguồn gốc của vành đai tiểu hành tinh bắt nguồn từ truyền thuyết cổ xưa của Rechensk về con trai của mặt trời Gelyus - Phaethon, bị Zeus (Sao Mộc) tấn công. Theo lý thuyết này, một đàn đá, nơi được cho là hình thành nên hành tinh Fazton, đã đến rất gần Sao Mộc. Dưới ảnh hưởng của đàn cửa ngõ của Sao Mộc, đàn chia thành các đàn riêng biệt - các tiểu hành tinh. Bán kính bầy đàn được ước tính là khoảng 10⁴ km; khối lượng của bầy (tổng khối lượng của các tiểu hành tinh) nhỏ hơn 10⁶ lần so với khối lượng của Sao Mộc.

Bầy đàn sẽ phải di chuyển cách trung tâm Sao Mộc bao xa trước khi nó bắt đầu tan rã?

Chúng ta hãy nhìn vào khối gần Sao Mộc nhất. Sự sụp đổ của đàn đồng nghĩa với việc khoảng cách giữa cụm này và tâm đàn sẽ tăng lên.

Toàn bộ đàn rơi xuống Sao Mộc với gia tốc được truyền cho nó bởi lực hấp dẫn của Sao Mộc:

$$ma_1 = G \frac{mM}{R^2} \Rightarrow a_1 = G \frac{M}{R^2},$$

trong đó $m$ là khối lượng của đàn, $M$ là khối lượng của Sao Mộc, $R$ là khoảng cách giữa tâm của đàn và Sao Mộc. Khối di chuyển dưới tác động của lực hấp dẫn của Sao Mộc và lực hấp dẫn tác động lên nó từ toàn bộ đàn. Gia tốc mà vật chuyển động về phía Sao Mộc là

$$a_2 = G \frac{M}{(R-r)^2} - G \frac{m}{r^2};$$

trong đó $r$ là bán kính của đàn. Nếu $a_2 > a_1$ thì khoảng cách giữa khối và tâm đàn sẽ tăng theo thời gian

⟦folio 49⟧

đàn ông - bầy đàn tan rã. Từ điều kiện này ta có:

$$\frac{M}{(R-r)^2} - \frac{m}{r^2} > \frac{M}{R^2}.$$

Sử dụng $r < R$, chúng tôi tìm thấy:

$$\frac{2rM}{R^3} > \frac{m}{r^2} \Rightarrow R < r^3 \sqrt{\frac{2M}{m}} \approx 1,26 \cdot 10^6 \text{ км}.$$

V. E. Belonchkin

F896. Trong một bình kín chứa nước bão hòa, hơi nước ở nhiệt độ 100°C và lượng nước còn lại. Khối lượng hơi nước $M = 100 \text{ г}$, khối lượng nước $m = 1 \text{ г}$. Bình được làm nóng cho đến khi toàn bộ nước bay hơi. Nên đun nóng bình đến nhiệt độ bao nhiêu? Điều này sẽ cần bao nhiêu nhiệt? Áp suất của hơi nước bão hòa tăng 3,7 kPa khi nhiệt độ tăng 1°C. Nhiệt dung riêng bay hơi của nước là $r = 2,25 \cdot 10^6$ J/kg, nhiệt dung riêng của hơi nước là $c_V = 1,38 \cdot 10^3$ J/(kg K).

◆ Đầu tiên chúng ta hãy xác định xem bình phải được đun nóng ở nhiệt độ nào để toàn bộ nước bay hơi.

Hãy viết phương trình trạng thái của hơi nước ở điều kiện ban đầu của nước và hơi nước trong bình sẽ là $p_2 + \Delta p$. Theo điều kiện bài toán $\Delta p = \alpha \cdot \Delta T$, trong đó $\alpha = 3,7$ kPa/K. Lợi dụng điều này, chúng ta viết phương trình trạng thái của hơi nước ở nhiệt độ $T_2$:

$$p_2 V = \frac{M + m}{\mu} RT_2,$$

hoặc

$$(p_1 + \alpha \cdot \Delta T) V = \frac{M + m}{\mu} R (T_1 + \Delta T).$$

Giải (1) và (2) cùng nhau, chúng ta tìm thấy $\Delta T$:

$$\Delta T = \frac{m T p}{M T a - M p - m p} \approx 0,29 \text{ K}.$$

Vì vậy, để làm bay hơi hết nước, suud phải được đun nóng đến nhiệt độ 100,20°C. Lượng nhiệt cần thiết cho việc này có thể được tìm thấy từ phương trình cân bằng nhiệt:

$$Q = r m + c_V (M + m) \cdot \Delta T \approx 2290 \text{ Дж}.$$

A. I. Buzdin

◆ Hãy viết phương trình chuyển động của hạt tại các điểm $A$ và $B$:

$$m a_A = q E_A, \quad m a_B = q E_B.$$

Nó theo sau đó

$$\frac{a_A}{a_B} = \frac{E_A}{E_B},$$

nghĩa là tỷ lệ gia tốc hạt tại các điểm $A$ và $B$ bằng tỷ lệ của trường định hướng được tạo bởi polyring tại các điểm này. Mặt khác, từ điều kiện bài toán, chúng ta thực sự biết được mối liên hệ của trường thế tại các điểm $A$ và $B$. Thật vậy, theo định luật bảo toàn năng lượng

$$\frac{m v_A^2}{2} = q \varphi_A, \quad \frac{m v_B^2}{2} = q \varphi_B$$

(vì ở vô cực năng lượng của hạt bằng 0) và

⟦folio 50⟧

$$\frac{\varphi_A}{\varphi_B} = \frac{v_A^2}{v_B^2} = n^2.$$

Hãy thử biểu diễn mối quan hệ $E_A/E_B$ thông qua mối quan hệ đã biết $\varphi_A/\varphi_B$.

Âm lượng được chia thành nhiều phần nguyên tố với điện tích $\Delta Q$ mỗi phần ($Q$ là điện tích của toàn bộ nửa vòng). Gọi $\Delta \varphi_B$ và $\Delta E_B$ lần lượt là điện thế và cường độ của trường được tạo ra tại điểm $B$ bởi một phần nằm ở khoảng cách $Q$ tính từ điểm này (xem hình). Sau đó

$$\Delta \varphi_B = k \frac{\Delta Q}{\varphi} = k \frac{\Delta Q}{2r \cos \alpha}, \quad \Delta E_B = k \frac{\Delta Q}{\varphi^2} = k \frac{\Delta Q}{4r^2 \cos^2 \alpha}.$$

Hình chiếu của vectơ $\vec{E}_B$ lên trục hoành $x$ bằng

$$\Delta E_{Bx} = \Delta E_B \cos \alpha = k \frac{\Delta Q}{4r^2 \cos \alpha} = \frac{\Delta \varphi_B}{2r}.$$

Từ các thông điệp đối xứng, rõ ràng cường độ trường $\vec{E}_B$ tại điểm $B$ hướng dọc theo trục $x$. Do đó, giá trị $E_B$ bằng tổng các hình chiếu $\Delta E_{Bx}$ của cường độ trường được tạo bởi tất cả các phần cơ bản, nghĩa là

$$E_B = \sum \Delta E_{Bx} = \sum \frac{\Delta \varphi_B}{2r} = \frac{\varphi_B}{2r}.$$

Về giá trị của $\varphi_A$ và $E_A$ thì

$$\varphi_A = \frac{Q}{r}, \quad E_A = \frac{2Q}{\pi r^2} = \frac{2\varphi_A}{\pi r}$$

(tự mình lấy những trận đấu này).

Vì vậy, $E_A/E_B = 4\varphi_A/\pi\varphi_B$ và tỷ số gia tốc hạt tại các điểm $A$ và $B$ bằng

$$\frac{a_A}{a_B} = \frac{4}{\pi} \frac{\varphi_A}{\varphi_B} = \frac{4}{\pi} n^2.$$

V. T. Karpetyan

**Quark hàng đầu và Top Tiger**

(Xem phần đầu ở trang 41)

người ta có thể đoán được từ kết quả đo động lượng của mọi hạt tích điện. Vì sự kiện được ghi lại có liên quan đến sự phân rã của một boson $W$ đứng yên, nên tổng động lượng của tất cả các hạt trong quá trình phân rã phải bằng 0. Tuy nhiên, động lượng đo được của các hạt tích điện hóa ra lại khác 0,

từ đó rút ra kết luận về sự có mặt của neutrino.

Cách giải mã đáng tin cậy của Nibaulier về sự kiện đang được đề cập là trong quá trình va chạm của một proton với một phản proton, một phần được sinh ra gồm hai quark - quark đỉnh $t$ và phản quark tuyệt đẹp $b$. Quark đỉnh phân rã theo sơ đồ

$$t \rightarrow b + \mu^+ + v$$

(ở đây $\mu^+$ là mu-meon dương), và $b$ và $b$ cho hai chùm hạt. Bây giờ chúng ta phải chờ kết quả.

Khối lượng của quark top được ước tính tương ứng với năng lượng khoảng 40 GeV (khối lượng của một hạt nhân canxi!).*) Năng lượng này, tất nhiên, nhỏ hơn khối lượng của một con hổ con, thậm chí là một con hổ sơ sinh, nhưng trong “vườn thú hạt” quark top giữ kỷ lục.

TÔI Ở VỚI.

*) Ước tính khối lượng của quark đỉnh này có được nếu chúng ta giả sử rằng khối lượng của meson ispilon bằng khối lượng của hai $b$-quark (5 GeV + 5 GeV = 10 GeV), và khối lượng của hạt mới sinh (≈ 50 GeV) bằng khối lượng của $b$-quark và quark đỉnh.
