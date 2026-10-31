---
id: 1971-6-resheniya-2ec5edef
issue: kvant_1971_6
year: 1971
number: "6"
title: Lời giải các bài toán M34—M38; F52—F58
rubric: zadachnik-kvanta
rubric_sub: Задачник «Кванта»
page_first: 37
page_last: 47
page_labels: 35, 36, 37, 38, 40, 41, 42, 43, 44, 45
tag: GCCN
lang: vi
source: kvant_digital
extraction: vision
content_sha256: 1ab8150d4dfd4b93afac994ce298766545a9b8ccea19e7c27e50f2ae0fc34ae7
prompt_sha256: 3ec6b8aabd9b98576af76503cd8a2902b9f5d18e01ee867dfb1228f59c6d52d8
translated_from: content/ru/1971/06/articles/11_resheniya-2ec5edef.md
source_content_sha256: a54702f559c4a03b80cb5b09ac40cef6ad3c8a5bc1d5790a344105c3c1765c79
translation_model: gpt-5.6-terra
translation_run: vi-codex-2026-10-31
---

⟦folio 35⟧

LỜI GIẢI

Trong số này chúng tôi công bố lời giải các bài M34—M38.

M34

Chứng minh rằng nếu một số tự nhiên chia hết cho 10 101 010 101, thì trong cách viết thập phân của nó có ít nhất sáu chữ số khác không.

Bài toán được giải rất dễ, nếu số $A$, chia hết cho 10 101 010 101, có không quá 12 chữ số; khi đó nó nhất thiết có dạng $ababababab$, và bài toán đã được giải quyết.

Còn lại là nghĩ ra một cách nào đó để đưa bài toán về trường hợp này.

Số 10 101 010 101 ta ký hiệu là $M$. Ta sẽ chứng minh rằng nếu số $A$ chia hết cho $M$, thì tồn tại một số $C$ có mười hai (hoặc ít hơn) chữ số, cũng chia hết cho $M$ và có không nhiều chữ số khác không hơn $A$.

Bổ đề. Nếu $A$ chia hết cho $M$ và có hơn 12 chữ số (kể cả các số không), thì tồn tại một số $B$, cũng chia hết cho $M$, nhỏ hơn $A$ và có không nhiều chữ số khác không hơn $A$.

Hãy chứng minh điều này. Cho $A = a_1a_2a_3\dots a_n$; xóa chữ số đầu tiên $a_1$ của nó và cộng nó xuống dưới 12 hàng, ví dụ:

$$123\ 456\ 789\ 123\ 456 \rightarrow 23\ 456\ 789\ 123\ 456$$
$$+\frac{1}{23\ 456\ 789\ 123\ 556}$$

Số nhận được chắc chắn nhỏ hơn số ban đầu: dễ kiểm tra rằng ta chỉ tính $a_1 \cdot (10^{n-1} - 10^{n-13})$. Trong ngoặc

⟦folio 36⟧

là tích $10^{n-13} \times (10^{12}-1)$; thừa số thứ hai hiển nhiên chia hết cho $A$. Còn phải lưu ý rằng trong số nhận được, số chữ số có nghĩa (khác 0) không nhiều hơn số ban đầu. Trong ví dụ của chúng ta, số lượng của chúng thậm chí giảm đi một; tuy nhiên, điều này có thể không xảy ra nếu ở vị trí thứ 13 là 0 hoặc nếu ở đó là một chữ số đủ lớn, còn ở vị trí trước đó là 0, như trong ví dụ

$$888 888 888 880 421 \rightarrow 88 888 888 880 421$$
$$+\frac{8}{88 888 888 881 221}$$

(ta chưa xét trường hợp khi nhớ cũng xảy ra ở hàng thứ 12, nhưng dễ thấy rằng khi đó số chữ số có nghĩa còn giảm đi). Bổ đề được chứng minh.

Bây giờ nếu $A$ chia hết cho $M$, ta trừ khỏi $A$ chữ số đầu tiên của nó, nhân với $10^{n-13} \cdot (10^{12}-1)$. Với số nhận được, ta làm phép toán ấy và cứ tiếp tục như vậy cho đến khi đạt tới một số có 12 chữ số. Vì trong đó có không ít hơn sáu chữ số có nghĩa, nên trong $A$ cũng có không ít hơn sáu chữ số có nghĩa.

Đa số những người giải đã thử xét thương của phép chia $A$. cho $M$;

nhưng giải nó bằng cách này rất khó, vì khi nhân ngược thương này với 10 101 010 101, các chữ số của nó «dính» vào nhau, có thể xảy ra nhiều lần nhớ đơn vị ở các hàng, và gần như không thể hiểu được kết quả sẽ là gì. Ý tưởng của lời giải là xét từng lần nhớ ấy một.

A. K. Tolpyeo

M35

Một đa diện 19 mặt nào đó được ngoại tiếp quanh mặt cầu bán kính 10. Chứng minh rằng trên bề mặt của nó có hai điểm mà khoảng cách giữa chúng lớn hơn 21.

Lời giải thứ nhất. Giả sử ngược lại, tức là khoảng cách giữa bất kỳ hai điểm nào trên bề mặt của đa diện 19 mặt của chúng ta không lớn hơn 21. Khi đó đa diện này nằm bên trong mặt cầu bán kính 11, đồng tâm với mặt cầu bán kính 10, và mỗi mặt của nó nằm giữa hai mặt cầu. Vì thế diện tích mỗi mặt không quá lớn, cụ thể là không vượt quá diện tích hình tròn chỉ trên hình 1, có bán kính bằng $\sqrt{21}$. Đa diện của chúng ta có 19 mặt, vì thế diện tích $S$ bề mặt của nó không vượt quá $19\left[\pi\left(\sqrt{21}\right)^2\right]=\pi\left(20^2-1^2\right)=399\pi$.

Nhưng đa diện được ngoại tiếp quanh mặt cầu bán kính 10. Từ đó diện tích bề mặt của nó lớn hơn diện tích mặt cầu này $4\pi\left(10\right)^2$*. Vậy, một mặt thì $S<399\pi$, mặt khác thì $S>400\pi$. Mâu thuẫn thu được giải quyết bài toán. (Một lời giải tương tự do D. Grizoryev ở Leningrad gửi cho chúng tôi.)

Trong lời giải (không chặt chẽ) này, chúng ta đã bỏ qua chứng minh của ba khẳng định bắt đầu bằng ba từ in nghiêng ở trên: khi đó, vì thế, từ đó. Chúng tôi để những chứng minh đơn giản này cho bạn đọc, nhưng muốn cảnh báo rằng mặc dù khẳng định cần thiết dễ chứng minh đối với đa diện lồi

*) Nhắc lại rằng đối với hình cầu bán kính $R$, thể tích bằng $\frac{4}{3}\pi R^3$, diện tích mặt cầu đới có chiều cao $h$ bằng $2\pi Rh$ và, riêng, diện tích mặt cầu bằng $4\pi R^2$.

⟦folio 37⟧

bằng cách so sánh thể tích của nó với thể tích hình cầu *), tuy nhiên, khẳng định trực giác rõ ràng và đúng rằng đa diện của chúng ta lồi lại khó chứng minh một cách chặt chẽ, vì bản thân định nghĩa chặt chẽ của đa diện rất phức tạp. (Chẳng hạn, hãy xem sách của I. Lakatos «Chứng minh và bác bỏ», M., «Nauka», 1967).

Lời giải thứ hai. Ta đặt một câu hỏi tổng quát hơn: một đa diện nội tiếp quanh một mặt cầu bán kính $r$ và nằm hoàn toàn trong mặt cầu đồng tâm với nó bán kính $R > r$ có thể có nhiều nhất bao nhiêu mặt? (Đây là tình huống đời thường đã gợi cho tác giả bài toán này: có thể dùng dao chém thẳng nhiều nhất bao nhiêu nhát để cắt hết lớp vỏ trên của quả cam mà không cắt phải một miếng lõi nào? Rõ ràng, sau khi cắt hết toàn bộ lớp vỏ trên, phần còn lại sẽ là một đa diện, vì trên bề mặt của nó sẽ không còn một phần cong nào, nên câu hỏi này tương đương với câu hỏi trước.) Ta không biết chính xác đáp án cho câu hỏi tổng quát hơn này, nhưng sẽ chứng minh một số bất đẳng thức đối với số mặt, mà khi $r = 10$, $R = 11$ cho thấy rằng $N > 22$. Như vậy, ta đã chứng minh rằng nếu trong điều kiện của bài M35, thay đa diện 19 mặt bằng đa diện 22 mặt, thì khẳng định của bài vẫn đúng.

Vậy, giả sử một đa diện $N$ mặt nội tiếp quanh một mặt cầu bán kính $r$ và nằm hoàn toàn bên trong một mặt cầu bán kính $R$. Xét một mặt bất kỳ của nó.

Mặt phẳng đi qua mặt ấy cắt từ mặt cầu một chỏm cầu (mặt phân đoạn) có chiều cao $R - r$. Rõ ràng, nếu dựng các chỏm cầu cho tất cả các mặt của đa diện chúng ta, thì hợp của chúng sẽ phủ toàn bộ mặt cầu ngoài. Mỗi chỏm trong $N$ chỏm

*) Thật vậy, thể tích của đa diện bằng $\frac{R \cdot S}{3}$, trong đó $R$ là bán kính mặt cầu nội tiếp, còn $S$ là diện tích bề mặt của nó.

mặt phân đoạn có chiều cao $R - r$, và do đó có diện tích $2\pi R (R - r)$. Tổng diện tích của tất cả các chỏm lớn hơn diện tích mặt cầu. Vì vậy $N \cdot 2\pi R (R - r) > 4\pi R^2$, từ đó $N > \frac{2R}{R - r}$, đặc biệt, với $R = 11$, $r = 10$ ta được $N > 22$.

Điều thú vị là từ bất kỳ tập hợp nào các chỏm phủ kín hoàn toàn mặt cầu ngoài, có thể dựng một đa diện ngoại tiếp mặt cầu trong. (Hãy chứng minh!) Vì vậy câu hỏi của chúng ta về số mặt tối thiểu hoàn toàn tương đương với câu hỏi sau. Số tối thiểu $N = N(h)$ các chỏm có chiều cao $h$, phủ kín hoàn toàn các mặt cầu bán kính 1, là bao nhiêu? (Trong bài toán $M35 h = \frac{1}{11}$).

Rõ ràng, $N(h) > \frac{2}{h}$, nhưng bất đẳng thức này chỉ phản ánh sự kiện rằng tổng diện tích các chỏm lớn hơn diện tích mặt cầu, trong khi trực giác cho thấy rằng khi $h < 1$ các chỏm phải chồng lấn lên nhau khá nhiều. Và thực sự, có thể chứng minh rằng với $h$ đủ nhỏ thì $N(h) > 1,2 \frac{2}{h}$. Hãy tự thử chứng minh, chẳng hạn, rằng khi $h < 1$

$N(h) > 1,001 \frac{2}{h}$.

(Có thể xem lời giải của bài toán này và những bài toán tương tự khác trong sách của L. F. Tota. “Sự sắp xếp trên mặt phẳng, trên mặt cầu và trong không gian”. M., Fizmatgiz, 1958).

A. G. Kushirienko

M36

Chứng minh rằng trên mặt phẳng không thể sắp xếp bảy đường thẳng và bảy điểm sao cho qua mỗi điểm có ba đường thẳng đi qua và trên mỗi đường thẳng có ba điểm nằm.

Giả sử rằng một cách sắp xếp như vậy của bảy điểm và bảy đường thẳng tồn-

⟦folio 38⟧

Hình 2. Bao lồi của một tập hợp hữu hạn điểm là một đa giác lồi có các đỉnh là một số trong các điểm ấy (hoặc là một đoạn thẳng, nếu mọi điểm đều nằm trên một đường thẳng).

tại. Trước hết chứng minh rằng mỗi hai trong các điểm đã cho nằm trên một trong các đường thẳng đã cho. Thật vậy, nếu $A$ là một trong các điểm ấy, thì qua $A$ có ba đường thẳng đi qua, và trên mỗi đường thẳng ấy có hai trong các điểm đã cho nằm (không kể $A$); do đó $A$ và bất kỳ một trong sáu điểm khác $A$ nằm trên một trong các đường thẳng đã cho. Tương tự, chứng minh được rằng mỗi hai trong các đường thẳng đã cho cắt nhau tại một trong các điểm đã cho: nếu $a$ là một trong các đường thẳng, thì qua mỗi trong ba điểm nằm trên nó có hai đường thẳng đi qua (không kể $a$), và vì thế mỗi đường thẳng ấy cắt $a$ tại một trong các điểm đã cho.

Bây giờ xét bao lồi của tập hợp gồm bảy điểm của ta — hình lồi nhỏ nhất chứa bảy điểm ấy.

Hình 3. Cấu hình này gần như hoàn toàn thỏa mãn các yêu cầu của bài M36, chỉ có một “đường thẳng” phải uốn cong.

Đó sẽ là một $n$-giác lồi nào đó, với $n \leqslant 7$ (có thể dựng nó như sau: đóng đinh tại bảy điểm đã cho rồi căng một sợi dây cao su bao quanh tất cả các đinh đó; sợi dây sẽ căng theo đường bao của một đa giác có các đỉnh là một số $n$ trong các điểm đã cho, còn tất cả các điểm khác ($7-n$) sẽ nằm bên trong hoặc trên biên của đa giác này; xem hình 2). Rõ ràng trường hợp $n \geqslant 4$ là không thể — vì trên mỗi cạnh của $n$-giác phải có thêm một điểm thứ ba, ngoài các đỉnh, trong khi tổng cộng chỉ có bảy điểm. Trường hợp $n=3$, khi bao lồi là một tam giác nào đó $ABC$, cũng không thể. Thật vậy, nếu $E$ và $F$ là các điểm (trong số bảy điểm đã cho) nằm trên các cạnh $AB$ và $BC$, thì $EF$ và $AC$ — hai trong các đường thẳng đã cho — phải cắt nhau tại một trong bảy điểm đã cho, nhưng chúng sẽ cắt nhau trên phần kéo dài của cạnh $AC$, tức là ở ngoài tam giác $ABC$. Ta được mâu thuẫn.

Hình 3 sẽ giúp những người đã gửi cho chúng tôi lời giải sai của bài toán này tìm ra sai lầm.

M37

Trong mỗi ô của một tờ giấy kẻ ô vô hạn có ghi một số nào đó sao cho tổng các số trong bất kỳ hình vuông nào (các cạnh của nó đi theo các đường lưới) không vượt quá một theo môđun. Chứng minh rằng khi đó tồn tại một số $c$ sao cho tổng các số trong bất kỳ hình chữ nhật nào (các cạnh của nó đi theo các đường lưới) không lớn hơn $c$; nói cách khác, các tổng số trong mọi hình chữ nhật đều bị chặn. Chứng minh rằng điều này đúng với $c=4$. Có thể bạn sẽ cải thiện được đánh giá này (chẳng hạn, chứng minh rằng khẳng định của chúng tôi đúng với $c=3$ hoặc thậm chí với $c=2$).

Lời giải mà chúng tôi đưa ra gần với đề xuất của $A$. Klimov (Moskva).

Chứng minh rằng $c$ bằng 4 là phù hợp.

Giả sử rằng trong một hình chữ nhật nào đó có các cạnh $a$ và $b$ tổng có môđun bằng $4+\epsilon$, trong đó $\epsilon > 0$ ($a < b$). Dựng bốn hình vuông, mỗi hình có ba cạnh đi theo một số ba đườn-

⟦folio 40⟧

Hình 6. Đặt $k_n = \frac{a_n}{b_n}$. Khi đó $k_{n+1} = f(k_n)$, trong đó $f(k) = \frac{|1-2k|}{2-k}$. Ở đây biểu diễn đồ thị của hàm này trên đoạn $0 \leq k \leq 1$. Khi giải bài toán, ta thu được rằng với mọi điểm $M$ thuộc nửa phải của đồ thị $MQ/MP > 2$; nếu $0 \leq k \leq \frac{1}{2}$, thì $0 \leq f(k) \leq \frac{1}{2}$, hơn nữa $f(f(k)) = k$, tức là hàm $f$ trên đoạn $0 \leq k \leq \frac{1}{2}$ trùng với hàm ngược của nó, và đồ thị của nó đối xứng qua tia phân giác của góc giữa các trục tọa độ.

Hình 7. Trong tất cả các ô chưa điền đều là số 0.

Thứ hai, nếu $\frac{a_n}{b_n} > \frac{1}{2}$, thì

$$\frac{1 - \frac{a_{n+1}}{b_{n+1}}}{1 - \frac{a_n}{b_n}} = \frac{1 - \frac{2a_n - b_n}{2b_n - a_n}}{1 - \frac{a_n}{b_n}} = \frac{3b_n}{2b_n - a_n} > \frac{3b_n}{2b_n - \frac{b_n}{2}} = 2;$$

do đó, đại lượng $1 - \frac{a_n}{b_n}$ khi chuyển từ $n$ sang $n+1$ tăng ít nhất gấp hai lần cho đến khi ta đi đến hình chữ nhật có $\frac{a_n}{b_n} \leq \frac{1}{2}$. Vì vậy, ta có thể giả sử rằng ngay từ đầu $\frac{a_1}{b_1} < \frac{1}{2}$.

Khi đó

$$a_3 = b_2 - 2a_2 = (2b_1 - a_1) - 2(b_1 - 2a_1) = 3a_1,$$

$$b_3 = 2b_2 - a_2 = 2(2b_1 - a_1) - (b_1 - 2a_1) = 3b_1.$$

Do đó, nói chung $a_{2k+1} = 3^k a_1$ và $b_{2k+1} = 3^k b_1$, hơn nữa tổng các số trong hình chữ nhật $3^k a_1 \times 3^k b_1$ lớn hơn $4 + 9^k e$, tức là, chọn $k$ đủ lớn, ta có thể làm cho nó lớn tùy ý. Bây giờ không khó để nhận được mâu thuẫn: rõ ràng, mọi hình chữ nhật $Na_1 \times Nb_1$, trong đó $a_1$, $b_1$ và $N$ là các số nguyên, đều có thể chia thành $a_1b_1$ hình vuông (có cạnh $N$), và vì thế tổng các số trong đó không thể vượt quá về trị tuyệt đối số $a_1b_1$.

Hình 6 cho thấy nửa sau của chứng minh. Hình 7 biểu diễn một ví dụ mà tổng các số trong một số hình chữ nhật bằng ba. Như vậy, với $c = 2$ mệnh đề của bài toán là sai. Rất có khả năng đánh giá chính xác là $c = 4$, nhưng chúng tôi không biết các ví dụ cho thấy rằng $c > 3$.

N. B. Vasiliev

⟦folio 41⟧

M38

Đường tròn dựng trên đường cao AD của tam giác vuông ABC làm đường kính cắt cạnh góc vuông AB tại điểm K, còn cạnh góc vuông AC tại điểm M. Đoạn thẳng KM cắt đường cao AD tại điểm L. Biết rằng các đoạn AK, AL và AM lập thành một cấp số nhân (tức là $\frac{AK}{AL} = \frac{AL}{AM}$).

Không khó chứng minh rằng AKDM là hình chữ nhật và L là tâm của nó (hình 8). Hạ đường vuông góc AP xuống KM.

Khi đó
$$AL^2 = AK \cdot AM = KM \cdot AP = 2AL \cdot AP,$$
$$AL = 2AP, \angle PLA = 30^\circ,$$

và vì $AL = KL = ML$, suy ra các góc nhọn của tam giác AKM bằng $15^\circ$ và $75^\circ$. Tam giác ABC cũng có các góc nhọn như vậy: $\angle C = \angle BAD = \angle AKM$.

Hình 8.

Lời giải này do C. Komanov từ Tbilisi và V. Krivitsky từ làng Kletno, tỉnh Minsk gửi đến.

L. M. Lopovok

Trong số này chúng tôi công bố lời giải các bài toán F52—F58

F52

Một quả bóng được ném thẳng đứng lên trên. Cái nào lớn hơn: thời gian bay lên hay thời gian rơi xuống?

Động năng của quả bóng ở bất kỳ độ cao nào khi bay lên đều lớn hơn khi quả bóng đi xuống. Thật vậy, nếu không có sức cản của không khí thì các năng lượng này bằng nhau. Do sức cản của không khí, khi đi xuống động năng của quả bóng nhỏ hơn khi bay lên một lượng bằng công dùng để thắng sức cản của không khí. Điều đó có nghĩa là ở bất kỳ độ cao nào vận tốc của quả bóng khi bay lên đều lớn hơn khi đi xuống. Rõ ràng vận tốc trung bình của quả bóng cũng lớn hơn. Vì vậy thời gian bay lên của quả bóng nhỏ hơn thời gian rơi xuống.

F53

Trong một bình có hai chất lỏng không trộn lẫn với khối lượng riêng $\rho_1$ và $\rho_2$ và độ dày các lớp $h_1$ và $h_2$ tương ứng. Từ mặt thoáng của chất lỏng, người ta thả vào bình một vật nhỏ có dạng khí động, vật chạm đáy đúng vào lúc vận tốc của nó bằng không. Khối lượng riêng của vật liệu làm vật bằng bao nhiêu?

Ta dùng nhận xét rằng thế năng mà vật có ở mặt thoáng của chất lỏng trên được tiêu hao khi vật chuyển động để thắng sức cản. Vì vậy
$$mg(h_1 + h_2) = A_1 + A_2,$$
(*)

trong đó $m$ là khối lượng của vật, $g$ là gia tốc rơi tự do, $A_1$ là công của lực cản trong chất lỏng phía trên và $A_2$ là công của lực cản khi vật chuyển động trong chất lỏng phía dưới. Vì vật có dạng thuôn dòng, lực cản là lực đẩy Ác-si-mét: $F_1 = \rho_1Vg$ trong chất lỏng phía trên và $F_2 = \rho_2Vg$ trong chất lỏng phía dưới (V là thể tích của vật). Do đó
$$A_1 = \rho_1Vgh_1$$ và $A_2 = \rho_2Vgh_2$.

Thay các biểu thức này của $A_1$ và $A_2$ vào phương trình (*) và lưu ý rằng $m = V \cdot \rho$ (ρ là khối lượng riêng của vật), ta được $\rho (h_1 + h_2) = \rho_1h_1 + \rho_2h_2$.

⟦folio 42⟧

Suy ra
$$\rho = \frac{\rho_1 h_1 + \rho_2 h_2}{h_1 + h_2}.$$

Lời giải đúng được V. Kalintsev ở Moskva, Yu. Polonsky ở Zelenodolsk, CHXHCNXV Tatar và các bạn đọc khác gửi đến.

Tuy nhiên, đa số bạn đọc đã giải bài toán bằng một cách phức tạp hơn.

Có hai lực tác dụng lên một vật chuyển động trong chất lỏng: trọng lực, bằng $mg = \rho Vg$, và lực đẩy Ác-si-mét (bằng $F_1 = \rho_1 Vg$ khi vật chuyển động trong chất lỏng có khối lượng riêng $\rho_1$, và $F_2 = \rho_2 Vg$ khi nó chuyển động trong chất lỏng có khối lượng riêng $\rho_2$).

Vì vật có dạng thuôn dòng, các lực tác dụng lên nó trong khi chuyển động trong mỗi chất lỏng không thay đổi. Do đó, vật chuyển động nhanh dần đều. Viết phương trình chuyển động của vật. Trong chất lỏng phía trên: $mg - F_1 = ma_1$ (gia tốc hướng xuống), trong chất lỏng phía dưới: $F_2 - mg = ma_2$ (gia tốc hướng lên). Từ các phương trình này, ta thấy rằng trong chất lỏng có khối lượng riêng $\rho_1$ vật chuyển động với gia tốc $a_1 = g \frac{\rho - \rho_1}{\rho}$, còn trong chất lỏng có khối lượng riêng $\rho_2 - c$ với gia tốc $a_2 = g \frac{\rho_2 - \rho}{\rho}$.

Đi qua chất lỏng thứ nhất, vật sẽ đạt vận tốc $V_0 = a_1 t_1$, trong đó $t_1$ là thời gian chuyển động. Thời gian này có thể tìm từ phương trình động học $h_1 = \frac{a_1 t_1^2}{2}$. Do đó $V_0 = \sqrt{2 a_1 h_1}$. Với vận tốc đó, vật bắt đầu chuyển động trong chất lỏng phía dưới. Vì vận tốc của vật ở cuối chuyển động phải bằng không, nên $V_0 - at_2 = 0$, trong đó $t_2$ là thời gian chuyển động của vật trong chất lỏng thứ hai.

Từ đó $t_2 = \frac{V_0}{a_2}$. Trong thời gian này vật đi được trong chất lỏng thứ hai quãng đường $h_2$. Do đó $h_2 = V_0 t_2 - \frac{a_2 t_2^2}{2}$.

Thay vào phương trình cuối các biểu thức của $V_0$, $a_2$ và $t_2$, ta được
$$h_2 = \frac{V_0^2}{a_2} - \frac{1}{2} \frac{V_0^2}{a_2} = \frac{1}{2} \frac{V_0^2}{a_2} = \frac{a_1 h_1}{a_2}.$$

⟦folio 43⟧

Nó bằng 7,5 ôm. Vì vậy qua nguồn có dòng điện $I_0 = \frac{30 \, \theta}{7,5 \, \omega} = 4 \, a$.

Dòng điện đi qua nguồn bằng tổng của dòng điện đi qua ampe kế và dòng điện $I_1$ đi qua điện trở $R_1$. Hãy tìm dòng điện $I_1$.

Tại điểm $A$, dòng điện $I_0$ chia đều giữa nhánh trên và nhánh dưới của mạch. Vì vậy, qua điện trở $R_2$ có dòng điện $I_2$ bằng 2$a$. Tại điểm $B$, dòng điện này lại chia đều giữa các điện trở giống nhau $R_1$ và $R_3$. Vì vậy, qua điện trở $R_1$ có dòng điện 1$a$. Bây giờ có thể tìm dòng điện đi qua ampe kế. Nó bằng $I_0-I_1=3a$.

H55

Hãy ước tính tên bay lên độ cao $H$ khi được bắn thẳng đứng lên từ một chiếc cung trẻ em. Khối lượng của tên $m=20 \, \text{г}$, chiều dài dây cung $AB=1 \, \text{м}$. Dây cung được kéo ra một đoạn $h_0=5 \, \text{см}$. Coi lực căng dây cung không đổi và bằng 250 $\text{н}$.

Năng lượng mà tên nhận được khi bắn bằng công của lực tác dụng lên tên từ phía dây cung. Lực này, hiển nhiên, bằng hợp lực $F$ của các lực căng $T$ của dây cung (hình 11). Nếu gọi góc tạo bởi dây cung tại các điểm $A$ và $B$ với đường $AB$ là $\alpha$, thì dễ thấy rằng $F=2T\sin \alpha$. Như vậy, lực tác dụng lên tên phụ thuộc vào mức độ kéo dây cung. Vì dây cung được kéo ra một khoảng nhỏ so với chiều dài của nó, nên góc $\alpha$ nhỏ, tức là $\sin \alpha \approx tg\alpha \approx \alpha$. Do đó $F=2T\alpha$.

Vì $tg\alpha = \frac{h}{AB}$ ($h$ — độ võng của dây cung), nên

$$F = 4T \frac{h}{AB}.$$

Như vậy, lực tác dụng lên mũi tên tỉ lệ với $h$ (hình 12).

Không khó tìm công của lực này. Nó bằng diện tích hình giữa

⟦folio 44⟧

Hình 13.

lý thuyết sơ cấp về sự bay và sóng trên nước” trong “Kvant” số 5 năm 1970. Hành vi của lá cờ được giải thích hoàn toàn giống như sự hình thành sóng trên nước.

Giả sử ở một chỗ nào đó lá cờ hơi bị uốn cong (hình 13). Trong trường hợp này, ở phía trên, khi dòng khí chảy quanh chỗ lồi, vận tốc gió lớn hơn, còn ở phía dưới, trong vùng lõm của lá cờ — nhỏ hơn vận tốc gió ở xa lá cờ. Từ định luật Bernoulli suy ra rằng áp suất không khí tại điểm A lớn hơn áp suất tại điểm B. Vì vậy, sự hình thành chỗ lồi phải tăng lên. Ngoài ra, vì do sự tách dòng phía sau chỗ lồi, áp suất phía sau nó nhỏ hơn áp suất phía trước chỗ lồi, chỗ lồi này sẽ dịch chuyển về phía cuối lá cờ. Như vậy, chỗ lõm ngẫu nhiên hình thành trên lá cờ sẽ tăng lên. Nếu còn tính đến rằng nhờ sự tách dòng khi dòng khí chảy quanh ngay cả một lá cờ phẳng trong gió đều, áp suất ở các phía khác nhau của lá cờ có thể khác nhau và vì thế các chỗ uốn nhỏ của bề mặt sẽ dễ hình thành, thì sẽ hiểu được vì sao lá cờ “phấp phới” trong gió.

Ф57

Hai quả cầu giống nhau, nối với nhau bằng một lò xo không trọng lượng, chuyển động trên sàn ngang nhẵn với cùng vận tốc vuông góc với bức tường thẳng đứng. Hãy mô tả sự va chạm của hệ với tường xảy ra như thế nào. Các quả cầu sẽ chuyển động thế nào sau va chạm? Va chạm của quả cầu với tường là đàn hồi tuyệt đối, thời gian va chạm nhỏ không đáng kể so với chu kì dao động của các quả cầu trên lò xo.

Vì vận tốc của các quả cầu lúc đầu như nhau và không đổi, nên lò xo không biến dạng. Thật vậy, nếu không thì lên mỗi quả cầu sẽ tác dụng một lực từ phía lò xo, truyền cho nó gia tốc, và vận tốc của quả cầu sẽ thay đổi theo thời gian. Sau khi quả cầu thứ nhất va vào tường, vận tốc của nó đổi sang hướng ngược lại. Các quả cầu bắt đầu chuyển động về phía nhau với các vận tốc có cùng độ lớn (xem hình 14), lò xo bị nén. Động năng của các quả cầu chuyển thành thế năng biến dạng của lò xo. Sau đó lò xo bắt đầu duỗi ra, truyền cho các quả cầu những vận tốc có cùng độ lớn và ngược chiều. Khi đó, cũng như trong lúc lò xo bị nén, khối tâm của hệ đứng yên đối với tường — không có lực ngang nào tác dụng lên hệ. Từ định luật bảo toàn năng lượng suy ra rằng tại thời điểm quả cầu bên phải va vào tường, độ lớn vận tốc của các quả cầu bằng vận tốc ban đầu của hệ. Sau va chạm của quả cầu với tường, vận tốc của nó lại đổi sang hướng ngược lại và các quả cầu chuyển động ra xa tường với cùng vận tốc. Vì vào thời điểm quả cầu va vào tường lò xo không biến dạng, nên nó cũng không biến dạng trong chuyển động tiếp theo của hệ.

Ф58

Trong từ trường, từ một độ cao lớn rơi xuống một vòng có đường kính $d$ và điện trở $R$. Mặt phẳng của vòng luôn nằm ngang. Hãy tìm vận tốc ổn định của vòng rơi, nếu cảm ứng từ của trường thay đổi theo độ cao theo quy luật

$$B = B_0 (1 + \alpha H).$$

Lực tác dụng lên vòng trong từ trường tỉ lệ với dòng điện chạy qua vòng, dòng điện tỉ lệ với suất điện động cảm ứng sinh ra trong vòng khi nó chuyển động, còn suất điện động cảm ứng, đến lượt nó, tỉ lệ với tốc độ biến thiên của từ thông xuyên qua mặt phẳng của vòng, và do đó tỉ lệ với tốc độ của vòng. Vì vậy, tại một tốc độ chuyển động nào đó của vòng, lực tác dụng lên nó trong từ trường trở nên bằng trọng lực. Tốc độ này chính là tốc độ chuyển động ổn định của vòng.

Vì khi vòng chuyển động, động năng của nó không thay đổi, nên độ biến thiên thế năng phải bằng tổn hao nhiệt trong vòng.

Gọi tốc độ của vòng là $v$. Suất điện động cảm ứng sinh ra trong vòng khi nó chuyển động, về độ lớn bằng

$$E = k \frac{\Delta \Phi}{\Delta t},$$

trong đó $\Phi$ là từ thông xuyên qua vòng, còn $k$ là hệ số tỉ lệ.

$$\Phi = \frac{\pi d^2}{4} B = \frac{\pi d^2}{4} B_0 (1 + \alpha H),$$

$$\frac{\Delta \Phi}{\Delta t} = \frac{\pi d^2}{4} B_0 \alpha \frac{\Delta H}{\Delta t}.$$

Nhưng $\frac{\Delta H}{\Delta t} = v$, do đó

$$E = k \frac{\pi d^2}{4} B_0 \alpha v$$

và qua vòng có dòng điện

$$I = \frac{E}{R} = \frac{k \pi d^2 B_0 \alpha v}{4 R}.$$

Bây giờ hãy viết định luật bảo toàn năng lượng. Gọi khối lượng của vòng là $m$. Trong thời gian $t$, trong vòng tỏa ra nhiệt lượng bằng $I^2 Rt$. Nếu trong thời gian đó vòng hạ xuống một độ cao $h$, thì

$$mgh = I^2 Rt.$$

Vì $\frac{h}{t} = v$, nên

$$mgv = I^2 R,$$

$$mgv = \frac{k^2 \pi^2 d^4 B_0^2 \alpha^2 v^2}{16 R}.$$

Từ đây

$$v = \frac{16 Rmg}{k^2 \pi^2 d^4 B_0^2 \alpha^2}.$$

I. Sh. Slovodetsky
