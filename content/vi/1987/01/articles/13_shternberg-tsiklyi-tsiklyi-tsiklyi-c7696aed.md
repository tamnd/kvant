---
id: 1987-1-shternberg-tsiklyi-tsiklyi-tsiklyi-c7696aed
issue: kvant_1987_1
year: 1987
number: "1"
title: Chu kỳ, chu kỳ, chu kỳ...
authors:
  - Штернберг Л. Ф.
rubric: raznoe
rubric_sub: Разное
page_first: 45
page_last: 48
page_labels: 43, 45, 46
tag: DCVI
lang: vi
source: kvant_digital
extraction: vision
content_sha256: 5fa1022484dccc7405db24b68947404127642172354a894986449e8927e1d2b7
prompt_sha256: draft-1
translated_from: content/ru/1987/01/articles/13_shternberg-tsiklyi-tsiklyi-tsiklyi-c7696aed.md
source_content_sha256: a1673b5960814355adb71def9cb115f2df52741074c3e69ad8c55647a7b1f8ca
translation_model: draft
translation_run: vi-draft-2026-10-31
translation_quality: draft
---

⟦folio 43⟧

Chu kỳ, chu kỳ, chu kỳ...

Ứng viên Khoa học Vật lý và Toán học
L. F. STERNBERG

Việc lập trình sẽ mất rất nhiều nếu không có khái niệm phân nhánh hoặc thuật toán trợ giúp, nhưng cốt lõi của chương trình vẫn là các vòng lặp. Tuy nhiên, vì một lệnh được viết bên trong một vòng lặp sẽ được thực thi nhiều lần, điều này mang lại ý nghĩa cho công việc biên dịch chương trình.

Bài toán lệnh thua được trả lời 3 trang trong SGK lớp 9 và giải được rất nhiều câu bài toán. 2 trang lý thuyết khác được giải đáp trong SGK “Informatικά-10” *); một công trình bổ sung được giới thiệu - một chu trình thuận tiện nhưng có thể được thực hiện mà không cần. Vậy chúng ta có thể nói gì về chu kỳ? Komy là một cụm từ không được giải thích trong tiếng Nga

trong khi điều kiện là mất hành động kts, từ đó nhận được lệnh

*) Đây là cách tác giả gọi ngắn gọn cuốn sách giáo khoa “Cơ bản về Tin học và Khoa học Máy tính,” Lưu ý. biên tập.)

số lần lặp lại (nếu thay từ “repeat” bằng từ “ncc”)? Chúng ta sẽ tiếp tục sử dụng từ “lặp lại” khi viết các lệnh chu trình - chu trình được viết theo cách này dễ đọc và dễ hiểu hơn. Tuy nhiên, các chu kỳ là khác nhau.

Hãy bắt đầu với bài toán đơn giản nhất: sử dụng những gì được mô tả trên trang. 78-81 của sách giáo khoa "Informatικά-9" nghệ sĩ đồ họa vẽ một cây trượng có chiều dài dòng là 50 và khoảng cách giữa các dòng là 3. Điều này có thể được thực hiện bằng chương trình sau (sau đây chúng tôi sẽ chỉ viết các chương trình, không có tiêu đề và không có mô tả):

k:=1;
cho đến khi k<5 lặp lại
phải (90); vẽ tranh; chuyển tiếp(50);
đừng vẽ; trở lại (50);
trái (90); tiến (3);
k:=k+1
kts

Nếu người biểu diễn của chúng tôi được chỉ huy bởi một người không quen với lập trình, thì anh ấy sẽ nói thế này: “làm như sau 5 lần: sang phải (90); kéo... về phía trước (3).” Và thực sự: chúng ta chỉ cần biến k để đếm số lần tổn thất vòng lặp; chúng ta không cần nó trong phần thân của vòng lặp; nhưng người biểu diễn không biết về điều này, và anh ta sẽ thành thật điền biến k và viết giá trị hiện tại của k vào đó: nếu nó được sử dụng trong tương lai thì sao?

⟦folio 45⟧

i:=0; y:=a[0];
cho đến khi tôi lặp lại
i:=i+1; y:=y·x+a[i]
kts

Hãy xem biến i: tại mỗi bước của vòng lặp, nó thay đổi thành cùng một giá trị (trong trường hợp này là 1) và chính biến này sẽ xác định thời điểm kết thúc vòng lặp. Đọc qua sách giáo khoa - trên hầu hết các trang, bạn sẽ tìm thấy một vòng lặp trong đó một số biến mỗi lần được thay đổi thành cùng một giá trị và chính giá trị của nó sẽ xác định mức độ hoàn thành của vòng lặp. Tình huống này xảy ra rất thường xuyên, vì vậy những vòng lặp như vậy được đặt một tên đặc biệt - những vòng lặp có tham số.

Tham số vòng lặp là cùng một biến thay đổi theo cùng một cách và dùng để xác định điểm kết thúc của vòng lặp. Ngoài ra còn có một mẫu ghi âm đặc biệt dành cho họ:

thay đổi tham số từ giá trị 1 trong các bước thành giá trị 2
lên tới giá trị 3 bước lặp lại kts

Ý nghĩa của cách xây dựng này, như mọi khi, tương ứng với ý nghĩa của cụm từ trong tiếng Nga. Với sự trợ giúp của nó, thuật toán sơ đồ Horner có thể được viết
y:=a[0];
thay đổi i từ 1 bước 1 thành n lặp lại
y:=y·x+a[i]
kts

Như bạn có thể thấy, ở đây tiêu đề vòng lặp quay về chính nó và đặt giá trị ban đầu của tham số, đồng thời thay đổi nó và kiểm tra phần cuối của vòng lặp. Trong trường hợp này, bước nếu bằng 1 thì không cần phải chỉ định. Vì vậy, trong trường hợp của chúng tôi, chúng tôi có thể viết

thay đổi i từ 1 thành n lặp lại

Vòng lặp như vậy thực tế tồn tại trong tất cả các ngôn ngữ lập trình, nhưng theo truyền thống, nó có dạng ký hiệu hơi khác:

for... from... step... to... Cycle và còn được gọi là “chu trình for”. Ở dạng này, nó được tìm thấy trong các ngôn ngữ Panipa, PL/1, Allol-60, Allol-68, v.v. Ngoài ra, trong một số ngôn ngữ (ví dụ: Fortran hoặc ngôn ngữ thuật toán trường học), giá trị cuối cùng trước tiên được chỉ định, sau đó là bước và trong một số (PL/1), bạn có thể viết cả hai cách.

Tại sao thiết kế chu trình này lại xuất hiện trong sách giáo khoa Thông tin-10? Thoạt nhìn, chu kỳ này, giống như chu kỳ lặp lại... lần, không mang lại cho chúng ta điều gì mới - chỉ có bản ghi đã trở nên giống nhau hơn: cùng nhau
x:=a;
cho đến khi x<b lặp lại
... x:=x+h;
kts

chúng tôi viết

thay đổi x từ bước h thành b lặp lại... kts thế là xong. Nhưng điều này không hoàn toàn đúng: ví dụ: nếu a=0, b=1, a h=0,1, thì cả hai chu kỳ sẽ diễn ra như nhau, nhưng nếu h=-0,1, thì chu trình sẽ xuất hiện (giá trị của a sẽ không bao giờ lớn hơn b) và chu trình với tham số chỉ đơn giản là không được thực hiện dù chỉ một lần: thực tế là trong chu trình này, điều kiện “x≤b” không chỉ được kiểm tra mà giá trị tham số được kiểm soát nằm trong khoảng từ a đến b; khi cố gắng rời khỏi phạm vi theo bất kỳ hướng nào, đặc biệt, nếu bước này không hướng tới b mà theo hướng ngược lại, chu trình sẽ không thực hiện. Vì vậy, một vòng lặp có tham số giống như một vòng lặp lặp lại...
thời gian là một công trình phòng thủ: những chu kỳ như vậy không bao giờ được bảo vệ.

Bài tập sử dụng chu trình cho (thay đổi chu trình) thuật toán KHAI THÁC và ĐẶT HÀNG (A7, A8 trên trang 93, “Thông tin-9”).

Nhưng ngay cả trong một vòng lặp có một tham số, một tình huống có thể phát sinh là không rõ trước phải thực hiện bao nhiêu bước để thay đổi tham số. Ví dụ: giả sử trong một bảng gồm M phần tử, chúng ta cần tìm vị trí mà phần tử bằng i xuất hiện. Để tìm kiếm một phần tử, bạn cần xem qua từng phần tử trong bảng, thay đổi chỉ số thành 1, nhưng không biết trước cần thực hiện bao nhiêu bước. Một cây nấm từ chu kỳ thay đổi và chu kỳ đồng thời sẽ giúp chúng ta đối phó với nhiệm vụ này:

thay đổi i từ 1 bước 1 cho đến a[i]≠x lặp lại kts Xin lưu ý: phần thân của vòng lặp trống - mọi thứ cần thiết đều được thực thi bởi tiêu đề vòng lặp; Vòng lặp thoát khi a[i]=x, trong khi i sẽ chứa số phần tử bảng nơi vòng lặp kết thúc.

Một chu trình như vậy tồn tại trong ngôn ngữ PL/1.

Rõ ràng là một giống lai cũng có thể được hình thành

tôi... từ... bước... lặp lại... cho đến khi... trong đó tham số được thay đổi và quá trình kiểm tra diễn ra ở cuối. Phương pháp tìm phần tử mong muốn trong bảng trên sẽ chỉ có tác dụng khi chúng ta chắc chắn về

⟦folio 46⟧

rằng phần tử bạn đang tìm kiếm có trong bảng. Nếu nó không có ở đó thì sau $M$ bước, giá trị $i$ sẽ vượt ra ngoài ranh giới của bảng và chúng ta sẽ nhận được thông báo lỗi hoặc máy tính sẽ bắt đầu làm điều gì đó không thể đoán trước. Hãy thay đổi thuật toán của chúng tôi để nếu thiếu phần tử bắt buộc, chẳng hạn, nó sẽ cung cấp cho chúng tôi một giá trị số 0. Có vẻ như bạn có thể làm điều đó như thế này:

thay đổi $i$ từ 1 bước 1 hiển thị $i \leqslant M$ và $a[i] \neq x$ lặp lại kts;
nếu $i > M$ thì $i := 0$; Tất cả;

nhưng điều này không thể thực hiện được: nếu không cần phần tử nào, thì ở bước $(M+1)$, ngay cả khi đã đảm bảo rằng $i > M$, máy tính vẫn sẽ cố gắng so sánh phần tử không tồn tại $a[M+1]$ với $x$ - và có thể đưa ra thông báo lỗi. Nhìn vào sách giáo khoa trên trang. 57, chúng tôi sẽ tìm cách thoát khỏi tình trạng này với cái giá phải trả là đưa ra một biến bổ sung và các so sánh bổ sung (số lượng so sánh cho ra không ít hơn gấp đôi), và sau khi nghiên cứu nó, chúng tôi thừa nhận rằng không phải ai cũng có thể tự mình nghĩ ra được. Bây giờ, nếu chúng ta có thể buộc máy tính so sánh $i$ với $M$ lần đầu tiên và chỉ thực hiện phép so sánh thứ hai nếu kết quả của lần so sánh đầu tiên là dương...

Nhưng người đọc có lẽ đã hiểu ý chính của chúng tôi: nếu chúng tôi không thoải mái khi làm việc, điều đó có nghĩa là chúng tôi đang thiếu một thứ gì đó và “cái gì đó” này cần được duy trì. Điều chúng tôi thiếu là khả năng thực hiện hai lần kiểm tra riêng biệt và hai lần thoát khỏi vòng lặp: khi phát hiện một phần tử và khi bảng hết. Xét rằng tìm kiếm bài toán là một bài toán rất phổ biến thì việc ra đời các công cụ tìm kiếm tiện lợi không phải là chuyện nhỏ. Nhưng nhận ra rằng có thể có nhiều hơn một lý do để thoát khỏi một chu kỳ là điều không đáng để giới hạn và suy nghĩ. Và giờ đây, cấu trúc vòng lặp mạnh mẽ và tiện lợi đã xuất hiện trong ngôn ngữ thuật toán của chúng tôi, bao gồm hầu hết tất cả các trường hợp cần thiết:

thay đổi...từ...bước...sang...
tạm biệt...lặp lại...lần
cơ thể chu kỳ
đến ... kts,

trong đó bất kỳ phần được gạch chân nào có thể vắng mặt và không nên có mặt cùng lúc -
