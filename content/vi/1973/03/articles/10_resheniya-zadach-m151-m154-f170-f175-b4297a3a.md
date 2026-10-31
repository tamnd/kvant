---
id: 1973-3-resheniya-zadach-m151-m154-f170-f175-b4297a3a
issue: kvant_1973_3
year: 1973
number: "3"
title: Lời giải bài toán M151—M154; F170—F175
rubric: zadachnik-kvanta
rubric_sub: Задачник «Кванта»
page_first: 39
page_last: 56
page_labels: 37, 38, 39, 40, 41, 43, 45, 46, 47, 48, 49, 51, 53, 54
tag: IO8C
lang: vi
source: kvant_digital
extraction: vision
content_sha256: 878e4c3a9d0a87d6df90e88272a57c06c114226788016b9e8776bab33a62e7c1
prompt_sha256: draft-1
translated_from: content/ru/1973/03/articles/10_resheniya-zadach-m151-m154-f170-f175-b4297a3a.md
source_content_sha256: 6049be7985fbc6e1d672eb567d5228cea02028bdedc9fc65ff3ed4315fdd5817
translation_model: draft
translation_run: vi-draft-2026-10-31
translation_quality: draft
---

⟦folio 37⟧

Lời giải bài toán

M151—M154; F170—F175

M151. Chúng tôi chia mỗi trong số chín số nguyên tố thành hai hình tứ giác, diện tích của chúng theo tỷ lệ 2:3. Chứng minh rằng có ít nhất ba trong số chín số nguyên tố đó đi qua cùng một điểm.

Nếu một đường thẳng cắt hai cạnh liền kề của một hình vuông thì rõ ràng nó sẽ cắt hình vuông đó thành một hình tam giác và một hình thứ năm. Nhưng theo điều kiện của mỗi trong số 9 số nguyên tố, hình vuông được cắt thành hình tứ giác. Do đó, một đường thẳng như vậy cắt hai cạnh đối diện của hình vuông, nghĩa là nó chia hình vuông thành hai hình thang (hoặc hai hình chữ nhật), đáy của chúng nằm trên các cạnh của hình vuông và chiều cao bằng cạnh của hình vuông. Rõ ràng là đường thẳng chia “đường giữa” của hình vuông theo tỷ lệ 2:3 (Hình 1), vì tỷ số diện tích của các hình thang này bằng tỷ số giữa các đường giữa của chúng (nằm trên đường giữa của hình vuông).

Trên đường giữa của hình vuông có hai điểm chia nó theo tỷ lệ 2:3. Nhìn vào hai cạnh đối diện còn lại của hình vuông, chúng ta sẽ tìm thấy thêm hai điểm nằm trên đường thẳng ở giữa song song với chúng.

Kết quả là, chúng ta nhận được rằng mỗi điểm trong số 9 điểm dữ liệu đều đi qua một trong 4 điểm được chỉ định (Hình 2).

Tất nhiên, có ít nhất ba số nguyên đi qua một trong những điểm này. Thật vậy, nếu không có nhiều hơn hai số nguyên tố đi qua mỗi điểm thì tổng cộng sẽ không có nhiều hơn 2,4 = 8 số nguyên tố, điều này mâu thuẫn với các điều kiện.

Người đọc chỉ ra một sự khái quát hóa tự nhiên bài toán: thay vì hình vuông, ta xét một 2n-giác có đối diện

Hình 1. Hình 2.

các cạnh đối diện là các đường thẳng song song, mỗi cạnh chia 2n giác này thành hai (n + 2)-giác có diện tích cố định.

Lưu ý rằng nếu hai cạnh của một đa giác không song song thì các đường thẳng, mỗi đường thẳng cắt các cạnh này và cắt mặt phẳng đã cho, sẽ không còn đi qua một điểm (chứng minh điều đó!), mà sẽ chạm vào một hyperbol nào đó.

B. M. Ivlev

M152. Cho a, b, m, n là các số tự nhiên và a nguyên tố cùng nhau với b và a > 1. Chứng minh rằng nếu a^m + b^m chia hết cho a^n + b^n thì m chia hết cho n.

Hóa ra câu bài toán có thể được thay thế bằng một câu chính xác hơn. Chúng ta sẽ chứng minh không chỉ m chia hết cho n, nghĩa là m = kn, trong đó k là số nguyên nào đó, mà k nhất thiết phải là số lẻ. Chúng ta sẽ chia chứng minh thành ba phần.

1°. Cho m = kn, trong đó k là số lẻ. Khi đó a^m + b^m được chia cho a^n + b^n.

2°. Cho m = kn + r, trong đó k là số lẻ và 0 < r < n. Khi đó a^m + b^m không chia hết cho a^n + b^n.

3°. Cho m = ln + r, trong đó l là số lẻ và 0 ≤ r < n. Khi đó a^m + b^m không chia hết cho a^n + b^n.

Lưu ý rằng bằng cách chứng minh 1°, 2°, 3°, chúng ta sẽ chứng minh được nhiều hơn những điều nói chung, cụ thể là: đối với polychoba a^m + b^m chia hết cho a^n + b^n thì điều cần và đủ là m bằng kn, trong đó k là số lẻ. Trong chứng minh 2° và 3° chúng ta sẽ sử dụng tính chất a và b là nguyên tố cùng nhau, nhưng trong chứng minh 1° thì không.

Chứng minh 1°. Cho c và d là số nguyên tùy ý. Khi đó c^k + d^k, trong đó k > 0 là số lẻ, chia hết cho c + d. (Do đó, với c = a^n và d = b^n, chúng ta nhận được 1°.) Thật vậy, như dễ thấy, đối với k lẻ

c^k + d^k = (c + d) (c^{k-1} - c^{k-2} d + ... - cd^{k-2} + d^{k-1}).

Chứng minh 2°. Hãy viết a^m + b^m ở dạng a^{kn+r} + b^{kn+r} = a^r (a^{kn} + b^{kn}) + b^{kn} (b^r - a^r).

Theo 1°, số hạng thứ nhất chia hết cho a^n + b^n, nhưng số hạng thứ hai không chia hết cho a^n + b^n, vì b^{kn} nguyên tố cùng nhau với a^n + b^n và 0 < |b^r - a^r| < a^n + b^n. Do đó, tổng không chia hết cho a^n + b^n.

Chứng minh 3°. Nếu l là số chẵn thì k = l - 1 là số lẻ. Hãy viết a^m + b^m dưới dạng a^{ln+r} + b^{ln+r} = a^{kn+r} (a^{kn} + b^{kn}) + b^{kn+r} (b^r - a^r).

Hai số hạng đầu tiên chia hết cho a^n + b^n, và số hạng cuối cùng, như trên, không chia hết cho

⟦folio 38⟧

đổ. Thật vậy, $b^{kn}a^n$ nguyên tố cùng nhau với $a^n + b^n$ và $0 < b^r + a^r < a^n + b^n$.

Hãy tự đưa ra ví dụ chứng minh rằng nếu không có giả định nguyên tố chung của $a$ và $b$ thì các phát biểu $2^\circ$ và $3^\circ$ là sai.

V. L. Gutenmacher

**M153. Hai zerraim tới zerra tiếp theo. Chúng tôi gọi một số là một số và số kia chúng tôi chèn nó, theo quyết định của chúng tôi, cùng với một trong các dấu hoa thị trong phần khác biệt sau:**

$$\begin{array}{c}
* \quad * \\
- \quad * \quad *
\end{array}$$

Sau đó, chúng ta gọi số đầu tiên là một số khác và poppy dallee 8 lần cho đến khi tất cả các dấu hoa thị được thay thế bằng số. Người gọi các con số cố gắng đảm bảo rằng sự khác biệt càng lớn càng tốt, và thứ hai - làm cho nó càng nhỏ càng tốt. Chứng minh rằng a) người thứ hai có thể xét các số sao cho hiệu cala không quá 4000, bất kể người thứ nhất gọi số nào;
b) Người thứ nhất có thể gọi tên các số sao cho hiệu không nhỏ hơn 4000, bất kể người thứ hai coi số đó ở đâu.

Chúng tôi trình bày lời giải cho trường hợp chung khi mỗi dòng không chứa 4 mà chứa dấu hoa thị $n$. Hãy để chúng tôi chứng minh rằng nếu có đối thủ trong trò chơi thì hiệu số sẽ bằng $4.10^{n-1}$.

a) Chiến lược cho trò chơi thứ hai.

Nếu số đầu tiên được người chơi thứ nhất gọi là 4 hoặc ít hơn thì người chơi thứ hai sẽ ghép số đó lại với chữ số cao nhất của số bị trừ. Sau đó, ngay khi người chơi thứ nhất gọi tên một số khác 0, người chơi thứ hai sẽ điền chữ số cao nhất của số bị trừ. Sự khác biệt hóa ra không quá $499 \ldots 9 - 100 \ldots 0 < 4.10^{n-1}$. Nếu người chơi đầu tiên, bắt đầu từ nước đi thứ hai, gọi 0 mỗi lần, thì chênh lệch cũng sẽ nhỏ hơn hoặc bằng $4.10^{n-1}$.

Nếu người chơi đầu tiên bắt đầu với số 5, 6, 7, 8 hoặc 9, thì người thứ hai đặt nó vào vị trí của chữ số có nghĩa nhất của số bị trừ, sau đó lấy chữ số có nghĩa nhất của số trừ của số được đặt tên đầu tiên, ngoài 9. Hơn nữa, nếu tất cả các số tiếp theo là số chín thì chênh lệch cũng sẽ không vượt quá $4.10^{n-1}$.

b) Chiến lược cho ván đầu tiên.

Miễn là các chữ số có ý nghĩa nhất của số bị trừ và số bị trừ vẫn còn trống, người chơi đầu tiên gọi các số 4 và 5. Bắt đầu từ thời điểm người chơi thứ hai điền vào một trong hai chữ số cao nhất và cho đến khi kết thúc trò chơi, người chơi đầu tiên gọi 0 nếu các chữ số bằng nhau của số bị trừ được điền và 9 nếu không. Vẫn còn phải làm rõ trong trường hợp nào người chơi đầu tiên gọi số 4 và trong trường hợp nào - số 5.

Trước khi người chơi đầu tiên thực hiện nước đi tiếp theo, chúng tôi theo dõi các số 0 ở tất cả các chữ số chưa điền. Nếu sau đó hiệu số không âm, anh ta công bố số 4, nhưng nếu hiệu số âm - số 5.

Hãy để chúng tôi chứng minh rằng chiến lược được mô tả của người chơi đầu tiên cho phép anh ta tạo ra sự khác biệt không dưới $4.10^{n-1}$.

Nếu chữ số có nghĩa nhất của số bị trừ bị chiếm bởi chữ số 4 thì chữ số có nghĩa nhất của số bị trừ sẽ là chữ số 9:

$$\underbrace{900 \ldots 0}_{n} - \underbrace{499 \ldots 9}_{n} > 4.10^{n-1}.$$

Nếu chữ số có nghĩa nhất của số bị trừ được điền bằng chữ số 5 thì chữ số có nghĩa nhất của số bị trừ sẽ được điền bằng chữ số 0, và

$$\underbrace{500 \ldots 0}_{n} - \underbrace{099 \ldots 9}_{n} > 4.10^{n-1}.$$

Giả sử rằng người chơi đầu tiên gọi số 4 và người chơi thứ hai điền chữ số có ý nghĩa nhất của số trừ. Trước nước đi này, sự chênh lệch không âm, sau nước đi, nó tăng thêm $4.10^{n-1}$ và không thay đổi nữa, vì đối với tất cả các nước đi tiếp theo, người chơi đầu tiên gọi 0.

Vẫn còn phải xem xét trường hợp khi người chơi đầu tiên đặt tên cho số 5 và người chơi thứ hai điền chữ số cao nhất của số phụ. Chia các số, được gọi là người chơi đầu tiên, thành chuỗi, kết hợp các số giống hệt nhau thành một chuỗi và ghép chúng thành một hàng. Giả sử rằng người chơi thứ hai không đặt các số giống hệt nhau cạnh nhau, nếu không chúng có thể bị gạch bỏ và không được xem xét trong lý luận tiếp theo. Bây giờ chúng ta hãy chứng minh rằng mỗi dãy số bốn đều kết thúc như thế này:

$$\begin{array}{c}
* \ldots * a_m a_{m+1} \ldots a_n \\
* \ldots * 4 b_m b_{m+1} \ldots b_n.
\end{array}$$

Việc loạt phim đầu tiên kết thúc như thế này thật đáng thất vọng. Hãy để chuỗi bốn thứ thứ s kết thúc theo cách này. Hãy chứng minh rằng chuỗi s + 1 sẽ kết thúc theo cách tương tự. Sau loạt hiệp thứ 4, một loạt hiệp 5 nhường chỗ. Chúng ta hãy nhìn vào năm số ngoài cùng bên trái của loạt bài này (hãy nhớ rằng chúng tôi không xem xét các số bị gạch bỏ!). Rõ ràng là nó thuộc loại trừ trong loại có số nhỏ hơn m và bên dưới nó có dấu hoa thị hoặc thuộc loại m - loại thứ nhất, bốn. Năm người này là người cuối cùng trong loạt bài của họ. Thật vậy, sau khi nó được thiết lập, sự khác biệt sẽ trở nên tích cực và người đầu tiên sẽ bắt đầu công bố số bốn. Nếu bây giờ chúng ta xem xét bộ tứ ngoài cùng bên trái của dãy s + 1, thì bằng cách sử dụng lý luận tương tự, chúng ta có thể tin chắc rằng nó nằm ở vị trí bị trừ, hơn thế nữa

⟦folio 39⟧

gần với con đầu tiên hơn con chim cuối cùng trong loạt phim trước, có một dấu hoa thị phía trên nó và nó là con cuối cùng trong loạt phim của nó.

Pozny sau khi bộ tứ cuối cùng được đặt tên, sự ngưng tụ sau sẽ phát sinh

$$* * * \dots * * a'_{k+1} \dots a'_n$$
$$* * * \dots * 4 b'_{k+1} \dots b'_n.$$

Sau đó, người chơi đầu tiên đặt tên cho số 5 một hoặc nhiều lần và vì sau mỗi lần di chuyển của mình, số trừ vẫn nhỏ hơn số bị trừ (khi thay thế dấu hoa thị bằng số 0), tình huống sau đã nảy sinh trước khi công bố số chín

$$* a_2 a_3 \dots a_{k-1} a_k a'_{k+1} \dots a'_n$$
$$5 a_2' a_3' \dots a'_{k-1} 4 b'_{k+1} \dots b'_n$$

trong đó đối với mỗi $i=2, 3, \dots, k-1$ $a_i=a'_i$ hoặc $a'_i=5$ và $a_i$ là dấu hoa thị và sự khác biệt của các số

$$a_2 a_3 \dots a_{k-1} a_k$$
$$a_2' a_3' \dots a'_{k-1} 4$$

tiêu cực. Thật vậy, nếu nó dương, thì trước khi công bố số chín, người chơi đầu tiên sẽ thông báo số bốn, nhưng nó không thể bằng 0, vì $a_k$ là dấu hoa thị hoặc dấu pter. Mặt khác, rõ ràng là nếu đối với $i < k$ $a_i$ và $a'_i$ không phải là dấu hoa thị thì $a_i=a'_i$; thực sự, chúng trùng hợp vào thời điểm bốn người cuối cùng được công bố. Vì vậy, đối với trận không chung kết, chênh lệch không nhỏ hơn $4 \cdot 10^{n-1} + 3 \cdot 10^{n-j} > 4 \cdot 10^{n-1}$. Bài toán lời giải.

Yu. I. Nonin

M154. Có 50 đoạn thẳng nằm trên một đường thẳng. Chứng minh rằng ít nhất một trong các khẳng định sau là đúng:
a) chênh lệch cuối cùng không nhỏ hơn $4 \cdot 10^{n-1} + 3 \cdot 10^{n-j} > 4 \cdot 10^{n-1}$.
b) có một đoạn lớn hơn, không nhiều hơn một số, không nhiều hơn một số.

Có khả năng là nhiều định lý khác nhau có thể được đưa ra, một trường hợp hoặc hệ quả đặc biệt của nó là phát biểu về bài toán này. Chúng tôi chỉ chỉ ra một trong số họ ở đây.

Định lý. Hãy để một hệ thống các phân đoạn tùy ý được đưa ra trên một dòng. Chúng ta hãy biểu thị bằng $M$ số điểm nhỏ nhất trên một đường thẳng sao cho mỗi đoạn của hệ chứa một trong các điểm này; đến $m$ là số lượng lớn nhất các phân đoạn không phải cuối cùng có thể được chọn từ các hệ thống lớn nhất. Sau đó $M = m$.

Bất đẳng thức $M \geq m$ rất hiển nhiên: rõ ràng là nếu trong một hệ thống có $m$ các phân đoạn rời nhau theo cặp thì không thể có ít hơn $m$ điểm, một trong số đó sẽ chứa từng phân đoạn của hệ thống (sau đây, ít nhất $m$ điểm phải được đặt trên $m$ các phân đoạn đã chọn). Việc còn lại là chứng minh bất đẳng thức $M \leq m$.

Để làm được điều này, chỉ cần chứng minh rằng từ hệ thống luôn có thể chọn một số điểm không hữu hạn $A_1$ và các đoạn giao nhau $A_2$, ..., $A_k$ và trong mỗi đoạn đó chọn các điểm $A_1$, $A_2$, ..., $A_k$ câu châm ngôn từ các đoạn của hệ thống chứa một trong các đoạn này $k$ điểm.

Nếu chúng ta tìm được các phân đoạn $k$ như vậy thì rõ ràng là $M \leq k$ và $k \leq m$, do đó $M \leq m$. (Trên thực tế, thì bắt buộc $M = k = m$ - suy cho cùng, bất đẳng thức $M < m$, như chúng ta đã thấy, là không thể.)

Hãy để chúng tôi chỉ ra cách bạn có thể chọn các phân đoạn và điểm như vậy.

Hãy tưởng tượng rằng đường thẳng nằm ngang trước mặt chúng ta. Chúng ta hãy chọn một đoạn $A_1$ có điểm nằm $A_1$ nằm ở bên phải nhiều hơn so với đầu bên trái của tất cả các đoạn khác. Hãy để chúng tôi xóa khỏi hệ thống tất cả các phân đoạn chứa điểm $A_1$ (cụ thể là $A_1$) *).

Rõ ràng là mỗi đoạn còn lại (nếu có) nằm hoàn toàn ở bên trái của điểm $A_1$ và rõ ràng là không giao nhau với đoạn $A_1$. Các quy trình được mô tả trong đoạn trước một lần nữa được áp dụng cho các phân đoạn còn lại - chúng ta có phân đoạn $A_2$ và điểm $A_2$, sau đó là phân đoạn $A_3$ và $A_3$, v.v. cho đến khi không còn một phân đoạn nào trong hệ thống của chúng ta ở bên trái đầu bên trái $A_k$ của phân đoạn $A_k$. Các phân đoạn $A_1$, $A_2$, ..., $A_k$ và các điểm $A_1$, $A_2$, ..., $A_k$ đáp ứng mọi yêu cầu của chúng tôi. Định lý đã được chứng minh.

Bây giờ chúng ta hãy giải bài toán M154. Hãy để chúng tôi chứng minh rằng từ $(pq+1)$ các đoạn trên một đường thẳng, người ta luôn có thể chọn các đoạn $(p+1)$ có ​​một điểm chung hoặc $(q+1)$ các đoạn rời rạc theo cặp. (Đối với $p=q=7$ đây là tuyên bố bài toán M154.)

Thật vậy, nếu đối với một hệ thống gồm các phân đoạn $(pq+1)$ nhất định, giá trị $M=m$, được thảo luận trong định lý, lớn hơn $q$, thì chúng ta có thể chọn $m \geq q+1$ các phân đoạn không giao nhau và nếu giá trị này không lớn hơn $q$, thì chúng ta có thể chọn một tập hợp $M \leq q$ điểm có điểm chung với mỗi điểm trong số $(pq+1)$ phân đoạn. Sau đó, tất nhiên, một số điểm $M$ này phải chứa ít nhất $(p+1)$ phân đoạn: nếu mỗi điểm chứa không quá $p$ phân đoạn thì tất cả các phân đoạn sẽ không nhiều hơn $Mp \leq pq$.

*) Chúng tôi tin rằng các phân đoạn được thảo luận trong bài toán là “đóng”, nghĩa là chúng chứa các điểm cuối của chúng. Tuy nhiên, phát biểu này, dễ dàng nhận thấy, vẫn đúng đối với các đoạn-khoảng “mở” không chứa điểm cuối của chúng.

⟦folio 40⟧

F170. Trong một plasma đồng nhất có mật độ (số điện tích của mỗi dấu trên một đơn vị thể tích) n, tất cả các electron ban đầu nằm trong lớp phân tử x sẽ trộn theo pháp tuyến với lớp electron ở khoảng cách x. Tìm trường điện tử E trong phần SS (Hình 3).

Chúng ta hãy xem xét hai lớp mỏng có độ dày Δx nằm ở khoảng cách bằng nhau trên các cạnh đối diện của phần SS. Những con voi này có thể được coi là các bản của một tụ điện phẳng có điện tích cùng kích thước nhưng khác nhau. Cường độ trường của các điện tích này có thể được tính bằng công thức

$$E = \frac{Q_{\Delta x}}{\varepsilon_0 s},$$

trong đó $Q_{\Delta x}$ là điện tích của mỗi tấm, s là diện tích của nó.

Như vậy, cường độ trường điện tích của các từ được chọn không phụ thuộc vào khoảng cách giữa các lớp. Nó chỉ được xác định bởi độ lớn của điện tích.

Trong phần SS, cường độ của trường bằng tổng cường độ trường của các cặp từ mỏng tương tự, nghĩa là bằng

$$E_{SS} = \sum \frac{Q_{\Delta x}}{\varepsilon_0 s} = \frac{1}{\varepsilon_0 s} \sum Q_{\Delta x}.$$

Kể từ $\sum Q_{\Delta x} = enxs$

$$E_{SS} = \frac{enxs}{\varepsilon_0 s} = \frac{enx}{\varepsilon_0}.$$

F171. Trên bàn ngang chính có một vòng quay đêm thẳng đứng, bao gồm một thanh không trọng lượng với hai quả bóng nhỏ giống hệt nhau ở hai đầu (Hình 4). Tác động truyền vận tốc v tới quả bóng phía trên theo phương nằm ngang. Ở độ dài tối đa l thì quả bóng phía dưới sẽ lập tức rời khỏi bàn?

Khi quả bóng trên cùng được truyền một tốc độ nằm ngang v, các quả bóng bắt đầu

$$\frac{v^2}{2l} > g,$$

đó là

$$l < \frac{v^2}{2g}$$

Và

$$l_{\max} = \frac{v^2}{2g}.$$

Tôi. Sh. Slobodetsky

F172. Thanh dẫn điện được treo nằm ngang trên hai dây dẫn ánh sáng trong một từ trường thẳng đứng có chỉ thị B = 1 ml (Hình 5). Chiều dài thanh l = 0,2 m, khối lượng m = 10 g, chiều dài dây l₁ = 0,1 m. Một tụ điện có C = 100 μF, được tích điện đến điện áp U = 100 V, được nối với các chốt giữ dây.

a) Xác định góc lắng đọng cực đại của hệ so với vị trí cân bằng sau khi phóng điện của tụ điện, dịch chuyển sao cho sự phóng điện xảy ra trong thời gian rất ngắn.

b) Xác định điện dung của tụ điện C₁,

⟦folio 41⟧

khi phóng điện, hệ sẽ bị lệch một góc $\alpha_1 = 3^\circ$, nếu khi phóng điện một tụ điện có công suất $C_0 = 10$ uF nạp đến điện áp cực đại thì góc đó sẽ lệch một góc $\alpha_0 = 2^\circ$.

a) Khi nối một tụ điện, dòng điện $i$ bắt đầu chạy qua thanh, do đó một lực $F = Bli$ sẽ tác dụng lên thanh, hướng vuông góc với thanh và vectơ $B$.

Độ lớn của dòng điện giảm dần theo thời gian từ giá trị cực đại về 0 nên cường độ dòng điện phụ thuộc vào thời gian.

Vì thời gian $\Delta t$ phóng điện của tụ điện ngắn nên chúng ta có thể giả sử rằng trong thời gian này độ dịch chuyển của thanh khỏi vị trí cân bằng là ngắn và thanh sẽ nhận được một xung lực $P$ theo phương nằm ngang.

Sau khi chia thời gian $\Delta t$ thành các khoảng nhỏ trong đó lực có thể được coi là không đổi, chúng ta viết

$$P = \Sigma F \Delta t = B l \Sigma i \Delta t = B l q$$

Và

$$v = \frac{P}{m} = \frac{B l}{m} q,$$

trong đó $q$ là điện tích truyền qua thanh. Khi tụ điện phóng điện hoàn toàn

$$q = CU.$$

Posetom

$$v = \frac{B l CU}{m}.$$

Góc lệch của hệ so với vị trí cân bằng sẽ được tìm từ định luật bảo toàn năng lượng. Chúng ta hãy đánh đồng các biểu thức về năng lượng tổng cộng của thanh ở vị trí cân bằng và ở độ lệch cực đại của nó (chúng ta sẽ giả sử rằng dây nguồn là cứng):

$$\frac{m v^2}{2} = m g l_1 (1 - \cos \alpha),$$

Ở đâu

$$1 - \cos \alpha = \frac{v^2}{2 g l_1} = \frac{B^2 C^2 U^2 l^2}{2 g l_1 m^2},$$

Nhưng

$$1 - \cos \alpha = 2 \sin^2 \frac{\alpha}{2}$$

Và

$$\alpha = 2 \arcsin \frac{B C U l}{2 m \sqrt{g l_1}} = 2 \arcsin 0, 1 \approx 12^\circ.$$

6) Bởi vì

$$\sin \frac{\alpha_0}{2} = C_0 \frac{B U l}{2 m \sqrt{g l_1}}$$

Và

$$\sin \frac{\alpha_1}{2} = C_1 \frac{B U l}{2 m \sqrt{g l_1}},$$

Cái đó

$$C_1 = C_0 \frac{\sin \frac{\alpha_1}{2}}{\sin \frac{\alpha_0}{2}}.$$

Góc $\alpha_0$ và $\alpha_1$ nhỏ nên

$$\sin \frac{\alpha_0}{2} \approx \frac{\alpha_0}{2} \text{ и } \sin \frac{\alpha_1}{2} = \frac{\alpha_1}{2}.$$

Kết quả là chúng tôi nhận được

$$C_1 = C_0 \frac{\frac{\alpha_1}{2}}{\frac{\alpha_0}{2}} = C_0 \frac{\alpha_1}{\alpha_0} = 15 \text{ мкф.}$$

V. V. Svetozarov

F173. Trong một quả cầu tích điện đồng đều có bán kính $R$ có một hộp hình cầu có bán kính $r$, tâm của nó nằm cách tâm quả bóng một khoảng $a$ (Hình 6). Tìm hướng của điện trường tại các điểm khác nhau trong hộp nếu mật độ điện tích là $\sigma$.

Chúng ta giả sử rằng đầu tiên quả bóng được tích điện đồng đều trong toàn bộ thể tích, sau đó một phần điện tích của nó nằm bên trong hộp bị loại bỏ.

Theo nguyên lý chồng chất, hướng của trường tại một điểm bất kỳ của một quả cầu tích điện đồng nhất bằng tổng vectơ của hướng trường của quả bóng có khoang và hướng của trường điện tích bị loại bỏ khỏi khoang.

Xét một điểm tùy ý $A$ bên trong hộp. Chúng ta biểu thị khoảng cách của nó với tâm hình cầu là $x$ và từ tâm của khoang là $y$. hướng $E_0$ của trường được tạo bởi một quả bóng đặc tại điểm này hướng dọc theo bán kính của quả bóng và có độ lớn bằng nhau

$$E_0 = \frac{4}{3} \pi x \sigma.$$

⟦folio 43⟧

tẩm khí bằng

$$A = P_{cp} \Delta V = \frac{P_1 + P_2}{2} (V_2 - V_1) = \frac{\alpha R}{2} (V_2 + V_1)(V_2 - V_1) = \frac{1}{2} R (T_2 - T_1) = \frac{1}{2} R \Delta T.$$

Thay biểu thức của $\Delta U$ và $A$ vào công thức (*), ta thu được

$$C \Delta T = C_V \Delta T + \frac{1}{2} R \Delta T.$$

Từ đây

$$C = C_V + \frac{1}{2} R.$$

Điều thú vị cần lưu ý là nếu $T \sim V^n$ thì $C = C_V + \frac{1}{n} R$. Những người biết hòa nhập sẽ dễ dàng chứng minh được điều này.

Trong trường hợp 6) $T = \frac{\beta}{V}$ ($\beta$ là một hằng số nào đó). Đó là lý do tại sao

$$PV = RT = \beta \frac{R}{V} \text{ и } P = \beta \frac{R}{V^2},$$

nghĩa là áp suất của một chất khí tỉ lệ nghịch với bình phương thể tích của nó. Để tìm công mà chất khí thực hiện, chúng ta chia khoảng thời gian thay đổi thể tích của nó thành các phần sao cho áp suất tác dụng lên chúng có thể coi là không đổi. Trong mỗi phần này, khí thực hiện công về số bằng diện tích hình chữ nhật ở các cạnh $P_i$ và $\Delta V_i = V_{i+1} - V_i$ (Hình 8). Rõ ràng là công mà khí thực hiện xấp xỉ bằng tổng diện tích của các hình chữ nhật đó:

$$A = \sum \frac{\beta R}{V_i^2} \Delta V_i,$$

hình 8.

Hơn nữa, các phần $\Delta V_i$ càng nhỏ thì tổng được viết tương ứng với lượng công mà khí thực hiện càng chính xác.

Vì $\Delta V_i$ nhỏ và $V_i \approx V_{i+1}$ nhỏ nên chúng ta có thể giả sử rằng $V_i^2 \approx V_i V_{i+1}$. Sau đó

$$A = \sum \frac{\beta R}{V_i V_{i+1}} (V_{i+1} - V_i) = \beta R \Sigma \left( \frac{1}{V_i} - \frac{1}{V_{i+1}} \right) = \beta R \left( \frac{1}{V_A} - \frac{1}{V_1} + \frac{1}{V_1} - \frac{1}{V_2} \right) = \beta R \left( \frac{1}{V_A} - \frac{1}{V_B} \right) = \beta R \cdot \frac{1}{\beta} (T_A - T_B) = -R (T_B - T_A) = -R \Delta T.$$

Thay biểu thức này vào công thức (*), ta thấy rằng

$$C = C_V - R.$$

Quét.

Để xác định công do chất khí thực hiện, có thể sử dụng phương pháp phân tích.

Chúng ta hãy xem xét công chuyển động của một điện tích trong trường nhà máy điện của một điện tích chính xác. Lực tác dụng lên điện tích trong trường này bằng

$$F = \frac{q_1 q_2}{4 \pi \varepsilon_0} \cdot \frac{1}{r^2}.$$

Đối với chuyển vị nhỏ vô hạn $\Delta r$ (khi lực có thể được coi là không đổi), công cơ bản bằng

$$\Delta A = F \Delta r.$$

Tổng công trên phần $(r_2 - r_1)$ bằng

$$A = \frac{q_1 q_2}{4 \pi \varepsilon_0} \left( \frac{1}{r_1} - \frac{1}{r_2} \right).$$

Áp suất khí trong trường hợp 6) bằng

$$P = \frac{\beta R}{V^2},$$

tức là tỉ lệ nghịch với bình phương thể tích.

Công thức cơ bản về sự giãn nở của khí ở phần $\Delta V$ (trong đó áp suất có thể được coi là không đổi) bằng

$$\Delta A = P \Delta V.$$

Theo phân tích với công việc trong lĩnh vực nhà máy điện, tổng công về sự giãn nở của khí từ thể tích $V_1$ đến thể tích $V_2$ bằng

$$A = \beta R \left( \frac{1}{V_1} - \frac{1}{V_2} \right).$$

F175. Lời giải trong số bài toán này có trong bài viết “Sự va chạm của những quả bóng” của G. L. Komkin (trang 19-21).

Tôi. Sh. Slobodetsky

⟦folio 45⟧

đã được thực hiện trong bài kiểm tra viết cuối cùng tại Nhà thi đấu Toruń. Vì bài kiểm tra là về đại số nên họ chủ yếu rút gọn vấn đề thành phương trình vô tỉ lời giải

$$\sqrt{2x^2 - 9} = \sqrt{x^2 - 81} + \sqrt{x^2 - 144},$$

hoặc tới lời giải hệ phương trình chưa biết:

$$\begin{cases}
x^2 - y^2 = 81, \\
x^2 - z^2 = 144, \\
2x^2 - (y + z)^2 = 9.
\end{cases}$$

Dễ dàng nhận thấy rằng cả hai đường dẫn đều yêu cầu một lượng tính toán đáng kể.

Nếu nhìn vào hình, bạn sẽ thấy các tam giác vuông ACD và BCE có các cạnh huyền bằng nhau, các góc nhọn ACD và BEC bằng nhau vì các cạnh của chúng lần lượt vuông góc. Vậy các tam giác này bằng nhau. Vì vậy, sự tương ứng là bằng nhau và chân của họ bằng nhau. Do đó, chiều rộng của đường AB = 12 + 9 = 21 (m) và chiều dài của cầu thang được xác định theo định lý Pythagore.

Sự khác biệt về độ khó lời giải là đáng chú ý!

Một trong những biểu hiện của mong muốn giải bài toán bằng cách sử dụng mẫu là tính toán tất cả các đại lượng có thể sử dụng để tìm ra ẩn số. Điều này hoàn toàn bỏ qua thực tế là không phải tất cả các đại lượng tính toán đều có trong biểu thức cuối cùng.

Ví dụ 3. Các cạnh đáy của một hình tam giác có độ dài là 15 cm, 16 cm và 17 cm. Các gân bên nghiêng với mặt phẳng của đế một góc 45°. Tìm thể tích của paramid.

Theo quy định, công thức dùng để tính thể tích của paramit và diện tích của bazơ thường được gọi là:

$$S = \sqrt{24 \times 9 \times 8 \times 7} = 24 \sqrt{21} (cm^2).$$

Khi đó MO vuông góc với mặt phẳng đáy là điều hợp lý.

Hình 2.

Di chuyển qua tâm của vòng tròn được mô tả gần đáy (Hình 2). Theo đó, chiều cao của paramid bằng bán kính của hình tròn được mô tả xung quanh đáy. Theo công thức nổi tiếng $R = \frac{abc}{4S}$. Có nghĩa,

$$h = \frac{15 \times 16 \times 17}{4 \times 24 \sqrt{21}} = \frac{85}{2 \sqrt{21}} (cm).$$

Cuối cùng,

$$V = \frac{1}{3} \times 24 \sqrt{21} \times \frac{85}{2 \sqrt{21}} = 340 (cm^3).$$

Nhưng nếu bạn không vội tính toán, bạn sẽ nhận được kết quả sau:

$$V = \frac{1}{3} SH = \frac{1}{3} SR = \frac{1}{3} S \cdot \frac{abc}{4S} = \frac{abc}{12}.$$

Vì vậy, việc tính toán $S$ và $H$ hóa ra là dư thừa.

Sau chiến tranh, các trường học của chúng tôi có một bài kiểm tra viết trong đó học sinh tốt nghiệp giải phương trình lập thể bài toán bằng phép đo lượng giác. Sau khi nhận được đáp số ở dạng tổng quát, những người tham gia phải thực hiện một số nghiên cứu và sau đó đưa đáp số “đến một số” với các giá trị tham số được chỉ định.

Sau đó, bản chất của kỳ thi này đã thay đổi, đặc biệt là các phép tính sử dụng bảng đã bị loại trừ. Nhưng mẫu vẫn giữ nguyên: đầu tiên hãy giải bài toán, sau đó khám phá.

Sẽ không làm tổn thương những người tin vào tính chất tất yếu của thứ tự công việc này khi biết rằng có khá nhiều phương trình bài toán không có phương trình lời giải trong bước của bạn

⟦folio 46⟧

học. Hãy nhớ lại một vài trong số bài toán này.

Ví dụ 4. Hai đường cao của một tam giác chia nó thành hai cặp phần bằng nhau. Đặt tên cho các hình tam giác.

Cho tam giác ABC vẽ các đường cao AK và BM cắt nhau tại điểm O thì tam giác được chia thành 4 phần: ABO, AMO, BKO và MOKC. Những cái nào có kích thước bằng nhau? Có ba trường hợp có thể xảy ra ở đây: 1) ABO và BKO; AMO và MOKC; 2) ABO và AMO; BKO và MOKC; 3) ABO và MOKC; AMO và BKO.

Lời giải bắt đầu bằng việc khám phá những khả năng này. Hóa ra hai trường hợp đầu tiên đã bị loại trừ. Chỉ sau đó chúng ta mới tiến tới lời giải bài toán (chứng minh tam giác ABC là đều).

Ví dụ 5. Tên đối tượng là tham số, phát triển cạnh là một đường thẳng đều cạnh a.

Ở đây trước tiên bạn cần tìm hiểu hình dạng của các tham số cơ sở. Vì các góc ở đỉnh của tham số là các góc của một hình ngũ giác đều (mỗi góc bằng 108°) nên có 3 góc như vậy. Do đó, tham số này có dạng hình tam giác.

Bước tiếp theo là đặt vị trí của thước uốn trên mẫu phẳng. Hóa ra một trong số chúng là đường chéo của hình ngũ giác, hai cái còn lại nối hai đầu của đường chéo này và điểm giữa của cạnh song song. Chỉ sau này bạn mới có thể tìm thấy các tính toán.

Như vậy, chúng ta thấy rằng lời giải theo mẫu gây khó khăn cho việc thu được kết quả ban đầu.

Bắt đầu từ mẫu, bạn có thể trở nên thanh lịch lời giải.

Ở đây chúng ta đang phải đối mặt với một vấn đề màu xanh lam. Thông thường, các ứng viên đồng ý rằng việc tưởng tượng ra lý trí lời giải là điều hấp dẫn. Tuy nhiên, họ ngay lập tức tạo ra cơ hội. Theo ý kiến ​​​​của họ, để nó tốt lời giải, bạn cần tưởng tượng việc giải bài toán theo nhiều cách. Và điều này, trong điều kiện thi cử, đòi hỏi rất nhiều thời gian,

mà người nộp đơn không đủ khả năng chi trả.

Nếu đúng như vậy thì câu hỏi làm thế nào để khám phá ra lời giải hợp lý sẽ không được xem xét. May mắn thay, có những khả năng phát hiện những đường dẫn này hoàn toàn khác nhau.

Hợp lý lời giải bài toán phải căn cứ điều kiện vào điều kiện cá nhân. Vai trò quyết định có được không phải bởi những đặc điểm mà trên cơ sở bài toán thuộc về một loại bài tập nhất định, mà bởi những đặc điểm phân biệt nó với lớp này. Đó là sự chú ý đến các giá trị số của các tham số, đến các tính năng cấu hình mở ra các đường dẫn đơn giản lời giải.

Ví dụ 6. Rút gọn biểu thức

$$tg 20^\circ + tg 40^\circ + \sqrt{3} tg 20^\circ \cdot tg 40^\circ.$$

Rõ ràng là - chuyển sang sin và cos. Nó đòi hỏi kiến ​​thức về một số công thức (tổng tiếp tuyến, tổng cosin, hiệu cosin), giá trị của sin và cosin của một góc 60°, cũng như khả năng thực hiện một chuỗi biến đổi không quá ngắn.

Các tính năng của điều kiện là gì? Nó chỉ bao gồm một hàm (tiếp tuyến) của hai góc (20° và 40°), và biểu thức chứa tổng và tích các tiếp tuyến của các góc này. Sự kết hợp này là một phần không thể thiếu của tiếp tuyến của công thức tổng hai góc. Nếu chúng ta thêm vào đó rằng tiếp tuyến của tổng các góc này đã được biết thì rõ ràng là nên sử dụng sự tương ứng cụ thể này. Cách tiếp cận này dẫn đến lời giải sau:

$$tg 20^\circ + tg 40^\circ + \sqrt{3} tg 20^\circ \times tg 40^\circ = \frac{tg 20^\circ + tg 40^\circ}{1 - tg 20^\circ tg 40^\circ} (1 - tg 20^\circ \times tg 40^\circ) + \sqrt{3} tg 20^\circ tg 40^\circ = \sqrt{3} (1 - tg 20^\circ tg 40^\circ) + tg 20^\circ \times tg 40^\circ = \sqrt{3} (1 - tg 20^\circ tg 40^\circ) + tg 20^\circ \times tg 40^\circ) = \sqrt{3}.$$

⟦folio 47⟧

Ví dụ 7. Số lớn nhất có bốn chữ số theo dữ liệu sau: tổng bình phương của các chữ số ở giữa là 13, tổng bình phương của các chữ số ở giữa là 85; Nếu bạn trừ 1089 khỏi số bị loại, bạn sẽ nhận được một số được viết với các số giống nhau theo thứ tự ngược lại.

Thông thường, ba phương trình được thực hiện với bốn ẩn số. Các bất đẳng thức phụ cho phép chúng ta chứng minh rằng hiệu giữa các số cực trị bằng 1. Khi đó bài toán bao gồm lời giải của hai hệ phương trình (cấp hai) với hai ẩn số.

Tuy nhiên, nếu chúng ta tính đến việc các chữ số là số nguyên không âm không vượt quá 9, thì hóa ra các chữ số tận cùng là 2 và 3 (chỉ $2^2 + 3^2 = 13$), còn các chữ số ở giữa là 9 và 2 hoặc 7 và 6. Theo quy ước, chữ số hàng nghìn là chữ số lớn hơn của đơn vị và chữ số hàng trăm là chữ số lớn hơn của hàng chục. Điều này có nghĩa là số được yêu cầu là 3922 hoặc 3762. Xác minh trực tiếp cho thấy chỉ có số thứ hai thỏa mãn điều kiện.

Ví dụ 8: Giải phương trình
$$3\sqrt{x^2 - 9} + 4\sqrt{x^2 - 16} + 5\sqrt{x^2 - 25} = \frac{120}{x}.$$
Nếu bạn giải theo cách thông thường, thì sau khi bình phương các biểu thức phức tạp ba lần, bạn sẽ nhận được phương trình bậc 16:
$$x^{16} - 50x^{14} - 4375x^{12} + 278800x^{10} + 1670600x^8 - 364700000x^6 + 7641610000x^4 - 54468000000x^2 + 129600000000 = 0.$$
Một phương trình như vậy khó có thể nằm trong khả năng của người nộp đơn. Chúng ta không còn nói về thời gian cần thiết để có được phương trình như vậy nữa. Trong trường hợp này, do tính đặc thù của phương trình. Vì vế trái không âm nên vế phải cũng vậy. Vì vậy, $x > 0$.

Khi $x$ tăng, bên trái tăng và bên phải giảm. Do đó, một phương trình chỉ có thể có nhiều nhất một nghiệm thực. Bằng cách thay thế giá trị tối thiểu có thể có $x = 5$, chúng ta đảm bảo rằng cả hai vế của phương trình đều có giá trị bằng nhau. Điều này có nghĩa là không có rễ thực sự nào khác.

Trong một số trường hợp, quy trình lời giải đạt được bằng cách sử dụng lượng kiến ​​thức tổng quát hơn lượng kiến ​​thức mà chương trình cung cấp. Giám khảo có thể kén chọn về những quyết định như vậy; trước đó, họ yêu cầu làm rõ trong bài kiểm tra miệng về cách người nộp đơn biết cách sử dụng một định lý hoặc công thức, liệu anh ta có thể chứng minh điều đó hay không, v.v.

Trong khi đó, không có gì sai với điều này. Trong nhiều năm nay, cái gọi là lớp học tự chọn đã được đưa vào các trường học của chúng ta. Bằng cách tham dự các lớp học như vậy, học sinh đã học được các đặc tính và thư từ vượt xa chương trình giảng dạy thông thường ở trường. Những học sinh được bổ sung kiến ​​thức cũng có thể tìm thấy điểm bất ngờ (theo quan điểm của giám khảo) lời giải trong kỳ thi.

Ví dụ 9. Chứng minh rằng
$$\frac{(x-a)(x-b)(x-c)}{(d-a)(d-b)(d-c)} + \frac{(x-a)(x-b)(x-d)}{(c-a)(c-b)(c-d)} + \frac{(x-a)(x-c)(x-d)}{(b-a)(b-c)(b-d)} + \frac{(x-b)(x-c)(x-d)}{(a-b)(a-c)(a-d)} = 1.$$

Sau khi học trong các lớp tự chọn (không có chứng minh) cái gọi là định lý cơ bản của đại số và các hệ quả của nó, học sinh có thể đề xuất một lập luận như vậy.

Nếu đẳng thức này không phải là hành động hiện tại thì nó là một phương trình. Mức độ của phương trình này đối với $x$ không thể lớn hơn ba. Điều này có nghĩa là phương trình này không thể có nhiều hơn ba nghiệm. Nhưng thật dễ dàng để kiểm tra rằng $x = a$, $x = b$, $x = c$, $x = d$ biến đẳng thức này thành một hành động hiện tại, có nghĩa là

⟦folio 48⟧

những gì đang được xem xét là sự bình đẳng không phải là một phương trình. Vì vậy, đây là một danh tính. Và đây là điều cần phải được chứng minh.

Theo cách tương tự, việc sử dụng định lý Ptolemy, công thức cho hàm số ba, v.v. có thể dẫn đến một lời giải đơn giản. Tuy nhiên, con đường này không thể được coi là con đường chính.

Điều quan trọng là phải nghiên cứu các phương pháp lời giải bài toán và làm quen với các điều kiện nên sử dụng các phương pháp này.

Chúng ta hãy nhớ lại một số trong số họ.

a) Nếu, trong các điều kiện hình học bài toán, dữ liệu và đại lượng cần thiết bị tách biệt thì nên thực hiện các phép biến đổi hình học để đưa các phần tử này lại gần nhau hơn.

Ví dụ 10. Đối với đơn vị BC của tam giác vuông ABC có tổng kamet là m, dựng một hình vuông có tâm O ở bên ngoài tam giác. Tìm khoảng cách AO.

Nếu chúng ta xoay tam giác ABO quanh điểm O một góc 90° thì tam giác này sẽ ở vị trí MCO (Hình 3). Đếm các góc cho thấy các điểm A, C, M cùng nằm trên một đường thẳng. Do đó tam giác AOM là tam giác vuông đều cạnh huyền AM bằng m. Từ đây tìm được khoảng cách cần thiết

$$AO = \frac{m}{V^2}.$$

b) Nếu bạn kết nối các phần tử được yêu cầu và đã cho bằng hình học

Hình 3.

không thể chuyển đổi thì nên xem xét các giá trị sau, có thể có vai trò tương ứng.

Ví dụ 11. Tìm thể tích của bốn paramid đều ngoại tiếp một quả cầu có bán kính r với góc phẳng α ở đỉnh.

Vì không dễ để liên hệ trực tiếp các đại lượng V, r và α, nên chúng tôi xét đến góc lưỡng diện φ ở đáy của paramid (Hình 4). Sau đó

$$a = 2r \text{ctg} \frac{\varphi}{2}; \quad H = r \text{ctg} \frac{\varphi}{2} \text{tg} \varphi;$$

$$V = \frac{1}{3} \cdot 4r^2 \text{ctg}^2 \frac{\varphi}{2} \cdot r \text{ctg} \frac{\varphi}{2} \text{tg} \varphi =$$

$$= \frac{4}{3} r^3 \text{ctg}^3 \frac{\varphi}{2} \text{tg} \varphi =$$

$$= \frac{8r^3}{3 \text{tg}^2 \frac{\varphi}{2} \left(1 - \text{tg}^2 \frac{\varphi}{2}\right)}.$$

Vẫn còn phải tìm mối liên hệ giữa hàm của các góc φ và α. Nếu MO là chiều cao của paramid và ME là trung điểm thì cos φ = $\frac{OE}{ME} = \frac{AE}{ME} = \text{tg} \frac{\alpha}{2}$. Đó là lý do tại sao

$$\text{tg}^2 \frac{\varphi}{2} = \frac{1 - \cos \varphi}{1 + \cos \varphi} = \frac{1 - \text{tg} \frac{\alpha}{2}}{1 + \text{tg} \frac{\alpha}{2}} =$$

$$= \frac{\text{tg} 45^\circ - \text{tg} \frac{\alpha}{2}}{1 + \text{tg} 45^\circ \text{tg} \frac{\alpha}{2}} = \text{tg} \left(45^\circ - \frac{\alpha}{2}\right).$$

⟦folio 49⟧

Phần còn lại đã đơn giản rồi.

Thay vì góc phụ, người ta có thể coi cạnh của đáy của đường thẳng đã biết, và sau đó (bằng cách tìm v) tính cạnh này thông qua r và α.

với dự đoán về khả năng tăng bài toán trong phép tính, thường thuận tiện khi giải ở dạng tổng quát mà không cần tính toán tất cả các đại lượng trung gian.

Điều này đặc biệt áp dụng cho các bài toán về vật quay.

Trong trường hợp gặp khó khăn trong việc tìm kiếm chứng minh của chứng minh, người ta nên tìm một định lý phụ trợ, được cho là được xem xét tốt hơn, đồng thời mô hình có thể đóng vai trò hỗ trợ cho chứng minh đang tìm kiếm.

Ví dụ 12. Chứng minh rằng tổng các cạnh của một đa giác đều lồi (hoặc phần mở rộng của chúng) tính từ điểm do trong.

Hãy thay thế đa giác này bằng một đa giác tương tự - thông thường. Trong trường hợp này, bằng chứng (chúng ta tính diện tích đa giác bằng tổng diện tích của các hình tam giác có chung một đỉnh tại một điểm cho trước) gần như hiển nhiên.

Hãy đặt đa giác này bên trong một đa giác đều sao cho các cạnh tương ứng của đa giác song song. Khi đó người ta sẽ thấy rằng tổng khoảng cách từ một điểm M cho trước đến các cạnh của một đa giác đều khác với tổng khoảng cách đến các cạnh của đa giác đều một lượng không đổi.

Bây giờ thật dễ dàng để thiết lập tính đúng đắn của định lý đang được chứng minh.

Đặc biệt, cách tiếp cận mang tính công thức đối với các bài toán hình học thường được thể hiện ở chỗ học sinh bị hạn chế trong việc xem xét các trường hợp đặc biệt và phân tích không đầy đủ về cấu hình.

Ví dụ 13. Hai đường cao được vẽ từ đỉnh của hình thoi. Khoảng cách giữa các đầu của đầu vào nhỏ hơn đường kính của hình thoi. Xác định các góc của hình thoi.

Mỗi học sinh vẽ đường cao từ đỉnh của góc tù ABC và coi khoảng cách giữa hai đầu của các đường cao này bằng nửa AC. Trong khi đó, theo điều kiện, khoảng cách này có thể bằng một nửa BD, ngoài ra có thể rút ra các đường cao từ đỉnh của góc nhọn của hình thoi. Trong bốn trường hợp có thể xảy ra, chỉ có một trường hợp bị loại trừ ngay lập tức do mâu thuẫn. Trong ba phép tính còn lại được hoàn thành thành công. Đáp số hóa ra là hai: 60° và 120° hoặc 30° và 150°.

Nhiều bài toán thừa nhận lời giải theo nhiều cách. Đôi khi những lời giải này khác nhau một chút về mức độ phức tạp, đôi khi - đáng kể. Theo quy định, bất kỳ học sinh nào cũng có thể tìm được lời giải đủ tốt. Để làm được điều này, bạn cần nghiên cứu kỹ các điều kiện, suy nghĩ xem cách tiếp cận bài toán nào phù hợp nhất với các đặc điểm của điều kiện của nó.

Sự khởi đầu cụ thể từ mẫu, phân tích cụ thể các điều kiện là chìa khóa thành công lời giải bài toán.

Văn học

1. L. M. Lopovok, Raschinalnoe lời giải bài toán, “Narodna Prosveta”, Sofia, 1968.
2. D. Polya, Khám phá toán học, Nauka, M., 1970.
3. S. I. Tumanov, Ponsky lời giải bài toán, “Khai sáng”, M., 1969.

⟦folio 51⟧

tác dụng của hai điện tích không thay đổi khi có điện tích thứ ba. Tuyên bố này làm cơ sở cho nguyên lý chồng chất, cùng với định luật Coulomb, là định luật cơ bản của tĩnh điện.

Thật thuận tiện khi xây dựng nguyên lý chồng chất bằng cách xem xét không phải lực tương tác, mà là điện trường được tạo ra bởi một hệ điện tích: cường độ điện trường được tạo ra bởi một hệ điện tích tại một điểm cho trước là sự chồng chất (nghĩa là tổng) của các trường được tạo ra tại điểm này bởi mỗi điện tích. Cần phải nhớ rằng cường độ trường là một đại lượng vectơ; Cường độ trường phải được cộng về mặt hình học, theo quy tắc cộng vectơ.

Việc sử dụng nguyên lý này để tính toán trường sinh ra bởi một vài điện tích chính xác thường rất đơn giản. Vì vậy, chúng ta sẽ không xem xét các ví dụ thuộc loại này ở đây. Nhưng trong trường hợp điện tích kéo dài (ví dụ: một mặt phẳng tích điện hoặc một số mặt phẳng tích điện), nhiều học sinh sẽ gặp khó khăn. Thông thường những khó khăn này có liên quan đến quan niệm sai lầm rất phổ biến rằng bất kỳ bề mặt kim loại nào cũng che chắn hiện trường.

Trước tiên chúng ta hãy xem xét bài toán với hình học phẳng (một hệ các mặt phẳng tích điện song song). Trường của một mặt phẳng dẫn điện tích đơn là đồng nhất (như nhau ở mọi điểm) và bằng $\frac{\sigma}{2\varepsilon_0}$, trong đó $\sigma$ là mật độ điện tích bề mặt (tức là điện tích trên một đơn vị diện tích), $\varepsilon_0$ là hằng số điện. Cần lưu ý rằng kết quả này chỉ đúng đối với mặt phẳng vô hạn. Đối với một tấm phẳng có kích thước hữu hạn, điều này chỉ đúng ở những khoảng cách nhỏ so với kích thước tuyến tính của tấm. Ở những khoảng cách tương đương với kích thước của tấm, sẽ rất hữu ích khi sử dụng một khoảng cách không đồng nhất, và cuối cùng, ở khoảng cách lớn, trường không thể phân biệt được với trường của một điện tích chính xác. Chúng ta sẽ hạn chế xem xét các trường ở những khoảng cách nhỏ so với kích thước của các tấm.

Bài toán 1. Tìm cường độ trường được tạo bởi hai mặt phẳng tích điện song song. Mật độ điện tích bề mặt trên một trong các mặt phẳng là $\sigma_1$, trên mặt kia là $\sigma_2$.

Trường trong toàn bộ không gian là sự chồng chất của các trường được tạo bởi mỗi mặt phẳng riêng biệt. Do đó, tại bất kỳ điểm nào ở bên trái của mặt phẳng 1 (Hình 1), ngay tại điểm $a$, cường độ trường bằng $E_1 + E_2$ và các đường sức hướng về bên trái (nếu cả hai mặt phẳng đều tích điện dương). Giữa các mặt phẳng (ví dụ: tại điểm $b$) cường độ trường bằng hiệu $E_1 - E_2$. Hướng của trường phụ thuộc vào độ lớn của điện tích $\sigma_1$ và $\sigma_2$. Nếu $\sigma_2 > \sigma_1$, $E_2 > E_1$ và trường tổng $E_b = \frac{\sigma_2 - \sigma_1}{2\varepsilon_0}$ được hướng sang trái. Ở bên phải mặt phẳng 2, cường độ trường cũng bằng $E_1 + E_2$, như tại điểm $a$, nhưng các đường sức trường hướng về bên phải.

Bây giờ chúng ta hãy xem xét một vài dịch vụ riêng tư:

1. Mật độ điện tích bề mặt trên cả hai mặt phẳng là như nhau: $\sigma_1 = \sigma_2 = \sigma$. Trong trường hợp này, $E_1 = E_2$ và tổng trường giữa các mặt phẳng bằng 0 (Hình 2), còn ở bên trái và bên phải của mặt phẳng, trường bằng $E_1 + E_2 = \frac{\sigma}{\varepsilon_0}$.

2. Mật độ điện tích trên mặt phẳng có giá trị giống nhau nhưng có

⟦folio 53⟧

Như vậy, tấm 2 không tích điện giống như một tụ điện phẳng: toàn bộ trường được tạo ra bởi các điện tích cảm ứng có dấu khác nhau $\sigma_2$ và $\sigma_2^*$ chứa các bản bên trong. Ở mọi nơi bên ngoài tấm 2, hiệu ứng đều giống như không có nó, nghĩa là nó chỉ được tạo ra bởi tấm tích điện 1.

Bài toán 3. Một tấm kim loại có điện tích Q được đưa vào khoảng trống giữa các bản của một tụ điện phẳng không tích điện, sao cho các tổ chức $l_1$ và $l_2$ dịch chuyển giữa bản và các bản của tụ điện (Hình 6). Diện tích của các bản bằng nhau và bằng S. Xác định hiệu điện thế giữa các bản của tụ điện.

Vì các bản tụ điện không được tích điện và chỉ xuất hiện điện tích cảm ứng nên chúng không tạo ra điện trường bên ngoài. Trường trong các khoảng trống chỉ được tạo ra bởi tấm tích điện. Điện áp của trường này

$$E = \frac{Q}{2\epsilon_0 S}.$$

Hiệu điện thế giữa bản này và bản bên trái của tụ điện là

$$\varphi_{01} = E l_1,$$

và giữa tấm và lớp lót bên phải -

$$\varphi_{02} = E l_2.$$

Do đó, hiệu điện thế giữa các bản bằng

$$\varphi_{12} = E (l_1 - l_2) = \frac{Q}{2\epsilon_0 S} (l_1 - l_2).$$

Bây giờ, hãy đặt một số bài toán với các trường không còn phẳng mà là hình cầu.

Bài toán 4. Quy trình của Cavendits, được đề cập ở phần đầu chỉ số, bao gồm việc thay đổi điện trường của quả cầu kim loại tích điện bên trong. Hiển thị cho người dùng chiếc cacoon của Coulomb và số lượng chủ quyền trên đó

⟦folio 54⟧

sự lựa chọn của chúng ta sẽ công bằng, chúng ta nhận được, sử dụng nguyên lý chồng chất, rằng tổng trường được tạo bởi toàn bộ hình cầu tại điểm A bằng 0. Nhưng điểm A được chọn hoàn toàn tùy ý. Điều này có nghĩa là sau bất kỳ điểm nào bên trong một quả cầu tích điện đều thì nó bằng 0.

Bài tập 5. Một điện tích chính xác Q được đặt trong mạch điện của một quả cầu kim loại. Xác định điện trường bên trong và bên ngoài quả cầu nếu vỏ: a) không tích điện; b) được thay thế.

a) Trên bề mặt bên trong và bên ngoài của một vật hình cầu, các điện tích sẽ được cảm ứng, cùng độ lớn và khác nhau về dấu (toàn bộ quả cầu không nhiễm điện). Từ các báo cáo về tính đối xứng cầu, rõ ràng là các điện tích cảm ứng được phân bố đều trên các quả cầu. Các điện tích này phải sao cho tổng trường trong dây dẫn bằng 0 (Hình 8). Theo nguyên lý chồng chất, trường nằm ở bất kỳ điểm nào của lớp vỏ (hình cầu bên ngoài, như sau từ lời giải bài toán 4, trường không được tạo ra bên trong chính nó). Trường của một quả cầu tích điện đều ở bên ngoài giống như trường của một điện tích chính xác đặt ở giữa; do đó, điều kiện bù trường tại điểm a sẽ được thỏa mãn nếu điện tích bên trong quả cầu bằng -Q. Vì toàn bộ vỏ không được tích điện nên điện tích +Q sẽ được tạo ra ở bề mặt bên ngoài. Bây giờ, sử dụng nguyên lý xếp chồng, chúng ta có thể kết luận,

Hình 8.

rằng trường bên trong và bên ngoài vỏ bằng điện trường của điện tích Q đặt tại tâm của nó.

6) Khi thay một dây dẫn thì điện thế của nó bằng không. Trong trường hợp của chúng ta, điều này có nghĩa là hướng của điện trường bên ngoài lớp vỏ trở thành bằng không. Để làm được điều này, điều cần thiết là điện tích phải biến mất khỏi bề mặt bên ngoài (nó đi vào lòng đất). Điện tích -Q vẫn được cảm ứng ở bề mặt bên trong. Trường điện tích này bù cho trường điện tích Q chính xác ở mọi nơi, ngoại trừ vùng bên trong vỏ. Như vậy, lớp vỏ được thay thế là một tấm chắn tĩnh điện.

Điều thú vị cần lưu ý là sự lựa chọn này đúng với mọi hình dạng vỏ và mọi cách sắp xếp điện tích bên trong nó. Ví dụ, trong trường hợp một vỏ hình cầu được thay thế, nhưng với sự sắp xếp không đối xứng của điện tích chính xác, trường bên ngoài vẫn bằng 0 và trường bên trong sẽ không còn đối xứng nữa. Điện tích -Q cảm ứng trên bề mặt bên trong không còn phân bố đồng đều nữa.

Nếu chúng ta loại bỏ sự thay thế và truyền thêm một điện tích Q vào vỏ (đồng thời tổng điện tích của nó bằng 0), thì điện tích phải được phân bổ trên vỏ sao cho trường trong dây dẫn vẫn bằng 0. Điều này chỉ đạt được khi có sự phân bố đồng đều điện tích Q trên bề mặt bên ngoài của vỏ hình cầu. Theo đó trường bên ngoài trong trường hợp
