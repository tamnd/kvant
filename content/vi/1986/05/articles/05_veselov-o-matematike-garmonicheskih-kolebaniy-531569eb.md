---
id: 1986-5-veselov-o-matematike-garmonicheskih-kolebaniy-531569eb
issue: kvant_1986_5
year: 1986
number: "5"
title: Về toán học của dao động điều hòa
authors:
  - Веселов А. П.
rubric: raznoe
page_first: 11
page_last: 15
page_labels: 9-13
tag: MBOG
lang: vi
source: kvant_digital
extraction: vision
content_sha256: ee3a87b761d0e8225d15c4216be5500daea3f4fd00a12efb951ea3b4b95ad098
prompt_sha256: draft-1
translated_from: content/ru/1986/05/articles/05_veselov-o-matematike-garmonicheskih-kolebaniy-531569eb.md
source_content_sha256: fd89bae33704b5286362fdc625a10065e1cb0886f9c67f048c71e95c2ed6ac8e
translation_model: draft
translation_run: vi-draft-2026-10-31
translation_quality: draft
---

⟦folio 9⟧

Về toán học của dao động điều hòa

Ứng viên Khoa học Vật lý và Toán học
A. P. VESELOV

Theo nhà vật lý lý thuyết, dao động và sóng là phương tiện chính để hiểu thế giới thực. Mọi thứ đều có thể dao động - mọi đồ vật, chất khí; ánh sáng, âm thanh, xung thần kinh suy cho cùng đều là các loại rung động.

Viện sĩ S. P. Novikov

Đồng hồ mềm, sóng biển, dao động, sự thay đổi ngày và đêm, sự thay đổi theo mùa trong tự nhiên - mỗi bạn có thể thêm vào danh sách này nhiều ví dụ khác về hiện tượng dao động. Giống như nhiều quá trình tiến hóa *), chúng có thể được mô tả bằng ngôn ngữ toán học của các phương trình vi phân. Môi trường của các phương trình vi phân mô tả dao động của cái này hay cái kia

*)Cm. bài viết của V.I. Arnold ở «Kvant» số 2 năm nay.

Trong một hệ khác, đơn giản nhất (và do đó quan trọng nhất) là phương trình của bộ dao động tuyến tính (từ tiếng Latin oscillatio - dao động) (hoặc bộ dao động điều hòa, hoặc dao động điều hòa, hoặc dao động nhỏ của ma trận):

$$\ddot{x} + \omega^2 x = 0.$$

Ở đây $\ddot{x}$ biểu thị tích thứ hai $\ddot{x} = x''(t)$ theo thời gian $t$ của hàm $x = x(t)$, mô tả độ lệch của hệ so với vị trí cân bằng và $\omega^2$ là một tham số nào đó (tất nhiên là dương).

Ở đây chúng ta sẽ mổ xẻ ở đâu và bằng cách nào thu được phương trình của bộ dao động tuyến tính - mặc dù học sinh lớp 10 đã biết về điều này từ khóa học vật lý (Vật lý 10, đoạn 4) - và sau đó chúng ta sẽ nghiên cứu nó từ quan điểm toán học.

Phương trình dao động tuyến tính xuất hiện ở đâu?

Bất cứ nơi nào phương trình này xuất hiện! Thẩm phán cho chính mình.

1. Các dao động nhỏ của ma trận. Cho một vật có khối lượng nhỏ $m$ được treo trên một sợi dây mỏng không dãn có chiều dài $l$, kích thước của nó (a là

⟦folio 10⟧

phản ứng và lực cản của không khí) có thể bỏ qua. Một hệ thống như vậy được gọi là ma trận toán học. Chúng ta hãy xem xét sự dao động của nó đối với những sai lệch nhỏ của sợi so với phương thẳng đứng, tức là nhỏ α (hình 1). Chúng ta ký hiệu x là độ dài của cung BA: x=lα (α là giá trị của góc BOA tính bằng radian). Sau đó, phân tích trọng lực và P=mg thành hai thành phần T và F (xem hình 1), ta thấy giá trị của F bằng mgsin α và phương trình chuyển động theo định luật Newton cho

$$m l \ddot{\alpha} = - mg \sin \alpha,$$

hoặc

$$\ddot{\alpha} = - \frac{g}{l} \sin \alpha.$$

Chúng ta thu được một phương trình (phi tuyến tính) liên quan đến độ lệch α=α(t). Bây giờ chúng ta lợi dụng độ nhỏ của α, giới hạn lim (sin α/α)=1 và thay sin α ở vế phải bằng α, nghĩa là chúng ta tiến hành tuyến tính hóa. Kết quả là chúng ta thu được một phương trình (tuyến tính) có dạng (*) với ω=\sqrt{g/l}.

2. Cơ thể bên ngoài (hình 2). Khi lệch khỏi vị trí cân bằng một x nhất định, vật chịu, theo định luật Hooke, một lực F = -kx từ phía lò xo, trong đó k là đại lượng gọi là độ cứng của lò xo. Phương trình chuyển động trùng với (*) tại ω=\sqrt{k/m}. Tất nhiên, ở đây cũng vậy, biểu thức lực (và do đó phương trình (*)) sẽ chỉ chính xác đối với những sai lệch không quá lớn so với vị trí cân bằng.

3. Một mạch dao động (hình 3), gồm một tụ điện có điện dung C và độ tự cảm L. Điện tích của tụ q thay đổi khi không có điện trở tác dụng theo định luật L\ddot{q}+\frac{1}{C}q=0 (“Vật lý 10”, đoạn 15), tương ứng với phương trình (*) cho ω=1/\sqrt{LC}.

4. Tàu thông tin liên lạc. Nếu trong một ống có hình chữ U (hình 4), mức chất lỏng (ví dụ: thủy ngân) lệch một lượng nhất định so với vị trí cân bằng, thì chất lỏng bắt đầu luân phiên tăng (và giảm) ở mỗi đoạn thẳng đứng của ống. Nếu độ lệch ban đầu nhỏ (như trường hợp này) thì độ lệch x=x(t) của mực chất lỏng tuân theo phương trình (*).

5. Tỷ trọng kế (hình 5). Nếu thiết bị này, dùng để đo mật độ của chất lỏng, hơi lệch về độ sâu so với vị trí cân bằng, thì do định luật Archimedes, nó bắt đầu dao động lên trên và ra ngoài. Những dao động này cũng được mô tả khá chính xác bằng phương trình (*) (trong mọi trường hợp, cho đến khi quá trình đào tạo bắt đầu diễn ra).

Điều khiển (dành cho những người yêu thích vật lý). Tìm đạo hàm của phương trình (*) cho ví dụ áp chót (4), biểu thị ω dưới dạng các tham số phù hợp.

Tất cả các ví dụ trên có điểm gì chung? Trạng thái của hệ được mô tả bởi một tham số x, tham số này thay đổi xung quanh vị trí cân bằng của nó x=0; trên hệ tác dụng, lực F(x) chỉ phụ thuộc vào tham số x. Bỏ qua thế năng, tham số biến thiên theo định luật II Newton có dạng $\ddot{x}=F(x)$. Trong trường hợp này, F(0)=0, vì x=0 là vị trí cân bằng. Nếu hàm F(x) có

⟦folio 11⟧

CÓ MỘT ĐẠO TỨC KHÔNG 0 TẠI 0: $F'(0) = \lim_{x \to 0} (F(x)/x) = a$, thì đối với $x$ nhỏ chúng ta có thể thay thế vế phải của $(F(x))$ bằng $ax$. Trong trường hợp này, $a$ phải âm, nếu không thì không thể có dao động nào ở gần số 0! Do đó, chúng ta đi đến phương trình tuyến tính (*), trong đó $\omega = \sqrt{-a} = \sqrt{-F'(0)}$.

Tất nhiên, quy trình tuyến tính hóa đã chỉ định sẽ dẫn đến một phương trình vi phân không tương đương, tuy nhiên phương trình này mô tả chính xác bức tranh định tính của chuyển động hướng tới vị trí cân bằng. Điều này bị ràng buộc phổ biến bởi phương trình dao động tuyến tính (*), cũng như tên của nó.

Sự tồn tại và duy nhất lời giải

Có thể dễ dàng kiểm tra rằng phương trình (*) thỏa mãn các hàm $x = \cos \omega t$ và $x = \sin \omega t$, và do đó các tổ hợp tuyến tính của chúng, tức là các biểu thức có dạng

$$x(t) = a \cos \omega t + b \sin \omega t$$

(hãy kiểm tra xem!) *. Hãy chứng minh rằng phương trình này không có lời giải nào khác.

Ta lợi dụng rằng trong quá trình chuyển động các đại lượng sau được bảo toàn

$$E = \frac{1}{2} (\dot{x}^2 + \omega^2 x^2) = \text{const}$$

(định luật bảo toàn năng lượng).

Thật vậy, $\dot{E} = \dot{x} \dot{x} + \omega^2 x \dot{x} = \dot{x} (\dot{x} + \omega^2 \dot{x}) = 0$, ngụ ý rằng $E = \text{const}$.

Bây giờ chúng ta hãy xem xét tích của phương trình (*): $x = x_1(t)$ và dữ liệu ban đầu của nó $a = x_1(0)$ và $\beta = \dot{x}_1(0)$. Chúng ta hãy chọn các hệ số $a$ và $b$ trong biểu thức $x_2 = a \cos \omega t + b \sin \omega t$ sao cho $x_2(0) = a$, $x_2(0) = \beta$. Để làm điều này, chỉ cần đặt $a = a$, $b = \beta/\omega$. Bây giờ chúng ta hãy tạo ra sự khác biệt $x(t) = x_1(t) - x_2(t)$, đây sẽ là giải pháp cho (*) (đánh dấu vào phần này). Dữ liệu ban đầu của nó sẽ bằng 0: $x(0) = \dot{x}(0) = 0$. Do định luật bảo toàn năng lượng

$$E = \frac{1}{2} (\dot{x}^2 + \omega^2 x^2) = \frac{1}{2} (\dot{x}^2(0) + \omega^2 x^2(0)) = 0,$$

$\dot{x}(t) \equiv x(t) \equiv 0$ đến từ đâu, tức là

$$x_1(t) \equiv x_2(t) \equiv \alpha \cos \omega t + \frac{\beta}{\omega} \sin \omega t.$$

Chúng tôi đã chỉ ra rằng mọi lời giải $x_1(t)$ đều có dạng (**), trong đó $a$ và $b$ được xác định duy nhất bởi dữ liệu ban đầu: Trong quá trình chứng minh, chúng tôi cũng thu được công thức cho lời giải thông qua dữ liệu ban đầu.

Chạy theo vòng tròn trên mặt phẳng pha

Chúng ta hãy chú ý đến những trường hợp đáng ngạc nhiên sau đây. Trong phương trình hoàn hảo (*), số $n$ bất ngờ bị ẩn, mặc dù không có đề cập đến bất kỳ vòng tròn nào trong câu lệnh bài toán. Trên thực tế, tất cả các phương trình lời giải (*) (ngoại trừ $x(t) \equiv 0$) hóa ra là hàm tuần hoàn của thời gian và tích chu kỳ của chúng với $\omega$ bằng $2\pi$. Vì số $n$ đã xuất hiện nên chúng ta hãy thử tìm một hình tròn.

Tìm nó ở đâu? Chúng ta sẽ tìm nó trên mặt phẳng pha, tức là trên mặt phẳng có tọa độ $(u; v)$, trong đó $u = x$, $v = \dot{x}$. Các điểm $(u; v)$ của mặt phẳng này được gọi là điểm pha; chúng mô tả trạng thái của hệ: tọa độ $u = x$ biểu thị độ lệch của hệ so với vị trí cân bằng và tọa độ $v = \dot{x}$ biểu thị tốc độ chuyển động của nó tại một thời điểm nhất định. Theo thời gian, vị trí của điểm pha $(u; v) = (x(t); \dot{x}(t))$ thay đổi và nó mô tả một đường nhất định trên mặt phẳng pha, được gọi là quỹ đạo pha. Cái nào?

⟦folio 12⟧

Người đọc nhanh trí có lẽ đã nghĩ - đó không phải là một vòng tròn sao?

Chúng ta đừng đi trước mọi thứ. Cho đến nay chúng ta chỉ có một hình elip - đường mức năng lượng $E = \text{const}$, tức là đường

$$\omega^2 u^2 + v^2 = 2E$$

(1)

(chúng tôi nhân với hai để không bận tâm đến các phân số không cần thiết), được hiển thị trên hình 6. Do định luật bảo toàn năng lượng, điểm pha $N(t) = (x(t); \dot{x}(t))$, tại thời điểm $t$ có ​​năng lượng $E$, sẽ luôn nằm trên hình elip (1), tức là nó sẽ di chuyển dọc theo hình elip.

Chúng ta hãy dựng một đường tròn trên trục hoành của nó làm đường kính và vẽ một đường thẳng đi qua điểm pha $N(t)$, song song với trục $Ov$, cho đến khi nó cắt đường tròn tại điểm $M(t)$. Khi đó tọa độ dọc theo trục $x$ của điểm $N(t)$ sẽ trùng với tọa độ dọc theo trục $x$ của điểm $M(t)$, tức là sẽ bằng $x(t)$.

Chúng ta hãy biến đổi biểu thức (**) cho $x(t)$, dẫn đến công thức cho một đối số bổ sung:

$$x(t) = a \cos \omega t + b \sin \omega t = \sqrt{a^2 + b^2} \cos(\omega t + \varphi),$$

trong đó $\varphi$ được xác định từ điều kiện

$$\cos \varphi = \frac{a}{\sqrt{a^2 + b^2}}, \sin \varphi = \frac{-b}{\sqrt{a^2 + b^2}}.$$

Bằng cách ký hiệu $A = \sqrt{a^2 + b^2}$, chúng ta có thể thấy rằng $A = \sqrt{a^2 + b^2} = \sqrt{a^2 + \beta^2/\omega^2} = \frac{1}{\omega} \sqrt{\beta^2 + \omega^2 a^2} = \frac{1}{\omega} \sqrt{\dot{x}^2(0) + \omega^2 x^2(0)} = \sqrt{2E/\omega}$.

Do đó $x(t)$ có thể được viết là

$$x(t) = \frac{2E}{\omega} \cos(\omega t + \varphi).$$

Giá trị $A = \sqrt{2E/\omega}$, đặc trưng cho

dao động điều hòa cực đại được gọi là biên độ, $\omega$ - tần số tuần hoàn, $T = 2\pi/\omega$ - chu kỳ, $\varphi$ - pha.

Bây giờ thật dễ dàng để xác định rằng điểm $M(t)$ sẽ quay đều với vận tốc góc $\omega$ xung quanh một đường tròn có tâm $O$ bán kính $A$. Thật vậy, nếu $\varphi$ biểu thị góc $uOM$ tại thời điểm $t=0$, thì góc $uOM(t)$ bằng $\omega t + \varphi$ do hình chiếu lên trục $Ou$ của điểm $M(t)$ được tính theo công thức (4). Chúng ta đã chứng minh rằng dao động điều hòa là hình chiếu lên một đường thẳng quay đều trong một đường tròn, bán kính của đường đó bằng biên độ dao động và vận tốc góc quay bằng tần số tuần hoàn.

Độ trơn tương đương là dao động điều hòa là một trong các tọa độ của vectơ quay đều (trong trường hợp này là $-\vec{OM}$). Độ dài của vectơ này trùng với biên độ và vị trí ban đầu được xác định theo pha. Biểu diễn rung động này được gọi là sơ đồ vectơ của nó và thường hữu ích. Hãy thử sử dụng nó để giải quyết bài toán sau.

Bài tập 1. Chứng minh rằng tổng của hai dao động điều hòa khác 0 là dao động điều hòa khi và chỉ khi chúng có cùng tần số (hoặc như người ta nói, tọa độ dọc theo trục $x$ của điểm $M(t)$, tức là sẽ bằng $x(t)$).

Bài 2. Chứng minh rằng tổng của ba dao động điều hòa cùng biên độ, tần số có pha $\varphi$, $\varphi + (2\pi/3)$ và $\varphi + (4\pi/3)$ bằng 0.

Trường hợp thứ hai đóng một vai trò quan trọng khi sử dụng dòng điện ba pha, vì chính những dao động như vậy mà máy phát điện xoay chiều ba pha tạo ra. Nhân tiện, trên sơ đồ vectơ, bạn sẽ tìm thấy những lý do chung cho các hướng tiêu chuẩn liên quan

⟦folio 13⟧

Zhenya 220 volt và 127 volt xấp xỉ bằng $\sqrt{3}$.

Bài 3. Phương trình có bao nhiêu nghiệm trên đoạn [0, 2]

$$\cos x + \frac{1}{2} \cos(x+a_1) + \frac{1}{4} \cos(x+a_2) + \dots + \frac{1}{2^n} \cos(x+a_n) = 0$$

($a_1, \dots, a_n$ là các tham số tùy ý)?

Kết quả nghiên cứu của chúng tôi về phương trình (*) là hình 7. Các nhà toán học hình như vậy gọi là chân dung pha hoặc sơ đồ pha của phương trình vi phân. Sơ đồ của chúng tôi cho thấy rằng mỗi điểm pha có hình elip riêng (tương ứng với mức năng lượng của nó), trong khi độ lệch so với vị trí cân bằng $x(t)$ thay đổi định kỳ, cũng như tốc độ $\dot{x}(t)$, đạt giá trị tối đa ở vị trí cân bằng. Chúng ta hãy chú ý đến tính chất đáng chú ý sau đây của một bộ dao động điều hòa: chu kì dao động của nó không phụ thuộc vào biên độ! Thuộc tính này là đặc biệt, có thể thấy trong ví dụ về ma trận toán học mà chúng ta sẽ tiếp tục.

Về toán học của ma trận toán học

Chúng ta hãy tập trung vào lý thuyết ma trận toán học, bây giờ từ bỏ giả định về các dao động nhỏ (nhưng vẫn giả sử rằng không có ma sát). Chúng ta đã biết phương trình chuyển động trong trường hợp này:

$$\ddot{x} + \omega^2 \sin x = 0.$$

Mặc dù dạng phương trình (*) không khác lắm so với phương trình (*) của bộ dao động tuyến tính, nhưng nó không còn tuyến tính nữa và việc giải nó không hề dễ dàng chút nào. Hơn nữa, nhìn chung không thể viết nó lời giải bằng cách sử dụng các hàm đã biết ở trường; điều này đòi hỏi các hàm đặc biệt gọi là hàm elip. Tôi nên làm gì?

Bạn có thể hình dung về phương trình lời giải (*) và hoạt động của ma trận toán học bằng cách sử dụng chân dung pha của nó (hình 8), được xây dựng bằng định luật bảo toàn năng lượng. Chúng ta hãy nhìn vào bức chân dung này.

Khi các điểm in đậm trên trục $Ox$ tương ứng với các vị trí cân bằng - ổn định (gốc tọa độ) và không ổn định

Hình 8.

(điểm $A$ ($\pi; 0$)), tức là vị trí thấp nhất và cao nhất của ma trận. Các hình bầu dục mở rộng gần điểm $O$ của trạng thái cân bằng ổn định tương ứng với các chế độ dao động ma trận khác nhau (với các biên độ khác nhau); gần điểm $O$ chúng không khác biệt về mặt thị giác so với các hình elip - quỹ đạo pha của phương trình (*)). Việc đi quanh một hình bầu dục (lớn hay nhỏ) như vậy phản ánh toàn bộ dao động của ma trận, giao điểm của nó với trục $Ox$ là đoạn đi qua vị trí cân bằng nguồn với tốc độ cực đại, giao điểm với trục $Ox$ là độ lệch cực trị của ma trận (tốc độ bằng 0). Các quỹ đạo lượn sóng ở phần dưới và phần trên của hình là biểu thức không đồng đều của ma trận, khi nhận ra lực đẩy thêm của hiện tại, có nghĩa là matnik đạt đến vị trí cân bằng trên với tốc độ khác 0, bỏ qua nó và tiếp tục quay, đạt các giá trị tốc độ cực cao khi đi qua vị trí cân bằng. Các quỹ đạo phân tách chuyển động dao động khỏi chuyển động quay được thể hiện bằng màu đỏ. Các quỹ đạo này tương ứng với chuyển động có mức năng lượng $E_0$ bằng thế năng của ma trận ở vị trí cân bằng trên (không ổn định) $A(\pi; 0)$. Với chuyển động này, ma trận đi qua vị trí cân bằng dưới $B(0; v_0)$ với tốc độ tối đa $v_0 = \sqrt{2E_0/m}$ và giảm dần tốc độ, tiến đến vị trí cân bằng trên; người ta có thể chứng minh rằng nó chỉ đạt tới (với tốc độ không phải bên trái) trong một khoảng thời gian vô hạn.

Phần kết luận

Chúng ta đã tìm hiểu một chút về các tính chất của bộ dao động tuyến tính và phi tuyến. Xin vui lòng, điều tuyệt vời nhất về bộ dao động là các yêu cầu đa logic và phổ quát của nó: thật khó để liệt kê tất cả những hệ thống vật lý đơn giản và đa dạng được mô tả bằng các phương trình (*) và (****). Bộ dao động là một phần của nhiều hệ thống. Ví dụ,

(Cuối cùng xem trang 43)
