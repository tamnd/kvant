---
id: 1977-3-resheniya-zadach-m391-m394-f397-f402-8e5b621a
issue: kvant_1977_3
year: 1977
number: "3"
title: Lời giải bài toán M391—M394; F397—F402
rubric: zadachnik-kvanta
rubric_sub: Задачник «Кванта»
page_first: 32
page_last: 39
page_labels: 30, 31, 32, 33, 34, 36, 37
tag: X6NE
lang: vi
source: kvant_digital
extraction: vision
content_sha256: 86c15e92cfa71fb46f6bcb0bff3efc993dd9d356a4756e76a847d6f899c3d620
prompt_sha256: draft-1
translated_from: content/ru/1977/03/articles/12_resheniya-zadach-m391-m394-f397-f402-8e5b621a.md
source_content_sha256: 7d977163577679ce7e57cacdcd865c47782cecd695180e8b3e87640e6e47bf4c
translation_model: draft
translation_run: vi-draft-2026-10-31
translation_quality: draft
---

⟦folio 30⟧

Lời giải bài toán

M391. a) Trong dãy $x_0, x_1, x_2, \dots$, các số $x_0$ và $x_1$ là số tự nhiên và nhỏ hơn 1000, mỗi số còn lại có modulo bằng hiệu của hai số trước. Chứng minh rằng một trong các số $x_1, x_2, \dots, x_{1500}$ bằng 0.

b) Trong dãy $x_0, x_1, x_2, \dots$, các số $x_0$ và $x_1$ là tự nhiên và nhỏ hơn 1000, và mỗi số $x_2, x_3, \dots$ bằng giá trị nhỏ nhất của trục hoành của hiệu hiệu của hai số trước. Chứng minh rằng $x_{20}=0$.

a) Chúng ta hãy chứng minh bằng quy nạp trên mọi số tự nhiên $n$ rằng nếu trong dãy $x_0$ và $x_1$ nhỏ hơn 2$n$ thì một trong các số $x_1, x_2, \dots, x_{3n}$ bằng 0 (với điều kiện bài toán $n=500$).

Trường hợp $n=1$ rất dễ kiểm tra. Hãy để tuyên bố được chứng minh cho tất cả $n$, ít hơn một. Vì $x_0 \leqslant 2n-1$, $x_1 \leqslant 2n-1$, $x_2 \geqslant 1$, rồi $x_3 \leqslant 2n-2$ và $x_4 \leqslant 2n-3$. Nếu $x_3 < 2n-2$ và $x_4 < 2n-2$, thì mọi thứ đều tuân theo giả thuyết quy nạp. Nếu $x_3=2n-2$ thì $x_2=1$, $x_1=2n-1$, $x_0=2n-2$. Nó vẫn còn để chứng minh tuyên bố trong trường hợp này. Chúng tôi có:
$x_3=2n-2$, $x_4=2n-3$, $x_5=1$, $x_6=2n-4$, $x_7=2n-5$, $x_8=1$, ..., $x_{3k}=2n-2k$, ..., $x_{3n}=0$.

b) Đầu tiên chúng ta sắp xếp lại các số hạng $x_0, x_1$ và $x_2$ theo thứ tự giảm dần. Chuỗi kết quả có thể khác với chuỗi ban đầu chỉ theo thứ tự của ba số hạng đầu tiên (bạn hãy xem phần này). Ngoài ra, nó rất indo, giết chết: xác định thuật ngữ $x_k$, chúng tôi có tất cả các khác biệt được sử dụng để xác định thuật ngữ $x_{k-1}$, cộng với sự khác biệt giữa $x_{k-1}$ và các thuật ngữ còn lại của chuỗi (với các số thấp hơn).

Bây giờ chúng ta lưu ý rằng với mọi số nguyên $k>0$
$x_k \geqslant x_{k+1}+x_{k+2}$.

Nếu không chúng ta sẽ có
$x_{k+2}>x_k-x_{k+1}=|x_k-x_{k+1}|$, điều đó là không thể.

Giả sử rằng $x_{20} \geqslant 1$. Khi đó, tất nhiên, $x_{19} \geqslant 1$, và nhờ vào (*) chúng ta có: $x_{18} \geqslant x_{19}+x_{20} \geqslant 2$, $x_{17} \geqslant x_{18}+x_{19} \geqslant 2+1=3$, $x_{16} \geqslant x_{17}+x_{18} \geqslant 3+2=5$, ..., $x_0 \geqslant x_1+x_2 \geqslant 4181+6765=10946>10000$, trái ngược với bài toán.

S. Fomin

M392. Tùy theo liều lượng gần đúng với tốc độ không đổi đó, các quyết định sẽ được đưa ra. Lúc đầu chúng không nằm trên cùng một đường thẳng. Chứng minh rằng chúng có thể nằm trên cùng một đường không quá hai lần.

Hãy để chúng tôi trình bày hai lời giải trong số bài toán này. Đầu tiên (hình học) sử dụng một kỹ thuật điển hình của vật lý: chuyển sang hệ thống báo cáo lái xe; cái thứ hai (phân tích) có thể được viết ngắn gọn bằng cách sử dụng “tích giả vô hướng” của vectơ.

I. Ta sẽ viết điều kiện điểm $P, Q, R$ thẳng hàng như sau: $R \in (PQ)$ (tại $P \neq Q$).

Chúng ta hãy chuyển sang hệ tọa độ được liên kết với một trong lời giải. Khi đó bài toán được rút gọn thành như sau: một điểm cố định $A$ được cho trên mặt phẳng; Chứng minh rằng nếu các điểm $P$ và $Q$ chuyển động trơn tru và đều thì đúng $A \in (PQ)$ chỉ có thể xảy ra không quá hai lần (nếu biết tại thời điểm ban đầu $t=0$ sẽ không xảy ra).

Giả sử tại một thời điểm nào đó $t_1$ lời giải $P$ và $Q$ ở các điểm $B$ và $C$ sao cho $A \in (BC)$. Hãy giới thiệu một “hư cấu” khác lời giải $Q'$: $Q'$ nằm ở điểm $B$ tại $t=t_1$ và di chuyển song song với đường đi lời giải $Q$ sao cho luôn là $A \in (QQ')$ (Hình 1, a). Rõ ràng là điều kiện $A \in (PQ), A \in (PQ')$ và $Q' \in (AP)$ là tương đương *). Rõ ràng, $Q'$ chuyển động đều. Do đó, đường thẳng $PQ'$ giữ nguyên hướng - nó di chuyển song song với chính nó - và chỉ có thể đi qua điểm $A$ tại một thời điểm $t_2$ (khác với $t_1$) (Hình 1, o). (Khả năng các điểm $P$ và $Q'$ luôn trùng khớp hoặc chúng di chuyển dọc theo đường thẳng $AB$ bị loại trừ khỏi các điều kiện ban đầu.)

⟦folio 31⟧

Không khó để đưa ra ví dụ cho thấy ba chữ lời giải thực có thể xuất hiện trên cùng một dòng hai lần, một lần hoặc không xuất hiện lần nào. Trước khi chuyển sang lời giải II, chúng ta hãy lưu ý mà không cần bằng chứng về một sự thật mà bài toán của chúng ta có thể dễ dàng theo dõi. Nếu hai điểm $P$ và $Q$ di chuyển đồng đều dọc theo hai đường thẳng, thì tất cả các đường thẳng $PQ$ đều đi qua một điểm hoặc song song với một hướng, hoặc (và đây là trường hợp chung) - chạm vào một parabol - “đường bao” của họ đường này (Hình 2). Rõ ràng là qua mỗi điểm $A$ của mặt phẳng có nhiều nhất hai đường thẳng thuộc họ này.

II. Hãy để chúng tôi giới thiệu hệ tọa độ $Oxy$. Điều kiện hai vectơ $v$ và $w$ có ​​tọa độ $(v_x; v_y)$ và $(w_x; w_y)$ thẳng hàng (song song với một hướng) rõ ràng có thể được viết như sau: $v_x w_y = v_y w_x$. Hãy giới thiệu ký hiệu

$$[v, w] = v_x w_y - v_y w_x.$$ (1)

Một hàm số của một cặp vectơ $(v, w) \rightarrow [v, w]$ có, rất dễ xác minh, thuộc tính sau:

$$[\lambda v, w] = [v, \lambda w] = \lambda [v, w];$$
$$[v + w, u] = [v, u] + [w, u],$$
$$[u, v + w] = [u, v] + [u, w]$$ (2)

với mọi vectơ $u, v, w$ và mọi số $\lambda$. Như đã nêu, $[v, w] = 0$ nếu và chỉ nếu $v$ và $w$ thẳng hàng. (Giá trị $[v, w]$ có ý nghĩa hình học đơn giản: mô hình của nó bằng diện tích của hình bình hành, các đường thẳng của nó được biểu thị bằng vectơ $v$ và $w$, và dấu phụ thuộc vào “hướng” của cặp $(v, w)$, với $[v, w] = -[w, v]$ (Hình 3); nhưng chúng ta sẽ không cần những tính chất này.)

Bây giờ chúng ta hãy chuyển trực tiếp đến lời giải bài toán. Để $P, Q$ và $R$ chuyển động thẳng và đều. Sau đó

$$\vec{RP} = \vec{a} + t \vec{v}, \quad \vec{RQ} = \vec{b} + t \vec{w},$$ (3)

trong đó $t$ là thời gian, $\vec{a}, \vec{b}, \vec{v}, \vec{w}$ là các vectơ độc lập với $t$. Không khó để thu được các công thức dạng (3), sử dụng thực tế là nếu một điểm $M$ nào đó chuyển động với tốc độ $\vec{u}$ thì $\vec{OM} = \vec{OM}_0 + t \vec{u}$, trong đó $\vec{M}_0$ là vị trí của $M$ tại $t = 0$, $O$ là một điểm cố định của mặt phẳng. Xét (1) - (3), điều kiện $R \in (PQ)$ có thể viết như sau:

$$[v, w] t^2 + ([a, w] + [b, v]) t + [a, b] = 0.$$ (4)

Chúng ta đã thu được phương trình bậc hai cho $t$. Mặc dù một số hệ số của nó có thể chuyển về 0, nhưng với $t = 0$, như đã nêu ở điều kiện (4), nó không thỏa mãn nên (4) không giống nhau. Do đó, $R \in (PQ)$ có ​​nhiều nhất hai giá trị $t$.

N. Vasiliev

M393. Tìm số tiền

$$\varphi(0) + \varphi\left(\frac{1}{n}\right) +$$
$$+ \varphi\left(\frac{2}{n}\right) + \dots + \varphi(1),$$

nếu $\varphi(x) = \frac{4^x}{4^x + 2}$.

Chúng ta sẽ giải bài toán tổng quát hơn, cụ thể là khi $\varphi(x) = \frac{a^{2x+k}}{a^{2x}+a}$, trong đó $k$ là số thực bất kỳ và $a > 0$ (đặt $k = 0$, $a = 2$, chúng ta nhận được đáp số bài toán M393).

Hãy tìm biểu thức cho $\varphi(1-x)$:

$$\varphi(1-x) = \frac{a^{-2x+k+2}}{a^{-2x+2}+a} = \frac{a^{k+1}}{a^{2x}+a}.$$

⟦folio 32⟧

Thêm $\varphi(1-x)$ và $\varphi(x)$, chúng ta nhận được:

$$\varphi(x) + \varphi(1-x) = \frac{a^{2x+k} + a^{k+1}}{a^{2x} + a} = a^k.$$

Đặt tổng cần thiết bằng $S$. Sau đó

$$S = \varphi(0) + \varphi\left(\frac{1}{n}\right) + \ldots + \varphi\left(\frac{n-1}{n}\right) + \varphi(1),$$

$$S = \varphi(1) + \varphi\left(\frac{n-1}{n}\right) + \ldots + \varphi\left(\frac{1}{n}\right) + \varphi(0).$$

Cộng hai đẳng thức này và tính đến điều đó

$$\varphi(0) + \varphi(1) = \varphi\left(\frac{1}{n}\right) + \varphi\left(\frac{n-1}{n}\right) = \ldots =$$

$$= \varphi(x) + \varphi(1-x) = a^k,$$

chúng tôi nhận được

$$2S = (n+1)a^k,$$

nghĩa là, $S = \frac{1}{2}(n+1)a^k$.

Vì vậy, đáp số đến bài toán M393 như sau:

$$S = \frac{1}{2}(n+1).$$

S. Berkolaiko

**M394. a) Các vectơ $a, b, c, d$ cho trên mặt phẳng, tổng của chúng bằng 0. Chứng minh bất đẳng thức:**

b) cho bốn số và c) bốn vectơ trong không gian ba chiều, tổng của chúng bằng 0.

**Hình 5.**

**Hình 6.**

Bây giờ chúng ta sẽ chỉ giải bài toán a) (tại Olympic, bài này được cung cấp cho học sinh lớp 9-10); lời giải và bài toán b) và c) sẽ là chủ đề của một ghi chú mà chúng tôi sẽ đăng trên một trong những số tiếp theo của tạp chí.

Đặt các vectơ $\vec{MN} = \vec{a}, \vec{NP} = \vec{b}, \vec{PQ} = \vec{c}, \vec{QM} = \vec{d}$ lần lượt sang một bên, chúng ta thu được một đường đứt nét khép kín (kể từ $\vec{a} + \vec{b} + \vec{c} + \vec{d} = 0$). Bằng cách thay đổi thứ tự của các vectơ $\vec{a}, \vec{b}, \vec{c}, \vec{d}$, người ta có thể thu được một số đường đứt nét như vậy. Hãy để chúng tôi chỉ ra rằng trong số những đường đứt đoạn này có đường tự cắt. Để làm điều này, hãy lấy một trong những dòng bị hỏng của chúng tôi. Nếu một trong các đỉnh của nó, chẳng hạn như $Q$, nằm bên trong tam giác $MNP$ được tạo bởi ba đỉnh (Hình 4, a), thì chúng ta đặt vectơ $\vec{QQ'} = \vec{MN}$ sang một bên. Vì trong trường hợp này $\vec{Q}'N = \vec{QM}$, đường gãy $MNPQ$ có thể được thay thế bằng đường gãy tự cắt $NPQQ'$ (Hình 4, b). Nếu $MNPQ$ là một đường gãy lồi thì trước tiên chúng ta thực hiện xây dựng như trong Hình 5.

Vì vậy, giả sử $\vec{MN} = \vec{a}, \vec{NP} = \vec{b}, \vec{PQ} = \vec{c}, \vec{QM} = \vec{d}$ và các đoạn $NP$ và $QM$ có ​​một điểm chung $R$ (Hình 6). Sau đó $|MR| + |PR| \geq |PM|, |NR| + |QR| \geq |QN|$, từ đó $|MR| + |PR| + |NR| + |QR| \geq |PM| + |QN|$. Nhưng $|PM| = |PQ + QM| = |c + d|,$

$$|QN| = |QM + MN| = |a + d|,$$

một $|MR| + |PR| + |NR| + |QR| = |QM| + |NP| = |b + d|$. Kể từ đây,

$$|b| + |d| \geq |a + d| + |c + d|.$$

(1)

Ngoài ra, điều rất quan trọng là $|a| + |c| \geq |a + c|$ và $|a + c| = |b + d|$ (xem Hình 6); Đó là lý do tại sao

$$|a| + |c| \geq |b + d|.$$

(2)

Cộng các bất đẳng thức (1) và (2), chúng ta thu được điều cần tìm.

Yu. nonin

⟦folio 33⟧

F397. Có bản thảo sau đây của một lematic annaram. Mặt trên của tấm phẳng lớn được nung ở nhiệt độ không đổi 0°C và mặt dưới được nung ở nhiệt độ 100°C. Nhà phát minh tuyên bố rằng bằng cách nhúng nhựa vào, chúng ta sẽ bay lên không trung giống như một chiếc khinh khí cầu. Giải thích, do đó. Hãy ước tính bậc độ lớn của lực nâng của một đĩa cây thuốc phiện có diện tích 1 m2 ở nhiệt độ không khí 20°C.

Các phân tử không khí tới trên tấm có tốc độ bình phương trung bình căn bằng $\bar{v}_{\text{cp.кв.}} = \sqrt{\frac{3kT}{m}}$, trong đó $T$ là nhiệt độ không khí, $m$ là khối lượng của các phân tử. Giá trị tuyệt đối trung bình của vận tốc thiết kế của các phân tử trên trục $OY$, vuông góc với bề mặt của tấm, bằng $\bar{v}_y \approx \frac{\bar{v}_{\text{cp.кв.}}}{\sqrt{3}} = \sqrt{\frac{kT}{m}}$.

Khi va chạm với một tấm, “nhiệt độ” của các phân tử sẽ bằng nhiệt độ của tấm. Điều này có nghĩa là sau khi phản xạ từ bề mặt trên

$$\bar{v}'_y = \sqrt{\frac{kT_1}{m}},$$

và sau khi phản xạ từ bề mặt trên

$$\bar{v}'_y = \sqrt{\frac{kT_2}{m}}.$$

Kết quả là hình chiếu $p_y$ của động lượng của các phân tử rơi xuống bề mặt dưới của tấm thay đổi khi va chạm bởi các giá trị sau:

$$\Delta p'_y = m \left( \sqrt{\frac{kT}{m}} + \sqrt{\frac{kT_1}{m}} \right),$$

và một phân tử rơi trên bề mặt trên - theo giá trị

$$\Delta p''_y = m \left( \sqrt{\frac{kT}{m}} + \sqrt{\frac{kT_2}{m}} \right).$$

Trong thời gian $\Delta t$, các phân tử nằm cách tấm một khoảng bằng $\bar{v}_y \Delta t$ sẽ chạm tới từng bề mặt. Số lượng phân tử này là $N = nv_y s \Delta t$, trong đó $n$ là số lượng phân tử trên một đơn vị thể tích, $s$ là diện tích của tấm.

Theo định luật thứ hai và thứ ba của Newton, các lực tác dụng lên tấm theo hướng trên có độ lớn tuyệt đối bằng sự thay đổi hình chiếu của các xung phân tử trong một đơn vị thời gian. Một lực hướng lên tác dụng lên mặt dưới của tấm (Hình 7)

$$|\vec{F}_1| = \frac{N \Delta p'_y}{\Delta t} = m n \bar{v}_y s \left( \sqrt{\frac{kT_1}{m}} + \sqrt{\frac{kT}{m}} \right),$$

và trên cùng - một lực hướng xuống

$$|\vec{F}_2| = \frac{N \Delta p''_y}{\Delta t} = m n \bar{v}_y s \left( \sqrt{\frac{kT_2}{m}} + \sqrt{\frac{kT}{m}} \right).$$

Vì $T_1 > T_2$, nên đường dẫn $\vec{R}$ bằng nhau của các lực $\vec{F}_1$ và $\vec{F}_2$ hướng lên trên và bằng nhau về giá trị tuyệt đối

$$|\vec{R}| = |\vec{F}_1| - |\vec{F}_2| = m n \bar{v}_y s \left( \sqrt{\frac{kT_1}{m}} - \sqrt{\frac{kT_2}{m}} \right) = nsk \sqrt{T} \left( \sqrt{T_1} - \sqrt{T_2} \right).$$

Số lượng phân tử chứa trong thể tích $V$ của không khí ở áp suất $p$ và nhiệt độ $T$ bằng $N_V = v \cdot N_A$, trong đó $v$ là số lượng phân tử không khí trong thể tích $V$, $N_A$ là số Abogadro. Nhưng $v = \frac{M}{\mu} = \frac{pV}{RT}$. Vậy số phân tử trên một đơn vị thể tích

$$n = \frac{p}{RT} N_A.$$

⟦folio 34⟧

Như vậy,

$$|\vec{R}| = \frac{pN_A sk}{RT} \sqrt{T_1} - \sqrt{T_2} = \frac{ps}{\sqrt{T}} (\sqrt{T_1} - \sqrt{T_2}).$$

Thay thế dữ liệu vào các điều kiện số lượng trong biểu thức này (đếm $p = 10^5 \text{h}/\text{m}^2$), chúng ta thu được

$$|\vec{R}| \approx 1,5 \cdot 10^4 \text{ h}.$$

F398. Đã xảy ra lỗi khi kết nối đồng hồ bảy đèn với hai công tắc. Kết quả là khi đóng một trong các công tắc, cả ba đèn đều cháy ở cường độ không hoàn toàn. Khi đóng, những công tắc khác vẫn đang cháy) và đạt được hiệu quả tương tự bằng cách đóng cả hai công tắc cùng một lúc. Khi mở công tắc thì cả 3 đèn đều không sáng. Vẽ sơ đồ lắp đặt đã hoàn thành và giải thích các tác động đạt được.

F399. Ba quả cầu kim loại nhỏ giống hệt nhau đặt trong chân không ở các đỉnh của một tam giác đều. Các quả bóng được kết nối lần lượt với một dây dẫn từ xa, được đặt và duy trì không đổi. Kết quả là quả bóng thứ nhất có điện tích $Q_1$, và quả bóng thứ hai có điện tích $Q_2$. Xác định điện tích của quả bóng thứ ba.

Mạch chuyển đổi đèn được hiển thị trong Hình 8. Khi phím $K_1$ đóng và phím $K_2$ mở, cả ba đèn được bật nối tiếp và do đó chúng cháy với nhiệt không hoàn toàn. Khi cả hai công tắc được đóng đồng thời, đèn $J_1$ bật sáng và đèn $J_2$ và $J_3$ được mắc song song với một đoạn mạch có rất ít điện trở. Ví dụ, không có đủ trên chúng và đèn không sáng. Khi một phím $K_2$ được đóng, chỉ có đèn $J_1$ bật.

Hình 8.

Khi mỗi quả bóng được nối với một dây dẫn ở xa, điện thế F được giữ không đổi thì điện thế của quả bóng bằng F.

Điện tích $Q_1$ xuất hiện trên quả bóng đầu tiên bằng

$$Q_1 = C\varphi,$$

trong đó $C$ là sức chứa của quả bóng.

Điện thế Ф của quả bóng thứ hai bao gồm điện thế trường được tạo ra bởi điện tích $Q_1$ ở khoảng cách $l$ tính từ quả bóng thứ nhất ($\varphi_1 = \frac{Q_1}{l}$) và điện thế của trường “riêng” của điện tích $Q_2$ ($\varphi_2 = \frac{Q_2}{C}$):

$$\varphi = \varphi_1 + \varphi_2 = \frac{Q_1}{l} + \frac{Q_2}{C}.$$

Thế năng Ф của quả bóng thứ ba bằng

$$\varphi = \frac{Q_1}{l} + \frac{Q_2}{l} + \frac{Q_3}{C},$$

trong đó $\frac{Q_1}{l}$, $\frac{Q_2}{l}$ là thế năng tương ứng của trường điện tích $Q_1$ và $Q_2$ ở khoảng cách $l$ tính từ chúng, $\frac{Q_3}{C}$ là thế năng của trường điện tích “riêng” $Q_3$.

Từ đẳng thức (2), sử dụng đẳng thức (1), ta tìm được $l$:

$$l = \frac{Q_1 C}{Q_1 - Q_2}.$$

Thay biểu thức này cho $l$ vào đẳng thức (3), chúng ta tìm thấy $Q_3$:

$$Q_3 = C \left[ \varphi - \frac{Q_1 + Q_2}{l} \right] = \frac{Q_2^2}{Q_1}.$$

⟦folio 36⟧

F402. Một thấu kính phân kì có tiêu cự $F = -0,6$ m được đặt sao cho một tiêu điểm của nó trùng với vạch trên gương trong. Tiêu cự $F'$ của gương là bao nhiêu nếu biết hệ cho ảnh thật của một vật đặt cách thấu kính một khoảng bất kỳ? Ảnh được tạo ra bởi các tia sáng truyền qua thấu kính lần thứ hai sau khi phản xạ từ gương.

Ở đâu
$$\frac{I_2}{I_1} = \frac{R}{r_2}.$$

Mặt khác, $\varphi_A = \varphi_C + I_1 r_G$ ($r_G$ là điện trở của điện kế) và $\varphi_B = \varphi_C + I_2 r_1$. Vì thế
$$\varphi_C + I_1 r_G = \varphi_C + I_2 r_1,$$

Ở đâu
$$\frac{I_1}{I_2} = \frac{r_G}{r_1}.$$

So sánh biểu thức (1) và (2), ta thu được:
$$\frac{R}{r_2} = \frac{r_G}{r_1},$$

hoặc
$$r_G = \frac{r_1}{r_2} R.$$

Biết các điện trở $r_1$, $r_2$, $R$, ta có thể tìm được điện trở của điện kế $r_G$.

◆
Thấu kính phân kỳ luôn cho ảnh thật nhỏ nhất của nguồn. Do đó, để hệ thống tạo ra một ảnh hợp lệ, ảnh trung gian thu được sau khi tia phản xạ từ gương phải là nguồn tối thiểu cho thấu kính, tức là nó phải ở bên phải thấu kính.

Trên thực tế, từ công thức tính thấu kính phân kỳ trong trường hợp nguồn sáng tối thiểu
$$-\frac{1}{d} + \frac{1}{f} = -\frac{1}{F}$$

nó theo sau đó
$$f = \frac{dF}{F - d}.$$

(Nhắc lại $d$ là khoảng cách từ thấu kính đến nguồn, $f$ là khoảng cách từ thấu kính đến ảnh, $F$ là tiêu cự của thấu kính.) Từ (1) cho thấy rõ rằng $f \geq 0$ nếu $d$ dương và không vượt quá $F$.

Do đó, ảnh trung gian $S_2$ của nguồn sau gương (Hình 14) phải đặt ở bên phải gương một khoảng $f_2$ sao cho
$$F \leq f_2 \leq 2F.$$

Nguồn của gương là ảnh trung gian $S_1$ - ảnh cực tiểu của nguồn $S$, được thấu kính cho sau lần khúc xạ đầu tiên của tia (xem Hình 14). Từ công thức thấu kính cho trường hợp này
$$\frac{1}{d_1} - \frac{1}{f_1} = -\frac{1}{F}$$

- chúng tôi tìm thấy
$$f_1 = \frac{d_1 F}{d_1 + F}.$$

⟦folio 37⟧

Khoảng cách $d_1$ từ nguồn đến ống kính có thể thay đổi từ 0 đến $\infty$. Trong trường hợp này, như sau từ công thức (3), $f_1$ thay đổi từ 0 thành $F$. Khoảng cách $d_2 = F + f_1$ từ ảnh $S_1$ đến gương thay đổi từ $F$ thành $2F$. Hãy nhớ lại rằng hình ảnh này đóng vai trò là nguồn cho gương. Vì vậy, chúng ta cần tìm ở tiêu cự $F'$ của gương ảnh của một nguồn nằm cách gương một khoảng $d_2$ sao cho

$$F \leqslant d_2 \leqslant 2F,$$

(4a)

thu được ở khoảng cách $f_2$ tính từ gương sao cho

$$F \leqslant f_2 \leqslant 2F.$$

(46)

Từ công thức gương -

$$\frac{1}{d_2} + \frac{1}{f_2} = \frac{1}{F'}$$

- nó theo sau đó

$$\frac{1}{f_2} = \frac{1}{F'} - \frac{1}{d_2}.$$

(5)

Theo điều kiện (46)

$$\frac{1}{2F} \leqslant \frac{1}{f_2} \leqslant \frac{1}{F},$$

vậy phần bên phải của đẳng thức (5) nằm trong

$$\frac{1}{2F} \leqslant \frac{1}{F'} - \frac{1}{d_2} \leqslant \frac{1}{F}.$$

Kể từ đây,

$$\frac{1}{2F} + \frac{1}{d_2} \leqslant \frac{1}{F'} \leqslant \frac{1}{F} + \frac{1}{d_2}.$$

Bất đẳng thức thu được phải đúng với mọi điều kiện tùy ý $d_2$ thỏa mãn (4a). Theo điều kiện này

$$\frac{1}{2F} \leqslant \frac{1}{d_2} \leqslant \frac{1}{F},$$

nên tiêu cự $F'$ của gương phải sao cho điều kiện

$$\frac{1}{2F} + \frac{1}{F} \leqslant \frac{1}{F'} \leqslant \frac{1}{F} + \frac{1}{2F}.$$

Do đó, $\frac{1}{F'} = \frac{3}{2F}$, hoặc

$$F' = \frac{2}{3} F = 0,4 \text{ m}.$$

I. Slovodetsky
