---
id: 1976-2-myakishev-raschet-tsepey-peremennogo-toka-s-pomoschyu-vektornyih-diagramm-62c93d73
issue: kvant_1976_2
year: 1976
number: "2"
title: Tính toán mạch điện xoay chiều bằng sơ đồ vectơ
authors:
  - Мякишев Г. Я.
rubric: praktikum-abiturienta
rubric_sub: Практикум абитуриента
page_first: 53
page_last: 59
page_labels: 51-57
tag: RTRZ
lang: vi
source: kvant_digital
extraction: vision
content_sha256: 0427360d808637e58ce2e979e593ccfead3222d9664c0f3b89d67256af3deb63
prompt_sha256: draft-1
translated_from: content/ru/1976/02/articles/14_myakishev-raschet-tsepey-peremennogo-toka-s-pomoschyu-vektornyih-diagramm-62c93d73.md
source_content_sha256: ff831a5601b2086788ce7356b79dadf27b93a119884b30fe609019f9194c7b24
translation_model: draft
translation_run: vi-draft-2026-10-31
translation_quality: draft
---

⟦folio 51⟧

G. Myakishchev

Việc tính toán mạch điện xoay chiều phức tạp hơn nhiều so với mạch điện một chiều. Tuy nhiên, nếu hướng và cường độ dòng điện thay đổi theo định luật điều hòa thì có một phương pháp tính toán mạch điện khá đơn giản và trực quan - phương pháp sơ đồ vectơ. Chúng tôi muốn giới thiệu với người đọc về anh ấy trong bài viết này.

Phương trình mô tả dao động cưỡng bức trong mạch dao động

Dòng điện xoay chiều công nghiệp là dao động điện từ cưỡng bức. Nếu hướng $u = u(t)$ ở hai đầu sợi dây thay đổi theo định luật điều hòa
$$u = U_0 \cos \omega t,$$
(1)
thì cường độ dòng điện $i$ cũng thay đổi điều hòa với cùng tần số $\omega$, nhưng trong trường hợp chung, dòng điện lệch pha so với hướng bởi một giá trị không đổi $\varphi$:
$$i = I_0 \cos (\omega t + \varphi).$$
(2)

Tuy nhiên, tại thời điểm đầu tiên sau khi đóng mạch, dao động của dòng điện có hình dạng phức tạp hơn nhiều. Khi đóng lại, mạch điện dường như nhận được một “lực đẩy” và nếu nó có tần số dao động riêng $\omega_0$ thì sẽ phát sinh dao động điện từ tự do trong đó. Các dao động này được xếp chồng lên các dao động cưỡng bức có tần số $\omega$, nhưng giảm dần do có điện trở hoạt động $R$ trong mạch (tại đó năng lượng được giải phóng dưới dạng nhiệt). Chỉ sau khi dao động tự do đã tắt đi thì dao động cưỡng bức mới được coi là thiết lập. Biên độ hiện tại $I_0$ trong công thức (2) là biên độ của các dao động cơ học đã thiết lập (để biết thêm chi tiết về điều này, hãy xem, ví dụ, bài viết của G. Ya. Myakishchev “Dao động cơ học cưỡng bức”, «Kvant», 1974, số 11).

Một trường hợp đặc biệt khá đơn giản nhưng rất quan trọng là dao động cưỡng bức trong mạch gồm một dây dẫn mắc nối tiếp có điện trở chủ động $R$, một cuộn cảm $L$ và một tụ điện $C$ (Hình 1). Mạch như vậy gọi là mạch dao động nối tiếp. Để hướng $u$ ở hai đầu sợi dây thay đổi theo định luật mô tả bằng phương trình (1); thì cường độ dòng điện $i$ trong mạch thay đổi theo biểu thức (2). Biên độ hiện tại $I_0$ và độ lệch pha $\varphi$ là bao nhiêu?

Như đã biết, phương trình mô tả dao động dòng điện cưỡng bức trong mạch này có dạng sau:
$$L \frac{\Delta i}{\Delta t} + Ri + \frac{q}{C} = U_0 \cos \omega t.$$ (3)
Ở đây $q$ là điện tích của tụ điện. (Cái này

⟦folio 52⟧

Phương trình này tương tự như phương trình mô tả các dao động cơ học cưỡng bức, ví dụ, dao động bên ngoài của tải.)

Phương trình (3) có thể được sử dụng như sau. Tại bất kỳ thời điểm nào, tổng điện áp ($u = U_0 \cos \omega t$) ở hai đầu mạch bằng tổng điện áp trên điện trở hoạt động ($u_R = Ri$), trên cuộn cảm ($u_L = L \frac{\Delta i}{\Delta t}$) và trên tụ điện ($u_C = \frac{q}{C}$):

$$u_L + u_R + u_C = u.$$ (4)

Cả ba điện áp đều dao động cùng tần số, nhưng có biên độ khác nhau và lệch pha nhau.

Để tìm biên độ của các dao động theo cường độ dòng điện và độ lệch pha giữa dòng điện và điện áp, bạn cần có khả năng cộng các dao động điều hòa lệch pha. Để làm điều này, bạn cần biết biên độ điện áp $u_R$, $u_L$ và $u_C$, cũng như độ lệch pha của các điện áp này so với cường độ dòng điện. Điều này sẽ được thảo luận trong ba đoạn tiếp theo.

Điện áp trên điện trở hoạt động

Trường hợp đơn giản nhất của mạch điện là mạch điện chỉ chứa điện trở tác dụng $R$. Đối với chuỗi như vậy, phương trình cơ bản (3) sẽ có dạng sau:

$$Ri = U_0 \cos \omega t.$$ (5)

Từ đây

$$i = \frac{U_0}{R} \cos \omega t = I_0 \cos \omega t.$$ (6)

Biên độ điện áp liên hệ với biên độ dòng điện bằng sự tương ứng

$$U_0 = I_0 R.$$ (7)

Sự dao động của dòng điện và điện áp trên điện trở hoạt động cùng pha. Lưu ý rằng đẳng thức (7) không khác với định luật Ohm đối với dòng điện một chiều.

Điện áp trên phản ứng cảm ứng

Đặt mục tiêu bao gồm một cuộn dây có độ tự cảm $L$. Chúng ta bỏ qua điện trở chủ động của cuộn dây. Thay vì phương trình (3), trong trường hợp này chúng ta sẽ có một phương trình đơn giản hơn

$$L \frac{\Delta i}{\Delta t} = U_0 \cos \omega t,$$

hoặc

$$\frac{\Delta i}{\Delta t} = \frac{U_0}{L} \cos \omega t.$$ (8)

Bây giờ tốc độ thay đổi của dòng điện ($\frac{\Delta i}{\Delta t}$) thực hiện các dao động điều hòa, trùng pha với dao động điện áp. Biên độ của những dao động này là $\frac{U_0}{L}$.

Để biểu thị cường độ dòng điện, người ta sử dụng sự tương tự giữa dao động điện từ trong mạch và dao động cơ của tải bên ngoài. Như đã biết, cường độ dòng điện $i$ tương ứng với tốc độ dao động của tải $v$ và tốc độ thay đổi của cường độ dòng điện $\frac{\Delta i}{\Delta t}$ tương ứng với gia tốc của tải $a$. Nhưng các dao động vận tốc tụt hậu so với các dao động gia tốc $\pi/2$, và biên độ vận tốc $v_0$ liên hệ với biên độ gia tốc $a_0$ bởi sự tương ứng $v_0 = a_0/\omega$. Điều này đúng với các dao động điều hòa thuộc bất kỳ bản chất nào. Do đó, nếu tốc độ thay đổi của dòng điện thỏa mãn phương trình (8) thì dòng điện thay đổi theo thời gian theo định luật

$$i = \frac{U_0}{L \omega} \cos \left(\omega t - \frac{\pi}{2}\right) = I_0 \cos \left(\omega t - \frac{\pi}{2}\right).$$ (9)

Biên độ điện áp liên hệ với biên độ dòng điện bằng sự tương ứng

$$U_0 = I_0 L \omega = I_0 R_L.$$ (10)

Đại lượng $R_L = L \omega$ được gọi là điện trở cảm ứng.

⟦folio 53⟧

Vì vậy, theo biểu thức (1) và (9), cường độ dòng điện trên điện kháng cảm ứng chậm hơn điện áp cùng pha một khoảng π/2.

điện áp tụ điện

Xét một mạch điện gồm một tụ điện C. Chúng ta khẳng định điện trở và độ tự cảm tác dụng của mạch điện. Dao động cưỡng bức trong mạch này sẽ được mô tả bằng phương trình

$$\frac{q}{C} = U_0 \cos \omega t. \tag{11}$$

Điện tích của tụ điện dao động cùng pha với điện áp và biên độ của các dao động này là $U_0 C$:

$$q = U_0 C \cos \omega t. \tag{12}$$

Trong trường hợp dao động điện từ, điện tích tương ứng với tọa độ của vật thực hiện dao động cơ học, và cường độ dòng điện, tức là tốc độ thay đổi điện tích ($i = \frac{\Delta q}{\Delta t}$), tương tự như tốc độ của vật này. Vì đối với bất kỳ dao động điều hòa nào, biên độ vận tốc của đại lượng lớn hơn $\omega$ lần so với biên độ của chính đại lượng đó và tốc độ lệch pha với các đại lượng π/2, nên trong trường hợp của chúng ta

$$i = \frac{\Delta q}{\Delta t} = U_0 C \cos \left( \omega t + \frac{\pi}{2} \right) = I_0 \cos \left( \omega t + \frac{\pi}{2} \right). \tag{13}$$

Do đó, công suất của mạch được xác định bởi điện áp trên tụ điện bằng π/2, hoặc tương tự, điện áp từ bộ ngắt mạch bằng π/2.

Biên độ điện áp là

$$U_0 = \frac{I_0}{C \omega} = I_0 R_C, \tag{14}$$

trong đó $R_C = \frac{1}{C \omega}$ là điện trở của tụ điện, gọi là điện dung.

Bổ sung các dao động điều hòa bằng sơ đồ vectơ

Dao động điều hòa có thể được thêm vào theo nhiều cách khác nhau (phân tích, đồ họa, v.v.). Tuy nhiên, trong trường hợp một phần khi tần số dao động giống nhau thì sử dụng phương pháp sơ đồ vectơ là thuận tiện nhất. Phương pháp này bao gồm những gì?

Từ bài giảng vật lý lớp 10, người ta đã biết rằng phép chiếu lên bất kỳ hướng nào của một vectơ quay với vận tốc góc không đổi $\omega$ thực hiện một dao động điều hòa. Nếu mô hình của vectơ $x_0$ bằng $x_0$ thì hình chiếu của nó lên trục $OX$ bằng $x = x_0 \cos \varphi$ (Hình 2). Khi vectơ $x_0$ quay đều thì góc $\varphi$ thay đổi theo thời gian theo định luật

$$\varphi = \omega t + \varphi_0,$$

trong đó $\varphi_0$ là giá trị của góc $\varphi$ tại thời điểm ban đầu $t=0$. Do đó, hình chiếu của vectơ quay dao động tuân theo định luật

$$x = x_0 \cos \left( \omega t + \varphi_0 \right). \tag{15}$$

Hình 2.

Hình 3.

⟦folio 54⟧

Bây giờ chúng ta hãy xem xét phép cộng hai dao động điều hòa xảy ra với cùng tần số $\omega$, nhưng có biên độ khác nhau $x_{0_1}$ và $x_{0_2}$ và các pha ban đầu khác nhau $\varphi_{0_1}$ và $\varphi_{0_2}$:

$$x_1 = x_{0_1} \cos(\omega t + \varphi_{0_1}),$$
$$x_2 = x_{0_2} \cos(\omega t + \varphi_{0_2}).$$

Các dao động được thêm vào tại bất kỳ thời điểm nào đều có độ lệch pha $\varphi = \varphi_{0_1} - \varphi_{0_2}$. Những dao động này có thể được biểu diễn dưới dạng dao động của hình chiếu của vectơ $x_{0_1}$ và $x_{0_2}$, quay tương đối với nhau một góc $\varphi$ và quay với vận tốc góc $\omega$ (Hình 3).

Cộng các vectơ $x_{0_1}$ và $x_{0_2}$, chúng ta thu được tổng vectơ $x_0 = x_{0_1} + x_{0_2}$. Hình chiếu $x$ của vectơ này lên hướng $OX$ cũng thực hiện một dao động điều hòa. Nhưng hình chiếu của vectơ tổng bằng tổng các hình chiếu của các vectơ được thêm vào. Kể từ đây,

$$x = x_1 + x_2 = x_0 \cos(\omega t + \varphi_0),$$

(16) trong đó $x_0$ là biên độ và $\varphi_0$ là pha ban đầu của dao động thu được. Các đại lượng $x_0$ và $\varphi_0$ có thể được tìm thấy bằng cách biết $x_{0_1}, x_{0_2}, \varphi_{0_1}$ và $\varphi_{0_2}$. Thật dễ dàng để chứng minh (xem Hình 3) rằng

$$x_0^2 = x_{0_1}^2 + x_{0_2}^2 + 2x_{0_1}x_{0_2} \cos(\varphi_{0_1} - \varphi_{0_2}),$$
$$tg \varphi_0 = \frac{x_{0_1} \sin \varphi_{0_1} + x_{0_2} \sin \varphi_{0_2}}{x_{0_1} \cos \varphi_{0_1} + x_{0_2} \cos \varphi_{0_2}}.$$

Vì vậy, mỗi dao động điều hòa có thể được biểu diễn bằng một vectơ quay với vận tốc góc không đổi và tổng của sóng hài

Hình 4.

dao động ical - sử dụng vectơ (tổng) kết quả quay với cùng tốc độ. Biểu diễn đồ họa sử dụng các giá trị của các đại lượng thay đổi hài hòa và sự tương ứng giữa chúng được gọi là sơ đồ vectơ.

Sơ đồ vector của mạch dao động nối tiếp

Chúng ta hãy quay lại mạch điện như trong Hình 1 và xây dựng sơ đồ vectơ dòng điện và điện áp cho nó. Điều này cho phép chúng ta xác định biên độ của dòng điện trong mạch và các pha cdwg giữa cường độ dòng điện và điện áp đặt vào.

Cường độ dòng điện tại một thời điểm nhất định là như nhau ở tất cả các phần của mạch*). Vì vậy, sẽ thuận tiện hơn khi xây dựng sơ đồ vectơ trên cơ sở có vectơ $I_0$ tương ứng với cường độ dòng điện. Nó có thể được định hướng tùy ý. Để định hướng, hãy mô tả vectơ $I_0$ dưới dạng mũi tên thẳng đứng (Hình 4).

Điện áp trên điện trở hoạt động cùng pha với dòng điện. Do đó, vectơ $U_{0R}$, được biểu thị bằng điện áp này, trùng hướng với vectơ $I_0$. Mô-đun của nó là $U_{0R} = I_0R$. Sự dao động điện áp trên điện kháng cảm ứng xác định dao động dòng điện tại $\pi/2$ và vectơ tương ứng $U_{0L}$ phải là bề mặt của vectơ $I_0$ tại $\pi/2**$. Mô-đun của nó là $U_{0L} = I_0L\omega$. Và cuối cùng, vectơ $U_{0C}$, tương ứng với điện áp trên tụ điện,

*) Dòng điện thỏa mãn điều kiện này gọi là dòng điện gần như dừng. Ở tần số dòng điện công nghiệp là 50 $2\pi$, trên thực tế, nó luôn có thể được coi là gần như cố định.
**) Các pha сdwг dương trong Hình 4 tương ứng với sự quay của vectơ so với các phần của mũi tên. Tất nhiên, có thể đo được góc $\varphi$ theo hướng ngược lại.

⟦folio 55⟧

trễ pha so với vectơ $I_0$ một khoảng $\pi/2$ (xem Hình 4). Mô-đun của nó là $U_{0C} = I_0/C\omega$.

Để tìm tổng điện áp (xem phương trình (4)), bạn cần cộng ba vectơ: $U_{0R}$, $U_{0L}$ và $U_{0C}$. Đầu tiên, thật thuận tiện khi thêm các vectơ $U_{0L}$ và $U_{0C}$ (Hình 5). Mô đun của tổng này là $|U_{0L} + U_{0C}| = I_0\left(L\omega - \frac{1}{C\omega}\right)$,

nếu $L\omega > \frac{1}{C\omega}$. Đây chính xác là trường hợp được hiển thị trong Hình 5. Sau đó, bằng cách cộng vectơ $U_{0L} + U_{0C}$ với vectơ $U_{0R}$, chúng ta thu được vectơ $U_0$, mô tả sự dao động điện áp ở hai đầu mạch.

Tam giác ABD vuông góc. Theo định lý Pythagore

$$U_0^2 = U_{0R}^2 + \left(U_{0L} - U_{0C}\right)^2 = I_0^2 R^2 + I_0^2 \left(L\omega - \frac{1}{C\omega}\right)^2.$$

Do đó biên độ dòng điện

$$I_0 = \frac{U_0}{\sqrt{R^2 + \left(L\omega - \frac{1}{C\omega}\right)^2}} = \frac{U_0}{Z},$$

trong đó $Z = \sqrt{R^2 + \left(L\omega - \frac{1}{C\omega}\right)^2}$ là tổng điện trở của mạch. Độ lệch pha giữa dòng điện và điện áp bằng góc $\varphi$ giữa các vectơ $U_0$ và $I_0$. Từ tam giác ABD

$$tg\varphi = \frac{L\omega - \frac{1}{C\omega}}{R}.$$

Hình 5 cho thấy trường hợp dòng điện chạy sau điện áp cùng pha (ở $L\omega < \frac{1}{C\omega}$ dòng điện sẽ chạy trước điện áp cùng pha).

Công thức (17) và (18) mô tả đầy đủ các dao động cưỡng bức trong mạch dao động nối tiếp. Hãy xem một trường hợp đặc biệt làm ví dụ.

Cường độ dòng điện trong mạch dao động đạt giá trị cực đại $I_0 = \frac{U_0}{R}$ tại $L\omega = \frac{1}{C\omega}$, tức là khi tần số của điện áp đặt vào mạch bằng tần số dao động tự nhiên của mạch $\omega_0 = \frac{1}{\sqrt{LC}}$. Như người ta nói, sẽ có một sự cộng hưởng. Khi cộng hưởng, điện áp $u_L$ và $u_C$ có biên độ giống nhau nhưng dao động ngược pha nên chúng triệt tiêu lẫn nhau bất cứ lúc nào. Sơ đồ vectơ cho trường hợp cộng hưởng được hiển thị trong Hình 6. Độ dịch pha giữa dòng điện và điện áp đặt vào trở thành bằng không. Sự đốt cháy ở điện trở hoạt động hóa ra bằng điện áp ở hai đầu mạch: $u_R = iR = U_0\cos\omega t$. Sự cộng hưởng trong mạch dao động nối tiếp thường được gọi là cộng hưởng điện áp. Thực tế là trong mạch điện thực, điện trở cảm ứng và điện dung luôn lớn hơn điện trở tác dụng, và khi cộng hưởng, biên độ điện áp $U_{0L}$ và $U_{0C}$ hóa ra là biên độ lớn của điện áp đặt vào $U_0$.

⟦folio 56⟧

Năng lượng tiêu thụ
mạch dao động

Sử dụng sơ đồ pha, có thể dễ dàng chỉ ra rằng năng lượng mạch tiêu thụ chỉ được giải phóng ở điện trở hoạt động $R$.

Công suất trong mạch điện xoay chiều được xác định theo công thức

$$P = \frac{I_0 U_0}{2} \cos \varphi.$$ (19)

Từ tam giác $ABD$ trong Hình 5

$$U_{0R} = I_0 R = U_0 \cos \varphi.$$ (20)

Thay thế vào biểu thức (19) thay vì $U_0 \cos \varphi$ giá trị của nó từ đẳng thức (20), chúng ta thu được

$$P = \frac{I_0^2 R}{2} = I^2 R,$$ (21)

trong đó $I$ là giá trị hiệu dụng của dòng điện.

Lưu ý rằng khi cộng hưởng, khi biên độ dòng điện đạt cực đại thì mạch dao động tiêu thụ lượng năng lượng lớn nhất từ ​​bên ngoài. Các điều kiện tối ưu được tạo ra để truyền năng lượng từ nguồn sang hệ dao động.

Ví dụ tính toán
mục đích AC
sử dụng sơ đồ vector

Hãy xem xét hai bê tông bài toán.

Bài toán 1. Đến nguồn điện xoay chiều chính có điện áp $U = 120$ V (U là giá trị điện áp hiệu dụng) thông qua một cuộn cảm có điện cảm $L = 0,05$ g và điện trở hoạt động $R = 1$ từ hệ thống chiếu sáng, bảy căn hộ được kết nối (Hình 7).

Điện áp $U_1$ ở lối vào căn hộ là bao nhiêu nếu dòng điện tiêu thụ là $I = 2a$? Điện áp thay đổi với tần số $v = 50$ Hz. Độ tự cảm và điện dung của mạch điện trong căn hộ có thể được bảo toàn.

Cuộn cảm và mạng chiếu sáng chung cư mắc nối tiếp vào đường dây chính nên dòng điện như nhau

⟦folio 57⟧

trên tất cả các phần của chuỗi. Điện áp $U_1$ và điện áp $U_R$ tại điện trở hoạt động của cuộn cảm cùng pha với dòng điện $I$. Điện áp $U_L$ trên điện kháng cảm ứng của cuộn cảm xác định dòng điện ở $\pi/2$. Do đó, sơ đồ vectơ của mạch điện có dạng như hình 8. Theo định lý Pythagore
$$U^2 = U_L^2 + (U_R + U_1)^2 = I^2 \omega^2 L^2 + (IR + U_1)^2.$$
Từ đây
$$U_1 = -IR \pm \sqrt{U^2 - I^2 L^2 \omega^2},$$
ở đâu $\omega = 2\pi v$. Vì giá trị điện áp hiệu dụng luôn dương, tức là $U_1 > 0$, nên
$$U_1 = -IR + \sqrt{U^2 - I^2 L^2 4\pi^2 v^2} \approx 114\theta.$$
Bài 2. Ở tần số $\omega$ nào không có muối moka $i$ và điện áp $u$ của mạch điện như hình 9?
bài toán này xem xét một mạch điện gồm hai nhánh mắc song song. Một nhánh chứa điện trở chủ động và cảm ứng, nhánh kia chứa điện trở điện dung. Mạch này gọi là mạch dao động song song.
Chúng ta bắt đầu xây dựng sơ đồ vectơ với vectơ tương ứng với ứng dụng của điện áp, vì điện áp ở cả hai nhánh của mạch là như nhau. Hãy hướng vectơ $U_0$ theo chiều dọc lên trên (Hình 10). Dòng điện $i$ là tổng của dòng điện $i_1$ và $i_2$ (xem Hình 9). Dao động hiện tại $i_1$ lệch pha với dao động điện áp, vì phần trên của mạch chứa điện kháng cảm. Xoay vectơ $I_{01}$ so với vectơ $U_0$ theo góc $\varphi$ theo hướng âm. Theo công thức (17) và (18)
$$I_{01} = \frac{U_0}{\sqrt{R^2 + L^2 \omega^2}}$$ và $tg\varphi = \frac{L\omega}{R}$.
Vậy $i_2$ chạy qua tụ điện xác định điện áp pha ở $\pi/2$. Xoay vectơ tương ứng $I_{02}$ theo góc $\pi/2$ theo hướng dương. Mô hình của nó là $I_{02} = U_0 C\omega$. Theo điều kiện bài toán, dòng điện $i$ cùng pha với điện áp đặt vào, do đó, vectơ $I_0$ có hướng giống như vectơ $U_0$. Sơ đồ vectơ cuối cùng được trình bày trong Hình 10. Từ sơ đồ này cho thấy biên độ của dòng điện trong các nhánh truyền thông tương ứng.
$$I_{02} = I_{01} \sin \varphi.$$ (22)
Thay các giá trị $I_{01}$, $I_{02}$ và $\sin\varphi = \frac{tg\varphi}{\sqrt{1 + tg^2\varphi}} = \frac{L\omega}{\sqrt{R^2 + L^2 \omega^2}}$ vào đẳng thức (22), ta thu được
$$U_0 C\omega = \frac{U_0}{\sqrt{R^2 + L^2 \omega^2}} \frac{L\omega}{\sqrt{R^2 + L^2 \omega^2}}.$$
Từ đây
$$\omega = \sqrt{\frac{1}{LC} - \frac{R^2}{L^2}}.$$
Ở tần số này, dòng điện $i$ và điện áp $u$ dao động cùng pha.
Nếu điện trở hoạt động $R$ nhỏ thì
$$\frac{R^2}{L^2} \ll \frac{1}{LC}$$
(trong bộ điều khiển dao động thực tế, điều này thực tế đúng), thì
$$\omega = \frac{1}{\sqrt{LC}}$$
- Phần điện áp xoay chiều này trùng với tần số dao động tự nhiên của mạch điện.
