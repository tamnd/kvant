---
id: 1980-1-zvenigorodskiy-zaochnaya-shkola-programmirovaniya-4fcf1ae9
issue: kvant_1980_1
year: 1980
number: "1"
title: Trường lập trình tương ứng
authors:
  - Звенигородский Г. А.
rubric: raznoe
rubric_sub: Разное
page_first: 54
page_last: 56
page_labels: 52-54
tag: 5JAV
lang: vi
source: kvant_digital
extraction: vision
content_sha256: eea5e2549268176c4dcfa5e1f4f1eb55bd28a50e3d763b7360c7c305d0f661c1
prompt_sha256: draft-1
translated_from: content/ru/1980/01/articles/23_zvenigorodskiy-zaochnaya-shkola-programmirovaniya-4fcf1ae9.md
source_content_sha256: 0d749d66114057743d373cc22bfe759990f777c693284291ec67321713d4959e
translation_model: draft
translation_run: vi-draft-2026-10-31
translation_quality: draft
---

⟦folio 52⟧

Mục “Nghệ thuật lập trình” đã được xuất bản trên tạp chí của chúng tôi kể từ số 9 năm ngoái. Mục đích của nó gồm hai phần: thứ nhất, làm rõ các vấn đề chung liên quan đến máy tính - thuật toán và chương trình là gì, bộ nhớ và bộ xử lý của máy tính là gì, con người và máy tương tác như thế nào; thứ hai, dạy một số ngôn ngữ máy, dạy cách viết chương trình và gỡ lỗi trên máy tính thật.

Trường Lập trình Tương ứng được thiết kế để phát triển những kỹ năng này (xem «Kvant», 1979, Số 9). Các chữ ký mới «Kvant» có thể được đưa vào bắt đầu từ bài học này nếu các em đã quen với các ý tưởng cơ bản về lập trình bằng ngôn ngữ Robik («Kvant», 1979, Số 9-11).

Chúng tôi nhắc nhở các học sinh cũ và thông báo cho các học sinh mới rằng tất cả các bài tập của một vấn đề phải được hoàn thành TRONG MỘT SỔ TỔNG KÝ HỌC SINH (chứ không phải trên các tờ riêng!) và gửi cho chúng tôi bằng một lá thư đơn giản (KHÔNG ĐĂNG KÝ!) (không qua đường bưu điện) không muộn hơn ngày 20 của địa điểm tiếp theo, viết dòng chữ “QUANTUM” trên phong bì ở góc dưới bên phải, đến địa chỉ: 630090, Novosibirsk 90, Đại lộ Nuuki 6, Trung tâm Khoa học Máy tính của Trường Chi nhánh Siberia của Viện Hàn lâm Khoa học, Khoa Khoa học Máy tính, Trường Lập trình Tương ứng. Vui lòng gửi kèm một phong bì có địa chỉ của bạn và con dấu 6 điểm cho đáp số trong lô hàng của bạn.

Tân sinh viên nên đính kèm lời giải vào bài tập 5 của bài viết theo mẫu ghi ở «Kvant» năm 1979, số 9, tr. 45.

Trường lập trình tương ứng

Bài 5: Các toán tử cơ bản của ngôn ngữ Rapier

Trong các bài học trước, chúng ta đã được giới thiệu về ngôn ngữ giáo dục Robik, được thiết kế để dạy các khái niệm lập trình cơ bản và các kỹ năng thiết yếu cần thiết cho lời giải bài toán trên máy tính. Hôm nay, chúng tôi đang bắt đầu nghiên cứu một ngôn ngữ mới, mạnh mẽ hơn đáng kể, cho phép chúng tôi giải quyết không chỉ các vấn đề giáo dục mà còn cả các vấn đề thực tế, khoa học và công nghiệp quan trọng bài toán.

Trước khi đọc tiếp, hãy tự kiểm tra bằng cách trả lời các câu hỏi sau:

1. Đơn thuốc là gì? thủ tục? nhà điều hành? chỉ thị?

2. Làm thế nào để mô tả và gọi các thủ tục trong Robik?

3. Làm thế nào để soạn và đọc sơ đồ cú pháp?

4. Tên là gì? Ý nghĩa của cái tên có thể là gì? Làm cách nào tôi có thể gán ý nghĩa mới cho tên?

5. Cách ghi và thực hiện trình tự ghép như thế nào? lệnh niêm phong? điều kiện và đơn thuốc theo chu kỳ?

6. Tham số là gì và chúng được sử dụng để làm gì?

Nếu bất kỳ câu hỏi nào trong số này gây khó khăn cho bạn, hãy xem tài liệu của bài 1-4 («Kvant», 1979, No. 9-11).

Các quy tắc cơ bản của ngôn ngữ Rapier

Các quy tắc cơ bản của ngôn ngữ Rapier rất giống với các quy tắc của Robic. Bất kỳ chương trình nào cũng bao gồm các câu; Mỗi trong số chúng được theo sau bởi một dấu chấm phẩy. Đơn thuốc bao gồm các từ riêng lẻ. Các từ trong hầu hết các ngôn ngữ lập trình, bao gồm Robik và Rapik, có nghĩa là số, văn bản, tên, ký tự đặc biệt (ví dụ: dấu ngoặc,

⟦folio 53⟧

dấu hiệu của phép tính số học, v.v.) và cái gọi là từ khóa (ví dụ: các từ IF, THEN, ELSE trong điều kiện của toán tử Robik). Các quy tắc viết bằng Rapier hầu hết đều quen thuộc với bạn từ Robik:

Tên bao gồm các chữ cái và số, ký tự đầu tiên trong tên phải là chữ cái, ví dụ:

A5, HARE, LEAD, ĐƯỜNG, THỜI GIAN.

Số lượng ký tự trong một tên có thể là bất kỳ, nhưng máy phân biệt tên bằng sáu ký tự đầu tiên, do đó, theo quan điểm của nó, tên

CÁ SẤU, CÁ SẤU5, CROCODE và CÁ SẤU

- đó là cùng một tên. Để tránh sai sót, không nên sử dụng tên dài hơn sáu ký tự trong chương trình trừ khi thực sự cần thiết. Ngoài ra, nghiêm cấm sử dụng tên trùng với từ khóa. Ví dụ: từ IF không thể là tên.

Văn bản bao gồm bất kỳ ký tự nào được đặt trong dấu nháy đơn:

'ĐÂY LÀ VĂN BẢN TRÊN RAPIER'
'A+B+C9090=33/—/'.

Các con số được tạo thành từ các chữ số; Để tách phần nguyên khỏi phần phân số, người ta sử dụng dấu chấm:

2.521 21393 2345.00098

Các số phải có không quá 12 chữ số.

Chúng ta sẽ làm quen với các ký tự đặc biệt và từ khóa khi nghiên cứu các câu riêng lẻ.

Trong Rapier, không giống như Robik, nó được phép đặt nhiều câu trên một dòng hoặc ngược lại, viết một câu thành nhiều dòng. Bạn có thể chuyển sang dòng mới ở bất kỳ đâu trong câu, nhưng bạn không thể ngắt các từ của ngôn ngữ.

Hướng dẫn định giá

Chúng tôi sẽ hướng dẫn các bạn làm quen với các câu trong ngôn ngữ Rapier với câu gắn. Sơ đồ cú pháp của anh ấy rất đơn giản và điền vào sơ đồ viết tắt theo hướng dẫn của Robic:

Mũi tên -> đọc “gán”. Trên bàn phím của các thiết bị đầu cuối thông thường không có ký hiệu này nên để hiển thị mũi tên bạn phải nhấn hai phím: “—” (trừ) và “>” (lớn hơn).

Không giống như Robik, giá trị của trường biểu thức biến trong Rapier không chỉ có thể là tên, số hoặc chuỗi mà còn có thể là bất kỳ chuỗi số và tên nào được kết nối bằng các dấu ngoặc đơn và dấu ngoặc đơn được đặt chính xác. Trong toán học, một công trình còn được gọi là biểu thức số học. (Một lát sau, chúng tôi gặp nhiều cách diễn đạt khác trong Rapier.)

Ngôn ngữ Rapier sử dụng các ký hiệu số học sau:

+ phép cộng
- phép trừ
* phép nhân
/ phân công
! lũy thừa*)

Thứ tự thực hiện các phép tính cũng giống như thường lệ trong toán học; Đầu tiên, phép lũy thừa được thực hiện, sau đó là phép nhân và chia, và cuối cùng là phép cộng và phép trừ; trong trường hợp này, như thường lệ, sự hiện diện của dấu ngoặc đơn sẽ được tính đến. Kết quả của việc gắn tên sau mũi tên.

Rõ ràng là các toán tử tính toán đặc biệt (THÊM, SUBTRACT, v.v.) có sẵn trong Robik hóa ra lại hoàn hảo trong Rapier: mọi phép tính đều có thể được sử dụng trong chính toán tử cộng và các công thức được viết gần giống như trong toán học ở trường.

*) Ví dụ: $A^2$ được viết như sau: $A!2$.

⟦folio 54⟧

Ví dụ: để tính toán bằng công thức
$$y = 2,781 \cdot 250 + 500 - 92,5$$
chỉ cần viết
$$2.781 \cdot 250 + 500 - 92.5 \rightarrow y$$

Tuy nhiên, khi chuyển từ ký hiệu toán học sang chương trình trên Rapier, cần lưu ý rằng dấu nhân trong Rapier, không giống như toán học thông thường, không thể bỏ qua: thay vì 2AB bạn cần viết 2*A*B, thay vì $(A+B)$ $(A-B)$ bạn viết $(A+B)*(A-B)$.

Nhiệm vụ 5.1. Viết ra bằng ngôn ngữ Rapier một chuỗi hướng dẫn tính toán bằng các công thức:

$$A = 15; \quad B = 24;$$
$$C = 3A + A^3B^2 + (A+B)^5 - \frac{A^6}{25} + 33A^6;$$
$$K = 8C + A^2(A+B+C)^7 - 33 + \frac{(76A-34)}{58} + C^9;$$
$$J = \frac{K^8}{38} + \frac{5A}{8} + (A+K+B)^9 - 76 + 58C;$$

Nhiệm vụ 5.2. Tạo một bảng các giá trị và xác định giá trị của các tên này sau khi sử dụng chương trình:
$$2 \rightarrow A; \quad A!2 \rightarrow B;$$
$$B*A + (B+A+B)*A!2+A \rightarrow A$$
$$A*B \rightarrow C$$
$$C*2+B*8+C*2+A/2 \rightarrow A$$

Nhiệm vụ 5.3. Viết công thức trên Rapier để tìm nghiệm X1 và X2 của phương trình bậc hai*) $Ax^2+Bx+C=0$.

(Gợi ý dành cho học sinh lớp sáu và lớp bảy: $\sqrt{A}$ có thể viết là $A^{1/2}$.)

*) Chúng tôi nói với học sinh lớp sáu công thức này: $X_{1,2} = \frac{-B \pm \sqrt{B^2-4AC}}{2A}$.

Câu điều kiện và chu kỳ
Một câu điều kiện và tuần hoàn trong Rapier trông như thế này:

Dấu hiệu đặc biệt :: (hai dấu hai chấm) trong câu tuần hoàn có nghĩa là “lặp lại”.

Sự khác biệt chính giữa các sơ đồ này và sơ đồ Robik, rất dễ nhận thấy, là sau các từ TO và ELSE trong một câu điều kiện và sau dấu :: trong một câu tuần hoàn, bất kỳ số lượng câu nào được phân tách bằng dấu chấm phẩy đều có thể xuất hiện chứ không chỉ một câu duy nhất như trong Robik. Từ khóa BCE được đặt ở cuối cả hai câu.

Điều kiện trong trường hợp đơn giản nhất trông như sau:

Rapier sử dụng các dấu hiệu so sánh sau:
= bằng nhau
/ = không bằng
> hơn
< ít hơn
> = lớn hơn hoặc bằng
= < nhỏ hơn hoặc bằng

Ví dụ, sau khi thực hiện câu
ECIF $A>B$ ĐẾN $B \rightarrow C$
KHÁC $A \rightarrow C$ TẤT CẢ;
giá trị của tên $C$ trở thành giá trị nhỏ hơn trong số các giá trị của tên $A$ và $B$.

Chúng ta hãy xem xét kỹ hơn cách chương trình này hoạt động:
