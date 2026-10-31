---
id: 1987-4-krutogin-po-stolbovyim-dorogam-mk-78472f24
issue: kvant_1987_4
year: 1987
number: "4"
title: Dọc các tuyến đường chính của MK
authors:
  - Крутогин Д. Г.
rubric: raznoe
page_first: 17
page_last: 19
page_labels: 15-17
tag: AZJH
lang: vi
source: kvant_digital
extraction: vision
content_sha256: 3c2ae686d441fa21c660abc289d91b7e959cf1872dd53d9e76c154a606694cd5
prompt_sha256: draft-1
translated_from: content/ru/1987/04/articles/05_krutogin-po-stolbovyim-dorogam-mk-78472f24.md
source_content_sha256: ff82eb9a8a1734fa5dd5a3c63f8ecc04dcc57fc9efcc80653749cb43c6af5339
translation_model: draft
translation_run: vi-draft-2026-10-31
translation_quality: draft
---

⟦folio 15⟧

BẰNG TRỤC TRỤ
ĐƯỜNG MK

(Hành trình qua máy vi tính)
Ứng viên Khoa học Kỹ thuật D. G. KRUTOGIN

Từ việc xem toàn cảnh và nghiên cứu quy hoạch thành phố MK (xem «Kvant» Số 2, 3), chúng ta hãy chuyển sang chuyến tham quan nó. Hôm nay mục tiêu của chúng tôi là đánh bại RAM và ROM trong các khu “dân cư” của thành phố. Chúng ta sẽ đến đó dọc theo con đường chính của thành phố, được gọi là “xe buýt chung” và kết nối tất cả các quận trong thành phố. Trên thang đo được chấp nhận*), di chuyển dọc theo lốp xe, chúng ta sẽ thấy dưới chân mình có mười dải kim loại nguyên thủy có kích thước 1 × 2 m (hình 1). Nhìn bề ngoài thì không thể phân biệt được chúng, nhưng theo kế hoạch, chúng ta biết rằng những đường ray này tạo thành ba hệ thống đường hoặc ba xe buýt riêng biệt. Bus rộng nhất là bus địa chỉ. Nó nhằm mục đích phân phối các từ máy vào các ô nhớ khi viết và gọi lại chúng từ đó khi đọc. Các ô nhớ được tổ chức thành một ma trận (hình2); việc lựa chọn ô mong muốn được thực hiện khi

*) Chúng tôi xin nhắc bạn rằng trong cuộc hành trình chúng ta sẽ phải thu nhỏ lại hàng triệu lần.

15

⟦folio 16⟧

sức mạnh của tín hiệu địa chỉ Tổ chức ma trận của các thiết bị lưu trữ là hợp lý nhất về tính dễ điều khiển và số lượng dây cần thiết.

Hai bus còn lại—bus dữ liệu và bus điều khiển—thường chứa ít dây hơn. Bus dữ liệu, không giống như các bus khác, có chuyển động tổ chức hai chiều (hướng tới hoặc rời khỏi quy trình).

Tốc độ giao thông trên đường phố thành phố luôn ở mức cao. Nhưng có ít đường phố và có nhiều người đi lại dọc theo đó nên xe buýt dữ liệu sẽ bận rộn trong thời gian dài. Để tránh giao thông và tai nạn đang tới, gần các lối ra đường chính ở tất cả các khu vực đều có các “trạm cảnh sát giao thông” duy nhất - vùng đệm thiết lập chế độ theo cách đã thống nhất

Hình 1. Mảnh vỡ của lốp xe. Ảnh có độ phóng đại khoảng 2000.

Hình 2. Sơ đồ tổ chức RAM ma trận 4×4 bit. Hình vuông biểu thị các ô RAM, hình tam giác biểu thị bộ đệm đầu vào, được đặt ở chế độ ghi hoặc đọc; X và Y là dây bus địa chỉ, PШ₀, PШ₁ là dây bit của bus dữ liệu.

Giao thông đường phố. Bộ đệm ngăn chặn sự di chuyển của các từ cá bởi một đám đông không có tổ chức; họ xếp chúng thành những cột dày đặc và gửi chúng đến đích. Việc trao đổi tích cực nhất sẽ diễn ra giữa các khu vực Bộ xử lý và RAM.

Giả sử rằng một yêu cầu được gửi từ Bộ xử lý tới RAM đối với một từ nhất định có trong một ô nhớ nhất định. Điều này có nghĩa là các xung tương ứng với tọa độ của ô này được gửi đến các dây bus địa chỉ, đồng thời lệnh đọc được gửi qua bus điều khiển. Ở lối vào vùng RAM, lệnh này được biểu thị bằng cách ghi vào các ô nhớ của thanh ghi đệm *). Sau đó, quá trình depyrization và thực hiện lệnh bắt đầu. Theo quy định, các tín hiệu phản hồi của ô (một tín hiệu cho mỗi bit của từ được yêu cầu) không đi trực tiếp đến bus dữ liệu mà lại đến thanh ghi đệm của bus này. Khi nó đầy, tức là word-đáp số được hình thành, bộ chuyển đổi bộ đệm sẽ chuyển toàn bộ nội dung của thanh ghi này tới Bộ xử lý. Đồng thời, lệnh yêu cầu không còn cần thiết sẽ bị xóa khỏi thanh ghi đệm bus điều khiển. Khi đến đích (giả sử là trong bộ xử lý), từ - đáp số RAM - sẽ lại được đặt trong “bộ tiếp nhận”, thanh ghi bộ đệm riêng của quy trình.

Chúng tôi đã nói rằng hoạt động hiệu quả của Bộ xử lý đảm bảo bộ nhớ nhanh và đủ lớn. Để nhanh chóng tìm thấy thông tin cần thiết, các nhà thiết kế đã chia vùng RAM thành các khối - trang. Tuy nhiên, một trang là một ma trận gồm 16x16 ô, tức là 256 ô có khả năng lưu trữ thông tin nhị phân. Nếu trang của chúng tôi là 256 thì tổng dung lượng RAM là 2562.

Các bóng bán dẫn phần tử logic được đặt ở đầu vào của mỗi trang tư. Giống như gửi thư ghim, điều này yêu cầu mã trang và mã ô phải có trong địa chỉ. Vì vậy, bản thân địa chỉ là một từ máy.

Thành phố đón khách

Ô lưu trữ một chút thông tin trong RAM là một flip-flop và thường chứa bốn bóng bán dẫn. Trước đây chúng ta coi một bóng bán dẫn là một ngôi nhà, bây giờ sẽ thích hợp hơn nếu coi nó là một trong những tòa nhà

*) Sau đây, chúng ta sẽ sử dụng thuật ngữ “đăng ký” để chỉ bộ nhớ RAM nhỏ có dung lượng bằng một hoặc hai từ máy.

⟦folio 17⟧

Hình 3. Ô RAM tĩnh có dung lượng 1 bit: a) - một ô không được điều khiển có hai trạng thái bằng nhau, b) - một bộ ba có hai đầu vào dựa trên một ô đó.

Hình 4. Pritsitsit hoạt động trí nhớ động.

nhà di động *). Mạch kích hoạt được kỹ sư vô tuyến người Nga M.A. BonchBruevich mô tả gần 70 năm trước. Cách kích hoạt đơn giản nhất của hai bóng bán dẫn được hiển thị ở hình 3, a. Trong hai bóng bán dẫn, một bóng bán dẫn luôn đóng, bóng kia luôn mở. Bằng cách đưa một tín hiệu ngắn từ bên ngoài vào một bóng bán dẫn đóng, vị trí có thể được thay đổi thành đối xứng và ngược lại. Thiết kế này được gọi là tế bào có thể ổn định được. Để điều khiển linh hoạt, bạn cần lắp thêm hai công tắc bóng bán dẫn vào đó. Trên thực tế, mạch mà bạn nhìn thấy trên hình 3, b là một ô nhớ kích hoạt 1 bit. Đây là một yếu tố xây dựng điển hình của quận OZU. Bộ nhớ như vậy trên trigger được gọi là tĩnh. Nó hoạt động nhanh chóng và đáng tin cậy, nhưng... Việc xây dựng một “ngôi nhà” gồm bốn bóng bán dẫn cho mỗi bit trở nên rất cồng kềnh khi số lượng lên tới hàng trăm nghìn bit (RAM của máy vi tính hiện đại phải có dung lượng ít nhất là 64 kB). Điều chính là không có đủ dung lượng cho RAM.

Do đó, đối với RAM lớn, một hệ thống bộ nhớ khác được sử dụng, nguyên lý của hệ thống này xuất hiện ở hình 4. Nếu tụ C được sạc qua phím S, thì sau khi mở phím, tụ điện sẽ duy trì chế độ của bóng bán dẫn T, được chỉ định bởi tín hiệu sạc ban đầu. Do đó, chế độ bóng bán dẫn (mở hoặc đóng) dường như lưu trữ một bit thông tin; nhưng cho đến khi nào? Cho đến khi tụ điện C*) được phóng điện. Công tắc S, như mọi khi trong vi điện tử, là một bóng bán dẫn và điện trở của nó cao nhưng không phải là vô hạn.

Để ngăn tụ điện bị phóng điện và bit được lưu trữ không bị mất, điện dung C phải được sạc lại định kỳ (khoảng 500 lần mỗi giây!), như thể đang “làm mới” bộ nhớ. Bộ nhớ dễ bị rò rỉ như vậy được gọi là động. Khi tính đến các hệ thống bảo trì, mạch RAM nói chung phức tạp hơn nhiều so với trên hình 4, nhưng vẫn đơn giản và tiết kiệm hơn so với trên flip-flop. Trong RAM động, có thể giảm mức tiêu thụ điện năng xuống 2,5 bóng bán dẫn mỗi bit. Ngày nay, mạch diac đạt công suất 1 Mbps trên khuôn silicon 7 x 9 mm. Đây là kỷ lục về mật độ xây dựng.

Rời khỏi khu vực RAM, có thể nói rằng kiến ​​trúc của nó tuy hợp lý nhưng vẫn rất đơn điệu. Đây thường là đặc điểm của các khu dân cư mới và trong các thành phố của chúng ta. Lưu ý rằng không có vùng trọng lượng nào của RAM được cung cấp cho máy khách vi tính; Một số trang, đôi khi lên tới 50%, được chính Bộ xử lý sử dụng để lưu kết quả tính toán trung gian, lưu trữ chương trình bảo trì, v.v.

Thành phố dành cho nông nghiệp

Bây giờ chúng ta hãy chuyển sang khu vực ROM, nó nằm ở gần đó. Có nhiều thành phần chung trong cấu trúc của RAM và ROM, ví dụ như tổ chức ma trận bộ nhớ, thiết bị logic và bộ đệm đầu vào, v.v. Tuy nhiên, cũng có những khác biệt. Vâng, trước hết, cư dân thường trú của thành phố của chúng tôi được cung cấp chỗ ở ở đây. Họ kiên định đến mức không bao giờ rời khỏi khu dân cư của mình. Bất cứ ai đã đọc cuốn tiểu thuyết ngắn “Thứ Hai bắt đầu vào thứ Bảy” của A. và V. Strugatsky đều có thể nhớ rằng nhân vật chính của nó, những nhà nghiên cứu nhiệt tình tại Viện Ma thuật và Pháp sư (NIICHAVO), đã tạo ra các bản sao của riêng họ, hoặc “nhân đôi” để thực hiện các nhiệm vụ thường ngày khác nhau. Các lệnh nằm trong ROM, không có bất kỳ tương tác nào và không gây hại khi liên tục tạo ra các “bản sao” theo yêu cầu của Bộ xử lý. Khi ở trên bus dữ liệu, tín hiệu “nhận” không khác gì các tín hiệu lệnh khác. Ma trận quốc gia

*) Trong điện toán, thuật ngữ “ô” được dùng để chỉ chuỗi kích hoạt có khả năng lưu trữ 1 byte = 8 bit hoặc một từ máy. Chúng tôi đang đơn giản hóa phần nào cấu trúc RAM cho người mới làm quen lần đầu.

*) Không có tụ điện C đặc biệt trong vi mạch. Trước đây chúng tôi đã chỉ ra («Kvant», 1986, Số 2) rằng bóng bán dẫn trong SVIS thường được sử dụng làm điốt hoặc tụ điện.
