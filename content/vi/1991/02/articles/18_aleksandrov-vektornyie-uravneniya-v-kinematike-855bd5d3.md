---
id: 1991-2-aleksandrov-vektornyie-uravneniya-v-kinematike-855bd5d3
issue: kvant_1991_2
year: 1991
number: "2"
title: Phương trình vectơ trong động học
authors:
  - Александров Д. А.
rubric: praktikum-abiturienta
rubric_sub: Практикум абитуриента
page_first: 61
page_last: 66
page_labels: 59-64
lang: vi
source: kvant_digital
extraction: vision
content_sha256: 082e571f7b29438bab1fac9946f17311a6312d643f3dd8b65cdc3fa9007b3ab0
prompt_sha256: draft-1
translated_from: content/ru/1991/02/articles/18_aleksandrov-vektornyie-uravneniya-v-kinematike-855bd5d3.md
source_content_sha256: 20e77b23eb8165bf5c3691c6daf842ed6ba322bd6fd70121201a6ca5d031f98b
translation_model: draft
translation_run: vi-draft-gaps-2026-11-06
translation_quality: draft
---

⟦folio 59⟧

---
running_head:
folio:
---

Vectơ
phương trình
trong động học

D. ALEXANDROV

Như đã biết, với gia tốc đều
sự phụ thuộc vào tốc độ $\vec{v}$
và chuyển vị $\vec{s}$ của vật theo thời gian được cho bởi các công thức

$$\vec{v} = \vec{v}_0 + \vec{a} t,$$
$$\vec{s} = \vec{v}_0 t + \frac{\vec{a} t^2}{2},$$

trong đó vận tốc ban đầu $\vec{v}_0$ và độ bám rễ của vật thể $\vec{a}$ là các vectơ không phụ thuộc vào thời gian.

Bài tập 1. Từ công thức (1) và (2) thu được các biểu thức sau:

$$\vec{s} = \frac{\vec{v}_0 + \vec{v}}{2} t,$$
$$v^2 - v_0^2 = 2\vec{a} \cdot \vec{s}$$

(trong đó $\vec{a} \cdot \vec{s}$ là tích vô hướng).

Bài tập 2. Đảm bảo rằng từ công thức (2) sau khi vi phân theo thời gian sẽ thu được biểu thức (1).

Trong số tất cả các trường hợp có thể xảy ra của chuyển động có gia tốc đều, có một vị trí đặc biệt là sự rơi tự do của một vật trong trường trọng lực. Lời giải đa số bài toán về chủ đề này, theo quy định, là nhân chứng cho việc áp dụng các công thức (1), (2) và (3). Sử dụng ví dụ này, chúng ta sẽ xem xét các phương pháp cơ bản để làm việc với phương trình vectơ.

Bài toán 1. Một vật được ném từ mặt đất một góc α so với phương ngang thì bị nén lại một khoảng L tính từ điểm ném. Xác định thời gian bay của cơ thể.

Lời giải 1. Chọn trục tọa độ X và Y như trong hình 1 và viết vectơ

⟦folio 60⟧

---
running_head:
folio:
---

phương trình (2) trong các hình chiếu lên các trục này:
$$x = v_0 \cos \alpha \cdot t,$$
$$y = v_0 \sin \alpha \cdot t - \frac{g t^2}{2}.$$
Gọi $\tau$ là thời gian bay cần thiết. Từ điều kiện bài toán suy ra tại $t = \tau$ vật có tọa độ $x = L$ và $y = 0$. Phương trình (4), viết cho thời điểm vật rơi, cho hệ hai phương trình với hai ẩn số
$$L = v_0 \cos \alpha \cdot \tau,$$
$$0 = v_0 \sin \alpha \cdot \tau - \frac{g t^2}{2}.$$
Từ đây loại bỏ $v_0$, ta tìm được
$$\tau = \sqrt{\frac{2 L t g \alpha}{g}}.$$
Chúng tôi đã giải quyết bài toán bằng phương pháp tiêu chuẩn, có thể gọi là “thiết kế trên trục”. Với sự trợ giúp của nó, phương trình vectơ là một tính chất của hệ vô hướng, sau đó được giải theo cách xiên. Đây chính xác là cách những người nộp đơn giải quyết bài toán như vậy, nhưng với đáp số, ngay cả những câu hỏi đơn giản cũng thường khiến họ bối rối. Ví dụ:
1) Sự khác biệt giữa các hệ phương trình (4) và (5) là gì?
2) Tại sao trong ba phương trình (1) - (3), mô tả chuyển động có gia tốc đều, phương trình thứ hai lại được chọn để thiết kế?
3) Tại sao các trục tọa độ lại có hướng như vậy?
Bài tập 3: Trước khi đọc đáp số, hãy nghĩ xem bạn sẽ trả lời những câu hỏi này như thế nào.

Tất nhiên, bạn đã giải được bài toán bằng dữ liệu số và biết rằng dữ liệu tổng quát trước tiên phải thu được chữ đáp số, hoặc, như người ta nói, đáp số ở dạng tổng quát, sau đó thay số vào đó. Rõ ràng là chữ cái đáp số chứa nhiều thông tin hơn chữ số một cách không tương xứng. Vì vậy, hệ (4) có mối quan hệ gần giống với hệ (5) giống như chữ cái đáp số đối với số một. Vì vậy, nếu hệ thống đầu tiên luôn đúng, tức là từ nó bạn có thể tìm thấy tọa độ của vật thể bất cứ lúc nào, thì hệ thống thứ hai chỉ đúng vào thời điểm vật thể rơi xuống.

Về câu hỏi thứ hai, chúng tôi lưu ý rằng ba đại lượng $\vec{v}, \vec{s}$ và $t$ thay đổi theo thời gian được đưa vào các phương trình (1) - (3). Trong bài toán của chúng tôi, chúng tôi biết phạm vi ($\vec{s}$) và tìm thời gian cần thiết ($t$), vì vậy chúng tôi đã chọn phương trình có cặp $\vec{s}, t$, tức là phương trình thứ hai.

Bài tập 4. Cần truyền đạt điều kiện bài toán như thế nào để có thể giải được bằng phương trình (1) hoặc (3)?

Lưu ý rằng những tin nhắn này có thể dễ dàng được chuyển đến bài toán từ bất kỳ phần vật lý nào. Rốt cuộc, tất cả những gì gặp phải với số lượng bài toán có thể được chia thành ba nhóm: đã biết

⟦folio 61⟧

---
running_head:
folio:
---

số lượng; số lượng chưa biết cần tìm; những đại lượng chưa biết không cần tìm. Rõ ràng là nếu các công thức không bao gồm hai loại đầu tiên thì bài toán không thể giải được, nhưng nên loại bỏ những loại thứ ba nếu có thể.

Về câu hỏi thứ ba, chắc hẳn bạn sẽ coi đó là ma cà rồng và cho rằng tất nhiên những trục tọa độ này là tiện lợi nhất. Nói chung, trong một bài toán như vậy, việc nghĩ đến việc hướng các trục đi nơi khác có vẻ đầy tham vọng. Và điều này thật dễ dàng để biện minh. Thật vậy, việc coi một phương pháp là thuận tiện hơn là điều tự nhiên nếu nó cho phép người ta thu được đáp số với ít phép tính hơn. Theo nghĩa này, thuật ngữ $\vec{g}t^2/2$ hứa hẹn sẽ gây ra nhiều rắc rối nhất trong việc điều khiển (2) - do đó, các điều khiển trở thành hình vuông. Nếu chúng ta không muốn giải hai điều khiển hình vuông, một trục của điều khiển mong muốn phải hướng theo chiều ngang. Cái thứ hai có thể hướng đi bất cứ đâu, nhưng để không tạo ra những góc mới khi thiết kế, chúng ta sẽ hướng nó theo chiều dọc. Ngoài ra, phạm vi bay và độ cao thường xuất hiện trong các bài toán như vậy, tọa độ chính xác với sự lựa chọn trục này. Hãy chắc chắn, phải không? Chưa hết...

Lời giải 2. Hướng trục $Z$ vuông góc với tốc độ ban đầu $\vec{v}_0$ (hình 2). Trong các hình chiếu lên trục này, cùng với điều khiển (2), chúng ta thu được

$$z = \frac{g \cos \alpha \cdot t^2}{2}.$$

Tại $t=\tau$ $z=L \sin \alpha$. Từ đây chúng ta nhận được đáp số:

$$\tau = \sqrt{\frac{2Ltg\alpha}{g}}.$$

Điều này lời giải trở nên khả thi vì các đại lượng thuộc loại thứ ba (theo phân loại của chúng tôi) $\vec{v}_0$ là vectơ và bạn có thể loại bỏ nó bằng cách chọn từ xa trục tọa độ, từ đó có được một điều khiển với một điều khiển chưa biết.

Tuy nhiên, bạn có thể di chuyển xung quanh mà không cần bất kỳ trục nào...

Lời giải 3. Công thức (2) phát biểu rằng với chuyển động có gia tốc đều thì vectơ dịch chuyển của vật tại thời điểm bất kỳ bằng tổng của các vectơ $\vec{v}_0 t$ và $\vec{g}t^2/2$ (hình 3). Nhân tiện, điều này có nghĩa là chuyển động của một vật được ném theo một góc so với đường chân trời bao gồm chuyển động thẳng đều và chuyển động thẳng với tốc độ $\vec{v}_0$ và rơi tự do không có tốc độ ban đầu.

Hãy cùng “vẽ” công thức (2) cho thời điểm vật rơi $\tau$ (hình 4). Từ tam giác vuông thu được, chúng ta có thể dễ dàng tìm thấy

$$Ltg\alpha = \frac{g\tau^2}{2},$$

Bài tập 5. Một vật được ném một góc $\beta$ so với đường chân trời từ sườn núi nghiêng một góc $\alpha$ so với đường chân trời. Cơ thể được nén lại ở khoảng cách $L$ tính từ điểm ném. 1) Điều khiển chuyển động của cơ thể (điều khiển (2)) trong các hình chiếu trên trục 1—5 (hình 5) tại thời điểm cơ thể rơi xuống sườn núi. 2) Chọn bất kỳ hai điều khiển nào trong số này và chỉ ra rằng những điều khiển còn lại có thể lấy được từ hai điều khiển này. 3) Đối với mỗi điều khiển nhận được, hãy đưa ra bài toán, trong đó điều khiển này ngay lập tức dẫn đến mục tiêu.

Bài 2. Trên mặt phẳng nghiêng cố định chính có một góc

⟦folio 62⟧

---
running_head:
folio:
---

nghiêng α, viên bi thép va vào một góc β so với mặt phẳng (hình 6). Với giá trị nào của β quả bóng có thể quay trở lại điểm va chạm đầu tiên trên mặt phẳng? Mọi va chạm đều được coi là đàn hồi.

Hãy giới hạn bản thân ở một - giải pháp hợp lý nhất, theo quan điểm của chúng tôi, cho vấn đề này bài toán.

Lời giải. Chuyển động của quả bóng nói chung trong trường hợp này không được tăng tốc đồng đều do tác động lên mặt phẳng. Tuy nhiên, trong khoảng thời gian giữa các lần va chạm, quả bóng chỉ chuyển động dưới tác dụng của trọng lực và do đó với tốc độ không đổi. Do đó, đối với mỗi khoảng thời gian, chúng ta có thể sử dụng công thức (1) - (3), mặc dù mỗi lần như vậy chúng ta sẽ phải tìm tốc độ ban đầu.

Như đã biết, trong quá trình va chạm đàn hồi, thành phần vận tốc của quả bóng song song với mặt phẳng không thay đổi và thành phần vận tốc vuông góc với mặt phẳng chỉ đổi dấu và không thay đổi độ lớn. Khi đó, biết vận tốc của quả bóng $\vec{v}_0$ trước lần va chạm đầu tiên, ta sẽ tìm vận tốc sau lần va chạm này và thay vào công thức (2) cho phần đầu của chuyển động có gia tốc đều. Sau đó, sử dụng công thức (1), ta tìm vận tốc của quả bóng trước lần va chạm thứ hai, v.v. Nói cách khác, công thức (1) - (3) các điều kiện mặt phẳng của lần va chạm tiếp theo quyết định hoàn toàn chuyển động của quả bóng.

Tất cả những gì còn lại là xác định việc lựa chọn trục. Theo truyền thống, nếu chúng ta hướng trục ngang và trục dọc, thì tất nhiên, chúng ta sẽ được hưởng lợi từ việc viết phương trình chuyển động cho từng phần riêng lẻ (vì hình chiếu của quả bóng trên trục ngang chuyển động đều), nhưng điều kiện để quả bóng bật lại sẽ trở nên phức tạp hơn nhiều. Do đó, chúng ta hướng trục X và Y như trong hình 7 và viết phương trình (2) dưới dạng hình chiếu lên các trục này:

$$x = v_{0x}t + \frac{g_x t^2}{2},$$
$$y = v_{0y}t + \frac{g_y t^2}{2},$$

Ở đâu
$$v_{0x} = v_0 \cos \beta, \quad v_{0y} = v_0 \sin \beta,$$
$$g_x = -g \sin \alpha, \quad g_y = -g \cos \alpha.$$

Quả bóng sẽ chạm mặt phẳng lần thứ hai khi tọa độ y bằng 0 (một ưu điểm khác của các trục mà chúng ta đã chọn). Đã giải được phương trình

$$0 = v_{0y} \tau + \frac{g_y \tau^2}{2},$$

chúng ta sẽ thấy rằng cuộc trốn thoát thứ hai sẽ xảy ra sau một thời gian

$$\tau = \frac{2v_{0y}}{-g_y} = \frac{2v_0 \sin \beta}{g \cos \alpha}.$$

⟦folio 63⟧

---
running_head:
folio:
---

Để tìm tốc độ của quả bóng trước lần va chạm thứ hai (tức là sau thời gian $\tau$), chúng ta viết phương trình (1) dưới dạng hình chiếu lên trục của chúng ta:

$$v_x = v_{0x} + g_x t,$$
$$v_y = v_{0y} + g_y t.$$

Thay thế $t = \tau = 2v_{0y} / (-g_y)$, chúng ta thấy rằng trước cú đánh thứ hai có $v_y = -v_{0y}$ và do đó, ngay sau cú đánh có $v_y = v_{0y}$. Kết quả này cho phép bạn thở phào nhẹ nhõm - bạn không cần phải đếm thêm nữa. Vì thời gian giữa các lần đánh chỉ phụ thuộc vào $v_{0y}$ nên tất cả các lần đánh sẽ xảy ra sau cùng một khoảng thời gian.

Bây giờ thuận tiện nhất là trả lời câu hỏi bài toán bằng cách vẽ đồ thị về sự phụ thuộc tọa độ của quả bóng theo thời gian bên dưới thời gian kia (hình 8). Quả bóng sẽ quay trở lại điểm cũ nếu tại một số thời điểm $x = y = 0$, điều này chỉ có thể xảy ra nếu $T = n\tau$, trong đó $n$ là số nguyên. Vì thế,

$$\frac{2v_0 \cos \beta}{g \sin \alpha} = n \frac{2v_0 \sin \beta}{g \cos \alpha},$$

Ở đâu

$$\text{ctg} \beta = n \text{tg} \alpha.$$

Điều thú vị là đối với $n$ chẵn và lẻ quả bóng hành xử hơi khác nhau. Đối với $n$ chẵn, tác động trung bình của quả bóng (tất cả các tác động $n+1$) sẽ xảy ra vuông góc với mặt phẳng và quả bóng sẽ quay trở lại theo cùng một quỹ đạo. Nếu $n$ là số lẻ thì sau nửa cú đánh, quả bóng sẽ bay thẳng đứng lên trên, rơi trở lại và quay trở lại, lặp lại toàn bộ đường đi đã đi.

Bài toán 3. Trong vùng không gian nơi tạo ra một điện trường nằm ngang có cường độ $\vec{E}$, một quả bóng được phóng ra, khối lượng của nó là $m$ và điện tích là $q$, với tốc độ $\vec{v}_0$, hướng thẳng đứng lên trên. Vận tốc tối thiểu của quả bóng khi chuyển động là bao nhiêu?

Bạn có ngạc nhiên trước sự hiện diện của “điện” bài toán ở đây không? KHÔNG? Và đúng như vậy, bài toán này tất nhiên liên quan trực tiếp đến động học.

Hãy thảo luận về hai lời giải.

Lời giải 1. Hai lực không đổi tác dụng lên quả bóng đang bay: lực hấp dẫn $m\vec{g}$ và lực điện $\vec{E}q$ (hình 9). Theo định luật II Newton, gia tốc của quả bóng không đổi và bằng

$$\vec{a} = \frac{\vec{E}q + m\vec{g}}{m}.$$

Đồng thời

$$a = |\vec{a}| = \frac{\sqrt{(Eq)^2 + (mg)^2}}{m}.$$

hình 10 cho thấy vectơ vận tốc của quả bóng thay đổi như thế nào theo thời gian (“công thức (1) được rút ra”). Rõ ràng là tốc độ tối thiểu sẽ xảy ra theo thời gian

$$t = \frac{v_0 \sin \alpha}{\alpha},$$

và độ lớn của nó sẽ bằng nhau

$$v_{\min} = v_0 \cos \alpha = v_0 \frac{Eq}{\sqrt{(Eq)^2 + (mg)^2}}.$$

Nếu bạn muốn các công thức tương tự, bạn có thể làm khác đi.

Lời giải 2. Hãy hướng các trục tọa độ vuông góc và song song với gia tốc (hình 11) và viết phương trình (1) dưới dạng hình chiếu lên các trục này:

⟦folio 64⟧

---
running_head:
folio:
---

Nếu bạn có nhiều thời gian rảnh và giấy trắng, hãy đảm bảo rằng việc chọn một trục khác lời giải sẽ không dễ dàng hơn chút nào, nói một cách nhẹ nhàng.

Bài tập
cho công việc độc lập

1. Quả bóng rơi tự do từ độ cao $H$ xuống một mặt phẳng nghiêng tạo một góc $\alpha$ với đường chân trời (hình 12). Tìm tỉ số khoảng cách giữa các điểm mà quả bóng chạm vào mặt phẳng nghiêng. Sự va chạm của quả bóng với mặt phẳng được coi là đàn hồi tuyệt đối.

2. Một khẩu súng cối được bắn vào các vật thể nằm trên sườn núi. Các quả mìn sẽ rơi cách súng cối bao nhiêu nếu thời gian bay của chúng là $t$? Góc nghiêng của ngọn núi so với đường chân trời là $\beta$,.minngười bắn nghiêng một góc $\alpha$ so với đường chân trời.

3. Một quả bóng đàn hồi được lấy ra khỏi một cái bàn có độ cao $H$, truyền cho nó một vận tốc nằm ngang nhất định. Tại thời điểm quả bóng chịu một trong các va chạm đàn hồi tự do với sàn, một quả bóng khác bị kéo xuống theo phương ngang từ cùng một bàn, tạo cho nó một vận tốc đến mức va chạm với quả bóng đầu tiên. Cuộc gặp sẽ diễn ra ở độ cao nào?

4. Một electron chạy vào một tụ điện phẳng, song song với các bản của nó, với tốc độ $v_0=2 \cdot 10^6$ m/s. Tìm mô hình vận tốc của electron tại thời điểm nó rời khỏi tụ điện. Cường độ trường trong tụ điện là $E=100$ V/m, chiều dài của các bản là $L=8$ cm, điện tích của electron là $e=1,6 \cdot 10^{-19}$ C, khối lượng của nó là $m=9,1 \cdot 10^{-34}$ kg.
