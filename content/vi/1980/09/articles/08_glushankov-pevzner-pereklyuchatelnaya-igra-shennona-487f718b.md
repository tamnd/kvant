---
id: 1980-9-glushankov-pevzner-pereklyuchatelnaya-igra-shennona-487f718b
issue: kvant_1980_9
year: 1980
number: "9"
title: Trò chơi chuyển đổi Shannon
authors:
  - Глушанков Е.
  - Певзнер П. А.
rubric: osnovnye-stati
page_first: 16
page_last: 22
page_labels: 14, 15, 16, 17, 18, 20
tag: Q02F
lang: vi
source: kvant_digital
extraction: vision
content_sha256: 7dbbf347cb7c58c0248ab2b71083a9615ca4f92e31a2a5807fe955bf74bc562e
prompt_sha256: draft-1
translated_from: content/ru/1980/09/articles/08_glushankov-pevzner-pereklyuchatelnaya-igra-shennona-487f718b.md
source_content_sha256: 8582c290bdfc67596a6df1ed260d51d2ec09636b38ca3b2c43be2ae6180199de
translation_model: draft
translation_run: vi-draft-2026-10-31
translation_quality: draft
---

⟦folio 14⟧

E. Glushankov,
P. Pevzner

Trò chơi chuyển đổi của Shanon

Có thể thực hiện được mà không cần tìm kiếm đầy đủ?

Sự phát triển nhanh chóng của sản xuất, kinh tế và vận tải trong thế kỷ 20 đã đặt ra những vấn đề mới cho toán học. Làm thế nào để quản lý một doanh nghiệp hiện đại, làm thế nào để lập kế hoạch cho một nhóm công việc lớn, làm thế nào để tạo ra một lịch trình tàu thuận tiện - các kỹ sư bắt đầu tìm đến các nhà toán học với tất cả những câu hỏi này. Tuy nhiên, các phương pháp của toán học cổ điển, chủ yếu dành cho lời giải bài toán vật lý và cơ học, không thể trả lời đáp số những câu hỏi như vậy. Điều này dẫn đến sự xuất hiện của các ngành toán học mới - lý thuyết trò chơi, lý thuyết đồ thị, lý thuyết mã hóa và nhiều ngành khác, hiện được thống nhất dưới cái tên “toán học rời rạc”.

Công trình đầu tiên về toán học rời rạc (thuộc về Leonhard Euler), xuất hiện vào năm 1736, được dành cho câu đố nổi tiếng về các địa điểm ở Königsberg: liệu có thể đi dạo quanh Königsberg (sơ đồ thành phố được thể hiện trong hình) theo cách mà bạn rời khỏi nhà, quay trở lại, sau khi đã đi qua từng địa điểm một lần không? Trong một thời gian dài, toán học rời rạc hầu như chỉ quan tâm đến các câu đố, và do đó được xếp vào vị trí Cô bé Lọ Lem trong số các nhà toán học máy chủ. Tuy nhiên, vào thế kỷ 19, các phương pháp rời rạc đã được sử dụng trong nghiên cứu mạch điện tử và mạch phân tử trong hóa học.

Việc tính toán thực sự của toán học rời rạc đã được quan sát thấy trong hai hoặc ba thập kỷ qua. Vật lý, hóa học, lập trình, kinh tế, di truyền học, xã hội học, ngôn ngữ học

⟦folio 15⟧

Chà, phản biện chỉ là một phần của một danh sách dài các ngành khoa học sử dụng các phương pháp toán học rời rạc.

Gần đây, các ngoại tác phổ quát đã thu hút một số bài toán cổ điển của toán học rời rạc, vốn đã chờ đợi lời giải của chúng trong hơn một trăm năm. Tất cả những bài toán này được đặc trưng bởi thực tế là nếu được đưa ra một “ứng cử viên cho đáp số”, thì rất dễ kiểm tra xem đó có thực sự là đáp số hay không, nhưng rất khó tìm thấy đáp số như vậy; thực sự đến để sắp xếp từng lựa chọn có thể có.

Một mặt, con người hầu như phải đối mặt với những vấn đề toán học thú vị hàng ngày. Đây là cuộc tìm kiếm bài toán để chứng minh định lý này. Trên thực tế, nếu đưa ra bằng chứng thì về nguyên tắc không khó để kiểm chứng tính đúng đắn của nó. Bạn chỉ cần đảm bảo rằng mỗi bước được thực hiện theo các quy tắc logic và các câu lệnh trung gian tuân theo các tiên đề và định lý đã biết. Nhưng làm thế nào để tìm ra bằng chứng này? Có cần thiết phải xem xét tất cả các lập luận có thể có, bắt đầu từ các tiên đề không? Nếu ai đó có thể giải thích cách anh ta "đoán" bằng cách giải bài toán, có lẽ điều đó có thể giúp các nhà toán học dạy một cỗ máy làm điều tương tự.

Đây là một ví dụ đơn giản hơn: bài toán về phân vùng. Cho $A = \{s_1, \dots, s_N\}$ là tập hữu hạn chứa các số tự nhiên. Cần phải chia tập hợp $A$ thành hai tập con $I$ và $J$ ($I \cap J = \emptyset$, $I \cup J = A$) sao cho tổng các phần tử từ $I$ bằng tổng các phần tử từ $J$. Như trong ví dụ trước, đối với một phân vùng nhất định của tập hợp $A$ thành tập hợp $I$ và $J$, rất dễ dàng để kiểm tra xem các tổng tương ứng có bằng nhau hay không. Nhưng làm thế nào để tìm được phân vùng cần thiết? Thật không may, khoa học chưa thể đưa ra điều gì tốt hơn đáng kể so với việc thử tất cả các lựa chọn $2^N$. Nhưng ngay cả với $N = 100$ một chiếc máy tính hiện đại, cũng sẽ phải mất hàng tỷ năm để xác minh một phép liệt kê như vậy.

Hiện nay người ta tin rằng đối với một số bài toán (ví dụ: bài toán về phân vùng), không có gì tốt hơn đáng kể so với tìm kiếm toàn diện có thể được đề xuất. Đó là lý do tại sao mọi ví dụ về một thuật toán hiệu quả trong tình huống mà trước đây chúng ta bằng lòng với vũ lực đều được khoa học rất quan tâm, ngay cả khi bản thân tình huống đó là “đồ chơi”. Một ví dụ như vậy sẽ được thảo luận trong bài viết này.

Vào đầu những năm 50, nhà toán học và kỹ sư xuất sắc người Mỹ, người sáng tạo ra lý thuyết thông tin, Claude Chenon, đã đề xuất một sơ đồ liệt kê các phương án cho một chương trình cờ vua. Hầu như tất cả các chương trình cờ vua hiện đại đều theo sơ đồ này. Tuy nhiên, số lượng tùy chọn được lặp lại thông qua các chương trình chạy theo thuật toán Shenon hóa ra lớn đến mức cả bộ nhớ và tốc độ của máy tính hiện đại đều không đủ để thực hiện chúng.

Shannon đang cố gắng áp dụng phương pháp của mình vào một số trò chơi khác. Ông đã xem xét một trò chơi trên đồ thị, trò chơi này ngày nay được gọi là Cenon chuyển mạch của Chenon (viết tắt là SCH).

Hiện nay, một số phương pháp lập trình trò chơi đã được đề xuất. «Kvant» đã viết về một phương pháp dựa trên phép liệt kê mà không có các tùy chọn không hứa hẹn (theo một số quan điểm). Một phương pháp khác (dựa trên nó vào giữa những năm 60, A. Lehman đã đề xuất “người chơi lý tưởng” trong NSP), liên quan đến việc bác bỏ hoàn toàn các lựa chọn liệt kê, dựa trên một số kết quả mới của toán học rời rạc.

Bên dưới, chúng tôi sẽ cho bạn biết cách bạn có thể chơi PIS mà không cần thông qua các tùy chọn.

Bridget

Vào cuối những năm 50, American Gale đã nghĩ ra trò chơi Bridge-it. Trường tiêu chuẩn để chơi Bridge-it được hiển thị trong Hình 1. Một người chơi nối các dấu chấm bằng bút chì màu xanh, người còn lại - bằng bút chì màu đỏ, nối các dấu chấm màu đỏ. Họ lần lượt “đi bộ” (tức là chơi các phân đoạn) của trò chơi. Người chiến thắng là người đầu tiên dựng được đường đứt nối hai cạnh đối diện cùng màu của mình (Hình 2, trận đấu kết thúc với chiến thắng thuộc về Quỷ đỏ).

*) R. S. Guter, M. V. Donskoy Máy chơi cờ («Kvant», 1974 số 11).

⟦folio 16⟧

Hãy thử chơi bridge-it trên các sân nhỏ (Hình 3) để hiểu người chơi nào có lợi thế hơn trong trò chơi này, sau đó cố gắng phát triển chiến lược giành chiến thắng cho người chơi này.

Bài toán 1. Chứng minh rằng không có “hòa” trong trò chơi bridge-it.

Nếu không có “người” nào trong hội thánh thì một trong các hội thánh đã có chiến lược chiến thắng. Thật vậy, chẳng hạn, giả sử người chơi $A$ không có chiến lược chiến thắng, nghĩa là đối với bất kỳ nước đi nào của mình, người chơi $B$ có đáp số sao cho trò chơi sẽ không kết thúc với chiến thắng $A$. Vì giả định rằng không có “hòa” trong trò chơi đang được xem xét nên trò chơi sẽ kết thúc với phần thắng thuộc về người chơi $B$, tức là $B$ có trình tự nước đi mà dù $A$ chơi thế nào thì $B$ vẫn sẽ thắng. Như vậy, người chơi $B$ có chiến lược chiến thắng.

Lý do vừa đưa ra là bằng chứng thuần túy về sự tồn tại: người ta đã chứng minh rằng có một chiến lược, nhưng không có từ nào về cách tìm ra nó. Nhưng đây là câu hỏi thú vị nhất.

NIPSH

Để mô tả chiến lược chiến thắng khi chơi Bridge-it, hãy chuyển từ Bridge-it sang PIP. Để làm được điều này, hãy thay đổi luật chơi một chút. Trong Hình 4, tất cả các nước đi có thể có của người chơi “xanh” được đánh dấu bằng các đoạn màu xanh lam và của người chơi “đỏ” - bằng các đoạn màu đỏ. Chúng ta sẽ gọi những hình vẽ như vậy là “đồ thị của những bước đi có thể xảy ra”. Nếu bạn đã chơi bridge-it, thì có lẽ bạn đã nhận ra rằng việc người chơi thực hiện các phân đoạn được chỉ ra trong hình 4 theo từng điểm là vô nghĩa. Do đó, chúng ta đừng xem xét chúng chút nào và hãy làm như sau: hãy kéo tất cả các điểm trên cùng thành một và thực hiện tương tự với các điểm bên trái, bên phải và dưới cùng (Hình 5). Bây giờ, mục tiêu của người chơi “xanh” là kết nối các đỉnh $s$ và $t$ với một đường dẫn có các cạnh màu xanh lam và mục tiêu của người chơi “đỏ” là kết nối các đỉnh $s'$ và $t'$ với đường dẫn màu đỏ.

Lưu ý rằng mỗi đường màu đỏ giao nhau đúng một đường màu xanh. Do đó, nếu người chơi “đỏ” thực hiện một nước đi, thì điều này về cơ bản có nghĩa là anh ta không thể thực hiện một (và chỉ một) nước đi của người chơi “xanh”, tức là, người chơi “đỏ” với nước đi của mình giống như vẽ một cạnh của biểu đồ màu xanh. Nhưng thay vì gạch bỏ cạnh màu xanh, bạn có thể sơn nó màu đỏ. Bây giờ chúng ta có thể loại bỏ hoàn toàn biểu đồ màu đỏ khỏi Hình 5 và giả sử trò chơi diễn ra như sau:

Hai người chơi lần lượt tô màu các cạnh của biểu đồ trong đó các đỉnh $s$ và $t$ được đánh dấu: một màu xanh lam, một màu đỏ (Hình 6). Mục tiêu của người chơi “xanh” là kết nối các đỉnh đã chọn bằng *) từ các cạnh màu xanh lam và mục tiêu của người chơi “đỏ” là đặt chúng (chúng ta sẽ làm rõ điều này có nghĩa là gì sau).

*) Hãy nhớ lại rằng đồ thị là một tập hợp hữu hạn các điểm (đỉnh của đồ thị) và các đoạn nối chúng (cạnh của đồ thị). Đường dẫn là một đường trên biểu đồ không đi qua bất kỳ cạnh nào nhiều hơn một lần.

⟦folio 17⟧

Đây là công tắc Izra Shenon PISH). Chỉ Shenon đề xuất nó theo một công thức tổng quát hơn: thứ nhất, bạn có thể chơi trên bất kỳ biểu đồ nào và thứ hai, bạn có thể chọn bất kỳ cặp đỉnh nào trên một biểu đồ nhất định.

Mỗi biểu đồ có hai đỉnh hiển thị xác định một biến thể nhỏ của PIP. Nước đi đầu tiên trong mỗi biến thể có thể được thực hiện bởi bất kỳ người chơi nào - cả “xanh” và “đỏ”. Vì người chơi "màu xanh" kết nối các đỉnh nên anh ta được gọi một cách thích hợp là Connection hoặc C-ceroc. Và chúng ta sẽ gọi người chơi màu đỏ là Cut hoặc P-cerok.

Một điều khá rõ ràng là không có “không có gì” trong NSP - C sẽ kết nối các đỉnh được nhìn thấy hoặc không. Do đó, một trong những người chơi trong NSP có chiến lược chiến thắng. Nhưng cái nào? Làm thế nào để tìm ra chiến lược này?

Phân loại các biến thể NSP
Lưu ý rằng nếu người đứng thứ hai có chiến lược chiến thắng thì anh ta cũng có chiến lược đó trong trường hợp người đứng thứ nhất. Thật vậy, cerok là người đầu tiên, anh ta sẽ sơn lên bất kỳ cạnh nào bằng màu sắc của mình, và sau đó anh ta sẽ phản ứng với các bước đi của đối thủ giống như anh ta sẽ làm nếu anh ta chơi thứ hai. Nếu ở một bước nào đó cần vẽ một cạnh mà anh ta đã vẽ trước đó thì anh ta sẽ vẽ một cạnh tùy ý. Đây là cách anh ta sẽ chơi, có một cạnh “thêm” về màu sắc của mình, điều này tất nhiên không thể cho phép anh ta thắng.

Do đó, từ quan điểm về khả năng giành chiến thắng cho từng biến thể của NSP, một và chỉ một trong ba sự hợp nhất sau đây đã phát sinh:

1. kết nối có chiến lược chiến thắng, bất kể anh ta chơi thứ nhất hay thứ hai;
2. người cắt có chiến lược chiến thắng, bất kể anh ta chơi thứ nhất hay thứ hai;
3. Người chơi thực hiện bước đi đầu tiên có chiến lược chiến thắng.

Chúng tôi sẽ gọi các biến thể PSP của nhóm S-cers đầu tiên, nhóm thứ hai -

2 Lượng tử số 9

⟦folio 18⟧

R-cerami, thứ ba - N-cerami. Các hình 7, a) - c) thể hiện các đồ thị lần lượt cho C-cer, P-cer và H-cer.

Bài toán 2. Chứng minh cây cầu đó là trò chơi H.

Một chút lý thuyết

Chúng ta hãy tạm dừng trò chơi một lúc và đưa ra một số định nghĩa từ lý thuyết đồ thị sẽ được đưa ra sau*.

Đồ thị G được gọi là liên thông nếu có một đường đi giữa hai đỉnh bất kỳ. Một biểu đồ không thể truyền được là một tập hợp của một số biểu đồ được kết nối, mỗi biểu đồ được gọi là thành phần của nó. Đường đi có đỉnh đầu và đỉnh cuối trùng nhau được gọi là chu trình. Nếu một đồ thị liên thông có một chu trình thì khi loại bỏ bất kỳ cạnh nào khỏi chu trình, đồ thị vẫn liên thông. Một đồ thị liên thông không có chu trình được gọi là cây. Ví dụ về cây được thể hiện trong Hình 8.

Dễ dàng nhận thấy rằng việc loại bỏ bất kỳ cạnh nào khỏi cây sẽ tạo ra một biểu đồ có hai thành phần và các đầu của cạnh bị loại bỏ nằm trong các thành phần khác nhau (Hình 9).

Một cạnh của đồ thị có hai đầu x và y sẽ được ký hiệu là [x, y]. Chúng ta biểu thị thành phần được hình thành bằng cách loại bỏ cạnh [x, y] khỏi cây A và chứa đỉnh x bởi A(x), và thành phần chứa đỉnh y bởi A(y).

Bổ đề về hai cây. Giả sử A và B là hai cây trên cùng một tập đỉnh và [x, y] là một cạnh của cây A. Khi đó trong cây B có một cạnh b, một đầu của cạnh này nằm ở A(x) và đầu kia nằm ở A(y) (Hình 10).

Quy tắc mới của trò chơi

Để tìm hiểu cách chơi PIP, chúng ta sẽ lại thay đổi sân chơi và luật chơi một chút. Để làm điều này, chúng tôi giới thiệu khái niệm về sự co lại của đồ thị.

*) Thông tin chi tiết hơn về đồ thị được thảo luận, chẳng hạn như trong cuốn sách của L. Yu. Berezina “Đồ thị và ứng dụng của chúng” (M., “Prosveshchenie”, 1979).

⟦folio 20⟧

Bổ đề này gợi ý một chiến lược cho người chơi kết nối.

Mục tiêu của người chơi $C$ là duy trì trong biểu đồ sự tồn tại của hai cây thỏa mãn điều kiện Lehmann (bằng cách chia kết quả này, anh ta đảm bảo sự tồn tại của hai đường đi giữa các đỉnh $s$ và $t$, và người chơi $P$ không có cách nào tách hai đỉnh này). Và người chơi $C$ thực sự có thể làm điều này nếu có hai cây như vậy trong biểu đồ ban đầu. Nếu người chơi $P$ loại bỏ cạnh $a$ của một trong những cây này, thì người chơi $C$ trong đáp số phải kéo một cạnh từ một cây khác tồn tại theo bổ đề cuối cùng. Nếu người chơi $P$ loại bỏ một cạnh không thuộc về một trong hai cây của chúng ta, thì người chơi $C$ có thể thu gọn một cạnh ở một trong các cây; rõ ràng là đồ thị mới vẫn chứa hai cây Lehman (cái nào?).

Sau mỗi cặp nước đi, số đỉnh trong mỗi cây của chúng ta giảm đi một, vì vậy các đỉnh $s$ và $t$ sớm hay muộn sẽ hợp nhất và người chơi $C$ sẽ giành chiến thắng.

Chúng tôi bắt đầu cho bạn chơi trò chơi $C$ bằng cách sử dụng hai cây Lehmann. Nhưng những cây này nằm ở đâu? Tất nhiên, bạn có thể sử dụng tìm kiếm toàn diện, nhưng điều này đòi hỏi sự đầu tư rất lớn về thời gian, ngay cả trên các máy tính hiện đại. Lehmann không thể tìm ra một thuật toán hiệu quả để tìm hai cây như vậy, nên trong một thời gian dài, định lý Lehmann dường như chỉ được quan tâm về mặt lý thuyết. Chỉ đến đầu những năm 70, Bruno và Weinberg mới xây dựng được một thuật toán như vậy.

Trên thực tế, Lehmann đã giải quyết hoàn toàn trò chơi chuyển đổi Shannon: ông cũng chứng minh rằng một biến thể của NIS là một trò chơi $P$ khi và chỉ nếu đồ thị có hai đồ thị con cùng loại. Nếu biến thể PIP là trò chơi $H$ thì sau nước đi hợp lý đầu tiên, chúng ta sẽ nhận được biến thể PIP trên biểu đồ mới, đó là trò chơi $P$ hoặc trò chơi $C$ - tùy thuộc vào người thực hiện nước đi đầu tiên: $P$ hoặc $C$, tương ứng. Một động thái như vậy tồn tại. Một động thái như vậy tồn tại trong một trò chơi $H$ nhất định. Về nguyên tắc, những động thái này có thể được thực hiện bằng vũ lực.

**Chiến lược bắc cầu**

Vì vậy, chúng tôi đã hướng dẫn bạn cách chơi trò chơi $C$. Nhưng bridge-it, theo bài toán 2, là một trò chơi $H$. Làm thế nào một người mới bắt đầu có thể chơi để giành chiến thắng?

Rõ ràng, trong trò chơi đánh bài, người mới bắt đầu có thể được coi là người chơi $C$. Ví dụ, với nước đi đầu tiên, anh ta có thể nắm bắt được cạnh được đánh dấu màu xanh lá cây trong Hình 13. Biểu đồ kết quả sau nước đi này chứa hai cây Lehmann: chúng được đánh dấu trong Hình 13 bằng màu đỏ và đen. Và sau đó người chơi $C$ có thể sử dụng chiến lược được mô tả ở trên cho trò chơi $C$. Trong Hình 13, các mũi tên được xem xét theo cách mà người chơi $P$ loại bỏ cạnh mà phần cuối của một số mũi tên chỉ vào.
