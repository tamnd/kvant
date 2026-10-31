---
id: 1988-2-chernoutsan-kinematicheskie-svyazi-v-zadachah-dinamiki-1c019da1
issue: kvant_1988_2
year: 1988
number: "2"
title: Các kết nối động học trong các bài toán động lực học
authors:
  - Черноуцан А. И.
rubric: praktikum-abiturienta
rubric_sub: Практикум абитуриента
page_first: 59
page_last: 64
page_labels: 57-62
tag: JSBZ
lang: vi
source: kvant_digital
extraction: vision
content_sha256: a11e3bceb64e07d0a74404f8eb4c6bd74f158d3bacfb50957b2cf7d6c159c312
prompt_sha256: draft-1
translated_from: content/ru/1988/02/articles/19_chernoutsan-kinematicheskie-svyazi-v-zadachah-dinamiki-1c019da1.md
source_content_sha256: 91347c2003eb69c4ed56421a5ffb65c6cc464e31bb713c943761596f0a15223a
translation_model: draft
translation_run: vi-draft-2026-10-31
translation_quality: draft
---

⟦folio 57⟧

Các kết nối động học trong bài toán động

Ứng viên Khoa học Vật lý và Toán học
A. I. CHernOUTSAN

Trong các bài toán cơ học, thường nảy sinh tình huống khi một vật chuyển động không được tự do. Các ràng buộc có thể được tạo ra bởi các bề mặt cứng, các sợi không thể mở rộng, các thanh cứng, v.v. Trong những trường hợp đơn giản nhất, chúng tôi tự động tính đến các ràng buộc đó mà thường không hề quy định sự tồn tại của chúng. Ví dụ: chúng tôi hướng gia tốc của một vật trên mặt phẳng dọc theo mặt phẳng (có tính đến sự có mặt của bề mặt rắn), chúng tôi coi tốc độ của tàu kéo và sà lan là như nhau (có tính đến sự có mặt của một sợi cáp không thể đứt), v.v. Tuy nhiên, đôi khi cần phải thể hiện những hạn chế này dưới dạng một điều khiển đặc biệt, mà chúng tôi sẽ gọi là “khớp nối động học”. Hãy bắt đầu với điều này bài toán.

Bài toán 1. Tìm gia tốc của lăng trụ có khối lượng $m_1$ và hình lập phương có khối lượng $m_2$ như ở hình 1, a. Ví dụ thứ ba.

Hãy viết định luật II Newton cho mỗi vật (hình chiếu lên hướng trùng với gia tốc tương ứng):

$$m_1 g - N \sin \alpha = m_1 a_1,$$

$$N \cos \alpha = m_2 a_2.$$

Chúng tôi đã dạy điều đó theo định luật thứ ba của Newton, $\vec{N}_{12} = -\vec{N}_{21}$, tức là $N_{12} = N_{21} = N$. Hai phương trình được viết có chứa ba ẩn số. Phương trình thứ ba, mối quan hệ động học giữa $a_1$ và $a_2$, sẽ phản ánh thực tế là khối lập phương và lăng kính luôn tiếp xúc với nhau. Điều này có thể được thực hiện theo nhiều cách.

1) Chúng ta hãy xem xét hai vị trí đóng của hệ thống, cách nhau một khoảng thời gian $\Delta t$ (hình 1, 6). Trong tam giác $ABC$, cạnh $AB$ bằng biến lăng trụ $\Delta x_1$ và cạnh $BC$ bằng

⟦folio 58⟧

di chuyển khối lập phương $\Delta x_2$. chúng tôi có
$$\Delta x_2 = \Delta x_1 \text{tg} \alpha.$$
Chia cả hai vế của đẳng thức cho $\Delta t$, ta được
$$v_2 = v_1 \text{tg} \alpha.$$
Vì sự tương ứng này có giá trị trong một thời điểm tùy ý, nên sự tương ứng mong muốn sẽ theo sau nó
$$a_2 = a_1 \text{tg} \alpha.$$ (3)
Chúng ta sẽ gọi phương pháp này để thu được kết nối động học là phương pháp trực tiếp.
2) Một cách khác để có được kết nối cần thiết là dựa trên việc chuyển sang hệ thống báo cáo hiện tại, nơi điều kiện liên hệ trở nên tầm thường. Trong hệ thống báo cáo liên quan đến nhận dạng (xem hình 1, 6), tốc độ của khối $\vec{v}_{\text{отн}}$ được hướng dọc theo bề mặt của nó, tức là nghiêng một góc $\alpha$ so với phương thẳng đứng. Viết định luật cộng vận tốc
$$\vec{v}_2 = \vec{v}_{\text{отн}} + \vec{v}_1$$
từ tam giác vector tương ứng chúng ta thu được
$$v_2 = v_1 \text{tg} \alpha, \text{и } a_2 = a_1 \text{tg} \alpha.$$
Chúng ta cùng nhau giải các phương trình (1)—(3) và tìm
$$a_1 = \frac{m_1}{m_1 + m_2 \text{tg}^2 \alpha} g,$$
$$a_2 = \frac{m_1 \text{tg} \alpha}{m_1 + m_2 \text{tg}^2 \alpha} g.$$
Trong phương pháp thứ hai bài toán này có vẻ hơi giả tạo. Tuy nhiên, trong một số trường hợp, việc lựa chọn đúng hệ thống báo cáo có thể đơn giản hóa đáng kể vấn đề liên lạc động học. Đây là một ví dụ.
Bài 2. Một hình nêm có chiều cao $h$ với góc nghiêng $\alpha$ đứng trên một mặt phẳng nằm ngang (hình 2). Khối lượng nêm $m_1$. Bắt đầu từ đỉnh nêm

cho phép một khối có khối lượng $m_2$ trượt không ma sát. Tìm gia tốc của nêm và thời gian trượt của vật.
Hãy bắt đầu với định luật thứ hai của Newton. Hãy viết nó ra cho hình nêm chiếu theo hướng ngang và cho thanh bây giờ ở dạng vectơ:
$$N \sin \alpha = m_1 a_1,$$
$$\vec{N}_{21} + m_2 \vec{g} = m_2 \vec{a}_2.$$ (5)
Như trước đây, $\vec{N}_{12} = -\vec{N}_{21}, N_{12} = N$. Việc lựa chọn hướng của các trục cho khối gắn liền với việc giải bài toán kết nối động học.
Mối quan hệ động học giữa các gia tốc sẽ phản ánh thực tế là trong quá trình chuyển động, khối luôn ở trên bề mặt của nêm. Viết điều này dưới dạng một phương trình thẳng hóa ra lại khó khăn. Thay vào đó, hãy chuyển sang hệ thống báo cáo liên quan đến cái nêm. Trong hệ thống này, tốc độ của khối $\vec{v}_{\text{отн}}$ và gia tốc của nó $\vec{a}_{\text{отн}}$ được hướng dọc theo nêm. Khi đó từ định luật cộng vận tốc
$$\vec{v}_2 = \vec{v}_{\text{отн}} + \vec{v}_1$$ ta thu được định luật cộng gia tốc (xem hình 2)
$$\vec{a}_2 = \vec{a}_{\text{отн}} + \vec{a}_1.$$ (6)
Từ đó chúng ta có thể thấy rằng việc chuyển từ ẩn số $a_1$ và $a_2$ sang ẩn số $a_1$ và $a_{\text{отн}}$ sẽ thuận tiện hơn, từ đó giải được bài toán kết nối động học. Thay đẳng thức (6) vào phương trình (5) và chiếu phương trình này lên các hướng dọc theo bề mặt nêm và vuông góc với nó, chúng ta thu được
$$m_2 g \sin \alpha = m_2 (a_{\text{отн}} - a_1 \cos \alpha),$$
$$N - m_2 g \cos \alpha = -m_2 a_1 \sin \alpha.$$ (5′′)
Từ phương trình (4), (5′′) ta tìm được
$$a_1 = \frac{m_2 \sin \alpha \cos \alpha}{m_1 + m_2 \sin^2 \alpha} g,$$
$$a_{\text{отн}} = \frac{(m_1 + m_2) \sin \alpha}{m_1 + m_2 \sin^2 \alpha} g.$$

⟦folio 59⟧

Đối với đáp số đối với câu hỏi thứ hai bài toán, chúng ta không cần tìm $a_2$, vì thời gian trượt được biểu thị chính xác theo $a_{\text{отн}}$:

$$\frac{a_{\text{отн}} t^2}{2} = \frac{h}{\sin \alpha}.$$

Từ đây là

$$t = \sqrt{\frac{2h}{a_{\text{отн}} \sin \alpha}} = \sqrt{\frac{2h(m_1 + m_2 \sin^2 \alpha)}{(m_1 + m_2) \sin^2 \alpha g}}.$$

Như đã đề cập, hạn chế chuyển động có thể được xác định không chỉ bởi sự tiếp xúc trực tiếp của các vật thể đang được xem xét, mà còn bởi sự hiện diện trong hệ thống của các phần tử được kết nối - thanh, sợi, v.v. Trong hầu hết các trường hợp, ngay cả khi điều này không được chỉ định trong các điều kiện, các phần tử được kết nối được coi là lý tưởng, tức là các sợi - không trọng lượng và không thể co giãn, thanh - không trọng lượng và hoàn toàn cứng nhắc, đối với các khối, ngoài việc không trọng lượng, việc không có ma sát cũng được coi là trục. (Trên thực tế, từ “không trọng lượng” có nghĩa là khối lượng của một phần tử nhất định không đáng kể so với khối lượng của các phần tử khác trong hệ, từ “không khối lượng” có nghĩa là việc loại bỏ một phần tử là nhỏ so với chuyển động của các phần tử trong hệ thống, v.v.) Trước khi xem các ví dụ cụ thể, chúng ta hãy tìm hiểu điều gì xảy ra sau các phần tử liên kết lý tưởng. Hãy xem xét ba trường hợp đặc biệt.

1. Sự không trọng lượng của sợi. Hãy viết định luật II Newton cho một đoạn sợi có khối lượng $\Delta m_{\text{н}}$ (hình 3, a):

$$T - T' = \Delta m_{\text{н}} a.$$

Vì $\Delta m_{\text{н}} = 0$ nên $T = T'$, tức là lực căng không thay đổi dọc theo sợi chỉ.

2. Khối không trọng lượng chuyển động và không có ma sát trên trục của nó. Để bung một khối không trọng lượng trong đó không có ma sát thì không cần mô men quay. Từ đó suy ra rằng độ căng của cùng một sợi ở cả hai mặt của khối là như nhau (hình 3, b), ngoài ra $T' - 2T = 0$, tức là $T' = 2T$.

3. Sự không trọng lượng của thanh. Điều kiện này có nghĩa là tổng lực và tổng mômen của các lực tác dụng lên thanh bằng không. Ví dụ, nếu hai lực tác dụng lên một thanh thì chúng bằng nhau về mô đun, ngược chiều và tác dụng dọc theo thanh (hình 3, c). (Không giống như sợi chỉ, thanh không chỉ có thể bị kéo căng mà còn có thể uốn cong.)

Tính không giãn và độ cứng của ren và thanh dẫn đến sự xuất hiện của các kết nối động học mà chúng ta sẽ phân tích riêng trong các nhiệm vụ sau.

Bài 3. Tìm gia tốc của các tải có khối lượng $m_1$ và $m_2$ sau khi cắt sợi chỉ trên (hình 4). Các chủ đề và khối được coi là lý tưởng.

Hãy chọn chiều dương của trục tung hướng xuống và viết định luật II Newton cho vật:

$$T + m_1 g = m_1 a_1,$$

$$m_2 g - 2T = m_2 a_2$$

(chúng ta đã học các thuộc tính của khối và luồng được mô tả ở trên).

⟦folio 60⟧

Để tìm mối liên hệ động học giữa $a_1$ và $a_2$, chúng tôi áp dụng, như chúng tôi gọi nó, phương pháp trực tiếp. Hãy viết chiều dài của sợi dây dưới dạng
$$l = x_2 + \pi R + (x_2 - x_1),$$
trong đó $x_1$ là tọa độ của tải có khối lượng $m_1$, $x_2$ là tọa độ tâm của khối, $R$ là bán kính của nó và có tính đến chiều dài của ren không thay đổi khi tải di chuyển. Sau đó, đối với việc di chuyển hàng hóa, chúng tôi nhận được thư từ
$$2\Delta x_2 - \Delta x_1 = 0,$$
Ở đâu
$$2v_2 - v_1 = 0,$$
$$2a_2 - a_1 = 0.$$ (9)
Giải chung phương trình (7)–(9), ta tìm được
$$a_1 = 2a_2 = \frac{2(m_2 + 2m_1)}{m_2 + 4m_1} g.$$
(Lưu ý rằng $a_1 > g$. Hãy nghĩ xem tại sao đáp số lại xuất hiện như vậy.)
Bài toán 4. Một thanh không trọng lượng có khối lượng bằng nhau $m$ ở hai đầu được gắn bản lề trên một trục chia chiều dài của nó theo tỷ lệ 2:1 (hình 5). Thanh được giữ ở vị trí nằm ngang và đến một lúc nào đó được thả ra. Tìm gia tốc của các vật ngay sau đó, cũng như áp suất của thanh tác dụng lên trục tại thời điểm này.

Hãy viết định luật II Newton cho tải trọng, chọn chiều dương của các trục theo hướng có gia tốc tương ứng:
$$mg - N_1 = ma_1,$$
$$N_2 - mg = ma_2,$$ (10)
trong đó $N_1$ và $N_2$ là các lực tác dụng lên tải trọng từ phía thanh. Vì tổng mômen của các lực tác dụng lên thanh không trọng lượng bằng 0 nên
$$N_1 \frac{2}{3} l - N_2 \frac{1}{3} l = 0,$$
trong đó $l$ là chiều dài của thanh. Từ đây
$$N_2 = 2N_1.$$ (12)
Vẫn còn phải viết ra mối quan hệ động học giữa $a_1$ và $a_2$. Để làm điều này, chúng ta hãy mô tả trên hình 5 vị trí của thanh sau một khoảng thời gian ngắn $\Delta t$ sau khi bắt đầu chuyển động. Từ sự giống nhau ta có

Hình 5.
Hình 6.
$$x_1 = 2x_2,$$
Ở đâu
$$v_1 = 2v_2,$$
$$a_1 = 2a_2.$$ (13)
Giải các phương trình (10)–(13) cùng nhau, ta tìm được
$$a_1 = 2a_2 = \frac{2}{5} g,$$
$$N_2 = 2N_1 = \frac{6}{5} mg.$$
Vì tổng các lực tác dụng lên thanh không trọng lượng bằng 0 nên phản lực của trục (có độ lớn bằng lực ép lên trục) bằng
$$N = N_1 + N_2 = \frac{9}{5} mg.$$
* * *

Trong nhiều bài toán được thiết kế để áp dụng định luật bảo toàn năng lượng, cần phải tìm vận tốc của các vật tại một thời điểm nhất định. Trong trường hợp này, cần thiết lập mối liên hệ động học không phải giữa các gia tốc mà giữa vận tốc của các vật thể. Đối với lời giải như vậy bài toán, sẽ rất hữu ích khi sử dụng thực tế là tổng công được thực hiện bởi bất kỳ phần tử kết nối lý tưởng nào đều bằng không. Lý do vật lý cho điều này là không có năng lượng nào có thể được lưu trữ trong một nguyên tố như vậy - không phải động năng (khối lượng của nó bằng 0),

⟦folio 61⟧

cũng không có thế năng (phần tử không bị biến dạng).

Tuyên bố cuối cùng đòi hỏi sự cam kết. Có thể chỉ ra rằng ngay cả với một biến dạng nhỏ của một thanh rất cứng (hoặc phần tử khác), thế năng biến dạng $E_p = kx^2/2$ của nó có thể lớn - xét cho cùng, nó tỷ lệ thuận với độ cứng của thanh $k$. Nhưng nếu chúng ta tính đến lực $F = kx$ phát sinh trong quá trình biến dạng vẫn hữu hạn ở $k \rightarrow \infty$ (nó được xác định bởi chuyển động của các vật gắn vào thanh), thì thế năng $E_p = F^2/(2k)$ nói chung $k$ hóa ra rất nhỏ.

Nhiệm vụ 5*). Một tải có khối lượng $M$ đầu tiên được giữ ở ngang các khối và sau đó được thả ra (hình 6). Giả sử các sợi dây và khối là lý tưởng, kích thước của các khối nhỏ so với khoảng cách 2l giữa chúng và đã biết khối lượng $m$ của các vật nặng ở hai đầu sợi dây, hãy tìm tốc độ tải tại thời điểm sợi dây tạo một góc $\alpha$ với phương thẳng đứng. Kết quả đáp số khám phá.

Tại thời điểm đang được xem xét, một tải có khối lượng $M$ được mang ở mức $H = l$ sttg $\alpha$ và các máy xúc có khối lượng $m$ đã tăng $h = l/\sin \alpha - l$ mỗi máy. Theo định luật bảo toàn năng lượng,

$$\frac{MV^2}{2} + 2\frac{mv^2}{2} - MgH + 2mgh = 0.$$ (14)

Ví dụ: để tìm mối liên hệ giữa $v$ và $V$, bạn có thể sử dụng phương pháp trực tiếp. Từ hình 6

$$l^2 + H^2 = L^2.$$

Vi phân theo thời gian (và xét đến $l' = 0$), ta thấy

$$2H \cdot H' = 2L \cdot L'.$$

Vì $L' = v$, $H' = V$ và $H/L = \cos \alpha$, chúng tôi có được kết nối cần thiết

$$v = V \cos \alpha.$$ (15)

Tuy nhiên, việc nhận trận đấu này sẽ dễ dàng hơn từ các tin nhắn sau. Vì việc xem xét $L$ từ một tải có khối lượng $M$ đến khối tại thời điểm đang xem xét tăng với tốc độ $v$ (ở tốc độ này sợi chỉ được kéo ra), nên hình chiếu của tốc độ $\vec{V}$ của tải trọng này lên hướng của sợi chỉ phải bằng $v$. Xét rằng tốc độ $\vec{V}$ được định hướng theo phương thẳng đứng, chúng ta thu được

$$\dots$$

(*) Cái này và cái bài toán tiếp theo có phần vượt quá mức bài toán thường được đưa ra trong các kỳ thi tuyển sinh đại học. Tuy nhiên, việc làm quen với họ không phải là điều vô ích đối với người nộp đơn.

Phương trình (15).

Từ phương trình (14) và (15) chúng ta tìm thấy

$$V = \sqrt{2gl \frac{M \cos \alpha + 2m(\sin \alpha - 1)}{\sin \alpha (M + 2m \cos^2 \alpha)}}.$$

Chúng ta hãy tìm hiểu xem trọng lượng trung tâm sẽ luôn giảm (chúng tôi coi các sợi chỉ rất dài) hay đến một lúc nào đó $\alpha$ nó sẽ dừng lại và bắt đầu tăng lên. Phương trình $V = 0$ (điều kiện dừng) được chuyển về dạng

$$tg \frac{\alpha}{2} = \frac{2m - M}{2m + M},$$

tức là việc dừng và di chuyển ngược hàng hóa chỉ xảy ra ở $M < 2m$. Nếu $M > 2m$ thì tải trọng trung tâm sẽ liên tục thay đổi và tốc độ của nó sẽ tăng vô hạn ($V \rightarrow \infty$ với $\alpha \rightarrow 0$ - hãy tự kiểm tra điều này). Nếu $M = 2m$, thì khi tải trung tâm được hạ xuống, hệ thống tiến đến trạng thái cân bằng, gia tốc của tải có xu hướng bằng 0 và tốc độ của chúng có xu hướng về giá trị giới hạn $V_\infty = \sqrt{gl}$ (bạn hãy tự kiểm tra điều này).

Tôi muốn bạn chú ý đến một thực tế là khi sử dụng định luật bảo toàn năng lượng, lực căng của sợi dây hoàn toàn không được đưa vào tính toán.

Ví dụ cuối cùng minh họa các phương pháp thu được các kết nối động học khi di chuyển các thanh đặc (hoặc các kết nối rắn khác). Ví dụ, khi một vật rắn chuyển động thì khoảng cách giữa hai điểm bất kỳ của nó không thay đổi.

Bài 6. Một thanh không trọng lượng có chiều dài $l$ có khối lượng $m$ ở hai đầu trượt dọc theo hai cạnh của một góc vuông bằng hai chân (hình 7, a). Tìm tốc độ của tải trọng tại thời điểm thanh tạo một góc $\alpha$ với đường chân trời. Không có ma sát. Trong thời gian đầu

⟦folio 62⟧

thời điểm thanh ở vị trí thẳng đứng.

Từ định luật bảo toàn năng lượng ta thu được

$$mg(l-y) = \frac{mv_1^2}{2} + \frac{mv_2^2}{2},$$

(16)

trong đó $y = l \sin \alpha$ là tọa độ của tải trọng thứ hai ở khoảng cách mô men. Để có được kết nối động học, bạn có thể sử dụng phương pháp trực tiếp, như đã được thực hiện trong bài toán trước đó (tự làm). Giao tiếp động học nhanh hơn và mượt mà hơn có được từ những tin nhắn như vậy. Vì khoảng cách giữa các tải không đổi nên tại mỗi thời điểm, tốc độ mà tải thứ nhất “di chuyển ra xa” khỏi tải thứ hai bằng tốc độ mà tải thứ hai “tiến tới” tải thứ nhất. Nói cách khác, hình chiếu vận tốc của tải trọng tác dụng lên thanh tại bất kỳ thời điểm nào đều giống nhau (xem hình 7, a):

$$v_1 \cos \alpha = v_2 \sin \alpha.$$

(17)

Thay (17) vào (16), ta tìm được

$$v_1 = \sqrt{2gl \sin^2 \alpha (1 - \sin \alpha)},$$

$$v_2 = \sqrt{2gl \cos^2 \alpha (1 - \sin \alpha)}.$$

Trong động học vật rắn, sự “phân tích” chuyển động phức tạp thành chuyển động tịnh tiến và chuyển động quay thường được sử dụng. Để chứng minh phương pháp này, chúng tôi áp dụng nó để thu được mối quan hệ động học (17). Trong hệ quy chiếu liên quan đến tải trọng thứ nhất, thanh thực hiện chuyển động quay thuần túy. Điều này có nghĩa là trong hệ thống này tốc độ của tải thứ hai $v_{0\mathrm{T}}$ hướng vuông góc với thanh. Áp dụng định luật cộng vận tốc $v_2 = v_{0\mathrm{T}} + v_1$ (xem hình 7, b), ta thu được sự tương ứng (17).

Có vẻ như các biểu thức tìm được cho vận tốc cho kết quả đầy đủ lời giải bài toán. Tuy nhiên, bài toán này chứa đựng một cách tiếp cận có đi có lại mà chúng tôi sẽ phân tích theo luật.

Lời giải sẽ hoàn thành nếu trọng lượng thứ hai không thể nhấc lên khỏi bức tường thẳng đứng. (Ví dụ, để làm được điều này, có thể đặt các vật nặng lên các ống mềm và thanh phải được gắn bản lề vào chúng). Tuy nhiên, trong phiên bản bài toán của chúng tôi (xem hình 7, a) ở một góc nào đó, tải thứ hai sẽ tách ra khỏi bức tường thẳng đứng, sau đó tải trọng đáp số tìm thấy sẽ không thể áp dụng được. Thực tế là xung lực ngang của hệ chỉ được xác định bởi chuyển động của tải đầu tiên, tốc độ của tải này, theo biểu thức của $v_1$, tăng đến một góc nhất định, sau đó bắt đầu giảm. Điều này có nghĩa là tại một thời điểm nào đó lực ngang bên ngoài tác dụng lên hệ phải đổi hướng. Nhưng chỉ có một lực ngang duy nhất - phản lực của bức tường thẳng đứng, không thể thay đổi hướng của nó. Như vậy, tại thời điểm phản lực của tường bằng 0 thì tải trọng thứ hai được tách ra khỏi tường. Vi phân biểu thức của $v_1$ theo thời gian, ta thấy rằng $v_1$ lớn nhất là $\sin \alpha = 2/3$. Ở góc $\alpha = \arcsin (2/3)$ thanh sẽ được tách ra khỏi bức tường thẳng đứng.

Trận chiến
1. Tìm gia tốc của thanh và nêm như ở hình 8. Không có ma sát.
2. Tìm độ căng chỉ trong hệ như ở hình 9.
3. (dành cho những người yêu thích thủ đoạn và cạm bẫy). Gia tốc của tải trong hệ thống được hiển thị trong hình 10 là bao nhiêu?
4. Tìm gia tốc của nêm tại hình 11. Không có ma sát. Gợi ý. Áp dụng phương pháp được sử dụng ở lời giải bài toán 2 trong bài viết.
