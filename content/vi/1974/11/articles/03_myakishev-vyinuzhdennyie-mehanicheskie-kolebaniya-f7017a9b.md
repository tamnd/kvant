---
id: 1974-11-myakishev-vyinuzhdennyie-mehanicheskie-kolebaniya-f7017a9b
issue: kvant_1974_11
year: 1974
number: "11"
title: Rung động cơ học cưỡng bức
authors:
  - Мякишев Г. Я.
rubric: osnovnye-stati
page_first: 4
page_last: 9
page_labels: 2-7
tag: M8OL
lang: vi
source: kvant_digital
extraction: vision
content_sha256: c2839b77716349ce691bcbb37ae502bdfe24f2b8e6820497b0e7c247769cfe03
prompt_sha256: draft-1
translated_from: content/ru/1974/11/articles/03_myakishev-vyinuzhdennyie-mehanicheskie-kolebaniya-f7017a9b.md
source_content_sha256: d3b4699b1a8f198b565211cb5611e8e732b03a85c3e930bb4239ff4ec18fa40f
translation_model: draft
translation_run: vi-draft-2026-11-03
translation_quality: draft
---

⟦folio 2⟧

Phương trình cơ bản của chuyển động trong cơ học là định luật thứ hai của Newton:

$$m a = F.$$

Để tìm vị trí của một vật và tốc độ của nó tại bất kỳ thời điểm nào, chỉ cần biết lực là hàm của tọa độ của vật và hình chiếu vận tốc của nó, cũng như các điều kiện ban đầu: tọa độ và hình chiếu của vận tốc của vật tại thời điểm ban đầu là đủ.

Trường hợp đơn giản nhất là chuyển động dưới tác dụng của một lực không đổi $F = const$ (cụ thể là lực có thể bằng 0). Khi đó gia tốc không đổi ($a = const$); tọa độ và tốc độ của vật thể được xác định dễ dàng bằng các phương trình động học nổi tiếng.

Trong chuyển động dao động rất phổ biến trong tự nhiên và được sử dụng rộng rãi trong công nghệ, gia tốc không phải là hằng số. Điều này làm cho lời giải cơ học bài toán trở nên khó khăn hơn nhiều. Chỉ những dao động điều hòa tự do của một vật dưới tác dụng của một lực tỷ lệ với sự dịch chuyển của vật khỏi vị trí cân bằng mới có thể được nghiên cứu hoàn toàn mà không cần dùng đến toán học cao hơn. Nhưng đã tính đến lực ba, tỷ lệ thuận với tốc độ, cần phải thay đổi các phương trình vi phân. Nó thậm chí còn khó khăn hơn (về mặt toán học) bài toán đối với dao động cưỡng bức, khi có thêm một lực tuần hoàn bên ngoài tác dụng lên hệ tác dụng. Trong trường hợp này, một hiện tượng gây tò mò và thực tế quan trọng được quan sát thấy trong hệ thống - sự cộng hưởng. Khi tần số của ngoại lực trùng với tần số riêng của hệ thì biên độ dao động của hệ tăng mạnh.

Tuy nhiên, có thể phân tích quá trình dao động cưỡng bức bằng cách sử dụng các thông điệp vật lý trực quan mà không cần dùng đến lời giải một phương trình chuyển động phức tạp. Đặc biệt, chúng ta có thể hiểu tại sao lại quan sát được sự cộng hưởng. Đây là những gì bài viết này nói về.

Nhưng trước tiên, chúng ta hãy nhắc lại một số điều khoản cơ bản liên quan đến dao động điều hòa tự do.

Dao động điều hòa tự do

Hệ dao động đơn giản nhất là hệ trong đó lực tác dụng tỷ lệ với độ dịch chuyển của vật so với vị trí cân bằng, hướng ngược lại với độ dịch chuyển. Tất nhiên, luôn có sự va chạm. Nhưng nếu nó nhỏ thì trong một khoảng thời gian không quá dài, dưới tác dụng của ba lực, bạn có thể không còn tồn tại. Các hệ thống như vậy bao gồm: tải trọng bên ngoài, thảm toán học (ở góc lệch nhỏ), một vật nổi trên mặt nước có tiết diện không đổi, v.v. Để định nghĩa, chúng ta sẽ chỉ nói về tải trọng bên ngoài. Có hai lực tác dụng lên tải trọng: trọng lực và lực đàn hồi của lò xo. Lực hấp dẫn không đổi $F_T = mg$ không ảnh hưởng đến quá trình dao động dưới bất kỳ hình thức nào. Nó sẽ chỉ gây nhầm lẫn về vị trí cân bằng của tải. Thật dễ dàng để loại trừ

⟦folio 3⟧

khỏi phương trình chuyển động nếu gốc của hệ quy chiếu kết hợp với đầu của một lò xo bị biến dạng do tải trọng khi tải đứng yên (hình 1). Hãy hướng trục tọa độ $OX$ theo phương thẳng đứng xuống dưới. Khi đó dao động sẽ chỉ xảy ra dưới tác dụng của lực đàn hồi $F_y = -kx$, trong đó $k$ là hệ số đàn hồi và $x$ là sự dịch chuyển của tải khỏi vị trí cân bằng. Phương trình chuyển động sẽ được viết như sau:

$$ma_x = -kx. \tag{1}$$

Chia phương trình này cho $m$ và đưa ra ký hiệu $\omega_0 = \sqrt{\frac{k}{m}}$, chúng ta thu được dạng được chấp nhận chung của phương trình mô tả dao động điều hòa với tần số tuần hoàn $\omega_0$:

$$a_x = -\omega_0^2 x. \tag{2}$$

Lời giải của phương trình này, tức là tìm hàm $x = x(t)$, có thể đạt được một cách cơ bản nhưng khá lâu. Kết quả là:

$$x = x_0 \cos(\omega_0 t + \varphi_0). \tag{3}$$

Ở đây $x_0$ là biên độ dao động và $\varphi_0$ là pha ban đầu. Các đại lượng này được tìm thấy từ các điều kiện ban đầu.

Rõ ràng là chúng ta kích thích dao động của một vật nặng đặt trên lò xo bằng cách kéo nó xuống và thả nó ra. Hơn nữa, tại thời điểm ban đầu (tại $t = 0$) $x = x_0$ và $v_x = 0$. Điều này khớp với $\varphi_0 = 0$. Sau đó

$$x = x_0 \cos \omega_0 t. \tag{4}$$

Dao động điều hòa có thể được mô tả bằng đẳng thức.

Hình 1.

các hàm lượng giác mới cosine và sin. Thay vì (3), end, chúng ta có thể viết:

$$x = x_0 \sin(\omega_0 t + \varphi_0). \tag{5}$$

Nhưng sau đó với các điều kiện ban đầu thông thường $\varphi_0 = \frac{\pi}{2}$ chứ không phải bằng 0. Do đó, viết bằng cosin có phần thích hợp hơn, mặc dù tất nhiên bạn cũng có thể sử dụng sin.

Tốc độ trong quá trình dao động điều hòa cũng thay đổi theo định luật điều hòa. Biên độ của nó bằng $v_0 = \omega_0 x_0$ và độ lệch pha so với tọa độ bằng $\frac{\pi}{2}$:

$$v_x = \omega_0 x_0 \cos\left(\omega_0 t + \frac{\pi}{2}\right) = -\omega_0 x_0 \sin \omega_0 t. \tag{6}$$

Gia tốc dao động lệch pha với tọa độ (ngược pha $\pi$) và có biên độ $a_0 = \omega_0^2 x_0$, tức là

$$a_x = \omega_0^2 x_0 \cos(\omega_0 t + \pi) = -\omega_0^2 x_0 \cos \omega_0 t. \tag{7}$$

Đó là tất cả những gì bạn cần biết để biết thêm về các dao động điều hòa tự do tương đối.

Phương trình chuyển động của dao động cưỡng bức

Cho một lực tuần hoàn bên ngoài $F_x = F_0 \cos \omega t$ tác dụng lên hệ dao động (trong ví dụ của chúng ta là tải trọng tác dụng lên lò xo). Ngoài ra, vật còn chịu tác dụng của lực đàn hồi $F_y = -kx$ và lực ma sát tỉ lệ với tốc độ $F_{\tau p} = -\mu v_x^*$), trong đó $\mu$ là hệ số ma sát. Khi đó phương trình chuyển động sẽ được viết như sau:

$$ma_x = -kx - \mu v_x + F_0 \cos \omega t. \tag{8}$$

Vượt qua vế trái của phương trình với tất cả các lực ngoại trừ lực bên ngoài, chúng ta nhận được:

$$ma_x + \mu v_x + kx = F_0 \cos \omega t.$$

*) Ở tốc độ chuyển động thấp của vật thể, thực tế chúng ta có thể giả sử rằng lực ma sát (hay nói cách khác là lực cản) tỷ lệ thuận với tốc độ.

⟦folio 4⟧

Hình 2.

Sẽ thuận tiện hơn nếu viết phương trình này ở dạng hơi khác, chia vế phải và vế trái cho $m$ và giới thiệu ký hiệu $\omega_0 = \sqrt{\frac{k}{m}}$:

$$a_x + \frac{\mu}{m} v_x + \omega_0 x = \frac{F_0}{m} \cos \omega t.$$ (9)

Chuyển động của một vật tuân theo phương trình này khá phức tạp, đặc biệt là lúc ban đầu, khi nó không điều hòa.

Thiết lập dao động

Cơ chế thiết lập dao động điều hòa cưỡng bức có thể được thực hiện như sau. Dưới tác dụng của ngoại lực, hệ nhận được một “lực đẩy”, do đó phát sinh các dao động tự do có tần số $\omega_0$ trong đó. Theo thời gian, các dao động tự do sẽ tắt đi càng nhanh thì hệ số ma sát $\mu$ càng lớn. Nhưng đồng thời, có một lực tuần hoàn bên ngoài trong hệ tác dụng gây ra các dao động trong hệ đó với tần số $\omega$. Do đó, trong một khoảng thời gian nhất định, cả dao động tự do và dao động cưỡng bức đều xảy ra đồng thời trong hệ, nghĩa là nguyên lý chồng chất áp dụng cho các chuyển động dao động.

Biên độ của dao động cưỡng bức tăng theo thời gian (hình 2) cho đến khi thiết lập một giá trị Dừng nhất định. Điều này sẽ xảy ra khi công của ngoại lực bằng công của lực ma sát, tức là khi năng lượng đi vào hệ từ bên ngoài bằng với sự mất đi năng lượng cơ học bên trong hệ.

Như vậy, chỉ sau thời điểm thiết lập dao động trong hệ thì các dao động tự do sẽ mất đi và chỉ còn lại các dao động điều hòa cưỡng bức có tần số $\omega$ và biên độ $x_0$:

$$x = x_0 \cos (\omega t + \varphi_0).$$ (10)

Ở bên ngoài, các phương trình dao động tự do và dao động cưỡng bức trùng nhau. Nhưng nếu trong quá trình dao động tự do $x_0$ và $\varphi_0$ chỉ được xác định bởi các điều kiện ban đầu, thì trong quá trình dao động cưỡng bức, chúng được xác định (như chúng ta sẽ thấy sau) bởi các tham số của cả hệ và ngoại lực. Trước hết, sự tương ứng giữa tần số dao động tự nhiên và dao động cưỡng bức đóng một vai trò quan trọng. Nhân tiện, lưu ý rằng các giá trị của $\varphi_0$ trong trường hợp dao động cưỡng bức được gọi là độ lệch pha giữa dao động của hỗn hợp và ngoại lực.

Tốc độ và gia tốc của một vật thực hiện dao động cưỡng bức được xác định bởi các đẳng thức tương tự như (6) và (7) đối với dao động tự do:

$$v_x = \omega x_0 \cos \left(\omega t + \varphi_0 + \frac{\pi}{2}\right),$$ (11)

$$a_x = -\omega^2 x_0 \cos (\omega t + \varphi_0).$$ (12)

Vì tốc độ luôn đặc trưng cho sự thay đổi nhanh chóng của tọa độ theo thời gian và gia tốc đặc trưng cho sự thay đổi nhanh chóng của tốc độ theo thời gian, nên khi biết sự phụ thuộc của tọa độ vào thời gian $x(t)$, chúng ta có thể xác định duy nhất hàm $v_x(t)$ và $a_x(t)$.

Bây giờ chúng ta hãy chuyển sang lời giải cơ bản bài toán. Chúng ta hãy tìm hiểu xem biên độ $x_0$ của dao động cưỡng bức và độ lệch pha $\varphi_0$ phụ thuộc vào điều gì và như thế nào. Để làm điều này, hãy xem xét ba trường hợp giới hạn.

⟦folio 5⟧

Trường hợp thứ nhất: $\omega \ll \omega_0 = \sqrt{\frac{k}{m}}$, tức là một phần ngoại lực tuần hoàn nhỏ hơn nhiều so với tần số riêng của hệ $^*$).

Trường hợp thứ hai: $\omega \gg \omega_0$; điều kiện ngược lại được thỏa mãn.

Và cuối cùng, trường hợp quan trọng nhất: $\omega \approx \omega_0$. Đây là một trường hợp cộng hưởng.

Dao động cưỡng bức tần số thấp

Chúng ta hãy viết lại phương trình (9) - phương trình chuyển động của dao động cưỡng bức:

$$a_x + \frac{\mu}{m} v_x + \omega_0^2 x = \frac{F_0}{m} \cos \omega t.$$

Nếu $\omega \ll \omega_0$, thì trong ba số hạng ở vế trái của phương trình này, số hạng lớn nhất sẽ là số hạng cuối cùng $\omega_0^2 x$. Thật vậy, biên độ của số hạng đầu tiên tỷ lệ với $\omega^2 x_0$, số hạng thứ hai - với $\omega x_0$ và số hạng cuối cùng - với $\omega_0^2 x_0$. Do đó, phép tính gần đúng (cho rằng $\omega \rightarrow 0$)

$$\omega_0^2 x = \frac{F_0}{m} \cos \omega t,$$

Ở đâu

$$x = \frac{F_0}{m \omega_0^2} \cos \omega t = \frac{F_0}{k} \cos \omega t.$$ (13)

Các dao động tọa độ tỷ lệ thuận và pha của dao động trùng với pha của ngoại lực.

*) Cần một phần nhỏ để đảm bảo độ chính xác. Khi có ma sát, tần số tự nhiên $\omega_c$ của dao động tự do không bằng $\omega_0 = \sqrt{\frac{k}{m}}$. Trên thực tế, nó có phần nhỏ hơn: $\omega_c = \sqrt{\omega_0^2 - \frac{\mu^2}{4m^2}}$. Nhưng với hệ số ma sát thấp ($\mu \rightarrow 0$) $\omega_c \approx \omega_0$. Những trường hợp thực tế thú vị nhất chính là những trường hợp ma sát nhỏ. Do đó, chúng ta có thể coi tần số dao động riêng của hệ bằng $\omega_0 = \sqrt{\frac{k}{m}}$ một cách đúng đắn.

Lưu ý rằng độ cứng của lò xo càng lớn thì biên độ dao động càng nhỏ. Về mặt định tính, trường hợp này có thể được mô tả như sau. Ở tần số thấp của ngoại lực, điều gần như xảy ra giống như khi một lực không đổi tác dụng lên một lò xo. Theo định luật Hooke, độ dịch chuyển tăng tỷ lệ với ngoại lực và tại bất kỳ thời điểm nào ngoại lực gần như cân bằng chính xác với lực đàn hồi của lò xo.

Từ quan điểm năng lượng, các điều kiện để bơm năng lượng vào hệ dao động từ các vật thể bên ngoài tác dụng lên hệ với một lực tuần hoàn là rất bất lợi. Trên thực tế: trong bốn giai đoạn, khi vật bị dịch chuyển khỏi vị trí cân bằng, ngoại lực thực hiện công dương, vì lực và tốc độ của vật, và do đó sự dịch chuyển, đều hướng theo một hướng (hình 3). Nhưng trong bốn giai đoạn tiếp theo, khi vật trở về vị trí cân bằng, lực và tốc độ (và do đó là độ dịch chuyển) hướng ngược nhau (hình 4). Công do ngoại lực thực hiện sẽ âm. Bức tranh tương tự sẽ được quan sát thấy trong nửa sau của giai đoạn này. Nhìn chung, trong thời gian làm việc, ngoại lực gần như bằng không. Chỉ một phần nhỏ công của ngoại lực bù cho công của lực ma sát, vì tốc độ của vật ở $\omega \ll \omega_0$ là rất nhỏ, và do đó độ lớn của lực ma sát cũng nhỏ.

⟦folio 6⟧

Ở đây có một sự tinh tế nào đó đôi khi khiến người ta khó hiểu được bản chất của vấn đề. Nếu sự thay đổi so với vị trí cân bằng tỷ lệ thuận với lực tại thời điểm bất kỳ, thì thoạt nhìn, có vẻ như công luôn luôn dương. Tuy nhiên, phải lưu ý rằng dấu của công phụ thuộc vào sự trùng hợp giữa hướng của lực và hướng chuyển động, tức là tốc độ chứ không phụ thuộc vào dấu tọa độ. Để công là dương, không nhất thiết các dấu $F_x$ và $x$ phải trùng nhau mà $F_x$ và $\Delta x$ (hoặc $\frac{\Delta x}{\Delta t} = v_x$) phải có cùng dấu.

Dao động cưỡng bức của một bộ phận lớn

Trong trường hợp $\omega \gg \omega_0$ ở vế trái của phương trình (9), tại bất kỳ thời điểm nào số lớn nhất sẽ là số hạng đầu tiên, biên độ của nó tỉ lệ với bình phương tần số. Nó sẽ đóng vai trò chính, vì vậy bạn có thể viết:

$$a_x = \frac{F_0}{m} \cos \omega t.$$

Bây giờ không phải tọa độ cùng pha với lực, mà là gia tốc và các dao động của tọa độ sẽ xảy ra ngược pha với dao động của ngoại lực. Biên độ tọa độ bằng

$$x_0 = \frac{a_0}{\omega^2} = \frac{F_0}{m\omega^2}.$$

Như vậy, dao động của cơ thể được truyền theo quy luật

$$x = -\frac{F_0}{m\omega^2} \cos \omega t.$$ (14)

Khi $\omega \to \infty$ (điều này tương đương với điều kiện $\omega \gg \omega_0$) $x_0 \to 0$, tức là biên độ dao động nhỏ. Kết quả này là khá tự nhiên. Các cột lực theo hướng mà vật có quán tính không có thời gian dịch chuyển đáng kể so với vị trí cân bằng.

Như trong trường hợp trước, khi $\omega \ll \omega_0$, một nửa chu kỳ ngoại lực thực hiện công dương và nửa còn lại - công âm. Trong nửa thời gian, lực và chuyển vị hướng cùng chiều, và trong nửa thời gian còn lại chúng hướng ngược chiều nhau. Một lần nữa, hầu như không có năng lượng nào đi vào hệ thống.

cộng hưởng

Phần thú vị nhất của trường hợp dao động cưỡng bức là trường hợp tần số của một lực tuần hoàn bên ngoài trùng với tần số dao động tự nhiên của hệ ($\omega \approx \omega_0$).

Trong trường hợp này, phương trình đầu tiên là (9), có thể viết như sau:

$$a_x = -\omega_0^2 x,$$

triệt tiêu lẫn nhau với số hạng thứ ba bằng $\omega_0^2 x$. Hai số hạng này tại bất kỳ thời điểm nào đều có độ lớn bằng nhau nhưng có dấu trái ngược nhau, vì gia tốc và tọa độ của bất kỳ dao động điều hòa nào đều lệch pha nhau π.

Kết quả là phương trình (9) có dạng:

$$\mu v_x = F_0 \cos \omega_0 t.$$ (15)

Đây là một phương trình đơn giản và chứa đựng bản chất của sự cộng hưởng. Tại $\omega \approx \omega_0$ tại bất kỳ thời điểm nào (chúng ta hãy nhấn mạnh một lần nữa rằng chúng ta đang nói về dao động cưỡng bức ổn định), ngoại lực dường như tắt người hầu ma sát khỏi trò chơi. Kết quả là gia tốc chỉ đến từ độ đàn hồi. Về bản chất, một tình huống rất nhỏ được thực hiện: các dao động điều hòa tồn tại trong hệ trong một thời gian dài tùy ý, bất chấp tác dụng của ma sát.

Từ (15) rõ ràng rằng trong quá trình cộng hưởng, pha dao động vận tốc trùng với pha của ngoại lực. Công do ngoại lực thực hiện dưới những điều kiện này là dương trên toàn bộ chiều dài của

⟦folio 7⟧

Rioda. Các điều kiện tối ưu được tạo ra để bơm năng lượng từ các vật thể bên ngoài vào hệ dao động.

Công dương do ngoại lực thực hiện có độ lớn hoàn toàn bằng công âm do lực ma sát thực hiện. Vì vậy, cơ năng của hệ không thay đổi. Năng lượng từ bên ngoài do tác dụng của lực ma sát biến thành nhiệt (lò xo mang tải trọng và không khí xung quanh nóng lên).

Biên độ dao động khi cộng hưởng bằng

$$x_0 = \frac{v_0}{\omega_0} = \frac{F_0}{\mu\omega_0}.$$

Hệ số ma sát càng nhỏ thì càng lớn. Tại $\mu \rightarrow 0$ $x_0 \rightarrow \infty$, nghĩa là rất/không, ở $\omega \approx \omega_0$ biên độ là cực đại. Nếu $\mu$ có giá trị đủ lớn thì biên độ dao động cộng hưởng không lớn.

Phương trình dao động cộng hưởng có dạng

$$x = \frac{F_0}{\mu\omega_0} \cos \left( \omega t - \frac{\pi}{2} \right),$$

vì quá trình trộn chậm hơn tốc độ một phần tư thời gian. Bây giờ có thể mô tả dạng gần đúng của sự phụ thuộc của biên độ $x_0$ và сdwа của pha $\varphi_0$ của dao động cưỡng bức vào tần số. Chúng ta biết rằng ở tần số thấp ($\omega = 0$), biên độ dao động bằng $\frac{F_0}{k}$ và cdwг cùng pha bằng 0.

Ở tần số cao ($\omega \rightarrow \infty$)
