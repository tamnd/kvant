---
id: 1991-3-resheniya-zadach-m1246-m1249-f1258-f1262-613abe1a
issue: kvant_1991_3
year: 1991
number: "3"
title: Lời giải bài toán M1246—M1249; F1258—F1262
rubric: zadachnik-kvanta
rubric_sub: Задачник «Кванта»
page_first: 21
page_last: 30
page_labels: 19-28
lang: vi
source: kvant_digital
extraction: vision
content_sha256: 565b1de5916e2c0c5eb1ce41002efe09eb3115e0a5beb52337371c3aba540316
prompt_sha256: draft-1
translated_from: content/ru/1991/03/articles/06_resheniya-zadach-m1246-m1249-f1258-f1262-613abe1a.md
source_content_sha256: 8c0e6b3b9cc65e22307bb17765b5258fcd54518df606adec3bf5d74d6f1bceeb
translation_model: draft
translation_run: vi-draft-gaps-2026-11-06
translation_quality: draft
---

⟦folio 19⟧

Lời giải bài toán
M1246—M1249, F1258—F1262

M1246. Chứng minh rằng trong mọi cấp số cộng có các số tự nhiên luôn tồn tại hai số có tổng các chữ số bằng nhau.

Đặt $a$ là số hạng đầu tiên và $d$ hiệu của cấp số nhân. Tất nhiên, chúng ta có thể giả sử rằng $d>0$. Khi đó, tất cả các số hạng của một cấp số có dạng $a+10^n d$, trong đó $n$ đủ lớn (vì vậy $10^n>a$), có cùng tổng các chữ số, bằng tổng của tất cả các chữ số $a$ và $d$.

S. Genkin

⟦folio 20⟧

---
running_head:
folio:
---

M1247. Có thể phủ toàn bộ mặt phẳng bằng các hình vuông có độ dài cạnh 1, 2, 4, 8, 16, ... (không chồng lên nhau), sử dụng mỗi hình vuông không quá a) mười lần; b) một lần?

Hình 1.

Đáp số: a) có thể; 6) điều đó là không thể.
a) Một ví dụ về lớp phủ (trong đó hình vuông ở cạnh 1 được sử dụng 4 lần và phần còn lại - mỗi mặt 3 lần) được đưa ra trên hình 1.
6) Giả sử có một lớp phủ trong đó tất cả các hình vuông đều khác nhau. Vì tổng của tất cả các số, không vượt quá $2^n$, nhỏ hơn $2^n (1+2+2^2+\ldots+2^{n-1}=2^n-1)$, nên mỗi cạnh của bất kỳ hình vuông nào

Hình 2.

Hình 3.

Sản phẩm lớp phủ của chúng tôi nên được áp dụng cho các cạnh của một hình vuông lớn. Suy ra mỗi đỉnh của hình vuông phải nằm trên cạnh của hình vuông lớn (nếu đỉnh B của hình vuông ABCD nằm trên cạnh của hình vuông lớn áp dụng cho cạnh AB (hình 2) thì đỉnh C sẽ nằm trên cạnh của hình vuông lớn áp dụng cho BC, v.v.). Bây giờ chúng ta hãy xem xét tên của tất cả các ô vuông phủ sóng. Bốn hình vuông sẽ được áp dụng cho nó như trong hình 3. Hãy xem xét hình vuông lớn hơn trong số các hình vuông này - để nó áp dụng cho cạnh AB của hình nhỏ nhất (tại hình là hình vuông ở đầu). Khi đó đỉnh A của hình vuông này không nằm trên cạnh của hình vuông lớn hơn nó. Chúng tôi có một sự mâu thuẫn.

D. Fomin

M1248. Một phân đoạn chứa một số phân đoạn nhỏ hơn bao phủ toàn bộ phân đoạn đó.
a) Chứng minh rằng bất kỳ vị trí nào của các đoạn này, loại bỏ bất kỳ vị trí nào - phải hoặc trái - thì các vị trí còn lại sẽ có độ dài ít nhất gấp ba lần độ dài của đoạn ban đầu.

Trước tiên chúng ta hãy lưu ý rằng có thể loại trừ các phân đoạn hoàn toàn có trong các phân đoạn khác. Tiếp theo, sau khi đánh số các đoạn theo thứ tự tùy ý, chúng ta sẽ lần lượt thực hiện thao tác sau trên từng đoạn: ta sẽ thay đoạn đó bằng đoạn nhỏ nhất có cùng phần giữa để các đoạn vẫn bao phủ đoạn ban đầu. (Trong trường hợp này, các số hạng đã chọn sẽ bị giảm đi và phép kết của chúng sẽ chỉ trở nên nhỏ hơn.) Lặp lại các thao tác này, chúng ta đi đến một hệ thống trong đó mỗi đoạn có thể có các điểm chung bên trong (giao nhau dọc theo đoạn) mà không có nhiều hơn một trong các điểm khác. Do đó, toàn bộ phân đoạn ban đầu được chia thành nhiều phần, mỗi phần được bao phủ bởi một hoặc hai phân đoạn chứa trong đó. Vì vậy, chỉ cần chứng minh mệnh đề cho trường hợp có hai đoạn thẳng là đủ. Điều này không khó trong cả hai trường hợp.

⟦folio 21⟧

---
running_head:
folio:
---

Mệnh đề a) hiển nhiên nếu nửa bên trái của các đoạn không cắt nhau: xét cho cùng, tổng độ dài của hai đoạn lớn hơn độ dài $d$ phần nối của chúng, do đó tổng độ dài hai nửa của chúng lớn hơn $d/2$. Nếu hai nửa bên trái cắt nhau (hình 1), thì phát biểu xuất phát từ thực tế là trung điểm của đoạn bên phải nằm bên phải điểm giữa $C$ của toàn bộ mảnh $AB$ đang xét, tức là các nửa này bao phủ $AC$.

Câu 6) là hiển nhiên nếu ít nhất một trong các đoạn không nhỏ hơn $2/3$ $d$, trong đó $d$ là phần được che. Trong trường hợp khác (hình 2), khoảng cách giữa trung điểm $E$ và $F$ của chúng không nhỏ hơn $d/3$ và các nửa được chọn của các đoạn không giao nhau hoặc che phủ đoạn $EF$.

D. Fomin

M1249*. Có $n>6$ thành phố ở vương quốc Olympia, mỗi thành phố được kết nối bằng một con đường một chiều. Hơn nữa, không thể đi từ thành phố này sang thành phố khác (mà không vi phạm luật lệ giao thông).
a) Chứng minh rằng nhà vua có thể chọn một trong các thành phố $u$, thay đổi hướng của tất cả các con đường ra vào nó, thêm âm điệu để có thể đi từ thành phố này đến thành phố khác.
b) Câu này có đúng với $n=6$ thành phố không?

Trước tiên chúng ta hãy chứng minh khẳng định a) cho $n=7$, thành phố. Chúng ta sẽ nói rằng hai thành phố là tương đương nhau nếu có thể đi từ thành phố này đến thành phố kia. Khi đó tất cả 7 thành phố sẽ được chia thành các nhóm thành phố tương đương với nhau, và mỗi nhóm có hai nhóm, nhóm này “chính” nhóm kia, theo nghĩa mọi con đường từ nhóm này đều dẫn đến nhóm khác. Khoảng cách đầu tiên, khi có nhiều hơn hai nhóm như vậy. Đặt $y$ là nhóm áp chót (hình 1). Bằng cách chọn bất kỳ thành phố $Y$ nào trong nhóm $y$ và thay đổi hướng của tất cả các con đường nối nó với các thành phố khác, chúng tôi có được những gì mình đang tìm kiếm: từ $Y$ giờ đây bạn có thể đến nhóm $a$ và từ đó đến bất kỳ thành phố nào khác; và ngược lại, bạn có thể đến $Y$ từ nhóm cuối cùng $z$ và đến nhóm đó từ bất kỳ thành phố nào khác. Vẫn cần xem xét đầu tiên khi chỉ có hai nhóm (hình 2). Giả sử có $x$ thành phố trong nhóm $a$ và $(7-x)$ trong nhóm $b$. Chúng ta có thể giả sử rằng $x$ ít nhất là 4 (nếu không chúng ta sẽ thay thế tất cả các mũi tên bằng các mũi tên ngược lại). Hãy xem xét ba nhóm: 1) $x=4$; 2) $x=5$; 3) $x=6$. Tuy nhiên, chúng ta hãy thay thế ngay rằng nhóm $x=5$ là không thể, vì nhóm không thể bao gồm hai thành phố tương đương.

Đối với các mục đích khác, sẽ thuận tiện hơn khi sử dụng bổ đề sau:
Trong một nhóm gồm $k>3$ thành phố tương đương bất kỳ, luôn có một đường đi khép kín đi qua (theo hướng mũi tên) qua tất cả các thành phố một lần (“chu trình Hamilton”).

Chúng ta đưa ra chứng minh bổ đề ở cuối lời giải.

Hãy nhìn vào các nhóm còn lại. 1) Tại $x=4$ nhóm trông như thể hiện trong hình 3 (hướng của con đường thứ sáu, không hiển thị là không quan trọng). Là thành phố mong muốn, bạn cần giành được $C$. 3) Tại $x=6$ nhóm $a$ trông như trong hình 4 (hướng của các đường khác chưa tồn tại). Giả sử rằng không có thành phố nào trong đó, nếu hướng của tất cả các con đường thay đổi, thì có thể đi từ thành phố đó đến bất kỳ thành phố nào trong nhóm $a$, chúng ta có thể kết luận rằng các con đường được hướng như trong hình 5. Nhưng sau đó, bất kỳ thành phố nào trong số sáu thành phố đều có thể được chọn làm thành phố mong muốn.

⟦folio 22⟧

---
running_head:
folio:
---

Vì vậy, với phát biểu $n=7$ bài toán a) được chứng minh.
Với $n>7$ có thể chứng minh bằng quy nạp.
Trước hết, chúng ta hãy chọn trong số các thành phố một thành phố có ít nhất hai con đường đi vào và từ đó có ít nhất hai con đường đi ra. (Nếu không có thành phố như vậy thì có 4 thành phố, mỗi thành phố có không quá một con đường, hoặc 4 thành phố, từ đó không có nhiều hơn một con đường đi ra. Nhưng điều này là không thể, vì sáu con đường giữa bốn thành phố có 6 “điểm đầu” và 6 “điểm cuối”.) Trong số ($n-1$) thành phố còn lại, theo giả thuyết quy nạp, có một thành phố trong đó có thể đạt được hiệu quả mong muốn bằng cách “hình thành” tất cả các con đường. Nó rất/không phù hợp với tất cả $n$ thành phố.
Hình 6 cho thấy rằng đối với $n=6$ thành phố, câu phát biểu là sai, tức là đáp số đối với câu hỏi 6) là phủ định.
(Điều thú vị là ví dụ này là ví dụ duy nhất có thể nói là đẳng cấu.)
Để kết luận, chúng tôi chứng minh bổ đề về chu trình Gallton (đối với $k=3$ thành phố thì rất như vậy). Chúng ta sẽ tranh luận bằng quy nạp. Hãy xóa bất kỳ thành phố nào trong số $k>3$ - thành phố $X$. Nếu ($k-1$) thành phố còn lại sau điều này tạo thành một số nhóm tương đương (như trong hình 1, và các mũi tên neoctor từ nhóm $z$ đi đến $X$ và từ $X$ đến nhóm $a$), thì vì trong mỗi nhóm $a, b, ..., y, z$ có một chu trình Galiltonian theo giả định quy nạp nên chúng được kết hợp rất chặt chẽ của chu trình Gallton, đi qua tất cả $k$ thành phố. Nếu các thành phố ($k-1$) còn lại tạo thành một nhóm tương đương thì nhóm đó chứa chu trình Galiltonian và trong số các đường nối các thành phố này với $X$ có ​​cả những đường đi vào $X$ và rời khỏi nó. Đi qua chu trình này, chúng ta có thể tìm thấy hai thành phố lân cận sao cho từ thành phố thứ nhất có đường đến $X$, và ở thành phố thứ hai có đường từ $X$ (hình 7). Vì vậy, chúng ta có thể thêm $X$ vào vòng lặp này.
Lưu ý rằng bằng cách sử dụng bổ đề này, chúng ta có thể chứng minh mệnh đề a) ngay lập tức cho bất kỳ $n$ nào lớn hơn 7, gần giống như cách đã làm ở trên đối với các thành phố $n=7$.
I. Itgenberg, D. Fomin

F1258. Có một cuộn dây có bán kính $R$ đặt trên một bàn nằm ngang. Một sợi chỉ mỏng, nhẹ được quấn vào một cuộn dây; bán kính của cuộn dây là $r$. Sợi chỉ được luồn qua một lỗ nhỏ ở độ cao $h$ tính từ mặt bàn ($h>R$). Lúc đầu khung dây đứng yên, sợi dây đứng yên

Rõ ràng là cuộn dây được định vị như trong hình 1 bắt đầu ở bên phải. Chúng ta hãy xác định vị trí nào cuộn dây sẽ có tốc độ tối đa.

Tại một thời điểm tùy ý, ba lực tác dụng lên cuộn dây - lực căng chỉ $T$, có độ lớn bằng $F$, lực hấp dẫn $Mg$ và phản lực đỡ $F_p$ (hình 2). Chúng ta hãy xem xét khoảnh khắc của tất cả các lực đối với điểm tựa. Lực $Mg$ và $F_p$ có mômen bằng 0 và mô men của lực $T$ tăng tốc độ quay của cuộn dây theo chiều kim đồng hồ và do đó, làm tăng tốc độ của nó

⟦folio 23⟧

---
running_head:
folio:
---

chuyển động ngang về bên phải. Rõ ràng là tốc độ này sẽ đạt mức tối đa khi phần tiếp theo của đường đi qua điểm hỗ trợ (điểm $D$ trên hình 3). Khi chuyển động xa hơn, mô men lực $T$ sẽ đóng băng, sau một thời gian cuộn dây sẽ dừng lại và quay trở lại.

Để tính tốc độ cực đại của cuộn dây, người ta sử dụng định luật bảo toàn năng lượng - động năng của cuộn dây bằng ngoại lực. Nguồn năng lượng duy nhất ở đây là người thí nghiệm, người kéo đầu sợi dây với một lực $F$. Công do lực này thực hiện bằng

$$A = F \Delta l,$$

trong đó $\Delta l$ là chiều dài của sợi chỉ được căng qua lỗ khi cuộn dây di chuyển từ vị trí ban đầu đến vị trí mà chúng ta quan tâm. Hãy tìm $\Delta l$ bằng cách so sánh độ dài “tự do” của sợi chỉ ở vị trí ban đầu và cuối cùng (xem hình 3).

Đặt điểm $O$ là điểm cuối của sợi chỉ tại thời điểm ban đầu và điểm $G$ là điểm tiếp xúc giữa sợi chỉ và cuộn dây tại thời điểm cuối cùng. Để tìm sự tiếp tục của điểm này tại thời điểm ban đầu, chúng ta cuộn cuộn dây lại. Trong trường hợp này, sợi chỉ sẽ được quấn một phần trên các cuộn dây và điểm $G$ sẽ di chuyển đến điểm $G_1$ (điểm trung gian $G_2$ có được từ $G$ bằng cách chuyển song song cuộn dây từ vị trí cuối cùng sang vị trí ban đầu). Vì vậy, chiều dài của đoạn ren đang xét ở vị trí cuối cùng là $BO + OG$, ở vị trí ban đầu $OC + CG_1$. Đánh đồng hai biểu thức này, ta tìm được

$$\Delta l = BO = OC + CG_1 - OG.$$

Hãy tính toán tất cả các số lượng ở đây. Trực tiếp từ hình 3 chúng ta thu được

$$OC = h - R, OG = OD - DG = h / \cos \alpha - R \cos \alpha.$$

Nó vẫn còn để tính toán chiều dài của sợi chỉ trên cuộn. Hãy chia chiều dài này thành hai:

$$\cup CG_1 = \cup CG_2 + \cup G_1 G_2.$$

Khi cuộn dây lăn từ vị trí cuối cùng đến vị trí ban đầu thì góc quay của nó bằng

$$\beta = \angle G_1 E_1 G_2 = \frac{EE_1}{R} = \frac{AD - r}{R} = \frac{h tg \alpha - r}{R}.$$

Đối với các tư thế, độ dài của sợi chỉ trong khu vực từ $G_1$ đến $G_2$ là

$$\cup G_1 G_2 = r \beta = r \frac{h tg \alpha - r}{R}.$$

Đồng thời

$$\angle CE_1 G_2 = \angle EDG = \alpha,$$

có thể tạo dáng được

$$\cup CG_2 = r \alpha.$$

Cuối cùng chúng tôi nhận được

$$\Delta l = h - R + \frac{r}{R} (h tg \alpha - r) + r \alpha - \frac{h}{\cos \alpha} + R \cos \alpha,$$

⟦folio 24⟧

---
running_head:
folio:
---

hoặc, biểu thị tất cả các hàm của góc $\alpha$ theo $\sin \alpha = r/t$,

$$\Delta l = r \arcsin \frac{r}{R} - \frac{r^2}{R} + (h - R)(1 - \sqrt{1 - \left(\frac{r}{R}\right)^2}).$$

Bây giờ chúng ta tính động năng của chuyển động có tốc độ $v$, chuyển động quay với tốc độ tuyến tính cũng bằng $v$, do đó động năng của cuộn dây bằng

$$E_k = \frac{1}{2} M v^2 + \frac{1}{2} \frac{M}{2} v^2 = \frac{3}{4} M v^2.$$

Bây giờ từ định luật bảo toàn năng lượng $E_k = A$ ta thu được đáp số:

$$v = \sqrt{\frac{4}{3} \frac{F}{M} \left(r \arcsin \frac{r}{R} - \frac{r^2}{R} + (h - R)\left(1 - \sqrt{1 - \frac{r^2}{R^2}}\right)\right).}$$

Điều thú vị cần lưu ý là công thức đưa ra các giá trị có ý nghĩa cho $v$ và tại $r = R$, mặc dù trong trường hợp này sự cân bằng của mômen lực (xem hình 3) ​​​​không bao giờ xảy ra - mômen của lực căng không phải lúc nào cũng được cuộn dây gia tốc. Đồng thời, mặc dù cuộn là vô hạn nhưng chỉ có một phần sợi hữu hạn đi qua lỗ và tốc độ của cuộn bị hạn chế.

A. Khodulev

F1259. Còi phát ra âm thanh có tần số $f_0 = 2000 \Gamma$. Tần số âm thanh sẽ thay đổi như thế nào nếu nhiệt độ không khí tăng từ 20 đến 40 độ C? Tiếng còi sẽ tạo ra âm thanh như thế nào trong chuông hơi khi làm việc dưới nước, trong đó hỗn hợp thở gồm màu xanh lá cây và oxy được cung cấp ở áp suất 1,5 atm? Áp suất riêng phần của oxy được coi là 0,3 atm. Giọng nói của một người sẽ thay đổi như thế nào trong chiếc chuông này? Có cần thiết phải sắp xếp lại công việc sao cho âm thanh trong chuông giống như bên ngoài không?

Tần số của còi được xác định bởi kích thước của còi (phụ thuộc - nghịch đảo) và tốc độ âm thanh (phụ thuộc - trực tiếp). Nếu người tiền sử thay đổi kích thước của còi khi đun nóng từ 20 đến 40 độ C, thì mọi thứ được xác định bằng sự tăng tốc độ âm thanh (tỷ lệ thuận với căn bậc hai của nhiệt độ tuyệt đối) lên 313/293 = 1,033 lần. Điều này có nghĩa là tần số sẽ trở thành 2066 Hz. Tất nhiên, sự khác biệt không lớn lắm nhưng nó hoàn toàn không thể chấp nhận được đối với các nhạc cụ - đặc biệt là trong một dàn nhạc. Khi chế tạo hai thiết bị, các biện pháp đặc biệt được thực hiện để cài đặt thực tế không thay đổi khi nhiệt độ thay đổi trong giới hạn quy định. Hãy tự suy nghĩ làm thế nào điều này có thể đạt được.

Câu hỏi thứ hai có phần phức tạp hơn. Chúng ta hãy nhớ rằng chúng ta thường hít thở hỗn hợp oxy (khối lượng mol của nó là 32 g/mol) và nitơ (28 g/mol). Có nhiều nitơ hơn và hỗn hợp khí thu được có khối lượng mol trung bình là 29 g/mol. Hỗn hợp heli và oxy có khối lượng mol thấp hơn rõ ràng, và do đó tốc độ âm thanh trong hỗn hợp sẽ lớn hơn và âm sắc của lời nói của con người sẽ cao hơn (xét cho cùng, “kích thước” của bộ máy phát âm vẫn giữ nguyên). Việc còn lại là tìm khối lượng mol của hỗn hợp oxy và heli. Nó có thể được thực hiện như thế này.

⟦folio 25⟧

---
running_head:
folio:
---

Về thể tích $V$ số mol oxy là $v_{\kappa} = p_{\kappa}V/(RT)$, heli là $v_{\mathrm{r}} = p_{\mathrm{r}}V/(RT)$ và tổng khối lượng của hỗn hợp là $m = m_{\kappa} + m_{\mathrm{r}} = M_{\kappa}v_{\kappa} + M_{\mathrm{r}}v_{\mathrm{r}}$. Khi đó khối lượng mol của hỗn hợp
$$M = (p_{\kappa}M_{\kappa} + p_{\mathrm{r}}M_{\mathrm{r}})/(p_{\kappa} + p_{\mathrm{r}}) = 9,6 \text{ г/моль}.$$
Vì vậy, cao độ của âm sẽ tăng $\sqrt{29/9,6} = 1,74$ lần (bạn nhận được “giọng nói của Buratino”) và tần số của âm sẽ bằng 3480 Hz.
Nhưng bạn không cần phải chế tạo lại cây đàn guitar - tần số rung của dây được xác định bởi các thông số hoàn toàn khác nhau.
A. Zilberman

F1260. Chuỗi điện trở vô hạn nổi tiếng (hình 1) chứa các điện trở $r$ và $R$. Điện trở thay đổi giữa hai nút lân cận (cách nhau bằng một điện trở $r$) là bao nhiêu? Sự thay đổi điện trở giữa hai nút cách nhau rất xa là bao nhiêu? Tìm điện trở này trong trường hợp tổng quát khi có $n$ điện trở $r$ giữa các điểm mà chúng ta quan tâm.

Trong trường hợp đầu tiên, chuỗi có thể được vẽ lại như trong hình 2, trong đó $\rho$ là điện trở của chuỗi bán vô hạn được hiển thị trong hình 3. Từ sự tương ứng
$$r + \frac{R\rho}{R + \rho} = \rho$$
dễ dàng có được
$$\rho = r(1 + \sqrt{1 + 4R/r})/2.$$
Khi đó điện trở thay đổi giữa hai nút lân cận $A$ và $B$ sẽ bằng
$$R_1 = R_{AB} = \frac{2R\rho r}{2R\rho + rR + r\rho} = \frac{2Rr}{\rho + 2R}.$$
Nếu các nút $A$ và $B$ ở rất xa nhau thì mạch có thể được thay thế như trong Hình 4 và 5. Do đó
$$R_{\infty} = R_{AB} = \frac{2\rho R}{2R + \rho}.$$
Bây giờ hãy để có các liên kết $N$ trong chuỗi giữa $A$ và $B$. Hãy áp dụng nguyên lý chồng chất. Hãy kết nối pin có EMF $\mathcal{E}$ (hình 6) giữa nút $A$ và dây dưới cùng $O$. Nếu ta lấy điện thế của dây bằng 0 thì điện thế và điểm sẽ bằng nhau
$$\varphi_A = \mathcal{E}, \varphi_B = \mathcal{E}(1 - r/\rho)^N, \varphi_0 = 0, I_A = I = \mathcal{E}(1/R + 2/\rho), I_B = 0, I_0 = -I.$$
Nếu cùng với pin trước, chúng ta lấy một pin có cực ngược lại và kết nối nó giữa $O$ và $B$, thì

Hình 1.
Hình 2.
Hình 3.

⟦folio 26⟧

---
running_head:
folio:
---

chiến thuật và tiềm năng sẽ ngang nhau
$$\varphi'_A = -\mathcal{E}(1 - r/\rho)^N, \varphi'_B = -\mathcal{E}, \varphi'_0 = 0,$$
$$I'_A = 0, I'_B = -I, I'_0 = I.$$

Hãy cộng điện áp và điện áp trong hai tình huống này và nhận được
$$\varphi''_A = \mathcal{E}(1 - (1 - r/\rho)^N), \varphi''_B = -\mathcal{E}(1 - (1 - r/\rho)^N), \varphi''_0 = 0,$$
$$I''_A = I, I''_B = -I, I''_0 = 0.$$

Vì không có dòng điện chạy qua nút $O$ nên chúng ta có thể giả sử rằng điện trở giữa $A$ và $B$ bằng
$$R_N = R_{AB} = \frac{\varphi''_A - \varphi''_B}{I} = \frac{2R\rho}{2R + \rho} \left(1 - \left(1 - \frac{r}{\rho}\right)^N\right).$$

Lưu ý rằng với $N = 1$ chúng ta nhận được đáp số cho trường hợp đầu tiên và với $N \to \infty$ cho trường hợp thứ hai.

P. Rodin

F1261. Đối với một cục pin có điện áp $U_0 = 4$ V, hai tụ điện được mắc nối tiếp, điện dung của chúng là $C_1 = 1$ µF và $C_2 = 3$ µF. Nối cuộn cảm $L = 1$ song song với tụ điện $C_1$. Tìm biên độ dòng điện trong cuộn dây. Vào thời điểm cuộn dây được kết nối, điện áp trên tụ điện được coi là ổn định. Tổn thất trong mạch có thể được yêu cầu.

Để tìm cường độ dòng điện cực đại qua cuộn dây, cách dễ nhất là sử dụng định luật bảo toàn năng lượng. Tại thời điểm dòng điện qua cuộn dây đạt cực đại, nối emf cảm ứng $L = 1$ Gi song song với tụ điện $C_2$. Trước khi nối cuộn dây, điện tích mỗi tụ điện bằng nhau
$$q_0 = C_1 C_2 U_0 / (C_1 + C_2).$$

Điều này có nghĩa là pin đã “đẩy” điện tích bổ sung qua mạch điện
$$q_{6ат} = \Delta q = C_2 U_0 - q_0 = C_2^2 U_0 / (C_1 + C_2)$$
và đã làm việc đó
$$A_{6ат} = q_{6ат} U_0.$$

Hãy viết ra sự cân bằng năng lượng:
$$W_{нач} + A_{6ат} = W_{кон},$$

hoặc
$$C_1 C_2 U_0^2 / (2(C_1 + C_2)) + C_2^2 U_0^2 / (C_1 + C_2) = C_2 U_0^2 / 2 + LI_M^2 / 2.$$
Từ đây ta tìm được giá trị dòng điện lớn nhất trong cuộn dây:

⟦folio 27⟧

---
running_head:
folio:
---

$$I_M = C_2 U_0 / \sqrt{L} \left( \bar{C}_1 + \bar{C}_2 \right) = 6 \cdot 10^{-3} \text{A}.$$

Vậy qua cuộn dây nó có giá trị trung bình bằng 0 và thay đổi theo định luật điều hòa, nghĩa là biên độ của dòng điện bằng giá trị tính toán. Cố gắng tìm một phần độc lập của dao động trong hệ thống. Chỉ trong trường hợp - đáp số: khoảng 80 Hz.

R. Aleksadrov

F1262. Một quạt điện có chuyển động không đồng bộ, được kết nối với mạng 220 V, phát triển với tốc độ 1800 vòng/phút. Để nó không kêu quá lớn, nó được kết nối thông qua một bộ tạo tự động với điện áp 127 V. Nó sẽ quay với tốc độ bao nhiêu? Hãy xem xét rằng tải trên các cánh quạt được xác định bởi hiệu ứng quá dòng của dòng điện “bánh xe sóc”.

Trong động cơ một pha, từ trường quay đạt được nhờ sự lệch pha 90° của dòng điện xoay chiều hình sin có cường độ bằng nhau chạy qua hai cuộn dây stato vuông góc với nhau.

Trong trường hợp này, thành phần x của từ trường bằng $B_x = B_0 \cos \omega t$, thành phần y là $B_y = B_0 \sin \omega t$ và trường kết quả $\bar{B}_0$ quay trong mặt phẳng XY ngược chiều kim đồng hồ với tần số $\omega$ dòng điện cung cấp (hình 1).

Chúng ta hãy xem xét các lực tác dụng lên rôto, coi nó đơn giản là một khung kim loại hình chữ nhật tính từ các cạnh $a$ và $b$. Đầu tiên, chúng ta thảo luận về trường hợp khung có trục quay OZ đóng bất động trong mặt phẳng YZ và vectơ cảm ứng từ trường $\bar{B}_0$, nằm trong mặt phẳng XY, quay quanh trục của khung với tần số $\omega_0$ ngược chiều kim đồng hồ (hình 2). Thành phần trường vuông góc với mặt phẳng của khung bằng

$$B_\perp = B_0 \cos \omega_0 t,$$

song song -

$$B_\parallel = B_0 \sin \omega_0 t.$$

Từ thông, hệ quy chiếu tùy ý, bằng

$$\Phi = B_\perp S = B_0 S \cos \omega_0 t,$$

trong đó $S = ab$ là diện tích của khung. Emf cảm ứng phát sinh trong hệ quy chiếu là

$$\delta_i = -\Phi'(t) = B_0 S \omega_0 \sin \omega_0 t,$$

và dòng điện trong khung là

$$I = \delta_i / R = B_0 S \omega_0 / R \sin \omega_0 t,$$

trong đó $R$ là điện trở đa dạng. Mômen xoắn so với trục khung chỉ được tạo ra bởi các thành phần của lực Ampe vuông góc với mặt phẳng YZ, tác dụng lên các cạnh song song với trục—

$$F_{1\perp} = F_{2\perp} = F = B_\parallel Ib = B_0^2 b S \omega_0 / R \sin^2 \omega_0 t.$$

Tổng mômen của các lực này

$$M = 2 F a / 2 = B_0^2 S^2 \omega_0 / R \sin^2 \omega_0 t.$$

Giá trị trung bình của nó trong khoảng thời gian $T = 2 \pi / \omega_0$ là

$$\bar{M} = B_0^2 S^2 \omega_0 / (2 R).$$

⟦folio 28⟧

---
running_head:
folio:
---

Vì các quá trình vật lý được thảo luận ở trên chỉ được xác định bởi sự định hướng lẫn nhau và tốc độ góc quay tương đối của trường và khung, nên có thể thu được biểu thức cho mômen lực làm bung khung trong trường hợp khung quay phía sau trường với tần số $\omega$ của khung có thể thu được bằng cách thay thế $\omega_0 \rightarrow \omega_0 - \omega$:

$$\bar{M}_p = B_0^2 S^2 (\omega_0 - \omega) / (2R).$$

Ở $\omega = 0$, khi khung đứng yên thì biên độ của dòng điện cảm ứng và lực Ampe là cực đại. Ở $\omega = \omega_0$, khi khung quay đồng bộ với từ trường, lực điện động cảm ứng, dòng điện và mômen xoắn bằng 0, điều này chỉ có thể xảy ra nếu không có tải lên trục động cơ.

Do thiết bị, đặc biệt là trong quạt của chúng tôi, rôto có thể được biểu diễn dưới dạng kết hợp của một số khung, tuy nhiên, trong trường hợp này, mô men quay của lực sẽ tỷ lệ với bình phương biên độ của cảm ứng từ trường bên trong stato và chênh lệch tần số quay của trường và rôto. Độ lớn cực đại của cảm ứng từ trường $B_0$ tỷ lệ thuận với biên độ $I$ của dòng điện xoay chiều chạy qua cuộn dây stato và giá trị này, theo các điều kiện, tỷ lệ thuận với hướng $U$ trong mạng. Pozny

$$\bar{M}_p \sim B_0^2 (\omega_0 - \omega) \sim I_0^2 (\omega_0 - \omega) \sim U^2 (\omega_0 - \omega).$$

Chuyển từ tần số tròn sang tần số thông thường, chúng ta thu được biểu thức có dạng

$$\bar{M}_p = \alpha U^2 (v_0 - v),$$

trong đó $\alpha$ là hệ số tỷ lệ không đổi.

Bây giờ chúng ta hãy xem xét tác động của các lực gây ra hiện tượng giảm tốc phanh, mà trong trường hợp của chúng ta là do dòng chảy bị tác động gây ra. Để quạt tạo ra một luồng không khí có diện tích $S$ di chuyển với tốc độ $v$. Sau đó, trong thời gian ngắn $\Delta t$, một khối không khí $\Delta m = \rho Sv \Delta t$ chảy vào dòng chảy, trong đó $\rho$ là mật độ không khí. Sự thay đổi cơ năng của không khí này là

$$\Delta E_k = \Delta m v^2 / 2 = \rho Sv^3 \Delta t / 2,$$

và công suất cơ do quạt tạo ra bằng

$$N = \Delta E_k / \Delta t = \rho Sv^3 / 2.$$

Vì (từ các thông điệp động học) tốc độ của tia tỷ lệ với tần số quay của các cánh quạt và công suất có liên hệ với mô men của các lực bằng sự tương ứng $N = M\omega$, nên đối với mô men hãm của các lực tác dụng lên cánh quạt, ta thu được

$$M_T \sim \omega^2,$$ hoặc $M_T = \beta v^2,$

trong đó $\beta$ là hệ số tỷ lệ không đổi.

Cân bằng mômen quay và mô men hãm của các lực tác dụng lên rôto động cơ, ta thu được

$$\alpha U^2 (v_0 - v) = \beta v^2,$$ hoặc $v^2 = k U^2 (v_0 - v),$
