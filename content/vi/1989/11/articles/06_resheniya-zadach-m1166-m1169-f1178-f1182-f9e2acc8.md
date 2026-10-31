---
id: 1989-11-resheniya-zadach-m1166-m1169-f1178-f1182-f9e2acc8
issue: kvant_1989_11
year: 1989
number: "11"
title: Lời giải bài toán M1166—M1169; F1178—F1182
rubric: zadachnik-kvanta
rubric_sub: Задачник «Кванта»
page_first: 27
page_last: 31
page_labels: 25-29
tag: 7B0G
lang: vi
source: kvant_digital
extraction: vision
content_sha256: 6c27eb79a0a12fd2641634fa6d348df159ae836554b4c0a41c1499eafcad0f81
prompt_sha256: draft-1
translated_from: content/ru/1989/11/articles/06_resheniya-zadach-m1166-m1169-f1178-f1182-f9e2acc8.md
source_content_sha256: 912e3ef86823eae774e5ec35066a26a0794073580d0ce1bfce1bb6ba34099cea
translation_model: draft
translation_run: vi-draft-2026-10-31
translation_quality: draft
---

⟦folio 25⟧

Lời giải bài toán
M1166 — M1169, F1178 — F1182

Thay thế $p, q, r$ bằng các số đối của chúng nếu cần, chúng ta có thể quy vấn đề về trường hợp hai trong số các số $p, q, r$, ví dụ $p$ và $q$, không dương và số thứ ba (số $r$) không dương. Do đó, theo bất đẳng thức tam giác $c^2 \geq (a-b)^2$,
$$a^2 pq + b^2 qr + c^2 rp \leq a^2 pq + b^2 qr + (a-b)^2 rp = a^2 p(q+r) + b^2 r(q+p) - 2abrp = -(ap+br)^2 \leq 0.$$
Vâng. Sh. Mustafaev

M1167. Có bao nhiêu hoán vị của các số $1, 2, ..., n$ trong đó, với bất kỳ số $i$ nào không đứng ở vị trí đầu tiên thì ít nhất một trong các số $i-1$ và $i+1$ nằm ở bên trái của $i$?

Đáp số: $2^{n-1}$. Đặt số $k$ ở vị trí đầu tiên. Lưu ý rằng nếu $k > 1$ thì các số $k-1, k-2, ..., 1$ nằm trong hoán vị của chúng ta theo thứ tự giảm dần (nếu chúng ta di chuyển từ trái sang phải). Thật vậy, theo điều kiện, ở bên trái của số 1 phải có 2, ở bên trái của 2-1 hoặc 3, tức là 3, ở bên trái của 3-2 hoặc 4, tức là 4, v.v. Tương tự, với $k < n$ số $k+1, k+2, ..., n$ theo thứ tự tăng dần, vì ở bên trái của $n$ phải có $n-1$, ở bên trái của số $n-1$ là số $n-2$, v.v. Do đó, bất kỳ hoán vị được sắp xếp lại nào cũng được xác định duy nhất bởi tập hợp các vị trí bị chiếm bởi các số $1, 2, ..., k-1$ (những vị trí như vậy có thể không tồn tại nếu $k=1$, tức là đối với hoán vị $1, 2, ..., n$). Số lượng các bộ này bằng số tập hợp con của tập hợp các phần tử $n-1$ - tất cả các vị trí ngoại trừ vị trí đầu tiên, tức là $2^{n-1}$.

A. V. Anzhans

M1168*. Đất nước có 1989 và 4000 (mỗi con đường nối hai thành phố). Chứng minh rằng có thể chọn được một đường vòng đi qua không quá 20 thành phố.

Hãy gọi một thành phố là “ngược dòng” nếu có không quá 2 con đường dẫn từ nó. Hãy xóa thành phố thuộc tỉnh vành đai, nếu có, khỏi bản đồ đất nước, cùng với những con đường dẫn từ đó. Hãy tạo một bản đồ mới theo cách tương tự và tiếp tục xóa các thị trấn cấp tỉnh cho đến khi chúng biến mất. Số lượng đường mà chúng ta có thể xóa trong trường hợp này không vượt quá 2·1989, tức là nhỏ hơn 4000; nên ít nhất một thành phố sẽ còn lại.

Hãy chọn bên trái trong số các thành phố còn lại. Ít nhất 3 con đường thoát ra khỏi nó, cũng như từ các thành phố còn lại khác. Hãy đi dọc theo một trong số chúng và mỗi khi đến một thành phố mới, chúng ta sẽ ngạc nhiên hơn nữa dọc theo một trong những con đường, khác với con đường mà chúng ta đã đi qua. Nếu 2 tuyến đường bất kỳ bao gồm không quá 10 đường kết thúc ở cùng một thành phố thì chúng ta sẽ nhận được tuyến đường vành đai mong muốn không quá 20 đường (xem hình). Nhưng không thể khác được, vì số lượng tất cả các tuyến đường như vậy không nhỏ hơn $3+3\cdot 2+3\cdot 2^2+...$

⟦folio 26⟧

...+3 · 2^9=3069, và số lượng thành phố, tức là số điểm cuối có thể có của các tuyến đường này, không quá năm 1989.

lời giải này có thể được khái quát hóa cho trường hợp $n$ thành phố và $m$ đường. Là kết quả của việc “phân chia” bản đồ hiện trạng thành phố, từ đó có ít nhất $s$ đường, trong đó $s$ là số nhỏ nhất sao cho $s \geq m/n$. Và sự khác biệt với các tuyến đường không giao nhau cho phép chúng ta chứng minh sự tồn tại của một chu kỳ (tuyến đường tròn) của $l$ đường, trong đó

$$l \leq 2[\log_{s-1} \frac{n(s-2)+2}{s} +1]$$

(dấu ngoặc vuông chỉ phần nguyên của số). Cụ thể, với $n=1989$ và $m=4000$, chúng ta nhận được $s=3$ và $l \leq 20$.

Một câu hỏi thú vị khác là: với bao nhiêu con đường $m$ giữa $n$ thành phố, chúng ta có thể tìm thấy một hệ thống đường không chứa các chu trình có độ dài $d$? Sử dụng một ước tính khá phức tạp về số lượng đường trung bình trong một hệ thống như vậy, có thể thấy rằng điều này có thể thực hiện được với

$$m < p \left( \frac{n(n-1)}{2} - \frac{n^2}{2d} \right),$$ ở đâu $p=n^{-\frac{d-2}{d-1}}$.

A. A. Razborov

**M1169. Giả sử $M$ là một điểm nằm bên trong đường thẳng ABCD, có diện tích $S$. Chứng minh bất đẳng thức $S \leq AM \cdot CM + BM \cdot DM$.**

Rõ ràng là diện tích của hình chữ nhật gấp đôi tổng diện tích của các tam giác AMD và BMC. (Để chứng minh, chỉ cần kiểm tra qua $M$ đường thẳng song song với $AD$, rồi tính diện tích của mỗi đường thẳng/đường thẳng tạo thành.) Áp dụng cho cạnh $AD$ tam giác VÀ bằng CMB sao cho $AN=CM$, $DN=BM$ (xem hìnhok). Sau đó

$$S = 2(S_{AMD} + S_{BMC}) = 2S_{AMDN} = 2S_{AMN} + 2S_{DMN} \leq AM \cdot AN + DN \cdot DM = AM \cdot CM + BM \cdot DM,$$

Q.E.D.

Tôi. Vâng. Goldsheid

**F1178. Một tấm ván ép rơi vào không gian. Hóa ra tại một thời điểm nào đó vận tốc của hai điểm trên tấm $a$ và $b$ bằng nhau - $\vec{v}_a = \vec{v}_b = \vec{v}$ - và nằm trong mặt phẳng của tấm. Hóa ra là sco-**

Chúng ta hãy tưởng tượng chuyển động phức tạp của tất cả các điểm của tấm gỗ dán tại một thời điểm xác định là tổng của hai chuyển động đơn giản - tịnh tiến cùng với các điểm $a$ và $b$ (và do đó cùng với đường thẳng $ab$) và quay tương đối với trục $ab$.

Hãy xem xét điểm $c$. Vectơ vận tốc $\vec{v}_c$ của nó bao gồm vectơ $\vec{v}$, tương ứng với chuyển động tịnh tiến và vectơ $\vec{v}_{bp}$, tương ứng với chuyển động quay

⟦folio 27⟧

tốc độ tăng của một điểm trên tờ c, nằm từ các điểm a và b ở khoảng cách bằng khoảng cách giữa các điểm a và b, gấp đôi tốc độ v. Ở đâu trên tờ giấy lúc này là những điểm có tốc độ bằng 3v?

Hình 1.

Hình 2.

Chuyển động và các vectơ $\vec{v}$ và $\vec{v}_{\text{bp}}$ vuông góc với nhau (hình 1):

$$\vec{v}_c = \vec{v} + \vec{v}_{\text{bp}},$$
hoặc $v_c^2 = v^2 + v_{\text{bp}}^2.$

Vì $v_c = 2v$, chúng tôi nhận được

$$v_{\text{bp}} = \sqrt{3}v.$$

Bây giờ chúng ta hãy tìm khoảng cách từ điểm c đến đường thẳng ab. Các điểm a, b và c là các đỉnh của một tam giác đều (hình 2). Hãy biểu thị cạnh của nó, ví dụ ab, bằng l. Khi đó khoảng cách chúng ta quan tâm

$$d = l \frac{\sqrt{3}}{2}.$$

Rõ ràng là các điểm mong muốn của tấm ván ép, tốc độ lớn hơn v gấp 3 lần về giá trị tuyệt đối, nằm trên hai đường thẳng song song với trục ab và cách nó một khoảng L nhất định. Để tìm khoảng cách này, chúng ta tiến hành như sau. Tương tự với điểm c, chúng ta biểu thị tốc độ của các điểm cần tìm bằng tổng các vận tốc $\vec{v}$ và $\vec{v}'_{\text{bp}}$ vuông góc với nhau:

$$(3v)^2 = v^2 + (v'_{\text{bp}})^2,$$

chúng ta lấy nó từ đâu

$$v'_{\text{bp}} = 2\sqrt{2}v.$$

Bây giờ hãy so sánh tốc độ $v_{\text{bp}}$ và $v'_{\text{bp}}$. Một mặt,

$$\frac{v_{\text{bp}}}{v'_{\text{bp}}} = \frac{\sqrt{3}v}{2\sqrt{2}v} = \frac{\sqrt{3}}{2\sqrt{2}},$$

mặt khác -

$$\frac{v_{\text{bp}}}{v'_{\text{bp}}} = \frac{d}{L} = \frac{l\sqrt{3}/2}{L}.$$

Như vậy,

$$\frac{l\sqrt{3}/2}{L} = \frac{\sqrt{3}}{2\sqrt{2}},$$
và $L = l\sqrt{2}$.

K. S. Sergeev

F1179. Nếu sét đánh xuống mặt nước trong cơn giông bão, thì sau cơn giông, người ta đôi khi nhìn thấy cá chết nổi trên mặt hồ. Làm thế nào để bắt buộc? Suy cho cùng, xác suất sét đánh trúng một con cá sống ở vùng nước thấp là rất thấp.

Tất nhiên, con cá bị giết không phải do sét đánh trực tiếp mà do dòng điện truyền qua nước. Khi bạn di chuyển ra khỏi vị trí bị sét đánh, mật độ dòng điện giảm dần. Sự chênh lệch điện thế xuất hiện trên cơ thể cá tỷ lệ thuận với cường độ dòng điện và mật độ dòng điện nhất định truyền qua nước. Cá nằm trong khu vực có mật độ dòng điện vượt quá giá trị tới hạn sẽ chết. Kích thước đặc trưng của khu vực này dao động từ vài mét đến vài mét,

⟦folio 28⟧

Và có thể có một số loài cá ở vùng nguy hiểm này.

Trong một số trường hợp, tình huống tương tự có thể xảy ra khi điện áp cao quay và rơi xuống đất. Trong trường hợp này, mật độ dòng điện chạy qua mặt đất tăng lên khi nó đến gần nơi dây rơi. Mức độ nguy hiểm đối với một người được đặc trưng ở đây bởi cái gọi là “điện áp bước” - điện áp phát sinh giữa hai chân của một người khi tiếp xúc với mặt đất. Rõ ràng là các bước nhỏ sẽ dẫn đến điện áp bước thấp hơn - đó là lý do tại sao cần phải rời khỏi vùng nguy hiểm nơi có ống bịt kín trong các bước nhỏ.

A. I. Buzdin

F1180. Bóng đèn nối với pin sẽ cháy trong ba giờ, sau đó pin sẽ cạn kiệt. Chúng tôi đã tạo một bản sao của loại pin này với kích thước tuyến tính gấp đôi từ cùng một vật liệu. Bóng đèn tương tự sẽ sáng trong bao lâu khi được kết nối với một bản sao như vậy? Điện trở trong của pin nhỏ hơn nhiều so với điện trở của bóng đèn.

Vì suất điện động của nguồn dòng hóa học chỉ được xác định bởi thành phần hóa học của nó nên suất điện động của bản sao sẽ bằng suất điện động của pin. Đặt emf này bằng $\mathcal{E}$, điện trở của bóng đèn là $R$ và điện trở trong của nguồn là $r$. Khi đó tổng công suất giải phóng trong mạch pin là $P_1 = \mathcal{E}^2 / (R + r_1)$ và trong mạch sao chép - $P_2 = \mathcal{E}^2 / (R + r_2)$. Vì $r_1 \ll R$ và do đó $r_2 \ll R$,

$$P_1 \approx P_2 \approx \frac{\mathcal{E}^2}{R}.$$

Nguồn dòng điện hóa học hoạt động bằng cách tiêu thụ năng lượng của các chất hóa học được lưu trữ trong nó. So với pin, bản sao chứa lượng thuốc thử nhiều hơn $2^3 = 8$ lần, do đó, với cùng công suất, nó có thể thực hiện cùng một lượng công việc. Điều này có nghĩa là bóng đèn kết nối với bản sao sẽ sáng trong 24 giờ.

K. S. Bedov

F1181. Một vật liệu dẫn điện mỏng, cứng đâm vào bề mặt nằm ngang không dẫn điện và nằm trong một từ trường đều, các đường cảm ứng của nó nằm ngang. Khối lượng vòng $m$, bán kính $R$, giá trị chỉ số $B$. Phải cho dòng điện chạy qua cái gai bằng bao nhiêu để nó bắt đầu nhấc lên?

Chúng ta hãy nhìn vào chiếc nhẫn khi nó vẫn ở vị trí nằm ngang (xem hình; nó hiển thị góc nhìn từ trên xuống). Chúng ta hãy đánh dấu trên đó kích thước của các điểm $C$ và $D$, hai phần nhỏ có chiều dài $\Delta l$ mỗi phần, nằm đối xứng với đường kính của vòng $AB$. Đoạn thứ nhất chịu tác dụng của lực thẳng đứng hướng xuống

$$\Delta F_1 = BI \Delta l \sin \alpha = BI \Delta x,$$

trong đó $\Delta x$ là hình chiếu của đoạn $\Delta l$ lên hướng của đường kính $AB$. Đoạn thứ hai chịu tác dụng của lực thẳng đứng hướng lên

$$\Delta F_2 = BI \Delta l \sin \alpha = BI \Delta x.$$

⟦folio 29⟧

Các lực này, có độ lớn giống nhau và hướng ngược nhau, đại diện cho một cặp lực tạo ra mômen quay so với trục $AB$

$$\Delta M = \Delta F_1 l_{CD} = BI \Delta x l_{CD} = BI \Delta S,$$

trong đó $\Delta S$ là diện tích của phần đường viền được tô bóng trên hình.

Chia toàn bộ chiếc nhẫn thành các cặp phần nhỏ tương tự nằm đối xứng với đường kính $AB$. Khi đó, chúng ta thu được rằng một vòng dẫn mỏng có dòng điện $I$, nằm trong từ trường nằm ngang có cảm ứng $B$, sẽ chịu một mômen lực từ bằng

$$M_{\text{магн}} = BIS = BI \pi R^2.$$

Anh ta quay chiếc nhẫn quanh trục ngang $AB$.

Khi vòng chuẩn bị nâng, hai lực cơ học sẽ quay ngược lại - lực hấp dẫn $mg$, tác dụng tại tâm vòng và theo hướng thẳng đứng hướng xuống, và phản lực pháp tuyến $N$, tác dụng tại điểm tiếp xúc của vòng và mặt phẳng và theo hướng thẳng đứng hướng lên trên. Vì chiếc nhẫn vẫn ở trạng thái cân bằng,

$$mg - N = 0, \text{ т. е. } N = mg,$$

do đó các lực cơ học tạo thành cặp lực riêng của chúng, lực này tạo ra mômen xoắn riêng

$$M_{\text{мек}} = mgR.$$

Từ trạng thái cân bằng của vòng, suy ra tổng mô men của tất cả các lực - trong trường hợp của chúng ta đây là tổng mômen của lực từ và lực cơ - bằng 0:

$$M_{\text{магн}} - M_{\text{мек}} = 0, \text{ или } BI \pi R^2 - mgR = 0.$$

Từ đây giá trị hiện tại được tìm thấy:

$$I = \frac{mg}{\pi BR}.$$

S. S. Krotov

F1182. Khi tiến hành định vị vô tuyến Mặt trăng đã nhô lên trên đường chân trời, để đảm bảo tính định hướng trở lại, bộ phát các cảnh vô tuyến tần số cao được kết hợp với kính thiên văn quang học. Tuy nhiên, với sự hiện diện của hình ảnh quang học của Mặt trăng, không có cảnh sóng vô tuyến phản xạ nào. Đồng thời, khi có thể thu được bức xạ phản xạ

Hiện tượng được mô tả thực sự đã xảy ra - tác giả gặp phải nó khi đang nghiên cứu một kênh liên lạc trong đó Mặt trăng được sử dụng làm vật phản xạ thụ động của hệ thống vô tuyến. Hơn nữa, ăng-ten kết nối với kính thiên văn quang học không nhằm mục đích hoạt động với Mặt trăng mà để thu truyền hình vệ tinh.

Khi Mặt trăng nhô lên trên đường chân trời, sự khúc xạ ánh sáng rất đáng kể, tức là các tia sáng bị bẻ cong do khúc xạ trong khí quyển. (Ví dụ, hãy nhớ rằng hình dạng và kích thước của Mặt trăng và Mặt trời bị biến dạng đến mức nào khi chúng ở thấp phía trên đường chân trời.) Đối với sóng vô tuyến (sử dụng sant-
