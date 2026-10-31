---
id: 1985-4-resheniya-zadach-m896-m900-f908-f912-36871dc8
issue: kvant_1985_4
year: 1985
number: "4"
title: Lời giải bài toán M896—M900; F908—F912
rubric: zadachnik-kvanta
rubric_sub: Задачник «Кванта»
page_first: 41
page_last: 47
page_labels: 39, 40, 41, 43, 44
tag: 88RS
lang: vi
source: kvant_digital
extraction: vision
content_sha256: 645fe206ea338ac7f90fb574a912fe741d73e29f1b7fc3c4d98184a1724dd9c5
prompt_sha256: draft-1
translated_from: content/ru/1985/04/articles/16_resheniya-zadach-m896-m900-f908-f912-36871dc8.md
source_content_sha256: 235c9d7070b7a0887df40e8f8b5126ed1df7f7804aa0f403ba0402564d0221cd
translation_model: draft
translation_run: vi-draft-2026-10-31
translation_quality: draft
---

⟦folio 39⟧

Lời giải bài toán

M896 — M900; F908 — F912

Đầu tiên là lời giải. Đặt $M$ và $N$ là trung điểm của $AB$ và $CD$, $h_M$ và $h_N$ khoảng cách từ các điểm $M$ và $N$ đến các đường $CD$ và $AB$, $a$ và $b$ — độ dài cạnh $AB$ và $CD$ (hình 1). Rõ ràng, các đường thẳng $BC$ và $AD$ song song khi và chỉ khi mỗi đường thẳng song song với đường trung bình $MN$ của tứ giác, tức là khi $S_{MNB}=S_{MNC}$ và $S_{MNA}=S_{MND}$. (Chữ cái $S$, như thường lệ, biểu thị diện tích của các hình tam giác tương ứng.) Và vì $S_{MNA}=S_{MNB}=\frac{1}{2} \cdot \frac{AB}{2} \cdot h_N=\frac{a/h_N}{4}$ và tương tự, $S_{MNC}=S_{MND}=\frac{bh_M}{4}=\frac{ab}{8}$ (theo điều kiện $h_M=a/2$), các đường thẳng $BC$ và $AD$ song song khi và chỉ khi $h_N=b/2$, tức là khi một đường tròn có đường kính $CD$ chạm $AB$.

Thứ hai lời giải. Trước tiên chúng ta giả sử rằng các đường $AB$ và $CD$ cắt nhau tại điểm $O$ (hình 2). Chúng ta thực hiện đối xứng tuần tự đối với phân giác của góc $AOD$ và chuẩn bị tâm $O$ và hệ số $OC/OB$ (sao cho điểm $B$ tiến tới $C$). Trong trường hợp này, điểm $A$ sẽ đi đến một điểm nào đó $D'$ trên tia $OD$, và một đường tròn có đường kính $AB$ sẽ đi vào một đường tròn có đường kính $CD'$, rõ ràng là chạm vào đường thẳng $AB$. Các kỹ thuật $BC$ và $AD'$ là song song, vì $OC:OB=OD':OA$. Do đó, để hoàn thiện chứng minh, cần lưu ý rằng một đường tròn có đường kính $CD$ tiếp xúc với đường thẳng $AB$ khi và chỉ khi $D=D'$.

Trường hợp $AB\parallel CD$ được xét theo cách tương tự: bạn chỉ cần lấy một đường thẳng có độ dài bằng $AB$ và $CD$ làm trục đối xứng và thay thế đường thẳng đã hoàn thành bằng một bản dịch song song.

N. B. Vasiliev, V. N. Dubrovsky

◆ Đáp số: một trong các cặp được tìm kiếm là $x=1$, $y=18$.

Hãy biến đổi biểu thức này:

$(x+y)^7-x^7-y^7$
$=7x^6+21x^5y^2+35x^4y^3+35x^3y^4+21x^2y^5+7xy^6$
$=7xy(x^5+3x^4y+5x^3y^2+5x^2y^3+3xy^4+y^5)$
$=7xy(x+y)(x^4+2x^3y+3x^2y^2+2xy^3+y^4)$
$=7xy(x+y)(x^2+xy+y^2)^2$.

Để biểu thức này chia hết cho $7^7$, điều cần thiết là $x^2+xy+y^2$ phải chia hết cho $7^3$ (theo quy ước, $xy(x+y)$ không chia hết cho $7$). Hãy đặt $x=1$ và cố gắng tìm $y$ sao cho $1+y+y^2=7^3=343$. Phương trình bậc hai này có nghiệm $y_1=18$ và $y_2=-19$, do đó một trong lời giải bài toán — (1; 18).

Có thể chứng minh rằng tất cả các cặp số nguyên $(x, y)$ mà $x^2+xy+y^2$ chia hết cho $7^3$ (tức là lời giải của bài toán của chúng ta) được mô tả bằng công thức: $(343n+k, 343m+18k), (343n+18k,$

⟦folio 40⟧

M898*. Đối với các số tự nhiên lẻ $a < b < c < d$, các điều kiện sau thỏa mãn: $ad = bc$, $a + d = 2^k$ và $b + c = 2^m$, trong đó $k$ và $m$ là các số tự nhiên không toric. Chứng minh rằng $a) a = 1$;
b) với mỗi $m \geqslant 3$ có và chỉ một tập hợp số $a, b, c, d, k$ thỏa mãn các điều kiện này.

◆
a) Trước tiên chúng ta hãy thiết lập $k > m$ đó. Sử dụng dữ liệu, chỉ có một bộ số $a, b, c, d, k$ thỏa mãn các điều kiện này.

$$2^k - 2^m = a + d - (b + c) = a - b + d - \frac{ad}{b} = \frac{d}{b} (b - a) - (b - a) = (b - a) \left( \frac{d}{b} - 1 \right) > 0$$

(vì $b > a$, $d > b$), do đó $k > m$.

Bây giờ chúng ta hãy chứng minh rằng $a + b = 2^{m-1}$. Đẳng thức $ad = bc$ có thể được viết lại thành $a(2^k - a) = b(2^m - b)$, tức là $b^2 - a^2 = 2^m b - 2^k a = 2^m (b - 2^{k-m} a)$. Do đó, tích của $b + a$ và $b - a$ chia hết cho $2^m$ (chúng ta đã thấy rằng $2^{k-m}$ là một số nguyên). Đồng thời tổng của chúng là $2b$ và $b$ là số lẻ nên không thể chia hết cho 4 cùng một lúc. Và vì những số này là số chẵn nên một trong số chúng phải chia hết cho $2^{m-1}$ (và số còn lại chỉ chia hết cho $2^1$). Nhưng $b - a < b < (b + c)/2 = 2^{m-1}$, do đó $a + b$ chia hết cho $2^{m-1}$. Khi tính đến bất đẳng thức $a + b < b + c = 2^m$ chúng ta kết luận rằng $a + b = 2^{m-1}$.

Do đó, $b = 2^{m-1} - a$ do đó là $c = 2^m - b = 2^{m-1} + a$ và $ad = bc = 2^{2m-2} - a^2$ do đó là $a(a + d) = 2^{2m-2}$. Vì $a$ là số lẻ nên đẳng thức cuối cùng chỉ có thể xảy ra với $a = 1$.

b) Từ kết quả thu được ở cuối điểm a) tương ứng các số $a, b, c, d$ và $k$ thỏa mãn điều kiện bài toán khi và chỉ khi $a = 1$, $b = 2^{m-1} - 1$, $c = 2^{m-1} + 1$, $d = 2^{2m-2} - 1$, $k = 2m - 2$ cho $m \geqslant 3$.

A. P. Savin

◆
a) Trước hết, lưu ý rằng chỉ cần chứng minh mệnh đề bài toán cho đẳng thức có dạng là đủ

$$x_1 + \dots + x_m = 0.$$

(Trường hợp tổng quát sẽ giảm xuống mức này nếu chúng ta chuyển tất cả các số hạng từ vế phải sang trái và tính đến việc làm tròn số $-y_i$ trùng với làm tròn số $y_i$, lấy bằng dấu trừ, vì $-[y_i] - 1 \leqslant -y_i \leqslant -[y_i]$).

Chúng ta sẽ làm tròn các số $x_i$ theo đẳng thức (*) từng cái một: một trong số chúng sẽ được làm tròn và chúng ta sẽ đồng thời thay đổi một số khác với cùng một lượng theo hướng ngược lại - đẳng thức này sẽ không bị vi phạm. Tất cả những gì bạn phải làm là đảm bảo rằng việc làm tròn số thay đổi vẫn giữ nguyên. Sau không quá $m - 1$ các bước như vậy, chúng ta sẽ làm tròn tất cả các số trong đẳng thức (*) và kết quả vẫn đúng.

Vì vậy, đường dẫn trong đẳng thức (*) là các số không nguyên. Rõ ràng có ít nhất hai, ví dụ $x_i$

⟦folio 41⟧

và $x_j$ Giả sử rằng khoảng cách $d$ từ $x_i$ đến số nguyên gần nhất $x_i'$ không lớn hơn khoảng cách tương tự của $x_j$. Thay thế $x_i$ bằng $x_i'$ và $x_j$ bằng $x_j' = x_j + (x_i - x_i')$. Trong trường hợp này, số lần làm tròn các số hạng sẽ tăng lên, tổng của chúng vẫn bằng 0 và việc làm tròn số $x_j'$ sẽ giống như làm tròn số $x_j$, vì $[x_j] \leqslant x_j' \leqslant [x_j] + 1$.

6), c Chúng ta sẽ hành động theo kế hoạch tương tự như ở điểm a). Hãy thêm số $-a_j$, $i=1, ..., m$ vào hàng thứ $i$, dưới cột thứ $j$ - số $-b_j$, $j=1, ..., n$ và ở góc dưới bên phải của bảng mở rộng này, chúng ta đặt tổng của tất cả các số này $s = a_1 + ... + a_m = b_1 + ... + b_n$. Rõ ràng, chỉ cần chứng minh câu 6) (hoặc c)) cho một bảng mới là đủ, tức là với điều kiện tổng các số ở tất cả các hàng và cột đều bằng 0. Để các điều kiện này được giữ nguyên khi làm tròn số tiếp theo, chúng ta sẽ cần thay đổi toàn bộ số nguyên cùng với số này và cách làm tròn của chúng phải giữ nguyên. Hãy để chúng tôi mô tả việc xây dựng một số nguyên như vậy.

Hãy lấy một số không nguyên $x_1$ từ bảng; trong cùng một dòng với nó nhất thiết phải có một số không nguyên khác $x_2$, trong cùng một cột với $x_2$ có ​​một số không nguyên $x_3$, trong cùng một cột với $x_3$ có một số không nguyên $x_4$, v.v. (xem hình 1, 2). Đến một lúc nào đó chắc chắn chúng ta sẽ gặp một số nằm cùng hàng (hàng hoặc cột) với số gặp trước đó. Đặt $x_k$ là số đầu tiên như vậy và đặt nó ở cùng cột với $x_k$ ($l < k$).

Giả sử $x_{l+1}$ nằm trên cùng dòng với $x_l$ (hình 1). Sau đó xét các số nguyên $x_p, x_{l+1}, ..., x_k$. Bất kỳ hai số liên tiếp nào trong số nguyên này đều nằm trên cùng một hàng (bên cạnh $x_k$ chúng tôi xem xét $x_l$) và ở mỗi bước, số nguyên “chuyển thành $90^\circ$”, do đó, trong cùng một dòng, cũng như trong cùng một cột với bất kỳ số nào trong số chúng, có chính xác một số nữa và tổng số các số trong số nguyên đó là số chẵn. Hãy chọn số gần với một số nguyên (nếu có một vài số nguyên thì bất kỳ số nào trong số đó), đặt số này là $x_i$ và số nguyên gần nhất là $x_i + d$. Hãy thay thế $x_i$ bằng cách làm tròn $x_i + d$ và di chuyển dọc theo số nguyên, chúng ta sẽ lần lượt thêm $-d$ hoặc $d$ cho mỗi số tiếp theo (thay $x_{i+1}$ bằng $x_{i+1} - d$, $x_{i+2}$ bằng $x_{i+2} + d$, v.v.). Khi duyệt toàn bộ số nguyên, chúng ta sẽ được một bảng mới có tổng bằng 0 theo hàng và cột, việc làm tròn tất cả các số không nguyên trong đó sẽ giống như trước và số lượng số nguyên sẽ tăng lên.

Nếu hóa ra $x_{l+1}$ nằm trong cùng một cột với $x_l$ (hình 2), thì phải kiểm tra chính xác lý do tương tự với toàn bộ $x_{l+1}, x_{l+2}, ..., x_k$.

Sau vài lần lặp lại thao tác này, tất cả các số trong bảng sẽ trở thành số nguyên.

Với bài toán c) chúng ta đã chứng minh thành công rằng tổng các làm tròn của các số trong bảng ban đầu mà chúng ta đã xây dựng là làm tròn tổng của chúng.

A. P. Savin

⟦folio 43⟧

=2, trong đó B, P và G là số đỉnh, cạnh và mặt của nó *)). Chúng ta sẽ suy ra (2) bằng cách làm theo một trong nhiều cách chứng minh công thức Euler.

Chúng ta hãy tính tổng $\sigma$ của tất cả các góc của tất cả các đa giác của ô xếp “đỏ” theo hai cách. Tổng các góc tại các đỉnh của đa giác P bằng $(m-2)\pi$ và tổng các góc tại các đỉnh “bên trong” $q_k$ là $2q_k\pi$. Vì vậy, $\sigma = (m-2+2q_k)\pi$. Mặt khác, bằng cách cộng tổng các góc của từng đa giác của phân vùng, tức là giá trị $(k-2)\pi$, trong đó $k$ là số cạnh của đa giác, chúng ta thấy rằng $\sigma = (N-2n_k)\pi$, trong đó $N$ là tổng số cạnh của tất cả các đa giác này, bằng $m+2p_k$. Do đó, $m-2+2q_k = m+2p_k-2n_k$, ngụ ý (2).

M. D. Kovalev

F908. Máy bay bay theo một đường thẳng về phía nhau với cùng tốc độ v. Phạm vi phát hiện tối đa - l. Tuy nhiên, sau khi phát hiện một chiếc máy bay khác, nó quay đầu mà không thay đổi tốc độ và bay song song với chiếc máy bay thứ hai, tiếp tục bay với tốc độ $\vec{v}$. Liệu các máy bay có mất dấu nhau sau khi rẽ nếu gia tốc trong lúc rẽ là a? Sau bao lâu kể từ khi phát hiện thì việc rẽ phải bắt đầu sao cho khi kết thúc lượt rẽ, khoảng cách giữa các máy bay là nhỏ nhất?

$$L^2 = x^2 + y^2 = (l - \pi R - 2v\tau)^2 + 4R^2.$$

Rõ ràng là giá trị của $L$ (τ) là tối thiểu với giá trị tối thiểu có thể có là $|x(\tau)|$ (y không phụ thuộc vào τ). Về vấn đề này, có hai trường hợp phát sinh: tại $l \geqslant \pi R$ điểm bắt đầu $L = 2R$ đạt đến $x=0$, tức là khi

$$\tau = \frac{l - \pi R}{2v} = \frac{1}{2} \left( \frac{l}{v} - \frac{\pi v}{a} \right);$$

tại $l < \pi R$ giá trị của $L$ là tối thiểu tại $\tau=0$ và bằng $L = \sqrt{4R^2 + (l - \pi R)^2}$.

Trong trường hợp $l \geqslant \pi R$, điểm bắt đầu $L = 2R$ đã hoàn thành phạm vi phát hiện tối đa. Chúng ta hãy tìm xem theo hướng nào $l = l_0$ các máy bay sẽ vẫn nằm trong tầm nhìn sau khi rẽ, tức là khi

$$L^2 = 4R^2 + (l_0 - \pi R)^2 = l_0^2.$$

Giải phương trình này cho $l_0$, ta thu được

$$l_0 = \frac{4 + \pi^2}{2\pi} R = \frac{4 + \pi^2}{2\pi} \frac{v^2}{a}.$$

Vì vậy, ở $l \geqslant l_0$ các máy bay không tiêu diệt nhau ngoài tầm nhìn. Trong trường hợp ngược lại ($l < l_0$), sau khi quay lại, chúng nằm ngoài phạm vi phát hiện.

I. I. Chim sẻ

*) Ví dụ, xem bài viết của M. Shubin “Cấu trúc liên kết và địa hình” («Kvant», 1982, số 8, trang 14).

⟦folio 44⟧

F909. Có hai quả bóng nằm trên một đường trượt không trọng lượng được tạo thành bởi hai mặt phẳng chính, mỗi mặt phẳng tạo một góc α với mặt phẳng nằm ngang (xem hình). Bàn trượt có thể trượt dọc theo mặt phẳng nằm ngang mà không có hình tam giác. Quả bóng phía trên có khối lượng là m₁ được thả ra. Trong những điều kiện nào thì quả bóng phía dưới có khối lượng m₂ bắt đầu “leo” lên đồi?

Rõ ràng là nếu quả bóng thứ hai đủ nhẹ thì nó sẽ bắt đầu leo ​​lên đồi. Hãy tìm khối lượng giới hạn m₀² của nó, tại đó nó chưa bắt đầu nâng lên nhưng đã ngừng ép mặt phẳng nghiêng bên phải.

Vì cầu trượt không có trọng lượng nên trong trường hợp này tổng hình chiếu theo phương ngang của các lực áp tác dụng lên cầu trượt từ phía các quả bóng phải bằng 0. Điều này có nghĩa là (xem hình)

$$N_1 \sin \alpha = N_2 \sin \alpha,$$

Ngoài ra, do quả bóng thứ hai không bay lên nên hình chiếu gia tốc của các quả bóng trên mặt phẳng nghiêng vuông góc với mặt phẳng nghiêng phải bằng hình chiếu của gia tốc của vật trượt theo hướng này). Như có thể thấy từ hình, góc giữa lực N₂ và mặt phẳng nghiêng phải là 90°—2α, và do đó điều kiện cuối cùng có thể được viết dưới dạng

$$\frac{m_1 g \cos \alpha - N_1}{m_1} = \frac{m_2^0 g \cos \alpha - N_2 \cos 2\alpha}{m_2^0}.$$

Từ đây là:

$$m_2^0 = m_1 \cos 2\alpha.$$

Như vậy, quả bóng phía dưới sẽ “leo” lên cầu trượt nếu điều kiện m₂ < m₁ cos 2α được đáp ứng.

A. I. Buzdin

F910. Một vòng cao su phát triển đều có khối lượng m được gắn vào một hình trụ có bán kính R. Chiều dài của vòng ở trạng thái không giãn bằng πR thì diện tích của miếng cao su là k. Hình trụ bắt đầu quay với gia tốc góc không đổi β. Sau bao lâu thì vòng bắt đầu trượt so với hình trụ nếu hệ số ma sát giữa vòng và hình trụ là μ? Vận tốc góc của vòng sẽ là bao nhiêu?

Xét một phần tử vòng nhỏ có thể nhìn thấy được từ tâm vòng ở góc Δα (xem hình).

Khối lượng của phần tử này là Δm = $\frac{m}{2\pi} \cdot \Delta\alpha$. Nó chịu tác dụng của các lực $\vec{N}$ của phản lực pháp tuyến từ phía bên của hình trụ, lực ma sát Fτ và lực căng từ các phần lân cận của vòng (chúng ta bỏ qua lực hấp dẫn). Vì vòng phát triển đồng đều nên lực căng có giá trị tuyệt đối như nhau và bằng T=kπ(2R-R)=kπR. Lực bằng nhau của tất cả các lực này tạo cho phần tử vòng một gia tốc $\vec{a}$. Hình chiếu $\vec{a}$ theo hướng xuyên tâm là gia tốc hướng tâm a₁(t) tại một thời điểm nhất định và hình chiếu $\vec{a}$ theo hướng tiếp tuyến với hình trụ là gia tốc tiếp tuyến a₇(t) tại một thời điểm nhất định. Vì vận tốc tuyến tính v(t) có liên hệ với vận tốc góc ω(t) bởi sự tương ứng v(t)=ω(t) R=βRt (t=0 là điểm bắt đầu quay),

$$a_1(t) = \frac{(v(t))^2}{R} = \beta^2 Rt^2,$$

$$a_7(t) = (v(t))' = \beta R.$$

Cho vòng trượt bắt đầu trượt ở thời điểm t sau khi bắt đầu quay. Theo định luật II Newton, với 0 < t < τ

$$2T \cdot \frac{\Delta\alpha}{2} - N(t) = \Delta m \cdot a_1(t) = \frac{m}{2\pi} \cdot \Delta\alpha \cdot \beta^2 Rt^2,$$

(1)

$$F_{τp} = \Delta m \cdot a_7(t) = \frac{m}{2\pi} \cdot \Delta\alpha \cdot \beta R$$

(2)

⟦folio none⟧

(chúng tôi đã dạy rằng $\Delta \alpha$ ít nhấn mạnh điều đó $\sin \frac{\Delta a}{2} \approx \frac{\Delta a}{2}$).

Tất cả thời gian này $F_{\text{tp}}$ là cường độ ma sát khi đứng yên. Khi tốc độ tăng, lực $N(t)$ giảm. Sự tuân thủ làm giảm giá trị tối đa $\mu \cdot N(t)$ của lực ma sát tĩnh; tại thời điểm $\tau$ nó sẽ bằng giá trị $F_{\text{tp}} = \Delta m \cdot \beta R$ - việc chia tỷ lệ sẽ bắt đầu.

Thay $t = \tau$ và $F_{\text{tp}} = \mu \cdot N(\tau)$ vào (1) và (2), ta tìm được giá trị của $\tau$:

$$\tau = \sqrt{\left(\frac{2\mu k\pi^2}{m} - \beta\right)/\mu\beta^2}.$$

A. A. Lapides

F911. hình hiển thị biểu đồ thay đổi áp suất của khí bột trong vô lăng khi viên đạn di chuyển vào vô lăng. Xác định tốc độ của thuốc súng (tính bằng kk/s) ở áp suất $p_{\text{max}}$, nếu tốc độ của viên đạn lúc này là $v$. Diện tích ngang của giây là vết thương s. Nhiệt độ của khí bột được coi là không đổi. Được biết, khí bột tạo thành khối thuốc súng M khi tăng tốc, tạo ra áp suất $p_0$ trong thể tích $V_0$.

Sự thay đổi áp suất của khí bột trong bảng xảy ra do sự thay đổi khối lượng của thuốc nổ và do sự thay đổi thể tích mà khí chiếm giữ khi viên đạn di chuyển. Vì lý do thứ nhất, áp suất phải tăng, lý do thứ hai là giảm. Như có thể thấy từ hình, xu hướng đầu tiên chiếm ưu thế trong phần 1–2 và xu hướng thứ hai chiếm ưu thế trong phần 2–3. Tại thời điểm $\tau$, khi áp suất là $p_{\text{max}}$, áp suất tăng do thuốc súng mài mòn sẽ bù đắp cho áp suất tăng do đạn tiến lên.

Hãy viết phương trình trạng thái của các chất khí tại thời điểm $\tau$, khi áp suất của chúng bằng $p_{\text{max}}$:

$$p_{\text{max}} V = \frac{m}{\mu} RT,$$

trong đó $m$ là khối lượng thuốc súng đã được sử dụng hết cho đến thời điểm này, $V$ là thể tích không gian trên mỗi viên đạn. Để khối lượng thuốc súng $\Delta m$ tích tụ trong một khoảng thời gian ngắn $\Delta t$, trong thời gian đó áp suất có thể coi là không đổi và bằng $p_{\text{max}}$. Thể tích không gian hồ bơi trong thời gian này đã tăng thêm $\Delta V_1 = vs \cdot \Delta t$

(Δτ ít nhấn mạnh rằng tốc độ của viên đạn $v$ có thể coi là không đổi). Áp suất khí không thay đổi trong thời gian $\Delta t$; điều này có nghĩa là khí hình thành khi khối lượng $\Delta m$ của thuốc súng giảm đi, ở áp suất $p_{\text{max}}$ chiếm chính xác thể tích $\Delta V_1$, tức là

$$p_{\text{max}} \cdot \Delta V_1 = \frac{\Delta m}{\mu} RT,$$ hoặc $p_{\text{max}} vs \cdot \Delta t = \frac{\Delta m}{\mu} RT$.

Từ đẳng thức cuối cùng ta tìm được áp suất $\tau$:

$$\frac{\Delta m}{\Delta t} = p_{\text{max}} vs \cdot \frac{\mu}{RT}$$

Từ điều kiện bài toán người ta biết rằng $p_0 V_0 = \frac{M}{\mu} RT$. Từ đó chúng ta tìm thấy $\frac{RT}{\mu} = \frac{p_0 V_0}{M}$, và cuối cùng chúng ta nhận được

$$\frac{\Delta m}{\Delta t} = \frac{M p_{\text{max}} sv}{p_0 V_0}$$

L. G. Markovich
