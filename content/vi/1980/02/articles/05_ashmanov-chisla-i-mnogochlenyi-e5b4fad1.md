---
id: 1980-2-ashmanov-chisla-i-mnogochlenyi-e5b4fad1
issue: kvant_1980_2
year: 1980
number: "2"
title: Số và đa thức
authors:
  - Ашманов С. А.
rubric: osnovnye-stati
page_first: 19
page_last: 23
page_labels: 17, 19, 20, 21
tag: KH6V
lang: vi
source: kvant_digital
extraction: vision
content_sha256: 724a7a9f9a77f75463e4b0754fd19170da74e64c36638f12f7a43cb61e9a9730
prompt_sha256: draft-1
translated_from: content/ru/1980/02/articles/05_ashmanov-chisla-i-mnogochlenyi-e5b4fad1.md
source_content_sha256: 52072e873ee40b6b3a95efc32d60aa9b0f3eb93d7174a814878e8019e7324a1a
translation_model: draft
translation_run: vi-draft-2026-10-31
translation_quality: draft
---

⟦folio 17⟧

S. Ashmanov

Số và đa thức

Trong bài viết này, chúng ta sẽ nói về mối liên hệ giữa số phức và đa thức trong toán học.

Khi số lượng là không đủ

Có những con số khác nhau: tích cực và tiêu cực, hợp lý và vô tỷ, đại số và siêu việt. Lịch sử xuất hiện của mỗi lớp số lò xo mới thật đáng trân trọng và thậm chí đầy kịch tính.

Đối với chúng ta, một đối tượng khắc sâu như số âm đã là chủ đề tranh luận trong suốt thế kỷ. Chúng đã được biết đến từ thời cổ đại ở Ấn Độ, Trung Quốc và Babylon, nhưng những tranh cãi về bản chất của số âm và quyền tồn tại của chúng đã được tiến hành từ thời Newton vào cuối thế kỷ 17.

Lý do đưa ra số âm rõ ràng là do khó khăn khi giải phương trình dạng $x+a=b$ cho bất kỳ số dương nào $a$ và $b$.

Việc giới thiệu số hữu tỷ sẽ nảy sinh để giải phương trình có dạng $ax=b$, trong đó $a$ và $b$ là số nguyên ($a \neq 0$).

Sau khi tính hợp lý của số $\sqrt{2}$ được chứng minh ở Hy Lạp cổ đại, tức là không thể giải được phương trình $x^2=2$, chỉ có số hữu tỷ theo ý mình, nhân loại một lần nữa phải đối mặt với nhu cầu mở rộng dự trữ số của mình.

Bạn có thể mở rộng tập hợp số hữu tỷ để phương trình $x^2=2$ trong một tập hợp mới, rộng hơn có nghiệm, không chỉ như cách làm trong sách giáo khoa mà còn như sau:

Hãy nhập ký hiệu $j$ và đặt $j^2=2$. Chúng ta sẽ xem xét các biểu thức có dạng $a+bj$, trong đó $a$ và $b$ là các số hữu tỷ tùy ý.

Hãy xây dựng các quy tắc hành động đối với các ứng cử viên của chúng ta cho những con số mới:

$$(a_1+b_1j) + (a_2+b_2j) = (a_1+a_2) + (b_1+b_2)j;$$

$$(a_1+b_1j) (a_2+b_2j) = (a_1a_2+2b_1b_2) + (a_1b_2+a_2b_1)j.$$

⟦folio 19⟧

Nếu bạn thêm tôi

Hãy thử, giống như chúng ta đã làm với trường số hữu tỷ và phương trình $x^2=2$, để mở rộng trường R của số thực bằng cách thêm vào đó “gốc” của phương trình $x^2+1=0$.

Đặt $i$ là một ký hiệu có đặc tính duy nhất là nó là nghiệm của phương trình $x^2+1=0$; nghĩa là, $i^2=-1$.

Hãy xem xét các biểu thức có dạng $a+bi$, trong đó $a$ và $b$ là các số thực tùy ý; Hãy gọi chúng là số phức. Hãy giới thiệu các quy tắc tính toán trên số phức:

$$\begin{align*}
(a_1+b_1i) + (a_2+b_2i) &= (a_1+a_2) + (b_1+b_2)i; \\
(a_1+b_1i) (a_2+b_2i) &= (a_1a_2-a_1b_2) + (b_1b_2+a_2b_1i).
\end{align*}$$

Người đọc có thể dễ dàng chứng minh rằng tập hợp các số phức với phép cộng và phép nhân được xác định là một trường.

Thật dễ dàng để xác minh rằng các số phức có dạng $a+0i$ hoạt động giống như số thực. Do đó, số thực $a$ và số phức $a+0i$ có ​​thể được xác định với nhau. Điều này có nghĩa là chúng ta có thể coi như chúng ta đã mở rộng trường số thực sang trường số phức. Trong trường phương trình rộng hơn này, $x^2+1=0$ có gốc: $i^2+1=0$ (và thậm chí có hai gốc: $(-i)^2+1=0)$.

Nhưng chúng tôi đã thêm những gì? Chỉ vì phương trình $x^2+1=0$ đã bén rễ? Hóa ra chúng tôi đã thêm nhiều thành phố hơn. Có một sự thay thế

Định lý cơ bản của đại số

Bất kỳ đa thức $P(x) = a_nx^n + a_{n-1}x^{n-1} + \dots + a_2x^2 + a_1x + a_0$ nào có bậc khác 0 đều có ít nhất một nghiệm trong các phức số đa số (tất nhiên, số này cũng có thể là số thực).

Nỗ lực đầu tiên để chứng minh định lý này được thực hiện bởi d'Alembert vào năm 1746. Một bằng chứng chặt chẽ được Gauss đưa ra vào năm 1799.

Hóa ra định lý cơ bản của đại số không chỉ đúng với đa thức

phép cộng: 1. giao hoán, 2. kết hợp, 3. có số 0, 4. với mỗi phần tử của M có một phần tử đối diện;

phép nhân: 5. giao hoán, 6. kết hợp, 7. có một, 8. với mọi phần tử khác 0 của M đều có một nghịch đảo, 9. phân phối đối với phép cộng.

với các hệ số thực, mà còn cho các đa thức có hệ số phức (hoặc, như người ta thường nói, đối với các đa thức trên một trường số phức).

Định lý cơ bản của Đại số cho phép chúng ta đưa ra một đáp số một cách tao nhã cho câu hỏi một đa thức bậc $n$ tùy ý có bao nhiêu nghiệm, nếu chúng ta xem xét các đa thức trên trường phức số.

Để hình thành đáp số này, chúng ta cần khái niệm “bội số” (căn gốc của một đa thức) và khái niệm này được xác định thông qua khái niệm “một đa thức chia hết cho một đa thức khác”. Một đa thức $P_1(x)$ được gọi là chia hết cho đa thức $P_2(x)$ nếu có một đa thức $q(x)$ sao cho $P_1(x) = q(x) \cdot P_2(x)$.

Khái niệm “chia” và “căn” Định lý 1. Số a là một ngón chân và chỉ một ngón chân là nghiệm của đa thức $P(x)$, dây $P(x)$ chia hết cho $x$-a.

Định lý 1 không khó để bạn tự chứng minh. (Tại cái vạc và e. Chia bằng một “góc”.).

Có thể đa thức $P(x)$ bậc $n$ sẽ không chỉ chia hết cho $x$-a mà còn chia hết cho một mức nào đó $x$-a. Theo những điều kiện này, a được gọi là căn bậc $k$ của đa thức $P(x)$ nếu $P(x)$ chia hết cho $(x-a)^k$ nhưng không chia hết cho $(x-a)^{k+1}$. (Ví dụ: số 1 là căn bậc hai của đa thức

$$P(x) = x^3 + x^2 - 5x + 3 = (x-1)^2(x+3).$$

Teler có thể dễ dàng được chứng minh

Định lý 2. Mọi đa thức $P(x)$ bậc $n$ (với hệ số thực hoặc hệ số phức) có trong trường phức của nó có chính xác $n$ nghiệm (trong đó tất nhiên có thể có số thực), nếu mỗi nghiệm chỉ được tính một lần thì bội số của nó là bao nhiêu.

Bằng chứng. Theo định lý cơ bản của đại số, đa thức $P(x)$ có các phức có chính xác là $n$ nghiệm trong trường. Giả sử rằng $a_1$ là nghiệm của đa thức $P(x)$. Theo Định lý 1 $P(x) = (x-a_1)q(x)$, trong đó $q(x)$ là đa thức bậc $n-1$. (Hơn nữa, các hệ số của đa thức $P(x)$ là số thực; đa thức $q(x)$ sẽ là nếu $a_1$ là một nghiệm phức và có hệ số phức.)

Chúng ta hãy áp dụng thêm cách suy luận tương tự cho đa thức $q(x)$. Theo định lý cơ bản của đại số, có nghiệm $a_2$ của đa thức $q(x)$, sao cho $q(x) = (x-a_2)h(x)$, trong đó $h(x)$ là đa thức có bậc đã là $n-2$. Lặp lại lý do này $n-1$ lần (tất nhiên là áp dụng khi

⟦folio 20⟧

trình bày chặt chẽ các nguyên lý quy nạp toán học), cuối cùng chúng ta sẽ đi đến phân tích

$$P(x) = a_n (x - a_1) (x - a_2) \dots (x - a_n),$$

trong đó $a_n$ là hệ số bậc cao nhất $x^n$ của đa thức $P(x)$.

Từ danh tính (*), không chỉ suy ra rằng các số phức $a_1, a_2, \dots, a_n$ (trung bình của chúng có thể bằng nhau!) là nghiệm của đa thức $P(x)$, mà còn cho thấy đa thức này không có nghiệm nào khác. Thật vậy, nếu số $\beta$ là đa thức của đa thức $P(x)$, thì

$$P(\beta) = a_n (\beta - a_1) (\beta - a_2) \dots (\beta - a_n).$$

Nhưng tích của các số phức bằng 0 khi và chỉ khi một trong các thành phần bằng 0 (đây là bằng chứng). Do đó, một trong các thành phần bằng 0, tức là $\beta = a_i$. Điều này hoàn thành việc chứng minh Định lý 2.

Khi khoa học phát triển, rõ ràng là không thể thực hiện được nếu không có số phức trong những vấn đề “thực tế” nhất. Khi máy bay xuất hiện, cần phải có lý thuyết về luồng không khí xung quanh cánh máy bay. Hóa ra ngôn ngữ tự nhiên nhất để mô tả một quá trình như vậy, tức là ngôn ngữ khí động học, là lý thuyết về hàm số phức! Vì vậy, khi bạn nhìn thấy một chiếc máy bay hiện đại, hãy biết rằng nó được tạo ra bởi rất nhiều nhà thiết kế, kỹ sư, công nhân và... số phức. Điều tương tự cũng có thể nói về khoa học về nước chảy quanh con tàu - thủy động lực học. Bạn có biết một món đồ chơi khác - Vanka-insert không? Bạn đưa Vanka vào giấc ngủ, anh ấy lập tức bật dậy - anh ấy có tư thế ổn định nhất khi đứng. Lý thuyết toán học về tính ổn định giải quyết các câu hỏi tương tự cho các thành phố có hệ thống cơ, điện và các hệ thống khác phức tạp hơn. Và một lần nữa, hóa ra đáp số về việc hệ thống có ổn định hay không nằm ở tính chất của số phức, vốn là gốc của một đa thức nhất định đặc trưng cho hệ thống đang được xem xét.

Máy bay hiện đại và Vanka-insert - đây là phạm vi hoạt động của số phức. Chúng tôi chỉ đưa ra một số lĩnh vực ứng dụng của họ, vì tất cả những điều trên đều không thể thực hiện được. Dưới đây là những con số tối thiểu dành cho bạn!

Bây giờ chúng ta sẽ chỉ ra, bằng ví dụ, số phức đã giúp trả lời một số câu hỏi quan trọng về đa thức với hệ số thực như thế nào.

Đa thức tương tự như số nguyên tố

Xét tập hợp tất cả các đa thức có bậc tùy ý trong biến $x$. Bạn có khả năng cộng các phần tử biến của đa thức này, tức là các đa thức và bạn biết cách phân tách chúng thành các đa thức.

Điều này rất giống với những gì bạn có thể làm với số tự nhiên. Bạn cũng có thể phân tích các số tự nhiên thành đa thức đơn giản. Bạn có thể biết rằng điều này luôn có thể được thực hiện và hơn nữa, theo cách duy nhất.

Vai trò của số nguyên tố trong lý thuyết đa thức được thực hiện bởi cái gọi là đa thức tối giản. Một đa thức $P(x)$ bậc $n > 0$ được gọi là tối giản nếu nó không chia hết cho bất kỳ đa thức bậc $0 < s < n$ nào.

Một sự tương tự của phát biểu về việc phân tích một số tự nhiên bất kỳ thành tích của các đa thức đơn giản nghe như sau:

Định lý 3. Mọi đa thức có bậc khác 0 đều phân tích thành tích các đa thức tối giản:

$$P(x) = P_1(x)P_2(x) \dots P_m(x),$$

và khai triển này là sự thống nhất của bậc do và đa thức bậc 0*).

Chứng minh Định lý 2, chúng ta thu được rằng mọi đa thức $P(x)$ bậc $n$ đều có thể phân tích trên trường số phức thành tích tuyến tính (tức là bậc một) khả quy (*)).

Như vậy, trên trường số phức cấp khác 0 và cấp khác 0.

Những đa thức nào khác 0 trên trường số thực? Dù ở quốc gia nào, số phức cũng sẽ giúp chúng ta trả lời câu hỏi này.

Cho $z = a + bi$ là một số phức tùy ý. Trên bề mặt phức tạp, số $z = a - bi$ liên hợp với số $z$.

Chúng ta cần Định lý 4. Nếu $z$ là nghiệm của đa thức $P(x)$ với các hệ số thực thì $u$ $z$ là nghiệm của nó.

Để chứng minh điều này, ta lưu ý các tính chất sau của phép lấy số liên hợp $z$:

1. Liên hợp của số $z$ với liên hợp của số $z$ giống với số phức ban đầu $z$.
2. Số $z$ bằng độ lệch của số $z$ khi và chỉ khi $z$ là số thực.
3. Liên hợp của tổng các số phức liên hợp với các số hạng:

$$z_1 + z_2 = z_1 + z_2.$$

4. Số liên hợp của một tích bằng tích của các số liên hợp với số phức:

$$z_1 \cdot z_2 = z_1 \cdot z_2.$$

*) Để chứng minh Định lý 3, xem ví dụ «Kvant», 1976, số 8, tr. 15.

⟦folio 21⟧

Sử dụng phương pháp quy nạp toán học, có thể chỉ ra rằng Quy tắc 3 và 4 áp dụng cho tổng và tích của nhiều hơn hai số:

$$\frac{z_1 + z_2 + \ldots + z_m}{z_1 \cdot z_2 \cdot \ldots \cdot z_m} = \frac{z_1 + z_2 + \ldots + z_m}{z_1 \cdot z_2 \cdot \ldots \cdot z_m}$$

cụ thể là $\bar{z}^m = (\bar{z})^m$.

5. Tích của đa thức $x - z$ và $x - \bar{z}$ là đa thức có hệ số thực:

$$(x - z)(x - \bar{z}) = x^2 - 2ax + (a^2 + b^2).$$

Chứng minh định lý 4. Giả sử

$$P(x) = a_n x^n + a_n \frac{1}{x^{n-1}} + \ldots + a_2 x^2 + a_1 x + a_0,$$

trong đó $a_n, a_{n-1}, \ldots, a_2, a_1, a_0$ là số thực, $z$ là nghiệm của đa thức này. Sau đó

$$0 = P(z) = a_n z^n + a_{n-1} z^{n-1} + \ldots + a_2 z^2 + a_1 z + a_0.$$

Hãy sử dụng thuộc tính của thao tác ghép nối:

$$0 = \bar{P}(z) = \frac{a_n z^n + a_{n-1} z^{n-1} + \ldots + a_2 z^2 + a_1 z + a_0}{a_n z^n + a_{n-1} z^{n-1} + \ldots + a_2 z^2 + a_1 z + a_0} = P(\bar{z}).$$

Định lý 4 đã được chứng minh.

Từ Định lý 4 dễ dàng suy ra

Định lý 5. Một đa thức có hệ số thực có số nghiệm chẵn.

Trên thực tế, theo Định lý 4, các nghiệm không thực của đa thức có hệ số thực “đi theo cặp”: $(z; \bar{z})$.

Nó ngay lập tức suy ra từ Định lý 5

Định lý 6. Một đa thức bậc lẻ có hệ số thực có ít nhất một nghiệm thực.

Theo định lý cơ bản của đại số, đa thức này có số nghiệm lẻ (bằng bậc của nó), do đó, theo Định lý 5, chúng không thể đều là nghiệm không thực.

Với sự trợ giúp của số phức, chúng ta đã chứng minh được một định lý hoàn toàn “thực”. Nhưng điều quan trọng và thú vị hơn nhiều là sự thật sau đây:

Định lý 7. Bất kỳ đa thức nào có hệ số thực có bậc lớn hơn 2 đều có thể rút gọn về trường số thực.

Bằng chứng. Nếu đa thức $P(x)$ có nghiệm thực $a$ thì $P(x) = q(x) \cdot (x - a)$. Từ chứng minh Định lý 1 mà bạn đã đưa ra, rõ ràng $q(x)$ là một đa thức có hệ số thực. Do đó, trong trường hợp này, $P(x)$ là một rút gọn của hai đa thức có hệ số thực, tức là $P(x)$ có thể rút gọn về trường số thực.

Giả sử bây giờ tất cả các nghiệm $z_1, z_2, \ldots, z_m$ của đa thức $P(x)$ không có thực. Theo Định lý 6 $n$ là số chẵn và

$$P(x) = a_n (x - z_1) (x - z_2) \ldots (x - z_n).$$

Chia các gốc $z_1, \ldots, z_n$ thành các cặp liên hợp có dạng $(z_i; \bar{z}_i)$ và viết $P(x)$ như thế này:

$$P(x) = a_n (x - z_1) (x - \bar{z}_1) (x - z_2) (x - \bar{z}_2) \times \ldots \times (x - z_k) (x - \bar{z}_k);$$

đây $k = \frac{n}{2}$.

Mỗi đa thức $P_i(x) = (x - z_i) \times (x - \bar{z}_i)$, $i = 1, 2, \ldots, k$, như chúng ta đã thấy, có các hệ số thực. Do đó, đa thức $P(x) = a_n P_1(x) P_2(x) \ldots P_k(x)$ có ​​thể rút gọn về trường số thực - xét cho cùng, đây là tích của ít nhất hai thừa số (từ $n > 2$ nó dẫn đến $k > 1$).

Do đó, kết luận cuối cùng về tính không dẫn điện của đa thức trên trường số thực như sau:

Định lý 8. Chỉ các đa thức bậc một và đa thức bậc hai có phân biệt âm là khả quy trên trường số thực.

Kết quả. Bất kỳ đa thức nào có hệ số thực đều có thể phân tích thành tích của đa thức bậc một và bậc hai có hệ số thực.

Chúng ta vẫn chưa nói về điều gì? Về vai trò của đa thức trong lời giải các làng bài toán quan trọng - bài toán về phép chia ba một góc, bình phương của một hình tròn và nhân đôi của một hình lập phương. Về cách chàng trai trẻ Niels Abel chứng minh rằng không có công thức nào để tìm nghiệm của đa thức bậc trên 4; Evariste Galya thậm chí còn trẻ hơn đã giải quyết hoàn toàn bài toán phương trình lời giải theo căn thức như thế nào. Cuối cùng, chúng ta vẫn chưa chứng minh được định lý cơ bản của đại số...

Không, tác giả phải thừa nhận rằng mình đã đảm nhận một nhiệm vụ bất khả thi bài toán; Anh kiệt sức đặt bút xuống và yêu cầu người đọc đừng quá khắt khe.
