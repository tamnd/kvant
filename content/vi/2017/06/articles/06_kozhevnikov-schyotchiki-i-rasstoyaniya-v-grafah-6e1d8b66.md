---
id: 2017-6-kozhevnikov-schyotchiki-i-rasstoyaniya-v-grafah-6e1d8b66
issue: kvant_2017_6
year: 2017
number: "6"
title: Bộ đếm và khoảng cách trong biểu đồ
authors:
  - Кожевников П. А.
rubric: matematicheskiy-kruzhok
rubric_sub: Математический кружок
page_first: 40
page_last: 53
page_labels: 39, 40, 46
tag: 4WBW
lang: vi
source: kvant_digital
extraction: native
content_sha256: e5487e8473be85b0ce2a04dd9a1ee492f5f206f51cff8e6aadf5a6eb9a50f6b1
prompt_sha256: draft-1
translated_from: content/ru/2017/06/articles/06_kozhevnikov-schyotchiki-i-rasstoyaniya-v-grafah-6e1d8b66.md
source_content_sha256: 1994cce5e01a3cecaffc09dccf06f0338f0872857a09c95c934f32e55e3e7fca
translation_model: draft
translation_run: vi-draft-2026-10-31
translation_quality: draft
---

⟦folio none⟧

VÒNG TRÒN TOÁN HỌC

Bộ đếm và khoảng cách trong biểu đồ

P.KOZHEVNIKOV

TRONG BÀI VIẾT NÀY CHÚNG TÔI SẼ THẢO LUẬN MỘT SỐ cách tiếp cận đối với các bài toán tổ hợp trong việc ước lượng số lượng phép toán. Trước tiên chúng ta hãy xem xét bài toán sau đây. Bài toán 1. Trên mặt phẳng, một hình vuông ca rô 5 5 (hình1) được bố trí bằng các vách ngăn (thành các đoạn đơn). Thật là nhỏ

⟦column⟧

⟦figure⟧

Hình 3

hai thẻ liền kề (hình3). Trong số lần di chuyển nhỏ nhất bạn luôn có thể có được một hàng thẻ đi từ trái sang phải theo thứ tự tăng dần là bao nhiêu? Các điều kiện bài toán hoàn toàn khác nhau nhưng có một cấu trúc duy nhất: một thao tác nhất định được xác định và câu hỏi được đặt ra là về số lượng nhỏ nhất các thao tác đó phải được thực hiện để đi từ vị trí này sang vị trí khác. Để tìm cách tiếp cận lời giải bài toán, trước tiên chúng ta thảo luận về bài toán đơn giản hơn với cấu trúc logic tương tự. Đơn giản bài toán. Con chip đứng ở điểm 7, mặt phẳng tọa độ 7 (hình4). Vì

⟦figure⟧

Hình 1

Cần phải cắt bỏ bao nhiêu phân vùng để mỗi ô vuông có thể thoát ra bên ngoài (không vượt qua phân vùng)? Bài toán 2. Cho một dải 1 20, trong đó mỗi ô có màu trắng hoặc đen. Trong một thao tác, bạn có thể đổi màu các ô theo bất kỳ hình chữ nhật nào (hình2). Để làm gì

⟦figure⟧

Hình 2

Với số thao tác ít nhất, bạn chắc chắn có thể làm cho toàn bộ dải màu trắng? Bài toán 3. Mười thẻ có số từ 1 đến 10 được xếp thành một hàng theo thứ tự nào đó. Bạn có thể thay đổi địa điểm chỉ trong một lần di chuyển

⟦figure⟧

Hình 4

Trong một lần di chuyển nó có thể được di chuyển 1 bên phải, bên trái, lên hoặc xuống. Số nước đi ít nhất mà một quân cờ có thể đi đến điểm gốc là bao nhiêu? Tất nhiên, ở ô 14: ô xuất phát cách mục tiêu 7 ô ngang và 7 ô dọc nên bạn sẽ phải thực hiện ít nhất 7 nước đi ngang và ít nhất 7 nước đi dọc (và tất nhiên, có rất nhiều cách để về đích đúng 14 nước đi). Người ta có thể tranh luận khác nhau. Đến mỗi nút của góc phần tư thứ nhất của số nguyên lại

⟦folio 39⟧

TOÁN HỌC

lưới, ta ghi tổng tọa độ, sau đó các số viết ra biểu thị một loại bộ đếm: khi một con chip nằm trong một ô có số k thì nó có k lượt di chuyển sang trái để về đích. Bộ đếm có thể được cài đặt mà không cần đến tọa độ, chỉ cần di chuyển từ mục tiêu “từ cuối”: chúng tôi đặt số 1 vào các nút mà từ đó bạn có thể đạt được mục tiêu trong một lần di chuyển (I “tầng”), số 2 trong các nút mà từ đó bạn có thể đến một nút nhất định từ tầng 1 trong một lần di chuyển (II “tầng”), v.v.

Bài tập 1. Chín quân cờ ban đầu điền vào góc trên bên phải của bàn cờ 3 3. Trong một lần di chuyển, bạn có thể di chuyển một trong các quân cờ sang ô trống liền kề. Số nước đi ít nhất mà 3 3 có thể di chuyển quân cờ đến góc dưới bên trái là bao nhiêu?

Nhưng hãy quay lại vấn đề 1–3. Bây giờ, nếu chúng ta cũng có thể tìm thấy một bộ đếm phù hợp thay đổi 1 (hoặc ít nhất theo một cách được kiểm soát nào đó) khi thực hiện thao tác... Khi đó, chúng ta sẽ hiểu chúng ta còn cách mục tiêu bao xa (về số lần di chuyển) và có lẽ chúng ta có thể hoàn thành lời giải trong thời gian ngắn như trong Đơn giản bài toán. Hãy thử nó! Thảo luận và lời giải bài toán 1. Chúng ta sẽ coi mặt phẳng là một “đại dương” trong đó các vách ngăn đã ngăn cách một số “hồ chứa” rải rác. Chúng ta hãy chú ý đến thực tế là lúc đầu chúng ta có nhiều vùng nước riêng biệt, và ở cuối, theo điều kiện, chỉ còn lại một vùng nước (bạn có thể bơi từ bất kỳ ô nào đến “đại dương”). Trong trường hợp này, trong một lần vận hành, hai hồ chứa liền kề với vách ngăn sẽ hợp nhất thành một. Điều này có nghĩa là số lượng hồ chứa trong một hoạt động giảm đi 1? Điều này gần như đúng: đôi khi hai ô liền kề với vách ngăn là các ô của cùng một vùng nước (hình5). Trong trường hợp này, sau thao tác tháo vách ngăn, số lượng hồ chứa sẽ không thay đổi. Dù thế nào đi nữa, trong một

Hình 5

VÒNG TRÒN

⟦column⟧

hoạt động, số lượng hồ chứa giảm không quá 1. Lúc đầu chúng ta có 26 hồ chứa (bao gồm cả “đại dương” bên ngoài), cuối cùng phải còn lại một hồ chứa, vì vậy số lượng hoạt động ít nhất là 26 – 1 = 25. Chúng tôi mời độc giả đưa ra một ví dụ về việc loại bỏ chính xác 25 phân vùng (như chúng ta hiểu bây giờ, trong ví dụ tối ưu, chỉ cần tránh loại bỏ các phân vùng giữa hai ô của cùng một hồ chứa). Do đó, bộ đếm thích hợp (số lần di chuyển tối thiểu đến mục tiêu) trong bài toán 1 là n – 1, trong đó n là số lượng nước. Lưu ý rằng việc cải cách bài toán này đã được thảo luận trong «Kvant» và trước đó - ví dụ: trong bài viết “Liên hệ với Bá tước” («Kvant» Số 4, 2014). Trên thực tế, trong nhiều bài toán của bài viết đã đề cập, bộ đếm “số vùng (hoặc phần, hoặc thành phần liên thông trong đồ thị)” xuất hiện. Thảo luận và lời giải bài toán 2. Cuối cùng, tất cả các ô của dải sẽ trở thành màu trắng, vì vậy lúc đầu, có vẻ như bộ đếm mà chúng ta đang tìm kiếm phải liên quan đến số lượng ô đen. Nhưng ngay cả khi có nhiều ô đen, đôi khi bạn có thể xử lý chỉ bằng một thao tác sơn lại (ví dụ: đối với sọc đen hoàn toàn). Thực tế là việc “chiến đấu” với một khối ô đen liên tiếp cũng dễ dàng như với một ô đen. Nhưng việc loại bỏ một số lượng lớn các chuyển tiếp giữa các khối đen và trắng không phải là điều dễ dàng như vậy. Chìa khóa của lời giải được tìm thấy bằng cách xem xét các khối này hoặc sự chuyển tiếp giữa các khối đen và trắng. Hãy lấy bộ đếm “số khối màu đen”. Sau khi xem xét tất cả các trường hợp có thể xảy ra khi thực hiện thao tác sơn lại (khi ranh giới của hình chữ nhật được sơn lại nằm bên trong khối đen hoặc trắng hoặc nằm giữa các khối; một số trường hợp được hiển thị trong hình 6), chúng tôi đảm bảo rằng số khối đen không thay đổi hoặc thay đổi bằng 1. Số khối đen cuối cùng phải là 0, số khối đen ban đầu có thể là 10 - như trong trường hợp “ngựa vằn” ở hình 7. Điều này có nghĩa là nếu màu ban đầu là ngựa vằn, thì chúng ta sẽ cần thực hiện ít nhất 10 thao tác.

⟦folio 40⟧

KVANT 2017/№6

⟦figure⟧

Hình 6

⟦figure⟧

Hình 7

Mặt khác, rõ ràng là trong mọi tình huống, số khối đen ban đầu không quá 10. Và chúng ta chỉ cần lấy một khối đen sau mỗi thao tác liên tiếp và biến nó thành màu trắng. Không quá 10 thao tác chúng ta sẽ có được một sọc trắng.

Bài tập 2. Nghĩ ra một lý luận khác để giải bài toán bằng cách sử dụng các “phân vùng” giữa các khối đen và trắng.

Thảo luận và lời giải bài toán 3. Có thể thấy rõ bằng trực giác rằng tình huống “bất tiện” nhất là khi các quân bài ban đầu được sắp xếp theo thứ tự giảm dần: 10, 9, 8, …, 1. Trước tiên, bạn có thể theo dõi chuyển động của từng quân bài. Để đạt thứ tự tăng dần là 1, 2, ..., 10, quân bài 1 (giống như quân bài 10) cần chuyển 9 vị trí sang trái (tương ứng sang phải), quân bài 2 và 9 - sang 7 vị trí, quân bài 3 và 8 - sang 5, quân bài 4 và 7 - sang 3, quân bài 5 và 6 - sang 1 vị trí. Tổng cộng, tổng chuyển động phải bằng 2(9 + 7 + 5 + + 3 + 1) = 50. Trong một nước đi, hai quân bài di chuyển bằng 1, vì vậy bạn cần thực hiện ít nhất 50/2 = 25 nước đi. Tuy nhiên, để mỗi quân bài di chuyển đúng số đơn vị quy định thì không được phép di chuyển “sai hướng”. Ví dụ: để về vị trí ngoài cùng bên trái trong 9 nước đi, quân bài 1 chỉ được di chuyển sang trái. Điều tương tự cũng đúng với quân bài 2: để về vị trí thứ hai tính từ bên trái trong 7 nước đi, quân bài 2 chỉ được di chuyển về bên trái. Nhưng đồng thời

⟦column⟧

Hai điều kiện này là không thể đối với quân bài 1 và 2. Thật vậy, trong tình huống ban đầu, quân bài 1 nằm ở bên phải quân bài 2, và trong tình huống cuối cùng, nó ở bên trái. Điều này có nghĩa là trong một số nước đi, chúng ta sẽ cần đổi quân bài 1 và 2, và quân bài 2 sẽ di chuyển 1 sang bên phải, tức là sẽ di chuyển theo hướng “sai”. Hóa ra việc cố gắng nhập bộ đếm “tổng số bước di chuyển” sẽ dẫn đến một số ước tính về số bước di chuyển, nhưng ước tính này không chính xác. Tuy nhiên, hiểu được tình hình, chúng tôi nhận ra rằng chúng tôi chắc chắn sẽ thực hiện một nước đi bao gồm việc đổi một cặp quân bài 1 và 2 cụ thể. Tương tự, đối với bất kỳ cặp quân bài nào m < n, mà trong tình huống ban đầu, quân bài n nằm ở bên trái quân bài m (những cặp quân bài “sai” ban đầu như vậy còn được gọi là “rối loạn”), tại một thời điểm nào đó lẽ ra phải có một nước đi bao gồm việc đổi quân bài m và n. Điều này có nghĩa là để từ vị trí 10, 9, 8, ..., 1 đến vị trí 1, 2, ..., 10 thì phải đổi từng cặp thẻ cụ thể. Như vậy, số bước di chuyển cần thiết không ít hơn số cặp, tức là không ít hơn

10 9 2

45.

Mặt khác, đối với bất kỳ tình huống ban đầu nào, 45 nước đi là đủ. Ví dụ: đầu tiên chúng ta đổi lá bài 1 với tất cả các lá bài ở bên trái của nó, kết quả là nó sẽ ở vị trí ngoài cùng bên trái. Sau đó, chúng ta “di chuyển” quân bài 2 sang trái và chuyển nó sang vị trí thứ hai bên trái, v.v. Mỗi lần chúng ta giảm số lần xáo trộn đi 1, nghĩa là chúng ta sẽ thực hiện không quá 45 nước đi đến vị trí cuối cùng 1, 2, ..., 10. (Tất nhiên, ở đây chúng ta có thể ước tính số nước đi mà không bị xáo trộn: quân bài 1 thực hiện không quá 9 nước đi, sau quân bài 2 đó - không quá 8 nước đi, v.v., cuối cùng, quân bài 9 không thực hiện nhiều hơn hơn một nước đi, tổng cộng không quá 9 + 8 + ... + 1 = = 45 nước đi.) Bài toán 3 đã được giải quyết. Bộ đếm “số lượng bất ổn” đã giúp ích ở đây. Bộ đếm này đã “chính xác”: trong một lần di chuyển, nó thay đổi (tăng hoặc giảm) đúng 1.

Bài tập 3. Ban đầu, 10 quân bài có số từ 1 đến 10 được xếp thành một hàng theo thứ tự 2, 4, 6, 8, 10, 1, 3, 5, 7, 9. Trong một nước đi, bạn có thể đổi chỗ hai quân bài liền kề (như trong bài toán 3).

⟦folio 46⟧

KVANT 2017/№6

Lớp 11 1. Xem bài toán 1 cho lớp 10. 2. Tìm số có ba chữ số viết dưới dạng số từ 0 đến 9 có đúng hai chữ số trùng nhau. 3. Đường tròn nội tiếp tứ giác ABCD có các cạnh AB và CD không bằng nhau tiếp xúc với các cạnh AB, BC, CD, AD lần lượt tại các điểm K, L, M và N. Chứng minh rằng các đường thẳng AC, KL, MN có điểm chung. 4. Tìm lũy thừa lớn nhất của số 3 chia hết tất cả các số tự nhiên từ 1 đến 2017. 5. Giải hệ hai phương trình $x y^{2} 2$ và $x^{2} y 2. 6.$ Với mỗi giá trị của a, tìm giá trị lớn nhất của hàm f x a

1 sin 2 x a

3 cos 2 x bằng M a. Tìm giá trị nhỏ nhất của M a.

BỘ PHẬN VẬT LÝ

VẬT LÝ

lớp 7

1. Dùng thước để đo chiều dài, chiều rộng và chiều cao của một hộp đặc, chẳng hạn như hộp giày. Xác định diện tích mỗi bề mặt và thể tích của hộp. Ước tính sai số của mỗi phép đo được thực hiện. 2. Đo chiều dài sải chân của bạn. Sử dụng “thước đo” này, hãy xác định độ dài quãng đường bạn đi bộ đến trường hoặc bến xe buýt. Ước tính sai số khi xác định đường đi. 3. Một ô tô đi nửa quãng đường đầu với vận tốc $v_{1} = 70$ km/h, nửa quãng đường sau với vận tốc $v_{2} = 30$ km/h. Xác định vận tốc trung bình trên toàn bộ quãng đường. 4. Người nghe vở opera: một khán giả ngồi trong phòng hát và một người nghe đài đặt gần máy thu. Micro được lắp đặt trong dàn nhạc. Tốc độ âm thanh v = 340 m/s. Tốc độ truyền sóng vô tuyến là $c 3 10^{8}$ m/s. Khán giả phải ngồi cách dàn nhạc một khoảng bao nhiêu $s_{1}$ để có thể nghe đồng thời với người nghe đài, nếu người nghe đài ở khoảng cách $s_{2} = = 7500$ km từ nhà hát?

⟦column⟧

5. Thang máy đi từ tầng mười một của tòa nhà xuống tầng năm rồi đi lên tầng tám. Giả sử khoảng cách giữa các tầng là L = 4 m, hãy xác định đường đi và chuyển vị của cabin.

lớp 8

1. Cm. bài toán 1 cho lớp 7. 2. Con thuyền chuyển động theo dòng nước giữa hai điểm, đã dành thời gian $t_{1}$, và khi quay trở lại, anh ấy đã dành thời gian $t_{2}$. Vận tốc của thuyền so với nước v. Tìm vận tốc của dòng nước. 3. Dài hai chuyến tàu $L_{1} = 600$ tôi và $L_{2} = = 800$ m đi dọc theo các đường song song cùng hướng với tốc độ $v_{1} = = 54$ km/h và $v_{2} = 72$ m/h tương ứng. Họ vượt qua nhau bao lâu? 4. Xác định lực căng của sợi dây nối hai quả cầu thể tích $10 см^{3}$ mỗi cái, nếu quả bóng trên nổi, một nửa chìm trong nước (hình3). Quả bóng dưới nặng gấp 3 lần quả bóng trên Hình 3 anh ấy. 5. Một vật khối lượng m rơi từ độ cao H rồi lại nâng lên độ cao h. Lượng nhiệt Q tỏa ra khi vật chạm vào bề mặt là bao nhiêu?

lớp 9

1. Khi một phần bánh bao đông lạnh được cho vào chảo nước sôi, mực nước trong đó dâng lên tới độ cao $h_{1}$. Sau một thời gian, bánh bao đã chín và nổi lên - sau đó mực nước lại tăng thêm $h_{2}$. Mật độ của bánh bao đông lạnh lớn hơn mật độ của nước sôi bao nhiêu lần? Bánh bao không hấp thụ nước. 2. Có hai thước đo giống nhau có kích thước a b c 30 2,5 0,4 cm và một khối lượng đã biết. Cần xác định khối lượng của thước. Để làm điều này, một thước kẻ được lắp theo chiều dọc và thước thứ hai được đặt trên thước thứ nhất sao cho thước tạo thành chữ T và thước ngang không rơi (hình4). Sau đó lấy một vật nặng có khối lượng m đã biết và tìm khoảng cách tối thiểu $x_{1}$ và $x_{2}$ đến các cạnh của đường thẳng

⟦folio none⟧

ĐÁP ÁN, HƯỚNG DẪN, GIẢI PHÁP

“SỐ LƯỢNG” CHO HỌC SINH THI

NHIỆM VỤ

(xem «Kvant» số 5)

1. 7 bán. Đổi bằng 3 đồng xu khác nhau không nhỏ hơn 1 + 2 + 3 = 6 selli. Vì số tiền này không đủ mua kem nên giá không dưới 7 selli. Kem không thể có giá nhiều hơn 7 selli, nếu không Pinocchio sẽ chi không ít hơn 8 + 8 = 16 selli cho hai cây kem, nhưng cậu ấy chỉ có một đồng xu, tức là không quá 20 selli, và khi đó cậu ấy sẽ không thể đổi lại được 6 selli. Điều này có nghĩa là kem chỉ có giá 7 selli. Thật vậy, quá trình thanh toán tiền kem sẽ như thế này: 20 – 7 = 13; 13 – 7 = 6 = 1 + + 2 + 3. 2. Màu xanh lam. Bức ảnh màu đầu tiên có 8 cạnh màu đỏ, bức ảnh thứ hai có 8 cạnh màu xanh và bức ảnh thứ ba có 8 cạnh màu vàng. Vì bốn hình lập phương có tổng cộng 6 ¥ 4 = 24 cạnh và 8 ¥ 3 = 24 nên ảnh đầu tiên có tất cả các mặt màu đỏ, ảnh thứ hai có toàn màu xanh và ảnh thứ ba có toàn màu vàng. Trong bức ảnh của hình song song, tất cả bốn khối đều có thể nhìn thấy được và chỉ một trong số chúng có một mặt nhìn thấy được và mỗi khối trong số ba khối còn lại có ít nhất hai mặt nhìn thấy được. Trong bức ảnh màu đầu tiên có hai hình khối chỉ có một cạnh màu đỏ, nghĩa là màu bạn đang tìm không thể là màu đỏ. Trong bức ảnh màu thứ ba có một khối lập phương không có mặt màu vàng, do đó màu bạn đang tìm không phải là màu vàng. Vì vậy, tất cả các mặt nhìn thấy được của hình khối chỉ có thể có màu xanh lam. Điều này có thể xảy ra, vì trong bức ảnh màu thứ hai: 1) có một khối lập phương có ba mặt màu xanh lam có một đỉnh chung; 2) có hai hình lập phương, mỗi hình có hai mặt màu xanh liền kề nhau; 3) có một khối lập phương khác có cạnh màu xanh. Lưu ý rằng điều kiện bài toán cho phép chúng ta xác định màu sắc của tất cả các hình khối. Có một khối lập phương có ba mặt đỏ liền kề và ba mặt xanh liền kề, một khối lập phương có ba mặt đỏ liền kề, hai mặt vàng và một mặt xanh và hai khối lập phương giống hệt nhau có ba mặt vàng liền kề, hai mặt xanh và một mặt đỏ. 3. Dưới đây là hai ví dụ có thể:

7 6 5 3 5 6 9 2 + + + = 9, + + + = 7. 4 8 1 2 4 8 3 1

4. Vâng, nó có thể. Ví dụ – tại hình 1.

⟦column⟧

⟦figure⟧

Hình 1

CUỘC THI ĐẶT THEO A.P. SAVINA

(xem «Kvant» số 4)

24. 182. Nếu phẩm chất nào đó của một nàng tiên tăng lên mỗi ngày, thì cô ấy không thể trở nên như cũ. Điều này có nghĩa là để nàng tiên không thay đổi, điều cần thiết là mỗi phẩm chất của nó phải xấu đi ít nhất một lần hoặc luôn giữ nguyên. Nếu có ít nhất 183 nàng tiên thì tổng cộng họ có 183 ◊ 2 = 366 phẩm chất - nhiều hơn số ngày trong một năm. Nhưng mỗi ngày chỉ có một phẩm chất của một nàng tiên xấu đi hoặc vẫn giữ nguyên. Vì vậy điều này không thể xảy ra. Hãy chứng minh rằng có thể có 182 nàng tiên. Thế thì họ có 364 phẩm chất. Hãy để mỗi ngày một trong những phẩm chất này giảm đi, tổng cộng là 365 phẩm chất giảm đi. 363 phẩm chất sẽ giảm đi một lần mỗi năm và bằng mức tăng lên trong tất cả các ngày khác. Và chất lượng còn lại sẽ có hai lần giảm, một lần nữa cũng chính xác bằng mức tăng trong 363 ngày còn lại. Rồi các nàng tiên cuối năm sẽ giống như lúc đầu. 25. a) Có; b) có; c) không. a) Gọi các đỉnh của tứ giác là A, B, C, D. Vì AC là dây cung của đường tròn nên đường trung trực của AC chia đường tròn làm đôi. Giả sử điểm E đối xứng với điểm D qua đường phân giác. Do tính đối xứng nên điểm E cũng nằm trên đường tròn nên AD = CE và AE = BD. Khi đó tứ giác ABCE là tứ giác mong muốn: nó nằm bên trong đường tròn và độ dài các cạnh của nó bằng độ dài của tứ giác ban đầu, nhưng thứ tự của chúng đã thay đổi. (Thật ra, chúng ta đã cắt tứ giác dọc theo đường chéo AC, lật tam giác ADC và nối lại thành một tứ giác.) Lưu ý rằng chúng ta chỉ sử dụng tính chất AC là dây cung của đường tròn.
