---
id: 1976-4-bashmakov-chto-takoe-vektor-37eeb1b4
issue: kvant_1976_4
year: 1976
number: "4"
title: Vectơ là gì?
authors:
  - Башмаков М. И.
rubric: osnovnye-stati
page_first: 4
page_last: 6
page_labels: 2-4
tag: DR01
lang: vi
source: kvant_digital
extraction: vision
content_sha256: aefcdc40494c0036ecff4d2746b5d655341474d0bb52e2fe12c3606e0555520f
prompt_sha256: draft-1
translated_from: content/ru/1976/04/articles/02_bashmakov-chto-takoe-vektor-37eeb1b4.md
source_content_sha256: 929a841e83f7064a97d883c048cc729411d4d955747343b2d549b34e9025c980
translation_model: draft
translation_run: vi-draft-2026-10-31
translation_quality: draft
---

⟦folio 2⟧

Vectơ là gì?

Từ "vectơ" được tìm thấy trong toán học, vật lý và các ngành ứng dụng. Những từ này biểu thị các đối tượng hoàn toàn khác nhau và không giống nhau. Vì vậy, trong sách giáo khoa hình học ở trường, khái niệm vectơ được kết hợp với khái niệm vận chuyển song song (mặt phẳng hoặc không gian). Trong vật lý, khi mô tả một chuỗi đại lượng, người ta nói rằng chúng có tính chất vectơ - như tốc độ chuyển động cơ học, lực hấp dẫn, hướng của từ trường. Điểm chung nào cho phép tất cả các đối tượng này được gọi giống nhau? Bạn cần xây dựng một lý thuyết toán học như thế nào để có được một khái niệm phục vụ được nhu cầu của cả toán học và vật lý? Đây là những gì bài viết nói về.

1. Không gian vectơ

Toán học có một cách tuyệt vời để định nghĩa một khái niệm mới bằng cách mô tả các đặc tính của nó. Vì vậy, ví dụ, thay vì xác định trực tiếp số thực là gì (sử dụng phân số thập phân hoặc cách khác), hầu hết các cuốn sách đều liệt kê các thuộc tính cơ bản của chúng, những thuộc tính sẽ được sử dụng trong tương lai. Cách tiếp cận này - nó được gọi là tiên đề - rất phổ biến trong toán học hiện đại. Khóa học hình học ở trường được cấu trúc chính xác như thế này. Họ sẽ xây dựng tương tự với vectơ - chúng liệt kê các tính chất chung vốn có trong tất cả các đại lượng vectơ, được tìm thấy cả trong toán học và trong các ứng dụng của nó.

Như mọi khi với cách tiếp cận tiên đề, chúng ta sẽ định nghĩa không phải một “vectơ” cô lập, đơn lẻ là gì mà là tổng thể các vectơ cùng một lúc - một không gian vectơ.

Không gian vectơ là tập M có hai phép toán thỏa mãn một yêu cầu nhất định *). Tuy nhiên, các thao tác này (thường gọi là phép cộng) gán phần tử thứ ba cho mỗi cặp a, b của tập hợp M (phần tử này được gọi là tổng của các phần tử a và b và ký hiệu là a + b). Phép toán thứ hai gán cho mỗi phần tử a của tập M và mỗi số thực λ một phần tử của tập M gọi là tích của phần tử a và số λ (“tích” này được ký hiệu là λa).

Chúng ta hãy liệt kê các yêu cầu (các tiên đề không gian vectơ) mà các phép toán này phải đáp ứng:

1°. Phép cộng các vectơ tuân theo định luật tổ hợp (kết hợp) và giao hoán (giao hoán):
$$x + (y + z) = (x + y) + z;$$
$$x + y = y + x.$$

2°. Có một vectơ 0: 0, sao cho x + 0 = x.

3°. Với mỗi vectơ có một vectơ có tổng với vectơ gốc là vectơ 0.
$$4^\circ. (\lambda_1 \lambda_2)x = \lambda_1(\lambda_2x).$$
$$5^\circ. (\lambda_1 + \lambda_2)x = \lambda_1x + \lambda_2x.$$
$$6^\circ. \lambda(x + y) = \lambda x + \lambda y.$$
$$7^\circ. 1 \cdot x = x.$$

Ở đây x, y, z là các vectơ tùy ý, $\lambda, \lambda_1$ và $\lambda_2$ là bất kỳ số thực nào.

2. Ví dụ về vectơ không gian

Các vectơ quan trọng đối với chúng ta là các đoạn có hướng trên một mặt phẳng. Tuy nhiên, để sắp xếp một vector pro-
*) So sánh với định nghĩa về bình ở «Kvant», 1974, số 2, tr. 4.

⟦folio 3⟧

cuộc hành trình không hề dễ dàng chút nào. Vì vậy chúng ta sẽ bắt đầu với những ví dụ đơn giản hơn.

1. hàm tuyến tính
Hãy xem xét tất cả các hàm tuyến tính có thể có (cho tập R của tất cả các số thực). Mỗi hàm như vậy được cho bằng: $x \rightarrow ax + b$. Rõ ràng là tổng của hai hàm tuyến tính lại là hàm tuyến tính. Theo cách tương tự, nếu bạn nhân một hàm tuyến tính với một số, bạn sẽ nhận được một hàm tuyến tính lần nữa. Hơn nữa, tất cả các tiên đề $1^\circ - 7^\circ$ đều thỏa mãn và do đó, tập hợp các hàm tuyến tính với các phép toán này là một không gian vectơ.

2. Chuyển song song
Chúng ta hãy xem xét tập hợp tất cả các bản dịch song song của mặt phẳng. Chúng có thể được thêm vào, thực hiện tuần tự lần lượt, nhân với các số. Đây là không gian vectơ bạn gặp ở trường.

3. Không gian hàng
Hãy xem xét các chuỗi có độ dài cố định $n$ của số thực: $(a_1, a_2, \dots, a_n)$. Hãy xác định việc thêm các chuỗi và nhân chúng với các số theo từng phần tử:
$$(a_1, a_2, \dots, a_n) + (b_1, b_2, \dots, b_n) = (a_1 + b_1, a_2 + b_2, \dots, a_n + b_n);$$
$\lambda (a_1, a_2, \dots, a_n) = (\lambda a_1, \lambda a_2, \dots, \lambda a_n)$. Rõ ràng, các chuỗi có độ dài $n$ với các phép toán xác định như vậy sẽ tạo thành một không gian vectơ.

4. Bộ ba hình vuông
Tập hợp các bộ ba hình vuông $\{ax^2 + bx + c\}$ (các số $a, b, c$ cũng có thể là số 0) cũng tạo thành một không gian vectơ đối với các phép toán tổng quát là cộng các đa thức và nhân chúng với các số.

5. Đa thức
Tập hợp tất cả các đa thức có cùng phép tính cũng tạo thành một không gian vectơ.

6. Chức năng
Tất cả các hàm được xác định trên một tập số A nào đó tạo thành một không gian vectơ đối với các phép toán tổng quát của A, được hình thành đầu tiên trên số B (tức là một đoạn có hướng thuộc lớp thứ hai được đặt ra khỏi B) và nếu điểm C là điểm cuối của đoạn thứ hai thì AC là đoạn có hướng thuộc lớp tương ứng với tổng các vectơ. Chúng ta phải chứng minh một cách độc lập rằng định nghĩa về tổng này là đúng, tức là kết quả không phụ thuộc vào phân đoạn có hướng nào từ lớp đầu tiên mà chúng ta chọn. Đưa ra định nghĩa bằng hình ảnh về phép nhân với một số. (Xử lý các vectơ tự do rất khó vì

⟦folio 4⟧

rằng mỗi trong số chúng đại diện cho toàn bộ lớp các phân đoạn được định hướng. Về mặt đồ họa, chúng tôi luôn mô tả mỗi lớp bằng một phân đoạn mà chúng tôi có thể chọn theo ý mình. Vì vậy, chúng ta phải kiểm tra xem kết quả có phụ thuộc vào các đại diện tùy ý mà chúng ta chọn hay không.

3. tọa độ

Hãy quay lại ví dụ đầu tiên của chúng ta - không gian vectơ của các hàm tuyến tính.

Hãy xem xét hai chức năng:
$$f_1: x \rightarrow x,$$
$$f_2: x \rightarrow 1.$$

Bất kỳ hàm $f: x \rightarrow ax+b$ nào cũng có thể được biểu diễn dưới dạng kết hợp tuyến tính của các hàm sau: $f=af_1+bf_2$. Cặp số $(a, b)$ được gọi là tọa độ của hàm tuyến tính $f$.

Điều đáng chú ý là khi cộng các hàm tuyến tính, tọa độ của chúng cộng lại như những đường thẳng:
$$f_1: x \rightarrow ax+b \leftrightarrow (a, b),$$
$$f_2: x \rightarrow cx+d \leftrightarrow (c, d),$$
$$f_1+f_2: x \rightarrow (a+c)x+(b+d) \leftrightarrow (a+c,b+d);$$
Nhưng
$$(a+c,b+d)=(a,b)+(c,d).$$

Hãy đưa ra một vài ví dụ nữa. Trong không gian vectơ của các bản dịch song song của một mặt phẳng, bạn có thể chọn hai bản dịch song song (ví dụ: thành hai vectơ không song song có độ dài 1), trong đó bất kỳ bản dịch nào được phân tách; các hệ số của sự khai triển này được gọi là tọa độ của phép truyền tương ứng.

Xét trong không gian vectơ của các dây có độ dài $n=4$
$$f_1=(1,0,0,0), f_2=(0,1,0,0),$$
$$f_3=(0,0,1,0), f_4=(0,0,0,1).$$

Chúng ta có thể biểu diễn bất kỳ chuỗi $f=(a_1,a_2,a_3,a_4)$ nào dưới dạng
$$f=a_1f_1+a_2f_2+a_3f_3+a_4b_4;$$
các số $(a_1,a_2,a_3,a_4)$ được gọi là tọa độ của hàng $f$.

Trong không gian vectơ của tam thức vuông, với tam thức tùy ý $f=ax^2+bx+c$ ta có:
$$f=af_1+bf_2+cf_3,$$
$$f_1=x, f_2=x^2, \dots, f_n=x^n, \dots.$$

Khi đó đa thức $F$ bất kỳ có thể được viết dưới dạng tổ hợp tuyến tính hữu hạn của các đa thức đã chọn; các hệ số khai triển của đa thức $F$ thành đa thức $f_0, f_1, \dots$ là tọa độ của nó:
$$F(x)=a_mx^m+a_{m-1}x^{m-1}+...$$
$$...+a_1x+a_0=a_mf_m+a_{m-1}f_{m-1}+...$$
$$...+a_1f_1+a_0f_0 \leftrightarrow (a_m,a_{m-1},...,a_1,a_0).$$

Bây giờ chúng ta có thể hỏi một số câu hỏi. Làm cách nào để chọn một hệ vectơ trong một không gian nhất định mà bất kỳ vectơ nào của không gian này có thể bị phân tách? Khi nào những hệ thống này có thể được chọn làm hệ thống cuối cùng? Sự phân hủy này độc đáo đến mức độ nào? Và các hệ số khai triển có liên quan như thế nào với các hệ vectơ khác nhau?

Đáp số những câu hỏi này được trả lời bởi nhánh toán học được gọi là đại số tuyến tính. Dưới đây là một cái nhìn nhanh về một số kết quả.

1. Không gian vectơ nghịch đảo là hữu hạn chiều và vô hạn chiều. Trong các hệ hữu hạn chiều, có các hệ vectơ hữu hạn mà bất kỳ vectơ nào trong không gian đều có thể được khai triển. Trong các ví dụ của chúng tôi, không gian của các hàm tuyến tính, tam thức bậc hai, chuỗi, các phép tịnh tiến song song và vectơ tự do là hữu hạn chiều. Không gian của mọi đa thức và mọi hàm số đều là vô hạn chiều.

2. Đối với không gian hữu hạn chiều, chúng ta có thể chỉ định số $n$ nhỏ nhất sao cho có vectơ $n$ mà bất kỳ vectơ nào trong không gian đều có thể được mở rộng. Con số $n$ này được gọi là chiều của không gian. Như vậy, không gian hàm số tuyến tính có chiều 2, không gian tam thức bình phương
