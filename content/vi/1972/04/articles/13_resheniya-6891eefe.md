---
id: 1972-4-resheniya-6891eefe
issue: kvant_1972_4
year: 1972
number: "4"
title: Lời giải bài toán M96—M100; F108—F115
rubric: zadachnik-kvanta
rubric_sub: Задачник «Кванта»
page_first: 44
page_last: 54
page_labels: 42, 43, 44, 45, 48, 49, 51, 52
tag: U9OT
lang: vi
source: kvant_digital
extraction: vision
content_sha256: 96471a2c2362896e2a242e1573ff76857dbfa21febd391d4e4b71635fab86670
prompt_sha256: draft-1
translated_from: content/ru/1972/04/articles/13_resheniya-6891eefe.md
source_content_sha256: 578c4d5b93a0f2487395e9dfb036395cbc2881800982bdfff7d2f57a390ba796
translation_model: draft
translation_run: vi-draft-2026-10-31
translation_quality: draft
---

⟦folio 42⟧

GIẢI PHÁP

Trong số này, chúng tôi xuất bản lời giải bài toán M96—M100

M96

Người ta đã biết về năm số dương nếu tổng của ba số bất kỳ trừ đi tổng của hai số còn lại thì hiệu sẽ là số dương. Chứng minh rằng tích của cả 10 hiệu như vậy không vượt quá bình phương tích của 5 số đã cho.

Đặt $a_1, a_2, a_3, a_4, a_5$ là các số đã cho Sau đó $(a_1+a_2+a_3-a_4)(a_1+a_3+a_4-a_2-a_5)=a_1^2-(a_2+a_5-a_3-a_4)^2\leq a_1^2$.

Tương tự, người ta chứng minh rằng $(a_2+a_3+a_1-a_4-a_5)\times(a_2+a_4+a_5-a_3-a_1)\leq a_2^3$,
$(a_3+a_4+a_2-a_5-a_1)\times(a_3+a_5+a_1-a_4-a_2)\leq a_3^2$,
$(a_4+a_5+a_3-a_1-a_2)\times(a_4+a_1+a_2-a_5-a_3)\leq a_4^2$,
$(a_5+a_1+a_4-a_2-a_3)\times(a_5+a_2+a_3-a_1-a_4)\leq a_5^2$.

Việc còn lại là nhân các bất đẳng thức này và bài toán được giải.

Chứng minh một phát biểu tổng quát hơn: nếu cho $2n+1$ số dương, hiệu giữa tổng của bất kỳ số $n+1$ nào và tổng của $n$ số dương còn lại, thì tích $B$ của tất cả $C_{2n+1}^n$ hiệu đó và tích $A$ của tất cả $2n+1$ các số đã cho có liên hệ với nhau bởi bất đẳng thức

$$B^n\leq A^{C_{2n+1}^n}$$

M97

Trong hình thang $ABCD$ có đáy $AB=a$ và $CD=b$ một đoạn $A_1B_1$ được vẽ nối trung điểm của các đường chéo. Trong hình thang thu được $A_1B_1CD$, đoạn $A_2B_2$ một lần nữa được vẽ, nối các điểm giữa của các đường chéo, v.v. (Hình 1). Có thể nào một số xuất hiện hai lần trong chuỗi độ dài đoạn $AB, A_1B_1, A_2B_2, \dots$ không? Trình tự này sẽ đơn điệu (tăng hay giảm?) Nó có xu hướng đạt đến một giới hạn nào đó không?

Đặt $A_1$ và $B_1$ là trung điểm của các đường chéo $AC$ và $BD$ của hình thang, $E$ và $F$ là trung điểm của cạnh-

⟦folio 43⟧

các mặt ngoài AD và BC (Hình 2). Vì $A_1F$ là đường trung bình của tam giác ACB và $B_1F$ là đường trung bình của tam giác DCB nên các điểm $A_1$ và $B_1$ nằm trên đoạn EF và

$$a_1 = A_1B_1 = |A_1F - B_1F| = \left| \frac{a-b}{2} \right|.$$

(Công thức này đúng cho dù số $a$ và $b$ nào lớn hơn.) Bằng cách tương tự, người ta chứng minh rằng

$$a_{n+1} = \left| \frac{a_n - b}{2} \right|,$$

(1)

trong đó $a_n = A_nB_n$ ($n=1, 2, 3, \dots$) là chuỗi mà chúng tôi quan tâm. Do đó, bài toán được rút gọn thành số đại số bài toán của dãy được xác định bởi sự tương ứng của (1) với số hạng ban đầu $a_0 = a > 0$.

Nếu $a_n > b$ thì $a_{n+1} = \frac{a_n - b}{2} < a_n - b$.

Do đó, nếu $a > b$ thì mỗi phần tử của dãy sẽ nhỏ hơn phần trước ít nhất $b$ cho đến khi gặp một phần tử $a_m$ sao cho $a_m \leq b$ (nếu $a \leq b$ thì ta đặt $m=0$, $a_m = a_0 = a$; nhiều độc giả chỉ xét trường hợp này; nó chỉ được xem xét trong cuốn “Toán học” bài toán" *).

Vì vậy, bây giờ chúng ta sẽ chỉ xem xét $n \geq m$.

Nếu $a_n \leq b$ thì $a_{n+1} = \frac{b - a_n}{2} \leq \frac{b}{2} < b$.

Do đó, tất cả các số hạng của dãy theo sau $a_m$ sẽ nhỏ hơn $b$ và do đó với tất cả $n \geq m$

$$a_{n+1} = \frac{b - a_n}{2}.$$

(2)

Cơm. 2.

*) E. B. Dynkin, S. A. Molchanov, A. L. Rosenthal, A. K. Tolygu, “Toán học bài toán”, ed. Lần thứ 3, “Khoa học”, 1971, bài toán 147.

Cơm. 3. Các số hạng của dãy $a_n$, được xác định bởi điều kiện $a_0 = a$, $a_{n+1} = \left| \frac{a_n - b}{2} \right|$ là các hoành độ của các đỉnh của đường đứt nét được bao quanh bởi màu xanh lá cây. Các liên kết của đường đứt nét này lần lượt song song với các trục $Ox$, $Oy$, các đỉnh của nó lần lượt nằm trên đường thẳng có phương trình $y = x$ và trên đồ thị của hàm số $y = \left| \frac{x - b}{2} \right|$.

Cơm. 4.

Phương trình $x = \frac{b - x}{2}$ có một lời giải $x = \frac{b}{3}$. Do đó, nếu có giới hạn trên chuỗi $\{a_n\}$ thì nó bằng $\frac{b}{3}$.

Hãy để $a_m \neq \frac{b}{3}$. Hãy đặt $a_n = \frac{b}{3} + \delta_n$. Khi đó từ (2) suy ra $\frac{b}{3} + \delta_{n+1} = \frac{b}{3} - \frac{\delta_n}{2}$, tức là

$$\delta_{n+1} = -\frac{\delta_n}{2}$$

(3)

— khi di chuyển từ $n$ đến $n+1$, hiệu $a_n - \frac{b}{3} = \delta_n$ đổi dấu và giảm một nửa về giá trị abscissa. Bây giờ mọi thứ đã rõ ràng: trong dãy $a_n$ không có số nào có thể xuất hiện hai lần, số hạng cuối cùng của mỗi số là $\frac{b}{3}$ so với số trước. Trình tự này không đơn điệu mà có xu hướng đạt đến giới hạn $\frac{b}{3}$ (Hình 3, 4).

⟦folio 44⟧

Cơm. 5.

Thật không may, một số độc giả viết: “Vì chuỗi không đơn điệu nên nó không có xu hướng đến giới hạn”.
Tất nhiên, lý do này là không chính xác. Chúng ta hãy chứng minh, bằng cách sử dụng định nghĩa giới hạn, rằng

$$\lim_{n \to \infty} a_n = \frac{b}{3}.$$

Cho $\varepsilon > 0$. Khi đó, nếu $n > N$, trong đó $N = N_{(\varepsilon)}$ là số nguyên nhỏ nhất thỏa mãn $2^N \varepsilon > 2^m |\delta_m|$, thì $\left| a_n - \frac{b}{3} \right| = |\delta_n| = \frac{|\delta_m|}{2^n - m} < \frac{|\delta_m|}{2^N - m} < \varepsilon$.

Vậy (4) được chứng minh.

Tất nhiên, giới hạn bằng $\frac{b}{3}$ ngay cả trong trường hợp $a_m = \frac{b}{3}$ - trong trường hợp này, tất cả các số hạng tiếp theo cũng bằng $\frac{b}{3}$. Chúng ta hãy tìm hiểu xem trường hợp này xảy ra với giá trị nào của $a$. Nếu $m = 0$ thì $a = \frac{b}{3}$. Nếu $m = 1$ và $a_1 = \frac{a - b}{2} = \frac{b}{3}$ thì $a = \frac{5b}{3}$.

Cơm. 6.

Nói chung, nếu $a_m = \frac{b}{3}$ thì $a = a_0$ thu được từ $a_m = \frac{b}{3}$ sau khi áp dụng công thức $a_{n-1} = 2a_n + b$ $m$ lần. Do đó, để dễ kiểm tra, các giá trị $a$ mà $a_m = \frac{b}{3}$ tạo thành chuỗi $\frac{b}{3}, \frac{5b}{3}, \frac{13b}{3}, \ldots, \frac{(2^k - 3)b}{3}$,... Đối với những giá trị này (và chỉ những giá trị này) $a$, chuỗi hóa ra là đơn điệu (và từ một điểm nào đó không đổi).

Chúng ta chưa thấy riêng trường hợp nào khi $a_m = b$ (đồng thời $a_{m+1} = 0, a_{m+2} = \frac{b}{2}, \ldots$), - theo quan điểm đại số, không có gì áp dụng được, nhưng các hình thang $n = m$ và $n = m+1$ tương ứng suy biến thành hình bình hành và thành hình tam giác (các điểm $B_{m+1}$ và $C_{m+1}$ trùng nhau, Hình 5); bắt đầu với $n = m+2$, sẽ thu được áp suất hình thang và như mọi khi, $a_n$ có xu hướng đạt đến giới hạn $\frac{b}{3}$.

M98

Chứng minh rằng trong bảng

1 1 1 1 1 1 1 1 1 1 1 1 1 1 1 1 1 1 1 1 1 1 1 1 1 1 1 1 1 1 1 1 1 1 1 1 1 1 1 1 1 1 1 1 1 1 1 1 1 1 1

trong đó mỗi số bằng tổng của ba số ở trên, mỗi dòng (bắt đầu từ số thứ ba) có một số chẵn. Mỗi dòng (trừ hai dòng đầu tiên) có chứa một số chia hết cho ba không?

Đầu tiên chúng ta hãy xem xét vấn đề chia hết cho hai. Trong bảng của chúng ta, chúng ta sẽ viết 0 cùng nhau và thay vì các số lẻ - 1. Sau đó, bảng 0 và 1 sẽ cần được biên soạn theo cùng một quy tắc (mỗi số được lấy bằng tổng của ba số ở trên nó ở dòng trước), chỉ cần thực hiện phép cộng “modulo hai” - theo quy tắc $0+0=0, 0+1=1+0=1, 1+1=0$.

Cách đầu tiên dựa trên sự kết hợp như vậy: các số chẵn cuối cùng trong mỗi hàng chỉ phụ thuộc vào các số chẵn cuối cùng ở hàng trước là gì, và do đó không có gì đáng ngạc nhiên khi bộ tứ này lặp lại định kỳ (với khoảng thời gian là 4, xem Hình 6) *).

*) Một lời giải tương tự được đưa ra trong cuốn sách của D. O. Shklyarsky, N. N. Chentsov và I. M. Yaglom “Chọn bài toán và Định lý Toán học Sơ cấp”, ed. Lần thứ 4, “Nuka”, 1965, bài toán 10.

⟦folio 45⟧

Một lời giải khác, do một số độc giả đề xuất, là một bằng chứng mâu thuẫn. Giả sử rằng một số chuỗi bao gồm toàn bộ các chuỗi:

111 ... 111

Vậy thì dòng trước, dễ thấy, chỉ có thể như thế này:

100100 ... 001001,

và người đi trước cô ấy giống như thế này:

110000110000 ... 000011000011.

Nhưng điều này là không thể, vì mỗi hàng trong bảng của chúng ta có một số lẻ.

Về khả năng chia hết cho 3, như bạn có thể dễ dàng nhận thấy, đã có ở hàng thứ tư tiếp theo của bảng (rất thuận tiện khi gán số 0 cho hàng trên cùng của một đơn vị)

1 4 10 16 19 16 10 4 1

Không một số nào chia hết cho 3 (và tất cả đều dư 1 khi chia cho ba). Sau khi hiểu cấu trúc của bảng “modulo 3” của chúng ta (trong Hình 7, các số có số dư 0, 1 và 2 khi chia cho 3 được thay thế bằng các vòng tròn màu vàng, đen và đỏ tương ứng), bạn có thể nhận thấy rằng cùng một thuộc tính sẽ có các hàng có số 1, 1+3=4, 1+3+3^2=13, 1+3+3^2+3^3=40, v.v.

Người đọc báo cáo trong thư của họ về các tính chất khác của các số trong bảng này. Có thể suy ra nhiều tính chất khác nhau; sử dụng thực tế là hàng thứ n của bảng chứa các hệ số của đa thức

$$(1+x+x^2)^n = \sum_{k=0}^{2n} B_n^k x^k$$

(các thao tác gần giống như trong bài “Số học hệ số biomp”, “Quant” số 6, 1970). Ví dụ, ngay lập tức rõ ràng rằng $\sum_{k=0}^{2n} B_n^k = 3^n$, $\sum_{k=0}^{2n} (-1)^k B_n^k = 1$, và không khó để chứng minh điều đó $\sum_{k=0}^{n} (B_n^k) = B_{2n}^n$ (xem bài toán 61 trong cuốn sách của A. M. và I. M. Yaglomov “Không sơ cấp bài toán trong một bài thuyết trình sơ cấp”, Gostekhidat, 1954). Kiểm tra xem

**Cơm. 7.**

Cơm. 8.

nếu $p$ là số nguyên tố, $s < p$ và $r < p$, thì

$$B_{lp+s}^l B_{m+r}^m \equiv B_{l}^l B_{m}^s + B_{l-1}^l B_{m}^s + p$$ (mod $p$)

(nếu $k > 2n$ thì $B_{n}^k$ được coi là bằng 0).

Lời giải bài toán **M96 - M98** do đa thức người đọc gửi. Ít nhất hai trong số bài toán này đã được giải quyết bởi A. Grizoryan (Baku), S. Konyazin (Saratov), A. Merkuryev (Leningrad), M. Rozov (Minsk), M. Preezer (Tomsk), A. Slinkin (Moscow), A. Chernyak (Minsk), E. Turkevich (Chernivtsi), S. Komanov (làng Tsalka của SSR Georgia), G. Timofeev (Saratov), Y. Kisin (Stranay Russa), V. Nadezhko (Leningrad), A. Blyukhin (Kiselevsk, vùng Kemerovo), E. Gundur (Voroshilgovryad), A. Makarytsev (Lvov), I. Shparlinsky (Moscow).

**M99**

Trong tam giác ABC, cạnh AC dài nhất. Chứng minh rằng với mọi điểm M trên mặt phẳng AM+CM không nhỏ hơn BM. Trong trường hợp nào có thể bình đẳng?

Đầu tiên chúng ta hãy chứng minh bổ đề này.

Bổ đề. Cho bốn điểm A, B, C, M bất kỳ trên mặt phẳng

$$AC \cdot BM \leq AB \cdot CM + BC \cdot AM$$ (1)

Đẳng thức xảy ra khi và chỉ khi ABCM là tứ giác nội tiếp lồi (hoặc khi một trong các số hạng ở vế phải bằng 0 do có một số điểm trùng nhau).

Chứng minh bổ đề. Chúng ta hãy chọn điểm P sao cho $\Rightarrow BAP = \Rightarrow CAM$ và $\Rightarrow MAP = \Rightarrow CAB$ và PA = $\frac{AB \cdot AM}{AC}$ (Hình 8). Sau đó $\triangle BAP \sim \triangle CAM$ (cái đầu tiên nhận được -

⟦folio 48⟧

mà ống hút sẽ quay sẽ không trùng với phần giữa của nó.

Lực ma sát của mỗi mẩu rơm tỉ lệ thuận với trọng lượng của những mẩu rơm đó

$$F_1 = m \frac{l - x}{l} gk, \quad F_2 = m \frac{x}{l} gk.$$

Bây giờ chúng ta có thể viết điều kiện để mô men của lực bằng 0 đối với điểm 0:

$$F(l - x) - F_1 \left( \frac{l - x}{2} \right) - F_2 \frac{x}{2} = 0.$$ (1)

Thay các giá trị $F_1$, $F_2$ và $F \approx mgk$ (vì theo điều kiện $F$ chỉ nhỏ hơn $mgk$ một chút), ta thấy

$$x = \frac{l}{\sqrt{2}}.$$

Khoảng cách này nhỏ hơn một nửa chiều dài của ống hút. Do đó, ống hút không quay quanh giữa mà xoay quanh một điểm gần với một đầu. Xoay ống hút về $180^\circ$, lũ kiến ​​sẽ nhìn thấy nó ở khoảng cách xa. Bây giờ toàn bộ thao tác có thể được lặp lại, chỉ với ống hút ở đầu kia. Và vân vân.

Chúng ta hãy kiểm tra công thức (1). Thay $F_1 = m \frac{l - x}{2} gk$ và $F_2 = m \frac{x}{l} gk$ vào đó và ký hiệu là $\alpha = \frac{F}{mgk}$, ta được

$$\alpha = \frac{2x^2 + l^2 - 2lx}{2l(l - x)}.$$

Những người biết cách tìm cực tiểu của một hàm và đánh đồng đạo hàm của nó với 0 có thể thấy rằng $\alpha$ nhỏ nhất tại $x = l \left( 1 - \frac{\sqrt{2}}{2} \right) \approx 0,3l$. Nó bằng 0,43. Như vậy, để xoắn ống hút, kiến ​​chỉ cần tác dụng một lực bằng 0,43 $mgk$ vào một đầu.

Đúng lời giải bổ sung: V. Belov (Vologda), I. Bramovskaya (Usolye-Sibirskoye, vùng Irkutsk), M. Weinhacher (Krivoy Rog); F. Galtsev (Tashkent); E. Golubev (Mamonov, vùng Kaliningrad), D. Grak (Smolevich, vùng Minsk), E. Gromak (Novokuznetsk); G. Zaitsev (Gagra); L. Knizherman (Moscow); S. Kuzmchi (Zhitomir); E. Latyshev (Baku), A. Levykin (Raigakhinsk, vùng Amur), S. Legushiin (Dnepropetrovsk), M. Preer (Tomsk), A. Redchenko (làng Novopetrovka, vùng Sumy), A. Renkov (làng Polomshnoye, vùng Kemerovo), L. Salina (Blagoveshchensk), V. Servakh (Frunze), N. Fedin (Omsk), M. Flerov (Moscow), G. Shepenko (David-Gorodok, vùng Brest), M. Yudson (Volgograd), S. Chekmarev (Moscow).

F109

Thí nghiệm cho thấy nhiệt độ $m=142$ e của nước đá ở trạng thái nhẹ, lơ lửng giữa phòng, tăng $\Delta t=4^\circ$ C trong nửa giờ. Khi có cùng một lượng băng thì phải mất 10 giờ mới kéo được nó. Dựa vào thí nghiệm này, nhiệt dung riêng của sự nóng chảy của nước đá là bao nhiêu? Nhiệt dung riêng của nước $c_B=1$ cal/g.

Hãy tìm lượng nhiệt $Q$ cung cấp cho bình trong nửa giờ. Vì lượng nhiệt này đủ để làm nóng nước nên

$$Q = c_B m \Delta t.$$

Trong 10 giờ, lượng nhiệt được cung cấp cho tàu tăng gấp 20 lần. Đó là lý do tại sao

$$\lambda m = 20 c_B m \Delta t.$$

Từ đây

$$\lambda = 20 c_B \Delta t = 80 \text{ кал/г}.$$

lời giải đúng của bài toán này là phần bổ sung cho khoảng 100 độc giả.

F110

Nếu vôn kế được mắc song song với điện trở trên $r_1$ (Hình 11), thì nó hiển thị $u_1=6$v, nếu song song với điện trở dưới $r_2$ thì $u_2=4$v, và nếu nó được nối với các điểm $A$ và $B$ thì nó hiển thị $u=12$v. Điện áp thực tế giảm trên các điện trở $r_1$ và $r_2$ là bao nhiêu?

Điện trở trong của nguồn nhỏ không đáng kể.

Khi nối vôn kế vào các điểm $A$ và $B$, số chỉ của nó bằng ed. Với. nguồn. Do đó, nếu nối một vôn kế với điện trở $r_1$ và điện trở trong của vôn kế là $r$ thì có dòng điện chạy qua mạch

$$I = \frac{u}{r_2 + \frac{r_1 r}{r_1 + r}}.$$ (1)

Điều này có nghĩa là

$$u_1 = \frac{u}{r_2 + \frac{r_1 r}{r_1 + r}}.$$ (1)

Cơm. 11.

⟦folio 49⟧

Hoàn toàn giống nhau

$$u_2 = \frac{u}{r_1 + \frac{r_2 r}{r_2 + r}} \frac{r_2 r}{r_2 + r}.$$

Chia phương trình cuối cùng (1) cho phương trình (2), chúng ta thu được

$$\frac{u_1}{u_2} = \frac{r_1}{r_2}.$$

Vì vậy, $$\frac{r_1}{r_2} = \frac{6}{4} = \frac{3}{2}.$$

Khi tắt vôn kế, hướng giảm trên các điện trở $r_1$ và $r_2$ bằng $u=12$ in. Vì đã biết tỷ số điện trở nên không khó để tìm ra hướng giảm theo hướng $u'_1$ và $u'_2$ trên các điện trở:

$$u'_1 + u'_2 = u, \quad \frac{u'_1}{u'_2} = \frac{r_1}{r_2}.$$

Từ đây

$$u'_1 = \frac{u r_1}{r_1 + r_2} = \frac{u}{1 + \frac{r_2}{r_1}} = 7,2b;$$

$$u'_2 = u - u'_1 = 4,8b.$$

lời giải chính xác được gửi bởi: P. Anenko (làng Totskoye, vùng Orenburg), E. Doltsov (Moscow), A. Kachilson (Novomoskovsk, vùng Tula), S. Kuzmchi (Zhitomir), E. Lamyshev (Baku), A. Levykin (Raigakhinsk, vùng Amur), A. Mamula (làng Dybintsy, vùng Kyiv), V. Peresedov (Pohvistnevo), M. Preezer (Tomsk), L. Rudtser (Kharkov), L. Salnitsa (Blagoveshchensk), A. Sboev (làng Medvedok, vùng Kirov), P. Sereev (Grozny), Sh. Slenoy (Chernivtsi), N. Tkachenko (Dnepropetrovsk), I. Turishchev (Kropotkin, vùng Krasnodar), N. Fedin (Omsk), G. Tsibenko (Slavyansk, vùng Donetsk), L. Tsiferblat (Lvov), V. Shabunin (Moscow), E. Shakhnovich (vùng Kalinin), R. Shzaanov (Lyubertsy, vùng Moscow), I. Yurtsenko (Kyiv).

F111

Có một sợi dây đồng nhất có chất nổ. Tốc độ cháy của dây là $v$, tốc độ truyền sóng nổ khi va chạm là $c$. Tìm hình dạng của đường mà bạn cần trải dây sao cho sóng từ tất cả các điểm của dây đồng thời truyền đến một điểm nhất định.

Có thể làm điều tương tự với bề mặt nổ và thu được sóng hình cầu giảm dần với mật độ năng lượng cao không?

Nếu tốc độ truyền sóng nổ lớn hơn tốc độ cháy của dây thì không thể trải dây sao cho sóng nổ từ mọi điểm của dây đều đồng thời chảy đến một điểm cho trước. Nếu $v=c$ thì sợi dây rất dài phải được kéo dài dọc theo một đường thẳng đi qua một điểm cho trước. Trong trường hợp $v>c$ đáp số thì không nhiều lắm.

Chúng ta hãy xem xét trường hợp này chi tiết hơn.

Lấy đường cong màu đỏ ở Hình 12 là đường mà sợi dây phải trải dọc theo sao cho sóng nổ đồng thời lao tới điểm $O$. Chúng ta hãy chọn hai điểm gần nhau trên đường $A$ và $B$ sao cho đường cong $AB$ có thể được coi là một đường thẳng (đối với điều này, đoạn $AB$ phải nhỏ hơn nhiều so với khoảng cách $r_0$ và $r_1$ từ điểm $O$ đến các điểm $A$ và $B$). Thời gian mà phần dây $AB$ được xây dựng sẽ được ký hiệu là $\tau$. Sau đó $AB=v\tau$. Độ nhỏ của $AB$ có nghĩa là $\tau$ nhỏ. Tại $\tau \rightarrow 0$, điểm $B$ “có xu hướng” hướng tới điểm $A$ và hướng của đoạn $AB$ có xu hướng hướng tiếp tuyến với đường cong màu đỏ tại điểm $A$.

Hãy tìm góc $\alpha$ tạo thành đoạn $AB$ có bán kính $OA$. Để thực hiện việc này, hãy tắt đoạn $OC$ ở bán kính $OA$, bằng với chiều dài bán kính $r_2$ và vẽ đoạn $BC$. Vì đoạn $AB$ nhỏ nên đoạn $BC$ trùng với một đường tròn khác có bán kính $r_1$ với tâm tại điểm $O$ và góc $ACB$ gần với một đường thẳng (và tại $\tau \rightarrow 0$ $\Rightarrow ACB \rightarrow \frac{\pi}{2}$). Điều này có nghĩa là

$$\cos \alpha = \frac{AC}{AB}.$$

Nhưng $AB=v\tau$ và $AC=r_0-r_1$. Vì thời gian truyền sóng nổ từ điểm $B$ phải nhỏ hơn m thời gian truyền sóng từ điểm $A$ nên $r_1=r_0-c\tau$. Do đó, $AC=r_0-r_0+c\tau=c\tau$ và

$$\cos \alpha = \frac{c\tau}{v\tau} = \frac{c}{v}.$$

Do đó, góc tiếp tuyến với đường cong màu đỏ và bán kính vẽ tới điểm của đường cong từ điểm $O$ không phụ thuộc vào khoảng cách của đường cong đến điểm $O$, và đường cong màu đỏ cắt tất cả các tia rời khỏi điểm $O$ ở cùng một góc $\alpha = \arccos \frac{c}{v}$. Một tài sản như vậy

⟦folio 51⟧

Cơm. 14.

tới và khúc xạ của tia sáng đối với mỗi mặt phẳng, chúng ta thu được rằng góc mà tia truyền đi trong mỗi mặt phẳng giống như khi ánh sáng chiếu vào nó từ không khí

$$\frac{\sin \beta_1}{\sin \gamma_i} = n_i$$

Cụ thể từ đây, suy ra rằng sau khi đi qua toàn bộ chồng mặt phẳng, tia sáng sẽ đi ra song song với hướng ban đầu của nó:

$$n_{k+1} = 1 \text{ и } \frac{\sin \beta_1}{\sin \gamma_{k+1}} = 1, \text{ то есть}$$

$$\beta_1 = \gamma_{k+1}$$

Sự pha trộn của chùm tia rõ ràng bằng tổng sự pha trộn của nó trong các mặt phẳng riêng lẻ

$$h = h_1 + h_2 + \dots + h_k$$

Hãy tìm hỗn hợp $h_i$ (Hình 14). Để làm điều này, trước tiên hãy tìm $AB$ từ tam giác ADB:

$$AB = \frac{AD}{\cos \gamma_i} = \frac{d}{\cos \gamma_i}$$

Bây giờ từ tam giác ACB ta có

$$h_i = AB \cdot \sin (\beta_1 - \gamma_i)$$

$$= d \frac{\sin (\beta_1 - \gamma_i)}{\cos \gamma_i}$$

$$= d (\sin \beta_1 - \cos \beta_1 \mathrm{tg} \gamma_i)$$

Kể từ $tg \gamma_i = \frac{\sin \gamma_i}{\sqrt{1 - \sin^2 \gamma_i}}$

$$= \frac{\sin \beta_1}{n_i} \sqrt{1 - \left(\frac{\sin \beta_1}{n_i}\right)^2} = \frac{\sin \beta_1}{\sqrt{n_i^2 - \sin^2 \beta_1}}$$

thì $h_i = d \sin \beta_1 \left(1 - \frac{\cos \beta_1}{\sqrt{n_i^2 - \sin^2 \beta_1}}\right)$

$$= d \cos \alpha \left(1 - \frac{\sin \alpha}{\sqrt{n_i^2 - \cos^2 \alpha}}\right)$$

Tổng số chùm trộn là

$$h = h_1 + h_2 + \dots + h_k$$

$$= d \cos \alpha \left( k - \frac{\sin \alpha}{\sqrt{n_1^2 - \cos^2 \alpha}} - \frac{\sin \alpha}{\sqrt{n_2^2 - \cos^2 \alpha}} - \dots - \frac{\sin \alpha}{\sqrt{n_k^2 - \cos^2 \alpha}} \right)$$

$$= d \cos \alpha \left( k - \sin \alpha \sum_{i=1}^{k} \frac{1}{\sqrt{n_i^2 - \cos^2 \alpha}} \right)$$

lời giải chính xác được gửi bởi V. Belov (Vologda), E. Dollov (Moscow), A. Mamula (Dybintsy, vùng Kyiv), V. Mukhanov (Kanash UASSR), S. Pomashev (Ulyanovsk), M. Premer (Tomsk), L. Rudtser (Kharkov), A. Sboev (làng Medvedok, vùng Kirov), P. Sereev (Grozny), Sh. Slepoy (Chernivtsi), N. Tkachenko (Dnepropetrovsk), A. Udaltsov (Kalinerrad, vùng Moscow), N. Fedin (Omsk), S. Fillenko (Zaporozhye), G. Filkovsky (Baku), M. Flerov (Moscow), S. Chekmarev (Moscow), G. Shenemko (David-Gorodok Brest) vùng).

F113

Bình chứa đầy nước một nửa, trong đó có một tảng băng nổi. Dầu hỏa được đổ lên trên đá, mức trên được đặt ở độ cao $h$ tính từ đáy nước sốt (Hình 15). Độ cao này sẽ thay đổi như thế nào khi băng tan?

Trong trường hợp một tảng băng được bao phủ hoàn toàn bằng dầu hỏa (như trong hình), bài toán được giải rất đơn giản.

Chúng ta hãy tinh thần sửa cái vỏ bao quanh một tảng băng và làm tan băng. Hiển nhiên thể tích nước tạo thành sẽ nhỏ hơn thể tích nước đá. Do đó, mức chất lỏng tổng thể trong bình sẽ giảm.

Bây giờ giả sử dầu hỏa không phủ được băng.

Rõ ràng là nếu trong bình chỉ có nước và băng thì sau khi băng tan, mực nước sẽ không thay đổi. Thật vậy, vì lực ép lên đáy nước sốt bằng trọng lượng của chất chứa trong nước sốt và nó không thay đổi khi đá tan nên lực ép lên đáy nước sốt không thay đổi. Điều này có nghĩa là áp suất ở đáy nước sốt không thay đổi. Nhưng băng không gây áp lực trực tiếp lên đáy - nó nổi. Do đó áp suất ở đáy bằng áp suất nước

$$P = \rho_B g h_B$$

Sau khi băng tan, áp suất cũng bằng áp suất nước

$$P = \rho_B g h_B'$$

Điều này có nghĩa là $h_B = h_B'$.

⟦folio 52⟧

Cơm. 15.

Trong trường hợp của chúng tôi, áp suất ở phía dưới cũng không thay đổi. Nhưng bây giờ nó bằng tổng áp suất của bao nhiêu nước và dầu hỏa

$$P = \rho_B g h_1 + \rho_K g (h - h_1) = (\rho_B - \rho_K) g h_1 + \rho_K g h'$$

Nếu mực nước trong bình sau khi đá tan là $h'_1$ và mức dầu hỏa là $h'$ thì

$$(\rho_B - \rho_K) g h'_1 + \rho_K g h' = (\rho_B - \rho_K) g h_1 + \rho_K g h'$$

Gọi thể tích nước đá trong nước bằng $V_1$, thể tích nước đá trong dầu hỏa bằng $V_2$ và khối lượng nước đá bằng $m$. Hãy tưởng tượng rằng, sau khi loại bỏ đá, chúng ta để lại lớp vỏ không trọng lượng của nó và đổ nước và dầu hỏa vào đó sao cho mực nước trong vỏ trùng với mực nước trong bình. Rõ ràng là lớp vỏ này sẽ ở trạng thái cân bằng. Nhưng điều này có nghĩa là vỏ nước chịu tác dụng của lực nổi Archimedean $F$, bằng trọng lượng của chất lỏng đổ vào vỏ

$$F = \rho_B g V_1 + \rho_K g V_2$$

Nếu nước đá được đặt vào vỏ thì lực $F$ sẽ không thay đổi. Nhưng băng trôi. Điều này có nghĩa là $F = mg$ và

$$\rho_B g V_1 + \rho_K g V_2 = mg.$$

Nếu trong bình chỉ có băng và nước thì trong nước sẽ có một thể tích băng $V'_1$ như vậy

$$\rho_B g V'_1 = mg.$$

Từ công thức (1) và (2), suy ra rằng trong trường hợp của chúng ta có thể tích $V_1$ trong nước, nhỏ hơn $V'_1$, tức là nhỏ hơn khối băng được ngâm trong nước khi không có dầu hỏa ở trên. Nhưng trong trường hợp sau, như chúng tôi đã chỉ ra, mực nước trong bình sẽ không thay đổi. Điều này có nghĩa là nước hình thành khi băng tan sẽ lấp đầy chính xác thể tích $V'_1$ của phần chìm trong băng.

Trong trường hợp của chúng ta, thể tích nước tạo thành khi băng tan là như nhau, nhưng thể tích
