---
id: 1973-8-resheniya-zadach-m174-m178-5f2eb56b
issue: kvant_1973_8
year: 1973
number: "8"
title: Lời giải bài toán M174—M178
rubric: zadachnik-kvanta
rubric_sub: Задачник «Кванта»
page_first: 64
page_last: 68
page_labels: 62-66
tag: UG4F
lang: vi
source: kvant_digital
extraction: vision
content_sha256: 40797e838483c12bd50777284b52ab10ddeb556a5bd7a5f82bf4685525987d03
prompt_sha256: draft-1
translated_from: content/ru/1973/08/articles/13_resheniya-zadach-m174-m178-5f2eb56b.md
source_content_sha256: 6f5d94e5c650aaef7ffd41b4a3cada658c15d63231a5b34f3eb80a1672e6fea9
translation_model: draft
translation_run: vi-draft-2026-10-31
translation_quality: draft
---

⟦folio 62⟧

Lời giải bài toán
M174—M178

M174. Xem bài viết của N. F. Sharyzin trên tr. 42.

M175. a) Mỗi ​​cạnh của một tam giác đều được chia thành m phần bằng nhau, kẻ các đường thẳng song song với các cạnh qua các điểm chia, cắt tam giác đó thành các tam giác nhỏ m2. Trong số các đỉnh của các tam giác thu được, N đỉnh phải được đánh dấu sao cho với mỗi hai đỉnh được đánh dấu A và B đoạn AB không song song với bất kỳ cạnh nào. Giá trị lớn nhất có thể có của N (cho m) là bao nhiêu?
Chúng ta hãy chia mỗi cạnh của tam giác thành m phần bằng nhau và vẽ các mặt phẳng song song với gam thông qua các điểm chia. Trong số các đỉnh của đa biên thu được, chúng ta đánh dấu N đỉnh sao cho không có hai đỉnh được đánh dấu nào nằm trên một đường thẳng song song với một trong các biên. N nhất có thể là gì?
b) Trong số các phương trình số nguyên lời giải

$$x_1 + x_2 + \dots + x_k = m,$$

thỏa mãn điều kiện m 0 ≤ x_i ≤ m (với mọi i=1,2,...,k), cần chọn N lời giải sao cho trong mỗi hai trong số lời giải đã chọn không có ẩn số x_i nào có cùng giá trị. Giá trị lớn nhất có thể có của N là bao nhiêu? (Bài toán a) và b) là một phần của trường hợp bài toán b) tương ứng với k=3 và k=4.)

Trước hết, hãy kiểm tra xem bài toán a) có phải là một phần của trường hợp bài toán b) với k=3 và k=4.

Tiếp nhận cho 1 là khoảng cách giữa các đường thẳng song song liền kề cắt hình tam giác (Hình 1). Mỗi điểm của tam giác được liên kết với 3 số: x₁, x₂ và x₃, biểu thị (theo thang đo đã chọn) khoảng cách từ điểm này đến cạnh của tam giác (Hình 2).

Dễ dàng chứng minh rằng tổng x₁ + x₂ + x₃ bằng nhau đối với mọi điểm của tam giác. Thật vậy, chúng ta hãy biểu thị bằng 2a độ dài cạnh của tam giác; thì ax₁, ax₂ và ax₃ là diện tích của các tam giác OA₂A₃, OA₁A₃ và OA₁A₂ (Hình 2); do đó a (x₁ + x₂ + x₃) là diện tích ΔA₁A₂A₃, nghĩa là x₁ + x₂ + x₃ không phụ thuộc vào việc chọn điểm O. Trên thang đo đã chọn, x₁ + x₂ + x₃ = m (trong đó m là số đoạn mà mỗi cạnh của tam giác được chia).

Chúng tôi ghép mỗi điểm của tam giác với 3 số: x₁, x₂ và x₃. Trong trường hợp này, các đỉnh của các hình tam giác nhỏ được liên kết với các số nguyên không âm (Hình 3).

Trong bài toán a) yêu cầu đối với mỗi hai đỉnh được đánh dấu A và B đoạn AB không song song với bất kỳ cạnh nào ΔA₁A₂A₃. Trong bài toán b) không có hai trong số lời giải được chọn, bất kỳ x_i chưa biết nào cũng phải thuộc cùng một giá trị. Tất nhiên, cả hai yêu cầu (yêu cầu thứ hai cho k=3) đều có nghĩa giống nhau.

Do đó, bài toán a), quả thực, dường như là trường hợp đặc biệt của bài toán b) với k=3.

Tương tự, người ta xác minh rằng bài toán 6) tương đương với bài toán b) với k=4.

Vì vậy, tất cả những gì còn lại là giải bài toán b).

Hãy định dạng lại nó:

Giả sử rằng trong một bảng hình chữ nhật có k cột và n hàng, có thể sắp xếp các số nguyên không âm sao cho tổng các số ở một hàng bất kỳ bằng m và không có số nào lặp lại ở bất kỳ cột nào. Cho k và m cố định. N có thể có nhiều nhất mà n có thể lấy là bao nhiêu?

Tất nhiên, công thức mới tương đương với công thức ban đầu, nhưng đồng thời cho phép phát biểu đơn giản hơn và ngắn hơn về lời giải.

⟦folio 63⟧

Hãy chứng minh rằng $N \leqslant \left[ \frac{2m}{k} \right] + 1$, trong đó $\left[ \frac{2m}{k} \right]$ là phần nguyên của số $\frac{2m}{k}$ (số nguyên lớn nhất không vượt quá $\frac{2m}{k}$).

Tổng số trong cột là $N$, chúng không lặp lại và không âm. Điều này có nghĩa là tổng của chúng không nhỏ hơn

$$0 + 1 + \cdots + (N - 1) = \frac{N(N - 1)}{2}.$$

Các cột trong bảng $k$. Điều này có nghĩa là tổng các số trong toàn bộ bảng không nhỏ hơn $\frac{kN(N - 1)}{2}$.

Mặt khác, ở mỗi hàng tổng các số là $m$ nên tổng các số trong toàn bảng là $Nm$.

Igak, $Nm \geqslant \frac{kN(N - 1)}{2}$. Do đó, $m \geqslant \frac{k(N - 1)}{2}$ và $\frac{2m}{k} \geqslant N - 1$. Vì $(N - 1)$ là số nguyên bắt buộc nên $\left[ \frac{2m}{k} \right] \geqslant N - 1$. Vì vậy, $N \leqslant \left[ \frac{2m}{k} \right] + 1$.

Chúng ta có thể nói điều đó $N = \left[ \frac{2m}{k} \right] + 1$ không?

Đối với $k = 1$ thì điều này rõ ràng không phải là trường hợp: $N = 1$, mà là $\left[ \frac{2m}{k} \right] + 1 = 2m + 1$. Nhưng hóa ra trường hợp $k = 1$ là ngoại lệ duy nhất: đối với $k \geqslant 2$

$$N = \left[ \frac{2m}{k} \right] + 1.$$

Để chứng minh điều này, chúng tôi xây dựng, đối với mọi số nguyên $k$ và $m$ ($k \geqslant 2, m \geqslant 0$), các bảng $k \times N$ thỏa mãn mọi điều kiện bài toán.

Đầu tiên đặt $k$ là một số tùy ý: $k = 2r, r \geqslant 1$. Nếu $m = rl$, trong đó $l$ là số nguyên không âm bất kỳ thì $N = l + 1$ (xem Bảng 1).

⟦folio 64⟧

Nếu $m = rl + q$, trong đó $0 \leq q < r$ thì trong toàn bộ số cột cuối cùng của Bảng 1 bạn cần thêm $q$ (xem Bảng 2); $N$ bằng $l + 1$. Do đó, với số chẵn $k$, các bảng được xây dựng cho bất kỳ $m$ nào.

Khi xây dựng bảng cho số lẻ $k > l$, chúng tôi đánh dấu trường hợp $k = 3$.

Đối với $k = 3$, nếu $m = 3l$ hoặc $m = 3l + 1$ thì $N = 2l + 1$ (Bảng 3 và 4) và nếu $m = 3l - 1$ thì $N = 2l$ (Bảng 5).

Cũng lưu ý e. Hình 3 tương ứng với bảng. 3 tại $k = 3$, $m = 6$.

Bây giờ, giả sử $k = 3 + 2r$ là số lẻ tùy ý lớn hơn ba và $m$ là số nguyên không âm bất kỳ. Chúng ta hãy biểu thị bằng $p$ phần còn lại của phép chia $m$ cho $k$ và theo khoảng cách 2 trường hợp: 1) $0 \leq p \leq r + 1$, 2) $r + 2 \leq p \leq 2r + 2$.

Trong trường hợp đầu tiên, $m = kl + q$, $0 \leq q = p \leq r + 1$, $N = 2l + 1$ và bảng tương ứng được hình thành bằng cách thêm vào bảng. 3 cột $2r$ như vậy sẽ thu được nếu có trong bảng. 2 thay thế $l$ bằng $2l$.

Trong trường hợp thứ hai $m = k(l - 1) + r + 2 + q$, $0 \leq q \leq r$, $N = 2l$ và bảng tương ứng được hình thành bằng cách thêm vào bảng. 5 cột $2r$ như vậy thu được nếu có trong bảng. 2 thay thế $l$ bằng $2l - 1$.

M. L. Gerver

M176. Cạnh nào của tam giác $ABC$ là giao điểm của các đường cao gần nhất với cạnh nào của tam giác đó, nếu $A < B < C$? Và đến đỉnh cao nào?

Chúng ta hãy biểu thị các độ cao bằng $AK$, $BM$, $CP$ và điểm giao nhau của chúng bằng $O$.

Khoảng cách từ $O$ đến các cạnh là $OK$, $OM$, $OP$.

Giả sử rằng $\Rightarrow C \neq 90^\circ$. Sau đó $OK < OM < OP$.

Hãy chứng minh bất đẳng thức bên trái (bất đẳng thức bên phải được chứng minh tương tự). Thật vậy, $\frac{OM}{OC} = \frac{AP}{AC} = \cos \theta A$, $\frac{OK}{OC} = \frac{BP}{BC} = \cos \theta B$.

Vì $\Rightarrow A < B$, rồi $\cos \theta A > \cos \theta B$, do đó $OM > OK$, đó là điều bắt buộc. Khoảng cách từ $O$ đến các đỉnh được sắp xếp theo độ lớn như sau: $OA > OB > OC$.

Hãy chứng minh bất đẳng thức bên trái (có thể chứng minh bất đẳng thức bên phải bằng cách tương tự).

$\frac{OA}{OP} = \frac{1}{\sin \theta OAP} = \frac{1}{\cos \theta B}$

$\frac{OB}{OP} = \frac{1}{\sin \theta OBP} = \frac{1}{\cos \theta A}$, từ đâu $OA > OB$. lời giải đã cho phù hợp với tất cả các hình tam giác ngoại trừ các hình tam giác vuông.

Trong trường hợp $C = 90^\circ$, cả hai bằng chứng đều thất bại.

Hãy tự tìm đáp số cho trường hợp này (nó rất mạnh).

M177. Tìm tất cả các phương trình lời giải

$\sqrt[n]{x^n - a^n} + \sqrt[n]{2a^n - x^n} = a$,

thực phẩm $a$ là một số thực nhất định, $n$ là một số tự nhiên lớn hơn một.

Đầu tiên chúng ta xét trường hợp đặc biệt $a = 0$. Chúng tôi nhận được:

$\sqrt[n]{x^n} + \sqrt[n]{-x^n} = 0$.

Nếu $n$ chẵn thì lời giải duy nhất sẽ là $x = 0$ (vì nếu không thì $x^n$ và $-x^n$ có dấu khác nhau và một trong các nghiệm là vô nghĩa). Nếu $n$ là số lẻ thì $x$ bất kỳ sẽ là lời giải.

Hãy để bây giờ $a \neq 0$. Ký hiệu $\sqrt[n]{x^n - a^n}$ bằng $y$ và $a - y$ bằng $z$, ta thu được hệ:

$$\begin{align*}
y + z &= a, \\
y^n + z^n &= a^n
\end{align*}$$

Cho phép

$$\begin{align*}
y &= a, \\
z &= 0
\end{align*}$$

hoặc $y = 0, z = a$.

Trong những trường hợp này, cả hai đẳng thức đều được thỏa mãn. Hãy xem những gì nó mang lại. Hãy tính $x$:

$$x^n = 2a^n$$ hoặc $x^n = a^n$.

Các đẳng thức này được thỏa mãn khi

$$x = \begin{cases}
a \sqrt[n]{2}, & \text{и } x = \begin{cases}
a, \text{если } n \text{-нечетное, } \pm a, \text{если } n \text{-четное, }
\end{cases}
\end{cases}$$

tương ứng. Thay thế các giá trị này của $x$ vào phương trình ban đầu, trong trường hợp chung, chúng ta thu được điều tương tự:

$$\sqrt[n]{a^n} = a$$.

Điều này đúng:

với mọi $a$, nếu $n$ là số lẻ, với $a \geq 0$, nếu $n$ là số chẵn.

Bây giờ chúng ta chứng minh rằng với $a \neq 0, y \neq 0, z \neq 0$ hệ (1) không thể thỏa mãn. Chỉ cần xét trường hợp khi $a > 0, y \geq z$. Thật vậy, nếu $y, z, a$ là cô ấy lời giải và $a < 0$, thì $-y, -z, -a$ cũng là cô ấy lời giải. Hơn nữa, nếu trong lời giải chúng ta đặt các giá trị $y, z$ vào các vị trí, thì chúng ta sẽ nhận được lời giải lần nữa. Điều này có nghĩa là nếu có lời giải với $a \neq 0$ thì cũng có lời giải với $a > 0$, sao cho $y \geq z$.

Vì vậy hãy để $a > 0, y \geq z$. Hai trường hợp cách nhau.

⟦folio 65⟧

a) $z > 0$. Sau đó
$$y^n + z^n = (y + z)^n,$$
(2)
từ đâu $z^n = (y + z)^n - y^n = (y + z - y) \times [(y + z)^{n-1} + \dots + y^{n-1}]$. But $z^n < z(y + z)^{n-1}$, so equality (2) is impossible.

6) $z < 0$. Hãy đặt $z = -w$.
Khi $n$ chẵn, hệ (1) có dạng
$$y - w = a,$$
$$y^n + w^n = a^n$$
hoặc
$$a + w = y,$$
$$a^n + w^n = y^n$$
tương tự phục vụ (a).
Vì vậy đây là đáp số cuối cùng.
Nếu $n$ là số lẻ thì với tất cả $a \neq 0$
$x_1 = a\sqrt{2}, x_2 = a$; cho $a = 0$ bất kỳ $x$ – lời giải.
Nếu $n$ chẵn thì với $a > 0$ $x_{1,2} = \pm a\sqrt{2}, x_{3,4} = \pm a$, với $a = 0$ $x = 0$ và với $a < 0$ lời giải thì không.

Hầu hết các lỗi trong thư do độc giả gửi là do đáp số được chỉ định không chính xác cho tất cả các giá trị của tham số $a$ và $n$, đáp số còn lại được chỉ định chính xác, nhưng không có bằng chứng nào cho thấy lời giải kia không đúng.

A. L. Toom

M178. Từ bất kỳ điểm $P$ nào, chúng ta thả các bisser của tam giác ABC vuông góc $PA_1, PB_1, PC_1$ lần lượt vào các cạnh BC, CA và AB. Gọi $R$ là giao điểm của đường $PA_1$ và $B_1C_1$. Chứng minh đường thẳng $AR$ chia cạnh BC làm đôi.

Vẽ đường thẳng đi qua điểm $R$ song song với cạnh BC. Để nó cắt các cạnh $AC$ và $AB$ tại các điểm $B_2$ và $C_2$. Chúng ta sẽ chứng minh rằng $R$ là trung điểm của đoạn $B_2C_2$: trong trường hợp này và chỉ trong trường hợp này đường thẳng $AR$ chia đôi BC. Vì $PR \perp B_2C_2$, để làm được điều này chúng ta cần chứng minh rằng tam giác $B_2PC_2$ là tam giác đều. Hãy chứng minh sự bằng nhau của các góc $C_2B_2P$ và $B_2C_2P$. Một vòng tròn có thể được mô tả xung quanh tứ giác $RC_2C_1P$ (điều này xuất phát từ thực tế là $C_2RP = C_2C_1P = 90^\circ$), có nghĩa là $RC_2P = RC_1P$. Nhưng tứ giác $AC_1PB_1$ ($\Rightarrow AC_1P = \Rightarrow AB_1P = 90^\circ$) cũng nội tiếp nên $B_2C_2P = PC_1B_1 = PAB_1$). Lập luận tương tự cho tứ giác $B_2B_1RP$ và $B_1AC_1P$ cho thấy $C_2B_2P = PAC_1$. Nhưng vì $AP$ là bisertier của $A$, nên chúng tôi yêu cầu các góc $C_2B_2P$ và $B_2C_2P$ phải bằng nhau. Nhiệm vụ lời giải.

H. F. Sharyn

⟦folio 66⟧

2, 8; L. Ruditser (Kharkov) 0, 2, 3; S. Sanktkovsky (Minsk) 4, 8; M. Sapir (Sverdlovsk) 0, 2, 3; A. Sboev (làng Medvedok, vùng Kirov) 4; S. Semenov (Voronezh) 0; R. Sirota (Kharkov) 0, 3, 8, 9a), 6), c); S. Sokov (làng Sokovki, Slobodskoy) 8; V. Slenoy (Frunze) 8; V. Slenenko (Chelyabinsk) 0, 4, 5, 8, 9a), 6), c); A. Slesarenko (Rubtsovsk) 0, 3, 4, 8; A. Slinkin (Moscow) 0, 2, 8; V. Solodushkin (Stepnogorsk) 3; P. Sukhov (Saratov) 3; Yu. Smetsko (Chernivtsi) 0; S. Tabachnikov (Moscow) 0; A. Tatsev (Baku) 0; A. Tinkov (Simferopol) 2; I. Tonoyan (Yerevan) 2; E. Turkevin (Chernivtsi) 0, 2—4, 8; A. Tulane (Kirovograd) 7, 8; V. Uryshev (Magnitogorsk) 8; V. Fedorov (khu vực Moscow) 8; V. Filin (Kaspiysk) 0; V. Khlebopros (Kyiv) 0; S. Tserkovny (Leningrad) 2; 4, 8; I. Tsukerman (Leningrad) 2; V. Circlevi (Balti) 2; N. Chamurltsev (Tbilis) 0; S. Cheremshantse (Leningrad) 9a), 6); N. Chernsov (Krivoy Rog) 8; V. Chernyakin (vùng Poltava) 8; E. Chesnokov (Moscow) 2; K. Schwarzan (Chisinau) 0; Yu. Shmelev (Yaroslavl) 0, 2, 4; I. Shuleev (Moscow) 8; V. Shuryshin (Gorky) 3; I. Sherbkov (Pervomaisk, vùng Nikolaev) 2; N. Sherbina (Dnepropetrovsk) 0, 2—5, 8; A. Shekhorsky (làng Stariki, vùng Zhytomyr) 2, 4, 8.

Yu. P. Lysov

Hầu hết tất cả độc giả đã gửi lời giải bài toán F188—F192 đều hoàn thành xuất sắc nhiệm vụ F188 và F190. bài toán còn lại đã được các độc giả sau giải đúng (số in đậm sau họ là chữ số cuối cùng của số đã giải bài toán): S. Akmertsev (Magnitogorsk) 1; M. Abdulkhakov (Angarsk) 2; O. Voinova (làng Kosh-Tegirmen Kigg. SSR) 9-1; S. Garkusha (Tashkent) 9; V. Grabsky (Leninakan) 9; N. Golovko (Proskhladny) 2; A. Davydov (Magnitogorsk) 1; S. Davtyan (Oktembergan, Cộng hòa Xã hội chủ nghĩa Xô viết Armenia) 1; Yu. Dvinin (Zaporozhye) 2; N. Demchuk (Myttish, vùng Moscow) 1; V. Zhelezny (Leningrad) 9, 1; V. Nenamiev (Volgograd) 9, 1; V. Karpenko (Kyiv) 9; V. Karpinsky (Sverdlovsk) 9, 1; Y. Kodan (Glazov) 1; V. Kolosov (Kyiv) 2; S. Kornilov (Grozny) 9, 1; I. Kuchik (Yaroslavl) 9, 1; A. Liyakomin (Dnepropetrovsk) 9; Z. Mayzlin (Kyiv) 2; G. Mamedov (Baku) 1; N. Mironov (Vyka) 9, 1; A. Nikolaev (Moscow) 9, 2; V. Novienko (làng Masalli, Cộng hòa Xã hội chủ nghĩa Xô viết Azerbaijan) 1; G. Ozannitsan (làng V. Artashat Arm. SSR) 9; V. Orlov (Moscow) 9; A. Papin (Gomel) 9, 2; V. Pankov (Minsk) 2; I. Pashin (Saratov) 9; Vâng. Pevzer (Leningrad) 9, 2; V. Prosmokshin (Riga) 9, 1; A. Resce (Rostov-on-Don) 2; L. Ruditser (Kharkov) 9; Y. Saibelan (Kyiv) 2; A. Sboev (làng Medvedok, vùng Kirov) 9; S. Svilolunov (Ufa) 1; Y. Simkin (Moscow) 9, 1, 2; Yu. Smolentsev (Essentuki) 9, 1; S. Surovce (Moscow) 9, 1; V. Tatarinov (làng Znoby-Novgorodskoe, vùng Sumy) 2; O. Teryaev (Dnepropetrovsk) 1, 2;

V. Usachev (làng Arkhangelskoye, quận Arkhangelsk) 2; N. Fedin (Omsk) 9, 2; A. Fridman (Moscow) 9; S. Khomenko (Podolsk) 9, 1; V. Tsirklev (Balti Moldova SSR) 9; V. Chernishov (vùng Penza) 1; V. Shendrik (Alma-Ata) 1; V. Shishchin (Izhevsk Udm. ASSR) 1; A. Shekhorsky (làng Stariki, quận Korostensky) 9; S. Shukin (Dnepropetrovsk) 2; S. Yakushev (Ufa) 9.

S. G. Semenchinsky

Đáp số trong trò chơi ô chữ xếp ở vị trí số 7
Theo chiều ngang
3. Dung nham. 4. Piri. 6. Entropy. 8. Cameron. 13. Sự gián đoạn. 15. Thanh. 17. Tuyết. 19. Cầu vồng. 20. Lỗi. 21. Số. 22. Clairo. 23. Liên tục. 25. Chẩn đoán. 26. Nhà tôpô. 27. Cát. 31. Angstrom. 32. Áp lực. 37. Dirac. 39. Sự ấm áp. 41. Pythagore. 43. Sự phản đối. 45. Chế độ. 46. ​​​​Phác thảo. 47. Ghi lại. 48. Suy tàn. 49. Giải thưởng. 50. Vinh. 51. Kim cương. 56. Quả bơ. 57. Điện cực. 58. Kant. 59. GIRD.
Nghèo nàn
1. Thạch anh. 2. Số. 3. Lenitz. 5. Summary. 7. Dự báo. 9. Lộ trình. 10. CÔNG BỐ. 11. Thần chú. 12. Tương tự. 13. Slin. 14. Ladoga. 16. Jump. 18. Hertz. 23. Hằng số. 24. Modulation. 27. Train. 28. Quark. 29. Jung. 30. Biyu. 33. Intuition. 34. Franklin. 35. Con quay hồi chuyển. 36. Tàu lượn. 38. Radian. 40. Aneroid. 41. Nutrition. 42. Tepp. 44. Tình trạng lấp lửng. 52. Sound. 53. Fire. 54. Low tide. 55. Probe.
