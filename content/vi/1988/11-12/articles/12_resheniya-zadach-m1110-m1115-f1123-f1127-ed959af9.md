---
id: 1988-11-12-resheniya-zadach-m1110-m1115-f1123-f1127-ed959af9
issue: kvant_1988_11-12
year: 1988
number: 11-12
title: Lời giải bài toán M1110—M1115; F1123—F1127
rubric: zadachnik-kvanta
rubric_sub: Задачник «Кванта»
page_first: 39
page_last: 47
page_labels: 37-45
tag: 1WAA
lang: vi
source: kvant_digital
extraction: vision
content_sha256: 537102f3724f19239d8a8c40cd2ac6e4f5c8f0b59925580192824772e48dbace
prompt_sha256: draft-1
translated_from: content/ru/1988/11-12/articles/12_resheniya-zadach-m1110-m1115-f1123-f1127-ed959af9.md
source_content_sha256: 29682a28003e8b9c249ec1aa805720052614cbeea5a6cdef50ea813060499666
translation_model: draft
translation_run: vi-draft-2026-10-31
translation_quality: draft
---

⟦folio 37⟧

P1146. Tìm điện trở giữa các điểm $A$ và $B$ trong dãy vô hạn các phần tử như trên hình 6. Tất cả các phần tử đều giống hệt nhau, điện trở của mỗi phần tử là $r$. S. Zdravkovich (Yougoslavia)

P1147*. Một vật nặng nhỏ nằm trên một bệ nghiêng một góc nhỏ $\alpha$ so với mặt phẳng nằm ngang. Khối lượng của bệ lớn hơn nhiều so với trọng lượng, có khoảng cách từ mép dưới của bệ là $l$ (xem hình Ảnh 7). Sàn dao động điều hòa quanh trục $OO'$ với tần số $\omega$ và biên độ $L$. Hệ số ma sát giữa vật nặng và mặt sàn là $k$. Sau bao lâu thì vật nặng rơi xuống sàn? (Thời gian này được giả định là lớn hơn nhiều so với $2\pi/\omega$).

Lời giải bài toán

M1110 — M1115, F1123 — F1127

M1110. Với mỗi số tự nhiên $n>1$, chúng ta viết ra các ước chung nhất của tất cả các cặp số phân biệt có thể có từ 1 đến $n$. Chứng minh rằng $a$ trung bình số học của tất cả các số viết $n(n-1)/2$ không bị giới hạn bởi khoảng cách $n$ nhưng không vượt quá $\ln n+1$; $b$ giá trị trung bình hình học của chúng không vượt quá 10 đối với bất kỳ $n$ nào.

Hình 1.

a) Gọi $P_n(d)$ biểu thị số cặp $(a, b)$ số tự nhiên $a < b \leq n$ có ​​ước chung nhất $d=HOД(a, b)$. Mỗi cặp như vậy có thể được biểu diễn dưới dạng $a=dx, b=dy$, trong đó $x<y \leq k=[n/d]$, $x$ và $y$ là nguyên tố cùng nhau. Dễ dàng ước tính số $P_k=P_k(1)$ của các cặp $(x, y)$ số nguyên tố cùng nhau từ phía trên:

$$P_k \leq 1+2+\ldots+(k-1)=k(k-1)/2,$$

vì với mỗi $y \leq k$ số $x<y$ nhận tối đa $y-1$ giá trị. Từ đây

$$P_n(d)=P_{[n/d]} \leq \frac{n}{2d}\left(\frac{n}{d}-1\right) \leq \frac{n(n-1)}{2d^2}.$$

Khi kết thúc lời giải chúng ta sẽ chứng minh ước tính $P_k \geq k(k-1)/4$; từ đó chúng ta có được ước tính cho $P_n(d)$:

$$P_n(d) \geq \frac{1}{4}\left(\frac{n}{d}-1\right)\left(\frac{n}{d}-2\right)=$$

$$= \frac{n^2-3nd+2d^2}{4d^2} > \frac{n(n-1)}{4d^2}-\frac{3n}{4d}.$$

Tổng của các số $d=HOД(a, b)$ trên tất cả các tham số $(a, b)$ bằng $\sum_{d=1}^{n-1} dP_n(d)$ và trung bình số học của chúng $A$ bằng $\frac{2}{n(n-1)}\sum_{d=1}^{n-1} dP_n(d)$. Sử dụng ước tính cho $P_n(d)$, chúng tôi thu được:

$$A \leq \frac{2}{n(n-1)}\sum_{d=1}^{n-1} d\left(\frac{n(n-1)}{4d^2}-\frac{3n}{4d}\right)=$$

$$= \frac{1}{2}\left(1+\frac{1}{2}+\ldots+\frac{1}{n-1}\right)-\frac{3}{2}.$$

Tiếp theo chúng ta cần những thứ sau

Bổ đề. Đối với bất kỳ tự nhiên $n$

⟦folio 38⟧

$$\frac{1}{2} + \ldots + \frac{1}{n} < \ln n < 1 + \frac{1}{2} + \ldots + \frac{1}{n-1}.$$

Để chứng minh, chúng ta có thể sử dụng thực tế $\ln n = \int_{1}^{n} 1/t \, dt$ là diện tích nằm dưới hyperbol $f(t) = 1/t$ trên mặt cắt $1 \leq t \leq n$ (hình 1); bạn không thể sử dụng tích phân, nhưng, ví dụ, xác minh tính đúng đắn của các bất đẳng thức

$$\frac{\alpha}{1+\alpha} \leq \ln(1+\alpha) \leq \alpha \quad \text{при} \ \alpha \geq 0$$

(chú ý rằng tại $\alpha=0$ cả ba số hạng đều bằng 0 và so sánh đạo hàm), sau đó thay $\alpha=1$, $\alpha=\frac{1}{2}$, ..., $\alpha=\frac{1}{n-1}$ vào chúng và cộng tất cả các bất đẳng thức thu được.

Áp dụng bổ đề cho ước lượng (1) và (2), chúng ta thu được

$$\frac{1}{2} \ln n - \frac{3}{2} < A \leq \ln(n-1)+1 < \ln n+1.$$

6) Logarit của trung bình số học của một số số bằng trung bình số học của logarit của chúng. Do đó, đối với lời giải bài toán, đủ để chứng minh rằng trung bình số học của các số $\ln d$ (trong đó $d=\text{НОД} (a, b)$, $a<b \leq n$) nhỏ hơn 2: xét cho cùng, $e^2 < 10$, tức là $2 < \ln 10$. Tiến hành tương tự như trên, ta được

$$\frac{2}{n(n-1)} \sum_{d=1}^{n} \ln d \cdot P_n(d) \leq \sum_{d=2}^{n} \frac{\ln d}{d^2} < \sum_{d=2}^{n} \left( \frac{1}{d^2} \sum_{h=1}^{n} \frac{1}{h} \right).$$

Ở đây chúng ta áp dụng bổ đề: $\ln d \leq 1 + \frac{1}{2} + \ldots + \frac{1}{d}$.

Trong tổng kép giáo dục của các số có dạng $\frac{1}{d^2} \frac{1}{h}$ ($1 \leq h \leq d$, $2 \leq d \leq n$), sẽ thuận tiện khi ghép các số có cùng $h$ ($1 \leq d \leq n$ cho $h=1$, $h \leq d \leq n$ cho $h>1$) và đánh giá $\sum_{d=h}^{n} \frac{1}{d^2}$ bằng cách sử dụng tổng thu gọn dễ dàng

$$\sum_{d=h}^{n} \frac{1}{d(d-1)} = \sum_{d=h}^{n} \left( \frac{1}{d-1} - \frac{1}{d} \right) = \frac{1}{h-1} - \frac{1}{n} < \frac{1}{h-1}$$

(ước tính này sẽ cần thiết ngay bây giờ một lần cho $h=2$).

Cuối cùng chúng tôi nhận được

$$\sum_{d=2}^{n} \frac{\ln d}{d^2} < \sum_{d=2}^{n} \frac{1}{d^2} + \sum_{h=2}^{n} \left( \frac{1}{h} \sum_{d=h}^{n-1} \frac{1}{d^2} \right) < 1 + \sum_{h=2}^{n} \frac{1}{h(h-1)} < 2.$$

Bây giờ chúng ta hãy chứng minh ước tính $P_k \geq k(k-1)$ bằng cách sử dụng lời giải của phần a). Hãy đặt $m=[k/2]$. Trong số tất cả các điểm nguyên $(x, y)$, trong đó $0 < x < y \leq k$, chúng tôi gọi những điểm mà $x$ và $y$ là nguyên tố cùng nhau (hình 2) màu đỏ. Chúng ta hãy vẽ một tia từ gốc $(0, 0)$ qua mỗi điểm màu đỏ trong tam giác $x < y \leq m$. Tất nhiên, những tia $P_m$ này chứa tất cả $m(m-1)/2$ điểm nguyên trong tam giác $x < y \leq m$.

Xét các điểm nguyên trên bất kỳ tia $P_h$ nào.

⟦folio 39⟧

IX kolichestvo trên phần $h+1 \leqslant y \leqslant k$ có thể vượt quá kolichestvo của chúng trên phần $1 \leqslant y \leqslant h$ không quá một (xét cho cùng, các điểm nguyên $(x, y)$ xuất hiện trên tia với những khoảng thời gian bằng nhau). Do đó, trong hình thang $m+1 \leqslant y \leqslant k$, $x < y$, trong tổng số $k(k-1)/2-m(m-1)/2$ điểm nguyên, không có nhiều hơn $m(m-1)/2+P_m$ điểm trên các tia được vẽ. Tất cả các điểm khác trong hình thang đều có màu đỏ; do đó số lượng của họ

$$P_k - P_m \geqslant \frac{k(k-1)}{2} - m(m-1) - P_m,$$

Ở đâu

$$P_k \geqslant \frac{k(k-1)}{2} - m(m-1) \geqslant \frac{k(k-1)}{4}$$

(bất đẳng thức cuối cùng có thể dễ dàng kiểm tra được $k=2m$ và $k=2m+1$).

Có thể chỉ ra rằng $\lim_{k \to \infty} \frac{P_k}{k^2} = 3/\pi^2$, tức là xác suất mà một lựa chọn ngẫu nhiên các số tự nhiên $(x, y)$, không vượt quá $k$, hóa ra là nguyên tố cùng nhau, có xu hướng $6/\pi^2$ cho $k \to \infty$ (ví dụ, xem bài toán 30 ở Chương III trong cuốn sách “Giới thiệu về Lý thuyết Số” của I. M. Vinogradov. M.: Khoa học, 1965).

N.V. Vasiliev, V.F. Lev

M1111. Một đường tròn ngoại tiếp tam giác nhọn ABC. Các tiếp tuyến của đường tròn vẽ tại các điểm A và C cắt tiếp tuyến vẽ tại điểm B tương ứng tại các điểm M và N. Trong tam giác ABC vẽ đường cao BP (điểm P nằm trên cạnh AC). Chứng minh rằng đường thẳng BP là phân giác của góc MPN.

Chúng ta hãy chứng minh rằng các tam giác APM và CPN bằng nhau (xem hình), và theo đó $\angle APM = \angle CPN$, tức là $\angle MPB = \angle NPB$. Đặt AB=c, BC=a, $\angle BAC=a$, $\angle BCA=γ$. Trong tam giác cân AMB, góc MAB giữa tiếp tuyến AM và dây AB của một đường tròn đã cho bằng một nửa độ lớn của cung AB, cũng như góc nội tiếp ACB, tức là $\angle MAB=γ$. Do đó, $\angle MAP=α+\gamma$, AM=c/(2 cos γ). Tương tự, $\angle NCB=α$, $\angle NCP=γ+\alpha$, CN=a/(2 cos α). Ngoài ra, AP=c cos α, PC=a cos γ. Do đó, trong các tam giác APM và CPN các góc MAP và NCP và các tỉ số khung hình bằng nhau:

$$AP/AM=2 \cos α \cos γ=CP/CN,$$

điều đó chứng tỏ sự giống nhau của chúng.

Lưu ý rằng khẳng định bài toán và cách chứng minh của nó, với những sửa đổi nhỏ, cũng áp dụng cho tam giác tù.

V. I. Chinik

M1112. Trên bảng có hai số được viết là 1 và 2. Cho phép cộng các số mới như sau: nếu trên bảng có hai số a và b thì

Đáp số: trong trường hợp a) - có thể, trong trường hợp 6) - không thể. Lưu ý rằng nếu $c=a+b+ab$ thì $c+1=(a+1)(b+1)$. Vì vậy, cùng với các số viết trên bảng, sẽ thuận tiện khi xem các số lớn hơn 1. Khi đó mỗi số mới bằng tích của hai số hiện có. Đầu tiên là các số $2=1+1$ và $3=2+1$; Có nghĩa,

⟦folio 40⟧

Mono viết số ab+a+b. Có thể thu được a) số 13121 theo cách này không? b) số 12131? Chứng minh rằng có vô số số tự nhiên không thể biểu diễn dưới dạng e) x+y+xy, d) x+y+2xy với các số tự nhiên x và y.

Tất cả các số tiếp theo đều có dạng $2^n \cdot 3^m$ ($n$ và $m$ là số tự nhiên). Vẫn còn phải kiểm tra những con số này: $13121+1=2 \cdot 3^8$ và $12131+1=2^2 \cdot 3^2 \cdot 337$.

Theo quan điểm trên, đủ để chứng minh rằng có vô số số tự nhiên $n>1$ không thể biểu diễn dưới dạng $(x+1)(y+1)$ với các số tự nhiên x và y. Nhưng điều kiện này được thỏa mãn bởi tất cả các số nguyên tố (và chỉ chúng), và như chúng ta biết, có vô số số nguyên tố đó. (Nhắc lại ý đưa ra về chứng minh tập hợp số nguyên tố vô cực: nếu $p_i$, ..., $p_k$ là số nguyên tố thì số $p_1 \cdot \dots \cdot p_k+1$ có ước số là số nguyên tố khác với $p_i$.) d) Nếu $z=x+y+2xy$ thì $2z+1=(2x+1)(2y+1)$. Lập luận theo cách tương tự như trong bài toánc), chúng tôi tin rằng tuyên bố của chúng tôi tương đương với thực tế là tập hợp các số nguyên tố có dạng $2z+1$ (tức là số lẻ) là vô hạn.

Hãy tự chứng minh câu bài toán c) và d) với mọi số tự nhiên a, tập hợp các số không thể biểu diễn dưới dạng x+y+axy là vô hạn.

A. A. Berzins, V. G. Iltsev

M1113*. 21 tuổi ở quê. Liên lạc hàng không giữa họ được thực hiện bởi một số công ty hàng không, một trong số đó phục vụ 10 công ty hàng không miễn phí kết nối năm thành phố thông qua ghép nối (trong trường hợp này, máy bay của một số công ty có thể bay giữa hai thành phố). Cứ hai thành phố được kết nối bởi ít nhất một hãng hàng không vô tận. Điều này có thể thực hiện được với số lượng công ty hàng không tối thiểu là bao nhiêu?

Hình 1.

Đáp số: Dành cho 21. Vì số lượng cặp thành phố là $21 \cdot 20/2=210$ nên mỗi cặp được phục vụ bởi ít nhất một công ty và mỗi công ty phục vụ 10 cặp nên số lượng công ty không thể ít hơn 210:10-21.

Vẫn còn phải đưa ra một ví dụ về sơ đồ phục vụ cho các thành phố của các công ty hàng không thứ 21. Chúng ta hãy biểu thị các thành phố bằng các đỉnh của hình 21 đều và được đánh số theo chiều kim đồng hồ (hình 1). Hãy để đại đội 1 phục vụ các thành phố có số 1, 3, 8, 9, 12, đại đội thứ 2 - các thành phố có số 2, 4, 9, 10, 13, thu được từ tập đầu tiên bằng cách xoay một góc $360^\circ/21$ (theo chiều kim đồng hồ) và nói chung, đại đội thứ k - thành phố, thu được từ tập đầu tiên bằng cách quay $(k-1) \cdot 360^\circ/21$. Bất kỳ cặp đỉnh nào của đa giác sẽ thuộc một trong các tập hợp này, vì vị trí trung bình của các điểm của tập hợp đầu tiên bằng độ dài của tất cả các cạnh và đường chéo của 21-giác.

Dễ dàng kiểm tra xem mạch mà chúng ta xây dựng có thỏa mãn các điều kiện sau không: 1) hai điểm bất kỳ được bao gồm trong ít nhất một bộ (điều này bắt buộc phải có trong bài toán), 2) hai bộ bất kỳ có một và chỉ một điểm. Nếu chúng ta thay từ “tập hợp” ở đây bằng từ “đường thẳng” và thêm một điều kiện nữa - 3) có 4 điểm, không có 3 điểm nào nằm trên cùng một đường thẳng - chúng ta thu được tiên đề của cái gọi là mặt phẳng xạ ảnh (trừu tượng): theo định nghĩa, đây là tập hợp các điểm tùy ý trong đó một số tập hợp con được xác định - “đường thẳng” thỏa mãn điều kiện 1) - 3). Đặc biệt, sơ đồ của chúng tôi là mặt phẳng xạ ảnh hữu hạn của 21-giác. Không khó để chứng minh rằng hai mặt phẳng xạ ảnh hữu hạn bất kỳ đều chứa cùng số điểm và nếu số này bằng n thì số điểm

⟦folio 41⟧

trên mặt phẳng nó bằng $n^2 - n + 1$ và số đó là số thẳng. hình 2 hiển thị sơ đồ mặt phẳng xạ ảnh nhỏ nhất - bảy điểm.

D. V. Fomin, V. N. Dubrovsky

**M1114. Chứng minh rằng với mọi tứ diện bất đẳng thức đều đúng**

$$r < \frac{ab}{2(a+b)},$$

$a, b$ là chiều dài của hai cạnh giao nhau, $a, r$ là bán kính của quả cầu nội tiếp.

Hình 1.

Hình 2.

**M1115*. a) Dòng đầu tiên chứa 19 số tự nhiên không quá 88, dòng thứ hai chứa 88 số tự nhiên không quá 19. Ta sử dụng một đoạn gồm một hoặc nhiều số viết liên tiếp trên một mặt. Chứng minh rằng bạn có thể chọn một đoạn từ các hàng đã cho sao cho tổng các số trong chúng bằng nhau. b) Cho $n, m, k$ là các số tự nhiên, $m \geq n$. Chứng minh rằng nếu

$$1 + 2 + \dots + n = mk,$$

thì các số 1, 2, ..., $n$ có thể chia thành các nhóm $k$ sao cho

Lưu ý rằng bán kính $r$ của hình cầu nội tiếp trong tứ diện bằng $3V/S$, trong đó $V$ là thể tích của nó và $S$ là diện tích bề mặt. (Để chứng minh điều đó, chỉ cần tưởng tượng thể tích của một tứ diện là tổng thể tích của bốn tứ diện, đáy của chúng là các mặt của một tứ diện cho trước và các đỉnh trùng với tâm của hình cầu.) Chúng ta hãy ước tính $V$ và $S$ thông qua độ dài của các cạnh $a, b$ và khoảng cách $h$ giữa các đường giao nhau chứa các cạnh này. Chúng ta hãy mô tả một hình bình hành xung quanh tứ diện, trong đó $a$ là cạnh của đáy dưới và $b$ là cạnh của đáy trên (hình 1). Chiều cao của nó được ước tính là $h$ nên thể tích của nó không vượt quá $abh$. Đồng thời, thể tích này lớn hơn thể tích của khối tứ diện 6 lần, điều này sẽ trở nên rõ ràng nếu chúng ta lấy mặt bên của nó, chứa mặt của khối tứ diện, làm đáy của hình bình hành. Vì vậy, $V \leq abh/6$.

Mặt khác, khoảng cách từ các đầu của cạnh $b$ tứ diện đến cạnh $a$ không nhỏ hơn $h$ và ít nhất một trong số chúng lớn hơn $h$ (hình 2), do đó tổng diện tích của các mặt liền kề với cạnh $a$ lớn hơn $ah$. Tương tự, tổng diện tích của hai mặt còn lại lớn hơn $bh$, tức là $S > (a+b)h$, và

$$r = \frac{3V}{S} < \frac{abh}{2(a+b)h} = \frac{ab}{2(a+b)}.$$

N. V. Vasiliev

a) Gọi $a_1, a_2, \dots, a_{19}$ là các số của dòng đầu tiên, $b_1, b_2, \dots, b_{88}$ dòng thứ hai, $A(i)=a_1+\dots+a_i, B(i)=b_1+\dots+b_i$. Giả sử $A(19) \geqslant B(88)$ (trường hợp $A(19) < B(88)$ xử lý tương tự). Đối với mỗi $i$, chúng tôi biểu thị bằng $n_i$ số nhỏ nhất trong số $n$ sao cho $A(n)-B(i) \geqslant 0$; $n_i$ như vậy tồn tại do giả định của chúng tôi. Hãy xem xét 88 điểm khác biệt $A(n_i)-B(i)$; chúng có thể thuộc các giá trị từ 0 đến 87, kể từ $A(n_i)-B(i)=A(n_i-1)-B(i)+a_{n_i} < a_{n_i} \leqslant 88$. Nếu những khác biệt này khác nhau thì có 0 trong số đó và tuyên bố của chúng tôi được thỏa mãn. Ngược lại, hai điểm khác biệt - chẳng hạn như đối với $i=l$ và $i=k$, $k<l$ - trùng khớp. Sau đó

$$A(n_l)-A(n_k)=B(l)-B(k),$$

tức là các phân đoạn được yêu cầu là $a_{n_k+1}, \dots, a_{n_l}$ và $b_{k+1}, \dots, b_l$.

Rõ ràng là các số 19 và 88 trong bài toán này có thể được thay thế bằng bất kỳ số tự nhiên nào.

6) Ta tiến hành chứng minh bằng quy nạp trên $n$. Đối với $n=1$ không có gì để chứng minh. Giả sử rằng tuyên bố của chúng tôi

⟦folio 42⟧

đúng với tất cả các giá trị của tham số nhỏ hơn $n$ và xem xét tập hợp $S_n = \{1, 2, \dots, n\}$.

Nếu $m = n$ thì $(n+1)/2 = k$ là số nguyên và phân vùng bắt buộc như sau:

$$\{n\}, \{1, n-1\}, \{2, n-2\}, \dots, \{(n-1)/2, (n+1)/2\};$$

nếu $m = n+1$ thì $n$ là số chẵn và phân vùng có dạng

$$\{1, n\}, \{2, n-1\}, \dots, \{n/2, n/2+1\}.$$

Bây giờ chúng ta hãy xem trường hợp 3.

Trường hợp 1: $n+1 < m < 2n$, $m$ không rõ ràng. Chọn từ bộ $S_n$ bộ $S_{m-n-1}$; các số $2n-m+1$ còn lại có thể được chia thành từng cặp với tổng là $m: \{m-n, n\}, \{m-n+1, n-1\}, \dots, \{(m-1)/2, (m+1)/2\}$. Tổng các số trong tập hợp $S_{m-n-1}$ bằng

$$\frac{(m-n-1)(m-n)}{2} = \frac{m^2-m(2n+1)}{2} + \frac{n(n+1)}{2} = m\left(\frac{m-2n-1}{2} + k\right)$$

và chia hết cho $m$ và $m \geqslant m-n-1$, do đó, những số này, theo giả định quy nạp, cũng có thể được chia thành các nhóm có tổng $m$ trong mỗi nhóm.

Trường hợp 2: $n+1 < m < 2n$, $m$ chẵn. Ở đây chúng ta cũng sẽ chọn tập hợp $S_{m-n-1}$ và chia các số còn lại thành từng cặp có tổng $m: \{m-n, n\}, \{m-n+1, n-1\}, \dots, \{m/2-1, m/2+1\}$ và một số khác $m/2$. Chúng ta hãy biểu thị tổng các số trong tập hợp $S_{m-n+1}$ là $(m-2n-1+2k)(m/2)$. Nó chia hết cho $m/2$ và $m/2 \geqslant m-n-1$, vì $m/2 < n$. Do đó, tập hợp $S_{m-n-1}$ có thể được chia thành các nhóm $m-2n-1+2k$ số lẻ có tổng $m/2$, thêm $m/2$ vào một trong số chúng và kết hợp các nhóm còn lại theo cặp - chúng ta có các nhóm có tổng $m$.

Trường hợp 3: $m \geqslant 2n$. Chúng tôi sẽ chia tập hợp $S_n$ thành các nhóm $k$ có ​​tổng bằng nhau, tổng này sẽ tự động bằng $m$. Lưu ý rằng $k = n(n+1)/2m \leqslant (n+1)/4$ và do đó $n-2k \geqslant 2k-1 > 0$.

Chúng ta hãy chọn bộ $S_{n-2k}$ từ $S_n$. Tổng các số trong tập hợp này

$$\frac{(n-2k)(n-2k+1)}{2} = \frac{n(n+1)}{2} - k(2n+1)+2k^2$$

chia hết cho $k$ và thương của phép chia này không nhỏ hơn $n-2k$ kể từ $(n-2k)(n-2k+1)/2(n-2k) = (n-2k+1)/2 \geqslant k)$.

Do đó, $S_{n-2k}$ có thể được phân chia theo giả định quy nạp thành các nhóm $k$ có tổng bằng nhau. Các số $2k$ còn lại được chia thành các cặp $k$ có tổng bằng nhau: $\{n-2k+1, n\}, \{n-2k+2, n-1\}, \dots$. Nó vẫn còn để đoàn kết mỗi nhóm với một cặp.

A. V. Anzhans

F1123. Đến cuối nhóm nước thẳng đứng dùng một miếng cao su ngắn

Hãy xem xét các lực tác dụng lên vòi nằm ngang (xem hình). Đây là hai lực $F$ của áp suất nước tại các chỗ uốn của vòi, lực của trọng lượng của nước $\rho lSg$ và trọng lực của bản thân vòi $Mg$.

⟦folio 43⟧

Một vòi thép có khối lượng M được gắn vào ống. Ở dòng nước nào vòi phun sẽ nằm ngang? Diện tích phần vòi là S, chiều dài của nó là l. Huấn luyện viên để yêu cầu.

F1124. Trên một thanh ngang nhẵn có bán kính R đặt một “cuốn sách nhỏ” gồm hai mặt phẳng hình vuông mỏng đồng nhất có cạnh l=4R. Các tấm được giữ với nhau bằng một thanh bản lề không trọng lượng. Các tấm tạo thành góc nào ở trạng thái cân bằng? Liệu trạng thái cân bằng này có ổn định không?

F1125. Một bình cô lập nhiệt thẳng đứng chứa khí đơn nguyên tử được đóng lại bằng một pít-tông có khối lượng M. Một máy cắt có công suất N được bật trong bình và pít-tông bắt đầu chuyển động từ từ lên trên. Sau bao lâu vật lên đến độ cao H so với

⟦folio 44⟧

Vị trí chính? Công suất của piston, rãnh và áp suất khí quyển được tính đến.

$$N\tau = MgH + \frac{3}{2} MgH$$

chúng tôi nhận được

$$\tau = \frac{5}{2} \frac{MgH}{N}.$$

A. R. Zilberman

F1126. Trong mạch hiển thị ở hình 1, phím K “dao động” giữa vị trí 1 và 2 với tần số $f=100\Gamma$; Chìa khóa vẫn ở mỗi vị trí trong cùng một khoảng thời gian. Bắt đầu dòng điện qua điện trở. $C_1=10$ µF, $C_2=30$ µF, $R=100$ kOhm.

Hình 1.

Hình 2.

Đáp số cho câu hỏi bài toán ước tính: dòng điện trung bình qua điện trở phải bằng 0. Trên thực tế, với bất kỳ giá trị nào khác 0, điện thế ở điểm nối của tụ điện cũng sẽ tăng vô hạn theo thời gian.

Điều đáng quan tâm hơn là sự truyền dòng điện qua pin, giả sử điện áp của pin là $U_0=10$V.

Có thể dễ dàng kiểm tra xem khi công tắc ở một trong các vị trí - 1 hoặc 2 - thì các tụ điện được sạc lại độc lập. Thật vậy, để một tụ điện có điện dung $C$ được tích điện đến điện áp $U$. Hãy đóng nó lại với một điện trở có điện trở $R$. Dòng điện $I=U/R$ sẽ chạy qua mạch, kết quả là trong một thời gian ngắn $t$ điện tích của tụ điện sẽ thay đổi thành

$$\Delta q = I\tau = U\tau/R,$$

và điện áp là

$$\Delta U = \Delta q/C = U\tau/(RC),$$

Vì thế

$$\frac{\Delta U}{U} = \frac{\tau}{RC} \ll 1.$$

Trên thực tế, sự thay đổi điện áp thậm chí còn nhỏ hơn vì một số điện tích cũng chảy ra từ pin.

Vì vậy, điện áp của tụ điện có thể được coi là không đổi. Sau đó, đối với các mạch hiển thị trong hình 2, chúng ta nhận được

$$\frac{U_1}{R} - i_1 = I_1, \quad \frac{U_2}{R} - i_2 = I_2.$$

Nhưng

$$i_1\tau_1 = I_2\tau_2 \text{ и } i_2\tau_2 = I_1\tau_1,$$

hoặc cho rằng $\tau_1 = \tau_2 = 1/(2f)$,

$$i_1 = I_2 \text{ и } i_2 = I_1.$$

Vì vậy, ở chế độ đã thiết lập

$$U_1 = U_2 = \frac{U_0}{2},$$

$$I_1 + I_2 = \frac{U_0}{2R},$$

và dòng điện qua pin

$$I = \frac{I_1 + I_2}{2} = \frac{U_0}{4R} = 25 \text{ мкA.}$$

⟦folio 45⟧

Điều gây tò mò là đáp số không bao gồm các giá trị điện dung của tụ điện. Chúng tôi chỉ cần chúng để xác nhận các điều kiện RC≈1/f.

A. R. Zilberman

F1127. Đèn pin phát ra một chùm tia, hội tụ ở khoảng cách $R_0=1$ m thành một điểm nhỏ. Trên đường đi của chùm tia, hai gương phẳng hình vuông được đặt sao cho đường tiếp xúc của chúng cắt trục chùm tia cách đèn pin một khoảng $r=70$ cm và phân bố lại trục này. Các mặt phẳng của gương chồng lên nhau và một trong các gương tạo một góc $\alpha=30^\circ$ với trục của chùm tia. Chùm tia sẽ hội tụ ở khoảng cách bao nhiêu so với đèn pin?

Đường đi của các tia phát ra từ đèn pin F được biểu thị ở hình. Trước khi đặt gương vào đường đi của tia sáng, chùm tia hội tụ tại điểm A.

Chúng ta hãy xem phần tia sáng đầu tiên bị phản xạ từ gương 1. Sau khi phản xạ, chúng đi như thể được phát ra bởi đèn pin F', tức là sự phản xạ của đèn pin F trong gương 1. Các tia này sẽ giao nhau tại điểm $A'$ nếu gương 2 không cản đường đi của chúng. Sau khi phản xạ từ đó, các tia sáng đi như thể được phát ra bởi đèn pin F', tức là sự phản xạ của F' trong gương 2. Dễ dàng nhận thấy Ф'' đối xứng tâm với Ф đối với điểm O. Kết quả là chùm tia tập trung tại điểm $A''$, đối xứng tâm với điểm A và nằm trên trục chùm tia một khoảng

$$x=R_0-2(R_0-r)=40 \text{ см}$$

từ đèn pin.

Lập luận tương tự cho thấy các tia đầu tiên phản xạ từ gương 2 cũng cắt nhau tại điểm $A''$. Vị trí của điểm này rõ ràng không phụ thuộc vào góc $\alpha$.

M. M. Tsypin
