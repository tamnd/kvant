---
id: 1990-12-gisin-chertezhnik-risuet-kvadrat-9fb93722
issue: kvant_1990_12
year: 1990
number: "12"
title: Người vẽ phác thảo vẽ một hình vuông
authors:
  - Гисин В. Б.
rubric: osnovnye-stati
page_first: 16
page_last: 19
page_labels: 14-17
lang: vi
source: kvant_digital
extraction: vision
content_sha256: 066912874351aeb2a8285700b3fbdc1304c53392e8554bc3ded35876ad3e7869
prompt_sha256: draft-1
translated_from: content/ru/1990/12/articles/04_gisin-chertezhnik-risuet-kvadrat-9fb93722.md
source_content_sha256: 60165098a7ac3335f24c3c4dea4c50bf251595bfb63dfc42a90609240edb430d
translation_model: draft
translation_run: vi-draft-gaps-2026-11-06
translation_quality: draft
---

⟦folio 14⟧

---
running_head:
folio:
---

ĐẾN ĐIỂM X
THẤP HƠN
LÔNG VŨ!
THANG MÁY
LÔNG VŨ!
nghĩa là
TRÊN
Vectơ
Tishkov

14

⟦folio 15⟧

---
running_head:
folio:
---

người soạn thảo
VẼ MỘT VUÔNG

Ứng viên Khoa học Vật lý và Toán học
V. GISIN

Đôi khi bài toán tưởng chừng như rất đơn giản trong khoa học máy tính lại dẫn đến những vấn đề toán học thú vị. Chúng ta sẽ xem xét một bài toán như vậy từ sách giáo khoa khoa học máy tính do A. P. Ershov (1988) biên tập.

Đầu tiên, chúng ta hãy nhớ lại mô tả về Draftsman - một thiết bị được thiết kế để vẽ đồ thị hình trên mặt phẳng tọa độ. Người soạn thảo có một cây bút có thể di chuyển dọc theo mặt phẳng. Nếu bút hạ xuống, nó sẽ để lại dấu vết. Người soạn thảo có thể thực hiện 4 lệnh: “nâng bút”, “hạ bút”, “di chuyển đến điểm $(x; y)$”, “di chuyển đến vector $(d_x; d_y)$”. Tọa độ các điểm và vectơ trong lệnh của Draftsman được viết dưới dạng phân số thập phân hữu hạn. Người ta tin rằng trước khi người phác thảo bắt đầu làm việc, mặt phẳng sẽ sạch sẽ, bút được nâng lên và nằm ở gốc tọa độ. Để nhận được hình bạn cần đưa cho Người soạn thảo một loạt lệnh. Ví dụ: nếu bạn ra lệnh:

di chuyển đến điểm $(1; 1)$; hạ bút xuống; dịch chuyển theo vectơ $(0; -2)$; dịch chuyển theo vectơ $(-2; 0)$; dịch chuyển theo vectơ $(0; 2)$; dịch chuyển theo vectơ $(2; 0)$; giơ bút lên

thì sau khi thực hiện, một hình vuông sẽ được vẽ từ cạnh 2 và tâm ở gốc (vấn đề 1 trong §4). Một câu hỏi tự nhiên được đặt ra: Người vẽ phác thảo có thể vẽ bất kỳ hình vuông nào có cạnh 2 và tâm ở gốc tọa độ không trùng với hình vuông của chúng ta không?

Rõ ràng là tọa độ các đỉnh của bất kỳ hình vuông nào như vậy đều được biểu thị bằng phân số thập phân hữu hạn. Ngược lại, nếu tọa độ của ít nhất một đỉnh của hình vuông có tâm tại gốc tọa độ là phân số thập phân hữu hạn (ví dụ: $(x; y)$), thì tọa độ của các đỉnh còn lại (cụ thể là $(x; y)$, $(-y; x)$, $(-x; -y)$, $(y; -x)$) và tọa độ của tất cả các vectơ bên (cụ thể là $(-x - y; x - y)$, $(-x + y; -x - y)$, $(x + y; -x + y)$, $(x - y; x + y)$) - hình 1. Tương tự, nếu ít nhất một trong bốn vectơ của chúng ta có tọa độ thập phân hữu hạn, thì các vectơ còn lại và tất cả các đỉnh đều có tọa độ thập phân hữu hạn. Do đó, một hình vuông có tâm tại gốc tọa độ có thể được xây dựng bằng cách sử dụng Draftsman của chúng tôi khi và chỉ khi ít nhất một trong các đỉnh của nó hoặc ít nhất một vectơ các cạnh của nó có tọa độ là phân số thập phân hữu hạn.

Sẽ thuận tiện hơn cho chúng ta khi xem xét không phải vectơ mà là một nửa số vectơ. Nếu cạnh của hình vuông bằng 2 thì nửa của nó bằng 1. Do đó, sao cho tất cả các hình vuông là nghiệm của bài toán của chúng ta

Hình 1.

⟦folio 16⟧

---
running_head:
folio:
---

chúng ta chỉ cần tìm tất cả các cặp số thập phân hữu hạn $(a; b)$ mà $a^2 + b^2 = 1$. Một cách khác là tìm tất cả các điểm của đường tròn đơn vị có tâm là gốc tọa độ của chúng là phân số thập phân hữu hạn.

Bốn điểm như vậy có thể nhìn thấy ngay lập tức: $(\pm 1; 0)$ và $(0; \pm 1)$. Nhưng chúng tương ứng với hình vuông của chúng tôi. Có cái gì khác không? Có, ví dụ: $a = 0,6$, $b = 0,8$ (hoặc $a = \pm 0,6$, $b = \pm 0,8$ hoặc $a = \pm 0,8$, $b = \pm 0,6$). Còn gì nữa? Còn nhiều hơn thế nữa, như lý luận hình học đơn giản cho thấy.

Tọa độ của một điểm tùy ý trên đường tròn của chúng ta là $(\cos \varphi; \sin \varphi)$, trong đó $\varphi$ là góc giữa hướng dương của trục $OX$ và vectơ bán kính của điểm của chúng ta, không phải ngược chiều kim đồng hồ. Điều này có nghĩa là chúng ta muốn tìm tất cả các góc $\varphi$ mà $\cos \varphi$ và $\sin \varphi$ là số thập phân hữu hạn. Bây giờ chúng ta cũng có các góc thập phân.

Bổ đề. Nếu $\varphi_1$ và $\varphi_2$ là các góc thập phân thì $\varphi_1 + \varphi_2$ và $\varphi_1 - \varphi_2$ cũng là các góc thập phân.

Bằng chứng. Điều này được thấy rõ ngay từ các công thức $\cos(\varphi_1 \pm \varphi_2) = \cos \varphi_1 \cos \varphi_2 - \sin \varphi_1 \sin \varphi_2$, $\sin(\varphi_1 \pm \varphi_2) = \sin \varphi_1 \cos \varphi_2 \pm \cos \varphi_1 \sin \varphi_2$.

Kết quả. Nếu $\varphi_1$ và $\varphi_2$ là các góc thập phân thì $k_1 \varphi_1 + k_2 \varphi_2$ là góc thập phân của mọi số nguyên $k_1$ và $k_2$.

Điểm $(0,6; 0,8)$ tương ứng với góc $\varphi_0$, trong đó $\cos \varphi_0 = 0,6$, $\sin \varphi_0 = 0,8$. Góc $\varphi_0$ là số thập phân. Nhưng theo những gì đã được chứng minh thì $2\varphi_0$ cũng là một góc thập phân. Theo các công thức nổi tiếng $\cos 2\varphi_0 = 0,6^2 - 0,8^2 = -0,28$, $\sin 2\varphi_0 = 2 \cdot 0,6 \cdot 0,8 = 0,96$. Vì vậy, đây là một cách tiếp cận khác đối với điểm vòng tròn: $(-0,28; 0,96)$. Hoặc bạn có thể lấy $(0,28; 0,96)$ và nói chung là $(\pm 0,28; \pm 0,96)$ hoặc $(\pm 0,96; \pm 0,28)$. Bạn cũng có thể lấy $3\varphi_0$, $4\varphi_0$, ... Vậy thì đừng quên điểm $(\pm 1; 0)$ và $(0; \pm 1)$. Chúng tương ứng với các góc $0, \frac{\pi}{2}, \pi, \frac{3\pi}{2}$, tức là các góc $\frac{l\pi}{2}$ với $l = 0,1,2,3$. Điều này có nghĩa là chúng ta biết khối lượng của các góc thập phân: đây đều là các góc

$k\varphi_0 + \frac{l\pi}{2}$ (*)

với bất kỳ số nguyên nào $k$ và $l = 0,1,2,3$ (bạn có thể nói “với bất kỳ số nguyên nào $l$”, nhưng nếu $l$ được thay đổi thành 4, góc sẽ thay đổi thành $2\pi$, tức là nó sẽ cho cùng một góc quay). Nhưng có lẽ đó không phải là tất cả? Không, chỉ vậy thôi. Chúng ta cũng sẽ xem xét định lý.

Định lý 1. Mọi góc thập phân đều có dạng (*) và mọi góc (*) ($c l = 0,1,2,3$) phân biệt.

Chúng ta sẽ chứng minh định lý này sau một chút. Bây giờ hãy lưu ý rằng các hình vuông mà Người soạn thảo của chúng tôi có thể xây dựng được lấy từ hình vuông được mô tả ở đầu chỉ số, bằng cách xoay theo các góc thập phân $\varphi$ xung quanh điểm gốc. hình 2 hiển thị các hình vuông được hình thành bởi trung điểm của các cạnh của hình vuông ban đầu và hình vuông được xoay. Các vectơ đơn vị đi từ gốc đến đỉnh của chúng là phần mười. Ngoài ra, vì quay một vectơ qua một góc $\pi/2$ sẽ biến mọi hình vuông thành chính nó nên định lý sau đây đúng.

Định lý 2. Các hình vuông có cạnh 2 và tâm ở gốc tọa độ, có thể dựng bằng Draftsman, là các hình vuông thu được từ hình vuông tương tự thứ nhất bằng cách quay theo hướng này hay hướng khác một góc $\varphi_0, 2\varphi_0, 3\varphi_0$, ... Tất cả các hình vuông này đều khác nhau.

⟦folio 17⟧

---
running_head:
folio:
---

(Hãy nhớ rằng phép quay qua một góc - φ là phép quay qua một góc φ theo hướng ngược lại.)
Bây giờ chúng ta sẽ tiếp tục từ các bài toán vẽ và chuyển sang chứng minh Định lý 1.
Chứng minh Định lý 1.
Đặt $\alpha$ là góc thập phân và đặt $\cos \alpha = A/10^n$, $\sin \alpha = B/10^n$, trong đó $A$ và $B$ là số nguyên. Sau đó
$$\left(\frac{A}{10^n}\right)^2 + \left(\frac{B}{10^n}\right)^2 = 1, A^2 + B^2 = (10^n)^2 = 10^{2n}.$$
Chúng ta hãy biểu thị bằng $C$ ước số chung nhất của các số $A, B$ và $10^n$ và đặt $a = A/C, b = B/C$; chúng tôi có:
$$a^2 + b^2 = (10^n/C)^2.$$
Số $10^n/C$ phải là số lẻ, nghĩa là nó là lũy thừa của năm. Thật vậy, nếu $10^n/C$ chẵn thì $a$ và $b$ không thể cùng chẵn; nhưng nếu một trong số chúng là số chẵn và số còn lại là số lẻ thì tổng $a^2 + b^2$ là số lẻ và với nó là $10^n/C$ là số lẻ, nhưng nếu $a$ và $b$ đều là số lẻ thì tổng $a^2$ và $b^2$ sẽ có số dư là 1 khi chia cho 4, trái với thực tế là số $(10^n/C)^2$ là số chẵn, phải là chia hết cho 4.
Vì vậy chúng ta phải giải các phương trình theo số nguyên
$$a^2 + b^2 = 5^{2m}.$$
Mục tiêu của chúng tôi là chứng minh rằng lời giải này đầy đủ những điều sau:
$$a = 5^m \cos \alpha, b = 5^m \sin \alpha,$$
trong đó $\alpha = k \varphi_0 + \frac{l \pi}{2}$ (và $m$ là số nguyên sao cho $a$ và $b$ là số nguyên). Nói cách khác,
$$a = 5^m \cos \left(k \varphi_0 + \frac{l \pi}{2}\right) = \left\{ \begin{array}{l} \text{или } \pm 5^m \cos \left(\pm k \varphi_0\right), \\ \text{или } \pm 5^m \sin \left(\pm k \varphi_0\right) \end{array} \right.$$
và tương tự cho $b$.
Giả sử rằng với $m < m_0$ tất cả số nguyên lời giải của phương trình của chúng ta có dạng được chỉ định. Lấy các phương trình lời giải $a, b$
$$a^2 + b^2 = 5^{2m}.$$
Chúng ta có thể giả sử rằng $a$ và $b$ không bị khử
chia hết cho 5 (nếu $a$ chia hết cho 5 thì $b$ cũng chia hết cho 5 và khi đó $a' = a/5, b' = b/5$ là lời giải có phương trình tương tự với $5^{2(m-1)}$ thay vì $5^{2m}$ và nó có dạng mong muốn theo giả định). Hãy viết lời giải của chúng ta thành $a = 5^m \cdot \cos \alpha, b = 5^m \cdot \sin \alpha$ và xem xét các số $3a + 4b, 3a - 4b$. Tích số $9a^2 - 16b^2 = 9(a^2 + b^2) - 25b^2 = 9 \cdot 5^{2m} - 25b^2$ của họ chia hết cho $5^2$ và không chia hết cho $5^3$; tổng của chúng $6a$ không chia hết cho 5. Điều này có nghĩa là một trong những số này, dùng $3a + 4b$ để xác định số này, sẽ chia hết cho $5^2$. Hãy đặt $a' = \frac{3a + 4b}{5^2}$. Đây là một số nguyên không chia hết cho 5. Hãy đặt $b' = a + b - 7a' = \frac{4a - 3b}{5^2}$. Sau đó
$$(a')^2 + (b')^2 = \frac{9a^2 + 12ab + 16b^2 + 16a^2 - 12ab + 9b^2}{5^4} = \frac{25(a^2 + b^2)}{5^4} = 5^{2m+2-4} = 5^{2(m-1)}.$$
Điều này có nghĩa là các phương trình $a'$, $b'$ - lời giải có ​​dạng của chúng ta với $5^{2(m-1)}$ thay vì $5^{2m}$, tức là.
$$a' = 5^{m-1} \cos \beta, b' = 5^{m-1} \sin \beta,$$
trong đó $\beta$ có dạng $q \varphi_0 + \frac{r \pi}{2}, r = 0, 1, 2, 3.$
Nhưng đồng thời
$$a' = \frac{3a + 4b}{5^2} = 5^{m-1} \cdot \left(\frac{3}{5} \cos \alpha + \frac{4}{5} \sin \alpha\right) = 5^{m-1} (\cos \varphi_0 \cos \alpha + \sin \varphi_0 \sin \alpha) = 5^{m-1} \cos (\alpha - \varphi_0)$$
và, tương tự,
$$b' = 5^{m-1} \sin (\alpha - \varphi_0).$$
Điều này có nghĩa là $\beta = \alpha - \varphi_0, \alpha = \beta + \varphi_0$ và lời giải của chúng tôi cũng có biểu mẫu được yêu cầu. Định lý đã được chứng minh.

Bài tập. Hãy giới thiệu một hạn chế bổ sung về hình thức lệnh của Người soạn thảo: mục nhập số không được chứa quá năm chữ số có nghĩa (các số 0 liên tiếp ở bên trái và bên phải không được tính). Xác định có bao nhiêu hình vuông có cạnh 2 và tâm ở gốc tọa độ có thể bị Người soạn thảo vi phạm.
