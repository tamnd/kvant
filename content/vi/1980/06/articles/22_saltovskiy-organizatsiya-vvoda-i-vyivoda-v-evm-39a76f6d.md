---
id: 1980-6-saltovskiy-organizatsiya-vvoda-i-vyivoda-v-evm-39a76f6d
issue: kvant_1980_6
year: 1980
number: "6"
title: Tổ chức đầu vào và đầu ra trong máy tính
authors:
  - Салтовский А. Н.
rubric: raznoe
rubric_sub: Разное
page_first: 50
page_last: 57
page_labels: 48-55
tag: S311
lang: vi
source: kvant_digital
extraction: vision
content_sha256: 82b51b0cb8d1e872692793c1f5532f8844cf3d8280390ccb08339de1a1b145fe
prompt_sha256: draft-1
translated_from: content/ru/1980/06/articles/22_saltovskiy-organizatsiya-vvoda-i-vyivoda-v-evm-39a76f6d.md
source_content_sha256: 0a7a25585594f1bb0a4b57d764b053b9cf158a2a95f4f1cc436b19381b12380e
translation_model: draft
translation_run: vi-draft-2026-10-31
translation_quality: draft
---

⟦folio 48⟧

A. Saltovsky

Tổ chức đầu vào và đầu ra trong máy tính

Bài viết này tiếp tục xuất bản nối tiếp về cấu trúc của máy tính (“Bộ nhớ máy tính” trong “Kvant số 4” và “Bộ xử lý hoạt động như thế nào” trong “Kvant số 5”).

Chế độ hàng loạt và hộp thoại
Tốc độ của bộ xử lý máy tính hiện đại đạt tới hàng trăm nghìn, hàng triệu thao tác mỗi giây. Với sự trợ giúp của nhiều kỹ thuật lời giải khác nhau với cùng tốc độ, có thể trao đổi thông tin giữa bộ xử lý và bộ nhớ.

Tình hình phức tạp hơn với việc cung cấp thông tin đến máy tính và kết quả tính toán được đưa ra từ máy. Những chức năng rất khác nhau này được thực hiện bởi các thiết bị đầu vào/đầu ra (I/O).

Giao tiếp trực tiếp giữa một người và một máy tính trong quá trình được gọi là đầu vào chương trình và dữ liệu "runic" từ bảng điều khiển, khi mỗi từ máy riêng lẻ được nhập vào máy của một người bằng một từ của người vận hành, tốn nhiều công sức ngay cả với các chương trình nhỏ. Trong chế độ hoạt động này, không thể bàn cãi về việc sử dụng máy tính hiệu quả. Một mặt, mâu thuẫn giữa tốc độ cao của bộ xử lý và bộ nhớ với sự không hoàn hảo của con người được giải quyết theo hai cách chính sau.

Trong phương pháp đầu tiên, thông tin dự định đưa vào máy tính được chuẩn bị trước trên một số phương tiện thông tin trung gian, ví dụ như thẻ đục lỗ, băng giấy đục lỗ hoặc băng từ. Các thiết bị giúp thực hiện công việc chuẩn bị trước khi nhập chương trình, dữ liệu vào máy tính gọi là thiết bị chuẩn bị, thêm tên thông tin –

Ảnh của V. Polykov và I. Fedorenko

⟦folio 49⟧

digital media - on punched cards, on punched tape or on magnetic tape (photo 1). Việc chuẩn bị thông tin trên phương tiện trung gian có thể được thực hiện mà không cần phải vội vàng vì các thiết bị chuẩn bị dữ liệu hoạt động độc lập với máy tính và không cần phải biên dịch tốc độ nhanh bằng máy. Đồng thời, một chương trình đã chuẩn bị sẵn (được đục lỗ trên thẻ hoặc băng đục lỗ, hoặc ghi trên băng từ) có thể được lưu trữ trong máy tính với tốc độ rất cao nhờ một đầu đọc đầu vào đặc biệt: đối với mỗi loại phương tiện có một thiết bị đầu vào cụ thể riêng. So với việc nhập thông tin “thủ công” từ bảng điều khiển máy tính, phương pháp chuẩn bị thông tin sơ bộ cho phép bạn giảm bớt quá trình sử dụng thiết bị máy tính tốc độ cao đắt tiền. This mode of entering information into the machine is called batch.

Điều quan trọng nhất có lẽ là thực tế là trong các hệ thống máy tính hiện đại, cùng với một điều khiển từ xa duy nhất (như trong các máy thế hệ đầu tiên), số lượng thiết bị đầu cuối đã tăng lên vài chục. Đồng thời, đối với mỗi người làm việc tại thiết bị đầu cuối, người dùng tạo ra ảo tưởng về công việc duy nhất với máy tính: thông tin mà mỗi chương trình yêu cầu sẽ được hiển thị ngay lập tức trên màn hình và thông tin mà chương trình nhập vào máy tính ngay lập tức được đặt vào đúng vị trí trong bộ nhớ. Chế độ giao tiếp với máy này được gọi là tương tác.

Lượng tử thời gian
để “trò chuyện” với máy tính

Khả năng đối thoại tương tác nhanh chóng giữa con người và máy tính dựa trên thực tế là phản ứng “tức thời” (theo quan điểm của con người) của máy thực sự xảy ra trong những khoảng thời gian tương đối lớn.

⟦folio 50⟧

trục thời gian (theo quan điểm của máy tính tốc độ cao): 40–100 mili giây ((40–100) · 10⁻³ s). Ví dụ: nếu một máy tính có khả năng thực hiện 10⁶ thao tác mỗi giây, thì đối với mỗi thao tác ngay lập tức và “ngay lập tức”, máy tính có thể thực hiện từ 40 đến 100 nghìn thao tác. Ví dụ: nếu mỗi người dùng - lập trình viên - được phân bổ một phần thời gian 5 mili giây, thì máy tính có thể "tiến" quá trình đối thoại với mỗi người trong số họ bằng 5000 lệnh trong thời gian này. Đó là lý do tại sao mọi người dùng đều chắc chắn rằng mình là người duy nhất làm việc với máy tính. Đúng vậy, một phần thời gian hoạt động của máy tính đã bị các chương trình quản lý và bảo trì - hệ điều hành “lấy đi”. Nếu trong ví dụ của chúng tôi, chúng tôi giả định rằng con người “ngay lập tức” là 100 mili giây, thì việc sử dụng khoảng thời gian này - 50 mili giây - sẽ được dành cho hoạt động của chương trình hệ điều hành. Sau đó, dựa trên tính toán rằng mỗi người dùng được phân bổ một phần 5 mili giây thời gian truy cập trực tiếp để làm việc với máy tính, chúng ta có thể nói rằng máy tính sẽ có thể “đồng thời”, duy trì ảo giác tức thời đáp số, giao tiếp với các lập trình viên đang hoạt động. Hệ điều hành được mô tả ở đây hoàn toàn mang tính minh họa. Điều quan trọng cần lưu ý là trong đó thời gian máy tính được phân phối giữa những người dùng một cách được quy định chặt chẽ. Trong việc này, hệ điều hành được hỗ trợ bởi đồng hồ điện tử của máy (còn gọi là “bộ hẹn giờ”) và hệ thống ngắt (xem “Cách thức hoạt động của bộ xử lý,” «Kvant», Số 5). Những hệ thống như vậy được gọi là hệ thống chia sẻ thời gian.

Hoạt động trao đổi cơ bản của sóng vô tuyến - Trí nhớ

Các thiết bị trên không giúp tổ chức giao tiếp giữa máy tính và thế giới bên ngoài. Sự trợ giúp nằm ở chỗ UVV đảm bảo chuyển đổi thông tin nhận được từ bên ngoài thành dạng thuận tiện cho việc xử lý trong máy tính. UVW cũng thực hiện chuyển đổi ngược lại: lời giải bài toán mà máy nhận được sẽ được xuất từ ​​máy sang thiết bị in. Tên thông thường của nó là

Ảnh 2.

tion - ATsPU, thiết bị in chữ và số (ảnh 3). Các máy tính hiện đại, trong số các phương tiện đầu ra của chúng, cũng có thể có nhiều thiết bị “kỳ lạ” hơn - một máy vẽ mô tả các hình vẽ trên giấy được lưu trữ ở dạng mã hóa trong bộ nhớ máy tính; photoguide - một thiết bị sử dụng chùm ánh sáng để tạo hình ảnh (slide) trên phim ảnh; một công cụ xây dựng phim cung cấp đầu ra của một loạt khung hình được vẽ trên phim, tức là phim hoạt hình, v.v.

Hoạt động của thiết bị trên không được điều khiển bằng các lệnh đầu vào/đầu ra. Chúng tạo thành một phần của hệ thống chỉ huy của máy. Một lệnh I/O thường chứa các thông tin sau:

Ảnh 3.

⟦folio 51⟧

Hình 1.

- loại (thường là số) thiết bị trên không mà người lập trình dự định làm việc;
- tính chất công việc - các luồng khí, theo quy luật, có thể hoạt động ở các chế độ khác nhau;
- lượng thông tin cần được truyền theo hướng này hay hướng khác.

Ngoài ra, lệnh đầu vào/đầu ra chứa thông tin điều khiển về địa chỉ nào (tại địa chỉ nào) trong bộ nhớ có thông tin dành cho đầu ra từ máy tính hoặc địa chỉ (địa chỉ) cần thiết để đặt thông tin đến máy tính từ thiết bị đầu vào.

Thông thường, giao tiếp của lập trình viên với máy tính bắt đầu và kết thúc bằng các lệnh đầu vào/đầu ra. Ngay từ đầu, các chương trình và dữ liệu được chuyển vào bộ nhớ, chẳng hạn như được chuẩn bị trước trên thẻ narfocard ngoại vi. Vào cuối phiên giao tiếp, ví dụ, kết quả sẽ được xuất ra ADPA. Từ sơ đồ đơn giản hóa này, có thể thấy rằng trong khi lệnh đầu vào/đầu ra đang được xử lý, thiết bị điều khiển (CU) kết nối bộ nhớ thông qua đường dẫn thông tin đến nguồn không khí đã chọn (Hình 1).

Đường dẫn thông tin là nơi lưu trữ ngắn hạn hoạt động của thông tin được truyền từ thiết bị này sang thiết bị khác. Tuy nhiên, một trong những đặc điểm của nó là độ rộng: lượng thông tin được truyền đi đồng thời. Do độ rộng của đường dẫn thông tin từ máy bay đến máy bay

thường ít hơn một từ máy, thông tin được chuẩn bị để truyền bắt đầu được tích lũy trước trong các điện trở đệm đặc biệt (Hình 2). Ví dụ, các máy tính hiện đại thuộc dòng EC cho phép trao đổi thông tin bằng bộ nhớ ở dạng từ kép (64 bit) và phần trao đổi chính trong truyền hàng không - bộ nhớ là một byte (8 bit). Tám byte được khớp trên thanh ghi bộ đệm 64 bit và sau khi thanh ghi bộ đệm đầy, các kết nối bộ nhớ sẽ được yêu cầu.

Ở những mẫu ô tô đời đầu, tại thời điểm giao tiếp, tôi khôi phục bộ nhớ của đơn vị logic số học (ALU). Tốt nhất, ALU tham gia vào việc đếm lượng thông tin được truyền theo byte hoặc từ máy. Với sự ra đời của bộ nhớ tốc độ cao, các khoảng dừng trong quá trình tập hợp hoặc phân tách thông tin sẽ có sẵn để trao đổi thông tin giữa P và ALU. Đây là sự gia tăng đáng kể về hiệu suất của máy tính, đặc biệt là các máy hoạt động ở chế độ đa chương trình.

Kênh là một bộ xử lý chuyên dụng

Hệ thống đầu vào-đầu ra của máy tính hiện đại nên
- chuyển đổi thông tin sang dạng thuận tiện cho việc truyền sang máy tính và khi cần thiết, thực hiện chuyển đổi ngược lại;

⟦folio 52⟧

- kết nối với bộ nhớ để trao đổi thông tin với luồng không khí và chỉ khi thực sự cần thiết, đồng thời tập hợp hoặc tách rời thông tin trong khi tạm dừng;

- cung cấp khả năng làm việc song song với các thiết bị máy tính khác, đặc biệt là với ALU;

— chỉ sử dụng các công cụ xử lý khi cần thiết: ​​ví dụ: để phân tích tình huống lỗi hoặc để kích hoạt các hoạt động I/O.

Trong trường hợp này, phương pháp kết nối thiết bị phun khí với hệ thống đầu vào-đầu ra, nếu có thể, phải phổ biến cho các loại thiết bị phun khí khác nhau.

Trong các máy tính hiện đại, các yêu cầu được liệt kê đối với hệ thống đầu vào-đầu ra được thực hiện bởi các thiết bị gọi là bộ xử lý đầu vào-đầu ra. Trong các máy dòng EC, chúng được gọi là các kênh.

Hình 3 cho thấy cấu trúc của EC-1060. Theo các khái niệm hiện đại, đây là một máy tính khá mạnh, có hai kênh - khu vực và bộ khuếch đại đa - khác nhau, trước hết, về đặc tính tốc độ: đối với kênh khu vực, thông lượng đạt 1,25 MB (1,25 × 22⁰ byte) mỗi giây; Kênh cung được kết nối với tốc độ sóng không khí - ổ đĩa từ (ảnh 4), máy ghi băng. Thông lượng tối đa cho các luồng thông tin truyền qua kênh nhiều loại là 600 KB (600×2¹⁰ byte) mỗi giây. Các thiết bị tốc độ thấp được kết nối với kênh nhiều loại - đây là máy đục lỗ, đầu đọc thẻ đục lỗ và băng đục lỗ, màn hình, máy đánh chữ điện tử và ADPU.

Định dạng lệnh kênh

Giống như hoạt động của máy tính được xác định bởi chương trình điều khiển nó, công việc của bộ xử lý chuyên dụng - một kênh - được điều khiển bởi một chương trình kênh dành cho bộ nhớ. Một chương trình kênh bao gồm một chuỗi các lệnh kênh, mỗi lệnh khiến kênh

⟦folio 53⟧

đáp ứng được định nghĩa về công việc. Trong một số trường hợp, không phải bằng cách xử lý mà bằng cách vận chuyển thông tin. Một định dạng lệnh kênh điển hình được trình bày trong Hình 4. Các trường chính trong định dạng này là:

- trường lệnh (mã hoạt động);
do thiết bị đầu vào/đầu ra có thể hoạt động ở các chế độ khác nhau nên trường lệnh mã hóa tính chất công việc mà kênh đã chọn và sóng vô tuyến tương ứng phải thực hiện; các thao tác điển hình nhất là “Đọc” và “Ghi”;

- trường địa chỉ dữ liệu, nghĩa là trường trong đó địa chỉ bắt đầu của một mảng thông tin dự định truyền qua kênh từ vụ nổ không khí (hoặc tới sóng không khí) được ghi lại;

- một trường thuộc tính trong đó các chi tiết nhất định về thông tin liên quan đến việc trao đổi được quy định.

Xử lý lệnh trong kênh
Hệ thống lệnh máy tính ES cũng chứa các lệnh đầu vào/đầu ra, nhưng không giống như các lệnh đầu vào/đầu ra, chúng chỉ thể hiện việc thực hiện ban đầu của một thao tác đầu vào/đầu ra. Vì vậy, ví dụ,

Lệnh vào/ra trong máy tính ES, được gọi là I/O Started, được phản ánh trong máy tính như sau:

— đầu tiên là lệnh từ bộ nhớ tới thanh ghi lệnh; Bộ điều khiển của bộ xử lý “nhận ra” nó, nghĩa là nó xác định rằng lò đang phản hồi cụ thể với lệnh khởi động I/O; sau đó, bằng cách sử dụng thông tin có trong lệnh địa chỉ, số kênh và thiết bị đầu vào/đầu ra mà quá trình trao đổi sẽ bắt đầu được xác định (Hình 5a);

- mỗi sóng được kết nối với kênh có số riêng; khi bất kỳ thiết bị vào/ra nào thuộc số của chính nó thì “xác nhận” đã nhận được lời mời liên lạc; Thông tin “xác nhận” chứa thông tin rằng thiết bị trên không có số hiệu như vậy đã thực sự sẵn sàng hoạt động (đặc biệt, thiết bị này không bị ngắt kết nối khỏi mạng); Trong khi thực hiện quy trình lấy mẫu mẫu ban đầu, kênh đồng thời truy cập vào một trong các ô nhớ được phân bổ cố định - từ địa chỉ kênh (ACK) được lưu trữ ở đó; ACK được gửi tới kênh; đặc biệt là ACK chứa địa chỉ bắt đầu của chương trình kênh (Hình 56), địa chỉ này sẽ được sử dụng trong quá trình trao đổi thông tin;

- kênh truy cập bộ nhớ tại địa chỉ được chỉ định trong ACK và

Xếp hạng miễn phí
Đội
Địa chỉ dữ liệu
Dấu hiệu
Quầy tính tiền
0 18 31 32 36 48 63
Hình 4.
KÊNH
Micro giây
Không vận số 1
Không vận số 2
Không vận số 3
Đội NBB
Thanh ghi lệnh
Lựa chọn kênh
tới Lực lượng Không quân số 2
Hình 5a.

⟦folio 54⟧

nhận lệnh kênh đầu tiên từ chương trình kênh; tuy nhiên, chương trình này có thể bao gồm một lệnh kênh duy nhất (Hình 5c);

— kênh bắt đầu giải mã lệnh kênh; nó gửi lệnh (bit 0-7 của lệnh kênh) đến thiết bị trên không, thiết bị này “nhận ra” số của nó ngay khi bắt đầu “tương tác” của bộ xử lý với kênh; nếu thiết bị trên không có khả năng thực hiện lệnh được đề xuất thì nó sẽ “phản hồi” với kênh, cho phép “bơm” thông tin (Hình 5d);

- sau đó, bộ xử lý “đánh giá” kênh và xử lý thông tin khác; kênh được “tích điện” quản lý thông tin hoạt động với bộ nhớ, thỉnh thoảng cung cấp bộ nhớ cho bộ xử lý;

- khi kênh xử lý lệnh kênh đầu tiên một cách bình thường (không ghi lại bất kỳ sự cố thiết bị nào, bất kỳ thẻ đục lỗ nào bị kẹt, v.v.), tiến trình hoạt động tiếp theo của kênh sẽ được xác định bằng cách quản lý thông tin trong trường thuộc tính (Hình 4) của lệnh kênh; đặc biệt, nếu thuộc tính “Chuỗi lệnh” hoặc thuộc tính “Chuỗi dữ liệu” được chỉ định trong đó, thì kết nối kênh với bộ nhớ có thể tiếp tục; danh bạ của họ trong trường hợp này không liên quan đến bộ xử lý (Hình 5d);

- nếu thông tin được hoàn thành thì kênh sẽ khởi động lại công việc của bộ xử lý; Trước khi truyền, kênh chuẩn bị một “từ trạng thái kênh” (CCW) trong thanh ghi đệm, trong đó nó báo cáo ở dạng mã hóa tất cả các điều kiện kết thúc phiên giao tiếp, yêu cầu truyền được gửi đến bộ xử lý và đồng thời CSC được ghi vào một trong các ô nhớ cố định; hệ điều hành được giải mã

⟦folio 55⟧

xác định các trường hợp kết thúc và tùy theo chúng mà chấp nhận lời giải: ví dụ: tiếp tục làm việc hoặc in yêu cầu tới người vận hành để thay cuộn băng từ thành từ tính, v.v.

Mặc dù việc truy xuất lệnh kênh gợi nhớ đến việc sáng tác một câu chuyện cổ tích đầy ý nghĩa: một cái kim trong một quả trứng, một quả trứng trong một con vịt, một con vịt trong một con thỏ..., hiệu quả của việc tổ chức I/O như vậy là cực kỳ cao.

KIỂM SOÁT TRAO ĐỔI THÔNG TIN
Mọi quá trình truyền thông tin tới máy tính đều được kiểm soát. Để điều khiển, mỗi đường dẫn thông tin được kèm theo các bit bổ sung, được gọi là các bit điều khiển. Mục đích của chúng là lượng bit bổ sung được truyền trong một khoảng thời gian (chu kỳ) nhất định, lên tới số lẻ. Ví dụ,

một byte 0 được kèm theo một byte trong bit kiểm tra. Do đó, 9 dây được sử dụng để truyền một byte (dây thứ chín giống với bit). Bit điều khiển được hình thành trong nguồn thông tin bằng mạch logic đặc biệt; Người nhận thông tin, sau khi nhận được byte, cũng tạo ra một bit điều khiển. Việc truyền thông tin được coi là hoàn thành thành công nếu các bit điều khiển của nguồn và máy thu khớp nhau. Phương pháp điều khiển này được gọi là “tích chập modulo 2”. Dễ dàng nhận thấy phương pháp này không phát hiện được lỗi ở số bit chẵn. Có các phương pháp kiểm soát phần cứng cho phép bạn phát hiện lỗi kép.

ĐỌC TIẾP THEO:

1. FLORES A. Tổ chức máy tính. (M., “Mir”, 1972).
2. FLORES A. Thiết bị máy tính bên ngoài (M., “Mir”, 1977).
