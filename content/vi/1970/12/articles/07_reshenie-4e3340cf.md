---
id: 1970-12-reshenie-4e3340cf
issue: kvant_1970_12
year: 1970
number: "12"
title: Lời giải các bài toán M16—M20; F24—F28
rubric: zadachnik-kvanta
rubric_sub: Задачник «Кванта»
page_first: 36
page_last: 46
page_labels: 34, 36, 37, 38, 42, 43, 44
tag: Y83H
lang: vi
source: kvant_digital
extraction: vision
content_sha256: 64ed81156ef927cde299b43e61fe44a6845b764f562c606f9e4a3cfc93842846
prompt_sha256: 3ec6b8aabd9b98576af76503cd8a2902b9f5d18e01ee867dfb1228f59c6d52d8
translated_from: content/ru/1970/12/articles/07_reshenie-4e3340cf.md
source_content_sha256: c57bf6ba28335510d96377239002b96cac0c15fc3f55a499149028c68ba19b2a
translation_model: gpt-5.6-terra
translation_run: vi-codex-2026-10-31
---

⟦folio 34⟧

LỜI GIẢI

M16. Chứng minh rằng đa thức $p(x)$ có hệ số nguyên, nhận giá trị 1 tại ba giá trị nguyên khác nhau của $x$, không thể có một nghiệm nguyên nào.

Lời giải и.e. Nhận xét rằng với mọi đa thức $p(x)$ có hệ số nguyên và với mọi hai số nguyên $a$ và $b$, hiệu $p(b) - p(a)$ chia hết cho $b - a$, vì với mọi số tự nhiên $m$, hiệu $b^m - a^m$ chia hết cho $b - a$:

$$b^m - a^m = (b - a) (b^{m-1} + b^{m-2}a + b^{m-3}a^2 + \ldots + ba^{m-2} + a^{m-1}).$$

Nếu tồn tại bốn số nguyên $c_1, c_2, c_3$ và $a$ sao cho $p(c_1) = p(c_2) = p(c_3) = 1$ và $p(a) = 0$, thì

$$p(c_1) - p(a) = p(c_2) - p(a) = p(c_3) - p(a) = 1,$$

và vì thế mỗi số trong các số $c_1 - a, c_2 - a, c_3 - a$ chỉ có thể bằng 1 hoặc —1, do đó tất cả các số này không thể khác nhau. Lời giải như vậy do A. Veselov ở làng Volchkovo, tỉnh Kalinin, I. Suprunenko ở Minsk và các bạn đọc khác gửi đến.

Phần đầu của lời giải có thể trình bày hơi khác đi, nếu biết phép chia đa thức *). Chia “góc” đa thức $p(x)$ cho $x - a$, trong đó $a$ là một nghiệm nguyên của đa thức. Khi đó $p(x) = (x - a)q(x)$, trong đó $q(x)$ cũng là một đa thức có hệ số nguyên. Thật vậy, vì hệ số của đa thức $x - a$ bằng 1, nên khi chia đa thức cho $x - a$ theo phép chia góc, tất cả các hệ số xuất hiện trong đa thức này sẽ nhận được từ những phép toán cộng, trừ và nhân trên các hệ số đã có, tức là cũng sẽ là số nguyên. Số dư bằng không, vì $a$ là nghiệm của đa thức: $p(a) = 0$. Như vậy, $(a - c_1)q(c_1) = (a - c_2)q(c_2) = (a - c_3)q(c_3) = 1$, và tiếp theo lập luận hoàn toàn giống như trong lời giải thứ nhất.

M17. Một người nông dân, đến chỗ rẽ của hai con đường tạo với nhau một góc $60^\circ$, hỏi: “Đi đến làng NN thế nào?” Người ta đáp: “Đi theo con đường bên trái đến làng N — từ đây đến đó tám verst, — ở đó anh sẽ thấy một con đường lớn, thẳng, rẽ sang phải vuông góc — đó chính là đường đến NN. Anh cũng có thể đi đường khác: bây giờ theo con đường bên phải; khi ra đến đường sắt, nghĩa là anh đã đi được nửa đường; ở đó rẽ trái và đi thẳng theo tà vẹt đến tận NN.” — “Thế đường nào ngắn hơn?” — “Như nhau cả, đi cách nào cũng vậy, không có gì khác.” Và người nông dân đi theo con đường bên phải.

Ông ta sẽ phải đi bao nhiêu verst để đến NN? Hơn mười hay ít hơn? Còn nếu đi thẳng từ chỗ rẽ đến NN? (Mọi con đường đều được coi là thẳng.)

Lời giải. Gọi $A$ là ngã rẽ, $B$ là làng $N$, $C$ là làng NN, $D$ là điểm nơi con đường bên phải đi ra đường sắt. Theo giả thiết (các khoảng cách được đo bằng versta) $AB = 8$, $\angle A = 60^\circ$, $AD = DC$, $\angle B = 90^\circ$, $AB + BC = 2AD$. Đặt $AD = 2x$, $DH \perp AB$ và

*) Xem bài «Rút gọn phân thức đại số» của A. N. Vilenkin («Kvant» số 11).

⟦folio none⟧

DK⊥BC (hình 1). Khi đó AH = x, KD = BH = 8 - x, AB + BC = 2AD = 4x, BC = 4x - 8, BK = DH = x√3, KC = |BC - BK| = |4x - 8 - x√3| và để thỏa mãn mọi điều kiện của bài toán*) cần và đủ có đẳng thức CK² + KD² = AD² hoặc (4x - 8 - x√3)² + (8 - x)² = 4x²,

trong đó 8 - x > 0 và 4x - 8 > 0, tức là 2 < x < 8. Sau khi biến đổi, ta được (2 - √3)x² - 2(5 - √3)x + 16 = 0.

Ký hiệu tam thức ở vế trái là f(x). Không khó kiểm tra rằng điều kiện 0 < x < 8 chỉ được nghiệm nhỏ hơn x₀ của phương trình f(x) = 0 thỏa mãn (hình 2). Nó có thể viết dưới dạng

x₀ = (5 - √3 - √6√3 - 4) / (2 - √3) = 7 + 3√3 - √44 + 26√3.

Người nông dân sẽ phải đi quãng đường 4x₀. Việc xác định số này lớn hơn hay nhỏ hơn 10 dễ hơn nếu làm trực tiếp từ phương trình. Vì f(5/2) = 1/4(14 - 5√3) > 0, rõ ràng x₀ > 5/2, tức là 4x₀ > 10. Ta sẽ chứng minh rằng khoảng cách AC đi thẳng nhỏ hơn 10. Thật vậy, bất đẳng thức √8² + (4x₀ - 8)² < 10 khi 2 < x₀ < 8 tương đương với các bất đẳng thức: (4x₀ - 8)² < 36, 4x₀ - 8 < 6, x₀ < 7/2. Cũng như trên, ta thấy rằng f(7/2) = 1/4(22 - 21√3) < 0, suy ra x₀ < 7/2, và do đó AC < 10.

Lời giải bài toán này được M. Prezer từ Tomsk, A. Mikhailov từ Ekibastuz và các bạn đọc khác gửi cho chúng tôi.

S. Berkolayko (tỉnh Belgorod) đã tìm được một chứng minh ngắn gọn rằng AB + BC > 10. Theo ký hiệu của chúng tôi, nó có dạng như sau:

*) Thực ra, dễ chứng minh rằng chân đường vuông góc K nằm ngoài đoạn BC (đúng như hình vẽ), nhưng điều này không được dùng trong lời giải của chúng tôi.

⟦folio 36⟧

theo định lý cosin từ tam giác ABD
$$BD^2 = 4x_0^2 + 64 - 16x_0;$$
mặt khác, bất đẳng thức tam giác cho
$$BD < BC + CD = 6x_0 - 8,$$
suy ra
$$4x^2 + 64 - 16x < (6x - 8)^2, 2x^2 - 5x > 0,$$
và với $2 < x_0 < 8$ ta được $x_0 > \frac{5}{2}$. Giá trị chính xác hơn của khoảng cách $AB + BC$, theo khẳng định của tác giả bức thư này, là: 11,044 verst.

Một số độc giả đã hiểu sai điều kiện của bài toán và cho rằng $\angle D = 90^\circ$, tức là tam giác ADC cân và vuông. Điều đó, dĩ nhiên, không đúng.

M18. a) Chứng minh rằng với mọi điểm $M$ trên đường tròn ngoại tiếp tam giác đều ABC, một trong ba đoạn thẳng MA, MB, MC bằng tổng hai đoạn còn lại.
6) Ba đường tròn bằng nhau $\gamma_1, \gamma_2, \gamma_3$ đôi một tiếp xúc nhau, và có một đường tròn $\gamma$ ngoại tiếp chúng, tiếp xúc với cả ba đường tròn: $\gamma_1, \gamma_2$ và $\gamma_3$. Chứng minh rằng với mọi điểm $M$ trên đường tròn $\gamma$, tiếp tuyến kẻ từ điểm $M$ đến một trong ba đường tròn $\gamma_1, \gamma_2, \gamma_3$ bằng tổng các tiếp tuyến kẻ từ điểm $M$ đến hai đường tròn còn lại.

Lời giải a) Giả sử điểm $M$ nằm trên cung $AB$ của đường tròn ngoại tiếp. Quay tam giác AMB quanh điểm $A$ một góc $60^\circ$ sao cho nó chiếm vị trí AKC (hình 3). Vì các góc MBA và MCA bằng nhau (chúng chắn cùng một cung AM), điểm $K$ nằm trên đoạn MC. Vì AM = AK và $\angle MAK = 60^\circ$ (theo cách dựng), tam giác AMK đều, do đó MK = AM. Vậy,
$$MA + MB = MK + KC = MC.$$

Một lời giải khác nhận được ngay từ định lý Ptolemy, theo đó trong mọi tứ giác nội tiếp, tích các đường chéo bằng tổng các tích của các cạnh đối diện: nếu trong đẳng thức $MC \times AB = MA \cdot BC + MB \cdot AC$ thay $BC$ và $AC$ bằng $AB$, ta được $MC \times AB = (MA + MB) AB$, suy ra $MC = MA + MB$.

Nhiều độc giả của chúng tôi đã giải bài toán này. A. Braverman từ Perm, A. Veselov từ tỉnh Kalinin, V. Metlitsky từ Angarsk, N. Mirolyubova từ Aktyubinsk, O. Khudaverdyan từ Evrev đã gửi đến thậm chí vài lời giải.

6) Chứng minh một sự kiện tổng quát hơn. Giả sử tâm của ba đường tròn bán kính $r$ là các đỉnh của tam giác đều $C_0C_1C_2$ và $O$ là tâm đường tròn ngoại tiếp nó bán kính $a$. Khi đó với mọi điểm $M$

⟦folio 37⟧

của đường tròn bán kính $R = a + r$ tâm $O$, tiếp tuyến kẻ từ điểm $M$ đến một trong hai đường tròn bán kính $r$ bằng tổng các tiếp tuyến kẻ từ điểm $M$ đến hai đường tròn còn lại. Nhận xét rằng khi $r = 0$ ta được kết quả của bài a).

Giả sử bán kính $OM$ tạo với các bán kính $OC_k$ ($k = 0, 1, 2$) các góc $\alpha_k = \alpha_0 + k \cdot 120^\circ$ (hình 4); khi đó $MC_k^2 = R^2 + a^2 - 2Ra \cos \alpha_k^*$), còn bình phương tiếp tuyến kẻ từ điểm $M$ đến đường tròn tương ứng bằng $MC_k^2 - r^2 = R^2 + a^2 - 2Ra \cos \alpha_k - (R - a)^2 = 2Ra (1 - \cos \alpha_k)$.

Do đó các tiếp tuyến bằng $2\sqrt{Ra} \sin \frac{\alpha_k}{2} \left( \sin \frac{\alpha_k}{2} \geq 0, \text{ vì } 0 \leq \alpha_k < 2\pi \right)$. Còn lại cần kiểm tra đẳng thức $\sin \frac{\alpha_0}{2} + \sin \frac{\alpha_2}{2} = \sin \frac{\alpha_1}{2}$. Điều này đơn giản: $\sin \frac{\alpha_0}{2} + \sin \frac{\alpha_2}{2} = 2 \cos 60^\circ \cdot \sin \frac{\alpha_0 + \alpha_2}{4} = \sin \frac{\alpha_1}{2}$.

M. Preezer đã gửi một lời giải bài toán này bằng hình học giải tích. A. Braverman đã gửi cho chúng tôi một chứng minh thú vị (bằng định lý Ptolemy) của sự tổng quát hóa sau đây của bài toán a): giả sử $M$ là một điểm trên cung $A_1A_{2n+1}$ của đường tròn ngoại tiếp đa giác đều ($2n + 1$) cạnh $A_1A_2A_3 \dots A_{2n}A_{2n+1}$; khi đó

$$MA_1 + MA_3 + \dots + MA_{2n+1} = MA_2 + MA_4 + \dots + MA_{2n}.$$

(Lời giải gồm ở chỗ viết các đẳng thức Ptolemy cho các tứ giác $MA_1A_2A_3, MA_2A_3A_4, \dots, MA_{2n-1}A_{2n}A_{2n+1}, MA_{2n+1}A_{2n}A_1, MA_{2n+1}A_2A_1$, trong đó mọi hạng chứa $MA_{2k}$ được chuyển sang vế trái của đẳng thức, còn mọi hạng chứa $MA_{2k+1}$ — sang vế phải, rồi cộng tất cả các đẳng thức lại.) Hãy suy nghĩ cách chứng minh mệnh đề này và sự tổng quát hóa tương tự của bài 6) bằng các hàm lượng giác.

M19. Trong một dãy vô hạn các ô thần kinh, mỗi ô có thể ở một trong hai trạng thái: “nghỉ” và “kích thích”. Nếu tại một thời điểm nào đó một ô bị kích thích, thì nó gửi một tín hiệu, sau một đơn vị thời gian (chẳng hạn, sau một mili giây) sẽ đến hai ô kề với nó. Mỗi ô bị kích thích khi và chỉ khi nó nhận được tín hiệu từ một trong các ô kề; nếu tín hiệu đến đồng thời từ hai phía thì chúng triệt tiêu nhau, và ô không bị kích thích.

Giả sử tại thời điểm ban đầu $t = 0$ chỉ có một ô bị kích thích. Sau 15 ms sẽ có bao nhiêu ô ở trạng thái kích thích? sau 65 ms? sau 1000 ms? nói chung sau $t$ ms?

Điều gì xảy ra nếu dãy không vô hạn mà chỉ gồm $N$ ô nối thành một vòng tròn — sự kích thích sẽ được duy trì vô hạn lâu hay sẽ tắt?

Lời giải. Chỉ cần theo dõi sự lan truyền của kích thích từ một ô đơn lẻ trong mười đến mười lăm nhịp đầu tiên (hình 5) để nhận thấy các quy luật sau.

1. Tại thời điểm $t = 2^k$, trong đó $k = 0, 1, 2, \dots$ chỉ có hai ô bị kích thích: $x = -2^k$ và $x = 2^k$.

2. Tại thời điểm $t = 2^k - 1$ có $2^k$ ô bị kích thích, từ $x = -2^k + 1$ đến $x = 2^k - 1$ với $x$ lẻ.

3. Giả sử $0 \leq t < 2^k$. khi đó tại thời điểm $2^k + t$ có số ô được kích thích nhiều gấp đúng hai lần so với tại thời điểm $t$.

Để chứng minh các quy luật này (bằng quy nạp theo $k$), có thể dùng nhận xét rằng «các làn sóng kích thích», được sinh ra bởi mỗi trong hai ô hoạt động tại thời điểm $2^k$, không chồng lên nhau cho đến thời điểm $t = 2^{k+1} - 1$ và vì thế mỗi làn sóng được cấu tạo hoàn toàn giống như làn sóng kích thích từ một ô khi $t < 2^k$.

*) $\cos(2\pi - \alpha) = \cos \alpha$, vì thế công thức cũng đúng khi $\alpha > \pi$.

⟦trang 38⟧

Hình 5.

Bây giờ dễ trả lời các câu hỏi được nêu trong bài toán. Sau 15 thời điểm, như cũng thấy trên hình, sẽ có 16 ô có thể có. Sau 64 = 2⁶ sẽ có hai ô, vì thế sau 65 — bốn ô. Với một t cụ thể tùy ý, có thể tính f(t) — số ô có thể có tại thời điểm t, — bằng cách áp dụng liên tiếp vài lần tính chất 3: mỗi lần có thể trừ khỏi t lũy thừa của hai lớn nhất có thể; do đó f(t) giảm đi một nửa. Ví dụ:

$$1000 - 2^9 = 1000 - 512 = 488, \quad f(1000) = 488 - 2^8 = 488 - 256 = 232, \quad = 2f(488) = 232 - 2^7 = 232 - 128 = 104, \quad = 4f(232) = 104 - 2^6 = 104 - 64 = 40, \quad = 8f(104) = 40 - 2^5 = 40 - 32 = 8, \quad = 16f(40) = 8 - 2^3 = 8 - 8 = 0, \quad = 32f(8) = 64.$$

f(t) bằng 2ⁿ, trong đó m là số lượng chữ số một trong cách viết số t theo hệ nhị phân.

Quy tắc này dễ chứng minh bằng quy nạp, còn với các t đầu tiên bạn có thể kiểm tra nó — ở bên phải hình 5 có ghi các khai triển nhị phân của các số t.

Có lẽ, những độc giả của tạp chí còn nhớ bài báo của Đ. B. Fuks và M.B. Fuks «Số học của các hệ số nhị thức**» đã chú ý rằng sự sắp xếp các ô có thể có trên hình 5 hoàn toàn trùng với sự sắp xếp các số một trong tam giác Pascal theo môđun hai (hình trên bìa «Kvant» số 6). Như vậy, đồng thời ta đã giải bài toán sau: có bao nhiêu số một trong hàng thứ t của tam giác Pascal theo môđun 2, nói cách khác, có bao nhiêu trong các hệ số nhị thức Cᵢᵢ (k = 0, 1,..., t) là lẻ?

Đáp án cho câu hỏi thứ hai được nêu trong điều kiện bài toán — điều gì sẽ xảy ra nếu sắp xếp N ô trên một đường tròn?—tất nhiên, không chỉ phụ thuộc vào N, mà còn,

***) (Xem bài báo của I. M. Yaglom «Các hệ đếm» («Kvant» số 6) hoặc cuốn sách mỏng của S. V. Fomin cùng tên.
***) («Kvant» số 6.

⟦trang không có⟧

lò xo chưa bị kéo giãn, và thế năng của lò xo tại thời điểm lò xo bị kéo giãn cực đại: ngoài lực trọng trường và lực căng của lò xo, khi ấy còn có lực phản ứng của giá đỡ tác dụng lên vật. Công do lực này thực hiện, hiển nhiên, không bằng không. Chỉ sau khi vật rời khỏi giá đỡ, ta mới có thể coi rằng toàn năng lượng của vật và lò xo không thay đổi.

Hãy viết biểu thức năng lượng của lò xo và vật nặng tại thời điểm vật nặng rời khỏi giá đỡ. Vào thời điểm ấy vật nặng có vận tốc $V = at$
$$a \sqrt{\frac{M(g-a)}{k \cdot a}}.$$

động năng $\frac{MV^2}{2} = \frac{M^2(g-a)a}{k}$ và thế năng $Mg(x_0-x) = Mgx_0 - \frac{M^2(g-a)g}{k}$ (ta coi thế năng của vật nặng bằng không khi lò xo bị kéo giãn cực đại).

Vì tại thời điểm đó lò xo đã bị kéo giãn đến độ dài $x = \frac{M(g-a)}{k}$, nên thế năng biến dạng của lò xo bằng $\frac{kx^2}{2} = \frac{M^2(g-a)^2}{2k}$.

Cộng năng lượng của vật và lò xo, ta thấy rằng tổng năng lượng của chúng bằng
$$W_1 = \frac{M^2(g-a)a}{k} + Mgx_0 - \frac{M^2(g-a)g}{k} + \frac{M^2(g-a)^2}{2k} = Mgx_0 - \frac{M^2(g-a)^2}{2k}.$$

Vào lúc lò xo giãn cực đại, vận tốc của vật, và do đó động năng của nó, bằng không. Vì vậy năng lượng của vật và lò xo sẽ bằng $W_2 = \frac{kx_0^2}{2}$.

Viết $W_1 = W_2$, ta được phương trình
$$\frac{kx_0^2}{2} - Mgx_0 + \frac{M^2(g-a)^2}{2k} = 0.$$

Giải nó, ta tìm được
$$x_0 = \frac{Mg}{k} \pm \frac{M\sqrt{a(2g-a)}}{k}.$$

Độ giãn cực đại của lò xo phải lớn hơn độ giãn của nó khi vật cân bằng, khi trọng lực $Mg$ tác dụng lên vật được cân bằng bởi lực căng của lò xo $T = kx_1$: khi đi qua vị trí cân bằng, vật sẽ có một vận tốc nào đó, nên nhất định sẽ vượt qua nó. Do đó, vì $x_1 = \frac{Mg}{k}$ và $x_0 > x_1$, nên
$$x_0 = \frac{Mg}{k} + \frac{M\sqrt{a(2g-a)}}{k}.$$

Giá trị thứ hai của $x_0$ có ý nghĩa vật lí không? Có, nhưng nó cho không phải độ giãn cực đại mà là độ giãn cực tiểu của lò xo khi vật dao động. Nếu ta cho rằng thế năng của vật bằng không khi lò xo giãn một đoạn $x_0$, thì tại độ giãn cực tiểu của lò xo, khi viết định luật bảo toàn năng lượng, ta cũng sẽ nhận được phương trình như khi giãn cực đại.

Không khó xác định biên độ dao động của vật. Nó bằng giá trị các nghiệm của phương trình đối với $x_0$, tức là
$$\frac{2M\sqrt{a(2g-a)}}{k}.$$

Nếu $a \geq g$, thì vật sẽ rời khỏi giá đỡ ngay khi giá đỡ bắt đầu chuyển động. Viết định luật bảo toàn năng lượng, ta thấy rằng trong trường hợp này độ dãn cực đại của lò xo bằng $\frac{2Mg}{k}$

Lời giải đúng của bài này do N. Fedin từ Omsk gửi đến.

⟦folio 42⟧

Hình 8.

Ф25. Nếu thế anôt của tế bào quang điện cao hơn thế catôt, thì có dòng điện $I_0=10\text{ ma}$ chạy qua tế bào quang điện (như vậy được gọi). Trong trường hợp ngược lại, không có dòng điện chạy qua tế bào quang điện. Bỏ qua điện trở trong của các pin, hãy tìm điện áp trên các tế bào quang điện trong các mạch vẽ ở hình 8 (các giá trị điện trở được ghi trên hình bằng kilôôm).

Lời giải. Trước hết xét mạch thứ nhất. Giả sử không có dòng điện chạy qua tế bào quang điện. Khi đó qua các điện trở 1 và 2 kilôôm sẽ có dòng điện $I = \frac{200\theta}{1\text{ кОм} + 2\text{ кОм}} = \frac{1}{15}a$. Khi đó độ giảm điện áp trên điện trở 2 kilôôm bằng $2 \cdot 10^3\text{ ом} \cdot \frac{1}{15}a \approx 133\theta$. Điều này có nghĩa là trong trường hợp đó thế của catôt tế bào quang điện bằng $200\theta - 133\theta = +67\theta$. Nhưng thế của anôt bằng $+100\theta$, tức là cao hơn thế của catôt. Ta đi đến mâu thuẫn, vì trong trường hợp này phải có dòng điện chạy qua tế bào quang điện. Điều đó có nghĩa là qua tế bào quang điện có dòng điện $I_0 = 10\text{ ma}$. Hãy tìm hiệu thế giữa anôt và catôt. Thế của anôt bằng $+100\theta$ (ta coi thế của điểm $P$ bằng không). Vì vậy cần tìm thế của catôt. Muốn vậy cần xác định độ giảm điện áp trên điện trở 1 kilôôm.

Giả sử các dòng điện qua các điện trở có chiều như các mũi tên chỉ trên hình, và ký hiệu chúng là $I_1$ và $I_2$, ta có thể viết rằng $I_0 + I_2 = I_1$.

Để tìm $I_1$ và $I_2$, ta cần lập thêm một phương trình nữa. Xét một mạch vòng gồm điện trở và nguồn có suất điện động 200$\theta$. Vì công chuyển điện tích trong điện trường bằng hiệu điện thế nhân với độ lớn điện tích, nên ta có thể viết rằng

$$E - u_1 - u_2 = 0$$

hoặc

$$E = I_1 \cdot R_1 + I_2 \cdot R_2.$$

Giải đồng thời các phương trình (1) và (2), ta được $I_1 \approx 73\text{ ma}$. Điều này có nghĩa là điện thế catốt bằng $I_1R_1 = 73\theta$, còn hiệu điện thế giữa anốt và catốt bằng 27$\theta$.

Tương tự, xét sơ đồ thứ hai. Nếu ta, như trong trường hợp thứ nhất,

⟦folio 43⟧

giả sử rằng không có dòng điện qua tế bào quang điện, thì có thể coi rằng ta có hai nhánh mạch, một nhánh gồm các điện trở 1 và 3 kilôôm mắc nối tiếp, nhánh kia gồm các điện trở 2 và 4 kilôôm, hai nhánh được nối song song và mắc vào nguồn có suất điện động 100 $\beta$. Khi đó qua các điện trở 1 và 3 kilôôm sẽ có dòng điện $I = \frac{100\beta}{4 \cdot 10^3 \text{ ôm}} = 2,5 \cdot 10^{-2} a = 25 \text{ мa}$, còn độ giảm điện áp trên điện trở 1 kilôôm bằng 25 $\beta$. Vậy điện thế anốt là $\varphi_A = 100\beta - 25\beta = 75\beta$. Tương tự có thể tìm điện thế catốt. Trong trường hợp này nó bằng $33\frac{1}{3} \beta$. Hóa ra điện thế anốt cao hơn điện thế catốt, và dòng điện phải đi qua tế bào quang điện.

Ta sẽ coi rằng dòng điện qua tất cả các điện trở đi theo chiều từ trên xuống dưới, còn qua tế bào quang điện — từ trái sang phải. Khi đó có thể viết các phương trình sau:

$$I_4 + I_0 = I_2,$$
$$I_1 - I_0 = I_3,$$
$$I_1R_1 + U_0 - I_4R_4 = 0,$$
$$E = I_1R_1 + I_3R_3,$$
$$E = I_2R_2 + I_4R_4.$$

Ở đây $U_0$ là độ sụt điện áp trên pin quang điện.

Cũng như đối với sơ đồ trước, hai phương trình đầu tiên trong hệ này biểu thị định luật bảo toàn điện tích. Thật vậy, chẳng hạn, tại điểm nối của các điện trở 4 kôm và 2 kôm và pin quang điện, trong một đơn vị thời gian điện tích $I_0 + I_4$ đi vào, còn $I_2$ đi ra.

Giải hệ này, ta được $U_0 \approx 20,8\beta$.

F26. Hai nửa mặt phẳng nằm ngang, đặt chồng lên nhau cách nhau một độ cao $h$, chuyển tiếp trơn tru vào nhau, như trên hình 9. Trên nửa mặt phẳng trên, dưới góc $\alpha$ so với hướng đi xuống, một khối nhỏ chuyển động với vận tốc $v$. Nó sẽ chuyển động như thế nào trên nửa mặt phẳng dưới?

Coi rằng khối không bị bật lên, tức là chuyển động không rời khỏi mặt dốc. Bỏ qua ma sát.

Hình 9.

Lời giải. Phân tích vận tốc của khối thành hai thành phần: $v_2 = v \cos \alpha$ theo hướng xuống dốc và $v_1 = v \sin \alpha$ theo phương vuông góc (hình 10). Vì không có ngoại lực nào tác dụng lên khối theo phương $v_1$, nên thành phần vận tốc này của khối không thay đổi. Còn thành phần $v_2$ tăng lên. Nhờ đó vận tốc của khối cũng tăng lên.

Ta tìm vận tốc $u$ mà khối sẽ có sau khi nó đi vào nửa mặt phẳng dưới

⟦folio 44⟧

phẳng. Để làm điều này, ta có thể dùng định luật bảo toàn năng lượng
$$\frac{mv^2}{2} + mgh = \frac{mu^2}{2}.$$
Suy ra $u = \sqrt{v^2 + 2gh}$.

Bây giờ có thể tìm góc mà khối sẽ chuyển động trên nửa
mặt phẳng dưới:
$$\sin \beta = \frac{v_1^2}{u} = \frac{v}{\sqrt{v^2 + 2gh}} \sin \alpha.$$
Lời giải như vậy được gửi bởi học sinh lớp 9 G. Zaitsev từ Gagra, CHXHCNXV Gruzia.

Ф27. Đổ nước qua lỗ ở phía trên vào một chuông hình bán cầu nằm khít trên mặt bàn
(hình 11). Khi nước dâng đến lỗ, nó nhấc chuông lên và bắt đầu chảy ra từ dưới. Tìm khối lượng của chuông, nếu bán kính của nó bằng $R$, còn khối lượng riêng của nước là $\rho$.

Lời giải. Lực ép lên bàn bằng tổng các trọng lực tác dụng lên chuông và nước: $F = Mg + \frac{4}{3} \pi R^3 \rho g$. Nhưng vào lúc nước bắt đầu
nhấc chuông lên và chảy vào phía dưới, bản thân chuông không ép lên bàn. Vì vậy lực ép lên bàn bằng áp suất của nước nhân với diện tích
đáy bình. Áp suất nước lên bàn tại mọi điểm là như nhau và
bằng $\rho g R$, do đó $F = \rho g R \cdot \pi R^2$.

Điều này có nghĩa là $\pi R^3 \rho g = Mg + \frac{4}{3} \pi R^3 \rho g$. Suy ra $M = \frac{1}{3} \pi R^3 \rho$.

Một ý tưởng lời giải thú vị được Anatoly Vorovlyansky từ Gorky đề xuất.

Giả sử chuông được đặt trong một bình hình trụ có bán kính và chiều cao. Đổ đầy nước vào bình này và coi khối lượng của chuông là không đáng kể.
Không khó để nhận thấy rằng vì áp suất lên chuông từ bên ngoài và từ bên trong tại mọi điểm
bằng nhau (điều này suy ra từ định luật Pascal và điều kiện chuông rất mỏng),
nên trạng thái cân bằng của nước sẽ không bị phá vỡ nếu bỏ chuông đi. Áp suất của nước lên bàn trong
trường hợp này cũng không thay đổi. Nhưng điều đó có nghĩa là lực ép của nước mà ta phải đổ thêm vào bình hình trụ tác dụng giống như chuông, và do đó khối lượng của chuông đúng bằng khối lượng nước đổ thêm

$$M = (V \text{ цилиндра} - V \text{ полушара}) \rho = \left( R \pi R^2 - \frac{2}{3} \pi R^3 \right) \rho = \frac{1}{3} \pi R^3 \rho.$$
