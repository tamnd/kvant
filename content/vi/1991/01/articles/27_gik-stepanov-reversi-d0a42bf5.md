---
id: 1991-1-gik-stepanov-reversi-d0a42bf5
issue: kvant_1991_1
year: 1991
number: "1"
title: Đảo ngược
authors:
  - Гик Е. Я.
  - Степанов О.
rubric: igry-i-golovolomki
rubric_sub: Игры и головоломки
page_first: 68
page_last: 72
page_labels: 66-70
lang: vi
source: kvant_digital
extraction: vision
content_sha256: a590f44681b9e17dc0c83bd8c9367bf471e00bfaaa9c294192b569303d475f1f
prompt_sha256: draft-1
translated_from: content/ru/1991/01/articles/27_gik-stepanov-reversi-d0a42bf5.md
source_content_sha256: bacf5045178799a765c2428ee20c33800c6ebbd7253efbc3b19677da7c900223
translation_model: draft
translation_run: vi-draft-gaps-2026-11-06
translation_quality: draft
---

⟦folio 66⟧

---
running_head:
folio:
---

Đảo ngược

Trò chơi đảo ngược (từ tiếng Anh sang đảo ngược - sang hình thức) được ưa chuộng ở nhiều nước. Ở Hoa Kỳ, nó đứng ở vị trí thứ hai sau cờ vua và ở Nhật Bản - sau cờ vây. Nhiều giải đấu và trận đấu khác nhau được tổ chức, bao gồm cả giải vô địch thế giới. Trò chơi thu hút bởi luật chơi đơn giản - chúng đơn giản hơn cờ vua và cờ đam - và năng động một cách đáng ngạc nhiên. Tình hình trên bàn cờ thay đổi ngay lập tức và tất cả các cuộc chinh phục của người chơi trong một lượt đều có thể thuộc về kẻ thù.

Reversi đã được biết đến từ thời xa xưa và vào đầu những năm 70 của thế kỷ 20, chúng đã được Hasedzhawa người Nhật khám phá lại. Những cái bẫy quỷ quyệt và những tình huống bất ngờ đặc trưng cho trò chơi đã khiến anh ta liên tưởng nó với Othello của Shakespeare, và kết quả là họ nhận được một cái tên khác - Othello.

Thuộc tính của trò chơi là 8x8 doxa và 64 chip (32 cho mỗi người chơi), một mặt sơn màu trắng và mặt kia màu đen. Bạn cũng có thể chơi cờ vua thông thường; màu sắc của các trường của nó không thành vấn đề. Chip có thể được tạo ra bằng cách dán các quân cờ trắng và đen thông thường với nhau hoặc sơn 64 nút giống hệt nhau bằng hai màu.

Hãy mô tả ngược lại luật chơi. Người chơi chơi quân trắng đặt chip của mình lên mặt trắng, và người chơi chơi đen đặt chip của mình lên mặt đen. Trước hết, các đối tác đặt hai quân cờ của họ vào giữa doxy, như thể hiện trong hình 1 (trong trò đảo ngược, không giống như cờ vua, các đường ngang của doxy được đánh số từ trên xuống dưới).

Đen thực hiện nước đi đầu tiên (như trong cờ vây và Renju, nhưng không giống như cờ vua và cờ đam). Đối thủ lần lượt đặt một trong các chip của họ trên các ô trống của doxy, bên cạnh một trong các chip của đối thủ và do đó, cùng với một số chip của họ, họ bao quanh (bao quanh) một hoặc nhiều chip của đối thủ theo chiều ngang, chiều dọc hoặc đường chéo (hoặc dọc theo nhiều đường cùng một lúc). Nói cách khác, một con chip được đặt trên cùng một hàng với một con chip khác cùng màu, đã có trên dox và giữa chúng phải có một hàng chip của đối phương, nhưng không có ô trống. Các con chip bao quanh cả hai mặt đều bị bắt, nhưng không bị loại bỏ khỏi doxy mà được lật sang phía bên kia, thay đổi màu sắc. Nếu việc bao vây xảy ra đồng thời dọc theo một số đường thì tất cả các chuỗi chip bị bắt sẽ được lật lại. Vì vậy, bất kỳ con chip nào rơi vào doxa vẫn ở trên đó cho đến khi kết thúc trò chơi, mặc dù nó có thể được lật lại bao nhiêu lần tùy thích.

Để minh họa, hãy xem xét vị trí đối xứng trên hình 2. Bây giờ là nước đi của Đen và bằng cách đặt một quân chip lên hình vuông góc a8, họ ngay lập tức bao quanh 18 quân trắng theo ba hướng có thể. Các chip theo chiều dọc “a”, từ a2 đến a7, được bao quanh bởi các chip a1 và a8, các chip của cuối cùng

⟦folio 67⟧

---
running_head:
folio:
---

xếp hàng từ b8 đến g8, với các chip a8 và h8, và cuối cùng là các chip trên đường chéo lớn, từ b7 đến g2, với các chip a8 và h1. Ví dụ này là một kỷ lục - số lượng chip nhiều nhất có thể bắt được và lật trong một lần di chuyển là 18.

Nếu tại một thời điểm nào đó, một trong những người chơi không thể thực hiện một nước đi (không thể bao vây bất kỳ người không quay nào), thì anh ta sẽ vượt qua nước đi đó.

Nếu một trong những người chơi đã sử dụng hết chip của mình thì anh ta có thể lấy một con chip từ nguồn cung cấp của đối thủ. Tuy nhiên, trong bộ trò chơi, cả trắng và đen đều có thêm hai chip và điều này, theo quy luật, là đủ để bạn sử dụng chip của riêng mình.

Các nước đi của cả hai bên được tính theo chiều đảo ngược không phải theo tham số, như trong cờ vua, mà riêng biệt (trong một số trường hợp hiếm hoi, số lẻ tương ứng với nước đi đen, số chẵn tương ứng với nước đi trắng). Trước khi trò chơi bắt đầu, bốn ô trên bàn cờ đã bị chiếm giữ và do đó nó kéo dài không quá 60 nước đi. Trò chơi kết thúc khi không đối tác nào có thể thực hiện thêm nước đi nào khác, đặc biệt là nếu tất cả 64 ô trên bàn cờ đều đã đầy chip. Người chiến thắng là người có số lượng chip trên bảng lớn nhất vào thời điểm hiện tại, nếu hòa thì sẽ hòa (tất nhiên có tính đến mặt “nhìn thấy” của các chip trên bảng).

Quay lại hình 2, chúng tôi lưu ý rằng nước đi a8 của Đen là nước đi cuối cùng trong trò chơi - toàn bộ bàn cờ chứa đầy chip. Lật số bản ghi

Lo chip - 18, udom đen được cứu - trận đấu kết thúc với tỷ số hòa - 32:32!

Bây giờ chúng ta hãy xem xét, làm ví dụ, mười nước đi trong một trò chơi đảo ngược (năm nước cho mỗi bên).

1. c5. Màu đen đã bao quanh chip d5 màu trắng với các chip c5 và e5 của nó, và nó lật ngược với mặt đen hướng lên trên (để đơn giản, chúng ta sẽ nói nó đổi màu).

2. c6. Bây giờ nó lật lại và trở thành chip trắng d5.

3. d6. Chip d6 lại chuyển sang màu đen.

4. e6. Các miếng d6 và e5 bị bao quanh, cả hai đều lật lại và trở thành màu trắng.

5. f6. Chip e5 đổi màu từ trắng sang đen.

6. c4. Các quân c5, d4 và d5 có màu trắng.

7. b6. Một hàng chip - c6, d6, e6 - bị lật và tất cả đều chuyển sang màu đen.

8. e7. Các chip d6, e5 và e6 có màu trắng.

9. f3. Chip d5 và e4 có màu đen.

10. e3. Chip e4 có màu trắng.

Vị trí hiển thị tại hình 3 đã phát sinh. Trắng, người có chip lớn, có thế chủ động. Nhưng còn quá sớm để vui mừng: các tình huống đảo ngược thay đổi, giống như trong kính vạn hoa, các con tắc kè hoa thỉnh thoảng được “đổi màu” và điều quan trọng là chúng sẽ như thế nào khi kết thúc trò chơi.

Trong hầu hết các trò chơi, chẳng hạn như cờ vua và cờ đam, ưu thế về vật chất quyết định rõ ràng việc chuyển tổng thể và ngược lại, một người chơi có số lượng chip cùng màu đáng kể có thể, trong một nước đi.

⟦folio 68⟧

---
running_head:
folio:
---

mất tất cả các cuộc chinh phục (ví dụ: xem hình 2).

Rõ ràng, nếu tại một thời điểm nào đó một trong những người chơi đã “ăn hết chip” của mình, thì trò chơi sẽ ngay lập tức kết thúc với thất bại. Trận đấu ngắn nhất với kết quả như vậy ("chiếu tướng" cho đảo ngược) bao gồm chín nước đi: 1. c5 2. c4 3. e3 4. e6 5. e7 6. d3 7. c3 8. f5 9. g5!, và chỉ còn lại quân đen trên bàn cờ. Trận đấu kết thúc với chiến thắng của họ với tỷ số 13:0.

Chúng ta hãy xem xét một số yếu tố của các nguyên tắc của trò chơi. Vì quân địch nằm ở trung tâm bàn cờ dễ bị bắt hơn so với ở rìa, nên bạn phải luôn cố gắng chiếm lĩnh các khu vực cực đoan của bàn cờ và đánh bại kẻ thù trong việc này. Việc nắm bắt các trường góc đặc biệt có lợi. Những con chip rơi vào chúng không bao giờ có thể lật lại được (đơn giản là không có gì để bắt chúng) và giữ được màu sắc cá nhân của chúng cho đến khi kết thúc trò chơi. Người nào đột nhập vào một trong các góc của bàn cờ sẽ nhận được lợi thế nghiêm trọng, và nếu điều này xảy ra ở đầu trò chơi thì đó là người quyết định. Vì vậy, nhân tiện, sẽ rất nguy hiểm nếu đặt chip của bạn cạnh các ô góc, đặc biệt là trên b2, b7, g2, g7; đối thủ có thể thực hiện một pha phối hợp đơn giản và hưởng quả phạt góc. Đây là một ví dụ nổi bật minh họa sức mạnh của quân chip ở góc (hình 4).

Như thể đã đến lúc Trắng phải bỏ cuộc - họ chỉ có một quân trước 53 quân của đối thủ! Tuy nhiên, họ dễ dàng chiếm thế thượng phong, thậm chí với số điểm “khô khan”! Hãy để chúng tôi đưa ra một kết thúc có hiệu quả cho trò chơi này.

1. a2. Với nước đi của mình, Đen vẫn sẽ buộc phải bỏ lỡ. Bây giờ, chữ “a” dọc luôn có màu trắng (hiện tại ngoại trừ trường a1). Đen vẫn không có động thái nào, vì anh ta sẽ không thực hiện cho đến khi kết thúc trò chơi. 2. h8. Đường ngang cuối cùng được sơn màu trắng. 3. h7. 4. h6. 5. h5. 6. h4. 7. h3. 8. a1. 9. h2. 10. h1. Vì vậy, toàn bộ bến tàu chứa đầy chip trắng, 64:0!

Những người chơi có kinh nghiệm trong trận mở màn ở giữa bàn cờ - trong ô c3 - c6 - f6 - f3, cố gắng tránh để quân của đối phương chạm tới mép bàn cờ càng lâu càng tốt. Khi đó quân trắng và quân đen lần lượt chiếm giữ mép bàn cờ, bạn phải cẩn thận không để quân địch đi vào góc. Càng về cuối trò chơi, các lựa chọn càng ít đi và những người chơi có kỹ năng sẽ tính toán chúng gần như đến cùng. Bây giờ việc phạt góc không còn quá nguy hiểm nữa.

Có thể nói rằng trò chơi đảo ngược thu hút rất nhiều sự chú ý từ những người yêu thích các trò chơi khác; nhiều chương trình đã được tạo ra xứng đáng với sự tương tác của con người. Năm 1989, tại Thế vận hội máy tính đầu tiên ở London, đây là giải đấu đảo ngược quy tụ nhiều chương trình từ các quốc gia khác nhau nhất - 15.

Bây giờ chúng ta hãy trình bày cách sử dụng trò chơi có tính thuận nghịch giữa người (da đen) và máy tính (da trắng). Để thuận tiện, các số nước đi được đặt trực tiếp trên lề bảng.

Trên hình 5 và 16 nước đi đầu tiên được chỉ định và màu của các quân chip chỉ hiển thị chính xác ai - trắng hoặc đen - đã thực hiện nước đi với một số nhất định.

⟦folio 69⟧

---
running_head:
folio:
---

Kết quả là vị trí bạn nhìn thấy tại hình 5, $\sigma$ (để chắc chắn về điều này, tất nhiên bạn cần phải chơi trò chơi trên bảng).

Đầu tiên, người chơi chiếm toàn bộ tâm bàn cờ (12 nước đi, hình vuông $4 \times 4$), sau đó thêu trên cạnh của bàn cờ (màu đen ở nước đi thứ 15 và màu trắng ở nước đi thứ 16). Lúc này trận mở màn có thể coi như đã hoàn thành. Trò chơi giữa của trò chơi, nước đi 17-42 có thể được bắt nguồn từ hình 6. Ở đây màu của các quân chip được đánh số cũng tương ứng với trình tự các nước đi và màu của các quân cờ không được đánh số vẫn giữ nguyên như ở hình 5, $\sigma$.

Ngày càng có nhiều quân xuất hiện ở các cạnh bàn cờ nhưng các đối thủ vẫn không cho nhau tiếp cận các góc của bàn cờ. Vị trí sau 42 nước đi được hiển thị là hình 7, $a$ (vì vậy hãy loại bỏ các số khỏi tất cả các chip đã có trên bảng).

Máy tính hiện chiếm thế chủ động (25:21), nhưng về cuối trận, con người đã tạo ra được đòn tấn công quyết định (nước đi 43-60). Để làm điều này, anh ta đã sử dụng một thủ thuật - anh ta tách góc dưới bên trái (máy chiếm nó với nước đi 46), nhưng với nước đi 47, 49, anh ta xâm nhập vào góc bên phải liền kề và giành được khoảng trống đáng kể ở phần dưới của bàn cờ. Cơ hội được san bằng, nhưng ở nước đi thứ 50, máy tính mắc lỗi và Đen chiếm được một góc khác, góc trên bên phải. Sau nước đi thứ 53, Trắng không thể đặt quân mới lên bàn cờ và buộc phải bỏ qua nước đi, tiếp theo là nước đi thứ hai (các chip postou được đánh số 53, 54 và 55 trên hình 7, $a$ có màu đen). Sau một vài nước đi, ván đấu kết thúc với quân Đen giành chiến thắng với lợi thế tối thiểu là 33:31 (hình 7, $\sigma$).

Chúng ta hãy xem xét một số nguyên tắc chiến lược của trò chơi. Trong Middlegame, người chơi nên tạo ra những tình huống trên bàn cờ sao cho có những ô mà anh ta có thể đi tới nhưng đối thủ thì không. Bốn trường hợp chính có thể có nước Trắng ở mép bàn cờ - $A, B, B, \Gamma$ được hiển thị ở hình 8.

Nếu có quân hỗ trợ thứ hai ở giữa bàn cờ (tại hình các ô trung tâm được bảo vệ), Trắng luôn có thể đặt một quân lên một trong các ô này; đối với màu đen, chúng không thể tiếp cận được ở bất kỳ vị trí nào ở trung tâm. Rõ ràng, sự hiện diện của các ô “dự trữ” như vậy cho một trong các bên, trong trường hợp này là Trắng, là rất quan trọng; trong thuật ngữ cờ vua, điều này cho phép bạn thắng được nhịp độ.

Không nên cho rằng điều quan trọng nhất trong đảo ngược là tính toán các phương án từ xa. Thông thường, các tình huống nảy sinh trong đó cuộc đấu tranh mang tính chất cục bộ, chỉ ảnh hưởng đến một số bộ phận của hội đồng quản trị. Hãy nhìn vào hình 9.

Trắng mở màn kém và Đen, bằng cách đặt một quân chip vào ô $A$, sẽ có được một ô dự trữ. Họ nên tránh chiếm ô $B$ càng nhiều càng tốt, và nếu đến một thời điểm nào đó Trắng chiếm được thì Đen sẽ có một ô mới $\Gamma$, trên đó anh ta có thể di chuyển, nhưng kẻ địch thì không.

Bây giờ giả sử Đen chiếm ô $B$ ở nước đi đầu tiên. Trong đáp số Trắng có thể phản ứng với sai lầm này

⟦folio 70⟧

---
running_head:
folio:
---

kết hợp một sự kết hợp đơn giản. Trắng - A, đen - G, trắng - B, và bây giờ đến lượt Đen di chuyển (hiện tại chúng tôi không quan tâm đến vị trí của các quân chip ở nửa trên của bàn cờ, nhưng người ta cho rằng có một quân trắng ở b4). Vì chiếm ô g7 là tự sát nên Đen buộc phải chuyển sang phần khác của bàn cờ.

Để hiểu ý tưởng về cách điều động tổ hợp của Trắng, chúng ta nên xem xét một số nguyên tắc chung của trò chơi. Trong bất kỳ tình huống nào trên bàn cờ, người chơi đều có nhiều nước đi tích cực và nhiều nước đi trung lập. Mục tiêu của đối thủ là buộc anh ta phải sử dụng mọi chiêu thức trung lập và cuối cùng khiến anh ta bị hạ gục. Thông điệp tiêu chuẩn là chuyển thứ tự lượt. Tình thế cục bộ diễn ra để cuối cùng là nước đi của địch. Số nguyên tố này được sử dụng trong hoạt động trên hình 9. Sau hành động thiếu chính xác và đúng đắn của Đen trên mặt đất, họ buộc phải di chuyển ra ngoài góc dưới bên phải.

Biết các vị trí tiêu chuẩn trên các cạnh (hình 8) - điều gì cần phấn đấu và điều gì cần tránh, bạn có thể dự đoán kết quả của trò chơi ở nước đi thứ 30. Cách chơi chính xác của “bên” bàn cờ cũng tương tự như cách chơi theo vị trí trong cờ vua. Tạo một ô dự trữ có thể được so sánh với việc sở hữu một đường mở hoặc tạo một con tốt đã qua... Tất nhiên, trong đảo ngược, như trong cờ vua, lợi thế về vị trí và đặc biệt là lợi thế về vật chất (vai trò của nó ở đây rất nhỏ), không đảm bảo chiến thắng, mặc dù nó làm tăng xác suất.

Các nguyên tắc chiến lược khác đã được xây dựng và áp dụng ở một số quy định nhất định.

Như với bất kỳ trò chơi nào, kết quả là có một số bài toán và sự kết hợp thú vị. Hãy để chúng tôi trình bày một bài toán độc đáo (trong ngôn ngữ cờ vua - etod), do một trong những tác giả O. Stepanov đề xuất. Ở hình 10 Trắng bắt đầu và thắng.

Viên ngọc này được giải bằng 1. e2! Hãy xem cách chúng ta xếp chồng lên nhau tiếp theo. Các chip đen d3 và e3 - e5 bị lật, chỉ còn các chip d4 và d5 là “sống”. Làm sao để chơi đen bây giờ? Sau nước đi d2 hoặc d7 và theo đó, đáp số d1 hoặc d8, như chúng ta thấy, trên bảng chỉ còn một quân trắng - trò chơi kết thúc. Trong trường hợp một trong các nước đi b7, b5, b4, b3, f2, f4, f5, f7 và các nước đi tương ứng đáp số a8, a5, a4, a2, g1, g4, g5, g8, Đen còn lại một quân duy nhất, bị bao vây theo mọi hướng, và với nước đi tiếp theo, Trắng kết thúc ván đấu với sự tiêu diệt hoàn toàn các lực lượng không cướp được.

Vì vậy, Đen buộc phải có đáp số g7, nhường một góc bàn cờ. Ví dụ: màu trắng chơi f5 (một quân trắng xuất hiện trên e5) với h8 không thể tránh khỏi. Kết quả là giành được góc dưới bên phải, tương đương với chiến thắng ở bàn đầu trận.

Có thể đây là vị trí duy nhất (tính đến biểu tượng) có hàng trăm vật chất gần bằng nhau, có thể lập luận rằng một trong các bên bắt đầu giành chiến thắng!

E. Gik, O. Stepanov
