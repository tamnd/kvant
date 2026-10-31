---
id: 1977-12-resheniya-zadach-m434-m435-f445-f446-e2ace72d
issue: kvant_1977_12
year: 1977
number: "12"
title: Lời giải bài toán M434, M435; F445, F446
rubric: zadachnik-kvanta
rubric_sub: Задачник «Кванта»
page_first: 38
page_last: 41
page_labels: 36-39
tag: M28Q
lang: vi
source: kvant_digital
extraction: vision
content_sha256: 44db900367cd6b94eae541b517c15a8b7c428999632aab1599721e40ebba196d
prompt_sha256: draft-1
translated_from: content/ru/1977/12/articles/11_resheniya-zadach-m434-m435-f445-f446-e2ace72d.md
source_content_sha256: d9df1c3ca53b0b8d0a8a16366b92543a5f31096463156abbd9240861d05fd5cb
translation_model: draft
translation_run: vi-draft-2026-10-31
translation_quality: draft
---

⟦folio 36⟧

Lời giải bài toán

M434, M435; F445, F446

M434. Số $\frac{2}{1} + \frac{2^2}{2} + \frac{2^3}{3} + \dots + \frac{2^n}{n}$
được biểu diễn dưới dạng phân số phi Socrates $\frac{p_n}{q_n}$.

a) Chứng minh rằng $p_n$ là số lớn hơn.
b) Chứng minh rằng nếu $n > 3$ thì $p_n$ chia hết cho 8.
c) Chứng minh rằng với mọi số tự nhiên $k$ người ta có thể chỉ ra $n$ nào mà các số $p_n, p_{n+1}, \dots, p_{n+2}, \dots$ chia hết cho $2^k$.

a), b) Nếu phân số không Socrates $\frac{p}{q}$ là tổng của một số phân số không Socrates, tử số của mỗi phân số đó chia hết cho $2^k$, thì $p$ cũng chia hết cho $2^k$. Đối với lời giải bài toán a) vẫn cần lưu ý rằng tử số của các phân số $\frac{2}{1}, \frac{2^2}{2}, \frac{2^3}{3}, \dots$ vẫn giữ nguyên sau khi giảm (vì với mọi số tự nhiên $m$ thì bất đẳng thức $2^{m-1} \geq m$ là đúng). Với lời giải bài toán b) chỉ cần có bất đẳng thức $2^{m-3} \geq m$ là đủ. Tuy nhiên, bất đẳng thức này chỉ có giá trị bắt đầu từ $m = 6$. Do đó, chúng ta hãy kiểm tra xem tử số của các tổng $\frac{2}{1} + \frac{2^2}{2} + \frac{2^3}{3} + \frac{2^4}{4}$ và $\frac{2}{1} + \frac{2^2}{2} + \frac{2^3}{3} + \frac{2^4}{4} + \frac{2^5}{5}$ sau khi rút gọn sẽ chia hết cho 8. Các tổng này lần lượt bằng $\frac{32}{3}$ và $\frac{256}{15}$.

c) Xét hàm $L_n(x) = \frac{x}{1} + \frac{x^2}{2} + \dots + \frac{x^n}{n}$. Ta chứng minh đa thức $L_n(2x - x^2) - 2L_n(x) = f(x)$ có dạng:

$$f(x) = x^{n+1} \cdot \left( \frac{a_0}{n+1} + \frac{a_1}{n+2} x + \dots + \frac{a_{n-1}}{2n} x^{n-1} \right),$$

trong đó $a_0, a_1, \dots, a_{n-1}$ là số nguyên. Để làm điều này, chỉ cần chứng minh rằng đa thức $f'(x)$ có dạng:

$$f'(x) = x^n \left( a_0 + a_1 x + \dots + a_{n-1} x^{n-1} \right).$$

Lưu ý rằng $L_n'(x) = 1 + x + x^2 + \dots + x^{n-1} = \frac{1-x^n}{1-x}$. Đó là lý do tại sao,

$$f'(x) = L_n'(2x - x^2) \cdot (2 - 2x) - 2L_n'(x) =$$

$$= \frac{1 - (2x - x^2)^n}{1 - 2x + x^2} \cdot (2 - 2x) - \frac{2(1 - x^n)}{1 - x} =$$

$$= 2 \cdot \frac{x^n - x^n(2 - x)^n}{1 - x} = x^n \cdot \frac{2(1 - (2 - x)^n)}{1 - x}$$

Và

$$1 - (2 - x)^n = (1 - (2 - x))(1 + (2 - x) + (2 - x)^2 + \dots +$$

$$+ (2 - x)^{n-1}) = (x - 1)(1 + (2 - x) + (2 - x)^2 + \dots +$$

$$+ (2 - x)^{n-1}).$$

Vì $f(2) = L_n(0) - 2L_n(2) = -2L_n(2)$, khi đó, đặt $x = 2$ vào đẳng thức (*), ta có

$$L_n(2) = -2^n \left( \frac{a_0}{n+1} + \frac{2a_1}{n+2} + \dots + \frac{2^{n-1}a_{n-1}}{2n} \right).$$

Từ bất đẳng thức $n < 2^{\frac{n+1}{2}}$, đúng với mọi số $n$, suy ra rằng tất cả các mẫu số ở bên phải

⟦folio 37⟧

M435. Trong bảng kích thước $m \times n$ ghi số thực, trong mỗi ô có một số. Mỗi cột gạch dưới $k$ số lớn nhất ($k \leq m$) và mỗi hàng gạch dưới $l$ số lớn nhất ($l \leq n$). Hãy chứng minh rằng có ít nhất $kl$ số được gạch chân hai lần.

$$k = 1; \quad l = 2.$$

Hình 1.

F445. Một tụ điện có điện dung $C = 0,04$ uF sử dụng phím $K$ được sạc định kỳ với tần số $v = 50$ lần mỗi giây từ một nguồn có e. d.s. % = 100 V và điện trở trong $r = 5$ Ohm và phóng điện qua điện trở $R = 1$ kOhm (Hình 2). Xác định công suất tỏa ra ở khu vực ngoài trời $R$ và k. N. bất kỳ thiết bị nào. Giả sử thời gian đóng của tụ điện đủ để tụ được sạc đầy (vị trí $I$) và phóng điện hoàn toàn (vị trí $II$).

Chúng ta sẽ giải bài toán bằng quy nạp theo một công thức tổng quát hơn một chút, giả sử rằng mỗi cột nhấn mạnh ít nhất $k$ số lớn nhất và mỗi hàng nhấn mạnh ít nhất $l$ số lớn nhất. Chúng ta tiến hành quy nạp trên $m+n$.

Đối với $m=n=k=l=1$ mệnh đề là hiển nhiên. Chúng ta hãy có một bảng có kích thước $m \times n$. Thông tin bài toán vào bảng $m \times (n-1)$ hoặc $(m-1) \times n$. Nếu trong bảng tất cả các số được gạch chân đều được gạch chân hai lần thì số của chúng không nhỏ hơn $kn$. Ngược lại, các số được gạch chân một lần, chúng ta chọn số lớn nhất $A$. Số $A$ là một trong những số lớn nhất hoặc là một trong những số lớn nhất về số lượng. Giả sử rằng $A$ là một trong những kích thước lớn nhất. Sau đó, vì $A$ không phải là một trong những số lớn nhất và $A$ là giá trị trung bình lớn nhất của các số được gạch chân một lần, nên tất cả các số lớn nhất trong một dòng $A$ đều được gạch chân (theo dòng!), được gạch chân hai lần (xem Hình 1). Bằng cách xóa dòng này khỏi bảng của chúng tôi, chúng tôi nhận được một bảng $(m-1) \times n$, trong đó ít nhất $l$ số lớn nhất trong mỗi số được gạch chân. Và ít nhất $k-1$ số trong mỗi cột. Giả định quy nạp là trong bảng nhỏ hơn này ít nhất $(k-1) l$ số được gạch chân hai lần. Những số tương tự này được gạch chân hai lần trong bảng lớn $m \times n$, trong đó, ngoài ra, ít nhất $l$ số ở dòng bị loại bỏ được gạch chân kép. Vì vậy, tổng cộng có ít nhất $(k-1) l+l=kl$ số được gạch chân hai lần trong bảng gốc, như đã nêu trong bài toán.

S. Konyazin

Trong quá trình phóng điện của tụ điện, toàn bộ năng lượng chứa trong tụ điện được giải phóng ở điện trở $R$. Năng lượng này

$$W = \frac{C \mathcal{E}^2}{2}.$$

Trong một giây, tụ điện phóng điện 50 lần (hạt công tắc phím $v=50$ 1/c). Do đó, công suất trung bình $P_{cp}$ được phân bổ trong tải $R$ bằng

$$P_{cp} = W v = \frac{C \mathcal{E}^2}{2} v = 10^{-2} B T.$$

Để có hệ số hiệu suất $\eta$ của thiết bị này, cần chia năng lượng $W$ giải phóng ở điện trở $R$ trong quá trình phóng điện của tụ điện bởi công $A$ được thực hiện bởi nguồn dòng điện trong quá trình nạp tụ điện. Bởi vì

$$A = q \mathcal{E} = C \mathcal{E} \mathcal{E} = C \mathcal{E}^2,$$

⟦folio 38⟧

$$\eta = \frac{W}{A} = \frac{C \mathcal{E}^2}{C \mathcal{E}^2} = \frac{1}{2},$$

nghĩa là hiệu suất không phụ thuộc vào các giá trị điện trở $R$ và $r$.

Nếu không có tụ điện và nguồn có e. d.s. $\mathcal{E}$ và điện trở trong $r$ sẽ không được nối chủ yếu với tải $R$, khi đó hiệu suất của mạch sẽ bằng nhau

$$\eta' = \frac{I^2 R}{I^2 (R + r)} = \frac{R}{R + r} = 0,995,$$

nhiều hơn đáng kể so với trường hợp của chúng tôi.

◆

Hãy hướng trục tọa độ $X$ sang bên phải và gốc tọa độ được nối với vị trí của vật tại thời điểm ban đầu (Hình 4). Hai lực tác dụng lên cơ thể khi băng tải tương đối đi qua nó. Một trong số chúng - lực đàn hồi của lò xo - tỷ lệ thuận với tọa độ $x$ của vật và hướng theo hướng ngược lại với độ dịch chuyển của nó:

$$F_{\text{упр}} = -kx,$$

và cái còn lại - sức mạnh của sự chuyển tổ chức - là không đổi:

$$F_{\text{тр}} = \mu M |\vec{g}|,$$

trong đó $\mu$ là hệ số ma sát của vật lên đai. Điều này có nghĩa là, giống như một nam châm lò xo nằm ngang thông thường, cơ thể phải thực hiện những rung động hài hòa tự do. Đúng, những dao động này xảy ra tương ứng với vị trí cân bằng - điểm $O'$ với tọa độ $x_0$, trong đó tổng hình chiếu của tất cả các lực bằng 0:

$$F_{\text{упр}} + F_{\text{тр}} = 0,$$ hoặc $-kx_0 + \mu M |\vec{g}| = 0,$

Ở đâu

$$x_0 = \frac{\mu M |\vec{g}|}{k};$$

Hãy để chúng tôi chứng minh rằng đây thực sự là trường hợp. Để thực hiện điều này, thật thuận tiện khi chuyển sang một hệ tọa độ khác, gốc của hệ tọa độ này là điểm $O'$ và trục $X'$ hướng sang phải (xem Hình 4). Hãy viết phương trình chuyển động của vật theo hình chiếu lên phương đã chọn:

$$Ma = F_{\text{упр}} + F_{\text{тр}}.$$

Đây $F_{\text{упр}} = -k(x_0 + x') = -k \left( \frac{\mu M |\vec{g}|}{k} + x' \right)$ và $F_{\text{тр}} = \mu M |\vec{g}|.$

Posetom

$$Ma = -k \left( \frac{\mu M |\vec{g}|}{k} + x' \right) + \mu M |\vec{g}|,$$

hoặc

$$Ma = -kx'.$$

(Lưu ý rằng chúng ta gặp trường hợp tương tự ở lời giải bài toán đối với dao động của một nam châm lò xo thẳng đứng (Hình 5). Ở đây, vai trò của lực ma sát không đổi cũng được đóng bởi lực hấp dẫn không đổi.) Chúng ta đã thu được phương trình chuyển động của một vật thực hiện các dao động điều hòa tự do. Những dao động này xảy ra theo quy luật

$$x' = x_m' \cos(\omega_0 t + \varphi_0).$$

Tần số dao động tuần hoàn

$$\omega_0 = \sqrt{\frac{k}{M}}.$$

Biên độ $x_m'$ có thể được tìm thấy từ việc xem xét năng lượng:

⟦folio 39⟧

tại thời điểm ban đầu, khi tốc độ của vật bằng 0 thì độ dời của nó là $x' = -x_0$. Do đó, biên độ dao động

$$x'_m = x_0 = \frac{\mu M |\vec{g}|}{k}.$$

Pha ban đầu $\varphi_0$ được xác định bởi các điều kiện ban đầu: tại $t=0$ $x' = -x_0$, từ đó $\varphi_0 = \pi$.

Vì thế,

$$x' = x_0 \cos(\omega_0 t + \varphi_0) = -\frac{\mu M |\vec{g}|}{k} \cos \sqrt{\frac{k}{M}} t.$$

Trong hệ tọa độ $OX$, tọa độ của vật tùy theo thời gian sẽ như sau:

$$x = x_0 + x' = x_0 (1 - \cos \omega_0 t) =$$

$$= \frac{\mu M |\vec{g}|}{k} \left( 1 - \cos \sqrt{\frac{k}{M}} t \right),$$

và các hình chiếu của vận tốc và gia tốc tương ứng là

$$v = x_0 \omega_0 \sin \omega_0 t = v_m \sin \omega_0 t = \mu |\vec{g}| \sqrt{\frac{M}{k}} \sin \sqrt{\frac{k}{M}} t$$

Và

$$a = x_0 \omega_0^2 \cos \omega_0 t = a_m \cos \omega_0 t = \mu |\vec{g}| \cos \sqrt{\frac{k}{M}} t.$$

Tuy nhiên, mọi suy luận của chúng ta chỉ có giá trị nếu biên độ $v_m$ của vận tốc cơ thể không vượt quá tốc độ $v_0$ của chuyển động của băng tải. Vì vậy, chỉ với điều kiện

$$v_m \leq v_0,$$ hoặc $\mu |\vec{g}| \sqrt{\frac{M}{k}} \leq v_0$

lực ma sát tác dụng lên vật là không đổi. Đồ thị phụ thuộc $x(t), v(t)$ và $a(t)$ cho trường hợp này được hiển thị trong Hình 6.

Và điều gì sẽ xảy ra với cơ thể nếu ngay cả trước khi đi qua vị trí cân bằng hỗn hợp (điểm $O'$), giá trị hấp thụ của tốc độ của nó bằng $v_0$? Rõ ràng, lúc này vật bị “túm” vào băng và lực ma sát giảm xuống giá trị $|\vec{F}_{\text{Tp}}| = |kx| < \mu M |\vec{g}|$. Do đó, vật chuyển động đều trong một thời gian với tốc độ của dây đai cho đến khi đạt đến điểm $O'$ với tọa độ $x_0 = \frac{\mu M |\vec{g}|}{k}$. Tại thời điểm này, lực ma sát trở nên bằng giá trị lớn nhất $\mu M |\vec{g}|$ và với chuyển động tiếp theo của vật, nó sẽ không đổi.

Do đó, bắt đầu từ thời điểm này, vật thể, như trong trường hợp đầu tiên, sẽ thực hiện các dao động điều hòa với cùng tần số $\omega_0 = \sqrt{\frac{k}{M}}$, nhưng với biên độ khác $x_m$.

Vì biên độ dao động của vận tốc bằng $v_0$ (với vận tốc như vậy vật đi qua vị trí cân bằng) nên biên độ dao động tọa độ

$$x_m = \frac{v_0}{\omega_0} = v_0 \sqrt{\frac{M}{k}}.$$

Tương tự, biên độ dao động gia tốc

$$a_m = v_0 \omega_0 = v_0 \sqrt{\frac{k}{M}}.$$

Đồ thị tương ứng của $x(t), v(t)$ và $a(t)$ được thể hiện trong Hình 7.

I. Slobodetsky
