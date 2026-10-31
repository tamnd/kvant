---
id: 1980-11-zalgaller-zadacha-o-treugolnikah-s-obschim-osnovaniem-652d2e9d
issue: kvant_1980_11
year: 1980
number: "11"
title: Bài toán trên các hình tam giác có chung đáy
authors:
  - Залгаллер В. А.
rubric: matematicheskiy-kruzhok
rubric_sub: Математический кружок
page_first: 17
page_last: 20
page_labels: 15-18
tag: A8NV
lang: vi
source: kvant_digital
extraction: vision
content_sha256: 88c39a6dba8417ed166f933702d5e794c25d3e0dd2c236b8615abc5eb29ef28b
prompt_sha256: draft-1
translated_from: content/ru/1980/11/articles/06_zalgaller-zadacha-o-treugolnikah-s-obschim-osnovaniem-652d2e9d.md
source_content_sha256: 67f10cb09c95036037b7e692591d9fe695173d2afb9467aafd62d3a4fb6a4e69
translation_model: draft
translation_run: vi-draft-2026-10-31
translation_quality: draft
---

⟦folio 15⟧

Bài toán
về hình tam giác
với điểm chung

Trong số thứ năm của «Kvant» năm 1978, người ta đã đề xuất tìm ra hình học lời giải của bài toán sau: hai hình tam giác trên mặt phẳng có một đáy chung và các đỉnh $C_1, C_2$ khác nhau và nằm cùng một phía của đáy; chứng minh rằng khoảng cách giữa các đỉnh $C_1$ và $C_2$ lớn hơn khoảng cách giữa tâm $O_1$ và $O_2$ của các đường tròn nội tiếp các tam giác này.

Trong hai năm qua, các biên tập viên đã nhận được rất nhiều tin nhắn về bài toán thú vị và khó khăn này. Tuy nhiên, không ai trong số độc giả của chúng tôi có thể tìm thấy một chứng minh có tính đến tất cả các khả năng về vị trí tương đối của các đỉnh.

Chúng tôi đặt hai bằng chứng; cái đầu tiên được phát minh bởi nhà toán học Kharkov A. I. Medyannik, cái thứ hai là bằng chứng do các tác giả bài toán V. A. Zalgaller và A. A. Ivanov đề xuất, được đơn giản hóa theo lời khuyên của viện sĩ A. V. Pogorelov.

Bằng chứng đầu tiên

Chúng ta sẽ cần tính chất sau của đường phân giác của một góc trong một tam giác (Hình 6-8, bài toán 914): nếu AD là đường phân giác của góc A của một tam giác

tù nhân $ABC$ ($D \in [BC]$), sau đó $\frac{|BD|}{|DC|} = \frac{|AB|}{|AC|}$.

Đặt điểm O là tâm của đường tròn nội tiếp $\triangle ABC$ (Hình 1). Chúng ta hãy biểu thị vectơ $\vec{O} = AO$ theo vectơ $\vec{a} = \vec{BC}, \vec{b} = \vec{AC}, \vec{c} = \vec{AB}$ và theo độ dài của chúng $a, b, c$.

Dễ dàng nhận thấy điều đó $\vec{\varrho} = \frac{|AO|}{|AD|} \cdot \vec{AD} = \frac{|AO|}{|AD|} \left( \vec{c} + \frac{|BD|}{|DC|} \vec{a} \right)$.

Theo tính chất đường phân giác $\frac{|DC|}{|BC|} = \frac{|BD|}{|DC|} + \frac{|BD|}{|DC|} = \frac{c}{b+c}$.

Tương tự ($BO$ là phân giác của góc B),

$\frac{|AO|}{|AD|} = \frac{1}{1 + \frac{|OD|}{|AO|}} = \frac{1}{1 + \frac{|BD|}{c}}$.

Từ $\frac{|BD|}{|DC|} = \frac{c}{b}$ và $|BD| + |DC| = a$ chúng ta nhận được $|BD| = \frac{ac}{b+c}$.

Vì vậy $\frac{|AO|}{|AD|} = \frac{b+c}{a+b+c}$.

Lợi dụng thực tế là $\vec{a} = -(\vec{b} + \vec{c})$, chúng ta thu được $\vec{\varrho} = \frac{b\vec{c} - c\vec{b}}{p}$ cuối cùng,

(1)

ở đâu $p = a + b + c$.

Bây giờ chúng ta hãy chuyển sang lời giải bài toán. Chúng ta hãy biểu thị độ dài của vectơ $\vec{d}_0 = O_1O_2$ theo $d = |C_1C_2|$ và độ dài các cạnh của tam giác $ABC_1, ABC_2$.

Theo những gì đã được chứng minh (xem Hình 2)

$\vec{d}_0 = \vec{\varrho}_2 - \vec{\varrho}_1 = \frac{b_2\vec{c} - c\vec{b}}{p_2} + \frac{c\vec{b}_1 - b_1\vec{c}}{p_1}$,

Hình 1.

⟦folio 16⟧

ở đâu $p_1 = a_1 + b_1 + c$, $p_2 = a_2 + b_2 + c$.

Tính $\vec{d}_0 \cdot \vec{d}_0 = d_0^2$, sau các phép biến đổi đơn giản, chúng ta thu được
$$p_1^2 p_2^2 d_0^2 = p_1^2 cb_2 [2cb_2 - 2(\vec{b}_2 \vec{c})] +$$
$$+ p_2^2 cb_1 [2cb_1 - 2(\vec{b}_1 \vec{c})] +$$
$$+ 2p_1 p_2 [cb_2(\vec{b}_1 \vec{c}) - c^2(\vec{b}_1 \vec{b}_2)] -$$
$$- b_1 b_2 c^2 + cb_1(\vec{b}_2 \vec{c})].$$

(2)

Lưu ý rằng $2(\vec{b}_1 \vec{c}) = a_1^2 - b_1^2 - c^2$, $2(\vec{b}_2 \vec{c}) = a_2^2 - b_2^2 - c^2$; Đó là lý do tại sao
$$2cb_1 - 2(\vec{b}_1 \vec{c}) = 2cb_1 - a_1^2 + b_1^2 + c^2 =$$
$$= (a_1 + b_1 + c)(b_1 - a_1 + c) =$$
$$= p_1(b_1 - a_1 + c),$$

tương tự,
$$2cb_2 - 2(\vec{b}_2 \vec{c}) = p_2(b_2 - a_2 + c).$$

Điều này làm giảm sự bình đẳng
(2) trên $p_1 p_2$. Ngoài ra, $\vec{d} = \vec{b}_2 - \vec{b}_1$, từ đâu $2(\vec{b}_1 \vec{b}_2) = b_1^2 + b_2^2 - d^2$. Đó là lý do tại sao
(2) có dạng
$$p_1 p_2 d_0^2 = p_1 cb_2(b_2 - a_2 + c) +$$
$$+ p_2 cb_1(b_1 - a_1 + c) +$$
$$+ [cb_2(a_1^2 - b_1^2 - c^2) - c^2(b_1^2 + b_2^2 - d^2)] -$$
$$- 2b_1 b_2 c^2 + cb_1(a_2^2 - b_2^2 - c^2)],$$
Ở đâu
$$p_1 p_2(d^2 - d_0^2) =$$
$$= [(a_1 + b_1 + c)(a_2 + b_2 + c) - c^2]d^2 +$$
$$+ [(a_2 - b_2 - c)(a_1 + b_1 + c)b_2 +$$
$$+ (a_1 - b_1 - c)(a_2 + b_2 + c)b_1 +$$
$$+ (b_1^2 - a_1^2 + c^2)b_2 + (b_1^2 + b_2^2)c +$$
$$+ 2b_1 b_2 c + (b_2^2 - a_2^2 + c^2)b_1]c,$$

mà sau khi chuyển đổi bên trong dấu ngoặc vuông sẽ cho
$$p_1 p_2(d^2 - d_0^2) = [(a_1 + b_1)(a_2 + b_2) +$$
$$+ c(a_1 + b_1 + a_2 + b_2)]d^2 +$$
$$+ [c(a_2 - a_1)(b_2 - b_1) +$$
$$+ (a_1 b_2 - b_1 a_2)(a_2 - a_1 + b_1 - b_2)]c.$$

(3)

Để chứng minh rằng $d > d_0$, chỉ cần chứng minh vế phải của đẳng thức (3) là dương là đủ. Sau này bao gồm hai điều khoản. Vì $a_1 + b_1 > c$ và $a_2 + b_2 > c$, số hạng đầu tiên lớn hơn $3c^2 d^2$. Vẫn còn phải kiểm tra xem số hạng thứ hai có nhỏ hơn $3c^2 d^2$ về giá trị tuyệt đối hay không. Sự tương ứng $|a_2 - a_1| < d$, $|b_2 - b_1| < d$ là hiển nhiên.

Hình 3

Bởi vì
$$p_1 p_2(d^2 - d_0^2) > (c^2 + 2c^2)d^2 -$$
$$- |c^2(a_2 - a_1)(b_2 - b_1)| -$$
$$- |a_1 b_2 - b_1 a_2|(|a_2 - a_1| +$$
$$+ |b_2 - b_1|)c > 3c^2 d^2 - c^2 d^2 -$$
$$- 2dc|a_1 b_2 - b_1 a_2| = 2c^2 d^2 -$$
$$- 2dc|a_1 b_2 - b_1 a_2|.$$

Dưới đây chúng ta sẽ chứng minh rằng $|a_1 b_2 - b_1 a_2| \leq cd$.

Do đó, vế phải của bất đẳng thức (4) là không âm.

Vì vậy, $d > d_0$.

Vì vậy, việc còn lại là chứng minh bổ đề sau.

Bổ đề. Cho điểm $C_2$ nằm tùy ý trong mặt phẳng của tam giác $ABC_1$. Sau đó (Hình 3)
$$|a_1 b_2 - b_1 a_2| \leq cd.$$

Bằng chứng. Chúng ta thả từ điểm $C_2$ đường vuông góc $C_2 P$, $C_2 Q$, $C_2 T$ đến các đường thẳng $BC_1$, $AC_1$, $AB$.

Một hình tròn có đường kính $AC_2$ có thể được mô tả xung quanh tứ giác $AQC_2 T$.

Vì $Q\hat{A}T = \alpha$, theo định lý sin, $|QT| = b_2 \sin \alpha$.

Tương tự xét các tứ giác $C_1 PC_2 Q$ và $PC_2 TB$, ta thu được $|PQ| = d \sin \gamma$ và $|PT| = a_2 \sin \beta$.

Gọi $R$ là bán kính của đường tròn ngoại tiếp tam giác $AC_1 B'$. Theo định luật sin, $\sin \gamma = \frac{c}{2R}$, $\sin \beta = \frac{b_1}{2R}$, $\sin \alpha = \frac{a_1}{2R}$. Hậu kỳ $|QT| = \frac{a_1 b_2}{2R}$, $|PT| = \frac{a_2 b_1}{2R}$, $|PQ| = \frac{cd}{2R}$.

Bất đẳng thức tam giác ngụ ý $|PT| - |QT| \leq |PQ|$; Đó là lý do tại sao

⟦folio 17⟧

Hình 4

mu sau khi thay thế các biểu thức cho $|QT|$, $|PT|$, $|PQ|$ và đơn giản hóa chúng ta nhận được

$$|a_1b_2-a_2b_1| \leq cd.$$

Bằng chứng thứ hai

Với chân đế $AB$ cố định, chúng ta sẽ di chuyển đồng đều đỉnh $C$ dọc theo đoạn $C_1C_2$ từ $C_1$ đến $C_2$. Trong trường hợp này, tâm $O$ của vòng tròn nội tiếp sẽ di chuyển dọc theo một đường nào đó từ $O_1$ đến $O_2$.

Bổ đề. Khi đỉnh $C$ di chuyển với tốc độ khác 0 thì tâm $O$ di chuyển với tốc độ thấp hơn.

Từ bổ đề này, suy ra rằng khi $C$ đi qua đoạn $C_1C_2$ với tốc độ không đổi, điểm $O$, chuyển động với tốc độ thấp hơn tại mỗi thời điểm, sẽ đi từ $O_1$ đến $O_2$ một đường đi ngắn hơn. Hơn nữa, đường dẫn trực tiếp $|O_1O_2|$ ngắn hơn $|C_1C_2|$.

Trước khi chứng minh bổ đề, chúng ta hãy xem xét bổ đề sau. Nếu đỉnh $C$ di chuyển với tốc độ $\vec{v} \neq 0$ thì các tia $BC$ và $AC$, chạy dọc theo các cạnh của tam giác, quay với một số vận tốc góc $\omega_1$ và $\omega_2$, và ít nhất một trong các vận tốc này không bằng 0. Hãy thống nhất các dấu: chúng ta coi vận tốc góc là dương nếu chùm tia quay theo chiều kim đồng hồ và âm nếu chùm tia quay ngược chiều kim đồng hồ.

Tốc độ $\vec{v}$ và $\omega_1$, $\omega_2$ có ​​liên quan với nhau. Nếu chúng ta loại bỏ vectơ $\vec{v} = \vec{CT}$ khỏi điểm $C$ (Hình 4), thì độ dài $|CP|$ hình chiếu của nó lên hướng vuông góc với tia $BC$ sẽ bằng $|\omega_1| \cdot |BC|$. (Đó là vì

Hình 5

tổng tốc độ chuyển động của điểm $C$ bao gồm tốc độ chuyển động của nó cùng với tia quay $BC$ và tốc độ chuyển động của nó dọc theo tia này.) Tương tự, độ dài $|CQ|$ của hình chiếu $\vec{v}$ theo hướng vuông góc với tia $AC$ bằng $|\omega_2| \cdot |AC|$. Có thể vẽ một đường tròn xung quanh tứ giác $CPTQ$. Hơn nữa, $\vec{v}$ bằng đường kính của hình tròn này.

Cách xây dựng tương tự có thể được thực hiện đối với tốc độ $\vec{v}_0$ chuyển động của tâm $O$, chỉ trong trường hợp này $[BC)$, $[AC)$ được thay thế bằng $[BO)$, $[AO)$ và $\omega_1$, $\omega_2$ được thay thế bằng $\frac{\omega_1}{2}$, $\frac{\omega_2}{2}$.

Ít nhất một trong các tốc độ $\omega_1$, $\omega_2$ không bằng 0. Ngoài ra, sự thay đổi đồng thời về dấu của $\omega_1$, $\omega_2$ sẽ đảo ngược hướng của $\vec{v}$ và $\vec{v}_0$ mà không làm thay đổi độ lớn của $\vec{v}$ và $\vec{v}_0$. Do đó, khi chứng minh bất đẳng thức $\|\vec{v}\| > \|\vec{v}_0\|$, không mất tính tổng quát, ta có thể giả sử $\omega_1 > 0$ và xét riêng ba trường hợp: $\omega_2 > 0$, $\omega_2 = 0$, $\omega_2 < 0$.

Trường hợp 1. Cho $\omega_2 > 0$. Chúng ta hãy xoay hình tứ giác $CPTQ$ bằng $90^\circ$ quanh điểm $C$ đến vị trí $CP'TQ'$ (Hình 5) và hình tứ giác $OP_0T_0Q_0$ quanh $O$ đến vị trí $OP'_0T'_0Q'_0$ và vẽ $(P'_0P'') \parallel (Q'_0Q'') \parallel (OC)$. Các điểm $P''$ và $Q''$ sẽ chia đôi các đoạn $CP'$, $CQ'$, vì $|CP'| / |CB| = \omega_1$ và $|OP'| / |OB| = \frac{\omega_1}{2}$.

Từ $\vec{v}$ - đường kính của hình tròn vẽ quanh một hình tam giác $CP'Q'$, MỘT $\vec{v}_0$ - Đường kính của hình tròn ngoại tiếp một hình tam giác $CP'Q'$, MỘT $\vec{v}_0$ - Đường kính của hình tròn ngoại tiếp một hình tam giác $CP'Q'$, MỘT $\vec{v}_0$ - đường kính của vòng tròn được mô tả

⟦folio 18⟧

Hình 6

Hình 7.

trượt quanh $OP'_0Q'_0$, chúng tôi có
$$|\vec{v}| = \frac{|P'_0Q'|}{\sin \gamma} = \frac{|P''Q''|}{\sin \frac{\gamma}{2} \cos \frac{\gamma}{2}},
$$
$$|\vec{v}_0| = \frac{|P'_0Q'|}{\sin \left(\frac{\pi}{2} + \frac{\gamma}{2}\right)} = \frac{|P'_0Q'|}{\cos \frac{\gamma}{2}}.$$

Đoạn $P'_0Q'_0$ nghiêng về đường phân giác $CO$ dốc hơn một trong các tia $AO$, $BO$, và thậm chí dốc hơn một trong các tia $AC$ và $BC$, nghiêng $CO$ một góc $\frac{\gamma}{2}$. Do đó, khoảng cách giữa các đường thẳng song song $P'_0P''$ và $Q'_0Q''$ vượt quá $|P'_0Q'_0| \sin \frac{\gamma}{2}$.

Hơn nữa, $|P''Q''| > |P'_0Q'_0| \sin \frac{\gamma}{2}$, cùng với (5) cho ra $|\vec{v}| > |\vec{v}_0|$.

Trường hợp 2. Đặt $\omega_2 = 0$ (Hình 6); sau đó $|CP| = \omega_1 |BC|$, $|OP_0| = \omega_1/2$, từ đâu $|\vec{v}| = \frac{\omega_1}{\sin \gamma} |BC|$, $|\vec{v}_0| =$

$$\frac{\omega_1}{2 \sin \frac{\gamma}{2}} |BO|.$$

Nhưng $|BC| > |BO|$ (vì $\angle BOC$ là ngu ngốc) và $\sin \gamma < 2 \sin \frac{\gamma}{2}$, do đó $|\vec{v}| > |\vec{v}_0|$.

Trường hợp 3. Cho $\omega_2 < 0$. Như trong trường hợp 1, chúng ta xoay các hình tứ giác $CPTQ$, $OP_0T_0Q_0$ theo $90^\circ$ đến các vị trí $CP'T'Q'$, $OP'_0T'Q'_0$ (Hình 7) và vẽ $(P'_0P'') \parallel (Q'_0Q'') \parallel (BD) \parallel (OC)$. Các điểm $P''$, $Q''$ lại nằm ở trung điểm của các đoạn $CP'$, $CQ'$.

Lần này một lần nữa
$$|\vec{v}| = \frac{|P'_0Q'|}{\sin (\pi - \gamma)} = \frac{|P''Q''|}{\sin \frac{\gamma}{2} \cos \frac{\gamma}{2}},
$$
$$|\vec{v}_0| = \frac{|P'_0Q'|}{\sin \left(\frac{\pi}{2} - \frac{\gamma}{2}\right)} = \frac{|P'_0Q'|}{\cos \frac{\gamma}{2}},
$$
và để đảm bảo rằng $|\vec{v}| > |\vec{v}_0|$, chúng ta chỉ cần kiểm tra xem trong trường hợp này
$$|P''Q''| > |P'_0Q'_0|.$$

Chúng ta hãy chuẩn bị đoạn $P''Q''$ với tâm $C$ để nó đi vào một đoạn nào đó $BM$. Tương tự, chúng ta hãy chuẩn bị đoạn $P'_0Q'_0$ với tâm $O$ để nó đi vào một đoạn nào đó $BN$. Điều quan trọng là các hệ số nấu phải giống nhau. Do đó, để chứng minh (6) chỉ cần chứng minh $|BM| > |BN|$ là đủ. Nhưng điều sau rõ ràng là tam giác $BNM$ có một góc tù ở đỉnh $N$. Thật vậy, nếu $N$ nằm bên trái của đường thẳng $BD$ thì $M\widehat{NB} > \widehat{COB} > \frac{\pi}{2}$, và nếu $N$ nằm bên phải của $BD$ thì $M\widehat{NB} > M\widehat{NO} = \widehat{COA} > \frac{\pi}{2}$. Bổ đề đã được chứng minh.

Bình luận. Từ bổ đề, dễ dàng suy ra rằng bất đẳng thức $|O_1O_2| < |C_1C_2|$ được bảo toàn, thứ nhất, nếu $C_1$, $C_2$ nằm trên các cạnh khác nhau của đường thẳng $AB$, và thứ hai, nếu các tam giác $ABC_1$, $ABC_2$ có đáy chung $AB$ nằm trong không gian trong các mặt phẳng khác nhau.

Câu hỏi. Hãy cố định đáy của hình tam giác và di chuyển phần trên của nó. Liệu tâm của quả cầu nội tiếp có chuyển động với tốc độ chậm hơn đỉnh không?
