---
id: 1975-10-stepin-tagi-zade-slova-s-ogranicheniyami-6f547c8b
issue: kvant_1975_10
year: 1975
number: "10"
title: Từ bị hạn chế
authors:
  - Стёпин А. М.
  - Таги-Заде А. Т.
rubric: matematicheskiy-kruzhok
rubric_sub: Математический кружок
page_first: 34
page_last: 39
page_labels: 32-37
tag: 6MKT
lang: vi
source: kvant_digital
extraction: vision
content_sha256: 9af1a3c3d652fe0c8794f3d2312aaf39ee0a2bb1cb5275fa5b17e59b2c09026f
prompt_sha256: draft-1
translated_from: content/ru/1975/10/articles/16_stepin-tagi-zade-slova-s-ogranicheniyami-6f547c8b.md
source_content_sha256: b92b786323ab41e96fca2903003541f6e932cd5ca018d8ac1b4c21482922df72
translation_model: draft
translation_run: vi-draft-2026-10-31
translation_quality: draft
---

⟦folio 32⟧

Từ bị hạn chế

A. M. Stepin,
A. T. Tatsi-Zade

Bài viết về chủ đề này rất gần với bài viết “Trình tự không lặp lại” của G. A. Gurevich, được xuất bản trên «Kvant» số 9 năm nay. Bài viết dành cho số được tính toán (và bằng chứng về sự tồn tại) của các từ có độ dài bất kỳ (bao gồm cả vô hạn), trong một bảng chữ cái nhất định với các hạn chế - đồng thời, nó giải được bài toán M300 từ “Zazdanika «Kvant», Số 12, 1974. Gurevich đã tính số (và chứng minh sự tồn tại) của các chuỗi có độ dài bất kỳ (và vô hạn), trong đó không có nhóm chữ số nào xuất hiện hai lần liên tiếp và được giải bằng bài toán M310.

Kỹ thuật tổ hợp với sự trợ giúp của bài toán M300 và M310 (và các khái quát hóa của chúng) đã được giải quyết được sử dụng rộng rãi trong khoa học toán học máy chủ: lý thuyết nhóm, lý thuyết đại số, lý thuyết số đại số.

Chúng tôi sẽ dạy làm quen với các từ và bảng chữ cái bằng cách phân tích bài toán M300, được cung cấp trong “Nhiệm vụ «Kvant», xem «Kvant» Số 12 cho năm 1974.

Nhiệm vụ M300

Bảng chữ cái gồm có 3 chữ cái a, b, c. Chúng ta hãy gọi một chuỗi có độ dài bất kỳ bao gồm các chữ cái này là một từ. Khi xử lý các từ, một số tổ hợp chữ cái (có độ dài từ hai chữ cái trở lên) bị coi là bị cấm. Được biết, trong danh sách tổ hợp chữ cái bị cấm tất cả các từ đều có độ dài khác nhau.

Hãy để chúng tôi chứng minh rằng có những từ có độ dài bất kỳ không chứa các tổ hợp chữ cái bị cấm.

Nhiệm vụ M300 có thể được đưa ra một hình thức – ​​“giải trí” – khác:

Một chiếc xe số tự động nào đó lái xe quanh thành phố với bố cục hình chữ nhật. Khi đến ngã tư, anh ta tiếp tục lái xe thẳng hoặc rẽ trái hoặc phải (bạn không thể rẽ lùi!) - có tính đến thực tế là luật giao thông cấm một số sự kết hợp của các điểm dừng này (trái và phải) và lối đi thẳng.

Được biết, tất cả các kết hợp bị cấm đều có độ dài ít nhất là hai (ví dụ: độ dài của kết hợp trái-phải là hai) và không có kết hợp nào khác nhau có cùng độ dài. Hóa ra là nếu thành phố đủ lớn và người lái xe xuất phát ở trung tâm, thì bất chấp mọi lệnh cấm, anh ta có thể lái xe qua bất kỳ số giao lộ nhất định nào trong thành phố này.

Giải bài toán M300 vẫn thuận tiện về thuật ngữ “chữ” và “chữ”.

Chúng tôi sẽ gọi các tổ hợp chữ cái bị cấm là các từ được chỉnh sửa và coi một từ là tốt nếu nó không chứa một từ được chỉnh sửa nào bên trong nó. Đôi khi chúng tôi sẽ gọi một tập hợp các từ phổ biến là danh sách những điều cấm hoặc hạn chế. Chúng tôi gọi một từ có chứa ít nhất một từ của người cha là “xấu”.

Hãy ký hiệu số từ hay có độ dài l là $G_l$. Để chứng minh sự tồn tại của các từ hay có độ dài bất kỳ, chỉ cần chứng minh rằng với mọi l tự nhiên, số $G_l$ lớn hơn 0 là đủ. Bây giờ chúng ta sẽ chỉ ra rằng với bất kỳ l nào cũng có khá nhiều từ hay có độ dài l: $G_l \geq 2^l$.

⟦folio 33⟧

Chúng tôi sắp xếp các từ bù trừ theo độ dài và biểu thị bằng $l_i$ độ dài của từ bù trừ thứ $i$ ($l_i \geq i$).

Bổ đề 1. Đối với các số $G_l$ bất đẳng thức sau đúng:

$$G_l \geq 3 \cdot G_{l-1} - \sum_{i=1}^{2 \leqslant l_i \leqslant l} G_{l-l_i} \cdot i$$

($G_1$, ước tính, bằng số đó; hãy đặt $G_0$ bằng một).

Bằng chứng. Lưu ý rằng tất cả các từ hay có độ dài $l$ đều nằm trong số các từ thu được bằng cách gán cho bên phải một trong các chữ cái $a, b, c$ cho các từ hay có độ dài $l-1$. Với cách gán này, chúng ta nhận được $3 \cdot G_{l-1}$ từ, trong số đó, ngoài những từ hay, có thể còn có một số từ phẳng có độ dài $l$. Hãy ước tính số lượng của họ. Rõ ràng, trong từ phẳng thu được, từ offset chỉ có thể ở cuối, tức là nó có cấu trúc như thế này: các chữ cái $l_i$ cuối cùng tạo thành một từ offset và các chữ cái $l-l_i$ đầu tiên tạo thành một từ hay ($2 \leqslant l_i \leqslant l$). Số lượng từ phẳng (độ dài $l$) của loại được mô tả kết thúc bằng một từ bù có độ dài $l_i$ không lớn hơn số từ hay có độ dài $l-l_i$, tức là số $G_{l-l_i}$ (theo quy ước chúng ta chỉ có một từ bù có độ dài $l_i$). Tuy nhiên, do việc gán một trong các chữ cái $a, b, c$ ở bên phải các từ hay có độ dài $l-1$, kết quả sẽ không nhiều hơn $\sum_{i=1}^{2 \leqslant l_i \leqslant l} G_{l-l_i}$ từ phẳng. Điều này có nghĩa là trong số $3 \cdot G_{l-1}$ từ có độ dài $l$ nhận được có ít nhất $3 \cdot G_{l-1} - \sum_{i=1}^{2 \leqslant l_i \leqslant l} G_{l-l_i}$ từ hay.

*) Tổng $\sum_{i=1}^{2 \leqslant l_i \leqslant l} G_{l-l_i}$, nói chung, không giống với $\sum_{i=1}^{2 \leqslant l_i \leqslant l} G_{l-i}$: trong tổng đầu tiên, tổng tùy ý chỉ được tính tổng theo các giá trị $l_i$, $2 \leqslant l_i \leqslant l$, mà trong danh sách cấm có một từ bị loại bỏ có độ dài tương ứng $l_i$ (nghĩa là, $l_i$ có lẽ không nhận tất cả các giá trị 2, 3, ..., $l$): Vậy nếu trong danh sách cấm không loại bỏ từ có độ dài 3 thì trong tổng $\sum_{i=1}^{2 \leqslant l_i \leqslant l} G_{l-l_i}$ thiếu thành viên $G_{l-3}$.

Bất đẳng thức (1) đóng vai trò chính trong việc ước tính số $G_l$.

Bổ đề 2. Với mọi số tự nhiên $l'$

$$G_l \geq 2 G_{l-1}.$$

(2)

Ta sẽ chứng minh Bổ đề 2 bằng phương pháp quy nạp toán học.

Cơ sở cảm ứng: $l = 1$; rõ ràng là $G_1 \geq 2 \cdot G_0$.

Bước quy nạp: Giả sử rằng bất đẳng thức (2) đúng với mọi $l \leqslant L$ tự nhiên, nghĩa là

$$\begin{cases} G_L \geq 2 \cdot G_{L-1}, \\ G_{L-1} \geq 2 \cdot G_{L-2}, \\ \dots \\ G_2 \geq 2 \cdot G_1. \end{cases}$$

(2')

Hãy để chúng tôi chứng minh rằng $G_{L+1} \geq 2 \cdot G_L$.

Từ bất đẳng thức (2') ta có:

$$G_L \geq 2 \cdot G_{L-1} \geq 2^2 \cdot G_{L-2} \geq \dots \geq 2^k \cdot G_{L-k},$$

đó là

$$G_{L-k} \leq G_L/2^k,$$

(2'')

ở đâu $k = 1, 2, \dots, L$.

Có tính đến các ước tính (2''), bất đẳng thức (1) và phương pháp tính nó, chúng ta thu được điều đó

$$G_{L+1} \geq 3 \cdot G_L - \sum_{i=1}^{2 \leqslant l_i \leqslant l} G_{L+1-l_i} \geq$$

$$\geq 3 \cdot G_L - \sum_{k=1}^{l} G_{L-k} \geq *$$

$$\geq 3 \cdot G_L - G_L \cdot \sum_{k=1}^{l} \frac{1}{2^k} \geq$$

$$\geq G_L \cdot (3-1) = 2 \cdot G_L,$$

và đây chính là điều cần phải chứng minh.

Vì $G_{l-1} \geq 2 \cdot G_{l-2}, G_{l-2} \geq 2 G_{l-3}, \dots, G_1 \geq 2 \cdot G_0 = 2$, thì $G_l \geq 2^l$, và ta có Định lý 1:

Với mọi số tự nhiên $l$ trong số bài toán M300 thì số từ hay có độ dài $l$ không nhỏ hơn $2^l$:

$$G_l \geq 2^l,$$

(3)

kết thúc bằng lời giải trong số bài toán của chúng tôi.

*) Đây là số tiền được công bố:

$$\sum_{k=1}^{l} G_{L-k} = G_{L-1} + G_{L-2} + \dots + G_{L-l}.$$

⟦folio 34⟧

Lời nói vô tận

Bây giờ chúng ta biết rằng “từ điển” bài toán M300 chứa những từ hay có độ dài bất kỳ. Liệu nó có những lời tốt đẹp dài vô tận?

Bây giờ chúng ta sẽ chứng minh rằng nếu danh sách các từ được đánh dấu là hữu hạn (chỉ có hữu hạn số tổ hợp chữ cái bị cấm), thì sẽ có một từ tốt dài vô hạn. Tuy nhiên, chúng tôi lưu ý ngay rằng trên thực tế, yêu cầu về một danh sách hữu hạn các từ riêng biệt không tồn tại: tuyên bố về sự tồn tại của một từ tốt dài vô hạn vẫn đúng trong trường hợp có vô số lệnh cấm *).

Hãy lấy từ trong ngoặc đơn dài nhất (vì theo giả định, số lượng từ trong ngoặc đơn là hữu hạn nên điều này có thể thực hiện được); đặt giá trị của nó bằng $n$. Hãy chọn $N$ tự nhiên sao cho $N$ lớn hơn $n$. Vì chúng ta có những từ hay có độ dài bất kỳ, hãy lấy những từ hay có độ dài

*) Bạn có thể tìm thấy bằng chứng cho sự thật này trong bài báo “Chuỗi không lặp lại” của G. A. Gurevich (xem «Kvant» số 9). Bài báo của Gurevich thực tế đã chứng minh rằng từ tính chất “có một từ hay dài tùy ý” thì tính chất “có một từ hay dài vô hạn” suy ra, tức là trên thực tế, sự tồn tại của những từ hay có độ dài bất kỳ đều tương đương với sự tồn tại của một từ hay dài vô hạn. Chúng tôi sẽ chứng minh rằng trong các câu của chúng tôi có một từ định kỳ, không hữu hạn và chúng tôi sẽ chỉ ra cách xây dựng một từ như vậy (như họ nói, chúng tôi sẽ đưa ra một bằng chứng xây dựng).

$N \cdot (3^N + 1)$, hãy biểu thị nó bằng $A$. Chúng ta hãy chia các từ $A$ thành $(3^N + 1)$ các phần có độ dài bằng nhau $B_k$ có độ dài $N$: nếu

$$A = x_1, x_2, \dots, x_N \cdot (3^N + 1).$$

trong đó $x_i$ là $a$, hoặc $b$, hoặc $c$, thì $B_k = x_N \cdot (k - 1) + 1, x_N \cdot (k - 1) + 2, \dots, x_N \cdot k.$

Vì $A$ là một từ hay nên mọi $B_k$ cũng là một từ hay có độ dài $N$. Nhưng trong bảng chữ cái của chúng ta chỉ có ba chữ cái $(a, b, c)$, vì vậy sẽ không có nhiều từ hay có độ dài $N$ hơn $3^N$. Chúng tôi đã nhận được $(3^N + 1)$ lời tốt đẹp $B_k$; Điều này có nghĩa là trong số đó có những cái giống hệt nhau. Ví dụ: đặt $B_{n_1} = B_{n_2}$ và $n_1 < n_2$. Chúng ta hãy lấy một đoạn của từ $A$, bao gồm các phần $B_k$ với các số $k$ từ $n_1$ đến $n_2 - 1$. Đây sẽ là một từ hay $C$ có độ dài $m \geq N$:

$$C = x_N \cdot (n_1 - 1) + 1, \dots, x_N \cdot (n_2 - 1).$$

Chúng ta hãy thêm từ $C$ tương tự vào từ $C$ ở bên phải. Chúng ta nhận được các từ $D$ có ​​độ dài $2m$:

$$D = x_N \cdot (n_1 - 1) + 1, \dots, x_N \cdot (n_2 - 1),$$

$$x_N \cdot (n_1 - 1) + 1, \dots, x_N \cdot (n_2 - 1).$$

Hãy chứng minh rằng $D$ là một từ hay.

Giả sử điều ngược lại: $D = CC$ là một từ phẳng; sau đó nó chứa một số loại từ trong ngoặc đơn. Rõ ràng đây là một câu cửa miệng

⟦folio 35⟧

chỉ có thể tìm thấy ở vùng “dán” hai từ hay $C$, sao cho giao điểm của nó với từ “phải” và “trái” $C$ không trống. Nhưng $B_{n_1} = B_{n_2}$ hoặc trên bất kỳ từ được đánh dấu nào đều được thay thế bằng $N$; Điều này có nghĩa là từ được đánh dấu này phải nằm trong vùng “dán lại” các phần $B_{n_2}-1$ và $B_{n_1}$ của từ tốt $A$, nhưng điều này không thể xảy ra, và do đó, từ $D$ là từ tốt.

Rõ ràng là một từ định kỳ vô hạn $CC \dots C$ với dấu chấm $C$ cũng sẽ tốt, và trên thực tế, điều này cung cấp mọi thứ cần thiết.

Vì vậy, số tự động của chúng tôi có thể lái xe quanh thành phố trong một thời gian dài vô tận mà không vi phạm luật lệ giao thông!

Ví dụ thú vị

Chúng ta hãy quay lại bất đẳng thức (1), với cách chứng minh mà chúng ta đã bắt đầu lời giải bài toán M300; hãy viết lại nó như thế này:

$$G_l - 3 \cdot G_{l-1} + \sum_{l_i, 2 \leqslant l_i \leqslant l} G_{l-l_i} \geqslant 0.$$ (4)

Độ chính xác của sự bất bình đẳng này như thế nào? Có thể thay dấu “=” trong đó bằng dấu “=” được không? Nói chung, điều đó là không thể, và đây là lý do.

Con số $3 \cdot G_{l-1}$ là số từ thu được khi thêm độ dài vào bên phải những từ hay $l-1$ một trong những lá thư $a, b, c$; trong số những từ như vậy có tất cả những từ hay và dài $l$. Trừ từ số $3 \cdot G_{l-1}$ con số $G_{l-l_i}$, Ở đâu $l_i$ - một số giá trị 2, 3, ..., $l$ (có thể là tất cả các nghĩa), do đó, chúng tôi gạch bỏ độ dài của các từ được xây dựng $l$ tất cả những từ phẳng có được nếu một từ có độ dài tốt $l-l_i$ thêm độ dài từ được đánh dấu $l_i$. Nhưng hóa ra có thể một từ phẳng nào đó có độ dài $l$ dường như bị gạch bỏ nhiều lần khỏi danh sách $3 \cdot G_{l-1}$ các từ kết quả. Nếu trong số chúng ta $3 \cdot G_{l-1}$ độ dài từ $l$ không có từ nào được sinh ra từ những từ hay và dài dòng $l-l_i$ bằng cách thêm một từ đánh dấu có độ dài vào bên phải $l_i$, thì tương ứng số $G_{l-l_i}$ Không cần phải trừ chút nào.

Tuy nhiên, dưới một số điều kiện bổ sung trong danh sách cấm cùng với các bất đẳng thức truy hồi (4) đối với các số $G_l$ ($l$ - bất kỳ), các đẳng thức truy hồi tương tự sẽ được thỏa mãn:

$$G_l - 3 \cdot G_{l-1} + \sum_{l_i, 2 \leqslant l_i \leqslant l} G_{l-l_i} = 0.$$ (4')

Trong những trường hợp như vậy, $G_l$ được viết rõ ràng dưới dạng hàm của $l$ và với mỗi giá trị cụ thể $l$ thì có thể tính được số $G_l$.

Cụ thể, từ phần trên cho thấy rằng để tính hợp lệ của đẳng thức truy hồi (4'), hai điều kiện sau là đủ:

1. Trong số các từ có độ dài $l$, thu được bằng cách gán ở bên phải một trong các chữ cái $a, b, c$ cho các từ hay có độ dài $l-1$, tìm tất cả các từ thu được từ các từ hay có độ dài $l-l_i$ bằng cách gán ở bên phải một từ có độ dài được đánh dấu $l_i$ (nó được cho là nằm trong danh sách bị cấm).

2. Mỗi từ dương có độ dài $l$ thu được bằng cách ghi công tối đa (của một chữ cái) được thể hiện dưới dạng một từ hay nào đó (độ dài nhỏ hơn) và một từ được đánh dấu theo một cách duy nhất.

Điều kiện 2° được thỏa mãn nếu không có từ nào được đánh dấu trong danh sách cấm đứng cuối bất kỳ từ nào được đánh dấu khác.

Bài tập 1. Kiểm tra xem bảng chữ cái gồm ba chữ cái và danh sách các từ được đánh dấu $ab, acb, accb, \dots, ac\dots cb$ có thỏa mãn các điều kiện 1° và 2° không, và đối với các số $G_l$ các mối quan hệ truy hồi cũng hợp lệ:

$$G_l - 3 \cdot G_{l-1} + G_{l-2} + \dots + G_{l-s} = 0.$$ (5)

(s là độ dài của từ được đánh dấu dài nhất).

Nếu danh sách cấm ở bài tập 1 chỉ giới hạn ở hai từ được đánh dấu $ab$

*) Các phương trình có dạng $G_l + b_1 G_{l-1} + b_2 G_{l-2} + \dots + b_s G_{l-s} = 0$ ($b_1, \dots, b_s$ là một số hằng số) được gọi là phương trình sai phân hữu hạn; bạn có thể đọc về phương pháp của họ lời giải trong cuốn sách “Tính sai phân hữu hạn” của A. O. Gelfon. M., “Khoa học”, Chương V, § 4, đoạn 2.

⟦folio 36⟧

và acb thì ta được phương trình
$$G_l - 3 \cdot G_{l-1} + G_{l-2} + G_{l-3} = 0. \quad (5')$$
Lời giải phương trình (5') sẽ được tìm ở dạng
$$G_l = \lambda^l. \quad (5'')$$
Thay (5'') vào (5'), ta thu được phương trình
$$\lambda^3 - 3\lambda^2 + \lambda + 1 = 0,$$
có ba gốc khác nhau:
$$\lambda_1 = 1, \quad \lambda_2 = 1 + \sqrt{2}, \quad \lambda_3 = 1 - \sqrt{2}.$$
Tổng quát lời giải của phương trình (5') được viết như sau:
$$G_l = C_1 + C_2 (1 + \sqrt{2})^l + C_3 (1 - \sqrt{2})^l,$$
trong đó $C_1, C_2$ và $C_3$ là các hằng số được xác định từ các điều kiện ban đầu:
$$G_0 = 1, \quad G_1 = 3, \quad G_2 = 8.$$
Điều này dẫn đến một hệ thống xác định $C_1, C_2, C_3$:
$$\begin{cases}
C_1 + C_2 + C_3 = 1, \\
C_1 + C_2 (1 + \sqrt{2}) + C_3 (1 - \sqrt{2}) = 3, \\
C_1 + C_2 (3 + 2\sqrt{2}) + C_3 (3 - 2\sqrt{2}) = 8,
\end{cases}
$$nó nằm ở đâu
$$C_1 = -\frac{1}{2}, \quad C_2 = \frac{3}{4} + \frac{\sqrt{2}}{2}, \\
C_3 = \frac{3}{4} - \frac{\sqrt{2}}{2},$$
Có nghĩa,
$$G_l = -\frac{1}{2} + \left(\frac{3}{4} + \frac{\sqrt{2}}{2}\right) \cdot (1 + \sqrt{2})^l + \left(\frac{3}{4} - \frac{\sqrt{2}}{2}\right) \cdot (1 - \sqrt{2})^l$$
(một phần, $G_3 = 20$).

Khái quát hóa bài toán M300

Giả sử bảng chữ cái bao gồm $n$ chữ cái $a_1, a_2, \dots, a_n$ và trong danh sách các từ bị loại (dài ít nhất hai) có hơn $m$ các từ khác nhau có cùng độ dài.

Bây giờ chúng tôi sẽ chứng minh rằng, theo những hạn chế nhất định đối với các số nguyên tố $n$ và $m$, một “từ” như vậy sẽ chứa các từ hay dài tùy ý và đối với mỗi $l$ tự nhiên ($l$ là độ dài của từ) - một lần nữa, khá nhiều.

Như với lời giải bài toán M300 (với M300 ta có: $n=3, m=1$), trước tiên chúng ta cần chứng minh điều đó.

Bổ đề 3. Nếu các điều kiện của “tổng quát bài toán M300” được thỏa mãn đối với các số $G_l$ và độ dài $l$ cũng đúng:
$$G_l \geq n \cdot G_{l-1} - \sum_{i=1}^{n-1} m_i \cdot G_{l-i}, \quad (6)$$
Nói cách khác, $m_i$ biểu thị số lượng từ bị loại bỏ có độ dài $l_i$ ($G_1$, rất indo, bằng $n$ và $G_0$ lại được đặt thành 1).

Bổ đề 3 được chứng minh bằng cách lập luận giống hệt như Bổ đề 1 (xem trang 33); Chúng tôi sẽ không chứng minh điều đó.

Vì, theo điều kiện của từng trường hợp, $m_i$ không lớn hơn $m$ (trong phần tiếp theo chúng ta sẽ xét $m = \max\{m_i\}$ và gọi $m$ là bội của hệ ràng buộc), nên
$$G_l \geq n \cdot G_{l-1} - m \cdot \sum_{i=1}^{n-1} G_{l-i}. \quad (7)$$
Bước tiếp theo sau Bổ đề 3 là chứng minh Bổ đề 4 quan trọng:
$$m \leq \left(\frac{n-1}{2}\right)^2, \quad (8)$$
mo. có một số $\lambda > 1$ sao cho đối với mọi $l$ tự nhiên
$$G_{l+1} \geq \lambda \cdot G_l. \quad (9)$$
Bổ đề 4, giống như Bổ đề 2 của đoạn đầu tiên, được chứng minh bằng phương pháp quy nạp toán học sử dụng bất đẳng thức (7) và các tương ứng (2') và (2''), trong đó số “2” được thay thế bằng chữ “λ” (xem trang 33). Có thể thực hiện chuyển đổi biểu thị từ $L$ sang $L+1$ vì bất đẳng thức tương đối bình phương $\lambda$
$$n - \frac{m}{\lambda - 1} \geq \lambda$$ với phân biệt không âm (do (8))
$$\left[ \left(\frac{n-1}{2}\right)^2 - m \right]$$ có lời giải
$$\lambda_1, 2 = \frac{n+1}{2} \pm \sqrt{\left(\frac{n-1}{2}\right)^2 - m}.$$
Vì $G_1 = n \cdot G_0$ (nhớ lại $G_0 = 1$) và
$$n \geq \frac{n+1}{2} + \sqrt{\left(\frac{n-1}{2}\right)^2 - m},$$
Cái đó
$$G_1 \geq \left(\frac{n+1}{2} + \sqrt{\left(\frac{n-1}{2}\right)^2 - m}\right) \cdot G_0,$$
và số $\lambda > 1$ tồn tại đã được chứng minh.
Cuối cùng, tương tự như Định lý 1, chúng ta sẽ thu được Định lý 2:
Nếu ở điều kiện “tổng quát bài toán M300” $m \leq \left(\frac{n-1}{2}\right)^2$, thì

### Chặn hạn chế

Việc hạn chế (8) về tính đa dạng của hệ thống cấm có cần thiết không?

Chúng ta đã thấy rằng điều kiện $m \leqslant \left(\frac{n-1}{2}\right)^2$ là đủ để tồn tại một từ tốt dài tùy ý. Nói chung, tình trạng này không thể bị suy yếu. Trên thực tế, đối với $n = 2$ đối với bảng chữ cái gồm hai chữ cái $a$ và $b$, chúng ta thu được điều kiện bội số $m \leqslant \frac{1}{4}$. Hãy đặt $m = 1$ và lấy ba từ sau đây làm dấu:

$$ab,\ aaa,\ bbbb.$$

Hãy chứng minh rằng không có từ hay nào dài hơn năm. Một hệ thống cấm không có từ ngữ hay nào dành cho bất kỳ độ dài nào sẽ được gọi là *chặn*.

Chứng minh (bằng phản chứng).

Giả sử có một từ hay có độ dài 6. Nó kết thúc bằng chữ cái $a$ hoặc chữ cái $b$.

Nếu từ này kết thúc bằng chữ cái $b$, thì vì sự kết hợp $ab$ bị cấm, nên từ “tốt” của chúng ta chỉ bao gồm các chữ cái $b$, điều này không thể xảy ra vì sự kết hợp $bbbb$ bị cấm.

Hãy để từ hay này (dài 6) kết thúc bằng một cây sồi $a$; Hãy xem xét chữ cái áp chót của nó: - nếu nó là $b$, thì tất cả các chữ cái khác (5 chữ cái) phải là $b$ - nhưng điều này không nên như vậy. Điều này có nghĩa là từ của chúng tôi kết thúc bằng $aa$. Bây giờ chúng ta lấy chữ cái thứ ba tính từ cuối từ của chúng ta: nếu lại là $a$ thì lệnh cấm $aaa$ ảnh hưởng, nhưng nếu là $b$ thì các chữ cái còn lại (4 chữ cái) cũng là $b$, và lệnh cấm $bbbb$ ảnh hưởng.

Chúng ta hãy đưa ra một ví dụ khác về hệ thống chặn các lệnh cấm - đối với bảng chữ cái gồm ba chữ cái $a$, $b$, $c$. Đối với bảng chữ cái như vậy, điều kiện (8) cho chúng ta rằng $m$ không được lớn hơn 1. Đặt $m = 2$, tức là giả sử rằng chúng ta có thể đánh dấu hai từ có cùng độ dài, chúng ta coi các từ sau là đã được đánh dấu:

$$ab,\ ac;\ bcb,\ bcc;\ aaaa,\ bbbb;\ ccccc.$$

Bài tập 2. Chứng minh rằng những từ được đánh dấu này tạo thành một ràng buộc chặn đối với những từ hay.

Độ dài tối đa của một từ tốt trong trường hợp này là bao nhiêu?

Từ các ví dụ được xem xét cho $n = 2$ và 3, suy ra rằng có một hệ thống chặn các lệnh cấm với bội số $m$ sao cho

$$\left(\frac{n-1}{2}\right)^2 < m \leqslant \left(\frac{n-1}{2}\right)^2 + 1.$$

⟦column⟧

Nhưng đối với một số tự nhiên tùy ý $n$ và một số nguyên $m$, trong đó

$$\left(\frac{n-1}{2}\right)^2 < m \leqslant \left(\frac{n-1}{2}\right)^2 + 1,$$

sự tồn tại của một hệ thống cấm đối với bảng chữ cái gồm $n$ các chữ cái có bội số $m$ vẫn chưa được chứng minh. Hãy để chúng tôi chứng minh rằng đối với một bảng chữ cái gồm $n$ các chữ cái $a_1,\ \ldots,\ a_n$ tồn tại một hệ thống chặn các lệnh cấm với bội số $m = \frac{n\,(n-1)}{2}$. Thật vậy, chúng ta hãy áp dụng một hệ thống cấm đoán như vậy

(1) $a_1a_2$, (2) $a_1a_3$, . . . , $(n-1)\ a_1a_n$,

$(n)\ a_2a_3$, . . . , $\left(\frac{n\,(n-1)}{2}\right) a_{n-1}a_n$.

Khi đó sẽ không có từ hay nào có độ dài lớn hơn $2n$, và từ hay duy nhất có độ dài $2n$ sẽ là từ

$$a_na_na_{n-1}a_{n-1}\ldots a_1a_1.$$

Nhưng, tất nhiên, trong từng trường hợp cụ thể, tất cả phụ thuộc vào cách cấu trúc hệ thống các lệnh cấm. Ví dụ, đối với một bảng chữ cái gồm hai chữ cái $a$, $b$ $(n = 2)$ và $m = 1$, chỉ cần lấy các từ được đánh dấu là đủ

$$aa,\ aba,\ abaa,\ abaab,\ \ldots,$$

làm thế nào chúng ta biết được rằng thậm chí còn có một từ định kỳ, dài vô tận $bb\ldots b\ldots$. Hơn nữa, bạn có thể lấy $m$ bằng số chẵn bốn (và chắc chắn là hai và ba) và dưới dạng các từ được đánh dấu, ví dụ:

$$aa,\ ab,\ ba,\ aab,\ aba,\ baa,\ aaa,$$

và chúng ta sẽ lại nhận được một từ tốt đẹp vô hạn $bb\ldots b\ldots$.

Để kết luận, chúng tôi mời những độc giả quan tâm đến “bài toán chữ hay” giải quyết bài toán.

1. Chứng minh rằng đối với bảng chữ cái $a$, $b$ không có hệ thống ràng buộc chặn nào ít hơn ba từ.

2. Chứng minh rằng trong trường hợp $n = 3$ và $m = 2$ không có hệ thống quyền anh nào có ít hơn sáu từ được đánh dấu.

3. Chứng minh rằng nếu đối với bảng chữ cái $a$, $b$, $c$ các từ $ca$, $cb$, $ba$ được đánh dấu thì $G_l$ lớn dần thành $l^2$.

4. Chứng minh rằng $G_{l_1+l_2} \leqslant G_{l_1} \cdot G_{l_2}$.

5. Chứng minh rằng với một bảng chữ cái gồm $n$ tồn tại một hệ ràng buộc chặn với bội số $m$ sao cho

$$\frac{n\,(n-2)}{2} + 2 \leqslant m < \frac{n\,(n-2)}{2} + 3.$$

⟦folio 37⟧
