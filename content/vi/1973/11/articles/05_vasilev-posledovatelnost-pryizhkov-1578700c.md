---
id: 1973-11-vasilev-posledovatelnost-pryizhkov-1578700c
issue: kvant_1973_11
year: 1973
number: "11"
title: Trình tự nhảy
authors:
  - Васильев Н. Б.
rubric: osnovnye-stati
page_first: 27
page_last: 33
page_labels: 25-31
tag: HGEZ
lang: vi
source: kvant_digital
extraction: vision
content_sha256: 1f3f7216e411e6f8541f634f41fbcc344ddf19e8fbc51bcb977969cc1c41a408
prompt_sha256: draft-1
translated_from: content/ru/1973/11/articles/05_vasilev-posledovatelnost-pryizhkov-1578700c.md
source_content_sha256: 4405c05b41b17c1840994f3f2b4d7c3c15285448a1625dcba24e4d2d9dbd0a25
translation_model: draft
translation_run: vi-draft-2026-10-31
translation_quality: draft
---

⟦folio 25⟧

Trình tự nhảy

Trong phần ghi chú này, chúng ta sẽ giải bài toán M190 từ “Bài toán lượng tử” - bài toán về một con cá xanh nhảy dọc theo hai đường thẳng. Nó có thể được giải quyết theo những cách khác nhau. Chúng ta sẽ rút gọn bài toán này thành câu hỏi sau: một đường đi được cho bởi hai hoặc nhiều chuyển động của mặt phẳng để lại một điểm O cho trước cố định (đây có thể là phép quay hoặc đối xứng); Phép biến đổi nào của mặt phẳng sẽ thu được nếu các phép biến đổi này được thực hiện tuần tự lần lượt?

Vì bản thân câu hỏi này rất thú vị và không chỉ liên quan đến giải pháp bài toán về nhạc blues, nên đôi khi chúng tôi sẽ đi chệch hướng và đưa ra các bài tập không liên quan trực tiếp đến bài toán M190.

Đầu tiên, hãy nhớ lại công thức của bài toán.

Cho hai đường thẳng a và b cắt nhau trên mặt phẳng. Tại điểm A₀, nằm trên đường a và cách đường b ít hơn 1, màu xanh mờ. Sau đó, cá xanh tuần tự nhảy đến các điểm B₀, A₁, B₁, A₂, B₂, ..., được hướng dẫn theo các quy tắc sau (Hình 1):

1) các điểm A₀, A₁, A₂, ... nằm trên đường thẳng a, các điểm B₀, B₁, B₂, ... nằm trên đường thẳng b;

2) A₀B₀ = B₀A₁ = A₁B₁ = =B₁A₂ = A₂B₂ = ... = 1;

3) điểm Aₙ+1 không trùng với Aₙ, ngoại trừ trường hợp A_rB_n ⊥ a (và tương tự, Bₙ+1 chỉ trùng với Bₙ nếu BₙAₙ+1 ⊥ b).

(Điều kiện 1) - 3) trình tự các bước nhảy được xác định duy nhất.)

Chứng minh rằng nếu các đường thẳng a và b thay đổi một số hữu tỉ thì đường đi của chim xanh sẽ tuần hoàn, tức là tại một thời điểm nào đó nó sẽ đến điểm ban đầu A₀ và sau đó lần lượt đi qua các điểm B₀, A₁, B₁, ..., như lúc bắt đầu đường đi; và nếu là số vô tỷ thì màu xanh sẽ không đạt điểm nào quá hai lần.

Tất nhiên, thật thú vị khi hiểu không chỉ đường đi của chim xanh có “theo chu kỳ” hay không mà còn phải hiểu một cách tổng thể chuỗi các điểm A₀, B₀, A₁, B₁, ..., (1) được cấu trúc như thế nào

ví dụ: học cách xác định vị trí của các điểm Aₙ và Bₙ theo số n. Trong lời giải, chúng tôi cũng sẽ nhận được đáp số cho câu hỏi này. Trong tương lai, cùng với từ “blukha” chúng ta sẽ thường xuyên sử dụng từ “điểm”.

Hình 1.

⟦folio 26⟧

1. Một điểm nhảy dọc theo hai đường thẳng
Việc bắt đầu bằng một thử nghiệm là điều tự nhiên:
vẽ hai đường thẳng, trang bị cho mình một vòng tròn (thậm chí tiện lợi hơn là mét) và lấy một điểm nào đó $A_0$ làm điểm bắt đầu, xem “quỹ đạo” của đồ thị trông như thế nào. Một ví dụ như vậy được xây dựng trong Hình 1: các điểm $A_0$, $B_0$, $A_1$, $B_1$, ... được kết nối tuần tự bằng các đoạn màu đỏ và đầu (có mũi tên) chỉ đường dẫn của lỗi. Bạn có thể lặp lại thí nghiệm này bằng cách chụp một góc khác giữa các đường thẳng hoặc một điểm bắt đầu khác. Sau nhiều lần trì hoãn, rõ ràng là các điểm $A_n$ (và $B_n$) rơi về một bên hoặc về phía bên kia của giao điểm $K$ của các đường $a$ và $b$. Đúng, không có tính định kỳ nghiêm ngặt ở đây:
ví dụ: trong Hình 1, đốm sáng xuất hiện trên mỗi tia có đỉnh $K$, đôi khi hai lần liên tiếp, đôi khi ba lần. Và tất nhiên, thử nghiệm không cho phép chúng tôi tìm hiểu xem blog sau vài bước có kết thúc ở điểm xuất phát hay không $A_0$: suy cho cùng, chúng tôi chỉ có thể thực hiện các công trình xây dựng bằng phép tính gần đúng, vì vậy từ hình vẽ, chúng tôi sẽ không thể nắm bắt được sự khác biệt giữa xấp xỉ hợp lý và xấp xỉ vô tỷ.

Hình 2.

Hình 3.

phế liệu. (Chỉ trường hợp góc đúng là rõ ngay; Hình 2.)

Không có hình vẽ bãi tập nào có thể gợi ý một mô hình xác định đường đi của kẻ bắt nạt đơn giản hơn quy tắc 1) - 3), được hình thành trong điều kiện bài toán.

2. Hướng nhảy
Các liên kết liên tiếp của đường đứt nét - quỹ đạo của đồ thị - là các vectơ có độ dài đơn vị

$\vec{A}_0\vec{B}_0, \vec{B}_0\vec{A}_1, \vec{A}_1\vec{B}_1, \vec{B}_1\vec{A}_2, \dots$ (2)
(Mỗi vectơ hiển thị bước nhảy tiếp theo là gì.)

Lưu ý rằng nếu chúng ta biết vectơ $\vec{u} = A_n\vec{B}_n$ (hãy vẽ nó ở đâu đó sang một bên, trên mặt phẳng), thì chúng ta có thể xác định được điểm $A_n$ và $B_n$ nằm ở đâu.

Thật vậy, bổ đề này là đúng. Đặt $a$ và $b$ là các đường giao nhau. Với bất kỳ vectơ $\vec{u}$ (trên mặt phẳng) sẽ tìm thấy hai điểm $A$ (trên đường thẳng $a$) và $B$ (trên đường thẳng $b$) thì vectơ $\vec{AB}$ cũng bằng vectơ đã cho $\vec{u}$. Điểm $A$ và $B$ được xác định duy nhất.

Chứng minh (Hình 3). Nếu chúng ta muốn phần đầu của vectơ nằm trên đường thẳng $a$ và vectơ này bằng $\vec{u}$ thì phần cuối của vectơ phải nằm trên đường thẳng $a'$, thu được bằng cách chuyển song song đường thẳng $a$ sang vectơ $\vec{u}$ (trong Hình 3, đường thẳng $a'$ được vẽ bằng một đường chấm). Do đó, điểm $B$ phải nằm tại giao điểm của đường $b$ với đường $a'$. Sau đó, điểm $A$ dễ dàng được tìm thấy.

Razzhene 1. Cho hai điểm $C$ và $D$ và hai đường thẳng $a$ và $b$. Tìm trên các đường $a$ và $b$ các điểm tương ứng $A$ và $B$ sao cho đoạn 們 của các đoạn $AC$ và $BD$ trùng nhau; b) tứ giác $ABCD$ là một hình thang có đáy $AB$ gấp đôi đáy $CD$.

Lấy một điểm $O$ trên mặt phẳng và đặt tất cả các vectơ của dãy là

⟦folio 27⟧

Hình 4.

(2) hoãn lại từ thời điểm này. Chúng ta ký hiệu các vectơ này bằng sự tương ứng của vectơ dãy (2), như sau:

$$\overrightarrow{OC_0}, \overrightarrow{OD_0}, \overrightarrow{OC_1}, \overrightarrow{OD_1}, \dots$$

(3) Từ bổ đề suy ra rằng, biết dãy (3), chúng ta có thể sử dụng dãy các điểm (1):

ví dụ: biết $\overrightarrow{OC_n}$, người ta có thể tìm thấy cả $A_n$ và $B_n$.

Hình 4 hiển thị “hướng khóa” (3) cho chuỗi hiển thị trong Hình 1. Lưu ý rằng các vectơ màu đỏ $\overrightarrow{OC_n}$ (tương ứng với các khóa từ dòng $a$ đến dòng $b$; $n = 0, 1, 2, \dots$) tạo thành các góc bằng nhau. Hóa ra đây là một thực tế chung và đúng với bất kỳ chuỗi khóa nào. Chúng ta hãy phát biểu nó dưới dạng một định lý.

Định lý. Nếu giá trị giữa các dòng $a$ và $b$ bằng $\gamma$ thì giá trị giữa

giữa các vectơ $\overrightarrow{OC_n}$ và $\overrightarrow{OC_{n+1}}$ bằng $2\gamma$.

Đây là thông điệp chính trong bài toán M190. Định lý có thể được chứng minh bằng cách sử dụng thực tế là hai đường liền kề bất kỳ của đường đứt nét theo dãy (2) là các cạnh bên của một tam giác cân và đáy của tam giác này lần lượt nằm trên đường thẳng $a$ hoặc trên đường thẳng $b$. Khó khăn chính trong việc chứng minh mối liên hệ là các mắt xích của một đường đứt nét có thể được định vị khác so với các đường thẳng đã cho. Ví dụ, để chứng minh định lý cho $\gamma = 60^\circ$, người ta sẽ phải xét 10 giá trị ngẫu nhiên như trong Hình 5 (các giá trị còn lại dương tính đối xứng tại giao điểm của các đường $a$ và $b$). Chúng ta sẽ làm khác đi: sử dụng khái niệm “biến đổi” và “tích của phép biến đổi”, chúng ta sẽ đưa ra một chứng minh tổng quát bao gồm tất cả các trường hợp cùng một lúc.

⟦folio 28⟧

3. Điểm nhảy quanh vòng tròn

Chúng ta hãy so sánh Hình 1 và Hình 4 một lần nữa. Chúng ta hãy chọn từ chúng những đoạn bao gồm hai liên kết liên tiếp (“tam giác đùi phải” giống nhau đã thảo luận ở trên; Hình 6, a, b và 7, a, b). Nhìn vào những hình ảnh này, có thể dễ dàng hình thành một quy tắc đơn giản để xây dựng chuỗi (3).

Ta ký hiệu bằng $p$ và $q$ các đường thẳng đi qua điểm $O$ và song song với các đường thẳng tương ứng $a$ và $b$; sau đó theo thứ tự (3)

sau vectơ $OC_n$ có vectơ $OD_n$, đối xứng với nó so với đường thẳng $p$; sau vectơ $OD_n$ có một vectơ $OC_{n+1}$, đối xứng với nó qua đường thẳng $q$ (ở đây $n = 0, 1, 2, \dots$).

Độ pha loãng Y 2. Kiểm tra xem quy tắc này có tương ứng chính xác với quy tắc 1)—3) trong các điều kiện bài toán (bao gồm cả trong “biểu thức” của trường hợp).

Phần mở rộng 3. a) Chứng minh rằng nếu dãy số (1) chạm điểm $A_0$ nhiều hơn hai lần thì nó sẽ là một dấu chấm và một số điểm $C_n$ trùng với $C_0$.

6) Cho ví dụ khi chuỗi chạm điểm $A_0$ hai lần: $A_1$ khớp với $A_0$, nhưng $B_1$ không còn khớp với $B_0$.

Bạn có thể e. Đối với một điểm $A$ trên đường thẳng $a$ có nhiều nhất hai vectơ bắt đầu tại $A$, kết thúc trên đường thẳng $b$ và có độ dài bằng 1.

Bây giờ chúng ta hãy hình thành lại bài toán M190 (hay đúng hơn là bài toán đã được giảm xuống), nhưng chúng ta sẽ không nói về sự biến đổi của tori $OC_n$ và $OD_n$ thành ai đó, mà là về sự biến đổi của các đầu của chúng - các điểm nằm trên vòng tròn đơn vị.

Giả sử $p$ và $q$ là hai đường thẳng đi qua điểm $O$. Chúng ta hãy biểu thị bằng $S_p$ phép biến đổi của đường tương đối đối xứng $p$ và bằng $S_q$ phép biến đổi của đường tương đối đối xứng $q$. (Chúng ta có thể coi những phép biến đổi này là phép biến đổi của tất cả các mặt phẳng lên chính chúng; ví dụ: $S_p$ gán cho mỗi điểm $X$ điểm $S_p(X)$, đối xứng với điểm $X$ so với đường thẳng $p$. Nhưng trong tương lai, chúng ta sẽ cần xem xét các điểm trên đường tròn đơn vị có tâm $O$. Rõ ràng là các phép biến đổi $S_p$ và $S_q$ ánh xạ vòng tròn đơn vị lên chính nó.) Giả sử $C_0$ là một điểm nào đó nằm ở khoảng cách 1 với $O$ và

$$C_0, D_0, C_1, D_1, C_2, D_2, \dots$$

- trình tự xác định theo điều kiện

$$D_n = S_p(C_n), C_{n+1} = S_q(D_n)$$

(Hình 8). Chúng ta phải chứng minh rằng điểm $C_n$ với neokotrom $n$ trùng với $C_0$ khi và chỉ khi góc $\gamma$ giữa các đường thẳng $p$ và $q$ được biểu thị bằng một số độ hợp lý.

Vì vậy, bài toán về việc nhảy dọc theo hai đường thẳng đã giảm xuống còn bài toán về việc nhảy dọc theo một vòng tròn.

Và định lý mà trước hết chúng ta phải chứng minh

⟦folio 29⟧

khẳng định rằng $C_n C_{n+1} = 2\gamma$. trong đó $\gamma$ là góc giữa $p$ và $q$.

4. Sản phẩm chuyển đổi

Quy tắc chuyển tiếp (5) của chúng tôi sẽ được đơn giản hóa hơn nữa nếu chúng tôi kết hợp hai lần nhảy liên tiếp thành một: theo trình tự

$$C_0, C_1, C_2, \dots$$

(6)

mỗi điểm tiếp theo được lấy từ điểm trước theo quy tắc sau:

$$C_{n+1} = S_q (S_p (C_n))$$

(7)

nghĩa là, bạn cần áp dụng $S_p$ cho $C_n$, sau đó đến điểm kết quả $-S_q$.

Về giới hạn. Đặt $K$ và $L$ là hai phép biến đổi của tập hợp $M$ lên chính nó. Tích của phép biến đổi $K$ và $L$ được gọi là phép biến đổi $R$, phép biến đổi này gán điểm $X$ từ $M$ đến điểm $L(K(X))$.

Do đó, tích của phép biến đổi $K$ và $L$ chỉ đơn giản là kết quả của việc thực hiện hai phép biến đổi một cách tuần tự: đầu tiên là $K$ và sau đó là $L$. Sản phẩm $R$ có nghĩa là: $R = L \cdot K$. Viết $K$ và $L$ theo đúng thứ tự này (“từ phải sang trái”) sẽ thuận tiện ở chỗ đối với bất kỳ điểm nào $X$ đẳng thức giữ nguyên:

$$R(X) = L \cdot K(X) = L(K(X))$$

(8)

Chúng tôi đã làm rõ cụ thể thứ tự viết các “thừa số”, bởi vì để nhân một phép biến đổi, nói chung, đẳng thức $L \cdot K = K \cdot L$ không giữ được (xem Bài tập 4 bên dưới).

Tích của ba và một số biến đổi lớn được xác định theo cách tương tự: $R = R_1 \cdot R_2 \cdot R_3$ có nghĩa là bạn cần thực hiện $R_3$ trước, sau đó là $R_2$, sau đó là $R_1$. Cuối cùng, ký hiệu $R = (R_1)^n$ có nghĩa là $R$ là kết quả của việc áp dụng phép biến đổi $R_1$ $n$ lần.

Chúng ta hãy quay lại $S_p$ và $S_q$ - các phép biến đổi đối xứng của chúng ta đối với các đường thẳng $p$ và $q$. Sản phẩm của họ sẽ là gì? (Bây giờ sẽ thuận tiện hơn cho chúng ta khi giả sử rằng $S_p$ và $S_q$ là các phép biến đổi vào mặt phẳng của chính chúng.) Rõ ràng là điểm $O$ vẫn giữ nguyên dưới phép biến đổi $S_q \circ S_p$: nó đi vào chính nó cả dưới phép biến đổi $S_p$ và dưới phép biến đổi $S_q$. Điều gì xảy ra với số điểm còn lại?

Sự chuyển đổi này có thể được biểu diễn trực quan như sau. Trong quá trình biến đổi $S_p$, mặt phẳng luôn bị lật quanh đường thẳng $p$ và được “phía bên kia” chồng lên chính nó. Sau phép biến đổi thứ hai $S_q$ - đối xứng so với đường thẳng $q$ - mặt phẳng lại được chuyển sang phía chuyển tiếp. Rõ ràng rằng chuyển động của một mặt phẳng có điểm cố định $O$ và không làm thay đổi “hướng” của mặt phẳng (không làm mặt phẳng chuyển động sang phía bên kia) chỉ có thể là chuyển động quay quanh điểm $O$. Do đó, $R = S_q \circ S_p$ là phép quay của mặt phẳng một góc nào đó xung quanh điểm $O$. Chính xác là ở góc độ nào? Để trả lời câu hỏi này, chỉ cần lấy một điểm và xem điều gì sẽ xảy ra với nó là đủ. Đặt góc từ đường thẳng $p$ đến đường thẳng $q$ bằng $\gamma$ (chúng ta sẽ đếm các góc ngược chiều kim đồng hồ). Hãy lấy điểm $E$ trên dòng $p$ (Hình 9) và tìm $R(E)$. Rõ ràng $S_p(E) = E$: điểm nào của đường $p$ biến thành chính nó dưới phép biến đổi $S_p$. Và khi đó điểm $E$ nằm trên một đường thẳng, đối xứng với đường thẳng $p$ so với đường thẳng $q$, tức là bề mặt xung quanh điểm $O$ một góc $2\gamma$. Vì vậy, nếu góc từ $p$ đến $q$ bằng $\gamma$ thì $R = S_q \circ S_p$ là phép quay qua góc $2\gamma$. Điều này dẫn đến định lý chính của chúng tôi:

$$\cup C_n C_{n+1} = 2\gamma.$$

⟦folio 30⟧

Hình 10.

Lực căng 4. Đảm bảo rằng phép biến đổi $S_p \circ S_q$ là phép quay theo góc $(-2\gamma)$, tức là phép quay $2\gamma$ theo chiều kim đồng hồ (xem tổng hợp trong Hình 4). Do đó, nếu góc $\gamma$ khác với góc 0 hoặc góc vuông thì $S_p \circ S_q \neq S_q \circ S_p$.

5. Ghi lại các phép quay và tính đối xứng của một vòng tròn

Có thể tính toán tích của biến đổi một cách hình thức. Để làm điều này, bạn cần phải nhập tọa độ. Vì chúng ta chỉ quan tâm đến các chuyển vị của mặt phẳng có điểm $O$ cho trước cố định, nên chúng ta có thể cùng với mặt phẳng đã biến đổi nói về ánh xạ của đường tròn đơn vị có tâm $O$ lên chính nó - về phép quay và sự đối xứng.

Hãy nhập tọa độ của hình tròn như thế này. Chúng ta hãy chọn phần đầu của báo cáo $E$—một trong những điểm giao nhau của đường thẳng $p$ với đường tròn đơn vị. Chúng ta gán cho mỗi điểm $X$ của đường tròn giá trị của góc $EOX$, tính từ $OE$ ngược chiều kim đồng hồ và được đo bằng độ (Hình 10); trong trường hợp này, điểm $X$ tương ứng với một tập hợp số

$$\varphi, \varphi \pm 360^\circ, \varphi \pm 2 \ 360^\circ, \dots$$

- một số khác nhau một bội số nguyên của $360^\circ$ tương ứng với cùng một điểm trên vòng tròn.

Lực căng 5. a) Phép biến đổi $S_p$ - tính đối xứng đối với đường thẳng $p$ - được tính theo công thức $S_p(\varphi) = -\varphi$.

6) Phép biến đổi $R^\alpha$—xoay theo góc $\alpha$ (ngược chiều kim đồng hồ)—được tính theo công thức $R^\alpha(\varphi) = \varphi + \alpha$.

b) Cho đường thẳng $q$ tạo một góc $\gamma$ với đường thẳng $p$. Chúng ta sẽ biểu thị thêm phép biến đổi $S_q$ bằng $S_\gamma$ để chỉ rõ góc mà đường thẳng $q$ tạo với đường thẳng “ban đầu” $p$. (Một phần, cùng với $S_p$ chúng ta sẽ viết $S_0$.) Sau đó

$$S_\gamma(\varphi) = 2\gamma - \varphi$$

Bình luận. Tất nhiên, $R^\alpha + 360^\circ = R^\alpha$ và $S_\gamma + 180^\circ = S_\gamma$ đối với bất kỳ số nguyên $n$ (góc mà đường thẳng $q$ tạo với đường thẳng $p$ được xác định bằng phép cộng bất kỳ bội số nào của $180^\circ$). Điều này hoàn toàn tương ứng với thực tế là $\varphi$ được xác định bằng phép cộng bội số nguyên của $360^\circ$.

Thì U 6. a) Chứng minh rằng $R^\gamma S_0 R^{-\gamma} = S_\gamma$. Ý nghĩa hình học của đẳng thức này là gì?

6) Chứng minh rằng $S_{\gamma_1} S_{\gamma_2} = R^{2\gamma_1 - 2\gamma_2}$ (do đó, một phần suy ra $S_0 S_\gamma = R^{-2\gamma}$ và $S_\gamma S_0 = R^{2\gamma}$)

b) Kiểm tra xem $R^\alpha R^\beta = R^\alpha + \beta$

d) Chứng minh rằng $S_\gamma R^\beta = S_\gamma - \frac{\beta}{2}$

d) Sản phẩm $R^\alpha S_\gamma$ là gì?

Hãy giải ví dụ bài toán g). Đặt điểm $X$ tương ứng với số $\varphi$. Khi đó điểm $S_\gamma^\circ R^\beta(X)$ ứng với số

$$S_\gamma\left(R^\beta(\varphi)\right) = S_\gamma(\varphi + \beta) = 2\gamma - (\varphi + \beta) = 2\left(\gamma - \frac{\beta}{2}\right) - \varphi.$$

tư thế, như chúng ta đã biết (bài tập 5 c)), $S_\gamma^\circ R^\beta = S_\gamma - \frac{\beta}{2}$.

Thì U 7. Chứng minh rằng a) $(R^\alpha)^n = R^\alpha n$

6) $(S_\gamma)^2 = I$, trong đó $I$ là phép biến đổi giống hệt nhau ($I$ giữ nguyên tất cả các điểm).

6. Kết thúc lời giải bài toán về bloxy

Vì vậy, chúng tôi phát hiện ra rằng theo chuỗi (6), mỗi điểm tiếp theo điểm trước đó bằng cách quay một góc $2\gamma$, trong đó $\gamma$ là góc giữa các đường thẳng $p$ và $q$. Do đó, $C_n$ thu được từ $C_0$ bằng cách xoay qua góc $2\gamma n$. Để $C_n$ và $C_0$ trùng nhau, điều cần thiết và đủ là góc quay phải là bội số nguyên của $360^\circ$. Rõ ràng là nếu

$$2\gamma n = 360^\circ k,$$ trong đó $k$ là số nguyên thì $\gamma$ thay đổi theo một số độ hợp lý. Ngược lại, nếu $\gamma = \frac{p}{q}$ độ thì với $n = 180^\circ q$ ta nhận được

$$2\gamma n = 360^\circ p,$$ trong đó $p$ là số nguyên, nên $C_n = C_0$.

⟦folio 31⟧

Hình 11.

Để kết luận, một lần nữa chúng tôi khuyên bạn nên cải thiện khả năng “nhảy, rẽ và đối xứng”.

7. Tập thể dục một chút

Mặc dù hầu hết các câu hỏi bên dưới được xây dựng cho các con số cụ thể, nhưng chúng tôi khuyên bạn nên cố gắng trả lời các câu hỏi phân tích ở dạng chung (đối với các giá trị tham số tùy ý). Nếu không thì cái này thậm chí còn đơn giản hơn.

8. Đặt góc $\gamma$ giữa các đường thẳng $a$ và $b$ bằng $60^\circ$ và góc của đoạn $A_0B_0$ với tia $KA_0$ là $7^\circ$. Đoạn $A_{100}B_{100}$ sẽ tạo với tia này một góc bằng bao nhiêu? Phân đoạn $B_{100}A_{101}$?

9. Đặt góc $\gamma$ bằng một radian và $KA_0=1$. Tìm xem điểm $A_{1973}$ thuộc tia $KA_0$ hay nằm ở nửa kia của đường thẳng $a$.

10. Chứng minh rằng chu kỳ quỹ đạo của khối (nhỏ nhất $n>1$ mà tại đó $A_n=A_0$) chỉ phụ thuộc vào góc $\gamma$ chứ không phụ thuộc vào điểm mà khối bắt đầu. Khoảng thời gian này bằng bao nhiêu nếu $\gamma=72^\circ$? Hãy thử kiểm tra sự thật này bằng “thực nghiệm”.

11. Hãy để $\gamma=37^\circ$. Hỏi các điểm của dãy $A_0, A_1, A_2$, ... xuất hiện bao nhiêu lần liên tiếp trên tia $KA_0$ (cho biết giá trị nhỏ nhất và nhỏ nhất)?

Nếu bạn muốn giải bài tập sau ở dạng tổng quát - về các mẫu trong một đường tròn - thì có thể bạn sẽ phải sử dụng lý thuyết nhỏ có trong bài tập 6 và 7. Theo mẫu, chúng tôi chỉ đơn giản muốn nói là một tập hợp không phụ của điểm $M$, bị cô lập bên trong đường tròn đơn vị: chúng ta có thể giả sử rằng đường tròn có màu trắng và đây là tập hợp
