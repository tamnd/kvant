---
id: 1973-11-guter-polunov-mashina-upravlyaet-0bdb0c50
issue: kvant_1973_11
year: 1973
number: "11"
title: Máy điều khiển
authors:
  - Гутер Р. С.
  - Полунов Ю. Л.
rubric: osnovnye-stati
page_first: 13
page_last: 18
page_labels: 11, 12, 14, 15, 16
tag: 59RQ
lang: vi
source: kvant_digital
extraction: vision
content_sha256: 7f0f2ea37eceef3f11081605048089232b574a5e8d1394b60d16d76f238703d6
prompt_sha256: draft-1
translated_from: content/ru/1973/11/articles/03_guter-polunov-mashina-upravlyaet-0bdb0c50.md
source_content_sha256: 4c4629622f00c23ba102d2fdee913be1bc0a9beaab68fe4f8d1f67c65ceff95e
translation_model: draft
translation_run: vi-draft-2026-10-31
translation_quality: draft
---

⟦folio 11⟧

Máy điều khiển
R. S. Guter,
Yu. L. Polunov

Gần đây, nhân viên của tạp chí Máy tính và Tự động hóa của Mỹ đã tính toán rằng trong số sáu trăm “nghề” về máy tính điện tử, có khoảng năm mươi ngành được gọi là máy “điều khiển” - những máy quản lý các quy trình thử nghiệm và kỹ thuật chuyển động nhanh. Ở đây chúng tôi muốn nói về cách máy móc điều khiển và tại sao cần tính toán để thực hiện điều này.

Làm thế nào để một người kiểm soát

Một chiếc ô tô số tự động đang phóng nhanh trên đường cao tốc. Người lái điều khiển chuyển động của ô tô. Khi vượt xe đang đi qua và vượt xe đang chạy tới, người lái xe liên tục quan sát đường đi. Anh ta phác thảo quỹ đạo và tốc độ chuyển động, đồng thời thay đổi vị trí của bàn đạp và vô lăng của ô tô sao cho quỹ đạo và tốc độ thực tế khác biệt ít nhất có thể so với dự định. Não - tay - máy - mắt - não - đây là hệ thống điều khiển tự động hóa.

Trong lò điện tử có khuôn để đúc. Nhiệt độ trong lò không được vượt quá giới hạn nhất định. Người công nhân theo dõi kim của thiết bị kết nối với nhiệt kế điện tử bên trong lò. Nếu mũi tên tiến đến giới hạn quy định thì người công nhân sẽ tăng hoặc giảm dòng điện trong bộ phận làm nóng, di chuyển thanh trượt biến trở để mũi tên quay về vị trí mong muốn.

Borscht đang được nấu trên bếp. Người đầu bếp nếm món borscht và thêm vào một số

⟦folio 12⟧

thức ăn hoặc thay đổi cường độ lửa cho đến khi lượng đồ trong chảo phù hợp với ý tưởng của anh ấy về một món ăn làm sẵn và ngon miệng. Dễ dàng nhận thấy nguyên tắc hành động của anh ta cũng giống như nguyên tắc hành động của người lái xe và người thợ ở lò sấy. Sự khác biệt trong hành động chỉ được xác định bởi tính năng của quy trình công nghệ.

Thuật toán điều khiển

Tất cả các ví dụ của chúng tôi đều liên quan đến một người. Tuy nhiên, nó có thể được loại trừ khỏi hệ thống điều khiển. Nếu luật điều khiển bất kỳ đối tượng nào được hình thành chính xác dưới dạng một chuỗi các quy tắc hành động (thuật toán), thì về nguyên tắc, có thể tạo ra một thiết bị và soạn chương trình thực hiện thuật toán này mà không cần sự tham gia của con người. Những hệ thống như vậy thường được gọi là hệ thống điều khiển tự động.

Ví dụ, để điều khiển một lò nung thực, chỉ cần gửi tín hiệu đầu ra của nhiệt kế điện đến thiết bị điều khiển động cơ nối với động cơ biến trở là đủ. Thuật toán điều khiển rất rõ ràng: nếu nhiệt độ trong lò bắt đầu giảm thì động cơ sẽ quay theo một hướng, làm tăng dòng điện trong lò; nếu nhiệt độ tăng thì động cơ phải giảm dòng điện và quay theo hướng ngược lại.

Tóm tắt từ hệ thống vật lý của các quá trình xảy ra trong hệ thống điều khiển, chúng ta có thể xác định các khối chung của các hệ thống này: đối tượng điều khiển, hệ thống điều khiển, các cơ quan điều hành và các cơ quan (thiết bị) truyền thông tin về mục tiêu và kết quả điều khiển đến hệ thống điều khiển. Biểu diễn đồ họa của một hệ thống như vậy (sơ đồ khối) được hiển thị trong Hình 1. Chúng tôi khuyên người đọc xác định chính xác vai trò của khối khác trong mỗi ví dụ đã cho là gì.

Hệ thống điều khiển vòng kín được mô tả

hoặc hệ thống phản hồi. Việc điều chỉnh các quá trình trong cơ thể sống, thiết bị kỹ thuật, hệ thống kinh tế và xã hội dựa trên nguyên tắc phản hồi - việc truyền thông tin từ đầu ra của hệ thống đến đầu vào của nó.

Để hiểu vai trò của phản hồi, bạn cần làm quen với các hệ thống vòng hở trong đó không có sự giao tiếp như vậy. Một ví dụ sẽ là một đài phun nước ngọt.

Máy này hoạt động như thế nào? Một đồng xu rơi vào đáp số được kiểm tra theo trọng lượng và rơi xa hơn sẽ đóng mạch điện. Khi nam châm điện của nó được bật, nó sẽ nhận được một đòn bẩy để mở van (vòi) trong một thời gian đủ để đổ đầy một cốc nước.

Có những lúc máy “không nạp tiền”. Tất nhiên, anh ta làm điều này không phải vì “có ý đồ xấu”; Đơn giản là trong quá trình vận hành, đặc tính của nam châm điện hoặc đòn bẩy đã thay đổi và anh ta sẽ mở van trong một khoảng thời gian ngắn hơn.

Hãy thử thiết kế chiếc máy sao cho xảy ra phản hồi. Để làm được điều này, bạn cần có một thiết bị thay đổi mức chất lỏng trong ly. Tín hiệu đầu ra của thiết bị này phải được đưa vào cuộn dây nam châm điện để van vẫn mở cho đến khi có tín hiệu “kính đầy”. Một hệ thống như vậy sẽ linh hoạt hơn và không ngại thay đổi.

Hệ thống điều khiển tự động vòng kín đã xuất hiện từ

⟦folio 14⟧

Kiểm soát phản hồi

Hệ thống điều khiển vòng kín được sử dụng bởi máy tính được sử dụng rộng rãi nhất trong các ngành công nghiệp hóa chất và luyện kim, trong năng lượng nhiệt và hạt nhân. Trong các hệ thống điều khiển khép kín, tác động được tạo ra có tính đến thông tin về tiến trình của quá trình. Các thiết bị thu thập thông tin này được gọi là cảm biến.

Theo quy luật, tín hiệu đầu ra của các cảm biến như vậy là một đại lượng vật lý không phải bát phân và liên tục. Để máy tính kỹ thuật số chấp nhận thông tin cảm biến, một đại lượng liên tục (thường được gọi là tương tự) phải được chuyển đổi thành dạng kỹ thuật số trong hệ thống số nhị phân. Vì vậy, một thành phần quan trọng của bộ điều khiển máy là bộ chuyển đổi tương tự sang số.

Đại lượng đầu vào của bộ chuyển đổi tương tự sang số là điện áp hoặc dòng điện, chuyển động góc hoặc tuyến tính hoặc vị trí của thiết bị. Một đại lượng tương tự đáng kể được chuyển đổi từ dạng ban đầu sang dạng khác, thuận tiện hơn cho việc chuyển đổi, ví dụ, áp suất được chuyển đổi thành chuyển vị.

Chúng ta hãy xem xét một ví dụ về một trong những sơ đồ khả thi để chuyển đổi điện áp thành số xung. Đặt điện áp $U_{bx}$ vào đầu vào của bộ chuyển đổi (Hình 2, a). Bộ chuyển đổi hoạt động riêng biệt, nghĩa là nó thay đổi điện áp theo những khoảng thời gian (chu kỳ) nhất định, trong thời gian đó điện áp đầu vào có thể được coi là gần như không đổi.

Điểm bắt đầu của mỗi chu kỳ đồng hồ được bù bằng một xung cực đại, được phát ra bởi bộ tạo xung cực đại (Hình 2, b). Xung như vậy khởi động bộ tạo xung đếm (Hình 2, c), bộ tạo điện áp răng cưa (Hình 2, e) và bật bộ đếm.

Điện áp răng cưa và điện áp đầu vào $U_{bx}$ được cung cấp cho hai đầu vào của mạch trùng khớp, tại thời điểm trùng khớp (Hình 2, e) tạo ra một xung (Hình 2, e), khóa bộ đếm. Số lượng tên đếm

Cơm. 2.

các xung (Hình 2, g) đi vào bộ đếm sẽ tỷ lệ thuận với khoảng thời gian giữa đồng hồ và các xung chặn, và khoảng thời gian này tỷ lệ thuận với giá trị của điện áp đầu vào $U_{bx}$.

Do đó, trong bộ chuyển đổi tương tự sang số này, mạch chuyển đổi sau được thực hiện: giá trị tương tự $\rightarrow$ điện áp $\rightarrow$ khoảng thời gian $\rightarrow$ dạng kỹ thuật số. Sơ đồ khối của việc chuyển đổi như vậy được hiển thị trong Hình 3.

Ngoài việc chuyển đổi tín hiệu tương tự sang dạng kỹ thuật số, việc chuyển đổi ngược lại cũng được yêu cầu. Vấn đề là máy tính

⟦folio 15⟧

Xe buýt tạo ra tín hiệu ở dạng kỹ thuật số. Nếu phần tử điều hành của hệ thống điều khiển tự động là bộ số hóa bước điều khiển tín hiệu số thì không cần chuyển đổi bổ sung. Nếu bộ số hóa chung (bộ giảm chấn, bộ điều chỉnh) được sử dụng làm bộ phận điều hành, yêu cầu tín hiệu đầu vào liên tục thì cần có bộ chuyển đổi kỹ thuật số sang tương tự. Những biến đổi như vậy dựa trên các nguyên tắc giống như các đối tượng tương tự đã thảo luận ở trên.

Sơ đồ khối của hệ thống điều khiển quá trình kỹ thuật vòng kín sử dụng máy tính điện tử được thể hiện trên hình 4. Có thể thấy, ngoài máy tính, hệ thống điều khiển còn chứa khá nhiều thiết bị bổ sung cần thiết để kết nối máy móc với đối tượng điều khiển.

Trước hết, cần có các cảm biến đại lượng đặc trưng cho quá trình được kiểm soát. Chúng bao gồm:

a) các thông số đầu vào của quá trình (áp suất, nhiệt độ, mức tiêu thụ nguyên liệu thô, mức tiêu thụ năng lượng nhiệt và điện, v.v.). Các đại lượng này có thể điều khiển được (nếu chúng ta có thể thay đổi chúng bằng tín hiệu bên ngoài) hoặc không thể điều khiển được (nếu chúng ta không thể thay đổi chúng);

b) nhiễu loạn vi phạm quy trình bình thường của quá trình (dao động về nhiệt độ môi trường, điện áp nguồn, v.v...);

b) các thông số đầu ra của quá trình (sự dao động và chất lượng của sản phẩm chính và sản phẩm phụ, nhiệt độ, thành phần của chúng, v.v.).

Mọi thông tin phải được chuyển đổi sang dạng số và nhập vào máy tính. Ngoài thông tin, cần nhập vào máy thuật toán điều khiển được dịch sang ngôn ngữ máy (chương trình điều khiển). Nhờ có chương trình mà máy có thể tính toán những hành động điều khiển nào là cần thiết trong một tình huống nhất định để quá trình được kiểm soát diễn ra theo cách có lợi nhất.

Thuật toán được biên dịch như thế nào

Việc xây dựng một thuật toán điều khiển cho từng hệ thống, hay chính xác hơn là cho từng quy trình được điều khiển, là một bài toán phức tạp. Rất thường không thể có được một mô tả toán học chặt chẽ về các quá trình phức tạp và biểu diễn sự phụ thuộc giữa các đặc điểm về độ lớn của chúng ở dạng tương tự. Sau đó phải sử dụng các phương pháp thử nghiệm để thiết lập các mối phụ thuộc đó.

Thông tin và mô tả thu được được sử dụng để xây dựng mô hình toán học của đối tượng, là mô hình phức tạp bài toán. Ngoài ra, cũng cần có tiêu chí chính xác cho quy trình tối ưu để xác định mục tiêu điều khiển*). Thường xuyên hơn

*) Việc xây dựng mục tiêu quản lý rõ ràng quan trọng như thế nào, người đọc có thể đánh giá qua câu chuyện của nhà văn khoa học viễn tưởng người Mỹ P. Shackle, Guardian Bird, M., “Young Guard”, 1968 (Thư viện khoa học viễn tưởng. Tập 16).

⟦folio 16⟧

Mục tiêu của quản lý là đạt được hiệu quả kinh tế tối đa. Tuy nhiên, đôi khi nó còn phụ thuộc vào các tiêu chí khác, chẳng hạn như năng suất tối đa, chi phí tối thiểu hoặc thời gian ngắn nhất có thể.

Trong một số trường hợp kiểm soát, thuật toán đầu tiên thành công ở “khả năng tự học”. Điều này có nghĩa là chương trình sẽ có thể phân tích kết quả của các hành động kiểm soát và sự tuân thủ của mô hình toán học đã chọn trong quá trình thực hiện nó và thực hiện các điều chỉnh cần thiết đối với mô hình toán học.

Hệ thống "BẮT ĐẦU"
Chắc hẳn tất cả độc giả đều đã từng nhìn thấy đèn giao thông tự động - hệ thống vòng hở đơn giản nhất. Trong đó, đèn được bật theo thứ tự nhất định ở những khoảng thời gian nhất định mà không tính đến tình hình thực tế tại ngã tư. Vào mùa hè năm 1972, trên quảng trường Serpukhovskaya Zastava ở Moscow (với mô hình giao thông khá phức tạp, xem Hình 5), một hệ thống điều khiển luồng giao thông tự động đã được bật. Từ các cảm biến đặt dưới các lối đi của các tuyến phố đối diện với quảng trường, hệ thống nhận thông tin về số lượng ô tô đang di chuyển tại mỗi vị trí có thể có của đèn giao thông, máy tính sẽ tính toán số lượng máy đang di chuyển và không hoạt động và xác định thời gian ngừng hoạt động trung bình của mỗi ô tô, sau đó chọn vị trí đèn giao thông sao cho thời gian ngừng hoạt động là tối thiểu.

Năm 1974, hệ thống kiểm soát luồng giao thông tự động “BẮT ĐẦU” đã được giới thiệu thử nghiệm ở Moscow, hệ thống này sẽ “quản lý” tất cả đèn giao thông bên trong Garden Ring của thủ đô. Đối với mỗi nút bên trong của mạch, có thể tính toán số lượng ô tô tiếp cận nút này theo các hướng khác nhau.

Thuật toán điều khiển cho hệ thống như vậy bao gồm tính toán thời gian ngừng hoạt động trung bình của máy; tiêu chí cho luồng quy trình tối ưu) là thời gian ngừng hoạt động tối thiểu.
