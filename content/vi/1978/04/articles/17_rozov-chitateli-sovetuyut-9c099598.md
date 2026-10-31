---
id: 1978-4-rozov-chitateli-sovetuyut-9c099598
issue: kvant_1978_4
year: 1978
number: "4"
title: Lời khuyên của độc giả
authors:
  - Розов Н. Х.
rubric: praktikum-abiturienta
rubric_sub: Практикум абитуриента
page_first: 50
page_last: 54
page_labels: 48-52
tag: STA6
lang: vi
source: kvant_digital
extraction: vision
content_sha256: 59fbbca49c43f3dbaeeccbcd353dfd214d2a261f9063db06f2832a63dba2f2ec
prompt_sha256: draft-1
translated_from: content/ru/1978/04/articles/17_rozov-chitateli-sovetuyut-9c099598.md
source_content_sha256: 678d4548dc53cce004d7ba8ab3127ea3f784d7f925f2313f43b37b8b6df4dbd0
translation_model: draft
translation_run: vi-draft-2026-10-31
translation_quality: draft
---

⟦folio 48⟧

Lời khuyên của độc giả

Tòa soạn «Kvant» liên tục nhận được thư từ các em học sinh, giáo viên và đơn giản là những người yêu thích toán học về chủ đề của chuyên mục “Thực hành của ứng viên”.
Nhiều người trong số họ đề cập đến các vấn đề từng phần và các biên tập viên sẽ trả lời những bức thư như vậy của chính tác giả. Nhưng trong một số bức thư, các vấn đề lý thuyết khác nhau của khóa học ở trường được thảo luận, các kỹ thuật lời giải thuộc một số loại nhất định bài toán được đề xuất, các nhận xét hữu ích có tính chất phương pháp luận và bài toán thú vị được đưa ra.
Theo chúng tôi, việc giới thiệu cho người đọc «Kvant» nội dung của những bức thư như vậy là rất hữu ích.
Không xét đến việc có thể xuất bản toàn bộ những bức thư như vậy, các biên tập viên quyết định chuẩn bị tuyển chọn các tài liệu được biên soạn theo ý tưởng và gợi ý của các tác giả bức thư, kèm theo những nhận xét bổ sung cần thiết. Chúng tôi hy vọng rằng những câu hỏi nêu ra trong quá trình tuyển chọn sẽ giúp ích cho các ứng viên vào các trường đại học.

Như mọi khi, có rất nhiều thư trong thư xã luận về các hệ và phương trình đại số và lượng giác khác nhau. Cùng với các bài toán tiêu chuẩn không được đặc biệt quan tâm, tác giả của một số bức thư còn đề xuất các phương trình, trong đó lời giải có chứa “niềm say mê” - cần tìm ra một đường biến đổi không chuẩn và chỉ ra cách thay thế thành công cho ẩn số.

Đây là phương trình, ý tưởng lời giải đã được độc giả M. Levin (Tallinn) của chúng tôi báo cáo cho biên tập viên.

Ví dụ 1: Giải phương trình

$$\sqrt{x^2 - 9x + 24} - \sqrt{6x^2 - 59x + 149} = 5 - x.$$ (1)

Người nộp đơn thường bắt đầu lời giải các phương trình vô tỷ bằng cách tìm phạm vi giá trị chấp nhận được của ẩn số. Cần lưu ý rằng thao tác này (đôi khi rất cồng kềnh) không phải lúc nào cũng cần thiết đối với phương trình lời giải. Trong nhiều trường hợp, sẽ có lợi hơn và dễ dàng hơn khi chuyển từ phương trình ban đầu sang hệ quả của nó, và cuối cùng hãy kiểm tra, hoặc thậm chí tốt hơn là chuyển sang các phương trình tương đương.

Rõ ràng là ví dụ tiêu chuẩn về lời giải phương trình vô tỷ - lũy thừa - khi áp dụng cho phương trình (1) sẽ dẫn đến việc tính toán tốn thời gian và không có hy vọng thành công rõ ràng. Vì vậy, hãy thử kiểm tra các phép biến đổi khác.

Vì giá trị $x=5$, rất indo, là nghiệm của phương trình (1), nên khi tìm các nghiệm khác của nó, chúng ta sẽ giả sử rằng $x\neq 5$. Hãy chia cả hai vế của phương trình (1) cho 5 - x:

$$\frac{1}{5-x}\sqrt{x^2 - 9x + 24} - \frac{1}{5-x}\sqrt{6x^2 - 59x + 149} = 1,$$ (2)

và hãy xem điều gì sẽ xảy ra nếu các thừa số: $\frac{1}{5-x}$ được nhập vào dưới dấu căn. Vì, như đã biết từ đại số,

$$a = \sqrt{a^2} \text{ при } a > 0;$$

$$a = -\sqrt{a^2} \text{ при } a < 0,$$

hai trường hợp cần được xem xét riêng: $5-x>0$ và $5-x<0$.

Nếu $5-x>0$, tức là nếu chúng ta tìm nghiệm của phương trình (1) thỏa mãn điều kiện $x<5$, thì phương trình (2) có thể được viết lại thành

$$\sqrt{\frac{x^2 - 9x + 24}{(5-x)^2}} - \sqrt{\frac{6x^2 - 59x + 149}{(5-x)^2}} = 1.$$ (3)

Dưới dấu của gốc đầu tiên, chúng tôi chọn toàn bộ phần:

$$\frac{x^2 - 9x + 24}{(5-x)^2} = \frac{(x^2 - 10x + 25) + (x - 1)}{(5-x)^2} = 1 + \frac{x-1}{(5-x)^2}.$$

⟦folio 49⟧

Tương tự, chúng ta biến đổi phân số dưới dấu căn bậc hai; Do đó phương trình (3) sẽ được viết dưới dạng

$$\sqrt{1 + \frac{x-1}{(5-x)^2}} - \sqrt{6 + \frac{x-1}{(5-x)^2}} = 1.$$

Bây giờ rõ ràng là nên thay thế

$$\frac{x-1}{(5-x)^2} = y,$$

(4)

sau đó còn lại để giải phương trình

$$\sqrt{1+y} - \sqrt{6+y} = 1.$$

Sử dụng phương pháp tổng quát, chúng ta có thể dễ dàng xác minh rằng phương trình này không có nghiệm.

Nếu $5-x<0$, tức là nếu chúng ta tìm nghiệm của phương trình (1) thỏa mãn điều kiện $x>5$, thì phương trình (2), như có thể dễ dàng xác minh, được rút gọn về dạng

$$-\sqrt{1 + \frac{x-1}{(5-x)^2}} + \sqrt{6 + \frac{x-1}{(5-x)^2}} = 1.$$

Sau khi thay (4) ta thu được phương trình

$$\sqrt{6+y} = 1 + \sqrt{1+y},$$

có gốc là $y=3$. Theo (4), giá trị $y$ này tương ứng với $x_1=4$ và $x_2=19/3$. Giá trị $x=4$ nên bị loại bỏ vì không thỏa mãn điều kiện $5-x<0$ và giá trị $x=19/3$ là nghiệm của phương trình ban đầu (1), vì phương trình này tương đương với phương trình (5) trên tập hợp $x>5$. Việc thay thế sau đó cho phép chúng ta tránh được việc kiểm tra không được biểu diễn bằng cách thay thế giá trị đã chỉ định vào phương trình ban đầu.

Vì vậy, phương trình (1) có hai nghiệm: $x_1=5$ và $x_2=19/3$.

Phương trình sau đây trùng khớp (với một phép thay thế đơn giản) với một phương trình tương tự như phương trình trước, được chỉnh sửa bởi độc giả A. Smolykov của chúng tôi (Neftekumsk, Lãnh thổ Stavropol).

1. Giải phương trình

$$\frac{1}{|\cos x|} + \sqrt{6} (\lg x + 1) = 8 \sqrt{\lg x}.$$

\* \*

Năm «Kvant», 1977, số 3, tr. 56-57 thảo luận một cách lời giải của phương trình

$$\sqrt[3]{8x+4} - \sqrt[3]{8x-4} = 2,$$

(6)

người đã sử dụng lập phương của cả hai vế của phương trình. Học sinh lớp 9 Nikolai Kim (trang trại tập thể mang tên Ya. M. Sverdlov, quận Sredne-Chirsky, Liên Xô của Uzbekistan) đã phản hồi ấn phẩm này. Độc giả của chúng tôi đề xuất giải phương trình (6) theo cách khác - bằng cách đưa ra các ẩn số phụ.

Chúng ta hãy giới thiệu các ẩn số phụ $u$ và $v$ như sau:

$$\sqrt[3]{8x+4} = u, \sqrt[3]{8x-4} = v.$$

Khi đó, theo định nghĩa nghiệm và dựa vào đẳng thức (6), ta viết được hệ phương trình

$$u^3 = 8x+4, v^3 = 8x-4, u-v=2,$$

(7) và các ẩn số $u$ và $v$ phải thỏa mãn số không âm có lập phương bằng $a$; xem "Đại số 8", đoạn 24).

Hệ phương trình (7) dễ giải. Trên thực tế, nếu bạn trừ số thứ hai khỏi phương trình đầu tiên: $u^3 - v^3 = 8$, sau đó, sử dụng phương trình thứ ba, loại bỏ, chẳng hạn như $u$, bạn sẽ nhận được phương trình bậc hai $v^2+2v=0$, có nghiệm $v_1=0, v_2=-2$. Sử dụng nghiệm thứ nhất của phương trình thứ hai của hệ (7), chúng ta tìm thấy $x=1/2$; căn thứ hai phải bị loại bỏ do không thỏa mãn điều kiện (8). Do đó, phương trình ban đầu (6) có một nghiệm duy nhất $x=1/2$.

Một người đọc chú ý sẽ dễ dàng nhận thấy rằng phương pháp được đề xuất dựa trên một ý tưởng nổi tiếng và thường được sử dụng - để tìm một sự thay thế thành công cho ẩn số của một phương trình đã cho. Như chúng ta đã thấy, đối với các phương trình vô tỉ lời giải, đôi khi việc đưa ra một số ẩn số bổ trợ sẽ rất thuận tiện.

⟦folio 50⟧

Bây giờ, bạn hãy tự giải một cách chi tiết phương trình vô tỷ sau đây do độc giả A. Aliev (làng Kubra, huyện Lak, Cộng hòa xã hội chủ nghĩa Xô viết tự trị Dagestan) gửi cho người biên tập.

2. Tìm nghiệm nguyên của phương trình

$$\sqrt[3]{24+x} + \sqrt{12-x} = 6.$$

Học sinh đã học rằng các phương trình thường được giải bằng cách chuyển đổi chúng sang dạng “đơn giản nhất” (ví dụ: phương trình bậc hai). Trong khi đó, trên các ví dụ ứng dụng trong toán học, bài toán, lời giải đôi khi được gợi ý, đòi hỏi trước hết phải có khả năng suy luận logic. Trong những bài toán này, theo quy luật, bạn cần phải “nhìn thấy” khả năng sử dụng một số tính chất của một hàm đã biết, áp dụng một bất đẳng thức quen thuộc, v.v. Chính những bài toán như vậy không chỉ kiểm tra ý nghĩa của việc xây dựng các quy tắc và công thức đã học ở trường mà còn cả mức độ phát triển toán học chung của chúng.

Độc giả N. Belevsky (Kharkov) của chúng tôi đã gửi cho người biên tập hai hệ phương trình, tại lời giải trong đó các kết luận logic đóng một vai trò quan trọng.

Ví dụ 2. Giải hệ phương trình

$$\begin{cases} z^2 + 1 = 2\sqrt{xy}, \\ x^2 - 1 = 2yz\sqrt{1-4xy}. \end{cases}$$

Thoạt nhìn, hệ thống này trông khá lạ: có ba ẩn số nhưng chỉ có hai phương trình. Nhưng tình huống này cũng đóng vai trò như một loại "gợi ý" - chúng ta không nên vội vàng biến đổi các phương trình của hệ mà trước tiên hãy cố gắng nghiên cứu các tính chất của chúng.

Nếu phương trình của hệ (9) được viết lại thành $z^2 = 2\sqrt{xy} - 1$, thì vì có biểu thức không âm ở bên trái nên chúng ta có thể kết luận rằng $2\sqrt{xy} - 1 \geq 0$, từ đó

$$1 - 4xy \leq 0.$$

Mặt khác, từ phương trình thứ hai của hệ (9), rõ ràng các giá trị cho phép của các ẩn số $x$ và $y$ phải thỏa mãn bất đẳng thức

$$1 - 4xy \geq 0.$$

So sánh sự tương ứng (10) và (11) cho thấy nghiệm của hệ (9) chỉ có thể là bộ ba số $(x, y, z)$ sao cho $4xy = 1$. Nhưng sau đó từ phương trình đầu tiên của hệ, chúng ta thu được $z = 0$, và từ phương trình thứ hai, nó dẫn đến $x_1 = 1$, $x_2 = -1$.

Như vậy, ta được hai bộ ba số $x_1 = 1$, $y_1 = 1/4$, $z_1 = 0$; $x_2 = -1$, $y_2 = -1/4$, $z_2 = 0$, riêng cái này có thể giải được hệ thống (9). Chúng tôi nhấn mạnh rằng từ các phép tính được thực hiện, không chứng tỏ rằng các bộ ba số tìm được thực sự là nghiệm của hệ (9); thực tế này phải được chứng minh bằng cách thay thế trực tiếp vào hệ thống ban đầu.

Chúng tôi cung cấp hệ thống thứ hai cho người đọc dưới dạng một phương trình.

3. Giải hệ phương trình

$$\begin{cases} xz = y + 2, \\ x + z = 2\sqrt{y}(\sqrt{x} - \sqrt{y} + \sqrt{z}). \end{cases}$$

Đánh giá qua các chữ cái, giáo viên quan tâm nhiều hơn đến việc trộn một phương trình với một tham số, điều này đã được thảo luận trong «Kvant» Số 6, 1977, tr. 71-73. N. Chuliev (Charjuu, Turkmen SSR) thông báo cho các biên tập viên về việc sửa đổi ví dụ này, sử dụng ý tưởng giới thiệu một ẩn số phụ trợ.

Ví dụ 3: Giải phương trình

$$x = a - b(a - bx^2)^2.$$

Phương trình này (có lũy thừa bậc 4 của ẩn số tương đối $x$) rất dễ giải nếu bạn mở dấu ngoặc đơn và nhận thấy rằng một phương trình tốt hơn có thể được coi là phương trình bậc hai $a$. Tuy nhiên, một phương pháp giải tỏa thắc mắc hơi khác một chút cũng dẫn đến mục tiêu.

Hãy giới thiệu ẩn số phụ $z = a - bx^2$. Khi đó, thay vì phương trình (12), bạn cần giải hệ phương trình

$$x = a - bz^2, \quad z = a - bx^2.$$

Trừ phương trình thứ hai khỏi phương trình đầu tiên của hệ, chúng ta thu được các đẳng thức $x = z$, $b(x + z) = 1$; sau khi loại trừ phần phụ chưa biết

⟦folio 51⟧

chúng ta đi đến hai phương trình:
$$x = a - bx^2; \quad b(x + a - bx^2) = 1.$$

Hơn nữa lời giải rất indo. Bạn chỉ cần nhớ rằng giải pháp là về các phương trình có tham số và nó tuân thủ cẩn thận các điều kiện để phép tính hợp lệ trên các tham số. đáp số cuối cùng sẽ trông như thế này:
nếu $ab < -1/4$ thì không có gốc;
nếu $ab = -1/4$ thì có một gốc: $x = -1/2b$;
nếu $-1/4 < ab < 0$ thì có hai nghiệm:
$$x_1 = \frac{-1 - \sqrt{1 + 4ab}}{2b} \quad \text{и}$$
$$x_2 = \frac{-1 + \sqrt{1 + 4ab}}{2b};$$
nếu $b = 0$ thì có một gốc: $x = a$;
nếu $a = 0$ nhưng $b \neq 0$ thì có hai nghiệm: $x = 0$ và $x = -1/2$;
nếu $0 < ab < 3/4$ thì có hai nghiệm: $x_1$ và $x_2$;
nếu $ab = 3/4$ thì có ba nghiệm: $x_1, x_2$ và $x = 1/2b$;
nếu $ab > 3/4$ thì có bốn nghiệm: $x_1, x_2,$
$$x_3 = \frac{1 - \sqrt{4ab - 3}}{2b} \quad \text{и}$$
$$x_4 = \frac{1 + \sqrt{4ab - 3}}{2b}.$$

Tất nhiên, các thông báo trên cũng áp dụng trong trường hợp phương trình đang xét không chứa bất kỳ tham số nào.

Ví dụ 4: Giải phương trình
$$x^2 + \sqrt{x + 5} = 5.$$

Đối với lời giải của phương trình này, thuận tiện là đưa vào ẩn số phụ $z = \sqrt{x + 5}$ và chuyển sang hệ phương trình $x^2 + z = 5, x + 5 = z^2$. Sau khi ước lượng các phép biến đổi ta thu được hai phương trình vô tỉ
$$\sqrt{x + 5} + x = 0; \sqrt{x + 5} = x + 1,$$
từ đó ta thu được hai nghiệm của phương trình (13):
$$x_1 = \frac{1 - \sqrt{21}}{2}, \quad x_2 = \frac{\sqrt{17} - 1}{2}.$$

Trong số các phương trình được độc giả gửi đến Shimich, có nhiều phương trình được giải bằng phương pháp nhân tử hóa. Tuy nhiên, không phải lúc nào cũng dễ dàng “nhìn thấy” việc phân nhóm dẫn đến kết quả mong muốn. Phương trình đầu tiên dưới đây được đề xuất bởi A. Ermilov (Kolomna, vùng Moscow), hai phương trình tiếp theo của L. Slukin (Lipetsk), và phương trình cuối cùng, khó nhất, của học sinh lớp 10 Seidazim Mirtsev (làng Khilly, vùng Neftechala, Azerbaijan Liên Xô).

Giải phương trình:
4. $$\frac{x^2}{\sqrt{3x - 2}} - \sqrt{3x - 2} = 1 - x.$$
5. $x^2 + \frac{1}{x} - 2 = 0.$
6. $x^4 + 4x^3 + 3x^2 + 2x - 1 = 0.$
7. $x^4 - 12x - 5 = 0.$

Người ta biết rằng bài toán hình học, trong đó các phép tính dài và rườm rà dẫn đến mục tiêu, đôi khi có thể được giải chỉ trong vài dòng. Để làm điều này, bạn chỉ cần chọn một “chìa khóa” cho bài toán—đoán cách áp dụng một định lý nhất định, xem cấu trúc bổ sung và có thể tận dụng các chi tiết cụ thể của cấu hình. Bạn nên tìm hiểu kỹ về một giải pháp độc đáo như vậy, mặc dù trước tiên bạn nên tự mình thử nó sẽ hữu ích hơn nhiều. Tìm nó (và sẽ có quá trình thu thập thông tin ngay cả khi việc tìm kiếm vẫn hoàn hảo).

Nhiều độc giả của tạp chí đã tỏ ra thích thú với đề xuất được đưa ra trong “Hội thảo dành cho người nộp đơn” nhằm gửi cho biên tập viên bản lời giải bài toán ngắn và màu đỏ được đưa ra trong kỳ thi tuyển sinh. Một số bài toán tương tự được đặt bên dưới. Chúng có thể được giải mà không cần “trí tưởng tượng hình học” (sau khi hình thành bài toán, nó được chỉ ra ở đâu lời giải cũng được xuất bản). Chúng tôi mời những người nộp đơn tìm lời giải trong số bài toán này mà không yêu cầu tính toán rườm rà. lời giải như vậy đối với ba bài toán đầu tiên đã được P. Gorshitey (Kyiv) báo cáo cho chúng tôi; lời giải trong số bài toán tiếp theo được chỉ định bởi Y. Aizenites (Kyiv).

8. Trong hình bình hành $ABCD$ góc tại đỉnh $A$ bằng $\alpha < \pi/2$. Chiều cao giảm từ đỉnh $B$ sang cạnh $AD$ chia đường chéo $AC$ theo tỷ lệ $m:n$. Tìm tỉ số độ dài các cạnh của hình bình hành.

⟦folio 52⟧

(Shakhno K.U., Cách chuẩn bị cho kỳ thi tuyển sinh đại học môn toán, Minsk, “Trường trung học”, 1970, bài toán 423.)

9. Trên hai cạnh liền kề của hình vuông, làm đường kính, hai hình bán nguyệt được dựng, nằm trong một hình vuông, trên mỗi hình bán nguyệt vẽ một hình tứ giác, song song với cạnh hình vuông là đường kính của hình bán nguyệt này. Tìm độ dài bán kính của hình tròn, hình ảnh bên ngoài của các quadoceros của các hình bán nguyệt này và các quadoceros được tạo bởi tứ giác. (Shakhno K.U. “Bộ sưu tập bài toán về toán tiểu học với độ khó tăng dần”, Minsk, “Trường trung học”, 1969, bài toán 932.)

10. Hai chân [AB] và [AC] của một tam giác vuông lần lượt nằm ở các mặt P và Q tại góc nhị diện nhọn có độ lớn φ. Chân [AB] tạo thành một góc nhọn α với cạnh của góc nhị diện. Xác định góc giữa cạnh này và chân [AC]. («Kvant», 1976, số 2, trang 58 và số 3, trang 76.)

11. Một tam giác đều nội tiếp một hình cầu có bán kính có chiều dài R.

(Phần đầu xem trang 21, 38)

(N. Dvor, vùng Grodno) 46, 51, 54, 56, 60a); I. Savenkov (Dãy núi Hói, vùng Saratov) 54; V. Skovin (Mì ống) 50; M. Sevriok (Moscow) 56, 58; A. Semov (Chelyabinsk) 54; P. Serdore (p/n Anna, vùng Voronezh) 56; A. Sivatsky (Leningrad) 47, 50, 51; V. Sidorenko (Krasnoisk) 51, 54, 56; P. Silvestrov (Novosibirsk) 48; O. Slavyansky (Leningrad) 47; Yu. Smirnov (Leningrad) 46-48, 50, 51, 53-55; A. Starkov (Moscow) 46, 47; V. Stovba (Moscow) 46, 48, 51, 52, 55—57, 59; F. Sukachev (Tashkent) 54; K. Tamalyan (Yerevan) 51, 53, 54; Z. Tleshov (Alma-Ata) 52, 54; V. Trofimov (Moscow) 46, 48, 50-58; K. Trumnev (Kazan) 51, 57; G. Tyurin (Kursk) 46; A. Udavixin (Ioshkar-Ola) 46; V. Falko (Kharkov) 46; N. Fedin (Omsk) 47, 52, 54, 56; Y. Fedorov (Leningrad) 51, 57; G. Firsova (Leningrad) 52, 54; I. Fomenko (Dnepropetrovsk) 49a); M. Khaimov (Voronezh) 50; I. Hangl (Tiệp Khắc) 58; S. Khosid (Almaty) 54; M. Chereninsky (Voronezh) 47, 48, 60a), 6); D. Shafer (Leningrad) 56; V. Shenkarb (Kyiv) 54; A. Shilo (Kivertsy) 54; A. Shikhakhmedov (Derbent) 54; I. Shlyakhova (Lobnya) 54; D. Shulbaev (Alma-Ata) 46—48, 52, 54, 57, 60a), 6); A. Shulevov (Kamensk Uralsky) 51.

Vật lý

Hầu hết tất cả độc giả đã gửi lời giải bài toán F. Azakshev (làng Zarat AzSSR) 51; K. Hakobyan (Yerevan) 52; E. Alexandrova (Glazov) 55; M. Alekseev (Obninsk) 52; E. Alisenderov (làng Dash Salahli AzSSR) 52; A. Antonyan (Yerevan) 60; A. Arbatsky (Blagoveshchensk, vùng Amur) 50; A. Bakan (Kyiv) 51; S. Bavkun (Cherkesck) 51, 52, 62; Yu. Balashov (Moscow) 60, 61; A. Baruev (Ulan-Ude) 53, 57; A. Barzikin (tr.
