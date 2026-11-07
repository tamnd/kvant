---
id: 1992-10-sprent-zachem-nuzhna-statistika-eab1e150
issue: kvant_1992_10
year: 1992
number: "10"
title: Tại sao chúng ta cần thống kê?
authors:
  - Спрент П.
rubric: osnovnye-stati
page_first: 22
page_last: 29
page_labels: 20-27
lang: vi
source: kvant_digital
extraction: vision
content_sha256: fb37a0a23b65b2fc05d95ea201a1cacf519bcd9f4d68879a3ef06d9c19f2060e
prompt_sha256: draft-1
translated_from: content/ru/1992/10/articles/06_sprent-zachem-nuzhna-statistika-eab1e150.md
source_content_sha256: c6403a59e44109e87a86cabce2cdd354e704f813936399a1f82427ac3f3ec1e3
translation_model: draft
translation_run: vi-draft-gaps-2026-11-07
translation_quality: draft
---

⟦folio 20⟧

TẠI SAO BẠN CẦN THỐNG KÊ?

P. XUÂN

Bắt đầu

Vào tháng 1 năm 1976, thâm hụt thương mại của Anh là 275 triệu bảng. Vào Ngày Thánh Patrick cùng năm, 1 bảng Anh trị giá 2,42 đô la Mỹ. Và sau vài ngày, người thí nghiệm nhận thấy trọng lượng của sáu heo con thay đổi từ 1218 lên 1314 gam trong khoảng thời gian vài tuần. Những con số hoặc dữ liệu thống kê này có thể được ai đó quan tâm và chắc chắn đã có ý nghĩa nhất định.

Đối diện cửa sổ phòng tôi có một tấm biển đề: "Đừng mạo hiểm! Người đi qua đường, anh ta an toàn hơn!" Tất nhiên, biển báo này chứa một số thông tin: nó cho bạn biết rằng sẽ khôn ngoan hơn khi sử dụng lối sang đường dành cho người đi bộ để băng qua đường. Bạn có thể tin điều này, nhưng từ “沛yater an toàn hơn” nghĩa là gì? Điều này khó có nghĩa là sự an toàn của tôi sẽ tăng lên gấp năm lần nếu tôi dành cả ngày đi đi lại lại dọc hành lang thay vì viết sách. Đúng hơn, điều này sẽ giúp bạn làm quen với thực tế là theo một nghĩa nào đó, nó rất

⟦folio 21⟧

---
running_head:
folio:
---

Đi qua đường sẽ an toàn hơn là băng qua đường ở nơi khác, nhưng ngay cả tuyên bố này cũng cần có bằng cấp. Đường dành cho người đi bộ thường được đặt ở những nơi giống nhau. Nếu bạn có thể băng qua đường nơi giao thông chậm, thì không thể tin được rằng việc đi bộ vài trăm mét đến cùng một ngã tư chỉ để qua đường sẽ an toàn hơn. Tuy nhiên, sử dụng lối qua đường thuận tiện sẽ an toàn hơn so với việc đi qua đường có mật độ giao thông đông đúc. “Năm” này đến từ đâu? Có ai so sánh số vụ tai nạn với những người băng qua đường trước anh ta 200 mét không? Có lẽ chúng ta không biết gì về điều này, nhưng chúng ta không cần phải lo lắng về điều đó, vì dòng chữ được treo ngay phía trên đường giao nhau. Vì vậy, “năm lần” cuối cùng không có ý nghĩa gì nhiều.

Khi dữ liệu mang tải lớn, chúng ta không thể dễ dàng xử lý giá trị số của nó. Những số liệu cán cân thương mại hàng tháng đầy hứa hẹn (như số liệu vào tháng 1 năm 1975) có thể dẫn đến sự sụt giảm hàng triệu đô la trong giá cổ phiếu, trong khi chỉ số chi phí sinh hoạt tăng mạnh có thể gây ra nhu cầu về mức lương cao hơn với những hậu quả kinh tế sâu rộng. Câu hỏi đặt ra là làm thế nào để biết được lượng thông tin tối đa có thể có trong dữ liệu số.

Trong cuộc sống hàng ngày, từ “thống kê” có hai nghĩa. Đầu tiên, nó biểu thị chính các con số hoặc dữ liệu; thứ hai, khoa học hoặc nghệ thuật trích xuất thông tin hữu ích từ các bộ số.

Chúng ta sẽ sử dụng từ “thống kê” theo nghĩa chung, nhưng thường xuyên hơn theo nghĩa thứ hai. Mục tiêu của chúng tôi là tìm ra cách thao tác dữ liệu để đưa ra kết luận với nhiều ứng dụng.

Chúng tôi đã đề cập đến việc cắt heo con hàng ngày, dao động từ 1218 đến 1314 gam. Những dữ liệu này phản ánh một hiện tượng chung: ngay cả khi heo con đến với chúng tôi như nhau và được nuôi trong cùng điều kiện, chúng sẽ không có cùng chỉ tiêu hàng tuần như nhau. Hơn nữa, chúng ta có thể hoàn toàn tin tưởng rằng một nhóm khác sẽ sinh heo con trong cùng một tuần hoặc nhóm đó sẽ có một lứa khác trong một tuần nữa. Vấn đề sẽ là tách biệt những khác biệt tự nhiên, không thể kiểm soát được giữa các cá thể (trong trường hợp này là heo con) khỏi những khác biệt phát sinh do những thay đổi được kiểm soát trong điều kiện bên ngoài. Ví dụ: chúng ta có thể nuôi một nhóm sáu heo con theo một chế độ ăn và một nhóm sáu heo con khác theo một chế độ ăn khác, tất cả các chế độ khác đều như nhau. Tôi muốn tìm hiểu xem chế độ ăn có ảnh hưởng đến năng suất của heo con hay không. Nếu kết quả hàng tuần với một chế độ ăn kiêng dao động từ 1218 đến 1314 gam, và với chế độ ăn khác - từ 893 đến 947 gam, thì rõ ràng chế độ ăn nào tốt hơn. Nhưng nếu kết quả của chế độ ăn kiêng thứ hai nằm trong khoảng từ 1198 đến 1283 gram thì cần có số liệu thống kê để tìm ra nên chọn chế độ ăn kiêng nào.

Đằng sau những con số là gì?

Công việc của một nhà thống kê là sự kết hợp đáng kinh ngạc giữa nghệ thuật và khoa học: khi phát triển các mô hình toán học phản ánh các hiện tượng quan sát được, đó là một nghệ thuật và khi đưa ra kết luận trong khuôn khổ logic toán học chặt chẽ, đó là một khoa học.

Matematika, nền tảng của thống kê, mang lại cho nó sức mạnh to lớn: một mô hình toán học có thể mô tả tốt các hiện tượng xảy ra trong nhiều lĩnh vực hoạt động của con người, ví dụ như trong chính trị, công nghiệp, y học và nông nghiệp.

Thông thường dữ liệu là kết quả của các phép đo. Một ví dụ là heo con được nuôi theo các chế độ ăn khác nhau.

⟦folio 22⟧

---
running_head:
folio:
---

Trường hợp này thành công do sự khác biệt tự nhiên giữa các heo con, ngay cả khi khi bắt đầu thí nghiệm chúng giống nhau và được nuôi trong điều kiện bình đẳng. Về mặt thống kê, đây chính xác là trường hợp xảy ra với những biến đổi tự nhiên như vậy; chúng đại diện cho số liệu thống kê cơ bản, quan trọng nhất và đại chúng dưới nhiều tên gọi. Tên gọi chung của chúng là những sai lệch hoặc sai sót sai sót, nhưng nó không hoàn toàn thuận tiện, ít nhất là trong sinh học. Việc Joe cao hơn Bill không có nghĩa là cả hai người đều có chiều cao sai. Một cái tên hiện đại hơn cho một số biến thể tự nhiên là tiếng ồn, một thuật ngữ được đưa vào thống kê từ lý thuyết truyền thông và được gọi là tiếng ồn nền.

Trước tiên, trích dẫn ví dụ về heo con, chúng tôi theo dõi diễn biến lịch sử của các sự kiện, vì các phương pháp thống kê thường bắt nguồn từ các thí nghiệm nông nghiệp. Mặc dù thống kê sử dụng nhiều khái niệm toán học lâu đời, đặc biệt là xác suất dễ hiểu, nhưng nó vẫn còn là đứa trẻ của thế kỷ 20. Người sáng lập các phương pháp thiết kế và phân tích thí nghiệm hiện đại, R. A. Fisher (1890–1962), đã thực hiện công việc xử lý dữ liệu cơ bản từ các thí nghiệm nông nghiệp tại Trạm thí nghiệm Rothamsted ở Hertfordshire. Nhiều phương pháp được phát triển lúc bấy giờ hiện đã được chấp nhận, với những sửa đổi nhỏ, trong các lĩnh vực hoạt động đa dạng của con người như công nghiệp, y học và khoa học xã hội.

Hãy làm quen với các lỗi của người dùng

Những sai lệch (hoặc tiếng ồn) sai sót, trong ví dụ với heo con được thể hiện ở sự khác biệt về trọng lượng, có tính chất không thể đoán trước. Khi được cho cùng một chế độ ăn, một con heo con có năng suất tốt hơn mức trung bình một chút, trong khi những con khác có năng suất kém hơn một chút. Mặt khác, có thể giảm những sai lệch không mong muốn đó bằng cách chọn heo con giống nhau nhất có thể và đặt chúng trong điều kiện bình đẳng. Các biện pháp phòng ngừa kiểu này có thể tốn kém nhưng không loại bỏ được hoàn toàn tiếng ồn, vì không có biện pháp phòng ngừa nào có thể loại bỏ được những khác biệt vốn có trong di truyền.

Tiếng ồn có nghĩa là một nhóm heo con khác sẽ cho kết quả khác với thí nghiệm của chúng tôi. Lỗi do nhiễu gây ra được gọi là "lỗi lấy mẫu ngẫu nhiên hoặc lỗi quá trình - lỗi ngẫu nhiên hoặc lỗi lấy mẫu". Từ "ngẫu nhiên" phản ánh tính không thể đoán trước của nó và "chọn lọc" có nghĩa là các mẫu khác nhau (trong ví dụ của chúng tôi là heo con) cho kết quả khác nhau.

Một thử nghiệm được thiết lập để quyết định xem liệu một chế độ ăn kiêng cụ thể có tốt hơn về mặt trung bình hay không và nếu có thì ở mức độ nào. Chúng tôi sẽ chỉ nhận được số liệu chính xác cho một mẫu lợn con cụ thể, nhưng số liệu thống kê cung cấp cho chúng tôi một công cụ mà chúng tôi có thể sử dụng để thiết lập một điều quan trọng và thú vị hơn, đó là: kết quả của việc áp dụng bất kỳ chế độ ăn nào cho toàn bộ (bộ) lợn con sẽ giống như trong thí nghiệm.

Trong trường hợp này, chúng tôi quan tâm đến các lỗi hệ thống do một chế độ ăn uống cụ thể, nhưng sự hiện diện của nhiễu khiến việc xác định ý nghĩa thực sự của chúng trở nên khó khăn.

Công việc của nhà thống kê không chỉ là tách các lỗi hệ thống ra khỏi nhiễu hoặc các biến thể ngẫu nhiên. Có nhiều hệ thống mà hành vi của chúng trong một khoảng thời gian ngắn là không thể đoán trước được, tức là được xác định chủ yếu bởi các yếu tố ngẫu nhiên, trong khi trong một khoảng thời gian dài, nó trở nên đều đặn và có thể dự đoán được. Hành vi của một hệ thống trong đó các yếu tố ngẫu nhiên đóng vai trò chính được gọi là “quá trình ngẫu nhiên”, một cái tên có phần khoa trương được đặt cho bất cứ thứ gì phát triển ngẫu nhiên.

⟦folio 23⟧

---
running_head:
folio:
---

Bưu điện thành phố là một mô hình tốt để nghiên cứu các hiện tượng như việc xếp hàng. Nói chung, một số cửa sổ thanh toán hoặc điểm dịch vụ nhất định thực hiện một số hoạt động theo yêu cầu của khách hàng: ở cửa sổ cuối cùng, một bà lớn tuổi chỉ cần một con tem cho một tấm bưu thiếp, ở cửa sổ tiếp theo, người chuyển phát nhanh từ một tổ chức sẽ mua một số tem bưu chính và bảo hiểm đắt tiền có mệnh giá khác nhau. Ngoài ra, còn có những người xếp hàng muốn đặt hàng qua bưu điện, nhận lương hưu, trả tiền điện thoại hoặc hỏi giá bưu điện, v.v.

Dựa trên kinh nghiệm, nhân viên bưu điện có thể tưởng tượng một cách chính xác xem họ sẽ phải phục vụ bao nhiêu người trong một ngày cụ thể. Họ cũng biết rõ về việc trung bình cần bao nhiêu thời gian để phục vụ một khách hàng và có thể cho bạn biết một cách tổng quát thời gian thay đổi tùy theo khách hàng như thế nào. Nhưng sự không chắc chắn càng lớn hơn khi nói đến thời gian mà vị khách tiếp theo sẽ xuất hiện và thời gian cần thiết để phục vụ anh ta.

Hệ thống cũng bị quy định bởi thực tế là không thể tưởng tượng được hành vi của khách truy cập: liệu anh ta (hoặc cô ta) sẽ đứng ở hàng ngắn nhất, liệu anh ta sẽ xếp hàng gần lối vào nhất hay hàng được phục vụ tốt bởi cuộc họp; liệu anh ta có chọn hàng đợi hay không, cố gắng “đoán” thời gian cần thiết để được phục vụ; nếu trong một hàng, anh ta thấy nhiều người với các mẫu đơn xin giấy tờ, thì có lẽ anh ta sẽ không vào được, vì anh ta biết rằng đây là một quá trình lâu dài; Rõ ràng là anh ta không đứng xếp hàng, nơi có nhiều người đứng, mỗi người cầm một chồng giấy trên tay. Một du khách có hiểu biết có thể nhanh chóng ước tính thời gian cần thiết để phục vụ mỗi hàng sẽ đứng trong hàng, không nhất thiết là hàng nhỏ nhất, mà anh ta cho rằng đang di chuyển nhanh. Hệ thống sẽ càng trở nên phức tạp hơn nếu những người đang di chuyển nhanh ở hàng tiếp theo di chuyển vào đó.

Khi điều chỉnh hệ thống xếp hàng, người ta cố gắng đảm bảo sự ổn định trong hoạt động của nó theo nghĩa là việc xếp hàng dài cũng như các khoản nợ “thời gian ngừng hoạt động” của người vận hành là rất hiếm. Tuy nhiên, ngay cả một hệ thống ổn định cũng có thể bị phá hủy bởi một sự thay đổi nhỏ về điều kiện. Hệ thống có người lái có thể hoạt động tốt nếu trung bình mỗi phút có một khách hàng đến, nhưng nếu khoảng cách trung bình giữa các lần đến là 57 giây, hệ thống sẽ trở nên hỗn loạn. Và nếu dịch vụ không tăng tốc, hàng đợi sẽ ngày càng tăng.

Không chỉ người dân xếp hàng mà còn cả tàu cập cảng, xe tải giao hàng, lấy hàng từ nhà máy hoặc đưa về cửa hàng.

Để nghiên cứu các quá trình ngẫu nhiên, đặc biệt là các hệ thống xếp hàng, lý thuyết thống kê. Và máy tính điện tử giúp anh ta xây dựng (chơi) một mô hình và theo đúng nghĩa đen là chỉ trong vài giây tái tạo hoạt động của một hệ thống mà anh ta phải xếp hàng trong vài tuần hoặc thậm chí nhiều năm. Mô phỏng giúp khám phá tác động của những thay đổi như giới thiệu điểm dịch vụ bổ sung hoặc tăng tốc dịch vụ.

Tiết kiệm tài nguyên

Trong thời đại của chúng ta, hơn bao giờ hết, chúng ta nhận thức được sự cần thiết phải tiết kiệm tài nguyên thiên nhiên hoặc tiền bạc, chúng ta đã học cách thu thập dữ liệu đúng cách. Không chỉ trong các thí nghiệm khoa học mà còn trong công nghiệp và thương mại, việc thu thập và phân tích dữ liệu là phương tiện duy nhất để có được câu trả lời đáp số cho các câu hỏi quan trọng. Lời giải sự cố kỹ thuật có thể tiết kiệm cho công ty hàng nghìn đô la. Các thí nghiệm phải được thiết kế để thu được thông tin chính xác (thường ở dạng

⟦folio 24⟧

---
running_head:
folio:
---

hoàn cảnh rất khó khăn) càng sớm càng tốt.

Ví dụ: một nhà máy sản xuất phân bón có tổ chức có thể sản xuất số lượng sản phẩm khác nhau nếu một hoặc nhiều yếu tố bên ngoài, chẳng hạn như độ tinh khiết của thuốc thử, nhiệt độ, áp suất, độ ẩm và thời gian xử lý thay đổi. Những yếu tố này có liên quan với nhau và để tìm ra sự kết hợp phù hợp giữa chúng, đôi khi cần phải thử và sai. Statistik có thể giảm thiểu yếu tố ngẫu nhiên và nhanh chóng thu được đáp số chính xác.

Để cho thấy một nhà thống kê có thể giúp đỡ như thế nào, hãy giả sử rằng số lượng thực phẩm chỉ được xác định bởi hai yếu tố - áp suất và nhiệt độ. Trong một thí nghiệm, chúng tôi đo hiệu suất sản phẩm ở áp suất và nhiệt độ nhất định. Mục tiêu của chúng tôi là tìm ra sự kết hợp giữa chúng để tối đa hóa năng suất.

Để giải thích cách giải quyết vấn đề này, chúng ta cần sử dụng một phép loại suy. Giả sử chúng ta có một bản đồ đường viền mà trên đó chúng ta có thể xác định độ cao của bất kỳ điểm nào, biết vĩ độ và kinh độ của nó. Bây giờ chúng ta hãy tưởng tượng rằng nhiệt độ là vĩ độ, áp suất là kinh độ và sản lượng là độ cao. Do đó, chúng tôi đang tìm kiếm đỉnh cao nhất trên bản đồ.

Mặc dù bản đồ không được hiển thị cho chúng tôi nhưng nó cho phép chúng tôi chọn các điểm rõ ràng bằng cách chỉ định vĩ độ và kinh độ của chúng, sau đó đưa ra chiều cao của từng điểm trong số bốn điểm. Biết những giá trị này, bạn có thể biết được một số đặc điểm của khu vực. Bằng cách tìm kiếm một đỉnh, chúng ta sẽ có được thông tin bổ sung bằng cách chọn các điểm tiếp theo rõ ràng theo hướng mà mỗi điểm đều liên quan đến các điểm đầu tiên của chúng ta là “lên dốc”. Quá trình này có thể được chính thức hóa về mặt toán học và được gọi là phương pháp "đi lên theo vòng tròn".

*) Trong tài liệu của chúng tôi, người ta thường xem xét việc đi xuống khe núi và phương pháp này được gọi là phương pháp đi xuống nhanh. (Lưu ý mỗi.)

Sử dụng sự tương tự này, người thực nghiệm chọn các kết hợp rõ ràng giữa nhiệt độ và áp suất (tương ứng với vĩ độ và kinh độ) và xác định bằng thực nghiệm hiệu suất của từng kết hợp đó. Sau đó, anh ta chọn những cái rõ ràng khác theo hướng phát triển hữu ích nhất và tiếp tục với tinh thần tương tự cho đến khi đạt đến đỉnh cao.

Nói chung, điều này giống với phương pháp được sử dụng để leo núi. Trừ khi có những chướng ngại vật rất nghiêm trọng trên đường đi, chúng ta chọn con đường dẫn thẳng lên. Có hai điểm khác biệt trong tình huống thực nghiệm: thứ nhất, chúng ta không có hình ảnh liên tục, chúng ta chỉ biết độ cao của các điểm đã chọn (tương ứng với các điểm thực nghiệm của chúng ta); thứ hai, nếu chúng ta lặp lại thí nghiệm ở cùng nhiệt độ và cùng áp suất, thì theo quy luật, chúng ta sẽ không đạt được năng suất tương tự do tiếng ồn hoặc lỗi lấy mẫu. Điều này tương tự như việc đọc vĩ độ và kinh độ chính xác từ bản đồ, nhưng mắc phải những lỗi ngẫu nhiên nhỏ khi xác định độ cao.

Nếu có một số đặc điểm

Nếu chúng ta biết hai hoặc nhiều đặc điểm của một người, liệu những đặc điểm này có giúp phân biệt giữa các cá nhân thuộc hai chủng tộc khác nhau không? Hầu hết mọi người thoạt nhìn có thể phân biệt người Trung Quốc với người Nigeria, nhưng họ ít có khả năng phân biệt người Tanzania với người Nigeria trừ khi họ biết đủ rõ về hai quốc gia này.

Những người thuộc các quốc tịch khác nhau không chỉ khác nhau về các đặc điểm chất lượng như màu da, tóc và quần áo mà còn có thể khác nhau về hình dáng và chiều cao, điều này hỗ trợ cho việc mô tả định lượng.

Người ta có thể hỏi: ở một số cá nhân có bao nhiêu chủng tộc khác nhau? Một câu hỏi khác có thể được đặt ra như sau: có dữ liệu về một số lượng cá thể nhất định thuộc hai chủng tộc trở lên, làm sao dữ liệu này có thể được xác định?

⟦folio 25⟧

---
running_head:
folio:
---

Hình 1. Chiều dài và độ dày xương đùi của người (●) và khỉ (○).

phân biệt một chủng tộc với một nhóm quy nạp khác? Bài toán của loại đầu tiên được gọi là phân loại bài toán, loại thứ hai - là nhận dạng bài toán. Đây là một ví dụ nhận dạng đơn giản. Antipologus có một số mẫu vật xương đùi của loài vượn và một số mẫu vật của người sơ khai. Anh ta đo chiều dài và độ dày của mỗi xương và vẽ chúng trên biểu đồ như trong hình 1.

Từ hình rõ ràng là chiều dài và độ dày của xương thuộc loài obozy chồng lên nhau. Tuy nhiên, nếu nhìn vào các vòng tròn tương ứng với một người và những vòng tròn tương ứng với một con khỉ, chúng ta sẽ thấy chúng được chia thành hai nhóm và sự trùng lặp của chúng là không TUYỆT VỜI. Một đường thẳng nối tại hình điểm 40 trên trục chiều dài và điểm 5 trên trục độ dày sẽ tạo ra ranh giới hợp lý giữa hai nhóm. Với một số trường hợp ngoại lệ, những điểm áp dụng cho con người nằm trên ranh giới này và những điểm đề cập đến khỉ nằm bên dưới.

Rõ ràng, đối với bất kỳ điểm nào nằm chính xác trên đường thẳng, biểu thức “chiều dài + 8×độ dày” bằng 40. Đối với một điểm phía trên đường thẳng, biểu thức này lớn hơn 40 và đối với một điểm bên dưới đường thẳng thì nó nhỏ hơn 40.

Vì các điểm tương ứng với một người chủ yếu nằm phía trên đường thẳng và đối với con khỉ - bên dưới nó, nên các xương khác không rõ nguồn gốc có thể được phân loại như sau: chúng thuộc về một người nếu biểu hiện

“chiều dài+8×độ dày” lớn hơn 40 và thuộc về khỉ nếu nó nhỏ hơn 40. Ở đây chúng ta coi tất cả xương đều thuộc về người hoặc khỉ. Khi làm như vậy, đôi khi chúng ta sẽ mắc sai lầm, nhưng hy vọng là không quá thường xuyên. Statistik có các cách công thức để xác định dòng “tốt nhất” - một ranh giới giống như ranh giới mà chúng tôi đã vẽ bằng mắt ở hình 1. Trong trường hợp này, trong từ “tốt nhất”, chúng tôi bao gồm ý nghĩa là số lượng phân loại không chính xác dự kiến ​​sẽ càng nhỏ càng tốt. Chúng ta có thể đánh giá và đạt được độ chính xác.

Chức năng

chiều dài + 8 × độ dày

được gọi là chức năng nhận dạng, vì dựa trên giá trị của nó, có thể tạo ra xương của người và khỉ.

Thông thường, cần phải thực hiện nhiều hơn hai phép đo cho mỗi điểm và việc vẽ các điểm trên một tờ giấy là không đủ. Các nhà thống kê biết các phương pháp giảm thiểu khả năng phân loại sai. Điều trên áp dụng cho trường hợp có nhiều hơn hai nhóm: ví dụ, một mẫu xương hóa thạch có thể thuộc về một số loài động vật.

Bài toán phân loại và công nhận không hề bị cạn kiệt bởi vòng tròn bài toán liên kết với một số đặc điểm. Ví dụ, một nhà sinh vật học có thể đặt bẫy để bắt côn trùng di chuyển theo hướng gió thịnh hành. Anh ta sẽ ghi lại số lượng côn trùng của từng loài bị mắc vào bẫy mỗi ngày và thay đổi tốc độ gió để kiểm tra lý thuyết cho rằng côn trùng bay theo hướng hoặc chế độ gió. Dữ liệu thực nghiệm của ông xác nhận lý thuyết rằng nhiều côn trùng sẽ bị mắc vào bẫy khi gió mạnh theo một hướng nhất định và ít côn trùng hơn khi gió yếu hoặc gió mạnh, nhưng cơn mưa rào không bắt được bẫy.

⟦folio 26⟧

---
running_head:
folio:
---

Dữ liệu quan sát được có thể được biểu diễn bằng đồ họa bằng cách vẽ đồ thị lực gió trên một trục và số lượng côn trùng bắt được mỗi ngày trên trục kia.

Hãy để kết quả của thí nghiệm tạo thành hình ảnh như trong hình 2. Dữ liệu thực nghiệm cho thấy nhiều côn trùng bị cuốn vào gió mạnh và ít côn trùng hơn trong gió yếu ủng hộ giả thuyết rằng côn trùng bay theo hướng gió hoặc bị gió thổi bay.

Một cảnh báo là theo thứ tự ở đây. Sự phụ thuộc giữa các biến, đặc biệt là những biến số tỷ lệ thuận ít nhiều trực tiếp, thường được xem là nguyên nhân và kết quả. Trong trường hợp gió và côn trùng, khá hợp lý khi cho rằng điểm của côn trùng bị ảnh hưởng bởi sức mạnh của gió. Sự giải thích này là tự nhiên và nó được xác định bởi ý tưởng của chúng ta về bản chất của sự vật. Chúng tôi sẽ không kết luận rằng số lượng côn trùng bị bắt ảnh hưởng đến lực gió. Điều này trái với lẽ thường và sẽ mâu thuẫn với sự hiểu biết của chúng ta về các quy luật vật lý và sinh học. Chúng ta biết đủ về nguyên lý tạo ra gió và ảnh hưởng động lực của gió lên côn trùng.

Mặt khác, nếu có mối quan hệ tỷ lệ thuận, chặt chẽ giữa số lượng kem bán ra trong một năm nhất định và số lượng kính râm được bán ra, thì không cần phải coi những sự kiện này là nhân quả: cả hai đại lượng đều bị ảnh hưởng bởi khí hậu và không có bằng chứng nào cho thấy việc ăn kem làm thay đổi độ nhạy của mắt với ánh sáng hoặc việc đeo kính râm gây ra cảm giác thèm ăn kem.

Từ góc độ thương mại

Thống kê ngày càng được sử dụng nhiều trong công nghiệp và thương mại. Chủ một chuỗi cửa hàng rau đảm bảo rằng sản phẩm ở tất cả các chi nhánh đều có chất lượng tốt và chất lượng này được duy trì ở mức cao.

Hầu hết các hợp đồng cung cấp đều quy định rằng không được có nhiều hơn một tỷ lệ nhỏ nhất định các mặt hàng lặt vặt hoặc các mặt hàng bị lỗi trong mỗi chuyến hàng. Nếu mỗi lô không đáp ứng yêu cầu này, nhà cung cấp có nghĩa vụ thay thế cam của sản phẩm hoặc đồng ý bán lô đó với giá giảm hoặc thay thế toàn bộ lô. Khó khăn với yêu cầu này là việc thử nghiệm từng sản phẩm có thể rất tốn kém (hoặc thậm chí không thể thực hiện được nếu liên quan đến việc tiêu hủy sản phẩm). Việc kết luận lô hàng có được chấp nhận hay không được đưa ra trên cơ sở chỉ kiểm tra một mẫu hàng, hoặc mẫu nhất định.

Giám đốc một cửa hàng rau củ mua vài nghìn hộp bưởi và quy định cụ thể sẽ trả đủ giá nếu trong mẫu 20 hộp có hơn 98% trái đạt chất lượng cao. Cách làm này không đảm bảo toàn bộ lô hàng chứa hơn 98% hàng chất lượng nhưng ít nhất cũng cho thấy số lượng trái cây hư hỏng không lớn. Những loại kiểm tra này là một ví dụ về kiểm soát chất lượng.

Tiếp theo, những người kế toán, những người nắm giữ cân số, sử dụng các phương pháp thống kê để tiết kiệm tiền. Ví dụ: một số công ty nhận được 5123 hóa đơn cho việc giao các bộ phận và mỗi hóa đơn

(Về phần kết xem trang 52)

⟦folio 27⟧

---
running_head:
folio:
---

Chúng tôi đã chạy chuyên mục này từ số này đến số khác kể từ khi thành lập tạp chí. bài toán được xuất bản trong đó không phải là tiêu chuẩn, nhưng lời giải của chúng không yêu cầu kiến ​​thức ngoài phạm vi chương trình học ở trường. Nan khó hơn bài toán được thay thế bằng dấu hoa thị. Sau khi hình thành bài toán, chúng tôi thường cho biết ai đã đề xuất điều đó cho chúng tôi. Tất nhiên, không phải tất cả những bài toán này đều được xuất bản lần đầu tiên.

Lời giải bài toán từ số này phải được gửi chậm nhất là ngày 15 tháng 12 năm 1992 đến địa chỉ: 103006, Moscow, K-6, st. Tverskaya-Yamskaya thứ nhất, 1/2, «Kvant». Lời giải bài toán từ các số khác nhau của tạp chí hoặc trong các chủ đề khác nhau (toán học và vật lý) được phân bổ trong các phong bì khác nhau. Trên phong bì, ở cột “Tới”, viết: “Bài toán Kvant Số 10-92” và các số bài toán, lời giải mà bạn đang gửi, ví dụ “M1366” hoặc “F1373”. Ở cột “…địa chỉ người gửi”, vui lòng ghi họ và tên rõ ràng. Bức thư bao gồm một phong bì có ghi địa chỉ của bạn và bộ tem bắt buộc (trong phong bì này bạn sẽ nhận được kết quả xác minh lời giải).

Các điều kiện của mỗi bản gốc bài toán được đề xuất xuất bản được chỉ định trong một phong bì riêng, thành hai bản sao cùng với giải pháp của bạn cho bài toán này (đánh dấu trên phong bì: “Bài toán Kvant, bài toán mới trong vật lý” hoặc “... mới bài toán trong toán học”).

Ở đầu mỗi chữ cái, vui lòng cho biết số trường của bạn và lớp bạn sẽ học.

Bài toán M1366–M1370 được đưa ra tại Cuộc thi Optimide toàn Nga về Toán học năm 1992.
