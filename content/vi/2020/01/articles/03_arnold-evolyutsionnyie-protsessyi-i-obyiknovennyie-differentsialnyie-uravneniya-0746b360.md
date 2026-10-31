---
id: 2020-1-arnold-evolyutsionnyie-protsessyi-i-obyiknovennyie-differentsialnyie-uravneniya-0746b360
issue: kvant_2020_1
year: 2020
number: "1"
title: Quá trình tiến hóa và phương trình vi phân thông thường
authors:
  - Арнольд В. И.
rubric: osnovnye-stati
page_first: 31
page_last: 43
page_labels: 30, 41
tag: JIJ9
lang: vi
source: kvant_digital
extraction: native
content_sha256: 7b1b9ea9b8cc81d22e67aaffa65e63f20f4d1a3694785a33ced7b86a259cb47b
prompt_sha256: draft-1
translated_from: content/ru/2020/01/articles/03_arnold-evolyutsionnyie-protsessyi-i-obyiknovennyie-differentsialnyie-uravneniya-0746b360.md
source_content_sha256: 67cf87b65ede8212b0a7f56c54b66555a281c86feb63fd127b2b9e0be593b565
translation_model: draft
translation_run: vi-draft-2026-10-31
translation_quality: draft
---

⟦folio none⟧

Quá trình tiến hóa và phương trình vi phân thông thường

V. ARNOLD

Phương trình rất phức tạp, nhưng vị giáo sư, với tính khiêm tốn đặc trưng của mình, đã gọi nó là bình thường. Từ một cuộc phỏng vấn trên báo với một nhà toán học

PHƯƠNG TIỆN vi phân là một trong những công cụ chính của khoa học toán học. Chúng được phát minh bởi Isaac Newton (1642–1727). Bài toán, về cơ bản dẫn đến phương trình vi phân, xuất hiện trước Newton. Tuy nhiên, chỉ những thiên tài như Chủ tịch Viện Hàn lâm Khoa học Pháp X. Huygens (1629–1695) và thầy giáo, nhà toán học và thần học của Newton, nhà truyền giáo của vua Anh I. Barrow (1630–1677) mới có thể giải được chúng. Sau Newton, tất cả học sinh và thậm chí cả học sinh đều giải được chúng. Newton coi phát minh của mình quan trọng đến mức ông đã mã hóa nó dưới dạng $анаграммы^{1}$, ý nghĩa của nó trong thời hiện đại là

1 6accdael3eff7i3l9n4o4qrr4s9tl2vx. Giải thích: data aequatione quot cunque fluxiones định lượng invuolvente fluxiones invenire et ngược lại, tức là “đối với một phương trình đã cho chứa số lượng hàm bất kỳ, hãy tìm đạo hàm và ngược lại.” Đảo chữ này có trong “bức thư thứ hai” nổi tiếng của Newton gửi Oldenburg, thư ký của Hiệp hội Hoàng gia (Viện Hàn lâm Khoa học Anh), đề ngày 24 tháng 10 năm 1676. Bức thư này được gửi cho Leibniz (1646–1716) và chứa đựng một thông điệp về việc phát minh ra phép phân tích toán học. Newton đã tiến hành trao đổi thư từ với Leibniz, người sống ở Đức, thông qua Oldenburg (người sau này bị giam trong Tháp vì liên lạc với người nước ngoài).

Xuất bản năm «Kvant» số 2, 1986.

⟦column⟧

Về mặt thực tế, nó có thể được diễn đạt một cách lỏng lẻo như sau: việc giải các phương trình vi phân là “hữu ích” (vì chúng thể hiện các quy luật tự nhiên). Trong một phép đảo chữ dài hơn, Newton cũng mã hóa công thức do ông phát minh ra lời giải cho tất cả các phương trình, bao gồm cả phương trình vi phân. Lý thuyết về phương trình vi phân biến các câu hỏi khoa học tự nhiên thành các câu hỏi hình học bài toán về các đường cong được xác định bởi các trường vectơ (xem bên dưới), giống như phương pháp tọa độ Descartes biến các câu hỏi về phương trình đại số thành các câu hỏi bài toán về đường thẳng và bề mặt.

Trạng thái quá trình

Để nghiên cứu bất kỳ quy trình nào, trước hết bạn phải có khả năng mô tả nhiều trạng thái có thể có của quy trình này. Hãy xem cách thực hiện điều này bằng các ví dụ. 1. Chuyển động của một điểm trên một đường thẳng. Kinh nghiệm cho thấy để xác định chuyển động

Cơm. 1. Chuyển động theo đường thẳng

⟦folio 30⟧

KVANT 2020/№1

Để di chuyển một điểm vật chất dọc theo đường thẳng trong trường hợp không có ngoại lực, việc đặt tốc độ và vị trí của nó trên đường thẳng tại thời điểm ban đầu là đủ. Do đó, nhà toán học xác định tập hợp tất cả các trạng thái của nó bằng mặt phẳng tọa độ s; v: mỗi điểm trên mặt phẳng này tương ứng với một điểm vật chất chuyển động với tốc độ v và chiếm một vị trí có tọa độ s và ngược lại - mỗi trạng thái tương ứng với một điểm riêng của nó trên mặt phẳng (Hình 1). 2. Dao động của con lắc. Trạng thái của con lắc phẳng còn được mô tả bằng hai tham số, ví dụ góc lệch T so với phương thẳng đứng và vận tốc góc Z của con lắc (Hình 2). Vì vậy, nhiều

⟦figure⟧

Cơm. 2. Dao động của con lắc

Trạng thái nào của con lắc sẽ lại là một mặt phẳng? Không thực sự. Thực tế là khi góc T thay đổi 2S thì con lắc sẽ trở về vị trí cũ. Do đó, tập hợp các trạng thái ở đây là một bề mặt hình trụ (xem Hình 2). 3. Vị trí của xe trên hai con đường. Thành phố A đến B được nối với nhau bằng hai con đường không giao nhau, trên mỗi đường có một chiếc xe đẩy; chúng tôi quan tâm đến vị trí tương đối của họ. Vị trí của xe trên con đường đầu tiên (Hình 3) có thể được xác định bằng số -

Cơm. 3. Bài toán về hai chiếc xe chạy trên hai con đường

⟦column⟧

phần khoảng cách từ A đến B (dọc theo con đường thứ nhất) giữa A và xe; tương tự, tải trọng trên đường thứ hai cũng được xác định bằng tải trọng trên đường thứ hai. Do đó, tập hợp các trạng thái mà chúng ta quan tâm được mô tả bởi các điểm x; y đơn vị bình phương ( 0 d x d 1, 0 d y d 1 ). Tập hợp các trạng thái quá trình trong lý thuyết phương trình vi phân được gọi là không gian pha. Vì vậy, mỗi điểm của không gian pha (điểm pha) mô tả trạng thái của quá trình. Và bản thân dòng chảy của một quá trình cụ thể được mô tả bằng một đường thẳng trong không gian pha; những đường này được gọi là quỹ đạo pha. Việc đưa ra không gian pha của quá trình hình học hóa lý thuyết - các câu hỏi về diễn biến của quá trình chuyển thành câu hỏi về hành vi của quỹ đạo pha. Kết quả hình học bài toán có thể khó khăn. Tuy nhiên, điều cũng xảy ra là chỉ cần đưa vào không gian pha là có thể giải được bài toán khó bài toán. Bài toán (N.N. Konstantinov). Hai con đường không giao nhau dẫn từ thành phố A đến thành phố B. Được biết, hai ô tô đi dọc theo những con đường khác nhau từ A đến B và được nối với nhau bằng một sợi dây có chiều dài nhỏ hơn 2l đã có thể đi từ A đến B mà không bị đứt dây. Hai xe tròn chở cỏ khô có bán kính l, tâm của chúng chuyển động hướng về nhau dọc theo những con đường này, có thể đi qua mà không chạm vào nhau không? Không gian pha ở đây là bình phương đơn vị. Vị trí ban đầu của ô tô (ở thành phố A) tương ứng với góc dưới bên trái của hình vuông và chuyển động của ô tô từ A đến B được mô tả bằng một đường cong dẫn đến góc đối diện (xem Hình 3). Tương tự như vậy, vị trí ban đầu của xe tương ứng với góc dưới bên phải của hình vuông và chuyển động của xe được mô tả bằng một đường cong dẫn đến góc đối diện của hình vuông (phía trên bên trái). Nhưng hai đường cong bất kỳ trong một hình vuông nối các cặp đỉnh đối diện khác nhau sẽ cắt nhau. Vì vậy, cho dù xe di chuyển như thế nào thì sẽ đến lúc một cặp xe sẽ đảm nhận vị trí của cặp xe đó tại một thời điểm nào đó. Cái này

⟦folio 41⟧

NHÂN VIÊN VẤN ĐỀ

đồ thị của điện áp trên tải mà nguồn đóng so với điện trở tải. Hãy nối một điện trở có điện trở R với nguồn. Điện áp trên tải liên hệ với dòng điện theo tỷ lệ đơn giản: $U_{н} RI$. Trong cùng hình vẽ thể hiện sự phụ thuộc U I của điện áp nguồn vào dòng điện chạy qua nó, chúng ta sẽ vẽ một đường thẳng $U_{н} RI$. Giao điểm của đồ thị U I và đường thẳng $U_{н} RI$ sẽ cho ta dòng điện và điện áp cần tìm. Đối với nguồn thông thường, trong đó điện áp ở các cực càng thấp thì dòng điện càng cao thì không có vấn đề gì phát sinh nữa - chỉ có một điểm giao nhau và kết quả được xác định rõ ràng. Nhưng đối với một nguồn bất thường, trong đó ở một khu vực nhất định, điện áp tăng khi dòng điện tăng, có một phạm vi giá trị R trong đó có tới ba điểm giao nhau. Rõ ràng là dòng điện không thể có ba giá trị cùng một lúc; Điều này có nghĩa là khu vực này cần được xử lý riêng - một phương pháp đồ họa thuận tiện để tìm dòng điện trong mạch rõ ràng là không phù hợp ở đây. Trước tiên, chúng ta hãy nối một điện trở có điện trở rất cao với nguồn, sau đó giảm dần điện trở. Dòng điện ban đầu trong mạch sẽ rất nhỏ và khi điện trở giảm thì nó sẽ tăng lên. TRÊN

⟦figure⟧

Cơm. 2

Trong Hình 2, chế độ này tương ứng với phần ab, trong đó giá trị của U và I U thay đổi từ $U_{a} = 20$ V, $I_{a} = 0$ đến $U_{b} | 10$ V, $I_{b} | 120$ mA. Mỗi điểm của phần này tương ứng với một điểm ổn định

"QUANTA"

⟦column⟧

trạng thái (những thay đổi nhỏ về dòng điện trong mạch dẫn đến thay đổi điện áp, có xu hướng bù đắp cho những thay đổi của dòng điện; điều này là điển hình cho tất cả các mạch “bình thường”). Khi R giảm thêm, chế độ thay đổi đột ngột từ $U_{b}, I_{b}$ thành $U_{c} | 22$ V, $I_{c} | 260$ mA, sau đó lại chuyển sang chế độ “ổn định” (ở bên phải điểm c dọc theo đường cong UI). Nếu chúng ta bắt đầu với điện trở nhỏ, thì khi tăng R, chúng ta sẽ đạt đến điểm d (Hình 3), sau đó sẽ có một bước nhảy từ $U_{d} | 23$ V, $I_{d} | 210$ mA đến $U_{e} | 8$ V, $I_{e} | 80$ mA và một lần nữa dọc theo đường cong UI đến điểm a.

⟦figure⟧

Cơm. 3

Điều gì sẽ xảy ra nếu bạn lấy một điện trở có điện trở nằm trong vùng 80 Ohm < < R < 100 Ohm (giá trị R | 80 Ohm tương ứng với các điểm b và c trong Hình 2, giá trị R | 100 Ohm tương ứng với các điểm e và d trong Hình 3) và nối nó với nguồn? Điện áp và dòng điện trong mạch sẽ như thế nào? Để trả lời câu hỏi này, bạn cần biết các thông số mạch như độ tự cảm của dây dẫn và điện dung giữa các cực điện trở. Ví dụ, nếu độ tự cảm của dây dẫn lớn (dây dài) và điện dung giữa các dây nhỏ, thì tại thời điểm điện trở được nối với nguồn, dòng điện sẽ nhỏ (tác dụng của điện cảm), và sau đó nó sẽ tăng lên - chế độ trong mạch sẽ được thiết lập theo Hình 2. Nếu điện dung giữa các dây nối với nguồn lớn và độ tự cảm của dây nhỏ thì tại thời điểm đầu tiên, dòng điện sẽ lớn và sẽ trở thành
