---
id: 1981-9-rar-kakie-byivayut-yazyiki-programmirovaniya-aed31b4a
issue: kvant_1981_9
year: 1981
number: "9"
title: Các ngôn ngữ lập trình khác nhau là gì?
authors:
  - Рар А.
rubric: raznoe
rubric_sub: Разное
page_first: 52
page_last: 56
page_labels: 50-54
tag: WJSA
lang: vi
source: kvant_digital
extraction: vision
content_sha256: c676f4c9891138632252081f52294ef85cd03725a5c8db8342c20b5936626201
prompt_sha256: draft-1
translated_from: content/ru/1981/09/articles/21_rar-kakie-byivayut-yazyiki-programmirovaniya-aed31b4a.md
source_content_sha256: 39ea9ef0c46e3d87cfed08cfd879ba81a9ee2799e160e6246ab14ee8960066a3
translation_model: draft
translation_run: vi-draft-2026-10-31
translation_quality: draft
---

⟦folio 50⟧

Nghệ thuật lập trình

Algol 68

Algol Algol-60
Bí danh Algol-Cobol
Almo Altran Alfarb
Ambit Amtran AP APL
APT ATF AED Hạnh phúc cơ bản
Boyaz BTspl 2 giờ sáng GPL GPS GPSS Graf
Sơ đồ hộp thoại GSL Jovial Jass
Diana Dynamo Dis-68 Euclid IPS
IPL CEL Cobol Cogenit Comfort
San hô Comit
LDT Môi Li
Logo Lotis Lotis
Militran Mirfak
Mary Neliak OSS
PL/360 PL-516
Giảm giá RPG Sidel
Tiếng Simskrit
Pascal PL/1
Thanh kiếm PL/11
Mô phỏng-1
Sirnus
bóng siboball

SỰ THẬT
FLAC
hình thức
pháo đài
fsl
tsdl tsp
Chilê
Ezol
Euler
Epsilon
Yarms
Yakhont

Đầu mối nút chai
nói ngọng
Mamlab
Thời trang điên cuồng
PS-440
giới thiệu
Ổn định
agma
-67

A. Rahr

Các ngôn ngữ lập trình khác nhau là gì?

Từ biên tập viên. Bài viết được xuất bản dưới đây cũng có sẵn cho những độc giả không học tại Trường Lập trình Tương ứng.
Trường Báo chí bắt đầu khóa học thứ ba và cũng là khóa học cuối cùng trong số tiếp theo.

Mặc dù những chiếc máy tính đầu tiên chỉ được tạo ra vào những năm 40, nhưng ngày nay các ngôn ngữ lập trình đã phát triển một cách dường như và vô hình (danh sách các ngôn ngữ không đầy đủ được hiển thị trên màn hình giật gân cho bài viết này).

Sinh viên ZShP có giá trị tốt về Rapier, chúng tôi sẽ đề cập đến nó trong phần phá hủy. Những độc giả khác có thể bỏ qua những chú thích này.

Chúng ta sẽ bắt đầu câu chuyện của mình từ thời xa xưa khi chưa có ngôn ngữ lập trình mà chỉ có

⟦folio 51⟧

Ngôn ngữ máy

Ngôn ngữ máy của máy tính không gì khác hơn là một hệ thống hướng dẫn máy của nó (xem «Kvant», 1981, Số 4 - “Ba địa chỉ, một địa chỉ và... máy không địa chỉ”). Các quy tắc để máy “hiểu” các lệnh này được nhúng trong thiết kế của máy tính, giống như, chẳng hạn, thiết kế tự động hóa được nhúng trong “sự hiểu biết” về ý nghĩa của việc xoay vô lăng.

Hãy đưa ra một ví dụ về hoạt động của chương trình được sử dụng bởi ngôn ngữ. Chúng ta hãy giả sử rằng lập trình viên này phải, trong quá trình lời giải của bài toán của mình, tính toán xem điểm ma trận nạp tự do ở độ cao nào $H$ nằm ở $T$ giây sau khi bắt đầu rơi, nếu độ cao ban đầu của điểm là $A_m$ thì tốc độ ban đầu là $V_m/c$. Công thức vật lý tương ứng đã được biết rõ:

$$H = 9,81 \cdot T^2/2 + V \cdot T + A,$$

nhưng sẽ thuận tiện hơn cho người lập trình viết lại dưới dạng khác:

$$H = (9,81 \cdot T/2 + V) \cdot T + A.$$

Khi bắt đầu làm việc trên một chương trình, lập trình viên phải thực hiện "cấp phát bộ nhớ" cho chương trình đó, nghĩa là xác định địa chỉ của các ô sẽ được sử dụng để lưu trữ số lượng nhất định.

Ví dụ: giả sử anh ta phân bổ bộ nhớ như sau:

| Kích cỡ | Địa chỉ ô |
| :--- | :--- |
| Hằng số 9,81 | 1001 |
| Hằng số 2 | 1002 |
| Biến $A$ | 1101 |
| Biến $V$ | 1102 |
| Biến $T$ | 1103 |
| Biến $H$ | 1104 |

Hơn nữa, trong máy của chúng ta (nhân tiện, đây là một làn gió rất xứng đáng của công nghệ máy tính trong nước - máy M-220, ngày nay vẫn được sử dụng ở một số nơi), phép toán cộng có mã 01, phép chia - 04, phép nhân - 05. Sau đó, theo tất cả các chương trình của anh ta, chẳng hạn bắt đầu từ ô 0101, lập trình viên viết:

$$Y = E'9.81;T,H$$
$$D = E'2';H$$
$$C = H,V,H$$
$$Y = H,T,H$$
$$C = H,A,H$$

(C - phép cộng, Y - phép nhân, D - phép chia; sử dụng cấu trúc = E'...' một hằng số được mô tả).

⟦folio 52⟧

Trong ví dụ này, cả sự thuận tiện và nhược điểm của tác giả đều được thể hiện rõ. Một mặt, chương trình không còn quan tâm đến bất kỳ địa chỉ nào. Bằng cách thay đổi một chương trình hoặc kết hợp nhiều chương trình thành một, sao cho các chương trình khác nhau không có cùng tên và có thể không chú ý đến chuyển động của chúng trong bộ nhớ. Tuy nhiên, mặt khác, văn bản trong autorok vẫn quá gần với văn bản trong ngôn ngữ máy; các hành động trong đó quá nhỏ và không bình thường đối với toán học.

Cho dù trình độ của tác giả thấp đến đâu, máy cũng không thể trực tiếp nhận biết các chương trình được viết trong đó và chúng, giống như các chương trình được viết bằng bất kỳ ngôn ngữ lập trình nào khác, phải được dịch sang ngôn ngữ máy trước khi sử dụng. Để dịch (phát sóng) như vậy, các chương trình đặc biệt đã được phát triển - dịch giả. Người dịch từ bản ghi tự động được gọi là người biên dịch. Sự gần gũi của tác giả với ngôn ngữ máy đảm bảo tính đơn giản tương đối của trình biên dịch.

Fortran và ALGOL

Ngôn ngữ độc lập với máy tính đầu tiên là Fortran, dành cho lập trình máy tính. bài toán. Nó được tạo ra vào năm 1956 ở Mỹ. Năm 1958-1960 Một nhóm các nhà toán học từ các quốc gia khác nhau đã phát triển ngôn ngữ ALGOL-60 cho cùng mục đích. Hai ngôn ngữ này vẫn được sử dụng rộng rãi trên toàn thế giới. Một số lượng lớn các chương trình từ các lĩnh vực ứng dụng toán học tính toán khác nhau được viết trên đó. Những ngôn ngữ này khác nhau về nhiều mặt, nhưng chúng tôi sẽ không đề cập đến sự khác biệt của chúng ở đây. Thay vào đó hãy quay lại ví dụ của chúng tôi. Chúng ta sẽ rất vui khi biết rằng để tính giá trị ban đầu, bây giờ chỉ cần một toán tử là đủ:

$$H = (9,81 * T/2 + V) * T + A$$

(ví dụ viết bằng Fortran).

Cùng với các đối tượng biến thông thường của các ngôn ngữ đang được xem xét, cũng có thể có các mảng - một chiều, hai chiều, v.v. Mảng một chiều là một chuỗi số có độ dài nhất định*. Mảng hai chiều là một dãy gồm các mảng một chiều có cùng độ dài, v.v. Mảng phải được mô tả trong chương trình; một mô tả như vậy phải xác định đầy đủ các kích thước của nó. Ví dụ: giả sử một chương trình Fortran mô tả một mảng hai chiều nhất định có tên TABLE và mô tả của mảng này cho biết các kích thước của nó: 3 ở chiều thứ nhất và 4 ở chiều thứ hai**. Thật thuận tiện khi coi mảng này như một bảng (ma trận) gồm 3 hàng và 4 cột, chứa đầy các số (phần tử mảng). Tại một số điểm trong quá trình sử dụng chương trình, ma trận này có thể giống như sau:

$$-4 \quad 0 \quad 5 \quad 8$$

$$6 \quad -2 \quad 4 \quad 3$$

$$0 \quad 0 \quad 15 \quad 11$$

Phần tử tại giao điểm của hàng thứ I và cột thứ J được xác định bởi một biến có chỉ số BẢNG (I, J). Bạn có thể thực hiện các hành động tương tự trên một biến có chỉ mục như trên các biến thông thường, do đó, một vài toán tử

$$K = 2$$

BẢNG (1,1)-BẢNG (K+1,4)+BẢNG (K,K)

sẽ thay thế phần tử trên cùng bên trái của ma trận bằng số 9.

Trong ngôn ngữ ALGOL-60 và Fortran, có các điều kiện của toán tử cho phép bạn xác định quá trình sử dụng tiếp theo của chương trình tùy thuộc vào giá trị hiện tại của một số biến nhất định, cũng như các toán tử vòng lặp thực hiện việc sử dụng lặp lại một số phần nhất định của chương trình***. ALGOL-60 có các quy trình cho phép

*) Trên Rappier, mảng một chiều được gọi là bộ dữ liệu (xem «Kvant», 1980, số 3, 3ШП, bài 8).
**) Trên Rappier có 3 thành phần của một bộ, mỗi thành phần có 4 phần tử.
***) Về các phương tiện tương tự trong Rappier, xem «Kvant», 1980, Số 9, 3ШП, bài 9.

⟦folio 53⟧

có thể gọi việc thực thi cùng một nhóm toán tử ở những nơi khác nhau trong chương trình *); Có những công cụ (chương trình con) tương tự trong Forteran.

Một đại dịch Varian khác

Sau khi Forter được tạo ra, ngày càng có nhiều ngôn ngữ lập trình mới bắt đầu xuất hiện ở các quốc gia khác nhau. Bây giờ, xin lỗi, chúng phải được tính đến hàng trăm. Liên quan đến sự phong phú về ngôn ngữ này, câu chuyện trong Kinh thánh về Địa ngục Babylon thường được nhắc lại. Theo truyền thuyết này, cư dân Babylon đã quyết định xây dựng một tòa tháp (cột) vươn lên trời. Nhưng không có gì xảy ra. Đức Chúa Trời, không muốn cho phép con người vào thiên đàng, đã chia toàn bộ ngôn ngữ thành ngôn ngữ của các dân tộc khác nhau, và những người xây dựng không còn hiểu nhau nữa. Màn hình tiêu đề của bài viết hiển thị Tháp Babel mới.

Có hai lý do cho sự sáng tạo ngôn ngữ sâu sắc như vậy. Thứ nhất, máy tính là thiết bị điện toán phổ quát được thiết kế cho lời giải tùy ý bài toán phát sinh trong nhiều lĩnh vực hoạt động của con người. Tất nhiên, tất cả những bài toán này có thể được giải quyết bằng ngôn ngữ máy, nhưng chúng tôi thấy rằng điều này rất khó. Các ngôn ngữ Forteran và ALGOL-60, tuy tạo điều kiện thuận lợi rất nhiều cho việc lập trình máy tính nói chung bài toán, nhưng lại kém phù hợp với các ngôn ngữ khác bài toán. Vì vậy, các ngôn ngữ chuyên ngành bắt đầu xuất hiện cho ngày càng nhiều lớp bài toán, đôi khi rất hẹp và cụ thể. Thứ hai, điều quan trọng là lập trình là một lĩnh vực hoạt động còn rất non trẻ của con người. Phần lớn trong đó vẫn chưa được thiết lập, và do đó các chương trình được tạo ra, phát minh, thử nghiệm, lựa chọn phương tiện ngôn ngữ phù hợp nhất cho các mục đích nhất định. Và những vấn đề này cuối cùng

*) Về thủ tục trong Rapier, xem «Kvant», 1980, số 2, 3ШП, bài 6.

hữu ích vì chúng giúp đánh giá và so sánh các cách tiếp cận khác nhau nhằm sử dụng chúng trong các ngôn ngữ tiên tiến hơn trong tương lai. Và những ngôn ngữ không được sử dụng đương nhiên sẽ chết đi.

Bây giờ chúng ta hãy xem xét kỹ hơn các chữ Cyrillic riêng lẻ của Tháp Babel mới và trước tiên hãy xem xét

Ngôn ngữ chuyên ngành

Tính toán bài toán cũng khác nhau. Đây có thể là kỹ thuật và khoa học-kỹ thuật bài toán, trong đó cần thực hiện số lượng phép tính lớn hơn trên một lượng dữ liệu tương đối nhỏ. Algol-60 và Forteran rất phù hợp cho những mục đích này. Ngoài ra còn có kế toán, kinh tế và kế toán bài toán, trong đó các hoạt động tùy ý rất đơn giản nhưng phải xử lý thông tin lớn và có tổ chức phức tạp, chẳng hạn như bảng lương. Đối với bài toán như vậy, ngôn ngữ Cobol đã được phát triển từ năm 1960. Các chương trình trong Cobol chỉ định định dạng (cách sắp xếp) thông tin trên tài liệu đầu vào và đầu ra, đồng thời xác định, bằng cách sử dụng các cụm từ gần với cụm từ trong ngôn ngữ tiếng Anh (hoặc tiếng Nga), những hành động nào phải được thực hiện trên các giá trị số và trên các văn bản có trong thông tin này.

Đồng thời, bài toán như vậy cũng rất phổ biến, trong đó việc xử lý văn bản hoặc thông tin không phải số (ký hiệu) khác chiếm vị trí trung tâm. Một trong những bài học của Trường Lập trình Tương ứng («Kvant», 1980, Số 11) được dành cho những vấn đề như vậy, nhưng chúng tôi sẽ phần nào mở rộng chủ đề của bài học này bằng cách đề cập thêm hai vòng tròn bài toán.

Vì vậy, chúng ta có thể nói rằng Algol-60, Forteran và Cobol biết số học, nhưng không biết đại số: chúng có thể tính giá trị của biểu thức $x^2 - y^2$ khi chỉ định giá trị của $x$ và $y$, nhưng chúng không thể chuyển đổi biểu thức này thành $(x+y)(x-y)$. Chúng tôi đã va chạm

⟦folio 54⟧

ở đây với một trong những bài toán xử lý thông tin biểu tượng quan trọng - các phép biến đổi hình thức.

Vòng tròn còn lại bài toán là ứng dụng lập trình vào chính việc lập trình. Các chương trình được viết bằng bất kỳ ngôn ngữ nào đều yêu cầu nhiều kiểu chỉnh sửa khác nhau và quan trọng nhất là sao chép, dịch sang ngôn ngữ máy. Nhưng chương trình là văn bản và tất cả bài toán này đều thuộc lĩnh vực xử lý văn bản, lĩnh vực này thường phức tạp và cụ thể. Có nhiều ngôn ngữ được thiết kế để làm việc với văn bản. Nanoball là nổi tiếng nhất trong số đó.

Một số ngôn ngữ lập trình được đặc trưng không phải bởi lĩnh vực ứng dụng của chúng mà bởi cấu trúc của dữ liệu đang được xử lý. Đây là Liss, một ngôn ngữ được thiết kế đặc biệt để làm việc với thông tin được sắp xếp theo danh sách. Danh sách khác với mảng một chiều ở chỗ nó linh hoạt hơn. Độ dài của nó không cố định trước, nó có thể được bổ sung ở bất kỳ đâu bằng các phần tử mới và các phần tử có thể bị xóa khỏi bất kỳ vị trí nào. Trong thực tế, điều này có nghĩa là các phần tử của danh sách không nằm gần nhau trong bộ nhớ (như thường thấy đối với mảng), nhưng mỗi phần tử được cung cấp một liên kết cho biết vị trí của phần tử tiếp theo. Rõ ràng là những thay đổi cục bộ trong danh sách không dẫn đến việc sửa đổi bộ nhớ của danh sách - chỉ các liên kết riêng lẻ mới thay đổi.

Ngôn ngữ phổ quát

Kể từ giữa những năm 60, cùng với mong muốn tạo ra các ngôn ngữ lập trình chuyên dụng, một mong muốn ngược lại đã nảy sinh: các ngôn ngữ phổ quát bắt đầu xuất hiện, phù hợp với mọi bài toán - kỹ thuật hoặc kế toán, biên tập hoặc dịch thuật - với cấu trúc phái sinh của thông tin đã xử lý.

Việc sử dụng cách hiểu ở đây về cụm từ “ngôn ngữ phổ quát” nói chung không được chấp nhận.

Chúng ta có thể nói ngay rằng trong thời hiện đại không thể có người chiến thắng giữa các ngôn ngữ chuyên biệt và phổ thông. Cả hai ngôn ngữ đều tốt trong một số điều kiện và xấu ở những điều kiện khác. Nếu một lập trình viên thường phải chuyển từ lớp bài toán này sang lớp khác hoặc nếu trong cùng một lớp bài toán, chẳng hạn, cần phải thực hiện các phép tính phức tạp và chỉnh sửa văn bản, thì tất nhiên, cần phải sử dụng ngôn ngữ phổ quát. Mặt khác, rõ ràng là không có ích gì khi tung ra một công cụ phổ quát cồng kềnh nếu bạn đang xử lý một số loại công việc hạn chế. Trong số các ngôn ngữ lập trình phổ quát, PL/1, Algol-68, Settle và Pascal được đề cập.

Nói một cách đại khái, chúng ta có thể nói rằng PL/1 đến từ Fortan và tiền thân của Algol-68 là Algol-60. PL/1 và ALGOL-68 có thể hoạt động với dữ liệu được sắp xếp theo trọng số một cách phức tạp. Ví dụ: bạn có thể định nghĩa một mảng có các phần tử là danh sách, mỗi phần bao gồm tuần tự một số nguyên, một chuỗi ký tự, một mảng số, một từ của số nguyên, v.v. Algol-68 còn có đặc điểm là lập trình viên có thể trong chương trình của mình đưa ra một phép toán ngôn ngữ (ví dụ: phép cộng với dấu + thông thường của nó) một ý nghĩa mới hoặc bổ sung (ví dụ: được phép cộng các mảng), cũng như xác định các phép toán mới. Lập trình viên cũng có thể, bằng cách xác định một tập hợp các thao tác mới cần thiết cho một số lớp bài toán, cung cấp tập hợp này cho tất cả các chương trình giải quyết bài toán của lớp đó. Do đó, ALGOL-68 hóa ra là một ngôn ngữ tự mở rộng và (vì các hoạt động mới có thể xuất hiện) đồng thời tự điều chỉnh (đối với một lĩnh vực ứng dụng cụ thể).

Đặc điểm chính của ngôn ngữ Settle là sử dụng một kiểu mới
