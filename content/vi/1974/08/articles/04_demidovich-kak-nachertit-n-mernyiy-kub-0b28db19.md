---
id: 1974-8-demidovich-kak-nachertit-n-mernyiy-kub-0b28db19
issue: kvant_1974_8
year: 1974
number: "8"
title: Làm thế nào để vẽ một khối lập phương n chiều?
authors:
  - Демидович Н. Б.
rubric: osnovnye-stati
page_first: 24
page_last: 28
page_labels: 22-26
tag: ATNJ
lang: vi
source: kvant_digital
extraction: vision
content_sha256: f8f8a501b6362ac979deb949b87021c827e3cf7b2b287056764f67021aa80677
prompt_sha256: draft-1
translated_from: content/ru/1974/08/articles/04_demidovich-kak-nachertit-n-mernyiy-kub-0b28db19.md
source_content_sha256: 5b8570b7ba66f5972c8399574d43848e4c66cd01fab75fd4da0451c01de9f7eb
translation_model: draft
translation_run: vi-draft-2026-10-31
translation_quality: draft
---

⟦folio 22⟧

Đoạn, hình vuông, hình lập phương...

Sự khác biệt giữa một đoạn thẳng, hình vuông và hình khối là gì? Đoạn thẳng là một phần của đường thẳng, hình vuông là một phần của mặt phẳng và hình lập phương là một phần của không gian. Chúng có điểm gì chung, ngoại trừ từ giờ trong định nghĩa của chúng? Hóa ra có một sự tương đồng sâu sắc trong quá trình xây dựng của họ. Trong thực tế, ví dụ, quá trình xây dựng một hình vuông cho một đoạn đã cho có thể được mô tả như sau:

từ các đầu của đoạn này ta dựng các đường vuông góc với nó sao cho các đường vuông góc này nằm trong cùng một mặt phẳng; Trên mỗi đường vuông góc, trên một phía của một đoạn nhất định, chúng ta sắp xếp các đoạn của giả và sau đó nối các đầu của các đoạn thu được.

Bây giờ chúng ta hãy viết lại quá trình xây dựng khối lập phương cho một hình vuông cho trước:

từ mỗi đỉnh của một hình vuông cho trước, ta dựng các đường vuông góc với mặt phẳng hình vuông (nghĩa là với hai cạnh của hình vuông hội tụ tại đỉnh này) sao cho các đường vuông góc này nằm trong cùng một không gian; trên các đường vuông góc ở một cạnh của hình vuông, chúng ta bố trí các đoạn có chiều dài bằng cạnh hình vuông; Qua các đầu của các đoạn này ta vẽ các đường thẳng song song với các cạnh của hình vuông (tức là dựng một hình vuông song song với hình đã cho).

Trong bài viết này, nổi bật là tính giả tạo và không phù hợp của cụm từ “chimba những đường vuông góc này nằm trong cùng một không gian”: xét cho cùng thì

không gian của chúng tôi nói chung là một! Nhưng hãy nói đùa và mô tả quá trình xây dựng thêm một công trình nữa:

từ mỗi đỉnh của một khối lập phương nhất định, chúng ta dựng các đường vuông góc với tất cả các cạnh (?!) hội tụ trong đó sao cho các đường vuông góc này nằm trong cùng một không gian; trên các đường vuông góc này ở một cạnh của hình lập phương (?!), chúng ta bố trí các đoạn có chiều dài bằng cạnh của hình lập phương; qua các đầu của các đoạn này chúng ta vẽ các đường thẳng, song song với các cạnh của hình lập phương và có chiều dài bằng nhau (có thể chúng ta dựng một khối lập phương song song với hình này (?!)).

Về mặt hình học, tất nhiên, một “công trình” như vậy là không thể - nếu chỉ vì trong không gian của chúng ta không thể vẽ nhiều hơn ba cặp đường vuông góc. Nhưng về mặt logic, lý do này hoàn toàn mạch lạc và dẫn đến khái niệm khối lập phương “bốn chiều” (nghĩa là khối lập phương trong đó 4 cặp cạnh vuông góc hội tụ tại mỗi đỉnh). Hơn nữa, tiếp tục mô tả cách xây dựng “bằng quy nạp”, chúng ta sẽ đi đến khái niệm về khối “năm chiều”, “sáu chiều” và trong trường hợp chung là khối lập phương “n chiều”. Theo lý luận này, hình lập phương thông thường là khối lập phương “ba chiều”, hình vuông là khối lập phương “hai chiều”, và một đoạn là khối lập phương “một chiều” (Hình 1, 2, 3).

Câu hỏi đặt ra là, có vật thể thực nào có đặc tính tương ứng với khối lập phương n chiều (n=1, 2, ...) không? Hóa ra chúng tồn tại; một đối tượng như vậy sẽ được thảo luận trong chương tiếp theo.

⟦folio 23⟧

Bảng đỉnh của khối n chiều
Một đoạn (khối một chiều) có hai đầu (hai đỉnh). Hãy biểu thị một trong các đầu của các số là 0 và đầu kia là 1. Chúng ta nhận được một bảng ở các đỉnh của đoạn:
0
1

Tập hợp các đỉnh của một hình vuông (khối lập phương hai chiều) được chia thành hai tập con các đỉnh có các cạnh song song với nhau. Hãy ký hiệu các đỉnh tương ứng của các cạnh có cùng số (0 hoặc 1); để phân biệt chúng với nhau, chúng ta thêm số 0 vào bên trái các đỉnh được chỉ định của một bên và số 1 của bên kia. Bảng các đỉnh của hình vuông có dạng:
00 10
01 11

Tương tự, từ bảng các đỉnh của hình vuông, lập bảng hình lập phương:
000 010 100 110
001 011 101 111

Tiếp theo là bảng ở các đỉnh của khối lập phương “bốn chiều”:
0000 0010 0100 0110 1000 1010 1100 1110
0001 0011 0101 0111 1001 1011 1101 1111

Quá trình xây dựng các bảng như vậy có thể được tiếp tục vô thời hạn. Các bảng này biểu diễn ảnh đại số của các khối n chiều; trong trường hợp này, đỉnh của khối n chiều tương ứng với một tập hợp có thứ tự n số 0 và số 1, được gọi là tọa độ của đỉnh.

Bây giờ chúng ta hãy mô tả các tính chất cơ bản của các đỉnh và cạnh của khối lập phương n chiều.

1) Mỗi cạnh của khối lập phương n chiều chứa đúng hai đỉnh của nó; tất cả tọa độ tương ứng của các đỉnh này đều giống nhau, ngoại trừ một tọa độ: ở một đầu của cạnh bằng 0 và ở đầu kia - 1. Chính tọa độ này đặc trưng cho hướng của cạnh.

2) Tất cả các cạnh theo một hướng đều song song với nhau và vuông góc với các cạnh của bất kỳ hướng nào khác.

3) Số hướng khác nhau là n. Tất cả chúng đều được mô tả bằng các cạnh cơ bản nối đỉnh 00... 0 với các đỉnh

00 . . . 01
00 . . . 10
.

.

01 . . . 00
10 . . . 00

4) Có chính xác n cạnh xuất hiện từ bất kỳ đỉnh nào của khối lập phương n chiều. Tất cả đều vuông góc với nhau theo cặp.

Với n=1, 2, 3 các thuộc tính được kiểm tra trực tiếp (kiểm tra!). Với n>3, chúng ta sẽ xây dựng các đặc tính được mô tả của các đỉnh và cạnh của khối lập phương (chúng ta để bạn xác minh tính nhất quán bên trong của chúng).

⟦folio 24⟧

Kỹ thuật đồng thời

Cùng với một hình ảnh đại số thuần túy thực - một bảng các đỉnh - một khối lập phương $n$ chiều cũng có thể được liên kết với một hình ảnh thuần túy hình học thực - một hình vẽ.

Hình 1 cho thấy một bản vẽ của một khối lập phương. Chúng ta hãy lưu ý các tính chất sau:

1) Các cạnh song song của khối vẫn song song trong bản vẽ.
2) Các cạnh vuông góc của hình lập phương trong hình vẽ không song song.
3) Các đỉnh khác nhau của khối lập phương trong hình vẽ không hợp nhất thành một.

Nói cách khác, hình vẽ của khối lập phương xuất hiện dưới dạng lưng rơi trên một bệ nằm ngang khi chiếu sáng mô hình có dây của khối vũ trụ với các tia sáng song song không nằm trong mặt phẳng của bất kỳ ranh giới nào.

Hóa ra là nếu áp dụng thiết kế song song như vậy cho khối lập phương có kích thước bất kỳ $n$, thì sẽ thu được một bản vẽ phẳng của khối lập phương $n$ chiều, có các đặc tính thứ ba được chỉ ra ở trên. Nhưng trước khi chứng minh điều này, hãy tính

Có bao nhiêu đỉnh trong một khối lập phương $n$ chiều?

Đặt $A$ là một đỉnh tùy ý của hình lập phương có tọa độ $a_n, a_{n-1}, \dots, a_2, a_1$. Vì $a_i$ bằng một hoặc một, nên chúng ta có thể coi tọa độ của đỉnh này là biểu diễn kép của một số $\varepsilon$:

$$\varepsilon = a_n \cdot 2^{n-1} + a_{n-1} \cdot 2^{n-2} + \dots + a_2 \cdot 2 + a_1$$

(khi đó ký hiệu kép $\varepsilon$ là:

$$\hat{\varepsilon}_2 = a_n a_{n-1} \dots a_2 a_1).$$

Các đỉnh của khối lập phương $n$ chiều tương ứng với tất cả các tập hợp số 0 và số một có thể có ($a_n, a_{n-1}, \dots, a_2, a_1$); mỗi bộ như vậy tương ứng với một số hoàn toàn xác định $\varepsilon$; số $\varepsilon + 1$ được lấy từ số $\varepsilon$ theo quy tắc sau: tất cả các chữ số bên phải $a_1, a_2, \dots, a_j$ là đơn vị trong một hàng, được thay thế bằng số 0, chữ số 0 (hoặc thiếu) đầu tiên $a_{j+1}$ ở bên phải được thay thế bằng một và phần còn lại (nếu có) không thay đổi. Ví dụ, chúng ta hãy tưởng tượng trong hệ thống kép các số 0, 1, 2,..., 15:

$$\hat{0}_2 = 0, \quad \hat{4}_2 = 100, \quad \hat{8}_2 = 1000,$$

$$\hat{1}_2 = 1, \quad \hat{5}_2 = 101, \quad \hat{9}_2 = 1001,$$

$$\hat{2}_2 = 10, \quad \hat{6}_2 = 110, \quad \hat{10}_2 = 1010,$$

$$\hat{3}_2 = 11, \quad \hat{7}_2 = 111, \quad \hat{11}_2 = 1011,$$

$$\hat{12}_2 = 1100,$$

$$\hat{13}_2 = 1101,$$

$$\hat{14}_2 = 1110,$$

$$\hat{15}_2 = 1111.$$

Dễ dàng nhận thấy rằng số $2^n$ trong hệ thống số kép được biểu diễn dưới dạng số có $n$ số 0 và số $2^{n-1}$ là tập hợp các số $n$. Điều này có nghĩa là có $2^n$ số kép khác nhau (từ 0 đến $2^n - 1$) có độ sâu bit không cao hơn $n$; do đó, số đỉnh của khối $n$ cũng là $2^n$.

Bây giờ chúng ta hãy thử xây dựng

Vẽ khối lập phương $n$ chiều

Hãy vẽ hai đường thẳng trên mặt phẳng một góc với nhau - sử dụng các đáy của chúng. Chúng ta hãy vẽ đồ thị trên một trong số chúng (hãy gọi nó là điểm đầu tiên) ở một bên của điểm giao nhau $2^n - 1$ nhân với tỷ lệ $a$ và ở mặt thứ hai - $n$ nhân với tỷ lệ $b$ (Hình 4, $a$). Hãy đánh số các đầu của các đoạn tỷ lệ trên trục số đầu tiên

$$1, 2,..., 2^n - 1,$$

và vào ngày thứ hai - số

$$1, 2,..., n.$$

Qua phần cuối của mỗi đoạn tỷ lệ, chúng ta vẽ một đường thẳng song song với đường chính kia. Chúng tôi nhận được tọa độ lưới. Đối với mỗi nút của lưới này, chúng ta gán một cặp số nguyên $(X, Y)$ - tọa độ của nút dọc theo hướng thứ nhất và thứ hai (điểm giao nhau của trục

⟦folio 25⟧

Hình 4: $a$ - khối bốn chiều; $\delta$ - khối năm chiều

dòng mới có tọa độ $(0,0)$). Đặt đỉnh của khối lập phương có tọa độ $(a_n, a_{n-1}, \ldots, a_2, a_1)$ tại nút của lưới kết quả có tọa độ xiên

$$\left( \sum_{i=1}^{n} a_i \cdot 2^{i-1}, \quad \sum_{i=1}^{n} a_i \right)^*.$$

Do đó, tọa độ xiên đầu tiên của nút,

$$*) \text{Знак } \Sigma \text{ (сигма)} \text{ — это знак суммирования, } \sum_{i=1}^{n} b_i = b_1 + \ldots + b_n.$$

chúng ta sẽ vẽ một đỉnh của hình lập phương, bằng số của đỉnh này và thứ hai là trọng số của nó $a_1 + \ldots + a_n$ (tức là tổng số đơn vị tọa độ của đỉnh).

Nếu hai đỉnh của khối lập phương $n$ chiều chỉ khác nhau ở một tọa độ, thì chúng ta kết nối hình ảnh tương ứng của các đỉnh trên lưới tọa độ xiên với một đoạn thẳng - đoạn này sẽ đóng vai trò là hình ảnh của cạnh của khối lập phương của chúng ta.

Điều này hoàn thành việc xây dựng bản vẽ khối lập phương $n$ chiều (trong hình -

⟦folio 26⟧

ke 4, a hiển thị hình vẽ của khối lập phương bốn chiều và trong Hình 4, b - khối lập phương năm chiều). Để chắc chắn rằng trong trường hợp tổng quát (n chiều), hình vẽ của khối lập phương n chiều là kết quả của phép chiếu song song của khối lập phương lên một mặt phẳng, hãy kiểm tra

Tính chất 3) rõ ràng được thỏa mãn: các số khác nhau tương ứng với các đỉnh khác nhau và do đó ảnh của chúng có tọa độ đầu tiên khác nhau và do đó không trùng nhau.

Bây giờ chúng ta hãy kiểm tra tính chất 1)—bảo toàn tính song song của các cạnh. Lấy hai cạnh song song bất kỳ của hình lập phương. Chúng ta hãy biểu thị tọa độ các đỉnh của cạnh đầu tiên bằng $\tilde{a}^1$ và $\tilde{a}^2$:

$$\tilde{a}^1 = (a_n^1, a_{n-1}^1, \dots, a_i^1, a_1^1),$$
$$\tilde{a}^2 = (a_n^2, a_{n-1}^2, \dots, a_i^2, a_1^2);$$

và tọa độ các đỉnh của cạnh thứ hai lần lượt qua $\tilde{b}^1$ và $\tilde{b}^2$:

$$\tilde{b}^1 = (b_n^1, b_{n-1}^1, \dots, b_i^1, b_1^1),$$
$$\tilde{b}^2 = (b_n^2, b_{n-1}^2, \dots, b_i^2, b_1^2).$$

Hướng của cạnh ở đây được đặc trưng bởi tọa độ thứ $i$.

Chúng tôi có:

$$a_j^1 = a_j^2, \quad j \neq i.$$

Không mất tính tổng quát, ta có thể giả sử rằng

$$a_i^1 = b_i^1 = 0,$$
$$a_i^2 = b_i^2 = 1.$$

Bây giờ chúng ta hãy xem xét hình ảnh $\tilde{a}^1, \tilde{a}^2, \tilde{b}^1, \tilde{b}^2$ của những hình bốn chiều này trên lưới tọa độ. Chúng ta hãy vẽ các đường thẳng song song với hướng lõi thứ nhất thông qua ảnh của các đỉnh $\tilde{a}^1$ và $\tilde{b}^1$, và các đường thẳng song song với hướng thứ hai thông qua ảnh của các đỉnh $\tilde{a}^2$ và $\tilde{b}^2$ (Hình 5). Điểm giao nhau của các đường này lần lượt được ký hiệu là $\tilde{a}$ và $\tilde{b}$. Chúng ta có hai hình tam giác: $\tilde{a}^1 \tilde{a}^2$ và $\tilde{b}^1 \tilde{b}^2$. Chúng tôi tính toán độ dài của các cạnh $\tilde{a}^1 \tilde{a}^2$ - theo cách xây dựng, nó bằng hiệu modulo của tọa độ tọa độ đầu tiên của các đỉnh $\tilde{a}^1$ và $\tilde{a}^2$:

$$\left| \sum_{j=1}^{n} a_j^1 \cdot 2^{j-1} - \sum_{j=1}^{n} a_j^2 \cdot 2^{j-1} \right| =$$
$$= \left| \sum_{j=1}^{n} \left( a_j^1 - a_j^2 \right) \cdot 2^{j-1} \right| =$$
$$= \left( a_i^2 - a_i^1 \right) \cdot 2^{i-1} = 2^{i-1}.$$

Độ dài các cạnh $\tilde{b}^1 \tilde{b}^2$ cũng bằng $2^{i-1}$. Độ dài cạnh thứ hai của tam giác
