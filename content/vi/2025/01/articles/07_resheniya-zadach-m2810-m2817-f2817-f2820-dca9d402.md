---
id: 2025-1-resheniya-zadach-m2810-m2817-f2817-f2820-dca9d402
issue: kvant_2025_1
year: 2025
number: "1"
title: Lời giải bài toán M2810—M2817; F2817—F2820
rubric: zadachnik-kvanta
rubric_sub: Задачник «Кванта»
page_first: 25
page_last: 34
page_labels: 24, 25, 27, 28, 30, 31, 32
lang: vi
source: kvant_digital
extraction: vision
content_sha256: e0a07c7b4c77322b6b97a4353a878af421e94e20f335071d867e806913ba133e
prompt_sha256: draft-1
translated_from: content/ru/2025/01/articles/07_resheniya-zadach-m2810-m2817-f2817-f2820-dca9d402.md
source_content_sha256: 57a5772499d92f4cb5a3365fdf933bdccb392d7ca115c64a64b8592dbd2a349e
translation_model: draft
translation_run: vi-draft-gaps-2026-11-03
translation_quality: draft
---

⟦folio none⟧

Lời giải bài toán M2810 – M2817, F2817–F2820

M2810. Cho một số tự nhiên $n \geq 2$. Có bao nhiêu cách sơn các đầu cuối của hình vuông $n \times n$ trong khung màu hoa anh túc sao cho hai đầu cuối bất kỳ có một cạnh hoặc một đỉnh chung đều được sơn bằng các màu khác nhau?

Đáp số: $3 \cdot 2^{n+2} - 24$.

Trường hợp 1. Ở dòng đầu tiên có các đầu cuối chỉ có hai màu, chẳng hạn (không mất tính tổng quát), 1 và 2. Sau đó, ở dòng thứ hai, màu 3 và 4 phải xuất hiện, ở dòng thứ ba, màu 1 và 2 lại xuất hiện, v.v. Trong trường hợp này, tất cả các màu được chỉ định đều phù hợp. Để xác định duy nhất cách tô màu như vậy, chúng tôi chọn một trong 6 cặp màu có thể xuất hiện ở dòng đầu tiên (qua đó, một cặp màu cụ thể cho mỗi dòng) và trong mỗi dòng, chúng tôi chọn một trong hai thứ tự màu có thể có. Tổng cộng $6 \cdot 2^n = 3 \cdot 2^{n+1}$ cách.

Trường hợp 2. Giả sử ở dòng đầu tiên có ít nhất 3 màu khác nhau, chẳng hạn (không mất tính tổng quát), 1, 2, 3. Giả sử màu 3 xuất hiện lần đầu muộn hơn màu 1 và 2 (đếm vết). Khoảng cách là khoảnh khắc đầu tiên như vậy. Sau đó, hai thiết bị đầu cuối ở bên trái của nó được hiển thị bằng các màu khác nhau. Do đó, chúng tôi đã tìm thấy ba thiết bị đầu cuối liên tiếp, được hiển thị bằng các màu khác nhau: không mất tính tổng quát, 1, 2, 3 - theo thứ tự đó (hình 1). Do đó, ở dòng tiếp theo, dưới đầu cuối màu 2 chỉ có thể có đầu cuối màu 4, nghĩa là ở bên phải của nó có đầu cuối màu 1, và ở bên trái có đầu cuối màu 3. Sau đó ở dòng thứ ba trên

⟦folio 24⟧

---
running_head:
folio:
---

ở ba vị trí giống nhau có các ô màu 1, 2, 3 (theo thứ tự đó). Điều này lấp đầy duy nhất ba cột liên tiếp. Hơn nữa, di chuyển từ ba cột này sang trái và phải, chúng tôi hiểu rằng theo dòng thứ hai, cột thứ nhất và thứ ba được khôi phục theo cùng một cách. Vì vậy, chúng tôi đã chứng minh rằng theo giả định của chúng tôi, dòng đầu tiên và dòng thứ ba có màu giống nhau. Tương tự, nó cho thấy tất cả các dòng có bốn số đều được tô màu giống nhau và tất cả các dòng có số lẻ đều được tô màu giống nhau. Khi đó, việc chúng tôi (tức là tùy thuộc vào các điều kiện) chỉ định màu của hai hàng đầu tiên là hoàn toàn chính xác, sao cho ở hàng đầu tiên (và sau đó ở hàng thứ hai) có các ô có ít nhất 3 màu. Đầu tiên chúng ta hãy đếm xem có bao nhiêu cách tô đúng hai đường thẳng bằng 4 màu. Trước tiên, hãy tô màu cột đầu tiên của hai ô - việc này có thể được thực hiện theo 12 cách, sau đó đối với mỗi cột tiếp theo, một tập hợp hai màu của các ô của nó sẽ được xác định duy nhất và cột này có thể được vẽ theo 2 cách. Tổng cộng $12 \cdot 2^{n-1} = 3 \cdot 2^{n+1}$ cách. Hãy trừ số cách "phụ" - trong đó ít nhất một trong các dòng (trên thực tế là cả hai) chứa đúng 2 màu khác nhau; sẽ có $6 \cdot 2^2 = 24$ các phương pháp như vậy (cách tính tương tự trường hợp 1). Tổng cộng, trong trường hợp thứ hai, chúng ta nhận được các phương thức $3 \cdot 2^{n+1} - 24$. Tổng hợp các phương thức từ trường hợp thứ nhất và thứ hai, chúng ta nhận được các phương thức $2 \cdot 3 \cdot 2^{n+1} - 24 = 3 \cdot 2^{n+2} - 24$.

I. Efremov

M2811. Liên tiếp các số tự nhiên $a_1, a_2, \dots, a_{100}$ là Poppy, $a_1 = 1$ và mọi số tự nhiên $n = 1, 2, \dots, 100$ ($a_1 + a_2 + \dots + a_n$) ($\frac{1}{a_1} + \frac{1}{a_2} + \dots + \frac{1}{a_n}$) là số nguyên. Giá trị quan trọng nhất mà $a_{100}$ có thể nhận là gì?

Đáp số: $2^{98}$.

Ví dụ: $a_1 = 1, a_2 = 1, a_3 = 2, a_4 = 2^2, a_5 = 2^3, \dots, a_{100} = 2^{98}$.

Cấp. Hãy chứng minh rằng $a_i$ là ước của $s_{i-1} = a_1 + \dots + a_{i-1}$ với mọi $i$. Điều này sẽ là đủ. Thật vậy, bằng cách chỉ ra trên $i$ chúng ta chứng minh một cặp ước lượng $s_{i-1} \leq 2^{i-2}, a_i \leq 2^{i-2}$ cho $i \geq 2$. Chuyển đổi $i \rightarrow i+1$ diễn ra như thế này:

$s_i \leq s_{i-1} + a_i \leq s_{i-1} + s_{i-1} \leq 2^{i-2} + 2^{i-2} = 2^{i-1}; a_{i+1} \leq s_i \leq 2^{i-1}$.

Vì vậy, hãy chứng minh điều đó.

Theo số lượng

$$l = \left(a_1 + \dots + a_i\right)\left(\frac{1}{a_1} + \dots + \frac{1}{a_i}\right)$$

Và

$$k = \left(a_1 + \dots + a_{i-1}\right)\left(\frac{1}{a_1} + \dots + \frac{1}{a_{i-1}}\right)$$

là toàn bộ. Sau đó số

$$l - k - 1 = a_i\left(\frac{1}{a_1} + \dots + \frac{1}{a_{i-1}}\right) + \left(a_1 + \dots + a_{i-1}\right)\frac{1}{a_i}$$

- trọn. Chúng ta hãy nhìn vào hai số hạng ở vế phải của đẳng thức này:

$$\alpha = a_i\left(\frac{1}{a_1} + \dots + \frac{1}{a_{i-1}}\right) \text{ и } \beta = \left(a_1 + \dots + a_{i-1}\right)\frac{1}{a_i}.$$

Các số $\alpha$ và $\beta$ là số hữu tỷ và tổng $\alpha + \beta$ là số nguyên. Điều này có nghĩa là các phân số $\alpha$ và $\beta$ có cùng mẫu số (tự nhiên) trong ký hiệu tối giản. Hơn nữa, nếu các mẫu số này lớn hơn 1 thì tích $\alpha \beta$ sẽ không phải là số nguyên, nhưng đối với chúng ta $\alpha \beta = k$ là số nguyên. Điều này có nghĩa là mẫu số trong ký hiệu tối giản của phân số $\alpha$ và $\beta$ bằng 1, tức là $\alpha$ và $\beta$ là số nguyên. Nhưng phần này kết thúc bằng lời giải, vì chúng ta cần chỉ ra rằng $\beta = \left(a_1 + \dots + a_{i-1}\right)\frac{1}{a_i} - \text{ целое число}.$

M. Turevsky

M2812. Trên mặt phẳng tọa độ, tại một số điểm có tọa độ nguyên có một viên sỏi (có rất nhiều viên sỏi). Cho phép phân chia nước đi: chọn một cặp viên sỏi, lấy một số vectơ $\vec{a}$ có tọa độ nguyên, sau đó một trong những viên sỏi đã chọn được đưa vào vectơ $\vec{a}$, và viên còn lại vào vectơ đối diện $\vec{-a}$; Trong trường hợp này, không được phép có nhiều hơn một viên sỏi ở cùng một điểm. Có phải nó luôn luôn

⟦folio 25⟧

---
running_head:
folio:
---

bạn có thể đạt được một số tiền trong một vài nước đi
ation trong đó tất cả các viên sỏi nằm trên
một đường thẳng?

Đáp số: luôn luôn.
Đặt $(x_1, y_1), (x_2, y_2), \ldots, (x_n, y_n)$ là số ban đầu
ny tọa độ của các viên sỏi và để $(x_0, y_0) =
\frac{x_1 + x_2 + \ldots + x_n}{n}, \frac{y_1 + y_2 + \ldots + y_n}{n}$ –
tọa độ khối tâm của chúng.
Xét đường thẳng $l$ đi qua
điểm $(x_0, y_0)$, trên đó có vô hạn
một số nút nhất định (tức là các điểm có số nguyên
tọa độ). Có một đường thẳng như vậy $l$.
Thật vậy, nếu $(x_0, y_0) \neq (0, 0)$ thì
đường thẳng phù hợp $y_0 x = x_0 y$ – họ nằm trên đó
các nút có dạng $(mnx_0, mny_0)$, trong đó $m \in \mathbb{Z}$; nếu như
$(x_0, y_0) = (0, 0)$, thì thẳng $y = 0$ sẽ được.
Hãy di chuyển với viên đá thứ 1 và $n$ như thế này:
để viên sỏi thứ nhất chạm vào một số
nút trực tiếp không có người ở $l$. (Lưu ý rằng
nước đi này có thể được thực hiện: nếu cam thứ nhất-
viên sỏi chạm vào nút $A$, sau đó là viên sỏi thứ $n$
sẽ nhấn nút $A'$, đối xứng $A$ so với điểm giữa của đoạn giữa vị trí số 1 và $n$-thứ đá để di chuyển; vì khả năng chọn nút $A$ vô số, thì đối với một số trong số đó là nút tương ứng $A'$ sẽ trống.) Hãy thực hiện các động tác tương tự với quân thứ 2 và $n$- viên sỏi thứ 3 và $n$-m sỏi, ..., với $(n-1)$-m và $n$-m sỏi.
Bây giờ tất cả các viên đá, có lẽ ngoại trừ $n$, đều nằm trên đường thẳng $l$. Nhưng lưu ý rằng trong quá trình thực hiện các động tác, khối tâm của các viên đá $(x_0, y_0)$ không thay đổi và nằm trên đường thẳng $l$ (theo lựa chọn của chúng ta $l$). Nhưng từ đó viên đá thứ $n$ còn lại cũng nằm trên $l$.
K. Ivanov, P. Kozhevnikov

M2813*. Tam giác ABCD được mô tả như thế nào xung quanh một đường tròn có tâm $I$ (hình 1). Các đường trung trực của các đoạn $AC$ và $BD$ cắt nhau tại điểm $P$. Các đường tròn ngoại tiếp tam giác $APC$ và $BPD$ cắt nhau tại các điểm $P$ và $Q$. Chứng minh rằng $I$ nằm trên đường thẳng $PQ$.

Đầu tiên, chúng tôi sẽ trình bày lời giải, được phát minh bởi I. Bogdanov. Lời giải hình học

⟦folio 27⟧

---
running_head:
folio:
---

Để kết luận, chúng tôi sẽ trả lời rằng tuyên bố của chúng tôi có thể được chứng minh bằng các phương pháp khác. Có một chứng minh ngắn gọn sử dụng định lý co rút kép của Desargues. Một cách tiếp cận khác là xét tứ giác của chúng ta tập hợp các điểm $X$ có tính chất (*). Hóa ra tập hợp này là một đường cong bậc ba - còn được gọi là khối tiêu điểm. Khối lập phương này có nhiều đặc tính thú vị và đẹp mắt; tuyên bố của chúng tôi cũng có thể được suy ra từ họ.

Chan Kuang Hung, P. Kozhevnikov

M2814. Các số dương $a, b, c$ sao cho $b + c = a^2$. Tìm ý nghĩa của biểu thức

$$\frac{\sqrt{a + \sqrt{b}} + \sqrt{a + \sqrt{c}}}{\sqrt{a - \sqrt{b}} + \sqrt{a - \sqrt{c}}}.$$

Đáp số: $\sqrt{2} + 1$.

Chúng ta hãy sử dụng công thức nổi tiếng để chuyển đổi căn thức kép (có thể dễ dàng chứng minh bằng cách bình phương). Theo ký hiệu của chúng tôi, tức là có tính đến đẳng thức $c = a^2 - b$, công thức này có dạng

$$\sqrt{a + \sqrt{b}} = \frac{1}{\sqrt{2}} \left( \sqrt{a + \sqrt{c}} + \sqrt{a - \sqrt{c}} \right),$$

hoặc

$$\sqrt{a + \sqrt{c}} + \sqrt{a - \sqrt{c}} = \sqrt{2} \cdot \sqrt{a + \sqrt{b}}.$$ (1)

Tương tự (lưu ý rằng $b$ và $c$ tương đương trong lý luận của chúng tôi):

$$\sqrt{a + \sqrt{b}} + \sqrt{a - \sqrt{b}} = \sqrt{2} \cdot \sqrt{a + \sqrt{c}}.$$ (2)

Chúng ta hãy biểu thị $X = \sqrt{a + \sqrt{b}} + \sqrt{a + \sqrt{c}}$ và $Y = \sqrt{a - \sqrt{b}} + \sqrt{a - \sqrt{c}}$, sao cho $\frac{X}{Y}$ là biểu thức chúng ta cần. Thêm (1) và (2), chúng ta có $X + Y = \sqrt{2}X$, đã mở $\frac{X}{Y} + 1 = \sqrt{2} \frac{X}{Y}$ và $\frac{X}{Y} = \frac{1}{\sqrt{2} - 1} = \sqrt{2} + 1$.

P. Kozhevnikov

M2815. Có một bộ xi măng 2n funk $n$ khác nhau, mỗi loại xi măng có hai funk. Các chức năng được sắp xếp ngẫu nhiên trong một hàng. Chứng minh rằng xác suất để trong một hàng có hai hàm số liền kề của cùng một loại xi măng lớn hơn 1/2.

Chúng ta hãy xem xét tất cả các chuỗi $2n$ funkki $n$ các tsemet khác nhau có thể có, hai funkki của mỗi tsemet. Chúng tôi sẽ gọi một chuỗi là *không thành công* nếu nó không chứa hai funkek liên kết đơn liền kề. Chúng tôi coi các hàng còn lại là *thành công*. Ta cần chứng minh số hàng không thành công nhỏ hơn số hàng funkecks và cặp này không nằm ở hai vị trí đầu tiên.

Hãy thực hiện một hàng không thành công. Đặt hàm đầu tiên có màu $A$. Hãy tìm hàm thứ hai $A$, đặt nó ở vị trí thứ $k$ ($k \geq 3$, vì chuỗi của chúng ta không thành công). Chúng ta hãy sắp xếp lại $k-1$ funkek đầu tiên trong chu trình sao cho hai hàm màu $A$ liền kề nhau. (Ví dụ: $ABCBDADC \rightarrow BCBDAADC$, $ABACDBDC \rightarrow BAACDBDC$, v.v.) Sau này, chúng ta có một chuỗi thú vị trong đó có chính xác một cặp hàm màu liền kề $A$. Vì vậy, chúng tôi đã ghép từng bộ truyện không thành công bằng một bộ truyện thú vị. Trong trường hợp này, bằng cách sử dụng một chuỗi thú vị, người ta có thể tái tạo lại một cách rõ ràng chuỗi không thành công mà nó được so sánh: cụ thể là, người ta có thể tìm thấy một cặp hàm lân cận một liên kết (một vách) và di chuyển chuỗi bên trái đến vị trí đầu tiên (bằng cách dịch chuyển các hàm còn lại dọc theo chu trình).

Vì vậy, có nhiều hàng không thành công cũng như có nhiều hàng thú vị. Nhưng rất, có những chuỗi đáng ngạc nhiên không thú vị, chẳng hạn như chuỗi có dạng $AA$... Như vậy, số lượng chuỗi không thành công hoàn toàn ít hơn số lượng hàm trong chu trình).

A. Antropov, P. Kozhevnikov

M2816. Với số tự nhiên nào $m$, người ta có thể chọn số tự nhiên $l$ sao cho tổng $n + n^2 + n^3 + \ldots + n^l$ chia hết cho $m$ với mọi số tự nhiên $n$.

Đáp số: cho $m$ không có hình vuông, tức là các số nguyên tố không chia hết cho hình vuông. Rõ ràng $m = 1$ là tốt.

Nếu $m$ chia hết cho $p^2$ đối với một số nguyên tố $p$, thì $m$ như vậy là không phù hợp. Thật vậy, đối với $n = p$ tổng được biểu thị bằng $p + p^2 (1 + p + \ldots)$; chúng tôi thấy rằng cô ấy không chia sẻ

⟦folio 28⟧

---
running_head:
folio:
---

cho $p^2$ và do đó không chia hết cho $m$.
Bây giờ, giả sử $m$ thoát khỏi hình vuông và $p$ là ước số nguyên tố của nó. Khi $n \div p$ được chỉ định trong điều kiện, số tiền được chia cho $p$.
Nếu $n \equiv 1 (\bmod p)$ thì $n + n^2 + n^3 + \ldots + n^l \equiv l (\bmod p)$, nghĩa là khả năng chia hết cho $p$ sẽ được thỏa mãn đối với $l$, bội số của $p$. Tiếp theo, cho $n$ có số dư khác 0 và 1 khi chia cho $p$. Chúng tôi có $n + n^2 + n^3 + \ldots + n^l = n \cdot \frac{n^l - 1}{n - 1}$; chúng ta thấy (vì $n$ và mẫu số $n - 1$ không chia hết cho $p$) nên tổng chia hết cho $p$ nếu $n^l$ chia cho $p$ dư 1. Theo định lý nhỏ của Fermat (trong đó phát biểu rằng nếu $n$ không chia hết cho $p$ thì $n^{p-1} \equiv 1 (\bmod p)$), thì bất kỳ bội số $l$ nào của $p - 1$ đều được.
Lập luận theo cách này cho mỗi ước nguyên tố của số $m$, chúng tôi hiểu rằng đối với $m = p_1 p_2 \ldots p_k$, trong đó $p_1, \ldots, p_k$ là các số nguyên tố khác nhau, $l$ là phù hợp, bội số của tất cả các số $p_i$ và $p_i - 1$, nói cách khác, $l \div \text{НОK}(m, p_1 - 1, p_2 - 1, \ldots, p_k - 1)$. Vì vậy, bài toán lời giải.
Đối với $n = p_1 p_2 \ldots p_k$, có thể chứng minh rằng điều kiện tìm được cho $l$ ($l \div \text{НОK}(m, p_1 - 1, p_2 - 1, \ldots, p_k - 1)$) không chỉ đủ mà còn cần thiết để $l$ thỏa mãn điều kiện bài toán. Để chứng minh điều này, chúng ta có thể áp dụng các thông điệp bổ sung, chẳng hạn như sử dụng sự tồn tại của căn modulo đầu tiên của một số nguyên tố (sao cho $n$ sao cho $x = p - 1$ là số tự nhiên nhỏ nhất mà $n^x \equiv 1 (\bmod p)$).
A. Skabelin

M2817*. Cho các đường tròn cố định $\Omega$ và $\gamma$ cũng có góc cực ABCDEF được mô tả tại $\Omega$ và ngoại tiếp quanh $\omega$. (Lưu ý rằng, theo định lý Poncelet, có vô số họ các góc cực như vậy.) Chứng minh rằng các giá trị $\frac{S_{\text{ABCDEF}}}{AD + BE + CF}$ không phụ thuộc vào việc chọn góc cực ABCDEF.

Từ định lý Brianchon, đối với một góc được mô tả bằng một cực, $AD$, $BE$ và $CF$ cắt nhau tại một điểm $J$, và người ta biết rằng điểm $J$ là một hằng số. (Trên thực tế, trong bất kỳ $(2n)$-giác nào nội tiếp trong một đường tròn cố định và ngoại tiếp quanh một đường tròn cố định, các đường chéo “chính” đi qua một điểm cố định - ví dụ, xem bài viết của V. Protasov “Hai thế kỷ định lý Poncelet” trong «Kvant» Số 5-6 năm 2014, hệ quả 3 của Định lý 3.) Hơn nữa, người ta biết rằng điểm $J$, được coi là một đường tròn có bán kính bằng 0, đồng trục với $\Omega$ và $\gamma$, tức là ba đường tròn này có một trục hướng tâm chung.
Chúng ta hãy biểu thị bằng $X, Y, Z, W, S, T$ các điểm tiếp tuyến tương ứng giữa $\gamma$ và $AB, BC, CD, DE, EF, FA$ (xem hình). Hãy đặt

$AT = AX = a, BX = BY = b, CY = CZ = c, DZ = DW = d, EW = ES = e, FS = FT = f$, vậy bình phương của các đoạn tiếp tuyến $a^2, b^2, c^2, d^2, e^2, f^2$ là lũy thừa của các điểm $A, B, C, D, E, F$ đối với $\gamma$. Ngoài ra $JA^2, \ldots, JF^2$ là độ của các điểm $A, B, C, D, E, F$ so với (vòng tròn bán kính bằng 0) $J$.
Chúng ta hãy sử dụng thực tế này về sự cạnh tranh của một vòng tròn: nếu các vòng tròn $\omega_1, \omega_2, \omega_3$ là đồng trục, thì đối với bất kỳ điểm $X \in \omega_3$ nào, tỷ lệ độ của điểm $X$ so với $\omega_1$ và $\omega_2$ là không đổi.
Chúng tôi hiểu điều đó

$\frac{a}{JA} = \frac{b}{JB} = \frac{c}{JC} = \frac{d}{JD} = \frac{e}{JE} = \frac{f}{JF} = \lambda$,

trong đó $\lambda$ là một hằng số nào đó, chỉ phụ thuộc vào các vòng tròn $\Omega$ và $\gamma$. (Lưu ý rằng các đẳng thức này có thể được sắp xếp lại

⟦folio 30⟧

---
running_head:
folio:
---

Theo định luật thứ ba của Kepler, bình phương của các chu kỳ chuyển động tỉ lệ với lập phương của các trục chính. Từ định luật thứ hai của Kepler về tính không đổi của vận tốc hình cung, theo đó thời gian rơi tỷ lệ thuận với chu kỳ và phần diện tích của hình elip bị che khuất bởi vectơ bán kính nối tiêu điểm của hình elip và vật chuyển động. Diện tích của khu vực bị tối bởi vectơ bán kính nối tâm Trái đất và mảnh vỡ gần bằng một nửa diện tích của toàn bộ hình elip tại thời điểm nó rơi. Điều này có nghĩa là thời điểm rơi gần bằng một nửa thời gian chuyển động dọc theo hình elip hẹp này. Chúng ta hãy thực hiện một phép tính chính xác hơn cho phần thời gian rơi trong toàn bộ thời gian chuyển động dọc theo một hình elip hẹp. Hãy biến hình elip này thành một hình tròn có bán kính 3,3R. Diện tích được quét là một phần của diện tích hình tròn, xấp xỉ 0,452 (bạn hãy tự kiểm tra điều này). Do đó, thời gian rơi sẽ vào khoảng $\Delta t = 24$ h $\cdot$ $(2^3)^{-2} \cdot 0,452 = 3$ h 50 phút.

Đây là đáp số cho câu hỏi thứ hai.
Bây giờ chúng ta tìm góc $\varphi$:
$$\varphi = 2\pi \cdot (8)^{-2} \cdot 0,452 \approx 1$$ vui mừng
và chúng tôi nhận được đáp số cho câu hỏi thứ ba:
$$v_{\text{отн}} = \sqrt{(u \cos \varphi)^2 + (v - u \sin \varphi)^2} = 7903,55$$ m/s.

Nói cách khác, khoảng cách giữa các cói tại thời điểm này đã tăng lên theo tốc độ tìm thấy.

S.Vzryvny

F2818. Nước được hút vào hồ từ một hồ lớn, trên bờ có lắp đặt máy bơm nước tập trung. Động cơ cảm ứng xoay chiều có tần số $f = 1450$ vòng/phút và công suất tối đa $W = 1$ kW. Động cơ này được sử dụng trong thiết kế một máy bơm được thiết kế để lấp đầy bể bơi có độ sâu $h = 1,5$ m, chiều rộng $b = 4$ m và chiều dài đường ray là $l = 20$ m. Cánh bơm có bán kính $R = 10$ cm và chiều rộng $d = 3$ cm. Lỗ ở đầu ra của máy bơm có tiết diện $S_0 = 20$ cm² và nằm sát mép cánh

cánh quạt. Nước chảy ra từ hố này theo phương thẳng đứng hướng lên trên đạt độ cao bằng một nửa chiều cao $H$, trên mặt nước trong hồ có mép trên của bể. Cần lắp một đường ống có chiều cao và mặt cắt ngang bằng nhau ở đầu ra của máy bơm để bể trống ban đầu có thể được đổ đầy nước trong thời gian tối thiểu?

Thời gian tối thiểu này là bao nhiêu? Có thể khẳng định sức mạnh của Pomermi khi cho nước chảy qua đồng rúp.

Tốc độ chuyển động của bánh công tác ở các đầu của nó xa trục quay nhất được xác định bởi tần số quay của trục và bán kính của bánh công tác:

$$u_{\text{max}} = \frac{2\pi Rf}{60 \text{ с}} \approx 15,2 \text{ м/с}.$$

Nếu đường thoát nước phản ứng từ thể tích mà bánh công tác quay được đặt gần các cạnh của bánh công tác, thì trong trường hợp này, áp suất bổ sung tối đa mà nước sẽ có trên các cạnh của bánh công tác khi không có dòng chảy (dòng nước) được xác định bởi giá trị

$$\frac{\rho u_{\text{max}}^2}{2} = 2,3 \cdot 10^5 \text{ Pa} = 2,3 \text{ atm}.$$

Điều này có nghĩa là về nguyên tắc, một máy bơm như vậy có thể cung cấp nước lên độ cao 23 mét (chỉ rất chậm). Chúng ta sẽ giả sử rằng nước trong thể tích mà bánh công tác quay đến từ đỉnh của trục quay và thoát ra từ phần dưới cùng của các cạnh của bánh công tác. Hãy để những câu trả lời này có phần giống nhau. Lưu lượng nước thể tích tối đa $S_0 u$ có thể được cung cấp bởi một động cơ có cánh quạt và phản hồi đầu ra trong máy bơm có kích thước được chỉ định trong điều kiện công việc được xác định bởi các điều kiện

$$\frac{S_0 \rho u^3}{2} = W.$$

Từ điều kiện này suy ra $u = 10$ m/s. Do đó, tốc độ dòng chảy tối đa là khoảng 20 l/s. Trong trường hợp này, áp suất ở đầu ra của máy bơm không khác với áp suất khí quyển và tốc độ trung bình của nước ở đầu ra của máy bơm bằng $u$. Từ đây bạn có thể tìm thấy độ cao mà bạn tìm thấy -

⟦folio 31⟧

---
running_head:
folio:
---

lơ lửng phía trên máy bơm (và mực nước trong hồ)
cạnh hồ bơi:
$$H = 2 \frac{u^2}{2g} = 10 \text{ м}.$$
Nếu nước trong đường ống với tốc độ đáng kinh ngạc $u_1$, dâng lên độ cao $h$, và khoảng cách còn lại $H - h$ bay trong không trung và chạm tới mép hồ bơi thì hồ bơi có thể được lấp đầy. Như vậy phải thỏa mãn điều kiện
$$V\rho gh + \frac{V\rho u_1^2}{2} = V\rho gH.$$
Áp suất ở đầu vào đường ống là $\rho gh$ và tốc độ dòng thể tích của chất lỏng là $Su_1$. Hóa ra năng lượng mà nước nhận được sẽ là
$$W = Su_1\rho gH.$$
Từ đó, sản phẩm $Su_1$ sẽ bằng 10 l/s, bằng một nửa tốc độ dòng chảy tối đa 20 l/s. Điều này có nghĩa là, ví dụ, trong khi duy trì tốc độ chuyển động của chất lỏng trong đường ống, tiết diện của đường ống phải lớn bằng một nửa.
Và vì nước phải duy trì ở điểm cao nhất của quỹ đạo, nên với điều kiện duy trì tốc độ chuyển động, đường ống phải có chiều cao 5 m và tiết diện bên trong là 10 cm². Trong trường hợp này, thời gian để đổ đầy bể thứ nhất là
$$t = \frac{120 \text{ м}^2}{0,01 \text{ м}^3/\text{с}} = 12 \cdot 10^3 \text{ с} = 3 \text{ ч} 20 \text{ мин}.$$
V.Vodyanoy

F2819. Có một lò xo "tải trước". Một lò xo như vậy bắt đầu thay đổi chiều dài của nó một cách molly ở một giá trị ngưỡng nhất định của lực khoảng cách. Lò xo được treo thẳng đứng. Chiều dài của nó với hai tải trọng lơ lửng khác nhau có khối lượng $M_1$ và $M_2$ lần lượt bằng $L_1$ và $L_2$. Đồng thời, tất cả các cuộn dây của lò xo đã giãn ra. Chiều dài của lò xo không tải $L_0$ nhỏ hơn $L_1$ và $L_2$, khối lượng của lò xo $m$. Xác định hệ số đàn hồi $k$ của lò xo và độ lớn lực dự ứng lực $f$.

Đặt giá trị ngưỡng lực là $f$. Nếu tác dụng một lực $f$ vào một lò xo thẳng đứng thì nó sẽ chỉ có một khoảng cách biên (như đã biết
một trăm) bằng $l = mg/(2k)$. Vì vậy, đối với chiều dài thẳng đứng của lò xo chịu tải, ta có thể viết biểu thức tương ứng
$$L = L_0 + \frac{mg}{2k} + \frac{Mg - f}{k} = a + bM,$$
Ở đâu
$$a = L_0 + \frac{1}{k} \left( \frac{mg}{2} - f \right), b = \frac{g}{k}.$$
Các hệ số $a$ và $b$ của phương trình tuyến tính cho $L$ được xác định theo các đại lượng đã biết $M_1, M_2, L_1, L_2$ bằng các tương ứng đơn giản
$$a = \frac{L_1 M_2 - L_2 M_1}{M_2 - M_1}, b = \frac{L_2 - L_1}{M_2 - M_1}.$$
Sử dụng các phương trình thu được, chúng ta có thể xác định hệ số đàn hồi của lò xo và lực dự ứng lực:
$$k = g \frac{M_2 - M_1}{L_2 - L_1},$$
$$f = g \left( \frac{m}{2} - \frac{\Delta L_1 M_2 - \Delta L_2 M_1}{L_2 - L_1} \right).$$
Đây $\Delta L_i = L_i - L_0$.
Đây là một ví dụ về dữ liệu thử nghiệm. Lò xo của trường có khối lượng 10,5 g và dài 5,9 cm. Chiều dài của nó với tải trọng 12,8 g là 6,8 cm và chiều dài của nó với tải trọng 50,7 g là 15,5 cm. Các thông số được tính toán bằng các công thức thu được như sau: $k = 4,3 \text{ H/m}, f = 0,14 \text{ H}$.
A. Vlasov

F2820. Một khung không từ tính có chiều dài $L$ có hình vuông đối xứng ngang với trục của nó với chiều dài cạnh $A$. Trên bề mặt của ống kính, trong một lớp xoắn, một sợi dây có tiết diện hình vuông, cạnh vuông $a$ được quấn. Bề mặt của dây được cách điện bằng một lớp sơn bóng. Chúng ta thực hiện chuỗi bất đẳng thức $a \ll A \ll L$. Theo hệ thống dây điện, dòng điện là $I$. Khung slenod được cắt cẩn thận ở một chỗ (lớn hơn phần giữa), 1/4 vòng dây được nhả ra (dài $A$) và các bộ phận của slenod này được định vị sao cho trục đối xứng của các kệ trùng khớp và không chạm vào khung; phần dây chiếm vị trí song song với các trục đối xứng này (xem hình). Dòng điện chạy qua

⟦folio 32⟧

---
running_head:
folio:
---

dây vẫn còn nguyên. Độ lớn của vectơ cảm ứng từ trường trong nước tiểu trên trục đối xứng nằm ở cùng khoảng cách với các phần tạo thành của cuộn dây điện từ sau khi cắt là bao nhiêu? Vectơ cảm ứng từ này tạo thành một góc bao nhiêu với trục đối xứng của hai nửa điện từ?

Nếu cuộn dây dài vô hạn và không bị cắt thì từ trường bên trong cuộn dây sẽ đều, song song với trục đối xứng và có độ lớn bằng $B_0 = \mu_0 I/a$, trong đó $\mu_0$ là hằng số từ. Trong trường hợp này, từ bất kỳ điểm nào của khung điện từ được chọn bên trong điện từ, có thể nhìn thấy điện từ ở một góc đặc $4\pi$. Bây giờ, sau khi thực hiện các thay đổi và tính đến chiều dài hữu hạn của khung, từ trường tại điểm đã chỉ định được tạo ra bởi cả hai phần dài (một nửa) của cuộn dây điện từ và phần của dây tự do. Sự đóng góp của các phần dài được hướng dọc theo trục đối xứng và sự đóng góp của phần dây không nằm trên khung vuông góc với trục đối xứng.

Đầu tiên, chúng ta hãy xem sự đóng góp vào trường của phần nối dây song song với trục đối xứng. Nếu từ điểm bạn cần tìm trường, bạn vẽ các đoạn vào hai đầu của phần dây này, thì chúng sẽ tạo thành các góc giống hệt nhau $\alpha$ với trục đối xứng, mà $\cos \alpha = \sqrt{1/3}$. Sự đóng góp của phần này vào từ trường (vuông góc với trục đối xứng) có độ lớn bằng nhau

$$B_1 = \frac{2\mu_0 I \cos \alpha}{A/\sqrt{2}} = \frac{2^{3/2}\mu_0 I}{\sqrt{3}A} \approx 1,633 \frac{\mu_0 I}{A}.$$

Bây giờ chúng ta hãy tìm sự đóng góp vào từ trường của hai nửa cuộn dây điện từ. Mỗi nửa của khung có thể nhìn thấy được từ một điểm đã chọn trên trục đối xứng ở một góc đặc

$$\Omega = \frac{4\pi}{6} - \frac{A^2}{(L/2 + A/2)^2} \approx \frac{2\pi}{3} - 4\left(\frac{A}{L}\right)^2.$$

Do đó, tổng góc khối bằng

$$2\Omega = \frac{4\pi}{3} - 8\left(\frac{A}{L}\right)^2.$$

Do đó, tiếp tục theo trục đối xứng, thành phần của vectơ cảm ứng từ trường bằng

$$B_2 = B_0 \frac{2\Omega}{4\pi} = \frac{\mu_0 I}{a}\left(\frac{1}{3} - \frac{2(A/L)^2}{\pi}\right).$$

Xét đến sự bất đẳng thức mạnh $a \ll A \ll L$ chúng ta có thể kết luận rằng độ lớn của vectơ cảm ứng từ trường xấp xỉ

$$B \approx B_2 = \frac{\mu_0 I}{3a},$$

và vectơ này tạo một góc nhỏ với trục đối xứng

$$\varphi = \frac{B_1}{B_2} = \frac{a}{A}(3 \cdot 1,633) \approx 4,89 \frac{a}{A}.$$

D. Từ tính
