---
id: 1973-1-ryivkin-formalizatsiya-usloviy-zadach-a32e792a
issue: kvant_1973_1
year: 1973
number: "1"
title: Chính thức hóa các điều kiện bài toán
authors:
  - Рывкин А. А.
rubric: praktikum-abiturienta
rubric_sub: Практикум абитуриента
page_first: 37
page_last: 41
page_labels: 35, 36, 38, 39
tag: BN3N
lang: vi
source: kvant_digital
extraction: vision
content_sha256: 63b99cfbbcc74eed4b9e92a6208ebb7eabfff9eda23454bcab9a9f75503d272f
prompt_sha256: draft-1
translated_from: content/ru/1973/01/articles/12_ryivkin-formalizatsiya-usloviy-zadach-a32e792a.md
source_content_sha256: c816f5dd5cb94867e38095187c52008fa24d9a35176b1ad4d1b5f653c88e07de
translation_model: draft
translation_run: vi-draft-2026-10-31
translation_quality: draft
---

⟦folio 35⟧

Chính thức hóa các điều kiện bài toán

A. A. Ryvkin

Khi những người có cuộc sống xoay quanh toán học nhớ đến trường học, họ vô tình nghĩ đến những chuyến tàu đi từ điểm A đến điểm B, và những bể bơi nơi nước được đổ vào bằng lao động này và đổ ra qua lao động khác. Tuy giống nhau bài toán có rất ít điểm chung với toán học asiomatic “thực sự” đó, tiêu chuẩn của nó trong nhiều thế kỷ đã là hình học cơ bản; khả năng giải một cách khéo léo là một trong những tiêu chí không thể thiếu để đánh giá trình độ chuẩn bị môn toán của đa số thí sinh.

Rõ ràng, sức sống của những văn bản bài toán như vậy nằm ở vai trò của logic trong chúng, vốn có trong bất kỳ nghiên cứu ứng dụng nghiêm ngặt nào.

Ngày nay, toán học ngày càng sử dụng thành công hơn cho lời giải những bài toán cụ thể như vậy (cả thuần túy thực tế và những thứ nảy sinh trong các ngành khoa học khác), đòi hỏi một cách tiếp cận phi tiêu chuẩn riêng khi định dạng chúng.

Khi gặp một vấn đề như vậy, trước tiên, một nhà toán học cố gắng diễn đạt nó bằng từ ngữ, nghĩa là xây dựng một mô hình bằng lời nói phản ánh tất cả các khía cạnh thiết yếu của hiện tượng và bỏ qua những khía cạnh thứ yếu. Sau đó mô hình ngôn từ này sẽ được trình bày để định dạng, hoặc xây dựng mô hình toán học của đối tượng đang nghiên cứu. Một mặt, mô hình chính thức phải đơn giản một cách chính xác để cho phép phân tích toán học sâu hơn, mặt khác, nó phải hiệu quả - nó phải đáp ứng mục đích mà nó được thiết kế.

Mô hình được xây dựng theo cách này có thể được nghiên cứu bằng một số phương tiện toán học. Thông thường, nó hóa ra là một hệ thống điều khiển và mục tiêu đạt được nhờ lời giải của nó. Trong các trường hợp khác, hệ thống bao gồm các điều khiển và ràng buộc. Thông thường, các điều kiện bài toán chứa một số tiêu chí chất lượng cho phép người ta chọn “tốt nhất” từ tập hợp các hệ thống lời giải có ​​thể. Người ta nghe nói rằng ở giai đoạn cuối lời giải của hệ thống, sự không nhất quán của mô hình với mục tiêu nghiên cứu đã bộc lộ. Sau đó, bạn phải quay lại giai đoạn đầu tiên và bắt đầu lại từ đầu.

Văn bản bài toán mà thí sinh gặp phải trong kỳ thi là mô hình lời nói của một số tiêu chí bài toán. Hãy để bài toán này không phải lúc nào cũng hoàn toàn thực tế về nội dung của nó, hãy cho mọi người biết trước rằng nó ít nhiều có một lời giải đơn giản. Logic của việc hình thức hóa và các giai đoạn còn lại của nghiên cứu toán ứng dụng nhất thiết phải có trong đó.

Giờ đây, tin nhắn bài toán đã bắt đầu xuất hiện, khiến các ứng viên gặp phải những vấn đề họ sẽ phải đối mặt sau khi vào đại học. Ví dụ, vào năm 1968, những người nộp đơn vào Khoa Kinh tế CyberNETKI của Khoa Kinh tế của Đại học Quốc gia Moscow đã được cung cấp bài toán sau đây.

Bài toán 1. Nhà máy phải gửi đơn đặt hàng 1100 bộ phận. Các bộ phận vận chuyển được đóng gói trong hộp. Hộp ba phút có sẵn. Một hộp loại thứ nhất có 70 phần, một hộp loại thứ hai có 40 phần và một hộp loại thứ ba có 25 phần. Chi phí gửi một hộp loại thứ nhất, thứ hai và thứ ba là 20, 10 và 7 rúp. Bạn nên sử dụng những hộp nào?

⟦folio 36⟧

nhà máy sao cho chi phí vận chuyển là tối thiểu? Hộp rẻ tiền không được phép.

Người đọc quen với việc giải văn bản bài toán sẽ dễ dàng viết ra các công thức nối tương ứng. Nếu chúng ta biểu thị bằng $x_1, x_2$ và $x_3$ số hộp chứa 70, 40 và 25 phần tương ứng thì

$$70 x_1 + 40 x_2 + 25 x_3 = 1100,$$

vì theo các điều kiện, không được phép chất quá tải các hộp. Các giá trị $x_1, x_2$ và $x_3$ phải được chọn sao cho chi phí vận chuyển

$$20 \times 70 x_1 + 10 \times 40 x_2 + 7 \times 25 x_3$$

là nhỏ nhất.

Thật không may, cách biểu diễn công thức của các điều kiện bài toán không giúp chúng ta nhiều trong việc tìm ra lời giải của nó. Sẽ hữu ích hơn nếu Goraddo tưởng tượng mình ở vị trí của nhân viên kiểm tra được giao nhiệm vụ chuyển trường này. Điều đầu tiên anh ta sẽ chú ý đến là chi phí vận chuyển một bộ phận cho mỗi lựa chọn trong số ba lựa chọn.

So sánh các số $\frac{20}{70}, \frac{10}{40}$ và $\frac{7}{25}$ hoặc sau khi giảm về một giá trị chung $\frac{200}{700}, \frac{175}{700}$ và $\frac{196}{700}$, anh ta sẽ nhận thấy rằng vận chuyển rẻ nhất là theo bộ 40 phần và đắt nhất là theo bộ 70 phần. Vì 1100 không chia hết cho 40 nên khách truy cập sẽ không chỉ được hưởng lợi từ những bộ có lợi nhất. Để mất ít nhất có thể, anh ta sẽ dần dần từ chối các điều kiện có lợi nhất, nghĩa là xem xét trường hợp khi số lượng bộ phận tối đa có thể được đóng vào hộp 40 phần: 1080, 1040, 1000, 960, v.v. Trong trường hợp đầu tiên, 20 bộ phận sẽ vẫn chưa được đóng gói, và trong trường hợp thứ hai - 60 bộ phận. Họ không thể tải các hộp có 25 bộ phận mỗi hộp, ít hơn 70 bộ phận. Trường hợp thứ ba khá chấp nhận được: giả sử rằng 25 hộp, mỗi hộp 40 phần ($25 \times 40 = 1000$) và 4 hộp, mỗi hộp 25 phần, sẽ được sử dụng để đóng gói. Bất kỳ lựa chọn nào khác sẽ dẫn đến chi phí lớn hơn, vì số lượng bộ dụng cụ có lợi nhất sẽ giảm do số lượng bộ dụng cụ ít lợi nhuận hơn (25 bộ phận mỗi hộp) tăng lên hoặc do sự xuất hiện của bộ dụng cụ có lợi nhất (mỗi bộ 70 bộ phận), hoàn toàn không được sử dụng trong tùy chọn mà chúng tôi tìm thấy.

Chúng tôi thấy rằng với lời giải ý thức chung bài toán này hóa ra lại hữu ích hơn nhiều so với toán học hình thức. Nhưng đối với bài toán từ một phiên bản khác cùng năm, làm ơn, chỉ ý thức chung thôi là chưa đủ.

Nhiệm vụ 2. Các nhóm nhạc sĩ của Chemyr đã thực hiện một chuyến đi bộ đường dài vào Chủ nhật qua một số cây thủy sinh có độ dài khác nhau. Tổng số khảo sát được thực hiện bởi nhóm thứ nhất và quý cộng lại lớn hơn 6 km so với tổng số khảo sát được thực hiện bởi nhóm thứ hai và thứ ba. Nhóm thứ hai rơi ít hơn nhóm thứ nhất 2 km. Số lượng nhạc sĩ của nhóm thứ ba bằng khoảng cách (tính bằng km) mà nhóm thứ nhất đi được, và số lượng nhạc sĩ của nhóm thứ hai bằng khoảng cách mà nhóm thứ tư đi được, bằng 494 km2. Hỏi mỗi nhóm đã đi được bao nhiêu km?

Như trong bài toán trước, hãy bắt đầu bằng cách định dạng điều kiện. Nếu số nhóm $i$ đi được $x_i$ km thì

$$\begin{cases} x_1 + x_4 = x_2 + x_3 + 6, \\ x_1 = x_2 + 2, \\ x_1^2 + x_2^2 + x_3^2 + x_4^2 = 494. \end{cases}$$

Ta thu được hệ phương trình có 4 ẩn số. Đúng, các điều kiện vẫn chưa được sử dụng, do đó $x_1$ bằng số lượng khách du lịch của nhóm thứ ba và $x_4$ bằng số lượng khách du lịch của nhóm thứ hai. Lúc đầu, những dữ liệu bài toán này gây ra sự hoang mang, và một trò đùa trẻ con bài toán hiện lên trong đầu, kết thúc những câu hỏi không liên quan đến làng cũng như thành phố.

⟦folio 38⟧

Đổ đầy bình thứ nhất và ống thứ hai liệu nó có mang lại kết quả tính toán là 5% axit không? Để ghi lại sự kiện bể đã được đổ đầy nước, chúng ta cần biết thời gian hai ống này hoạt động. Nó bằng $\frac{1}{x_1+x_2}$. Trong thời gian này, người ta đã nhận được $\frac{qx_1}{x_1+x_2}$ axit đậm đặc, chiếm 5% thể tích bằng một:

$$\frac{qx_1}{x_1+x_2} = 0,05.$$

Trong trường hợp thứ hai, hồ chứa được bổ sung trước khi nó đầy. Lượng axit đậm đặc hóa ra bằng $\frac{qx_1}{2(x_1+x_2)}$.

Sau đó, nó chỉ được bổ sung bằng ống thứ hai, qua đó axit nồng độ $q$ chảy qua. Do đó, có tổng cộng $\frac{qx_1}{2(x_1+x_2)} + \frac{q}{2}$ axit đậm đặc trong bể. Vì vậy, chúng ta thu được phương trình thứ hai:

$$\frac{qx_1}{2(x_1+x_2)} + \frac{q}{2} = 0,1.$$

Giải hệ phương trình thu được, ta thấy đường ống dẫn nước chảy qua có công suất thông lượng gấp đôi so với đường ống dẫn axit chảy qua.

Mặc dù bài toán lời giải khá nhanh nhưng quá trình lập phương trình đòi hỏi nhiều phép tính logic khó hơn mức cần thiết.

Chúng ta nên chú ý ngay đến thực tế là bản thân hồ chứa không đóng bất kỳ vai trò nào trong các điều kiện của vấn đề, và do đó chúng ta đã chọn “lõi” bài toán không chính xác. Trong cả trường hợp thứ nhất và thứ hai, các điều kiện nói lên dòng chất lỏng chứ không phải trữ lượng của nó. Nếu nước sạch và dung dịch axit có nồng độ không đổi bắt đầu chảy vào bể qua hai đường ống cùng lúc, thì sẽ thu được dung dịch axit 5% không chỉ sau khi bổ sung. Tại mỗi thời điểm, do sự chuyển động của hai chất lỏng đi vào bể chứa, thu được hỗn hợp có nồng độ 5%. Bây giờ chúng ta lấy dung tích của đường ống mà axit chảy qua là một và biểu thị dung tích của đường ống kia là $p$ (chúng ta phải xác định $p$ theo điều kiện bài toán). Giả sử, như trước đây, nồng độ axit đi qua ống thứ nhất bằng $q$. Quá trình trộn có thể được mô tả bằng một phương trình đơn giản:

$$\frac{q}{p+1} = 0,05$$

(trong một đơn vị thời gian, một lượng chất lỏng bằng $p+1$ đi vào bể, và axit đậm đặc trong chất lỏng này sẽ là $q$).

Phần thứ hai bài toán hiện được xây dựng lại như sau: bằng cách trộn hai thể tích axit giống hệt nhau, một thể tích có nồng độ 0,05 và thể tích còn lại $q$, thu được dung dịch có nồng độ 0,1:

$$\frac{0,05+q}{2} = 0,1.$$

Lời giải các phương trình thu được có vẻ không khó.

Trong bài toán này, việc lựa chọn một con đường ít hợp lý hơn để hình thức hóa nó không phải là điều kiện thực tế cho quá trình lời giải của hệ phương trình thu được. Tuy nhiên, trong cùng một vấn đề về nồng độ bài toán có ​​thể chỉ phát sinh do một phương trình không thành công đã được chọn bằng cách soạn phương trình. Ví dụ: hãy xem bài toán, được đưa ra nhiều lần trong các kỳ thi (Cơ học và Toán học, 1962, Kiberetic kinh tế, 1965).

Nhiệm vụ 4. Từ một bình đầy chứa 729 lít axit nguyên chất, người ta đã đổ một lít và một gallon nước. Sau khi di chuyển hoàn toàn (cho đến khi thu được độ nổ đồng nhất), một lít dung dịch lại được đổ ra khỏi bể, một bể nước lại được thêm vào và bể được di chuyển cẩn thận. Sau khi thực hiện thao tác nhúng sáu lần, chất lỏng trong bể

⟦folio 39⟧

chứa 64 lít axit nguyên chất. Xác định các giá trị của $a$.

Trong các điều kiện, điểm nhấn mạnh là sau khi lặp lại thao tác sáu lần, vẫn còn 64 lít axit nguyên chất trong bể. Thông thường, những điều kiện này làm cơ sở để lập phương trình.

Tuy nhiên, bài toán có thể giải dễ dàng hơn nếu chọn nồng độ dung dịch thay vì thể tích làm cơ sở để xây dựng phương trình. bài toán tương tự được gọi là bài toán cho sự tập trung, vì chính sự hấp dẫn đối với sự tập trung đã cho phép chúng ta có được ký hiệu công thức thuận tiện nhất cho điều kiện. Chúng ta hãy biểu thị bằng $q_1, q_2, \dots$ nồng độ axit trong lò nướng sau hoạt động thứ nhất, thứ hai,.... Rõ ràng là

$$q_1 = \frac{729 - a}{729}, \quad q_2 = q_1 \frac{729 - a}{729}, \dots,$$

$$q_6 = q_5 \frac{729 - a}{729}.$$

Trên thực tế, nếu trước hoạt động thứ $(i + 1)$, nồng độ axit là $q_i$, thì $q_i$ lít axit nguyên chất đã được loại bỏ khỏi bể, sau đó vẫn còn lại $q_i (729 - a)$ lít axit nguyên chất trong đó. Như vậy,

$$q_{i+1} = q_i \frac{729 - a}{729}.$$

Vì vậy, nồng độ $q_i$ tạo thành một cấp số nhân với giá trị $\frac{729 - a}{729}$. Vì nồng độ $q_6$ bằng $\frac{64}{729}$ theo điều kiện nên ta thu được phương trình

$$\left( \frac{729 - a}{729} \right)^6 = \frac{64}{729},$$

tức là, $\frac{729 - a}{729} = \frac{2}{3}$,

từ đâu $a = 243$.

Bây giờ chuyển sang bài tập. Hãy dành thời gian để xem xét lời giải ngay cả khi bài toán có vẻ không khó đối với bạn và bạn chỉ muốn kiểm tra tính đúng đắn trong quá trình suy nghĩ của mình. Mang bài toán đến đáp số, thực hiện nó một cách bề ngoài và cẩn thận, và chỉ sau đó mới đọc lời giải. So sánh cách tiếp cận của bạn với cách tiếp cận được đề xuất ở cuối vấn đề.

Bài tập

1. (Khoa Kinh tế, Đại học Tổng hợp Matxcova, 1968). Dự kiến ​​​​sẽ sử dụng 2000 rúp. trên đường chia nhà. Voucher có thời hạn 15, 27 và 45 ngày; giá của chúng lần lượt là 21, 40 và 60 rúp. Bạn cần mua bao nhiêu và loại voucher nào để tối đa hóa tổng số ngày nghỉ?

2. (Khoa Hóa học, Đại học Tổng hợp Matxcova, 1969). Bình thứ nhất có dung tích 6 lít chứa 4 lít dung dịch axit sunfuric 70%; Đổ 3 lít dung dịch axit sunfuric 90% (có nghĩa là hàm lượng thể tích) vào bình thứ hai trong cùng một bình chứa. Phải đổ bao nhiêu lít dung dịch từ bình thứ hai sang bình thứ nhất để thu được dung dịch $r\%$ axit sunfuric trong bình thứ nhất? Tìm tất cả các giá trị của $r$ mà bài toán có ​​lời giải.

3. (Khoa Hóa học, Đại học quốc gia Mátxcơva, 1970). Hai ống khi hoạt động cung cấp 100 lít chất lỏng mỗi phút cho bể. Có hai dung dịch axit - mạnh và yếu. Nếu trộn 10 lít mỗi dung dịch với 20 lít nước sẽ được 40 lít dung dịch 20%. Người ta cũng biết rằng nếu trong một giờ, dung dịch yếu được đưa vào bể ban đầu trống qua ống thứ nhất và dung dịch mạnh qua ống thứ hai, bạn sẽ nhận được dung dịch axit 30%. Axit sẽ thu được nồng độ bao nhiêu (tính bằng%) nếu cho dung dịch mạnh vào bình rỗng ban đầu trong một giờ qua ống thứ nhất và dung dịch yếu qua ống thứ hai? (Người ta tin rằng khi trộn nước và axit thì thể tích không thay đổi.)

4. (Khoa Ngữ văn, Đại học quốc gia Mátxcơva, 1970). Hồ chứa được cung cấp nước thông qua năm đường ống. Vòi đầu tiên đầy bể trong 40 phút, vòi thứ hai và thứ tư trong 10 phút, vòi thứ ba và thứ năm trong 20 phút, cuối cùng là vòi thứ tư và thứ năm trong 30 phút. Khi làm việc cùng một lúc thì mất bao lâu để đổ đầy bình?

5. Bình chứa dung dịch axit thứ $p\%$-th phải được đổ đầy dung dịch axit thứ $q\%$-th và sau khi trộn, lượng tương tự được phân phối. Sau khi bán hoạt động này $k$ lần, chúng tôi đã nhận được giải pháp $r\%$. Dung dịch ban đầu chiếm bao nhiêu phần thể tích của bình?
