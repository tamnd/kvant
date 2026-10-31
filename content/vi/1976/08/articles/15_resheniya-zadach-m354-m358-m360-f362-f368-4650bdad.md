---
id: 1976-8-resheniya-zadach-m354-m358-m360-f362-f368-4650bdad
issue: kvant_1976_8
year: 1976
number: "8"
title: Lời giải bài toán M354—M358, M360; F362—F368
rubric: zadachnik-kvanta
rubric_sub: Задачник «Кванта»
page_first: 40
page_last: 48
page_labels: 38-46
tag: 8V1H
lang: vi
source: kvant_digital
extraction: vision
content_sha256: a33dab552adf60d206cef6215cc64738078315290ca85fb343c2c01908aa0b8d
prompt_sha256: draft-1
translated_from: content/ru/1976/08/articles/15_resheniya-zadach-m354-m358-m360-f362-f368-4650bdad.md
source_content_sha256: 829d67a978aef3b8564863bdb8ad887e7a5e7e187a889a87650dc42e63ac0d0f
translation_model: draft
translation_run: vi-draft-2026-10-31
translation_quality: draft
---

⟦folio 38⟧

F410. Trong một thiết bị dựa trên điện tử, cực âm vonfram tinh khiết được đặt trong một bình lớn chứa oxy dư ở áp suất $p = 10^{-7}$ atm và nhiệt độ $T = 300^\circ\text{K}$. Giả sử rằng mọi phân tử chạm vào cực âm đều dính vào nó, hãy ước tính thời gian hình thành lớp đơn phân tử. Các phân tử có thể được coi là những quả bóng có đường kính $d \approx 3 \cdot 10^{-8}$ cm. (9 ô)

F411. Một đồng hồ đo áp suất thủ công hình chữ U có thể thay đổi áp suất lên tới 1 atm. Áp suất tối đa có thể thay đổi được là bao nhiêu nếu hai đồng hồ đo áp suất như vậy mắc nối tiếp với một ống ngắn? (lớp 9-10)

F412. Giáo viên, đáp lại doxa, giám sát lớp học bằng hình ảnh phản chiếu trong kính. Đồng thời, anh ta nhìn thấy hai hình ảnh phản chiếu của một học sinh ngồi cách mình 5 m: một cách 5 m, một cách $\frac{5}{7}$ m. Chỉ quay mặt về phía lớp, qua cặp kính anh nhìn thấy hình ảnh của cậu học sinh đó ở khoảng cách 2,5 m. Xác định chiết suất của thủy tinh làm thấu kính. (10 lớp)

Lời giải bài toán
M354 — M358, M360; F362 — F368

M354. Có thể xét các số 1, 2, 3, ..., $4n + 2$ tại các đỉnh và trung điểm của các cạnh của một nút thắt đều (2n + 1) sao cho tổng của ba số ở hai đầu và giữa mỗi cạnh bằng nhau đối với tất cả các cạnh?

Chúng ta hãy xem xét trường hợp $n = 3, n = 8$ làm ví dụ,

Hình 1.

Đáp số. Có thể.

Hãy đưa ra một trong những phương pháp sắp xếp. Tại trung điểm của các cạnh của đa giác, chúng ta xếp các số từ 1 đến $2n + 1$ theo thứ tự. Thông báo này giúp bạn sắp xếp các số còn lại $2n + 2, \dots, 4n + 2$. Hãy tìm tổng $S$ của ba số ở cuối và giữa mỗi bên. Rõ ràng, $S = \frac{\Sigma + \Sigma'}{2n + 1}$, trong đó $\Sigma = 1 + 2 + \dots + (4n + 2) = (2n + 1) \times (4n + 3)$ là tổng của tất cả các số được viết, $\Sigma' = (2n + 2) + \dots + (4n + 2) = (2n + 1) (3n + 2)$ là tổng của các số cần đặt ở các đỉnh; do đó $S = 7n + 5$. Bây giờ chúng ta đặt số $4n + 2$ ở đỉnh, chung cho các cạnh có số 1 và 2 ở giữa, và chúng ta sẽ đặt các số $4n + 1, 4n, \dots, 2n + 2$ lần lượt ở các đỉnh, coi đỉnh có số $4n + 2$ là đỉnh đầu tiên - xem Hình 1 (trong hình này, tất cả các điểm đều nằm trên cùng một đường tròn; các chấm đen là “trung điểm”, các chấm màu đỏ là “đỉnh”). Hãy chứng minh rằng bằng cách này, số cần tìm sẽ được đặt ở mỗi đỉnh (không còn nghi ngờ gì nữa rằng đây sẽ là các số $2n + 2$, ..., $4n + 2$). Trên thực tế, sau $n$ bước đầu tiên chúng ta sẽ đến đỉnh liền kề với đỉnh ban đầu và số $(4n + 2) - n = 3n + 2$ sẽ được đặt ở đỉnh này, do đó tổng các số ở cạnh có một số ở giữa chính xác là $(3n + 2) + 1 + (4n + 2) = 7n + 5$. Bây giờ số tiền chính xác không phải là

⟦folio 39⟧

M355. N đứa trẻ chuyền N quả bóng. Khi bắt đầu mỗi người trong số họ, chúng tôi ném quả bóng của mình cho một trong những người bạn đồng hành của mình và bắt quả bóng do ai đó ném (anh ta có thể ném và bắt quả bóng của chính mình) để mọi người lại có một quả bóng. Sau đó, các chàng trai lại ném quả bóng cho chính những người mà họ đã ném lần đầu tiên, v.v. Trò chơi dừng lại khi tất cả các quả bóng được trả lại cho chủ nhân của chúng (các quả bóng chưa được thay thế, chúng ta sẽ coi chúng có màu sắc khác nhau).

Chứng minh rằng
a) Trả bóng cho từng người tham gia sau khi ném N;
b) cerra bắt buộc phải chấm dứt;
e) thời lượng của cerra luôn là ước số của số N!=1·2·…·N;
d) thời hạn của cerra không được vượt quá $\frac{N}{3}$.

Cho phép người chơi $A_1$ chuyền bóng của mình cho người chơi $A_2$, người chơi $A_2$ cho người chơi $A_3$it. D. Vì có số lượng người chơi hữu hạn nên theo trình tự này sớm hay muộn một trong hai người chơi sẽ gặp nhau hai lần. Rõ ràng người chơi đầu tiên như vậy sẽ là người chơi $A_1$. Có hiệu quả, hãy để người chơi $A_n$ chuyền bóng của mình cho người chơi $A_k$, trong đó $k < n$ và $k > 1$. Sau đó, người chơi $A_n$ và $A_{k-1}$ chuyền bóng cho cùng một người chơi và từ điều kiện bài toán thì người chơi $A_{k-1}$ và $A_n$ là cùng một người. Vì vậy, các cầu thủ $A_1$, $A_2$, ... có thể xếp thành vòng tròn sao cho mỗi cầu thủ chuyền và nhận bóng từ người hàng xóm của mình. Tuy nhiên, người chơi có thể được xếp vào một số vòng kết nối như vậy. Vì không có quá N người trong mỗi vòng tròn này nên bóng sẽ quay trở lại bất kỳ người chơi nào sau không quá N lần ném.

Chúng ta có tổng cộng s vòng tròn, trong đó lần lượt có $l_1$, $l_2$, ..., $l_s$ người. Nếu có l người trong một vòng tròn thì sau khi ném m·l, tất cả các quả bóng trong đó đều nằm trong tay người chủ. Vì vậy, trò chơi sẽ kết thúc sau $T = H.O.K.(l_1, l_2, ..., l_s)$ lần ném. (H.O.K.(l_1, ..., l_s) là bội số chung nhỏ nhất của $l_1$, ..., $l_s$). Vì mọi thứ đều là $l_i \leq N$ nên rõ ràng T là ước của N!. Như vậy ta đã trả lời được điểm a), b) và d) bài toán. Hãy nhìn vào điểm d).

Lưu ý rằng $l_1 + l_2 + ... + l_s = N$ và tất cả $l_i$ đều là số nguyên.

Hãy để chúng tôi chứng minh điều đó $l_1 \cdot l_2 \cdot ... \cdot l_s \leq 3$. (Trong điều kiện bài toán, được xuất bản ở «Kvant» Số 11 năm 1975, ở đoạn d) có lỗi đánh máy: thời lượng của trò chơi không được vượt quá $\frac{N}{3}$, chứ không phải 3N/3.) Có hiệu lực, nếu có một số $l_s \geq 4$, thì thay thế bằng 2+($l - 2$), chúng tôi sẽ không thay đổi số tiền $l_1 + l_2 + ... + l_s$ và không giảm sản phẩm $l_1 \cdot l_2 \cdot ... \cdot l_s$. Do đó, từ tích $l_1 \cdot l_2 \cdot ... \cdot l_s$ chúng ta có thể đi đến tích không tối thiểu, trong đó tất cả các thành phần không quá ba. Lưu ý, nếu điều này xảy ra, 1+1 nhân 2, 1+3 nhân 2+2 và 2+2+2 nhân 3+3, chúng ta sẽ được tích có dạng 3·3·…·3, 3·3···3·2 hoặc 3·3···3·2·2 tùy theo số dư thu được khi chia N cho 3, không nhỏ hơn bất kỳ tích nào $l_1 \cdot l_2 \cdot ... \cdot l_s$. Cụ thể: nếu N chia hết cho 3 thì chúng ta lấy $\frac{N}{3}$ bộ ba và nhận được ước tính cần thiết; nếu số dư là 1 thì lấy $\frac{N}{3}$ ba và hai hai; sau đó $l_1 \cdot l_2 \cdot ... \cdot l_s < 2 \cdot 2 \cdot 3 = \frac{N-4}{3}$; nhưng 4·3 < 3, vì $4^3 > 3^4$. Nếu số dư là 2 thì lấy $\frac{N}{3}$ ba và một hai;

⟦folio 40⟧

M356. Từ điểm M nằm trong tam giác $A_1B_1C_1$, các đường vuông góc $MA_2$, $MB_2$, $MC_2$ lần lượt được thả xuống các đường thẳng $B_1C_1$, $A_1C_1$, $A_1B_1$, sau đó từ điểm này, các đường vuông góc $MA_3$, $MB_3$ được thả xuống, $MC_3$ đến các đường thẳng $B_2C_2$, $A_2C_2$, $A_2B_2$, v.v. Hãy chứng minh rằng trong dãy kết quả các tam giác $A_1B_1C_1$, $A_2B_2C_2$, $A_3B_3C_3$, ... tam giác $A_{3n+1}B_{3n+1}C_{3n+1}$ đồng dạng với tam giác $A_1B_1C_1$.

Trước tiên chúng ta hãy chứng minh sự tương ứng phụ sau: $\hat{A}_{i+1} = B_i\hat{M}C_i - \hat{A}_i$ (tương ứng $\hat{B}_{i+1} = A_i\hat{M}C_i - \hat{B}_i$, $\hat{C}_{i+1} = A_i\hat{M}B_i - \hat{C}_i$).

Thật vậy, vì $MA_{i+1}\bot B_iC_i$, $MB_{i+1}\bot A_iC_i$ và $MC_{i+1}\bot A_iB_i$, các đường tròn có đường kính $MC_i$ và $MB_i$ có thể được mô tả lần lượt xung quanh các tứ giác $MA_{i+1}C_iB_{i+1}$ và $MA_{i+1}B_iC_{i+1}$. Do đó, $MA_{i+1}\bot B_{i+1} = MC_i\bot B_{i+1}$ và $MA_{i+1}\bot C_{i+1} = MB_{i}\bot C_{i+1}$ (là các góc treo dựa trên cùng một cung) và đối với góc $A_{i+1}$ chúng ta có (xem Hình 3):

$$\hat{A}_{i+1} = C_{i+1}\hat{A}_{i+1}B_{i+1} + MA_{i+1}C_{i+1} = MC_{i}\hat{B}_{i+1} + MB_{i}\hat{C}_{i+1} = (\hat{C}_i - M\hat{C}_iB_i) + (\hat{B}_i - M\hat{B}_iC_i) = (\hat{B}_i + \hat{C}_i) - (M\hat{B}_iC_i + M\hat{C}_iB_i) = (180^\circ - \hat{A}_i) - (180^\circ - M\hat{C}_i) = B_i\hat{M}C_i - \hat{A}_i.$$

Sau nhiệt độ các góc của tam giác là $A_4B_4C_4$. Chúng tôi có:

$$\hat{A}_4 = B_3\hat{M}C_3 - \hat{A}_3 = (180^\circ - \hat{A}_2) - (B_2\hat{M}C_2 - \hat{A}_2) = (180^\circ - B_2\hat{M}C_2) = \hat{A}_1.$$

Tương tự như $\hat{B}_4 = \hat{B}_1$, $\hat{C}_4 = \hat{C}_1$, tức là $\Delta A_4B_4C_4 \sim \Delta A_1B_1C_1$. Lấy tam giác $A_4B_4C_4$ ngoại trừ ($\Delta A_1'B_1'C_1'$), ta chứng minh tương tự rằng

$$\Delta A_7B_7C_7 \sim \Delta A_4B_4C_4 \sim \Delta A_1B_1C_1,$$

vậy thì sao

$$\Delta A_{10}B_{10}C_{10} \sim \Delta A_7B_7C_7 \sim \dots \sim \Delta A_1B_1C_1,$$

vân vân, vân vân

$$\Delta A_{3n+1}B_{3n+1}C_{3n+1} \sim \Delta A_{3n} \sim 2C_{3n} \sim 2 \dots \sim \Delta A_1B_1C_1,$$

Q.E.D.

J. Sukonic

⟦folio 41⟧

M357. Chứng minh rằng nếu $x + \frac{1}{y} = y + \frac{1}{z} = z + \frac{1}{x}$ thì $x = y = z$ hoặc $x^2y^2z^2 = 1$.

Từ điều kiện bài toán suy ra
$$x - y = \frac{y - z}{yz}, \quad y - z = \frac{z - x}{xz} \quad \text{и} \quad z - x = \frac{x - y}{xy}.$$

Trong hai quan hệ đầu tiên $x - y = \frac{z - x}{xyz^2}$; thay thế hiệu $z - x$ biểu thức của nó thông qua $x$ và $y$ (quan hệ cuối cùng), chúng ta thu được $x - y = \frac{x - y}{x^2y^2z^2}$. Do đó, $x = y$ và sau đó là $z - x = 0$, $y - z = 0$, tức là $x = y = z$, hoặc $1 = \frac{1}{x^2y^2z^2}$, tức là $x^2y^2z^2 = 1$.

I. Klumova

M358. Chứng minh rằng bất kỳ n đường chéo nào ($n \geqslant 4$) đều có ít nhất một đường chéo nằm hoàn toàn bên trong đường thẳng n và tìm ra số đường chéo nhỏ nhất mà một đường thẳng n có thể có là bao nhiêu ($n$ mỗi đường chéo $n$).

Hình 4.

Hình 5

Trước hết, chúng ta lưu ý rằng tất cả các đường chéo của một lớp vỏ $n$ lồi đều nằm bên trong nó và số đường chéo này bằng $\frac{n(n - 3)}{2}$. Một điều cũng rất quan trọng là với mỗi $n$ đã cho, số $\frac{n(n - 3)}{2}$ đường chéo nằm bên trong không phải là nhỏ nhất: Hình 4 cho thấy một tứ giác chỉ có một đường chéo bên trong, trong khi bất kỳ tứ giác lồi nào cũng có cả hai đường chéo bên trong.

Hãy chứng minh rằng đối với các đường chéo $n$-velovians ($n \geqslant 4$) không lồi thì có ít nhất một đường chéo nằm hoàn toàn bên trong.

Xét góc $ABC$ của góc $n$ không lồi của chúng ta, vượt quá $180^\circ$. Các tia $BA$ và $BC$, tạo thành góc này, chia toàn bộ mặt phẳng thành hai phần: phần màu xanh $I$ và phần màu trắng $II$ (xem Hình 5).

Bây giờ chúng ta lấy đỉnh của đơn vị $n$ - chúng ta biểu thị nó bằng chữ cái $D$ - nằm trong phần $II$ (có một đỉnh như vậy, vì $\widehat{ABC} > 180^\circ$); và vẽ đường chéo $BD$. Nếu đường chéo $BD$ cắt bất kỳ cạnh nào của thanh $n$ của chúng ta, thì cạnh này không nằm hoàn toàn trong phần $I$; do đó, ít nhất một trong các đầu của nó - hãy biểu thị nó bằng chữ cái $E$ - nằm trong phần $II$. Nếu đường chéo $BE$ cũng cắt một cạnh nào đó của đường $n$, thì bằng cách suy luận tương tự, chúng ta thu được rằng một trong các đầu của cạnh này nằm trong phần $II$ và chúng ta có thể vẽ đường chéo $BF$. Hãy tiếp tục quá trình này. Vì không có đỉnh nào có thể xuất hiện hai lần trong dãy của chúng ta (kiểm tra cái này) và chỉ có một số hữu hạn trong số chúng, sớm hay muộn chúng ta sẽ có một đường chéo nằm hoàn toàn bên trong đa giác.

Bây giờ chúng ta biểu thị bằng $x_n$ số đường chéo nhỏ nhất có thể nằm hoàn toàn bên trong một thanh $n$ (đối với mỗi thanh $n$; rõ ràng là một thanh $n$ có số đường chéo như vậy nhỏ nhất có thể sẽ không lồi). Rõ ràng là $x_4 = 1$ (xem Hình 4) và $x_3 = 0$ (không có đường chéo nào trong tam giác cả). Dựa trên những ví dụ này, chúng ta có thể giả sử rằng với mỗi $n$ thì số đó là $x_n = n - 3$. Hãy chứng minh điều này đúng bằng phương pháp quy nạp toán học.

Cơ sở cảm ứng. $n = 4$, $x_n = 1 = 4 - 3$.

Bước cảm ứng. Giả sử rằng với mọi $n \leqslant k$ thì phát biểu đúng: $x_5 = 5 - 3$, ..., $x_k = k - 3$. Hãy để chúng tôi chứng minh rằng $x_{k+1} = (k + 1) - 3$.

Lấy một bức tường $(k+1)$ không lồi có phạm vi nhỏ nhất có thể trong số tất cả các bức tường $(k+1)$ có số đường chéo nằm hoàn toàn bên trong và xem xét đỉnh đó

⟦folio 42⟧

B, góc vượt quá $180^\circ$. Ở trên chúng ta đã chứng minh rằng một đường chéo $BQ$ xuất phát từ một đỉnh như vậy, nằm hoàn toàn bên trong $(k+1)$-giác này. Đường chéo $BQ$ của $(k+1)$-giác của chúng ta được chia thành hai đa giác với số cạnh nhỏ hơn: $m \geq 3$ và $[(k+1)-m+2] = k-m+3$, mỗi đa giác có số lượng nhỏ nhất có thể là $(m)$-và $(k-m+3)$-giác nằm hoàn toàn bên trong môi trường đường chéo, tương ứng. Theo giả định chỉ báo, đối với đa giác đầu tiên $x_m = m-3$, đối với đa giác thứ hai $x_{k-m+3} = k-m$. Số lượng đường chéo nằm bên trong $(k+1)$-giác của chúng ta không nhỏ hơn tổng số đường chéo như vậy trong $(m)$- và $(k-m+3)$-giác, mặt phẳng một (chính đường chéo $BQ$); đó là

$$x_{k+1} \geq (m-3) + (k-m+1) = (k+1)-3.$$

Vì vậy, cho đến nay người ta đã chứng minh rằng với $n > k$ thì số đó là $x_n \geq n-3$. Mỗi $n$ đã cho vẫn phải đưa ra một ví dụ về $n$-giác, có chính xác $n-3$ đường chéo bên trong. Hãy lấy bất kỳ đường cong lồi nào $\Gamma$—như trong Hình 6 (ví dụ: paraboly) và lấy một điểm trên $\Gamma$ $n-1$. Đường cong $\Gamma$ chia toàn bộ mặt phẳng thành hai vùng: $I$ và $II$. Chúng ta hãy lấy một điểm khác trong vùng $II$ và kết nối nó với từng điểm $(n-1)$ nằm trên $\Gamma$. Chúng ta sẽ nhận được $n$-gon theo yêu cầu: dễ dàng nhận thấy không có đường chéo $n-3$ bên trong.

I. Klumova, L. Limanov

**M360*). Đối với chuỗi $a_1, a_2, a_3, \dots$, người ta biết rằng $|a_1|=1$ và $|a_{k+1}|=|a_k|+1$ cho mỗi $k=1,2,\dots$. Cộng giá trị nhỏ nhất có thể có của tổng $|a_1|+a_2|+\dots+a_k|$ nếu

a) $n=1975$;
b) $n=1976$.

Đáp số. Giá trị nhỏ nhất có thể có của tổng $|a_1+a_2+\dots+a_n|$ với $n=1975$ là 20; tại $n=1976$, bằng 24.

Lời giải. Đối với chuỗi $\{a_i\}$ từ điều kiện bài toán, chúng ta có:

$$\begin{cases}
a_1^2 = 1, \\
a_2^2 = a_1^2 + 2a_1 + 1, \\
\dots \\
a_{n+1}^2 = a_n^2 + 2a_n + 1.
\end{cases}$$

Thêm các đẳng thức này, chúng ta nhận được:

$$a_{n+1}^2 = n+1+2\sum_{i=1}^{n} a_i,$$

Ở đâu

$$\sum_{i=1}^{n} a_i = \frac{a_{n+1}^2 - (n+1)}{2}$$

(đây là số nguyên vì số $a_k$ giống với số chẵn lẻ $k$). Vì thế,

$$|a_1| + \dots + a_{1975}| = \frac{a_{1976}^2 - 1976}{2},$$

$$|a_1| + \dots + a_{1976}| = \frac{a_{1977}^2 - 1977}{2}$$

Bây giờ hãy lưu ý rằng mọi số nguyên $x$, $|x| \leq n$ có tính chẵn lẻ giống với $n$ đều có thể được nhận ra là $a_n$ đối với một số chuỗi $\{a_i\}$ (hãy tự chứng minh điều đó!). Tiếp theo, $44^2 < 1976 < 45^2$ và $44^2 < 1977 < 45^2$, rất gần với quảng trường 1976

⟦folio 43⟧

Bình phương của một số chẵn là $1936 = 44^2$ và bình phương gần nhất với 1977 của một số lẻ là $2025 = 45^2$. Do đó, tổng $|a_1 + a_2 + \ldots + a_{1975}|$ nhận giá trị nhỏ nhất $\frac{1936 - 1976}{2} = 20$ (giá trị này đạt được đối với các chuỗi như vậy $\{a_i\}$, có $|a_{1976}| = 44$) và tổng $|a_1 + a_2 + \ldots + a_{1976}|$ nhận giá trị nhỏ nhất $\frac{2025 - 1977}{2} = 24$ (đối với các chuỗi như vậy $\{a_i\}$, có $|a_{1977}| = 45$).

V. Golubyatnikov

F362. Một tụ điện nhiều lớp bao gồm ba tấm kim loại song song có diện tích S. Khoảng trống giữa các tấm chứa đầy chất điện môi có đặc tính điện môi $\varepsilon_1$ và $\varepsilon_2$ và điện trở suất $\rho_1$ và $\rho_2$. Độ dày của lớp điện môi $d_1$ và $d_2$. Tụ điện có điện áp không đổi U. Xác định điện tích của bản giữa khi dòng điện chạy trong mạch không đổi.

Hình 7.

F363. Các sợi chỉ được quấn trên hình trụ như Hình 7. Các đầu bên phải của sợi được kéo với tốc độ $v_1$, các đầu bên trái được kéo với tốc độ $v_2$. Hình trụ quay quanh trục của nó với tốc độ bao nhiêu? Bán kính của hình trụ là R.

Hình 8.

Tụ điện phân lớp này là sự kết hợp của hai tụ điện. Chúng ta hãy biểu thị hướng của điện trường trong chúng thông qua $E_1$ và $E_2$ bề mặt mật độ điện tích trên các bản của chúng - $\sigma_1$ và $\sigma_2$ và hướng đến các tụ điện - tương ứng thông qua $U_1$ và $U_2$.

Điện tích ở hai bên của tấm giữa có dấu khác nhau nên điện tích ở tấm giữa bằng

$$q = (\sigma_2 - \sigma_1) S.$$

Với sự phân bố điện tích cố định, bạn có thể sử dụng các công thức tĩnh điện. Sau đó

$$E_1 = \frac{\sigma_1}{\varepsilon_0 \varepsilon_1}, \quad E_2 = \frac{\sigma_2}{\varepsilon_0 \varepsilon_2},$$

$$U_1 = E_1 d_1, \quad U_2 = E_2 d_2, \quad U_1 + U_2 = U.$$

Mặt khác, xét về dòng điện, tụ điện có thể coi là vật dẫn điện có điện trở tương ứng là $R_1 = \rho_1 d_1 / S$ và $R_2 = \rho_2 d_2 / S$. Theo định luật Ohm

$$U_1 = I \frac{\rho_1 d_1}{S} \quad \text{и} \quad U_2 = I \frac{\rho_2 d_2}{S}.$$

Giải hệ phương trình nước thu được, ta tìm được

$$q = \frac{\varepsilon_2 \rho_2 - \varepsilon_1 \rho_1}{d_2 \rho_2 + d_1 \rho_1} \varepsilon_0 US.$$

Hình 7 thể hiện phương pháp quấn ren trên hình trụ, trong đó hình trụ có thể quay quanh trục của nó. Chúng ta hãy biểu thị bằng $\omega$ vận tốc góc của chuyển động quay này. Lần lượt trục của hình trụ chuyển động đều song song với chính nó. Hãy biểu thị tốc độ của nó bằng $v$.

Vận tốc của điểm 1 và 2 của bề mặt hình trụ có thể được biểu diễn dưới dạng tổng đại số của tốc độ tuyến tính $\omega R$ và tốc độ $v$ của chuyển động tịnh tiến của hình trụ (Hình 8):

$$v_1 = v + \omega R, v_2 = v - \omega R.$$

Từ đây

$$\omega = \frac{|v_1 - v_2|}{2R}$$

(lưu ý rằng $v_1$ và $v_2$ có dấu khác nhau).

⟦folio 44⟧

F364. Hệ số ma sát của dao cắt trên mặt ngoài của hình nón có góc ở đỉnh là 2α là bao nhiêu để một xe máy có thể chuyển động dọc theo bề mặt này đến bề mặt hình nón dọc theo một đường tròn nằm ngang bán kính R với tốc độ v (Hình 9)?

Hình 9.

Chúng tôi sẽ coi người lái xe mô tô như một điểm vật chất, từ đó loại bỏ mọi vấn đề liên quan đến sự ổn định của anh ta liên quan đến việc lật úp. Các lực tác dụng lên người lái xe mô tô được thể hiện trên Hình 9. Đó là trọng lực mg, phản lực N và lực ma sát F_TP.

Hãy viết định luật II Newton dưới dạng hình chiếu lên trục hoành và trục tung:

$$F_{Tp} \sin \alpha - N \cos \alpha = m \frac{v^2}{R},$$

$$F_{Tp} \cos \alpha + N \sin \alpha - mg = 0.$$

Lực ma sát khô của cao su lên mặt ngoài của hình nón

$$F_{Tp} \leq kN.$$

Giải hệ phương trình thu được, ta tìm được

$$k \geq \frac{gR + v^2 \mathrm{tg} \alpha}{gR \mathrm{tg} \alpha - v^2},$$

nếu $v < \sqrt{gR \mathrm{tg} \alpha}$. Nếu không, xe máy sẽ không thể di chuyển quanh đường tròn bán kính R.

B. Bukhovtsev

F365. Tìm điện dung của hệ tụ điện mắc vào như hình 10.

Hình 10.

Chúng ta hãy biểu thị bằng $U_i$ và $q_i = C_i U_i$ điện áp và điện tích trên tụ điện bằng emkomnost $C_i$ (Hình 11). Nếu nối hệ tụ điện này với một cục pin có suất điện động $\delta$ thì tổng điện dung của hệ

$$C_{06ш} = \frac{q_1 + q_2}{\mathcal{E}} = \frac{C_1 U_1 + C_2 U_2}{\mathcal{E}}.$$

(*)

Hãy viết ra các tương ứng sau (xem Hình 11):

$$U_1 + U_2 = \mathcal{E},$$

(1)

$$U_4 + U_5 = \mathcal{E},$$

(2)

$$U_1 + U_3 + U_5 = \mathcal{E}.$$

Có tính đến cực tính dự kiến ​​của điện tích trên tụ điện có emkomnost $C_3$, định luật bảo toàn điện tích, được viết cho các phần đã chọn của mạch điện (xem Hình 11), cho

$$q_1 - q_2 - q_3 = 0, \quad q_3 + q_4 - q_5 = 0.$$

Các phương trình này, sau khi thay thế các giá trị độ tương ứng, được rút gọn về dạng

$$U_1 - 2U_2 - 3U_3 = 0,$$

(4)

$$3U_3 + 2U_4 - U_5 = 0.$$

Giải hệ phương trình (1) - (5), ta tìm được các điện áp $U_1$ và $U_2$:

$$U_1 = \frac{5}{9} \mathcal{E}, \quad U_2 = \frac{4}{9} \mathcal{E}.$$

Cuối cùng, theo biểu thức (*), ta có

$$C_{06ш} = \frac{C_1 U_1 + C_2 U_2}{\mathcal{E}} = \frac{13}{9} C.$$

V. Belonukkin

⟦folio 45⟧

F366. Bình cầu có dung tích $V=1$ l được mở và đóng lại. Một lớp không khí đơn phân tử vẫn còn trên thành bình. Tính áp suất trong bình ở nhiệt độ lên tới 300°C, nếu bạn biết rằng ở nhiệt độ này thành bình đã được khử nhiễm hoàn toàn.

Số lượng phân tử còn lại trên thành bình xấp xỉ $N \sim \frac{4\pi R^2}{d^2}$, trong đó $R \approx 0,06$ m là bán kính của bình, $d \sim 10^{-10}$ m là đường kính của phân tử khí. Sau khi khử trùng thành bình, nồng độ các phân tử trong bình sẽ bằng

$$n = \frac{N}{V} \sim \frac{3}{d^2 R},$$

và áp suất mong muốn

$$p = nkT \sim \frac{3kT}{d^2 R} \approx 40 \text{ н/м}^2.$$

Ở đây $k = 1,38 \cdot 10^{-23}$ j/srad là hằng số Boltzmann, $T \approx 600^\circ\text{K}$.

Hãy so sánh áp suất thu được với áp suất khí quyển bình thường $p_0 \approx 10^5 \text{ н/м}^2$:

$$\frac{p}{p_0} \approx \frac{40}{10^5} \sim 10^{-4}.$$

Ví dụ đơn giản này cho thấy “chân không” ở trạng thái kín có thể xuống cấp đến mức nào nếu thành bình không được khử trùng trước.

A. Mitrofanov

F367. Tạo ảnh của một hình vuông cho bởi thấu kính hội tụ (Hình 12). Giữa cạnh của hình vuông nằm trên trục chính của thấu kính, cách thấu kính một khoảng bằng tiêu cự.

Để tạo ảnh của một hình vuông, cách thuận tiện nhất là sử dụng các tia đi qua tiêu điểm của thấu kính. Điều cần thiết nhất trong số đó là tia $ABGF$ (Hình 12), chạy dọc theo cạnh trên của hình vuông, vì ảnh của tất cả các điểm trên cạnh này phải nằm trên chính tia $GF$ hoặc phần tiếp theo của nó. Chúng ta cũng hãy xây dựng đường đi của tia $AM$, đi qua tiêu điểm bên trái $F$ của thấu kính và tia $BN$, như thể nổi lên từ cùng một tiêu điểm. Sau thấu kính, cả hai tia đi song song với trục chính của thấu kính.

Hình 12.

Ảnh thật $A'$ của điểm $A$ nằm ở giao điểm của tia $GF$ và $MA'$. Tương tự, ảnh nhỏ nhất $B'$ của điểm $B$ nằm ở giao điểm của phần mở rộng của tia

⟦folio 46⟧

Của ai $GF$ và $NH$. Để xác định hình ảnh $C'$ và $D'$ của các điểm tương ứng $C$ và $D$, việc hạ đường vuông góc từ $A'$ và $B'$ xuống trục quang chính là đủ. Ảnh của các cạnh $AC$ và $BD$ vuông góc với trục quang của thấu kính thì phải vuông góc với trục quang.

Để xây dựng đường đi của tia $AM$ và $BN$, chúng tôi phải mở rộng thấu kính theo cả hai hướng như thể nó lớn hơn kích thước. Điều này có thể được thực hiện trên cơ sở rằng bất kỳ bộ phận nào của ống kính đều tạo ra hình ảnh giống như toàn bộ ống kính (sự khác biệt giữa ống kính là độ chiếu sáng).

Như vậy, ảnh của hình vuông gồm hai phần: phần thực (phần góc bên phải của $A'$ $C'$) và cực tiểu (phần góc bên trái của $B'$ $D'$). phần thật là ảnh của nửa hình vuông nằm xa hơn mặt phẳng tiêu cự, phần tối thiểu là ảnh của nửa hình vuông nằm sát mặt phẳng tiêu cự của thấu kính.

B. Bukhovtsev

F368. Một tên lửa có khối lượng $m$ bắt đầu nghiêng một góc $\alpha$ so với đường chân trời. Công việc trong t giây có làm di chuyển các gói hàng, tạo ra lực đẩy $F$ và đảm bảo chuyển động tuyến tính của các gói hàng không. Bỏ qua sự thay đổi khối lượng của gói và sức cản không khí, xác định độ cao $h$ tại đó động cơ dừng hoạt động.

Đối với lời giải bài toán, chúng tôi sẽ giả sử rằng hệ thống báo cáo liên quan đến Trái đất là quán tính và chuyển động của gói hàng bị giới hạn trong không gian nơi gia tốc rơi tự do $g$ không đổi.

Chúng ta hãy viết phương trình chuyển động của các gói trong quá trình chuyển động của nó:

$$m a = m g + F = R.$$

Ở đây $a$ là gia tốc của gói, $R$ là lực bằng nhau tác dụng lên gói. Từ điều kiện bài toán và giả định quán tính của hệ thống báo cáo đã chọn, suy ra rằng lực $R$ (cũng như gia tốc $a$) phải không đổi trong suốt thời gian chuyển động và tạo một góc $\alpha$ với đường chân trời (Hình 13). Do đó, độ cao $h$ mà tại đó gói tăng lên theo thời gian $t$ bằng

$$h = \frac{a_y t^2}{2} = \frac{R_y t^2}{2 m},$$

trong đó $a_y$ và $R_y$ là hình chiếu của vectơ $a$ và $R$ lên trục tọa độ $OY$, hướng thẳng đứng lên trên.

Như có thể thấy trong Hình 13, đẳng thức phải được thỏa mãn

$$(R_y + m g)^2 + (R_y \text{ctg} \alpha)^2 = F^2.$$

Từ đây

$$R_y = m g \left( \sqrt{(F/mg)^2 - \cos^2 \alpha} - \sin \alpha \right) \sin \alpha,$$

và cuối cùng

$$h = \frac{R_y t^2}{2 m} = \frac{g t^2}{2} \left( \sqrt{(F/mg)^2 - \cos^2 \alpha} - \sin \alpha \right) \sin \alpha.$$

V. Pozozhev
