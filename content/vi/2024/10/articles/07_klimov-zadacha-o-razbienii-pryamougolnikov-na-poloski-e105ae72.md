---
id: 2024-10-klimov-zadacha-o-razbienii-pryamougolnikov-na-poloski-e105ae72
issue: kvant_2024_10
year: 2024
number: "10"
title: Bài toán về việc chia hình chữ nhật thành dải
authors:
  - Климов А. В.
rubric: raznoe
rubric_sub: Разное
page_first: 25
page_last: 26
page_labels: "24"
tag: OYKE
lang: vi
source: kvant_digital
extraction: native
content_sha256: ca0312465b08e35f40fdb8031d71e2ec736cabf071ff15ba8c43465aee6ab28f
prompt_sha256: draft-1
translated_from: content/ru/2024/10/articles/07_klimov-zadacha-o-razbienii-pryamougolnikov-na-poloski-e105ae72.md
source_content_sha256: ba1fee8df3caf4d8fd87656c7257917ca4b2840abca9135d4f078b06742e351d
translation_model: draft
translation_run: vi-draft-2026-10-31
translation_quality: draft
---

⟦folio none⟧

VẤN ĐỀ LỊCH SỬ

Bài toán về việc chia hình chữ nhật thành các dải

A. KLIMOV

TẠI Olympic TOÁN HỌC MOSCOW 1974, bài toán sau đây đã được đề xuất ở hai lớp cuối cấp. Một tờ giấy hình chữ nhật có cạnh 1 cm được cắt thành các dải hình chữ nhật, mỗi dải có cạnh 1 cm. Các đường cắt song song với các cạnh của tờ giấy gốc. Chứng minh rằng ít nhất một trong $чисел^{a} или^{b}$ là số nguyên. Lịch sử xuất hiện của nó rất thú vị. Đầu tiên, chúng ta hãy lạc đề ngắn gọn về hoàn cảnh cuộc sống trong những năm đó. Vào thời điểm đó, nhiều tòa nhà cũ đã bị phá bỏ ở Moscow, nơi có rất nhiều giá trị về mặt nghệ thuật. Kolya $Константинова^{1}$ (nổi tiếng trong giới Olympic) có một người bạn (thậm chí giống như bạn cùng lớp) - nghệ sĩ Vitya Galkin. Anh bị ám ảnh bởi ý tưởng cứu vãn và bảo tồn những gì có giá trị trong những ngôi nhà bị phá hủy này. Đây không chỉ là những đồ vật (như đèn hoặc ấm đun nước), mà còn là các bộ phận của đồ nội thất và bản thân các tòa nhà - tay cầm, lan can, bệ cửa sổ, tấm ốp và nhiều thứ khác. Kolya đã giúp đỡ anh ấy, truyền cảm hứng cho chúng tôi, những sinh viên, tham gia vào việc này. Khi biết rằng trong một hoặc hai ngày nữa, một ngôi nhà tuyệt vời nào đó sẽ bị phá hủy, chúng tôi sẽ đến đó, đôi khi vào ban đêm, để mọi thứ còn giá trị có thể được tháo ra, xé ra, xé ra và chất lên ô tô. Viti có một ngôi nhà khá lớn ở làng Gryzlovo, nằm gần sông Lopasnya. Chúng tôi đã cất giữ “của cải” của mình trong ngôi nhà này. Sau đó chúng tôi giúp anh ấy sắp xếp mọi thứ và sắp xếp chúng theo thứ tự.

1 Nikolai Nikolaevich Konstantinov – cao-

một nhà tổ chức tài năng của giáo dục toán học. Đọc cuộc phỏng vấn với anh ấy ở «Kvant» số 1 năm 2010.

⟦column⟧

Và rồi một ngày tôi phải xử lý một đống gạch vuông nhỏ có cùng kích thước, khoảng 2 x 2 cm. Cần phải đóng gói chúng chặt chẽ hơn trong một hộp gỗ với kích thước tất nhiên không phải bằng bội số của cạnh của viên gạch. Hơn nữa, gạch có độ dày rất khác nhau - từ 3 đến 8 mm. Vì vậy, tôi quyết định đặt chúng ở cạnh trong một lớp, để sau này tôi có thể đặt lớp thứ hai lên chúng, v.v. Hoàn thành lớp này, tôi thấy còn lại một mảnh chưa lấp đầy và một khu vực như vậy sẽ có thêm 1-2 viên gạch nữa. Tôi bắt đầu cố gắng thay đổi hướng của các ô, nhưng tất cả đều vô ích. Tôi đã phải để lại một khoảng trống. Và chỉ ngày hôm sau, khi đã ở Moscow, tôi mới nhận ra rằng có một sự thật toán học nào đó ẩn chứa trong điều này. Đây là cách bài toán ở trên xuất hiện. Hơn nữa, tất nhiên, tôi cũng quan tâm đến diện tích tối thiểu của phần dư cho a và b không nguyên. Một Thế vận hội khác sắp diễn ra và đây sẽ là một bài toán tốt cho cô ấy. Tuy nhiên, phải mất một thời gian dài mới giải quyết được bài toán. Cuối cùng họ tìm thấy lời giải, khá phức tạp, theo đó họ đồng ý chấp nhận cô ấy. Tôi đã hy vọng rằng một trong những người tham gia có thể tìm thấy một lời giải đơn giản hơn. Nhưng sự mong đợi này đã không thành hiện thực. Bài toán được đưa ra cho hai lớp cao cấp, 9 và 10. Và theo như tôi nhớ, chỉ có 2 hoặc 3 tác phẩm trong đó có thể, với một khoảng thời gian dài, để phân biệt nguyên mẫu của một bằng chứng khả thi. Trong một trong những tác phẩm này - được viết bởi Andrei Korobov từ lớp 10 của trường toán thứ 179 - có một bản phác thảo chứng minh cho trường hợp cả hai mặt của tờ giấy đều là số hữu tỉ, tức là chính xác là bội số của 1 n đối với một số nguyên n. Kích thước của các dải cũng được cho là hợp lý. Người ta cũng giả định rằng tất cả các vết cắt đều tuân theo các đường lưới với bước 1 n. Các ô được vẽ trên các đường chéo được vẽ trong hình chữ nhật ban đầu với một bước gồm n ô (tức là 1 cm). Hóa ra là trong mỗi dải cơ bản có kích thước 1 ô ô có chính xác 1 ô được tô bóng ở bất kỳ vị trí hoặc hướng nào. Do đó, mỗi dải có kích thước m u n (ô) chứa chính xác m ô màu, tức là số lượng của chúng tỷ lệ thuận với tổng số ô trong đó mn. Bây giờ vẫn phải đảm bảo rằng nếu cả hai mặt của trang gốc không chia hết cho n (theo nghĩa là số ô),

⟦folio 24⟧

KV A NT 2024/No. 10

thì đối với diện tích của toàn bộ tấm, tỷ lệ này không được quan sát. Tất cả những gì còn lại đối với tôi bây giờ là đi đến giới hạn ở n o f và đạt được cấp độ sơ cấp sau (tức là trường học, không có vô cực) lời giải cho $любых^{a} и^{b.}$ Chúng ta sẽ giải bài toán trong một bối cảnh rộng hơn. Xét bất kỳ lớp phủ không hoàn chỉnh nào của tấm a ub không chồng lên nhau bằng các dải hình chữ nhật có chiều rộng 1 có các cạnh song song với các cạnh của tấm, ta chứng minh rằng $если^{a} и^{b}$ đều không phải là toàn bộ thì sẽ luôn có phần không được che phủ của tấm. Chúng tôi cũng sẽ cố gắng ước tính từ bên dưới kích thước của phần còn lại tùy thuộc vào $от^{a} и^{b.}$ Chúng tôi sẽ vẽ trên tờ giấy gốc một loạt các đường chéo (ở 45q sang một bên) các đường thẳng cùng hướng (các đường màu xanh lam trong hình), cách nhau 1 cm

^a ` ^ b ` nhỏ hơn (hoặc bằng) 1 thì không

⟦column⟧

nó không chứa đoạn cát tuyến, vì góc của tờ giấy nằm bên dưới đường chéo của hình vuông đơn vị bù (được biểu thị bằng đường chấm). Kết quả là, tất cả các cát tuyến đều được bao phủ bởi các dải cắt, có nghĩa là tổng diện tích của chúng bằng L. Và ngay cả trong trường hợp này, một phần diện tích ^ a `  ^ b ` vẫn chưa được che phủ, thì với bất kỳ lớp phủ nào khác sẽ không ít hơn. Hơn nữa, nếu ^a ` ^ b `! 1, thì độ dài hình chiếu của cát tuyến trong hình chữ nhật này sẽ là ^ a ` ^ b ` 1, ​​​​vì vậy diện tích còn lại cho bất kỳ vùng phủ sóng nào sẽ ít nhất

^ a `  ^ b ` ^ a ` ^ b ` 1

1 ^ a `  1 ^ b `! 0.

Vì vậy, chúng tôi đã tìm thấy giới hạn dưới của diện tích phần không được che phủ của tấm:

min ^ a `  ^ b `, 1 ^ a `  1 ^ b `.

theo chiều dọc và chiều ngang. Chúng ta sẽ gọi chúng là secant. Mỗi dải có kích thước 1 ul bao gồm các đoạn cát tuyến có tổng chiều dài l 2 hoặc $просто^{l,}$ nếu chúng ta đo độ dài của các đoạn bằng hình chiếu của chúng lên $сторону^{l.}$ Do đó, “độ dài” có điều kiện này bằng diện tích của dải. (Thật vậy, những hình chiếu này bao phủ chính xác $сторону^{l}$ mà không trùng nhau.) Gọi L là tổng “độ dài” của tất cả các cát tuyến trên trang tính. Đối với bất kỳ lớp phủ nào, tổng diện tích của các dải không được lớn hơn L. Để một trong các đường cắt đi qua góc dưới bên trái của tấm, như trong hình. Hãy xem xét việc cắt và phủ tham khảo sau đây. Cắt toàn bộ (từ mép này sang mép khác) các dải có chiều rộng 1 ở bên trái đến mức tối đa, sau đó cắt các dải ngắn có chiều cao 1 từ dưới lên, như trong hình. Chúng bao phủ toàn bộ trang tính ngoại trừ một hình chữ nhật nhỏ ở trên cùng bên phải có kích thước ^a ` u ^ b `. Ở đây ^ x ` là phần phân số của $числа^{x.}$ Nếu tổng các cạnh của hình chữ nhật này

Con số này rõ ràng lớn hơn $0, когда^{a} и^{b}$ cả hai đều không phải là số nguyên. Hơn nữa, khi ^a ` ^ b ` 1, đối số đầu tiên của giá trị tối thiểu là tối thiểu và ngược lại. Câu hỏi đặt ra là liệu giới hạn dưới thu được có đạt được ở mức ^ a ` ^ b ` hay không! 1? Nếu một trong các cạnh của tấm nhỏ hơn 1 thì chỉ có thể cắt dải có chiều rộng 1 ở mặt còn lại (nếu nó lớn hơn 1), và do đó phần còn lại sẽ luôn là ^ a `  ^ b `. Nhưng nếu cả hai vế đều lớn hơn 1 thì có thể chạm tới giới hạn 1 ^ a `  1 ^ b `. Chúng tôi để người đọc tự tìm cách cắt tương ứng (ví dụ: khi 1 a, b 2 và a b! 3 ).
