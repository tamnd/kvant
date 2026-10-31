---
id: 1975-2-resheniya-zadach-m268-m272-f278-f284-4df14b70
issue: kvant_1975_2
year: 1975
number: "2"
title: Lời giải bài toán M268—M272; F278—F284
rubric: zadachnik-kvanta
rubric_sub: Задачник «Кванта»
page_first: 30
page_last: 42
page_labels: 28-40
tag: U8NV
lang: vi
source: kvant_digital
extraction: vision
content_sha256: bb118def0b0929d3c0cd2c050f4853fce964fc3aa8984219015b452c202ff18d
prompt_sha256: draft-1
translated_from: content/ru/1975/02/articles/10_resheniya-zadach-m268-m272-f278-f284-4df14b70.md
source_content_sha256: 173c37f53fc9c5b9acce90821eff3299d4047a9f1e0e079cff8aa655f39e34c3
translation_model: draft
translation_run: vi-draft-2026-10-31
translation_quality: draft
---

⟦folio 28⟧

Lời giải bài toán

M268. Ở góc bàn cờ, stosht ftsurra. Con cerok đầu tiên có thể di chuyển nó hai lần liên tiếp như một hiệp sĩ thông thường (hai ô theo một hướng, một ô theo hướng vuông góc) và con thứ hai có thể di chuyển nó một lần với tư cách là một hiệp sĩ với một nước đi kéo dài (ba ô vuông theo một hướng và một ô theo hướng vuông góc). Thế là họ thay phiên nhau. Người đầu tiên cố gắng đặt ftsurra ở góc đối diện, và người thứ hai cố gắng đặt nó vào đó. Cái nào trong số chúng có thể chịu được (kích thước của bảng là $n \times n$, trong đó $n \geq 4$)?

Hãy để hiệp sĩ đầu tiên ở góc dưới bên trái của bàn cờ. Rõ ràng là người chơi đầu tiên, với nước đi đầu tiên của mình, có thể đưa quân mã ra khỏi góc bàn cờ và đặt nó trên đường chéo (xem Hình 1 - dấu thập màu xanh là kết quả nước đi của người chơi đầu tiên). Hãy để chúng tôi chứng minh rằng người chơi đầu tiên có thể tự mình quay trở lại đường chéo và ngày càng cao hơn.

Để người chơi đầu tiên đặt quân mã lên một ô vuông nào đó trên đường chéo của bàn cờ (Hình 2). Các ô mà người chơi thứ hai có thể di chuyển quân mã từ đường chéo vào được đặt trong Hình 2 với các dấu thập màu đen và đỏ. Từ các ô được đánh dấu bằng chữ thập đỏ, người chơi đầu tiên có thể đưa quân mã về đường chéo của bàn cờ, di chuyển nó lên đúng một ô (theo hướng của góc mong muốn). Từ các ô được đặt bằng các chữ thập màu đen, người chơi đầu tiên cũng có thể đưa hiệp sĩ về đường chéo, nhưng không phải về ô tiếp theo mà là sau một ô. Tuy nhiên, rõ ràng là khi kết thúc trò chơi, người chơi thứ hai sẽ không thể đặt hiệp sĩ vào các ô được đặt bằng các chữ thập màu đen: bàn cờ bị giới hạn và khi một hoặc hai ô vuông vẫn còn ở góc trên, các đường viền trên và bên phải của bàn cờ sẽ bị “cắt” khỏi cấu hình kết quả bởi các ô chữ thập màu đen (Hình 3); người chơi thứ hai sẽ buộc phải bắt đầu đặt hiệp sĩ vào các ô vuông có chữ thập đỏ. Rõ ràng là trong trường hợp này người chơi đầu tiên sẽ đạt được mục tiêu.

I. N. Klumova

M269. Chúng ta hãy biểu thị bằng $T_k(n)$ tổng các tích của $k$ các số từ 1 đến $n$. Ví dụ: $T_2(4) = 1.2 + 1.3 + 1.4 + 2.4 + 3.4 = 35$.

a) Tìm công thức tổng quát của $T_2(n)$ và $T_3(n)$.
b) Chứng minh rằng $T_k(n)$ được biểu diễn dưới dạng đa thức theo lũy thừa $n$ của $2k$ (với mọi số tự nhiên $k \geq 2$).
b) Nêu phương pháp tìm đa thức $T_k(n)$ ($k = 2, 3, 4, \dots$) và áp dụng để tìm đa thức $T_4(n)$ và $T_5(n)$.

Ta sẽ chứng minh rằng $T_2(n), T_3(n), T_4(n)$ và $T_5(n)$ lần lượt bằng nhau
$$\frac{(n+1)n(n-1)(3n+2)}{24}, \frac{(n+1)^2n^2(n-1)(n-2)}{48},$$
$$\frac{(n+1)n(n-1)(n-2)(n-3)(15n^3+15n^2-10n-8)}{5760}$$

Và
$$\frac{(n+1)^2n^2(n-1)(n-2)(n-3)(3n^2-n-6)}{11520}$$

(cố gắng chứng minh trực tiếp rằng những số này là số nguyên với mọi số nguyên $n$), và với mọi $k$, các số $T_k(n)$ là giá trị của đa thức $T_k$ bậc $2k$ (với hệ số dẫn đầu $\frac{1\cdot 3\cdot 5\cdots(2k-1)}{1\cdot 2\cdot 3\cdot 4\cdots(2k)}$), trong đó các số - 1, 0, 1, ..., $(k-1)$ đều có nghiệm.

Nhân tiện xin lưu ý rằng $T_1(n)$ — tổng tích của các số từ 1 đến $n$ “từng số một” — bằng
$$\sum i = 1 + 2 + \ldots + n = \frac{n(n+1)}{2}.$$

⟦folio 29⟧

Cách đầu tiên. Bạn có thể tìm công thức cho $T_k(n)$ bằng cách sử dụng các công thức phổ biến về tổng lũy ​​thừa của các số tự nhiên:

$$\Sigma i^2 = 1^2 = 2^2 + \dots + n^2 = \frac{n(n+1)(2n+1)}{6},$$

$$\Sigma i^3 = 1^3 + 2^3 + \dots + n^3 = \frac{n^2(n+1)^2}{4} \text{ и т. д.}$$

(ví dụ, xem các bài viết của V. S. Abramovich trong «Kvant» Số 5 năm 1973 và Số 6 năm 1974). Ví dụ, từ đẳng thức

$$(\Sigma i)^2 = \Sigma i^2 + 2 \sum ij$$

theo đó $T_2(n)$ bằng

$$\sum_{i<j} ij = \frac{n(n+1)}{2} \left( \frac{n^2+n}{4} - \frac{2n+1}{6} \right) =$$

$$= \frac{n(n+1)(n-1)(3n+2)}{24}$$

(kiểm tra xem $T_2(2) = 2$, $T_2(3) = 11$, $T_2(4) = 35$, $T_2(5) = 85$).

Từ sự bình đẳng

$$(\Sigma i)^3 = \Sigma i^3 + 3 \sum ij^2 + 6 \sum ijk,$$

$$i \neq j \quad i < j < k$$

$$(\Sigma i)(\Sigma j^2) = \Sigma i^3 + \sum ij^2$$

theo sau $T_3(n) = \sum ijk = i < j < k$

$$= \frac{1}{6} \left( (\Sigma i)^3 - 3(\Sigma i)(\Sigma j^2) + 2\Sigma i^3 \right) = \frac{n^2(n+1)^2}{6} \times$$

$$\times \left( \frac{n(n+1)}{8} - \frac{2n+1}{4} + \frac{1}{2} \right) = \frac{n^2(n+1)^2(n-1)(n-2)}{48}.$$

Dưới đây chúng tôi sẽ chỉ ra cách người ta có thể tìm $T_k(n)$ mà không cần lấy công thức tính tổng lũy ​​thừa.

Công thức tái diễn. Nếu tất cả các số hạng của tổng $T_k(n)$ được chia thành hai nhóm: một nhóm bao gồm các tích bao gồm $n$, nhóm kia bao gồm các phần còn lại, thì sẽ thu được công thức cơ bản sau:

$$T_k(n) - T_k(n-1) = nT_{k-1}(n-1)$$

(1)

Cô cùng với một người bình đẳng khác

$$T_k(k) = 1 \cdot 2 \cdot \dots \cdot k = k!$$

cho phép bạn xác định một cách nhất quán tất cả các số $T_k(n)$ cho $n \geq k$, nếu $T_{k-1}(n)$ đã biết. (Lưu ý rằng nếu $T_k$ và $T_{k-1}$ là đa thức thì công thức (1) phải được thỏa mãn cho tất cả $n$, chứ không chỉ cho số nguyên $n$ lớn hơn $k$; có được điều này, dễ dàng xác minh rằng $T_k(n)$ phải bằng 0 đối với số nguyên $n$ từ $(-1)$ đến $(k-1)$ và tìm các giá trị của $T_k(n)$ cho số nguyên $n$, được chỉ ra trong Bảng 1.) Từ công thức (1) người ta có thể suy ra rằng $T_k(n)$ là đa thức bậc $2k$, nếu bên phải là đa thức $nT_{k-1}(n-1)$ bậc $2k-1$ từ $n$ (xem các bài của V. S. Abramovich, đã đề cập ở trên, hoặc bài của V. N. Vaguten trong «Kvant» Số 2, 1972); tuy nhiên, chúng tôi sẽ không chứng minh điều này một cách riêng biệt mà sẽ ngay lập tức thu được công thức cho đa thức $T_k(n)$.

⟦folio 30⟧

Bảng này hiển thị các số $T_k(n)$ (các số $T_k(k)=k$ được bao trong khung màu đỏ!

Cách thứ hai. Hãy đặt

$$C_x^m = \frac{x(x-1)\ldots(x-m+1)}{1\cdot 2\cdot 3\cdot \ldots m}$$

(3a)

Chúng ta sẽ coi $C_x^m$ là đa thức bậc $m$ trong $x$. Thật dễ dàng để kiểm tra điều đó cho tất cả $x$

$$C_{x+1}^m = C_x^m + C_x^{-1}, (x-m)C_x^m = (m+1)C_x^{m+1}$$

(36)

Lưu ý rằng

$$T_1(n) = \frac{(n+1)n}{2} = C_{n+1}^2$$

(4a)

Giả sử điều đó đối với một số $b_0^{k-1}, b_1^{k-1}$

$$T_{k-1}(n) = \Sigma b_m^{k-1} C_{n+1}^m$$

(46)

và chọn $b_m^k$ sao cho đa thức (46) và

$$T_k(n) = \Sigma b_m^k C_{n+1}^m$$

(5)

đẳng thức (1) được thỏa mãn; vì, theo (36),

$$T_k(n) - T_k(n-1) = \Sigma b_m^k (C_{n+1}^m - C_n^m) =$$

$$= \Sigma b_m^k C_{n+1}^m - \Sigma b_m^{k+1} C_n^m, nT_{k-1}(n-1) = n\Sigma b_m^{k-1} C_n^m =$$

$$= \Sigma b_m^{k-1}(n-m)C_n^m + \Sigma b_m^{k-1}mC_n^m =$$

$$= \Sigma b_m^{k-1}(m+1)C_{n+1}^{m+1} + \Sigma b_m^{k-1}mC_{n+1}^{m}$$

(6)

Hơn nữa, theo (4a)

$$b_2^1 = 1; b_1^m = 0, m \neq 2.$$

(7)

Lập bảng số $b_m^k$ và chứng minh rằng

$$b_m^k = 0, m \leq k \text{ и } m \geq 2k+1; b_2^k = 1\cdot 3\cdot 5\ldots (2k-1);$$

$$b_{k+1}^k = k!.$$

Đẳng thức Posny (2) cho đa thức (5) cũng được thỏa mãn. Theo đó, $T_k(n)$ thực được tính theo công thức (5), trong đó các hệ số $b_m^k$ được tìm thấy từ các đẳng thức (6), (7).

Theo cách tương tự, người ta có thể bị thuyết phục rằng

$$T_k(n) = \Sigma d_m^n C_{n+m-k}^m$$

(9)

trong đó các hệ số $d_m^k$ được xác định bởi các điều kiện

$$d_2^1 = 1; d_1^m = 0, m \neq 2;$$

$$d_{k+1}^k = -(m-k+1)d_{k+1}^{k-1} + md_{k+1}^{k-1}.$$

(10)

⟦folio 31⟧

Mặc dù công thức (10) cho các hệ số $d_m^k$ kém thuận tiện hơn (6) cho $b_m^k$, nhưng bản thân các số này nhỏ hơn một chút, do đó từ công thức (9) sẽ thuận tiện hơn khi thu được $T_4(n)$ và $T_5(n)$ ở dạng chúng được biểu thị ở đầu lời giải. Ví dụ: tìm số $d$ và sử dụng sự tương ứng (3), ta có

$$T_4(n) = \left( \left( \frac{105}{8} - 105 \right) \frac{n+3}{7} + 25 \right) \frac{n+2}{6} - 1 C_{n+1}^5 = C_{n+1}^5 (15n^3 + 15n^2 - 10n - 8)/48.$$

Công thức của $T_5(n)$ được biến đổi theo cách hoàn toàn tương tự.

Các số $T_k(n)$ khá phổ biến trong các bài toán tổ hợp và đại số khác nhau; biến mất hoàn toàn khỏi chúng với dấu của số $(-1)^{n+k-1} T_k(n)$ và có một cái tên đặc biệt: Số Stirling.

Ví dụ, ứng dụng của những con số này và sự đồng nhất kết nối chúng được mô tả trong cuốn sách “Giới thiệu về phân tích tổ hợp” của J. Riordan (M., IL, 1963).

◆

Trước hết, cần làm rõ các điều kiện: các hợp âm $AB$ và $CD$ phải không đều (trong trường hợp này, vị trí của các điểm $K$ và $H$ được xác định duy nhất), và các đường $AD$ và $BC$ cũng không đều (chúng ta biểu thị điểm giao nhau của chúng là $E$).

Đầu tiên chúng ta chứng minh rằng đường thẳng $KH$ đi qua tâm đường tròn. Để điểm $M$ di chuyển đều dọc theo đường thẳng $KH$; Chúng ta hãy biểu thị bằng $M(t)$ vị trí của nó tại thời điểm $t$ đến $M'(t)$ và $M''(t)$—các hình chiếu của điểm $M(t)$ lần lượt lên các đường $AB$ và $CD$. Ta chọn gốc và đơn vị thời gian sao cho $M(0) = K$, $M(1) = H$; sau đó $M'(0) = A$, $M'(1) = B$, $M''(0) = C$, $M''(1) = D$. Rõ ràng là mỗi điểm $M'(t)$ và $M''(t)$ được số hóa thống nhất dọc theo đường thẳng của chính nó.

Tại $t = \frac{1}{2}$, điểm $M'(t)$ và $M''(t)$ rơi vào trung điểm của các đoạn $AB$ và $CD$, do đó, điểm $M\left(\frac{1}{2}\right)$ rơi vào tâm đường tròn - giao điểm của các đường vuông góc với dây $AB$ và $CD$, được phục hồi tại trung điểm của chúng.

Bây giờ chúng ta chứng minh rằng đường thẳng $KH$ đi qua điểm $E$. Đối với bất kỳ vị trí nào của các điểm $A$, $B$, $C$ và $D$ trên đường tròn, các tam giác $AEB$ và $CED$ đều giống nhau (ở hai góc) và đỉnh $A$ tương ứng với đỉnh $C$, đỉnh $B$ tương ứng với đỉnh $D$. Rõ ràng là dưới phép biến đổi tương tự lấy $\Delta AEB$ đến $\Delta CED$, mỗi điểm $M'(t)\in(AB)$ chiếu tới điểm $M''(t)\in(CD)$ (có cùng giá trị $t$). Nhưng đáy $E'$ của chiều cao $EE'$ của tam giác $AEB$ trong trường hợp này đi vào đáy của chiều cao $EE''$ của tam giác $CED$, nghĩa là, đối với một số $t=t_0$ đồng thời $M'(t_0)=E'$ và $M''(t_0)=E''$, do đó, $M(t)=E$.

N. B. Vasiliev

◆

Hãy chứng minh rằng sự sắp xếp cần thiết là có thể thực hiện được.

Nếu số nguyên $b$ bằng các số nguyên $a$ và $c$ thì $a+c$ là số chẵn, do đó các số $a$ và $c$ có cùng tính chẵn lẻ, tức là chúng chẵn hoặc lẻ. Do đó, nếu sắp xếp các số 1, 2, ..., $n$ sao cho tất cả các số chẵn đứng trước, sau đó đến tất cả các số lẻ thì số $b$ có thể bằng ta được ta đứng ở vị trí khác nhau

⟦folio 32⟧

các cạnh của các số $a$ và $c$ chỉ khi cả ba số này có cùng tính chẵn lẻ. Như vậy, vẫn còn phải chứng minh rằng cả các số chẵn từ 1 đến $n$ và các số lẻ đều có thể được sắp xếp theo cách yêu cầu.

Nhưng dễ hiểu là các số 2, 4, 6 đều có vị trí. . ., $2k$ hoặc các số 1, 3, 5, . . ., $2k-1$ có thể theo thứ tự như các số 1, 2, . . ., $k$. Thật vậy, nếu $2b = \frac{2a+2c}{2}$ hoặc $2b-1 = \frac{(2a-1)+(2c-1)}{2}$ thì $b = \frac{a+c}{2}$.

Như vậy, bài toán được rút gọn thành thứ tự các số 1, 2, . . ., $k$ ($k = \frac{n}{2}$ nếu $n$ là số chẵn và $k = \frac{n+1}{2}$ nếu $n$ là số lẻ). Vì mệnh đề đang được chứng minh là đúng với $n = 1$ nên nó đúng với mọi $n$ tự nhiên và tuân theo nguyên lý quy nạp toán học.

Lý luận trên đưa ra một cách cụ thể để xây dựng cách sắp xếp cần thiết của các số 1, 2,... . ., $n$. Ví dụ: chúng tôi sẽ thực hiện việc xây dựng như vậy cho $n=16$.

1
2 1
4 2 3 1
8 4 6 2 7 3 5 1
16 8 12 4 14 6 10 2 15 7 11 3 13 5 9 1

**M272. Cho hai đường tròn bán kính $R$ và $r$, tiếp tuyến ngoài. Xây dựng các ranh giới ABCD khác nhau sao cho mỗi vòng tròn tiếp xúc với các cạnh bên chung và cùng một vùng tính từ đáy của các ranh giới. Tìm độ dài cạnh AB ngắn nhất có thể.**

Hình 4.

Không mất tính tổng quát, chúng ta có thể giả sử rằng $R>r$ (nếu $R=r$ thì hình thang ABCD trở thành hình chữ nhật có cạnh AB bằng $2(R+r)=4r$). Tâm của hình tròn có bán kính $R$ được ký hiệu là $O_1$ và tâm của hình tròn có bán kính $r$ được ký hiệu là $O_2$. Ngoài ra, chúng ta giả sử đường tròn $O_1$ tiếp xúc với đáy AD và đường tròn $O_2$ tiếp xúc với đáy BC. Đặt $PQ$ là tiếp tuyến chung ngoài của các đường tròn này (điểm $P$ nằm trên đường tròn $O_1$ và điểm $Q$ nằm trên đường tròn $O_2$, xem Hình 1). Dễ dàng tính được độ dài của đoạn $PQ$ bằng $2\sqrt{Rr}$.

Chúng ta hãy vẽ các đoạn $PA$ và $QB$ trên đường thẳng $PQ$ bên ngoài đoạn $PQ$ và tìm xem sự tương ứng giữa độ dài của các đoạn này là tiếp tuyến $AA'$ với đường tròn $O_1$ (khác với $AP$) song song với tiếp tuyến $BB'$ với đường tròn $O_2$ (khác với $BQ$).

Các tiếp tuyến này song song với điều kiện tổng các góc $BAA'$ và $ABB'$ bằng $180^\circ$, tức là $O_2BQ$ và $Q_1AP$ bù nhau thành một góc vuông. Điều kiện cuối cùng có nghĩa là sự bằng nhau của các góc $BO_2Q$ và $O_1AP$ và do đó, tỷ lệ

$$\frac{|BQ|}{|O_2Q|} = \frac{|O_1P|}{|AP|}.$$

Bằng cách đặt $x=[BQ]$, $x'=[AP]$, điều kiện để các tiếp tuyến song song $AA'$ và $BB'$ có thể được viết như sau: $x \cdot x' = R \cdot r$. Độ dài của đoạn $AB$ trong trường hợp này bằng $x + \frac{Rr}{x} + 2\sqrt{Rr}$.

Nếu thỏa mãn điều kiện song song thì ký hiệu $D$ và $C$ là giao điểm của tiếp tuyến ngoài thứ hai $O_1$ và $O_2$ với các đường thẳng song song $AA'$ và $BB'$, ta thu được hình thang ABCD thỏa mãn

⟦folio 33⟧

Thỏa mãn điều kiện bài toán. Tuy nhiên, tuyên bố này có vẻ khó hiểu khi nhìn vào Hình 4, cần phải được làm rõ. Nhìn vào Hình 5. Nếu số $x$ quá lớn, bạn sẽ không thể có được hình thang. Rõ ràng số $x$ phải nhỏ hơn độ dài của đoạn $QB$ trong Hình 6. Chứng minh rằng $|QB| = \frac{2r}{R-r} \sqrt{Rr}$.

Vì vậy, vẫn còn phải giải quyết bài toán sau: tìm giá trị nhỏ nhất của hàm $f(x) = x + \frac{Rr}{x} + 2\sqrt{Rr}$ trên khoảng $0 < x < \frac{2r}{R-r} \sqrt{Rr}$. Thay vì hàm này, chúng ta có thể lấy hàm $g(x) = x + \frac{Rr}{x}$, đồ thị của hàm này (tại $x > 0$) được hiển thị trong Hình 7. Nó tiêu diệt ở $0 < x \leq \sqrt{Rr}$ và trả về ở $x \geq \sqrt{Rr}$ (chứng minh điều này). Do đó, nếu $\frac{2r}{R-r} \cdot \sqrt{Rr} > \sqrt{Rr}$ thì giá trị nhỏ nhất của độ dài cạnh $AB$ là $f(\sqrt{Rr}) = 4\sqrt{Rr}$. Nếu $\frac{2r}{R-r} \cdot \sqrt{Rr} \leq \sqrt{Rr}$ thì hàm $f$ không có giá trị nhỏ nhất trên khoảng $]0, \frac{2r}{R-r} \sqrt{Rr}$.

Bất đẳng thức $\frac{2r}{R-r} \sqrt{Rr} \leq \sqrt{Rr}$ tương đương với việc dịch $R \geq 3r$. Do đó, nếu $r < R < 3r$, mức tối thiểu loại trừ là $4\sqrt{Rr}$, nhưng nếu $R \geq 3r$, giá trị tối thiểu $|AB|$ không tồn tại: độ dài của cạnh $|AB|$ có thể nhận bất kỳ giá trị nào lớn hơn $f\left(\frac{2r}{R-r} \times \sqrt{Rr}\right) = \frac{(R+r)^2}{2r(R-r)} \sqrt{Rr}$, nhưng bản thân giá trị này không đạt tới.

Yu. I. Ionin.

Để đơn giản, chúng ta sẽ giả sử rằng tốc độ của vệ tinh thay đổi trong một khoảng thời gian rất ngắn (nhỏ so với chu kỳ quay của vệ tinh trên quỹ đạo tròn). Khoảng cách tối thiểu từ bề mặt Trái đất đến quỹ đạo hình elip bằng bán kính quỹ đạo tròn ban đầu, tức là cả hai quỹ đạo vệ tinh đều có một điểm chung (điểm $I$ trong Hình 8), tại đó tốc độ của vệ tinh thay đổi. Chúng ta hãy tìm tốc độ $v_0$ và $v_1$ của vệ tinh tại thời điểm này theo quỹ đạo hình tròn và hình elip, sau đó là sự thay đổi tốc độ $\Delta v = v_1 - v_0$.

Đầu tiên, chúng ta xác định tốc độ $v_0$ của vệ tinh khi chuyển động theo quỹ đạo tròn. Vì gia tốc hướng tâm $a = \frac{v_0^2}{R+h}$ ($R$ là bán kính Trái đất) được truyền tới vệ tinh bởi lực hấp dẫn $F_T = \gamma \frac{mM}{(R+h)^2}(M$ là khối lượng của Trái đất, $m$ là khối lượng của vệ tinh), nên theo định luật II của Newton, $\frac{mv_0^2}{R+h} = \gamma \frac{mM}{(R+h)^2}$. Từ đẳng thức này chúng ta có thể trực tiếp tìm thấy,

⟦folio 34⟧

$$v_0 = \sqrt{\gamma \frac{M}{R+h}}.$$

Để xác định tốc độ $v_1$ của vệ tinh khi nó chuyển động theo quỹ đạo elip ở độ cao $h$ so với Trái Đất, chúng ta sử dụng định luật bảo toàn năng lượng và định luật Kepler III*). Từ sự tương tự giữa trường hấp dẫn và trường tĩnh điện, chúng ta có thể kết luận rằng tại thời điểm vệ tinh ở khoảng cách $h$ so với Trái đất, nó có thế năng là $\Pi_1 = -\gamma \frac{mM}{R+h}$. Ngoài ra, vệ tinh có động năng $K_1 = \frac{mv_1^2}{2}$. Ở độ cao $H$ tính từ Trái đất, vệ tinh có thế năng $\Pi_2 = -\gamma \frac{mM}{R+H}$ và động năng $K_2 = \frac{mv_2^2}{2}$, trong đó $v_2$ là tốc độ của vệ tinh ở độ cao $H$. Theo định luật bảo toàn năng lượng,

$$\frac{mv_1^2}{2} - \gamma \frac{mM}{R+h} = \frac{mv_2^2}{2} - \gamma \frac{mM}{R+H}.$$

Theo định luật thứ hai của Kepler, diện tích được quét bởi vectơ bán kính của vệ tinh trong những khoảng thời gian bằng nhau là bằng nhau. Trong Hình 8 đây là diện tích của các hình được tô bóng. Nếu khoảng thời gian $\Delta t$ nhỏ thì tốc độ của vệ tinh lớn hơn điểm 1 và 2 có thể được coi là không đổi. Sau đó, thay vì xem xét các cung, chúng ta có thể xem xét các tam giác đều tương ứng. Chúng ta hãy viết ra sự bằng nhau về diện tích của chúng:

$$\frac{1}{2} v_1 \Delta t (R+h) = \frac{1}{2} v_2 \Delta t (R+H).$$

Từ hai đẳng thức cuối cùng ta tìm được

$$v_1 = \sqrt{\frac{2\gamma M}{2R+H+h} \frac{R+H}{R+h}}.$$

Sau đó, sự thay đổi tốc độ vệ tinh

$$\Delta v = v_1 - v_0 = \sqrt{\frac{\gamma M}{R+h}} \left( \sqrt{\frac{2(R+H)}{2R+H+h}} - 1 \right) \approx \frac{2\kappa M}{c}.$$

Bây giờ chúng ta hãy xác định chu kỳ $T$ của vòng quay của vệ tinh theo quỹ đạo hình elip. Theo định luật Kepler III, tỉ số bình phương chu kỳ quỹ đạo của vệ tinh bằng tỉ số lập phương của bán trục lớn các quỹ đạo của nó. Đó là lý do tại sao

$$\frac{T^2}{T_0^2} = \frac{(2R+h+H)^3}{8(R+h)^3},$$

trong đó $T_0 = \frac{2\pi (R+h)}{v_0}$ là chu kỳ quay của vệ tinh theo quỹ đạo tròn có bán kính $R+h$. Kể từ đây,

$$T = \pi (2R+H+h) \sqrt{\frac{2R+H+h}{2\gamma M}} \approx 12\mu.$$

*) Ví dụ, xem bài viết của E. P. Kuznetsov “Không gian bài toán trong kỳ thi tuyển sinh”, «Kvant», 1974, số 11.

⟦folio 35⟧

F279. Hình trụ làm bằng vật liệu không nóng chảy dẫn điện được chia bằng vách ngăn không nóng chảy thành hai phần, thể tích là $V_1$ và $V_2$. Phần thứ nhất chứa khí ở nhiệt độ $T_1$ dưới áp suất $p_1$. Phần thứ hai chứa cùng một loại khí, nhưng ở nhiệt độ $T_2$ và dưới áp suất $p_2$. Nhiệt độ khí sẽ được thiết lập trong xi lanh nếu vách ngăn được loại bỏ?

Vì thành của hình trụ được làm bằng vật liệu không rắn dẫn điện nên bất kể quá trình nào xảy ra với chất khí trong hình trụ khi nó chuyển động, nó đều tuân theo định luật bảo toàn năng lượng.

$$cm_1(T - T_1) = cm_2(T_2 - T).$$

Ở đây $c$ là nhiệt dung riêng của khí, $m_1$ và $m_2$ là khối lượng của khí tương ứng ở phần thứ nhất và thứ hai của hình trụ, và $T$ là nhiệt độ được thiết lập trong hình trụ sau khi xảy ra trạng thái cân bằng. Từ công thức này (phương trình cân bằng nhiệt), sau khi biến đổi đơn giản, ta thu được

$$T = \frac{(m_1/m_2)T_1 + T_2}{1 + \frac{m_1}{m_2}}.$$

Tỷ lệ $\frac{m_1}{m_2}$ không khó tìm được bằng cách hoàn thành phương trình trạng thái khí. Đối với phần khí ở phần hình trụ trước khi tháo vách ngăn ra, ta có thể viết

$$p_1V_1 = \frac{m_1}{\mu}RT_1 \quad p_2V_2 = \frac{m_2}{\mu}RT_2.$$

Chia đẳng thức thứ nhất cho đẳng thức thứ hai, ta được

$$\frac{m_1}{m_2} = \frac{p_1V_1T_2}{p_2V_2T_1}.$$

Rồi cuối cùng

$$T = \frac{T_1T_2(p_1V_1 + p_2V_2)}{p_1V_1T_2 + p_2V_2T_1}.$$

F280. Nguồn sáng cách vật một khoảng 3a có tiêu cự $a$. Độ sáng trung bình của một điểm trên màn, nằm cách vạch 1,5 a, thay đổi bao nhiêu lần nếu đặt một tấm kính phẳng 0,5 a giữa vạch và nguồn? Chiết suất của thủy tinh là $n$.

⟦folio 36⟧

Chúng ta hãy tìm riêng độ chiếu sáng trong trường hợp thứ nhất và thứ hai, sau đó là tỷ lệ của chúng.

Trong trường hợp đầu tiên, nguồn nằm ở khoảng cách $d_1 = 3a$ so với đường dây. Từ công thức thấu kính $\frac{1}{d} + \frac{1}{f} = \frac{1}{F}$, chúng ta thấy rằng ảnh nguồn nằm cách đường thẳng một khoảng $f_1 = \frac{Fd_1}{d_1 - F} = \frac{3}{2}a$, tức là nằm chính xác trên màn hình.

Giả sử diện tích nguồn nhỏ và bằng $\Delta S$ (kích thước thực tế của nguồn phải nhỏ so với khoảng cách từ nó đến đường thẳng, vì sử dụng công thức thấu kính, chúng ta chỉ xét các tia gần trục quang chính). Sau đó, chúng ta có thể giả sử rằng quang thông, được biểu thị bằng đơn vị diện tích nguồn theo một góc khối đơn vị - hãy ký hiệu nó là $I$ - là một giá trị không đổi. Do đó, quang thông $\Phi_1 = I\Delta S\Omega_1$ rơi trên đường thẳng tính từ nguồn, trong đó $\Omega_1$ là góc đặc mà tại đó nhìn thấy được đường của các điểm nguồn. Góc $\Omega_1$ được đo bằng tỷ lệ $\frac{S}{d_1^2}$ ($S$ là diện tích của đường thẳng, $d_1$ là khoảng cách từ đường thẳng đến nguồn). Dòng ánh sáng này sau khi thấu kính chạm vào màn hình. Vùng hình ảnh $\Delta S_1$ trên màn hình có liên quan đến vùng nguồn là $\frac{f_1^2}{d_1^2}$, tức là

$$\frac{\Delta s_1}{\Delta S} = \frac{f_1^2}{d_1^2} = \frac{1}{4}.$$

Khi đó độ sáng màn hình trong trường hợp đầu tiên bằng

$$E_1 = \frac{\Phi_1}{\Delta S_1} = I \frac{S}{d_1^2} \frac{\Delta S}{\Delta S_1} = \frac{4}{9} \frac{IS}{a^2}.$$

Sau khi một tấm phẳng ngang được đặt giữa nguồn và thấu kính, ảnh của nguồn do tấm đó mang lại sẽ trở thành nguồn cho thấu kính. Hãy tìm vị trí của hình ảnh này (khoảng cách $x$ trong Hình 9).

Ví dụ, để làm điều này, chúng ta sẽ xây dựng đường đi của hai tia xuất phát từ điểm $A$ của nguồn. Để một tia vuông góc với tấm và tia thứ hai tạo thành một góc nhỏ $\alpha$ với tia thứ nhất. Từ tam giác $A'CK$ đoạn $CK$ bằng

$$CK = A'K \mathrm{tg} \alpha = \left(l - x + \frac{a}{2}\right) \mathrm{tg} \alpha.$$

Ở phía bên kia,

$$CK = CD + KD = \frac{a}{2} \mathrm{tg} \beta + l \mathrm{tg} \alpha.$$

Kể từ đây,

$$\left(l - x + \frac{a}{2}\right) \mathrm{tg} \alpha = \frac{a}{2} \mathrm{tg} \beta + l \mathrm{tg} \alpha.$$

Do đó $x = \frac{a}{2} \left(1 - \frac{\mathrm{tg} \beta}{\mathrm{tg} \alpha}\right)$. Vì các góc $\alpha$ và $\beta$ nhỏ nên $\frac{\mathrm{tg} \beta}{\mathrm{tg} \alpha} = \frac{\sin \beta}{\sin \alpha} = \frac{1}{n}$ và $x = \frac{a}{2} \left(1 - \frac{1}{n}\right)$. Do đó, ảnh của nguồn do tấm cho trước có khoảng cách $d_2 = 3a - x = \frac{a}{2} \left(5 + \frac{1}{n}\right)$.

⟦folio 37⟧

Trong trường hợp này, kích thước của hình ảnh giống với kích thước của nguồn (xem Hình 9). Quang thông $\Phi_2$ tới thấu kính từ nguồn mới này là $\Phi_2 = I \Delta S \Omega_2 = I \Delta S \frac{S}{d_2^2}$.

Bây giờ, từ công thức thấu kính, hãy tìm vị trí ảnh của nguồn này:

$$f_2 = \frac{Fd_2}{d_2 - F} = a \frac{5n + 1}{3n + 1}.$$

Rõ ràng là trên màn hình không có hình ảnh rõ ràng mà trên màn hình có một điểm mờ. Tuy nhiên, vì đối với kính $n$ nằm trong khoảng từ 1,5 đến 2 nên $f_2$ nhận các giá trị từ 1,54 a đến 1,57 a. Đây là ảnh nằm cách màn một khoảng 0,05 a. Khoảng cách này nhỏ so với khoảng cách 1,5 a từ màn đến thấu kính. Ngoài ra, kích thước của vật và đường kính của thấu kính cũng nhỏ (lưu ý một lần nữa rằng chúng ta chỉ đang xem xét các chùm tia đồng trục hẹp). Do đó, chúng ta có thể giả định rằng kích thước của một hình ảnh rõ ràng không khác với kích thước của điểm trên màn hình (Hình 10) và $\frac{\Delta s_2}{\Delta S} = \frac{f_2^2}{d_2^2} = \frac{4n^2}{(3n + 1)^2}$.

Khi đó màn hình chiếu sáng $E_2$ trong trường hợp này bằng

$$E_2 = \frac{\Phi_2}{\Delta s_2} = \frac{I S \Delta S}{d_2^2 \Delta s_2} = \left( \frac{3n + 1}{5n + 1} \right)^2 \frac{I S}{a^2},$$

và tỷ lệ chiếu sáng

$$\frac{E_2}{E_1} = \frac{9}{4} \left( \frac{3n + 1}{5n + 1} \right)^2.$$

Ban đầu, hiệu điện thế giữa các bản của tụ điện là $E_2$, và điện tích của tụ điện là $q_1 = CE_2$. Sau khi đóng chìa khóa, dòng điện sẽ chạy qua mạch và hiệu điện thế giữa các bản tụ (hiệu điện thế giữa các điểm $B$ và $A$) sẽ bằng $U_2 = E_2 - Ir_2$, trong đó $I$ là dòng điện chạy qua mạch. Hãy tìm dòng điện này.

Từ đặc tính dòng điện của diode, suy ra rằng khi dòng điện chạy qua diode thì điện áp chạy qua nó luôn bằng $U_2 = 1\epsilon$. Hãy viết định luật Ohm cho mạch hoàn chỉnh:

$$E_2 - E_1 = U_{\pi} + Ir_1 + Ir_2.$$

Từ đây

$$I = \frac{E_2 - E_1 - U_{\pi}}{r_1 + r_2}.$$

Khi đó, sau khi đóng chìa khóa, hiệu điện thế giữa các bản tụ sẽ bằng

$$U_2 = E_2 - \frac{E_2 - E_1 - U_{\pi}}{r_1 + r_2} r_2,$$

*) Trong «Kvant» số 6 năm 1974, trong điều kiện bài toán F281 có một lỗi đánh máy.

⟦folio 38⟧

và phí của nó

$$q_2 = CU_2 = CE_2 - Cr_2 \frac{E_2 - E_1 - U_\pi}{r_1 + r_2}.$$

Do đó, điện tích của tụ điện sẽ thay đổi một lượng

$$\Delta q = q_2 - q_1 = -Cr_2 \frac{E_2 - E_1 - U_\pi}{r_1 + r_2} = -\frac{2}{3} \cdot 10^{-6} \text{ мкф.}$$

F282. Tên là tần số dao động “đối xứng” của hệ như trên Hình 12, a. Khối lượng của các quả cầu là m, hệ số đàn hồi của lò xo là k.

Trước hết, hãy tìm lực tác dụng lên mỗi quả bóng khi nó được trộn từ vị trí cân bằng (Hình 12, 6). Chúng ta hãy biểu thị khoảng cách ban đầu của quả bóng đến tâm của hệ (điểm O) là $x_0$, khoảng cách mới là $x$, độ dịch chuyển của quả bóng so với vị trí cân bằng là $\Delta x$, chiều dài ban đầu của lò xo là $l_0$, chiều dài của nó ở trạng thái giãn là $l$ và sự thay đổi độ dài của lò xo là $\Delta l$.

Hình 12.

Như có thể thấy trong Hình 12, 6,
$$l_0 = 2x_0 \cos 30^\circ \text{ и } l = 2x \cos 30^\circ.$$
Khi đó mỗi lò xo khi trộn các viên bi sẽ bị giãn ra một lượng

$$\Delta l = l - l_0 = 2(x - x_0) \cos 30^\circ = \sqrt{3} \Delta x.$$

Do đó, mỗi quả bóng sẽ chịu tác dụng của hai lực có độ lớn tuyệt đối từ phía lò xo: ​​$F = k\Delta l = \sqrt{3}k\Delta x$.

Lực bằng nhau của các lực này hướng về vị trí cân bằng của quả bóng và bằng giá trị tuyệt đối (Hình 12, 6) $F' = 2F \cos 30^\circ = 3k\Delta x$, tức là tỷ lệ thuận với độ dịch chuyển của quả bóng khỏi vị trí cân bằng. Điều này có nghĩa là hệ tương đương với một hệ gồm ba nam châm lò xo thông thường được nối tại điểm O và mỗi nam châm có độ cứng $k' = 3k$. Do đó, tần số dao động của hệ sẽ bằng

$$\omega = \sqrt{\frac{k'}{m}} = \sqrt{\frac{3k}{m}}.$$

F283. Các quả cầu tích điện có cùng khối lượng, đặt cách nhau một khoảng l, âm

Các quả bóng di chuyển ra xa nhau dưới tác dụng của lực đẩy điện F, bằng (trong hệ đơn vị SGSE)

$$F = \frac{q^2}{r^2},$$ trong đó $q$ là điện tích của mỗi quả bóng, $r$ là khoảng cách

⟦folio 39⟧

(không có tốc độ ban đầu). Sau t giây, khoảng cách giữa chúng được thông báo. Sau bao lâu sẽ biết được khoảng cách giữa các quả bóng nếu chúng được thả từ khoảng cách 3l?

$$\frac{\Delta x_2}{\Delta x_1} = 3$$

Để $k$ thay đổi theo giá trị $\Delta k = \frac{\Delta x}{x_0}$. thì độ dịch chuyển của mỗi quả bóng trong trường hợp đầu tiên ($\text{когда } 2x_0 = l$) là $\Delta x_1 = \Delta k \frac{l}{2}$, và trong trường hợp thứ hai ($\text{когда } 2x_0 = 3l$) là $\Delta x_2 = \Delta k \frac{3}{2} l$. Tỉ số chuyển động của quả bóng bằng

$$\frac{\Delta x_2}{\Delta x_1} = 3.$$

Bây giờ hãy so sánh tốc độ trung bình của các quả bóng. Để làm điều này, chúng ta sẽ sử dụng định luật bảo toàn năng lượng. Tại thời điểm ban đầu, các quả bóng chỉ có thế năng tương tác điện $\Pi_0 = \frac{q^2}{2x_0}$ (trong hệ thống SGSE). Tại thời điểm khoảng cách giữa các quả bóng là $2x$ thì chúng có thế năng $\Pi = \frac{q^2}{2x}$ và động năng $K = 2 \frac{mv^2}{2}$ (m là khối lượng của quả bóng). Theo định luật bảo toàn năng lượng $\frac{q^2}{2x_0} = \frac{q^2}{2x} + mv^2$. Từ đây

$$v = \sqrt{\frac{q^2}{2m} \frac{x-x_0}{xx_0}} = \sqrt{\frac{q^2}{2x_0 m} \frac{k-1}{k}}.$$

Chúng ta thấy rằng với cùng một độ dịch chuyển tương đối $k$ thì tốc độ của quả bóng trong trường hợp đầu tiên lớn hơn $\frac{\sqrt{q^2/ml}}{\sqrt{q^2/3ml}} = \sqrt{3}$ lần tốc độ của quả bóng trong trường hợp thứ hai.

Rõ ràng là khi $k$ thay đổi theo giá trị $\Delta k$ thì tốc độ trung bình của các quả bóng sẽ chênh lệch $\sqrt{3}$ lần: $\frac{v_{\text{cp.1}}}{v_{\text{cp.2}}} = \sqrt{3}$.

Thời gian cần thiết để di chuyển đến $\Delta x_1$ trong trường hợp đầu tiên và đến $\Delta x_2$ trong trường hợp thứ hai lần lượt bằng nhau

$$\Delta t_1 = \frac{\Delta x_1}{v_{\text{cp.1}}} \text{ и } \Delta t_2 = \frac{\Delta x_2}{v_{\text{cp.2}}}.$$

Từ đây

$$\frac{\Delta t_2}{\Delta t_1} = \frac{\Delta x_2}{\Delta x_1} \frac{v_{\text{cp.1}}}{v_{\text{cp.2}}} = 3 \sqrt{3},$$

nghĩa là, đối với bất kỳ thay đổi nào về giá trị $k$, thời gian chuyển động trong trường hợp đầu tiên lớn hơn $3 \sqrt{3}$ lần thời gian chuyển động trong trường hợp thứ hai.

Vì vậy, khi khoảng cách giữa các quả bóng

⟦folio 40⟧

$$\frac{t_2}{t_1} = 3\sqrt{3}$$

Đầu tiên, xét trường hợp tấm rơi thẳng đứng xuống dưới với vận tốc không đổi $v$. Các electron rơi cùng với tấm bị tác dụng bởi từ trường bởi lực Lorentz (Hình 13) $F_\pi = evB$ (e là điện tích của electron). Kết quả là các electron sẽ trộn lẫn về phía bên phải của tấm. Sự phân bố lại các electron bên trong tấm dẫn đến xuất hiện một điện trường hướng từ trái sang phải (xem Hình 13). Sự trộn lẫn các electron sẽ xảy ra cho đến khi lực Lorentz bên trái cân bằng với lực $F_3$ tác dụng từ điện trường: $F_\pi = F_3$, hoặc $evB = eE$. Do đó tính định hướng của điện trường $E = vB$.

Vì độ dày của tấm nhỏ hơn nhiều so với bán kính của nó nên điện trường bên trong tấm có thể được coi là đồng đều (có thể bỏ qua hiệu ứng cạnh). Điều này có nghĩa là bản tụ có thể được coi là một tụ điện phẳng, giữa các bản có hiệu điện thế là $u = Ed = Bvd$, điện tích của nó bằng

$$q = Cu = \frac{\varepsilon_0 S}{d} Bvd = \varepsilon_0 SBv$$

($S = \pi R^2$ là diện tích của tấm).

Điện tích này phụ thuộc vào tốc độ của tấm. Khi tấm chuyển động với một gia tốc nào đó, cùng với tốc độ của tấm theo thời gian, các điện tích ở hai bên của tấm cũng sẽ thay đổi. Do đó, khi tốc độ của tấm thay đổi sẽ xuất hiện một dòng điện trong đó

$$I = \frac{\Delta q}{\Delta t} = \varepsilon_0 SB \frac{\Delta v}{\Delta t} = \varepsilon_0 SB a$$

trong đó $a$ là gia tốc của tấm. Tuy nhiên, như chúng ta đã biết, một lực $F = BId$ tác dụng lên một dây dẫn có dòng điện đặt trong từ trường và hướng thẳng đứng lên trên. Vì vậy, ngoài lực hấp dẫn, một lực $F$ cũng sẽ tác dụng lên tấm kim loại khi nó rơi khỏi từ trường. Hãy viết phương trình chuyển động của tấm:

$$ma = mg - BId$$ hoặc $ma = mg - B^2 d\varepsilon_0 a\pi R^2$.

Từ đây

$$a = g \frac{1}{1 + \frac{B^2 d\varepsilon_0 \pi R^2}{m}}.$$

Tôi. Sh. Slobodetsky
