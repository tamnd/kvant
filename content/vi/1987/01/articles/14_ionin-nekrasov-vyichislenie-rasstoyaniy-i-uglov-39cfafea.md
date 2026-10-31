---
id: 1987-1-ionin-nekrasov-vyichislenie-rasstoyaniy-i-uglov-39cfafea
issue: kvant_1987_1
year: 1987
number: "1"
title: Tính khoảng cách và góc
authors:
  - Ионин Ю. И.
  - Некрасов В. Б.
rubric: praktikum-abiturienta
rubric_sub: Практикум абитуриента
page_first: 49
page_last: 53
page_labels: 47, 48, 50, 51
tag: ROC0
lang: vi
source: kvant_digital
extraction: vision
content_sha256: a9b4840ef5a3ec835e8bc23f3093ca5157ae94be6a1d962fc11502420ffa58a8
prompt_sha256: draft-1
translated_from: content/ru/1987/01/articles/14_ionin-nekrasov-vyichislenie-rasstoyaniy-i-uglov-39cfafea.md
source_content_sha256: bd92730ddf940480deef215de2d84af829a826b5218ca8ee01440a0a1de60d71
translation_model: draft
translation_run: vi-draft-2026-10-31
translation_quality: draft
---

⟦folio 47⟧

Nâng cao khoảng cách và góc độ

Ứng viên khoa học sư phạm
Yu. I. IONIN,
V. V. NEKRASOV

Bài viết này thảo luận về một số bài toán hình học, cho lời giải mà cần phải tính khoảng cách hoặc góc nhất định trong không gian (những bài toán này được trình bày trong kỳ thi tuyển sinh vào chương trình phát triển đại học). Các bài toán thuộc loại này có thể được giải thuận tiện bằng cách sử dụng tích vô hướng của vectơ. Phương pháp chính lời giải là chọn một cơ sở phù hợp trong không gian và biên soạn một bảng nhân - một bảng tích vô hướng của các vectơ của cơ sở này. Có một bảng như vậy và biết cách phân rã các vectơ trong cơ sở đã chọn, người ta dễ dàng tính được độ dài của các vectơ này và góc giữa chúng. Chúng ta sẽ bắt đầu với một bài toán đơn giản, trong đó phương pháp tự hướng dẫn và sau đó chuyển sang các vấn đề phức tạp hơn, trình bày tất cả các trường hợp cơ bản ở đó.

Nhiệm vụ 1 (MAI, 1981). Trong tam giác ABCD, tất cả các cạnh đều có cùng độ dài. Điểm M là trung điểm cạnh AD, điểm O là tâm tam giác ABC, điểm N là trung điểm cạnh AB, điểm K là trung điểm cạnh CD. Tìm góc giữa hai đường thẳng MO và KN.

Lời giải e. Chúng ta hãy lấy độ dài cạnh của tứ diện là một và chọn vectơ $\overrightarrow{DA} = \vec{a}, \overrightarrow{DB} = \vec{b}, \overrightarrow{DC} = \vec{c}$ làm cơ sở. Hãy tạo một bảng nhân cho cơ sở này (Bảng 1, trang 48). Chúng ta hãy mở rộng các vectơ $\overrightarrow{MO}$ và $\overrightarrow{KN}$ thành các vectơ $\vec{a}, \vec{b}, \vec{c}$:

$$\overrightarrow{MO} = \overrightarrow{DO} - \overrightarrow{DM} = \frac{1}{3} (\vec{a} + \vec{b} + \vec{c}) - \frac{1}{2} \vec{a} = \frac{1}{6} (-\vec{a} + 2\vec{b} + 2\vec{c}),$$

$$\overrightarrow{KN} = \overrightarrow{DN} - \overrightarrow{DK} = \frac{1}{2} (\vec{a} + \vec{b}) - \frac{1}{2} \vec{c} = \frac{1}{2} (\vec{a} + \vec{b} - \vec{c}).$$

Góc $\varphi$ giữa hai đường thẳng MO và KN được tính theo công thức

$$\cos \varphi = \frac{|\overrightarrow{MO} \cdot \overrightarrow{KN}|}{|\overrightarrow{MO}| \cdot |\overrightarrow{KN}|}.$$

Hãy tìm $\overrightarrow{MO} \cdot \overrightarrow{KN}$, $|\overrightarrow{MO}|$ và $|\overrightarrow{KN}|$, được bảng 1:

⟦folio 48⟧

$$\overrightarrow{MO} \cdot \overrightarrow{KN} = \frac{1}{12} (-\vec{a} + 2\vec{b} + 2\vec{c}) (\vec{a} + \vec{b} - \vec{c}) = \frac{1}{12};$$
$$|\overrightarrow{MO}| = \frac{1}{6} \sqrt{(-\vec{a} + 2\vec{b} + 2\vec{c})^2} = \frac{1}{2};$$
$$|\overrightarrow{KN}| = \frac{1}{2} \sqrt{(\vec{a} + \vec{b} - \vec{c})^2} = \frac{\sqrt{2}}{2}.$$
Do đó $\cos \varphi = \frac{\sqrt{2}}{6}$, $\varphi = \arccos \frac{\sqrt{2}}{6}$.

Tuy nhiên, điều kiện bài toán không phải lúc nào cũng cho phép chọn cơ sở với bảng nhân được xác định đầy đủ. Trong trường hợp này, bạn cần cố gắng tạo phương trình cho phần tử không đủ.

Bài toán 2 (MIPT, 1974). Cạnh đáy của lăng trụ tam giác vuông $ABCA_1B_1C_1$ bằng $a$, các điểm $O$ và $O_1$ lần lượt là tâm của các đáy $ABC$ và $A_1B_1C_1$. Độ dài hình chiếu trực giao của đoạn $AO_1$ lên đường thẳng $B_1O$ bằng $\frac{5a}{6}$. Xác định chiều cao của lăng kính.

Đã giải quyết và e. Chúng ta hãy chọn các vectơ $\overrightarrow{AA_1} = \vec{m}, \overrightarrow{AB} = \vec{n}, \overrightarrow{AC} = \vec{p}$ (hình 1) làm cơ sở. Hãy để $h = |\vec{m}|$. Bảng 2 là bảng nhân của cơ số $(\vec{m}, \vec{n}, \vec{p})$.

Hình chiếu trực giao của đoạn $AO_1$ lên đường thẳng $B_1O$ bằng độ dài của đoạn này nhân với cosin của góc

Hình 1.

f giữa các dòng $AO_1$ và $B_1O$. Để tính $|\overrightarrow{AO_1}|$ và cos $\varphi$, chúng ta mở rộng vectơ $\overrightarrow{AO_1}$ và $\overrightarrow{B_1O}$ thành cơ sở $(\vec{m}, \vec{n}, \vec{p})$:

$$\overrightarrow{AO_1} = \frac{1}{3} (\overrightarrow{AA_1} + \overrightarrow{AB_1} + \overrightarrow{AC_1}) =$$
$$= \frac{1}{3} (\vec{m} + \vec{m} + \vec{n} + \vec{p}) =$$
$$= \frac{1}{3} (3\vec{m} + \vec{n} + \vec{p});$$
$$\overrightarrow{B_1O} = \overrightarrow{AO} - \overrightarrow{AB_1} = \frac{1}{3} (\vec{n} + \vec{p}) - (\vec{m} + \vec{n}) =$$
$$= \frac{1}{3} (-3\vec{m} - 2\vec{n} + \vec{p}).$$

Qua bảng 2, chúng tôi thấy:

$$|\overrightarrow{AO_1}| = |\overrightarrow{B_1O}| = \frac{1}{3} \sqrt{9h^2 + 3a^2},$$
$$\overrightarrow{AO_1} \cdot \overrightarrow{B_1O} = -\frac{1}{6} (6h^2 + a^2),$$
$$\cos \varphi = \frac{6h^2 + a^2}{2(3h^2 + a^2)}.$$

Vì $|\overrightarrow{AO_1}| \cdot \cos \varphi = \frac{5a}{6}$ nên ta có phương trình
$$\frac{\sqrt{9h^2 + 3a^2}(6h^2 + a^2)}{6(3h^2 + a^2)} = \frac{5a}{6}.$$
Do đó $h = \frac{a \sqrt{6}}{3}$.

Có bốn loại bài toán chính để tính khoảng cách và góc:

1. Khoảng cách từ một điểm đến một đường thẳng

Cho trước: điểm $M$; đường $l$ có vectơ chỉ hướng $\vec{a}$, điểm $A$ thuộc đường $l$; $\overrightarrow{AM} = \vec{m}$.

Tìm: khoảng cách từ điểm $M$ đến đường thẳng $l$.

(Các vectơ $\vec{a}$ và $\vec{m}$ trong điều kiện khai triển của chúng theo một cơ sở nhất định với một bảng nhân cho trước.)

Hãy để chúng tôi trình bày sơ đồ lời giải của bài toán này.

Gọi $N$ là hình chiếu trực giao của điểm $M$ lên đường thẳng $l$ (hình 2). Sau đó $\overrightarrow{MN} = \overrightarrow{AN} - \overrightarrow{AM} = x\vec{a} - \vec{m}$. Nezvest-

⟦folio 50⟧

$\vec{A} = 60^\circ$. Tất cả các cạnh của lăng kính có chiều dài $a$. Điểm $K$ là hình chiếu trực giao của điểm $B_1$ lên mặt phẳng $DA_1C_1$, còn điểm $L$ là hình chiếu trực giao của điểm $K$ lên mặt phẳng $DD_1C_1C$. Tìm thể tích của kim tự tháp $DCLK$.

Lời giải. Lấy đáy của hình gốc $DCLK$ làm hình tam giác $CDL$, nằm trong mặt phẳng $DD_1C_1C$. thì đoạn $KL$ là chiều cao của đoạn gốc (hình 5). Do đó, $V_{KCDL} = \frac{1}{3} S_{CDL} \cdot KL = \frac{1}{6} DC \cdot LM \cdot KL$, trong đó $M$ là hình chiếu trực giao của điểm $L$ lên đường thẳng $DC$.

Hãy chọn các vectơ $\vec{C}_1\vec{B}_1 = \vec{m}, \vec{C}_1\vec{D}_1 = \vec{n}, \vec{C}_1\vec{C} = \vec{p}$ làm cơ sở và điền vào Bảng 4 - bảng nhân cho cơ sở này.

Kế tiếp,
$$\vec{B}_1\vec{K} = \vec{C}_1\vec{K} - \vec{C}_1\vec{B}_1 = x\vec{C}_1\vec{A}_1 + y\vec{C}_1\vec{D} - \vec{C}_1\vec{B}_1 = x(\vec{m} + \vec{n}) + y(\vec{n} + \vec{p}) - \vec{m} = (x - 1)\vec{m} + (x + y)\vec{n} + y\vec{p}.$$

Vì vectơ $\vec{B}_1\vec{K}$ vuông góc với vectơ $\vec{C}_1\vec{A}_1$ và $\vec{C}_1\vec{D}$ nên ta thu được hệ
$$\vec{B}_1\vec{K} \cdot (\vec{m} + \vec{n}) = 0, \quad \vec{B}_1\vec{K} \cdot (\vec{n} + \vec{p}) = 0.$$

Thay thế vectơ $\vec{B}_1\vec{K}$ bằng sự phân rã của nó thành cơ sở $(\vec{m}, \vec{n}, \vec{p})$ và sử dụng Bảng 4, quy trình được đơn giản hóa cho hệ thống điều khiển $2x + y = 1$, $3x + 4y = 1$, chúng ta mở $\vec{KL} = \frac{3}{5}(\vec{m} + \vec{n}) - \frac{1}{5}(\vec{n} + \vec{p}) = \frac{1}{5}(3\vec{m} + 2\vec{n} - \vec{p})$. Tương tự như $\vec{KL} = \vec{C}_1\vec{L} - \vec{C}_1\vec{K} = z\vec{C}_1\vec{D}_1 + t\vec{C}_1\vec{C} - \vec{C}_1\vec{K} = z\vec{n} + t\vec{p} - \frac{1}{5}(3\vec{m} + 2\vec{n} - \vec{p}) = \frac{1}{5}(-3\vec{m} + (5z - 2)\vec{n} + (5t + 1)\vec{p})$. Vì $\vec{KL} \cdot \vec{n} = 0$, rồi $-\frac{3}{2} + 5z - 2 = 0$, mở $z = \frac{7}{10}$ và $5t + 1 = 0$, mở $t = -\frac{1}{5}$. Kể từ đây,
$$\vec{KL} = \frac{1}{5}(-3\vec{m} + \frac{3}{2}\vec{n}) = \frac{3}{10}(-2\vec{m} + \vec{n}).$$

Bây giờ bạn có thể tìm thấy chiều cao của prima $KCDL$:
$$KL = \frac{3}{10}\sqrt{(-2\vec{m} + \vec{n})^2} = \frac{3a\sqrt{3}}{10}.$$

Tất cả những gì còn lại là tìm $\vec{LM}$:
$$\vec{LM} = \vec{CM} - \vec{CL} = u\vec{CD} - (\vec{C}_1\vec{L} - \vec{C}_1\vec{C}) = u\vec{n} - z\vec{n} - t\vec{p} + \vec{p} = (u - \frac{7}{10})\vec{n} + \frac{6}{5}\vec{p}.$$

Vì $\vec{LM} \cdot \vec{n} = 0$, nên $u = \frac{7}{10}$, mở $\vec{LM} = \frac{6}{5}\vec{p}$, $|\vec{LM}| = \frac{6a}{5}$. Như vậy,
$$V_{KCDL} = \frac{1}{6} \cdot a \cdot \frac{6a}{5} \cdot \frac{3a\sqrt{3}}{10} = \frac{3a^3\sqrt{3}}{50}.$$

3. Khoảng cách và góc giữa các đường giao nhau

Cho: đường thẳng $l_1$ có vectơ chỉ phương $\vec{a}_1$, điểm $A_1$ thuộc đường thẳng $l_1$; đường $l_2$ có vectơ chỉ hướng $\vec{a}_2$, điểm $A_2$ thuộc đường $l_2$; $\vec{A}_1\vec{A}_2 = \vec{m}$.

Tìm: khoảng cách $u$ góc giữa các đường thẳng $l_1$ và $l_2$.

⟦folio 51⟧

Nhiệm vụ loại này lời giải theo sơ đồ sau.

Cosin của góc φ giữa đường thẳng $l_1$ và $l_2$ được tìm theo công thức

$$\cos \varphi = \frac{|\vec{a}_1 \cdot \vec{a}_2|}{|\vec{a}_1| \cdot |\vec{a}_2|}.$$

Để xác định khoảng cách giữa các đường thẳng $l_1$ và $l_2$, tức là độ dài phân bố lại chung của chúng $P_1P_2$ ($P_1 \in l_1$, $P_2 \in l_2$, hình 6), chúng ta biểu thị vectơ $\vec{P}_1\vec{P}_2$ là $\vec{P}_1\vec{P}_2 = \vec{P}_1\vec{A}_1 + \vec{A}_1\vec{A}_2 + \vec{A}_2\vec{P}_2 = x\vec{a}_1 + \vec{m} + y\vec{a}_2$. Các hệ số không có trọng số $x, y$ được tìm từ điều kiện phân phối lại vectơ $\vec{P}_1\vec{P}_2$ cho các vectơ $\vec{a}_1$ và $\vec{a}_2$:

$$\begin{cases}
(x\vec{a}_1 + y\vec{a}_2 + \vec{m})\vec{a}_1 = 0, \\
(x\vec{a}_1 + y\vec{a}_2 + \vec{m})\vec{a}_2 = 0.
\end{cases}$$

Khoảng cách cần thiết là độ dài của vectơ $\vec{P}_1\vec{P}_2$, tức là $\sqrt{(x\vec{a}_1 + y\vec{a}_2 + \vec{m})^2}$.

Nhiệm vụ 5 (MSU, Mek.-Mat., 1977). Đáy của tham số SABC là tam giác đều ABC có độ dài cạnh là $4\sqrt{2}$. Cạnh bên SC phân bố lại trên mặt phẳng đáy và có độ dài 2. Tìm góc và khoảng cách giữa hai đường thẳng cắt nhau, một đường đi qua điểm S và trung điểm của cạnh BC, đường kia đi qua điểm C và điểm giữa của cạnh AB.

Lời giải. Gọi $M$ và $N$ là trung điểm của cạnh BC và AB (hình 7). Chúng ta hãy chọn các vectơ $\vec{CA} = \vec{a}$, $\vec{CB} = \vec{b}$, $\vec{CS} = \vec{c}$ làm cơ sở. Bảng nhân cho cơ sở này là bảng 5. Hãy tìm góc φ giữa hai đường thẳng SM và CN:

$$\vec{SM} = \vec{CM} - \vec{CS} = \frac{1}{2} \vec{b} - \vec{c} = \frac{1}{2} (\vec{b} - 2\vec{c}); \quad \vec{CN} = \frac{1}{2} (\vec{a} + \vec{b}).$$

Hãy tính $\vec{SM} \cdot \vec{CN}$, $|\vec{SM}|$, $|\vec{CN}|$:

$$\vec{SM} \cdot \vec{CN} = 12, \quad |\vec{SM}| = 2\sqrt{3}, \quad |\vec{CN}| = 2\sqrt{6}.$$

Vì vậy, $\cos \varphi = \frac{12}{2\sqrt{3} \cdot 2\sqrt{6}} = \frac{\sqrt{2}}{2}, \quad \varphi = 45^\circ$.

Bây giờ chúng ta hãy tính khoảng cách giữa các đường SM và CN, tức là độ dài phân phối lại PQ chung của chúng ($P \in SM, Q \in CN$):

$$\vec{PQ} = x\vec{SM} + y\vec{CN} + \vec{SC} = \frac{x}{2} (\vec{b} - 2\vec{c}) + \frac{y}{2} (\vec{a} + \vec{b}) - \vec{c} = \frac{1}{2} (y\vec{a} + (x + y)\vec{b} - (2x + 2)\vec{c}).$$

Từ điều kiện phân phối lại vectơ $\vec{PQ}$ của vectơ $\vec{b} - 2\vec{c}$ và $\vec{a} + \vec{b}$ ta thu được hệ phương trình

$$3x + 3y = -1, \quad x + 2y = 0,$$

từ đâu $x = -\frac{2}{3}, \quad y = \frac{1}{3}$.

Vì vậy, $\vec{PQ} = \frac{1}{6} (\vec{a} - \vec{b} - 2\vec{c}), \quad PQ = \frac{1}{6} \sqrt{(\vec{a} - \vec{b} - 2\vec{c})^2} = \frac{2\sqrt{3}}{3}$.

4. Góc giữa các mặt phẳng

Góc giữa hai mặt phẳng bằng góc giữa hai đường thẳng đó. Thật vậy, các mặt phẳng trống $a$ và $b$ cắt nhau dọc theo đường thẳng $c$ (hình 8). Thông qua một số đường $c$, chúng ta vẽ các đường $a$ và $b$, giao các mặt phẳng $a$ và $b$ dọc theo các đường $a_1$ và $b_1$, được phân phối lại bởi đường $c$ (xem hình 8). Góc giữa các mặt phẳng $a$ và $b$ bằng góc giữa các đường thẳng $a_1$ và $b_1$, đến lượt nó bằng góc giữa các đường thẳng $a$ và $b$ (vì các đường thẳng $a, b, a_1, b_1$ nằm trong cùng một mặt phẳng và $a \perp a_1, b \perp b_1$).
