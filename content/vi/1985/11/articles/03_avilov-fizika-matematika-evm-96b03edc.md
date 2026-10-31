---
id: 1985-11-avilov-fizika-matematika-evm-96b03edc
issue: kvant_1985_11
year: 1985
number: "11"
title: Vật lý + Toán + Máy tính
authors:
  - Авилов В. В.
rubric: osnovnye-stati
page_first: 4
page_last: 8
page_labels: 2-6
tag: HA75
lang: vi
source: kvant_digital
extraction: vision
content_sha256: 629b7ccc7cba5069bca9349e627c08ee58038623f925ad187dc630d6bf3625ba
prompt_sha256: draft-1
translated_from: content/ru/1985/11/articles/03_avilov-fizika-matematika-evm-96b03edc.md
source_content_sha256: 53a844f697ca4c482bcaa4bde2d88500d37f17c54289484be7baaa8764af5cc2
translation_model: draft
translation_run: vi-draft-2026-10-31
translation_quality: draft
---

⟦folio 2⟧

Vật lý Toán học Máy tính

Ứng viên Khoa học Vật lý và Toán học
V. V. AVILOV

Bài viết này sẽ tập trung vào vật lý tính toán, một ngành khoa học mới ra đời ở điểm giao thoa giữa vật lý và toán ứng dụng. Ngay khi máy tính tốc độ cao xuất hiện, chúng bắt đầu được sử dụng trong mọi lĩnh vực vật lý. Ở đây chúng ta sẽ gác lại vai trò của máy tính trong các thí nghiệm vật lý hiện đại, những thí nghiệm mà ngày nay thường đơn giản là không thể thực hiện được nếu không sử dụng máy tính và sẽ chuyển sang sử dụng chúng trong nghiên cứu lý thuyết.

Tính toán Monte-Carlo về các tính chất của hợp kim nhị phân bằng mô hình Ising. Máy tính phân tán các nguyên tử loại A (hình vuông sáng trên màn hình) trên một mạng phẳng 16x16, để lại những khoảng trống còn lại cho các nguyên tử loại B (hình vuông tối), và bây giờ đếm số lần các nguyên tử thuộc các loại khác nhau va chạm nhau.

Hiện nay, có hai hướng chính trong việc sử dụng máy tính trong vật lý lý thuyết. Trong cách tiếp cận đầu tiên, nhà vật lý cố gắng đi xa nhất có thể trong lời giải bài toán trước khi chuyển sang máy tính. Máy chỉ được sử dụng để tính các khoảng, tổng, để tìm lời giải các phương trình phức tạp không thể thu được bằng phương pháp giải tích (dưới dạng công thức). Một cách tiếp cận khác được gọi là mô hình hóa máy. Những người ủng hộ hướng này chỉ tính toán dựa trên các định luật vật lý cơ bản và kiểm tra kết quả tính toán, thử

⟦folio 3⟧

rút ra kết luận vật lý mới. Về nhiều mặt, những hoạt động như vậy gần giống với các thí nghiệm vật lý; đôi khi cái tên “thí nghiệm số” thậm chí còn được sử dụng. Trước tiên hãy xem xét cách tiếp cận đầu tiên.

Nếu bạn cần trợ giúp về máy tính

Ban đầu, các nhà vật lý không được phép sử dụng máy tính. Các tính toán được thực hiện bởi các chương trình. Điều này là do trên các máy tính thế hệ đầu tiên, các chương trình được biên dịch bằng cái gọi là mã máy, mã này khác nhau đối với từng loại máy tính. Rất khó để một người không chuyên về lập trình có thể viết và gỡ lỗi chương trình. Có sự phân công lao động rõ ràng: nhà vật lý viết các công thức, nhà toán học-lập trình viên tính toán từ đó. Một số lượng lớn bài toán đã được giải theo cách này, nhưng đồng thời cũng tính toán được nhược điểm của phương pháp này. Đối với nhiều bài toán, phương pháp này không đạt được lời giải chính xác. Trước hết, điều này là do máy tính thực hiện các phép tính với độ chính xác hữu hạn; việc thực hiện từng hành động dẫn đến lỗi làm tròn. Đối với hầu hết các máy tính, liên quan đến việc tính toán từng hành động nằm trong khoảng $10^{-8} - 10^{-16}$. Có vẻ như đây là độ chính xác rất cao. Nhưng vì máy tính thực hiện tới $10^8$ thao tác mỗi giây nên lỗi tính toán có thể nhanh chóng tích lũy.

Nếu cùng một đại lượng có thể được tính theo nhiều cách khác nhau thì chúng ta nói về các quá trình số khác nhau. Các quy trình số này có thể mạnh hoặc không mạnh đối với việc tích lũy các lỗi làm tròn. Thậm chí có những quá trình tích lũy quá trình làm tròn khiến phương pháp tính toán không thể áp dụng được chỉ sau một vài bước. Điều này có nghĩa là một nhà vật lý muốn thực hiện các phép tính số bằng các công thức của mình phải hiểu các quy trình số và tưởng tượng những phương pháp toán học ứng dụng nào anh ta có thể sử dụng trong công việc của mình. Rõ ràng là các nhà vật lý và toán học phải tương tác với nhau ở mọi giai đoạn - bắt đầu từ việc lập công thức bài toán và kết thúc bằng quá trình số. Hoàn cảnh này đã góp phần vào sự xuất hiện của một chuyên ngành - vật lý tính toán.

Chúng tôi cũng lưu ý rằng khả năng kết hợp các chuyên ngành như vậy cũng gắn liền với sự phát triển của các ngôn ngữ lập trình giúp việc “giao tiếp” với máy trở nên dễ dàng hơn. Màn hình tiện lợi*) đã đơn giản hóa việc tiếp xúc của người dùng với máy tính. Bạn hoặc thư viện chương trình đã được tạo; Bây giờ cần phải biên dịch lại chương trình cho lời giải tiêu chuẩn bài toán mỗi lần, sau đó sử dụng thư viện các chương trình tiêu chuẩn trong quá trình này. Các tạp chí đặc biệt cũng xuất hiện đăng các công trình về vật lý tính toán. Ở giai đoạn đầu, các tạp chí chỉ in nội dung của chương trình. Rõ ràng là điều này chỉ có thể được thực hiện với những chương trình đơn giản nhất. Thực tế là khi gõ ở nhà in, rồi khi “chuyển” chương trình từ tạp chí sang máy tính, chắc chắn sẽ xuất hiện lỗi. Vì vậy, hiện nay chỉ có mô tả về phương pháp tính toán được công bố; bản thân chương trình được lưu trữ trong một thư viện đặc biệt và gửi cho người dùng theo yêu cầu.

Vào đầu những năm 70, tại một trong những hội nghị về phương pháp tính toán hệ thống quang điện tử, các nhân viên của trung tâm máy tính thuộc Chi nhánh Siberia của Viện Hàn lâm Khoa học Liên Xô đã trình diễn công việc của tổ hợp chương trình do IMM tạo ra. Nửa ngày trước báo cáo, họ yêu cầu những người không phải là chim ưng định dạng bài toán để giải quyết vấn đề này trong công việc của họ. Tại cuộc họp buổi tối, cùng với các diễn giả, nhân viên CC đã giúp mọi người làm quen với giải pháp của họ cho những bài toán này, có được trên máy tính sử dụng một chương trình phức hợp. Rõ ràng là bài toán, lời giải, trước đây phải mất vài tháng, có thể được giải quyết trong vòng vài giờ. Một minh chứng sống động như vậy về khả năng của máy tính đã buộc họ phải có thái độ rất khôn ngoan đối với chúng.

Ngày nay, nhiều tổ hợp tương tự đã xuất hiện, định hướng

*) Đây là tên của tổ hợp màn hình và bàn phím trong một máy tính hiện đại, với sự trợ giúp của nó, cuộc đối thoại giữa nhà khoa học và máy móc được thực hiện. Chương trình được sao chép và xử lý trong máy tính trên màn hình và kết quả tính toán cũng được hiển thị trên đó.

⟦folio 4⟧

đến một vòng tròn nhất định bài toán. Một nhà vật lý sắp làm việc với một tổ hợp như vậy không cần phải lập trình để nghiên cứu các quá trình số để tìm sự ổn định. Máy sẽ tự thực hiện việc này, bạn chỉ cần viết các phương trình cơ bản và đặt các điều kiện ban đầu. Ở đầu ra, người dùng nhận được lời giải gốc ở dạng bảng và biểu đồ. Nếu cần thiết, tổ hợp thậm chí sẽ tạo ra một màng màu dựa trên kết quả đếm. Một nhà vật lý ngồi trước màn hình có thể điều khiển lời giải, thay đổi các giá trị tham số và thực hiện các điều kiện ban đầu khác nhau. Tất nhiên, việc tạo ra từng tổ hợp chương trình đòi hỏi sự làm việc chăm chỉ của các chuyên gia vật lý và toán học ứng dụng.

Thí nghiệm số

Sáu chiếc ghim đi theo chiều ngang trên một chiếc taxi tốc độ, khi tính chất vật lý của hiện tượng đang nghiên cứu được hiểu rõ ngay cả trước khi chuyển sang máy tính. Kết quả của những tốc độ này là cần thiết cho các mục đích thực tế.

Bây giờ chúng ta sẽ nói về một lĩnh vực khác của vật lý tính toán—mô hình hóa máy. Như đã đề cập, phương pháp mô hình hóa máy được đặc trưng bởi thực tế là chỉ có các mẫu cơ bản mô tả hệ thống được xác định.

Ví dụ: nếu phương pháp này được sử dụng để nghiên cứu các tính chất của khí, lỏng, plasma, thiên hà hoặc hệ khác bao gồm nhiều hạt, thì định luật tương tác của chúng cũng như tọa độ và vận tốc ban đầu của các hạt sẽ được xác định. Tiếp theo, họ soạn các phương trình chuyển động (*) và giải chúng bằng máy tính.

Quan sát sự phát triển của hệ thống và so sánh hành vi của hệ thống, chúng ta thu được

*) Trong cơ học cổ điển, phương trình chuyển động của mỗi hạt được tìm thấy dưới dạng định luật thứ hai của Newton. Nếu sự tích tụ của các hạt không thể coi là nhỏ so với tốc độ ánh sáng thì nên sử dụng các phương trình tương ứng của lý thuyết phương trình tương đối của cơ học lượng tử làm phương trình chuyển động.

⟦folio 5⟧

được mong đợi là kết quả của một thí nghiệm số như vậy, với dữ liệu thực nghiệm có sẵn hoặc với những gì được dự đoán bằng các phương pháp phân tích gần đúng, các nhà khoa học cố gắng xác định mô hình phát triển của nó.

Ở nhiều khía cạnh, phương pháp mô hình hóa máy tương tự như một thí nghiệm vật lý; bằng phương pháp này người ta cố gắng tái tạo, “sao chép” bản chất. Ưu điểm của mô hình hóa là nó cho phép chúng ta xem xét các hệ thống chưa thể thu được dữ liệu thực nghiệm (các quá trình ở áp suất cực cao, nhiệt độ, năng lượng hạt).

Khả năng của phương pháp này không phải là không giới hạn. Để mô tả hành vi của các phân tử trong 1 cm³ chất lỏng thực, cần theo dõi chuyển động của khoảng 1022 phân tử. Hơn nữa, đối với một máy tính lớn hiện đại, con số này quá lớn. Cho đến nay, các hệ thống bao gồm không quá 10⁶ hạt đều có sẵn để tính toán. Tuy nhiên, ngay cả khi xem xét một số lượng hạt “hạn chế” như vậy, trong nhiều trường hợp, các mô hình được tiết lộ là đặc trưng của một hệ thống cụ thể gồm một số lượng lớn các hạt.

Các phương pháp mô hình hóa máy hoạt động tốt hơn khi máy tính được triển khai chương trình trên đó càng mạnh. Trong những năm gần đây, họ bắt đầu tạo ra những chiếc máy tính đặc biệt, mỗi chiếc chỉ phù hợp với lời giải một dòng bài toán, có thể có một số sửa đổi, nhưng đây là dòng mà một chiếc máy tính như vậy có thể giải quyết tốt.

Có rất nhiều ví dụ khi mô hình máy tính dẫn đến những khám phá giúp cải thiện đáng kể quan điểm của chúng ta về thế giới vật chất.

Do đó, vào năm 1954, Enrico Fermi và các đồng nghiệp của ông đã sử dụng máy tính để mô phỏng sự lan truyền dao động trong chuỗi một chiều gồm các nguyên tử tương tác. Vì vậy, họ muốn hiểu trạng thái cân bằng nhiệt được thiết lập như thế nào trong chất rắn. Để mô hình hóa sự tương tác, người ta giả định rằng các nguyên tử lân cận được kết nối bằng liên kết. Từ xem xét lý thuyết sơ bộ, người ta đã biết rằng trong trường hợp lực căng F phải được hỗ trợ bởi các nguyên tử, gắn liền với sự thay đổi độ dài của nó Δx theo định luật tuyến tính tổng quát F = -k·Δx, trạng thái cân bằng nhiệt trong hệ không bao giờ được thiết lập. Đồng thời, người ta tin rằng chỉ cần đưa bất kỳ tính phi tuyến nào vào định luật tương tác của các nguyên tử là đủ (nghĩa là coi F(Δx) là một hàm phi tuyến) - và trạng thái cân bằng nhiệt sẽ được thiết lập trong một hệ thống như vậy trong một thời gian hữu hạn.

Trong công trình của họ, Fermi và các cộng sự của ông đã giảm tính phi tuyến đơn giản nhất bằng cách thêm một số hạng tỷ lệ với (Δx)² vào biểu thức lực F. Các phép tính số đã chỉ ra rằng trong trường hợp này trạng thái cân bằng nhiệt trong hệ thực sự đã được thiết lập, nhưng cực kỳ chậm. Thời gian đặc trưng của quá trình này lớn hơn nhiều lần so với những ước tính đã mang lại kết quả đáng kể về mặt lý thuyết. Kết quả đáng ngạc nhiên này đã kích thích các nghiên cứu số và phân tích sâu hơn. Người ta đã chứng minh rằng đối với một số dạng phụ thuộc phi tuyến của lực căng vào khoảng cách Δx, trạng thái cân bằng ấm trong hệ sẽ không bao giờ được thiết lập.

Hiện tại, hàng trăm, nếu không muốn nói là hàng nghìn bài báo đã được xuất bản trong đó các nghiên cứu số và phân tích cũng được thực hiện trên các hệ thống. Kết quả của những nghiên cứu này không tìm thấy

⟦folio 6⟧

ứng dụng tầm thường trong phạm vi rộng bài toán vật lý plasma, thủy động lực học, quang học, v.v.

Khi Fermi và các cộng sự của ông bắt đầu công việc, họ nhận ra rằng mô hình dây chuyền mà họ đã chọn không phải là vật rắn thực sự. Tinh thể thật có mạng ba chiều phức tạp; không chỉ những người hàng xóm gần nhất tương tác trong đó, và quy luật tương tác của các nguyên tử thành phố còn phức tạp hơn những gì được giả định trong công việc này. Tuy nhiên, một mô hình đơn giản của chuỗi một chiều cho phép những hậu quả có thể xảy ra của định luật tương tác KHÔNG TRỰC TUYẾN giữa các nguyên tử.

Mô hình Ising và bộ tạo số ngẫu nhiên

Tuy nhiên, không phải tất cả bài toán đều là tính chất của phương trình chuyển động số lời giải. Đối với loạt bài bài toán, một phương pháp mô hình hóa máy tính quan trọng như phương pháp Monte Carlo được sử dụng. Hãy làm quen với nó bằng cách sử dụng ví dụ nghiên cứu các chuyển pha. Nhưng trước tiên, hãy nói đôi lời về bản thân vấn đề chuyển pha, mà trong nhiều năm, do tính phức tạp của nó nên các nhà vật lý không thể hiểu hết được.

Sự chuyển pha cũng bao gồm các hiện tượng nổi tiếng như nóng chảy và sôi, cũng như nhiều hiện tượng ít quen thuộc hơn - sự chuyển đổi của kim loại sang trạng thái siêu dẫn và gel sang trạng thái siêu lỏng, trật tự của các hợp kim, v.v. Tất cả những điều này, thoạt nhìn, là những hiện tượng không giống nhau, có một đặc tính chung - khi một hệ thống tiếp cận quá trình chuyển đổi, sự tương tác của số lượng hạt ngày càng tăng của nó trở nên đáng kể, làm phức tạp việc sử dụng các phương pháp chung của vật lý lý thuyết. Đây là lúc máy tính ra tay giải cứu, cho phép bạn tính toán hoạt động của hệ thống phát hiện chuyển pha. Tuy nhiên, trước tiên bạn cần đưa ra một mô hình phù hợp - đơn giản, đồng thời phản ánh các đặc tính cơ bản của hệ thống.

Ví dụ, đây là cách chúng ta có thể mô tả quá trình chuyển pha từ trạng thái khí sang trạng thái lỏng. Hãy xem xét một mạng phẳng chứa $N$ nút chứa $m$ ($m < N$) nguyên tử. Người ta biết rằng sự tương tác giữa các nguyên tử giảm nhanh khi khoảng cách giữa chúng ngày càng tăng, do đó có thể giả định một cách đại khái rằng các nguyên tử trong mạng chỉ tương tác nếu chúng ở trong các nút mạng lân cận. Mô hình này được gọi là mô hình Ising của khí mạng với tương tác lân cận gần nhất.

Ở nhiệt độ cao, các nguyên tử được phân bố trung bình đều khắp mạng tinh thể. Tuy nhiên, ở nhiệt độ đủ thấp, nhờ lực hút giữa các nguyên tử, chúng hình thành với nhau, chứa đầy các thể tích mạng tân hướng. Do đó, khi nhiệt độ giảm, hơi nước đầu tiên trở nên bão hòa và sau đó ngưng tụ thành những giọt chất lỏng.

Để tìm ra nhiệt độ tại đó xảy ra “ngưng tụ” của khí mạng tinh thể (chuyển pha), hoặc, ví dụ, để tìm ra nhiệt của quá trình chuyển pha hoạt động như thế nào, cần có khả năng tính toán năng lượng của hệ tương tác của các nguyên tử đối với từng phương pháp sắp xếp của chúng dọc theo mạng (cấu hình). Khó khăn chính là số cách sắp xếp các nguyên tử tại một nút mạng rất nhanh chóng quay trở lại $N$ khi số lượng nút tăng lên. Nếu, ví dụ,
