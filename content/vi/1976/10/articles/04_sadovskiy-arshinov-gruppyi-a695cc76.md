---
id: 1976-10-sadovskiy-arshinov-gruppyi-a695cc76
issue: kvant_1976_10
year: 1976
number: "10"
title: Nhóm
authors:
  - Садовский Л. Е.
  - Аршинов М. Н.
rubric: osnovnye-stati
page_first: 8
page_last: 14
page_labels: 6-12
tag: Y6VB
lang: vi
source: kvant_digital
extraction: vision
content_sha256: 851e52a8d7d611486c0fd79259efa6b3dd0ffe9045c685714280e0039b11a2a5
prompt_sha256: draft-1
translated_from: content/ru/1976/10/articles/04_sadovskiy-arshinov-gruppyi-a695cc76.md
source_content_sha256: f0194078460b25ef6fa541a554914aabfd69d307bad793fd5bea1cd17130456d
translation_model: draft
translation_run: vi-draft-2026-10-31
translation_quality: draft
---

⟦folio 6⟧

L. Sadovsky,
M. Artsinov
NHÓM

Toán học thế kỷ XXI có thể rất khác với toán học của chúng ta; có lẽ một học sinh bắt đầu học đại số với lý thuyết nhóm thay thế, điều mà bây giờ anh ta có thể làm nếu không có truyền thống đã được thiết lập.
Simon Newcombe, 1893

Đại số nghiên cứu các hành động (phép toán) khác nhau và các nguyên tắc mà chúng tuân theo. Các phép toán này có thể được xác định không chỉ trên các số, đa thức và vectơ mà bạn đã biết từ khóa học toán học và vật lý ở trường mà còn trên các phần tử có bản chất khác.
Trong bài viết của A. Kolmogorov, các bạn đã làm quen với hoạt động thành phần các chuyển vị và khái niệm “nhóm chuyển vị”. Ở đây chúng ta sẽ nói về một cấu trúc đại số trừu tượng được gọi là nhóm.

Các nhà toán học phải mất gần nhiều năm mới phát triển được khái niệm nhóm ở dạng hiện đại. Hai trăm năm trước, nhà khoa học nổi tiếng người Pháp Joseph-Louis Lagrange (1736-1813), khi nghiên cứu lời giải phương trình đại số theo bán kính, đã thực sự vận dụng khái niệm nhóm, mặc dù bản thân ông không sử dụng thuật ngữ này. Năm 1771, ông đã xây dựng và chứng minh định lý cơ bản đầu tiên trong lý thuyết nhóm.

Nghiên cứu của Lagrange được tiếp tục bởi nhà toán học người Na Uy Niels Henrik Abel và người Pháp Evariste

⟦folio 7⟧

Galois*), người đầu tiên đặt ra thuật ngữ “nhóm”. Các phần tử của các nhóm mà ông coi là sự thay thế các nghiệm của phương trình đại số
$$a_n x^n + a_{n-1} x^{n-1} + \dots + a_1 x + a_0 = 0.$$
Nhóm hoán vị cũng được nghiên cứu bởi Augustin-Louis Cauchy (1789-1857), Arthur Cayley (1821-1903), Camille Jordan (1838-1922) và các nhà toán học nổi tiếng khác. Định nghĩa được chấp nhận hiện nay về nhóm được Cayley đề xuất vào năm 1854.

Tính chất đối xứng, phổ biến trong tự nhiên, có liên quan chặt chẽ đến nhóm có thể hiểu được. Không chỉ những bông tuyết, tổ ong, muối ăn và tinh thể thạch anh mới có tính đối xứng. Các hạt cơ bản cũng tuân theo “định luật đối xứng” - liên hợp điện tích, theo đó mỗi hạt tương ứng với một phản hạt. Cơ sở cho sự đối xứng của thế giới xung quanh chúng ta là các nguyên lý năng lượng tương đối của Galileo, các định luật bảo toàn năng lượng, động lượng, điện tích, v.v.

Việc nghiên cứu các định luật đối xứng, chung cho những biểu hiện đa dạng nhất của nó, đã dẫn đến việc tạo ra một bộ máy toán học đặc biệt gọi là lý thuyết nhóm.

Định nghĩa của một nhóm dựa trên khái niệm về phép toán nhị phân.

Hoạt động nhị phân
Giả sử rằng mỗi cặp có thứ tự $a$ và $b$ của các phần tử của một số tập hợp tùy ý $G$ được liên kết với một số phần tử $c$ của cùng một tập hợp. Khi đó chúng ta nói rằng một phép toán nhị phân được xác định trên tập $G$. Kết quả của việc áp dụng thao tác này với một cặp phần tử cho trước, viết dưới dạng ký hiệu
$$a * b = c.$$
*) Về những toán học này, xem «Kvant», 1973, số 10 và 1976, số 5.

Đôi khi thuật ngữ ghép được chọn cho phép toán nhị phân, nghĩa là phép cộng, phép nhân hoặc phép hợp. Một ví dụ về phép toán nhị phân là thành phần của các chuyển động trên một mặt phẳng.

Sản phẩm $a * b$ và $b * a$ có thể giống hoặc khác nhau. Trong trường hợp đầu tiên, họ nói rằng $a$ và $b$ tính toán (hoán vị), trong trường hợp thứ hai họ không tính toán. Phép toán nhị phân * được gọi là giao hoán nếu với bất kỳ $a, b$ nào có $a * b = b * a$ và không giao hoán nếu có ít nhất một cặp phần tử $a, b$ mà $a * b \neq b * a$.

Bài toán 1. Kiểm tra xem
a) phép cộng thông thường là phép toán nhị phân trên tập $Z$ của tất cả các số nguyên;
b) phép nhân cũng là một phép toán nhị phân trên tập $Z$.

Vì vậy, trên cùng một tập hợp, nói chung, người ta có thể định nghĩa các phép toán nhị phân khác nhau.

Bài toán 2. Là $Z$ phép toán nhị phân trên tập hợp
a) phép chia;
b) phép trừ?
Những phép toán này có giao hoán không?
Bài toán 3. Các phép tính cộng, trừ, nhân, chia nhị phân có trên tập hợp toàn số lẻ không?

Chỉ có hai khả năng để di chuyển một bộ ba phần tử $a, b, c$ nhất định mà không thay đổi thứ tự của chúng: $(a * b) * c$ hoặc $a * (b * c)$. Nếu như
$$(a * b) * c = a * (b * c),$$
thì bộ ba phần tử $a, b, c$ được gọi là liên kết; Đối với cô, ký hiệu $a * b * c$ có một ý nghĩa nhất định. Nếu các phép toán * mỗi bộ ba phần tử liên kết với nhau thì chính phép toán đó * được gọi là liên kết.

Bài toán 4. Các hoạt động sau có liên quan không:
a) thành phần của chuyển động;
b) phép cộng và nhân số thực (phức);
b) chia và nâng các số lên lũy thừa $(a * n = a^n)$?

⟦folio 8⟧

Định nghĩa nhóm

Một tập hợp $G$ có phép toán nhị phân * được xác định trên đó được gọi là một nhóm nếu ba tiên đề được thỏa mãn:

Tiên đề I (sự tồn tại của một yếu tố duy nhất). Có một phần tử duy nhất $e$ của tập hợp $G$ sao cho

$$e * a = a * e = a$$

đối với mọi phần tử $a$ của $G$.

Tiên đề II (sự tồn tại của một phần tử nghịch đảo). Với mỗi phần tử $a$ của tập hợp $G$ tồn tại một phần tử $a^{-1}$ sao cho

$$a * a^{-1} = a^{-1} * a = e.$$

Tiên đề III (tính kết hợp của phép toán nhị phân). Đối với bất kỳ phần tử ba $a, b, c$ nào từ $G$ đẳng thức

$$a * (b * c) = (a * b) * c.$$

Nếu một phép toán nhị phân có tính giao hoán thì nhóm được gọi là Abelian (để vinh danh Abelai) hoặc giao hoán, ngược lại - không phải Abelian hoặc không giao hoán.

Vì vậy, một tập hợp sẽ trở thành một nhóm ngay khi một phép toán nhị phân được thực hiện trên đó, phụ thuộc vào ba tiên đề đã chỉ ra. Đồng thời, không có gì được giả định liên quan đến chính các phần tử của tập hợp này: chúng có thể là số, đa thức, chuyển vị hoặc đối tượng có tính chất khác.

Bây giờ đã đưa ra định nghĩa về nhóm, mọi người sẽ thấy rằng mình đã quen thuộc với nhóm từ lâu. Trong thực tế, nhiều tập hợp số liên quan đến các phép tính tổng quát của phép cộng và phép nhân tạo thành một nhóm. Như vậy, một nhóm là một tập hợp các số nguyên có phép cộng; nó được gọi là nhóm cộng các số nguyên. Đây là một nhóm Abelian, phần tử “đơn vị” của nó là số: $0 + c = c + 0 = c$, nghịch đảo của một số tùy ý là số đối của nó: $c + (-c) = 0$.

Hình 1.

Nhóm cũng được hình thành bởi tập hợp $G$ của tất cả các thay đổi ánh xạ lên chính chúng một số hàm (tel) $F$. Nhóm này đóng vai trò là đặc điểm của tính đối xứng của các hàm $F$ và được gọi là nhóm của hàm đối xứng $F$.

Bài toán 5. Kiểm tra xem tập hợp số hữu tỉ và số thực bằng phép cộng có phải là nhóm hay không (nhóm cộng được của số hữu tỉ và số thực).

Bài toán 6. Chứng minh rằng
a) lý trí tích cực;
b) Các số thực dương khi nhân với nhau tạo thành nhóm (nhóm nhân của số hữu tỉ dương và số thực dương).

Bài toán 7. Các nhóm có tạo thành tập hợp số hữu tỉ và số thực bằng phép nhân không?

Ba người một nhóm

Người đầu tiên (số học). Chúng ta hãy sửa một số tự nhiên $n$ ($n \neq 1$) và xét tập hợp (ký hiệu là $T_n$) số dư khi chia mỗi số tự nhiên cho $n$. Rõ ràng có chính xác $n$ số dư khác nhau, chúng bằng các tương ứng 0, 1, 2, . . . , $n-1$. Bất kỳ hai số $k$ và $l$ nào khi chia cho $n$ đều có số dư bằng nhau, được gọi là so sánh modulo $n$ và viết

$$k \equiv l \pmod n.$$

Bây giờ chúng ta mở rộng tập hợp số tự nhiên $N$ thành các lớp $n$ theo nguyên tắc sau.

Trong lớp 0 (để biểu thị là thuận tiện khi sử dụng cùng một số 0), chúng tôi thu thập tất cả các số mà khi chia cho $n$, sẽ cho

⟦folio 9⟧

số dư 0, tức là $a$ sao cho $a \equiv 0$ (mod $n$).

Trong lớp đầu tiên, giá trị riêng $a \equiv 1$ (mod $n$), tức là để lại số dư 1 khi chia cho $n$.

Nói chung, chúng tôi đặt tất cả các số $a \equiv k$ (mod $n$) vào lớp thứ $k$. Để chỉ định lớp này, chúng tôi sử dụng cùng một số $k$ (Hình 1).

Bây giờ chúng ta định nghĩa một phép toán nhị phân trên tập $Z_n$ của các lớp được xây dựng. Đặt $k$ và $l$ là hai lớp bất kỳ. Hãy chọn bất kỳ số nào từ mỗi số đó, ví dụ: $a$ và $b$: $a \equiv k$ (mod $n$), $b \equiv l$ (mod $n$).

Hãy cộng tổng số tiền $a+b$ và chia cho $n$. Khi đó phần còn lại sẽ là $k+l$ (nếu $k+l < n$) hoặc $k+l-n$ (nếu $k+l \geq n$).

Điều này có nghĩa là thao tác sau $\oplus$ có ý nghĩa (hãy gọi nó là “bổ sung lớp”):

$$k \oplus l = \begin{cases} k+l, & \text{ если } k+l < n, \\ k+l-n, & \text{ если } k+l \geq n. \end{cases}$$

Ví dụ: tại $n=3$ có ba lớp: 0, 1, 2. Bảng cộng cho các lớp này trông như sau:

| $\oplus$ | 0 | 1 | 2 |
| :--- | :--- | :--- | :--- |
| 0 | 0 | 1 | 2 |
| 1 | 1 | 2 | 0 |
| 2 | 2 | 0 | 1 |

Tập $Z_n$ đối với phép toán $\oplus$ tạo thành một nhóm gọi là nhóm dư modulo $n$. Thật vậy, tất cả các tiên đề nhóm đều được thỏa mãn: phần tử trung hòa là lớp 0; phần tử đối diện của lớp $k$ ($k \neq 0$) là lớp $n-k$ ($-0=0$). Cuối cùng, thao tác $\oplus$ có tính kết hợp (kiểm tra!).

Mặt thứ hai (hình học). Tập hợp các phép quay của mặt phẳng quanh tâm $O$ của một $n$-giác đều theo các góc $\alpha$, tại đó $n$-giác này được ánh xạ lên chính nó, cũng tạo thành một nhóm xét về phép tính $\oplus$ thành phần của một biến. Nghịch đảo của $R^\alpha$ là $R^{-\alpha}$:

$$R^\alpha \circ R^{-\alpha} = E.$$

Trong nhóm này có các phần tử $n$ (các lượt $R^{\alpha_k}$, trong đó $\alpha_k = k \cdot \frac{360^\circ}{n}$, $k=0, 1, \dots, n-1$; xem Hình 2) và thành phần chính xác của các lượt có thể được viết như sau:

$$R^{\alpha_k} \circ R^{\alpha_m} = \begin{cases} R^{\alpha_k+m}, & \text{ если } k+m < n, \\ R^{\alpha_k+m-n}, & \text{ если } k+m \geq n. \end{cases}$$

Đây là vị trí đúng trong phép cộng (1) đúng của các lớp, sử dụng nó chúng ta có thể viết:

$$R^{\alpha_k} \circ R^{\alpha_m} = R^{\alpha_k+m}.$$

Người thứ ba (phức tạp). Nó có thể được làm trơn tru bởi những người đã quen với số phức và các phép toán trên chúng. Bây giờ chúng ta quan tâm đến tập hợp tất cả các nghiệm phức bậc $n$ của các đơn vị, tức là tập lời giải của phương trình $z^n=1$.

Nếu $z=\cos \alpha+i\sin \alpha$ là dạng lượng giác của một số như vậy thì theo quy tắc nhân số phức, $z^n=\cos n\alpha+i\sin n\alpha$. Đẳng thức $z^n=1$ đúng cho $n\alpha=2\pi k$, trong đó $k$ là một số nguyên, vì vậy tất cả $n$ nghiệm phân biệt của đơn vị đều được tính theo công thức

$$z_k=\cos \frac{2\pi}{n} k+i\sin \frac{2\pi}{n} k$$

($k=0, 1, \dots, n-1$). Dễ dàng kiểm tra

⟦folio 10⟧

rằng tập hợp tất cả các nghiệm này tạo thành một nhóm với quy tắc nhân sau:

$$z_h \cdot z_l = z_{k \oplus l}.$$

(3)

Chúng ta hãy nhớ lại rằng mỗi số phức $z = r$ (với $\alpha + i \sin \alpha$) với mô hình $r$ và đối số $\alpha$ được biểu diễn trong hệ tọa độ hình chữ nhật bằng một vectơ có chiều dài $r$, tạo một góc $\alpha$ với trục $Ox$. Do đó, các số $z_h$ được biểu diễn bằng các vectơ có độ dài 1 sao cho cứ hai vectơ liền kề nhau tạo một góc $2\pi/n$ với nhau. Nói cách khác, điểm cuối của các vectơ này nằm ở các đỉnh của $n$-gon thông thường (Hình 3).

Bây giờ rõ ràng là nhóm nghiệm thứ $n$ của một và nhóm phép quay $R^{\alpha_k}$ về cơ bản là “không khác” và “tương tự” với nhóm $Z_n$. Để làm rõ cụm từ cuối cùng, cần giới thiệu một trong những khái niệm quan trọng nhất của toán học.

Khái niệm đẳng cấu

Xét hai nhóm bất kỳ $G$ và $H$. Giả sử rằng sự tương ứng một-một đã được thiết lập giữa các phần tử của các nhóm này (chúng tôi biểu thị nó bằng chữ cái $\varphi$), nghĩa là đưa ra một ánh xạ nghịch đảo $\varphi$ tập $G$ lên tập $H$. Chúng ta hãy chọn một cặp phần tử tùy ý $a, b$ trong $G$; chúng tương ứng với một số phần tử $\varphi(a), \varphi(b)$ trong $H$. Vì $G$ và $H$ là các nhóm nên tích $ab \in G$, $\varphi(a) \varphi(b) \in H$ và $\varphi(ab) \in H$ cũng được xác định.

Về giới hạn. Các nhóm $G$ và $H$ được gọi là đẳng cấu nếu có một ánh xạ một-một $\varphi$ của nhóm $G$ lên nhóm $H$ để bảo toàn sản phẩm, nghĩa là với bất kỳ $a, b \in G$ nào cũng có $\varphi(a) \varphi(b) = \varphi(ab)$.

Ánh xạ này được gọi là đẳng cấu.

Tính đẳng cấu của hai nhóm sẽ làm rõ rằng các quy luật chi phối hoạt động của cả hai nhóm là giống nhau và mọi tính chất vốn có trong hoạt động của một trong các nhóm đều như nhau.

trong phạm vi một hoạt động vốn có trong một nhóm đẳng cấu với nó. Do đó, các nhóm đẳng cấu được gọi là “bằng nhau một cách trừu tượng” và được xác định với nhau, dẫn đến sự xuất hiện của một nhóm trừu tượng: một nhóm liên quan đến bản chất của các thành phần mà không có giả định cụ thể nào được đưa ra.

Một ví dụ về nhóm đẳng cấu là ba nhóm vừa xem xét: nhóm dư lượng, nhóm phép quay và nhóm nghiệm đơn vị trên thực tế chỉ là ba cách thể hiện của cùng một nhóm trừu tượng.

Đẳng cấu $\psi$ giữa nhóm quay và nhóm $Z_n$ là bản đồ

$$\psi (R^{\alpha_k}) = k.$$

Rõ ràng là trong trường hợp này tích của phép quay sẽ tương ứng, như sau từ công thức (2), với tổng các số dư.

Sự đẳng cấu $\varphi'$ giữa nhóm phép quay của một $n$-giác đều và nhóm căn bậc $n$ của các số 1 được xác lập bằng sự tương ứng

$$\varphi (R^{\alpha_k}) = z_k.$$

Tất nhiên, quy tắc (4) được thỏa mãn; nó suy ra từ đẳng thức (3).

Bài toán 8. Thiết lập đẳng cấu giữa nhóm căn bậc $n$ của đơn vị và nhóm $Z_n$ của dư lượng modulo $n$.

Bài toán 9. Xây dựng đẳng cấu giữa nhóm cộng của tất cả các số thực và nhóm nhân của các số thực dương.

⟦folio 11⟧

Nhóm đối xứng

Thật dễ dàng để phân biệt một hình đối xứng với một hình không đối xứng - trực giác giúp chúng ta điều này. Nó cho chúng ta biết rằng hình vuông đối xứng hơn hình thoi và hình tròn đối xứng hơn hình thoi. Nhưng chỉ trực giác thôi thì chưa đủ. Những cân nhắc chi tiết hơn nảy sinh khi xem xét các chuyển vị của không gian (hoặc mặt phẳng), trong đó các hình F đã cho sẽ được ánh xạ lên chính nó. Khả năng của các phép biến đổi như vậy (với hoạt động thành phần của các chuyển vị) tạo thành một nhóm được gọi là nhóm các hình đối xứng F. Bạn đã biết về điều này từ bài báo của A. Kolmogorov (xem trang 4), và chúng tôi đã đưa ra ví dụ này về một nhóm. Bây giờ chúng ta sẽ nghiên cứu các nhóm đối xứng của một số hình.

Hãy bắt đầu với hình tròn, mà từ xa xưa đối với con người dường như là hiện thân của sự hoàn hảo và là một ví dụ về sự đối xứng. Với bất kỳ góc quay nào so với tâm và với sự phản chiếu của gương so với đường kính tùy ý, vòng tròn sẽ tự căn chỉnh. Do đó, nhóm đối xứng đường tròn bao gồm tất cả các phép quay $R_0^\alpha$ quanh tâm $O$ của đường tròn và tất cả các phép đối xứng trục $S_l$ với trục $l$ đi qua điểm $O$.

Nhóm đối xứng của hình elip nhỏ hơn nhiều - nó bao gồm hai đối xứng trục tương ứng với đường kính liên hợp vuông góc lẫn nhau của hình elip (hình elip được mô tả trong «Kvant», 1975, số 1), phép quay $R_0^{180^\circ}$ (đối xứng tâm) xung quanh hình elip và tất nhiên, cũng là một ánh xạ hiệu quả $E$. Tương tự sẽ là nhóm đối xứng của hình thoi.

Nhưng hình vuông có nhóm đối xứng lớn hơn, bây giờ chúng ta sẽ tách chúng ra.

Hãy vẽ một hình vuông trên mặt phẳng và đánh dấu các đỉnh của nó bằng các số 1, 2, 3, 4. Để hình vuông tự thẳng hàng, mỗi đỉnh của nó đều kết thúc ở vị trí của một đỉnh nhất định. Vì vậy, ví dụ khi xoay $R_0^{90^\circ}$ ($O$ là tâm của hình vuông), các đỉnh 1, 2, 3, 4 sẽ lần lượt biến thành các đỉnh 2, 3, 4, 1 (Hình 4): $R_0^{90^\circ}(1) = 2$, $R_0^{90^\circ}(2) = 3$, $R_0^{90^\circ}(3) = 4$, $R_0^{90^\circ}(4) = 1$. Thực tế này có thể được viết khác nhau:

$$1 \rightarrow 2, 2 \rightarrow 3, 3 \rightarrow 4, 4 \rightarrow 1.$$

Tương tự, lần lượt $R_0^{180^\circ}$ khớp với mục nhập

$$1 \rightarrow 3, 2 \rightarrow 4, 3 \rightarrow 1, 4 \rightarrow 2.$$

Những gì đã nói cũng có thể được viết dưới dạng veena, ý nghĩa của nó đã rõ ràng so với dạng trước:

$$R_0^{90^\circ} = \begin{pmatrix} 1 & 2 & 3 & 4 \\ 2 & 3 & 4 & 1 \end{pmatrix}, R_0^{180^\circ} = \begin{pmatrix} 1 & 2 & 3 & 4 \\ 3 & 4 & 1 & 2 \end{pmatrix}.$$

Chúng ta đã thu được cái mà các nhà toán học gọi là sự thay thế: ánh xạ nghịch đảo của tập hữu hạn $M$ lên chính nó (ở đây là tập hợp bốn điểm - các đỉnh của một hình vuông). Sau khi bao bọc các phần tử của tập hữu hạn này bằng các số 1, 2, ..., $n$, chúng ta sẽ cộng từng phần tử thay thế dưới dạng bảng

$$\begin{pmatrix} 1 & 2 & 3 & 4 & ... & n \\ a_1 & a_2 & a_3 & a_4 & ... & a_n \end{pmatrix},$$

dòng dưới cùng chứa các số giống như dòng trên cùng nhưng theo thứ tự khác. Do đó, sự thay thế bao gồm thực tế là mỗi phần tử $a_k$ từ $M$ được liên kết với một phần tử duy nhất $b_k$ từ cùng một bộ và các phần tử khác nhau $a_k$ tương ứng với $b_k$ khác nhau.

⟦folio 12⟧

Với quan điểm này, các mục khác nhau có thể được lấy cho cùng một sự thay thế, ví dụ:

$$\begin{pmatrix} 1 & 2 & 3 & 4 \\ 3 & 2 & 1 & 4 \end{pmatrix}, \begin{pmatrix} 2 & 3 & 1 & 4 \\ 2 & 1 & 3 & 4 \end{pmatrix}, \begin{pmatrix} 1 & 3 & 2 & 4 \\ 3 & 1 & 2 & 4 \end{pmatrix}.$$

Thông thường, các phần tử của hàng trên cùng được sắp xếp theo thứ tự tự nhiên và do đó, nói chung, việc thay thế các phần tử $n$ được viết dưới dạng

$$\begin{pmatrix} 1 & 2 & \dots & n \\ a_1 & a_2 & \dots & a_n \end{pmatrix}.$$

Đặt $\sigma$ và $\tau$ là hai hoán vị của tập hợp $M$. Tích $\tau \circ \sigma$ của phép thay thế $\sigma$ bằng $\tau$ là phép thay thế $\omega$ phát sinh do việc thực hiện tuần tự $\sigma$ đầu tiên và sau đó là $\tau$. Do đó, nếu $\sigma$ khớp với phần tử $a$ với $b$ và $\tau$ khớp với phần tử $b$ với $c$, thì tích $\tau \circ \sigma$ với phần tử $a$ khớp với $c$. Sản phẩm phụ thuộc vào thứ tự của các thành phần. Thật vậy, nếu $\tau$ ánh xạ phần tử $a$ tới phần tử $d$ và $\sigma$ ánh xạ $f$ tới phần tử $d$, thì tích $\sigma \circ \tau$ ánh xạ $a$ tới $f$.

Thay thế danh tính

$$e = \begin{pmatrix} 1 & 2 & \dots & n \\ 1 & 2 & \dots & n \end{pmatrix},$$

không thay đổi cách sắp xếp các phần tử, đóng vai trò đơn vị. Đối với mỗi hoán vị $\omega$ có một nghịch đảo duy nhất $\omega^{-1}$ sao cho $\omega \circ \omega^{-1} = \omega^{-1} \circ \omega = e$.

Bài tập 10. Chứng minh rằng định nghĩa trên, phép nhân các số thay thế, có tính kết hợp.

Nhiệm vụ 11. Chứng minh rằng sự thay thế $\omega^{-1}$ phát sinh từ sự thay thế đã cho nếu hàng trên cùng và dưới cùng của nó hoán đổi cho nhau.

Tập hợp các hoán vị của các phần tử $n$ tạo thành một nhóm (ánh xạ khả nghịch của một tập hữu hạn $M$ lên chính nó), nó được gọi là “nhóm đối xứng bậc $n$” và được ký hiệu là $S_n$.

Bài 12. Viết các phép thay thế tương ứng với các đối xứng trục của hình vuông (Hình 5) $S_{(24)}$, $S_{(13)}$, $S_l$, $S_m$ và phép quay $R_0^{270^\circ}$ (ở đây (24) là đường thẳng đi qua các điểm 2, 4, v.v.).

Bài 13. Chứng minh nhóm hoán vị của 4 phần tử gồm 24 phần tử.

Nhiệm vụ 14. Đảm bảo rằng không phải mỗi sự thay thế này đều có thể khớp với một hình vuông tự sắp xếp.

Chuỗi bài toán cho thấy có ít hơn 24 phần tử trong nhóm đối xứng hình vuông - mỗi phần tử tự sắp xếp của hình vuông tương ứng với một phép thay thế (4 đỉnh của hình vuông), nhưng không phải mọi sự thay thế đều tương ứng với việc tự sắp xếp của một hình vuông.

Đây là điểm khác giữa hình vuông và hình tam giác: nhóm đối xứng của tam giác bao gồm sáu phần tử và sự thay thế của 3 đỉnh của tam giác cũng là sáu, và nhóm đối xứng của một tam giác là đẳng cấu với nhóm thay thế của 3 phần tử.

Lưu ý rằng nhóm đối xứng của hình vuông (cũng như hình tam giác) là không giao hoán:

$$S_{(13)} \circ S_l = R_0^{-90^\circ} \neq R_0^{90^\circ} = S_l \circ S_{(13)}.$$

Nhiệm vụ 15. Tìm tất cả các mặt phẳng biến thiên ánh xạ hình vuông lên chính nó (sẽ có tổng số chúng trong mọi thứ).

Bài 16. Lập bảng gồm các mặt phẳng biến thiên ánh xạ hình vuông lên chính nó (tương tự như bảng nhân các số từ 1 đến 9).

Bài 17. Chứng minh số hoán vị khác nhau của tập hợp gồm các phần tử $n$ là $n!$ ($n! = 1 \cdot 2 \cdot 3 \cdot \dots \cdot n$).

Tóm lại, chúng tôi lưu ý rằng các tính chất và cấu trúc của các nhóm hiện thực hóa trừu tượng và cụ thể được nghiên cứu về mặt toán học bởi một môn học gọi là lý thuyết nhóm, môn học này chưa được ứng dụng rộng rãi trong nhiều ngành toán học, vật lý lý thuyết, hóa học, tinh thể học, lý thuyết truyền thông và các ngành khoa học khác.
