---
id: 1985-7-uspenskiy-semenov-reshimyie-i-nereshimyie-algoritmicheskie-problemyi-5cc3054a
issue: kvant_1985_7
year: 1985
number: "7"
title: Các vấn đề thuật toán đã được giải quyết và không thể giải quyết được
authors:
  - Успенский В. А.
  - Семёнов А. Л.
rubric: osnovnye-stati
rubric_sub: Основные статьи
page_first: 11
page_last: 17
page_labels: 9-15
tag: 01S7
lang: vi
source: kvant_digital
extraction: vision
content_sha256: 3f41bd8ebcd5d27d13bd31dd0e3f6513ccf370ba460ba0a22bf0576d6dbc48f0
prompt_sha256: draft-1
translated_from: content/ru/1985/07/articles/05_uspenskiy-semenov-reshimyie-i-nereshimyie-algoritmicheskie-problemyi-5cc3054a.md
source_content_sha256: 844ff57fa59d28894c472be2803f9967f9104e0ff1ec67fad92ef7cc12780d3a
translation_model: draft
translation_run: vi-draft-2026-10-31
translation_quality: draft
---

⟦folio 9⟧

Quyết đoán
và không thể giải quyết được
thuật toán
vấn đề

Giáo sư
V. A. USPENSKY,
Tiến sĩ Khoa học Vật lý và Toán học
A. L. SEMENOV

Thuật toán

Tất cả chúng ta đều biết cách cộng các số có nhiều chữ số - chúng ta đã học điều này từ khi còn nhỏ. Chúng ta hãy tự hỏi, lời dạy của chúng ta là gì? Khi trong vở kịch "Bài học" của E. Ionesco, một học sinh thể hiện khả năng thay thế cho một biến số có mười chữ số, giáo viên bị sốc khi biết rằng phương pháp của cô rất đơn giản - cô đã học bảng nhân (vô hạn!) cho tất cả các số. Rõ ràng, phương pháp của chúng tôi là một loại khác. Chúng ta biết một cách hữu hạn duy nhất để giải tập vô hạn bài toán. Trong trường hợp của chúng tôi, tập hợp vô hạn được hình thành bởi bài toán và tìm tổng: cho mỗi cặp số - bài toán của chính nó. Phương pháp này thống nhất vì mọi người đều giống nhau bài toán. Phương pháp này hữu hạn theo nghĩa là nó có thể được biểu diễn bằng một số hữu hạn từ (và nếu không phải như vậy thì phương pháp này không thể dạy được!). Như bạn đã biết, phương pháp này được gọi là "cộng cột" và bao gồm thực tế là một số (ví dụ: 8257) được ký màu xanh lam bên dưới một số khác (ví dụ: 64) với biểu thức của cạnh phải (nghĩa là như thế này: 64/8357 chứ không phải như thế này: 64/8357) và sau đó bắt đầu ứng dụng tuần tự của bảng để cộng các số có một chữ số (phải được trừ trước) bằng cách chuyển, nếu cần, sang chữ số tiếp theo. Kết quả là số 8421 sẽ được hình thành.

Ở đây chúng tôi không phác thảo quá nhiều về phương pháp như đã nhớ lại, đảm bảo rằng nó đã được biết đến. Tuy nhiên, sẽ rất hữu ích nếu người đọc viết toàn bộ phương pháp này ra giấy để người chưa biết cách cộng các số có nhiều chữ số có thể hiểu và sử dụng. Bài tập mà chúng tôi đề xuất tới bạn đọc được xây dựng bằng ngôn ngữ khoa học như sau: viết ra một thuật toán giải

⟦folio 10⟧

bài toán cộng số. Chúng tôi sẽ trình bày rõ hơn vấn đề này và các vấn đề khác trong việc xây dựng thuật toán, chỉ ra những gì được yêu cầu đối với thuật toán, gần đúng theo dạng sau:

**Vấn đề. Cho: hai số tự nhiên tùy ý. Yêu cầu: tìm tổng của chúng.**

Dạng ký hiệu này sẽ đóng vai trò là tín hiệu cho chúng ta biết rằng bài toán lời giải không phải là tìm cách tính kết quả riêng cho mỗi hai số mà là tìm một phương pháp chung duy nhất phù hợp với tất cả các cặp số, tức là tìm một thuật toán (trong trường hợp này là thuật toán cộng).

Trong bài viết này, bằng thuật toán, chúng ta sẽ hiểu bất kỳ hệ thống quy tắc hữu hạn nào xác định một quy trình tính toán. Quá trình này bắt đầu bằng việc trình bày (gửi tới đầu vào của thuật toán) dữ liệu ban đầu tùy ý (nhưng được chọn từ một tập hợp cố định cho một thuật toán nhất định). Quá trình có thể kết thúc bằng việc nhận được kết quả hoàn chỉnh được xác định bởi dữ liệu ban đầu này; thì kết quả được gọi là đầu ra của thuật toán. Tuy nhiên, quá trình này có thể tiếp tục vô thời hạn; kết quả của thuật toán không phải lúc nào cũng tồn tại. Ví dụ: thuật toán tính thương của hai số dưới dạng phân số thập phân có thể không hoạt động (vì vậy 1:3=0,33333...).

Khái niệm thuật toán là một trong những khái niệm cơ bản của toán học. Lý thuyết về thuật toán, cùng với logic toán học, tạo thành cơ sở lý thuyết chức năng cho việc xây dựng và sử dụng công nghệ máy tính. Sự khởi đầu danh nghĩa của các thuật toán cho một số bài toán nhất định cho phép bạn giải các bài toán này trên máy tính.

Bản thân thuật ngữ “thuật toán” đã rất đáng chú ý. Trên thực tế, có nhiều thuật ngữ khoa học bao gồm tên địa lý không? Cái tên như vậy không thể được làm mịn ngay lập tức trong lớp “thuật toán”, nhưng nó ở đó - đây là tên của thành phố “Khorezm”. Xét cho cùng, thuật ngữ “thuật toán” được đặt theo tên của al-Khorezmi (có nghĩa là “từ Khorezm”), một nhà toán học vĩ đại của thế kỷ thứ 9. Các nhà toán học và thuật toán lớn nhất từ ​​​​khắp nơi trên thế giới đã vinh danh vai trò cơ bản của al-Khorezmi, đã tập trung vào tháng 9 năm 1979 tại vùng Khorezm của Uzbekistan, tại thành phố Urgench, nơi họ thảo luận các vấn đề về lý thuyết thuật toán và các ứng dụng của nó ở giai đoạn hiện tại. Một trong những người tổ chức nó, Viện sĩ A.P. Ershov, đã nói điều tương tự về cuộc họp này ở Urgench (xem «Kvant», 1984, số 8, trang 29).

Chúng tôi sẽ cho người đọc xem những ví dụ minh họa và quan trọng nhất về các vấn đề thuật toán không thể giải được, tức là các vấn đề thuật toán mà lời giải không tồn tại. Ngược lại, những ví dụ này sẽ chứa những ví dụ có thuật toán (mặc dù đôi khi rất phức tạp) hoặc câu hỏi liệu có thuật toán nào vẫn chưa được giải quyết hay không.

**Lời giải phương trình đại số**

Hãy viết ra phương trình

$$x^2 + 2 = y^3$$

(1)

và chúng tôi sẽ quan tâm đến quyết định của anh ấy. Lời giải trong trường hợp này là một cặp số (a; b) tuân theo điều kiện $a^2 + 2 = b^3$, ví dụ: một cặp (5; 3).

Khi giải bất kỳ phương trình nào, bạn phải luôn biết chính xác những con số nào có thể được sử dụng làm lời giải của nó. Ví dụ: nếu lời giải phương trình đóng vai trò là sự gia tăng số lượng dê trong một đàn như vậy trong một khoảng thời gian như vậy và như vậy, liệu tác hại có phù hợp với chúng ta không đáp số “hai phần ba” (nhưng đáp số “trừ mười” sẽ có ý nghĩa: điều đó có nghĩa là số lượng dê trong đàn, thật không may, không tăng mà lại giảm). Đối với phương trình (1), người ta có thể quan tâm đến nghiệm thực của nó, tức là tham số của số thực, nghiệm định vị, tức là tham số của số định vị, nghiệm số nguyên, tức là tham số của số nguyên. Phương trình (1) có vô số số thực lời giải: chỉ cần lấy a bất kỳ và đặt b = $\sqrt[3]{a^2 + 2}$ là đủ, khi đó cặp (a; b) sẽ là lời giải (câu hỏi dành cho người đọc: có thể lấy bất kỳ b nào và đặt a = $\sqrt{b^3 - 2}$?). Không khó để chứng minh rằng (1) có vô số tọa độ lời giải; đây là một trong số đó: (0,383; 0,129). Chỉ có hai mục tiêu lời giải: (5; 3) và (−5; 3). Tuy nhiên, điều này không dễ để chứng minh.

Lời giải phương trình trong số nguyên dường như rất cổ xưa (nó được chính Pythagoras nghiên cứu vào thế kỷ thứ 6 trước Công nguyên) và - trong trường hợp tổng quát - rất khó bài toán. Khó khăn chính là tìm ra liệu một phương trình đã cho có ít nhất một số nguyên lời giải hay không. Ví dụ, nó chưa được biết (ít nhất là nó chưa được biết cho đến khi so sánh)

⟦folio 11⟧

gần đây) có lời giải có $x^3+y^3+z^3=30$ và $x^4+y^4+z^4=u^4$ cho mục đích số học.

Bài toán cho người đọc. Đối với mỗi phương trình $x^4+y^4=5z^2$, $3x^2-y^2=1$, $x^2+y^3=z^4$, hãy tìm một số lời giải cho mục đích tính số hoặc chứng minh rằng lời giải đó không tồn tại.

Gợi ý. Bạn có thể đọc về những phương trình này và các phương trình khác cho mục đích số trong các tài liệu quảng cáo phổ biến: Gelfond A. O. “Lời giải phương trình cho mục đích số”, M., 1952. (loạt bài “Bài giảng phổ biến về toán học”, số 8); Serpisky V. “Về các phương trình lời giải cho mục đích số”, M., 1961.

Bài toán "có thể tìm ra từ một phương trình đại số tùy ý với mục đích hệ số xem nó có lời giải cho mục đích số hay không" tạo thành một trong hai mươi ba bài toán được gọi là "bài toán Hilbert". Vấn đề là gì?

Khi David Hilbert (1862–1943), một trong những nhà toán học vĩ đại nhất thế kỷ 20, chuẩn bị bài báo của mình tại Đại hội Toán học Thế giới ở Paris năm 1900, ông đã chọn ra 23 bài toán từ nhiều lĩnh vực toán học khác nhau. Những vấn đề này là nỗ lực của ông “nhằm thâm nhập vào các điều kiện sắp tới của khoa học của chúng ta và những bí mật về sự phát triển của nó ở giai đoạn sơ khai”. Nỗ lực này hóa ra cực kỳ thành công và có giá trị. Và cho đến ngày nay, lời giải (sau đây gọi là thương số) của bất kỳ bài toán nào của Hilbert đều được cả thế giới coi là thành tựu toán học cao nhất. Gilbert coi yêu cầu bắt buộc đối với một vấn đề cơ bản thực sự là “khả năng trình bày nội dung của nó cho người đầu tiên bạn gặp”. Bài toán về việc xác định sự có mặt của số nguyên lời giải là bài toán thứ mười trong danh sách của Hilbert. Người đọc có thể tự mình đánh giá mức độ mà công thức của nó mang tính xã hội. Bây giờ chúng ta sẽ xây dựng bài toán thứ mười của Hilbert theo các tiêu chuẩn được áp dụng ở đây.

Bài toán 1 (Bài toán thứ mười của Hilbert). Cho: một phương trình đại số tùy ý với các hệ số khách quan. Yêu cầu: tìm hiểu xem phương trình đã cho có lời giải cho mục đích số hay không.

Thuật toán yêu cầu: năm 1970, nhà toán học Liên Xô Yu. V. Matiyasevich đã chứng minh rằng không thể có một thuật toán giải quyết vấn đề này (xem «Kvant», 1970, số 7, trang 39).

Liên quan đến việc hình thành vấn đề, việc áp dụng một sự thay thế không chỉ cho nó mà còn với những thay đổi thích hợp trong các trường hợp khác là phù hợp. Đã tồn tại một thuật toán để tìm một số lời giải của bất kỳ phương trình nào được biết là có lời giải! Một thuật toán hiệu quả là thế này: bạn chỉ cần thay thế tất cả các bộ số tự nhiên vào phương trình. Cuối cùng sẽ tìm được tập hợp thỏa mãn phương trình.

Hãy để chúng tôi trình bày một số sửa đổi tự nhiên của vấn đề đầu tiên.

Bài 2. Cho: phương trình đại số tùy ý có hệ số khách quan. Yêu cầu: tìm hiểu xem phương trình này có lời giải ở dạng số thực hay không.

Thuật toán bạn đang tìm kiếm: tồn tại!

Lời giải bài toán 2 được người dùng nổi tiếng Alfred Tarski lấy được vào những năm 40 của thế kỷ 20. Việc áp dụng kết quả này sẽ được thảo luận thêm. Trên thực tế, Tarski đã xây dựng một thuật toán tổng quát hơn để xác định sự hiện diện của lời giải trong các hệ đẳng thức và bất đẳng thức.

Để đánh giá mức độ không tầm thường của thuật toán Tarski, hãy thử giải bài toán sau. Cho một phương trình đại số tùy ý với tất cả các hệ số và một hệ số chưa biết, bạn cần tìm hiểu xem liệu nó có lời giải trong số thực hay không. (Rõ ràng bài toán này là một trường hợp đặc biệt đơn giản của Bài toán 2). Nếu bậc của phương trình là số lẻ, bạn có thể trả lời ngay rằng nghiệm của phương trình có tồn tại. Nếu là một cặp thì sao?

Bài 3. Cho: phương trình đại số tùy ý có hệ số khách quan. Yêu cầu: tìm hiểu xem phương trình này có lời giải ở dạng số hữu tỷ hay không.

Thuật toán bạn đang tìm kiếm: nó có tồn tại hay không thì chưa xác định được.

Hãy xem công thức của các bài toán 1, 2 và 3 của chúng ta gần nhau đến mức nào: những công thức này chỉ khác nhau một từ. Và tuy nhiên, đáp số khác nhau như thế nào khi được hỏi liệu thuật toán tương ứng có tồn tại hay không. Khái niệm này thật tuyệt vời!

⟦folio 12⟧

Chuyển đổi từ

Trong toán học, từ là bất kỳ chuỗi ký hiệu hữu hạn nào. Ví dụ: 1985 là một từ có độ dài 4. Các từ không những không cần phải có nghĩa mà thậm chí còn có thể phát âm được. Vì vậy, BRDROBSH là một từ được tạo thành từ các chữ cái tiếng Nga (và hơn nữa, có độ dài 8), mặc dù không phải là một từ trong tiếng Nga. Thông thường, dữ liệu đầu vào cho thuật toán là từ. Khi một thuật toán được xác định, một tập hợp các chữ cái cũng được xác định, tức là các ký hiệu tạo nên các từ được cung cấp cho nó làm đầu vào. Một bộ như vậy được gọi là bảng chữ cái. Các bảng chữ cái trong đó văn bản được viết bằng ngôn ngữ tự nhiên và ngôn ngữ lập trình cũng như sách được in ra không quá vài trăm chữ cái. Số có nhiều chữ số trong thuật toán “trường học” là các từ trong bảng chữ cái mười chữ cái gồm các chữ cái 0, 1, 2, ..., 9; những chữ cái này, như bạn biết, được gọi là số; và để viết phân số thập phân, ngoài mười chữ số này, người ta còn sử dụng một chữ cái khác - dấu phẩy.

Máy tính hiện đại hoạt động với các từ kép bao gồm các chữ cái 0 và 1. Để minh họa tính linh hoạt và khả năng của khái niệm “từ”, hãy lưu ý rằng một cặp từ có thể được mã hóa thành một từ, chẳng hạn bằng cách đặt giữa các thành viên của cặp một chữ cái không thuộc bảng chữ cái mà các thành viên này được viết. Như vậy, chỉ cần coi các từ là dữ liệu ban đầu cho thuật toán là đủ, nhưng không cần phải xem xét các cặp, bộ ba, v.v. của các từ trong khả năng này. Chúng ta cũng hãy lưu ý rằng việc xem xét các từ có độ dài sàn thường rất thuận tiện; nó được gọi là từ trống vì nó không chứa chữ cái nào cả.

Nhiều bạn đã chơi trò chơi sau. Một nhiệm vụ được đưa ra, chẳng hạn như “chuyển sói sang dê”. Lời giải:

Một bước tu sửa là gì? - Thay thế bất kỳ chữ cái nào của một từ đã thu được bằng bất kỳ chữ cái nào khác trong bảng chữ cái tiếng Nga, và sao cho đối tượng thu được (một từ theo nghĩa toán học của từ đó) hóa ra là một từ có nghĩa của tiếng Nga.

Bây giờ, hãy đơn giản hóa trò chơi - hãy quên rằng trong số tất cả các chuỗi chữ cái, các từ trong tiếng Nga được đánh dấu. Chúng tôi sẽ coi tất cả các từ (theo nghĩa toán học, nghĩa là cả có ý nghĩa và vô nghĩa) trong bảng chữ cái tiếng Nga là như nhau. Vậy có thể biến sói thành dê được không? Chà, bây giờ thì khá dễ dàng:

SÓI→KOLK→DÊ→DÊ

Biết đâu bây giờ từ nào cũng có thể đổi thành từ nào? Tất nhiên là không - các từ phải có cùng độ dài. Nhưng điều kiện này là đủ!

Vấn đề. Cho: hai từ trong bảng chữ cái tiếng Nga. Bạn cần tìm hiểu xem một trong những cái còn lại có phải là một chuỗi thay thế từng chữ cái hay không.

Thuật toán bắt buộc: so sánh độ dài của các từ, nếu chúng khớp nhau thì đáp số CÓ, nếu chúng không khớp thì đáp số KHÔNG.

Lưu ý rằng vấn đề ban đầu là làm lại một từ nhất định trong tiếng Nga; Cũng rất hiếm khi chỉ có một cuốn từ điển (hữu hạn!) gồm tất cả các từ trong tiếng Nga có thể sử dụng trong trò chơi và có đủ thời gian và giấy tờ. Một phép tính đơn giản cho thấy rằng bài toán này có thể áp dụng thực tế lời giải trên các máy tính ngày nay.

Bây giờ, tôi lại quên mất tiếng Nga (nhưng không quên bảng chữ cái tiếng Nga) và theo các từ của khái niệm dãy hữu hạn tùy ý các chữ cái tiếng Nga, các điều kiện bài toán giới tính; nó được gọi là từ trống vì nó không chứa chữ cái nào cả.

Việc chuyển đổi một từ trong một bước, như trước đây, sẽ bao gồm thực tế là ở bất kỳ đâu trong từ, chúng ta thay thế phần được phép thay thế bằng phần được phép thay thế. Trong trường hợp này, tất cả các thay thế được phép đều có tính chất hai mặt: nếu phần X được phép thay thế bằng phần Y thì phần Y cũng được phép thay thế bằng phần X. Ví dụ: nếu

⟦folio 13⟧

Vì các phép thay thế được phép giống như chúng ta vừa chọn nên phép biến đổi trong một bước có thể như sau: BAAB - BBBBB, hoặc như thế này: BAB - ABAB, hoặc như thế này: BABA - BAAAA.

Vấn đề. Cho: hai từ trong bảng chữ cái tiếng Nga. Yêu cầu: tìm hiểu xem cái này có thể được chuyển sang cái khác hay không, sử dụng hệ thống thay thế được phép sau đây:

AB BB AY BỞI DBA DYB BBA
BA BB YA YB BD YD BBA

Thuật toán tìm kiếm: không tồn tại. Điều này đã được chứng minh bởi nhà toán học Liên Xô G.S. Tseytin, người đã đưa ra hệ thống thay thế được chỉ định.

Một bài toán tương tự ở dạng tổng quát (tức là bất kỳ hệ thay thế nào được phép) lần đầu tiên được đặt ra bởi nhà toán học nổi tiếng người Na Uy Axel Thueve vào năm 1914. Chính ông đã chứng minh sự tồn tại của thuật toán trong một số trường hợp đặc biệt.

Thue đặc biệt nhấn mạnh trường hợp khi trong mỗi sự thay thế được phép, một trong các thuật ngữ là một từ trống và do đó, mọi sự thay thế được phép bao gồm thực tế là bạn có thể chèn từ được chỉ định trong từ thay thế vào bất kỳ vị trí nào trong một từ hiện có hoặc gạch bỏ nó. Ví dụ: bằng cách chèn và gạch bỏ các từ AB và BA, bạn có thể nhận được BABAB từ từ ABBBA. Đang cố gắng xây dựng thuật toán cần thiết để chèn và xóa AB và BA, nghĩa là đối với danh sách các thay thế được phép như vậy:

AB
từ trống
VA
từ trống

(Ngay cả ví dụ đơn giản nhất này cũng quan trọng đối với nhánh đại số được gọi là “lý thuyết nhóm”.)

Đối với bất kỳ tập hợp chèn và xóa được phép nào, tồn tại một thuật toán xác định xem một từ có thể được chuyển sang từ khác hay không. Điều này đã được nhà toán học Liên Xô S.I. Adyan chứng minh vào năm 1966.

Hình học cơ bản

Ở đây chúng ta không có cơ hội đưa ra một định nghĩa chi tiết về hình học cơ bản theo nghĩa chặt chẽ, được làm rõ với sự trợ giúp của logic toán học. Tuy nhiên, chúng tôi sẽ cố gắng đưa ra một mô tả gần đúng. Các khái niệm ban đầu của hình học cơ bản là điểm, đường thẳng, mặt phẳng, đoạn thẳng, đường tròn, hình cầu, các quan hệ “nằm trên”, “nằm giữa”, “bị tắc nghẽn”, v.v. Cho phép hình thành các khái niệm mới - nhưng không sử dụng hình elip và cụm từ “v.v.” (tại thời điểm này, ý tưởng logic toán học chặt chẽ của hình học cơ bản khác với hình học truyền thống mờ). Ví dụ, khái niệm hình tam giác thuộc về hình học cơ bản: suy cho cùng, một hình tam giác có thể được định nghĩa là ba đoạn $A_1A_2$, $A_3A_4$, $A_5A_6$, chẳng hạn như $A_2=A_3$, $A_4=A_5$, $A_6=A_1$. Nhưng khái niệm chung về đường đứt nét không thuộc về hình học cơ bản, bởi vì định nghĩa của nó liên quan đến dấu chấm lửng và các từ “v.v.”: đường đứt nét là một tập hợp các đoạn trong $A_1A_2$, $A_3A_4$,... (dấu chấm lửng ở đây!), $A_{n-1}$, $A_n$, sao cho $A_2=A_3$, $A_4=A_5$, v.v.

Vấn đề. Cho: một phát biểu về hình học cơ bản. Yêu cầu: kiểm tra xem nó có đúng không.

Thuật toán bắt buộc: tồn tại.

Sự tồn tại của thuật toán về cơ bản đã được Tarski thiết lập vào những năm 40 của thế kỷ chúng ta. Nó suy ra khá đơn giản từ sự tồn tại của thuật toán Tarski đã đề cập trước đó. Mối liên hệ giữa các bài toán đại số và hình học đã được phát hiện từ lâu (hình học giải tích) và đương nhiên nó mở rộng sang các bài toán thuật toán.

Kết quả của Tarski thực sự có vẻ cực kỳ mạnh mẽ và thậm chí nghịch lý. Hóa ra có một lĩnh vực rộng lớn của toán học cổ điển (cụ thể là hình học cơ bản), theo truyền thống được cho là đòi hỏi trí thông minh tinh tế và chắc chắn không tương ứng với loại phép tính, đồng thời có một thuật toán có thể kiểm tra tính đúng đắn của các định lý trong lĩnh vực này (và nếu cần, hãy tìm kiếm bằng chứng của chúng). Điều an ủi duy nhất là thuật toán của Tarski không có thật: nó đòi hỏi một thời gian cực kỳ dài để thực hiện.

Thật hữu ích khi tưởng tượng xem những câu lệnh hình học đó bắt đầu “gần gũi” như thế nào, mặc dù có sự tồn tại của một thuật toán chung,

⟦folio 14⟧

nhịp điệu, sự thật hay giả của họ bây giờ vẫn chưa được biết.

Đây là một ví dụ rõ ràng. Hãy lấy một động cơ gồm các hộp tròn có cùng đường kính (bằng 10 cm). Chúng tôi muốn đóng gói chúng, dựng đứng chúng trong một chiếc hộp tròn. Điều này có thể được thực hiện, ví dụ như được hiển thị trong hình 1). Tuy nhiên, bạn có thể sắp xếp các lọ chặt chẽ hơn - để có được một chiếc hộp nhỏ hơn kích thước của nó. Ví dụ: như được hiển thị trong hình 2. Cuối cùng, bao bì được hiển thị trong hình 3 cho phép bạn sử dụng hộp thậm chí còn nhỏ hơn. Câu hỏi đặt ra là liệu có thể tìm được một chiếc hộp tròn có đường kính nhỏ hơn nữa để vừa với tất cả các chiếc lọ của chúng ta không? Đáp số không biết về câu hỏi này, mặc dù đáp số này có thể đạt được bằng thuật toán Tarski: chúng ta cần áp dụng thuật toán này cho tuyên bố rằng gói thứ ba là tốt nhất và xem kết quả sẽ xảy ra như thế nào. CÓ hoặc KHÔNG. Tuy nhiên, phương pháp này không được triển khai vì phải mất nhiều thời gian hơn về mặt thiên văn để thu được kết quả của thuật toán.

Một ví dụ về bằng chứng của sự thiếu quyết đoán

Giả sử rằng chúng ta đang làm việc trong Trung tâm Máy tính. Trung tâm này có một Máy tính tuyệt vời. Nó có thể thực hiện các phép tính trên bất kỳ chương trình $p$ nào được viết bằng một số Ngôn ngữ lập trình, nghĩa là sử dụng dữ liệu đầu vào $m$, nó sẽ tìm thấy kết quả $p(m)$ của chương trình $p$ (tất nhiên là nếu nó được xác định).

Các chương trình có thể được sắp xếp lại (ví dụ: theo thứ tự bảng chữ cái, vì mỗi chương trình có thể được coi là một từ trong ký hiệu của Ngôn ngữ lập trình), tạo Thư viện trong tất cả các chương trình:

$$p_1, p_2, p_3, \dots, p_n, \dots$$

Tốt nhất là xử lý các chương trình $p$ mà với bất kỳ đầu vào nào được cung cấp $m$, sẽ tạo ra kết quả $p(m)$. Ví dụ: đây là chương trình tiêu chuẩn để tính hàm $y=m^2+5m-6$. Thật không may, cũng có những chương trình, đối với một số giá trị nhất định của dữ liệu đầu vào, không hoàn thành công việc của chúng; chúng “đi theo chu kỳ,” như chương trình nói. Do đó, chương trình tính ký hiệu thập phân của hàm $y=m/3$ không tạo ra kết quả cho $m=10$.

Đây là một tình huống rất khó chịu. Suy cho cùng, nếu chúng ta nhập một chương trình như vậy vào Máy tính cùng với dữ liệu ban đầu “xấu” như vậy thì công việc của Máy tính sẽ không kết thúc chút nào và chúng ta sẽ chỉ lãng phí Thời gian Máy đắt tiền.

Để tránh điều này, tốt nhất nên có một số quy trình (thuật toán!), dựa trên số chương trình, sẽ chuẩn bị trước xem chương trình có số này có cho kết quả hay không với dữ liệu đầu vào đã chọn.

Vấn đề. Cho: một cặp số tự nhiên tùy ý $(n, m)$. Yêu cầu: xây dựng một thuật toán để tìm hiểu xem chương trình thứ $n$ $p_n$ có ​​kết thúc với dữ liệu đầu vào $m$ hay không.

Thuật toán chúng tôi đang tìm kiếm: không tồn tại và bây giờ chúng tôi sẽ chứng minh điều đó.

Bằng chứng. (Diazonal Cantopa). Giả sử rằng thuật toán yêu cầu A tồn tại. Hãy tạo một bảng gồm tất cả các chương trình và dữ liệu nguồn:

⟦folio 15⟧

Hãy xem xét chương trình $\bar{p}$, kết quả của nó là “không giống như trên đường chéo”, nghĩa là chúng ta được xác định bằng cách sửa

$$\bar{p}(m) = \begin{cases} p_m(m) + 1, & \text{ если } p_m(m) \text{ определено, } 0 \\ 0, & \text{ если } p_m(m) \text{ не определено.} \end{cases}$$

Đây là một chương trình thực, nghĩa là $p$ được tính toán bằng thuật toán. (Cụ thể là thế này: chúng ta kiểm tra điều kiện $p_m(m)$ được xác định bằng thuật toán $A$, nếu thỏa mãn thì chúng ta tính $p_m(m)$ và thêm một, nếu không, chúng ta giả sử $\bar{p}(m) = 0$). Nhưng sau đó $\bar{p}$ được đưa vào danh sách tất cả các chương trình Viblotekka, dưới một số con số. Hãy biểu thị số này bằng $k$ và xem xét $p_k(k)$ (phần tử đường chéo!).

Nếu $p_k(k)$ không được xác định thì $\bar{p}(k) = 0$ và do đó $\bar{p}(k) \neq p_k(k)$.

Nếu $p_k(k)$ được xác định thì $\bar{p}(k) = p_k(k) + 1 \neq p_k(k)$.

Trong cả hai trường hợp, $\bar{p}(k) \neq p_k(k)$ là không thể, hoặc $\bar{p}$ và $p_k$ là cùng một chương trình. Mâu thuẫn này hoàn thành chứng minh.

Người đọc có thể muốn biết tại sao chứng minh trên được gọi là "đường chéo" của Cantor. Thực tế là phương pháp chứng minh tao nhã được sử dụng ở đây được phát minh bởi nhà toán học người Đức Georg Cantor (1845-1918), người sáng lập lý thuyết tập hợp. Đúng, Cantor đã đưa ra một tuyên bố hoàn toàn khác. Cụ thể là tập hợp số thực không thể bị nhầm lẫn với số tự nhiên, tức là lập danh sách tất cả các số thực: $a_1, a_2, a_3, \dots$ (Người đọc đã thấy kết quả này từ lâu - “xét cho cùng, có nhiều số thực hơn số tự nhiên”, chúng tôi khuyên bạn nên chứng minh rằng tất cả các số hữu tỷ đều có thể bị nhầm lẫn - mặc dù chúng cũng “lớn hơn số tự nhiên một cách đáng tự hào”).

Theo Cantor, chúng ta sẽ chứng minh (bằng phản chứng) rằng ngay cả tập số thực trên khoảng [0,1] cũng không thể bị nhầm lẫn. Giả sử rằng chúng ta đã làm được điều này. Hãy sắp xếp các số của chúng ta, giả sử số đó là 0,abc trong đó $a$ là bất kỳ chữ số nào khác ngoài $a_1$; $b$ — bất kỳ số nào khác ngoài $b_2$; $c$ là bất kỳ số nào khác ngoài $c_3$, v.v. Mâu thuẫn!

Hãy lấy một ít cổ phiếu. Chúng ta đã làm quen với khái niệm thuật toán - khái niệm quan trọng nhất của toán học và khoa học máy tính hiện đại. Tất nhiên, nhiều thuật toán cụ thể (ví dụ: thuật toán cộng cột hoặc thuật toán Euclid để tìm số đo tổng quát) đã được biết đến từ rất lâu, nhưng ý tưởng chung về thuật toán chỉ được hình thành trong nửa đầu thế kỷ 20. Mọi nỗ lực sử dụng máy tính cho lời giải bất kỳ bài toán nào đều bắt đầu bằng việc xây dựng thuật toán giải các bài toán này. Chừng nào không có thuật toán như vậy thì không thể soạn chương trình cho máy tính. Và nếu hóa ra một thuật toán là cần thiết và không thể tồn tại, thì việc cố gắng soạn thảo một chương trình là vô nghĩa. Vì vậy, kết quả về tính bất khả thi của một số thuật toán nhất định có ý nghĩa rất thực tế. Ngoài ra, lý do dẫn đến việc xác lập điều không thể xảy ra như vậy cho phép chúng ta đi sâu hơn vào bản chất của chính khái niệm “thuật toán”.

Người đọc có thể đặt câu hỏi: có thể chạy bất kỳ thuật toán nào trong một chương trình máy tính không? Đáp số: về mặt lý thuyết - đúng vậy. Từ “về mặt lý thuyết” ở đây có nghĩa là đáp số là khẳng định, nếu chúng ta cho phép các chương trình có độ dài phù hợp bất kỳ (để viết mà không có đủ giấy, mực và bút chì trên toàn bộ Trái đất) và trong bất kỳ khoảng thời gian nào (nghìn tỷ năm). Lưu ý rằng những giả định kiểu này có nguồn gốc sâu xa từ toán học. (Chúng tôi cho phép đa giác có số cạnh bất kỳ. Chúng tôi tin rằng thuật toán cộng cột cho phép các số có kích thước bất kỳ, mặc dù chúng tôi biết rằng nếu những đa giác bị suy yếu có dấu lớn hơn các Nguyên tử trên Trái đất, thì không hoàn toàn rõ ràng cách viết các thuật ngữ như vậy và số lượng quả bóng khi thêm chúng sẽ trở nên lớn về mặt thiên văn...) Ngoài ra, khả năng của công nghệ máy tính không ngừng phát triển. Nếu những chiếc máy tính đầu tiên thực hiện hàng trăm thao tác mỗi giây và được điều khiển bởi các chương trình gồm hàng chục lệnh, thì những chiếc máy hiện đại nhanh chóng đạt tới hàng trăm triệu thao tác mỗi giây và kích thước chương trình của chúng lên tới hàng trăm nghìn lệnh. Thật vui khi nghĩ rằng khả năng của máy sẽ tăng gấp 10 lần sau mỗi 5 năm. Tuy nhiên, tất nhiên, các ước tính và kích thước của thuật toán cũng như số lượng quả bóng mà nó vận hành là hết sức quan trọng. Nhưng đây là chủ đề dành cho các cuộc thảo luận riêng về máy chủ.
