---
id: 1987-5-sobolev-o-sluchaynyih-bluzhdaniyah-92de19b2
issue: kvant_1987_5
year: 1987
number: "5"
title: Về bước đi ngẫu nhiên
authors:
  - Соболев С. И.
rubric: matematicheskiy-kruzhok
rubric_sub: Математический кружок
page_first: 47
page_last: 50
page_labels: 45-48
tag: YQUU
lang: vi
source: kvant_digital
extraction: vision
content_sha256: ad87a5d3177c9e071b88ec7b7df2b6e9d2f313892446dbd9d3b2b7f3fbdccd2f
prompt_sha256: draft-1
translated_from: content/ru/1987/05/articles/14_sobolev-o-sluchaynyih-bluzhdaniyah-92de19b2.md
source_content_sha256: 7debb2e706e90d3f16db5e6954bd9423960b2d60c62dbb6d945961ca65b27ab8
translation_model: draft
translation_run: vi-draft-2026-10-31
translation_quality: draft
---

⟦folio 45⟧

Về bước đi ngẫu nhiên

Ứng viên Khoa học Vật lý và Toán học
S. I. SOVOLEV

Trong một chương trình phát thanh dựa trên câu chuyện cổ tích “Cipollino và những người bạn” của Gianni Rodari, thám tử ông Carrot đang tìm kiếm Cipollino đã được phục hồi theo nguyên tắc:

“Lùi lại, tiến lên,
Tên cướp sẽ không rời bỏ chúng ta.”

Nguyên tắc tìm kiếm này có thể bị tác giả coi là một trò đùa nếu tính hiệu quả của nó không xuất phát từ một định lý của lý thuyết xác suất. Lưu ý của chúng tôi liên quan đến định lý này và các vấn đề liên quan.

Bước đi ngẫu nhiên qua vùng hoang dã

Hãy đánh dấu các điểm nguyên trên đường thẳng, lấy một đồng xu và một con chip. Hãy tưởng tượng rằng tại thời điểm 0 có một mã thông báo tại điểm $a \in Z$. Hãy tung một đồng xu. Nếu nó hạ cánh dưới dạng quốc huy, hãy di chuyển chip 1 sang phải, nếu nó hạ cánh ở dạng đuôi thì di chuyển chip 1 sang trái. Và sau đó chúng ta ném đồng xu một lần nữa và hành động theo quy tắc này, v.v. Nếu đồng xu không có lỗi thì con chip, tại thời điểm $t$ ($t = 0, 1, 2, \dots$) đứng tại điểm $k \in Z$, tại thời điểm tiếp theo $t + 1$ với xác suất 1/2 sẽ kết thúc tại điểm $k + 1$ hoặc có cùng xác suất sẽ kết thúc tại điểm $(k - 1)*$.

Quá trình được mô tả được gọi là bước đi ngẫu nhiên đối xứng trên tập hợp $Z$ các điểm nguyên trên đường thẳng bắt đầu từ điểm $a$. Kiểu bước đi này được gọi là đối xứng vì đồng xu có đầu và đuôi có quyền ngang nhau.

Làm rõ một chút tình huống từ câu chuyện cổ tích của Gianni Rodari, chúng ta sẽ giả sử rằng thám tử Carrot, khi tìm kiếm Cipollino, thực hiện một bước đi ngẫu nhiên đối xứng qua tập hợp $Z$ (với sự trợ giúp của một đồng xu).

*) Xác suất $p(x)$ của sự kiện $x$ là một đặc tính số nhất định về khả năng xảy ra sự kiện này. Xác suất của một sự kiện không thể xảy ra được coi là bằng 0, của một sự kiện đáng tin cậy là bằng 1 và nói chung là $0 \leq p(x) \leq 1$. Trong các tình huống phức tạp, xác suất được xác định theo tiên đề, nhưng trong lưu ý này, lý thuyết tiên đề sẽ được thay thế bằng một lượng nhỏ lẽ thường. Đặc biệt, nếu một số sự kiện có khả năng xảy ra như nhau thì xác suất của chúng là như nhau; ví dụ: xác suất nhận được mặt ngửa (hoặc patter) trên một viên xúc xắc không gian lận tất nhiên là 1/6, xác suất nhận được mặt ngửa trên một đồng xu không gian lận là 1/2.

⟦folio 46⟧

Nhiệm vụ 1. Lấy một đồng xu và một con chip, đặt con chip vào điểm 0. Ném một đồng xu, di chuyển con chip và ghi lại vị trí của nó. Lặp lại tối đa 10 lần. Kết quả là bạn sẽ nhận được một chuỗi các vị trí chip tuần tự.

Một bước đi cụ thể có thể được hình dung bằng cách vẽ quỹ đạo của nó. Vị trí của token tại thời điểm $t$ tại điểm $k$ sẽ được đánh dấu bằng điểm $M_t$ có ​​tọa độ $(t; k)$ trên mặt phẳng có hệ tọa độ Descartes hình chữ nhật. Bằng cách kết nối điểm $M_t$ với điểm $M_{t+1}$ ($t = 0, 1, 2, \dots$) bằng một mũi tên, chúng ta sẽ có được hình ảnh trực quan về quỹ đạo của chip.

Ví dụ: nếu khi tung đồng xu, $\Gamma, \Gamma, P, \Gamma, P$ được trả theo trình tự và vị trí ban đầu của chip là điểm 0 thì các vị trí tiếp theo cũng là:

| thời gian | 0 | 1 | 2 | 3 | 4 | 5 |
| :--- | :--- | :--- | :--- | :--- | :--- | :--- |
| vị trí chip | 0 | 1 | 2 | 1 | 2 | 1 |

và quỹ đạo trông giống như trong hình 1.

Nhiệm vụ 2. Vẽ một quỹ đạo mô tả bước đi của con chip từ nhiệm vụ 1.

Xác suất trúng một điểm nhất định

Để mã thông báo đi dọc theo một đường thẳng bắt đầu từ điểm 0. Một câu hỏi thú vị là xác suất tại thời điểm $t$ mã thông báo kết thúc ở vị trí $k$ là bao nhiêu. Nói cách khác, xác suất để quỹ đạo liên kết $t$ đến điểm $(t; k)$ là bao nhiêu? Hãy để chúng tôi biểu thị niềm tin này $P_t(k)$. Đáp số đối với câu hỏi đặt ra phụ thuộc vào số $S_t(k)$ quỹ đạo đi từ điểm $(0; 0)$ đến điểm $(t; k)$.

Gần mỗi điểm $(t; k)$, tại đó có ít nhất một quỹ đạo đến, chúng ta viết số $S_t(k)$, cho biết có bao nhiêu quỹ đạo dẫn đến điểm này cho $t = 0, 1, 2, 3$ (hình 2).

Nhiệm vụ 3. Tiếp tục hình 2 cho $t = 4, 5, 6$.

Có thể lưu ý những điều sau đây. Mũi tên chỉ có thể đi đến điểm $(t; k)$ từ các điểm $(t - 1; k - 1)$ và $(t - 1; k + 1)$, và không có nơi nào khác. Vì vậy $S_t(k) = S_{t-1}(k-1) + S_{t-1}(k+1)$.

Bảng bao gồm các số $S_t(k)$, phần đầu mà chúng ta vẽ, hóa ra được gọi là tam giác Pascal. Nó luôn luôn, theo từng cột, tạo ra các điều kiện $S_0(0) > 1$ và sự tương ứng (1). Ví dụ:

$$\begin{align*}
S_1(-1) &= S_0(-2) + S_0(0) = 0 + 1 = 1, \\
S_1(1) &= S_0(0) + S_0(2) = 1 + 0 = 1, \\
S_2(-2) &= S_1(-3) + S_1(-1) = 0 + 1 = 1, \\
S_2(0) &= S_1(-1) + S_1(1) = 1 + 1 = 2, \\
S_2(2) &= S_1(1) + S_1(3) = 1 + 0 = 1,
\end{align*}$$

và vân vân.

Tất nhiên, số quỹ đạo liên kết $t$ nhiều gấp đôi so với quỹ đạo liên kết $(t - 1)$ - xét cho cùng, mỗi quỹ đạo liên kết $(t - 1)$ tạo ra hai quỹ đạo liên kết $t$. Do đó, có 2 quỹ đạo liên kết đơn, 4 quỹ đạo liên kết đôi, v.v., quỹ đạo liên kết $t$ – $2^t$.

Tất cả các quỹ đạo liên kết $2^t t$ đều là những quỹ đạo có thể xảy ra của chuyển động của con chip (vì đầu $\Gamma$ và đuôi $P$ đều là kết quả có thể xảy ra của việc tung một đồng xu), trong đó quỹ đạo $S_t(k)$ đạt đến điểm $(t; k)$. Do đó, xác suất $P_t(k)$ để quỹ đạo liên kết $t$ đến điểm $(t; k)$ bằng $S_t(k)/2^t$. Gần điểm $(t; k)$, tại đó có ít nhất một quỹ đạo tới, chúng ta viết ra xác suất $P_t(k)$. Hãy gọi bảng kết quả là một tam giác tin cậy. Chia đẳng thức (1) cho $2^t$, ta thu được định luật

⟦folio 47⟧

$$P_t(k) = \frac{1}{2} P_{t-1}(k-1) + \frac{1}{2} P_{t-1}(k+1),$$

tạo ra (sử dụng các điều kiện $P_0(0) \geq 1$) toàn bộ tam giác xác suất (hình 3).

Nhiệm vụ 4. Tiếp tục vẽ tam giác xác suất $P_t(k)$ sang phải, viết ra $t = 4, 5, 6$.

Công thức (2) xét rằng:

1) Một quân cờ có thể ở vị trí $k$ tại thời điểm $t$ chỉ khi nó ở một trong các vị trí lân cận $k - 1$ hoặc $k + 1$ tại thời điểm $t - 1$;

2) quá trình chuyển đổi từ vị trí $k - 1$ sang vị trí $k + 1$ hoặc từ vị trí $k + 1$ sang vị trí $k$ xảy ra với xác suất $1/2$ (vị trí trước $P_{t-1}(k - 1)$ và $P_{t-1}(k + 1)$ và hệ số chi phí $1/2$).

Hai bài toán tiếp theo dành cho những người đã quen với các tổ hợp số nhất định và biết công thức nhị thức.

Nhiệm vụ 5. Chứng minh rằng

$$P_n(k) = C_n^{\frac{n+k}{2}}/2^n,$$

số $C_n^m$ khác của sự kết hợp của các phần tử $n$ bằng $m$.

Bài 6. a) Kiểm tra $t = 1, 2, 3, 4$ rằng hệ số $x^k$ trong khai triển đa thức

$$\frac{1}{2^n} \left( x + \frac{1}{x} \right)^t$$

ở lũy thừa $x$ bằng $P_t(k)$. 6) Chứng minh khẳng định phần a) với mọi số tự nhiên $t$.

Cipollino sẽ bị bắt?

Giả sử có một Cipollino ngẫu nhiên tại điểm 0 trên đường thẳng và tại điểm $k$ có cầu Morkovu. Chúng tôi giả định rằng thám tử đang tìm kiếm Cipollino thực hiện một bước đi ngẫu nhiên đối xứng bắt đầu từ thời điểm 0 tại điểm $k$ trên đường thẳng. Với xác suất nào để chủ nhân của Morkova tìm thấy Cipollino, tức là liệu anh ta có kết thúc ở điểm 0 không?

Hãy biểu thị xác suất này $P(k)$. Giống như bất kỳ xác suất nào, $P(k)$ là một phần của một:

$$0 \leq P(k) \leq 1.$$

Lưu ý rằng $P(0) > 1$ (nếu $k = 0$ thì tại thời điểm 0 thám tử và Cipollino đang ở cùng một điểm,

hãy nhớ - một sự kiện đáng tin cậy và xác suất của nó bằng 1). Nếu $k \neq 1$, thì vì từ điểm $k$ thám tử chỉ có thể đến điểm 0 bằng cách đi vào thời điểm tiếp theo sau khi rời điểm $k$ qua các điểm lân cận $k - 1$ và $k + 1$, nên định luật tổng một nửa tương tự hóa ra vẫn đúng:

$$P(k) = \frac{1}{2} P(k - 1) + \frac{1}{2} P(k + 1).$$

Ở đây người ta tính đến việc chuyển đổi trên một đơn vị thời gian từ điểm $k$ sang điểm $k - 1$ xảy ra với xác suất $1/2$; điều tương tự cũng đúng khi di chuyển từ điểm $k$ đến điểm $k + 1$.

Xét các điểm $M_k(k; p(k))$ trên mặt phẳng có hệ tọa độ Descartes góc vuông $xOy$. Vì trung điểm của đoạn nối các điểm $(x_1; y_1)$ và $(x_2; y_2)$ là điểm $\left( \frac{x_1 + x_2}{2}; \frac{y_1 + y_2}{2} \right)$ nên rõ ràng điểm $M_k$ (trong đó $k \neq 0$) là trung điểm của đoạn $M_k - 1M_k + 1$. Do đó, các điểm $M_k$, trong đó $k \geq 0$, nằm trên một tia và các điểm $M_k$, trong đó $k \leq 0$, nằm trên một tia. Cả hai tia này đều đi ra từ điểm $M_0(0; 1)$ (kể từ $P(0) > 1$) và nằm trong dải $0 \leq y \leq 1$ (kể từ $0 \leq P(k) \leq 1$ với mọi $k$) được bao bọc bởi hình 4. Do đó, chúng tạo thành đường thẳng $y = 1$. Tất cả các điểm $M_k(k; P(k))$ đều nằm trên đường thẳng này, vì vậy $P(k) \geq 1$ với mọi $k$.

Vì vậy, chúng tôi đã chứng minh rằng thám tử sớm hay muộn sẽ tìm thấy Cipollino với xác suất 1, bất kể anh ta bắt đầu lang thang từ thời điểm nào $k$!

Người đọc có thể hỏi - điều gì sẽ xảy ra nếu khi ném một đồng xu, một đồng xu luôn rơi ra ngoài, vì khi đó thám tử sẽ ở bên phải theo một đường thẳng và không tìm thấy Cipollino nào? Tất nhiên, việc đi bộ như vậy là có thể xảy ra về mặt logic, nhưng xác suất để xảy ra một cuộc đi bộ không dẫn đến điểm 0 là bằng 0. Đây là định lý mà chúng ta đã chứng minh. Câu hỏi về ứng dụng của nó

⟦folio 48⟧

Bước đi ngẫu nhiên trên máy bay và trong không gian

Xét một lưới tam giác trên mặt phẳng; Hãy lấy một con chip và một con xúc xắc (không bị biến dạng). Chúng ta sẽ biểu thị sáu chuyển động có hướng trên lưới bằng các số 1, 2, 3, 4, 5, 6 như trong hình 5. Hãy đặt một con chip vào một trong các nút của lưới và ném một con súc sắc. Hãy di chuyển chip đến nút liền kề theo hướng tương ứng với dấu hiệu của xương. Và sau đó chúng ta ném xúc xắc một lần nữa và hành động theo quy tắc này, v.v. Quá trình này được gọi là bước đi ngẫu nhiên đối xứng trên một lưới tam giác phẳng.

Giả sử rằng Cipollino được ẩn trong một trong các nút lưới và thám tử Mr. Morkovu thực hiện các bước đi đối xứng ngẫu nhiên trên lưới; liệu anh ấy có tìm thấy Cipollino không? Hóa ra trong trường hợp này, thám tử cũng tìm thấy nạn nhân của mình với xác suất là một. Đây cũng là một định lý toán học xuất phát từ lý thuyết xác suất, được mệnh danh là “mọi con đường đều dẫn đến thành Rome”. Chúng tôi không trình bày chứng minh của nó - nó phức tạp hơn một chút so với chứng minh của định lý về bước đi ngẫu nhiên trên một đường thẳng. Kết quả sẽ tương tự đối với một lưới hình vuông phẳng (thay vì xúc xắc thông thường, bạn sẽ phải sử dụng một “xúc xắc” có hình khối đa diện thông thường).

Tuy nhiên, nếu chúng ta đi vào một lưới khối trong không gian và xác định tương tự một bước đi ngẫu nhiên đối xứng trên đó (ở đây một lần nữa
Hình 5.

Hình 7.

Nếu bạn sử dụng một con xúc xắc thông thường - sau cùng, có sáu cạnh xuất hiện từ mỗi đỉnh của lưới hình khối), thì kết quả sẽ hoàn toàn khác. Nếu Cipollino trốn xa thám tử thì xác suất bị trúng đòn sẽ không đáng kể. Đây vốn đã là một định lý khó; chúng tôi sẽ không nói bất cứ điều gì về bằng chứng của nó.

Hai từ về ứng dụng

Bản chất vui tươi của ghi chú này không nên đánh lừa người đọc. Lý thuyết bước đi ngẫu nhiên là một nhánh quan trọng và rất hữu ích của lý thuyết xác suất. Nó được sử dụng thành công trong nghiên cứu các quá trình phát triển khác nhau (trong vật lý, hóa học và thậm chí cả kinh tế). Đặc biệt trong những năm gần đây, khi các quá trình ngẫu nhiên được mô phỏng dễ dàng trên máy tính bằng các cảm biến số ngẫu nhiên. Nó nhận được những ứng dụng hiệu quả và bất ngờ trong việc xác định thực tế các phương trình vi phân cụ thể lời giải bằng cách sử dụng cái gọi là phương pháp Monte Carlo. Nhưng đây là một chủ đề cho một câu chuyện riêng biệt.

Để kết luận, chúng tôi đề xuất hai bài toán.

Nhiệm vụ 7. Cipollino sẽ ẩn náu tại điểm 0, tại điểm N có vực thẳm, còn thám tử Morkov đang ở điểm k (k∈Z, 0<k<N). Thám tử cũng trích dẫn Cipollino theo cách tương tự. Nếu chạm điểm 0, anh ta sẽ tìm thấy Cipollino, còn nếu chạm điểm N, anh ta sẽ rơi xuống vực thẳm (hình 6). Xác suất để thám tử tìm thấy Cipollino là bao nhiêu? Khả năng một thám tử rơi xuống vực thẳm là bao nhiêu?

Gợi ý: Chứng minh rằng (theo ký hiệu cũ)

$$P(k) = \frac{1}{2} P(k-1) + \frac{1}{2} P(k+1),$$
