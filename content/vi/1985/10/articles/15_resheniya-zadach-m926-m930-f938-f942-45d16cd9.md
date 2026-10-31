---
id: 1985-10-resheniya-zadach-m926-m930-f938-f942-45d16cd9
issue: kvant_1985_10
year: 1985
number: "10"
title: Lời giải bài toán M926—M930; F938—F942
rubric: zadachnik-kvanta
rubric_sub: Задачник «Кванта»
page_first: 36
page_last: 42
page_labels: 34, 35, 36, 38, 39, 40
tag: J2MN
lang: vi
source: kvant_digital
extraction: vision
content_sha256: 290de204d68b08c3e4eb4d255b93327412cb8c7c580dc3ca6252314644ea7271
prompt_sha256: draft-1
translated_from: content/ru/1985/10/articles/15_resheniya-zadach-m926-m930-f938-f942-45d16cd9.md
source_content_sha256: d745215f88c949040a89a51b98e6c2e6bda145266b9f12eb9d23465960cfa2c1
translation_model: draft
translation_run: vi-draft-2026-10-31
translation_quality: draft
---

⟦folio 34⟧

in sequence? How much water must be used when one heater of power $P=100$ Wt is working? The temperature of the water source is $t_1=10^\circ\text{C}$, the aquarium water temperature is $27^\circ\text{C}$, its water mixes very rapidly.

A. R. Zilberman

P962. Point sources, located on the principal optical axis of a lens, constitute a uniformly lighted string (passing through the lens' focus). Find the rule $E(x)$ expressing the luminosity at points of the optical axis on the opposite side of the lens, when the distance $x$ from the lens is large ($x \gg F$, where $F$ is the lens' focal distance).

M. A. Vorontsov, V. E. Kunitsin

Lời giải bài toán

M926 — M930; F938 — F942

Thật thuận tiện để biểu diễn điều kiện bài toán về mặt hình học. Chúng ta hãy đánh dấu các điểm $A(x; y)$ và $B(u; v)$ trên mặt phẳng tọa độ $Oxy$. Góc $AOB$ đúng vì $OA \cdot OB = xu + yv = 0$. Ngoài ra, $OA^2 = x^2 + y^2 = 1$ và $OB^2 = 1$, do đó điểm $B$ thu được từ điểm $A$ bằng cách xoay quanh $O$ theo $\pm 90^\circ$ (xem hình) và $x = \cos \alpha$, $y = \sin \alpha$, trong đó $\alpha$ là góc giữa vectơ $OA$ và trục $Ox$, nghĩa là $u = \cos (\alpha \pm 90^\circ) = \pm \sin \alpha = \mp y$, $v = \sin (\alpha \pm 90^\circ) = \pm \cos \alpha = \pm x$. Kể từ đây,

$$x^2 + u^2 = x^2 + y^2 = 1,$$
$$y^2 + v^2 = y^2 + x^2 = 1,$$
$$xy + uv = xy - xy = 0.$$

Hãy để chúng tôi trình bày thêm một biểu thức đại số thuần túy nữa, lời giải. Hành động tương tự

$$(x^2 + y^2 - 1)^2 + (u^2 + v^2 - 1)^2 + 2(xu + yv)^2 = x^4 + y^4 + u^4 + v^4 + 2 - 2(x^2 + y^2 + u^2 + v^2) + 2(x^2y^2 + u^2v^2 + x^2u^2 + y^2v^2) + 4xuyv = (x^2 + u^2 - 1)^2 + (y^2 + v^2 - 1)^2 + 2(xy + uv)^2$$

phía bên trái, theo điều kiện, bằng 0; Do đó, vế phải cũng bằng 0, tức là ba đẳng thức đang được chứng minh là đúng.

Hãy thử khái quát hóa bài toán của chúng ta cho trường hợp ba chiều - chứng minh rằng nếu ba vectơ có độ dài 1 trong không gian có tọa độ $(x_1; x_2; x_3)$, $(y_1; y_2; y_3)$, $(z_1; z_2; z_3)$ vuông góc từng cặp thì các vectơ $(x_1; y_1; z_1)$, $(x_2; y_2; z_2)$ và $(x_3; y_3; z_3)$ cũng có độ dài 1 và vuông góc từng cặp.

S. V. Duzhin

a) Hãy chứng minh rằng thông qua một số hữu hạn các phép toán “loại a” - thay thế các đoạn giao nhau $AC$ và $BD$ bằng các đoạn không giao nhau $AB$ và $CD$ - chúng ta sẽ đi đến một cấu hình trong đó sẽ không còn các đoạn giao nhau nữa.

Chúng ta hãy xem xét tổng $s$ độ dài của các đoạn cấu hình. Đối với mỗi thao tác loại $a$ nó giảm:

$$AB + CD < AC + BD$$

(đối với lượng giác $APB$ và $CPD$, trong đó $P$ là giao điểm của $AC$ và $BD$ - hình 1, các bất đẳng thức $AB < AP + PB$ và $CD < CP + PD$ thỏa mãn; cộng chúng lại, ta thu được (*)).

Mặt khác, đại lượng $s$ chỉ có thể nhận một số hữu hạn các giá trị, bởi vì

⟦folio 35⟧

vì chỉ có một số hữu hạn các cấu hình khác nhau của các đoạn có đỉnh tại các điểm cho trước. Do đó, trong một số hữu hạn các bước, chúng ta sẽ đi đến một cấu hình mà với nó không còn có thể thực hiện thao tác làm giảm s nữa.

lời giải này cung cấp giới hạn trên rất sâu cho số lượng thao tác $T_n$ tối đa có thể được thực hiện trên một cấu hình ở $n$ điểm - chúng tôi chỉ có thể nói rằng nó nhỏ hơn số lượng tất cả các cấu hình, tức là $2^{n(n-1)^2}$ ($n(n-1)/2$ là số phân đoạn riêng biệt có điểm cuối tại $n$ điểm nhất định).

Hãy để chúng tôi trình bày ý tưởng về một lời giải khác, đưa ra ước tính tốt hơn đáng kể. Chúng ta hãy xem xét việc phân chia tùy ý $f$ các điểm này thành hai tập hợp không trống, mỗi tập hợp nằm hoàn toàn trên một phía của một đường thẳng nào đó $l$. Có hữu hạn, vô số đường thẳng như vậy cho một phân vùng nhất định, nhưng luôn có thể thu được một trong số chúng bằng cách xoay theo chiều kim đồng hồ đường thẳng nối hai điểm cuộn $A$ và $B$ ở một góc rất nhỏ quanh giữa đoạn $AB$ (hình 2); Hãy biểu thị đường thẳng này $l_f$. Số đoạn thẳng $l_f$, và do đó số khoảng cách của các phân vùng “lồi” không vượt quá số cặp điểm $n(n-1)/2$.

Chúng ta hãy gọi sự cân bằng của một cấu hình là tổng số $b$ giao điểm của các đoạn của nó với tất cả các đường $l_f$; rõ ràng là $0 \leq b \leq (n(n-1)/2)^2$. Trong thao tác loại $a$, số giao điểm của bất kỳ đường nào $l_f$ với các đoạn của cấu hình không tăng và đối với ít nhất một đường thì nó giảm đi 2. Do đó, $T_n \leq n^2(n-1)^2/8$. Sẽ rất thú vị nếu có được ước tính chính xác hơn nữa cho $T_n$.

6) Chúng ta hãy đưa ra một ví dụ cho thấy rằng đối với một thao tác “loại $\delta$”—thay thế các phân đoạn giao nhau $AC$ và $BD$ bằng $AB$ và $BC$ có một kết thúc chung—quá trình có thể “đi theo chu kỳ” và do đó tiếp tục vô thời hạn. Chúng ta hãy đặt 18 điểm tại các đỉnh của một 18 giác đều và biểu thị bằng $D(k,l)$ một cấu hình gồm 36 đoạn, trong đó mỗi điểm trong số 18 điểm được kết nối với thứ $k$ và $l$ từ nó trong một hàng.

Để hoàn thành đường dẫn $D(4,8) \rightarrow D(5,9) \rightarrow D(6,7) \rightarrow D(4,8)$ (hình 3) trong 54 thao tác, chỉ cần thực hiện từng thao tác được mô tả trong hình 4 18 lần (xoay ảnh $20^\circ$ mỗi lần) là đủ.

Rõ ràng, cũng có những ví dụ có số điểm $n$ và độ dài chu kỳ $T$ nhỏ hơn đáng kể so với $n=18$ và $T=54$.

N. B. Vasiliev, V. E. Kolosov

⟦folio 36⟧

M928. Trong rạp chiếu phim $N+1$. Lúc đầu, $N$ những người có vé chỉ chỗ ngồi (bao gồm cả Igor) ngồi ngẫu nhiên ở $N$ chỗ ngồi, không ăn vé của mình. Khán giả $(N+1)$ đến cuối cùng muốn thế chỗ; nếu nó bị chiếm giữ - một mặt ở đó, anh ta cũng làm như vậy, v.v. cho đến khi chỗ mà ý thức cần được tự do. Xác suất để Igor phải đổi chỗ là bao nhiêu? (Nói cách khác, tỷ lệ môi trường của tất cả các vị trí có thể có của khán giả là vô hình đối với Igor?)

Đáp số: 1/2. Hãy để chúng tôi chứng minh rằng có nhiều vị trí có lợi cho Igor cũng như có nhiều vị trí không có lợi và sự tương ứng lẫn nhau đã được thiết lập giữa hai vị trí đó.

Giả sử rằng với một số vị trí ban đầu là $P$ $N$ khán giả ở $N+1$ ghế, Igor đã chuyển sang một ghế trống. sau đó bạn nhận được một vị trí mới $P'$. Do đó, tất cả các vị trí có thể được chia thành các cặp $(P, P')$ và nó đủ để chứng minh rằng trong mỗi cặp, một vị trí có lợi cho Igor (nó không có giá trị) và vị trí kia không có lợi.

Nếu $P$ là một vị trí thuận lợi, thì khán giả cuối cùng tham gia chuyển nhượng (tức là có vé cho một ghế trống) ở vị trí $P'$ xứng đáng là Igor. Điều này có nghĩa là $P'$ là một vị trí vô hình. Nếu $P$ là một vị trí không trực quan, thì khán giả xứng đáng với Igor sẽ không có ai xứng đáng ở vị trí $P'$, vì vậy việc chuyển nhượng sẽ kết thúc ở đó, tức là $P'$ là vị trí có lợi cho Igor.

I. V. Alekseev-Astafev

M929. Các số tự nhiên $a, b, c, d$, e thỏa mãn điều kiện $a^4 + b^4 + c^4 + d^4 = e^4$. Chứng minh rằng ít nhất $a$ ba trong số chúng là số chẵn, $b$ ba chia hết cho 5, $b$ hai chia hết cho 10.

Định lý nhỏ Fermat
Đối với mọi số nguyên $n$ và số nguyên tố $p$, số $n^p - n$ chia hết cho $p$.

Đáp án: 1/2. Hãy để chúng tôi chứng minh rằng có nhiều vị trí có lợi cho Igor cũng như có nhiều vị trí không có lợi và sự tương ứng lẫn nhau đã được thiết lập giữa hai vị trí đó.

Giả sử rằng với một số vị trí ban đầu là $P$ $N$ khán giả ở $N+1$ ghế, Igor đã chuyển sang một ghế trống. sau đó bạn nhận được một vị trí mới $P'$. Do đó, tất cả các vị trí có thể được chia thành các cặp $(P, P')$ và nó đủ để chứng minh rằng trong mỗi cặp, một vị trí có lợi cho Igor (nó không có giá trị) và vị trí kia không có lợi.

Nếu $P$ là vị trí thuận lợi thì khán giả cuối cùng tham gia chuyển nhượng (tức là có vé ngồi ghế trống), tại vị trí $P'$ sẽ không có người đứng nên việc chuyển tuyến sẽ kết thúc ở đó, tức là $P'$ là vị trí thuận lợi cho Igor.

I. V. Alekseev-Astafev

a) Lưu ý rằng số $n^4$ khi $n$ là số chẵn thì chia hết cho 16 và khi $n$ là số lẻ thì khi chia cho 16 thì dư 1. (Thật vậy, khi $n=2k+1$
$n^4-1=(n-1)(n+1)(n^2+1)=$
$=8k(k+1)(2k^2+2k+1)$,
và $k(k+1)$ luôn chia hết cho 2.)
Do đó, phần dư của $a^4+b^4+c^4+d^4+e^4$ chia cho 16 bằng số số lẻ giữa $a, b, c, d$. Và vì nó phải trùng với phần còn lại tương tự của $e^4$, nên chúng ta thấy rằng điều kiện bài toán chỉ có thể được thỏa mãn nếu tất cả các số đều là số chẵn hoặc nếu số $e$ và chính xác một trong các số khác là số lẻ. Điều này cũng chứng minh khẳng định a).

6) Đối với số dư khi chia số $n^4$ cho 5, phát biểu tương tự như đã chứng minh ở điểm a là đúng: số dư này bằng 0 hoặc 1, tùy thuộc vào việc $n$ có chia hết cho 5 hay không. (Thật vậy, nếu $n=5k±1$ thì $n^2-1=5k(5k±2)$ chia hết cho 5; nếu $n=5k±2$ thì $n^2+1=5k(5k±4)+5$ chia hết cho 5. Do đó, $n^4-1=(n^2-1)(n^2+1)$ luôn chia hết cho 5 nếu $n$ không phải là bội số của 5. Mệnh đề này là trường hợp đặc biệt của cái gọi là định lý nhỏ Fermat, công thức của định lý này đã cho ở lề.)

Bây giờ, theo cách tương tự như trong lời giải ở a), chứng minh rằng tất cả các số $a, b, c, d, e$ đều chia hết cho 5 hoặc số $e$ và có chính xác một trong các số còn lại không chia hết cho 5, tức là có 6).
c) Xét ba trường hợp.

1) Số $e$ là số chẵn. Từ lời giải bài toán a) suy ra rằng tất cả các số khác cũng là số chẵn và từ lời giải bài toán 6) có ít nhất ba trong số chúng chia hết cho 5 và do đó chia hết cho 10.

2) Số $e$ chia hết cho 5. Trường hợp này được xử lý tương tự như trường hợp trước: tất cả

⟦folio 38⟧

cho $f_0 = e_1 - e_0$ và $f_1 = e_2 - e_0$ từ tập $F$, hiệu $f_1 - f_0 = e_2 - e_1$ của chúng cũng phải thuộc về tập $F$, điều này mâu thuẫn với giả định của chúng tôi.

Kết quả mâu thuẫn chứng tỏ khẳng định bài toán.

Lập luận theo cách tương tự như trong lời giải đã cho, không khó để chứng minh rằng mệnh đề bài toán đúng cho bất kỳ phân vùng nào của các số $N$ đầu tiên $1, 2, ..., N$ thành các tập hợp $k$ cho

$$N = N_k = k! \left( 1 + \frac{1}{1!} + \frac{1}{2!} + \dots + \frac{1}{k!} \right)$$

($n! = 1 \cdot 2 \cdot \dots \cdot n$). Các giá trị của $N_k$ cho $k = 1, ..., 6$ được tính trong lề. Rõ ràng là với mọi $N \geqslant N_k$ mệnh đề bài toán sẽ đúng với tập $k$; trong trường hợp của chúng tôi $1985 > 1957 = N_6$. Lưu ý rằng tổng trong ngoặc đơn ở bên phải của (3) tại $k \to \infty$ sẽ rất nhanh chóng bị giảm xuống cơ số logarit tự nhiên - số $e = 2,718$... Nó có thể kiểm tra xem $N_k = [k! e]$, nhưng thật không may, công thức đẹp đẽ này không cho giá trị phù hợp nhỏ nhất $N$ cho một $k$ đã cho; ví dụ: đối với $k = 3$ giá trị nhỏ nhất là 14, không phải 16. Ở đây có thể ước tính bài toán thú vị nhưng có vẻ khó khăn về giá trị nhỏ nhất này. Chẳng hạn, có đúng là nó luôn lớn hơn $ck!$, trong đó $c$ là một hằng số nào đó không? Ước tính được biết đến nhiều nhất cho đến nay vẫn là $(3^k - 1)/2$ của A. Khodleva (xem lời giải bài toán M540, «Kvant» Số 12, 1979, trang 23).

A. D. Valtsev, V. N. Dubrovsky

F938. Phi công của một tàu vũ trụ di chuyển với tốc độ $v = 1$ km/s, sau đó với tốc độ của một tàu vũ trụ có đường kính $d = 7$ km, khi vẫn còn khoảng cách $l = 8,5$ km trên bề mặt của nó. Phi hành gia ngay lập tức bật động cơ khẩn cấp, trong một thời gian ngắn động cơ này sẽ truyền cho con tàu thêm tốc độ $\Delta v = 300$ m/s, hướng do phi hành gia đặt ra. Liệu một con tàu có thể tránh được va chạm?

♦

Để tránh va chạm, phi hành gia cũng phải thay đổi tốc độ của tàu sao cho góc giữa hướng ban đầu “hướng về tiểu hành tinh” và hướng đi mới lớn hơn góc $\alpha_0$ xác định bởi các điều kiện (hình 1)

$$\sin \alpha_0 = \frac{d/2}{l + d/2} = \frac{d}{2l + d} \approx 0,292.$$

Độ lệch tối đa so với hướng ban đầu khi truyền thêm tốc độ $\Delta v$ cho tàu được đảm bảo trong trường hợp vectơ $\vec{\Delta v}$ vuông góc với vectơ $\vec{v}_1 = \vec{v} + \vec{\Delta v}$ (hình 2), tức là khi

Hình 1.

Hình 2.

$$\sin \alpha = \frac{\Delta v}{v} = 0,3.$$

Điều này có nghĩa là khi bật động cơ khẩn cấp, phi hành gia có thể thay đổi hướng đi của con tàu một góc $\alpha > \alpha_0$ và sẽ không xảy ra va chạm với tiểu hành tinh.

A. V. Andrianov

F939. Đáy tàu nghiêng một góc $\alpha = 45^\circ$ so với đường chân trời. Đáy có hình bán cầu lồi bán kính $R$

♦

Xét một vật có dạng nửa quả cầu có bán kính $R$. Giả sử nó ở vị trí Q và hướng theo hướng

⟦folio 39⟧

(hình 1). Chiều cao của lượng chất lỏng này so với mặt lồi bằng N. Lực thẳng đứng nào do chất lỏng tác dụng lên phần lồi của đáy? Mật độ của chất lỏng là q.

Hình 1.

Hình 2.

Các chấm của Stran giống như chỗ phình ra ở đáy của một chiếc bình nhất định.

Theo định luật Archimedes, vật này chịu tác dụng của một lực nổi $\vec{F}$, hướng thẳng đứng lên trên và bằng mô đun

$$F = \varrho g V = \varrho g \frac{1}{2} \cdot \frac{4}{3} \pi R^3 = \frac{2}{3} \varrho g \pi R^3.$$

Mặt khác, lực $\vec{F}$ có thể được biểu diễn dưới dạng tổng của hai lực áp suất từ ​​chất lỏng: lực $\vec{F}_1$, tác dụng lên “đế” của một nửa quả bóng và lực $\vec{F}_2$, tác dụng lên bề mặt bên của nó (hai khả năng so sánh được thể hiện trong hình 2):

$$\vec{F} = \vec{F}_1 + \vec{F}_2.$$

Chúng ta quan tâm đến hình chiếu của lực $\vec{F}_2$ lên trục tung (chúng ta ký hiệu là X và hướng nó lên trên):

$$F_{2x} = F - F_{1x} \quad (\text{для одного сличая})$$

hoặc

$$F_{2x} = F_{1x} - F \quad (\text{для другого сличая}).$$

Để tìm mô đun và hình chiếu của lực $\vec{F}_1$, chúng ta lưu ý rằng áp suất tăng tuyến tính theo độ sâu và do đó chúng ta có thể sử dụng giá trị trung bình của nó:

$$F_1 = p_{cp} S = \varrho g (H + R) \pi R^2,$$
$$F_{1x} = \varrho g (H + R) \pi R^2 \cos \alpha.$$

Sau đó, đối với ngoại lệ chúng tôi nhận được

$$F_{2x} = F - F_{1x} = \frac{2}{3} \varrho g \pi R^3 - \varrho g (H + R) \pi R^2 \cos \alpha$$

hoặc

$$F_{2x} = F_{1x} - F = \varrho g (H + R) \pi R^2 \cos \alpha - \frac{2}{3} \varrho g \pi R^3.$$

Ở góc $\alpha = 45^\circ$, phép so sánh đầu tiên hóa ra là không thể: $2/3 < \cos \alpha = \sqrt{2}/2$, do đó $F_{2x} < 0$, không thể xảy ra trong tình huống này. Vì vậy, so sánh thứ hai vẫn là:

$$F_{2x} = \varrho g \pi R^2 \left( (H + R) \cos \alpha - \frac{2}{3} R \right).$$

L. G. Markovich

F940. Tại sao vữa đất sét được sử dụng trong lò gạch để uốn gạch mà không phải là xi măng (mặc dù nó cứng hơn)?

Có thể xảy ra sự chênh lệch nhiệt độ lớn và không đồng đều về thời gian và thể tích trong lò. Nếu gạch và vữa được làm bằng các vật liệu khác nhau (tức là từ các vật liệu có hệ số giãn nở nhiệt khác nhau) thì khi nhiệt độ thay đổi (làm mát, sưởi ấm) chúng sẽ thay đổi thể tích khác nhau (giãn nở, co lại). Điều này sẽ dẫn đến xuất hiện ứng suất bên trong lớn tại các điểm tiếp xúc giữa gạch và vữa; Kết quả là lò sẽ bị nứt.

V. A. Ilyin

F941. Trong từ trường có dòng điện thẳng một chiều, chúng ta thấy khung hình vuông ABCD (xem.

⟦folio 40⟧

hình). Khung được di chuyển đến vị trí mới, được hiển thị trong hình bằng đường chấm. Điều này có thể được thực hiện theo hai cách: bằng cách quay đều quanh phía CD hoặc bằng cách dịch song song đều dọc theo AD. Phương pháp nào sẽ tạo ra nhiều nhiệt hơn nếu thời gian di chuyển khung đến vị trí mới nhìn chung là như nhau?

F942. Một sóng ánh sáng phẳng rơi bình thường lên màn E. Độ rọi của màn tại điểm M sẽ thay đổi như thế nào (xem hình) nếu đặt một tấm đục bán âm P trên đường đi của sóng, song song với màn?

Mặt sóng của sóng phẳng là mặt phẳng vuông góc với phương truyền sóng. Ánh sáng rơi bình thường lên tấm P, do đó mặt phẳng đặt tấm này là một trong các bề mặt sóng và nó có thể được coi là một tập hợp các nguồn thứ cấp giống hệt nhau dao động cùng pha. Độ rung thu được tại điểm M trên màn hình là sự chồng chất của các rung động đến từ các nguồn này.

Khi đưa tấm vào thì một nửa nguồn thứ cấp sẽ bị đóng lại. Do đó biên độ dao động tại điểm M sẽ giảm đi 2 lần. Độ rọi của màn hình tại điểm M tỷ lệ với bình phương của biên độ này. Do đó, khi đưa tấm này vào, độ chiếu sáng sẽ giảm đi 4 lần.

D. A. Kuptsov

Cứ như thể trái đất đang bị bào mòn và không còn nơi nào có thể nhìn thấy đất rắn để xây dựng. Đối với tôi, điều luôn có vẻ thuận tiện là cơ sở dao động và đầy mâu thuẫn này đủ để cho phép Bohr - một người có trực giác tuyệt vời và khả năng cảm nhận tinh tế - tìm ra các định luật quan trọng nhất của các vạch quang phổ và vỏ electron của nguyên tử, bao gồm cả ý nghĩa của chúng đối với hóa học. Tôi đã đạt được chất lượng này ngay cả bây giờ. Đây được gọi là âm nhạc trong lĩnh vực tư duy.

A. Einstein

Trong toàn bộ thế giới khoa học trong lịch sử của chúng ta, không có người nào có ảnh hưởng đến tự nhiên như Bohr. Trong tất cả các lý thuyết lý thuyết, lý thuyết của Bohr là quan trọng nhất.

P. Kapitsa

Tôi đến Liên Xô để gặp gỡ những người bạn cũ và tìm những người bạn mới, bởi vì nội dung của các nhà khoa học từ các quốc gia khác nhau không chỉ giúp ích cho sự phát triển của khoa học mà còn giúp ích cho sự nghiệp hòa bình.

N. Bor

Tôi vẫn học được khi nhìn vào một lò phản ứng hạt nhân.

N. Bor

Nếu tôi có thể làm bất cứ việc gì một cách khéo léo thì có lẽ tôi nên nghĩ... N. Bohr

Lý thuyết lượng tử không làm tôi bối rối trước những vấn đề của nó. Bây giờ vấn đề chính là tìm cách ngăn chặn sóng hạt nhân!

N. Bor
