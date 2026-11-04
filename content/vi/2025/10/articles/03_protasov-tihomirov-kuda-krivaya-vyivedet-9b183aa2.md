---
id: 2025-10-protasov-tihomirov-kuda-krivaya-vyivedet-9b183aa2
issue: kvant_2025_10
year: 2025
number: "10"
title: Đường cong sẽ dẫn tới đâu?
authors:
  - Протасов В. Ю.
  - Тихомиров В. М.
rubric: osnovnye-stati
page_first: 4
page_last: 25
page_labels: 3, 4, 10, 11, 12, 13, 15, 16, 17, 19, 21, 23
lang: vi
source: kvant_digital
extraction: vision
content_sha256: 4a9367dc07d3752a295a1766b2ca3c813088a4d53fe23305add482132b09ceca
prompt_sha256: draft-1
translated_from: content/ru/2025/10/articles/03_protasov-tihomirov-kuda-krivaya-vyivedet-9b183aa2.md
source_content_sha256: 2c3497137764207da6bc0cac8cd77ea3929f72d91e14b68c7125e8ff776495b4
translation_model: draft
translation_run: vi-draft-gaps-2026-11-04
translation_quality: draft
---

⟦folio none⟧

---
running_head:
folio:
---

Đường cong sẽ dẫn tới đâu?
V. PROTASOV, V. TIKHOMIROV

Chúng ta sẽ bắt đầu với việc tối ưu hóa đơn giản bài toán, không phải trong toán học mà trong vật lý. Những đường cong mà nó thảo luận sẽ dẫn chúng ta đến bài toán Cao nguyên của các bề mặt tối thiểu, đến hình dạng tối ưu của vòm trong kiến ​​trúc và đến một mô hình hình học phi Euclide. Ở đây, kỹ thuật tương tự xuất hiện, được hình thành cách đây hơn ba thế kỷ cho lời giải một bài toán hoàn toàn khác.

Âm thanh đi theo đường cong nào?

Nhiều năm trước, một trong những tác giả của bài viết này đã viết về tối ưu hóa vật lý đô thị. Tôi không giành được vị trí đầu tiên nhưng cũng không vô ích: một bài toán thật đáng nhớ. Cô ấy có câu số 2 và nói về tín hiệu âm thanh truyền trong nước, trong đó tốc độ âm thanh phụ thuộc vào độ sâu. Những học sinh lớp mười siêng năng giải quyết thậm chí còn không nghi ngờ rằng bài toán này có mối liên hệ sâu sắc (theo mọi nghĩa). Chúng tôi thậm chí còn không chắc liệu chính tác giả của nó có biết về nó hay không. Từ đó tiến một bước tới nguyên lý tối ưu nổi tiếng trong lý thuyết cực trị, nguyên lý có nhiều ứng dụng trong các ngành khoa học khác. Chúng ta sẽ rút ra nguyên tắc này và từ từ lần theo những ứng dụng khác nhau của nó, định kỳ làm chúng ta xao lãng với lịch sử và khả năng khái quát hóa. Nhưng trước tiên, hãy trình bày chính bài toán (chúng tôi đã thay đổi cách diễn đạt một chút).

Bài toán. Được biết, ở các vĩ độ ánh sáng, tốc độ truyền âm trong nước trong điều kiện bình thường tăng theo độ sâu theo công thức $v(h) = 1450 + 0,0167h$. Xác định độ sâu tối đa mà tín hiệu âm thanh mạnh có hướng phát ra ở góc $15^\circ$ so với mặt nước. Định luật khúc xạ sóng âm cũng giống như định luật khúc xạ ánh sáng.

DOI: https://doi.org/10.4213/kvant20251001

Lời giải. Chúng ta chỉ chia nước thành nhiều lớp ngang mỏng và trong mỗi lớp tốc độ sẽ được coi là không đổi. Khi đó tín hiệu âm thanh sẽ có dạng một đường đứt nét, liên kết thứ $k$ của nó sẽ đi qua lớp thứ $k$ và cắt nó một góc $\alpha_k$ (hình 1). Đã viết ra luật
Hình 1
đứt gãy ở ranh giới lớp, chúng ta thu được $\frac{\cos \alpha_{k+1}}{\cos \alpha_k} = \frac{v_{k+1}}{v_k}$, trong đó $v_k$ là vận tốc trong lớp thứ $k$.
Ở dạng thông thường, định luật khúc xạ, hay định luật Snell, được viết bằng cách sử dụng sin của các góc so với pháp tuyến, tất nhiên là giống nhau. Hãy viết lại nó ở dạng $\frac{\cos \alpha_{k+1}}{v_{k+1}} = \frac{\cos \alpha_k}{v_k}$. Sau đó, bằng quy nạp, chúng tôi giả sử rằng mối quan hệ $\frac{\cos \alpha_k}{v_k}$ là giống nhau đối với tất cả các lớp. Ở độ sâu tối đa $h$ chúng ta có $\alpha_N = 0$. Chúng ta thu được phương trình $\frac{\cos \alpha_N}{v_N} = \frac{\cos \alpha_1}{v_1}$, trong đó $v_1 = 1450$, $\alpha_1 = 15^\circ$ và $v_N = 1450 + 0,0167h$. Thay thế các giá trị đã biết, chúng ta tìm thấy đáp số: $h = 3063$ m.

Công thức đưa ra trong các điều kiện là một công thức Wilson được đơn giản hóa một chút. Điều này đúng ở nhiệt độ thấp và bình thường

⟦folio 3⟧

---
running_head:
folio:
---

độ mặn của nước thấp. Khoảng cách 3
km không nên làm phiền chúng tôi. trong nước
có thể nghe được âm thanh có cường độ trung bình
kéo dài hơn 15-20 km, và
tín hiệu mạnh mẽ – hơn 100 km.
Tín hiệu không chạm tới đáy không phải vì
sẽ mờ dần, nhưng vì nó sẽ đi dọc theo một đường cong.
Chúng tôi sẽ không quan tâm đến mức tối đa
độ sâu và hình dạng của quỹ đạo và (mà
đặc biệt quan trọng!) thời điểm nó trôi qua.
Nếu chúng ta chọn những quỹ đạo tùy ý
điểm $A$ và $B$ thì cung giữa chúng sẽ là
đường cong có thời gian ngắn nhất
bạn có thể nhận được từ $A$ đến $B$ với tốc độ
$v(h)$, được tính bằng công thức Wilson.
Chúng ta biết điều này từ quang học: ánh sáng (trong trường hợp này
trường hợp - âm thanh) luôn đi theo con đường của
thời gian, và đường đi này tuân theo định luật khúc xạ. Chúng tôi sẽ sử dụng luật này.

Phương pháp quang học
Vì vậy, một tín hiệu âm thanh định hướng
đi theo quỹ đạo có thời gian ngắn nhất. Sẽ ra sao nếu tốc độ âm thanh
ở độ sâu sẽ không được tính theo công thức
Wilson, nhưng sử dụng một công thức khác? Đáp số
mọi chuyện sẽ khác, nhưng nguyên tắc lời giải
sẽ vẫn như cũ. Biểu diễn môi trường dưới dạng
kết hợp các lớp mỏng, chúng ta có được,
rằng tỷ số cosin của góc nghiêng của giao thông
vectơ và tốc độ âm thanh không đổi trong suốt
cách. Vì vậy, mối quan hệ này là một quỹ đạo bất biến. Thay thế
các công thức khác nhau cho tốc độ âm thanh,
chúng ta thu được lời giải của nhiều cực trị
bài toán, không còn liên quan đến quang học nữa.
Chúng ta sẽ chuyển từ tia âm thanh sang nhiều hơn nữa
ánh sáng chúng ta đã quen và xem xét
mặt phẳng tọa độ chuẩn.
Mặt phẳng được tạo ra từ một môi trường tùy ý,
chiết suất của nó phụ thuộc vào
chỉ từ khoảng cách đến trục $x$. Vì thế
Như vậy, tốc độ ánh sáng tùy ý
điểm $(x; y)$ bằng $v(y)$, hàm này được cho
TRÊN. Chúng ta sẽ coi nó khả vi,
t.e. sự thay đổi chỉ số khúc xạ
dần dần. Giả sử vật chất
điểm muốn nhận được từ một điểm nhất định $A$
để điểm $B$ trong thời gian ngắn nhất, đồng thời
tốc độ tại mỗi thời điểm là

Giá trị hàm $v(y)$. Như chúng ta đã biết
nó phải di chuyển dọc theo đường đi của chùm tia
ánh sáng, và quỹ đạo này có thể được mô tả bằng
sử dụng bất biến $\frac{\cos \alpha}{v(y)} = \text{const}$, trong đó $\alpha$ –
góc mà đường đi giao nhau
đường ngang tại điểm $(x; y)$
(hình 2). Tất nhiên góc độ này phụ thuộc vào
dấu chấm và sẽ đúng hơn nếu viết $\alpha(x)$.
Chúng tôi sẽ đề xuất rằng quỹ đạo
là đồ thị của hàm số nào đó
$y = f(x)$. Sau đó $\alpha = \alpha(x) - \text{угол}$, mà
tạo thành một tiếp tuyến với đồ thị với trục $x$
điểm $(x; f(x))$.

Trong số tất cả các hàm $f(x)$, đồ thị kết nối hai điểm cho trước trên mặt phẳng, chúng ta phải tìm hàm mà chuyển động dọc theo đồ thị mất ít thời gian nhất.

Định lý 1. Hàm số $y = f(x)$ tương ứng với thời gian chuyển động nhỏ nhất dọc theo đồ thị với tốc độ $v(y)$,
có tài sản $\frac{\cos \alpha}{v(y)} = \text{const}$.

Bằng chứng. Nếu hàm $f$ đơn điệu thì tại mỗi điểm trên đồ thị của nó, nó phải tuân theo định luật khúc xạ ánh sáng, như chúng ta đã biết, dẫn đến công thức đã chỉ ra. Trong trường hợp tổng quát, thể tích của đồ thị nằm trên khoảng đơn điệu.

Tỷ lệ $\frac{\cos \alpha}{v(y)}$ thay đổi liên tục và không đổi ở mỗi khoảng thời gian, nghĩa là nó không đổi trong toàn bộ đường đi. Định lý đã được chứng minh.

Trước khi chuyển sang các nhiệm vụ cực đoan, hãy làm rõ các quy tắc. Điều này rất quan trọng!
Sự không đổi của tỷ số cosine và tốc độ chỉ là điều kiện cần để có hiệu suất tối ưu, nhưng chưa đủ. Chúng tôi sẽ không tính toán tất cả các đường cong thỏa mãn điều kiện này và chúng tôi sẽ không chứng minh đường cong tối ưu. Chúng ta đã kết thúc rồi

⟦folio none⟧

---
running_head:
folio:
---

đi quá xa vào phép tính biến phân. Có thể có một số đường cong như vậy và chúng tôi (không cần chứng minh) sẽ chọn đường cong đạt được thời gian ngắn nhất. Cuối cùng, chúng ta hãy loại bỏ trường hợp tầm thường $f(x) = \text{const}$, khi đồ thị là một đường nằm ngang. Trong trường hợp này, $\cos \alpha = 1$ và tốc độ $v(y)$ là không đổi, vì tọa độ $y$ là không đổi. Do đó, tính chất bất biến được thỏa mãn. Tuy nhiên, trong hầu hết bài toán trường hợp ngoại lệ này không đưa ra giá trị tối thiểu và không được xem xét. Do đó, chúng ta sẽ luôn giả định rằng $f$ không biến thành một hằng số giống hệt nhau trên bất kỳ khoảng nào, tức là đường cong không chứa các đoạn nằm ngang.

Như thường được thực hiện trong phân tích, chúng ta sẽ nói rằng số khác 0 $a$ là “gần bằng” với số $b$ nếu hiệu của chúng nhỏ hơn nhiều so với $a$. Tương tự như vậy đối với các biến có độ lớn $a, b$: nếu cả hai đều có xu hướng bằng 0 thì “$a$ gần bằng $b$” có nghĩa là tỷ lệ $(a-b)/a$ có xu hướng bằng 0.

Quy tắc cài đặt. Hãy bắt đầu!

Về brachistochrone một lần nữa

Câu chuyện về đường cong dốc nhất đã được mô tả chi tiết trong các bài báo, sách vở. Nhiều người coi đây là một trong những bước ngoặt trong lịch sử toán học. Chính từ bài toán mà brachistochrone bị thiếu trong phép tính ngây thơ hiện đại. Cô ấy đã chứng minh sức mạnh của phân tích toán học, lúc đó nó mới giành được quyền. «Kvant» cũng đề cập đến chủ đề này [1]. Ngay cả bây giờ chúng ta cũng sẽ không thể giải quyết được nó, vì đó là lúc Johann Bernoulli (1667–1748), người đã phát hiện ra định luật của lý thuyết chất lỏng không nén được, lần đầu tiên sử dụng phương pháp quang học. Ông đã áp dụng nó, như người ta nói, chẳng hạn: trong trường hợp của ông, đại lượng $v(y)$ chính xác là tốc độ, mặc dù không phải của ánh sáng mà là của một điểm vật chất. Sau đó, chúng ta sẽ thấy rằng có thể đạt được mức độ trừu tượng cao hơn - trong các nhiệm vụ không còn liên quan đến chuyển động.

Vào tháng 6 năm 1696, Johann Bernoulli đã xuất bản một ghi chú trên tạp chí Acta Eruditorim với tiêu đề hấp dẫn: “bài toán mới, mà các nhà toán học lời giải được mời tham gia.”

Vấn đề của Bernoulli. Trong mặt phẳng thẳng đứng cho điểm $A$ và $B$. Điểm phải uốn dọc theo đường cong nào dưới tác dụng của độ mềm của chính nó để khi di chuyển đến $A$, nó sẽ đến B trong thời gian ít nhất?

Ngay cả Galileo cũng hiểu rằng đường thẳng tuy ngắn nhất nhưng không cho lời giải. Bằng thực nghiệm, ông đã chứng minh rằng đường đi dọc theo một cung tròn sẽ nhanh. Không hoàn toàn rõ ràng liệu ông có cho rằng chính cung của một đường tròn là nơi đi xuống nhanh nhất hay không. I. Bernoulli đã tìm thấy đường cong giảm dần nhanh nhất và đánh dấu đáp số dưới từ “brachistochrone”, trong tiếng Hy Lạp - “thời gian ngắn nhất”. Vấn đề nhận được năm lời giải, tất cả đều đúng. Tuy nhiên - của tác giả, những người khác đến từ Leibniz, L'Hopital, từ anh trai ông Jacob Bernoulli, và bức thư cuối cùng được gửi đến là ẩn danh. Tuy nhiên, trong đó, tác giả Isaac Newton ngay lập tức được nhận diện bởi phong cách hoàn hảo của mình, “như người ta nhận ra một con sư tử bằng những khúc gỗ của nó”.

Mọi người đều thích lời giải Bernoulli của tác giả là tác phẩm thanh lịch và bất ngờ nhất. Ông đề xuất thay thế chuyển động của một điểm bằng sự truyền lan của một cung ánh sáng trong một môi trường không đồng nhất. Trong trường hợp này, chiết suất của môi trường được chọn sao cho tương ứng với tốc độ của điểm ở một độ cao nhất định. Cái sau có thể dễ dàng tính toán từ định luật bảo toàn năng lượng. Bernoulli không viết ra một cách rõ ràng bất biến $\frac{\cos \alpha}{v}$, nhưng đã tìm ra lời giải từ việc xem xét hình học. Đáp số, ẩn dưới bút danh “brachistochrone”, hóa ra là cung tròn của xích lô - một đường cong được mô tả bằng một điểm trên đường tròn lăn không xuyên qua một đường thẳng. Trong trường hợp này, đường ngang này đi qua điểm $A$. Bất kỳ điểm $B$ nào nằm bên dưới $A$ đều có thể được kết nối với vòm $A$ của một cyclops như vậy và theo một cách độc đáo. Trên hình 3 điểm $A$ và $B$ nằm gần như cùng một độ cao. Để di chuyển từ $A$ đến $B$ trên Cyclops, trước tiên bạn phải đi sâu vào

⟦folio 4⟧

---
running_head:
folio:
---

hố sâu, rồi tăng lên điểm $B$. Hóa ra con đường nghịch lý này lại cho thời gian ngắn nhất!

Phương pháp quang học ở đây trông khá tự nhiên. Vận tốc ở độ cao $y$ được tính từ định luật bảo toàn năng lượng $\frac{mv^2}{2} + mgy = const$. Chúng ta đặt gốc tọa độ ở $A$, vì vậy chiều cao $y$ sẽ âm. Hằng số bằng 0 vì chúng ta bắt đầu từ $A$ với tốc độ bằng 0. Vì vậy, $v(y) = \sqrt{-2gy}$. Bây giờ là ví dụ về Định lý 1. Vì đã biết đáp số, nên chúng ta chỉ cần chứng minh rằng xoáy thuận thỏa mãn điều kiện bất biến $\frac{\cos \alpha}{v(y)} = const$.

Lời giải bài toán Bernoulli. Một hình tròn có bán kính $R$ lăn dọc theo trục $x$, chạm vào nó màu xanh lam (hình 4). Một điểm tùy ý $M$ của đường tròn mô tả cung của xoáy thuận từ điểm $A$ đến $B$. Tốc độ của nó $v$ tại mỗi thời điểm có hướng tiếp tuyến với lốc xoáy. Chúng ta hãy biểu thị bằng $C$ tâm của vòng tròn và $u$ tốc độ di chuyển của nó (chữ $v$ đã được sử dụng). Lưu ý rằng vận tốc $u$ và $v$ không phải là hằng số; tại mỗi điểm của lốc xoáy chúng khác nhau. Chúng tôi chỉ biết rằng $v(y) = \sqrt{-2gy}$. Bây giờ chúng ta sẽ liên hệ các đại lượng này với phương trình.

Chuyển động không bị trượt nên điểm $M$ chuyển động với cùng tốc độ $u$ so với tâm $C$, tốc độ này hướng tiếp tuyến với đường tròn. Theo nguyên lý cộng vận tốc, tốc độ cuối cùng của điểm $M$ bằng tổng của hai vận tốc này. Chúng ta sẽ tìm tổng bằng cách sử dụng quy tắc paradlogograph, trong trường hợp này là hình thoi. Tốc độ được hướng dọc theo đường chéo của hình thoi $MF$, do đó $\alpha = \angle DMF$ là góc giữa tốc độ và trục $x$. Đường chéo của hình thoi là đường phân giác của nó, vì vậy $\angle DME = 2\alpha$. Cuối cùng, $ME$ tiếp tuyến với đường tròn nên $\angle EMC = 90^\circ$. Tọa độ của điểm $M$ là

$$y = -R\left(1 + \sin\left(90^\circ - 2\alpha\right)\right) = -2R\cos^2\alpha,$$

Ở đâu

$$v(y) = \sqrt{-2gy} = 2\sqrt{gR}\cos\alpha.$$

Vì thế,

$$\frac{\cos\alpha}{v(y)} = \frac{1}{2\sqrt{gR}} = const,$$

do đó, xoáy thuận thỏa mãn các điều kiện của Định lý 1 và bài toán lời giải.

Trong bài toán brachistochrone được thảo luận trong khoảng thời gian ít nhất. Bây giờ chúng ta sẽ thực hiện thêm một bước nữa và giảm thiểu các đại lượng khác - diện tích, thế năng, khoảng cách. Điều đáng ngạc nhiên là phương pháp quang học cũng sẽ xuất hiện ở đó.

vấn đề cao nguyên

Chúng ta sẽ sử dụng phương pháp quang học để giảm thiểu diện tích. Điều này sẽ được thực hiện thông qua việc lựa chọn đặc biệt các chức năng tốc độ $v(y)$.

Hãy xem xét bài toán sau đây. Một bộ giới hạn $V$ được đưa ra trong không gian; cần phải bao bọc bề mặt của nó với diện tích nhỏ nhất. Nói cách khác, trong số tất cả các bề mặt kín chứa $V$, chúng ta cần tìm bề mặt có diện tích nhỏ nhất. Chúng ta sẽ biểu thị bề mặt này bằng $S$ và ký hiệu tương tự sẽ biểu thị diện tích của nó. Điều kiện cho phép bề mặt có thể bị ngắt kết nối, tức là bao gồm nhiều mảnh.

Nếu tập $V$ bao gồm một số hữu hạn các điểm thì nó có thể được phủ bằng một bề mặt

⟦folio none⟧

---
running_head:
folio:
---

cung tròn có tâm $E$ và một số góc khoảng cách từ $E$ đến giữa $CD$. Trừ đi diện tích của các phần hình tròn bên ngoài và bên trong, chúng ta có được
$$\frac{\gamma}{2}\left(d + \frac{r}{2}\right)^2 - \frac{\gamma}{2}\left(d - \frac{r}{2}\right)^2 = \gamma dr.$$
Lưu ý rằng $\gamma d$ là độ dài cung của hình tròn có tâm $E$ và bán kính $d$. Cung này thu được (do sự phát triển của vòng) từ vòng tròn quay của đoạn giữa đoạn $CD$ so với trục $x$. Độ dài của vòng tròn này là $2\pi m$, vì vậy $\gamma d = 2\pi m$. Vì vậy, trong trường hợp này, diện tích của chiếc nhẫn là $2\pi mr$.

Chúng ta thấy rằng diện tích của một vòng trong cả hai trường hợp đều bằng $2\pi mr$. Bây giờ chúng ta hãy thực hiện bước chính: tìm tốc độ $v$ mà tại đó thời gian di chuyển đoạn $CD$ bằng số với diện tích của vòng tròn. Rất đơn giản: diện tích là $2\pi mr$ và thời gian là $\frac{r}{v}$. Do đó, $\frac{r}{v} = 2\pi mr$, do đó $v = \frac{1}{2\pi m}$. Vì vậy, một điểm chuyển động với tốc độ $v = \frac{1}{2\pi m}$ đi qua một đoạn đường đứt nét $CD$ trong thời gian bằng số diện tích của vòng tròn. Do đó, thời gian cần thiết để đi qua toàn bộ đường đứt nét bằng tổng diện tích của các vòng, xấp xỉ bằng $S'$. Vận tốc trên mỗi mắt xích của đường đứt bằng
$$\frac{1}{2\pi m} \approx \frac{1}{2\pi f(x)} = \frac{1}{2\pi y(x)}.$$
Vì vậy, chúng ta có thứ chính - chức năng tốc độ $v(y)$. Diện tích bề mặt quay của đồ thị của hàm $f(x)$ bằng số với thời gian để đi qua đồ thị này với tốc độ thay đổi $v(y) = \frac{1}{2\pi y}$. Áp dụng Định lý 1 và xét rằng trong trường hợp $\frac{\cos \alpha}{v(y)} = 2\pi y \cos \alpha$ này, chúng ta thu được mô tả bề mặt của diện tích nhỏ nhất.

**Định lý 2. Hàm $y = f(x)$, tạo ra một bề mặt quay tối thiểu chứa “schmanga”, có tính chất $y \cos \alpha = \text{const.}$**

Nói cách khác, cosin của góc $\alpha(x)$ của tiếp tuyến với đồ thị tại điểm $(x; y)$ với trục $x$ tỷ lệ nghịch với $y$. Một đường cong có đặc tính này, một viên đá, được tính theo công thức $y = chx$, trong đó $chx = \frac{1}{2}\left(e^x + e^{-x}\right) - \text{гиперболический косинус. График этой функции (рис. 8)}$

giống như một paraboly, vì đối với $x$ nhỏ, hàm $chx$ gần bằng $1 + \frac{x^2}{2}$, nhưng sau đó nó bắt đầu phát triển nhanh hơn nhiều. Nếu người đọc đã quen với tính chất tùy ý và các tính chất của số mũ $e^x$, thì có thể dễ dàng chứng minh rằng catenonade có tính chất $y \cos \alpha = \text{const.}$ Nếu không, xin hãy tin lời chúng tôi.

**Xây dựng bề mặt tối thiểu**

Việc tìm ra công thức cho đường cong tối ưu là chưa đủ; bạn cũng cần kiểm tra đường cong này thông qua các điểm $(-a; R)$ và $(a; R)$ đã cho. Catenade có thể được dịch chuyển song song bởi vectơ $(c; b)$ và được tạo sẵn với hệ số $k$:

$$f(x) = b + k \text{ ch}\left(\frac{x - c}{k}\right).$$

Trong trường hợp của chúng tôi, có thể dễ dàng tìm thấy $c, b$ từ tính đối xứng: $b = c = 0$, nhưng cần phải tính hệ số $k$. Để làm điều này, chúng ta tìm điểm $D$ giao điểm của đồ thị hàm số $y = chx$ với đường thẳng $y = \frac{R}{a}x$. Để điểm sẵn sàng có hệ số $k$ di chuyển điểm $D$ đến điểm $(a; R)$. Sau đó, catenonade cần thiết được tính theo phương trình $y = k \text{ ch}\left(\frac{x}{k}\right)$. Đây là cách chúng tôi tìm thấy lời giải bài toán Cao nguyên cho “shanga”.

⟦folio 10⟧

---
running_head:
folio:
---

qini $y = -\text{ch} x$ chúng ta vẽ một tiếp tuyến và vuông góc với nó (bình thường ngoài). Góc giữa pháp tuyến và vuông góc $KM$ với trục $x$ bằng góc giữa tiếp tuyến và trục $x$, tức là bằng $\alpha$. Ở đâu

$$KM \cdot \cos \alpha = |y| \cos \alpha = \text{const.}$$

Điều này có nghĩa là độ dài hình chiếu của đoạn thẳng đứng $KM$ lên pháp tuyến bên ngoài tại điểm $M$ là như nhau đối với tất cả các điểm của đồ thị.

Hãy tưởng tượng rằng toàn bộ không gian phía trên biểu đồ, cho đến trục $x$, được lấp đầy bằng bê tông. Một lớp bê tông thẳng đứng nằm dọc theo đoạn $KM$ ép vào điểm $M$ với một lực tỉ lệ với chiều dài $KM = |y|$. Hình chiếu của lực này lên pháp tuyến bên ngoài là thành phần pháp tuyến của lực áp suất. Vì vậy, thành phần pháp tuyến của lực ép là như nhau tại mọi điểm trên đồ thị của hàm số $y = -\text{ch} x$.

Do đó, vòm ở dạng vòm dây xích) sẽ phân bổ đều áp lực dọc theo toàn bộ chiều dài. Vì vậy, vòm như vậy là đáng tin cậy nhất. Và thật dễ dàng để xây dựng hình dạng của vòm đáng tin cậy nhất - treo một sợi dây xích ở hai đầu và phản chiếu hình ảnh. Kiến trúc sư đã luôn luôn sử dụng điều này. Do đó, vào ngày hình 13, Arch of Khosrow nổi tiếng được mô tả, phần trung tâm của Cung điện Trắng ở Ctesiphon (thế kỷ VI, Cung điện của Sassanid Shah, Prak), vào ngày hình 14 – Casa Mila, một tòa nhà dân cư ở Barcelona, ​​​được xây dựng vào năm 1906-1910 bởi kiến ​​trúc sư nổi tiếng người Tây Ban Nha Antonio Gaudi.

Hình 14

Mô hình Poincaré của mặt phẳng lobachevsky

Bây giờ chúng ta phải giải nghịch đảo bài toán: tìm hàm tốc độ $v(y)$ nếu biết trước quỹ đạo tối ưu. Vậy chúng ta sẽ hiểu khái niệm đường $\delta$ trong một trong các mô hình hình học phi Euclide.

Hình học phi Euclid ra đời từ những nỗ lực chứng minh tính bất khả thi của nó. Trong gót chân của các tiên đề Euclid, tiên đề cuối cùng, thứ năm, không hoàn toàn rõ ràng. Nó giả định rằng từ bất kỳ điểm nào không thuộc một đường thẳng cho trước, người ta có thể kiểm tra một đường thẳng song song với nó. Liệu có thể rút ra tiên đề này từ bốn tiên đề kia, hay ít nhất là từ những tính chất bổ sung, rõ ràng hơn của mặt phẳng và đường thẳng? Giả sử điều ngược lại - rằng có một điểm mà từ đó chúng ta có thể kiểm tra ít nhất hai đường không giao nhau với đường thứ ba, chúng ta sẽ sớm phát triển những tuyên bố sâu sắc. Ví dụ: tổng các góc của bất kỳ tam giác nào đều nhỏ hơn $180^\circ$.

Hình học phi Euclid được phát triển độc lập bởi K.F.Gauss (1777-1855), J.Bolyai (1802-1860) và N.I.Lobachevsky (1792-1856). Sau này tiếp tục tiến xa hơn trong việc xây dựng và không bao giờ đi đến mâu thuẫn logic. Mặc dù nhiều sự thật được khám phá ra đối với họ mâu thuẫn với trực giác cơ bản. Ví dụ, trong hình học của Lobachevsky không có hình nào là hình vuông. Nếu không, nó sẽ bị chia theo đường chéo thành hai hình tam giác bằng nhau có tổng các góc $180^\circ$. Không có một cặp hình nào giống nhau và không bằng nhau. Ví dụ, nếu có hai cái giống nhau

⟦folio 11⟧

---
running_head:
folio:
---

ny tam giác, sau đó kết hợp một trong các góc của chúng, chúng ta sẽ có một tứ giác (tam giác lớn hơn trừ tam giác nhỏ hơn) với tổng các góc là 360°. Chia nó cho một đường chéo, chúng ta sẽ có hai hình tam giác, ít nhất một trong số đó có tổng các góc ít nhất là 180°. Cuối cùng, điều có vẻ khá hiển nhiên đối với các quốc gia, trên bình diện Lobachevsky không có hình tam giác nào có diện tích cực lớn. Diện tích của tất cả các hình tam giác bị giới hạn bởi một hằng số nhất định.

Vào cuối thế kỷ 19, một số mô hình toán học của mặt phẳng lobachevsky đã được xây dựng, chứng minh tính nhất quán với điều kiện hình học chính là nhất quán. Một trong số đó, được đặt theo tên nhà toán học xuất sắc người Pháp Henri Poincaré (1854–1912), được đề xuất bởi một nhà khoa học khác, Eugen Beltrami (1835–1900). Mô hình này không chỉ chứng minh tính nhất quán của hình học Lobachevsky mà còn giúp chứng minh nhiều phát biểu của nó trong khuôn khổ hình học cơ bản.

Mặt phẳng Lobachevsky trong mô hình Poincaré là nửa mặt phẳng trên của mặt phẳng khóa chung. Ranh giới của nó, trục $x$, được gọi là trục tuyệt đối hoặc đơn giản là trục; nó không được bao gồm trong nửa mặt phẳng trên (hình 15). Các đường thẳng trong mặt phẳng Lobachevsky là nửa trên của đường tròn có tâm nằm ở điểm tuyệt đối. Hình bán nguyệt mở, tức là không bao gồm các đầu nằm trên tuyệt đối. Ngoài ra, trong số các đường thẳng còn có các tia thẳng đứng mở bắt đầu từ trục $x$. Người đọc có thể dễ dàng chứng minh rằng qua hai điểm bất kỳ có thể vẽ được một đường thẳng. Hơn nữa, qua mỗi điểm không nằm trên một đường thẳng cho trước, có thể vẽ được nhiều đường thẳng không cắt nhau. Tuy nhiên, để đáp ứng đầy đủ tất cả các tiên đề, bạn vẫn cần đưa ra khái niệm về chiều dài và góc. Nhập chiều dài không phải là quá dễ dàng! Rốt cuộc, ở độ dài này, các đường ngắn nhất phải là hình bán nguyệt với các đầu nằm trên trục! Do đó, độ dài trên nửa mặt phẳng Poincaré phải khác nhau. Cái mà?

Tất nhiên, bản thân Beltrami đã biết trước đáp số, từ lý thuyết về hàm biến phức. Chúng tôi sẽ chỉ cho bạn cách xây dựng độ dài này bằng các phương tiện cơ bản.

Hãy sử dụng lại sự tương tự quang học. Chúng tôi sẽ đo khoảng cách không phải bằng mét mà bằng giây. Khoảng cách giữa các điểm $A$ và $B$ bằng thời gian chuyển động của tia sáng từ $A$ đến $B$. Với khoảng cách như vậy, cả bất đẳng thức tam giác và định luật tổng khoảng cách của ba điểm trên một đường thẳng đều đúng.

Nếu môi trường đồng nhất thì ánh sáng sẽ di chuyển với tốc độ như nhau trong toàn bộ diện tích, và do đó, đường đi ngắn nhất sẽ là đường thẳng (Euclide). Chúng ta cần tìm hàm tốc độ $v(y)$ trên nửa mặt phẳng mà đường đi ngắn nhất sẽ luôn là bạn của đường tròn có tâm trên trục $x$. Vì vậy, chúng ta đã đi đến nghịch đảo bài toán: tìm hàm tốc độ $v(y)$ nếu quỹ đạo được cho trước.

Nếu các điểm $A$ và $B$ được nối với một đường tròn khác có tâm tại điểm $P$ trên trục $x$ thì theo Định lý 1 cho tất cả các điểm $M$ của cung này $\frac{\cos \alpha}{v(y)} = c$ phải được thỏa mãn. Ở đây $y - расстояние от $M$ до оси $x$, и $\alpha là góc giữa tiếp tuyến $KM$ với đường tròn và trục (hình 16). Vì góc này trong một tam giác vuông $KMP$ bằng góc giữa chân $MP$ và chiều cao $y$, nên chúng ta thu được $\cos \alpha = \frac{y}{MP}$, từ đó $v(y) = \frac{1}{c \cdot MP} y$.

Không $MP$ – bán kính của hình tròn, tức là các giá trị không đổi. Vì vậy, $\frac{\cos \alpha}{y} = const$,

⟦folio 12⟧

---
running_head:
folio:
---

điều này có nghĩa là tốc độ $v(y)$ tỷ lệ thuận với $y$.
Để đơn giản ta chọn hệ số tỉ lệ với 1 ta được $v(y) = y$. Ở tốc độ này, ánh sáng giữa $A$ và $B$ di chuyển theo hình cung tròn có tâm ở trục $x$.

Hãy để chúng tôi nhấn mạnh lại: chúng tôi chỉ chứng minh rằng cung của một đường tròn có tâm nằm trên trục là nghiệm của phương trình $\frac{\cos \alpha}{y} = \text{const}$.
Chúng tôi chưa chứng minh được rằng lời giải này là duy nhất và cũng chưa chứng minh được rằng nó thực sự mang lại thời gian ngắn nhất. Các phương pháp tính các biến phân (dữ liệu nằm ngoài phạm vi của bài viết này) giúp chứng minh rằng cả hai đều đúng.

**Định lý 4.** Nếu tốc độ tại mỗi điểm $(x; y)$ của nửa mặt phẳng trên là $y$, thì đường đi ngắn nhất giữa hai điểm bất kỳ (tức là đường đi mà người ta có thể đi từ điểm này đến điểm khác trong thời gian tối thiểu) sẽ là một cung của đường tròn có tâm trên trục.

Nếu các điểm $A$ và $B$ nằm trên cùng một đường thẳng đứng thì đường tròn sẽ biến thành một tia thẳng đứng.

Sau khi hiểu được độ dài, bây giờ chúng ta có thể đưa ra một số phát biểu quan trọng.

**Mệnh đề 1.** Mỗi hệ thống kết quả có điểm cuối trên mặt tuyệt đối có chiều dài vô hạn. Đường x không thể tiếp cận được từ bất kỳ điểm nào của nửa mặt phẳng trên.

Chúng tôi sẽ đưa ra một bằng chứng chặt chẽ sau đó một chút, nhưng bây giờ chúng tôi sẽ giới hạn ở việc phân vùng. Hãy chứng minh rằng một điểm tùy ý sẽ di chuyển về phía trục $x$ dọc theo đường vuông góc trong thời gian vô hạn. Hãy để cô ấy đi được nửa thời gian $T$. Đi được nửa đường còn lại, tọa độ $y$ của các điểm tương ứng sẽ lớn bằng một nửa, tức là nó sẽ di chuyển với tốc độ một nửa và đi được một nửa quãng đường. Do đó, nó sẽ đi được một nửa quãng đường còn lại trong cùng thời gian $T$. Một nửa khoảng cách còn lại sẽ lại mất thời gian $T$, v.v.

**Phát biểu 2.** Nghịch đảo đối với đường tròn có tâm ở điểm tuyệt đối là sự đối xứng trục của mặt phẳng Lobachevsky trong mô hình Poincaré.

Đối xứng trục có thể được mô tả là các chuyển động của mặt phẳng để lại các điểm của một đường nhất định tại chỗ và thay đổi vị trí của các điểm khác. Sự đảo ngược của một đường tròn có tâm nằm trên trục khiến tất cả các điểm của đường tròn này cố định. Pozny vẫn phải chứng minh rằng chuyển động này, tức là sự đảo ngược đó không làm thay đổi khoảng cách.

Như mọi khi, chỉ cần chứng tỏ rằng nó “gần như” không làm thay đổi khoảng cách giữa các điểm gần nhau thì bất kỳ đoạn thẳng nào cũng được chia thành các đoạn nhỏ, v.v. Hãy lấy một đường thẳng tùy ý trong mô hình Poincaré. Nếu nó được biểu diễn bằng một tia trực giao với trục thì phép đảo ngược sẽ trở thành đối xứng trục và không chứng tỏ được điều gì. Giả sử nó được biểu thị bằng một hình tròn có bán kính $R$ với tâm $O$. Hãy lấy hai điểm gần nhau $A$, $B$ (hình 17); sự đảo ngược đưa chúng tới các điểm $A'$, $B'$. Vì $OA \cdot OA' = OB \cdot OB' = R^2$, nên $\frac{OA}{OB'} = \frac{OB}{OA'}$ và do đó, các tam giác $OAB$ và $OB'A'$ tương tự nhau với một số hệ số $k$. Hệ số này bằng tỷ lệ độ dài của các đoạn $AB$ và $A'B'$, cũng như tỷ lệ $\frac{OA}{OB'}$, gần bằng tỷ lệ $\frac{OA}{OA'}$, vì các điểm $B'$ và $A'$ gần nhau. Mặt khác, $\frac{OA}{OA'} = \frac{y_A}{y_A'}$ = $\frac{v(y_A)}{v(y_A')}$, trong đó $y_A$ và $y_A'$ là tọa độ của các điểm $A$ và $A'$. Vì vậy, $\frac{AB}{A'B'} = k \approx \frac{v(y_A)}{v(y_A')}$. Vì các đoạn nhỏ nên chúng ta có thể giả sử rằng toàn bộ đoạn $AB$ chuyển động với tốc độ

⟦folio 13⟧

---
running_head:
folio:
---

$v(y_A)$ và toàn bộ đoạn $A'B'$ được chạy ngang với tốc độ $v(y_A')$. Như vậy, tỉ số độ dài của các đoạn bằng tỉ số giữa tốc độ, nghĩa là các đoạn đó được bao phủ trong cùng một thời gian.

Bây giờ chúng ta có thể chứng minh một cách chặt chẽ mệnh đề 1. Nếu một điểm di chuyển đến trục $x$ dọc theo một đường tròn tùy ý có tâm nằm trên trục (tức là dọc theo một đường thẳng tùy ý trên mặt phẳng Lobachevsky), thì bằng cách sử dụng phép đảo ngược thích hợp, biến đường tròn này thành một đường thẳng (Euclide), chúng ta sẽ có một điểm chuyển động vuông góc với trục. Nó, như được hiển thị trước đó, sẽ di chuyển vô thời hạn.

Lưu ý rằng trong mặt phẳng lobachevsky, định lý Chall cũng được thỏa mãn (và được chứng minh theo cách tương tự): mọi chuyển động đều là sự hợp thành của không quá ba đối xứng trục. Do đó, bất kỳ chuyển động nào trong mô hình Poincaré đều là sự kết hợp của không quá ba phép nghịch đảo. Như chúng ta đã biết, phép nghịch đảo bảo toàn góc giữa các đường tròn. Do đó, mọi chuyển động trong mô hình Poincaré đều bảo toàn các góc (Euclide). Điều này ngụ ý (chúng tôi bỏ qua các chi tiết) tuyên bố sau đây.

Phát biểu 3. Góc giữa các đường thẳng trong mặt phẳng Lobachevsky bằng góc (Euclide) giữa các đường tròn tương ứng trong mô hình Poincaré.

Người đọc quen với khái niệm tích phân có thể rút ra công thức tính khoảng cách giữa các điểm tùy ý $A$ và $B$. Đây được gọi là logarit của tỷ lệ kép: $\ln \left( \frac{AN}{BN} : \frac{AM}{BM} \right)$, trong đó $M, N$ là giao điểm của “đường thẳng” $AB$ (tức là một đường tròn có tâm trên trục đi qua $A$ và $B$) với đường tròn tuyệt đối. Bạn có thể đọc chi tiết về mô hình Poincaré và hình học Lobachevsky trong các bài viết [3-5].

Còn gì nữa?

Phương pháp quang học không giải quyết được mọi cực đoan bài toán. Trong hai thế kỷ qua, con người đã phát minh ra nhiều phương pháp phổ quát hơn. Tuy nhiên, họ sẽ cần chúng ta chuẩn bị nhiều hơn. Để bắt đầu, hãy làm quen với phép tính tích phân và phương trình vi phân. Đối với phương pháp quang học, điều này không cần thiết. Nó thực sự rất đơn giản. Nhưng ưu điểm chính của nó lại khác: nó cho thấy một ý tưởng đơn giản có thể đóng vai trò là đòn bẩy của Archimedean trong những bàn tay khéo léo. Và trong toán học hiện đại điều này luôn xảy ra. Những ý tưởng đột phá mới nhất rất đơn giản và rõ ràng. Thật đáng để nhìn xung quanh và truy tìm mối liên hệ giữa mọi thứ.

Chà, ngoài ra, phương pháp quang học rất đẹp! Mặc dù theo quan điểm của chúng tôi, các phương pháp hiện đại cũng không kém phần đẹp đẽ.

Đáp số cho câu hỏi
về phim xà phòng

Bề mặt có diện tích nhỏ nhất sẽ là phần giao của hai đường tròn. Tổng diện tích của hai bề mặt phẳng được kéo dài bởi các vòng tròn trở thành nghiệm bài toán Cao nguyên. Màng xà phòng sẽ chia thành hai phần.

Văn học

1. S. Verov. Brachistochrone, hay Một bí ẩn khác của Cyclops. – «Kvant», 1975, số 12.
2. A. Plakhov, V. Promasov. Khí động học bài toán Newton và Người vô hình. – «Kvant», 2022, số 1.
3. V. Boltyansky. Bí ẩn của “tiên đề song song” – «Kvant», 1976, số 3.
4. V. Vavilov. Hình học của một vòng tròn. – «Kvant», 1977, số 6.
5. K. Samarov, V. Uroev. Mô hình Poincaré. – «Kvant», 1984, số 6.

⟦folio 15⟧

---
running_head:
folio:
---

Kết quả có thể được viết dưới dạng vi phân:
$$dE = -\frac{3kQq}{l^4} x_0^2 dl.$$
Sau khi chia cho biên độ thế năng:
$$\frac{dE}{E} = -\frac{3kQq x_0^2}{l^4 \cdot 4 \frac{kQq}{l^3} \frac{x_0^2}{2}} dl = -\frac{3}{2} \frac{dl}{l}.$$
Việc xen kẽ dẫn đến một bất biến trong phép tính gần đúng hài hòa, tức là bất biến Einstein:
$$\ln \left(El^{3/2}\right) = inv \rightarrow El^{3/2} = inv.$$
Chúng ta tìm thấy sự thay đổi biên độ dao động khi lăn xuống theo hệ số hai:
$$x_0^2 l_0^{3/2} = x^2 \left(\frac{l_0}{2}\right)^{3/2},$$
$$x = x_0 \cdot 2^{3/4} \approx x_0 \cdot 1,68.$$
Ở biên độ lớn, các dao động trở nên phi tuyến và có thể kiểm tra sự hiện diện của bất biến (pha) tổng quát

chỉ sử dụng máy tính. Các biểu đồ (hình 16) minh họa việc kiểm tra này. Hai đồ thị đầu tiên (quỹ đạo pha và bất biến Einstein) đề cập đến các dao động có biên độ nhỏ (chế độ dao động điều hòa). Cặp đồ thị tương tự thứ hai đề cập đến các dao động có biên độ lớn. Ở đây quỹ đạo pha chỉ có dạng elip và bất biến Einstein không được bảo toàn như mong đợi. Nhưng bất biến pha (diện tích bị vectơ bán kính pha quét khi nó quay một góc 2π) được bảo toàn với độ chính xác cao.

bài toán tiếp theo nên được đặt tên là Hannes Alfvén, một nhà vật lý người Thụy Điển đã nhận giải Nobel Vật lý năm 1970 cho công trình nghiên cứu của ông trong lĩnh vực từ thủy động lực học.

Bài 7. Momen từ của điện tích
Một hạt có khối lượng m và điện tích q chuyển động với tốc độ v theo một đường tròn trong từ trường không đổi có cảm ứng B (hình 17). Tại một thời điểm nào đó

⟦folio 16⟧

---
running_head:
folio:
---

Chia ba tham số $B, v, R$ cho hai:
$$\frac{\sqrt{B}}{v} \rightarrow \frac{B}{v^2} \rightarrow \pi R^2 B \rightarrow vR = inv.$$
Ở đây thật thú vị khi lưu ý đến bất biến $\pi R^2 B = \Phi$ – sự bảo toàn độ lớn quỹ đạo của từ thông, yếu tố xác định quỹ đạo của hạt. Bất biến $vR$ bổ sung cho công thức tính mô men từ của điện tích - mômen từ của vòng dây với dòng điện (đại lượng vectơ) được xác định theo công thức
$$\vec{p}_m = i\vec{s},$$
trong đó $\vec{s}$ là vectơ diện tích bề mặt được “kéo dài” trên đường viền hiện tại (hướng của vectơ được xác định theo quy tắc vít bên phải). Mômen từ xác định năng lượng tương tác của dòng điện với từ trường thông qua tích vô hướng của vectơ: $W = -\vec{p}_m \cdot \vec{B}$. Tương tự, chúng ta có thể xác định mômen từ của một điện tích chuyển động tròn (ở dạng vô hướng):
$$p_m = \frac{q}{2\pi R/v} \pi R^2 = \frac{q}{2} vR.$$
Từ công thức này, rõ ràng bất biến $vR$ là bất biến của mô men từ của điện tích trong từ trường.
Câu hỏi về quỹ đạo pha trong bài toán này sẽ bị bỏ qua (quá khó). Nhưng vật lý của bài toán tiếp theo thì đơn giản nhưng toán học lại khá phức tạp.

Bài 8. Phiên bản dọc bài toán
Một quả bóng nhỏ chuyển động thẳng đứng, phản xạ đàn hồi từ mặt phẳng ngang phía dưới (hình 18). Tại điểm trên cùng của quỹ đạo, quả cầu thức ăn chạm vào mặt ngang của tấm ván lớn. Tại thời điểm quả bóng bật lại tiếp theo từ mặt phẳng dưới của bảng trên, chúng ta bắt đầu di chuyển xuống dưới với tốc độ không đổi rất thấp. Tốc độ của quả bóng thay đổi bao nhiêu lần (tại thời điểm bật lại từ mặt phẳng bên dưới) khi khoảng cách giữa các mặt phẳng giảm đi một nửa?

⟦folio 17⟧

---
running_head:
folio:
---

Chúng tôi đã xem xét phiên bản nằm ngang của bài toán (bài toán 1) này, khi vòng đệm (quả bóng) di chuyển dọc theo một bề mặt nhẵn nằm ngang giữa các bức tường thẳng đứng, một trong số đó lướt qua hệ thống rất chậm. Khi quét hệ thống, công việc được lưu
$$xv = inv.$$
Kết quả này tương ứng với bất biến adivational của Einstein (mặc dù các dao động không điều hòa):

$$E(x)T(x) = inv \rightarrow m \frac{v^2}{2} \frac{2x}{v} \rightarrow xv = inv.$$

Trong bài toán này (do tính phức tạp của toán học) chúng ta sẽ không rút ra công thức bất biến adival bằng phương pháp năng lượng truyền thống. Chúng ta sẽ giả sử rằng có một bất biến pha tổng quát

$$I = \frac{1}{2\pi} \oint p dq = \frac{1}{2\pi} \oint p(x) dx.$$

Để tính toán, chúng ta tìm sự phụ thuộc của xung cũ, tức là xung tại thời điểm phản xạ từ mặt phẳng thấp hơn, từ tọa độ thẳng đứng (sự phụ thuộc này có thể rút ra từ định luật bảo toàn năng lượng):

$$mv = p = m \sqrt{v_0^2 - 2gx} = p_0 \sqrt{1 - 2gx/v_0^2}.$$

Chúng ta thay hàm này vào tích phân của bất biến (chúng ta giả sử quỹ đạo là đóng):

$$I = \frac{1}{2\pi} \cdot 2p_0 \int_0^h \sqrt{1 - 2qx/v_0^2} dx =$$
$$= -\frac{1}{3\pi} m \frac{v_0^3}{g} \left(1 - \frac{2gx}{v_0^2}\right)^{3/2} \Bigg|_0^h =$$
$$= \frac{1}{3\pi} m \frac{v_0^3}{g} \left(1 - \frac{2gh}{v_0^2}\right)^{3/2}.$$

Bây giờ bạn có thể trả lời câu hỏi bài toán. Hãy viết lại đẳng thức của các bất biến:

$$v^3 \left(1 - \left(1 - \frac{2gh}{v^2}\right)^{3/2}\right) = v_0^3 \left(1 - \left(1 - \frac{2gh}{v_0^2}\right)^{3/2}\right).$$

Sử dụng điều kiện đầu và điều kiện cuối: $2h = h_0, 2gh_0 = v_0^2$ và giới thiệu biến tương đối $v/v_0 = u$, chúng ta thu được một phương trình phức tạp cho nó

$$u^3 \left(1 - \left(1 - \frac{1}{2u^2}\right)^{3/2}\right) = 1.$$

Phương trình phức tạp nhưng có thể được giải khá đơn giản bằng số (phương pháp tương tác). Đối với phương trình lời giải, chúng ta chuyển nó sang dạng

$$u = \frac{1}{1 - \left(1 - \frac{1}{2u^2}\right)^{3/2}}.$$

Khi chiều cao của mặt phẳng phản xạ giảm đi một nửa, năng lượng của hệ không thể mạnh lắm. Nếu chúng ta giả sử rằng năng lượng đã tăng gấp 2 lần thì tốc độ đã tăng $\sqrt{2}$. Chúng ta hãy coi đây là giá trị ban đầu của đại lượng mong muốn, mà chúng ta thay thế vào vế phải của phương trình cho $u$. Việc tính toán dẫn đến giá trị gần đúng đầu tiên tiếp theo của giá trị mong muốn. Lặp lại (thủ tục tính toán) được lặp lại. Chúng tôi trình bày một bảng các giá trị gần đúng liên tiếp (hình 19 ở bên trái). Có thể thấy rằng với độ chính xác đến ba chữ số thập phân lời giải đã đạt được ở bước tương tác thứ bảy. Sơ đồ pha truyền thống cung cấp một bức tranh về giải pháp.

Bây giờ chúng ta hãy quay trở lại với thiết bị điện tử.

⟦folio 19⟧

---
running_head:
folio:
---

Hai bài toán tiếp theo gắn liền với tên của Paul Ehrenfest. Trong một trong những bài viết của mình về lý thuyết lượng tử, ông xem xét hai ví dụ về các hệ thống trong đó có thể vi phạm tính bất biến adnabatic.

Bài 10. Lưỡng cực Ehrenfest

Lưỡng cực điện dao động trong một điện trường đều (hình 22). Tại một số thời điểm, cường độ của trường E bắt đầu giảm với tốc độ không đổi rất thấp. Xác định sự thay đổi các tham số dao động trong quá trình “đảo ngược” cường độ trường (vectơ cường độ thay đổi hướng của nó sang hướng ngược lại). Các đại lượng sau đây đã được biết:

$m - масса части диполя, 2l - длина диполя, $q - mô đun điện tích, $\varphi_0 - начальная амплитуда колебаний, $\alpha = \frac{dE}{dt} - tốc độ thay đổi cường độ trường.

Hãy viết định luật bảo toàn năng lượng trong dao động lưỡng cực trong trường không đổi:

$$W = \frac{p_\varphi^2}{2ml^2} - 2qlE \cos \varphi,$$

từ đó chúng ta tìm thấy sự phụ thuộc của mô men động lượng (mômen) vào góc quay:

$$p_\varphi = \sqrt{2ml^2W \left(1 + \frac{2qlE}{W} \cos \varphi\right)}.$$

Pha bất biến phụ thuộc pha:

$$I = \frac{1}{2\pi} \cdot 2 \int_0^\varphi p_\varphi(\varphi) d\varphi = \frac{\sqrt{2ml^2W}}{\pi} \int_0^\varphi \sqrt{1 + \frac{2qlE}{W} \cos \varphi} d\varphi.$$

Khoảng này không được tính toán rõ ràng vì nó được rút gọn thành bất biến elip không hoàn chỉnh thuộc loại thứ hai:

$$I = \frac{\sqrt{2ml^2W}}{\pi} \sqrt{1 + \varepsilon} \cdot \int_0^{2\alpha} \sqrt{1 - k^2 \sin^2 \alpha} d\alpha,$$

ở đâu $k^2 = \frac{2\varepsilon}{1 + \varepsilon}, \varepsilon = \frac{2qlE}{W}$. Sự phụ thuộc của bất biến $I$ vào cường độ của trường được “ẩn” trong $\varepsilon$.

Khi phân tích các thay đổi trong hệ thống, chúng ta sẽ chỉ hài lòng với hình ảnh máy tính về quỹ đạo pha (hình 23). Hình ảnh thật thú vị. Vùng có biên độ nhỏ là dao động trong quá trình tắt trường adnabatic. Tại một số thời điểm, góc lệch trở nên lớn $90^\circ$ và lưỡng cực bước vào pha quay. Bất biến adnabatic bị vi phạm. Cường độ của trường bằng 0, bắt đầu tăng (vectơ trường thay đổi hướng) và lưỡng cực trở về chế độ dao động. Trong trường hợp này, điểm cân bằng của các dao động mới dịch chuyển sang một góc $\pi$.

Trong ví dụ mô phỏng này, biên độ dao động ở chế độ chuyển động thứ hai tăng so với chế độ dao động thứ nhất. Nhưng sự tương ứng của biên độ có thể khác nhau (bao gồm cả biên độ không thể thay đổi), vì quá trình thay đổi pha của vùng chuyển động phụ thuộc vào sự đồng bộ của mômen thay đổi hướng của trường và pha của dao động lưỡng cực. Rõ ràng là sự thay đổi tiếp theo về hướng của trường sẽ dẫn đến sự quay trở lại của dao động về vùng pha đầu tiên.

Bài 11. Ống Ehrenfest “Bí mật” (trong cách diễn đạt bài toán văn bản của tác giả được giữ nguyên)

Toika, không chịu tác dụng của lực, di chuyển tới lui trong một buồng lái đóng kín cả hai bên. Để ở giữa cabin

⟦folio 21⟧

---
running_head:
folio:
---

Hình 26
Mối quan hệ vi phân thu được có thể được viết dưới dạng vi phân tương đối (chúng ta chia cho năng lượng của hệ $E = \left(k - m\omega^2\right)\frac{x_0^2}{2}$ tại thời điểm có độ lệch cực đại, những thay đổi về giá trị $\Delta E$, $\Delta\omega$ được coi là vi phân):

$$\frac{dE}{E} = -\frac{1}{2}\frac{m x_0^2 \cdot 2}{\left(k - m\omega^2\right) x_0^2}\omega d\omega = \frac{1}{2}\frac{-2m\omega d\omega}{\left(k - m\omega^2\right)}.$$

Sau khi tích hợp, chúng tôi thu được bất biến:

$$\ln E = \ln \sqrt{k - m\omega^2} + \ln C \rightarrow \frac{E}{\sqrt{k - m\omega^2}} = \text{const.}$$

Để xác định sự thay đổi các tham số rung, chúng tôi đánh đồng các bất biến của trạng thái ban đầu và trạng thái cuối cùng:

$$k \frac{x_0^2}{2\sqrt{k}} = \left(k - \omega m^2\right)\frac{x^2}{2\sqrt{k - m\omega^2}}$$

từ đó ta thu được sự phụ thuộc của biên độ dao động vào tốc độ quay:

$$\left(\frac{x}{x_0}\right)^4 = \frac{1}{1 - \left(\frac{\omega}{\Omega}\right)^2}, \quad x = x_0 \frac{1}{1 - \left(\frac{\omega}{\Omega}\right)^2}^{1/4},$$

trong đó $\Omega = \sqrt{\frac{k}{m}}$ là tần số tự nhiên của dao động ma trận khi không có chuyển động quay.

Chúng ta hãy lưu ý tính tất yếu của một “sự phá vỡ” các dao động khi vận tốc góc quay của hệ tiến tới tần số dao động tự nhiên của ma trận.

Thật thú vị khi nhìn vào quỹ đạo pha của các dao động (hình 26). Biểu đồ cho thấy việc thực hiện quỹ đạo pha trên máy tính khi tốc độ quay thay đổi. Để rõ ràng, gia tốc góc được chọn không nhỏ lắm. Hệ thống sụp đổ (quả bóng chạy đi đến vô cùng) trong khoảng 10 dao động. Trên biểu đồ, $X$ và $V$ lần lượt là tọa độ và tốc độ của điểm cân bằng, điểm này sẽ thay đổi khi tốc độ quay thay đổi.

***

Tóm lại – bài toán dành cho những người tò mò và có tội:

Một mạch dao động lý tưởng đang ở chế độ dao động. Tại một số thời điểm, các bản của tụ điện phẳng bắt đầu giãn nở rất chậm (advabatic) cho đến khi tần số dao động thay đổi theo hệ số n. Năng lượng của mạch sẽ thay đổi bao nhiêu lần (và theo hướng nào)?

Lưu ý rằng Einstein sẽ trả lời câu hỏi này ngay lập tức mà không cần đến sự nhắc nhở của Paul Ehrenfest.

⟦folio 23⟧

---
running_head:
folio:
---

Chứng minh rằng nếu bạn thực hiện tất cả $pq$ lần lật có thể xảy ra theo thứ tự ngẫu nhiên thì tất cả các số từ 1 đến $p$ đều ở vị trí $p$ đầu tiên và tất cả các số từ $p+1$ đến $n-$ ở vị trí $q$ cuối cùng.
6) Hãy để $n=2025$. Các ô đang thực hiện lật phải liền kề nhau.
Trình tự các lần lật sao cho đối với bất kỳ sự sắp xếp ban đầu nào, việc áp dụng trình tự các lần lật này vào nó sẽ dẫn đến các số được sắp xếp từ trái sang phải theo thứ tự tăng dần. Số lần lật tối đa có thể có trong chuỗi này là bao nhiêu?
c) Đặt $n=2025$. Các ô thực hiện thao tác lật có thể là hai ô bất kỳ của dải.
Chứng minh rằng tồn tại một chuỗi gồm 66 lần lật sao cho với cách sắp xếp ban đầu bất kỳ, áp dụng chuỗi lần tung này vào nó sẽ dẫn đến các số được sắp xếp từ trái sang phải theo thứ tự tăng dần.
D. Fomin

F2869. Hai quả bóng đồng thời nhận vận tốc bằng nhau, tạo các góc bằng nhau với đường chân trời và tâm của chúng chuyển động trong cùng một mặt phẳng thẳng đứng. Tại điểm cao nhất của quỹ đạo, các quả bóng trở nên phẳng. Chúng ta có thể giả sử rằng tác động là hoàn toàn đàn hồi. Tỷ số khối lượng của các quả bóng là bao nhiêu nếu sau va chạm, một trong số chúng rơi đúng vào vị trí va chạm? Ảnh hưởng của phơi nhiễm.

F2870. Trong bánh lồng bên dưới trục, một bệ nằm ngang nhẹ (hình 2) được cố định vào một phần ba bán kính $R$ của bánh xe. Một con khỉ thông minh được đặt ở rìa của trang web. Khối lượng của bánh xe $M$ phân bố đều dọc theo chu vi, khối lượng của khỉ là $m$, các thành bên của chuồng không có trọng lượng và chắc chắn. Con khỉ phải di chuyển quanh khu vực đó như thế nào để chiếc lồng không bị xoay?

F2871. Từ sáu hình vuông phẳng và mỏng giống hệt nhau có chiều dài cạnh $a$, một khối lập phương đã được lắp ráp trong không gian cách xa tất cả các vật thể khác. Tất cả các mặt của khối lập phương dọc theo các bề mặt bên ngoài đều được tích điện đều với mật độ bề mặt $\sigma$. Ở mỗi đỉnh của hình lập phương có ba mặt và để kết nối chúng, người ta sử dụng các sợi ngắn để nối ba góc của ba mặt tạo thành đỉnh này. Ở mỗi góc của mỗi mặt có một lỗ nhỏ để luồn chỉ qua đó. Không có ma sát giữa các bức tường và các sợi. Các cạnh của khối lập phương không chạm vào nhau nhưng các khoảng trống rất nhỏ. Hóa ra mỗi mặt được kết nối với các cạnh lân cận bằng bốn sợi ngắn ở mỗi góc của mặt. Tại mỗi đỉnh của hình lập phương, một sợi dây căng sẽ tạo thành một hình tam giác đều (hình 3). Giả sử cả 8 sợi dây đều bị căng như nhau, hãy xác định độ lớn lực căng của sợi dây. Nếu một trong bốn sợi dây giữ một mặt rơi xuống thì lực căng của sợi dây còn lại thay đổi như thế nào? Bạn có thể thoát khỏi trọng lực.

F2872. Hai tấm kính phẳng (chỉ số lấp đầy trước $n=1,5$) được đặt trong không khí song song với nhau và khoảng cách giữa các bề mặt gương gần nhất của chúng là $d=0,3$ µm. Hệ số phản xạ của những chiếc gương này là 99%, tức là 1% ánh sáng tới nó đi qua gương. Qua hai tấm kính này, Vasya nhìn vào bóng đèn sợi đốt. Anh ta nhìn thấy bóng đèn màu gì? Màu sắc (bước sóng truyền qua thiết bị này) phụ thuộc như thế nào vào góc giữa đường vuông góc với gương và hướng từ bóng đèn đến mắt?
