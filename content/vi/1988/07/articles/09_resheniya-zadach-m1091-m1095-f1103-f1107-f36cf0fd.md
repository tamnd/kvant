---
id: 1988-7-resheniya-zadach-m1091-m1095-f1103-f1107-f36cf0fd
issue: kvant_1988_7
year: 1988
number: "7"
title: Lời giải bài toán M1091—M1095; F1103—F1107
rubric: zadachnik-kvanta
rubric_sub: Задачник «Кванта»
page_first: 38
page_last: 45
page_labels: 36, 37, 38, 39, 41, 42, 43
tag: FV99
lang: vi
source: kvant_digital
extraction: vision
content_sha256: f3ba57df80e868281ca9d054feee5d216dc4368c8826d262b3c0a691fb888015
prompt_sha256: draft-1
translated_from: content/ru/1988/07/articles/09_resheniya-zadach-m1091-m1095-f1103-f1107-f36cf0fd.md
source_content_sha256: 99a4f4e221cd8e8954b5b7e5ff832f6ae0b3c6f3f6d17bb2f4c7e1a2a140e1e8
translation_model: draft
translation_run: vi-draft-2026-10-31
translation_quality: draft
---

⟦folio 36⟧

Lời giải bài toán

M1091. Giả sử một số tự nhiên thành công nếu các chữ số trong ký hiệu thập phân của nó có thể được chia thành hai nhóm sao cho tổng các chữ số trong các nhóm này bằng nhau.
a) Tìm số a nhỏ nhất sao cho a và a+1 là số may mắn.
b) Có tồn tại các số a, a+1 và a+2 là may mắn không?

M1092. Một hình đa giác lồi được cắt ra từ giấy được gấp 10 lần (làm theo một số đường thẳng) rồi cắt thành một đường thẳng. Số mảnh lớn nhất có thể thu được là bao nhiêu?

Đáp số: a=549. Rõ ràng tổng các chữ số của một số bất kỳ là số chẵn. Do đó, nếu a và a+1 là số may mắn thì a sẽ bằng 9 (nếu không thì các chữ số của hai số này có số chẵn lẻ khác nhau). Rõ ràng là a không thể có hai giá trị (99+1=100). Nếu số a có ba chữ số, tức là a=xy9 (thanh có nghĩa là ký hiệu thập phân), thì y<9 và a+1=x(y+1)0. Do đó, x+y=9, x=y+1. Do đó x=5, y=4.

6) Đáp số: không tồn tại. Như có thể thấy từ lời giải bài toán a), cả hai số - a và a+1 - phải bằng 9, nhưng điều này là không thể.

N. I. Zilberer

Đáp số: 1025. Hãy giải ngay bài toán trong trường hợp tổng quát cho n mũi nhọn. Chúng ta hãy vẽ một đoạn AB tùy ý bên trong đa giác và đánh dấu trên đó các điểm C₁, C₂, ..., Cₙ+1 và cả CₙB=2⁻k·AB (xem hình). Qua mỗi điểm Cₙ ta vẽ đường thẳng lₖ vuông góc với AB. Chúng ta lần lượt uốn đa giác dọc theo các đường thẳng l₁, l₂, ..., lₙ từ trái sang phải n lần (giả sử ban đầu điểm A nằm bên trái B) và cắt nó dọc theo đường thẳng lₙ+1. Đoạn AB sẽ được gấp thành đoạn CₙB, trên đó hình gấp có 2ⁿ lớp. Ở bên trái của vết cắt, mỗi lớp được kết nối với một lát cắt khác thông qua phần uốn cong lₙ, vì vậy chúng ta nhận được 2ⁿ−1 đoạn từ. Ở bên phải của vết cắt, các lớp cũng được kết nối theo cặp, ngoại trừ hai từ dưới cùng duy nhất - các cạnh của hình gốc. Do đó, ở bên phải sẽ có 2ⁿ−1+1 quân và tổng cộng sẽ có 2ⁿ+1 quân.

Hãy để chúng tôi chỉ ra bằng cách chỉ ra số lần uốn n rằng số lượng mảnh không thể nhiều hơn 2ⁿ+1. Với n=0 thì phát biểu này là hiển nhiên. Giả sử nó đúng với n biến tố. Hãy uốn cong đa giác n+1 lần. Sau lần uốn cong đầu tiên, thu được hai lớp đa giác chồng lên nhau một phần được kết nối với nhau. Trong tương lai, mỗi từ này có thể được xem xét riêng biệt: nó sẽ được uốn cong và cắt n lần, theo giả định của chỉ dẫn, sẽ là 2ⁿ+1 mảnh. Vì ít nhất hai phần từ các từ khác nhau phải được kết nối thông qua một biến cách nên tổng số phần không vượt quá 2(2ⁿ+1)-1=2ⁿ−1+1.

Như vậy, số lượng mảnh tối đa là 2ⁿ+1; cụ thể, với n=10 chúng ta nhận được 2¹⁰+1=1025 miếng.

S. V. Kazakov

Đáp số trong bài toán a): n−k+1.
a), 6) Hãy chia các điểm thành các “chuỗi”, mỗi điểm bắt đầu bằng hai và bao gồm các điểm tiếp theo

⟦folio 37⟧

nhưng tại tất cả các điểm, các phép biến đổi sau được thực hiện: mỗi số 2 được thay thế bằng 0, sau đó đến số tiếp theo dọc theo mũi tên số hình trụ bằng $k \ge 1$.

a) Sau bao nhiêu phép biến đổi chắc chắn không còn một hai phép biến đổi nào?

b) Ngoài ra, tại $n-k$ các điểm còn lại ban đầu chứa các điểm 1. Chứng minh rằng cuối cùng sẽ còn lại $k$ số một và $n-k$ số không.

(theo chiều kim đồng hồ) đơn vị. Nếu chuỗi bắt đầu tại điểm $A_1$, thì nó sẽ kết thúc trước điểm $A_2$ (trong đó có hai hoặc một số 0 - trên hình 1, ​​điều này được biểu thị bằng một ngôi sao)

Con gái) và bao gồm $m \ge 0$ đơn vị, thì sau $m+1$ bước tại $m$ điểm theo sau $A_1$ sẽ có $m$ số 0 và tại điểm $A_2$ sẽ có một số 0. Hình 2, a, b, c mô tả sự phát triển của một chuỗi cho $m=0$, $m=1$ và $m=4$ ($\emptyset$ có nghĩa là 0 hoặc 1). Sự tiến hóa này xảy ra đồng thời với tất cả các chuỗi. Do đó, nếu lúc đầu có $k$ hai số tại các điểm $A_1$, $A_2$, ..., $A_k$ và chuỗi dài nhất chứa $m \le n-k$ số một, thì chính xác sau các phép biến đổi $m+1$ sẽ không còn một hai số nào. Nếu đồng thời có các số 1 ở các điểm $n-k$ còn lại, thì sau tất cả các phép biến đổi sẽ có các số 0 ở vị trí của chúng và tại $k$ các điểm $A_1$, $A_2$, ..., $A_k$ - các số một.

N. V. Vasiliev

M1094. Đặt $a, b, c$ là số không âm.
a) Chứng minh rằng từ bất đẳng thức $a^4+b^4+c^4 \le 2(a^2b^2+b^2c^2+c^2a^2)$ (1)
bất đẳng thức $a^2+b^2+c^2 \le 2(ab+bc+ca)$ theo sau. (2)
b) Điều ngược lại có đúng không: bất đẳng thức (2) kéo theo bất đẳng thức (1)?

a) Biến đổi hiệu giữa vế phải và vế trái của (1):
$$D=2(a^2b^2+b^2c^2+c^2a^2)-(a^4+b^4+c^4)=4a^2b^2-(a^2+b^2)^2+2c^2(a^2+b^2)-c^4=(2ab)^2-(a^2+b^2-c^2)^2.$$
Nếu $D \ge 0$ thì $2ab \ge |a^2+b^2-c^2|$. Vì các chữ cái $a, b, c$ được đưa vào trong điều kiện đối xứng hoàn hảo nên chúng ta có thể giả sử $a \ge b \ge c$. Sau đó $a^2+b^2+c^2=|a^2+b^2-c^2|+2c^2 \le 2ab+2c^2 \le 2(ab+bc+ca)$.
6) Đáp số: không đúng. (Ví dụ: $a=4$, $b=c=1$.)
Lưu ý rằng, tiếp tục biến đổi hiệu $D$, chúng ta có thể phân tách nó thành các thừa số tuyến tính:
$$D=(a+b+c)(a+b-c)(a+c-b)(b+c-a).$$
Ở đây chỉ có một dấu ngoặc đơn (trong đó số lớn nhất $a, b, c$ bị trừ) có thể âm. Do đó, (1) tương đương với điều kiện mỗi số $a, b, c$ không lớn hơn tổng của hai số còn lại. Tương tự, (2) tương đương với việc nói rằng mỗi số $\sqrt{a}, \sqrt{b}, \sqrt{c}$ không lớn hơn tổng của hai số còn lại. Từ đây thật dễ dàng để có được một lời giải bài toán a): xét cho cùng, nếu $b+c \ge a$ thì $(\sqrt{b}+\sqrt{c})^2 \ge b+c \ge a$ và $\sqrt{b}+\sqrt{c} \ge \sqrt{a}$.
Biểu thức $D$ xuất hiện trong công thức Heron tính diện tích hình tam giác có cạnh $a, b, c$ (diện tích này bằng $\sqrt{D}/4$); một tam giác như vậy tồn tại nếu $D > 0$.

⟦folio 38⟧

M1095*. Trên mặt phẳng, cho đường tròn tâm O và hai điểm A, B (khác O) sao cho đường thẳng AB đi qua điểm O. Dựng dây MN của đường tròn này, nhìn từ điểm A một góc α và a) song song với đường thẳng AB; b) đi qua điểm B. (Nếu B nằm ngoài đường tròn thì đoạn dài của dây MN phải đi qua B.)

Hình 1.

Hình 2.

Đối với bất kỳ đường thẳng nào đi qua một điểm P tùy ý và cắt một đường tròn cho trước, PX $\times$PY = $|d^2 - R^2|$, trong đó X và Y là giao điểm, d = PO là khoảng cách từ P đến tâm O của đường tròn, R là bán kính của đường tròn. (Từ sự đồng dạng của các tam giác PXX1 và PY1Y suy ra PX $\cdot$PY = PX1 $\times$PY1 = $(d + R)|d - R|$).

Theo những gì đã được chứng minh, đoạn MM1 thu được sẽ có độ dài cần thiết. Bây giờ, sử dụng thực tế là đối với dây cung gốc MN, góc MN1N đã biết (nó bằng α) và khoảng cách ON=OM=R, chúng ta có thể xây dựng một đoạn bằng dây cung này. Để làm điều này, chỉ cần vẽ một tia ở góc α với đoạn MM1 đã được tạo từ đầu M1 của nó và đánh dấu các điểm giao nhau của tia này với đường tròn đã cho. Có thể có 0, 1 hoặc 2 điểm như vậy (hình 3). Các đoạn nối các điểm này với M cho giá trị có thể có của độ dài của dây cung ban đầu. Vẫn còn phải dựng trong một đường tròn cho trước một dây có độ dài đã biết song song với đường thẳng AB đã cho. Vì độ dài đã biết này có giá trị 0, 1 hoặc 2 nên bài toán của chúng tôi có thể có 0, 2 hoặc 4 lời giải. (Người đọc sẽ tự thấy 4 lời giải bài toán có thể có gì nếu điểm A nằm ngoài đường tròn đã cho; ví dụ về tình huống như vậy được đưa ra ở hình 4.)

6) Một lần nữa chúng ta giả sử rằng dây cung mong muốn MN được xây dựng (hình 5). Chúng ta vẽ đường tròn AMN và ký hiệu nó bằng các đường thẳng AB và MO ($C \neq A, M_1 \neq M$). Hoá ra vẫn thế

⟦folio 39⟧

Rằng độ dài của đoạn $MM_1$ không phụ thuộc vào góc đã cho. Để chứng minh điều đó, bạn cần áp dụng định lý trên (hình2) nhiều lần:
$$BC \cdot BA = BM \cdot BN = BE \cdot BF,$$
trong đó $E$ và $F$ là giao điểm của đường tròn ban đầu với $AB$; điều này có nghĩa là vị trí của điểm $C$ không phụ thuộc vào góc đã cho và một lần nữa

$$OM_1 \cdot OM = OA \cdot OC.$$

Hơn nữa, lời giải hầu như không khác lời giải bài toán a), chỉ có điều lần này cần xây dựng không phải một dây có độ dài cho trước, song song với một đường cho trước, mà là một dây có độ dài cho trước, phần mở rộng của dây đó đi qua một điểm cho trước. Cũng cần lưu ý rằng đối với một số vị trí của các điểm $A$ và $B$ (ví dụ: xem hình 6), góc $MM_1N$ có thể bằng $\pi - \alpha$ chứ không phải $\alpha$.

Hình 4.

Bạn có thể tránh liệt kê các trường hợp nếu sử dụng khái niệm "góc định hướng": góc từ đường thẳng $AM$ đến đường thẳng $AN$, vắng mặt, chẳng hạn, ngược chiều kim đồng hồ, sẽ luôn bằng góc từ $M_1M$ đến $M_1N$, vắng mặt theo cùng một hướng. Vẫn bài toán có 0, 2 hoặc 4 lời giải.

R. O. Burdin

F1103. Một cuốn sách toán có chiều dài $l$ được trình bày tại điểm $A$ trên một hình nón có góc khoảng cách $2\beta$ (hình 1). Tấm matnik sẽ đi được bao xa trước khi nó tách ra khỏi bề mặt hình nón nếu tấm matnik bị đẩy nhẹ ra khỏi vị trí cân bằng của nó? Góc nghiêng của hình nón so với mặt đất là $\alpha$ thì bề mặt của hình nón được coi là nhẵn.

Vì đầu trên của sợi chỉ được cố định nên matnik sẽ chuyển động theo vòng tròn cho đến khi tách khỏi bề mặt hình nón. Mặt phẳng của đường tròn này nghiêng một góc $(\pi/2 - \alpha)$ so với đường chân trời, bán kính của nó là $r = l \sin \beta$. Khi nó co lại khỏi hình nón, tốc độ của điểm $A$ tăng lên, nghĩa là gia tốc hướng tâm của nó cũng phải tăng lên. Tại một số thời điểm, lực tác dụng lên tấm thảm có thể không “đủ” để tiếp tục chuyển động quanh vòng tròn, khi đó điểm $A$ sẽ bị tách ra khỏi bề mặt hình nón.

Chúng ta hãy xem xét các lực tác dụng lên điểm $A$ khi nó di chuyển dọc theo một hình nón. Đó là lực hấp dẫn $m\vec{g}$, lực căng chỉ $\vec{T}$ và phản lực mặt đất $\vec{N}$ (hình 2). Tại thời điểm tách, lông mao của phản ứng trở thành số không. Điều này sẽ được sử dụng cho đáp số để đặt câu hỏi bài toán.

Hãy giới thiệu hệ tọa độ như hình hình 2: hướng trục $X$ dọc theo bán kính về tâm đường tròn, trục $Y$ - dọc theo tiếp tuyến với đường tròn và trục $Z$ -

⟦folio 41⟧

Hãy vẽ từ điểm $E$ thẳng $EF \parallel DN$. Điều kiện xảy ra tương đương với điều kiện hình thành tam giác từ các đoạn $ME$ và $EF=DN$ (bằng độ dài của các sợi) và đoạn $MF=|MN|-ED$ (bằng hiệu độ dài của các thanh):

$$MF > |EM|-DN|.$$

Do đó, nếu hiệu độ dài của các thanh lớn hơn hiệu độ dài của các sợi ren thì các thanh song song, nếu không thì các ren song song. Cụ thể, nếu các thanh bằng nhau thì ren song song; nếu các ren bằng nhau thì các thanh song song. Nếu độ dài của thanh và ren chênh lệch nhau thì cả thanh và ren đều nằm trên phương thẳng đứng $OA$.

V. T. Karpetyan

F1105. Một đĩa kim loại có bán kính $r=10$ cm được gia công trong mặt phẳng nằm ngang với tốc độ $v=60$ vòng/phút. Từ độ cao $H=10$ cm, một khối phẳng rơi xuống nó, khối lượng của khối này nhỏ hơn nhiều so với khối lượng của cái đĩa. Cạnh dưới của khối luôn song song với mặt phẳng của đĩa, hệ số ma sát giữa kim loại và mặt phẳng là $\mu=0,1$. Khối này phải rơi cách trục một khoảng bằng bao nhiêu để khi gắn lại nó sẽ rơi ra ngoài đĩa? Giả sử rằng sau khi bật lại khối sẽ tăng lên độ cao trước đó; Bỏ qua kích thước của khối.

Để khối, khi áp dụng lần đầu tiên, chạm vào đĩa tại điểm $A$, nằm cách tâm đĩa một khoảng $x$ (xem hình). Trong khi va chạm, có hai lực tác dụng lên khối từ phía của đĩa - hướng thẳng đứng, phản lực hỗ trợ $\vec{N}$ và hướng ngang, lực ma sát $\vec{F}_{\text{тр}}$. Giả sử rằng trong toàn bộ vụ va chạm, tốc độ của khối so với đĩa nhỏ hơn tốc độ tuyến tính $v_A = \omega x = 2\pi vx$ của đĩa điểm $A$, chúng ta luôn đạt được điều đó $F_{\text{тр}} = \mu N$. Khi đó xung truyền từ đĩa tới khối theo hướng ngang tương ứng có liên quan đến xung truyền tới khối theo hướng ngang.

$$P_r = \mu P_B.$$

Ở phía bên kia,

$$P_r = mv,$$

trong đó $m$ là khối lượng của khối, $v$ là tốc độ nằm ngang của nó sau va chạm,

$$P_B = 2mv_0,$$

trong đó $v_0 = \sqrt{2gh}$ là vận tốc thẳng đứng của vật ngay trước khi va chạm. Từ đây là

$$v = 2\mu v_0 = 2\mu \sqrt{2gh}.$$

Trong khoảng thời gian $\tau = 2t_{\text{пяд}} = 2\sqrt{2h/g}$ giữa lần va chạm thứ nhất và thứ hai, khối sẽ bay một quãng đường theo phương ngang

$$l = v\tau = 8\mu h.$$

Theo điều kiện, bài toán phải thỏa mãn

$$l > \sqrt{r^2 - x^2},$$

tức là

$$x > \sqrt{r^2 - l^2} = \sqrt{r^2 - (8\mu h)^2} = 6 \text{ см.}$$

Hãy kiểm tra xem điều kiện $v < v_A$ có được thỏa mãn hay không:

$$v = 2\mu \sqrt{2gh} \approx 28 \text{ см/c},$$

$$v_A = 2\pi vx \approx 38 \text{ см/c} > v.$$

Vì vậy, khối đầu tiên phải rơi vào đĩa ở khoảng cách ít nhất 6 cm so với tâm của nó.

L. A. Zakrevsky

⟦folio 42⟧

F1106. Đôi lời về hướng dẫn viên miền Bắc. Các dây dẫn phía bắc có đặc tính đẩy ra một từ trường (còn gọi là hiệu ứng Meissner), nhờ đó chúng có thể nổi phía trên một nam châm. Tính năng này của các dây dẫn phía bắc được cho là sẽ được sử dụng để tạo ra các đoàn tàu cao tốc phía bắc trên cơ sở “bay từ trường”, các nguyên mẫu đã được thử nghiệm. Và bây giờ là bài toán chính cô ấy. Theo hướng bắc, một mẫu có khối lượng m lơ lửng phía trên một nam châm vĩnh cửu được đặt trên một tải trọng có cùng khối lượng. Phải tăng cảm ứng từ của từ trường do nam châm tạo ra bao nhiêu lần để vật dẫn phía bắc mang tải lơ lửng cách nam châm một khoảng bằng nhau?

F1107. Tuyết mịn mới rơi nhân tạo dưới ánh mặt trời. Ước tính khoảng cách đặc trưng giữa các “tia lửa” riêng lẻ.

Chúng ta sẽ giả sử rằng các mảng tuyết trong lớp phủ tuyết là những tấm gương phẳng được định hướng ngẫu nhiên có cùng diện tích khoảng 10 mm².

Mỗi tấm gương bông tuyết phản chiếu ánh sáng dưới dạng chùm tia phân kỳ. Góc phân kỳ bằng kích thước góc của Mặt trời $a \approx 0,5^\circ$. Xác suất $q$ để ánh sáng phản xạ từ một bãi tuyết định hướng ngẫu nhiên chạm vào một điểm cho trước $A$ (xem hình) bằng tỷ lệ giữa diện tích đáy của hình nón chùm ánh sáng với diện tích bán cầu đi qua các điểm $A$ (tâm bán cầu nằm trên bãi tuyết). Xét rằng chiều cao của hình nón ánh sáng gần bằng bán kính của bán cầu, ta thấy

$$q = \frac{\pi r^2}{\pi R^2} = \frac{\pi R^2 \text{tg}^2 \alpha/2}{\pi R^2} = \text{tg}^2 \alpha/2 \approx \frac{\alpha^2}{4},$$

trong đó $R$ là bán kính của bán cầu hoặc khoảng cách từ bãi tuyết đến điểm được quan sát, $r$ là bán kính của đáy chùm tia sáng.

Trên một mét vuông tuyết phủ phía bắc có $n \approx 10^5$ bông tuyết và ánh sáng từ các hạt $qn$ sẽ chạm tới điểm $A$.

Để ước tính khoảng cách đặc trưng giữa các “tia lửa” riêng lẻ, chúng ta sẽ giả sử rằng các mảng tuyết phát sáng nằm trên bề mặt của bề mặt ánh sáng, chẳng hạn như trên tâm của các hình lục giác xếp sát nhau. Khi đó diện tích của một là sáu

⟦folio 43⟧

Góc $S_0$ và khoảng cách đặc trưng giữa các tia lửa $d$ có liên quan đến các quan hệ

$$S_0 = \frac{\sqrt{3}}{2} d^2,$$

nó đến từ đâu?

$$d \approx 60 \text{ см.}$$

Khi quan sát những bông tuyết trong thực tế, người ta phải tính đến khả năng thị giác sinh học của con người. Ở khoảng cách ngắn, người ta quan sát thấy: đường kính của chùm sáng nhỏ hơn khoảng cách giữa hai con ngươi và mỗi mắt nhìn thấy tia lửa “của riêng mình”. Ở khoảng cách lớn ($R > 30$ m), đường kính của chùm ánh sáng từ một bông tuyết riêng lẻ trở thành một bậc có độ lớn lớn hơn khoảng cách giữa các con ngươi và có thể sử dụng mô hình “người quan sát chính xác”, như đã thực hiện ở trên.

Lưu ý rằng tuyết lấp lánh có thể được quan sát không chỉ vào ban ngày mà còn vào ban đêm, chẳng hạn như dưới ánh đèn đường. Hãy nhớ A. A. Fet:

Tiếng bước chân cọt kẹt dọc con phố trắng.
Ánh đèn ở phía xa.
Trên những bức tường đóng băng
Pha lê lấp lánh.

E. N. Yunosov, I. V. Yaminsky

Đơn hàng được chấp nhận...

(Để bắt đầu, xem trang 22)

Mục đích của cuốn sách là giới thiệu cho người đọc không chuyên về những sự thật cơ bản của vật lý lượng tử và lịch sử khám phá chúng.

95. Tarbeev Yu. V. Đại lượng vật lý. Edinet. Tiêu chuẩn. Hằng số. 1 chà. 10k.

Các khái niệm đo lường cơ bản, tên và cách xác định các đại lượng vật lý, các giá trị chính xác và đáng tin cậy nhất của các đại lượng vật lý cũng như đơn vị của đại lượng vật lý được trình bày dưới dạng ngắn gọn và dễ tiếp cận.

96. Yavorsky B. M., Seleznev Yu. A. Hướng dẫn tham khảo vật lý cho người đăng ký vào đại học và tự học. 1 chà. 90k.

Sách hướng dẫn này chứa thông tin về tất cả các phần vật lý được nghiên cứu ở các trường trung học cơ sở và các cơ sở giáo dục chuyên ngành trung học cơ sở.

108. Butikov E. I., Bykov A. A., Kondratiev A. S. Vật lý trong các ví dụ và bài toán. 1 chà.

Mục tiêu của tác giả là dạy người đọc cách suy luận, giúp người đọc hiểu sâu sắc về các hiện tượng đang được xem xét. Phiên bản mới phản ánh những thay đổi mới nhất về nội dung các môn vật lý bậc trung học cơ sở và các chương trình thi đại học mang tính cạnh tranh.

109. Gursky I. P. Vật lý cơ bản với các ví dụ lời giải bài toán. 1 chà. 10k.

Toàn bộ khóa học vật lý cơ bản được ôn tập một cách nhất quán và ngắn gọn. Mục tiêu của tác giả là giúp người nộp đơn lặp lại khóa học vật lý với mức đầu tư thời gian tối thiểu.

110. Meledin G.V. Bài toán vật lý: Bài thi bài toán có lời giải. 70k.

Chứa bản tóm tắt 500 bài toán được cung cấp trong kỳ thi tuyển sinh viết môn vật lý tại Đại học bang Novosibirsk.
