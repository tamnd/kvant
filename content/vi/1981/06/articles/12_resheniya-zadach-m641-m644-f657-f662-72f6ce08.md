---
id: 1981-6-resheniya-zadach-m641-m644-f657-f662-72f6ce08
issue: kvant_1981_6
year: 1981
number: "6"
title: Lời giải bài toán M641—M644; F657—F662
rubric: zadachnik-kvanta
rubric_sub: Задачник «Кванта»
page_first: 35
page_last: 42
page_labels: 33-40
tag: J2DA
lang: vi
source: kvant_digital
extraction: vision
content_sha256: d70c489ab1cb7340cd5e63795708588ed52e7b57214dd479bce332ad1d8ca971
prompt_sha256: draft-1
translated_from: content/ru/1981/06/articles/12_resheniya-zadach-m641-m644-f657-f662-72f6ce08.md
source_content_sha256: 1d56150f0ae82d3d6cd55cb307b7ecd8efed30752fcacf85c08087e449c0749e
translation_model: draft
translation_run: vi-draft-2026-10-31
translation_quality: draft
---

⟦folio 33⟧

Lời giải bài toán

M641. Cho hình lục giác đều ABCDEF tâm O. Điểm M và N là trung điểm của các cạnh CD và DE. Các đường thẳng AM và BN cắt nhau tại điểm L. Chứng minh rằng
a) tam giác ABL và tứ giác DMLN có diện tích bằng nhau;
b) ALO = OLN = 60°;
c) OLD = 90°.

Tất cả các phát biểu bài toán đều dễ dàng có được từ một quan sát: khi quay 60° quanh tâm O, tứ giác AMCB được ánh xạ lên tứ giác BNDC.
Thật vậy, khi xoay $R_0^{60°}$ (ngược chiều kim đồng hồ), điểm A đi tới điểm B, điểm B đến điểm C, cạnh CD ánh xạ tới cạnh DE, sao cho M ở giữa của cạnh CD đi vào giữa N của cạnh DE (xem hình). Do đó, tứ giác AMCB và BNDC là hai tứ giác tắc nghẽn nên diện tích bằng nhau. Trừ diện tích của tứ giác BCML khỏi các diện tích bằng nhau này, chúng ta thu được diện tích bằng nhau, tức là tam giác ABL và tứ giác DMLN có kích thước bằng nhau.

Vì khi quay $R_0^{60°}$ tia AM được ánh xạ lên tia BN nên góc giữa các hướng của các tia này bằng góc quay, tức là $ALB = 60°$. Vì vậy, $ALN = 120°$. Chúng tôi trình bày hai chứng minh $ALO = OLN = 60°$ và $OLD = 90°$.

1°. Hãy sử dụng thực tế hiển nhiên này: nếu hai đường thẳng cắt nhau tại điểm K và cách đều điểm P thì đường thẳng PK đóng vai trò là phân giác của góc giữa hai đường thẳng này (chứa điểm P). Vì điểm O cách đều các đường thẳng AM và BN nên OL là ma trận nhị phân của góc ALN, tức là $ALO = OLN = 60°$. Vì điểm D cách đều các đường thẳng AM và BN bằng nhau (cùng khoảng cách với C cách đường thẳng AM), $NLD = DLM = 30°$, tức là $OLD = 90°$.

2°. Một đường tròn có thể được mô tả xung quanh tứ giác DMON, vì các góc ở đỉnh M và N của nó là góc vuông. Điểm L cũng thuộc đường tròn này. Điều này xuất phát từ thực tế là trong tứ giác DMLN tổng các góc tại đỉnh D và L bằng 180°. Nhận thấy rằng $ODN = 60°$, chúng ta áp dụng định lý góc nội tiếp. Sau đó chúng ta nhận được $OLN = ODN = 60°$ và $OLD = OMD = 90°$.

E. Gotman

M642. Chứng minh rằng mọi số tự nhiên đều có thể biểu diễn dưới dạng $a_0 + 2a_1 + 2^2a_2 + \dots + 2^n a_n$, trong đó mỗi số là $a_k = 0, -1$ hoặc 1 và $k \cdot a_{k+1} = 0$ với mọi $0 \leq k \leq n-1$, và cách biểu diễn như vậy là duy nhất.

Xem xét các lượt xem bắt buộc
$$A = a_0 + 2a_1 + 2^2a_2 + \dots + 2^n a_n$$
(*)
($a_k = 0, -1$ hoặc 1, $a_k \cdot a_{k+1} = 0$) đối với một số số tự nhiên dễ dàng thấy rằng
1) dấu cuối cùng+dừng ở $2^n$ (chữ số có nghĩa nhất $a_n = +1$) cho các số A từ $2^n - 2^{n-2} - 2^{n-4} - \dots$ đến $2^n + 2^{n-2} + 2^{n-4} + \dots$ (ví dụ: trong bảng của chúng tôi ở lề, dấu cuối cùng+dừng ở $2^3$ cho các số A từ $2^3 - 2 = 6$ đến $2^3 + 2 = 10$, tại $2^4$ cho các số A từ $2^4 - 2^2 = 1 = 11$ đến $2^4 + 2^2 + 1 = 21$, v.v.);
2) dấu đầu tiên (chữ số phụ $a_0 \neq 0$) được lặp lại định kỳ với khoảng thời gian là 4, nghĩa là nó chỉ phụ thuộc vào số dư khi chia A cho 4 ($a_0 = 0$ thậm chí còn được lặp lại thường xuyên hơn - với khoảng thời gian là 2).

Hai cách chứng minh về biểu diễn mong muốn (*) và tính duy nhất của nó được xây dựng trên hai người quan sát này. Cả hai cách chứng minh này đều được thực hiện bằng quy nạp, nghĩa là một phát biểu hợp lệ cho một số A cho trước được suy ra từ tính đúng đắn của nó đối với mọi số A.

1°. Chúng ta hãy biểu thị số $2^n + 2^{n-2} + 2^{n-4} + \dots$ bằng $M_n$ (số hạng cuối cùng ở đây là $2^1 = 2$ cho số lẻ $n$ và $2^0 = 1$ cho số chẵn $n$). Hãy chứng minh rằng mỗi số $A \leq M_n$ được biểu diễn dưới dạng (*) một cách duy nhất và $a_n = 1$ đối với các số
$$2^n - M_{n-2} \leq A \leq 2^n + M_{n-2} = M_n.$$

⟦folio 34⟧

MB43. Các thẻ có số 1, 2, ..., 32 được xếp theo thứ tự. Được phép loại bỏ bất kỳ số lượng thẻ nào ở phía trên và đặt chúng vào giữa một số thẻ còn lại hoặc bên dưới nó mà không thay đổi thứ tự của cả hai, nếu không thì tùy ý.

Hoạt động này được gọi là di chuyển em.

1. Chứng minh rằng sau 5 nước đi bạn có thể a) sắp xếp lại các quân bài theo thứ tự ngược lại;
6) sắp xếp các thẻ theo thứ tự bất kỳ.
11. Chứng minh rằng không phải thứ tự bài nào cũng có thể lấy được sau 4 nước đi.

Hình 1.

Chúng ta có thể (vì chúng ta chứng minh bằng quy nạp) coi phát biểu của mình đã được chứng minh với các số $A$ không vượt quá $M_{n-2}$. Bằng cách sử dụng điều này, chúng ta thu được biểu diễn (*) cho bất kỳ số nguyên $A$ nào từ khoảng (1). Thật vậy, $A=2^n$ hoặc $1 \leqslant A-2^n \leqslant M_{n-2}$ hoặc $1 \leqslant 2^n-A \leqslant M_{n-2}$. Bằng cách cộng biểu diễn của số $A-2^n$ với $2^n$ hoặc trừ biểu diễn của số $2^n-A$ khỏi nó, chúng ta thu được biểu diễn (*) cho $A$.

Lưu ý rằng

$$2^n-M_{n-2}-1=M_{n-1};$$

đẳng thức này trở nên rất mạnh nếu nó được viết như thế này:

$$2^n-1=M_{n-2}+M_{n-1}=2^{n-1}+2^{n-2}+2^{n-3}+\dots+1.$$

Như có thể thấy từ đẳng thức (2), các khoảng (1) cho $n=1, 2, 3, \dots$ không trùng nhau và lấp đầy toàn bộ tập hợp số tự nhiên $N$, do đó biểu diễn (*) tồn tại cho mọi $A$. Từ đây tính duy nhất của nó cũng trở nên rõ ràng: cho $A \in \mathbb{N}$ chữ số $n$ của chữ số đứng đầu $a_n=1$ được xác định duy nhất và phép cộng $|2^n-A|$ được biểu diễn một cách duy nhất bằng giả định quy nạp.

$$2^\circ.$$ Nếu $A$ là số chẵn thì $a_0=0$ và cách biểu diễn (*) của số $A=2m$ thu được từ cách biểu diễn số nhỏ hơn $m$ “được dịch chuyển” bởi một chữ số. Nếu $A$ là số lẻ thì $a_0=\pm 1$ và $a_1$ phải bằng 0; do đó, số $A-a_0$ được chia cho 4 và cách biểu diễn (*) của số $A=4m+a_0$ được lấy từ cách biểu diễn số nhỏ hơn $m$ bằng cách “vuốt” thành hai chữ số và cộng số $a_0$ sang bên trái. Trong tất cả các trường hợp này, tính duy nhất của cách biểu diễn số $A$ suy ra từ tính duy nhất của cách biểu diễn số $m$.

Cách biểu diễn duy nhất của số 1 rất giống nhau: nếu $n>1$ và $|a_n|=1$ thì $|a_0+a_1 \cdot 2+\dots+a_n \cdot 2^n| \geqslant 2^n-(2^{n-2}+2^{n-4}+\dots) \geqslant 2$.

N. Vasiliev

◆

Hãy để chúng tôi trình bày hai lời giải trong số bài toán này.

Đầu tiên là lời giải. Chúng ta sẽ giả định rằng các quân bài trong chồng bài được sắp xếp theo thứ tự ngẫu nhiên. Hãy để chúng tôi chứng minh rằng chúng có thể được sắp xếp theo năm chuyển động, nhưng không phải lúc nào cũng theo bốn chuyển động. Như vậy bài toán sẽ được giải quyết.

Chúng ta hãy gọi một đoạn là một nhóm thẻ nằm thành một hàng, số lượng thẻ tăng theo khoảng cách tính từ đầu ngăn xếp. Độ dài của một đoạn sẽ là số lượng thẻ có trong đó.

Nếu có hai phân đoạn, thì bạn luôn có thể thực hiện mà không cần thay đổi thứ tự của các thẻ trong mỗi phân đoạn đó bằng cách di chuyển chúng để có được một phân đoạn bao gồm các thẻ từ các phân đoạn này và chỉ từ chúng. Chúng ta sẽ nói rằng một phân đoạn như vậy có được bằng cách hợp nhất hai phân khúc. Rõ ràng là độ dài của kết quả hợp nhất bằng tổng độ dài của các đoạn hợp nhất.

Trước tiên, chúng ta hãy đánh dấu 32 đoạn có cùng độ dài trong một chồng thẻ và sau đó thực hiện các chuyển động như sau:

1) chia ngăn xếp làm đôi;
2) hợp nhất các phân đoạn tương ứng từ nửa thứ nhất và nửa thứ hai của ngăn xếp theo cặp;
3) Hãy để chúng tôi lưu ý các phân đoạn là kết quả của việc hợp nhất điểm 2).

Chúng tôi sẽ lặp lại thao tác này năm lần (Hình 1 cho thấy điều gì xảy ra với các phân đoạn thu được sau lần hợp nhất thứ hai). Độ dài của các đoạn phồng lên trước khi chuyển bằng một nửa chiều dài của các đoạn phồng lên sau đó (xem Hình 1). Do đó, sau thao tác thứ năm, độ dài của đoạn sưng lên (duy nhất!) Sẽ bằng $2^5=32$. Điều này chứng minh các câu a) và b) bài toán (đối với điểm a) các chuyển động cần thiết đã được đưa ra ở lề).

Để chứng minh rằng các quân bài được xếp ngẫu nhiên không thể xếp thứ tự trong 4 nước đi, chúng tôi giới thiệu

⟦folio 35⟧

đây là một khái niệm Hãy biến hai quân bài liền kề trong chồng thành một cặp khiếm khuyết nếu quân bài có số cao hơn cao hơn quân bài có số thấp hơn.

Bổ đề. Nếu có $n > 1$ cặp bị lỗi trong một chồng thì sau khi di chuyển sẽ có ít nhất $m = \left[ \frac{n}{2} \right]$ cặp bị lỗi trong đó.

Bằng chứng. Chia ngăn xếp thành hai, chúng ta thu được ít nhất $m$ cặp bị lỗi ở ít nhất một trong các ngăn xếp. Thật vậy, đặt có các cặp bị lỗi $k$ và $l$ trong một ngăn xếp. Nếu chúng ta giả sử rằng $k \leq m - 1$ và $l < m$ thì $k + l < 2m - 1 \leq n - 1$. Tuy nhiên, phải có $k + l \geq n - 1$, vì nhiều nhất một cặp bị lỗi có thể “phân kỳ” khi ngăn xếp được chia. Vì vậy, $k \geq m$ hoặc $l \geq m$.

Bây giờ hãy lưu ý rằng nếu bất kỳ thẻ nào được chèn vào giữa các thẻ của một cặp bị lỗi thì ít nhất một cặp bị lỗi sẽ được hình thành (đảm bảo rằng đây chính là thẻ được lắp vào). Điều này chứng minh bổ đề.

Bây giờ giả sử có hơn 15 cặp bị lỗi trong ngăn xếp. Áp dụng bổ đề đã được chứng minh bốn lần, chúng ta thấy rằng sau bốn lần di chuyển, ít nhất một cặp bị lỗi vẫn còn trong ngăn xếp.

Một bài toán thú vị nảy sinh liên quan đến bổ đề cuối cùng: biết số cặp bị lỗi của một cách sắp xếp, hãy xác định chính xác số lượng chuyển động tối thiểu cần thiết để đạt được sự sắp xếp này từ một ngăn xếp có thứ tự. Hóa ra nếu $N$ là số cặp vị trí bị lỗi thì chuyển động $\left[ \log_2 N \right] + 1$ là cần thiết.

Thứ hai lời giải. I 6) Hãy xem xét thao tác ngược lại của việc di chuyển: chúng ta rút một số thẻ từ các vị trí tùy ý trong ngăn xếp và đặt chúng lên trên. Trong trường hợp này, thứ tự tương đối của cả môi trường được rút ra và phần còn lại của thẻ không thay đổi. Hãy để chúng tôi chứng minh một phát biểu tổng quát hơn: các thẻ $2^n$, được sắp xếp theo bất kỳ thứ tự nào, có thể được sắp xếp theo các chuyển động ngược lại $n$.

Ta tiến hành chứng minh bằng quy nạp.

Để đặt hai lá bài ($n = 1$), một nước đi ngược lại là đủ. Hãy chứng minh rằng để đặt mua thẻ $2^k$, chuyển động ngược lại $k$ là đủ. Hãy để chúng tôi chứng minh rằng quân bài $2^{k+1}$ luôn có thể được sắp xếp theo các nước đi ngược lại $k+1$.

Hãy xem xét việc sắp xếp các thẻ $2^{k+1}$ thành một chồng. Các chồng bài được đánh số từ 1 đến $2^k$ (gọi là ngăn xếp này là màu đỏ) và được đánh số từ $2^k + 1$ đến $2^{k+1}$ (gọi là ngăn xếp này là màu xanh) - với vị trí tương đối của quân bài trong mỗi ngăn xếp giống như trong chồng quân bài $2^{k+1}$ - có thể được sắp xếp theo quy nạp trong các nước đi ngược lại $k$. Hãy biểu thị những chuyển động này bằng $A_1, A_2, \dots, A_k$ đối với ngăn xếp màu đỏ và $B_1, B_2, \dots, B_k$ đối với ngăn xếp màu xanh lam.

Bây giờ chúng ta hãy thực hiện $k$ chuyển động đảo ngược của một chồng lớn (của các thẻ $2^{k+1}$) như sau: trong chuyển động đảo ngược thứ $i$, chúng ta rút ra các thẻ đỏ, những thẻ này sẽ được rút ra khi di chuyển $A_i$, và các thẻ xanh, sẽ được rút ra khi di chuyển $B_i$, sau đó chúng ta đặt cả hai thẻ này lên trên cùng của ngăn xếp - cái này ở dưới cái kia (Hình 2 sẽ giúp bạn hiểu những gì đang xảy ra). Sau $k$ các thao tác như vậy, các cọc màu đỏ và xanh lam sẽ được sắp xếp. Còn lại là nước đi cuối cùng, thứ $(k+1)$ để rút các quân bài của cọc màu đỏ và đặt chúng lên trên.

II. Hãy để chúng tôi chứng minh rằng nếu có nhiều hơn $2^n$ thẻ trong một ngăn xếp, thì trong các nước đi $n$ chúng không thể được sắp xếp theo thứ tự ngược lại - theo thứ tự số giảm dần.

Ta tiến hành chứng minh bằng quy nạp. Tại $n = 1$ số lượng thẻ trong ngăn xếp ít nhất là ba. Vì khi di chuyển chúng ta lấy ít nhất hai quân bài từ phía trên hoặc để lại ít nhất hai quân bài nên sau một nước đi chúng ta sẽ tìm thấy hai quân bài có thứ tự tương đối không thay đổi.

Giả sử câu bài toán đúng với $n = k$. Đối với $n = k + 1$, chúng tôi giả sử điều ngược lại, nghĩa là, chúng tôi giả sử điều đó đối với $k + 1$

⟦folio 36⟧

đã di chuyển đã đảo ngược thứ tự trong một ngăn xếp chứa nhiều hơn $2^{k+1}$ thẻ. Hãy xem điều gì đang xảy ra.

Trong lần di chuyển đầu tiên, ít nhất các thẻ $2^{k+1}$ bị xóa ở trên hoặc không được chọn, do đó, có một chồng thẻ $2^{k+1}$ có thứ tự tương đối không thay đổi sau lần di chuyển đầu tiên. Nhưng theo giả thuyết quy nạp, đối với các nước đi $k$ còn lại, các quân bài trong bộ bài này không thể sắp xếp theo thứ tự ngược lại. Kết quả mâu thuẫn chứng minh khẳng định bài toán.

Yu. Lysov, V. Turchininov

M644. a) Chứng minh rằng tồn tại một đơn vị lồi 1980 có độ dài các cạnh là 1, 2,..., 1980, tất cả các cạnh đều có kích thước bằng nhau.
6) Liệu một ngày trong tuần năm 1981 như vậy có tồn tại không?

Chứng minh rằng nếu $n$ không phải là lũy thừa của một số nguyên tố, tức là $n = p \cdot q$, $n > 3$ và $p$ và $q$ là các số nguyên tố cùng nhau khác một thì luôn có thể dựng được một $n$-giác có các cạnh có độ dài 1, 2,..., $n$, song song với các cạnh của số nguyên tố $n$-gon. Vì $1980 = 4 \cdot 495$ và $1981 = 7 \cdot 283$, chúng ta sẽ giải những bài toán này.

Hãy xem xét một $n$-gon ($n = p \cdot q$) thông thường. Chúng ta hãy chọn trong số các đỉnh $p$ của nó tạo thành một $p$-giác đều (trong hình $n=15$, $p=3$, $q=5$). Bây giờ, hãy xem xét $p$ bộ đỉnh $q$ của $n$-giác (thông thường) của chúng ta sao cho trong mỗi bộ các đỉnh này tạo thành một $q$-giác đều và đỉnh đầu tiên của bộ thứ $i$ trùng với đỉnh thứ $i$ của $p$-gon đã chọn (xem hình). Vì các số $p$ và $q$ là số nguyên tố cùng nhau nên các tập hợp này không giao nhau. Do đó, chúng tôi đang tìm cách sử dụng hết tất cả các đỉnh của $n$-gon.

Bây giờ chúng ta sẽ “sắp xếp” $p$ bộ vectơ $q$. Ta sắp xếp các vectơ $q$ đầu tiên có độ dài 1, 2,..., $q$ như sau: đặt vectơ đầu tại các đỉnh kế tiếp của $q$-giác đầu tiên và lấy hướng của mỗi vectơ trùng với hướng cạnh của $n$-giác, giáp với đỉnh tương ứng của $q$-giác (hướng đi ngang là cố định). Chúng ta hãy biểu thị tổng các vectơ của tập hợp đầu tiên bằng $\vec{b}_1$.

Tập vectơ $q$ thứ hai được lấy theo cách tương tự như tập thứ nhất, chỉ khác là nó được “tạo ra” bởi các đỉnh của $q$-gon thứ hai. Tổng các vectơ $\vec{b}_2$ của tập thứ hai rõ ràng thu được từ vectơ $\vec{b}_1$ bằng cách quay qua một góc $360^\circ/p$ quanh tâm của $n$-giác. Bằng cách tăng độ dài của mỗi vectơ của tập thứ hai lên $q$ một, chúng ta không thay đổi tổng $\vec{b}_2$, vì sự gia tăng đó là việc cộng các vectơ $q$ tạo thành một $q$-giác đều (tổng của chúng là $\vec{0}$).

Vì vậy, chúng ta có thể nhận được $p$ bộ vectơ $q$: hướng của vectơ của tập hợp thứ $i$ được xác định bởi các đỉnh của $i$-th $q$-giác và độ dài của chúng là $1+q(i-1)$, $2+q(i-1)$,..., $qi$. Tổng $\vec{b}_i$ của các vectơ này thu được từ $\vec{b}_1$ bằng cách quay qua một góc $360^\circ \cdot (i-1)/p$ xung quanh tập hợp các $n$-giác.

Từ kết quả trên, các vectơ $\vec{b}_i$ tạo thành một $p$-giác đều. Do đó, tổng của chúng bằng 0 và do đó tổng các vectơ được xây dựng $pq=n$ bằng 0, hướng của chúng tương ứng với hướng của các cạnh bên phải $n$-gon của chúng ta và độ dài bao gồm tất cả các số tự nhiên từ 1 đến $n$. Những gì còn lại là sự sắp xếp tuần tự của các vectơ $n$ này sao cho hướng của chúng tương ứng với hướng của các cạnh kế tiếp của một $n$-giác đều.

Đối với $n=p^k$, trong đó $p$ là số nguyên tố, không thể xây dựng một $n$-giác như vậy, nhưng chúng ta không biết bằng chứng cơ bản nào cho thực tế này.

Yu. Lysov

F657. Bán kính cong của hai bong bóng xà phòng giống hệt nhau quay ngược nhau bằng $R$. Sau cuộc trò chuyện
36

⟦folio 37⟧

giữa các bong bóng lonnyla, một bong bóng có bán kính $R_1$ đã được hình thành. Tìm áp suất khí quyển. Hệ số căng bề mặt của dung dịch xà phòng là σ.

Hình 1.

Hình 2. $\overrightarrow{OAB} = 30^\circ$;
$$|OB| = \frac{1}{2}|OA| = \frac{1}{2}R;$$
$$r = \sqrt{R^2 - \frac{R^2}{4}} = \frac{R\sqrt{3}}{2};$$
$$h = |OD| - |OB| = R - \frac{R}{2} = \frac{R}{2}.$$

F658. Từ một quả bóng chứa hơi kali có độ tinh khiết cao, một chùm nguyên tử phát ra qua một ống hẹp nằm ngang. Xác định nhiệt độ hơi nếu trên một đường nằm ngang có chiều dài $l = 50$ cm độ dịch chuyển dọc trung bình của các nguyên tử là $h = 3,2$ µm.

trong đó $p_0$ là áp suất khí quyển, $4\sigma/R$ là áp suất dư trong bong bóng dưới bề mặt cong có bán kính $R$ (trước đá σ hệ số là 4 chứ không phải 2, vì màng xà phòng có hai bề mặt). Điều kiện áp suất bằng nhau ở bên phải vách ngăn có nghĩa là vách ngăn phẳng (nếu không thì áp suất trong các bong bóng phải khác nhau bởi lượng áp suất dư thừa dưới bề mặt cong của vách ngăn). Vì các bong bóng giống hệt nhau nên mặt phẳng phân chia nằm ở khoảng cách bằng nhau tính từ tâm của các bong bóng.

Ba lực tác dụng lên bất kỳ phần nào của bề mặt màng, màng tiếp nhận và vách ngăn: hai lực căng từ các màng tạo thành bong bóng của chính chúng và một lực căng từ màng ngăn. Vì giá trị tuyệt đối của các lực này là như nhau nên trong điều kiện cân bằng, các lực này hướng một góc $120^\circ$ với nhau (Hình 1).

Do đó, ở trạng thái ban đầu của không khí trong bong bóng ở áp suất $p = p_0 + 4\sigma/R$, thể tích $V = 2\left(\frac{4}{3}\pi R^3\right) - V'$ chiếm, trong đó $V' = 2 \cdot \frac{1}{6} \pi h (3r^2 + h^2)$ là thể tích của hai đoạn hình cầu “cắt đứt” bởi một vách ngăn từ bong bóng (Hình 2). Như có thể thấy trong Hình 2, bán kính của vách ngăn là $\tau = R\sqrt{3}/2$, chiều cao của đoạn bóng là $h = R/2$ và

$$V' = \frac{1}{3} \pi \frac{R}{2} \left(3 \frac{3R^2}{4} + \frac{R^2}{4}\right) = \frac{5}{12} \pi R^3,$$

$$V = \frac{8}{3} \pi R^3 - \frac{5}{12} \pi R^3 = \frac{9}{4} \pi R^3.$$

Sau khi vách ngăn vỡ ra, không khí trong bong bóng có bán kính $R_1$ chiếm thể tích $V_1 = \frac{4}{3} \pi R_1^3$ ở áp suất $p_1 = p_0 + \frac{4\sigma}{R_1}$.

Chúng ta giả định rằng nhiệt độ không khí trong bong bóng không đổi (bằng nhiệt độ môi trường). Sau đó $\frac{p}{p_1} = \frac{V_1}{V}$, hoặc

$$\frac{p_0 + \frac{4\sigma}{R}}{p_0 + \frac{4\sigma}{R_1}} = \frac{16}{27} \frac{R_1^3}{R^3}.$$

Từ đây chúng ta tìm thấy áp suất khí quyển:

$$p_0 = \frac{4\sigma(16R_1^2 - 27R^2)}{27R^3 - 16R_1^3}.$$

(Từ biểu thức cho $p_0$ suy ra rằng bán kính $R$ và $R_1$ có ​​liên hệ với nhau bởi mối quan hệ

$$\frac{3^3\sqrt{4}}{4} < \frac{R_1}{R} < \frac{3\sqrt{3}}{4}.$$

Hãy tự mình xem.)

T. Petrova

◆

Nhiệt độ của hơi được xác định bởi tốc độ trung bình (chính xác hơn là trung bình) của các phân tử hơi:

$$T \approx \frac{\mu v^2_{cp}}{3R}.$$

Để xác định nhiệt độ, bạn cần tìm $v_{cp}$.

Sự trộn theo chiều dọc xảy ra do lực căng. Thời gian t chuyển động của các phân tử, độ dài $l$ của các tên được duyệt trong thời gian này là các chùm tia và sự trộn lẫn theo phương thẳng đứng của các phân tử $h$ theo tỷ lệ $\tau = l/v_{cp} = \sqrt{2h/g}$, từ đó

$$v_{cp} = l \sqrt{\frac{g}{2h}}.$$

⟦folio 38⟧

Thay (2) vào (1), ta tìm được
$$T \approx \frac{\mu l^2 g}{6 R h} \approx 6 \cdot 10^2 \text{ K}.$$
(Không cần độ chính xác cao hơn của các phép tính, vì chúng ta đã ước tính khá đại khái tốc độ chuyển động trung bình của các phân tử, sử dụng vận tốc trung bình.)

A. Zilberman

F659. Một chiếc máy nhỏ nặng $m=200$ kg cắt trong quá trình vận hành do khối lượng nặng không đồng nhất, cắt ở tốc độ góc 600 vòng / phút. Để đơn giản hóa việc lựa chọn xích sàn trong xưởng lắp đặt máy, một miếng đệm đàn hồi có độ dày $h=10$ cm làm bằng vật liệu có mô hình đàn hồi $E=3,1 \times 10^8 \text{ H/m}^2$ đã được đặt dưới khung. Diện tích đáy của giường là $S=2 \text{ m}^2$. Việc lắp đặt miếng đệm có làm giảm sự chồng chéo có thể lựa chọn không?

Dao động của máy do máy quay không cân bằng gây ra dẫn đến xuất hiện lực điều hòa $F=F_0 \sin \omega t$ tác dụng từ máy lên giá đỡ ($F_0$ - biên độ, $\omega=2\pi f$ - tần số tròn, $f$ - tần số lực). Sự tương tác giữa máy và trần, được ngăn cách bằng một miếng đệm đàn hồi, có thể được sử dụng trên cơ sở một hệ đơn giản gồm hai khối lượng chính xác $m$ và $M$, được nối với nhau bằng một lò xo có độ cứng $k$ (xem hình; vai trò của các khối lượng được thực hiện bởi sự tương ứng của máy và trần nhà, lò xo bắt chước miếng đệm giữa chúng). Độ cứng $k$ của lò xo (độ cứng của miếng đệm) bằng
$$k = \frac{ES}{h}.$$

Trọng lượng của sàn $M$ lớn hơn rất nhiều so với trọng lượng của máy $m$. Thật vậy, nếu sàn được làm bằng bê tông cốt thép (mật độ khoảng 2500 kg/$\text{m}^3$) và có độ dày xấp xỉ 0,2 m thì khối lượng của chỉ một mét vuông (mật độ bề mặt) của sàn là 500 kg, lớn hơn nhiều so với trọng lượng của máy (theo 200 kg).

Cho $x_1$ và $x_2$ là hỗn hợp của các khối lượng $m$ và $M$ dọc theo trục $OX$ so với tọa độ của các khối lượng ở trạng thái không bị kích thích. Khi đó gia tốc khối lượng theo định luật II Newton có thể viết dưới dạng
$$\vec{a}_1 = x_1'' = -\frac{k \Delta h}{m} + \frac{F}{m} = \frac{k}{m} (x_2 - x_1) + \frac{F_0}{m} \sin \omega t,$$
$$\vec{a}_2 = \frac{k \Delta h}{M} = \frac{k}{M} (x_1 - x_2).$$

Đối với các dao động điều hòa $x_1 = A_1 \sin \omega t$, $x_2 = A_2 \sin \omega t$, $a_1 = -\omega^2 A_1 \sin \omega t$, $a_2 = -\omega^2 A_2 \sin \omega t$, trong đó $A_1, A_2$ lần lượt là biên độ dao động của các khối lượng $m$ và $M$. Thay các biểu thức này vào (2), ta được
$$\left( -\omega^2 + \frac{k}{m} \right) A_1 - \frac{k}{m} A_2 = \frac{F_0}{m},$$
$$- \frac{k}{m} A_1 + \left( -\omega^2 + \frac{k}{m} \right) A_2 = 0,$$

hoặc
$$- \omega^2 A_1 + \frac{k}{m} \left( A_1 - A_2 \right) = \frac{F_0}{m},$$
$$- \omega^2 A_2 - \frac{k}{m} \left( A_1 - A_2 \right) = 0.$$

Từ đây là
$$A_1 - A_2 = \frac{F_0}{m} \cdot \frac{1}{-\omega^2 + \frac{k(m+M)}{mM}} = \frac{F_0}{m(\omega_p^2 - \omega)},$$
Ở đâu
$$\omega_p = \sqrt{\frac{k(m+M)}{mM}}$$

- Tần số tròn cộng hưởng của các dao động điều hòa của một hệ khối lượng nối với nhau bằng một lò xo. Tại $M \gg m$
$$\omega_p \approx \sqrt{\frac{k}{m}}.$$

Từ (2') (2'') ta xác định được biên độ trộn khối $M$:

⟦folio 39⟧

$$A_2 = \frac{F_0}{(m+M)\omega^2} \cdot \frac{1}{\left(\frac{\omega}{\omega_p}\right)^2 - 1}.$$

Trong trường hợp không có miếng đệm, lực $F$ truyền gia tốc cho máy hệ thống - trùng với khối lượng $m+M$

$$|\vec{a}_0| = \frac{|\vec{F}|}{m+M}.$$

Biên độ $A_0$ của dao động trong trường hợp này được tìm thấy từ điều kiện $a_0 = -\omega^2 A_0$ sin $\omega t$:

$$A_0 = -\frac{F_0}{(m+M)\omega^2}.$$

Như vậy, tỉ số giữa biên độ trộn sàn sau khi lắp gioăng và trước đó bằng

$$\frac{A_2}{A_0} = \frac{1}{1 - \left(\frac{\omega}{\omega_p}\right)^2} = \frac{1}{1 - \left(\frac{f}{f_p}\right)^2},$$

(4)

Ở đâu

$$f_p = \frac{1}{2\pi} \omega_p \approx \frac{1}{2\pi} \sqrt{\frac{k}{m}} = \frac{1}{2\pi} \sqrt{\frac{ES}{hm}} \approx 885 \text{ Гц}$$

(xem (1) và (3)). Vì theo điều kiện $f = 600$ Hz nên từ (4) ta tìm được

$$\frac{A_2}{A_0} = \frac{1}{1 - \left(\frac{600}{885}\right)^2} \approx 1,85,$$

tức là rung sau khi lắp gioăng sẽ thành công.

Làm thế nào để giảm tác động lên sàn? Như có thể thấy từ công thức (4), điều này có thể đạt được bằng cách chọn các tham số của miếng đệm sao cho thỏa mãn điều kiện $f_p \ll f$, nghĩa là bạn nên chọn vật liệu cho miếng đệm có kiểu dáng Young nhỏ hoặc tăng độ dày của miếng đệm. Vì vậy, nếu $E = 3,1 \cdot 10^6$ N/m$^2$, tức là nhỏ hơn 100 lần so với điều kiện bài toán, thì bạn có thể nhận được

$$\left|\frac{A_{20}}{A'_{20}}\right| \approx 0,02,$$

nghĩa là độ rung giảm đi đáng kể.

R. Vinokur

F660. Phao được làm bằng vật liệu đồng nhất, có hình đậu lăng - một vật thể, được giới hạn bởi hai bề mặt hình cầu có bán kính $R_1 = R_2 = R = 3$ cm. Độ dày tối đa của chechevitsa là $h = 4$ cm; khối lượng của đậu lăng là $m_1 = 5$ cm. Một kim đan có chiều dài $l = 10$ cm và khối lượng $m_2 = 3$ cm được đưa vào phao dọc theo toàn bộ độ dày dọc theo trục đối xứng. Vị trí của phao có ổn định khi nó nổi trên mặt nước của chechevy không? Hãy xem xét rằng ít đậu lăng được ngâm trong chất lỏng.

Để đảm bảo rằng ít đậu lăng được ngâm trong chất lỏng hơn, bạn có thể sử dụng dữ liệu được cung cấp trong điều kiện bài toán. Điều kiện cân bằng của phao ở vị trí “kim đan lên” là $\vec{F}_T + \vec{F}_A = \vec{0}$, hoặc $\vec{F}_T - \vec{F}_A = \vec{0}$, trong đó $\vec{F}_T = (m_1 + m_2) |\vec{g}|$ là lực hấp dẫn tác dụng lên phao bằng kim đan, $\vec{F}_A = \varrho_B |\vec{g}| V'$ là lực nổi ($V'$ là thể tích của phần phao chìm trong nước). Từ sự bình đẳng

$$(m_1 + m_2) |\vec{g}| = \varrho_B |\vec{g}| V'$$

hãy xác định $V'$:

$$V' = \frac{m_1 + m_2}{\varrho_B} = 8 \text{ см}^3.$$

Thể tích của đậu lăng poling (thể tích của đoạn hình cầu) bằng

$$V = \frac{1}{6} \pi h_1 (3r^2 + h_1^2) \approx 29 \text{ см}^3$$

(xem hình 1). Điều kiện $V' < V$ có nghĩa là có ít đậu lăng được ngâm trong nước hơn.

Bây giờ chúng ta hãy xem xét vấn đề ổn định của phao ở vị trí “lên tiếng”. Chúng ta sẽ giả sử rằng với một độ lệch nhỏ của phao, khi các nan hoa tạo một góc nhỏ $\alpha$ với phương thẳng đứng (Hình 2) thì phần phao chìm trong nước

⟦folio 40⟧

vẫn có dạng hình cầu và mớn nước không thay đổi. (Độ lệch của phao là sự quay của nó quanh điểm $O$, tức là xung quanh tâm quả cầu, giới hạn phần dưới của phao.) Điều kiện này có nghĩa là, như trước đây, $\vec{F}_{\tau} + \vec{F}_{\mathrm{A}} = 0$. Nếu do sự sai lệch, xuất hiện mômen lực có xu hướng đưa phao về vị trí cũ thì vị trí này - “đan kim lên” - ổn định; nếu mômen lực làm cho phao tiếp tục lệch thì vị trí “lên tiếng” không ổn định.

Trong khi phao ở vị trí cân bằng, các lực $\vec{F}_{\tau}$ và $\vec{F}_{\mathrm{A}}$ tác dụng dọc theo một đường thẳng - phương thẳng đứng đi qua nan hoa. Lực $\vec{F}_{\tau}$ tác dụng tại điểm $C$ - tại tâm khối của phao có nan hoa, và lực $\vec{F}_{\mathrm{A}}$ tác dụng tại điểm $O$ (lực $\vec{F}_{\mathrm{A}}$ là kết quả của lực ép do nước tác dụng lên phao). Điểm $C$ nằm cách đáy phao một khoảng $x = |DC|$ (xem Hình 2) sao cho

$$m_1 \left( \frac{l}{2} - x \right) = m_2 \left( x - \frac{h}{2} \right);$$

từ đây

$$x = \frac{m_1 l/2 + m_2 h/2}{m_1 + m_2} = 3,125 \text{ cm.}$$

Điểm $O$ nằm cách đáy phao $|DO| = R = 3$ cm. Do đó, điểm $C$ nằm phía trên điểm $O$.

Với một độ lệch nhỏ của phao (khi quay quanh $O$), các điểm tác dụng của lực $\vec{F}_{\mathrm{A}}$ vẫn giữ nguyên - điểm $O$; điểm $C$ sẽ được trộn với điểm dọc $DC$. Do đó, khi phao bị lệch hướng, sẽ có một vài lực tác dụng lên nó; mô men của các lực này có xu hướng làm phao quay lệch xa hơn so với vị trí cân bằng (trong Hình 2 - ngược chiều kim đồng hồ).

Do đó, phao “đan kim lên” là vị trí cân bằng không ổn định.

D. Kuznetsov

F661. Hình vẽ thể hiện đặc tính dòng điện-điện áp của hai điện trở không bị giam giữ $R_1$ và $R_2$. Điểm, sự nghẹt thở qua các điện trở và một nguồn có EMF $\varepsilon = 10$ V và điện trở trong $r = 2$ Ohm sẽ như thế nào, nếu nối các điện trở với nguồn, nối chúng a) nối tiếp, b) song song?

Nếu các điện trở được mắc nối tiếp thì tại mỗi giá trị điện áp $U_{\mathrm{noc}}$ trên đoạn mạch chứa các điện trở bằng tổng điện áp trên mỗi điện trở. Với kết nối song song, dòng điện trong mạch ở mỗi giá trị điện áp $U_{\mathrm{nap}}$ trên các điện trở bằng tổng dòng điện chạy qua từng điện trở. Sự phụ thuộc $I(U_{\mathrm{noc}})$ và $I(U_{\mathrm{nap}})$ được vẽ trong hình.

Điện áp $U_6$ ở các cực của pin thay đổi khi điểm trong mạch thay đổi:

$$U_6 = \varepsilon - r I = 10 - 2 I.$$

Sự phụ thuộc $I(U_6)$ cũng được vẽ trong hình. Giao điểm của đường thẳng $I(U_6)$ với đường cong $I(U_{\mathrm{noc}})$ và $I(U_{\mathrm{nap}})$ cho giá trị cường độ dòng điện và điện áp trong mạch tương ứng đối với cách mắc nối tiếp và song song của các điện trở.

Từ hình ảnh có:

a) $I_1 = I_2 = I_6 = 0,25$ A; $U_1 = 5,5$B, $U_2 = 3,9$B;
