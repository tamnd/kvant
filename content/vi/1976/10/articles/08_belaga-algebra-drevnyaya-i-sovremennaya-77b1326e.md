---
id: 1976-10-belaga-algebra-drevnyaya-i-sovremennaya-77b1326e
issue: kvant_1976_10
year: 1976
number: "10"
title: Đại số - cổ xưa và hiện đại
authors:
  - Белага Э. Г.
rubric: matematicheskiy-kruzhok
rubric_sub: Математический кружок
page_first: 26
page_last: 32
page_labels: 24, 25, 26, 27, 28, 30
tag: 9G9S
lang: vi
source: kvant_digital
extraction: vision
content_sha256: 78fa593ad9e0c8b1a5692c03036ef12a06c9de6c29a99e0547e5b2ca52019582
prompt_sha256: draft-1
translated_from: content/ru/1976/10/articles/08_belaga-algebra-drevnyaya-i-sovremennaya-77b1326e.md
source_content_sha256: 2edcfd12177bb775a1c54f503bbb70adb9b3dbdcf880af3d3e3e8f231947efd2
translation_model: draft
translation_run: vi-draft-2026-10-31
translation_quality: draft
---

⟦folio 24⟧

E. Belaga
ĐẠI SỐ -
CỔ ĐẠI
VÀ HIỆN ĐẠI

Bạn đã đọc các bài viết của A. Kolmogorov “Nhóm chuyển đổi” và “Nhóm” của L. Sadovsky và M. Arshinov, trong đó các khái niệm về phép toán nhị phân và nhóm được giới thiệu. Để thu hút sự chú ý đến những khái niệm mới đối với bạn, bạn cần xem xét một số ví dụ “với một cây bút chì trong tay”. Bài viết dưới đây sẽ giúp bạn điều này. Nó nói về phép nhân của các từ, sự tự kết hợp của các khối đa diện thông thường, các nút và sự thay thế, cũng như việc áp dụng lý thuyết trừu tượng vào lời giải cụ thể bài toán. Một người đọc chú ý và kiên nhẫn sẽ có thể suy luận độc lập nhiều tính chất thay thế của các phép toán trên các đối tượng này, chia nhỏ các điều kiện và tìm kiếm lời giải bài toán (chúng đóng vai trò là phần tiếp theo của văn bản chính). Những câu hỏi thú vị nhất và thường khá khó bài toán được đánh dấu bằng dấu hoa thị.

I. MỌI THỨ KHÁC LÀ CÔNG VIỆC CỦA BÀN TAY CON NGƯỜI...

Trong các bộ lạc nguyên thủy, tên các con số không thể tách rời khỏi tên các đồ vật được liệt kê. Không phải “hai” hay “tri” mà chỉ là “hai sông” hay “ba chiến sĩ”. Với sự ra đời của khái niệm trừu tượng về con số, toán học đã ra đời. Có lẽ đây là lý do tại sao nhà toán học kiệt xuất người Đức Leopold Kronecker đã từng thốt lên câu nói nghịch lý đến mức nổi tiếng của mình: “Chúa tạo ra số nguyên, mọi thứ khác đều là công việc của con người”.
Một người phải mất vài nghìn để học, để một người học bài toán dưới dạng công thức. Sau đó, các chữ cái xuất hiện trong các công thức này thay vì số. Số học “theo nghĩa đen” mới bắt đầu được gọi là đại số. Và sau đó, các ký hiệu đại số và các phép toán đại số được mở rộng cho nhiều đối tượng có bản chất phi số học - phép thay thế, ma trận, phép biến đổi hình học, v.v., và trục số (hoặc mặt phẳng phức) hóa ra chỉ là một trong rất nhiều cấu trúc đại số được nghiên cứu trong đại số mới.

II. VỀ “Những ĐIỀU” CÓ THỂ “NHÂN” VÀ THÔI KHI ĐƯỢC CHIA, DÙ KHÔNG PHẢI LÀ CON SỐ

Chúng ta được dạy từ rất sớm rằng các số có thể được cộng, nhân, trừ và chia. Thật ngạc nhiên - và bạn cũng cần phải làm quen với điều này - rằng bạn có thể “cộng” (hoặc “nhân”) ngay cả “những thứ” không có tính chất số.

Ví dụ 1: từ
Chúng tôi sẽ gọi bất kỳ bộ sưu tập ký hiệu nào là bảng chữ cái. Chúng ta sẽ giới hạn ở các bảng chữ cái hữu hạn (trong đại số và logic toán học của tiếng Ba Lan).

⟦folio 25⟧

cũng là vô hạn). Dưới đây là hai ví dụ về bảng chữ cái:

$A_1$. Một bảng chữ cái bao gồm hai chữ cái Hy Lạp: α và β.

$A_2$. Bảng chữ cái tranh luận: các số từ 0 đến 9, các ký hiệu tranh luận, dấu bằng và dấu ngoặc đơn:

$$\{0, 1, 2, 3, 4, 5, 6, 7, 8, 9, +, -, :, \times, =, ),\}$$.

Chúng tôi sẽ gọi bất kỳ chuỗi ký hiệu hữu hạn nào từ $A$ là một từ phía trên bảng chữ cái $A$. Dưới đây là ví dụ về các từ phía trên hai bảng chữ cái được mô tả ở trên (để tách mục từ khỏi văn bản xung quanh, chúng tôi “đóng gói” nó trong dấu ngoặc nhọn):

$$(A_1): \langle \alpha\beta \rangle, \langle \alpha\beta\alpha\beta \rangle, \langle \rangle;$$
$$(A_2): \langle 1976 \rangle, \langle 2 + 2 = 4 \rangle,$$
$$\langle - \rangle +): \langle 3 \rangle).$$

Một từ cũng có thể là “trống”, tức là không chứa bất kỳ ký tự nào (từ “cuối cùng” trong ví dụ đầu tiên), từ đó được biểu thị bằng chữ cái $\lambda$: $\lambda = \langle \rangle$. Chúng tôi biểu thị tập hợp các từ trong bảng chữ cái nhất định $A$ bằng $C(A)$. Chúng ta sẽ biểu thị các phần tử của nó, tức là các từ, bằng các chữ cái Latinh nhỏ (chúng không thuộc bảng chữ cái mà chúng ta xem xét ở đây).

Tích hoặc thành phần của hai từ $a$ và $b$ từ $C(A)$ chúng ta sẽ gọi từ $c$ (và viết: $c = a \otimes b$), từ kết quả được gán cho từ $a$ ở bên phải của nó là từ $b$. Dưới đây là ví dụ về sự kết hợp từ:

$$(A_1): a = \langle \alpha \rangle, b = \langle \alpha\beta \rangle,$$
$$c = a \otimes b = \langle \alpha\alpha\beta \rangle;$$
$$(A_2): a = \langle 2 + 2 \rangle, b = \langle 4 \rangle,$$
$$c = a \otimes b = \langle 2 + 2 = 4 \rangle.$$

Một từ trống không chứa bất kỳ ký tự nào, vì vậy $a \otimes \lambda = \lambda \otimes a = a$ đối với bất kỳ từ $a$ nào của $C(A)$, tức là từ trống $\lambda$ khi sắp xếp lại các từ sẽ hoạt động giống như một đơn vị khi sắp xếp lại các số.

Nếu tiếp tục tìm kiếm điểm giống và khác nhau giữa phép nhân từ và phép nhân số, chúng ta sẽ nhận thấy phép toán “⊗” có tính chất kết hợp:

$$(a \otimes b) \otimes c = a \otimes (b \otimes c),$$

Nói cách khác, ký hiệu $a \otimes b \otimes c$ có ý nghĩa.

Bài toán 1. Đối với bất kỳ từ nào $a$ từ $C(A)$, chúng ta xác định lũy thừa không âm của nó bằng cách đặt $a^0 = \lambda$, $a^1 = a$, $a^2 = a \otimes a$, nói chung là $a^{n+1} = a \otimes a^n$. Chứng minh rằng với mọi số nguyên không âm thì đẳng thức

$$a^m \otimes a^n = a^{m+n}.$$

Đẳng thức sau nó cho phép chúng ta viết tắt ký hiệu của các từ không âm: cùng nhau $a = \langle \alpha \rangle^3 \otimes \langle \beta \rangle^3 \otimes \langle \alpha \rangle^4$ hoặc, cho phép ký hiệu có độ sóng không âm, $a = \langle \alpha^3\beta^3\alpha^4 \rangle$. Nhưng việc đổi thứ tự các chữ cái thành từ, nói chung, không thể nói “⊗” có thể không có tính chất giao hoán, tức là $a \otimes b$ có ​​thể không trùng với $b \otimes a$.

Bài toán 2. a) Phép tính “⊗” giao hoán được thực hiện trên bảng chữ cái nào, nghĩa là với mọi từ $a$ và $b$ sẽ có $a \otimes b = b \otimes a$?

6)* Hai từ $a$ và $b$ nên được sắp xếp như thế nào trong một bảng chữ cái $A$ chứa hai ký tự trở lên sao cho cấu tạo của các từ này không phụ thuộc vào thứ tự của chúng?

Ví dụ 2: tự căn chỉnh

Như đã biết, sự đồng dạng (người ta thường nói là “bằng nhau”) của các hình và vật thể trong hình học được thiết lập bằng sự thay đổi: nếu có một chuyển động của mặt phẳng (hoặc không gian), trong đó một hình được ánh xạ lên một hình khác, thì những hình này là congrugis. Một chuyển động trong đó bản thân giá trị không âm sẽ được gọi là tự căn chỉnh.

Ví dụ, đối với một khối lập phương, chỉ có 48 cách tự sắp xếp khác nhau. Thật vậy, chúng ta hãy vẽ một mặt của khối lập phương và đánh dấu hướng trên một trong các cạnh bao quanh mặt này (Hình 1). Sau đó, khả năng tự căn chỉnh của hình lập phương được xác định bởi mặt nào của hình khối mà mặt màu được ánh xạ tới, cạnh nào của mặt này mà cạnh được đánh dấu sẽ đi tới và đầu nào của cạnh này mà mũi tên hướng tới (từ những dữ liệu này, nó được xác định duy nhất

⟦folio 26⟧

Hình 1.
Vị trí của khối lập phương được chia). Hình lập phương có 6 mặt, mỗi mặt có 4 cạnh, mỗi cạnh có 2 đầu, tổng cộng có $6 \times 4 \times 2 = 48$ cách.

Tích $c = a \circ b$ của phép tự sắp xếp $a$ và $b$ của khối đa diện đều $\Delta$ được định nghĩa là thành phần tổng quát của các phép dịch chuyển: đầu tiên $b$ được thực hiện và sau đó là $a^*$). Kiểm tra xem $(a \circ b) \circ c = a \circ (b \circ c)$ đối với ba cách tự sắp xếp $a, b, c$ bất kỳ từ bộ $\Gamma (\Delta)$ của tất cả các cách tự sắp xếp của cơ thể $\Delta$ (tính kết hợp; so sánh với mô tả của nhóm ở trang 8 và tiên đề của nhóm III ở đó).

Bài tập 3. Chứng minh rằng việc thực hiện tuần tự hai phép quay hình lập phương: đầu tiên quanh trục $AB$ (Hình 2) một góc $90^\circ$, sau đó quanh trục $CD$ một góc $120^\circ$, có thể viết là một phép quay quanh trục $EF$ nhân $180^\circ$, là tích của hai phép quay. Sản phẩm này có phụ thuộc vào thứ tự thực hiện các lượt không?

*) Thứ tự ghi này thuận tiện ở chỗ hình ảnh $(a \circ b)(M)$ của điểm $M$ khi được ánh xạ $a \circ b$ sẽ là $a(b(M))$.

Hình 2.
Bài tập 4. Chứng minh rằng chỉ có 4 cách thẳng hàng khác nhau của đường thẳng trong không gian (Hình 3): giống nhau $e$, quay $a$ quanh $AB$, $b$ – quanh $CD$, $c$ – quanh $EF$, và $a^2 = b^2 = c^2 = e$, $a \circ b = b \circ a = c$, $b \circ c = c \circ b = a$, $a \circ c = c \circ a = b$.

Phần dư của đẳng thức bài toán 4 có thể viết dưới dạng bảng cửu chương sau:

| $e$ | $a$ | $b$ | $c$ |
| :--- | :--- | :--- | :--- |
| $e$ | $e$ | $a$ | $b$ |
| $a$ | $a$ | $e$ | $c$ |
| $b$ | $b$ | $c$ | $e$ |
| $c$ | $c$ | $b$ | $a$ |

Rõ ràng là bất kỳ sự tự căn chỉnh nào $a$ của một hình hoặc cơ thể $\Delta$ đều tương ứng với một "nghịch đảo" duy nhất $a^{-1}$, đưa cơ thể về vị trí ban đầu ($a^{-1}$ có thể trùng với $a$, như trong nhiệm vụ 4). Hơn nữa, nếu $a^{-1}$ là đảo ngược $a$, thì $a$ là đảo ngược $a^{-1}$:

$a \circ a^{-1} = a^{-1} \circ a = e$.

⟦folio 27⟧

Hình 5.

Bây giờ chúng ta có thể xác định bất kỳ mức độ nguyên nào $a^k$ của việc tự căn chỉnh $a$:
$$a^0 = e, a^1 = a, a^2 = a \circ a, \dots, a^{k+1} = a \circ a^k, a^{-k-1} = a^{-1} \circ a^{-k}.$$
Thật dễ dàng để xác minh rằng $a^k \circ a^l = a^{k+l}$ với bất kỳ $a$ nào của $\Gamma(\Delta)$ và mọi số nguyên $k$ và $l$; cụ thể là, $a^k$ và $a^{-k}$ nghịch đảo lẫn nhau. (So ​​sánh với mô tả của nhóm ở trang 8 và Tiên đề II.)

Bài toán 5. Tìm tất cả các cách tự sắp xếp của một hình khối đều, hình bát diện và hình hai mươi mặt đều (Hình 4). Cái nào trong số chúng thỏa mãn đẳng thức $a^2 = e$? Bình đẳng $a^3 = e$? Bình đẳng $a^5 = e$? Lập bảng nhân cho sự tự kết hợp của khối lập phương và khối lập phương.

Bài toán 6. Chứng minh rằng bất kỳ sự tự thẳng hàng nào của một khối hai mươi mặt đều có thể thu được bằng cách “nhân” một số phép quay (với $72^\circ$) xung quanh hai đỉnh liền kề; chính xác hơn, nếu chúng ta biểu thị các phép quay này bằng các chữ cái $a, b$, thì bất kỳ sự tự sắp xếp nào của khối hai mươi mặt đều có thể được viết dưới dạng tích của một số cách tự sắp xếp, mỗi cách sắp xếp đó là $a$ hoặc $b$.

Ví dụ 3: sự thay thế

Di truyền học, như người đọc có thể biết, bắt đầu từ đậu Hà Lan. Lý thuyết nhóm bắt đầu với sự thay thế - chúng là đối tượng và công cụ “phi số” đầu tiên của đại số mới cho Joseph-Louis Lagrange, Paolo Ruffini và Evariste Galya.

Thuộc tính chính của sự thay thế là sắp xếp lại hoặc hoán đổi số hoặc chữ cái trong một chuỗi nhất định. Hình 5 cho thấy sự thay thế các chữ cái trong các từ đảo chữ làm thay đổi nghĩa của những từ này; Các bản ghi số “hai tầng” chung của những sự thay thế này được viết gần đó.

Sự thay thế được thảo luận trong bài viết “Nhóm”; chúng ta chỉ nhớ lại rằng hai phép thay thế $b, a$ của cùng một tập hợp các phần tử, được thực hiện lần lượt, sẽ cho ra phép thay thế cần thiết $c = a \circ b$, được gọi là tích của chúng. Hình 6 minh họa định nghĩa ngắn gọn này. Tập hợp tất cả các hoán vị của tập hợp $(1, 2, 3, \dots, n)$ sẽ xử lý một nhóm gọi là "nhóm đối xứng bậc $n$" và ký hiệu là $S_n$. Nhóm này chứa $n!$ thay thế.

Bài toán 7. Đặt $a$ là một sự thay thế nào đó. Chứng minh rằng nếu $k$ là số nguyên dương nhỏ nhất mà $a^k = e$, thì đẳng thức $a^l = e$ suy ra rằng $k$ chia hết $l$. Tiếp theo, chứng minh rằng $k$ chia hết $n!$ và không vượt quá $3^{n/3}$).

Bài toán 8*. Chứng minh rằng bất kỳ sự thay thế nào từ $S_n$ đều có thể thu được bằng cách thực hiện tuần tự một số

*) bài toán này đã được cung cấp cho độc giả «Kvant» (xem «Kvant», 1975, số 11, M355, và cả «Kvant», 1976, số 8, trang 39).

Hình 6.

⟦folio 28⟧

Hình 7.
Hình 8.

Số lượng (và theo thứ tự thích hợp) thay thế
$$\begin{pmatrix}
1 & 2 & 3 & \dots & n-1 & n \\
2 & 3 & 4 & \dots & n & 1 \\
\end{pmatrix}
$$
Và
$$\begin{pmatrix}
1 & 2 & 3 & \dots & n \\
2 & 1 & 3 & \dots & n \\
\end{pmatrix}.$$

Ví dụ bốn và cuối cùng: các nút
Nút là một đường cong không gian khép kín không có điểm tự giao nhau. Các nút được nghiên cứu trong cấu trúc liên kết, nhưng các phương pháp đại số đóng vai trò quyết định cả trong việc mô tả các nút riêng lẻ và trong nghiên cứu tập hợp $Y$ của tất cả các nút. Chúng ta sẽ xem xét các thuộc tính của thành phần nút ở đây. Định nghĩa về thành phần $c = a \# b$ của hai nút $a$ và $b$ được thể hiện rõ ràng trong Hình 7.

Bài toán 9. Chứng minh rằng hợp thành là một phép toán kết hợp và giao hoán (có phần bất ngờ). Nút nào đóng vai trò trong việc này?

Ba tính chất đáng chú ý hơn của hoạt động kết hợp nút thắt có thể được chứng minh.

a) Bất kỳ nút thắt nào không phải là đơn vị (nghĩa là không được cởi ra mà không bị đứt) đều không thể đảo ngược được. Nói cách khác: bạn không thể tháo một nút thắt bằng cách buộc một nút khác bên cạnh nó; hoặc cách khác: các nút có thể được nhân lên nhưng không được chia cho nhau.

6) Có những cái “đơn giản”; chúng không thể được biểu diễn dưới dạng tích của hai nút khác, mỗi nút khác với “đơn vị” (ví dụ: các nút $a$, $b$ trong Hình 7 và $m$, $n$ trong Hình 8 là đơn giản).

c) Bất kỳ nút nào đều đơn giản hoặc là sự kết hợp của các nút đơn giản và cách biểu diễn như vậy là duy nhất. Thật là một sự tương đồng đáng kinh ngạc với tính chất của số nguyên!
(Các nút thắt được mô tả chi tiết trong «Kvant», 1975, số 7).

Những gì nhà đại số nhìn thấy trong các ví dụ của chúng ta

Một nhà đại số giống như một nhà địa hình - anh ta nhìn các đối tượng toán học “từ góc nhìn của một con chim” và chỉ chú ý cũng như khám phá những mối liên hệ và mô hình chung nhất. Nhưng kết quả của nó có tính chất tổng quát và phổ quát nhất. (Tất nhiên, những tổn thất cũng là không thể tránh khỏi, vì nhà địa hình không thể tiếp cận được vẻ đẹp của phong cảnh đất nước, bản đồ mà ông biên soạn bằng cách sử dụng các bức ảnh chụp từ trên không.)

Để nhận thấy rằng một bảng hợp nhất những “thứ” khác nhau, chẳng hạn như các từ, nút, sự thay thế và sự tự kết hợp, có thể được diễn đạt bằng ngôn ngữ của các định nghĩa và tiên đề được xây dựng trong bài viết “Nhóm” (xem trang 7-8). Trong mỗi ví dụ này, một tập hợp sẽ phát sinh trong đó phép toán nhị phân được chỉ định. Hoạt động không phải lúc nào cũng ngược lại, nhưng trong tất cả các ví dụ, hoạt động này có tính chất kết hợp. Tập hợp có phép toán nhị phân kết hợp (tiên đề nhóm III) được gọi là nửa bình. Như bạn có thể thấy, sự tồn tại của sự thống nhất và tính khả nghịch của các phần tử (các tiên đề của nhóm I và II) không được thừa nhận trong nửa bình.

Tất cả các ví dụ mà chúng tôi đã xem xét đều là các nửa bình, và các nhóm tự kết hợp và thay thế thậm chí còn tạo thành các nhóm - cả hai tiên đề I và II đều thỏa mãn trong đó.

Bạn đọc đã quen thuộc với đa thang $N$ của mọi số tự nhiên với phép nhân, đa thang của mọi số tự nhiên.

⟦folio 30⟧

Xung quanh định lý Lagrange

Không đưa ra bằng chứng về định lý Lagrange (có thể tìm thấy trong sách giáo khoa về lý thuyết nhóm), chúng tôi sẽ minh họa bằng các ví dụ về cách thức hoạt động của định lý này.

Và minh họa 1 (đại số). Nếu trong một nhóm hữu hạn $G$ có một phần tử $g$ có cấp $k$ bằng cấp $r(G)$ của nhóm $G$, thì bất kỳ phần tử $a$ nào của $G$ đều là lũy thừa nào đó của $g: a = g^m$ ($0 \leqslant m \leqslant k-1$). Nhóm $G$ như vậy được gọi là tuần hoàn; cô ấy luôn là một người giao tiếp.

Một ví dụ về nhóm tuần hoàn là nhóm tự sắp xếp của một $n$-gon thông thường (xem trang 9), trong đó phần tử $g$, “tạo ra” toàn bộ nhóm, là một phép quay qua góc $360^\circ/n$.

Bài toán 11. Chứng minh rằng trong nhóm tuần hoàn, số lời giải của phương trình $x^n = e$ bằng ước số thể tích lớn nhất của các số $n$ và $r(G)$.

Bài toán 12*. Chứng minh rằng nếu cấp $r(G)$ của một nhóm hữu hạn $G$ là số nguyên tố thì nhóm $G$ là tuần hoàn.

Và hình minh họa 2 (hình học). Thứ tự của nhóm $\Gamma(D)$ tự sắp xếp của khối mười hai mặt $\Delta$ (nhóm đối xứng của khối mười hai mặt) chia hết cho 30. Thực tế này có thể được suy ra từ định lý Lagrange mà không cần tính toán - đơn giản từ sự tồn tại của ba kiểu tự sắp xếp của khối mười hai mặt (xem Hình 9): phép quay quanh đỉnh “trên một mặt” (trên $120^\circ$), xoay quanh các cạnh giữa ở $180^\circ$ và xoay quanh tâm của khuôn mặt ở $72^\circ$. Thứ tự của các phần tử này trong nhóm $\Gamma(D)$ rõ ràng lần lượt là 3, 2 và 5, do đó thứ tự của nhóm $\Gamma(D)$ chia hết cho $3 \cdot 2 \cdot 5 = 30$.

Và hình minh họa 3 (số học). Bài toán vì số chia hết thường rất đẹp; Ví dụ, hãy thử chứng minh rằng các số $7^8-1$, $11^8-1$, $13^8-1$, $17^8-1$, $19^8-1$, $23^8-1$, $29^8-1$ chia hết cho 30. Khi tìm thấy lời giải, bạn sẽ rất vui khi biết rằng thực tế này là một trong những hệ quả của định lý Lagrange.

Hình 9.

Ta biểu thị bằng $\Phi(m)$ tập hợp các số tự nhiên nhỏ hơn $m$ và nguyên tố cùng nhau với $m$. Hãy để chúng tôi giới thiệu trên bộ $\Phi(m)$ phép toán "" của phép nhân modulo $m: a * b$ bằng phần còn lại của phép chia tích chung $a \cdot b$ của các số $a$ và $b$ cho $m$ (ví dụ: nếu $m = 30$, thì $7 \cdot 17 = 29$, vì $7 \cdot 17 = 119 = 3 \cdot 30 + 29$).

Bài toán 13. Chứng minh rằng $\Phi(m)$ tạo thành nhóm Abel, tức là

a) $a * b$ thuộc về $\Phi(m)$ và $a * b = b * a$;

b) số 1 luôn thuộc về $\Phi(m)$ và $a * 1 = a$ với bất kỳ $a$ nào của $\Phi(m)$;

b) với mọi $a$ từ $\Phi(m)$ đều có $b$ sao cho $a * b = 1$.

Vì vậy, $\Phi(m)$ là một nhóm. Chúng ta hãy biểu thị thứ tự của nó bằng $\Phi(m)$, sau đó với bất kỳ $a$ nào từ $\Phi(m)$ sẽ có $a^{\Phi(m)} = 1$ (Định lý Lagrange trong công thức thứ hai!). Ở đây, việc nâng lũy ​​thừa $\Phi(m)$ là tùy ý trong nhóm $\Phi(m)$ và đối với lũy thừa tổng quát của các số nguyên, điều này có nghĩa là $a^{\Phi(m)}$ để lại phần dư là 1 khi chia cho $m$, tức là $a^{\Phi(m)} - 1$ chia hết cho $m$. Nếu $m = 30$ thì $\Phi(m) = \{1, 7, 11, 13, 17, 19, 23, 29\}$, $\varphi(m) = 8$ và ngay lập tức chúng ta nhận được rằng các số $7^8-1, 11^8-1, \dots$ chia hết cho 30.

Chủ đề suy nghĩ

Về lời nói. Sử dụng bảng chữ cái $A$, chúng ta hãy xây dựng một bảng chữ cái $\hat{A}$ gồm các ký hiệu và “phản ký hiệu”: nếu $A$ bao gồm ký hiệu $a$ thì $\hat{A}$ bao gồm $a$ và $a$.
