---
id: 1981-11-gik-evm-i-shahmatnyiy-kodeks-4b1f4256
issue: kvant_1981_11
year: 1981
number: "11"
title: Máy tính và mã cờ vua
authors:
  - Гик Е. Я.
rubric: shahmatnaya-stranichka
rubric_sub: Шахматы
page_first: 67
page_last: 68
tag: 6GYV
lang: vi
source: kvant_digital
extraction: vision
content_sha256: 16000d8ce03be2cfc80d624c281e7d7dcf4839299cef72c5f520ed212968488f
prompt_sha256: draft-1
translated_from: content/ru/1981/11/articles/01_gik-evm-i-shahmatnyiy-kodeks-4b1f4256.md
source_content_sha256: e234d646aff5a63c35507efa02b7b45710a4fb66bdf0d1694d257ed67ec4dc9e
translation_model: draft
translation_run: vi-draft-2026-10-31
translation_quality: draft
---

⟦folio none⟧

CUỘC THI CỜ VƯƠNG

MÃ MÁY TÍNH VÀ CỜ VƯƠNG

Khi các nhà toán học (những người sáng tạo ra Kansa) dạy máy tính nghiên cứu về tàn cuộc, họ đã phân tích một số quan điểm nổi tiếng. Và đây là điều đã trở nên rõ ràng.

Một trong những kết thúc khó khăn nhất là "quân hậu với quân tốt của hiệp sĩ đấu với quân hậu". Máy kiểm tra các vị trí có quân tốt trắng ở hàng thứ bảy và bây giờ có thể nói chính xác cho từng vị trí rằng Trắng sẽ thắng hay không, và nếu họ thắng thì sẽ đi bao nhiêu nước đi. Đây là một trong hai vị trí đáng được họ đặc biệt quan tâm.

Nước đi của Đen. Trắng sẽ thắng

Ở đây quân trắng thực sự thắng, nhưng... trong luật cờ vua có các quy tắc sau: trò chơi kết thúc với tỷ số hòa nếu cả hai bên thực hiện 50 nước đi, trong đó không có quân nào bị bắt và không có quân tốt nào thực hiện nước đi. Cho đến thời điểm này, trong phiên bản mới nhất của bộ luật có cách giải thích như sau: "Đối với các vị trí "vua và hai hiệp sĩ chống lại vua và tốt", số lượng 50 nước đi tăng lên 75 nước đi. Nó chỉ có thể được tăng lên đối với các vị trí cụ thể khác với điều kiện con số này và các vị trí này được chỉ định rõ ràng trong quy định của giải đấu hoặc trận đấu. "

Ở thế cờ trên, cả hai bên đều chơi 58 nước, có sự cơ động và chỉ đến nước thứ 59, quân tốt bị bắt hoặc thăng cấp.

Vì vậy, các vị trí được máy tính khám phá cho thấy số lượng 50 nước đi nên được tăng lên trong mã và cho tàn cuộc “vua, hậu và tốt chống lại vua và hậu”. Có thể nói đây là lần đầu tiên trong lịch sử một máy tính được kết hợp thành một mã cờ vua! (Trò chơi kết thúc “vua và hai hiệp sĩ chống lại vua và quân tốt” đã được nghiên cứu từ nhiều năm trước và không có sự trợ giúp của máy tính).

Trong thực tế, một số lượng đáng kể các đuôi quân hậu được tìm thấy ở các đuôi quân xe. Họ là một trong những kiểu kết thúc phổ biến như vậy - “quân xe với quân tốt chống lại xe” - và cũng được giao nhiệm vụ nghiên cứu máy tính. Sau 60 giờ sử dụng máy tính, cô ấy nhanh chóng hoàn thành nhiệm vụ của mình và giờ đây có thể đánh giá bất kỳ vị trí nào thuộc loại này, bất kể vị trí của con tốt. Trong trường hợp này, máy có thể được thiết lập dựa trên bất kỳ dữ kiện nào. Ví dụ, cô ấy phát hiện ra một thế cờ sẽ giành được không sớm hơn nước đi thứ 60: Trắng - Kc3, Rlc4, pb2; Đen - Kc4, Rd1 (Đen di chuyển). Nhân tiện, con tốt ở đây chỉ có thể được đưa ra khỏi vị trí của nó ở nước đi thứ 32 sau một thời gian dài thao tác khó khăn.

Để nhanh chóng đánh giá các vị trí cuối trò chơi đang nổi lên, sẽ rất hữu ích nếu có một sơ đồ và vùng chiến thắng cho vị trí của bất kỳ quân cờ nào với vị trí cố định của các quân cờ còn lại. Máy tính cũng giúp ích ở đây.

Ở “vị trí” này, đó là nước đi của Đen (vua đen có thể đứng trên bất kỳ ô nào trên bàn cờ có sẵn cho mình). Ở một số vị trí vua Đen, Trắng sẽ thắng, ở những vị trí khác thì không. Kết quả phân tích được thực hiện bởi máy tính được hiển thị trực tiếp trong hình. Nếu trên ô không có số dành cho vua thì chức vị đó vô giá trị; nếu số n được viết trên trường này thì Trắng sẽ thắng trong n nước đi. Chúng ta thấy rằng nếu vua đen bị cắt dọc theo đường “f”, thì ô lưu trữ duy nhất cho ông ta là g4 (không tính các ô mà vua chỉ lấy quân trắng).

Nhiệm vụ cạnh tranh ngày nay sẽ cho phép bạn cạnh tranh với máy tính. Đây là những tàn cuộc cờ vua thực sự mà máy đã phân tích thành công.

1. Trắng bắt đầu và thắng.

2. Trắng bắt đầu và thắng.

Ngày gửi thư lời giải là ngày 31 tháng 12 năm 1981 (có ghi chú trên phong bì “Cuộc thi cờ vua số 11-81”).

⟦folio none⟧

Olympic Toán học toàn Liên đoàn lần thứ XV dành cho học sinh
(Alma-Ata, tháng 4 năm 1981).

Giám tuyển lớp 8 A. M. Slinko tiến hành phân tích bài toán với học sinh.

lời giải của ai tốt hơn?

Có lẽ «Kvant» sẽ giúp ích?
