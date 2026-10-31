---
id: 1971-7-resheniya-144ae3fc
issue: kvant_1971_7
year: 1971
number: "7"
title: Lời giải các bài toán M39—M49; F45, F59—F65
rubric: zadachnik-kvanta
rubric_sub: Задачник «Кванта»
page_first: 26
page_last: 41
page_labels: 24, 25, 28, 29, 30, 31, 32, 33, 34, 35, 36, 37, 38, 39
tag: TOTZ
lang: vi
source: kvant_digital
extraction: vision
content_sha256: 82c1fe843ecac67f600fd36550458499667ea9d2e6a1ac9fd588b7cb6f03080e
prompt_sha256: 3ec6b8aabd9b98576af76503cd8a2902b9f5d18e01ee867dfb1228f59c6d52d8
translated_from: content/ru/1971/07/articles/06_resheniya-144ae3fc.md
source_content_sha256: e1a3fbdb757005486ff829983ef70add42079516e3e900a92be749f36af4d3b3
translation_model: gpt-5.6-terra
translation_run: vi-codex-2026-10-31
---

⟦folio 24⟧

LỜI GIẢI

Trong số này, chúng tôi công bố lời giải các bài toán M39—M49.

M39

Chứng minh rằng các số nguyên không âm $x, y$ thỏa mãn phương trình $x^2 - mxy + y^2 = 1$ (trong đó $m$ là một số nguyên cho trước, lớn hơn một) khi và chỉ khi $x$ và $y$ là hai số hạng kề nhau của dãy $\varphi_0 = 0, \varphi_1 = 1, \varphi_2 = m, \varphi_3 = m^2 - 1, \varphi_4 = m^3 - 2m, \varphi_5 = m^4 - 3m^2 + 1$, ..., trong đó $\varphi_{k+1} = m\varphi_k - \varphi_{k-1}$ với mọi $k \ge 1$.

Chẳng hạn, mọi nghiệm của phương trình

$$x^2 - 3xy + y^2 = 1$$

(1)

trong các số nguyên $(x, y)$, $0 \leq x < y$, là các cặp

$$(0, 1), (1, 3), (3, 8), (8, 21), \dots$$

(2)

gồm các số hạng kề nhau của dãy $0, 1, 3, 8, 21, \dots$, được xác định bởi các điều kiện $\varphi_0 = 0, \varphi_1 = 1, \varphi_{k+1} = 3\varphi_k - \varphi_{k-1}$ với mọi $k \ge 1$.

Giải bài toán này với $m = 3$ (với các $m > 1$ khác, lời giải hoàn toàn tương tự.) Ta phải chứng minh rằng, thứ nhất, mọi cặp số (2) đều thỏa mãn phương trình (1) và, thứ hai, không có cặp số không âm nào khác thỏa mãn phương trình này. (Lưu ý rằng phần thứ hai khó hơn của lời giải này đã bị nhiều độc giả gửi thư bỏ qua.)

Trong dãy (2), sau mỗi cặp $(x, y)$ là cặp $(x_1, y_1)$, có thể nhận được từ $(x, y)$ bằng phép biến đổi sau:

$$x_1 = y, y_1 = 3y - x.$$

(3)

Ta ký hiệu phép biến đổi $(x, y) \rightarrow (y, 3y - x)$ bằng chữ $T$. Dễ dàng

⟦folio 25⟧

kiểm tra rằng nếu cặp $(x, y)$ thỏa mãn phương trình (1), thì cặp $(x_1, y_1) = T(x, y)$ cũng thỏa mãn nó:

$$x_1^2 - 3x_1y_1 + y_1^2 = y^2 - 3y(3y - x) + (3y - x)^2 = y^2 - 3xy + x^2.$$

(4)

Từ đây lập tức thấy rằng mọi cặp (2) đều thỏa mãn phương trình (1): bởi vì cặp (0, 1) thỏa mãn nó, còn tất cả các cặp khác đều nhận được từ nó bằng một số hữu hạn phép biến đổi $T$.

Bây giờ ta sẽ chứng minh rằng phương trình (1) không có nghiệm nguyên nào khác $(x, y)$ thỏa mãn các điều kiện $0 \leq x < y$. Giả sử $(x_1, y_1)$ là một trong các nghiệm ấy. Ta hãy tìm một cặp $(x, y)$ mà từ đó $x_1$ và $y_1$ này nhận được theo các công thức (3), — để làm điều đó chỉ cần biểu diễn $x$ và $y$ qua $x_1$ và $y_1$:

$$x = 3x_1 - y_1, y = x_1.$$

(5)

Phép chuyển như vậy từ $(x_1, y_1)$ sang $(x, y)$ — phép biến đổi nghịch *) với $T$ — chúng ta sẽ ký hiệu là $T^{-1}$. Từ các đẳng thức (4) suy ra rằng nếu cặp $(x_1, y_1)$ thỏa mãn phương trình (1), thì cặp $(x, y) = T(x_1, y_1)$ cũng thỏa mãn nó. Chúng ta sẽ chứng minh rằng nếu thêm vào đó $0 < x_1 < y_1$, thì

$$0 \leq x < y.$$

(6)

Biểu diễn đẳng thức $x_1^2 - 3x_1y_1 + y_1^2 = 1$ theo hai cách sau:

$$x_1^2 + y_1(y_1 - 3x_1) = 1,$$

$$x_1(x_1 - y_1) + y_1(y_1 - 2x_1) = 1.$$

(7)

Từ đẳng thức (7) lập tức suy ra ($x_1$ và $y_1$ dương!) rằng $-x = y_1 - 3x_1 \leq 0$, hơn nữa nếu $y_1 - 3x_1 = 0$, thì $x_1 = 1$ và $y_1 = 3$. Đến lượt mình, từ đẳng thức (8) suy ra rằng $y - x = y_1 - 2x_1 > 0$ (vì $x_1 - y_1$ âm). Các bất đẳng thức (6) đã được chứng minh. Lưu ý rằng chúng cũng có thể được viết như sau:

$$0 \leq x < x_1,$$

(9)

vì $x_1 = y$. Vậy, mọi nghiệm $(x_1, y_1)$, $0 < x_1 < y_1$, sau phép biến đổi $T^{-1}$ chuyển thành nghiệm $(x, y)$, với $0 \leq x < y$. Nếu đồng thời $x > 0$, thì ta có thể áp dụng $T^{-1}$ thêm một hoặc nhiều lần nữa, thu được các nghiệm mới (nhỏ hơn về độ lớn). Thật vậy, như (9) cho thấy, giá trị của số nguyên $x$ giảm đi sau mỗi phép biến đổi. Vì thế, sau một số hữu hạn bước nào đó ta phải dừng lại, và ta chỉ có thể dừng lại khi thu được nghiệm $(x, y)$, trong đó $x = 0$ và do đó $y = 1$. Như vậy, ta đã chứng minh rằng từ mỗi nghiệm $(x_1, y_1)$, sau một số hữu hạn phép biến đổi $T^{-1}$, thu được nghiệm (0, 1). Từ đây suy ra rằng mỗi nghiệm từ (0, 1) qua một số hữu hạn phép biến đổi $T$ (tức là không có nghiệm nào khác, khác với (2)). Bài toán được giải hoàn toàn.

Có thể hình dung lời giải này rõ hơn như sau. Ta sẽ biểu diễn một cặp số $(x, y)$ như thường lệ, bằng một điểm trên mặt phẳng. Khi đó phương trình $x^2 - 3xy + y^2 = 1$ xác định trên mặt phẳng một đường cong gọi là “hyperbol”. (Trên bìa vẽ cả một họ hyperbol được xác định bởi các phương trình $x^2 - 3xy + y^2 = c$ với các giá trị khác nhau của tham số $c$, còn hyperbol mà ta quan tâm có màu vàng.) Giải phương trình này trong các số nguyên nghĩa là chỉ ra mọi điểm có tọa độ nguyên nằm trên hyperbol. Tuy nhiên, một điểm như vậy dễ chỉ ra: đó là điểm đen có tọa độ (0, 1). Mọi điểm còn lại (trong góc $0 \leq x < y$), như ta đã chứng minh, đều nhận được từ nó bằng cách lần lượt áp dụng phép biến đổi $T : (x, y) \rightarrow (y, 3y - x)$. Phép biến đổi $T$ của mặt phẳng có các tính chất sau:

1) Biến mỗi đường thẳng trên mặt phẳng thành một đường thẳng (những phép biến đổi như vậy được gọi là tuyến tính).

*) Khái niệm phép biến đổi ngược đã được bàn trong bài viết của A. N. Kolmogorov “Hàm số là gì?” (“Kvant” số 1,1970).

⟦folio 28⟧

Hình 2. Trong $m+k+1$ phần tử, trước hết chọn một phần tử (sao cho bên trái và bên phải nó đều có không ít hơn $k$ phần tử), kẻ một vạch qua nó, rồi ở bên trái vạch và bên phải vạch chọn mỗi bên $k$ phần tử. Trong hình của chúng ta $m=9, k=3, m+k+1=13$.

các phần tử xác định $k+m$, rồi thêm $k$ phần tử nữa trong số $n-m$ phần tử còn lại. Điều đã nói có thể tìm được như sau. Xếp «thành một hàng» $n+k$ phần tử đã cho và kẻ một vạch thẳng đứng, ngăn cách $k+m$ phần tử ở bên trái với $n-m$ phần tử ở bên phải. Chọn bằng một cách nào đó $k$ phần tử ở bên trái vạch và $k$ phần tử ở bên phải vạch, rồi lập sự nối ghép của mỗi lựa chọn «bên phải» như vậy. Rõ ràng, tổng số sự nối ghép như thế là $C_{k+m}^k \cdot C_{n-m}^k$.

Bây giờ không khó chứng minh rằng

$$C_k^k \cdot C_n^k + C_{k+1}^k \cdot C_{n-1}^k + C_{k+2}^k \cdot C_{n-2}^k + \dots + C_n^k \cdot C_k^k = C_{n+k+1}^k \cdot C_{n-k+1}^k.$$

Để làm điều đó, chỉ cần thiết lập một tương ứng một-một giữa các lựa chọn $2k+1$ phần tử trong số $n+k+1$ phần tử và các lựa chọn từ $n+k$ phần tử có dạng: «$k$ phần tử bên trái vạch; vạch; $k$ phần tử bên phải vạch», mà tổng số bằng tổng đứng ở vế trái của đẳng thức (2). Vậy tổng cần tìm bằng

$$(k!)^2 \cdot C_{n+k+1}^2 = \frac{(n+k+1)!(k!)^2}{(2k+1)!(n-k)!}.$$

Đặc biệt, đối với bài toán thứ nhất M40, ta có $k=1$ và do đó tổng sẽ bằng $C_{n+2}^3 = \frac{(n+2)(n+1)n}{6}$.

Nếu cách lập luận đã trình bày có vẻ khó đối với bạn, và càng hơn nữa nếu nó có vẻ thú vị đối với bạn, chúng tôi khuyên bạn xem cuốn sách của N. Ya. Vilenkin “Tổ hợp học” (M., “Nauka”, 1969). Ở đó, đặc biệt, tại trang 57 có chứng minh công thức (24), tương tự công thức (2).

V. N. Berezin

M41

Cho một đường tròn, đường kính $AB$ của nó và điểm $C$ trên đường kính này. Dựng trên đường tròn hai điểm $X$ và $Y$, đối xứng nhau qua đường kính $AB$, sao cho đường thẳng $YC$ vuông góc với đường thẳng $XA$.

Gọi $K$ là giao điểm của các đoạn thẳng $XY$ và $AB$; theo giả thiết $XY \perp AB$ và $XK = KY$. Với mọi điểm $X$ trên đường tròn $\Rightarrow AXB = 90^\circ$. Vì vậy, yêu cầu $YC \perp AX$ tương đương với mỗi điều kiện sau:

$$YC \parallel BX, \Rightarrow YCB = \Rightarrow CBX,$$

$$\triangle CYK = \triangle KBX, \quad CK = KB.$$

Như vậy, dựng tại trung điểm của đoạn thẳng $CB$ đường vuông góc với đường thẳng $AB$, ta sẽ nhận được tại giao điểm của nó với đường tròn hai điểm cần tìm (có thể lấy bất kì điểm nào trong số đó làm $X$, khi đó điểm kia sẽ đóng vai trò $Y$).

⟦folio 29⟧

M42

Các chữ số của một số có mười bảy chữ số nào đó được viết theo thứ tự ngược lại. Số nhận được được cộng với số ban đầu. Chứng minh rằng ít nhất một trong các chữ số của tổng của chúng là chẵn.

Chứng minh bằng quy nạp theo $n$ rằng mệnh đề này đúng với mọi số có $(4n+1)$ chữ số. Với $n=0$ điều đó hiển nhiên. Giả sử rằng với một $n$ nào đó nó sai, tức là tồn tại một số $a_1 a_2 a_3 \dots a_{4n-1} a_{4n} a_{4n+1}$ sao cho trong tổng

$$\frac{a_1}{a_{4n+1}} + \frac{a_2}{a_{4n}} + \dots + \frac{a_{4n-1}}{a_{4n}} + \frac{a_{4n+1}}{a_{4n}}$$

mọi chữ số đều lẻ. Khi đó tổng các chữ số $a_1 + a_{4n+1}$ là lẻ và tại những vị trí được chỉ bằng mũi tên không xảy ra việc nhớ một đơn vị sang hàng tiếp theo. Vì vậy trong tổng các số có $(4n-3)$ chữ số

$$\frac{a_3 \dots a_{4n-1}}{a_{4n-1} \dots a_3}$$

cũng mọi chữ số đều lẻ, do đó mệnh đề của chúng ta cũng sai với $(n-1)$. Chứng minh hoàn tất (hãy suy nghĩ vì sao “bước quy nạp” thông thường — “nếu đúng với $n$, thì cũng đúng với $(n+1)$” — có thể thay bằng bước ngược lại: “nếu sai với $n$, thì sai cả với $(n-1)$”!).

Nhận xét rằng không thể tăng cường mệnh đề đã chứng minh: với các số mà số chữ số là chẵn hoặc có dạng $(4n+3)$, mệnh đề của bài toán có thể không đúng:

$$11 \ 112 \ 222 + 22 \ 221 \ 111 = 33 \ 333 \ 333, \ 72 \ 727 \ 262 \ 626 + 62 \ 626 \ 272 \ 727 = 135 \ 353 \ 535 \ 353.$$

M43

Mỗi cạnh của một tam giác đều được chia thành $n$ phần bằng nhau. Qua các điểm chia, kẻ các đường thẳng song song với các cạnh. Kết quả là tam giác được chia thành $n^2$ tam giác nhỏ. Gọi là «chuỗi» một dãy các tam giác, trong đó không tam giác nào xuất hiện hai lần và mỗi tam giác tiếp theo có một cạnh chung với tam giác trước đó. Số tam giác lớn nhất có thể có trong chuỗi là bao nhiêu?

Đáp số: $n^2 - n + 1$. Để chứng minh rằng không thể nhiều hơn, chỉ cần thực hiện một bước bất ngờ: tô màu các tam giác theo kiểu bàn cờ, như trên hình vẽ. Phần còn lại hoàn toàn đơn giản.

Trong toàn bộ tam giác, số tam giác đỏ nhiều hơn số tam giác vàng $n$ chiếc (trong mỗi hàng ngang, số tam giác đỏ nhiều hơn một chiếc), còn trong chuỗi các màu phải xen kẽ, vì vậy số tam giác đỏ chỉ có thể nhiều hơn số tam giác vàng một chiếc.

Một trong các chuỗi có độ dài lớn nhất được chỉ ra trên hình vẽ. (Từ điều đã nói ở trên, rõ ràng rằng để chuỗi có độ dài $n^2 - n + 1$, cần và đủ là nó bắt đầu và kết thúc ở các tam giác đỏ và đi qua tất cả, không trừ một tam giác vàng nào.)

⟦folio 30⟧

Chứng minh rằng với mỗi số tự nhiên $K$ tồn tại vô hạn số tự nhiên $T$ không chứa chữ số không trong cách viết thập phân và sao cho $T$ và $KT$ có tổng các chữ số bằng nhau.

Giả sử số $K$ (trong cách viết thập phân) có $k$ chữ số. Khi đó, có thể lấy làm $T$ bất kỳ số nào 999...99, được viết bằng $n$ chữ số chín, với $n \geqslant k$; khi ấy cả tổng các chữ số của $T$, lẫn tổng các chữ số của $KT$ đều bằng 9$n$ (trong số $KT = K(10^n-1)$ các chữ số cách nhau $n$ hàng cho tổng bằng 9; chẳng hạn, $743\ 552 \cdot 99\ 999\ 999 = 743\ 552 \cdot (10^8-1) =$
$= 74\ 355\ 200\ 000\ 000-743\ 552 = 74\ 355\ 199\ 256\ 448$;

chứng minh gần như hiển nhiên cho trường hợp tổng quát xin để lại cho độc giả).

M45

Chứng minh rằng từ bất kỳ 200 số nguyên nào cũng có thể chọn ra 100 số mà tổng của chúng chia hết cho 100.

Hãy thử khái quát bài toán này: chứng minh rằng từ bất kỳ $2n-1$ số nguyên nào cũng có thể chọn ra $n$ số mà tổng của chúng chia hết cho $n$, với $n \geqslant 2$.

Bổ đề. Nếu khẳng định của bài toán đúng với $n = a$ và với $n = b$, thì nó cũng đúng với $n = ab$.

Lưu ý rằng tính chất «tổng của $n$ số nguyên $x_1, \ldots, x_n$ chia hết cho $n$» cũng có thể phát biểu như sau: «trung bình cộng $\frac{x_1 + \ldots + x_n}{n}$ là một số nguyên».

Vậy, cho tùy ý $2ab-1$ số nguyên. Vì khẳng định đúng khi $n = b$ và $2ab-1>2b-1$, từ $2ab-1$ số đã cho có thể chọn ra $b$ số mà tổng của chúng chia hết cho $b$. Sau đó, từ các số còn lại (nếu chúng không ít hơn $2b-1$) chọn thêm $b$ số có tính chất này, và cứ tiếp tục như vậy.

Vì
$$2ab-1 = (2a-1)b + (b-1),$$
nên có thể lặp lại phép toán này $2a-1$ lần và thu được $2a-1$ nhóm, mỗi nhóm gồm $b$ số, trong mỗi nhóm trung bình cộng của $b$ số là một số nguyên. Vì mệnh đề đúng với $n = a$, từ $2a-1$ trung bình cộng này có thể chọn ra $a$ trung bình cộng mà tổng của chúng chia hết cho $a$. Rõ ràng khi đó $ab$ số tạo thành $a$ nhóm tương ứng, mỗi nhóm gồm $b$ số, có tính chất cần thiết: tổng của chúng chia hết cho $ab$. Bổ đề được chứng minh (bổ đề này, cũng như bài toán, do Yu. I. Nonin nghĩ ra).

Vậy, để chứng minh khẳng định của bài toán với $n = a_1a_2\ldots a_k$ tùy ý, chỉ cần chứng minh nó cho từng thừa số riêng lẻ $n = a_1$, $n = a_2$, ..., $n = a_k$ (và áp dụng bổ đề vài lần). Do đó, chỉ cần biết cách chứng minh khẳng định này cho các thừa số nguyên tố của số $n$. Chẳng hạn, để chứng minh với $n = 100$, chỉ cần chứng minh hai khẳng định: “từ bất kỳ 3 số nguyên nào cũng có thể chọn 2 số có tổng chia hết cho 2” và “từ bất kỳ 9 số nguyên nào cũng có thể chọn 5 số có tổng chia hết cho 5”. Khẳng định thứ nhất là hiển nhiên, còn khẳng định thứ hai có thể chứng minh bằng một phép xét hết không quá dài. Để bạn đọc tự kiểm tra điều này, cũng như thử tìm ra một chứng minh dùng được ngay cho mọi $n$ nguyên tố. Tuy nhiên, chứng minh như vậy sẽ được trình bày trong số báo tiếp theo.

⟦folio 31⟧

M46

Một đa giác lồi có thể có bao nhiêu cạnh bằng đường chéo lớn nhất?

Đáp án: hai, một hoặc không có cạnh nào.

Không khó dựng các ví dụ cho từng trường hợp này. Không tồn tại đa giác có ba hoặc nhiều hơn ba cạnh bằng đường chéo lớn nhất, vì hai cạnh bằng đường chéo lớn nhất nhất thiết phải có một đỉnh chung (hình 5), còn ba cạnh mà từng hai cạnh có một đỉnh chung chỉ có thể thuộc về một tam giác, mà tam giác thì không có đường chéo.

M47

Từ các chữ số 1 và 2 lập thành năm số có $n$ chữ số sao cho trong mỗi hai số, các chữ số trùng nhau đúng ở $m$ vị trí, nhưng không có vị trí nào mà cả năm số trùng nhau. Chứng minh rằng $\frac{2}{5} \leq \frac{m}{n} \leq \frac{3}{5}$.

Viết các số thành một cột. Trong mỗi hàng («cột») có 5 chữ số. Từ chúng có thể lập được 10 cặp (không có thứ tự). Trong tất cả $n$ cột sẽ có 10 $n$ cặp như vậy. Hãy xác định trong số đó có bao nhiêu cặp gồm các chữ số giống nhau, tức là các cặp (1, 1) và (2, 2). Trong mỗi cột có либо 4, либо 6 cặp như vậy. Vì thế tổng số các cặp như vậy không nhỏ hơn 4 $n$ và không lớn hơn 6 $n$. Mặt khác, số các cặp như vậy bằng 10 $m$, vì khi so sánh hai số bất kỳ theo tất cả $n$ hàng, theo giả thiết, thu được đúng $m$ cặp như vậy, còn số mọi cặp từ 5 số là 10.

Vậy, $4n \leq 10m \leq 6n$, điều phải chứng minh (xem hình 6).

M48

Trong tam giác nhọn $ABC$, đường phân giác $AD$, đường trung tuyến $BM$ và đường cao $CH$ cắt nhau tại một điểm. Chứng minh rằng góc $BAC$ lớn hơn 45°.

Không khó chứng minh rằng với $\Rightarrow BAC = \alpha < \frac{\pi}{2}$ cho trước, tồn tại đúng một (tới đồng dạng) tam giác $ABC$, trong đó đường cao $CH$, đường phân giác $AD$ và trung tuyến $BM$

⟦folio 32⟧

Diana $BM$ cắt nhau tại một điểm. Thật vậy, lấy trên một cạnh của góc $\Rightarrow A = \alpha$ (tùy ý) đoạn $AC$, hạ xuống cạnh kia của góc đường vuông góc $CH$ và gọi giao điểm của nó với tia phân giác của góc $A$ là $O$, ta tìm được điểm $B$ là giao điểm của cạnh thứ hai của góc và đường thẳng $OM$ (trong đó $M$ là trung điểm của đoạn $AC$), nhờ đó dựng được tam giác cần tìm $ABC$; rõ ràng, với $\Rightarrow A$ và $AC$ đã cho, nó được xác định duy nhất. Nhận xét rằng khi đó góc $B$ là góc nhọn (vì điểm $H$ — chân đường cao — nằm trên cạnh $AB$).

Chứng minh rằng nếu $\Rightarrow A < \frac{\pi}{4}$, thì $\Rightarrow ACB > \frac{\pi}{2}$. Trên đường thẳng $AB$ lấy đoạn $HB_1 = AH$. Khi đó đường phân giác $B_1F$ của góc $B_1$ của tam giác cân $AB_1C$ sẽ đi qua điểm $O$. Vì $\frac{AF}{FC} = \frac{AB_1}{B_1C} > 1$, nên điểm $M$ nằm giữa $A$ và $F$, do đó $B_1$ nằm giữa $A$ và $B$ và $\Rightarrow BCA > \Rightarrow B_1CA > \frac{\pi}{2}$.

Trong bài toán này cũng có thể thu được kết quả chính xác hơn: tìm cận dưới chính xác cho góc $\alpha$ với điều kiện $\Rightarrow ACB = \gamma < \frac{\pi}{2}$. Để làm điều đó, ta biểu diễn $\gamma$ như một hàm của $\alpha$. Kẻ $HE \parallel BM$ (E là điểm trên $AC$). Khi đó (hình 7)

$$\frac{EM}{MC} = \frac{HO}{OC} = \frac{AH}{AC} = \cos \alpha, \quad \frac{HB}{AH} = \frac{EM}{AE} = \frac{\cos \alpha}{1 - \cos \alpha}, \quad \frac{HB}{HC} = \frac{\cos^2 \alpha}{\sin \alpha (1 - \cos \alpha)},$$

$$\gamma = \gamma(\alpha) = \frac{\pi}{2} - \alpha + \arctg \frac{\cos^2 \alpha}{\sin \alpha (1 - \cos \alpha)}.$$

Từ đây rõ rằng hàm số $\gamma = \gamma(\alpha)$ trên đoạn $0 < \alpha < \frac{\pi}{2}$ giảm đơn điệu ( $\alpha$ càng lớn thì sin $\alpha$ càng lớn và cos $\alpha$ càng nhỏ, do đó phân số đứng dưới dấu arctang cũng luôn nhỏ hơn). Bây giờ hãy tìm $\alpha$ sao cho $\gamma(\alpha) = \frac{\pi}{2}$. Phương trình này quy về dạng sau: $0 < \alpha < \frac{\pi}{2}, \sin^2 \alpha (1 - \cos \alpha) = \cos^3 \alpha$, từ đó cos $\alpha = \frac{\sqrt{5} - 1}{2}$. Vậy, nếu $\gamma < \frac{\pi}{2}$, thì $\alpha > \alpha_0 = \arccos \frac{\sqrt{5} - 1}{2} \left( \alpha_0 > \frac{\pi}{4} \right)$, vì $\frac{\sqrt{5} - 1}{2} < \frac{\sqrt{2}}{2}$; như có thể kiểm tra theo bảng, số đo góc tương ứng với $\alpha_0$, tính bằng độ, xấp xỉ $51^\circ 50'$).

M49

Trên các thẻ viết các số từ 11 111 đến 99 999 kể cả hai đầu. Sau đó các thẻ này được xếp thành một dãy theo thứ tự tùy ý. Chứng minh rằng số gồm 444 445 chữ số thu được không thể là một lũy thừa của hai.

⟦folio 33⟧

Dễ chứng minh rằng số này chia hết cho 11 111, bằng cách dùng việc các số $10^5A$ và $A$ với mọi số nguyên $A$ cho cùng số dư khi chia cho 11 111, còn tổng $11 111+11 112+\dots+99 998+99 999$ chia hết cho 11 111. Nhưng nếu số đó chia hết cho 11 111 thì dĩ nhiên nó không thể là lũy thừa của hai. (Điều này, chẳng hạn, lập tức suy ra từ định lý về tính duy nhất của phân tích thành các thừa số nguyên tố.)

Những lời giải bài toán thành công nhất được E. Turkevich từ thành phố Chernivtsi gửi đến cho chúng tôi (em đã tìm được đánh giá chính xác của góc $\alpha$ trong bài M48, giải các bài M46 và M49) và R. Akhmetshin từ thành phố Osh (M42, M44, M47).

N. B. Vasiliev

Trong số này chúng tôi công bố lời giải các bài Ф45, Ф59—Ф65

Hãy trở lại một lần nữa với bài Ф45. Nó có một lời giải khá đơn giản và đẹp.

Ф45

Một tụ điện hình cầu, chứa đầy chất điện môi và được tích điện đến một hiệu điện thế nào đó, phóng điện qua chất điện môi của nó. Từ trường của các dòng phóng điện trong không gian giữa hai mặt cầu sẽ như thế nào?

Vì tại mọi điểm của chất điện môi, mọi hướng trong mặt phẳng vuông góc với bán kính đều bình đẳng, nên vectơ $\vec{B}$ của cảm ứng từ không thể có thành phần nằm trong mặt phẳng ấy. Vì vậy vectơ $\vec{B}$ chỉ có thể hướng theo bán kính. Nhưng mọi điểm của chất cách điện đều bình đẳng. Điều đó có nghĩa là các vectơ $\vec{B}$ và các đường sức từ hoặc hội tụ vào tâm mặt cầu, hoặc đi ra từ tâm. Nhưng các đường sức từ phải khép kín. Vậy điều đó là không thể, và $\vec{B} = 0$. Từ trường của các dòng phóng điện của tụ điện bằng không.

Ф59

Cần bỏ đi cạnh nào của một khối lập phương bằng dây để điện trở giữa các điểm $A$ và $B$ (hình 8) thay đổi mạnh nhất? Điện trở của tất cả các cạnh của khối lập phương đều như nhau.

Hãy đánh số tất cả các cạnh và các đỉnh của khối lập phương. Dòng điện đi theo cạnh 1 phân nhánh tại đỉnh 1 thành hai dòng, sau đó đi theo các cạnh 7 và 8.

Tương tự, dòng điện đi theo cạnh 2 phân thành hai dòng bằng nhau tại đỉnh 2, v.v. Qua cạnh 4 đi dòng điện đã đi theo các cạnh 7 và 12... Các cạnh 5 và 6 tương đương với cạnh 4. Điều đó có nghĩa là qua các cạnh 1, 2, 3, 4, 5 và 6 đi dòng điện lớn gấp đôi so với qua các cạnh 7, 8, 9, 10, 11 và 12. Rõ ràng điện trở của mạch sẽ thay đổi nhiều nhất nếu bỏ khỏi mạch dây dẫn có dòng điện lớn nhất đi qua. Cần bỏ khỏi khối lập phương bằng dây một trong các cạnh 1, 2, 3, 4, 5 hoặc 6.

Hãy tự kiểm tra điều đó bằng cách tính điện trở của các mạch tương ứng.

⟦folio 34⟧

Một vài gợi ý. Không khó tính điện trở của khối lập phương giữa các đỉnh A và B. Muốn vậy chỉ cần nhận thấy rằng do tính đối xứng, các đỉnh 1, 2 và 3 có cùng điện thế. Vì thế điện trở của mạch sẽ không thay đổi nếu nối chúng lại với nhau. Dĩ nhiên các đỉnh 4, 5 và 6 cũng có cùng điện thế và cũng có thể nối chúng lại với nhau. Sau đó bạn sẽ được một mạch (hình 9), điện trở của nó rất dễ tính. Nếu lấy điện trở của một cạnh bằng 1 ôm, thì điện trở của mạch sẽ bằng 5/6 ôm. Không khó tìm điện trở của mạch trong trường hợp bỏ đi một trong các cạnh 1, 2, 3, 4, 5 hoặc 6. Ở đây cũng có thể tìm được các điểm tương đương, khi nối chúng lại bạn sẽ được một sơ đồ gồm các nối tiếp và song song. Nhưng trước khi tìm điện trở của mạch sau khi bỏ đi một trong các cạnh 7, 8, 9, 10, 11 hoặc 12, hãy đọc bài của A. R. Zilberman “Biến đổi các mạch điện” trong “Kvant” số 3 năm 1971. Bạn sẽ cần phương pháp được trình bày trong bài đó.

Ф60

Trong gương phẳng thấy ảnh của một ngọn nến. Điều gì sẽ xảy ra với nó nếu đặt một tấm kính phẳng song song giữa gương và ngọn nến?

Vẽ đường đi của vài tia, không khó để thấy rằng sau khi đặt một tấm kính phẳng song song giữa ngọn nến và gương, ảnh của ngọn nến sẽ tiến lại gần gương (hình 10). Các đường màu xanh chỉ đường đi của tia khi không có tấm kính, các đường màu đỏ — khi có tấm kính.

F61

Một khối lập phương trượt không ma sát trên sàn nằm ngang nhẵn va một mặt bên của nó vào một bức tường thẳng đứng. Hệ số ma sát của khối lập phương với tường bằng k. Khối lập phương sẽ bật ra dưới góc nào đối với tường, nếu trước khi va chạm với nó nó chuyển động theo hướng hợp với tường một góc α?

Khi khối lập phương va vào tường, có hai lực tác dụng lên nó: lực phản ứng pháp tuyến N của tường và lực ma sát Fтр (hình 11). Ta phân tích vận tốc của khối lập phương trước và sau khi va chạm với tường thành các thành phần song song với những lực này. Các vận tốc v1 = v sinα và u1 vuông góc với tường, còn các vận tốc v2 = v cosα và u2 song song với nó. Theo phương vuông góc với tường, giữa khối lập phương và tường, như thường lệ, xảy ra va chạm đàn hồi tuyệt đối, kết quả là thành phần vận tốc của khối lập phương vuông góc với tường đổi sang chiều ngược lại: u1 = −v1 = −v sinα. Điều này có nghĩa:

Hình 10.
Hình 11.

⟦folio 35⟧

rằng thành phần xung lượng của khối lập phương vuông góc với tường thay đổi một lượng $2mv\sin\alpha$ ($|u_1-v_1| = 2v\sin\alpha, m - \text{masca кубика})$.

Nếu ký hiệu thời gian tiếp xúc của khối lập phương với tường là $\tau$, còn giá trị trung bình của lực phản ứng của tường là $N_{cp}$, thì theo định luật II Newton, độ biến thiên thành phần xung lượng của khối lập phương vuông góc với tường bằng xung lượng của lực $N_{cp}$, tức là

$$2mv\sin\alpha = N_{cp}\tau.$$

Nếu lực ma sát không tác dụng lên khối lập phương, thì thành phần xung lượng của khối lập phương song song với tường sẽ không thay đổi và khối lập phương sẽ bật ra khỏi tường dưới cùng góc $\alpha$ mà nó đã chuyển động tới tường trước va chạm. Tuy nhiên, do tác dụng của lực ma sát trong trường hợp của chúng ta, thành phần $v_2$ của vận tốc khối lập phương cũng thay đổi. Trước hết giả sử rằng lực ma sát trung bình $F_{\tau p,cp} = N_{cp}k$, tác dụng lên khối lập phương, sao cho trong thời gian tương tác của khối lập phương với tường, thành phần vận tốc của khối lập phương song song với tường chưa kịp giảm xuống bằng không. Trong trường hợp này, theo định luật II Newton,

$$mu_2 - mv_2 = -F_{\tau p,cp}\tau,$$ hoặc $mu_2 = mv\cos\alpha - N_{cp}k\tau$.

Nhưng $N_{cp}\tau = 2mv\sin\alpha$, do đó

$$mu_2 = mv\cos\alpha - 2kmv\sin\alpha,$$

hoặc

$$u_2 = v(\cos\alpha - 2k\sin\alpha).$$

Bây giờ ta tìm góc mà khối lập phương sẽ bật ra:

$$tg\beta = \frac{|u_1|}{u_2} = \frac{v\sin\alpha}{v(\cos\alpha - 2k\sin\alpha)} = \frac{tg\alpha}{1 - 2ktg\alpha}.$$

Lời giải như vậy được V. Goncharenko ở Maikola, vùng Krasnoarsk, M. Gilburg ở Borislav, tỉnh Lvov, N. Smirnov ở Gorky, V. Zakass ở Usolye-Sibirskoye, tỉnh Irkutsk, I. Gritsik ở David-Gorodok, tỉnh Brest, A. Senyavin ở Moskva, A. Anishchenko ở Sarapul, UASSR, và Kudek ở Rzhev đưa ra.

Tuy nhiên, đây chưa phải là lời giải đầy đủ của bài toán. Điều này được các bạn đọc A. Vlasov ở Valdai, B. Shparberg ở Mogilev trên sông Dnepr, A. Zhukov ở Kirovsk, tỉnh Donetsk, và I. Berman ở Chernivtsi nhận thấy.

Rõ ràng, lời giải của chúng ta đúng nếu $u_2 > 0$, tức là $2ktg\alpha < 1$.

Khi $tg\alpha \rightarrow \frac{1}{2k}$ thì $tg\beta \rightarrow \infty$ và $\beta \rightarrow \frac{\pi}{2}$. Điều đó có nghĩa là gì?

Nếu $tg\alpha = \frac{1}{2k}$, thì $u_2 = v(\cos\alpha - 2k\sin\alpha) = v\left(\cos\alpha - \frac{1}{tg\alpha}\sin\alpha\right) = 0$.

Trong thời gian khối lập phương tương tác với tường, thành phần vận tốc của khối lập phương song song với tường trở thành bằng không. Còn va chạm với tường sẽ xảy ra thế nào nếu $tg\alpha > \frac{1}{2k}$?

Trong trường hợp này, khối lập phương sẽ trượt tương đối so với tường không phải trong toàn bộ thời gian va chạm, mà cho đến khi thành phần vận tốc của nó song song với tường trở thành bằng không. Cùng với nó, lực ma sát tác dụng lên khối lập phương cũng trở thành bằng không, và khối lập phương sẽ bật ra dưới góc $90^\circ$ so với tường.

Vậy,

$$\beta = \begin{cases} \arctg\left(\frac{tg\alpha}{1 - 2ktg\alpha}\right) & \text{khi } tg\alpha < \frac{1}{2k}, \\ \frac{\pi}{2} & \text{khi } tg\alpha \geq \frac{1}{2k}. \end{cases}$$

⟦folio 36⟧

Một sợi dây mảnh không giãn gồm hai đoạn. Khối lượng trên một đơn vị chiều dài của một đoạn bằng $\rho_1$, còn của đoạn kia bằng $\rho_2$. Sợi dây ôm quanh một vành rất nhẹ bán kính $R$, có khối lượng không đáng kể so với khối lượng của sợi dây ôm quanh nó, các đầu dây được gắn vào sàn (hình 12). Trên đoạn dây có khối lượng trên một đơn vị chiều dài $\rho_1$, vành lăn với vận tốc $v_1$. Vành sẽ lăn với vận tốc nào trên đoạn dây thứ hai?

Khi vòng chuyển từ đoạn dây này sang đoạn dây khác, thế năng của dây thay đổi. Thật vậy, khi vòng chuyển động trên đoạn dây có mật độ dài $\rho_1$, thế năng của vòng dây bằng $m_1 g R = \rho_1 2 \pi R g R = 2 \pi \rho_1 R^2 g$ (khối tâm của vòng nằm ở tâm của nó). Khi vòng chuyển động trên đoạn dây có mật độ dài $\rho_2$, nó bằng $m_2 g R = 2 \pi \rho_2 R^2 g$. Tương ứng, động năng của vòng dây cũng thay đổi. Vì không có tổn hao, ta có thể sử dụng định luật bảo toàn năng lượng.

Tuy nhiên, để làm điều đó, ta cần biết động năng của một vòng khối lượng $m$, lăn không trượt trên mặt phẳng với vận tốc $v$. Có thể sử dụng kết quả thu được trong bài báo của A. K. Kikon «Chuyển động quay của các vật》（Kvant số 1, 1971):

$$K = \frac{mv^2}{2} + \frac{I \omega^2}{2} = \frac{mv^2}{2} + \frac{mR^2 \omega^2}{2} = \frac{mv^2}{2} + \frac{mv^2}{2} = mv^2.$$

Nhưng ta sẽ nhận được công thức này bằng một thủ thuật đơn giản.

Quả cầu lăn không trượt tại mọi thời điểm quay quanh tâm quay tức thời — điểm tiếp xúc với mặt phẳng (hình 13). Vận tốc góc quay của quả cầu $\omega = \frac{v}{R}$. Điều này có nghĩa là vận tốc của điểm $A$ trên quả cầu vuông góc với đoạn $OA$ và bằng $OA \cdot \omega$. Từ $\triangle OAD$ suy ra $OA = 2R \cos \alpha$. Do đó $v_A = 2R \cos \alpha = 2v \cos \alpha$. Tương tự, vận tốc của điểm $B$, đối diện theo đường kính với điểm $A$, bằng $v_B = 2v \cos (90^\circ - \alpha) = 2v \sin \alpha$. Động năng của các phần nhỏ có khối lượng $\Delta m$ gần các điểm $A$ và $B$

$$K_{A+B} = \frac{\Delta mv_A^2}{2} + \frac{\Delta mv_B^2}{2} = \frac{1}{2} \Delta m (4v^2 \cos^2 \alpha + 4v^2 \sin^2 \alpha) = 2\Delta mv^2.$$

$K_{A+B}$ không phụ thuộc vào $\alpha$. Điều đó có nghĩa là bất kỳ cặp điểm đối diện qua đường kính nào khác của vành cũng có đúng năng lượng ấy. Vì vậy động năng của toàn bộ vành là $mv^2$. Bây giờ viết định luật bảo toàn năng lượng:

$$m_1 v_1^2 + m_1 g R = m_2 v_2^2 + m_2 g R;$$

suy ra

$$v_2 = \sqrt{\frac{m_1}{m_2} v_1^2 + g R \left(\frac{m_1}{m_2} - 1\right)} = \sqrt{\frac{\rho_1}{\rho_2} v_1^2 + g R \left(\frac{\rho_1}{\rho_2} - 1\right)}.$$

⟦folio 37⟧

Bây giờ hãy xem ta đã thu được gì. Nếu $\rho_1 > \rho_2$, thì $\frac{\rho_1}{\rho_2} - 1 > 0$ và dưới dấu căn là một số dương với mọi giá trị của $v_1$, kể cả khi $v_1 = 0$. Đáp số khi $v_1 = 0$ có ý nghĩa sau: nếu vành đứng như trên hình 14, và vì những nguyên nhân ngẫu nhiên bắt đầu chuyển động sang phải với vận tốc vô cùng nhỏ, thì khi dây đỏ tháo ra khỏi nó và dây xanh quấn vào, nó sẽ có vận tốc $v_2 = \sqrt{gR\left(\frac{\rho_1}{\rho_2} - 1\right)}$.

Nếu $\frac{\rho_1}{\rho_2} < 1$, thì khi $v_1^2 < gR\left(\frac{\rho_1}{\rho_2} - 1\right)\frac{\rho_2}{\rho_1}$ biểu thức dưới dấu căn trở thành âm. Điều đó có nghĩa là với vận tốc như vậy, vành không thể chuyển sang dây có mật độ dài $\rho_2$. Nó sẽ quấn một phần dây nặng hơn (hình 15), dừng lại và bắt đầu chuyển động theo hướng ngược lại.

Lời giải đúng được gửi bởi V. Yakir từ Kishinev, A. Vlasov từ Valdya thuộc tỉnh Novgorod, I. Berman từ thành phố Chernovtsy, CHXHCN Ukraina, B. Shparbere từ Mogilev, CHXHCN Belorussia, A. Anishchenko từ Sarapul, CHXHCN Udmurt, E. Gubarev từ Moskva.

Ф63

Một người, để không bị trượt trên ngọn đồi băng giá, chạy xuống khỏi nó. Tại sao làm như vậy là hợp lý?

Lên người đứng trên dốc tác dụng hai lực: trọng lực $\vec{F}_T = mg$ và lực $\vec{F}_p$, bằng tổng của lực ma sát $\vec{F}_{tp}$ và lực $\vec{N}$ — phản lực pháp tuyến của dốc (hình 16, a).

Vì mômen của trọng lực đối với khối tâm của người bằng không, nên người sẽ giữ được thăng bằng và không bị «lật» chỉ khi lực $\vec{F}_p$ đi qua khối tâm của họ.

Nếu ma sát của đế giày với dốc lớn và người đứng trên dốc, thì tổng các lực tác dụng lên người bằng không. Nghĩa là lực $\vec{F}_p$ hướng thẳng đứng và bằng trọng lực.

Khác đi nếu ma sát nhỏ. Trước hết xét trường hợp giới hạn: $\vec{F}_{tp} = 0$. Khi đó người sẽ không ngã nếu họ vuông góc với dốc (hình 16, б). Chỉ trong trường hợp này lực phản ứng $\vec{N}$ của dốc đi qua khối tâm của người. Nhưng hợp lực $\vec{R}$ của các lực $\vec{N}$ và $mg$ khi đó sẽ không bằng không. Nó hướng song song với mặt phẳng nghiêng và bằng $mg\sin\alpha$. Vì vậy người phải trượt xuống với gia tốc $a = g\sin\alpha$.

Nếu ma sát nhỏ nhưng không bằng không, thì gia tốc của người phải nhỏ hơn. Viết định luật II Newton, ta tìm được rằng nó bằng $a = g\sin\alpha - \frac{F_{tp}}{m}$.

⟦folio 38⟧

Hình 16.

Vậy, người có thể giữ thăng bằng nếu họ chạy với gia tốc $a = g \sin \alpha - \frac{F_{\text{тр}}}{m}$, tạo với dốc một góc nào đó được xác định bởi độ lớn của lực ma sát. Thực chất, trong trường hợp này người, cũng như khi đi bộ bình thường, ngã về phía chân đưa ra trước (hình 16, θ). Thăng bằng được giữ, có thể nói, «trung bình» trong khoảng thời gian lớn hơn nhiều thời gian của một bước.

Ф64

Với một quả cầu gỗ và một bình cao chứa nước, người ta tiến hành bốn thí nghiệm: trong thí nghiệm thứ nhất, chúng được cân khi quả cầu nổi trong bình (hình 17, a); trong thí nghiệm thứ hai, khi cân quả cầu được buộc vào đáy bình (hình 17, б); trong thí nghiệm thứ ba, nó được giữ trong bình bằng một thanh mảnh (hình 17, θ); và cuối cùng, trong thí nghiệm thứ tư, quả cầu nổi lên trong khi cân (hình 17, e). Trong thí nghiệm nào khối lượng của quả cân cân bằng bình cùng quả cầu lớn hơn?

Hình 17.

⟦folio 39⟧

Trong thí nghiệm thứ nhất và thứ hai, câu trả lời rất đơn giản: khối lượng của quả cân phải bằng khối lượng của bình chứa nước và quả cầu. Trong thí nghiệm thứ hai, mực nước cao hơn trong thí nghiệm thứ nhất, và do đó lực nước ép lên đáy bình lớn hơn, nhưng lên đáy cũng tác dụng, từ phía quả cầu qua sợi dây, một lực hướng lên trên.

Trong thí nghiệm thứ ba, vào trọng lực tác dụng lên bình, nước và quả cầu còn thêm lực tác dụng lên hệ từ phía thanh. Vậy khối lượng của quả cân phải lớn hơn trong thí nghiệm thứ nhất và thứ hai.

Nếu quả cầu chìm trong nước bắt đầu nổi lên, thì vận tốc của nó tăng cho đến khi lực cản (nó phụ thuộc vào vận tốc) bằng hiệu giữa lực đẩy Archimedes và trọng lực. Sau đó quả cầu sẽ chuyển động đều. Xét trường hợp sau. Vì quả cầu chuyển động đều, nên các lực tác dụng lên nó cân bằng, tức là lực $F$ tác dụng lên quả cầu từ phía nước hướng lên trên và có độ lớn bằng trọng lực $mg$. Theo định luật III Newton, điều đó có nghĩa là từ phía quả cầu tác dụng lên nước một lực — $F$, bằng $mg$. Như vậy, lên đĩa cân sẽ tác dụng một lực có độ lớn bằng tổng các trọng lực tác dụng lên quả cầu, bình và nước. Nghĩa là khối lượng quả cân phải giống như trong thí nghiệm thứ nhất và thứ hai.

Bây giờ xét trường hợp quả cầu nổi lên có gia tốc. Khi đó, vào thời điểm quả cầu vừa bắt đầu nổi lên và lực cản không tác dụng lên nó (tỉ lệ với vận tốc nhỏ của quả cầu), bình có quả cầu nặng bằng trong thí nghiệm thứ ba. Thật vậy, theo định luật III Newton, từ phía quả cầu tác dụng lên nước trong trường hợp này, cũng như trong thí nghiệm thứ ba và thứ tư, chỉ có lực $F_0$, bằng lực đẩy Archimedes tác dụng lên quả cầu từ phía nước. Nó bằng $\rho gV$, trong đó $V$ — thể tích quả cầu và $\rho$ — khối lượng riêng của nước. Điều đó có nghĩa là trong cả hai trường hợp, lực ép lên đĩa cân bằng tổng các trọng lực tác dụng lên nước, bình và lực $F_0$.

Khi gia tốc của quả cầu trong thí nghiệm thứ tư giảm đi do lực cản của nước, thì lực tác dụng lên nước từ phía quả cầu cũng giảm: trong trường hợp này lực có độ lớn bằng hiệu giữa lực Archimedes và lực cản.

Chúng tôi nhận được nhiều thư giải bài toán này, nhưng chỉ có hai độc giả hiểu rõ nó đến cùng: N. Fedin ở Omsk và N. Smirnov ở Gorky.

Ф65

Các bản của tụ điện phẳng được tích điện đến các thế năng $+\varphi$ và —$\varphi$ so với đất. Điện dung của tụ điện tạo bởi các bản bằng $C$, còn điện dung của các tụ điện mà mỗi bản tạo với đất là $C_1$. Điện áp của điện trường giữa các bản sẽ thay đổi bao nhiêu lần nếu nối đất một bản trong số chúng?

Hãy vẽ sơ đồ tương đương của mạch (hình 18). Vì hiệu thế giữa các bản của tụ điện có điện dung $C$ bằng $2\varphi$, nên điện tích của mỗi bản bằng

$$q = C \cdot 2\varphi = 2C\varphi.$$

Trong khi đó, trên các bản tụ điện có điện dung $C_1$ trong trường hợp này có các điện tích $q_1 = C_1\varphi$. Điều đó có nghĩa là điện tích của các bản $II$ bằng

$$Q = q + q_1 = (2C + C_1)\varphi.$$
