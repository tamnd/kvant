---
id: 1990-12-resheniya-zadach-m1231-m1235-f1243-f1247-363cace5
issue: kvant_1990_12
year: 1990
number: "12"
title: Lời giải bài toán M1231—M1235; F1243—F1247
rubric: zadachnik-kvanta
rubric_sub: Задачник «Кванта»
page_first: 23
page_last: 31
page_labels: 21-29
lang: vi
source: kvant_digital
extraction: vision
content_sha256: 3bc821f29dd07c024fd4dbf069a860145dc26471028d87e86b4030812b51620b
prompt_sha256: draft-1
translated_from: content/ru/1990/12/articles/07_resheniya-zadach-m1231-m1235-f1243-f1247-363cace5.md
source_content_sha256: f2fd08628350eca40d13af97803e0a108eb162a8dc4b21e113e5ed8bd4dc000d
translation_model: draft
translation_run: vi-draft-gaps-2026-11-06
translation_quality: draft
---

⟦folio 21⟧

Lời giải bài toán

M1231 — M1235, F1243 — F1247

M1231. Đồ thị $n$ của tam thức vuông có dạng $y = ax^2 + bx + c$ ($n=1, 2, 3, \dots$) có thể chia mặt phẳng Oxy tối đa là bao nhiêu phần?

Đáp số: $n^2 + 1$.
Hãy chứng minh bằng quy nạp rằng số phần không vượt quá $n^2 + 1$. Đối với $n=1$ điều này rõ ràng: parabol chia mặt phẳng thành nhiều nhất $(n-1)^2 + 1$ phần. Hãy chạy biểu đồ thứ $n$-thứ cuối cùng. Nó giao với mỗi cực đại $n-1$ trước đó tại hai điểm, tức là nó sẽ được chia thành không quá $2(n-1)+1=2n+1$ phần (bao gồm cả hai phần cực đại tiến đến vô cùng). Mỗi mảnh parabol này chia một trong các phần hiện có của mặt phẳng thành hai. Như vậy, khi thực hiện các parabol cuối cùng, số phần sẽ tăng không quá $2n+1$, tức là không vượt quá $(n-1)^2 + 1+2n+1=n^2 + 1$.

Có thể dễ dàng xây dựng một ví dụ khi tất cả các đồ thị giao nhau theo cặp tại hai điểm (xem hình) - điều này sẽ dẫn đến số phần tối đa được chỉ định trong đáp số.

Theo cách tương tự, bạn có thể tính số phần tối đa mà mặt phẳng $n$ của đường thẳng, $n$ của hình tròn, v.v. được chia thành.

N. Vasiliev

⟦folio 22⟧

---
running_head:
folio:
---

M1232. Bà chủ nướng một ngưỡng cho khách. Có thể có p người hoặc q người ở bàn. Số phần tối thiểu (không nhất thiết phải bằng nhau) mà ngưỡng phải được cắt trước là bao nhiêu để trong mọi trường hợp có thể chia thành từng phần? Hãy xem xét các trường hợp sau:
a) p và q là các số nguyên tố cùng nhau,
b) p và q có ước chung nhất d.

Hình 1.

Hình 2.

Đáp số: a) $p+q-1$; b) $p+q-d$.

Để đưa ra ví dụ về yêu cầu cắt, chúng ta hãy tưởng tượng ngưỡng ở dạng đoạn chia cho $p-1$ điểm thành $p$ phần bằng nhau và $q-1$ điểm thành $q$ phần bằng nhau. Với $p$ và $q$ nguyên tố chung thì sẽ có tổng cộng $p+q-2$ điểm chia, còn với GCD ($p, q)=d$ thì chỉ rút ra $p+q-d-1$ các điểm chia khác nhau ($d-1$ số điểm chia trùng nhau) nên đoạn đó sẽ rơi chính xác vào số phần ghi ở đáp số. (Rõ ràng là có thể cắt ngưỡng theo cách tương tự: nếu nó có hình dạng của một góc vuông; chỉ cần thực hiện các vết cắt song song với một bên là đủ.)

Ví dụ: trên hình 1, trong đó $p=5, q=3$, tất cả 6 điểm phân chia đều khác nhau và đoạn được chia thành 7 phần và trên hình 2, trong đó $p=15, q=12$ và $d=3$, có 23 điểm phân chia khác nhau và đoạn được chia thành 24 phần.

Chúng tôi trình bày hai bằng chứng khác nhau rằng số lượng mảnh được chỉ ra trong đáp số là tối thiểu.

Chúng tôi sẽ trình bày ngay bằng chứng đầu tiên cho các điểm chung bài toán.

Cắt ngưỡng thành nhiều phần sao cho thỏa mãn điều kiện bài toán. Chúng ta hãy chọn $p$ khách của nhóm thứ nhất và $q$ khách của nhóm thứ hai làm điểm trên mặt phẳng và nối với các phân đoạn những khách có đủ mảnh giống nhau (xem ví dụ trong hình). Ta sẽ được hệ các đỉnh và các cạnh của một đồ thị nhất định. Hãy xem xét một số thành phần liên thông của biểu đồ này (tập hợp tất cả các đỉnh trong đó một đỉnh có thể được thêm vào dọc theo các cạnh của biểu đồ). Hãy ghép các mảnh tương ứng với các cạnh của thành phần này lại với nhau. Từ chúng, có thể thu thập một số nguyên của $k$ phần của $1/p$ porg và một số nguyên của $m$ phần của $1/q$ porg. Nhưng nếu $k/p=m/q$ thì $k$ phải được chia cho $p/d$ và $m$ cho $q/d$, do đó, trong thành phần này, các phần được thu thập tạo nên ít nhất một inch của các phần $d$ của porg. Nếu $p$ và $q$ là nguyên tố cùng nhau, $d=1$ và chỉ có một thành phần thì trong trường hợp chung có nhiều nhất là $d$. Nhưng trong mỗi thành phần, số đỉnh không lớn hơn số cạnh 1. (Bằng cách loại bỏ một số cạnh, bạn có thể lấy một cây từ nó - một biểu đồ trong đó một đường đi dẫn từ mỗi đỉnh này đến bất kỳ đỉnh nào khác. Đối với nó, số đỉnh lớn hơn số cạnh 1.) Do đó, tổng số phần không vượt quá $p+q-d$.

Chúng tôi trình bày cách chứng minh thứ hai, ngắn hơn, chỉ cho điểm a), tức là đối với trường hợp $p$ và $q$ nguyên tố cùng nhau. Ở đây lưu ý rằng bài toán của chúng ta tương đương với giá trị sau: chứng minh rằng số lượng số nhỏ nhất phải đặt trong các ô của bảng $p \times q$ sao cho tổng hàng là $1/p$ và tổng cột là $1/q$ là $p+q-1$.

Hãy để chúng tôi chứng minh một thực tế tổng quát hơn. Giả sử $a_1, a_2, \dots, a_p$ và $b_1, b_2, \dots, b_q$ là hai tập hợp số dương có cùng tổng và sao cho không có tổng con nào của các số của tập thứ nhất bằng bất kỳ tổng con nào của tập thứ hai. Khi đó số số viết được vào các ô của bảng $p \times q$ sao cho tổng ở hàng và cột lần lượt bằng số của hai tập hợp này không nhỏ hơn $p+q-1$. Áp dụng thực tế này cho tập hợp số

⟦folio 23⟧

---
running_head:
folio:
---

1/p,..., 1/p và 1/q,..., 1/q (sự đơn giản lẫn nhau của p và q đảm bảo thỏa mãn điều kiện tổng), ta thu được kết quả mong muốn.

Hãy tiến hành quy nạp trên p+q (với p=q=1 mọi thứ đều rất/không). Đặt p>q. Khi đó ở một hàng nào đó của bảng chỉ có một số thuộc nhóm đầu tiên (nếu không thì tổng số số trong bảng không nhỏ hơn 2p>p+q-1) - gọi đó là số a₁, đứng ở hàng đầu tiên và cột đầu tiên, b₁ - tổng các số trong cột này. Sau khi gạch bỏ dòng đầu tiên, chúng ta áp dụng câu lệnh cho các tập hợp a₂, a₃,..., a_p và b₁-a₁, b₂,..., b_p - đối với nó số lượng các số ít hơn 1 và điều kiện về tổng con rất thỏa mãn. Theo giả thuyết quy nạp, bảng (p-1)×q phải chứa ít nhất các số (p-1)+(q-1)=p+q-2. Bằng cách cộng số bị loại bỏ a₁, chúng ta có được ước tính p+q-1 mong muốn cho bảng p×q.

A. Tolpygo, D. Fomin

M1233. Cho ABCD, đường chéo AC bằng cạnh BC, H là trung điểm của đáy AB. Gọi l là đường thẳng đi qua H, P và Q lần lượt là giao điểm của đường l với đường thẳng AD và BD. Chứng minh rằng các góc ACP và QCB bằng nhau hoặc tổng bằng 180°.

Gọi K lần lượt là giao điểm của đường thẳng l và CD, M và N lần lượt là giao điểm của đường thẳng CP và CQ với đường thẳng AB. Hãy chứng minh đẳng thức AM=BN. Từ đây phát biểu bài toán sẽ tuân theo: các góc ACM và BCN bằng nhau, và các góc chúng ta cần ACP và BCQ lần lượt bằng các góc này hoặc chúng bù nhau tới 180°. Từ sự giống nhau của các tam giác ta tìm được

$$\frac{DC}{AM} = \frac{DP}{AP} = \frac{DK}{AH}, \frac{DC}{BN} = \frac{DQ}{BQ} = \frac{DK}{BH}.$$

Vì AH=BH nên điều này hàm ý đẳng thức mong muốn AM=BN.

Bạn có thể chứng minh đẳng thức này mà không cần tính toán bằng cách đi vào không gian. Xét hình chiếu tâm của mặt phẳng lên một mặt phẳng p khác chứa đường thẳng AB, rồi chọn tâm hình chiếu O sao cho mặt phẳng OCD song song với p. Với hình chiếu tâm như vậy (ảnh hình 1 - hình 2) mọi đường thẳng đi qua điểm C sẽ song song với nhau và mọi đường thẳng

⟦folio 24⟧

---
running_head:
folio:
---

đi qua $D$, - cũng vậy; do đó, hình ảnh $P'$ và $Q'$ của các điểm $P$ và $Q$ sẽ đối xứng với $H$, và do đó các điểm $M$ và $N$ cũng vậy.

I. Sharyzin, V. Dubrovsky

M1234. Có thể chia tam giác nào a) thành 7, 6)* thành 5 tam giác đồng dạng không?

Hình 1.

Hình 2.

$\alpha = a_{11}X + a_{12}Y + a_{13}Z,$
$\beta = a_{21}X + a_{22}Y + a_{23}Z,$
$\gamma = a_{31}X + a_{32}Y + a_{33}Z.$

Thật dễ dàng để có được sự phân chia thành 7 hình tam giác - chỉ cần cắt hình tam giác thành 4 phần bằng cách sử dụng các đường ở giữa và cắt lại một trong các hình tam giác thu được thành 4 bằng các đường ở giữa (hình 1). Lưu ý rằng thật dễ dàng để có được sự mở rộng thêm 6, 8 hoặc bất kỳ số lượng lớn hơn nào của những cái tương tự (hình 2) bằng cách thêm 3 hình tam giác vào những cái hiện có.

Chứng minh rằng không phải mọi tam giác đều có thể chia thành 5 tam giác đồng dạng. Chúng tôi sẽ đưa ra hai bằng chứng, mỗi bằng chứng cho một số tam giác có các góc khác nhau (và không vuông) $\alpha > \beta > \gamma$. Cả hai đều dẫn đến thực tế là các hình tam giác phân vùng phải giống với hình tam giác ban đầu - nó có cùng các góc $\alpha, \beta, \gamma$. Lý luận sâu hơn không phải là khó khăn. Nếu các hình tam giác giống nhau được cắt khỏi một hình tam giác ở các góc thì phần còn lại chỉ có thể cắt thành hai hình tam giác nếu đó là hình tam giác hoặc hình tứ giác (hình 3). Nhưng trong trường hợp chung, một vết cắt như vậy hóa ra có hai góc cộng lại là $180^\circ$, trong khi trong số các góc $\alpha, \beta, \gamma$ không có góc nào như vậy.

Hãy để chúng tôi trình bày hai lập luận. Đầu tiên hoàn toàn là đại số (thuộc về tác giả đầu tiên). Xét một tam giác có các góc $\alpha, \beta, \gamma$ độc lập hữu tỉ, tức là không có số nguyên nào khác 0 $k, l, m$ sao cho $k\alpha + l\beta + m\gamma = 0$. Để tất cả các đỉnh hội tụ tại một hoặc một số góc của tam giác có độ lớn là $X, Y, Z$. Khi đó các đẳng thức được chỉ ra trong các trường được thỏa mãn, trong đó các hệ số $a_{ij}$ là số nguyên không âm. Nếu tất cả các hệ số của một trong các góc $X, Y$ hoặc $Z$ đều bằng 0, thì có thể chứng minh (bằng cách biểu thị hai góc còn lại từ hai phương trình đầu tiên theo $\alpha$ và $\beta$ và thay chúng vào phương trình thứ ba) rằng $\alpha, \beta, \gamma$ phụ thuộc hợp lý nên trường hợp này là không thể. Nhưng nếu sau khi cộng ba phương trình, chúng ta thấy rằng các hệ số của $X, Y, Z$ đều dương thì tất cả chúng phải bằng 1, vì

$$\alpha + \beta + \gamma = X + Y + Z = 180^\circ.$$

Từ đây rõ ràng là trong mỗi phương trình chỉ có một hệ số 1 và hai hệ số còn lại bằng 0 - đây là điều cần phải chứng minh.

Thứ hai là một bằng chứng hình học (ý tưởng của ông được đề xuất bởi I. Arzhantsev, một người tham gia trại hè toán học Mỹ-Liên Xô, nơi bài toán này đã được thảo luận), làm ơn, thậm chí còn đơn giản hơn.

Giả sử trong số các góc $\alpha, \beta, \gamma$ của tam giác $\alpha$ của chúng ta có nhiều (hơn 5 lần) lớn hơn $\beta$ và $\beta$ lớn hơn nhiều so với $\gamma$. Giả sử rằng nó được chia thành 5 cái tương tự. Để một số đỉnh của nó bị phá vỡ và $\alpha_1, \beta_1, \gamma_1$ —

⟦folio 25⟧

---
running_head:
folio:
---

phần lớn nhất trong số các phần lần lượt tạo nên các góc $a$, $b$ và $\gamma$. Vì mỗi góc được chia thành không quá 5 phần nên $\alpha_1 > \beta_1 > \gamma_1$. Vì vậy, đây là các góc của tam giác phân vùng, tổng của chúng bằng $180^\circ$, và do đó, chúng tương ứng bằng $a$, $b$, $\gamma$; do đó, thực sự không có đoạn nào thoát ra khỏi các góc.

A. Soifer (Mỹ), N. Vasiliev

M1235*. Cho $p = 2 \cdot q + 1$ là số nguyên tố. Chứng minh số $2^{3q} q! - (-1)^q (2q-1)!!$ chia hết cho $a$) $p$; $b$) $p^2$; $\epsilon$) $p^3$ (tại $p > 3$). (Đây $q! = 1 \cdot 2 \cdot \dots \cdot q$; $(2q-1)!! = 1 \cdot 3 \cdot 5 \cdot \dots \cdot (2q-1)$.)

$p = 5$: 1
11
121
1331
14141
100001

$p = 7$: 1
11
121
1331
14641
153351
1616161
10000001

Môđun tam giác Pascal $p$.

Mệnh đề a) tương đối dễ chứng minh dựa trên tính chất đơn giản của số $C_n^k$ - hệ số khai triển bậc nhị thức

$(1+x)^n = 1+nx + \dots + C_n^k x^k + \dots + x^n$. (*)

Từ công thức $C_n^k = n(n-1) \dots (n-k+1)/k!$, suy ra rằng với số nguyên tố $n$ tất cả các hệ số $C_n^k$, ngoại trừ hai hệ số cực trị, đều chia hết cho $n$ và thực tế là trong tam giác Pascal (trong dòng $n$ có các số $C_0^n = 1$, $C_1^n$, $C_2^n$, ..., $C_n^n = 1$) mỗi số bằng tổng của hai số ở trên nó: $C_n^k + C_n^{k+1} = C_n^{k+1}$. Vì $2^q q! (2q-1)!! = (2q)! = C_2^q q!^2$, $2^q (2^{3q} q! - (-1)^q (2q-1)!!) = q! (2^{4q} - (-1)^q C_2^q)$ và các số $2^q$ và $q!$ là nguyên tố cùng nhau với $p=2q+1$, nên đủ để chứng minh rằng số trong ngoặc đơn cuối cùng chia hết cho $p$.

Chúng ta sẽ xem xét các số “modulo $p$”, cụ thể, “phần dư - 1” sẽ có nghĩa giống như “phần dư $p - 1$”. Hãy chứng minh rằng phần dư của phép chia $C_2^q$ cho $p$ bằng $(-1)^q$. Nếu trong tam giác Pascal, chúng ta thay thế các số bằng số dư của chúng khi chia cho $p$, thì dòng thứ $p$ sẽ có dạng 1 0 0...0 1, và do đó, dòng thứ $2q$ trước đó (bao gồm các số $2q+1$) -

$$1 - 1 1 - 1 \dots 1 - 1 1,$$

vì vậy mức trung bình của nó là $C_2^q = (-1)^q$ (ví dụ về tam giác Pascal modulo $p$ cho $p=5$ và $p=7$ được đưa ra ở lề). Dòng tương tự này cũng sẽ hữu ích cho chúng ta khi tìm số dư cho bậc 2.

Thay $x=1$, $n=2q$ vào công thức (*), ta thấy modulo $p$ số $2^{2q}$ bằng 1 (đây là trường hợp đặc biệt của Định lý nhỏ Fermat), do đó, hiệu $2^{4q} - (-1)^q C_2^q$ mà chúng ta quan tâm modulo $p$ bằng $1 - (-1)^{2q} = 1 - 1 = 0$.

Bằng chứng của tuyên bố 6) được lấy dưới dạng sản phẩm phụ ở cuối Chương VIII của cuốn sách tuyệt vời “Giới thiệu về lý thuyết số” của G. Hardy và F. Wright, thật không may, cuốn sách này vẫn chưa được dịch sang tiếng Nga. Chúng tôi sẽ đưa ra một bằng chứng ngắn hơn. (Tất nhiên, đối với câu $p=3$ 6) là hiển nhiên: $2^3 + 1 = 3^2$. Dưới đây chúng tôi giả định rằng $p>3$, tức là $q>1$.

⟦folio 26⟧

---
running_head:
folio:
---

Định lý nhỏ Fermat. Nếu $p$ là số nguyên tố, $a$ là số tự nhiên và không chia hết cho $p$ thì $a^{p-1}-1$ chia hết cho $p$.

Hãy tưởng tượng tích $2^{3q}q!(2q-1)!!$ là một “đa thức trong $p^2$”:
$$2^{3q}q!(2q-1)!! = 2^{2q}(2q)! = 2 \cdot 4 \cdot \dots \cdot (p-1)(p+1)...(2p-2) = (p-(p-2))...(p-1)(p+1)...(p+(p-2)) = (p^2-(p-2)^2)...(p^2-(2k-1)^2)...(p^2-1)^2 = (p^2-(2q-1)^2)...(p^2-(2k-1)^2)...(p^2-1)^2 = p^{2q}-S_1 p^{2q-2} + \dots + (-1)^k S_k p^{2q-2k} \dots$$
... $-(-1)^q S_{q-1} p^2 + (-1)^q S_q$. (**)

Ở đây $S_k$ là tổng của tất cả các tích của $k$ số $1^2, 3^2, 5^2, \dots, (2q-1)^2$, một phần,
$$S_1 = 1^2 + 3^2 + \dots + (2q-1)^2,$$
$$S_{q-1} = 3^2 \dots (2q-1)^2 + 1^2 \cdot 5^2 \dots (2q-1)^2 + \dots + 1^2 \cdot 3^2 \cdot 5^2 \dots (2q-3)^2 = S_q(1+1/3^2+...+1/(2q-1)^2),$$
$$S_q = (2q-1)!!^2$$ là tích của tất cả $q$ bình phương của các số $1, 3, \dots, (2q-1)$.

Rõ ràng, tất cả các số hạng của tổng cuối cùng (**), ngoại trừ số hạng cuối cùng, đều chia hết cho $p^2$. Theo đó, hiệu $2^{2q}(2q)! - (-1)^q(2q-1)!!^2$ chia hết cho $p^2$ và vì $p$ là số nguyên tố nên loại bỏ các thừa số bổ sung $(2q-1)!!$, không chia hết cho $p$, nên chúng ta thu được kết quả mình cần, hiệu sẽ chia hết cho $p^2$.

Bây giờ chúng ta hãy trình bày bằng chứng cho phát biểu cuối cùng, mạnh mẽ nhất trong mỗi khám phá về điều đáng kinh ngạc (các ví dụ về $p=5, 7, 11, 13$ được đưa ra bên lề).

Tất cả các số hạng của tổng $S_1$ đều có số dư khác nhau khi chia cho $p$, vì hiệu $i^2-j^2 = (i-j)(i+j)$ không chia hết cho $p$ đối với $i, j$ lẻ, $1<i<j<p$. Điều tương tự cũng có thể nói về số tiền $S_{q-1}$. Nhưng bình phương của các số tự nhiên không phải là bội số của $p$ chỉ có thể cho $(p-1)/2=q$ số dư khác nhau khi chia cho $p$ (vì bình phương $i$ và $p-i$ cho cùng số dư). Tất cả số dư này xuất hiện một lần trong cả hai tổng $S_1$ và $S_{q-1}$, bao gồm cùng số số hạng $(p-1)/2=q$, vì vậy cả hai tổng đều có số dư bằng nhau khi chia cho $p$.

Tổng đầu tiên rất dễ tính - nó bằng $p(p-1)(p-2)/6$ (bạn có thể sử dụng quy nạp) và chia hết cho $p$ khi $p>3$. Do đó, tổng thứ hai được chia cho $p$.

(Chúng ta có thể chứng minh rằng tổng $S_k$ của tất cả các tích với $k$ bình phương của các số $1, 3, 5, \dots, 2q-1$ cho mỗi $k<q$ chia hết cho $p$, nhưng chúng ta không cần điều này.)

Vì $S_{q-1}$ chia hết cho $p$, nên hiệu
$$2^{2q}(2q)! - (-1)^q(2q-1)!!^2$$
chia hết cho $p^3$. Sau khi loại bỏ các thừa số thừa không chia hết cho $p$, chúng ta có được thứ mình cần, hiệu sẽ chia hết cho $p^3$.

I. Vainshtein

⟦folio 27⟧

---
running_head:
folio:
---

F1243. Một con gián và hai con bọ có thể sử dụng một chiếc bàn ngang lớn. Mỗi con bọ có thể đạt tốc độ lên tới $v=1$ cm/s. Lúc đầu, côn trùng đang ở các đỉnh của một tam giác đều. Một con gián có thể phát triển với tốc độ bao nhiêu để ngay cả khi có bất kỳ sự thay đổi nào ở con bọ, hình tam giác vẫn giữ nguyên?

Hãy xem xét một khoảng thời gian ngắn $\Delta t$, sau đó con bọ đầu tiên di chuyển đến $\vec{s}_1=\vec{v}_1\Delta t$ và con thứ hai đến $\vec{s}_2=\vec{u}_2\Delta t$. Chúng ta hãy tìm xem hỗn hợp của con gián sẽ như thế nào để tam giác nối chúng vẫn bằng nhau.

Hãy để chúng tôi lý luận tuần tự. Trước tiên, chúng ta hãy giả sử rằng con bọ đầu tiên bất động và con thứ hai đã chuyển động $\vec{s}_2$ (hình 1). Để tam giác $J_1J_2T'$ là đều, con gián phải di chuyển đến $\vec{T'T'}$, và

$$|\vec{T'T'}|=|\vec{s}_2|=v_2\Delta t.$$

Bây giờ hãy để con bọ thứ hai bất động và con bọ đầu tiên được trộn lẫn ở $\vec{s}_1$. Sau đó con gián sẽ phải trộn

Hình 1.

Hình 2. Hình 3.

di chuyển đến $T'T''$, trong khi

$$|\vec{T'T''}|=|\vec{s}_1|=v_1\Delta t.$$

Vì vậy, nếu một con bọ di chuyển đến $\vec{s}_1$, con thứ hai - đến $\vec{s}_2$, thì con gián sẽ di chuyển đến

$$\vec{T'T'}+\vec{T'T''}=\vec{T'T''}.$$

Từ tam giác $TT'T''$ (hình 2) ta có

$$|\vec{T'T'}| \leqslant |\vec{T'T'}|+|\vec{T'T'}|=(v_1+v_2)\Delta t.$$

Điều này có nghĩa là tốc độ phát triển của một con gián có liên quan tương ứng đến tốc độ của bọ cánh cứng.

$$v_\tau=\frac{|\vec{T'T'}|}{\Delta t} \leqslant v_1+v_2 \leqslant 2v.$$

Đẳng thức tương ứng với trường hợp hỗn hợp của con gián $TT'$ và $T'T''$ hướng về cùng một hướng. Để làm được điều này, tốc độ của bọ cánh cứng phải được định hướng, chẳng hạn như trong hình 3.

A. Korshkov

F1244. Tủ lạnh gia dụng duy trì nhiệt độ không đổi $-12^\circ\text{C}$ trong buồng. Ở nhiệt độ

Chênh lệch nhiệt độ $\Delta T$ bên ngoài, bên trong tủ lạnh và thời gian tạm dừng lâu $\tau_2$ lần lượt có liên quan với nhau

$$\tau_2\Delta T=\text{const.}$$

(1)

⟦folio 28⟧

---
running_head:
folio:
---

Đối với một máy làm lạnh lý tưởng, đẳng thức sau đây có giá trị:
$$\frac{A}{Q} = \frac{\Delta T}{T},$$
trong đó $A$ là hoạt động của động cơ, $Q$ là lượng nhiệt được tối ưu hóa từ bên trong buồng làm lạnh, $T$ là nhiệt độ của buồng. Rõ ràng công mà động cơ thực hiện tỷ lệ thuận với thời gian $\tau_1$ hoạt động của động cơ -
$$A \sim \tau_1,$$
và lượng nhiệt tối ưu tỷ lệ thuận với tổng “chu kỳ” $(\tau_1 + \tau_2)$ và chênh lệch nhiệt độ -
$$Q \sim (\tau_1 + \tau_2) \Delta T,$$
có thể được viết một cách có ý nghĩa
$$\frac{\tau_1 + \tau_2}{\tau_1} (\Delta T)^2 = T = \text{const.}$$

Thay các giá trị $\tau_1$ và $\tau_2$ vào các đẳng thức (1) và (2) cho trường hợp đầu tiên và $\Delta T$ cho cả hai trường hợp, ta tìm được các giá trị mới $\tau'_1$ và $\tau'_2$ cho trường hợp thứ hai:
$$\tau'_1 = 2 \text{ min}, \tau'_2 = 4,1 \text{ min.}$$

Nhiệt độ tối đa có thể có trong phòng là $\tau''_2 = 0$:
$$\Delta T_{\text{max}} = \Delta T \sqrt{8/5} = 46,8 \text{ K},$$
$$t_{\text{max}} = 34,8 \text{ °C.}$$

R. Alexandrov

F1245. Trong mạch ở hình, ampe kế chỉ dòng điện 10 mA, vôn kế chỉ chiều 2 V. Sau khi ngắt điện trở ra khỏi vôn kế và mắc song song với ampe kế, ampe kế hiển thị giảm xuống 2,5 mA. Sử dụng dữ liệu này, xác định điện trở của vôn kế? Có thể xác định điện trở của ampe kế và hướng của pin từ dữ liệu này không? Pin được coi là lý tưởng.

Trong trường hợp đầu tiên, hướng qua điện trở $R_x$ bằng
$$U_1 = U_{Rx1} = U \frac{RR_x/(R + R_x)}{r + RR_x/(R + R_x)} = U \frac{RR_x}{r + R_x(R + r)},$$
trong đó $U$ là chiều của pin, $R$ là điện trở của vôn kế, $r$ là điện trở của ampe kế.

Trong trường hợp thứ hai, ampe kế và vôn kế đổi chỗ cho nhau nên chiều qua điện trở sẽ bằng nhau
$$U_{Rx2} = U \frac{rR_x}{rR + R_x(R + r)}.$$
Nó không đồng thời là một hướng trên ammertra; điều này có nghĩa là dòng điện qua nó bằng
$$I_2 = \frac{U_{Rx2}}{r} = \frac{UR_x}{rR + R_x(R + r)} = \frac{U_1}{R}.$$
Từ đây bạn có thể tìm thấy điện trở của vôn kế:
$$R = \frac{U_1}{I_2} = 0,8 \text{ кОм.}$$

Khi đó điện trở của điện trở là

⟦folio 29⟧

---
running_head:
folio:
---

$$R_x = \frac{U_1}{I_1 - U_1/R} = \frac{U_1}{I_1 - I_2} \approx 0.27 \text{ кОм.}$$

Không thể tìm thấy điện trở ampe và điện áp pin từ dữ liệu bài toán.

A. Zilberman

F1246. Hai mạch LC giống hệt nhau được đặt cách xa nhau. Đầu tiên, các dao động được kích thích với biên độ điện áp trên tụ $U_0$. Tại thời điểm điện áp trên tụ điện bằng 0, hãy nối mạch thứ hai (hình 1) bằng dây dẫn. Phân tích các quá trình trong mạch sau khi kết nối. Điều gì sẽ thay đổi nếu kết nối được thực hiện tại thời điểm điện áp trên tụ đạt giá trị lớn nhất?

Hình 1.

Hình 2.

Hãy bắt đầu với trường hợp thứ hai, khi tại thời điểm đóng công tắc, điện áp trên tụ thứ nhất là cực đại, tức là toàn bộ điện tích tập trung vào tụ $C_1$ và không có dòng điện trong cuộn dây $L_1$. Ngay sau khi đóng công tắc, điện áp trên tụ điện bằng $U_1 = U_0$ và $U_2 = 0$. $U_0$ được áp dụng cho các dây kết nối và do điện trở của chúng rất thấp nên quá trình phân phối lại điện tích nhanh chóng (so với chu kỳ dao động) giữa các tụ điện xảy ra trong hệ thống. Vì điện dung bằng nhau nên điện tích được chia đều, tức là

$$U_1' = U_0/2 \text{ и } U_2' = U_0/2.$$

Cuộn dây không tham gia vào quá trình này.

Sau khi phân phối lại điện tích, cả hai mạch đều ở trạng thái ban đầu giống nhau - điện áp trên tụ điện là $U_0/2$, không có dòng điện trong cuộn dây và dao động đồng bộ chung của chúng bắt đầu với tần số $\omega = 1/\sqrt{LC}$ và biên độ điện áp $U_0/2$:

$$u_1(t) = u_2(t) = U_0/2 \cos \omega t.$$

Các quá trình này không bị ảnh hưởng bởi bước nhảy giữa các mạch; sau khi trao đổi phí, nó có thể được gỡ bỏ.

Bây giờ chúng ta hãy thảo luận về trường hợp đầu tiên khi tại thời điểm ban đầu điện áp trên tụ điện thứ nhất bằng 0. Tình huống này phức tạp hơn.

Vì vậy, tại thời điểm đóng công tắc, điện áp trên tụ $C_1$ bằng 0 và qua cuộn dây $L_1$ có dòng điện chạy qua $I_0 = \sqrt{C/L} U_0$ (điều này thu được từ đẳng thức $LI_0^2/2 = CU_0^2/2$). Để mô tả các quá trình tiếp theo trong mạch, chúng tôi lưu ý rằng sau khi đóng phím, một dòng điện một chiều có thể chạy dọc theo mạch $L_1 - L_2$, không tạo ra bất kỳ điện áp nào (chúng tôi bỏ qua điện trở hoạt động của cuộn dây). Chúng ta hãy tưởng tượng sự phân bố dòng điện trong cuộn dây như trong hình 2.

Trong cuộn dây $L_1$ và $L_2$ có điểm bằng nhau và ứng suất bằng nhau $i_1 = i_2 = I_0/2$ chảy và dòng điện một chiều $i = I_0/2$ chạy dọc theo mạch $L_1 - L_2$. Sau đó

$$I_1 = i_1 + i, \quad I_2 = i_2 - i.$$

Lý luận sâu hơn tương tự như trường hợp đầu tiên. Thật vậy, nếu chúng ta tạm thời quên đi dòng điện một chiều $i$, dòng điện này không tạo ra điện áp và do đó không ảnh hưởng đến các quá trình khác trong mạch, thì mạch sẽ có kết quả như ban đầu.
