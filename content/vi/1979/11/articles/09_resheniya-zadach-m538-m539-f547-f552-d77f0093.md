---
id: 1979-11-resheniya-zadach-m538-m539-f547-f552-d77f0093
issue: kvant_1979_11
year: 1979
number: "11"
title: Lời giải bài toán M538, M539; F547—F552
rubric: zadachnik-kvanta
rubric_sub: Задачник «Кванта»
page_first: 29
page_last: 37
page_labels: 27, 28, 30, 31, 32, 33, 34, 35
tag: PFXN
lang: vi
source: kvant_digital
extraction: vision
content_sha256: adf67ede86bc87a70cf2505cde99ba06251d4c56c5e698f7ed94222a07cd7119
prompt_sha256: draft-1
translated_from: content/ru/1979/11/articles/09_resheniya-zadach-m538-m539-f547-f552-d77f0093.md
source_content_sha256: 8646554f75a09329e85d2e335d1c6734c7838a9679bad1882b7beec67bd15ac0
translation_model: draft
translation_run: vi-draft-2026-10-31
translation_quality: draft
---

⟦folio 27⟧

Lời giải bài toán
M538, M539; F547—F552

M538. Tập hợp các số tự nhiên là tập rút gọn của hai tập con rời rạc $f(1), f(2), \dots, f(n), \dots$}, $\{g(1), g(2), \dots, g(n), \dots\}$, $\exists f(1) < f(2) < \dots < f(n) < \dots, u g(n) = f(f(n)) + 1$ với mọi $n \ge 1$. Xác định $f(240)$.

Chúng ta hãy biểu thị tập hợp $f(n)$ và $\{g(n)\}$ bằng $F$ và $G$ (theo quy ước $F \cap G = \emptyset$ và $F \cup G = N$). Bắt đầu với các số tự nhiên đầu tiên 1, 2, 3, ..., thật dễ dàng để tìm ra một cách nhất quán tập hợp nào $F$ hoặc $G$ nên gán số tự nhiên tiếp theo và số $n$ tương ứng với trong tập hợp của nó: rõ ràng là $1 = f(1)$, do đó $2 = f(f(1)) + 1 = g(1)$; xa hơn, $3 = f(2), 4 = f(3), 5 = f(f(2)) + 1 = g(2)$, ... (Bảng 1). Trong trường hợp này, chúng ta nhận được điều kiện $g(n) = f(f(n)) + 1$ - chúng ta đặt $g(n)$ tiếp theo ngay sau khi $f(f(n))$ được đặt.

Do đó, $f(n)$ và $g(n)$ được xác định duy nhất và về nguyên tắc, chúng ta có thể giải bài toán chỉ bằng cách đưa bảng của chúng ta đến hàng thứ 240. Tuy nhiên, nó nhàm chán và không thú vị. Bạn có thể tiết kiệm thời gian bằng cách chú ý đến các mẫu hình mới nổi:

1°. chênh lệch $f(n+1) - f(n)$ luôn bằng 1 hoặc 2 và

$$f(n+1) - f(n) = \begin{cases} 1, \text{ если } n \in G, \\ 2, \text{ если } n \in F \end{cases}$$

(nếu $n = f(k)$ thì $f(n)+1 \neq g(k)$);

2°. $g(n) = f(n)+n$ cho bất kỳ $n$ nào. Thật vậy, trong số $g(n)$ số 1, 2, ..., $f(f(n)), g(n)$ có $f(n)$ số $f(1), f(2), \dots, f(f(n))$ từ $F$ và $n$ số $g(1), g(2), \dots, g(n)$ từ $G$. Vì vậy, $g(n) = f(n)+n$.

Thuộc tính 1° và 2° cho chúng ta cơ hội tạo bảng “tăng tốc” 2. Teler vẫn sử dụng thuộc tính 1° để di chuyển từ 234 đến 240 (bảng 3). Nó thậm chí còn đơn giản hơn, như độc giả A. Balinsky của chúng tôi đã đồng ý, để thực hiện thêm bước sớm hơn (sử dụng đẳng thức $f(f(n)) = f(n)+n-1$):

$$f(57) = 90+2 \quad (56 \in F), \quad f(92) = 92+56 = 148,$$

$$f(148) = 148+91,$$

$$f(239) = 239+147 = 386, \quad f(240) = 386+2 = 388 \quad (239 \in F).$$

Vì vậy, đáp số cho câu hỏi cụ thể bài toán M538 nhận được: $f(240)=388$. Tuy nhiên, hóa ra ở đây chúng ta có thể tiến xa hơn nhiều - tìm các công thức đơn giản thay thế ngay lập tức cho đáp số cho bất kỳ $n$ nào:

$$f(n) = \left[ \frac{1+\sqrt{5}}{2} n \right], \quad g(n) = \left[ \frac{3+\sqrt{5}}{2} n \right]$$

(ở đây $[x]$ là phần nguyên của $x$). Một số độc giả của chúng tôi đã tìm ra các công thức (*), nhưng không phải ai cũng chứng minh được chúng một cách chính xác. Việc chứng minh đại số về nội dung rất phức tạp (mặc dù không khó lắm); Cùng nhau, chúng ta sẽ không trình bày một bức tranh rõ ràng mà từ đó cả hai công thức (*) và quá trình xây dựng các chuỗi $f(n)$, $g(n)$ sẽ rõ ràng. Nhưng trước tiên, hãy giải thích “bằng ngón tay” nơi số vô tỉ $\frac{\sqrt{5}+1}{2}$ xuất hiện trong bài toán này.

Nhìn vào Bảng 1, điều tự nhiên là giả định rằng chuỗi $f(n)$ phát triển gần như một hàm tuyến tính của $n$: $f(n) \approx \gamma n$. Sau đó, đối với $n$ lớn thì phải có $g(n) \approx f(f(n)) \approx \gamma (\gamma n) = \gamma^2 n$. Nhưng theo 2°, $g(n) = f(n)+n$, thì $\gamma^2 n \approx \gamma n+n$, và điều này chỉ có thể xảy ra với $\gamma^2 = \gamma+1$, do đó (nếu $\gamma > 0$) $\gamma = (\sqrt{5}+1)/2$. Từ những gì tiếp theo, sẽ rõ ràng rằng tập hợp $F$ và $G$ của các số tự nhiên $n$ đầu tiên của chúng ta chứa khoảng $n/\gamma$ và $n/\gamma^2$ các số tương ứng (như người ta nói, chúng có sự hoàn chỉnh $1/\gamma$ và $1/\gamma^2$).

⟦folio 28⟧

Số γ và những “họ hàng” gần gũi của nó

$$\frac{1}{\gamma} = \gamma - 1 = \frac{(\sqrt{5} - 1)}{2}, \quad \gamma^2 = \gamma + 1 = \frac{(\sqrt{5} + 3)}{2}, \quad 1/\gamma^2 = \frac{(3 - \sqrt{5})}{2}$$

phát sinh trong rất nhiều vấn đề *), đặc biệt, trong nghiên cứu các số Fibonacci 1, 2, 3, 5, 8, 13, ..., $\Phi_{n+1} = \Phi_{n-1} + \Phi_n$, ... (bất cứ điều gì Pitts đều biết rằng những số này nhỏ hơn 1 so với các số $n$ trong Bảng 2; hãy nghĩ tại sao), trong lý thuyết số, trong hình học. Đặc biệt, có thể dễ dàng kiểm tra rằng khi cắt một hình vuông từ một đường trượt tuyết thẳng với tỷ lệ chiều dài “vàng”, cạnh γ vẫn giữ nguyên của một đường trượt tuyết thẳng giống với hình ban đầu - theo đó trong Hình 1, trong đó việc cắt như vậy được thực hiện hai lần, các điểm O, K và M nằm trên cùng một đường thẳng. Tính chất này của số γ sẽ hữu ích cho chúng ta.

Bây giờ chúng ta hãy trình bày một cách đơn giản để xây dựng các số $f(n)$ và $g(n)$. Trên giấy ca rô như trên mặt phẳng tọa độ (Hình 2), chúng ta vẽ một đường thẳng $l$, được xác định bởi phương trình $y = \gamma x$ - với độ dốc “vàng” $\gamma = \frac{(\sqrt{5} + 1)}{2}$. (Làm thế nào để thực hiện việc này bằng cách sử dụng la bàn và thước kẻ?) Sắp xếp tất cả các ô “màu đỏ” (Hình 2) mà đường thẳng $l$ giao nhau, bắt đầu từ ô 0 chứa gốc $O$. Vì γ là trò chơi nên $l$ không đi qua các nút lưới, tức là nó đi vào ô tiếp theo, giao với đường $y = n$ hoặc đường $x = n$ ($n \in \mathbb{Z}$). Lưu ý rằng số ô $\{(x; y) : [x] = i, [y] = j\}$ bằng $i+j$ (tại sao?). Chúng tôi khẳng định rằng nếu số ô là $m$ thì $m = f(n)$ hoặc $m = g(n)$. Nói cách khác, nếu chúng ta sắp xếp các đoạn của tia tọa độ $Ox$ và $Oy$ theo thứ tự thì trên số đoạn $n$ của trục $x$ nằm số ô $g(n)$, và bên phải số đoạn $n$ của trục $y$ nằm số ô $f(n)$. Hãy xem nó trong Bảng 1 và Hình 2!

Bằng chứng cho thấy các số $f(n)$ và $g(n)$ được xây dựng theo cách này, sử dụng giấy ca rô, trên thực tế là những gì chúng ta cần, bao gồm việc kiểm tra xem các số trong ô có thỏa mãn tất cả các thuộc tính của chuỗi $f$ và $g$ từ điều kiện bài toán hay không. Việc chúng ta thu được sự phân chia toàn bộ chuỗi tự nhiên $N$ thành hai chuỗi tăng dần rời rạc là rõ ràng. Vẫn còn phải kiểm tra xem $g(k) = f(f(k)) + 1$. Hãy “mở rộng” cách đánh số ô màu đỏ cho toàn bộ mặt phẳng: mỗi ô của mặt phẳng $\{(x; y) : [x] = i, [y] = j\}$ sẽ được gán một số $i+j$ (số màu xanh trong Hình 2); trong trường hợp này, số lượng phân đoạn trên ong bắp cày trùng với số lượng ô chứa chúng.

Đối với $n$ tùy ý, chúng ta đánh dấu các điểm $K(n/\gamma; n)$ và $M(n/\gamma; n)$ giao điểm của đường $l$ với các đường $y = n$ và $x = n$ (Hình 3). Sau đó, ô bên trái chứa điểm $K$ được đánh số $f(n)$ và ô dưới cùng chứa điểm $M$ được đánh số $g(n)$. Chúng ta hãy lưu ý các hình chiếu $K'$ và $M'$ của các điểm $K$ và $M$ lên trục $y$. Lưu ý rằng $K'KM' = 45^\circ$ (nhớ Hình 1) nên các ô chứa điểm $K$ và $M'$ được đánh số $f(n)$. Do đó, tại điểm $M$ có đường $f(f(n))$ đi vào số ô $g(n)$, tức là $f(f(n)) + 1 = g(n)$.

*) N. N. Vorobyov “Số Fibonacci” (M., “Nauka”, 1978); G. S. M. Coxeter “Giới thiệu về hình học” (Moscow, “Nauka”, 1966), ch. “Tỷ lệ vàng và phyllotaxis”; A. D. Bendukdze “Phần vàng” («Kvant», 1973, số 8, trang 22).

⟦folio 30⟧

Lưu ý rằng bổ đề này cũng đúng với mọi điểm $K$ trong không gian: nếu điểm $K$ nằm phía trên mặt phẳng vẽ 5 với khoảng cách $z$, tức là có tọa độ $(x; y; z)$, thì $2z^2$ sẽ được cộng vào cả hai vế của (1).

Bây giờ chúng ta hãy chứng minh khẳng định $2^\circ$. Theo $1^\circ$, đỉnh $A_1, B_1$ Và $C_1$ song song - đỉnh thứ tư của đường thẳng/libs $PBA_1C$, $PCB_1A$ Và $PAC_1B$ (Hình 6) - nằm cách xa $\sqrt{2r^2-p^2}$ từ điểm $K$. Sử dụng nó một lần nữa $1^\circ$: đỉnh thứ tư $D$ trực tiếp/libnik $A_1CB_1D$, cái mà $|A_1K|^2 = |B_1K|^2 = 2r^2 - p^2$, $|CK|^2 = r^2$, là từ điểm $K$ ở một khoảng cách

$$\sqrt{2(2r^2-p^2)}-r^2 = \sqrt{3r^2-2p^2}.$$

Vì vậy, chúng ta đã chứng minh rằng đỉnh $D$ của hình bình hành nằm trên một hình cầu có tâm $K$ và bán kính $\sqrt{3r^2-2p^2}$. Tuy nhiên, như trong bất kỳ bài toán nào để tìm một tập hợp điểm, cần phải chứng minh điều ngược lại: rằng bất kỳ điểm nào của hình cầu này đều là đỉnh của một hình bình hành nhất định thỏa mãn các điều kiện của bài toán. Tôi biết rất nhiều về điều này từ những độc giả đã gửi cho chúng tôi lời giải bài toán M539. Trong khi đó, ở đây chúng ta đưa ra một chứng minh rõ ràng cho mệnh đề ngược lại, nó không đơn giản như trong trường hợp mặt phẳng (ở đó, cho điểm $P$ và $D$, thật dễ dàng, bằng cách dựng một đường tròn có đường kính $[PD]$, tìm đỉnh $A$ và sử dụng $1^\circ$ để chứng minh rằng đỉnh thứ tư $C$ là thẳng $PADC$ nằm trên đường tròn đã cho). Có lẽ điều này là do trong không gian bài toán có nhiều quyền tự do hơn trong việc lựa chọn hình song song mong muốn: đối với các điểm $P$ và $D$ nhất định, có cả một nhóm chúng. (Tất nhiên, chúng tôi chỉ cần xây dựng một trong số chúng.)

Để chứng minh điều ngược lại, một số độc giả đã sử dụng phương pháp tọa độ, một số khác đã sử dụng thông báo liên tục. Ở đây chúng ta cũng sẽ bắt đầu với các quan sát hình học đã được thực hiện khi cố gắng giải bài toán này:

$$3^\circ. \text{Квадраты радиусов четырех сфера с центром } K, \text{ на коморых лежат точки } P; A, B \text{ и } C; A_1, B_1 \text{ и } C_1, D, \text{ образуют арифметическую прогрессию:}$$
$$p^2, r^2, 2r^2-p^2, 3r^2-2p^2.$$

Mẫu tương tự tồn tại trong phiên bản phẳng (mặc dù chỉ có ba thuật ngữ trong chương trình). Về vấn đề này, chúng tôi chỉ ra logic sau của tuyên bố được chứng minh:

Nếu có nhiều đường tròn đồng tâm, các bậc hai của chúng tạo thành một cấp số cộng,

⟦folio 31⟧

Cơm. 8.

gressio, cắt một số đường tròn γ thì các dây chung (với γ) của các đường tròn này song song và cách nhau một khoảng như nhau (Hình 7).

Chúng ta sẽ bắt gặp một phiên bản không gian của tuyên bố này, trong đó thay vì hình tròn thì có hình cầu, cùng với dây cung thì có hình tròn, v.v. (nó thu được từ hình 7 phẳng bằng cách quay quanh trục đối xứng).

4°. Dễ dàng chứng minh rằng các mặt phẳng ABC và A₁B₁C₁ cắt đường chéo PD của hình song song tại các điểm lớn nhất M và M₁, chia nó thành ba đoạn giống hệt nhau: |PM| = |MM| = |M₁D| - và là giao điểm của các đường trung tuyến của tam giác ABC và A₁B₁C₁ (Hình 8). Trung điểm Q của đường chéo PD đóng vai trò là tâm đối xứng của hình bình hành.

5°. Để có được hình không gian 6 và 8, chúng tôi cũng chỉ ra các sự kiện sau:

Hình chiếu Q' lên mặt phẳng ABC có tâm Q của hình song song bên phải rơi vào tâm của đường tròn ngoại tiếp tam giác ABC; hình chiếu P' của đỉnh P của hình bình hành trùng với trực tâm của tam giác ABC (giao điểm của các đường cao). Từ đây và từ 4° dễ dàng suy ra định lý Euler: M∈[Q'P'] và |MQ'| : |MP'| = 2 (Hình 9) *). Theorel đã sẵn sàng cho sự kết thúc của lời giải bài toán M539.

Hãy |KP| = p và |DK| = √3r² - 2p²; Q là trung điểm của đoạn [PD], γ và γ₁ là các đường tròn có một hình cầu có đường kính [PD] cắt các hình cầu có bán kính r và √2r² - p² có tâm K (xem Hình 8). Theo 4°, các mặt phẳng của các vòng tròn này chia [PD] thành ba phần bằng nhau: [PM], [MM₁], [M₁D]. Lấy bất kỳ điểm A∈γ nào và ký hiệu là A₁ là điểm A₁∈γ₁ đối xứng với nó đối với Q.

Rõ ràng là PAD = PA₁D = 90°. Vẽ các mặt phẳng đi qua các điểm P và D vuông góc với các đoạn [PA] || [DA₁]. Điểm giao nhau của các mặt phẳng này với các đường tròn γ và γ₁ cho chúng ta các đỉnh của đường thẳng song song cần thiết (xem Hình 8): trên thực tế, trung điểm E và E₁ của các đoạn AD và A₁P (Hình 10, 11) nằm trong mặt phẳng của các đường tròn γ và γ₁ và đóng vai trò là tâm của các phần của hình cầu bằng các mặt phẳng được xây dựng; do đó, AC₁DB₁ và A₁CPB thẳng hàng.

N. Vasiliev

*) Đúng, cách chứng minh như vậy chỉ phù hợp với tam giác nhọn, vì chỉ tam giác đó mới có thể dùng làm tiết diện (ABC) cho hình bình hành vuông. Hãy xem xét liệu chứng minh này có thể được làm lại cho ΔABC tù hay không.

⟦folio 32⟧

F547. Các tế bào quang học gồm các khối hình cầu plasma phát sáng bay chậm đều cho đến khi dừng lại có dạng sọc dài l. Chiều rộng dải tối đa d ≤ l. Khoảng cách giữa plasma và thấu kính máy ảnh là L, tiêu cự của thấu kính là F. Thời gian “phơi sáng” tối thiểu cần thiết để một hình ảnh xuất hiện trên bề mặt ảnh là t. Xác định gia tốc của các khối. Ống kính máy ảnh vẫn mở cho đến khi cục máu đông dừng hẳn.

F548. Sự nông phản ứng có khối lượng m chúng ta mô tả một khối lượng chết dọc theo một đường tròn thẳng đứng bán kính R với tốc độ tuyến tính không đổi v. Lực yêu cầu thực hiện bao nhiêu công khi di chuyển vận chuyển từ vị trí thấp nhất đến vị trí cao nhất? Hệ số chênh lệch giữa đường nông và đường bằng μ.

Cơm. 12.

Chiều rộng tối đa của dải rõ ràng được xác định bởi đường kính D của bó. Nếu Γ = |$\frac{F}{F-L}$| là độ phóng đại của máy ảnh thì D = $\frac{d}{Γ}$. Để tránh xuất hiện trên phim, vận tốc v của chùm cần phải sao cho trong thời gian t, chùm sẽ di chuyển một quãng đường không quá D. Nếu thời gian trôi qua từ lúc ảnh xuất hiện cho đến khi chùm ảnh dừng hẳn thì tại thời điểm ảnh xuất hiện, tốc độ của chùm là |v| = |a| t và thỏa mãn điều kiện

$$\frac{D}{|a| t} = \frac{d}{\Gamma |a| t} = \tau.$$ (1)

Cho đến khi cục máu đông dừng hẳn, nó sẽ che phủ khoảng cách

$$L = \frac{l}{\Gamma} = \frac{|a| t^2}{2}.$$ (2)

Từ phương trình (1) và (2) ta tìm được gia tốc của bó:

$$|\vec{a}| = \frac{d^2}{2\Gamma l\tau^2} = \frac{d^2}{2l\tau^2} \left| \frac{F-L}{F} \right|.$$

V. Seretsevich

Chúng ta hãy xem xét hai vị trí đối xứng của xe đẩy, trong đó vectơ bán kính của các điểm đặt xe tạo cùng một góc α với phương thẳng đứng (Hình 12). $\vec{N}_1$ và $\vec{N}_2$ là phản lực của mặt đường tại các vị trí này, $\vec{F}_{T1}$ và $\vec{F}_{T2}$ là lực kéo, $\vec{F}_{Tp1}$ và $\vec{F}_{Tp2}$ là lực ma sát. Vì xe trượt dọc đường nên $F_{Tp1} = \mu N_1$ và $F_{Tp2} = \mu N_2$ (ở đây là $N_1 = |\vec{N}_1|$, $F_{Tp1} = |\vec{F}_{Tp1}|$, v.v.).

Xe chuyển động tròn đều với vận tốc v; do đó, tổng hình chiếu của tất cả các lực tác dụng lên xe lên phương của bán kính bằng $mv^2/R$, tức là (xem Hình 12)

$$N_1 - mg \cos \alpha = mv^2/R, \quad N_2 + mg \cos \alpha = mv^2/R.$$

Từ đây

$$N_1 = (mv^2/R) + mg \cos \alpha, \quad N_2 = (mv^2/R) - mg \cos \alpha$$

Và

$$F_{Tp1} = \mu [(mv^2/R) + mg \cos \alpha], \quad F_{Tp2} = \mu [(mv^2/R) - mg \cos \alpha].$$

Khi vectơ bán kính quay một góc nhỏ Δα, tức là khi hình chiếu của xe nhỏ tại Δl = R Δα với ma sát mạnh $\vec{F}_{Tp1}$ và $\vec{F}_{Tp2}$, công $\Delta A_1 = F_{Tp1}R \Delta \alpha$ và $\Delta A_2 = F_{Tp2}R \Delta \alpha$ được thực hiện.

Tổng công của các lực $\vec{F}_{Tp1}$ và $\vec{F}_{Tp2}$ trong diện tích nhỏ Δl bằng $\Delta A = (F_{Tp1} + F_{Tp2})R \Delta \alpha = 2\mu mv^2 \Delta \alpha.$

Giá trị của ΔA không phụ thuộc vào α. Điều này có nghĩa là khi vectơ bán kính của xe quay một góc nhỏ Δα từ hai điểm đối xứng bất kỳ (tương tự I và 2), phép hợp nhất thực hiện công như nhau, tỷ lệ với Δα.

Việc di chuyển xe từ điểm dưới cùng của đường lên đỉnh tương ứng với sự thay đổi của α bằng π/2, nghĩa là ΣΔα = π/2. Do đó, công do lực ma sát thực hiện với hình chiếu như vậy bằng

$$A = \sum \Delta A = 2\mu mv^2 \Delta \alpha = \pi\mu mv^2.$$

O. Savigan

⟦folio 33⟧

F549. Hai quả bóng có khối lượng $m_1$ và $m_2$ được nối với nhau bằng một lò xo có độ cứng $k$; lò xo được đặt đúng vị trí và không bị biến dạng. Các quả bóng đồng thời có tốc độ $\vec{v}_1$ và $\vec{v}_2$, như trong Hình 13, với $|\vec{v}_1| = |\vec{v}_2| = v$.
Tìm độ cao cực đại của hệ và độ biến dạng cực đại của lò xo.

Cơm. 13.

Khối tâm của hệ (cm) sẽ chuyển động giống như một vật có khối lượng $M = m_1 + m_2$, được ném nghiêng một góc so với đường chân trời với xung lực ban đầu $\vec{p}_0$ bằng tổng các xung lực ban đầu của các quả bóng:

$$\vec{p}_0 = M \vec{u}_0 = m_1 \vec{v}_1 + m_2 \vec{v}_2$$

($\vec{u}_0$ là tốc độ ban đầu của tâm). Hình chiếu của xung $\vec{p}_0$ lên trục tung $OY$ bằng $m_2 v$, do đó hình chiếu của vận tốc ban đầu c. m. trên trục $OY$ bằng $u_y = m_2 v / M$. Điều này có nghĩa là độ cao cực đại của khối tâm của hệ bằng

$$H = \frac{u_y^2}{2g} = \frac{v^2}{2g} \left( \frac{m_2}{m_1 + m_2} \right)^2.$$

Bây giờ hãy tìm độ biến dạng lớn nhất của lò xo. Rõ ràng, tại thời điểm lò xo biến dạng lớn nhất, trong một hệ tọa độ chuyển động với vận tốc khối tâm của hệ thì các quả cầu chỉ có thể lăn quanh khối tâm. Điều này có nghĩa là năng lượng của hệ có thể được biểu diễn dưới dạng tổng năng lượng $W_C$ của toàn bộ hệ và năng lượng bên trong, bằng tổng thế năng biến dạng của lò xo $kx^2 / 2$ (x là lượng biến dạng) và động năng quay của các quả bóng $W_K = 1 / 2 \left[ m_1 (\omega l_1)^2 + m_2 (\omega l_2)^2 \right]$, trong đó $\omega$ là vận tốc góc quay và $l_1$ và $l_2$ là khoảng cách từ các quả bóng tương ứng đến tâm wt.

Chúng ta biểu thị chiều dài của lò xo bằng $l$. Sau đó $l_1 = lm_2 / M$, $l_2 = lm_1 / M$, vậy

$$W_K = \frac{1}{2} \omega^2 l^2 \left( \frac{m_1 m_2^2}{M^2} + \frac{m_2 m_1^2}{M^2} \right) = \frac{1}{2} \omega^2 l^2 \frac{m_1 m_2}{M}.$$

Hãy tìm $\omega$. Từ định luật bảo toàn động lượng góc suy ra rằng

$$m_1 (\omega l_1) l_1 + m_2 (\omega l_2) l_2 = m_1 \omega_0 l_{10}^2 + m_2 \omega_0 l_{20}^2,$$

trong đó $l_{10}$ và $l_{20}$ là khoảng cách ban đầu từ quả bóng đến tâm khối, $\omega_0$ là vận tốc góc ban đầu. Hiển nhiên, nếu chiều dài ban đầu của lò xo là $l_0$ thì

$$l_{10} = l_0 m_2 / M, \quad l_{20} = l_0 m_1 / M.$$

Poznym chúng ta có thể viết

$$\left[ m_1 \left( \frac{m_2}{M} \right)^2 + m_2 \left( \frac{m_1}{M} \right)^2 \right] \omega l^2 = \left[ m_1 \left( \frac{m_2}{M} \right)^2 + m_2 \left( \frac{m_1}{M} \right)^2 \right] \omega_0 l_0^2.$$

Do đó $\omega = \omega_0 (l_0 / l)^2$. Để tìm $\omega_0$ cần tìm vận tốc ban đầu của các quả bóng $\vec{v}_1$ và $\vec{v}_2$ ở tâm hệ khối lượng. Vì tốc độ của khối tâm tại thời điểm ban đầu bằng $\vec{u}_0 = \left( m_1 \vec{v}_1 + m_2 \vec{v}_2 \right) / M$ nên tốc độ của các quả bóng trong hệ khối tâm tương ứng với

$$\vec{v}_1 = \vec{v}_1 - \vec{u}_0 = \frac{m_2}{M} \left( \vec{v}_1 - \vec{v}_2 \right),$$

$$\vec{v}_2 = \vec{v}_2 - \vec{u}_0 = \frac{m_1}{M} \left( \vec{v}_2 - \vec{v}_1 \right).$$

Ví dụ, vận tốc góc $\omega_0$ của các quả bóng bằng hình chiếu của vận tốc $\vec{v}_0$ lên trục $OY$ chia cho $l_{20}$, tức là

$$\omega_0 = \frac{v m_1 / M}{l_{20}} = \frac{v}{l_0}.$$

⟦folio 34⟧

Như vậy,

$$W_K = \frac{1}{2} \omega_0^2 l_0^2 \frac{m_1 m_2}{M} = \frac{v^2}{2} \frac{m_1 m_2}{M} = \frac{m_1 m_2}{2M} v^2.$$

Bây giờ chúng ta hãy sử dụng định luật bảo toàn năng lượng. Tổng năng lượng của hệ là

$$\frac{m_1 v_1^2}{2} + \frac{m_2 v_2^2}{2} = \frac{M v^2}{2}.$$

Bởi vì

$$\frac{M v^2}{2} = W_C + \frac{k x^2}{2} + W_K.$$

Nhưng, theo định luật bảo toàn năng lượng, đối với toàn bộ hệ thống

$$W_C = W_{co} = \frac{M u_0^2}{2} = \frac{M}{2} \left( \frac{m_1 \vec{v}_1 + m_2 \vec{v}_2}{M} \right)^2.$$

Vì các vectơ $m_1 \vec{v}_1$ và $m_2 \vec{v}_2$ đã được phân phối lại cho nhau,

$$\left( m_1 \vec{v}_1 + m_2 \vec{v}_2 \right)^2 = m_1^2 v_1^2 + m_2^2 v_2^2 = \left( m_1^2 + m_2^2 \right) v^2.$$

Bởi vì

$$W_C = \frac{m_1^2 + m_2^2}{2M} v^2,$$

và định luật bảo toàn năng lượng có thể viết lại thành

$$\frac{M v^2}{2} = \frac{m_1^2 + m_2^2}{2M} v^2 + \frac{k x^2}{2} + \frac{m_1 m_2 v^2}{2M}.$$

Từ đây

$$x = v \sqrt{\frac{m_1 m_2}{k M}}.$$

I. Slobodetsky

Khoảng cách $h$ từ tâm vòng đệm nhôm đến đỉnh hình nón được xác định theo phương trình $\frac{h + a}{h} = \frac{R}{r}$ (Hình 14) và bằng $h = a \frac{r}{R - r} = 3$ (cm).

Khi được làm nóng, vòng đệm nhôm nở ra nhiều hơn diện tích hình nón mà nó tiếp xúc ($\beta_2 > \beta_1$) nên nó trượt xuống. Vòng đệm sắt "nêm" vào hình nón ($\beta_3 < \beta_1$) và trộn lẫn với phần hình nón giữ nó. Khi đun nóng, góc ở đỉnh hình nón không thay đổi. Khoảng cách mới $h'$ từ tâm vòng đệm nhôm đến đỉnh hình nón được xác định theo phương trình $\frac{h'}{h} = \frac{r'}{r}$ và bằng

$$h' = h \frac{r (1 + \beta_2 \Delta t)}{r} = h (1 + \beta_2 \Delta t).$$

Khi được làm nóng, khoảng cách giữa các vòng đệm tăng lên

$$\Delta a = \left( H' - h' \right) - a = a \beta_1 \Delta t - h \left( \beta_2 - \beta_1 \right) \Delta t \approx 0,16 \text{ (мм)}.$$

G. Komkin

⟦folio 35⟧

F551. Một tải trọng khối lượng m được treo vào hai lò xo có độ cứng $k_1$ và $k_2$ nhờ một sợi dây và một khối (Hình 15). Tìm chu kỳ dao động nhỏ của tải. Nimtb và khối sitam không trọng lượng.

Khi khối được trộn với tải trọng có giá trị $x$ thì tổng biến dạng của lò xo bằng $2x$, tức là
$$x_1 + x_2 = 2x,$$
trong đó $x_1, x_2$ lần lượt là biến dạng của lò xo có độ cứng $k_1$ và độ cứng $k_2$. Các lực đàn hồi phát sinh trong các lò xo là như nhau - mỗi lực đều có giá trị tuyệt đối bằng lực $\vec{T}$ của lực căng chỉ. Vì vậy, $x_1 = T/k_1, x_2 = T/k_2$ và
$$2x = \frac{T}{k_1} + \frac{T}{k_2}$$
(ở đây $T = |\vec{T}|$). Từ đây là
$$T = 2 \frac{k_1 k_2}{k_1 + k_2} x.$$
Lực $\vec{F}$ tác dụng lên khối có tải có giá trị tuyệt đối bằng $2T$, tức là
$$F = \frac{4k_1 k_2}{k_1 + k_2} x$$
(ở đây $F = |\vec{F}|$). Như vậy, dao động của một khối có tải trọng có thể được coi là dao động của khối lượng $m$ trên một lò xo có độ cứng $k' = \frac{4k_1 k_2}{k_1 + k_2}$. Chu kỳ dao động như vậy bằng
$$T = 2\pi \sqrt{\frac{m}{k'}} = \pi \sqrt{\frac{m(k_1 + k_2)}{k_1 k_2}}.$$

F552. Đặc tính điện áp-ampe của đèn neon được thể hiện trong hình 16. Ở giá trị nào $R$ điện trở của điện trở được đưa vào mạch như hình 17, thì đèn neon (n.l.) sẽ không bị kẹt sau khi phím $K$ được đóng?

Khi đóng chìa khóa, tụ điện bắt đầu tích điện. Khi điện áp trên tụ điện và do đó trên đèn bằng 110 V thì đèn sẽ sáng. Kể từ thời điểm này, dòng điện chạy qua đèn sẽ tăng lên, điện áp trên đèn và do đó trên tụ điện sẽ giảm - tụ điện sẽ tích điện. Nếu trong quá trình sạc, tụ điện nhỏ hơn 80 V, đèn sẽ tắt - dòng điện trong mạch nhỏ hơn dòng định mức chạy qua đèn khi sạc ~80 V (xem Hình 16). Vì vậy, để đèn không bị tắt thì điện áp trên tụ không được trong quá trình

Cơm. 16. Hình 17.

phóng điện giảm xuống dưới 80 V. Trong trường hợp giới hạn $U_C = 80$ V, điện áp trên điện trở là 40 V, dòng điện chạy qua điện trở bằng dòng điện chạy qua đèn (1 µA), và do đó điện trở của điện trở là $R = 40$ ohm. Với giá trị điện trở thấp hơn $U_C < 80$ V thì đèn không sáng.

I. Slovodetsky
