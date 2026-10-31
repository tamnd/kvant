---
id: 1979-1-resheniya-zadach-m494-m496-m499-f508-f511-7eaa4962
issue: kvant_1979_1
year: 1979
number: "1"
title: Lời giải bài toán M494, M496—M499; F508—F511
rubric: zadachnik-kvanta
rubric_sub: Задачник «Кванта»
page_first: 32
page_last: 37
page_labels: 30, 31, 33, 34, 35
tag: OD2N
lang: vi
source: kvant_digital
extraction: vision
content_sha256: 9b0de4b4c5766e3f897322dc6b39decc4a8eae9cb8e446957e87047eed04d756
prompt_sha256: draft-1
translated_from: content/ru/1979/01/articles/11_resheniya-zadach-m494-m496-m499-f508-f511-7eaa4962.md
source_content_sha256: 63123778ed4fcb89c63eb8d32ce163873f97a1ac125270c4d2f011a315af6029
translation_model: draft
translation_run: vi-draft-2026-10-31
translation_quality: draft
---

⟦folio 30⟧

Lời giải bài toán
M494, M496—M499; F508—F511

M494. Bên trong hình vuông ở cạnh 1 có $n^2$ điểm. Chứng minh rằng tồn tại một đường đứt nét chứa các điểm có độ dài nhỏ hơn a) 3n; b) 2n.

Ý tưởng xây dựng một đường gãy rõ ràng từ Hình 1: chúng ta chia hình vuông thành $n$ sọc dọc và sau đó thảo luận về tất cả các điểm theo kiểu “rắn”: chúng ta chuyển sọc đầu tiên bên trái từ trên cùng của chế độ xem, sọc tiếp theo từ dưới lên, v.v. Tổng độ dài của các liên kết của đường đứt nét không lớn hơn tổng độ dài hình chiếu của chúng lên các cạnh dọc và ngang của hình vuông. Tổng các hình chiếu dọc, dễ dàng nhận thấy, không vượt quá $n$, và tổng các hình chiếu ngang có thể được ước tính như sau. Hình chiếu ngang của liên kết không giao nhau với ranh giới của các dải không vượt quá $1/n$ và hình chiếu của liên kết giao nhau với $k$ của các đoạn dọc của ranh giới của dải không vượt quá $(k+1)/n = k/n+1/n$. Tổng số ranh giới dọc của các dải là $n-1$ nên tổng của tất cả các hình chiếu ngang $n^2-1$ không lớn hơn

$(n^2-1)/n+(n-1)/n=n+1-2/n \leq n+1$.

Do đó, đối với độ dài của đường đứt nét, chúng ta thu được ước tính $2n+1$.

Hình 1. Hình 2. Hình 3.

Vấn đề a) lời giải, và để chứng minh 6), chúng ta cần cải thiện ước lượng lên 1.

Để làm được điều này, chúng ta cần thay đổi thiết kế của mình. Hãy chia hình vuông thành $n$ sọc có chiều rộng khác nhau $(h_1, h_2, \dots, h_n)$ sao cho mỗi dải có chính xác $n$ điểm (“điểm” viền có thể được gán cho cả bên trái và bên phải). Chúng ta hãy kết nối tất cả các điểm trên của sọc và tất cả các điểm dưới bằng các đoạn có màu đỏ và xanh xen kẽ (Hình 2). Chúng ta có thể chọn điểm bắt đầu của đường rắn để nó đi dọc theo tất cả các đoạn màu xanh hoặc dọc theo tất cả các đoạn màu đỏ. Tổng các hình chiếu ngang $2(n-1)$ của các đoạn màu đỏ và xanh của đường đứt nét với nhau không quá 2; nếu chúng ta chọn màu mà tổng này nhỏ hơn 1, chúng ta sẽ thu được ước tính cho tổng của tất cả các hình chiếu ngang

$(n-1)(h_1+h_2+\dots+h_n)+1 \leq n$.

Tổng các hình chiếu dọc như trước không quá $n$.

Vì vậy, chúng tôi đã xây dựng một đường gãy có độ dài không lớn hơn $2n$, chúng tôi quyết định là 6).

Một ví dụ về cách sắp xếp các điểm “dày đặc” tại các đỉnh của một mạng tam giác (Hình 3; đối với $n$ lớn, để bình phương các điểm $1 \times 1$ $n^2$, bạn cần lấy độ dài cạnh của tam giác bằng khoảng $\sqrt{2/\sqrt{3}}/n$) cho thấy rằng hằng số $2$ trong các điều kiện chỉ định rõ ràng NOTLZ (thêm nữa cho lớn $n$) được thay thế bằng một số nhỏ hơn $\sqrt{2/\sqrt{3}}$.

N. Vasiliev, A. Tarmakovsky

⟦folio 31⟧

M496. Số có sáu chữ số nào lớn hơn: số có thể biểu diễn dưới dạng tích của hai số có ba chữ số hay số không thể biểu diễn?

Chỉ có 900 số có ba chữ số (từ 100 đến 999). Do đó, chỉ có $\frac{900 \cdot 899}{2} + 900 = \frac{900 \cdot 901}{2} = 405450$ cặp số có ba chữ số (không nhất thiết phải khác nhau).

Vì vậy, không có nhiều hơn số có sáu chữ số này, được biểu diễn bằng tích của hai số có ba chữ số. Và có tổng cộng 900.000 số có sáu chữ số. Điều này có nghĩa là hơn một nửa trong số chúng không thể được biểu diễn dưới dạng tích của hai số có ba chữ số.

N. Vasiliev

M497. Trên các cạnh BC, CA, AB của tam giác nhọn ABC lấy các điểm tùy ý A₁, B₁, C₁; Các vòng tròn được xây dựng trên các đoạn AA₁, BB₁ và CC₁ như trên đường kính. Chứng minh rằng ba dây chung của các cặp đường tròn này cắt nhau tại giao điểm các đường cao của tam giác ABC.

Lời giải trong số này bài toán sử dụng định lý tốt hơn sau:

Nếu ba đường tròn giao nhau theo cặp thì các dây chung của mỗi cặp đường tròn (hoặc phần mở rộng của chúng) đi qua một điểm hoặc song song (Hình 4).

Đầu tiên chúng ta sẽ giải bài toán và sau đó đưa ra sơ đồ chứng minh định lý.

Chúng ta hãy dựng các đoạn AB, AA₁ và BB₁ tương ứng như trên các đường kính của đường tròn OₑB, OₑA₁ và OₑB₁. Hợp âm chung của các đường tròn OₑB và OₑA₁ rõ ràng là đường cao AHₐ của tam giác ABC (vì $\widehat{AH}_A B = \widehat{AH}_A A_1 = 90^\circ$; Hình 5). Tương tự, dây chung các đường tròn OₑB và BHₐ của tam giác ABC.

Người ta chứng minh tương tự rằng các dây chung của hai cặp đường tròn khác: OₑA₁ và OₑC₁, OₑC₁ và OₑB₁ đi qua giao điểm các đường cao của tam giác ABC. Bài toán lời giải.

Việc còn lại là chứng minh định lý.

Chúng ta hãy dựng ba hình cầu có tâm trong mặt phẳng của các đường tròn trên các đường tròn này (nằm trong mặt phẳng ngang) và nhìn chúng từ trên xuống. Chúng ta sẽ thấy ba vòng tròn mà các hình cầu giao nhau (hình chiếu của chúng trên mặt phẳng nằm ngang là ba dây cung của chúng ta) và điểm giao nhau của chúng (hình chiếu của nó là điểm giao nhau mong muốn của các dây cung).

V. Gutemacher

M498. Với mọi số tự nhiên n ≥ 3 chỉ ra k nhỏ nhất sao cho n điểm bất kỳ trên mặt phẳng, không có ba điểm nào cùng thuộc một đường thẳng cho trước, có thể cách nhau bởi k đường thẳng.

Nhiều người trong số những người đã gửi cho chúng tôi lời giải điều này bài toán đã nhớ lại sự thật này (không khó để chứng minh bằng quy nạp):

k đường thẳng chia mặt phẳng thành không quá $\frac{k(k+1)}{2} + 1$ phần (với k đường thẳng ở vị trí tổng quát sẽ có chính xác $\frac{k(k+1)}{2} + 1$).

⟦folio 33⟧

F508. Thời kỳ Sao Thủy quay quanh Mặt trời là 88 ngày Trái đất và quanh trục của nó - 59 ngày Trái đất. Độ dài ngày và đêm trên sao Thủy là bao nhiêu?

Chúng ta hãy biểu thị độ dài một ngày trên Sao Thủy bằng $x$ (Ngày Trái Đất). Trong một ngày trên trái đất, Sao Thủy sẽ quay quanh trục của nó một góc $\frac{360^\circ}{59}$ và sẽ dịch chuyển dọc theo quỹ đạo của nó (cùng hướng) một góc $\frac{360^\circ}{88}$. Sự khác biệt $\frac{360^\circ}{59} - \frac{360^\circ}{88}$ thể hiện góc mà Sao Thủy sẽ quay so với Mặt trời trong một ngày Trái đất:

$$\frac{360^\circ}{59} - \frac{360^\circ}{88} = \frac{360^\circ}{x}.$$

Từ đây

$$x \approx 179$$

Một ngày trên sao Thủy xấp xỉ bằng hai năm sao Thủy.

Do đó, ngày và giờ của sao Thủy có độ dài xấp xỉ bằng năm của nó.

E. Levitan

F509. Hồ có dòng chảy chỉ giữ được lớp nước trên cùng. Một chiếc bè với annapagura bắt tai trôi xuôi dòng. Ở phía dưới, phía trước dòng điện, có một nguồn âm thanh bất động. Một người quan sát trên bè phát hiện ra rằng âm thanh truyền tới bè theo hướng tạo một góc $\beta$ với phương thẳng đứng. Góc từ phương thẳng đứng đến phương thật của nguồn âm là bao nhiêu? Tốc độ của dòng điện là $u$, tốc độ âm thanh trong nước là $v$. Độ dày của lớp chuyển động nhỏ hơn nhiều so với độ dày của đại dương.

Hình 8.

Hình 9.

Tại ranh giới $AB$ của lớp chuyển động, âm thanh bằng cách nào đó thay đổi hướng - nó bị khúc xạ (Hình 8). Âm thanh truyền tới bè $P$ một góc $\beta$ bằng góc khúc xạ. Vì lớp mỏng nên chúng ta có thể lấy góc $CPS$ bằng góc tới $\alpha$. Như vậy, bài toán với việc suy ra định luật khúc xạ sóng âm tại ranh giới của môi trường bất động và chuyển động.

Gọi $CO$ là hướng truyền âm thanh trong môi trường bất động và $KO$ là vị trí của bề mặt sóng (mặt sóng) tại một thời điểm nào đó $t$ (Hình 9). Sau khoảng thời gian $\Delta t$, mặt sóng sẽ chiếm vị trí $K'O'$. Theo cách tương tự, chúng ta hãy biểu thị bằng $OD$ hướng truyền âm thanh ở lớp nước trên (theo quan điểm quan sát được trên bè) và bằng $OL$ và $O'L'$ vị trí của mặt trước sóng tại các thời điểm $t$ và $t + \Delta t$.

Trong thời gian $\Delta t$, mặt sóng $KO$ di chuyển đến một khoảng cách $|MO'| = |v| \Delta t (MO' \perp KO)$, và điểm giao nhau của mặt trước với bề mặt của phương tiện truyền thông tách biệt di chuyển đến một khoảng cách $|OO'| = \frac{|v| \Delta t}{\sin \alpha}$. Tương tự, độ dịch chuyển của điểm chuyển động của mặt sóng $OL$ với giao diện so với tần số sóng quan sát được ($\alpha \rightarrow \pi/2$, $\sin \alpha \rightarrow 1$) thì góc khúc xạ không vượt quá giá trị

$$\beta \rightarrow \arcsin \frac{1}{1 + |u|/|v|}$$

Hóa ra định luật khúc xạ tương tự cũng đúng khi chiếc bè đã thổi bụi qua nguồn âm. Đúng, trong trường hợp này góc khúc xạ $\beta$ lớn hơn góc tới $\alpha$ nên khúc xạ chỉ xảy ra ở các góc

⟦folio 34⟧

Từ chối

$$\alpha < \alpha_{\text{np}} = \arcsin \frac{1}{1 + |\vec{u}| / |\vec{v}|}.$$

Ở các góc lớn, sự phản xạ hoàn toàn âm thanh từ lớp chuyển động xảy ra.

G. Komkin

F510. Một lưới cao su chắc chắn được căng trên quả bóng cao su, các sợi của chúng được kéo dọc theo kinh tuyến của quả bóng. Quả bóng sẽ có hình dạng như thế nào nếu có áp suất tác dụng lên nó?

Chúng ta hãy xem xét một trong các sợi chỉ và chọn một đoạn nhỏ có độ dài $l$ trên đó (Hình 10). Chúng ta biểu thị lực căng của sợi chỉ bằng $\vec{T}$. Tổng hợp $\vec{Q}$ của lực căng tác dụng lên vùng được chọn có giá trị tuyệt đối bằng $2|\vec{T}| \sin \frac{\alpha}{2}$.

Tại $l \ll R$ ($R$ là bán kính cong của sợi tại một vị trí nhất định) $\alpha = \frac{l}{R} \ll 1$, do đó chúng ta có thể giả sử rằng

$$\sin \frac{\alpha}{2} = \frac{\alpha}{2}, \quad |\vec{Q}| = \frac{l}{R} |\vec{T}|.$$

Vì phần được chọn của sợi chỉ ở trạng thái cân bằng nên tổng các lực tác dụng lên nó bằng 0. Điều này có nghĩa là một lực tác dụng lên sợi dây từ phía bên của quả bóng

$$\vec{F} = -\vec{Q}.$$

Theo định luật III Newton, một lực tác dụng lên quả bóng từ phía của sợi chỉ

$$-\vec{F} = -(-\vec{Q}) = \vec{Q},$$

hướng vào tâm quả bóng.

Cùng một số sợi $N$ đi qua bất kỳ đường song song nào của quả bóng. Đối với một đường song song có bán kính $r = R \cos \varphi$ ($\varphi$ là góc tạo bởi bán kính của quả bóng vẽ về đường song song với mặt phẳng xích đạo) bằng $2\pi r = 2\pi R \cos \varphi$. Do đó, số sợi đi qua một phần vỏ bi có diện tích $l \times l$

$$n = \frac{N}{2\pi R \cos \varphi} l.$$

Khi đó áp suất tác dụng lên vỏ bằng

$$p = n \frac{|\vec{Q}|}{l^2} = \frac{N |\vec{T}|}{2\pi R^2 \cos \varphi}.$$

Nếu vỏ quả bóng vẫn có dạng hình cầu thì áp suất sẽ tăng khi góc tăng dần $\varphi$. Trên thực tế, theo định luật Pascal, áp suất sẽ tăng lên tương tự. Điều này có nghĩa là vỏ quả bóng không có hình cầu. Nó nằm dọc theo đường xích đạo hơn là dọc theo đường kính thẳng đứng; bán kính cong của kinh tuyến giảm dần về phía xích đạo và tăng dần về phía cực sao cho $R^2 \cos \varphi = \text{const}$.

Hình dạng của vỏ giống quả bí ngô (Hình 11). Có lẽ hình dạng của quả bí ngô được giải thích chính xác bởi sự hiện diện của “sợi dây gia cố” và linh hồn dọc theo kinh tuyến của nó?

F511. Các bản của tụ điện dạng bản song song có diện tích $S$ tạo thành một góc nhỏ $\alpha$ ($\alpha \ll 1$) với nhau. Khoảng cách trung bình giữa các tấm là $b$. Vẽ hình gần đúng của các đường phẳng của trường electron của tụ điện và tìm điện dung của tụ điện.

Hình ảnh gần đúng về các đường electron hợp lưu của các vòng tròn có tâm ở điểm $O$. Thật vậy, các đường thoát nước luôn vuông góc với bề mặt dây dẫn, tức là chúng vuông góc với các bản tụ điện. Từ các báo cáo về các đối xứng, người ta thấy rất rõ ràng rằng chúng vuông góc với đường phân giác của góc tạo bởi các tấm. Nếu đặt một tấm kim loại mỏng vào vị trí của đường phân giác thì hình ảnh các đường mận sẽ không thay đổi chút nào. Lập luận theo cách tương tự, chúng ta sẽ đi đến kết luận rằng đường thoát nước nên

⟦folio 35⟧

vuông góc với bất kỳ tia nào phát ra từ điểm $O$ và nằm trong góc $\alpha$. Điều này có nghĩa là các đường mạnh là các cung tròn đồng tâm.

Mật độ của các đường sức không phải lúc nào cũng giống nhau; nó giảm dọc theo trục $X$. Điều này không khó để giải thích. Như đã biết, mật độ đường sức tỉ lệ thuận với hiệu điện thế của điện trường. Hãy tìm xem điện áp thay đổi như thế nào khi tọa độ $x$ tăng (gốc tọa độ nằm ở điểm $B$). Công việc di chuyển một đơn vị điện tích từ bản tụ này sang bản tụ khác dọc theo đường dây mạnh nam-nam phải giống nhau (công này bằng hiệu điện thế giữa các bản). Do đó, đường dây điện càng dài thì điện áp (lực tác dụng lên một đơn vị điện tích) càng thấp. Có tính đến độ nhỏ của góc $\alpha$ ta thu được

$$|\vec{E}| = |\vec{E}_0| \frac{b}{b + \alpha x},$$

trong đó $\vec{E}_0$ là điện áp trên đường dây điện $AB$ (trong đó khoảng cách giữa các bản tụ điện là $b$), $\vec{E}$ là điện áp trên đường dây điện liền kề, cách nhau $AB$ bằng $x$, $b$ và $b + x$ - độ dài của các đường dây điện tương ứng.

Mật độ đường dây điện cũng thay đổi.

Bây giờ chúng ta hãy tìm điện dung $C$ của tụ điện. Theo định nghĩa

$$C = \frac{q}{U},$$

trong đó $q$ là điện tích và $U$ là điện áp của tụ điện. $U$ có ​​thể được thể hiện thông qua $|\vec{E}_0|$:

$$U = |\vec{E}_0| b.$$

Nó vẫn còn để thể hiện $q$.

Ở gần tấm, điện trường giống như điện trường của mặt phẳng; do đó điện áp của nó

$$|\vec{E}| = \frac{\sigma}{2\varepsilon_0},$$

trong đó $\sigma$ là mật độ điện tích bề mặt, $\varepsilon_0$ là hằng số điện. Từ đây

$$\sigma = 2\varepsilon_0 |\vec{E}| = \frac{2\varepsilon_0 |\vec{E}_0| b}{b + \alpha x}.$$

Chúng ta hãy biểu thị bằng $l$ “độ sâu” của tấm và chọn một dải hẹp có chiều rộng $\Delta x$ trên tấm. Điện tích của nó bằng nhau

$$\Delta q = \sigma l \Delta x = \frac{2\varepsilon_0 |\vec{E}_0| b l}{b + \alpha x} \Delta x.$$

Để tìm toàn bộ điện tích của tấm, chúng ta cần tổng điện tích của tất cả các dải cơ bản và đi đến giới từ tại $\Delta x \rightarrow 0$. Kết quả là chúng tôi nhận được

$$q = 2\varepsilon_0 b l |\vec{E}_0| \int_{-a}^{a} \frac{dx}{b + \alpha x} = \frac{2\varepsilon_0 b l |\vec{E}_0|}{\alpha} \ln \frac{b + \alpha a}{b - \alpha a}.$$

Rồi cuối cùng

$$C = \frac{q}{U} = \frac{2\varepsilon_0 l}{\alpha} \ln \frac{b + \alpha a}{b - \alpha a}.$$

I. Slovodetsky
