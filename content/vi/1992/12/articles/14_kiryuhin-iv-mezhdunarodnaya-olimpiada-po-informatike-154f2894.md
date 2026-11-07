---
id: 1992-12-kiryuhin-iv-mezhdunarodnaya-olimpiada-po-informatike-154f2894
issue: kvant_1992_12
year: 1992
number: "12"
title: Olympic Tin học quốc tế lần thứ IV
authors:
  - Кирюхин В. М.
rubric: olimpiady
rubric_sub: Олимпиады
page_first: 58
page_last: 63
page_labels: 56-61
lang: vi
source: kvant_digital
extraction: vision
content_sha256: 79806f40aad274c862ced5ca2115ee3a3845dcd2d034025feea7eaa01cba21db
prompt_sha256: draft-1
translated_from: content/ru/1992/12/articles/14_kiryuhin-iv-mezhdunarodnaya-olimpiada-po-informatike-154f2894.md
source_content_sha256: ca957c24f985a0ec0e1382e81a5a7ac215fd2d49333ca96f52108f7c3f01151c
translation_model: draft
translation_run: vi-draft-gaps-2026-11-07
translation_quality: draft
---

⟦folio 56⟧

Olympic thông tin quốc tế lần thứ IV

Ứng viên khoa học kỹ thuật
V. KIRYUKHIN

Năm nay, Đức đăng cai Olympic Thông tin Quốc tế (IOI-92). Thế vận hội diễn ra từ ngày 12 đến ngày 21 tháng 7 tại Bonn và thu thập khuyến nghị từ những người tham gia. Tổng cộng có đại diện từ 50 quốc gia từ tất cả các châu lục đã tham gia. 166 học sinh từ 45 quốc gia trên thế giới đã tham gia cuộc thi và mỗi đội không quá bốn người.

Sự tham gia của một số lượng lớn người tham gia vào quỹ đạo Olympic minh chứng cho sự ngày càng gia tăng về mức độ phổ biến của Olympic Thông tin Quốc tế và sự chú ý mà nhiều quốc gia trên thế giới đang dành cho việc tìm kiếm và đào tạo các tài năng trẻ trong lĩnh vực thông tin và công nghệ máy tính. Việc tham gia vào đội MOI-92 của Hoa Kỳ, Hàn Quốc, Úc, Nam Phi đã làm tăng đáng kể và làm tăng tính cạnh tranh vốn đã rất cao để giành quyền trở thành người chiến thắng tại Olympic.

Tại Olympic hiện tại, Nga, Ukraina, Belarus và các nước vùng Baltic được đại diện bởi các đội riêng biệt. Đội tuyển quốc gia Nga dựa trên kết quả của Thế vận hội Olympic quốc gia, Thế vận hội của các quốc gia CIS và vùng Baltic, cũng như các trại huấn luyện bao gồm các sinh viên tốt nghiệp từ Hoa Kỳ. 82 làng Chernogolovka, khu vực Moscow Sergei Yuffe, tốt nghiệp Trung tâm khoa học Đại học quốc gia Moscow Dmitry Zhukov và Evgeniy Kuzne-

⟦folio 57⟧

---
running_head:
folio:
---

cũng như Dmitry Davydok, một sinh viên tốt nghiệp của làng. w. 239 St.Petersburg.

Ủy ban trù bị quốc gia của MOI-92, do Giáo sư F. Kriokebert và Tiến sĩ P. Heiderhof đứng đầu, đã làm mọi thứ có thể để tổ chức thành công Thế vận hội. Nhân dịp khai mạc MOI-92, thị trưởng Bonn đã tổ chức tiệc chiêu đãi tại tòa thị chính. Lễ khai mạc Olympic đã diễn ra tại nơi ở của ban giám đốc Trung tâm nghiên cứu khoa học máy tính và công nghệ thông tin quốc gia (GMD). Có rất nhiều lời nói tử tế và lời chia tay dành cho các chàng trai lời giải trong lễ khai mạc, nhưng tất cả những suy nghĩ của họ đều gắn liền với những thành tựu trong tương lai. Mọi người đều cố gắng trả lời câu hỏi - liệu anh ấy có thành công trong việc trở thành nhà vô địch Olympic hay không.

Theo truyền thống, MOI-92 được tổ chức thành hai vòng. So với các kỳ Olympic quốc tế trước đây, thời lượng của mỗi vòng thi tại Olympic này đã tăng lên năm giờ. Trong cả hai vòng, những người tham gia Olympic được tặng một bài toán, được các thành viên ban giám khảo quốc tế lựa chọn ngay trước khi vòng thi bắt đầu từ gói bài toán do ủy ban khoa học chuẩn bị. Theo kết quả bỏ phiếu, bài toán sau đây đã được chọn.

Bài toán Tour “Đảo trên biển”

Vị trí của các đảo trên biển được thể hiện bằng lưới có kích thước $N \times N$. Mỗi hòn đảo được biểu thị bằng ký hiệu "" tại một nút của lưới này. Bài toán là tái tạo lại bản đồ các đảo biển từ thông tin được mã hóa về sự phân bố các đảo theo chiều ngang và chiều dọc. Để minh họa nguyên tắc mã hóa khoảng cách, bản đồ sau và các mã tương ứng của nó:

* * * 1 2
* * * * 3 1
* * * * 1 1 1
* * * * * 5
* * * * * 2 1 1
* * 1

Các con số bên phải bản đồ trên hình này là mã số và thể hiện thứ tự cũng như quy mô của nhóm đảo trong lưới ngang tương ứng. Ví dụ: các số "1 2" ở hàng đầu tiên cho biết chiều ngang đầu tiên chứa một nhóm gồm một hòn đảo, tiếp theo là nhóm gồm hai hòn đảo.

Bên trái và bên phải của mỗi nhóm đảo có một biển có chiều dài tùy ý. Tương tự như vậy, chuỗi "1 1 1" ở cột đầu tiên dưới bản đồ đảo có nghĩa là trục dọc đầu tiên chứa ba nhóm đảo, mỗi nhóm có một hòn đảo, v.v.

Sản xuất bài toán

Viết chương trình thực hiện các hành động (các bước) sau cho đến khi một tệp đầu vào nhất định, chứa một số khối thông tin độc lập, được đọc hoàn toàn:

1. Đọc khối thông tin tiếp theo từ tệp ASCII đầu vào (cấu trúc của tệp truyền này trong ví dụ 1) và hiển thị nó trên màn hình.

Ví dụ 1

6
1 2 0 ← đường ngang đầu tiên
3 1 0
1 1 1 0
5 0
2 1 1 0
1 0
1 1 1 0 ← hàng cho cột đầu tiên
1 2 0
4 0
2 3 0
2 0
1 2 0

Ví dụ 2

Khối đầu vào
4 Cột 1 2 3 4
0 Dòng 1
1 0 Dòng 2 *
2 0 Dòng 3 * *
0 Dòng 4
0
1 0
2 0
0

Ví dụ 3

2
0
0
2 0
2 0

Không có bản đồ cho dữ liệu này.

Ví dụ 4

2
1 0
1 0
1 0
1 0

Dữ liệu này được đáp ứng bởi hai thẻ khác nhau.

Mỗi khối thông tin bắt đầu bằng một kích thước lưới hình vuông, theo sau là một nhóm gồm hai hòn đảo.

⟦folio 58⟧

---
running_head:
folio:
---

Không có thông tin mã nào về sự phân bố theo chiều ngang và chiều dọc của các hòn đảo. Mã cho mỗi dòng ngang và dọc riêng lẻ là một dòng riêng biệt của tệp và là một dãy số được phân tách bằng dấu cách. Mỗi dòng kết thúc bằng số 0. Trong trường hợp này, đầu tiên có thông tin về tất cả các thông tin theo chiều ngang, sau đó là về các thông tin theo chiều dọc.

2. Khôi phục một thẻ (hoặc tất cả các thẻ trong trường hợp có nhiều hơn một lời giải, như trong ví dụ 4) và hiển thị (chúng) trên màn hình.

3. Thêm (các) bản đồ vào cuối tệp ASCII cao. Mỗi vị trí đường dẫn trong lưới phải được biểu thị bằng hai dấu cách và mỗi hòn đảo phải được biểu thị bằng dấu "*" (dấu hoa thị và dấu cách). Trong trường hợp lời giải không rõ ràng, các thẻ khác nhau phải cách nhau bằng một đường dẫn. Nếu không thể khôi phục bản đồ, hãy viết “không có bản đồ” vào dòng thứ hai của tệp đầu ra. Lời giải liên quan đến các khối thông tin khác nhau trong tệp đầu vào phải được phân tách trong tệp đầu ra bằng một dòng có nhãn “vấn đề tiếp theo”.

Hạn chế về mặt kỹ thuật

1. N không được nhỏ hơn 1 và không lớn hơn 8.

2. Chương trình kết quả phải được đặt trong tệp văn bản ASCII có tên "C:\IOI\DAY-1\413-PROG.xxx". Phần mở rộng .xxx cho PASCAL là .PAS, cho C là .C, cho BASIC là .BAS, cho LOGO là .LOG.

3. Tên tệp đầu vào ASCII phải là "C:\IOI\DAY-1\413-SEAS.IN".

Nhiệm vụ vòng 2 “Chinh phục đỉnh cao”

Câu lạc bộ leo núi gồm có các thành viên P, được đánh số từ 1 đến P. Mỗi người leo núi leo núi với tốc độ như nhau và tốc độ thay đổi không khác gì tốc độ đi xuống. Một người leo núi với số i tiêu tốn C(i) đơn vị tài nguyên mỗi ngày cả trong quá trình đi lên và đi xuống và không thể mang theo nhiều hơn S(i) đơn vị tài nguyên đó tại bất kỳ thời điểm nào.

Giả sử rằng một người leo núi có thể lên đến đỉnh trong N ngày với đầy đủ nguồn lực cho cả việc leo lên và đi xuống. Ngọn núi có thể cao đến mức ban đầu một người leo núi không thể mang theo tất cả các nguồn lực cần thiết cho việc đi lên và đi xuống. Vì vậy, một nhóm người leo núi xuất phát ở cùng một địa điểm và cùng lúc để đảm bảo quá trình đi lên. Một người leo núi có thể bắt đầu đi xuống, không lên tới đỉnh, đồng thời cung cấp tất cả các nguồn lực mà anh ta không cần để đi xuống cho những người leo núi khác, những người có thể lấy chúng. Những người leo núi không tách rời trong chuyến thám hiểm.

Nhiệm vụ là lập lịch trình leo núi cho câu lạc bộ leo núi.

Ít nhất một người leo núi phải lên đến đỉnh núi và tất cả những người leo núi trong nhóm leo núi phải quay lại điểm xuất phát sau khi sử dụng hết tài nguyên.

Sản xuất bài toán

Viết chương trình thực hiện các công việc sau:

1. Nhập từ bàn phím số ngày N cần thiết để lên đến đỉnh núi, số P của các thành viên câu lạc bộ và các số S(i), C(i) với tất cả i từ 1 đến P.

Tất cả dữ liệu đầu vào đều là số nguyên, dữ liệu thực sẽ không được nhập. Lặp lại yêu cầu dữ liệu không có ý nghĩa.

2. Xác định lịch trình đi lên cũng như số lượng người leo núi a(1), a(2), ... a(k), tạo thành các nhóm để đi lên và các số M(j) (cho tất cả j từ 1 đến k), cho biết số lượng đơn vị tài nguyên mà mỗi người leo núi đã lấy khi bắt đầu.

Thông báo nếu không thể tạo lịch trình như vậy cho N, S(i) và C(i) đã cho.

3. Hiển thị các thông tin sau trên màn hình:

a) số k người leo núi tham gia leo núi (quy mô nhóm leo núi);

b) tổng số nguồn lực cần thiết cho việc này;

b) số người leo núi tham gia leo núi a(1), a(2), ..., a(k).

d) với mỗi a(j) - anh ta mang theo bao nhiêu đơn vị tài nguyên ngay từ đầu;

d) với mỗi a(j) - số ngày sau đó anh ta sẽ học cách đi xuống.

4. Lịch trình được tìm thấy phải gần với mức tối ưu. Lịch trình là tối ưu nếu:

a) số lượng người leo núi tham gia leo núi cần thiết để một trong số họ lên tới đỉnh là tối thiểu;

b) mức độ tham gia trung bình của nhóm, tổng số đơn vị nguồn lực được mang theo ngay từ đầu là tối thiểu.

Hạn chế về mặt kỹ thuật

1. Đặt chương trình kết quả của bạn vào tệp văn bản ASCII có tên "C:\IOI\DAY-2\422-PROG.xxx". Phần mở rộng .xxx cho PASCAL là .PAS, cho C là .C, cho BASIC là .BAS, cho LOGO là .LOG.

2. Chương trình không nên chấp nhận dữ liệu đầu vào nếu N<1 hoặc N>100, cũng như P<1 hoặc P>20.

Ví dụ:

Cuộc đối thoại sau đây với chương trình của bạn có thể xảy ra:

Số ngày cần thiết để lên tới đỉnh - 4

Số người leo núi trong câu lạc bộ - 5

Nguồn lực tối đa cho người leo núi 1 - 7

⟦folio 59⟧

---
running_head:
folio:
---

Tiêu thụ tài nguyên hàng ngày cho người leo núi 1 - 1
Nguồn lực tối đa cho người leo núi 2 - 8
Tiêu thụ tài nguyên hàng ngày cho người leo núi 2 - 2
Nguồn lực tối đa cho người leo núi 3 - 12
Tiêu thụ tài nguyên hàng ngày cho người leo núi 3 – 2
Nguồn lực tối đa cho người leo núi 4 - 15
Tiêu thụ tài nguyên hàng ngày cho người leo núi 4 - 3
Nguồn lực tối đa cho người leo núi 5 - 7
Tiêu thụ tài nguyên hàng ngày cho người leo núi 5 - 1
Cần có 2 người leo núi để lên tới đỉnh.
Tổng cộng cần 10 đơn vị tài nguyên cho việc này.
Người leo núi 1 và 5 sẽ leo lên.
Climber 1 sẽ lấy 7 đơn vị tài nguyên và bắt đầu đi xuống sau 4 ngày.
Climber 5 sẽ lấy 3 đơn vị tài nguyên và bắt đầu đi xuống sau 1 ngày.
Bạn muốn lên kế hoạch leo núi cho một câu lạc bộ leo núi khác? (Có/Không) —↓.
Số ngày cần thiết để lên top - 2
Số người leo núi trong câu lạc bộ - 1
Nguồn lực tối đa cho người leo núi 1 - 3
Tiêu thụ tài nguyên hàng ngày cho người leo núi 1 - 1
Sự thăng thiên là không thể.
Muốn lên kế hoạch leo núi cho một câu lạc bộ leo núi khác (Y/N) - N. Goodbye.

Trong thời gian diễn ra Thế vận hội, mỗi người tham gia được cấp một máy tính cá nhân IBM PC AT (286). Tất cả các máy tính được kết nối bởi một mạng cục bộ. Đối với lời giải đề xuất bài toán chỉ được phép sử dụng một trong các hệ thống lập trình được cài đặt trên máy tính: Turbo Pascal v. 5.5 và v. 6.0, Borland C++ v. 2.0 và Microsoft C v. 5, Quick C, Quick Basic v. 4.5 và GWBasic, LCN Logo v. 2.

Phần lớn người tham gia Olympic đã chọn Turbo Pascal từ các hệ thống lập trình được đề xuất, với 69 người sử dụng top 6.0 và 42 người sử dụng top 5.5. Có 14 người làm việc trong môi trường lập trình C++. Mười một vận động viên Olympic đã sử dụng Quick Basic. Các hệ thống còn lại chiếm số lượng người tham gia không đáng kể.

Tất cả các chương trình đều được những người tham gia trình bày dưới hình thức điều hành để ban giám khảo quốc tế và ban chỉ đạo xem xét. Công việc của họ được đánh giá chính xác bằng các bài kiểm tra có tính đến các thông số kỹ thuật đầu vào-đầu ra được đưa ra trong điều kiện bài toán. Các tiêu chí đánh giá cũng được bao gồm trong các điều kiện bài toán và bài kiểm tra được thực hiện theo đúng các điều kiện đó. Bảng 1, 2 trình bày chi tiết cho từng bài toán.

Bài toán của cả hai vòng hóa ra có độ phức tạp gần như nhau đối với các cuộc đua thuyền, mặc dù bài toán của loại thứ hai có một số khoảnh khắc khó khăn hơn. Kết quả của Thế vận hội nói lên điều này. Nhiều người tham gia đã hoàn thành hoàn toàn bài toán của cả hai vòng, đạt được số điểm tối đa.

Cuối cùng, 12 vận động viên Olympic nhận được 200 điểm. Ban giám khảo quốc tế đã cân nhắc rất lâu về cách phân chia giải thưởng giữa họ, vì giải thưởng chính là máy tính các loại (bao gồm cả máy tính xách tay), hóa ra lại ít hơn con số này. Do đó, theo thông lệ, lời giải xác định những sinh vật sở hữu sự công nhận thân yêu bằng cách rút thăm. Ngoài ra, họ đều nhận được huy chương vàng. Trong số đó có 3 học sinh đến từ Trung Quốc, 2 học sinh đến từ Mỹ và Thái Lan, và 1 học sinh đến từ Hungary, Việt Nam, Tiệp Khắc, Thụy Điển và Hàn Quốc. Người ta cũng quyết định trao huy chương vàng cho vận động viên đến từ Thụy Điển, người đạt 198 điểm.

Bảng 1

Đã xếp hạng lời giải

1. Đọc một khối thông tin từ một tập tin đầu vào và hiển thị nó trên màn hình
2. Xử lý từng khối thông tin một cho đến khi đọc xong file đầu vào
3. Khôi phục 1 thẻ cho mỗi khối thông tin (nếu lời giải tồn tại) và hiển thị lên màn hình
4. Viết bản đồ lời giải vào tệp đầu ra
5. Khôi phục tất cả các thẻ có thể (nếu lời giải không được sử dụng) và hiển thị chúng trên màn hình
6. Viết các bản đồ được phân tách chính xác lời giải vào tệp đầu ra
7. Xác định các khối thông tin không tồn tại lời giải
8. Thực hiện đầy đủ các yêu cầu kỹ thuật

⟦folio 60⟧

---
running_head:
folio:
---

Mọi người đạt được 175-195 điểm đều nhận được huy chương bạc. Trong số đó có: Dmitry Zhukov (187 điểm) từ đội Nga, Alexey Skovortsov (185 điểm) từ Ukraine, Girts Karnitis (185 điểm) từ Latvia và Vladimir Bely (185 điểm) từ Belarus.

Học sinh đạt 123-172 điểm được trao huy chương đồng. Số lượng huy chương đồng lớn nhất - ba huy chương - thuộc về các đội Nga, Đức, Ukraine và Litva. Họ được nhận bởi Sergey Noffe (170 điểm), Evgeny Kuznetsov (165 điểm) và Dmitry Davydok (131 điểm) từ đội Nga, Pavel Matlash (158 điểm), Denis Filipenko (155 điểm) và Vitaly Bondarenko (124 điểm) từ đội Ukraine, Gidrius Meynorus (170 điểm), Valdas Ambazusha (160 điểm) và Maris Alburga (140) điểm) từ đội Lithuania. Đến từ các quốc gia láng giềng, Sergei Gafurov (150 điểm) đến từ Belarus, Andris Galans (139 điểm) đến từ Latvia và Peter Laud (125 điểm) đến từ Estonia cũng giành huy chương đồng.

Kết quả tốt nhất cho phương án này là ý tưởng của học sinh đến từ Trung Quốc. Họ nhận được ba huy chương vàng và một huy chương bạc với tổng số 785 điểm. Theo sau họ là các đội Tanland (743 điểm), Thụy Điển (731 điểm) và Hàn Quốc (728 điểm).

Sự gia tăng số lượng người tham gia đã làm trầm trọng thêm đáng kể cuộc đấu tranh để được công nhận địa điểm. Điều đáng mừng là bất chấp những khó khăn hiện tại, các đội tuyển Nga đã khẳng định được uy tín cao của mình. Xét về số huy chương giành được, đội tuyển ta đứng thứ 6 (652 điểm), chỉ kém đội tuyển Olympic, đội tuyển Đức (671 điểm) một chút và dẫn trước các đội rất mạnh Tiệp Khắc, Mỹ, Bulgaria, Argentina, Ba Lan, Romania, Anh.

Các chàng trai của chúng ta hơi thiếu huy chương vàng. Như những năm trước, trình độ đào tạo lý thuyết cao bị ảnh hưởng do thiếu kỹ năng lập trình kỹ thuật ổn định. Tất nhiên, có thể nói về việc thiếu kinh nghiệm thi đấu quốc tế và các chàng trai quá háo hức. Tuy nhiên, những lỗi kỹ thuật nhỏ mắc phải có thể đã không xảy ra nếu người tham gia thực hành lập trình nhiều hơn. Thật không may, phí ngắn hạn rõ ràng là không đủ ở đây. Và không thể phát triển các kỹ năng cần thiết một cách “tự động” trong vòng vài tuần. Điều này đòi hỏi một thời gian dài và làm việc chuyên sâu trên máy tính dưới sự hướng dẫn của những người cố vấn giàu kinh nghiệm. Chỉ có làm việc thường xuyên với những học sinh có năng khiếu mới có thể mang lại kết quả tốt hơn, và đây là điều chúng ta cần phấn đấu.

Cũng rất thú vị khi ghi nhận kết quả cạnh tranh giữa các đội đến từ các nguồn lực của Liên Xô cũ: Belarus, Latvia, Lithuania, Nga, Ukraine và Estonia. Đội tuyển Nga đã giành vị trí đầu tiên tại đây. Đội mạnh Ukraine thua đội Nga tới 31 điểm. Theo sau họ là các đội Lithuania và Belarus. Nếu các quốc gia nói trên thi đấu như một đội duy nhất, thì khi ghi được 742 điểm, đội này sẽ đứng thứ ba sau Trung Quốc và Tanland, đồng thời có bốn huy chương bạc trong kho bạc, giống như năm ngoái.

Ngày Proteelli MY-92. Ngoài cuộc thi, người tham gia còn có cơ hội ngắm cảnh nước Đức, làm quen với những phát triển mới nhất trong lĩnh vực công nghệ thông tin và gặp gỡ các chuyên gia hàng đầu trong lĩnh vực này. Trong sự lạnh lẽo của khách sạn tối ưu, một buổi giới thiệu thú vị về công ty Siemens Nixdorf, nhà tài trợ cho MOI-92 và đã đóng góp rất nhiều để tổ chức thành công các cuộc thi này. Tôi nhớ những cuộc gặp gỡ với đại diện của nhiều công ty nhóm khác nhau trong nhà xuất bản.

⟦folio 61⟧

---
running_head:
folio:
---

hội nghị Springer-Verlag ở Heidelberg và chuyến thăm trung tâm viễn thông ở Cologne. Đặc biệt quan tâm là bài giảng của Tiến sĩ N. Thalmann, liên quan đến việc tổng hợp phim máy tính dựa trên hình ảnh ba chiều của một diễn viên, khi kết thúc một trong những bộ phim này được chiếu và tất cả những người tham gia đều nhận được những cuốn sách có nội dung tương tự như một món quà từ các tác giả.

Lễ đóng cửa MOI-92 cũng diễn ra tại nơi ở của công ty GMD. Những người chiến thắng đã nhận được các giải thưởng và huy chương mà họ đã giành được trong cuộc đấu tranh khó khăn. Những người chiến thắng đã được tặng quà làm quà lưu niệm. Và mặc dù thực tế là hầu hết những người tham gia đều không có huy chương, tuy nhiên, nụ cười vẫn không tắt trên khuôn mặt của cả những người đó và những người khác. Theo quy định, Bộ trưởng Bộ Giáo dục và Khoa học Liên bang Đức, Giáo sư R. Ortleb, đã lưu ý trong bài phát biểu của mình, “MOI-92 chỉ là một cuộc thi, mặc dù là một cuộc thi khó và trong cuộc sống sẽ có nhiều cuộc thi như vậy, và ai có thể phân bổ lực lượng hợp lý và học cách vượt qua những khó khăn nảy sinh sẽ giành chiến thắng”.

Theo thông tin, Olympic quốc tế tiếp theo sẽ diễn ra ở Argentina vào tháng 10 năm 1993. Ủy ban quốc tế phần lớn vẫn giữ nguyên các quy định tổ chức cuộc thi vào năm tới. Những thay đổi này chỉ ảnh hưởng đến các hệ thống lập trình đang hoạt động, đã được phê duyệt là Turbo Pascal v. 6.0, Borland C++ v. 2.0, cũng như Quick Basic hoặc GWBasic.

Như kinh nghiệm của MOI-92 đã chỉ ra, để đạt được thành công trong các cuộc thi như vậy, cần phải thành thạo như nhau về lập trình kỹ thuật và các phương pháp lời giải không chuẩn bài toán, tức là các phương pháp Olympic bài toán. Tôi hy vọng rằng thế hệ vận động viên Olympic tiếp theo sẽ có thể tiếp thu kinh nghiệm của những người tiền nhiệm và sẽ đại diện xứng đáng cho đất nước chúng tôi ở Argentina.
