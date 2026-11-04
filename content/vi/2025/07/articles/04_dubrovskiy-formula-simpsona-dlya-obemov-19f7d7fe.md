---
id: 2025-7-dubrovskiy-formula-simpsona-dlya-obemov-19f7d7fe
issue: kvant_2025_7
year: 2025
number: "7"
title: Công thức tính thể tích của Simpson
authors:
  - Дубровский В. Н.
rubric: osnovnye-stati
page_first: 12
page_last: 19
page_labels: 11, 12, 13, 14, 16, 17
lang: vi
source: kvant_digital
extraction: vision
content_sha256: e8ef238281036f8988fe5916df32c2f10592a347d2b5cbec58c79baa83daa707
prompt_sha256: draft-1
translated_from: content/ru/2025/07/articles/04_dubrovskiy-formula-simpsona-dlya-obemov-19f7d7fe.md
source_content_sha256: dd7896e620dfff86d15dfb209361f3708035a70265c927b09bf429481e4a0525
translation_model: draft
translation_run: vi-draft-gaps-2026-11-04
translation_quality: draft
---

⟦folio none⟧

---
running_head:
folio:
---

Công thức Simpson
cho khối lượng
V. DUBROVSKY

TRONG HÌNH 1 BẠN THẤY KHÔNG-
có bao nhiêu khối đa diện khác nhau
trong đó có một xã hội: tất cả chúng
các đỉnh nằm trong hai mặt phẳng song song. Hóa ra khối lượng của tất cả những thứ này
cơ thể và nhiều cơ thể khác, chúng hoàn toàn không thể hiểu được
những cái đang chạy, có thể được tìm thấy bằng cách sử dụng một và
công thức tương tự, pha chế với một mini-
do tôi tính toán và không sử dụng inte-
sự phân nhánh. Về công thức này và ứng dụng của nó
chúng tôi và rasケjem.

Một công thức cho các cơ thể khác nhau
Công thức tính khối lượng được nhận dạng và sử dụng
các bộ trưởng ngoại giao được nhiều người biết đến - họ được giữ ở
trường học. Chúng giống nhau, chỉ có hệ số của chúng là khác nhau:

$$V_{\text{призмы}} = SH, V_{\text{пирамиды}} = \frac{1}{3} SH,$$

trong đó $S$ là diện tích đáy, $H$ là chiều cao. Điều thú vị là có một công thức tương tự cho “nhận dạng theo chiều ngang” -
đặc điểm hình tam giác, trong đó mặt bên được lấy làm “cơ sở” (xem hình 1, $\theta$).

Bài tập 1. Chứng minh rằng thể tích của một cạnh tam giác có thể được tìm bằng công thức $\frac{1}{2} SH$, trong đó $S$ là diện tích của một trong các mặt bên của nó và $H$ là khoảng cách giữa mặt này và cạnh bên đối diện.

Hình 1. a) Lăng kính, b) hình chóp, b) “lăng kính ngang”, d) hình chóp cụt

Hai mặt phẳng chứa tất cả các đỉnh của đa giác được gọi là các mặt phẳng hỗ trợ.
mi¹. Để thuận tiện, chúng ta sẽ giả sử rằng chúng nằm ngang - một cái ở dưới, cái kia ở trên. Các phần của ranh giới của một khối đa diện nằm trong bất kỳ mặt phẳng nào trong số này sẽ được gọi là các đáy của nó - dưới và trên (đáy có thể là một mặt, một đỉnh hoặc một cạnh). Các mặt không phải là đáy sẽ được gọi là mặt bên và khoảng cách giữa các mặt phẳng sẽ được gọi là chiều cao.

Rõ ràng là công thức thể tích phổ quát phải bao gồm diện tích của cả hai đáy và đối xứng. Nhưng điều này vẫn chưa đủ: hãy so sánh các công thức của kim tự tháp và “nhận dạng theo chiều ngang”. Chúng ta hãy thêm vào các đối số của công thức - chiều cao $H$ và diện tích $S_{\text{H}}$ và $S_{\text{B}}$ của đáy dưới và đáy trên - một tham số nữa: diện tích $S_{\text{cp}}$ ở giữa phần, tức là các phần của một vật thể theo mặt phẳng song song với các đáy và cách đều chúng.

Bài tập
2. Ta sẽ tìm công thức tổng quát có dạng
$$V = \left(kS_{\text{H}} + lS_{\text{cp}} + kS_{\text{B}}\right)H$$
đối với một số $k$ và $l$. Chọn hệ số $k$ và $l$ để công thức có cả hai đặc điểm

⟦folio 11⟧

---
running_head:
folio:
---

và các thông số. Kiểm tra xem với các hệ số này, nó có đưa ra biểu thức chính xác cho âm lượng của “nhận dạng ngang” hay không và nếu thành công, các tham số sẽ được chuyển đổi thành công thức nổi tiếng $V = \frac{H}{3} \left( S_H + \sqrt{S_H S_B} + S_B \right)$.

3. Chứng minh rằng công thức bạn tìm được đưa ra các giá trị đúng cho thể tích của các vật thể hiển thị trong hình 2.

Hình 2. a) “Tứ diện trên một cạnh”, b) phản lăng kính tam giác hay còn gọi là bát diện, c) “obelisk”

Đã đến lúc chúng ta tiết lộ bí mật. Thể tích của tất cả các vật thể thể hiện trong Hình 1 và 2 có thể được tính bằng công thức

$$V = \frac{H}{6} \left( S_H + 4 S_{cp} + S_B \right).$$

Nó được gọi là công thức Simpson (đối với thể tích)$^2$.

Công thức Simpson
đối với đặc điểm lồi

Một khối đa diện có tất cả các đỉnh nằm trên hai mặt phẳng song song được gọi là khối đa diện. Hãy chứng minh định lý sau đây.

Định lý 1. Thể tích của một đặc trưng lồi tùy ý có thể được tìm bằng công thức Simpson.

Để chứng minh điều đó, chỉ cần chúng ta biết các công thức nhận biết và các tham số là đủ. Thuộc tính sau đây đóng một vai trò quan trọng ở đây.

Tính chất thích ứng. Nếu công thức của Simpson đúng cho một số viên phấn không chồng lên nhau với một cặp mặt phẳng tham chiếu chung, thì nó cũng có giá trị cho sự thống nhất của chúng.

Thật vậy, thể tích, diện tích của các đáy và diện tích của bất kỳ phần nào của tập hợp đều bằng tổng khối lượng và tương tự

$^2$ Công thức bột này có liên quan đến một công thức Simpson khác - để tính gần đúng các tích phân, nhưng chúng tôi không đề cập đến chủ đề này ở đây.

lĩnh vực của từng thành phần của hiệp hội các cơ quan này.

Và ngược lại: nếu biết rằng trong cùng một tình huống, công thức được áp dụng cho liên minh và tất cả các cơ quan cấu thành của nó ngoại trừ một cơ quan, thì nó được áp dụng cho cơ thể cuối cùng này.

Hình 3 giải thích tính hấp dẫn của công thức Simpson và khả năng ứng dụng của nó như thế nào

Nếu bạn áp dụng nó cho một hình vuông và một hình tứ giác nguyên thủy, bạn có thể suy ra rằng nó được áp dụng cho một “đặc điểm nằm ngang” và xa hơn nữa là cho một “tứ diện trên một cạnh”.

Bài tập 4. Chứng minh rằng thể tích của “tứ diện trên một cạnh” bằng $\frac{2}{3} S_{cp} H = \frac{1}{6} abH \sin \varphi$, trong đó $H$ là “chiều cao”, tức là khoảng cách giữa các cạnh đối diện-đáy, $a$ và $b$ – độ dài của chúng, $\varphi$ – góc giữa chúng.

Chứng minh Định lý 1. Xét một hàm lồi tùy ý. Chúng ta có thể giả sử rằng ít nhất một trong các đáy của nó, theo định nghĩa, đáy dưới $B$, không suy biến, tức là là một đa giác (nếu không thì lăng trụ là một “tứ diện trên một cạnh”, mà công thức đã được chứng minh). Chúng ta hãy đánh dấu một điểm tùy ý $P$ bên trong đa giác $B$. Sau đó, do tính lồi, lăng kính có thể được chia thành các khối nguyên thủy có cùng một đỉnh $P$, các đáy của nó là các mặt của nó khác với $B$. Nếu đáy trên của nguyên mẫu cũng không suy biến thì nó sẽ là đáy của một trong các nguyên mẫu này, và đáy của các nguyên mẫu còn lại sẽ là các mặt bên của nguyên mẫu, tức là hình tam giác hoặc hình thang. Chúng ta sẽ chia mỗi hình thang thành các hình tam giác theo đường chéo, sao cho cuối cùng tất cả các khối nguyên thủy của phân hoạch sẽ là các khối nguyên thủy có đáy nằm trong một và một đỉnh nằm trong một mặt phẳng tham chiếu khác, hoặc là “tứ diện trên một cạnh” đối với

⟦folio 12⟧

---
running_head:
folio:
---

máy bay hỗ trợ mạnh mẽ. Do đó, tất cả chúng, và do đó, sự kết hợp của chúng, đều thỏa mãn công thức Simpson. Q.E.D.

Nguyên lý và điều kiện Cavalieri trên mặt cắt ngang

Công thức của Simpson không chỉ được áp dụng cho các hình lăng trụ mà còn cho các “vật tròn” của hình học trường học - một hình trụ, một hình nón và bất ngờ là cho một quả bóng (các mặt phẳng đỡ của quả bóng là hai mặt phẳng tiếp tuyến song song bất kỳ). Để kiểm tra, bạn có thể sử dụng các công thức cho đối tượng của mình đã biết trong sách giáo khoa. Ví dụ: đối với một quả bóng có bán kính $R$ chúng ta có

$$H = 2R, S_H = S_B = 0, S_{cp} = \pi R^2,$$

$$V = \frac{2R}{6} \left( 0 + 4\pi R^2 + 0 \right) = \frac{4}{3} \pi R^3.$$

Nhưng tiêu chí thú vị hơn (và hữu ích hơn) là chúng ta không mở sách giáo khoa, không biết các công thức và có thể trực tiếp chứng minh khả năng ứng dụng của công thức Simpson cho các vật thể này. Ở đây nguyên tắc Cavalieri giúp chúng ta, trong nhiều trường hợp, thay thế sự nội tâm hóa. Ví dụ: nó bao gồm những gì (xem [1]–[3]).

Priicip Cavalieri. Nếu bất kỳ mặt phẳng nào song song với mặt phẳng này và bị cắt bởi hai vật thể có diện tích bằng nhau thì thể tích của chúng bằng nhau.

Theo nguyên tắc này, chỉ cần chọn các lăng trụ cùng với hình trụ, hình nón hoặc quả bóng sẽ lần lượt thỏa mãn các điều kiện của nguyên lý Cavalieri là đủ.

Trong trường hợp hình trụ hoặc hình nón, mọi thứ đều đơn giản: như một hình lăng trụ như vậy, người ta có thể lấy tương ứng một lăng kính hoặc một paramid có cùng chiều cao và cùng diện tích đáy. Trường hợp bóng phức tạp hơn một chút. Trước hết, chúng ta tìm diện tích $S_{III}(h)$ của mặt cắt của nó theo mặt phẳng $\alpha(h)$ (hình 4, a), song song với các mặt phẳng đỡ và nằm cách mặt phẳng bên dưới một khoảng $h$. Gọi bán kính của quả bóng là $R$. Sau đó

$$S_{III}(h) = \pi r^2 = \pi \left( R^2 - (R - h)^2 \right) = \pi h (2R - h).$$

Hình 4

Sau khi thực hiện các bài tập sau, bạn sẽ tin rằng mình có thể ghép một quả bóng với một “tứ diện trên một cạnh” và chúng ta sẽ ngay lập tức chứng minh một định lý tổng quát hơn.

Bài tập 5 (xem bài toán M1211 "Bài toán Kvant]). Xét một “tứ diện trên một cạnh”, các mặt phẳng đỡ của nó tiếp xúc với một quả cầu có bán kính $R$ (hình 4, b). Chứng minh rằng diện tích $S(h)$ của tiết diện tứ diện này với mặt phẳng $\alpha(h)$ bằng $\frac{(2R - h)h}{R^2} S_{cp}$, trong đó $S_{cp}$ là diện tích của phần giữa. Với giá trị nào $S_{cp}$ thì tiết diện của hình tứ diện có kích thước bằng tiết diện tương ứng của quả bóng?

Diện tích mặt cắt ngang $S_{III}(h)$ của quả bóng được biểu thị dưới dạng hàm bình phương của $h$. Hóa ra điều kiện này, bất kể dạng hàm cụ thể nào, đều đủ để áp dụng công thức Simpson.

Định lý 2. Giả sử một vị trí nhất định được hỗ trợ bởi các mặt phẳng $\alpha$ và $\beta$, và đặt diện tích $S(h)$ của mặt cắt ngang của nó, nằm ở độ cao $h$ phía trên mặt phẳng hỗ trợ dưới $\alpha$, được biểu thị bằng đa thức bậc không lớn hơn 2 trong $h$. Vậy thì nơi này thỏa mãn công thức của Simpson.

Người đọc quen với phép nội suy có thể tính tích phân của hàm $s(x) = Ax^2 + Bx + C$ và trực tiếp thấy rằng

$$\int_a^b s(x) dx = \frac{b - a}{6} \left( s(a) + 4s\left(\frac{a + b}{2}\right) + s(b) \right)$$

(trên thực tế, đẳng thức này đúng với đa thức bậc không lớn hơn 3).

Chúng tôi sẽ đưa ra một bằng chứng hình học.

⟦folio 13⟧

---
running_head:
folio:
---

Hình 5

Chứng minh Định lý 2. Khoảng cách giữa ba đối tượng đơn giản nhất với mặt phẳng tham chiếu $\alpha$ và $\beta$ (hình 5): (lật) paramid và “đối tượng nằm ngang”, cơ sở của chúng nằm trong mặt phẳng $\beta$ và nhận biết. Chúng ta hãy biểu thị bằng $S_1, S_2$ và $S_3$ diện tích các căn cứ của chúng. Diện tích mặt cắt ngang của các vật thể này theo mặt phẳng $\alpha(h)$ lần lượt bằng $Ah^2, Bh$ và $C$, trong đó $A = \frac{S_1}{H^2}, B = \frac{S_2}{H}, C = S_3$ ($H$ là khoảng cách giữa các mặt phẳng $\alpha$ và $\beta$). Do đó, có thể chọn diện tích các đáy để biểu diễn hàm này có dạng $S(h) = Ah^2 + Bh + C$ với các hệ số không âm là diện tích tiết diện theo mặt phẳng $\alpha(h)$ của hợp của cả ba vật thể này hoặc một số vật thể này. Theo nguyên lý Cavalieri, thể tích của bất kỳ vật thể $T$ nào có diện tích tiết diện $S(h)$ tại $0 \leq h \leq H$ bằng thể tích của phần hợp này, và do tính hấp dẫn của công thức Simpson nên nó cũng đúng với $T$. Nếu một hệ số nào đó âm thì thể tích và diện tích mặt cắt ngang tương ứng trong quá trình cộng phải được tính bằng dấu trừ. Định lý đã được chứng minh.

Sử dụng định lý đã được chứng minh, chúng ta có thể mở rộng lớp vật thể chứa công thức Simpson.

Tính năng tổng quát

Cho có một số đoạn $A_iB_i$, $i = 1, 2, ..., n$ nối các điểm $A_i$ của mặt phẳng $\alpha$ với điểm $B_i$ của mặt phẳng $\beta$ song song với nó và các đoạn không giao nhau theo cặp nhưng các đầu của chúng có thể trùng nhau. Chúng ta hãy biểu thị bằng $C_i$ điểm giao nhau của đoạn $A_iB_i$ với mặt phẳng tùy ý $\gamma$ song song với $\alpha$ và $\beta$ (và vị trí giữa $\alpha$ và $\beta$). Nếu đối với tất cả các mặt phẳng như vậy $\gamma$ các đường đứt đoạn khép kín $C_1...C_n$ không tự giao nhau thì sự kết hợp của các đa giác giới hạn sẽ được gọi là đặc điểm tổng quát với các cạnh bên $A_iB_i$. Hãy chứng minh định lý sau đây.

Định lý 3. Công thức Simpson có thể áp dụng cho mọi khái quát hóa.

Bằng chứng. Nó đủ để chứng minh rằng diện tích của phần $C_1...C_n$ phụ thuộc bậc hai vào chiều cao của nó trên $\alpha$. Chúng ta hãy tưởng tượng rằng mặt phẳng $\gamma$ chuyển động đều từ $\alpha$ đến $\beta$. Sau đó, mỗi điểm $C_i$ sẽ di chuyển đều từ $A_i$ đến $B_i$. Chiếu một phần trên $\alpha$, chúng ta thu được một đa giác bằng nó, mỗi đỉnh của nó di chuyển đều dọc theo một đường thẳng nhất định từ $A_i$ đến hình chiếu $B_i$. Hóa ra là trong trường hợp này, diện tích định hướng $[C_1...C_n]$ của đa giác thay đổi theo phương trình bậc hai (hoặc có thể là tuyến tính). Để không bị phân tâm, cuối cùng chúng ta sẽ chứng minh sự thật quan trọng này và bây giờ chúng ta sẽ chỉ chứng minh rằng $[C_1...C_n]$ là diện tích của đa giác, được lấy bằng dấu phẳng nếu việc đi qua ranh giới của nó theo thứ tự $C_1, C_2, ..., C_n, C_1$ xảy ra ngược chiều kim đồng hồ và có dấu trừ nếu theo chiều kim đồng hồ. Vì khi di chuyển từ $\alpha$ đến $\beta$, phần $C_1...C_n$ vẫn là một đa giác nên diện tích (thông thường) của nó luôn dương, có nghĩa là vùng định hướng $[C_1...C_n]$ không biến mất khi di chuyển và do đó, giữ nguyên dấu của nó. Do đó, giá trị tuyệt đối của nó, bằng tổng diện tích, cũng thay đổi theo phương trình bậc hai, từ đó, theo Định lý 2, suy ra công thức Simpson có thể áp dụng được cho việc khái quát hóa. Định lý 3 đã được chứng minh.

Đặc biệt, Định lý 3 mở rộng công thức Simpson cho các tính chất không lồi. Nhưng không chỉ vậy. Kết quả thu được cho phép người ta tìm thể tích của các vật thể khá kỳ lạ, không phải đa giác, hầu như không cần tính toán.

khối tứ diện quay

Chúng ta hãy xem xét vật thể tạo ra từ sự tăng dần của một tứ diện đều $ABCD$ có cạnh $a$ xung quanh trục đối xứng của nó - một đường thẳng nối các trung điểm của đối diện

⟦folio 14⟧

---
running_head:
folio:
---

các cạnh dương $AB$ và $CD$ (hình 6). Khi quay, các xương sườn này tự quét hai vòng tròn (phần đế của thân) và mỗi xương sườn còn lại sẽ quét một bề mặt nhất định, giống nhau đối với tất cả các xương sườn (mặt bên). Những gì bạn có thể thấy là sự chia của một khối tứ diện cho một mặt phẳng song song với $AB$ và $CD$. Đây là một hình chữ nhật có tâm nằm trên trục đối xứng, do đó, tất cả các đỉnh của nó khi xoay sẽ mô tả cùng một đường tròn - một phần bề mặt bên của vật thể đang được xem xét. Có thể chứng minh rằng bề mặt này là một hyperboloid quay (chính xác hơn là một phần của nó). Nhưng thực tế này cũng như cách tính diện tích mặt cắt ngang theo sau là tích phân đều không cần thiết để tìm được thể tích cần thiết! Hãy xem xét các vị trí mà cạnh $AC$ sẽ chiếm trong các lần quay liên tiếp qua góc $\frac{2\pi}{n}$: $A_1C_1 = AC, A_2C_2, \ldots, A_nC_n$ và xem xét đặc điểm thể tích $\Pi_n$ với cạnh bên $A_iC_i$ (hình 7 cho $n = 6$). Bất kỳ mặt cắt ngang nào $\Pi_n$ đều là một $n$-giác đều nội tiếp trong một vòng tròn dọc theo đó mặt phẳng cắt giao với vật quay của chúng ta. Do đó, ở $n \rightarrow \infty$ thể tích của vật thể và diện tích của bất kỳ phần nằm ngang nào của nó có xu hướng bằng thể tích và diện tích của phần vật thể quay trong cùng một mặt phẳng. Chúng tôi áp dụng công thức Simpson

đến $\Pi_n$ và vẫn có hiệu lực khi vượt đến giới hạn. Vì vậy, nó được áp dụng cho cơ thể đang được kiểm tra. Bây giờ bạn có thể tính toán khối lượng của nó. Dễ dàng nhận thấy rằng chiều cao của nó (khoảng cách giữa các cạnh đối diện của tứ diện) là $H = \frac{a}{\sqrt{2}}$, diện tích các đáy là $S_H = S_B = \frac{\pi a^2}{4}$, và diện tích phần giữa là $S_{cp} = \frac{\pi a^2}{8}$, từ đó

$$V = \frac{a}{6\sqrt{2}} \left( \frac{2\pi a^2}{4} + \frac{4\pi a^2}{8} \right) = \frac{\pi a^3}{6\sqrt{2}}.$$

Bài tập 6. Tìm thể tích của vật thể được hình thành bằng cách xoay một khối lập phương có cạnh $a$ quanh đường chéo của nó.

"Thỏa mãn ba chiều"

Phương pháp tìm thể tích được sử dụng ở phần trước có thể được áp dụng cho phần thân $T$, một bề mặt giới hạn được hình thành bởi các đoạn có độ dài không đổi $L$ với các đầu nằm trên hai đường vuông góc giao nhau $a$ và $b$, nằm cách nhau một khoảng $H$ (hình 8).

Một lần nữa, phần thân $T$ có thể được ước tính gần đúng với bất kỳ độ chính xác nhất định nào bằng đặc điểm thể tích, các cạnh bên của nó là các đoạn $A_iB_i$ có chiều dài $L$ với các đầu ở $a$ và $b$, được vẽ “khá dày đặc”. Do đó, công thức Simpson có thể áp dụng cho vật $T$. Chúng ta biết chiều cao của nó $H$ và diện tích của “đế” $S_H = S_B = 0$; phần dưới của phần giữa vẫn còn. Mặt phẳng $\gamma$ của phần này cắt từng đoạn $AB$ ở giữa của nó, do đó, phần này là quỹ tích các trung điểm $M$ của các đoạn $AB$ có chiều dài $L$, tạo thành ranh giới $T$. Hãy để $PQ = H$,

⟦folio 16⟧

---
running_head:
folio:
---

ron từ $AB$ (hình 10 từ bên phải), $\angle B'AC > 90^\circ$, $\cos \angle B'AC < 0$ và $[ABC] < 0$.

Việc sử dụng sản phẩm nghiêng dựa trên hai đặc tính quan trọng của thao tác này.

1) Đối xứng nghiêng: $\vec{a} \vee \vec{b} = -(\vec{b} \vee \vec{a})$ (tên của thao tác xuất phát từ thuộc tính này).

Chúng ta hãy rút ra tính chất này trực tiếp từ định nghĩa. Lưu ý rằng $R(\vec{u}) \cdot R(\vec{v}) = \vec{u} \cdot \vec{v}$ đối với mọi vectơ $\vec{u}, \vec{v}$. Do đó, $\vec{a} \vee \vec{b} = R(\vec{a}) \cdot \vec{b} = R(R(\vec{a})) \cdot R(\vec{b}) = -\vec{a} \cdot R(\vec{b}) = -(\vec{b} \vee \vec{a})$, nơi chúng tôi đã lợi dụng thực tế là thành phần của hai lượt bật $90^\circ$ là một lượt bật $180^\circ$.

2) Tính tuyến tính trong các lập luận tổng quát:
$$\vec{a} \vee (\vec{b}_1 + \vec{b}_2) = \vec{a} \vee \vec{b}_1 + \vec{a} \vee \vec{b}_2$$
$$\vec{a} \vee (k\vec{b}) = k(\vec{a} \vee \vec{b}), k \in \mathbb{R},$$
và các đẳng thức tương tự cho “chủ thể” đầu tiên.

Do tính đối xứng lệch nên chỉ cần chứng minh các đẳng thức này cho đối số thứ hai là đủ. Và đối với anh ta, họ trực tiếp suy ra các tính chất tương tự của tích vô hướng. Ví dụ,
$$\vec{a} \vee (\vec{b}_1 + \vec{b}_2) = R(\vec{a}) \cdot (\vec{b}_1 + \vec{b}_2) = R(\vec{a}) \cdot \vec{b}_1 + R(\vec{a}) \cdot \vec{b}_2 = \vec{a} \vee \vec{b}_1 + \vec{a} \vee \vec{b}_2.$$
Hãy quay trở lại Bổ đề 1.

Chứng minh bổ đề 1. Chúng ta sử dụng tính tuyến tính để chứng minh diện tích định hướng của tam giác $OAB$ có các đỉnh $A$ và $B$ chuyển động với vận tốc không đổi $\vec{v}$ và $\vec{u}$ phụ thuộc bậc hai theo thời gian. Chúng ta hãy biểu thị vị trí của các đỉnh $A$ và $B$ tại thời điểm $t$ bằng $A_t$ và $B_t$, sau đó
$$\overrightarrow{OA_t} = \overrightarrow{OA_0} + \vec{v}t, \overrightarrow{OB_t} = \overrightarrow{OB_0} + \vec{u}t$$
$$[OA_tB_t] = \frac{1}{2}(\overrightarrow{OA_0} + \vec{v}t) \vee (\overrightarrow{OB_0} + \vec{u}t).$$

Mở dấu ngoặc ở biểu thức cuối cùng, chúng ta có được một hình tam giác vuông. (Lưu ý rằng hệ số của nó tại $t^2$ sẽ chỉ bằng 0 tại $\vec{v} \vee \vec{u} = 0$, tức là khi vận tốc thẳng hàng, nói cách khác, khi các điểm di chuyển dọc theo các đường thẳng song song hoặc trùng nhau.)

Diện tích định hướng của một đa giác tùy ý $A_1A_2 \dots A_n$ được cho bởi5
$$[A_1A_2 \dots A_n] = \frac{1}{2}(\overrightarrow{OA_1} \vee \overrightarrow{OA_2} + \overrightarrow{OA_2} \vee \overrightarrow{OA_3} + \dots + \overrightarrow{OA_{n-1}} \vee \overrightarrow{OA_n} + \overrightarrow{OA_n} \vee \overrightarrow{OA_1}),$$
trong đó $O$ là điểm bất kỳ trên mặt phẳng. Nói cách khác,
$$[A_1A_2 \dots A_n] = [OA_1A_2] + [OA_2A_3] + \dots + [OA_{n-1}A_n] + [OA_nA_1].$$

Lưu ý rằng tổng ở phía bên phải rõ ràng không phụ thuộc vào đỉnh nào mà nó bắt đầu từ đó (trong khi vẫn giữ nguyên thứ tự) và khi hướng đi qua các đỉnh bị thay đổi, tổng chỉ thay đổi dấu. Không rõ nó không phụ thuộc vào việc chọn điểm $O$. Hãy kiểm tra xem điều này có thực sự đúng hay không, tức là chúng ta hãy thiết lập tính đúng đắn của định nghĩa này.

Hãy viết số hạng đầu tiên cho một điểm khác $O'$ và biến đổi nó bằng cách sử dụng các thuộc tính của tích nghiêng:
$$\overrightarrow{O'A_1} \vee \overrightarrow{O'A_2} = \left(\overrightarrow{O'O} + \overrightarrow{OA_1}\right) \vee \left(\overrightarrow{O'O} + \overrightarrow{OA_2}\right) = \overrightarrow{O'O} \vee \overrightarrow{O'O} + \overrightarrow{O'O} \vee \left(\overrightarrow{O'A_2} - \overrightarrow{O'A_1}\right) + \overrightarrow{OA_1} \vee \overrightarrow{OA_2} = \overrightarrow{O'O} \vee \overrightarrow{A_1A_2} + \overrightarrow{OA_1} \vee \overrightarrow{OA_2}.$$

5 Xem thêm bài [5]. Một cách tiếp cận phối hợp hơi khác một chút để xác định và suy ra các thuộc tính của một vùng định hướng đã được sử dụng trong bài báo [6]. Ý nghĩa hình học và vật lý của vùng định hướng trong trường hợp đường đứt đoạn tự giao nhau được thảo luận trong bài viết [7].

⟦folio 17⟧

---
running_head:
folio:
---

Chúng ta viết lại các số hạng còn lại một cách tương tự và cộng tất cả các đẳng thức $n$ theo từng số hạng:
$$\overrightarrow{O'A_1} \vee \overrightarrow{O'A_2} + \ldots + \overrightarrow{O'A_n} \vee \overrightarrow{O'A_1} =$$
$$= \overrightarrow{O'O} \vee \left( \overrightarrow{A_1A_2} + \ldots + \overrightarrow{A_nA_1} \right) + \overrightarrow{OA_1} \vee \overrightarrow{OA_2} + \ldots$$
$$\ldots + \overrightarrow{OA_n} \vee \overrightarrow{OA_1}.$$
Vì $\overrightarrow{A_1A_2} + \ldots + \overrightarrow{A_nA_1} = 0$, vế phải bằng $\overrightarrow{OA_1} \vee \overrightarrow{OA_2} + \ldots + \overrightarrow{OA_n} \vee \overrightarrow{OA_1}$, có nghĩa là định nghĩa đúng.
Cụ thể, trong trường hợp tam giác $ABC$, định nghĩa này tại $O = A$ vượt quá công thức mà chúng ta đã bắt đầu:
$$[ABC] = \frac{1}{2} \overrightarrow{AB} \vee \overrightarrow{AC}.$$
Thực tế là khi các điểm $A_1, A_2, \ldots, A_n$ di chuyển đều dọc theo các đường thẳng, diện tích định hướng $[A_1A_2 \ldots A_n]$ được biểu thị bằng đa thức bậc không cao hơn 2 theo thời gian trực tiếp từ định nghĩa: ở trên chúng ta đã chứng minh điều đó cho bất kỳ tam giác nào có hai đỉnh di chuyển và $[A_1A_2 \ldots A_n]$ là tổng diện tích định hướng của các tam giác $OA_1A_2, OA_2A_3, \ldots$. Bổ đề 1 đã được chứng minh.

Bài tập

7. Chứng minh diện tích định hướng của hình bình hành $ABCD$ bằng $\overrightarrow{AB} \vee \overrightarrow{AD}$, và đối với hình tứ giác tùy ý là $[ABCD] = \frac{1}{2} \overrightarrow{AC} \vee \overrightarrow{BD}.$

8. Các đỉnh của tam giác di chuyển dọc theo những đường thẳng đó với tốc độ không đổi; tại thời điểm $t$ chúng đang ở điểm $A_t, B_t, C_t$. Chứng minh rằng nếu tam giác $A_1B_1C_1$ đồng dạng với tam giác $A_0B_0C_0$ và các tam giác này ngược hướng thì
$$[A_tB_tC_t] = (1-t)^2 [A_0B_0C_0] + t^2 [A_1B_1C_1].$$
Vẫn còn phải chứng minh một tính chất nữa mà chúng ta sử dụng liên quan đến công thức Simpson.

Bổ đề 2. Diện tích “tổng” của một đa giác bằng giá trị tuyệt đối của diện tích định hướng của nó.

Bằng chứng. Chúng ta sẽ giới hạn trong trường hợp đa giác $A_1A_2 \ldots A_n$, bên trong có một điểm $O$, từ đó có thể nhìn thấy tất cả các cạnh (hình 11), bao gồm cả đa giác. Chúng ta hãy viết ra định nghĩa của $[A_1A_2 \ldots A_n]$ liên quan đến điểm này. Các đoạn $OA_i$ chia đa giác thành $n$ hình tam giác, do đó diện tích (tổng) của nó $S$ bằng tổng diện tích của chúng. Mặt khác, hai tam giác liền kề bất kỳ $OA_{i-1}A_i$ và $OA_iA_{i+1}$ nằm đối diện nhau của $OA_i$ và do đó có cùng hướng. Do đó, dấu hiệu khu vực định hướng của chúng là như nhau, từ đó
$$\|[A_1A_2 \ldots A_n]\| = \|[OA_1A_2]\| + \ldots + \|[OA_nA_1]\| = S.$$
Chứng minh trong trường hợp tổng quát được thực hiện bằng quy nạp sử dụng định lý nổi tiếng rằng mọi đa giác đều có đường chéo nằm hoàn toàn bên trong nó. Nếu chúng ta viết định nghĩa về diện tích của hai phần mà đa giác được chia cho một đường chéo như vậy, thì chúng ta sẽ nhận được hai tổng diện tích của các hình tam giác và diện tích của tam giác liền kề với đường chéo xuất hiện một lần trong mỗi tổng, nhưng với các dấu khác nhau. Khi các thuật ngữ này được thêm vào, chúng triệt tiêu lẫn nhau và các hình tam giác còn lại tạo thành tổng của đa giác ban đầu. Chúng tôi để lại chi tiết cho độc giả.

Văn học

1. V. Rabinovich. Tính toán khối lượng bằng nguyên lý Cavalieri. – «Kvant», 1972, số 6.
2. D. Tereshin. Kháng cáo từ nguyên tắc Cavalieri. – «Kvant», 1994, số 2.
3. S. Lurie. Tập sách toán học của Cavalieri. – «Kvant», 1994, số 2.
4. K.Kokhas. Dây đàn tranh luận kỳ diệu. – «Kvant», 2024, số 3.
5. A. Lopshin. Các vùng hình định hướng. – «Kvant», 1978, số 3.
6. N. Vazumen. Công thức diện tích. – «Kvant», 1981, số 4.
7. A.Toom. Một đa giác có bao nhiêu diện tích? – «Kvant», 1984, số 12.
