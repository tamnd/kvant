---
id: 2024-2-resheniya-zadach-m2770-m2773-f2777-f2780-d7fc678b
issue: kvant_2024_2
year: 2024
number: "2"
title: Lời giải bài toán M2770—M2773; F2777—F2780
rubric: zadachnik-kvanta
rubric_sub: Задачник «Кванта»
page_first: 24
page_last: 28
page_labels: 23-26
lang: vi
source: kvant_digital
content_sha256: 1863a41a741c299d18e6bab404983f616812fbe4fbee4abb3bd312ae2c998e9a
prompt_sha256: draft-1
translated_from: content/ru/2024/02/articles/04_resheniya-zadach-m2770-m2773-f2777-f2780-d7fc678b.md
source_content_sha256: 3aef7a961d4e790f79da12353180f8ee46d84dffaad3155adbd25c4129816315
translation_model: draft
translation_run: vi-draft-gaps-2026-11-01
translation_quality: draft
---

⟦folio none⟧

Lời giải bài toán M2770-M2773, F2777-F2780

M2770. Một lỗ hình tam giác được tạo trên một tờ giấy hình vuông có diện tích 1 (các đỉnh của lỗ không kéo dài đến mép của tờ giấy). Chứng minh rằng bạn có thể cắt một hình tam giác có diện tích 1/6 từ tờ giấy còn lại.

Chúng ta hãy lấy một điểm bên trong tam giác, chiếu các đỉnh của tam giác từ điểm đó lên đường viền của hình vuông ABCD và nối các hình chiếu với nhau. Bạn sẽ có được một hình tam giác mới chứa hình tam giác ban đầu. Nếu cùng lúc hai đỉnh của tam giác mới nằm cùng một cạnh của hình vuông thì hãy tăng cạnh này của tam giác sao cho trùng với cạnh của hình vuông (thao tác này có thể phải lặp lại cho hai cạnh của hình vuông). Chỉ cần chứng minh khẳng định cho tam giác cuối cùng là đủ. Lưu ý rằng bên trong một cạnh của hình vuông (trống cạnh AD) không có đỉnh nào của tam giác. Do đó, ta có thể giả sử các đỉnh K, L, M của tam giác lần lượt nằm trên các cạnh AB, BC, CD (xem hình), có lẽ một số chúng trùng với các đỉnh của hình vuông.

⟦folio 23⟧

NHÂN VIÊN VẤN ĐỀ

Một trong các đoạn BL, CL không nhỏ hơn 1 2. Giả sử, để xác định, đây là đoạn CL. Nếu trong trường hợp này CM t 2 3, thì $S_{LCM} t 1 6$. Nếu CM 2 3 thì $S_{ADM} t 1 6$. A.Yuran

M2771. Với N lớn nhất nào thì có số có N chữ số có đặc tính sau: trong ký hiệu thập phân của nó, trong số nhiều chữ số liên tiếp bất kỳ, một số chữ số xuất hiện đúng một lần?

Đáp số: 1023. Chúng tôi sẽ gọi những số có thuộc tính từ tình trạng tốt. Cấp. Chúng ta hãy chứng minh bằng quy nạp rằng một số tốt chứa không quá k chữ số khác nhau 1 d k d 10 có không quá $2^{k} 1$ chữ số. Từ đây, ước tính mà chúng ta cần sẽ tuân theo cho k 10. (Trong phần đánh giá sâu hơn, chúng ta sẽ giả định rằng số này có thể bắt đầu bằng bất kỳ chữ số nào, kể cả 0.) Cơ số (k 1) là hiển nhiên - chỉ một chữ số được sử dụng và không thể lặp lại. Hãy thực hiện bước cảm ứng. Cho 2 d k d 10 và X là một số tốt chứa tối đa k chữ số khác nhau. Theo điều kiện, một trong các số xuất hiện đúng một lần. Lưu ý rằng có những số tốt được viết ở bên trái và bên phải của chữ số này, mỗi số sử dụng không quá k 1 chữ số khác nhau, do đó, trong mỗi số đó (theo giả định quy nạp) không có quá $2^{k} 1 1$ chữ số và tổng cộng trong số X của chúng ta không quá $2^{k} 1 1 1 2^{k} 1 1 2^{k} 1$ chữ số, đó là yêu cầu bắt buộc. Ví dụ. Chúng ta cũng sẽ xây dựng một ví dụ về một số tốt chứa k chữ số khác nhau 2 d k d 10, có chính xác $2^{k} 1$ chữ số, bằng quy nạp. Cơ sở (k 2): số 101 là phù hợp. Bước cảm ứng. Giả sử 3 d k d 10 và X là một số tốt có k 1 chữ số khác nhau và dấu $2^{k} 1 1$. Hãy lấy số a, không xuất hiện trong số này và cộng số X vào bên trái và bên phải, chúng ta được XaX. Số kết quả có $2^{k} 1$ ký tự và điều đó là tốt: xét cho cùng, bất kỳ phần nào của số đó từ một số chữ số liên tiếp đều bao gồm chữ số duy nhất a trong số hoặc là một phần của số tốt X. A. Glebov

"QUANTA"

⟦column⟧

M2772. Trong các ô trắng của bàn cờ 100 và 100 có 100 quân tượng, trong đó có quân trắng và quân đen. Họ có thể thực hiện các bước di chuyển theo bất kỳ thứ tự nào và bắt giữ các quân tượng có màu đối diện. Số nước đi nhỏ nhất được biết là đủ để để lại một quân tượng trên bàn cờ là bao nhiêu?

Đáp số: 197 nước đi. Thuật toán. Chúng tôi sẽ thực hiện mọi động tác để quân tượng của cả hai màu vẫn ở trên bàn cờ, miễn là có ít nhất hai quân tượng. Nếu có thể thực hiện một cuộc bắt giữ tiết kiệm (hãy gọi đó là một nước đi trong đó quân tượng trong một nước đi đánh bại quân tượng khác màu đứng trên cùng đường chéo với nó), thì chúng tôi sẽ thực hiện. Nếu không, chúng ta sẽ thực hiện việc bắt giữ không kinh tế trong hai nước đi: chúng ta sẽ chọn hai quân tượng có màu sắc khác nhau và xem xét con đường mà quân tượng đầu tiên có thể đi đến quân thứ hai trong hai nước đi (luôn có một con đường như vậy). Nếu có nhiều quân trên con đường này, chúng ta sẽ tìm trong số đó hai quân tượng khác màu gần nhau nhất và để một quân đánh bại quân kia trong hai nước đi. Ban đầu, tất cả quân tượng đứng trên 99 đường chéo màu trắng song song với đường chéo chính màu trắng. Sau đó, một trong số họ có ít nhất hai giám mục. Hãy gọi hai vị giám mục này là đặc biệt. Nếu các quân tượng đặc biệt có màu sắc khác nhau, thì có thể bắt giữ một cách kinh tế ngay lần di chuyển đầu tiên dọc theo đường chéo này; hãy làm điều đó. Hãy để những con voi đặc biệt này có cùng màu, nói là màu trắng. Sau đó, trong quá trình bắt giữ, chúng ta sẽ đánh các quân tượng da trắng bằng các quân tượng da đen. Sau khi vị giám mục đặc biệt đầu tiên được bổ nhiệm, hạn chế này sẽ được loại bỏ. Lưu ý rằng bạn có thể rút tiền tiết kiệm ngay sau đó. Vì tổng cộng có 99 lần bắt và ít nhất một trong số đó là tiết kiệm nên không cần nhiều hơn 2 99 1 197 nước đi. Cấp. Hãy đặt 50 quân tượng ở dòng dưới và trên của bàn cờ, màu sắc của quân tượng không quan trọng. Hãy xem xét tất cả 199 đường chéo màu trắng theo cả hai hướng (đặc biệt, chúng tôi cũng coi các ô vuông màu trắng ở góc của bảng là các đường chéo). Trong trường hợp này, tất cả 199 đường chéo màu trắng ban đầu sẽ có tượng. Trong khi di chuyển, số đường chéo chứa ít nhất một quân tượng có thể

⟦folio 24⟧

---
running_head:
folio:
---

giảm không quá 1. Thật vậy, đường chéo duy nhất có thể “biến mất” là đường chéo mà quân tượng rời đi để bắt một quân tượng khác. Cuối cùng, khi chỉ còn lại một tượng thì sẽ có 2 đường chéo bị chiếm giữ. Tổng cộng trong khoảng cách ban đầu này sẽ có ít nhất 199 – 2 = 197 bước di chuyển.

A. Gribalko

M2773. Vòng tròn $\omega$ nằm bên trong vòng tròn $\Omega$ và chạm vào bên trong nó tại điểm $T$ (hình 1). Hãy để $XY$ –

Hình 1
dây cung thay đổi của đường tròn $\Omega$ tiếp tuyến với $\omega$. Gọi $X'$ và $Y'$ biểu thị trung điểm của các cung $TY$ và $TX$ không chứa các điểm $X$ và $Y$ của cung tương ứng. Chứng minh rằng mọi đường thẳng $X'Y'$ đều đi qua một điểm cố định.

Chúng ta sẽ chứng minh các đường thẳng $X'Y'$ cắt đường kính $TS$ của đường tròn $\Omega$ tại một điểm cố định $K$ (hình 2).

Đặt $L$ là điểm tiếp tuyến giữa $XY$ và $\omega$. Sau đó, như đã biết, $TL$ cắt $\Omega$ lần thứ hai ở giữa $Z$ của cung $XY$ (ví dụ: điều này xuất phát từ việc xem xét việc chuẩn bị với tâm $T$, chuyển $\omega$ sang $\Omega$: với sự chuẩn bị này $XY$ sẽ tiếp tuyến với $\Omega$, đi qua $Z$ nên tiếp tuyến này song song với $XY$. Do đó, $TZ$ là phân giác của góc $XTY$, nghĩa là $XX', YY'$ và $TZ$ cắt nhau tại một điểm $I$ – tâm của đường tròn nội tiếp tam giác $XYT$. $X'Y'$ cắt nhau $TZ$ tại điểm $R$. Từ sự bằng nhau của các góc $\angle Y'X'X = \angle TX'Y'$ và $\angle X'Y'Y = \angle TY'X'$ chúng ta hiểu rằng các tam giác $X'Y'I$ và $X'Y'T$ đối xứng với $X'Y'$. $TI = 2TR$ và $TZ \perp X'Y'$, nghĩa là $\angle TRK = \angle TZS = 90^\circ$.

Chỉ cần chứng minh rằng $TK/TS$ đã được xây dựng là đủ. Nhưng $TK/TS = TR/TZ = TI/(2TZ)$. Khi đó chỉ cần hiểu rằng $TI/TZ$ được xây dựng hoặc $ZI/ZT$ được xây dựng là đủ. Theo bổ đề nhánh $ZX = ZI$. Vì vậy, chỉ cần hiểu rằng $ZX/ZT = const$ là đủ.

Nhưng từ việc chuẩn bị với tâm $T$, nó dẫn đến $TL/TZ = r/R$ (trong đó $r$ và $R$ lần lượt là bán kính của $\omega$ và $\Omega$), và từ sự giống nhau của $ZXL \sim ZTX$, nó dẫn đến $ZL \cdot ZT = ZX^2$, tiết lộ $\frac{R-r}{R} ZT \cdot ZT = ZX^2$. Chúng ta thấy rằng mối quan hệ $ZX/ZT = \sqrt{\frac{R-r}{R}}$ được xây dựng và điều này hoàn thành lời giải bài toán.

Lưu ý rằng cách xây dựng này có nhiều bất biến thú vị. Ví dụ, từ những xem xét cuối cùng và định lý sin, dễ dàng phát hiện ra rằng bán kính của đường tròn ($XZL$) đã được xây dựng. Bài toán với sản phẩm như vậy đã được đưa ra tại Thế vận hội toàn Nga năm 2001 (tác giả - T. Emelnova).

P. Kozhevnikov, F. Petrov

F2777.1 Một con sóc ngồi trên cành cây ném một quả hạch vào một con chuột nằm trên một mặt phẳng nằm ngang. Sau một thời gian, chúng tôi đeo đai ốc vào

1 Tác giả lời giải bài toán F2777–F2780 – V. Plis.

⟦folio 25⟧

---
running_head:
folio:
---

bề mặt của bàn chân chuột. Hướng “từ con sóc đến con chuột” tạo thành một góc β với phương thẳng đứng. Tốc độ ban đầu của đai ốc là nhỏ nhất trong cực đại. Vector vận tốc ban đầu của đai ốc tạo với đường chân trời một góc α bằng bao nhiêu? Sức cản của không khí là không đáng kể.

Phạm vi bay theo phương ngang của một quả bóng được ném với tốc độ $v_0$ từ độ cao $h$ một góc α so với phương ngang (hình 1) bằng

Hình 1
$s = x(T) = v_0 \cos \alpha \cdot T$. Tốc độ $v$ tại thời điểm rơi không phụ thuộc vào góc α và bằng $v = \sqrt{v_0^2 + 2gh}$. Điều này tuân theo định luật bảo toàn cơ năng toàn phần. Hơn nữa, trong quá trình quả bóng bay, nó thay đổi theo thời gian theo định luật $\vec{v}(t) = \vec{v}_0 + \vec{g}t$. Vào thời điểm rơi $\vec{v}(T) = \vec{v}_0 + \vec{g}T$.

Hãy chuyển sang tam giác tốc độ (hình 2) và tính diện tích của nó, bằng một nửa tích của đáy và chiều cao, hoặc một nửa tích của chiều dài các cạnh và sin của góc giữa chúng:

$$\frac{1}{2} g T v_0 \cos \alpha = \frac{1}{2} v_0 v \sin \delta,$$

trong đó $\delta$ là góc quay của vectơ vận tốc trong suốt chuyến bay. Từ đây chúng ta có được phạm vi bay ngang:

$$s = \frac{1}{g} v_0 v \sin \delta.$$

Trong biểu thức này, chỉ có góc $\delta$ phụ thuộc vào α. Do đó, phạm vi tối đa đạt được khi vectơ vận tốc quay một góc $\delta = \frac{\pi}{2}$ trong suốt chuyến bay. Khoảng này bằng

$$s = \frac{v_0 \sqrt{v_0^2 + 2gh}}{g}.$$

Do đó, tốc độ tối thiểu mà một quả bóng nên được ném từ độ cao $h$ đến khoảng cách ngang tối đa $s$, và do đó đạt khoảng cách tối đa $l = \sqrt{s^2 + h^2}$ tính từ điểm xuất phát, là

$$v_0 \min = \sqrt{g(l - h)}.$$

Với cú ném như vậy

$$tg \alpha = \frac{v_0 \min}{\sqrt{v_0^2 + 2gh}} = \sqrt{\frac{1 - \frac{h}{l}}{1 + \frac{h}{l}}} = \sqrt{\frac{1 - \cos \beta}{1 + \cos \beta}} = tg \frac{\beta}{2},$$

tức là $\alpha = \frac{\beta}{2}$. Góc ném bằng một nửa góc mà hướng về mục tiêu tạo với phương thẳng đứng.

F2778. Một cái vòng được làm từ một sợi dây cứng, đồng nhất có chiều dài L. Trong thí nghiệm đầu tiên, cái vòng được đặt trên một bề mặt gồ ghề nằm ngang và, bằng một cú va chạm, nó sẽ chuyển động về phía trước với một tốc độ nằm ngang nhất định. Trong quá trình đóng băng, độ dịch chuyển của mỗi vòng bằng s. Trong thí nghiệm thứ hai (xem hìnhnok), cái vòng được đặt trên cùng một bề mặt, giữ nó trong một mặt phẳng thẳng đứng và bằng một cú đánh, nó sẽ chuyển động về phía trước; tại thời điểm ban đầu, mọi thứ trong vòng chuyển động với cùng tốc độ theo phương ngang như trong thí nghiệm đầu tiên. Được biết, trong quá trình trượt, gia tốc góc không đổi và bằng $\frac{\Delta \omega}{\Delta t} = \frac{a}{R}$, trong đó a là mô đun của chuỗi khối lượng có gia tốc của vòng. Chúng ta sẽ hoàn thành vòng quay trong hệ thống chuỗi khối bao nhiêu vòng vào thời điểm khi

⟦folio 26⟧

---
running_head:
folio:
---

chuyển động của vòng sẽ có chất lượng mà không cần
kêu gọi? Hệ số ma sát
trượt vòng theo phương ngang
bề mặt giống nhau ở tất cả các điểm của điều này
các bề mặt.

Trong thử nghiệm đầu tiên $s = \frac{v_0^2}{2\mu g}$, trong đó $v_0$ là giá trị ban đầu
tốc độ của vòng, $\mu$ – hệ số
ma sát. Trong thí nghiệm thứ hai, trong quá trình chuyển động
tốc độ thay đổi xung vòng
bằng tổng các ngoại lực (trọng lực,
phản lực hỗ trợ và ma sát):

$$\frac{\Delta(m\vec{v})}{\Delta t} = m\vec{g} + \vec{N} + \vec{F}_{\text{tp}}.$$

Hãy chuyển sang hình chiếu lực và gia tốc
theo hướng dọc và ngang
leniya:

$$N = mg, F_{\text{tp}} = \mu N = \mu mg,$$

$$\frac{\Delta(mv)}{\Delta t} = -\mu mg, \quad \frac{\Delta v}{\Delta t} = -\mu g.$$

Do đó, có tính đến đẳng thức $R \frac{\Delta\omega}{\Delta t} = \mu g$ thì nó tuân theo

$$\frac{\Delta v}{\Delta t} + R \frac{\Delta\omega}{\Delta t} = 0.$$

Trong quá trình lăn bị trượt
tổng $v + \omega R$ không đổi, bằng
về giá trị ban đầu của nó $v_0$. Ngay bây giờ
chuyển sang lăn không trượt
$v = \omega R = 0,5v_0$. Điều này sẽ xảy ra trong thời gian $t = \frac{0,5v_0}{\mu g}$ sau khi bắt đầu. Đến lúc này
góc quay vòng

$$\varphi = \frac{1}{2} \left( \frac{\Delta\omega}{\Delta t} \right) t^2,$$

tốc độ

$$n = \frac{\varphi}{2\pi} = \frac{v_0^2}{16\pi\mu g R} = \frac{s}{4L}.$$

F2779. Trong một hình trụ thẳng đứng dưới
được chứa bởi một piston di chuyển nhẹ
một số ý tưởng đơn nguyên tử
khí ga. Khí đang dần nóng lên. TRONG
Trong quá trình giãn nở, khí chứa công
mu $A = 10U_0$, trong đó $U_0$ – nội năng
 khí ở trạng thái ban đầu. Hãy tìm

tỷ lệ trung bình đạt được
nguyên tử khí với các ngăn xếp trên mỗi
đơn vị diện tích trên một đơn vị thời gian trong
trạng thái ban đầu và cuối cùng. Tre-
nie sitmaite không đáng kể đâu nhé.

Số lần tác động trung bình trên mỗi
đơn vị diện tích trên một đơn vị thời gian
tỷ lệ thuận với nồng độ của phân tử (hoặc
tỷ lệ nghịch với thể tích của hình trụ) và tốc độ chuyển động nhiệt trung bình của các phân tử, tỷ lệ thuận với
căn bậc hai của nhiệt độ tuyệt đối:

$$z = \frac{1}{4} nv_{\text{cp}} = \frac{1}{4} n \sqrt{\frac{3kT}{m}} \sim n\sqrt{T} \sim \frac{1}{V}\sqrt{T}.$$

Thái độ yêu cầu

$$\alpha = \frac{z_0}{z_1} = \frac{v_1}{v_0} \sqrt{\frac{T_0}{T_1}}.$$

Trong quá trình hình ảnh

$$A = p_0 \left( V_1 - V_0 \right) = vR \left( T_1 - T_0 \right), v = \frac{p_0V_0}{RT_0},$$

hơn nữa

$$\frac{p_0V_1}{p_0V_0} = \frac{T_1}{T_0} = \frac{V_1}{V_0} = 1 + \frac{A}{p_0V_0},$$

$$\alpha = \sqrt{1 + \frac{3}{2} \frac{A}{U_0}} = 4.$$

F2780. Trong quá trình gia nhiệt, khí
heli với lượng $v = 1$ mol mol
nhiệt lượng cuối cùng của khí C tính bằng nhiệt độ tuyệt đối $T$ theo định luật
$C = R \frac{T}{T_1}$, trong đó $R = 8,31$ J/(mol K) – uni-
hằng số khí ngược, $T_1 = 400$ K –
nhiệt độ ban đầu. Hãy tìm một công việc
mu của khí đến thời điểm thể tích của khí
sẽ trở nên tối thiểu.

Sự phụ thuộc $p(V)$ được thể hiện một cách tồn tại
trên hình 1. Theo điều kiện, trong một khu phố nhỏ
trạng thái 2 nhiệt mol trong quá trình đốt nóng heli bằng

$$C = \frac{3}{2} R,$$ xảy ra ở vùng lân cận này
gia nhiệt đẳng tích đến nhiệt độ
