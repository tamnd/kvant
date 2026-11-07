---
id: 1992-4-stolyarov-algoritm-f84e9f66
issue: kvant_1992_4
year: 1992
number: "4"
title: Thuật toán
authors:
  - Столяров Л.
rubric: raznoe
rubric_sub: Разное
page_first: 62
page_last: 64
page_labels: 60-62
lang: vi
source: kvant_digital
extraction: vision
content_sha256: 64ecae6be6e6b3fb650438faf0f23e524bd67d46b531032e329843885d08eedf
prompt_sha256: draft-1
translated_from: content/ru/1992/04/articles/21_stolyarov-algoritm-f84e9f66.md
source_content_sha256: 34bf444ca7672c47fa5fab384520eea11085ffe2e06dc99f013aa036e490c23a
translation_model: draft
translation_run: vi-draft-gaps-2026-11-06
translation_quality: draft
---

⟦folio 60⟧

---
running_head:
folio:
---

Thuật toán

Tiến sĩ Khoa học Vật lý và Toán học
L. STOLYAROV

Từ “thuật toán” đã đi vào vốn từ vựng của chúng ta một cách chắc chắn với sự ra đời của máy tính điện tử như một từ chỉ một tập hợp các hành động tạo nên một quy trình nhất định. Và mặc dù chúng tôi muốn nói ở đây, theo quy luật, quy trình lời giải của một số bài toán, ngoài ra còn có công thức nấu nướng, hướng dẫn sử dụng máy may và nhiều quy tắc khác, thường không liên quan đến toán học, là các thuật toán. Và trong toán học cũng vậy, thuần túy hình học bài toán, như bài toán trong xây dựng, chứa các thuật toán trong lời giải của chúng.

Thuật ngữ “thuật toán” xuất phát từ tên của nhà khoa học thế kỷ 8-9 Al-Khorezmi. Tên của anh ấy cho biết anh ấy sinh ra ở thành phố Khorezm (nay là một phần của Uzbekistan). Al-Khorezmi đã dành phần lớn cuộc đời mình dưới quyền của hai vị vua ở Baghdad. Tên tuổi của ông gắn liền với việc thành lập “Ngôi nhà trí tuệ” ở Baghdad - kho lưu trữ chữ viết tay của Baghdad. Trong số các công trình toán học của Al-Khorezmi, chỉ có hai công trình ra đời trước chúng ta - đại số và lập luận. Công việc đại số được gọi là "Đại số walmukabala", có nghĩa là "Tái thiết và mâu thuẫn". Ông gọi sự phục hồi là việc chuyển các số hạng âm sang một phần khác của phương trình, và phản đối việc rút gọn các số hạng bằng nhau ở các phần khác nhau của phương trình. Từ tựa đề của cuốn sách này đã ra đời từ đại số. Cuốn sách thứ hai, bị coi là thất lạc từ lâu, được tìm thấy vào năm 1857 trong thư viện Đại học Cambridge. Chính xác hơn, bản dịch của nó sang tiếng Latin đã được tìm thấy. Cuốn sách này đưa ra những quy tắc rõ ràng cho các hành động tranh luận, gần như giống những quy tắc đang được sử dụng hiện nay. Những dòng đầu tiên của cuốn sách này được dịch như sau: "Thuật toán đã nói. Chúng ta hãy ca ngợi Chúa, người lãnh đạo và người bảo vệ của chúng ta." Vì vậy, cái tên Al-Khorezmi đã trở thành Thuật toán, đó là nguồn gốc của từ thuật toán. Nó được nhà toán học người Đức Ernst Schröder (1841-1902) đưa vào sử dụng để biểu thị các quy trình tính toán có tính chất cơ học.

Khái niệm trực quan về thuật toán như một hệ thống dự đoán hành động đã không thể làm hài lòng các nhà toán học ngay cả trong thế kỷ trước, chưa kể đến thế kỷ hiện tại, khi thông tin đã đi sâu vào mọi lĩnh vực hoạt động của con người.

Vào những năm hai mươi của thế kỷ chúng ta, bài toán việc xác định chính xác khái niệm thuật toán đã trở thành một trong những vấn đề trọng tâm của toán học. Thực tế là khi đó có hai quan điểm về các vấn đề toán học:

1. Tất cả các vấn đề thuật toán đều có thể giải được, nhưng đối với một số thuật toán vẫn chưa được tìm thấy, vì các nhánh toán học tương ứng vẫn chưa được phát triển.

⟦folio 61⟧

---
running_head:
folio:
---

2. Có những vấn đề lời giải mà không thể có thuật toán nào cả.

Những người ủng hộ quan điểm thứ hai hóa ra là đúng, nhưng để chứng minh nó, cần phải đưa ra định nghĩa rõ ràng về thuật toán. Điều này được thực hiện thông qua công trình của cả một thiên hà các nhà toán học, bao gồm K. Gödel, A. Church, S. Kleene, A. Thjoring, E. Post, A. Markov, A. Kolmogorov và nhiều hơn nữa.

Một định nghĩa chính xác về khái niệm thuật toán đáng lẽ phải xuất hiện ngay bây giờ để chứng minh tính không thể giải được về mặt thuật toán của hơn một chục vấn đề toán học. Chúng bao gồm bài toán thứ mười của D. Hilbert, một nhà toán học xuất sắc người Đức vào cuối thế kỷ trước và đầu thế kỷ này, người đã đưa ra danh sách các bài toán quan trọng nhất của toán học ở thời đại ông.

Bài toán thứ mười của Hilbert liên quan đến nghiệm của cái gọi là “phương trình Diophantine”, tức là phương trình có dạng $P(x_1, x_2, \dots, x_n) = 0$, trong đó $P$ là đa thức có hệ số nguyên, ví dụ $x + y + z = 1$ hoặc $x^n + y^n = z^n$. Gilbert đã xây dựng nó theo cách này:

“Giả sử cho một phương trình Diophantine tùy ý với một số ẩn số tùy ý..., cần phải chỉ ra một phương pháp tổng quát, theo đó người ta có thể tìm ra trong một số hữu hạn các bước xem một phương trình đã cho có lời giải cho mục đích của... số hay không."

Có lý do để tin rằng Hilbert đã bị thuyết phục về sự tồn tại của một phương pháp tổng quát và muốn khuyến khích việc tìm kiếm nó. Tính không thể giải được bằng thuật toán của bài toán này đã được nhà toán học Liên Xô Yu chứng minh vào năm 1970. Matiyasevich, người có tài năng rõ ràng trong những năm đi học tại các cuộc thi Olympic toán học.

Chúng tôi sẽ cố gắng giới thiệu cho người đọc những quan điểm khác nhau về khái niệm thuật toán trong các số tiếp theo của tạp chí và bây giờ chúng tôi sẽ hình thành các ý tưởng trực quan hiện đại về các thuật toán cho quy trình xử lý dữ liệu có thể được áp dụng trong thực tế tính toán.

1. dữ liệu

Các đối tượng cần thao tác thường được gọi là đối tượng cấu trúc. Thuật toán xử lý các đối tượng cấu trúc ban đầu thành các đối tượng cấu trúc thu được.

1.1. Nhận dạng dữ liệu

Mỗi đối tượng cấu trúc phải được xác định (được chọn) trong số các đối tượng cấu trúc khác bằng cách này hay cách khác. Vì vậy, ví dụ, các con số khác nhau về cách viết, số cờ khác nhau về mục đích, màu sắc và tọa độ vị trí trên bàn cờ.

1.2. Cấu trúc dữ liệu

Từ tổng thể các đối tượng cấu trúc, những đối tượng được xác định ban đầu sẽ được phân biệt. Chúng được gọi là sơ cấp và bộ sưu tập của chúng được gọi là bảng chữ cái. Các phần tử cấu trúc còn lại được gọi là phức tạp và được tạo từ các phần tử bằng các thao tác nhất định. Ví dụ: số tự nhiên được biểu diễn bằng chuỗi chữ số.

1.3. Tính hữu hạn của dữ liệu

Một bảng chữ cái phải luôn chứa một số phần tử hữu hạn. Đồng thời, vô số đối tượng có cấu trúc phức tạp có thể được hình thành từ các thành phần của bảng chữ cái. Do đó, từ một bảng chữ cái chỉ chứa mười chữ số, có thể tạo thành một chuỗi số tự nhiên vô hạn, nhưng một tập hợp các số tự nhiên không thể có trong bảng chữ cái.

2. Quá trình

Quá trình thuật toán được chia thành các bước riêng lẻ. Mỗi bước chuyển trạng thái phát sinh trước bước này sang trạng thái tiếp theo khác. Các trạng thái được mô tả như một tập hợp các đối tượng cấu trúc. Chuyển đổi tính ngẫu nhiên bằng một thao tác từ danh sách hữu hạn các thao tác được giới thiệu cụ thể cho từng đối tượng cấu trúc.

⟦folio 62⟧

---
running_head:
folio:
---

3. CPU

Bộ xử lý thực hiện chuyển đổi trạng thái, ghi và lưu trữ thông tin trạng thái. Các hành động được thực hiện theo thứ tự lựa chọn lệnh đã chỉ định. Ghi lại lệnh bằng bất kỳ ngôn ngữ nào và thỏa thuận về thứ tự thực hiện chúng là một thuật toán cụ thể. Ngôn ngữ này có thể là ngôn ngữ lập trình (BASIC, Pascal, Fortran), ngôn ngữ máy hoặc ngôn ngữ chung của con người, chẳng hạn như các quy tắc cộng số trong sách của Al-Khwarizmi.

Tất nhiên, không phải mọi quá trình chuyển đổi trạng thái này sang trạng thái khác đều có thể được gọi là thuật toán. Như vậy, quá trình vật lý chuyển đổi năng lượng của nước rơi thành năng lượng điện không thể gọi là thuật toán được.

Các quy trình thuật toán phải đáp ứng một số yêu cầu.

Sự quyết tâm

Khi áp dụng một thuật toán cho cùng một dữ liệu ban đầu, nó phải luôn thu được cùng một kết quả, do đó, quá trình chuyển đổi trạng thái này sang trạng thái khác phải đáp ứng một số yêu cầu.

Danh sách độc giả gửi đúng lời giải

(Để bắt đầu, xem trang 33)

ko (Mukachevo) 08.10; S. Makarov (Usinsk) 08-11; S. Malatstskaya (Kuznetsovsk) 09.11; Yu. Maravin (Evpatoria) 98,99,02—12; A. Matrunichi (Uzhgorod) 98—06,08,10,11; M. Makhmudov (Isfara) 03-06,08-11; P. Melentyev (Stary Oskol) 98,06,08,11; V. Mushik (Kuznetsovsk) 11; A. Myasoed (Oskol đầy sao) 08.11; A. Nemurenko (Kyiv) 98-01.03-12; M. Nemirovsky (Odeska) 98,02,04,06,08,10—12; A. Nosikov (Vinnitsa) 08.11; A. Ovsyannikov (Stary Oskol) 08; A. Olkhovets (Kyiv) 98,99,02—06,08—11; A. Ordabaev (Alma-Ata) 03—06,08,10,11; D. Ostrovsky (St. Petersburg) 98,01,02,08,10—12; Kh. Otzhenev (Khẩn cấp) 08; D. Pastukhov (Vitebsk) 98,00,02,04—11; D. Petraitis (Volsk) 04,06,08,11; Vâng. Pikaev (Vladivostok) 03; A. Pikaov (Kanash) 98,02; M. Pletokhov (Brest) 00.02—06.08—11; V. Ponkratov (Stary Oskol) 08.11; S. Rassadin (Minsk) 03,04,08,09,11,12; E. Rosly (Omsk) 05,06,11; D. Ruzmetov (Khẩn cấp) 08; III. Ruzmetov (huyện Khiva, vùng Khorezm) 03,08,11; V. Rybauk (Vinnitsa) 00,03,08,11; S. Samsonov (Stary Oskol) 08.11; I. Sikharuldze (Tbilisi) 11; D. Smirnov (Kuznetsovsk) 03.04; A. Soklakov (Brest) 04,08,11; A. Terentyev (Kanash) 98.00.02.04—06.08.11; S. Timoshuk (thôn Chernitsa, vùng Rivne) 08,09,11; V. Tolpekin (Odeska) 99,03,04,06,09,11; S. Tumachka (Kyiv) 08,09,11; A. Faizuldze (huyện Shavat, vùng Khorezm) 03,04,08,10,11; D. Fedorets (Kharkov) 04; R. Khapkov (Stary Oskol) 08.11; A. Khatskevich (Brest) 98,02; D. Chizsheev (St. Petersburg) 03,04,06,08—11; D. Chirkin (Grozny) 00.02—04.07; A. Chisty (Brest) 00.02—06.08,10.11; D. Chuchkan (Baranovich) 06,07,10-12; I. Shirev (Kuznetsovsk) 03,04,09,11; A. Shpazin (Marinuol) 98—00,02,04—06,08—12; O. Shyrko (Kyiv) 98-12; I. Shumovich (NIKOLAYEV) 08,09,12; T. Shutenko (Marinuol) 98-12; D. Yudin (Samsonov) 98,02,04,05,08—11; R. Yakunov (Kuznetsovsk) 98,99,01—04,06,08—11; R. Yachenko (Kuznetsovsk) 03,04,08,09,11.
