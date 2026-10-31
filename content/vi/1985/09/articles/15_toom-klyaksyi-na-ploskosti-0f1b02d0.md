---
id: 1985-9-toom-klyaksyi-na-ploskosti-0f1b02d0
issue: kvant_1985_9
year: 1985
number: "9"
title: Vết bẩn trên máy bay
authors:
  - Тоом А. Л.
rubric: zadachnik-kvanta
rubric_sub: Задачник «Кванта»
page_first: 49
page_last: 50
page_labels: 47-48
tag: C0NQ
lang: vi
source: kvant_digital
extraction: vision
content_sha256: 31b27c26aef728bede02c64e2eeea164b1914849ca3c3d33866a95ba17c778a4
prompt_sha256: draft-1
translated_from: content/ru/1985/09/articles/15_toom-klyaksyi-na-ploskosti-0f1b02d0.md
source_content_sha256: 96275b3abbc8284bb83d3546b85948351d1c8520894edc3c28f528678e672575
translation_model: draft
translation_run: vi-draft-2026-10-31
translation_quality: draft
---

⟦folio 47⟧

F937. Một người có “chiều cao” $h=20$ cm hướng vào một bức tường thẳng đứng, đầu người ở độ cao $H=2$ m so với sàn nhà. Sử dụng một đường thẳng có tiêu cự $F=0,1$ m sẽ thu được ảnh của một người trên sàn. Những kích thước này cung cấp hình ảnh rõ ràng nhất.

Hình ảnh trên sàn có thể thu được ở các vị trí khác nhau của thấu kính và độ phóng đại sẽ phụ thuộc vào vị trí của thấu kính. Hình ảnh rõ nét nhất sẽ có trong trường hợp “tâm” của nguồn (điểm $A$ trên hình) và điểm hình ảnh tương ứng (điểm $A'$) nằm trên trục quang chính của ống kính. Dễ dàng chứng minh rằng mặt phẳng chứa thấu kính đi qua đỉnh $O$ của góc vuông $AOA'$ (xem hình).

Hãy viết công thức thấu kính:

$$\frac{1}{F} = \frac{1}{d} + \frac{1}{f} = \frac{1}{|AO'|} + \frac{1}{|O_1A'|}.$$

Giả sử rằng $|OA| = H - h/2 = H_1$, chúng ta nhận được $|AO'| = H_1 \cos \alpha$, $|O'A'| = |OA'| \sin \alpha = H_1 \text{tg} \alpha \cdot \sin \alpha$ và

$$\frac{1}{H_1 \cos \alpha} + \frac{1}{H_1 \text{tg} \alpha \cdot \sin \alpha} = \frac{1}{F},$$

Ở đâu

$$\sin^2 \alpha \cdot \cos \alpha = \frac{F}{H_1} = \frac{F}{H - h/2}.$$

Từ phương trình này chúng ta có thể tìm được góc $\alpha$. Có thể giả định gần đúng (góc $\alpha$ nhỏ) là $\cos \alpha \approx 1$; Sau đó

$$\sin \alpha \approx \sqrt{\frac{F}{H - h/2}} \approx 0,233 \text{ и } \alpha \approx 0,231.$$

Bây giờ hãy tính kích thước hình ảnh. Nếu nguồn và ảnh nằm trong mặt phẳng vuông góc với trục chính của thấu kính thì độ phóng đại sẽ bằng

$$\Gamma = \frac{|O'A'|}{|AO'|} = \frac{H_1 \text{tg} \alpha \cdot \sin \alpha}{H_1 \cos \alpha} = \text{tg}^2 \alpha.$$

Trong trường hợp của chúng tôi, độ phóng đại bằng tỷ lệ độ dài của hình chiếu của hình ảnh và nguồn lên các mặt phẳng này; Điều này có nghĩa là kích thước hình ảnh là

$$h' = h \Gamma \text{tg} \alpha = h \text{tg}^3 \alpha \approx 0,25 \text{ см.}$$

A. R. Zilberman

Vết bẩn trên máy bay

Hãy tưởng tượng một bản đồ địa lý hiển thị khu vực có một loài thực vật hoặc dịch bệnh. Phần bản đồ tương ứng với lãnh thổ này được sơn một màu nhất định, phần còn lại được giữ nguyên màu trắng. Để nghiên cứu sơ đồ vị trí của một loài hoặc dịch bệnh, một chuỗi các bản đồ tương ứng với các thời điểm khác nhau được biên soạn và cố gắng thu được các mô hình thay đổi ở phần bóng mờ. Nếu một đứa trẻ sắp mắc phải một trận dịch, tất nhiên chúng ta muốn nó biến mất. Nếu đứa trẻ nói về một số loài có giá trị, chúng tôi muốn nó được bảo tồn. Trong cả hai trường hợp, điều quan trọng đối với chúng ta là phần được sơn có biến mất hay không. Những thông điệp như vậy dẫn đến những vấn đề tương tự như vấn đề đã được xuất bản trên tạp chí số 5 của chúng tôi trong năm nay trong “Sách vấn đề Quaita” (M925). Chúng tôi sẽ cung cấp cho nó lời giải và một số liên quan khác bài toán.

M925. Trên mặt phẳng màu trắng có một singra $K_0$. Từ đó, thu được một hình singra mới $K_1$ theo quy tắc sau, áp dụng đồng thời ứng dụng cho tất cả các điểm $M$ của mặt phẳng: nếu ít nhất một cực có diện tích hình tròn bán kính 1 với tâm tại điểm $M$ bị chiếm bởi một màu thì các điểm $M$ trở thành màu xanh lam, và nếu ít cực hơn thì màu trắng. Ở bước tiếp theo, từ hình singra thu được $K_1$, theo các quy tắc tương tự, thu được hình $K_2$, sau đó từ nó $K_3$, v.v. Chứng minh rằng: a) đối với một hình giới hạn tùy ý $K_0$, bắt đầu từ một bước nhất định, nếu mặt phẳng trở thành màu trắng; b) nếu $K_0$ là vòng 100, thì điều này sẽ xảy ra không muộn hơn một triệu bước.

Chúng ta hãy biểu thị bằng chữ cái $F$ quy tắc mà mỗi hình tạo ra hình tiếp theo. Nó đơn điệu theo nghĩa sau: từ một hình nhỏ hơn, theo quy tắc $F$, thu được một hình nhỏ hơn; chính thức hơn nó có thể được viết như thế này:

$$K \subset K' \Rightarrow F(K) \subset F(K').$$

Nhờ sự đơn điệu này nên ta coi như những số liệu ban đầu là đủ

⟦folio 48⟧

gur chỉ vòng tròn. Thật vậy, mọi hình giới hạn đều nằm trong một hình tròn nhất định, và ngay cả khi hình tròn này, dưới tác dụng của quy tắc của chúng ta, biến thành một tập rỗng, thì hình chứa nó thậm chí còn hơn thế. Vòng tròn rất tiện lợi vì dưới tác dụng của $F$ chúng biến thành vòng tròn. Chính xác hơn:

a) nếu $K$ là hình tròn có bán kính lớn hơn hoặc bằng $1/\sqrt{2}$ (tức là có diện tích lớn hơn hoặc bằng $\pi/2$) thì $F(K)$ cũng là hình tròn (bán kính nhỏ hơn);

6) nếu $K$ là đường tròn có bán kính nhỏ hơn $1/\sqrt{2}$ thì $F(K)$ là tập trống.

Hãy xem hàm $f(R)$, xác định cho $R$ lớn hơn $1/\sqrt{2}$, như sau: nếu $R$ là bán kính của hình tròn $K$ thì $f(R)$ là bán kính của hình tròn $F(K)$. Đồ thị của hàm $f$ được hiển thị ở hình 1. Khi $R$ tăng từ $1/\sqrt{2}$ lên vô cùng, hàm $f(R)$ tăng đơn điệu từ $1-1/\sqrt{2}$ lên vô cùng, với đồ thị của nó luôn ở dưới bissertrix của góc tọa độ $(R-f(R))>0$. Không khó để chứng minh rằng hiệu $R-f(R)$ là hàm số giảm đơn điệu của $R$ (có xu hướng tiến tới 0 tại $R \rightarrow \infty$). Đường đứt nét ở hình 1 cho biết cách hoạt động của bán kính $R_0$, $R_1=f(R_0)$, $R_2=f(R_1)$, ... (tại hình 1 nó đã là $R_3<1/\sqrt{2}$, vì vậy ở giai đoạn tiếp theo, kết quả sẽ là một tập hợp trống). Trong trường hợp tổng quát, tính đơn điệu của $R-f(R)$ ngụ ý:

$$R_0-R_1<R_1-R_2<R_2-R_3<\dots$$

Do đó, biểu thị $R_0-R_1=d>0$, chúng ta thu được $R_n<R_0-nd$ đó. Điều này có nghĩa là đối với một số giá trị $n$ (không quá $R_0/d+1$), hình $K_n$ sẽ trống. Điều này chứng minh khẳng định a). (Trong chứng minh này, các chi tiết không phải bát phân chỉ được phác thảo, nhưng trong quá trình lời giải bài toán 6 sau đây), chúng ta sẽ thu được một lời giải a. khác).

Để giải quyết điểm 6), cần ước tính bằng số giá trị mà tại đó bán kính $R$ của đường tròn $K$ giảm theo tác động của quy tắc $F$. Nếu bên trong đường tròn $K$ có ít hơn một phần của đường tròn “tiêu chuẩn” $D$ bán kính 1 với tâm ở điểm $M$, thì điểm này không được đưa vào $F(K)$ và do đó, $f(R)<OM$, trong đó $O$ là tâm của đường tròn $K$. Như có thể thấy từ hình 2, đây sẽ là trường hợp, ví dụ: khi chu vi của một hình tròn $K$ cắt đường kính $AA_1$ của một hình tròn $D$ tại các điểm giữa $B$ và $B_1$ của bán kính $MA$ và $MA_1$ trong trường hợp này trường hợp diện tích của đoạn thẳng là $BB_1G$ nhỏ hơn diện tích của các tam giác cong $ABL$ và $A_1B_1L_1$, nên diện tích giao điểm của hình tròn $D$ và $K$ nhỏ hơn một nửa diện tích hình tròn $D$. Hơn nữa, $OM^2=OB^2-MB^2=R^2-1/4$, do đó,

$$f(R)^2<OM^2=R^2-1/4$$

(với mọi $R>1/\sqrt{2}$), tức là $R_n^2<R_n^{n-1}-1/4$.

Từ đây chúng ta kết luận bằng quy nạp rằng với $R_{n-1}>1/\sqrt{2}$

$$R_n^2<R_n^2-n/4$$

Do đó, một đường tròn có bán kính tùy ý $R_0$ sẽ biến mất sau một số hữu hạn bước (chứng minh câu a)) và con số này không lớn hơn $4R_0^2+1$. Đối với $R_0=100$ nó hoàn thành trong chưa đầy một triệu, đó là điều cần được chứng minh trong bài toán 6).

Bài toán 1.

1. Gọi $N(R)$ là số lần áp dụng quy tắc $F$ biến các đường tròn có bán kính $R$ thành tập hợp trống. Chúng tôi đã chứng minh rằng $N \leqslant 4R^2+1$. Mặt khác, chứng minh rằng $N \geqslant cR^2$, trong đó $c$ là hằng số dương không phải tác nhân.

2. Hãy xem xét một quy tắc khác $H$ để biến đổi các hình trên mặt phẳng. Hãy để chúng tôi giới thiệu hệ tọa độ $Oxy$. Nếu cho hình $K$ thì hình mới $H(K)$ bao gồm tất cả các điểm $T(x; y)$ mà giao điểm của $K$ và một tam giác có các đỉnh $(x; y), (x+1; y), (x; y+1)$ có diện tích ít nhất bằng một nửa diện tích của tam giác này. Chứng minh rằng bất kỳ hình giới hạn nào dưới tác dụng lặp lại $H$ đều biến thành một tập hợp rỗng trong hữu hạn bước $N$ và đối với một đường tròn có bán kính $R$

$$c_1 \cdot R \leqslant N \leqslant c_2 \cdot (R+1),$$

trong đó $c_1$ và $c_2$ là các hằng số dương không phải tác nhân.

3. Trên một quả cầu màu trắng có đường kính $d>1$ có hình $K_0$ màu xanh lam. Chúng ta hãy liên kết từng điểm $M$ của hình cầu với “vùng lân cận” của nó $D_M$ - một phần của hình cầu được bao bọc trong một quả bóng có đường kính 1 với tâm $M$ và một hình màu xanh lam mới $K_1$ được hình thành từ những điểm đó và chỉ những điểm $M$ mà diện tích giao điểm $D_M$ và $K_0$ không nhỏ hơn một nửa diện tích của hình cầu khu phố $D_M$. Tương tự, từ $K_1$ ta có $K_2$, v.v.

a) Chứng minh rằng nếu hình ban đầu $K_0$ được chứa trong một quả cầu có đường kính nhỏ hơn $d$ thì sau hữu hạn bước toàn bộ quả cầu sẽ trở thành màu trắng.

6) Chứng minh rằng với mọi $\varepsilon>0$ đều có thể chỉ ra một $d$ và một hình $K_0$ màu xanh có diện tích không lớn hơn $\varepsilon d^2$ trên một quả cầu màu trắng có đường kính $d$ sao cho sau một số hữu hạn các phép biến đổi được mô tả, toàn bộ quả cầu sẽ chuyển sang màu xanh lam.

b) Có hình $K_0$ nào khác ngoài bán cầu mà $K_1$ trùng với $K_0$ không?

A. L. TOOM
