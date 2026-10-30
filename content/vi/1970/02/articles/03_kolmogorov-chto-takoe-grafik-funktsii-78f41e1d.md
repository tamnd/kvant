---
id: 1970-2-kolmogorov-chto-takoe-grafik-funktsii-78f41e1d
issue: kvant_1970_2
year: 1970
number: "2"
title: Đồ thị của hàm số là gì
authors:
  - Колмогоров А. Н.
rubric: osnovnye-stati
page_first: 5
page_last: 15
page_labels: 3, 4, 5, 6, 7, 8, 9, 10, 12, 13
tag: 669V
lang: vi
source: kvant_digital
extraction: vision
content_sha256: 66e272d91c289be81ef3ee887ab5db16faca179bb0c49125fbb55ccc624de4fd
prompt_sha256: 3ec6b8aabd9b98576af76503cd8a2902b9f5d18e01ee867dfb1228f59c6d52d8
translated_from: content/ru/1970/02/articles/03_kolmogorov-chto-takoe-grafik-funktsii-78f41e1d.md
source_content_sha256: cf759b539caa753e6caf65358e60375dffa5bb27cc2f769097e18b383331a0c9
translation_model: gpt-5.6-terra
translation_run: vi-codex-2026-10-30
---

⟦folio 3⟧

ĐỒ THỊ CỦA HÀM SỐ LÀ GÌ

A. N. KOLMOGOROV

Ở đây tiếp tục trình bày quan điểm mới,
tổng quát hơn về những khái niệm quen thuộc từ trường học —
hàm số và đồ thị của nó.
Phần đầu của sự trình bày này có trong bài
“Hàm số là gì”,
được đăng trong số đầu tiên của “Kvant”.
Để hiểu bài viết này
cần nắm được các khái niệm đã được xác định trong bài thứ nhất

1. NHẮC LẠI VÀ MỘT VÀI BỔ SUNG NHỎ

Trong số đầu tiên của tạp chí, qua bài “Hàm số là gì”, các em đã làm quen với cách hiểu tổng quát hiện đại về từ hàm số: hàm số là một ánh xạ hoàn toàn tùy ý của một tập hợp $E$ lên một tập hợp khác $M$. Tập hợp $E$ được gọi là miền xác định của hàm số, còn tập hợp $M$ — tập hợp các giá trị của nó. Để cho một hàm số có miền xác định $E$, cần chỉ ra cho mỗi phần tử $x$ của tập hợp này

1* 3

⟦folio 4⟧

$$y = f(x).$$

Dù ta làm điều đó bằng cách nào, ta cũng nhận được một hàm số có miền xác định $E$. Nếu tập hợp $E$ gồm các học sinh trong lớp của bạn, thì chẳng hạn, với bất kỳ học sinh $x$ nào, có thể lấy $y = f(x)$ là chữ cái thứ hai trong tên của em đó (giả sử rằng trong lớp không có học sinh nào có tên chỉ gồm một chữ cái duy nhất, — mặc dù tôi đã biết một cô bé tên Olya, người ta gọi đơn giản là “O”).

Với cách cho hàm số như vậy, tập hợp các giá trị $M$ của nó tự nhiên được xác định; đó là tập hợp tất cả những đối tượng $y$ mà tồn tại ít nhất một phần tử $x$ của tập hợp $E$, sao cho

$$f(x) = y.$$

Vì thế, khi mô tả ý nghĩa của thuật ngữ hàm số, có thể không nói rõ về tập giá trị. Chẳng hạn, sẽ đúng nếu chỉ nói rằng “hàm số là một quy luật, theo đó mỗi phần tử $x$ của một tập hợp nào đó $E$ được đặt tương ứng với một đối tượng hoàn toàn xác định $y = f(x)$”. Tuy nhiên, chúng tôi cho rằng không nên coi mọi mô tả như vậy là định nghĩa. Nếu thực sự muốn định nghĩa khái niệm hàm số thông qua khái niệm “quy luật”, người ta sẽ đòi hỏi chúng ta phải định nghĩa chính xác ý nghĩa của thuật ngữ “quy luật”, v.v. Ta sẽ coi khái niệm hàm số là một trong những khái niệm cơ bản của toán học, mà ý nghĩa chỉ được làm sáng tỏ chứ không được cho bằng một định nghĩa hình thức.

Ở trường, các em chỉ quen làm việc với các hàm số, miền xác định của chúng gồm các số và giá trị của chúng là các số. Ý nghĩa của cụm từ “hàm số của một đối số số” không hoàn toàn xác định. Bởi vì bản thân khái niệm số ở trường luôn được khái quát hóa. Ta sẽ dừng ở hệ thống tất cả các số thực, mà học sinh làm quen ở lớp chín. Các hàm thực của đối số thực chủ yếu được nghiên cứu ở các lớp cuối cấp trung học. Các em biết vẽ đồ thị của chúng trên “mặt phẳng số”.

Trong sách giáo khoa phổ thông, người ta viết rằng “mặt phẳng số” là một mặt phẳng mà trên đó các tọa độ được đưa vào theo một cách xác định nào đó. Nếu tin sách giáo khoa theo nghĩa đen, thì có rất nhiều mặt phẳng số. Kẻ các trục tọa độ trên bảng lớp, giáo viên biến mặt phẳng của chiếc bảng này thành một “mặt phẳng số”; học sinh trên các trang vở của mình tạo ra ngày càng nhiều “mặt phẳng số” mới, đôi khi vài cái trên cùng một trang!

Ở mục 3 của bài này, các em đã biết các nhà toán học thực sự làm việc với mặt phẳng số nào. Nhưng trước hết tôi muốn đưa ra một nhận xét bổ sung về phần trình bày trong bài “Hàm số là gì”.

Trong khóa học đại số ở trường, thường gặp nhất là các hàm số được cho “giải tích” bằng công thức. Miền xác định của một hàm số như vậy, nếu không nói gì khác, được coi là tập hợp mọi giá trị của đối số mà với chúng mọi phép toán trên các số được quy định trong công thức đều thực hiện được. Chẳng hạn, như thường làm ở trường, ta sẽ coi-

*) Từ bài thứ nhất, các em biết rằng giá trị của hàm số có thể không chỉ là các số, mà còn là những ngôi nhà, các cậu bé hoặc các cô bé, nói chung là bất cứ vật nào, hay như người ta thường nói, các “đối tượng”.

⟦folio 5⟧

dấu $V$ là dấu căn bậc hai “số học”. Rõ ràng, công thức

$$y = f(x) = (\sqrt{x})^2$$

(1)

cho phép tính giá trị $y$ tương ứng với $x$ đã cho chỉ khi $x$ không âm (nếu không thì căn bậc hai “không lấy được”).

Khi $x$ không âm

$$y = f(x) = x.$$

(2)

Công thức (2) đơn giản hơn công thức (1), và ta muốn coi nó là công thức xác định hàm số của ta. Nhưng miền xác định của hàm số được cho bởi công thức (2) không chỉ gồm các số $x$ không âm, mà gồm mọi số $x$. Nếu muốn cho một định nghĩa mới về chính hàm số được xác định bởi công thức (1), ta phải viết

$$y = f(x) = \begin{cases} x \text{ khi } x \geq 0, \\ \text{ không xác định khi } x < 0. \end{cases}$$

(3)

Tương tự, hàm số $g(x) = \frac{x^3 - 1}{x - 1}$ có thể được viết như sau:

$$g(x) = \begin{cases} x^2 + x + 1 \text{ khi } x \neq 1, \\ \text{ không xác định khi } x = 1. \end{cases}$$

(4)

Trong các kỳ thi ở trường phổ thông và đại học, người ta đòi hỏi độ chính xác đầy đủ trong những vấn đề như vậy.

2. ĐỒ THỊ CỦA HÀM SỐ

Xét đồ thị trực nhật sau đây (xem số 1 của “Kvant”, tr. 29):

| | Thứ Hai | Thứ Ba | Thứ Tư | Thứ Năm | Thứ Sáu | Thứ Bảy | Chủ Nhật |
| :--- | :--- | :--- | :--- | :--- | :--- | :--- | :--- |
| Petya | | | | | | | |
| Kolya | | | | | | | |
| Sasha | | | | | | | |
| Voloda | | | | | | | |

Ta đã biết rằng đây là đồ thị của một hàm số: tên của người trực nhật có thể coi là một hàm của ngày trong tuần. Vì có bảy ngày trong tuần, còn có bốn cậu bé, nên ta đã vẽ

$$7 \times 4 = 28$$

ô, nhưng chỉ tô đỏ bảy ô trong số đó. Nếu các cậu bé quyết định sắp xếp tên của mình theo thứ tự bảng chữ cái, thì sẽ được bảng ở tr. 6. Nó trông khác đi, nhưng biểu diễn cùng một sự phân công trực nhật — cùng một hàm số.

⟦folio 6⟧

Trong cả hai bảng, 28 ô tương ứng với 28 cặp có thể có (ngày trong tuần, cậu bé).

Trong 28 cặp này, bảy cặp được chọn ra
(thứ Hai, Petya), (thứ Ba, Kolya), (thứ Tư, Sasha), (thứ Năm, Voloda),
(thứ Sáu, Petya), (thứ Bảy, Kolya), (chủ Nhật, Sasha),

tức là tất cả các cặp mà trong đó ngày trong tuần được nối với người trực nhật vào ngày ấy:
(ngày trong tuần, người trực nhật vào ngày ấy),

hay trừu tượng: các cặp dạng
$(x, f(x))$.

Chỉ việc chọn các cặp này là điều cốt yếu để xác định hàm số.
Sau ví dụ này, có lẽ bạn sẽ không thấy định nghĩa sau là cần thiết:
Đồ thị của hàm số $f$ là tập hợp tất cả các cặp $*$
$(x, y)$,
sao cho: 1) phần tử thứ nhất của cặp $x$ thuộc miền xác định của hàm số,
2) phần tử thứ hai của cặp
$$y = f(x).$$

| | Thứ Hai | Thứ Ba | Thứ Tư | Thứ Năm | Thứ Sáu | Thứ Bảy | Chủ Nhật |
| :--- | :--- | :--- | :--- | :--- | :--- | :--- |
| Voloda | | | | | | | |
| Kolya | | | | | | | |
| Petya | | | | | | | |
| Sasha | | | | | | | |

Trong ví dụ của chúng ta, đồ thị của hàm số $f$:
$$\Gamma_f = \{(пн, Петя), (вт, Коля), (cp, Саша), (чт, Волода), (пт, Петя), (сб, Коля), (вс, Саша)\}.$$
Đối với các hàm số được cho bằng bảng

| $x$ | $f_1$ | $f_2$ | $f_3$ | $f_4$ |
| :--- | :--- | :--- | :--- | :--- |
| $A$ | $A$ | $B$ | $A$ | $B$ |
| $B$ | $A$ | $B$ | $B$ | $A$ |

*) Ở mọi chỗ trong bài này đều hiểu là “cặp có thứ tự”. Cặp (1,2) khác với cặp (2,1). Phần tử thứ nhất và thứ hai của cặp cũng có thể trùng nhau: (1,1) hoặc (2,2) cũng là các cặp.

⟦folio 7⟧

theo định nghĩa đã cho, ta thu được các đồ thị

$$\Gamma_1 = \{(A, A), (B, A)\}, \quad \Gamma_2 = \{(A, B), (B, B)\},
\quad \Gamma_3 = \{(A, A), (B, B)\}, \quad \Gamma_4 = \{(A, B), (B, A)\}.$$

Rõ ràng, đối với một hàm có miền xác định hữu hạn, số phần tử của đồ thị (tức là số cặp thuộc đồ thị) bằng số phần tử của miền xác định của hàm. Đối với một hàm có miền xác định vô hạn, không thể liệt kê tất cả các cặp

$$(x, f(x))$$

được. Phải mô tả các cặp này bằng các tính chất của chúng. Chẳng hạn, đối với hàm

$$y = f(x) = \sqrt{1-x^2}$$

đồ thị gồm tất cả các cặp $(x, y)$ thỏa mãn hai điều kiện

$$x^2 + y^2 = 1 \text{ và } y \geq 0.$$

Định nghĩa này của đồ thị hàm số có thể viết dưới dạng

$$\Gamma_f = \{(x, y) | x^2 + y^2 = 1, \ y \geq 0\}.$$

Bản thân định nghĩa tổng quát về đồ thị của hàm $f$ có thể viết dưới dạng công thức sau *):

$$\Gamma_f = \{(x, y) | y = f(x)\}.$$

Khi định nghĩa đồ thị của một hàm là tập hợp các cặp, mỗi cặp gồm giá trị của đối số và giá trị của hàm tương ứng với giá trị ấy của đối số, ta đã giải phóng khái niệm đồ thị khỏi mọi điều ngẫu nhiên. Theo cách hiểu trừu tượng này, mỗi hàm có một và chỉ một đồ thị.

3. MẶT PHẲNG SỐ

Hãy xét các hàm thực của biến thực thường gặp nhất ở trường học. Ở trường, các em đã quen với việc gọi đồ thị của một hàm như vậy $f$ là tập hợp những điểm $P(x, y)$ của mặt phẳng số mà các tọa độ $x$ và $y$ thỏa mãn đẳng thức

$$y = f(x).$$

Cách phát biểu này và định nghĩa chung về đồ thị đã cho ở trên, ở mục 2, giống nhau, nhưng hơi khác nhau. Ở mục 2 nói về tập hợp các cặp $(x, y)$, còn trong định nghĩa thông thường ở trường học — về tập hợp các điểm $P$ có tọa độ $x$ và $y$. Nhưng chẳng lẽ không thể đưa hai cách phát biểu này đến chỗ hoàn toàn thống nhất?

*) Chúng tôi dùng ký hiệu chuẩn, được chấp nhận trong lý thuyết tập hợp.

$$\{x | A(x)\}$$

ký hiệu tập hợp tất cả các đối tượng $x$ thỏa mãn điều kiện $A(x)$. Chẳng hạn, $\{x | x^2 = 1\}$ — tập hợp tất cả các $x$ mà với chúng $x^2 = 1$, tức là tập hợp gồm hai số: $\{1, -1\}$.

⟦trang 8⟧

Hóa ra, điều đó rất đơn giản. Chính lời giải đơn giản này đã được phổ biến rộng rãi trong văn liệu khoa học hiện đại. Theo định nghĩa, người ta coi mặt phẳng số là tập hợp tất cả các cặp số thực. Mặt phẳng số được ký hiệu là $R^2$. Định nghĩa của nó có thể viết bằng ký hiệu như sau

$$R^2 = \{x, y \mid x \in R, y \in R\}.$$

Suy nghĩ một chút, bạn sẽ tự thấy rằng với định nghĩa như vậy về mặt phẳng số, định nghĩa thông thường ở trường học về đồ thị của hàm số thực của biến số thực trở thành một bộ phận của định nghĩa chung đã cho ở mục 2.

Ký hiệu $P(x, y)$ cho điểm có tọa độ $x$ và $y$ giờ trở nên không cần thiết. Các điểm của mặt phẳng số theo nghĩa mới chỉ là các cặp số $(x, y)$. Có thể nói đơn giản về “điểm $(0, 0)$” (gốc tọa độ), về các điểm $(1, 2), (-2, -1)$ v.v.

Cần lưu ý rằng thuật ngữ “đường thẳng số” giờ cũng phải mang một nghĩa mới: đường thẳng số đơn giản là chính tập hợp các số thực $R$. Đương nhiên, các điểm của đường thẳng số khi đó phải được coi đơn giản là các số thực. Hiển nhiên trong sách giáo khoa phổ thông điều này không được nói trực tiếp, nhưng thường dùng ngôn ngữ hình học khi nói về các số: tập hợp các số

$$[a, b] = \{x \mid a \leqslant x \leqslant b\}$$

được gọi là “đoạn thẳng”, nói rằng “điểm” 2 thuộc “đoạn thẳng” [1, 3] v.v.

Bất kỳ tập hợp nào gồm các điểm của mặt phẳng số sẽ được gọi là một hình hình học nằm trên mặt phẳng số. Chẳng hạn, đường tròn tâm $(0, 0)$ và bán kính bằng một: đó là tập hợp các điểm, tức là các cặp số $(x, y)$, mà với chúng

$$x^2 + y^2 = 1.$$

Đương nhiên, các điểm và các hình hình học của mặt phẳng số có thể được biểu diễn trực quan trên bản vẽ. Để làm điều đó, trên mặt phẳng thực (tờ giấy hoặc bảng) người ta chọn các trục tọa độ và biểu diễn điểm của mặt phẳng số $(x, y)$ bằng một điểm thực có tọa độ $x$ và $y$. Tất nhiên, sự biểu diễn như vậy chỉ có thể là gần đúng. Các đồ thị được vẽ trên giấy hoặc trên bảng chỉ là những hình biểu diễn gần đúng của các đồ thị “thật” của các hàm số, mà theo cách hiểu của chúng ta đơn giản là các tập con của mặt phẳng số. Chính các đồ thị “thật” này là đối tượng của khẳng định rằng một hàm số được xác định hoàn toàn bởi đồ thị của nó.

Cho một tập hợp các cặp

$$M = \{(x, y)\}.$$

Chẳng hạn, bất kỳ “hình” nào trên mặt phẳng số đều là một tập hợp như vậy. Cần đòi hỏi thêm điều gì để tập hợp các cặp này là đồ thị của một hàm số nào đó?

⟦folio 9⟧

Câu trả lời không khó: điều cần và đủ là trong tập hợp $M$ không thể tìm được hai cặp $(x, y_1)$ và $(x, y_2)$ có cùng phần tử thứ nhất $x$ và các phần tử thứ hai khác nhau $y_1 \neq y_2$. (Hãy tự chứng minh.) Trên hình 1, đường cong đỏ là đồ thị của một hàm, còn đường cong đen không phải là đồ thị.

Tập hợp các cặp $(x, y)$, trong đó không tồn tại hai cặp dạng $(x, y_1), (x, y_2), y_1 \neq y_2$, có thể gọi là đồ thị hàm. Hãy lưu ý rằng lúc này ta đã định nghĩa “đồ thị hàm” mà không dùng khái niệm “hàm”. Có thể từ phía này đưa ra một định nghĩa hình thức cho chính khái niệm hàm, khái niệm mà chúng ta coi là cơ bản, tức là không cần định nghĩa hình thức, hay không? Tôi không muốn trả lời câu hỏi này ở đây. Nó không hoàn toàn đơn giản. Trong tạp chí của chúng ta, còn sẽ có dịp trở lại cả những quan niệm hiện đại về khái niệm hàm lẫn lịch sử của nó.

4. CÁC PHÉP BIẾN ĐỔI HÌNH HỌC

Để làm quen với cách hiểu rộng về thuật ngữ “hàm”, hãy xét thêm một số phép biến đổi hình học đơn giản.

Để quay một hình phẳng quanh điểm $O$ (hình 2), có thể chép các đường bao của hình lên giấy can đặt trên mặt phẳng bản vẽ, ghim giấy can tại điểm $O$ và, sau khi quay giấy can, chép các đường bao của bản sao của hình từ giấy can sang mặt phẳng bản vẽ (chẳng hạn bằng giấy than). Khi quay, mọi điểm của hình đều quay quanh $O$ theo cùng một chiều và cùng một góc.

Ký hiệu

$$Q = R_0^\alpha(P)$$ (1)

vị trí của điểm $P$ sau khi quay một góc $\alpha$ ngược chiều kim đồng hồ. Nếu điểm $O$ và góc $\alpha$ được cho, thì mỗi điểm $P$ theo công thức (1) xác định hoàn toàn điểm $Q$. Rõ ràng rằng theo nghĩa định nghĩa của chúng ta, $R_0^\alpha$ là một hàm. Miền xác định của nó là tập hợp các điểm $P$ của mặt phẳng.

Các góc quay được chỉ ra kèm dấu. Trên hình 3, điểm $Q_2$ nhận được từ điểm $P$ bằng phép quay $120^\circ$, còn điểm $Q_1$ — bằng phép quay $-120^\circ$ (hoặc phép quay $240^\circ$). Nếu điểm $Q$ nhận được từ điểm $P$ bằng phép quay $\alpha$ độ, thì điểm $P$ có thể nhận được bằng cách quay $Q$ đi $-\alpha$ độ: nếu

$$Q = R_0^\alpha(P),$$

⟦folio 10⟧

$$P = R^{-\alpha} o(Q).$$

Ta thấy rằng phép quay $R_0^\alpha$ luôn là một hàm khả nghịch.

Khi áp dụng cho các phép quay, người ta thường nói về «ánh xạ». Ánh xạ ngược với phép quay $R_0^\alpha$ là phép quay $R_0^{-\alpha}$. Viết bằng ký hiệu:

$$R_0^{-\alpha} (R_0^\alpha(P)) = P,$$
$$(R_0^\alpha)^{-1} = R_0^{-\alpha}.$$

Phép quay ánh xạ tập hợp các điểm của mặt phẳng lên chính nó. Nếu coi mặt phẳng không là gì khác ngoài tập hợp các điểm của nó (người ta vẫn làm như vậy trong cách trình bày hình học hiện đại), thì có thể nói rằng phép quay là một ánh xạ khả nghịch của mặt phẳng lên chính nó.

Các ánh xạ khả nghịch của mặt phẳng lên chính nó được gọi là các phép biến đổi hình học của mặt phẳng. Các em đã gặp các phép biến đổi hình học nhiều lần trên các trang tạp chí của chúng tôi. Còn bây giờ chỉ nêu thêm một ví dụ về phép biến đổi hình học của mặt phẳng. Phép tịnh tiến song song là ánh xạ của mặt phẳng lên chính nó

$$P \rightarrow Q = T(P),$$

trong đó mọi điểm $P$ được dịch chuyển cùng một khoảng cách và theo cùng một hướng (hình 4).

5. VECTƠ

Mặc dù đã xuất hiện rằng các em đã xác lập từ việc làm quen với những khái niệm mới và cách giải thích không quen thuộc về những điều các em đã biết, chúng ta sẽ làm thêm một điều thành công nữa. Hãy cố gắng hiểu đồ thị và của phép tịnh tiến song song $P \rightarrow Q = T(P)$ là gì. Theo định nghĩa chung, đó là tập hợp mọi cặp điểm

$$(A, B),$$

mà với chúng

$$B = T(A).$$

⟦folio 12⟧

3. Cần thêm điều kiện bổ sung nào vào công thức
$$f(x) = 1,$$
để thu được hàm xác định
$$f_4(x) = (\sqrt{x})^2 + (\sqrt{1-x})^2?$$

Chú ý e. Trong các bài toán 1—3, dưới dấu $V$ hiểu là căn bậc hai «số học», tức là số không âm.

2. Đồ thị của hàm số

4. Có bao nhiêu hàm số với miền xác định 1, 2, 3 mà đồ thị là các tập con của tập các cặp
$$\{(1,1), (1,2), (2,1), (2,2), (2,3), (3,3)\}$$

(xem hình 6)?
Có bao nhiêu trong các hàm số này có hàm ngược?

5. Chứng minh rằng đồ thị của hàm ngược $f^{-1}$ được xác định bởi công thức
$$\Gamma_{f^{-1}} = \{(x, y) | (y, x) \in \Gamma_f\}.$$
(Tất nhiên, giả sử rằng hàm $f$ có hàm ngược.)

3. Mặt phẳng số

6. Mô tả cấu tạo của đồ thị hàm Dirichlet:
$$D(x) = \begin{cases} 1, nếu x рационально, \\ 0, nếu x irrationalно. \end{cases}$$

7*) Số $x$ thuộc đoạn [0; 1] được khai triển thành phân số tam phân vô hạn
$$x = 0, x_1 x_2 x_3 \dots (x_n = 0, 1, 2).$$

Giá trị của hàm số $y = C(x)$ được xác định bởi phân số nhị phân
$$y = 0, y_1 y_2 y_3 \dots (y_n = 0, 1)$$
theo cách sau:
nếu $x_n = 0$, thì $y_n = 0$,
nếu $x_n = 1$ hoặc $x_n = 2$, thì:
$$y_n = 1$$ với điều kiện trong các chữ số $x_1, x_2, \dots, x_{n-1}$ chưa có chữ số một,
$$y_n = 0$$ với điều kiện trong các chữ số $x_1, x_2, \dots, x_{n-1}$ đã xuất hiện một chữ số một.

Hãy thử vẽ đồ thị của hàm số này. Chứng minh rằng nó chứa vô hạn đoạn thẳng nằm ngang. Nếu bạn biết khái niệm về tính liên tục của hàm số, hãy thử chứng minh rằng hàm số của chúng ta liên tục.

Chú ý e. Trong bài toán này, chúng ta không loại trừ các phân số tam phân mà từ một chỗ nào đó trở đi mọi chữ số đều là hai, và các phân số nhị phân mà từ một chỗ nào đó trở đi mọi chữ số đều là một. Chẳng hạn, trong hệ tam phân ta viết
$$0,2222 \dots = 1; 0,1222 \dots = 0,200000 \dots$$

và trong hệ nhị phân ta coi rằng
$$0,1111111 \dots = 1; 0,01011111 \dots = 0,01100000 \dots$$

*) Đây là một bài toán khó (xem § 15 trong sách: S. V. Fomin «Các hệ đếm», 1968.

⟦folio 13⟧

4. Các phép biến đổi hình học

8. Hãy mô tả bằng các thuật ngữ hình học những phép biến đổi của mặt phẳng tọa độ, tương tự các công thức bài toán:

a) $(x, y) \rightarrow (-y, x)$,
b) $(x, y) \rightarrow (x, -y)$,
c) $(x, y) \rightarrow (y, -x)$,
d) $(x, y) \rightarrow (x+1, y)$,
e) $(x, y) \rightarrow (x+a, y+a)$.

9. Chứng minh công thức sau đối với các phép quay quanh tâm $O$

$$R_O^\alpha [R_O^\beta (P)] = R_O^{\alpha+\beta}(P).$$

(1)

10. Chứng minh rằng với mọi tâm $O_1$ và $O_2$, phép biến đổi

$$F(P) = R_O^\alpha [R_O^{-\alpha}(P)]$$

là một phép tịnh tiến. Theo hướng nào và với độ dài bao nhiêu?

5. Vectơ

11. Chứng minh công thức

$$T_a [T_b(P)] = T_{a+b}(P).$$

(2)

12. Chứng minh rằng phép biến đổi

$$F(P) = T_a [R_O^\alpha(P)]$$

là một phép quay góc $\alpha$. Quanh tâm nào?

Nhận xét. Các công thức (1) và (2) thường được viết ngắn gọn là

$$R_O^\alpha R_O^\beta = R_O^{\alpha+\beta},$$

$$T_a T_b = T_{a+b}.$$

Việc lấy hàm của các hàm ở nhiều phương diện giống với phép nhân. Nhưng đó đã là một chủ đề riêng, việc phát triển nó không suy giảm ở đất nước này. Chúng ta sẽ dùng cách viết ngắn gọn như vậy của hàm của các hàm (hợp các ánh xạ) trong các bài 13 và 14.

13. Chứng minh rằng luôn luôn

$$T_a T_b = T_b T_a$$

và

$$R_O^\alpha R_O^\beta = R_O^\beta R_O^\alpha$$

khi quay quanh cùng một tâm. Hãy chỉ ra bằng ví dụ rằng, nói chung,

$$R_O^\alpha R_O^\beta \neq R_O^\beta R_O^\alpha$$

khi quay quanh các tâm $O_1, O_2$.

14. Hãy làm rõ đầy đủ vấn đề về khi nào thì

$$R_O^\alpha R_O^\beta = R_O^\beta R_O^\alpha.$$
