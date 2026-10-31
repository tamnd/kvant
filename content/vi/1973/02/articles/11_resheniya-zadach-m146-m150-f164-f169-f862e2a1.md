---
id: 1973-2-resheniya-zadach-m146-m150-f164-f169-f862e2a1
issue: kvant_1973_2
year: 1973
number: "2"
title: Lời giải bài toán M146—M150; F164—F169
rubric: zadachnik-kvanta
rubric_sub: Задачник «Кванта»
page_first: 49
page_last: 65
page_labels: 47, 48, 49, 50, 54, 55, 56, 59, 61, 62, 63
tag: X3IH
lang: vi
source: kvant_digital
extraction: vision
content_sha256: b904365277236c8da34f7c0a1ca962655cd2cbd8f2021bb5b176a72903a359e9
prompt_sha256: draft-1
translated_from: content/ru/1973/02/articles/11_resheniya-zadach-m146-m150-f164-f169-f862e2a1.md
source_content_sha256: 84cf7cfea5fb2f5d133252849d1ba7ddba2ff14476d1c61eb65a79e1d3375fec
translation_model: draft
translation_run: vi-draft-2026-10-31
translation_quality: draft
---

⟦folio 47⟧

Lời giải bài toán

M146—M150; F164—F169

M146. a) Tại các đỉnh của hình 7 giác đều xét qua một đoạn các đỉnh có các dấu hiệu cùng màu (nếu lấy màu thì đa giác đó có số cạnh chẵn).

a) Rõ ràng là trong số bảy đỉnh chắc chắn anh ta sẽ tìm thấy hai đỉnh lân cận có các thẻ cùng màu (nếu các màu được vẽ thì đa giác sẽ có số cạnh chẵn).

Chúng ta hãy biểu thị các đỉnh này bằng $A_1$ và $A_2$. Chúng ta có thể giả định rằng các mặt của chip có màu trắng (Hình 1). Lưu ý rằng có ba đỉnh, mỗi đỉnh cùng với các đỉnh $A_1$ và $A_2$ là một tam giác đều; hãy biểu thị chúng bằng $A_0$, $A_3$ và $B$. Nếu một trong số chúng chứa chip màu trắng thì hình tam giác tương ứng - $A_0A_1A_2$, - $A_3A_1A_2$ hoặc $BA_1A_2$ - là hình tam giác mong muốn. Nếu cả ba đỉnh đều có chip màu đen thì tam giác $A_0A_3B$ là tam giác mong muốn.

Lý do tương tự cũng đúng đối với bất kỳ $n$-giác thông thường nào có $n \geq 5$ lẻ (vai trò của $A_0$, $A_3$ được đóng bởi các đỉnh liền kề với $A_1$ và $A_2$, và vai trò của $B$ là điểm giữa của cung lớn hơn trong các cung $A_1A_2$).

6) Với $n = 8$ mệnh đề là sai. Một ví dụ về cách sắp xếp các quân cờ đen và trắng, trong đó không có ba quân cờ cùng màu nằm ở các đỉnh của một tam giác đều, được thể hiện trên Hình 2, b, c, d); Những ví dụ khác là có thể.

b) Đáp số: Mệnh đề đúng với $n = 5$, $n = 7$ và $n \geq 9$.

Ví dụ được mô tả trong Hình 2 cho thấy câu phát biểu đúng với $n = 3, 4, 6, 8$. Ở trên chúng ta đã chứng minh rằng nó đúng với $n = 5$, $n = 7$ và với số lẻ lớn $n$. Hãy chứng minh nó đúng với mọi $n \geq 9$.

Giả sử rằng đối với một khoảng cách nào đó các mã thông báo ở các đỉnh của $n$-giác thông thường thì câu lệnh là sai. Trước hết, rõ ràng là ở đâu đó sẽ có hai đỉnh liền kề có các chip cùng màu - nếu màu của các chip là màu đen thì tam giác đều cần thiết sẽ nằm ở gót của các đỉnh liên tiếp. Chúng ta có thể giả sử rằng đây là các đỉnh $A_4$ và $A_5$ với các mã thông báo lớn có màu (Hình 3). Sau đó tuần tự

| Chúng tôi đang xem xét | Chúng tôi rút ra kết luận |
| :--- | :--- |
| $A_3A_4A_5$ và $A_4A_5A_6$ | $A_3$ và $A_6$ có màu đen |
| $A_3A_6A_9$ | $A_9$ – trắng |
| $A_1A_5A_9$ và $A_5A_7A_9$ | $A_1$ và $A_7$ có màu đen |
| $A_1A_2A_3$ và $A_6A_7A_8$ | $A_2$ và $A_8$ - trắng |
| $A_2A_5A_8$ | mâu thuẫn |

Có thể chứng minh rằng một phát biểu mạnh hơn cũng đúng: đối với bất kỳ phân vùng nào của tập {1, 2, ..., 9} thành hai tập con, thì ít nhất trong một trong các tập con đó sẽ có các số trong đó một tập bằng hai tập con còn lại. Chúng tôi đã chứng minh điều này

⟦folio 48⟧

Cơm. 3.

khẳng định theo giả định bổ sung rằng 4 và 5 thuộc cùng một tập hợp con. Các trường hợp khác cũng tương tự.

**M147.** Hãy chứng minh rằng nếu tứ giác ABCD ngoại tiếp đường tròn sao cho các tiếp tuyến của đường tròn tại điểm A và C cắt nhau trên phần kéo dài của đường chéo BD thì
a) các tiếp tuyến tại các điểm B và D cắt nhau dọc theo đường chéo AC;
b) các đường phân giác của các góc trong A và C của tứ giác cắt nhau trên đường chéo BD (và các nút B và D - trên AC).

a) Cho A, B, C là ba điểm trên đường tròn, K là giao điểm của các tiếp tuyến vẽ tại các điểm A và C. Tìm điều kiện xác định vị trí điểm D của giao điểm đường thẳng BK với đường tròn (Hình 4).

$$\triangle ABK \sim \triangle DAK: \text{угол } K \text{ у этих треугольников общий, а } \triangle BAK = \triangle ADK, \text{ поскольку каждый из них изменяется положенной дуги } AB. \text{ Поэтому}$$

$$\frac{AB}{AD} = \frac{BK}{AK} = \frac{AK}{DK}$$

(đồng thời chứng minh định lý nổi tiếng: $AK^2 = BK \cdot KD$).

Tương tự như vậy $\triangle CBK \sim \triangle DCK$, và do đó

$$\frac{BC}{CD} = \frac{BK}{CK} = \frac{CK}{DK}$$

(đồng thời chứng minh định lý nổi tiếng: $AK^2 = BK \cdot KD$).

Vế phải trong (1) và (2) bằng nhau vì $AK = CK$, do đó

$$\frac{AB}{BC} = \frac{AD}{CD}$$

(lưu ý rằng tỷ lệ $AD/CD$ tăng theo cấp số nhân khi điểm D di chuyển dọc theo một cung tròn từ A đến C. Thật vậy, theo định lý sin áp dụng cho $\triangle ACD$ (Hình 5))

$$\frac{AD}{CD} = \frac{\sin C}{\sin A} = \frac{\sin (180^\circ - D - A)}{\sin A} = \sin (180^\circ - D) \cdot \text{ctg } A - \cos (180^\circ - D);$$

ở đây $180^\circ - D$ là một giá trị không đổi, $\sin (180^\circ - D) > 0$ và $\text{ctg } A$ giảm đơn điệu khi $A$ tăng từ 0 đến $180^\circ - D$, nghĩa là khi điểm D di chuyển từ C đến A. Nó tuân theo điều kiện (3) tương ứng với một định nghĩa về vị trí của điểm D (đối với A, B và C đã cho).

Như vậy, điều kiện (3) không những cần mà còn đủ để các điểm B, D và giao điểm của các tiếp tuyến dựng tại các điểm A và C cùng nằm trên một đường thẳng.

Tương tự, có thể chứng minh điều kiện cần và đủ để các tiếp tuyến tại điểm B và D cắt nhau trên đường thẳng AC có thể viết như sau:

$$\frac{BA}{DA} = \frac{BC}{DC}.$$

Nhưng điều kiện (3) và $(3')$ rõ ràng trùng khớp:

$$AB \cdot CD = BC \cdot AD.$$

Điều này làm cho tuyên bố bài toán a) hiển nhiên.

6) Gọi $L_1$ là giao điểm của bissertrix góc A của tam giác BAD với đường thẳng BD (Hình 6). Sau đó, như đã biết,

$$\frac{BL_1}{L_1D} = \frac{AB}{AD}.$$

Tương tự, nếu $L_2$ là giao điểm của bissertrix góc C với BD thì

$$\frac{BL_2}{L_2D} = \frac{BC}{CD}.$$

Pozny từ điều kiện (3) suy ra rằng

$$\frac{BL_1}{L_1D} = \frac{BL_2}{L_2D}.$$

Nhưng mỗi giá trị $\frac{BL}{DL}$ tương ứng với một điểm L trên đoạn BD,

⟦folio 49⟧

vì khi điểm $L$ di chuyển từ $B$ đến $D$ thì giá trị này tăng đơn điệu. Do đó, điểm $L_1$ và $L_2$ trùng nhau.

**M148. Trình tự $x_0, x_1, x_2, \dots$ được xác định bởi các điều kiện sau: $x_0 = 1$, $x_1 = \lambda$, với mọi $n > 1$**

$$(\alpha + \beta)^n x_n = \alpha^n x_n x_0 + \alpha^{n-1} \beta x_{n-1} x_1 + \alpha^{n-2} \beta^2 x_{n-2} x_2 + \dots + \beta^n x_0 x_n.$$

Ở đây $\lambda, \alpha, \beta$ là các số dương. Gán $x_n$ và tìm ra tại đó $n$ giá trị $x_n$ sẽ lớn nhất.

Chúng ta hãy viết ra các đẳng thức xác định $x_n$ cho một vài giá trị đầu tiên của $n > 1$ (sử dụng các điều kiện $x_0 = 1$):

$$[(\alpha + \beta)^2 - \alpha^2 - \beta^2] x_2 = \alpha \beta x_1^2,$$

$$[((\alpha + \beta)^3 - \alpha^3 - \beta^3] x_3 = \alpha^2 \beta x_2 x_1 + \alpha \beta^2 x_1 x_2,$$

$$[((\alpha + \beta)^4 - \alpha^4 - \beta^4] x_4 = \alpha^3 \beta x_3 x_1 + \alpha^2 \beta^2 x_2^2 + \alpha \beta^3 x_1 x_3.$$

Từ đây chúng ta tìm thấy (sử dụng các điều kiện $x_1 = \lambda$):

$$x_2 = \frac{\lambda^2}{2}, \quad x_3 = \frac{\lambda^3}{2 \cdot 3}, \quad x_4 = \frac{\lambda^4}{2 \cdot 3 \cdot 4}.$$

Đó là điều tự nhiên khi cho rằng

$$x_n = \frac{\lambda^n}{n!},$$

ở đâu $n! = 1 \cdot 2 \cdot \dots \cdot n$. Chúng ta hãy chứng minh bằng quy nạp rằng điều này đúng với mọi $n$ (nếu chúng ta giả sử, theo thông lệ, rằng $0! = 1! = 1$, thì công thức $x_n = \frac{\lambda^n}{n!}$ đúng với $n = 0$ và $n = 1$).

Chúng ta có thể coi đó là điều đã biết rằng $x_k = \frac{\lambda^k}{k!}$ đối với tất cả $k \leq n - 1$. Khi đó từ đẳng thức

$$[((\alpha + \beta)^n - \alpha^n - \beta^n] x_n = \sum_{k=1}^{n-1} \alpha^n - k \beta^k x_{n-k} x_k = \sum_{k=1}^{n-1} \frac{\alpha^n - k \beta^k \lambda^n - k \lambda^k}{(n-k)! k!} = \frac{\lambda^n}{n!} \sum_{k=1}^{n-1} C_n^k \alpha^n - k \beta^k = \frac{(\alpha + \beta)^n - \alpha^n - \beta^n}{n!} \frac{\lambda^n}{n!}$$

theo sau $x_n = \frac{\lambda^n}{n!}$ vì $\alpha > 0$ và $\beta > 0$ và thừa số chung của bên trái và bên phải là dương tại $n > 1$.

Chúng tôi sử dụng công thức trên

$$C_n^k = \frac{n!}{k!(n-k)!}$$

cho hệ số khai triển nhị thức

$$(a + b)^n = \sum_{k=0}^{k=n} C_n^k a^{n-k} b^k,$$

được mô tả trong bài viết của V. N. Vaguten (xem trang 27-34).

Cùng tìm hiểu xem $n$ giá trị $x_n$ lớn nhất là bao nhiêu, không vượt quá $\lambda$, từ đây ta nhận được đáp số cho câu hỏi bài toán: giá trị lớn nhất $x_n$ lấy ở $n = [\lambda]$ ($[\lambda]$ là số nguyên lớn nhất, không vượt quá $\lambda$); nếu $\lambda$ là số nguyên thì $x_{[\lambda]-1} = x_{[\lambda]}$ là hai số cao nhất của dãy $x_n$.

Hình 7 hiển thị biểu đồ của chuỗi $n \rightarrow x_n$ cho $\lambda = 2,5$ để minh họa.

**M149. Gọi $O$ là lũy thừa giao điểm của tứ giác ABCD với các đường chéo. Chứng minh rằng**

a) nếu các tam giác ABC, BCD, CDA và DAB có chu vi bằng nhau thì ABCD là hình chữ nhật;

b) Nếu các tam giác ABO, BCO, CDO và DAO có chu vi bằng nhau thì ACBD là hình thoi.

a) Hãy ký hiệu các cạnh và các đường chéo của tứ giác như trên Hình 8. Từ các đẳng thức

$$x_1 + x_2 + y_1 = x_3 + x_4 + y_1,$$

$$x_2 + x_3 + y_2 = x_1 + x_4 + y_2,$$

cộng chúng với nhau (và trừ cái này với cái kia), chúng ta tìm thấy: $x_2 = x_4, x_1 = x_3$. Do đó ABCD là hình bình hành.

⟦folio 50⟧

Cơm. 8.

Từ sự bình đẳng
$$x_1 + x_2 + y_1 = x_2 + x_3 + y_2 = x_2 + x_1 + y_2$$
Theo đó, $y_1 = y_2$, tức là $ABCD$, là hình chữ nhật.

6) Trên mỗi đường chéo $AC$, $BD$, chúng tôi chọn đoạn lớn hơn mà nó được chia cho điểm $O$. Chúng ta có thể giả sử, thay đổi ký hiệu nếu cần, rằng $AO \geq OC$, $BO \geq OD$ (Hình 9). Khi đó chu vi của tam giác $AOB$ không nhỏ hơn chu vi của tam giác $COD$ và chỉ có thể bằng nhau nếu $AO = OC$ và $BO = OD$. (Để xác minh điều này, chỉ cần dựng một tam giác $A'OB'$, đối xứng với tam giác $AOB$ so với điểm $O$; $A'OB'$ bao trùm $COD$.) Nhưng nếu $AO = OC$ và $BO = OD$, thì từ sự bằng nhau của các chu vi, ngay lập tức suy ra rằng $AB = BC = CD = DA$, rằng là $ABCD$ - hình thoi.

N. B. Vasiliev

M150. Từ các số 1, 2, ..., $k$ tạo ra tất cả các tập hợp có thể có $(a_1, a_2, ..., a_n)$ có độ dài $n$ (dễ dàng nhận thấy có $k^n$ trong số đó). Chọn tối đa hai điều ước $P$ và $Q$ (nên đưa cùng một bộ vào $P$ và $Q$). Được biết, nếu chúng ta lấy một tập hợp tùy ý $(p_1, p_2, ..., p_n)$ từ $P$ và một tập hợp tùy ý $(q_1, q_2, ..., q_n)$ từ $Q$, thì chúng sẽ trùng nhau ít nhất ở một chỗ (có thể là $p_i = q_i$ đối với một số $i$). Khi đó có nhiều nhất $k^{n-1}$ bộ trong $P$ hoặc $Q$.

Cơm. 10.

Chứng minh tuyên bố này
a) cho $k = 2$ và bất kỳ $n$ nào;
b) cho $n = 1, 2, 3$ và bất kỳ $k$ nào;
c) cho $k \geq 2$ và $n \geq 1$ tùy ý.

Hãy thử tìm các hạn chế khác về số lượng phần tử trong các tập hợp con $P$ và $Q$ liên quan đến các điều kiện tối đa.

a) $k = 2$. Chúng ta gọi tập hợp $\bar{d}$ đối diện với tập hợp $d$ nếu $\bar{d}$ thu được từ $d$ bằng cách thay tất cả 1 bằng 2 và 2 bằng 1. Gọi $\bar{M}$ biểu thị tập hợp tất cả các tập hợp đối diện với tập hợp $M$. Bộ $d$ và $\bar{d}$ không trùng nhau ở bất kỳ chỗ nào. Do đó, nếu $d$ được đưa vào $P$ thì $\bar{d}$ không thể được đưa vào $Q$. Điều này có nghĩa là $\bar{P}$ và $Q$ không chứa các bộ giống hệt nhau. Do đó, $\bar{P}$ hoặc $Q$ chứa không quá một nửa tổng số bộ. Nhưng $P$ và $\bar{P}$ có cùng số bộ. Điều này có nghĩa là $P$ hoặc $Q$ chứa không quá một nửa tổng số bộ, tức là không quá $2^{n-1}$ bộ.

Cơm. 9.

6) Đối với $n = 1$ mệnh đề là hiển nhiên.
Đối với $n = 2$ bài toán có thể được biểu diễn như sau: $k^2$ các điểm được đặt trên mặt phẳng tại các nút của mạng vuông $(k-1) \times (k-1)$ (Hình 10). Một số điểm này cần được sơn màu đỏ, một số - màu xanh lam để bất kỳ điểm đỏ và xanh nào nằm trong cùng một cột hoặc trên cùng một đường thẳng (nghĩa là tình huống c) là không thể). Tuy nhiên, một điểm có thể được sơn bằng cả hai màu (trường hợp d). cần phải

⟦folio 54⟧

Cơm. 13.

giảm nhẹ của các quốc gia. Xi lanh Melloisoller từ môi trường.

Pít-tông được giải phóng và sau khi thiết lập trạng thái cân bằng, thể tích chiếm giữ của khí sẽ tăng gấp đôi. Nhiệt độ của khí và áp suất của nó sẽ thay đổi như thế nào? Nhiệt dung của xi lanh, piston và lò xo rất nhỏ.

Theo định luật nhiệt động thứ nhất, lượng nhiệt Q truyền cho chất khí bằng tổng độ biến thiên nội năng của chất khí ΔU và công A mà nó thực hiện:

$$Q = \Delta U + A.$$ (1)

Nhưng trong trường hợp này, bình ổn nhiệt và Q = 0. Do đó,

$$\Delta U + A = 0.$$ (2)

Nghĩa là công của chất khí được thực hiện bằng cách giảm nội năng của nó nên có thể nói ngay rằng nhiệt độ của chất khí giảm.

Đầu tiên, đặt nhiệt độ khí là $T_1$, áp suất $P_1$ và thể tích $V_1$, sau khi nhả piston và thiết lập trạng thái cân bằng, các thông số khí trở nên tương ứng $T_2$, $P_2$ và $V_2$ và $V_2 = 2V_1$ (theo điều kiện).

Sự thay đổi nội năng của khí lý tưởng tỷ lệ thuận với sự thay đổi nhiệt độ của khí và bằng

$$\Delta U = c_v (T_2 - T_1),$$ (3)

trong đó $c_v$ là nhiệt độ của 1 mol khí ở thể tích không đổi.

Hơn nữa, công do chất khí thực hiện bằng độ biến thiên thế năng của lò xo biến dạng:

$$A = \frac{kx^2}{2}$$ (4)

(x là độ dịch chuyển của piston).

Hãy để chúng tôi biểu thị các giá trị của $\frac{kx^2}{2}$ theo các thông số khí.

Vì piston đứng yên sau khi thiết lập trạng thái cân bằng nên lực lò xo $F = kx$ bằng lực ép khí $P_2S$ (S là diện tích bề mặt của piston):

$$kx = P_2S.$$ (5)

Áp suất của chất khí có liên quan đến nhiệt độ của trạng thái khí bên trong của nó. Đối với một mol khí

$$P_2V_2 = RT_2.$$ (6)

Vì thể tích khí trong quá trình phân phối tăng lên và sự thay đổi về thể tích khí là $Sx$, sau đó là $V_2 = 2Sx$, và do đó,

$$2P_2Sx = RT_2.$$ (7)

Xét sự tương ứng (5) và (7), chúng ta có thể viết

$$kx = \frac{RT_2}{2x}$$ (8)

$$kx^2 = \frac{RT_2}{2}.$$ (9)

Vậy công mà khí thực hiện bằng

$$A = \frac{kx^2}{2} = \frac{RT_2}{4}.$$ (10)

Hãy thay thế biểu thức (3) và (10) thành đẳng thức (2):

$$c_v (T_2 - T_1) + \frac{1}{4}RT_2 = 0.$$

Từ đây

$$T_2 = T_1 \frac{1}{1 + \frac{1}{4} \frac{R}{c_v}}.$$ (11)

Thật vậy, $T_2$ nhỏ hơn $T_1$.

Bây giờ hãy xem áp suất khí thay đổi như thế nào. Theo phương trình trạng thái khí, áp suất khí ban đầu $P_1$, thể tích $V_1 = \frac{V_2}{2}$ và nhiệt độ $T_1$ liên hệ với nhau bởi công thức

$$P_1 \frac{V_2}{2} = RT_1.$$

Chia đẳng thức này cho đẳng thức (6), chúng ta thu được

$$\frac{P_1}{P_2} = 2 \frac{T_1}{T_2} = 2 \left(1 + \frac{1}{4} \frac{R}{c_v}\right),$$

$$P_2 = \frac{P_1}{2 \left(1 + \frac{1}{4} \frac{R}{c_v}\right)}$$

Áp lực cũng giảm đi.

F167. Chúng tôi kết nối một ampe kế lý tưởng với đầu ra của “hộp đen”. Nếu chúng ta kết nối pin với ví dụ: vào đầu vào của “hộp”. d.s. E và điện trở trong r thì có thể nhỏ hơn đúng 2 lần so với trường hợp hai pin mắc nối tiếp được nối với đầu vào của hộp. Hãy vẽ sơ đồ đơn giản nhất có thể về cấu trúc bên trong của “hộp đen”.

⟦folio 55⟧

Cơm. 14.

Một mạch điện bên trong không thể chỉ bao gồm điện trở. Thật vậy, hãy xem xét mạch hiển thị trong Hình 14, trong đó $R$ là điện trở của “cái hộp”.
Khi kết nối một nguồn, dòng điện phải chạy qua bộ khuếch đại

$$I = \frac{E}{R + r},$$

(1)

và khi hai nguồn được kết nối - 2I hiện tại và

$$2I = \frac{2E}{R + 2r}.$$

(2)

Phương trình (1) và (2) không tương thích. Họ không có lời giải cho bất kỳ $R$ nào. Thật vậy, chia phương trình (1) cho (2), chúng ta thu được

$$\frac{1}{2} = \frac{R + 2r}{2(R + r)}$$

hoặc

$$R + r = R + 2r,$$

nhưng điều này là không thể.

Việc kết nối một điện trở song song với đầu vào hoặc đầu ra của hộp cũng không giúp ích được gì. (Cho nó xem!). Do đó, mạch bên trong phải bao gồm phần tử “hoạt động” - nguồn dòng điện.

Cơm. 15.

Chúng ta hãy xem xét một trong các sơ đồ khả thi được hiển thị trong Hình 15 và chỉ ra rằng nó thỏa mãn điều kiện bài toán.

Khi nối 1 cục pin vào đầu vào của hộp thông qua cường độ dòng điện thì dòng điện sẽ tăng

$$I_1 = \frac{E + E_1}{r + r_1},$$

và khi kết nối hai - hiện tại

$$I_2 = \frac{2E + E_1}{2r + r_1}.$$

Vì $I_2 = 2I_1$ thì

$$\frac{2(E + E_1)}{r + r_1} = \frac{2E + E_1}{2r + r_1}.$$

Từ đây chúng ta sẽ tìm thấy

$$E_1 = -E \frac{2r}{3r + r_1}.$$

Sự bình đẳng này kết nối e. d.s. nguồn $E_1$ và điện trở trong của nó $r_1$. Dấu “—” nghĩa là nguồn là nguồn nội bộ.

F168. Cây bút chì sáu phút đứng im dọc theo mặt phẳng ngang, như trong Hình 16. Tại giá trị nào của hệ số thời gian $\alpha$ giữa cây bút chì và mặt phẳng thì cây bút chì sẽ trượt dọc theo mặt phẳng mà không lành lại?

Hai lực tác dụng lên một cây bút chì đang chuyển động từ các cạnh của mặt phẳng: phản lực pháp tuyến của mặt phẳng $N$ và lực ma sát $F_{TP}$. Vì bút chì không được di chuyển theo phương thẳng đứng nên lực $N$ có ​​giá trị tuyệt đối bằng lực:

$$N = mg.$$

Lực ma sát bằng $F_{TP} = \alpha N = \alpha mg$.

Hãy xem xét thời điểm bút chì bắt đầu lăn, xoay quanh mép $A$. Trong trường hợp này, cả hai lực—lực $N$ và lực $F_{TP}$—đều tác dụng lên cạnh $A$. Nếu lực bằng nhau $R$ của các lực này truyền xuống bên dưới trọng tâm của bút chì, tức là bên dưới trục của bút chì, thì mômen của lực này so với trục của bút chì sẽ làm cho bút chì quay. Nếu lực $R$ vượt lên trên trục thì bút chì sẽ không quay.

Vậy điều kiện để bút chì không quay được:

$$tg \beta = \frac{N}{F_{TP}} > tg 60^\circ,$$

hoặc

$$\frac{mg}{\alpha mg} > \sqrt{3}.$$

⟦folio 56⟧

Cơm. 17.

Từ đây chúng ta tìm được hệ số ma sát phải là:

$$\alpha < \frac{1}{\sqrt{3}}.$$

Nhiều độc giả đã gửi thư cho chúng tôi đã giải quyết được bài toán này bằng cách thử hệ tọa độ không liên kết với mặt phẳng mà bằng bút chì. Đây là hệ tọa độ không quán tính và trong đó cây bút chì vẫn chịu quán tính rất mạnh.

$$F_{\pi} = ma,$$

trong đó $a$ là gia tốc của bút chì so với mặt phẳng.

Vì gia tốc này truyền cho bút chì lực ma sát trên mặt phẳng $F_{\pi} = \alpha mg$, rồi $a = \alpha g$, và do đó $F_{\pi} = m\alpha g$. Bút chì quay quanh cạnh $A$ (trục quay tức thời), nếu mômen lực $F_{\pi}$ so với điểm này lớn hơn mô men lực của vật nặng (Hình 17), tức là nếu

$$F_{\pi} \cdot \frac{a \sqrt{3}}{2} > \frac{1}{2} mg,$$ hoặc

$$\alpha mg \sqrt{3} > mg.$$

Từ đó ta thấy bút chì lăn không quay nếu

$$\alpha < \frac{1}{\sqrt{3}}.$$

F169. Để liên lạc trong không gian khoảng cách xa, một vệ tinh có thể tích $V=100$ m³, chứa đầy không khí trong điều kiện bình thường, được sử dụng. Meterorim chúng tôi vượt qua vùng bị từ chối $S=1$ cm² trong cơ thể của nó. Tính thời gian sau đó áp suất bên trong vệ tinh thay đổi 1%. Nhiệt độ của khí không đổi. Hằng số khí phổ quát là 8,3·10³ J/deg·kmol.

Để ước tính, chúng ta có thể giả sử rằng mỗi phân tử không khí trong vệ tinh chỉ có thể chuyển động dọc theo một trong ba trục vuông góc với nhau, một trong số đó vuông góc với mặt phẳng bác bỏ (mô hình đơn giản hóa như vậy thường được sử dụng trong lý thuyết động học của chất khí). Sau đó, tại bất kỳ thời điểm nào, 1/3 tổng số phân tử không khí trong vệ tinh sẽ di chuyển dọc theo trục này và tốc độ của một nửa số phân tử này, tức là 1/6 tổng số phân tử, hướng tới sự loại bỏ. Trong số này, theo thời gian $t$, những phân tử ở khoảng cách $l = \bar{v}t$ so với mức bị từ chối sẽ bị từ chối và bay ra khỏi vệ tinh, tức là các phân tử nằm ở thời điểm ban đầu về thể tích $V_0 = S\bar{v}t$, trong đó $\bar{v}$ là vận tốc bình phương trung bình của các phân tử (Hình 18). (Chúng tôi giả định để đánh giá rằng tất cả các phân tử đều chuyển động với cùng vận tốc abscylotic, bằng vận tốc bình phương trung bình $\bar{v}$). Nếu số lượng phân tử trên một đơn vị thể tích là $n$, thì chỉ trong thời gian $t$

$$N = \frac{1}{6} S\bar{v}t n \text{ молекул.}$$

Vì các phân tử bị đẩy ra khỏi vệ tinh nên số lượng phân tử trên một đơn vị thể tích sẽ thay đổi. Sự thay đổi này là

$$\Delta n = \frac{N}{V} = \frac{1}{6} \frac{S\bar{v}t n}{V}.$$

Sự tương ứng này có thể được viết lại thành

$$\frac{\Delta n}{n} = \frac{1}{6} \frac{S\bar{v}t}{V}$$

hoặc

$$\tau = 6 \frac{\Delta n}{n} \frac{V}{S\bar{v}}.$$

Theo điều kiện bài toán nhiệt độ không khí trong vệ tinh không đổi. Như sau từ phương trình trạng thái Clapeyron-Mendleev đối với khí lý tưởng, trong trường hợp này, áp suất tỷ lệ thuận với mật độ của khí (và do đó tỷ lệ với số lượng phân tử trên một đơn vị thể tích): $P \sim n$. Đó là lý do tại sao

$$\frac{\Delta P}{P} = \frac{\Delta n}{n} = 0,01.$$

Có tính đến biểu thức cho tốc độ bình phương trung bình của các phân tử

$$\bar{v} = \sqrt{\frac{3RT}{\mu}},$$

⟦folio 59⟧

Lời giải. Trong trường hợp này, giả sử lời giải được gợi ý bởi tính đối xứng của phương trình này đối với sin x, cos x. Xác định rõ ràng các đa thức đối xứng đơn giản nhất của sin x và cos x (các biểu thức sin x + cos x, sin x cos x), ta viết phương trình dưới dạng

$$(\sin x + \cos x) - 4 \sin x \cdot \cos x + \sin x \cdot \cos x (\sin x + \cos x) = 2.$$

Đặt sin x + cos x = u; thì $u^2 - 1 = 2 \sin x \cdot \cos x$ và phương trình có dạng

$$u (u^2 - 4 u + 1) = 0,$$

từ đâu $u_1 = 0, u_2 = 2 + \sqrt{3}, u_3 = 2 - \sqrt{3}$.

Phương trình sin x + cos x = u có thể giải dễ dàng, và vì |u| = |sin x + cos x| = |\sqrt{2} \cos \left( x - \frac{\pi}{4} \right)| \leqslant \sqrt{2} thì gốc $u_2 = 2 + \sqrt{3}$ không phù hợp.

Đáp số: $x = -\frac{\pi}{4} + k\pi; x = \frac{\pi}{4} \pm \arccos \frac{2 - \sqrt{3}}{\sqrt{2}} + 2l\pi$.

Nhóm ví dụ tiếp theo cho thấy rằng để thành công lời giải được đưa ra trong các kỳ thi đăng ký bài toán, việc rút gọn một phương trình thành một trong các loại đã biết là chưa đủ (các phương trình có thể rút gọn thành một hàm lượng giác duy nhất, đồng nhất, đối xứng, v.v.).

Ví dụ 4 (MIPT, 1970). Giải phương trình

$$\sin x + 2 \cos x = \cos 2x - \sin 2x.$$

Lời giải. Chuyển phương trình (1) cho đối số x sử dụng các công thức sin 2x = 2 sin x cos x và cos 2x = $\cos^2 x - \sin^2 x = 1 - 2 \sin^2 x$, ta thu được

$$\sin x + 2 \sin^2 x + 2 \cos x + 2 \sin x \cos x - 1 = 0.$$

Phương trình (2) có thể được rút gọn thành phương trình đại số cho u bằng cách sử dụng cái gọi là giá trị phổ quát $u = \mathrm{tg} \frac{x}{2}$, biểu thị sin x và cos x theo u. Dễ dàng thấy rằng trong trường hợp này chúng ta thu được phương trình

$$3 u^4 + 2 u^3 - 6 u^2 - 6 u - 1 = 0.$$

Chúng tôi sẽ không tìm ra nghiệm của phương trình này, mặc dù điều này có thể được thực hiện, nhưng chúng tôi sẽ cố gắng tìm một let lời giải ngắn hơn, dựa trên việc phân tích vế trái của phương trình.

Phương trình (2) có nghiệm sin x = -1 (trong trường hợp này cos x = 0), do đó vế trái của phương trình có thể được phân tích thành nhân tử:

$$(1 + \sin x)(2 \sin x + 2 \cos x - 1) = 0.$$

Đáp số: $x = -\frac{\pi}{2} + 2k\pi; x = -\frac{\pi}{4} + (-1)^n \arcsin \frac{1}{2 \sqrt{2}} + \pi n$.

Bình luận. Cần nhấn mạnh rằng phương pháp nhân tử hóa, kết hợp với các phương pháp khác, là một trong những ví dụ hiệu quả nhất về phương trình lượng giác lời giải.

⟦folio 61⟧

Trước khi chúng ta tiến xa hơn theo hướng này, hãy đơn giản hóa phương trình (7) bằng cách uống rượu.

Nhận thấy rằng $tg^2 x + ctg^2 x = -2 + \frac{4}{\sin^2 2x}$, chúng tôi tìm thấy

$$\frac{1}{\sin^2 2x} = 1 - \frac{1}{\sqrt{3}} \frac{\cos 2x}{\sin 2x}$$

và hơn nữa, biến đổi, chúng ta thu được $\sqrt{3} \cos^2 2x + \sin 2x \cdot \cos 2x = 0$. Phương trình cuối cùng rất dễ giải.

Đáp số: $x = \frac{\pi}{4} + \frac{k\pi}{2}$; $x = -\frac{\pi}{6} + \frac{l\pi}{2}$ (có thể dễ dàng kiểm tra xem đối với các giá trị này của $x$ thì chúng ta có $\sin 2x \neq 0$).

Lời giải thu được, tuy nhiên, để so sánh, bây giờ chúng ta hãy hoàn thành phương trình lời giải (7), phương trình đầu tiên đã dẫn chúng ta đến phương trình (8). Nhóm các số hạng có hệ số $\sqrt{3}$ sẽ cho phương trình

$$(u^2 - 1) \left[ \sqrt{3} (u^2 - 1) - 2u \right] = 0,$$

có gốc: $u_1 = 1; u_2 = -1; u_3 = \sqrt{3}; u_4 = -\frac{1}{\sqrt{3}}$.

Dễ dàng kiểm tra xem các nghiệm này có dẫn đến cùng đáp số hay không.

Bình luận. Không còn nghi ngờ gì nữa, trong trường hợp này, việc chuyển đổi phương trình bằng cách chuyển sang đối số $2x$ sẽ tốt hơn là thay thế $u = tg x$. Một lần nữa chúng ta thấy rằng việc tăng lập luận của các hàm lượng giác có trong phương trình sẽ dẫn đến sự đơn giản hóa của nó.

Hãy xem xét một ví dụ về một loại khác.

Ví dụ 8: Giải phương trình

$$tg (120^\circ + 3x) - tg (140^\circ - x) = 2 \sin (80^\circ + 2x).$$

Lời giải. Khi tìm đường đi lời giải hợp lý của phương trình (9), hiển nhiên người ta phải đặc biệt chú ý đến lập luận của các hàm lượng giác có trong phương trình. Mối liên hệ giữa các đối số sẽ trở nên rõ ràng nếu chúng ta nhận thấy rằng $tg (140^\circ - x) = -tg (x + 40^\circ)$. Giờ đây, việc sử dụng thay thế $x + 40^\circ = t$ là không còn nghi ngờ gì nữa. Sử dụng phép thay thế này, phương trình ban đầu được chuyển về dạng $tg 3t + tg t = 2 \sin 2t$, hoặc

$$\frac{\sin 4t}{\cos t \cdot \cos 3t} = 2 \sin 2t.$$

Vì $\sin 4t = 2 \sin 2t \cos 2t$, phương trình (10) có thể được biểu diễn dưới dạng

$$\frac{2 \sin 2t (\cos 2t - \cos 3t \cdot \cos t)}{\cos t \cdot \cos 3t} = 0.$$

Hãy chuyển đổi biểu thức trong ngoặc đơn bằng công thức

$$\cos 2t = \cos (3t - t) = \cos 3t \cdot \cos t + \sin 3t \cdot \sin t.$$

Sau đó bài toán rút gọn thành việc tìm các phương trình lời giải đó

$$\sin t \cdot \sin 2t \cdot \sin 3t = 0,$$

⟦folio 62⟧

thỏa mãn các điều kiện $\cos t \cdot \cos 3t \neq 0$, tức là đến lời giải của phương trình $\sin 3t = 0$.

Đáp số: $x = -40^\circ + \frac{n\pi}{3}$.

Ví dụ 9. Giải phương trình

$$\cos 3x + \cos \frac{5x}{2} = 2.$$

Lời giải. Nếu biến đổi vế trái của phương trình này bằng công thức tính tổng cosin, chúng ta sẽ thu được phương trình $\cos \frac{x}{4} \cdot \cos \frac{11x}{4} = 1$. Vì đối với bất kỳ $\alpha$ nào, bất đẳng thức $|\cos \alpha| \leq 1$ là hợp lệ nên phương trình kết quả chỉ có thể có lời giải nếu điều kiện được thỏa mãn

$$\begin{cases} \cos \frac{x}{4} = 1, \\ \cos \frac{11x}{4} = 1 \end{cases}$$ hoặc $$\begin{cases} \cos \frac{x}{4} = -1, \\ \cos \frac{11x}{4} = -1. \end{cases}$$

Bằng cách này người ta có thể tìm được lời giải của phương trình ban đầu. Tuy nhiên, có một con đường khác đơn giản hơn cũng dẫn đến mục tiêu.

Vế trái của phương trình chỉ có thể bằng hai trong trường hợp đẳng thức $\cos 3x = 1$ và $\cos \frac{5x}{2} = 1$ xảy ra đồng thời.

Tìm lời giải của phương trình thứ nhất ($x = \frac{2k\pi}{3}$) và thay nó vào phương trình thứ hai, chúng ta thu được $\cos \frac{5k\pi}{3} = 1$, từ đó $k = 6m$.

Đáp số: $x = 4m\pi$.

Các ví dụ sau yêu cầu khả năng sử dụng khái niệm giá trị tuyệt đối.

Ví dụ 10 (MIPT, 1971). Giải phương trình

$$\text{tg}x + \frac{1}{9}\text{ctg}x = \sqrt{\frac{1}{\cos^2x} - 1} - 1.$$

Lời giải. Vế phải của phương trình (11) có thể được viết như sau: $\sqrt{\text{tg}^2x} - 1 = |\text{tg}x| - 1$. Một sai lầm nghiêm trọng là loại bỏ dấu mô đun (không may là khá nhiều thí sinh giải ví dụ này đã mắc phải lỗi này). Phương trình (11) có dạng

$$\text{tg}x + \frac{1}{9}\text{ctg}x = |\text{tg}x| - 1.$$

Hãy xem xét hai trường hợp: $\text{tg}x > 0$, $\text{tg}x < 0$ (vì $\text{tg}x = 0$ vế trái của phương trình trở nên vô nghĩa).

a) Nếu $\text{tg}x > 0$, thì phương trình (12) được rút gọn về dạng $\text{ctg}x = -9$, ngụ ý rằng $\text{ctg}x < 0$, mâu thuẫn với điều kiện $\text{tg}x > 0$. Trong trường hợp này không có lời giải.

b) Nếu $\text{tg}x < 0$ thì giả sử $u = \text{tg}x$, từ (12) ta tìm được $18u^2 + 9u + 1 = 0$, từ đó

$$u_1 = -\frac{1}{6}; \quad u_2 = -\frac{1}{3}.$$

⟦folio 63⟧

Cả hai giá trị tìm thấy đều âm nên điều kiện $tg x < 0$ được thỏa mãn.

Đáp số: $x = -\arctg \frac{1}{6} + n\pi; \quad x = -\arctg \frac{1}{3} + m\pi$.

Ví dụ 11. Giải phương trình

$$\sin x + \sqrt{3} \cos x = \sqrt{2 + \cos 2x + \sqrt{3} \sin 2x}.$$

(13)

Lời giải. Vì vế phải của phương trình không âm nên điều kiện phải được thỏa mãn

$$\sin x + \sqrt{3} \cos x \geq 0.$$

(14)

Nếu loại bỏ căn thức bằng cách bình phương cả hai vế của phương trình (13), chúng ta thu được phương trình

$$\sin^2 x + 3 \cos^2 x + 2 \sqrt{3} \sin x \cos x = 2 + \cos 2x + \sqrt{3} \sin 2x,$$

mà sau phương trình có dạng

$$\cos 2x = \cos 2x.$$

(15)

Chúng tôi đã nhận được cử chỉ tương tự. Tuy nhiên, điều này không có nghĩa là phương trình ban đầu được thỏa mãn bởi tất cả các giá trị của $x$, vì phương trình (15) chỉ là hệ quả của phương trình (13). Phương trình (13) và (15) trở nên tương đương nếu điều kiện (14) được thỏa mãn. Như vậy, lời giải của phương trình (13) đều là các giá trị của $x$ thỏa mãn bất đẳng thức (14) và chỉ những giá trị này. Lời giải bất đẳng thức (14) không khó.

Đáp số: $-\frac{\pi}{3} + 2\pi n \leq x \leq \frac{2\pi}{3} + 2\pi n$.

Bình luận. đáp số này có thể được thực hiện theo nhiều cách. Chúng ta có $2 + \cos 2x + \sqrt{3} \sin 2x = \left[ 1 + \cos \left( 2x - \frac{\pi}{3} \right) \right] = 4 \cos^2 \left( x - \frac{\pi}{6} \right)$, và do đó phương trình ban đầu có dạng $\cos \left( x - \frac{\pi}{6} \right) = \left| \cos \left( x - \frac{\pi}{6} \right) \right|$. Chúng ta lại đến với điều kiện (14).

Bài tập

Giải phương trình:
1. (MIPT, 1969). $\sin^4 x + \sin^3 x \cdot \cos x + \sin^2 x \cos^2 x + \sin x \cdot \cos^3 x + \cos^4 x = 1$.
2. $\sin^3 x (1 + \text{ctg} x) + \cos^3 x (1 + \text{tg} x) = 2 \sqrt{\sin x \cos x}$.
3. (MIPT, 1971). $\cos^2 x + \cos^2 2x = \cos^2 3x$.
4. $\cos \frac{4x}{3} = \cos^2 x$.
5. (MIPT, 1970). $\sqrt{1 - 2 \text{tg} x} - \sqrt{1 + 2 \text{ctg} x} = 2$.
