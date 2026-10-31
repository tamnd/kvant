---
id: 1981-2-resheniya-zadach-m616-m621-f623-f630-be024004
issue: kvant_1981_2
year: 1981
number: "2"
title: Lời giải bài toán M616—M621; F623—F630
rubric: zadachnik-kvanta
rubric_sub: Задачник «Кванта»
page_first: 26
page_last: 33
page_labels: 24, 25, 26, 27, 28, 30, 31
tag: Q8IX
lang: vi
source: kvant_digital
extraction: vision
content_sha256: d95b22016063a81788501b05bb80c284ee59ff11dbfc49995448602c94180c6c
prompt_sha256: draft-1
translated_from: content/ru/1981/02/articles/10_resheniya-zadach-m616-m621-f623-f630-be024004.md
source_content_sha256: 0a6929746dcdd516efff9e335e9cf2ea63bf011b2f2a17dc00a75967540c9fb3
translation_model: draft
translation_run: vi-draft-2026-10-31
translation_quality: draft
---

⟦folio 24⟧

tín hiệu ở đầu vào ăng-ten cần thiết để hoạt động bình thường, $P_{\min} = 1 \cdot 10^{-13}$ W.
Ước tính phạm vi phát hiện tối đa của máy bay có diện tích bề mặt phản xạ là $S = 5$ m$^2$. Giả sử rằng công suất của tín hiệu phản xạ nhỏ hơn $n = 10$ lần so với công suất của tín hiệu tới và sự phản xạ xảy ra đồng đều theo mọi hướng.

A. Zilberman

Lời giải bài toán

M616. Có thể chia các số 1, 2, ..., 30 thành các nhóm a) năm số, b) sáu số sao cho tổng các số trong tất cả các nhóm đều bằng nhau?

c) Với n và k nào thì có thể chia các số 1, 2, ..., nk thành n nhóm, mỗi nhóm k số sao cho tổng các số trong tất cả các nhóm đều bằng nhau?

Hình 1.

Hình 2.

Hình 3.

Chúng ta gọi một phân vùng thỏa mãn điều kiện bài toán là chính xác. Đáp số cho câu hỏi chung c) bài toán đưa ra

Định lý. Để tập {1, 2, ..., nk} thừa nhận một phân vùng thông thường thành các tập con phần tử k, điều cần và đủ là k chẵn hoặc nk lẻ.

Sự cần thiết của những điều kiện này là hiển nhiên. Trên thực tế, có tồn tại các phân vùng trống; thì tổng của các số $\frac{nk(nk+1)}{2}$ chia cho n (số của tập hợp con), tức là số $k(nk+1)/2$ là số nguyên; do đó k là số chẵn hoặc nk+1 là số chẵn, nghĩa là nk là số lẻ.

Điều này cho thấy rằng đáp số trong câu hỏi a) bài toán là âm ($k=5$ là số lẻ và $n=6$ là số chẵn).

Để chứng minh điều đó, chúng ta hãy xây dựng định lý ở dạng rõ ràng hơn:

Để n số {1, 2, ..., nk} được sắp xếp đúng cách trong bảng k hàng và n cột (tổng các số trong tất cả các cột bằng nhau) thì k là chẵn hoặc nk lẻ là điều cần thiết và đủ.

Cho k chẵn. Sau đó, các số có thể được sắp xếp theo kiểu “rắn” trong bảng (Hình 1; với mỗi hai hàng liên tiếp, tổng các số ở cột bất kỳ là như nhau).

Hãy để nk là lẻ. Hãy sắp xếp các số {1, 2, ..., 3n} “đúng” vào ba hàng trên cùng của bảng (các số còn lại, bắt đầu bằng số 3n+1, có thể xếp trong bảng $(k-3) \times n$ bằng con rắn, vì $k-3$ là số chẵn - Hình 2). Cách thực hiện điều này với $n=3, 5, 7$ được hiển thị trong Hình 3, a-c. Theo cách tương tự, bạn có thể tạo bảng $3 \times n$ cho bất kỳ $n=2m+1$ lẻ nào (Hình 4; kiểm tra xem nó có chứa bất kỳ số nào từ 1 đến $3n=6m+3$ một lần không).

Dễ dàng nhận thấy sự khái quát hóa tầm thường của định lý đã được chứng minh là đúng: các số n số {a+1, a+2, a+3, ..., a+nk} có thể được sắp xếp trong một bảng gồm k hàng và n cột một cách chính xác, điều này cần và đủ để k chẵn hoặc nk lẻ.

Sự khái quát hóa này gợi ý một cách khác để “sắp xếp chính xác” một đường thẳng $3 \times n$: bạn cần chia một đường thẳng $3 \times n$ thành một đường thẳng $3 \times 3, 3 \times 5$ (hoặc một số lẻ

⟦folio 25⟧

số $n \geqslant 9$ có thể được biểu diễn dưới dạng $n=3p+5q$, trong đó $p, q$ là số nguyên không âm) và sắp xếp chính xác các phân đoạn của chuỗi $\{1, 2, \dots, 3n\}$ trong chúng - tương ứng, từ 9 và 15 số - như trong các bảng tạo sẵn ở Hình 3, a, b (trong trường hợp này, trong mỗi hình chữ nhật, bạn sẽ phải thêm một hằng số vào số $a$).

Hãy nghĩ về câu hỏi phức tạp hơn này: vì $k < n$ có một “hình chữ nhật ma thuật” gồm các số 1, 2, ..., $nk$, trong đó tổng các số trong tất cả các hàng bằng nhau và tổng các số trong các cột cũng bằng nhau. Một hình vuông ma thuật tồn tại cho bất kỳ $n \geqslant 3$ nào (xem cuốn sách “Những hình vuông ma thuật” của M. M. Postnikov, M., “Hayka”, 1964).

S. Berkolaiko, N. Vasiliev

**M617. Bên trong tam giác có các đường tròn $a, b, \gamma$, δ có cùng bán kính sao cho mỗi đường tròn $a, b, \gamma$ tiếp xúc với hai cạnh của tam giác và đường tròn $b$. Chứng minh rằng tâm của đường tròn δ thuộc đường thẳng đi qua các tâm trong tam giác đã cho của đường tròn và đường tròn ngoại tiếp nó.**

Đặt $ABC$ là một tam giác nhất định và $O_1, O_2, O_3$ là tâm của các đường tròn tắc nghẽn tiếp xúc với các cặp cạnh của nó và $O_4$ là tâm của hình tròn thứ tư - đường tròn chạm vào ba đường tròn được chỉ định (xem hình). Độ dài bán kính của chúng được ký hiệu là $q$. Tam giác $O_1O_2O_3$ được chuẩn bị cho tam giác $ABC$, vì các cạnh của nó lần lượt song song với các cạnh của tam giác $ABC$. Không khó để nhận ra rằng tâm của sự đồng nhất này sẽ là điểm $N$, vừa là tâm của đường tròn nội tiếp tam giác $ABC$, vừa là tâm của đường tròn nội tiếp tam giác $O_1O_2O_3$. Thật vậy, các đường thẳng $AO_1, BO_2, CO_3$ là các đường phân giác của các góc của cả tam giác $ABC$ và tam giác $O_1O_2O_3$, và điểm $N$ là giao điểm của các đường phân giác này.

Bây giờ hãy lưu ý rằng điểm $O_4$ là tâm của một đường tròn ngoại tiếp tam giác $O_1O_2O_3$ (khoảng cách của nó đến mỗi đỉnh của tam giác này là 2$q$).

Hãy xem xét một sự đồng nhất có tâm tại $N$ ánh xạ tam giác $O_1O_2O_3$ thành tam giác $ABC$. Điểm $O_4$ đi vào một điểm $M$ nào đó nằm trên đường thẳng $NO_4$. Chúng ta đã biết rằng điểm $O_4$ là tâm của đường tròn ngoại tiếp tam giác $O_1O_2O_3$; do đó, ảnh của nó - điểm $M$ - sẽ là tâm của đường tròn ngoại tiếp tam giác $ABC$. Vậy tâm của đường tròn được mô tả xung quanh tam giác $ABC$ nằm trên cùng một đường thẳng với điểm $O_4$ và với tâm của đường tròn được mô tả trong tam giác $ABC$. Điều này chứng minh tuyên bố bài toán.

Không khó để tính giá trị q của bốn đường tròn này theo $r$ và $R$—bán kính của đường tròn nội tiếp trong tam giác và đường tròn ngoại tiếp.

Lưu ý rằng bán kính của hình tròn nội tiếp tam giác $O_1O_2O_3$ là $r-q$ và bán kính của hình tròn ngoại tiếp tam giác này là $2q$.

Gọi $k$ là hệ số đồng nhất được xét ở trên. Sau đó $(r-q)k=r$ và $2qk=R$. Biểu thị $k$ từ mỗi sự tương ứng và đánh đồng các biểu thức thu được, chúng ta thấy

$$\frac{r}{r-q} = \frac{R}{2q},$$

Ở đâu

$$q = \frac{rR}{R+2r}.$$

A. Savin

⟦folio 26⟧

M618. a) Chứng minh rằng có vô số số tự nhiên n sao cho n! chia hết cho $n^2+1$.

b) Chứng minh rằng với mọi a>0 tồn tại vô số số nguyên dương n sao cho $[\alpha n]!$ chia hết cho $n^2+1$. (Ở đây m!=1·2·...·m; [x] là phần nguyên của số x.)

Ví dụ, chúng ta hãy chứng minh rằng có vô số n mà $n^2+1$ có dạng $5m^2$. Nói cách khác, phương trình $n^2-5m^2=-1$ có ​​vô số số tự nhiên lời giải. Tuyên bố này xuất phát từ hai sự kiện sau, mỗi sự kiện có thể được xác minh trực tiếp: cặp $n=2$, m=1 thỏa mãn phương trình này và nếu n=a, m=b là lời giải của nó, thì cặp $n=9a+20b$, m=4a+9b cũng vậy (cách các công thức này thực hiện điều này được giải thích trong bài viết của N. Vaguten “Liên hợp số”, «Kvant», 1980, số 2).

Điều này ngay lập tức cung cấp cho chúng tôi bằng chứng về tuyên bố bài toán a). Thật vậy, với các giá trị tìm được của n, chúng ta có $n^2+1=5m^2$, $m=\sqrt{\frac{n^2+1}{5}}<\frac{n}{2}$ và n! chia hết cho $n^2+1$, vì với n>5 tích 1·2·3·...·n chứa các số 5, m và 2m.

Điều tương tự có thể được thực hiện trong trường hợp tổng quát 6). Nhưng để làm được điều này, chúng ta sẽ phải chứng minh rằng có vô số D tự nhiên sao cho số lời giải tự nhiên của phương trình $n^2-Dm^2=-1$ là vô hạn (sau đó chọn D sao cho bất đẳng thức $D\geqslant5/\alpha^2$ giữ nguyên, chúng ta sẽ thu được các giá trị cần thiết của n). Tuyên bố này đúng, nhưng việc chứng minh cơ bản của nó rất khó, vì vậy chúng ta sẽ đi theo một con đường khác.

Chúng ta sẽ tìm n mà chúng ta cần trong số các số có dạng $2k^2$. Trong trường hợp này, $n^2+1$ bị phân hủy thành sản phẩm $n^2+1=4k^4+1=(2k^2+2k+1)(2k^2-2k+1)$, nhưng điều này vẫn chưa đủ. Hãy để chúng tôi chỉ ra cách thu được nhiều k sao cho các số $P(k)=2k^2+2k+1$ và $Q(k)=2k^2-2k+1$ là hợp số (có thể phân tích thành thừa số). Hãy lấy tích tự nhiên c và đặt p=P(c), q=Q(c). Khi đó với l bất kỳ, số P(c+lpq) chia hết cho q (chứng minh điều đó!). Đặt $P(c+lpq)=p\cdot r$ và $Q(c+lpq)=q\cdot s$. Bằng cách lấy c đủ lớn, chúng ta có thể làm cho p=P(c) và q=Q(c) lớn hơn 5/a (điều này xuất phát từ thực tế là P(k) và Q(k) tăng vô hạn khi k tăng). Trong trường hợp này, $n^2+1=4k^4+1=P(k)\cdot Q(k)=p\cdot q\cdot r\cdot s$, trong đó $k=c+lpq$, $r=P(k)/p<\frac{P(k)}{5/\alpha}<\frac{an}{4}$ (đối với k>5) và $s=Q(k)/q<\frac{Q(k)}{5/\alpha}<\frac{an}{4}$ (đối với k>5). Bây giờ chọn l sao cho p và q nhỏ hơn an/4, chúng ta thấy rằng trong dãy 1, 2, 3, ..., [an] có bốn số riêng biệt, một số chia hết cho p, số khác chia hết cho q, số thứ ba cho r và số thứ tư cho s. Do đó, chúng tôi đã xây dựng một đa phản hồi vô hạn n sao cho [an] chia hết cho $n^2+1$.

lời giải khác trong số bài toán này cũng có thể xảy ra. Cái ngắn nhất dường như dựa trên sự phân hủy

$$64m^{12}+1=(4m^4+1)(4m^4-4m^3+2m^2-2m+1)\times(4m^4+4m^3+2m^2+2m+1)$$

(điều này lời giải do độc giả V. Yudak của chúng tôi đề xuất).

A. Weintrob

Vẽ cho M619.

M619. Chứng minh rằng nếu phương trình $|CD|=|AD|+|BC|$ đúng cho tứ giác treo ABCD thì hai đường phân giác của các góc A và B cắt nhau trên cạnh CD.

Về cơ bản, bài toán yêu cầu chứng minh sự tồn tại của vô số số nguyên dương n sao cho $n!$ chia hết cho $n^2+1$.

Ví dụ, chúng ta hãy chỉ ra rằng có vô số số tự nhiên n sao cho số số tự nhiên lời giải của phương trình $n^2-Dm^2=-1$ là vô hạn (sau đó chọn D sao cho bất đẳng thức $D\geqslant5/\alpha^2$ đúng, chúng ta sẽ thu được các giá trị cần thiết của n). Tuyên bố này đúng, nhưng việc chứng minh cơ bản của nó rất khó, vì vậy chúng ta sẽ đi theo một con đường khác.

Chúng ta lấy điểm K trên cạnh CD sao cho $|DK|=|AD|$, $|KC|=|BC|$ (xem hình) và vẽ đường tròn quanh tam giác ABK. Gọi M là giao điểm thứ hai của đường tròn này với [CD]. Chứng minh rằng [AM] và [BM] là hai đường phân giác của các góc tương ứng. Ví dụ: đối với [AM], chúng tôi có $BAM=BKC=90^\circ-\frac{BCK}{2}=90^\circ-\frac{1}{2}(180^\circ-DAB)=\frac{1}{2}DAB$, đây là yêu cầu bắt buộc.

I. Sharyn

⟦folio 27⟧

M620. Đặt $x_1, x_2, \dots, x_n$ là các số thực sao cho $x_1^2 + x_2^2 + \dots + x_n^2 = 1$. Chứng minh rằng tổng mô hình của các số $2^n$

$$\pm x_1 \pm x_2 \pm \dots \pm x_n$$

(vì vậy với tất cả các kết hợp có thể có của các dấu “+” và “-”) không vượt quá $2^n$.

Trước tiên chúng ta hãy chứng minh rằng nếu $a_1^2 + a_2^2 + \dots + a_k^2 = k$ thì $a_1 + a_2 + \dots + a_k \leq k$. Thật vậy, hãy để $a_i = 1 + a_i$ ($i = 1, 2, \dots, k$). Sau đó

$$a_1^2 + a_2^2 + \dots + a_k^2 = k + 2(a_1 + \dots + a_k) + (a_1^2 + \dots + a_k^2),$$

Ở đâu

$$a_1 + a_2 + \dots + a_k = -\frac{1}{2} (a_1^2 + a_2^2 + \dots + a_k^2) \leq 0.$$

Posetom

$$a_1 + a_2 + \dots + a_k = k + (a_1 + a_2 + \dots + a_k) \leq k.$$

Bây giờ chúng ta biểu thị tổng của các số $2^n$ của mô hình

$$\pm x_1 \pm x_2 \pm \dots \pm x_n$$

(vì vậy tất cả các kết hợp có thể có của các dấu “+” và “-”) đến $S$. Dễ dàng kiểm tra xem tổng bình phương của tất cả các số $2^n$ có trong tổng $S$ có ​​bằng $2^n (x_1^2 + x_2^2 + \dots + x_n^2) = 2^n$ hay không. Chúng ta hãy biểu thị các số $2^n$ có trong $S$ bằng $a_1, a_2, \dots, a_{2^n}$. Khi đó $a_1^2 + a_2^2 + \dots + a_{2^n} = 2^n$, và từ khẳng định đã được chứng minh ở trên, chúng ta thu được ước tính $a_1 + a_2 + \dots + a_{2^n} \leq 2^n$, đây chính là điều chúng ta cần chứng minh.

Như độc giả của chúng tôi A. Heiftz từ Rostov-on-Don đã thay thế một cách đúng đắn, bài toán M620 là một trường hợp đặc biệt của lời hứa sau đây của M. Klamkin (American Mathematical Monthly, 1975, 82, No. 8, p. 829-830):

Đặt $x_1, x_2, \dots, x_n$ là số thực bất kỳ. Sau đó với $\lambda \geq 2$ và với $\lambda \leq 0$ bất đẳng thức đúng

$$\sum |\pm x_1 \pm x_2 \pm \dots \pm x_n|^\lambda \geq 2^n \left( \sum_{i=1}^{n} x_i^2 \right)^{\lambda/2},$$

và với $0 < \lambda < 2$ - một bất đẳng thức có nghĩa ngược lại. (Tổng hợp các tổ hợp tùy ý của các dấu “+” và “-” ở phía bên trái.) Chúng tôi mời bạn suy nghĩ về việc tự mình chứng minh nhận định này.

I. Klumova

M621. Một bức tường p được mô tả xung quanh vòng tròn. Một điểm tùy ý $P$ bên trong đường tròn được nối với tất cả các đỉnh và điểm tiếp tuyến của nó. Các tam giác 2n thu được được bao quanh bởi một biến có màu đỏ và xanh lam. Chứng minh rằng tích diện tích các hình tam giác màu đỏ bằng tích diện tích các hình tam giác màu xanh.

F623. Tụ điện biến thiên có công suất ban đầu $C_0$, được tích điện theo hướng $U$, nối ngắn mạch với điện trở có điện trở $R$ (xem hình. ok). Cấu trúc của nước ngưng sẽ thay đổi như thế nào theo thời gian?

◆ Gọi $A_1 A_2 \dots A_n$ là đường ngoại tiếp $n$-gon, $t_1, t_2, \dots, t_n$ là độ dài của các đoạn tiếp tuyến vẽ với đường tròn từ điểm tiếp tuyến của các đoạn thẳng, khi đó tích $n$ của độ dài các đoạn nằm trong tam giác xanh bằng tích $n$ của độ dài các đoạn nằm trong tam giác xanh. Để chứng minh, chỉ cần lưu ý $T_{k-1} T_k$, bằng tỉ số diện tích của các tam giác $PT_{k-1} A_k$ và $PT_k A_k$ là đủ.

◆ Cường độ dòng điện trong mạch được xác định bởi hiệu điện thế trên điện trở bằng hiệu điện thế trên tụ điện: $I = U/R$. Vì dòng điện phải không đổi nên điện áp trên tụ cũng phải không đổi, nghĩa là

$$\frac{q_0}{C_0} = \frac{q_0 - \Delta q}{C},$$

⟦folio 28⟧

hình xuyến để có dòng điện chạy trong mạch hở? Công suất nào được tạo ra bởi ngoại lực, do đó điện dung của tụ điện thay đổi?

F624. Trong quá trình vận hành bình được đóng kín bằng một pít-tông phẳng có đường kính $D=5$ cm, có một lượng nước nhỏ (xem hình). Đường kính của quá trình là $d=2$ mm. Nếu ở nhiệt độ không đổi $t=20^\circ C$ piston được hạ xuống $H=10$ cm thì mực nước trong quá trình này sẽ tăng $h=1$ mm. Tìm áp suất hơi bão hòa của nước ở nhiệt độ $t=20^\circ C$.

F625. Động cơ phản lực trong hình được làm từ vỏ trứng. Diện tích của lỗ trên vỏ là $s=3\text{ mm}^2$. Công suất tối đa của động cơ này là bao nhiêu nếu nhiệt độ của nước trong vỏ được duy trì ở mức $100^\circ C$?

Trong đó $q_0$ là điện tích ban đầu của tụ điện, $\Delta q=It/R$ là điện tích chạy qua mạch trong thời gian $t$, $C$ là điện dung của tụ điện tại thời điểm $t$. Từ đây

$$C = C_0 \left( 1 - \frac{\Delta q}{q_0} \right) = C_0 \left( 1 - \frac{t}{RC_0} \right).$$

Để xác định công suất $N$ do ngoại lực phát triển, ta sử dụng định luật bảo toàn và biến thiên năng lượng: độ biến thiên năng lượng của hệ theo thời gian $t$ bằng các ngoại lực, tức là

$$\left( \frac{CU^2}{2} - \frac{C_0U^2}{2} \right) + I^2Rt = Nt.$$

Từ đây, xét đến sự phụ thuộc của điện dung vào thời gian, ta tìm được công suất của các ngoại lực:

$$N = \frac{U^2}{2R}.$$

P. Zubkov

◆

Vì có nước ngay từ đầu trong quá trình này nên hơi nước trong bình đã bão hòa. Khi piston được hạ xuống, áp suất của nó không thay đổi và trọng lượng của hơi nằm trong thể tích “biến mất”

$$V = \pi D^2/4H,$$

ngưng tụ. Khối lượng nước ngưng tụ là

$$m = \varrho p d^2/4h,$$

trong đó $\varrho = 10^3 \text{ кг/m}^3$ là mật độ của nước.

Từ phương trình Mendeleev-Clapeyron, hơi bão hòa được tìm thấy:

$$p = \frac{m}{\mu} \frac{RT}{V} = \varrho \left( \frac{d}{D} \right)^2 \frac{h}{H} \frac{RT}{\mu} = 2,16 \text{ кПа.}$$

Quét. Trong công thức thu được, các đại lượng $d$ và $D$, $h$ và $H$ tạo thành các kết hợp không thứ nguyên. Do đó, giá trị của các đại lượng này có thể được thay thế bằng bất kỳ đơn vị đo lường nào, nhưng nhất thiết phải giống hệt nhau. Ví dụ: $d$ và $D$ tính bằng milimet, $a$ và $H$ tính bằng centimét. Giả sử rằng các đại lượng còn lại ($\varrho$, $R$, $T$ và $\mu$) được biểu thị bằng đơn vị SI, thì đáp số được tính bằng pakaleh.

V. Belonukkin

◆

Theo định luật bảo toàn động lượng, phản lực tác dụng lên vỏ bằng modulo độ chênh lệch động lượng của các phân tử bay ra khỏi vỏ trong một đơn vị thời gian và bay vào vỏ trong cùng một thời gian. Mặt khác, áp suất của khí tác dụng lên tường không lớn hơn hai lần động lượng của các phân tử chạm vào một đơn vị diện tích bề mặt của tường trong một đơn vị thời gian. Như vậy, động lượng của các phân tử phát ra từ một lỗ có diện tích $s$ trên một đơn vị thời gian bằng $ps/2$, động lượng của các phân tử phát ra là $p_0s/2$ (trong đó $p$ và $p_0$ là áp suất bên trong và bên ngoài lớp vỏ, tương ứng) và lực mong muốn

$$F = \frac{ps}{2} - \frac{p_0s}{2} = (p - p_0) \frac{s}{2}.$$

Về mặt lý thuyết, áp suất tối đa có thể đạt được bên trong vỏ lớn hơn hai lần áp suất khí quyển một chút. Thật vậy, nếu nước trong vỏ nóng lên nhanh đến mức khối không khí không có thời gian thay đổi, thì áp suất sẽ là tổng của áp suất không khí (ở $100^\circ C$ lớn hơn áp suất khí quyển một chút) và áp suất của hơi nước bão hòa (ở $100^\circ C$ bằng khí quyển). Trong trường hợp này

$$F_{\text{max}} = (p_{\text{max}} - p_0) \frac{s}{2} = p_0 \frac{T}{T_0} \frac{s}{2} \approx 0,2 \text{ H}.$$

⟦folio 30⟧

mỡ động vật sẽ nguội đi nhanh chóng, nhưng bồ hóng sẽ tiếp tục nóng. Nếu chảo được làm nguội từ bên trong, than sẽ nguội từ từ, nhiệt độ của kim loại sẽ có thời gian theo nhiệt độ của than và thực tế sẽ không có sự chênh lệch nhiệt độ.

Các lực thúc đẩy sự phân tách cặn cacbon có phát sinh trong quá trình làm nguội chậm, tức là trên thực tế khi nhiệt độ của cặn kim loại và cặn cacbon bằng nhau không? Có, vì cặn kim loại và carbon có hệ số giãn nở tuyến tính khác nhau. Nhưng hóa ra những lực này không đủ để phá hủy lớp bồ hóng và tách nó ra khỏi đáy chảo.

L. Ashkinazi

F628. Trong một ống thẳng đứng dài $H=152$ cm, bịt kín ở đầu dưới, có rất nhiều không khí cao $h=76$ cm, bị nhốt trong rất nhiều thủy ngân (Hình 1). Áp suất khí quyển là $10^5$ Pa, và nhiệt độ là $t_0=17^\circ$ C. Không khí trong ống phải tăng đến nhiệt độ nào $t_1$ để toàn bộ thủy ngân biến mất?

Hình 1.

Hình 2.

Áp suất không khí ban đầu trong ống là tổng áp suất thủy tĩnh của lượng thủy ngân có chiều cao $H-h=76$ cm và áp suất khí quyển. Áp suất khí quyển theo điều kiện bằng $10^5$ Pa≈76 cm thủy ngân. Nghệ thuật. Do đó, áp suất không khí ban đầu trong ống xấp xỉ bằng hai lần áp suất khí quyển.

Chúng ta sẽ giả sử rằng thủy ngân chảy ra từ từ, sao cho hệ tại mỗi thời điểm có thể được coi là ở trạng thái cân bằng. Ở trạng thái cuối cùng, khi gần như toàn bộ thủy ngân đã chảy ra ngoài, áp suất không khí trong ống sẽ bằng áp suất khí quyển, tức là bằng một nửa áp suất. Thể tích không khí $HS$ (S là diện tích mặt cắt ngang của ống) sẽ lớn gấp đôi thể tích trơ tráo $hS$. Theo phương trình trạng thái khí lý tưởng, điều này có nghĩa là nhiệt độ ở trạng thái cuối cùng phải bằng nhiệt độ ở trạng thái ban đầu!

Tất nhiên, nếu không tăng nhiệt độ, thủy ngân sẽ không chảy ra khỏi ống. Do đó, kết quả thu được có nghĩa là đối với đáp số được đề cập bài toán, chúng ta nên hạn chế chỉ xem xét trạng thái cuối cùng và trơ tráo, nhưng chúng ta cần phải tuân theo toàn bộ quá trình.

Chúng ta hãy tìm hiểu xem nhiệt độ của không khí trong ống phải thay đổi như thế nào để thủy ngân được giải phóng dần dần và tại mỗi thời điểm hệ có thể coi là ở trạng thái cân bằng.

Chúng ta hãy biểu thị độ cao của lượng không khí đó tại một thời điểm nào đó bằng $z$. Khi đó áp suất không khí trong ống $p(z)$ bằng

$$p(z) = p_0 + \rho g(H-z),$$

trong đó $\rho$ là mật độ của thủy ngân và $p_0$ là áp suất khí quyển, theo điều kiện bài toán, gần bằng áp suất của rất nhiều thủy ngân ở độ cao $H/2$:

$$p_0 = \rho g H/2.$$

Thay (2) vào (1), ta được

$$p(z) = \rho g \left( \frac{3}{2} H-z \right).$$

Vì chúng ta giả sử rằng không khí trong ống ở trạng thái cân bằng nhiệt động ở bất kỳ $z$ nào, nên áp suất $p(z)$ của không khí, thể tích mà nó chiếm $Sz$ và nhiệt độ $T(z)$ có liên hệ với nhau bởi phương trình trạng thái của khí lý tưởng:

$$\frac{p(z) Sz}{T(z)} = \frac{2 p_0 SH/2}{T_0},$$

trong đó $T_0$ là nhiệt độ ban đầu, $2 p_0$ là áp suất không khí ban đầu trong ống, $SH/2$ là thể tích không khí ban đầu. Thay $p(z)$ từ (3) và $p_0$ từ (2) vào (4), ta tìm được sự phụ thuộc của nhiệt độ vào độ cao của không khí trong ống:

$$T(z) = T_0 \frac{(3H-2z)z}{H^2}.$$

Đồ thị hàm số $T(z)$ được thể hiện trên Hình 2. Quá trình lắng cặn thủy ngân tương ứng với vùng có các điểm $z=H/2$ và $z=H$ được biểu thị bằng một đường thẳng liền nét. Có thể thấy rằng đối với một quá trình chậm (gần như cân bằng), nhiệt độ sẽ bắt đầu tăng lên giá trị $T_1=(9/8)T_0$ (trong trường hợp này

⟦folio 31⟧

Hình 3.

F629. Một quả cầu có khối lượng m được treo vào một lò xo có độ cứng k (lò xo nam châm). Điểm treo của lò xo thực hiện dao động điều hòa theo phương thẳng đứng có biên độ a và tần số $\omega$. Quả bóng chuyển động như thế nào khi dao động đều?

F630. Một phần tử của pin nguyên tử là một tụ điện, trên một trong các bản được đặt chất phóng xạ, phát ra các hạt α với tốc độ $v_0=2,2 \cdot 10^6$ m/s. Xác định emf của phần tử này. Tỷ số giữa điện tích của hạt α và khối lượng của nó là k=4,8 $\cdot 10^7$ C/kg.

một nửa lượng thủy ngân đầu tiên sẽ bay ra ngoài), sau đó co lại về giá trị ban đầu $T_0$. Vì vậy, để đốt cháy hoàn toàn thủy ngân, không khí trong ống phải được đun nóng đến nhiệt độ $T_1 \approx 326$ K. Ở nhiệt độ này, cần duy trì tiếp xúc với lò sưởi có nhiệt độ $T_1$. Hơn nữa, thủy ngân sẽ bị ép ra ngoài và quá trình này sẽ không còn gần như cân bằng nữa.

Để hiểu rõ hơn về điều này, sẽ rất hữu ích khi xem xét quy trình theo sơ đồ $p-V$ (Hình 3). Quá trình cân bằng của dòng thủy ngân chảy ra tương ứng với sự phụ thuộc tuyến tính của áp suất không khí trong ống vào z, được mô tả bằng công thức (3) và được biểu thị dưới dạng một đường liền nét giữa các giá trị $z=H/2$ và $z=H$. Hình tương tự hiển thị hình ảnh của nhiệt độ tương ứng $T_0$ và $T_1$. Trạng thái đầu và cuối nằm trên cùng một đường đẳng nhiệt. Có thể thấy rằng ở nhiệt độ trên $T_1$, không có một đường đẳng nhiệt nào cắt đường thẳng $p(z)$, tức là không thể cân bằng không khí trong ống ở bất kỳ giá trị nào của chiều cao cột z. Do đó, nếu nhiệt độ không khí được duy trì ít nhất trên giá trị $T_1$ thì toàn bộ thủy ngân chắc chắn sẽ bị đẩy ra khỏi không khí.

E. Butikov, A. Bykov, A. Kondratev

Hình vẽ thể hiện vị trí của hệ tại một thời điểm t. Điểm O là vị trí cân bằng của điểm treo; x là độ lệch của quả cầu so với vị trí cân bằng khi đó chiều dài của lò xo bằng $l_0+mg/k$ ($l_0$ là chiều dài của lò xo ở trạng thái không giãn nở).

Viết phương trình chuyển động của quả bóng:

$$mg-k\Delta X=m\ddot{x}.$$

Thay $\Delta X=\frac{mg}{k}+x+a\sin \omega t$ (độ dài hoàn toàn của lò xo), ta được:

$$m\ddot{x}+kx=-ka\sin \omega t.$$

Dao động cưỡng bức của quả bóng xảy ra với tần số của lực cưỡng bức, tức là với tần số $\omega$. Ở trạng thái ổn định không có dao động tự nhiên có tần số là $\omega_0=\sqrt{k/m}$.

Chúng ta sẽ tìm lời giải (1) ở dạng

$$x=A\sin \omega t+B\cos \omega t,$$

trong đó A và B là một số hệ số không đổi cần xác định. Lấy một số tùy ý từ (2) hai lần và thay (2) vào (1), ta có:

$$(-A\omega^2 m+kA)\sin \omega t+(-B\omega^2 m\cos \omega t+kB)\cos \omega t$$

$$=-ka\sin \omega t.$$

Sự bình đẳng này phải được duy trì ở bất kỳ thời điểm nào.

Lấy $t_1=0$ và $t_2=\pi/2\omega$, ta tìm được $B=0$, $A=\frac{ka}{\omega^2 m-k}=\frac{a}{\omega^2-\omega^2}=1$.

Thay các giá trị tìm được của A và B vào (2), ta thu được:

$$x=\frac{a\sin \omega t}{\omega^2-\omega^2}-1.$$

A. Zilberman

suất điện động của nguồn bằng tỉ số giữa công do ngoại lực thực hiện làm di chuyển một điện tích dọc theo mạch với độ lớn của điện tích này. EMF tối đa sẽ là khi các hạt α không còn chạm tới bản đối diện của tụ điện. Nói cách khác, khi công của phía lực bằng động năng của hạt α phát ra:

$$\mathcal{E}=\frac{mv_0^2}{2q}=\frac{v_0^2}{2k}\approx 5 \cdot 10^5 \text{ B}=500 \text{ kB}.$$

A. Grizorenko, học sinh lớp 10, Makeev, vùng Donetsk.
