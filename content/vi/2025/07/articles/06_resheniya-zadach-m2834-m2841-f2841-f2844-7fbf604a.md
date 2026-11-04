---
id: 2025-7-resheniya-zadach-m2834-m2841-f2841-f2844-7fbf604a
issue: kvant_2025_7
year: 2025
number: "7"
title: Lời giải bài toán M2834—M2841; F2841—F2844
rubric: zadachnik-kvanta
rubric_sub: Задачник «Кванта»
page_first: 29
page_last: 38
page_labels: 27, 28, 29, 30, 31, 32, 33, 34, 36
lang: vi
source: kvant_digital
extraction: vision
content_sha256: c12b451cfde02a84346d0f80d5000ddf48bbb9d97f928592429e7301b5e85626
prompt_sha256: draft-1
translated_from: content/ru/2025/07/articles/06_resheniya-zadach-m2834-m2841-f2841-f2844-7fbf604a.md
source_content_sha256: 3b08b22751709b897534b76d1c650a6fad163d5b8ebc08ed77a0792b1a1d19d2
translation_model: draft
translation_run: vi-draft-gaps-2026-11-04
translation_quality: draft
---

⟦folio 27⟧

Lời giải bài toán M2834-M2841, F2841-F2844

M2834. Ta gọi một tập hợp số là may mắn nếu nó không thể chia nó thành hai nhóm không rỗng sao cho tích của tổng các số trong nhóm này và tổng các số trong nhóm kia là dương. Giáo viên viết một số số nguyên lên bảng. Chứng minh rằng á nhân có thể cộng thêm một số nguyên 马克 vào các số hiện có để tập kết quả thành công.

Gọi tổng các số do giáo viên viết ra bằng $S$; thì các bé chỉ cần cộng số $-S$. Thật vậy, sau đó tổng của tất cả các số đều bằng 0, nghĩa là khi chia chúng thành hai nhóm thì tổng trong các nhóm sẽ là những số đối diện nhau. Vì vậy, sản phẩm của họ sẽ không tích cực.

A. Kuznetsov

⟦folio 28⟧

---
running_head:
folio:
---

M2835. Mỗi bảng $2 \times 200$ chứa một đồng rúp. Dasha và Sonya tserrat lần lượt thực hiện các động tác tấn công Dasha. Trong một lần di chuyển, bạn có thể chọn bất kỳ đồng xu nào và di chuyển nó: Dasha di chuyển đồng xu đến thiết bị đầu cuối theo đường chéo liền kề, Sonya di chuyển nó sang cạnh liền kề. Nếu hai đồng xu rơi vào cùng một thiết bị đầu cuối, một trong số chúng có thể được lấy ra khỏi bảng và đưa cho Sonya. Sonya có thể để lại cerra bằng bất kỳ đồng xu nào và lấy tất cả số xu cô ấy nhận được. Chiến thắng lớn nhất mà cô ấy có thể nhận được là gì, cho dù Dasha muốn bao nhiêu?

Đáp số: 300.
Đầu tiên, hãy đưa ra chiến lược cho Sonya. Chỉ cần cô ấy chưa nhận được quá 299 xu thì còn lại ít nhất 101 xu trên bàn cờ trước khi cô ấy di chuyển. Chia bảng thành 100 ô vuông $2 \times 2$. Hóa ra có hai đồng xu nằm trong cùng một hình vuông $2 \times 2$. Nếu hai đồng xu này ở cạnh nhau thì Sonya đẩy đồng xu này lên đồng xu kia và nhận được một đồng xu khác. Nếu các đồng xu được đặt theo đường chéo thì Sonya sẽ di chuyển một trong số chúng vào cột cạnh cột kia (sau đây, cột có chiều dài là 2, hàng có chiều dài là 200). Bây giờ, bất kể Dasha thực hiện động thái nào, hai đồng xu này vẫn sẽ ở cạnh nhau (hoặc một đồng sẽ bị loại bỏ và chuyển sang thu nhập của Sonya), điều đó có nghĩa là với động thái tiếp theo của mình, Sonya có thể nhận được một đồng xu khác. Vì vậy, Sonya sẽ luôn có thể tăng số tiền thắng của mình miễn là nó dưới 300. Bây giờ cô ấy sẽ hướng dẫn cách chơi cho Dasha để Sonya không nhận được nhiều hơn 300 xu. Đánh số các cột theo thứ tự từ 1 đến 200, chọn một đồng xu ở mỗi cột lẻ và nhẩm tô màu đỏ. Dasha chỉ cần đảm bảo rằng những đồng xu đỏ luôn ở trên bảng. Ngược lại, đối với điều này, chỉ cần hai đồng xu đỏ không bao giờ rơi vào cùng một ô là đủ, bởi vì khi một đồng xu đỏ và một đồng xu không đỏ vào một ô, chúng ta có thể giả định rằng đồng xu không đỏ đã bị loại khỏi bảng.
Gọi là cách sắp xếp các đồng xu trên bảng là tồi nếu một đồng xu đỏ nằm ở cột 1, 3, 5, ..., 197, còn một đồng xu đỏ nằm ở một trong hai cột cuối cùng 199, 200. Dễ dàng nhận thấy điều đó sau

Trong bất kỳ nước đi nào từ vị trí ổn định, hai đồng xu đỏ không ở cùng một ô. Dasha sẽ chơi sao cho sau mỗi lần di chuyển, cô ấy sẽ có được một vị trí ổn định. Nếu sau nước đi của Sonya, vị trí vẫn ổn định thì Dasha sẽ di chuyển đồng xu giữa hai cột cuối cùng và Dasha sẽ làm tương tự với nước đi đầu tiên của mình. Nếu sau khi Sonya di chuyển, vị trí không còn ổn định thì Sonya đã di chuyển một trong những đồng xu đỏ từ cột $x$ nào đó sang cột liền kề. Sau đó Dasha sẽ tự mình trả nó về cột $x$. Vì vậy, chơi theo chiến lược đã chỉ định, Dasha giữ tất cả 100 đồng đỏ trên bảng.

A. Kuznetsov

M2836. Các đường cao BD và CE của tam giác nhọn ABC cắt nhau tại điểm H (hình1), các đường cao của tam giác

Hình1

Các đường thẳng ADE cắt nhau tại điểm F, điểm M là trung điểm của cạnh BC. Chứng minh rằng BH + CH $\geq 2FM$.

Phản chiếu H so với AB, ta thu được điểm $C'$ nằm trên đường thẳng CH và sao cho E là trung điểm của $HC'$ và $BC' = BH$ (hình2).

⟦folio 29⟧

---
running_head:
folio:
---

Tương tự, điểm đường dẫn $B'$, đối xứng với $H$ đối với $AC$, sao cho $D$ nằm ở giữa $HB'$ và $CB' = CH$.
Vì $DF \perp AB$, chúng ta có $DF \parallel CE$. Tương tự như vậy, $EF \parallel BD$. Điều này có nghĩa $HEFD$ là hình bình hành. Trong tam giác $HC'B'$, điểm $E$ và $D$ là trung điểm của các cạnh. Cũng lưu ý trung điểm $F'$ của cạnh $B'C'$ thì $HEF'D$ là hình bình hành. Hóa ra $F'$ trùng với $F$, tức là $F$ – giữa $B'C'$. Vì $M$ và $F$ là trung điểm của $BC$ và $B'C'$, nên chúng ta có đẳng thức vectơ $\overrightarrow{MF} = \frac{1}{2}\left(\overrightarrow{BC'} + \overrightarrow{CB'}\right)$.
(“Định lý đường trung bình vectơ” này có thể được chứng minh bằng cách cộng các đẳng thức
$$\overrightarrow{MF} = \overrightarrow{MB} + \overrightarrow{BC'} + \overrightarrow{C'F},
\overrightarrow{MF} = \overrightarrow{MC} + \overrightarrow{CB'} + \overrightarrow{B'F}$$
và tận dụng những gì
$$\overrightarrow{MB} + \overrightarrow{MC} = \vec{0}, \overrightarrow{C'F} + \overrightarrow{B'F} = \vec{0}.$$
Bây giờ bất đẳng thức cần suy ra dễ dàng suy ra từ bất đẳng thức tam giác $(|\vec{a} + \vec{b}| \leq |\vec{a}| + |\vec{b}|)$: ta có
$$MF \leq \frac{1}{2}\left(BC' + CB'\right) = \frac{1}{2}\left(BH + CH\right).
$$
Nhiệm vụ lời giải.
Để kết luận, chúng tôi sẽ trả lời rằng có lời giải khác, được tìm thấy bởi một số học sinh ở giai đoạn khu vực của Olympic toàn Nga. Nó dựa trên việc áp dụng bất đẳng thức Pmolemy cho các điểm $M, D, E, F$.
A. Kuznetsov
M2837. Trên biểu đồ của hàm $y = x^2$ 1000 điểm khác nhau được đánh dấu, hoành độ của comorbih là các số nguyên từ đoạn [0; 100000]. Chứng minh rằng có thể chọn một phần sáu số điểm triệt tiêu phân biệt $A, B, C, A', B', C'$ sao cho diện tích của các tam giác $ABC$ và $A'B'C'$ bằng nhau.
Hãy chứng minh bổ đề.
Bổ đề. Đặt sáu điểm $A, B, C, A', B', C'$ nằm trên parabol và hoành độ của chúng lần lượt là $a, b, c, a', b', c'$. Hãy để $a' - a = b' - b = c' - c$. Sau đó $S_{ABC} = S_{A'B'C'}$.
Bằng chứng. Không mất tính tổng quát, chúng ta sẽ giả sử rằng $a < b < c$. Gọi $A_1, B_1, C_1$ là hình chiếu của điểm $A, B, C$ lên trục $Ox$
(xem hình). Khi đó $S_{ABC}$ được biểu thị theo diện tích hình thang chữ nhật:
$$S_{ABC} = S_{ACC_1A_1} - S_{ABB_1A_1} - S_{BCC_1B_1}.$$
Theo công thức tính diện tích hình thang,
$$S_{ACC_1A_1} = \frac{(AA_1 + CC_1) \cdot A_1C_1}{2} = \frac{(a^2 + c^2)(c - a)}{2}.$$
Tương tự, chúng ta biểu thị diện tích adb của các hình thang khác và sau khi biến đổi, chúng ta thu được
$$S_{ABC} = \frac{a^2c - ac^2 + c^2b - b^2c + b^2a - ba^2}{2} = \frac{(c - a)(c - b)(b - a)}{2}.$$
Chúng ta có biểu thức tương tự cho $S_{A'B'C'}$, vì $c' - a' = c - a, c' - b' = c - b, b' - a' = b - a$. Bổ đề đã được chứng minh.
Lưu ý rằng bổ đề có thể được chứng minh theo cách khác, sử dụng tính song song của các liên kết ngược nhau trong đường đứt nét khép kín $AB'CA'BC'$, hoặc sử dụng cái gọi là phép quay parabol (ví dụ, xem bài viết “Có những kiểu rẽ nào” trong «Kvant» số 2 năm 2017).
Hãy quay lại bài toán.
Hãy đặt $k = 1000, l = 100000$. Hãy sắp xếp hoành độ của các điểm bị hủy theo thứ tự tăng dần: $0 \leq x_1 < x_2 < \dots < x_k \leq l$. Hãy xem xét $k - 1$ phân đoạn $[x_1; x_2], [x_2; x_3], \dots, [x_{k-1}; x_k]$. Nếu trong số đó có 5 đoạn có độ dài bằng nhau thì ta tìm được 6 điểm hủy khác nhau thỏa mãn điều kiện của bổ đề, nghĩa là khẳng định bài toán sẽ đúng. Thật vậy, chúng ta hãy đánh số 5 đoạn bằng nhau này theo thứ tự tăng dần của trục hoành của các đầu bên trái. Sau đó, như hình chiếu của điểm $A, B, C$, chúng ta lấy các đầu bên trái của đoạn 1, 3 và 5, và trong

⟦folio 30⟧

---
running_head:
folio:
---

Theo dự đoán $A', B', C'$ chúng tôi chọn bên phải
đầu trên của cùng một phân đoạn. Thật dễ dàng để thấy
rằng các điểm $A, B, C, A', B', C'$ được chọn theo cách này là khác nhau.
Bây giờ chúng ta hãy giả sử rằng trong số $k - 1 = 999$
không có phân đoạn nào $[x_1; x_2], [x_2; x_3], \dots, [x_{k-1}; x_k]$
gót của các đoạn có chiều dài bằng nhau. Sau đó cho
mỗi $i$ trong số các phân khúc này không có
hơn bốn đoạn có chiều dài $i$. Nên-
Thật vậy, tổng chiều dài của các đoạn này không phải là
ít hơn
$$4 \cdot 1 + 4 \cdot 2 + \dots + 4 \cdot 249 + 3 \cdot 250 =$$
$$= 125250 > l = 100000.$$
Chúng tôi có một mâu thuẫn hoàn thành
lời giải.
Lưu ý nếu ở điều kiện bài toán giảm
đáp ứng yêu cầu các điểm khác nhau thì
lời giải có thể tha thứ: đủ rồi
học cách chọn 4 điểm đã đánh dấu
$A, B, A', B',$ cơ hoành $a, b, a', b'$ trong đó
thỏa mãn đẳng thức $b - a = b' - a'$; V.
trong trường hợp này $AB' \parallel A'B$ hoặc tương đương,
$S_{ABA'} = S_{B'BA'}$.
P. Kozhevnikov, A. Tereshin
M2838. Có những bình đựng nước trái cây xếp thành vòng tròn.
mi, không nhất thiết phải cùng kích cỡ.
Nó được phép đổ từ bất kỳ bình nào
thêm bất kỳ phần nào của nước trái cây (có thể ở mức thấp
bao nhiêu hoặc tất cả nước trái cây) vào một bình liền kề
ở bên phải để âm lượng không bị tràn
và hàm lượng hỗn hợp trong đó bằng 10%.
Được biết, tại thời điểm ban đầu
một số truyền máu có thể được thực hiện từ
bất kỳ bình nào. Chứng minh rằng bạn có thể
thực hiện một số theo thứ tự
truyền máu tối đa (không quá một trong
mỗi bình), sao cho có đủ
hỗn hợp trong tất cả các bình không rỗng đã bị cuốn trôi
bằng 10%.
Lưu ý khi trộn hai loại nước ép
hóa ra là một dạng yếu trung gian nào đó-
sự khác biệt giữa các tính chất của các loại nước ép này. Kế tiếp
Thuật ngữ sau đây sẽ thuận tiện.
Hãy gọi một cái bình là bình thường nếu nó
trống hoặc nội dung trong đó bằng 10%,
chua - nếu độ axit của nó nhỏ hơn 10%,
ngọt ngào - nếu nhiều hơn. Chúng tôi muối nó cẩn thận
tất cả nước trái cây trong thùng và tương tự chúng ta sẽ tính toán,
rằng thùng của chúng tôi thuộc một trong ba loại: bình thường
thơm, chua hoặc ngọt. Hãy cho đi
hai có thể lời giải.
Đầu tiên là lời giải. Nếu một cái bình nào đó
bình thường thì việc truyền máu từ đó không được thực hiện
sẽ thay đổi loại bình ở bên phải. Vì vậy, đúng
va cũng là một cái bình bình thường, vân vân.
Sau đó tất cả các bình đều bình thường và tràn
không cần phòng tắm.
Nếu không thì chúng ta có nhiều loại chua ngọt
một số bình (đặc biệt là bình tổng
số chẵn). Mở nắp bình
thành các cặp lân cận, sao cho trong mỗi cặp
bình bên trái thì chua, bình bên phải thì chua
ngọt. Truyền máu trong mỗi buồng
Hãy làm một bình đựng đồ ngọt bình thường (có thể truyền máu như vậy tùy theo điều kiện).
Hóa ra cái bình bên phải trong mỗi
phần nhợt nhạt trở lại bình thường, nhưng phần bên trái vẫn còn
chua hoặc trở nên bình thường (trống rỗng).
Chúng ta thấy trọng lượng của thùng chua
hoặc bình thường, và nó là bình thường
cuối cùng nếu và chỉ nếu sau
của những lần truyền máu này, tất cả các bình còn lại trong
cặp trống và trong trường hợp này chúng tôi thực hiện
hoặc những lần truyền máu cần thiết. Nhưng nếu
chia thành các cặp khác nhau (để trong
mỗi bình bên trái nhạt đều ngọt ngào,
còn bên phải thì chua), thì tương tự như vậy chúng ta
sẽ kết luận rằng cái thùng thật ngọt ngào
Kim hay bình thường. Vì thế, chan
thực sự bình thường và phù hợp với chúng tôi
tiếp tục truyền máu đã đề cập trước đó theo cặp
(từ bình chua đến bình ngọt).
Thứ hai lời giải. Bình Zanuterum
theo một vòng tròn sao cho người đầu tiên có thể
làm cho nó bình thường bằng cách sử dụng cái thứ 2,
Thứ 2 - với sự trợ giúp của thứ 3, ..., $n$th - với sự trợ giúp của thứ 1.
Sau đó, hãy làm cho bình thứ 1 bình thường với
với sự giúp đỡ của thứ 2. Trong bình thức ăn thứ 2
vẫn giữ nguyên, chỉ có nước trái cây có thể trở thành
ít hơn, có nghĩa là nó vẫn có thể được xử lý
bình thường khi sử dụng bình thứ 3.
Hãy làm điều đó. Chúng ta hãy thực hiện tương tự như bình thường
Chúng tôi có tất cả các bình ngoại trừ thứ $n$. Hãy chứng minh điều đó
Bình thứ $n$ trở nên bình thường, tức là Chúng tôi
đã đạt được những gì được yêu cầu.
Nếu thùng ngọt thì bình thứ $n$ cũng trở thành
ngọt ngào, nhưng sau đó anh ấy lại ngọt ngào (từ

⟦folio 31⟧

---
running_head:
folio:
---

Rốt cuộc, họ chỉ rút bớt một ít nước trái cây từ anh ta). Lặp lại lý luận, bắt đầu quá trình với một chiếc bình khác, chúng ta phát hiện ra rằng tất cả các chiếc bình đều ngọt. Nhưng sau đó không thể thực hiện được một lần truyền máu. Chúng tôi gặp tình huống tương tự nếu thùng bị chua. Vì vậy, thùng là bình thường. Nhưng sau khi truyền máu, bình thứ $n$ trở nên bình thường, đó là điều chúng tôi muốn chứng minh.

A. Shapovalov

M2839. Cho một số tự nhiên $k$. Tại đất nước Valioma Comoroi - Mugriks, vitriol có hai mệnh giá số nguyên được lưu hành. Cả người mua và người bán đều có khá nhiều kupor, nhưng đối với mỗi khoản thanh toán, họ không thể sử dụng nhiều hơn $k$ kupor cùng nhau (bao gồm cả việc đầu hàng). Được biết, bạn có thể thanh toán toàn bộ số tiền bất kỳ từ 1 đến $n$ cốcrik. Giá trị lớn nhất có thể có của $n$ là bao nhiêu?

Đáp số: $n = k(k+1)$.
Hãy để những mái vòm phẩm giá $P$ và $Q$ được sử dụng. Giả sử một số nguyên được chấp nhận nếu nó có thể được biểu diễn dưới dạng $aP + bQ$, trong đó $a$ và $b$ là các số nguyên thỏa mãn điều kiện $|a| + |b| \leq k$. Lưu ý rằng 0 là một số hợp lệ và ngoài ra, các số $t$ và $-t$ đồng thời hợp lệ hoặc không hợp lệ (từ cách biểu diễn một số, người ta có thể thu được cách biểu diễn của số đối diện bằng cách thay thế các số $a$ và $b$ bằng số đối của chúng). Rõ ràng các khoản thanh toán mà chúng ta có thể thực hiện (theo điều kiện của bài toán) chính xác là những số dương hợp pháp.

Cấp. Số lượng số được chấp nhận rất nhiều không lớn hơn số cặp số nguyên $(a,b)$ thỏa điều kiện $|a| + |b| \leq k$. Số lượng các cặp như vậy rất dễ tính: với $a = 0$ có ​​$2k+1$ giá trị phù hợp $b$, với $a = \pm 1$ có $2k-1$ giá trị phù hợp $b$, ..., với $a = \pm k$ có một giá trị phù hợp $b$; tổng cộng

$$
(2k+1) + 2((2k-1) + (2k-3) + \dots + 1) = 2k(k+1) + 1.
$$

Điều này có nghĩa là số lượng số dương được chấp nhận không vượt quá

$$
\frac{(2k(k+1)+1)-1}{2} = k(k+1)
$$

(ở đây chúng tôi đã dạy rằng tất cả các số hợp lệ, ngoại trừ số 0, đều được chia thành các cặp số đối lập).

Ví dụ. Chúng tôi sẽ sử dụng cupora trong $P = k$ và $Q = k+1$ tugriks. Hãy để chúng tôi chứng minh rằng trong trường hợp này phát biểu sau đây là đúng: $2k(k+1)+1$ các số được chấp nhận; đây chính xác là tất cả các số nguyên từ phân đoạn $[-k(k+1); k(k+1)]$.

Đầu tiên chúng ta chứng minh rằng có chính xác $2k(k+1)+1$ số có thể chấp nhận được. Với lý do ở trên, điều này tương đương với thực tế là tất cả các biểu diễn có dạng $ak+b(k+1)$, trong đó $|a|+|b| \leq k$, đều cho các số tiền khác nhau. Giả sử có một trận đấu:

$$
ak+b(k+1) = ck+d(k+1),
$$

trong đó các số nguyên $a, b, c, d$ sao cho $|a|+|b| \leq k$ và $|c|+|d| \leq k$. Có nghĩa,

$$
(a-c)k = (d-b)(k+1).
$$

Khi đó, vì các số $k$ và $k+1$ là số nguyên tố cùng nhau nên $(a-c)$ chia hết cho $k+1$ và $(d-b)$ chia hết cho $k$. Nếu các cặp $(a,b)$ và $(c,d)$ khác nhau thì ít nhất một trong các chênh lệch $(a-c), (d-b)$ không bằng 0, nhưng khi đó hiệu thứ hai không bằng 0. Do đó,

$$
k+1 \leq |a-c| \leq |a|+|c|, k \leq |d-b| \leq |d|+|b|,
$$

từ đâu sau khi cộng chúng ta nhận được

$$
2k+1 \leq |a|+|c|+|b|+|d| = \left(|a|+|b|\right) + \left(|c|+|d|\right) \leq 2k.
$$

Sự mâu thuẫn.

Vì vậy, về cơ bản có $2k(k+1)+1$ số hợp lệ (và chúng đều là số nguyên rất nhiều). Nhưng lưu ý rằng con số được chấp nhận nhiều nhất là $k(k+1)$ (thu được với $a=0, b=k$). Tương tự, số hợp lệ nhất là $-k(k+1)$. Vì vậy, chúng ta cần khẳng định được chứng minh.

A. Shapovalov

M2840. Các đường cao $AA_1, BB_1, CC_1$ của tam giác nhọn ABC cắt nhau tại điểm $H$ (hình 1). Các đường phân giác của các góc B và C của tam giác BHC cắt nhau từ

⟦folio 32⟧

---
running_head:
folio:
---

cắt CH và BH lần lượt tại các điểm X và Y. Chúng ta hãy biểu thị các giá trị của góc ХА₁Y bằng α. Chúng ta hãy định nghĩa β và γ một cách tương tự. Tìm giá trị của tổng α + β + γ.

Đáp số: 270°.
Gọi giao điểm của các phân giác của góc ABH và ACH với đoạn AH lần lượt là P và Q. Hãy chứng minh điều đó
$$\angle PC_1H = \angle AB_1Q = 90^\circ - \angle QB_1H.$$ (1)
Từ đó sẽ có lời giải bài toán - tổng từ điều kiện được chia thành ba cặp góc có tổng bằng 90° (hình 2), tức là tổng cần thiết sẽ bằng 270°.

Vì vậy, hãy chứng minh (1). Vì $\angle ABH = \angle ACH$, thì cũng $\angle ABP = \angle HCQ$ (hình 3), do đó
$$\angle BPA_1 = \angle ABP + \angle BAP = \angle HCQ + \angle BCH = \angle BCQ.$$
Do đó, các tam giác vuông BPA₁ và QCA₁ có hai góc bằng nhau nên
$$\frac{BA_1}{PA_1} = \frac{QA_1}{A_1C} \Leftrightarrow BA_1 \cdot A_1C = PA_1 \cdot QA_1.$$ (2)
Như đã biết, tam giác A₁BC₁ và A₁B₁C đồng dạng với tam giác ABC nên đồng dạng với nhau.
Từ đây
$$\frac{BA_1}{A_1C} = \frac{B_1A_1}{A_1C} \Leftrightarrow BA_1 \cdot A_1C = B_1A_1 \cdot A_1C.$$ (3)
Từ đẳng thức (2) và (3) suy ra rằng
$$PA_1 \cdot QA_1 = B_1A_1 \cdot A_1C \Leftrightarrow \frac{PA_1}{A_1C} = \frac{B_1A_1}{QA_1}.$$
Chúng ta hãy sử dụng một thực tế nổi tiếng khác: chiều cao AA₁ là phân giác của góc B₁A₁C₁. Khi đó $\angle C_1A_1P = \angle B_1A_1Q$, có nghĩa là các tam giác PC₁A₁ và B₁QA₁ giống nhau về góc và tỷ số của các cạnh kề nhau, do đó $\angle A_1C_1P = \angle A_1QB_1$.
Kế tiếp,
$$\angle PC_1H = \angle A_1C_1P - \angle A_1C_1C = \angle A_1QB_1 - \angle A_1AC = \angle AB_1Q,$$
hoàn thành lời giải.
Lưu ý rằng có nhiều cách để chứng minh đẳng thức khóa (1). Hãy đưa ra kế hoạch cho một phương pháp khác sử dụng các vòng tròn phụ.
Giả sử BP và CQ cắt nhau tại điểm T (hình 4). Dễ dàng nhận thấy $\angle BTC = 90^\circ$, tức là T nằm trên đường tròn BCB₁C₁ (dây dựng với BC là đường kính).

⟦folio 33⟧

---
running_head:
folio:
---

Vì $\angle BTC_1 = \angle BCC_1 = \angle BAA_1$ nên các điểm $A, T, P, C_1$ nằm trên cùng một đường tròn. Tương tự, các điểm $A, T, Q, B_1$ nằm trên cùng một đường tròn. Hơn nữa (1) rút ra từ một phép tính góc đơn giản.
A. Doledenok

M2841*. Chúng tôi sơn mỗi ô vuông của bảng $2m \times 2n$ đen hoặc trắng để các ô của mỗi chuỗi tạo thành một đa giác. Sau đó Vasya cắt bảng thành các quân domino (hình chữ nhật gồm hai hình vuông). Pya cố gắng đảm bảo rằng cô ấy nhận được càng nhiều quân domino hai màu càng tốt, và Vasya cố gắng đảm bảo rằng cô ấy nhận được càng ít quân domino càng tốt. Pemya có thể đảm bảo số lượng quân domino hai màu tối đa là bao nhiêu, bất kể Vasya hành động như thế nào?

Đáp số: $(m - 1)(n - 1) + 1$.
1) Hãy để chúng tôi chứng minh rằng cho dù Petya tô màu bảng như thế nào, Vasya vẫn có thể cắt nó theo cách để thu được không quá $(m - 1)(n - 1) + 1$ quân domino hai màu.
Trước tiên, hãy để Vasya cắt bảng thành đường viền có chiều rộng 1 và thành $(m - 1)(n - 1)$ hình vuông $2 \times 2$. Không có hình vuông nào trong số $2 \times 2$ này có thể được tô màu theo mẫu bàn cờ, nếu không, các ô màu đen sẽ không tạo thành đa giác. Do đó, Vasya có thể cắt mỗi ô vuông $2 \times 2$ này thành hai quân domino, ít nhất một quân trong số đó là một chân.
Tiếp theo, chúng tôi sẽ chỉ ra rằng đường viền có thể được chia thành các quân domino, trong đó không có nhiều hơn một quân hai màu. Hãy chứng minh rằng các ô đen và trắng của đường viền tạo thành các tập hợp liên thông. Giả sử trường hợp này không xảy ra và trên đường viền có hai ô đen $A$ và $B$ sao cho từ $A$ không thể tiếp cận $B$ dọc theo đường viền (đi đến các ô liền kề ở bên cạnh), chỉ nhìn vào các ô đen. Nhưng trên bảng gốc giữa $A$ và $B$ có một con đường dọc theo các ô vuông màu đen. Đường dẫn này chia bảng thành hai phần, mỗi phần chứa ít nhất một hình vuông màu trắng (thậm chí chúng có thể được tìm thấy ở cạnh). Nhưng giữa các ô trắng này không thể có đường đi dọc theo các ô trắng, do đó các ô trắng không tạo thành đa giác - một điều mâu thuẫn.
Từ tuyên bố đã được chứng minh, Vasya có thể cắt đường viền thành các quân domino, trong đó không quá một quân có hai màu. (Thật vậy, đường đi của Vasya sẽ thực hiện vết cắt đầu tiên giữa các ô có màu khác nhau, sau đó đường cắt của đường viền sẽ được khôi phục một cách duy nhất.)
Như vậy, tổng cộng Vasya sẽ nhận được không quá $(m - 1)(n - 1) + 1$ quân domino hai màu.
2) Bây giờ hãy chỉ ra cách Petya có thể tô màu bảng để đảm bảo $(m - 1)(n - 1) + 1$ quân domino hai màu.
Ở viền của con đường, Petya sẽ sơn tất cả các ô phía dưới màu đen, ngoại trừ ô ngoài cùng bên trái. Hãy loại bỏ ranh giới về mặt tinh thần. Ở bảng còn lại, đường dẫn $2(m - 1) \times 2(n - 1)$ Petya sẽ tô màu tất cả các cột có số dạng $4k + 2$ màu đen, và ở tất cả các cột có số lẻ anh ấy sẽ tô màu các ô 1, 3, ..., $2m - 3$ (tính từ trên xuống). Petya sơn phần còn lại của ô màu trắng. hình hiển thị màu kết quả cho bảng $8 \times 10$ và $8 \times 12$. Rõ ràng, các ô đen và trắng tạo thành đa giác. Tiếp theo, chúng ta đặt “trọng số” $\pm 1$ vào các ô theo hình bàn cờ, sao cho ô góc bên trái có trọng số là 1. Sau đó tính tổng các trọng số trong

⟦folio 34⟧

---
running_head:
folio:
---

tất cả các ô đen đều bằng $(m-1)(n-1)+1$ (thực ra, tổng trên các ô đen của đường viền bằng 1, ở bảng còn lại $2(m-1)\times 2(n-1)$ ở các cột có số dạng $4k+2$ tổng sẽ bằng 0 và ở mỗi cột có số lẻ tổng sẽ bằng $m-1$). Vì tổng trọng số trong mỗi quân domino bằng 0 nên đối với bất kỳ lần cắt nào, ít nhất $(m-1)(n-1)+1$ ô đen sẽ tạo thành một quân domino có ô trắng, đó là điều chúng tôi muốn thiết lập.
A. Gribalko

F2841. Có một cái nêm (hình 1) trên một mặt phẳng nằm ngang gồ ghề. Vòng đệm được đặt trên mặt phẳng nghiêng thô của nêm và tốc độ ban đầu được truyền cho vòng đệm. Quả bóng di chuyển dọc theo một cái nêm đứng yên. Một phần của mô hình tốc độ của quả bóng phụ thuộc thời gian được trình bày ở hình 2. Chuyển động quan sát được của quả bóng trước và sau khi dừng lại sẽ có vận tốc dọc theo cùng một đường thẳng. Khối lượng của vòng đệm là $m=0,2$ kg, khối lượng của nêm là $M=2m$. Tăng tốc độ mặc miễn phí $g=10\text{ m/c}^2$.

Hình 1

Hình 2

1) Tìm sin $\alpha$, trong đó $\alpha$ là góc mà mặt phẳng nghiêng của hình nêm tạo với đường chân trời.
2) Tìm mô-đun $F_{\text{тр}}$ của lực ma sát lớn nhất mà mặt phẳng ngang tác dụng lên nêm trong quá trình chuyển động của vòng đệm dọc theo nêm ở $0<t<0,3$ s.
3) Tại giá trị nào của hệ số $\mu$ ma sát trượt của khối nêm trên mặt phẳng ngang thì khối nêm sẽ đứng yên khi $0<t<0,3$ Với?

1) Theo lịch trình tại mô-đun tăng tốc hình 2 trong quá trình hạ xuống
$a_1=g(\sin \alpha+\mu\cos \alpha)=8\text{ m/c}^2,$
mô-đun tăng tốc nâng
$a_2=g(\sin \alpha-\mu\cos \alpha)=4\text{ m/c}^2.$
Sau đó
$\sin \alpha=\frac{a_1+a_2}{2g}=0,6,$ $\cos \alpha=0,8.$
2) Trong một hệ các vật tương tác theo định luật thứ ba của Newton, tổng tích của khối lượng và gia tốc bằng tổng các ngoại lực tác dụng lên hệ. Khi quả bóng di chuyển dọc theo nêm
$m\vec{a}=m\vec{g}+2m\vec{g}+\vec{N}+\vec{F}_{\text{тр}}.$ (*)
Chúng ta chuyển sang hình chiếu các lực và gia tốc theo phương ngang:
$F_{\text{тр}}=ma\cos \alpha.$
Lực ma sát nhỏ nhất của mặt phẳng ngang tác dụng lên nêm trong khoảng thời gian chuyển động xác định bằng
$F_{\text{тр1}}=ma_1\cos \alpha=1,28\text{ H}.$
3) Đối với đáp số ở câu hỏi thứ ba, chúng ta tìm lực $\vec{N}$ của phản lực pháp tuyến. Trong các hình chiếu của lực và gia tốc theo phương thẳng đứng, từ phương trình (*) ta thu được
$-ma\sin \alpha=-mg-2mg+N,$
Ở đâu
$N=3mg-ma\sin \alpha.$
Khi đó hệ số ma sát yêu cầu
$\mu \geq \frac{F_{\text{тр1}}}{N_1}=\frac{ma_1\cos \alpha}{3mg-ma_1\sin \alpha}=\frac{a_1\cos \alpha}{3g-a_1\sin \alpha}\approx 0,25.$
V.Plis

F2842. Một tấm được cắt từ một tấm kim loại đồng nhất có hình tam giác đều ABC (hình 1) được đặt trên mặt phẳng ngang chính và giữ im lặng. Cái đĩa bắt đầu di chuyển. Tại thời điểm $t=0$ hóa ra tốc độ của điểm A hướng sang một bên

⟦folio 36⟧

---
running_head:
folio:
---

từ Mặt trời, giống như Trái đất, trong khi nhỏ-
nhiệt độ thấp $T_{\text{min}} = T_0$. Khi
ema đang di chuyển ra xa Mặt trời đến khoảng cách tối đa của nó thì tối đa
 nhiệt độ $T_{\text{max}}$ của một số cốc
trở thành bằng $T_0$. Nhiệt độ của $T_0$ và $T_{\text{max}}$ là bao nhiêu? Nhóm cốc này quay quanh Mặt trời trong khoảng thời gian nào? Một quả cầu đồng nhỏ có bề mặt rất đen được “nhào” vào nhóm cốc. Nhiệt độ của nó là bao nhiêu? (Chúng ta có thể tự mình tìm thấy các giá trị số của các đại lượng vật lý cần thiết cho lời giải.)

Độ đen tuyệt đối của một bề mặt có nghĩa là ánh sáng bị hấp thụ hoàn toàn bởi bề mặt mà nó chiếu tới. Người ta biết rằng các vật thể cô lập được nung nóng đến nhiệt độ $T$ tỏa ra không gian xung quanh một năng lượng tỷ lệ thuận với tổng diện tích bề mặt của chúng và nhiệt độ của chúng theo lũy thừa thứ 4: $W = \sigma T^4$. Hệ số tỷ lệ là hằng số Stefan-Boltzmann $\sigma = 5,67 \cdot 10^{-8} \text{ Bt}/(\text{m}^2 \cdot \text{K}^4)$. Mặt trời tỏa sáng theo mọi hướng và ở khoảng cách từ Mặt trời là 150 ml km (khoảng cách từ Trái đất đến Mặt trời), cứ mỗi mét vuông bề mặt vuông góc với các tia sẽ phát ra năng lượng (Hằng số mặt trời) $E = 1370 \text{ Bt}/\text{m}^2$.

Ở giá trị nhiệt độ ổn định của khối lập phương có cạnh $a$, công suất mà nó hấp thụ bằng với công suất mà khối lập phương này mất đi do bức xạ. Tùy thuộc vào hướng của khối lập phương so với các tia Mặt trời, diện tích bề mặt mà các tia mặt trời chiếu vào có thể tối thiểu $S_{\text{min}} = a^2$ hoặc tối đa $S_{\text{max}} = 1,5a^2$. Trong trường hợp thứ hai, đường chéo dài nhất của hình lập phương song song với tia sáng Mặt trời (xem hình). Hình được chiếu sáng lên một mặt phẳng vuông góc với

tia Mặt trời, là một hình lục giác đều, trong đó khoảng cách giữa các cạnh song song với nhau bằng $a\sqrt{2}$. Từ đó có thể dễ dàng tính được diện tích của hình lục giác đó. Do đó, các hình khối có công suất khá khác nhau và diện tích bề mặt bị mất năng lượng của chúng là như nhau và bằng $6a^2$. Theo điều kiện, các hình khối là đồng, tức là. Chúng dẫn nhiệt tốt và nhỏ, điều này cho phép chúng ta giả sử rằng nhiệt độ trên toàn bộ bề mặt của mỗi khối là như nhau. Vì ở khoảng cách tối đa so với Mặt trời, tác động tối đa từ các cốc tới Mặt trời lớn hơn $(1,5)^{1/4}$ lần so với khoảng cách tối thiểu, tức là trục của hình elip, quỹ đạo của nhóm quay quanh Mặt trời, lớn hơn hai lần khoảng cách từ Trái đất đến Mặt trời $1 + (1,5)^{1/2}$ lần. Theo định luật thứ ba của Kepler, tỷ số bình phương chuyển động của các hành tinh quanh Mặt trời bằng tỷ số lập phương của các trục chính của hình elip của chúng. Trong trường hợp của chúng tôi, chu kỳ quay của các cốc quanh Mặt trời dài hơn khoảng 1,193 lần so với một năm và xấp xỉ 435,8 ngày Trái đất.

Vì các cốc của quả bóng có diện tích phát ra bức xạ nhiệt lớn hơn 4 lần so với diện tích hấp thụ ánh sáng mặt trời nên nhiệt độ của nó bằng với tác động tối đa để tìm các cốc ở gần nó.

Vì thế,

$$T_0 = T_{\text{min}} \approx 251,9 \text{ K},$$
$$T_{\text{max}} = T_0 \cdot (1,5)^{1/4} \approx 278,8 \text{ K};$$

Chu kỳ quay của các cốc quanh Mặt trời là 435,8 ngày Trái đất; nhiệt độ của quả cầu đồng bằng nhiệt độ cực đại của khối lập phương.

S.Varlamov
