---
id: 1984-10-boltyanskiy-eksponenta-7ff4dd41
issue: kvant_1984_10
year: 1984
number: "10"
title: Nhà triển lãm
authors:
  - Болтянский В. Г.
rubric: matematicheskiy-kruzhok
rubric_sub: Математический кружок
page_first: 22
page_last: 26
page_labels: 20-24
tag: 4WCW
lang: vi
source: kvant_digital
extraction: vision
content_sha256: 4635c2e603995cf2edc6255e9c9803d10390e64e902fb27e967e8a6d58684cb4
prompt_sha256: draft-1
translated_from: content/ru/1984/10/articles/09_boltyanskiy-eksponenta-7ff4dd41.md
source_content_sha256: 5818213399aa2c72b2b8b555f79aa58ddaf995dc1a855bcea436ea751faeb315
translation_model: draft
translation_run: vi-draft-2026-10-31
translation_quality: draft
---

⟦folio 20⟧

Nhà triển lãm

Thành viên tương ứng của Viện Hàn lâm Khoa học Sư phạm Liên Xô
V. G. BOLTYANSKY

Trong bất kỳ sách giáo khoa cấp trường nào, phần trình bày chủ đề về hàm số mũ và số e đều chứa đựng những phát biểu chưa được chứng minh, những đoạn văn được trình bày ngắn gọn. Điều này được giải thích bởi sự phức tạp của chủ đề. Ở đây chúng ta sẽ nói về một cách tiếp cận khác đối với những khái niệm này, khám phá ý nghĩa và mối liên hệ của chúng với các phương trình vi phân. Với cách trình bày này còn có những phát biểu chưa được chứng minh (định lý tổng quát của danh từ và tính duy nhất của phương trình vi phân và tính chất của hàm liên tục lấy giá trị trung gian). Tuy nhiên, những phát biểu chưa được chứng minh này có ý nghĩa trực quan đơn giản và có tầm quan trọng cơ bản đối với toàn bộ toán học.

1. Bài toán về một vật rơi trong môi trường có điện trở

Người nhảy dù đang rơi xuống bị ảnh hưởng bởi trọng lực và lực cản của không khí (các khả năng còn lại để phương trình vi phân và tính chất của hàm liên tục lấy các giá trị trung gian). Lực cản của không khí có thể coi là tỷ lệ thuận với tốc độ $v$, tức là có độ lớn bằng $qv$ (hệ số $q$ phụ thuộc chủ yếu vào đường kính và hình dạng của dù). Như vậy,

$$ma = mg - qv,$$

trong đó $a = v'$ là giá trị gia tốc (dấu trừ ở phía trước $qv$ là do lực cản của không khí tác dụng ngược với hướng rơi; Hình 1). Chia cho $m$ ta được

$$v' = -\frac{q}{m} v + g.$$ (1)

Sự tương ứng (1) là một phương trình vi phân tuyến tính: đạo hàm của hàm chưa biết $v = v(t)$ (cần được xác định từ phương trình này) được biểu thị dưới dạng đa thức bậc một của hàm chưa biết này. Ký hiệu hàm chưa biết là $y = y(x)$, các hệ số là $a$ và $b$, ta viết phương trình vi phân dưới dạng

$$y' = ay + b.$$ (2)

Phương trình vi phân này không chỉ mô tả sự rơi của một vật vào môi trường có lực cản mà còn mô tả các quá trình vật lý đa chiều.

2. Định lý tồn tại và duy nhất

Định lý 1. Dù là số thực $x_0, y_0$ thì cũng chỉ có một hàm số $y = y(x)$ là lời giải của phương trình (2) và thỏa mãn phương trình tương ứng $y(x_0) = y_0$. lời giải này được xác định trên toàn bộ dòng số.

Mối quan hệ $y(x_0) = y_0$ được gọi là tình trạng mũi. Do đó, Định lý 1 có nghĩa là phương trình (2) đối với bất kỳ tình trạng mũi đã cho nào cũng có lời giải (và hơn nữa, là phương trình duy nhất).

Hãy trình bày lý thuyết hình học của định lý này và xét trường hợp đặc biệt khi $a = 1$, $b = 2$, tức là lấy phương trình

$$y' = y + 2.$$ (3)

Tại các điểm $y = 0$ (trên trục $x$), theo (3), $y' = 2$, tức là đồ thị của hàm số ban đầu $y(x)$ phải có hệ số góc tiếp tuyến bằng 2 tại các điểm này. Chúng ta hãy phác thảo hướng của tiếp tuyến bằng các đường ngắn được vẽ tại các điểm của trục hoành (Hình 2). Hơn nữa, đối với $y = 1$, theo (3), $y' = 3$, tức là tại các điểm của đường thẳng $y = 1$ đồ thị của hàm số ban đầu phải có hệ số góc tiếp tuyến bằng 3; Chúng ta hãy đánh dấu hướng của tiếp tuyến tại các điểm của đường $y = 1$ bằng các dấu gạch ngang ngắn. Sau đó, chúng ta có thể đánh dấu các đường trên các đường thẳng khác song song với trục x (Hình 2). Bây giờ hành vi của “đường trường” của “trường định hướng” này trở nên rõ ràng. Tại mỗi điểm, “đường lực” chạm vào đường tương ứng, tức là tiếp tuyến của nó có hệ số góc là $y'$, do cấu tạo của đường thẳng nên bằng $y + 2$. Điều này có nghĩa là "đường trường" là đồ thị của hàm thỏa mãn phương trình (3). Từ hình vẽ, có thể thấy rõ rằng qua mỗi điểm $(x_0; y_0)$ có một “đường lực” và hơn nữa, chỉ có một. Điều này cung cấp sự xác nhận rõ ràng về tính đúng đắn của Định lý 1. Chứng minh của nó

⟦folio 21⟧

3. Nhà triển lãm

Hàm thỏa mãn phương trình vi phân $y'=y$ và điều kiện ban đầu $y(0)=1$ được gọi là hàm mũ và được ký hiệu bằng ký hiệu expr.

Lưu ý rằng phương trình $y'=y$ là phương trình ngẫu nhiên từng phần của phương trình (2); do đó, lời giải của nó với điều kiện ban đầu $y(0)=1$, theo Định lý 1, tồn tại và được xác định duy nhất, và miền định nghĩa của lời giải này (nghĩa là hàm mũ) là một đường thẳng.

Nó suy ra trực tiếp từ định nghĩa rằng hàm mũ là một hàm khả vi và đạo hàm của nó trùng với cùng một hàm (vì nó là nghiệm của phương trình $y'=y$):

$$\text{exp } x' = \text{exp } x.$$  (4)

Định lý 2. Các giá trị của hàm expr là dương, tức là expr $>0$, với mọi số thực $x$.

Bằng chứng. Giả sử rằng expr $x_0=0$ đối với một số $x_0$. Khi đó hàm $y=\text{exp } x$ thỏa mãn phương trình $y'=y$ và điều kiện $y(x_0)=0$. Hàm $y\equiv 0$ cũng thỏa mãn phương trình $y'=y$ và điều kiện $y(x_0)=0$. Hơn nữa, hàm $y=\text{exp } x$ và $y\equiv 0$ khác nhau (ví dụ: expr $0=1$, tức là expr $0\neq 0$). Nhưng sau đó hóa ra phương trình $y'=y$ có ​​hai lời giải khác nhau theo điều kiện ban đầu $y(x_0)=0$, mâu thuẫn với Định lý 1. Vì vậy, đẳng thức expr $x=0$ không thể xảy ra với bất kỳ $x$ nào.

Bây giờ chúng ta giả sử rằng đối với một số $x_1$ chúng ta có expr $x_1<0$. Hàm expr khả vi và do đó liên tục; do đó, giữa hai điểm mà tại đó nó nhận các giá trị khác dấu ($\text{exp } x_1<0$, expr $0=1$), hàm này phải biến mất (Hình 3). Nhưng điều này, như chúng ta đã thấy, là không thể.

Vì vậy, số mũ không thể nhận giá trị 0 hoặc âm; do đó expr $x>0$ với mọi $x\in R$.

Kết quả. Hàm mũ là hàm tăng.

⟦folio 22⟧

Thật vậy, theo Định lý 2, hàm đạo hàm exp (tức là chính hàm này) chỉ nhận các giá trị dương, và do đó hàm exp đang tăng.

Định lý 3. Với mọi p, q ∈ R ta có

$$\exp(p+q) = \exp p \cdot \exp q.$$ (5)

Bằng chứng. Xét hàm y = exp(p+x). chúng tôi có

$$y' = (\exp(p+x))' = \exp(p+x) = y$$

(xem (4)), nghĩa là hàm này thỏa mãn phương trình y'=y. Trong trường hợp này y(0) = exp p.

Bây giờ chúng ta xét hàm y = exp p · exp x. chúng tôi có

$$y' = \exp p \cdot (\exp x)' = \exp p \cdot \exp x = y$$

nghĩa là hàm này cũng thỏa mãn phương trình y'=y. Trong trường hợp này y(0) = exp p. Theo Định lý 1, các hàm đang xem xét trùng nhau:

$$\exp(p+x) = \exp p \cdot \exp x.$$

Cụ thể, với x=q chúng ta thu được (5).

4. Số e

Giá trị hàm exp. khi x=1 được ký hiệu bằng chữ e, tức là e=exp 1. Để tìm giá trị gần đúng của số e, bạn có thể tiến hành như sau. Hãy chia đoạn [0; 1] thành n phần bằng nhau (mỗi phần có độ dài Δx=1/n). Qua điểm A0 (0; 1) ta vẽ đường “nét” tương ứng với phương trình y'=y; nó có hệ số góc k1=y, tức là k1=1. Chúng ta sẽ xem xét “dấu gạch ngang” này trên đoạn [0; 1/n]. Đầu bên phải A1 của nó có tọa độ x=1/n, y=1+k1Δx=1+1·1/n=1+1/n (Hình 4).

Qua A1 ta vẽ được một “dấu gạch ngang” mới, cũng tương ứng với phương trình y'=y; hệ số góc của nó bằng y (cung độ của điểm A1), nghĩa là bằng k2=1+1/n. Chúng ta sẽ xem xét “dấu gạch ngang” này trên [1/n; 2/n]. Đầu bên phải A2 của nó có tọa độ

$$x = \frac{2}{n}, y = \left(1 + \frac{1}{n}\right) + k_2 \Delta x =$$

$$= \left(1 + \frac{1}{n}\right) + \left(1 + \frac{1}{n}\right) \cdot \frac{1}{n} = \left(1 + \frac{1}{n}\right)^2$$

Qua A2 chúng ta lại vẽ một “dấu gạch ngang” tương ứng với phương trình y'=y. Hệ số góc k3 của nó bằng tọa độ điểm A2, tức là k3=(1+1/n)^2, và đầu bên phải của A3 có tọa độ x=3/n, y=(1+1/n)^2+k3Δx = (1+1/n)^3.

Tiếp tục, chúng ta thu được đường đứt nét A0A1A2...An - đường đứt nét Euler cho phương trình y'=y (trong Hình 4, để thuận tiện, các tỷ lệ khác nhau được lấy trên các trục); điểm An có tọa độ x=1, y=(1+1/n)^n. Đường đứt nét này đưa ra ý tưởng gần đúng về phương trình lời giải y'=y đi qua điểm A0, tức là hàm y=exp x (đồ thị màu đỏ trong Hình 4); cụ thể, điểm An gần với đồ thị điểm y=exp x, có hoành độ x=1, tức là tới điểm (1; e). Nói cách khác, (1+1/n)^n≈e. N càng lớn thì đẳng thức gần đúng này càng chính xác và do đó

$$\lim_{n \to \infty} \left(1 + \frac{1}{n}\right)^n = e.$$ (6)

Ví dụ: lấy n=1.000.000, nghĩa là thực hiện hành động 1.0000011000000 (điều này rất dễ thực hiện với máy tính vi mô), chúng tôi tìm thấy e=2.7182818...

5. Chỉ định e^x

Bổ đề. Với mọi x hữu tỉ thì đẳng thức đúng

$$\exp x = e^x.$$ (7)

Đi tiểu. 4.

⟦folio 23⟧

Bằng chứng. Áp dụng nhất quán công thức (5), ta tìm được
$$\exp 2x = \exp (x+x) = \exp x \cdot \exp x = (\exp x)^2,$$
$$\exp 3x = \exp (2x+x) = \exp 2x \cdot \exp x = (\exp x)^2 \cdot \exp x = (\exp x)^3$$
v.v. Vì vậy, đối với $n$ tự nhiên, chúng ta có
$$\exp nx = (\exp x)^n,$$
từ đâu $\exp x = (\exp nx)^{1/n}$. Trường ở đây là $x=m/n$ (trong đó $m$ là tự nhiên), chúng ta nhận được
$$\exp \frac{m}{n} = (\exp m)^{1/n} = (\exp m \cdot 1)^{1/n} = \left((\exp 1)^m\right)^{1/n} = (\exp 1)^{m/n} = e^{m/n}$$
Điều này có nghĩa là đối với số hữu tỷ dương $x=m/n$ bổ đề được chứng minh là hợp lệ. Thật dễ dàng để kiểm tra xem nó có đúng với các số hữu tỉ âm (cũng như với $x=0$) hay không.
Theo định nghĩa, các điều kiện được giả định rằng sự tương ứng (7) đúng với mọi số thực $x$. Nói cách khác, chúng tôi giả định rằng $e^x$ chỉ đơn giản là một dạng viết khác của $\exp x$ (và đối với $x$ hữu tỉ, dạng viết này nhất quán, nhờ bổ đề đã được chứng minh, với một công thức dễ hiểu với số mũ hữu tỉ). Khi sử dụng ký hiệu này, công thức (5) có dạng thông thường $e^{p+q} = e^p e^q$. Lưu ý rằng trong tài liệu toán học, cả hai công thức viết số mũ đều được sử dụng: $y=e^x$ và $y=\exp x$.

6. Lời giải phương trình vi phân

Khi viết phương trình vi phân lời giải, ký hiệu $e^x$ thường được sử dụng thay vì $\exp x$. Chúng tôi sẽ tuân thủ truyền thống này.

Định lý 4. Với $a \neq 0$ lời giải phương trình vi phân (2) với điều kiện ban đầu $y(0)=y_0$ có ​​dạng
$$y = -\frac{b}{a} + ce^{ax},$$
(8)
$$e\delta e = b/a + y_0.$$
Bằng chứng. Vì (theo Định lý 1) loại bỏ hàm duy nhất nên chỉ cần kiểm tra hàm (8) (đối với giá trị xác định là $c$) thỏa mãn phương trình (2) và điều kiện ban đầu cần thiết. chúng tôi có
$$y' = (ce^{ax})' = c(e^{ax})' = cae^{ax} = a(ce^{ax}) = a(y + \frac{b}{a}) = ay + b,$$
nghĩa là hàm (8) thực sự thỏa mãn phương trình (2) (đối với bất kỳ giá trị nào của hằng số $c$). Kế tiếp,
$$y(0) = -\frac{b}{a} + ce^0 = -\frac{b}{a} + c = -\frac{b}{a} + \left(\frac{b}{a} + y_0\right) = y_0.$$
Điều này có nghĩa là đối với giá trị được chỉ định $c$ thì hàm $y$ cũng thỏa mãn điều kiện ban đầu được yêu cầu.

Định lý đã được chứng minh hứa hẹn sẽ được áp dụng như sau. Thuật ngữ $y = -b/a$ rất dễ nhớ: nó thu được nếu $y'$ bằng 0; hơn nữa, hệ số $a$ của hàm chưa biết trong (2) trở thành hệ số của đối số trong số mũ. Đối với 常态ы $c$, giá trị của nó (được chỉ ra trong Định lý 4) thường không được ghi nhớ và trong mỗi ví dụ cụ thể, $c$ được tìm thấy bằng cách sử dụng các điều kiện ban đầu.

Ví dụ 1. Khối lượng $m(t)$ của chất phóng xạ có trong một mảnh đá tại thời điểm $t$ giảm theo thời gian, tức là đạo hàm $m'(t)$ (tốc độ phân rã) là âm. Nếu cần, lượng chất phóng xạ, tốc độ phân rã tỷ lệ thuận với khối lượng chất phóng xạ:
$$m' = -km$$
(trong đó hệ số $k > 0$ phụ thuộc vào loại chất phóng xạ). Tìm định luật biến thiên khối lượng $m(t)$ theo thời gian, nếu tại thời điểm ban đầu $t=0$ khối lượng của chất phóng xạ thu được bằng $m_0$.

Lời giải. Theo Định lý 4 chúng ta có $m(t) = ce^{-kt}$. Thay thế $t=0$, chúng ta nhận được $m_0 = ce^0$, do đó $c = m_0$. Kết quả cuối cùng là $m(t) = m_0e^{-kt}$.

Ví dụ 2. Sau khoảng thời gian $T$ lượng chất phóng xạ giảm đi đúng một nửa?

Lời giải. Chúng ta cần tìm $T$ từ phương trình $m_0/2 = m_0e^{-kT}$, tức là $e^{-kT} = 1/2$ hoặc $e^{kT} = 2$. Điều này tương ứng với trạng thái cân bằng sau: $\ln 2 = kT$, từ đó $T = (\ln 2)/k \approx 0.7/k$.

Giá trị $T = (\ln 2)/k$ được gọi là chu kỳ bán rã. Nó phụ thuộc vào $k$ (tức là chất phóng xạ); ví dụ: đối với radium $T \approx 1600$ năm.

⟦folio 24⟧

Ví dụ 3. Tìm định luật rơi của một vật trong môi trường có lực cản, biết rằng tại $t=0$ tốc độ rơi bằng $v_0$.

Lời giải. Từ phương trình (1) ta tìm được theo Định lý 4:

$$v(t) = \frac{mg}{q} + ce^{-\frac{q}{m}t}.$$

Thay $t=0$, ta được $v_0=mg/q+ce^0$, do đó $c=v_0-mg/q$. Như vậy, cuối cùng chúng ta có

$$v(t) = \frac{mg}{q} + \left(v_0 - \frac{mg}{q}\right)e^{-\frac{q}{m}t}.$$

Vì $e^{-\frac{q}{m}t} \to 0$ tại $t \to \infty$, nên $v(t) \to mg/q$, nó sẽ trở thành, tốc độ giảm dần dần được thiết lập. Ví dụ, một người nhảy dù rơi trong một cú nhảy xa ở tốc độ cao, sau khi mở dù, nhanh chóng đạt được tốc độ xấp xỉ không đổi $mg/q$ (tùy thuộc vào khối lượng của dù và các thông số của dù). Điều này cho phép tính toán chiếc dù sao cho việc hạ cánh được an toàn.

Bài tập
1. Chứng minh rằng với mọi $x \neq 0$ thì phương trình $x > x+1$ là đúng.
2. Sử dụng bất đẳng thức $\exp \frac{1}{n} > 1 + \frac{1}{n}$ (xem bài toán 1), chứng minh rằng $e > (1+1/n)^n$.
3. Sử dụng bất đẳng thức $\exp \left(-\frac{1}{n+1}\right) > 1 - \frac{1}{n+1}$ (xem bài toán 1), chứng minh rằng $e > (1+1/n)^n$, tức là $e < (1+1/n)^{n+1}$.
4. Sử dụng các bất đẳng thức thu được trong bài toán 2 và 3, chứng minh các đẳng thức (6).
5. Chứng minh rằng lời giải của phương trình (2) với điều kiện ban đầu $y(x_0)=y_0$ có dạng (8), trong đó $c=(b/a+y_0)e^{-ax_0}$.
6. Tại thời điểm $t=t_0$ khối lượng của chất phóng xạ có trong mảnh đá bằng $m_0$, và tại thời điểm $t=t_1$ hóa ra nó bằng $m_1$. Xác định chu kỳ bán rã.
7. Khi một gam chất phóng xạ phân rã sẽ tạo ra $d$ gam sản phẩm phân rã. Chu kỳ bán rã $T$ của chất phóng xạ này đã được biết. Xác định tuổi của một mảnh đá nếu nó chứa $p$ gam chất phóng xạ đang đề cập và $q$ gam sản phẩm phân rã của nó.
8. Do trao đổi nhiệt với môi trường, vật được làm nóng dần nguội đi, tức là nhiệt độ của nó $t(\tau)$ giảm theo thời gian $\tau$. Theo định luật làm mát của Newton, tốc độ làm mát tỷ lệ thuận với chênh lệch nhiệt độ giữa cơ thể và môi trường: $t'(\tau) = -k(t(\tau) - t_{cp})$. Giả sử nhiệt độ của môi trường $t_{cp}$ không đổi, hãy rút ra công thức tính định luật làm nguội.
9. Cường độ dòng điện $I(t)$ chạy trong ô $RL$ (Hình 5) thay đổi theo quy luật $LI' + RI = E$, trong đó $L$ là độ tự cảm của cuộn dây, $R$ là điện trở của điện trở. Xác định định luật $I(t)$ của sự thay đổi dòng điện nếu tại thời điểm đóng mạch ($t=0$) dòng điện bằng không.
10. Trong mạch $RL$ (Hình 6) hiện tại có dòng điện $t=0$ $I_0$ chạy qua. Xác định giá trị cường độ dòng điện chạy trong mạch tại $t>0$.
11. Điện áp $u(t)$ (hiệu điện thế trên các bản tụ) thay đổi theo hướng $RC$ (Hình 7) theo quy luật $Cu' + u/R=0$. Xác định đặc tính của sự thay đổi điện áp nếu tại thời điểm $t=0$điện áp bằng $u_0$.
12. Xét đa tuyến Euler cho phương trình $y'=y$ với điều kiện ban đầu $y(0)=1$, hãy chỉ ra rằng đối với $x>0$ cố định thì chuỗi $(1+x/n)^n$ trả về và bị chặn.
13. Sử dụng định lý Weierstrass cho dãy số tăng có giới hạn và Bài toán 12, chứng minh sự tồn tại của giới hạn $(1+x/n)^n$ đối với $x \geq 0$ cố định và sau đó đối với $x<0$.
14*. Chứng minh sự tồn tại của số mũ. Gợi ý. Đặt $y(x)=\lim_{n \to \infty} (1+x/n)^n$ (xem bài toán 13), tính tích $y'(x)$ và thiết lập rằng $y'(x)=\lim_{n \to \infty} (1+x/n)^n$; Từ đó suy ra $y(x)$ là nghiệm của phương trình $y'=y$ với điều kiện ban đầu $y(0)=1$. (Khi tính $y'(x)$, hãy sử dụng công thức quần xã của Newton.)
15*. Chứng minh số mũ duy nhất. Gợi ý. Giả sử điều ngược lại (sự tồn tại của hai số mũ khác nhau) và xem xét sự khác biệt của chúng.
