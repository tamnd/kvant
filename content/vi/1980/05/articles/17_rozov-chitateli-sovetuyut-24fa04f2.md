---
id: 1980-5-rozov-chitateli-sovetuyut-24fa04f2
issue: kvant_1980_5
year: 1980
number: "5"
title: Lời khuyên của độc giả
authors:
  - Розов Н. Х.
rubric: praktikum-abiturienta
rubric_sub: Практикум абитуриента
page_first: 48
page_last: 52
page_labels: 46-50
tag: S85W
lang: vi
source: kvant_digital
extraction: vision
content_sha256: e9f74109fd66dc1f296e399ca35d3f979f5af9e9562a3a904c6beb864eeedb0e
prompt_sha256: draft-1
translated_from: content/ru/1980/05/articles/17_rozov-chitateli-sovetuyut-24fa04f2.md
source_content_sha256: aa39e6b6acb3461b40cb356c78104687f6cea9fa801b0ea339168c1448bff7de
translation_model: draft
translation_run: vi-draft-2026-10-31
translation_quality: draft
---

⟦folio 46⟧

Hội thảo lối vào

N. Rozov

Lời khuyên của độc giả

Những bức thư và ghi chú được đăng trên «Kvant» gửi tới học sinh, giáo viên và những người đam mê toán học thường đề cập đến các vấn đề liên quan đến chủ đề của “Hội thảo Ứng dụng”. Độc giả của tạp chí đưa ra những nhận xét có tính chất lý thuyết, báo cáo các kỹ thuật lời giải thuộc từng loại riêng lẻ bài toán, đưa ra lời khuyên về phương pháp và đưa ra các bài tập được phát minh độc lập. Các tin nhắn và bài toán có trong những bức thư và ghi chú này không phải lúc nào cũng mới và nguyên bản, nhưng theo chúng tôi, một số trong số chúng rất hữu ích để tham khảo khi chuẩn bị cho kỳ thi tuyển sinh đại học. Vì vậy, ban biên tập quyết định chuẩn bị một tuyển tập tài liệu khác, biên soạn theo ý kiến ​​góp ý của độc giả «Kvant», kèm theo những nhận xét bổ sung cần thiết.

Trong các biến thể của kỳ thi tuyển sinh môn toán, người ta thường gặp phải hệ thống kiểm soát. Theo quy định, người nộp đơn thành thạo các kỹ thuật cơ bản của hệ thống lời giải - phương pháp thay thế và phương pháp loại bỏ. Độc giả tạp chí P. Chebotarev (Moscow) thu hút sự chú ý đến một thông điệp thú vị cho phép giải quyết một số hệ thống điều khiển. Tuy nhiên, trước khi nói về điều này, chúng ta hãy nói một chút về các hàm phức tạp thuộc loại đặc biệt.

Giả sử hàm $f$ và để đơn giản, chúng ta sẽ giả sử rằng $D(f) = R$. Dựa vào chức năng này, bạn có thể hình thành một chức năng mới

$$F(x) = f(f(x));$$

nó cũng được xác định rất rõ ràng trên toàn bộ trục số. Hàm $F$ thường được gọi là hàm *lặp*) $f$. Từ Hình 1, có thể dễ dàng hiểu cách sử dụng đồ thị của hàm $f$ để tìm giá trị lặp $f(f(x_*))$ cho một giá trị cụ thể $x_*$ của đối số.

Xét phương trình

$$f(f(x)) = x. \tag{1}$$

Trước hết, hãy lưu ý rằng nếu $x_0$ là nghiệm của phương trình

$$f(x) = x, \tag{2}$$

thì $x_0$ là nghiệm của phương trình (1). Nhưng tất nhiên, phương trình (1) có thể có các nghiệm khác không phải là nghiệm của phương trình (2) (hãy thử xem thực tế này từ Hình 1).

Vì phương trình (2) là phương trình (1), nên sẽ rất hữu ích khi chỉ ra các tình huống trong đó các phương trình này tương đương nhau. Ví dụ, chúng ta hãy chứng minh mệnh đề sau: nếu hàm $f$ thỏa mãn điều kiện

$$\begin{cases} f(x) \geq x, \text{ при всех } x < a, \\ f(a) = a, \\ a \leq f(x) \leq x, \text{ при всех } x > a, \end{cases}$$

thì phương trình (1) và (2) là tương đương (đưa ra cách giải thích hình học của định lý này).

Ở trên đã lưu ý rằng nghiệm của phương trình (2) luôn đóng vai trò là nghiệm của phương trình (1); Hãy để chúng tôi thiết lập tính hợp lệ của tuyên bố ngược lại. Đặt $x_0$ là nghiệm của phương trình (1):

$$f(f(x_0)) = x_0; \tag{4}$$

*) Nói chung, phép lặp (từ tiếng Latin iteratio - lặp lại) trong toán học là kết quả của việc áp dụng lặp đi lặp lại từng thao tác.

⟦folio 47⟧

Chúng ta hãy xem xét riêng từng trường hợp có thể xảy ra $x_0 > a$, $x_0 < a$, $x_0 = a$.

Nếu $x_0 > a$ thì (xem (3))
$$a \leq f(x_0) \leq x_0.$$ (5)

Từ tính chất (3) của hàm $f$, suy ra các bất đẳng thức $a \leq f(z) \leq z$ đúng với mọi $z \geq a$. Do đó, chọn $z = f(x_0)$, xét đến (5), ta có
$$a \leq f(f(x_0)) \leq f(x_0).$$ (6)

Từ sự tương ứng (6) và (5) rõ ràng rằng
$$f(f(x_0)) \leq f(x_0) \leq x_0.$$
So sánh bất đẳng thức số nguyên này với đẳng thức (4), chúng ta kết luận rằng $f(x_0) = x_0$, tức là $x_0$, là nghiệm của phương trình (2).

Chúng ta hãy giả định thêm rằng $x_0 < a$.
Trong trường hợp này, bất đẳng thức $f(x_0) \geq a$ là không thể: nếu nó xảy ra thì sự tương ứng (6) sẽ được thỏa mãn, điều này nếu xét đến bất đẳng thức $x_0 < a$ sẽ dẫn đến mâu thuẫn với đẳng thức (4). Vì vậy, nếu $x_0 < a$ thì $f(x_0) < a$. Từ tính chất (3) của hàm $f$, suy ra bất đẳng thức $f(z) \geq z$ đúng với mọi $z < a$. Do đó, chọn $z = x_0$ đầu tiên và sau đó $z = f(x_0)$, chúng ta có
$$x_0 \leq f(x_0) \leq f(f(x_0)).$$
Sử dụng đẳng thức (4), chúng ta lại kết luận rằng $f(x_0) = x_0$.

Nghe $x_0 = a$ rất rõ ràng. Do đó, trong điều kiện (3), mọi nghiệm của phương trình (1) đều là nghiệm của phương trình (2).

Để kết luận, chúng tôi lưu ý rằng từ một hàm đã cho $f$ rõ ràng người ta cũng có thể xác định được hàm
$$f(f(f(x))), f(f(f(f(x))))), \dots$$
Mệnh đề sau đây đúng (bạn hãy tự chứng minh): nếu hàm $f$ thỏa mãn điều kiện (3), thì mỗi phương trình $f(f(f(x))) = x, f(f(f(f(x)))) = x, \dots$
tương đương với phương trình (2).

Bây giờ chúng ta hãy xem làm thế nào các đề xuất được xây dựng có thể được sử dụng cho lời giải các hệ thống như vậy trong đó tất cả các phương trình đều giống hệt nhau cho đến khi chỉ định các biến và mỗi phương trình chỉ bao gồm hai biến.

Ví dụ 1 (MSU, Cơ học và Toán học, 1977). Tìm tất cả lời giải hệ phương trình
$$\begin{cases} y^3 - 6x^2 + 12x - 8 = 0, \\ z^3 - 6y^2 + 12y - 8 = 0, \\ x^3 - 6z^2 + 12z - 8 = 0. \end{cases}$$

hãy cô lập chức năng
$$f(x) = \sqrt[3]{6x^2 - 12x + 8}, x \in \mathbb{R};$$ (7)

thì hệ này có thể viết lại dưới dạng
$$y = f(x), z = f(y), x = f(z).$$ (8)

Sử dụng phương pháp thay thế, chúng tôi nhận được từ đây
$$f(f(f(x))) = x.$$ (9)

Trước hết, hãy xem xét phương trình $f(x) = x$, hoặc
$$x^3 - 6x^2 + 12x - 8 = 0.$$
Nó có một nghiệm duy nhất $x = 2$ (nhóm vế trái thứ nhất với vế cuối cùng và vế thứ hai với vế thứ ba), cũng là nghiệm của phương trình (9). Từ biểu thức (7) cho hàm $f$ và phương trình (8), chúng ta thu được lời giải của hệ ban đầu:
(2; 2; 2).

Chúng ta hãy kiểm tra xem hàm (7) có thỏa mãn điều kiện (3) đối với $a = 2$ không, và do đó phương trình (9) không có nghiệm nào khác ngoài $x = 2$. Bất bình đẳng $f(x) \geq x$, trong trường hợp này được rút gọn về dạng
$$(x - 2)^3 \leq 0$$
(thực hiện các phép biến đổi cần thiết), thực sự đúng với $x < 2$ và $f(2) = 2$. Hơn nữa, $f(x) \leq x$ đó cho tất cả $x > 2$. Cuối cùng, bất đẳng thức $f(x) \geq 2$ có thể dễ dàng được viết lại dưới dạng
$$6x^2 - 8x \geq 0,$$
từ đó rõ ràng là nó đúng với $x > 2$.

Do đó, hệ thống ban đầu có lời giải (2; 2; 2) duy nhất.

Bài tập
1. Tìm tích phân $f(f(x))$ nếu:
a) $f(x) = \sin x$;
b) $f(x) = \sqrt{1+x^2}$;
c) $f(x) = -x^2 + 1$.

⟦folio 48⟧

2. Xác định hàm $f(f(x))$ nếu $f(x) = -x + 3$.

3. Giải phương trình $f(x) = x$ và $f(f(x)) = x$ nếu:
   a) $f(x) = -x^2 + 1$;
   b) $f(x) = -x + 3$.
   c) $f(x) \leqslant x$ cho tất cả $x \in \mathbb{R}$
   hoặc nếu $f(x) \geqslant x$ cho tất cả $x \in \mathbb{R}$
   thì phương trình $f(f(x)) = x$ có một nghiệm duy nhất $x = a$.
   Giải các hệ phương trình:

6. $\begin{cases} x - 5y = 2y^2 + 2, \\ y - 5z = 2z^2 + 2, \\ z - 5x = 2x^2 + 2. \end{cases}$

7. $\begin{cases} x = \frac{2y^2}{1 + y^2}, \\ y = \frac{2z^2}{1 + z^2}, \\ z = \frac{2x^2}{1 + x^2}. \end{cases}$

8. (MSU, cơ chế, 1977).

9. Đối với một số giá trị $a$, đồ thị của hàm $y = a^x$ và $y = \log_a x$ có ​​thể chạm vào nhau không?

Chúng ta hãy giải thích rằng hai đường cong tiếp xúc nhau nếu chúng có tiếp tuyến chung tại một điểm chung nào đó.

Độc giả của chúng tôi A. Kornilov (Rostov-on-Don) đã gửi một bức thư rất quan trọng cho người biên tập. Ông chỉ ra rằng trong bài báo của Y. Sukonnik và P. Gorshtein “Hình học lời giải hình học bài toán” («Kvant», 1979, Số 9, trang 38) với lời giải bài toán 1 đã xảy ra lỗi máy chủ.

Hãy để chúng tôi nhắc bạn rằng chúng tôi đang nói về bài toán nào.

Ví dụ 2. Một đường tròn ngoại tiếp tam giác AMB có tâm cách cạnh AM một khoảng bằng 10. Phần kéo dài của cạnh AM ngoài đỉnh M cắt nhau tại điểm C và tiếp tuyến với đường tròn này vẽ qua đỉnh B. Tìm diện tích tam giác BMC nếu biết rằng

$$|BC| = 29, \quad \hat{ACB} = \arctg \frac{20}{21}.$$

Điều kiện của hầu hết mọi hình học bài toán không cung cấp định nghĩa, mô tả đầy đủ về loại cấu hình (hình) nghĩa là gì: chỉ một số thuộc tính, đặc điểm hoặc tham số của nó là cố định và phần còn lại không được trình bày chi tiết trong các điều kiện. Nếu các điều kiện bài toán nói đến “tam giác AMB”, thì theo quan điểm logic, tam giác này có thể là tam giác nhọn, hình chữ nhật và tù. Trong hầu hết các trường hợp, ave cho lời giải bài toán không yêu cầu biết các thuộc tính của cấu hình không được chỉ định trong các điều kiện và đáp số đương nhiên không phụ thuộc vào chúng.

Tuy nhiên, trong một số bài toán nghiêm trọng hơn, cần phải bắt đầu từ lời giải bằng việc làm rõ hoặc làm rõ các thuộc tính riêng lẻ của cấu hình, không được chỉ định rõ ràng trong các điều kiện, nhưng được suy luận từ nó bằng lý luận. Giả sử, đối với lời giải bài toán trước tiên chúng ta cần chứng minh rằng tam giác AMB đang nói đến thực sự không thể thiếu. Trong những vấn đề như vậy, điều đặc biệt quan trọng là không được bỏ qua bất kỳ khả năng logic nào và mỗi khả năng đó phải tìm hiểu xem cấu hình tương ứng có tương thích với dữ liệu của điều kiện bài toán hay không.

Tất cả những điều trên áp dụng cho hình cầu ở trên bài toán - đối với lời giải của nó, trước hết, cần trích xuất thông tin bổ sung về hình từ điều kiện, để làm rõ diện mạo của nó. Trong hệ thống được đề cập lời giải, bài toán này về cơ bản bắt đầu bằng chứng minh rằng tam giác AMB không thiếu (mặc dù điều này không được nêu trực tiếp ở đó).

⟦folio 49⟧

Nhưng). Nếu góc AMB là góc vuông thì ta có đáp số:

$$S_{BMC} = 210.$$

Tuy nhiên, điều này không làm cạn kiệt tất cả các khả năng logic về các loại góc của tam giác AMB (hoặc, tương tự, tất cả các vị trí có thể có của tâm của đường tròn ngoại tiếp), và lý luận được đưa ra trong bài viết về cơ bản chỉ dựa trên một hình vẽ so với tam giác nhọn AMB. Đúng, trường hợp

góc MAB thẳng
góc MAB tù,
góc ABM - thẳng,
góc AMB - tù

theo các nguyên tắc khác nhau, các điều kiện bài toán không tương thích với dữ liệu (đưa ra ký hiệu cần thiết). Khả năng cuối cùng vẫn còn: góc ABM tù (Hình 2).

Chúng ta thả đường vuông góc $BM_1$ từ điểm B sang cạnh AM và tiếp tục như vậy cho đến khi nó cắt đường tròn tại điểm $M_2$, rồi chiếu tâm đường tròn O lên các dây AM và $BM_2$. Sau đó, thật dễ dàng để kiểm tra,

$$|BM_1| = |BC| \sin \widehat{ACB} = 20 = 2|OK|,$$
$$|BM_2| = 2(|BM_1| + |M_1L|) = 3|BM_1|;$$

sự tương ứng cuối cùng, không giống như trường hợp tam giác nhọn AMB, không mâu thuẫn với điều kiện bài toán. Nếu bây giờ chúng ta xem xét tuần tự các tam giác $BM_1C$, $BOL$, $OKM$ và nhận thấy rằng $\widehat{OBL} = \widehat{ACB}$, chúng ta sẽ đạt được đáp số (hãy đảm bảo điều này):

$$S_{BMC} = \frac{1}{7}(3470 - 600\sqrt{22}).$$

Trong hình học, người ta thường lập công thức bài toán sao cho đáp số

hóa ra là giống nhau đối với bất kỳ cấu hình nào trong giới hạn sản xuất chấp nhận các điều kiện. Từ quan điểm này, công thức trên của bài toán không thành công: tùy thuộc vào tam giác AMB thẳng hay tù mà thu được đáp số (10) hoặc (11) khác nhau. Để không có sự mơ hồ như vậy, các điều kiện bài toán phải bắt đầu như thế này:

"Gần tam giác không tù AMB...", thì bài toán có một đáp số (10). Tuy nhiên, tác giả bài viết trên đã vô tình lược bỏ từ “không tù túng” trong nội dung điều kiện bài toán.

Nhiều độc giả gửi thư của họ các phương trình đại số khác nhau có bậc trên giây, đối với lời giải mà bạn cần phải “xem” ngay cả việc phân tích nhân tử của đa thức, đôi khi khá phức tạp. Dưới đây là hai phương trình như vậy do học sinh lớp 8 Aleksandr Matveev (Riga) đề xuất:

Giải các phương trình:

10. $x^3 + x^2 - 5x - 6 = 0.$
11. $x^4 - 10x^3 + 24x^2 - 6x - 9 = 0.$

Học sinh nhận thức rõ rằng đối với lời giải bài toán ở cực trị, có một phương pháp phổ quát liên quan đến việc sử dụng đạo hàm. Tuy nhiên, điều này không có nghĩa là trong bất kỳ bài toán nào, phương pháp này là dễ nhất và nhanh nhất để đạt được mục tiêu. Đôi khi tốt hơn là đừng vội phân biệt mà hãy cố gắng tìm hiểu xem liệu có thể tận dụng một số đặc điểm của bê tông được đề cập hay không bài toán.

Đây chính xác là điều mà độc giả của “Kvaent” nhắc nhở chúng ta trong bức thư gửi S. Berkolaiko (làng Kotovo, vùng Belgorod). Ví dụ 3. Tìm diện tích bề mặt bên của hình song song hình chữ nhật $ABCDA_1B_1C_1D_1$, có tổng quát nhất, nếu biết rằng

$$|AC| = 2\sqrt{2}, \quad |AA_1| = 1.$$

⟦folio 50⟧

Vì chiều cao của hình bình hành đã cho nên hình bình hành lớn nhất sẽ có mặt phẳng đáy $ABCD$. Nếu chúng ta biểu thị bằng $x$ độ dài một cạnh của hình chữ nhật $ABCD$ thì $\sqrt{8-x^2}$ là độ dài cạnh kia của hình chữ nhật. Vì vậy, câu hỏi khi nào đáy có diện tích phẳng nhất, chứng tỏ sự vắng mặt của giá trị phẳng nhất của hàm số

$$S(x) = x\sqrt{8-x^2}.$$

Phương pháp tiêu chuẩn lời giải như bài toán bằng cách kiểm tra $S'(x)$ tùy ý yêu cầu một số phép biến đổi và tính toán.

Điều này có thể tránh được nếu bạn thực hiện một cách tiếp cận ít công thức hơn một chút để bài toán tìm hình chữ nhật có diện tích phẳng nhất với độ dài đường chéo cho trước. Chúng ta hãy chọn góc $\alpha$ giữa các đường chéo của hình chữ nhật $ABCD$ làm giá trị biến. thì sẽ thu được biểu thức tính diện tích của nó (kiểm tra!)

$$S(\alpha) = 4\sin \alpha,$$

từ đó có thể thấy ngay, không cần phân biệt, rằng hình vuông có diện tích phẳng nhất ở cạnh có chiều dài 2. Do đó, diện tích bề mặt bên của hình bình hành bằng 8.

* *

Khái niệm giới hạn của dãy là một trong những khái niệm quan trọng nhất trong môn toán ở trường, đồng thời là một trong những khái niệm khó nhất đối với học sinh. Thông thường, học sinh biết giới hạn của một dãy là gì (nghĩa là các em có thể đọc thuộc lòng định nghĩa từ trí nhớ), nhưng không phải ai cũng hiểu đủ sâu về định nghĩa này (tức là các em có thể tự do làm việc với nó). V. Lebedenko (Dubna, vùng Moscow) đã gửi bài toán (phải thừa nhận là khá nổi tiếng) cho người biên tập, lời giải đòi hỏi sự hiểu biết về định nghĩa giới hạn của dãy.

12. Có giới hạn nào cho tính nhất quán không

$$x_n = \sin n?$$

Việc nắm vững các kỹ thuật biến đổi khác nhau có tầm quan trọng hơn trong toán học - không kém ý nghĩa của các định lý khác nhau hoặc khả năng thực hiện suy luận logic. Tuy nhiên, một trong những kỹ thuật này là cộng và trừ một số biểu thức đã chọn đã bị loại bỏ. Đây là điều thường được thực hiện, ví dụ như khi phân tích các đa thức.

Học sinh lớp 9 Avaz Naziev (thôn Minjevan, huyện Zangelan, Azerbaijan Liên Xô) đưa ra ví dụ sau:

Ví dụ 4. Chứng minh rằng nếu hàm $f(x)$ tùy ý tại $x = a$ thì

$$\lim_{x \to a} \frac{xf(a) - af(x)}{x - a} = f(a) - af'(a).$$

Trước khi tính toán các phép biến đổi đại số của biểu thức đã cho (giả sử $x \neq a$):

$$\frac{xf(a) - af(x)}{x - a} = \frac{xf(a) - af(x)}{x - a} - \frac{af(x) - af(a)}{x - a} = f(a) - a \frac{f(x) - f(a)}{x - a}.$$

Từ đây, rõ ràng là giới hạn thực được chỉ ra trong (12) tồn tại nếu $f'(a)$ tồn tại và đẳng thức (12) là hợp lệ.

* *

Chúng tôi cung cấp cho độc giả của tạp chí một lời giải độc lập và hai bài toán khác. Bức đầu tiên được gửi cho chúng tôi bởi học sinh lớp 10 Aladdin Eyvazov (làng Ashurlu, quận Masalli của AzSSR), bức thứ hai do học sinh lớp 10 Andrey Kazarinov (Tolyatti) gửi cho chúng tôi.

13. Giải phương trình

$$3^{\log_2 x} + x^{\log_3 x} = 162.$$

14. Ba đường tròn nằm trong cùng một mặt phẳng sao cho mỗi đường tròn đi qua tâm của hai đường tròn còn lại. Tìm diện tích hình là giao của cả ba hình tròn, biết diện tích giao điểm của cả ba hình tròn là $S$.
