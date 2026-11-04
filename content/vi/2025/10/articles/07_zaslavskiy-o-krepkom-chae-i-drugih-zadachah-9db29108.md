---
id: 2025-10-zaslavskiy-o-krepkom-chae-i-drugih-zadachah-9db29108
issue: kvant_2025_10
year: 2025
number: "10"
title: Về trà đặc và các công việc khác
authors:
  - Заславский А. А.
rubric: matematicheskiy-kruzhok
rubric_sub: Математический кружок
page_first: 37
page_last: 44
page_labels: 35, 36, 37, 39, 40, 41, 42
lang: vi
source: kvant_digital
extraction: vision
content_sha256: c32cf67dc6b7cf1a670d6dc5a812ab459670959e6e0121cb60e87d6e8c9b3279
prompt_sha256: draft-1
translated_from: content/ru/2025/10/articles/07_zaslavskiy-o-krepkom-chae-i-drugih-zadachah-9db29108.md
source_content_sha256: 19a0330694bcf90b6d091b71403c64ca6d67964f92c3468b252c0689c56a9123
translation_model: draft
translation_run: vi-draft-gaps-2026-11-04
translation_quality: draft
---

⟦folio 35⟧

VÒNG TRÒN TOÁN HỌC

Về trà đặc và các công việc khác

A. ZASLAVSKY

“Cô ấy không muốn uống trà lớn,” March Hare nói.
“Có lẽ bạn muốn nói rằng cô ấy không muốn uống ít trà hơn,” Bolshinchik trả lời.

L. Carroll. Alice ở xứ sở thần tiên

Sản xuất bài toán

Hãy xem xét bài toán sau đây.
Bài toán. Nếu hai ly giống hệt nhau chứa nửa ly trà có nồng độ lần lượt là $a_1$ và $a_2$ và một cốc chứa nửa ly nước. Nước từ cốc

ki được rót vào ly, sau đó đổ cùng một lượng chất lỏng từ mỗi ly vào cốc. Nồng độ tối đa của trà bạn có thể nhận được trong một cốc là bao nhiêu?

Thoạt nhìn, có vẻ như điều tốt nhất nên làm là đổ hết nước vào ly trà đậm hơn. Tuy nhiên, điều này chỉ đúng khi nồng độ trà trong một ly cao hơn bốn lần nồng độ trong ly kia. Ví dụ: nếu nồng độ ban đầu là 80% và 25% thì khi đổ hết nước vào ly đầu tiên, chúng ta sẽ thu được nồng độ 40% và nếu chúng ta chia nước cho các ly theo tỷ lệ xấp xỉ 0,924:0,076 thì nồng độ trà trong cốc sẽ tăng lên 40,2%.

bài toán càng trở nên thú vị hơn khi có thêm kính. Ví dụ: nếu có ba ly có nồng độ trà là 80%, 40% và 25%, thì độ đậm đặc tối đa của trà trong một cốc, bằng 42,3%, sẽ đạt được nếu có khoảng 0,757 cốc được đổ vào cốc đầu tiên và phần nước còn lại trong cốc thứ hai.

Trong bài viết này chúng tôi sẽ đưa ra lời giải bài toán cho trường hợp tổng quát khi có $n$ kính

⟦folio 36⟧

---
running_head:
folio:
---

với nồng độ trà trong đó $a_1, \ldots, a_n$. Trong trường hợp này, chúng tôi sẽ giả sử rằng $a_1 \geq a_2 \geq \ldots \geq a_n$.

Lời giải bài toán

Trước hết chúng ta hãy tìm nồng độ của trà trong cốc. Chúng ta lấy thể tích chất lỏng trong ly là 1 và biểu thị thể tích nước đổ vào ly thứ $i$ là $x_i$. Sau đó, sau khi rót, thể tích chất lỏng trong ly này sẽ bằng $1 + x_i$ và do đó, nồng độ của trà sẽ giảm xuống $a_i / (1 + x_i)$. Do đó, lượng chất lỏng $x_i$ đổ từ ly này trở lại cốc sẽ chứa $g_i(x_i) = a_i x_i / (1 + x_i)$ trà, và nồng độ hứa hẹn của trà trong cốc sẽ là $g_1(x_1) + \ldots + g_n(x_n)$. Vì vậy, chúng ta cần tìm giá trị lớn nhất của hàm $g_1(x_1) + \ldots + g_n(x_n)$ cho các giá trị của $x_1, \ldots, x_n$ thỏa mãn điều kiện
$$x_i \geq 0, x_1 + \ldots + x_n = 1.$$
Xem xét đồ thị của hàm $g_i(x_i)$ (xem hình), dễ dàng nhận thấy rằng hàm này đang tăng, nhưng đạo hàm $g_i'(x_i) = a_j / (1 + x_i)^2$ của nó thì không. Thuộc tính cuối cùng có nghĩa là các hàm $g_i$ đều có thể thực hiện được và do đó tổng của chúng sẽ là hàm lõm.

Chúng ta sẽ không đưa ra một định nghĩa chặt chẽ về hàm lõm. Chúng ta chỉ cần nói thêm rằng độ lõm hình học có nghĩa là đoạn nối hai điểm bất kỳ trên đồ thị của hàm số nằm bên dưới đồ thị. Điều này cũng đúng với hàm lõm nhiều biến.

Hàm lõm có tính chất quan trọng sau.

**Định lý.** Hàm lõm xác định trên một viconvex, đóng (tức là chứa biên của nó) được đặt bởi ràng buộc đạt giá trị cực đại tại một điểm duy nhất.

Liên quan đến bài toán của chúng tôi, điều này có nghĩa là có một tập hợp các biến duy nhất $(x_1, \ldots, x_n)$ mà tại đó đạt được độ mạnh tối đa của trà. Khám phá các thuộc tính của nó.

**Bổ đề 1.** Nếu trong tập tối ưu các biến $x_i, x_j$ là dương thì
$$g_i'(x_i) = g_j'(x_j).$$

**Chứng minh.** Hãy biểu thị tổng $x_i + x_j$ bằng $c$ và xét hàm $h(x) = g_i(x) + g_j(c - x)$. Đạo hàm của nó là $h'(x) = g_i'(x) - g_j'(c - x)$. Nếu $g_i'(x_i) \neq \neq g_j'(x_j)$ thì $h'(x_i) \neq 0$ và hàm $h$ không thể đạt cực đại tại điểm $x_i$. Khi đó hàm $g_1(x_1) + \ldots + g_n(x_n)$ không thể đạt mức tối đa trên tập hợp $(x_1, \ldots, x_n)$.

Từ Bổ đề 1, các giá trị của tích $g_i'(x_i)$ đều bằng nhau đối với tất cả các biến dương $x_i$. Chúng ta hãy biểu thị ý nghĩa chung của chúng bằng $k$.

**Bổ đề 2.** Nếu $x_j = 0$, thì $g_j'(x_j) \leq k$.

Cách chứng minh Bổ đề 2 cũng tương tự như cách chứng minh Bổ đề 1: nếu $x_i > 0$, $x_j = 0$ và $g_j'(x_j) > g_i'(x_i)$, thì bằng cách tăng giá trị của $x_j$ và giảm giá trị của $x_i$ một lượng bằng nhau, chúng ta có thể tăng giá trị của $g_1(x_1) + \ldots + g_n(x_n)$.

Từ Bổ đề 1 và 2, xét đến thực tế là $g_i'(x_i) < g_i'(0) = a_i$ và $a_1 \geq a_2 \geq \ldots \geq a_n$, thì tập hợp tối ưu $(x_1, \ldots, x_n)$ có ​​dạng sau. Đối với một số $m \leq n$
$$x_1, \ldots, x_m > 0,$$
$$x_{m+1} = \ldots = x_n = 0,$$
$$x_1 + \ldots + x_m = 1,$$
$$g_i'(x_1) = \ldots = g_m'(x_m) \geq a_{m+1}.$$

Việc còn lại là xác định giá trị $m$ và các biến $x_1, \ldots, x_m$. Ký hiệu $g_i'(x_1) = k$ như trước, ta được
$$\frac{a_i}{(1 + x_i)^2} = k, \quad i = 1, \ldots, m,$$
$$x_i = \sqrt{\frac{a_i}{k}} - 1,$$
$$x_1 + \ldots + x_m = \frac{\sqrt{a_1} + \ldots + \sqrt{a_m}}{\sqrt{k}} - m = 1,$$
$$\sqrt{k} = \frac{\sqrt{a_1} + \ldots + \sqrt{a_m}}{m + 1},$$
$$x_i = \frac{(m + 1)\sqrt{a_i}}{\sqrt{a_1} + \ldots + \sqrt{a_m}} - 1.$$

Hơn nữa, từ điều kiện $x_m > 0$ ta thu được $\sqrt{a_m} > \left(\sqrt{a_1} + \ldots + \sqrt{a_m-1}\right)/m$ đó, và từ điều kiện

⟦folio 37⟧

---
running_head:
folio:
---

$g'_m(x_m) \geq a_{m+1}$, tức là $\sqrt{a_{m+1}} \leq \left( \sqrt{a_1} + \ldots + \sqrt{a_m} \right)/m$.
Điều này xác định duy nhất $m$ và cho phép chúng ta hình thành thuật toán sau lời giải bài toán.

1. Hãy tính các đại lượng $b_i = \sqrt{a_i}$ và $s_i = (b_1 + \ldots + b_{i-1})/i$.

2. Chúng ta hãy tìm $m$ nhỏ nhất mà $b_{m+1} \leq s_{m+1}$.

3. Hãy đặt $x_{m+1} = \ldots = x_n = 0$ và tính các giá trị của $x_1, \ldots, x_m$ bằng các công thức trên.

Cụ thể, áp dụng thuật toán này cho các ví dụ được đưa ra ở đầu bài viết, chúng ta thu được đáp số được chỉ định.

Cuộc thảo luận

Cách tiếp cận bài toán để tối đa hóa độ mạnh của trà trông không được tự nhiên cho lắm. Tuy nhiên, nhiều bài toán được áp dụng được mô tả bằng các mô hình toán học tương tự. Ví dụ: giả sử chúng ta cần phân phối một nguồn lực hạn chế giữa $n$ doanh nghiệp thuộc bất kỳ loại nào, một loại sản phẩm nào đó và nếu doanh nghiệp thứ $i$ được phân bổ nguồn lực $x_i$, thì lợi nhuận nhận được từ doanh nghiệp này bằng $g_i(x_i)$, trong đó $g_i$ là hàm tăng dần và (thường) lõm. Khi đó, bài toán của việc cực đại hóa tổng xấp xỉ có dạng giống như dạng chúng ta đã xem xét và lời giải của nó cũng thỏa mãn Bổ đề 1 và 2, vì trong chứng minh các bổ đề này, chúng ta chỉ sử dụng hàm lõm $g_i$. Hơn nữa, nếu chúng ta sắp xếp các doanh nghiệp theo thứ tự giảm dần giá trị $g'_0(0)$ thì giải pháp tối ưu sẽ là phân phối tài nguyên giữa các doanh nghiệp $m$ đầu tiên cho một số $m \leq n$.

Chúng ta có thể xem xét một bài toán tổng quát hơn: có một số tiền $S$ có thể được chi để mua $n$ sản phẩm và giá của $p_1, \ldots, p_n$ sản phẩm là cố định. Mỗi bộ sản phẩm $(x_1, \ldots, x_n)$ được đặc trưng bởi một số tiện ích và nếu chúng ta cố định giá trị của tất cả các biến ngoại trừ $x_i$, thì tiện ích sẽ là hàm tăng nhưng lõm của $x_i$. Hàm tùy ý của hàm này được gọi là *tiện ích cận biên* của tích thứ $i$. Nhiệm vụ chính thức tập trung vào việc tìm kiếm một bộ sản phẩm tối đa hóa tiện ích và đáp ứng các điều kiện.

$x_j \geq 0$,
$p_1x_1 + \ldots + p_nx_n \leq S$.

Cụ thể, trường hợp khi $p_1 = \ldots = p_n = 1$ và tiện ích của tập hợp $(x_1, \ldots, x_n)$ bằng $g_1(x_1) + \ldots + g_n(x_n)$, chúng ta thu được bài toán để xem xét. Lập luận theo cách tương tự như trong chứng minh Bổ đề 1, chúng ta thu được các phát biểu sau.

**Bổ đề 1'.** Đối với gói tối đa hóa tiện ích, tiện ích cận biên của các sản phẩm được mua tỷ lệ thuận với giá của chúng.

Tuyên bố này được gọi là *giá hữu dụng cận biên*. Nói một cách không chính thức, đồng xu cuối cùng chi cho mỗi sản phẩm sẽ tạo ra cùng một tiện ích. Trong trường hợp tổng quát bài toán việc tìm giá trị lớn nhất của hàm lõm xác định trên một tập lồi, đóng, bị chặn được gọi là *bài toán lập trình lồi*. Có nhiều phương pháp để giải bài toán đó một cách hiệu quả. Một phần quan trọng của các phương pháp này dựa trên *định lý Kuhn-Tucker*, mô tả các thuộc tính của lời giải tối ưu. Công thức Bổ đề 1 và 2 của chúng tôi là kết quả của việc áp dụng định lý này để xem xét bài toán.

Tác giả cảm ơn I. Sonin và Y. Malinovsky, người đã thu hút sự chú ý của ông đến việc xem xét bài toán và vui lòng cho phép tôi sử dụng tài liệu của họ.

⟦folio 39⟧

---
running_head:
folio:
---

Lưu ý rằng biểu thức thu được hoàn toàn trùng khớp với hướng của trường được tạo ra tại điểm $P$ bởi một phần nhỏ của cung tròn có bán kính $h$ với mật độ điện tích tuyến tính $\lambda$ (hình 3). Vì mỗi phần nhỏ của một đoạn có thể được gán cho phần riêng của nó trong một cung tròn có cùng trường, nên theo nguyên tắc chồng chất, hướng tại điểm $P$ luôn trùng với hướng của toàn bộ đoạn (cả về mô hình và hướng).

Sự thật 2. Hướng của trường của đoạn $AB$ hướng dọc theo phân giác của góc $APB$.

Bằng chứng. Hãy sử dụng thực tế 1: hướng của trường của một đoạn trùng với hướng của trường của cung tương ứng. Từ thông điệp của sự đối xứng, rõ ràng hướng của trường cung tròn tại tâm cong hướng dọc theo đường phân giác của góc, vì nó là trục đối xứng của cung tròn (hình 4). Chúng ta có thể chứng minh điều đó chi tiết hơn: xét các đoạn nhỏ của cung đối xứng với đường phân giác và lưu ý rằng các thành phần định hướng vuông góc với đường phân giác triệt tiêu nhau.

Sự thật 3. Hướng của trường của một cung tròn bán kính $R$ với mật độ điện tích tuyến tính $\lambda$ và độ lớn góc $\alpha$ tại tâm cong của cung tròn bằng

$$E = \frac{2k\lambda}{R}\sin \frac{\alpha}{2}.$$

Bằng chứng. Hãy sử dụng nguyên lý chồng chất và phương pháp xếp chồng. Để một cung có mật độ điện tích tuyến tính $+\lambda$ tạo ra một trường $E_+$ tại tâm cong của nó, hướng dọc theo đường phân giác của góc $\alpha$. Hãy quay cung tròn một góc nhỏ $\Delta\alpha$ và tích điện với cùng mật độ tuyến tính theo mô hình, nhưng trái dấu, tức là với mật độ $-\lambda$. Rõ ràng là hướng trường của cung mới sẽ giống nhau theo mô hình: $E_- = E_+$, nhưng hướng sẽ thay đổi thành $180^\circ$ do thay đổi dấu của điện tích và thành $\Delta\alpha$ do chuyển động quay chung của cung. Bây giờ, hãy xếp chồng hai phân bố điện tích này lên nhau, như minh họa trong hình 5.

Hình 5

Trường tổng $E_c$ có phân bố như vậy có thể được tìm thấy thông qua các hướng $E_-$ và $E_+$. Lưu ý rằng tam giác gồm các vectơ $\vec{E}_+$, $\vec{E}_-$ và $\vec{E}_c$ là tam giác đều ($E_+ = E_- = E$) và đáy của nó bằng

$$E_c = 2E \sin \frac{\Delta\alpha}{2} \approx E\Delta\alpha.$$

(Ở đây chúng ta đã tận dụng độ nhỏ của góc $\Delta\alpha$ và công thức tính gần đúng $\sin \Delta\alpha \approx \Delta\alpha$).

Mặt khác, sự phân bổ điện tích mới có thể được biểu diễn dưới dạng chồng chất của hai điện tích chính xác $+\Delta q$ và $-\Delta q$, trong đó $\Delta q = \lambda R\Delta\alpha$. Trường tổng $E_c$ có thể được biểu thị thông qua hướng của các điện tích chính xác $E_{T+}$ và $E_{T-}$, trong đó

$$E_{T} = E_{T+} = E_{T-} = \frac{k\Delta q}{R^2} = \frac{k\lambda\Delta\alpha}{R}.$$

Tam giác của các vectơ chỉ phương mới cũng là tam giác đều, do đó

$$E_c = 2E_{T} \sin \frac{\alpha}{2} = 2\frac{k\lambda\Delta\alpha}{R} \sin \frac{\alpha}{2}.$$

Chúng tôi thể hiện cùng một hướng $E_c$ theo hai cách khác nhau. Do đó ta có đẳng thức

$$E\Delta\alpha = \frac{2k\lambda\Delta\alpha}{R} \sin \frac{\alpha}{2}$$

⟦folio 40⟧

---
running_head:
folio:
---

và cuối cùng tìm thấy điện áp mong muốn $E$:

$$E = \frac{2k\lambda}{R} \sin \frac{\alpha}{2}.$$

Sự thật 4 (không có bằng chứng). Các bề mặt đẳng thế của trường tĩnh điện tại mỗi điểm vuông góc với các đường thẳng của vectơ điện áp.

Sự thật 5. Bề mặt đẳng thế của một đoạn điện tích đều là một hình elip quay có tiêu điểm ở hai đầu của đoạn đó.

Bằng chứng. Chúng ta hãy tìm bề mặt đẳng thế của đoạn $AB$ đi qua một điểm tùy ý $P$ của không gian. Như chúng ta đã chứng minh, điện áp trường tĩnh điện tại điểm $P$ hướng dọc theo đường phân giác của góc $APB$ (hình 6). Bề mặt đẳng thế tại điểm này nằm vuông góc với đường phân giác. Vẫn còn phải tìm một bề mặt có tiếp tuyến tại mỗi điểm vuông góc với đường phân giác của góc chắn bởi đoạn đó.

Sự kiện 6. Tính chất quang học của hình elip (chưa được chứng minh). Nếu một tia được giải phóng khỏi một tiêu điểm của hình elip thì khi phản xạ từ bề mặt của hình elip, nó sẽ rơi vào một tiêu điểm khác (hình 7). Nói cách khác, phân giác của góc $F_1PF_2$ (trong đó $F_1, F_2$ là tiêu điểm của hình elip và $P$ là một điểm trên hình elip) trùng với pháp tuyến của bề mặt tại điểm $P$.

Sử dụng tính chất quang học của hình elip, chúng ta có thể dễ dàng kết luận rằng bề mặt đẳng thế của một đoạn tích điện đều là một hình elip hình cầu có tiêu điểm ở hai đầu của đoạn đó.

Trường quay Ellipsoid

Sự kiện 7. Định lý duy nhất (hoặc phương pháp ảnh; không có chứng minh). Giả sử có một hệ thống điện tích $\{q\} + \{q'\}$, trong đó $\{q\} = \{q_1, q_2, \ldots, q_n\}, \{q'\} = \{q'_1, q'_2, \ldots, q'_m\}$.

Chúng ta hãy vẽ nhẩm một bề mặt đẳng thế $S$ (trên đó điện thế có cùng giá trị $\varphi = \varphi_0$), chia không gian thành hai vùng: I và II. Trong các khu vực này lần lượt có các nhóm điện tích $\{q\}$ và $\{q'\}$ (hình 8).

Trường trong vùng I được xác định duy nhất bởi điện tích $\{q\}$ và giá trị tiềm năng $\varphi = \varphi_0$ tại giao diện của vùng. Nói cách khác, trường trong vùng này (và chỉ ở đây!) sẽ không thay đổi nếu hệ thống điện tích $\{q'\}$ được thay thế bằng hệ thống khác $\{q''\}$, nếu hệ thống mới này tạo ra (cùng với điện tích $\{q\}$) trên bề mặt $S$ cùng một điện thế $\varphi = \varphi_0$. Điều này có nghĩa là để tính toán trường trong vùng I, chẳng hạn, người ta có thể thay thế nhóm điện tích $\{q'\}$ của một bề mặt dẫn điện có điện thế $\varphi = \varphi_0$.

Và ngược lại, nếu có một nhóm điện tích $\{q\}$ và một bề mặt dẫn điện $S$ có điện thế $\varphi = \varphi_0$, thì để tính trường người ta có thể thay thế bề mặt này bằng một nhóm điện tích $\{q'\}$, cùng với các điện tích $\{q\}$ tạo ra điện thế cần thiết $\varphi = \varphi_0$ tại các điểm trên bề mặt $S$. Các điện tích giả định $\{q'\}$ trong trường hợp này được gọi là các điện tích được mô tả $\{q\}$ và việc thay thế bề mặt được đề xuất bằng một nhóm điện tích là phương pháp mô tả.

Bằng cách sử dụng định lý duy nhất, người ta có thể tính toán, ví dụ, lực hấp dẫn giữa một quả bóng dẫn điện và một điện tích chính xác hoặc một mặt phẳng dẫn điện vô hạn và một điện tích chính xác. Những biến chứng này khá nổi tiếng

⟦folio 41⟧

---
running_head:
folio:
---

và được mô tả trong tài liệu (ví dụ, xem bài viết “Phương pháp hình ảnh điện” của A. Chernoutsan trong «Kvant» Số 1, 1996).

Việc chứng minh định lý duy nhất ở dạng tổng quát là không thể nếu không có các giá trị của phương trình vi phân. Trong phần phụ lục của bài viết này, chúng tôi sẽ tiến hành chứng minh trong một trường hợp cụ thể, về mặt khái niệm lặp lại chứng minh của trường hợp tổng quát và dễ hiểu đối với học sinh.

Sự kiện 8. Định lý Gauss (không có chứng minh). Dòng vectơ hướng qua một bề mặt kín tùy ý $S$ bằng tổng đại số của các điện tích nằm bên trong bề mặt này, chia cho $\varepsilon_0$:

$$\Phi_E = \sum_S E_i \Delta S_i \cos \alpha_i = \frac{Q}{\varepsilon_0}.$$

Sự thật 9. Một bài toán khác cho phương pháp hình ảnh. Điện áp trường của một elip dẫn điện quay có điện tích $Q$ và khoảng cách giữa các tiêu điểm $F_1F_2 = 2L$ trong không gian bên ngoài trùng với hướng trường của một đoạn tích điện đều $F_1F_2$ có mật độ điện tích tuyến tính $\lambda = Q/(2L)$.

Bằng chứng. Hãy sử dụng thực tế 7. Bề mặt của hình elip là tương đương vì nó dẫn điện. Nếu chúng ta tìm thấy sự phân bố điện tích bên trong bề mặt $S$ mà điện thế trên bề mặt $S$ không thay đổi, thì hướng của trường bên ngoài bề mặt này sẽ không thay đổi. Trong thực tế 5, bề mặt tương đương của một đoạn tích điện đều là một elip quay có tiêu điểm ở hai đầu của đoạn đó. Để thỏa mãn các điều kiện của định lý duy nhất, vẫn phải điều chỉnh mật độ điện tích tuyến tính của đoạn $\lambda$ sao cho điện thế từ đoạn đó và điện thế từ các điện tích trên elipson dẫn điện là như nhau. Nhưng chúng ta hãy sử dụng một phương pháp khác thay vì tính điện thế của một elipson dẫn điện (và điều này thực sự khó khăn).

Chúng ta biết rằng khi xác định mật độ điện tích tuyến tính của đoạn $\lambda$ tại bất kỳ điểm nào bên ngoài hình elip, trường định hướng từ điện tích của đoạn đó và từ điện tích của chính hình elip sẽ giống nhau. Chúng ta hãy viết định lý Gauss cho một bề mặt khép kín nằm bên ngoài hình elip (hình 9) trong hai trường hợp:

$$\Phi_E^{\text{эллипсонд}} = \frac{q_{\text{эллипсонд}}}{\varepsilon_0}, \Phi_E^{\text{отрезка}} = \frac{q_{\text{отрезка}}}{\varepsilon_0}.$$

Vì hướng của trường ellipsoid và đoạn thẳng trùng nhau nên các thông lượng có hướng của vectơ cũng bằng nhau, do đó

$$q_{\text{эллипсонд}} = q_{\text{отрезка}}, \lambda = \frac{Q}{2L}.$$

Vì vậy, chúng ta đã học cách tính hướng của trường từ việc dẫn các hình elip tại bất kỳ điểm nào trong không gian. Nói chung, đây là một bài toán rất khó - xét cho cùng, chúng ta không biết các điện tích được phân bố như thế nào trên bề mặt của một elipsoid dẫn điện. Chúng tôi không biết chúng được phân phối như thế nào, nhưng chúng tôi biết chúng tạo ra lĩnh vực gì! Đây không phải là một tình huống hiếm gặp đối với tĩnh điện.

Sự thật 10. Hình học của hình elip (không có chứng minh). Chúng ta hãy xem xét một hình elip xoay có điểm cuối $a, b = c$. Vì đã biết rằng độ dài của đoạn bằng khoảng cách giữa các tiêu điểm của hình elip, nên đối với độ dài của đoạn $F_1F_2 = 2L$ mối quan hệ là hợp lệ

$$L = ae,$$

trong đó $e$ là độ lệch tâm của hình elip.

Sự thật 11. Thế năng của một elipsoid dẫn điện có điện tích $Q$, khoảng cách giữa tiêu điểm $F_1F_2 = 2L$ và độ lệch tâm $e$ được xác định bằng biểu thức

$$\varphi = \frac{kQ}{2L} \ln \frac{1+e}{1-e}.$$

Bằng chứng. Sử dụng thực tế 9, chúng ta thấy rằng chỉ cần tính toán thế năng là đủ

⟦folio 42⟧

---
running_head:
folio:
---

đoạn tích điện đều tương ứng với mật độ điện tích tuyến tính $\lambda = Q/(2L)$ tại một điểm tùy ý của hình elip. Vì chúng ta có thể chọn điểm trên bề mặt của ellipsoid mà tại đó chúng ta sẽ tự tính toán thế năng, nên việc chọn điểm thuận tiện nhất là điều đương nhiên. Xét điểm $X$ nằm trên trục chính của hình elip. Theo nguyên lý xếp chồng,

$$\varphi_X = \sum_{\text{по отрезку}} \Delta \varphi_i = \sum_{\text{по отрезку}} \frac{k \lambda \Delta r_i}{r},$$

trong đó $\Delta \varphi_i$ là điện thế được tạo ra bởi một phần nhỏ của đoạn có chiều dài $\Delta r_i$. Thật không may, số tiền này không thể tính được nếu không tích phân. Sử dụng các yếu tố của toán học cao hơn, chúng ta có được

$$\varphi_X = \sum_{\text{по отрезку}} \frac{k \lambda \Delta r_i}{r} = \int_{a-L}^{a+L} k \lambda \frac{dr}{r} = k \lambda \ln \frac{a+L}{a-L} = \frac{kQ}{2L} \ln \frac{1+e}{1-e}.$$

Cuối cùng. Năng lượng của một elipsoid dẫn điện

Cuối cùng, chúng ta đã sẵn sàng trả lời câu hỏi chính của bài viết này: năng lượng của một elipsoid dẫn chuyển động quay là bao nhiêu? Rõ ràng, năng lượng của ellipsoid bằng

$$W_{\text{эллипсоида}} = \frac{\varphi Q}{2} = \frac{kQ^2}{2L} \ln \frac{1+e}{1-e}.$$

Và nó khác với năng lượng quả cầu trong

$$\frac{W_{\text{эллипсоида}}}{W_{\text{сферы}}} = \frac{R}{2L} \ln \frac{1+e}{1-e}$$

Ứng dụng. Chứng minh định lý duy nhất trong trường hợp đơn giản

**Định lý.** Giả sử tồn tại một hệ điện tích $\{q\} + \{q'\}$, trong đó

$$\{q\} = \{q_1, q_2, \ldots, q_n\}, \{q'\} = \{q'_1, q'_2, \ldots, q'_m\}.$$

Chúng ta hãy vẽ nhẩm một bề mặt đẳng thế khép kín $S$ (trên đó điện thế có cùng giá trị $\varphi = \varphi_0$), chia không gian thành hai vùng: I và II. Ở những khu vực này có các nhóm điện tích $\{q\}$ và $\{q'\}$ tương ứng (xem hình 8). Trường trong vùng chỉ được xác định bởi điện thế biên $S$ và điện tích $\{q'\}$ trong vùng này. Và ngược lại, nếu có một nhóm điện tích $\{q\}$ và một bề mặt dẫn điện $S$ có điện thế $\varphi = \varphi_0$, thì để tính trường người ta có thể thay thế bề mặt này bằng một nhóm điện tích $\{q'\}$, cùng với các điện tích $\{q\}$ tạo ra điện thế cần thiết $\varphi = \varphi_0$ tại các điểm trên bề mặt $S$. Các điện tích hư cấu $\{q'\}$ trong trường hợp này được gọi là hình ảnh của các điện tích $\{q\}$.

**Bổ đề.** Nếu không có điện tích bên trong một bề mặt đẳng thế kín thì trường bên trong bề mặt này bằng không.

**Chứng minh bổ đề.** Giả sử điều ngược lại. Giả sử có một điểm bên trong bề mặt mà hướng của trường khác 0. Do đó, cũng có một đường hợp nhất đi qua điểm này. Nhưng đường hợp nhất này không thể bắt đầu và kết thúc bên trong bề mặt này - không có điện tích ở đó. Điều này có nghĩa là nó chỉ có thể vượt qua bề mặt này. Nhưng nếu nó cắt các bề mặt, thì chúng ta sẽ xem xét công di chuyển một điện tích chính xác dọc theo một đường viền khép kín: chúng ta sẽ đi dọc theo đường mận (ở đó điện trường thực hiện một công), và sau đó chúng ta sẽ đóng đường viền bằng cách đi dọc theo bề mặt đẳng thế (công của điện trường trong phần này bằng không). Chúng ta đã tìm thấy một mạch kín, công của điện trường không bằng 0 - mâu thuẫn với các điều kiện về thế năng của trường.

**Chứng minh định lý.** Hãy chứng minh rằng nếu chúng ta lấy một phân bố khác của các điện tích nhiễu $\{Q'\}$, giữ nguyên điện thế bề mặt $S$, thì trường trong vùng P sẽ không thay đổi.

Giả sử có hai phân bố điện tích: $\{q\} + \{q'\}$ và $\{q\} + \{Q'\}$, được tạo bởi cùng một bề mặt đẳng thế $S$ có ​​điện thế $\varphi = \varphi_0$. Chúng ta hãy trừ đi phần thứ hai từ phân bố điện tích đầu tiên, tức là xem xét phân bố

$$\left(\{q\} + \{q'\}\right) - \left(\{q\} + \{Q'\}\right).$$

Rõ ràng là khi nhân tất cả các điện tích với $(-1)$, hướng trường tại mỗi điểm trong không gian vẫn giữ nguyên theo mô hình, nhưng hướng thay đổi ngược lại. Lưu ý rằng bề mặt $S$ vẫn duy trì trạng thái đẳng thế (hơn nữa, điện thế trên nó bằng 0). Không có điện tích bên trong bề mặt này, vì vậy hướng của trường bên trong nó bằng không. Do đó, hướng tại mỗi điểm bên trong từ sự phân bố điện tích thứ nhất $\left(\{q\} + \{q'\}\right)$ trùng với hướng từ trường từ sự phân bố điện tích thứ hai $\{q\} + \{Q'\}$, đó là điều cần phải được chứng minh.
