---
id: 1987-2-krutogin-puteshestvie-po-mikrokompyuteru-fe4e28ff
issue: kvant_1987_2
year: 1987
number: "2"
title: Hành trình qua máy vi tính
authors:
  - Крутогин Д. Г.
rubric: raznoe
page_first: 21
page_last: 23
page_labels: 19-21
tag: EGC7
lang: vi
source: kvant_digital
extraction: vision
content_sha256: b8a598d97b1ba94ff7f460098ea203850e6bdfbcf8ca99ae4c6710fca0e95a5f
prompt_sha256: draft-1
translated_from: content/ru/1987/02/articles/05_krutogin-puteshestvie-po-mikrokompyuteru-fe4e28ff.md
source_content_sha256: 4ad47848f7b6e51777a39825ad1ae3851b34a60658fcbf8fe2ab211b666fcdc4
translation_model: draft
translation_run: vi-draft-2026-10-31
translation_quality: draft
---

⟦folio 19⟧

HÀNH TRÌNH
BẰNG VI TÍNH

Đội trưởng Khoa học Kỹ thuật D. G. KRUTOGIN

Một năm trước, chúng tôi đã xem xét “quá trình xây dựng” của một sơ đồ liên vùng lớn (BIS), so sánh nó với việc xây dựng một thành phố (“Quait”, 1986, số 2). Khi đó chúng tôi chủ yếu quan tâm đến công nghệ xây dựng

các vấn đề, và bây giờ chúng tôi mời bạn làm quen với chính thành phố, cấu trúc của nó, đọc về từng quận và khu phố, khám phá các thắng cảnh kiến ​​trúc...

Phản chiếu ở chế độ toàn cảnh

Để làm quen, chúng ta hãy chọn một mạch kết nối cực lớn (VLSI) - ví dụ: vi mạch microeBM một chip. Một mạch như vậy chứa 10⁵—10⁶ bóng bán dẫn riêng lẻ. MicroeBM, hay thường được gọi là máy vi tính (MC) làm nhiệm vụ gì? Thứ nhất, đếm, tức là thực hiện

19

⟦folio 20⟧

thực hiện các phép toán ở tốc độ khá cao - lên tới một triệu phép tính đơn giản mỗi giây. Chúng ta sẽ gọi những thao tác đơn giản đó là một số thao tác mà máy tính có thể thực hiện “từ khi sinh ra”; Về cơ bản nó là phép cộng (trừ) và so sánh. Để thực hiện các hành động phức tạp, trước tiên bạn phải dạy cho máy “chuyển đổi” những hành động này thành một chuỗi các thao tác đơn giản. Thứ hai, thực hiện các phép toán logic với cùng tốc độ. Không đi sâu vào sự phức tạp của các phép toán logic, hãy xem xét một ví dụ phù hợp: bạn cần tạo một danh sách theo thứ tự bảng chữ cái của một tập hợp một triệu tên nhất định. Nhìn chung, đây là một công việc đơn giản, không cần tính toán - bạn cần so sánh họ theo các chữ cái đầu tiên, thứ hai, thứ ba, v.v. và dựa trên kết quả so sánh, đưa họ vào danh sách theo các con số tương ứng. Đối với một người, công việc này mệt mỏi, nhàm chán và rất dài. Máy tính, bao gồm cả máy vi tính, sẽ thực hiện công việc này khá nhanh chóng. Thứ ba, máy vi tính có thể điều khiển máy móc, đơn vị sản xuất và quy trình. Khả năng cộng này từ hai khả năng đầu tiên, hoặc nói một cách rất đơn giản, quy trình kiểm soát có thể được biểu diễn dưới dạng tính toán một số phương án hành động có thể chấp nhận được, so sánh kết quả và lựa chọn lời giải tối ưu.

Rõ ràng là VLSI đẹp nhất đã “chết”, vô dụng nếu nó bị thiếu hệ thống cấp điện, phương tiện nhập thông tin (ví dụ: bàn phím) và hiển thị kết quả (ví dụ: màn hình hoặc thiết bị in). Máy tính điều khiển cũng cần có hệ thống liên lạc với các cơ chế vận hành. (Vì vậy, bộ não con người, chiếc máy tính cá nhân đa năng của chúng ta, sẽ bất lực nếu không có giao tiếp hai chiều với mắt, tai, cơ thể, tay.)

Vì vậy, hãy xây dựng: VLSI là một máy tính mạnh mẽ, phần phức tạp nhất của nó. Máy vi tính VLSI sẽ là mục tiêu trong hành trình của chúng tôi và để đơn giản hóa phần nào, VLSI mà chúng tôi sẽ gọi là thành phố MK.

Hãy nhìn vào bức ảnh được đăng trên trang này (nó được chụp với độ phóng đại 1,5): một số chân cắm mười chân được lấy ra từ gói VLSI. Đây là những con đường nối thành phố MK với các “ngoại vi” - đây là cái tên có phần chê bai của bàn phím, màn hình, thiết bị số hóa, v.v. và những con đường cung cấp điện cho thành phố - điện áp không đổi (thường là 5 V). Trong trường hợp làm việc với các nhiệm vụ có độ phức tạp lớn hoặc khối lượng lớn (ví dụ: cùng một danh sách gồm một triệu tên), lưu trữ hoặc bộ nhớ bên ngoài, cần có sự trợ giúp; Để liên lạc với các thiết bị lưu trữ bên ngoài (ESD), đường đầu ra cũng được cung cấp.

Hãy nhớ lại rằng một mạch tích hợp quy mô cực lớn thì rất nhỏ. Tinh thể silicon - đế của VLSI - có kích thước khoảng 5x5 mm, còn bản thân VLSI trong vỏ và dây dẫn là một hộp không lớn hơn 40x25 mm và nặng 15-20 g. Vì vậy, để thuận tiện cho việc di chuyển quanh thành phố MK, chúng tôi khuyên bạn nên thu nhỏ tinh thần lại một triệu lần. (Trong văn học cổ tích, ví dụ này đã được sử dụng nhiều lần, mặc dù hệ số tương tự thấp hơn.) Với mức giảm như vậy, khi chiều cao của chúng ta trở thành 1,5-1,8 micron, một chuyến tham quan VLSI MK cũng giống như ở quy mô thông thường của chúng ta, làm quen với một thành phố có diện tích khoảng 30 km2.

Rõ ràng, nếu có cơ hội như vậy, các thành phố sẽ bị bỏ lại từ một điểm trên cao (từ xe đẩy Ostankino, từ Nhà thờ St. Isaac, v.v.). Chúng tôi sẽ dừng lại ở rìa của trường hợp VLSI ở độ cao khoảng 1000 mét (có tính đến tỷ lệ!) phía trên thành phố MK và bắt đầu từ đây.

Dưới thung lũng là thành phố của chúng tôi. Nó được xây dựng trên bờ Biển Vật lý Chất rắn, gần Vịnh Bán dẫn, và không còn nghi ngờ gì nữa, đây là một trong những khu định cư lớn nhất trên bờ biển.

⟦folio 21⟧

ít thường xuyên hơn*). Điểm độc đáo của thành phố của chúng tôi, giống như các thành phố Sochi hay Jurmala, là nó được xây dựng để tiếp nhận và phục vụ một lượng lớn khách du lịch. Dân số thường trú của thành phố chỉ làm điều này. Như thường lệ, ở một thành phố như vậy có ít cư dân thường trú hơn nhiều so với khách. Thành phố MK là một tòa nhà mới; các kế hoạch tổng thể lớn tương tự đã được tạo ra trong năm năm qua. Lần đầu tiên, một thành phố lớn được xây dựng trên một địa điểm va chạm nhau. Trước đây, nhiệm vụ phục vụ du lịch được giải quyết bởi cả một cụm làng nhỏ, có khi nằm cách nhau hàng trăm km (đừng quên nhân với 10⁻⁶!). Bạn có thể tưởng tượng có bao nhiêu bước di chuyển không?

Một lời về lời nói

Bây giờ chúng ta nên làm rõ loại khách du lịch mà chúng ta đang nói đến. Khách du lịch ở MK là những phân đoạn (yếu tố) thông tin mà cái tên “từ máy” rất phù hợp. Đây hoàn toàn không phải là những đám đông tự phát của những cá nhân “man rợ” đổ xô đến các thị trấn nghỉ mát ven biển vào mùa hè. Khách du lịch của chúng ta là những hạt của luồng thông tin tổ chức được gọi là máy tính có thể lập trình. Việc mất đi bất kỳ từ nào cũng có nguy cơ phá hủy ý nghĩa của toàn bộ chương trình, nhưng không được thêm bất kỳ từ nào. (Về mặt này, một chương trình hay cũng giống như một bài thơ hay.)

Vâng, những cư dân thường trú của thành phố là ai? Đây cũng là những từ máy, được “quy định” hoặc được ghi lại trong chính MK. Chúng là cần thiết để vượt qua việc xử lý chương trình.

Các từ máy, giống như các từ chung, mang một số thông tin cụ thể. Đối với bản thân, chúng ta có thể chia các từ máy thành hai nhóm: các từ lệnh (làm gì) và các từ dữ liệu (là các số hoặc đại lượng logic, lệnh hoạt động trên mục đích gì; chúng còn được gọi là toán hạng, sau khi được tạo bằng lệnh). Nhưng điều này là dành cho riêng tôi,

*) Bạn đã đi dọc bờ Vịnh Bán dẫn nếu bạn đã đọc cuốn sách “Giới thiệu về Chất bán dẫn” của M.E. Levinshtein và G.S. Simin, xuất bản trên Viblotechek «Kvant» (số 33, trang 238).

và đối với các mạch điện tử MK, bất kỳ từ máy nào cũng chỉ là một chuỗi các số 1 và số 0, hay nói đúng hơn là điện áp cao (thường là hơn 2,5 V) và thấp (dưới 0,5 V) ở đầu vào của các phần tử bóng bán dẫn. Như vậy, lời máy là một chuỗi xung điện chạy dọc các con đường, khu dân cư của MK.

Bài toán của mỗi xung riêng lẻ - bật một hoặc một bóng bán dẫn khác trong phần tử logic hoặc bộ nhớ lưu trữ của máy tính. Đổi lại, mỗi sự bao gồm như vậy sẽ dẫn đến sự chuyển động của các gói điện tích—các electron và lỗ trống—thông qua tinh thể MC. Do đó, thông tin trong MK có dạng vật lý của các gói hạt tích điện, di chuyển có mục đích dọc theo vi mạch, cho đến khi cuối cùng, sự xuất hiện của các xung định hướng tại các điểm tiếp xúc đầu ra của MK thông báo việc hoàn thành quá trình xử lý thông tin và nhận kết quả.

Và một chút nữa về từ ngữ. Chúng ta thường hầu như không gặp khó khăn gì trong việc lựa chọn từ ngữ để diễn đạt suy nghĩ của mình. Tất cả các máy tính, bao gồm cả MK của chúng tôi, đều có thứ tự nghiêm ngặt - bạn có thể sử dụng các từ có một độ dài cụ thể: ví dụ: từ 8 hoặc 16 chữ cái, hơn nữa, các chữ cái là 0 hoặc 1 (các chữ cái như vậy được gọi là bit). Để so sánh, chúng tôi lưu ý rằng ngày càng có nhiều máy tính “nói” bằng các từ 64 và 128 bit, và các máy vi tính tốt nhất vẫn chỉ là 32 bit. Tất nhiên, những từ có dạng từ ngắn (8 hoặc 16 bit) ít biểu cảm hơn nhưng đầy đủ hơn nhiều. Đối với một chiếc máy tính “bỏ túi” bạn cũng cần có một cuốn từ điển bỏ túi!

Có những khó khăn không thể tránh khỏi trong giao tiếp giữa người và máy. Soạn một chương trình bằng ngôn ngữ máy là một công việc khó khăn và đòi hỏi một kỹ năng nhất định. Sẽ thuận tiện hơn cho chúng ta khi giao tiếp với máy móc bằng ngôn ngữ logic đối với con người (chẳng hạn như tiếng Nga hoặc tiếng Anh). Ngôn ngữ trung gian như vậy dành cho bài toán Có hàng tá mục đích sáng tạo: Fortran, Algol, Colol, v.v. Chà, ở những nơi sử dụng nhiều ngôn ngữ, người ta không thể làm gì nếu không có người phiên dịch... Nhưng chúng ta sẽ tiếp tục cuộc trò chuyện về các dịch giả và công ty dịch thuật tồn tại ở thành phố của chúng ta trong số tiếp theo.
