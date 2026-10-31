---
id: 1975-5-matiyasevich-formulyi-dlya-prostyih-chisel-b3a758a3
issue: kvant_1975_5
year: 1975
number: "5"
title: Công thức cho số nguyên tố
authors:
  - Матиясевич Ю. В.
rubric: osnovnye-stati
page_first: 7
page_last: 15
page_labels: 5-13
tag: TTX4
lang: vi
source: kvant_digital
extraction: vision
content_sha256: 15ba9845bc65c451586f75efc4e9b8b882d54b503ef0e450c5453c9786a5181c
prompt_sha256: draft-1
translated_from: content/ru/1975/05/articles/03_matiyasevich-formulyi-dlya-prostyih-chisel-b3a758a3.md
source_content_sha256: ec6cff0c3f6cfd56b0c70b5480dd1d8a7b8b05addf2bed8fd3707f3b60f25d6c
translation_model: draft
translation_run: vi-draft-2026-10-31
translation_quality: draft
---

⟦folio 5⟧

Những gì được yêu cầu?

Các số nguyên tố nằm rải rác trong chuỗi tự nhiên một cách rất kỳ quái, và không có gì đáng ngạc nhiên khi sản phẩm của các nhà toán học tìm cách tìm ra một “công thức cho số nguyên tố”. Bằng cách này, chúng ta có thể đặt tên cho các công thức có các thuộc tính khác nhau và ở đây, điều rất quan trọng là phải hiểu những gì chúng ta thực sự cần.

Công thức đơn giản nhất cho số nguyên tố có vẻ là:

$$p = p_n,$$

(1)

trong đó $p_n$ biểu thị số nguyên tố thứ $n$. Tại sao công thức này không thành lập chúng ta? Thực tế là phần bên phải của đẳng thức này được tính bằng cách sử dụng hình ảnh - ví dụ: hãy thử tự tìm $p_{1975}$! Chúng tôi muốn có được một công thức tương tự với cách đơn giản nhất có thể để tính vế phải (tuy nhiên, như chúng tôi thấy, tính dễ tính hoàn toàn không phải là một khái niệm). Có thể nói đây là một chương trình mặt nạ.

Để đơn giản hóa công thức, người ta có thể bỏ yêu cầu phụ thuộc rõ ràng vào số $n$ và tìm kiếm các công thức cung cấp số nguyên tố, có thể không theo thứ tự. Hơn nữa, bạn có thể từ chối mong muốn chỉ định tất cả các số nguyên tố cùng một lúc bằng một công thức và chỉ yêu cầu công thức đó đưa ra vô số số nguyên tố. Cuối cùng, có thể giả định rằng công thức này, cùng với vô số số nguyên tố, cũng cho ra các số tổng hợp không hữu hạn. Đây là một chương trình tối thiểu.

Các công thức tưởng chừng rất đơn giản nhưng có thể không phải là công thức tốt nhất (1). Bây giờ chúng ta chuyển sang những ví dụ như vậy.

Định lý của E. M. Wright

Năm 1947, W. H. Mill công bố kết quả sau:

Tồn tại một số thực $\lambda$ sao cho với mọi $n=1, 2, \dots$ số đó

$$[\lambda^{3^n}]$$

(2)

rất đơn giản *).

Sau đó, một số công thức cùng loại xuất hiện. Tuy nhiên, đây đều là những kết quả mà công thức có vẻ hấp dẫn và đầy hứa hẹn, nhưng bằng chứng lại gây thất vọng. Đối với bất kỳ ai muốn hiểu tại sao lại như vậy, chúng tôi khuyên bạn nên xem xét cách chứng minh định lý sau đây của E. M. Wright:

Tồn tại một số thực $\mu$ sao cho mọi số có dạng

$$[2^2 \cdot 2^{\mu}]$$

(3)

thật đơn giản.

Điểm mấu chốt trong việc chứng minh định lý Wright là định đề Bertrand. Theo định đề này thì tại $x \geq 4$ luôn tồn tại giữa $x$ và $2x-2$

*) Ở đây và bên dưới [$\alpha$] biểu thị phần nguyên của số $\alpha$, tức là số nguyên lớn nhất không vượt quá $\alpha$.

⟦folio 6⟧

số nguyên tố. Giả thuyết này lần đầu tiên được đưa ra bởi nhà toán học người Pháp Bertrand: ông không thể chứng minh được nó và do đó sử dụng nó trong lập luận của mình như một cách xây dựng không thể chứng minh được. Chứng minh phỏng đoán của Bertrand sau đó đã được nhà toán học xuất sắc người Nga P. L. Chebyshev * tìm ra).

Để tìm số cần tìm μ, trước tiên chúng ta chọn một dãy số nguyên tố $q_1, q_2, \dots$ sao cho với mọi $n=1, 2, \dots$
$$2^q < q_{n+1} < 2^{q+1} - 1. \quad (4)$$
(Bất kỳ số nguyên tố nào cũng có thể được coi là $q_1$; có thể tiếp tục không giới hạn chuỗi $\{q_n\}$, tuân theo bất đẳng thức (4), đảm bảo cho cách xây dựng của Bertrand.)

Để cho ngắn gọn, chúng ta hãy ký hiệu số
$$2^2,$$
trong đó chúng ta lấy $n$ số mũ, thông qua $\exp^n \alpha$ và hàm nghịch đảo,
$$\log_2 \log_2 \dots \log_2 \beta - \text{через } \log_2^n \beta.$$

Hãy thử chọn số μ sao cho tại $n=1, 2, \dots$
$$[\exp^n \mu] = q_n. \quad (5)$$
Theo định nghĩa phần nguyên của một số thì đẳng thức (5) tương đương với bất đẳng thức
$$q_n \leqslant \exp^n \mu < q_n + 1.$$

Nhân nó $n$ lần trong cơ số 2, ta thu được một bất đẳng thức kép khác tương đương với (5):
$$\log_2^n q_n \leqslant \mu < \log_2^n (q_n + 1). \quad (6)$$

Hãy tự kiểm tra xem điều gì tiếp theo từ (4)
$$\log_2^1 q_1 < \log_2^2 q_2 < \dots < \log_2^n q_n < \log_2^{n+1} q_{n+1} < \dots < \log_2^{n+1} (q_{n+1} + 1) < \log_2^n (q_n + 1) < \dots < \log_2^2 (q_2 + 1) < \log_2^1 (q_1 + 1).$$

Vì vậy trình tự
$$\log_2^1 q_1, \log_2^2 q_2, \dots, \log_2^n q_n, \dots$$
tăng nghiêm ngặt và phạm vi hạn chế; do đó nó có giới hạn. Chúng ta sẽ coi đây là số μ; chứng minh rằng μ được chọn thỏa mãn bất đẳng thức thậm chí còn mạnh hơn (6)
$$\log_2^n q_n < \mu < \log_2^n (q_n + 1), \quad (7)$$
và do đó, đẳng thức (5) là đúng. Định lý Wright đã được chứng minh.

Nhược điểm chính của công thức (2) và (3) là chúng (chính xác hơn là chứng minh của chúng) không đưa ra bất kỳ

*) Bạn có thể đọc về cách chứng minh này trong bài viết của M. I. Bashmkov, «Kvant», 1971, số 5.

phương pháp tìm số nguyên tố hoặc để tính bất kỳ số nguyên tố nào bằng công thức (2) hoặc (3), số λ và μ được yêu cầu phải được biết với độ chính xác vừa đủ. Do đó, công thức (2) và (3) theo một số nghĩa chỉ là phiên bản trá hình (và tệ hơn) của công thức (1). Ngoài ra, dạng công thức (2) và (3) thực tế hầu như không nói gì cụ thể về tập hợp số nguyên tố. Từ việc chứng minh định lý Wright, rõ ràng là các công thức tương tự như (2), (3) có thể được xác định cho bất kỳ tập hợp “đủ dày đặc” nào.

Nhược điểm của công thức (2) và (3) xuất phát từ thực tế là chúng bao gồm các số thực λ và μ, được xác định theo một cách gián tiếp nào đó. Trong phần tiếp theo, chúng ta sẽ chỉ xem xét các công thức chỉ bao gồm các hệ số nguyên. Những công thức như vậy có một ưu điểm quan trọng: chúng có thể (về nguyên tắc) được viết ra một cách rõ ràng:

Số nguyên tố Mersenne và Fermat
Các công thức của Millas, Wright và các công thức tương tự khác vẫn là những sự thật biệt lập và không dẫn đến kết quả mới. Tuy nhiên, trong những trường hợp khác, khả năng biểu diễn một số số nguyên tố dưới dạng đặc biệt này hay dạng đặc biệt khác lại gây ra những hậu quả bất ngờ và sâu sắc.

Bây giờ chúng ta hãy xem xét hai công thức có dạng đơn giản tương thích:
$$p = 2^n - 1, \quad (8)$$
$$p = 2^n + 1. \quad (9)$$

Rõ ràng, công thức (8) không phải lúc nào cũng cho số nguyên tố; ví dụ: nếu $n$ là hợp số, $n = kl, k > 1, l > 1$ thì $p$ chia hết cho $2^k - 1$ và $2^l - 1$. Nhưng ngay cả với $n$ đơn giản thu được từ công thức (8), số này có thể là hợp số:
$$2^{11} - 1 = 2047 = 23 \cdot 89.$$

Các số nguyên tố thu được theo công thức (8) được gọi là số Mersenne trong Marin Mer-

⟦folio 7⟧

Senna, người quay lại năm 1664 đã chỉ ra tất cả các giá trị nguyên tố $n$ không vượt quá 257, theo quan điểm của ông, công thức (8) cho các số nguyên tố. Tuy nhiên, Mersenne không đưa ra bằng chứng; sau đó người ta phát hiện ra rằng dự đoán của ông đã sai một phần.

Sự quan tâm đến số Mersenne là do mối liên hệ của chúng với cái gọi là số hoàn hảo - những con số bằng tổng của tất cả các ước của chúng, tất nhiên, khác với chính số đó. Euclid cũng đã chứng minh (bằng chứng và bạn) rằng nếu số nguyên tố $p$ có dạng như công thức (8) thì số $p \cdot (p+1)/2$ là số hoàn hảo. Ví dụ,

$$3 = 2^2 - 1, \quad 7 = 2^3 - 1$$

là các số nguyên tố và do đó

$$6 = (3 \cdot 4)/2 = 1 + 2 + 3, \quad 28 = (7 \cdot 8)/2 = 1 + 2 + 4 + 7 + 14$$

- những con số hoàn hảo Vài thế kỷ sau, Leonhard Euler đã chứng minh (hãy thử dùng tay của ông ở đây) rằng tất cả các số hoàn hảo chẵn đều có dạng như Euclid chỉ ra. Do đó, câu hỏi liệu tập hợp bốn số hoàn hảo là hữu hạn hay vô hạn đã được rút gọn thành câu hỏi liệu tập hợp số nguyên tố Mersenne là hữu hạn hay vô hạn, nghĩa là câu hỏi liệu công thức (8) có thực hiện được chương trình tối thiểu của chúng ta hay không. Đáp số câu trả lời cho câu hỏi này vẫn chưa được biết *).

Công thức (9) không phải lúc nào cũng cho ra số nguyên tố, ví dụ: nếu $n$ có ước số lẻ đơn giản $m$ thì $p$ chia hết cho $2^{m/2} + 1$ và nếu $n$ là số lẻ thì $p$ chia hết cho 3. Do đó, thay vì $n$ trong công thức (9), bạn chỉ nên thay thế 0 và lũy thừa của số 2. Vì công thức $n=0, 2^0, 2^1, 2^2, 2^3$ và $2^4$ (9) thực sự cho ra các số nguyên tố, và Pierre

*) Bạn có thể đọc về lịch sử và hiện trạng nghiên cứu về số hoàn hảo và số nguyên tố Mersenne trong bài viết của I. Ya. Depman, «Kvant», 1971, số 8.

Form, người sống ở thế kỷ 17, đã đề xuất rằng với bất kỳ $n$ nào có dạng $2^k$ thì công thức (9) sẽ cho một số nguyên tố; trong đó các số nguyên tố có dạng $2^{2k} + 1$ được gọi là số Fermat. Giả thuyết của Fermat đã bị Euler bác bỏ, người chỉ ra rằng số $2^{25} + 1$ chia hết cho 641. Hiện tại, một số giá trị của $n$ có dạng $2^k$ đã được biết, tại đó các số tổng hợp thu được bằng công thức (9), nhưng không tìm thấy một số Fermat nguyên tố mới nào, khác với những giá trị được chỉ ra ở trên.

Số nguyên tố Fermat tiết lộ mối liên hệ bất ngờ với hình học Nhà toán học xuất sắc người Đức Carl Friedrich Gauss đã chứng minh rằng một $p$-giác đều có thể được dựng bằng một chu trình và thước cho số nguyên tố $p$ khi và chỉ khi $p$ là số Fermat*). Một kết quả tổng quát hơn là thế này: một $m$-giác đều có thể được dựng bằng một đường tròn và một thước thẳng khi và chỉ khi $m=2^s \cdot p_1p_2 \dots p_l$, trong đó $p_1, p_2, \dots, p_l$ là các số nguyên tố Fermat phân biệt theo cặp.

Khăn trải bàn Ulama

Công thức (8) và (9) chứa lũy thừa. Không thể thực hiện được các nhiệm vụ có vô số nhiệm vụ chỉ bằng phép cộng, phép trừ và phép nhân sao? Hãy tìm đáp số cho câu hỏi này.

Hãy bắt đầu bằng việc xem xét đa thức một biến có hệ số tự nhiên; Chúng ta hãy xem đa thức nào sẽ có tính chất và số lượng là bao nhiêu.

Trước tiên chúng ta hãy lấy đa thức bậc một (tức là đa thức tuyến tính). Rõ ràng, đa thức rút gọn $x$ xác định vô số đa thức, hơn nữa là tất cả các số nguyên tố, nhưng đây là một trường hợp không mấy thú vị. Chúng ta có thể nói gì về đa thức $ax + b$ (trong đó $a, b$ và $x$ là số tự nhiên)? Rõ ràng là nếu $a$ và $b$ có ước chung thì khác nhau

*) Khám phá này của Gauss khi đó còn rất trẻ được mô tả chi tiết hơn trong bài viết của S. G. Gindikna, «Kvant», 1972, No. 1.

⟦folio 8⟧

Cơm. 1.

từ 1 thì giá trị của đa thức $ax + b$ là hợp số là bội số của ước số này. Trường hợp $a$ và $b$ tương đối nguyên tố thì ít được đánh giá cao hơn nhiều.

Nhà toán học người Pháp Legendre (sống ở thế kỷ 18) đã đưa ra giả thuyết rằng nếu $a$ và $b$ là nguyên tố cùng nhau, thì trong một chương trình số học có số hạng đầu tiên $b$ và hiệu $a$ sẽ có vô số số nguyên tố. Giả thuyết này chỉ được chứng minh vào thế kỷ trước bởi nhà toán học người Đức Lejeune Dirichlet.

Bây giờ chúng ta chuyển sang đa thức bậc hai. Trong số đó có những “người giữ kỷ lục”, ví dụ như đa thức $x^2 + x + 41$ - nó đã được nghiên cứu bởi Leonard Euler. Đa thức này lấy giá trị nguyên tố ở $x = 1,2,...,40$. Khi $x=41$ giá trị của nó là tổng hợp.

Người ta đã chứng minh rằng không có đa thức nào (tất nhiên ngoài cấu trúc) chỉ có thể có giá trị là số nguyên tố, nhưng vẫn chưa biết liệu có đa thức (không phải đa thức tuyến tính) trong số các giá trị của nó có vô số số nguyên tố hay không.

⟦folio 9⟧

Pris. 2

Pris. 3.

Gần đây, mối quan tâm đến việc biểu diễn các số nguyên tố dưới dạng giá trị của đa thức bậc hai đã nảy sinh liên quan đến một quan sát cần thiết của S. M. Ulam*). Khi bắt đầu đánh dấu các số nguyên tố trên một đường xoắn ốc toàn số tự nhiên (Hình 1), Ulam rất ngạc nhiên khi phát hiện ra các số nguyên tố được sắp xếp dọc theo các đường chéo, tạo thành những chuỗi khá dài. (Chứng minh rằng các số nằm dọc theo đường chéo bất kỳ nằm trong giới hạn bởi vạch đỏ trên Hình 1 là giá trị của một số đa thức bậc hai có hệ số nguyên). Điều đáng ngạc nhiên hơn nữa là mô hình này cũng được quan sát thấy khi đường xoắn ốc được mở rộng (với sự trợ giúp của máy tính) thành các số lớn - trong Hình 2, các chấm sáng đánh dấu các số nguyên tố trên đường xoắn ốc từ 10.000 số đầu tiên. Mẫu hiển thị trong Hình 2 được gọi là “khăn trải bàn Ulama”.

Để mẫu được ghi chú xuất hiện, không cần thiết phải bắt đầu đường xoắn ốc bằng một đơn vị. Ví dụ: các giá trị của đa thức $x^2 + x + 41$ được sắp xếp dọc theo các đường chéo của hình xoắn ốc bắt đầu bằng số 41 (Hình 3). Rất có thể độc giả của «Kvant», với sự khéo léo và kiên nhẫn thích đáng, sẽ có thể tìm ra những mẫu “hình học” màu đỏ mới để sắp xếp các số nguyên tố giữa số nhiều của tất cả các số.

Hiện tượng các số nguyên tố có xu hướng tạo thành chuỗi dọc theo các đường chéo được phát hiện tương đối gần đây và chưa nhận được bất kỳ lời giải thích toán học nào.

Chúng ta sẽ nói về việc biểu diễn số nguyên tố bằng đa thức nhiều biến ở cuối bài.

Đa thức hàm mũ của Julia Robinson

Đa thức hàm mũ khác với đa thức thông thường ở chỗ số mũ của chúng không chỉ có thể là số tự nhiên cụ thể mà còn có thể là đa thức tuyến tính trong các biến có hệ số tự nhiên, tức là đa thức có dạng $a_1x_1 + a_2x_2 + \ldots + a_kx_k + b$, trong đó $a_1, a_2, \ldots, a_k, b$ là số nguyên không âm.

Ví dụ đơn giản nhất về đa thức mũ trong biến $n$ là quy tắc của phần công thức (8) và (9).

Trong tương lai, chúng ta sẽ luôn tưởng tượng rằng tất cả các biến chúng ta gặp đều có giá trị nguyên dương.

Năm 1952, nhà toán học người Mỹ Julia Robinson*) đã công bố kết quả sau:

*) Đây là cách quan sát này được thực hiện, M. Gardner kể một cách đầy màu sắc trong “Giải trí toán học”, M., “Mir”, 1972.

⟦folio 10⟧

Có một đa thức hàm mũ $R(x_0, \dots, x_h)$ sao cho bất kỳ giá trị dương nào của nó đối với các giá trị nguyên dương của các biến đều là số nguyên tố; Bất kỳ số nguyên tố nào cũng có thể được biểu diễn dưới dạng này.

Kết quả là “công thức tính số nguyên tố” sau:

$$p = R(x_0, \dots, x_h).$$

Công thức này được thay thế bằng cái này. Thứ nhất, nó chỉ bao gồm các số nguyên, và do đó, không giống như các công thức của Mills, Wright và những thứ tương tự, công thức Julia Robinson có thể được viết ra một cách rõ ràng. Thứ hai, nó chỉ định tất cả các số nguyên tố chứ không chỉ một số số nguyên tố được chọn, không giống như tất cả các công thức đã thảo luận ở trên. Thứ ba, mặc dù công thức (10) không chỉ xác định các số nguyên tố, nhưng chúng ta có một cách rất đơn giản để lọc ra các số “phụ”: mỗi giá trị không nguyên tố $R$ cho các giá trị nguyên dương của ẩn số không vượt quá 0. Bằng cách này, công thức của Julia Robinson so sánh thuận lợi với các công thức (8) và (9), cũng như với các công thức đầy đủ vừa được xem xét *).

Chứng minh của Julia Robinson khá đơn giản. Ý tưởng chính của nó được nêu dưới đây; Chúng tôi giao nhiệm vụ đưa bằng chứng đến mức chính xác về mặt hình thức cho người đọc: tất cả các kết quả trung gian đều được xây dựng dưới dạng năm bổ đề, và đây là những kết quả cần được chứng minh. Như chúng ta sẽ thấy, những bổ đề này không chỉ ngụ ý sự tồn tại của đa thức hàm mũ $R$ mà còn cả dạng rõ ràng của nó.

Chúng ta nên làm gì?

Để chứng minh định lý Julia Robinson, rõ ràng chúng ta phải chỉ định một đa thức hàm mũ $R$ sao cho phương trình (10) có thể giải được

*) Công thức đầy đủ là công thức được cho bởi đa thức.

trong các số tự nhiên đối với các biến $x_0, \dots, x_h$ khi và chỉ khi điều kiện sau được thỏa mãn:

$$p - \text{простое число.}$$

Đây là ví dụ về điều kiện trên biến $p$.

Dưới đây là một vài ví dụ khác về điều kiện trên một tập hợp các biến:

$$\lambda_1, \dots, \lambda_n, x_0, \dots, x_h.$$

Nếu ta yêu cầu tập hợp số (11) thỏa mãn hệ phương trình dạng

$$F_i(\lambda_1, \dots, \lambda_n, x_0, \dots, x_h) = 0$$

($i=1, \dots, s$), (11'')

hoặc giả sử mô tả bằng lời như: “tất cả $\lambda_i$ đều là số nguyên tố” hoặc “$\lambda_1$ là số nguyên tố, $ax_0, \dots, x_h$ là số nguyên,” v.v., thì từ tập hợp tất cả các bộ (11''), chúng ta sẽ chọn một số điều kiện phụ cho chúng.

Chúng tôi sẽ không xác định chính xác loại điều kiện nào được chúng tôi chấp nhận. Mô tả các ví dụ về phương trình đã cho để xác định phương pháp hành động mà chúng ta sẽ sử dụng trong tương lai.

Trong phần trình bày sau đây, chúng ta sẽ phân biệt giữa các biến, gọi một số biến trong số chúng là tham số, do đó việc chia biến thành tham số và ẩn số hoàn toàn có điều kiện.

Nếu tất cả vế trái của hệ phương trình (11'') là đa thức hàm mũ trong $\lambda_1, \dots, \lambda_n, x_0, \dots, x_h$, và lời giải của hệ này được tìm kiếm dưới dạng số nguyên dương, thì hệ như vậy được gọi là Diophantine hàm mũ; nếu $F_i$ là các đa thức tổng quát thì hệ phương trình (11'') được gọi đơn giản là Diophantine.

Phương trình (10) là một ví dụ về phương trình Diophantine hàm mũ đối với các biến $p, x_0, \dots, x_h$.

Chúng ta sẽ nói rằng hai hệ phương trình có cùng tham số tương đương với hệ phương trình khác về các tham số này nếu tập hợp các giá trị tham số mà chúng ta có lời giải một trong các hệ thống này trùng với tập hợp các giá trị tham số mà chúng ta có lời giải và hệ kia. (Lưu ý rằng chúng tôi không nói bất cứ điều gì trong định nghĩa này.)

⟦folio 11⟧

Đó là về mối liên hệ giữa các giá trị của những ẩn số—đối với mục đích của chúng tôi, điều này không quan trọng; các hệ thống tương đương theo hiểu biết của chúng ta có thể không có ẩn số chung nào cả.)

Một ví dụ về điều kiện tương đương cho tham số $\lambda$ có thể là bất đẳng thức

$$2^n < \lambda < 2^{n+1}$$

và bình đẳng

$$\lambda = (2x_0 + 1) \cdot x_1.$$

Rõ ràng là mỗi điều kiện này có lời giải khi và chỉ nếu tham số $\lambda$ thuộc tập hợp các số không phải là số nguyên lũy thừa 2.

Trong thuật ngữ này, mục tiêu của chúng tôi được xây dựng như sau: tìm một đa thức tương đương $R(x_0, \dots, x_h)$ sao cho điều kiện (10) tương đương với điều kiện (11) đối với tham số $p$.

Tuy nhiên, yêu cầu tham số $p$ chỉ xuất hiện ở vế trái của đẳng thức (10), như chúng ta sẽ thấy, là nghiêm ngặt một cách không cần thiết.

Hãy thỏa mãn điều này: tìm một đa thức tương đương $Q(p, x_1, \dots, x_h)$ sao cho phương trình Diophantine tương đương (điều kiện trên $p, x_1, \dots, x_h$)

$$Q(p, x_1, \dots, x_h) = 0$$

(12) tương đương với điều kiện (11).

Hãy đặt

$$R(x_0, \dots, x_h) = x_0 \cdot (1 - Q^2(x_0, \dots, x_h)).$$

Bổ đề 1. Nếu các đa thức tương đương $R$ và $Q$ có liên hệ bởi quan hệ (13), thì phương trình (10) và (12) tương đương với tham số $p$.

Chúng ta thậm chí không cần tìm một phương trình là đủ, mà ít nhất là một hệ phương trình Diophantine tương đương

$$\begin{cases} Q_1(p, x_1, \dots, x_h) = 0, \\ Q_l(p, x_1, \dots, x_h) = 0, \end{cases}$$

tương đương với điều kiện (11) đối với $p$.

Bổ đề 2. Nếu

$$Q(p, x_1, \dots, x_h) = \sum_{i=1}^{l} Q_i^2(p, x_1, \dots, x_h),$$

trong hệ (14) tương đương với phương trình (12).

Chúng ta sẽ nghiên cứu hệ phương trình Diophantine tương đương của Nhật Bản tương đương với điều kiện (11).

Số nguyên tố là gì?

Một câu hỏi lạ, người đọc sẽ ngạc nhiên. Mọi người đều biết số nguyên tố là số lớn hơn số 1, chỉ chia hết cho 1 và chính nó. Tất nhiên, điều này đúng, nhưng định nghĩa như vậy không dễ thực hiện - xét cho cùng, nó giả định rằng việc kiểm tra tính nguyên tố của một số bao gồm việc thử vô số các ước số tiềm năng - tất cả các số tự nhiên ngoại trừ 1. Đối với mục đích của chúng tôi, định nghĩa sau đây phù hợp hơn:

một số $p$ là số nguyên tố nếu $p > 1$ và $p$ không chia hết cho bất kỳ số nào nhỏ hơn $p$ và khác 1.

Không có ràng buộc $q \neq 1$ trong định nghĩa này và quan trọng hơn, nó cho phép một số lượng phương trình H.O.D thay đổi. (1, $p$) = 1, H.O.D. (2, $p$) = 1, ..., H.O.D. (p - 1, $p$) = 1 rút gọn thành một điều kiện:

H.O.D.((p - 1)!, $p$) = 1.

Nhận xét đưa ra cho phép chúng ta viết hệ phương trình đầu tiên tương đương với điều kiện (11) đối với tham số $p$:

$$\begin{cases} p = r + 1, \\ s = r!, \\ H.O.Д. (s, p) = 1. \end{cases}$$

Điều kiện đầu tiên trong số này có dạng duy nhất của phương trình Diophantine (hơn nữa là Diophantine), và điều kiện thứ ba có thể dễ dàng rút gọn về dạng tương tự bằng cách đưa vào hai ẩn số mới:

*) H.O.D. (a, b) là ước số chung nhất của các số $a$ và $b$.

⟦folio 12⟧

Bổ đề 3. Điều kiện (17) tương đương với các tham số tương đối $r$ và điều kiện $s$

$$x_1 \cdot s - x_2 \cdot p = 1^*).$$

Vì phương trình (18) là Diophantine hàm mũ nên ta chỉ cần tìm hệ phương trình Diophantine hàm mũ tương đương với các tham số tương đối $r$ và $s$ của điều kiện (16).

Làm thế nào để tính giai thừa?

Điều kiện (16) bao gồm $r!$; Chính giai thừa này đã “làm phiền” chúng ta. Hãy nhớ lại rằng hàm giai thừa trong biểu thức cho hệ số biomp**): tại $t \geq r$

$$C_t^r = \frac{t(t-1) \dots (t-r+1)}{r!},$$

đó là

$$r! = \frac{t(t-1) \dots (t-r+1)}{C_t^r}.$$

Đa thức trong tử số có cấu trúc khá phức tạp. Hãy thử thay thế nó bằng một cái đơn giản hơn—cụ thể là đa thức $t^r$. Với $t \geq r$ chúng ta có:

$$\frac{t^r}{C_t^r} = \frac{t^r}{t(t-1) \dots (t-r+1)} \times \frac{t(t-1) \dots (t-r+1)}{C_t^r} = \left(1 + \frac{1}{t-1}\right)\left(1 + \frac{2}{t-2}\right) \times \dots \times \left(1 + \frac{r-1}{t-r+1}\right) \cdot r! \geq r!.$$

Thật dễ dàng để thấy điều đó

$$r! = \lim_{t \to \infty} \frac{t^r}{C_t^r},$$

(*) So sánh bổ đề này với Bổ đề 2 từ «Kvant» Số 6 năm 1972, tr. 33.

**) Anh ấy không nói về tính chất của hệ số biomp «Kvant»; xem, chẳng hạn, số 6, 1970, tr. 17-25, hoặc số 2 cho năm 1973, tr. 27-34.

tuy nhiên, việc ghi lại hệ số này không mang lại cho chúng ta bất cứ điều gì, vì $t$, là một tham số trong hệ phương trình ban đầu, có thể nhận bất kỳ giá trị nào, tuy nhiên nhiều hơn, nhưng có giá trị hữu hạn. Nhưng chúng ta sẽ không tiến hành giới từ mà sẽ sử dụng giá trị nguyên $r!$ - từ (19) và (20) nó theo sau để đủ lớn $t$

$$r! = \left[ \frac{t^r}{C_t^r} \right].$$

Bổ đề 4. Công thức (21) đúng như sữa $t \geq 2 r^{r+2}$.

Bổ đề 4 cho phép chúng ta chuyển đổi các điều kiện (16) thành một hệ tương đương với các tham số $r$ và $s$ (kiểm tra sự tương đương!)

$$\begin{cases} t = 2r^{r+2}, \\ c = C_t^r, \\ t^r = s \cdot c + (x_3 - 1), \\ (x_3 - 1) + x_4 = c. \end{cases}$$

Ở đây các điều kiện (22), (24) và (25) có dạng theo yêu cầu, và tất cả những gì chúng ta phải làm là tìm một hệ phương trình Diophantine hàm mũ tương đương với điều kiện (23) đối với các tham số $r$, $t$ và $c$.

Vì vậy, tất cả những gì chúng ta phải làm là “loại bỏ” hệ số biomp.

Hệ số quần xã là hệ số quần xã!

Chúng ta vừa sử dụng biểu thức hệ số biomp thông qua giai thừa; nhưng hệ số biomp có nhiều định nghĩa khác. Bây giờ chúng ta hãy sử dụng nó

$$(u + 1)^t = \sum_{i=0}^{t} C_t^i u^i.$$

Công thức này là định nghĩa của hệ số biomp nếu được coi là đa số đối với $u$. Nhưng chúng ta cần $u$ là một ẩn số chỉ lấy một giá trị làm phần tử cụ thể lời giải của hệ ban đầu.

⟦folio 13⟧

Lưu ý rằng
$$C_t^i \leq \sum_{i=0}^{t} C_t^i = (1+1)^t = 2^t,$$
và do đó nếu
$$u > 2^t,$$
thì $C_t^0, C_t^1, \dots, C_t^t$ là các chữ số trong ký hiệu của số $(u+1)^t$ trong hệ số vị trí có cơ số $u$.
Do đó, các hệ số biomp được xác định duy nhất bởi điều kiện đẳng thức (26) và bất đẳng thức (27) và (28) được thỏa mãn đồng thời với ít nhất một giá trị $u$.

Bổ đề 5. Điều kiện (23) tương đương với các tham số tương đối $r, t$ và $c$ của hệ điều kiện
$$\begin{cases} u = 2^t + 1, \\ x_5 = u + 1, \\ x_5^t = x_6 u^{r+1} + cu^r + x_7, \\ x_7 + x_8 = u^r, \\ c + x_9 = u. \end{cases}$$

Ở đây tất cả các điều kiện đã có dạng chúng ta cần.

Vì vậy, chúng tôi đã chỉ ra rằng các điều kiện (11) tương đương với hệ tham số tương đối $p$, bao gồm các phương trình Diophantine hàm mũ (15), (18), (22), (24), (25), (29) - (33). Để thu được đa thức hàm mũ cần thiết, vẫn phải thay đổi các biến $r, s, t, c$ và $u$ thành $x_{10}, x_{11}, x_{12}, x_{13}, x_{14}$, kết hợp tất cả các phương trình thành một theo Bổ đề 2 và biến đổi phương trình này để sử dụng dạng (10) theo Bổ đề 1.

Các bước tiếp theo
Công thức (10) không chứa rõ ràng số nguyên tố được chỉ định. Phương pháp được mô tả ở trên để xây dựng đa thức mũ $R$ không cung cấp cách trực tiếp để đưa số nguyên tố vào công thức (10). Sử dụng những kỹ thuật phức tạp hơn nhiều, Martin Davis, Hilary Putnam, và Julia Robinson vào năm 1961 đã chứng minh một định lý rất mạnh mẽ và có những hệ quả như vậy.

Có một đa thức hàm mũ $P(x_0, \dots, x_k, n)$ sao cho với mọi giá trị cố định của tham số $n$ và các giá trị tùy ý của các biến khác, đa thức $P$ nhận một giá trị dương và giá trị này là số nguyên tố thứ $n$.

Năm 1970, tác giả bài viết này đã có thể sử dụng các kết quả khác của Julia Robinson để xây dựng phương trình Diophantine sau:
$$M(a, b, c, z_1, \dots, z_m) = 0,$$
(34) có thể giải được khi và chỉ nếu các tham số $a, b$ và $c$ có liên hệ với nhau bởi hệ thức $a = b^c$. Kết quả này cho phép chúng ta áp dụng từ “số mũ” trong công thức của định lý trước đó, tức là cho phép xây dựng một đa thức cho trước các số nguyên tố. Tuy nhiên, chúng ta sẽ nói về điều này vào lúc khác. Bạn đọc quan tâm đến những chủ đề như vậy và không ngại khó có thể thử tự tìm hiểu trong bài viết của tác giả “Đa số Diophantine”, đăng trên tạp chí “Thành công của khoa học toán học”, XXVII, số 5, 1972.

Chủ đề suy nghĩ
1. Chứng minh rằng cấp số biến phân là 3, 7, 11, . . . và 5, 11, 17, . . . có vô số số nguyên tố.
2. Tập hợp các đa thức có giá trị nằm dọc theo đường chéo là bao nhiêu nếu đường xoắn ốc (xem trang 9) bắt đầu từ 1? từ một số $u$? từ một số nhất định $u$, và dọc theo đường xoắn ốc có một thành viên của cấp số cộng $u, u + v, u + 2v, \dots$?
3. Định lý Wilson phát biểu rằng nếu $p$ là số nguyên tố thì $(p-1)! + 1$ chia hết cho $p$. Bạn có thể sử dụng kết quả này như thế nào để giảm số ẩn số trong đa thức hàm mũ $R$ cho trước các số nguyên tố?
4. Xây dựng một đa thức hàm mũ $S(x_0, \dots, x_h)$, xác định tập hợp các số nguyên tố sinh đôi, nghĩa là nếu $S(x_0, \dots, x_h) > 0$ thì cả hai số $S(x_0, \dots, x_h) - 1$ và $S(x_0, \dots, x_h) + 1$ đều là số nguyên tố và ngược lại, nếu $s-1$ và $s+1$ là số nguyên tố thì $S(x_0, \dots, x_h) = s$ đối với một số $x_0, \dots, x_h$.
5. Xây dựng một đa thức hàm mũ $T(q, x_0, \dots, x_m)$ sao cho nếu $q$ là số nguyên tố thì tồn tại các số $x_0, \dots, x_m$ sao cho $T(q, x_0, \dots, x_m) > 0$;
nếu $q$ là số nguyên tố và $T(q, x_0, \dots, x_m) > 0$ thì $T(q, x_0, \dots, x_m)$ là số nguyên tố theo sau $q$;
nếu $q$ không phải là số nguyên tố thì luôn luôn $T(q, x_0, \dots, x_m) \leq 0$.

Đa thức hàm mũ này đưa ra "công thức cho số nguyên tố tiếp theo".
