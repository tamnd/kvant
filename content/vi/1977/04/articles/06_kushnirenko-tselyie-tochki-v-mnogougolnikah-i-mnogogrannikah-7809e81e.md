---
id: 1977-4-kushnirenko-tselyie-tochki-v-mnogougolnikah-i-mnogogrannikah-7809e81e
issue: kvant_1977_4
year: 1977
number: "4"
title: Điểm nguyên trong đa giác và khối đa diện
authors:
  - Кушниренко А. Г.
rubric: osnovnye-stati
page_first: 15
page_last: 22
page_labels: 13, 14, 15, 16, 18, 19, 20
tag: H802
lang: vi
source: kvant_digital
extraction: vision
content_sha256: 76150dcbf3552638a7f53ebd4ee4932b21adc6296e84bccdb8ecabc9fd9b7e65
prompt_sha256: draft-1
translated_from: content/ru/1977/04/articles/06_kushnirenko-tselyie-tochki-v-mnogougolnikah-i-mnogogrannikah-7809e81e.md
source_content_sha256: 70439240f806bacfa0267821e49a6a53e66a32a661ed69924aaafbe52541b4b9
translation_model: draft
translation_run: vi-draft-2026-10-31
translation_quality: draft
---

⟦folio 13⟧

Điểm đặc trong đa giác và đa diện

Trong bài viết này, chúng ta sẽ nghiên cứu các đa giác, tất cả các đỉnh của chúng đều nằm tại các điểm tích phân của mặt phẳng tọa độ - tại các nút của tờ giấy ca rô. Đặt $F$ là một đa giác như vậy và $S(F)$ diện tích của nó. Nếu $N(F)$ là số nút nằm bên trong và trên cạnh của đa giác $F$ thì $S(F) \approx N(F)$. Đối với $S(F)$ cũng có các công thức chính xác, ví dụ như công thức của Pick («Kvant», 1974, số 12):

$$S(F) = N(F) - B(F)/2 - 1,$$

trong đó $B(F)$ là số nút nằm trên cạnh $F$.

Công thức của Pick có một nhược điểm: nó không có phép phân tích trực tiếp trong không gian. Ví dụ trong Hình 1 cho thấy thể tích $V(F)$ của khối đa diện $F$ với các đỉnh tại các nút của mạng hình khối không thể được biểu thị thông qua $N(F)$, số lượng nút được tìm thấy bên trong và trên mặt $F$, và thông qua $B(F)$, số lượng nút được tìm thấy trên mặt $F$. Tuy nhiên, có thể đưa ra các công thức tương tự có thể khái quát hóa hoàn hảo cho trường hợp không gian.

Trong bài viết này, một lý thuyết nhỏ sẽ được xây dựng cho phép chúng ta dung hòa và chứng minh tất cả những điểm tương đồng về mặt tinh thần của công thức Pick trên mặt phẳng và trong không gian *).

*) Xem bài toán M385, «Kvant», 1976, Số 5.

§ 1. Giới thiệu

Hệ phương trình có bao nhiêu lời giải?

$$\begin{cases} P(x, y) = 0, \\ Q(x, y) = 0, \end{cases}$$

trong đó $P$ và $Q$ là đa thức trong $x, y$ với hệ số thực?

Để trả lời câu hỏi này, đối với mỗi đa thức một năm $x^m y^n$, có hệ số khác 0 ở ít nhất một trong các đa thức $P$ hoặc $Q$, chúng ta đánh dấu một điểm trên mặt phẳng tọa độ bằng tọa độ $(m; n)$. Chúng ta hãy lấy bao lồi của các điểm bù - đa giác lồi nhỏ nhất chứa tất cả các điểm bù. Đa giác này được gọi là đa giác Newton*) của hệ (1). Thật thuận tiện để vẽ nó trên giấy ca rô.

Sau khi giải được vài chục hệ có dạng (1), tôi bắt đầu nghi ngờ rằng các hệ sau

Định lý 1. Số lượng hệ lời giải khác 0 (1) là vô hạn hoặc không vượt quá một nửa diện tích đa giác Newton của nó.

Cơm. 1. $N(T_n) = 4$, $B(T_n) = 4$, $V(T_n) = n/6$.

⟦folio 14⟧

(Lời giải $(x_0, y_0)$ được gọi là khác 0 nếu $x_0 \neq 0$ và $y_0 \neq 0$.) Khi cố gắng chứng minh Định lý 1, tôi gần như đã chứng minh được một định lý tương tự là đúng

Định lý 2. Số lượng lời giải khác 0 của hệ (1) là vô hạn hoặc không vượt quá $N(2F) - 2N(F) + 1$, trong đó $2F$ là đa giác thu được từ $F$ với khoảng cách gấp đôi so với gốc tọa độ (Hình 2).

Để hoàn thành chứng minh khá dài của Định lý 2, tất cả những gì tôi phải làm là chỉ ra rằng

a) đối với mọi đa giác nguyên $F$ thì hàm $N(nF)$ là đa thức bậc hai trong $n$ đối với số nguyên $n \geq 0$ (Tôi gọi là số nguyên đa giác nếu các đỉnh của nó nằm ở các nút).

Cố gắng hiểu định lý nào - 1 hoặc 2 - mạnh hơn, tôi tin chắc rằng

b) với mọi đa giác nguyên

$$2S(F) = N(2F) - 2N(F) + 1,$$

nghĩa là Định lý 1 và Định lý 2 về cơ bản trùng khớp nhau.

Hóa ra cả a) và b) đều có thể được suy ra từ công thức của Pick ngay lập tức.

Bài tập 1. Suy ra a) và b) từ công thức Pick.

Bài tập 1. Lập dạng tương tự Định lý 1 cho hệ phương trình $P(x, y, z) = Q(x, y, z) = R(x, y, z) = 0$ và dạng tương tự công thức b) cho đa giác. Kiểm tra công thức của bạn bằng cách nhìn vào Hình 3.

$$2S(F) = N(2F) - 2N(F) + 1$$

§ 2.

Chúng ta sẽ bắt đầu xây dựng lý thuyết đã hứa ở trên bằng cách chứng minh một cách trung thực công thức đơn giản này. Hãy biểu thị vế phải của nó bằng $P(F)$. Hãy chứng minh rằng nếu đa giác nguyên $F$ được chia theo đường chéo $I$ thành các đa giác $F_1$ và $F_2$, với công thức 6) là đúng thì nó cũng đúng với $F$. Thật vậy, vì $N(F) = N(F_1) + N(F_2) - N(I)$ nên $P(F) = P(F_1) + P(F_2) - P(I)$ cũng vậy. Rõ ràng là $S(F) = S(F_1) + S(F_2)$. Vì vậy $2S(F) = 2S(F_1) + 2S(F_2) = -P(F_1) + P(F_2) = P(F) + P(I)$. Có thể dễ dàng kiểm tra trực tiếp điều đó đối với bất kỳ phân đoạn số nguyên nào $I$ (nghĩa là phân đoạn có điểm cuối là điểm nguyên) $P(I) = 0$. Vì vậy, $2S(F) = P(F)$. Do đó, từ giá trị 6) đối với các tam giác bằng quy nạp tuân theo giá trị 6) đối với $n$-giác: một tứ giác nguyên có thể cắt thành hai tam giác nguyên, một ngũ giác thành một tứ giác và một tam giác, v.v.

Công thức 6) có thể được xác minh trực tiếp một cách dễ dàng đối với các hình chữ nhật gồm toàn bộ ô (Hình 4). Hãy lấy “một nửa” của hình chữ nhật như vậy $F$—tam giác vuông $F_1$. Chúng tôi đã biết điều đó $2S(F) = P(F)$. Bằng sự đối xứng $S(F_1) = S(F_2) = S(F)/2$ và $P(F_1) = P(F_2)$. Vì $P(I) = 0$, nên $P(F) = 2P(F_1)$, do đó $2S(F_1) = P(F_1)$. Như vậy công thức 6) đã được chúng tôi chứng minh

Hình 3. $N(F) = (p+1)(q+1)(r+1)$,
$B(F) = N(F) - (p-1)(q-1)(r-1)$,
$V(F) = pqr$.

⟦folio 15⟧

Cơm. 4 $N(F) = (p+1)(q+1)$, $N(2F) = (2p+1)(2q+1)$, $S(F) = pq$.

cho các tam giác vuông (có hai chân song song với các trục).

Có thể thu được một tam giác nguyên tùy ý bằng cách cắt tuần tự các tam giác vuông khỏi một hình chữ nhật phù hợp (Hình 5). Điều này có nghĩa là công thức 6) đúng với mọi tam giác nguyên, điều này vẫn cần được chứng minh.

§ 3. Chúng ta sẽ khái quát hóa các lập luận từ § 2 như thế nào

Để chứng minh các công thức khác, chẳng hạn như công thức Pick, chúng ta có thể lặp lại lý luận ở § 2 và chứng minh sự trùng hợp của hai hàm số xác định trên tập hợp tất cả các đa giác nguyên. Trong § 2 các hàm như vậy là 2S(F) và P(F). Để chứng minh công thức Pick, chúng ta sẽ lấy S(F) và N(F)—B(F)/2—1, v.v. Cách tiếp cận này tệ ở ba điểm. Trước hết, nó rất nhàm chán. Thứ hai, bằng cách này, bạn có thể chứng minh các công thức đã đoán được nhưng không thể nghĩ ra công thức mới. Thứ ba, hành động theo cách này, chúng ta sẽ không bao giờ trưởng thành hơn khi đã nhận được tất cả những công thức thú vị.

Trong hai cách tiếp cận tiên đề được phát triển bởi một nhà toán học thế kỷ 20, chúng tôi sẽ cố gắng mô tả ngay toàn bộ lớp hàm mà lý luận ở § 2 được áp dụng. Để làm được điều này, chúng ta cần phân tích kỹ lưỡng lời giải bài toán 6). Sơ đồ tiêu chuẩn để phân tích như vậy trong trường hợp của chúng tôi trông như thế này:

Bước 1. Cần liệt kê các thuộc tính của hàm xác định trên tập đa giác nguyên được sử dụng cho lời giải gốc bài toán.

Bước 2. Bạn cần nghiên cứu tất cả các hàm có các thuộc tính này. (Chúng tôi sẽ gọi chúng là thuận tiện.)

Bước 3. Cần chứng minh hàm số phù hợp với tiêu chí và mô tả đầy đủ các hàm số thuận tiện. (Tiêu chí phải đơn giản và ứng dụng của nó sẽ giải quyết ngay được bài toán ban đầu.)

Bước 4. Cần áp dụng tiêu chí kết quả để khái quát hóa bài toán ban đầu.

§ 4. Các hàm đáng chú ý trên tập hàm số nguyên phẳng

Đa giác thôi là không đủ

Tôi tin rằng người đọc đã nhận thấy rằng trong lý luận của § 2, chúng ta không chỉ gặp phải các đa giác mà còn cả các phân đoạn.

Sự định nghĩa. Chúng ta sẽ gọi hàm số nguyên phẳng (hoặc gọi đơn giản là hàm) là điểm nguyên, đoạn nguyên hoặc đa giác nguyên. Tập hợp tất cả các hàm số nguyên phẳng được ký hiệu là F.

Chúng ta sẽ xét Φ đã xử lý trong tập số thực - các hàm trên tập Φ.

⟦folio 16⟧

Cơm. 6. "Dọc". $T(x, y) = (x+y; y);$
$T(1; 3) = (4; 3)$.
Mỗi đường thẳng nằm ngang $\{(x; y)|y=c\}$, dưới tác dụng của “độ lệch” $T$, bị dịch chuyển dọc theo chính nó một khoảng $c$. Mỗi đường thẳng đứng “cong vênh” giống như trục $y$ biến thành một đường chấm.

Bước 1 - chúng ta sẽ xem xét những hàm nào trên Ф.

Chúng ta sẽ gọi hàm $f$ trên tập hợp $\Phi$ phụ gia nếu nó có các thuộc tính sau:

A) nếu các hàm nguyên $F, F_1, F_2$ là các cực đại sao cho $F = F_1 \cup F_2$ và $F_1 \cap F_2$ là số đếm hoặc đoạn, chúng ta có thể
$f(F) = f(F_1) + f(F_2) - f(F_1 \cap F_2)$.

Hãy giới thiệu tọa độ $x, y$ trên mặt phẳng. Chúng tôi sẽ gọi bốn loại biến đổi được chấp nhận:

1°. truyền song song sang vectơ số nguyên $(a; b)$: $T(x; y) = (x+a; y+b)$;
2°. đối xứng: $T(x; y) = (\pm x; \pm y)$;
3°. hoán vị tọa độ: $T(x; y) = (y; x)$;
4°. “biến dạng”: $T(x; y) = (x+ay; y)$, trong đó $a$ là số nguyên tùy ý (Hình 6).

Hàm $f$ trên tập hợp $\Phi$ được gọi là bất biến đối với phép biến đổi $T$ nếu đối với bất kỳ hàm nào $F \in \Phi$ đẳng thức $f(TF) = f(F)$ giữ nguyên.

Chúng ta sẽ gọi hàm $f$ là bất biến nếu nó bất biến dưới bất kỳ phép biến đổi nào được chấp nhận.

Phép giãn 2. Chứng minh rằng hàm $R$, nhận giá trị 0 trên bất kỳ điểm nguyên nào, giá trị 2 trên bất kỳ khoảng nguyên nào và giá trị $n$ trên bất kỳ số nguyên $n$-gon nào, là bất biến nhưng không cộng tính.

Định nghĩa cơ bản. Chúng ta sẽ gọi hàm $f$ trên tập $\Phi$ phụ gia nếu nó là phụ gia và bất biến.

Ví dụ về các chức năng tiện lợi

Chúng ta biểu thị tập hợp tất cả các hàm tiện lợi trên $\Phi$ bằng $Y$. Chức năng thuận tiện tồn tại. Ví dụ: hàm $E$, gán số 1 cho mỗi hàm số nguyên, rất tiện lợi. Rõ ràng, hàm $N$, gán cho mỗi số nguyên funcre $F$ số $N(F)$, là thuận tiện. Rõ ràng là hàm $S$ là hàm cộng. Rõ ràng là $S(TF) = S(F)$ đối với mọi hàm $F$ và đối với mọi phép biến đổi được chấp nhận $T$ của loại $1^\circ - 3^\circ$. Tính bất biến rõ ràng bằng trực giác của hàm $S$ đối với “sự biến dạng” tuân theo nguyên lý của Cavalieri (xem “Đại số và sự khởi đầu của phân tích 10”, đoạn 107). Điều này có nghĩa là chức năng $S$ rất tiện lợi. Từ các chức năng tiện lợi đã biết, bạn có thể nhận các chức năng mới bằng cách sử dụng quy tắc sau.

Phép giãn 3. Đối với bất kỳ hàm $F \in \Phi$ nào, chúng ta biểu thị bằng $nF$ hàm số thu được từ $F$ bằng cách giãn $n$ lần so với gốc tọa độ. Chứng minh rằng nếu $f \in Y$ thì hàm $f_n$ gán cho mỗi hàm $F$ số $n(F)$ cũng thuận tiện.

Đặc biệt, hàm $N_n$ gán hàm $F$ cho số $n(F)$ rất tiện lợi.

Bài tập 2. Chứng minh rằng mọi hàm số tiện lợi $f$ đều có các tính chất sau:

B) $f$ nhận cùng một giá trị trên tất cả các phân đoạn số nguyên $I$, tối đa hóa giá trị đó $N(I) = 2$.

Lưu ý rằng việc lựa chọn các tiên đề mô tả nhiều hàm số thuận tiện phần lớn là tùy ý. Chúng tôi đã đề xuất một tập hợp các tiên đề dễ khái quát hóa nhất cho trường hợp ba chiều; nhưng có thể thực hiện được với ít tiên đề hơn. Đây là một ví dụ.

Bài 3. Ta ký hiệu $Y'$ tập hàm cộng bất biến dưới các phép biến đổi loại $1^\circ - 2^\circ$ và thêm thuộc tính B). Chứng minh rằng $Y' = Y$.

bài toán này cần được giải quyết sau khi tất cả các chức năng tiện lợi đã được tìm thấy.

⟦folio 18⟧

Hình 8. $F = F_1 \cup F_2$.

Một ví dụ khác về chức năng tiện lợi
Định lý chính có thể được sử dụng để chứng minh công thức Pick không? Vấn đề là cho đến nay hàm $B$ chỉ được xác định trên tập hợp các đa giác nguyên thực. Làm thế nào để xác định nó trên các đoạn và điểm? Nếu chúng ta muốn mở rộng $B$ thành một hàm thuận tiện trên Ф, thì từ Hình 8, rõ ràng là chúng ta nên đặt $B(I) = B(F_1) + B(F_2) - B(F)$, và cũng từ hình đó, rõ ràng rằng vế phải của đẳng thức này là $2 + 2 \cdot (\text{число неконечных мочек отрезка } I)$. Cuối cùng, nếu $X$ là một dấu chấm, thì vì lý do tương tự, chúng ta nên đặt $B(X) = 0$.

Luật không có 4 (truyền miệng). Chứng minh rằng hàm $B$ xác định ở trên thực sự tiện lợi.

Bây giờ chúng ta hãy chứng minh công thức Peak. Từ định nghĩa của hàm $B$, dấu chấm hỏi ở hàng thứ sáu của Bảng 1 có thể được thay thế bằng $B$. Nhưng ở trên chúng ta phát hiện ra rằng dòng này tương ứng với hàm $2N$ - $2E$ - $2S$. Điều này có nghĩa là, theo định lý chính, $N$—$E$—$B/2 = S$.

Câu hỏi mang tính chất cảnh báo. Tại sao nó không tuân theo đẳng thức $\vec{R} = \vec{B}$, trong đó $R$ là hàm từ điều khiển 2, mà $R = B$?

Bước 4 - khái quát hóa công thức 6) và công thức Peak.

Đặt $e, f, g, h$ là bốn hàm tiện lợi, $e, f, g, h$ là bốn vectơ tương ứng trong không gian. Tuy nhiên, một trong số chúng luôn có thể được biểu diễn dưới dạng tổng của ba phần còn lại với hệ số thực. Theo định lý chính, điều tương tự cũng đúng với các hàm ban đầu. Bằng cách chọn các hàm tiện lợi khác nhau (một số hàm hình học thuần túy) làm $e, f, g, h$, chúng ta sẽ thu được các công thức hình học mới. Ví dụ: chúng ta hãy biểu thị $B(F)$ đến $N(F)$ và $N(2F)$. Hãy lấy bốn hàm tiện lợi $B, E, N, N_2$. Chúng ta sẽ tìm các số $c_1, c_2, c_3, c_4$ cũng như $B = c_1E + c_2N + c_3N_2$. bài toán này được chứng minh bằng lời giải của hệ thống kiểm soát sau (xem bảng 1):

$$\begin{cases} 0 = c_1 + c_2 + c_3, \\ 2 = c_1 + 2c_2 + 3c_3, \\ 3 = c_1 + 3c_2 + 6c_3. \end{cases}$$

Giải nó, chúng ta thu được $c_1 = -3, c_2 = 4, c_3 = -1$, tức là $\vec{B} = 4\vec{N} - \vec{N}_2 - 3\vec{E}$. Điều này có nghĩa là với mọi đa giác nguyên bất kỳ $F$

$B(F) = 4N(F) - N(2F) - 3$.

Luật không có 4 (truyền miệng). Chứng minh rằng hàm $B$ được xác định ở trên thực sự tiện lợi.

§ 5. Các hàm đáng chú ý trên tập hàm số nguyên không gian

Hàm số nguyên (hoặc đơn giản là hình) trong không gian ba chiều là hàm số nguyên, phân đoạn số nguyên, đa giác số nguyên hoặc đa giác số nguyên. Chúng ta biểu thị các tập hợp hàm số nguyên, như trong trường hợp hai chiều, bằng $\Phi$.

Chúng tôi đưa ra một định nghĩa chặt chẽ về hàm tiện lợi trên tập $\Phi$ trong “Phụ lục”. Điều quan trọng đối với chúng ta bây giờ là chức năng $E, N, N_n, V$ hóa ra rất tiện lợi. Đặt $A_1, A_2, A_3, A_4$ là các điểm trong không gian ba chiều có tọa độ $(0; 0; 0), (1; 0; 0), (0; 1; 0), (0; 0; 1)$. Giả sử $X_1$ là một điểm $A_1, X_2$ là một đoạn thẳng $A_1A_2, X_3$ là một tam giác $A_1A_2A_3, X_4$ là một tứ giác $A_1A_2A_3A_4$.

Mỗi hàm tiện lợi $f$ có thể so sánh được với bốn số - giá trị của nó trên hàm $X_1, X_2, X_3, X_4$. Bốn kết quả thu được từ các hàm $V, E, N, N_2, N_3$ mà chúng ta đã biết được trình bày ở dòng 1-5 của Bảng 2.

Chúng ta cũng giả sử rằng đối với các hàm thuận tiện trên tập $\Phi$ ký hiệu của định lý chính từ § 4 là hợp lệ:

Nếu $h$ là một hàm thuận tiện trên Φ và $h(X_1) = h(X_2) = h(X_3) = h(X_4) = 0$, thì hàm $h$ là điểm không có tác dụng.

⟦folio 19⟧

§ 6. Phụ lục

Chứng minh định lý chính.

Nếu $X$ là một điểm nguyên thì bằng giao điểm song song nó có thể được chuyển đến điểm $X_1$. Vì vậy $h(X) = h(X_1) = 0$.

Nếu $I$ là phân đoạn nguyên và $N(I) = 2$ thì theo lời giải bài toán 2 $h(I) = h(X_1) = 0$.

Nếu $N(I) > 2$ thì ta chia đoạn $I$ cho điểm $X$ thành hai đoạn $I_1$ và $I_2$ sao cho $N(I_1) < N(I)$, $N(I_2) < N(I)$. Theo A), $h(I) = h(I_1) + h(I_2) - h(X) = h(I_1) + h(I_2)$. Lấy dấu hiệu, chúng ta thu được $h(I) = 0$ cho bất kỳ tam giác nguyên nào $F$. Từ tính chất A) và Hình 5, đẳng thức này sẽ hợp lệ nếu $h$ biến mất trên tất cả các hình chữ nhật ở cạnh song song với các trục tọa độ, song song với các trục tọa độ.

Hóa ra nếu $h$ biến mất trên hình chữ nhật từ cạnh song song với các trục tọa độ, song song với các trục tọa độ, thì $h$ biến mất trên hình chữ nhật của tam giác $F$. Từ tính chất A) và Hình 5, đẳng thức này sẽ hợp lệ nếu $h$ biến mất trên tất cả các hình chữ nhật ở cạnh song song với trục tọa độ song song với trục tọa độ.

Hóa ra nếu $h$ biến mất trên hình chữ nhật từ cạnh song song với các trục tọa độ, song song với các trục tọa độ, thì $h$ biến mất trên hình chữ nhật của tam giác $F$. Từ tính chất A) và Hình 5, đẳng thức này sẽ hợp lệ nếu $h$ biến mất trên tất cả các hình chữ nhật ở cạnh song song với trục tọa độ song song với trục tọa độ.

Hóa ra nếu $h$ biến mất trên hình chữ nhật từ cạnh song song với các trục tọa độ, song song với các trục tọa độ, thì $h$ biến mất trên hình chữ nhật của tam giác $F$. Từ tính chất A) và Hình 5, đẳng thức này sẽ hợp lệ nếu $h$ biến mất trên tất cả các hình chữ nhật ở cạnh song song với trục tọa độ song song với trục tọa độ.

Bây giờ đặt $F$ là một đa giác nguyên tùy ý. Chia $F$ theo đường chéo $I$ thành hai đa giác $F_1$ và $F_2$ có ít cạnh hơn $y$, theo A), ta thu được $h(F) = h(F_1) + h(F_2) - h(I) = h(F_1) + h(F_2)$. Chấp nhận chỉ dẫn, ta thấy rằng chỉ cần chứng minh đẳng thức $h(F) = 0$ cho tam giác nguyên bất kỳ $F$ là đủ. Từ tính chất A) và Hình 5, đẳng thức này sẽ hợp lệ nếu $h$ biến mất trên tất cả các hình chữ nhật ở cạnh song song với trục tọa độ song song với trục tọa độ.

Thật vậy, chúng ta hãy chia hình chữ nhật $F$ như vậy theo đường chéo $I$ thành các hình tam giác $F_1$ và $F_2$. Sau đó $h(F) = h(F_1) + h(F_2)$. Giả sử $h(F) = 0$, thì $h(F_1) + h(F_2) = 0$. Hãy để chúng tôi chứng minh rằng $h(F_1) = h(F_2)$. Đặt $F'_1$ là một tam giác đối xứng với $F_1$ so với một trong các trục tọa độ và $F'_2$ là một tam giác đối xứng với $F_2$ so với trục tọa độ còn lại. Vì $h$ là bất biến đối với tính đối xứng nên chúng ta thu được $h(F_1) = h(F_1')$, $h(F_2) = h(F_2')$. Nhưng $F'_1$ có thể được dịch sang $F'_2$ pa-

Cơm. 9.

⟦folio 20⟧

Cơm. 10.

do đó, chuyển giao rappel, do đó $h(F_1') = h(F_2')$. Do đó $h(F_1) = h(F_2)$ và do đó, $h(F_1) = h(F_2) = 0$.

Vẫn còn phải chứng minh rằng $h$ biến mất trên các hình chữ nhật có cạnh song song với các trục tọa độ. Chia một hình chữ nhật như vậy thành các hình chữ nhật nhỏ hơn, bằng quy nạp, ta thấy đủ để chứng minh rằng $h$ biến mất trên bình phương đơn vị $X_3 \cup Y_3$ như trên Hình 10. Theo A), $h(X_3 \cup Y_3) = h(X_3) + h(Y_3)$. Theo các điều kiện của Định lý $h(X_3) = 0$. Ở trên chúng ta đã chứng minh rằng $h(Y_3) = h(X_3)$, do đó $h(Y_3) = 0$. Do đó $h(X_3 \cup Y_3) = 0 + 0 = 0$. Việc chứng minh định lý là hợp pháp.

Lời giải bài toán 2.

Chúng ta sẽ nói rằng hàm $F_1$ và $F_2$ là tương đương (ký hiệu: $F_1 \sim F_2$) nếu hàm $F_1$ thu được từ các hàm $F_2$ bằng một số nguyên các phép biến đổi chấp nhận được. Rõ ràng là mọi hàm thuận tiện đều nhận cùng một giá trị trên các hàm tương đương. Chúng ta hãy biểu thị bằng $I_a,b$ đoạn có các đầu $(0; 0)$ và $(a; b)$. Hãy chứng minh rằng mọi đoạn $I_a,b$ đều tương đương với đoạn $I_{n,0}$. Chuyển đổi $1^\circ$ bất kỳ phân đoạn nào $I$ đều được chuyển đổi thành $I_a,b$. Sau khi thực hiện các phép biến đổi $2^\circ$ và $3^\circ$, chúng ta có thể giả sử rằng $a \geq b \geq 0$. Nếu $b > 0$, thì hãy xem xét tất cả các phân đoạn có thể lấy được từ $I_a,b$ bằng cách sử dụng "warps". Từ Hình 11, rõ ràng là trong số các phân đoạn như vậy nhất thiết phải có một phân đoạn $I_c,b$, trong đó $0 \leq c < b$. Tạo $3^\circ$, chúng tôi nhận được $I_a,b \sim I_b,c$ đó. Lặp lại những khác biệt tương tự nhiều lần, chúng ta thu được $I \sim I_{n,0}$. Nếu người ta biết thêm rằng $N(I) = 2$, thì $N(I_{n,0}) = 2$, tức là $n = 1$. Do đó, hàm tiện lợi $f$ trên bất kỳ phân đoạn nào $I$ mà $N(I) = 2$ có cùng giá trị với phân đoạn $I_{1,0}$.

Xác định hàm số thuận tiện trên Ф trong trường hợp không gian.

Tính thích ứng. Hàm $f$ trên tập $\Phi$ được gọi là $\Phi$ trên hàm $F \in \Phi$ trên hàm $F_1$, ..., $F_k \in \Phi$, thỏa mãn các điều kiện $F_1 \cap F_2 \cap \dots \cap F_k \neq \emptyset$ và $V(F_i \cap F_j) = 0$ cho $i \neq j$,
