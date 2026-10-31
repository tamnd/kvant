---
id: 2018-7-ptushenko-bazyikina-o-rastitelnyih-uzorah-i-horoshih-modelyah-afea7b0d
issue: kvant_2018_7
year: 2018
number: "7"
title: Về mô hình cây trồng và mô hình tốt
authors:
  - Птушенко В. В.
  - Базыкина А.
rubric: raznoe
rubric_sub: Разное
page_first: 37
page_last: 57
page_labels: 35, 36, 45, 46, 55
tag: 7GSW
lang: vi
source: kvant_digital
extraction: native
content_sha256: ebe0e04de75f3ccce2174ee65e58233ae54831426320b74ba9358e2a0f41107c
prompt_sha256: draft-1
translated_from: content/ru/2018/07/articles/06_ptushenko-bazyikina-o-rastitelnyih-uzorah-i-horoshih-modelyah-afea7b0d.md
source_content_sha256: d5de4d6dad612ebd9766f805a1b6153e8fa3c6beaa18f890ba2fa932ba9727e7
translation_model: draft
translation_run: vi-draft-2026-10-31
translation_quality: draft
---

⟦folio 35⟧

CỦA CHÚNG TÔI VÀ

N B L Y U D E N IA

Hoạt động tương tự để giảm số lượng cọc có thể được thực hiện thêm cho đến khi còn lại 3 cọc. Nếu số quân a, b và c trong chúng có liên hệ với nhau theo quan hệ c F a, b thì trạng thái ban đầu trong trò chơi Nim với m cọc phải gắn với dấu “-”, nếu không chúng ta gán dấu “+” cho trạng thái. Quy trình được mô tả trở nên cồng kềnh với số lượng cọc lớn. Ana-

⟦column⟧

Có thể, nhưng rất khó, để phân tích trạng thái của trò chơi và xác định nước đi đưa trò chơi vào trạng thái trừ bằng thuật toán được mô tả. Trong phần thứ hai của bài viết, chúng ta sẽ nghiên cứu hàm F kỹ hơn và có được chiến lược chơi Nim với số cọc tùy ý, thuận tiện khi sử dụng.

(Còn tiếp)

CỦA CHÚNG TÔI VÀ NA B L Y U D E N IYA

Về mô hình cây trồng và mô hình tốt

V. PTUSHENKO, A. BAZYKINA

TRÊN TRANG 4 CỦA BÌA SỐ THỨ TÁM «Kvant» năm ngoái có một bức ảnh chụp một họa tiết đơn giản được tạo thành bởi rêu dưới một chiếc ghế dài bằng gỗ. Trong văn bản kèm theo đã đề cập rằng lý do cho sự xuất hiện của nó có thể là do nhiều yếu tố khác nhau: sự sẵn có của ánh sáng, độ ẩm và ảnh hưởng của việc giẫm đạp. Tình huống “đồ chơi” này thực sự là một mô hình tốt cho bài toán sinh thái và địa sinh học lớn hơn và phức tạp hơn nhiều – bài toán về sự phân bố của các loài thực vật và động vật khác nhau trên khắp các vùng trên Trái đất. Đối với một số loài thực vật, khu vực phân bố của chúng bị giới hạn bởi lượng ẩm sẵn có dưới dạng mưa trong mùa sinh trưởng. Những loài khác đã thích nghi với điều kiện khô ráo thông qua hệ thống rễ sâu hoặc thời gian phát triển rất ngắn nhưng yêu cầu nhiệt độ cụ thể trong suốt cả năm. Vẫn còn những cây khác bị “gắn liền” với sự phân bố của các loài thụ phấn hoặc phát tán hạt giống của chúng (một ví dụ điển hình là cây dừa, mọc chủ yếu ở các vùng ven biển và có quả nổi tự do trên mặt nước và bị dòng hải lưu cuốn đi xa). Ngoài ra, sự cạnh tranh với các loài khác đóng một vai trò quan trọng: hãy nhớ làm thế nào thực vật từ “vùng ấm áp” phát triển tốt ở vĩ độ cao hơn trên bãi đất trống trong vườn thực vật, nơi loại trừ yếu tố cạnh tranh. Tuy nhiên, trong tất cả các trường hợp này, diện tích phân bố được xác định bởi tác động của một số yếu tố. Và không phải lúc nào cũng có thể chỉ ra yếu tố chính - cái gọi là yếu tố hạn chế. Chúng ta hãy xem lại ví dụ mà chúng ta đã bắt đầu: sự phát triển không đồng đều của rêu dưới băng ghế (Hình 1). Làm thế nào người ta có thể xác định được yếu tố hạn chế sự phát triển của rêu ở đây là gì: ánh sáng hay độ ẩm?

⟦figure⟧

Hình 1. Sự phân bố rêu dưới ghế gỗ có thể được xác định bởi tác động của nhiều yếu tố khác nhau. Ảnh của V. Ptushenko

⟦folio 36⟧

KVAN T 2018/№7

Có thể quan sát mảnh đất này trong mùa hè, đo một cách có hệ thống luồng ánh sáng đi vào các phần khác nhau của nó và xác định độ ẩm của đất. Sau đó, tính trung bình tất cả dữ liệu, lấy “bản đồ” phân bố ánh sáng và độ ẩm rồi so sánh chúng với “bản đồ” sự phát triển của rêu. Đây sẽ là một nghiên cứu quan sát - thận trọng nhất, tức là ảnh hưởng tối thiểu đến hệ thống đang được nghiên cứu, nhưng đồng thời tốn nhiều công sức và không phải lúc nào cũng cho phép giải thích rõ ràng. Bạn có thể thực hiện một nghiên cứu thử nghiệm: đặt đèn chiếu sáng gần băng ghế để tạo ra ánh sáng đồng đều cho toàn bộ không gian bên dưới nó vào ban ngày, nhưng không ngăn nước xâm nhập vào mặt đất qua các vết nứt giữa các tấm ván khi trời mưa. Hoặc ngược lại, làm ẩm đều đất dưới ghế, không làm thay đổi điều kiện ánh sáng và bóng tối, đồng thời quan sát xem hoa văn do rêu tạo thành thay đổi như thế nào. Nhưng ngay cả sau khi thực hiện cẩn thận những nghiên cứu như vậy, bạn có thể không nhận được đáp số rõ ràng. Ví dụ, hãy tưởng tượng rằng một phạm vi độ ẩm nhất định của đất là nền tảng cho sự phát triển của thảm thực vật. Hơn nữa, độ ẩm này được xác định không phải bởi sự xâm nhập của hơi ẩm dưới băng ghế qua các vết nứt trên đó khi mưa, mà bởi sự xâm nhập của ánh sáng mặt trời qua các vết nứt tương tự, làm khô đất (và trong bóng râm, đất vẫn ẩm hơn). Và khi đó sự phân bố độ ẩm dưới băng ghế sẽ được xác định... bởi mô hình ánh sáng và bóng tối! Những vấn đề tương tự xảy ra khá thường xuyên trong nghiên cứu thực tế. Chúng không nhất thiết khiến bài toán không thể quyết định được, nhưng chúng có thể khiến lời giải trở nên rất khó khăn. Và do đó, những mô hình thử nghiệm cho phép bạn nhìn thấy lời giải rõ ràng, rõ ràng luôn đặc biệt có giá trị. Bức ảnh được trình bày ở đây trong Hình 2 và trên trang 4 của trang bìa số tạp chí này cung cấp một ví dụ về một mô hình thành công như vậy của một cộng đồng thực vật trong nhiều điều kiện phát triển đang thay đổi. Những bậc thang của bờ kè Venice dẫn xuống mặt nước được bao phủ bởi một “tấm thảm” xanh dày đặc. Rõ ràng là việc chiếu sáng ở tất cả các bậc thang gần như

⟦column⟧

⟦figure⟧

Hình 2. Những bậc thang đi xuống mặt nước và phủ đầy thảm tảo dày đặc không chỉ là một bức tranh đẹp mà còn là một hình mẫu đẹp. Ảnh của A. Bazykina

là như nhau, nhưng lượng hơi ẩm rơi vào nó thay đổi theo từng bước: những phần thấp hơn thường xuyên bị sóng cuốn trôi và chỉ những tia nước bắn tung tóe mới có thể chạm tới những phần cao hơn. Bức ảnh cho thấy rõ mật độ thực vật giảm dần khi bạn di chuyển lên các bậc thang. Nếu muốn, bạn thậm chí có thể xác định độ ẩm tối ưu cho sự phát triển. Đúng vậy, ở đây người ta cũng có thể nghi ngờ tác động của nhiều yếu tố khác nhau - ví dụ (cùng với độ ẩm), tác động của sóng cuốn trôi tảo khỏi các bậc thang. Do đó, bức tranh mà chúng ta quan sát vẫn có phần phức tạp hơn so với cái nhìn đầu tiên và được xác định không phải bởi một mà ít nhất là hai yếu tố. Tuy nhiên, mỗi yếu tố đều có “khu vực trách nhiệm” riêng: một trong số đó (độ ẩm) xác định giới hạn phân bố trên và yếu tố thứ hai (bất ổn) xác định giới hạn dưới. Giống như trong địa sinh học thực sự! Đúng là một mô hình tốt. Tuy nhiên, để diễn giải câu nói nổi tiếng về một lý thuyết đúng đắn và đẹp đẽ, chúng ta có thể nói rằng một người mẫu tốt thì luôn đẹp! Và nhìn vào các bậc thang của bờ kè Venice, thật khó để không đồng ý với điều này.

⟦folio 45⟧

THÔNG TIN

Pha loãng đến nhiệt độ âm, lấy ra khỏi tủ lạnh và quan sát quá trình gia nhiệt của nó, định kỳ thêm các phần bằng nhau của chất pha rắn nằm ở điểm nóng chảy $T_{п} 110 q C$. Đồ thị nhiệt độ thay đổi theo thời gian và các giá trị đặc trưng của chúng được thể hiện trên Hình 1. Xác định nhiệt dung riêng của phản ứng nóng chảy của chất, coi hằng số công suất nhiệt và bỏ qua nhiệt dung của bình.

⟦column⟧

pin không bị ảnh hưởng bởi dòng điện. 5. Một tải trọng m = 5000 kg treo trên móc của cần trục tháp (Hình 3). Cần cẩu được trang bị hai dây cáp: một dây được ném qua một khối ở cuối cần và dùng để nâng tải, dây thứ hai - Hình 3 được gắn vào trục của khối này và giữ cần trục gắn bản lề với tháp ở vị trí nghiêng một góc 30° so với phương ngang. Xác định lực căng của sợi cáp giữ cần, với điều kiện nó được kéo căng theo phương ngang. Bỏ qua khối lượng của mũi tên.

lớp 10

⟦figure⟧

Hình 1

3. Có nước đựng trong một bình hình trụ. Khi thả một khối nhựa vào bình thì mực nước dâng lên h = 1 cm. Mức này sẽ thay đổi như thế nào nếu đổ dầu hỏa lên trên? Mật độ nước $U_{0}$, khối lập phương $U 0,9 U_{0}$, dầu hỏa $U_{1} 0,8 U_{0}$, lớp dầu hỏa phía trên khối. 4. Học sinh lắp ráp một mạch điện gồm ba điện trở, một ampe kế và một cục pin có hiệu điện thế 10 V (Hình 2), quên mất phần sơ bộ

⟦figure⟧

Hình 2

Đo cẩn thận điện trở của điện trở. Người thứ hai không thực sự làm anh ta bối rối: đã ghi lại số chỉ của ampe kế $I_{1} = 12,5$ mA ở trạng thái ban đầu và nhận được số chỉ tương tự của ampe kế $I_{2} = 15$ mA với các điểm A và B hoặc B và C lần lượt đóng bằng dây (A và B đang mở), anh ta nhanh chóng giải quyết vấn đề. Xác định điện trở của các điện trở. Điện áp đầu cuối

1. Giải bài toán 1 cho lớp 9. 2. Người sinh viên này đã hàn mạch điện như hình 4. Trong lúc vội vàng, anh ta quên kiểm tra điện trở của các điện trở. Để sửa lỗi, ông đo điện trở trong mạch đã lắp ráp. Hóa ra điện trở giữa điểm A và B bằng R AB = 0,8 kOhm, giữa B và C, còn $так-_{Рис.} 4$ A và C thì bằng R BC R AC 1,2 kOhm. Xác định điện trở của các điện trở. 3. Chuyến bay tên lửa diễn ra trong tình trạng khẩn cấp. Người ta cho rằng sau khi phóng, động cơ của nó sẽ hoạt động trong W = 100 s và tắt ở độ cao H = 60 km, nhưng sau một thời gian W 2 tên lửa mất định hướng trong không gian nên động cơ bắt đầu hoạt động để phanh. Tên lửa đã ở độ cao bao nhiêu khi động cơ hoạt động trong thời gian yêu cầu W rồi tắt? Bỏ qua sự thay đổi khối lượng của tên lửa, lực đẩy của động cơ không đổi, gia tốc trọng trường g 10 m $с^{2}. 4.$ Thuyền đi trên quãng đường từ điểm A đến điểm B, nằm ở phía đối diện

⟦folio 46⟧

KV AN T 2018/№7

trên bờ sông giả đối diện chính xác với điểm A, thời gian $t_{1}$ nếu bơi theo đường thẳng và thời gian $t_{2}$ nếu lần đầu tiên di chuyển, giữ cơ thể chính xác qua sông, sau đó đi ngược dòng chảy dọc theo bờ. Xác định vận tốc của thuyền khi nước yên lặng và vận tốc của dòng sông nếu chiều rộng của sông là h = 1 km. 5. Ống trượt không ma sát dọc theo nan ngang (Hình 5). Ở hai đầu ống

⟦figure⟧

Hình 5

sợi chỉ treo chiếc nhẫn đã được cố định. Khối lượng của vòng và ống bằng nhau và bằng m. Với một lực nào đó, ống được kéo sang phải sao cho vòng nằm chính xác dưới đầu bên trái của nó và góc của sợi chỉ ở đầu bên phải của nó là 30 q. Hãy tìm sức mạnh đó.

lớp 11

1. Hai khối giống hệt nhau có khối lượng m nằm trên một mặt phẳng nằm ngang. Một khối được gắn vào khối bên trái và một sợi dây ném qua khối này được gắn vào khối bên phải (Hình 6). Đầu sợi A được kéo

⟦figure⟧

Hình 6

về bên phải với một lực F. Xác định gia tốc của đầu sợi dây. Không có ma sát, sợi chỉ không thể giãn ra được. 2. Cậu bé quyết định thực hiện cú nhảy bungee ngoạn mục trên mặt sông. Anh ta buộc một sợi dây bungee (một sợi dây buộc vào cành cây, đầu bằng một thanh ngang bằng gỗ mà bạn phải dùng tay giữ chặt) vào một cành cây treo lơ lửng giữa sông. Anh ta đã làm điều này theo cách mà có thể, giữ sợi dây theo chiều ngang, nhảy từ bờ sông dốc cao 6 m, bay, chạm nhẹ vào mặt nước và dừng lại ở bờ bên kia. Cậu bé đã rơi xuống nước từ độ cao bao nhiêu để cậu có thể dùng tay đỡ trọng lượng của mình? Chiều rộng của sông là 12 m.

⟦column⟧

bỏ qua vận tốc nhảy ban đầu và độ cao của cậu bé. 3. Một bình kín được chia bằng vách ngăn kín thành hai ngăn, mỗi ngăn có chiều cao H, ngăn trên chứa một phần nước, ngăn dưới trống (Hình 7). Các ngăn được nối với nhau bằng một ống mỏng với một van. Hỏi nếu mở van thì mực nước ở ngăn trên sẽ chảy hết xuống ngăn dưới là bao nhiêu? Bè- Hình 7 hàm lượng nước U, thể tích tự do chứa đầy không khí ở áp suất khí quyển $p_{0}. 4.$ Công suất giải phóng trong mạch ở Hình 8 thay đổi bao nhiêu lần nếu điốt Hình 8? Mạch được tạo thành từ sáu điện trở giống hệt nhau và một nguồn điện áp xoay chiều. Điốt là một thiết bị là chất dẫn lý tưởng cho dòng điện theo hướng mũi tên và là chất cách điện cho dòng điện theo hướng ngược lại. 5. Một khẩu pháo lò xo bắn những quả bóng theo một góc 45° so với phương ngang. Quả bóng rơi cách khẩu pháo một khoảng L. Nó sẽ bay được khoảng cách bao nhiêu nếu một quả bóng khác được bắn theo phương thẳng đứng từ cùng một khẩu pháo ngay phía dưới đỉnh quỹ đạo của nó và các quả bóng va chạm đàn hồi trên cùng một trục thẳng đứng (Hình 9)? Việc bắn được thực hiện từ một bề mặt nằm ngang, bỏ qua ma sát và lực cản của không khí.

Hình 9

⟦folio 55⟧

ĐÁP ÁN,

HƯỚNG DẪN

khối lượng của nó thì quỹ đạo Trái đất cũng như chu kỳ quỹ đạo của nó đều không thay đổi. 5. Sẽ giữ nguyên, vì chu kỳ quỹ đạo của một vật thể không phụ thuộc vào khối lượng của nó (nếu khối lượng của vệ tinh nhỏ hơn nhiều so với khối lượng của vật thể trung tâm, trong trường hợp này là Trái đất). 6. Chu kỳ Mặt trăng quay quanh Trái đất so với các ngôi sao, gọi là thiên văn, là 27,3 ngày. Chu kỳ quay của Mặt trăng quanh Trái đất so với Mặt trời, bằng khoảng thời gian giữa hai pha giống hệt nhau liên tiếp của Mặt trăng và được gọi là giao hội, là 29,53 ngày. Đáp số đến bài toán 5 đề cập đến cả hai giai đoạn. 7. Quỹ đạo của Mặt trăng gần như nằm trong mặt phẳng hoàng đạo nên đường đi nhìn thấy được của Mặt trăng trên bầu trời gần như trùng với quỹ đạo của Mặt trời, tuy nhiên, nó hoàn thành vòng quay của mình không phải trong một năm mà trong một tháng âm lịch - 27,3 ngày. Do đó, từ cực địa lý của Trái đất, nó sẽ hiển thị phía trên đường chân trời trong 2 tuần và ẩn bên dưới nó trong 2 tuần. 8. Nhật thực sẽ xảy ra thường xuyên hơn - hàng tháng. 9. Dựa trên các phép đo kích thước góc của Mặt trời trong năm, cũng như các phép đo vận tốc góc của Mặt trời so với các ngôi sao. 10. Khối tâm của hệ Trái đất-Mặt trăng chuyển động theo quỹ đạo hình elip. Quỹ đạo Trái Đất gần giống hình elip nhưng bị biến dạng do tác động của Mặt Trăng. 11. Trái đất vào thời điểm này không thể tiếp cận được để quan sát, ngoại trừ khả năng rất hiếm là Trái đất đi ngang qua đĩa Mặt trời, nhưng ngay cả khi đó cũng chỉ nhìn thấy được hình bóng của nó. 12. Có thể, nếu cuộc cách mạng hàng ngày của hành tinh và cuộc cách mạng của nó quanh Mặt trời xảy ra theo cùng một hướng và với những khoảng thời gian gần nhau. Ví dụ: trên Sao Thủy, trong đó độ dài của chu kỳ hàng ngày (tức là ngày thiên văn) bằng 2/3 chu kỳ quỹ đạo (tức là năm), một ngày mặt trời kéo dài 2 năm Sao Thủy và một ngày ban ngày kéo dài 1 năm. Nếu chu kỳ ngày và chu kỳ quỹ đạo trùng nhau thì chu kỳ ngày và đêm sẽ hoàn toàn dừng lại. 13. Khi các vành đai của Sao Thổ nằm sát Mặt trời, bề mặt của chúng không được chiếu sáng và các vành đai trở nên vô hình. Điều tương tự cũng xảy ra khi họ trở nên khó gần với người quan sát trên trái đất. 14. Tiểu hành tinh Icarus ở điểm cận nhật tiến gần Mặt trời hơn Sao Thủy. Khoảng cách trung bình của nó với Mặt trời là 0,387 đơn vị thiên văn, trong khi khoảng cách của Icarus là 0,19 AU. 15. Lực hấp dẫn từ các hành tinh làm biến dạng quỹ đạo hình elip ban đầu của sao chổi. Những thay đổi về quỹ đạo này tích lũy từ vòng quay này sang vòng quay khác xung quanh Mặt trời.

GIẢI PHÁP

KINH NGHIỆM VI MÔ

⟦column⟧

Một hành tinh sáng có thể nhanh chóng được phân biệt với một ngôi sao sáng do nó không nhấp nháy. Đĩa nhìn thấy được của ngôi sao nhỏ hơn các vòng xoáy bất thường trong bầu khí quyển Trái đất. Kích thước góc của các đĩa hành tinh đủ lớn để loại trừ hiện tượng nhấp nháy.

TỔ HỢP VUÔNG

9. Áp dụng câu lệnh bài toán 6. 10. Áp dụng câu lệnh bài toán 6 một lần nữa. 11. Áp dụng câu bài toán 4 cho các ô vuông màu xanh (Hình 5).

⟦figure⟧

Hình 5

12. Áp dụng câu lệnh bài toán 4 cho các ô vuông màu xanh lam (Hình 6).

⟦figure⟧

Hình 6

13. Áp dụng câu lệnh bài toán 4 cho một cặp hình vuông và cho cặp hình vuông kia, chúng ta thu được hai tam giác vuông cân có cạnh huyền chung (Hình 7).

⟦figure⟧

Hình 7

14. Hãy xem xét các hình vuông màu xanh lá cây có các đỉnh ở tâm của các hình vuông này (Hình 8).
