---
id: 1983-2-shternberg-standartnyie-priemyi-programmirovaniya-8fd0aad1
issue: kvant_1983_2
year: 1983
number: "2"
title: Kỹ thuật lập trình tiêu chuẩn
authors:
  - Штернберг Л. Ф.
rubric: raznoe
rubric_sub: Разное
page_first: 56
page_last: 57
page_labels: 54-55
tag: CWJS
lang: vi
source: kvant_digital
extraction: vision
content_sha256: 73304fc2781db0ec4f15f487225d09f2b08148659b1914bc5ca41aed2fb71245
prompt_sha256: draft-1
translated_from: content/ru/1983/02/articles/14_shternberg-standartnyie-priemyi-programmirovaniya-8fd0aad1.md
source_content_sha256: 2bab37529391d5d0cf4d62e230ec6fd09fb78e986cd937559c947de89b567653
translation_model: draft
translation_run: vi-draft-2026-10-31
translation_quality: draft
---

⟦folio 54⟧

Kỹ thuật lập trình truyền thống

Bài 5. 2x2 trên máy tính hay Machine Arthmetic là bao nhiêu và cách xử lý

Kiến thức đáp số cho câu hỏi “2×2 là gì?” là một điều cần thiết hiện đại đối với một người khao khát tầm quan trọng của toán học ít nhất là trong phạm vi thang đo ban đầu. Máy tính trả lời câu hỏi này như thế nào? Điều ngạc nhiên là trên máy tính

$$2 \times 2 = 4$$
nhưng $2.0 \times 2.0 \neq 4.0$, chính xác hơn là $2.0 \times 2.0 \approx 4.0^*$

Thực tế là số nguyên là chính xác và số thực là gần đúng. Hơn nữa, tất cả các con số vẫn có một phạm vi thay đổi hạn chế. Lập trình viên nên rút ra kết luận gì từ điều này?

Hãy xem xét phần chuẩn bị lời giải bài toán được đưa ra trong bảng. Bài toán dường như cực kỳ dễ dàng đối với bạn và lời giải đã cho là không thể nghi ngờ. Tuy nhiên, tất cả lời giải đều không chính xác; chính xác hơn, kết quả có thể không chính xác hoặc không được đưa ra. Và điều này xảy ra do đặc thù của số học máy.

Các số thực trong máy tính được biểu diễn dưới dạng gọi là dấu phẩy động, tức là số a được biểu diễn dưới dạng $a \cdot n^6$, trong đó $1/n < |a| < 1$, n là cơ sở của hệ thống số mà máy tính này hoạt động (theo quy định, đây là hệ nhị phân hoặc hệ thập lục phân, tuy nhiên, hệ thống này hoàn toàn không quan trọng để hiểu ngày xảy ra sự việc). Giả sử máy tính của chúng ta hoạt động theo hệ thống số thập phân và có 4 chữ số cho mantisu và 1 chữ số cho thứ tự. Godda (xem Hình 1), chỉ các số và dấu hiệu của bọ ngựa và thứ tự được lưu trữ trong ô bộ nhớ, dấu chấm được ngụ ý trước chữ số đầu tiên của bọ ngựa và thứ tự hiển thị theo hướng nào và bao nhiêu chữ số mà điểm thực sự “nổi” (do đó có thuật ngữ “dấu phẩy động”). Do đó, biểu diễn tối đa của một số trong máy tính của chúng ta là $0.9999 \times 10^9$, tức là khoảng một tỷ.

Bây giờ hãy xem xét bài toán 2 và giả sử rằng $n = 1000$ và tất cả $a_i$ đều có giá trị xung quanh $2 \times 10^6$. Sau đó, nỗ lực lấy tổng của các phần tử mảng sẽ không mang lại kết quả vì tổng này không thể được ghi vào bộ nhớ máy tính. Để tránh điều này, công thức tính giá trị trung bình số học phải được viết lại dưới dạng

$$m = \sum_{i=1}^{n} \frac{a_i}{n}$$

và chia chương trình cho $n$ của mỗi $a_i$. Tất nhiên, điều này thay thế chương trình, nhưng chương trình ngắn hơn của chúng tôi hiển thị trong bảng có thể không tạo ra kết quả.

Bây giờ, với cùng $n = 1000$, chúng ta hãy giả sử rằng

$$\sum_{i=1}^{900} a_i = 9555, a_{901} = a_{902} = \dots = a_{1000} = 0.2.$$

Khi cộng $a_{901}$ với tổng tích lũy ta được $0.95552 \times 10^4$ nhưng máy tính sẽ loại bỏ dấu cuối cùng “2” (các bit vượt quá ranh giới của lưới bit sẽ bị mất). Do đó, 100 thành phần cuối cùng sẽ không đóng góp vào kết quả và sẽ dẫn đến sai số tổng (bằng $0.2 \times 100 = 20.0$).

(Trong trường hợp này, cần phải tính tổng riêng biệt tất cả các số có độ lớn nhỏ, sau đó sử dụng tổng kết quả làm phần tử để tính tổng tiếp theo.)

Có thể đưa ra ví dụ về luật kết hợp và luật phân phối*).

Máy tính thực hoạt động với phạm vi lớn hơn nhiều và độ chính xác cao hơn trong việc biểu thị các con số, do đó, trong hầu hết các trường hợp, không cảm nhận được sự khác biệt giữa số học máy và số học thông thường. Tuy nhiên, có những trường hợp khi chương trình Fortran, khi được truyền từ máy tính BESM-6 (hoạt động với độ chính xác khoảng 12 chữ số thập phân trên máy tính dòng EC (độ chính xác khoảng 7 chữ số thập phân), được ghi: độ chính xác thấp của máy tính EC dẫn đến lỗi do tích lũy lỗi.

Theo quy định, phạm vi và độ chính xác của máy tính là đủ để tránh. Vì vậy, việc cộng các số có thứ tự khác nhau rõ rệt một lần không làm chúng ta bận tâm: khi số đếm ở hàng triệu thì phần mười không quan trọng; và để mất độ chính xác khi liên tục thêm số lượng lệnh đóng, bạn cần thực hiện khoảng $10^8$ phép cộng trên máy tính EC và khoảng $10^{13}$ trên BESM-6. Các đặc điểm của số học máy bắt đầu ảnh hưởng nếu bạn cần độ chính xác gần bằng độ chính xác của máy tính hoặc nếu khối lượng tính toán đạt mức tới hạn đối với một máy tính nhất định.

*) Đối với những độc giả được thừa nhận, chúng tôi sẽ thông báo cho bạn rằng $2.0 \times 2.0$ vẫn chính xác bằng 4.0, vì cả 2.0 và 4.0 đều thể hiện chính xác trong bộ nhớ. Nhưng nếu một trong các thành phần có thể tính toán được, thì kết quả có thể không còn chính xác nữa: $(1.0/3.0) \times 6.0 \neq 2.0$, vì kết quả trung gian 1/3 không thể được biểu diễn chính xác trên các máy tính hoạt động trong hệ thống số kép hoặc số thập phân.

⟦folio 55⟧

Lời giải chuẩn bị bài toán

Nhiệm vụ 1 (bảng giá trị $x^2$)

$$x := a;$$
while $x < = b$ do
begin writeln $(x, '**2 =', x**2);$
$$x := x + h$$
end;

Nhiệm vụ 2 (trung bình số học).

$$s := 0;$$
for $i := 1$ to $n$ do $s := s + a[i]$:
$$s := s/n$$;

Nhiệm vụ 3 (popsk của một số nhất định).

$$k := 0; i := 1;$$
while $(i < = n)$ AND $(k = 0)$ do
begin if $a[i] = x$ then $k := i;$
$$i := i + 1$$
end;

Trong ví dụ được đề cập với chương trình Forteran, cần có độ chính xác $10^{-5}$ với độ chính xác của máy tính là $10^{-7}$ và độ chính xác $10^{-3}$ của chương trình trên máy tính EC đã được cung cấp.

Kết luận nào rút ra từ tất cả những điều trên? Chỉ có một kết luận duy nhất: người lập trình phải chuẩn bị tinh thần để gặp một cỗ máy số học. Chính xác thì anh nên làm gì khi gặp cô? Không có phương pháp chung và bạn phải chọn từ các tùy chọn sau.

a) Chứng minh rằng với một thuật toán cho trước, sai số của máy số học không vượt quá giới hạn chấp nhận được.

b) Chứng minh điều tương tự dưới các điều kiện bổ sung trên dữ liệu gốc (xác định rằng với dữ liệu của bạn mọi thứ sẽ đúng thứ tự, mặc dù điều này không thể được đảm bảo trong trường hợp chung).

c) Xây dựng thuật toán bù lỗi.

e) Sử dụng các phép tính có độ chính xác cao hơn (thực hiện bằng phần cứng hoặc phần mềm), cụ thể là tính toán chương trình trên một mẫu máy tính khác với số học chính xác hơn.

Trong thực tế, các phương án e) hoặc e) thường được sử dụng nhiều nhất. Trong một số ngôn ngữ lập trình (ví dụ như Fortran và PL/1), có thể chỉ định rằng các phép tính phải được thực hiện với độ chính xác cao hơn. Điều này trên máy tính EC được triển khai trong phần cứng (với một số phần mềm chậm) và trên BESM-6 - trong phần mềm (với phần mềm chậm đáng kể).

Tốt hơn hết là đừng so sánh số thực để tìm sự bằng nhau,

vì với xác suất gần một trăm phần trăm, chúng tôi nhận được kết quả “không bằng”. Vì vậy, toán tử ở nhiệm vụ 3

if $a[i] = x$ then...
nên được thay thế bằng
if abs $(a[i] - x) < eps$ then...

trong đó eps là hằng số được mô tả, ví dụ: eps = 0,0001 (tùy thuộc vào độ chính xác của máy tính và độ chính xác mà bạn cần). Khi đó các số hành động được coi là bằng nhau nếu chúng khác nhau không quá một số ε.

Trong nhiệm vụ 1, nếu $a = 0, b = 1, a h = 0,1$, thì chúng ta không có gì đảm bảo rằng chúng ta sẽ nhận được tất cả 11 giá trị hàm: sau khi thêm $x$ với $h$ 10 lần, chúng ta có thể nhận được một giá trị nhỏ hơn $b$ hoặc nhiều hơn $b$ một chút, và trong trường hợp sau, vòng lặp sẽ không còn hoạt động với giá trị đó nữa. Để đạt được kết quả mong muốn, bạn cần tổ chức một vòng lặp với các điều kiện while $(x < b + h/2)$ hoặc tính toán trước số lần lặp lại của vòng lặp $n := \text{round}((b - a)h)$ và tổ chức một vòng lặp cho $i := o$ đến $n$ làm... Tuy nhiên, đường dẫn này có thể không dẫn đến kết quả mong muốn: nếu giá trị $n$ (số bước cần thiết) đủ lớn thì khi toán tử được thực thi lặp lại $x := x + h$ có thể tích lũy lỗi vượt quá giá trị $h$. Sau đó, vòng lặp được tổ chức thông qua while sẽ được thực thi ít hơn một (hoặc thậm chí vài) lần và vòng lặp được tổ chức thông qua for sẽ được thực thi với số lần cần thiết, nhưng giá trị cuối cùng sẽ khác xa $b$. Để bù đắp cho điều này, chúng ta sẽ phải tổ chức vòng lặp như thế này:

$$n := \text{round}((b - a)/h);$$
for $i := 0$ to $n$ do
begin $x := a + i*h;$
writeln $(x, '**2 =', x**2)$
end;

(Tất nhiên, chương trình này sẽ chậm hơn, vì mỗi phép tính giá trị đối số đều yêu cầu các phép toán lớn.)

Sử dụng ba ví dụ đơn giản, chúng tôi đã kiểm tra việc thực hiện tùy chọn e) - sự phát triển của một thuật toán đặc biệt. Lưu ý rằng các tùy chọn e) và e) yêu cầu phải thực hiện các bước $a$ và $b$ như một phần của quy trình để đảm bảo rằng thuật toán đã phát triển tạo ra hiệu quả mong muốn. Nếu không thì đơn giản. Vì vậy, ví dụ, rất rõ ràng rằng

$$\sum_{i=1}^{k} \frac{a_i}{n} < \max\{a_i\} (k < n),$$

Có thể, khi tính toán bằng công thức $\sum \frac{a_i}{n}$, việc tràn không làm chúng tôi bận tâm—biến thể $a$ đã được chứng minh. Nhưng nếu $n \cdot \max\{a_i\}$ nhỏ hơn số biểu thị tối đa thì bạn có thể làm việc theo công thức $\frac{1}{n} \sum_{i=1}^{k} a_i$ - đây là tùy chọn e):

Với dữ liệu của chúng tôi, nó có thể hoạt động, mặc dù nói chung, thuật toán tant rất nguy hiểm. Các bằng chứng ở đây chỉ được thực hiện một cách mẫu mực; bạn nên tự mình thực hiện chúng một cách chi tiết hơn (đối với những trường hợp đơn giản này, bạn có thể sử dụng tính năng này). Trong các trường hợp khác, bằng chứng bắt buộc $a$ hoặc $b$ có thể phức tạp.

Kiểm soát công việc

5.1. Cho một máy tính hoạt động trong hệ thống số $p$-ary có độ dài phần định trị là $n$ chữ số. Đối với nhiệm vụ 1, được phát triển ở trên, hãy xác định xem sự tương ứng nào giữa $a, b, h, p$ và $n$, có thể xây dựng một bảng bằng cách sử dụng vòng lặp while với mức tăng tuần tự $x$ theo số lượng $n$ để đảm bảo sự lặp lại chính xác của vòng lặp.

(Không có phần chuẩn bị bài toán cho bài học tiếp theo (cuối cùng)!)
L. F. Sternberg
