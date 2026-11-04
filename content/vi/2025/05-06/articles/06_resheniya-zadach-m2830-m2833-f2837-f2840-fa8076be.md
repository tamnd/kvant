---
id: 2025-5-6-resheniya-zadach-m2830-m2833-f2837-f2840-fa8076be
issue: kvant_2025_5-6
year: 2025
number: 5-6
title: Lời giải bài toán M2830—M2833; F2837—F2840
rubric: zadachnik-kvanta
rubric_sub: Задачник «Кванта»
page_first: 24
page_last: 31
page_labels: 22, 23, 26, 26, 27, 28, 29
lang: vi
source: kvant_digital
extraction: vision
content_sha256: 1d643100442307e677f6d5e7aeefb799c8e25fed5feb1cefd7fec5c855518605
prompt_sha256: draft-1
translated_from: content/ru/2025/05-06/articles/06_resheniya-zadach-m2830-m2833-f2837-f2840-fa8076be.md
source_content_sha256: d77009802c036315d52aa36b1b212ba0d4c324f2e072e7ae9a727f4b5f6ebe6b
translation_model: draft
translation_run: vi-draft-gaps-2026-11-03
translation_quality: draft
---

⟦folio 22⟧

Lời giải bài toán M2830-M2833, F2837-F2840

M2830. Đầu vào là một đồng xu có mệnh giá là a và b dyblon, trong đó a và b là các số tự nhiên được xem lẫn nhau đã cho, với $a < b < 100$. Một số nguyên không âm n được gọi là remote nếu tổng n dybloons có thể được thu thập bằng cách sử dụng không quá 1000 xu. Tìm số lượng các số từ xa.

Đáp số: $1001b - \frac{b(b-1)}{2}$.

Nếu bộ này sử dụng ít nhất b đồng xu dybloons, chúng ta có thể thay thế chúng bằng một đồng xu b dybloons. Trong trường hợp này, số lượng mệnh giá sẽ không thay đổi nhưng tổng số xu sẽ giảm. Do đó, từ bất kỳ bộ thay thế nào như vậy, có thể thu được một bộ có cùng số lượng, trong đó không có nhiều hơn $(b-1)$ đồng xu của một dyblon. Vì vậy, hơn nữa, chúng tôi chỉ xem xét các bộ trong đó có từ 0 đến $b-1$ đồng xu của một dyblon.

Lưu ý rằng các quyền chọn có số lượng xu và dyblon khác nhau rõ ràng sẽ cho số tiền khác nhau, vì chúng có số dư khác nhau khi chia cho b. (Thật vậy, nếu $0 \leq i < j \leq b-1$ là số đồng xu trên một dybloons, thì tổng tương ứng khi chia cho b sẽ có cùng số dư là $ia$ và $ja$. Nhưng $ja-ia = (j-i)a$ không chia hết cho b, vì a và b nguyên tố cùng nhau, a $0 < j-i < b$.

Chúng ta hãy ấn định số lượng k xu bằng một dybloons. Sau đó, bạn có thể thêm vào chúng 0,1,...,1000-k xu b dyblon, và rõ ràng là tất cả số tiền thu được sẽ khác nhau. Chúng tôi thấy rằng với một k nhất định, chúng tôi có $(1001-k)$ tùy chọn.

Tổng hợp bằng $k = 0,1,...,b-1$, ta được tổng số phương án:

$$1001 + (1001-1) + (1001-2) + \dots + (1001-(b-1)) = 1001b - (1+2+\dots+(b-1)) = 1001b - \frac{b(b-1)}{2}.$$

P. Kozhevnikov

M2831. Chúng ta hãy viết DEF (hình 1) thành lưu biến parabol. Vẽ các tiếp tuyến tại các điểm D, E, F và được giới hạn bởi tam giác ABC. Chứng minh rằng $S_{DEF} = 2S_{ABC}$.

Tuyên bố màu đỏ này có thể được chứng minh bằng nhiều cách, bao gồm cả tính toán “vũ phu” trong tọa độ. Tuy nhiên, một trong những bằng chứng có thể dựa vào bổ đề như vậy.

Vẽ các tiếp tuyến AE và AF từ điểm A đến parabol (sao cho E và F là các điểm tiếp tuyến). Sau đó:

(1) Đường trung tuyến AK của tam giác AEF song song với trục của parabol (hay nói cách khác A nằm trên đường thẳng đi qua trung điểm EF;

⟦folio 23⟧

---
running_head:
folio:
---

(2) Ngoài ra, trung điểm của đường trung tuyến AK nằm trên parabol.
Bổ đề có thể được chứng minh trực tiếp nhiều lần.
phép tính: nếu $y = x^2$ là phương trình
parabol thì các tiếp tuyến được vẽ tới
nó tại các điểm $(d; d^2)$, $(e; e^2)$, cắt nhau tại
điểm $\left(\frac{d + e}{2}; de\right)$.
Chúng tôi cũng sử dụng thực tế này: nếu ủng hộ
vẽ các đường thẳng song song rồi tìm trung điểm
các đoạn được khắc trên chúng bởi một hình parabol,
nằm trên một đường thẳng song song với trục
parabol. (Điều này dễ dàng chứng minh được,
Tôi sẽ sử dụng định lý Vieta.)
Hãy chuyển sang lời giải bài toán.
Không mất tính tổng quát, chúng ta tin rằng dự án
tion $B$ trên trục $Ox$ nằm giữa các hình chiếu $A$
và $C$. Đặt $K, L, M$ là trung điểm của các cạnh $EF$,

Hình 2
FD, DE tương ứng với (hình 2). Theo
bổ đề, $AK \parallel BL \parallel CM$ (ba cặp trực tiếp này
song song với trục của parabol). Chúng ta thấy điều đó về
hình chiếu của các đoạn $KM$ và $AC$ lên trục $Ox$ bằng nhau,
lấy độ dài của hình chiếu này là $l$.
Tiếp theo, qua điểm $E$ ta vẽ một đường thẳng,
song song với $DF$, coi nó là thứ yếu
cắt parabol tại điểm $T$. Sau đó bởi
thực tế ở trên, phần giữa $R$ cắt-
ka $ET$ nằm trên đường thẳng (dọc) $BL$. Để tiếp tuyến của parabol vẽ tại điểm $T$ cắt $AC$ tại điểm $S$. Một lần nữa, theo bổ đề, $SR$ song song với trục
parabol, do đó $S$ cũng nằm trên $BL$. Qua
phát biểu (2) của bổ đề, giao điểm

Sự kết hợp của $BL$ với một parabol chia đôi từng đoạn $BL$ và $SR$. Vì vậy, $BS = RL$. Hãy chuyển sang tính toán diện tích:
$2S(ABC) = AC \cdot BS \cdot \sin \angle ASB =$
$= BS \cdot (AC \sin \angle ASB) = BS \cdot l$.

Trong hình tam giác $DEF$ (hoặc trong hình thang $DETF$)
chiều cao được vẽ từ điểm $E$ bằng
$RL \sin \angle RLF$. Pozotomu
$S(DEF) = DF \cdot RL \cdot \frac{\sin \angle RLF}{2} =$
$= RL \cdot \frac{DF}{2} \cdot \sin \angle RLF =$
$= RL \cdot (KM \sin \angle RLF) = BS \cdot l$,
bằng $2S(ABC)$.
Hãy để chúng tôi trình bày một sơ đồ khác lời giải. Nó
dựa trên thực tế sau đây.
Để một đường thẳng song song với trục của parabol và đi qua $B$ cắt nhau $AC$ tại điểm $B'$. Khi đó $B'$ và $E$ đối xứng
so với phần giữa $AC$.
(Điều này rất dễ chứng minh, ví dụ, biểu thức
ziv abscissa của tất cả các điểm abscissa
điểm tiếp xúc.)
Tương tự, chúng ta xác định các điểm $A'$ và $C'$; Vì
Họ có một tài sản tương tự. Vì thế,
trong tam giác $A'B'C'$ và $DEF$ tương ứng với các đỉnh đối xứng của trung điểm tương đối của cạnh tam giác $ABC$. Những tam giác như vậy được gọi là đẳng trường đối với tam giác $ABC$.
Người ta biết (và không quá khó để chứng minh) rằng
tam giác đồng vị có diện tích bằng nhau.
Vẫn còn phải đảm bảo rằng nếu
hình vuông song song $ABC$
cevians $AA'$, $BB'$ và $CC'$ (tức là $A'$, $B'$, $C'$ –
cũng có điểm trên các dòng $BC$, $CA$, $AB$
$AA' \parallel BB' \parallel CC'$), rồi $S(A'B'C') = 2S(ABC)$.
Bình luận. Như M. Didin đã lưu ý, điều này
bài toán có thể được điều chỉnh lại mà không cần chuẩn bị trước
lực hút của parabol như sau.
Chọn điểm $P$ trên đường tròn ngoại tiếp tam giác $ABC$ (thực tế là
$P$ – tiêu điểm của parabol tiếp tuyến với các đường thẳng
$AB$, $BC$, $CA$). Qua điểm $P$ ta vẽ
đường tròn tiếp tuyến với cạnh $AB$ trong
điểm $B$, cũng như tiếp tuyến của đường tròn
cạnh $AC$ tại điểm $C$. Họ đang tái-
cắt ở điểm $A'$ (thực ra $A'$ nằm

⟦folio 26⟧

---
running_head:
folio:
---

M2833*. Xung quanh đường tròn a) 26; b) 30 một-
những đồng xu trông giống nhau. Người ta biết rằng
chính xác hai trong số đó là giả. Hiện tại
những đồng xu nặng như nhau, chúng là giả
có thể, nhưng chúng dễ bị ướt hơn. Bạn nghĩ thế nào về
thế giới cân trên thang tsashina mà không có
cân để xác định, thuốc giả mo-
Chúng ta có ngu ngốc hay không?

Lời giải trong số này bài toán được đưa ra trong bài viết
A. Gribalko và K. Knopa trong số tạp chí này.

F2837. Hai quả bóng mềm nhỏ
khối lượng m được cố định bằng ba
những sợi chỉ không trọng lượng và không thể căng ra giữa
hai bức tường thẳng đứng trên cánh đồng
độ mềm (hình 1). Khoảng cách giữa

Tường 3d, chiều dài sợi, đính kèm
đến các bức tường bằng d, chiều dài của các sợi
nhẹ nhàng với quả bóng 2d. Từ độ cao h, từ
rửa từ giữa sợi ngang,
chúng tôi thả một quả bóng khác về phía đồng
có một cái móc gắn vào rượu rum. Vượt qua gần đó
với một sợi ngang, quả bóng được móc
móc sợi chỉ. Xác định các lực
độ căng của sợi dây tại thời điểm này. Usko-
Tỷ lệ nadiya tự do bằng g.

Tốc độ của quả bóng rơi lúc này
khi anh bám vào chiều ngang
sợi dây bằng v = $\sqrt{2gh}$. Hãy xem xét chuyển động
một trong những quả bóng lơ lửng trên
chủ đề (tại hình 2 – trái). Nó di chuyển theo vòng tròn với tâm ở điểm gắn chỉ trên bức tường bên trái. Phép chiếu

tốc độ của quả bóng bên trái và trung tâm
trên sợi ngang phải bằng nhau. Vận tốc của quả cầu ở giữa v hướng thẳng đứng xuống dưới. Do đó, tốc độ của quả bóng bên trái tại thời điểm ban đầu bằng không. Hình chiếu pháp tuyến của gia tốc của quả bóng bên trái cũng bằng 0 nên chỉ có thành phần tiếp tuyến $\vec{a}_\tau = \vec{a}$. Hãy xác định đại lượng này theo hai cách.

Cách 1. Vào hệ thống báo cáo,
chuyển động đi xuống với tốc độ không đổi $\vec{v}$ (hình 3). Trong đó, quả bóng bên trái di chuyển theo một vòng tròn, tâm của quả bóng đó là quả bóng trung tâm. Phép chiếu gia tốc bình thường trong hệ thống báo cáo này được hướng dọc theo luồng và bằng $a_n = v^2/d$. Nhưng việc chuyển đổi sang hệ thống báo cáo quán tính không làm thay đổi độ lớn hoặc hướng của gia tốc. Giá trị đặt ra của $a_n$ là hình chiếu của gia tốc $\vec{a}$ trên sợi ngang:

$a_n = a \cos \alpha, \frac{v^2}{d} = a \cos 30^\circ, a = \frac{2v^2}{\sqrt{3}d}$.

Cách 2. Chuyển sang hệ thống báo không phần trăm của quả bóng bên trái, khi đó quả bóng ở giữa sẽ chịu thêm lực quán tính $-m\vec{a}$ (hình 4). Ta viết phương trình định luật II Newton cho quả cầu ở tâm hình chiếu lên trục hoành:

$m \frac{v^2}{d} = T_2 - ma \cos 30^\circ - T_2'$.

Chúng ta lấy đâu ra điều tương tự đáp số.
Bây giờ không khó để tìm ra lực căng $T_1$ của sợi ngang và $T_2$ của sợi ngang. Từ định luật thứ hai của Newton cho quả bóng bên trái, nó tuân theo

$m \frac{v^2}{d} = T_2 - T_1 \sin 30^\circ$,

$m \frac{v^2}{\sqrt{3}d} = T_1 \cos 30^\circ - mg$.

⟦folio 26⟧

---
running_head:
folio:
---

Từ đây chúng ta có được
$$T_1 = \frac{2\sqrt{3}}{3} mg + \frac{2mv^2}{3d}, T_2 = \frac{\sqrt{3}}{3} mg + \frac{4mv^2}{3d}.$$
Thay thế $v^2 = 2gh$, cuối cùng chúng ta nhận được
$$T_1 = \frac{mg}{3}\left(2\sqrt{3} + 4\frac{h}{d}\right), T_2 = \frac{mg}{3}\left(\sqrt{3} + 8\frac{h}{d}\right).$$
A. Apollonsky

F2838. Một vết cắt mỏng có diện tích mặt cắt ngang $S$ được mô tả dưới dạng chữ cái đảo ngược $\Pi$ (xem hình). trong lửa
Trong khu vực cabin có một piston không trọng lượng, được nối với thành bên trái bằng lò xo. Theo chiều dọc
Trong buồng cắt có hai chất lỏng ở trạng thái cân bằng: bên trái có chất lỏng có mật độ $\rho_1$, và bên phải có chất lỏng có mật độ $\rho_2 < \rho_1$. Trong trường hợp này, sự chênh lệch mức của ranh giới trên của chất lỏng ở khuỷu tay thẳng đứng là $\Delta h$, cánh tay ở trạng thái không bị biến dạng. Hệ số độ cứng $k$ của lò xo được chọn sao cho khi thêm chất lỏng có mật độ $\rho_1$ vào đầu gối trái, sự chênh lệch về mức $\Delta h$ luôn không đổi.
1) Hệ số độ cứng $k$ là gì? Ở phần bên trái của cabin, chúng tôi thêm một thể tích $\Delta V$ chất lỏng có mật độ $\rho_2$, trong khi ranh giới trên của chất lỏng ở các phần thẳng đứng bằng nhau.
2) Xác định mức âm lượng $\Delta V$ đã được thêm vào đầu gối trái.
Piston trượt mà không có khiếu nại. Chất lỏng giữa piston và thành bình không bị cuốn lên và không tràn ra khỏi bình. Thể tích của lò xo có thể được xác định, chất lỏng không trộn lẫn và không di chuyển trong các khuỷu thẳng đứng khác. Gia tốc áp suất tự do là $g$.

Vì cả hai đầu của ống đều thông với khí quyển nên có thể bỏ qua áp suất khí quyển. Trạng thái cân bằng của piston ở vị trí ban đầu có dạng
$$\rho_1gh_1S = \rho_2gh_2S,$$
trong đó $h_1$ và $h_2$ lần lượt là chiều cao của cột chất lỏng phía trên tâm piston ở bên trái và bên phải. Khi một chất lỏng có mật độ $\rho_1$ được thêm vào bình bên trái, pít-tông sẽ di chuyển một khoảng $x$ sang phải và một lực đàn hồi bắt đầu tác dụng lên nó. Chúng ta hãy viết mức cân bằng của piston sau khi thêm một lượng chất lỏng nhất định:
$$\rho_1gH_1S = \rho_2gH_2S + kx.$$
Sau khi di chuyển piston một khoảng $x$, mức chất lỏng ở phía bên phải cũng sẽ tăng $x$, khi đó
$$\rho_1g(h_1 + y)S = \rho_2g(h_2 + x)S + kx,$$
trong đó $y$ là độ cao mà mức chất lỏng trong bình bên trái tăng lên. Để chênh lệch chiều cao $\Delta h$ không đổi, $y$ phải bằng $x$. Đó là lý do tại sao
$$k = \left(\rho_1 - \rho_2\right)gS.$$
Trạng thái cân bằng của piston sau khi thêm chất lỏng có khối lượng riêng $\rho_2$ vào bên trái thể tích $\Delta V$ có dạng
$$\rho_1g(h_1 - x)S + \rho_2gzS = \rho_2g(h_2 + x)S + kx.$$
Để các ranh giới trên của chất lỏng trùng nhau thì chiều cao $z$ của chất lỏng có mật độ $\rho_2$ cộng vào khuỷu tay trái phải bằng $\Delta h + 2x$. Sau đó, có tính đến hệ số độ cứng của lò xo tìm được,
$$x = \frac{\rho_2\Delta h}{2\left(\rho_1 - \rho_2\right)}.$$
Chúng ta hãy đảm bảo rằng khi piston di chuyển một khoảng $x$, chất lỏng có mật độ $\rho_1$ vẫn ở phần thẳng đứng bên trái của ống. Từ điều kiện cân bằng của piston ở thời điểm ban đầu
$$\rho_1gh_1S = \rho_2g(h_1 + \Delta h)S$$
chúng tôi nhận được
$$h_1 = \frac{\rho_2\Delta h}{\rho_1 - \rho_2}, h_1 > x.$$
Thể tích chất lỏng thêm vào có thể được tính bằng công thức
$$\Delta V = S\left(\Delta h + 2x\right),$$

⟦folio 27⟧

---
running_head:
folio:
---

chúng ta lấy nó từ đâu
$$\Delta V = \frac{\rho_1 \Delta h S}{\rho_1 - \rho_2}.$$
A. Vergunov

F2839. Một chuỗi mật không đổi, đồng nhất, mềm dẻo lý tưởng, có khối lượng m và chiều dài L, được treo bằng một sợi dây ngắn từ một nốt ruồi cố định A (hình 1,a). Tại một số thời điểm, sợi dây bị đốt cháy và các sợi xích bắt đầu kéo ở đầu dưới của nó với một lực F không đổi theo hướng nước tiểu A (hình 1, ​​​​b).
1) Với gia tốc tuyệt đối $a_0$, chúng ta bắt đầu di chuyển đầu trên của sợi xích ngay sau khi đốt cháy sợi dây?
2) Sau khi sợi dây bị đốt hết bao lâu thì toàn bộ sợi dây xích sẽ liền lại với nhau?
3) Xác định mô đun vận tốc của dây v ngay sau khi nó duỗi thẳng.
4) Hỏi cây chổi Q sẽ được thả ra trong thời gian τ là bao nhiêu?
5) Xác định lực căng T của sợi xích trong nước tiểu B, nằm ở giữa của nó, sau khi duỗi thẳng sợi xích.
Gia tốc trọng trường là g. Sức cản của không khí phải được khắc phục. Kích thước của zenevi trong chuỗi nhỏ hơn nhiều so với chiều dài của nó. Hãy coi rằng stolnova zeneviev trong chuỗi không co giãn.

Sau khi sợi dây bị đốt cháy, chiều dài của đoạn thẳng đứng của sợi xích, ở mép chịu lực F tác dụng, sẽ tăng lên. Một đoạn khác của dây xích có chiều dài giảm đi sẽ chỉ chuyển động dưới tác dụng của trọng lực, nghĩa là mô hình gia tốc của mép trên của dây xích ngay sau khi cháy hết và cho đến thời điểm dây xích đảo ngược hoàn toàn bằng
$$a_0 = g.$$
Theo định lý về chuyển động của khối tâm, gia tốc của khối tâm của dây hình chiếu lên trục y (hình 2) bằng
$$a_y = \frac{mg - F}{m} = g - \frac{F}{m}.$$

Trong thời gian τ, khối tâm của sợi dây sẽ dịch chuyển dọc theo trục y một khoảng $\frac{a_y \tau^2}{2}$. Cạnh trên của chuỗi sẽ di chuyển một khoảng $\frac{g \tau^2}{2}$ trong thời gian τ, nghĩa là
$$L + \frac{a_y \tau^2}{2} = \frac{g \tau^2}{2}.$$
Có tính đến sự tuân thủ nhận được,
$$\tau = \sqrt{\frac{2Lm}{F}}.$$
Đáp số có thể được trả lời theo cách khác cho cùng một câu hỏi. Hãy chuyển từ hệ thống báo cáo LABoratory sang hệ thống báo cáo không phần trăm, rơi xuống không có vận tốc ban đầu với gia tốc rơi tự do g. Trong hệ thống báo cáo này, một dây xích ban đầu đứng yên bắt đầu chuyển động dưới tác dụng của chỉ một lực F.
Và tổng lực hấp dẫn và lực quán tính tác dụng lên bất kỳ phần cơ bản (nhỏ) nào đều bằng 0. Trong trường hợp này, khối tâm của sợi dây chuyển động, theo định lý về chuyển động của khối tâm, với gia tốc $a' = F/m$ và đi được quãng đường L trong thời gian độc quyền τ. Điều này có nghĩa là $\tau = \sqrt{\frac{2L}{a'}}$, cho kết quả tương tự đáp số.
Sau thời gian τ, tất cả các phần của sợi dây chuyển động với cùng một tốc độ, bằng tốc độ khối tâm của nó. Do đó, $v = |v_y| = |a_y| \tau$, tức là
$$v = |g - \frac{F}{m}| \sqrt{\frac{2Lm}{F}}.$$

⟦folio 28⟧

---
running_head:
folio:
---

Đáp số có thể đạt được tại thời điểm này và cũng có thể sử dụng việc chuyển sang hệ thống báo cáo phi quán tính. Tốc độ trong hệ thống báo cáo này ngay sau khi đảo ngược chuỗi bằng
$$v' = a'\tau = \frac{F}{m} \sqrt{\frac{2Lm}{F}} = \sqrt{\frac{2FL}{m}}$$
và hướng lên trên. Lúc này hệ thống báo cáo đã chọn sẽ di chuyển xuống với tốc độ
$$v_c = g\tau = g \sqrt{\frac{2Lm}{F}}.$$
Khi chuyển báo cáo trở lại hệ thống phòng thí nghiệm, có tính đến định luật cộng vận tốc, chúng ta thu được
$$v_y = v_c - v' = \left( g - \frac{F}{m} \right) \sqrt{\frac{2Lm}{F}}.$$
Có nghĩa là $v = |v_y|$.
Công $A_F$ của lực $F$ bằng tổng độ biến thiên cơ năng $\Delta E_{\text{мек}}$ của dây xích và lượng nhiệt tỏa ra $Q$:
$$A_F = \Delta E_{\text{мек}} + Q,$$
Ở đâu
$$A_F = F \left( L - \frac{a_y \tau^2}{2} \right), \Delta E_{\text{мек}} = \frac{mv^2}{2} - mg \frac{a_y \tau^2}{2}.$$
Từ đây là
$$Q = FL.$$
Trong hệ thống báo cáo phi quán tính, khi dây xích quay hoàn toàn thì điểm tác dụng của lực $F$ sẽ chuyển sang $2L$ nên công của nó bằng $2FL$. Độ biến thiên động năng của dây chuyền là
$$\frac{mv'^2}{2} = FL.$$
Khi tính đến điều này, chúng tôi tìm thấy lượng nhiệt thoát ra:
$$Q = 2FL - FL = FL.$$
Sau khi làm thẳng sợi xích, chúng ta chọn sợi chỉ dưới (bên dưới điểm $B$) có khối lượng $m/2$ và viết cho phần này định lý về chuyển động của khối tâm khi chiếu lên trục $y$:
$$\frac{m}{2} a_y = \frac{m}{2} g - T.$$
Kết quả là chúng tôi nhận được
$$T = \frac{F}{2}.$$
Xét chuyển động trong hệ báo cáo không quán tính, nửa dưới của dây xích sau khi quay sẽ chịu tác dụng của một lực
$$T = \frac{m}{2} a' = \frac{F}{2}.$$
A. Kireev
F2840. Chúng ta hãy xem xét hai quá trình $A$ và $B$, trong mỗi thành phần trong mô hình khí lý tưởng đơn nguyên tử, chúng được chuyển gần như tĩnh từ trạng thái 1 với thể tích $V$ và nhiệt độ $T$ sang trạng thái 2 với thể tích $2V$ và nhiệt độ $2T$ để trong toàn bộ quá trình nhiệt độ của khí không giảm và chất tan không bị loại bỏ khỏi khí. Trong trường hợp này, quy trình A được thực hiện sao cho lượng nhiệt cung cấp cho khí đạt mức tối đa có thể khi các điều kiện này được đáp ứng, và trong quy trình B, lượng nhiệt là tối thiểu.
1) Xác định giá trị $V_A^{\max}, V_B^{\max}$ tối đa và tối thiểu $V_A^{\min}, V_B^{\min}$ ​​của vật thể khí trong mỗi quá trình này.
2) Lượng nhiệt $Q_A$ và $Q_B$ được cung cấp trong mỗi quá trình là bao nhiêu?
Chính xác một đường đẳng nhiệt đi qua bất kỳ điểm nào tương ứng với trạng thái của khí trong tọa độ $pV$. Các đường đẳng nhiệt không giao nhau và nhiệt độ cao hơn tương ứng với các đường đẳng nhiệt nằm ở trên. Khi khí chuyển từ trạng thái 1 sang trạng thái 2, điểm tương ứng với trạng thái của nó không thể chuyển từ đường đẳng nhiệt “trên” sang đường đẳng nhiệt “thấp”, vì nhiệt độ của khí không giảm và quỹ đạo của quá trình nằm giữa các đường đẳng nhiệt đi qua các điểm này.
Nếu bây giờ chúng ta xem xét theo cách tương tự trên cùng một mặt phẳng $pV$ của các họ đoạn nhiệt, thì điểm tương ứng với trạng thái của chất khí không thể chuyển từ đoạn nhiệt “trên” sang đoạn nhiệt “thấp”, vì vật không được tách ra khỏi khí, do đó, quỹ đạo của quá trình nằm ở đoạn đoạn nhiệt đi qua điểm 1 và 2.
Hãy chứng minh rằng lượng nhiệt tối đa trong một quá trình như vậy được cung cấp cho khí nếu nó đoạn nhiệt lần đầu tiên.

⟦folio 29⟧

---
running_head:
folio:
---

chuyển từ trạng thái 1 sang trạng thái 3, sau đó đẳng nhiệt từ trạng thái 3 sang trạng thái 2 (xem hình). Xét chu trình 1-3-2-1, giả sử việc chuyển từ trạng thái 2 sang trạng thái 1 là tùy ý, nằm bên trong tứ giác cong 1-3-2-4-1. Công trong chu trình này bằng hiệu giữa lượng nhiệt cung cấp ở phần 1-3-2 $Q_{132}$ và lượng nhiệt loại bỏ trong quá trình chuyển tiếp 2-1 $Q_{21}$. Vì công việc là tích cực, nên
$$Q_{132} > Q_{21}.$$
Vì quy trình 2-1 được chọn tùy ý (với các hạn chế về nguồn cung cấp nhiệt và thay đổi nhiệt độ được chỉ định trong các điều kiện), nên các giá trị $Q_{132}$ tương ứng với giá trị tối đa của lượng nhiệt có thể được cung cấp trong quá trình chuyển đổi như vậy. Tương tự, có thể chứng minh rằng lượng nhiệt tối thiểu có thể tương ứng với một quá trình trong đó khí đầu tiên giãn nở đẳng nhiệt từ trạng thái 1 đến trạng thái 4, sau đó trải qua quá trình giãn nở đoạn nhiệt, chuyển từ trạng thái 4 sang trạng thái 2.
Hãy để chúng tôi trình bày phân tích về bản chất của các quá trình $A$ và $B$ theo cách khác - sử dụng khái niệm entropy. Các quá trình $A$ và $B$ diễn ra sao cho trong toàn bộ quá trình, nhiệt độ của khí không giảm và nhiệt không bị loại bỏ khỏi khí, có nghĩa là entropy trong các quá trình này không thể giảm. Lượng nhiệt được cung cấp $\delta Q$ và sự thay đổi entropy $dS$ có liên quan với nhau bởi hệ thức
$$\delta Q = TdS.$$

Quá trình $A$ tiến hành với lượng nhiệt đầu vào tối đa có thể, có nghĩa là trong quá trình này, tất cả nhiệt đầu vào phải được truyền ở nhiệt độ tối đa có thể, tương ứng với quá trình trong đó khí đầu tiên được nén đẳng nhiệt từ trạng thái 1 đến trạng thái 3, sau đó giãn nở đẳng nhiệt, chuyển từ trạng thái 3 sang trạng thái 2. Quá trình $B$ tiến hành với lượng nhiệt đầu vào tối thiểu có thể, có nghĩa là trong quá trình này, mọi thứ được cung cấp nhiệt phải được truyền ở nhiệt độ thấp nhất có thể, sau đó hệ thống phải được chuyển sang trạng thái 2 mà không cần cấp nhiệt. Điều này tương ứng với một quá trình trong đó khí đầu tiên giãn nở đẳng nhiệt từ trạng thái 1 sang trạng thái 4, sau đó giãn nở adinabati, chuyển từ trạng thái 4 sang trạng thái 2.
Chúng ta chuyển sang tính thể tích tương ứng với điểm 3 và 4. Phương trình nối các biến $T$ và $V$ trong quá trình tính toán có dạng
$$TV^{\gamma-1} = \text{const},$$
trong đó $\gamma$ là chỉ báo adinabata. Trong trường hợp khí lý tưởng đơn nguyên tử, $\gamma = 5/3$ và $TV^{2/3} = \text{const}$. Đối với quá trình $A$
$$TV^{2/3} = 2T\left(V_{A}^{\min}\right)^{2/3}, V_{A}^{\min} = \frac{V}{2\sqrt{2}}.$$
Rõ ràng là $V_{A}^{\max} = 2V$. Đối với quá trình $B$
$$2T \cdot (2V)^{2/3} = T\left(V_{B}^{\max}\right)^{2/3}, V_{B}^{\max} = 4\sqrt{2}V.$$
Tất nhiên, $V_{B}^{\min} = V$.
Nhiệt trong các quá trình này được cung cấp thông qua các đường đẳng nhiệt. Lượng nhiệt trong một quá trình đẳng nhiệt bằng công mà khí thực hiện. Đối với quá trình $A$
$$Q_{A} = 2vRT \ln \frac{V_{2}}{V_{3}} = 5vRT \ln 2,$$
cho quá trình $B$
$$Q_{B} = 2vRT \ln \frac{V_{4}}{V_{1}} = \frac{5}{2}vRT \ln 2.$$
A. Apollonsky
