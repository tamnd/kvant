---
id: 1981-4-pervin-trehadresnyie-odnoadresnyie-i-bezadresnyie-mashinyi-2dede3dd
issue: kvant_1981_4
year: 1981
number: "4"
title: Máy ba địa chỉ, một địa chỉ và... máy không địa chỉ
authors:
  - Первин Ю. А.
rubric: raznoe
rubric_sub: Разное
page_first: 53
page_last: 56
page_labels: 51-54
tag: PAYE
lang: vi
source: kvant_digital
extraction: vision
content_sha256: 4411ce56db72ef99f71d55307e487940be29d862d13d88b40be5c9b6b06f8434
prompt_sha256: draft-1
translated_from: content/ru/1981/04/articles/16_pervin-trehadresnyie-odnoadresnyie-i-bezadresnyie-mashinyi-2dede3dd.md
source_content_sha256: 53f66de7340630ea777c822cefd5fa7ca89f5339ad4d46f2eedd2227e26646ba
translation_model: draft
translation_run: vi-draft-2026-10-31
translation_quality: draft
---

⟦folio 51⟧

Máy ba địa chỉ, một địa chỉ và... máy không địa chỉ

Khi độc giả «Kvant» làm quen với hoạt động của thiết bị điều khiển *) của máy tính, họ coi các máy tính có định dạng lệnh như trong Hình 1. Phần địa chỉ của lệnh trong hình này được chia thành ba trường với địa chỉ của các toán hạng (các giá trị liên quan đến thao tác).

Mã hoạt động Trường địa chỉ thứ nhất Trường địa chỉ thứ 2 Trường địa chỉ thứ 3

Hình 1.

Trường địa chỉ đầu tiên chứa địa chỉ của toán hạng đầu tiên của thao tác đang được thực hiện và trường địa chỉ thứ hai chứa địa chỉ của toán hạng thứ hai. Trường địa chỉ thứ ba là địa chỉ kết quả. Cả ba địa chỉ đều có cùng độ dài. Định dạng lệnh này không cần thiết đối với máy BESM-2 ba địa chỉ cho đến ngày nay. Ví dụ: lệnh 01 0257 1023 0016 trong BESM-2 có nghĩa là thêm (mã thao tác - 01) giá trị được lưu trong từ máy tại địa chỉ 0257 với giá trị nằm trong từ máy tại địa chỉ 1023 và đặt kết quả vào từ máy có địa chỉ 0016.

Khi địa chỉ của một từ máy nằm trong bộ nhớ được ghi vào trường địa chỉ của lệnh (như trong trường hợp BESM-2), độ dài của trường địa chỉ được xác định bởi dung lượng RAM. Ví dụ: để các từ máy 4K = 2¹² = 4096*) từ RAM có các địa chỉ khác nhau, độ dài của một địa chỉ phải có ít nhất 12 chữ số kép.

Lệnh của máy unicast có dạng khác (Hình 2).

Mã giao dịch Trường địa chỉ

Hình 2.

Chỉ có thể chỉ định một địa chỉ trong trường địa chỉ của lệnh đó. Làm cách nào bạn có thể đặt địa chỉ của toán hạng thứ hai trong trường hợp này? Tôi nên gửi kết quả ở đâu? Để trả lời những câu hỏi này, bạn cần biết rằng trong máy địa chỉ đơn có một thanh ghi đặc biệt có độ dài bằng một từ máy. Thanh ghi này được gọi là bộ cộng. Anh ta tham gia thực hiện các nhiệm vụ thực tế của máy chỉ huy. Ví dụ: trong mã của một “ông nội” khác của máy tính tiên tiến - máy địa chỉ đơn "Ural-2" - việc cộng hai số được lưu trong bộ nhớ tại địa chỉ 0257 và 1023 và gửi kết quả đến địa chỉ 0016 được thực hiện bằng các lệnh sau:

02 0257 (gửi số từ máy có địa chỉ 0257 tới bộ cộng)
01 1023 (cộng nội dung của bộ cộng với số được lưu trong word máy tại địa chỉ 1023; kết quả thu được trong bộ cộng)
16 0016 (gửi một số từ bộ cộng trong từ máy đến địa chỉ 0016)

Bạn không nên nghĩ rằng chương trình này giống nhau bài toán trong máy một địa chỉ, giây luôn dài hơn trong máy ba địa chỉ. Trong phần lớn

*) Ở đây K không có nghĩa là khóa bằng 1024 byte mà đơn giản là số 1024 = 2¹⁰.

⟦folio 52⟧

Trong trường hợp thực tế (đặc biệt khi kết quả của một thao tác được sử dụng trực tiếp trong thao tác tiếp theo), cam kết của chương trình là nhỏ.

Đây là một ví dụ. Trong mã của chương trình máy ba địa chỉ, biểu thức tính toán $a^2+a-1$ được viết như sau:
03 A A B (nhân $a \cdot a$)
01 A B B (cộng $a^2+a$)
02 V C V (trừ $(a^2+a)-1$)

trong đó A là địa chỉ của số $a$, đơn vị được lưu tại địa chỉ C, B là địa chỉ của từ máy dùng làm từ trung gian. Trong máy một địa chỉ, chương trình tương tự trông như thế này:
02 A (gửi số $a$ tới bộ cộng)
06 A (nhân $a \cdot a$; kết quả là cộng)
01 A (cộng $a^2+a$; kết quả là cộng)
03 C (phép trừ $a^2+a-1$; kết quả là phép cộng).

Vì vậy, chương trình chỉ tăng thêm một lệnh (bạn có để ý rằng chương trình cuối cùng không chứa các từ máy trung gian không?). Nhưng việc tiết kiệm phần cứng trong máy địa chỉ đơn là rất đáng kể: xét cho cùng, phần địa chỉ của mỗi lệnh sẽ trở nên ngắn hơn.

Chắc hẳn sau đó người đọc sẽ thấy ngạc nhiên về một chiếc ô tô hai địa chỉ (chẳng hạn như những chiếc ô tô Minsk). Nhưng hóa ra ở đầu vào đầu tiên, chiếc xe có vẻ ngắn hơn, nhưng ở đầu vào thứ hai thì ngắn hơn. Nhưng hãy tưởng tượng rằng một máy tính có hai loại RAM: một loại là loại thông thường, lớn, trong đó cần có địa chỉ “dài” để chỉ ra vị trí của một từ máy; cái còn lại cực nhanh, có số lượng thanh ghi nhỏ, trong đó một địa chỉ rất “ngắn” là đủ cho một gợi ý một giá trị. Đây là những gì máy tính nhận được.

Tuy nhiên, trong các máy sau này, các thanh ghi dùng để xác định địa chỉ toán hạng lại có những cách sử dụng khác. Trong các máy lớn, địa chỉ liên quan đến lệnh trực tiếp tại thời điểm thực thi (cái gọi là “địa chỉ thực thi” không trùng với giá trị của trường địa chỉ mà được tính bằng giá trị của một số hàm. Hàm như vậy thường trông giống như tổng của giá trị được ghi trong trường địa chỉ (được gọi là khung) và nội dung của một thanh ghi (cơ sở) được chỉ định trong lệnh hoặc hai thanh ghi (cơ sở và chỉ mục). Ví dụ, trong máy BESM-6 (nếu chúng ta lạc đề từ một số chi tiết không quan trọng), định dạng của hầu hết các lệnh như trong Hình 3.

Hình 3.

Các số trong trường lệnh trong Hình 3 cho biết độ dài của trường tương ứng, được đo bằng hai chữ số. RAM BESM-6 chứa 32K=2$^{15}$ từ máy và số lớn nhất được ghi trong trường địa chỉ, trong mọi trường hợp, nhỏ hơn 2$^{13}$. Và ở đây, một trong mười sáu thanh ghi cơ sở $(2^4=16)$ đã được giải cứu, chính xác là thanh ghi có số (địa chỉ) được chỉ định trong trường thanh ghi cơ sở. Địa chỉ thực thi của các lệnh là tổng của giá trị mười lăm hàng được lưu trong thanh ghi cơ sở đã chỉ định và giá trị offset mười hai hàng. Ví dụ, lệnh

03 004 0231
với điều kiện thanh ghi thứ ba chứa số 12000, nó sẽ cộng (004 là mã phép toán cộng) nội dung của bộ cộng với số được lưu tại 12000+231=12231 và gửi kết quả đến bộ cộng. Ở đây 3 là địa chỉ (số) của thanh ghi cơ sở, 12000 là cơ sở, 231 là offset, 12231 là địa chỉ điều hành. Do đó, cơ sở có nghĩa là địa chỉ bắt đầu của một số RAM và địa chỉ của từ cần thiết trong vùng này có được bằng cách thêm phần bù vào cơ sở. Phương pháp đánh địa chỉ này được gọi là tương đối.

Nó thuận tiện vì nó cho phép bạn di chuyển các chương trình hoặc

⟦folio 53⟧

các phần của chương trình trên khắp RAM, để các chương trình không cần phải theo dõi các thay đổi của chương trình.

Thậm chí còn có nhiều khả năng đánh địa chỉ tiên tiến hơn trong các máy thuộc dòng máy tính EC. Bộ nhớ của các máy này được tạo thành từ một cộng đồng RAM và một bộ tương đối nhỏ (16) thanh ghi đa năng và hai trường địa chỉ thường được ghi trong phần địa chỉ của lệnh. Vì vậy, những máy này không chỉ có một mà có tới ba dạng lệnh. Đầu tiên trong số đó - “điện trở - điện trở” (Hình 4) - mô tả

| Mã hoạt động | P1 | P2 |
| :--- | :--- | :--- |

Hình 4.

lệnh hoạt động trên các số được lưu trong thanh ghi P1 và P2 và ghi kết quả vào địa chỉ P1. Định dạng thứ hai là “điện trở - bộ nhớ” (Hình 5). Ở đây Địa chỉ 2-20 operad

Hình 5.

địa chỉ của một trong các toán hạng (thứ hai) được chỉ định trong bộ nhớ. Địa chỉ điều hành có được bằng cách thêm hỗn hợp CM2 với các giá trị được lưu trong thanh ghi cơ sở B2 và thanh ghi chỉ số I2. Cuối cùng, trong các lệnh chuyển từ bộ nhớ sang bộ nhớ (Hình 6), cả hai toán hạng đều nằm trong bộ nhớ chính. Đối với mỗi người trong số họ, địa chỉ điều hành có được bằng cách thêm hỗn hợp với giá trị của thanh ghi cơ sở. Ngoài ra (đây là một tính năng của máy dòng EC), định dạng này chỉ định độ dài D1 và D2 ​​của các trường toán hạng, giúp nó có thể hoạt động không chỉ với các từ máy có một kích thước duy nhất mà còn với dữ liệu có độ dài dẫn xuất.

Chúng ta hãy quay trở lại hệ thống địa chỉ một lần nữa, được minh họa bằng hình vẽ. Máy ba từ (Hình 1) được đặc trưng bởi thực tế là tất cả các từ máy trong bộ nhớ của nó đều giống hệt nhau về mặt tổ chức và thời gian truy cập. Các máy có đặc tính này được gọi là máy tuyến tính hay chính xác hơn là máy có cấu trúc bộ nhớ tuyến tính. Đã có trong máy unicast chung (Hình 2), tính tuyến tính hơi bị hỏng: có một thanh ghi đặc biệt - bộ cộng - có thể lưu trữ thông tin giống như các từ máy khác trong bộ nhớ, nhưng rất khác với chúng. Đặc biệt, đây là sổ đăng ký duy nhất có thể gửi kết quả của một thao tác mà không cần chuyển trước. Trong các máy có thanh ghi cơ sở (Hình 3), tính tuyến tính bị vi phạm không chỉ bởi sự hiện diện của cơ sở và chỉ mục trong định dạng lệnh mà còn bởi khả năng làm việc với các từ có độ dài khác nhau. Đồng thời, về nguyên tắc, tất cả các máy này đều giữ nguyên cấu trúc tuyến tính của phần chính của RAM.

Nhưng trong các máy có cấu trúc bộ nhớ xếp chồng lên nhau, nguyên lý tuyến tính đã bị giáng một đòn nặng nề.

Cách dễ nhất để hiểu chồng sách là gì là hãy tưởng tượng một chồng sách trên bàn làm việc của bạn.

Địa chỉ 1-20 operad Địa chỉ 2-20 operad

Chiều dài 1-20 hoạt động
Chiều dài 2-20 hoạt động

⟦folio 54⟧

Hình 7.

(trong tiếng Anh “stack” đồng nghĩa với “stack”). Bạn chỉ có thể thêm sách vào chồng sách này bằng cách đặt cuốn sách cuối cùng mà bạn quan tâm lên trên cùng của chồng sách. Cuốn sách này, được đặt cuối cùng, hóa ra cũng là cuốn sách đầu tiên có sẵn. Tiếp theo, bạn cần một số cuốn sách ở giữa chồng sách, sau đó cuốn sách đầu tiên cần lấy trong quá trình tìm kiếm này sẽ là cuốn sách cuối cùng được đặt trên đầu chồng sách. Ngăn xếp là một nhóm các từ máy trong đó chỉ có một từ có sẵn tại một thời điểm, cụ thể là từ được viết lần cuối. Từ có sẵn này trên ngăn xếp được gọi là đỉnh của ngăn xếp và phần còn lại của ngăn xếp được gọi là phần thân của nó. Thêm một từ vào ngăn xếp có nghĩa là tạo một đỉnh mới; phần trên cùng trước đó trở thành phần tử thứ hai của ngăn xếp, một phần của phần thân. Việc lấy một từ ra khỏi ngăn xếp sẽ làm cho phần tử trên cùng của ngăn xếp trở thành phần tử ngay sau đỉnh ngăn xếp trước khi thao tác được thực hiện.

Nếu bộ nhớ máy tính được tổ chức dưới dạng ngăn xếp thì để thực hiện nhiều thao tác, không thể chỉ định địa chỉ của các toán hạng nếu trước đó chúng được đặt ở đầu ngăn xếp hoặc ngay sau ngăn xếp đó. Do đó, lệnh SL, chỉ được xác định bằng mã thao tác (và không có gì hơn!), thêm hai số, một trong số đó ở đầu ngăn xếp và số kia luôn ở ngay sau nó và đặt kết quả ở đầu ngăn xếp. Như bạn có thể thấy, không có phần địa chỉ nào trong lệnh. Do đó, các máy có cấu trúc bộ nhớ ngăn xếp được gọi là bộ phận không có địa chỉ và. Tất nhiên, thuật ngữ này không có nghĩa là máy từ trong bộ nhớ ngăn xếp không có địa chỉ. Các địa chỉ tồn tại, nhưng sau khi các toán hạng được đẩy vào ngăn xếp, không cần thiết phải cung cấp các địa chỉ này trong phần địa chỉ của hầu hết các lệnh máy.

Ví dụ: đây là chương trình tính toán biểu thức đã hoàn thành $a^2 + a - 1$ trong máy Elbrus, máy xếp chồng thế hệ thứ tư nhanh nhất của Liên Xô (A là thông tin về địa chỉ của giá trị $a$):

ZGTs1 (nạp số nguyên 1 vào đầu ngăn xếp - Hình 7, $a$)

LỊCH A (đặt giá trị nằm ở địa chỉ A ở đầu ngăn xếp; đỉnh trước đó được nhúng vào thân ngăn xếp - Hình 7, $b$)

DIVID (“phân chia” phần trên cùng: một thể hiện của giá trị được lưu ở đầu ngăn xếp hiện được viết thành từ ngay sau phần trên cùng; phần còn lại của ngăn xếp thậm chí còn giảm sâu hơn - Hình 7, $e$).

DIV (một “phép chia” khác: thực tế là trong các hoạt động tiếp theo sẽ cần ba bản sao của giá trị $a$ - Hình 7, $e$)

UMN (số biến nằm ở hai từ trên cùng của ngăn xếp; kết quả $a^2$ vẫn ở đầu ngăn xếp và các toán hạng đã sử dụng sẽ bị xóa khỏi ngăn xếp - Hình 7, $d$)

SL (cộng các số nằm ở hai từ trên cùng của ngăn xếp; kết quả $a^2 + a$ vẫn ở đầu ngăn xếp - Hình 7, $e$)

TÍNH TOÁN (phép trừ: từ trên cùng của ngăn xếp - tổng $a^2 + a$ - 1 bị trừ, nằm trong ngăn xếp ngay bên dưới trên cùng; kết quả vẫn ở trên cùng của ngăn xếp - Hình 7, $ж$)

Các lệnh của chương trình này được viết ở dạng hơi đơn giản hóa và không đưa ra một bức tranh hoàn chỉnh về hệ thống lệnh Elbrus rất phong phú và linh hoạt. Một bài viết riêng sẽ dành cho câu chuyện về chiếc xe này ở một trong những số sau «Kvant».
