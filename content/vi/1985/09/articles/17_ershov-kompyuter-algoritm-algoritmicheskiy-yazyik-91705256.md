---
id: 1985-9-ershov-kompyuter-algoritm-algoritmicheskiy-yazyik-91705256
issue: kvant_1985_9
year: 1985
number: "9"
title: Máy tính - thuật toán - ngôn ngữ thuật toán
authors:
  - Ершов А. П.
rubric: raznoe
rubric_sub: Разное
page_first: 52
page_last: 55
page_labels: 50-53
tag: GUYN
lang: vi
source: kvant_digital
extraction: vision
content_sha256: db2a38dc24369faa03ec86cab2743b2d65f9ba5907bbfb6c7df8029958bcf50c
prompt_sha256: draft-1
translated_from: content/ru/1985/09/articles/17_ershov-kompyuter-algoritm-algoritmicheskiy-yazyik-91705256.md
source_content_sha256: d27aab288230c1012009924e0dd6a0f0d0952d40a485a170be8e88dbfe4f0078
translation_model: draft
translation_run: vi-draft-2026-10-31
translation_quality: draft
---

⟦folio 50⟧

Do việc đưa khóa học “Cơ bản về Thông tin và Khoa học Máy tính” vào chương trình giảng dạy ở trường tiểu học kể từ năm học 1985-86, chúng tôi sẽ tiếp tục kết quả xuất bản trong phần “Nghệ thuật lập trình”, mở trên trang «Kvant» vào năm 1979. Tài liệu chúng tôi xuất bản nhằm mục đích làm rõ, phát triển và đào sâu chương trình giảng dạy ở trường. Chúng tôi sẽ bắt đầu quy tắc giáo dục này bằng hai bài viết của thành viên Hội đồng biên tập của chúng tôi, Viện sĩ A.P. Ershov. Mục tiêu chính của những bài viết này là dạy cách viết thuật toán một cách chính xác. Khi đọc chúng, bạn nên chú ý đến những từ in nghiêng - đây là những thuật ngữ thông tin đặc biệt, ý nghĩa chính xác của chúng cần được kiểm tra bởi nhà khoa học.

Máy tính – thuật toán – ngôn ngữ thuật toán

Viện sĩ A. P. ERSHOV

Máy tính hôm nay và ngày mai

Không cần phải chứng minh máy tính quan trọng như thế nào trong cuộc sống hàng ngày của chúng ta. Ngày nay, máy tính không chỉ thực hiện mọi loại tính toán, chúng còn phân phối máy bay, chơi cờ vua, hình cơ quan tự động hóa được thiết kế, soạn nhạc, đánh giá các buổi biểu diễn thể thao, chẩn đoán bệnh nhân, điều khiển nhà máy điện. Hơn nữa, vai trò của máy tính trong xã hội ngày càng phát triển nhanh chóng.

Sự hiểu biết của chúng ta về chúng cũng đang thay đổi: chúng không còn là những bóng đèn nhấp nháy bên trong những chiếc tủ lớn nữa mà là những chiếc TV lai khiêm tốn nhưng trang nhã với máy đánh chữ.

Nhưng trên thực tế, máy tính trước hết là môi trường mỏng nhất của tinh thể silicon, có kích thước gần bằng một thương hiệu, vướng vào một sợi dây mỏng nhất, mà trong tương lai sẽ có chỗ đứng trong hầu hết mọi sản phẩm công nghiệp. Tên khoa học của tinh thể như vậy là bộ vi xử lý. Theo tôi, việc sản xuất công nghiệp các bộ vi xử lý là sự đổi mới kỹ thuật mang tính cách mạng nhất của thế kỷ 20. Và theo một số nhà tương lai học, trong một tương lai không xa, điều đó sẽ dẫn đến thực tế là sản xuất xã hội sẽ chủ yếu được thực hiện bởi robot và được điều khiển bởi máy tính, và phần lớn dân số sẽ bận rộn viết các chương trình hỗ trợ chúng.

Bằng cách này hay cách khác, những người mà cuộc sống lao động chủ yếu dành cho thế kỷ 21 không thể trở thành thành viên chính thức của xã hội nếu họ không biết cách giao tiếp với máy tính, nếu họ chưa vượt qua ngưỡng biết chữ thứ hai (máy tính). Với mục đích này, nhà trường đã giới thiệu khóa học mới “Cơ bản về công nghệ máy tính thông tin”.

Serody lời giải khoa học hoặc thực tế bài toán trên máy tính là một tác phẩm được dàn dựng chung giữa con người và máy móc. Chúng ta sẽ bắt đầu với một mô tả ngắn gọn về các bước chính.

⟦folio 51⟧

Các giai đoạn lời giải bài toán trên máy tính
1. Tạo một thuật toán
Trước hết cần tìm một thuật toán phù hợp cho lời giải cho trước bài toán. Các thuật toán dành cho máy chủ bài toán thường được phát minh và viết ra bởi các nhà toán học hoặc chuyên gia thông tin, đôi khi là cả một nhóm các nhà khoa học. Và trong những trường hợp đơn giản hơn, việc này sẽ được thực hiện bởi các chương trình - người chuyên nghiệp hoặc...người mới bắt đầu. Đối với nhiều người, bài toán một thuật toán tốt đã được biết đến - các ví dụ về các thuật toán như vậy có trong sách giáo khoa của bạn và sẽ được đưa ra trên các trang «Kvant», nhưng, theo quy định, chúng tôi sẽ tìm thấy lời giải bài toán từ tiếng Nhật một thuật toán phù hợp.

2. Lập trình
Để máy tính có thể sử dụng thuật toán mà chúng ta đã tạo ra, nó phải được viết dưới dạng chương trình bằng một trong các ngôn ngữ lập trình mà máy hiểu được. Các chương trình thường được viết bằng các ngôn ngữ như Algorithm, Fortran, Basic, Pacal, Rancha. Các chương trình được tạo sẵn, thường xuyên sử dụng sẽ được lưu trữ trong thư viện các chương trình tiêu chuẩn. Trong «Kvant» ở phần đầu, chúng ta sẽ viết các thuật toán bằng ngôn ngữ thuật toán, những kiến ​​thức cơ bản về ngôn ngữ này sẽ được nêu trong sách giáo khoa của bạn.

3. Nhập một chương trình vào máy tính
Ở giai đoạn hiện nay, có hai cách chính để nhập chương trình bằng văn bản vào máy tính. Phương pháp sử dụng đầu tiên, lỗi thời khi làm việc ở chế độ hàng loạt: chương trình ghi (mã hóa) dưới dạng đục lỗ (lỗ) trên thẻ đục lỗ và một bộ thẻ đục lỗ được đưa vào máy. Phương pháp thứ hai liên quan đến làm việc ở chế độ tương tác: chương trình hoặc người vận hành gõ chương trình trên bàn phím hiển thị, đồng thời giám sát tính chính xác của đầu vào trên màn hình.

4. Gỡ lỗi chương trình
Rõ ràng là chương trình có lỗi (điều này hầu như luôn xảy ra trong các chương trình lớn). Một số lỗi (gọi là lỗi cú pháp, hay lỗi khối) được máy tính báo ngay khi vào chương trình; những người khác có thể được lập trình viên phát hiện khi phân tích kết quả (kiểm tra hoặc chạy chương trình). Gỡ lỗi một chương trình là quá trình loại bỏ các lỗi được phát hiện trong đó. Bạn không thể thực hiện việc này một cách “thủ công” (không có sự trợ giúp của máy tính): để thực hiện việc này, bạn cần đặt mình vào vị trí của người dùng và cố gắng “cuộn qua chương trình” trong những tình huống đơn giản nhất.

⟦folio 52⟧

5. Phát sóng chương trình
Để máy thực thi chương trình được nhập vào hoặc phát hiện lỗi, máy phải có trình dịch từ ngôn ngữ lập trình mà chương trình được viết. Trình dịch—giống như trình dịch điện tử—chuyển các hướng dẫn của chương trình thành các thao tác đơn giản do máy trực tiếp thực hiện. Mặc dù việc triển khai trình dịch là một công việc rất phức tạp, đòi hỏi những người lập trình hệ thống có tay nghề cao nhưng chúng ta sẽ làm điều gì đó tương tự khi làm việc với máy tính vi mô.

6. Thực thi chương trình
Ở chế độ hàng loạt truyền thống, máy tự thực hiện giai đoạn công việc này mà không cần sự trợ giúp của con người: ở tốc độ khổng lồ, máy tính lần lượt thực hiện tất cả các hoạt động được cung cấp bởi chương trình dành riêng cho ngành. Trong một số chương trình tương tác, máy tính có thể đặt câu hỏi cho người dùng khi đang chạy và sau đó tiếp tục hoạt động. Bằng cách này hay cách khác, ở giai đoạn này chủ sở hữu là chiếc xe; ở đây sự vượt trội của nó so với con người được thể hiện ở tốc độ, độ chính xác và độ chính xác.

7. Đầu ra của kết quả
Các máy tính hiện đại có thể trình bày kết quả thực hiện chương trình dưới nhiều hình thức khác nhau. Kết quả (số, văn bản, bảng, hình) có thể được hiển thị trên màn hình hiển thị, được in trên ADPU (thiết bị in) hoặc được vẽ trên một tờ giấy bằng máy vẽ. Một số máy tính cá nhân được trang bị bộ mô phỏng âm thanh điện tử, trên đó chúng “phát” kết quả khi kết quả là một giai điệu.

Nếu không có máy tính thì sao?

Chúng tôi chủ yếu tập trung vào những học sinh bắt đầu học thông tin trong năm học này tại một trường chưa thành lập lớp học tin học. Những học sinh như vậy thường hỏi: tại sao lại viết một chương trình nếu nó không chạy trên máy tính thật?

Câu hỏi này rất giống với câu hỏi này - tại sao lại viết một bài luận nếu nó không được gửi đến nhà in? Và đáp số cũng tương tự: có thể thành thạo khả năng đọc viết trên máy tính mà không cần máy móc, cũng giống như có thể thành thạo khả năng đọc viết thông thường mà không cần đến kiểu chữ.

Tuy nhiên, hoạt động lập trình của bạn không nằm trong lĩnh vực lý thuyết thuần túy trong mọi trường hợp. Nếu trường học của bạn (hoặc nơi sử dụng) không có máy tính lớn, một số chương trình của bạn có thể chạy trên máy vi tính có thể lập trình (ví dụ: Elektronka BZ-34 hoặc MK-52), mà bạn phải có ở trường của mình.

⟦folio 53⟧

Tuy nhiên, chúng tôi sẽ không cố gắng biến độc giả của mình thành những chuyên gia lập trình máy tính vi mô. Điều chính đối với chúng tôi sẽ là tìm kiếm các thuật toán giải quyết một số bài toán nhất định, khả năng viết chương trình bằng ngôn ngữ thuật toán đặc biệt, được mô tả trong sách giáo khoa của bạn. (Theo quy định, chúng tôi sẽ viết chương trình trên máy vi tính dựa trên ký hiệu thuật toán này, tức là chúng tôi sẽ tự dịch (dịch) ký hiệu này thành mã hoạt động của máy tính.)

Dưới đây bạn sẽ thấy một số ví dụ về thuật toán và trong bài viết tiếp theo, chúng tôi sẽ nói chi tiết hơn về cách viết chúng bằng ngôn ngữ thuật toán.

Thuật toán

Từ “thuật toán” xuất phát từ tên của nhà khoa học vĩ đại thời Trung cổ al-Khorezmi (xem “Quant”, 1984, số 8, trang 29), nhưng ý nghĩa to lớn của khái niệm này chỉ trở nên rõ ràng vào nửa sau thế kỷ 20 gắn liền với sự phát triển của công nghệ máy tính và công nghệ thông tin. Khái niệm này chắc chắn đóng một vai trò trong toán học (về điều này, xem “Quant”, 1985, số 7, trang 9) - lý thuyết toán học của các thuật toán liền kề với một trong những lĩnh vực nổi tiếng nhất của toán học - logic toán học. Tuy nhiên, các thuật toán cũng được tìm thấy trong cuộc sống hàng ngày, hơn nữa, ở mỗi bước, dưới những cái tên như “hướng dẫn”, “đơn thuốc”, “sẽ giải quyết”, “phương pháp chung lời giải” và những thứ tương tự. Chính xác hơn, chúng ta có thể nói rằng thuật toán là một khái niệm và sự thể hiện chính xác của người thực hiện để thực hiện một chuỗi hành động nhằm đạt được một mục tiêu cụ thể hoặc lời giải đặt bài toán.

Người thực hiện thuật toán có thể là người hoặc thiết bị tự động (máy tính, máy tính, robot) có khả năng nhận biết lệnh và thực hiện các hành động được chỉ định trong đó.

Nguyên lý của thuật toán không chỉ là nhiều kỹ thuật toán học tổng quát, chẳng hạn như phép cộng số bằng stolnik hay thuật toán.

Euclid để tìm N.O.D., cũng như các công thức nấu ăn, gợi ý khi di chuyển bằng phương tiện công cộng đến một địa điểm nhất định, nhiều sách hướng dẫn vận hành, cũng như hướng dẫn, cách sử dụng điện thoại quốc tế, một số hướng dẫn nhất định về lắp đặt quân sự. Tuy nhiên, không phải mọi đơn thuốc đều là một thuật toán. Được biết đến từ thế giới truyện cổ tích, “Đến đó, tôi không biết ở đâu, mang cái đó đi, tôi không biết cái gì”, tất nhiên, không thể coi là một thuật toán: nó không đủ chính xác và dễ hiểu, cũng như không chỉ ra một chuỗi hành động cụ thể. Điều tương tự cũng có thể nói về mệnh lệnh chung dành cho sĩ quan tình báo “Hành động tùy theo tình hình!” Thuật toán phải cung cấp tất cả các tình huống có thể phát sinh trong quá trình thực thi và chỉ ra rõ ràng những việc cần làm trong mỗi tình huống đó.

Hãy xem một số ví dụ về bài toán và các thuật toán cung cấp chúng lời giải.

Bài toán tìm phần còn lại. Cho các số tự nhiên x và y; bạn cần tìm số dư khi chia x cho y.

Thuật toán đầu tiên (dành cho người biểu diễn - học sinh lớp 4-10):
— Viết x và y cạnh nhau trên một dòng;
- tách chúng bằng một góc;
— chia x cho y với một góc cho số đơn vị của số bị chia (x);
— xuất ra dưới dạng lời giải kết quả của phép trừ cuối cùng.

Thuật toán thứ hai (dành cho người biểu diễn - hạng nhất):
- So sánh x và y;
- nếu x < y, xuất x dưới dạng lời giải;
- nếu không thì tôi sẽ trừ y khỏi x và ghi nhớ sự khác biệt;
— nếu chênh lệch nhỏ hơn y, xuất nó dưới dạng lời giải;
