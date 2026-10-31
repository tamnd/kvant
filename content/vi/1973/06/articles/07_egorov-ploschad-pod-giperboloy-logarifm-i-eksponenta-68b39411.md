---
id: 1973-6-egorov-ploschad-pod-giperboloy-logarifm-i-eksponenta-68b39411
issue: kvant_1973_6
year: 1973
number: "6"
title: Diện tích dưới một hyperbol, logarit và số mũ
authors:
  - Егоров А. А.
rubric: matematicheskiy-kruzhok
rubric_sub: Математический кружок
page_first: 32
page_last: 40
page_labels: 30, 31, 32, 34, 36, 38
tag: HOPC
lang: vi
source: kvant_digital
extraction: vision
content_sha256: f459ad326d7fb598e731e1a7a429cc6ba264ac284b4b9cf6ec886bd71ba1266a
prompt_sha256: draft-1
translated_from: content/ru/1973/06/articles/07_egorov-ploschad-pod-giperboloy-logarifm-i-eksponenta-68b39411.md
source_content_sha256: 68280c9140ddf60c9fdcac91d25e8cc07632bfd85813ae1daaadb811489a7063
translation_model: draft
translation_run: vi-draft-2026-10-31
translation_quality: draft
---

⟦folio 30⟧

1. Giới thiệu.
Định nghĩa logarit

Hàm mũ $x \rightarrow a^x$ được nghiên cứu ở trường sau một số cách khái quát hóa hoạt động nâng lũy ​​thừa: đầu tiên, xác định bậc với số mũ tự nhiên, sau đó với số mũ hữu tỷ và cuối cùng là với số mũ vô tỷ. Logarit sau đó được định nghĩa là nghịch đảo của hàm số mũ.

Chúng ta sẽ làm đúng: chúng ta sẽ bắt đầu ngay với định nghĩa của logarit, sau đó chuyển sang hàm nghịch đảo - “số mũ”. Định nghĩa mà chúng tôi đang đưa ra giúp nghiên cứu các tính chất cơ bản của các hàm này và thu được các ước tính đặc biệt quan trọng đối với các ứng dụng vật lý, cũng như chứng minh một trong những phương pháp được sử dụng thường xuyên trong toán học để xây dựng các hàm mới bằng cách sử dụng các hàm đã biết.

Một hàm phổ biến như vậy sẽ được chúng ta gọi là hàm $x \rightarrow \frac{1}{x}$, đồ thị của $y = \frac{1}{x}$ là hyperbol quen thuộc.

Sự định nghĩa. Cho $b$ là một số dương. Chúng ta biểu thị bằng $\ln b$ số có mô hình bằng diện tích của hàm giới hạn bởi đồ thị của hàm $y = \frac{1}{x}$, trục hoành $y = 0$ và các đường thẳng $x = 1$ và $x = b$, và dấu phẳng nếu $b > 1$ (Hình 1, a) và trừ nếu $b < 1$ (Hình 1, b); nếu $b = 1$, thì $\ln b = 0$.

Hàm $b \rightarrow \ln b$ được gọi là logarit tự nhiên.

Chúng ta sớm thấy rằng $\ln b$ thực là logarit của số $b$ cơ số $e$, trong đó $e = 2,71828\dots$ là hằng số toán học thay thế, đã được thảo luận trong «Kvant» (xem bài viết của L. G. Limenov “Về số $e$ và $n$” ở số 5 năm 1972).

Đối với những người đã quen thuộc với tích phân dễ hiểu (ví dụ, theo bài viết của Yu. I. Ionin trong «Kvant» Số 9), định nghĩa của chúng ta về logarit có thể được hình thành như sau:

$$\ln b = \begin{cases} \int \frac{1}{x} dx, \text{ если } b > 1, \\ 0, \text{ если } b = 1, \\ -\int \frac{1}{x} dx, \text{ если } 0 < b < 1. \end{cases}$$

Đôi khi chúng tôi sẽ tham khảo các bài “Về số $e$” và “Tích phân”, nhưng chỉ để so sánh: người đọc không bắt buộc phải có kiến ​​thức trước về nó. Một độc giả muốn theo dõi tất cả các lập luận một cách chi tiết, chặt chẽ và giải quyết bài toán (và chúng chứa một phần quan trọng nội dung của bài viết) sẽ cần kiến ​​​​thức về các tính chất cơ bản của số thực *). Tuy nhiên, Sta-

*) Ví dụ, xem sách giáo khoa thử nghiệm của B. E. Weizza và I. T. Demidov “Đại số và sự khởi đầu của phân tích”, lớp 9, M., “Prosveshchenie”, 1969.

⟦folio 31⟧

Hình 1.
Nếu có thể, nó được viết theo cách có thể hiểu được các sự kiện cơ bản liên quan đến tính chất của logarit và số mũ, chỉ sử dụng những ý tưởng ngây thơ về số thực, tính liên tục, giới hạn, v.v. mà không đi sâu vào sự tinh tế liên quan đến các định nghĩa chặt chẽ của các khái niệm này.

2. Quảng trường
Một trong những khái niệm cần được xác định chặt chẽ là khái niệm diện tích. Thật vậy, cần phải giải thích ý nghĩa của chúng tôi về diện tích của “hình thang cong” (xem Hình 1). Xét cho cùng, ở trường chúng ta chỉ nói về diện tích của đa giác, hình tròn và các phần của nó, còn hình thang của chúng ta bị giới hạn một bên bởi một hyperbol.

Ở đây chúng ta sẽ tự giới hạn việc thay thế diện tích đó là một hàm, có thể được xác định trên một lớp hàm đủ rộng (lớp này bao gồm đa giác, và tất cả các hàm giới hạn lồi và “hình thang” của chúng ta) sao cho các điều kiện được thỏa mãn:

1) diện tích của bất kỳ hàm nào là số không âm;
2) diện tích của các hàm bằng nhau (đồng dạng) là bằng nhau;
3) nếu một hàm được cắt thành hai phần, với mỗi phần được xác định diện tích thì tổng các diện tích này bằng diện tích của tất cả các hàm;

Hình 2.
4) diện tích của hình chữ nhật ở các cạnh $a$ và $b$ bằng $ab$.

Chúng tôi sẽ không mô tả loại hàm mà hàm $S$ như vậy có thể được xác định, nhưng chúng tôi sẽ chứng minh rằng theo điều kiện 1–4 thì diện tích $S$ của “hình thang cong” $a \leq x \leq b$; $0 \leq y \leq \frac{1}{x}$ (Hình 2) được xác định duy nhất.

Để làm điều này, chúng ta chia đoạn $[a, b]$ thành $n$ các phần bằng nhau và xây dựng hai “cầu thang” - hàm bước bao gồm các hình chữ nhật có đáy $\frac{b-a}{n}$ trên trục $Ox$, một trong số đó chứa hình thang cong của chúng ta và cái còn lại nằm trong đó (Hình 2). Đặt $S'_n$ và $S''_n$ là diện tích của những “cầu thang” $^*$ này). Rõ ràng là $S'_n < S < S''_n$. Mặt khác, rõ ràng là

$$S''_n - S'_n = \frac{b-a}{n} (a^{-1} - b^{-1}),$$

nghĩa là, đối với $n$ đủ lớn, sự khác biệt giữa $S''_n$ và $S'_n$ có ​​thể được làm nhỏ tùy ý. Do đó, chỉ có một số $S$, nằm giữa $S'_n$ và $S''_n$ cho tất cả $n$ (điều này cũng dẫn đến việc cả hai chuỗi $S'_n$ và $S''_n$ đều tiếp cận $S$ khi $n$ tăng lên, tức là $S$ là giới hạn chung của chúng).

*) Chúng ta có thể xác định các diện tích này bằng điều kiện 3 và 4.

⟦folio 32⟧

3. Tính chất chính của logarit tự nhiên

Tính chất này được thể hiện bằng công thức

$$\ln x_1 x_2 = \ln x_1 + \ln x_2$$

(1)

(tại $x_1 > 0$ và $x_2 > 0$)

và có nghĩa là logarit tự nhiên của tích bằng tổng logarit tự nhiên của các thừa số.

Trước khi chứng minh công thức (1), chúng ta hãy thiết lập một tính chất quan trọng của hình thang cong cho hàm số $y = \frac{1}{x}$.

Chúng ta biểu thị bằng $S[A, B]$ diện tích của hình thang cong có các đỉnh $A, B$ (Hình 3). Khi đó, nếu $b > a > 0$ và $k$ là số dương tùy ý thì (Hình 4)

$$S[a, b] = S[ka, kb].$$

(2)

Để chứng minh điều này, chúng ta hãy xem xét một phép biến đổi của mặt phẳng bao gồm việc kéo dài theo hệ số $k$ từ trục $Oy$ và trượt theo hệ số $k$ sang trục $Ox$, tức là một phép biến đổi lấy điểm $(x, y)$ đến điểm $(kx, \frac{y}{k})$ (Hình 5). Dễ dàng nhận thấy đây là sự chuyển đổi bởi:

$$\int_a^b \frac{1}{x} \, dx = \int_k^a \frac{1}{x} \, dx.$$

⟦folio 34⟧

5. Nhà triển lãm

Có thể chứng minh rằng hàm chúng ta đã nghiên cứu ở các đoạn trước lấy toàn bộ các giá trị thực *). Trong trường hợp này, tất nhiên, mỗi giá trị được lấy chính xác một lần, nghĩa là đối với bất kỳ $x$ nào, phương trình $\ln y = x$ có một lời giải duy nhất. Đối với số $y$, là nghiệm của phương trình này, ký hiệu được chấp nhận

$$y = \exp x.$$

Hàm mới thu được $x \rightarrow \exp x$, nghịch đảo của hàm $x \rightarrow \ln x$, được gọi là hàm mũ.

Lưu ý rằng theo định nghĩa của số mũ đẳng thức

$$\exp (\ln x) = \ln (\exp x) = x.$$ (6)

Đồ thị $y = \exp x$ đối xứng với đồ thị $y = \ln x$ đối với đường thẳng $y = x$. Trên thực tế, vì $y = \exp x$ tương đương với $\ln y = x$ nên đồ thị của số mũ được lấy từ đồ thị logarit bằng cách biến đổi mặt phẳng, trong đó điểm $(x, y)$ tiến đến điểm $(y, x)$ và phép biến đổi này là đối xứng với đường thẳng $y = x$ (Hình 8**)).

*) Chúng tôi sẽ không chứng minh điều này, nhưng lưu ý rằng điều đó gần như hiển nhiên “từ các thông báo liên tục”. Một bằng chứng chặt chẽ về thực tế này có thể được thực hiện theo cách gần giống như bằng chứng về sự tồn tại của $\sqrt{a}$ với bất kỳ $a \geq 0$ nào.

**) Để kiểm chứng tính đúng đắn của hình này, bạn cần chứng minh rằng $\ln x < x$ với mọi $x > 0$.

Do đó, số mũ là hàm tăng dần được xác định trên toàn bộ trục số $-\infty < x < +\infty$ và nhận giá trị dương. Ngoài ra, số mũ có giá trị lớn hơn đáng kể khi $x$ tăng vô hạn và có xu hướng bằng 0 khi $x$ có ​​xu hướng $-\infty$.

6. Thuộc tính chính của số mũ

Tính chất này được thể hiện bằng công thức sau:

$$\exp \left( x_1 + x_2 \right) = \exp x_1 \cdot \exp x_2.$$ (7)

Để chứng minh điều đó, chúng ta sẽ sử dụng tính chất chính của logarit tự nhiên và sự tương ứng (6). Vì $\ln y_1 y_2 = \ln y_1 + \ln y_2$, nên với $y_1 = \exp x_1$ và $y_2 = \exp x_2$, chúng ta nhận được $\ln y_1 y_2 = x_1 + x_2$, tức là $y_1 \cdot y_2 = \exp \left( x_1 + x_2 \right)$ hoặc $\exp x_1 \cdot \exp x_2 = \exp \left( x_1 + x_2 \right)$.

Dễ dàng suy ra từ tính chất cơ bản của exp (hoặc từ tính chất tương ứng của hàm ln) rằng

$$\exp (-x) = \frac{1}{\exp x}$$

Và

$$\exp \left( x_1 + x_2 + \dots + x_n \right) = \exp x_1 \cdot \exp x_2 \dots \cdot \exp x_n).$$

Chúng ta hãy biểu thị số exp1 bằng $e$. Nói cách khác, $e$ là lời giải của phương trình $\ln e = 1$.

Sử dụng tính chất chính của hàm mũ, chúng ta chứng minh rằng với $x = \frac{m}{n}$ exp $x = e^x$ hữu tỉ.

Trước hết, với $m$ exp $m = \exp \left( 1 + 1 + \dots + 1 \right) = \exp 1 \cdot \exp 1 \cdot \dots \cdot \exp 1 = e^m$ và exp $(-m) = \frac{1}{\exp m} = \frac{1}{e^m} = e^{-m}$ tự nhiên.

Vậy exp $m = e^m$ với mọi số nguyên $m$.

Ngoài ra, với $n$ tự nhiên

$$\exp \left( \frac{1}{n} \right)^n = \exp \left( \frac{1}{n} + \frac{1}{n} + \dots + \frac{1}{n} \right) = \exp 1 = e,$$

⟦folio 36⟧

tiếp tuyến thực của góc nghiêng với trục Ox bằng (Hình 9)

$$\text{tg} \alpha = \frac{f(x_1) - f(x_0)}{x_1 - x_0}.$$

Khi điểm $x_1$ tiến đến $x_0$, cát tuyến có xu hướng về vị trí giới hạn của nó - tiếp tuyến được vẽ với đường cong $y = f(x)$ tại điểm $x_0$. Do đó, giá trị tùy ý tại $x = x_0$ bằng hệ số góc của tiếp tuyến với đồ thị tại điểm $(x_0, f(x_0))$.

Hãy thử tính tốc độ thay đổi “tức thời” của hàm $f(x) = \ln x$. Gia số của nó trên đoạn $[x_0, x_1]$ bằng

$$\ln x_1 - \ln x_0 = \ln \frac{x_1}{x_0} = \ln \left(1 + \frac{x_1 - x_0}{x_0}\right),$$

tư thế

$$\frac{\ln x_1 - \ln x_0}{x_1 - x_0} = \frac{1}{x_0} \cdot \frac{\ln(1 + h)}{h},$$

Ở đâu

$$h = \frac{x_1 - x_0}{x_0}.$$

Khi $x_1$ tiến tới $x_0$ thì số lượng $h$ tiến tới 0. Do đó, vẫn còn phải xem tỷ lệ $\frac{\ln(1 + h)}{h}$ ứng xử như thế nào đối với $h$ nhỏ.

Từ định nghĩa của chúng ta về logarit, như chúng ta sẽ sớm thấy, các ước tính có thể dễ dàng thu được từ đó nó suy ra rằng khi $h$ tiến đến 0, giá trị $\frac{\ln(1 + h)}{h}$ tiến đến 1, nghĩa là

$$\ln(1 + h) \approx h \text{ (при малых } h).$$

Công thức này rất quan trọng cho các phép tính gần đúng, cũng có thể được viết lại như sau:

$$\exp h \approx 1 + h \text{ (при малых } h).$$

Từ đây chúng ta rút ra các công thức cơ bản về tốc độ thay đổi của logarit và số mũ:

$$(\ln x)' = \frac{1}{x}$$

Và

$$(\exp x)' = \exp x.$$

9. Ước tính logarit tự nhiên của độ lớn của đơn vị

Đây là một trong những tính chất chính của logarit:

$$\left| x - \frac{x^2}{x+1} \right| = \left| \frac{x}{x+1} \right| < \left| \ln(1+x) \right| < |x|.$$

Để chứng minh các bất đẳng thức này cho $x > 0$, chỉ cần so sánh diện tích hình thang cong $ABCD$ với diện tích hai đường thẳng $AD'CB$ và $ADC'B$ (Hình 10). Thật vậy, diện tích hình thang cong bằng $\ln(1+x)$, diện tích $AD'CB$ bằng

⟦folio 38⟧

điều khoản

$$e^x = 1 + x + \frac{x^2}{1 \cdot 2} + \dots + \frac{x^k}{1 \cdot 2 \cdot \dots k} + \dots$$

(16)

giống như cấp số nhân vô hạn $1 + x + x^2 + \dots$ được biểu thị tại $|x| < 1$ bằng hàm $y = \frac{1}{1-x}$.

Cách trình bày này thuận tiện vì hai lý do. Thứ nhất, để tính số mũ với độ chính xác cao (ví dụ: khi biên soạn bảng) bằng công thức $e^x \approx 1 + x + \frac{x^2}{2!} + \dots + \frac{x^n}{n!}$, một số lượng thuật ngữ tương đối nhỏ là đủ và thứ hai, việc mở rộng này sẽ giúp bạn có thể nghiên cứu số mũ sâu hơn (ví dụ: để chứng minh tính vô tỷ của số $e$ (xem bài toán 11, 12).

Chúng ta sẽ giới hạn ở việc chứng minh công thức (16) cho $x > 0$.

Vì vậy hãy đặt $T_n(x) = \left(1 + \frac{x}{n}\right)^n$ và $S_n(x) = 1 + x + \frac{x^2}{1 \cdot 2} + \dots + \frac{x^n}{n!}$. Chúng ta phải chứng minh rằng

$$\lim S_n(x) = \exp x.$$

Sử dụng công thức nhị thức chúng ta nhận được

$$\left(1 + \frac{x}{n}\right)^n = 1 + n \cdot \frac{x}{n} + \frac{n(n-1)}{1 \cdot 2} \frac{x^2}{n^2} + \dots + \frac{x^n}{n!} = 1 + x + \frac{\left(1 - \frac{1}{n}\right) x^2}{1 \cdot 2} + \dots + \frac{\left(1 - \frac{1}{n}\right) x^k}{1 \cdot 2} + \dots + \frac{x^n}{n!}.$$

Các số ở vế phải của đẳng thức này trong ngoặc đều nhỏ hơn một. Nếu thay bằng đơn vị thì vế phải tăng
38
