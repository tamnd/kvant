---
id: 1972-4-vasilev-rasstanovka-kubikov-535a6248
issue: kvant_1972_4
year: 1972
number: "4"
title: Sự sắp xếp các hình khối
authors:
  - Васильев Н. Б.
rubric: osnovnye-stati
page_first: 8
page_last: 11
page_labels: 6, 8, 9
tag: 61ON
lang: vi
source: kvant_digital
extraction: vision
content_sha256: 486255ebfbb267595d62429e03b6a73baaebd10beaae3f5b606721ee63f6ee6f
prompt_sha256: draft-1
translated_from: content/ru/1972/04/articles/04_vasilev-rasstanovka-kubikov-535a6248.md
source_content_sha256: 69f9ba39e1d9e8d19cb33283116262e2bf8439f6141d2b78790c911f724c2c97
translation_model: draft
translation_run: vi-draft-2026-10-31
translation_quality: draft
---

⟦folio 6⟧

Hình 4.

Chúng ta hãy gọi một lớp là một tập hợp các ô có tâm nằm trong mặt phẳng song song với một trong các mặt của đế và một đường thẳng - một tập hợp các ô có tâm nằm trên một đường thẳng song song với một cạnh; một lớp bao gồm $n^2$ ô, một dòng - gồm $n$ ô. Hãy vẽ hình chiếu của bến tàu lên một trong các mặt, chẳng hạn như trên mặt phẳng $Ox_1x_2$ (mặt trước) và trên mỗi trường của bến tàu kết quả $n \times n$, chúng ta viết số lớp mà quân xe xuất hiện, chiếu lên trường này. Khi đó, việc sắp xếp các quân xe như trong Hình 3 sẽ được viết như trong Hình 4 (chúng ta sẽ không gặp phải tình huống có nhiều hơn một quân xe trên một dòng, vì vậy dockki $n \times n$ sẽ viết không quá một số trên mỗi ô vuông). Lưu ý rằng trong Hình 4, đối với mỗi trường trống trong hàng và cột tại giao điểm của nó, tất cả các số sẽ xuất hiện: 1, 2 và 3. Điều này có nghĩa là mọi trường dock $3 \times 3 \times 3$ không theo hướng $x_3$ sẽ theo hướng $x_1$ hoặc theo hướng $x_2$.

Vì vậy, chúng tôi tin chắc rằng $A_3 \leq 5$. Thực tế là $A_3 \geq 4$ đã được chứng minh (xem (1)). Câu hỏi đặt ra: $A_3$ bằng: 4 hay 5 là bao nhiêu? Chúng tôi mang đến cho độc giả cơ hội đa dạng hóa

lấy trường hợp $n=3, n=4$, v.v. rồi đi thẳng vào trường hợp tổng quát.

Bài tập không thể đặt 4 quân xe để chúng chỉ là dockku $3 \times 3 \times 3$; 6) chỉ ra một ví dụ về cách sắp xếp 8 quân xe, tổng cộng sẽ là $4 \times 4 \times 4$; trong tài liệu rằng $A_4=8$.

Trường hợp chung. Công thức của kết quả

Trong bài toán ed của chúng tôi, có lẽ điều khó khăn nhất là đưa ra giả thuyết chính xác: cái gì bằng $A_n$. đáp số này đã dễ dàng hơn nhiều để xây dựng một ví dụ (nghĩa là ước tính $A_n$ từ phía trên) và để chứng minh rằng không thể thực hiện được với ít quân xe hơn. Và đáp số là:

$$A_n = \begin{cases} \frac{n^2}{2}, \text{ если } n \text{ четно}, \\ \frac{n^2 + 1}{2}, \text{ если } n \text{ нечетно}. \end{cases}$$

Cụ thể là $A_4=8$, $A_5=13, \dots, A_{10}=50$.

Ví dụ về vị trí "tối ưu" của quân $A_n$ được nêu rõ trong Hình 5, $a$ ($n$ chẵn) và 5, $b$ ($n$ lẻ). Có thể dễ dàng kiểm tra xem tất cả các trường không tồn tại theo hướng $x_3$ có tồn tại theo hướng $x_1$ hoặc theo hướng $x_2$ hay không: trong mỗi “chữ thập” - một hàng và cột tại giao điểm của nó có một trường trống - tất cả các số từ 1 đến $n$ đều xuất hiện.

Vẫn còn phải chứng minh rằng với ít quân hơn thì họ không thể chiếm được toàn bộ bến tàu.

Bằng chứng đầu tiên

Đặt các quân $M$ sao cho chúng từ tất cả các ô vuông được neo. Từ tất cả các lớp, hãy chọn lớp có số lượng quân xe là tối thiểu (nếu có một số lớp như vậy thì có thể). Chúng ta có thể giả sử rằng nó nằm song song với mặt phẳng $Ox_1x_2$. Hãy biểu thị lớp này bằng $S$ và số quân xe trong đó là $m$. Đặt các quân $m$ này thuộc $m_1$ hàng theo hướng $x_1$ và $m_2$ hàng theo hướng $x_2$ (chúng ta có thể giả sử rằng $m_1 \geq m_2$; tất nhiên, $m \geq m_1$ và $m \geq m_2$). Sau đó

⟦folio 8⟧

Bằng chứng thứ hai

Bổ đề. Đặt $n \times n$ là các số nguyên không âm trong bảng sao cho nếu trường nào đó chứa 0 thì tổng của tất cả các số trong hàng và cột tại giao điểm của trường này không nhỏ hơn $n$. thì tổng của tất cả các số trong bảng không nhỏ hơn $\frac{n^2}{2}$ (và do đó, nếu tất cả các số trong bảng đều là số nguyên thì nếu $n$ là số lẻ thì tổng này không nhỏ hơn $\frac{n^2+1}{2}$).

Từ bổ đề, bạn cần ước tính cho $A_n$ thật dễ dàng: chỉ cần chiếu bảng lên một trong các mặt và viết vào trường nào của bảng kết quả $n \times n$ có bao nhiêu quân xe được chiếu vào đó. Rõ ràng là các điều kiện của bổ đề cho bảng kết quả sẽ được thỏa mãn.

Nó vẫn còn để chứng minh bổ đề. Chúng ta sẽ không làm điều này, vì bổ đề này đã xuất hiện gần đây trong «Kvant»: nghịch lý thay, nó lại được đề xuất vào cùng năm ngoái dưới dạng một bài toán riêng biệt tại Olympic Quốc tế (xem «Kvant» số 12, 1971). Thật không may, bằng chứng thứ hai về bài toán của chúng tôi, và do đó, bổ đề, đã không được thảo luận khi phân tích bài toán tại Olympic toàn Liên minh, vì vậy cả các nhà lãnh đạo của đội Liên Xô đều không biết bổ đề này (nếu không, tất nhiên, họ đã thêm nó để nó không được cung cấp cho học sinh vì nó quá nổi tiếng), cũng như những người tham gia trong nhóm của chúng tôi (nếu không thì tất cả họ đều giải quyết nó một cách hoàn hảo).

Vì vậy, bài toán chính, được thảo luận ở điểm a), b) và c) của điều kiện, lời giải.

Lưu ý về khái quát

Đối với bài toán tổng quát hơn, được xây dựng ở điểm r), - tương tự như bài toán không phải dành cho bảng “ba chiều”, mà dành cho bảng “k chiều” ($k \geq 4$), ở đây không biết kết quả cuối cùng. Đối với số lượng tối thiểu $A_n^k$ quân xe, chỉ có một bàn cờ $n \times n \times \dots \times n$ (chúng tôi giữ nguyên thuật ngữ cờ vua, nhưng ví dụ: bây giờ hình vuông $x$ là một tập hợp các số $k$ ($x_1, x_2, \dots, x_k$),

trong đó mỗi $k$ nhận giá trị từ 1 đến $n$), dễ dàng thu được các ước tính tương tự như (1), (2):

$$A_n^k \leq n^{k-1}, A_n^k \geq \frac{n^k}{k(n-1)+1}.$$

Có razzhene 4. Chứng minh các bất đẳng thức này. Cố gắng cải thiện điểm $n^{k-1}$ bằng cách sử dụng các cân nhắc tương tự như trong Bài tập 2.

Vì $A_n^2=n$ và $A_n^3$ bằng $\frac{n^2}{2}$ hoặc $\frac{n^2+1}{2}$, nên giả thuyết là $A_n^k$ gần với $\frac{n^{k-1}}{k-1}$. Giả thuyết này, cùng với những giả thuyết khác, đã được thảo luận bởi những người tham gia Olympic và các thành viên ban giám khảo không chỉ trong Thế vận hội mà còn sau đó. Tuy nhiên, kết quả thú vị nhất đã được báo cáo cho chúng tôi bởi D. Grigoriev, một sinh viên tốt nghiệp Trường Vật lý và Toán học tại Đại học Leningrad, và độc giả V. Ginzburg của chúng tôi: họ (độc lập) đã chứng minh được rằng nếu $M$ quân xe là toàn bộ bàn cờ và không có hai quân nào khác nhau, thì $M \geq \frac{n^{k-1}}{k-1}$ (chúng tôi đặt bằng chứng ở cuối bài viết). Rõ ràng, kết quả này đúng ngay cả khi không có giả định bổ sung được in nghiêng, tức là bất đẳng thức $A_n^k \geq \frac{n^{k-1}}{k-1}$ là đúng, và, như các ví dụ đã cho thấy, đối với $n > k$ ước tính này khá gần với ước tính chính xác (hoặc thậm chí trùng khớp chính xác với nó).

Tuy nhiên, ước tính $\frac{n^{k-1}}{k-1}$ phụ thuộc không "rất chính xác" cho tất cả $n$ và $k$.

Ví dụ: nếu $n=2$ thì $\frac{n^{k-1}}{k-1} = \frac{2^{k-1}}{k-1}$ và ước tính "sơ bộ" $\frac{n^k}{k(n-1)+1} = \frac{2^k}{k+1}$ hóa ra là tốt nhất (đối với $k>3$); đối với $k$ lớn, số $\frac{2^k}{k+1}$ được áp dụng gấp đôi so với $\frac{2}{k-1}$.

Razzhene có 5. Tìm $A_2^4, A_3^4, A_2^5$.

Đôi lời về mã bài toán

Một bài toán, rất gần với công thức của chúng tôi, là quá sớm—quá sớm vì nó quan trọng đối với các ứng dụng. Trong “thuật ngữ cờ vua” thì có vẻ như thế này: cái nào tốt nhất

⟦folio 9⟧

số cổ của các quân xe có thể được đặt trên một bảng $k$ chiều $n \times n \times \dots \times n$ sao cho chúng không phải là nhau? (Tùy chọn khác: sao cho không có trường nào là gấp đôi?) Nói cách khác: tập $Y$ nào của các tập $y = (y_1, y_2, \dots, y_k)$ có thể được tạo sao cho a) cứ hai tập trong $Y$ khác nhau ở nhiều hơn một tọa độ, hoặc b) mọi tập hợp $x = (x_1, x_2, \dots, x_k)$, trong tập $Y$ có nhiều nhất một tập hợp $y$, khác với $x$ chỉ trong một tập hợp phối hợp? Việc hình thành nhiệm vụ liên quan trực tiếp đến lý thuyết về khoa học thông tin, hay chính xác hơn là liên quan đến phần của nó - lý thuyết về mã sửa lỗi. Lý thuyết này giải quyết các vấn đề thuộc loại này: soạn một tập hợp $Y$ “từ” $(y_1, y_2, \dots, y_k)$ sao cho nếu khi truyền một trong những từ này (chẳng hạn như qua điện thoại hoặc qua kênh liên lạc trong máy tính), nó được bao gồm trong một số “bức thư” thì lỗi này có thể được phát hiện và thậm chí tốt hơn là được sửa, tức là “từ” được truyền có thể được khôi phục. Do đó, tập $Y$ thỏa mãn điều kiện a) được gọi là “mã phát hiện lỗi đơn” và tập hợp thỏa mãn điều kiện b) được gọi là “mã sửa lỗi đơn”. Bạn thấy rằng trong toán học, từ “mật mã” không được sử dụng theo cách hoàn toàn giống như trong sách quay.

Trong pháp luật b. Gọi $B_n^k$ là số quân xe tối đa có thể đặt trên một bảng $k$ chiều $n \times n \times \dots \times n$ sao cho chúng không phải là nhau a) Số nào lớn hơn: $B_n^k$ hoặc $A_n^k$? b) Tìm $B_n^2, B_n^3, B_n^4$.

Lý thuyết về mật mã có lẽ là ví dụ nổi bật nhất về ứng dụng của đại số hiện đại trong một lĩnh vực mà thoạt nhìn thì không liên quan trực tiếp đến các ứng dụng kỹ thuật. Đã cống hiến nhiều công trình khoa học và một số cuốn sách dày dặn, cô ấy đang phát triển nhanh chóng và xứng đáng được làm quen với chuyên môn.

*) W. Peterson. Mã hướng dẫn lỗi, "Mir", 1964; E. Berlekham p Lý thuyết mã hóa đại số, "Thế giới", 1971.

Ứng dụng

Định lý. Đặt $X$ là tập hợp tất cả các bộ dữ liệu $x = (x_1, x_2, \dots, x_k+1)$, trong đó mỗi tọa độ $k+1$ $x$ nhận các giá trị $n$: $1, 2, \dots, n$; $Y$ là tập hợp con của $X$ sao cho (1) hai bộ $Y$ bất kỳ khác nhau ở ít nhất hai tọa độ và (2) đối với mỗi $x$ của $X$ có một bộ $y$ của $Y$ khác với $x$ ở nhiều nhất một tọa độ. Khi đó có nhiều nhất $n^k/k$ phần tử trong $Y$.

Bằng chứng. Đặt $\alpha(x)=1$ nếu $x$ thuộc về $Y$ và $\alpha(x)=0$ nếu không. Hãy đặt $\beta(x)=\beta(x_1, x_2, \dots, x_k)$:

$$\sum_{i=1}^{k} \alpha(x_i, x_j, \dots, x_k) = \sum_{i=1}^{k} \alpha(x_i, x_j, \dots, x_k) = \sum_{i=1}^{k} \beta(x_i, x_j, \dots, x_k)$$

Các tập hợp tọa độ (“rút gọn” của $k$ và $(k-1)$ chúng ta sẽ biểu thị bằng cùng một chữ cái $x$, hãy nhớ rằng các đối số $\beta$ luôn có $x_{k+1}$ bị loại bỏ, và $y \gamma_i - x_{k+1}$ và $x_i$. Theo điều kiện (1) $\beta(x) \leq 1$ cho bất kỳ $x$ nào. Theo điều kiện (2), nếu $\beta(x)=0$ đối với một số $x$, thì $\sum_{i=1}^{k} \gamma_i(x) \geq n$ đối với $x$ này Do đó, đối với tất cả $x$ không có ngoại lệ.

$$\sum_{i=1}^{k} \gamma_i(x) (1-\beta(x)) \geq n (1-\beta(x))$$

Chúng ta hãy tổng hợp tất cả các bất đẳng thức tương ứng với $n^k$ các tập hợp khác nhau $(x_1, x_2, \dots, x_k)$. Chúng tôi biểu thị tổng này bằng chữ cái $\Sigma'$ và tổng trên tất cả các tọa độ ngoại trừ $x_i$ bằng $\Sigma'_i$. Đặt tổng số phần tử $Y$ khác nhau $M$. Sau đó, vì $\Sigma'_i(x)=M$ và $\Sigma'_i(y)=M$ cho mỗi $i$, chúng ta nhận được

$$\sum_{i=1}^{k} (nM - \sum_{i=1}^{k} \gamma_i^2(x)) \geq n^{k+1}-nM$$

Vì tổng bình phương $N$ của các số thực không nhỏ hơn tổng bình phương chia cho $N$ nên vế trái nhiều nhất là

$$\sum_{i=1}^{k} (nM - \sum_{i=1}^{k} \gamma_i^2(x)) \leq \sum_{i=1}^{k} \left( nM - \frac{(\sum_{i=1}^{k} \gamma_i(x))^2}{n^{k-1}} \right) = knM - \frac{kM^2}{n^{k-1}}.$$

Vậy bất đẳng thức đúng

$$knM - \frac{kM^2}{n^{k-1}} \geq n^{k+1}-nM,$$

từ đâu $M \leq n^{k/k}$.
