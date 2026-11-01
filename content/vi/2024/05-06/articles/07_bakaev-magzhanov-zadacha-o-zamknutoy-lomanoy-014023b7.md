---
id: 2024-5-6-bakaev-magzhanov-zadacha-o-zamknutoy-lomanoy-014023b7
issue: kvant_2024_5-6
year: 2024
number: 5-6
title: Bài toán về một đa tuyến khép kín
authors:
  - Бакаев Е. В.
  - Магжанов Д.
rubric: zadachnik-kvanta
rubric_sub: Задачник «Кванта»
page_first: 27
page_last: 34
page_labels: 25-31
lang: vi
source: kvant_digital
extraction: vision
content_sha256: c6dfd456fd725769f29715d178ae18a533538ed1bc9a08e88e8ed9ff41599676
prompt_sha256: draft-1
translated_from: content/ru/2024/05-06/articles/07_bakaev-magzhanov-zadacha-o-zamknutoy-lomanoy-014023b7.md
source_content_sha256: cbf156c4e6e7f1f7bcb0aed3dcf958a15286bf9bc1bc1f663302ba606afac834
translation_model: draft
translation_run: vi-draft-gaps-2026-11-01
translation_quality: draft
---

⟦folio 25⟧

Vấn đề về một đường gãy khép kín

E. BAKAEV, D. MAGZHANOV

Trong bài viết này chúng tôi sẽ trình bày lời giải bài toán M2785 “Sách Vấn Đề Lượng Tử” và thảo luận về một số vấn đề liên quan. Chúng tôi rất biết ơn P.A. Kozhevnikov, trước đây
người đã đặt ra lời giải thứ tư và thứ năm của đoạn a) của bài toán và bài toán 5 này.

Vấn đề M2785

Trên mặt phẳng đã cho có một tập hợp hữu hạn $S$ gồm $n > 2$ điểm ở vị trí tổng quát (tức là

DOI: https://doi.org/10.4213/kvant20240504

không có ba điểm nào thẳng hàng). Số lần không tự qua đường -
đối với các đường gãy liên kết $n$ đóng có đỉnh tại các điểm này sẽ được biểu thị
phần $f(S)$. Chứng minh rằng

a) $f(S) > 0$ cho bất kỳ $S$ nào;

b) $f(S) = 1$ khi và chỉ khi tất cả các điểm $S$ nằm trên bao lồi của tập hợp $S$;

b) nếu $f(S) > 1$ thì $f(S) \ge n - 1$; giá trị này đạt được khi ở bên trong bạn-

⟦folio 26⟧

---
running_head:
folio:
---

bao lồi của tập hợp $S$ chứa đúng một trong các điểm của nó;
d) nếu bên trong bao lồi của tập hợp $S$ có hai điểm của nó thì
$$f(S) \geq \frac{(n-2)(n-3)}{2}.$$
Hãy để $n > 2$. Chúng ta sẽ biểu thị $F(n)$ bằng-
giá trị lớn nhất có thể có của hàm $f(S)$
trên tất cả các bộ $S$ trong số $n$ điểm nói chung
quy định.
e) Chứng minh rằng $F(n) \geq 3 \cdot 2^{\frac{n-8}{3}}$.

Lời giải của điểm a)
Mỗi đường nét đứt khép kín về cái nào
khi chúng ta đang nói về điều kiện bài toán, chúng ta sẽ
nêu tên các quy định

Đầu tiên là lời giải.
Sắp xếp theo tọa độ
Bổ đề 1. Trên một mặt phẳng cho trước, hữu hạn
tập hợp các điểm ở vị trí tổng quát. Sau đó, bạn có thể kết nối tất cả các điểm bằng các đoạn
poppy để có được một đường gãy không tự giao nhau (không đóng).
Bằng chứng. Hãy để chúng tôi giới thiệu đồng Descartes
tọa độ. Hãy sắp xếp các điểm theo thứ tự tăng dần của hoành độ, và trong trường hợp bằng nhau, theo thứ tự tăng dần của thứ tự. Chúng tôi biểu thị các điểm được sắp xếp lần lượt là $A_1, A_2, \ldots, A_n$ và các giá trị hoành độ của chúng lần lượt là $x_1, x_2, \ldots, x_n$ (hình 1).
Hãy kết nối các điểm liên tiếp từ -
cắt thì hình chiếu của mỗi đoạn $A_i A_{i+1}$ là $[x_i, x_{i+1}]$. Điều này có nghĩa là các đoạn thẳng chỉ có thể có điểm chung tại các đỉnh của đường đứt nét. Đường đứt gãy được xây dựng.
Bổ đề 2. Giả sử điểm $X, Y \in S$ là
bạn rằng $XY - \delta$氨erm của bộ $S$ (m.e.
thùy $X$ và $Y$ – loại bỏ tối đa
điểm cách nhau trong tập hợp này).

Hãy để chúng tôi giới thiệu tọa độ Descartes sao cho trục x chứa $XY$. Khi đó, trong ký hiệu của bổ đề trước, $X$ và $Y$ là các điểm $A_1$ và $A_n$.

Bằng chứng. Để hình chiếu $P'$ lên đoạn $XY$ của một điểm $P \in S$ nào đó (khác với $X$ và $Y$) không nằm trên đoạn $XY$ (hình 2). Khi đó $PX > P'X \geq XY$ hoặc $PY > P'Y \geq XY$, nghĩa là $XY$ không phải là đường kính, ta có mâu thuẫn. Sledova-
Do đó, hình chiếu của tất cả các điểm đều nằm bên trong $XY$ nên tọa độ của điểm $X$ và $Y$ là tọa độ nhỏ nhất và lớn nhất của tọa độ
không có tất cả các điểm. Bổ đề đã được chứng minh.

Sử dụng các bổ đề này, chúng ta thu được lời giải của phần a) bài toán. Đặt $A, B \in S$ sao cho $AB - \delta$氨erm $S$. Hãy vẽ một đường tọa độ chứa đường kính - nó sẽ chia mặt phẳng thành hai nửa mặt phẳng (hình 3). Xét các điểm nằm trong

hình 3
nửa mặt phẳng thứ nhất, bao gồm cả ranh giới. Chúng ta hãy sắp xếp chúng và dựng một đường đứt nét, như trong chứng minh của Bổ đề 1. Theo Bổ đề 2, các điểm $A$ và $B$ là các điểm cực trị của đường đứt nét thu được và tất cả các đoạn đều nằm trong nửa mặt phẳng thứ nhất, bao gồm cả đường thẳng $AB$.

Hãy làm tương tự cho các điểm nằm trong nửa mặt phẳng thứ hai, bao gồm cả đường biên. Kết quả là, theo Bổ đề 1, chúng ta thu được một đường gãy khép kín có các liên kết không giao nhau trong nửa mặt phẳng. Rõ ràng, các liên kết từ các nửa mặt phẳng khác nhau cũng không giao nhau.

Thứ hai lời giải.
Sắp xếp theo góc cực
Xét điểm $X \notin S$ nằm bên trong hoặc trên bao lồi $S$

⟦folio 27⟧

---
running_head:
folio:
---

(hình 4). Chúng ta hãy giới thiệu tọa độ cực có tâm tại điểm này và biểu thị các điểm của tập hợp $S$ bằng $A_1, \ldots, A_n$ sao cho $0 \leq \varphi_1 < \varphi_2 < \ldots < \varphi_n < 2\pi$ là các góc cực tương ứng. Khi đó đường đứt nét $A_1A_2 \ldots A_nA_1$ là dây đai. Hơn nữa, rõ ràng là $X$ nằm trong vùng giới hạn bởi cực này. Chúng ta sẽ gọi vành đai thu được bằng cách xây dựng như vậy là vecrue cực không bao gồm $X$.

Bây giờ chúng ta hãy xem xét điểm $X \in S$ nằm bên trong bao lồi $S$ (hình 5), giới thiệu tọa độ cực có tâm tại $X$ và sắp xếp các điểm còn lại của tập hợp theo cách tương tự, ký hiệu là $A_1, \ldots, A_{n-1}$. Khi đó đường đứt nét là $A_iA_{i+1} \ldots A_{n-1}A_1 \ldots A_{i-1}XA_i$, trong đó $i \in \{1, 2, \ldots, n-1\}$ là dây đai. Rõ ràng là có $n-1$ những chiếc thắt lưng như vậy.

Nếu $X \in S$ nằm trên một bao lồi thì bằng cách này chúng ta chỉ có thể tạo được một đai $A_iA_{i+1} \ldots A_{i-1}XA_i$.

Chúng ta sẽ gọi các vành đai có thể thu được theo cách thứ hai (lấy điểm từ $S$ làm tâm tọa độ cực) bao gồm vectơ cực $X$.

Thứ ba lời giải.
Kết nối thân lồi

Xét bao lồi của tập $S$. Hãy gọi nó trước. Tiếp theo, đối với tập hợp các điểm còn lại (được bao bọc bên trong bao lồi thứ nhất), chúng ta cũng sẽ xem xét bao lồi, mà chúng ta sẽ gọi là bao lồi thứ hai (ví dụ được hiển thị trong hình 6). Chúng tôi sẽ tiếp tục hoạt động này càng lâu càng tốt. (Có thể bước cuối cùng được thực hiện với một tập hợp gồm một hoặc hai điểm.)

Hình 6

Bổ đề 3. Cho một đoạn nối các điểm từ bao lồi thứ $i$ và một điểm từ bao lồi thứ $(i+1)$. Khi đó nó không cắt bao lồi thứ $i$.

Bằng chứng. Điều này là như vậy bởi vì toàn bộ đoạn thẳng nằm bên trong đa giác lồi được hình thành bởi bao lồi thứ $i$ (có nghĩa là nó không giao nhau với nó).

Bổ đề 4. Các đầu của một đoạn bất kỳ $AB$ (không phải đoạn cuối cùng) của bao lồi thứ $i$ có thể được nối với các đầu của một đoạn thuộc bao lồi thứ $(i+1)$ (hoặc từ một điểm trong trường hợp bao lồi gồm một điểm) bằng hai đoạn sao cho chúng không cắt nhau.

Bằng chứng. Trường hợp lớp vỏ thứ $(i+1)$ bao gồm một điểm là rất rõ ràng - chúng ta chỉ cần vẽ hai đoạn từ $A$ và $B$ cho nó. Trường hợp lớp vỏ thứ $(i+1)$ gồm hai điểm $C$ và $D$ cũng được xác định: các đoạn $AC$ và $BD$ không cắt nhau hoặc các đoạn $AD$ và $BC$ không cắt nhau.

Chúng ta hãy xem xét trường hợp còn lại khi lớp vỏ thứ $(i+1)$ bao gồm nhiều hơn hai điểm. Chúng ta sẽ giả sử rằng $AB$ đi theo chiều ngang và điểm $A$ nằm ở bên trái của $B$ (hình 7). Đặt $X$ là một điểm gần với đường $AB$ từ lớp vỏ thứ $(i+1)$ (nếu có nhiều điểm trong số đó thì hãy chọn điểm ngoài cùng bên trái). Khi đó các đoạn $AX$ và $BX$ không giao nhau với bao lồi thứ $(i+1)$ (nếu không thì $X$ không phải là điểm đóng).

Xem xét các đường chứa các đoạn nối $X$ với các đỉnh lân cận từ bao lồi thứ $(i+1)$. Hãy gọi chúng là $m$ và $n$ sao cho $m$ giao với đường $AB$ về bên trái hơn $n$ giao với đường $AB$. Điểm giao nhau của $m$ với đường $AB$ được gọi là $M$ (nếu một trong các đường thẳng $m$ và $n$ song song với $AB$ thì chúng ta sẽ chỉ định nó là $m$ và đường còn lại là $n$; trong trường hợp này chúng ta sẽ lấy điểm $M$ còn lại vô tận

⟦folio 28⟧

---
running_head:
folio:
---

chỉ vào $AB$). Điểm giao nhau $n$ với đường $AB$ được gọi là $N$.
Đỉnh lân cận của $X$, nằm trên $m$, được gọi là $M_1$. Đỉnh lân cận của $X$, nằm trên $n$, được gọi là $N_1$. Đặt $P, Q \in AB$ là bất kỳ điểm nào sao cho $P$ nằm ở bên trái của $A$, $Q$ nằm ở bên phải của $B$.
Hãy xem xét ba so sánh.
1) Điểm $A$ nằm trên tia $MN$ (hình 8; trong trường hợp $M$ để vô tận
điểm ở xa, tia $MN$ là toàn bộ đường thẳng).
Hãy vẽ các đoạn $AX$ và $BM_1$.
2) Điểm $B$ nằm trên tia $NM$ (hình 9). Trường hợp này là “đối xứng” với trường hợp đầu tiên. Hãy vẽ các đoạn $AN_1$ và $BX$.
3) Điểm $A$ nằm trên tia $MP$, mochika $B$ nằm trên tia $NQ$ (hình 10). Sau đó, bạn có thể kết nối $A$ với $X$ và $B$ với $M_1$ mà không cần giao nhau.
Trong mọi trường hợp, sẽ không có giao điểm với lớp vỏ thứ $i$ theo Bổ đề 3.
Bổ đề 4 đã được chứng minh.

Hình 8

Bây giờ, hãy chọn bất kỳ phân đoạn nào $A_1B_1$ trong lớp vỏ thứ nhất và kết nối nó với một phân đoạn từ lớp thứ 2 (hình 11). Sau đó, chúng ta nối đoạn $A_2B_2$ từ lớp vỏ thứ 2, đoạn này không được nối với lớp vỏ thứ nhất, với đoạn từ lớp vỏ thứ 3, v.v. Trong mỗi thân lồi bằng một số lẻ, hãy điền vào phần giữa hai thân lồi liên tiếp, không bao gồm tứ giác được tạo thành bởi hai đoạn thẳng nối nhau. Trong mỗi vỏ có số lẻ hãy điền vào hình tứ giác này. Đường viền của hình được tô bóng là đường viền của tập hợp.

Thứ tư lời giải.
Phá vỡ chiều dài tối thiểu
Rõ ràng là tập hợp các đường đứt nét khép kín có thể vẽ qua $S$ là hữu hạn. Hãy chứng minh rằng đường đa giác có độ dài nhỏ nhất.
Giả sử có một số giao điểm $X$ của hai liên kết $AB$ và $CD$ của một đường đứt nét (hình 12). thay thế
Nếu hai đoạn này nằm trên $AC$ và $BD$ hoặc trên $AD$ và $BC$, thì ở một trong hai trường hợp, đường đứt nét sẽ vẫn được kết nối. Nhưng đồng thời, độ dài của nó sẽ giảm đi do hai bất đẳng thức tam giác: $AC < AX + XC$ và $BD < BX + XD$, từ đó suy ra $AC + BD < AB + CD$. Tương tự như vậy, $AD + BC < AB + CD$. Điều này có nghĩa là một đường đứt đoạn khép kín có độ dài tối thiểu là không tự giao nhau, tức là posyaom.

⟦folio 29⟧

---
running_head:
folio:
---

Thứ năm lời giải. cảm ứng
Trước tiên chúng ta chứng minh bổ đề sau.
Bổ đề 5. Cho một đa giác M và một điểm A cũng có đường thẳng l ngăn cách M và A (tức là M và A nằm đối diện với l). Khi đó một số cạnh M nhìn thấy được hoàn toàn từ điểm A (chúng ta sẽ nói rằng cạnh PQ nhìn thấy được hoàn toàn từ điểm A nếu không có điểm nào khác của đa giác bên trong tam giác APQ).
Bằng chứng. Hãy sơn mỗi cạnh của đa giác một màu khác nhau. Hãy xem xét hình chiếu tâm của đa giác từ điểm A đến đường thẳng l (ví dụ được hiển thị trong hình 13). Trên đường thẳng l

sẽ được hiển thị khi nhìn thấy đa giác từ điểm A. Ví dụ: nếu một mảnh của cạnh màu đỏ che khuất một mảnh của cạnh màu xanh, thì hình chiếu của cạnh màu đỏ được hiển thị trên đường thẳng l. Nếu một đỉnh được chiếu lên một điểm trên đường thẳng l thì ta sẽ vẽ trong hình chiếu hướng (mũi tên) trong đó cạnh này chặn cạnh kia, tức là điểm cuối của cạnh nào là hình chiếu của đỉnh.

Cho kết quả phép chiếu có k đoạn. Có k-1 điểm giữa chúng, một số trong đó chỉ ra hướng. Vì có nhiều đoạn hơn số điểm nên không có mũi tên nào trỏ đến bất kỳ đoạn nào. Điều này có nghĩa đây là hình chiếu của toàn bộ cạnh, tức là toàn bộ cạnh có thể nhìn thấy được từ điểm A.
Bổ đề đã được chứng minh.
Chúng ta hãy chứng minh điểm a) bằng cách sử dụng bổ đề này. Chúng ta sẽ tiến hành quy nạp lời giải trên n. Cơ sở cho n=3 điểm là rất tốt. Hãy lấy điểm A - đỉnh của bao lồi và loại bỏ nó khỏi tập hợp. Điểm A có thể được phân cách bằng một đường thẳng khỏi tập hợp các điểm khác. Chúng ta hãy áp dụng giả thuyết quy nạp cho nó: thông qua bộ này chúng ta có thể kiểm tra được dây đai. Theo bổ đề, PQ một phía

vành đai có thể nhìn thấy hoàn toàn từ điểm A. Thay thế cạnh PQ trong đa giác bằng đường đứt nét PAQ, chúng ta thu được đa giác cần thiết.

Lời giải điểm 6)
Trước hết chúng ta hãy chứng minh rằng nếu mọi điểm đều nằm trên một bao lồi thì f(S)=1. Hãy giả sử điều ngược lại. Khi đó, ngoài đai trùng với thân lồi còn có ít nhất một đai nữa. Nó chứa liên kết AB, là đường chéo của bao lồi. Mặt phẳng chứa AB chia mặt phẳng thành hai nửa mặt phẳng, mỗi nửa mặt phẳng chứa các điểm S. Các điểm của nửa mặt phẳng này không thể nối với các điểm của nửa mặt phẳng kia, vì nếu không chúng sẽ cắt AB. Điều này có nghĩa là đai không thể đóng được. Sự mâu thuẫn.

Bây giờ chúng ta sẽ chứng minh rằng nếu f(S)=1 thì mọi điểm đều nằm trên bao lồi. Hãy giả sử điều ngược lại. Bên trong bao lồi có một điểm A thuộc tập S. Xét việc bao gồm một đường tròn xung quanh A. Có n-1>1 trong số chúng, vì A nằm bên trong bao lồi. Sự mâu thuẫn.

Lời giải điểm c)
Chúng ta hãy sử dụng cấu trúc từ lời giải của phần thứ hai của điểm 6). Đối với n điểm, trong trường hợp có một điểm bên trong bao lồi, nó cho ước lượng f(S) ≥n-1.

Hãy chứng minh rằng nếu chỉ có một điểm bên trong bao lồi thì f(S)=n-1. Gọi X là một điểm bên trong bao lồi. Nó được nối với hai điểm A và B từ bao lồi và điểm lân cận. Ngược lại, dây đai sẽ tự giao nhau, vì liên kết nối các bộ phận của dây đai, gồm nhóm giữa A và B, phải cắt nhau AXB. Ngược lại, mỗi hàng xóm chỉ có thể được kết nối với hàng xóm của nó, nếu không thì mạng sẽ tự giao nhau với cùng một thông báo. Chúng ta nhận được rằng tất cả các cách xây dựng có thể đều đưa ra một tập hợp các vùng bao quanh X. Điều này có nghĩa là có n-1 trong số chúng.

Lời giải điểm d)
Cho các điểm P và Q của một tập hợp đã cho nằm bên trong bao lồi. Cân nhắc

⟦folio 30⟧

---
running_head:
folio:
---

viền hai cạnh $AB$ và $CD$ tùy ý của thân lồi. hình 14 cho thấy trường hợp hai cạnh này không có đỉnh chung, hình 15 – khi chúng có đỉnh chung. Số cách chọn chúng là $\frac{(n-2)(n-3)}{2}$, vì có $n-2$ các đoạn trong bao lồi.

Hãy chứng minh rằng có thể thực hiện ít nhất một trong hai việc trong bao lồi:
1) thay thế $AB$ bằng các phân đoạn $AP$ và $BP$ và $CD$ bằng các phân đoạn $CQ$ và $DQ$ để bạn có được một đa giác (tức là sẽ không có giao lộ tự),
2) thay thế $AB$ bằng các phân đoạn $AQ$ và $BQ$ và $CD$ bằng các phân đoạn $CP$ và $DP$ để bạn có được một đa giác.

Gọi $X$ là giao điểm của đường $AB$ và $CD$, và $Y$ là điểm trên đoạn $PQ$. Khi đó các đoạn $AB$ và $CD$ nằm trong các nửa mặt phẳng khác nhau so với $XY$ (các đỉnh của chúng chỉ có thể nằm trên $XY$ nếu đây là đỉnh chung của chúng và nó sẽ trùng với $X$), và các điểm $P$ và $Q$ cũng vậy. (Nếu không có điểm $X$, vì $AB$ và $CD$ song song nên ta sẽ cùng xét đường thẳng $XY$, đường thẳng đi qua $Y$ và song song $AB$ và $CD$.)

Trước tiên hãy xem xét trường hợp $P$ và $Q$ không nằm trên $XY$. Khi đó, nếu $AB$ và $P$ nằm trong cùng một nửa mặt phẳng thì các đoạn $AP$ và $BP$ nằm trong cùng một nửa mặt phẳng, còn các đoạn $CQ$ và $DQ$ - nằm trong một nửa mặt phẳng khác. Do đó, các đoạn $AP$, $BP$, $CQ$, $DQ$ không giao nhau và có thể xây dựng từ điểm 1). Nếu $AB$ và $Q$ nằm trong cùng một nửa mặt phẳng thì việc xây dựng từ điểm 2) cũng có thể thực hiện tương tự.

Nếu $P$ nằm trên $XY$ thì $Q$ cũng nằm trên $XY$. Lý do trên cũng có tác dụng trong trường hợp này, nếu các đoạn $AB$ và $CD$ không có đỉnh chung. Nếu chúng có một đỉnh chung thì nó trùng với điểm $X$, nhưng sau đó hóa ra các điểm $X$, $P$ và $Q$ trong tập hợp của chúng ta là thẳng hàng, nhưng chúng ta chỉ xem xét các điểm ở vị trí tổng quát.

Bằng chứng đã hoàn tất.

Bình luận. Mọi người có thể quan tâm hãy suy nghĩ về câu hỏi sau đây mà chúng tôi không có đáp số.

Giả sử có $k$ điểm bên trong bao lồi. $f(S)$ có thể được bao nhiêu điểm? Trước tiên chúng ta có thể xem xét các giá trị nhỏ của $k$:

1) Có đúng là nếu có ít nhất hai điểm bên trong bao lồi của tập hợp $S$ thì có cận dưới bậc hai trên $f(S)$ (tức là bạn có thể ước tính $f(S)$ bằng đa thức bậc hai)?

2) Có đúng là nếu bên trong một bao lồi tập $S$ chứa đúng ba điểm thì có một cận dưới bậc ba trên $f(S)$?

Lời giải điểm e)

Trước tiên chúng ta hãy xem xét trường hợp $n \leq 5$. Dễ hiểu là $F(3) = 1$, $F(4) \geq 2$, $F(5) \geq 2$, trong khi giá trị của biểu thức $3 \cdot 2^{\frac{n-8}{3}}$ nhỏ hơn 1 đối với $n=3$ và nhỏ hơn 2 đối với $n=4$ và $n=5$, nên bất đẳng thức được thỏa mãn.

Đối với $n \geq 6$, hãy xem xét các bao lồi lồng nhau liên tiếp, như trong lời giải thứ ba của phần a). Chọn một tập hợp điểm sao cho thân thứ nhất chứa 3, 4 hoặc 5 điểm và các bao lồi $k-1$ còn lại là các hình tam giác (tương ứng, $n$ bằng $3k$, $3k+1$ hoặc $3k+2$, $k \geq 2$). Khi đó có ít nhất 3 phương án để chọn đoạn đầu tiên. Khi nối các thân lồi, như trong lời giải thứ ba, có hai cách để chọn một đoạn trong mỗi tam giác (trong mỗi tam giác $k-1$, ngoại trừ cách cuối cùng). Sử dụng bất đẳng thức $3k+2 \geq n$, ta thu được

$$F(n) \geq 3 \cdot 2^{k-2} \geq 3 \cdot 2^{\frac{n-8}{3}}.$$

Nhiệm vụ lời giải.

⟦folio 31⟧

---
running_head:
folio:
---

Trên thực tế, người ta đã chứng minh rằng hàm $F(n)$ tăng trưởng thành $b^n$, trong đó $4,642 \leq b \leq 56$.
Các kết quả nổi tiếng về điều này có thể được đọc trong chương “Các bài toán về điểm ở vị trí tổng quát” trong cuốn sách của P. Brass, W. Moser, J. Pach “Khám phá bài toán hình học rời rạc” (MCNMO, 2021), cũng như trên trang web Erik Demaine: https://erikdemaine.org/polygonization/

Liên quan bài toán
1. Đặt đa giác đã cho và điểm $P$ ở bên trong đa giác đó. Có nhất thiết phải nhìn thấy toàn bộ cạnh nào của đa giác từ điểm $P$ không? Điều gì sẽ xảy ra nếu điểm $P$ nằm ngoài đa giác?
2. Có một số đoạn không giao nhau trên mặt phẳng. Có phải luôn luôn có thể kết nối các đầu của một số trong số chúng với các đoạn để thu được một đa tuyến khép kín không tự giao nhau không?

3. Tam giác của một tập hợp điểm là một đồ thị phẳng, trong đó các đỉnh là tất cả các điểm của tập hợp, các cạnh là các đoạn nối các điểm và tất cả các mặt, ngoại trừ mặt ngoài, đều là hình tam giác. Xét tam giác của tập hợp $S$. Có đúng là bất kỳ tam giác nào của tập hợp $S$ đều có thể được chuyển thành các trường bằng cách loại bỏ một số cạnh không?

4. Xét tập $S$ các điểm ở vị trí tổng quát. Chúng ta hãy nhìn vào tất cả các loại thắt lưng. Hãy để có nhiều hơn một. Có thể tất cả họ đều có một liên kết chung?

5 (P. Kozhevnikov, Cúp tưởng nhớ A.N. Kolmogorov, 2013). Trên mặt phẳng đã cho có một tập hữu hạn $S$ gồm $n > 2$ điểm ở vị trí tổng quát (tức là không có ba điểm nào nằm trên cùng một đường thẳng). Hãy xem xét tất cả các đa giác có tập đỉnh trùng với $S$. Có đúng là hợp của tất cả các đa giác như vậy nhất thiết phải trùng với bao lồi của tập hợp $S$?

THƯ MÔNG CỔ
(xem trang 2 của bìa)
Bạn có thể thấy mỗi từ được viết dưới dạng một dãy ký tự nằm trên một dòng dọc chung. Hai từ bắt đầu bằng âm $t$ bắt đầu bằng cùng một dấu $y$.
Từ đây chúng ta có thể gợi ý rằng chữ cái được sắp xếp theo thứ tự bảng chữ cái và hướng của nó là từ trên xuống dưới. Không khó để xác định một số dấu hiệu tương ứng với những gì:
sr kn m

Nguyên âm $y$ được viết là $q$ trong mọi trường hợp. Nếu nó ở đầu một từ thì trước nó là dấu “c”, giống với dấu của $a$ ở giữa từ. Dấu hiệu này luôn được đặt ở đầu một từ nếu nó bắt đầu bằng một nguyên âm; nếu các từ bắt đầu bằng $a$, dấu hiệu được lặp lại hai lần.

Khi đó o được viết là $q$.

Nhiệm vụ 1
“Khủng hoảng” – kimural, 2 – mark, 3 – Altai.
Từ 2 dường như có nghĩa là "tem" (trong tiếng Mông Cổ nó có nghĩa là "tem bưu chính"). Từ 3 có nghĩa là Altai (khu vực địa lý hoặc dãy núi Altai).

Nhiệm vụ 2
Söri “ngăn xếp” có mục đích “đồi trụy” ​​ý “Ý”

(ở cuối chữ $a$ và $n$ không phân biệt được).

⟦folio none⟧

---
running_head:
folio:
---

Để nghiên cứu một sự kiện trong thế giới hiện tượng vật lý, trước tiên bạn phải biết nó xảy ra ở đâu và khi nào. Trả lời câu hỏi ở đâu? - có nghĩa là chỉ nơi giác ngộ...

Arthur Chernin

Việc ba điểm trên mặt phẳng xuất hiện để liên kết các trọng số như vậy sao cho điểm thứ tư đã cho trở thành tâm của chúng ... đã đưa tôi đến một phương pháp mới để xác định các điểm trên mặt phẳng.

Tháng Tám Mobius

Hãy vẽ hai đường thẳng (trục tọa độ) cắt nhau vuông góc và đặt vị trí của hạt... bằng khoảng cách từ nó đến từng trục.

Richard Feynman

...định luật tự nhiên không cho phép chúng ta biết cả vị trí lẫn vận tốc của một hạt với bất kỳ độ chính xác nào mà chúng ta mong muốn.

Werner Heisenberg

Điều này xảy ra trong không gian pha của một trong nhiều hệ kín. Phối hợp sau những hành trình dài tôi mệt mỏi và kiệt sức hoàn toàn.

Lev Blumenfeld
