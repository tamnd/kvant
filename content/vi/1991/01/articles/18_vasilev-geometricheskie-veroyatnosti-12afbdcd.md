---
id: 1991-1-vasilev-geometricheskie-veroyatnosti-12afbdcd
issue: kvant_1991_1
year: 1991
number: "1"
title: xác suất hình học
authors:
  - Васильев Н. Б.
rubric: matematicheskiy-kruzhok
rubric_sub: Математический кружок
page_first: 49
page_last: 54
page_labels: 47-52
lang: vi
source: kvant_digital
extraction: vision
content_sha256: 6b353c76829f30f9e2e320a92279b4165f8a154ded80ded87daba85a8f38438a
prompt_sha256: draft-1
translated_from: content/ru/1991/01/articles/18_vasilev-geometricheskie-veroyatnosti-12afbdcd.md
source_content_sha256: 013ea86c3d5467df1f0f3b53adf98eaa0c2b296c1c11f842701fda64c8dd6445
translation_model: draft
translation_run: vi-draft-gaps-2026-11-06
translation_quality: draft
---

⟦folio 47⟧

---
running_head:
folio:
---

vòng tròn toán học

xác suất hình học

Ứng viên Khoa học Vật lý và Toán học
N. VASILBEV

Trong bài viết này, chúng ta sẽ không quan tâm đến việc xác định các khái niệm cơ bản của lý thuyết xác suất mà sẽ làm quen với một số vấn đề trong đó chúng ta có thể tính xác suất của một thông điệp đối xứng, cũng như biểu diễn trực quan của chính nó bằng cách sử dụng tọa độ trên một mặt phẳng.

Trong trường hợp này, chúng ta sẽ giải quyết không chỉ những bài toán có số hữu hạn các phương án khả thi như nhau mà còn giải quyết những bài toán có vô số phương án. Đây là hai trong số đó.

Vấn đề về cuộc họp. Hai Prigels đồng ý gặp nhau trên Quảng trường Mayakovsky từ 12 đến 13 giờ. Mỗi

Một người đến vào một thời điểm ngẫu nhiên nào đó, đợi người kia 15 phút rồi rời đi. Xác suất để họ gặp nhau là bao nhiêu?

Bài toán về tam giác nhọn. Ba điểm được chọn ngẫu nhiên trên vòng tròn. Xác suất để một tam giác có các đỉnh tại các điểm này là nhọn là bao nhiêu?

Nhưng chúng ta vẫn sẽ dạy từ những ví dụ đơn giản hơn, hữu hạn hơn.

Ném xúc xắc

Công cụ thuận tiện nhất cho người lần đầu làm quen với xác suất là xúc xắc: một khối lập phương có các mặt được đánh số 1, 2, ..., 6.

Vì khuôn hoàn toàn đối xứng nên chúng tôi xem xét tất cả sáu lựa chọn có thể có cùng xác suất. Giả sử xác suất đổ được số sáu là 1/6, xác suất đổ được số không nhỏ hơn 3 là 4/6=2/3, xác suất đổ được số lẻ

⟦folio 48⟧

---
running_head:
folio:
---

kov, bằng 1/2. (Tuân thủ xã hội về “kết quả thuận lợi” - thể hiện bằng màu đỏ trên Hình 1 a, 6, e.)

Nếu không có xúc xắc trong tay, bạn có thể dễ dàng lăn những chiếc bút chì hình lục giác lên bàn với các số 1, 2, ..., 6 được viết ở hai bên. Thật dễ dàng để tưởng tượng những chiếc bút chì không phải có 6 mà có số n cạnh bất kỳ.

Vì vậy, con đường chúng ta có là một công cụ cung cấp n lựa chọn khả thi như nhau. Theo định nghĩa, chúng tôi giả định rằng xác suất của mỗi tùy chọn này được thực hiện là bằng 1/n và xác suất của mỗi thuộc tính A, bao gồm k tùy chọn, bằng k/n.

Tất nhiên, với n=6, thật dễ dàng để liệt kê tất cả các tùy chọn, mô tả chúng trên hình. Nhưng khi số lượng lựa chọn n lớn, một số quy tắc tính xác suất sẽ có ích.

Chúng ta sẽ biểu thị xác suất sở hữu A là p(A). Cuộc họp của chúng ta chỉ đơn giản là một tập con nhất định của tập E gồm tất cả các phương án có thể có, với p(E)=1. Đối với một con xúc xắc được ném, tập E bao gồm sáu phần tử 1, 2, ..., 6. Mối quan hệ đơn giản nhất giữa các xác suất phát sinh từ mối quan hệ giữa tập hợp, hay chính xác hơn là số phần tử trong chúng.

Xác suất của thuộc tính $\bar{A}$ bổ sung cho A (nó bao gồm tất cả các phần tử của E không có trong A) bằng

$$p(\bar{A}) = 1 - p(A).$$

(1)

Ví dụ: nếu A gồm các số từ 1 đến 6 chia hết cho 3 thì $\bar{A}$ là số không chia hết cho 3; $p(A) = 1/3$, $p(\bar{A}) = 1 - 1/3 = 2/3$ (hình 1, 2).

Hợp $A \cup B$ là một sự kiện bao gồm việc có ít nhất một trong hai sự kiện xảy ra: A hoặc B. Nếu sự kiện A và B không tương thích, tức là hai tập hợp A và B không cắt nhau, thì

$$p(A \cup B) = p(A) + p(B).$$

(2)

Nếu sự kiện A và B tương thích nhau, nghĩa là có giao điểm AB không trống, thì

$$p(A \cup B) = p(A) + p(B) - p(AB).$$

(3)

(Giao điểm của hai tập hợp A và B - một sự kiện trong đó A và B được thực hiện đồng thời - chúng ta biểu thị, theo thông lệ trong lý thuyết xác suất, đơn giản là AB.)

Kiểm tra lặp đi lặp lại

Hãy tưởng tượng rằng con xúc xắc được tung hai lần (hoặc con xúc xắc được ném cùng một lúc); đây là hai bài kiểm tra độc lập.

Bài toán 1. Xác suất để ở lần quay đầu tiên bạn nhận được ít nhất 5 điểm và ở lần quay thứ hai bạn nhận được ít nhất 4 điểm là bao nhiêu?

Bây giờ tập E là tập hợp tất cả các cặp (x, y), trong đó x và y là các số từ 1 đến 6 (x nghĩa là số điểm lăn được trên xúc xắc đầu tiên, y trên xúc xắc thứ hai). Tất cả các cặp (x, y) đều có xác suất như nhau, số của chúng là 6·6=36. Thật thuận tiện khi biểu diễn chúng dưới dạng hình vuông 6x6: một ô có tọa độ x và y đại diện cho một cặp (x, y) (hình 2). Từ đó cần chọn ra những ô thỏa mãn điều kiện bài toán: $x \leq 5$, $y \leq 4$. Chúng sẽ điền vào một đường thẳng gồm các ô 2x3. Vì vậy, trong số 6 6 cặp, 2 3 được chọn nên xác suất mong muốn bằng

$$\frac{2 \cdot 3}{6 \cdot 6} = \frac{6}{36} = \frac{1}{6}.$$

Nói chung, nếu sự kiện A được xác định bởi kết quả của lần thử đầu tiên và B - theo lần thử thứ hai (nghĩa là A là một tập hợp các cột nhất định)

⟦folio 49⟧

---
running_head:
folio:
---

và $B$ là một số tập hợp chuỗi),
thì xác suất thực hiện đồng thời $A$ và $B$ bằng
$$p(AB) = p(A) \cdot p(B).$$
Trong trường hợp này, các sự kiện $A$ và $B$ được gọi là độc lập. Quy tắc tích số (4) cũng có thể được sử dụng cho một số lượng lớn các phép thử độc lập. Ví dụ: xác suất nhận được năm hoặc sáu trên mỗi lần tung xúc xắc là $(1/3)^3 = 1/27$.

Bây giờ chúng ta hãy xem xét hai ví dụ trong đó trẻ cũng giải quyết hai phép thử, tức là $E$ là một tập hợp các cặp $(x, y)$, nhưng sự kiện mà chúng ta quan tâm phụ thuộc vào $x$ và $y$ theo cách phức tạp hơn, do đó điều kiện “độc lập” không còn được thỏa mãn.

Bài toán 2. Xác suất để ít nhất một trong hai lần tung xúc xắc đạt ít nhất 5 điểm là bao nhiêu?

Các cặp trùng khớp được đánh dấu ở hình 3, vì vậy xác suất mong muốn là $20/36 = 5/9$.

Lưu ý rằng chúng ta có thể nghĩ khác: tìm xác suất bổ sung để không quá 4 điểm xuất hiện ở cả lần ném thứ nhất và thứ hai. Điều này có thể được thực hiện bằng cách sử dụng quy tắc tích số: $(2/3) \times (2/3) = 4/9$, do đó xác suất mong muốn bằng $1 - \frac{4}{9} = \frac{5}{9}$.

Bài 3. Xác suất để số điểm đạt được trong hai lần tung khác nhau không quá 1 là bao nhiêu?

Các cặp bắt buộc được đánh dấu trên hình 4, đây là 6 ô dọc theo đường chéo $x=y$ và 5 trên hai đường thẳng song song liền kề. Xác suất yêu cầu là $16/36 = 4/9$.

Số và điểm ngẫu nhiên:
phân phối đồng đều

Bây giờ chúng ta sẽ nói về các điểm ngẫu nhiên trên một đoạn, trên một hình tròn, trong một hình vuông... Xác suất được xác định trong trường hợp này như thế nào? Những “sự kiện” nào có thể được xem xét?

Hãy lăn những chiếc bút chì tròn trên bàn - một hình trụ. Để bề mặt của nó có màu vàng, nhưng một số dải (hoặc một số dải) có chiều rộng $\alpha$ được phủ màu đỏ (hình 5); Xác suất để bút chì nằm trên vạch đỏ thay vì vạch vàng là bao nhiêu? (Ở đây $\alpha$ là góc được thay đổi, tính bằng độ.)

Hãy tưởng tượng một bài toán tương tự về những chiếc bút chì có số cạnh $n$ lớn, trong đó $k$ được phủ màu đỏ. Khi đó xác suất mong muốn sẽ bằng tỷ lệ $k/n$. Đối với một cây bút chì tròn, tập hợp các “sự kiện cơ bản” $E$ là một vòng tròn và xác suất của từng phần tử riêng lẻ - xác suất còn lại trên một dòng cụ thể - là 0; nhưng xác suất để sự kiện “dừng lại trên một trong các vạch đỏ” đương nhiên được coi là bằng tỷ lệ $\alpha/360^\circ$.

Tương tự như vậy, nói về một điểm ngẫu nhiên trên một đoạn (hoặc trên một đường tròn) có độ dài $L$, chúng ta sẽ giả sử rằng xác suất nó rơi vào bất kỳ đoạn nào

⟦folio 50⟧

---
running_head:
folio:
---

Cung (hoặc cung) có độ dài $d$ bằng $d/L$. Theo quy tắc (1), chúng tôi cũng giả sử rằng xác suất rơi vào một trong các đoạn đã cho (không giao nhau) có tổng chiều dài $d$ bằng $d/L$. Ví dụ: xác suất để chữ số đầu tiên sau dấu thập phân của một số ngẫu nhiên trên khoảng [0; 1] là số nguyên tố, tức là một trong các chữ số 2, 3, 5 và 7 (hình 6), bằng $4/10 = 2/5$.

Tương tự như vậy, khi nói về một điểm ngẫu nhiên trong hình vuông hoặc hình khác có diện tích $S$, chúng ta sẽ giả sử rằng xác suất xuất hiện của nó trong mỗi vùng diện tích $s$ là bằng $s/S$. Lưu ý rằng các quy tắc (1), (2) và (3) được thỏa mãn cho cả độ dài trên đoạn thẳng và diện tích của hình.

Điều đáng chú ý là việc chọn độc lập nhau hai số $x$ và $y$ trên đoạn [0; 1], chúng ta có thể giả sử rằng $(x, y)$ là tọa độ của một điểm ngẫu nhiên trong một hình vuông đơn vị: tương tự với công thức tích (4), xác suất một điểm $(x, y)$ rơi vào hình chữ nhật từ cạnh $a$ và $b$, song song với trục $Ox$ và $Oy$, bằng tích $ab$, tức là diện tích của hình chữ nhật này.

Ví dụ: xác suất để một số ngẫu nhiên được chọn trên khoảng [0; 1], nằm ở khoảng cách không quá 0,1 tính từ giữa đoạn, bằng 0,2 (các điểm đó bao phủ đoạn từ 0,4 đến 0,6). Nếu $x$ và $y$ là hai số ngẫu nhiên trên khoảng [0; 1], xác suất để cả hai cách không quá 0,1 tính từ giữa là $0,2^2 = 0,04$, và xác suất để ít nhất một trong số chúng cách không quá 0,1 tính từ giữa là 0,36 (hình 7); xác suất này có thể được tìm thấy bằng cách cộng các diện tích của các hình chữ nhật tạo nên “chữ thập” hoặc bạn có thể bằng cách chuyển đến “sự kiện bổ sung”, sử dụng công thức $(1 - 0,8^2)$.

Bây giờ chúng ta có thể quyết định và bài toán về cuộc họp được hình thành ở đầu bài viết. Hãy làm rõ nó như sau. Chúng ta sẽ giả sử rằng mỗi người bạn đến vào một thời điểm ngẫu nhiên nào đó được chọn trong khoảng [0; 45] (trong 45 phút đầu tiên của giờ có điều kiện) đợi thêm 15 phút; Vì vậy, họ sẽ gặp nhau nếu chênh lệch giữa thời điểm $x$ và $y$ (modulo) của họ không vượt quá 15.

Chúng ta hãy vẽ trên hình vuông $0 \leq x \leq 45$, $0 \leq y \leq 45$ tập hợp các điểm $(x, y)$, trong đó $|x - y| \leq 15$ - nó được giới hạn bởi các đường thẳng $y - x = 15$ và $y - x = -15$, song song với đường chéo $x = y$ (hình 8). Diện tích của bộ này bằng $45^2 - 30^2$ (hai hình tam giác màu trắng cùng nhau tạo thành một hình vuông có cạnh 30) và xác suất mong muốn bằng tỷ lệ của nó với diện tích của toàn bộ hình vuông $45 \times 45$:

$$1 - \frac{30^2}{45^2} = 1 - \left(\frac{2}{3}\right)^2 = \frac{5}{9}.$$

Hãy giải bài toán khác về một điểm ngẫu nhiên $(x, y)$.

Bài toán 4. Tìm xác suất $p = p(a)$ để tổng bằng $x + y$, trong đó $x, y$ là các số ngẫu nhiên trên khoảng [0; 1], lớn hơn số đã cho $a$.

Phương trình $x + y = a$ xác định một đường thẳng song song với đường chéo $x + y = 1$ của hình vuông. Xác suất cần thiết là diện tích của phần hình vuông nằm phía trên đường này. (Đối với $a > 1$ nó là một hình tam giác, đối với $a < 1$ nó là một gót chân và việc tính diện tích bổ sung sẽ dễ dàng hơn.) Đáp số được viết như sau:

$$p = \begin{cases} (2 - a)^2 / 2 \text{ при } a \geq 1, \\ 1 - a^2 / 2 \text{ при } a \leq 1. \end{cases}$$

⟦folio 51⟧

---
running_head:
folio:
---

Thông điệp đối xứng
Điểm trên đường tròn

Lưu ý rằng với $a=1$ ở bài toán trước đó, chúng ta nhận được đáp số $p=1/2$.
(Các điểm tương ứng $(x, y)$ nằm phía trên đường chéo.) Có thể đoán ngay mà không cần có mẫu hình trên hình vuông: nếu $x, y$ là các số được chọn ngẫu nhiên trên khoảng [0; 1], thì điều kiện $x+y \leq 1$ có thể được viết thành $x \leq 1-y$ và đọc như sau: “x gần 0 hơn $y$ gần 1”. Rõ ràng là điều kiện bổ sung có được chỉ bằng cách thay thế $x$ bằng $y$ và có cùng tính hợp lý: xét cho cùng, vai trò của $x$ và $y$, cũng như các đầu của đoạn đường đều cạnh hoàn hảo.

Đây là một ví dụ khác.

Bài toán 5. Trên đoạn [0; 1] trường hợp, ba số được chọn. Xác suất để $a$ được chọn làm số cuối cùng là lớn nhất là bao nhiêu? b) các số có theo thứ tự tăng dần không?

Ở đây, quyết định không phải về hai, mà là về ba số $x, y, z$. Bộ ba $(x, y, z)$ có thể được coi là tọa độ của một điểm trong khối lập phương và có thể tính được thể tích của các bộ cần thiết. Nhưng điều này là không cần thiết. Xét cho cùng, rõ ràng là cả 6 phương án sắp xếp ba số: $x<y<z, y<x<z, x<z<y, y<z<x, z<x<y, z<y<x$ đều có xác suất hoàn toàn bằng nhau và có cùng xác suất là 1/6. Như vậy, đáp số cho câu hỏi 6) là 1/6, và cho câu hỏi a) 1/3 (được trả lời bằng hai phương án đầu tiên).

Bây giờ chúng ta hãy giải bài toán về tam giác nhọn được xây dựng ở đầu bài viết. Rõ ràng là với bất kỳ vòng quay nào của vòng tròn, xác suất của các sự kiện và các điều kiện về “độ sắc nét” đều được bảo toàn; vì vậy chúng ta có thể giả sử rằng một trong ba đỉnh được chọn $A, B, C$—chẳng hạn như $C$—là cố định và hai đỉnh còn lại đã được chọn ngẫu nhiên. Chúng ta sẽ đặt vị trí độ lớn của chúng theo từng $CA=\alpha, CB=\beta$, đếm ngược chiều kim đồng hồ. Hãy thay đổi các góc theo radian, khi đó cặp $(\alpha, \beta)$ là một điểm trong hình vuông $0<\alpha<2\pi, 0<\beta<2\pi$. Theo định lý độ lớn của góc nội tiếp thay đổi theo cung dương giữa các cạnh của nó thì các góc của tam giác $ABC$ bằng $\pi-\beta/2, \alpha/2$ và $(\beta-\alpha)/2$ (ta giả sử rằng $\beta>\alpha$ (hình 9); trường hợp $\alpha>\beta$ hoàn toàn tương tự - $\alpha$ và $\beta$ đổi vai trò). Các điểm $(\alpha, \beta)$ trong tam giác $\alpha<\beta<2\pi$, có cả ba góc $A, B, C$ đều nhỏ hơn $\pi/2$, tức là $\beta>\pi, \alpha<\pi$ và $\beta-\alpha<\pi$, lấp đầy phần bên trong của tam giác nhỏ hơn, được tạo thành bởi các đường giữa của tam giác lớn hơn (hình 10). Tình huống trong tam giác dưới $\beta<\alpha<2\pi$ đối xứng với đường chéo $\alpha=\beta$ của hình vuông. Do đó, độ tin cậy cần thiết là 1/4.

bài toán này có lời giải đẹp tuyệt vời khác, cho phép bạn giải bài toán tương tự cho điểm $n$ (xem bài toán 9 ở cuối); chúng tôi đã học được điều đó từ nhà vật lý V.V. Fok và nhà toán học Yu.V. Chekanov.

Chúng ta sẽ tìm kiếm sự tin cậy bổ sung rằng ba điểm $A, B, C$ là các đỉnh của một tam giác tù.

Đối với mỗi điểm $M$ của đường tròn, hãy xét điểm $M'$ đối diện theo đường kính với nó và thu được đường tròn mà $M'$ đóng vai trò là điểm giữa của cung. Bộ ba $A, B, C$ là “cù” khi và chỉ nếu các hình bán nguyệt tương ứng với các điểm $A, B$ và $C$ tái hiện

⟦folio 52⟧

---
running_head:
folio:
---

cắt dọc theo một khu vực nhất định (hình 11). (Đối với mỗi bán kính OD trong khu vực đã chọn, tất cả các góc DOA, DOB, DOC đều là tula; bán kính OD như vậy tồn tại nếu A, B, C nằm trên cùng một hình bán nguyệt hoặc tương đương, tạo thành một tam giác “ngủ”.)

Chúng tôi sẽ chọn điểm ngẫu nhiên trong hai giai đoạn. Đầu tiên, chúng ta đánh dấu ngẫu nhiên ba cặp điểm có đường kính đối xứng và vẽ đường kính đối xứng cho mỗi cặp. Và sau đó trong mỗi cặp, chúng tôi chọn độc lập (với xác suất là 1/2) một trong các điểm. Hãy để chúng tôi chứng minh rằng từ 8 phương án chọn điểm, có chính xác 6 sẽ tạo ra một rãnh A, B, C "cùn". Trên thực tế, ba đường kính chia vòng tròn thành 6 phần và mỗi cung có thể thu được là giao điểm của ba hình bán nguyệt cụ thể tương ứng với một số điểm A, B, C nhất định. Vì vậy, xác suất để có được một rãnh "cù" là 6/8 = 3/4, nghĩa là xác suất bổ sung bằng 1/4.

vấn đề của Buffon

Chúng ta đã quen với thực tế rằng độ tin cậy luôn là một phân số có các số nguyên nhỏ ở tử số và mẫu số. Nhưng để kết luận, chúng tôi trình bày hai bài toán, trong đó số π xuất hiện trong đáp số. Cái đầu tiên gần như rất inda.

Bài 6. Một dấu chấm được ném ngẫu nhiên lên một tờ giấy ca-rô lớn ở cạnh ô 1. Xác suất để chấm đó nằm trên đó là bao nhiêu?

Hình 11.

khoảng cách nhỏ hơn 1/2 tính từ tâm của một ô nào đó?

Nó là đủ để xem xét một tế bào. Các điểm nằm cách tâm không quá 1/2 sẽ lấp đầy một vòng tròn có diện tích π/4. Đây là đáp số: xác suất cần thiết (tỷ lệ giữa diện tích hình tròn và diện tích ô) bằng π/4.

Vấn đề 7 (Vấn đề về kim tiêm của Buffon)

MÁY BAY ĐƯỢC DÀNH THÀNH CÁC SỌC CÓ CHIỀU RỘNG 1. Toàn bộ (đoạn) có chiều dài 1 được ném lên nó. Xác suất để toàn bộ sẽ vượt qua một trong các dòng là gì?

bài toán này có một điều đáng kinh ngạc đáp số: 2/π. π đến từ đâu nếu trong điều kiện không nói đến đường tròn hay khoảng cách?

Chúng ta hãy phác thảo ngắn gọn một trong lời giải. Vị trí của kim (nếu chúng ta không nói đến việc trộn nó dọc theo các đường, điều này không thực sự đóng vai trò gì) được xác định bởi hai tham số: khoảng cách y của đầu kim từ mép trên của dải mà nó chạm 0<y<1, và góc α của kim với đường thẳng vuông góc với các đường (hình 12, a). Theo thông điệp đối xứng, chúng ta có thể giả sử rằng α<π/2. Điều kiện để kim đi qua mép dải: y<cos α. Vì vậy, trong số các điểm (α, y) thuộc đường thẳng 0<α<π/2, 0<y<1 ta phải chọn các đường thẳng y=cos α (hình 12, b) nằm bên dưới và tìm tỉ số giữa diện tích S của hình thu được với diện tích của đường thẳng (π/2). Đối với những người đã quen thuộc với khoảng dễ hiểu (họ học nó ở trường trung học), bài toán này không khó: ∫_{0}^{\pi/2} cos α dα=1. Nhưng bạn có thể nhận được đáp số dựa trên sự tương tự từ cơ học. Hãy tưởng tượng một điểm, đều với vận tốc đơn vị, đi qua cung AB trên 1/4 đường tròn bán kính 1 (hình 12, s). Khi điểm M ở vị trí α trên cung (0<α<π/2), tốc độ hình chiếu M' của nó lên bán kính OB đúng bằng cos α. Vậy hình 12, b là đồ thị tốc độ của điểm M' và diện tích S bên dưới đồ thị bằng hình chiếu của đường đi, tức là S=OB=1.
