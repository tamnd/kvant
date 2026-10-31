---
id: 1982-2-efros-chto-takoe-teoriya-protekaniya-5dc4b303
issue: kvant_1982_2
year: 1982
number: "2"
title: lý thuyết thẩm thấu là gì
authors:
  - Эфрос А.
rubric: osnovnye-stati
page_first: 4
page_last: 11
page_labels: 2, 3, 5, 7, 8, 9
tag: 28C3
lang: vi
source: kvant_digital
extraction: vision
content_sha256: 45cdaeb0fd1d65fb1fbb0b5afd0c3a5ba61b78c70f4b3ba16cf87150282ff920
prompt_sha256: draft-1
translated_from: content/ru/1982/02/articles/04_efros-chto-takoe-teoriya-protekaniya-5dc4b303.md
source_content_sha256: 7187af29e11e98fd5c52494da2e6edb5f9b257ebeb6cc4079254059e3da652bc
translation_model: draft
translation_run: vi-draft-2026-10-31
translation_quality: draft
---

⟦folio 2⟧

A. Efros

lý thuyết thẩm thấu là gì

Hai ông chồng nhà khoa học xé nát lưới màn hình

Không thường xuyên các báo cáo về thí nghiệm xuất hiện trên các tạp chí khoa học hiện đại, đối tượng của nó là một mảnh lưới màn hình thông thường*) được mua với mục đích hơi bất thường ở cửa hàng phần cứng gần nhất. Và mặc dù bài báo của các nhà vật lý người Mỹ Watson và Lees, đăng trên tạp chí Physical Review năm 1974, không phải là công trình đầu tiên trong lĩnh vực lý thuyết thẩm thấu, câu chuyện của chúng ta bắt đầu từ đó.

*) Mục đích trực tiếp của lưới màn hình là bảo vệ các thiết bị vô tuyến khác nhau khỏi nhiễu điện.

Mảnh lưới mà Watson và Lees làm việc có hình vuông và chứa $137 \times 137 = 18769$ nút có khoảng cách $1/4$ inch (6,35 mm) giữa các nút liền kề. Các nhà khoa học hàn các điện cực đồng vào hai cạnh đối diện của hình vuông và nối lưới điện với một mạch điện (Hình 1, a) để thay đổi độ dẫn điện của nó (hãy nhớ rằng độ dẫn điện là nghịch đảo của điện trở). Sau đó, họ bắt đầu cắt các nút từ lưới này (Hình 1, b) và nghiên cứu tính dẫn điện tùy thuộc vào tỷ lệ các nút bị cắt.

Mỗi nút mới bị cắt được chọn ngẫu nhiên trong số các nút chưa bị cắt trước đó. Về nguyên tắc, để làm được điều này, người ta có thể viết tọa độ của từng nút trên một tờ giấy riêng, cho tất cả các mảnh giấy vào một chiếc mũ, trộn đều và lấy ra từng mảnh một. Tuy nhiên, với số lượng lớn các nút, quy trình như vậy (giống như các phương pháp đúc lô cơ học khác) là vô cùng bất tiện, và do đó các nhà khoa học đã sử dụng một phương pháp ngẫu nhiên.

⟦folio 3⟧

một chuỗi tọa độ được biên soạn bởi máy tính.

Rõ ràng là khi số lượng nút cắt tăng lên thì độ dẫn điện của lưới giảm đi. Điều này là lớn, nếu tỷ lệ giữa số nút chưa cắt trên tổng số nút (137²) biểu thị $x$, thì ở một giá trị nhất định $x$, mà chúng ta sẽ gọi thêm là giá trị ngưỡng và biểu thị $x_c$, độ dẫn điện sẽ bằng 0. Điều này xảy ra khi đường dẫn cuối cùng kết nối các điện cực trái và phải bị cắt. Định nghĩa về vết cắt $x_c$ là một trong những thí nghiệm bài toán của Batson và Lees. Họ tìm thấy rằng $x_c = 0,59$.

Câu hỏi được đặt ra một cách tự nhiên: giá trị $x_c$ là ngẫu nhiên và không tự nguyện từ trải nghiệm này sang trải nghiệm khác hay nó hoàn toàn được xác định?

Có vẻ như bằng cách lặp lại thí nghiệm với một mảnh lưới màn hình khác và sử dụng một chuỗi nút cắt ngẫu nhiên khác, chúng ta sẽ thu được giá trị khác là $x_c$. đáp số này hỗ trợ lẽ thường: vì ở mỗi giai đoạn, toàn bộ cấu hình bị cắt bỏ

$$\bar{x}_c(N) = \frac{x_{c1} + x_{c2} + \ldots + x_{cQ}}{Q} = \frac{\sum_{i=1}^{Q} x_{ci}}{Q}.$$

Để xác định mức trung bình của các giá trị $x_{ci}$ thu được trong các thử nghiệm khác nhau khác với $\bar{x}_c(N)$ bao nhiêu, chúng tôi thực hiện như sau. Chúng ta hãy tìm tổng các biểu thức có dạng $(x_{ci} - \bar{x}_c(N))^2$ (tức là tổng bình phương độ lệch $x_{ci}$ từ $\bar{x}_c(N))$ và chia tổng này cho $Q$. Giá trị

$$\delta(N) = \frac{\sum_{i=1}^{Q} (x_{ci} - \bar{x}_c(N))^2}{Q}$$

biểu thị giá trị trung bình của độ lệch bình phương của $x_{ci}$ từ $\bar{x}_c(N)$ cho trước $N$. Đại lượng này được gọi là độ phân tán. Giá trị $\sqrt{\delta(N)}$ đặc trưng cho sự phân tán của các giá trị $x_{ci}$ thu được trong một loạt thử nghiệm với các lưới chứa các nút $N$. (Lưu ý rằng nếu chúng ta bắt đầu cộng không phải độ lệch bình phương mà là lũy thừa cao, tức là các biểu thức có dạng $x_{ci} - \bar{x}_c(N)$, thì đối với giá trị trung bình của độ lệch, chúng ta sẽ nhận được 0, vì $x_{ci} - \bar{x}_c(N)$ có cả giá trị dương và âm.)

Vì vậy, để đánh giá “mức độ ngẫu nhiên” của giá trị $x_c$, cần theo dõi hành vi của giá trị $\delta(N)$.

Tính toán cho thấy khi số lượng nút lưới tăng lên $N$ thì giá trị $\delta(N)$ tăng mạnh (theo định luật lũy thừa)

⟦folio 5⟧

tổng mô men từ $M = \mu N$ xuất hiện, trong đó $N$ là số lượng nguyên tử trong mẫu và $\mu$ là mô men từ của một nguyên tử. Điều quan trọng là mômen từ trên một đơn vị thể tích không phụ thuộc vào thể tích và bằng $M = \mu/v_0$, trong đó $v_0$ là thể tích trên mỗi nguyên tử. Giá trị $M$ được gọi là từ hóa tự phát (từ “tự phát” có nghĩa là “tự phát”, tức là phát sinh không phải dưới tác động của từ trường bên ngoài mà do chính nó phát sinh).

Chuyển động nhiệt phá hủy trật tự từ tính, và do đó có một nhiệt độ tới hạn, gọi là nhiệt độ Curie, mà trên đó độ từ hóa tự phát bằng không. Ví dụ, đối với sắt, nhiệt độ Curie là $770^\circ C$. Ở nhiệt độ cao hơn, sắt không thể có tính sắt từ.

Bây giờ chúng ta hãy xem xét một chất là dung dịch rắn (hỗn hợp các nguyên tử từ tính và không từ tính (không có mô men từ). Đây là một tinh thể trong các nút chứa các nguyên tử từ tính hoặc không từ tính, và sự sắp xếp của chúng hóa ra không có trật tự mà hoàn toàn ngẫu nhiên. Chúng ta hãy biểu thị $x$ liên quan đến nồng độ (phần) của các nguyên tử từ tính và tìm hiểu xem liệu tất cả các giá trị của $x$ có từ hóa tự phát hay không, tức là chất đó có tính sắt từ.

Chúng ta hãy giả sử rằng sự tương tác giữa các mô men từ của các nguyên tử giảm theo khoảng cách nhanh đến mức chỉ tính đến sự tương tác của các lân cận gần nhau. Điều này có nghĩa là nếu hai nguyên tử từ tính đứng cạnh nhau thì khoảnh khắc của chúng nhất thiết phải song song, nhưng nếu có ít nhất một nguyên tử không từ tính giữa chúng, thì khoảnh khắc có thể được định hướng tùy ý: chúng đã “không biết gì” về nhau.

Hãy để chúng tôi giới thiệu một số định nghĩa. Chúng ta sẽ gọi hai nguyên tử từ tính được kết nối với nhau nếu chúng đứng cạnh nhau hoặc nếu chúng được kết nối với nhau bằng một chuỗi nguyên tử từ tính nằm cạnh nhau (Hình 2, a). Một tập hợp các nguyên tử có liên quan thường được gọi là lớp

Cơm. 2. Nguyên tử có từ tính được biểu thị bằng vòng tròn màu đỏ, nguyên tử không có từ tính được biểu thị bằng vòng tròn màu xanh. Các đường đứt nét là ranh giới cụm.

(● từ tiếng Anh “cụm”, có nghĩa là “cụm”, “bàn chải”).

Bây giờ chúng ta giả sử rằng các nguyên tử từ tính rất nhỏ ($x \ll 1$). Đương nhiên, trong trường hợp này chúng chủ yếu nằm một mình. Lớp hai nguyên tử từ tính đã là hiếm, lớp ba nguyên tử lại càng hiếm hơn, v.v.

Nhờ tương tác từ, mômen từ của các liên kết của các nguyên tử này được định hướng theo một hướng. Do đó, mỗi lớp có mômen từ sinh ra tỉ lệ với số lượng nguyên tử trong cụm. Mặt khác, chúng tôi đồng ý rằng các nguyên tử từ tính không ở gần shikhmi sẽ không tương tác với nhau. Do đó, các nguyên tử thuộc các lớp khác nhau không tương tác với nhau. Kết quả là, mômen định hướng của các lớp hóa ra là tùy ý (xem Hình 2, a), sao cho mômen trung bình của tất cả các lớp bằng 0.

Vì vậy, chúng tôi đã phát hiện ra rằng ở nồng độ thấp của các nguyên tử từ tính thì không có hiện tượng từ hóa tự phát.

Bây giờ hãy xem xét trường hợp hầu hết các nguyên tử đều có từ tính. Rõ ràng, một lượng tạp chất nhỏ không loại bỏ được hiện tượng từ hóa tự phát mà chỉ làm giảm nhẹ nó. Hãy cùng thảo luận vấn đề này bằng ngôn ngữ của các lớp học. Đối với $x=1$ tất cả các nguyên tử $N$ thuộc cùng một cụm. Nếu $x$ xuất sắc một chút-

⟦folio 7⟧

Bài toán về độ dẫn điện tử được chúng tôi xây dựng cho lưới phẳng; tuy nhiên, rõ ràng là có thể dễ dàng thiết lập nó thành một khối lập phương, ở hai cạnh đối diện mà các electron được hàn. Trong bài toán về chất sắt từ, lý luận của chúng tôi áp dụng như nhau cho cả lưới điện và khối lập phương. Do đó, từ quan điểm của nồng độ tới hạn $x_c$ bài toán về độ dẫn điện tử của mạng và bài toán về tạp chất sắt từ là như nhau bài toán. Nó được gọi là vấn đề về nút.

Để kết thúc phần này, chúng tôi một lần nữa nhấn mạnh rằng các khái niệm cơ bản của lý thuyết thẩm thấu, chẳng hạn như ngưỡng thẩm thấu, cụm vô hạn, v.v., chỉ có được đặc tính rõ ràng khi được áp dụng cho một hệ thống lớn vô hạn. Trong bất kỳ hệ thống hữu hạn nào, ngưỡng thẩm thấu đều bị “mờ”; Khi lặp lại thí nghiệm, kết quả chỉ được sao chép với độ chính xác nhất định và bản thân định nghĩa về ngưỡng trở nên mơ hồ. Ví dụ: trong một thử nghiệm với lưới dẫn điện, chúng ta có thể gọi ngưỡng thấm là giá trị $x$ tại đó sự thẩm thấu xảy ra từ trên xuống dưới thay vì từ trái sang phải hoặc giá trị tối thiểu $x$ tại đó sự thẩm thấu xảy ra từ cả trên xuống dưới và từ trái sang phải. Trong một hệ thống đủ lớn, sự khác biệt giữa các định nghĩa này sẽ biến mất và ngưỡng thẩm thấu trở thành một giá trị được xác định rõ ràng.

Lưu ý rằng độ nhạy ngày càng tăng đối với quy mô của hệ thống là đặc tính chung của tất cả cái gọi là hiện tượng tới hạn. Do đó, nhiệt độ Curie tại đó tính sắt từ biến mất luôn bị “bôi nhọ” một chút trong hệ thống cuối cùng vì những lý do tương tự như ngưỡng thẩm thấu. Tuy nhiên, cần lưu ý rằng kích thước thực tế của hệ thống chỉ quan trọng nếu chúng ta đang cố gắng mô phỏng một cách giả tạo một hiện tượng quan trọng (ví dụ: sử dụng lưới màn hình). Một hệ thống vi xử lý thực tế luôn có thể được coi là vô hạn. Rốt cuộc, một khối vật chất chứa khoảng $10^{22}$ nguyên tử!

Lưới khác bài toán

Trong các phần trước, các nút mạng bài toán đã được xem xét. Bây giờ chúng tôi sẽ giải thích kết nối bài toán là gì. Hãy tưởng tượng rằng trong thử nghiệm với lưới màn hình, chúng ta sẽ không tăng gấp ba các nút mà sẽ cắt các dây (kết nối) kết nối các nút này (Hình 4). Hãy để chúng tôi biểu thị bằng $x$ phần dây chưa cắt. Sau đó, một lần nữa chúng ta có thể đặt ra câu hỏi về phần tới hạn $x_c$, tại đó dòng điện trong một lưới điện rất lớn có các điểm tiếp xúc kim loại ở hai bên vượt quá. bài toán này cũng có thể được hình thành bằng ngôn ngữ cụm, coi như các nút được kết nối với nhau nếu chúng được kết nối bằng một chuỗi dây chưa cắt.

nút Bài toán và liên kết bài toán có vẻ rất giống nhau. Tuy nhiên, họ không chỉ trẻ con. Những bài toán này cũng có thể được hình thành cho các mạng phức tạp hơn hình vuông và hình khối. Giả định rằng mỗi nút mạng có thể được kết nối với tất cả các nút lân cận gần nhất của nó. Số lượng lân cận gần nhất phụ thuộc vào loại mạng và do đó ngưỡng thấm thay đổi tùy theo mạng. Nhưng trên bất kỳ mạng nào, ngưỡng thấm của bài toán liên kết không nhiều hơn ngưỡng thấm của các nút bài toán.

Bài toán ràng buộc trên một mạng vuông đơn giản được giải quyết một cách chính xác; ngưỡng thẩm thấu $x_c = 1/2$ (nó nhỏ hơn giá trị ngưỡng $x_c = 0,59$ trong các nút bài toán trên cùng một mạng). Chính xác lời giải cũng tồn tại đối với một số mạng hai chiều (phẳng) khác. Đối với các mạng ba chiều (khối lượng), vẫn chưa tìm thấy một lời giải chính xác nào. Ba như vậy-

⟦folio 8⟧

Cơm. 5.

chiều bài toán được giải bằng các phương pháp gần đúng (như các phương pháp được mô tả ở phần đầu tiên) và mô phỏng trên máy tính.

Giá trị ngưỡng cho các loại cách tử khác nhau được đưa ra trong bảng. Các giá trị chính xác được gạch chân. Các kết quả còn lại thu được bằng phương pháp gần đúng. Đương nhiên, kết quả gần đúng thu được bằng các phương pháp khác nhau có phần khác nhau. Bảng thể hiện các kết quả phù hợp nhất theo quan điểm của tác giả.

Các ứng dụng khác nhau của lý thuyết thẩm thấu

Lý thuyết thẩm thấu là một môn toán học còn rất trẻ. Ý tưởng chính của nó được hình thành vào năm 1957 trong công trình của các nhà toán học người Anh Broadbent và Hammersley. Trong cùng một công việc, lý thuyết đã được thực hiện và đặt tên. (Trong tiếng Anh nó được gọi là “lý thuyết thẩm thấu”.
Bản dịch chính xác của “thẩm thấu” có nghĩa là “rò rỉ”, “lọc”; Trong văn học Nga, cùng với thuật ngữ "thẩm thấu", bạn có thể tìm thấy từ "thẩm thấu".

Mặc dù lý thuyết còn non trẻ nhưng phạm vi ứng dụng của nó rất rộng. Trong bài viết này, chúng tôi chỉ phân tích cái gọi là mạng bài toán, nhưng chúng không làm cạn kiệt toàn bộ trường và đóng một vai trò tương đối nhỏ trong các ứng dụng.

Để hình thành một lý thuyết bài toán khác về dòng chảy, chúng ta hãy nhớ lại truyền thuyết cổ xưa về Con tàu Neva. Truyền thuyết này kể rằng một số người cho rằng đã từng có một trận lũ lụt trên Trái đất. Chỉ một nhóm nhỏ những người đã đóng một con tàu lớn (ark) mới được cứu khỏi nó. Con tàu này dường như đang đi đâu đó trong vùng Caucasus, vì nơi đầu tiên nó cập bến khi nước bắt đầu rút là đỉnh núi Ararat... Bây giờ, hãy tưởng tượng rằng các du khách quyết định băng qua sườn núi Caucasus từ nam lên bắc bằng đường thủy. Cuộc hành trình này vẫn ở mức độ tối thiểu nào

⟦folio 9⟧

sẽ phát sinh? Nói cách khác, mực nước phải giảm đến mức nào để tuyến đường thủy băng qua dãy Kavkaz từ nam lên bắc biến mất? (Tất nhiên, khi bạn được phép di chuyển giữa các đỉnh nhô ra khỏi mặt nước.)

bài toán này (với điều kiện hệ thống núi có phạm vi đủ lớn theo mọi hướng) cũng là một vấn đề trong lý thuyết thẩm thấu, chỉ được hình thành không phải trên một mạng tinh thể mà trong không gian liên tục. Mực nước mong muốn được gọi là mực nước.

Ví dụ, bằng cách sử dụng khái niệm mức độ thẩm thấu, chúng tôi mô tả quá trình chuyển đổi điện môi-kim loại xảy ra trong chất bán dẫn có tạp chất khi nồng độ electron tăng lên. Thực tế là tạp chất trong chất bán dẫn nằm ở vị trí ngẫu nhiên và có thể tích điện. Kết quả là ở một số khu vực điện tích dương chiếm ưu thế, ở những khu vực khác điện tích âm chiếm ưu thế. Các electron được thêm vào hệ thống được thu thập trong các khu vực có điện tích dương, tạo thành một cái gì đó giống như hồ hoặc giọt ở đó. Những khu vực xuất hiện các giọt electron có độ dẫn điện cao. Tuy nhiên, nếu nồng độ electron trong hệ thống thấp thì những giọt này không được kết nối với nhau. Giữa là vùng có độ dẫn điện rất thấp nên độ dẫn điện của chất bán dẫn là không đáng kể. Tình hình thay đổi đáng kể khi nồng độ electron tăng lên đến mức các giọt electron nằm cạnh nhau hoặc kết nối với nhau hoặc kết nối thông qua các kênh electron hẹp. Ở những nồng độ tới hạn nhất định, có thể đi qua toàn bộ chất bán dẫn, chỉ ngạc nhiên ở khu vực chứa đầy electron. Sau đó độ dẫn điện trở lại mạnh mẽ. Hiện tượng này được gọi là sự chuyển tiếp điện môi-kim loại. Để xác định nồng độ tới hạn cần giải bài toán của lý thuyết dòng chảy, an-

hợp lý bài toán về đường thủy xuyên qua hệ thống núi.

Chúng ta có thể liệt kê các ứng dụng đa dạng nhất của lý thuyết dòng chảy: dòng chất lỏng chảy vào một vật thể xốp (mỗi lỗ rỗng có đường kính riêng và do tính mao dẫn của chất lỏng, nó chỉ đi qua ở một áp suất nhất định; bạn cần tìm áp suất tới hạn mà chất lỏng chảy một khoảng cách rất xa qua hệ thống các lỗ ngẫu nhiên), sự phá hủy đá (do tuổi tác hoặc ứng suất, hình thành các vết nứt vi mô, hợp nhất, tách đá), các mô hình khác nhau của quá trình chuyển đổi điện môi kim loại, sự ràng buộc của tính chất dị thường của nước siêu lạnh, v.v.

Bây giờ chúng ta hãy cố gắng hình thành điểm chung giữa tất cả những vấn đề này và trên thực tế, đâu là chủ đề của lý thuyết thẩm thấu. Điều này khá khó thực hiện. Tôi có thể nói rằng lý thuyết thẩm thấu đề cập đến khả năng kết nối của một số lượng phần tử rất lớn (vĩ mô), với điều kiện là kết nối của mỗi phần tử với các phần tử lân cận của nó là ngẫu nhiên, nhưng đạt được theo một cách nhất định (ví dụ: bằng cách tung đồng xu). Điều quan trọng là tập hợp các kết nối được phát triển bằng phương pháp này phải cố định và không thể thay đổi trong quá trình lời giải bài toán.

Cũng cần lưu ý rằng lý thuyết thẩm thấu không chỉ đề cập đến việc tìm các giá trị ngưỡng mà còn (ở mức độ lớn hơn nhiều) các quy luật xác định hành vi của các giá trị ngưỡng khác nhau. Nếu các giá trị ngưỡng là cụ thể cho từng bài toán, thì các định luật theo đó các hàm như $P(x)$ trong bài toán về một chất sắt từ ứng dụng hoặc độ dẫn điện trong bài toán về một lưới biến mất hóa ra lại phổ biến cho tất cả các lý thuyết thẩm thấu bài toán. Đây có lẽ là loạt câu hỏi thú vị nhất trong lý thuyết thẩm thấu, nhưng câu chuyện về nó sẽ còn dài và nằm ngoài phạm vi của bài viết này.
