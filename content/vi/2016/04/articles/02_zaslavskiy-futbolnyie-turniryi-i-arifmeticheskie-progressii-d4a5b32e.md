---
id: 2016-4-zaslavskiy-futbolnyie-turniryi-i-arifmeticheskie-progressii-d4a5b32e
issue: kvant_2016_4
year: 2016
number: "4"
title: Các giải đấu bóng đá và tiến trình số học
authors:
  - Заславский А. А.
rubric: zadachnik-kvanta
rubric_sub: Задачник «Кванта»
page_first: 22
page_last: 23
page_labels: 20-21
tag: 5SZ3
lang: vi
source: kvant_digital
extraction: native
content_sha256: eb6e206cc497d94ca6fa01bda77cabab31803ced1f7ebf5a9032885350f42910
prompt_sha256: draft-1
translated_from: content/ru/2016/04/articles/02_zaslavskiy-futbolnyie-turniryi-i-arifmeticheskie-progressii-d4a5b32e.md
source_content_sha256: 720ec65ff540fae60adf0e6158945dae63f2c22438f5c82152ba5cf80a923599
translation_model: draft
translation_run: vi-draft-2026-10-31
translation_quality: draft
---

⟦folio 20⟧

KVANT 2016/№4

Các giải đấu bóng đá và tiến trình số học

Vào năm 2012, bài toán sau đây đã được đề xuất tại Olympic Toán học LXXV Moscow. 75 đội tham dự giải bóng đá một vòng (thắng – 3 điểm, hòa – 1, thua – 0). Khoảng cách điểm nhỏ nhất có thể có giữa đội đầu tiên và đội cuối cùng là bao nhiêu nếu không có hai đội bằng điểm nhau? Vì khoảng cách tối thiểu giữa các đội liền kề là một điểm nên hiển nhiên khoảng cách giữa đội đầu tiên và đội cuối cùng không thể dưới 74 điểm. Tuy nhiên, thật khó để hiểu liệu ước tính này có thể đạt được hay không. Để tìm hiểu, điều tự nhiên là bạn nên bắt đầu bằng cách xem xét các giải đấu có số lượng người tham gia ít. Sau khi xem qua tất cả các giải đấu có 2 hoặc 3 người tham gia, thật dễ dàng để đảm bảo rằng những giải đấu bạn đang tìm kiếm không nằm trong số đó. Nhưng có thể xây dựng một giải đấu như vậy cho 4 đội (Bảng 1).

Bảng 1

Các nỗ lực cũng thành công đối với một số giá trị tiếp theo của số lệnh n. Do đó, nảy sinh giả định rằng các giải đấu tương ứng tồn tại với mọi n > 3. Điều này thực sự là như vậy; chính xác hơn, tuyên bố sau đây là đúng. Đối với $n \ge 4$ bất kỳ, sẽ có một giải đấu vòng tròn gồm n đội, trong đó các đội ghi được n – 2, n – 1, n, …, 2n – 3 điểm. Hãy chứng minh bằng quy nạp. Với n = 4, chúng ta đã xây dựng được giải đấu cần thiết. Giả sử rằng chúng ta có một giải đấu như vậy dành cho n đội và chúng tôi sẽ hướng dẫn cách thêm một đội mới vào giải đấu đó. Hãy sắp xếp các đội cũ theo thứ tự điểm giảm dần và để đội mới thắng đội nhất, thua đội thứ hai và thứ ba, thắng đội thứ tư, thua đội thứ năm và thứ sáu, v.v. (với thời gian là 3) cho đến khi cô ấy còn một, hai hoặc ba đội để thi đấu (tùy theo số dư của n khi chia cho 3). Trong trường hợp đầu tiên, đội mới đấu với đội cuối cùng với tỷ số hòa. Trận thứ hai, anh ta hòa với người áp chót và thua người cuối cùng, ở trận thứ ba, anh ta hòa với người cuối cùng, thua người áp chót và thắng người thứ ba từ dưới lên. Bằng cách tính toán trực tiếp, chúng tôi tin chắc rằng trong cả ba trường hợp, chúng tôi đều nhận được sự phân bổ số điểm mà chúng tôi cần.

⟦column⟧

điểm d tự nhiên mà các đội ghi được có thể tạo thành một cấp số cộng với chênh lệch d? Để hoàn thiện, chúng ta có thể đặt d là 0, trong trường hợp đó rõ ràng giải đấu mong muốn tồn tại (ví dụ: nếu tất cả các trận đấu đều kết thúc với tỷ số hòa). Với mọi n, trường hợp d = 3 có thể xảy ra (nếu đội thứ nhất thắng tất cả mọi người, đội thứ hai thắng tất cả mọi người ngoại trừ đội đầu tiên, v.v.). Cũng rõ ràng là sự khác biệt không thể lớn hơn 3 (tại sao?). Vì vậy, điều còn lại đối với chúng ta tiếp theo là nghiên cứu trường hợp d = 2. Hãy bắt đầu lại với các giá trị nhỏ của n. Đối với n = 2 và n = 3 thì không có giải đấu bắt buộc, đối với n = 4 thì có (Bảng 2).

Bảng 2

Nhưng với n = 5 thì không thể xây dựng được một giải đấu. Hãy để chúng tôi chứng minh rằng điều này thực sự là không thể. Nếu số điểm ghi được tạo thành một cấp số cộng với hiệu là 2 thì tổng của chúng được chia cho 5. Vì tổng số trận trong một giải đấu năm đội là 10, nên chúng ta thu được rằng tổng số điểm ghi được là 30 nếu tất cả các trận đấu kết thúc với chiến thắng cho một trong các đội và mỗi trận hòa sẽ giảm tổng số điểm này đi 1. Do đó, 0, 5 hoặc 10 trận đấu phải kết thúc với tỷ số hòa. Nếu không có trận hòa thì số điểm mỗi đội là bội số của 3 và không thể chênh lệch 2, còn 10 trận hòa thì tất cả các đội đều ghi được 4 điểm. Hãy xem xét trường hợp 5 trận hòa. Khi đó tổng số tiền là 25, tức là các đội phải ghi được 9, 7, 5, 3 và 1 điểm. Nhưng chỉ có một cách để ghi 9, 7, 5 và 1 điểm trong bốn ván đấu: lần lượt là ba thắng và một thua; hai trận thắng, một trận hòa và một trận thua; một trận thắng, hai trận hòa và một trận thua; một trận hòa và ba trận thua. Vì tổng số trận thắng phải bằng tổng số trận thua nên đội còn lại phải có số trận thắng và thua bằng nhau, điều này là không thể với 3 điểm. Tiếp tục xem xét các giá trị nhỏ của n, chúng tôi tin chắc rằng với n = 6, n = 7 và n = 8 thì tồn tại các giải đấu bắt buộc (Bảng 3, 4, 5).

Bảng 3

Bài tập 1: Kiểm tra.

Bây giờ hãy khái quát hóa bài toán và đặt câu hỏi sau. M2419. Có n đội tham gia vào một giải đấu bóng đá một vòng. Một đội thắng được 3 điểm, hòa được 1 điểm và thua được 0 điểm. Tại cái gì

Sau khi thử nghiệm thêm một vài giá trị của n, chúng ta có thể hình thành giả thuyết sau. 1) Với tất cả các số chẵn n = 2m, $m \ge 2$, có một giải đấu trong đó các đội ghi được m – 1, m + 1, m + 3, …, 5m – 3 điểm.

⟦folio 21⟧

NHÂN VIÊN VẤN ĐỀ

"QUANTA"

Bảng 4

Bảng 5

Bảng 7

⟦column⟧

Thao tác cộng hai lệnh có thể được thực hiện với n lẻ bất kỳ. Hãy để tất cả các đội cũ, ngoại trừ hai đội cuối cùng, ghi 3 điểm trước đội mới, và hai đội cuối cùng - mỗi đội một điểm, và nếu số dư của chia n cho 3 là 0 hoặc 2 thì cả hai đội này đều ghi điểm trước một trong các đội mới, và nếu là 1 thì với các đội khác. Sau đó, bạn có thể phân phối điểm giữa các đội mới để một trong số họ ở vị trí đầu tiên và đội kia ở vị trí thứ ba.

Bài tập 3. Chứng minh điều đó.

2) Đối với tất cả $n = 2m + 1, m \ge 3$ lẻ, có một giải đấu mà các đội ghi điểm m – 1, m + + 1, m + 3, …, 5m – 1 điểm. Hãy để chúng tôi chứng minh rằng đây thực sự là trường hợp. Hãy bắt đầu với trường hợp chẵn. Vì chúng tôi đã xây dựng các giải đấu cho 4, 6 và 8 đội nên chỉ cần chỉ ra cách thêm sáu đội mới vào giải đấu đồng đội 2k là đủ. Hãy để mỗi đội trong k đội cũ đứng đầu thua đội mới đầu tiên và thắng năm đội mới còn lại, và để mỗi đội cũ k cuối bảng, ngược lại, thắng đội mới đầu tiên và thua năm đội mới còn lại. Các đội mới chơi với nhau, như trong ví dụ về 6 đội. Không khó để xác minh rằng kết quả sẽ là sự phân bổ điểm mong muốn.

Bài tập 2. Kiểm tra.

Hãy chuyển sang trường hợp kỳ lạ. Đầu tiên, chúng tôi sẽ hướng dẫn bạn cách thêm hai đội nữa vào giải đấu bảy đội. Cho các đội mới đấu với các đội cũ như trong Bảng 6 (dòng trên cùng là số điểm mà các đội cũ ghi được trong các trận đấu với nhau).

Bảng 6

Khi đó các đội cũ có 17, 15, 13, 11, 9, 5 và 3 điểm, còn các đội mới có 19 và 4 điểm. Nếu bây giờ đội A mới đầu tiên thua đội B thì chúng ta sẽ có được giải đấu mong muốn cho 9 đội. Bây giờ chúng ta hãy thêm hai đội nữa vào giải đấu này (Bảng 7). Và một lần nữa để đội mới C đầu tiên thua đội mới thứ hai D. Kết quả là chúng ta có được giải đấu mong muốn gồm 11 đội.

Tuy nhiên, vì chúng tôi đã có các giải đấu dành cho 7, 9 và 11 đội nên việc tiến hành tương tự như trường hợp chẵn sẽ dễ dàng hơn và thêm sáu đội mới vào giải đấu đồng đội 2k+1. Hãy để mỗi đội trong số k cũ đứng đầu thua đội mới đầu tiên và đánh bại những đội còn lại, và để mỗi đội ở k cuối bảng, ngược lại, thắng đội mới đầu tiên và thua năm đội còn lại. Cuối cùng, để đội cũ trung bình thua ba đội mới đầu tiên và giành chiến thắng trước ba đội mới còn lại. Để các đội mới chơi với nhau như trong Bảng 8.

Bảng 8

Kết quả là chúng ta có được sự phân bổ điểm mong muốn. Tuyên bố đã được chứng minh đầy đủ.

Bài tập 4. Hãy chắc chắn về điều này.

Bây giờ chúng ta có thể tóm tắt và đưa ra kết quả đáp số hoàn chỉnh cho câu hỏi được đặt ra: với d = 0 và d = 3, giải đấu bắt buộc tồn tại với mọi n, với d = 1 - với mọi n, ngoại trừ 2 và 3, với d = 2 - với mọi n, ngoại trừ 2, 3 và 5. Để kết luận, chúng tôi khuyên bạn nên suy nghĩ xem đáp số sẽ thay đổi như thế nào nếu, thay vì bóng đá, chúng ta xem xét các giải đấu trong các môn thể thao khác, chẳng hạn như bóng chuyền, khi If một trong hai đội thắng với tỷ số 3:0 hoặc 3:1, đội thắng và đội thua lần lượt nhận được 3 và 0 điểm, còn nếu tỷ số là 3:2 - 2 và 1. A. Zaslavsky
