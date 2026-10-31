---
id: 1979-4-yantarov-kommutiruyuschie-mnogochlenyi-ab390f7c
issue: kvant_1979_4
year: 1979
number: "4"
title: Đa thức đi lại
authors:
  - Янтаров И.
rubric: matematicheskiy-kruzhok
rubric_sub: Математический кружок
page_first: 21
page_last: 25
page_labels: 19-23
tag: VM8V
lang: vi
source: kvant_digital
extraction: vision
content_sha256: 877f31d6697ad99dfc1cec62ff64c33c2c359cbdae640bc44a3b7de729537f5d
prompt_sha256: draft-1
translated_from: content/ru/1979/04/articles/10_yantarov-kommutiruyuschie-mnogochlenyi-ab390f7c.md
source_content_sha256: 4dc0ca05ff975b79bdac624912582dac02aeec3af88049bf535e1072875c8a13
translation_model: draft
translation_run: vi-draft-2026-10-31
translation_quality: draft
---

⟦folio 19⟧

I. Yanmatov

Đa thức đi lại

Từ biên tập viên
Nói chung, toán học bài toán được cung cấp cho học sinh có liên quan rất gián tiếp đến kết quả mới hoặc liên quan đến các chi tiết riêng lẻ của chúng và không mang lại cơ hội nhìn thấy toàn bộ bức tranh. Điều này có thể xảy ra bởi vì trong toán học, mọi thứ đều được kết nối với nhau và, như một quy luật, để hiểu đầy đủ ngay cả một câu hỏi hoàn toàn cơ bản, người ta phải rút ra những thông điệp từ các lĩnh vực toán học không phải tiểu học.
Bài toán về đa thức giao hoán, liên quan đến bài viết này, được coi là một ngoại lệ: ở đây có thể tiếp cận một vấn đề toán học tổng quát khá gần gũi, chỉ sử dụng các phương tiện cơ bản.
Chúng tôi biết đến bài toán này từ một bức thư gửi cho «Kvant» hai năm trước bởi E. Turkevich, người đã viết kết quả đầu tiên ở đây. Bài toán điều này, bổ sung thêm một số điểm, đã được đề xuất trong loại nghiên cứu XI của Olympic Thế giới và được đặt trong Bài toán «Kvant» (M455).

Công thức bài toán
Đa thức $P$ và $Q$ trong một biến được gọi là giao hoán *) nếu $P(Q(x)) = Q(P(x))$. Đẳng thức được viết có nghĩa là nếu ở cả hai vế của đẳng thức, chúng ta mở tất cả các dấu ngoặc và thêm các số hạng giống nhau thì chúng ta sẽ có được các đa thức giống nhau. Điều này tương đương với thực tế là với bất kỳ số thực $d$ nào thì đẳng thức số $P(Q(d)) = Q(P(d))$ đúng.

*) Từ tiếng Latin commutativus - thay đổi.

Bài tập M455 chỉ xét các đa thức có hệ số cao nhất là 1; Chúng ta sẽ gọi các đa thức như vậy là đơn nhất. (Như chúng ta sẽ thấy bên dưới, câu hỏi về đa thức giao hoán tùy ý có thể được rút gọn thành câu hỏi về đa thức có hệ số dẫn đầu bằng ±1.)

a) Với mọi số $\alpha$, hãy tìm tất cả các đa thức bậc nhiều nhất là ba giao hoán với đa thức $P(x) = x^2 - \alpha$.

b) Chứng minh rằng có nhiều nhất một đa thức có bậc cho trước giao hoán với đa thức $P$ bậc hai đã cho.

b) Tìm tất cả các đa thức bậc 4 và 8 giao hoán với đa thức $P$ bậc hai đã cho.

d) Chứng minh rằng nếu hai đa thức $Q$ và $R$ giao hoán với một đa thức $P$ bậc hai nào đó thì chúng giao hoán với nhau.

d) Chứng minh rằng tồn tại khối đa thức $P_1, P_2, \dots, P_h, \dots$ giao hoán với nhau, bậc của đa thức $P_h$ bằng $k$ và $P_2(x) = x^2 - 2$.

Lời giải bài toán a)—d)

a) Đặt $Q(x) = x^3 + ax^2 + bx + c$. Chúng ta hãy viết ra đẳng thức $P(Q(x)) = Q(P(x))$:
$x^3 + ax^2 + bx + c)^2 - \alpha = (x^2 - \alpha)^3 + a(x^2 - \alpha)^2 + b(x^2 - \alpha) + c$.

Trước khi mở ngoặc, lưu ý rằng ở bên phải chỉ có bốn lũy thừa $x$ và hệ số vết tại $x^5$ bằng 2a. Vì vậy, $a = 0$. Nhưng khi đó hệ số vết của $x^3$ bằng 2c, thì $c = 0$ cũng vậy. Vì vậy $Q(x) = x^3 + bx$. Mở ngoặc và cân bằng các hệ số, ta được hệ
$$\begin{cases} 2b = -3\alpha, \\ b^2 = 3\alpha^2 + b, \\ \alpha = \alpha^3 + b\alpha. \end{cases}$$

Đặt $\alpha = 2\gamma$, sau đó $b = -3\gamma$. Từ phương trình thứ 2 $9\gamma^2 = 12\gamma^2 - 3\gamma$, tức là $\gamma^2 - \gamma = 0$. Vì vậy, $\gamma = 0$ hoặc $\gamma = 1$. Thật dễ dàng để kiểm tra xem cả hai lời giải này đều phù hợp.

⟦folio 20⟧

Do đó, đa thức bậc 3 $Q$ giao hoán với đa thức $P(x) = x^2 - \alpha$ chỉ tồn tại với $\alpha = 0$ ($P(x) = x^2$, $Q(x) = x^3$) và cho $\alpha = 2$ ($P(x) = x^2 - 2$, $Q(x) = x^3 - 3x$).

Người ta cũng chứng minh tương tự rằng nếu bậc $Q$ bằng 2 thì $Q = P$, và nếu nó bằng 1 thì $Q(x) = x$.

Điểm này rất đơn giản. Nó được trao cho học sinh tại Thế vận hội để các em hiểu rõ hơn về các điều kiện của bài toán và làm quen một chút với nó. Ngoài ra, nếu bạn hiểu kỹ các phương trình đã được viết ra, thì sẽ nảy sinh ý tưởng về cách giải điểm 6) - một trong những điểm mấu chốt bài toán.

6) Đặt $Q(x) = x^k + a_1x^{k-1} + a_2x^{k-2} + \dots + a_{k-1}x + a_k$, $P(x) = x^2 + px + q$. Hãy viết biểu thức đẳng thức $(x^k + a_1x^{k-1} + \dots + a_k)^2 + p(x^k + \dots + a_k) + q - (x^2 + px + q)^k - a_1(x^2 + px + q)^{k-1} - \dots - a_k = 0$.

Đánh đồng các hệ số tại $x^{2k}$, $x^{2k-1}$, ..., $x$, $x^0$ với 0, ta thu được hệ phương trình cho $a_1$, $a_2$, ..., $a_k$, $p$, $q$. Việc giải hệ thống này và thậm chí chỉ đơn giản là viết nó ra cũng khá khó khăn. Tuy nhiên, dễ dàng nhận thấy các hệ số $b_1$, $b_2$, ..., $b_k$ cho lũy thừa $x^{2k-1}$, $x^{2k-2}$, ..., $x^k$ có dạng sau:

$$b_1 = 2a_1 + R_1(p, q) = 0,$$
$$b_2 = 2a_2 + R_2(p, q, a_1) = 0,$$
$$b_k = 2a_k + R_k(p, q, a_1, \dots, a_{k-1}) = 0.$$

Đây $R_i$ là một số biểu thức đại số từ $p$, $q$, $a_1$, ..., $a_{i-1}$. Từ phương trình đầu tiên, $a_1$ được biểu thị thông qua $p$ và $q$; từ giây - rằng $a_2$ được biểu thị qua $p$, $q$ và $a_1$, và do đó được biểu thị qua $p$ và $q$, ... Vì vậy, chúng ta thấy rằng tất cả các hệ số $a_1$, ..., $a_k$ được biểu thị qua $p$ và $q$, tức là các hệ số của đa thức $Q$ giao hoán với $P$, được biểu diễn duy nhất theo $p$ và $q$, đây là điều cần phải chứng minh.

Thật dễ dàng để xác minh rằng một lý luận tương tự có thể được xác minh cho bất kỳ đa thức $P$ nào, miễn là bậc của nó lớn hơn 1 (và $Q$ là đơn vị), tức là tuyên bố trong đoạn 6) là đúng với bất kỳ đa thức nào.

Điểm 6) là chìa khóa trong bài toán. Điểm c) và d) dễ dàng theo dõi từ đó.

c) Hãy chứng minh đa thức $Q(x) = P(P(x))$ giao hoán với $P$. Thật vậy, $Q(P(x)) = P(Q(x))$. Đa thức $Q$ có bậc bốn và, theo 6) là đa thức duy nhất ở bậc này giao hoán với $P$. Tương tự, người ta chứng minh rằng đa thức bậc 8 duy nhất giao hoán với $P$ là đa thức $R(x) = P(P(x))$.

d) Đặt $S(x) = Q(R(x))$ và $T(x) = R(Q(x))$. Vì $P$ giao hoán với $Q$ và $R$, nên $P(S(x)) = P(Q(R(x))) = Q(P(R(x))) = Q(R(P(x))) = S(P(x));$ có nghĩa là $P$ giao hoán với đa thức $S$. Theo cách tương tự, người ta xác minh rằng $P$ giao hoán với đa thức $T$. Hơn nữa, rõ ràng rằng $S$ và $T$ là các đa thức đơn nhất có cùng bậc (nếu $Q$ và $R$ có bậc $k$ và $l$ thì bậc của đa thức $S$ và $T$ là $kl$). Từ 6) suy ra $S = T$, tức là $Q(R(x)) = R(Q(x))$, là điều bắt buộc.

Tương tự như ở điểm 6), mệnh đề vẫn đúng nếu $P$ là đa thức bậc bất kỳ lớn hơn 1 và $Q$ và $R$ là đơn nhất.

Đa thức Chebyshev.
Lời giải điểm d)

Điểm d) khó hơn nhiều so với các điểm khác. Chúng tôi sẽ đưa ra một số cách tiếp cận khác nhau đối với lời giải của nó.

Cách đầu tiên. Hãy để $x = t + t^{-1}$. thì dễ dàng kiểm tra được $x^k$ có dạng

$$x^k = (t + t^{-1})^k = (t^k + t^{-k}) + a_1(t^k - 1 + t^{-(k-1)}) + a_2(t^k - 2 + t^{-(k-2)}) + \dots + a_{k-1}(t + t^{-1}) + a_k,$$

trong đó $a_1$, ..., $a_k$ là một số số cố định. Bằng quy nạp trên $k$ suy ra $t^k + t^{-k}$ có thể được biểu diễn dưới dạng

$$x^k + b_1x^{k-1} + \dots + b_{k-1}x + b_k,$$

trong đó $b_1$, ..., $b_k$ là một số số cố định. Chúng ta hãy biểu thị đa thức $x^k + b_1x^{k-1} + \dots + b_k$ bằng

⟦folio 21⟧

$P_k(x)$. Theo định nghĩa $P_k(t+t^{-1}) = t^k + t^{-k}$, vậy $P_k(P_l(t+t^{-1})) = P_k(t^l + t^{-l}) = t^{kl} + t^{-kl} = P_{kl}(t + t^{-1})$. Do đó, $P_k(P_l(x)) = P_{kl}(x) = P_l(P_k(x))$, tức là hai đa thức bất kỳ $P_k$ giao hoán. Kể từ $P_2(x) = x^2 - 2$, chúng ta đã xây dựng được chuỗi đa thức cần thiết.

Cách thứ hai. Hãy để chúng tôi trình bày một phương pháp thu được đa thức $P_k$ bằng cách sử dụng đa thức Chebyshev $T_k$. Chúng tôi sẽ không đưa ra định nghĩa trực tiếp về các đa thức này, nhưng chúng tôi sẽ đưa ra sự tương ứng mà chúng thỏa mãn (và xác định chúng một cách duy nhất):

$$T_k(\cos t) = \cos kt.$$

Có thể chứng minh rằng $T_k$ là đa thức bậc $k$. Dễ dàng chứng minh rằng đa thức Chebyshev giao hoán:

$$T_k(T_m(x)) = T_{km}(x) = T_m(T_k(x))$$

- thực tế là $\cos k(mt) = \cos kmt = \cos m(kt)$. Nhưng $T_k$ không phải là đa thức đơn nhất: hệ số cao nhất của nó là $2^{k-1}$. Nhược điểm này có thể dễ dàng khắc phục bằng cách “kéo dài” đối số và giá trị của đa thức theo hệ số hai bằng cách sử dụng phép đổi biến, tức là bằng cách đặt $P_k(x) = 2T_k(x/2)$. Quy trình này không vi phạm tính giao hoán (hãy kiểm tra cái này!). Một dãy đa thức Chebyshev đáng chú ý, xuất hiện trong nhiều bài toán giải tích (đặc biệt trong lý thuyết xấp xỉ hàm số bằng đa thức), hóa ra lại là một dãy đa thức giao hoán. Bằng cách này, chuỗi $P_k$ đã được E. Turkev và Part xây dựng.

Cả hai phương pháp được mô tả đều dựa trên cùng một ý tưởng. Giả sử có một hàm nào đó $f$ lấy vô số giá trị và sao cho với mọi số tự nhiên $n$

$$f(nt) = Q_n(f(t))$$

trong đó $Q_n$ là đa thức. Khi đó các đa thức $Q_m$ và $Q_n$ giao hoán. Ví dụ: nếu $f(t) = e^t$, thì chúng ta thu được đa thức chuyển mạch nối tiếp $F_n(x) = x^n$. Nếu $f(t) = e^t + e^{-t}$, thì chúng ta nhận được đa thức nối tiếp $P_n$ (đây chính xác là phương pháp xây dựng đa thức $P_n$ đầu tiên của chúng ta, chỉ có $t$ ở đây được thay thế bằng $e^t$). Nếu $f(t) = \cos t$ thì chúng ta thu được đa thức nối tiếp $T_n$. (Đối với những người quen thuộc với số phức và công thức $\cos \varphi = (e^{i\varphi} + e^{-i\varphi})/2$, thật dễ dàng tìm ra lý do tại sao hàm $e^t + e^{-t}$ và cos $t$ về cơ bản lại dẫn đến cùng một chuỗi đa thức, khoảng cách lên tới gấp đôi.)

lời giải trong đoạn e) rất đẹp, nhưng chúng có một nhược điểm: hoàn toàn không rõ làm cách nào để truy cập chúng. Chúng tôi sẽ tặng thêm một lời giải; nó sẽ bớt ngắn hơn nhưng sẽ rõ ràng nó được phát minh như thế nào và cách viết nhanh các đa thức $P_n$.

Cách thứ ba. Như sau từ điểm b), chỉ có thể có một đa thức $P_k$ bậc $k$ giao hoán với $P_2(x) = x^2 - 2$. Chúng ta hãy viết ra một vài đa thức đầu tiên như vậy:

$$P_1(x) = x,$$
$$P_2(x) = x^2 - 2,$$
$$P_3(x) = x^3 - 3x,$$
$$P_4(x) = x^4 - 4x^2 + 2,$$
$$P_5(x) = x^5 - 5x^3 + 5x,$$
$$P_6(x) = x^6 - 6x^4 + 9x^2 - 2$$

(ở đây $P_4(x) = P_2(P_2(x))$, $P_6(x) = P_2(P_3(x))$, $P_5(x)$ giống như ở điểm a)). Sau khi xem xét chuỗi đa thức này, chúng ta có thể thay thế nó thỏa mãn công thức truy hồi $P_{k+1}(x) = xP_k(x) - P_{k-1}(x)$. Thật tự nhiên khi cho rằng công thức này đúng với mọi $k > 1$.

Vì vậy, chúng ta hãy định nghĩa dãy đa thức $P_1, P_2, \dots, P_n, \dots$ bằng quy nạp, giả sử rằng

$$P_1(x) = x,$$
$$P_2(x) = x^2 - 2,$$

và tại $k > 1$

$$P_{k+1}(x) = xP_k(x) - P_{k-1}(x).$$

Hãy chứng minh rằng mọi đa thức $P_k$ đều giao hoán với đa thức $P_2$; thì tất cả đều đi lại với nhau (điểm d)).

Hãy chứng minh bằng quy nạp. Rõ ràng là các đa thức $P_1$ và $P_2$ giao hoán với $P_2$; giả sử rằng mọi đa thức $P_1, P_2, \dots$

⟦folio 22⟧

..., $P_k$ giao hoán với $P_2$, và chúng ta chứng minh rằng đa thức $P_{k+1}$ giao hoán với $P_2$.

Chúng ta cần thể hiện điều đó
$$P_{k+1}(x^2-2)=(P_{k+1}(x))^2-2.$$

Thay công thức truy hồi cho $P_{k+1}$ vào đẳng thức này, chúng ta viết lại nó dưới dạng
$$(x^2-2)P_k(x^2-2)-P_{k-1}(x^2-2)$$
$$=(xP_k(x)-P_{k-1}(x))^2-2.$$

Bây giờ chúng ta sử dụng giả định quy nạp:
$$(x^2-2)(P_k(x)^2-2)-(P_{k-1}(x)^2-2)$$
$$=(xP_k(x)-P_{k-1}(x))^2-2.$$

Mở rộng dấu ngoặc và điều kiện dẫn động, chúng ta thu được đẳng thức sau:
$$-2(P_k(x)^2-xP_k(x)P_{k-1}(x))+P_{k-1}(x)^2=2x^2-8$$

hoặc
$$P_k(x)^2-xP_k(x)P_{k-1}(x)+P_{k-1}(x)^2=4-x^2.$$

Hãy biểu thị vế trái (*) bằng $S_k(x)$. Chúng ta còn phải chứng minh rằng $S_k(x)$ không phụ thuộc vào $k$ (và bằng $4-x^2$). Thật vậy, hãy để $k>2$. Sau đó
$$S_k(x)=P_k(x)^2-xP_k(x)P_{k-1}(x)+P_{k-1}(x)^2=P_k(x)[P_k(x)-xP_{k-1}(x)]+P_{k-1}(x)^2$$
$$=-P_k(x)P_{k-2}(x)+P_{k-1}(x)^2=P_{k-2}(x)^2-xP_{k-1}(x)P_{k-2}(x)+P_{k-1}(x)^2=S_{k-1}(x),$$
tức là $S_k(x)=S_{k-1}(x)$. Vì $S_2(x)=4-x^2$, $S_k(x)=4-x^2$ cho tất cả $x \geq 2$. Vì vậy, chúng ta đã chỉ ra rằng $P_k$ giao hoán với $P_2$ với mọi $k$.

Bài toán về đa thức giao hoán

Chúng ta muốn thảo luận về bài toán liên quan đến bài toán sau: mô tả tất cả các cặp đa thức giao hoán (không nhất thiết là đơn nhất) $P$ và $Q$.

Bài toán 1. Chứng minh rằng hai đa thức $P$ và $Q$ bậc một giao hoán khi và chỉ nếu $P(x)=x+\alpha$, $Q(x)=x+\beta$ hoặc tồn tại một $x_0$ sao cho $P(x_0)=Q(x_0)=x_0$ (điểm cố định chung).

Bài toán 2. Giải bài toán tổng quát khi bậc của một trong các đa thức $P$, $Q$ bằng 1.

Trong phần tiếp theo, chúng ta sẽ giả sử rằng bậc của đa thức $P$ và $Q$ lớn hơn 1.

Đặt $P(x)=a_0x^k+a_1x^{k-1}+\cdots+a_{k-1}x+a_k$, $Q(x)=b_0x^e+\cdots+b_{e-1}x+b_e$. Trước hết, chúng tôi chứng minh rằng chúng tôi có thể quy giản bài toán tổng quát cho trường hợp các hệ số $a_1$ và $b_1$ bằng 0 (đa thức loại này được gọi là *giảm*). Để làm điều này, chúng tôi sẽ sử dụng thao tác sau. Chúng ta hãy sửa số $a$ và sử dụng nó để xây dựng từ mỗi đa thức $R$ một đa thức mới, “khớp” $R^{(a)}$ bằng cách sử dụng công thức $R^{(a)}(x)=R(x-a)+a$. Rõ ràng là đa thức $R$ có thể được xây dựng lại từ đa thức $R^{(a)}:R(x)=R^{(a)}(x+a)-a$.

Bài toán 3. a) Chứng minh rằng nếu đa thức $P$ và $Q$ giao hoán thì $P^{(a)}$ và $Q^{(a)}$ cũng giao hoán.

6) Chứng minh rằng mọi cặp đa thức giao hoán $P$ và $Q$ bậc lớn hơn 1 đều có dạng $P=S^{(a)}$, $Q=T^{(a)}$, trong đó $a$ là một số nào đó, còn $S$ và $T$ đang giao hoán các đa thức rút gọn.

Trong phần tiếp theo, chúng ta sẽ giả sử rằng các đa thức $P$ và $Q$ đã cho. Ngoài ra, chúng ta sẽ giả sử rằng chúng là đơn nhất, nghĩa là hệ số cao nhất của chúng bằng 1. Rõ ràng, đây là trường hợp đặc biệt thú vị nhất. Ngoài ra, bằng cách suy luận tương tự như cách làm ở trên, cho thấy có thể quy giản bài toán tổng quát cho trường hợp hệ số cao nhất của các đa thức $P$ và $Q$ đều bằng ±1, sao cho trường hợp riêng này không khác nhiều so với trường hợp tổng quát (trong các lập luận này cần sử dụng thao tác “kéo dài”, liên kết từng đa thức $R$ với đa thức $R^{\lambda}$ theo công thức $R^{\lambda}(x)=\lambda R(x/\lambda)$). Chúng ta hãy mô tả một số chuỗi đa thức giao hoán:

1. Giả sử $R$ là đa thức bậc $r$. Xét chuỗi đa thức $P_0(x)=x$, $P_1(x)=R(x)$, $P_2(x)=R(R(x))$, $P_3(x)=R(R(R(x)))$ (nói chung $P_{i+1}(x)=P_i(R(x))$).

Rõ ràng là mọi đa thức $P_i$ giao hoán và bậc của đa thức $P_i$ bằng $r^i$.

⟦folio 23⟧

2. Chuỗi đa thức $F_k(x) = x^k$. Tất cả các đa thức $F_k$ giao hoán và bậc của đa thức $F_k$ là $k$.

3. $\{P_k\}$ là chuỗi đa thức được xây dựng tại lời giải của điểm e) bài toán M455. Các đa thức này được xác định bởi điều kiện $P_k(t + t^{-1}) = t^k + t^{-k}$. Bậc của đa thức $P_k$ là $k$.

4. Chúng ta hãy định nghĩa chuỗi đa thức $H_1, H_3, H_5, \dots$ theo điều kiện sau: $H_k(t - t^{-1}) = t^k - t^{-k}$ (k lẻ). Thật dễ dàng để xác minh rằng các đa thức đó tồn tại và được xác định duy nhất bởi điều kiện đã viết. Tất cả các đa thức này giao hoán và bậc của đa thức $H_k$ bằng $k$.

Trên thực tế, ví dụ 3 và 4 là trường hợp đặc biệt của một ví dụ tổng quát hơn. Để mô tả ví dụ chung này, chúng ta đưa ra một nhận xét về các hệ số của đa thức. Cho đến nay chúng ta vẫn giả định rằng các hệ số này là số thực. Tuy nhiên, trong hầu hết các câu hỏi đại số, tốt hơn là nên làm việc với số phức. Do đó, hãy giả sử rằng các hệ số của đa thức của chúng ta có thể là bất kỳ số phức nào.

5. Chúng tôi sửa một số tự nhiên $m$ và một số phức $\lambda$ sao cho $\lambda^m = 1$ (với mỗi $m$ có một số $m - 1$ khác 1).

Xét các cặp số $(u, v)$ sao cho $u.v = \lambda$ và đặt $x = u + v$. Dễ dàng kiểm tra được rằng $u^k + v^k = x^k + a_1x^{k-1} + \dots + a_k$, trong đó $a_1, \dots, a_k$ là một số số, phụ thuộc vào $\lambda$. Hãy đặt $P_k(x) = x^k + a_1x^{k-1} + \dots + a_k$; đa thức $P_k$ được đặc trưng bởi điều kiện sau: $P_k(u + v) = u^k + v^k$ nếu $uv = \lambda$.

Gọi $l$ là số chia cho $m$ dư 1. Sau đó $u^lv^l = (uv)^l = \lambda^l = \lambda$, vậy $P_k(u^l + v^l) = u^{kl} + v^{kl}$. Do đó, nếu $k$ và $l$ cho số dư 1 khi chia cho $m$, thì $P_k(P_l(u + v)) = u^{kl} + v^{kl} = P_l(P_k(u + v))$, tức là các đa thức $P_k$ và $P_l$ giao hoán. Dựa vào số $\lambda$, chúng ta đã xây dựng được dãy đa thức giao hoán $P_1, P_{m+1}, P_{2m+1}$, …. Tất cả các đa thức này đều đơn nhất, rút ​​gọn và bậc $P_k$ bằng $k$.

Đối với $m = 1$, $\lambda = 1$ chúng ta lấy ví dụ 3, đối với $m = 2$, $\lambda = -1$ chúng ta lấy ví dụ 4.

Ví dụ 1–5 đã sử dụng hết tất cả các ví dụ đã biết về giao hoán đa thức, vì vậy chúng ta có thể đưa ra giả thuyết rằng nếu $P$ và $Q$ đang giao hoán các đa thức rút gọn đơn nhất bậc lớn hơn 1 với các hệ số phức, thì chúng được đưa vào một trong các chuỗi được xây dựng trong Ví dụ 1, 2, 5.

Không giải được bài toán tổng quát, bạn có thể thử trả lời một số câu hỏi từng phần:

1. Với $\alpha$ thì đa thức $P(x) = x^2 - \alpha$ giao hoán với một đa thức bậc lẻ nào đó.

2. Giả sử $P$ là một đa thức đơn nhất có bậc lớn hơn 1. Hãy lưu ý bậc của tất cả các đa thức đơn nhất $Q$ giao hoán với $P$. Tập hợp con số tự nhiên nào có thể dẫn đến kết quả này?

Ví dụ, trong ví dụ 1 đây là cấp số nhân; trong ví dụ 5 - số học.

3. Cho $P, Q$ giao hoán các đa thức đơn nhất bậc $k$ và $l$. Giả sử $l$ chia hết cho $k$. Có đúng là $Q$ có dạng $Q(x) = P(R(x))$, trong đó $R$ là đa thức đơn nhất giao hoán với $P$?

Bạn có thể hình thành một bài toán tổng quát hơn - tìm tất cả các hàm hữu tỉ giao hoán $P$ và $Q$. Trong trường hợp này, nhiều ví dụ thú vị mới xuất hiện.

Phương pháp chung mà chúng ta đã thảo luận ở lời giải của đoạn e) cho đa thức cũng phù hợp ở đây. Giả sử tồn tại một hàm $f$ (nhận vô số giá trị) sao cho

$$f(nt) = P_n(f(t)),$$

trong đó $P_n$ là hàm hữu tỉ. Sau đó, đối với các hàm $n$ và $m$ khác nhau, các hàm $P_n$ và $P_m$ chuyển đổi.

Một câu hỏi thú vị được đặt ra: đối với những hàm nào $f$, với bất kỳ $n$ nào, chúng ta có thể chọn một hàm hữu tỷ $P_n$ sao cho $P_n(f(t)) = f(nt)$. Ví dụ: có thể dễ dàng kiểm tra xem hàm $f(t) = tg t$ có thỏa mãn điều kiện này hay không.

Có thể xây dựng các ví dụ khác về hàm $f$ bằng cách sử dụng lý thuyết hàm elip. Vì đây không phải là một lý thuyết cơ bản nên chúng ta sẽ không mô tả các cách xây dựng tương ứng ở đây.

Tất cả những ví dụ này cho thấy rằng bài toán về việc mô tả các đa thức giao hoán (và nói chung hơn là giao hoán các hàm hữu tỷ) có liên quan trực tiếp đến các lý thuyết toán học rất sâu sắc và phong phú. Lời giải điều này bài toán rõ ràng sẽ tiết lộ một số sự thật mới, chưa được biết đến trước đây. Nói tóm lại, đây là một khoản vay đáng bài toán.
