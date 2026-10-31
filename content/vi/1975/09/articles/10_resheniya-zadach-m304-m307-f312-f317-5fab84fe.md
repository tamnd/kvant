---
id: 1975-9-resheniya-zadach-m304-m307-f312-f317-5fab84fe
issue: kvant_1975_9
year: 1975
number: "9"
title: Lời giải bài toán M304—M307; F312—F317
rubric: zadachnik-kvanta
rubric_sub: Задачник «Кванта»
page_first: 36
page_last: 44
page_labels: 34-42
tag: HBMD
lang: vi
source: kvant_digital
extraction: vision
content_sha256: 4acbbcd4a48f8587c263230f69d360af71206c7695d406c03f5c66d7dce2eb8b
prompt_sha256: draft-1
translated_from: content/ru/1975/09/articles/10_resheniya-zadach-m304-m307-f312-f317-5fab84fe.md
source_content_sha256: 3476b3017a923acacbede52653a626d0fa59ec904075cb77aab2607e0d37ad9c
translation_model: draft
translation_run: vi-draft-2026-10-31
translation_quality: draft
---

⟦folio 34⟧

Lời giải bài toán

M304. Chúng ta sẽ sử dụng đường tròn để biểu thị một phép toán nhất định (chưa biết) có thể áp dụng cho hai số nguyên không âm a và b bất kỳ và có thể cho một số nguyên không âm a*b=c. Cho phép toán này thỏa mãn các điều kiện sau:

1) a*b = b*a;
2) nếu a*b=c thì b*c=a;
3) nếu a*b > c thì b*c < a hoặc a*c < b.
a) Tìm 0*0; 0*1; 1*1; 0*2.
6) Hãy chứng minh rằng 0*a=a và 1*a =
-{a+1, nếu a chẵn,
-a-1 nếu a lẻ.
8) Hãy chứng minh rằng có nhiều nhất một phép toán thỏa mãn điều kiện bài toán.
2) Hãy chứng minh rằng phép toán này tồn tại và chỉ ra quy tắc cho phép chúng ta tính a*b cho a, b.

a) Hãy tìm 0*0.
Giả sử rằng 0*0>0. Thay a=b=c=0 vào điều kiện 3) chúng ta nhận được 0*0<0, điều này là không thể. Vì vậy, 0*0=0. Hãy tìm 0*1.
Nếu 0*1=0 thì 0*0=1, điều này không chính xác. Nếu 0*1>1 thì từ điều kiện (3) 1*1<0, điều này là không thể. Do đó 0*1=1.
Bằng cách lập luận tương tự, chúng ta thu được rằng
1*1=0, 0*2=2.

6) 1. Hãy chứng minh rằng 0*a=a bằng dấu hiệu của a.
Giả sử điều này đúng với mọi a<n и докажем, что 0*n=n. Пусть 0*n=k<n. тогда 0*k=n, что противоречит допущению. Пусть 0*n>n. thì từ điều kiện 3) n*n<0, điều này là không thể. Vì vậy, 0*n=n.

2) Hãy chứng minh rằng 1*a =
{a+1, nếu a chẵn,
a-1 nếu a lẻ.

biểu thị bằng a.
Giả sử rằng điều này đã được chứng minh với mọi a<n, và chúng ta sẽ chứng minh điều đó với a=n.
Hãy xem xét hai trường hợp.

(a) n là số chẵn.
Hãy biểu thị 1*n=k. thì 1*k=n. Nếu k<n thì ta có mâu thuẫn. Bây giờ đặt 1*n>n+1. thì theo điều kiện 3) 1*(n+1)<n hoặc n*(n+1)<1, nhưng cả hai đều dẫn đến mâu thuẫn. Vì vậy, 1*n=n+1.

(6) n - lẻ.
Khi đó, theo điều đã được chứng minh, 1*(n-1)=n, từ đó 1*n=n-1.

c) Bây giờ chúng ta chứng minh rằng có nhiều nhất một phép toán thỏa mãn điều kiện bài toán.
Chúng ta hãy giả sử rằng có hai hoạt động như vậy. Chúng ta hãy biểu thị thao tác đầu tiên bằng $\circ$ và thao tác thứ hai bằng $\odot$. Theo giả định, có ít nhất một cặp số a, b thỏa mãn a*b≠a*b. Từ tất cả các cặp như vậy, hãy chọn cặp có tổng a+b nhỏ nhất. Vì vậy, hãy để a*b≠a*b; nếu a'+b'<a+b, то a'*b'=a'*b'. Обозначим a*b=k, a*b=l. Пусть k<l (случай k>l tương tự). Vì a*b>k nên a*k<b hoặc b*k<a. Đặt a*k=m<b (trường hợp b*k<a tương tự). thì a*m=k. Vì m<b nên a+m<a+b, và do đó a*m=a*m=k. Khi đó a*k=m, điều này mâu thuẫn với thực tế là a*k=b.

Kết quả mâu thuẫn chứng minh câu c).
d) Bây giờ chúng ta hãy chứng minh rằng một phép toán như vậy tồn tại.
Mọi số nguyên không âm a được biểu diễn duy nhất dưới dạng
a=a₀·2⁰+a₁·2¹+a₂·2²+...+aₖ·2⁷+...*).

*) Đây là cách biểu thị số a trong hệ thống số kép.

⟦folio 35⟧

Ở đây $a_0, a_1, \dots$ là một dãy vô hạn trong đó hữu hạn số hạng là số 1, số còn lại là số 0.

Hãy để $a = \sum_{k=0}^{\infty} a_k \cdot 2^k, b = \sum_{k=0}^{\infty} b_k \cdot 2^k$.

Hãy xác định giá trị của $c = a \circ b$: đặt $c = \sum_{k=0}^{\infty} c_k \cdot 2^k$, trong đó các số $c_k$ được xác định theo quy tắc sau:

$$c_k = \begin{cases} 0, & \text{ если } a_k = b_k, \\ 1, & \text{ если } a_k \neq b_k. \end{cases}$$

Rõ ràng là các điều kiện hoạt động xác định như vậy 1) và 2) được đáp ứng. Hãy kiểm tra xem điều kiện 3) có thỏa mãn không. Hãy định dạng lại nó như thế này:

nếu $a \circ b \neq c$ thì: $a \circ b < c$ hoặc $a < c < b$ hoặc $b \circ c < a$.

Hãy để $a \circ b \neq c$. Chúng ta biểu thị bằng $k$ số cao nhất mà điều kiện (*) không được thỏa mãn. Khi đó xảy ra một trong hai trường hợp sau:

(a) $a_h = b_h = c_h = 1$.

Trong trường hợp này, thậm chí cả ba bất đẳng thức đều được thỏa mãn. Thật vậy, chẳng hạn, chúng ta hãy chứng minh rằng $a \circ b < c$. Vì chữ số thứ $k$ của số $a \circ b$ bằng 0 và ở chữ số $(k+1)-м, (k+2)-м, \dots$ các số $a \circ b$ và $c$ trùng nhau nên

$$a \circ b \leq 2^0 + 2^1 + \dots + 2^{k-1} + \Delta = 2^k - 1 + \Delta,$$

trong đó bằng $\Delta$ chúng ta biểu thị số $c_{k+1} \cdot 2^{k+1} + c_{k+2} \cdot 2^{k+2} + \dots$. Nhưng chữ số thứ $k$ của số $c$ là 1; điều đó có nghĩa là $c \geq 2^k + \Delta$, do đó $a \circ b < c$.

(6) Trong ba số $a_h, b_h, c_h$, một số bằng một, hai số còn lại bằng 0.

Đặt $a_h = b_h = 0, c_h = 1$ (các trường hợp khác tương tự). Sau đó $a \circ b < c$, kể từ đó một lần nữa $a \circ b \leq 2^k - 1 + \Delta, c \geq 2^k + \Delta$.

A. A. Gritsoryan, A. L. Toom

♦

a) Có hai trường hợp có thể xảy ra; chúng được thể hiện trong Hình 1, a và 6. Xét các tam giác $B'PC'$ và $BPC$. Đối với khu vực của họ, chúng tôi có

$$\frac{S_{B'PC'}}{S_{BPC}} = \frac{|C'P| \cdot |B'P|}{|CP| \cdot |BP|} = \frac{q' \cdot |B'P|}{q \cdot |BP|}.$$

Ở phía bên kia,

$$\frac{S_{B'PC'}}{S_{BPC}} = \frac{S_{A'PB'} \cdot \frac{|B'C'|}{|A'B'|}}{S_{APB'} \cdot \frac{|BC|}{|AB|}} = \frac{|B'P| \cdot |A'P| \cdot |B'C'| \cdot |AB|}{|BP| \cdot |AP| \cdot |BC| \cdot |A'B'|}.$$

Vì $\triangle APB \sim \triangle A'PB'$ thì

$$\frac{|A'P|}{|A'B'|} = \frac{|BP|}{|AB|},$$

đó là

$$|A'P| \cdot |AB| = |BP| \cdot |A'B'|.$$

Pozny

$$\frac{q' \cdot |B'P|}{q \cdot |BP|} = \frac{|B'P| \cdot |B'C'|}{|AP| \cdot |BC|},$$

⟦folio 36⟧

Ở đâu
$$|B'C'| = \frac{|BC| \cdot |AP|}{|BP|} \cdot \frac{q'}{q}. \tag{1}$$

Tương tự như vậy
$$|A'C'| = \frac{|AC| \cdot |BP|}{|AP|} \cdot \frac{q'}{q}. \tag{2}$$

Nhân các đẳng thức (1) và (2), ta thu được
$$\frac{s'}{s} = \left( \frac{q'}{q} \right)^2. \tag{3}$$

Daloe
a) $$|AP|^2 = |AC|^2 + |CP|^2 + 2|AC| \cdot |CP| \cdot \cos(\widehat{BCP}) =$$
$$= |AC|^2 + q^2 + 2q \cdot |AC| \cdot \cos(\widehat{BCP});$$
$$|BP|^2 = |BC|^2 + q^2 - 2q \cdot |BC| \cdot \cos(\widehat{BCP}).$$

Nhân kết quả đầu tiên với |BC|, kết quả thứ hai với |AC| và cộng chúng lại chúng ta có được
$$|AP|^2 \cdot |BC| + |BP|^2 \cdot |AC| = (s + q^2) \cdot |AB|,$$
đó là
$$s + q^2 = \frac{|BC| \cdot |AP|^2 + |AC| \cdot |BP|^2}{|AB|}. \tag{4}$$

Theo cách tương tự, người ta thấy rằng
$$s' + (q')^2 = \frac{|A'C'| \cdot |B'P|^2 + |B'C'| \cdot |A'P|^2}{|A'B'|}. \tag{5}$$

Chúng ta hãy biến đổi sự tương ứng (5), xét đến các đẳng thức (1), (2), (4) và các tam giác đồng dạng APB và A'PB':

$$s' + (q')^2 = |A'P|^2 \cdot \frac{1 + \frac{|B'P|^2}{|A'P|^2} \cdot \frac{|A'C'|}{|B'C'|}}{1 + \frac{|A'C'|}{|B'C'|}} =$$
$$= |A'P|^2 \cdot \frac{1 + \frac{|B'P|^2}{|A'P|^2} \cdot \frac{|AC| \cdot |BP|^2}{|BC| \cdot |AP|^2}}{1 + \frac{|AC| \cdot |BP|^2}{|BC| \cdot |AP|^2}} =$$
$$= |A'P|^2 \cdot |AP|^2 \cdot \frac{|AB|}{|BC| \cdot |AP|^2} = \frac{t^2}{s + q^2},$$
đó là
$$\frac{s' + (q')^2}{t} = \frac{t}{s + q^2}. \tag{6}$$

Nó chỉ còn để chứng minh rằng, ví dụ,
$$\frac{t}{s + q^2} = \sqrt{\frac{s'}{s}}.$$

Nhưng đây chỉ là một bài tập (xem (3) và (6)):
$$\frac{s' + (q')^2}{s + q^2} = \frac{s'}{s} \Rightarrow s' + (q')^2 =$$
$$= \frac{s'}{s} \cdot (s + q^2) \Rightarrow t^2 = \frac{s'}{s} \cdot (s + q^2)^2.$$

Cơm. 1.

Cơm. 2.

⟦folio 37⟧

6) Chúng ta sẽ giải bài toán 6) theo giả định rằng điểm $P$ nằm trong mặt cầu không cho trước $S$ (đối với trường hợp $P$ là phần bên trong của hình cầu $S$ thì mọi lý luận đều tương tự).

Đặt $AB$ và $QR$ là hai dây giao nhau của đường tròn $\sigma$, $A'$ và $B'$ - các điểm từ tập hợp $\sigma'$ tương ứng với các điểm $A$ và $B$ (Hình 2). Chúng ta hãy vẽ một mặt phẳng đi qua các điểm $A$, $B$ và $P$; thì trong mặt cắt ngang bạn sẽ có được hình ảnh tương ứng với Hình 1, 6.

Trong bài toán a) chúng ta đã chứng minh được rằng

$$|C'P| = \frac{|CP| \cdot |AP| \cdot |A'P|}{|AC| \cdot |CB| + |CP|^2}$$

Nếu $Q'$ và $R'$ là các điểm của tập $\sigma'$ tương ứng với các điểm $Q$ và $R$ của đường tròn $\sigma$ thì

$$|QP| \cdot |Q'P| = |AP| \cdot |A'P|,$$

và ngoài ra,

$$|QC| \cdot |CR| = |AC| \cdot |CB|.$$

Điều này có nghĩa là điểm $C'$ (thuộc dây cung $A'B'$) cũng thuộc đoạn $Q'R'$, và do đó, các điểm $A', B', Q'$ và $R'$ nằm trong cùng một mặt phẳng. Vì chúng tôi đã chọn các điểm tùy ý, nên tất cả các điểm của tập hợp $\sigma'$ đều thuộc cùng một mặt phẳng; có nghĩa là $\sigma'$ là một hình tròn.

A. I. Shirshov

Bây giờ chúng ta hãy trình bày hai lời giải bài toán 6), không sử dụng các phép tính bài toán a).

Ý tưởng về lời giải đầu tiên được độc giả S. Finashina (Leningrad) của chúng tôi chấp nhận.

Chúng ta hãy vẽ qua các điểm $P$ và đường tròn $\sigma$ các hình cầu $S'$; gọi $\pi$ là mặt phẳng tiếp xúc với hình cầu $S'$ tại điểm $P$. Chứng minh rằng mọi điểm của tập hợp $\sigma'$ đều thuộc mặt phẳng $\pi'$, song song với mặt phẳng $\pi$. Để làm điều này, chúng ta sửa điểm $A'$ thuộc $\sigma'$ và chứng minh rằng với mọi điểm $B'$ thì tập $\sigma'$ thuộc $\sigma'$ song song với mặt phẳng $\pi$.

Xét mặt phẳng đi qua các điểm $P$, $A'$ và $B'$. Mặt phẳng này cắt các hình cầu $S$ và $S'$ dọc theo đường tròn $\tau$ và $\tau'$, tương ứng với mặt phẳng $\pi$ - dọc theo đường thẳng $l$ (Hình 3; điểm $A$ và $B$ là giao điểm $(PA')$ và $(PB')$ với hình cầu $S$ - chúng thuộc về hình tròn $\sigma$).

Chúng ta hãy biểu thị góc $A'B'B$ bằng $\alpha$. Khi đó cung $A'AB$ bằng $2\alpha$, cung $BB'A'$ bằng $(2\pi - 2\alpha)$, góc $A'AB$ bằng $\pi - \alpha$ và góc $BAP$ bằng $\alpha$; nghĩa là góc $PBA$ bằng $2\alpha$. Do đó, góc $BPQ$ bằng $\alpha$, tức là các góc $A'B'B$ và $BPQ$ bằng nhau. Điều này có nghĩa là đường thẳng $A'B'$ song song với đường thẳng $l$, đây là điều cần chứng minh.

lời giải bài toán 6) thứ hai thu được bằng cách sử dụng phép biến đổi hình học - đảo ngược. Trước tiên chúng ta hãy nhớ lại nghịch đảo trên mặt phẳng là gì (các tính chất của nghịch đảo trên mặt phẳng đã được thảo luận chi tiết trong bài viết của A.P. Savin và “Đảo ngược và bài toán Apollo”, «Kvant», 1971, số 8; chương thứ hai của I.M. Ya Glom “Biến đổi hình học” được dành cho nghịch đảo, tập II, Các phép biến đổi tuyến tính và dốc, M., Gostekhidat, 1956).

Giả sử $A$ là một điểm nào đó không trùng với tâm $P$ của một đường tròn bán kính cho trước $k$. Đảo ngược với $A$ điểm $A'$ (tức là ảnh của điểm $A$ khi đảo ngược) được xác định như sau. Điểm này nằm trên tia $PA$ (xem Hình 4) và khoảng cách của nó với tâm $P$ thỏa mãn phép nghịch đảo tương ứng.

⟦folio 38⟧

Bây giờ chúng ta hãy liệt kê một số tính chất của nghịch đảo.

1. Một đường thẳng đi qua tâm P nghịch đảo sẽ biến thành chính nó trong quá trình nghịch đảo.

2. Đường thẳng nào không đi qua tâm P của phép nghịch đảo sẽ đi vào đường tròn đi qua điểm P và ngược lại (Hình 5, a, 6).

3. Một đường tròn không đi qua tâm P của nghịch đảo sẽ biến đổi trong quá trình đảo ngược thành một đường tròn khác cũng không đi qua điểm P (Hình 6, a, 6), hoặc có lẽ, vào cùng một đường tròn. Khả năng thứ hai được thực hiện trong hai trường hợp: 1) khi đường tròn này tương đối với đường tròn nghịch đảo (Hình 4); 2) khi đường tròn này trùng với đường tròn nghịch đảo.

Bạn có thể tìm thấy bằng chứng về những đặc tính này trong bài viết đã được đề cập của A. P. Savin và cuốn sách của I. M. Yaglom.

Lý thuyết nghịch đảo có thể dễ dàng được chuyển từ mặt phẳng sang không gian: điều này không khó để xác minh nếu chúng ta xem xét các vật thể không gian, do phép quay của các hình thể hiện trong Hình 4-6, thu được xung quanh đường tâm (PA, hoặc PB, hoặc PO₁). Cho một hình cầu Σ có tâm P và bán kính k; chúng ta định nghĩa một điểm nghịch đảo với một điểm A cho trước đối với mặt cầu Σ là một điểm A' thuộc tia PA và sao cho khoảng cách |PA|·|PA'|=k².

Trong sự biến đổi này, quả cầu nghịch đảo biến thành chính nó. Các hình cầu trực giao với hình cầu nghịch đảo cũng biến thành chính chúng trong quá trình đảo ngược: hình cầu nghịch đảo chia hình cầu trực giao với nó thành hai phần, trong quá trình đảo ngược “hoán đổi vị trí”.

Lý thuyết sẽ chỉ ra cách giải bài toán M305 6) bằng phép nghịch đảo. Xét một mặt cầu Σ có tâm tại một điểm P cho trước, trực giao với một mặt cầu S cho trước. Chúng ta hãy thực hiện một phép nghịch đảo đối với mặt cầu Σ. Trong trường hợp này, hình cầu S sẽ chuyển vào chính nó, và bất kỳ điểm A nào của đường tròn σ∈S sẽ chuyển điểm A' đảo ngược của nó: điểm giao nhau thứ hai của tia PA với hình cầu S. Do đó, các điểm của tập hợp σ' là các điểm có nghịch đảo tương ứng với các điểm của đường tròn σ và ngược lại. Từ tất cả các nhận xét được đưa ra trước đó, suy ra rằng σ' là một đường tròn.

I. N. Klumova

Rõ ràng, phần còn lại của bảng có thể được cắt thành 18 hình tam giác có kích thước bằng nhau (Hình 7). Hãy chứng minh rằng không thể cắt thành 17 hình tam giác được nữa.

Trên thực tế, nếu phần còn lại của tấm bảng có thể được cắt thành 17 hình tam giác có kích thước bằng nhau thì diện tích của mỗi hình sẽ lớn hơn $\frac{7}{2}$ (cụ thể là $\frac{63}{17}$).

Hãy xem xét hai hình tam giác, các đáy của chúng chứa cạnh (hoặc một phần cạnh) của ô bị loại bỏ và đỉnh của ô này nằm bên trong bảng (Hình 8). Chiều cao của các hình tam giác này không vượt quá 7 và đáy của một trong số chúng không quá 1. Do đó, diện tích của ít nhất một trong các hình tam giác đang xem xét không thể lớn hơn $\frac{7}{2}$.

Vì vậy, số hình tam giác có kích thước bằng nhau nhỏ nhất có thể cắt phần còn lại của bảng là 18.

V. P. Fedomov

⟦folio 39⟧

M307. Máy bay được chia thành các phòng có sáu bức tường giống hệt nhau. Một số bức tường có cửa hình hoa anh túc, do đó, ở bất kỳ đỉnh nào mà ba bức tường (các cạnh của cột) gặp nhau, sẽ có cửa ở đúng hai bức tường. Chúng ta hãy chứng minh rằng bất kỳ con đường khép kín nào đi qua mê cung đều đi qua một số cửa chẵn.

Bây giờ chúng ta có một đường đi khép kín dọc theo các đường màu đỏ. Nói chung, nó có thể vượt qua chính nó. Nhưng nếu anh ta đi qua cùng một phòng hai lần, chúng ta sẽ chia anh ta thành d theo một đường kín. Chúng ta sẽ làm điều này cho đến khi chia đường dẫn này thành nhiều đường dẫn khép kín không tự giao nhau. Vì vậy, chỉ cần lưu ý rằng mọi đường đi không tự giao nhau đều có số đoạn chẵn.

Cho chúng ta một đường dẫn khép kín không tự giao nhau $L$ (một đường dẫn như vậy được hiển thị trong Hình 9 bằng các mũi tên). Nó giới hạn phần mặt phẳng gồm các hình thoi. Đặt $A$ hình thoi trong đó. Chúng chỉ có cạnh 4A. Để tìm ra số đoạn của đường đi $L$, cần phải trừ từ số 4A số gấp đôi của các cạnh mà các hình thoi gặp nhau. Sự khác biệt sẽ là một số chẵn, theo yêu cầu.

Bạn có thể đạt được lời giải khác bằng cách đảm bảo rằng đối với một bố cục nhất định, có thể sơn các phòng bằng hai màu để các phòng liền kề có các màu khác nhau (Hình 10).

A. L. Toom

F312. Vòng của padus $R$ đang chuyển động với tốc độ $v$ trên mặt phẳng nằm ngang, trong khi chúng ta đang bay không đàn hồi theo phương trình abscilton thì khi chúng ta di chuyển ra khỏi bậc thang thì động lượng của vòng sẽ thay đổi. Từ phía của bậc thang, một lực tác dụng lên vòng hướng dọc theo tấm đệm $R$ vòng (Hình 11). Do đó, động lượng của vòng thay đổi khi nó bước sao cho hình chiếu của nó lên trục $OX$, chạy dọc theo bệ $R$, trở thành bằng 0. Hình chiếu của xung lên trục $OY$ không thay đổi. Do đó, nhờ bước này, xung của vòng có giá trị abscyl bằng $mv \sin \alpha$ và tốc độ của nó trở thành $v \sin \alpha = v \frac{R-h}{R}$ (xem Hình 11). Bây giờ chúng ta sử dụng định luật bảo toàn năng lượng. Ngay sau khi tháo ra, vòng có động năng $\frac{mv^2}{2}\left(\frac{R-h}{R}\right)^2$. nâng cao-

⟦folio 40⟧

Khi đặt lên bậc thang, vòng sẽ có thế năng $mgh$ và một phần động năng $\frac{mv_h^2}{2}$; kể từ đây,

$$\frac{mv_h^2}{2} \left( \frac{R-h}{R} \right)^2 = mgh + \frac{mv_h^2}{2}.$$

Từ đây chúng ta sẽ tìm được tốc độ mà vòng sẽ có khi nó “chạy lên” bước:

$$v_h = \sqrt{v^2 \left( \frac{R-h}{R} \right)^2 - 2gh}.$$

Nếu tốc độ $v_{\min}$ là tốc độ tối thiểu mà vòng sẽ “chạy lên” đến bậc thang thì trên bậc thang đó nó sẽ chỉ có thế năng, tức là

$$v_h = \sqrt{v_{\min}^2 \left( \frac{R-h}{R} \right)^2 - 2gh} = 0.$$

Từ đây

$$v_{\min} = \frac{R}{R-h} \sqrt{2gh}.$$

Tôi. Sh. Slobodetsky

F313. Chiết suất của khí quyển phẳng giảm theo độ cao $h$ so với bề mặt của nó theo định luật $n = n_0 - \alpha h$. Bán kính của kế hoạch là $R$. Cụ thể là ở độ cao nào $h_0$ phía trên bề mặt của mặt phẳng có một kênh quang mà qua đó các tia sáng sẽ đi qua mặt phẳng, giữ nguyên ở độ cao không đổi. Chúng ta hãy nhìn vào hai tia cực trị.

Một chùm tia còn lại ở độ cao không đổi $h_0$ (Hình 12) sẽ kịp thời vượt qua kế hoạch

$$t = \frac{2\pi(R+h_0)}{v_1} = 2\pi(R+h_0) \frac{n_0 - \alpha h_0}{c}.$$

Một tia khác của cùng một kênh ánh sáng, vắng mặt so với tia đầu tiên ở khoảng cách $\Delta h \ll h_0$, phải đi qua mặt phẳng ở độ cao $h_0 + \Delta h$ trong cùng một thời điểm (chỉ trong trường hợp này, mặt trước của sóng ánh sáng truyền dọc theo kênh sẽ vuông góc với một đường tròn bán kính $R + h_0$):

$$t = \frac{2\pi(R+h_0 + \Delta h)}{v_2} = 2\pi(R+h_0 + \Delta h) \frac{n_0 - \alpha(h_0 + \Delta h)}{c}.$$

Đánh đồng thời gian lan truyền và tính đến $\Delta h \ll h_0$, chúng ta thấy

$$h_0 = \frac{1}{2} \left( \frac{n_0}{\alpha} - R \right).$$

Lưu ý rằng khoảng cách là một khúc xạ tròn. Như các quan sát cho thấy, điều đó có thể xảy ra, chẳng hạn như trong bầu khí quyển của Sao Kim.

⟦folio 41⟧

F314. Bằng sự mượt mà và tuyệt đối
rất nhiều grubka kiên cường,
chứa một lượng rất lớn
số lượng đầu gối, bắt đầu từ bao nhiêu
mùa đông của quả bóng (Hình 13). Tìm thấy
tốc độ ổn định
chuyển động ngang của quả bóng
các khu vực khai thác gỗ. Nó có phụ thuộc vào ban đầu không
tốc độ? Chênh lệch độ cao của các đường ngang liền kề
lô h. Xiên
các đồ thị hình thành với góc đường chân trời α.

Di chuyển dọc theo phần nghiêng của ống chính, quả bóng tăng động năng và khi nó di chuyển tại thời điểm chuyển từ phần này sang phần khác, nó sẽ mất năng lượng. Do đó, chúng ta thực sự có thể nói về tốc độ ở trạng thái ổn định $v_{yct}$ của quả bóng chuyển động dọc theo một ống như vậy. Hãy thể hiện điều này một cách chặt chẽ hơn.

Với mỗi lần va chạm, thành phần động lượng của quả bóng, được xác định lại bởi trục uốn cong của ống mà quả bóng đi qua, sẽ bằng 0. Thành phần xung lực hướng dọc theo trục của đầu gối này không thay đổi. Do đó, nếu quả bóng đến gần chỗ uốn cong của ống với tốc độ $v$ thì nó sẽ chuyển động ra xa khỏi ống với tốc độ $v$ góc α (Hình 13).

Gọi vận tốc của quả bóng ở cuối đoạn nằm ngang ban đầu là $v_0$. Sau khi đi qua chỗ gấp sẽ bằng $v_0$ góc α. Khi kết thúc đoạn ban đầu đầu tiên, tốc độ sẽ tăng lên giá trị

$$v_1 = \sqrt{v_0^2 \cos^2 \alpha + 2gh},$$

có thể tìm được bằng cách áp dụng định luật bảo toàn cơ năng

$$\frac{m(v_0 \cos \alpha)^2}{2} + mgh = \frac{mv_1^2}{2}.$$

Trên đoạn nằm ngang thứ hai, tiếp theo sau khi vượt qua chỗ gấp, vận tốc sẽ bằng

$$v_2 = v_1 \cos \alpha = \sqrt{v_0^2 \cos^2 \alpha + 2gh \cos \alpha},$$

trên phần ngang thứ ba -

$$v_3 = \sqrt{v_0^2 \cos^6 \alpha + 2gh \left(\cos^4 \alpha + 1\right) \cos \alpha},$$

vào ngày thứ tư -

$$v_4 = \sqrt{v_0^2 \cos^{10} \alpha + 2gh \left(\cos^8 \alpha + \cos^4 \alpha + 1\right) \cos \alpha},$$

vào ngày thứ n -

$$v_n = \sqrt{v_0^2 \cos^{2(2n-3)} \alpha + 2gh \left(\cos^4(n-2)\alpha + \cos^4(n-3)\alpha + \ldots + 1\right)} \times \cos \alpha = \sqrt{v_0^2 \cos^{2(2n-3)} \alpha + 2gh \frac{1 - \cos^4(n-1)}{\cos^4 \alpha}} \cos \alpha.$$

Vì $\cos \alpha < 1$, đối với $n \cos^2(2n-3) \alpha \ll 1$ và $\cos^4(n-1) \alpha \ll 1$ rất lớn. Do đó, quả bóng sẽ chuyển động dọc theo mặt cắt ngang với tốc độ ổn định

$$v_{yct} \approx \frac{\cos \alpha}{\sqrt{1 - \cos^4 \alpha}} \sqrt{2gh} = \frac{\cos \alpha}{\sin \alpha \sqrt{1 + \cos^2 \alpha}} \sqrt{2gh}.$$

Lưu ý rằng $v_{yct}$ không phụ thuộc vào tốc độ ban đầu $v_0$. Có nghĩa là tốc độ ở trạng thái ổn định là cần thiết theo phương trình (*), trong đó cần đặt $v_{yct} = v_0 = v_1 \cos \alpha$ (xem Hình 13).

⟦folio 42⟧

F315. Một sợi dây xoắn ốc nối với hệ thống chiếu sáng thành phố được tích điện. Một nửa hình xoắn ốc bắt đầu được làm mát (ví dụ bằng nước). Điều này sẽ ảnh hưởng như thế nào đến lượng kim loại được giải phóng bởi nửa đường xoắn ốc này? Tất cả các hình xoắn ốc? Điện áp bảy được coi là không thay đổi.

Cơm. 14.

Cơm. 15.

Chúng ta hãy biểu thị điện trở của mỗi nửa xoắn ốc trước khi bắt đầu nguội là $R$ (Hình 14). Vì điện trở của kim loại phụ thuộc vào nhiệt độ (tăng khi nóng lên và giảm khi nguội) nên việc làm lạnh một nửa của hình xoắn ốc sẽ dẫn đến điện trở của nửa này giảm xuống một giá trị nhất định $R_1 < R$. Vì điện áp nguồn $U$ không thay đổi nên điều này sẽ làm tăng dòng điện trong mạch và do đó làm nóng thêm nửa còn lại của cuộn dây. Điện trở của nửa này sẽ tăng lên và bằng $R_2 > R$ (Hình 15).

Giá trị hiện tại mới trong mạch $I = \frac{U}{R_1 + R_2}$ sẽ lớn hơn giá trị trước đó $I_0 = \frac{U}{2R}$. Thật vậy, chúng ta hãy giả sử điều ngược lại rằng $I \leqslant I_0$. khi đó điện trở của nửa xoắn ốc không được làm mát giữ nguyên hoặc giảm ($R_2 \leqslant R$), và điện trở của nửa xoắn ốc được làm mát $R_1 < R$. Do đó, tổng điện trở là $R_1 + R_2 < 2R$ và giá trị hiện tại mới là $I > I_0$, điều này mâu thuẫn với giả định của chúng tôi.

Vì vậy, $I > I_0$, và do đó công suất giải phóng trong toàn bộ mạch (tức là lượng nhiệt trên một đơn vị thời gian) $P = IU$ sẽ tăng lên.

Vì $I > I_0$ và $R_2 > R$, lượng nhiệt $P_2 = I^2 R_2$ giải phóng ở nửa không được làm mát cũng sẽ tăng lên.

Ngược lại, công suất $P_1 = I^2 R_1 = \frac{U^2 R_1}{(R_1 + R_2)^2}$ được giải phóng ở nửa đã nguội sẽ làm giảm công suất $P_0 = I^2 R = \frac{U^2}{4R}$. Hãy thể hiện nó.

Hãy tìm tỉ số $P_0/P_1$:

$$\frac{P_0}{P_1} = \frac{U^2}{4R} : \frac{U^2 R_1}{(R_1 + R_2)^2} = \frac{(R_1 + R_2)^2}{4R_1 R_2}.$$

Rõ ràng là

$$\frac{(R_1 + R_2)^2}{4R_1 R} > \frac{(R_1 + R_2)^2}{4R_1 R_2},$$

và biểu thức cuối cùng lớn hơn hoặc bằng 1, vì trung bình hình học của hai đại lượng $(\sqrt{R_1/R_2})$ không vượt quá trung bình số học $(\frac{R_1 + R_2}{2})$.

Do đó, thực sự $P_1 < P_0$, tức là công suất giải phóng ở nửa xoắn ốc đã nguội sẽ giảm.

F316. Nếu các mặt lồi “hình ngôi sao” đa dạng, được làm bằng nhựa, có lực ném mạnh theo phương thẳng đứng xuống dưới thì nó sẽ nảy lên như một quả bóng cao su đàn hồi, thực tế không bị nhăn. Ở thời của tôi, nhựa tan chảy rất dễ bị nhăn bằng tay. Tại sao?

Dưới tác dụng của ngoại lực, bất kỳ vật thể nào cũng có thể bị biến dạng. Nếu một vật thoát khỏi tác dụng của lực được khôi phục lại hình dạng và kích thước ban đầu thì biến dạng đó được gọi là đàn hồi. Nếu vật không hoàn toàn trở lại hình dạng ban đầu thì người ta nói rằng cùng với biến dạng đàn hồi, biến dạng dẻo cũng xảy ra.

Vật liệu có thể chịu được các biến dạng dẻo mà không bị phá hủy, có giá trị rất lớn so với độ lớn biến dạng đàn hồi được gọi là nhựa. Ngược lại, nếu vết nứt xảy ra sau khi biến dạng dẻo rất nhỏ so với biến dạng đàn hồi thì vật liệu được gọi là giòn.
