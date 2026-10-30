---
id: 1970-7-varpahovskiy-kolmogorov-o-reshenii-desyatoy-problemyi-gilberta-dec16bb0
issue: kvant_1970_7
year: 1970
number: "7"
title: Về lời giải bài toán thứ mười của Hilbert
authors:
  - Варпаховский Ф. Л.
  - Колмогоров А. Н.
rubric: osnovnye-stati
page_first: 41
page_last: 46
page_labels: 39, 40, 41, 42, 44
tag: L6M4
lang: vi
source: kvant_digital
extraction: vision
content_sha256: 77bf80f8892614f395026756d516e9984a1a7f50a0c37ad6267e7d97b8ad9639
prompt_sha256: 3ec6b8aabd9b98576af76503cd8a2902b9f5d18e01ee867dfb1228f59c6d52d8
translated_from: content/ru/1970/07/articles/07_varpahovskiy-kolmogorov-o-reshenii-desyatoy-problemyi-gilberta-dec16bb0.md
source_content_sha256: c20a81f9f1d013b3f5638da69a142cf6b8c1a163980e2129cefbb63cb558de9c
translation_model: gpt-5.6-terra
translation_run: vi-codex-2026-10-30
---

⟦folio 39⟧

Trong số thứ ba của «Kvant» đã đưa tin về thành công xuất sắc của nhà toán học trẻ Leningrad Yu. V. Matiyasevich, người gần đây đã thực hiện được bước cuối cùng trong việc giải một trong những «bài toán Hilbert» nổi tiếng, được đặt ra từ năm 1900. Công trình của Yu. V. Matiyasevich được công bố trong Báo cáo của Viện Hàn lâm Khoa học Liên Xô*). Và điều hiếm khi xảy ra là một học sinh suy nghĩ kỹ có thể tự mình hiểu được nội dung cơ bản của công trình này, vốn có ý nghĩa quan trọng đối với khoa học toán học hiện đại. Vấn đề là phần nguyên gốc trong công trình của Yu. V. Matiyasevich được dành cho việc chứng minh một định lý mà phát biểu hoàn toàn sơ cấp và được nêu trong bài báo chúng tôi công bố. Các phương pháp chứng minh cũng sơ cấp. Khó hơn, thực ra, là giải thích bằng ngôn ngữ học sinh có thể hiểu được vì sao định lý này về các số Fibonacci lại có ý nghĩa lớn đến vậy đối với toán học hiện đại. Xét theo phát biểu và các phương pháp chứng minh, nó đúng hơn gợi nhớ một bài toán tối ưu hóa khéo léo.

1. Định lý về các số Fibonacci

Trong toàn bộ phần sau, chúng ta sẽ chỉ làm việc với các số nguyên. Xét tính chất sau của một cặp số (a, b):

“b chia hết cho a”.

Tính chất này của một cặp số cũng có thể diễn đạt như sau:

“tồn tại một số x sao cho ax—b=0”.

Chúng ta đã diễn đạt tính chất của cặp số (a, b) thông qua sự tồn tại nghiệm của phương trình

ax—b=0

(nhắc lại một lần nữa rằng chúng ta chỉ làm việc với các số nguyên và do đó chỉ với các nghiệm nguyên). Phương trình này có dạng

P(a, b, x) = 0,

trong đó P là một đa thức của ba biến a, b, x.

Bây giờ ta đưa ra một định nghĩa tổng quát; tính chất của một dãy hữu hạn các số (a₁, a₂, ..., aₘ) được gọi là Diophant nếu tồn tại một đa thức nào đó của m + n biến

P(a₁, a₂, ..., aₘ), sao cho dãy (a₁, a₂, ..., aₘ) có tính chất của chúng ta khi và chỉ

*) Đây là tên và «địa chỉ» chính xác của bài báo: Yu. V. Matiyasevich. Tính Diophant của các tập hợp liệt kê được, DAN Liên Xô, 1970, tập 191, số 2.

⟦folio 40⟧

khi tồn tại các số $x_1, x_2, \dots, x_n$, đối với chúng $P(a_1, a_2, \dots, a_m, x_1, x_2, \dots, x_n) = 0$.

Thành tựu cơ bản của Matiyasevich chính là ở việc chứng minh tính Diophant của một tính chất đặc biệt nào đó của các cặp số $(a, b)$.

Nhiều bạn đã biết các số Fibonacci

$$\psi_0 = 0, \quad \psi_1 = 1,$$
$$\psi_2 = \psi_0 + \psi_1 = 1,$$
$$\psi_3 = \psi_1 + \psi_2 = 2,$$
$$\psi_4 = \psi_2 + \psi_3 = 3,$$
$$\psi_5 = \psi_3 + \psi_4 = 5,$$

mà dãy vô hạn của chúng được xác định bởi công thức truy hồi

$$\psi_{n+1} = \psi_{n-1} + \psi_n.$$

Tính chất của cặp số $(a, b)$ mà Matiyasevich xét là:

“$b$ là một số Fibonacci

mang số thứ tự $2a$”, tức là $b = \psi_{2a}$.

Rõ ràng, các cặp

$(0,0), (1,1), (2,3), (3,8)$

v.v. có tính chất này. Khẳng định rằng tính chất của Matiyasevich là Diophant có nghĩa là tồn tại một đa thức

$$Q(a, b, x_1, x_2, \dots, x_n)$$

sao cho $b$ là số Fibonacci thứ $2a$ khi và chỉ khi tồn tại các số $x_1, x_2, \dots, x_n$ sao cho

$$Q(a, b, x_1, x_2, \dots, x_n) = 0.$$

Về nguyên tắc, đa thức $Q$ với các hệ số nguyên có thể được viết ra tường minh. Matiyasevich không làm điều đó và thậm chí không cho biết số $n$ các biến phụ là bao nhiêu.

Về chứng minh của định lý đã phát biểu, như đã nói, nó hoàn toàn sơ cấp. Matiyasevich viện dẫn một bổ đề được chứng minh trong cuốn sách của N. N. Vorobyov “Các số Fibonacci”, dành cho học sinh, và một kết quả được chứng minh trong cuốn sách uyên bác hơn của A. I. Mal'tsev, nhưng cũng sơ cấp. Trong chính công trình của Matiyasevich, mười chín bổ đề được nêu mà không chứng minh, nhưng chứng minh của từng bổ đề riêng lẻ không khó hơn những bài toán thông thường dành cho học sinh. Khó khăn chỉ ở chỗ tìm ra đúng tổ hợp các mệnh đề sơ cấp dẫn tới mục đích cuối cùng.

2. Tại sao tất cả điều này lại quan trọng đến vậy?

Nếu đa thức $Q$ của Matiyasevich thực sự rất cần cho các nhà toán học để thực hiện những phép tính nào đó, thì có lẽ Matiyasevich đã không ngại viết nó ra tường minh. Nhưng trên thực tế, bản thân việc dùng các số Fibonacci có tính chất kinh nghiệm, để lần lượt viết ra tất cả các cặp có tính chất này

$(0,0), (1,1), (2,3), (3,8), (4,21), (5,55), \dots$

Vì số các cặp ấy là vô hạn, nên quá trình viết chúng ra sẽ không bao giờ kết thúc. Nhưng ta có một quy tắc theo đó các cặp của ta có thể được viết ra từng cặp một với sự chắc chắn rằng

1) chỉ những cặp có tính chất của Matiyasevich mới được viết ra,
2) bất cứ cặp nào có tính chất của Matiyasevich thì sớm hay muộn cũng sẽ được viết ra.

Một tính chất (bằng ngôn ngữ uyên bác hơn là “vị từ”) của một dãy hữu hạn các số $(a_1, a_2, \dots, a_m)$ được gọi là liệt kê được, nếu tồn tại một quy tắc cho phép bằng cách áp dụng máy móc quy tắc đó thu được lần lượt các dãy, nhất thiết có tính chất đã cho, và sao cho bất cứ dãy nào

⟦trang 41⟧

có tính chất ấy sớm hay muộn cũng sẽ được thu được.

Theo quan điểm hiện đại, hệ quả quan trọng nhất của định lý Matiyasevich về các số Fibonacci là

Định lý 1. Mọi tính chất liệt kê được của một dãy hữu hạn các số đều là Diophantine.

Trước năm 1961, định lý này có vẻ cực kỳ bất ngờ. Nhưng một kết quả yếu hơn nào đó của Davis, Putnam và Robinson, được chứng minh năm 1961, khiến giả thuyết như vậy không còn quá khó tin. Các nhà toán học đã bỏ ra không ít công sức để chứng minh nó. Matiyasevich cũng đã sử dụng một số, như người ta nói, “phép quy giản” của bài toán về các bài toán chuyên biệt hơn. Nhưng ý tưởng quy tất cả về tính chất của các số Fibonacci, ngay trong hoàn cảnh đã hình thành vào năm 1970, vẫn là bất ngờ.

Như vậy, thành công lớn của Matiyasevich đòi hỏi sự kết hợp giữa hiểu biết về những vấn đề lớn của toán học hiện đại và tri thức sâu rộng trong lĩnh vực của mình với nghệ thuật tìm ra những con đường sơ cấp hoàn toàn bất ngờ để giải các bài toán chuyên biệt.

3. Matiyasevich đã giải bài toán thứ mười của Hilbert theo nghĩa nào

Bài toán thứ mười của Hilbert*) nói về các phương trình dạng

$$P(x_1, x_2, \ldots, x_n) = 0,$$

trong đó $P$ là một đa thức với các hệ số nguyên. Bậc của phương trình như vậy được gọi là bậc của đa thức $P$. Khi câu hỏi được đặt ra về việc tìm nghiệm nguyên của chúng, các phương trình này được gọi là “Diophantine”. Chẳng hạn, phương trình

$$x^2 + y^2 = 1$$

có bốn nghiệm nguyên

$$x = \pm 1, \quad y = \pm 1,$$

*) Có thể đọc chi tiết hơn về các bài toán của Hilbert trong cuốn sách D. Hilbert, “Các bài toán toán học”, “Nauka”, 1969.

còn phương trình

$$x^2 + y^2 = 3$$

không có nghiệm nguyên.

Bây giờ hãy để chính Hilbert lên tiếng:

“Cho một phương trình Diophantine bất kỳ với số lượng ẩn bất kỳ ...; cần chỉ ra một phương pháp tổng quát, theo đó có thể trong một số hữu hạn bước biết được phương trình đã cho có nghiệm nguyên ... hay không”.

Hilbert, dường như, tin rằng phương pháp tổng quát cần tìm tồn tại, và vấn đề chỉ là tìm ra nó. Đã có không ít nỗ lực nhằm tìm kiếm phương pháp này, nhưng không thu được kết quả nào đáng khích lệ.

Bài toán về các nghiệm nguyên của một phương trình bất kỳ dễ dàng quy về bài toán về các nghiệm tự nhiên (nguyên không âm). Hơn nữa, không khó để chỉ ra rằng chỉ cần xét các phương trình Diophantine có bậc không quá bốn. Đối với các phương trình Diophantine bậc không quá hai, phương pháp tổng quát cần tìm đã được tìm ra, nhưng các phương trình bậc ba đã không khuất phục trước bất kỳ nỗ lực nào.

Do những thất bại theo hướng này, đã nảy sinh nghi ngờ rằng phương pháp tổng quát được nói đến trong phát biểu của Hilbert đơn giản là không tồn tại! Tình huống tương tự cũng xảy ra trong một số bài toán khác có tính chất tương tự. Tuy nhiên, tìm được phương pháp tổng quát cần thiết là một việc — ở đây chỉ cần đưa ra phương pháp đó và trực tiếp kiểm tra rằng nó thỏa mãn các điều kiện do Hilbert đề ra.

Còn để chứng minh sự không tồn tại của một phương pháp nào đó nhằm giải một loạt bài toán, cần phải đưa ra định nghĩa chính xác về phương pháp tổng quát ấy là gì, nó có thể được thực hiện như thế nào và bằng những phương tiện nào.

Đầu những năm ba mươi, các định nghĩa tương ứng đã được xây dựng trong các công trình của nhà khoa học Mỹ Church và nhà khoa học Anh Turing. Các định nghĩa này đã đặt nền móng cho lý thuyết thuật toán. Nhìn lại chặng đường đã qua, các nhà toán học phải biết ơn bài toán thứ mười của Hilbert ít nhất vì nó đã là một trong các động lực cho sự ra đời của lý thuyết này.

Trong khuôn khổ lý thuyết thuật toán cũng đã thu được định nghĩa chính xác của khái niệm “tính chất liệt kê được”, mà chúng ta đã sử dụng ở mục trước.

Hóa ra từ tính Diophantine của bất kỳ tính chất liệt kê được nào của một dãy số hữu hạn suy ra

Định lý 2. Không thể có một phương pháp tổng quát (thuật toán) cho phép, đối với bất kỳ phương trình Diophantine đã cho nào, xác định nó có nghiệm nguyên hay không.

Từ định lý của mình về tính Diophantine của tính chất đặc biệt của một cặp số (a, b)

$$b = \psi_{2a}$$

Matiyasevich đã suy ra chứng minh của định lý 1, mà như đã biết, kéo theo định lý 2, tức là lời giải phủ định cho bài toán thứ mười của Hilbert.

Để hiểu trọn vẹn mọi điều đã nói, bạn chỉ còn thiếu sự hiểu biết rõ ràng về “thuật toán” (phương pháp tổng quát để giải một dãy vô hạn các bài toán) và “tính chất liệt kê được” (vị từ liệt kê được) là gì. Nhưng đó đã là một chủ đề khó hơn đáng kể.

4. Các định nghĩa và sự kiện của lý thuyết thuật toán

1. Trong số các hàm được xác định trên tập N các số tự nhiên và nhận các giá trị tự nhiên, lớp các hàm đệ quy nguyên thủy được выделяется như sau.

Xét hàm S(n) n+1 và q(n)=n-p, trong đó p²≤n<(p+1)². Từ các hàm f(n) và q(n) có thể tạo thành hàm h₁(n)=f(n)+q(n) (phép cộng), $h_2(n)=f(q(n))$ (phép thế), còn từ một hàm f(n) — hàm được xác định bởi các đẳng thức h₃(0)=0, h₃(n+1)=f(h₃(n)) (phép lặp). Lớp các hàm đệ quy nguyên thủy gồm các hàm S, q và tất cả những hàm có thể nhận được từ chúng bằng một số hữu hạn phép cộng, phép thế và phép lặp.

Ví dụ. Hãy chỉ ra rằng các hàm φ(n)=2n và φ(n)=2n+1 là đệ quy nguyên thủy. Trước hết, áp dụng phép lặp cho hàm S(n)=n+1. Khi đó h(0)=0, h(n+1)=S(h(n))=h(n)+1. Do đó, h(n)=n và φ(n) nhận được bằng cách áp dụng phép cộng cho hai hàm, mỗi hàm đều bằng h(n): φ(n)=h(n)+h(n)=n+n=2n. Cuối cùng, hàm φ(n) nhận được bằng phép thế, áp dụng cho các hàm S(n)=n+1 và φ(n)=2n: φ(n)=S(φ(n))=S(2n)=2n+1.

2. Tập M các số tự nhiên được gọi là liệt kê được nếu nó trùng với tập các giá trị của một hàm đệ quy nguyên thủy nào đó.

Chẳng hạn, tập các số chẵn là liệt kê được, vì nó là tập các giá trị của hàm đệ quy nguyên thủy φ(n)=2n. Tập các số lẻ, trùng với tập các giá trị của hàm đệ quy nguyên thủy φ(n)=2n+1, cũng liệt kê được.

3. Tập M được gọi là quyết định được nếu nó liệt kê được cùng với phần bù N—M của nó (trong đó N—tập tất cả các số tự nhiên).

Đặc biệt, tập các số quyết định được, vì nó liệt kê được cùng với phần bù của nó (tập các số lẻ).

4. Tồn tại các tập liệt kê được nhưng không quyết định được.

Có thể đưa ra một ví dụ cụ thể về một tập như vậy, tuy nhiên cấu trúc tương ứng quá phức tạp về mặt kỹ thuật để có thể trình bày trong khuôn khổ chú thích này.

Bây giờ giả sử đã cho một tập M nào đó gồm các số tự nhiên. Có thể đặt câu hỏi: liệu có tồn tại một phương pháp chung mà với mỗi số tự nhiên n, trong một số hữu hạn bước, xác định được n này có thuộc tập M hay không. Mệnh đề cơ bản của lý thuyết thuật toán (luận đề Church) khẳng định rằng một phương pháp (thuật toán) như vậy tồn tại khi và chỉ khi tập M quyết định được.

⟦folio 44⟧

trình tự, sao cho bất đẳng thức $v > u^n$ là đúng. Hoàn cảnh này được minh họa bằng bảng dẫn ở tr. 43. (Trong đó đánh dấu những ô mà ở đó các số $u^k$ nhỏ hơn các số $v$ tương ứng).

Sau khi tính chất đã nêu được kiểm tra, Matiyasevich đã «chỉnh sửa» dãy Fibonacci bằng cách loại bỏ khỏi nó các số hạng lẻ. Cụ thể, ông xét dãy được xác định bởi các hệ thức sau: $\varphi_0 = 0, \varphi_1 = 1, \varphi_{n+1} = 3\varphi_n - \varphi_{n-1}$. Chính xác thu được dãy gồm các số hạng chẵn của dãy ban đầu: $\varphi_0 = 0, \varphi_1 = 1, \varphi_2 = 3, \varphi_3 = 8, \varphi_4 = 21, \varphi_5 = 55, \varphi_6 = 144, \varphi_7 = 377$ v.v. Lấy $u$ là chỉ số của một số hạng của dãy, còn $v$ là số hạng có chỉ số $u$, tức là $\varphi_u$, ta lại có tính chất cần thiết đối với $u$ và $v$. Bây giờ chỉ còn xây dựng phương trình $P(u, v, x_1, \dots, x_k) = 0$, có nghiệm tự nhiên khi và chỉ khi $v = \varphi_u$, — phần còn lại là áp dụng kết quả của Julia Robinson! Để làm điều đó, chỉ cần xây dựng một hệ phương trình Diophantine $P_1 = 0, \dots, P_n = 0$ theo các biến $u, v, x_1, \dots, x_k$, có nghiệm khi và chỉ khi $v = \varphi_u$ — vì hệ này có chính xác các nghiệm giống như phương trình duy nhất $P_1^2 + \dots + P_n^2 = 0$.

Matiyasevich đã thu được hệ phương trình cần thiết dưới dạng sau:

1) $u + (a - 1) = v$,
2) $v + b = l$,
3) $l^2 - lk - k^2 = 1$,
4) $g^2 - gh - h^2 = 1$,
5) $l^2c = g$,
6) $ld = r - 2$,
7) $(2h + g)e = r - 3$,
8) $x^2 - rxy + y^2 = 1$,
9) $lp = x - u$,
10) $(2h + g)q = x - v$.

Để chứng minh rằng sự tồn tại của một nghiệm tự nhiên của hệ này tương đương với điều kiện $v = \varphi_u$, Matiyasevich đã dùng đặc trưng sau đây của tính chất của dãy $\{\varphi_k\}$:

cặp điều kiện $x < y$ và $x^2 - 3xy + y^2 = 1$ tương đương với sự tồn tại một $k$ sao cho $x = \varphi_k$ và $y = \varphi_{k+1}$.

Chúng tôi khuyên bạn đọc quan tâm thử sức mình trong việc chứng minh sự tương đương này.

Cuối cùng, xin chỉ ra rằng lời giải tìm được của bài toán thứ mười có một số hệ quả thú vị, trong đó, có lẽ hiệu quả nhất là hệ quả sau: có thể chỉ ra một đa thức cụ thể bậc mười, tập các giá trị dương của nó trùng với tập tất cả các số nguyên tố!

Khoa học toán học đã ghi vào thành tích của mình một thành tựu nghiêm túc và đáng ghi nhận.

Bài tập 1

1. Chứng minh rằng với mọi $k$, các số $\varphi_k$ và $\varphi_{k+1}$ nguyên tố cùng nhau.
2. Chứng minh hệ thức: $\varphi_{k+1} = \varphi_k + 1$.
3. Chứng minh rằng phương trình Diophantine $P(y, x_1, \dots, x_k) = 0$ có nghiệm trong các số nguyên dương khi và chỉ khi phương trình sau có nghiệm như vậy

$$Z = (1 - (P(z, x_1, \dots, x_k))^2) - y.$$

Do lỗi của nhà in, trong “Kvant” số 5 (tr. 64, bài 1226) công thức chia các số được sắp chữ không đúng. Nó phải có dạng như sau:

$$\frac{1}{2} \times \frac{1}{2} \times \frac{1}{2} \times \frac{1}{2} \times \frac{1}{2} \times \frac{1}{2} \times \frac{1}{2} \times \frac{1}{2} \times \frac{1}{2} \times \frac{1}{2} \times \frac{1}{2} \times \frac{1}{2} \times \frac{1}{2}$$
