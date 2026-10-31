---
id: 1972-7-gotman-teorema-kosinusov-i-ee-sledstviya-ebfa1deb
issue: kvant_1972_7
year: 1972
number: "7"
title: Định lý cosine và các hệ quả của nó
authors:
  - Готман Э. Г.
rubric: matematicheskiy-kruzhok
rubric_sub: Математический кружок
page_first: 31
page_last: 34
page_labels: 29-32
tag: G2GT
lang: vi
source: kvant_digital
extraction: vision
content_sha256: c0e16ebd87dc56b053313c319d36ff65aa24e70cb653827e1717930fa32c1463
prompt_sha256: draft-1
translated_from: content/ru/1972/07/articles/09_gotman-teorema-kosinusov-i-ee-sledstviya-ebfa1deb.md
source_content_sha256: 645ae642aea29c17e27d3e832185c3644891ab07c774a82487539fb494fdc46a
translation_model: draft
translation_run: vi-draft-2026-10-31
translation_quality: draft
---

⟦folio 29⟧

Bài viết này giải thích cách sử dụng định lý cosin để giải nhiều loại bài toáns hình học. Định lý cosin CAMA chưa được chứng minh.

Để tính các phần tử của một tam giác từ hai cạnh và góc giữa chúng hoặc từ ba cạnh, sự tương ứng được sử dụng

$$a^2 = b^2 + c^2 - 2bc \cos A,$$

gọi là "định lý cosin".

Định lý cosine cũng có thể được sử dụng cho lời giải khó hơn bài toán.

Ví dụ 1. Tìm diện tích hình bình hành nếu biết các cạnh a và b và góc nhọn α giữa hai đường chéo.

Lời giải. Đặt $ABCD$ là hình bình hành và đặt $AB = a$ và $BC = b$ (Hình 1). Chúng tôi sẽ giả định rằng $a > b^*$. Khi đó góc $BOC$ giữa các đường chéo là góc nhọn và theo điều kiện bài toán $\Rightarrow BOC = \alpha$.

Nếu chúng ta biểu thị độ dài của đường chéo $AC$ bằng 2x và độ dài của đường chéo bằng $*$) Nếu $a = b$, thì hình bình hành là hình thoi và góc giữa các đường chéo là một đường thẳng.

BD đến 2y thì diện tích hình bình hành $S$ bằng 2xysinα. Từ các tam giác $AOB$ và $BOC$, sử dụng định lý cosin, ta tìm được các cạnh a và b:

$$a^2 = x^2 + y^2 + 2xycos\alpha,$$
$$b^2 = x^2 + y^2 - 2xycos\alpha.$$

Bởi vì

$$a^2 - b^2 = 4xycos\alpha,$$

Ở đâu

$$xy = \frac{a^2 - b^2}{4cos\alpha}.$$

Kể từ đây,

$$S = \frac{(a^2 - b^2)sin\alpha}{2cos\alpha}$$

hoặc

$$S = \frac{a^2 - b^2}{2}tg\alpha.$$

Ghi chú. Nếu $A$ là góc của hình bình hành thì $S = absinA$, ngụ ý rằng $0 < S \leq ab$. Bởi vì

$$\frac{a^2 - b^2}{2}tg\alpha \leq ab$$ và

$$tg\alpha \leq \frac{2ab}{a^2 - b^2}.$$

Như vậy, để bài toán có lời giải cần chọn tham số a, b và α sao cho thỏa mãn các bất đẳng thức

$$a > b > 0, \alpha \leq arctg \frac{2ab}{a^2 - b^2}.$$

⟦folio 30⟧

Sử dụng các công thức hình học và lượng giác nổi tiếng, từ định lý cosin, người ta có thể rút ra một số mối quan hệ nối các phần tử của bất kỳ tam giác nào.

Ví dụ 2. Chứng minh các cạnh, các cạnh và diện tích S của tam giác ABC thỏa mãn hệ thức

$$\text{ctg } A + \text{ctg } B + \text{ctg } C = \frac{a^2 + b^2 + c^2}{4S}.$$

Lời giải. Từ công thức $S = \frac{1}{2} bc \sin A$ chúng ta tìm thấy $bc = \frac{2S}{\sin A}$. Thay thế biểu thức $\frac{4S}{\sin A}$ vào công thức $a^2 = b^2 + c^2 - 2bc \cos A$ cùng với $2bc$, ta thu được hệ thức

$$a^2 = b^2 + c^2 - 4S \text{ctg } A.$$ (1)

Kể từ đây,

$$\text{ctg } A = \frac{b^2 + c^2 - a^2}{4S}.$$

Nếu theo công thức này, chúng ta biểu thị thông qua các cạnh của tam giác $ctg B$ và $ctg C$ rồi cộng các biểu thức thu được thì chúng ta thu được đẳng thức

$$\text{ctg } A + \text{ctg } B + \text{ctg } C = \frac{a^2 + b^2 + c^2}{4S}.$$

Ví dụ 3. Chứng minh rằng với mọi tam giác mọi bất đẳng thức sau đều đúng:

a) $\sin \frac{A}{2} \leqslant \frac{a}{2\sqrt{bc}}$,

b) $\text{tg} \frac{A}{2} \leqslant \frac{a}{2h_a}$,

$a, b, c$ là các cạnh của tam giác ABC và $h_a$ là đường cao vẽ từ đỉnh A.

Lời giải. a) Công thức (*) có thể viết như sau:

$$a^2 = (b - c)^2 + 2bc (1 - \cos A).$$

Nếu $1 - \cos A$ bây giờ được thay thế bằng $2\sin^2 \frac{A}{2}$, thì chúng ta có công thức sau

$$a^2 = (b - c)^2 + 4bc \sin^2 \frac{A}{2}.$$ (2)

Sau đó

$$a^2 \geqslant 4bc \sin^2 \frac{A}{2},$$

hoặc

$$\sin \frac{A}{2} \leqslant \frac{a}{2\sqrt{bc}},$$

và sự bình đẳng chỉ đạt được ở $b = c$.

6) Công thức (2) có thể dễ dàng rút gọn về dạng này:

$$a^2 = (b - c)^2 + 4S \text{tg} \frac{A}{2}.$$ (3)

Để làm điều này, chỉ cần thực hiện các phép biến đổi sau:

$$bc \sin^2 \frac{A}{2} = \frac{2S}{\sin A} \sin^2 \frac{A}{2} =$$

$$= \frac{2S\sin^2 \frac{A}{2}}{2\sin \frac{A}{2}\cos \frac{A}{2}} = S \text{tg} \frac{A}{2}.$$

Công thức (3) suy ra bất đẳng thức $a^2 \geqslant 4S \text{tg} \frac{A}{2}$, từ đó $tg \frac{A}{2} \leqslant \frac{a^2}{4S}$.

Xét rằng $S = \frac{1}{2} ah_a$, chúng ta thu được bất đẳng thức $tg \frac{A}{2} \leqslant \frac{a}{2h_a}$.

Từ các ví dụ trên, rõ ràng là công thức

$$a^2 = b^2 + c^2 - 2bc \cos A$$

sử dụng các phép biến đổi đơn giản thành một trong các loại 1-3. Các mối quan hệ sau đây có nguồn gốc tương tự:

$$a^2 = (b + c)^2 - 4bc \cos^2 \frac{A}{2},$$ (4)

$$a^2 = (b + c)^2 - 4S \text{tg} \frac{A}{2}.$$ (5)

Bây giờ chúng ta hãy xem xét một số bài toán có thể được giải bằng công thức (1)–(5).

Ví dụ 4. Tính diện tích hình tam giác khi biết các cạnh của nó.

⟦folio 31⟧

Lời giải. Ta viết lại tương ứng (3) và (5) như sau:

$$4S \mathrm{tg} \frac{A}{2} = a^2 - (b - c)^2,$$
$$4S \mathrm{ctg} \frac{A}{2} = (b + c)^2 - a^2.$$

Nếu chu vi của một tam giác được ký hiệu là 2p thì
$$a^2 - (b - c)^2 = (a + b - c) \times (a + c - b) = 4(p - b) \times (p - c),$$
$$(b + c)^2 - a^2 = (a + b + c) \times (b + c - a) = 4p(p - a).$$

Kể từ đây,

$$S \mathrm{tg} \frac{A}{2} = (p - b)(p - c),$$
$$S \mathrm{ctg} \frac{A}{2} = p(p - a).$$

Biến đổi các đẳng thức này theo từng số hạng, chúng ta thu được công thức nổi tiếng của Heron để tính diện tích hình tam giác

$$S^2 = p(p - a)(p - b)(p - c).$$

Ví dụ 5. Cho tam giác đều ABC có cạnh a. Qua điểm M nằm trên cạnh AB kẻ các đường thẳng song song với các cạnh AC và BC của tam giác, cắt các cạnh này lần lượt tại các điểm K và L. Tính diện tích tam giác KLM nếu KL = d (Hình 2).

Lời giải. Chúng ta hãy ký hiệu các đoạn KM và LM lần lượt là x và y. Do đó tam giác AKM và BLM đều bằng nhau

![Рис. 2.](image)

Ví dụ 6. Chia tam giác này thành hai phần bằng nhau bằng đoạn có độ dài ngắn nhất.

Lời giải. Cho đoạn MN chia diện tích tam giác ABC làm đôi (Hình 3). Nếu điểm M và N nằm trên hai cạnh góc BAC và S là diện tích tam giác ABC thì diện tích tam giác AMN bằng $\frac{1}{2}S$, và theo công thức (3)

$$MN^2 = (AM - AN)^2 + 2S \mathrm{tg} \frac{A}{2},$$

Từ đây chúng ta thấy ngay rằng với AM = AN thì đoạn MN có độ dài ngắn nhất bằng $\sqrt{2S \mathrm{tg} \frac{A}{2}}$.

⟦folio 32⟧

Hình 3.

Độ dài đoạn AM dễ tính vì $S = AM^2 \sin A = \frac{1}{2} bc \sin A,$

Ở đâu

$$AM = \sqrt{\frac{bc}{2}}.$$

Rõ ràng rằng nếu hai đầu của đoạn MN nằm trên các cạnh của góc B của tam giác thì độ dài ngắn nhất của đoạn này là $\sqrt{2S \mathrm{tg} \frac{B}{2}}.$

Hãy để $a < b < c,$ sau đó

$$\sqrt{2S \mathrm{tg} \frac{A}{2}} < \sqrt{2S \mathrm{tg} \frac{B}{2}} < \sqrt{2S \mathrm{tg} \frac{C}{2}}.$$

Đối với Posny, độ dài đoạn tối thiểu MN bằng $\sqrt{2S \mathrm{tg} \frac{A}{2}}.$ đồng thời $AM = AN = \sqrt{\frac{bc}{2}}.$

Việc dựng đoạn MN luôn có thể thực hiện được; kể từ $c < a + b < 2b,$ rồi $\sqrt{\frac{bc}{2}} < b$ và thậm chí hơn thế nữa $\sqrt{\frac{bc}{2}} < c.$

Để kết luận, chúng tôi trình bày một số bài toán mà chúng tôi để người đọc tự giải quyết.

1. Trên các cạnh của một tam giác có góc $60^\circ$ có các tam giác đều bên ngoài cấu trúc của nó. Chứng minh rằng tổng diện tích của tam giác đã cho và tam giác dựng trên cạnh đối diện với góc $60^\circ,$ bằng tổng diện tích của hai tam giác.

2. Trên các cạnh của tam giác $ABC,$ góc $C$ bằng $135^\circ,$, bên ngoài nó dựng các hình vuông $ABMN, BCKL$ và $CAPQ.$. Chứng minh rằng diện tích hình lục giác $KLMNPQ$ bằng hai lần diện tích hình vuông $ABMN.$

3. Tính diện tích hình bình hành $ABCD,$ nếu $AB=5, BC=2$ và góc giữa các đường chéo của nó là $45^\circ.$

4. Biểu diễn hàm lượng giác của các góc đa giác của một tam giác theo các cạnh của nó.

5. Chứng minh rằng các cạnh của tam giác $ABC$ thỏa mãn đẳng thức $a^2 + b^2 = 2c^2$ khi và chỉ khi các góc của tam giác liên hệ với nhau bởi các quan hệ

$$\text{ctg} A + \text{ctg} B = 2 \text{ctg} C.$$

6. Các cạnh của tam giác $ABC$ được nối bởi các phụ thuộc $a^2 + b^2 = nc^2,$ trong đó $n>1.$ Chứng minh rằng $\cos C \geq \frac{n-1}{n}.$

7. Chứng minh rằng các góc của tam giác đều thỏa mãn bất đẳng thức.

$$\text{tg} \frac{A}{2} + \text{tg} \frac{B}{2} + \text{tg} \frac{C}{2} \leq \text{ctg} A + \text{ctg} B + \text{ctg} C.$$

8. Một tam giác đều có cạnh $a.$ nội tiếp trong một đường tròn. Chứng minh rằng $x^2 + y^2 + z^2 = 2a^2,$ trong đó $x, y, z$ là khoảng cách từ một điểm tùy ý trên đường tròn đến các đỉnh của tam giác.

9. Một đường tròn nội tiếp tam giác $ABC$ và tiếp xúc với các cạnh $AB$ và $AC$ tại các điểm $M$ và $N.$ Xác định góc $A$ của tam giác nếu $\frac{AM}{MB} = \frac{1}{6}$ và $\frac{AN}{NC} = \frac{1}{7}.$

10. Tìm diện tích của tam giác $ABC,$ biết góc $A$ và các đoạn $m$ và $n,$ mà điểm tiếp tuyến của đường tròn nội tiếp chia cạnh $BC.$

11. Cho một đường thẳng $l$ và hai điểm $A$ và $B,$ không nằm trên đó. Tìm trên dòng $l$ điểm $M,$ mà tại đó tỷ lệ $\frac{AM}{BM}$ lấy $a)$ giá trị lớn nhất; $6)$ ý nghĩa nhất.

12. Chứng minh rằng các góc của tam giác đều thỏa mãn bất đẳng thức

$$\sin \frac{A}{2} \sin \frac{B}{2} \sin \frac{C}{2} \leq \frac{1}{8}.$$

13. Một hình thang có đáy $a$ và $b$ ($a > b$) được mô tả xung quanh một hình tròn có bán kính $r$. Tính góc giữa các cạnh của nó.

14*) Chứng minh rằng với mọi tam giác $ABC$ luôn có hệ thức sau:

$$16S^2 = (a^2 + c^2 - b^2)(a^2 + b^2 - c^2) + (b^2 + c^2 - a^2)(a^2 + b^2 - c^2) + (b^2 + c^2 - a^2)(a^2 + b^2 - b^2).$$

*) bài toán này được gửi bởi độc giả V.P. Gasparin.
