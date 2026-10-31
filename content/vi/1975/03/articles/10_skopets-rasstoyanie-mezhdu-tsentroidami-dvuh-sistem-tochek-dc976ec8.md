---
id: 1975-3-skopets-rasstoyanie-mezhdu-tsentroidami-dvuh-sistem-tochek-dc976ec8
issue: kvant_1975_3
year: 1975
number: "3"
title: Khoảng cách giữa trọng tâm của hai hệ thống điểm
authors:
  - Скопец З. А.
rubric: matematicheskiy-kruzhok
rubric_sub: Математический кружок
page_first: 41
page_last: 45
page_labels: 39-43
tag: ZS78
lang: vi
source: kvant_digital
extraction: vision
content_sha256: 4ed6b8678801a1cf27ca5dddf6cdde7d8004143f1f159f8f3d1113c39129129c
prompt_sha256: draft-1
translated_from: content/ru/1975/03/articles/10_skopets-rasstoyanie-mezhdu-tsentroidami-dvuh-sistem-tochek-dc976ec8.md
source_content_sha256: e95a21eada2aa3f4e1c542a20561745c1d6840aa27f8fffbc9a5bb1398ad1d83
translation_model: draft
translation_run: vi-draft-2026-10-31
translation_quality: draft
---

⟦folio none⟧
⟦rubric⟧ VÒNG TRÒN TOÁN HỌC

## Khoảng cách giữa trọng tâm của hai hệ thống điểm
Z. A. Skopets

Xét một hệ gồm $n$ điểm $A_1, A_2, \ldots, A_n$, nằm tùy ý trong không gian. Cho phép các điểm riêng lẻ (hoặc thậm chí tất cả) của hệ thống này trùng khớp. Thứ tự của các điểm không quan trọng.

*Trọng tâm của hệ điểm $A_1, \ldots, A_n$ là điểm $O$ mà đẳng thức vectơ giữ nguyên*

$$\overrightarrow{OA}_1 + \overrightarrow{OA}_2 + \ldots + \overrightarrow{OA}_n = \sum_{i=1}^{n} \overrightarrow{OA}_i = \vec{0}. \quad (1)$$

Sự *tồn tại* của trọng tâm không trực tiếp tuân theo định nghĩa này. Do đó, chúng ta sẽ chứng minh rằng mọi hệ điểm đều có một trọng tâm và hơn nữa là một trọng tâm duy nhất.

Chúng ta hãy chọn một hệ điểm $A_1, A_2, \ldots, A_n$ trong không gian, xác định tùy ý một điểm $M$ mà chúng ta lấy làm điểm bắt đầu của vectơ và một điểm khác $O$ (Hình 1). Sau đó bạn có thể viết

$$\overrightarrow{OA}_1 = \overrightarrow{MA}_1 - \overrightarrow{MO},$$
$$\overrightarrow{OA}_2 = \overrightarrow{MA}_2 - \overrightarrow{MO},$$
$$\ldots \ldots \ldots \ldots$$
$$\overrightarrow{OA}_n = \overrightarrow{MA}_n - \overrightarrow{MO}.$$

Giả sử điểm $O$ là tâm của hệ điểm này. Tổng hợp các đẳng thức này theo từng số hạng, chúng ta thu được, có tính đến (1)

$$\vec{0} = \overrightarrow{MA}_1 + \overrightarrow{MA}_2 + \ldots + \overrightarrow{MA}_n - n \cdot \overrightarrow{MO}.$$

⟦column⟧

Từ đây chúng ta tìm thấy

$$\overrightarrow{MO} = \frac{1}{n}(\overrightarrow{MA}_1 + \overrightarrow{MA}_2 + \ldots + \overrightarrow{MA}_n) = \frac{1}{n}\sum_{i=1}^{n} \overrightarrow{MA}_i. \quad (2)$$

Thực hiện các phép tính theo thứ tự ngược lại, chúng ta có thể dễ dàng xác minh rằng điểm $O$, được xác định bởi đẳng thức (2), thỏa mãn hệ thức (1), tức là nó là tâm. Do đó, sự *tồn tại* của trọng tâm đã được chứng minh. Nó vẫn còn để chứng minh *tính duy nhất*. Thật vậy, chúng ta hãy lấy điểm $O'$, khác với $O$. Sau đó

$$\overrightarrow{O'A}_1 = \overrightarrow{O'O} + \overrightarrow{OA}_1, \ldots, \overrightarrow{O'A}_n = \overrightarrow{O'O} + \overrightarrow{OA}_n.$$

Cộng các đẳng thức này và tính đến (1), chúng ta thu được

$$\overrightarrow{O'A}_1 + \ldots + \overrightarrow{O'A}_n = n \cdot \overrightarrow{OO'};$$

vì điểm $O'$ khác với $O$, nên $\overrightarrow{O'O} \neq \vec{0}$ và $n \cdot \overrightarrow{O'O} \neq \vec{0}$, nghĩa là

$$\overrightarrow{O'A}_1 + \ldots + \overrightarrow{O'A}_n \neq \vec{0}.$$

Như vậy, không có điểm $O'$ nào ngoài $O$ là tâm của hệ điểm $A_1, \ldots, A_n$. Điều này hoàn thành việc chứng minh sự tồn tại và duy nhất trọng tâm của hệ $n$ điểm. Ngoài ra, phương pháp xây dựng trọng tâm cũng được chỉ ra (xem (2)).

Bây giờ chúng ta chứng minh khẳng định sau.

Định lý 1. *Cho $O_1$ là trọng tâm của hệ điểm $A_1, \ldots, A_m$ và $O_2$ là trọng tâm của hệ điểm*

⟦folio 39⟧

⟦folio 40⟧

Trong $B_1, \dots, B_n$. Khi đó tâm $O$ của hệ gồm tất cả $m + n$ điểm $A_1, \dots, A_m, B_1, \dots, B_n$ nằm trên đoạn $O_1O_2$ và ta thỏa mãn điều kiện $|O_1O| : |OO_2| = n : m$.

Bằng chứng. Đối với một điểm $O$ nằm trên đoạn $O_1O_2$ và thỏa mãn điều kiện $|O_1O| : |OO_2| = n : m$, ta có $\vec{mOO}_1 + n\vec{OO}_2 = \vec{0}$. (3)

Chúng ta hãy đảm bảo rằng điểm $O$ là tâm của hệ thống tất cả $m + n$ điểm. Thật ra, vì $O_1$ là tâm của hệ điểm $A_1, \dots, A_m$ nên theo (2) ta có

$$\vec{OA}_1 + \vec{OA}_2 + \dots + \vec{OA}_m - m \cdot \vec{OO}_1 = \vec{0}. \quad (4)$$

Tương tự, từ $O_2$ là tâm của hệ điểm $B_1, \dots, B_n$, ta thu được

$$\vec{OB}_1 + \vec{OB}_2 + \dots + \vec{OB}_m - n \cdot \vec{OO}_2 = \vec{0}. \quad (5)$$

Cộng các tương ứng (3), (4), (5) theo từng số hạng, ta thu được

$$\vec{OA}_1 + \dots + \vec{OA}_m + \vec{OB}_1 + \dots + \vec{OB}_n = \vec{0},$$

và điều này có nghĩa là $O$ là tâm của hệ điểm $A_1, \dots, A_m, B_1, B_2, \dots, B_n$.

Kết quả. Let $A_1, \dots, A_m$ be some systems of the point $k$ be a natural number less than $m$. Chúng ta hãy chọn một số $k$ điểm từ $A_1, \dots, A_m$ và đặt $O'$ là tâm của chúng và $O''$ là tâm của các điểm $m - k$ còn lại. Sau đó, tất cả các đoạn $O'O''$) thu được theo cách này đều đi qua một điểm $O$ (tâm của hệ điểm $A_1, \dots, A_m$) và được chia tại điểm này theo tỷ lệ $(m - k) : k$.

From the proven theorem and this corollary, a number of conclusions can be drawn. Trước hết, từ Định lý 1 cho $m = n = 1$, ta thấy tâm của hai điểm $A, B$ trùng với trung điểm của đoạn nối chúng. Hơn nữa, đối với $m = 2, n = 1$, chúng ta thu được từ Định lý 1 rằng tâm $O$ của ba điểm $A_1, A_2, B$ nằm trên đoạn nối $D$ của đoạn $A_1A_2$ với điểm $B$ và $|DO| : |OB| = 1 : 2$. Cụ thể, theo sau, nếu các điểm $A_1, A_2, B$ không nằm trên cùng một đường thẳng thì tâm của hệ điểm này trùng với giao điểm của các đường trung tuyến của tam giác $A_1A_2B$ (xem Hình 2; điểm này được gọi là trọng tâm của tam giác).

Đối với trường hợp có bốn điểm, chúng ta thu được (với $m = 3, n = 1$) như sau. Giả sử rằng không có ba trong số bốn điểm $A, B, C, D$ nằm trên cùng một đường thẳng và nối bất kỳ điểm nào trong số này với trọng tâm của một tam giác có các đỉnh tại ba điểm còn lại; có lẽ bốn điểm này

⟦folio 41⟧

Các đoạn thẳng cắt nhau tại một điểm O và chia tại đó theo tỷ lệ 3:1.
Ba đoạn thẳng nữa đi qua cùng một điểm O, điều này thu được nếu trung điểm của các đoạn có điểm cuối ở hai điểm được nối với điểm giữa của các đoạn có điểm cuối ở hai điểm khác.

Lưu ý rằng những phát biểu này đúng với bốn điểm không chỉ trên mặt phẳng mà còn đúng trong không gian. Cụ thể, từ chúng, suy ra rằng hai đường trung bình của tứ giác và đoạn nối trung điểm của các đường chéo cắt nhau tại một điểm O, điểm này đóng vai trò là trung điểm chung của cả ba đoạn thẳng.
Và đối với các điểm trong không gian, chúng ta có thể đưa ra công thức sau: các đoạn nối các đỉnh của tứ diện với trọng tâm của các mặt đối diện cắt nhau tại một điểm O (gọi là trọng tâm của tứ diện) và được chia trong đó theo tỷ lệ 3:1, tính từ đỉnh; Ba đoạn thẳng đi qua cùng một điểm O, nối trung điểm của các cạnh đối diện và O đóng vai trò là trung điểm chung của ba đoạn thẳng này.

Chúng ta cũng hãy lưu ý trường hợp năm điểm.

Gọi A, B, C, D, E là chân các điểm sao cho không có 4 điểm nào cùng thuộc một mặt phẳng.
Bằng cách nối mỗi điểm với trọng tâm của khối tứ diện có các đỉnh ở bốn điểm còn lại, chúng ta thu được các đỉnh của các đoạn cắt nhau tại một điểm O; Mười đoạn nữa sẽ đi qua cùng một điểm, mỗi đoạn nối đoạn giữa với các đầu tại hai điểm với trọng tâm của một tam giác có các đỉnh tại ba điểm còn lại.

Công thức Lagrange

Gọi O là trọng tâm của hệ các điểm A₁, ..., Aₘ và M là một điểm tùy ý. Khi đó, như chúng ta đã thấy ở trên, quan hệ (2) là hợp lệ. Quảng trường Beria *), chúng tôi nhận được

$$|\vec{M}O|^2 = \frac{1}{m^2} (\vec{M}A_1 + \dots + \vec{M}A_m)^2 = \frac{1}{m^2} \left[ |\vec{M}A_1|^2 + \dots + |\vec{M}A_m|^2 + 2 \sum_{i < j} \vec{M}A_i \cdot \vec{M}A_j \right].$$

Nhưng

$$2 \vec{M}A_i \cdot \vec{M}A_j = |\vec{M}A_i|^2 + |\vec{M}A_j|^2 - (\vec{M}A_j - \vec{M}A_i)^2 = |\vec{M}A_i|^2 + |\vec{M}A_j|^2 - |\vec{A}_i \vec{A}_j|^2.$$

Cộng các quan hệ này cho tất cả các cặp i, j, với i < j, ta thu được

$$2 \sum_{i < j} \vec{M}A_i \cdot \vec{M}A_j = (m - 1) \left( |\vec{M}A_1|^2 + \dots + |\vec{M}A_m|^2 \right) - \sum_{i < j} |\vec{A}_i \vec{A}_j|^2.$$

Thay (6') vào quan hệ (6), ta tìm được (sau khi đơn giản hóa):

$$|\vec{M}O|^2 = \frac{1}{m} \left( |\vec{M}A_1|^2 + \dots + |\vec{M}A_m|^2 \right) - \frac{1}{m^2} \sum_{i < j} |\vec{A}_i \vec{A}_j|^2.$$

Mối quan hệ (7) là công thức Lagrange nổi tiếng, biểu thị bình phương khoảng cách từ điểm M đến trọng tâm O của hệ các điểm A₁, ..., Aₘ thông qua bình phương khoảng cách từ điểm M đến điểm Aᵢ và bình phương khoảng cách |Aᵢ Aᵢ|.

Khoảng cách trung tâm

Cuối cùng, gọi hệ điểm đã cho là A₁, ..., Aₘ và B₁, ..., Bₙ. Hãy tính khoảng cách d giữa trọng tâm O₁ và O₂ của các hệ thống này, giả sử rằng tất cả khoảng cách lẫn nhau giữa các điểm của hệ thống thứ nhất, tất cả khoảng cách lẫn nhau giữa trọng tâm Aᵢ và Aᵢ đều đã biết.

*) Tích vô hướng của vectơ a và vectơ b được ký hiệu là a · b; bằng |a| · |b| · cos α, trong đó |a| là độ dài của vectơ và α là góc giữa vectơ a và b; do đó bình phương vô hướng là a, a = |a|² = |a|².

⟦folio 42⟧

Giữa các điểm của hệ thứ hai và khoảng cách tương hỗ của từng điểm của hệ thống này với từng điểm của hệ thống kia.
Hãy giới thiệu ký hiệu sau:
$$|A_i A_j| = a_{ij}, |B_s B_t| = b_{st},$$
$$|A_p B_q| = c_{pq}.$$
Như đã tìm thấy ở trên (xem (7)),
$$d^2 = |O_1 O_2|^2 = \frac{1}{n} |O_1 B_1|^2 + \dots$$
$$\dots + |O_1 B_n|^2) - \frac{1}{n^2} \sum_{s < t} b_{st}^2,$$
$$|O_1 B_h|^2 = \frac{1}{m} (|A_1 B_h|^2 + \dots$$
$$\dots + |A_m B_h|^2) - \frac{1}{m^2} \sum_{i < j} a_{ij}^2,$$
(trong đó $k$ là bất kỳ số nào trong số 1, 2, ..., $n$). Thay thế các tương ứng (8') vào công thức (8), cuối cùng chúng ta thu được (sau khi đơn giản hóa hơn nữa):
$$d^2 = |O_1 O_2|^2 = \frac{1}{mn} \sum_{p, q} c_{pq}^2 -$$
$$- \frac{1}{m^2} \sum_{i < j} a_{ij}^2 - \frac{1}{n^2} \sum_{s < t} b_{st}^2.$$

Sử dụng công thức này, trong trường hợp tổng quát nhất, khoảng cách giữa trọng tâm của hai hệ điểm được tính toán.

Ví dụ

1. Cho tam giác $A_1 B_1 B_2$. Trọng tâm $O_1$ của hệ thống gồm một điểm $A_1$ trùng với $A_1$, trọng tâm $O_2$ của hệ thống các điểm $B_1, B_2$ trùng với điểm giữa $[B_1 B_2]$ (Hình 3).

Trong trường hợp này, $[O_1 O_2]$ là đường trung bình của tam giác $A_1 B_1 B_2$. chúng tôi có
$$d^2 = \frac{1}{2} (|A_1 B_1|^2 + |A_1 B_2|^2) -$$
$$- \frac{1}{4} |B_1 B_2|^2.$$

2. Cho tứ giác $A_1 A_2 B_1 B_2$. Trọng tâm $O_1$ của hệ thống điểm $A_1, A_2$ trùng với giữa đoạn $A_1 A_2$, trọng tâm $O_2$ của hệ thống điểm $B_1, B_2$ trùng với giữa đoạn $B_1 B_2$ (Hình 4).

Hãy sử dụng công thức (9):
$$d^2 = \frac{1}{4} (|A_1 B_1|^2 + |A_1 B_2|^2 +$$
$$+ |A_2 B_1|^2 + |A_2 B_2|^2 - |A_1 A_2|^2 -$$
$$- |B_1 B_2|^2).$$ (10)

Công thức này, biểu thị bình phương khoảng cách giữa các trung điểm của các cạnh đối diện của một tứ giác thông qua bình phương các cạnh và đường chéo của nó, được gọi là công thức Euler. Ở đây hình tứ giác là tùy ý: nó có thể lồi, tự cắt hoặc không phẳng.

Nếu trọng tâm của các đoạn $A_1 A_2$ và $B_1 B_2$ trùng nhau thì tứ giác là hình bình hành và chúng ta thu được mối quan hệ đã biết giữa các cạnh và đường chéo của hình bình hành. Lưu ý rằng (vì $d^2 \geq 0$) theo công thức (10) $|A_1 B_1|^2 + |A_1 B_2|^2 + |A_2 B_1|^2 + |A_2 B_2|^2 \geq |A_1 A_2|^2 + |B_1 B_2|^2$, tức là tổng bình phương của tất cả các cạnh

⟦folio 43⟧

Một tứ giác luôn không nhỏ hơn tổng bình phương các đường chéo của nó. Sự bất hòa chỉ xảy ra với $d = 0$, nghĩa là khi và chỉ khi $A_1A_2B_1B_2$ là hình bình hành.

3. Hãy tìm khoảng cách từ điểm $A_1$ đến tâm của hệ điểm $B_1, B_2, B_3$ (Hình 5). Trong trường hợp này chúng ta có (theo công thức (7))

$$d^2 = \frac{1}{3} \left( |A_1B_1|^2 + |A_1B_2|^2 + |A_1B_3|^2 \right) - \frac{1}{9} \left( |B_1B_2|^2 + |B_2B_3|^2 + |B_1B_3|^2 \right).$$

Đây là sự tương ứng biểu thị khoảng cách từ đỉnh $A_1$ của khối tứ diện $A_1B_1B_2B_3$ đến tâm. Các đối diện của mặt $B_1B_2B_3$ thông qua các bình phương của các cạnh của khối tứ diện được gọi là công thức Leibniz. Đặc biệt, cả bốn điểm đều có thể thuộc cùng một mặt phẳng hoặc thậm chí thuộc cùng một đường thẳng.

Bài tập
1. Chứng minh rằng tổng bình phương khoảng cách của một điểm bất kỳ trên đường tròn, được mô tả bằng quan hệ đếm biểu thị khoảng cách từ đỉnh $A_1$ của khối tứ diện $A_1B_1B_2B_3$ đến tâm. Chứng minh rằng tổng $|A_1|^2 + |A_2|^2 + |A_3|^2$ không phụ thuộc vào vị trí tương đối của điểm $P$ và $Q$ của đường tròn $\omega$, tổng $|PA|^2 + |PB|^2 + |PC|^2 + |QA|^2 + |QB|^2 + |QC|^2$ không đổi.

5. Có $n$ điểm trên một vòng tròn. Qua trọng tâm của mỗi điểm $n-2$ kẻ một đường thẳng vuông góc với đường thẳng đi qua hai điểm còn lại. Chứng minh rằng $C_n^2$ của các đường thẳng đã dựng cắt nhau tại một điểm (trực tâm của hệ điểm đã cho).

Lập và giải một bài toán tương tự cho trường hợp các điểm $n$ đã cho thuộc cùng một hình cầu.

Lời khuyên dành cho gia sư mới bắt đầu
(xem trang 35)

Nhưng đồng thời, hãy quan tâm đến danh tiếng của một kẻ yếu đuối. Bạn không bao giờ có thể nhấn mạnh nhiều lần rằng bạn không bị thúc đẩy bởi lợi ích cá nhân mà chỉ bởi mong muốn trở nên hợp lý, tử tế và nếu có thể là vĩnh cửu. Không có sự khác biệt nào lớn hơn đối với tâm hồn bạn ngoài cảm giác rằng bạn đã gia tăng xã hội thêm một vài thành viên xứng đáng hơn.

Sau khi phát câu hỏi, hãy đi sang phòng khác và bắt đầu công việc của bạn. Những học sinh giỏi hơn sẽ hoàn thành nhiệm vụ của mình trước rồi mới giúp đỡ những bạn còn tụt lại phía sau. Điều này sẽ phát triển trong họ ý thức về chủ nghĩa tập thể, điều cần thiết đối với một trường đại học.

Đến giữa bài học sẽ nổ ra một cuộc thảo luận sôi nổi về các chủ đề thể thao. Không có nghĩa là ít hơn xương sườn. Hãy để họ, khi rời xa bạn, mong chờ cuộc gặp tiếp theo, trong thời gian đó họ có thể tiếp tục cuộc trò chuyện hấp dẫn.

Cuối bài, đừng quên phát bài tập về nhà được chép trước từ sách giáo khoa cũ đã bị lãng quên và phát hành dưới dạng đề thi mới. Yêu cầu học sinh giữ bí mật nội dung vé của mình. Nó gây ấn tượng mạnh mẽ.

Đừng lo lắng về chất lượng khi bạn bận rộn. Hãy hiểu điều chính - các chàng trai và cô gái đến với bạn chỉ vì lợi ích của cha và mẹ của họ, và chủ đề này ít khiến họ quan tâm nhất. Điều duy nhất bạn nên quan tâm là mọi khoản thanh toán với phụ huynh đều được hoàn thành trước kỳ thi.

Để kết thúc điểm quan trọng này, có hai lời khuyên hữu ích hơn. Vì bạn hoàn toàn không quan tâm đến môn học nào bạn sử dụng để hỗ trợ tài chính, chúng tôi khuyên bạn nên tập trung vào toán học.

(Tiếp theo trang 68.)
