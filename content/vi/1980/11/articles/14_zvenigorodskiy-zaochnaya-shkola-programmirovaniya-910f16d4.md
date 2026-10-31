---
id: 1980-11-zvenigorodskiy-zaochnaya-shkola-programmirovaniya-910f16d4
issue: kvant_1980_11
year: 1980
number: "11"
title: Trường lập trình tương ứng
authors:
  - Звенигородский Г. А.
rubric: raznoe
rubric_sub: Разное
page_first: 44
page_last: 46
page_labels: 42-44
tag: 80JC
lang: vi
source: kvant_digital
extraction: vision
content_sha256: 4d3eeeb085ee9f3e7ab91e3a4f4ecbb3d57260b6f1a9476069f6ed732bf46a52
prompt_sha256: draft-1
translated_from: content/ru/1980/11/articles/14_zvenigorodskiy-zaochnaya-shkola-programmirovaniya-910f16d4.md
source_content_sha256: 694f68725d6bbb3705d473dc57fdfb892dc69dfa4ff3ac4b12b01953904027ea
translation_model: draft
translation_run: vi-draft-2026-10-31
translation_quality: draft
---

⟦folio 42⟧

Trường lập trình tương ứng
Bài 11: Xử lý văn bản trên máy tính

Điều duy nhất là thay đổi tiêu đề đã cho và thay đổi một số chương từ ngôi thứ nhất sang ngôi thứ ba.

N.V. Gogol. "Áo khoác ngoài"

Xử lý văn bản được sử dụng ở đâu?

Xử lý văn bản ngày nay được phổ biến rộng rãi trong nhiều lĩnh vực ứng dụng máy tính. Ví dụ: phần lớn bài toán phát sinh trong quá trình chuẩn bị tự động để in sách, tạp chí, báo và các ấn phẩm khác đều có liên quan đến xử lý văn bản. Để xử lý thông tin văn bản, bạn có thể chuẩn bị phôi, mài và chà nhám bề mặt của tác phẩm, cắt cả hai đầu, kiểm tra ba lỗ, cắt một sợi ở một trong số chúng và phủ một lớp sơn điện. Hãy nghĩ ra phương pháp mã hóa các hướng dẫn công nghệ và viết nó ra dưới dạng văn bản.

Nhiệm vụ 11.2. Để chế tạo một bộ phận, cần phải dập phôi, mài và chà nhám bề mặt của chi tiết, cắt hai đầu, kiểm tra ba lỗ, cắt ren ở một trong số chúng và phủ một lớp sơn kín. Hãy nghĩ ra phương pháp mã hóa các hướng dẫn công nghệ và viết nó ra dưới dạng văn bản.

Nhiệm vụ 11.3. Về mặt sinh học, Young đã phát minh ra một hệ thống như vậy để ghi lại những quan sát của họ về hành vi của động vật trong điều kiện tự nhiên: chữ C biểu thị giấc ngủ của động vật, O - săn bắn, K - cho ăn, B - tưới nước, D - chiến đấu, I - tsera, U - chăm sóc trẻ em. Hãy miêu tả bằng lời hành vi của con vật được thể hiện trong đoạn văn sau:

'OVOXVDKIS'—>THÚ VẬT;

Bạn nghĩ các chàng trai đã theo đuổi loại động vật nào: đó là động vật thân thảo hay động vật thân thảo, trẻ hay già?

Các dạng xử lý văn bản đơn giản
Một trong những hình thức xử lý văn bản đơn giản nhất là đếm số lượng chữ cái nhất định hoặc tổ hợp các chữ cái (nhiệm vụ 4a và 46 của Olympic Lập trình - «Kvant», 1980, số 3). Khi chuẩn bị các ấn phẩm và tài liệu in, bài toán như vậy tương đối hiếm, nhưng với lời giải bài toán từ các khu vực khác thì điều đó rất phổ biến. Ví dụ: bằng cách này, bạn có thể xác định tỷ lệ phần trăm valium trong protein, đếm số lượng mũi khoan khi xử lý một bộ phận hoặc

⟦folio 43⟧

số trường hợp con vật ngủ ngay sau khi ăn.

Hãy mô tả hàm COUNT1 với hai tham số - LETTER và TEXT, hàm này sẽ đếm số lần một chữ cái nhất định xuất hiện trong văn bản:

PERCENT COUNT1 VĂN BẢN THƯ => BỘ ĐẾM;
0 —> BỘ ĐẾM; 1 —> SỐ;
SỐ TẠM BIỆT = < (≠ TEXT) ::
NẾU VĂN BẢN[SỐ] = THƯ
SAU ĐÓ BỘ ĐẾM + 1 —> BỘ ĐẾM
TẤT CẢ;
SỐ + 1 --> SỐ;
TẤT CẢ
KSC;

Kiểm tra xem giá trị của hàm COUNT1('K', TRAIN) có phải là 5 không.

Nhiệm vụ 11.4. Mô tả hàm COUNT2(SGMENT, TEXT), đếm số đoạn đã cho của chuỗi chữ cái trong văn bản. Ví dụ: giá trị của hàm COUNT2('KU','COOK') là 2.

Thường thì bạn cũng phải giải quyết vấn đề này bài toán: xây dựng một bảng tóm tắt về số lần lặp lại của mỗi chữ cái được tìm thấy trong văn bản. Thật thuận tiện khi biểu diễn một bảng như vậy dưới dạng một tập hợp bao gồm các bộ dữ liệu có dạng <LETTER, SỐ LẶP LẠI>.

Ví dụ: đối với văn bản “KUKAREKU”, bảng có thể trông như thế này: <*<'К',3>, <'У',2>, <'A',1>, <'P',1>, <'E',1>*>.

Rõ ràng là để xây dựng một bảng, bạn cần xem qua toàn bộ văn bản và đối với mỗi chữ cái của nó, hãy kiểm tra xem có một bộ dữ liệu nào trong bảng hay không, phần tử đầu tiên của nó là chữ cái này. Nếu có một bộ dữ liệu như vậy, thì bạn cần thêm một bộ dữ liệu vào phần tử thứ hai của nó, và nếu không, bạn cần thêm một bộ dữ liệu mới vào bảng, phần tử đầu tiên là chữ cái gặp phải và phần tử thứ hai là một. Quy trình tương ứng có thể trông như thế này:

VĂN BẢN BẢNG PERC => NHIỀU;
<**> —> NHIỀU; 1 —> SỐ;
SỐ TẠM BIỆT = < (≠ TEXT) ::
VĂN BẢN[SỐ] -> THƯ;
0 --> KIỂM SOÁT;
ĐỐI VỚI MỘT TẬP ĐOÀN::
NẾU TUPLE[1] = THƯ ĐẾN
TUPLE[2] + 1 —> TUPLE[2];
1 -> KIỂM SOÁT
TẤT CẢ
TẤT CẢ;
NẾU KIỂM SOÁT = 0 ĐẾN
NHIỀU + <THƯ,1> -> NHIỀU
TẤT CẢ
TẤT CẢ
KSC;

Hãy chú ý đến cái tên KIỂM SOÁT! Nó phải được đưa vào để kiểm tra xem bộ dữ liệu được yêu cầu có nằm trong số các phần tử của bộ MULTIPLE hay không. Bạn có thể in một bảng như vậy ở dạng thuận tiện, ví dụ như sau:

ĐỐI VỚI MỘT TẬP ĐOÀN::
IN('THƯ',TUPLE[1],
'MEETS',TUPLE[2]'TIME')
TẤT CẢ;

Chỉnh sửa

Xin vui lòng, các tác vụ văn bản thú vị nhất phát sinh khi xử lý văn bản “thực”: hình ảnh in, tài liệu, chương trình bằng nhiều ngôn ngữ lập trình khác nhau, v.v. Việc sử dụng máy tính cho phép bạn chỉnh sửa những văn bản đó một cách dễ dàng và nhanh chóng, thực hiện bất kỳ chỉnh sửa và thay đổi nào đối với chúng, in ở bất kỳ định dạng nào và đôi khi ở bất kỳ phông chữ nào (trong một trong các bài viết, chúng tôi sẽ cho bạn biết thêm về cách chuẩn bị hình ảnh in trên máy tính).

Một ví dụ điển hình của nhiệm vụ chỉnh sửa là bài toán 4v của Olympida: “Ở mọi nơi trong văn bản có tên ĐẶT HÀNG, hãy thay từ 'KAPIAN IVANOV' bằng 'MAJOR IVANOV'.” Hầu hết những người tham gia Olympias không hoàn toàn đối phó với nhiệm vụ này, nhưng hầu như không ai chú ý đến một điều tinh tế: khi tìm những nơi cần thay thế, cần phải tìm đoạn “KAPIAN IVANOV” (có khoảng trắng sau họ!), chứ không chỉ “KAPIAN IVANOV”, nếu không, chẳng hạn, Đại úy Ivanovsky, nếu họ của anh ta xuất hiện trong thứ tự, cũng hóa ra là thiếu tá.

Nhiệm vụ thay thế các từ trong văn bản, có tính đến các dạng ngữ pháp khác nhau (trong ví dụ của chúng tôi, các từ “KAPIAN IVANOV” có thể xuất hiện với nhiều nghĩa khác nhau) khó lập trình hơn nhiều. Tuy nhiên, Akaki Akakievich của Gogol, như chúng ta biết, cũng không hoàn thành được nhiệm vụ này. Kiểu chỉnh sửa văn bản phức tạp này được thực hiện một cách thuận tiện trong chế độ hội thoại, khi người vận hành xem qua văn bản và tìm những chỗ cần thay thế văn bản (đôi khi việc tìm kiếm như vậy có thể diễn ra với một “gợi ý” từ máy) và bản thân việc thay thế được thực hiện bởi máy tính.

Để làm việc ở chế độ này, thật thuận tiện khi mô tả trước các quy trình thực hiện các thao tác phổ biến nhất (tìm kiếm đoạn văn bản mong muốn, thay thế, xóa, chèn, xuất ra thiết bị đầu cuối, v.v.),

⟦folio 44⟧

và sau đó sử dụng các thủ tục này như chỉ dẫn trong quá trình đối thoại.

Nhiệm vụ 11.5. Mô tả quy trình REPLACE(TEXT,STAR,NEW), quy trình này sẽ thay thế các phép gán ký tự nhất định bằng một đoạn văn bản nhất định trong văn bản có tên TEXT. Tham số thứ hai của quá trình này là đoạn văn bản được thay thế và tham số thứ ba là đoạn văn bản được thay thế.

Gợi ý và e. Nếu độ dài của đoạn văn bản cũ và mới không khớp nhau thì phải sử dụng phép nối chuỗi để thay thế chính xác. Ví dụ: nếu từ “KRONDIL”, nằm trong văn bản có tên BARMALEY, bắt đầu từ vị trí thứ 128, cần được sửa thành “CROCODILE”, thì có thể thực hiện như sau:
BARMALEY[1:130] + 'KO'
+ BARMALEY[132:(≠BARMALEY)]
-> BARMALEY;
Thay vào đó, nếu bạn cố gắng sử dụng một bài tập đơn giản, bạn sẽ không thể sửa được lỗi: sau bài tập 'KO'-> BARMALEY[131:131];
nó sẽ trở thành "CROCDIL".

Thủ tục REPLACE cho phép bạn sửa lỗi và thực hiện các thay đổi đối với văn bản. Nhưng bạn cần sử dụng cẩn thận để không phát sinh lỗi mới. Hãy xem xét một ví dụ đơn giản. Giả sử rằng trong văn bản có tên sách giáo khoa bạn phải in định dạng sau:
SIN (X) + COS (X) = S;

Trong khi xem văn bản này trên màn hình thiết bị đầu cuối, người vận hành nhận thấy có lỗi. Dòng trông như thế này:
SIN (S) + COS (X) = S;
Người điều hành đã cố gắng sửa nó và gõ lệnh sau:
REPLACE(sách giáo khoa,'S','X');
Nhìn qua nơi này một lần nữa, anh ngạc nhiên khi thấy hình thức đã mang một diện mạo hoàn toàn kỳ lạ:
XIN (X) + COS (X) = X.

Lý do rất rõ ràng: tất cả các chữ cái “S” trong sách giáo khoa (và không chỉ ở dòng này!) đã được thay thế bằng “X”.

Nhiệm vụ 11.6. Viết chỉ thị REPLACE chính xác để sửa tùy chọn ban đầu đầu tiên.

dòng này (có thể ảnh hưởng đến các phần khác của văn bản xác nhận quyền sở hữu).

Nếu toàn bộ cuốn sách hoặc chương trình lớn được lưu trữ trong bộ nhớ dưới dạng một văn bản dài thì việc chỉnh sửa văn bản đó sẽ không thuận tiện lắm. Với mỗi lần sửa chữa, cần kiểm tra xem phần văn bản được thay thế hoặc loại bỏ không bị lặp lại ở chỗ nào khác. Tất nhiên, việc kiểm tra như vậy có thể được giao cho máy (sử dụng quy trình COUNT2 ở trên), nhưng thông thường sẽ thuận tiện hơn khi chỉ cần chỉ ra chính xác vị trí điều chỉnh. Để làm điều này, văn bản lớn được chia thành các phần ngắn 50-60 ký tự - dòng và các dòng được tạo thành từ một bộ tuple. Mỗi dòng hoàn toàn hiển thị trên màn hình đầu cuối, vì vậy việc chọn cách chỉnh sửa phù hợp rất dễ dàng: bạn không cần phải lo lắng về sự an toàn của phần còn lại của văn bản. Trong lệnh REPLACE, với phương thức biểu diễn văn bản này, một tham số khác sẽ xuất hiện - số dòng cần thực hiện thay thế.

* Nhiệm vụ 11.7. Tạo một quy trình để kiểm tra vị trí chính xác của dấu ngoặc theo định dạng được biểu thị bằng văn bản có tên FORM. Dấu ngoặc đơn được coi là được đặt chính xác nếu có thể thiết lập sự tương ứng một-một giữa dấu ngoặc đơn mở và đóng sao cho mỗi dấu ngoặc đơn mở tương ứng với dấu ngoặc đơn đóng sau nó. ()()()() là ví dụ về cách đặt dấu ngoặc đơn đúng. Dưới đây là ví dụ về vị trí không chính xác: )(),()(),()(),()(),()().

Gợi ý và e. Đối với lời giải này bài toán, sẽ thuận tiện hơn khi sử dụng một ví dụ đơn giản gọi là thuật toán Rutishauser. Hãy gán tên COUNTER giá trị 0 và xem qua văn bản FORMS từ trái sang phải. Sau khi tìm thấy dấu ngoặc đóng, chúng tôi sẽ trừ một giá trị khỏi giá trị của tên COUNTER và sau khi tìm thấy dấu ngoặc mở, chúng tôi sẽ thêm một dấu ngoặc mở. Nếu ở cuối quá trình xem xét, tên COUNTER là dương thì thiếu dấu ngoặc đơn đóng. Nếu trong khi xem tên này, nó trở thành số âm ít nhất một lần, điều đó có nghĩa là dấu ngoặc đơn được đặt không chính xác. Nếu trong quá trình xem xét, nó không trở thành số âm và đến cuối nó bằng 0, thì mọi thứ đều ổn (chứng minh điều đó!).

G. Zvenitsgorodsky
