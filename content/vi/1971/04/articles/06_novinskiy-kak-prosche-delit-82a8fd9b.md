---
id: 1971-4-novinskiy-kak-prosche-delit-82a8fd9b
issue: kvant_1971_4
year: 1971
number: "4"
title: Chia thế nào dễ hơn?
authors:
  - Новинский Г. Д.
rubric: smes
page_first: 22
page_last: 31
page_labels: 22, 25, 26, 28, 29
tag: 396J
lang: vi
source: kvant_digital
extraction: vision
content_sha256: 97114e5d156eac9ac8ceacd2b501f5347fe5b0f575e81f50fe719e4ffb621aab
prompt_sha256: 3ec6b8aabd9b98576af76503cd8a2902b9f5d18e01ee867dfb1228f59c6d52d8
translated_from: content/ru/1971/04/articles/06_novinskiy-kak-prosche-delit-82a8fd9b.md
source_content_sha256: 5e4a85609e8485fe20ba3ad24ee4c90b3015d4d22983a418777240417de8e252
translation_model: gpt-5.6-terra
translation_run: vi-codex-2026-10-31
---

⟦folio none⟧

CHIA THẾ NÀO DỄ HƠN?

Làm thế nào để chia dễ nhất một số nhỏ hơn cho một số lớn hơn, nếu số lớn hơn tận cùng bằng chữ số 9?

Giả sử cần chia số a cho số b, trong đó a < b. Đặt b = 10c + 9. Hãy kiểm tra rằng

$$\frac{a}{10c+9} = 10^{-1} \frac{a-p_1}{c+1} + \frac{a-p_1}{c+1} + 10p_1$$

trong đó $p_1$ là số dư khi chia $a$ cho $c+1$, do đó $\frac{a-p_1}{c+1}$ là một số nguyên.

Giả sử $\frac{a}{b} = 0, \alpha_1 \alpha_2 \alpha_3 \dots$ là biểu diễn thập phân của thương. Khi đó $\alpha_1 = \frac{a-p_1}{c+1}$ và $\alpha_1 + 10p_1 = 0, \alpha_2 \alpha_3 \dots$.

Ký hiệu $\alpha_1 + 10p_1$ là $a_1$, ta viết đẳng thức $\frac{a_1}{10c+9} = 0, \alpha_2 \alpha_3 \dots$, từ đó bằng cách tương tự sẽ tìm được $\alpha_2$ và cứ thế tiếp tục.

Ví dụ

1. Cần chia 37 cho 89. Ta làm như sau: chia 37 không cho 89 mà cho 9, vì chữ số hàng đơn vị của số chia là 9, còn hàng chục là 8, 8+1=9. Sau đó viết số dư trước thương rồi lại chia cho 9, và cứ thế tiếp tục. Các thương thu được là các chữ số liên tiếp trong biểu diễn thập phân của phân số $\frac{37}{89}$.

$$-\frac{37}{36} \left| \frac{9}{4} \right| - \frac{14}{9} \left| \frac{9}{1} \right|$$

$$-\frac{51}{45} \left| \frac{9}{5} \right| - \frac{65}{63} \left| \frac{9}{7} \right|$$

Vậy, $\frac{37}{89} = 0,4157\dots$

(Xem phần tiếp theo ở tr. 29.)

⟦folio 22⟧

lời giải trước hết đã được Euler tìm ra bằng phương pháp giải tích, nhưng vẫn bị lẫn trong khối công thức, và chỉ nhờ những cách diễn giải đơn giản và trực quan của Poinsot mà nó được trình bày trước mắt các nhà khoa học một cách hoàn toàn rõ ràng.

Vai trò của Poinsot trong việc làm sáng tỏ vấn đề chuyển động của vật rắn cũng chính là vai trò của Helmholtz trong việc làm sáng tỏ vấn đề chuyển động của chất lỏng.

Hầu như mọi công trình của Helmholtz về cơ học đều посвящены cho cơ học chất lỏng. Có thể nói rằng thủy động lực học hiện đại trong sự phát triển của mình chủ yếu mang ơn Helmholtz. Trong khi đó, công trình đáng chú ý nhất của nhà khoa học trong lĩnh vực này đã xuất hiện vào năm 1858*), tức 43 năm sau khi các công thức chứa đựng nguyên nhân bảo toàn xoáy được Cauchy tìm ra. Nhưng Cauchy chỉ xem xét kết quả nhận được từ phía giải tích và không thấy trước khối lượng những vấn đề có thể được giải quyết khi các kết luận được soi sáng một cách hình học thích đáng.

Bây giờ tôi sẽ cố gắng giải thích cho các bạn một cách đơn giản nhất có thể khái niệm về xoáy do Helmholtz xác lập.

Hãy tưởng tượng một bình hình trụ có chiều cao hữu hạn (hình 1) với đáy rất lớn

*) Ở đây nói đến công trình của Helmholtz về các phương trình thủy động lực học tương ứng với các chuyển động xoáy.

Hình 1

, chứa đầy chất lỏng (hoặc khí), và giả sử chất lỏng này chuyển động như sau: cột hình trụ trung tâm của nó, có một độ dày nào đó, quay như một vật rắn quanh trục của mình, còn phần chất lỏng còn lại quay quanh cột này theo các vòng tròn với vận tốc tỉ lệ nghịch với khoảng cách đến trục của cột, và những vận tốc ấy, tăng lên khi đến gần cột trung tâm, chuyển tại bề mặt của nó thành vận tốc của cột.

Chuyển động như vậy của chất lỏng được gọi là xoáy, còn cột hình trụ đặc trưng cho nó gọi là sợi xoáy. Ta sẽ nói rằng độ mạnh của xoáy bằng một nửa tích của vận tốc chất lỏng trên bề mặt sợi xoáy với chu vi tiết diện vuông góc của sợi.

Đại lượng gấp đôi của tích này được gọi là tuần hoàn vận tốc.

Nói chung, tuần hoàn vận tốc theo một đường cong kín nào đó bên trong chất lỏng chuyển động bằng tích của độ dài đường cong với vận tốc trung bình của tất cả các điểm trên đường cong theo hướng tiếp tuyến với đường cong.

Vì trong chuyển động của chất lỏng được mô tả ở hình 1, các vận tốc tỉ lệ nghịch với các bán kính, nên tuần hoàn vận tốc theo mọi đường tròn nằm ngang có tâm trên trục của cột và bao quanh nó đều bằng nhau và do đó bằng hai lần độ mạnh của xoáy, còn tuần hoàn vận tốc theo các đường cong gồm những cung của hai đường tròn nằm giữa những đoạn của hai bán kính và nằm ngoài sợi xoáy (đường cong АВСД ở hình 2) bằng không. Ngoài ra, có thể chứng minh rằng tuần hoàn vận tốc theo mọi đường cong kín bao quanh xoáy bằng hai lần độ mạnh của xoáy, còn tuần hoàn vận tốc theo mọi đường cong kín không bao quanh xoáy bằng không.

⟦folio none⟧

Hình 5.

bằng nhau, thì tâm này sẽ đi xa đến vô tận, và cả hai sợi sẽ lao về phía trước theo hướng vuông góc với đường thẳng nối các tâm, như thấy ở hình 5.

Ở hình 6 trình bày các quỹ đạo (đường đi) của ba sợi xoáy, trong đó 1 và 2 quay ngược chiều kim đồng hồ, còn 3 quay theo chiều kim đồng hồ.

Khái niệm mà chúng ta đã xác lập về một dây xoáy thẳng nằm trong một bình hình trụ rất rộng được mở rộng cho các dây xoáy phát sinh trong bất kỳ khối chất lỏng nào. Khi đó có thể tìm các dây xoáy bằng cách lập các tuần hoàn

Hình 6.

Hình 7.

⟦folio 25⟧

trong thời gian chuyển động hoặc sẽ có hai đầu nằm trên các biên của chất lỏng (trên thành bình hoặc trên mặt tự do), hoặc sẽ vẫn khép kín.

Thật vậy, để rời khỏi thành bình, đáy của xoáy phải giảm kích thước đến không; mà vì tuần hoàn vận tốc theo đường bao của đáy phải không đổi, nên sự hội tụ sẽ đòi hỏi vận tốc của chất lỏng quay ở chân dây tăng đến vô hạn.

Áp suất thủy động của chất lỏng giảm khi vận tốc tăng. Vì vậy, khi sự hội tụ của xoáy trên thành bình giảm, áp suất ở chỗ đó sẽ giảm nhanh, và phần chất lỏng còn lại sẽ ép lên các hạt ở đầu dây xoáy và ngăn chúng hội tụ vào thành. Có thể nói, dây xoáy hút các đầu của nó vào thành bình. Nếu đầu dây nằm trên mặt tự do, thì có thể nhận thấy sự hút như vậy qua phễu hình thành trên mặt tự do ở “chân” dây.

Nếu các đầu của dây xoáy không nằm trên các biên của chất lỏng, thì chúng phải khép với nhau, và như vậy thu được một dây xoáy khép kín, — một dây mà, có thể nói, cả hai đầu hút vào nhau.

Dạng đơn giản nhất của dây xoáy khép kín là vòng xoáy, được chỉ ra trên hình 7.

Mọi phần chất lỏng nằm ngoài vòng đều xoáy theo những đường cong khép kín đi xuyên qua vòng sao cho tuần hoàn vận tốc theo tất cả các đường cong ấy bằng nhau và bằng tuần hoàn vận tốc trên đường bao tiết diện ngang của vòng. Còn khi đi vào trong vòng, ta sẽ nhận được những tuần hoàn khác nhau đối với quỹ đạo của các hạt của nó. Vận tốc của các điểm chất lỏng

lớn nhất trên bề mặt vòng. Chúng giảm khi rời xa bề mặt này vào bên trong vòng và bằng không trên một đường trục nào đó. Chúng cũng giảm khi rời xa vòng vào khối chất lỏng bao quanh nó. Đối với những điểm chất lỏng ở khoảng cách đáng kể so với vòng, các vận tốc tỉ lệ nghịch với lập phương khoảng cách đến vòng.

Chúng ta đã thấy rằng hai dây thẳng song song phát sinh trong khối chất lỏng, quanh chúng chất lỏng quay với các hướng xoáy bằng nhau nhưng ngược chiều nhau, sẽ chuyển động theo phương vuông góc với mặt phẳng đi qua chúng. Cũng vì nguyên nhân ấy, vòng xoáy sẽ không đứng yên mà sẽ chuyển động theo phương vuông góc với mặt phẳng của vòng, về phía mà chất lỏng chảy ra khỏi vòng.

Ta thấy trên hình 7 rằng các hạt của khối chất lỏng chuyển động theo các quỹ đạo khép kín phía trên sẽ chạy tới mép dưới của vòng và đẩy nó sang phải; cũng vậy, các hạt của khối chất lỏng chuyển động theo các quỹ đạo khép kín phía dưới sẽ chạy tới mép trên của vòng và cũng đẩy nó sang phải. Toàn bộ vòng sẽ chuyển động đều sang phải, mang theo chất lỏng quay quanh nó. Chuyển động này sẽ càng nhanh khi cường độ xoáy càng lớn và kích thước vòng càng nhỏ.

Chúng tôi đã nói rằng bên trong chất lỏng lý tưởng, các xoáy phải tồn tại, được bảo toàn, và không thể hình thành các dây xoáy mới. Trong tự nhiên, chúng ta thường thấy sự xuất hiện và sự tắt dần của các xoáy. Điều này xảy ra vì nước và không khí của chúng ta có một mức độ nhớt nào đó, do đó các kết quả lý thuyết nêu trên có phần thay đổi. Một mặt, các xoáy có thể phát sinh (chủ yếu

⟦folio 26⟧

ở những nơi mà hai lớp chất lỏng chuyển động trượt lên nhau với những vận tốc khác nhau), mặt khác, các xoáy đã phát sinh không được bảo toàn mà dần dần biến mất.

Helmholtz đã biểu diễn sự hình thành các xoáy thẳng bằng một thí nghiệm đẹp, được mô tả trong bài diễn văn của ông về các cơn bão xoáy. Ở đây chúng tôi sẽ lặp lại thí nghiệm ấy.

Ở đáy một bình hình trụ (hình 8) có một lỗ nhỏ, bịt bằng nút. Bình được đổ đầy nước. Bằng các luồng không khí được một ống hướng vào một mép của mặt nước tự do, ta làm cho chất lỏng quay chậm. Chất lỏng bắt đầu chảy ra khỏi lỗ, đi từ các thành bình về trục của nó. Vì sự tuần hoàn của vận tốc theo các đường tròn vẽ từ một điểm trên trục của hình trụ và đi qua cùng những hạt chất lỏng không được thay đổi theo thời gian, nên khi bán kính của các đường tròn ấy giảm đi, vận tốc của các hạt chất lỏng sẽ tăng lên. Sự quay của chất lỏng, khi tiến gần trục, sẽ trở nên ngày càng nhanh hơn, và ta sẽ nhận thấy một xoáy hình thành rõ rệt, phía trên nó xuất hiện một cái phễu ngày càng sâu hơn.

Tôi cũng sẽ chỉ ra sự hình thành xoáy bằng một đĩa quay nhanh.

Trên hình 9 là dụng cụ của giáo sư F. N. Shvedov. Qua đáy của một bình hình trụ bằng thủy tinh, một trục thẳng đứng được đưa qua một vòng đệm, đầu trục có một đĩa nhỏ. Trục này có thể được làm quay nhanh bằng một bộ truyền đai vô tận. Nước và dầu được đổ vào bình, dầu nổi trên mặt nước. Khi quay đĩa, ta sẽ nhận thấy nước dần dần bắt đầu quay và tạo thành phía trên đĩa một dây xoáy, được biểu hiện bằng một cái phễu trên mặt phân cách giữa nước và dầu. Cái phễu này được dầu lấp đầy; dầu, dưới dạng một vòi rồng đi xuống, hạ xuống tới đĩa. Vào lúc dầu tiếp xúc với đĩa, toàn bộ khối lượng của nó phân tán trong nước.

Còn thú vị hơn là cách tạo thành các xoáy thẳng trong không khí. Không khí ở phía trên mặt nước được làm quay bằng một cánh quạt đặc biệt quay nhanh, đặt ở một độ cao nào đó trên mặt nước (hình 10). Xoáy không khí cuốn nước theo trục của mình và nâng nước lên dưới dạng một vòi rồng đi lên, tới tận cánh quạt.

Các vòng xoáy trong không khí được biểu diễn bằng dụng cụ của Tait. Nó gồm một hộp (hình 11), mặt sau được căng da, còn ở mặt trước có một lỗ với các mép sắc. Hình dạng của-

⟦folio 28⟧

Cho đến nay, các vòng được chúng ta phóng ra từ một lỗ tròn. Bây giờ hãy thử tạo chúng từ một lỗ hình elip và hình vuông. Ta thấy rằng khi đó các vòng không giữ hình dạng của lỗ, mà dao động, có xu hướng chuyển thành một vòng tròn; như vậy, vòng tròn là dạng ổn định duy nhất của một dây xoáy khép kín.

Bây giờ ta xét ảnh hưởng của các vật bên ngoài lên các vòng xoáy. Đưa các vật rắn lại gần vòng xoáy đang chuyển động từ bên cạnh, ta thấy chúng đẩy vòng xoáy ra. Nhưng nếu vòng xoáy chạy vào một mặt phẳng đứng yên song song với mặt phẳng của nó, thì khi đến gần mặt phẳng ấy, nó càng lúc càng tăng kích thước, có thể nói là loang ra trên mặt phẳng. Nếu ta cho vòng xoáy chạy vào một lưỡi dao mà mặt phẳng của nó đi qua trục của vòng xoáy, thì vòng xoáy sẽ bị lưỡi dao cắt thành hai nửa vòng, các đầu của chúng sẽ trượt trên bề mặt lưỡi dao; nhưng khi đi qua bề mặt ấy, các đầu lại nối với nhau, và vòng xoáy được phục hồi.

Ngoài các vòng khói trong không khí, còn có thể quan sát các vòng không khí trong nước. Hiện tượng thú vị này, thoạt nhìn có vẻ nghịch lý, được giải thích rất đơn giản bởi vì do lực ly tâm, áp suất giảm đáng kể trên trục của vòng xoáy. Nếu khi tạo vòng xoáy ta đưa vào nước vài bọt không khí, chúng lập tức sẽ đi vào chỗ của chất lỏng nơi áp suất là nhỏ nhất, tức là vào trục của vòng xoáy, và sẽ được giữ ở đó suốt thời gian vòng xoáy chuyển động trong khối nước xung quanh, mặc dù không khí nhẹ hơn nước 800 lần.

Ở đây tôi chỉ ra một dụng cụ tạo các vòng không khí trong nước, là một biến dạng của dụng cụ của giáo sư Osborne Reynolds. Ở đây có (hình 12) một bể thủy tinh lớn chứa đầy nước. Trong đó nhúng một ống thủy tinh rộng, uốn vuông góc.

Hình 12.

Vào đầu trên của ống nhô ra khỏi nước, người ta lắp một ống tay bằng quả cầu cao su, nhờ đó có thể bơm không khí vào ống và đẩy nước ra khỏi nó. Bóp nhanh quả cầu, ta đẩy một cột nước ra khỏi đoạn ống nằm ngang và làm điều đó sao cho không khí gần chạm tới đầu dưới của ống, nhưng không thoát ra khỏi đó với số lượng lớn. Cột nước, thoát vào chất lỏng xung quanh đứng yên, cuộn thành một vòng xoáy. Đồng thời cùng với nước sẽ bị đẩy ra vài bọt khí, và vòng xoáy sẽ thấy rõ: nó sẽ được tạo thành như từ những hạt ngọc trai lấp lánh. Chạy dọc theo cả bể, vòng xoáy đập vào thành đối diện và ở đây, nở rộng ra, biến mất.

Với dụng cụ của chúng ta, ta có thể biểu diễn rõ ràng sự phản xạ của các vòng xoáy từ mặt thoáng của nước. Muốn vậy chỉ cần xoay ống sao cho đầu dưới của nó hướng hơi lên trên. Vòng xoáy, chạy đến mặt thoáng của chất lỏng, bị nó phản-

⟦folio 29⟧

giảm, hơn nữa góc tới bằng góc phản xạ.

Vì các chất lỏng thực có độ nhớt và cọ xát vào thành các bình chứa mà chúng chuyển động trong đó, nên trong quá trình chuyển động chúng luôn luôn được lấp đầy bởi các ống xoáy. Helmholtz đã chỉ ra rằng khối chất lỏng trong mọi chuyển động tưởng tượng có thể được xem là được lấp đầy liên tục bởi các ống xoáy, và dùng làm phương tiện nghiên cứu chuyển động của các ống này.

Những thông tin ngắn về các nhà khoa học được nhắc đến trong bài giảng của N. E. Zhukovsky.

Euler là nhà toán học lớn nhất thế kỷ XVIII, viện sĩ Viện Hàn lâm Petersburg, một trong những người sáng lập cơ học giải tích. Laplace gọi Euler là cha đẻ của giải tích toán học hiện đại.

Poinsot là nhà khoa học Pháp, nhà toán học và nhà cơ học. Năm 1834, ông đã tìm được lời giải hình học thanh nhã cho một số vấn đề của động lực học quay.

Helmholtz là nhà vật lý và toán học Đức xuất sắc của thế kỷ XIX. Ông nổi tiếng, đặc biệt, nhờ các công trình về âm học (các bộ cộng hưởng Helmholtz) và về nhiệt động lực học. Ông cũng là người sáng lập lý thuyết xoáy.

Cauchy là nhà khoa học Pháp cuối thế kỷ XVIII — nửa đầu thế kỷ XIX, người được coi là một trong những người sáng lập toán học hiện đại. Ông để lại hơn 800 chuyên khảo về những ngành rất khác nhau của toán học.

Shvedov V. F. là giáo sư Đại học Odessa, chuyên gia nổi tiếng về thủy động lực học chất lỏng nhớt (nửa sau thế kỷ XIX).

Teg là giáo sư vật lý ở Edinburgh (Anh, nửa sau thế kỷ XIX).

Reynolds là giáo sư Trường Cao đẳng Owens ở Manchester (Anh, nửa sau thế kỷ XIX). Ông nổi tiếng nhờ các công trình về thủy động lực học.

2. Cần chia 28 cho 59. 5+1=6.

$$\frac{28}{24} \cdot \frac{6}{4} - \frac{44}{42} \cdot \frac{6}{7}$$

$$\frac{27}{24} \cdot \frac{6}{4} - \frac{34}{30} \cdot \frac{6}{5}$$

Vậy, $$\frac{28}{59} = 0.4745$$

Cách chia này đơn giản hơn cách được chấp nhận rộng rãi và dễ thực hiện hơn. Nó được nhà toán học Đức G. Spitzer đề xuất năm 1847. Nhưng chẳng bao lâu người ta đã quên nó.

G. D. Novinsky
