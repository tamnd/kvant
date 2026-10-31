---
id: 1972-10-grudenov-metod-resheniya-zadach-s-kontsa-69ce3b22
issue: kvant_1972_10
year: 1972
number: "10"
title: Phương pháp lời giải bài toán "từ cuối"
authors:
  - Груденов Я. И.
rubric: praktikum-abiturienta
rubric_sub: Практикум абитуриента
page_first: 49
page_last: 53
page_labels: 47, 48, 50, 51
tag: DPHK
lang: vi
source: kvant_digital
extraction: vision
content_sha256: 047d72f28dcbed0eb2a5495737f3f6787af3c25c6451673866bd02e7323671fa
prompt_sha256: draft-1
translated_from: content/ru/1972/10/articles/12_grudenov-metod-resheniya-zadach-s-kontsa-69ce3b22.md
source_content_sha256: 531f1bb66fe344036d290266aac5927f3cb137023875c66c02f276300cef435a
translation_model: draft
translation_run: vi-draft-2026-10-31
translation_quality: draft
---

⟦folio 47⟧

Phương pháp lời giải bài toán "từ cuối"

Thông thường lời giải bài toán hoặc việc chứng minh định lý chúng ta thực hiện từ cái đã biết đến cái chưa biết, từ cái đã cho đến cái cần tìm. Nhưng bạn có thể hành động khác đi. Ở đây chúng ta sẽ xem xét phương pháp lời giải bài toán “từ cuối”, khi việc suy luận được thực hiện từ cái chưa biết đến cái đã biết, từ cái được tìm kiếm đến cái đã cho.

Đề án chung

Cần phải chứng minh một khẳng định nào đó $A$. Giả sử điều đó đúng và dựa trên dữ liệu bài toán và các định lý đã biết, chúng ta sẽ cố gắng thu được hệ quả đúng từ $A$. Trong trường hợp này, một số trường hợp có thể xảy ra.

1. Đã thu được một kết quả không chính xác. Điều này có nghĩa là giả định của chúng tôi về tính hợp lệ của tuyên bố $A$ là sai. Lời giải bài toán về luật này - chúng tôi nhận thấy rằng $A$ là không chính xác.

2. Đã thu được một kết quả không chính xác. Trong trường hợp này, bạn nên kiểm tra tính thuận nghịch của đối số, vì từ một phát biểu sai (ví dụ: $a = -a$, $a \neq 0$), bạn cũng có thể nhận được hệ quả đúng ($a^2 = a^2$).

a) Nếu mọi lý luận đều ngược lại thì $A$ là đúng.

b) Nếu trong số các lý do có những lý do không thể đảo ngược (ví dụ: ở một giai đoạn nào đó chúng ta bình phương đẳng thức), thì việc sử dụng các phương pháp tìm lời giải bài toán khác sẽ được áp dụng.

3. Nếu không thể thu được kết quả chính xác thì cũng đã đến lúc chuyển sang các phương pháp khác.

Hai gợi ý

1. Trong các biểu thức trung gian thu được, nên giảm số lượng tham số và sau đó đơn giản hóa các biểu thức này.

2. Nếu bài toán không chứa điều kiện bổ sung * thì tất cả dữ liệu bài toán phải được sử dụng.

Ví dụ

Ví dụ 1. Trong tam giác vuông ABC, số AC lớn hơn số AB ba lần. Điểm K và M của đá AC được chia thành ba phần bằng nhau. Chứng minh rằng $\triangle AMB + \triangle AKB + \triangle ACB = 90^\circ$.

Lời giải e. Đặt $\triangle AMB = \alpha$, $\triangle AKB = \beta$, $\triangle ACB = \gamma$ (Hình 1). Giả sử $\alpha + \beta + \gamma = 90^\circ$ (1)

hoặc, vì $\alpha = 45^\circ$,

$$\beta + \gamma = 45^\circ.$$ (1a)

Sau đó

$$tg(\beta + \gamma) = tg 45^\circ,$$ (2)

$$\frac{tg \beta + tg \gamma}{1 - tg \beta \cdot tg \gamma} = 1.$$ (2a)

*) Việc tìm ra dòng điều kiện của nó là một điểm cộng lớn lời giải, nhưng thông thường các dòng bài toán cạnh tranh không chứa điều kiện của chúng.

⟦folio 48⟧

Đẳng thức (2) hoặc (2a) đúng vì
$$tg \beta = \frac{AB}{AK} = \frac{1}{2}, \quad tg \gamma = \frac{1}{3}$$

Và
$$\frac{\frac{1}{2} + \frac{1}{3}}{1 - \frac{1}{2} \cdot \frac{1}{3}} = 1.$$

Học sinh thường kết thúc với lời giải bài toán, tức là

**Cơm. 1.**

một sai lầm. Bắt đầu đảo ngược các phép biến đổi, chúng ta nhận thấy rằng từ tính hợp lệ của đẳng thức (2), nó không dẫn đến đẳng thức (1a), mà là sự phụ thuộc
$$\beta + \gamma = 45^\circ + 180^\circ \cdot n,$$
ở đâu $n = 0; \pm 1; \pm 2; \pm 3; \dots$

Nhưng từ các tam giác $AKB$ và $ACB$ ta thấy rằng $0 < \beta < 45^\circ; 0 < \gamma < 45^\circ$ do đó
$$0 < \beta + \gamma < 90^\circ.$$

Do đó, từ sự tương ứng (2) và (3) suy ra $\beta + \gamma = 45^\circ$, và, vì $\alpha = 45^\circ$, nên $\alpha + \beta + \gamma = 90^\circ$.

Ví dụ 2. Chứng minh rằng trong tam giác bất kỳ $R = \frac{a \cdot b \cdot c}{4S}$, trong đó $a, b, c$ là các cạnh của tam giác, $S$ là diện tích, $R$ là bán kính của đường tròn ngoại tiếp.

Lời giải e. Giả sử đẳng thức là đúng:
$$R = \frac{a \cdot b \cdot c}{4S}.$$

Hãy giảm số lượng tham số:
$$R = \frac{a \cdot b \cdot c}{4 \cdot \frac{1}{2} b \cdot c \cdot \sin A}, \quad R = \frac{a}{2 \cdot \sin A},$$

Ở đâu
$$2R = \frac{a}{\sin A},$$

điều này đúng theo định luật sin. Tất cả các phép biến đổi đều dễ dàng xử lý, do đó đẳng thức (4) được chứng minh.

Ví dụ 3. Các cạnh của tam giác $a, b, c$ ($a < b < c$) tạo thành một quá trình số học. Chứng minh rằng $ac = 6Rr$, trong đó $R$ là bán kính của đường tròn ngoại tiếp, $a$ $r$ là bán kính của đường tròn ngoại tiếp trong tam giác.

Lời giải e. Hãy để đẳng thức $ac = 6Rr$ là đúng. Hãy giảm số lượng tham số bằng cách biểu thị $R$ và $r$ theo các cạnh của tam giác: $R = \frac{abc}{4S}, r = \frac{S}{p}$, trong đó $S$ là diện tích của tam giác, $p$ là nửa chu vi của tam giác. Chúng tôi nhận được:
$$ac = 6 \cdot \frac{abc}{4S} \cdot \frac{S}{p}, \quad 1 = \frac{3b}{2p},$$
$$a + b + c = 3b, \frac{a + c}{2} = b,$$

điều này đúng, vì $a, b, c$ tạo thành một quá trình số học.

Tất cả các phép biến đổi này có thể được kiểm tra theo thứ tự ngược lại, do đó, sự tương ứng được chứng minh là đúng.

Ví dụ 4. Chứng minh tích các đường chéo của một hình treo bằng tổng các cạnh đối diện (định lý Ptolemy).

Lời giải e. Giả sử đẳng thức là đúng (Hình 2):
$$AC \cdot BM = AM \cdot BC + AB \cdot CM.$$

Hãy giảm số lượng tham số bằng cách biểu thị tất cả các phân đoạn theo một số phần tử khác. Nhu cầu sử dụng tất cả dữ liệu bài toán (gấp bốn - vissanny) đưa chúng ta đến ý tưởng

⟦folio 50⟧

Ở đâu
$$\sin(\alpha + \beta) \cdot \cos \alpha = 2 \sin \alpha \times \cos (\alpha + \beta);$$
$$\left( \alpha + \beta \neq \frac{\pi}{2} + \pi k; \quad \alpha \neq \frac{\pi}{2} + \pi n \right);$$
$$\frac{1}{2} \left[ \sin (2\alpha + \beta) + \sin \beta \right] =$$
$$= 2 \cdot \frac{1}{2} \left[ \sin (2\alpha + \beta) + \sin (-\beta) \right);$$
$$3 \sin \beta = \sin (2\alpha + \beta),$$

điều này đúng với điều kiện bài toán.

Các phép biến đổi này có thể được chứng minh theo thứ tự ngược lại (với tất cả các giá trị hợp lệ của các đối số), do đó đẳng thức (9) là đúng.

Ví dụ 7. Chứng minh rằng với mọi giá trị chấp nhận được của $\alpha$ ta có bất đẳng thức
$$|\mathrm{tg} \alpha + \mathrm{ctg} \alpha| > |\sin \alpha + \cos \alpha|.$$ (11)

Lời giải e. Giả sử rằng bất đẳng thức (11) là đúng. Hãy giảm số lượng chức năng:
$$\left| \frac{\sin^2 \alpha + \cos^2 \alpha}{\sin \alpha \cos \alpha} \right| > |\sin \alpha + \cos \alpha|;$$ (12)
$$\frac{1}{|\sin \alpha \cdot \cos \alpha|} > |\sin \alpha + \cos \alpha|.$$ (13)

Để so sánh độ lớn của các biểu thức này, nên biểu thị chúng thông qua một hàm, ví dụ: thông qua sin:
$$\frac{2}{|\sin 2\alpha|} > \sqrt{2} |\sin \left( \alpha + \frac{\pi}{4} \right)|.$$ (14)

Nhưng $|\sin 2\alpha| \leqslant 1$, $|\sin \left( \alpha + \frac{\pi}{4} \right)| \leqslant 1$, do đó $\frac{2}{|\sin 2\alpha|} \geqslant 2$, và $\sqrt{2} |\sin \left( \alpha + \frac{\pi}{4} \right)| \leqslant \sqrt{2}$, và bất đẳng thức (14) đúng với tất cả các giá trị được chấp nhận của $\alpha$.

Từ bất đẳng thức (14) suy ra (13), và do đó (12), và từ bất đẳng thức (12) suy ra (11), do đó bất đẳng thức (11) đúng với mọi $\alpha \neq \frac{\pi k}{2}$.

Suy luận trên cho thấy có thể chứng minh được bất đẳng thức mạnh hơn
$$|\mathrm{tg} \alpha + \mathrm{ctg} \alpha| \geqslant \sqrt{2} |\sin \alpha + \cos \alpha|.$$ (50)

Ví dụ 8. Chứng minh rằng trong mọi tam giác
$$h_a > \sqrt{p(p-a)},$$ (15)

trong đó $h_a$ là chiều cao hạ xuống cạnh $a$, $p$ là mét của tam giác.

Lời giải e. Cho bất đẳng thức (15) đúng. Hãy giảm số lượng tham số:
$$\frac{\sqrt{p(p-a)(p-b)(p-c)}}{1/2 a} > \sqrt{p(p-a)}.$$

Chúng tôi đã sử dụng các công thức
$$S_\Delta = \frac{1}{2} h_a \cdot a,$$
$$S_\Delta = \sqrt{p(p-a)(p-b)(p-c)},$$
$$\sqrt{(p-b)(p-c)} > \frac{1}{2} a.$$

Cả hai vế của bất đẳng thức đều dương - chúng có thể bình phương
$$(p-b)(p-c) > \frac{a^2}{4},$$
$$\frac{a+c-b}{2} \cdot \frac{a+b-c}{2} > \frac{a^2}{4},$$
$$a^2 + ab - ac + ac + bc - c^2 - ab - b^2 + bc > a^2,$$
$$2bc - c^2 - b^2 > 0,$$
$$-(b-c)^2 > 0,$$

điều đó không đúng. Do đó, giả định của chúng tôi về giá trị của bất đẳng thức (15) là sai.

Tại thời điểm này, lời giải bài toán có thể được coi là hoàn chỉnh hoặc chúng tôi đã chứng minh rằng công thức (15) là sai. Tuy nhiên, sau khi chứng minh được công thức (15) sai, qua đó ta chứng minh được công thức đó luôn đúng
$$h_a \leqslant \sqrt{p(p-a)}.$$

Cố gắng tìm ra khi nào sự bằng nhau xảy ra trong công thức cuối cùng. Ở đây phương pháp của chúng tôi lời giải bài toán “từ cuối” trở thành phương pháp “bằng mâu thuẫn”.

Kỹ thuật lời giải hình học bài toán này có những điểm tương đồng nhất định với phương pháp được mô tả, khi được yêu cầu

⟦folio 51⟧

và các phần tử chưa biết khác (đoạn, góc, v.v.) được chỉ định bằng các chữ cái $x, y, z, \dots$ và được xử lý như thể chúng đã biết.

Ví dụ 9. Trong một hạt có góc 120°, một hình vuông được nội tiếp. Tìm cạnh hình vuông biết bán kính hình tròn là $R$.

Lời giải. Đặt $ABCK$ là hình vuông, $\cup EF = 120^\circ$, $O$ là tâm của hình tròn (Hình 3). Hãy biểu thị

Cơm. 3.

$BC$ đến $2x$ và vẽ $OP \perp EF$. Sau đó $ON = \sqrt{R^2 - x^2}$, $OM = \frac{1}{2}R$, $MN = 2x$, $OM = ON - MN$.

Chúng ta có phương trình
$$\frac{R}{2} = \sqrt{R^2 - x^2} - 2x$$
giải quyết điều đó, chúng tôi nhận được $x = \frac{R(\sqrt{19} - 2)}{10}$

Đáp số: $\frac{R(\sqrt{19} - 2)}{5}$.

Nhiều học sinh không chỉ mắc lỗi lời giải bài toán mà còn mắc lỗi khi trình bày các câu hỏi lý thuyết. Ví dụ, đây là cách họ chứng minh một danh tính nổi tiếng:
$$\log_a \left( \frac{x}{y} \right) = \log_a x - \log_a y$$
(tại $x > 0$ và $y > 0$).

“Chúng ta hãy di chuyển $\log_a y$ sang vế trái và sử dụng định lý đã được chứng minh trước đó:
$$\log_a \left( \frac{x}{y} \right) + \log_a y = \log_a x$$
$$\log_a \left( \frac{x}{y} \cdot y \right) = \log_a x$$
$$\log_a x = \log_a x.$$

Ta đã thu được đẳng thức đúng, nghĩa là công thức ban đầu đã được chứng minh.”

Rõ ràng là những lập luận này vẫn chưa chứng minh được công thức. Họ nói, học sinh thường chửi thề trong sách giáo khoa của trường, nơi công thức được chứng minh theo cách giống hệt nhau, thậm chí không thể hiểu được. Đối với họ, việc tham khảo trong sách giáo khoa về sự tương đương của các công thức không được chú ý.

Bài tập

1. Trong một tam giác đều có đáy $a$ và cạnh $b$, góc ở đỉnh là $20^\circ$. Chứng minh rằng $a^3 + b^3 = 3ab^2$.

2. Chứng minh rằng trong một tứ giác lồi, hai góc kề với một cạnh tạo thành một góc bằng nửa tổng hai góc còn lại.

3. Chứng minh bất đẳng thức
$$\text{ctg} \frac{\varphi}{2} > 1 + \text{ctg} \varphi$$ tại $0 < \varphi < \frac{\pi}{2}$.

4. Chứng minh bất đẳng thức $(x + y)(x + y + 2\cos x) + 2 \geq 2\sin^2 x$. Ở giá trị nào của $x$ và $y$ thì đạt được sự bình đẳng?

5. Trong tam giác $ABC$, các góc $A, B$ và $C$ tạo thành một cấp số nhân có giá trị phần tử là 2. Chứng minh rằng $\frac{1}{a} = \frac{1}{b} + \frac{1}{c}$.

6. Chứng minh rằng
$$\frac{1}{\log_2 \pi} + \frac{1}{\log_5 \pi} + \frac{1}{\log_{10} \pi} > 4.$$

7. Chứng minh rằng tổng bề mặt lớn nhất của một hình bình hành thẳng bằng $\frac{M^2}{24}$, trong đó $M$ là tổng độ dài các cạnh của hình bình hành đó.

8. Có đúng là tổng bình phương các đường chéo của hình thang bằng tổng bình phương các cạnh bên cộng với tích hai đáy không?

9. Kiểm tra xem bất đẳng thức sau có được chứng minh đúng hay không:
$$\sin^2 \alpha + \sin^2 \beta \geq \sin \alpha \cdot \sin \beta + \sin \alpha \cdot \sin \beta - 1?$$

“Ta hãy viết lại bất đẳng thức cần chứng minh dưới dạng
$$2\sin^2 \alpha + 2\sin^2 \beta - 2\sin \alpha \cdot \sin \beta - 2\sin \alpha - 2\sin \beta + 2 \geq 0,$$
hoặc
$(\sin \alpha - 1)^2 + (\sin \beta - 1)^2 + (\sin \alpha - \sin \beta)^2 \geq 0,$
điều đó rất đau đớn."

10. Có đúng vậy không $\sin(\cos \varphi) = \cos(\sin \varphi)?$
