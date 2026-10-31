---
id: 1983-3-yurskiy-provodyaschaya-sfera-v-zadachah-po-elektrostatike-711337ac
issue: kvant_1983_3
year: 1983
number: "3"
title: Quả cầu dẫn điện trong bài toán tĩnh điện
authors:
  - Юрский С. А.
rubric: shkola-v-kvante
rubric_sub: Школа в «Кванте»
page_first: 33
page_last: 38
page_labels: 31, 32, 34, 35, 36
tag: E51B
lang: vi
source: kvant_digital
extraction: vision
content_sha256: 98b3fb2935f6bceb6543eab4c11d49a0ed4f05b29c490e9e15eb9401f0de4598
prompt_sha256: draft-1
translated_from: content/ru/1983/03/articles/10_yurskiy-provodyaschaya-sfera-v-zadachah-po-elektrostatike-711337ac.md
source_content_sha256: e04e9e7ec0faad90982838bcd0850b4b23ab58ea2ec6e482da979ff8667abab3
translation_model: draft
translation_run: vi-draft-2026-10-31
translation_quality: draft
---

⟦folio 31⟧

Quả cầu dẫn điện trong bài toán máy điện

S. A. YURSKY

Bề mặt hình cầu là một trong những bề mặt đơn giản nhất trong hình học. Gần bề mặt của nó trong tự nhiên có rất nhiều vật thể: Mặt trời và Trái đất, những giọt mưa và quả thanh lương trà, thậm chí cả các electron trong trí tưởng tượng của chúng ta cũng được vẽ dưới dạng những quả bóng nhỏ.

Vật thể hình cầu là một phần của bài toán trong các bài toán về máy điện. Điều này thường là do tính đối xứng hình cầu cho phép sử dụng đáng kể nhiều phép tính toán học mà không ảnh hưởng đến nội dung vật lý.

Trước khi tiến hành phân tích bài toán cụ thể, chúng ta sẽ thảo luận một số vấn đề chung của máy điện.

Trong một hệ vật thể cô lập, bất kể có thay đổi gì trong đó, tổng đại số của điện tích dương và điện tích âm vẫn không đổi.

Tương tác điện có thể được mô tả một cách định lượng. Trong trường hợp đơn giản nhất gồm hai điện tích chính xác $q_1$ và $q_2$, nằm trong chân không cách nhau $r$, lực tương tác giữa chúng được xác định bởi định luật Coulomb

$$F = k \frac{q_1 q_2}{r^2},$$

trong đó $k$ là hệ số, tùy thuộc vào việc lựa chọn hệ đơn vị. Trong SI nó được viết là $k = 1 / (4\pi\varepsilon_0)$ (ở đây $\varepsilon_0$ là hằng số điện). Tất nhiên, các điện tích không chính xác cũng tác dụng lên nhau, nhưng cường độ tương tác của chúng không còn được xác định bởi công thức đã cho. Trong trường hợp này, các vật tích điện phải được chia thành các điện tích chính xác, tìm lực tương tác cho từng cặp điện tích, sau đó cộng tất cả các giá trị thu được.

Như bạn đã biết, các điện tích tương tác thông qua điện trường mà chúng tạo ra. Để mô tả định lượng trường này, các đặc tính năng lượng và hợp nhất được sử dụng: cường độ trường và thế năng của nó. Điện áp $\vec{E}$ của trường tại một điểm cho trước bằng lực tác dụng lên một điện tích dương đơn vị đặt tại điểm này, và thế năng $\phi$ của một điểm cho trước bằng công thực hiện bởi trường để di chuyển một đơn vị điện tích dương từ điểm này đến vô cực, hay tương tự, công của các ngoại lực làm di chuyển một đơn vị điện tích dương từ vô cực đến một điểm cho trước. Khi nói “vô cực”, chúng tôi muốn nói đến một vùng không gian thực sự cách xa mọi điện tích và không có trường trong đó.

Từ định nghĩa về tiềm năng ở trên, rõ ràng rằng chỉ có sự khác biệt tiềm năng giữa các điểm đang được xem xét là có tầm quan trọng thực tế chứ không phải giá trị tuyệt đối của tiềm năng của các điểm. Vì vậy, phần đầu của báo cáo tiềm năng có thể được chọn tùy ý. Theo quy luật, điện thế của một điểm ở vô cực hoặc điện thế của bất kỳ điểm nào được nối bằng dây dẫn với Trái đất (nghĩa là điểm nối đất) được coi là bằng 0. Về vấn đề này, chúng ta hãy nói một chút về các vật thể nối đất.

Trái đất là một vật thể dẫn điện có kích thước khổng lồ. Nó có điện tích âm đáng kể. Một điện tích không gian dương khác được chứa trong khí quyển, ở tầng cao cỡ hàng chục km. Tại bề mặt Trái đất, cường độ trường là ≈ 130 V/m. Coi Trái đất là một quả cầu dẫn điện và biết cường độ trường ở bề mặt, chúng ta có thể ước tính độ lớn điện tích của Trái đất:

⟦folio 32⟧

$Q_3 \approx 6 \cdot 10^5$ C và thế năng của nó: $\varphi_3 \approx 8 \cdot 10^8$ V. Thuật ngữ “vật thể được nối đất” có nghĩa là nó được nối với Trái đất bằng một dây dẫn. Với kết nối như vậy, điện tích và thế năng của Trái đất thực tế không thay đổi, mặc dù một số điện tích có thể chuyển từ cơ thể sang Trái đất hoặc ngược lại. Vì Trái đất được so sánh với bất kỳ vật thể không gian nào trên trái đất đến vô cùng và thế năng của nó là không đổi, nên chúng tôi đồng ý coi thế năng này là bằng không. Vì vậy, nối đất dây dẫn có nghĩa là cho nó điện thế bằng không.

Để có được mô hình điện áp sạc

$$E = \frac{q}{4\pi\varepsilon_0 r^2}$$

và tiềm năng

$$\varphi = \frac{q}{4\pi\varepsilon_0 r}.$$

Tất cả các dữ kiện thực nghiệm đều chỉ ra rằng điện trường có một tính chất thay thế: điện trường của một hệ các nguồn là tổng các trường của các nguồn riêng lẻ. Nói cách khác, trường của mỗi điện tích cố định không phụ thuộc vào sự có mặt của các điện tích khác. Để tìm cường độ thu được tại một điểm nhất định, chỉ cần cộng vectơ cường độ của trường được tạo ra tại điểm này bằng các điện tích riêng lẻ là đủ. Để tìm tổng thế năng, tại một điểm nhất định, chỉ cần lấy tổng đại số của các điện thế được tạo ra bởi mỗi điện tích riêng biệt là đủ, và điểm có điện thế bằng 0 tất nhiên phải chung cho mọi điện tích. Nguyên tắc tìm trường kết quả này được gọi là nguyên tắc chồng chất.

Điện trường thường được mô tả bằng đồ họa bằng cách sử dụng các đường sức căng (đường sức) hoặc sử dụng các bề mặt tiềm năng tương đương. Các đường sức luôn vuông góc với các bề mặt đẳng thế, do đó, khi biết một hình ảnh, bạn có thể dễ dàng thu được một hình ảnh khác.

Từ "dây dẫn" thường có nghĩa là vật dẫn điện, nghĩa là chứa điện tích tự do, thân có kích thước và hình dạng bất kỳ, thường là kim loại. Bên trong một dây dẫn đặt trong điện trường, hướng của điện trường luôn bằng 0 và mọi điểm của dây dẫn đều có cùng điện thế. Sự vắng mặt của trường trong vật dẫn không có nghĩa là từ trường bên ngoài không xuyên qua nó. Hoàn toàn ngược lại, nhờ sự xuyên qua của trường vào dây dẫn, các điện tích xuất hiện trên bề mặt của nó, trường bên trong dây dẫn bù cho trường bên ngoài. Vì vậy, các điện tích tự do trong vật dẫn chỉ có thể nằm trên bề mặt của nó.

Để mô tả khả năng tích lũy điện tích của dây dẫn, một đại lượng vật lý đặc biệt được đưa ra - công suất điện. Tụ điện có công suất điện lớn - một hệ thống gồm hai dây dẫn (được ngăn cách bởi một lớp điện môi mỏng) được tích điện với các điện tích bằng nhau nhưng khác nhau. Điện dung của tụ điện $C$ được gọi là tỷ số giữa điện tích $q$ của một trong các vật dẫn với hiệu điện thế $\Delta \varphi$ giữa chúng: $C = q / (\Delta \varphi)$. Nó phụ thuộc vào kích thước, hình dạng và vị trí tương đối của dây dẫn cũng như tính chất điện của chất điện môi.

Bây giờ hãy chuyển sang lời giải cụ thể bài toán.

Bài tập 1. Một quả cầu kim loại mỏng có bán kính $R$ đồng dạng với mặt phẳng $o$. Chứng minh rằng cường độ trường tại một điểm bất kỳ bên trong quả cầu bằng không. Tìm sự phụ thuộc của lực căng và thế năng vào khoảng cách $r$ (tính từ tâm quả cầu) bên trong và bên ngoài quả cầu. Xây dựng các đồ thị tương ứng.

Đầu tiên chúng ta chứng minh rằng cường độ trường bên trong quả cầu bằng không. Để làm điều này, hãy lấy một điểm tùy ý $A$ và dựng hai hình nón đối xứng có các góc nhỏ giống hệt nhau ở đỉnh, như trong Hình 1. Các phần hình cầu nhỏ $S_1$ và $S_2$ được cắt ra trên bề mặt của hình cầu hình nón, có thể được coi là phẳng. Các hình nón giống nhau vì các góc ở đỉnh bằng nhau. Từ sự giống nhau suy ra rằng

⟦folio 34⟧

những lĩnh vực không có lĩnh vực, không có công việc nào được thực hiện, tức là không có gì được thêm vào công việc đã hoàn thành. Điều này có nghĩa là đối với bất kỳ điểm nào bên trong quả cầu thì điện thế bằng điện thế trên bề mặt của nó. Sự phụ thuộc φ=φ(r) được thể hiện trên Hình 3, b.

Bài toán 2. Một điện tích nhọn +q được đặt ở tâm của một quả cầu dẫn điện không tích điện, bán kính bên trong là a và bán kính bên ngoài là b. Ở đâu và loại phí nào sẽ phát sinh? Hình ảnh mô hình các đường định hướng và thế năng điện trường từ khoảng cách r đến tâm quả cầu.

Hình ảnh cũng là hình ảnh của các đường định hướng bên trong và bên ngoài quả cầu khi điện tích +q trộn lẫn tại một điểm tùy ý bên trong quả cầu.

Khi đưa vào một điện tích +q, các điện tích được cảm ứng ở bề mặt bên trong và bên ngoài của quả cầu. Giả sử chúng lần lượt bằng q₁ và q₂. Người ta biết rằng các đường sức điện trường (đường định hướng) luôn bắt đầu bằng điện tích dương và kết thúc ở điện tích âm. Vì không có trường trong quả cầu chỉ dẫn các bức tường nên không có đường sức nào ở đó. Bên trong quả cầu, các đường sức bắt đầu tại điện tích q và kết thúc tại điện tích cảm ứng q₁

bề mặt bên trong. Suy ra tổng điện tích bên trong quả cầu bằng 0:

$$q + q_1 = 0, \quad q_1 = -q.$$

Đổi lại, từ mật độ electron của quả cầu dẫn điện đối với điện tích trên bề mặt bên ngoài của nó, chúng ta có

$$q_2 = -q_1 = q.$$

Do tính đối xứng nên các điện tích cảm ứng phân bố đều trên cả hai bề mặt của quả cầu. Hình ảnh của đường dây điện trông giống như trong Hình 4.

Để tìm cường độ và thế năng của trường do toàn bộ hệ điện tích tạo ra, chúng ta áp dụng nguyên lý chồng chất. Trường bên ngoài quả cầu trùng với trường tổng cộng của các điện tích điểm q, q₁ và q₂ đặt tại tâm quả cầu. Vì các điện tích cảm ứng có độ lớn bằng nhau và trái dấu: q₁ = -q₂, nên trường tổng chỉ được tạo ra bởi điện tích q:

$$\text{при } r > b \quad E = \frac{q}{4\pi\varepsilon_0 r^2}, \quad \varphi = \frac{q}{4\pi\varepsilon_0 r}.$$

Không có trường bên trong quả cầu, cường độ bằng 0 và điện thế bằng nhau ở mọi điểm và bằng điện thế ở bề mặt ngoài của quả cầu:

$$\text{при } a < r < b \quad E = 0, \quad \varphi = \frac{q}{4\pi\varepsilon_0 b}.$$

Bên trong quả cầu, trường cũng trùng với trường chỉ có điện tích q (vì điện tích q₁ và q₂ bên trong

⟦folio 35⟧

lĩnh vực lĩnh vực không được tạo ra; xem bài toán 1):

tại $r < a$ $E = \frac{q}{4\pi\varepsilon_0 r^2}$, $\varphi = \frac{q}{4\pi\varepsilon_0 r}$.

Đồ thị phụ thuộc $E = E(r)$ và $\varphi = \varphi(r)$ được thể hiện trên Hình 5, a và 6.

Bây giờ chúng ta hãy xem xét câu hỏi cuối cùng bài toán. Khi điện tích $+q$ được trộn từ tâm quả cầu đến một điểm khác, độ lớn của điện tích cảm ứng rõ ràng sẽ giữ nguyên, nhưng mật độ phân bố điện tích trên bề mặt bên trong sẽ thay đổi. Các điện tích âm sẽ được phân phối lại sao cho điện trường ở đỉnh các bức tường vẫn bằng 0. Mật độ của các điện tích này sẽ lớn hơn ở vị trí của bề mặt bên trong, nằm gần điện tích $+q$. Cũng trong khu vực này, quả cầu bên trong sẽ lớn hơn và cường độ của các đường lực sẽ lớn hơn. Vì quả cầu là một bề mặt có điện thế bằng nhau nên các đường sức bị cong để tiếp cận bề mặt đẳng thế theo một góc vuông. Các điện tích ở bề mặt bên ngoài không liên quan gì đến từ trường của quả cầu bên trong; ở đó tổng đóng góp của họ bằng không. Các khoản phí “bên ngoài” vẫn được phân bổ đều. Như vậy, trường của quả cầu bên ngoài không thay đổi; nó không phụ thuộc vào sự phân bố điện tích $+q$ của quả cầu bên trong. Hình ảnh của đường dây điện trong trường hợp này được thể hiện trong Hình 6.

Bài toán 3. Hai quả cầu kim loại đồng tâm có bán kính $R_1$ và

$R_2$ có phí $q_1$ và $q_2$. Vẽ đồ thị lực căng và điện thế theo khoảng cách $r$ đến tâm của hệ.

Hãy xem xét trường hợp một tụ điện hình cầu ($q_1 = -q_2$) và tìm điện dung của nó.

Hãy để $q_1 > q_2$. Sau đó

$$\begin{align*}
\text{при } 0 < r < R_1 & \left\{ \begin{array}{l}
E = 0, \\
\varphi = \frac{1}{4\pi\varepsilon_0} \left( \frac{q_1}{R_1} + \frac{q_2}{R_2} \right);
\end{array} \right. \\
\text{при } R_1 < r < R_2 & \left\{ \begin{array}{l}
E = \frac{q_1}{4\pi\varepsilon_0} r^2, \\
\varphi = \frac{1}{4\pi\varepsilon_0} \left( \frac{q_1}{r} + \frac{q_2}{R_2} \right);
\end{array} \right. \\
\text{при } r > R_2 & \left\{ \begin{array}{l}
E = \frac{q_1 + q_2}{4\pi\varepsilon_0} r^2, \\
\varphi = \frac{q_1 + q_2}{4\pi\varepsilon_0} r.
\end{array} \right.
\end{align*}$$

Các đồ thị tương ứng được thể hiện trên Hình 7, a và 6.

Một tụ điện hình cầu có điện tích bằng nhau và trái dấu: $q_1 = -q_2$. Do đó, điện áp và điện thế ở vùng bên ngoài biến mất và giữa các bản ($\text{при } R_1 < r < R_2$) chúng có dạng

$$E = \frac{q}{4\pi\varepsilon_0} r^2, \varphi = \frac{q}{4\pi\varepsilon_0} \left( \frac{1}{r} - \frac{1}{R_2} \right).$$

Các phụ thuộc $E = E(r)$ và $\varphi = \varphi(r)$ cho trường hợp này được trình bày trên Hình 8, a và 6. Để xác định hệ tụ điện cầu ta sẽ tìm hiệu điện thế trên

⟦folio 36⟧

Xây dựng. Vì thế năng của quả cầu bên ngoài bằng 0 nên hiệu điện thế

$$\Delta \varphi = \frac{q}{4\pi \varepsilon_0} \left( \frac{1}{R_1} - \frac{1}{R_2} \right).$$

Do đó điện dung của tụ điện

$$C = \frac{q}{\Delta \varphi} = 4\pi \varepsilon_0 \frac{R_1 R_2}{R_2 - R_1}.$$

Bài toán 4. Một quả cầu kim loại không tích điện bán kính r bao quanh một vỏ dẫn điện bán kính R có điện thế φ. Điện thế của vỏ sẽ bằng bao nhiêu nếu quả bóng được nối đất (Hình 9)?

Trước khi nối đất, thế năng vỏ φ được tạo ra bởi một số điện tích q: φ = $\frac{q}{4\pi \varepsilon_0 R}$. Vì quả bóng không bị tích điện nên nó có điện thế như nhau. Sau khi tiếp đất, điện thế của quả bóng trở thành bằng không. Điều này có nghĩa là một số loại điện tích đã xuất hiện trên đó. Chúng ta tìm thấy các giá trị của nó $q'$ từ điều kiện tổng điện thế tạo bởi điện tích q và $q'$ trên bề mặt quả bóng bằng 0:

$$\frac{q}{4\pi \varepsilon_0 R} + \frac{q'}{4\pi \varepsilon_0 r} = 0, \text{ и } q' = -\frac{r}{R} q.$$

Bây giờ thật dễ dàng tìm thấy một thế vỏ mới, được tạo ra bởi cùng điện tích q và $q'$:

$$\varphi' = \frac{q}{4\pi \varepsilon_0 R} + \frac{q'}{4\pi \varepsilon_0 R} = \frac{q(R-r)}{4\pi \varepsilon_0 R^2} = \frac{R-r}{R} \varphi.$$

Bài toán 5. Sự cố trong không khí xảy ra trong điện trường có cường độ $E_M = 3 \cdot 10^4 \text{ B/cm}$. Có một tụ điện hình cầu tích điện không khí, lớp vỏ ngoài có bán kính R = 4 cm, bán kính lớp vỏ trong được điều chỉnh sao cho tụ điện không bị xuyên qua ở giá trị chênh lệch điện thế cao nhất có thể. Xác định sự khác biệt tiềm năng tối đa này.
