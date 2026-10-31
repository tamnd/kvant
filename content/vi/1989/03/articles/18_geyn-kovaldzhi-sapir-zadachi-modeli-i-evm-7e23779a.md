---
id: 1989-3-geyn-kovaldzhi-sapir-zadachi-modeli-i-evm-7e23779a
issue: kvant_1989_3
year: 1989
number: "3"
title: Bài toán mô hình và máy tính
authors:
  - Гейн А. Г.
  - Ковальджи А. К.
  - Сапир М. В.
rubric: raznoe
rubric_sub: Разное
page_first: 61
page_last: 66
page_labels: 59-64
tag: RMQH
lang: vi
source: kvant_digital
extraction: vision
content_sha256: b06c0792cdad4dd9c6d683398a59ba4dc7e5de537b9f9cd760db29ebf5e40671
prompt_sha256: draft-1
translated_from: content/ru/1989/03/articles/18_geyn-kovaldzhi-sapir-zadachi-modeli-i-evm-7e23779a.md
source_content_sha256: 3a2a0542171a9703e8ca3d6a145cbcabade652f479cb64ada31e2f766aac173d
translation_model: draft
translation_run: vi-draft-2026-10-31
translation_quality: draft
---

⟦folio 59⟧

Bài toán, mô hình và máy tính

Ứng viên Khoa học Vật lý và Toán học
A. G. GEIN,
A. K. KOVALDZHI,
Ứng viên Khoa học Vật lý và Toán học
M. V. SAPIR

Chắc hẳn tất cả độc giả «Kvant» đều biết rằng máy tính có tốc độ đếm tuyệt vời, giải phóng chúng ta khỏi những phép tính rườm rà và tẻ nhạt. Đồng thời, bạn liên tục nghe về việc máy tính được sử dụng để tùy ý và quản lý sản xuất, để vẽ phim hoạt hình và tìm kiếm người đại diện, tức là cho lời giải bài toán, với các phép tính dường như không liên quan. Cái này hoạt động thế nào? Rốt cuộc ở đây rõ ràng có mâu thuẫn! Và thực sự đó là một sự mâu thuẫn. Thiên Bình không dễ vượt qua. Cách sử dụng máy tính cho lời giải không tính toán bài toán sẽ được thảo luận trong một loạt bài viết bắt đầu trong số này «Kvant».

Hãy nhớ rằng, trong bài thơ của N.A. Nekrasov có mô tả cách tập hợp những người đàn ông ở các làng xung quanh để thảo luận xem ai sẽ sống tốt ở Rus'? Trong những lúc rảnh rỗi đó, họ không thể làm gì để cuộc sống của mình dễ dàng hơn: mọi vấn đề xã hội đều do gia đình quyết định. Giờ đây, không một vấn đề xã hội nào có thể được giải quyết mà không cần thảo luận rộng rãi. Đây là một trong những bài toán mà cơ quan lập kế hoạch thường sử dụng.

Vấn đề. Một số khu định cư nằm trong một chế độ ăn kiêng. Một tuyến đường sắt chạy qua khu vực. Khi khu vực này trở nên sôi động, người ta có kế hoạch xây dựng một nhà ga và mở rộng đường từ đó đến từng khu định cư. Cần xác định vị trí thuận tiện nhất của nhà ga.

hình 1 hiển thị bản đồ của khu vực (chúng tôi giữ lại tên làng Nekrasov). Hãy tưởng tượng rằng bạn đang làm việc như một chương trình

⟦folio 60⟧

trong ủy ban điều hành quận và bạn được hướng dẫn giải quyết vấn đề này bài toán bằng cách sử dụng dịch vụ của máy tính. Điều gì là cần thiết cho việc này? Trước hết, bạn cần nhớ: máy tính không thể làm gì khác ngoài việc thực hiện các hướng dẫn và thuật toán của bạn và chỉ khi chúng được xây dựng bằng ngôn ngữ mà nó hiểu được. Và để soạn một thuật toán, bạn cần biết cái gì đã cho, cái gì cần lấy, dữ liệu ban đầu và kết quả có liên quan như thế nào cũng như những lệnh nào có thể được sử dụng. Nói cách khác, bài toán phải được xây dựng rõ ràng.

Hãy tạm gác đường sắt bài toán của chúng ta sang một bên và nói về việc sản xuất bài toán.

Sản phẩm bài toán

Chỉ trong các nhiệm vụ ở trường, người ta mới hiểu rõ ngay những gì được cho và những gì cần phải nhận. Mọi thứ trong cuộc sống phức tạp hơn. Kinh nghiệm thực sự hét lên về mức độ khó của việc đặt chính xác bài toán: không tha thứ quá mức và không thêm lại, không bỏ sót dữ liệu ban đầu quan trọng và không bao gồm những dữ liệu không cần thiết, cân bằng sắt với những gì có thể.

Giả sử bạn đã quyết định, với tư cách là một hoạt động lao động cá nhân, tổ chức một văn phòng trao đổi căn hộ. bài toán của bạn - đối với mỗi đơn đăng ký nhận được, hãy chọn một tùy chọn trao đổi đáp ứng tất cả các bên quan tâm. Hãy cố gắng trình bày điều này bài toán một cách rõ ràng. Nhiều câu hỏi ngay lập tức được đặt ra: những thông số nào về không gian sống sẵn có và cần thiết cần được tính đến trong ứng dụng (số lượng và diện tích của phòng, vị trí tương đối của chúng, diện tích nhà bếp và các phòng tiện ích khác, năm xây nhà, tầng, có thang máy, khoảng cách từ trung tâm thành phố, v.v.)? Bạn có chấp nhận yêu cầu ăn trưa và trao đổi căn hộ không? Có nên tính đến chi phí của một căn hộ hợp tác?

Hoặc bài toán khác: lập lịch học ở trường. Đầu vào cho bài toán này là gì? Tất nhiên, điều này phụ thuộc vào yêu cầu lập kế hoạch. Yêu cầu hai bài học khác nhau không diễn ra cùng lúc trong cùng một lớp? Khi đó sẽ có rất ít dữ liệu ban đầu: một danh sách các môn học giáo dục cho các cấp lớp trong mỗi song song. Tuy nhiên, cùng lúc đó, có thể lớp này chỉ dạy môn toán, lớp khác chỉ dạy địa lý, và một giáo viên dạy văn khó có thể hài lòng nếu được giao dạy các bài vật lý. Cố gắng hình thành rõ ràng bài toán việc tự mình lập thời khóa biểu ở trường. Chúng tôi nghĩ rằng sau này các bạn sẽ thông cảm với công việc khó khăn của hiệu trưởng, người giải quyết vấn đề bài toán này sáu tháng một lần.

Hai ví dụ này có lẽ đủ để hiểu: việc tạo ra bài toán là một phần quan trọng (đôi khi họ nói là một nửa) của lời giải của nó. Bằng cách đặt bài toán, cần phải hình thành các giả định cho phép chúng ta trích xuất dữ liệu ban đầu từ biển thông tin về đối tượng đang nghiên cứu, xác định kết quả sẽ phục vụ mục đích gì và mối liên hệ giữa dữ liệu ban đầu và kết quả là gì. Tất cả điều này - các giả định, dữ liệu đầu vào, kết quả và mối liên hệ giữa chúng - được gọi là mô hình bài toán.

Không phải lúc nào cũng rõ ràng những thuộc tính nào của một đối tượng là cần thiết cho lời giải bài toán. Ở đây, giả sử, bài toán cũ.

Với hai nhát rìu, hãy cắt móng ngựa thành nhiều mảnh nhất có thể mà không cần sắp xếp lại mảnh sau nhát chém.

Hãy chính thức hóa bài toán. Chúng ta có thể đưa ra ngay các giả định sau: nhát rìu là một đường cắt thẳng, móng ngựa là một loại vòng cung, các phần của móng ngựa sau đòn vẫn còn

⟦folio 61⟧

được đặt đúng chỗ và không bị biến dạng. Điều này có nghĩa là bạn cần vẽ một vòng cung và cắt nó bằng hai đường thẳng. Chúng tôi đã đặt rõ ràng bài toán và dễ dàng nhận thấy rằng hơn 1/5 phần sẽ không thành công (hình 2).

Tuy nhiên, trong cuốn sách của E. I. Ignatev “In the Kingdom of Ingenuity” (M., Nauka, 1982) có một bài toán tương tự, người ta yêu cầu cắt một chiếc móng ngựa thành sáu phần và một phần khác hình (hình 3; tốt khi có đáp số!) được đưa ra. Hóa ra là chúng ta quá trừu tượng và không dạy rằng móng ngựa cũng có chiều rộng. Vì vậy, trong mô hình của chúng ta, chúng ta cần thay thế giả định rằng móng ngựa là một vòng cung bằng điều này: móng ngựa là một nửa vòng tròn.

Tuy nhiên, tiếp tục theo cách tương tự, chúng ta có thể nói rằng móng ngựa cũng có độ dày (hình 4), và sau đó dar toropa có một đường cắt phẳng. Một chiếc móng ngựa có thể được chia thành bao nhiêu phần, có tính đến độ dày? Chúng tôi có 7 phần.

Bài tập 1. Dùng hai chiếc udarami toropa cắt móng ngựa thành 7 miếng.

Hoặc có thể trong thực tế còn có nhiều hơn đáp số? Tôi nên tính đến điều gì khác? Tất nhiên là có lỗ! Suy cho cùng, móng ngựa có lỗ để đóng đinh (hình 5). Khó có thể tin thành công nhưng hóa ra lại có tới 11 phần!

Bài tập 2. Dùng hai udarami toropa cắt móng ngựa thành 11 miếng.

Vì vậy, nhờ mô tả đối tượng đầy đủ hơn, kết quả ban đầu có thể tăng hơn gấp đôi! Điều thú vị là, mỗi phép tính gần đúng mới của mô hình với thực tế đều dẫn đến một bài toán được nêu rõ ràng với một đáp số rõ ràng.

Như bạn có thể thấy, bài toán phụ thuộc đáng kể vào các giả định ban đầu và càng có nhiều thuộc tính của một đối tượng mà chúng ta học trong mô hình thì lời giải càng phức tạp. Tuy nhiên, không phải lúc nào khi gấp mô hình, chúng ta sẽ nhận được kết quả mới. Cộng lại, những ai đã từng nhìn thấy móng ngựa đều biết rằng móng ngựa không có hai lỗ mà nhiều hơn (xem hình 6). Tuy nhiên, việc tăng số lượng lỗ trên móng ngựa thật có thể không ảnh hưởng đến đáp số đến bài toán.

Bài tập 3. Chứng minh rằng móng ngựa được chọn ở hình 6 không thể bị cắt bằng hai nhát toropa thành nhiều mảnh hơn móng ngựa ở hình 5.

Nghệ thuật vẽ ra một mô hình nằm ở việc tính đến tất cả sự tồn tại trong đó mà không làm mô hình trở nên phức tạp quá mức và loại bỏ những gì không quan trọng.

Hình 2.
Hình 3.
Hình 4.
Hình 5.
Hình 6.

⟦folio 62⟧

Đây không phải là điều mà bất kỳ tác phẩm nghệ thuật nào cũng bao gồm, dù là hội họa hay điêu khắc? Và nói chung, làm ơn, mọi hình thức nghệ thuật đều tham gia vào việc tạo ra một mô hình cuộc sống sử dụng các phương tiện biểu đạt.

Và một kết luận nữa có thể được rút ra: nếu chúng ta thay thế cuộc sống bài toán bằng mô hình của nó, thì đáp số cũng đề cập đến mô hình và chỉ gián tiếp đến bài toán ban đầu.

Vì vậy, việc tạo ra một mô hình tốt bài toán không phải là một việc dễ dàng. Tiếp theo, hãy quyết định tự mình trình bày bài toán này cho bạn. Nếu bài toán cần được giải thích với máy tính thì sao? Trong trường hợp này, bạn sẽ phải tính đến “khả năng” của máy tính, hay chính xác hơn là khả năng của ngôn ngữ mà bạn sẽ giải thích cho nó. Nếu máy tính của bạn chỉ có nhiệm vụ tính toán thì khi thể hiện ý tưởng về một đối tượng, bạn cần đảm bảo rằng dữ liệu và kết quả ban đầu là những con số và mối liên hệ giữa chúng là những sự tương ứng toán học. Thực hiện “bản dịch” bài toán sang ngôn ngữ toán học như vậy, bạn sẽ nhận được một mô hình được hứa hẹn gọi là mô hình toán học.

Mathematical models

Bây giờ chúng ta có thể quay lại trạm bài toán của mình. Hãy bắt đầu một cách tự nhiên bằng việc xây dựng một mô hình toán học. Trước hết, chúng tôi bày tỏ ý tưởng của mình. Chúng ta giả sử đoạn đường đi qua địa phận huyện là đoạn thẳng; Nhà ga có thể được xây dựng ở bất cứ đâu trên đoạn đường và được kết nối bằng những con đường thẳng đến từng khu dân cư $A_1$, $A_2$, ..., $A_n$.

Bây giờ chúng ta cần hiểu cụm từ “vị trí thuận tiện nhất của nhà ga”. Làm thế nào để hiểu điều này? Nếu muốn tiết kiệm chi phí làm đường thì ga phải được bố trí sao cho tổng chiều dài đường nối ga với khu dân cư là nhỏ nhất. Nếu chúng ta cố gắng đạt được sự công bằng tối đa thì hãy chọn vị trí đặt trạm tự nhiên sao cho khoảng cách từ trạm đó đến khu dân cư càng ngắn càng tốt. Ví dụ, nếu một người bị ốm ở khu định cư xa nhà ga nhất thì người đó phải được đưa đến nhà ga trong thời gian ngắn nhất.

Chúng tôi ủng hộ công lý, và do đó chúng tôi sẽ tránh nguyên tắc thứ hai.

Bài tập 4. a) Chứng minh rằng hai nguyên nhân này dẫn đến kết quả khác nhau.

6) Hai khu định cư nên được bố trí như thế nào để những nguyên nhân này tạo ra kết quả giống nhau?

Bài toán cho nghiên cứu. Giải bài tập 4 b trong trường hợp có số độ lún tùy ý.

Các giả định đã được đưa ra, chúng tôi sẽ xác định đâu sẽ là dữ liệu ban đầu và đâu sẽ là kết quả trong mô hình toán học của chúng tôi. May mắn thay (hay đúng hơn là có chủ ý), các giả định sao cho chúng ta có thể dễ dàng dịch bài toán sang ngôn ngữ của các con số. Để thực hiện việc này, hãy vẽ các trục tọa độ trên bản đồ của khu vực sao cho trục hoành độ đi dọc theo nút đường sắt quan tâm và gốc tọa độ trùng với đầu bên trái của nó. Tất nhiên, dữ liệu chúng tôi sử dụng là số lượng $n$ khu định cư, tọa độ của chúng $(a_1; b_1), (a_2; b_2), ..., (a_n; b_n)$ hoặc $S$ đoạn đường sắt chạy qua khu vực. Kết quả là trục hoành của điểm cần xây dựng nhà ga (hình 7).

Vẫn còn phải tìm sự tương ứng giữa dữ liệu được điền và kết quả.

⟦folio 63⟧

Hãy lấy bất kỳ điểm nào trên đoạn đường đó và mô tả một tuyến đường sắt. Đặt $t$ là hoành độ của nó. Đặt $Z$ biểu thị khoảng cách tối đa giữa điểm này và từng khu định cư:

$$Z = \max \left\{ \sqrt{(t-a_1)^2 + b_1^2}, \right. \\
\sqrt{(t-a_2)^2 + b_2^2} ; \dots ; \sqrt{(t-a_n)^2 + b_n^2} \}.$$

Rõ ràng rằng $Z$ là hàm của $t$. Để xác định nơi xây dựng trạm, bạn cần tìm xem $t$ nào từ đoạn [0; hàm $S$] $Z(t)$ nhận giá trị nhỏ nhất.

Như bạn có thể thấy, chúng tôi đã thay thế bài toán ban đầu về trạm bằng một bài toán: tìm điểm tối thiểu của một hàm nào đó. bài toán này là một mô hình toán học.

Làm thế nào để tìm được điểm tối thiểu? Tất nhiên, bạn nên thử lấy một hàm tùy ý $Z(t)$ và đánh đồng nó bằng 0. Họ gặp rất nhiều khó khăn: hàm $Z(t)$ không thể được tính bằng một công thức đơn giản và hàm số tùy ý của nó rất có thể không tồn tại ở mọi điểm. Chúng ta hãy thử tưởng tượng đồ thị của hàm $Z(t)$.

Sự khác biệt 5. Chọn tọa độ tùy ý của một số cây, cũng như chiều dài của đoạn đường sắt và sử dụng máy tính hoặc máy vi tính để xây dựng (từng điểm) đồ thị của hàm $Z(t)$.

Có thể dễ dàng xác minh rằng hàm $Z(t)$ đầu tiên sẽ tắt và sau đó tăng lên. Chúng ta thật may mắn: hàm số của chúng ta chỉ có một điểm cực tiểu. Nó có thể được tìm thấy với bất kỳ độ chính xác nào bằng cách sử dụng phương pháp sau. Hãy chia đoạn [0; $S$] thành các phần bằng nhau, độ dài của mỗi phần được ký hiệu bằng chữ cái $r$. Sau đó, chúng tôi tìm thấy các giá trị của $Z$ tại $t=0, r, 2r, \dots$, v.v. cho đến $t=S$. Chúng ta hãy chọn giá trị nhỏ nhất trong số các giá trị này và thay thế kết quả $t$ mà nó đạt được. Giá trị $t$ này sẽ khác với kết quả “đúng” không quá $r$.

Vì vậy, chúng tôi đã thay thế phép tính phức tạp bài toán trong việc tìm điểm tối thiểu của hàm có độ cay thấp bằng nhiệm vụ đơn giản là tìm giá trị tối thiểu của một số số.

Sau đây là sự đơn giản của độ chính xác. Kết quả chỉ thu được bằng cách tính gần đúng: $r$ càng nhỏ thì càng chính xác. Tuy nhiên, chẳng ích gì khi theo đuổi độ chính xác cụ thể - xét cho cùng, trên thực tế, đường sắt không thẳng và tọa độ của cây chỉ được biết gần đúng, và Trái đất, như chúng ta biết, không bằng phẳng, và quan trọng nhất, cả nhà ga và các ngôi làng đều không phải là điểm.

Đúng, bằng cách sử dụng các cấu trúc hình học, có thể tìm thấy “chính xác” lời giải.

Bài tập 6. $n$ điểm và một đoạn được cho trên mặt phẳng. Chỉ dùng compa và thước kẻ, tìm một điểm trên đoạn thẳng sao cho khoảng cách từ điểm đó đến các điểm cho trước là nhỏ nhất.

Việc lựa chọn các đề xuất ban đầu cho mô hình toán học bài toán về nhà ga có thể bị ảnh hưởng không chỉ bởi mong muốn công lý mà còn bởi một số yếu tố kinh tế, chẳng hạn như thiếu kinh phí xây dựng đường. Khi đó, nguyên tắc tìm vị trí của nhà ga sẽ như sau: tổng khoảng cách từ nhà ga đến khu dân cư phải ở mức tối thiểu.

Bài tập 7. Lập mô hình toán học bài toán về nhà ga dựa trên nguyên tắc này.

Nhiệm vụ nghiên cứu. $n$ điểm và một đoạn được cho trên mặt phẳng. Xây dựng một điểm trên đoạn thẳng sao cho tổng khoảng cách từ điểm đó đến các điểm cho trước là nhỏ nhất.

Vì vậy, để tạo mô hình toán học cho lời giải bài toán, bạn cần:

1) nêu bật các đề xuất làm cơ sở cho mô hình toán học;
2) xác định những gì được coi là dữ liệu đầu vào và kết quả;
3) viết ra các sự tương ứng toán học (công thức, phương trình, bất đẳng thức, v.v.) kết nối kết quả với dữ liệu gốc.

Như bạn có thể thấy, một mô hình toán học luôn dựa trên một số nguyên tắc. Tuy nhiên, nhờ sự thay thế

⟦folio 64⟧

của một đối tượng với mô hình tương ứng của nó, nó có thể hình thành bài toán nghiên cứu nó như toán học và tận dụng nó lời giải bằng toán học.

Mô hình được xây dựng. Tiếp theo là gì?

Việc tạo mô hình toán học sẽ hoàn thành giai đoạn đầu tiên lời giải bài toán bằng máy tính. Tiếp theo bạn cần viết chương trình thích hợp. Chúng tôi sẽ không cho bạn biết cách thực hiện việc này - nó phụ thuộc vào khả năng của một máy tính cụ thể và các ngôn ngữ được triển khai trên đó. Nhưng sau đó bạn cần đảm bảo rằng mô hình phù hợp với đối tượng thực. Sự tự tin như vậy chỉ có thể đạt được thông qua thử nghiệm. Khi thực hiện các phép tính trên máy tính cần phải phân tích kết quả. Trong trường hợp này, có thể cần phải làm rõ mô hình toán học, vì rõ ràng là trong quá trình phát triển nó, bất kỳ thuộc tính thiết yếu nào của đối tượng đều không được tính đến. Tinh chỉnh mô hình, soạn lại chương trình, tiếp tục tính toán trên máy tính và phân tích kết quả. Và một lần nữa nó có thể yêu cầu tính đến mô hình. Điều này sẽ tiếp tục cho đến khi việc phân tích kết quả cho thấy sự tương ứng của chúng với đối tượng đang được nghiên cứu.

Sau khi đảm bảo rằng mô hình toán học phù hợp với thực tế, bạn có thể tiến hành các thí nghiệm tính toán bằng máy tính. Trong trường hợp này, bạn có thể nấu các giá trị của dữ liệu ban đầu, nghiên cứu các tình huống khắc nghiệt, xác định giới hạn khả năng áp dụng của mô hình, v.v. Do đó, máy tính cho phép bạn thay thế một thí nghiệm tự nhiên, thường tốn kém và nguy hiểm, bằng một thí nghiệm tính toán an toàn và tương đối rẻ. Đây có lẽ là ưu điểm chính của máy tính.

Bài tập

1. Lập mô hình toán học bài toán về nhà ga, được hướng dẫn theo nguyên tắc thỏa hiệp: nếu $Z$ là khoảng cách từ nhà ga đến điểm xa nhất và $W$ là tổng khoảng cách đến tất cả các điểm, thì bạn cần tính tổng $kZ+(1-k)W$ càng nhỏ càng tốt, trong đó $k$ là một số từ đoạn [0; 1] (mức độ thỏa hiệp).

2. Nghiên cứu bài toán về một nhà ga đường sắt cho hai khu định cư, một khu có 1000 người và khu còn lại có 2000 người, được hướng dẫn theo nguyên tắc sau: tổng số “man-km” mà người dân dành trên đường đến ga phải là nhỏ nhất.

3. Một cậu học sinh không biết phép tính tích phân đã biên soạn mô hình toán học sau đây để tìm chu vi của một cuộc leo núi tùy ý.

Giả định: chúng tôi coi việc leo lên là một hình phẳng; nếu bạn chia ranh giới của đoạn leo thành nhiều phần nhỏ và nối các điểm phân tách một cách tuần tự, thì chu vi của đa giác thu được sẽ khác rất ít so với chu vi của đoạn leo và độ phân chia càng nhỏ thì kết quả càng chính xác.

Hoàn thiện việc xây dựng mô hình toán học.

4. Một cậu học sinh không biết định lý Pythagore đã biên soạn mô hình toán học sau để xác định độ dài đường chéo của một bàn hình chữ nhật tùy ý.

Giả định: coi mặt bàn là một hình chữ nhật có các cạnh $a$ và $b$; chiều dài của đường chéo $d$ xấp xỉ bằng chiều dài của đường đứt nét hiển thị trong hình 8, tất nhiên, nếu các bước của đường gãy này đủ nhỏ; với số bước tăng không giới hạn, giá trị đường chéo sẽ đạt được với bất kỳ độ chính xác nào. Sau đó $d=a+b$ (thực sự, độ dài của đường đứt nét bằng $a+b$, bất kể nó có bao nhiêu bước).

Tại sao kết quả sai: đường chéo của hình chữ nhật bằng tổng các cạnh liền kề của nó?

Đề tài thí nghiệm tính toán (đối với chương trình)

Soạn chương trình tương ứng với khoảng cách trong mô hình thống kê bài toán về nhà ga. Xem vị trí của trạm thay đổi như thế nào khi số $k$ trong bài toán 1 thay đổi và khi số lượng phân đoạn tăng lên.
