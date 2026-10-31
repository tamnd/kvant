---
id: 1980-1-salihova-sokolova-graficheskaya-sistema-shpaga-fbbce7ea
issue: kvant_1980_1
year: 1980
number: "1"
title: Hệ thống đồ họa Epee
authors:
  - Салихова А.
  - Соколова Н.
rubric: raznoe
rubric_sub: Разное
page_first: 58
page_last: 61
page_labels: 56-59
tag: RC9K
lang: vi
source: kvant_digital
extraction: vision
content_sha256: 674fef06b75e3c42218a7fcc88ed5513c6ecbccfe4b4fd173692ec1c1cc38379
prompt_sha256: draft-1
translated_from: content/ru/1980/01/articles/25_salihova-sokolova-graficheskaya-sistema-shpaga-fbbce7ea.md
source_content_sha256: 449689ef22805adabff52d1e02abafa6d9f6f0643860d28c039001ed69348449
translation_model: draft
translation_run: vi-draft-2026-10-31
translation_quality: draft
---

⟦folio 56⟧

A. Salikhova, N. Sokolova

Hệ thống đồ họa Epee

Những bức vẽ do máy tính thực hiện đã nhiều lần được đăng trên bìa tạp chí của chúng tôi. Các chương trình dành cho "người yêu thích máy tính" biên soạn các chương trình thử nghiệm sử dụng ngôn ngữ lập trình và hệ thống đồ họa máy tính khá phức tạp.

Nhiều bức vẽ trong phần “Nghệ thuật lập trình” cũng được thực hiện bằng máy tính nhưng sử dụng các chương trình có tác giả từ 8 đến 15 tuổi. Bức ảnh của chúng tôi chụp một nhóm lập trình viên trẻ đang làm việc trên một máy vẽ đồ thị. Nữ sinh ở phía bên trái, Asya Salikhova, học sinh lớp bảy, và bạn của cô, Natasha Sokolova, học sinh lớp tám, đã phát triển một bộ quy trình cho hệ thống đồ họa Shpara, được sử dụng để tạo ra chương trình đồ họa máy tính của chúng tôi.

Các bài viết về hệ thống này do các nhà phát triển của nó viết, mở ra tiểu mục “Tribune of a Young Programmer”.

Hệ thống Epee là một tập hợp các quy trình, mỗi quy trình vẽ một đường hoặc thực hiện một hành động phụ trợ (ví dụ: thay đổi hệ tọa độ). Quy trình nói có thể được sử dụng trong nhiều ngôn ngữ lập trình, bao gồm Robic, Rapier, Algol, Poplan và Pascal. Thanh kiếm trước hết là một hệ thống huấn luyện, vì vậy tên và thông số quy trình của nó*) đã được chọn sao cho dễ nhớ và dễ hiểu. Nhân tiện, bản thân các hệ thống được đặt tên được giải mã như sau:

Gói quy trình đồ họa dành cho trường học, được điều chỉnh

Bản vẽ bắt đầu từ đâu?

Để máy vẽ được chiếc tàu hơi nước như hình 1 thì phải giao nhiệm vụ.

Trước tiên, bạn nên xác định vị trí cho bản vẽ, nghĩa là đặt khung có kích thước mong muốn (ví dụ: 100 x 100 mm). Sau này cần thiết

*) Nếu các từ “thủ tục” và “tham số” có vẻ xa lạ với bạn, hãy xem tài liệu của các bài học đầu tiên của Trường Lập trình Tương ứng («Kvant», 1979, Số 9-11).

⟦folio 57⟧

Dimo mang bút hoặc công cụ vẽ khác đến điểm A, vẽ một đường thẳng đến điểm B, đến điểm C và D, lại đến điểm A. Sau đó di chuyển công cụ đến điểm E và tiếp tục làm việc.

Để thực hiện những hành động này, các quy trình cơ bản dự định của Epee là: KHUNG, CUNG CẤP, CHÙM, ĐIỂM, VÒNG TRÒN và các quy trình khác. Ví dụ: một chương trình trong Rapier để mô tả một tác phẩm kịch tính có thể trông như thế này: FRAME (100, 100); CUNG (25, 30); CHÙM (15,45); CHÙM (85, 45); CHÙM (75, 30); CHÙM (25, 30); CUNG (35, 45); CHÙM (35, 50); CHÙM (60, 50); CHÙM (60, 45); CUNG (45, 50); CHÙM (45, 60); CHÙM (50, 60); CHÙM(50, 50); KẾT THÚC;

Hãy để chúng tôi mô tả chi tiết hơn hoạt động của các quy trình đồ họa được tìm thấy trong chương trình này.

Thủ tục FRAME(D,C) đóng vai trò rất quan trọng trong hệ thống của chúng ta; bất kỳ chương trình nào sử dụng quy trình Sword đều phải bắt đầu bằng nó. Các tham số D và B trong quy trình này cho biết kích thước của khung tính bằng milimét (D - chiều dài, H - chiều cao). Sử dụng quy trình FRAME, trước tiên, máy vẽ một khung có kích thước xác định, thứ hai, tìm bên trên và bên dưới khung một số thông tin về hình ảnh (tên hệ thống đồ họa, ngày giờ sử dụng hình ảnh) và thứ ba, đặt hệ tọa độ hình chữ nhật tiêu chuẩn bên trong khung: đơn vị tỷ lệ là 1 mm, gốc tọa độ nằm ở góc dưới bên trái của khung.

Bạn đã chứng minh được cách thức hoạt động của quy trình BEAM và SUPPLY; quy trình CUNG CẤP (X, Y) đặt công cụ vẽ (bút vẽ) tại điểm (X, Y) mà không để lại bất kỳ dấu vết nào trên giấy. Quy trình RAY (X, Y) vẽ một đoạn thẳng từ điểm đặt bút trước đó đến điểm (X, Y).

Tất cả các quy trình vẽ của hệ thống Lời nói chỉ hoạt động trong khuôn khổ đã được thiết lập. Ví dụ: nếu khi thực hiện quy trình BEAM, điểm bắt đầu hoặc điểm kết thúc của một đoạn (hoặc cả hai cùng một lúc) nằm ngoài khung do lỗi chương trình, thì chỉ phần đó của đoạn nằm trong khung sẽ được vẽ.

Thủ tục END, không có tham số, báo cho máy biết rằng chương trình đã làm việc xong với máy vẽ. Sau khi hoàn thành bất kỳ quy trình Kiếm nào, bạn không thể sử dụng nó.

Tên của hầu hết các thủ tục hệ thống có thể được viết tắt. Đặc biệt các từ FRAME, BEAM và SUPPLY có thể viết tắt thành một chữ cái: R, L và P. Ngược lại, tên của thủ tục END không thể viết tắt.

Ở dạng viết tắt, chương trình này rất nhỏ gọn. Ví dụ: đối với hình ảnh một chiếc máy bay.

⟦folio 58⟧

Chỉ cần viết*):

P (120, 100); P (30, 46); L (15, 46);
L (15, 40); L (30, 40); P (20, 46);
L (20, 60); L (15, 60); L (15, 25);
L (20, 25); L (20, 40); P (40, 60);
L (40, 46); L (30, 46); L (40, 60);
L (78, 60); L (85, 80); L (100, 80);
L (100, 55); L (85, 30); L (30, 30);
L (30, 46); P (48, 60); L (60, 90);
L (80, 90); L (70, 60); P (50, 30);
L (50, 46); L (60, 46); L (60, 30);
P (70, 50); L (48, 50); L (38,20);
L (60, 20); L (70, 50); . KẾT THÚC;

Hình 4.

Dấu chấm, vòng tròn, vòng cung

Thủ tục ĐIỂM (X, Y) (viết tắt là T (X, Y)) cho phép bạn vẽ một điểm ở vị trí mong muốn trong ảnh. Sau đó, bút vẫn ở điểm (X, Y).

Thủ tục CIRCLE (R) sẽ vẽ một đường tròn có bán kính R có tâm tại điểm đặt pero trước đó. Sau khi sử dụng quy trình, pero quay trở lại trung tâm. Tên viết tắt của thủ tục này là K(R). Ví dụ: theo chương trình: P (100, 100); T(50, 50);
K (10); K (20); K (30); K(40);
K (50); KẾT THÚC;

MÁY TÍNH. sẽ vẽ một số vòng tròn đồng tâm (giống như mục tiêu) có dấu chấm ở giữa.

Đối với hình ảnh của một người bạn, bốn thủ tục được sử dụng: DUGAL, DUGAP, DUGAL, DUGAPB (viết tắt là DL, DP, DLB, DPB). Mỗi người trong số họ có ba tham số:

*) Chương trình do lớp thứ ba I. Afanasyeva biên soạn.

Hình 3.

(X, Y, R). X và Y là tọa độ điểm kết thúc của cung, R là bán kính của cung. Giống như đoạn trong quy trình URE BEAM, vòng cung được vẽ từ điểm đặt pero trước nó.

Từ hình vẽ 4, có thể thấy rằng từ điểm này đến điểm khác có bán kính cho trước, theo quy luật, có thể kiểm tra 4 cung khác nhau: thứ nhất, nhiều hơn hoặc nhỏ hơn hình bán nguyệt và thứ hai, theo chiều kim đồng hồ hoặc ngược chiều kim đồng hồ. Bốn trường hợp REM này tương ứng với bốn thủ tục. Chữ B ở cuối tên có nghĩa là cung phải lớn hơn hình bán nguyệt; thủ tục DP và DPB vẽ một cung ngược chiều kim đồng hồ, nghĩa là ở bên phải của vectơ được vẽ từ điểm bắt đầu của cung đến điểm cuối (do đó có tên DP - “cung bên phải”), thủ tục DL và DLB vẽ một cung ở bên trái của vectơ, nghĩa là theo chiều kim đồng hồ. Ví dụ, đây là chương trình cho Hình 4:

P(100, 100); P (70, 30);
L (30, 70); L (33, 70); L (30, 67);
L (30, 70); P (70, 30); DP (30, 70, 35);
P (70, 30); DL (30, 70, 35);
P (70, 30); DP (30, 70, 35);
P (70, 30); ĐLB (30, 70, 35);
.KẾT THÚC;

Nếu danh sách bán kính nhỏ được chỉ định thì cung sẽ không bị phá vỡ và hệ thống sẽ in thông báo:

LỖI. BÁNH GIÁ ÍT HƠN NỬA KHOẢNG CÁCH GIỮA CÁC ĐIỂM.

⟦folio 59⟧

Chữ khắc

Rất thường xuyên cần phải đặt một số dòng chữ trên bản vẽ. Với mục đích này, hệ thống Lời nói cung cấp các thủ tục INCAPTION, NPN và LINE.

Quy trình INscription (T, V, D) (viết tắt là NP (T, V, D)) cho phép bạn khắc họa dòng chữ ngang bằng các chữ cái thẳng (dọc). Tham số đầu tiên của thủ tục là văn bản được viết (hoặc tên có giá trị là văn bản). Điểm đặt pERO ​​được coi là góc dưới bên trái của dòng chữ. Từ thời điểm này, penERO bắt đầu vẽ. Tham số B chỉ định chiều cao của dòng chữ và tham số D chỉ định độ dài của nó.

Quy trình NPN (T, V, D) hoạt động theo cách tương tự nhưng tạo ra dòng chữ có góc nghiêng phải tiêu chuẩn.

Thủ tục LINE (T, X1, Y1, X2, Y2, X3, Y3) cho phép bạn vẽ văn bản T ở một vị trí tùy ý. Các tham số còn lại của thủ tục này là tọa độ của ba điểm: (X1, Y1), (X2, Y2) và (X3, Y3). Văn bản phù hợp với hình bình hành, các đỉnh của nó là các điểm này (đỉnh thứ tư rất dễ hoàn thành). Điểm đầu tiên trong số này được coi là đỉnh dưới bên trái của hình bình hành, điểm thứ hai - phía trên bên trái và điểm thứ ba - phía dưới bên phải. Bằng cách thao tác các điểm này, bạn thậm chí có thể có được các dòng chữ ngược và phản chiếu qua gương.

Trong tất cả các thủ tục này, các dòng chữ được viết bằng chữ thường; nếu chúng ta muốn viết hoa chữ cái thì chúng ta cần đặt một dấu kép ở phía trước nó trong văn bản.

Ví dụ về các quy trình được mô tả được hiển thị trong Hình 5, được thực hiện bằng chương trình sau:

`:QUANTUM' -> A;

P(100, 100); P (10, 85); NP (A, 10, 30); P (60, 85); NPN (A, 10, 30); HÀNG(A, 60, 40, 60, 47, 80, 20); HÀNG(A, 60, 50, 60, 67, 80, 70); HÀNG(A, 40, 40, 40, 47, 20, 20); HÀNG(A, 40, 57, 40, 50, 20, 77); .KẾT THÚC;

Thay đổi hệ tọa độ
Hệ tọa độ được thiết lập bởi thủ tục FRAME có thể được thay đổi. Đối với điều này, các quy trình QUY MÔ, BẮT ĐẦU, XOAY và một số thủ tục khác được sử dụng.

Thủ tục SCALE(A) (viết tắt là M(A)) đặt đơn vị thang đo mới bằng A mm.

Thủ tục ORIGIN(X,Y) (viết tắt là H(X,Y)) chuyển gốc tọa độ về điểm (X, Y) của hệ thống hiện tại; quy trình ROTATION (A) quay hệ tọa độ theo góc A xung quanh tọa độ tác động. Góc được xác định bằng radian, khi A>0 thì quay ngược chiều kim đồng hồ, khi A<0 - theo chiều kim đồng hồ.

Nếu thủ tục START và ROTATE được sử dụng nhiều lần trong cùng một chương trình thì mỗi thủ tục đó sẽ được sử dụng trong hệ tọa độ do quy trình thiết lập và cuối cùng rất khó để xác định hệ tọa độ nào đang có hiệu lực tại một thời điểm nhất định. Do đó, quy trình RESET không tham số (viết tắt là C) được cung cấp để khôi phục hệ tọa độ tiêu chuẩn.

Bạn có thể chuyển từ hệ tọa độ chuẩn sang tọa độ cực bằng quy trình không có tham số POLAR. Trong trường hợp này, trong tất cả các quy trình Lời nói, tham số X được coi là bán kính cực và Y là góc cực. Để trở về tọa độ Descartes (hình chữ nhật), hãy sử dụng quy trình DECARTES.

Ở đây chúng tôi chỉ mô tả các quy trình cơ bản của hệ thống Lời nói. Sử dụng cùng với chúng các thiết kế của nhiều ngôn ngữ lập trình, chu trình, mô tả quy trình, điều kiện kê đơn, v.v., bạn có thể sử dụng hệ thống Lời nói để có được nhiều bản vẽ và bản vẽ khác nhau, xây dựng biểu đồ của các hàm phức tạp, tạo phim hoạt hình và thực hiện các công việc đồ họa khác.
