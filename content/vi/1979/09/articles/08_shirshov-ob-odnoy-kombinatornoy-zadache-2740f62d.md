---
id: 1979-9-shirshov-ob-odnoy-kombinatornoy-zadache-2740f62d
issue: kvant_1979_9
year: 1979
number: "9"
title: Về một tổ hợp bài toán
authors:
  - Ширшов А. И.
rubric: matematicheskiy-kruzhok
rubric_sub: Математический кружок
page_first: 21
page_last: 22
page_labels: 19-20
tag: ZY85
lang: vi
source: kvant_digital
extraction: vision
content_sha256: 548e29796194f6c896eca9180f41aa883981568a53e283fcaca442e4fc9a2164
prompt_sha256: draft-1
translated_from: content/ru/1979/09/articles/08_shirshov-ob-odnoy-kombinatornoy-zadache-2740f62d.md
source_content_sha256: 75bff3984250d2b738cc4f0aa1c9d700fa0e8943551a96ccd3f1b0451c34f7dd
translation_model: draft
translation_run: vi-draft-2026-10-31
translation_quality: draft
---

⟦folio 19⟧

A. Sơ mi

Về một tổ hợp bài toán

Như bạn đã biết, phép nhân tổng quát có tính kết hợp: $(ab)c=a(bc)$ với mọi số. Kết hợp và nhân các hàm: $(f(x)g(x))z(x)=f(x)(g(x)z(x))$.

Tuy nhiên, trong một số nhánh của toán học, phép nhân không liên kết được xem xét. Nếu phép nhân không liên kết, nó chỉ đi kèm với dấu ngoặc đơn để biểu thị thứ tự thực hiện, giống như trong các ví dụ trường học liên quan đến phép cộng và phép nhân hoặc chia.

Hãy xem xét các từ $a_1a_2a_3...a_n$. Có bao nhiêu cách đặt dấu ngoặc đơn trong đó để có thể tính được “tích” không liên kết của các “chữ cái” này? Chúng ta hãy biểu thị số cách như vậy bằng $\varphi(n)$. Rõ ràng là $\varphi(1)=1$ và $\varphi(2)=1$. Đối với từ ba chữ cái $a_1a_2a_3$, có hai cách sắp xếp dấu ngoặc đơn “tốt”: $(a_1a_2)a_3$ và $a_1(a_2a_3)$. Đối với các chữ cái có bốn chữ cái, có năm cách sắp xếp như sau: $a_1(a_2(a_3a_4))$, $a_1((a_2a_3)a_4)$, $(a_1a_2)(a_3a_4)$, $((a_1a_2)a_3)a_4$ và $(a_1(a_2a_3))a_4$. Vì vậy $\varphi(3)=2$, $\varphi(4)=5$. (Hãy thể hiện rằng $\varphi(5)=14$, $\varphi(6)=42$.) Các số $\varphi(n)$ được gọi là số Catalan. Trong «Kvant» số 7 năm 1978, những con số này đã được thảo luận chi tiết. Mối liên hệ giữa những con số này và vị trí của dấu ngoặc cũng được đề cập ở đó. Trong bài viết này tôi muốn đưa ra một chứng minh đơn giản về công thức tính số sau đây

$$\varphi(n) = \frac{1}{2n-1} C_{2n-1}^{n-1}.$$ (*)

(Từ công thức này suy ra rằng số $\frac{1}{2n-1} C_{2n-1}^{n-1}$ là số nguyên cho tất cả $n$.)

Đầu tiên tôi cần giới thiệu khái niệm từ so sánh tuần hoàn. Bắt đầu bằng một ví dụ sẽ dễ dàng hơn. Từ các ký hiệu $a_1, a_2, a_3$, được lấy lần lượt, có thể tạo thành hai loại từ so sánh theo chu kỳ:

$$\{a_1a_2a_3, a_2a_3a_1, a_3a_1a_2\}$$

Và

$$\{a_1a_3a_2, a_3a_2a_1, a_2a_1a_3\}.$$

Để có được các lớp này, bạn cần viết các ký hiệu $a_1, a_2, a_3$ trong một vòng tròn, giống như trên mặt số đồng hồ, sau đó bắt đầu viết theo chiều kim đồng hồ từ bất kỳ ký hiệu nào.

Bây giờ chúng ta hãy đưa ra một định nghĩa chính xác. Hai từ $A$ và $B$ được cho là có thể so sánh theo chu kỳ nếu

$$A = b_1b_2...b_kb_{k+1}...b_n$$

$$B = b_kb_{k+1}...b_nb_1b_2...b_{k-1}.$$

Bây giờ chúng ta hãy tiến hành như sau. Mỗi từ không liên kết (như chúng ta sẽ gọi là các từ có dấu ngoặc đơn được đặt đúng) từ các ký hiệu $a_1, a_2, ..., a_n$ sẽ được liên kết với một từ liên kết (nghĩa là một từ không có dấu ngoặc đơn) từ các ký hiệu $a_1, ..., a_n$, $p$ theo quy tắc sau: $a_i \rightarrow a_i$ và nếu $u \rightarrow A$, $v \rightarrow B$ thì $u \cdot v \rightarrow ABp$. Ví dụ: $a_1a_2 \rightarrow a_1a_2p$, $a_1(a_2a_3) \rightarrow a_1a_2a_3pp$, $a_1((a_2a_3)a_4) \rightarrow a_1a_2a_3pa_4pp$, $(a_1a_2)(a_3a_4) \rightarrow a_1a_2pa_3a_4pp$.

Dễ hiểu là với mỗi từ không liên kết có độ dài $k$ từ các ký hiệu $a_i$ sẽ tương ứng với một số từ liên kết có độ dài $2k-1$, trong đó $p$ xảy ra $k-1$ lần. Điều ngược lại, hữu hạn, là sai. Ví dụ: không thể lấy được các từ $ppa_1a_2a_3$ hoặc $a_1pa_2a_3p$ bằng quy trình được mô tả. Tuy nhiên, tuyên bố sau đây là đúng:

Bổ đề. Đặt $A$ là một từ kết hợp nào đó có độ dài $2n-1$, co-

⟦folio 20⟧

giữ từng biểu tượng $a_i$ ($i=1, 2, \dots, n$) một lần và biểu tượng $p$ $n-1$ lần. Khi đó, có một và chỉ một từ liên kết có thể so sánh theo chu kỳ $A$ (có thể là chính nó) tương ứng với một số từ không liên kết có độ dài $n$ từ các ký tự $a_1, a_2, \dots, a_n$.

Bổ đề này có bản chất tương tự như nhiều bài toán đơn giản được công bố trong «Kvant». Tôi sẽ đưa ra bằng chứng của nó chỉ nhằm mục đích trình bày.

Rõ ràng, trong lớp các từ tuần hoàn có thể so sánh với $A$, sẽ hợp lý khi chỉ xem xét những từ không bắt đầu bằng ký hiệu $p$ mà kết thúc bằng ký hiệu $p$. Tất nhiên, những điều này tồn tại. Trong $A_1$ như vậy - điều này cũng dễ hiểu - có một từ phụ (một phần của từ) có dạng $a_i a_j p$, tương ứng với từ không liên kết $a_i a_j$. Hãy biểu thị phần này của từ $A_1$ bằng $a_i$. Chúng tôi đã nhận được một từ chứa $a_1, a_2, \dots, a_n$, không bao gồm $a_j$ và ký hiệu $p$ xuất hiện $n-2$ lần. Chứng minh bổ đề được rút ra từ quy nạp đơn giản đối với số $n$.

Cơ sở của quy nạp là xét các từ như $a_1 a_2 p$ hoặc tương tự.

Vậy bổ đề đã được chứng minh. Bây giờ công thức (*) trở nên gần như hiển nhiên. Trên thực tế, trong số $2n-1$ vị trí, chúng ta có thể chọn chính xác theo $C_{2n-1}^{n-1}$ cách sắp xếp $n-1$ của ký hiệu $p$ và ở những vị trí còn lại, chúng ta có thể sắp xếp các ký hiệu $a_1, a_2, \dots, a_n$ sao cho trong một từ liên kết “tốt” có thể so sánh theo chu kỳ, các chỉ số $y_i$ theo thứ tự tăng dần từ 1 đến $n$. Vì trong mỗi loại từ có thể so sánh theo chu kỳ có độ dài $2n-1$ có chính xác $2n-1$ lần và số hạng của các phần tử (tại sao?) của chúng là $\varphi(n) = \frac{1}{2n-1} C_{2n-1}^{n-1}$.

Công thức (*) đã được chứng minh.

Để kết luận, tôi muốn kể cho bạn nghe về lịch sử tương tác được tạo ra với nhiệm vụ này.

Tạp chí toán học nổi tiếng của Mỹ “The American Mathematical Monthly” (viết tắt là AMM) năm 1935 đã công bố bài toán của nhà toán học nổi tiếng G. Birkhoff (số 3674) theo công thức sau:

Chứng tỏ rằng với mọi k dương biểu thức $\varphi(k) = \frac{1}{2k-1} C_{2k-1}^{k-1}$ là một số nguyên; chứng minh tính đúng đắn của mối quan hệ truy hồi

$\varphi(k) = \varphi(1) \varphi(k-1) + \varphi(2) \varphi(k-2) + \dots + \varphi(k-1)\varphi(1)$.

Dễ hiểu rằng G. Birkhoff, khi giải quyết các vấn đề tương tự, đã đi đến công thức (*) theo kinh nghiệm. Việc trao đổi thư từ thường xuyên, khi xem xét kỹ hơn, rất indo.

Vấn đề này đã được giải quyết bằng các phương pháp phân tích toán học khá hiệu quả vào tháng 10 năm 1935.

Vì vậy, đối với tôi, dường như thang đo của trang trong cùng một tạp chí năm 1941 đã nhìn thấy bài toán được in (số 3954) của một nhà toán học nổi tiếng khác O. Ore:

Từ ba phần tử $a, b, c$, được cho theo thứ tự cụ thể, có thể tạo ra $\varphi(3)=2$ tích của $(ab)c$ và $a(bc)$, trừ khi chúng ta giả định rằng luật kết hợp đúng. Tương tự, từ bốn yếu tố $a, b, c, d$ người ta có thể tạo ra sản phẩm $\varphi(4)=5$

$[(ab)c]d, [a(bc)]d, a[(bc)d], a[b(cd)], (ab)(cd)$.

Tìm biểu thức tổng quát $\varphi(n)$ cho số nhân $n$.

Trong công thức này, bài toán này đã được giải vào cùng năm 1941. Tôi không quen với lời giải này, vì nó rất bám sát từ một tham chiếu đơn giản đến bài toán trước đó.

Bây giờ đây là những gì thú vị. Năm 1957, các biên tập viên của AMM quyết định dành một số tạp chí riêng cho các bản ghi nhớ của O. Dunkel, người đứng đầu bộ phận vấn đề trong nhiều năm. Ban giám khảo bao gồm 25 bài toán nổi tiếng được gửi đến tạp chí này để đưa vào số báo tương ứng. Thật ngạc nhiên, cả hai bài toán này đều nằm trong số những người được bầu.

(Cuối cùng xem trang 32)
