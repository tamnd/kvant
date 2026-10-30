---
id: 1970-11-resheniya-ea9bff7c
issue: kvant_1970_11
year: 1970
number: "11"
title: Lời giải các bài toán M11—M15; F18—F23
rubric: zadachnik-kvanta
rubric_sub: Задачник «Кванта»
page_first: 31
page_last: 45
page_labels: 29, 30, 31, 32, 33, 34, 35, 36, 37, 38, 39, 41, 42, 43
tag: KSKR
lang: vi
source: kvant_digital
extraction: vision
content_sha256: 0a2423f931ab16a0dbdcc2a15a95caa80da8c6c208235add4f0bac743802b8ec
prompt_sha256: 3ec6b8aabd9b98576af76503cd8a2902b9f5d18e01ee867dfb1228f59c6d52d8
translated_from: content/ru/1970/11/articles/09_resheniya-ea9bff7c.md
source_content_sha256: 50590bd2e7b05730af3ba43a2c5a9d7fc477b1a8834bee11166a4bdc1a822db7
translation_model: gpt-5.6-terra
translation_run: vi-codex-2026-10-31
---

⟦folio 29⟧

M11. Trên 44 cây bố trí theo một đường tròn có 44 chú chim sẻ vui vẻ đậu (mỗi cây một chú). Thỉnh thoảng hai chú sẻ đồng thời bay sang các cây kề bên theo những hướng ngược nhau (một chú theo chiều kim đồng hồ, chú kia ngược chiều). Chứng minh rằng các chú sẻ không tụ lại trên một cây. Còn nếu số chim sẻ và số cây là $n$?

Lời giải. Ta giải bài toán ngay cho $n$ chú sẻ và $n$ cây. Đánh số các cây theo thứ tự (chẳng hạn, theo chiều kim đồng hồ) bằng các số từ 1 đến $n$ (hình 1). Ký hiệu số chim sẻ trên cây thứ $k$ tại một thời điểm bất kỳ là $a_k$ (trên cây thứ nhất là $a_1$, trên cây thứ hai là $a_2$ v.v.). Xét biểu thức

$$S = 1 \cdot a_1 + 2 \cdot a_2 + \dots + ka_k + \dots + na_n.$$

Ta sẽ chỉ ra rằng khi hai chú sẻ bay sang các cây kề bên theo những hướng ngược nhau, thì $S$ hoặc không đổi, hoặc thay đổi một lượng $n$.

Thật vậy, giả sử một con chích nào đó bay từ cây thứ $k$ sang cây kế tiếp theo chiều kim đồng hồ. Khi đó trong tổng $S$ có hai số hạng thay đổi. Nếu $k < n$, thì các số hạng thứ $k$ và thứ $(k+1)$ thay đổi, và tổng của chúng trở thành

$$k (a_k - 1) + (k+1) (a_{k+1} + 1) = ka_k + (k+1) a_{k+1} + 1,$$

nghĩa là tăng thêm 1. Nếu $k=n$, thì số hạng thứ $n$ và số hạng thứ nhất thay đổi, còn tổng của chúng

$$n (a_n - 1) + 1 (a_1 + 1) = na_n + 1 \cdot a_1 - (n-1)$$

giảm đi $n-1$. Ngược lại, nếu con chích bay sang cây bên cạnh ngược chiều kim đồng hồ, thì tổng hoặc giảm đi 1, hoặc tăng thêm $n-1$. Vì vậy, khi hai con chích đồng thời bay sang các cây bên cạnh (một con theo chiều kim đồng hồ, con kia — ngược chiều), thì tổng $S$ hoặc hoàn toàn không thay đổi, hoặc thay đổi một lượng $n$.

Ở thời điểm ban đầu, trên mỗi cây có một con chích,

$$S = 1 \cdot 1 + 2 \cdot 1 + \dots + n \cdot 1 = 1 + 2 + \dots + n = \frac{n (n+1)}{2}.$$

⟦folio 30⟧

Như vậy, sau bất kỳ số lần bay nào, tổng sẽ bằng $\frac{n(n+1)}{2} + np$, trong đó $p$ là một số nguyên nào đó. Nếu tất cả chim sẻ siskin tụ họp trên một cây thứ $q$ nào đó, thì $S$ sẽ bằng $nq$, tức là có đẳng thức $\frac{n(n+1)}{2} + np = nq$, từ đó $n+1+2p = 2q$; $n = 2(q-p)-1$.

Như vậy, nếu $n$ chẵn, chẳng hạn $n = 44$, thì các chim sẻ siskin không thể tụ họp trên một cây. Ta sẽ chỉ ra rằng với $n$ lẻ thì điều đó có thể thực hiện được*).

Xét tình huống ban đầu, khi trên mỗi cây có một chim sẻ siskin đậu. Ta “ra lệnh” cho một chim sẻ siskin ngồi yên tại chỗ và gọi nó là “bất động”. Chia các chim sẻ siskin còn lại thành từng cặp ngồi cách chim bất động một khoảng $r$ lần bay theo hai phía ($r=1, 2, \ldots, \frac{n-1}{2}$). Rõ ràng, mỗi cặp như vậy có thể, sau $r$ lần bay, đến cây nơi chim sẻ siskin bất động đang ngồi.

D. Grigoriev ở thành phố Leningrad, V. Luzgin ở thành phố Georgievsk thuộc vùng Stavropol và các độc giả khác cũng gửi những lời giải tương tự.

Lời giải đã nêu là điển hình cho các bài toán trong đó cần выяснить liệu có thể, bằng một dãy biến đổi nào đó, nhận được một kết quả xác định hay không. Trong trường hợp này, biến đổi là việc hai con chim sẻ bay sang các cây theo những hướng ngược nhau, và ta muốn biết liệu kết quả có thể là tất cả các con chim sẻ tụ tập trên một cây hay không. Để chứng minh rằng có thể, chỉ cần đưa ra một ví dụ về cách làm điều đó. Để chứng minh rằng không thể nhận được kết quả cần thiết bằng bất kỳ biến đổi nào, thường thuận tiện làm như sau: tìm một đại lượng nào đó được bảo toàn trong mọi biến đổi đang xét và có giá trị ban đầu khác với giá trị cần có ở trạng thái cuối (đại lượng như vậy được gọi là bất biến của các biến đổi đã cho). Trong bài toán của chúng ta, đại lượng đó là số dư khi chia tổng $S$ cho $n$.

Những ai đã giải bài toán này sẽ thấy thú vị khi tìm hiểu câu hỏi tổng quát hơn sau đây. Cho hai cách sắp xếp khác nhau của $a$ con chim sẻ trên $n$ cây. Gọi chúng là tương đương nếu có thể nhận được cách này từ cách kia (khi các con chim sẻ bay như đã nêu trong điều kiện bài toán). Làm sao biết được các cách sắp xếp này có tương đương hay không? Còn một câu hỏi nữa. Rõ ràng tập hợp mọi cách sắp xếp có thể của $a$ con chim sẻ trên $n$ cây được chia thành một số lớp tương đương. Có bao nhiêu lớp như vậy?

M12. Những tứ giác nào có thể được cắt bằng một đường thẳng thành hai tứ giác đồng dạng với nhau?

Lời giải. Ta sẽ chứng minh rằng chỉ có hình thang và hình bình hành có tính chất này.

Giả sử tứ giác $ABCD$ được cắt bởi một đường thẳng thành hai tứ giác đồng dạng. Rõ ràng đường thẳng này cắt hai cạnh đối

*) Sự cần thiết của bước chứng minh này, như thấy từ lá thư, không hề rõ ràng đối với tất cả độc giả của chúng tôi. Ta sẽ dừng lại ở đây chi tiết hơn. Đến nay ta đã chứng minh được gì? Chỉ rằng nếu các con chim sẻ đã tụ tập được trên một cây, thì số chim sẻ nhất thiết là số lẻ (đó là điều kiện cần). Bây giờ cần chứng minh rằng điều kiện này cũng đủ, tức là nếu số chim sẻ là số lẻ thì chúng có thể tụ tập trên một cây (từ điều ta đã chứng minh đến nay, điều kiện đủ).

⟦folio 31⟧

diện của tứ giác. Giả sử nó cắt cạnh AD tại điểm K và cạnh BC tại điểm L (hình 2). Sau đây ta sẽ vài lần dùng mệnh đề hiển nhiên sau: nếu biết rằng hai tứ giác EFGH và PQRS đồng dạng và đỉnh E tương ứng với đỉnh P, thì <E = <P, <G = <R và hơn nữa, либо <F = <Q và <H = <S, либо <F = <S và <Q = <H.

Vậy, giả sử rằng các tứ giác ABLK và CDKL đồng dạng (ta chỉ cần dùng đến việc các góc tương ứng của chúng bằng nhau), và chứng minh rằng trong tứ giác ABCD có hai cạnh nào đó song song. Góc α của tứ giác ABLK (<α = <AKL) có thể tương ứng với một trong các góc của tứ giác KLCD.

1) <α tương ứng với <D. Khi đó <α = <D, <γ = <B, AB || KL || CD.
2) <α tương ứng với <C. Khi đó <α = <C, <δ = <B; <B + <C = <α + <δ = 180°, AB || CD; đồng thời <A = <γ, <D = <β (trường hợp <β = = <γ, <A = <D không cần xét riêng, vì khi đó <β + <γ = 180° và <A = <D = <β = <γ = 90°).
3) <α tương ứng với <γ. Khi đó <B = <D, AD || BC và AB || DC, tức là ABCD là hình bình hành.
4) <α tương ứng với <δ. Khi đó <α = <δ = 90°, <B = <C và либо <β = <γ = 90°, AD || BC (hình thang cân hoặc hình chữ nhật), либо <β = <D, <γ = <A, <A + <D = 180°, AB || CD, và nếu đổi ký hiệu thì trường hợp này quy về trường hợp 2).

Chúng tôi đã chứng minh rằng ABCD là một hình bình hành hoặc một hình thang. Dễ thấy rằng, ngược lại, bất kỳ hình bình hành hoặc hình thang nào cũng có thể chia thành hai tứ giác đồng dạng. Bất kỳ đường thẳng nào đi qua tâm đều chia hình bình hành thành hai tứ giác bằng nhau (dĩ nhiên, miễn là đường thẳng không đi theo đường chéo). Hình thang có các đáy a < b được một đường thẳng song song với các đáy và chia chiều cao theo tỉ số $\sqrt{b}/\sqrt{a}$ chia thành hai hình đồng dạng; tất nhiên cần kiểm tra rằng các cạnh tương ứng khi đó tỉ lệ (hình 3): AK/KD = BL/LC = AB/KL=

⟦folio 32⟧

КЛ/DC = $\sqrt{b}/\sqrt{a}$. Hãy thử tìm xem khi nào có thể chia một hình thang thành hai tứ giác đồng dạng bằng một cách tinh vi hơn, tương ứng với trường hợp 2) sau đây, — như trên hình 4 (đáp án: khi và chỉ khi $\sqrt{a}/\sqrt{b} < \sin \alpha/\sin \beta$, trong đó $\alpha < \beta$ – các góc ở đáy lớn hơn của hình thang $b$).

**M13. Chứng minh rằng nếu hiệu giữa số lớn nhất và số nhỏ nhất trong $n$ số thực $a_1, a_2, \ldots, a_n$ bằng $d$, còn tổng các môđun của tất cả $\frac{n(n-1)}{2}$ hiệu từng đôi của các số này

$$\sum_{i<j} |a_i - a_j| \text{ bằng } s, \text{ thì } (n-1) d \leqslant s \leqslant \frac{n^2}{4} d.$$

Lời giải: Đặt các điểm $a_1, a_2, \ldots, a_n$ trên trục số. Khi đó $d$ là khoảng cách giữa hai điểm ngoài cùng trong các điểm này, điểm ngoài cùng bên trái và điểm ngoài cùng bên phải, còn $s = \sum_{i<j} |a_i - a_j|$ là tổng всех khoảng cách từng đôi giữa các số này.

Rõ ràng, có thể coi rằng các điểm được ký hiệu là $a_1, a_2, \ldots, a_n$ theo thứ tự tăng dần: $a_1 \leqslant a_2 \leqslant \ldots \leqslant a_n$ (hình 5). Ký hiệu khoảng cách giữa hai điểm kề nhau $a_k$ và $a_{k+1}$ là $d_k(k=1, 2, \ldots, n-1)$. Rõ ràng, $d = d_1 + d_2 + \ldots + d_{n-1}$.

Bây giờ biểu diễn $s$ qua các đại lượng $d_k$. Để làm điều đó, trong tổng $s$ thay độ dài của mỗi đoạn $[a_i - a_j]$ bằng tổng các $d_k$ tạo nên nó: $|a_i - a_j| = d_i + d_{i+1} + \ldots + d_{j-1}$. Rõ ràng, $d_k$ thuộc vào những đoạn mà đầu trái nằm ở một trong các điểm $a_1, \ldots, a_k$, còn đầu phải nằm ở một trong các điểm $a_{k+1}, \ldots, a_n$, tức là tổng cộng $d_k$ được tính vào tổng $k(n-k)$ lần. Do đó

$$s = \sum_{k=1}^{n-1} k(n-k)d_k.$$

Bây giờ các khẳng định cần chứng minh suy ra từ hai bất đẳng thức hoàn toàn đơn giản: với mọi $k=1, \ldots, n-1$

1) $k(n-k) \geqslant n-1 \iff kn-k^2-n+1 \geqslant 0 \iff (k-1)(n-k-1) \geqslant 0$;
2) $k(n-k) \leqslant \frac{n^2}{4} \iff n^2-4nk+4k^2 \geqslant 0 \iff (n-2k)^2 \geqslant 0$.

Dùng những ví dụ này chúng ta sẽ dùng những cái thu được, những cái thu được

$$\sum_{k=1}^{n-1} k(n-k)d_k \geqslant \sum_{k=1}^{n-1}(n-1)d_k = (n-1)d,$$

$$\sum_{k=1}^{n-1} k(n-k)d_k \leqslant \sum_{k=1}^{n-1}\frac{n^2}{4}d_k = \frac{n^2}{4}d.$$

Các lời giải đúng của bài toán này đã được gửi bởi M. Preger ở thành phố Tomsk, học sinh lớp mười I. Protasov ở thành phố Kiev, S. Pozdnyakov ở thành phố Vilnius và những độc giả khác.

Còn thú vị là выяснить, các đánh giá nêu trong điều kiện bài toán có phải là chính xác không, chẳng hạn có thể thay $n-1$ trong bất đẳng thức bên trái bằng những số lớn hơn không? Để thấy điều ngược lại, chỉ cần đưa ra một ví dụ trong đó bất đẳng thức trở thành đẳng thức (hơn nữa ở cả hai vế đều là các số dương). Một ví dụ như vậy dễ nghĩ ra, nếu đã hiểu lời chứng minh của chúng ta: cần sắp xếp

⟦folio 33⟧

các điểm $a_1, a_2, \dots, a_n$ sao cho mọi $d_k$, trừ cái đầu tiên — $d_1$, đều bằng không, tức là $a_1 < a_2 = a_3 = \dots = a_n$. Khi đó $s = (n-1)d_1 = (n-1)d$.

Về bất đẳng thức thứ hai $s \leqslant \frac{n^2}{4}d$, thì khi $n = 2m$ chẵn, trong đó cũng có thể đạt dấu bằng (chỉ cần lấy $a_1 = a_2 = \dots = a_m < a_{m+1} = \dots = a_{2m}$), còn khi $n = 2m+1$ lẻ, nó có thể được làm chính xác hơn đôi chút: không khó thấy rằng khi $n$ lẻ, lớn nhất trong các số $k(n-k)$ là $\frac{n-1}{2} \cdot \frac{n+1}{2} = \frac{n^2-1}{4}$ (hãy chứng minh điều này chặt chẽ!); dùng điều này thay cho bất đẳng thức 2), cũng như ở trên, có thể chứng minh bất đẳng thức mạnh hơn $s < \frac{n^2-1}{4}d$. Dấu bằng trong đó đạt được khi $a_1 = \dots = a_m < a_{m+1} = \dots = a_{2m+1}$.

M14. Trên một đa diện lồi màu trắng, một số mặt được sơn màu đen sao cho không có hai mặt đen nào có chung một cạnh. Chứng minh rằng nếu thỏa mãn ít nhất một trong các điều kiện sau:
a) số mặt đen lớn hơn một nửa;
b) diện tích các mặt đen lớn hơn một nửa diện tích bề mặt đa diện, thì không thể nội tiếp một quả cầu vào đa diện này.

Lời giải. Bắt đầu với bài 6). Giả sử có thể nội tiếp một quả cầu vào đa diện. Đánh dấu trên mỗi mặt điểm tiếp xúc với quả cầu và nối từ điểm đó các đoạn thẳng tới các đỉnh của mặt này. Khi đó mặt được chia thành các tam giác. Với mỗi cạnh của đa diện có hai tam giác như vậy kề với nó, nằm trên các mặt kề nhau. Chúng bằng nhau theo ba cạnh (vì hai tiếp tuyến kẻ từ một điểm đến quả cầu thì bằng nhau). Theo điều kiện, với mỗi cạnh có không quá một mặt đen kề với nó. Như vậy, với mỗi tam giác đen có một tam giác trắng bằng nó kề với nó*). Do đó, tổng diện tích các mặt đen không lớn hơn tổng diện tích các mặt trắng. Bài 6) đã được giải.

Hoàn toàn tương tự cũng giải được bài a), bài đã được nói đến trong bài viết “Các đa diện không thể nội tiếp” của E. M. Andreev (xem “Kvant” số 8, bài 9 ở cuối bài viết). Trong bài viết này, cả một loạt câu hỏi nảy sinh liên quan đến bài toán của chúng ta được xét đến: có tồn tại các đa diện thỏa những điều kiện tương tự hay không, còn có những “dấu hiệu không thể ngoại tiếp” nào khác, v.v. Đúng là, như có thể thấy từ tên bài viết, ở đó nói về việc liệu có thể nội tiếp đa diện này hay đa diện kia vào một mặt cầu hay không, còn trong bài toán của chúng ta — liệu có thể ngoại tiếp nó quanh một mặt cầu hay không. Tuy nhiên, hóa ra hai lý thuyết hoàn toàn tương tự nhau.

Chính xác hơn, với mỗi đa diện lồi nội tiếp có thể đặt tương ứng một đa diện ngoại tiếp sao cho khi đó với mỗi mặt, thì các mặt phẳng tương ứng với chúng sẽ cắt nhau tại một điểm — một đỉnh của đa diện mới, tương ứng với mặt của đa diện nội tiếp ban đầu. Nếu hai đỉnh của đa diện nội tiếp được nối bằng một cạnh, thì các mặt phẳng tiếp xúc tương ứng sẽ cắt nhau theo một cạnh của đa diện ngoại tiếp. Như vậy ta đã xây dựng một ánh xạ từ các đa diện nội tiếp vào tập các đa diện ngoại tiếp; dễ thấy rằng ánh xạ này phủ lên toàn bộ tập các đa diện ngoại tiếp và nó có ánh xạ ngược

*) Nhưng dĩ nhiên, với một tam giác trắng cũng có thể kề một tam giác trắng — điều quan trọng chỉ là các tam giác đen khác nhau tương ứng với các tam giác trắng khác nhau.

⟦folio 34⟧

(chúng tôi dùng thuật ngữ đã được nói đến trong bài của A. N. Kolmogorov “Hàm là gì” trên «Kvant» số 1),— nói cách khác, với mỗi đa diện ngoại tiếp có thể đối ứng một đa diện nội tiếp mà từ đó đa diện ngoại tiếp này được tạo ra theo cách đã nêu trên. Chỉ cần đánh dấu trên mỗi mặt điểm tiếp xúc — đỉnh của đa diện nội tiếp tương lai — và chứng minh rằng mọi điểm tiếp xúc của các mặt có chung một đỉnh đều nằm trong một mặt phẳng (hình 6). Cả hai ánh xạ này, liên kết tập hợp các đa diện nội tiếp và ngoại tiếp lồi, là một ví dụ đẹp về tình huống mà các nhà toán học thường gọi bằng từ “đối ngẫu” (từ này đã được E. M. Andreev nhắc đến thoáng qua trong bài viết của mình). Hãy suy nghĩ xem những đa diện ngoại tiếp nào sẽ đối ngẫu với các đa diện nội tiếp sau đây: hình lập phương, lăng trụ đều $n$ giác, hình chóp đều $n$ giác, hình chóp cụt đều, khối mười hai mặt đều.

Chúng tôi rất khuyên độc giả quay lại bài “Các đa diện không nội tiếp được” và, sử dụng tính đối ngẫu mà chúng tôi vừa nói đến, chuyển nội dung của nó sang các đa diện “không ngoại tiếp được”.

M15. Bảng vuông $n \times n$ được điền các số không âm sao cho tổng các số trong mỗi hàng và tổng các số trong mỗi cột đều bằng 1. Chứng minh rằng có thể chọn từ bảng $n$ số dương $x$, sao cho không có hai số nào nằm trong cùng một cột hay cùng một hàng.

Lời giải. Trước hết, nhận xét rằng nếu ta hoán vị các hàng (hoặc các cột) của bảng, thì điều đó không ảnh hưởng đến điều kiện bài toán cũng như điều cần chứng minh. Giả sử rằng bằng các hoán vị hàng và cột, ta đã gom được vào một góc vuông kích thước $m \times k$ chỉ các số không (hình 7). Ta sẽ chứng minh rằng $m + k$ luôn không lớn hơn $n$. Hãy tính tổng các số nằm trong phần được ký hiệu bằng chữ $C$ trên hình. Rõ ràng tổng các số trong phần $B$ bằng $m$ ($m$ cột, trong mỗi cột tổng bằng 1). Tương tự, tổng các số trong phần $A$ bằng $k$ ($k$ hàng). Vì tổng tất cả các số trong bảng bằng $n$, nên phần $C$ còn lại $n - m - k$. Số này không âm, vì theo điều kiện mọi số trong bảng đều không âm. Vậy, $n - m - k \ge 0$, tức là $m + k \le n$, như đã khẳng định.

Bây giờ ta có thể phát biểu lại bài toán như sau: trong bảng $n \times n$ có các số, và biết rằng không một hoán vị nào của các hàng và cột có thể đưa-

⟦folio 35⟧

Xét trong đó một góc gồm các số không có kích thước $m \times k$ sao cho $m + k > n$; hãy chứng minh rằng có thể chọn $n$ số khác không sao cho không có hai số nào trong số đó nằm cùng một cột hoặc cùng một hàng. (Bây giờ đối với chúng ta không còn quan trọng rằng các số là dương và tổng theo các hàng và các cột bằng 1. Những điều kiện này ta đã dùng rồi. Về sau ta chỉ phân biệt “số không” và “số khác không”.)

Nếu bạn đã đọc bài của M. I. Bashmakov “Ghép đôi và mạng vận tải” trong số 4 của tạp chí chúng ta, thì bạn sẽ dễ dàng nói rằng cách phát biểu mới của bài toán chúng ta chỉ là sự viết bằng ngôn ngữ “bảng” của định lý về việc mai mối. Thật vậy, hãy ghi vào các hàng của bảng $n \times n$ các chàng trai, còn vào các cột — các cô gái (mỗi bên có $n$ người). Tại giao điểm của hàng thứ $s$ và cột thứ $t$, ta đặt một “khác-không” (dấu sao), nếu chàng trai thứ $s$ quen cô gái thứ $t$, và một “số không”, nếu không quen. Ta sẽ thu được một bảng (như các nhà toán học nói, một “ma trận”) các mối quen biết.

Hãy lấy một nhóm tùy ý gồm $k$ chàng trai. Đặt các hàng tương ứng với họ lên đầu. Nếu không chàng trai nào trong số này quen một cô gái nào đó, thì trong cột tương ứng ở $k$ hàng đầu có các số không. Nếu ta chuyển tất cả các cột tương ứng với những cô gái như vậy xuống cuối (giả sử số lượng của họ bằng $m$), thì ta sẽ được một góc gồm các số không kích thước $m \times k$ (hình 8). Trong mỗi cột đầu tiên $m - n$ có ít nhất một “không-không” ở các hàng đầu, vì cô gái tương ứng quen một chàng trai khác trong số $k$ chàng trai mà ta đã chọn. Vì $m + k \leq n$, nên $m - n \geq k$, tức là những cô gái như vậy không ít hơn $k$. Ta thấy rằng dữ kiện của bài toán hoàn toàn trùng với dữ kiện của “định lý về mai mối”. Việc chọn $n$ cô dâu cho tất cả các chàng trai chính là việc chọn $n$ “không-không” nằm ở các hàng và các cột khác nhau.

Bây giờ bạn có thể đọc chứng minh đơn giản (theo quy nạp) của “định lý về mai mối”, chứng minh này cũng cho lời giải hoàn chỉnh của bài toán. Dĩ nhiên, hoàn toàn không bắt buộc phải quy bài toán về định lý này. Có thể tiến hành lập luận quy nạp ngay lập tức — bằng cách hoán vị các hàng và các cột (chẳng hạn, độc giả Đ. Grigoriev ở thành phố Leningrad đã làm như vậy). Khi đó thu được một chứng minh mới của “định lý về mai mối”*).

*) Nhưng dĩ nhiên, nếu chỉ đơn giản gạch bỏ cột cuối và hàng cuối trong bảng thỏa mãn các điều kiện của bài toán, ta có thể thu được một bảng không còn thỏa mãn điều kiện này nữa,— không thể tiến hành quy nạp một cách “thô” như vậy.

⟦folio 36⟧

F18. Nếu nhìn ánh sáng qua hai cái lược có tần số răng khác nhau, chồng lên nhau, thì các vùng sáng sẽ xen kẽ với các vùng tối. Các vùng này sẽ dịch chuyển với tốc độ nào, nếu dịch chuyển một cái lược so với cái kia với tốc độ 1 cm/giây? Cái lược đứng yên có 5 răng trên 1 xentimét, cái đang chuyển động có —6.

Lời giải. Hãy làm trùng một vài răng của các lược (hình 9). Khi đó các răng kế tiếp sẽ cách nhau $1/5$ cm—$1/6$ cm = $1/30$ cm. Bây giờ hãy dịch lược đi khoảng này. Khi đó hình các vạch sáng và tối sẽ dịch đi $1/5$ cm—khoảng cách giữa các răng của lược cố định. Nếu dịch lược đi 1 cm, thì hình các vạch sáng và tối sẽ dịch đi $1/5$ cm·30 = 6 cm.

Điều đó có nghĩa là khi lược có tần số răng lớn hơn chuyển động với vận tốc 1 cm/giây, các vạch sáng và tối chuyển động với vận tốc $v = 6$ cm/giây theo cùng chiều mà lược động dịch chuyển.

Hình các vạch sáng và tối xen kẽ, chuyển động với vận tốc không đổi, là một mô hình rất tiện lợi cho sự truyền của sóng có bất kỳ bản chất vật lý nào. Nếu quan sát các vạch chuyển động qua một khe (hình 10), thì khe sẽ lần lượt bị các vạch vàng, rồi các vạch đen che kín:

⟦folio 37⟧

ta sẽ thấy dao động. Màu đen và màu vàng của các vạch tương ứng với hai pha đối lập của dao động (hình 11). Bước sóng bằng tổng bề rộng của một vạch sáng và một vạch tối. Đếm số vạch đen hoặc vàng đi qua khe trong một giây, có thể xác định tần số dao động và chu kỳ của chúng.

Mô hình đơn giản này cho phép tìm hiểu nhiều hiện tượng và quá trình vật lý trong các thí nghiệm thú vị.

Bằng các vạch đen-vàng có thể mô hình hóa không chỉ sóng thẳng mà cả mọi loại sóng khác, chẳng hạn sóng tròn (hình 12). Chuyển động của các sóng tròn như vậy có thể biểu diễn, chẳng hạn, bằng một xoắn ốc Archimedes đen-vàng (hình 13). Khi xoay xoắn ốc, qua khe sẽ thấy các sóng chạy về tâm hoặc từ tâm ra, tùy theo chiều quay của xoắn ốc.

Nếu các vạch không chuyển động, ta sẽ nhận được hình sóng đứng yên. Những hình như vậy được gọi là raster. Không được nhầm sóng-raster đứng yên với sóng dừng. Mô hình của sóng dừng là các vạch đen-vàng xen kẽ, tuần hoàn đổi màu sang màu đối lập.

Khi vài sóng hình sin chồng lên nhau, xuất hiện những sóng mới, không còn là sóng hình sin. Chúng được gọi là sóng nhóm. Sóng nhóm khác các sóng hình sin được cộng cả về độ dài, vận tốc truyền và các tham số khác. Những sóng nhóm đơn giản nhất là sóng nhịp. Chúng xuất hiện khi cộng hai sóng có bước sóng không bằng nhau nhưng gần nhau.

Để dựng mô hình sóng nhóm, cần chồng hai hệ vạch lên nhau. Nếu các hệ này giống nhau, có thể chồng chúng sao cho các vạch của hệ này trùng với các vạch của hệ kia. Những sóng như vậy được gọi là kết hợp. Nếu các hệ vạch hơi khác nhau về khoảng cách giữa các vạch, ta sẽ nhận được hình nhịp (hình 14). Hình tương tự đã xuất hiện trong các thí nghiệm của bạn với lược.

Không khó tìm bước sóng nhịp do các sóng có bước sóng $\lambda_1$ và $\lambda_2$ ($\lambda_1 > \lambda_2$) tạo ra. Nếu hai vạch đen trùng nhau, thì vạch thứ n của hệ vạch có bước sóng $\lambda_1$ và vạch thứ $(n+1)$ của hệ vạch có bước sóng $\lambda_2$. Điều đó có nghĩa là bước sóng nhịp bằng

$$L = n\lambda_1 = (n+1)\lambda_2.$$

⟦folio 38⟧

Từ đẳng thức $n\lambda_1 = (n+1)\lambda_2$ ta tìm được rằng $n = \frac{\lambda_2}{\lambda_1 - \lambda_2}$.

Vì vậy $L = \frac{\lambda_1\lambda_2}{\lambda_1 - \lambda_2}$.

Các sóng chồng lên nhau càng ít khác biệt, thì độ dài của các sóng nhóm càng lớn. Điều này được dùng khi thay đổi bước sóng của các dao động cao tần. Để thay đổi, người ta chọn bước sóng thứ hai sao cho khi cộng các sóng lại thu được các phách có bước sóng lớn. Những phách như vậy dễ quan sát và thay đổi bằng máy hiện sóng. Biết độ dài phách và bước sóng của một trong các dao động, không khó xác định bước sóng của dao động đang khảo sát.

Các sóng phách được chỉ ra trên hình 14 là các sóng đứng. Nếu cho một hoặc cả hai hệ sóng chuyển động, thì các sóng nhóm cũng sẽ chuyển động. Vận tốc $v$ của các sóng nhóm có thể tìm được giống như cách ta tìm vận tốc chuyển động của các sóng nhóm thu được khi chồng các chiếc lược lên nhau. Nó bằng

$$v = \frac{\lambda_1 v_2 - \lambda_2 v_1}{\lambda_1 - \lambda_2},$$

trong đó $v_1$ là vận tốc của các sóng có bước sóng $\lambda_1$, còn $v_2$ là vận tốc của các sóng có bước sóng $\lambda_2$.

Công thức này là sự khái quát của công thức mà chúng ta đã suy ra cho các chiếc lược.

Bằng cách này, bài toán đã được giải bởi Vyacheslav Mileshin (Beltsy, Moldavia) và Aleksadr Karpenko (Lisichansk, tỉnh Voroshilovgrad). Bằng cách tương tự, bài toán được giải bởi Lyutsman Petraskik (Lida, tỉnh Grodno) và Sergey Yushman (Vilyany, Latvia). Một số độc giả, giải bài toán đúng, đã tính sai khoảng cách giữa các răng lược. Nếu một chiếc lược có $n$ răng trên 1 cm, thì trên 1 cm cũng có $n$ khoảng giữa các răng (chứ không phải $n-1$). Trong hai răng ở hai đầu của một xentimét, răng thứ nhất thuộc xentimét này, còn răng cuối cùng thuộc xentimét tiếp theo.

F19. Hình dạng của các bình thông nhau được chỉ ra trên hình 15. Nước sẽ chảy về đâu qua ống nối các bình, nếu đun nóng nước trong một trong các bình?

Lời giải. Bất kể bình nào được đun nóng, nước sẽ chảy sang phải. Giả sử chất lỏng trong bình bên phải được đun nóng. Khi đó nó sẽ nở ra và chiếm thể tích lớn hơn. Nếu bình là hình trụ (hình 16), thì áp suất của chất lỏng lên đáy sẽ không thay đổi: sự giảm mật độ của nước sẽ được bù chính xác bởi sự tăng chiều cao cột chất lỏng. Điều này suy ra từ việc lực ép lên đáy của bình hình trụ, một mặt, bằng trọng lực tác dụng lên lượng nước chứa trong bình, mặt khác, bằng áp suất của chất lỏng lên đáy nhân với diện tích đáy: $P = pS$. Vì cả trọng lực lẫn diện tích đáy đều không thay đổi khi đun nóng chất lỏng, nên áp suất lên đáy bình hình trụ cũng không thay đổi.

⟦folio 39⟧

Trong bình hình nón loe, khi mật độ chất lỏng giảm như vậy, chiều cao cột chất lỏng tăng ít hơn so với trong bình hình trụ. Điều này xảy ra vì hai nguyên nhân: thứ nhất, lượng chất lỏng nở ra ít hơn, nghĩa là thể tích của nó thay đổi ít hơn; thứ hai, khi nở ra nước phải lấp đầy thể tích được gạch trên hình. Vì vậy áp suất lên đáy bình giảm khi đun nóng chất lỏng. Vì khi chất lỏng cân bằng trong ống nối các bình, áp suất ở đầu ống trong bình bên trái phải bằng áp suất ở đầu ống trong bình bên phải, nên chất lỏng sẽ chảy từ bình bên trái sang bình bên phải.

Xét tương tự sự đun nóng và sự nở ra của chất lỏng trong bình bên trái, ta sẽ thấy rằng khi đun nóng bình bên trái, áp suất lên đáy của nó tăng. Điều đó có nghĩa là trong trường hợp này chất lỏng cũng sẽ chảy từ bình bên trái sang bình bên phải.

Bài toán này được giải đúng bởi Vladimir Metlitsky (Angarsk, tỉnh Irkutsk) và Aleksandr Karpenko. Học sinh lớp 8 Efim Kaplun (Vinnitsa, Ukraina) đã chú ý rằng trong bình được đun nóng, nước bay hơi mạnh hơn so với bình có nhiệt độ không thay đổi. Điều này phải ảnh hưởng đến sự chảy nước. Tuy nhiên, nếu nhiệt độ các bình không cao, thì có thể bỏ qua hiệu ứng này.

Ф20. Song song với trục của một hình trụ bán kính $R$, ở khoảng cách $\frac{R}{2}$ từ tâm của nó, khoan một lỗ tròn. Bán kính lỗ bằng $\frac{R}{2}$. Hình trụ nằm trên một tấm ván, được từ từ nâng lên ở một đầu (hình 17). Tìm góc nghiêng tới hạn của tấm ván mà tại đó hình trụ vẫn còn cân bằng. Hệ số ma sát giữa hình trụ và tấm ván bằng 0,2.

⟦folio 41⟧

hình trụ sẽ mất ổn định khi góc nghiêng của tấm ván bằng

$$\alpha = \alpha_1 = \arcsin \frac{1}{6}.$$

Bài toán này được giải đúng bởi Lyutsman Petrasik, Vladimir Metlitsky, Mikhail Kuznetsov (làng Golchevskaya, tỉnh Vologda), Vladimir Korneev (Moskva), Aleksandr Karpenko, Aleksei Efimov (Moskva) và những người khác.

Ф21. Trục rôto của hai động cơ điện một chiều giống nhau được nối cứng với nhau. Nếu nối vào cuộn dây rôto các nguồn giống nhau có suất điện động E, thì vận tốc góc quay không tải của rôto bằng $\omega_0$; nếu hãm các động cơ để chúng không quay, thì dòng điện $I_0$ chạy qua các cuộn dây rôto. Một trong các nguồn điện được chuyển mạch sao cho mômen quay của các rôto ngược chiều nhau. Cần tác dụng mômen ngoài nào lên trục rôto để chúng quay với vận tốc góc cho trước $\omega$? Ma sát trong các ổ trục động cơ nhỏ; từ trường stato được tạo bởi nam châm vĩnh cửu.

Lời giải. Khi rôto bị hãm hoàn toàn, dòng điện $I_0 = \frac{E}{R}$ chạy qua cuộn dây của nó. Điều đó có nghĩa là điện trở cuộn dây rôto $R = \frac{E}{I_0}$.

Khi phần ứng của động cơ điện quay, trong cuộn dây của nó xuất hiện suất điện động cảm ứng $E_n$, tỉ lệ với vận tốc góc quay của phần ứng:
$$E_n = k\omega (k - \text{hệ số tỉ lệ}).$$
Viết định luật bảo toàn năng lượng cho động cơ điện:
$$EIt = I^2Rt + Nt.$$
Hoặc, rút gọn theo thời gian làm việc $t$ của động cơ, ta được
$$EI = I^2R + N;$$
ở đây $N$ — công suất mà động cơ điện nhận từ mạng điện, $I^2R$ — tổn hao nhiệt trong cuộn dây phần ứng, $N$ — công suất truyền cho tải, $R$ — điện trở của cuộn dây phần ứng và $I$ — dòng điện trong cuộn dây.

Từ phương trình này suy ra rằng khi không có tải ($N = 0$), dòng điện qua cuộn dây phần ứng bằng không. Nhưng theo định luật Ôm, dòng điện đi qua cuộn dây phải bằng $I = \frac{E - E_n}{R}$. Điều này có nghĩa là khi không có tải, suất điện động cảm ứng xuất hiện trong cuộn dây phần ứng bằng suất điện động của nguồn: $E = E_n$.

Sau khi chuyển mạch một trong các nguồn, trong các cuộn dây phần ứng sẽ cảm ứng suất điện động $E'_n = k\omega = E_n \frac{\omega}{\omega_0} = E \frac{\omega}{\omega_0}$. Khi đó trong các cuộn dây sẽ có các dòng điện
$$I_1 = \frac{E - E'_n}{R} = \frac{\left(E - E \frac{\omega}{\omega_0}\right)}{E/I_0} = I_0 \left(1 - \frac{\omega}{\omega_0}\right),$$
$$I_2 = \frac{E + E'_n}{R} = I_0 \left(1 + \frac{\omega}{\omega_0}\right).$$

Hơn nữa, cả công của các nguồn lẫn công của ngoại lực đều dùng để đốt nóng các cuộn dây. Vì vậy $EI_1 + EI_2 + N' = I_1^2R + I_2^2R$.

Vì $N' = F \cdot v = F \cdot r\omega = M\omega$ (F là ngoại lực tác dụng lên phần ứng, M là mômen của nó đối với trục và v = $\omega r$ là vận tốc góc của các điểm trên bề mặt trục phần ứng), nên thay $N'$, $I_1$, $I_2$ và R bằng các biểu thức của chúng theo M, $\omega$, $\omega_0$ và E, ta được
$$M\omega + EI_0 \left[ \left(1 + \frac{\omega}{\omega_0}\right) + \left(1 - \frac{\omega}{\omega_0}\right) \right] = I_0^2 \frac{E}{I_0} \left[ \left(1 + \frac{\omega}{\omega_0}\right)^2 + \left(1 - \frac{\omega}{\omega_0}\right)^2 \right],$$

⟦folio 42⟧

suy ra $M\omega + 2EI_0 =$
$= EI_0 \left[ 2 + 2 \left( \frac{\omega}{\omega_0} \right)^2 \right]$
và $M = \frac{2EI_0\omega}{\omega_0^2}$.

B22. Hai người thợ rèn đang rèn một cục sắt. Lúc đầu họ đặt nó lên đe và lần lượt dùng búa đập, sau đó treo nó lên trần và đồng thời đập từ hai phía. Lực đập của mỗi người thợ rèn là như nhau trong cả hai trường hợp. Trong trường hợp nào cục sắt nóng lên nhiều hơn sau một nhát đập?

Lời giải. Trong trường hợp thứ hai. Rõ ràng rằng cả khi một người thợ rèn đập vào cục sắt nằm trên đe, lẫn khi các người thợ rèn đập vào cục sắt treo, đều thực hiện cùng một công: trong trường hợp thứ nhất, vai trò của người thợ rèn thứ hai đập vào cục sắt được cái đe đảm nhận. Công này dùng để nung nóng cục sắt và, ngoài ra, để thực hiện công cơ học khi cục sắt nở ra. Khi sắt nằm trên đe, trọng tâm của nó nâng lên khi nở ra — công được thực hiện chống lại lực trọng trường. Còn khi cục sắt được treo, trọng tâm của nó hạ xuống khi nở ra. Điều đó có nghĩa là trong trường hợp thứ hai, khi không chỉ công do các người thợ rèn thực hiện mà cả một phần thế năng của cục sắt cũng chuyển thành nhiệt (công do sắt thực hiện khi nở ra là âm), nó sẽ nóng lên nhiều hơn sau một nhát đập so với trường hợp thứ nhất.

F23. Trên mặt phẳng ngang có hai ống thành mỏng giống hệt nhau, mỗi ống có khối lượng $m$. Các trục của chúng song song, còn bán kính bằng $R$. Ban đầu một ống đứng yên, còn ống kia lăn không trượt theo hướng về phía ống thứ nhất cho đến khi va chạm. Vận tốc chuyển động tịnh tiến của ống bằng $v$. Các vận tốc chuyển động tịnh tiến và các vận tốc góc quay của các ống phụ thuộc vào thời gian như thế nào (hãy vẽ đồ thị)?

Hệ số ma sát trượt của các ống với mặt phẳng ngang bằng $k$, ma sát giữa các ống khi va chạm là không đáng kể, va chạm hoàn toàn đàn hồi.

Lời giải. Vì ma sát giữa các ống là không đáng kể, có thể coi rằng khi va chạm, sự quay của một ống không truyền sang ống kia. Vì vậy, khi xét sự va chạm của các ống, ta có thể không tính đến sự quay của ống thứ nhất (ban đầu chuyển động).

Viết các định luật bảo toàn năng lượng và động lượng cho va chạm của các ống:

$$mv_0 = mv_1 + mv_2, \frac{mv_0^2}{2} = \frac{mv_1^2}{2} + \frac{mv_2^2}{2}$$

($v_1$ và $v_2$ là các vận tốc chuyển động tịnh tiến tương ứng của ống thứ nhất và thứ hai sau va chạm).

Giải đồng thời các phương trình này, ta được $v_1 = 0$ và $v_2 = v_0$, tức là khi va chạm các ống trao đổi các vận tốc chuyển động tịnh tiến — hoàn toàn giống như khi va chạm của hai quả cầu giống nhau.

Bây giờ hãy xét điều gì xảy ra với ống thứ nhất, ban đầu chuyển động, sau va chạm. Trong hệ tọa độ gắn với trục của ống lăn không trượt trên mặt phẳng với vận tốc $v_0$, vận tốc của điểm tiếp xúc với mặt phẳng bằng — $v_0$. Điều này có nghĩa là ống như vậy quay quanh trục của nó sao cho vận tốc tuyến tính của sự quay

⟦folio 43⟧

của các điểm trên bề mặt nó bằng về độ lớn vận tốc chuyển động tịnh tiến của trục ống. Vì vậy ống thứ nhất sau va chạm quay quanh trục của nó với vận tốc góc $\omega = \frac{v_0}{R}$.

Lực ma sát $F_{\text{тр}} = kmg$ (hình 20), tác dụng lên ống này, làm chậm sự quay của nó và đồng thời truyền cho nó gia tốc $a = \frac{F_{\text{тр}}}{m} = kg$ theo hướng chuyển động ban đầu của ống. Đến thời điểm $t$, ống này sẽ có vận tốc chuyển động tịnh tiến $u'_1 = at = kgt$ và sẽ quay quanh trục với vận tốc góc $\omega_1 = \frac{v_0 - kgt}{R}$. Vận tốc chuyển động tịnh tiến của ống tăng lên, còn vận tốc quay của ống giảm tỉ lệ với thời gian. Đến thời điểm $t_0$, khi vận tốc chuyển động tịnh tiến của trục ống trở nên bằng vận tốc dài của sự quay của ống quanh trục, sự trượt của ống đối với mặt phẳng sẽ chấm dứt, và sau đó cả vận tốc quay của ống $\omega'_1$, lẫn vận tốc chuyển động tịnh tiến của trục ống $u'_1$ đều không còn thay đổi. Từ điều kiện $kgt_0 = v_0 - kgt_0$ ta tìm được $t_0 = \frac{v_0}{2kg}$. Vào thời điểm này

$$u_1 = \frac{v_0}{2} \text{ và } \omega_1 = \frac{v_0}{2}.$$

Xét tương tự chuyển động của ống thứ hai, ta thấy rằng lực ma sát tác dụng lên nó làm giảm vận tốc chuyển động tịnh tiến của nó, $u_2 = v_0 - kgt$, và làm tăng vận tốc góc quay $\omega_2 = \frac{kgt}{R}$.

Đến thời điểm $= \frac{v_0}{2kg}$ sự trượt của ống so với mặt phẳng sẽ chấm dứt. Vào thời điểm này, ống sẽ có vận tốc chuyển động tịnh tiến không đổi về sau $u_2 = \frac{v_0}{2}$ và vận tốc góc quay quanh trục $\omega_2 = \frac{v_0}{2R}$.

Các đồ thị biểu diễn sự phụ thuộc của vận tốc chuyển động tịnh tiến của các ống và vận tốc góc quay của chúng vào thời gian được trình bày trên hình 21.

Lời giải đúng của bài toán này do Mikhail Kuznetsov và Sergei Yushmanov gửi tới.
