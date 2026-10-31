---
id: 1982-4-lyudomirskiy-panfilov-pochemu-visit-koltso-d88a0fd5
issue: kvant_1982_4
year: 1982
number: "4"
title: Tại sao chiếc nhẫn lại bị treo?
authors:
  - Людомирский М.
  - Панфилов А.
rubric: laboratoriya-kvanta
rubric_sub: Лаборатория «Кванта»
page_first: 24
page_last: 26
page_labels: 22-24
tag: KO6K
lang: vi
source: kvant_digital
extraction: vision
content_sha256: 650be99ebb649997e44140f325a14a1cb7c52f1c141f8508c7e0c76e878f36f2
prompt_sha256: draft-1
translated_from: content/ru/1982/04/articles/07_lyudomirskiy-panfilov-pochemu-visit-koltso-d88a0fd5.md
source_content_sha256: 522b9ebf7f60821231690a5cdee4bd62324087a0acec172268dfbc64f6e6c0ed
translation_model: draft
translation_run: vi-draft-2026-10-31
translation_quality: draft
---

⟦folio 22⟧

Tại sao cổ phần lại bị treo?

“Tại sao cọc nhôm lại treo lỏng lẻo trên lõi hở của máy biến áp?” — câu hỏi này được đề xuất bởi một người tham gia Chuyến tham quan lần thứ ba của các nhà vật lý trẻ ở Moscow. Có lẽ, bất kỳ học sinh lớp chín nào, không do dự, sẽ trả lời đại loại như sau: "Dòng điện được tạo ra trong vòng, tương tác với từ trường bên ngoài. Theo quy tắc của Lenz, dòng điện indurian luôn có chiều sao cho tác dụng của nó cản trở nguyên nhân tạo ra nó. Trong trường hợp này, dòng điện cảm ứng có hướng đến mức lực Ampe dường như đẩy chiếc cọc ra khỏi cuộn dây máy biến áp. Trong một số trường hợp, lực này cân bằng trọng lực của vòng và nó treo lơ lửng trong không khí."

Thật dễ dàng để xác minh rằng hành vi này của vòng này chính xác là do dòng chảy indurian. Để làm điều này, chỉ cần cắt ngang cọc - nó sẽ không bị treo trong bất kỳ điều kiện nào. Tuy nhiên, có hai điểm trong lời giải thích trên mà chúng tôi muốn lưu ý. Thứ nhất, không rõ loại điện trở vòng nào - chủ động hay cảm ứng - đóng vai trò quyết định. Thứ hai, cần giải thích sự tồn tại của một vị trí cân bằng duy nhất của vòng. Chúng ta hãy cố gắng hiểu những vấn đề này.

1. Hãy chứng minh rằng hiệu ứng treo vòng sẽ không tồn tại nếu vòng chỉ có lực cản chủ động. Hãy thực hiện một số tính toán.

Lực Ampe tác dụng lên một cọc mỏng có chiều dài l mang dòng điện I bằng

$$F = B_r I l,$$

trong đó $B_r$ là hình chiếu nằm ngang của vectơ cảm ứng từ của từ trường bên ngoài (Hình 1). Dòng điện cảm ứng I được xác định theo định luật Ohm:

$$I = \frac{\varepsilon}{R}.$$

Ở đây $\varepsilon$ là suất điện động cảm ứng, $R$ là điện trở hữu dụng của vòng dây. Theo định luật cảm ứng điện từ, suất điện động cảm ứng bằng tốc độ biến thiên của từ thông, lấy dấu ngược lại:

$$\varepsilon = -\Phi' = -(B_B S)'$$

($B_B$ là hình chiếu thẳng đứng của vectơ cảm ứng từ, $S$ là diện tích bị giới hạn bởi thể tích). Cho từ trường biến thiên theo định luật điều hòa với tần số $\omega$ thì

$$B_r = B_{rm} \cos \omega t,$$

$$B_B = B_{bm} \cos \omega t,$$

$$\varepsilon = -(B_B S)' = B_{bm} S \omega \sin \omega t.$$

$$I = \frac{\varepsilon}{R} = \frac{B_{bm} S \omega}{R} \sin \omega t,$$

Và

$$F = B_r I l = \frac{B_{rm} B_{bm} S \omega}{2 R} \sin 2 \omega t,$$

trong đó $B_{rm}$ và $B_{bm}$ là các giá trị lớn nhất của hình chiếu ngang và dọc của vectơ cảm ứng.

Vì giá trị trung bình của sin trong khoảng thời gian bằng 0 nên giá trị trung bình của lực Ampe cũng bằng 0. Vì vậy, Kolyu sẽ không thể làm được mọi việc.

Mâu thuẫn này được loại bỏ nếu chúng ta giả sử rằng kola không chỉ có tác dụng mà còn có tác dụng

⟦folio 23⟧

điện trở dẫn điện cũng đóng vai trò chính. Trong trường hợp này, dòng điện trong vòng sẽ thay đổi theo sự thay đổi pha so với EMF và đối với giá trị tức thời của lực Ampe, sẽ thu được một biểu thức khác:

$$I = \frac{B_{\text{BM}} S \omega}{Z} \sin(\omega t + \varphi),$$

Và

$$F = B_{\text{r}} I l = \frac{B_{\text{GM}} B_{\text{BM}} S \omega l}{Z} \cos \omega t \times \sin(\omega t + \varphi) = \frac{B_{\text{GM}} B_{\text{BM}} S \omega l}{2 Z} \times (\sin(2 \omega t + \varphi) + \sin \varphi)$$

(ở đây $Z$ là tổng điện trở của vòng, $\varphi$ là độ lệch pha giữa dòng điện và suất điện động). Giá trị trung bình của lực trong thời gian đó sẽ bằng

$$F_{\text{cp}} = \frac{B_{\text{GM}} B_{\text{BM}} S \omega l}{2 Z} \sin \varphi,$$

đó chắc chắn không phải là số không.

Trong các thí nghiệm của mình, chúng tôi đã sử dụng các vòng làm từ nhiều lớp lá nhôm với tổng độ dày khoảng 1 mm. Bán kính bên trong của các vòng là 15 mm và bán kính bên ngoài là 30 mm. Người ta ước tính rằng ở tần số 50 Hz, điện trở hoạt động của các vòng như vậy là milliohms và điện trở cảm ứng là mười milliohms. Với các thông số như vậy, lực Ampe có mức $10^{-2}$ N, đủ để giữ một chiếc nhẫn nặng vài gam. Đây là những gì được quan sát bằng thực nghiệm.

2. Tại sao vòng cân bằng chỉ ở một vị trí, ở một độ cao cụ thể? Chúng tôi nhận được Đáp số cho câu hỏi này theo kinh nghiệm.

Biểu thức của lực Ampe bao gồm các giá trị biên độ của các hình chiếu thẳng đứng và nằm ngang của vectơ cảm ứng từ. Cần phải tìm hiểu xem các giá trị này thay đổi như thế nào theo chiều cao.

Chúng tôi đang tiến hành lắp đặt, ảnh chụp trong Hình 2. Một lõi hình trụ làm bằng các thanh sắt (dài 200 mm, đường kính 2 mm) được đặt trong một cuộn dây (bán kính trong của nó là 10 mm, bán kính 40 mm, cao 70 mm) với một cuộn dây đồng tráng men (đường kính 1,2 mm). Cuộn dây được cung cấp điện áp (100-120 V) từ máy biến áp tự ngẫu trong phòng thí nghiệm. Chúng tôi có thể thay đổi hình chiếu theo chiều dọc và chiều ngang của từ trường trong vùng lân cận của lõi ở các khoảng cách khác nhau tính từ cuộn dây. Để làm cảm biến, chúng tôi sử dụng một cuộn dây (làm bằng 300 vòng dây đồng tráng men có đường kính 0,2 mm), trong đó sinh ra lực điện động cảm ứng. Để đo EMF này, cuộn dây được kết nối với đầu vào của máy hiện sóng.

Hóa ra là hình chiếu thẳng đứng của vectơ cảm ứng từ thực tế không thay đổi theo chiều cao và hình chiếu ngang thay đổi như trong Hình 3. Ở đây, chiều cao $H$ phía trên cuộn dây (tính bằng cm) được vẽ dọc theo trục hoành (tính bằng cm) và giá trị biên độ $B_{\text{GM}}$ của hình chiếu ngang của từ trường (tính bằng mili giây) được vẽ dọc theo trục tọa độ. Biểu đồ kết quả cho phép chúng tôi giải thích vị trí quan trọng duy nhất của việc lắp đặt vòng.

⟦folio 24⟧

Để cọc có khối lượng sao cho để bù cho trọng lực tác dụng lên cọc thì cần có một hình chiếu trường nằm ngang khoảng 0,9 mT. Trên đồ thị chỉ có một điểm A tương ứng với giá trị này; Điều này có nghĩa là cọc sẽ treo ở độ cao 4 cm so với cuộn dây. Vị trí cân bằng này ổn định, vì nếu vô tình hạ chiếc vòng xuống sẽ rơi vào từ trường mạnh hơn, lực Ampe sẽ tăng lên và nâng chiếc cọc lên độ cao trước đó.

Điều gì sẽ xảy ra nếu cần có hình chiếu ngang khoảng 0,75 mT để cân bằng vòng? Giá trị này tương ứng với hai điểm trên đồ thị - C và D. Tuy nhiên, trong trường hợp này, chỉ có một điểm cân bằng ổn định - tại điểm C, tức là ở độ cao 6 cm so với cuộn dây. Và tại điểm D trạng thái cân bằng không ổn định. Thật vậy, nếu chiếc cọc giảm xuống dưới độ cao 11,5 cm một chút thì lực Ampe sẽ giảm và không thể cân bằng được lực hấp dẫn; do đó, tiền đặt cược sẽ còn giảm xuống thấp hơn nữa (đến điểm C).

Lưu ý rằng rất khó để phát hiện bằng thực nghiệm vị trí của một điểm cân bằng không ổn định. Điều này là do sự hiện diện của nhiều tác động bên ngoài khác nhau khiến cổ phần bị loại bỏ khỏi vị trí này.

Bạn có thể nghe thấy tiếng gầm của voi ma mút không?
(Để bắt đầu, xem trang 20)

Do đó, Leonid Martynov, người theo sát sự phát triển của khoa học vật lý, đã mô tả sự tương ứng giữa âm thanh và ánh sáng dưới dạng này:

Nó gần như là một cực hình của sự bất động.
Lao đi đâu đó với tốc độ âm thanh,
Biết rất rõ rằng đã có ở đâu đó
Người nào đó
bay
Với tốc độ
Sveta!

Nhưng đây là bài thơ “Tiếng nói” của Mikhail Svetlov, gợi ý rằng theo thời gian, nhờ những chuyến bay vào vũ trụ, một người có thể nghe thấy giọng nói của những người và động vật sống trước đây:

Và có thể là ở ngoài đường chân trời
Anh ấy sống giữa những thế giới đầy sao -
Không được ghi bằng máy ghi âm
Những con voi ma mút chết.
Chúng ta - cùng sống trên thế giới -
Không phải tất cả các phép lạ đã được giải quyết.
Và họ sẽ đau khổ từ hành tinh này sang hành tinh khác
Sức mạnh của giọng nói của đàn ông.
Và có lẽ trên mọi chân trời
Bây giờ lặp lại lần nữa
Lời thì thầm không ngừng của những người yêu nhau
Và Mayakovsky dày đặc bạn.

Đừng chỉ để ngôi sao tách ra,
Nhưng có thể hiểu được và sống mãi
Với giọng khàn khàn của Tsiolkovsky
Sóng âm vẫn chưa dừng lại.
Từ nhỏ tôi đã không giỏi về khoa học;
Không cần tranh cãi với các nhà khoa học,
Tôi dang đôi bàn tay già nua của mình ra
Vào trong không gian xanh vô tận.

Bầu trời đầy những cái đầu
Những người đã sống và yêu thương trên Trái đất.

Nếu Svetlov đúng, thì không khó để tính toán vũ trụ phải di chuyển ra khỏi Trái đất với tốc độ siêu thanh bao nhiêu để chẳng hạn, trong mười năm bay, nó sẽ bắt kịp tiếng gầm của voi ma mút đã bay vào vũ trụ. Như bạn đã biết, mammon đã biến mất khoảng mười nghìn năm trước.

Bạn đọc thân mến, hãy làm một số phép toán và đánh giá những khó khăn khi phóng tên lửa bay với tốc độ thích hợp.

Tiếc thay, sự tự phê bình về tư thế trong bài thơ này không phải là không có cơ sở. Nhớ lại câu chuyện của Puskin, chúng ta đừng quá khắt khe với tư thế, tuy nhiên, sai lầm chính về thể chất của Svetlov là gì? Đáp số cho câu hỏi ở thì hiện tại đơn rằng bạn không nên gửi nó đến tạp chí của chúng tôi. Hãy nghĩ xem cuộc sống trên Trái đất sẽ phức tạp hơn biết bao nếu Svetlov đúng.
