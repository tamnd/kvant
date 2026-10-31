---
id: 2016-2-panov-spasyom-vodolaza-93e1597e
issue: kvant_2016_2
year: 2016
number: "2"
title: Hãy cứu thợ lặn
authors:
  - Панов А. А.
rubric: laboratoriya-kvanta
rubric_sub: Лаборатория «Кванта»
page_first: 43
page_last: 45
page_labels: 41-43
tag: IMEB
lang: vi
source: kvant_digital
extraction: native
content_sha256: 8c405ed9878e44948f9e7bb0462258b9c96184c430f36b53392b7011010ec3da
prompt_sha256: draft-1
translated_from: content/ru/2016/02/articles/04_panov-spasyom-vodolaza-93e1597e.md
source_content_sha256: 0ca8abfe9371c10aee9d2a3c9e46fb78e70ed61dd6537c5bd535a842da7d5c5f
translation_model: draft
translation_run: vi-draft-2026-10-31
translation_quality: draft
---

⟦folio 41⟧

PHÒNG THÍ NGHIỆM

Hãy thực hiện điều này cho tất cả các ô tương ứng với các số ở cột bên trái và gạch bỏ các hàng được đánh dấu (tất cả chúng sẽ khác nhau, vì mỗi ô chỉ được chọn chính xác một ô). Vì chúng ta sẽ không gạch bỏ mọi thứ nên chúng ta sẽ chỉ còn lại một “bảng” gồm 8 hàng - chẳng hạn như k cột và 8 - k hàng. Khi đó diện tích của nó bằng k ◊ (8 - k), không lớn hơn 16. Điều này có nghĩa là tổng số ô được chọn không quá 16 + 8 = 24. Một mâu thuẫn. 2 (lời giải 6, biến thể lời giải 5). Đầu tiên chúng ta đánh dấu tùy ý 32 ô, được đánh số bằng các số khác nhau. Chúng tôi sẽ gọi các ô không được chọn là “miễn phí” và các dòng (hàng hoặc cột) trong đó tất cả các ô đều trống - trống. Giả sử rằng một số dòng, ví dụ như dòng đầu tiên, trống. Do đó, trong đó có 8 số khác nhau và 8 ô có số tương ứng được đánh dấu ở dòng khác. Chúng tôi lập luận rằng một trong 8 số này không phải là duy nhất trong hàng hoặc trong cột của nó và do đó nó có thể được thay thế bằng một số bằng nhau ở hàng đầu tiên mà không cần “loại bỏ” các hàng hoặc cột khác, tức là giảm số lượng dòng trống. Trên thực tế, trên toàn bộ bàn cờ, ngoại trừ hàng đầu tiên, chỉ có 24 ô vuông trống. Do đó, không có quá ba hàng trong đó một trong 8 số đứng “một mình” và không quá bốn cột như vậy. Do đó, không quá bảy số nằm trong hàng hoặc cột của chúng và ít nhất một trong 8 số của chúng tôi thực sự có thể được thay thế. Nếu sau đó vẫn còn hàng hoặc cột trống, hãy tiến hành theo cách tương tự.

3 (lời giải 7). Có $2^{32}$ lựa chọn trong số 32 ô có số khác nhau trên đó (từ mỗi cặp ô được đánh số giống nhau, bạn phải chọn một ô). Hãy ước tính số lượng các lựa chọn xấu. Không có số nào được chọn trong cột đầu tiên. Điều này có nghĩa là tất cả các số trong đó đều khác nhau, nên có $2^{24}$ lựa chọn như vậy. Tổng cộng có 16 hàng nên tổng số lựa chọn sai không quá 16 ◊ $2^{24} = 2^{28} < 2^{32}$, tức là có nhiều lựa chọn tốt.

tái bút Hãy thử thay đổi một chút tình trạng của bài toán ban đầu. Bây giờ chúng ta có 16 số được viết trong 64 ô, mỗi số 4 lần. Câu hỏi được đặt ra: “Bây giờ có thể đảm bảo đánh dấu mỗi ô bằng mỗi số sao cho theo từng hàng ngang và trong mỗi số?”

"QUANTA"

⟦column⟧

có ít nhất một ô được đánh dấu trên mỗi hàng dọc không?” Và nếu có thể, lời giải nào của chúng tôi nằm trong bài toán mới? Hóa ra sự thật này cũng sẽ đúng. Ví dụ: lời giải hiển nhiên xuất hiện, tương tự như lời giải 3. Mỗi số cô gái sẽ có lũy thừa là 8, vì nó xuất hiện 4 lần và được tính mỗi lần thành 2 hàng, trong khi có thể chúng ta đã tính đến tình bạn nào đó tới 4 lần nếu con số đó rơi bốn lần liên tiếp. Từ định lý Hall suy ra rằng chúng ta có 16 đám cưới cần thiết. Mọi thứ hóa ra lại đơn giản và đẹp đẽ biết bao! Và nếu bạn nghĩ đến giải pháp 2 thì... Euler vĩ đại sẽ xuất hiện ở đây! Trong biểu đồ của chúng tôi, mọi đỉnh hiện có bậc 4, có thể có nhiều cạnh và vòng lặp. Khi đó, mỗi thành phần liên thông sẽ chỉ bao gồm các đỉnh bậc chẵn, có nghĩa là tiêu chuẩn Euler được thỏa mãn - mỗi thành phần liên thông sẽ có một chu trình Euler, tức là một chu trình đi qua tất cả các cạnh một lần, với mỗi đỉnh trong chu trình xuất hiện hai lần và mỗi chu trình Euler có độ dài chẵn. Điều này có nghĩa là trong mỗi chu trình Euler này, có thể tô màu các cạnh theo kiểu bàn cờ (trắng, đen, trắng, đen, v.v.). Kết quả là, chẳng hạn, trong đồ thị các cạnh đen, mỗi đỉnh sẽ có bậc 2, và ở đây bổ đề nhảy tròn sẽ hoạt động, theo đó đồ thị các cạnh đen được chia thành một hoặc nhiều chu trình rời nhau, trong đó, bằng cách tương tự với giải pháp 2, chúng ta sẽ sắp xếp đường truyền mà chúng ta cần. Vì vậy, chúng tôi đã chứng minh một thực tế mạnh mẽ hơn là trong mỗi hàng sẽ có ít nhất 2 ô được đánh dấu. Thật hữu ích biết bao khi thay đổi điều kiện bài toán! Những ý tưởng hay ho khác sẽ ngay lập tức xuất hiện!

PHÒNG THÍ NGHIỆM "QUANTA"

Hãy cứu thợ lặn

A.PANOV

NHIỀU NĂM ĐÃ trôi qua kể từ khi xuất bản bài viết “K thợ lặn nghệ thuật – thế hệ P” (xem «Kvant»

số 2 cho năm 2012). Trong thời gian này, tôi đã học được một số điều mới mà tôi muốn chia sẻ ở đây. Và tôi cũng muốn sửa một lỗi lầm. Hóa ra người phát minh ra thợ lặn Descartes hoàn toàn không phải là Descartes, mà rất có thể là nhà sư người Ý Raffaello Magiotti (Raffaello Magiotti, 1597–1656), một tín đồ của Galileo và là bạn của Torricelli. Năm 1648, Maggiotti xuất bản một luận thuyết về tính không nén được của nước; ông đã sử dụng thợ lặn để minh họa tính không thể nén được này. Hãy nhìn vào hình 1 (cũng như trên trang thứ 4 của trang bìa), nơi tái hiện hình của tác giả Maggiotti - bạn chắc chắn sẽ nhận ra hai thợ lặn ở đó.

“Le caraffine di Magiotti” là tên của văn bản được viết bởi Beniamino Danese và nằm trên trang web http://www.reinventore.it/. Từ tiếng Ý, tên này được dịch rất đơn giản - “Chai (hoặc bình) của Maggiotti.” Ngoài ra, trang web còn có một video dài 12 phút (khung hình từ video đó được hiển thị trên hình 2). Tôi đã xem nó nhiều lần với niềm vui lớn và tôi khuyên mọi người nên làm như vậy. Mặc dù lần trước tôi đã khuyên bạn nên sử dụng pipet thông thường khi lặn, nhưng sau khi xem phim, tôi quyết định quay trở lại với chai bào chế thủy tinh cổ điển. Vì vậy, chúng ta hãy đổ đầy nước vào một chai nhựa, và sau đó... ...Cái chai chứa đầy một phần nước sẽ được úp ngược vào trong chai. Trong trường hợp này, lượng nước trong chai phải được điều chỉnh sao cho chai có độ nổi dương nhẹ - với một lực đẩy yếu, chai sẽ chìm dưới nước. Bây giờ chúng ta vặn nút chặt hơn và thợ lặn đã sẵn sàng hành động. Khi bạn ấn vào chai nhựa, thể tích không khí bên trong chai giảm đi và chai hạ xuống -

⟦folio 42⟧

KVANT 2016/№2

⟦column⟧

⟦figure⟧

Hình 2. Cảnh trong phim của Beniamino Danese

⟦figure⟧

Hình 1. Chai Maggiotti

đang đi xuống. Buông chai - người thợ lặn nổi lên... Đây thực ra là một trích dẫn nhỏ từ bài viết trước. Bây giờ chúng ta hãy thực hiện một số thí nghiệm mới.

Chúng tôi sẽ giải cứu thợ lặn. Có thể thật xấu hổ khi một thợ lặn vừa hạ xuống một cái chai lại lập tức chạm đáy. Bạn phải đổ hết nước trong chai, đưa thợ lặn ra ngoài và chuẩn bị lại cho anh ta. Chúng ta hãy cố gắng làm mà không cần điều này - cứu người thợ lặn và buộc anh ta phải tự mình leo lên. Điều này có thể được thực hiện theo nhiều cách. Cách 1: hâm nóng lại. Giả sử một thợ lặn thấy mình ở dưới đáy và không muốn ngoi lên. Mở nắp và đặt chai có thợ lặn vào nước nóng. Nước trong chai sẽ ấm lên, thể tích không khí trong chai sẽ tăng lên và người thợ lặn sẽ nổi lên mặt nước. Đúng là khi nước nguội, người thợ lặn sẽ lại chết đuối. Cách 2: hít vào. Hãy thử làm điều gì đó như hô hấp nhân tạo. Hãy ngậm chặt môi quanh cổ chai và hít một ít không khí chứa trong đó. Áp suất trong chai sẽ giảm, thể tích không khí trong chai lại tăng lên và người thợ lặn sẽ nổi lên mặt nước. Nhưng ngay cả ở đây, ngay khi chúng ta rời miệng khỏi chai, người thợ lặn sẽ chết đuối. Cách 3: nâng cao. Khi được tặng một chiếc phong vũ biểu lần đầu tiên, tôi lập tức leo vào thang máy và đi lên tầng trên cùng. Tất nhiên, kim phong vũ biểu cho thấy áp suất không khí giảm theo độ cao. Hãy tận dụng thực tế này và đưa người thợ lặn chết đuối trong chiếc chai đã mở cùng chúng ta vào thang máy. Nếu bạn tăng đủ cao, áp suất không khí sẽ giảm đáng kể, không khí bên trong chai sẽ giãn nở đến mức người thợ lặn sẽ có được lực nổi dương và bay lên trên. Cách 4: bóp. Hãy để người thợ lặn thấy mình ở dưới đáy và không muốn ngoi lên. Mở nắp và bóp chai bằng một tay để không khí thoát ra nhiều hơn. Không giảm lực nén, vặn phích cắm bằng tay kia. Sau khi chúng ta buông cái chai ra, các lực đàn hồi sẽ bắt đầu tác dụng, cố gắng đưa nó trở lại hình dạng trước đó. Chúng chống lại áp suất không khí bên ngoài và làm tăng thể tích của chai, bao gồm cả thể tích không khí trong chai. Thợ lặn có được sức nổi tích cực, nổi lên và sẵn sàng làm việc.

Một? Hai? Ba! Tại sao đôi khi có trường hợp cái chai nổi trong cốc, còn nếu ném nó vào trong chai thì nó lại chìm? Bởi vì bạn không cần phải ném nó mà hãy cẩn thận và từ từ hạ nó xuống chai, khi đó nó sẽ nổi lên trên cùng giống như trong ly. Nhưng bản thân việc chết đuối cũng khá thú vị. Không phải thợ lặn nào nổi trên đỉnh cũng sẽ chết đuối nếu bị đẩy xuống. Điều này chỉ có thể thực hiện được nếu nó có độ nổi dương thấp. Thực tế là khi một thợ lặn đi xuống, áp suất thủy tĩnh của chất lỏng lên anh ta tăng lên, thể tích không khí bên trong chai giảm và độ nổi của thợ lặn cũng giảm. Và nếu chai đủ cao thì đến một độ cao nhất định lực nổi sẽ trở nên âm và người thợ lặn sẽ tự chìm. Hóa ra một thợ lặn được điều chỉnh tốt với độ nổi dương thấp có hai vị trí cân bằng ổn định bên trong chai. Một khi người thợ lặn ở vị trí trên cùng, và một khi anh ta đứng yên ở phía dưới. Nếu anh ta ở một trong những trạng thái này, thì sau một chút xáo trộn nhỏ, anh ta sẽ quay lại đó. Hơn nữa, ở vị trí phía trên độ nổi của nó là dương, ở vị trí phía dưới là âm. Nhưng sau đó hóa ra là ở một độ cao trung gian nào đó lực nổi của thợ lặn phải bằng không. Và đây là một vị trí cân bằng khác cho thợ lặn. Chỉ có điều, không giống như hai cái đầu tiên, nó không ổn định. Nếu người lặn di chuyển lên trên một chút từ vị trí này, anh ta sẽ có lực nổi dương và sẽ tiếp tục tăng tốc đi lên. Nếu nó hơi lệch xuống dưới, nó sẽ phát triển lực nổi âm và sẽ chìm.

⟦folio 43⟧

PHÒNG THÍ NGHIỆM

⟦figure⟧

Hình 3. Nhấn theo cách này (như hình bên trái) và thợ lặn sẽ chết đuối, nhấn theo cách khác (như hình bên phải) - anh ta nổi lên

⟦figure⟧

Hình 4. Chúng ta nén nó theo cách này (như bên trái) và diện tích mặt cắt ngang giảm đi; chúng tôi nén nó theo cách khác (như bên phải) – nó tăng lên

Thợ lặn hành động kép. Sẽ thật tuyệt nếu có một thợ lặn, theo yêu cầu của chúng tôi, sẽ chìm xuống đáy và ở đó hoặc nếu muốn, sẽ nổi lên trên và bơi ở đó. Dưới đây là một số cách để đạt được điều này. 1: vặn/tháo vít. Hãy đặt một thợ lặn có độ nổi dương thấp vào trong chai. Hãy bắt đầu vặn phích cắm. Kết nối của nó với chai sẽ trở nên kín khí ngay cả trước khi nắp được vặn hoàn toàn. Từ thời điểm này cho đến khi nút chai được vặn hoàn toàn, thể tích chứa bên trong chai sẽ bắt đầu giảm. Thể tích không khí bên trong người thợ lặn cũng sẽ giảm và người thợ lặn sẽ chết đuối. Rút phích cắm và thợ lặn sẽ nổi lên. Đây là ví dụ đầu tiên về thợ lặn hành động kép. 2: bóp và bóp. Có những chai có tiết diện hình bầu dục (hình3). Nếu bạn cắt một cái chai như vậy bằng một mặt phẳng nằm ngang, thì mặt cắt ngang sẽ giống như hình minh họa ở hình 4. Hãy đặt một thợ lặn có độ nổi dương thấp và hai trạng thái cân bằng ổn định vào một cái chai như vậy. Nếu bạn ấn vào các cạnh phẳng của chai (xem hình 3 và 4, bên trái), diện tích mặt cắt của nó sẽ giảm, nghĩa là thể tích sẽ giảm và thợ lặn sẽ chìm xuống đáy. Nếu bây giờ bạn nhấn vào các cạnh tròn (xem hình 3 và 4, bên phải), âm lượng sẽ tăng lên và người lặn sẽ nổi lên mặt nước. 3: đặt vào kẹp. Lấy một chiếc kẹp giun có đường kính lớn có thể gắn vào chai nhựa (hình5). Hãy đặt một dụng cụ lặn có độ nổi dương vào chai, vặn chặt nắp và dùng tuốc nơ vít để bắt đầu siết chặt kẹp. Áp suất không khí bên trong chai sẽ tăng lên và đến một lúc nào đó người thợ lặn sẽ chìm xuống đáy. Và quá trình này có thể đảo ngược. Nếu bạn nới lỏng kẹp, thợ lặn sẽ vươn lên dẫn đầu.

"QUANTA"

⟦column⟧

⟦figure⟧

Hình 5. Chai có kẹp, rất thuận tiện cho thợ lặn điều khiển

4: hãy gõ cửa. Bất cứ ai đã cố gắng tạo ra một thợ lặn có độ nổi dương tối thiểu, có hai trạng thái cân bằng ổn định - ở trên cùng và dưới cùng của chai, đều biết rằng đây là một bài toán khó. Điều này đòi hỏi phải tinh chỉnh sơ bộ tỷ lệ nước và không khí bên trong thợ lặn. Việc sử dụng kẹp truyền động sâu giúp đơn giản hóa vấn đề này. Hãy đặt một thợ lặn có độ nổi tích cực vào trong chai và vặn chặt nắp. Bây giờ chúng ta sẽ từ từ bắt đầu siết chặt chiếc kẹp cho đến khi vị trí phía dưới của thợ lặn “lần đầu tiên” trở nên ổn định. Một thợ lặn như vậy sẽ có hai trạng thái ổn định - trên và dưới, và giữa chúng (ở độ cao thấp) sẽ có trạng thái cân bằng không ổn định. Bằng cách bóp chai, chúng ta sẽ hạ thợ lặn xuống đáy. Nếu bây giờ bạn chạm đáy chai trên bàn, người lặn sẽ nhảy lên, giống như trên tấm bạt lò xo, vượt lên trên vị trí cân bằng không ổn định, sau đó anh ta sẽ có được lực nổi dương và vươn lên dẫn đầu. Đây là một thợ lặn hành động kép khác dành cho bạn. Thay vì đập chai xuống bàn, bạn có thể dùng nắm đấm đập vào bàn - hiệu quả sẽ như nhau. 5: hãy nâng nó lên. Tất nhiên, việc đập tay xuống bàn là quá khắc nghiệt. Hãy hành động tinh tế hơn. Như trong trường hợp trước, hãy tạo một thợ lặn có ba vị trí cân bằng. Bóp chai sẽ đưa thợ lặn xuống đáy. Bây giờ chúng ta hãy lấy nút chai và nhấc cái chai lên - người thợ lặn sẽ nổi lên mặt nước. Hóa ra lực hấp dẫn, không được bù đắp bởi phản lực của bàn, làm tăng thể tích của cái chai tròn cao và áp suất không khí trong đó giảm xuống. 6: nghiêng. Hãy tạo lại một thợ lặn với ba vị trí cân bằng và hạ anh ta xuống phía dưới. Nó sẽ ở đó trong trạng thái cân bằng ổn định. Chúng tôi nghiêng mạnh chai để chiều cao của cột nước phía trên người thợ lặn giảm đi đáng kể. Ở cấp độ của thợ lặn, áp suất nước sẽ giảm, không khí trong đó sẽ giãn ra và bắt đầu dâng lên. Tại một thời điểm nào đó, chúng ta đặt cái chai theo chiều dọc và người thợ lặn sẽ ở trên cùng. Đó có lẽ là tất cả. Tôi cũng nói thêm rằng học trò của tôi Dima Gulyev đã dạy tôi cách trang bị một chiếc kẹp giun cho thợ lặn. Tôi nghĩ đây là một ý tưởng rất tốt.
