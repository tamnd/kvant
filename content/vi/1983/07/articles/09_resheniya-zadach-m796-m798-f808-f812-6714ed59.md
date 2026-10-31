---
id: 1983-7-resheniya-zadach-m796-m798-f808-f812-6714ed59
issue: kvant_1983_7
year: 1983
number: "7"
title: Lời giải bài toán M796—M798; F808—F812
rubric: zadachnik-kvanta
rubric_sub: Задачник «Кванта»
page_first: 48
page_last: 52
page_labels: 46-50
tag: 13QT
lang: vi
source: kvant_digital
extraction: vision
content_sha256: eb82310a2072db6f886bf9b2bf0e2335b32ef6a580ce444f4ab971d94f004ed0
prompt_sha256: draft-1
translated_from: content/ru/1983/07/articles/09_resheniya-zadach-m796-m798-f808-f812-6714ed59.md
source_content_sha256: 8a8732c598e42cc819acb01b4dec2c8fcafff62bb74b0d85045b4866921eb65f
translation_model: draft
translation_run: vi-draft-2026-10-31
translation_quality: draft
---

⟦folio 46⟧

the ammeter then? The battery is assumed ideal, the resistance of the wires is 2 Ohm.

A. R. Zilberman

P826. Far-away objects are viewed through a convergent lens of focal distance $F=9$ cm, the eye being located at the distance $a=36$ cm from the lens. Estimate the minimal size of a screen which, if placed behind the lens, would entirely cover the field of vision. Where should the screen be placed?

D. V. Belov

P827. A cube with side $a$ moves with velocity $v=0.8$ c (where $c$ is the velocity of light) in a direction perpendicular to one of its faces. What will we see on a photograph of the cube taken by a far-away camera with a very short exposure, if the optical axis of the camera is perpendicular to a face of the cube and intersects the trajectory of its centre (figure Pric. 3)?

D. Ju. Grigoriev

Lời giải bài toán

M796—M798; F808—F812

TRẢ LỜI: $\widehat{APB}=135^\circ$. Hãy xoay $\triangle ABP$ quanh điểm $B$ bằng $90^\circ$ sao cho đỉnh $A$ thẳng hàng với $C$ (xem hình). Để đỉnh $P$ đi đến điểm $Q$. Sau đó $|PQ|^2=2|BP|^2=8|AP|^2$ ($\triangle BPQ$ hình chữ nhật có đầu bằng nhau) và $|QC|=|PA|$. Do đó, $|PQ|^2+|QC|^2=9|AP|^2=|CP|^2$, tức là $PQC$, là tam giác vuông có góc vuông $PQC$. Do đó $\widehat{APB}=\widehat{CQB}=\widehat{CQP}+\widehat{PQB}=90^\circ+45^\circ=135^\circ$.

Ngoài ra còn có một lời giải ít nhân tạo hơn (nhưng cồng kềnh hơn) bằng cách sử dụng phương pháp tọa độ. Ta lấy các đường thẳng $AB$ và $AD$ làm trục tọa độ; gọi $(x, y)$ là tọa độ của điểm $P$. Khi đó, xét cạnh hình vuông bằng 1, ta có: $|AP|^2=x^2+y^2$, $|BP|^2=x^2+(1-y)^2$, $|CP|^2=(1-x)^2+(1-y)^2$. Theo điều kiện $|AP|^2:|BP|^2:|CP|^2=1:4:9$, từ đây dễ dàng tìm được $x$ và $y$, rồi đến góc mong muốn.

L. D. Kurlyandchik

M797*. Người ta biết rằng các chữ số cuối cùng của bình phương các số nguyên chỉ có thể là các số 0, 1, 4, 5, 6 và 9. Có đúng là trước chữ số cuối cùng chúng có thể chứa bất kỳ nhóm chữ số nào, nghĩa là với bất kỳ tập hợp $n$ chữ số $a_1, a_2, \dots, a_n$ nào, người ta có thể tìm thấy một số nguyên có hình vuông kết thúc bằng các chữ số $a_1a_2\dots a_nb$ (trong đó b là một trong các chữ số được liệt kê ở trên)?

TRẢ LỜI: Không. Chúng tôi sẽ đưa ra hai bằng chứng về sự thật này.

Bằng chứng đầu tiên. Gọi $A_n$ là số của tất cả các kết hợp từ $n$ chữ số mà hình vuông chính xác quay trên đó. Chúng ta sẽ chỉ ra rằng nếu $n \geq 4$ thì $A_n<10^n$. Tuyên bố của chúng tôi sẽ tiếp nối điều này: ngay cả khi mỗi kết hợp $a_1, \dots, a_n$ được tìm thấy kết hợp với chỉ một $b$, thì sẽ có $A_n=10^n$. Để có được tất cả các phần cuối có $n$ chữ số của các hình vuông là rất cần thiết; chỉ cần xét bình phương của các số có $n$ chữ số là đủ. Hãy chia các số $10^n$ này (từ 0 đến $10^n$-1) thành các lớp, thu thập vào một lớp tất cả các số có cùng đuôi hình vuông $n$ chữ số ($p$ và $q$ được xếp vào một lớp nếu $p^2-q^2$ chia hết cho $10^n$). Khi đó $A_n$ bằng số lớp đó; Dựa trên điều này, chúng tôi sẽ ước tính $A_n$.

Chúng ta hãy xem xét riêng ba nhóm số có $n$ chữ số: (1) các số chia hết cho $5^n$ (và cả $2^n$); (2) số lẻ không chia hết cho $5^n$ (có ít hơn $0,5 \cdot 10^n$); (3) các số chẵn không chia hết cho $5^n$ (các số này cũng ít hơn $0,5 \cdot 10^n$). Số lượng các số trong nhóm đầu tiên nhỏ so với $10^n$. Điều quan trọng đối với chúng tôi là chúng cho các số dư khác nhau theo từng cặp khi chia cho $2^n$ (vì $k \cdot 5^n-l \cdot 5^n=(k-l) \cdot 5^n$ không thể chia cho

⟦folio 47⟧

2$^n$ tại $1 \leqslant l < k \leqslant 2^n$), và do đó, trong số các dư lượng này, tất cả các dư lượng có thể có của quá trình phân tách ở $2^n$ đều xảy ra một lần. Hơn nữa, giả sử $m$ là một số thuộc nhóm thứ hai. Chúng ta hãy tìm trong nhóm đầu tiên các số $k_1 \cdot 5^n, k_2 \cdot 5^n, k_3 \cdot 5^n$ và $k_4 \cdot 5^n$, khi chia cho $2^n$ thì có cùng số dư như $2m, 2^{n-1}+2m, 2^n-2m$ và $2^{n-1}-2m$. Khi đó các bình phương của 8 số $m, 10^n-m, 0,5 \cdot 10^n \pm m, k_1 \cdot 5^n-m, k_3 \cdot 5^n+m$ và $k_4 \cdot 5^n+m$ (chúng được viết ở lề) có cùng đuôi $n$ chữ số ở $n \geqslant 4$. Thật vậy, vì $0,25 \cdot 10^n$ là số nguyên ($n \geqslant 4$), $k_i$ là số chẵn và các số trong ô màu xanh ở lề đều chia hết cho $2^n$ nên tất cả các số trong ô màu đỏ đều chia hết cho $10^n$. Do đó, các lớp số của nhóm thứ hai chứa ít nhất 8 phần tử nên số của chúng nhỏ hơn $0,5 \cdot 10^n/8$. Tương tự, đối với $n \geqslant 4$ các lớp số của nhóm thứ ba chứa ít nhất 16 phần tử. (Mỗi lớp, cùng với số $m$, chứa các số $10^n-m, 0,25 \cdot 10^n \pm m, 0,5 \cdot 10^n \pm m, 0,75 \cdot 10^n \pm m, k_1 \cdot 5^n-m, ..., k_4 \cdot 5^n-m, k_5 \cdot 5^n+m, ..., k_8 \cdot 5^n+m$, trong đó $k_1, ..., k_8$ được chọn sao cho các số $k_1 \cdot 5^n, ..., k_8 \cdot 5^n$ khi chia cho $2^n$ sẽ có số dư bằng các số $2^n, 2^{n-2}+2m, 2^{n-1}+2m, 3 \cdot 2^{n-2}+2m, 2^n-2m, 2^{n-1}-2m, 3 \cdot 2^{n-2}-2m$.) Do đó, số lớp trong nhóm (3) nhỏ hơn $0,5 \cdot 10^n/16$ và tổng số số lớp $A_n < 2^n + \frac{0,5 \cdot 10^n}{8} + \frac{0,5 \cdot 10^n}{16} = 10^n \left( \frac{1}{5^n} + \frac{1}{16} + \frac{1}{32} \right) \leqslant 10^n \left( \frac{3}{32} + \frac{1}{5^4} \right) = 0,9535 \cdot 10^{n-1} < 10^{n-1}$.

Hãy thử tìm kiếm $\lim_{n \to \infty} A_n/10^{n-1}$.

Bằng chứng thứ hai. Nó ngắn hơn cái đầu tiên, nhưng kém tôn trọng hơn. Thực tế sau đây được áp dụng:

Nếu chữ số áp chót của một hình vuông là số lẻ thì chữ số cuối cùng là 6.

Trên thực tế, từ đẳng thức $(10a+b)^2 = 100a^2 + 20ab + b^2$, rõ ràng chữ số áp chót của bình phương của bất kỳ số nào và chữ số áp chót của bình phương của chữ số cuối cùng của nó có cùng tính chẵn lẻ. Nhưng trong bình phương của số có một chữ số, chữ số áp chót chỉ là số lẻ trong hai trường hợp: $4^2 = 16$ và $6^2 = 36$.

Bây giờ chúng ta sẽ chỉ ra rằng một hình vuông chính xác không thể kết thúc bằng 005$b$. Thật vậy, theo những gì đã được chứng minh, một bình phương như vậy phải có tận cùng là 0056, và khi chia cho 16 sẽ có dư 8, điều này rõ ràng là không thể (bình phương của một số chia hết cho 4 thì chia hết cho 16, và bình phương của một số không chia hết cho 4 thì không chia hết cho 8).

Chúng tôi mời người đọc nghiên cứu độc lập $n=2$ và 3 chi tiết hơn. Chứng minh rằng a) với mọi số $a_1a_2$ luôn tồn tại một số chính phương có tận cùng là $a_1a_2b$; b) một bình phương chính xác có thể tận cùng bằng $a_1a_2a_3b$ (với neoctor $b$) khi và chỉ nếu số có ba chữ số $a_1a_2a_3$ có số dư không bằng 5 hoặc 7 khi chia cho 8.

Chúng ta hãy đưa ra một bài toán khác về chủ đề này, do D. Fedorov gửi cho người biên tập: chứng minh rằng một số có dạng $aa...ab$, trong đó $b=a+1$, không thể là một số chính phương.

D. B. Fuchs

◆ Trước tiên chúng ta giả sử rằng các đoạn màu đỏ không giao nhau và chứng minh rằng khi đó mỗi đoạn màu đỏ giao nhau với ít nhất một hình ảnh, tức là số giao điểm màu đỏ-xanh không nhỏ hơn $k$. Lấy bất kỳ đoạn màu đỏ nào $AB$ và một trong những người bạn phụ trách đoạn đó. Số chấm đỏ trên đó là số chẵn (vì

⟦folio 48⟧

đoạn mi và đoạn màu xanh lam 2k - đến đoạn màu xanh lam (không có ba đoạn nào giao nhau tại một điểm). Chứng minh rằng có ít nhất k giao điểm của đoạn màu đỏ và đoạn màu xanh.

Hình 1.

Hình 2.

F808. Một chiếc thuyền máy đặt tại điểm A cách bờ hồ một khoảng R, bắt đầu chuyển hướng, chuyển động với vận tốc v=18 km/h dọc theo một đường tròn bán kính r=R/2; Tại thời điểm ban đầu, vận tốc của thuyền hướng vào bờ. Sóng từ thuyền vào bờ tại thời điểm t=3 phút sau khi bắt đầu rẽ. Vận tốc truyền sóng từ thuyền dọc theo mặt nước là u=9km/h. Tìm khoảng cách R

F809. Một bình hình trụ chứa đầy chất lỏng có khối lượng riêng q. Phía trên thùng được đậy kín bằng nắp có bán kính R. Ở phía dưới thùng có một lỗ có diện tích s, được đậy kín bằng nút có khối lượng m (xem hình).

Rằng bất kỳ điểm nào trong số chúng phải được nối bằng một đoạn với một điểm trên cùng một cung), do đó, số điểm màu xanh trên cung này là số lẻ. Do đó, một trong các đoạn màu xanh bắt đầu trên nó phải cắt AB.

Telery sẽ chỉ ra rằng bất kỳ hệ thống nào có các đoạn màu đỏ và xanh lam đều có thể được "làm sáng tỏ" - được thay thế bằng một hệ thống mới trong đó các đoạn màu đỏ không giao nhau theo cặp mà không làm tăng số lượng giao điểm màu đỏ-xanh. Cho AC và BD cắt các đoạn màu đỏ. Hãy thay thế chúng bằng các đoạn màu đỏ AB và CD (Hình 1). Rõ ràng là bất kỳ đoạn thẳng nào (đỏ hoặc xanh) cắt đoạn AB hoặc đoạn CD đều có cùng số giao điểm với nó như với AC và BD. Do đó, khi thay thế, số nút giao đỏ-xanh không tăng mà số nút giao đỏ-xanh giảm ít nhất 1. Sau một số thao tác như vậy, ta thu được hệ các đoạn trong đó các đoạn màu đỏ không giao nhau theo cặp và số lượng nút giao đỏ-xanh không nhiều hơn ban đầu, đồng thời như đã chứng minh ở phần đầu, không nhỏ hơn k.

Có thể dễ dàng xây dựng một ví dụ về hệ thống các đoạn có k nút giao màu đỏ-xanh (Hình 2).

S. V. Fomin

◆ Coi con thuyền là nguồn sóng, truyền từ mỗi điểm trên quỹ đạo của con thuyền, ta sẽ tìm được điểm C mà từ đó sóng sẽ vào bờ. Vị trí điểm C được xác định từ điều kiện bằng nhau giữa vận tốc truyền sóng và hình chiếu vận tốc của thuyền theo phương “hướng vào bờ” (trục X trên hình):

$$u = v_x = v \sin \alpha \Rightarrow \sin \alpha = u/v = 1/2,$$

nghĩa là, $\alpha = 30^\circ$. Xét từ điểm C ra bờ là

$$l = R - r \cos \alpha = R - \frac{R}{2} \cos \alpha = R \left( 1 - \frac{1}{2} \cos \alpha \right).$$

Thời gian t để sóng truyền từ điểm C vào bờ là

$$t_1 = l/u = \frac{R}{u} \left( 1 - \frac{1}{2} \cos \alpha \right).$$

Thời gian t₂ để thuyền đi từ điểm A đến điểm C là

$$t_2 = \frac{2\pi r}{v} \cdot \frac{60^\circ}{360^\circ} = \frac{\pi R}{6v}.$$

Tổng thời gian sau đó kể từ khi bắt đầu rẽ sóng vào bờ bằng

$$t = t_1 + t_2 = \frac{R}{u} \left( 1 - \frac{1}{2} \cos \alpha \right) + \frac{\pi R}{6v}.$$

Từ đây tìm được R từ điểm A tới bờ:

$$R = \frac{6tuv}{3v (2 - \cos \alpha) + \pi u} \approx 545 \text{ м.}$$

A. I. Buzdin

◆ Áp suất trong chất lỏng trong một bể quay ở cùng độ sâu sẽ khác nhau ở tâm bình và ở thành bình - áp suất tăng khi nó di chuyển ra xa tâm. Chúng ta hãy tìm xem áp suất ở các bức tường khác với áp suất ở trung tâm là bao nhiêu.

Chúng ta hãy nhẩm chọn một cột chất lỏng mỏng nằm ngang có diện tích mặt cắt ngang σ (xem hình).

⟦folio 49⟧

Để rút phích cắm ra khỏi bình, bạn cần tác dụng một lực f. Với tốc độ góc tối đa bao nhiêu thì thùng có thể quay quanh một trục thẳng đứng mà phích cắm không bị văng ra ngoài?

Khối tâm của bàn này chuyển động dọc theo một đường tròn bán kính $R/2$. Viết phương trình chuyển động của chiếc ghế:

$$\varrho R \omega^2 \frac{R}{2} = \Delta p \cdot \sigma$$

($\varrho R \sigma$ là khối lượng của stolnik, $\Delta p \cdot \sigma$ là kết quả của các lực ép tác dụng lên stolnik ở bên phải và bên trái). Do đó, áp suất trong chất lỏng ở thành lớn hơn áp suất ở trung tâm phía trên

$$\Delta p = \frac{1}{2} \varrho \omega^2 R^2.$$

Đối với Posny, lực tác dụng lên nút từ phía chất lỏng bằng

$$F = s \left( p_0 + \varrho g H + \frac{1}{2} \varrho \omega^2 R^2 \right),$$

trong đó $p_0$ là áp suất khí quyển, $H$ là chiều cao của bể.

Hãy viết phương trình ùn tắc giao thông:

$$m \omega^2 R = p_0 s + F_{\text{тр}} - s \left( p_0 + \varrho g H + \frac{1}{2} \varrho \omega^2 R^2 \right).$$

Theo điều kiện sau, phích cắm bay ra khỏi bình ở mức $F_{\text{тр}} = f + s \varrho g H$. Khi tính đến điều này, chúng ta tìm được vận tốc góc quay mà tại đó phích cắm sẽ bay ra ngoài:

$$\omega = \sqrt{\frac{f}{m R + \frac{1}{2} s \varrho R^2}}.$$

V. I. Komov

F810. Có máy cắt có nhiệt độ hoạt động $t_H = 700^\circ\text{C}$. Nhiệt độ môi trường xung quanh - $t_0 = 20^\circ\text{C}$. Phải lấy nhiệt lượng tối thiểu bao nhiêu từ máy cắt để bay hơi $m = 3$ kkw. nước, cắt đến điểm sôi ($t_1 = 100^\circ\text{C}$)? Nhiệt độ riêng của nước cắt $r = 2,26$ MJ/kg.

Khi truyền nhiệt trực tiếp từ lò sưởi sang nước, để làm bay hơi một khối nước $m$ cần nhận một lượng nhiệt $Q_0 = mr$ từ lò sưởi.

Chúng ta hãy cố gắng giảm giá trị này bằng cách lợi dụng thực tế là một máy bơm nhiệt (nghĩa là động cơ nhiệt hoạt động theo chu trình ngược) có thể bơm một lượng lớn năng lượng nhiệt từ vật lạnh sang vật nóng với chi phí cơ năng thấp, nếu chênh lệch nhiệt độ không phải là VELK.

Hãy tưởng tượng một thiết bị làm bay hơi nước, bao gồm một động cơ nhiệt lý tưởng $M$ và một bơm nhiệt lý tưởng $H$, được bật như trong Hình 1. Máy lấy lượng nhiệt $Q_1$ từ lò sưởi và truyền lượng nhiệt $Q_2$ sang nước nóng, trong khi thực hiện công $A$. bơm nhiệt $H$, sử dụng công $A$, lấy lượng nhiệt $Q_3$ từ môi trường và truyền lượng nhiệt $Q_4$ sang nước nóng.

Hãy tính tổng nhiệt lượng $Q_2 + Q_4$, ta được nước. Hệ số hiệu suất của máy $M$ bằng

$$\eta = \frac{A}{Q_1} = \frac{T_H - T_1}{T_H}.$$

Từ đây

$$A = Q_1 \frac{T_H - T_1}{T_H}, \quad Q_2 = Q_1 \frac{T_1}{T_H}.$$

Vì bơm nhiệt $H$ là một động cơ nhiệt lý tưởng hoạt động theo chu trình ngược nên chúng ta có thể viết nó theo cách tương tự

$$\frac{A}{Q_4} = \frac{T_1 - T_0}{T_1} \Rightarrow Q_4 = A \frac{T_1}{T_1 - T_0} = Q_1 \frac{(T_H - T_1) T_1}{T_H (T_1 - T_0)}.$$

Như vậy,

$$Q_2 + Q_4 = Q_1 \frac{T_1}{T_H} \frac{T_H - T_0}{T_1 - T_0}.$$

⟦folio 50⟧

Để làm bay hơi nước, tổng lượng nhiệt truyền vào nó phải bằng $Q_2 + Q_4 = Q_0$. Vì vậy máy M phải lấy lượng nhiệt từ dàn nóng

$$Q_1 = Q_0 \frac{T_H(T_1 - T_0)}{T_1(T_H - T_0)} \approx 0.31 \text{ mr.}$$

Do đó, khi sử dụng máy bơm nhiệt (tủ lạnh) lý tưởng $Q_1$, lượng nhiệt cần thiết để làm bay hơi nước sẽ ít hơn đáng kể.

Từ công thức tính hiệu suất của bơm nhiệt, ở mức $\frac{T_1 - T_0}{T_1} \ll 1$, có thể sử dụng năng lượng ấm của môi trường (để bay hơi, sưởi ấm, v.v.), trong khi tiêu tốn một lượng nhỏ năng lượng cơ, điện hoặc bất kỳ năng lượng phi vật chất nào khác. Tuy nhiên, trên thực tế, máy bơm nhiệt (tủ lạnh) vẫn chưa đạt đến mức lý tưởng và việc sử dụng chúng làm bộ phận làm nóng vẫn chưa trở nên phổ biến.

Điều thú vị cần lưu ý là sẽ thu được kết quả (*) nếu máy M hoạt động giữa nhiệt và môi trường (Hình 2).

O. S. Rabinovich

F811. Trong mạch tổng quát của bộ chỉnh lưu nửa sóng (Hình 1) $C = 1000$ μF, $R = 500$ Ohm. Tần số mạng $v = 50$ Hz. Giả sử diode là lý tưởng, hãy tìm:
1) độ lớn của hệ số gợn sóng điện áp $k = \frac{\Delta U}{U}$ trên điện trở $R$;
2) Hệ số $k$ sẽ giảm bao nhiêu lần nếu một cuộn cảm $L = 100$ Hz mắc nối tiếp với điện trở?

Hình 1.

Hình 2.

1) Với thông số đã chọn $C$ và $R$, điện tích của tụ thay đổi không đáng kể nên dòng phóng điện của tụ có thể coi là không đổi. Sau đó

$$\Delta U = \frac{\Delta q}{C} = \frac{I \cdot \Delta t}{C} = \frac{U \cdot \Delta t}{RC}.$$

Có nghĩa,

$$k = \frac{\Delta U}{U} = \frac{\Delta t}{RC}.$$

Nếu tụ điện được phóng điện một chút thì nó sẽ được sạc lại tại thời điểm có điện áp dương cực đại trong mạng (Hình 2), tức là

$$\Delta t = T = \frac{1}{v}.$$

Kể từ đây,

$$k = \frac{1}{vRC} = 0.04.$$

2) Khi nối một cuộn cảm, hệ số gợn sóng càng nhỏ hơn (độ tự cảm lớn: $2\pi vL \gg R$). Dòng tải càng có thể được coi là không đổi; Điều này có nghĩa là điện áp trên tụ điện sẽ nhỏ hơn theo quy luật tương tự như trong trường hợp đầu tiên. Trong trường hợp này, điện áp trên cuộn dây gần như sẽ bù đắp cho sự thay đổi điện áp trên tụ điện. Dòng điện qua cuộn dây trong chu kỳ mạng sẽ nhỏ hơn theo định luật parabol (emf cảm ứng theo định luật tuyến tính) và giá trị dòng điện cực đại sẽ ở giữa chu kỳ:

$$\mathcal{E} = \frac{\Delta U}{T} t \quad (\text{при } t \in [nT, (n+1)T])$$

$$I = l_0 - \frac{\Delta U}{T} \frac{1}{L} \frac{1}{2} t^2.$$

Ripple trong trường hợp này được xác định bởi những thay đổi của dòng điện: $\Delta U_1 = R \cdot \Delta I$. Từ

$$\Delta I = I_{\max} - I_{\min} = \frac{1}{2} \frac{\Delta U}{LT} \frac{T^2}{4} = \frac{1}{8} \frac{UT^2}{LRC}$$

($\Delta U = \frac{UT}{RC}$), cuối cùng chúng tôi nhận được:
