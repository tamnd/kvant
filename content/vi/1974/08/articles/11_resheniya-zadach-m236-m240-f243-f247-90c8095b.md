---
id: 1974-8-resheniya-zadach-m236-m240-f243-f247-90c8095b
issue: kvant_1974_8
year: 1974
number: "8"
title: Lời giải bài toán M236—M240; F243—F247
rubric: zadachnik-kvanta
rubric_sub: Задачник «Кванта»
page_first: 48
page_last: 55
page_labels: 46, 47, 48, 51, 52, 53
tag: Y5MF
lang: vi
source: kvant_digital
extraction: vision
content_sha256: 125e005e5b52b27d2b90913bd3ab8176a5632a87fb7a8b6bf97eba004bdd62f1
prompt_sha256: draft-1
translated_from: content/ru/1974/08/articles/11_resheniya-zadach-m236-m240-f243-f247-90c8095b.md
source_content_sha256: 36b3cab34c289f2f057ecf1bd1ae8d0c2869917d3cfa48181743e935f60400ca
translation_model: draft
translation_run: vi-draft-2026-10-31
translation_quality: draft
---

⟦folio 46⟧

Lời giải bài toán
M236—M240; F243—F247

M236. a) Có 51 số có hai chữ số. Hãy chứng minh rằng từ những số này có thể chọn được ít nhất 6 số sao cho không có hai số nào trong số đã chọn có cùng một chữ số ở bất kỳ chữ số nào.

b) Cho các số tự nhiên k và n, 1 < k < n. Với mọi m nhỏ nhất, các phát biểu sau đây đúng: với bất kỳ sự phân tán nào của m quân trên một bàn có kích thước n × n, có thể chọn k quân từ m này sao cho không có hai quân được chọn nào giống nhau không?

Trước tiên hãy giải bài toán 6). Chúng ta hãy chứng minh rằng nếu m = n (k − 1) + 1 thì luôn có thể chọn k quân sao cho không có hai quân nào giống nhau. (Thực tế là n (k − 1) quân xe không đủ có nghĩa là có quá nhiều thứ để sắp xếp trong k − 1 cột đầu tiên và sau đó không thể chọn nhiều hơn k − 1.) Vì vậy, m = n (k − 1) + 1. Hãy chứng minh rằng từ những m quân xe này luôn có thể chọn một quân sao cho trong “chữ thập” của nó - đi qua một quân xe trong một cột và một hàng - tốn không quá n + k − 2 quân xe. Hãy để điều này không được thực hiện. Trong số tất cả các hàng (hàng và cột), chúng tôi chọn hàng có nhiều quân nhất; Hãy biểu thị số của họ bằng l. Theo giả định, phép thập của mỗi quân xe này chứa nhiều hơn n + k − 2 quân xe; Điều này có nghĩa là có tổng cộng ít nhất l (n − k − l) xe và l ≥ n + k − l và n ≥ l, tức là l ≥ k. Bây giờ dễ dàng thấy rằng l (n + k − l) không nhỏ hơn n · k, lớn hơn m = n (k − 1) + 1 nếu n lớn hơn một. Chúng tôi đã nhận được một mâu thuẫn; Do đó, có một quân xe mà hình chữ thập chứa nhiều nhất n + k − 2 quân xe. Hãy đánh dấu quân xe này và cắt hình chữ thập của nó ra khỏi bến tàu. Từ các phần còn lại, chúng ta sẽ tạo một dock có kích thước (n ​​- 1) × (n - 1). Sẽ có ít nhất m − (n + k − 2) = n (k − 1) + 1 − (n + k − 2) = (n − 1) (k − 2) + 1 quân xe trên bàn cờ mới.

Bây giờ giả sử rằng đối với các bảng r × r, trong đó r < n, mệnh đề đã được chứng minh (ví dụ, hãy kiểm tra nó với n = 3, k = 2). Khi đó trên một bảng gồm (n − 1) × (n − 1) từ (n − 1) · (k − 2) + 1 quân xe luôn có thể chọn (k − 1) quân sao cho không

⟦folio 47⟧

kaospessya bên trong tam giác tại điểm O (Hình 1). Lưu ý rằng để trọng tâm*) của các khối lượng này đạt đến điểm O thì phải thỏa mãn các tương ứng $\frac{m_c}{m_a} = \frac{AD}{DC}$ và $\frac{m_b}{m_a} = \frac{AE}{BE}$ (chứng minh điều này). Bây giờ chúng ta hãy chuyển sang lời giải bài toán.
a) Gọi BD và CE là các đường cao của tam giác ABC (Hình 2). Sau đó
$$\frac{BD}{AD} = \text{tg} \alpha, \quad \frac{BD}{DC} = \text{tg} \gamma,$$
đó là
$$\frac{AD}{DC} = \frac{\text{tg} \gamma}{\text{tg} \alpha}.$$
Theo nhận xét sau đây, $\frac{m_c}{m_a} = \frac{\text{tg} \gamma}{\text{tg} \alpha}$ và tương tự $\frac{m_b}{m_a} = \frac{\text{tg} \beta}{\text{tg} \alpha}$. Điều này có nghĩa là, ví dụ, khối lượng $m_a = \text{tg} \alpha, m_b = \text{tg} \beta, m_c = \text{tg} \gamma$ có ​​thể được đặt ở các đỉnh A, B, C của tam giác ABC.
6) Gọi O là tâm của đường tròn ngoại tiếp (Hình 3). Chúng tôi có:
$$\frac{AD}{BD} = \frac{\sin \beta_1}{\sin \alpha},$$
$$\frac{DC}{BD} = \frac{\sin \beta_2}{\sin \gamma}.$$
(định nghĩa về sin của các tam giác ABD và BCD).
Vì thế
$$\frac{AD}{DC} = \frac{\sin \gamma \cdot \sin \beta_1}{\sin \alpha \cdot \sin \beta_2}.$$
Tam giác BAK - hình chữ nhật

*) Về trọng tâm, xem bài viết của M. B. Balka, N. A. Grigoriev, Cơ học giúp hình học, «Kvant», 1973, Số 11, tr. 34-35.

(✉BAK = 90°) và ✉BKA = ✉BCA = γ; do đó $\sin \beta_1 = \cos \gamma$. Tương tự như $\sin \beta_2 = \cos \alpha$.
Vì thế,
$$\frac{AD}{DC} = \frac{\sin \gamma}{\sin \alpha} \cdot \frac{\cos \gamma}{\cos \alpha} = \frac{\sin 2\gamma}{\sin 2\alpha}.$$
Xem xét ghi chú:
$$\frac{m_c}{m_a} = \frac{\sin 2\gamma}{\sin 2\alpha}.$$
Theo cách tương tự
$$\frac{m_b}{m_a} = \frac{\sin 2\beta}{\sin 2\alpha}.$$
Vì vậy chúng ta có thể lấy $m_a = \sin 2\alpha, m_b = \sin 2\beta, m_c = \sin 2\gamma$.
c) Dễ dàng nhận thấy (xem Hình 4) rằng AD=p-a, DC=p-c, trong đó $p = \frac{a+b+c}{2}$, do đó
$$\frac{m_c}{m_a} = \frac{p-a}{p-c}.$$
Tương tự AE=p-a, EB=p-b, tức là
$$\frac{m_b}{m_a} = \frac{p-a}{p-b}.$$
Vì vậy, chỉ cần đặt
$$m_a = \frac{1}{p-a}, \quad m_b = \frac{1}{p-b}, \quad m_c = \frac{1}{p-c}.$$
d) Vì BD là phân giác của góc B (xem Hình 5), nên $\frac{AD}{DC} = \frac{c}{a}$ hoặc $\frac{m_c}{m_a} = \frac{c}{a}$;
tương ứng CE là phân giác của góc C và $\frac{AE}{BE} = \frac{b}{a}$, tức là $\frac{m_b}{m_a} = \frac{b}{a}$. Vì vậy, bạn có thể lấy $m_a = a, m_b=b, m_c=c$.

B. D. Ginzburg

⟦folio 48⟧

Hình 6.

**M238.** Chứng minh rằng tổng $C_n^1 + C_n^3 \cdot 1973 + C_n^5 \cdot (1973)^2 + C_n^7 \cdot (1973)^3 + \dots$ chia hết cho $2^{n-1}$. (Ở đây $C_n^k$ là các hệ số nhân của số nhân)

$$ (a + b)^n = \sum_{k=0}^{n} C_n^k a^k b^{n-k}. $$

Chúng ta sẽ giải bài toán bằng quy nạp. Hãy đặt

$$ \gamma_n = C_n^1 + C_n^3 \cdot 1973 + C_n^5 \cdot (1973)^2 + \dots $$

Chúng tôi có:

$$ \gamma_1 = 1 \text{ делится на } 2^{1-1}=1; $$
$$ \gamma_2 = 2 \text{ делится на } 2^{2-1}=2. $$

Giả sử rằng với tất cả $k<n$

$$ \gamma_k = C_k^1 + C_k^3 \cdot 1973 + \dots. $$

chia hết cho $2^{k-1}$ và ta sẽ chứng minh rằng $\gamma_n$ chia hết cho $2^{n-1}$. Từ định nghĩa của số $C_n^k$ suy ra ngay như sau

$$ \gamma_n = C_n^1 + C_n^3 \cdot 1973 + \dots = \frac{(1 + \sqrt{1973})^n - (1 - \sqrt{1973})^n}{2\sqrt{1973}}. $$

Chúng ta hãy biểu thị $1 + \sqrt{1973}$ bằng $\alpha, a_1 - \sqrt{1973}$ bằng $\beta$.

Khi tính đến các ký hiệu này, chúng tôi viết lại $\gamma_n$ như sau:

$$ \gamma_n = \frac{(\alpha^{n-1} - \beta^{n-1})(\alpha + \beta)}{2\sqrt{1973}} - \frac{\alpha \beta (\alpha^{n-2} - \beta^{n-2})}{2\sqrt{1973}} = 2\gamma_{n-1} + 1972 \gamma_{n-2} = 2\gamma_{n-1} + 4 \cdot 493\gamma_{n-2}. $$

Theo giả định quy nạp, $\gamma_{n-1}$ chia hết cho $2^{n-2}$, $\gamma_{n-2}$ chia hết cho $2^{n-3}$; Điều này có nghĩa là toàn bộ số tiền chia hết cho $2^{n-1}$ - đây là điều cần chứng minh.

L. G. Limanov

**M239.** Cho hai điểm $A$ và $B$ trên mặt phẳng. Giả sử $C$ là một điểm không sắc nét có khoảng cách bằng nhau với $A$ và $B$. Chúng ta hãy xây dựng một chuỗi các điểm $C_1 = C$, $C_2$, $C_3$, ..., $C_n$, $C_{n+1}$, ..., và $C_{n+1}$ - tâm của đường tròn ngoại tiếp tam giác $AC_nB$. Ở vị trí nào của điểm $C$

a) điểm $C_n$ sẽ rơi ở giữa đoạn $AB$ (trong trường hợp này $C_{n+1}$ và các số hạng tiếp theo của dãy không được xác định)?
b) điểm $C_n$ có trùng với $C$ không?

Hãy để $\not\Rightarrow C_nBA = \not\Rightarrow C_nAB = \alpha_n$. Dễ dàng kiểm tra (Hình 6 a, 6) rằng đối với một tam giác nhọn

$$ \alpha_{n+1} = 2\alpha_n - \frac{\pi}{2}, \frac{\pi}{4} < \alpha_n < \frac{\pi}{2}, $$

cho sự tù túng

$$ \alpha_{n+1} = \frac{\pi}{2} - 2\alpha_n, 0 < \alpha_n < \frac{\pi}{4}. $$

Điều này có thể được viết bằng một công thức:

$$ \alpha_{n+1} = \left| 2\alpha_n - \frac{\pi}{2} \right|, 0 < \alpha_n < \frac{\pi}{2}, $$

cũng phù hợp với tam giác vuông; với $\alpha_n = \frac{\pi}{4}$ chúng ta nhận được $\alpha_{n+1} = 0$ - tâm $C_{n+1}$ nằm ở giữa đoạn $AB$.

Chúng ta đặt $\alpha_n = x_n \cdot \frac{\pi}{2}$ ($x_n$ là tỷ lệ giữa giá trị của góc $\alpha_n$ với giá trị của góc vuông). Từ (3), rõ ràng là $x_n$ thu được từ $x_0$ bằng $n$-gấp ánh xạ áp dụng

$$ x \rightarrow f(x) = |2x - 1|, x \in [0, 1], $$

hình 7.

⟦folio 51⟧

Bình luận. Chúng tôi đã tính đa thức $x^{1000}$ bằng phương pháp (2). Tuy nhiên, có những đa thức mà cả phương pháp (1) lẫn phương pháp (2) đều không phải là tốt nhất. Ví dụ: đa thức $x^{170}$ có thể được tính bằng 9 phép nhân (bạn hãy tự tìm cách làm như vậy!), mặc dù $\langle 170 \rangle_2 = 10 \cdot 101 \cdot 010$, vì vậy $E(170) = H(170) = 4$, $[\log_2 170] = 7$; với phương pháp (1) bạn cần 10 phép nhân và với phương pháp (2) - 11 phép nhân và một phép chia.

E. G. Belaya

F243. Tại sao, trong ánh sáng rực rỡ, những người sử dụng kính không mạnh lắm có thể đọc tôi mà không mắc lỗi?

Tại sao, để tạo thành đồng thời hai vật thể, một vật ở xa vật kia hơn và thu được hình ảnh sắc nét của vật đó trên vật đó thì tổng đường kính khẩu độ của vật đó (đường kính thấu kính) lại giảm xuống?

Hình ảnh sắc nét do thấu kính của một mắt không hoàn hảo tạo ra không phải ở võng mạc mà ở phía trước võng mạc nếu người đó bị cận thị, hoặc phía sau võng mạc nếu người đó bị viễn thị. Trong cả hai trường hợp, hình ảnh của từng điểm trên võng mạc của mắt thu được dưới dạng một điểm tròn nóng chảy, đường kính của điểm này phụ thuộc vào đường kính của đồng tử và mức độ cận thị (hoặc viễn thị) của người đó (Hình 9). Đường kính của đồng tử càng nhỏ thì chùm tia tạo ảnh của một điểm càng hẹp, chùm tia tạo ảnh trên võng mạc càng nhỏ. Trong ánh sáng mạnh, đường kính của đồng tử giảm và hình ảnh cây sồi đối với những người đeo kính không mạnh có vẻ hơi mờ. Vì vậy, họ có thể đọc mà không mắc lỗi. Đối với những người sử dụng cửa sổ chắc chắn, hình ảnh của cây sồi ở xa võng mạc và mặc dù đường kính của đồng tử nhỏ nhưng hình ảnh của cây sồi rất mờ nên vẫn không thể đọc được văn bản mà không mắc lỗi.

Tương tự, việc tăng độ sâu trường ảnh (nghĩa là diện tích

Hình 10.

trở nên sắc nét trên phim ảnh) bằng cách giảm đường kính lỗ của vật thể. Thật vậy, trống rỗng, chúng ta muốn tạo thành đồng thời hai điểm nằm cách nhau một khoảng (Hình 10). Nếu thiết bị được hình thành trên một vật thể nào đó giữa hai điểm này (thấu kính cho hình ảnh sắc nét của vật thể này trên phim ảnh), thì hình ảnh của điểm trên phim ảnh sẽ bị mờ, nhưng đường kính của từng điểm - được mô tả bằng các chấm - phụ thuộc vào đường kính lỗ của vật thể, giảm khi đường kính này giảm.

F244. Được gắn vào hai điểm là các chuỗi có chiều dài l và hai đầu của hai thanh, tổng chiều dài của chúng có thể bằng l và các đầu tự do có bản lề. Chúng ta ở dưới sợi dây mềm mại của ai - sợi dây chuyền hay những chiếc que?

Kéo một trong các mắt xích của dây xích (Hình 11), nó có thể được tạo thành hình que. Trong trường hợp này, công việc sẽ được thực hiện, rất thuận tiện là làm tăng thế năng của dây xích, tức là nâng trọng tâm của nó lên. Do vị trí mới của trọng tâm của dây xích trùng với vị trí của trọng tâm của các thanh nên rõ ràng dây xích của dây treo tự do nằm bên dưới trọng tâm của các thanh.

F245. Có một bán cầu được tải đồng đều. a) Chứng minh rằng mặt phẳng “che” bán cầu này là tương đương. b) Xác định hướng của từ trường tại các điểm trên mặt phẳng này.

Mật độ của bán cầu chịu tải là σ.

⟦folio 52⟧

Chúng ta hãy thêm hai bán cầu tích điện đồng đều giống hệt nhau với mật độ điện tích bằng nhau. Trong trường hợp này, chúng ta có một quả cầu tích điện đều, bên trong đó hướng trường, như đã biết, bằng không. Tuy nhiên, theo nguyên lý chồng chất, hướng của trường điện tích của quả cầu bằng tổng các hướng của trường điện tích của các bán cầu. Do đó, tổng $E_1 + E_2$ hướng của trường điện tích của các bán cầu bằng 0. Điều này chỉ có thể thực hiện được nếu $|E_1| = |E_2|$ và ngoài ra, cả hai vectơ $E_1$ và $E_2$ đều hướng về mặt phẳng $\Pi$, mặt phẳng “bao phủ” bán cầu. Thật vậy, từ tính đối xứng, rõ ràng các thành phần của vectơ $E_1$ và $E_2$, song song với mặt phẳng này, phải bằng nhau. Khi được thêm vào, chúng chỉ cho số 0 nếu bản thân chúng bằng 0.

Vì vậy, chúng ta đã chứng minh được rằng vectơ hướng trường tại các điểm của mặt phẳng $\Pi$ vuông góc với mặt phẳng này. Điều này có nghĩa là khi di chuyển một điện tích trong mặt phẳng $\Pi$, công không trùng nhau. Do đó mặt phẳng $\Pi$ là tương đương.

Bây giờ chúng ta hãy tìm hướng trường tại các điểm của mặt phẳng $\Pi$. Theo nguyên lý chồng chất, hướng của trường tại điểm $O$ bằng tổng hướng của các trường điện tích của từng phần riêng lẻ của bán cầu. hướng của trường điện tích phần $A$ rõ ràng bằng nhau về giá trị tuyệt đối

$$E_A = \frac{Q_A}{R^2} = \frac{\sigma S_A}{R^2},$$

trong đó $S_A$ là diện tích của phần $A$ (phần $A$ là phần định hướng của bán cầu, một cột xà phòng, có thể coi là phẳng, tức là kích thước tuyến tính của nó nhỏ hơn nhiều so với bán kính của bán cầu).

 Hướng của trường tại điểm $O$ rõ ràng bằng tổng hướng của trường điện tích của từng phần riêng lẻ của bán cầu. Thành phần $E_A$, hướng về mặt phẳng của bán cầu, bằng $E_A$ cos $\alpha$ (xem Hình 12). Vì vậy chúng ta cần

$$E = \sum \frac{\sigma}{R^2} S_A \cos \alpha = \frac{\sigma}{R^2} \Sigma S_A \cos \alpha.$$

Vì $S_A$ cos $\alpha$ là hình chiếu của diện tích của phần $A$ lên mặt phẳng $\Pi$, và tổng các hình chiếu đó của diện tích của tất cả các phần của bán cầu rõ ràng bằng diện tích của mặt phẳng $\Pi$, tức là $\pi R^2$, nên

$$E = \frac{\sigma}{R^2} \pi R^2 = \pi \sigma.$$

Chúng tôi đã tìm thấy hướng ở tâm của mặt phẳng $\Pi$. Không khó để tìm ra hướng của trường tại các điểm của đường tròn, đó là giao điểm của mặt phẳng $\Pi$ và bán cầu. Vì bề mặt của bán cầu là tương đương nên các đường hợp lưu tại bất kỳ điểm nào của bán cầu phải vuông góc với bán cầu. Mặt khác, tại các điểm $C$ và $B$ phải vuông góc với mặt phẳng $\Pi$. Tuy nhiên, cả hai đều chỉ có thể xảy ra nếu hướng của trường tại những điểm này bằng không.

Việc tìm ra hướng của trường được tạo ra bởi điện tích của bán cầu tại các điểm khác của mặt phẳng đòi hỏi những phép tính phức tạp. Lĩnh vực này không phải là không phù hợp. Rõ ràng, nó có tính đối xứng đối với điểm $O$ và tại mỗi điểm của mặt phẳng phụ thuộc vào khoảng cách đến điểm này từ tâm $O$.

F246. Một bình thủy tinh có thể tích 2 V được chia đôi bằng một vách ngăn. Trong một đa giác của bình chứa một loại khí đơn nguyên tử có nhiệt độ $T_1$ và áp suất $p_1$, trong đa giác kia có một loại khí đơn nguyên tử khác có áp suất $p_2$ và nhiệt độ $T_2$. Tìm nhiệt độ cài đặt của hỗn hợp khí sau mỏ khi vách ngăn được loại bỏ.

Hãy sử dụng định luật bảo toàn năng lượng. Vì bình dẫn nhiệt nên tổng năng lượng của các chất khí không thể thay đổi khi chúng chuyển động. Nội năng $n$ mol của khí đơn nguyên lý tưởng bằng động năng của chuyển động hỗn loạn của các phân tử khí:

$$U = \frac{3}{2} nRT,$$

trong đó $T$ là nhiệt độ tuyệt đối của khí, $R$ là hằng số khí phổ quát. Điều này có nghĩa là cho đến khi bỏ vách ngăn đi, nội năng của hệ bằng

$$U = \frac{3}{2} n_1RT_1 + \frac{2}{3} n_2RT_2$$

($n_1$ là số mol khí thứ nhất, $n_2$ là số mol khí thứ hai). Sau khi vách ngăn được loại bỏ, nhiệt độ của khí trở thành $\frac{3}{2} n_1RT$ và $\frac{3}{2} n_2RT$. Theo định luật bảo toàn năng lượng

$$\frac{3}{2} n_1RT_1 + \frac{3}{2} n_2RT_2 = \frac{3}{2} n_1RT + \frac{3}{2} n_2RT.$$

⟦folio 53⟧

Hình 13.

Từ đây

$$T = \frac{n_1 T_1 + n_2 T_2}{n_1 + n_2} = \frac{\frac{n_1}{n_2} T_1 + T_2}{\frac{n_1}{n_2} + 1}.$$

Biểu thức này bao gồm quan hệ $n_1/n_2$. Để tìm nó, chúng ta viết phương trình trạng thái khí cho cả hai khí trước khi trộn:

$$p_1 V = n_1 R T_1; \quad p_2 V = n_2 R T_2.$$

Chia đẳng thức thứ nhất cho đẳng thức thứ hai, ta được

$$\frac{n_1}{n_2} = \frac{p_1}{p_2} \frac{T_2}{T_1}.$$

Kể từ đây,

$$T = \frac{T_1 T_2 (p_1 + p_2)}{p_1 T_2 + p_2 T_1}.$$

F247. Mô hình phân tử carbon dioxide CO₂ là một quả bóng, được nối với nhau bằng lò xo và nằm ở vị trí cân bằng dọc theo một đường thẳng. Một phân tử như vậy có thể thực hiện các dao động tuyến tính thuộc hai loại: a) hoặc b) trong Hình 13. Tên tần số của các dao động thực nghiệm.

Chúng ta hãy biểu thị độ cứng của các lò xo của mô hình phân tử là $k$, khối lượng của các quả bóng là nguyên tử oxy là $M$ và khối lượng của quả bóng là các nguyên tử carbon là $m$ ($m/M = 12/16$).

Thực hiện các dao động loại $a$), cả hai nguyên tử oxy đều dao động đồng bộ so với nguyên tử carbon đứng yên. Điều này là do thực tế là, do tính đối xứng của dao động của các nguyên tử oxy, các lực có độ lớn tuyệt đối bằng nhau và ngược chiều tác dụng lên nguyên tử carbon từ cả hai phía tại bất kỳ thời điểm nào, chúng “cân bằng” lẫn nhau. Do đó, trong trường hợp a) nguyên tử oxy thực hiện dao động tự do, chu kỳ của dao động này bằng

$$T_a = 2\pi \sqrt{\frac{M}{k}}.$$

Trong các dao động loại $\delta$), các tác động lên nguyên tử carbon có cường độ tuyệt đối như nhau, nhưng chúng hướng theo cùng một hướng. Nếu một quả bóng - một nguyên tử carbon được chia thành hai phần bằng nhau thì rõ ràng là chúng sẽ dao động thống nhất: chúng luôn chịu tác dụng của các lực bằng nhau và do đó, các nửa quả bóng sẽ có cùng gia tốc, vận tốc và tọa độ tại bất kỳ thời điểm nào. Tần số rung của phân tử CO₂ bằng tần số rung của hệ thống bao gồm một nguyên tử oxy và một nửa nguyên tử carbon. Do đó, bài toán dùng để xác định chu kỳ dao động của các quả bóng có khối lượng $M$ và $m/2$ được nối với nhau bằng một lò xo. Những quả bóng như vậy dao động xung quanh khối tâm cố định của hệ. Nếu chiều dài của lò xo ở trạng thái không bị đóng đinh bằng $l$ thì khối tâm của hệ cách quả cầu có khối lượng $M$ một khoảng $l \frac{m}{m+2M}$. Do đó, chúng ta có thể giả sử rằng một quả cầu có khối lượng $M$ (nguyên tử oxy) dao động so với tâm của một lò xo có chiều dài

$$l_1 = l \frac{m}{m+2M}.$$

Độ cứng của một phần lò xo lớn hơn độ cứng của toàn bộ lò xo. Vì độ cứng tỉ lệ nghịch với phần tương đối với chiều dài của toàn bộ lò xo nên độ cứng của một phần lò xo

$$k_1 = k \frac{l}{l_1} = k \frac{m+2M}{m}.$$

Chu kỳ dao động của một quả cầu có khối lượng $M$ trên một lò xo cứng $k_1$ bằng

$$T_\delta = 2\pi \sqrt{\frac{M}{k_1}} = 2\pi \sqrt{\frac{mM}{k(m+2M)}}.$$

MỘT

$$\frac{T_\delta}{T_a} = \sqrt{\frac{m+2M}{m}} = \sqrt{1 + \frac{2M}{m}}.$$

Vì $\frac{M}{m} = \frac{16}{12} = \frac{4}{3}$, từ

$$\frac{T_\delta}{T_a} = \sqrt{1 + \frac{8}{3}} = \sqrt{\frac{11}{3}}.$$

Do đó, tỷ số tần số

$$\frac{v_\delta}{v_a} = \sqrt{\frac{3}{11}}.$$

Tôi. Sh. Tiếng Slovodechkiy
