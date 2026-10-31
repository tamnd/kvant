---
id: 1975-6-resheniya-zadach-m292-m295-f300-f302-ddae61ac
issue: kvant_1975_6
year: 1975
number: "6"
title: Lời giải bài toán M292—M295; F300—F302
rubric: zadachnik-kvanta
rubric_sub: Задачник «Кванта»
page_first: 26
page_last: 32
page_labels: 24-30
tag: JEZ2
lang: vi
source: kvant_digital
extraction: vision
content_sha256: 6b0f7f575343d25ad16f127e01a197611c49e8ccf50bfd7547f2ea766074ec68
prompt_sha256: draft-1
translated_from: content/ru/1975/06/articles/10_resheniya-zadach-m292-m295-f300-f302-ddae61ac.md
source_content_sha256: 8fc3d2cc9ac2e44bb724856e129fd876e570d278ef1ac18677130fc5b7ce4705
translation_model: draft
translation_run: vi-draft-2026-10-31
translation_quality: draft
---

⟦folio 24⟧

Lời giải bài toán

M292. Các số từ 1 đến 50 được viết trên bảng. Chúng ta được phép xóa hai số bất kỳ và viết chúng lại thành một số - mô đun hiệu của chúng. Sau khi lặp lại quy trình này nhiều lần, một số vẫn còn trên bảng. Đây có thể là số mấy?

Đáp số. Bất kỳ số lẻ nào nhỏ hơn 50, tức là một trong 25 số 1, 3, 5,..., 49.

Đầu tiên chúng ta hãy chỉ ra rằng bất kỳ số nào trong số này đều có thể thu được. Chúng ta muốn lấy số 2m+1 (m=0,1,...,24). Việc chia các số từ 1 đến 50 thành các cặp như sau: (1, 2m+2), (2, 3), (4, 5), ..., (2m, 2m+1), (2m+3,2m+4), ..., (49, 50). Chúng ta hãy cùng nhau viết ra mô hình hiệu của các số có trong đó: 2m+1, 1, ..., 1 (24 đơn vị). Nó vẫn còn để loại bỏ các đơn vị. Để làm điều này, bạn có thể chia chúng thành từng cặp để có 12 số 0, sau đó loại bỏ các số 0 (thay vì cặp (a, 0), chúng ta có thể viết một số |a−0|=a).

Bây giờ chúng ta sẽ chứng minh rằng không thể tìm được số nào khác ngoài 1, 3, 5,...,49. Trước hết, rõ ràng là bất kỳ số nào được viết trên bảng sẽ nằm trong khoảng từ 0 đến 50 (nếu 0<a<50, 0<b<50, thì 0<a−b<50). Hãy chứng minh rằng số thu được nhất thiết phải là số lẻ. Chúng ta hãy theo dõi tổng của tất cả các số được viết trên bảng. Lúc đầu nó bằng nhau

$$1+2+3+\dots+50=25\cdot51,$$

nghĩa là, kỳ quặc. Nhưng thay cặp (a, b) bằng một số duy nhất |a−b| không làm thay đổi tính chẵn lẻ của toàn bộ tổng, vì các số a+b và |a−b| luôn có cùng tính chẵn lẻ (cả hai đều là số chẵn hoặc cả hai đều là số lẻ). Do đó, tổng các số được viết ở mỗi bước, kể cả số cuối cùng, khi còn một số, sẽ là số lẻ.

Có thể chứng minh rằng trong trường hợp tổng quát hơn, khi viết các số từ 1 đến n lên bảng ngay từ đầu thì ở cuối bảng có thể thu được bất kỳ số nguyên k nào sao cho 0<k<n và k có cùng tính chẵn lẻ với n(n+1)/2 (nghĩa là k chẵn nếu n chia cho 4 có số dư là 3 hoặc 0, và lẻ nếu số dư là 1 hoặc 2).

◆

Hãy thử chứng minh giới hạn này là gì (giả sử rằng có một giới hạn khác đã được chứng minh). Từ điều kiện bài toán suy ra rằng $C_{n+1}C_{n+2}$ là lưỡng tính của góc của tam giác $C_nC_{n+1}O$ (Hình 1), do đó

$$2\gamma_{n+1}+\gamma_n+\alpha=\pi.$$

Nếu giới hạn lim $\gamma_n$ tồn tại và bằng $\beta$, thì chuyển sang giới hạn trong đẳng thức (1), chúng ta thu được

$$2\beta+\beta+\alpha=\pi,$$

Ở đâu

$$\beta=(\pi-\alpha)/3.$$

Bây giờ chúng ta sẽ chứng minh rằng $\gamma_n$ số thực có xu hướng đạt tới giới hạn $\beta=(\pi-\alpha)/3$. Hãy xem sự khác biệt giữa $\gamma_n$ và $\beta$ thay đổi như thế nào khi n tăng. Hãy thay đổi (1) như thế này:

$$2\left(\gamma_{n+1}-\frac{\pi-\alpha}{3}\right)=\frac{\pi-\alpha}{3}-\gamma_n.$$

Suy ra |$\gamma_{n+1}-\beta$|=|$\gamma_n-\beta$|/2, tức là sự khác biệt giữa $\gamma_n$ và $\beta$ khi chuyển từ n sang n+1 giảm đi một nửa. Do đó, |$\gamma_n-\beta$|=|$\gamma_1-\beta$|/2$^{n-1}$ có xu hướng về 0, tức là giới hạn $\gamma_n$ là có thật và bằng $\beta=(\pi-\alpha)/3$.

⟦folio 25⟧

M294. Chứng minh rằng nếu $a, b, c, d, x, y, u, v$ là số thực $u abcd > 0$ thì $(ax + bu)(av + by)(cx + dv) \times (cu + dy) \geq (acuvx + bcuxy + advxy + bduvy) \times (acx + bcu + adv + bdy)$.

M295. Các phần của đa tạp lồi của một tam giác bởi các mặt phẳng song song $p_0, p_1, p_2$ ($p_1$ nằm giữa $p_0$ và $p_2$ ở cùng một khoảng cách $h$ so với $u$ khác của tôi), chúng ta có diện tích lần lượt là $S_0, S_1$ và $S_2$. Không có đỉnh nào của đa tạp nằm giữa $p_0$ và $p_2$.
a) Chứng minh rằng
$$2\sqrt{S_1} \geq \sqrt{S_0} + \sqrt{S_2}.$$
b) Trong trường hợp nào thì bất đẳng thức trở thành đẳng thức?
e) Tìm diện tích $S_t$ của một phần của đa tạp theo mặt phẳng song song với $p_0$ và nằm cách $th$ một khoảng từ $p_0$ và $(2-t)$ từ $p_2$ ($0 < t < 2$).
e) Tìm thể tích của đa tạp chứa giữa các mặt phẳng $p_0$ và $p_2$.

Hình 2.
Hình 3.
Hình 4.

Nếu bạn mở tất cả các dấu ngoặc, thì trong mỗi phần của bất đẳng thức, bạn nhận được 16 số hạng, trong đó có 12 số hạng giống nhau và bị hủy. Các số hạng còn lại sau khi đưa các số hạng tương tự tạo thành bất đẳng thức hiển nhiên sau, tương đương với số hạng ban đầu:
$$abcd (xy - uv)^2 \geq 0.$$

Chúng ta hãy biểu thị phần của khối đa diện nằm giữa các mặt phẳng $p_0$ và $p_2$ bằng $M$; đến $V$ là thể tích của khối đa diện lồi $M$. Theo điều kiện, tất cả các đỉnh $M$ đều nằm trong mặt phẳng $p_0$ và $p_2$. Trong các hình, chúng ta sẽ mô tả các đỉnh và cạnh của khối đa diện $M$, nằm trong mặt phẳng $p_2$, làm màu phần đầu, trong $p_0$ - màu xanh lục và phần của mặt phẳng $p_1$ - màu đỏ.

Trước tiên hãy xem xét một vài ví dụ.
1°. $M$—nhận biết các căn cứ trong mặt phẳng $p_0$ và $p_2$ (Hình 2). Khi đó $S_t = C$ (giá trị không đổi), một phần, $S_0 = S_1 = S_2 = C$, do đó đẳng thức giữ nguyên
$$2\sqrt{S_1} = \sqrt{S_0} + \sqrt{S_2}$$

và $V = 2S_0h$ (chiều cao của đối tượng địa lý là 2h).
2°. $M$ là một paramid hình tam giác có đỉnh nằm trong mặt phẳng $p_0$ và đáy nằm trong mặt phẳng $p_2$ (Hình 3). Khi đó kích thước tuyến tính của một phần bởi một mặt phẳng song song với $p_0$ tỷ lệ thuận với khoảng cách của mặt phẳng này với $p_0$, sao cho $S_t$ tỷ lệ với $t^2$: $S_t = At^2$, sao cho
$$S_0 = 0, S_1 = A, S_2 = 4A,$$
và đẳng thức (*) lại được thỏa mãn; đồng thời $V = 2S_2h/3$.
3°. $M$ là một tham số tam giác cụt có các đáy trong mặt phẳng $p_0$ và $p_2$ (Hình 4). Sau đó $S_t = A(t - \tau)^2$ (điều này được xác định bởi khoảng cách $|\tau|$ từ mặt phẳng $p_0$ phần mở rộng của các mặt bên của giao điểm paramid; $\tau > 2$ hoặc $\tau < 0$, tùy thuộc vào điểm giao nhau của phần mở rộng của các mặt bên nằm cùng phía với $p_0$ với $p_2$ hay ở phía bên kia), do đó
$$S_0 = A\tau^2, S_1 = A(1 - \tau)^2, S_2 = A(2 - \tau)^2.$$

Kiểm tra xem đẳng thức (*) có giữ nguyên không và $A$ và $\tau$ có thể được biểu thị dưới dạng $S_0$ và $S_2$ như thế này:
$$\frac{\tau - 2}{\tau} = \sqrt{\frac{S_2}{S_0}} \Rightarrow \tau = \frac{2\sqrt{S_0}}{\sqrt{S_0} - \sqrt{S_2}};$$
$$A = \left(\frac{\sqrt{S_0} - \sqrt{S_2}}{2}\right)^2.$$

Âm lượng của $V$ bằng $2(S_0 + \sqrt{S_0}S_2 + S_2)h/3$ (có thể tìm thấy sự khác biệt giữa âm lượng của hai paramid không bị cắt cụt: $V = \frac{S_0h\tau}{3} - \frac{S_2h(\tau - 2)}{3}$).

Tất nhiên, ví dụ 2° có thể được coi là một phần của trường hợp 3°.
4°. $M$ là một đặc điểm hình tam giác nằm nghiêng (Hình 5, a). Có $S_t = B(2 - t)$ ở đây, vậy
$$S_0 = 2B, S_1 = B, S_2 = 0,$$
và bất đẳng thức được thỏa mãn
$$2\sqrt{S_1} > \sqrt{S_2} + \sqrt{S_0},$$
a $V = S_0h$ (Hình 5, b).

⟦folio 26⟧

5°. M là một tham số tam giác có hai đỉnh thuộc $p_0$, và hai - $p_2$ (Hình 6, a). Sau đó $S_t$ là diện tích hình bình hành có độ dài cạnh phụ thuộc tuyến tính vào $t$, và chuyển sang 0 khi $t=0$, và cái kia tại $t=2$, Đó là lý do tại sao $S_t=At$ (t—2), vậy $S_0=S_2=0$, $S_1=-A$ và bất đẳng thức (**) được thỏa mãn. Âm lượng $V$ ở đây bằng nhau $4S_1h/3$ (Hình 6, b).

6°. M là một khối đa diện trong đó tất cả các mặt cắt song song với $p_0$ và $p_2$ đều là hình bình hành (có thể suy biến ở $t=0$ hoặc $t=2$ - xem Hình 7). Ví dụ này bao gồm 4°, 5°, paralelopps, một paramid bị cắt cụt với hình bình hành ở đáy và các khối đa diện khác. Ở đây chúng ta chỉ lưu ý rằng độ dài của cạnh này và cạnh kia của hình bình hành phụ thuộc tuyến tính vào $t$ (hoặc hoàn toàn không phụ thuộc vào $t$), do đó $S_t$ được biểu thị bằng hàm có dạng $S_t=C$, $S_t=B(t-\tau_0)$ hoặc $S_t=A(t-\tau_1)(t-\tau_2)(\tau_j$-các số không thuộc khoảng ]0;2[).

Bây giờ chúng ta trình bày sơ đồ lời giải bài toán trong trường hợp tổng quát, để lại chi tiết chứng minh cho người đọc.

Bất kỳ khối đa diện nào $M$ đều có thể được rút gọn thành những khối đã được xem xét bằng cách sử dụng một hoặc một trong các phương pháp sau:

(P). $M$ có thể được cắt thành các paramid hình tam giác (loại 2° và 5°) bởi một số mặt phẳng nhất định đi qua các đỉnh của nó (Hình 8, a-e).

(D). Nếu $M$ khác với khối đa diện loại 6°, thì bằng cách mở rộng một số mặt của nó, chúng ta có thể sử dụng một số tham số và nhận dạng cắt ngắn hình tam giác (loại 3° và 2° và 1°) thành đa giác $M$ thành một tham số hoặc nhận dạng cắt ngắn hình tam giác (Hình 8, e).

Định lý 1. Diện tích mặt cắt ngang $S_t$, là hàm của $t$, được biểu thị cho mọi khối đa diện $M$ bằng một tam thức bình phương:

$$S_t=At^2+Bt+C,$$

và phân biệt đối xử là một tam thức không âm:

$$B^2-4AC\geq 0$$

và bằng 0 molko đối với các tham số được công nhận và tham số (bao gồm cả các tham số bị cắt cụt) có đáy trong các mặt phẳng $p_0$ và $p_2$.

Bổ đề a. Đặt $F(t)=At^2+Bt+C\geq 0$ nằm trên đoạn $a\leq t\leq b$. Khi đó đồ thị của hàm $y=\sqrt{F(t)}$ trên đoạn này lồi lên nếu $B^2-4AC>0$, lồi xuống dưới nếu $B^2-4AC<0$ và là đoạn thẳng (hoặc gồm các đoạn của hai đường thẳng) nếu $B^2-4AC=0$. (Chúng ta gọi đồ thị của hàm $y=f(t)$ trên đoạn $[a,b]$ lồi lên trên nếu với bất kỳ điểm $c$, $c-d$ và $c+d$ của đoạn này thì bất đẳng thức là lồi—xem Hình 9.)

Rõ ràng là từ Định lý 1 và bổ đề, mệnh đề a) bài toán M295 và đáp số cho câu hỏi 6) và c) như sau:

6) đẳng thức (*) chỉ đúng với các paramid, các paramid được nhận dạng và cắt cụt có đáy trong các mặt phẳng $p_0$ và $p_2$.

c) $S_t=At^2+Bt+C$, trong đó $A,B$ và $C$ được xác định từ hệ phương trình $S_0=C$, $S_1=A+B+C$, $S_2=4A+2B+C$; từ đây

$$S_t=\frac{S_2-2S_1+S_0}{2}t^2-\frac{3S_0-4S_1+S_2}{2}t+S_0.$$

Để tìm thể tích của $V$, những người quen thuộc với phép tính tích phân ban đầu có thể chỉ cần lấy tích phân $S_t$ từ $t=0$ đến $t=2$ và nhân kết quả với $h$. Tuy nhiên, ngay từ đầu, rõ ràng là nếu công thức được yêu cầu tồn tại (nghĩa là phạm vi của biểu thức hành động thông qua $S_0$, $S_1$, $S_2$ và $h$), thì nó phải có dạng $V=(\alpha S_0+\beta S_1+\alpha S_2)h$ và các số $\alpha$ và $\beta$

⟦folio 27⟧

dễ dàng tìm thấy từ năm ví dụ được thảo luận. Do đó, chúng ta đi đến định lý sau, cho kết quả đáp số cho câu hỏi d).

Định lý 2. *Thể tích V của khối đa diện M bằng* $(S_0+4S_1+S_2)h/3$.

Để kết luận, chúng tôi sẽ đưa ra một số gợi ý cho bằng chứng của tất cả các tuyên bố được đưa ra.

Các phát biểu (P) và (D) có thể được chứng minh bằng quy nạp theo số đỉnh hoặc số mặt của khối đa diện M.

Trong chứng minh Định lý 1, sẽ thuận tiện khi sử dụng (E) - nếu $M\bigcup П_1\bigcup...\bigcup П_n=П_0$ và $S_t^i (i=0, 1,..., n)$ là diện tích mặt cắt ngang của khối đa diện $П_i$ (hình chóp cụt và hình lăng trụ), thì

$$S_t=S_t^{(0)}-S_t^{(1)}-...-S_t^{(n)}=At^2+Bt+C,$$

trong đó mỗi $S_t^{(i)}$ là $C_i$ hoặc $A_i(t-\tau_i)^2$; vì $S_t\geqslant0$ cho $0\leqslant t\leqslant2$ và (nếu $S_t$ không phải là hằng số) $At^2+Bt+C$ nhận các giá trị không dương (nếu $S_t^{(0)}=A^{(0)}(t-\tau_0)^2$ thì cho $t=\tau_0$, nếu $S_t^{(0)}=C_0$ thì với $t$ đủ lớn), $S_t=At^2+Bt+C$ có nghiệm thực, tức là $B^2-4AC\geqslant0$.

Để chứng minh bổ đề, sẽ rất hữu ích khi sử dụng tính chất “có nghiệm thực” và hướng lồi của đồ thị được bảo toàn nếu chúng ta nhân tam thức với một số dương hoặc chuyển sang một tam thức mới bằng cách sử dụng phép biến đổi tuyến tính của biến $t=pt^*+q$ ($p$ và $q$ là bất kỳ số nào, $p\neq0$). Đối với những người đã làm quen với các đường cong bậc hai từ các bài viết của I. N. Bronstein («Kvant», Số 1, 3, 4), chúng tôi lưu ý rằng trong trường hợp $B^2-4AC>0$ đồ thị của $y=\sqrt{F(t)}$ sẽ là một phần của hình elip hoặc hyperbol, tiêu điểm của chúng nằm trên trục $Ot$, và trong trường hợp $B^2-4AC<0$ - một phần của một hyperbol có đoạn nối các tiêu điểm vuông góc với $Ot$.

Để chứng minh Định lý 2, tốt hơn nên sử dụng (P) - khi đó công thức $V$ là đủ để kiểm tra tứ diện $2^\circ$ và $5^\circ$.

N. B. Vasiliev

◆

⟦figure⟧
Hình 8, c.

⟦figure⟧
Hình 8, thành phố

⟦figure⟧
Hình 8, d.

⟦figure⟧
Hình 9.

F300*). *Tìm độ cao của chất lỏng khi mao mạch hình nón giãn nở và co lại. Quá trình làm ướt đã hoàn tất. Góc ở đỉnh của hình nón tạo thành mao quản là $2\alpha$. Góc này được coi là nhỏ. Hệ số căng bề mặt chất lỏng $\sigma$.*

---
*) Lời giải bài toán F299 sẽ được đăng ở số tiếp theo.

⟦column⟧

Vì quá trình làm ướt hoàn toàn nên bề mặt tự do của chất lỏng trong mao quản là một phần của bề mặt hình cầu nội tiếp hình nón. Bán kính của quả cầu này $R$ bằng $r/\cos\alpha$, trong đó $r$ là bán kính của mao quản ở độ cao mà chất lỏng dâng lên (Hình 10, 11). Dưới bề mặt hình cầu lõm có bán kính $R$, áp suất trong chất lỏng nhỏ hơn áp suất khí quyển $p_д=\dfrac{2\sigma}{R}=\dfrac{2\sigma\cos\alpha}{r}$ và bằng $p=p_0-p_д=p_0-\dfrac{2\sigma\cos\alpha}{r}$. Ở mức bề mặt của chất lỏng trong một bình rộng, áp suất trong mao quản là $p+\rho gh$ và rõ ràng là bằng áp suất khí quyển $p_0$. Kể từ đây,

$$p_0-\dfrac{2\sigma\cos\alpha}{r}+\rho gh=p_0,\quad\text{или}\quad \rho gh=\dfrac{2\sigma\cos\alpha}{r}.\qquad(1)$$

Chúng ta biểu thị bằng $r_0$ bán kính của mao quản ở mức bề mặt chất lỏng trong một bình rộng. Sau đó $r=r_0+h\,\mathrm{tg}\,\alpha$ trong trường hợp mao mạch giãn nở và $r=r_0-h\,\mathrm{tg}\,\alpha$

⟦folio 28⟧

với mao quản khô. Hoặc, đối với cả hai trường hợp, $r = r_0 + kh \text{tg} \alpha$, trong đó $k = 1$ dành cho mao quản giãn nở và $k = -1$ dành cho mao quản khô. Khi tính đến điều này, chúng tôi viết lại (1) dưới dạng

$$\rho gh = \frac{2\sigma \cos \alpha}{r_0 + kh \text{tg} \alpha}.$$

(2)

Đối với $\alpha = 0$ phương trình này cho kết quả đã biết $h = \frac{2\sigma}{\rho g r_0}$. Nếu $\alpha$ không bằng 0 thì từ (2) ta thu được phương trình bậc hai

$$k \rho g \text{tg} \alpha h^2 + \rho g r_0 h - 2\sigma \cos \alpha = 0.$$

(3)

Giải phương trình này, ta tìm được

$$h_{1,2} = \frac{-\rho g r_0 \pm \sqrt{(\rho g r_0)^2 + 8k \rho g \sigma \sin \alpha}}{2k \rho g \text{tg} \alpha}$$

(4)

Trong trường hợp mao quản giãn nở (ở $k = 1$), chỉ có một giá trị dương cho nghiệm của phương trình (3):

$$h = \frac{-r_0 + 1 \sqrt{r_0^2 + 8\sigma \sin \alpha/\rho g}}{2 \text{tg} \alpha}$$

Chất lỏng trong mao mạch giãn nở sẽ tăng lên đến độ cao này.

Trong trường hợp mao quản khô ($k = -1$), nếu $\rho g r_0^2 > 8\sigma \sin \alpha$ thì gốc có thể dương tính và do đó cần kiểm tra đáp số chi tiết hơn. Để làm điều này, hãy quay lại phương trình (2). Biểu thức ở vế trái của phương trình là áp suất thủy tĩnh của cột chất lỏng có chiều cao $h$; hãy biểu thị nó $p_r$. Biểu thức ở bên phải là áp suất “hỗ trợ” bổ sung $p_d$, phát sinh do tác động của lực căng bề mặt. Chúng ta hãy vẽ bằng một đồ thị về sự phụ thuộc của $p_r$ và $p_d$ vào $h$ (Hình 12). Các điểm giao nhau của đồ thị tương ứng với các giá trị tìm được $h_1$ và $h_2$, tức là vị trí cân bằng của chất lỏng trong mao quản. Chúng ta hãy xem xét cả hai điều khoản này. Để $h = h_1$ và theo một số nguyên tắc ngẫu nhiên, mức chất lỏng tăng nhẹ. Trong trường hợp này, $p_d$ sẽ tăng ít hơn $p_r$, do đó, bề mặt chất lỏng sẽ hạ xuống, trở về mức $c = h_1$. Khi $h$ giảm, $p_d$ sẽ giảm ít hơn $p_r$, do đó, bề mặt chất lỏng sẽ tăng lên. Điều này có nghĩa là vị trí cân bằng của chất lỏng không ổn định. Tương tự, xét vị trí cân bằng $h = h_2$, có thể chứng minh rằng nó không ổn định. Nếu mức chất lỏng thay đổi sẽ tiếp tục giảm xuống $h_1$, còn nếu $h$ tăng thì sẽ tăng lên đến ranh giới trên của mao quản.

Tại $\rho g r_0^2 = 8\sigma \sin \alpha$ chỉ có một giá trị gốc, đồ thị $p_r$ và $p_d$ (đường đứt nét trong hình) chạm vào điểm $h = \frac{r_0}{2 \text{tg} \alpha}$.

Trong trường hợp này, vị trí cân bằng của chất lỏng không ổn định, nếu mức chất lỏng tăng nhẹ sẽ tiếp tục giảm đến ranh giới mao quản. Tại $\rho g r_0^2 < 8\sigma \sin \alpha$ không có vị trí cân bằng nào cả và chất lỏng phải chạm tới đỉnh mao quản.

⟦folio 29⟧

F301. Một thấu kính Kruezda có đường kính D gồm hai nửa có đường kính nối với nhau. Tiêu cự của một trong số chúng là F, cái còn lại là 2F. Cách vật một khoảng a có một nguồn sáng, cách một khoảng 2a ở phía bên kia thấu kính có một màn ảnh. Vẽ đồ thị biểu diễn sự phụ thuộc độ rọi của ảnh nguồn trên màn vào khoảng cách từ nguồn màn tới trục quang của thấu kính. Bộ chuyển đổi nằm trên trục quang của ống kính, màn hình vuông góc với trục này.

Hai nửa thấu kính tạo thành một hệ quang học gồm hai thấu kính có tiêu cự F (lin cho L1) và 2F (lin cho L2). Trục quang của các thấu kính này trùng nhau. Theo định nghĩa, độ chiếu sáng phụ thuộc vào quang thông tới trên màn hình và diện tích của điểm trên màn hình. Trong trường hợp của chúng tôi, khi xác định vị trí của nguồn, mỗi ống kính sẽ tạo ra điểm sáng riêng trên màn hình, vì khoảng cách ống kính là khác nhau. Độ lớn của các luồng ánh sáng truyền qua thấu kính là như nhau, vì diện tích của thấu kính là như nhau, và do đó chứa các góc đặc trong đó các luồng ánh sáng rơi trên màn hình. Do đó, độ sáng của màn hình được xác định bởi kích thước của vùng hình ảnh. Rõ ràng, khi vị trí của nguồn thay đổi thì vị trí ảnh của nó cũng thay đổi, do đó diện tích của điểm trên màn hình và độ sáng của ảnh trên màn hình cũng thay đổi.

Hình 13.

Sử dụng công thức thấu kính, ta thấy ảnh nguồn cách thấu kính một khoảng f1 = Fa/a - F và f2 = 2Fa/a - 2F. Hãy khoảng cách một số vị trí của nguồn.

Với a < F f1 < 0 và f2 < 0, nghĩa là cả hai ảnh nguồn đều tối thiểu. Các tia ở Hình 13 rơi trên màn. Các tia này trên màn hình không chồng lên nhau mà thấu kính chiếu sáng phần màn hình và tự tạo ra ánh sáng trên đó. (Hãy nhớ lại rằng trong quang học hình học, các chùm tia đồng trục hẹp được xem xét, do đó điểm sáng trên màn hình nhỏ và chúng ta có thể giả sử rằng độ chiếu sáng ở bất kỳ vị trí nào trong điểm là như nhau.) Bên phải trong hình là biểu đồ biểu thị sự phụ thuộc của độ chiếu sáng vào khoảng cách x đến trục quang.

Với F < a < 2F f1 > 0 và f2 < 0. Ảnh của nguồn ở thấu kính thứ nhất là ảnh thật và ở thấu kính thứ hai là tối thiểu. Tuy nhiên, sự phân bố độ sáng phụ thuộc vào việc f1 lớn hơn hay nhỏ hơn khoảng cách tới màn hình 2a. Điều này tương ứng với F < a < 3/2 F và 3/2 F < a < 2F sau.

⟦folio 30⟧

Hình 15.

Các chùm tia và đồ thị chiếu sáng cho những trường hợp này được thể hiện trong Hình 14 và 15.

Và cuối cùng, đối với $a > 2F$ cả hai hình ảnh nguồn đều hợp lệ và $f_1 < 2a$ và $f_2$ có ​​thể lớn hơn hoặc nhỏ hơn $2a$. Nếu $2F < a < 3F$ thì $f_2 > 2a$; Đường đi của tia sáng và đồ thị chiếu sáng tương tự như trường hợp được hiển thị trong Hình 15. Nếu $a > 3F$, thì $f_2 < 2a$, cách xây dựng và đồ thị tương tự như trường hợp tương ứng với Hình 14. Hãy tự mình xem nhé.

F302. Phía sau con cáo chạy thẳng và đều với tốc độ $v_1$, một con chó chạy theo sau, tốc độ với $v_2$ không đổi có giá trị tuyệt đối và luôn hướng về phía con cáo. Tại thời điểm khi tốc độ $v_1$ và $v_2$ hóa ra có giá trị vượt trội lẫn nhau, hãy coi sự khác biệt giữa con cáo và con chó bằng $l$. Gia tốc của con chó lúc này là bao nhiêu?

Vì giá trị tuyệt đối của tốc độ của con chó không đổi và chỉ có hướng của tốc độ thay đổi nên gia tốc của con chó có hướng vuông góc với vectơ tốc độ. Để tìm gia tốc của con chó, chúng ta lợi dụng thực tế là bất kỳ quỹ đạo nào của một điểm vật chất trong một khoảng thời gian rất ngắn đều có thể được coi là một đường tròn khác. Khi đó gia tốc của con chó được biểu thị bằng gia tốc hướng tâm bằng

$$a = \frac{v_2^2}{R},$$

trong đó $R$ là bán kính của vòng tròn, có thể thay thế bằng quỹ đạo thực tế của con chó.

Hãy xem xét chuyển động của một con chó trong thời gian ngắn $\Delta t$. Trong thời gian này, vectơ vận tốc của con chó sẽ quay một góc $\alpha$ sao cho $\alpha = \frac{v_2 \Delta t}{R}$ (Hình 16). Mặt khác, trong thời gian $\Delta t$ con cáo sẽ di chuyển một quãng đường $v_1 \Delta t = \alpha l$, vì vectơ vận tốc của con chó luôn hướng về phía con cáo. Kể từ đây,

$$\frac{v_2 \Delta t}{R} = \frac{v_1 \Delta t}{l}.$$

Sau đó

$$R = \frac{v_2}{v_1} l \text{ и } a = \frac{v_1 v_2}{l}.$$

Tôi. Sh. Slobodetsky
