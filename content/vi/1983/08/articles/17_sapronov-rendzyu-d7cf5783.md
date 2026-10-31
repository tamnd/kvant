---
id: 1983-8-sapronov-rendzyu-d7cf5783
issue: kvant_1983_8
year: 1983
number: "8"
title: renju
authors:
  - Сапронов В. А.
rubric: igry-i-golovolomki
rubric_sub: Игры и головоломки
page_first: 59
page_last: 60
page_labels: 57-58
tag: DK1R
lang: vi
source: kvant_digital
extraction: vision
content_sha256: e43e676be73a50b56751f7a848d203fd005ba8e5d4b4b2ed1fd24a4b5485f516
prompt_sha256: draft-1
translated_from: content/ru/1983/08/articles/17_sapronov-rendzyu-d7cf5783.md
source_content_sha256: 1461fccc2eea6a1c3e5df267c6e0b8279018332d503f61c9077b47bfb4de8491
translation_model: draft
translation_run: vi-draft-2026-10-31
translation_quality: draft
---

⟦folio 57⟧

renju

V. A. SAPRONOV

Khi còn nhỏ, chắc hẳn nhiều bạn đã chơi “tic-tac-toe” trên bảng 3x3 (Hình 1): người chơi lần lượt đặt “tic-tac-toe” vào các ô trống; Người chiến thắng là người xây dựng được một hàng (theo chiều dọc, chiều ngang hoặc đường chéo) lần lượt gồm ba “chữ thập” hoặc “ngón chân”. Trong ủng hộ
Hình 1.

hơn những người chơi trò “tic-tac-toe” đơn giản này nhanh chóng nhận ra rằng trò chơi này là một trận hòa: nếu cả hai người chơi đều chơi đúng thì trận đấu sẽ kết thúc với tỷ số hòa.

Có lẽ đó là lý do tại sao trò chơi “tic-tac-toe” trên một bảng “vô tận” (tức là không giới hạn) đang lan rộng trong giới học sinh và học sinh trung học. Dễ dàng nhận thấy nếu trên bàn cờ như vậy chúng ta lại coi “ba liên tiếp” là thắng thì người mới bắt đầu sẽ dễ dàng thắng. Kiểm tra xem trong trò chơi “bốn liên tiếp”, người mới bắt đầu có thể giành chiến thắng khá dễ dàng. Họ thường chơi “năm liên tiếp”. Thực tế cho thấy rằng trong trường hợp này người mới bắt đầu sẽ thắng (chúng tôi không có bằng chứng về tuyên bố này).

Từ quan điểm logic, renju là một lựa chọn trung gian giữa hai dạng mô tả của tic-tac-toe. Bảng - 15x15. Người mới bắt đầu đặt một chữ thập vào ô trung tâm. Sau đó, người chơi thứ hai đặt số “0” vào bất kỳ ô nào trong số 224 ô trống. Ở nước đi thứ ba, người chơi đầu tiên đặt một “chữ thập” vào bất kỳ ô trống nào không nằm ở ô vuông trung tâm 5x5 (đây là hạn chế duy nhất được công nhận để cân bằng cơ hội của các bên). Sau đó, lần lượt người chơi đặt “ngón chân” và “chữ thập” vào bất kỳ ô trống nào. Người chiến thắng là người xây dựng được một hàng gồm năm “chữ thập” hoặc theo đó là “ngón chân”, và các hàng dài hơn không được tính. Bot và tất cả các quyền Renju.

Chỉ cần nói thêm rằng bản thân những người theo chủ nghĩa Renjiist nói một ngôn ngữ khác – khá tương đương –.

Trò chơi "Renju" có nguồn gốc từ Trung Á hơn bốn nghìn năm trước. Nó được chơi bởi người Armenia cổ đại và người Inca ở châu Mỹ thời tiền Colombia. Vào đầu lịch sử của chúng ta, Renju đã đến Nhật Bản, nơi nó trở nên phổ biến nhất. Vào thế kỷ 20, Renju lan rộng khắp thế giới.

Renju được chơi như thế nào? Sooreriki đặt quân cờ của mình tại các điểm giao nhau của đường vuông trên cạnh 14 ô (Hình 2); trên mỗi cạnh của hình vuông như vậy có 15 điểm, tổng cộng là 15x15. Người mới bắt đầu (“đen”) đặt quân cờ đen ở điểm trung tâm. Sau đó, người chơi thứ hai (“trắng”) đặt quân cờ trắng vào bất kỳ điểm nào trong số 224 điểm miễn phí. Ở nước đi thứ ba, Đen đặt một quân cờ đen vào bất kỳ điểm trống nào nằm bên ngoài ô vuông trung tâm (trong các bức tranh nó được vẽ cùng màu), chứa 5x5 điểm (hạn chế này* chỉ áp dụng ở nước đi thứ ba!). Sau đó quân trắng và đen lần lượt đặt quân cờ của mình vào bất kỳ điểm trống nào. Người chiến thắng là người xây được hàng (theo chiều dọc, chiều ngang hoặc đường chéo)

*) Nó được phát minh ra cách đây vài năm ở nước ta. Họ cũng cố gắng cân bằng cơ hội của các bên với những hạn chế khác (ví dụ, xem “Khoa học và Cuộc sống”, 1980, số 9).

⟦folio 58⟧

từ gót quân cờ của họ, và các hàng dài hơn không được tính.

Bạn ngồi xuống bàn và ngay lập tức nhận ra rằng việc giành chiến thắng khó khăn như thế nào: đối thủ của bạn đang chặn mọi nỗ lực của bạn để lọt vào top 5 đáng thèm muốn và đang đe dọa giành chiến thắng. Làm thế nào để giành chiến thắng?

Hãy bắt đầu từ cuối. Tất nhiên, tất cả các cuộc tấn công, trừ khi đối thủ mắc một sai lầm cơ bản, kết thúc bằng việc hình thành một trong các nhánh: 4-4, 4-3 hoặc 3-3 (Hình 3; số 4 biểu thị bốn - séc, số 3 - ba - kiểm tra một nửa).

Hình 4 thể hiện trò chơi Makarenko - Sapronov của Giải vô địch Moscow lần thứ hai (cờ rô đen sau đây được mô tả là vòng tròn đen, cờ caro trắng là vòng tròn màu đỏ; số bên trong vòng tròn là số nước đi; tôi khuyên bạn nên vẽ một bảng và “chơi” trò chơi này trên đó từng nước đi).

Ở nước đi thứ 34, Trắng kiểm tra một nửa, Đen đáp lại bằng một loạt séc (nước 35, 37, 39,..., 51), kết thúc bằng tỷ số 4-3, sau đó Trắng buộc phải từ chức.

Hình 5 thể hiện trận đấu Janson - Sundling của Giải vô địch Thụy Điển. Ở nước đi thứ 18, Trắng kiểm tra một nửa, Đen đáp lại bằng một loạt séc (nước đi 19, 21,..., 27), kết thúc bằng ngã ba 4-3. (Theo tôi, nước đi thứ 5 của Đen không phải là nước đi tốt nhất và Trắng có thể chứng minh điều này bằng cách chơi nước đi thứ 6 đến điểm 9. Một nước đi hứa hẹn hơn cho Đen sẽ là nước đi thứ 5 đến điểm 8; nếu Trắng đi đến điểm 7 với nước đi thứ 6, Đen sẽ đi đến điểm 6 với nước đi thứ 7.)

Đôi khi lời đe dọa fork hiệu quả hơn một loạt “kiểm tra, kiểm tra một nửa” hoặc “kiểm tra một nửa, kiểm tra”. Trong Hình 6, sau khi Đen di chuyển đến điểm 1, Trắng không thể phòng thủ. Không khó để xác minh rằng việc LOB di chuyển đến điểm A và chỉ sau đó việc di chuyển đến điểm 1 mới làm mất đi cơ hội chiến thắng của Đen.

Ngược lại, ở Hình 7, Trắng nên chơi “nguyên thủy” ở điểm 1, rồi đến điểm 3. Nếu Trắng đi thẳng đến điểm 3 thì Đen sẽ dễ dàng phòng thủ.

Trong Hình 8, quân đen, bằng cách di chuyển đến điểm 1, đã tạo ra vị trí ban đầu cho đợt tấn công tiếp theo của một loạt séc (nước đi này được gọi là chỉ định
