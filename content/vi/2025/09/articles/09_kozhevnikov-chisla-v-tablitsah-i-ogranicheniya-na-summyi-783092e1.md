---
id: 2025-9-kozhevnikov-chisla-v-tablitsah-i-ogranicheniya-na-summyi-783092e1
issue: kvant_2025_9
year: 2025
number: "9"
title: Các số trong bảng và hạn chế về số lượng
authors:
  - Кожевников П. А.
rubric: zadachnik-kvanta
rubric_sub: Задачник «Кванта»
page_first: 36
page_last: 41
page_labels: 34, 35, 36, 38, 39
lang: vi
source: kvant_digital
extraction: vision
content_sha256: f1d8b585966bfa5ac324ae3d6fa5d0c9f422fbf892d9e39bf44632ae182b9558
prompt_sha256: draft-1
translated_from: content/ru/2025/09/articles/09_kozhevnikov-chisla-v-tablitsah-i-ogranicheniya-na-summyi-783092e1.md
source_content_sha256: ed3a8c266241ca34e8c204658c1b0845936411a4f31d87c25afed2df46a3ba47
translation_model: draft
translation_run: vi-draft-gaps-2026-11-04
translation_quality: draft
---

⟦folio 34⟧

---
running_head:
folio:
---

trong bảng
và hạn chế
cho số tiền

P.KOZHEVNIKOV

Mục đích của bài viết này là để nói về kỹ thuật thú vị được phát minh bởi nhà cổ điển thứ 11 đến từ Kazan, Arthur Abzalov, tại Olympic toàn Nga với lời giải khó bài toán 4 cho lớp 11 (bài toán này đã được đưa vào “Bài toán Kvant dưới số M2849). Trên thực tế, kỹ thuật này cho phép người ta giải bài toán tổng quát hơn nhiều bằng một công thức tương tự. Lời giải của Arthur tại Thế vận hội được đánh dấu bằng một lăng kính đặc biệt.

***

Hãy bắt đầu cuộc trò chuyện với “một chiều” đơn giản sau đây bài toán.

Nhiệm vụ 1a. Các đầu cuối của hình chữ nhật $1 \times 10$ phải được điền các số không âm không quá 5; trong trường hợp này, tổng các số trong bất kỳ hình chữ nhật $1 \times 3$ nào không được vượt quá 7. Chúng ta hãy tìm giá trị lớn nhất có thể có của tổng $S$ của tất cả các số.

Người đọc có thể tự giải bài toán hoặc tham khảo bài tập tiếp theo.

Bài tập 1. Cho các điều kiện bài toán 1a, đạt được giới hạn trên của $S$ bằng cách chia hình chữ nhật $1 \times 10$ thành các hình chữ nhật một cách thích hợp.

Bạn sẽ thích “lời giải” bài toán 1a tiếp theo như thế nào?

"Lời giải". Để tạo ra $S$ nhiều nhất, bạn cần tính tất cả các tổng trong hình chữ nhật $1 \times 3$ ở mức tối đa có thể, tức là bằng 7. Khi đó, sự sắp xếp của chúng ta phải là 3 tuần hoàn, tức là các ô cách nhau 3 ô (3 lần di chuyển đến ô liền kề) phải có cùng số. Vẫn còn khác biệt

⟦folio 35⟧

---
running_head:
folio:
---

hãy xem sự sắp xếp 3 kỳ, tức là sự sắp xếp có dạng $x, y, z, x, y, z, x, y, z, x,$ trong đó $x + y + z \leq 7$. Nhưng với cách sắp xếp này thì đã dễ hiểu rồi:
$$S = 4x + 3y + 3z \leq
\leq x + 3(x + y + z) \leq 5 + 3 \cdot 7 = 26.$$
Ví dụ: thu được $S = 26$ với $x = 5, y = 2, z = 0$.

Phần thứ hai trong “lời giải” đúng: nếu tất cả các tổng trong hình chữ nhật $1 \times 3$ bằng nhau thì sự sắp xếp là 3 tuần hoàn. Trên thực tế, cho một số cặp ô cách nhau 3 ô chứa các số $a$ và $d$, và để hai ô giữa chúng chứa các số $b$ và $c$, tức là có một đoạn $a, b, c, d$; thì từ điều kiện bằng nhau của các tổng $a + b + c = b + c + d$ nó dẫn đến $a = d$. Và sau đó với sự sắp xếp 3 kỳ, thật dễ dàng để tìm ra nó.

Nhưng với lý luận ban đầu (rút gọn về cách sắp xếp 3 tuần hoàn) chắc chắn có điều gì đó không ổn... Đầu tiên, hãy đưa ra một nhận xét mà lẽ ra chúng ta đã đặt ra: có rất nhiều cách sắp xếp 3 tuần hoàn trong đó tổng trong tất cả các hình chữ nhật $1 \times 3$ đều bằng 7, nhưng $S < 26$, và thậm chí cả một cách sắp xếp không tuần hoàn trong đó tổng của ba số liên tiếp bất kỳ có thể “thắng” trước cách sắp xếp đó có ít hơn 7 số. Và quan trọng nhất, cụm từ “PHẢI tính tất cả các tổng trong hình chữ nhật $1 \times 3$ tối đa có thể” chứa một lỗi thô: tính chu kỳ 3 không phải là điều kiện cần để đạt được giá trị tối đa $S = 26$. Trong bài tập tiếp theo, chúng tôi mời người đọc tìm các ví dụ liên quan.

Bài tập 2. Trong điều kiện bài toán 1a, cho ví dụ
a) Sắp xếp 3 kỳ, trong đó tổng của ba số liên tiếp bất kỳ là 7 và tổng tổng là $S = 21$;

6) sự sắp xếp không định kỳ trong đó $S = 23$ và tổng trong tất cả các hình chữ nhật $1 \times 3$ không vượt quá 6;
b) một thỏa thuận không định kỳ trong đó $S = 26$.

Vì vậy, trong “lời giải” đã cho có những lỗi toán học và việc sửa chúng dường như khó hơn việc giải bài toán 1a “từ đầu”. Nhân tiện, hiện tại, khi được yêu cầu đưa ra lời giải bài toán 1a, trí tuệ nhân tạo, nếu không đủ mạnh và được đào tạo, sẽ tạo ra những lý luận sai lầm, hơi giống với những lý luận được đưa ra trong “lời giải”.

Tuy nhiên, thực tế là trong các điều kiện bài toán 1a, trong số các cách sắp xếp có tổng lớn nhất $S$ thì bắt buộc phải tìm một đúng 3 kỳ. Bây giờ chúng ta sẽ chứng minh sự thật này trong một tình huống tổng quát hơn (xem bên dưới bài toán 1), nhưng quan trọng nhất, chúng ta sẽ không chỉ chứng minh điều đó mà còn học cách thu được một sự sắp xếp định kỳ từ một sự sắp xếp tùy ý theo một cách cụ thể mà không vi phạm các điều kiện bài toán và không làm giảm tổng số tiền $S$. Đây sẽ là nhịp độ do A. Abzalov đề xuất. Tất nhiên, bài toán 1 rất dễ giải nếu không có bước này (tương tự như bài tập 1), nhưng ngay sau đó với lời giải bài toán 2 và 3 càng khó, chúng ta có thể thực sự đánh giá cao tính hữu ích của bước này.

Bài 1. Cho các số tự nhiên $a \leq A$, $m$ và $s$ là số dương. Trong các ô của hình chữ nhật $1 \times A$ chúng ta phải xem xét các số không âm không vượt quá $m$. Chúng tôi gọi một thỏa thuận là được chấp nhận nếu tổng các số trong bất kỳ hình chữ nhật nào $1 \times a$ không vượt quá $s$. Hãy tìm giá trị lớn nhất của tổng $S$ của tất cả các số trong cách sắp xếp được chấp nhận.

Bổ đề 1. Trong cách sắp xếp chấp nhận được này, chúng ta thấy một số số liên tiếp có tổng lớn nhất. Teger thay thế sự sắp xếp ban đầu như thế này: để lại những thứ này

$$A = 26, a = 5, m = 5, s = 11$$

Hình 1

⟦folio 36⟧

---
running_head:
folio:
---

một số liên tiếp ở vị trí của chúng,
các số còn lại là sorm và tiếp tục là sản phẩm-
bấm máy trái và phải với dấu chấm
độ dài a (ví dụ - tại hình 1). Sau đó:
1) sự sắp xếp mới đạt được có thể chấp nhận được;
2) tuy nhiên, tổng số tiền trong đó không phải là
khác với cách sắp xếp ban đầu.

Chứng minh Bổ đề 1. Cho các số vào
sự sắp xếp ban đầu được hình thành một cách tuần tự
x1, x2, ..., xA. Gọi các số được chọn là các số xk+1, xk+2, ..., xk+a và tổng của chúng bằng x. Vì thỏa thuận ban đầu được chấp nhận nên x  s.

1) Trong cách sắp xếp a-tuần hoàn mới, tổng các số trong bất kỳ hình chữ nhật 1×a nào sẽ bằng x, nghĩa là cách sắp xếp mới được chấp nhận.

2) Bây giờ hãy ước tính tổng số tiền trong cách sắp xếp mới. Hãy thực hiện riêng cho hình chữ nhật 1×k nằm ở bên trái của xk+1, ..., xk+a (đối với hình chữ nhật nằm ở bên phải, cách chứng minh tương tự). Trong cách sắp xếp ban đầu, các vị trí k+a đầu tiên chứa các số x1, x2, ..., xk+a. Chúng ta hãy ký hiệu y1, y2, ..., yk+a các số ở những vị trí này trong cách sắp xếp chu kỳ a mới (hình 2).

Chia k cho a có số dư: k = ta + r (0 ≤ r < a). Vì tổng x lớn nhất nên ta có

$$x_1 + \dots + x_a \leq x = y_1 + \dots + y_a$$
$$x_{a+1} + \dots + x_{2a} \leq x = y_{a+1} + \dots + y_{2a}$$
...,
$$x_{(t-1)a+1} + \dots + x_{ta} \leq x = y_{(t-1)a+1} + \dots + y_{ta}$$
$$x_{ta+1} + \dots + x_{ta+a} \leq x = y_{ta+1} + \dots + y_{ta+a}$$.

Trong đẳng thức cuối cùng, chúng tôi loại bỏ điểm yếu bằng nhau
xk+1 = yk+1, ..., xta+a = yta+a và sau đó chúng ta cộng tất cả các đẳng thức. Chúng tôi nhận được những gì chúng tôi cần:

$$x_1 + \dots + x_k \leq y_1 + \dots + y_k$$.

Bổ đề 1 đã được chứng minh.

Điều quan trọng nhất đã được thực hiện. Bây giờ chúng ta biết rằng với lời giải bài toán 1, chỉ cần phân tích cú pháp theo cách sắp xếp a-định kỳ là đủ. Trong các bài tập sau, chúng tôi đề xuất đảm bảo rằng việc này không hề khó khăn và đưa bài toán 1 đến đáp số cho các giá trị tham số cụ thể.

Bài tập 3. Trong bài toán 1, tìm giá trị lớn nhất của S tại A = 101, a = 7, m = 3, s = 10.

Trước khi chuyển sang cuộc trò chuyện “hai chiều”, chúng tôi cung cấp thêm hai bài tập không cần thiết nữa.

Bài tập

4. Chứng minh rằng chứng minh Bổ đề 1 sẽ có tác dụng nếu tổng xk+1 + ... + xk+a nghịch đảo nhất không phải trong số tất cả các tổng trên a của các số liên tiếp, mà chỉ trong số các tổng có dạng xk+1 + ... + xk+a, trong đó k ≡ 0 (mod a) hoặc k ≡ A (mod a).

5. đáp số sẽ thay đổi như thế nào trong bài toán 1 nếu tham số m và s được nhân đồng thời với λ > 0?

***

Hãy xây dựng phiên bản hai chiều bài toán - cho bảng A×B (hàng A, cột B; ở đây và bên dưới, với kích thước gợi ý, thứ tự sẽ luôn quan trọng, chẳng hạn như hình chữ nhật 2×3 và 3×2 được coi là khác nhau).

Bài toán 2. Cho a ≤ A, b ≤ B là số tự nhiên, a m và s là số dương. Trong các ô quan sát A×B, các số từ đoạn [0; m]. Một thỏa thuận được gọi là chấp nhận được nếu tổng các số trong bất kỳ ô vuông a×b nào không vượt quá s. Tìm giá trị lớn nhất có thể có của tổng S của tất cả các số trong ma trận được chấp nhận.

Bài toán 2 không khó nếu A∶a và B∶b, nhưng nhìn chung các trọng số

$$A = 26, a = 5, m = 5, s = 11$$

$$3 \quad 5 \quad 0 \quad 0 \quad 2 \quad 3 \quad 3 \quad 1 \quad 1 \quad 1 \quad 3 \quad 3 \quad 1 \quad 2 \quad 0 \quad 5 \quad 2 \quad 0 \quad 3 \quad 0 \quad 4 \quad 4 \quad 0 \quad 1 \quad 1 \quad 4$$
$$x_1 \quad x_2 \quad \dots \quad x_a \quad x_{a+1} \quad x_{a+2} \quad \dots \quad x_{2a} \quad \dots \quad x_{ta+1} \quad \dots \quad x_{k+1} \quad \dots \quad x_{ta+a} \quad \dots \quad x_k+a$$

Hình 2

⟦folio 38⟧

---
running_head:
folio:
---

Điều này hoàn toàn trùng khớp với phép biến đổi dãy mà chúng ta đã xem xét trong Bổ đề 1 “một chiều”! Điều này có nghĩa là chúng ta đã biết (từ chứng minh Bổ đề 1) rằng với phép biến đổi như vậy thì tổng $x_1 + x_2 + \ldots + x_B = S$ sẽ không giảm. Bổ đề 2 đã được chứng minh.

Vì vậy, bằng cách sử dụng Bổ đề 2, chúng ta đã chuyển sang một cách sắp xếp mới có thể chấp nhận được, đó là $b$-định kỳ theo chiều ngang. Với sự sắp xếp thu được, chúng ta thực hiện một bước “thẳng đứng” tương tự từ Bổ đề 2 và thu được một sự sắp xếp $a$-tuần hoàn theo chiều dọc. Tuy nhiên, dễ dàng nhận thấy, khi thực hiện bước thứ hai, tính tuần hoàn $b$ theo chiều ngang sẽ được giữ nguyên. Vì vậy, phần chính của lời giải bài toán 2 – rút gọn thành sắp xếp định kỳ $(a,b)$ – ​​đã diễn ra.

Vẫn còn phải tìm giá trị tối đa của tổng số tiền $S$ chỉ đối với các thỏa thuận được chấp nhận định kỳ $(a,b)$. Hãy xem một ví dụ với các giá trị tham số cụ thể (như trong hình 4) rằng điều này không hề khó khăn chút nào.

Ví dụ. Hãy để $A = 9, B = 11, a = 2, b = 3, m = 3, s = 10$.

Giả sử có một số $x_{11}, x_{12}, x_{13}, x_{21}, x_{22}, x_{23}$ tại giao điểm của hai hàng đầu tiên và ba cột đầu tiên, sau đó các số trong tất cả các ô được xác định dựa trên tính chu kỳ $(2,3)$. Chúng ta thấy rằng $x_{11}$ và $x_{12}$ xảy ra $5 \cdot 4 = 20$ lần trong bảng, $x_{13}$ xảy ra $5 \cdot 3 = 15$ lần, $x_{21}$ và $x_{22}$ xảy ra $4 \cdot 4 = 16$ lần, $x_{23}$ xảy ra $4 \cdot 3 = 12$ lần. Sau đó

$$S = 20x_{11} + 20x_{12} + 16x_{21} +$$

$$+ 16x_{22} + 15x_{13} + 12x_{23}.$$

(*)

$$A = 9, B = 11, a = 2, b = 3, m = 3, s = 10$$

Biểu thức này phải được tối đa hóa theo các ràng buộc $0 \leq x_{ij} \leq 3$ và $x_{11} + x_{12} + x_{13} + x_{21} + x_{22} + x_{23} \leq s = 10$. Điều này đã rõ ràng: tổng $s = 10$ phải được “phân phối”, phân tách theo thứ tự giá trị lớn nhất có thể có của các biến theo thứ tự giảm dần của các hệ số trong tổng (*). Cụ thể, trong trường hợp của chúng tôi, $S$ tối đa đạt được ở $x_{11} = x_{12} = 3, x_{13} = x_{23} = 0$ và $x_{21} + x_{22} = 4$ (việc 4 này được phân phối như thế nào giữa $x_{21}$ và $x_{22}$ không quan trọng, vì các hệ số trong tổng (*) đối với chúng bằng nhau; ví dụ: $x_{21} = x_{22} = 2$ hoặc $x_{21} = 3, x_{22} = 1$). Vậy giá trị tối đa của $S$ là 184.

Bài tập 8. Trong bài toán 2, cùng với phép biến đổi bảng từ Bổ đề 2, bạn có thể thử cách sau:

chọn hình chữ nhật $a \times b$ có tổng cao nhất và tiếp tục sắp xếp các số $(a,b)$-dấu, bắt đầu từ hình chữ nhật này. Cho ví dụ chứng tỏ phép biến đổi này có thể giảm tổng của $S$ (tức là phép biến đổi này không có tác dụng với lời giải).

***

Hãy tạo thành một bài toán ba chiều, tương tự như khoảng cách.

Bài 3. Cho $a \leq A, b \leq B, c \leq C$ là số tự nhiên, $a$ và $s$ là số dương. Trong các khối đơn vị song song với $A \times B \times C$, các số từ đoạn $[0; m]$ được xem xét. Một sự sắp xếp được gọi là chấp nhận được nếu tổng các số trong bất kỳ hình vuông song song nào $a \times b \times c$ không vượt quá $s$. Hãy tìm giá trị lớn nhất có thể có của tổng $S$ của tất cả các số trong khoảng cách cho phép.

Các bước tối ưu hóa tương tự như các bước trên sẽ giúp giảm sự sắp xếp tùy ý thành một từ định kỳ $(a,b,c)$. Bây giờ, để sắp xếp tuần hoàn theo một trong các hướng (giả sử hướng thẳng đứng - song song với cạnh $C$), hãy xem xét chuỗi tổng $x_1, x_2, \ldots, x_C$ theo lớp $A \times B \times 1$. Trong chuỗi này, chọn $c$ các số liên tiếp có tổng cao nhất. Bây giờ hãy thay thế cách sắp xếp ban đầu của các số như thế này: giữ nguyên tất cả các số trong vùng chọn -

⟦folio 39⟧

---
running_head:
folio:
---

các lớp và tiếp tục sắp xếp này $c$-theo định kỳ theo chiều dọc. Sau khi đã đạt được sự sắp xếp định kỳ theo một hướng, chúng ta lặp lại các bước cho các hướng khác. Do đó, cách tiếp cận này là một thỏa thuận được chấp nhận định kỳ $(a,b,c)$ trong đó tổng số tiền không nhỏ hơn số tiền trong thỏa thuận ban đầu. Người đọc có thể thực hiện lập luận một cách chi tiết và đảm bảo rằng kỹ thuật so sánh này giống như ở task 2.

Đối với việc sắp xếp định kỳ $(a,b,c)$ cho các giá trị tham số cụ thể lời giải bài toán 3 không còn khó khăn nữa. Cách lập luận sẽ tương tự như ví dụ đã xét ở nhiệm vụ 2. Tương tự, bài toán 3 được xây dựng và giải bài toán về việc sắp xếp các số trong mảng nhiều chiều.

Cuối cùng, rõ ràng là nhiệm vụ M2849 trùng với nhiệm vụ 3. Chúng ta hãy nhớ lại công thức ban đầu.

**M2849. Cho một số tự nhiên $N$. Một khối lập phương có cạnh $2N + 1$ bao gồm $(2N + 1)^3$ cốc đơn vị, mỗi cốc có màu đen hoặc trắng. Hóa ra trong số 8 cốc bất kỳ có một đỉnh chung và tạo thành hình lập phương $2 \times 2 \times 2$ thì không có quá 4 cốc đen. Có thể sử dụng tối đa bao nhiêu cốc đen?

Từ việc tô màu, chúng ta chuyển sang sắp xếp các số: viết số “0” vào cốc trắng, số “1” vào cốc đen. Điều này dẫn đến công thức sau:

Cho một số tự nhiên $N$. Trong các cốc đơn vị của khối lập phương $(2N + 1)^3$, các số 0 hoặc 1 được sắp xếp sao cho trong bất kỳ khối lập phương $2 \times 2 \times 2$ nào tổng các số không vượt quá 4. Tổng $S$ lớn nhất có thể có của tất cả các số là bao nhiêu?

Đây gần như là trường hợp đặc biệt của bài toán 3, với điểm khác biệt là ở nhiệm vụ 3 chúng ta đã cho phép sắp xếp các số thực từ một phân đoạn nhất định, nhưng ở đây – chỉ các số từ tập hữu hạn $\{0,1\}$. Nhưng về cơ bản, điều này không thay đổi bất cứ điều gì: nếu tập rời rạc $\{0,1\}$ được thay thế bằng phân đoạn $\{0;1\}$, thì lý do trong ước tính vẫn giữ nguyên và trong ví dụ tối ưu, các số vẫn sẽ là số nguyên: 0 hoặc 1.

Vì vậy, trong bài toán này, cũng như trong nhiệm vụ 3, chúng ta chỉ ra rằng giá trị lớn nhất $S$ chỉ có thể tìm được cho các sắp xếp tuần hoàn $(2,2,2)$. Vì lợi ích của khung vẽ, chúng ta hãy thực hiện lý luận đầy đủ với sự sắp xếp định kỳ $(2,2,2)$ và nhận được đáp số.

Đặt trong cách sắp xếp tuần hoàn $(2,2,2)$ trong cốc góc $2 \times 2 \times 2$ có giá trị bằng số $x_{ijk}$, trong đó $i, j, k$ là số lớp theo ba hướng, $i,j,k \in \{1,2\}$ (8 số này xác định hoàn toàn sự sắp xếp tuần hoàn $(2,2,2)$). Chúng ta thấy rằng $x_{111}$ xảy ra trong một khối lớn $(N + 1)^3$ lần, $x_{211}, x_{121}, x_{112}$ xảy ra $N(N + 1)^2$ lần, $x_{221}, x_{122}, x_{212} - \text{по } N^2(N + 1)$ lần và cuối cùng, $x_{222}$ xảy ra $N^3$ lần. Sau đó chúng ta tối đa hóa biểu thức tuyến tính

$$S = (N + 1)^3 x_{111} +$$

$$+ N(N + 1)^2 (x_{211} + x_{121} + x_{112}) +$$

$$+ N^2(N + 1)(x_{221} + x_{122} + x_{212}) + N^3x_{222}$$

theo các hạn chế nhất định: tất cả các biến đều thuộc phân đoạn $[0;1]$ và tổng của chúng không vượt quá 4. Các hệ số trong biểu thức này được sắp xếp như sau:

$$(N + 1)^3 > N(N + 1)^2 > N^2(N + 1) > N^3,$$

về mặt tư thế $S$ đạt giá trị tối đa

$$S = (N + 1)^3 + 3N(N + 1)^2$$

Tại

$$x_{111} = x_{211} = x_{112} = x_{121} = 1,$$

$$x_{221} = x_{122} = x_{212} = x_{222} = 0.$$

Nhiệm vụ lời giải.
