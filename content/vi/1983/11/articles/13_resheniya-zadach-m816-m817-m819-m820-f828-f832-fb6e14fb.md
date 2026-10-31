---
id: 1983-11-resheniya-zadach-m816-m817-m819-m820-f828-f832-fb6e14fb
issue: kvant_1983_11
year: 1983
number: "11"
title: Lời giải bài toán M816, M817, M819, M820; F828—F832
rubric: zadachnik-kvanta
rubric_sub: Задачник «Кванта»
page_first: 41
page_last: 45
page_labels: 39, 40, 43
tag: IIDV
lang: vi
source: kvant_digital
extraction: vision
content_sha256: 66517607483553a88cba2a442712ccc9476cff34ddc0162e7f73936fa0548b94
prompt_sha256: draft-1
translated_from: content/ru/1983/11/articles/13_resheniya-zadach-m816-m817-m819-m820-f828-f832-fb6e14fb.md
source_content_sha256: 6502541d952a232a58231441eb6e423fea6100b4a3ac1d8110ff7a1e83155781
translation_model: draft
translation_run: vi-draft-2026-10-31
translation_quality: draft
---

⟦folio 39⟧

Lời giải bài toán
M816, M817, M819, M820*); F828—F832

M816. Các số tự nhiên a và b được tạo thành từ nhau bằng cách sắp xếp lại các chữ số. Chứng minh rằng
a) tổng các chữ số của số 2a và 2b bằng nhau;
b) tổng các chữ số của các số a/2 và b/2 bằng nhau (nếu a và b là số chẵn);
c) tổng các chữ số của số 5a và 5b bằng nhau.

Đầu tiên chúng ta chứng minh một mệnh đề phụ.
Gọi $S(x)$ là tổng các chữ số của số tự nhiên $x$, $N(x)$ số các chữ số của số đó lớn hơn 4. Khi đó
$$S(2x) = 2S(x) - 9N(x).$$

Hãy tưởng tượng rằng chúng ta thêm số $x$ vào chính nó trong một cột, bắt đầu bằng các chữ số thấp nhất. Việc chuyển từ một sang chữ số thứ $(k+1)$ tiếp theo của tổng xảy ra khi và chỉ khi chữ số thứ $k$ của số $x$ chứa một trong các chữ số 5, 6, 7, 8 hoặc 9 (trong ví dụ ở lề, điều này xảy ra ở thứ 2, 3 và 5 tính từ cuối chữ số), tức là số lần chuyển là $N(x)$. Với mỗi lần chuyển số mười, được bao gồm trong tổng $S(x) + S(x)$, một đơn vị sẽ xuất hiện, được bao gồm trong tổng $S(2x)$, tức là $S(2x)$ so với $2S(x)$ giảm đi 9. Từ đây chúng ta nhận được (*).

Bây giờ thật dễ dàng để chứng minh khẳng định bài toán.
a) Thay thế (*) với $x$ lần lượt $a$ và $b$ và xét các đẳng thức tiếp theo $S(a) = S(b)$ và $N(a) = N(b)$, ta thu được $S(2a) = S(2b)$.
b) Lưu ý rằng chữ số $i$ của số $x$ lớn hơn 4 khi và chỉ khi chữ số $(i+1)$ của số $2x$ là số lẻ. Do đó, $N(x)$ bằng số chữ số lẻ trong $2x$. Do đó, đối với các số $a$ và $b$, gồm các chữ số giống nhau, $N(a/2) = N(b/2)$ và nhờ vào (*)
$$S\left(\frac{a}{2}\right) = \frac{1}{2}\left(S(a) + 9N\left(\frac{a}{2}\right)\right) = \frac{1}{2}\left(S(b) + 9N\left(\frac{b}{2}\right)\right) = S\left(\frac{b}{2}\right).$$
c) Rõ ràng các số 10a và 10b thỏa mãn điều kiện tại điểm 6) nên
$$S(5a) = S\left(\frac{10a}{2}\right) = S\left(\frac{10b}{2}\right) = S(5b).$$
A. D. Lisitsky

M817. Điểm $K$ nằm trên cạnh $BC$ của tam giác $ABC$. Chứng minh rằng sự tương ứng $|AK|^2 = |AB| \cdot |AC|$ - $|KB| \cdot |KC|$ đúng khi và chỉ khi $|AB| = |AC|$ hoặc $BAK = CAK$.

Hình 1.
$$|AK|^2 = q|AB|^2 + p|AC|^2 - |BK| \cdot |KC|$$
ở đâu $p = |BK| : |BC|$, $q = |CK| : |BC|$.

Cái đầu tiên là lời giải (Hình 1). Đặt $p = |BK| : |BC|$, $q = 1 - p = |CK| : |BC|$, sau đó
$$\overrightarrow{AK} = \overrightarrow{AB} + \overrightarrow{BK} = \overrightarrow{AB} + p\overrightarrow{BC} = \overrightarrow{AB} + p(\overrightarrow{AC} - \overrightarrow{AB}) = q\overrightarrow{AB} + p\overrightarrow{AC}.$$
(*)

Trong điều kiện $|AK|^2 = (q\overrightarrow{AB} + p\overrightarrow{AC})^2 = |AB| \cdot |AC|$ - $|KB| \cdot |KC| = |AB| \cdot |AC| - pq(\overrightarrow{AC} - \overrightarrow{AB})^2$.

Mở rộng dấu ngoặc và tính đến $p + q = 1$, chúng ta nhận được:
$$q|AB|^2 + p|AC|^2 - |AB| \cdot |AC| = 0.$$

Do đó, tỷ lệ độ dài cạnh của tam giác $\lambda = |AB| : |AC|$ thỏa mãn phương trình bậc hai $q\lambda^2 - \lambda + p = 0$, tức là $\lambda = 1$ hoặc $\lambda = p/q$. Trong trường hợp đầu tiên $|AB| = |AC|$, trong trường hợp thứ hai - $|AB| : |AC| = p/q = |BK| : |KC|$, từ đó, theo định lý nổi tiếng***), suy ra rằng $AK$ là bisserris hoặc $BAK = CAK$.

Sử dụng đẳng thức (*), dễ dàng suy ra công thức tổng quát tính độ dài của đoạn $AK$, được gọi là công thức Stewart. Nó được đưa ra trong lề.

*) Bài toán M818 sẽ được giải bằng một trong các số sau «Kvant».
***) Ví dụ, xem S. R. Sefi Bekov “Bốn cách chứng minh định lý Bisseris” («Kvant», 1983, số 8).

⟦folio 40⟧

Thứ hai lời giải. Chúng ta lấy một điểm L trên đoạn BC sao cho $\widehat{CAL} = \widehat{KAB}$ (Hình 2). Hãy để chúng tôi chứng minh điều đó $|AL| = |AK|$. Từ đây sẽ suy ra rằng hoặc hai điểm L và K trùng nhau, tức là AK là bissertis của góc A, hoặc $\Delta ALK$ là hai cạnh đều và khi đó, theo định lý về góc ngoài của một tam giác

$$\widehat{ABC} = \widehat{AKC} - \widehat{BAK} = \widehat{ALB} - \widehat{LAC} = \widehat{ACB},$$

tức là tam giác ABC đều.

Gọi D là giao điểm của đường thẳng AK và đường tròn ngoại tiếp tam giác ABC. Vì $ACB = ADB$ nên tam giác ACL đồng dạng với tam giác ADB nên $|AL| \cdot |AD| = |AB| \cdot |AC|$. Tam giác ACK và BDK cũng đồng dạng ($\widehat{ACB} = \widehat{ADB}, \widehat{AKC} = \widehat{BKD}$), nên $|BK| \cdot |KC| = |AK| \cdot |KD|$. Do đó, đẳng thức cho trong điều kiện tương đương với đẳng thức sau

$$|AK|^2 = |AL| \cdot |AD| - |AK| \cdot |KD|$$

hoặc

$$|AK|(|AK| + |KD|) = |AL| \cdot |AD|.$$

Do đó nó dẫn đến $|AK| = |AL|$.

A. L. Toom, N. B. Vasiliev

**M819. Có n thành phố ở Schwambrania, mỗi thành phố được nối với nhau bằng một con đường. (Các con đường chỉ hội tụ trong các thành phố, tất cả các giao lộ đều bị giới hạn ở các góc khác nhau.) Tên phù thủy độc ác có ý định thiết lập giao thông một chiều trên mỗi con đường để một khi bạn rời khỏi bất kỳ thành phố nào, bạn sẽ không thể quay lại thành phố đó được nữa. Chứng minh rằng a) thuật sĩ có thể làm được điều này;
b) trong trường hợp này, sẽ có một thành phố mà từ đó bạn có thể đến tất cả những thành phố khác, và sẽ có một thành phố mà bạn không thể rời đi;
c) có $n! = 1 \times 2 \times \dots \times n$ cách để thực hiện ý định của thuật sĩ này.**

a) Trình hướng dẫn có thể đánh số tất cả các thành phố của Schwambrania với các số từ 1 đến n và đặt trên mỗi con đường một chuyển động từ thành phố có số thấp hơn đến thành phố có số cao hơn. Bằng cách này, anh ta sẽ đạt được mục tiêu của mình, bởi vì số lượng thành phố gặp phải khi di chuyển dọc theo bất kỳ tuyến đường nào có hạn chế như vậy sẽ luôn được trả về.

b) Bắt đầu từ bất kỳ thành phố nào, chúng ta sẽ đi dọc theo những con đường của Schwambrania, tuân theo các quy tắc của thầy phù thủy này. Chúng ta hãy ngạc nhiên chừng nào điều này còn có thể. Sẽ không tìm thấy thành phố nào trên tuyến đường của chúng tôi và vì số lượng thành phố là hữu hạn nên sớm hay muộn chúng tôi sẽ phải dừng lại. Nhưng điều này có nghĩa là chúng tôi đã đến thành phố Z, nơi chúng tôi không thể rời đi.

Bây giờ chúng ta hãy đảo ngược hướng chuyển động trên mọi con đường. Rõ ràng là, theo quy định mới, chúng ta sẽ không thể đến thăm cùng một thành phố nữa. Do đó, như trên, có một thành phố A mà bạn không thể rời đi theo quy định mới (!). Do đó, ban đầu trên con đường nối A với bất kỳ thành phố B nào khác, giao thông được thiết lập từ A đến B, nghĩa là từ A bạn có thể đến bất kỳ thành phố nào (chỉ đi qua một con đường).

Lưu ý rằng bạn có thể đi từ bất kỳ thành phố nào ngoại trừ Z (ví dụ đến Z) và bạn có thể đi đến bất kỳ thành phố nào ngoại trừ A.

c) Hãy tiến hành quy nạp theo số thành phố n. Với n = 1, câu c) là hiển nhiên. Hãy chứng minh điều đó cho n thành phố, giả sử rằng nó đúng cho n - 1 thành phố. Theo điểm 6), đối với bất kỳ quy tắc giao thông nào đáp ứng các điều kiện của trình hướng dẫn này, có một và chỉ một thành phố Z mà bạn không thể rời khỏi đó. Nó có thể là bất kỳ thành phố n nào.

Trên tất cả các con đường nối về thành phố Z. Do đó, không có con đường nào nối hai thành phố khác không thể đi qua Z nữa và chỉ cần đặt hướng trên các con đường giữa n - 1 thành phố còn lại sao cho không thể đi đến bất kỳ thành phố nào trong số đó khi đi dọc theo các hướng này. Theo giả thuyết quy nạp điều này có thể thực hiện được (n - 1)! cách. Do đó, tổng số cách là n · (n - 1)! = n!.

Một lời giải khác dựa trên thực tế là có một tuyến đường dài nhất (theo số đường)

⟦folio 43⟧

Hơi phía trên bề mặt của raster chỉ chứa các phân tử nước. Hằng số giá trị phổ quát là $R = 8,3$ J/(mol K).

Chúng ta tìm thấy mật độ $\rho_{\pi}$ của hơi nước ở nhiệt độ $T = 293$ K từ phương trình trạng thái khí:

$$\rho_{\pi} = p_{\text{mac}} \frac{\mu}{RT}.$$

Như vậy,

$$h = \frac{0,05c_2RT}{\mu g} (2 \frac{h_0}{h} - 1).$$

Thay thế dữ liệu số đã cho vào điều kiện, ta tìm được

$$h \approx 16,4 \text{ см.}$$

Điều thú vị cần lưu ý là, như sau từ bài toán đã xem xét, nếu dưới mui xe có hai bình giống hệt nhau chứa các dung dịch có nồng độ khác nhau, thì sự bay hơi sẽ xảy ra từ dung dịch có nồng độ thấp hơn. Ngược lại, hơi nước sẽ ngưng tụ thành dung dịch có nồng độ cao hơn. Vì vậy, nồng độ sẽ có xu hướng cân bằng. Hiện tượng vật lý này có liên quan đến việc làm ướt đường, muối, v.v. trong bầu không khí ẩm ướt.

A. I. Buzdin

F831. Một vỏ cầu có thành mỏng dẫn điện, đặt trong điện trường đều. Khi hướng từ trường là $E_0$, lớp vỏ sẽ vỡ. Tại hướng từ trường tối thiểu nào thì một vỏ có bán kính gấp đôi và có cùng độ dày thành sẽ bị vỡ?

◆ Một vỏ dẫn điện đặt trong điện trường sẽ xuất hiện điện tích cảm ứng. Mật độ bề mặt của các điện tích này tỷ lệ thuận với hướng của trường $E$. Khi kích thước của lớp vỏ thay đổi $n$ lần và hướng của trường $k$ lần, các lực tác dụng lên hai nửa quả cầu (trên đó cảm ứng điện tích trái dấu) thay đổi $k^2n^2$ lần.

Vì độ dày thành không đổi nên lực trên một đơn vị chiều dài của vỏ phải như nhau. Nếu trong trường hợp đầu tiên, điểm gián đoạn tỉ lệ với hướng của trường $k$ lần và hướng của trường $n$ lần và hướng của trường $k$ lần thì điểm gián đoạn tỉ lệ, Từ điều kiện $f = (k^2n^2/n)f_0$. Từ điều kiện $f = f_0$ suy ra:

$$\frac{k^2n^2}{n} = 1 \Rightarrow k = \frac{1}{\sqrt{n}}.$$

Khi bán kính vỏ tăng gấp đôi, độ gián đoạn tỉ lệ với trường

$$E = E_0 / \sqrt{2}.$$

S. K. Strokov

F832*. Một khung siêu dẫn hình vuông không biến dạng ở cạnh a đặt nằm ngang và nằm trong từ trường bậc thấp, cảm ứng của nó thay đổi trong không gian theo định luật

$$B_x = -kx,$$

$$B_y = 0,$$

$$B_z = kz + B_0.$$

Khối lượng khung $m$, độ tự cảm $L$. Tại thời điểm ban đầu, tâm của khung trùng với gốc tọa độ và các cạnh song song với trục $X$ và $Y$. Khung bị xỉn màu. Nó sẽ di chuyển như thế nào và sẽ kết thúc ở đâu sau thời gian $t$?

Từ thông tạo ra diện tích giới hạn bởi mạch siêu dẫn là không đổi. Thật vậy, $\Delta \Phi / \Delta t = \delta_i$, nhưng $\delta_i = iR = 0$ (kể từ $R = 0$), do đó $\Phi = B_0 a^2 + kz^2 + Li$.

Vì tại thời điểm ban đầu $(z = 0, i = 0)$ $\Phi = B_0 a^2$, tại bất kỳ thời điểm nào khác, giá trị của điểm $i$ sẽ được xác định bởi mối quan hệ

$$Li = -kz^2 \Rightarrow i = -\frac{kz^2}{L}.$$

Lực sinh ra từ từ trường tác dụng lên khung có dòng điện $i$ bằng tổng các lực tác dụng lên các cạnh của khung song song với trục $Y$,
