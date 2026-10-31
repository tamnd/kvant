---
id: 2021-4-vlasov-kak-voznikaet-haos-zakonyi-ravnovesnogo-haosa-idealnogo-gaza-29b1e225
issue: kvant_2021_4
year: 2021
number: "4"
title: Làm thế nào sự hỗn loạn phát sinh. Định luật hỗn loạn cân bằng của khí lý tưởng
authors:
  - Власов А. И.
rubric: fizicheskiy-fakultativ
rubric_sub: Физический факультатив
page_first: 32
page_last: 39
page_labels: 33, 34, 37
tag: WP2G
lang: vi
source: kvant_digital
extraction: native
content_sha256: 4856988066ab47106b3a9382f66b7383e01432675bde99e8aa8be232e34c7643
prompt_sha256: draft-1
translated_from: content/ru/2021/04/articles/04_vlasov-kak-voznikaet-haos-zakonyi-ravnovesnogo-haosa-idealnogo-gaza-29b1e225.md
source_content_sha256: 9ab4a19431349b3e229fca6e1e0be63048b90e357aff8e828ac47880799cac9c
translation_model: draft
translation_run: vi-draft-2026-10-31
translation_quality: draft
---

⟦folio none⟧

TÙY CHỌN VẬT LÝ

Làm thế nào sự hỗn loạn phát sinh. Định luật hỗn loạn cân bằng của khí lý tưởng

A. VLASOV

Vào tháng 9 năm 1859, TẠI CUỘC HỌP CỦA Hiệp hội Khoa học Anh, J. Maxwell đã báo cáo về nghiên cứu của mình trong lĩnh vực lý thuyết động học phân tử của chất khí. Trong báo cáo này, lần đầu tiên định luật thống kê phân bố vận tốc phân tử được trình bày. Với công trình này, xác suất xuất hiện trong lý thuyết động học của chất khí và sự hình thành vật lý thống kê bắt đầu. Ở đây rất thích hợp để trích dẫn cuốn sách của L.D. Landau và E.M. Lifshitz “Vật lý tĩnh”: “Chủ đề của vật lý thống kê... là nghiên cứu về một loại định luật đặc biệt chi phối hành vi và tính chất của các vật thể vĩ mô, tức là các vật thể bao gồm một số lượng khổng lồ các hạt riêng lẻ - nguyên tử và phân tử... Thoạt nhìn, người ta có thể kết luận từ điều này rằng với sự gia tăng số lượng hạt thì độ phức tạp và phức tạp của các tính chất của một hệ cơ học sẽ tăng lên không thể tưởng tượng được và chúng ta không thể tìm thấy dấu vết của bất kỳ sự đều đặn nào trong hành vi của một hệ thống cơ học." Tuy nhiên, điều này không phải như vậy, và sau này chúng ta sẽ thấy rằng với một số lượng rất lớn các hạt, những khuôn mẫu đặc biệt mới sẽ xuất hiện. Chúng ta hãy lưu ý ngay rằng chúng ta sẽ giới hạn việc nghiên cứu các hệ thống lý tưởng cổ điển đơn giản nhất. Chúng ta hãy thử tìm hiểu làm thế nào khi số lượng hạt cấu thành một hệ thống tăng lên thì một trật tự thống kê giới hạn sẽ xuất hiện trong đó như thế nào. Đương nhiên, ở đây sẽ không đẹp (nhưng một học sinh không thể hiểu được)

DOI: https://doi.org/10.4213/kvant20210403

⟦column⟧

tuy nhiên, toán học chúng ta không thể làm được nếu không có những công thức thể hiện trật tự hỗn loạn. Máy tính sẽ trả lời các câu hỏi được đặt ra (tất nhiên, chúng tôi sẽ cung cấp cho nó chương trình thích hợp). Hãy bắt đầu bằng cách tinh chỉnh mô hình khí lý tưởng.

Mô hình khí lý tưởng Từ sách giáo khoa người ta biết rằng khí lý tưởng là một hệ gồm các điểm vật chất không tương tác. Nhưng trong mô hình như vậy không có yếu tố chính - không có khả năng xuất hiện hỗn loạn và theo đó, không có khả năng xuất hiện một trật tự xác suất. Rõ ràng là sự hỗn loạn trong một hệ kín (cô lập) gồm các hạt không tương tác chỉ có thể phát sinh do sự va chạm của chúng. Va chạm chỉ có thể xảy ra giữa các hạt có kích thước. Nếu chúng ta coi các phân tử khí là những quả bóng đàn hồi thì sẽ nảy sinh vấn đề về thể tích “loại trừ”. Khí gồm những quả cầu đặc không còn là khí lý tưởng nữa và trạng thái cân bằng của nó không còn tuân theo phương trình Clapeyron–Mendeleev nữa. Nhưng tình trạng này có thể được khắc phục bằng cách đề xuất một cơ chế va chạm ảo đặc biệt. Tại thời điểm xảy ra va chạm ảo, những thay đổi về tốc độ được xác định (được tính toán), nhưng những thay đổi này tạm thời bị “hoãn lại”. Các quả bóng tiếp tục chuyển động và chỉ tại thời điểm khoảng cách ngắn nhất giữa tâm của chúng thì sự thay đổi chậm về tốc độ mới “bật”.

Phân bố Maxwell và định luật phân bố đều Ở đây chúng ta không thể làm gì nếu không có khái niệm xác suất. Chúng ta hãy đi sâu vào lĩnh vực lý thuyết xác suất cơ bản. Các quá trình vật lý có thể mang tính quyết định hoặc ngẫu nhiên. Theo đó, các tham số (đại lượng vật lý) đặc trưng cho các quá trình này là xác định hoặc ngẫu nhiên. Bản chất của các quá trình và các tham số của chúng được xác định trong các phép đo lặp lại. Đối với các đại lượng xác định, các phép đo lặp lại cho kết quả nhất quán (trong phạm vi sai số đo). Đối với các biến ngẫu nhiên, các phép đo lặp lại sẽ dẫn đến một tập hợp (phổ) các giá trị. Xác suất là một đặc tính của quá trình ngẫu nhiên. “Toán học” của cô ấy dựa trên ý tưởng

⟦folio 33⟧

THUỘC VẬT CHẤT

tọa độ hạt được tính bằng công thức $x_{i} x_{i}^{v} i$ dt, trong đó dt là khoảng thời gian rất ngắn. Khi các quả bóng chồng lên nhau, giai đoạn va chạm xảy ra. Vận tốc mới của các phân tử gặp phải được tính toán và chuyển động tiếp tục. Trong suốt quá trình thử nghiệm trên máy tính, thông tin cần thiết về trạng thái vật lý của hệ thống được thu thập. Trong trường hợp của chúng tôi, đây là số liệu thống kê về tốc độ và năng lượng của các phân tử. Hình 4 cho thấy phổ xác suất của vận tốc phân tử khí. Máy tính của chiếc xe này-

KHÔNG BẮT BUỘC

⟦column⟧

⟦figure⟧

Cơm. 5

⟦figure⟧

Cơm. 4

Teen có được cách này. Toàn bộ phạm vi tốc độ phân tử có thể được chia thành các ô nhỏ. Sau mỗi bước chuyển động, 1 được thêm vào các ô tương ứng (những ô có tốc độ phân tử giảm). Sau khi hoàn thành một thử nghiệm đủ dài, nội dung của các ô sẽ được chia cho số bước (số lần thử). Rõ ràng là bằng phép chia này, chúng ta xác định được xác suất tốc độ của các phân tử trong một khoảng thời gian nhất định. Đồ thị thu được chứng minh tính chất rời rạc của phổ vận tốc phân tử. Tổng cộng có 36 tiểu bang. Có thể nhận thấy rằng có sự đối xứng khá rõ ràng trong quang phổ. Và quan trọng nhất, phổ này phụ thuộc vào các điều kiện ban đầu. Điều này được xác nhận bằng biểu đồ lặp lại của hệ thống với các điều kiện ban đầu khác nhau (Hình 5). Điều thú vị là số lượng trạng thái vẫn giữ nguyên, nhưng bức tranh về quang phổ thay đổi đáng kể. Và có một sự bằng nhau hoàn toàn bất ngờ (đối với một hệ nhỏ như vậy chỉ có 2 hạt) về năng lượng trung bình của các hạt nhẹ và hạt nặng. Trong hai lần triển khai, tỷ lệ năng lượng trung bình khá gần bằng 1 (0,988 và 1,139).

⟦figure⟧

Cơm. 6

Khi số lượng hạt tăng lên 4 (hai cặp hạt, nhẹ - nặng), hàm xác suất thay đổi mạnh (Hình 6). Nó trở nên gần như liên tục. Số lượng trạng thái vượt quá 400 (số lượng ô tốc độ). Biểu đồ cho thấy tất cả các ô tốc độ đã được lấp đầy và độ chính xác của các phép tính không còn cho phép chúng tôi xác định được độ rời rạc nữa. Việc thay đổi trạng thái ban đầu trên thực tế không làm thay đổi phổ và do đó, khi số lượng hạt tăng thêm, người ta có thể chuyển sang các hàm mật độ xác suất. Để làm điều này, xác suất khoảng phải được chia cho kích thước của khoảng. Đồ thị trên Hình 7 thể hiện hàm mật độ xác suất của phép chiếu vận tốc cho 3 cặp hạt. Dấu chấm (chéo) – thí nghiệm trên máy tính, đường liên tục màu xanh tương ứng với hàm Maxwell lý thuyết cho trường hợp khí lý tưởng một chiều

$mv^{2}$

U v

m  $e^{2} kT. 2 S kT$

⟦folio 34⟧

KVAN T 2021/№4

⟦figure⟧

Cơm. 7

⟦column⟧

Mô hình khí lý tưởng hai chiều Ở đây mọi thứ thú vị hơn nhiều. Các mô hình khí ở chiều thứ hai và thứ ba phải có phổ vận tốc liên tục (với số lượng hạt nhỏ sẽ không còn phổ rời rạc). Điều này được xác định bởi tính liên tục của tham số góc quyết định sự thay đổi vận tốc trong quá trình va chạm. Bây giờ chúng ta hãy xem phổ vận tốc thay đổi như thế nào khi số lượng hạt tăng lên. Hình 10 thể hiện đồ thị của 2 hạt. Một kết quả rất bất ngờ và đẹp mắt là hàm mật độ xác suất tuyến tính (đối với hệ gồm hai hạt, sự có mặt của tốc độ cực đại là có khả năng xảy ra cao nhất). Điều này rất xa với hàm Maxwell. Nhưng ngay khi một hạt được thêm vào, hệ thống sẽ bắt đầu “sửa” (Hình 11). Với sự tăng thêm về số lượng hạt, hệ thống sẽ “hội tụ” rất nhanh dọc theo phổ vận tốc đến hàm Maxwell (Hình 12 đối với 16 hạt). Ở đây rất thích hợp để cung cấp thêm thông tin (cho những người đam mê lập trình)

⟦figure⟧

Cơm. 8

⟦figure⟧

Cơm. 10

⟦figure⟧

Cơm. 9

Biểu đồ cho thấy rằng đối với 3 cặp (6 hạt) đã có mối tương quan khá rõ ràng với hàm Maxwell. Biểu đồ sau (Hình 8) tương ứng với hệ thống gồm 10 cặp (20 hạt). Ở đây đường cong lý thuyết gần như trùng khớp với đường cong thực nghiệm; sự khác biệt chỉ có thể nhìn thấy được (dao động nhỏ) trong vùng vận tốc bằng không. Cuối cùng, đồ thị trong Hình 9 cho 50 cặp (100 hạt) minh họa rằng thí nghiệm và lý thuyết hoàn toàn phù hợp với nhau.

Cơm. 11

⟦folio 37⟧

BÀI KIỂM TRA

A được thực hiện nếu trong quá trình quay các thanh bị lệch một góc D 45 q? Lấy gia tốc rơi tự do bằng g 10 m $с^{2}$ thì có thể bỏ qua kích thước của các tải trọng. 2. Hệ dao động gồm một tải trọng $массой^{m,} лежаще-_{Рис.} 4$ đặt trên mặt phẳng nằm ngang nhẵn, một khối nhẵn không trọng lượng, hai sợi dây không trọng lượng, không dãn và ba lò xo không trọng lượng $жесткостью_{1}^{k} 2 3$ N cm $,_{2}^{k} 1 2$ N cm $и_{3}^{k} 1$ N cm tương ứng được nối như hình 5. Trọng tâm của tải trọng nằm trên cùng một phương ngang với vật gắn vào sợi chỉ và trục lò xo $жесткостью_{1}^{k}$. Ở vị trí cân bằng, mọi lò xo đều bị dãn. Giả sử rằng các sợi dây luôn luôn giữ nguyên $натянутыми,^{Рис.} 5$, hãy xác định tần số tròn Z của các dao động điều hòa nhỏ của tải. 3. Một bình chứa đầy có thể tích $V_{0} 5$ l chứa $m_{0} 2,5$ kg propan hóa lỏng $( C_{3} H_{8} ).$ Nếu một phần propan thoát ra bên ngoài thì propan lỏng và hơi bão hòa của nó sẽ ở trạng thái cân bằng. Tìm khối lượng $m_{1}$ của propan ở trạng thái khí trong bình khi D (%) của propan chứa ban đầu thoát ra khỏi bình này, nếu nhiệt độ của propan được giữ không đổi và bằng t 17 q C. Áp suất hơi bão hòa của propan ở nhiệt độ này là p 0,8 MPa. Khối lượng mol của propan là 0,44 g mol, hằng số khí phổ R là 8,31 J mol K. 4. Hai hạt tích điện trái dấu nằm trên trục x của hệ tọa độ Descartes cách nhau l 3 cm (Hình 6). Trong khi giữ một hạt bất động, hạt thứ hai chuyển động theo hướng trục y một khoảng $l_{1} 4$ cm. Trong trường hợp này, $A_{1}$ công việc đã được thực hiện. Cơm. 6

NGUYÊN VẬT LIỆU

⟦column⟧

Cần phải thực hiện công việc gì $A_{2}$ để di chuyển hạt thứ hai một khoảng $l_{2} 2$ cm theo hướng của trục x? 5. Có một tấm gương phẳng ở đáy ngang của bể cá. Một người cúi xuống nhìn thẳng xuống nước thì thấy ảnh của mắt mình trong gương cách gương 150 cm. Xác định độ dày của lớp nước H trong bể cá nếu mắt ở cách mặt nước h 10 cm. Coi chiết suất của nước bằng n 4 3. Xin lưu ý rằng đối với các giá trị nhỏ của đối số M, tính bằng radian, chúng ta có thể giả sử tan M | tội lỗi M | M.

Giai đoạn cuối

Giai đoạn cuối cùng của Olympic được tổ chức vào ngày 25–27 tháng 2 năm 2021 theo hình thức từ xa trên cổng https: Exam.distant.msu.ru. Để tham gia vào giai đoạn này, một số yêu cầu kỹ thuật nhất định đã được áp đặt tại nơi làm việc của đối tượng thử nghiệm (bạn có thể tìm thấy những yêu cầu này trên trang web Olympiad). Bài tập dành cho học sinh lớp 7–9 bao gồm bốn bài toán về các chủ đề được nghiên cứu như một phần của chương trình vật lý ở trường trung học cơ sở. Các nhiệm vụ dành cho học sinh lớp 10–11 được biên soạn đầy đủ theo Bộ mã hóa kỳ thi thống nhất quốc gia năm 2021 về Vật lý và bao gồm các phần chính của Bộ mã hóa, cụ thể là: 1) cơ học, 2) vật lý phân tử và nhiệt động lực học, 3) điện động lực học và 4) quang học. Bài tập điển hình bao gồm bốn phần khác nhau, bao gồm bài toán và các câu hỏi tiếp theo về lý thuyết. 4 giờ thiên văn (240 phút) được phân bổ để hoàn thành nhiệm vụ cho tất cả các lớp.

Lớp 7–9 1. Trong khi thực hiện bài tập vật lý trong phòng thí nghiệm, một học sinh đã sử dụng ba lò xo, độ cứng của hai trong số đó lần lượt là $равными_{1}^{k} 10$ N m $и_{2}^{k} 20$ N m, và độ cứng của lò xo thứ ba thì chưa biết. Theo gợi ý của giáo viên, học sinh nối cả ba lò xo nối tiếp và kéo căng lò xo tổng hợp thu được, tác dụng lên mỗi đầu tự do của nó một lực F 1 N (Hình 7). Bằng cách đo độ giãn dài tổng cộng' l co-
