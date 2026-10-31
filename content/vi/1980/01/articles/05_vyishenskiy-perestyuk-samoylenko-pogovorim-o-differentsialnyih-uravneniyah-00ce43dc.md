---
id: 1980-1-vyishenskiy-perestyuk-samoylenko-pogovorim-o-differentsialnyih-uravneniyah-00ce43dc
issue: kvant_1980_1
year: 1980
number: "1"
title: Hãy nói về phương trình vi phân
authors:
  - Вышенский В. А.
  - Перестюк Н. А.
  - Самойленко А. М.
rubric: osnovnye-stati
page_first: 12
page_last: 16
page_labels: 10-14
tag: WSJ1
lang: vi
source: kvant_digital
extraction: vision
content_sha256: dac0e7a0088ba0147234c1a3400b22ddde3c4c335fdc3bed8ab970528d6852f6
prompt_sha256: draft-1
translated_from: content/ru/1980/01/articles/05_vyishenskiy-perestyuk-samoylenko-pogovorim-o-differentsialnyih-uravneniyah-00ce43dc.md
source_content_sha256: f985762ec236d5b2cecd90e2c7ee7fdc38aadb691a1f9eed88c22b652b1ad899
translation_model: draft
translation_run: vi-draft-2026-10-31
translation_quality: draft
---

⟦folio 10⟧

Hãy nói về phương trình vi phân

Nếu trong các phương trình thông thường được giải ở trường, bạn cần tìm các giá trị số của một biến nhất định, thì trong phương trình vi phân, hàm cần tìm là hàm bắt buộc và phương trình bao gồm tích của hàm này. Bạn đã quen thuộc với các phương trình vi phân đơn giản trong sách giáo khoa ở trường. Đây là phương trình tăng trưởng (hoặc phân rã) theo cấp số nhân

$$y' = ky,$$

(1)

trong đó $y = y(x)$ là hàm chưa biết, $k \neq 0$ là hằng số cho trước (“Đại số và các phần tử phân tích 10”, trang 110) và phương trình dao động điều hòa

$$y'' = -\omega^2 y,$$

(2)

trong đó $y$ lại là một hàm chưa biết, $\omega > 0$ là một hằng số (ibid., đoạn 80).

Trong các lĩnh vực hoạt động khác nhau của con người, bài toán phát sinh, gắn liền với một phương trình vi phân. Bản chất của bài toán này và phương pháp của lời giải của chúng có thể được mô tả giống như thế này. Chúng tôi đang nghiên cứu một số quá trình - vật lý, sinh học, v.v. Chúng tôi quan tâm đến sự thay đổi theo thời gian của một số đặc tính của quá trình này, tức là một đại lượng nhất định (nhiệt độ, áp suất, khối lượng, v.v.). Nếu chúng ta có nhiều thông tin về diễn biến của quá trình này, chúng ta có thể cố gắng xây dựng một mô hình toán học về nó. Trong nhiều trường hợp, không thể thu được thông tin về tốc độ thay đổi của đại lượng $y = y(t)$ tùy theo thời gian $t$, tức là về đạo hàm $y' = y'(t)$, từ dữ liệu thực nghiệm hoặc từ vật lý và các định luật khác. Thông tin này thường có thể được viết dưới dạng phương trình vi phân với hàm chưa xác định $y = y(t)$. Phương trình thu được mô tả chính xác quá trình của chúng tôi theo quan điểm về đặc tính $y$ của nó. Sau khi quét tất cả lời giải của phương trình vi phân - bản thân nó đã là một bài toán toán học thuần túy, chúng tôi tìm thấy tất cả các tùy chọn có thể có để thay đổi giá trị $y$.

Lưu ý rằng trong một mô tả toán học (mô tả như vậy được gọi là mô hình), người ta luôn phải đưa ra một số đề xuất đơn giản hóa, tránh các tác dụng phụ nhất định, chấp nhận các điều kiện “lý tưởng” - tóm lại là trừu tượng từ các chi tiết cụ thể. Điều này dẫn đến những hạn chế đã biết trong việc áp dụng mô hình đã xây dựng.

Kinh nghiệm phát triển của các ngành khoa học khác nhau cho thấy nhiều dữ liệu lẫn nhau về nội dung của bài toán dẫn đến các phương trình vi phân giống nhau hoặc tương tự nhau. Do đó, việc phát triển các phương pháp lời giải cho các phương trình như vậy là điều tự nhiên bất kể các vấn đề được đưa ra hoặc có thể dẫn đến chúng. Đây chính xác là điều mà lý thuyết toán học về phương trình vi phân giải quyết.

Nếu bất kỳ bài toán nào được kết nối với một phương trình vi phân có phương pháp lời giải đã được biết, thì bài toán này có thể được coi là giải được. Trong trường hợp này, phần sáng tạo lời giải kết thúc bằng việc biên soạn một phương trình vi phân, trong khi giai đoạn thứ hai - quét lời giải của phương trình - sẽ là, mặc dù quan trọng nhưng thuần túy là kỹ thuật bài toán. Ở đây có sự tương tự hoàn toàn với các bài toán liên quan đến phương trình đại số tổng quát.

Trong bài viết này, chúng tôi sẽ minh họa những gì đã được nói bằng ví dụ bài toán, liên quan đến phương trình vi phân (1) và (2) ở trường

⟦folio 11⟧

khóa học. Hãy bắt đầu với việc điền vào
này.

1. Vi sai tuyến tính
phương trình

Phương trình $y' = ky$ được gọi là tuyến tính-
nom vì chức năng chưa được biết
$y$ và sản phẩm của nó $y'$ được bao gồm trong đó
cách tuyến tính. Như đã biết từ
sách giáo khoa, bất kỳ lời giải nào của phương trình này
Ý kiến ​​được viết dưới dạng

$$y = Ae^{kx},$$

(3)

trong đó $A$ là hằng số tùy ý.

Hóa ra nếu trên tọa độ
trên mặt phẳng để vẽ đồ thị
những lời giải này trong tất cả những gì có thể
giá trị $A$, thì chúng sẽ bao phủ toàn bộ
mặt phẳng và qua mỗi mặt phẳng
điểm mặt phẳng sẽ đi qua chính xác
một trong những đồ thị. Mặt phẳng của mắt là
được gọi như thể được dệt từ than chì
fikov $y = Ae^{kx}$ (Hình 1).

Hãy chứng minh điều đó, tại sao lại tìm thấy nó
trong số các hàm có dạng (3) tất cả những hàm đó
fic của ai xuyên suốt chuyện này
điểm $(x_0; y_0)$ của mặt phẳng tọa độ. Để xác định hằng số $A$ ta thu được phương trình

$$Ae^{kx_0} = y_0,$$

có một lời giải
$A = y_0e^{-kx_0}$. Do đó, một và chỉ một trong các đồ thị (3) đi qua điểm của chúng ta - đây là

$$y = \left(y_0e^{-kx_0}\right) \cdot e^{kx} = y_0e^{k(x-x_0)}.$$

(4)

Thực tế là chúng tôi thường xuyên nhận được
công thức như sau:
phương trình vi phân $y' = ky$ có duy nhất lời giải thỏa mãn y ban đầu

Cơm. 1.

điều kiện $y(x_0) = y_0$; đây là lời giải
được cho bởi công thức (4).

Vi phân tuyến tính tổng quát hơn
phương trình cial được viết dưới dạng

$$y' = ky + a,$$

(5)

trong đó $a$ (như $k$) là một hằng số. phương trình.
(5) dễ dàng trùng khớp với đã được sử dụng
phương trình sau (1): nếu
bên phải được viết là

$$ky + a = k\left(y + \frac{a}{k}\right)$$

(hãy nhớ rằng chúng ta xét $k \neq 0$) và biểu thị hàm $y + a/k$ bằng $z$, sau đó

$$z' = \left(y + \frac{a}{k}\right)' = y' = ky + a = kz.$$

Như vậy hàm số $z(x) = y(x) + a/k$ thỏa mãn phương trình
nyu $z' = kz$, do đó $z = Ae^{kx}$, tức là $y + a/k = Ae^{kx}$, từ đâu đến

$$y(x) = -\frac{a}{k} + Ae^{kx}.$$

Giá trị của hằng số $A$ lại là
được xác định duy nhất nếu
điều kiện ban đầu $y(x_0) = y_0$ được đưa ra.

Về bản chất, đây là toàn bộ lý thuyết toán học của các phương trình vi phân tuyến tính bậc nhất, tức là các phương trình, chỉ bao gồm hàm tùy ý đầu tiên của một hàm chưa biết.

2. Ứng dụng tuyến tính
phương trình vi phân

Thảo luận trong sách giáo khoa ở trường
một số quy trình được nghiên cứu bởi
tính chất của vi phân tuyến tính
phương trình cơ bản, nghĩa là, theo nguyên lý
thay đổi lý thuyết đã nêu ở đoạn 1.
Đây là các quá trình phân tán phóng xạ
pada, dân số posta và sự trao đổi chất của cơ thể. Chúng ta sẽ xem xét thêm ba ví dụ từ các lĩnh vực khoa học khác.
Hãy để chúng tôi nhắc nhở bạn rằng điều quan trọng nhất đối với chúng tôi là
giảm bài toán thành một phương trình vi phân.

(A) Mô hình tăng trưởng dân số
của vi khuẩn. Gọi $N(t)$ là kích thước của quần thể vi khuẩn sinh sản tại thời điểm $t$. Trong điều kiện lý tưởng $\Delta N(t) = N(t + \Delta t)$ - $N(t)$ trong khoảng thời gian từ $t$ đến $t + \Delta t$ cho
nhiều loại vi khuẩn có thể được xem xét

⟦folio 12⟧

tỷ lệ theo bảng số lượng vi khuẩn có $t$ vi khuẩn tại thời điểm đó; Ngoài ra, đối với $\Delta t$ nhỏ, mức tăng $\Delta N(t)$ phải xấp xỉ tỷ lệ với $\Delta t$.
Vì vậy, với các giả định đã được đưa ra, chúng ta có thể viết
$$\Delta N(t) \approx kN(t)\Delta t,$$
trong đó $k > 0$ là hệ số tùy thuộc vào loại vi khuẩn. Vì thế,
$$\frac{\Delta N(t)}{\Delta t} \approx kN(t).$$
Trừu tượng từ thực tế là số chỉ có thể thay đổi ở dạng số nguyên, chúng ta sẽ giả sử rằng $N(t)$ thay đổi liên tục theo thời gian. Xét rằng đẳng thức cuối cùng phải chính xác hơn, $\Delta t$ càng nhỏ (hãy nghĩ xem), sau khi chuyển giới từ trong đó là $\Delta t$ tiến về 0, chúng ta thu được phương trình vi phân có dạng (1):
$$N'(t) = kN(t).$$
Vì vậy (xem điểm 1),
$$N(t) = Ae^{kt},$$
nên dân số tăng theo quy luật hàm mũ. Nếu biết kích thước quần thể ban đầu, tức là điều kiện ban đầu $N(0) = N_0$, thì theo công thức (4), chúng ta có thể viết
$$N(t) = N_0e^{kt}.$$
(B) Rơi tự do do ma sát (mô hình dù). Để một vật có khối lượng $m$ rơi thẳng đứng từ một độ cao nhất định, và cùng với lực hấp dẫn $F_\tau = mg$, nó chịu tác dụng của một lực ma sát ngược chiều với vận tốc, tỉ lệ với độ lớn của vận tốc: $F_{\tau p} = -\alpha v$, trong đó $\alpha > 0$ là hệ số ma sát. Hãy xác định sự phụ thuộc của tốc độ vào thời gian.
Trong trường hợp này, phương trình vi phân thu được ngay từ định luật thứ hai của Newton: $ma = F = F_\tau + F_{\tau p}$, tức là $mv' = mg - av$. Chia cả hai vế cho $m$, chúng ta lại thu được một phương trình vi phân tuyến tính, nhưng lần này có dạng (5):
$$v' = -\frac{\alpha}{m}v + g.$$

Khu công nghiệp (6)
$$v(t) = \frac{mg}{\alpha} + Ae^{-\frac{\alpha}{m}t}.$$
Trong trường hợp $v(0) = 0$, chúng ta tìm thấy $A = -\frac{mg}{\alpha}$ và
$$v(t) = \frac{mg}{\alpha}\left(1 - e^{-\frac{\alpha}{m}t}\right).$$

Khi rơi tự do không ma sát ($v' = g$), giá trị tốc độ quay trở lại là tuyến tính: $v(t) = gt$. Tuy nhiên, khi có ma sát, tốc độ quay trở lại có xu hướng không đổi: với giá trị trả về $t$, giá trị của $e^{-\frac{\alpha}{m}t}$ có xu hướng về 0, do đó $v(t)$ có xu hướng về giá trị giới hạn $v_{\text{np}} = mg/\alpha$ (biểu đồ của giá trị tốc độ được hiển thị trong Hình 2).

(B) Công thức khí áp kế. Người ta biết rằng càng lên cao thì không khí càng loãng - áp suất khí quyển giảm theo độ cao. Hãy thử xác định sự phụ thuộc của $p = p(h)$ áp suất $p$ vào độ cao $h$ so với mực nước biển.

Chúng ta hãy nhớ lại rằng các giá trị áp suất khí quyển được coi là trọng lượng của một cột không khí thẳng đứng có bề mặt phẳng.

Cơm. 2.
Cơm. 3.

⟦folio 13⟧

phần $S = 1$ cm$^2$. Vì thế, sự khác biệt

$$p(h) - p(h + \Delta h) = -\Delta p(h)$$

bằng về mặt số lượng với trọng lượng của cột tác động từ độ cao $h$ đến độ cao $h + \Delta h$ (Hình 3), tức là

$$-\Delta p(h) = \Delta mg,$$

trong đó $\Delta m$ là khối lượng của mảnh đá này. Thể tích của stolnik bằng $\Delta V = S\Delta h = \Delta h$, do đó, nếu mật độ va chạm trung bình trong stolnik là $\rho_{cp}$ thì $\Delta m = \rho_{cp}\Delta h$, do đó $-\Delta p(h) = g\rho_{cp}\Delta h$ và cuối cùng,

$$\frac{\Delta p(h)}{\Delta h} = -g\rho_{cp}.$$

Chúng ta hãy biểu thị mật độ tác động ở độ cao $h$ bằng $\rho(h)$; thì khi $\Delta h$ tiến tới 0, mật độ trung bình của $\rho_{cp}$ có xu hướng $\rho(h)$ và từ lần tương ứng cuối cùng chúng ta thu được phương trình vi phân

$$p'(h) = -g\rho(h),$$

tuy nhiên, trong đó hàm $\rho(h)$ cũng chưa được biết.

Bây giờ chúng ta giả sử rằng nhiệt độ ảnh hưởng là như nhau ở tất cả các lớp khí quyển. Khi đó, có thể dễ dàng suy ra từ định luật Boyle-Mariotte hoặc từ phương trình trạng thái khí rằng áp suất tỷ lệ thuận với mật độ$^*$:

$$p(h) = b\rho(h).$$

Từ đẳng thức này và các đẳng thức trước đó, chúng ta thu được phương trình vi phân cuối cùng

$$p'(h) = -\frac{g}{b}p(h)$$

- nó lại trông giống như (1)! Áp dụng lý thuyết ở điểm 1, ta thấy

$$p(h) = p_0 e^{-\frac{g}{b}h},$$

trong đó $p_0$ là áp suất khí quyển ở mực nước biển, tức là ở $h = 0$.

Vì vậy, áp suất giết chết độ cao theo quy luật hàm mũ, phù hợp với cái gọi là kết quả thu được

$$*) pV = RT,$$

từ đó $p = \frac{RT}{V} = \frac{RT}{M} \times \frac{M}{V} = b\rho$, trong đó $b = \frac{RT}{M}$, $R$ là hằng số khí phổ quát, $M$ là khối lượng mol của khí.

bằng công thức khí áp kế. Công thức mà chúng tôi thu được “thất bại” ở những độ cao có độ lớn tương đương với bán kính Trái đất. Và điều này không chỉ do chúng ta bỏ qua sự thay đổi nhiệt độ theo độ cao mà còn do sự thay đổi gia tốc rơi tự do.

Lưu ý rằng trong trường hợp này, phương trình vi phân không mô tả một quá trình vật lý mà chỉ đơn giản là sự thay đổi của một đại lượng vật lý ($p$) tùy thuộc vào một đại lượng khác ($h$).

3. Về dao động điều hòa

Bây giờ chúng ta hãy tập trung vào phương trình vi phân thứ hai được học ở trường - phương trình dao động điều hòa

$$y'' = -\omega^2 y.$$

Như đã biết từ khóa học ở trường, bất kỳ lời giải nào của phương trình này đều được viết dưới dạng

$$y(t) = A \cos (\omega t + \varphi),$$

trong đó $A$ và $\varphi$ là các hằng số tùy ý và chúng ta có thể giả sử rằng $A \geq 0$, $\varphi \in [0; 2\pi]$. Theo những hạn chế này, các hằng số $A$ và $\varphi$ được xác định duy nhất bởi các điều kiện ban đầu, trong trường hợp này đã yêu cầu hai: $y(t_0) = y_0$ và $y'(t_0) = v_0$.

Lưu ý rằng trong trường hợp này, qua mỗi điểm $(t_0; y_0)$ của mặt phẳng tọa độ có vô số đồ thị có dạng (7). Tuy nhiên, đồ thị được xác định duy nhất nếu bạn cũng chỉ định tiếp tuyến của đồ thị tại một điểm nhất định (giải thích). Điều này là do thực tế là phương trình (2) bậc hai, nghĩa là nó bao gồm hàm quan tâm tùy ý thứ hai.

Về đại lượng $y$, đại lượng thay đổi theo thời gian theo định luật (7), người ta nói rằng nó thực hiện dao động điều hòa với tần số $\omega$. Điều quan trọng cần lưu ý là tần số không phụ thuộc vào các điều kiện ban đầu mà chỉ được xác định bởi hệ số trong phương trình ban đầu.

Phương trình dạng (2) được tìm thấy trong phần mô tả dao động đa giác

⟦folio 14⟧

các hệ thống, và không chỉ các hệ thống cơ khí. Sách giáo khoa xét một ví dụ về dao động bên ngoài của quả bóng: nếu khối lượng của quả bóng là $m$ thì hệ số cứng của lò xo là $k$, độ dịch chuyển của quả bóng so với vị trí cân bằng là $x$ thì theo định luật thứ hai Newton là $mx'' = -kx$, do đó $x'' = -\omega^2 x$, trong đó $\omega = \sqrt{\frac{k}{m}}$.

Hãy xem một ví dụ khác.

Các dao động nhỏ của ma trận. Đặt một quả bóng có khối lượng $m$ được cố định ở đầu $M$ của một thanh không trọng lượng $OM$ được treo bởi Sharirino tại điểm $O$ sao cho ma trận dao động trong một mặt phẳng (Hình 4). Thật thuận tiện khi thay đổi độ lệch của ma trận $OM$ so với vị trí cân bằng $OM_0$ bằng giá trị $x$ của góc $M_0OM$, tính bằng radian.

Hai lực tác dụng lên quả bóng: hướng thẳng đứng hướng xuống của lực hấp dẫn $F_\tau = -mg$ và hướng hướng tâm $MO$ phản lực của thanh $N$.

Hãy viết định luật II Newton dưới dạng hình chiếu lên tiếp tuyến:

$$m(lx)'' = -mg \sin x,$$

đó là

$$x'' = -\frac{g}{l} \sin x$$

Chúng ta sẽ chỉ xem xét các dao động nhỏ của ma trận, nghĩa là chúng ta sẽ coi giá trị $x$ là nhỏ. Khi đó tội lỗi $x$ có thể được thay thế bằng $x$ (hãy nhớ rằng

$$\lim_{x \to 0} \frac{\sin x}{x} = 1$$

- “Đại số và nguyên lý phân tích 10”, đoạn 78) và từ kết quả cân bằng vi phân ta đi đến cân bằng dao động điều hòa

$$x'' = -\frac{g}{l} x,$$

hoặc $x'' = -\omega^2 x$,

ở đâu $\omega = \sqrt{\frac{g}{l}}$.

Do đó, đối với những sai lệch nhỏ so với vị trí cân bằng, các dao động của ma trận sẽ gần như điều hòa, với tần số $\omega = \sqrt{g/l}$, không phụ thuộc vào khối lượng $m$ và các điều kiện ban đầu, miễn là $x_0$ và $v_0$ đủ nhỏ.

Tất nhiên, toàn bộ sự đa dạng của các quá trình và hiện tượng tự nhiên không thể chỉ quy gọn vào sự kiểm soát của hai loại khác nhau. Thế giới cân bằng vi phân cũng phong phú gần như thế giới thực. Kinh nghiệm khoa học cho thấy rằng việc sử dụng cân bằng vi phân làm mô hình toán học là rất hiệu quả - tất nhiên, nếu chúng ta không quên phạm vi ứng dụng hạn chế của bất kỳ loại mô hình nào.

Bài tập và bài toán

1. Tìm lời giải của cân bằng vi phân $y' = -2y + 4$ thỏa mãn điều kiện ban đầu $y(0) = 5$.

2. Có một lượng chất phóng xạ nhất định. Được biết, sau 30 ngày, 50% chất này sẽ phân hủy. Sau bao nhiêu ngày chất đó còn lại 1% lượng chất ban đầu?

3. Một vật được làm nóng đến $100^\circ$ được đặt trong môi trường có nhiệt độ không đổi $20^\circ$. Sau 10 phút, nhiệt độ cơ thể giảm xuống $60^\circ$. Sau bao lâu nhiệt độ cơ thể sẽ trở thành $25^\circ$?

(Gợi ý cho bài 2 và 3. Sử dụng ví dụ 1 và 3 ở đoạn 110 của sách giáo khoa.)

4. 12 giờ sau khi bắt đầu thí nghiệm, một số lượng vi khuẩn nhất định đã tăng gấp ba lần. Số lượng vi khuẩn sẽ tăng lên bao nhiêu lần trong 24 giờ?

5. Giá trị của hằng số $b$ trong công thức khí áp cho hiệu ứng tổng là $7,7 \cdot 10^4 \text{ m}^2/\text{c}^2$. Bạn cần lên cao bao nhiêu để giảm áp suất xuống một nửa?

6. Thuyền chuyển động chậm dần do lực cản của thuyền. Vận tốc ban đầu của thuyền là 2 m/s, sau 4 s vận tốc của nó là 1 m/s. Sau bao nhiêu giây vận tốc của thuyền là 0,25 m/s? Thuyền đi được bao xa thì dừng lại?

7. Một cô gái đu trên xích đu. Độ lệch lớn nhất so với vị trí cân bằng là 1 m, gia tốc cực đại là 4 m/s2. Giả sử dao động điều hòa là dao động điều hòa, hãy tìm chu kỳ của chúng. Xác định độ cao của xích đu.

8. Tìm dạng tổng quát lời giải của cân bằng vi phân $y'' = -\omega^2 y + a(\omega > 0)$ và $a$ là các hằng số.
