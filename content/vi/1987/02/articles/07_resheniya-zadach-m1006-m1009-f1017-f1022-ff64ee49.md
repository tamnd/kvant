---
id: 1987-2-resheniya-zadach-m1006-m1009-f1017-f1022-ff64ee49
issue: kvant_1987_2
year: 1987
number: "2"
title: Lời giải bài toán M1006—M1009; F1017—F1022
rubric: zadachnik-kvanta
rubric_sub: Задачник «Кванта»
page_first: 26
page_last: 37
page_labels: 24, 25, 26, 27, 28, 29, 30, 31, 33, 35
tag: 2C2D
lang: vi
source: kvant_digital
extraction: vision
content_sha256: e64367bbf0a73fe9ca0920c8f421814a70d2ca516c8d8ca6ddc25e2e55099fd6
prompt_sha256: draft-1
translated_from: content/ru/1987/02/articles/07_resheniya-zadach-m1006-m1009-f1017-f1022-ff64ee49.md
source_content_sha256: d84d6d0274d3c8dc7b60a98ae2d81791756837c6d1889349728ee54cd52e07cb
translation_model: draft
translation_run: vi-draft-2026-10-31
translation_quality: draft
---

⟦folio 24⟧

M1006. Hai đường thẳng đi qua hai đỉnh của một tam giác, chia tam giác đó thành ba tam giác và một tứ giác.
a) Diện tích của tất cả có thể là hình tứ giác không?
b) Ba phần nào sau đây có thể có diện tích bằng nhau?
Diện tích adb của tứ giác bằng bao nhiêu lần?

Lời giải bài toán
M1006—M1009; F1017—F1022

Trong lời giải giá trị gần như có giá trị tiếp theo sẽ được sử dụng nhiều lần
Bổ đề. Tỷ lệ trong đó một đường thẳng đi qua đỉnh của một tam giác chia diện tích adb của nó bằng tỷ lệ mà nó chia đáy của nó (xem hình 1).

a) Đáp số: họ không thể. Ngay cả khi chỉ có ba hình tam giác của phân vùng có kích thước bằng nhau (chúng ta không cần giả định về kích thước diện tích của tứ giác), thì theo bổ đề, các đoạn phân chia của tam giác đã cho phải chia nhau thành một nửa (hình 2), tức là chúng sẽ là các đường chéo của các đường chéo song song. Nhưng điều này là không thể, vì hai cạnh đối diện của “hình bình hành” này nằm trên các đường thẳng giao nhau - các cạnh của tam giác này.

b) Đáp số: các diện tích bằng nhau có thể là một hình tứ giác và hai hình tam giác bất kỳ của vách ngăn; tỷ lệ diện tích của phần thứ 4 với diện tích của mỗi phần trong số ba phần bằng nhau có thể bằng 3 hoặc $\sqrt{5}-2$.

Chúng ta hãy giới thiệu ký hiệu như trong hình 3. Từ lời giải bài toán a) rõ ràng một phần bằng nhau là tứ giác CLPK, phần còn lại là một trong các tam giác APL và BPK; ta sẽ giả sử đây là tam giác APL (trường hợp tam giác BPK được xét theo cách tương tự). Phần thứ ba là tam giác BPK hoặc APB; hai trường hợp này phải được xem xét riêng biệt.

⟦folio 25⟧

Ta biểu thị diện tích của ba phần bằng nhau là $s$ ($s=S_{CLPK}=S_{APL}$), diện tích của phần thứ 4 là $s_1$. Để tìm mối quan hệ cần thiết $s_1/s$, chúng ta biểu diễn theo hai cách các mối quan hệ trong đó các điểm $L$ và $K$ chia các cạnh $AC$ và $BC$, thông qua diện tích sử dụng bổ đề:

$$\frac{CL}{LA} = \frac{S_{CLB}}{S_{LAB}} = \frac{S_{CLP}}{S_{LAP}},$$

$$\frac{CK}{KB} = \frac{S_{CKA}}{S_{KBA}} = \frac{S_{CKP}}{S_{KBP}},$$

(*)

và các khu vực nước ngọt đến trải qua $s$, $s_1$ và $x=S_{CPL}$.

Trong trường hợp đầu tiên (hình 3, a) chúng ta có:

$$\frac{2s}{s+s_1} = \frac{x}{s}, \frac{2s}{s+s_1} = \frac{s-x}{s}.$$

Từ đây dễ dàng tìm được $x=s/2$, $s_1/s=3$.

Trong trường hợp thứ hai (hình 3, b) hệ thống sẽ được viết như sau:

$$\frac{s+s_1}{2s} = \frac{x}{s}, \frac{2s}{s+s_1} = \frac{s-x}{s}.$$

Phương trình đầu tiên cho kết quả $x=(s+s_1)/2$; Thay biểu thức này vào phương trình thứ hai, chúng ta thấy rằng mối quan hệ $s_1/s$ thỏa mãn phương trình bậc hai $(s_1/s)^2+4(s_1/s)-1=0$, tức là $s_1/s=\sqrt{5}-2$.

Vẫn còn phải kiểm tra xem liệu chúng ta có chia các cạnh của tam giác $ABC$ theo tỷ lệ hay không

$$CL : LA=CK : KB=2s : (s+s_1)=1 : 2$$

trong trường hợp thứ nhất và

$$CL : LA=BK : KC=(s+s_1):2s=(\sqrt{5}-1)/2$$

trong trường hợp thứ 2, khi đó ba phần tương ứng của phân vùng sẽ thực sự có kích thước bằng nhau. Sử dụng các đẳng thức (*), điều này khá dễ thực hiện trong trường hợp thứ nhất và hơi khó thực hiện hơn trong trường hợp thứ hai. Đối với trường hợp thứ 2, chúng tôi sẽ đưa ra một lý do khác, giải thích lý do tại sao số $\alpha=(\sqrt{5}-1)/2$ lại xuất hiện trong bài toán của chúng tôi. (Số $\tau=\frac{1}{\alpha}=\frac{\sqrt{5}+1}{2}$ là ý nghĩa của “vàng lời giải”.) Lưu ý rằng tuyên bố của chúng tôi, như chúng tôi nói, affine, tức là nó chỉ chứa các khái niệm và đại lượng hình học được bảo toàn trong quá trình chiếu song song: một đường thẳng, tỷ số độ dài các đoạn của một đường thẳng, diện tích bằng nhau, v.v. (Ngược lại, các khái niệm như giá trị góc, tỷ lệ độ dài các cạnh của một tam giác hoặc các cung bic không được bảo toàn trong quá trình chiếu - và không được đưa vào tuyên bố của chúng tôi.) Và vì bất kỳ tam giác nào cũng có thể được chuyển thành tam giác có hình dạng nhất định với sự trợ giúp của một số phép chiếu song song (nghĩ tại sao!), nên chỉ cần kiểm tra tuyên bố của chúng tôi để tìm các tam giác thuộc một, loại thuận tiện nhất. Để là một tam giác “tốt” như vậy, chúng ta lấy tam giác $ABC$, được tạo bởi hai đường chéo và các cạnh của một hình ngũ giác đều (hình 4). Không khó để chứng minh rằng tỉ số giữa các cạnh của một hình ngũ giác đều và đường chéo của nó là $\alpha$. Từ đây rõ ràng là vào hình 4

$$CL : LA=BK : KC=BD : AC=\alpha;$$

và đồng thời $S_{APB}=S_{APL}=S_{CKPL}$, vì rất rõ ràng rằng $BP=PL$, và tam giác $APL$ đơn giản là tương đương với tứ giác $CKPL$.

G. A. Galperin,
A. P. Savin

⟦folio 26⟧

M1007. Chứng minh rằng các tam giác có độ dài các cạnh a, b, c và a₁, b₁, c₁ đồng dạng khi và chỉ khi
$$\sqrt{a a_1} + \sqrt{b b_1} + \sqrt{c c_1} = \sqrt{(a_1 + b_1 + c_1)(a + b + c)}.$$

Sau khi bình phương cả hai vế của đẳng thức được chứng minh và một số phép biến đổi, nó được rút gọn về dạng
$$(\sqrt{a b_1} - \sqrt{a_1 b})^2 + (\sqrt{c a_1} - \sqrt{c_1 a})^2 + (\sqrt{b c_1} - \sqrt{b_1 c})^2 = 0,$$
và do đó, nó tương đương với các đẳng thức $a/a_1 = b/b_1 = c/c_1$, tức là tương tự như các tam giác.

Sau đó, có thể thu được một bằng chứng khác rằng cạnh trái bằng tích vô hướng của các vectơ có tọa độ $(\sqrt{a}, \sqrt{b}, \sqrt{c})$ và $(\sqrt{a_1}, \sqrt{b_1}, \sqrt{c_1})$ và không thể lớn hơn cạnh phải, bằng tích độ dài của các vectơ này; sự bằng nhau chỉ có thể xảy ra khi góc giữa các vectơ bằng 0, tức là chúng tỉ lệ với nhau.

Về cơ bản, trong lập luận thứ hai, chúng ta sử dụng cái gọi là bất đẳng thức Cauchy-Bunyakovsky:
$$x_1 y_1 + x_2 y_2 + \dots + x_n y_n \leq \sqrt{(x_1^2 + x_2^2 + \dots + x_n^2)(y_1^2 + y_2^2 + \dots + y_n^2)},$$
chỉ trở thành đẳng thức khi tập hợp số $(x_1, \dots, x_n)$ và $(y_1, \dots, y_n)$ tỷ lệ thuận với nhau (chúng ta có $n=3$, $(x_1, x_2, x_3) = (\sqrt{a}, \sqrt{b}, \sqrt{c}), (y_1, y_2, y_3) = (\sqrt{a_1}, \sqrt{b_1}, \sqrt{c_1})$).

V. P. Chuchin, V. N. Dubrovsky

M1008. Cầu thang gồm có 2n+1 bậc. Trên các bậc thang pinnix có một hòn đá. Cả hai cũng thay phiên nhau đập đá. Người đầu tiên có thể di chuyển bất kỳ hòn đá nào lên bậc tự do đầu tiên, và người thứ hai có thể di chuyển hòn đá xuống một bậc nếu nó tự do. Mục tiêu đầu tiên là đặt hòn đá lên bậc trên cùng. cái thứ hai có thể phù hợp với anh ta?

Đáp số: có thể.

Để tránh nhầm lẫn, chúng ta sẽ viết số của các ký tự bài toán (“tên” của chúng) bằng chữ in hoa. Quy tắc hành động của Người thứ hai là thế này: anh ta luôn đặt một hòn đá trên bậc thang đã bị bỏ trống sau nước đi của Người thứ nhất (điều này luôn có thể thực hiện được, vì hòn đá ở bước tiếp theo hoặc nằm trước nước đi của Người thứ nhất).

Hình 1. Hình 2.

Người đầu tiên - và vẫn ở đó sau lần di chuyển này, hoặc kết thúc ở đó do động thái của Người đầu tiên). Nếu Phần thứ hai tuân theo quy tắc này, thì sau bất kỳ bước di chuyển nào của Phần thứ nhất và đáp số của Phần thứ hai, sẽ không có gì thay đổi (hình 1), hoặc trên một phần nào đó của thang, tất cả các bậc trong đó ngoại trừ bậc trên cùng đều bị chiếm, bước thứ hai sẽ bị bỏ trống và một hòn đá được đặt lên trên (hình 2). Rõ ràng là trong trường hợp này, bước dưới luôn bị chiếm giữ và không thể tạo thành nhóm gồm hai bước điểm liên tiếp trở lên (tất nhiên là không tính các bước phía trên viên đá phía trên; ngay từ đầu các bước tự do nằm bên dưới viên đá (thứ n) phía trên, trước bất kỳ bước di chuyển nào của Bước đầu tiên không quá n - 1, tức là hai bước trên sẽ trống và Bước đầu tiên không thể chiếm bước trên.

S. L. Eliseev, N. N. Konstantinov

M1009. Đường phân giác của hình bình hành ABCD cắt các đường thẳng BC và

Chúng ta hãy ký hiệu tâm của đường tròn SKL bằng O; chỉ cần chúng ta chứng minh rằng $\angle BOD = \angle BCD$ (xem hình) là đủ. Trước tiên chúng ta hãy lưu ý rằng các đoạn AB và BK, cũng như LC

⟦folio 27⟧

CD lần lượt tại các điểm K và L. Chứng minh tâm đường tròn đi qua các điểm C, K, L nằm trên đường tròn đi qua các điểm B, C, D.

F1017. Mạng điện thoại lớn nhất thế giới có một tấm gương có đường kính D = 6 m làm vật thể. Sẽ mất bao lâu, khi so sánh các bức ảnh được chụp trên chiếc điện thoại này, để nhận thấy sự quay lẫn nhau của Thiên hà của chúng ta và tinh vân Tiên Nữ xung quanh một khối tâm chung? Khoảng cách tới Andromeda R=1,42·10¹¹ R₀, trong đó R₀ là bán kính quỹ đạo Trái đất. Khối lượng của Thiên hà và Tiên nữ lần lượt bằng nhau, M₇=2,5·10¹¹ M₀, M₄=3,6·10¹¹ M₀, trong đó M₀ là khối lượng của Mặt trời. Hiệu suất quang được thực hiện trong ánh sáng khả kiến ​​ở bước sóng λ=5·10⁻⁷ m.

F1018. Con thuyền đang cập bờ một hồ lớn (bờ biển thẳng tắp) bỗng bị lỏng dây, gió thổi thổi nó với vận tốc không đổi v₀=2,5 km/h, nghiêng một góc α=15° so với thân cây bạch dương. Liệu bạn có thể đuổi kịp thuyền nếu tốc độ của bạn và SK bằng nhau, vì trong tam giác ABK các góc trên cạnh AK bằng nhau (∠BAK=∠KAD=∠AKB) và đường thẳng LC song song với AB. Điều này một phần hàm ý sự bằng nhau của các tam giác OKC và OCL (OK=OC=OL, KC=CL). Hãy quay mặt phẳng quanh điểm O sao cho tam giác OKC trùng với tam giác OCL. Khi đó dầm KC sẽ thẳng hàng với cung CL, nên góc giữa các dầm này, tức là ∠BCD, bằng góc quay. Đồng thời, điểm B trong quá trình quay này sẽ di chuyển đến D, vì KB=AB=CD nên góc BOD cũng bằng góc quay; Như vậy chứng minh được sự bằng nhau của các góc BOD và BCD.

Hình ở lề minh họa trường hợp AB>BC và góc BAD là nhọn, tuy nhiên, lý luận của chúng tôi có thể áp dụng trong tất cả các trường hợp khác mà không có bất kỳ thay đổi nào.

Khoảng cách góc tối thiểu giữa hai vật mà tại đó chúng có thể được quan sát riêng biệt được xác định bằng nhiễu xạ và xấp xỉ bằng λ/D. Để nhận thấy Andromeda đã thay đổi vị trí, nó phải di chuyển chính xác theo góc này:

$$\varphi_0 \approx \frac{\lambda}{D} = \frac{5 \cdot 10^{-7}}{6} \text{ рад} \approx 8 \cdot 10^{-8} \text{ рад.}$$

Nếu chu kỳ quay của Thiên hà và Andromeda quanh khối tâm là T thì chuyển động quay theo góc φ₀ xảy ra trong khoảng thời gian:

$$\tau = \frac{T}{2\pi} \varphi_0.$$

Chu kỳ T có thể được tìm thấy từ định luật Kepler III tổng quát (trong sách giáo khoa thiên văn học ở trường, nó được gọi là tinh chỉnh):

$$\left(\frac{T}{T_2}\right)^2 \left(\frac{M_1+m_1}{M_2+m_2}\right) = \left(\frac{R_1}{R_2}\right)^3.$$

Viết nó cho hệ Trái đất-Mặt trời và Thiên hà-Andromeda và bỏ qua khối lượng của Trái đất, chúng ta thu được:

$$\left(\frac{T}{T_0}\right)^2 \left(\frac{M_\Gamma+M_A}{M_0}\right) = \left(\frac{R}{R_0}\right)^3,$$

trong đó T₀=1 năm (trên trái đất).

Từ các phương trình (1), (2) và (3) chúng ta tìm thấy:

$$\tau = \frac{\lambda}{2\pi D} T_0 \left(\frac{R}{R_0}\right)^{3/2} \left(\frac{M_0}{M_\Gamma+M_A}\right)^{1/2} \approx 10^3 \text{ лет.}$$

V.E. Belonuchkin

Giả sử rằng tại thời điểm phát hiện vật thể catarrh, bạn đang ở trên bờ tại điểm O (xem hình) và catarrh, sau khi rời khỏi điểm E, di chuyển dọc theo đường thẳng EF, tạo một góc α=15° với cây bạch dương tuyến tính, với tốc độ v₀=2,5 km/h. Để trả lời câu hỏi bài toán, chúng ta hãy xây dựng ranh giới của vùng có thể tiếp cận — vùng mà sau thời gian t sau khi bắt đầu chuyển động, bạn có thể tìm thấy chính mình bằng cách “kết hợp” đi bộ và bơi lội. Ranh giới này (xem hình) là cung AB của đường tròn có bán kính |OA|=

⟦folio 28⟧

trên bờ $v_1=4$ km/h, dưới nước - $v_2=2$ km/h? Tính tổng quát này có thể xảy ra ở tốc độ nào của catarrh?

$$= |OB|=v_2t$$ và hai đoạn tiếp tuyến với đường tròn này - CA và DB, và $|OC|=|OD|=v_1t$ (việc xây dựng ranh giới này đã được mô tả chi tiết trong bài viết “Về quỹ đạo chuyển động tối ưu” ở «Kvant» số 6 năm 1982, trang 30). Sau thời gian $\Delta t$, ranh giới của vùng tiếp cận sẽ có vị trí mới $C'A'B'D'$ và $|CC'|=|DD'|=v_1 \cdot \Delta t$, $|AA'|=|BB'|=v_2 \cdot \Delta t$. Dễ hiểu là nếu hình chiếu tốc độ của catarrh lên hướng OA (theo hướng này phần phẳng của ranh giới vùng tiếp cận lan truyền với tốc độ $v_2$) lớn hơn tốc độ $v_2$ thì bạn sẽ không bao giờ đồng ý. Giá trị tối thiểu của tốc độ của catarrh, tại đó không thể bắt kịp catarrh nữa, được xác định từ điều kiện (xem hìnhok)

$$v_{\min}\cos \beta=v_2,$$ ở đâu $\beta=\varphi-a$.

Vì $\varphi=\arcsin \frac{v_2}{v_1}=\arcsin \frac{1}{2}=30^\circ$, $\cos \beta=\cos 45^\circ=\frac{1}{\sqrt{2}}$ và

$$v_{\min}=v_2\sqrt{2}\approx 2.8$$ km/giờ.

Khi thuyền đang di chuyển với tốc độ $v_0=2.5$ km/h ($v_0<v_{\min}$), hình chiếu tốc độ của thuyền theo hướng OA nhỏ hơn $v_2$, do đó, dù bạn ở trên bờ bao lâu, bạn cũng có thể đuổi kịp thuyền bằng chiến lược di chuyển dày dạn (ranh giới khu vực tiếp cận chắc chắn sẽ đuổi kịp thuyền).

S. S. Krogov

F1019. Một bình hình trụ nhỏ có diện tích đáy S được hạ xuống một bình lớn chứa chất lỏng có khối lượng riêng $\rho_1$, trong đó còn lại một ống có chiều dài l (hình1); Các bức tường của tàu được gắn chặt với nhau. Một chất lỏng màu có mật độ $\rho_2$ ($\rho_2>\rho_1$) được đổ vào một bình nhỏ có độ cao H sao cho mực chất lỏng trong bình lớn và nhỏ bằng nhau. Tại một thời điểm nào đó, lỗ trên ống chất lỏng có mật độ $\rho_2$ sẽ chảy vào một bình lớn hơn cho đến khi áp suất tại điểm A (hình2) từ chất lỏng có mật độ $\rho_1$ trở nên bằng áp suất của chất lỏng có mật độ $\rho_2$. Từ điều kiện này dễ dàng tìm được khối lượng chất lỏng lần đầu tiên chảy ra khỏi bình nhỏ.

Để làm điều này, chúng ta viết ra các điều kiện cân bằng (xem hình2):

$$\rho_1g(H+l)=\rho_2g(h+l)=\rho_2g(H-\Delta h+l),$$

(1)

trong đó $\Delta h=(H-h)$ là sự giảm mực chất lỏng trong một bình nhỏ. Từ đây

$$h=\frac{\rho_1}{\rho_2}H-\frac{\rho_2-\rho_1}{\rho_2}l,$$

Và

$$\Delta m=\rho_2 \cdot \Delta h \cdot s=(\rho_2-\rho_1)(H+l)s$$

(s là diện tích đáy bình nhỏ).

Để dự đoán thêm lời giải, chúng tôi sẽ đưa ra một số đề xuất.

1. Diện tích mặt cắt ngang của bình lớn hiện nay lớn nên nếu chất lỏng chảy ra khỏi bình nhỏ hoặc chảy vào đó thì mức chất lỏng trong bình lớn không thay đổi.

2. Động lực học của ống và chiều dài hiện tại của nó nhỏ nên thể tích của ống này so với thể tích của bình có thể bỏ qua, tức là khi chất lỏng từ

⟦folio 29⟧

ống rò rỉ ra ngoài, mức chất lỏng trong nước sốt nhỏ không thay đổi.

Thoạt nhìn, có vẻ như sau khi áp suất tại điểm $A$ được cân bằng, quá trình sẽ dừng lại; nhưng điều đó không đúng. Tình trạng này là không bền vững. Giả sử rằng một chất lỏng có mật độ $\rho_1$ chảy vào ống đến một độ cao nhỏ $\Delta x$ (hình 3); thì áp suất tại điểm $A'$ ở phía chất lỏng có mật độ $\rho_1$ sẽ lớn hơn áp suất tại điểm $A'$ ở phía chất lỏng có mật độ $\rho_2$.

Thật vậy, áp suất tại điểm $A'$ ở phía chất lỏng có mật độ $\rho_1$ sẽ bằng $p_1 = \rho_1 g(H + l - \Delta x)$, và ở phía chất lỏng có mật độ $\rho_2 - p_2 = \rho_2 g(h + l - \Delta x)$; sự khác biệt giữa những áp lực này

$$\Delta p = p_1 - p_2 = (\rho_2 - \rho_1) g \cdot \Delta x$$

sẽ di chuyển chất lỏng lên trên, vì $\rho_1 g(H + l) = \rho_2 g(h + l)$ là điều kiện cân bằng (xem (1)). Chất lỏng có mật độ $\rho_1$ sẽ ở dạng nước sốt nhỏ cho đến khi áp suất trên và dưới tại điểm $B$ (xem hình 3) bằng nhau. Một chất lỏng có mật độ $\rho_1$ sẽ nổi lên trên chất lỏng có mật độ $\rho_2$ (theo điều kiện bài toán chúng không trộn lẫn với nhau).

Hãy viết điều kiện cân bằng tại điểm $B$:

$$\rho_1 g H = \rho_1 g \Delta h_1 + \rho_2 g h,$$

trong đó $\Delta h_1$ là chiều cao của chất lỏng có mật độ $\rho_1$, có trong một loại nước sốt nhỏ.

Từ (1) và (2) chúng ta tìm thấy: $\Delta h_1 = \frac{\rho_2 - \rho_1}{\rho_1} l$, và

$$\Delta m_1 = (\rho_2 - \rho_1) l s.$$

Bây giờ nguyên nhân của dòng chất lỏng từ nước sốt này sang nước sốt khác đã trở nên rõ ràng, chúng ta hãy viết các phương trình cân bằng trong trường hợp tổng quát hơn. Giả sử rằng trạng thái cân bằng tại điểm $B$ xảy ra tại thời điểm

$$\rho_1 g H = \rho_1 g h_1 + \rho_2 g h_2,$$

trong đó $h_1$ là chiều cao của chất lỏng có mật độ $\rho_1$ và $h_2$ là chiều cao của chất lỏng có mật độ $\rho_2$ trong nước sốt nhỏ (hình 4). Chúng ta đã biết rằng vị trí cân bằng không ổn định và chất lỏng sẽ chảy ra khỏi nước sốt nhỏ cho đến khi áp suất tại điểm $A$ cân bằng, điều đó có nghĩa là

$$\rho_1 g(H + l) = \rho_1 g h_1 + \rho_2 g(h'_2 + l).$$

Từ (3) và (4) ta thu được: $\Delta h_2 = h_2 - h'_2 = \frac{\rho_2 - \rho_1}{\rho_2} l$, và

$$\Delta m_2 = (\rho_2 - \rho_1) l s.$$

Khi áp suất tại điểm $A$ bằng nhau, vị trí không ổn định và chất lỏng có mật độ $\rho_1$ sẽ chảy ra thành nước sốt nhỏ cho đến khi áp suất tại điểm $B$ cân bằng, nghĩa là

$$\rho_1 g H = \rho_1 g h'_1 + \rho_2 g h'_2.$$

Từ (4) và (5) ta thu được: $\Delta h_3 = h'_1 - h_1 = \frac{\rho_2 - \rho_1}{\rho_1} l$, và

$$\Delta m_3 = (\rho_2 - \rho_1) l s = \Delta m_2.$$

Điều này có nghĩa là mỗi lần cùng một lượng chất lỏng sẽ chảy ra khỏi nước sốt nhỏ và thấm vào văn bản.

$$\Delta m = (\rho_2 - \rho_1) l s.$$

Lưu ý rằng lượng chất lỏng chảy ra từ nước sốt sẽ thay đổi; Tại sao lại như vậy, hãy tự suy nghĩ.

V. E. Skorovarov

⟦folio 30⟧

F1020. Một piston chuyển động chia hình trụ thành hai phần bằng nhau có thể tích $V_0=10^{-3}$ m³. Một phần chứa không khí khô, phần còn lại chứa hơi nước và $m=4$ g nước. Khi xi lanh nóng lên từ từ, piston bắt đầu chuyển động. Sau khi piston di chuyển được 1/4 chiều dài của xi lanh thì chuyển động dừng lại. Khối lượng hơi nước trong bình trước khi đun nóng là bao nhiêu? Khối lượng không khí trong bình và nhiệt độ ban đầu của nó là bao nhiêu? Ở nhiệt độ nào piston ngừng chuyển động? Sự phụ thuộc của áp suất hơi nước bão hòa vào nhiệt độ được cho trong bảng.

| $t, \text{°C}$ | $p_H \cdot 10^{-5}$, Bố |
| :--- | :--- |
| 100 | 1 |
| 120 | 2 |
| 133 | 3 |
| 152 | 5 |
| 180 | 10 |

F1021. Trong mạch hiển thị ở hình, $R=100$ Ohm, $C=10$ mF, $U_0=10$ V, điện trở trong của pin và điện trở của ampe là không đáng kể. Nhiệt độ định kỳ Klioch K không đáng kể. Nhiệt độ định kỳ Klioch K không đáng kể. Nhiệt độ định kỳ Klioch K không đáng kể. Nhiệt độ định kỳ Klioch K không đáng kể.

F1020. Một piston chuyển động chia hình trụ thành hai phần bằng nhau có thể tích $V_0=10^{-3}$ m³. Một phần chứa không khí khô, phần còn lại chứa hơi nước và $m=4$ g nước. Khi xi lanh nóng lên từ từ, piston bắt đầu chuyển động. Sau khi piston di chuyển được 1/4 chiều dài của xi lanh thì chuyển động dừng lại. Khối lượng hơi nước trong bình trước khi đun nóng là bao nhiêu? Khối lượng không khí trong bình và nhiệt độ ban đầu của nó là bao nhiêu? Ở nhiệt độ nào piston ngừng chuyển động? Sự phụ thuộc của áp suất hơi nước bão hòa vào nhiệt độ được cho trong bảng.

| $t, \text{°C}$ | $p_H \cdot 10^{-5}$, Bố |
| :--- | :--- |
| 100 | 1 |
| 120 | 2 |
| 133 | 3 |
| 152 | 5 |
| 180 | 10 |

Chuyển động của piston sẽ dừng lại khi toàn bộ nước đã bay hơi hết; trong trường hợp này, ở bên trái và bên phải của piston sẽ có các chất khí (không khí và hơi nước), trạng thái của chúng được mô tả bằng phương trình Mendeleev-Clapeyron. Dễ hiểu là trước đó, khi piston chuyển động, thể tích không khí giảm từ $V_0$ xuống $V_0/2$, và hơi nước luôn bão hòa.

Đặt nhiệt độ và áp suất ban đầu là $T_0$ và $p_0$, nhiệt độ cuối cùng - $T_1$ và $p_1$, và khối lượng hơi nước trước khi đun nóng $M$. Khi đó chúng ta có thể viết các phương trình sau: đối với không khí -

$$\frac{p_0V_0}{T_0} = \frac{p_1V_0}{2T_1};$$

cho hơi nước tại thời điểm ban đầu -

$$p_0V_0 = \frac{M}{\mu_\pi}RT_0, \quad p_0 = p_H(t_0),$$

ở cuối quá trình -

$$p_1\frac{3}{2}V_0 = \frac{M+m}{\mu_\pi}RT_1, \quad p_1 = p_H(t_1),$$

trong đó $\mu_\pi$ là khối lượng mol của hơi nước. Giải các phương trình (1) - (3) cùng nhau, ta tìm được khối lượng hơi nước trước khi đun nóng:

$$M = m/2 = 2\text{ г.}$$

Sử dụng bảng đã cho trong các điều kiện, chúng ta sẽ vẽ đồ thị sự phụ thuộc $p_H(t)$ của hơi nước (xem hình). Khi đó nhiệt độ $T_0$ được xác định từ điều kiện giao điểm của đồ thị này với đường $p = \frac{M}{\mu_\pi}\frac{R}{V_0}T$ và $T_1$ với đường $p = \frac{M+m}{\mu_\pi}\frac{2R}{3V_0}$. Sử dụng phương pháp đồ họa này lời giải, chúng tôi tìm thấy:

$$t_0 = 140 \text{ °C}, \quad t_1 = 170 \text{ °C},$$

$$p_0 \approx 3,8 \cdot 10^5 \text{ Па.}$$

Biết nhiệt độ $T_0=413$ K và các giá trị $p_0$, từ phương trình Mendeleev-Clapeyron cho nước ($\mu_B = 29 \text{ г/mоль}$), chúng ta tìm được khối lượng của nước $M_0$:

$$M_0 = \frac{p_0V_0\mu_B}{RT_0} \approx 3,2 \text{ г.}$$

A. I. Vuzdin

Khi đóng chìa khóa, các tụ điện được sạc gần như ngay lập tức (điện trở của ampe và điện trở trong của pin không đáng kể) đến điện áp $U_3 = \frac{U_0}{2}$, và khi đóng chìa khóa, chúng gần như phóng điện hoàn toàn. Hãy giải thích điều này.

Mỗi tụ điện được phóng điện qua điện trở $R$. Dòng phóng điện ở thời điểm đầu tiên -

$$I_0 = \frac{U_3}{R} = \frac{U_0}{2R}.$$

Nếu dòng điện này không thay đổi thì tụ điện sẽ phóng điện hoàn toàn trong thời gian

$$\tau = \frac{q}{I_0} = \frac{CU_3}{I_0} = RC.$$

Trong thực tế, dòng điện giảm khi tụ phóng điện và tụ phóng điện chậm hơn

⟦folio 31⟧

cô ấy; Nói một cách chính thức, nó không bao giờ phóng điện hoàn toàn. Chúng tôi không quan tâm đến mức phóng điện hoàn toàn tuyệt đối của nó, mà quan tâm đến mức mà tại đó nó chỉ đơn giản là $U \ll U_3$; đối với điều này, chỉ cần yêu cầu $T_{\text{pa3p}} \gg \tau$ là đủ. Trong trường hợp của chúng tôi $T_{\text{pa3p}} = \tau_2 = 20 \cdot 10^{-3} \text{ c} \gg \tau = 1 \cdot 10^{-3} \text{ c}$.

Hãy tính điện tích chạy qua ampe khi chìa khóa đóng:

$$q_1 = \frac{U_0}{2R} \tau_1 - C \frac{U_0}{2}$$

(điện áp trên điện trở là $\frac{U_0}{2}$, dòng điện của điện trở chạy qua ampe).

Khi mở, cả hai tụ điện đều được phóng điện qua ampe:

$$q_2 = 2 \frac{CU_0}{2}$$

Dòng điện trung bình

$$I_{\text{cp}} = \frac{q_1 + q_2}{\tau_1 + \tau_2} = \frac{-C \frac{U_0}{2} + \frac{U_0}{2R} \tau_1 + CU_0}{\tau_1 + \tau_2} = \frac{U_0}{2R} \frac{\tau_1 + RC}{\tau_1 + \tau_2} \approx 4,8 \cdot 10^{-3} \text{ A}$$

A. P. Zilberman

F1022. Hộp đen chứa một cuộn dây, một điện trở, một tụ điện và có ba cực. Trong quá trình nghiên cứu, ông đã thu được những kết quả sau.

Trong mạch hiển thị ở hình 1, ampe hiển thị $I_1 = 0,1$ A ở tần số dao động $v_1 = 1000 \text{ Гц}$; dòng điện qua ampe lệch pha với điện áp đầu vào là $\Delta \varphi_1 = \pi/6$. Khi tần số máy phát giảm đi 100 lần thì dòng điện tăng chưa đến 2 lần. Tần số máy phát được trả về giá trị trước đó và một vôn kế (hình 2) được kết nối với mạch cùng với ampe. Vôn kế

Có khá nhiều phương án khả thi (trong số ba phần tử nêu trong điều kiện chỉ định) - 24. Vì vậy, trước tiên bạn phải vẽ chúng và quyết định xem về nguyên tắc, phần tử nào trong số chúng có thể đáp ứng các điều kiện đã đặt ra. Để không bỏ sót mạch nào, bạn cần phân loại chúng một cách thông minh - ví dụ: trước tiên hãy vẽ tất cả các mạch trong đó chỉ có một điện trở được nối với điểm 2 (“lời hứa”), sau đó chỉ là tụ điện, sau đó chỉ là một cuộn dây. Chỉ có 12 mạch như vậy. Sau đó, chúng ta sẽ vẽ các mạch trong đó có chính xác hai phần tử được kết nối với chân này - có 6 mạch như vậy. Vẫn còn các mạch: không có phần tử nào được kết nối với dây chung - có 5 phần tử trong số đó và cả ba phần tử đều được kết nối với dây chung - chỉ có một mạch như vậy. (Ở đây chúng tôi không xem xét các sơ đồ trong đó điểm 1 hoặc 3 không được kết nối - lý do rõ ràng.)

Một phân tích khá đơn giản cho thấy rằng các điều kiện của nhiệm vụ chỉ có thể được thỏa mãn bởi mạch hiển thị ở hình 3. Trong mạch có ampe-ampe mắc song song với tụ điện (xem hình 1), bạn có thể “vứt bỏ” tụ điện - ampe là lý tưởng, nghĩa là không có dòng điện nào chạy qua tụ điện. hình 4 hiển thị sơ đồ “đơn giản hóa” như vậy (hình 4, a) và sơ đồ vectơ chỉ hướng (hình 4, b). Từ sơ đồ ta có:

$$\frac{X_L}{R} = tg \frac{\pi}{6} = \frac{1}{\sqrt{3}},$$

Ở đâu

$$X_L = \frac{1}{\sqrt{3}} R$$

$$I_1 \sqrt{R^2 + X_L^2} = I_1 \frac{2R}{\sqrt{3}} = U_0 \Rightarrow I_1 = \frac{\sqrt{3}}{2} \frac{U_0}{R}$$

Tại hình 5 có sơ đồ “hộp đen” có vôn kế nối (hình 5, a) và sơ đồ chiều (hình 5, b):

⟦folio 33⟧

Hình 1.

Nhân tiện, từ đây, theo sau, trong trường hợp “cực kỳ xui xẻo”, bạn sẽ không thể làm điều đó trong vòng chưa đầy 1002 giây: nếu sự kết hợp mong muốn của ba chữ số là số cuối cùng, thì các xác nhận có ba chữ số này sẽ được nhấn ở giây thứ 1000, 1001 và 1002.

Mục tiêu rất rõ ràng: sắp xếp tất cả các mã có ba chữ số sao cho mỗi mã tiếp theo bắt đầu bằng hai chữ số cuối của mã trước đó, nhưng liệu nó có đạt được không?

Đây là một tình huống tương tự mà nó không thể đạt được.

Biết rằng các chữ số của mã gồm ba chữ số là khác nhau và đây là các số 1, 2 và 3. Nói cách khác, bạn chỉ cần kiểm tra 6 mã: 123, 132, 213, 231, 312 và 321. Nếu kéo chúng thành một chuỗi thì việc chọn mã sẽ mất 8 giây. Nhưng bạn không thể kéo chúng thành một chuỗi! Chúng tạo thành hai chuỗi (chuỗi nào?), vì vậy việc chọn mã sẽ không mất 8 mà là 10 giây (kiểm tra!).

Một biểu đồ có hướng được chọn đặc biệt (viết tắt là oreraf) sẽ giúp chúng tôi giải quyết một câu hỏi có thể xảy ra và hạn chế việc xác minh tuần tự các mã. Đây là tên được đặt cho một tập hợp hữu hạn các điểm (gọi là đỉnh oreraph) nếu một số trong chúng được nối với nhau bằng các mũi tên (mũi tên chỉ hướng); cụ thể, nếu mũi tên oreraf không bị loại trừ thì đó là Euler và định lý đã được chứng minh.

Hình 2.

Có các mũi tên ròng nối đỉnh với chính nó.

Tổ chức $T_{10}$

Chúng ta hãy xây dựng một sơ đồ với sự trợ giúp của nó để giải quyết bài toán a). Hãy lấy 100 điểm. Hãy điền các tham số của chúng bằng các số: 00, 01, 02, ..., 98, 99. Từ điểm $ab$ đến điểm $dc$ chúng ta sẽ vẽ một mũi tên nếu $b=d$. Ví dụ $13\rightarrow 38$, $45\rightarrow 55$; cụ thể là bất kỳ điểm nào có số lượng hai kết nối kỹ thuật số giống hệt nhau với chính nó.

Hãy để chúng tôi biểu thị đồ thị được xây dựng $T_{10}$.

Trên mũi tên từ $ab$ đến $bc$ mã ba chữ số điển hình là $abc$: $13 \rightarrow 38$, $33 \rightarrow 333$. Bất kỳ mã ba chữ số nào cũng sẽ được viết đúng 1 lần: giả sử, 455 sẽ được viết trên mũi tên từ 45 đến 55. Do đó, $T_{10}$ chứa 10 đỉnh và 1000 mũi tên với tất cả các số có ba chữ số có thể có. Trong trường hợp này, 10 mũi tên đi ra từ mỗi đỉnh và 10 mũi tên đi vào mỗi đỉnh: mũi tên $ab0$, $ab1$, ..., $ab9$ đi ra từ $ab$, mũi tên $0ab, 1ab$, ..., $9ab$ nhập $ab$.

Theo các mũi tên, bạn có thể đi từ bất kỳ đỉnh nào $ab$ đến bất kỳ đỉnh nào $cd$:

$$ab \xrightarrow{abc} bc \xrightarrow{bcd} cd.$$

Các tổ chức có thuộc tính này sẽ được gọi là được kết nối.

Hãy nhớ: mục tiêu của chúng ta là kéo tất cả các mã có ba chữ số thành một chuỗi; mục tiêu sẽ đạt được nếu chúng ta đi vòng quanh $T_{10}$ dọc theo các mũi tên, đi qua từng mũi tên đúng 1 lần.

Sự tồn tại của một vật thể như vậy được đảm bảo bởi định lý chu trình Euler.

Chúng ta gọi một đồ thị ghép là *chính quy* nếu với mỗi đỉnh của nó $A$ số mũi tên rời khỏi $A$ bằng số mũi tên đi vào $A$; Chúng ta sẽ biểu thị con số này $p_A$.

Ví dụ: trong $T_{10}$ cho mỗi đỉnh $ab$

$$p_{ab}=10;$$

hình 1 hiển thị hai đồ thị thông thường được kết nối (hoặc, nếu bạn muốn, một đồ thị không kết nối thông thường), với $p_A=2$ cho một số đỉnh và $p_A=1$ cho các đỉnh khác.

Định lý. Trong bất kỳ đồ thị liên thông thông thường nào đều có một chu trình (một đường khép kín dọc theo các mũi tên) đi qua mỗi mũi tên đúng một lần (hình 2).

Chúng ta sẽ gọi những chu trình như vậy là Euler.

Chứng minh định lý chu trình Euler

Hãy lấy bất kỳ đỉnh nào $A$ và đặt từ nó dọc theo các mũi tên một cách tùy ý, “đốt cháy những nơi phía sau chúng ta” - xóa các mũi tên mà chúng ta đã đi theo. Vì mũi tên là một số hữu hạn nên đến một lúc nào đó chúng ta sẽ bị mắc kẹt - chúng ta sẽ đi vào ngõ cụt không có lối thoát. Chúng ta không thể bị kẹt ở đỉnh $B \neq A$, vì số lượng mũi tên đi ra từ $B$ giống nhau khi nhập $B$. Điều này có nghĩa là ngõ cụt là đỉnh ban đầu $A$.

Vì vậy, đường đi của chúng ta là chu trình $c$, bắt đầu và kết thúc tại $A$. Vì chúng tôi đã xóa ngay lập tức từng mũi tên mà chúng tôi đã theo dõi nên chu trình $c$ không đi qua bất kỳ mũi tên nào hai lần.

Nếu chu trình $c$ chứa tất cả các mũi tên của đồ thị thì đó là chu trình Euler và định lý được chứng minh.

Nếu không, thì trong số các đỉnh mà $c$ đi qua sẽ có một đỉnh $A_1$ mà từ đó mũi tên không bị xóa $s_1$ nhô ra (nếu không tìm thấy các đỉnh đó, đồ thị của chúng ta sẽ không bị ngắt kết nối, hình 3).

⟦folio 35⟧

Hình 7.

Từ định lý chu trình Euler suy ra:
tại bài toán c) thời gian $t_{\min} = 722$ s (thường là tại $n > 3$ thời gian $t_{\min} = n(n-1)(n-2) + 2$ s); với $n = 3$ do sự không nhất quán của $D_3$ mã pop mất thêm 2 giây: $t_{\min} = \text{не 8}, \text{а 10 с}.$

Như vậy, $t_{\min}$ trong các bài toán a), 6) và c) đã được tìm thấy. Hãy thử sử dụng phương pháp tương tự để tìm $t_{\min}$ nếu
1) có 10 nút và biết rằng ít nhất một trong các chữ số của mã ba chữ số là chín;
2) có 10 nút và biết rằng mã ba chữ số có đúng hai chữ số giống nhau;
3) $2 \leq k \leq n$, các nút $n$ và mã là $k$ chữ số;
4) Có 6 nút, trên các nút có các số 0, 1, ..., 5, tất cả các số của mã 3 chữ số đều khác nhau và mã chứa số 5.

Hãy chuyển sang thảo luận về câu hỏi thứ hai:

Làm thế nào để tìm lại mã bị quên trong thời gian ngắn nhất?

Từ phần trước, bạn có thể hành động như thế này.
1) Lấy một đồ thị thích hợp ($T_{10}, T_3$ hoặc $D_{10}$ lần lượt trong các bài toán a), 6) và c)).
2) Tìm chu trình Euler e trong đó.
3) Tự ý cố định mũi tên $S_1$, lấy các mũi tên đến trong chu kỳ e sau $S_1$:
$S_1, S_2, ..., S_N$,
$N = \begin{cases} 1000 \text{ в задаче a)}, \\ 27 \text{ в задаче 6)}, \\ 720 \text{ в задаче b)}. \end{cases}$
4) Viết lần lượt các số mũi tên có ba chữ số $S_1, S_2, ..., S_N$.
Vì số $S_{i+1}$ chỉ thêm một chữ số mới vào số $S_i$ nên bạn chỉ có thể chỉ ra số đó (chứ không phải toàn bộ số $S_{i+1}$); do đó, mục 4) có thể được thay thế bằng mục này:
4' Thêm vào số $S_1$ chữ số thứ ba của số $S_2$, sau đó là chữ số thứ ba của số $S_3$, v.v. - lên đến $S_N$; chuỗi kết quả là $\Pi$ gồm $(N+2)$ chữ số. Bằng cách nhấn các nút có các số này, mỗi nút một giây, trong $(N+2)$ giây (tức là trong $t_{\min}$ thời gian), chúng tôi sẽ xem qua tất cả các mã gồm ba chữ số yêu cầu xác minh và do đó, không quá $(N+2)$ giây, chúng tôi sẽ tìm thấy mã bị quên.

Ví dụ: chu trình $e$ trong sơ đồ $T_3$ với mũi tên đầu tiên 113 (hình 6) tương ứng với dãy $\Pi$ gồm 29 chữ số: 113 332 331 322 321 312 311 2 221 211 1.

Vì $e$ là một chu trình, nên cặp chữ số đầu tiên và cuối cùng trong chuỗi $\Pi$ giống nhau (đây là số đỉnh mà mũi tên $S_1$ đi ra và đi vào mũi tên $S_N$). Do đó, thay vì viết $N+2$ số $\Pi$ trên một dòng, bạn có thể viết $N$ số trong một vòng tròn (xem hình 9, trong đó $N=27$).

Trên hình 9 dọc theo vành bánh xe (chúng ta sẽ gọi là bánh xe $B$) có 9 đơn vị, 9 đôi và 9 rãnh theo thứ tự đặc biệt. Mục này chứa đầy đủ lời giải bài toán 6). Vẫn còn phải vẽ các bánh xe thay thế tương tự $A$ và $B$ cho bài toán a) và c).

Chúng có phải là sự thay thế giống nhau không? Điều này có nghĩa là gì?

Đối thoại về chiếc nhẫn $A, B$ và $B$
— Vậy bánh xe thay thế $B$ là gì?
- Dù bạn lấy số nào, nếu bạn đi từ đó theo chiều kim đồng hồ, đọc từng số một thì trong 29 giây bạn sẽ gặp tất cả các số có ba chữ số của các số 1, 2, 3.
- Đúng, đây là vật thay thế (và bánh xe $A$ và $B$ phải có đặc tính tương tự), nhưng đây không phải là thứ đã được thay thế!
- Bạn có thể đi ngược chiều kim đồng hồ với số bằng nhau!

- Có thể, nhưng tính chất này nối tiếp tính chất đầu tiên. Và cả hai đều đúng cho một bánh xe được xây dựng từ chu trình Euler bất kỳ $e$ trong $T_n$.
— Vậy chu kỳ $e$ trên hình 6 có đặc biệt không?
- Đúng! Nó được xây dựng không theo một công thức chung phù hợp với bất kỳ đồ thị kết nối thông thường nào, mà theo một thuật toán đặc biệt được sử dụng bởi $T_n$.
- Và cái này mang lại điều gì?
— Ở mức $n=3$ sự khác biệt không lớn. Và trong $T_{10}$ đã có hàng nghìn mũi tên và việc tìm kiếm $e$ trong $T_{10}$ theo công thức chung có thể quá dài và tốn nhiều công sức - ngay cả khi bạn sử dụng máy tính.
— Có thuật toán đặc biệt nào nhanh $e$ không?
- Vâng, tôi cam kết viết một nghìn con số lên bánh xe $A$ trong một nghìn giây! Tôi không cần máy tính, không cần điền những con số đã viết, tôi chỉ cần nhớ 3-4 chữ số cuối. Trình tự của tôi gần như đơn giản như chuỗi tự nhiên.
- Edorov! Chuỗi 720 số trên bánh xe $B$ cũng đơn giản phải không? Nó có thể được viết ra trong 720 giây?
- Đúng! Mặc dù không dễ để nghĩ ra trình tự đơn giản này...
...Ở đây chúng tôi sẽ dịch đoạn hội thoại này để không làm mất đi sự tiện lợi của người đọc khi giới thiệu việc thay thế số cho bánh xe $A$ và $B$, hoặc thậm chí trong trường hợp chung - đối với mã $k$ chữ số từ số $n$. (Có những gợi ý ẩn trong văn bản và trong hình ảnh tiết lộ bí quyết xây dựng và nhanh chóng viết ra chuỗi $\Pi$; nhưng có lẽ bạn sẽ không cần chúng và bạn sẽ đi theo con đường riêng của mình.) Và chúng tôi hy vọng, sau khi nhận được thư của bạn, sẽ quay lại vấn đề bài toán này trong một trong những số tiếp theo của tạp chí.

M. L. Gerver
