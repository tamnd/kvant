---
id: 1979-7-sadovskiy-arshinov-dvoichnoe-kodirovanie-9d796ae0
issue: kvant_1979_7
year: 1979
number: "7"
title: Mã hóa nhị phân
authors:
  - Садовский Л. Е.
  - Аршинов М. Н.
rubric: osnovnye-stati
page_first: 16
page_last: 22
page_labels: 14-20
tag: EP49
lang: vi
source: kvant_digital
extraction: vision
content_sha256: 529e912a6a1daf8277433464a63836366f974bdb2783aaa9f90bd8d2cc590890
prompt_sha256: draft-1
translated_from: content/ru/1979/07/articles/04_sadovskiy-arshinov-dvoichnoe-kodirovanie-9d796ae0.md
source_content_sha256: 0cd952f807cd4305f759389dbb70cc2efec7f4d696a2f961361d1f8b26f2ab08
translation_model: draft
translation_run: vi-draft-2026-10-31
translation_quality: draft
---

⟦folio 14⟧

Mã hóa nhị phân

Thông điệp được truyền qua đường dây liên lạc như thế nào? Sơ đồ truyền như vậy được thể hiện trong hình.

Thiết bị mã hóa liên kết mỗi tin nhắn được truyền với một tổ hợp tín hiệu nhất định (có thể chấp nhận để truyền qua một kênh liên lạc nhất định), được gọi là mã. Hoạt động truyền một thông điệp thành một chuỗi các tín hiệu khác nhau được gọi là mã hóa, phép biến đổi ngược bao gồm thông điệp được truyền từ các tín hiệu nhận được được gọi là giải mã. Mã sử ​​dụng hai chip khác nhau được gọi là mã kép. Mã phương ngữ điện thoại là Morse và Baudot. Trong mã Morse, mỗi chữ cái được liên kết với một chuỗi cụ thể của các xung dòng điện ngắn hạn (gọi là vòng đệm) và dài hạn (thế giới). Trong mã Baudot, mỗi chữ cái được liên kết với một chuỗi cụ thể của một mảng tín hiệu cơ bản - xung và tạm dừng.

Quá trình mã hóa, khi có nhiều loại khác nhau, các yêu cầu đối với chúng và nhiều vấn đề liên quan đều được nghiên cứu bằng lý thuyết thông tin và mã hóa. Nó kết hợp các phương pháp xác suất, đại số và tổ hợp.

Ở đây chúng tôi chỉ tập trung vào một số vấn đề cụ thể về mã hóa và chúng tôi giới thiệu những độc giả quan tâm đến những cuốn sách đặc biệt - ví dụ: A. M. Yaglom và I. M. Yaglom “Xác suất và thông tin” (M., “Hayka”, 1973), W. Peterson “Mã sửa lỗi (M., “Mir”, 1964), W. Peterson, E. Weldon “Mã sửa lỗi (M., “Mir”, 1964), W. Peterson, E. Weldon “Mã sửa lỗi (M., “Mir”, 1964), “World”, 1976).

Chúng tôi hỏi - chúng tôi trả lời

Mã hóa kép dựa trên một nguyên tắc rất đơn giản. Hãy giải thích điều này nhé bài toán.

Ai đó đã nghĩ ra một số từ 0 đến 7. Người đoán được phép đặt câu hỏi, đáp số và chỉ được trả lời dưới dạng “có” hoặc “không”. Bạn có thể hỏi bao nhiêu câu hỏi để biết chắc chắn con số dự định?

Cách dễ dàng nhất (đây là điều mà một đứa trẻ có thể sẽ làm) là sắp xếp các số một cách ngẫu nhiên, tìm

⟦folio 15⟧

chúc may mắn. Với tác động rất mạnh, nó có thể lưu trữ dù chỉ một câu hỏi, nhưng nếu không may mắn, bạn có thể nhận được tới bảy câu hỏi. Do đó, chúng ta hãy từ bỏ hy vọng thành công ngay lập tức và cố gắng xây dựng một hệ thống câu hỏi sao cho bất kỳ câu hỏi nào trong số đáp số trên đó - “có” hoặc “không” - đều cung cấp cho chúng ta thông tin tương tự (trống, mặc dù không đầy đủ) về số dự định và số lượng câu hỏi là tối thiểu.

Ví dụ: câu hỏi đầu tiên có thể là: “Con số dự kiến ​​có nằm trong khoảng từ 0 đến 3 không?” Cả đáp số - cả “có” và “không” - đều đưa chúng ta đến gần mục tiêu hơn: trong trường hợp chung, vẫn còn bốn khả năng cho một số chưa biết (ban đầu chúng được hát).

Nếu câu hỏi đầu tiên nhận được đáp số khẳng định, thì lần thứ hai bạn có thể hỏi: “Số dự kiến ​​là 0 hay 1?}; nếu đáp số là số âm, chúng ta hỏi: “Số dự định là 4 hay 5?”

Trong mọi trường hợp, sau đáp số câu hỏi thứ hai có hai khả năng lựa chọn. Để đưa ra lựa chọn cuối cùng này, một câu hỏi là đủ. Vì vậy, để đoán con số dự định, dù đó là con số nào, chỉ cần ba câu hỏi là đủ.

Nếu mỗi câu trong số hai câu đáp số “có” hoặc “không” thường được ký hiệu bằng các ký hiệu “0” và “1”, thì đáp số được viết dưới dạng một chuỗi bao gồm 0 và 1. Vì vậy, ví dụ: nếu trong ví dụ trên, số dự kiến ​​​​là 0, thì đối với mỗi câu hỏi trong số ba câu hỏi đáp số sẽ có “có”. Ba chữ “có” tương ứng với dãy 000.

Nếu số “3” được hình thành thì câu trả lời sẽ là: có, không, không. Nghĩa là, “ba” tương ứng với dãy 011. Dựa trên kết quả của đáp số, bạn có thể tạo Bảng 1 bên dưới. Những ai quen thuộc với hệ thống số kép sẽ nhận ra ở dòng dưới cùng ký hiệu kép của các số tương ứng ở dòng trên cùng.

Lưu ý rằng các tập hợp số từ 0 đến 7 có thể được coi là bất kỳ tập hợp nào có thể và chúng ta có thể xác định từng tập hợp đó

Bảng 1

⟦folio 16⟧

mã hóa các chuỗi 0 và 1 có độ dài 3. Chuỗi 0 và 1 có thể mã hóa bất kỳ tập hợp thông báo hữu hạn nào.

Thật vậy, có $2^3 = 8$ chuỗi kép có độ dài 3 (tất cả chúng đều được đưa ra trong bảng), chuỗi kép có độ dài 4 nhiều gấp đôi - có $2^4 = 16$. Nói chung, số chuỗi kép có độ dài $n$ bằng $2^n$. Do đó, nếu bạn cần mã hóa số 0 và số 1, chẳng hạn như 125 tin nhắn, thì chuỗi kép có độ dài 7 sẽ là quá đủ cho việc này (chúng tôi có sẵn $2^7 = 128$ trong số chúng). Cuối cùng, để mã hóa bất kỳ số lượng tin nhắn $M$ nào, có thể sử dụng chuỗi kép có độ dài $n$ sao cho $2^n \geq M$.

Mã fano

Việc mã hóa tin nhắn bằng các từ có cùng độ dài như chúng tôi đã làm ở trên có luôn mang lại lợi ích không?

Hãy tưởng tượng rằng một số tin nhắn phải được truyền đi khá nhiều, những tin nhắn khác - tương đối hiếm và những tin nhắn khác - trong những trường hợp rất đặc biệt. Rõ ràng là những từ tốt nhất đầu tiên nên được mã hóa bằng các từ ngắn, để lại những từ dài hơn cho các tin nhắn mã hóa ít xuất hiện hơn.

Trong toán học, thước đo tần suất xuất hiện của một thông điệp là xác suất của nó. Bất cứ ai không quen với khái niệm này đều có thể hình dung xác suất của một tin nhắn (tin nhắn) nhất định là tỷ lệ của các trường hợp nó xuất hiện trên tổng số tin nhắn (tin nhắn) đang được xem xét *). Xác suất của tin nhắn $A$ được ký hiệu là $P(A)$.

Đặt bốn tin nhắn $A_1, A_2, A_3, A_4$ có xác suất

$$P(A_1) = \frac{1}{2}, P(A_2) = \frac{1}{4}, P(A_3) = P(A_4) = \frac{1}{8}.$$

*) Ví dụ, hãy xem cuốn sách trên của A. Yaglom và I. Yaglom.

Điều này có nghĩa là, ví dụ: trong số 1000 tin nhắn được truyền đi, tin nhắn $A_1$ xuất hiện khoảng 500 lần, tin nhắn $A_2$ xuất hiện khoảng 250 lần và tin nhắn $A_3$ và $A_4$ mỗi tin nhắn xuất hiện khoảng 125 lần.

Những tin nhắn này có thể dễ dàng được mã hóa thành các từ kép có độ dài 2, như được hiển thị trong bảng:

| $A_1$ | $A_2$ | $A_3$ | $A_4$ |
| :--- | :--- | :--- | :--- |
| 00 | 01 | 10 | 11 |

Đồng thời, khả năng xảy ra của chúng không được tính đến. Bây giờ chúng ta hãy làm mọi việc khác đi. Chúng ta hãy chia các tin nhắn thành hai nhóm bằng nhau: nhóm đầu tiên chứa tin nhắn $A_1$, nhóm thứ hai - $A_2$, $A_3$, $A_4$. Chúng ta hãy liên kết nhóm đầu tiên với ký hiệu “0” và nhóm thứ hai với ký hiệu “1”. Điều này gần giống với hai nguyên tắc được sử dụng trong bài toán với việc đoán. Thật vậy, ký hiệu “0” tương ứng với đáp số “có” cho câu hỏi “Thư có thuộc nhóm đầu tiên không?” và “1” tương ứng với đáp số “không”. Sự khác biệt duy nhất là trước đây toàn bộ tập hợp được chia thành hai nhóm bao gồm cùng số phần tử, bây giờ - từ các phần tử khác nhau. Tuy nhiên, như trước đây, sự khác biệt là cả đáp số “có” và “không” đều có thể xảy ra như nhau. Tiếp tục với tinh thần tương tự, chúng ta hãy chia tập hợp thông điệp $A_2, A_3, A_4$ lại thành hai nhóm bằng nhau. Thông báo đầu tiên, bao gồm một thông báo $A_2$, chúng tôi khớp với ký hiệu “0”, thông báo thứ hai, bao gồm các thông báo $A_3$ và $A_4$, chúng tôi khớp với ký hiệu 1. Cuối cùng, chúng tôi chia nhóm hai thông báo còn lại thành các tin nhắn $A_3$ và $A_4$, chúng tôi khớp ký hiệu đầu tiên là 0, ký hiệu thứ hai – 1 (chúng đều đáng tin cậy như nhau). Quá trình này đã kết thúc. Thông báo $A_1$ ở bước đầu tiên đã hình thành một nhóm “độc lập” và ký hiệu 0 được liên kết với nhóm đó, mã hóa thông báo này. Thông báo $A_2$ hình thành một nhóm độc lập theo hai bước, ở bước đầu tiên nó tương ứng với ký hiệu 1, ở bước thứ hai - 0; điều này có nghĩa là tin nhắn $A_2$ được mã hóa bằng từ 10. Tương tự, đối với

⟦folio 17⟧

tin nhắn $A_3$ và $A_4$ lần lượt chúng ta có chuỗi 110 và 111. Vì vậy, chúng ta nhận được bảng mã sau:

| $A_1$ | $A_2$ | $A_3$ | $A_4$ |
| :--- | :--- | :--- | :--- |
| 0 | 10 | 110 | 111 |

Đây chính xác là phương pháp mã hóa do Fano đề xuất. Câu hỏi đặt ra: chúng ta đạt được gì so với mã thống nhất khi sử dụng mã Fano? Để trả lời câu hỏi này, hãy tưởng tượng rằng các tin nhắn $A_1$, $A_2$, $A_3$, $A_4$ được truyền liên tục - tổng cộng 1000 tin nhắn. Hãy tính xem cần bao nhiêu ký hiệu kép để truyền chúng bằng phương pháp mã hóa thứ nhất và thứ hai.

Khi sử dụng mã thống nhất, điều này không khó tính toán: mỗi tin nhắn có hai ký tự, nghĩa là có tổng cộng 2000 ký tự.

Bây giờ chúng ta hãy sử dụng mã Fano. Chúng ta hãy nhớ rằng trong số 1000 tin nhắn, tin nhắn đầu tiên xuất hiện khoảng 500 lần, được mã hóa chỉ bằng một ký tự (500 ký tự), 250 lần tin nhắn $A_1$ xuất hiện, nó được mã hóa bằng hai ký tự (500 ký tự khác), trên tin nhắn $A_3$ và $A_4$, xuất hiện khoảng 125 lần, nên cần phải sử dụng thêm các ký tự $3 \times 250 = 750$ khác. Tổng cộng, bạn cần truyền khoảng 1750 ký tự. Bạn sẽ thắng chứ? Chắc chắn. Thật vậy, trong trường hợp thứ hai, việc chuyển tiền sẽ mất ít thời gian hơn. Người ta có thể tưởng tượng một tình huống mà lợi ích từ việc sử dụng mã Fano hóa ra lại lớn hơn trong ví dụ đã cho.

Tin tưởng nhưng xác minh

Chúng ta đã chứng minh rằng bất kỳ tập hợp thông điệp hữu hạn nào cũng có thể được mã hóa bằng các từ mã 0 và 1 (từ mã nhị phân). Vấn đề là có thể xảy ra lỗi khi truyền tin nhắn được mã hóa.

Theo quy định, chúng tôi không có khả năng loại bỏ hoàn toàn nguồn gốc của sai sót. Vậy thì làm thế nào chúng ta có thể bảo vệ mình khỏi ảnh hưởng của họ và liệu điều này có thể xảy ra với tất cả mọi người không? Và nếu có thể thì với chi phí bao nhiêu?

Hóa ra những cơ hội như vậy - để phát hiện lỗi và thậm chí sửa chúng - vẫn tồn tại. Nhưng cái giá phải trả không thể tránh khỏi cho việc này là việc kéo dài các từ mã, tức là thêm một số ký tự nhất định. Những biểu tượng này không còn mang thông tin về các tin nhắn được truyền đi nhưng có thể cung cấp thông tin về các lỗi xảy ra trong quá trình truyền. Nói cách khác, mục đích của chúng là giám sát việc truyền từ mã chính xác. Các ký tự bổ sung được nhập vào được gọi là ký tự điều khiển (hoặc ký tự xác minh).

Tất cả một lần kiểm tra

Điều tối thiểu là chỉ thêm một ký tự xác minh vào mỗi từ mã. Hãy cùng tìm hiểu xem chúng ta có thể tin cậy vào điều gì trong trường hợp này. Đặt $\alpha_1 \alpha_2 \dots \alpha_n$ là từ mã kép ($\alpha_i = 0$ hoặc 1). Rõ ràng, sẽ thuận lợi hơn nếu chọn ký tự điều khiển $\alpha_{n+1}$ sao cho giá trị của nó bị ảnh hưởng bởi từng ký tự của từ mã. Đơn giản nhất là đặt $\alpha_{n+1} = \alpha_1 + \alpha_2 + \dots + \alpha_n$ (mod 2) *. Ký hiệu này có nghĩa là ký tự kiểm tra $\alpha_{n+1}$ bằng 0 nếu từ mã $\alpha_1 \alpha_2 \dots \alpha_n$ chứa số chẵn và một số khác. Ví dụ: thêm ký tự kiểm tra như vậy vào từ 1010, chúng ta được từ 10100; tương ứng từ 1110 ta được 11101.

Lưu ý rằng tất cả các từ mã đã xóa $\alpha_1 \alpha_2 \dots \alpha_n \alpha_{n+1}$ đều chứa một số từ mã, tức là $\alpha_1 + \alpha_2 + \dots + \alpha_n + \alpha_{n+1} = 0$ (mod 2). (1)

Chúng ta hãy tưởng tượng rằng trong quá trình truyền, một lỗi duy nhất (hoặc thậm chí bất kỳ số lỗi lẻ nào) được bao gồm trong từ mã từ xa $\alpha_1 \alpha_2 \dots \alpha_n \alpha_{n+1}$.

*) Bạn có thể đọc về phép cộng “modulo” trong bài viết “So sánh và các loại dư lượng” của N. Vilenkin («Kvant», 1978, số 10).

⟦folio 18⟧

bên). Khi đó trong từ độc quyền $\alpha'_1\alpha'_2 \dots \alpha'_n\alpha'_{n+1}$ số lượng đơn vị sẽ trở thành số lẻ. Điều này đóng vai trò như một dấu hiệu cho thấy từ nhận được có lỗi. Tất nhiên, chúng ta không cần đếm kỹ số lượng đơn vị; chỉ cần kiểm tra xem đẳng thức (1) có thỏa mãn đối với các ký hiệu của từ được chấp nhận hay không - điều này có thể dễ dàng thực hiện với thiết bị tính toán đơn giản nhất. Nếu đẳng thức (1) được thỏa mãn, chúng ta coi như thông báo đã được truyền chính xác, nếu không chúng ta tuyên bố rằng đã xảy ra lỗi và nếu có thể thì cần phải truyền lặp lại từ mã. Nhưng chúng ta không thể tự mình sửa lỗi được. Ví dụ: nếu nhận được "từ sai" 11100 thì có thể bất kỳ từ mã nào đã được gửi:

01100; 10100; 11000; 11110; 11101.

Mỗi trường hợp được liệt kê tương ứng với một lỗi duy nhất. Lỗi cũng có thể xảy ra ở ba hoặc thậm chí năm ký tự. Sẽ tệ hơn nhiều nếu có lỗi kép hoặc thậm chí là số lỗi chẵn. Rốt cuộc, sự tương ứng (1) sẽ không bị vi phạm và chúng ta sẽ coi từ bị bóp méo là đúng, kết quả là sẽ nhận được một tin nhắn sai.

Do đó, mã được mô tả (được gọi là mã chẵn lẻ chung) cho phép phát hiện số lỗi lẻ, nhưng dẫn đến giải mã không chính xác nếu có số lỗi chẵn. Tốt nhất nên sử dụng số dư khi xác suất xảy ra một lỗi duy nhất đủ cao và rất khó xảy ra lỗi ở số lượng ký hiệu lớn hơn.

Các mã có nhiều ký tự kiểm tra thường được sử dụng nhiều hơn - điều này không chỉ cho phép phát hiện mà còn sửa lỗi, không chỉ các ký tự đơn lẻ mà còn cho phép nhiều ký tự.

Kỹ thuật sửa lỗi đơn giản nhất là lặp lại từng ký hiệu thông tin nhiều lần để các ký hiệu 0 và 1 được mã hóa thành các khối gồm $n$ số 0 (tương ứng là $n$). Khi giải mã khối chữ cái $n$ chứa các ký tự có thể sai, lời giải được chấp nhận bởi “đa số phiếu bầu”. Nếu khối nhận được chứa nhiều số 0 hơn số 1 thì nó được giải mã thành 00 ... 0, ngược lại - là 11 ... 1. Quy tắc giải mã này cho phép bạn khôi phục chính xác các ký hiệu được truyền nếu nhiễu trong kênh làm biến dạng ít hơn một nửa số ký hiệu trong mỗi khối được truyền. Nếu độ dài của khối $n$ được chọn đủ lớn thì trên thực tế chúng ta sẽ tự bảo vệ mình khỏi những lỗi có thể xảy ra, nhưng việc truyền tin nhắn sẽ diễn ra với tốc độ nhanh hơn.

Khi kiểm tra tính chẵn lẻ chung và mã có sự lặp lại - hai phản mã. Cách đầu tiên rất nhanh nhưng thường “phù phiếm”. Về mặt lý thuyết, khả năng sửa lỗi của người thứ hai là vô hạn, nhưng nó thực hiện quá chậm.

Từ những thông điệp được trình bày trước đó, có thể thấy rằng để sửa lỗi cần phải sử dụng các từ để giải mã khá khác nhau. Trong trường hợp này, rất có thể khi truyền lỗi, rất có thể chúng sẽ vẫn khác nhau và những biến dạng không ngăn cản chúng ta “đoán” từ đã gửi.

Tổng khoảng cách chưa được đào tạo

Chúng ta đã đạt đến một khoảng cách có thể hiểu được giữa các từ mã. Khoảng cách (chính xác hơn là khoảng cách Hamming) $ρ(x, y)$ giữa hai từ mã $x, y$ là số lượng ký hiệu mà chúng khác nhau. Ví dụ: khoảng cách giữa các từ 1010111 và 0110010 là 4 - chúng khác nhau về các ký tự ở vị trí thứ 1, 2, 5 và 7.

Thuật ngữ “khoảng cách” cho đại lượng $ρ(x, y)$ được xác định bởi thực tế là nó có các tính chất cơ bản của khoảng cách tổng quát giữa các điểm trên mặt phẳng hoặc trong không gian (mục 4 trong “Hình học 6” hoặc mục 132 trong “Hình học 8”).

⟦folio 19⟧

Một đặc điểm quan trọng của khả năng hiệu đính mã là khoảng cách mã $d$, được định nghĩa là khoảng cách tối thiểu giữa các từ mã khác nhau $\min \rho(x, y)$.

Rõ ràng là khoảng cách mã càng lớn thì khả năng sửa lỗi của mã nhất định càng cao. Chúng ta có thể xây dựng thực tế này một cách chính xác hơn:

Để mã sửa các tổ hợp lỗi $t$ (hoặc ít hơn), điều cần thiết và đủ là khoảng cách mã của nó lớn hơn 2$t$.

Thật vậy, nếu đúng như vậy thì $\rho(x, y) \geq 2t + 1$ đối với bất kỳ từ mã nào $x$ và $y$. Nếu do sự biến dạng, cả hai từ biến thành một từ $z$ (tức là chúng trở nên thờ ơ), thì (do một trong những tính chất của khoảng cách - tiên đề tam giác)

$\rho(x, z) + \rho(z, y) \geq 2t + 1$, và do đó, $\rho(x, z) > t$ hoặc $\rho(z, y) > t$. Điều này có nghĩa là bất kỳ lỗi nào trong $t$ hoặc ít hơn ký tự của bất kỳ từ mã nào $x$ và $y$ đều khiến chúng vẫn khác nhau và do đó bản gốc có thể được khôi phục. Tuyên bố ngược lại thậm chí còn dễ dàng hơn để chứng minh.

Bài tập

1. Có 8 từ mã kép có độ dài 3. Chúng có thể được biểu diễn trong hệ tọa độ không gian dưới dạng các đỉnh của khối lập phương trên cạnh 1. “Ý nghĩa hình học” của khoảng cách giữa các từ mã trong trường hợp này là gì?

2. Chứng minh rằng mã kép tối đa có độ dài 5 (nghĩa là mã có tất cả các từ mã có độ dài 5) với khoảng cách mã là 3 chứa 4 từ mã. Chỉ định mã này.

3. Có mã nào có độ dài 20 chứa 1000 từ mã và sửa lỗi mã hóa có ba lỗi trở xuống không?

4. Chứng minh rằng để phát hiện được $s$ (hoặc ít hơn) lỗi thì cần và dư khoảng cách mã $d \geq s + 1$.

5. Chứng minh rằng để sửa lỗi $t$ (hoặc ít hơn) và đồng thời phát hiện $s$ ( ≥ $t$) thì khoảng cách mã phải thỏa mãn bất đẳng thức $d \geq t + s + 1$.

Mã Hamming

Đặt số lượng tin nhắn cần truyền đến thuê bao là 16. Để mã hóa chúng, bạn có thể sử dụng các từ có độ dài 4, nhưng khi đó mã sẽ không sửa được lỗi. Chúng ta đã biết rằng khi sử dụng các từ có độ dài 5, bất kỳ lỗi nào trong từ mã đều có thể được phát hiện, nhưng than ôi, không thể sửa được. Hai ký tự bổ sung cũng không đủ để sửa các lỗi đơn lẻ (hãy tự kiểm tra điều này).

Nhưng ba ký hiệu bổ sung có thể được sử dụng để xác định và sửa bất kỳ lỗi nào.

Giả sử rằng chúng tôi đã cố gắng chỉ định 16 từ mã có độ dài bảy - $\alpha_1\alpha_2\alpha_3\alpha_4\alpha_5\alpha_6\alpha_7$, theo mô hình hai, các đẳng thức sau được thỏa mãn:

$$\begin{cases}
S_1 = \alpha_4 + \alpha_5 + \alpha_6 + \alpha_7 = 0, \\
S_2 = \alpha_2 + \alpha_3 + \alpha_6 + \alpha_7 = 0, \\
S_3 = \alpha_1 + \alpha_3 + \alpha_5 + \alpha_7 = 0.
\end{cases}$$

Sau đó, chữ số mắc một lỗi duy nhất được biểu thị bằng số ký hiệu kép $S_1S_2S_3$ (hãy nhớ rằng mỗi $S_i$ là 0 hoặc 1). Đặc biệt, đối với từ mã, con số này là 0 (= 000), biểu thị rằng không có bit nào bị lỗi.

Tuyên bố được đưa ra dựa trên thực tế là với mã hóa của chúng tôi (tức là với bộ mã số của chúng tôi) cho một từ kép có độ dài 7 với một lỗi duy nhất $S_1 = 1$ nếu và chỉ nếu lỗi này xảy ra ở chữ số thứ tư, thứ năm, thứ sáu hoặc thứ bảy (xem (2)), $S_2 = 1$ nếu và chỉ khi lỗi ở chữ số thứ hai, thứ ba, thứ sáu hoặc thứ bảy và $S_3 = 1$ - khi ở chữ số thứ nhất, thứ ba, thứ sáu hoặc thứ bảy.

Ví dụ: Đặt $S_1 = 1$, $S_2 = 0$, $S_3 = 1$. Khi đó lỗi ở một trong bốn chữ số cuối ($S_1 = 1$), nhưng không có lỗi ở hai chữ số cuối ($S_2 = 0$); điều này có nghĩa là lỗi nằm ở chữ số thứ tư hoặc thứ năm; kể từ $S_3 = 1$, nó ở hạng thứ năm, nhưng $S_1S_2S_3 =$

⟦folio 20⟧

=101 chính xác là ký hiệu kép của số 5. ​​Các trường hợp còn lại được xử lý tương tự.

Vẫn còn phải tìm 16 từ mã thỏa mãn sự tương ứng (2). Để làm điều này, chỉ cần thay thế nếu $\alpha_1, \alpha_2, \alpha_3$ và $\alpha_4$ được chọn tùy ý và mod 2 thì các đẳng thức được giữ nguyên

$$\begin{cases}
\alpha_5 = \alpha_2 + \alpha_3 + \alpha_4, \\
\alpha_6 = \alpha_1 + \alpha_3 + \alpha_4, \\
\alpha_7 = \alpha_1 + \alpha_2 + \alpha_4,
\end{cases}$$

thì các tương ứng (2) là đúng.

Mã được nghiên cứu ở đây là mã Hamming có độ dài 7 với bốn ký hiệu thông tin.

Nói chung, các từ mã của mã Hamming kép sửa một lỗi đơn có độ dài $2^m - 1$. Để xác định vị trí của lỗi, cần phải kiểm tra $m$, tức là $m$ ký tự kiểm tra. Các ký tự $2^m - 1 - m$ còn lại mang tính thông tin.

Danh sách độc giả đã gửi quy tắc lời giải bài toán của Bài toán Kvant

Trong số này chúng tôi công bố họ của độc giả gửi quy tắc lời giải bài toán M516 - M530, F523 - F532 (các số in đậm sau họ là chữ số cuối cùng của các số đã giải bài toán).

Toán học

K. Abdukhalikov (Alma-Ata) 16-18, 19a), 20, 21, 26-28; E. Abramchkin (Kuibyshev) 16a); I. Avemisyan (làng Mulki, ArmSSR) 18; O. Avrammava (Moscow) 21; A. Adeev (làng Pokrovka AzSSR) 166), 21, 22, 24, 26; S. Aznabaev (Novotroitsk, vùng Orenburg) 26; V. Hayriyan (Hrazdan) 16a), 6) 18, 20, 22, 24, 26, 27; Z. Alaverdyan (Ijevan) 26; V. Aliev (Tbilisi) 26; V. Andrusevich (Kobrin) 28; R. Ardan (Lviv) 28; K. Aromamyan (Kafan) 26; N. Arutina (Kyiv) 28; A. Akhmetkhozin (Anjan) 27; A. Ashkinazi (Moscow) 16-19; D. Babarikin (Magnitogorsk) 16a); A. Badalyan (làng Berd, Cộng hòa xã hội chủ nghĩa Xô viết Armenia) 16, 21-23, 26-28, 30a); B. Baysakalov (Alma-Ata) 166), 18, 19, 21, 24, 26-29; A. Balinsky (làng Dublyany, vùng Lviv) 16, 18, 19, 21-24, 26-28, 30; I. Baranets (làng Dzerzhinsky, vùng Moscow) 26-28; A. Barvinok (Leningrad) 28, 29; A. Barre (Nikolaev)

16a; 6); B. Beun (Moscow) 16, 21; A. Beluosov (Kalinerrad, khu vực Moscow) 26; S. Bespamyatnykh (Artemovsky, vùng Sverdlovsk) 19a), 24, 27, 28; V. Bobov (Leningrad) 26; N. Bovsunovsky (làng Putlyuvchi, vùng Zhytomyr) 21; T. Bolotnikov (Kharkov) 16, 18, 19a), 21, 26, 28, 29, 30a); A. Bortsev (Leningrad) 19, 26-28; V. Borovko (Novopoloshk) 26; I. Borodin (Solikamsk) 22, 23; O. Bokhonov (Moscow) 21, 22, 236), 24, 26, 27, 30a); A. Bratsisky (Voronezh) 24; A. Burin (Moscow) 28; A. Vasiliev (Saratov) 16a), 21, 26, 28, 30a); S. Velikovich (Minsk) 28; V. Vinorezadov (Moscow) 16, 18, 19a), 21, 22, 23a), 24, 26-28, 30a); A. Voronov (Moscow) 16; A. Gabovich (Kharkov) 26; E. Gadzhilarov (Tbilisi) 26-28; A. Galenko (Moscow) 16a), 6), 26; E. Galstyan (làng Aygezard ArmSSR) 18; N. Gasilov (Baku) 26; K. Gedalin (Tbilisi) 26; A. Gilman (Moscow) 16, 18, 19, 21, 22, 24, 26-28; L. Gitlin (Vitebsk) 16a), 6), 21, 23; M. Gladina (V. Volochek) 21; Yu. Glukhov (Shelkovo) 166), 18, 21, 28; A. Golovin (Moscow) 21; O. Gordienko (Pavlodar) 16a), 21, 22, 27; M. Gorolev (Belorotsk) 16, 18, 19, 26, 28, 30a); G. Grabarnik (Tashkent) 26, 27, 29, 30a; G. Grabuzhik (Tashkent) 16, 18-24; P. Grigoruk (Gayvoron) 21, 24; N. Gribere (Kyiv) 26, 28; L. Groysman (Kharkov) 28; V. Guba (Vologda) 16, 18-21, 24-29;

(Tiếp theo trang 32)
