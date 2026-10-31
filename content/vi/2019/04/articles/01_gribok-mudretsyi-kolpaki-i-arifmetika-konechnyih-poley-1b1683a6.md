---
id: 2019-4-gribok-mudretsyi-kolpaki-i-arifmetika-konechnyih-poley-1b1683a6
issue: kvant_2019_4
year: 2019
number: "4"
title: Hiền nhân, mũ và số học của các trường hữu hạn
authors:
  - Грибок С. В.
rubric: osnovnye-stati
page_first: 7
page_last: 9
page_labels: 6-7
tag: D2QW
lang: vi
source: kvant_digital
extraction: native
content_sha256: 60f6c33a07aff487d34206c1d6fd3c458377a168976c2ce9359bd8b96bb99875
prompt_sha256: draft-1
translated_from: content/ru/2019/04/articles/01_gribok-mudretsyi-kolpaki-i-arifmetika-konechnyih-poley-1b1683a6.md
source_content_sha256: fc085d37a9c4d2b3038343c4ee03fafcfd73b9fdf1fd7959ef9e92f95ff49f1e
translation_model: draft
translation_run: vi-draft-2026-10-31
translation_quality: draft
---

⟦folio none⟧

Hiền nhân, mũ và số học của các trường hữu hạn

S.GRIBOK

Kiểm tra 1. Hai trên ba. Giới thiệu về bộ nhị phân, hình khối và quả bóng

Ngày xửa ngày xưa, vua Shahryar trị vì ở Ba Tư. Suốt ngày nhà vua tiệc tùng, săn bắn và vui chơi, sắp xếp những cuộc xét xử tàn khốc cho các cận thần của mình. Trong khi nhà vua dành thời gian nhàn rỗi thì hội đồng các nhà hiền triết trong triều đình đã tham gia giải quyết mọi công việc phức tạp của nhà nước và cai trị đất nước. Một ngày nọ, nhà vua quyết định kiểm tra xem các nhà hiền triết trong triều đình của ông có thực sự thông minh đến vậy hay không. Ông ra lệnh triệu tập ba nhà thông thái và thông báo các điều kiện của bài kiểm tra đang chờ đợi họ vào ngày mai. Mỗi hiền nhân sẽ đội một chiếc mũ màu trắng hoặc đen trên đầu. Mọi người sẽ có thể nhìn thấy mũ của người khác, nhưng sẽ không biết mũ của họ màu gì. Người hành quyết sẽ quyết định đội chiếc mũ nào cho mỗi cây xô thơm bằng cách tung đồng xu ba lần, một mặt màu trắng và mặt còn lại màu đen. Sau đó, mỗi nhà thông thái sẽ được phát một chiếc bút lông và một mảnh giấy da để viết mũ của mình màu gì. Nếu ít nhất hai nhà thông thái trả lời đúng thì mọi người sẽ được khen thưởng, nhưng nếu có ít nhất hai nhà thông thái trả lời đúng thì tất cả các nhà thông thái sẽ bị xử tử. Nghiêm cấm đưa ra bất kỳ dấu hiệu nào cho nhau trong quá trình kiểm tra. Đêm trước cuộc thi, các nhà thông thái có cơ hội đi đến thống nhất và phát triển một chiến lược thống nhất. Những người khôn ngoan nên hành động như thế nào để tối đa hóa cơ hội sống sót của họ? Hãy để chúng tôi chứng minh rằng không có cách nào làm cho xác suất chiến thắng của các nhà thông thái lớn hơn 3 4.

DOI: https://doi.org/10.4213/kvant20190402

⟦column⟧

Hãy để thử nghiệm được lặp lại nhiều lần. Hãy để các nhà hiền triết phát triển một phương pháp cho phép trung bình hai trong số ba nhà hiền triết đoán màu mũ của họ thường xuyên hơn so với ba trong số bốn trò chơi. Như vậy, trong số 12 nhà hiền triết đáp số được nói trong bốn trò chơi, trung bình có hơn 6 đáp số sẽ đúng (6 3 2). Nhưng điều này là không thể, vì mọi nhà thông thái đều đoán màu mũ của mình trong một trong hai trường hợp, điều đó có nghĩa là trung bình trong số 12 đáp số có ​​chính xác 6 đáp số là đúng. Tổng cộng có 8 lựa chọn khác nhau để phân bổ giới hạn giữa ba nhà hiền triết. Xác suất thắng 3 4 có nghĩa là nhà thông thái thắng trong sáu phương án và thua hai trong tám phương án. Chúng ta hãy cố gắng xây dựng một chiến lược cho những nhà thông thái để họ có thể giành chiến thắng trong sáu trên tám trường hợp. Để thuận tiện cho việc ghi các bộ mũ, chúng ta sẽ dùng số 0 để biểu thị mũ trắng và số 1 để biểu thị mũ đen. Ví dụ: mục 001 có nghĩa là hai nhà thông thái đầu tiên nhận được mũ trắng và nhà thông thái thứ ba nhận được mũ đen. Hãy chọn ra hai bộ mũ “chết người” mà các nhà thông thái sẽ không thể đoán được. Ví dụ: giả sử các bộ chết người là 000 và 111. Chúng tôi muốn các nhà hiền triết có thể thắng tất cả các bộ khác. Làm thế nào để đạt được điều này? Trước hết, hãy lưu ý rằng đối với bất kỳ bộ mũ không gây chết người nào, một trong những nhà thông thái sẽ thấy rằng những người hàng xóm có mũ cùng màu. Chiến lược của nhà hiền triết này rất rõ ràng: nếu bạn nhìn thấy hai chiếc mũ cùng màu ở hàng xóm của mình, hãy gọi màu kia. Ối-

⟦folio 6⟧

KVANT 2019/№4

Rõ ràng, đối với bất kỳ bộ không gây chết người nào, chiến lược này có hiệu quả và được đảm bảo cho phép nhà hiền triết đoán màu mũ của mình. Hãy giải quyết hai nhà thông thái còn lại, mỗi người nhìn thấy những chiếc mũ có màu sắc khác nhau trên người hàng xóm của mình. Để giành chiến thắng, chỉ cần ít nhất một trong số những nhà thông thái này gọi đúng màu mũ của mình là đủ. Cũng lưu ý rằng mũ của họ có cùng màu. Điều này có nghĩa là nếu một trong hai nhà thông thái gọi tên người da trắng và người kia là người da đen thì người đó chắc chắn sẽ đoán đúng. Nhưng làm sao những nhà thông thái biết gọi màu gì nếu cả hai cùng nhìn thấy một bức tranh - những người hàng xóm của họ đội những chiếc mũ có màu sắc khác nhau? Vấn đề là nếu nhìn kỹ, chúng ta sẽ nhận thấy có một số khác biệt trong những gì hai nhà thông thái này nhìn thấy. Ví dụ, để các nhà thông thái đứng thành vòng tròn. Sau đó, một trong hai nhà thông thái nhìn thấy chiếc mũ màu trắng ở bên trái và chiếc mũ màu đen ở bên phải. Một nhà hiền triết khác nhìn thấy một bức tranh khác: bên trái là mũ đen, bên phải là màu trắng. Bây giờ, thật dễ dàng để đưa ra một quy tắc cho phép một trong những nhà thông thái này đoán màu mũ của anh ta: nếu bạn thấy những chiếc mũ có màu khác nhau ở hàng xóm của mình, hãy đặt tên cho màu mà bạn nhìn thấy ở bên phải (lưu ý rằng quy tắc "đối xứng gương" cũng có tác dụng: nếu bạn nhìn thấy những chiếc mũ có màu khác nhau ở hàng xóm của mình, hãy đặt tên cho màu mà bạn nhìn thấy ở bên trái). Vì vậy, bài toán đã được giải quyết, nhưng chúng ta đừng vội vàng. Đầu tiên, chúng ta hãy xem xét liệu có thể đơn giản hóa các quy tắc mà người khôn ngoan phải tuân theo hay không. Không khó để đoán rằng hai quy tắc chúng tôi tìm thấy có thể được phát biểu lại thành một quy tắc đơn giản: đặt tên KHÔNG phải màu mà bạn nhìn thấy ở hàng xóm bên trái. Thứ hai, chúng ta hãy xây dựng cách giải thích hình học của bài toán về ba chữ mũ. Thật thuận tiện khi hình dung ra nhiều lựa chọn để phân phối mũ ở dạng khối lập phương (Hình 1). Mỗi bộ mũ tương ứng với một trong các đỉnh của khối lập phương. Nếu hai bộ nắp chỉ khác nhau về màu sắc của một nắp (các bộ như vậy gọi là

⟦column⟧

⟦figure⟧

Cơm. 1

lân cận), chúng nằm ở các đỉnh được nối với nhau bằng một cạnh. Bây giờ chúng ta hãy hoàn thành hai quả bóng, tâm của chúng nằm ở điểm chết 000 và 111, và bán kính bằng cạnh của khối lập phương. Mỗi quả bóng bao gồm bốn điểm của khối lập phương. Mỗi điểm của khối lập phương đều nằm trên bề mặt hoặc ở tâm của một trong các quả bóng. Trong những trường hợp như vậy, họ nói rằng một “lớp phủ hình lập phương bằng những quả bóng không giao nhau” đã được xây dựng. Nếu điểm nằm ở tâm quả bóng, các hiền nhân sẽ không đoán được màu mũ của mình, nhưng nếu điểm nằm trên bề mặt quả bóng thì hầu hết các hiền nhân sẽ gọi tên chính xác màu sắc của chúng.

Kiểm tra 2. Bốn trên bảy. Về đa thức và bộ mã

Ngày hôm sau, bảy nhà thông thái được đưa đến gặp nhà vua. Người cai trị thông báo rằng một cuộc kiểm tra khác sẽ diễn ra vào ngày hôm nay. Luật chơi vẫn giống như ngày hôm qua: mỗi hiền nhân sẽ đội một chiếc mũ màu trắng hoặc đen trên đầu, sau đó mỗi hiền nhân phải viết ra màu sắc mà mình nghĩ là chiếc mũ đó sẽ đội trên đầu. Nếu ít nhất bốn nhà thông thái trả lời đúng thì mọi người sẽ được khen thưởng, nhưng nếu ít nhất bốn người trả lời sai thì mọi người sẽ bị xử tử. Các nhà thông thái nên hành động như thế nào để giảm thiểu khả năng bị hành quyết lần này? Hãy bắt đầu lại với ước tính thấp hơn về xác suất thực hiện. Hãy chứng minh rằng nó không tồn tại

⟦folio 7⟧

SAGES,

CAPS

VÀ

số học

một phương pháp cho phép bạn làm cho xác suất thắng lớn hơn 7 8. Cách chứng minh cũng giống như trong bài toán đầu tiên, cho đến việc thay thế các số. Hãy để các nhà hiền triết phát triển một phương pháp cho phép trung bình bốn trong số bảy nhà hiền triết đoán màu mũ của họ thường xuyên hơn bảy trong số tám trò chơi. Do đó, trong số 56 nhà hiền triết đáp số được nói trong suốt tám trò chơi, trung bình có hơn 28 đáp số sẽ đúng (28 7 4). Nhưng điều này là không thể, vì mọi nhà thông thái đều đoán màu mũ của mình trong một trong hai trường hợp, điều đó có nghĩa là trung bình trong số 56 đáp số có chính xác 28 đáp số là đúng. Có tổng cộng 128 lựa chọn khác nhau để phân bổ giới hạn cho bảy nhà hiền triết. Xác suất thắng 7/8 có nghĩa là nhà thông thái thắng trong 112 phương án và thua 16 phương án trong số 128 phương án. Tương tự với nhiệm vụ đầu tiên, bây giờ chúng ta cần bằng cách nào đó chọn ra 16 bộ chết người. Nhưng làm thế nào để làm điều này? Trong bài toán trước, chúng tôi đã đặt tất cả bộ ba mũ ở các đỉnh của khối lập phương. Bây giờ có bảy mũ, có nghĩa là nhiều bộ tương ứng với các đỉnh của siêu khối bảy chiều. Thật khó để tưởng tượng con số này, nhưng điều này không ngăn cản chúng ta suy đoán về các đặc tính của nó. Lưu ý rằng vì có bảy nhà thông thái nên mỗi bộ mũ có bảy bộ lân cận, do đó, mỗi quả bóng 7 chiều có bán kính đơn vị có tâm tại đỉnh của khối lập phương N chiều bao phủ chính xác 8 điểm của khối lập phương. Vì 128 16 8, nên về mặt lý thuyết, để bao phủ tất cả 128 đỉnh của một khối lập phương 7 chiều, cần có đủ mười sáu quả bóng 7 chiều rời nhau, ở giữa mỗi quả bóng đó chúng ta sẽ đặt một bộ chết người. Nhưng làm thế nào để làm điều này trong thực tế? Chúng ta sẽ gọi khoảng cách giữa hai tập hợp là số vị trí mà các tập hợp này khác nhau. Khoảng cách giữa các tập liền kề bằng một. Bây giờ chúng ta hãy xây dựng các tính chất của tập hợp các tập hợp chết người mà chúng ta muốn xây dựng.

CUỐI CÙNG

TRƯỜNG

⟦column⟧

1) Tổng cộng có 16 bộ. 2) Khoảng cách giữa hai bộ bất kỳ ít nhất là ba (sao cho các quả bóng ở tâm của bộ có bộ chết người không giao nhau). 3) Sự dịch chuyển theo chu kỳ của một tập hợp cái chết cũng là một tập hợp cái chết (nếu không thì các nhà hiền triết khác nhau sẽ phải sử dụng các chiến lược khác nhau). Theo trực giác, rõ ràng là các tập hợp gây chết người phải được phân bố đồng đều trên tập hợp tất cả các tập hợp có thể. Chúng ta có thể thử tưởng tượng mỗi tập hợp mũ là một biểu diễn nhị phân của một số nguyên từ 0 đến 127 và tập hợp các tập hợp tử là các phần tử của cấp số cộng nào đó, nhưng các phép toán số học truyền thống không phù hợp lắm để cung cấp các thuộc tính 2 và 3 mà chúng ta cần. Vì số học truyền thống không phù hợp với chúng ta nên chúng ta sẽ sử dụng số học “phi truyền thống”, cụ thể là cái gọi là số học của đa thức trên trường {0,1}. Trước hết, chúng ta xác định thao tác cộng hai bộ mũ. Tổng của hai tập hợp có độ dài n là một tập hợp có độ dài n, mỗi phần tử của nó bằng tổng modulo 2 của các phần tử tương ứng của các tập hợp ban đầu. Chúng ta hãy nhắc lại các quy tắc cộng modulo 2: 0 + 0 = 0, 0 + 1 = 1, 1 + 0 = 1, 1 + 1 = 0. Ví dụ: 00110101 + 11110000 = 11000101. Để định nghĩa các phép nhân và chia các tập hợp mũ, thuận tiện nhất là viết các tập hợp dưới dạng đa thức. Tập hợp các chữ hoa $v_{0}, v_{1}, v_{2},^{…}, v n_{1}$ có thể được viết dưới dạng đa thức trong biến $х:_{0}^{v} v_{1}$ $x_{2}^{v}$ $x^{2} …^{v} n_{1}$ $x^{n} 1$. Như vậy, tập các bộ có độ dài n tương đương với tập các đa thức có bậc không vượt quá n – 1. Bây giờ chúng ta định nghĩa tích của hai bộ là tập tương ứng với đa thức
