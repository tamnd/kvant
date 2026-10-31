---
id: 1985-8-resheniya-zadach-m916-m920-f927-f932-2409dd0b
issue: kvant_1985_8
year: 1985
number: "8"
title: Lời giải bài toán M916—M920; F927—F932
rubric: zadachnik-kvanta
rubric_sub: Задачник «Кванта»
page_first: 45
page_last: 51
page_labels: 43, 44, 46, 47, 48, 49
tag: YUI4
lang: vi
source: kvant_digital
extraction: vision
content_sha256: 8996ec96f11cc050746769aa5fca4c27aa8c6b4f43eccda49fcd5671e9b889e4
prompt_sha256: draft-1
translated_from: content/ru/1985/08/articles/16_resheniya-zadach-m916-m920-f927-f932-2409dd0b.md
source_content_sha256: ceaa6348137e5e7516c2e4b79502320f81b64c5bc330c437bbccbfc51a4c391a
translation_model: draft
translation_run: vi-draft-2026-10-31
translation_quality: draft
---

⟦folio 43⟧

Lời giải bài toán
M916 — M920; F927 — F932

M916. Từ giữa mỗi cạnh của một tam giác nhọn, các đường vuông góc được vẽ sang hai cạnh còn lại. Chứng minh rằng diện tích giới hạn hoặc hình lục giác bằng một nửa diện tích hình tam giác.

Chúng ta hãy biểu thị các đỉnh của tam giác này bằng $A, B, C$, trung điểm của các cạnh của nó bằng $A_1, B_1, C_1$ và ba đỉnh còn lại của hình lục giác được xem xét trong bài tập là $A_2, B_2, C_2$ (xem hình). Lưu ý rằng các đoạn nối tâm $O$ của đường tròn ngoại tiếp tam giác $ABC$ với trung điểm các cạnh của nó chia hình lục giác của chúng ta thành ba hình bình hành $OA_1C_2B_1, OB_1A_2C_1$ và $OC_1B_2A_1$ (các đoạn $OA_1$ và $B_1C_2$ song song với nhau, vì cả hai đều được phân bố lại sang một bên $BC$; tương tự $OB_1 \parallel A_1C_2$, v.v.). Theo đó, các tam giác $A_1B_1C_2, B_1C_1A_2$ và $C_1A_1B_2$ lần lượt bằng các tam giác $A_1B_1O, B_1C_1O$ và $C_1A_1O$, tức là diện tích hình lục giác gấp đôi diện tích tam giác $A_1B_1C_1$, hiển nhiên bằng 1/4 diện tích tam giác ban đầu.

Một cách chứng minh khác dựa trên việc ba đường cao của tam giác cắt nhau tại một điểm: $A_2, B_2$ và $C_2$ là giao điểm của các đường cao của các tam giác bằng nhau $AB_1C_1, C_1A_1B_1$ và $B_1CA_1$, do đó $\triangle A_2B_1C_1 = \triangle C_2CA_1$, $\triangle B_2A_1C_1 = \triangle C_2CB_1$, do đó tam giác của chúng ta có kích thước bằng hình bình hành $C_1A_1CB_1$.

Lưu ý rằng trong trường hợp một tam giác tù, cách xây dựng tương tự sẽ dẫn đến một đường gãy lục giác tự giao nhau, mà phát biểu này sẽ vẫn đúng khi xét đến cái gọi là “diện tích định hướng” (xem bài viết của A.L. Toom “Một đa giác có bao nhiêu diện tích?” trong «Kvant» Số 12 năm 1984).

A. A. Azamov

M917. a) Chuỗi vé xấu liên tiếp tối đa có độ dài bao nhiêu? b) Có bao nhiêu chuỗi có độ dài lớn nhất như vậy? (Số vé được coi là nằm trong khoảng từ 000000 đến 999999; một vé được gọi là may mắn nếu tổng ba chữ số đầu bằng tổng ba chữ số cuối.) a) Đáp số: 1000. Số vé bất kỳ nằm giữa hai số may mắn $1000N + N$ và $1000(N + 1) + (N + 1)$ (N và N + 1 là số có ba chữ số) có ba chữ số đầu tiên là số tương tự, xét theo thứ tự, bắt đầu từ số cuối cùng (đối với số bằng 1000A + B, trong đó A và B là số có ba chữ số, cần lấy N = A nếu A < B, và N = A - 1 nếu A ≥ B). Vì chênh lệch giữa các số may mắn này là 1001 nên độ dài của dãy vé không may mắn không thể lớn hơn 1000. Đồng thời, hai dãy số có độ dài 1000 - từ 000001 đến 001000 và từ 998999 đến 999998, hiển nhiên bao gồm các số không may mắn.

b) Đáp số: hai dãy; chúng được cho trong lời giải bài toán a).

Hãy để chúng tôi chứng minh điều đó giữa hai số may mắn bất kỳ $n = \overline{abcabc}^*$ và $n' = n + 1001 =$

*)Thanh có nghĩa là ký hiệu thập phân: $\overline{a_1a_2...a_n} = a_1 \cdot 10^{n-1} + a_2 \cdot 10^{n-2} + ... + a_n$.

⟦folio 44⟧

= \frac{a'b'c'a'b'c'}{(a'b'c'=abc+1)} với \frac{abc}{≠000} và \frac{abc}{≠998} có ít nhất một con số may mắn nữa. Rõ ràng từ đây, không có “bộ truyện không may” nào dài 1000, ngoại trừ những bộ đã nêu ở trên.

Nếu $a \neq 9$, $c \neq 0$ thì số đó là $\frac{abc}{(a+1)b(c-1)}$; nếu $a=9$ thì $a'=9$ và số được yêu cầu là $\frac{a'b'c'8b_1c_1}{b_1c_1}$, trong đó số $b_1c_1$ có được bằng cách tăng một trong các chữ số của số $\frac{b'c'}{(b'c'≠99)}$ lên 1; nếu $c=0$ thì $c'=1$ và số được yêu cầu là $\frac{a'b'c'a_2b_2}{a_2b_2}$, trong đó $a_2b_2$ thu được từ $\frac{a'b'}{a'b'}$ bằng cách giảm một trong các chữ số xuống 1 $(\frac{a'b'}{≠00})$.

S. Yu. Orevkov

M918.* Bán kính hình tròn nội tiếp một tam giác là 1 và độ dài các cạnh của nó là số nguyên. Chứng minh rằng các số đó là 3, 4 và 5.

Giả sử trong một tam giác đã cho $ABC$ độ dài các cạnh $AB, BC$ và $CA$ bằng $c, a$ và $b$, khi đó, như dễ thấy, các đoạn của các cạnh từ đỉnh $A, B, C$ đến các điểm tiếp tuyến của đường tròn nội tiếp nhìn từ cạnh đều bằng nhau

$$x = \frac{b+c-a}{2}, y = \frac{c+a-b}{2}, z = \frac{a+b-c}{2}$$

(xem hình để biết các ký hiệu). Trong trường hợp này, nửa chu vi $p$ của tam giác bằng $x+y+z$. So sánh các biểu thức tính diện tích $S$ của tam giác bằng công thức Heron -

$$S = \sqrt{p(p-a)(p-b)(p-c)},$$

và qua nửa chu vi và bán kính $r=1$ của đường tròn nội tiếp -

$$S = pr,$$

chúng tôi hiểu được điều đó $p=(p-a)(p-b)(p-c)$ hoặc

$$x+y+z=xyz.$$

Từ các đẳng thức (1), suy ra các số $x, y$ và $z$ đều là số nguyên hoặc bán số nguyên (nghĩa là có dạng $n+1/2$, trong đó $n$ là số nguyên). Trong trường hợp thứ hai, các số $2x, 2y$ và $2z$ phải là số lẻ, điều này không thể xảy ra do đẳng thức (2) $(2x \cdot 2y \cdot 2z = 4(2x+2y+2z)=4(a+b+c)$ - số lẻ bằng số chẵn) và do đó chúng ta phải giải phương trình (2) dưới dạng số nguyên.

Giả sử định nghĩa $x \leqslant y \leqslant z$, thì $xyz \leqslant 3z$, tức là $xy \leqslant 3$. Đi qua các cặp số tự nhiên $(x, y)$ thỏa mãn bất đẳng thức này (và điều kiện $x \leqslant y$), chúng ta thu được $x=y=1$ và sau đó là $2+z=z$, điều này là không thể; hoặc $x=1, y=2$, rồi $3+z=2z$, tức là $z=3$; hoặc $x=1, y=3$ và $z=2<y$, điều này mâu thuẫn với giả định của chúng tôi. Vì vậy, $x=1, y=2, z=3$, tức là $a=y+z=5, b=z+x=4, c=x+y=3$.

V. V. Praslov

M919. a) Chứng minh đẳng thức

$$\int_0^{\frac{1}{4}} \frac{1}{\sqrt{gx}} dx + \int_0^{1} \frac{1}{\sqrt{arctg x}} dx = \frac{\pi}{4}.$$

⟦folio 46⟧

$$z = nx^2y^2 - \frac{x^3 + y^3}{z^2} \geq nx^2y^2 - (x + y).$$

Đồng thời, hiển nhiên $x^3 + y^3$ chia hết cho $z^2$, nên
$$x^3 + y^3 \geq z^2 \geq (nx^2y^2 - (x + y))^2,$$
kể từ đây,
$$n^2x^4y^4 < 2nx^2y^2(x + y) + x^3 + y^3.$$

Chia cả hai vế cho $nx^3y^3$, ta được ước tính cần thiết
$$nxy < 2\left(\frac{1}{x} + \frac{1}{y}\right) + \frac{1}{nx^3} + \frac{1}{ny^3}.$$

Từ đó suy ra ngay $x = 1$, vì với $x \geq 2$ (và $y \geq x$) phần nằm của bất đẳng thức (*) không nhỏ hơn 4 và vế phải nhỏ hơn 3. Hãy thay giá trị $x = 1$ vào (*):

$$ny < 2 + \frac{2}{y} + \frac{1}{n} + \frac{1}{ny^3}.$$

Bất đẳng thức này chỉ có thể đúng với $y \leq 3$ (với $y \geq 4$ vế phải của nó nhỏ hơn 4). Hãy nhớ rằng số $x^3 + y^3 = 1 + y^3$ phải chia hết cho $z^2$ và $z \geq y$; theo đó, $z = 1$ cho $y = 1(1 + y^3 = 2)$, $z = 3$ cho $y = 2(1 + y^3 = 9)$ và đối với $y = 3(1 + y^3 = 28)$ không có giá trị phù hợp nào là $z$. Vẫn còn phải thay các bộ ba số (1, 1, 1) và (1, 2, 3) vào phương trình ban đầu và tìm thấy rằng trong trường hợp đầu tiên $n = 3$ và trong trường hợp thứ hai $n = 1$.

Vì vậy, đáp số: đối với $n = 3$ $x = y = z = 1$, đối với $n = 1$ phương trình được thỏa mãn bởi bộ ba (1, 2, 3) và mọi thứ tạo ra từ nó bằng các hoán vị.

Lời giải chúng tôi có một phương trình hỗ trợ cấu trúc của phương trình $x^2 + y^2 + z^2 = nxyz$, đã được thảo luận chi tiết trong bài viết của M. G. Kerin “Phương trình Diophantine của A. A. Markov” trong «Kvant» số 4 năm nay. Điều thú vị là phương trình này cũng chỉ có thể giải được với $n = 1$ và $n = 3$, nhưng số lời giải của nó là vô hạn trong các trường hợp tổng quát. Một phương trình tương tự khác cho số $(x + y + z = xyz)$ được tìm thấy trong lời giải bài toán M918.

R. A. Mazov, V. N. Dubrovsky

F927. Một hạt tích điện truyền qua một bộ đếm nhấp nháy, có hình dạng song song và các phân tử nhấp nháy nằm dọc theo quỹ đạo của nó sẽ phát ra ánh sáng. Ánh sáng tại mỗi điểm được phát ra đồng đều, tức là đồng đều theo mọi hướng. Phần năng lượng ánh sáng nào sẽ thoát ra từ chất nhấp nháy vào không khí nếu chiết suất của chất nhấp nháy là $n = 1,6$? Hãy chú ý đến vị trí của ánh sáng trong máy nhấp nháy.

Lưu ý uresol ở đỉnh hình nón bằng $\Omega = 2\pi(1 - \cos \theta)$, trong đó $\theta$ là góc giữa trục của hình nón và trục tạo thành của nó.

Xét một chùm ánh sáng phát ra từ một điểm tùy ý bên trong máy nhấp nháy.

Gọi $\alpha$ là góc mà tia này tạo với pháp tuyến $\vec{N}$ với một trong các mặt của mặt phẳng song song, được xác định trên mặt đất bởi mặt $A$ của nó, và $\alpha_0 = \arcsin(1/n) \approx 39^\circ$ là góc giới hạn của phản xạ toàn phần ánh sáng tại ranh giới tia chớp-không khí.

Hãy để chúng tôi chứng minh rằng với mọi giá trị của chiết suất $n > \sqrt{2}$ thì các phát biểu sau đều đúng:

1. Chùm tia phát ra ở góc $\alpha < \alpha_0$ chắc chắn sẽ thoát ra khỏi thiết bị nhấp nháy và hơn nữa, chỉ xuyên qua mặt $A$.
2. Không có tia nào phát ra ở góc $\alpha > \alpha_0$ có thể đi qua mặt $A$.

Trước hết, hãy lưu ý rằng khi phản ánh

⟦folio 47⟧

ánh sáng từ các mặt song song với $\vec{N}$, góc $\alpha$ không thay đổi (điều này tuân theo định luật phản xạ ánh sáng). Hơn nữa, vì đối với $n > \sqrt{2}$ $\alpha_0 < 45^\circ$, góc tới tối thiểu có thể có của chùm tia (thỏa mãn điều kiện $\alpha < \alpha_0!$) trên các mặt song song với $\vec{N}$ hóa ra lớn hơn $\alpha_0$ và do đó, ánh sáng không thể thoát ra khỏi đèn nhấp nháy qua các mặt này. Như vậy Mệnh đề 1 đã được chứng minh.

Hãy chuyển sang chứng minh khẳng định thứ hai. Hãy xem xét tất cả các giá trị có thể có của các góc $\alpha$ từ 0 đến $180^\circ$. Ở vùng $\alpha_0 < \alpha < 90^\circ$, do nhận xét sau đây, rõ ràng là ở bất kỳ góc nào trong số này, ánh sáng không thể thoát qua mặt $A$. Ở các góc ban đầu $90^\circ \leq \alpha \leq 180^\circ$, chỉ những tia đã phản xạ hoàn toàn trên mặt $B$, song song với $A$, mới có thể chiếu tới mặt $A$ (nhưng không nhất thiết phải đến đó). Nhưng những tia như vậy không thể đi qua mặt $A$, vì góc tới của chúng trên đó hoàn toàn giống với trên mặt $B$ mà chúng bị phản xạ. Do đó Mệnh đề 2 cũng được chứng minh.

Vì vậy, tất cả các tia đi ra khỏi quầy đều tập trung vào sáu hình nón - trục của mỗi hình nón vuông góc với một trong các mặt của hình song song. Góc khối được cắt bởi tất cả các hình nón từ góc khối lớn nhất bằng 4π là một phân số

$$\eta = \frac{6 \cdot 2\pi(1 - \cos \alpha_0)}{4\pi} = 3\left(1 - \sqrt{1 - \frac{1}{n^2}}\right).$$

Điều này có nghĩa là khoảng 2/3 năng lượng ánh sáng thu được sẽ đến từ bộ nhấp nháy $n=1,6$.

S. A. Khorozov

F928. Hai nửa chindra chính giống hệt nhau, tổng khối lượng là $m$, được treo trên một sợi chỉ cô dâu không thể giãn ra như trong hình. Lực căng của sợi chỉ và lực ép của nửa chindra này lên nửa kia là bao nhiêu?

Mỗi nửa chindra chịu tác dụng của trọng lượng, lực căng của sợi chỉ và lực ép từ nửa chindra thứ hai. Hãy viết điều kiện bán chindra:

trong các hình chiếu trên trục ngang -

$$T + T \cos \alpha = N,$$

(1)

trong các hình chiếu trên trục tung -

$$T \sin \alpha = \frac{mg}{2}.$$

(2)

Giải các phương trình (1) và (2) cùng nhau, ta tìm được lực $T$ của lực căng của sợi dây và lực $N$ của áp suất của nửa chindra này lên nửa kia:

$$T = \frac{mg}{2 \sin \alpha},$$

$$N = \frac{mg(1 + \cos \alpha)}{2 \sin \alpha}.$$

L. G. Markovich

⟦folio 48⟧

F929. Được biết, bằng cách làm nguội bình bằng nước và đồng thời bơm khí ra khỏi bình, người ta có thể làm cho nước sôi. Chất lỏng có thể sôi khi làm nguội một bình kín chứa chất lỏng và khí không?

Điều kiện để một chất lỏng sôi ở nhiệt độ nhất định là áp suất phía trên nó bằng áp suất của hơi bão hòa ở nhiệt độ đó.

Nếu một bình kín chứa chất lỏng và khí được làm lạnh đồng đều thì ở bất kỳ nhiệt độ nào, áp suất trên chất lỏng sẽ lớn hơn áp suất hơi bão hòa của nó bằng giá trị áp suất riêng phần của khí trong bình. Trong trường hợp này, chất lỏng sẽ không sôi khi nguội.

Nếu bình được làm nguội không đều, khiến phần trên của bình nguội nhanh hơn thì chất lỏng có thể sôi. Điều này sẽ xảy ra khi tổng áp suất của khí và hơi bão hòa phía trên chất lỏng, nơi có nhiệt độ thấp hơn, trở thành áp suất của hơi bão hòa ở nhiệt độ cao hơn mà chất lỏng hiện có.

L. A. Ashkinazi

F930. Mật độ điện tích bề mặt trên các bản hình chữ nhật của tụ điện phẳng là +σ và -σ. Khoảng cách giữa các tấm nhỏ hơn nhiều so với kích thước của các tấm. Xác định hướng của tiết diện điện tại điểm A (xem hình).

Từ các thông điệp đối xứng, dễ dàng chỉ ra rằng vectơ chỉ phương $\vec{E}_A$ của trường tĩnh điện tại điểm A có hướng vuông góc với các bản tụ điện.

Thật vậy, hãy nhẩm chia mỗi đĩa thành những phần nhỏ giống hệt nhau. Chúng ta hãy chọn các cặp phần đối xứng (nằm đối diện nhau) trên hai tấm. Ví dụ: $\vec{E} = \vec{E}_1 + \vec{E}_1'$ của trường được tạo bởi điện tích của các phần này tại điểm A được định hướng theo phương thẳng đứng (xem hình). Vậy tổng hướng $\vec{E}_A$ của điện trường tại điểm A cũng thẳng đứng (tức là vuông góc với các bản tụ).

Ngoài ra, mỗi bản tụ điện của chúng ta có thêm ba bản giống nhau (có cùng mật độ điện tích) sao cho điểm A nằm bên trong khung tụ điện với các bản “gấp bốn”. Ví dụ: $\vec{E}_0$ của trường của tụ điện như vậy tại điểm A sẽ bằng $\vec{E}_0 = 4\vec{E}_A$, trong đó $E_0 = \sigma/\varepsilon_0$. Kể từ đây,

$$E_A = \frac{E_0}{4} = \frac{\sigma}{4\varepsilon_0}.$$

Ồ, vâng. Savchenko

F931. Một nguồn điểm cách thấu kính một khoảng 2F. Một màn ảnh cách thấu kính một khoảng 3F (xem hình). Phía sau thấu kính có một tấm tròn bán kính R truyền

⟦folio 49⟧

Đến một điểm trên màn hình nằm ở khoảng cách $r$ từ trục quang $(r \leqslant R_\pi)$, tia sáng đi ra khỏi thấu kính ở khoảng cách tới $2r$ từ trục. Độ sáng tại điểm này của màn hình (không sử dụng tấm) bằng

$$E_0(r) = \frac{IF}{(F^2 + r^2)\sqrt{F^2 + r^2}} = \frac{IF}{(F^2 + r^2)^{3/2}}$$

(I là cường độ sáng của nguồn; bỏ qua sự mất mát ánh sáng trong thấu kính). Khi sử dụng tấm bản, độ sáng ở thời điểm này sẽ là

$$E(r) = E_0(r) \cdot T(2r) = \frac{IF}{(F^2 + r^2)^{3/2}} T(2r),$$

trong đó $T(2r)$ là “thông lượng” của tấm tại các điểm của nó, nằm ở khoảng cách $2r$ tính từ trục quang. Rõ ràng là độ chiếu sáng tại bất kỳ điểm nào của điểm (bất kể $r$) sẽ giống nhau nếu $T(2r) = k(F^2 + r^2)^{3/2}$, nghĩa là

$$T(r) = k \left(F^2 + \frac{r^2}{4}\right)^{3/2},$$

trong đó $k$ là hệ số tỷ lệ nhất định.

Vì $T(r) \leqslant 1$, khả năng tối đa tại tất cả các điểm của điểm khi sử dụng tấm không thể lớn hơn độ chiếu sáng tối thiểu của điểm thu được khi không có tấm. Độ chiếu sáng tối thiểu không có tấm là tại các điểm nằm trên ranh giới điểm, nghĩa là ở khoảng cách $R_\pi$ tính từ trục quang. Những điểm này bị các tia phát ra từ tấm ở khoảng cách $R_\pi$ chạm vào trục. Do đó, giá trị lớn nhất của $k$ được xác định bởi điều kiện $T(R_\pi) = 1$, tức là

$$k = \frac{1}{(F^2 + R_\pi^2/4)^{3/2}}.$$

Vì vậy, một điểm trên màn hình có khả năng chiếu sáng tối đa đồng đều nếu “thông lượng” của tấm thay đổi dọc theo bán kính của nó theo định luật

$$T(r) = \frac{1}{(F^2 + R_\pi^2/4)^{3/2}} \left(F^2 + r^2/4\right)^{3/2} = \left(\frac{4F^2 + r^2}{4F^2 + R_\pi^2}\right)^{3/2}.$$

A. A. LanUDEC
