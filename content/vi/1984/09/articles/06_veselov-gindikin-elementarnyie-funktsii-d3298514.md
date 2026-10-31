---
id: 1984-9-veselov-gindikin-elementarnyie-funktsii-d3298514
issue: kvant_1984_9
year: 1984
number: "9"
title: Các hàm cơ bản
authors:
  - Веселов А. П.
  - Гиндикин С. Г.
rubric: osnovnye-stati
page_first: 11
page_last: 16
page_labels: 9-14
tag: IBOE
lang: vi
source: kvant_digital
extraction: vision
content_sha256: fb8904998179342b48381f488ac5b171df84f4c561b3385d5e6bc1263af5fa20
prompt_sha256: draft-1
translated_from: content/ru/1984/09/articles/06_veselov-gindikin-elementarnyie-funktsii-d3298514.md
source_content_sha256: 8443342b29d47c77a876f1fc39c7478567459e98aeefb1ef95d869932bb68629
translation_model: draft
translation_run: vi-draft-2026-10-31
translation_quality: draft
---

⟦folio 9⟧

Các hàm cơ bản

Ứng viên Khoa học Vật lý và Toán học
A. P. VESELOV
Ứng viên Khoa học Vật lý và Toán học
S. G. GINDIKIN

Bài viết này đề cập đến các hàm mũ, logarit và trionometric. Các hàm này thuộc loại hàm cơ bản (cũng bao gồm hàm tuyến tính $y=ax+b$, hàm lũy thừa $y=x^n$, cũng như tất cả các kết hợp có thể có của các hàm được liệt kê - tổng, hiệu, tích, thương và thành phần). Những hàm này được gọi như vậy vì chúng là những hàm đầu tiên được nghiên cứu trong toán học, và trong một thời gian dài các nhà toán học cơ bản đã không vượt quá những hàm này.

Chúng ta sẽ xem xét hai cách tiếp cận chính để xác định các hàm số mũ, logarit và lượng giác: tiên đề và động học, đảm bảo rằng các phương pháp này dẫn đến các hàm giống nhau và thảo luận về mối quan hệ của chúng với các định nghĩa kinol.

Định nghĩa tiên đề của hàm số mũ

Hàm mũ $a^x$ là hàm $y=f(x)$ sao cho các điều kiện sau được thỏa mãn:

1) $f$ được xác định cho tất cả $x$;

2) $f(1)=a>0$ ($a\neq 1$);

3) với mọi $x$, $y$ thì sự tương ứng được thỏa mãn

$$f(x+y)=f(x)f(y);$$

4) $f(x)$ là hàm đơn điệu.

Lý thuyết trường phái về hàm số mũ bao gồm việc xây dựng một hàm thỏa mãn bốn tính chất được liệt kê; điều quan trọng là chỉ có một hàm có những đặc tính này. Ngược lại, ở trường người ta chỉ chứng minh được rằng 2), 3) xác định $f$ duy nhất cho hợp lý $x$; tuyên bố về sự tiếp tục duy nhất cho tất cả $x$ từ hữu tỉ $x$ theo điều kiện 4) được đưa ra mà không có bằng chứng (bằng chứng có thể được tìm thấy trong bài viết của R.K. Gorder “Mức độ là gì”, Kvant, 1981, số 2).

Những định nghĩa như vậy về một đối tượng bằng cách liệt kê các thuộc tính đặc trưng của nó được gọi là tiên đề. Cần phải hiểu rằng định nghĩa tiên đề của hàm mũ về cơ bản không khác gì định nghĩa của trường phái. Mối quan hệ (2) được gọi là phương trình hàm của hàm số mũ. Các phương trình hàm liên hệ các giá trị của hàm tại các điểm khác nhau và lời giải của chúng được gọi là các hàm tương ứng với các điểm này. Trong trường hợp này, các hàm số mũ là nghiệm của phương trình hàm (2) (và nếu các hạn chế bổ sung nêu trên được đáp ứng thì không có lời giải nào khác).

Bài toán 1. Chứng minh rằng trong trường hợp lời giải (2), định nghĩa cho tất cả $x$ là hoặc

⟦folio 10⟧

số 0 giống hệt nhau hoặc hàm dương ở mọi nơi (và do đó, hàm số mũ được xác định ở mọi nơi chỉ tồn tại đối với các cơ số không âm $a$).

Cách tiếp cận tiên đề thú vị ngày nay để xác định hàm số mũ không xuất hiện ngay lập tức. Điều đáng chú ý là hàm số mũ xuất hiện lần đầu tiên dưới dạng lời giải của một phương trình vi phân. Câu chuyện này đáng được ghi nhớ.

Định nghĩa động học của hàm số mũ

Vào đầu thế kỷ 17, Galileo (1564-1642) muốn khám phá định luật xảy ra sự rơi tự do. Ông hy vọng có thể khám phá quy luật này một cách thuần túy bằng suy đoán, chỉ được hướng dẫn bởi những thông điệp về sự đơn giản. Do đó, ông cho rằng sự rơi tự do tỷ lệ thuận với quãng đường di chuyển:

$$\dot{s} = \lambda s.$$

(3)

Theo thông điệp vật lý $\lambda > 0$ (chuyển động được tăng tốc) và $s(0) = 0$ (tại thời điểm ban đầu cơ thể sẽ tích lũy). Sau một thời gian, Galileo vô cùng ngạc nhiên phát hiện ra rằng phương trình vi phân (3) không thể có lời giải với $s(0) = 0$ khác với $s \equiv 0$ (một chuyển động không thể có với các tính chất mà Galileo ban đầu cho là rơi tự do).

Bài toán 2. Chứng minh nhận định của Galileo. Gợi ý. Hãy để $\lambda > 0$; sau đó tốc độ $\dot{s}$ trở lại với mức tăng $s$. Nếu tại một thời điểm nào đó $t_0$ chúng ta có: $s(t_0) = c > 0$, thì $\dot{s}(t_0) = \lambda c$; $\dot{s}(t) < \lambda c$ với $t < t_0$, có nghĩa là $t_0 > 1/\lambda$ bất kể $c!$. Từ đây dễ dàng suy ra rằng $s \equiv 0$.

Quan sát này đã thúc đẩy Galileo thay đổi định luật được cho là thành $\dot{s} = gt$, dẫn đến việc ông phát hiện ra định luật rơi tự do và ông không còn quan tâm đến chuyển động theo định luật nữa (3). Bạn có thể đọc thêm về điều này trong cuốn sách “Những câu chuyện về Vật lý và Toán học” của S. G. Gindikin (M., “Nuka”, 1981).

Chúng ta phải nhớ đến một nhà toán học đáng chú ý khác - John Napier, Nam tước Merchiston (1550-1617), người gần như cùng năm với Galileo, đã nghiên cứu chuyển động theo định luật (3) bằng các phương pháp khác nhau. Nếu Galileo tìm cách đạt được một mô tả toán học về một hiện tượng cơ học thực sự, thì Napier lại đi theo hướng hoàn toàn ngược lại: ông muốn đưa ra một cách giải thích cơ học cho các thủ tục toán học thuần túy. Ngay cả trước Napier, các nhà toán học đã cố gắng tận dụng mối liên hệ giữa cấp số biện luận và cấp số nhân để đơn giản hóa các phép tính (thay thế phép nhân bằng phép cộng!). Để tăng độ chính xác, cần phải có các cấp số “thường xuyên” hơn, và cái nhìn sâu sắc của Napier là điều này nên được đưa đến cùng và thay thế các cấp số rời rạc bằng các giá trị - hàm liên tục. Vì mục đích này, xem xét chuyển động tưởng tượng theo định luật (3) và giải thích thời gian như một sự tương tự liên tục của một tiến trình tranh luận, Napier thuyết phục rằng vậy thì hãy coi nó là một sự tương tự của một tiến trình hình học. Cụ thể, nếu thời gian $t$ tăng lên $k$ đơn vị thì hãy nhân nó với $q^k$ đối với một số $q$; nếu chúng ta chuyển sang những đơn vị thời gian nhỏ hơn, thì như trước đây, sự dịch chuyển thời gian $t$ tương ứng với các phép biến đổi theo quy luật cấp số nhân.

Sự khác biệt chính giữa cách tiếp cận của Napier và cách tiếp cận của Galileo là nó loại bỏ ràng buộc $s(0) = 0$. Hãy để $\lambda$ được cố định. Một tính chất quan trọng của chuyển động (3) được rút ra từ phát biểu của Galileo. Chuyển động theo định luật (3) đối với $\lambda$ cố định hoàn toàn được xác định bởi giá trị của $s$ tại bất kỳ thời điểm cố định nào $t_0$. Thật vậy, nếu $s_1(t), s_2(t)$ là hai chuyển động với $s_1(t_0) = s_2(t_0)$, thì đối với $s(t) = s_1(t) - s_2(t)$, cũng là nghiệm của (3), chúng ta có: $s(t_0) = 0$, tức là $s \equiv 0$; theo định lý Galileo và $s_1(t) = s_2(t)$. Hơn nữa, nếu $s$ là lời giải (3), thì $s_1(t + t_0)$ cũng là lời giải, có nghĩa là tất cả lời giải (3) chỉ được phân biệt bằng một thừa số không đổi. Ngoài ra, nếu $s$ là lời giải thì $s_1(t) = s(t + t_0)$ cũng là lời giải (đối với $t_0$ cố định).

Giả sử $S_\lambda(t)$ là lời giải (3) sao cho $S_\lambda(0) = 1$. Hãy lấy $s_1(t) = S_\lambda(t + t_0)$, $s_2(t) = S_\lambda(t) S_\lambda(t_0)$. Cả hai hàm này sẽ là nghiệm của (3), lấy cùng giá trị $S_\lambda(t_0)$ tại $t = 0$ và sau đó phải trùng nhau. Chúng tôi hiểu điều đó

⟦folio 11⟧

$$S_{\lambda}(t+t_0) = S_{\lambda}(t) S_{\lambda}(t_0).$$

Hơn nữa, hàm $S_{\lambda}$ khả vi, nghĩa là nó liên tục. Theo định lý Halley, nó không biến mất ở đâu cả, nghĩa là nó có cùng dấu ở mọi nơi, tức là $S_{\lambda}(t) > 0$ ($S_{\lambda}(0) = 1$). Theo (3), thì $S_{\lambda}(t)$ có cùng dấu ở mọi nơi với $\lambda$, tức là nó tăng ở $\lambda > 0$, tiêu diệt ở $\lambda < 0$.

Vì vậy, lời giải của phương trình (3) với $s(0) = 1$ nhất thiết phải là hàm số mũ. Nếu bây giờ chúng ta vi phân (4) theo $t_0$ và đặt $t_0 = 0$, chúng ta nhận được

$$S_{\lambda}(t) = S_{\lambda}(t) S_{\lambda}(0).$$

Điều này có nghĩa là hàm số mũ (giả sử rằng nó khả vi) là nghiệm của (3), $\lambda = S_{\lambda}(0)$. Tính khả vi của hàm số mũ được chứng minh trực tiếp (xem “Đại số và sự khởi đầu của phân tích 9-10”, đoạn 65).

Còn một vấn đề nữa cần phải bàn. Chúng tôi đã kiểm tra lời giải (3) với giả định rằng chúng tồn tại. Giả định này xuất phát từ một thực tế chung về phương trình vi phân mà chúng tôi sẽ không chứng minh ở đây*). Nếu chúng ta chấp nhận nó, thì chúng ta thu được sự tồn tại hàm mũ của hàm số mũ, khác với hàm số đã nhận ra ở trên. Mặt khác, khả năng giải được phương trình (3) xuất phát từ sự tồn tại và tính khả vi của hàm số mũ.

Số $e$ (không phải số đầu tiên)

Bây giờ chúng ta có hai cách tiếp cận để xác định hàm số mũ. Với định nghĩa tiên đề, các hàm số mũ được phân biệt một cách tự nhiên bởi cơ số $f(1) = a$ của chúng. Nếu chúng ta tiến hành từ phương trình (3), thì phương trình tự nhiên hơn dựa trên hệ số $\lambda$. Các CONSTANT này có liên quan như thế nào?

Trước hết, sử dụng phương pháp động học tự nhiên chọn hàm mũ tương ứng với $\lambda = 1$. Cơ số của nó thường được ký hiệu là $e$ và được gọi là số không nguyên tố, và bản thân hàm này đôi khi được ký hiệu là expr $t$ (sau phần đầu của từ “số mũ”). Vì vậy, đối với một chuyển động xảy ra theo quy luật $\dot{s} = s$, mà $s(0) = 1$, chúng ta có: $s(t) = e^{\dot{s}}$ ($= \exp t$).

Hãy cùng khám phá con số $e$. Đây là khoảng cách tính từ điểm bắt đầu mà điểm xuất hiện tại thời điểm $t = 1$. Vì chuyển động xảy ra với tốc độ lớn hơn 1 và chuyển động bắt đầu ở khoảng cách 1 so với lúc đầu, nên chúng ta thu được rằng ở $t = 1$ khoảng cách là $e > 1 + 1 = 2$. Mặt khác, hãy chứng minh rằng $e < 3$ (điểm sẽ không có thời gian để vượt quá điểm 3). Để làm điều này, chúng ta sẽ chia nó từ 1 đến 3 thành 8 phần bằng nhau (độ dài của một phần là 1/4). Điểm sẽ đi qua đoạn đầu tiên với tốc độ không vượt quá giá trị của nó ở đầu bên phải của đoạn, trong đó, theo (3), nó bằng 5/4; do đó, thời gian cần thiết cho phân đoạn này ít nhất là 1/5. Tương tự, đoạn thứ hai sẽ mất ít nhất 1/6, đoạn thứ ba - ít nhất là 1/7, v.v. Tổng thời gian trên đường đi từ 1 đến 3 không nhỏ hơn $\frac{1}{5} + \frac{1}{6} + \frac{1}{7} + \frac{1}{8} + \frac{1}{9} + \frac{1}{10} + \frac{1}{11} + \frac{1}{12}$ và tổng này lớn hơn 1. Điều này có nghĩa là điểm $e$ nằm gần 3.

Nếu bây giờ chúng ta chia đoạn thời gian $[0, 1]$ thành $n$ các phần bằng nhau thì trong đoạn thời gian đầu tiên tốc độ lớn hơn 1, điểm sẽ di chuyển $\Delta t = 1/n$ một quãng đường dài hơn $1/n$ và hóa ra là xa hơn so với lúc đầu so với $1+1/n$ với tốc độ vượt quá đoạn $\Delta = 1/n$ nó sẽ đi một đường lớn hơn $(1+1/n)/n$ và điểm quay đầu ra ở khoảng cách lớn hơn $(1+1/n)^2$ so với lúc ban đầu với tốc độ lớn hơn $(1+1/n)^2$, v.v., tại thời điểm $t = 1$ - ở khoảng cách $(1+1/n)^n$ so với lúc bắt đầu.

Từ lý do này, có vẻ đúng khi $n$ tăng thì giá trị $a_n = (1+1/n)^n$ cũng tăng (chứng minh rằng điều này đúng!) và có xu hướng $e$. Trong sách giáo khoa “Đại số và sự khởi đầu của phân tích 9-10” (§22, đoạn 113), ông chứng minh rằng

$$e = \lim_{n \to \infty} \left(1 + \frac{1}{n}\right)^n,$$

đặc biệt, từ đó, $e$ có thể được xác định với bất kỳ độ chính xác nào. Hãy nhớ lại điều đó $e = 2,718281828459045\dots$. Tương tự, người ta chứng minh rằng

$$e' = \lim_{n \to \infty} \left(1 + \frac{t}{n}\right)^n.$$

Hãy xem xét cách giải thích động học của đẳng thức này.

Bài toán 3. Chứng minh động học của bất đẳng thức

⟦folio 12⟧

$$e < \left(1 + \frac{1}{n}\right)^{n+1}.$$

Gợi ý. Chia đoạn đường dẫn $[1, \left(1 + \frac{1}{n}\right)^{n+1}]$ thành các đoạn $(n+1)$ có ​​dạng $[\left(1 + \frac{1}{n}\right)^{k-1}, \left(1 + \frac{1}{n}\right)^k]$. Sau đó, khi di chuyển dọc theo đoạn $k$-thứ độ dài $\frac{1}{n+1}\left(1 + \frac{1}{n}\right)^k$, theo định luật $\dot{s} = s$, tốc độ không vượt quá $\left(1 + \frac{1}{n}\right)^k$ và thời gian sử dụng tương ứng lớn hơn $1/n+1$, tức là tổng thời gian lớn hơn 1.

Hãy quay lại câu hỏi bắt đầu cuộc trò chuyện của chúng ta về số $e$. Hãy để $S_\lambda(t) = a^t$. $\lambda$ và $a$ có liên quan như thế nào? Lưu ý rằng nếu $s(t)$ - lời giải (3) đối với một số $\lambda$, thì $s(ct)$ - lời giải (3) với $\lambda' = c\lambda$ và cùng giá trị bằng 0, tức là $S_{\lambda c}(t) = S(ct)$, từ đó $S_\lambda(t) = a^t$, trong đó $a = e^\lambda$.

Do đó, mối liên hệ giữa $a$ và $\lambda$ được thể hiện rất đơn giản thông qua một số phi hạt nhân.

Chúng ta hãy tóm tắt việc xem xét phương trình (3). Chúng ta đã chứng minh rằng tổng quát lời giải của phương trình này có dạng $s(t) = s_0 \exp(\lambda t), s_0 = s(0)$.

Phương trình (3) được gọi là phương trình tăng trưởng theo cấp số nhân (hoặc theo cấp số nhân) (hoặc giảm ở $\lambda < 0$). Nó mô tả nhiều quá trình được tìm thấy trong tự nhiên: phân rã phóng xạ, thay đổi nhiệt độ theo thời gian và áp suất theo độ cao, quy luật phát triển sinh học và xã hội và các quá trình khác. Đặc điểm quan trọng nhất của hàm mũ, thể hiện ở hiện tượng mà nó mô tả, là sự tăng trưởng nhanh chóng của nó (tại $\lambda > 0$). Cụ thể, mức tăng trưởng theo cấp số nhân (tại $\lambda > 0$) vượt quá bất kỳ mức tăng trưởng nào và mức giảm theo cấp số nhân (tại $\lambda < 0$) vượt quá mức độ giảm, cụ thể là

$$\lim_{t \to +\infty} \frac{t^k}{\varepsilon^{\lambda t}} = 0 \quad (\lambda > 0), \quad \lim_{t \to +\infty} e^{\lambda t} t^k = 0 \quad (\lambda < 0)$$

(“Đại số và phần đầu của phân tích 9-10”, § 22, đoạn 117).

Hàm logarit $\log_a x$, $a > 0, a \neq 1$

Hàm này được định nghĩa là nghịch đảo của hàm mũ $a^x$, $a \neq 1$ và tất cả các thuộc tính của nó tuân theo trực tiếp từ định nghĩa này.

Nó được xác định ở $x > 0$, phạm vi của nó là toàn bộ dòng, $\log_a x$ tăng ở $a > 1$ và giảm ở $a < 1$, $\log_a 1 = 0$, nhưng quan trọng nhất là nó có một phương trình hàm (được gọi là “tính chất cơ bản của logarit” trong trường học)

$$\log_a xy = \log_a x + \log_a y,$$

(7) suy ra trực tiếp từ phương trình hàm số của hàm số mũ (1) (tại sao?). Hàm logarit cũng có thể được mô tả dưới dạng hàm danh nghĩa: $\log_a x$ là hàm đơn điệu bằng 1 với $x = a$, thỏa mãn (7) và xác định cho tất cả $x > 0$ (chứng minh!). Lưu ý rằng khi chuyển qua hàm logarit, về cơ bản chúng ta sử dụng tính đơn điệu nghiêm ngặt của $a^x$ cho $a \neq 1$ (điều này đảm bảo sự tồn tại của hàm nghịch đảo); vì lý do này, $a = 1$ bị loại trừ.

Logarit tự nhiên $\ln x$ được định nghĩa là nghịch đảo của $e^x$, tức là thời gian để một điểm di chuyển theo $\dot{s} = s$ đi từ 1 đến $x$.

Có thể nói rằng chính hàm logarit chứ không phải hàm mũ mới là mục tiêu của Napier. Tuy nhiên, bức tranh anh xây dựng có phần phức tạp. Anh ấy nhìn vào phương trình (3) với $\lambda = 10^{-7}$ và lấy nó lời giải với $s(0) = 10^7$, tức là $s(t) = 10^7 \exp(10^{-7} t)$; Theo đó, hàm nghịch đảo - logarit Neper - có dạng $t = \text{Ner} \log x = 10^7 \ln 10 + 10^7 \ln x$, và đối với nó thì $t(x \cdot y) = t(x)t(y)$, $t(1) = 0$ là không đúng. Vào cuối hai mươi năm biên soạn bảng logarit, Napier chắc chắn cảm thấy không hài lòng với hệ thống mà ông đã áp dụng. Anh ta đã có ý tưởng về logarit thập phân, nhưng không đủ sức để thực hiện các phép tính trực tiếp.

⟦folio 13⟧

gốc Các bảng tương ứng được biên soạn theo chiều dọc bởi nhà toán học Henry Briggs, người có cơ hội thảo luận về ý tưởng logarit thập phân với Napier trong những năm cuối đời. Logarit thập phân đôi khi vẫn được gọi là logarit Brissian (cuốn sách “Số học logarit” của Briggs, xuất bản năm 1624, được dành riêng cho chúng). Logarit tự nhiên xuất hiện vào năm 1619 trong cuốn sách của giáo viên dạy toán quy mô nhỏ Speidel (một bảng nhỏ ẩn danh xuất hiện một năm trước đó trong phần phụ lục của ấn bản thứ hai cuốn sách của Napier).

Từ định nghĩa động học của logarit theo quy tắc đạo hàm hàm nghịch đảo ta thu được

$$\left( \ln x \right)' = \frac{1}{x}.$$

Hơn nữa, mối liên hệ ở trên giữa λ và cơ sở lời giải $S_\lambda(t)$ có nghĩa là $(a^t)' = \ln a \cdot a^t$, từ đó

$$\log_a x)' = \frac{1}{x \ln a}.$$

Bài toán 4. Tìm trung bình cộng lớn nhất của các số có dạng $\sqrt[n]{n}$ (n là số tự nhiên).
Gợi ý. Xét cực trị của hàm số

$$f(x) = x^{\frac{1}{x}} = \exp \left( \frac{\ln x}{x} \right)$$

hoặc tương đương, $g(x) = \ln x/x$.

Hàm $\ln x$ thuận tiện cho việc tính toán các chỉ số khác nhau của các quá trình được mô tả bằng phương trình (3). Do đó, nếu chúng ta lấy thời gian $\tau$, trong thời gian đó giá trị giảm (hoặc giảm một nửa), làm đặc tính của sự tăng trưởng (giảm), thì vì $e^{\lambda \tau} = 2$, chúng ta thu được $\tau = \frac{\ln 2}{\lambda}$ cho $\lambda > 0$

và $\tau = -\frac{\ln 2}{\lambda}$ tại $\lambda < 0$. Trong trường hợp phân rã phóng xạ, $\tau$ được gọi là chu kỳ bán rã ($\lambda < 0$).

Bài toán 5. Tiền gửi có kỳ hạn trong ngân hàng tiết kiệm tăng 3% mỗi năm. Trong bao nhiêu năm nó sẽ tăng gấp đôi?

Cuối cùng, chúng tôi lưu ý rằng do số mũ của hàm tăng rất nhanh nên hàm logarit, theo hướng, tăng cực kỳ chậm. Nó phát triển chậm hơn bất kỳ sức mạnh tích cực nào $x$:

$$\lim_{x \to +\infty} \frac{\ln x}{x^a} = 0, \quad a > 0.$$

Hàm tam giác

Cả hai đường dẫn chúng ta đã thảo luận liên quan đến hàm số mũ (hoạt động)

Đồ thị của một số hàm lượng giác.

mô phỏng và động học) cũng có sẵn cho các hàm lượng giác. Tuy nhiên, không phải ai trong số họ là nguồn đầu tiên. Cách đầu tiên là xác định các hàm lượng giác thông qua tỉ số các cạnh trong một tam giác hoặc đường tròn lượng giác. Đúng, trong trường hợp này, các hàm phát sinh lấy các giá trị số, trong khi đối số của chúng lấy các giá trị góc chứ không phải số. Để chuyển sang các hàm đối số số, bạn cần học cách thay đổi góc. Phải nói rằng mặc dù lượng giác đã phát triển từ thế kỷ thứ 2 trước Công nguyên. e., và nó có tầm quan trọng lớn liên quan đến các phép tính thiên văn, định nghĩa hiện tại về hàm lượng giác chỉ xuất hiện vào thế kỷ 18 (phần lớn là từ Euler). Trước đó, chúng tôi đã thực hiện với tất cả các loại bảng, chẳng hạn như các hợp âm tương ứng với các góc. Không được quên rằng trong một thời gian dài, đối với hầu hết các nhà toán học, các hàm số không vượt quá các hàm đại số và họ không hề nghĩ rằng phép lượng giác bằng cách nào đó có mối liên hệ với phép giải tích.

Chúng ta hãy tập trung vào định nghĩa động học của hàm lượng giác. Hãy xem xét một trong những định luật đơn giản nhất: gia tốc (hoặc lực) tỷ lệ thuận với khoảng cách, hoặc

$$\ddot{x} + \omega^2 x = 0.$$

Phương trình này được gọi là phương trình dao động điều hòa (nó mô tả chuyển động của quả bóng ở bên ngoài, sự dao động của con lắc quanh vị trí cân bằng, v.v.). Trước tiên chúng ta hãy giới hạn bản thân ở tia $\omega = 1$

$$\ddot{x} + x = 0.$$

Chúng ta biết rằng nghiệm của phương trình này là $\sin t$ và $\cos t$, nhưng hãy cố gắng tìm ra định nghĩa độc lập của chúng

⟦folio 14⟧

Lênin. Trước hết, chúng ta cần thu được một dạng tương tự của định lý Galileo cho (3)—định lý duy nhất. Chúng ta phải chứng minh rằng lời giải (9) duy nhất có $x(0)=\dot{x}(0)=0$ là $x=0$. Xin lưu ý rằng chúng tôi nhận được bài toán hai điều kiện cho $t=0$, đó là do thực tế là (9) bao gồm điều kiện tùy ý thứ hai. Chứng minh được rút ra từ việc bảo toàn giá trị $E=\frac{1}{2}(\dot{x}^2+x^2)$ (kiểm tra xem $\dot{E}=0$ bằng phương trình (9)).

Ta ký hiệu $s(t)$ lời giải (9) với $s(0)=0$, $\dot{s}(0)=1$. Hãy cùng khám phá các tính chất của lời giải này (thực tế giống với sin $t$, nhưng chúng tôi muốn rút ra tất cả các tính chất từ ​​phương trình (9)).

1) Để $c(t)=\dot{s}(t)$; sau đó $c(t)$ — lời giải (9) với các điều kiện ban đầu $c(0)=1$, $\dot{s}(0)=0$ (được kiểm tra bằng vi phân không biểu diễn: $\ddot{c}=\dot{s}=-\dot{s}=-c$, $\dot{c}=-s$).

2) $s(t)=-s(-t)$, $c(t)=c(-t)$ (chỉ cần kiểm tra xem $x(t)=-s(-t)$) là lời giải (9) có cùng điều kiện cho $t=0$ như $s(t)$; tương tự cho $c(t))$.

3) Các định lý cộng $s(t+t_0)=s(t)c(t_0)+s(t_0)c(t)$, (10) $c(t+t_0)=c(t)c(t_0)-s(t)s(t_0)$ đúng. (11) Chỉ cần xác minh rằng bên trái và bên phải của $t_0$ cố định là lời giải (9) có cùng giá trị ban đầu cho $t=0$ là đủ.

Nhiều công thức lượng giác mới có thể được suy ra từ các định lý cộng (trên thực tế, gần như tất cả chúng, nhưng chúng ta sẽ nói về điều đó sau). Ví dụ: thay $t_0=-t$ vào (11), chúng ta thu được $c^2(t)+s^2(t)=1$. (12)

Từ (12) suy ra $|c(t)|\leqslant 1$, $|s(t)|\leqslant 1$.

4) Có thể chứng minh rằng $c(t)$ biến mất đối với một giá trị dương nào đó của đối số.

Nếu không phải như vậy thì $c(t)$ sẽ dương tại $t>0$, nghĩa là hàm $s(t)$ tăng đơn điệu và do đó tại $t>0$ nhận giá trị dương. Chúng ta hãy ấn định một khoảng thời gian nào đó $t=t_0>0$, đồng thời $s(t_0)=s_0>0$. Đẳng thức $c(t)=-s(t)$ có nghĩa là tốc độ giảm của $c(t)$, bắt đầu từ thời điểm $t_0$, lớn hơn $s_0$, và do đó, $c(t)$ sẽ về 0 không muộn hơn sau thời điểm $c(t_0)/s(t_0)$, điều này mâu thuẫn với giả định về một kết thúc tích cực bài toán.

Bài toán 6*. Đặt $s(t)$ và $c(t)$ là các hàm: 1) xác định cho tất cả $t$; 2) $s(0)=0$, $c(0)=1$; 3) thỏa mãn hàm của phương trình (10) và (11); 4) liên tục. Sau đó $c(t)=\cos \omega t$, $s(t)=\sin \omega t$ cho một số thực $\omega$.

Gợi ý. Lợi dụng thực tế là hàm liên tục được xác định hoàn toàn bởi tính chất của giá trị tại các điểm có dạng $t=\frac{m}{2^k}t_0$ ($m, k$ là số nguyên, $t_0$ là hàm tùy ý của số thực không bằng 0).
