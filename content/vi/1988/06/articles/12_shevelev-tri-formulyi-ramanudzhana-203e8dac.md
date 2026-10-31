---
id: 1988-6-shevelev-tri-formulyi-ramanudzhana-203e8dac
issue: kvant_1988_6
year: 1988
number: "6"
title: Ba công thức của Ramanujan
authors:
  - Шевелёв В. С.
rubric: matematicheskiy-kruzhok
rubric_sub: Математический кружок
page_first: 54
page_last: 57
page_labels: 52-55
tag: 6MNW
lang: vi
source: kvant_digital
extraction: vision
content_sha256: 7a15052568f82312b57e3dfa449384e66884e6e431bc7119c8b1376c7e598ba7
prompt_sha256: draft-1
translated_from: content/ru/1988/06/articles/12_shevelev-tri-formulyi-ramanudzhana-203e8dac.md
source_content_sha256: bd0f5d413a30adec4e2bbdba1d45ff2362fd886b1a021dd11ba0a76360344135
translation_model: draft
translation_run: vi-draft-2026-10-31
translation_quality: draft
---

⟦folio 52⟧

Ba công thức của Ramanujan
Ứng viên Khoa học Vật lý và Toán học
V. S. SHEVELEV

Các công thức của Ramanujan luôn chứa đựng nhiều điều hơn những gì bạn tưởng tượng ngay từ cái nhìn đầu tiên...

Hardy

Trong bài viết này, chúng ta sẽ nói về ba công thức đáng chú ý của Ramanujan *), mỗi công thức chứa ba căn bậc ba ở vế trái:

$$\sqrt[3]{\frac{1}{9}} - \sqrt[3]{\frac{2}{9}} + \sqrt[3]{\frac{4}{9}} = \sqrt[3]{\sqrt[3]{2} - 1},$$

(1)

$$\sqrt[3]{\cos \frac{2\pi}{7}} + \sqrt[3]{\cos \frac{4\pi}{7}} + \sqrt[3]{\cos \frac{8\pi}{7}} =$$

$$= \sqrt[3]{\frac{5 - 3\sqrt[3]{7}}{2}},$$

(2)

Những công thức này rất khó nhầm lẫn với công thức của bất kỳ nhà toán học nào khác: chúng giống với trò tung hứng bí ẩn với các con số.

Công thức đầu tiên đơn giản hơn và chứng minh được các lập phương liên tiếp. Đối với chúng tôi, ngoài nhận thức tự nhiên, nó còn thú vị vì về cấu trúc các mối quan hệ, nó rất giống với hai mối quan hệ tiếp theo. Đối với công thức (2) và (3), ở đây không phải mọi thứ đều đơn giản như vậy. Dưới đây là một số trích dẫn thú vị về các công thức này từ tài liệu quảng cáo của V. I. Levin**):

“Những công thức này rất cơ bản nhưng rất sâu sắc. Chúng có tính đối xứng nội tại độc đáo, điều này cho thấy sự tồn tại của chúng.”

**) Bạn có thể đọc về cuộc đời và công việc của nhà toán học độc đáo này trong «Kvant» Số 10, 1987.

**) Levin V.I. Ramanujaan. - M.: Kiến thức, 1968.

⟦folio 53⟧

Chỉ có nhà toán học cấp cao nhất mới có thể.” Và một lần nữa: “Tất nhiên, những đẳng thức chính xác này là những trường hợp đặc biệt của những quan hệ tổng quát hơn nhiều mà Ramanujan đã tuyên truyền, nhưng ông ấy chưa bao giờ báo cáo bất cứ điều gì về chúng…”

Mời độc giả theo dõi chứng minh công thức (2) và (3). Ở một số chỗ anh ấy sẽ cần bút chì và giấy. Như một phần thưởng, anh ta gần như có một cơ chế bên trong để điều khiển những công thức tuyệt đẹp này và dường như anh ta sẽ có thể tự mình chứng minh một số công thức giống như công thức của Ramanujan (do tác giả tìm ra - xem Bài tập 5), và có thể tự mình nghĩ ra công thức đó.

Kết nối với công thức của Vieta

Mối liên hệ giữa lượng giác và đại số có thể dễ dàng nhận thấy trong các công thức của Ramanujan. Chúng ta hãy xem xét kỹ hơn các con số

$$\begin{cases} \cos \frac{2\pi}{7}, \cos \frac{4\pi}{7}, \cos \frac{8\pi}{7} \\ \cos \frac{2\pi}{9}, \cos \frac{4\pi}{9}, \cos \frac{8\pi}{9} \end{cases}.$$

Trước hết, điều đáng chú ý là các đối số của cosin tạo thành cấp số nhân có giá trị 2 ở cả hai bộ ba.

Lợi dụng sự chuyển đổi

$$\cos \alpha \cos 2\alpha \cos 4\alpha = \frac{\sin 2\alpha \cos 2\alpha \cos 4\alpha}{2 \sin \alpha} = \frac{\sin 4\alpha \cos 4\alpha}{4 \sin \alpha} = \frac{\sin 8\alpha}{8 \sin \alpha},$$

chúng ta có thể thiết lập các đẳng thức sau:

$$\cos \frac{2\pi}{7} \cos \frac{4\pi}{7} \cos \frac{8\pi}{7} = \frac{1}{8},$$

$$\cos \frac{2\pi}{9} \cos \frac{4\pi}{9} \cos \frac{8\pi}{9} = -\frac{1}{8}.$$

Đây là thành công đầu tiên của chúng tôi cho thấy rằng các đối số cosine trong các công thức của Ramanujan được chọn tương đối không ngẫu nhiên.

Bây giờ chúng ta hãy thử tìm tổng của ba cosin. Chúng tôi có:

$$\cos \frac{2\pi}{7} + \cos \frac{4\pi}{7} + \cos \frac{8\pi}{7} =$$

$$= \frac{2 \sin \frac{\pi}{7}}{2 \sin \frac{\pi}{7}} \left( \cos \frac{2\pi}{7} + \cos \frac{4\pi}{7} + \cos \frac{6\pi}{7} \right) =$$

$$= \frac{1}{2 \sin \frac{\pi}{7}} \left( \sin \frac{3\pi}{7} - \sin \frac{\pi}{7} + \sin \frac{5\pi}{7} \right) - \sin \frac{3\pi}{7} + \sin \pi - \sin \frac{5\pi}{7} = -\frac{1}{2};$$

$$\cos \frac{2\pi}{9} + \cos \frac{4\pi}{9} + \cos \frac{8\pi}{9} =$$

$$= \cos \frac{2\pi}{9} + \cos \frac{4\pi}{9} - \cos \frac{\pi}{9} =$$

$$= 2 \cos \frac{3\pi}{9} \cos \frac{\pi}{9} - \cos \frac{\pi}{9} = 0.$$

Cuối cùng, chúng tôi gửi số tiền sau:

$$S_1 = \cos \frac{2\pi}{7} \cos \frac{4\pi}{7} + \cos \frac{2\pi}{7} \cos \frac{8\pi}{7} + \cos \frac{4\pi}{7} \cos \frac{8\pi}{7},$$

$$S_2 = \cos \frac{2\pi}{9} \cos \frac{4\pi}{9} + \cos \frac{2\pi}{9} \cos \frac{8\pi}{9} + \cos \frac{4\pi}{9} \cos \frac{8\pi}{9}.$$

Bài tập 1. Chứng minh rằng $S_1 = -\frac{1}{2}, S_2 = -\frac{3}{4}$.

Bây giờ chúng ta hãy viết công thức Vieta cho phương trình bậc ba. Nếu $x, y, z$ là nghiệm của phương trình

$$t^3 + pt^2 + qt + r = 0,$$

thì, như đã biết,

$$\begin{cases} x + y + z = -p, \\ xy + xz + yz = q, \\ xyz = -r. \end{cases}$$

Chúng ta hãy so sánh (4) với các đẳng thức mà chúng ta thu được ở trên đối với bộ ba cos Ramanujan, chúng ta kết luận rằng bộ ba đầu tiên bao gồm các nghiệm của phương trình

$$t^3 + \frac{1}{2} t^2 - \frac{1}{2} t - \frac{1}{8} = 0,$$

và thứ hai là từ nghiệm của phương trình

$$t^3 - \frac{3}{4} t + \frac{1}{8} = 0.$$

Giai đoạn này là quan trọng nhất trong chứng minh của chúng tôi. Nó cho thấy làm thế nào

⟦folio 54⟧

và bản chất của mối liên hệ giữa các biểu thức lượng giác và đại số trong các công thức (2) và (3).

Hãy xem xét tổng của ba gốc ...

Bây giờ hãy đặt bài toán như thế này. Cho phương trình
$$t^3 + pt^2 + qt + r = 0,$$
có gốc là các số $x, y, z$. Chúng ta cần tìm tổng các căn bậc ba của chúng (chúng ta biểu thị lập phương của tổng này bằng $A$):
$$\sqrt[3]{x} + \sqrt[3]{y} + \sqrt[3]{z} = \sqrt[3]{A}.$$
(7)

Hóa ra tổng (7) rất dễ tìm cùng với một tổng khác:
$$\sqrt[3]{xy} + \sqrt[3]{xz} + \sqrt[3]{yz} = \sqrt[3]{B}.$$
(8)

Lập phương cả hai phần (7), rồi đến (8) và xét đến công thức Vieta (4), ta được (tự kiểm tra):
$$A = -p + 3\sqrt[3]{AB} + 3\sqrt[3]{r},$$
$$B = q - 3\sqrt[3]{ABr} - 3\sqrt[3]{r^2},$$
(10)

Nhân (9) với $\sqrt[3]{r}$ và cộng với (10), chúng ta biểu thị $B$ đến $A$:
$$B = q - (A + p)\sqrt[3]{r}.$$
(11)

Thay thế phương trình này vào (9), chúng ta thu được phương trình chỉ cho $A$:
$$A + p - 3\sqrt[3]{r} = 3\sqrt[3]{A(q - (A + p)\sqrt[3]{r})}.$$
(12)

Cuối cùng, bằng cách lập phương cả hai vế của phương trình, chúng ta thu được phương trình bậc ba sau cho $A$:
$$A^3 + 3(p + 6\sqrt[3]{r})A^2 + 3(p^2 + 3p\sqrt[3]{r} + 9\sqrt[3]{r^2} - 9q)A + (p - 3\sqrt[3]{r})^3 = 0.$$ (11)

Đơn giản hóa phương trình bậc ba

Cho ta một phương trình bậc ba
$$x^3 + 3bx^2 + 3cx + d = 0.$$ (12)

Chúng tôi sẽ chỉ ra cách, trong một số trường hợp đặc biệt thành công, nó có thể được đơn giản hóa.

Thay $x = z - b$ vào (12), chúng ta thu được phương trình bậc ba cho $z$, không chứa $z^2$ (kiểm tra!). Hơn nữa, nếu $b$ và $c$ trong phương trình (12) có liên hệ với nhau bởi các quan hệ
$$b^2 = c,$$
thì số hạng với $z^1$ cũng sẽ biến mất khỏi phương trình của $z$. Kết quả là, phương trình
biểu thức (12) sẽ có dạng
$$z^3 = b^3 - d.$$
Quay trở lại $x$, chúng tôi nhận được
$$x = \sqrt[3]{b^3 - d} - b.$$ (13)

Chúng ta hãy kiểm tra xem trường hợp nào điều kiện $b^2 = c$ được thỏa mãn cho phương trình (11). So sánh với (12), ta có:
$$b = p + 6\sqrt[3]{r},$$
$$c = p^2 + 3p\sqrt[3]{r} + 9\sqrt[3]{r^2} - 9q,$$
và điều kiện $b^2 = c$ có dạng:
$$3\sqrt[3]{r^2} + p\sqrt[3]{r} + q = 0.$$ (14)

Bây giờ đến một thời điểm thú vị: xét cho cùng, các số $p, q$ và $r$ được biết đến nhờ phương trình có gốc là bộ ba cosin Ramanujan (xem công thức (5) và (6))!

Đối với ba phần đầu tiên: $p = 1/2$, $q = -1/2$, $r = -1/8$; đối với bộ ba thứ hai: $p = 0$, $q = -3/4$, $r = 1/8$. Thay các giá trị này vào (14), chúng ta thu được các đẳng thức về số! Nhưng trong trường hợp này, theo (13) (tại $x = A$, $b = p + 6\sqrt[3]{r}$, $d = (p - 3\sqrt[3]{r})^3$),
$$A = \sqrt[3]{b^3 - d} - b.$$
Trong trường hợp ba trường hợp đầu tiên, $b = \frac{1}{2} - 3 = -\frac{5}{2}$, $d = \left(\frac{1}{2} + \frac{3}{2}\right)^3 = 8$, vậy
$$A = \frac{-3\sqrt{189} + 5}{2} = \frac{5 - 3\sqrt{7}}{2}.$$
Trong trường hợp bộ ba thứ hai $b = 3$, $d = \left(-\frac{3}{2}\right)^3 = -\frac{27}{8}$ và
$$A = \sqrt[3]{27 + \frac{27}{8}} - 3 = \frac{3\sqrt[3]{9} - 6}{2}.$$

Đây không phải là những biểu thức căn bản của vế phải của các công thức (2) và (3) của Ramanujan. Vì vậy, việc chứng minh đã hoàn tất.

Bài tập 2. Đặt $\sqrt[3]{x} = u$, $\sqrt[3]{y} = v$, $\sqrt[3]{z} = w$, chứng minh điều kiện (14) với $u, v, w$ không bằng 0 là tương đương với điều kiện
$$u^3 + v^3 + w^3 + \frac{(uv)^2}{w} + \frac{(uw)^2}{v} + \frac{(vw)^2}{u} + 3uvw = 0.$$ (15)

Từ chứng minh của chúng ta, điều kiện (15) được thỏa mãn bởi căn bậc ba của Ramanujan

⟦folio 55⟧

cosin (bộ ba thứ nhất và thứ hai). Dễ dàng kiểm tra trực tiếp rằng nó cũng thỏa mãn bộ ba số

$$u = \sqrt[3]{\frac{1}{9}}, v = -\sqrt[3]{\frac{2}{9}}, w = \sqrt[3]{\frac{4}{9}}.$$

Do đó, các đẳng thức (1), (2), (3) dựa trên điều kiện tổng quát (15).

Có lẽ Ramanujan biết các bộ ba số khác ($u, v, w$) thỏa mãn điều kiện (15).

Bài tập 3. Chứng minh rằng cùng với các số $u, v, w$, điều kiện (15) thỏa mãn bởi: a) các số $\frac{1}{u}, \frac{1}{v}, \frac{1}{w}$;
6) số $\sqrt[3]{u^3+uvw}, \sqrt[3]{v^3+uvw}, \sqrt[3]{w^3+uvw}$.

Bài tập 4. Chứng minh nếu điều kiện (15) thỏa mãn thì đẳng thức đúng

$$\left( \frac{u}{v} + \frac{v}{u} + \frac{u}{w} + \frac{w}{u} + \frac{w}{v} \right)^3 + 6 = \left( \frac{u}{v} \right)^3 + \left( \frac{v}{u} \right)^3 + \left( \frac{u}{w} \right)^3 + \left( \frac{w}{v} \right)^3.$$

Ví dụ: kiểm tra (16) bộ ba số $u = \sqrt[3]{\frac{1}{9}}, v = -\sqrt[3]{\frac{2}{9}}, w = \sqrt[3]{\frac{4}{9}}$. Ngược lại, có thể suy ra (15) từ (16) không?

Bài tập 5. Chứng minh đẳng thức:

$$1^\circ. \sqrt[3]{\sec \frac{2\pi}{7}} + \sqrt[3]{\sec \frac{4\pi}{7}} + \sqrt[3]{\sec \frac{8\pi}{7}} = \sqrt[3]{8-6\sqrt[3]{7}};$$

$$2^\circ. \sqrt[3]{\sec \frac{2\pi}{9}} + \sqrt[3]{\sec \frac{4\pi}{9}} + \sqrt[3]{\sec \frac{8\pi}{9}} = \sqrt[3]{6(\sqrt[3]{9}-1)};$$

$$3^\circ. \sqrt[3]{\sec 2+\sec \frac{2\pi}{7}} + \sqrt[3]{\sec 2+\sec \frac{4\pi}{7}} + \sqrt[3]{\sec 2+\sec \frac{8\pi}{7}} = \sqrt[3]{6\sqrt[3]{7}-10};$$

$$4^\circ. \sqrt[3]{\frac{1}{2}+\cos \frac{2\pi}{7}} +$$
