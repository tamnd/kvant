---
id: 2023-9-gribalko-zaslavskiy-platnyie-vesyi-81c6eadf
issue: kvant_2023_9
year: 2023
number: "9"
title: Cân trả phí
authors:
  - Грибалко А. В.
  - Заславский А. А.
rubric: matematicheskiy-kruzhok
rubric_sub: Математический кружок
page_first: 32
page_last: 39
page_labels: 36-37
tag: VZZZ
lang: vi
source: kvant_digital
extraction: native
content_sha256: c52847d22706565902b37cb299f6915f5cbb87b9964f40b8e371ee7eb420a883
prompt_sha256: draft-1
translated_from: content/ru/2023/09/articles/03_gribalko-zaslavskiy-platnyie-vesyi-81c6eadf.md
source_content_sha256: 1ddbc0a143849d0f110970aab07986e8b3967007f337c8b59c1a6626999c5de5
translation_model: draft
translation_run: vi-draft-2026-10-31
translation_quality: draft
---

⟦folio none⟧

VÒNG TRÒN TOÁN HỌC

Cân trả phí

A. GRIBALKO, A. ZASLAVSKY

VÀO MÙA THU NĂM 2022 TẠI GIẢI ĐẤU THÀNH PHỐ, bài toán sau đây đã được đề xuất (theo cách diễn đạt hơi khác một chút). Bài toán 1. Có 8 đồng xu giống hệt nhau, trong đó có một đồng tiền giả. Tất cả các đồng tiền thật đều có trọng lượng như nhau, nhưng đồng tiền giả khác với chúng về trọng lượng theo một hướng không xác định. Có những chiếc cân dạng cốc, mỗi lần cân bạn phải trả một đồng xu. Hơn nữa, nếu thanh toán bằng tiền thật, cân sẽ hiển thị kết quả chính xác và nếu sử dụng tiền giả, nó sẽ hiển thị kết quả ngẫu nhiên. Có thể tìm và không tiêu 5 đồng tiền thật không? Lời giải. Đặt các đồng xu được đánh số từ 1 đến 8. Chúng ta sẽ trả đồng xu 8 cho lần cân đầu tiên và đặt đồng xu 1 và 2 vào một bát, đồng xu 3 và 4 vào bát kia. Nếu những cái bát vẫn cân bằng thì bốn đồng tiền này là thật. Thật vậy, nếu đồng xu 8 là thật thì chiếc cân hiển thị kết quả chính xác và do đó, đồng xu giả không thể nằm trong số những đồng xu được cân. Nếu đồng 8 là giả thì tất cả các đồng còn lại đều là thật. Sau đó, đến lần cân thứ hai, chúng ta so sánh đồng 1 và đồng 5, thanh toán bằng đồng 7. Nếu cân cân bằng thì đồng 5 cũng là thật, nếu không thì đồng 5 hoặc đồng 7 có thể là giả, tức là đồng 6 rõ ràng là thật. Bây giờ, trong lần đầu tiên cân một trong hai cái bát, chẳng hạn như đồng xu 1 và 2, nặng hơn. Khi đó đồng xu 5, 6, 7 chắc chắn là có thật. Bây giờ chúng ta so sánh đồng xu 1 và đồng xu 2, trả tiền cân bằng đồng xu 4. Nếu cân cân bằng thì đồng xu 1 và 2 là thật. Nếu một trong số chúng nặng hơn thì đồng xu nhẹ hơn và đồng xu 3 là có thật. Trong mọi trường hợp, chúng tôi nhận được năm đồng tiền thật rõ ràng. Việc tìm lời giải đã cho không khó lắm nhưng có thể bạn đọc sẽ đặt câu hỏi: tại sao số 8 và 5 lại cho trước điều kiện bài toán? Bạn có thể hiểu điều này bằng cách giải bài tập sau.

DOI: https://doi.org/10.4213/kvant20230902

Bài tập 1. Bạn tìm được bao nhiêu đồng xu thật nếu lúc đầu có 4, 5,..., 9 đồng xu?

⟦column⟧

Từ Bài tập 1, rõ ràng là nếu lúc đầu có $n d^{8}$ đồng xu thì có thể tìm thấy ít nhất n 3 đồng xu thật, nhưng với $n^{9}$ thì điều này trở nên không thể. Đó là điều tự nhiên khi cho rằng ngay cả khi có $n !^{9}$ thì ít nhất bốn đồng xu sẽ bị “mất”. Về vấn đề này, câu hỏi sau đây được đặt ra. Bài toán 2. Với mỗi k, hãy tìm n lớn nhất để có thể tìm được n k đồng thật từ n đồng xu có sẵn ban đầu. Trước khi giải bài toán này, chúng ta hãy xem xét phép tương tự đơn giản hơn của nó, khi biết trọng lượng của đồng tiền giả khác với trọng lượng của đồng tiền thật theo hướng nào. Để chắc chắn, hãy giả sử rằng đồng tiền giả nhẹ hơn đồng tiền thật. Trường hợp được phân tích tương tự khi một đồng tiền giả có thể nhẹ hơn hoặc nặng hơn đồng tiền thật, nhưng đối với mỗi đồng tiền có sẵn, người ta biết trọng lượng của nó có thể khác với đồng tiền thật theo hướng nào. Chúng ta hãy đưa ra một vài nhận xét sơ bộ. 1. Khi lập kế hoạch cho lần cân tiếp theo, bạn có thể giả định rằng tiền thật đã được thanh toán trong tất cả các lần cân trước đó. Thật vậy, nếu được hướng dẫn bởi giả định này, chúng tôi xác định được một số đồng tiền là thật thì những đồng tiền này sẽ là tiền thật ngay cả trong trường hợp đồng tiền giả đã từng được thanh toán. 2. Đối với mỗi lần cân, bạn phải thanh toán bằng một đồng xu đáng ngờ (tức là một đồng xu chưa rõ là giả hay thật). Thật vậy, nếu biết chắc chắn rằng một đồng xu là giả thì không cần phải cân thêm nữa, và nếu đồng xu đó được biết là thật thì thay vào đó, bằng cách trả tiền cho một đồng xu đáng ngờ, chúng ta sẽ có thể xác định, theo nhận xét trước đó, không ít đồng xu thật mới, nhưng chúng ta sẽ cứu được đồng xu hiện có. 3. Số lần cân không được vượt quá $k^{1}$. Thật vậy, sau k lần cân chúng ta sẽ chỉ còn lại n k đồng xu, trong số đó có thể có đồng tiền giả. Bây giờ chúng ta hãy xem số lượng đồng xu đáng ngờ thay đổi như thế nào trong lần cân tiếp theo.

⟦folio none⟧

11. Tại sao thân đàn cello lại lớn hơn đàn violin rất nhiều? 12. Tại sao thân rỗng của đàn violin, cello hay guitar lại được tạo hình? 13. Tại sao nhạc cụ dây sau khi mang từ nơi lạnh vào phòng ấm lại phải chỉnh dây? 14. Nếu dây của một nhạc cụ bắt đầu phát ra âm thanh trầm bất thường, bộ chỉnh dây sẽ tăng độ căng của dây. Làm thế nào phương pháp này có thể đạt được tần số dao động mong muốn? 15. Người chơi guitar gảy dây và thả ra, sau đó mỗi dây rung tự do và phát ra âm thanh theo tần số riêng. Nhưng người nghệ sĩ vĩ cầm liên tục di chuyển cây cung của mình dọc theo dây đàn thì làm sao nó rung động? 16. Tại sao cung của nhạc cụ dây lại được cọ xát bằng nhựa thông trước khi chơi?

Kinh nghiệm vi mô

Chà một ngón tay ướt dọc theo mép kính hoặc kính. Ở một tốc độ lưu thông nhất định, bạn có thể làm cho ly thủy tinh “hát”. Điều gì gây ra âm thanh này? Nước sẽ thay đổi như thế nào nếu bạn đổ nước vào cốc?

Thật thú vị rằng...

...theo truyền thuyết, vào thời cổ đại, gần thành phố Thebes của Ai Cập cổ đại, vào mỗi buổi sáng lúc bình minh, một bức tượng khổng lồ, được gọi là Bức tượng khổng lồ của Memnon, phát ra âm thanh A của quãng tám đầu tiên, và các nhạc sĩ đã đến đó để chỉnh dây nhạc cụ của họ. ...Pythagoras đã phát hiện bằng thực nghiệm mối liên hệ giữa độ cao của một giai điệu âm nhạc và độ dài của dây hoặc cây sáo tạo ra nó, và sự hài hòa của âm thanh khớp được xác định bởi một tỷ lệ hợp lý đơn giản về độ dài của các nhạc cụ này. Đây là cách Pythagoras khám phá ra định luật vật lý toán học đầu tiên. ...cây gậy âm nhạc, được phát minh vào đầu thế kỷ 11 bởi tu sĩ người Ý Guido d'Arezzo, là biểu đồ đầu tiên trong lịch sử, vì nó cho thấy sự thay đổi cao độ theo chiều dọc và thời gian trôi qua theo chiều ngang từ trái sang phải. ... đóng góp đáng kể nhất cho lời giải bài toán về dây dao động là của Leonhard Euler, bắt đầu với tác phẩm $^{1739}$ của ông “An Try on a New Theory of Music”, trong đó ông đưa ra ý nghĩa chính xác cho vấn đề về thang âm. ...Beethoven, người điếc, nghe tiếng đàn piano, giữ một đầu cây gậy của mình vào đó, đầu kia giữ chặt răng. ...Albert Einstein không chỉ thích chơi violin mà còn biểu diễn các tác phẩm của Bach, Vivaldi và Mozart trên piano. Theo những người cùng thời, ông dễ dàng chấp nhận những đánh giá tiêu cực về lý thuyết khoa học của mình, nhưng sẽ rất khó chịu nếu ai đó chỉ trích phong cách chơi violin của ông. ...nhạc cụ điện tử gia dụng đầu tiên - Theremin - được thiết kế vào năm $в^{1920}$ bởi nhà vật lý người Nga Lev Theremin. Cao độ và âm lượng của âm thanh trong thiết bị này có thể được kiểm soát bằng cách thay đổi vị trí tay của người biểu diễn so với ăng-ten của thiết bị. ...vào thế kỷ 20 đã có một cuộc cách mạng thực sự về phương tiện ghi âm, truyền tải và chơi nhạc. Từ các nhạc cụ cơ khí - đàn organ thùng và đồng hồ âm nhạc - qua máy hát, máy ghi âm - cho đến các thiết bị âm thanh kỹ thuật số. Ví dụ như một máy vi tính có trí tuệ nhân tạo được tích hợp trong tai nghe hoặc một chương trình chọn nhạc cho người dùng tương tự như những gì họ đã nghe trước đây.

⟦column⟧

Đọc gì trong «Kvant» về sự kết hợp giữa vật lý và âm nhạc

(xuất bản những năm gần đây)

1. "Xin chào! Bạn có nghe tôi nói không? – 2015, Phụ lục số 1, trang 111; 2. “Tiếng vỗ tay ở đây im lặng” – 2016, Số 3, trang 34; 3. “Tại sao hét ngược gió lại xấu” – 2020, Số 5, trang 25; 4. “Bùm và suỵt…” – 2022, Số 11 12, trang 42.

Tài liệu do A. Leonovich chuẩn bị

⟦folio 36⟧

⟦figure⟧

Hình 2. Tín hiệu và việc cắt tín hiệu

KVANT 2023/№9

Bài viết này sẽ cho bạn biết cách chúng tôi tạo ra một bàn đạp hiệu ứng guitar DIY thực sự. Chúng tôi đã chọn hiệu ứng biến dạng $(англ.^{distortion}$ – biến dạng). Hiệu ứng này làm thay đổi hình thức của tín hiệu gốc, hay đúng hơn là hình dạng của nó (Hình 2). Tín hiệu ban đầu hay còn gọi là tín hiệu gốc là sóng hình sin đều. Tiếp theo là cắt, tức là làm biến dạng tín hiệu gốc. Biên độ của tín hiệu được xử lý vượt quá giá trị điện áp cho phép. Sóng hình sin bây giờ dường như không vừa với cửa sổ. Tín hiệu bị méo, tập hợp tần số tăng lên. Âm thanh hung hãn hơn. Có hai kiểu cắt: cắt cứng - kết quả của hiệu ứng biến dạng, và cắt mềm - kết quả của hiệu ứng tăng tốc $(англ.^{overdrive}$ - tăng tốc).

⟦column⟧

Việc tạo ra bàn đạp của chúng tôi bắt đầu bằng việc tìm kiếm một mạch điện phù hợp. Trên Internet, chúng tôi tìm thấy hướng dẫn tạo bàn đạp hiệu ứng Fuzz (Hình 3). Bảng mạch đầu tiên đã phải bị loại bỏ vì một trong các bóng bán dẫn bị lỗi và chúng tôi cũng đã tìm ra cách đơn giản hóa đáng kể mạch điện bằng cách sử dụng một vi mạch thay vì tầng bán dẫn. Lần thử thứ hai đã thành công, thiết kế đã hoạt động và chúng tôi có thể nghe thấy tiếng tăng tốc ấm và giòn (tín hiệu bị cắt). Nhưng bây giờ chúng tôi không hài lòng với vẻ ngoài của mạch điện (Hình 4), và chúng tôi quyết định chuyển nó từ bìa cứng sang bảng mạch thật (bảng mạch in). Bảng mạch in (Hình 5) được sản xuất bằng phương pháp tiêu cực hóa học, hay đúng hơn là -

⟦figure⟧

Hình 4. Nguyên mẫu đầu tiên của bảng trên bìa cứng

Hình 3. Mạch bàn đạp hiệu ứng guitar Fuzz đã được sửa đổi

⟦folio 37⟧

PHÒNG THÍ NGHIỆM

⟦figure⟧

Hình 5. Ván trong quá trình sản xuất sử dụng công nghệ sắt-laser

thuận tiện hơn cho điều kiện gia đình bằng công nghệ sắt-laser. Trước hết, chúng tôi đã thiết kế một khuôn tô cho bảng mạch in trong tương lai trong hệ thống thiết kế có sự hỗ trợ của máy tính Altium Designer. Tiếp theo, bản vẽ stencil thu được trên bảng của chúng tôi được in trên giấy bóng từ tạp chí bằng máy in laser (do đó có từ “laser” trong tên của phương pháp). Trên một tấm sợi thủy tinh đã chuẩn bị trước

Hình 6. Bàn đạp xong

"QUANTA"

⟦column⟧

Lita, sử dụng bàn ủi, thiết kế đã được chuyển từ khuôn tô. Việc chuẩn bị tấm laminate sợi thủy tinh bao gồm làm sạch bề mặt bằng chất mài mòn và tẩy dầu mỡ sau đó. Tiếp theo là chuyển mực từ giấy nến sang bề mặt phôi, sau đó giấy được loại bỏ bằng nước và một miếng bông. Quá trình ăn mòn diễn ra trong dung dịch hydro peroxide và axit citric có thêm muối ăn, đây là chất xúc tác trong phản ứng này. Quá trình này mất khoảng 30–40 phút. Kết quả là tất cả số đồng thừa đã bị khắc đi và những gì bên dưới bản vẽ vẫn còn nguyên. Kết quả là một mô hình dẫn điện, đó là mạch điện. Việc cài đặt thêm các phần tử hóa ra lại là một niềm vui thực sự. Sau khi chúng tôi tin chắc rằng mạch điện đang hoạt động, đã đến lúc chế tạo vỏ máy. Chúng tôi quyết định làm cho nó màu đen và chọn hình vuông. Chất liệu được sử dụng là gỗ và nhựa nên bên trong bàn đạp phải được che chắn. Để làm điều này, chúng tôi phủ bên trong vỏ bằng băng dính nhôm. Để tránh nhiễu và xuất hiện điện dung ký sinh, các mảnh băng riêng lẻ được nối với nhau bằng một dây dẫn (một giọt chất hàn). Đây là cách Fusik-2000 yêu quý của chúng tôi được tạo ra (Hình 6).
