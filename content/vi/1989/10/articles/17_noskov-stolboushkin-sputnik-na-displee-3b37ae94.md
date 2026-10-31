---
id: 1989-10-noskov-stolboushkin-sputnik-na-displee-3b37ae94
issue: kvant_1989_10
year: 1989
number: "10"
title: Vệ tinh được trưng bày
authors:
  - Носков Н. Н.
  - Столбоушкин С. К.
rubric: raznoe
rubric_sub: Разное
page_first: 62
page_last: 66
page_labels: 60-64
tag: 5ZN9
lang: vi
source: kvant_digital
extraction: vision
content_sha256: abe33e215c9de6e5fe562ef4affe61f1aeb371893f271149cb61ebb2503feebc
prompt_sha256: draft-1
translated_from: content/ru/1989/10/articles/17_noskov-stolboushkin-sputnik-na-displee-3b37ae94.md
source_content_sha256: f8980b900901d96ef33eb426d8696f5a4d7baa18f064a9f79c7b2fd2f196e457
translation_model: draft
translation_run: vi-draft-2026-10-31
translation_quality: draft
---

⟦folio 60⟧

Vệ tinh được trưng bày

N. N. NOSKOV, S. K. STOLBOUSHKIN

Trước Newton, chuyển động của nhiều vật thể khác nhau, chẳng hạn như các hành tinh, dường như là một bí ẩn đối với các nhà khoa học, nhưng sau phát hiện của Newton, mọi thứ đột nhiên trở nên rõ ràng.

R. Feynman

Tất cả chúng ta đều từng xây dựng mô hình tàu thuyền hoặc mô hình nhà cửa và thành phố. Bạn có muốn tạo ra một mô hình hoạt động của Vũ trụ hay ít nhất là Hệ Mặt trời không? Hoàn toàn có thể xây dựng một mô hình như vậy và máy tính là một công cụ rất thuận tiện để tạo ra nó.

Chúng ta sẽ bắt đầu với một điều đơn giản - với mô hình chuyển động của vệ tinh Trái đất. Đầu tiên, chúng ta sẽ giải quyết công thức lý thuyết của bài toán, tức là chúng ta sẽ thiết lập các định luật vật lý xác định chuyển động của vệ tinh và sau đó chúng ta sẽ biên soạn một thuật toán để chúng ta có thể viết một chương trình máy tính.

1. Sản xuất bài toán

Sự đơn giản hóa là điều không thể tránh khỏi khi lập mô hình. Do đó, để bắt đầu, chúng ta sẽ giả định rằng chỉ có hai vật thể trong không gian: Trái đất và vệ tinh. Để xây dựng mô hình tương tác của chúng, bạn cần biết các định luật vật lý xác định chuyển động của chúng. Hai định luật này gồm có: định luật thứ hai của Newton và định luật vạn vật hấp dẫn, do ông phát hiện ra. Ngoài ra, bạn cần thiết lập dữ liệu ban đầu. Hãy bắt đầu với điều này.

Lực duy nhất tác dụng lên vệ tinh là lực hấp dẫn của Trái đất. Nó có thể được tính bằng công thức của định luật vạn vật hấp dẫn

$$F = G \frac{M_1 m_c}{R},$$

trong đó $G$ là hằng số hấp dẫn, nó bằng $6,67 \cdot 10^{-11} \text{ m}^3 / (\text{кг} \cdot \text{с}^2)$;

$M_3$ là khối lượng của Trái đất, bằng $5,98 \times 10^{24} \text{ кг}$;

$m_c$ là khối lượng của vệ tinh.

Theo định luật thứ hai của Newton, gia tốc $\vec{a}$ của vệ tinh bằng: $\vec{a} = \vec{F} / m_c$. Hơn nữa, biết tọa độ $\vec{S} \vec{\theta} = (x\theta; y\theta)$ và tốc độ $\vec{v} \vec{\theta}$ của vệ tinh tại một thời điểm nào đó và ma trận động học được áp dụng

$$\vec{v} = v\theta + \vec{a} \Delta t, \quad \vec{S} = S\theta + \vec{v} \Delta t,$$

(1)

Kazalova, có thể xác định được tốc độ và vị trí của vệ tinh qua thời gian $\Delta t$. Nhưng điều đó không đúng! Lực tác dụng lên vệ tinh và tốc độ $\vec{v}$ sẽ thay đổi theo thời gian $\Delta t$. Phải làm gì?

Có một lối thoát. Giả sử rằng khoảng thời gian $\Delta t$, qua đó cần tính toán vị trí và tốc độ của vệ tinh, là nhỏ. Khi đó trong thời gian này, khoảng cách từ vệ tinh đến Trái đất sẽ thay đổi một chút và bằng cách thay đổi lực $\vec{F}$ và tốc độ $\vec{v}$ thì sẽ có thể chạy trong khoảng thời gian này. Bạn chỉ cần chọn các giá trị $\Delta t$ một cách khôn ngoan. Kết quả tính toán sẽ là những giá trị mới về tọa độ và tốc độ của vệ tinh. Đối với họ, bạn có thể lặp lại các phép tính tương tự với cùng $\Delta t$ và nhận được các giá trị tọa độ và tốc độ tiếp theo. Áp dụng nhất quán sơ đồ tính toán này, chúng ta sẽ thu được tọa độ của vệ tinh tại các thời điểm liên tiếp $T1, T2, T3, ...$ và bằng cách nối các điểm này với các đoạn thẳng, chúng ta sẽ thu được một đường đứt nét gần đúng

⟦folio 61⟧

nhưng đại diện cho quỹ đạo của vệ tinh (hình 1). Những đường đứt đoạn như vậy được gọi là đường đứt đoạn Euler, và bản thân phương pháp tính toán cũng mang tên Leonhard Euler, nhà khoa học vĩ đại người Nga của thế kỷ 18.

Phương pháp Euler không chỉ được sử dụng để tìm quỹ đạo của các thiên thể. Nó được sử dụng cho lời giải một loại phương trình rộng được gọi là phương trình vi phân. Phương trình ban đầu của chúng ta (định luật thứ hai của Newton) cũng là vi phân. Hơn nữa, phương pháp Euler còn được sử dụng cho các phương trình lời giải không thể giải được bằng các phương pháp chính xác.

Bây giờ, khi biết phương pháp Euler, chúng ta có thể vẽ ra một sơ đồ chi tiết để tính toán quỹ đạo của một vệ tinh trong quỹ đạo Trái đất thấp.

Do quỹ đạo của vệ tinh nằm trong cùng mặt phẳng với tâm Trái đất nên chúng ta sẽ thiết lập hệ tọa độ sao cho mặt phẳng quỹ đạo trùng với mặt phẳng $xy$. Trong trường hợp này, tọa độ $z$ luôn bằng 0 và có thể bỏ qua. Hãy đặt gốc của hệ tọa độ ở tâm Trái đất (xem hình 2). Đặt khoảng cách từ tâm Trái đất đến vệ tinh là $R$ và tốc độ của nó so với Trái đất là $\vec{v}$. Để xác định rõ ràng vị trí của vệ tinh, chỉ giá trị $R$ là không đủ. Cần phải thêm góc $\alpha$ vào $R$, tại đó vệ tinh có thể nhìn thấy được từ gốc hoặc cùng với các cặp $R$, $\alpha$, chỉ định một cặp tọa độ $x, y$.

Nếu khoảng cách $R$ và góc $\alpha$ đã biết thì tọa độ $x, y$ có ​​thể được xác định bằng cách sử dụng các công thức $x=R \cos \alpha, y=R \sin \alpha$.

Tốc độ của vệ tinh và lực căng của Trái đất là các đại lượng vectơ; chúng ta hãy phân tách chúng thành các thành phần dọc theo trục $x, y$. Từ sự giống nhau của các tam giác tương ứng trên hình 2, rõ ràng là

$$\frac{F_x}{F} = -\frac{x}{R}, \quad \frac{F_y}{F} = -\frac{y}{R},$$

từ đây

$$F_x = -|F|x/R, \quad F_y = -|F|y/R.$$

Nếu chỉ có lực căng của Trái Đất tác dụng lên vệ tinh thì định luật II Newton có thể viết dưới dạng

$$m_c a_x = -G \frac{M_3 \cdot m_c}{R^2} \frac{x}{R}, \quad m_c a_y = -G \frac{M_3 \cdot m_c}{R^2} \frac{y}{R}.$$

Giảm $m_c$ và thay giá trị gia tốc vào các công thức động học (1), ta thu được công thức tính giá trị mới của các thành phần tọa độ và vận tốc theo thời gian $\Delta t$:

$$x^\mathrm{H} = x + v_x \Delta t, \quad y^\mathrm{H} = y + v_y \Delta t, \quad v_x^\mathrm{H} = v_x - G \cdot M_3 x \Delta t/R^3, \quad v_y^\mathrm{H} = v_y - G \cdot M_3 y \Delta t/R^3.$$

Công thức (2) biểu thị sơ đồ thuật toán được tạo sẵn cho máy tính. Chúng tôi sẽ trình bày việc thực hiện thuật toán này. Nhưng trước tiên, hãy tìm cách đặt bước $\Delta t$. Có những phương pháp tính bước đặc biệt để sau một thời gian dài sai số tính tọa độ không vượt quá giá trị định trước. Chúng tôi sẽ làm điều đó đơn giản hơn - chúng tôi sẽ chọn giá trị bước bằng phương pháp thử nghiệm. Để thực hiện việc này, bạn cần chọn $\Delta t$ tùy ý và tìm lời giải cho giá trị này. Sau đó giảm một nửa bước và tìm lại quỹ đạo. Nếu lời giải đối với $\Delta t$ mới không thể phân biệt được với cái trước đó thì chúng ta sẽ cho rằng việc lựa chọn bước là thỏa đáng.

Bây giờ bạn có thể bắt đầu triển khai mô hình trên máy tính.

2. Lập trình

Chúng tôi có một thuật toán tính toán quỹ đạo của vệ tinh, tức là một bộ công thức (2) cho phép xác định vị trí và tốc độ của vệ tinh bất cứ lúc nào. Nhưng nếu bạn áp dụng

⟦folio 62⟧

các công thức này đều thuộc SI thì mọi đại lượng sẽ có giá trị lớn hơn tương ứng với thang vũ trụ. Do đó, sẽ thuận lợi hơn nếu bạn tạo hệ thống đơn vị của riêng mình trong đó tích $GM_3$ bằng một. Điều này sẽ giải quyết được nếu chúng ta lấy bán kính Trái đất làm đơn vị chiều dài và vận tốc vũ trụ đầu tiên $v_{1k} = \sqrt{GM_3/R_3}$ làm đơn vị tốc độ. Trong trường hợp này, thời gian sẽ thay đổi theo đơn vị $R_3/v_{1k}$. Mối quan hệ giữa các đơn vị của hệ đo lường mới và SI của Trái đất sẽ như sau: đơn vị chiều dài - $6,38 \cdot 10^6$ m, tốc độ - $7,8 \cdot 10^3$ m/s, thời gian - $0,82 \cdot 10^3$ s và công thức (2) có dạng
$$x^H = x + v_x \Delta t,$$
$$y^H = y + v_y \Delta t,$$
$$v_x^H = v_x - x \Delta t/R^3,$$
$$v_y^H = v_y - y \Delta t/R^3.$$
Các công thức đã trở nên phù hợp hơn để tính toán và quan trọng nhất là phổ quát. Chúng “làm việc” không chỉ cho Trái đất mà còn cho bất kỳ thiên thể vũ trụ nào, một cách tự nhiên, trong một hệ đơn vị trong đó đơn vị chiều dài là bán kính của vật thể này, và đơn vị tốc độ là vận tốc thoát đầu tiên của vật thể này.

Điều cuối cùng chúng ta cần làm trước khi viết chương trình là hiểu màn hình đồ họa là gì và cách đặt mô hình của chúng ta lên đó. Màn hình ở chế độ đồ họa có độ phân giải cao là một trường hình chữ nhật gồm các chấm có kích thước $m \times n$. Trục $x$ trên đó luôn nằm từ trái sang phải và trục $y$ có ​​thể nằm từ trên xuống dưới hoặc từ dưới lên trên. Giả sử rằng trục $y$ đi lên và $m=n=256$. Để hiển thị một điểm trên màn hình, bạn cần chỉ định tọa độ và màu sắc của nó. Để vẽ một đường thẳng, bạn phải xác định tọa độ của điểm bắt đầu và điểm kết thúc. Để mô tả một vòng tròn, bạn phải xác định tọa độ của tâm và bán kính. Chúng ta sẽ biểu thị các toán tử cho những hành động này như sau:
dấu chấm(X,Y), màu sắc;
dòng (X1, Y1) - (X2, Y2), màu sắc;
hình tròn (X, Y), R, màu sắc.

Tuy nhiên, bạn không thể đơn giản lấy tọa độ vật lý làm tọa độ màn hình. Như bạn còn nhớ, chúng ta đã lấy bán kính Trái đất làm một và đặt gốc tọa độ ở tâm Trái đất. Bây giờ chúng ta cần đặt tâm Trái đất vào giữa màn hình (một điểm có tọa độ ($X_\pi$, $Y_\pi$), ví dụ (128, 128)) và thông báo mọi thứ $k$ lần. Ta thu được các công thức sau: nếu tọa độ vật lý của điểm (vệ tinh) là $x, y$ thì tọa độ trên màn hình

$$XD = X_\pi + k*x, \quad YD = Y_\pi + k*y.$$

Chúng tôi sẽ xác định giá trị của $k$ sau.

Bây giờ bạn có thể chuyển trực tiếp sang việc soạn thảo chương trình. Đầu tiên, chúng ta sẽ xây dựng một sơ đồ chung, sau đó chúng ta sẽ trình bày chi tiết. Trong nhóm gần đúng, chương trình chuyển động của vệ tinh Trái đất có thể được viết dưới dạng sau:

bắt đầu
đầu vào dữ liệu ban đầu;
chuẩn bị hiển thị đồ họa;
vẽ Trái đất và vệ tinh;
lặp lại
tính toán các giá trị tọa độ mới;
vẽ đoạn quỹ đạo và vệ tinh ở vị trí mới;

kết thúc lặp lại kết thúc.

Hai hướng dẫn đầu tiên không gây ra vấn đề gì. Để vệ tinh tại thời điểm ban đầu TF nằm trên trục $x$ thì tọa độ ban đầu $y$ phải được đặt bằng 0 và khoảng cách $x$ phải giữ nguyên theo đơn vị của hệ tọa độ vật lý, tức là tính bằng đơn vị bán kính trái đất.

Tốc độ ban đầu cũng đơn giản dưới dạng cặp số VX, VY. Tuy nhiên, hóa ra sẽ thuận tiện hơn khi nhập giá trị của mô hình vận tốc và hướng của nó (góc với trục $x$), sau đó chuyển nó thành các thành phần của hệ tọa độ trực tiếp bằng cách sử dụng các công thức

$$VX = V*\cos (y\theta*\pi/180),$$
$$VY = V*\sin (y\theta*\pi/180).$$

Cần có biểu thức trong ngoặc đơn để chuyển đổi góc từ độ sang radian,

⟦folio 63⟧

bởi vì trong tất cả các ngôn ngữ, hàm lượng giác chỉ được tính bằng radian.

Việc chuẩn bị một màn hình đồ họa không khó, chỉ cần thực hiện đúng theo hướng dẫn dành cho máy tính. Bạn có thể vẽ khung viền cho thẩm mỹ. Nếu màn hình đồ họa cũng cho phép xuất văn bản thì tên bài toán có thể được viết ở đầu hoặc cuối màn hình. Những bổ sung này là không cần thiết, nhưng với chúng, hình ảnh trông đẹp hơn nhiều. Bạn có thể thể hiện trí tưởng tượng của mình và thêm một số phụ kiện khác đang chờ vào bức tranh.

Bây giờ hãy mô tả Trái đất và vệ tinh. Để vẽ, bạn cần xác định hệ số tỷ lệ $k$. Chúng tôi đề xuất thiết lập nó bằng công thức $k=100/x$. Sau đó hình ảnh Trái đất và vệ tinh (có màn hình tọa độ XD, YD) được người vận hành hiện thực hóa

hình tròn (X$_\pi$, Y$_\pi$), $k$, màu xanh lam;
XD←X$_\pi$+$k^*x$; YD←Y$_\pi$;

chấm (XD, YD), màu đỏ.

Trong trường hợp này, việc mở rộng quy mô được thực hiện tự động. Nếu bạn quyết định phóng một vệ tinh từ bề mặt Trái đất, tức là $x=1$, thì hình ảnh của Trái đất sẽ chiếm gần như toàn bộ màn hình, bán kính của nó sẽ là một trăm đơn vị màn hình. Nếu vệ tinh được đặt ở khoảng cách $x=10$ thì Trái đất sẽ chiếm một hình tròn có bán kính 10 điểm.

Việc còn lại là xác định bước thời gian T$\theta=\Delta t$. Người ta đã xác định bằng thực nghiệm rằng giá trị trong khoảng 0,1–0,2 hoạt động tốt.

Mọi hành động chuẩn bị đều hợp pháp, chúng ta hãy bắt đầu mô hình hóa chuyến bay vệ tinh dựa trên công thức (3).

Lặp lại
XS←XD; YS←YD;
X←X+VX*T$\theta$;
Y←Y+VY*T$\theta$;
XD←X$_\pi$+$k^*X$;
YD←Y$_\pi$+$k^*Y$;

Dòng (XS, YS) - (XD, YD), màu xanh lam;
Chấm (XD, YD), màu đỏ;

$R\leftarrow\sqrt{X^2+Y^2}$;
VX←VX-X*T$\theta/R^3$;
VY←VY-Y*T$\theta/R^3$;

Kết thúc lặp lại.

Như bạn có thể đã đồng ý, XS và YS là màn hình tọa độ vệ tinh cũ. Hơn nữa, chúng tôi không chỉ vạch ra một ranh giới hay chấm dứt nó, mà chúng tôi còn làm cả hai việc. Kết quả là một chấm đỏ sẽ di chuyển trên màn hình, để lại một vệt màu xanh phía sau. Khi vẽ một đường, bạn chỉ có thể xác định tọa độ của điểm cuối nếu máy tính ghi nhớ điểm bắt đầu.

Chương trình thực tế là hữu hạn; vẫn còn phải quyết định cách lặp lại chu kỳ. Bạn có thể đặt trước số lần lặp lại, nhưng có thể chúng ta sẽ cảm thấy mệt mỏi khi làm việc với mô hình trước khi chu kỳ kết thúc hoặc ngược lại, chu trình kết thúc vào thời điểm thú vị nhất. Vì vậy, sẽ thuận tiện hơn nếu lặp lại chu kỳ theo mong muốn của chúng ta. Ví dụ: hãy nhấn một phím nào đó. Và phải thêm một điều kiện nữa để kết thúc vòng lặp. Vấn đề là nếu R<1 thì không có gì ngăn cản chương trình tiếp tục chạy. Và điều này có nghĩa là vệ tinh thời gian đi vào Trái đất và tiếp tục di chuyển theo độ sâu của nó. Do đó, chúng tôi duy trì cái gọi là biến Boolean UPAL, chỉ nhận hai giá trị: đúng và sai. Và chúng ta sẽ tính toán nó như thế này: FALLED←(R<1). Điều kiện được lặp lại trong trường hợp này:

LẶP LẠI CHO ĐẾN KHI (BỊ BỎ) VÀ (KEY ≠“S”)

Chu kỳ sẽ tiếp tục cho đến khi ít nhất một trong các điều kiện bị vi phạm.

Chúng tôi đã viết một chương trình bằng một ngôn ngữ giả định. Nó có thể dễ dàng dịch sang ngôn ngữ của bất kỳ máy tính nào.

Bây giờ hãy nói về những gì bạn có thể tự thay đổi và thêm vào chương trình. Phần đầu tiên của những thay đổi liên quan đến thiết kế tự nhiên. Nếu vệ tinh rơi xuống, thì bạn có thể mô tả một vụ nổ tại điểm va chạm. Và bản thân vệ tinh có thể được vẽ không phải dưới dạng một điểm mà ở dạng hình (đối với những người có kỹ năng về nghệ thuật vẽ hình, điều này

⟦folio 64⟧

sẽ không khó). Bạn có thể hiển thị tốc độ hiện tại và khoảng cách tới Trái đất sau 10 hoặc 20 chu kỳ. Đây là điều đầu tiên bạn nghĩ đến. Chúng tôi hy vọng bạn nghĩ ra điều gì đó khác.

Ngoài các tính năng nghệ thuật bổ sung, bạn có thể tự thay đổi mô hình. Trong trường hợp này, thậm chí còn có nhiều chỗ hơn cho trí tưởng tượng. Nếu trong các công thức của VX và VY chúng ta thay điểm trừ bằng điểm cộng thì định luật vạn vật hấp dẫn sẽ chuyển thành định luật lực đẩy phổ quát. Như vậy, mô hình vệ tinh sẽ biến thành mô hình tương tác của các hạt tích điện một chiều. Hoặc bạn có thể đóng góp cho một Vũ trụ không tồn tại. Lực trong định luật hấp dẫn tỉ lệ nghịch với bình phương khoảng cách. Điều gì xảy ra nếu nó tỷ lệ nghịch với lập phương hoặc lũy thừa bậc nhất của khoảng cách? Chúng tôi cũng không khó để tạo điều kiện thuận lợi cho tình huống này - chỉ cần thay thế $R^3$ trong các công thức bằng $R^4$ hoặc $R^2$ là đủ.

Nhưng sự thay đổi tiếp theo sẽ đòi hỏi nhiều công việc hơn. Chúng ta đã tạo ra mô hình vệ tinh của Trái đất nhưng không thể điều khiển được nó. Ngoài ra, còn có những vật thể khác trong không gian có thể bay lên được. Sẽ rất thú vị khi đưa “Poprygunchik” lên “Soyuz” từ “Phobos” trên Phobos. Chúng tôi sẽ giải quyết vấn đề này trong một trong những số tiếp theo của tạp chí.

Danh sách độc giả:
những người đã gửi đúng lời giải
(Để bắt đầu, xem trang 38)

48, 55, 58, 59; P. Molodov (Lomonosov) 55; S. Murin (Wrest) 59; V. Mytko (Leningrad) 48, 52, 55, 59, 60; A. Nasibov (Quận Sheki của Cộng hòa xã hội chủ nghĩa Xô viết tự trị) 52; A. Nasirov (Quận Sheki của Cộng hòa xã hội chủ nghĩa Xô viết tự trị) 52; N. Nemirovskaya (Kyiv) 48, 52, 58; A. Nikolaev (Kyiv) 48, 49; I. Novikov (Kalinerrad) 58; R. Novoselov (Moscow) 55, 58, 59, 61; D. Ometsinsky (Kyiv) 48, 49, 51, 58-61; V. Onishchuk (Minsk) 58, 59; G. Orener (Kyiv) 58; A. Orlovsky (Kyiv) 48, 49, 51, 58-61; D. Ostrovsky (Dnepropetrovsk) 60; A. Pavlotsuk (Kyiv) 49, 52, 58; Y. Paiko (Wrest) 58; P. Penzin (Kuibyshev) 58-60; M. Perepechko (Moscow) 55; S. Petukhov (Gorky) 52; I. Pilosin (Alma-Ata) 52, 58; N. Plakhtiy (Kyiv) 58; T. Podalyako (Leningrad) 58, 61; S. Podryatov (Kyiv) 49, 52; E. Pomarsky (Tashkent) 49, 52; V. Polushuk (Kanev) 51, 61; S. Polyshin (Kharkov) 52, 58-61; S. Ponomarenko (Novosibirsk) 49; S. Pogorochin (Izhevsk) 52, 55, 58, 60; E. Giải thưởng (Odessa) 51, 55, 58, 59, 61; E. Proskurina (Kyiv) 58; V. Puzanov (Donetsk) 51; I. Ptaikin (Moscow) 55; A. Revsky (Moscow) 61; A. Raspereza (Wrest) 48, 49, 52, 55, 58, 61; I. Rassadin (Minsk) 52; R. Rolinsky (Kyiv) 52; A. Ruevsky (Ivano-Frankivsk) 52; R. Ruzev (huyện Khankinsky, vùng Khorezm) 52; I. Ryabova (Kharkov) 52, 59; A. Savin (Gorlovka) 58, 59, 61; A. Savchenko (làng Moshny

vùng Cherkasy) 58, 59, 61; N. Samoilova (Kyiv) 58; A. Samuenko (Semipalatinsk) 48, 49, 55; S. Sevchenko (Minsk) 52; A. Skabelin (Baranovich) 48, 51, 55, 58-60; T. Skripnik (Kyiv) 48; V. Soldatov (khu định cư Krasnorechensky, vùng Primorsky) 55, 59; Yu. Người phát ngôn (Kyiv) 48, 51, 52, 58, 59, 61; Yu. Starostin (Yakutsk) 55; M. Subbotin (Stayy Oskol) 49; A. Suvkhanov (Chardzhou) 59; N. Suleymanov (quận Sheki của Cộng hòa xã hội chủ nghĩa Xô viết tự trị) 52; I. Sysovev (Semipalatinsk) 55, 59, 61; S. Tabaltsev (Moscow) 58; V. Tamoshina (Vilnius) 48, 49, 51, 52, 59; A. Tenekedzhi (Voronezh) 58, 59; S. Timashov (Alma-Ata) 48, 49, 55; M. Titov (Kyiv) 48, 55, 58-60; S. Tikhonov (Voronezh) 48, 51; R. Todorov (Varna, NRV) 52; A. Tutov (Riga) 51; D. Ukrainsky (Moscow) 58; A. Usinsky (làng Ptichya, vùng Rivne) 48, 49, 52, 60, 61; Yu. Fenok (Kyiv) 58; L. Frenklakh (Voronezh) 58, 60; A. Fridlyand (Saratov) 48, 49, 55; G. Khachatran (quận Artashat của Cộng hòa xã hội chủ nghĩa Xô viết Armenia) 48; R. Christok (Kyiv) 48, 51; E. Chashechkina (làng Chernogolovka, vùng Moscow) 48, 49, 52, 55, 58-60; I. Chemolosov (Moscow) 60, 61; L. Chernysheev (Moscow) 49, 59, 61; D. Chokin (Alma-Ata) 48, 49, 52, 55, 58, 61; V. Chuev (Stayy Oskol) 52; E. Shaarov (Grozny) 48, 59; A. Shazinyan (Rostov) 59; T. Sharafutdino (Ust-Kamenogorsk) 48, 49; E. Shvets (Chernivtsi) 49, 52, 60; S. Shinkevich (Verezniki) 48, 49, 51, 52, 58-60; S. Shubsky (Phần còn lại) 48; I. Shulyak (Kyiv) 52, 55, 58-60; K. Shurunov (Kuibyshev) 58, 59; N. Sherbina (Artemovsk) 52; M. Entit (Tula) 48, 49, 51, 52, 55, 58-61; V. Yurasov (Volgodonsk) 55; I. Yaholtser (Chernivtsi) 52, 55, 58, 59.
