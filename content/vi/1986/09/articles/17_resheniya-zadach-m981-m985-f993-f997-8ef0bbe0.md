---
id: 1986-9-resheniya-zadach-m981-m985-f993-f997-8ef0bbe0
issue: kvant_1986_9
year: 1986
number: "9"
title: Lời giải bài toán M981—M985; F993—F997
rubric: zadachnik-kvanta
rubric_sub: Задачник «Кванта»
page_first: 41
page_last: 52
page_labels: 39, 40, 41, 42, 43, 44, 47, 50
tag: BEP2
lang: vi
source: kvant_digital
extraction: vision
content_sha256: bb647baea848fb1675e28624226b24cb6ccbd054557b8db778cbbab77e65f087
prompt_sha256: draft-1
translated_from: content/ru/1986/09/articles/17_resheniya-zadach-m981-m985-f993-f997-8ef0bbe0.md
source_content_sha256: 154e098ff1d6a817298fc7e1cb70e9b72e78943bb100c9b970ac01836aad11a5
translation_model: draft
translation_run: vi-draft-2026-10-31
translation_quality: draft
---

⟦folio 39⟧

U=100 V and current flows through it as plotted on figure Pisc. 4, p. 37. Determine the original inductivity of the coli. Assuming losses negligible, find the velocity of the core at time $\tau=10^{-3}$ s.

V. E. Skogovarov

P1017. The world’s largest (Soviet-made) telescope has a mirror of diameter $D=6$ m for a lens. How much time is required to register the relative rotation of our Galaxy and Andromeda about their common centre of mass by comparing photographs obtained by this telescope? The distance to Andromeda is $R=1.42 \cdot 10^{11} R_0$, where $R_0$ is the radius of Earth’s orbit. The masses of our Galaxy and Andromeda equal, respectively, $M_G=2,5 \cdot 10^{11} M_0$ and $M_A=3.6 \cdot 10^{11} M_0$, where $M_0$ is the Sun’s mass. The photographs are taken in visible light of wavelength $\lambda=5 \cdot 10^{-7}$ m.

V. E. Belonuchkin

Lời giải bài toán

M981 — M985; F993 — F997

a) Rõ ràng nếu số $a$ viết bằng $n$ thì số $b$ viết bằng $k$ đơn vị và $n$ chia hết cho $k$ thì $a$ cũng chia hết cho $b$. Và kể từ năm 1986 = $2 \cdot 3 \cdot 331$, số $A=11...1$ của 1986 đơn vị, ngoài chính số 1 và $A$, còn có ít nhất 6 ước số nữa của cùng một đơn vị:

$$11, 111, 111 111, \underbrace{11...1}_{331}, \underbrace{11...1}_{662}, \underbrace{11...1}_{993}$$

b) Chúng ta chỉ ra không phải 28 mà là 128 ước của số $A$. Lưu ý rằng 111111 được phân tách thành 5 thừa số nguyên tố:

$$111111=1001 \cdot 111=3 \cdot 7 \cdot 11 \cdot 13 \cdot 37.$$

Xét rằng $10^{993}+1$ chia hết cho $10^3+1=1001$ và $10^{993}-1$ chia hết cho $10^3-1=999$ (xem tương tự ở lề, trong đó $n=2k+1=331$, $x=10^3$) và đặt $a=10^{331}$, chúng ta nhận được

$$A=\frac{a^6-1}{9}=(a^3+1)\frac{a^3-1}{9}=\frac{3 \cdot 7 \cdot 11 \cdot 13 \cdot 37}{1001} \cdot \frac{a^3-1}{999}.$$

Tích của bất kỳ tập hợp nào trong số 7 thừa số này sẽ là ước số $A$ (“tập rỗng” được trả lời bằng ước số 1). Vì vậy, chúng tôi đã tìm thấy $2^7=128$ các ước số và chúng đều khác nhau. Để xác minh điều này, chúng ta hãy chứng minh rằng tất cả 7 thừa số trong khai triển bằng văn bản $A$ đều đơn giản theo cặp. Trên thực tế, số dư khi chia số $a$ cho $m=10^6-1$ là 10, vì $10^{331}-10=10(10^6-55-1)$ chia hết cho $m$; do đó, $a^3 \pm 1$ khi chia cho $m$ cho phần dư $10^3 \pm 1$, tức là các số $(a^3+1)/1001$ và $(a^3-1)/999$ là nguyên tố cùng nhau với $m$ và rõ ràng là nguyên tố cùng nhau.

Không khó để tiếp tục khai triển $A$ thành thừa số nguyên tố cùng nhau:

$$A=3 \cdot 7 \cdot 11 \cdot 13 \cdot 37 \frac{a+1}{11} \cdot \frac{a^2-a+1}{91} \cdot \frac{a-1}{9} \cdot \frac{a^2+a+1}{111}$$

(từ tuyên bố được Chicken nhấn mạnh ở trên, suy ra rằng các thừa số ở đây là số nguyên); từ đó rõ ràng là $A$ có ít nhất $2^9=512$ ước số. Tiếp tục quá trình phân hủy này “bằng tay”

⟦folio 40⟧

M982. Trên các cạnh AB, BC và CA của tam giác ABC, dựng các hình vuông ABB₁A₂, BCC₁B₂, CAA₁C₂ ở mặt ngoài. Chứng minh rằng các phân phối lại cho các đoạn A₁A₂, B₁B₂, C₁C₂, được xây dựng lại tại điểm giữa của chúng, cắt nhau tại một điểm.

M983. Trong một giải đấu có 16 tay vợt mỗi người, hai người chơi một trận.
a) Cho một ví dụ về sự phân bố kết quả của một trò chơi trong đó 10 người tham gia bất kỳ có thể được xếp vào một vòng tròn sao cho mỗi người đánh bại người hàng xóm bên trái của mình.
b) Chứng minh rằng nếu điều kiện ở điểm a) được thỏa mãn thì có thể sắp xếp 11 người tham gia bất kỳ thành một vòng tròn như vậy.

Nuyu" vốn đã khó. Tuy nhiên, từ Định lý nhỏ của Fermat (được ghi bên lề), ta suy ra rằng $9A=10^{1986}-1$ chia hết cho số nguyên tố 1987. Do đó, một trong 4 thành phần cuối cùng phải chia hết cho 1987, nghĩa là A có ít nhất $2^{10}=1024$ ước số. Có lẽ một trong những độc giả đã cố gắng nâng xếp hạng này lên cao hơn nữa?

N. V. Vasiliev, L. D. Kurlyandchik

♦ Chúng ta sẽ chứng minh rằng các phép phân phối lại được xét ở bài toán chứa các đường trung tuyến của một tam giác nhất định được chuẩn bị cho tam giác ABC đã cho. Tuyên bố bài toán sau đó xuất phát từ thực tế là các đường trung tuyến của bất kỳ tam giác nào cắt nhau tại một điểm.

Vẽ các đường thẳng đi qua tâm các hình vuông song song với các cạnh của tam giác ABC (xem hình 1); họ giới hạn tam giác $A_0B_0C_0$ đã chuẩn bị sẵn cho anh ấy. Vì các đường $A_0B_0$ và $A_0C_0$ là trung điểm của đường phân phối lại cho các đoạn $AA_2$ và $AA_1$, nên điểm $A_0$ giao điểm của chúng là tâm đường tròn ngoại tiếp của tam giác $AA_1A_2$ và do đó, nằm trên trung điểm của phân phối lại $p_a$ với đoạn $A_1A_2$. Tương tự, trung điểm của các đoạn thẳng $p_b$ và $p_c$ tới các đoạn $B_1B_2$ và $C_1C_2$ lần lượt đi qua các điểm $B_0$ và $C_0$.

Vẫn còn phải chứng minh rằng các đường thẳng $p_a$, $p_b$, $p_c$ chứa các đường trung tuyến của tam giác $A_0B_0C_0$. Để làm được điều này, chỉ cần kiểm tra xem chúng có song song với các đường trung bình của tam giác ABC hay không là đủ; ví dụ: đường $p_a$ song song với đường trung tuyến AM hoặc $AM \perp A_1A_2$. Xoay tam giác ABC $90^\circ$ quanh điểm A sao cho đỉnh B tiến tới $A_2$ (hình 2). Trong trường hợp này, đặt điểm M và C là $M'$ và $C'$; thì $M'$ là trung điểm của $A_2C'$ và A là trung điểm của $A_1C'$ ($A_1A=AC=AC', \angle A_1AC=\angle CAC'=90^\circ$). Do đó, $AM'$ là đường trung bình của tam giác $A_1C'A_2$, tức là $AM' \parallel A_1A_2$; đồng thời $AM \perp AM'$.

Bạn có thể nhận được lời giải khác từ thông báo sau: gọi O là giao điểm của các đường trung tuyến của tam giác ABC; nếu các đoạn $A_1A_2$, $B_1B_2$ và $C_1C_2$ cắt song song thành các vectơ $\vec{AO}$, $\vec{BO}$ và $\vec{CO}$ tương ứng thì ba đoạn này sẽ ghép lại thành một hình tam giác và các đường thẳng $p_a$, $p_b$ và $p_c$ sẽ là điểm giữa của nó.

V. N. Dubrovsky

♦ a) Cho 16 tay vợt đứng thành vòng tròn và mỗi người đánh 7 người đứng cạnh mình theo chiều kim đồng hồ (cách các tay vợt cách nhau 8 chỗ chơi với nhau là không đáng kể). Sự phân bổ kết quả này thỏa mãn điều kiện bài toán: nếu bạn đánh dấu ngẫu nhiên 10 vận động viên quần vợt vào một vòng tròn - $A_1$, $A_2$, ..., $A_{10}$ (theo chiều kim đồng hồ), thì giữa $A_1$ và $A_2$, $A_2$ và $A_3$, ..., $A_{10}$ và $A_1$ sẽ có không quá 6 người chơi quần vợt, vì vậy trong mỗi cặp này, người đầu tiên thắng người thứ hai.

Số 16 trong điều kiện bài toán có thể được thay thế bằng bất kỳ $n \geq 3$ nào và 10 - bằng bất kỳ $k$ nào sao cho $(n+3)/2 \leq k \leq n$ - ví dụ được xây dựng theo cách giống hệt nhau. Nếu $k<(n+3)/2$, không thể xây dựng được ví dụ như vậy.

6) Hãy để chúng tôi chứng minh rằng nếu có $k(2<k<n)$ trong số $n$ người chơi quần vợt từng đấu với nhau

⟦folio 41⟧

trò chơi, có thể sắp xếp theo điều kiện thì $k+1$ điểm bất kỳ.

Hãy xem xét một nhóm $k+1$ người chơi quần vợt nhất định và loại bỏ một $-A$ khỏi nhóm đó, đồng thời sắp xếp $k$ còn lại trong một chu kỳ (sao cho mỗi người thắng người tiếp theo). Hãy đánh dấu những người từ $k$ mà $A$ thua là màu đỏ và những người mà nó thắng là màu xanh lam (xem hình); sẽ tìm thấy ít nhất một màu đỏ và ít nhất một màu xanh lam, bởi vì $A$ cùng với bất kỳ người chơi quần vợt $k-1$ nào có thể được sắp xếp theo một chu kỳ (nghĩa là, ngay cả trong số $k-1$ bất kỳ trong số $k$ của chúng tôi cũng có cả người chơi quần vợt màu đỏ và màu xanh lam). Bây giờ, hãy chọn bất kỳ vị trí nào trong vòng lặp của chúng ta có màu xanh lam sau màu đỏ theo chiều kim đồng hồ và chèn $A$ giữa chúng.

Lưu ý rằng đối với $n=16$, $k=10$, tuyên bố bài toán vẫn đúng ngay cả khi chúng tôi không yêu cầu tất cả người chơi quần vợt phải đấu với nhau. Để kiểm chứng điều này, chỉ cần xét điều kiện là có thể sắp xếp 10 vận động viên quần vợt bất kỳ thành một vòng tròn để rút ra hệ quả sau:

1) mỗi người thắng không quá 7 trận;
2) trong số 11 người bất kỳ có một người chơi cùng cả 10 người còn lại.

K. P. Kokhas, N. V. Vasiliev

M984. Thông qua một điểm tùy ý $K$ của hình vuông $ABCD$, một đường thẳng được kiểm tra cắt các cạnh đối diện của nó $AB$ và $CD$ tại các điểm $P$ và $Q$. Chứng minh giao điểm của đường tròn đi qua các điểm $K$, $B$, $P$ và $K$, $D$, $Q$ khác $K$, nằm trên đường chéo $BD$.

Gọi $L$ là giao điểm của đường chéo $BD$ với đường tròn $DQK$. Hãy chứng minh rằng điểm này cũng nằm trên đường tròn thứ hai - $BPK$. Để xác định điều này, giả sử rằng các điểm $K$ và $Q$ nằm đối diện nhau của $BD$, và $P$ và $K$ nằm cùng phía (xem hình). Khi đó, vì các góc $DQK$ và $DLK$ nội tiếp trong một đường tròn và nằm trên cùng một cung $DK$,

$$\angle BPK = \angle PQD = \angle KLD = 180^\circ - \angle KLB,$$

tức là tứ giác $PKLB$ nội tiếp trong một đường tròn.

Hãy đưa ra một lời giải khác sử dụng phép xoay. Đặt $M$ và $N$ lần lượt là giao điểm của các đường tròn $KQD$ và $KPB$ với các đường $AD$ và $BC$ (xem hình). Rõ ràng $\angle MKQ = \angle PKN = 90^\circ$, tức là đoạn $MN$ vuông góc với $PQ$ và đi qua các điểm $K$. Xét phép quay của điểm $Q$ thành $M$ (và tia $QC$ thành tia $MD$). Dễ dàng nhận thấy trong trường hợp này đường thẳng rẽ $QP$ sẽ biến thành $MN$, và đường thẳng $AB$ thành $BC$. Do đó, điểm $P$ sẽ chuyển sang $N$. Vì các đoạn $QM$ và $PN$ có thể nhìn thấy được từ tâm quay theo góc vuông nên tâm này nằm ở giao điểm của các vòng tròn này. Mặt khác, nó bằng các đường $AB$ và $BC$ (vì đường đầu tiên đi vào đường thứ hai) và do đó, nằm trên đường chéo $BD$.

V. N. Dubrovsky

M985. Góc giữa hai đường thẳng cắt nhau tại điểm $O$ gọi là góc giữa phương bắc $O$ và phương không hướng lên $90^\circ$. Có bao nhiêu cách kiểm tra ba đường thẳng $l_1$, $l_2$, $l_3$ đi qua điểm $O$ trong không gian sao cho các góc giữa $l_2$ và $l_3$, $l_3$ và $l_1$, $l_1$ và $l_2$ lần lượt bằng nhau về số lượng $\alpha_1$, $\alpha_2$, $\alpha_3$? (Hai đường thẳng

⟦folio 42⟧

$l_1, l_2, l_3$ và $l'_1, l'_2, l'_3$ được coi là giống nhau nếu chúng được "tải", tức là nếu có một phép quay hoặc sự đối xứng về mặt phẳng chuyển $l'_i$ thành $l'_i$, với tất cả $i=1, 2, 3$.

Phòng ngừa: đáp số phụ thuộc vào độ lớn của $a_1, a_2, a_3$: ví dụ: đối với $a_1=a_2=a_3=30^\circ$ nó không giống với $a_1=a_2=a_3=70^\circ$.

Mỗi góc phẳng phải nhỏ hơn tổng của hai góc còn lại và tổng của cả ba góc phải nhỏ hơn $360^\circ$ (ví dụ, xem sách giáo khoa: Hình học 9-10 / Biên tập bởi Z. A. Skorets - M.: Prosveshchenie, 1981, tr. 224). Trong trường hợp này, một góc tam diện được xác định duy nhất bởi các góc phẳng của nó (đến mức tắc nghẽn).

Gọi $l_1, l_2, l_3$ là các đường thẳng thỏa mãn điều kiện bài toán. Trên đường thẳng $l_1$, chúng tôi chọn một trong các tia có phần đầu $O$ - chúng tôi biểu thị nó $r_1$, - và trên các đường thẳng $l_2$ và $l_3$ - các tia $r_2$ và $r_3$, tạo các góc có độ lớn $a_2$ và $a_3$ với $r_1$ (xem hình). Vì góc giữa các đường thẳng $l_2$ và $l_3$ là $a_1$ nên góc giữa các tia $r_2$ và $r_3$ có thể là $a_1$ hoặc $180^\circ-a_1$. Từ những gì đã nói về góc tam diện, có thể suy ra rằng có nhiều nhất hai đường thẳng khác nhau (đến mức tắc nghẽn) với một góc cho trước $a_1, a_2, a_3$ giữa chúng. Chúng có được bằng cách mở rộng các cạnh của hai góc tam giác $T$ và $T'$ với các góc phẳng lần lượt là $a_1, a_2, a_3$ và $180^\circ-a_1, a_2, a_3$, và để tồn tại chúng cần và đủ các điều kiện (1) được thỏa mãn trong trường hợp thứ nhất, (2) trong trường hợp thứ hai.

Lưu ý rằng với $a_1=90^\circ$ tất cả các đường thẳng của chúng ta đều giống hệt nhau ($T \cong T'$, vì $a_1=180^\circ-a_1$). Tất nhiên, điều này cũng đúng khi $a_2=90^\circ$ - trong tính toán, bạn có thể chỉ cần thay đổi cách đánh số các dòng. Vì vậy, nếu ít nhất một trong các góc $a_1, a_2, a_3$ bằng $90^\circ$ và điều kiện (1) được thỏa mãn (hoặc điều kiện (2) trùng khớp với nó trong trường hợp này), thì bài toán của chúng ta có một lời giải duy nhất.

Cuối cùng, đặt tất cả các góc $a_1, a_2, a_3$ nhọn và thỏa mãn hệ tổng quát (1) và (2). Hãy để chúng tôi chỉ ra rằng khi đó các đường thẳng được tạo từ các góc tam diện $T$ và $T'$ là khác nhau. Để hai rãnh như vậy bị tắc nghẽn, góc $T'$ cần phải bị tắc nghẽn với góc $T$ hoặc nói chung là bất kỳ góc nào trong 8 góc tam giác có đỉnh $O$, các cạnh của chúng nằm trên cùng một đường thẳng $l_1, l_2, l_3$ với các cạnh của góc $T$. Dễ dàng nhận thấy góc phẳng của các góc tam diện này có thể bằng ($a_1, a_2, a_3$) (đối với góc $T$ và góc “thẳng đứng” với nó), ($180^\circ-a_1, 180^\circ-a_2, a_3$), ($a_1, 180^\circ-a_2, 180^\circ-a_3$) hoặc ($180^\circ-a_1, a_2, 180^\circ-a_3$). Nhưng góc $T'$ có chính xác 2 góc nhọn ($a_2$ và $a_3$), và trong tất cả các đường đi được viết ra, số của chúng là 3 hoặc 1.

A. V. Goncharov, V. N. Dubrovsky

F993. Một sợi dây được ném qua một thanh xà cố định nằm ngang. Để giữ một vật có khối lượng $m=6$ kg, cần tìm đầu thứ hai của sợi dây có lực nhỏ nhất là $F_1=40$ N (xem hình). Phải kéo sợi dây với lực tối thiểu bằng bao nhiêu $F_2$ để tải bắt đầu tăng?

Trọng lượng của tải $P=mg=60$ N lớn hơn đáng kể so với lực $F_1$ mà sợi dây phải được kéo. Tình huống này chúng ta đã biết rõ từ trong cuộc sống và gắn liền với sự hiện diện của dấu vết giữa sợi dây và khúc gỗ.

Trong trường hợp đầu tiên (dây đứng yên), lực của khay có hướng chống lại tác động của trọng lượng của tải và giúp giữ dây với tải. Việc tính toán hoàn chỉnh sự phân bố lực của dây là khá phức tạp, vì giá trị tuyệt đối của lực căng dây (xác định phản lực của gối đỡ trong

⟦folio 43⟧

điểm tiếp xúc giữa sợi dây và khúc gỗ) thay đổi từ $F_1$ (điều kiện cân bằng cho đầu bên trái của sợi dây) thành $P = mg$ (điều kiện cân bằng cho đầu bên phải). Tuy nhiên, đối với lời giải bài toán, chúng ta chỉ cần lưu ý rằng lực ma sát $F_{\tau p}$, tỷ lệ thuận tại mỗi điểm với phản lực của giá đỡ, sẽ tỷ lệ với lực căng của dây; để định nghĩa, chúng ta sẽ giả sử rằng $F_{\tau p}$ tỷ lệ thuận với lực căng lớn hơn, tức là $F_{\tau p} = kP$. Điều này có nghĩa là $F_1 = P - kP$ và tỷ lệ giữa lực căng lớn hơn $P$ với lực căng nhỏ hơn $F_1$ là một hằng số: $P/F_1 = 1/(1-k) = \text{const}$.

Trong trường hợp thứ hai, khi chúng ta muốn nâng tải lên, các đầu của sợi dây dường như đổi chỗ. Lực ma sát hóa ra có hướng chống lại tác dụng của lực $F_2$ và không còn giúp ích mà còn cản trở. Tỷ lệ giữa lực căng lớn hơn $F_2$ và lực căng nhỏ hơn $P$ phải giống như trong trường hợp đầu tiên $F_2/P = P/F_1$.

Từ đây là:

$$F_2 = \frac{P^2}{F_1} = 90 \text{ H.}$$

A. I. Buezdin

F994. Vệ tinh khám phá một hành tinh có mật độ $\rho$, di chuyển theo quỹ đạo tròn với chu kỳ quỹ đạo là $T$ và bề mặt tương đối của nó. Bao nhiêu bề mặt hành tinh sẽ vẫn chưa được khám phá?

◆ Từ vệ tinh, chỉ có thể nhìn thấy một phần bề mặt hành tinh, nằm bên trong hình nón, đỉnh của nó là điểm hiện đang đặt vệ tinh và các máy phát là tiếp tuyến với bề mặt hành tinh được vẽ từ điểm này (xem hình). Do đó, hai đoạn hình cầu vẫn chưa được khám phá, diện tích của chúng

$$s = 2 \cdot 2\pi rh = 4\pi r^2 (1 - \cos \alpha) = 4\pi r^2 \left(1 - \sqrt{1 - \left(\frac{r}{R}\right)^2}\right),$$

trong đó $r$ là bán kính của hành tinh, $R$ là bán kính quỹ đạo của vệ tinh. Tỷ lệ của diện tích này với diện tích bề mặt của hành tinh là

$$\frac{s}{S} = 1 - \sqrt{1 - \left(\frac{r}{R}\right)^2}.$$

Hãy biểu diễn mối quan hệ $r/R$ thông qua dữ liệu cho trong điều kiện bài toán.

Hãy viết phương trình chuyển động của vệ tinh:

$$G \frac{Mm}{R^2} = ma,$$ hoặc $a = G \frac{M}{R^2} = G \cdot \frac{4}{3} \pi r^3 \dot{\rho} \cdot \frac{1}{R^2}$.

Mặt khác, $a = (2\pi/T)^2 R$. Kể từ đây,

$$\frac{4}{3} G \pi \rho \frac{r^3}{R^2} = \frac{4\pi^2}{T^2} R,$$

Ở đâu

$$\frac{r}{R} = \sqrt[3]{\frac{3\pi}{G \rho T^2}}.$$

Thay thế giá trị này vào (*), chúng tôi tìm thấy phần diện tích bề mặt của hành tinh vẫn chưa được khám phá:

$$\frac{s}{S} = 1 - \sqrt{1 - \left(\frac{3\pi}{G \rho T^2}\right)^2/3}.$$

V. V. Dorin

⟦folio 44⟧

F995. Trong mao mạch phía tây có một chất lỏng có mật độ $\rho$. Khi mao quản được làm nóng đến mức nhỏ $\Delta T$, hóa ra ranh giới $AB$ giữa chất lỏng và hơi của nó (xem hình) không được kết nối. Đồng thời, áp suất hơi tăng $\Delta p$. Mật độ của chất lỏng thay đổi như thế nào?

Từ điều kiện bài toán suy ra trạng thái của hệ trước và sau khi đun nóng tương ứng với trạng thái cân bằng của chất lỏng và hơi của nó. Điều này có nghĩa là trong biểu đồ $p - T$, cả hai trạng thái đều nằm trên đường cong xã hội. Đường cong này, như đã biết, thể hiện sự phụ thuộc của áp suất $p$ của hơi bão hòa vào nhiệt độ $T$, và sự phụ thuộc này là đơn điệu. Các tiếp tuyến của đường cong $p$ (T) tạo các góc khác nhau với trục $T$. Chúng ta hãy chọn điểm đó trên đường cong mà tại đó tiếp tuyến tạo một góc $\alpha = \arctg \frac{\Delta p}{\Delta T}$ với trục $T$. Các giá trị $p$ và $T$ tương ứng với điểm này xác định duy nhất áp suất và nhiệt độ ban đầu của khí.

Khi đun nóng, chất lỏng sẽ nở ra, nghĩa là ranh giới $AB$ sẽ di chuyển sang phải. Tính bất động của ranh giới có nghĩa là khi đun nóng, một khối chất lỏng $\Delta m$ bay hơi đến mức chất lỏng còn lại có mật độ $\rho - \Delta \rho$ chiếm chế độ âm lượng. Như có thể thấy từ hình, thể tích này bằng thể tích chiếm giữ của hơi nước. Như vậy,

$$\Delta \rho = \frac{\Delta m}{V}.$$

(*)

Sự thay đổi áp suất hơi bão hòa có liên quan đến việc tăng nhiệt độ của nó thêm $\Delta T$. Từ phương trình trạng thái của hơi nước ở nhiệt độ $T$ và $T + \Delta T$ -

$$pV = \frac{m}{\mu} RT,$$

$$(p + \Delta p)V = \frac{m + \Delta m}{\mu}R(T + \Delta T)$$

- chúng tôi nhận được:

$$\Delta p \cdot V = \frac{\Delta m}{\mu}RT + \frac{m}{\mu}R \cdot \Delta T + \frac{\Delta m}{\mu}R \cdot \Delta T.$$

Bỏ qua số hạng $\frac{R}{\mu}(\Delta m \cdot \Delta T)$, từ đây xét (*) ta tìm được:

$$\Delta \rho = \frac{\mu}{R} \frac{\Delta p \cdot T - p \cdot \Delta T}{T^2}.$$

L. G. Markovich

F996. Trong máy đo chọn lọc khối lượng ở trạng thái rắn, nguồn phát ra một loạt các hạt tích điện, đầu tiên chúng bay tự do (hình 1) và đi qua cảm biến đầu tiên ($\Delta_1$), ở hình 1.

Cho một hạt có khối lượng $m$ bay ra khỏi nguồn với tốc độ $v$. Chúng ta hãy biểu thị bằng $v_||$ hình chiếu của vận tốc này lên hướng song song với lưới $C$ và $v_⊥$ bằng hình chiếu $v$ lên hướng vuông góc với lưới. Khi các hạt di chuyển phía sau lưới (ở bên phải của lưới), $v_||$ không thay đổi và $v_⊥$ thay đổi từ $+v_⊥$ thành $-v_⊥$. Theo định luật bảo toàn động lượng (trong các hình chiếu lên phương vuông góc với lưới), $F \cdot \Delta t = m \cdot \Delta v_⊥ = 2mv_⊥$, trong đó $\Delta t$ là thời gian chuyển động của các hạt phía sau lưới; do đó $\Delta t = 2mv_⊥/F$. Tổng thời gian bay là

$$T = t + \Delta t = \frac{2L}{v_⊥} + \frac{2mv_⊥}{F}$$

(*) (t là tổng thời gian di chuyển từ cảm biến $\Delta_1$ đến lối vào lưới và từ lối ra khỏi lưới đến cảm biến $\Delta_2$).

⟦folio 47⟧

T. Misirnashaev (Moscow) 60; C. Mortisi (Tigroviste, SRR) 62; Y. Mustafayev (Baku) 64; S. Mushinsky (Novosibirsk) 57, 59, 62, 63, 65, 67, 68; T. Narbekov (Alma-Ata) 65; V. Neff (Donetsk) 65; Yu. Nikonorov (làng Mikhailovka, Cộng hòa Xã hội chủ nghĩa Xô viết Kazakhstan) 62, 65; O. Nits (Odeska) 60, 62, 63, 65, 67, 68; S. Okulovsky (Leningrad) 62, 64, 65; M. Pankov (Lviv) 62, 65, 67; Yu. Panchul (Kyiv) 62, 65; P. Pasmanik (Moscow) 65, 67; D. Pastur (Kharkov) 60; M. Pasumansky (Leningrad) 64; O. Pelevin (Kostroma) 62; A. Petrova (Leningrad) 57, 60; V. Pickman (Kyiv) 65; A. Pokrovsky (Kyiv) 57, 60, 62, 65, 67, 68; V. Polivov (Magnitogorsk) 57, 60; V. Pomaz (Semyonovka) 65; M. Pomerantsev (Cherkasy) 57; I. Portnoy (Odeska) 62—65, 67, 70; V. Protsak (Kyiv) 62, 64, 65, 67; V. Lông thú (Kharkov) 62, 64, 65, 67; V. Radulin (Chelyabinsk) 67, 68; A. Raisky (Alma-Ata) 65; I. Raskina (Vitebsk) 62, 65; S. Reznov (Kyiv) 62, 65, 67, 68; M. Rzaev (Vaku) 62; A. Roiterstein (Leningrad) 62-64; K. Rubtsov (Kyiv) 62, 65; T. Rudenko (Kyiv) 65; D. Romanin (Krasnoirsk) 57, 64; V. Sakbeev (Alma-Ata) 65; Z. Salkanova (Alma-Ata) 65; I. Samovol (Gayvoron) 60; D. Seminkhin (Kyiv) 62, 65, 68; S. Silvestrov (Kyiv) 62, 64, 65, 67; I. Simonenko (Vellike Luki) 60; K. Sinalevich (Leningrad) 65; V. Slituzhe (Dimitrovgrad) 67; S. Smirnov (Leningrad) 62—65, 67, 68, 70; V. Stolin (Vilnos) 62, 63, 67; A. Strunin (Yaroslavl) 64, 65, 67, 68; K. Styrkas (làng Chernogolovka, vùng Moscow) 62, 64, 67; D. Seminkhin (Kyiv) 62, 65, 68; S. Silvestrov (Kyiv) 62, 64, 65, 67, 68; I. Simonenko (Vellike Luki) 60; I. Ustilovsky (Moscow) 59, 60, 62-65, 67, 68, 70; V. Fililshtein (Voronezh) 65; V. Fokin (Khabarovsk) 62, 65, 67; D. Khadzhtsev (Stara Zagora, Belarus) 62; L. Hristov (Silistra, NRB) 67; A. Chazirov (Alma-Ata) 60; E. Chernaya (Depprodzerzhinsk) 67, 70; K. Churashe (Novosibirsk) 62, 65, 67; E. Churashe (Novosibirsk) 62, 65, 67; Yu. Shampuk (Tselinograd) 62, 67; Yu. Shampuk (D. Novy Dvor, vùng Grodno) 67; I. Shekhtman (Kyiv) 67, 68; S. Shekhtman (Kyiv) 65; V. Shmuklerman (Odeska) 62; I. Sholev (Stara Zagora, Belarus) 65; I. Shor (Kyiv) 65; I. Shor (Kyiv) 65; P. Shrabotey (Moscow) 67; V. Shryer (Leningrad) 62-65; P. Steinberg (Pushino) 62, 65; G. Shuzay (Zaporozhye) 65; O. Shelkov (Navon) 62, 67; I. Shenetkova (Moscow) 67; V. Elkin (Kharkov) 62, 65; Y. Efdideev (Vaku) 62; O. Yusukhno (Kyiv) 62, 63, 65; A. Yavryan (Yerevan) 67.

Vật lý
A. Abanov (Krasnoirsk) 68, 69, 74; U. Abakirov (Alma-Ata) 75; O. Azikova (Tselinograd) 73-75, 78, 80; A. Anisimov (Kyiv) 78, 80; F. Asmanyarova (Tselinograd) 73-75, 78, 80; T. Akhmetov (Novosibirsk) 78, 80; K. Bedov (Chelyabinsk) 68—70, 72; A. Belechky (Kyiv) 78; Yu. Beloborodov (Chelyabinsk) 80; S. Belovolov (Novosibirsk) 68, 69, 78; D. Belonov (Sverdlovsk) 70; V. Berezsky (Kyiv) 69; A. Bermus (Grozny) 75; O. Besman

⟦folio 50⟧

Vị trí của lập trình và khoa học máy tính là một trong những hiểu lầm hiện nay. Tôi dám nói một cách mỉa mai rằng có khá nhiều “người thông minh” mà bạn có thể nghe thấy “đây hoàn toàn không phải là khoa học máy tính, đây là lập trình thuần túy”. Tuyên bố như vậy, theo quan điểm của tôi, cho thấy sự kém cỏi hoặc một quan điểm không chính xác về mặt phương pháp. Xét cho cùng, lập trình là một phần không thể thiếu của khoa học máy tính.

Tôi sẽ cố gắng làm rõ điều này bằng cách đưa ra câu hỏi cho chính mình. Tất nhiên, cách dễ nhất để tôi nói là chuyên ngành khoa học của tôi là lập trình. Bởi vì tôi đã lập trình theo nghĩa rộng trong phần lớn cuộc đời trưởng thành của mình. Đồng thời, tôi sẽ nhấn mạnh vào sự hiểu biết mở rộng như vậy về từ “lập trình”; nó không chỉ bao gồm việc viết các chương trình cụ thể. Nhưng bây giờ khoa học máy tính của chúng ta đã có tên - khoa học máy tính - tôi phải nói rằng khoa học máy tính cũng là chuyên ngành khoa học của tôi. Tôi có những công việc và suy nghĩ liên quan đến chủ đề khoa học máy tính, mối liên hệ của nó với các ngành khoa học khác, với toán học và vật lý cũng như nội dung của nó trong khóa học ở trường. Vì vậy, tôi sẽ trả lời ngắn gọn câu hỏi theo cách này: chuyên ngành khoa học hiện tại của tôi là khoa học máy tính, và chuyên ngành hẹp hơn là lập trình.

Bạn tưởng tượng sự tương tác giữa toán học và thông tin như thế nào?

— Trước hết, tôi muốn nhấn mạnh rằng khoa học máy tính mở rộng phạm vi của toán học. Ví dụ, các khía cạnh của khoa học máy tính như lý thuyết thuật toán và lập trình lý thuyết, cấu trúc dữ liệu, mô hình thông tin và thí nghiệm tính toán tạo cơ sở cho nghiên cứu toán học. Ngoài ra, máy tính còn cho phép ứng dụng hiệu quả nhất các phương pháp toán học thực tiễn vào mọi lĩnh vực hoạt động của con người. Có thể nói rằng khoa học máy tính là con đường mà các nhà toán học đang chinh phục thế giới.

Đối với các chuyên gia khoa học máy tính, khoa học toán học là bộ máy làm việc chính. Nhưng bản thân khoa học máy tính là một ngành khoa học tích hợp, nó không chỉ lấy từ toán học mà còn từ khoa học hiện tượng học, ngôn ngữ học và tâm lý học. Thông tin chiếm một vị trí đặc biệt sau các ngành khoa học khác: mục tiêu của nó là bộc lộ và vượt qua những nguyên tắc cơ bản về sự thống nhất xử lý thông tin trong Vũ trụ. (Tôi sẽ lưu ý trong ngoặc đơn rằng mạng mạng có phạm vi ứng dụng tương tự, nhưng không giống nhau: nghiên cứu các nguyên tắc cơ bản của luồng xử lý thông tin, nhưng không phải trong “toàn bộ Vũ trụ”, mà chỉ trong phạm vi kiểm soát.)

Chúng ta có thể nói thế này: nếu vật lý đang cố gắng trả lời “câu hỏi chết người” - tại sao thế giới được cấu trúc theo cách mà con người có thể sống trong đó, thì khoa học máy tính sẽ trả lời “câu hỏi chết người” của nó - tại sao chúng ta có thể hiểu thế giới xung quanh, nắm vững thông tin tồn tại một cách khách quan trong tự nhiên. Thông tin với tư cách là một khoa học bóp méo sự tồn tại của các hệ thống ký hiệu tự nhiên - vật mang thông tin trong tự nhiên, và chính nó tạo ra các hệ thống ký hiệu, bộc lộ sự thống nhất của các quy luật xử lý thông tin trong tự nhiên, trong công nghệ.

Việc tạo ra trí tuệ nhân tạo là một trong bài toán khoa học máy tính. Trong công nghiệp và công nghệ, chúng tôi giải phóng con người khỏi lao động chân tay. Thông tin giải quyết các vấn đề của con người trong quá trình xử lý thông tin, điều này đạt được bằng cách giải thích kỹ lưỡng về các chức năng của nó, sau đó được chuyển sang máy tính. Vì vậy, để hiểu được thông tin, cần phải phát triển một thuật toán xử lý nó. Đó là lý do tại sao họ thường nói: chúng ta biết nếu chúng ta lập trình được nó.

Tôi sẽ không đi sâu hơn vào việc duy trì chủ đề khoa học máy tính. Tôi sẽ chỉ nói rằng thông tin không phải là vật chất hay năng lượng, nhưng không phải là thông tin thứ ba. Bất kỳ khoa học nào cũng nghiên cứu một số cấu trúc của tự nhiên. Ở một khía cạnh nào đó, việc nghiên cứu cấu trúc của cấu trúc cũng thú vị và hấp dẫn không kém việc nghiên cứu cấu trúc của vật chất - sở thích thời trẻ của tôi - mà tôi đã nói đến ở đầu cuộc trò chuyện.

Veseda được ghi lại bởi A. V. Sosinsky
