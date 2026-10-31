---
id: 2017-5-kanunnikov-algebra-i-geometriya-kompleksnyih-chisel-83900e56
issue: kvant_2017_5
year: 2017
number: "5"
title: Đại số và hình học của số phức
authors:
  - Канунников А. Л.
rubric: shkola-v-kvante
rubric_sub: Школа в «Кванте»
page_first: 30
page_last: 34
tag: QA6M
lang: vi
source: kvant_digital
extraction: native
content_sha256: fa4c16d85b4663e0af2fcafe9607520270443acb2e5261ab92b754f2d19cea9d
prompt_sha256: draft-1
translated_from: content/ru/2017/05/articles/04_kanunnikov-algebra-i-geometriya-kompleksnyih-chisel-83900e56.md
source_content_sha256: 127f727af035f172a0849cc3ed9d9bcee0a1c6e16a3c937555320534cc71c4c5
translation_model: draft
translation_run: vi-draft-2026-10-31
translation_quality: draft
---

⟦folio none⟧

TRƯỜNG KVANT

Đại số và hình học của số phức

A.KANUNIKOV

Chúng tôi khuyên bạn nên đọc bài viết này sau bài viết “Sự kỳ diệu của số phức” (tr. 5) hoặc song song với nó. Các sơ đồ của bài viết đó thường tuân theo cùng một kịch bản: đối với các phương pháp hình học lời giải đại số bài toán được sử dụng “trong hậu trường” và kết quả hoàn thiện xuất hiện giống như một con thỏ chui ra khỏi mũ. Đại số thuần túy có thể giải quyết những vấn đề nào về số phức và đâu là giới hạn ứng dụng của nó? Các phương pháp hình học giúp giải quyết những vấn đề gì và số phức và hình học làm phong phú lẫn nhau như thế nào? Chúng tôi sẽ nói về tất cả điều này trong bài viết. Nhưng mục tiêu chính của chúng tôi - vì đây là tiêu đề "Trường học ở «Kvant» - là để dạy cho bạn, bạn đọc thân mến, các kỹ thuật làm việc với số phức, các phương pháp đại số và hình học lời giải bài toán, dựa trên cơ sở lý thuyết vững chắc. Đừng cố hiểu mọi thứ cùng một lúc. Hãy nghiên cứu bài viết một cách chu đáo, chậm rãi, quay lại phần "Sự kỳ diệu của số phức" (bí mật được tiết lộ?). và quan trọng nhất là giải bài toán, hầu hết đều bao gồm đáp số và gợi ý (tr. 51).

Đại số số phức

§1. Định nghĩa và tính chất trong câu hỏi và câu trả lời

Chúng tôi sẽ không định nghĩa lại các khái niệm ban đầu với hy vọng bạn đã quen thuộc với chúng (xem trang 5). Tốt hơn hết, hãy đọc phần giới thiệu chi tiết hơn về số phức từ nhiều nguồn khác nhau, chẳng hạn như [2–5]. Chúng tôi thực sự không hiểu ý nghĩa của chúng

⟦column⟧

lặp lại. Hãy cùng trả lời tốt hơn những câu hỏi thường gặp nhất trong loạt bài “Bạn muốn biết (làm rõ) điều gì nhưng lại ngại hỏi”. Khi thảo luận, chúng ta sẽ đi đến một định nghĩa hợp lý về số phức. Hỏi: Tại sao đơn vị tưởng tượng lại được biểu thị bằng chữ i? Tại sao bạn không thể viết $- 1$? Đáp: Đây là chữ cái đầu tiên trong từ Latin imaginarius (tưởng tượng). Nó được Euler đề xuất vào năm 1777. Thay vì viết i, sẽ không chính xác khi viết $- 1$, vì đây là ký hiệu cho tập nghiệm của phương trình $x^{2} = - 1$, ngoài i, còn có một nghiệm khác –i: $x^{2} + 1 = ( x - i )( x + i )$. Nhân tiện, chính trên ký hiệu đáng tiếc này mà các lỗi cơ bản như

1 = 1 =

$( - 1 )^{2} =$

2

$- 1 = - 1$.

Hỏi: Tại sao số phức thường được định nghĩa trong văn học là các cặp số thực? Điều này có vẻ hơi lạ, đặc biệt là khi giới thiệu phép nhân bằng công thức $( a, b )( c, d ) = ( ac - bd, ad + bc )$. Tại sao không chỉ viết a + bi? Đáp: Cách tiếp cận với các cặp đôi là sự tôn vinh chủ nghĩa hình thức, không hơn không kém. Khi đó họ vẫn chuyển sang ký hiệu dễ hiểu a + bi thay vì ( a, b ). Nó chỉ dễ dàng hơn để xác định mà không cần phải đắn đo thêm: các cặp đôi và thế là xong. Nhưng bạn nói đúng, việc nhân các cặp có vẻ điên rồ và những cuốn sách hay luôn thúc đẩy điều đó. Nếu bạn viết ngay a + bi, thì câu hỏi sẽ đặt ra, cộng này là gì và phép nhân của b với i là bao nhiêu. Tuy nhiên, trước tiên bạn cần xác định số phức là đối tượng và chỉ sau đó mới thực hiện các phép toán. Hỏi: Có phải thực sự không thể đưa ra một định nghĩa vừa chặt chẽ vừa rõ ràng? Đáp: Điều đó là có thể. Hãy coi số phức là vectơ trong mặt phẳng: $C = R^{2}$. Các vectơ là những cặp giống nhau và chúng ta biết cách cộng và nhân chúng với số thực (theo tọa độ). Hãy xác định vectơ (1, 0) bằng số 1 và ký hiệu vectơ (0, 1) bằng chữ i. Khi đó ( a, b ) = a ( 1, 0 ) + b ( 0, 1 ) = a + bi

– phân tích vectơ theo cơ sở 1, i. Vẫn còn phải xác định phép nhân của các vectơ cơ sở

⟦folio none⟧

KÍNH KÍNH KÍNH “QUANTA”

Xếp lát tuần hoàn của một mặt phẳng là lớp phủ của một mặt phẳng với các hình không chồng lên nhau, tồn tại hai vectơ không song song sao cho một sự dịch chuyển trên bất kỳ vectơ nào trong số chúng sẽ biến lớp phủ thành chính nó. Nếu lớp phủ định kỳ được hình thành bởi các bản sao của cùng một đa giác thì nó được gọi là sàn gỗ. Chỉ có ba đa giác đều - hình tam giác, hình vuông và hình lục giác - là sàn gỗ. Đối với các n-giác đều, góc đỉnh không phải là ước số của 360. Các phép tính của đa giác lồi không đều phức tạp hơn nhiều. Rõ ràng, sàn gỗ có thể được gấp lại, sao chép bất kỳ hình tam giác hoặc hình tứ giác nào. Nhưng không có n-giác lồi nào có n > 7 có thể được sử dụng để tạo thành một sàn gỗ. Với n = 6, ba loại hình lục giác lồi được tìm thấy và chứng minh rằng không có loại nào khác tồn tại (đối với hình lục giác ABCDEF, những loại này được đặc trưng bởi một tập hợp các mối quan hệ về góc và cạnh; không có hạn chế nào được áp đặt đối với các góc và cạnh không được đề cập).

⟦column⟧

đa giác, bằng cách chuyển song song, bạn có thể có được toàn bộ sàn gỗ. Năm loại đầu tiên được K. Reinhardt tìm ra vào năm 1918, và loại cuối cùng được biết đến, loại thứ 15, được C. Mann, J. McLeod, D. Von Derau tìm ra vào năm 2015. Loại 14 và 15 được xác định một cách cứng nhắc (đến mức tương tự nhau). Các loại còn lại có bậc tự do (ví dụ loại 1 có năm), việc thay đổi có thể thay đổi diện mạo của sàn gỗ khá đáng kể. Hơn nữa, một số loại hình ngũ giác ở dạng chung cho phép ốp nhiều lớp. Nhưng nó cũng xảy ra khác - loại này có một loại phụ (không có bậc tự do hoặc có ít bậc tự do hơn loại chính), có thể được sử dụng để xếp một mặt phẳng theo nhiều cách. Việc xác định các loại đa giác sàn gỗ thông qua tỷ lệ các cạnh và góc là nhỏ gọn và truyền thống nhất. Sau khi phân tích nó, chúng ta có thể đưa ra cấu trúc trực quan hơn của từng lớp, tiết lộ hình dạng của các tham số tự do. Bạn đọc quan tâm có thể cài đặt chương trình bách khoa toàn thư miễn phí

Với n = 5 bài toán không giải được hoàn toàn. Mười lăm loại hình ngũ giác lồi tạo thành sàn gỗ đã được phát hiện, nhưng liệu những loại khác có tồn tại hay không và nếu có thì loại nào vẫn chưa được biết. Các loại hình ngũ giác sàn gỗ ABCDE được tìm thấy với các mối quan hệ đặc trưng được trình bày ở trang bên phải của Kính vạn hoa. Miền cơ bản (được chọn vì lý do đối xứng) được đánh dấu rõ ràng - một tập hợp số lượng tối thiểu có thể có là http://www.jaapsch.net/tilings. Trong đó, tác giả của nó - J. Scherphuis - đã thu thập tất cả các ô xếp tuần hoàn hiện được biết đến (không chỉ với đa giác lồi mà còn không lồi). Tessellations với đa giác không lồi và bài toán khác của chủ đề này đã được thảo luận trong “Kính vạn hoa «Kvant» Số 2 năm 2009. Tài liệu do N. Andreev, M. Panov chuẩn bị
