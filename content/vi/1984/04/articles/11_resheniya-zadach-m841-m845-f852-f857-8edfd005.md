---
id: 1984-4-resheniya-zadach-m841-m845-f852-f857-8edfd005
issue: kvant_1984_4
year: 1984
number: "4"
title: Lời giải bài toán M841—M845; F852—F857
rubric: zadachnik-kvanta
rubric_sub: Задачник «Кванта»
page_first: 37
page_last: 42
page_labels: 35-40
tag: NBKU
lang: vi
source: kvant_digital
extraction: vision
content_sha256: 5a1c6cb4d2db616b2055a4a6214fc8d79d65a8e93bb454b39ac270ebcefb5812
prompt_sha256: draft-1
translated_from: content/ru/1984/04/articles/11_resheniya-zadach-m841-m845-f852-f857-8edfd005.md
source_content_sha256: 3b83419bc6145553bff88363038eaba26e714176af68dae7dae59e23e8e31f1c
translation_model: draft
translation_run: vi-draft-2026-10-31
translation_quality: draft
---

⟦folio 35⟧

isochorically heated to its initial temperature, which requires the amount of heat $Q=125$ J. Determine $c_x$.

A. A. Sheronov

P871. An initially uncharged capacitor of capacity $C$ is connected consecutively to a battery of EMF of tension $U_0$ and a coil of inductivity $L$. The current in the coil first increases, then decreases. At the moment when the current banishes, the capacitor is disconnected and then reconnected with the ends interchanged.

What maximal current will then flow through the coil. How will the current change if the reconnection process is repeated 1984 times? The circuit’s resistance is negligible.

A. R. Zilberman

P872. A long sled, sliding on very slippery ice, reaches an ice-free section of the road and stops before travelling half its length. Then a sharp push restores the sled’s previous velocity, and it stops again. What is the relationship between 1) the slowing down times in the first and second cases? 2) the distances travelled while slowing down?

S. S. Krotov

Lời giải bài toán

M841 — M845; F852 — F857

bài toán đơn giản này có một số lời giải. Chúng ta hãy chỉ đưa ra một trong số họ. Gọi $a$ và $b$ là độ dài của hai chân, $c$ độ dài cạnh huyền của tam giác đã cho $ABC$; $A_1, B_1$ và $C_1$ là các điểm tiếp tuyến của đường tròn nội tiếp nhìn từ phía bên (xem hình). Bằng định lý về sự bằng nhau của các tiếp tuyến vẽ đường tròn từ một điểm $|AB_1| = |AC_1|$, $|BC_1| = |BA_1|$ và $|CA_1| = |CB_1|$. Nó theo sau đó

$$|AC_1| = \frac{c+b-a}{2}, \quad |BC_1| = \frac{c+a-b}{2}.$$

Bởi vì

$$|AC_1| \cdot |BC_1| = \frac{1}{4} (c+b-a)(c-(b-a)) = \frac{1}{4} (c^2-(b-a)^2) = \frac{1}{4} (c^2-b^2-a^2+2ab) = \frac{ab}{2} = S_{\triangle ABC}$$

(chúng tôi đã sử dụng định lý Pythagore).

Trong trường hợp tam giác tùy ý $ABC$, phép tính tương tự sẽ dẫn đến công thức sau:

$$S_{\triangle ABC} = |AC_1| \cdot |BC_1| \cdot \text{ctg} (\widehat{C}/2).$$

V. N. Dubrovsky

a) Đây là một câu nói khá nổi tiếng - gợi ý cho điểm 6); nó có thể được chứng minh dễ dàng bằng cách sử dụng các công thức tiêu chuẩn để chuyển đổi tổng các sin và hiệu các cosin thành tích:

$$\sin \alpha + \sin \beta + \sin \gamma = 2 \sin \frac{\alpha+\beta}{2} \cos \frac{\alpha-\beta}{2} + 2 \sin \frac{\gamma}{2} \cos \frac{\gamma}{2} = 2 \sin \frac{\gamma}{2} \left( \cos \frac{\gamma}{2} - \cos \frac{\alpha-\beta}{2} \right) =$$

b) Các giá trị $\widehat{A}$, $\widehat{B}$ và $\widehat{C}$ của tam giác thỏa mãn

⟦folio 36⟧

Tình trạng
$$\frac{\sin \hat{A} + \sin \hat{B} + \sin \hat{C}}{\cos \hat{A} + \cos \hat{B} + \cos \hat{C}} = \sqrt{3}.$$
Chứng minh rằng ít nhất một trong số chúng bằng 60°.

$$= 4 \sin \frac{\gamma}{2} \sin \frac{\alpha - \beta - \gamma}{4} \sin \frac{\alpha + \gamma - \beta}{4} = -4 \sin \frac{\alpha}{2} \sin \frac{\beta}{2} \sin \frac{\gamma}{2}$$
(ở phần sau là quá trình chuyển đổi điều kiện $\alpha + \beta + \gamma = 0$).

6) Vì $\sqrt{3} = \frac{\sin 60^\circ}{\cos 60^\circ}$, các điều kiện có thể được viết lại như sau:
$$\sin \hat{A} \cos 60^\circ - \cos \hat{A} \sin 60^\circ + \sin \hat{B} \cos 60^\circ - \cos \hat{B} \sin 60^\circ = 0$$
hoặc
$$\sin (\hat{A} - 60^\circ) + \sin (\hat{B} - 60^\circ) + \sin (\hat{C} - 60^\circ) = 0.$$
Áp dụng phát biểu của điểm a) cho các góc $\hat{A} - 60^\circ$, $\hat{B} - 60^\circ$ và $\hat{C} - 60^\circ$, ta thu được
$$\sin \frac{\hat{A} - 60^\circ}{2} \cdot \sin \frac{\hat{B} - 60^\circ}{2} \cdot \sin \frac{\hat{C} - 60^\circ}{2} = 0,$$
nghĩa là, ít nhất một trong các góc $\hat{A}$, $\hat{B}$, $\hat{C}$ bằng 60°.
L. D. Kurlyandchik

**M843. Tại các đỉnh của tam giác ABC, các phân bố lại AA1, BB1 và ​​CC1 cho mặt phẳng của nó ở một cạnh có chiều dài bằng các đường cao tương ứng của tam giác đã được khôi phục. Chứng minh rằng phân bố lại của các mặt phẳng ABC1, BB1 và ​​CC1 trên mặt phẳng ABC nằm tại tâm đường tròn nội tiếp tam giác ABC và có chiều dài bằng bán kính của nó.

◆ Gọi $Q$ là giao điểm của các mặt phẳng ABC1, BB1 và ​​CC1, $O$ hình chiếu của nó lên mặt phẳng ABC, $P$ hình chiếu $O$ lên một trong các cạnh của tam giác, để định nghĩa - lên đường thẳng BC. Rõ ràng, tam giác QOP đồng dạng với tam giác $A_1AH$, trong đó $AH$ là đường cao của tam giác ABC (xem Hình 1). Do đó, $|OP|:|OQ| = |AH|:|AA_1| = 1$, tức là $|OP| = |OQ|$. Người ta chứng minh tương tự rằng khoảng cách từ điểm $O$ đến các đường thẳng $AB$ và $AC$ cũng bằng $|OQ|$. Nhưng điều này cũng có nghĩa là $O$ là tâm của đường tròn nội tiếp, $a$ $|OQ|$ là bán kính của nó.

Hãy đưa ra sự tương ứng tổng quát giữa khoảng cách $d$ từ điểm $Q$ đến mặt phẳng ABC và các độ dài $a$, $b$ và $c$ của các đoạn AA1, BB1 và ​​CC1:
$$\frac{d}{a} + \frac{d}{b} + \frac{d}{c} = 1$$ hoặc $d = \frac{abc}{ab + bc + ca}$.

Hình 1.
Hình 2.

Hãy tự chứng minh và kiểm tra xem nếu $a$, $b$ và $c$ là độ dài các đường cao của một tam giác thì $d$ là bán kính của đường tròn nội tiếp tam giác đó. hình 2 minh họa cách chứng minh sự tương ứng tương tự trong trường hợp hai chiều.

V. N. Dubrovsky,
A. A. Yaguyants

**M844. a) Chứng minh rằng mọi số tự nhiên $a$ đều có thể biểu diễn trực quan dưới dạng
$a = a_1 \cdot 1! + a_2 \cdot 2! + \dots + a_n \cdot n!$, (1)
thức ăn $a_k$ - số nguyên, $0 \leq a_k \leq k$, $a_n \neq 0$. (Theo định nghĩa, $k! = 1 \cdot 2 \cdot \dots \cdot k$, $1! = 1$.)
b) * Chứng minh rằng mọi số hữu tỉ $r$, $0 < r < 1$ đều có thể

◆ a) Hãy chỉ ra cách, cho một số $a$, tìm hệ số dẫn đầu $a_n$ trong biểu diễn
$$a = a_1 \cdot 1! + a_2 \cdot 2! + \dots + a_{n-1} \cdot (n-1)! + a_n \cdot n!$$
(*)
trong đó $0 \leq a_k \leq k$, $a_n \neq 0$ và số của nó $n$.
Từ điểm đầu tiên ở lề (xem trang 37), theo đó đối với các giá trị được chỉ định của các hệ số $a_k$
$a' = a_1 \cdot 1! + a_2 \cdot 2! + \dots + a_{n-1} \cdot (n-1)! \leq$
$\leq 1 \cdot 1! + 2 \cdot 2! + \dots + (n-1) \cdot (n-1)! < n!$,
Ngoài ra, $n! \leq a_n \cdot n! \leq n \cdot n!$. Với mọi số tự nhiên $a$ người ta có thể tìm thấy một $n$ duy nhất sao cho $a$ nằm trong khoảng $n! \leq a < (n+1)!$; điều này xác định duy nhất $n$ trong biểu diễn-

⟦folio 37⟧

biểu diễn dưới dạng
$$r = \frac{b_1}{2!} + \frac{b_2}{3!} + \dots + \frac{b_n}{(n+1)!},$$
(2)
thức ăn $b_k$ - số nguyên, $0 \leq b_k \leq k$, $b_n \neq 0$.
c) Trình bày số $a=1984$ ở dạng (1) và số $r=19/84$ ở dạng (2).

$$1 \cdot 1! + 2 \cdot 2! + \dots + n \cdot n! = (2! - 1!) + (3! - 2!) + \dots + ((n+1)! - n!) = (n+1)! - 1$$

họ (*). Bằng cách chia khoảng này thành các khoảng $n$ (mỗi khoảng dài $n!$), chúng ta tìm thấy giá trị duy nhất có thể có $a_n$ là số khoảng mà $a : a_n \cdot n! \leq a < (a_n+1)n!$ rơi vào; nói cách khác, $a_n$ là thương riêng phần của $a$ chia cho $n! : a = a_n \cdot n! + a'$, trong đó $0 \leq a' < n!$ ($a_n = [a/n!]$, trong đó $[x]$ là phần nguyên của $x$).

Tương tự, chúng ta có thể tìm cho $a'$ hệ số dẫn đầu trong biểu diễn
$$a' = a_1 \cdot 1! + a_2 \cdot 2! + \dots + a_{n-1} \cdot (n-1)!$$
v.v. Bằng chứng chính thức về sự tồn tại và tính duy nhất của biểu diễn được yêu cầu (*) có thể được chứng minh bằng phương pháp quy nạp toán học: với $a=1$ mệnh đề là hiển nhiên và lý luận của chúng tôi cho thấy từ giả định rằng nó đúng với các số nhỏ hơn $a$, thì kết quả là nó đúng với $a$ đã cho.

Bạn cũng có thể thắc mắc theo hướng ngược lại: đầu tiên tìm $a_1$, sau đó $a_2$, v.v. Trong trường hợp này, $a_1$ là phần dư của phép chia $a$ cho 2, $a_2$ là phần dư của phép chia $(a-a_1 \cdot 1!)/2$ cho 3 và nói chung, $a_k$ là phần dư của phép chia $(a-a_1 \cdot 1! - \dots - a_{k-1} \cdot (k-1)!)/k!$ cho $k+1$.

Cả hai phương pháp này đều cho phép chúng ta suy ra công thức chung sau cho $a_k$:
$$a_k = [a/k!] - [a/(k+1)!] (k+1).$$

6) Chúng ta sẽ tuần tự chia đoạn [0; 1]: ở bước 1 - thành 2 phần bằng nhau, ở bước thứ 2 của mỗi đoạn trong hai đoạn được tạo thành - thành 3 phần bằng nhau, v.v. Nói chung, ở bước $k$-th của mỗi đoạn thu được ở bước $(k-1)$-th, chúng ta chia thành $k+1$ phần bằng nhau. Rõ ràng là sau bước thứ $k$ đoạn [0; 1] sẽ được chia thành $(k+1)$ phần bằng nhau.

Hãy xem xét điểm phân vùng $r$, xuất hiện lần đầu ở bước $n$ (rõ ràng là $r=m/(n+1)!$, trong đó $m$ không chia hết cho $n+1$). Điểm này cách xa điểm của bước thứ $(n-1)$ gần điểm đó nhất ở bên trái một lượng $b_n/(n+1)!$, trong đó $b_n$ là một số nguyên, $0 < b_n \leq n$. Đổi lại, điểm này của bước $(n-1)$ cách xa điểm của bước $(n-2)$ gần bên trái nhất là $b_{n-1}/n!$, trong đó $0 \leq b_{n-1} \leq n-1$, v.v. Kết quả là, chúng ta có được biểu diễn
$$r = \frac{b_1}{2!} + \frac{b_2}{3!} + \dots + \frac{b_n}{(n+1)!}, 0 \leq b_k \leq k, b_n \neq 0.$$

(**)

Hệ quả duy nhất của nó là đối với bất kỳ tập hợp $b_1, \dots, b_n$ nào trong (**) các số
$$\frac{b_1}{2!}, \frac{b_1}{2!} + \frac{b_2}{3!}, \dots, \frac{b_1}{2!} + \frac{b_2}{3!} + \dots + \frac{b_n}{(n+1)!}$$

theo đó, thu được không muộn hơn ở bước thứ 1, thứ 2, ..., $n$-thứ của phân vùng và (do bất đẳng thức $0 \leq b_k \leq k$) mỗi bước trong số chúng gần bên trái nhất với bước tiếp theo trong số tất cả các số của cùng một bước.

Cần lưu ý rằng mọi số khác $r=p/q$ với khoảng [0; 1] sẽ xuất hiện dưới dạng điểm phân vùng không muộn hơn ở bước $(q-1)$, kể từ $r=p(q-1)/q!$.

Trên thực tế, trong lời giải này, các hệ số $b_1, \dots, b_n$ được xác định tuần tự bắt đầu từ $b_n$: nếu $b_n, \dots, b_k$ đã được tìm thấy thì $b_{k-1}$ là phần còn lại của phép chia số (số nguyên!)
$$\left(r - \frac{b_n}{(n+1)!} - \dots - \frac{b_k}{(k+1)!}\right) \cdot k!$$ đến $k$. Hãy suy nghĩ về cách bạn có thể tìm thấy
Quay số các hệ số này bắt đầu từ $b_1$. Kiểm tra xem công thức sau có đúng không:
$$b_k = [r \cdot (k+1)!] - [r \cdot k!](k+1)$$
(bạn có thể sử dụng danh tính thứ hai ở lề).

c) Đáp số: 1984 = 2·2! + 3·3! + 2·4! + 4·5! + 2 6!, 19/84 = 1/3! + 1/4! + 2/5! + 6/7!. Những cách biểu diễn này rất dễ tìm thấy dựa trên lời giải điểm a) và b).

V. E. Kolosov

♦ Đáp số: với mọi số chẵn $n$.

Hình 2 cho thấy cách tạo một hình đối xứng tâm (góc $4 \times n$) từ bất kỳ góc số chẵn $n$ nào. Ngược lại, hãy chứng minh rằng bất kỳ hình đối xứng tâm $f$ nào từ điều kiện chỉ có thể chứa một số góc chẵn. Chúng ta hãy đưa ra hai bằng chứng.

⟦folio 38⟧

Đầu tiên dựa trên ý tưởng truyền thống của Olympic - tô màu và tính chẵn lẻ. Tâm đối xứng $O$ của hình $\Phi$ là một trong những tâm đối xứng của lưới vuông tương ứng, nghĩa là nút của nó hoặc điểm giữa của đoạn giữa hai nút liền kề hoặc tâm của ô. Cuối cùng, số ô trong hình sẽ là số lẻ nhưng phải chia hết cho 4. Hãy vẽ mặt phẳng “bằng một sọc xanh lam”, như trong Hình 3. Khi đó số ô màu xanh lam trong hình $\Phi$ sẽ là số chẵn. (Tùy thuộc vào vị trí của tâm $O$, mỗi ô đối xứng màu xanh lam có màu trắng - như đối với tâm $O_1$ và $O_2$ trong Hình 3, $a$, và sau đó số ô đối xứng màu xanh lam trong $\Phi$ bằng một nửa tổng số ô, bội số của bốn; hoặc mỗi ô đối xứng màu xanh lam là một màu xanh lam khác - như đối với điểm $O_3$ trong Hình 3, $a$.) Nhưng trong bất kỳ hình chữ nhật $4 \times 1$ nào trên lưới, số lượng ô màu xanh lam là số chẵn (Hình 3, $a$) và ở bất kỳ góc nào là số lẻ (Hình 3, $6$). Vì vậy số góc phải chẵn.

Chứng minh thứ hai dựa trên thực tế là tâm đối xứng $O$ của hình $\Phi$ cũng là tâm khối của nó (nếu coi nó như một tấm đồng nhất; chúng ta cũng có thể thay thế $\Phi$ bằng một hệ hữu hạn có khối lượng bằng nhau tập trung tại tâm của các ô tạo nên hình này). Như chúng ta đã thấy ở trên, ít nhất một trong các đường lưới đi qua điểm $O$; Hãy coi nó là trục tọa độ và trục hoành độ - bất kỳ đường lưới tiền tiền định nào. Đơn vị đo chiều dài sẽ là cạnh của lồng. Trong các trục này, tọa độ của điểm $O$, cũng như tâm khối của bất kỳ hình chữ nhật $4 \times 1$ nào sẽ là số nguyên hoặc thu được, tức là các số có dạng $a/2$, trong đó $a$ là số nguyên. Khối tâm của góc nằm ở giữa đoạn nối tâm của hai hình chữ nhật $2 \times 1$ mà nó được tạo thành (Hình 4), do đó tọa độ của nó có dạng $b \pm 1/4$ ($b$ là số nguyên). Bây giờ chúng ta hãy lợi dụng thực tế là nếu chúng ta thay thế từng hình - hình chữ nhật và góc tạo nên $\Phi$, bằng tâm khối lượng của nó và đặt các khối lượng bằng nhau tại các tâm này, thì tâm của hệ mới thu được cũng rơi vào điểm $O$. Điều này có nghĩa là tọa độ của điểm $O$ bằng trung bình số học của các tâm tọa độ tương ứng của khối lượng của tất cả các hình tạo nên $\Phi$. Do đó, tổng hoành độ của các tâm này, tức là tổng của một số số có dạng $a/2$ và $n$ các số có dạng $b \pm 1/4$, phải bằng 0. Nhưng điều này, rất nhiều, chỉ có thể thực hiện được với thậm chí $n$.

Để chứng minh thứ hai trở nên hoàn toàn chặt chẽ, chúng ta cũng phải đưa ra một định nghĩa toán học chính xác về khối tâm và chứng minh việc sử dụng các tính chất của nó, ví dụ, tính hợp pháp của việc thay thế một nhóm khối lượng nhất định bằng tâm của nó. Điều này được thảo luận chi tiết trong bài viết của M. B. Balk và V. G. Boltyansky trên tạp chí này.

V. G. Belov

F852. Trên mặt phẳng không dẫn điện nằm ngang không xuyên qua một vòng có khối lượng đều mang tải $m$. Sau khi bật một từ trường nằm ngang có cảm ứng $\vec{B}$, phân bố lại mặt phẳng của vòng, lực ép của vòng lên mặt phẳng giảm đi một nửa. Chiếc vòng đã lăn với tốc độ bao nhiêu nếu điện tích của nó là $q$?

Sự thay đổi lực ép của vòng trên mặt phẳng là do tác dụng của một lực nào đó lên vòng từ từ trường. Chúng ta hãy tìm thấy sức mạnh này.

Chúng ta hãy xem xét hai phần nhỏ có đường kính đối diện của vòng gần các điểm $A$ Và $C$ (xem hình. ok). Kể từ thời điểm $O$ - tâm quay tức thời của vòng, tốc độ tức thời của các điểm $A$ Và $C$ bằng tương ứng

$$v_A = \frac{v}{R} |OA| = \frac{v}{R} 2R \cos \frac{\alpha}{2} = 2v \cos \frac{\alpha}{2},$$

$$v_C = \frac{v}{R} |OC| = 2v \sin \frac{\alpha}{2},$$

trong đó $R$ là bán kính của vòng tròn. Các vectơ $\vec{v}_A$ và $\vec{v}_C$ phân phối lại các phân đoạn tương ứng $OA$ và $OC$. Đặt điện tích của mỗi phần là $\Delta q$. Vì diện tích nhỏ nên những khoản phí này có thể được coi là chính xác. Lực Lorentz tác dụng lên mỗi điện tích trong từ trường bằng

$$F_A = \Delta q \cdot B2v \cos \frac{\alpha}{2},$$

$$F_C = \Delta q \cdot B2v \sin \frac{\alpha}{2}.$$

Các vectơ $\vec{F}_A$ và $\vec{F}_C$ được định hướng dọc theo các đoạn $OA$ và $OC$ và bố cục

⟦folio 39⟧

Chúng nằm ở các góc ngang tương ứng bằng

$$\beta = \frac{\alpha}{2} + \left( \frac{\pi}{2} - \alpha \right) = \frac{\pi}{2} - \frac{\alpha}{2},$$

$$\gamma = \frac{\pi}{2} - \left( \frac{\pi - \alpha}{2} \right) = \frac{\alpha}{2}.$$

Trong hình chiếu lên phương ngang, lực tác dụng lên cả hai phần bằng

$$\dot{f}_x = \Delta q \cdot 2Bv \left( \cos \frac{\alpha}{2} \sin \frac{\alpha}{2} - \sin \frac{\alpha}{2} \cos \frac{\alpha}{2} \right) = 0,$$

và chiếu lên phương thẳng đứng

$$\dot{f}_y = \Delta q \cdot 2Bv \left( \cos^2 \frac{\alpha}{2} + \sin^2 \frac{\alpha}{2} \right) = \Delta q \cdot 2Bv.$$

Xét tương tự từng cặp phần đường kính đối diện, ta thấy hình chiếu ngang của lực tác dụng lên cọc từ từ trường bằng 0 và hình chiếu thẳng đứng bằng

$$F_y = \sum_i F_{yi} = 2vB \sum_i \Delta q_i,$$

trong đó $\sum_i \Delta q_i$ là tổng điện tích của tất cả các phần tử của các hạt tạo nên một nửa vòng, nghĩa là $\sum_i \Delta q_i = \frac{q}{2}$. Như vậy,

$$F_y = qvB.$$

Chúng ta hãy viết điều kiện cân bằng của vòng tròn theo phương thẳng đứng:

$$mg = N + qvB.$$

Theo điều kiện bài toán $N = mg/2$ và do đó

$$qvB = mg/2.$$

Từ đây

$$v = mg/2qB.$$

L. G. Markovich

◆ Khi tác dụng một lực $F_1$ vào tâm của bức tường bên phải, thùng chứa sẽ chuyển động khi lực này bằng lực ma sát $\mu N'_1$ tác dụng lên các giá đỡ cố định. Vậy lực ép sàn lên các giá đỡ này là -

$$N_1 = F_1/\mu.$$

Tổng mômen của các lực đối với trục đi qua các con lăn phải bằng 0 (thùng chứa không bị lật). Do đó (xem Hình 1)

$$\frac{mg l}{2} - \frac{F_1 l}{2} - N_1 l = 0.$$

Từ đây, tính đến thực tế là $N_1 = F_1/\mu$, chúng ta thu được:

$$mg = F_1 \left( 1 + \frac{2}{\mu} \right).$$

Khi một lực $F_2$ tác dụng vào tâm của phía bên trái (Hình 2), lực ép của sàn lên các giá đỡ cố định bằng $F_2/\mu$. Sự bằng 0 của tổng mô men xoắn đối với trục đi qua các con lăn dẫn đến sự phù hợp với mômen tương ứng.

$$mg = F_2 \left( \frac{2}{\mu} - 1 \right).$$

($F_2 > F_1$, vì trong trường hợp thứ hai, mômen lực $F_2$ dẫn đến tải trọng bổ sung lên các giá đỡ cố định và do đó làm tăng lực ma sát.)

Giải (1) và (2) cùng nhau, chúng ta tìm thấy $m$:

$$m = \frac{2F_1 F_2}{g (F_2 - F_1)}.$$

Một số tủ lạnh có cấu trúc hỗ trợ tương tự như thùng chứa của chúng tôi. Chúng di chuyển dễ dàng về phía các con lăn và khó khăn hơn nhiều theo hướng ngược lại. Đôi khi tủ lạnh không muốn trượt chút nào mà bắt đầu lật úp. Điều này xảy ra ở một giá trị nhất định của hệ số ma sát. Trong trường hợp tủ lạnh “khối” có khối lượng phân bố đồng đều - ở mức $\mu \geq 1$. Đạt được giá trị giới hạn $\mu$

⟦folio 40⟧

F854. Ước tính lực trung bình phải tác dụng lên mép của đệm hơi để đệm đệm nằm ở giữa dưới một cạnh thẳng. Nệm không bị quá tải ở một bên. Hãy tự mình đặt số lượng cần thiết cho lời giải và các giá trị số khá thực tế của chúng và nhận được kết quả bằng số.

Hãy ước tính công việc cần làm để tấm nệm được đặt đúng góc. Theo thứ tự độ lớn, có thể ước tính là $A \sim p \cdot \Delta V$, trong đó $p$ là chênh lệch giữa áp suất khí quyển và áp suất không khí bên trong nệm, $\Delta V$ là sự thay đổi thể tích của nệm trong quá trình biến dạng của nó. Như có thể thấy trên hình, $\Delta V$ gần bằng tích của diện tích tam giác $ABC$ và chiều rộng của nệm $b$:

$$\Delta V \approx \frac{2d \cdot d}{2} b = d^2 n,$$

trong đó $d$ là độ dày của nệm.

Mặt khác, công uốn một tấm nệm có thể được ước tính bằng tích của lực trung bình $F_{cp}$ và quãng đường di chuyển:

$$A \approx F_{cp} \frac{2\pi l}{4} \sim F_{cp} l$$

(l là chiều dài của nệm).

Từ các biểu thức trên suy ra rằng

$$A \sim p \cdot \Delta V \sim p d^2 b \sim F_{cp} l,$$

Ở đâu

$$F_{cp} \sim \frac{p d^2 b}{l}.$$

Để tính toán số, bạn có thể đặt $b \approx 0,8$ m, $d \approx 0,15$ m, $l \approx 2$ m. Việc ước tính $p$ khó khăn hơn. Hãy sử dụng ý tưởng này. Nếu bạn đứng trên nệm bằng chân thì nó thường tiếp tục chạm đất. Do đó, $p$ có cùng thứ tự với áp lực do bàn chân của một người tác dụng lên mặt đất:

$$p \sim \frac{mg}{S} \sim \frac{700 \text{ H}}{0,2 \cdot 0,3 \text{ m}^2} \sim 10^4 \text{ Pa}.$$

Cuối cùng chúng tôi tính toán:

$$F_{cp} \sim \frac{10^4 \Pi a \cdot (0,15 \text{ m})^2 \cdot 0,8 \text{ m}}{2 \text{ m}} \sim 10^2 \text{ H},$$

điều này phù hợp tốt với kinh nghiệm hàng ngày của chúng tôi.

E. I. Palchikkov

F855. Một tụ điện phẳng nối với cực của pin có suất điện động $\delta$ được cắm hoàn toàn song song với các bản của nó bằng một bản tích điện cách một trong các bản của tụ điện một khoảng $b$ (xem hình). Tìm lực tác dụng lên tấm đầu vào nếu điện tích của nó là $q$. Chạy tiếp theo. Diện tích của các bản tụ là $S$, khoảng cách giữa chúng là $d$.

Điện trường bên trong tụ điện là tổng của trường tạo bởi bản có điện tích $q$ và trường tạo ra bởi điện tích của các bản tụ. Ví dụ: các trường này được chỉ định tương ứng với $E$ và $E_1$. (Hình vẽ thể hiện hướng của trường $E$ và $E_1$ trong trường hợp các điện tích dương đi vào tấm.)

Lực tác dụng lên tấm chèn bằng

$$F = q E_1.$$

Điện áp $E_1$ có thể được tìm thấy bằng cách viết hiệu điện thế giữa các bản tụ dưới dạng

$$\delta = (E_1 + E)(d - b) + (E_1 - E) b.$$

Từ đây

$$E_1 = \frac{\delta + E(2b - d)}{d}.$$

Thay $E = q/2\varepsilon_0 S$, ta được:

$$E_1 = \frac{\delta + q(2b - d)}{2S\varepsilon_0}.$$

Do đó, lực tác dụng lên tấm chèn là
