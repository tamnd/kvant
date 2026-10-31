---
id: 1977-11-resheniya-zadach-m431-m433-f442-f444-5a773a40
issue: kvant_1977_11
year: 1977
number: "11"
title: Lời giải bài toán M431—M433; F442—F444
rubric: zadachnik-kvanta
rubric_sub: Задачник «Кванта»
page_first: 51
page_last: 53
page_labels: 49-51
tag: 32ZX
lang: vi
source: kvant_digital
extraction: vision
content_sha256: ad43c9c9433cf86128169bdbd70f8e8747cc8d1729a2008b85d5a742a81747bb
prompt_sha256: draft-1
translated_from: content/ru/1977/11/articles/13_resheniya-zadach-m431-m433-f442-f444-5a773a40.md
source_content_sha256: 6544da969551fc965bf41179e9a3871c911adfd75ea89f2c62fee8b55b9c429a
translation_model: draft
translation_run: vi-draft-2026-10-31
translation_quality: draft
---

⟦folio 49⟧

Lời giải bài toán
M431—M433; F442—F444

M431. Cây hình trụ mọc trong rừng. Cần có kết nối để căng một sợi dây xuyên rừng từ điểm A đến điểm B, khoảng cách giữa chúng bằng l. Chứng minh rằng để nối một đoạn dây dài 1,6 l là đủ để nối.

Hãy nối các điểm A và B. Ở những nơi không có cây xanh, chúng ta sẽ vẽ một sợi dây dọc theo grama này. Ở cùng một nơi mà đường thẳng AB cắt đường viền của thân cây, chúng ta hãy chạy dây dọc theo vòng tròn nhỏ hơn trong hai vòng tròn, giới hạn tiết diện của thân cây bằng một mặt phẳng vuông góc với thân cây (xem Hình 1). Hãy chứng minh rằng trong trường hợp này chiều dài của dây không vượt quá $\frac{\pi l}{2}$.

Gọi $a_1, \dots, a_n$ là độ dài đoạn thẳng của sợi dây, và $b_1, \dots, b_k$ là độ dài đoạn thẳng AB nằm bên trong các ống. Vì mỗi $b_i$ ($i=1, \dots, k$) không vượt quá đường kính của hình tròn tương ứng, tổng chiều dài các phần cong của dây không vượt quá $\frac{\pi b_1}{2} + \dots + \frac{\pi b_k}{2}$ và tổng chiều dài của dây không vượt quá $\frac{\pi l}{2}$, nên không thể thay thế ít hơn trong bất đẳng thức này, vì dễ dàng chỉ ra một ví dụ khi cần một sợi dây có chiều dài $\frac{\pi l}{2}$: một cây có đường kính l mọc trong rừng, và điểm A và B là các điểm đối xứng về đường kính trên chu vi thân của nó.

A. Altschiller

Cơm. 1.

M432. Có hình vuông hoàn hảo nào có tổng các chữ số bằng
a) 1977;
b) 1978?
c) Tìm những số tự nhiên nào bằng tổng các chữ số của bình phương một số nguyên.

Hãy giải ngay điểm b) bài toán. Trước hết, chúng ta lưu ý rằng tổng các chữ số của một hình vuông không thể tùy ý. Thật vậy, bình phương của số người yêu với 9 hoặc khi chia cho 9 sẽ có số dư là 1, 4, 7. Khi chia cho 9, điều tương tự cũng đúng đối với tổng các chữ số của một bình phương, do đó đối với một bình phương tổng các chữ số có thể có dạng 9k, hoặc 9k+1, hoặc 9k+4, hoặc 9k+7. Hãy để chúng tôi chứng minh rằng tất cả các số như vậy thực sự có thể là tổng.

Thật vậy, số 9k là tổng các chữ số của bình phương số $10^k-1$:

$$(10^k-1)^2 = (10^k-2) \cdot 10^k + 1 = \underbrace{99 \dots 98}_{k} \underbrace{00 \dots 01}_{k};$$

⟦folio 50⟧

số $9k+1$ ($k \neq 0$) - tổng các chữ số của bình phương số $10^k-2$:
$$(10^k-2)^2 = (10^k-4) \cdot 10^k + 4 = \underbrace{99 \ldots 96}_{k} \underbrace{00 \ldots 04}_{k}$$

(trường hợp $k=0$ rất xác định: $1=1^2$); số $9k+4$ ($k \neq 0$) - tổng các chữ số của bình phương số $10^k-3$:
$$(10^k-3)^2 = (10^k-6) \cdot 10^k + 9 = \underbrace{99 \ldots 94}_{k} \underbrace{00 \ldots 09}_{k}$$

(với $k=0$ chúng ta nhận được số 4 và $4=2^2$). Số $9k+7$ là tổng các chữ số của bình phương của số $10^k+1-5$:
$$(10^k+1-5)^2 = (10^k+1-10) \cdot 10^k+1 + 25 = \underbrace{99 \ldots 90}_{k+1} \underbrace{00 \ldots 025}_{k+1}$$

Như vậy, số 1978 có thể là tổng các chữ số của bình phương nhưng số 1977 thì không.

L. Limanov

M433. Ở gót chân lồi
cạnh ABCDE
BC song song với đường chéo
Cạnh AD, CD - đường chéo
BE, cạnh DE - đường chéo
Phía AC và AE -
đường chéo BD (Hình 2). Chứng minh rằng cạnh AB song song với đường chéo CE.

Cơm. 2.

Đặt $F = [AD] \cap [BE]$, $G = [AC] \cap [BE]$ và $K = [BD] \cap [AC]$ (xem Hình 2).

Từ sự giống nhau của các tam giác $AEF$ và $BCD$ suy ra rằng
$$\frac{|AF|}{|EF|} = \frac{|BC|}{|CD|}.$$ Do đó, $$\frac{|AF| + |BC|}{|EF| + |CD|} = \frac{|BC|}{|CD|}$$

và $$\frac{|AD|}{|BE|} = \frac{|BC|}{|CD|},$$ kể từ $|BC| = |DF|$, $|BF| =$
$= |CD|$, tức là
$$\frac{|BC|}{|AD|} = \frac{|CD|}{|BE|}.$$ (1)

Tương tự, từ sự giống nhau của các tam giác $BKC$ và $AED$ ta thu được điều đó
$$\frac{|AE|}{|BD|} = \frac{|DE|}{|AC|}.$$ (2)

Cuối cùng, từ sự giống nhau của tam giác $BKG$ và $AGE$
$$\frac{|BG|}{|BK|} = \frac{|CD|}{|AE|},$$ từ $$\frac{|BE|}{|BD|} = \frac{|CD|}{|AE|},$$

hoặc
$$\frac{|CD|}{|BE|} = \frac{|AE|}{|BD|}.$$ (3)

Từ thư từ (1) - (3) suy ra rằng
$$\frac{|BC|}{|AD|} = \frac{|CD|}{|BE|} = \frac{|AE|}{|BD|} = \lambda.$$ (4)

Kế tiếp:
$$\vec{BC} + \vec{CD} + \vec{DE} + \vec{EA} + \vec{AB} = \vec{0},$$
$$\vec{AD} + \vec{BE} + \vec{DB} + \vec{CA} + \vec{EC} = \vec{0},$$

và $$\vec{BC} = \lambda \vec{AD}, \vec{CD} = \lambda \vec{BE}, \vec{DE} = \lambda \vec{CA}, \vec{EA} = \lambda \vec{DB}.$$

Posetom
$$\vec{0} = \lambda (\vec{AD} + \vec{BE} + \vec{CA} + \vec{DB}) + \vec{AB} = -\lambda \vec{EC} + \vec{AB},$$

từ đó $$\vec{AB} = \lambda \vec{EC},$$ có nghĩa là sự song song của cạnh $AB$ của đường chéo $EC$.

lời giải ngắn hơn thu được bằng cách sử dụng hệ tọa độ góc. Đặt các điểm $D, C$ và $E$ có ​​tọa độ $D(0; 0), C(1; 0), E(0; 1)$ (Hình 2). Khi đó $A$ và $B$ có tọa độ $(1; a)$ và $(b; 1)$, vì $(CD) \parallel (BE), (DE) \parallel (AC).$

⟦folio 51⟧

Các điều kiện song song $(AE) \parallel (BD)$ và $(BC) \parallel (AD)$ được viết như sau:

$$\frac{a-1}{1-0} = \frac{1-0}{b-0} \quad \text{и} \quad \frac{1-0}{b-1} = \frac{a-0}{1-0},$$

tức là $b(a-1)=1$, $a(b-1)=1$, từ đó $a=b$ và $\frac{a-1}{1-b} = \frac{1-0}{0-1}$, tức là $(AB) \parallel (EC)$.

Lưu ý rằng khuôn tô $ABCDE$, được thảo luận trong bài toán này, có thể được biến thành khuôn mẫu thông thường bằng phép biến đổi affine (hoặc đơn giản là độ lệch).

I. Klumova, E. Turkevich

F442. Các quả bóng có khối lượng 1, 2, 3 và 4 ke được nối với nhau bằng các thanh nhẹ, mỗi thanh dài 1 m. Các thanh được buộc chặt sao cho tạo thành hình chữ thập (Hình 3). Hệ có thể quay tự do trong trục xung quanh đi qua điểm O vuông góc với mặt phẳng hình vẽ. Tìm biên độ dao động của hệ nếu tại thời điểm ban đầu thanh nối các quả bóng với các khối lượng $m_2=2$ke và $m_4=4$ke thẳng đứng và các quả bóng đứng yên.

Cơm. 3.

F443. Như bạn đã biết, quả địa cầu thực hiện một vòng quay hoàn toàn quanh trục của nó trong 23 giờ 56 phút 4 giây. Vì vậy, vào ban ngày, tất cả những chiếc đồng hồ có mặt số được chia thành 24 giờ đều phải hoạt động được gần 4 phút. Con số này gần như là một vòng quay hoàn chỉnh quanh trục của nó trong 23 giờ 56 phút 4 giây. Do đó, trên mỗi trái đất, người ta vẫn quan sát thấy rằng các ngôi sao trên bầu trời trong thời gian $T$ thực hiện một vòng hoàn chỉnh quanh trục của chúng trong 23 giờ 56 phút 4 giây, Mặt trời “quay quanh” Trái đất trong 24 giờ (và chính xác là 24 giờ, liên quan đến điều này, mặt số của tất cả các đồng hồ trên trái đất được chia ra).

Điều này xảy ra bởi vì trong một vòng quay hoàn toàn quanh trục của nó, Trái đất trong chuyển động quỹ đạo quanh Mặt trời cố gắng tiến lên khoảng 1/365 một giờ chiều dài quỹ đạo (Hình 5). Ví dụ, mặc dù quả địa cầu thực hiện một vòng quay hoàn toàn quanh trục của nó, do đó, người quan sát trên trái đất nhìn thấy Mặt trời, nói một cách đại khái, ở cùng một vị trí (và ghi chú, ví dụ, thời điểm bắt đầu buổi trưa trên đồng hồ của anh ta), quả địa cầu cũng phải quay thêm 1/365 của một giờ, mất gần 4 phút.

B. Bukhovtsev
