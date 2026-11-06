---
id: 1991-11-rafailov-kak-izluchat-radiovolnyi-d4c1ec0e
issue: kvant_1991_11
year: 1991
number: "11"
title: Làm thế nào để phát ra sóng vô tuyến?
authors:
  - Рафаилов А.
rubric: shkola-v-kvante
page_first: 35
page_last: 37
page_labels: 33-35
lang: vi
source: kvant_digital
extraction: vision
content_sha256: 96b19427ce711b1e51419a4458ba8737c31dc1e991b7e0dcf544bf3c512fc570
prompt_sha256: draft-1
translated_from: content/ru/1991/11/articles/12_rafailov-kak-izluchat-radiovolnyi-d4c1ec0e.md
source_content_sha256: 8f6cc0d405a24c7f7c5e3a375adaac3cb7eff80452a73dc11d2a79e5679ef4e0
translation_model: draft
translation_run: vi-draft-gaps-2026-11-06
translation_quality: draft
---

⟦folio 33⟧

Làm thế nào để phát ra vôn phóng xạ?

Trước khi phát ra vôn vôn - dao động điện từ xác định tần số, bạn cần thu được các dao động này. Điều này có thể được thực hiện bằng cách sử dụng máy tạo dao động liên tục. Nhưng làm thế nào để đảm bảo rằng sự hiện diện của dao động có thể được nhận biết ở xa máy phát là chủ đề của ghi chú này.

Hãy biểu mẫu bài toán cụ thể hơn: những gì cần được kết nối với đầu ra của bộ tạo dao động liên tục để sóng điện từ chạy từ nó? Câu hỏi này không hề đơn giản, có thể dễ dàng đoán ra rằng các phần tử đảm nhiệm vai trò làm anten bức xạ là không phù hợp. Ví dụ ở đây là một điện trở. Nếu chúng ta kết nối nó với đầu ra của máy phát điện thì toàn bộ năng lượng mà nó nhận được từ máy phát điện sẽ được chuyển hóa hoàn toàn thành nhiệt. Một tụ điện cũng không phù hợp với vai trò của ăng-ten - công suất trung bình mà nó nhận được từ máy phát chính xác bằng 0 (độ lệch pha giữa điện áp và dòng điện bằng bốn chu kỳ). Điều này có nghĩa là anh ta đơn giản là không có gì để phát ra - xét cho cùng, khi phát ra sóng điện từ, năng lượng phải được truyền từ nguồn theo mọi hướng. Điều tương tự cũng đúng với cuộn cảm.

Vì vậy, để tối ưu hóa công suất từ ​​máy phát, phải thay đổi độ lệch pha giữa dòng điện và điện áp - không được là chu kỳ thứ tư. Điều này có thể đạt được, ví dụ, bằng cách mắc nối tiếp một tụ điện và điện trở. Tuy nhiên, sẽ không có gì hữu ích xảy ra với chúng ta: bây giờ các tải (tụ điện và điện trở) được tối ưu hóa bởi máy phát năng lượng, nhưng toàn bộ năng lượng này được chuyển hóa hoàn toàn thành nhiệt. Hãy thử tự mình xem điều này - đối với một mạch đơn giản như vậy, nó sẽ không gây khó khăn gì. Hóa ra đối với các mạch LCR tùy ý (ví dụ như trên hình 1), quy tắc này đúng: tất cả năng lượng mà mạch nhận được từ nguồn sẽ đi vào

⟦folio 34⟧

---
running_head:
folio:
---

Tello. Trong trường hợp này, sự phụ thuộc của công suất tức thời vào thời gian có dạng
$p = u(t)i(t) = U_0 \cos \omega t \cdot I_0 \cos (\omega t + \varphi)$,
trong đó $\varphi$ là độ lệch pha giữa dòng điện và điện áp. Sau các phép biến đổi lượng giác đơn giản, có thể dễ dàng tìm được công suất trung bình tiêu thụ từ nguồn trong một khoảng thời gian (và do đó trong một khoảng thời gian dài):

$$P_{cp} = \frac{1}{2} U_0 I_0 \cos \varphi = UI \cos \varphi.$$

Đây chính xác là sức mạnh biến thành nhiệt.

Nhân tiện, hãy lưu ý rằng giá trị cực đại của công suất tức thời lớn hơn giá trị $P_{cp}$ và ở giai đoạn dịch chuyển gần đến $90^\circ$ - nhiều lần. Điều này có nghĩa là nguồn phải có khả năng tạo ra công suất tức thời cao hơn đáng kể so với công suất trung bình được lấy từ nó. Tình huống này đôi khi phát sinh trong kỹ thuật điện thực tế - khi kết nối đèn huỳnh quang, động cơ điện, v.v. Với đèn huỳnh quang, điều này xảy ra do dòng điện qua đèn được đặt bởi kết nối nối tiếp của cuộn cảm và độ lệch pha gần bằng $90^\circ$ (hình 2). Tải quá mức trên mạng điện là điều cực kỳ không mong muốn, vì nó dẫn đến tổn thất bổ sung dưới dạng nhiệt và buộc phải sử dụng dây dẫn đắt tiền. Vị trí có thể được điều chỉnh bằng cách kết nối song song một tụ điện có điện dung phù hợp (điều này đòi hỏi phải điều chỉnh để tạo ra sự cộng hưởng!). Trong trường hợp này, cuộn dây và tụ điện sẽ trao đổi năng lượng với nhau trong toàn bộ thời gian - năng lượng “thêm” được bơm giữa chúng và mạng - nguồn năng lượng đi vào tải - chỉ giải phóng lượng năng lượng chuyển thành nhiệt.

Vì vậy, các mạch loại này (mạch LCR) không phù hợp với vai trò của ăng-ten. Vấn đề là làm cho sự lệch pha giữa dòng điện và điện áp trong mạch khác với $90^\circ$, nhưng không gây ra hiện tượng sinh nhiệt, tức là không có điện trở. Hóa ra nếu kích thước của các thành phần mạch tải nhỏ so với bước sóng thì không thể làm được gì. Nhưng với các phần tử tải lớn, có thể thu được sự dịch pha bổ sung do độ trễ truyền sóng.

Giả sử một tụ điện được sử dụng làm tải, điện trở của nó (đối với dòng điện xoay chiều có tần số nhất định) là tối ưu đối với một máy phát nhất định. Bây giờ chúng ta hãy bắt đầu tăng độ trễ bằng cách thay đổi khí của tụ điện. Nhưng bạn không thể đơn giản tăng kích thước của các tấm tụ điện - công suất của nó sẽ lớn hơn. Để duy trì công suất, bạn sẽ phải tăng khoảng cách giữa các tấm. Nói đúng ra, tụ điện lớn không còn là tụ điện nữa. Sự dịch pha bây giờ tương ứng với một mạch khác và sẽ cần nguồn điện từ máy phát, mặc dù không có điện trở và không tạo ra nhiệt. Do đó, năng lượng từ máy phát điện phải đi đâu đó, cụ thể là tỏa vào không gian.

⟦folio 35⟧

---
running_head:
folio:
---

Để có được công suất bức xạ lớn nhất, bạn cần tối ưu hóa kích thước và cấu hình của ăng-ten. Ví dụ, nếu một ăng-ten như vậy bao gồm hai thanh - dài và mỏng, thì độ dài tối ưu của mỗi thanh phải bằng bốn bước sóng, thanh phải được hướng dọc theo một đường thẳng và các đầu cuối của bộ tạo dao động không tắt dần phải được kết nối như trong hình 3. Những ăng-ten như vậy thường được sử dụng cho tivi. Về bản chất, ăng-ten ứng dụng và ăng-ten phát không khác nhau (chỉ đối với các máy phát rất mạnh thì mới cần chế tạo ăng-ten phát đặc biệt, có tính đến hướng cao và dòng điện cao cung cấp cho ăng-ten để truyền).

Nếu kích thước của ăng-ten được chọn chính xác thì sẽ không có tải "phụ" nào được tạo ra cho bộ tạo máy phát vô tuyến và năng lượng phát ra từ nó sẽ được tỏa vào không gian. Tuy nhiên, những mong muốn này chỉ dễ dàng được đáp ứng đối với các máy phát vô tuyến cố định và không có tần số truyền quá thấp (bước sóng không quá dài). Đối với các đài phát thanh di động, điều này không phải lúc nào cũng thực hiện được - ăng-ten hóa ra ngắn hơn nhiều so với mức cần thiết để phối hợp tối ưu với máy phát.

Trong trường hợp này, bạn có thể "làm nhẹ số phận" của máy phát điện bằng cách mắc nối tiếp với ăng-ten một cuộn dây cảm ứng (người ta gọi đó là cuộn dây mở rộng) - một điện dung
Điện trở của dây anten ngắn sẽ bị triệt tiêu bởi điện kháng cảm ứng của cuộn dây.

Ăng-ten cũng có thể bao gồm một số dây dẫn - bằng cách chọn độ dài và vị trí của các dây dẫn này và cung cấp cho chúng dòng điện từ máy phát theo các pha cần thiết, có thể đảm bảo rằng bức xạ xảy ra chủ yếu theo một hướng nhất định (ăng-ten ("định hướng"). Đây là một ví dụ về việc sử dụng tích hợp cho mục đích kỹ thuật. Nhân tiện, không nhất thiết phải kết nối tất cả các dây dẫn với máy phát - dòng điện phát sinh trong dây dẫn do nó nằm trong trường điện từ của ăng-ten chính có thể khá đủ cho mục đích của chúng tôi. Tất cả điều này áp dụng cho ăng-ten được áp dụng, thường bao gồm dây dẫn chính - "bộ rung" (nguồn gốc của thuật ngữ này phải rõ ràng) và một số dây dẫn bổ sung, không được kết nối với kích thước và vị trí được xác định nghiêm ngặt (chúng được gọi là "đạo diễn" và "bộ phản xạ", số lượng và độ chính xác của việc lựa chọn phụ thuộc vào hướng của ăng-ten).

Hóa ra là có thể chọn cấu hình của một ăng-ten phức tạp để nó hoạt động tốt không chỉ ở tần số được xác định nghiêm ngặt mà còn trên toàn bộ dải tần. Điều này là hoàn toàn cần thiết, chẳng hạn như để thu sóng truyền hình - xét cho cùng, việc có ăng-ten riêng cho mỗi kênh sẽ không thuận tiện lắm. Tuy nhiên, nếu tần số kênh cách xa nhau hoặc ăng-ten ở rất xa trung tâm viễn thông, bạn phải sử dụng nhiều ăng-ten riêng biệt được điều chỉnh tốt.

A. Rafailov
