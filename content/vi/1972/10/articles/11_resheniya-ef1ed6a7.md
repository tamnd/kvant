---
id: 1972-10-resheniya-ef1ed6a7
issue: kvant_1972_10
year: 1972
number: "10"
title: Lời giải bài toán M126—M128; F142—F147
rubric: zadachnik-kvanta
rubric_sub: Задачник «Кванта»
page_first: 42
page_last: 48
page_labels: 40-46
tag: UKWM
lang: vi
source: kvant_digital
extraction: vision
content_sha256: c62dcda45ccf2c31e1d2963da66a2c688e9a40989222dfd97f76697defa35f70
prompt_sha256: draft-1
translated_from: content/ru/1972/10/articles/11_resheniya-ef1ed6a7.md
source_content_sha256: 36cbecfceb4ff4339a0aa0afa3676eebff850ffb0987faadca261c2bff90e4f4
translation_model: draft
translation_run: vi-draft-2026-10-31
translation_quality: draft
---

⟦folio 40⟧

GIẢI PHÁP

Trong số này, chúng tôi xuất bản lời giải bài toán M126—M128

M126

Một đa giác ngoại tiếp một hình tròn có bán kính $r$ bằng cách nào đó được cắt thành các hình tam giác. Chứng minh rằng tổng bán kính các đường tròn nội tiếp của các tam giác này lớn hơn $r$.

Đặt $S$ là diện tích của một đa giác nhất định, $p$ là diện tích chu vi của nó; $S_i$, $p_i$, $r_i$ - tương ứng là diện tích, đạo hàm và bán kính của các đường tròn nội tiếp của các hình tam giác mà nó được cắt vào ($i = 1, 2, ..., n$). Khi đó $S = pr$, $S_i = p_i r_i$ và $p > p_i$ cho tất cả $i$ (không khó để chứng minh rằng chu vi của một đa giác lớn hơn chu vi của bất kỳ đa giác lồi nào mà nó chứa). Đó là lý do tại sao

$$r_1 + r_2 + \cdots + r_n = \frac{S_1}{p_1} + \frac{S_2}{p_2} + \cdots + \frac{S_n}{p_n} > \frac{S_1}{p} + \frac{S_2}{p} + \cdots + \frac{S_n}{p} = \frac{S}{p} = r.$$

Sự đẳng thức cuối cùng được minh họa trong Hình 1.

M127

Đối với mỗi số tự nhiên $n$ chúng ta biểu thị bằng $s(n)$ tổng các chữ số của nó (theo ký hiệu thập phân). Hãy gọi một số tự nhiên $m$ là đặc biệt nếu nó không thể được biểu diễn dưới dạng $m = n + s(n)$, trong đó $n$ là một số tự nhiên nào đó. (Ví dụ: số 117 không đặc biệt vì $117 = 108 + s(108) = 108 + 9$, nhưng số 121, như bạn có thể dễ dàng thấy, là đặc biệt.) Có đúng là chỉ có hữu hạn số đặc biệt không?

Đáp số: Câu này sai; Có vô số số đặc biệt.

Ý tưởng đằng sau lời giải tự nhiên nhất như sau. Hãy xem xét tất cả các số $n$ từ 1 đến một số $N$. Trong số đó có một số lượng nhất định $R_N$ như vậy $n$ mà $n + s(n) > N$. Do đó, các số từ 1 đến $N$ được chứng nhận là không có nhiều hơn $N - R_N$ số được biểu thị là $n + s(n)$, nghĩa là, ít nhất $R_N$ số là đặc biệt (ở đây chúng tôi thậm chí không tính đến việc một số số có thể được biểu thị là $n + s(n)$ theo nhiều cách). Vẫn cần đảm bảo rằng bằng cách chọn $N$ tương ứng, chúng ta có thể thu được góc lớn hơn $R_N$.

Ý tưởng này được tìm thấy trong các quyết định của V. Bikmashev và A. Weintrob từ Moscow, A. Grigoriyan từ Baku, I. Majulis từ Riga và một số độc giả khác. Để đưa nó đến mức đầy đủ lời giải, chúng tôi chứng minh rằng trong số các số $n$ từ 1 đến $N = 10^{10^k} + k$ có ​​nhiều hơn đáng kể $10^k$ sao cho $n + s(n) > N$. Thật vậy, nếu $n < N$ và $n \geq N_1 = (10^{10^k} - 1) 10^k = 9 \dots 90 \dots 0 (10^k$ là số chín và $k$ là số 0), thì $n + s(n) \geq (10^{10^k} + k - 10^k) + 9 \cdot 10^k > N$,

và số lượng các số $n$ sao cho $N_1 \leq n \leq N$ bằng $N - N_1 + 1 = 10^k + 1$.

⟦folio 41⟧

Một lời giải khác (nó được thực hiện chính xác nhất trong các tác phẩm của A. Pechkovsky từ Moscow và L. Puets từ Dnepropetrovsk) - chỉ ra một phương pháp cho phép bạn xây dựng một chuỗi số đặc biệt cụ thể. Đây là một trình tự như vậy:

$$m_1 = 9 + 11 = 20,$$
$$m_2 = 20 + 101 = 121,$$
$$m_3 = 121 + 1001 = 1122,$$

ở đâu $m_k = m_{k-1} + 10^k + 1$.

Hãy chứng minh bằng quy nạp rằng tất cả các số này đều đặc biệt. Giả sử điều này đúng với $m_{k-1}$ ($k \ge 3$), nhưng không đúng với $m_k$: $m_k = n + s(n)$.

Trước khi sử dụng giả định này, chúng ta hãy chứng minh rằng khai triển thập phân của số $m_k$ trông như thế này:

$$m_k = 10^k + a_{k-1} 10^{k-1} + \dots + a_0,$$

trong đó số là $a_{k-1} \neq 0$, tức là $11 \cdot 10^{k-1} < m_k < 2 \cdot 10^k$. Bất đẳng thức bên trái rất indo, và bất đẳng thức bên phải có thể được chứng minh bằng quy nạp: $m_k = m_{k-1} + 10^k + 1 < 2 \cdot 10^k - 1 + 1 = 12 \cdot 10^{k-1} + 1 < 2 \cdot 10^k$.

Bây giờ chúng ta có thể chứng minh rằng ký hiệu thập phân của số $n$ cũng bắt đầu bằng một: $n = 10^k + b_{k-1} \cdot 10^{k-1} + \dots + b_1 \cdot 10 + b_0$, tức là $10^k < n < 2 \cdot 10^k$. Ở đây bất đẳng thức bên phải rất indo, còn bất đẳng thức bên trái được chứng minh bằng sự mâu thuẫn: nếu $n < 10^k$ thì $s(n) < 9k$ và $n + s(n) < 10^k + 9k < 10^k + 10^{k-1} = 11 \cdot 10^{k-1} < m_k (9k < 10^{k-1}$ cho $k \ge 3$).

Chúng ta hãy biểu thị số $n - 10^k$ (số $n$ với chữ số đầu tiên bằng một bị loại bỏ) bằng $n^*$. Sau đó, rất indo, $s (n^*) = s(n) - 1$ và do đó

$$n^* + s (n^*) = n - 10^k + s(n) - 1 = m_k - 10^k - 1 = m_{k-1}.$$

Như vậy hóa ra số $m_{k-1}$ không có gì đặc biệt. Sự mâu thuẫn với giả định chứng tỏ tính đúng đắn của phép chuyển đổi quy nạp từ $k - 1$ sang $k$. Không khó để khẳng định rằng các số $m_1$ và $m_2$ là đặc biệt.

**M128**

Tìm tỉ số cạnh của một tam giác mà một trong các đường trung tuyến của nó bị đường tròn nội tiếp chia thành ba phần bằng nhau.

Gọi $BK$ là đường trung bình của tam giác $ABC$ - đường tròn nội tiếp được chia thành các đoạn bằng nhau $BM = MN = NK = x$, $AB = c$, $BC = a$, $CA = b$ và $T$ - điểm tiếp tuyến của đường tròn nội tiếp trên cạnh $BC$ (Hình 2).

Hình 2.

Hai trận đấu ABC sau đây là cần thiết nhất:

$$a + c - b = 2BT,$$
$$2a^2 + 2c^2 - b^2 = 4BK^2$$

(cái đầu tiên được suy ra từ các đẳng thức $BT + CT = a$, $BT - CT = c - b$; cái thứ hai dễ chứng minh bằng cách hoàn thiện tam giác để tạo thành hình bình hành $ABCD$). Từ đẳng thức thứ hai ta tìm được

$$2a^2 + 2c^2 - b^2 = 36x^2. \quad (1)$$

Vì, vì các điểm $B$ và $K$, rất indo, cách đều tâm của đường tròn nội tiếp, nên $BC = KC$, từ đó

$$b = 2a. \quad (3)$$

Thay (3) vào (1) và (2), ta tìm được

$$c^2 - a^2 = 18x^2, \quad (c - a)^2 = 8x^2.$$

Từ những đẳng thức này ta thu được (rõ ràng là $c - a \neq 0$, $x \neq 0$):

$$\frac{c + a}{c - a} = \frac{9}{4},$$

từ đâu $\frac{c}{a} = \frac{13}{5}$.

Đáp số: $a:b:c = 5:10:13$.

Không khó để kiểm tra rằng trong một tam giác có tỷ số cạnh như vậy, đường trung tuyến của cạnh $b$ thực sự sẽ bị đường tròn nội tiếp chia thành ba phần bằng nhau (khi kiểm tra, sẽ thuận tiện hơn khi sử dụng các công thức tương tự đã được sử dụng ở trên).

Đúng lời giải của một số bài toán M121 - M128 bổ sung: V. Ashaskiy (Moscow) M126; V. Astmankovi (Borisov BSSR) M124; V. Birch (Gorky) M122 - M123; A. Blyukhin (Kiselevsk, vùng Kemerovo) M123; A. Bikmatsev (Moscow) M126 - M128; A. Boedanov (Glazov, Cộng hòa xã hội chủ nghĩa Xô viết tự trị Udmurt) M128; A. Botsarov (Nikolaev) M126 - M128; L. Braetskin (Frunze) M126; A. Brutmer (Chisinau) M128; O. Burlakov (Tashkent) M128; A. Weintrob (Moscow) M126 - M128; T. Galkina (Kuibyshev) M126; L. Genriinovich (Tashkent) M126, M128; A. Gordienko (làng Poltachenko, Lãnh thổ Krasnoarsk) M122, M126; A. Grigoryan (Baku) M126; V. Greenman (Moscow) M124; A. Demidov (Moscow) M124; V. Drobimko (Kherson) M126; V. Evdokimov (Yaroslavl) M123; A. Edrenkin (Moscow) M126; M. Zhukov (Baku) M128; A. Zhumadildaev (Alma-Ata) M122 - M124; V. Zarubin (khu định cư Letniy, khu vực Moscow riêng biệt) M126; V. Zablochiky (Donetsk) M128; E. Zeiman (Orrey, Liên Xô Moldavia) M126; T. Zlamkus (Sovetsk, vùng Kaliningrad), M128; I. Nenatyev (s. Sarmanovo, Cộng hòa xã hội chủ nghĩa Xô viết tự trị Tatar) M128; M. Ilartsionov (Voronezh) M121 - M124, M126, M128; S. Ioannidi (Tbilis) M128; M. Kaul (Frunze) M121, M122, M124; A. Kvasov (Moscow) M122 - M124, M126; A. Kislenev (Moscow) M122; Yu. Kisin (Staraya Russa) M123, M124, M126; V. Kleimenov (Ulan-Ude) M126; V. Kolosov (Kyiv)

⟦folio 42⟧

Trong số này, chúng tôi xuất bản lời giải bài toán F142—F147

F142

Một quả cầu thép treo trên một sợi dây có chiều dài l bị lệch làm cho sợi dây chuyển sang vị trí nằm ngang rồi thả ra. Tại thời điểm sợi dây tạo một góc α=30° so với phương thẳng đứng thì quả bóng chạm vào một tấm thép đứng yên (Hình 3). Quả bóng sẽ bay lên đến độ cao bao nhiêu sau khi chạm vào tấm, nếu tác động có thể được coi là đàn hồi tuyệt đối?

Gọi vận tốc của quả bóng tại thời điểm nó chạm vào tấm bằng v. Vận tốc này có hướng vuông góc với sợi dây. Vì tác động của quả bóng là đàn hồi tuyệt đối và do đó tức thời nên khi chạm vào quả bóng, nó hoạt động như thể nó tự do, không dính vào sợi dây. Do đó, tốc độ của quả bóng khi va chạm chỉ thay đổi theo hướng sao cho góc phản xạ của quả bóng so với mặt đĩa bằng góc tới. Điều này có nghĩa là sau khi chạm vào tấm, nó chuyển động với vận tốc v₁=v cos 2α, vuông góc với sợi dây. Năng lượng của quả bóng ngay sau khi va chạm bằng $\frac{mv_1^2}{2}$; khi quả bóng lên tới độ cao h thì nó bằng mgh. (Thông thường, tổng động năng của quả bóng W = $\frac{mv^2}{2} = \frac{mv_1^2}{2} + \frac{mv_2^2}{2}$ sau khi va chạm sẽ chuyển thành năng lượng dao động của quả bóng dọc theo sợi dây hoặc cuối cùng là trong dây Tello. Độ lớn của tổn thất này là $\frac{mv_2^2}{2}$.

⟦folio 43⟧

Theo định luật bảo toàn năng lượng

$$\frac{mv_1^2}{2} = mgh \quad \text{или} \quad \frac{v^2 \cos^2 2\alpha}{2} = gh.$$

Bây giờ chúng ta hãy tìm tốc độ $v$ của quả bóng tại thời điểm nó va chạm với tấm đĩa. Ban đầu quả bóng ở độ cao $H = l \cos \alpha$ so với đĩa. Độ biến thiên thế năng của quả bóng khi chuyển động từ vị trí ban đầu đến va chạm với tấm bằng động năng mà quả bóng thu được:

$$\frac{mv^2}{2} = mgl \cos \alpha.$$

Từ đây

$$v^2 = 2gl \cos \alpha.$$

Kể từ đây,

$$h = \frac{v^2 \cos^2 2\alpha}{2g} = l \cos \alpha \cos^2 2\alpha = \frac{\sqrt{3}}{8} l.$$

F143

Máy bay hạ cánh trên boong tàu sân bay với tốc độ 100 km/h. Sau khi nhắm vào dây phanh, máy bay chạy được 50 m cho đến khi dừng hẳn. Xác định tình trạng quá tải nếu hệ số đàn hồi của dây không thay đổi khi nó bị giãn.

Khi máy bay phanh lại, một lực $F = kx$ tác dụng lên nó từ phía của sợi dây, trong đó $x$ là độ giãn của dây, $k$ là hệ số đàn hồi của nó. Lực này tăng lên khi sợi dây căng ra. Gia tốc cũng tăng

$$a = \frac{F}{M} = \frac{k}{M} x,$$

chúng tôi báo cáo lực $F$ của máy bay (M là khối lượng của máy bay).

Nhưng gia tốc $a$ không chỉ di chuyển máy bay mà còn cả phi công, được giữ bằng dây đai trên ghế. Gia tốc này được truyền cho phi công bởi lực $T$ tác động lên anh ta từ dây đai. Nếu khối lượng của phi công là $m$ thì

$$T = ma = \frac{mk}{M} x.$$

Lực này đạt cực đại ở $x = L = 50$ m,

$$T_{\text{max}} = \frac{mkL}{M}.$$

(1)

Biểu thức của $T$ bao gồm hệ số đàn hồi của dây. Hãy tìm anh ấy.

Động năng của máy bay tại thời điểm hạ cánh rõ ràng bằng công thực hiện bởi lực $F$. Lực này thay đổi theo quãng đường $x$ mà máy bay di chuyển khi được tàu sân bay bắn ra. Hãy vẽ đồ thị về sự phụ thuộc của $F$ vào $x$ (Hình 4). Rõ ràng, công do lực $F$ thực hiện trên đường đi $L$ bằng diện tích tam giác dưới đồ thị $F$ so với $x$, tức là $A = \frac{1}{2}kL \cdot L = \frac{kL^2}{2}$. Vì vậy, $\frac{kL^2}{2} = \frac{Mv^2}{2}$. Do đó $k = \frac{Mv^2}{L^2}$.

Thay biểu thức của $k$ vào công thức (1), ta thu được

$$T_{\text{max}} = m \frac{v^2}{L} = mg \frac{v^2}{Lg} \approx 1,5mg.$$

Từ các phía của ghế và dây đai, các lực vuông góc lẫn nhau tác dụng lên người phi công: phản lực pháp tuyến của ghế $N$ và lực căng của dây đai $T$. Các lực tác dụng bằng nhau này có giá trị tuyệt đối bằng trọng lượng của phi công $P$ (trọng lượng là lực mà phi công tác động lên ghế và dây đai):

$$R = \sqrt{T_{\text{max}}^2 + (mg)^2} \approx 1,8 \text{ mg}.$$

Điều này có nghĩa là trọng lượng của bè gấp 1,8 lần trọng lượng của nó trong điều kiện bình thường.

F144

Tỷ lệ của hình tam giác với sàn là bao nhiêu để nó đứng vững như trong Hình 5? Chiều dài sợi dây giữ thanh bằng chiều dài của thanh.

⟦folio 44⟧

Vì thanh ở trạng thái cân bằng nên tổng hình chiếu của tất cả các lực tác dụng lên nó theo phương thẳng đứng và phương ngang phải bằng 0. Các lực tác dụng lên thanh được thể hiện trên Hình 5. Điều này có nghĩa là
$$F_{ТР} - T \sin \alpha = 0,$$
$$N + T \cos \alpha - mg = 0.$$

Chúng ta cũng hãy viết điều kiện để thanh không quay quanh điểm C. Để làm được điều này, tổng mô men của tất cả các lực đối với điểm C phải bằng 0:

$$Tl \sin \alpha - mg \frac{l}{2} \sin \alpha = 0.$$

Từ phương trình (2) suy ra $T = \frac{1}{2} mg$. Chúng ta hãy viết lại, có tính đến điều này, phương trình (1). Chúng ta cũng biết rằng ở hệ số ma sát thấp nhất, khi thanh vẫn có thể đạt được trạng thái cân bằng, $F_{ТР} = kN$:

$$kN - \frac{1}{2} mg \sin \alpha = 0,$$
$$N + \frac{1}{2} mg \cos \alpha - mg = 0.$$

Từ đây
$$kN = \frac{1}{2} mg \sin \alpha,$$
$$N = mg \left(1 - \frac{1}{2} \cos \alpha\right).$$

Kể từ đây,
$$k = \frac{\sin \alpha}{2 - \cos \alpha} = \frac{\sqrt{3}}{3}.$$

F145

Một loại khí lý tưởng đầu tiên chuyển từ trạng thái 1 ($P_1, V_1, T_1$) sang trạng thái 2 ($P_2, V_2, T_2$). Sau đó, từ trạng thái 2, khí thích ứng từ từ (không cung cấp cho bắp chân) và chuyển sang trạng thái 3 ($P_3, V_3, T_3$). Được biết, trong quá trình chuyển tiếp 2→3, khí thực hiện công bằng với lượng công truyền cho khí trong quá trình chuyển tiếp 1→2. Hãy chứng minh rằng $T_3 = T_1$. Vẽ các tiến trình 1→2 và 2→3 trên mặt phẳng VT.

Vì trong quá trình $1 \rightarrow 2$ $V = V_1 =$ const, khí không sinh công và độ biến thiên nội năng của khí $\Delta W_1$ bằng lượng nhiệt $Q$ truyền cho khí:

$$Q = \Delta W_1.$$

Quá trình 2→3 thích ứng ($Q = 0$), có nghĩa là khí hoạt động nhờ năng lượng bên trong. Do đó, công $A$ do khí thực hiện bằng độ biến thiên nội năng của nó:

$$A = \Delta W_2.$$

So sánh (1) và (2), ta thấy
$$\Delta W_1 = \Delta W_2.$$

Nhưng nội năng của chất khí tỉ lệ thuận với nhiệt độ tuyệt đối của nó. Điều này có nghĩa là trong suốt quá trình 2→3 và quá trình 1→2, nhiệt độ khí thay đổi như nhau. Vì vậy, $T_1 = T_3$.

Đồ thị quá trình được hiển thị trong Hình 6. Vì trong quá trình 1→2, nội năng của khí tăng lên nên $T_2 > T_1$. Vì trong quá trình 2→3 khí hoạt động nên $V_3 > V_1$.

Rõ ràng, đáp số của chúng tôi chỉ hợp lệ nếu $V_1 \rightarrow 2 =$ là const.

F146

Có một pin với e. d.s. $E = 100$ $\theta$ và điện trở trong $r = 2$ $\Omega$. Khi tải bạn cần có điện áp $U = 20$ $\theta$ và khi điện trở tải $R$ thay đổi từ 50 $\Omega$ thành 100 $\Omega$ thì điện áp trên nó không được thay đổi quá 2%. Hãy nghĩ ra một mạch điện đơn giản để cấp nguồn cho tải và tính toán các thông số của mạch này.

Một trong những mạch đơn giản nhất là kết nối tuần tự giữa điện trở $R$ tải, điện trở $R_1$ và nguồn (Hình 7). Trong trường hợp này, nếu điện trở tải là 50 $\Omega$ thì để điện áp trên tải bằng 20 $\Omega$ (tức là 1/5 emf của nguồn $E$), tổng điện trở nguồn và điện trở $R_1$ phải là 200 $\Omega$. Nhưng trong trường hợp này, với điện trở tải 100 $\Omega$, điện áp trên nó sẽ là

$$U = E \frac{R}{R_1 + R + r} = \frac{100}{3} \theta \approx 33,3\theta.$$

⟦folio 45⟧

Hình 8.

Do đó, với sơ đồ kết nối tải với nguồn như vậy, sự thay đổi điện áp trên tải lớn hơn 2%.

Một mạch khác là mạch “chia” (Hình 8). Rõ ràng là khi điện trở $R_2$ nhỏ so với điện trở tải thì tổng điện trở của đoạn mạch khoanh tròn trong hình thay đổi rất ít khi điện trở tải thay đổi. Điện áp trên tải cũng thay đổi ít.

Hãy tính các thông số của “dải phân cách”. Điện áp tải là
$$U = IR_2'$$
trong đó $I = \frac{E}{R_1 + r + R_2'}$ là dòng điện trong mạch và $R_2' = \frac{R_2R}{R_2 + R}$ là điện trở của khu vực được bao quanh bởi khung.

$$U = \frac{E}{R_1 + r + \frac{R_2R}{R_2 + R}} \cdot (1)$$

Trong sơ đồ này, e. d.s. nguồn được chia thành điện trở $R_2'$ và điện trở $R_1 + r$. Điện trở $R_2'$ càng lớn thì điện áp trên tải càng lớn. Mặt khác, điện trở $R_2'$ tăng khi điện trở tải $R$ tăng. (Biểu đồ phụ thuộc của $R_2'$ vào $R$ được hiển thị trong Hình 9.) Nếu, với điện trở tải $R = 50$ ohm, điện áp trên tải là 20 $\beta$, thì với điện trở tải $R = 100$ ohm, điện áp trên nó phải cao hơn 2%, tức là 20,4 $\beta$. Thay thế các giá trị số của tất cả các đại lượng đã biết vào công thức (1), chúng ta thu được hai phương trình:

$$\begin{align*}
\frac{100}{2 + R_1 + \frac{50R_2}{R_2 + 50}} &= 20, \\
\frac{100}{2 + R_1 + \frac{100R_2}{R_2 + 100}} &= 20,4,
\end{align*}$$

và lực $F$ truyền cho anh ta gia tốc hướng tâm $\frac{v^2}{r}$, thì

$$F = m \frac{v^2}{r},$$

hoặc $\frac{e^2}{r^2} = m \frac{v^2}{r}$.

Từ đẳng thức này suy ra rằng

$$mv^2 = \frac{e^2}{r}.$$

⟦folio 46⟧

Do đó, động năng của electron bằng

$$W_K = \frac{m v^2}{2} = \frac{e^2}{2 r}.$$

Bây giờ chúng ta có thể tìm tổng năng lượng của một electron trên quỹ đạo có bán kính $r$:

$$W = W_K + W_\pi = \frac{e^2}{2 r} - \frac{e^2}{r} = -\frac{e^2}{2 r}.$$

Năng lượng của photon do nguyên tử phát ra là:

$$E = W_1 - W_2 = -\frac{e^2}{2 r_1} - \left(-\frac{e^2}{2 r_2}\right) =$$

$$= \frac{e^2}{2} \left(\frac{1}{r_2} - \frac{1}{r_1}\right) = 16, 3 \cdot 10^{-12} \text{ erp}.$$

Vì năng lượng của photon liên hệ với tần số $v$ của nó theo công thức $E = hv$, trong đó $h$ là hằng số Planck, nên

$$v = \frac{E}{h} = 2, 6 \cdot 10^{15} \text{ c}^{-1}.$$

Các biên tập viên đã nhận được hơn 600 lá thư. Hầu hết tất cả các chữ cái đều chứa các quy tắc lời giải bài toán $\Phi 139$, $\Phi 143$, $\Phi 144$. lời giải đúng trong số bài toán mông còn lại là những độc giả sau: A. Hayrapemyan (Yerevan) $\Phi 142$, $\Phi 145$, $\Phi 147$; A. Andreev (Leningrad) $\Phi 145$, $\Phi 146$; Sh. Atakulov (Fergana) $\Phi 145$, $\Phi 146$; A. Alyaev (Arzamas) $\Phi 147$; A. Asasyan (Yerevan) $\Phi 147$; V. Belkov (Moscow) $\Phi 142$; I. Bramovskaya (Usolye-Sibirskoye) $\Phi 145$; A. Baevsky (Gomel) $\Phi 138$, $\Phi 142$; V. Burkin (Sterlitamak) $\Phi 147$; M. Bolyshakov (Saratov) $\Phi 146$, $\Phi 147$; A. Blinov (Moscow) $\Phi 142$; M. Brenerman (Kazan) $\Phi 145$; Bardina (Novokuznetsk) $\Phi 145$, $\Phi 147$; A. Borminkov (Krasnodar) $\Phi 142$; O. Belkin (Orenburg) $\Phi 147$; A. BakULEV (Moscow) $\Phi 142$; T. Weintraub (Chisinau) $\Phi 145$—$\Phi 147$; V. Vorobiev (Koutancy) $\Phi 147$; V. Vekshtein (Kyiv) $\Phi 145$; I. Vasitsak (Kyiv) $\Phi 140$; A. Barinov (Zhukovsky, vùng Moscow) $\Phi 145$; I. Vacker (Minsk) $\Phi 142$; Yu. Gorny (Khadzhensk, vùng Krasnodar) $\Phi 147$; S. Granin (Dzerzhinsk) $\Phi 145$; O. Glutsenenko (Glukhov, vùng Sumy) $\Phi 142$; A. Goffman (Moscow) $\Phi 140$; V. Gerasimov (Sarapul) $\Phi 147$; S. Grigoryan (Yerevan) $\Phi 147$; A. Grigoriev (Grozny) $\Phi 147$; S. Gorodnikov (Grozny) $\Phi 145$; S. Dick (Zhodino, vùng Minsk) $\Phi 145$; V. Derevezin (Donetsk) $\Phi 145$, $\Phi 147$; E. Dollov (Moscow) $\Phi 142$, $\Phi 145$; V. Dashkevich (Kirovsk, vùng Mogilev) $\Phi 145$; A. Davisikov (Leningrad) $\Phi 142$; A. Danizl (Leningrad) $\Phi 145$; A. Dorofeev (làng Fokino, vùng Gorky) $\Phi 142$; S. Egorov (Klimovsk, vùng Moscow) $\Phi 147$; A. Edrenkin (Moscow) $\Phi 145$, $\Phi 147$; V. Zhelezny (Leningrad) $\Phi 146$; V. Zindels (Kyiv) $\Phi 145$; A. Zboev (làng Medvedok, vùng Kirov) $\Phi 140$; V. Zabolochkin (Donetsk) $\Phi 142$, $\Phi 147$; I. Zmukko (làng Ruzhany, vùng Brest) $\Phi 145$; A. Izrailevich (Sverdlovsk) $\Phi 147$; P. Kryshenik (Uzhgorod) $\Phi 147$; V. Kolesnikov (Chelyabinsk) $\Phi 142$; S. Korneev (Novokuznetsk) $\Phi 145$; A. Krechemnikov (Sumy) $\Phi 140$; V. Kadaer (Moscow) $\Phi 140$—

46
