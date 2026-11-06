---
id: 1990-12-dubrovskiy-kubiki-mak-magona-i-tablitsa-konveya-c47fe7ba
issue: kvant_1990_12
year: 1990
number: "12"
title: Khối McMahon và bảng Conway
authors:
  - Дубровский В. Н.
rubric: igry-i-golovolomki
rubric_sub: Игры и головоломки
page_first: 66
page_last: 66
page_labels: "64"
lang: vi
source: kvant_digital
extraction: vision
content_sha256: d22f3a7b895af24e95a7cab452197e75af532147910128afe1f3e02fc097c125
prompt_sha256: draft-1
translated_from: content/ru/1990/12/articles/21_dubrovskiy-kubiki-mak-magona-i-tablitsa-konveya-c47fe7ba.md
source_content_sha256: 10e8c889044f1ca039a57ae2da5332c945729302a450747d98acd81f72b2e622
translation_model: draft
translation_run: vi-draft-gaps-2026-11-06
translation_quality: draft
---

⟦folio 64⟧

---
running_head:
folio:
---

Khối McMahon và bảng Conway

Vào đầu thế kỷ này, Thiếu tá người Anh Alexander MacMahon, một giáo viên toán tại Học viện Quân sự Hoàng gia, đã nghĩ ra một số bài toán với những chiếc cốc nhiều màu. Trước ông, những bộ cốc như một trò chơi chỉ được sử dụng để xây dựng những tòa nhà kiên cố và để ghép các bức tranh lại với nhau từ những mảnh ghép trên các cạnh của chúng. (Nhân tiện, “khối có thẻ” không có lịch sử lâu đời như vậy - chúng được phát minh ở Đức vào giữa thế kỷ trước.) Kể từ đó, số lượng trò chơi với cốc đã tăng lên vô cùng, và khối Rubik vượt trội đã chiếm vị trí tự hào trong số đó... Tuy nhiên, người đầu tiên là Vetset McMahon và bạn của ông, Đại tá Jocelyn, người đã chứng minh khả năng giải được cơ bản của nó bài toán. Nhưng điều đầu tiên trước tiên.

Hãy tưởng tượng rằng bạn cần sơn một khối lập phương có 6 màu, mỗi cạnh một màu khác nhau. Đối với cạnh dưới, bạn có thể chọn bất kỳ màu nào trong số các màu, cho mặt trước - bất kỳ màu nào trong số 5 màu còn lại, cho bên phải - bất kỳ màu nào trong số 4 màu còn lại, v.v. Hóa ra có tổng cộng 6·5·4·3·2·1=720 phương pháp tô màu. Nhưng nếu bạn chuẩn bị 720 chiếc cốc này, bạn sẽ thấy rằng nhiều chiếc trong số đó ngay khi bạn nhặt chúng lên sẽ không thể phân biệt được - xét cho cùng, trên khối lập phương không có ghi mặt nào là mặt dưới, mặt nào là mặt trước. Các màu sắc trung tính thu được từ nhau bằng cách xoay khối lập phương, biến nó thành chính nó. Có 24 phép quay như vậy: 9 phép quay với các góc ±90° và 180° quanh trục đi qua tâm của các cạnh đối diện, 8 phép quay với góc ±120° quanh đường chéo của hình lập phương, 6 phép đối xứng trục so với các đường thẳng nối trung điểm của các cạnh đối diện và một phép biến đổi giống hệt nhau. Do đó, với mỗi trong số 720 màu được xét ở trên, có thêm 23 màu tương đương và số lượng màu khác nhau đáng kể là 720:24=30. Đó là cột cốc trong bộ McMahon. Tất cả đều được thể hiện trong bảng ở bìa sau. Nó cũng thông báo cách sử dụng bảng này, được phát minh bởi nhà toán học người Mỹ John Conway, để giải quyết nhanh chóng và đẹp mắt bài toán McMahon: bằng cách đặt một khối lập phương từ bộ - một mẫu, tìm phần giữa của 29 khối còn lại như 8, từ đó bạn có thể thêm một bản sao nhân đôi của mẫu, tuân theo “quy tắc domino”: các khối nhỏ phải chạm vào các cạnh cùng màu.

Nếu nhìn vào khối lập phương mẫu dọc theo đường chéo, chúng ta sẽ thấy ba mặt sụp đổ ở một đầu của nó. Hãy biểu thị chúng bằng các màu 1, 2, 3 và màu của các mặt được tạo ra lần lượt là 4, 5, 6. Khi sử dụng hình số 8, bạn phải bao gồm ít nhất một khối lập phương có góc tam diện, được sơn cùng màu 1, 2, 3 và theo cùng một thứ tự. Có sáu cốc như vậy cùng với mẫu (đây là số hoán vị của các số 4, 5, 6). Tuy nhiên, không khó hiểu khi “quy tắc domino” chỉ để lại trong sáu tùy chọn màu này, lần lượt là đối diện 1, 2, 3: 5, 6, 4, 6, 4, 5. Từ thông điệp về tính đối xứng, có thể thấy rõ rằng bất kỳ chiếc cốc nào trong hai chiếc cốc này đều có thể được đặt ở góc (1, 2, 3) của một khối lập phương lớn, thì khối thứ hai sẽ cần được đặt ở góc đối diện (4, 5, 6). (Điều thú vị là trong bảng Conway, hai khối lập phương này và mẫu luôn nằm ở các vị trí có dạng Hu, Yx và Zx). Tương tự, có ba cặp cốc cho ba đường chéo còn lại. Do đó, lá Eight of Cup quyết định bài toán

McMahon đối với một mẫu nhất định đã được xác định rõ ràng, mặc dù có hai cách để gấp một khối lớn hơn từ nó - để lấy phương pháp này từ phương pháp kia, bạn cần di chuyển từng khối sang góc đối diện. Trong bảng Conway, các hình khối tương ứng với mẫu Hu nằm ở hàng Y và cột x; khối Yx phải được loại trừ khỏi chúng. Bạn có thể kiểm tra xem bốn khối lập phương trong một hàng khi lắp ráp một khối lớn sẽ chiếm các vị trí ở đầu đường chéo của đế dưới và đường chéo của đế trên cắt ngang nó.

Bài toán McMahon có phần tiếp theo: sau khi tạo một bản sao theo mẫu này, bạn cần tìm trong số các cốc còn lại mẫu và 8 cốc tạo thành bản sao của nó tuân thủ “quy tắc domino”. Bằng cách sử dụng bảng, bài toán này được giải gần như tự động - các khối dấu phẩy được xác định duy nhất và là hình ảnh phản chiếu của các cốc của bộ đầu tiên.

Có lẽ bảng của Conway sẽ giúp bạn giải được bài toán sau.

1. Tuân thủ “quy tắc domino”, gấp một khối lập phương 2x2x2, mỗi mặt của khối đó sẽ được tô bằng một trong a) gót, 6) bốn, b) ba màu (trong mỗi trường hợp phải sử dụng tất cả các màu đã cho). Tất cả những bài toán này có được phép không?

2. Hãy từ bỏ "luật domino". Sau đó, bạn có thể gấp bao nhiêu cách gấp một khối lập phương 2×2×2 theo một cách nhất định? Có bao nhiêu bộ 8 cốc có thể làm được điều này? Chứng minh rằng một khối lập phương từ một bộ như vậy có thể được gấp lại theo 2, 4, 8 hoặc 16 cách. Khối sao chép 3x3x3 có thể gấp lại được không?

V. Dubrovsky
