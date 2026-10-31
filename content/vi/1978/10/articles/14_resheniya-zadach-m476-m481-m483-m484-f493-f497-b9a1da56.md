---
id: 1978-10-resheniya-zadach-m476-m481-m483-m484-f493-f497-b9a1da56
issue: kvant_1978_10
year: 1978
number: "10"
title: Lời giải bài toán M476—M481, M483, M484; F493—F497
rubric: zadachnik-kvanta
rubric_sub: Задачник «Кванта»
page_first: 42
page_last: 58
page_labels: 40, 41, 42, 44, 45, 46, 47, 48, 49, 50, 51, 52, 53, 55, 56
tag: 3TCO
lang: vi
source: kvant_digital
extraction: vision
content_sha256: 4621c8b6103963899128ba3bd09f2b69a23120cb04dad146a014e01de21c4256
prompt_sha256: draft-1
translated_from: content/ru/1978/10/articles/14_resheniya-zadach-m476-m481-m483-m484-f493-f497-b9a1da56.md
source_content_sha256: 455199d6ea1431677282b64b233b471e3857fcf2a60a2d57ed42459a2d17fc46
translation_model: draft
translation_run: vi-draft-2026-10-31
translation_quality: draft
---

⟦folio 40⟧

Lời giải bài toán
M476—M481, M483, M484; F493—F497

M476. a) Chứng minh rằng nếu các đỉnh của n-уzelbnika lồi nằm trong các nút của tờ giấy dán và không có nút nào khác bên trong hoặc trên các cạnh của nó thì n 4.
b) Giả sử không gian được chia chủ yếu bởi các họ mặt phẳng song song thành các hình lập phương giống hệt nhau. Phần trên của cốc được gọi là nút. Chứng minh rằng nếu tất cả n đỉnh của một khối đa diện lồi đều nằm trong các nút và không có nút nào khác trên các cạnh, biên hoặc bên trong khối đa diện đó thì n<8.

Hình 1.

M477. Cho một đa thức P(x) có hệ số nguyên sao cho với mỗi tên x thì bất đẳng thức P(x)>x đúng. Hãy xác định dãy {b_n} như sau: b_1=1, b_{k+1}=P(b_k) với k ≥1. Được biết, với bất kỳ tên d nào, một thành viên của dãy {b_n} chia cho d đã được đặt tên. Chứng minh rằng P(x)=x+1.

Trước tiên hãy lưu ý rằng nếu các số nguyên x và y cho cùng số dư khi chia cho một số tự nhiên d thì P(x) và P(y) cũng có cùng số dư khi chia cho d. Điều này xuất phát từ thực tế là khi thay x và y thành đa thức P, các số hạng tương ứng sẽ có cùng số dư khi chia cho d. (Trên thực tế, x^k-y^k với mọi k tự nhiên đều chia hết cho x-y, vì x^k-y^k=(x-y)(x^{k-1}+x^{k-2}y+x^{k-3}y^2+...+y^{k-1}); do đó, nếu x-y chia hết cho d thì x^k-y^k cũng chia hết.)

Đặt P(x) khác với x+1. Vì dãy {b_n} được tạo thành từ các số tự nhiên và P(x)>x với mỗi tên x, nên với một số tự nhiên n nào đó sẽ có b_{n+1}>b_n+1. Hãy lấy mức tối thiểu như vậy n. Ta có: b_1=1, b_2=2,...,b_n=n, b_{n+1}>n+1. Hãy đặt d=b_{n+1}-1. Số dư khi chia các số hạng của dãy tại d ban đầu sẽ bằng 1, 2,...,n, sau đó do thay thế và chọn d nên chúng sẽ lặp lại theo chu kỳ: b_{n+1} cho số dư 1, b_{n+2} cho 2,...,b_{2n} cho n, b_{2n+1} - lại 1, v.v. Không có số hạng nào của dãy, hỏi điều kiện bài toán, sẽ không có chia hết cho d. Do đó P(x)=x+1.

⟦folio 41⟧

M478. Trong giải bóng chuyền, mỗi đội thi đấu một trận.
a) Chứng minh rằng nếu có hai đội bất kỳ có một tam giác thắng hai đội này thì số đội ít nhất là bảy.
b) Chứng minh rằng nếu trong ba đội bất kỳ có một tam giác thắng ba đội này thì số đội ít nhất là bảy.
6) Xây dựng một ví dụ về một giải đấu bảy đội.
b) Chứng minh rằng nếu trong ba đội bất kỳ có một tam giác thắng ba đội này thì số đội ít nhất là bảy.

Hình 2.

M479. Có a) sáu, 6) 1000 số văn phòng tối đa sao cho với hai số a và b bất kỳ trong số chúng, tổng a + b chia hết cho hiệu a - b?

M480. Chuỗi $c_n$ được xây dựng theo quy tắc sau: $c_1 = 2$, $c_{n+1} = [3c_n/2]$ cho $n \geq 1^*$). Chứng minh rằng dãy số này có vô số số tuần hoàn.

*) Ở đây [x] là phần nguyên của số x.

a) Xét một đội tùy ý $A$ cùng với một trong các đội $B$, đội $A$ thua, ta thấy rằng $B$ phải thua ít nhất một đội trong số những đội $A$ thắng. Nói cách khác, tất cả các đội thắng $A$ đều thua ít nhất một trận khi thi đấu với nhau. Điều này có nghĩa là số đội thắng $A$ ít nhất là ba. Nhưng trong số tất cả các đội của chúng ta phải có một đội thắng ít nhất bằng số trận thua (tổng số trận thắng). Đội này thua ít nhất ba lần và thắng ít nhất ba lần, điều này có thể xảy ra trong trường hợp số đội ít nhất là bảy.

6) Chúng ta hãy liên kết mỗi đội với một đỉnh của hình bảy cạnh lồi. Chiến thắng của đội $A$ trước đội $B$ được biểu thị bằng một mũi tên vẽ từ điểm $A$ đến điểm $B$. Hình 2 của chúng tôi cho thấy khả năng đáp ứng các điều kiện bài toán.

b) Để đội $A$ thắng ít nhất số trận họ thua. Bằng cách kiểm tra điều kiện bài toán có thỏa mãn đối với tất cả các tam giác có thể có được tạo thành từ đội $A$ và hai đội đã thắng đội đó, chúng ta thấy rằng đội thắng $A$ tạo thành một tập hợp thỏa mãn điều kiện bài toán a). Vì vậy, có ít nhất bảy người trong số họ. Đội $A$ thắng ít nhất bảy trận và thua ít nhất bảy trận; Vì vậy, tổng cộng có ít nhất 15 đội tham gia giải đấu.

Tương tự, dễ dàng chứng minh rằng nếu (với một $m$) bất kỳ $m$ nào có một đội chưa thua tất cả thì số đội đó không nhỏ hơn $2^{m+1} - 1 = a_m$ (dãy $a_1 = 3$, $a_2 = 7$, $a_3 = 15$, ... thỏa mãn điều kiện bài toán a). Vì vậy, có ít nhất bảy người trong số họ. Đội $A$ thắng ít nhất bảy trận và thua ít nhất bảy trận; Vì vậy, tổng cộng có ít nhất 15 đội tham gia giải đấu.

Tương tự, dễ dàng chứng minh rằng nếu (với một $m$) bất kỳ $m$ nào có một đội chưa thua tất cả thì số đội đó không nhỏ hơn $2^{m+1} - 1 = a_m$ (dãy $a_1 = 3$, $a_2 = 7$, $a_3 = 15$, ... thỏa mãn điều kiện bài toán a). Vì vậy, có ít nhất bảy người trong số họ. Đội $A$ thắng ít nhất bảy trận và thua ít nhất bảy trận; Vì vậy, tổng cộng có ít nhất 15 đội tham gia giải đấu.

Điểm a) là hệ quả của điểm 6) trong dạng thành công này: dãy $e_n$ bắt đầu từ một vị trí nào đó là tuần hoàn, nghĩa là, $e_{n+T} = e_n$ đối với một số tự nhiên $T$ với mọi $n$ bắt đầu từ một số $N$. Điều này có nghĩa là với bất kỳ $n \geq N$ nào thì các số $c_n$ và $c_{n+T}$ đều có cùng tính chẵn lẻ. Nó theo sau đó

$$\frac{3}{2} c_n - \left[ \frac{3}{2} c_n \right] = \frac{3}{2} c_{n+T} - \left[ \frac{3}{2} c_{n+T} \right],$$

⟦folio 42⟧

ngồi xuống và vô số người không phải cem-
số;
b) tuần tự $e_n = (-1)^{c_n}$ không định kỳ;
c) có một số $\gamma$,
Cái gì
$$c_n = \left[ \left( \frac{3}{2} \right)^n \gamma \right] + 1.$$

và do đó $c_{n+1} - c_n = \frac{3}{2} (c_{n+1} - c_n)$. Nhưng rõ ràng
rằng không có dãy số vô hạn
các số trong đó mỗi số lớn hơn nửa mora lần
cái trước đó. (Trên thực tế, nếu một số hạng nhất quán có dạng $2^k \cdot r$, trong đó $r$ là số lẻ, thì $k + 1$ bước sau nó chúng ta sẽ gặp
số hạng $\frac{3^k + 1}{2}$ không phải là số nguyên.) Một mâu thuẫn.

c) Dễ dàng kiểm tra được điều đó với bất kỳ $n$ nào
$$c_{n+1} \leq \frac{3}{2} c_n, c_{n+1} - 1 \geq \frac{3}{2} (c_n - 1).$$

Posetom
$$\frac{c_n - 1}{(3/2)^n} \leq \frac{c_{n+1} - 1}{(3/2)^{n+1}} < \frac{c_{n+1}}{(3/2)^{n+1}} \leq \frac{c_n}{(3/2)^n}.$$

Độ dài của đoạn $\left[ \frac{c_n - 1}{(3/2)^n}; \frac{c_n}{(3/2)^n} \right]$ bằng $(2/3)^n$, - nó
có xu hướng bằng 0 khi $n \to \infty$, nên tất cả các đoạn này đều có một điểm chung duy nhất. Hãy biểu thị nó bằng $\gamma$.

Từ định nghĩa của $\gamma$ suy ra $(3/2)^n \gamma \in [c_n - 1; c_n]$.
Hơn nữa, đẳng thức $(3/2)^N \gamma = c_N$ là không thể đối với bất kỳ $N$ nào: từ đó sẽ dẫn đến $(3/2)^n \gamma = c_n$ đối với bất kỳ
số nguyên $n \geq N$ hoặc $c_{n+1} = \frac{3}{2} c_n$ cho bất kỳ số nguyên $n \geq N$,

điều này mâu thuẫn với những gì đã nói ở trên. Điều này có nghĩa là $[(3/2)^n \gamma] = c_n - 1$, đó là điều cần phải chứng minh.

Trong lời giải bài toán này, chúng tôi đã tận dụng nguyên tắc quan trọng của các phân đoạn có thể thu gọn, theo đó trình tự của các phân đoạn mặt phẳng
$$[a_1; b_1] \supset [a_2; b_2] \supset [a_3; b_3] \supset \dots,$$

độ dài $|a_n - b_n|$ có xu hướng về 0, chúng ta luôn có một số thực duy nhất; nguyên tắc này (hoặc bất kỳ nguyên tắc tương đương nào) được coi là một tiên đề. Nó thể hiện rõ tính chất rất đặc biệt của “mật độ” của trục số, không có “lỗ hổng” trong đó. Nguyên lý này có thể được chứng minh dựa trên định lý Weierstrass về giới hạn của dãy giới hạn đơn điệu.

Trong bài toán của chúng tôi, thật dễ dàng để chỉ ra các đầu bên phải của đoạn $n$-thứ cho một vài $n$ đầu tiên và từ đó tính toán gần đúng $\gamma$; ví dụ: với hai chữ số thập phân: $\gamma \approx 0,81$.

S. Konyatsin

**M481. Trong dãy số tự nhiên $a_1, a_2, a_3, \dots$, mỗi số hạng $a_{k+1}$ bằng tổng bình phương của số $b$ trong ký hiệu thập phân của số $a_k (k \geq 1)$. Hãy để chúng tôi chứng minh rằng với mọi $a_1$ số 1 hoặc số 89 sẽ kết thúc theo dãy này.**

Rõ ràng là tổng bình phương của các chữ số của số $x$ - hãy ký hiệu nó là $f(x)$ - đối với $x$ đủ lớn nhỏ hơn đáng kể so với chính số $x$. Vì vậy, nếu $x$ là số có bốn chữ số, tức là $10^3 \leq x < 10^4$, thì $f(x) \leq 4.9^2 = 364 < 10^3 \leq x$. Nói chung, nếu $10^{n-1} \leq x < 10^n$ và $n > 3$ thì $f(x) \leq 81n < 10^{n-1}$. (Bất đẳng thức cuối cùng dễ chứng minh bằng quy nạp: $81n < 10^{n-1} \Rightarrow 81 (n + 1) = 81n + 81 < 10^{n-1} + 81 < 10^n$.) Ta hãy chứng minh rằng với mọi $x$ ba chữ số thì cũng có $f(x) < x$. Nếu chữ số đầu tiên của số $x$ bằng $p > 1$ thì $f(x) < p^2 + 2 \cdot 81 = 162 + p^2 < 100p$ (điều này rất dễ xác minh cho mỗi $p = 2, 3, 4, \dots, 9$). Nếu chữ số đầu tiên $x$ là 1 và chữ số thứ hai $q$ thì $f(x) \leq 1 + q^2 + 81 < 100 + 10q \leq x$ cho bất kỳ $q = 1, 2, \dots, 9$ nào.

⟦folio none⟧

Do đó, với mọi số tự nhiên $a_1, a_2, a_3, \dots$, trong đó $a_{n+1} = f(a_n)$, (*)

gặp một số không vượt quá 99. Đối với số có hai chữ số và một chữ số, người ta tiến hành nghiên cứu các dãy tương ứng (*) bằng vũ lực. Việc tính toán được hỗ trợ bởi một bảng có tổng $i^2 + j^2$ tại giao điểm của hàng thứ $i$ và cột thứ $j$ - bảng này được đặt ở trên. Đối với bất kỳ $x \leq 99$ nào sẽ có $f(x) \leq 162$; do đó, tập hợp $X = \{1, 2, \dots, 162\}$ được ánh xạ vào chính nó: $f(x) \leq 162$ cho tất cả $x \leq 162$.

Cách cấu trúc ánh xạ $f$ tới tập hợp $X$ được thể hiện trong Hình 3: từ mỗi số $x$ có ​​một mũi tên đến số $f(x)$. Từ

Hình 3.

⟦folio 44⟧

Hình 3 cho thấy rằng đối với bất kỳ $a_1$ nào, chuỗi (*) sẽ nhập “điểm cố định” 1: đối với một số $N$ kết quả sẽ là $a_N = 1$ (và sau đó là $a_{N+1} = a_{N+2} = \dots$), hoặc sẽ rơi vào “chu kỳ” (dấu chấm) ... $\rightarrow$ $89 \rightarrow$ $145 \rightarrow$ $42 \rightarrow$ $20 \rightarrow$ $4 \rightarrow$ $16 \rightarrow$ $37 \rightarrow$ $58 \rightarrow$ $89 \rightarrow \dots$ (Do đó, số 89 trong các điều kiện có thể được thay thế bằng bất kỳ số nào trong bảy số khác của chu kỳ này; 89 chỉ đáng chú ý vì nó nằm cạnh "nhánh" mạnh nhất trong hình.) Điều này ngụ ý tuyên bố bài toán M481.

Đối với một bài toán tương tự, trong đó thay vì tổng bình phương của các chữ số, nó chỉ liên quan đến tổng các chữ số, thu được kết quả đơn giản hơn: sau nhiều lần áp dụng ánh xạ “$x \rightarrow$ tổng các chữ số $x$”, từ các số $a_1$, bội số của chín, kết quả là 9 và từ bất kỳ số nào $a_1$, không phải bội số của chín, phần còn lại của phép chia của $a_1$ đến 9 sẽ đạt được. Như vậy, có chín điểm cố định 1, 2, ..., 9 và bằng $a_1$ chúng ta có thể biết ngay điểm nào chúng ta sẽ chạm tới.

Tất nhiên, chúng ta có thể kết hợp $f$ các hàm khác, chẳng hạn như tổng các khối hoặc bốn thân chữ số, v.v. Đối với những ánh xạ này, người ta cũng có thể chứng minh rằng $f(x) < x$ đối với một $x$ đủ lớn, có nghĩa là các chuỗi có dạng (*) sớm hay muộn sẽ nhập một trong số hữu hạn các “chu kỳ” - đặc biệt, có lẽ, chúng kết thúc bằng một “chu kỳ có độ dài 1”, tức là ở một điểm cố định. Mặc dù những người hâm mộ đĩa kỹ thuật số có thể hài lòng khi tình cờ gặp những điểm cố định như $1^3 + 5^3 + 3^3 = 153$ (V. Panfilov) hoặc $1^4 + 6^4 + 3^4 + 4^4 = 1634$ (G. Gurevich), việc tìm kiếm tất cả các chu trình ở đây là một công việc khá tẻ nhạt, ngay cả khi bạn có máy tính trong tay.

**M483**). a) Chứng minh rằng tỉ số giữa bình phương bán kính đường tròn nội tiếp của một tam giác vuông với tổng các bình phương độ dài các đường trung tuyến vẽ từ các góc nhọn không vượt quá 1/20. b) Tìm giá trị lớn nhất mà tỉ số này có thể nhận được.

Gọi $a$ và $b$ là độ dài hai cạnh của tam giác, $c = \sqrt{a^2 + b^2}$ độ dài cạnh huyền, $r$ bán kính của đường tròn nội tiếp. Vì tổng bình phương của độ dài các đường trung tuyến được đề cập trong điều kiện bằng

$$\left(\frac{a}{2}\right)^2 + b^2 + \left(\frac{b}{2}\right)^2 + a^2 = \frac{5}{4} (a^2 + b^2) = \frac{5}{4} c^2,$$

trong bài toán chúng ta cần đánh giá tỷ lệ $4r^2/5c^2$. Lưu ý rằng

$$r = \frac{ab}{a+b+c} = \frac{ab}{a+b+\sqrt{a^2+b^2}} < \frac{a^2+b^2}{2\sqrt{a^2+b^2}} = \frac{c}{4},$$

kể từ $ab \leq (a^2+b^2)/2$ và $a+b > \sqrt{a^2+b^2}$. Từ đây ta được kết quả a):

$$\frac{4r^2}{5c^2} < \frac{4}{5\cdot 4^2} = \frac{1}{20}.$$

Một ước tính chính xác hơn (nó sử dụng các bất đẳng thức $a + b \geq 2\sqrt{ab}$ và $c^2 = a^2 + b^2 \geq 2ab$, trở thành các đẳng thức cho $a = b$):

$$\frac{r^2}{c^2} = \frac{a^2b^2}{(a+b+\sqrt{a^2+b^2})^2c^2} \leq \frac{ab}{2(2\sqrt{ab}+\sqrt{2ab})^2} = \frac{1}{4(1+\sqrt{2})^2},$$

nơi chúng tôi nhận được kết quả 6):

$$\frac{4r^2}{5c^2} \leq \frac{1}{5(3+2\sqrt{2})} = \frac{3-2\sqrt{2}}{5}$$

(tại $a = b$ chúng ta thu được đẳng thức, tức là ước tính là tốt nhất).

⟦folio 45⟧

bài toán này cho phép lời giải khác sử dụng thông điệp hình học. Hãy cho hai lời giải.

1°. Nếu chúng ta tiếp tục vẽ đường chéo của hình vuông trong Hình 4 cho đến khi nó cắt cạnh huyền, chúng ta sẽ có bissertis của một góc vuông; hãy biểu thị độ dài của nó bằng $l$. Vì vậy $r + r\sqrt{2} \leq l$. Nhưng bissertis trong bất kỳ tam giác nào đều nằm giữa chiều cao $h$ và đường trung tuyến, chiều dài của đường trung bình trong một tam giác vuông có cạnh huyền dài $c$ là $c/2$. Do đó $r(1 + \sqrt{2}) \leq c/2$, chúng ta nhận được kết quả từ đâu.

2°. Chúng ta hãy sửa một đoạn $AB$ có độ dài $c$. Đặt $C$ là điểm bất kỳ của hình bán nguyệt có đường kính $[AB]$ (khi đó $ACB = 90^\circ$) và $M$ là tâm đường tròn nội tiếp của tam giác $ABC$. Bằng cách tìm kiếm $AMB = 135^\circ$, các điểm $M$ nằm trên cung tại $90^\circ$ có các đầu $A$, $B$ và do đó khoảng cách từ $M$ đến đường thẳng $AB$ (bán kính $r$ của đường tròn nội tiếp) sẽ lớn nhất khi $M$ nằm ở giữa của cung này, tức là khi tam giác vuông $ABC$ là đều.

N. Vasiliev

M484. Với kikh p sucestium vipukly p-uezdnik, cái nào có thể được cắt thành nhiều đa giác đều (không nhất thiết phải giống hệt nhau)?

Hình 4.

Bây giờ chúng ta sẽ chứng minh rằng đối với $3 \leq n \leq 12$ thì n-quận cũng là sucestium, nhưng đối với $n > 12$ thì không phải vậy.

Chúng ta hãy biểu thị sự chia $n$-gon cho $M$. Một đa giác bên phải tham gia xếp lớp $M$ được gọi là tốt nếu có ít nhất một trong các đỉnh của nó là đỉnh của đa giác $M$.

(Hơn nữa, khi nói về các đa giác xếp kề, từ đa giác chúng ta sẽ luôn có nghĩa là đa giác đều.)

Bằng chứng của chúng tôi sẽ bao gồm một số điểm.

1°. Lưu ý rằng tại đỉnh của đa giác $M$ không quá hai đa giác đều có thể hội tụ và đây là hai hình tam giác, hoặc một hình tam giác và một hình vuông, hoặc một hình tam giác và một hình chữ nhật.

Tuyên bố này ngay lập tức xuất phát từ thực tế là độ lớn của mỗi góc $M$ nhỏ hơn $180^\circ$ và độ lớn của góc của một đa giác đều tùy ý không nhỏ hơn $60^\circ$, và ngoài ra, chỉ có thể có các kết hợp sau: $60^\circ + 60^\circ$, $60^\circ + 90^\circ$, $60^\circ + 108^\circ$.

Từ nhận xét của chúng tôi, chúng tôi suy ra rằng nếu một $k$-gon $c$ $k \geq 6$ thông thường liền kề với đỉnh của đa giác $M$, thì các cạnh của nó sẽ chạy dọc theo các cạnh $M$.

2°. Hãy để chúng tôi chứng minh rằng một $k$-giác thông thường cho $k > 6$ không thể tốt. Hãy giả sử điều ngược lại. Sau đó, nếu nó tốt và nếu tất cả các đỉnh của nó trùng với các đỉnh của $M$ thì nó trùng với $M$ và chúng ta giả sử rằng $M$ được chia thành ít nhất hai đa giác. Nếu anh ta tìm thấy hai đỉnh lân cận $A$ và $B$ của một k-giác, một trong số đó ($A$) là đỉnh $M$, và đỉnh còn lại ($B$) không phải (Hình 5), thì tại đỉnh $B$ một góc được vẽ có độ lớn nhỏ hơn $60^\circ$ (trong Hình 5) là như vậy bóng mờ), không thể lấp đầy các góc của đa giác đều. Sự mâu thuẫn.

3°. Vì một hình lục giác đều có thể được chia thành các hình tam giác đều nên chúng ta giả sử rằng các hình lục giác không liên quan đến phép chia.

Với điều kiện này, chúng ta thấy rằng hình tam giác, hình vuông và hình chữ nhật đều có thể tốt.

4°. Hãy để chúng tôi chứng minh rằng nếu trong ô xếp $M$ có một hình chữ nhật tốt (chúng tôi biểu thị nó bằng chữ cái $П$) thì đó không thể là điểm trong của cạnh của đa giác $M$ hoặc bất kỳ đa giác nào của ô xếp (ngược lại tại điểm này

⟦folio 46⟧

một góc “xấu” sẽ được hình thành, không được lấp đầy bởi các đa giác đều - xem Hình 6, a, 6). Do đó, mỗi đỉnh $P$ hoặc là đỉnh $M$ hoặc nằm hoàn toàn bên trong $M$ và là đỉnh chung của một số đa giác khác của phân vùng.

Giả sử rằng có hai đỉnh lân cận $P$, một trong số đó $(A)$ là đỉnh $M$ và $(B)$ còn lại nằm hoàn toàn bên trong $M$. Hãy để chúng tôi chứng minh rằng điều này là không thể. Trên thực tế, vì $B$ là một đỉnh chung của đa giác, một trong số đó là hình ngũ giác, nên chúng ta cần lấp đầy góc tại $360^\circ - 108^\circ = 252^\circ$ bằng đa giác đều. Không khó để nói rằng góc này không thể được lấp đầy bằng bốn (hoặc nhiều) đa giác: bốn hình tam giác là không đủ, nhưng ba hình tam giác và một hình vuông đã là quá nhiều rồi $(4.60^\circ = 240^\circ < 252^\circ; 3.60^\circ + 90^\circ = 270^\circ > 252^\circ)$. Điều này có nghĩa là chúng ta có thể cố gắng lấp đầy góc ở $252^\circ$ bằng hai hoặc ba đa giác xếp kề nhau.

Nếu có ba đa giác thì một trong số chúng nhất thiết phải là hình tam giác $(3.90^\circ = 270^\circ > 252^\circ)$; vì vậy trong trường hợp này có một góc $252^\circ - 60^\circ = 192^\circ$ còn lại để lấp đầy hai đa giác. Đặt đây là một số $k$- và $m$-gons. Sau đó

$$180^\circ \left(1 - \frac{2}{k}\right) + 180^\circ \left(1 - \frac{2}{m}\right) = 192^\circ,$$

$$\frac{1}{k} + \frac{1}{m} = \frac{7}{15},$$

và nếu $k \leq m$ thì $\frac{2}{k} \geq \frac{7}{15}$, do đó $k \leq \frac{30}{7} < 5$ (và $k \geq 3$).

Đối với $k = 4$ chúng tôi nhận được $m = \frac{60}{13}$ - không phải là số nguyên; do đó, hình vuông không thể tham gia lấp đầy góc giá trị $192^\circ$. Vì lý do tương tự, hình tam giác không thể tham gia vào việc lấp đầy nó: với $k = 3$ chúng ta nhận được $m = \frac{15}{2}$. Điều này có nghĩa là góc ở $192^\circ$ là "xấu" và do đó góc ở $252^\circ$ không thể điền vào các hình tam giác.

Nếu có hai đa giác thì

$$180^\circ \left(1 - \frac{2}{k}\right) + 180^\circ \left(1 - \frac{2}{m}\right) = 252^\circ (k \leq m),$$

Ở đâu

$$\frac{1}{k} + \frac{1}{m} = \frac{3}{10}.$$

Hãy tự mình xem rằng vì mục đích của số $k, m, k \leq m$ phương trình này chỉ có lời giải: $k = 5, m = 10$ và $k = 4, m = 20$. Hãy để chúng tôi chứng minh rằng không ai trong số họ là phù hợp. Thật vậy, ở đỉnh $B$, không thể áp dụng hình ngũ giác, hình thập giác hay hình thập giác cho cạnh $[AB]$ của hình ngũ giác $P$ (chúng có các góc ngoài “xấu” - $72^\circ, 36^\circ$ và $18^\circ$, tương ứng); Điều này có nghĩa là tại đỉnh $B$ một hình vuông phải được áp dụng cho $[AB]$. Dễ hiểu là khi đó tất cả các đa giác liền kề với $[AB]$ đều phải là hình vuông (Hình 7), điều này là không thể, vì đỉnh của góc “tự do” tại đỉnh $A$ nhỏ hơn $72^\circ < 90^\circ$.

Điều này có nghĩa là một hình ngũ giác tốt không thể có đỉnh bên trong $M$. Điều này chứng tỏ Phát biểu 4: nếu một hình ngũ giác tham gia xếp $M$ là tốt thì tất cả các đỉnh của nó đều là đỉnh $M$.

$5^\circ$ Dễ hiểu là đa giác không thể áp dụng phép chia cho các cạnh trạng thái (bắt đầu từ đỉnh chung của các đa giác này, theo những gì đã được chứng minh, cũng là đỉnh của góc $M$, ít nhất ba đa giác sẽ hội tụ, một trong số đó là hình ngũ giác và tổng các góc

⟦folio 47⟧

Hình 9.

Hình 10.

Hình 11.

Hình 12.

sẽ không nhỏ hơn 108° + 2·60° > 180°). Do đó, các đa giác ốp lát chỉ có thể được áp dụng cho các cạnh không liền kề của một hình chữ nhật tốt. Đặt $[AB]$ là cạnh của hình ngũ giác $I$, áp dụng một số đa giác ốp lát khác (Hình 8). Đặt $A_1$ và $B_1$ là hai đầu thứ hai của cạnh đa giác $M$, lần lượt nổi lên từ các đỉnh $A$ và $B$ ($A_1$ và $B_1$ không phải là các đỉnh của hình ngũ giác $I$; có thể là $A_1 = B_1$). Chúng ta hãy biểu thị bằng $C$ điểm giao nhau của $(AA_1)$ với $(BB_1)$. Khi đó $\triangle ACB$ là một hình tam giác đều, bên trong chứa tất cả các đa giác phân vùng nằm phía trên $[AB]$ (nếu $\Pi$ nằm dưới $[AB]$, như trong Hình 8).

6°. Hãy chứng minh rằng tất cả các đa giác của phân vùng nằm bên trong $\triangle ABC$ (Hình 8) đều là hình tam giác.

Giả sử điều ngược lại - giả sử có "không phải hình tam giác". (Chúng ta sẽ giả sử rằng bên $[AB]$ theo chiều ngang.) Hãy xem xét gần nhất với $[AB]$ đỉnh (thấp nhất) của một hình không phải tam giác; nếu có nhiều đỉnh như vậy thì lấy đỉnh ở giữa bên phải nhất. Chúng ta hãy biểu thị đỉnh “thấp nhất” và đỉnh ngoài cùng bên phải này bằng $D$. chấm $D$ không thể nằm nghiêng $[AB]$: Nếu không phải tam giác được định vị như trong Hình 9, $a$, thì một góc không lớn hơn $\frac{180° - 90°}{2} = 45°$ - "xấu"; nếu vậy, như trong Hình 9, $b$và “không phải tam giác” - “không vuông”, sau đó một lần nữa chúng ta nhận được một góc “xấu” (chúng tôi đã đồng ý rằng “không phải tam giác” - và “không phải hình lục giác”); nếu “không phải tam giác” là hình vuông thì từ phải đến đỉnh $D$ áp dụng lại hình vuông (Hình 9, $\theta$), và do đó, đỉnh $D$ - không phải cái đúng. chấm $D$ không thể nằm nghiêng $[AA_1]$ Và $[BB_1]$ đa giác $M$: kết thúc $A_1$ Và $B_1$ - không gần nhất $[AB]$, và nếu $D$ - điểm bên trong $[AA_1]$ hoặc $[BB_1]$, thì “không phải tam giác” phải nằm hoàn toàn bên trong một góc 60° (Hình 10, $a$, $\theta$), điều đó là không thể.

Vì vậy, các điểm $D$ là điểm bên trong của vùng $AA_1 \dots B_1B$ của đa giác $M$. Vì tất cả các “không phải tam giác” hội tụ tại $D$ phải nằm không thấp hơn các góc ở đỉnh $D$ không quá 180°. Điều này có nghĩa là đây là hai hình vuông hoặc chỉ có một "không phải tam giác" có đỉnh ở $D$. Nếu đây là hai hình vuông thì chỉ theo chiều ngang - như trong Hình 11; nhưng khi đó đỉnh $D$ không phải là đỉnh ngoài cùng bên phải của “không phải tam giác”. Nếu chỉ có một “không phải tam giác” trong $D$ (ví dụ: $k > 4$, $k \neq 6$) và các đa giác còn lại của phân vùng là hình tam giác, thì

$$360^\circ - 180^\circ \left(1 - \frac{2}{k}\right) = 60^\circ n$$

(n - tự nhiên). Do đó $k = \frac{6}{n - 3}$. Trong số tự nhiên, phương trình này cũng có lời giải: $n = 4, k = 6$;

⟦folio 48⟧

Hình 13.
Hình 14,
Hình 15.
Hình 16.
Hình 17.
Hình 18.
Hình 19.
Hình 20.
Hình 21.
Hình 22.

$n = 5, k = 3; n = 6, k = 2; n = 9, k = 1$. Không có cái nào phù hợp với chúng tôi (chúng tôi có $k > 4$ và $k \neq 6$). Kết quả mâu thuẫn chứng minh khẳng định $6^\circ$: tất cả các đa giác của phân vùng nằm bên trong $\Delta ABC$ đều là hình tam giác.

$7^\circ$. Hãy chứng minh rằng nếu trong số các đa giác tốt có một hình chữ nhật thì $M$ có nhiều nhất chín cạnh (có thể $n \leq 9$).

Thật vậy, nếu $A_1 \neq B_1 \neq C$ thì $M$ có các góc tại các đỉnh $A_1$ và $B_1$ có độ lớn bằng $120^\circ$ (tại các đỉnh $A_1$

⟦folio 49⟧

và $B_1$ tam giác hội tụ - một hoặc hai; không thể có một tại $A_1$ hoặc tại $B_1$, vì trong trường hợp này tổng độ lớn của các góc tại các đỉnh $A_1$ và $B_1$ bằng $360^\circ - 2\cdot 60^\circ = 240^\circ$ hoặc $360^\circ - 60^\circ - 120^\circ = 180^\circ$ và nó phải hoàn toàn nhỏ hơn $180^\circ$). Vì đa giác $M$ lồi nên điều này có nghĩa là đoạn $[A_1B_1]$ là cạnh của nó.

Do đó, nếu một hình ngũ giác tốt tham gia vào việc chia đa giác $M$, thì một đa giác có thể được áp dụng cho không quá hai cạnh của hình ngũ giác này và đây là hình tam giác đều hoặc hình thang đều (Hình 12). Tuyên bố $7^\circ$ xuất phát từ điều này.

$8^\circ$. Bây giờ chúng ta hãy chứng minh rằng nếu đa giác lồi $M$ có thể chia thành các đa giác đều thì nó có nhiều nhất là hai mươi cạnh (tức là $n \leq 12$). Giả sử điều ngược lại: đặt $n > 12$. thì từ các điểm $3^\circ$ và $7^\circ$ suy ra rằng trong số các đa giác tốt tham gia chia đa giác $M$ chỉ có hình tam giác và hình vuông. Do đó, giá trị của mỗi góc của nó có dạng $90^\circ k + 60^\circ m$ ($k \geq 0, m \geq 0, k \in N, m \in N$) và chia cho 30; vì $90^\circ k + 60^\circ m < 180^\circ$, độ lớn của mỗi góc $M$ tối đa là $150^\circ$. Do đó, giá trị của mỗi góc ngoài của nó không nhỏ hơn $30^\circ$, và khi đó tổng tất cả các góc ngoài của nó không nhỏ hơn $13\cdot 30^\circ > 360^\circ$ - một mâu thuẫn.

Ví dụ về các đa giác được chia có các khay, bốn, ..., mười hai cạnh được thể hiện trong Hình 13-22.

S. Mironov

F493. Mặt Trăng có ảnh hưởng gì đến quỹ đạo Trái Đất quay quanh Mặt Trời?

Hình 23.

Như đã biết, dưới tác dụng của lực hấp dẫn, Mặt Trăng và Trái Đất quay quanh kính thiên văn và điểm $P$ (Hình 23). Tâm Mặt Trăng chuyển động dọc theo đường tròn bán kính $r_\perp \approx 380\ 000$ km, còn tâm Trái Đất chuyển động dọc theo đường tròn bán kính $r_3 \approx 4700$ km. Dưới tác dụng của lực hấp dẫn của Mặt trời, hệ Trái đất-Mặt trăng quay quanh điểm $P$, rồi quay quanh điểm kia. Khi di chuyển xung quanh điểm otectori $P$, Tâm Trái đất có khoảng cách $S = 2\pi r_3 \approx 29\ 500$ km và tốc độ tuyến tính của nó $v = S/T_\perp \approx 12.5$ m/s hơi vượt quá tốc độ kỷ lục của một người ($\approx 10$ m/s). Tốc độ tuyến tính của chuyển động quỹ đạo của điểm $P$ bằng $V \approx 30$ km/s.

Phần quỹ đạo đi qua điểm $P$ trong thời gian tương đối ngắn có thể được coi là đường thẳng. (Trong một ngày, vectơ bán kính của điểm $P$ quay một góc $\alpha \approx \frac{2\pi}{365} \approx 0.99^\circ$ và cung đi qua điểm $P$ có thể được coi là một đoạn thẳng.) Nói cách khác, tốc độ của điểm $P$ trong một khoảng thời gian ngắn có thể được coi là không đổi theo hướng. Trong một khoảng thời gian ngắn, hình chiếu của tốc độ $v$ lên hướng chuyển động dọc theo quỹ đạo chính có thể được viết dưới dạng $v_0 = v \sin(\omega t + \varphi_0)$, trong đó tần số quay là $\omega = v/r_3$ và pha ban đầu $\varphi_0$ chỉ liên quan đến việc lựa chọn điểm bắt đầu thời gian $t$. Mô hình tốc độ của tâm Trái đất so với Mặt trời trong một khoảng thời gian ngắn.

⟦folio 50⟧

hình 25.

F494. Trong mạch hiển thị ở Hình 26, $R_2=90$ Ohm, $R_3=300$ Ohm, $R_4=60$ Ohm, $L_2=90$ G. Các giá trị của $R_1$ và $L_1$ là bao nhiêu nếu không có dòng điện chạy qua điện kế $G$, bất kể nguồn được kết nối với cực a và b dốc hay moka xen kẽ?

Hình 26.

F495. Ba chất lỏng không thể thay thế có mật độ $\rho_1$, $\rho_2$ và $\rho_3$ lấp đầy một ống đơn hình kín, tạo thành một vòng, mặt phẳng thẳng đứng.

$$\vec{V}_3 = V + v_0 = V + v \sin(\omega t + \varphi_0).$$

Như vậy, trong một khoảng thời gian ngắn, quỹ đạo của Trái Đất quanh Mặt Trời là một sóng hình sin (phần sóng hình sin). Toàn bộ quỹ đạo của Trái đất trong một vòng quay hoàn toàn của điểm $P$ quanh Mặt trời có thể được biểu diễn gần đúng dưới dạng các phần liên tiếp của sóng hình sin, “uốn cong” thành một vòng tròn. Số dao động do Trái đất tạo ra xung quanh quỹ đạo chính trong một năm rõ ràng là 1 năm/$T_\pi \approx 13.5$. Vậy là sau một năm, tâm Trái Đất không còn ở vị trí “năm ngoái”.

Chúng ta thấy rằng, nói một cách chính xác, không có sự lặp lại trong chuyển động của Trái đất, tức là đối với chuyển động của Trái đất quanh Mặt trời thì không thể đưa ra khái niệm về một thời kỳ cách mạng. Từ quan điểm toán học, chuyển động của toàn bộ hệ thống Trái đất-Mặt trăng là tuần hoàn.

Hình 25 biểu diễn sơ đồ quỹ đạo của tâm Trái đất quanh Mặt trời.

A. Dozorov

Việc không có dòng điện chạy qua điện kế có nghĩa là điện thế và pha của chúng tại các điểm $c$ và $d$ là như nhau. Do đó $u_{cn} = u_{dn}$, $u_{cm} = u_{dm}$ và $\frac{u_{cn}}{u_{cm}} = \frac{u_{dn}}{u_{dm}}$. Vì tỷ số của độ lệch hướng trong các phần kế tiếp của mạch tỷ lệ với tỷ lệ trở kháng của các phần này nên

$$\frac{R_3}{\sqrt{R_1^2 + \omega^2 L_1^2}} = \frac{R_4}{\sqrt{R_2^2 + \omega^2 L_2^2}},$$

hoặc

$$R_1^2 R_4^2 - R_2^2 R_3^2 + \omega^2 \left(L_1^2 R_4^2 - L_2^2 R_3^2\right) = 0.$$

Đẳng thức này phải đúng với mọi giá trị $\omega$. Điều này có nghĩa là hệ số của $\omega^2$ phải bằng 0, tức là

$$L_1^2 R_4^2 - L_2^2 R_3^2 = 0,$$

và do đó

$$R_1^2 R_4^2 - R_2^2 R_3^2 = 0.$$

(Dễ dàng kiểm tra rằng trong trường hợp này $\frac{L_1}{R_1} = \frac{L_2}{R_2}$, do đó pha của điện thế tại các điểm $c$ và $d$ là giống nhau.)

Từ các phương trình cuối cùng chúng ta tìm thấy:

$$L_1 = L_2 \frac{R_3}{R_4} = 450 \Gamma,$$

$$R_1 = \frac{R_2 R_3}{R_4} = 450 \Omega.$$

Áp suất bên trong ống tại các điểm $A$ và $B$ là như nhau; áp suất tại các điểm $C$ và $D$ cũng như nhau. Điều này có nghĩa là $\rho_1 gh_1 = \rho_2 gh_2 + \rho_3 gh_3$.

Nhưng $h_3 = h_1 - h_2$. Sử dụng mối quan hệ này, chúng ta thu được $(\rho_1 - \rho_3) h_1 = (\rho_2 - \rho_3) h_2$. (TÔI)

⟦folio 51⟧

(Hình 27). Một chất lỏng có mật độ $\rho_1$ lấp đầy cung tròn với góc $\alpha_1$, chất lỏng có mật độ $\rho_2$ lấp đầy cung tròn $\alpha_2$. Góc $\alpha$ cần bằng bao nhiêu để bán kính thẳng đứng của vòng vẽ tới ranh giới của các chất lỏng này? Hiệu ứng bề ngoài không thể bỏ qua.

Hình 27.

F496. Một tia phân kỳ của dây dẫn dương có góc lệch nhỏ $\alpha$ được đưa vào tụ điện hình trụ tại điểm A (Hình 28). Tất cả chúng trong chùm tia đều có năng lượng như nhau. Những vật có vectơ vận tốc tại điểm A hướng vuông góc với AO chuyển động dọc theo một đường tròn bán kính $AO=r_0$, đồng tâm với các bản tụ. Chứng minh rằng chùm tia yun sẽ tập trung tại điểm B bởi makoi, tức là $\widehat{AOB} = \pi/\sqrt{2}$. Xác định chiều dài chùm tia tối đa.

Hình 28.

Hình 29.

Từ hình bạn có thể thấy: $h_1 = R \cos \alpha + R \cos (\pi - \alpha - \alpha_1) = R [\cos \alpha - \cos (\alpha + \alpha_1)]$ và $h_2 = R \cos \alpha - R \cos (\alpha_2 - \alpha)$, trong đó $R$ là bán kính của chiếc nhẫn. Thay thế các biểu thức này cho $h_1$ và $h_2$ thành đẳng thức (1), chúng ta tìm thấy $(\rho_1 - \rho_3) [\cos \alpha - \cos \alpha \cos \alpha_1 + \sin \alpha \sin \alpha_1] = (\rho_2 - \rho_3) [\cos \alpha - \cos \alpha_2 \cos \alpha - \sin \alpha_2 \sin \alpha]$ hoặc $(\rho_1 - \rho_3) (1 - \cos \alpha_1 + \sin \alpha_1 \tg \alpha) = (\rho_2 - \rho_3) (1 - \cos \alpha_2 - \sin \alpha_2 \tg \alpha)$. Giải phương trình này, ta tìm được $\tg \alpha = \frac{(\rho_1 - \rho_3) (1 - \cos \alpha_1) - (\rho_2 - \rho_3) (1 - \cos \alpha_2)}{(\rho_1 - \rho_3) \sin \alpha_1 + (\rho_2 - \rho_3) \sin \alpha_2}$.

Để có thể nghiên cứu chuyển động của tụ điện hình trụ, trước hết cần tìm hiểu xem lực nào tác dụng lên nó trong điện trường của tụ điện hình trụ, tức là tìm ra hướng của điện trường của tụ điện là gì.

Điện áp trường tỷ lệ thuận với mật độ của các đường mận. Nếu $n$ đường mận đi qua một cung có góc đơn vị thì $N = n\varphi$ đường mận đi qua một cung có góc $\varphi$. Mật độ của các đường mận đi qua một cung có bán kính $r$ bằng tỷ lệ của số $N$ với chiều dài $r\varphi$ của cung, tức là bằng $\frac{n}{r}$ (Hình 29).

Do đó, điện áp kích từ của tụ $\frac{1}{r}$:

$$E = -\frac{b}{r}, b = \text{const.}$$

Trong một trường như vậy, điện tích $q$, nằm cách tụ điện một khoảng $r$, chịu tác dụng của một lực $\vec{F}$ sao cho

$$|\vec{F}| = \frac{bq}{r}.$$

Lực này truyền cho điện tích một gia tốc $a$ mô đun bằng nhau

$$|\vec{a}| = \frac{bq}{rm},$$

trong đó $m$ là khối lượng điện tích.

Chúng ta biểu thị bằng $x$ độ lệch của nó so với quỹ đạo chính có bán kính $r_0$ (quỹ đạo này được thể hiện trong Hình 28 bằng đường màu đỏ). Sau đó $r = r_0 + x$, và

$$|\vec{a}| = \frac{bq}{m(r_0 + x)}.$$

Chúng ta hãy xem xét chuyển động của nó trong hệ thống cắt, biểu thị xung quanh trục của tụ điện sao cho vận tốc góc của nó tại mỗi thời điểm bằng tốc độ góc $\omega$ của tụ bị lệch. Trong hệ thống này, gia tốc không còn bằng $a$, vì tất cả các điểm cũng chuyển động với một gia tốc nào đó so với hệ thống cắt tĩnh liên kết với trục của tụ điện. Một điểm cách trục một khoảng $r_0 + x$ sẽ chuyển động với gia tốc trung tâm $\|\vec{a}_\mu\| = \omega^2(r_0 + x)$.

⟦folio 52⟧

Vì vậy, trong hệ thống báo cáo luân phiên, gia tốc bằng

$$\left| \vec{a}_{\text{OTH}} \right| = - \left| \vec{a} \right| + \left| \vec{a}_{\text{II}} \right| = - \frac{bq}{m(r_0+x)} + \omega^2(r_0+x).

$$\text{Định luật bảo toàn động lượng góc suy ra điều đó}

$$m(r_0+x)^2\omega = mr_0^2\omega_0,

$$\text{where } \omega_0 \text{ là vận tốc góc của nano tại điểm } A. \text{ Nó cũng bằng tốc độ góc của nano chuyển động dọc theo quỹ đạo “đỏ”. Nhưng gia tốc hướng tâm } \left| \vec{a__0 \right| = \omega_0^2 r_0 \text{ inu chuyển động dọc theo quỹ đạo bán kính “đỏ” } r_0, \text{ truyền lực } \vec{F}, có độ lớn } \frac{bq}{r_0}, \text{ do đó}

$$\omega_0^2 r_0 = \frac{bq}{mr_0}, \text{ и } \omega_0^2 = \frac{bq}{mr_0^2}.

\text{Takим образом,}

$$\left| \vec{a}_{\text{OTH}} \right| = - \frac{bq}{m(r_0+x)} + \frac{bq}{mr_0^2}(r_0+x) \frac{r_0^4}{(r_0+x)^4} =

= \frac{bq\left[r_0^2-(r_0+x)^2\right]}{m(r_0+x)^3} = \frac{bq\left(-2r_0x-x^2\right)}{m(r_0+x)^3}.

\text{Tại } x << r_0

$$\left| \vec{a}_{\text{OTH}} \right| = -2 \cdot \frac{bq}{mr_0^2} x.

\text{Мы видим, что}

$$m\trái| \vec{a__{\text{OTH}} \right| = -kx, \text{ trong đó } k = 2 \cdot \frac{bq}{r_0^2}.

\text{Như đã biết, với sự phụ thuộc như vậy của gia tốc của vật vào chuyển vị, vật sẽ thực hiện dao động điều hòa với một chu kỳ } T = 2\pi\sqrt{\frac{m}{k}}. \text{ Do đó, chúng là những chùm tia có tốc độ tại điểm } A \text{ tạo thành một góc nhỏ } \alpha \text{ với tốc độ của các tia chuyển động dọc theo quỹ đạo chính sẽ thực hiện dao động điều hòa hướng tâm với chu kỳ so với quỹ đạo chính}

$$T = 2\pi\sqrt{\frac{mr_0^2}{2bq}}.

\text{Этот период одинаков для всех инов. Значит, после того как инов попадают в конденсатор в точке } A \text{ через времена } t_n = n\frac{T}{2}(n=1,2,3,\dots), \text{ все инов будут оказаться в одной и той же точке основной траектории — будут фокусироваться. Нетрудно найти угол } \varphi_0 \text{ между последовательными фокусами:}

$$\varphi_0 = \omega_0 t = \omega_0 \frac{T}{2} = \sqrt{\frac{bq}{mr_0^2}} \cdot \pi \sqrt{\frac{mr_0^2}{2bq}} = \frac{\pi}{\sqrt{2}}.

\text{Do đó, nếu } \widehat{AOB} = \pi/\sqrt{2}, \text{ thì các ion sẽ tập trung tại điểm } B.

\text{Bây giờ hãy tìm chiều rộng tối đa của chùm tia. Để làm điều này, chúng ta lợi dụng thực tế là giá trị tuyệt đối lớn nhất của tốc độ của một vật thực hiện các dao động điều hòa và biên độ } x_{\text{max}} \text{ của các dao động ghép của nó}

⟦folio 53⟧

Tuân thủ

$$|\vec{v}|_{\max} = x_{\max} \Omega,$$

trong đó $\Omega = 2\pi/T$ là tần số dao động. Trong trường hợp của chúng tôi
$$|\vec{v}|_{\max} \text{ равно значению радиальной проекции скорости в точке } A \text{ иона (рис. 30):}$$
$$|\vec{v}|_{\max} = |\vec{v}_0| \sin \frac{\alpha}{2} = \omega r_0 \sin \frac{\alpha}{2} \approx \frac{1}{2} \omega r_0 \alpha$$
(vì $\alpha$ nhỏ, $\sin \frac{\alpha}{2} \approx \frac{\alpha}{2}$). Pozny
$$\frac{1}{2} \omega r_0 \alpha = x_{\max} \frac{2\pi}{T}.$$

Do đó, chiều rộng tối đa $d$ của chùm tia bằng
$$d = 2x_{\max} = \frac{\omega r_0 \alpha T}{2\pi} = \frac{r_0 \alpha}{\sqrt{2}}.$$

F497. Một đĩa có bán kính $r$, chuyển động với vận tốc góc $\omega$, được ném với vận tốc $v$ một góc $\alpha$ so với phương ngang. Mặt phẳng của đĩa vẫn thẳng đứng trong quá trình chuyển động của nó. Bán kính là độ cong của quỹ đạo của điểm cao nhất của đĩa tại thời điểm đĩa đạt độ cao tăng tối đa.

Tại thời điểm đĩa đạt đến độ cao tối đa khi nâng lên, vận tốc tâm của đĩa sẽ hướng theo phương ngang và giá trị tuyệt đối của nó sẽ bằng $|\vec{v}| \cos \alpha$. Vì đĩa đang chuyển động quanh tâm với vận tốc góc $\omega$, nên tốc độ tuyến tính của các điểm của đĩa trong hệ tọa độ chuyển động theo chiều ngang với cùng tốc độ với tâm của đĩa bằng $\omega r$ và gia tốc của chúng có độ lớn bằng $\omega^2 r$ và hướng về tâm của đĩa. Trong hệ tọa độ liên quan đến mặt đất, tốc độ $u$ của điểm cao nhất của đĩa tại thời điểm đĩa đạt độ cao nâng tối đa được hướng theo chiều ngang và $|\vec{u}| = |\vec{v}| \cos \alpha + \omega r$. Gia tốc $a$ của điểm này tại thời điểm này được hướng theo phương thẳng đứng và $|\vec{a}| = \omega^2 r + |\vec{g}|$. Do đó, tại thời điểm này điểm đang chuyển động dọc theo một đường tròn có bán kính được xác định bởi hệ thức

$$|\vec{a}| = \frac{u^2}{R}.$$

Từ đây

$$R = \frac{u^2}{|\vec{a}|} = \frac{\left(|\vec{v}| \cos \alpha + \omega r\right)^2}{\omega^2 r + |\vec{g}|}.$$

I. Slobodetsky

⟦folio 55⟧

giới hạn

Đối với khái niệm dãy giới hạn được giới thiệu trong sách giáo khoa (phần 26), sẽ rất hữu ích nếu bổ sung thêm hai dãy nữa: dãy $(x_n)$ được gọi là bị chặn từ trên nếu có một số $M$ sao cho với mọi $n$
$x_n \leqslant M$;
 tiếp theo $(x_n)$ được gọi là sizu hữu hạn nếu có một số như vậy $m$cái đó dành cho tất cả mọi người $n$
$x_n \geqslant m$.

Rõ ràng, dãy $(x_n)$ bị chặn khi và chỉ nếu nó bị chặn trên và dưới.

Tại nhà vợ

5. Cho bốn ví dụ về dãy: giới hạn từ phía trên nhưng không giới hạn từ phía dưới; hạn chế hơi xanh, nhưng không phải từ trên cao; không bị giới hạn ở dưới hoặc ở trên; hạn chế cả bên dưới và bên trên.

6. Chứng minh rằng dãy số không giảm thì bị chặn ở dưới và dãy số không tăng thì bị chặn ở trên.

Sự tồn tại sẽ trở nên rõ ràng hơn nếu chúng ta mô tả nó dưới dạng một cái bàn. Bất kỳ chuỗi nào cũng có (dấu + trong bảng bên dưới) hoặc không có (dấu -) một trong hai thuộc tính được chỉ ra phía trên cột “đầu vào” của bảng. Như vậy sẽ có bốn khả năng xảy ra. Trong ba trường hợp, các định lý được xây dựng ở trên có thể khẳng định sự tồn tại (+ dấu ở cột “đầu ra” của bảng) hoặc không tồn tại (dấu -) của giới hạn. Trong trường hợp thứ tư (dòng thứ ba của bảng), không thể nói gì về định nghĩa (xem Bài tập 7).

Sự tồn tại của một giới hạn

Sách giáo khoa chứng minh nếu một dãy có giới hạn thì nó bị chặn (phần 26). Do đó, nếu một dãy không bị giới hạn thì nó không có giới hạn.

Ngoài ra, sách giáo khoa còn xây dựng định lý nêu ở đầu bài. Weierstrass: nếu một dãy đơn điệu và bị chặn thì nó có giới hạn (mục 32).

⟦folio 56⟧

Định lý Weierstrass lưu lại nhiều phép tính toán học mà nếu không thì sẽ trở nên lỏng lẻo. Hãy so sánh hai phép tính.

Ví dụ 1. Hãy đặt

$$x = \sqrt{2 + \sqrt{2 + \sqrt{2 + \ldots}}}$$

(số lượng gốc là vô hạn). Lưu ý rằng dưới căn bậc nhất có 2+x. Giải phương trình

$$x = \sqrt{2 + x},$$

chúng tôi nhận được $x=2$.

Ví dụ 2. Hãy đặt

$$x = 1 + 2 + 4 + 8 + 16 + 32 + \ldots$$

(số lượng thuật ngữ là vô hạn). Lưu ý rằng

$$x = 1 + 2 + 4 + 8 + 16 + \ldots = 1 + 2(1 + 2 + 4 + 8 + \ldots) = 1 + 2x.$$

Giải phương trình

$$x = 1 + 2x,$$

chúng tôi nhận được $x=-1$.

Lý do tương tự, nhưng trong ví dụ thứ hai, chúng ta thấy rõ ràng là vô nghĩa. Hãy thử lưu (thực hiện nghiêm ngặt) phép tính đầu tiên. Để làm điều này, bằng cách sử dụng khái niệm giới hạn, chúng tôi đưa ra ý nghĩa chính xác cho “biểu thức vô hạn” (1). Hãy xem xét trình tự

$$\begin{cases} x_1 = \sqrt{2}, \\ x_n = \sqrt{2 + x_{n-1}}. \end{cases}$$

Theo biểu thức (1) việc hiểu giới hạn của dãy này là điều đương nhiên nếu nó tồn tại. Đây là lúc định lý Weierstrass phát huy tác dụng. Thật dễ dàng để kiểm tra điều đó với mọi $n$, thứ nhất, $x_n < 2$ (bằng quy nạp) và thứ hai, $x_n > x_{n-1}$ (xem Bài tập 4). Điều này có nghĩa là theo định lý Weierstrass thì dãy $(x_n)$ có giới hạn. Như vậy, ký hiệu $x$ cho biểu thức (1) là đúng. Từ đẳng thức $x_n = \sqrt{2 + x_{n-1}}$, chuyển đến giới hạn, ta được (2). Lý do ví dụ 1 được lưu *).

*) Về cách hiểu “biểu thức vô hạn”, xem thêm «Kvant», 1977, số 10, tr. 60.
