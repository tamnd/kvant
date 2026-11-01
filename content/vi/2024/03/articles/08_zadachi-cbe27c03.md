---
id: 2024-3-zadachi-cbe27c03
issue: kvant_2024_3
year: 2024
number: "3"
title: Bài toán
rubric: kvant-dlya-mladshih-shkolnikov
rubric_sub: «Квант» для младших школьников
page_first: 37
page_last: 44
page_labels: 37-42
tag: DS90
lang: vi
source: kvant_digital
content_sha256: fd1840742093fe905292a9af31fb55ae09217aaa63b961dfcf86f64a2368bb6d
prompt_sha256: draft-1
translated_from: content/ru/2024/03/articles/08_zadachi-cbe27c03.md
source_content_sha256: be2da87c8c2fd86abe6e115454e300151798b878d408b17dd69e79ff6191eb38
translation_model: draft
translation_run: vi-draft-gaps-2026-11-01
translation_quality: draft
---

⟦folio none⟧

1.

Bài toán

⟦folio 37⟧

TOÁN HỌC

Petya viết, những con số mà máy tính sẽ in theo chương trình của anh ấy cũng sẽ bắt đầu lặp lại định kỳ. Vì vậy, máy tính chỉ có thể in phần mở rộng thập phân của số hữu tỉ. Như bạn có thể thấy, ý định của Petino là không khả thi do kích thước hạn chế của một chiếc máy tính thực sự. Nếu số lượng ô nhớ của máy tính là không giới hạn thì việc viết chương trình tính căn bậc hai sẽ không khó.

Bài tập 10. Bạn có thể xây dựng một máy tự động với không quá 100 trạng thái có thể in được chuỗi số nào?

Tuy nhiên, có một số bài toán mà ngay cả một máy tính có kích thước vô hạn cũng không thể xử lý được. bài toán như vậy được gọi là không thể giải quyết được về mặt thuật toán. Có thể bạn đã từng giải các phương trình số nguyên và biết việc tìm lời giải khó đến mức nào. Điều này không phải ngẫu nhiên - như định lý đáng chú ý của Matiyasevich cho thấy (xem «Kvant» số 5 năm 1975), bài toán lời giải của các phương trình như vậy là không thể giải được về mặt thuật toán. Tuy nhiên, ngay cả khi không dùng đến các dịch vụ của máy tính, có thể chứng minh rằng ngay cả một thiết bị tự động có khả năng thực thi các chương trình có độ phức tạp và độ dài bất kỳ vẫn không thể giải được nhiều công thức rất đơn giản bài toán. Ý tưởng về tính tuần hoàn sẽ lại giúp chúng ta điều này. Chúng ta hãy nhìn vào một cỗ máy có vẻ ngoài rất đơn giản - Draftsman. Anh ta có thể di chuyển dọc theo một tờ giấy ca rô, tô màu các ô. Chúng ta sẽ mô tả hướng chuyển động của Người soạn thảo bằng một mũi tên. Đối với Người soạn thảo, chỉ được phép thực hiện ba hành động: 1. “SƠN” – sơn lên ô. 2. “TRÁI” – xoay 90 độ sang trái xung quanh đầu mũi tên. 3. “JUMP” – nhảy đến giữa ô liền kề theo hướng mũi tên. Ngoài ra, Người soạn thảo còn biết cách kiểm tra điều kiện “THE EDGE AHEAD”. Thoạt nhìn, có vẻ như Người soạn thảo thậm chí còn thô sơ hơn cả Minotaur: anh ta thậm chí còn không hiểu lệnh “ĐÚNG”. Nhưng sự đơn giản là lừa dối. Để làm quen với Draftsman và đảm bảo rằng nó không tầm thường, hãy thử làm các bài tập 10–11.

VÒNG TRÒN

⟦column⟧

Các chương trình dành cho Người soạn thảo có thể được viết dưới bất kỳ hình thức nào thuận tiện cho bạn, sử dụng bất kỳ phương pháp viết nhánh, vòng lặp và chương trình con nào. Bạn không thể buộc Người soạn thảo thực hiện các lệnh mà anh ta không thể thực hiện được (ví dụ: “ĐÚNG”) và kiểm tra các điều kiện mà anh ta không hiểu (ví dụ: điều kiện “CẠNH TRÁI”). Và điều cũng rất quan trọng - Người soạn thảo không biết đếm. Nó không có khả năng lặp với các tham số hoặc làm việc với các biến số (hoặc bất kỳ biến nào khác). Nếu người đọc không thoải mái khi làm việc với chương trình bằng ngôn ngữ “tùy ý”, thì chúng tôi sẽ sử dụng BLACK BASIC: mỗi dòng chứa một số lệnh và một lệnh chỉ có dạng GOTO N (đi tới lệnh số N), “PAINT”, “LEFT”, “JUMP” hoặc bước nhảy có điều kiện IF EDGE, THEN GOTO N. Và nếu không có chuyển đổi thì lệnh có số tiếp theo sẽ được thực thi tiếp theo.

Bài tập

11. Viết một chương trình cho Người soạn thảo, theo đó anh ta, trên bất kỳ tờ giấy nào: a) sẽ đến góc của tờ giấy, bất cứ nơi nào chúng ta đặt nó; b) sơn tất cả các ô của tờ giấy; c) sẽ di chuyển ra khỏi mép của tờ giấy nếu nó được đặt ở mép; d) xác định xem anh ta có ở trong góc hay không, sơn hình vuông ở góc nếu anh ta ở trong góc và giữ nguyên vị trí ban đầu nếu không. 12. Viết chương trình cho Người soạn thảo, theo đó anh ta, trên một tờ giấy vuông bất kỳ: a) bắt đầu từ vị trí hình 2, vẽ một dải k 2 ô nếu k chẵn và quay về vị trí ban đầu không vẽ gì nếu k lẻ; b*) sẽ tô màu tất cả các ô của hình vuông, ngoại trừ các ô chứa tâm của nó (tuỳ theo độ dài ngang bằng của cạnh trang tính mà tâm là một ô hoặc bốn ô).

Hình 2

⟦folio 38⟧

---
running_head:
folio:
---

Để cuối cùng thuyết phục bạn về tính không tầm thường của Người soạn thảo, chúng tôi trình bày, không có bằng chứng, một tuyên bố cho thấy rằng Người soạn thảo không đơn giản hơn một chiếc máy tính có bộ nhớ vô hạn.

Sự thật đáng kinh ngạc. Giả sử $a_1, a_2, \dots$ là một dãy số tự nhiên và có một chương trình trong đó một máy tính (có bộ nhớ vô hạn) với mỗi n sẽ tính toán $a_n$. Sau đó, có một chương trình dành cho Người soạn thảo, theo đó anh ta, với bất kỳ n nào, bắt đầu từ vị trí $2^n$ đến hình 3, sẽ vẽ một dải gồm các đầu cuối $2^{a_n}$, nếu tờ giấy là mặt phẳng màu.

Hình 3

Đối với các số mũ và logarit nhỏ hơn, người soạn thảo có thể thay thế máy tính. (Điều này có nghĩa là, nói theo ngôn ngữ nghiêm ngặt của các nhà logic học, với sự trợ giúp của nó, bạn có thể tính toán bất kỳ hàm tính toán nào $a(n)$.)

Do đó, một Người soạn thảo, người hoàn toàn không quen thuộc với các con số, có thể được dạy tính toán mọi thứ mà một máy tính có bộ nhớ vô hạn có thể tính toán, chẳng hạn như các số trong khai triển thứ mười của căn bậc hai (để biết thêm thông tin về các thuật toán, hãy xem cuốn sách “The Post Machine” của V.A. Uspensky).

Tuy nhiên, có những nhiệm vụ rất đơn giản là tô màu một tờ giấy - hoạt động chính của Người vẽ phác thảo, mà anh ta không thể học cách thực hiện với tất cả mong muốn của chúng tôi và anh ta. Đây là một ví dụ về một nhiệm vụ như vậy.

Bài toán 13. Chứng minh rằng không có chương trình nào mà theo đó người soạn thảo sẽ vẽ lên các đầu cuối chứa chuỗi của tờ giấy trên bất kỳ tờ giấy vuông nào, bất kể vị trí ban đầu. (Thật ngạc nhiên là Người soạn thảo có thể vẽ lên tất cả các thiết bị đầu cuối, ngoại trừ các thiết bị đầu cuối chính.)

Lời giải. Rõ ràng là đối với một tờ giấy có kích thước nhất định, các chương trình cần thiết phải được viết ra nhiều lần. Điều này có nghĩa là toàn bộ vấn đề là bạn cần tạo một chương trình sẵn sàng cho bất kỳ số lượng tờ giấy nào.

Hãy tưởng tượng một chương trình ngắn để xác định 1000 dòng và một tờ giấy rất lớn, chẳng hạn như vài trăm nghìn ô. Và thế là Người soạn thảo đứng ở góc tờ giấy và lên đường, được chương trình của chúng tôi hướng dẫn. Sẽ phải mất rất nhiều thời gian trước khi anh ấy đến được trung tâm và vẽ ô ở đó. Trước đó, anh ta sẽ phải đi bộ rất lâu khỏi các mép của tờ giấy. Người soạn thảo cư xử như thế nào khi ở xa rìa? Để hiểu điều này, hãy giả sử rằng trang tính không có cạnh nào cả—trang tính là vô hạn.

Có lẽ sau đó Người soạn thảo di chuyển theo định kỳ? Kinh nghiệm của chúng tôi cho thấy rằng với tư cách là trạng thái của Người soạn thảo, chúng ta phải thay thế dòng chương trình đang được thực hiện tại thời điểm đó và hướng của Người soạn thảo trên mặt phẳng (một trong bốn: lên, xuống, phải, trái). Nếu số dòng trong chương trình là n thì trạng thái có thể là $4n$. Chúng tôi sẽ thay đổi thời gian trong chương trình làm việc đó. Tất nhiên, bạn có thể sử dụng định lý tuần hoàn, nhưng chúng ta vẫn sẽ nghiên cứu Người soạn thảo.

Bây giờ hãy để trạng thái lặp lại tại các thời điểm $T, T + \Delta T$. (Chúng ta có thể giả sử rằng $\Delta T < 4n$. Tại sao?) Trong thời gian này, Người soạn thảo sẽ cung cấp cho vectơ $a$ và trong tương lai, trong mỗi khoảng thời gian $\Delta T$, anh ta sẽ cung cấp cho vectơ này. Chuyển động của Người soạn thảo, nếu nhìn từ góc nhìn của một con chim, giống như một vật thể không có ngoại lực tác động lên - “thẳng và đều”, tức là nó di chuyển dọc theo một đường thẳng, lệch khỏi nó đến một khoảng cách giới hạn và vẽ một mô hình lặp lại định kỳ.

Bài tập 13. a) Chứng minh rằng mọi chuyển động tuần hoàn đều có thể xảy ra dọc theo một đường thẳng có góc nghiêng hợp lý.

6) Kích thước của hình vuông có thể được vẽ bằng chương trình gồm n câu lệnh là bao nhiêu? Gợi ý. Hãy để trạng thái bên trong của Người soạn thảo chỉ là một vị trí trong chương trình.

c) Chứng minh rằng nếu Người soạn thảo đi “đến vô cùng”, thì cả trạng thái bên trong và hướng của anh ta đều lặp lại với khoảng thời gian $\Delta T < n$.

Chuyển động của Người soạn thảo giống như hành vi của một hạt cơ bản. Nếu nó xuất hiện trên một tờ giấy “từ góc nhìn của một con chim”

⟦folio 39⟧

---
running_head:
folio:
---

chuyến bay", sau đó chúng tôi thấy những gì chúng tôi thấy từ rìa
lá (hoặc dọc theo mép) nó có thể di chuyển
theo một số cách hữu hạn. Trong trường hợp “va chạm”
không" với một bức tường hoặc góc sẽ xảy ra "dis-
haying", và từ một phương pháp di chuyển, theo
một số luật, người soạn thảo tiến hành
phương thức di chuyển khác (tùy theo
từ những gì nó va chạm - một bức tường hoặc
góc, hướng và cả “pha” –
nó sẽ va chạm ở trạng thái bên trong nào).
Một sự thật đáng ngạc nhiên cho chúng ta biết về độ khó vô tận bài toán của việc tán xạ nhiều lần.

Bài tập 14 (một bằng chứng khác về tính tuần hoàn của chuyển động của người vẽ phác thảo). Chứng minh rằng chương trình dành cho Người soạn thảo làm việc trên một tờ giấy không giới hạn có thể được viết lại sao cho hành vi của Người soạn thảo không thay đổi và chỉ có một lệnh chuyển sang dòng khác (ở cuối chương trình).

Gợi ý. Thay thế tất cả các điều kiện chuyển tiếp bằng các điều kiện vô điều kiện (tại sao điều này có thể được thực hiện?), sau đó chỉ định các dòng của chương trình chứa các lệnh “LEFT”, “JUMP”, “PAINT” bằng dấu chấm và bằng mũi tên - lệnh tiếp theo sẽ được thực thi. Con đường dọc theo mũi tên là gì?

Như bạn có thể thấy, ngoài các cạnh của tờ giấy, Người vẽ phác thảo không thông minh hơn Minotaur, chỉ có sự hiện diện của các cạnh khiến anh ta có thể so sánh với một chiếc máy tính. Tự do không phải lúc nào cũng tốt!

Hãy quay lại lời giải bài toán 13. Chúng ta có thể kết luận: ra khỏi các cạnh của trang tính, Người soạn thảo di chuyển định kỳ với một khoảng thời gian và khoảng thời gian trước không vượt quá độ dài của chương trình. Vì vậy, giai đoạn chuẩn bị sẽ kết thúc rất lâu trước khi Người soạn thảo phải đến được trung tâm. Khi đến trung tâm, anh ta phải thực hiện lệnh “SƠN”. Điều này có nghĩa là lệnh này được bao gồm trong dấu chấm và Người soạn thảo phải thực hiện nó nhiều lần trên đường đến giữa trang tính.

Bài tập 15. lời giải bài toán 13 đã cho không thẳng lắm đâu, nó “mượt” thôi. Cụ thể: cho chương trình dành cho Người soạn thảo chứa $n$ dòng. Hãy ước tính kích thước của tờ giấy cần lấy để Người soạn thảo không thể chỉ vẽ các ô trung tâm.

Có lẽ ở đây bạn (như tôi lúc đầu) nghi ngờ về một sự thật đáng kinh ngạc. Rốt cuộc, nếu số $n$ rất lớn, thì chẳng hạn, trong quá trình chuyển đổi từ $2^n$ sang $2^{n^2}$, Người soạn thảo sẽ phải đi chệch khỏi ranh giới nhiều lần, và khi đó hai trạng thái nhất thiết phải được lặp lại đối với anh ta, một giai đoạn bắt đầu và Người soạn thảo không thể dừng lại. Hãy làm rõ những thông điệp này. Bằng cách chuyển từ số $k$ sang số $l$ chúng ta sẽ hiểu sự chuyển đổi từ vị trí trên cạnh ở khoảng cách $k$ từ đỉnh của góc sang vị trí trên cạnh ở khoảng cách $l$ tính từ đỉnh. Chúng ta sẽ xác định “trạng thái ở rìa” như sau: đầu tiên, chúng ta tính đến số lượng lệnh được thực thi trong chương trình và hướng trên mặt phẳng. Tất nhiên, điều này vẫn chưa đủ: sau khi phản ánh, Người soạn thảo có thể đến một bức tường khác ở các “giai đoạn” khác nhau, tức là ở một nơi tùy ý trong thời kỳ “trạng thái nội bộ”. Do đó, trong các trạng thái dễ hiểu, chúng ta cũng sẽ bao gồm phần còn lại của việc chia khoảng cách đến đỉnh của góc cho bội số chung của tất cả các chu kỳ có thể có của chuỗi trạng thái bên trong khi Người soạn thảo di chuyển dọc theo một mặt phẳng không giới hạn (ví dụ: cho $k!$, trong đó $k$ là số lượng lệnh trong chương trình).

Bây giờ, sự lặp lại của hai trạng thái bleibt được theo sau không chỉ bởi cùng một “sự khởi hành” khỏi bức tường mà còn cùng một “sự đến” với bức tường kia (tại sao?).

Nếu bản thân bạn phát hiện ra sai sót trong lý luận trước đó, thì sự thật đáng kinh ngạc sẽ trở nên rõ ràng hơn với bạn.

Chúng tôi sẽ cố gắng giải thích nó một cách tổng quát.

Trước hết, bằng cách di chuyển dọc theo một đường thẳng có góc nghiêng hợp lý (xem Bài tập 12,a), bạn có thể di chuyển từ số $2x$ sang số $3x$, $5x$, v.v. (chỉ ra cách thực hiện). Ngoài ra, bạn có thể IMIT kiểm tra khoảng cách đến một đỉnh về tính chẵn lẻ (xem Bài tập 10,a), cũng như khả năng chia hết cho $3,5,7$, v.v.

hình 4 trình bày sơ đồ khối thuật toán di chuyển từ $2^n$ tương ứng với $3^n$ và $2^{2^n}$. Tất nhiên, những sơ đồ này vẫn cần phải được viết ra chi tiết để Người soạn thảo có thể hiểu được.

Vấn đề 14*. a) Hãy làm điều này. b) Vẽ sơ đồ khối tương tự cho quá trình chuyển đổi từ số $2^n$ sang chữ số thập phân thứ $n$ của khai triển căn hai thập phân. (Nếu sơ đồ quy trình của một quy trình nhất định đã bị vi phạm thì quy trình đó có thể được biểu thị thêm bằng một hành động.)

Một thực tế đáng kinh ngạc được giải thích là các chỉ mục được máy tính sử dụng có thể

⟦folio 40⟧

KVA NT 2024/Số 3

⟦column⟧

Tính từ “mô hình” không phải ngẫu nhiên - nó rất giống với những gì các nhà khoa học tự nhiên làm, loại bỏ một phần đặc tính của một hiện tượng tự nhiên để làm cho nó có thể nhìn thấy được. Những ý tưởng thường gặp, “lý luận tiêu chuẩn” (ví dụ nguyên lý Dirichlet, tính tuần hoàn) cũng có thể được coi là mô hình của các tình huống. Những mô hình này sơ đồ đến mức trông tầm thường, nhưng biết được những “điều tầm thường” như vậy sẽ khiến cuộc sống trở nên dễ dàng hơn nhiều.

Bài tập

16. Giả sử rằng Người soạn thảo không chỉ có thể vẽ mà còn có thể xóa sơn khỏi ô đã sơn (giả sử sử dụng lệnh “ERASE”). a) Viết chương trình cho Người soạn thảo, theo đó anh ta sẽ vẽ các ô trung tâm và chỉ chúng. b) Chứng minh rằng không thể tạo một chương trình để Người soạn thảo “xóa” mà theo đó anh ta sẽ vẽ một hệ các ô vuông lồng nhau (hình 5) trên một tờ giấy hình vuông bất kỳ.

⟦figure⟧

Hình 4

nhưng mô hình sử dụng số mũ cho số nguyên tố - có một chỉ số thì có nhiều. Từ thực tế này, người ta có thể rút ra tính không thể quyết định được về mặt thuật toán của một số phát biểu - ví dụ, định lý Matiyasevich đã được đề cập ở trên. Bạn đã thấy ý tưởng đi xe đạp hoạt động như thế nào. Mặc dù trông khá đơn giản, nhưng bài toán, lấy ý tưởng này làm ý chính, không phải lúc nào cũng dễ dàng. Có chuyện gì thế này? Hóa ra là ngay cả những ý tưởng chính rất đơn giản cũng nên biết trước, nếu không chúng sẽ khó được khám phá giữa những ý tưởng và sự phức tạp về mặt kỹ thuật khác. Nếu chưa xác định được ý chính và có khó khăn về mặt kỹ thuật thì ý tưởng đó phải được “trích xuất”, nhưng không phải trực tiếp mà có sự giúp đỡ của người khác bài toán. Xét cho cùng, bài toán không tồn tại một mình mà được bao quanh bởi những người thân của nó (ngay cả đối với lời giải “một ô” bài toán 1, cần phải xem xét các chữ số cuối cùng của tất cả các lũy thừa của hai). Vì vậy, họ nghiên cứu bài toán, có liên quan về mặt tư tưởng với cái này (đây là cách lời giải bài toán 13 về tâm hình vuông được đặt ra). Thông thường, vì mục đích này, các trường hợp đặc biệt quan trọng nhất hoặc mô hình khác bài toán sẽ được xem xét, trong đó các khó khăn hiện diện ở “dạng yếu hơn” và có ít khó khăn kỹ thuật hơn.

⟦figure⟧

Hình 5

17. Viết thông dịch viên cho ngôn ngữ Minotaur và Draftsman.

Khái quát hóa ý tưởng về tính chu kỳ

Khái quát hóa ý tưởng về tính chu kỳ là phổ biến. Chúng ta đã thấy ý tưởng này hoạt động như thế nào trong trường hợp “rời rạc”, khi chúng ta chỉ làm quen với một số ứng dụng của ý tưởng về tính tuần hoàn và với trường hợp “rời rạc” khi số lượng trạng thái là hữu hạn. Nhưng ngay cả trong trường hợp “liên tục”, với vô số trạng thái, tính tuần hoàn hay chính xác hơn là “gần như tuần hoàn” thường phát sinh, khi các trạng thái không được lặp lại một cách tuyệt đối chính xác mà chỉ xấp xỉ. Vì vậy, mùa hè nào cũng giống và khác với mùa hè trước. Người xưa đã nghĩ đến điều này, và chúng tôi sẽ kể cho bạn vào lúc khác. Hãy xem một ví dụ điển hình.

⟦folio 41⟧

---
running_head:
folio:
---

Bài toán 15. Trên sân vận động hình tròn (chiều dài bóng đèn là 1 chặng) chúng ta nhảy Centavar. Chiều rộng bước nhảy của anh ấy, tôi. Cung mà nó dịch chuyển liên tục là không đổi và bằng a. Chứng minh rằng Centavar sẽ tiến càng gần vị trí ban đầu của nó càng tốt.

Lời giải. Tất nhiên, bang Centavar là nơi anh ta đứng, tức là chỉ vào một vòng tròn. Số lượng trạng thái là vô hạn và việc lặp lại chính xác các trạng thái là không cần thiết. (Ví dụ: sẽ không có sự lặp lại nếu a là số vô tỉ.)
Nguyên lý Dirichlet mang lại điều gì trong trường hợp này? Sự lặp lại các trạng thái với độ chính xác bất kỳ được gọi là “gần như lặp lại”.
Hãy xem xét điều này chi tiết hơn. Hãy để Centavar thực hiện n bước nhảy. Chúng ta hãy đánh dấu từng vị trí của Centavar bằng một điểm; n + 1 điểm này chia đường tròn thành n đoạn, một số đoạn có độ dài không quá 1/n. Các điều kiện “gần như lặp lại”.
Mỗi trạng thái xác định cả trạng thái tiếp theo và trạng thái trước đó; Tôi muốn áp dụng ý tưởng “chuyển động ngược”, tuy nhiên…

Một ví dụ khó chịu. Bloxa nhảy dọc theo đoạn [0; 1]. Nếu bây giờ cô ấy đang ở điểm X, thì ở lần nhảy tiếp theo, cô ấy sẽ kết thúc ở điểm X². Có một sự “gần như lặp lại”, một sự trở lại im lặng.
Lý do là vì mặc dù đối với một số n cả hai trạng thái thứ i-e và (n + i) đều gần nhau nhưng mức độ gần gũi phụ thuộc vào n và i. Nếu tác dụng chuyển động ngược lại lên chúng n lần thì chúng có thể phân tán.
Tuy nhiên, trong bài toán về Centavar, điều này không xảy ra, vì khoảng cách giữa hai trạng thái giống như giữa các trạng thái tiếp theo và giữa các trạng thái trước đó.

Bài tập 18. Hoàn thành chứng minh. Cũng chứng minh rằng không muộn hơn n lần nhảy, Nhân mã sẽ quay trở lại khoảng cách không quá 1/n tính từ điểm xuất phát.

Bài toán 16. Nếu a vô tỷ thì Centavar sớm muộn cũng sẽ rơi vào bất kỳ cung nào của đường tròn. Chứng minh điều đó.

Gợi ý. Nếu trong n lần nhảy Centavar chuyển sang một cung nhỏ ε thì trong k · n lần nhảy nó chuyển sang k · ε, và vì a là vô tỷ nên ε có thể nhỏ, khác 0.

Điều gì sẽ xảy ra nếu hai nhân mã đang nhảy (mỗi nhân mã có độ dài bước nhảy riêng)? Khi nào cả hai sẽ cách vị trí ban đầu ít hơn 1/n? Thời gian chờ này không quá n2 giây (quá trình nhảy được thực hiện trong 1 giây). Ở đây trạng thái là một cặp điểm trên một vòng tròn. Hãy chứng minh rằng trong số n2 + 1 có hai trạng thái gần nhau, tức là vị trí của các nhân mã tương ứng khác nhau không quá 1/n.

Chúng ta hãy mô tả trạng thái của một cặp nhân mã như một điểm của một hình vuông. Tọa độ x có nghĩa là vị trí của tọa độ thứ nhất, tọa độ y - thứ hai. Các điểm vuông có tọa độ khác nhau một số nguyên biểu thị cùng một trạng thái. (Những dấu chấm này là gì?)

Hãy chia hình vuông thành n2 hình vuông, mỗi hình có cạnh bằng 1/n. Khi đó khoảng 2 điểm từ n2 + 1 điểm được đánh dấu sẽ xếp thành một hình vuông. Chúng sẽ mô tả các trạng thái gần nhau mà vị trí của các nhân mã tương ứng khác nhau không quá 1/n.

Bài tập 19. Hoàn thành chứng minh.

Bài toán 17. Khoảng cách cơ hội với centavars. Chứng minh rằng không muộn hơn n2 giây, tất cả các centavarra sẽ ở cùng một khoảng cách không quá 1/n tính từ vị trí ban đầu. (Ban đầu, tất cả centawarra đều ở một nơi.)

Điều thú vị là, trường hợp (thực sự rời rạc) của một bước nhảy hữu tỉ đối với một nhân mã tương đương với phát biểu rằng một cấp số cộng với một bậc hữu tỉ, đi qua 0, chứa vô số số nguyên. Điều tự nhiên là mong đợi rằng một cấp số cộng tùy ý đi qua số 0 sẽ tiến đến gần một số nguyên một cách tùy ý.

Bài toán

18. a) Chứng minh rằng với mọi số thực a đều tồn tại các số nguyên p và q sao cho |p·a - q| < 1/q (hoặc, giống nhau, |a - p/q| < 1/q²), do đó phân số p/q “gần đúng” bởi a.

b*) Chứng minh rằng với mọi số a(i), i = 1, ..., n cũng tồn tại p và q sao cho |p·a(i) - q| < (1/q)¹/n với mọi i = 1, ..., n.

Gợi ý. Trạng thái của một số a·q là phần phân số của nó.

⟦folio 42⟧

KVANT 2024/№3

19**. Gọi a là số vô tỷ và b là số tùy ý trong khoảng 0; 1, q m là phần nhỏ nhất của phần phân số n a, trong đó $n <^{m}$ là số nguyên. Tương tự, r m là giá trị nhỏ nhất của phân số $части^{b} n ^{a}$. Chứng minh rằng q m! r m cho vô hạn $многих^{m.} 20.$ a) Chứng minh rằng các số chia hết cho 2 có thể gần giống với các số $вида^{n} 1 2$, trong đó n là số tự nhiên tùy thích. b*) Chứng minh rằng lũy ​​thừa của hai có thể bắt đầu bằng số chín bất kỳ. Gợi ý. Lấy logarit cơ số 10 của bất đẳng thức $0,9^{…} 9$ $10^{k} 2^{l} 10^{k}$. Sử dụng tính vô tỷ của log 2. c*) Xác suất của lũy thừa được chọn ngẫu nhiên của hai bắt đầu bằng một là bao nhiêu? d*) Chứng minh rằng tồn tại n sao cho các số $2^{n}$ và $3^{n}$ đồng thời bắt đầu bằng các chữ số $1000...^{21*.}$ Cho ánh xạ F lấy bình phương đơn vị K vào chính nó và bảo toàn diện tích mỗi tập con của nó. Chứng minh rằng với mọi tập con của hình vuông U có diện tích lớn hơn 0, luôn tồn tại một điểm x từ U sao cho với một số $n > 0 точка^{F} …^{x}$ ... (n lần) cũng thuộc U. Một phát biểu tổng quát hơn được gọi là định lý truy hồi Poincaré. Định lý này dẫn đến một kết luận có phần bất ngờ: nếu bạn mở một chai nước hoa trong một căn phòng kín thì gần như chắc chắn sau một thời gian tất cả các phân tử của chất có mùi đó sẽ tụ lại trong chai (mặc dù thời gian “một lúc nào đó” dài hơn nhiều so với vòng đời của Vũ trụ). Bằng chứng của thực tế này gợi nhớ đến cách lập luận trong các bài toán về đàn minotaur hoặc nhân mã: vị trí của tất cả các phân tử được mô tả gần giống nhau bởi một điểm trong không gian trạng thái (không gian pha), kết quả trả về được thiết lập bằng định lý Poincaré. Thông thường lý do của tính tuần hoàn về bản chất là nếu tập hợp các trạng thái bị giới hạn thì hai trạng thái sẽ “gần như lặp lại” và sẽ ở gần nhau trong một thời gian. Người xưa đã nghĩ tới điều này. Chúng tôi sẽ kết thúc bài viết về sự trở lại này bằng cách quay trở lại Truyền đạo: “Mặt trời mọc, mặt trời lặn, vội vã về nơi nó mọc. Gió đi về hướng nam, đi về hướng bắc, quay tròn, quay tròn, và gió quay lại theo vòng tròn.”

⟦column⟧

của họ. Mọi sông đều chảy ra biển, nhưng biển không tràn; đến nơi sông chảy, chúng lại chảy trở lại... Cái đã có là cái sẽ có; và những gì đã làm sẽ được thực hiện, và không có gì mới dưới ánh mặt trời.

* * * Hãy cung cấp thêm một vài bài toán về các chủ đề được thảo luận.

1*. Hàm số y cos $x cos^{5} 2 x cos^{5} 4x cos^{5} 8x$ có tuần hoàn không?

2. Tổng của hai hàm tuần hoàn có chu kỳ 1 và 2 nhỏ nhất có thể lại là hàm tuần hoàn không? 3**. Tuyên bố chung: hãy $a_{1}$, … $, a_{n}$ – các số thực sao cho không có số nào trong số chúng có thể được biểu diễn dưới dạng các số khác bằng cách sử dụng tổ hợp tuyến tính với các hệ số hữu tỉ. Sau đó với bất kỳ tập hợp nào $0 b_{i} 1$ và bất kỳ H! 0 tồn tại một L sao cho với mọi i bất đẳng thức L a i b i H là đúng (đối với L được chọn ngẫu nhiên thì điều này đúng với xác suất $H^{n} ). 4.$ Giấy kiểm tra được đưa ra. Các đường song song được vẽ thông qua hai nút. Chứng minh rằng dải kín thu được chứa vô số nút lưới. 5. a) Chứng minh rằng nếu bán kính của một hình tròn tiến tới vô cùng thì khoảng cách từ nó đến điểm nguyên gần nhất có xu hướng bằng 0. b) Tỷ lệ số điểm nguyên rơi trên một đường tròn với bán kính của nó cũng có xu hướng bằng không. 6. Năm nhà khoa học đi dọc hành lang của Viện MIMINO, đến cuối hành lang, mỗi người quay lại. Trong khi Trưởng đi qua hành lang một lần, Trưởng đi qua hai lần, Cấp trên - ba, Cấp trung - năm, Cấp dưới - bảy lần. Chứng minh rằng có một thời điểm tất cả chúng đều hướng về cùng một đích. 7. Chỉ rõ lũy thừa của 5 sao cho trong ký hiệu thập phân của nó sẽ có hơn 1000 số 0 liên tiếp. Và sao cho có sự kết hợp của chính xác 1000 số 0 liên tiếp? 8. Chứng minh rằng có lũy thừa của 3 bắt đầu bằng 1000 chữ số ở cuối. 9. Cho hai đường thẳng tạo thành một góc M. Một điểm M nằm trên một điểm và một con bọ chét đậu ở điểm này và nhảy từ đường thẳng này sang đường thẳng khác đúng 1 cm, và luôn đến một điểm khác điểm trước đó. Chứng minh rằng nếu con bọ chét quay lại điểm xuất phát thì số M S là số hữu tỉ. 10. Nếu cosin của một góc là 1 3 thì số đo của nó là vô tỉ. Chứng minh điều đó. Tóm tắt bài toán.
