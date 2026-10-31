---
id: 1975-2-gotman-pryamaya-eylera-f2f06c4e
issue: kvant_1975_2
year: 1975
number: "2"
title: Đường Euler
authors:
  - Готман Э. Г.
rubric: matematicheskiy-kruzhok
rubric_sub: Математический кружок
page_first: 22
page_last: 27
page_labels: 20-24
tag: MFX4
lang: vi
source: kvant_digital
extraction: vision
content_sha256: 8213375b0c6950f72edb3805dba2f214c42ed7134c1e06704f2c8d3d09179e35
prompt_sha256: draft-1
translated_from: content/ru/1975/02/articles/07_gotman-pryamaya-eylera-f2f06c4e.md
source_content_sha256: 3f3cbbb4899e8c4287d4fe9ea8a050319fb0733431448317e8680e62a75e8dfd
translation_model: draft
translation_run: vi-draft-2026-10-31
translation_quality: draft
---

⟦folio 20⟧

Các tính chất của hình tam giác đã được người Hy Lạp cổ đại nghiên cứu kỹ lưỡng.

Trong cuốn Elements quan trọng của Euclid, người ta đã chứng minh rằng tâm của một đường tròn ngoại tiếp một tam giác là giao điểm của điểm giữa các đường vuông góc với các cạnh của nó.

Archimedes, khi xác định vị trí trọng tâm của một tấm tam giác đồng nhất, đã phát hiện ra rằng nó nằm trên một trong ba đường trung tuyến. Giao điểm các đường trung tuyến của một tam giác gọi là tâm mềm hay tâm tam giác.

Sau đó người ta đã chứng minh được rằng ba đường cao của một tam giác cũng cắt nhau tại một điểm gọi là trực tâm của tam giác đó.

Sự đều đặn về vị trí của ba điểm đáng chú ý này của tam giác - tâm O của đường tròn ngoại tiếp, trọng tâm G và trực tâm H - lần đầu tiên được phát hiện bởi nhà toán học nổi tiếng Leonhard Euler (1707-1783). Trước tiên chúng ta hãy xem xét một trường hợp đặc biệt: tam giác vuông ABC (Hình 1).

O ở giữa cạnh huyền AB là tâm của đường tròn ngoại tiếp nó. Tâm G chia đường trung tuyến CO theo tỉ lệ 2:1 tính từ đỉnh C. Hai chân AC và BC là đường cao của tam giác nên đỉnh C của góc vuông trùng với trực tâm H của tam giác. Do đó, các điểm O, G, H nằm trên cùng một đường thẳng và $\overrightarrow{OH} = 3\overrightarrow{OG}$. Sử dụng phương pháp tọa độ, Euler đã chứng minh rằng có cùng một mối liên hệ giữa ba điểm đã chỉ ra hoặc về một tam giác. Chúng tôi sẽ chứng minh điều này bằng cách sử dụng vectơ và người đọc chỉ cần làm quen với các thao tác đơn giản nhất: cộng vectơ và nhân vectơ với một số.

Phân chia một đoạn trong một mối quan hệ nhất định

Cho A, B và O là các điểm của mặt phẳng và biết điểm G chia đoạn AB theo quan hệ k: $\frac{\overrightarrow{AG}}{\overrightarrow{GB}} = k$ (Hình 2). Chúng ta hãy biểu thị vectơ $\overrightarrow{OG}$ theo các vectơ $\overrightarrow{OA}$ và $\overrightarrow{OB}$. Để làm điều này, chúng ta thay thế biểu thức của tất cả các vectơ thành đẳng thức $\overrightarrow{AG} = k \times \overrightarrow{GB}$ thông qua $\overrightarrow{OG}$, $\overrightarrow{OA}$ và $\overrightarrow{OB}$: $\overrightarrow{OG} - \overrightarrow{OA} = k (\overrightarrow{OB} - \overrightarrow{OG})$. Giải phương trình này cho $\overrightarrow{OG}$, ta được

$$\overrightarrow{OG} = \frac{\overrightarrow{OA} + k\overrightarrow{OB}}{1 + k}.$$ (1)

Ví dụ: nếu G là trung điểm của đoạn $\overrightarrow{AB}$ thì $k = 1$ và $\overrightarrow{OG} = \frac{1}{2}(\overrightarrow{OA} + \overrightarrow{OB})$.

Định lý về giao điểm của các đường trung tuyến của một tam giác tại một điểm

Ở đây chúng ta thu được một đẳng thức vectơ mà chúng ta sẽ cần sau này.

⟦folio 21⟧

Định lý 1. Các thuốc nhất thời $ABC$ cắt nhau tại một điểm $G$ và chia theo tỷ lệ 2:1, tính từ đỉnh, và
$$3\overrightarrow{PG} = \overrightarrow{PA} + \overrightarrow{PB} + \overrightarrow{PC},$$
(2)
thức ăn $P$ - bất kỳ điểm nào trên mặt phẳng hoặc không gian.
Bằng chứng. Chúng ta lấy điểm $G$ trên đường trung tuyến $CD$ của tam giác $ABC$, được xác định bằng sự tương ứng $|CG| : |GD| = 2:1$ (Hình 3). Theo công thức (1),
$$\overrightarrow{PG} = \frac{\overrightarrow{PC} + 2\overrightarrow{PD}}{3},$$
$$\overrightarrow{PD} = \frac{1}{2} (\overrightarrow{PA} + \overrightarrow{PB}),$$
Ở đâu
$$\overrightarrow{PG} = \frac{1}{3} (\overrightarrow{PA} + \overrightarrow{PB} + \overrightarrow{PC}).$$
Bằng cách tính vectơ $\overrightarrow{PG}$ có điểm cuối tại điểm $G'$ chia một trong hai đường trung tuyến còn lại của tam giác theo tỷ lệ 2:1 (tính từ đỉnh), chúng ta thu được biểu thức tương tự ở bên phải:
$$\overrightarrow{PG'} = \frac{1}{3} (\overrightarrow{PA} + \overrightarrow{PB} + \overrightarrow{PC}),$$
tư thế $\overrightarrow{PG'} = \overrightarrow{PG}$ và điểm $G'$ trùng với điểm $G$. Do đó, cả ba đường trung tuyến của tam giác cắt nhau tại một điểm $G$, được xác định bằng sự tương ứng (2).

Định lý về đường cao của một tam giác tùy ý
Định lý 2. Các đường cao của tam giác $ABC$ cắt nhau tại một điểm $H$, và
$$\overrightarrow{OH} = \overrightarrow{OA} + \overrightarrow{OB} + \overrightarrow{OC},$$
(3)
thức ăn $O$ là tâm của đường tròn ngoại tiếp tam giác.
Bằng chứng. Cho $ABC$ là một tam giác không phải là tam giác vuông (Hình 4). Chúng ta hãy tìm tổng của các vectơ $\overrightarrow{OA}$ và $\overrightarrow{OB}$. Vì điều này

⟦folio 22⟧

chúng ta hãy dựng một điểm $M$ đối xứng với $O$ so với cạnh $AB$, sau đó $\overrightarrow{OM} = \overrightarrow{OA}+\overrightarrow{OB}$. Sau đó, chúng ta xây dựng điểm $H$, trong đó

$$\overrightarrow{OH} = \overrightarrow{OM}+\overrightarrow{OC} = \overrightarrow{OA}+\overrightarrow{OB}+\overrightarrow{OC},$$

và chứng minh rằng điểm $H$ là trực tâm của tam giác $ABC$.

Thật vậy, theo cách xây dựng, đường thẳng $CH$ và $OM$ song song, $OM$ là đường trung trực của đoạn $AB$, do đó đường thẳng $CH$ cũng vuông góc với đường thẳng $AB$ và điểm $H$ nằm ở độ cao của tam giác $ABC$ vẽ từ đỉnh $C$.

Nếu chúng ta lặp lại việc xây dựng, bắt đầu với vectơ $\overrightarrow{OA}$ và $\overrightarrow{OC}$, chúng ta sẽ nhận được cùng một điểm $H$, nhưng cách lập luận tương tự cho thấy rằng bây giờ điểm $H$ nằm trên đường cao của tam giác vẽ từ đỉnh $B$. Tương tự, chúng ta thấy rằng điểm $H$ nằm trên đường cao vẽ từ đỉnh $A$. Do đó, các đường cao của tam giác $ABC$ cắt nhau tại điểm $H$, được xác định theo hệ thức (3).

Dễ dàng kiểm tra được Định lý 2 cũng đúng với tam giác vuông.

**Đường thẳng Euler**

Từ Định lý 1 và 2 đã được chứng minh, chúng ta rút ra tính chất các điểm đáng chú ý của một tam giác mà chúng ta quan tâm.

Định lý 3. *Tâm $O$ của đường tròn ngoại tiếp, tâm $G$ và trực tâm $H$ của bất kỳ tam giác nào cùng nằm trên một đường thẳng và điểm $G$ nằm giữa các điểm $O$, $H$ và $|OG| : |GH| = 1 : 2$.*

Bằng chứng. Theo Định lý 1

$$3\overrightarrow{OG} = \overrightarrow{OA}+\overrightarrow{OB}+\overrightarrow{OC}.$$

So sánh đẳng thức này với đẳng thức (3), ta thu được

$$\overrightarrow{OH} = 3\overrightarrow{OG}.$$

Do đó, các vectơ $\overrightarrow{OH}$ và $\overrightarrow{OG}$, có chung nguồn gốc $O$, nằm ở vị trí

⟦column⟧

các bà vợ nằm trên cùng một đường thẳng và $|\overrightarrow{OG}| : |\overrightarrow{GH}| = 1 : 2$.

Đường thẳng chứa các điểm $O$, $G$ và $H$ được gọi là *Đường thẳng Euler*.

$$* \quad * \quad *$$

Trong phép đo lập thể, khối đa diện đơn giản nhất - tứ diện (hình chóp tam giác) đóng vai trò tương tự như hình tam giác trong phép đo mặt phẳng. Các tính chất của hình tam giác và hình tứ diện phần lớn giống nhau. Chúng ta hãy thử mở rộng tính chất các điểm đáng chú ý của một tam giác thành một tứ diện.

**Hình cầu ngoại tiếp một tứ diện**

Người ta biết rằng xung quanh bất kỳ tứ diện nào người ta có thể mô tả một hình cầu, tâm của nó $O$ nằm trên đường vuông góc với các mặt của tứ diện, dựng tại tâm của các đường tròn được mô tả xung quanh các mặt.

**Các đường trung bình của tứ diện**

Đoạn nối đỉnh của tứ diện với trọng tâm của mặt đối diện được gọi là *trung tuyến* của tứ diện. Tính chất các đường trung tuyến của một tứ diện cũng giống như tính chất của các đường trung tuyến của một tam giác.

Định lý 4. *Bốn đường trung tuyến của tứ diện $ABCD$ cắt nhau tại một điểm $G$, chia mỗi đường trung tuyến đó theo tỷ lệ $3:1$, tính từ đỉnh của tứ diện và*

$$4\overrightarrow{PG} = \overrightarrow{PA}+\overrightarrow{PB}+\overrightarrow{PC}+\overrightarrow{PD}, \quad (4)$$

*trong đó $P$ là điểm bất kỳ trong không gian.*

Bằng chứng. Chúng ta lấy điểm $G$ trên đường trung tuyến $DG_1$ của tứ diện $ABCD$, được xác định bởi hệ thức $|DG| : |GG_1| = 3:1$ (Hình 5). Theo công thức (1),

$$\overrightarrow{PG} = \frac{\overrightarrow{PD}+3\overrightarrow{PG_1}}{4}.$$

Xét rằng trọng tâm $G_1$ của tam giác $ABC$ thỏa mãn hệ thức $3\overrightarrow{PG_1} = \overrightarrow{PA}+\overrightarrow{PB}+\overrightarrow{PC}$, ta thu được

⟦folio 23⟧

$$\vec{PG} = \frac{1}{4}\left(\vec{PA} + \vec{PB} + \vec{PC} + \vec{PD}\right).$$

Bằng cách tính vectơ $\vec{PG'}$ có điểm cuối tại điểm $G'$ chia bất kỳ đường trung tuyến nào trong ba đường trung tuyến còn lại của tứ diện theo tỷ lệ $3:1$ (tính từ đỉnh), chúng ta thu được biểu thức tương tự. Điều này có nghĩa là cả bốn đường trung tuyến của tứ diện cắt nhau tại một điểm $G$, thỏa mãn hệ thức (4). Điểm $G$ được gọi là *trọng tâm* (hoặc *trọng tâm*) của tứ diện.

**Chiều cao tứ diện**

Các đường cao của tam giác luôn cắt nhau tại một điểm. Bằng cách tương tự, chúng ta có thể giả sử rằng chiều cao của bất kỳ tứ diện nào cũng giao nhau tại một điểm. Tuy nhiên, điều này không đúng.

Ví dụ: hãy xem xét một tứ diện $ABCD$ có góc nhị diện vuông ở cạnh $AB$, trong đó $|AC| = |BC|$ nhưng $|AD| \neq |BD|$ (Hình 6). Độ cao $CE$ và $DF$ của khối tứ diện lần lượt nằm trên các mặt $ABC$ và $ABD$, nhưng điểm $E$ là giữa $AB$, còn $F$ thì không. Nếu độ dài của các cạnh $DA$ và $DB$ bằng nhau thì đáy $E$ và $F$ của các chiều cao sẽ trùng nhau, nhưng hai chiều cao còn lại của tứ diện không thể đi qua điểm $E$.

Vì vậy, ngay cả hai chiều cao của một tứ diện cũng có thể không có điểm chung.

Tuy nhiên, cũng có các khối tứ diện, tất cả bốn chiều cao đều giao nhau tại một điểm. Ví dụ: đây sẽ là tứ diện $ABCD$ với các góc vuông ở đỉnh $D$. Các cạnh $DA$, $DB$ và $DC$ là độ cao của nó và đỉnh $D$ là *trực tâm* (điểm giao nhau của cả bốn độ cao).

Chúng ta hãy cố gắng tìm tất cả các tứ diện có chiều cao cắt nhau tại một điểm.

Để các đường cao của tứ diện $ABCD$ vẽ từ các đỉnh $C$ và $D$ cắt nhau tại điểm $H$ (Hình 7). Khi đó $CH_1 \perp AB$ và $DH_2 \perp AB$ tức là đường thẳng $AB$ vuông góc với hai đường thẳng đó

⟦column⟧

⟦figure⟧
Cơm. 5.

⟦figure⟧
Cơm. 6.

⟦figure⟧
Cơm. 7.

⟦figure⟧
Cơm. 8.

**23**

⟦folio 24⟧

cắt nhau bởi một đường thẳng nằm trong mặt phẳng CDH, do đó AB⊥CD. Người ta chứng minh tương tự rằng nếu hai đường cao còn lại của khối tứ diện ABCD đi qua cùng một điểm H thì AC⊥BD và AD⊥BC. Vì vậy, nếu tất cả các chiều cao của một khối tứ diện giao nhau tại một điểm thì các cạnh đối diện của khối tứ diện vuông góc với nhau. Một khối tứ diện như vậy được gọi là trực tâm.

Định lý 5. Nếu các đường cao của khối tera hedron ABCD trực tâm cắt nhau tại một điểm thì các cạnh đối diện của khối tera hedron vuông góc với nhau. Một khối tứ diện như vậy được gọi là trực tâm.

Định lý 5. Nếu các đường cao của khối tera hedron ABCD trực tâm cắt nhau tại một điểm thì các cạnh đối diện của khối tera hedron vuông góc với nhau. Một khối tứ diện như vậy được gọi là trực tâm.

Cho ABCD là một khối tứ diện trực tâm, DG₁ là đường trung tuyến, DH₁ chiều cao của nó (Hình 8). Khi đó G₁ là trọng tâm và H₁ là trực tâm của tam giác ABC (bạn hãy tự chứng minh điều này - đây là nơi sử dụng độ vuông góc của các cạnh đối diện của khối tứ diện) và các điểm O₁ (tâm của đường tròn ngoại tiếp tam giác ABC), G₁ và H₁ nằm trên cùng một đường thẳng. Lưu ý rằng tâm O của hình cầu ngoại tiếp khối lục giác ABCD nằm trên đường vuông góc với mặt phẳng của tam giác ABC, được phục hồi tại điểm O₁.

Chúng ta sẽ chứng minh định lý tương tự như Định lý 2 cho tam giác: dựng điểm H theo nhiều cách khác nhau thỏa mãn (5).

Đầu tiên, thêm các vectơ $\overrightarrow{OA}$, $\overrightarrow{OB}$ và $\overrightarrow{OC}$:

$$\overrightarrow{OM} = \overrightarrow{OA} + \overrightarrow{OB} + \overrightarrow{OC}.$$

Theo Định lý 1 $\overrightarrow{OG}_1 = \frac{1}{3}(\overrightarrow{OA} + \overrightarrow{OB} + \overrightarrow{OC})$, do đó $\overrightarrow{OM} = 3\overrightarrow{OG}_1$ hoặc $\overrightarrow{G}_1\overrightarrow{M} = 2\overrightarrow{OG}_1$. Các điểm O₁, G₁, H₁ nằm trên đường thẳng Euler của tam giác ABC và $\overrightarrow{H}_1\overrightarrow{G}_1 = 2\overrightarrow{G}_1\overrightarrow{O}_1$. Kể từ đây,

$$\overrightarrow{OH} = \frac{1}{2}(\overrightarrow{OM} + \overrightarrow{OD}) = \frac{1}{2}(\overrightarrow{OA} + \overrightarrow{OB} + \overrightarrow{OC} + \overrightarrow{OD})$$

Từ đó suy ra các đường thẳng H₁M và OO₁ song song và vì đường thẳng OO₁ vuông góc với mặt phẳng ABC nên đường thẳng H₁M vuông góc với mặt phẳng này. Do đó, điểm M nằm trên đường thẳng DH₁ (nếu điểm O và O₁ trùng nhau thì điểm M và H₁ cũng trùng nhau).

Giả sử định lý $\overrightarrow{OH} = \frac{1}{2}(\overrightarrow{OM} + \overrightarrow{OD}) = \frac{1}{2}(\overrightarrow{OA} + \overrightarrow{OB} + \overrightarrow{OC} + \overrightarrow{OD})$ Từ đẳng thức bên trái suy ra điểm H là trung điểm của đoạn DM, tức là điểm H nằm ở độ cao DH₁ của khối tứ diện.

Tương tự, điểm N được dựng: $\overrightarrow{ON} = \overrightarrow{OA} + \overrightarrow{OB} + \overrightarrow{OD}$ và $\overrightarrow{H}:\overrightarrow{OH} = \frac{1}{2}(\overrightarrow{ON} + \overrightarrow{OC})$ và người ta chứng minh rằng điểm H nằm trên đường cao của khối tứ diện vẽ từ đỉnh C, v.v.

Do đó, chiều cao của khối tứ diện trực tâm giao nhau tại một điểm H, được xác định bởi (5) tương ứng.

Đường Euler của tứ diện

Định lý 6. cenir O của hình cầu ngoại tiếp, cenirod G và khối tứ diện trực tâm ABCD cùng nằm trên một đường thẳng, hai điểm O và H đối xứng nhau qua điểm G.

Bằng chứng. Theo công thức (4) và (5)

$$\overrightarrow{OH} = \frac{1}{2}(\overrightarrow{OA} + \overrightarrow{OB} + \overrightarrow{OC} + \overrightarrow{OD}),$$

$$\overrightarrow{OG} = \frac{1}{4}(\overrightarrow{OA} + \overrightarrow{OB} + \overrightarrow{OC} + \overrightarrow{OD}),$$

từ đâu $\overrightarrow{OH} = 2\overrightarrow{OG}$. Sự đẳng thức thu được có nghĩa là các điểm O, G, H nằm trên cùng một đường thẳng và các điểm O và H đối xứng với điểm G.

⟦folio none⟧

Đường thẳng chứa các điểm $O$, $G$, $H$ có ​​thể được gọi là *đường thẳng Euler của một tứ diện trực tâm.*

Bài tập

Giải bằng cách sử dụng tích vô hướng của vectơ bài toán 1-4.

1. a) Chứng minh rằng nếu $O$ là tâm của đường tròn ngoại tiếp tam giác $ABC$ và $\overrightarrow{OH} = \overrightarrow{OA} + \overrightarrow{OB} + \overrightarrow{OC}$ thì $H$ là giao điểm các đường cao của tam giác.

b) Chứng minh rằng nếu $O$ là tâm của hình cầu ngoại tiếp tứ diện trực tâm $ABCD$ và $\overrightarrow{OH} = {}^{1}\!/_{2}(\overrightarrow{OA} + \overrightarrow{OB} + \overrightarrow{OC} + \overrightarrow{OD})$ thì $H$ là giao điểm của bốn đường cao của tứ diện.

2. Chứng minh rằng nếu $A$, $B$, $C$ và $D$ là bốn điểm tùy ý trong không gian thì

$\overrightarrow{AB} \cdot \overrightarrow{CD} + \overrightarrow{BC} \cdot \overrightarrow{AD} + \overrightarrow{CA} \cdot \overrightarrow{BD} = 0.$

Sử dụng đẳng thức này, chứng minh rằng

a) Ba đường cao của một tam giác cắt nhau tại một điểm;

b) nếu các cạnh đối diện $AB$ và $CD$, $AD$ và $BC$ của tứ diện $ABCD$ vuông góc thì các cạnh $CA$ và $BD$ cũng vuông góc.

3. Chứng minh rằng nếu $A$, $B$, $C$, $D$ là bốn điểm tùy ý trong không gian thì

$$|AB|^2 + |CD|^2 - |AD|^2 - |BC|^2 = 2\overrightarrow{AC} \cdot \overrightarrow{DB}.$$

Sử dụng đẳng thức này, chứng minh rằng

a) tổng bình phương các đường chéo của hình thang bằng tổng bình phương các cạnh bên của nó cộng với hai lần tích hai đáy;

b) các đường chéo của một tứ giác vuông góc khi và chỉ khi tổng các bình phương của các cạnh đối diện bằng nhau;

⟦column⟧

c) Để một tứ diện là trực tâm thì điều cần và đủ là tổng các bình phương của các cạnh đối diện của nó bằng nhau.

4. Chứng minh rằng tất cả các góc phẳng tại một đỉnh của tứ diện trực tâm đều là nhọn, vuông hoặc tù và ít nhất một trong các mặt của nó là tam giác nhọn.

5. a) Chứng minh rằng các điểm đối xứng với trực tâm $H$ của tam giác $ABC$ so với trung điểm các cạnh của nó, cũng như các điểm đối xứng với trực tâm $H$ đối với các đường thẳng $BC$, $CA$ và $AB$, đều nằm trên đường tròn ngoại tiếp tam giác này.

b) Gọi $H$ lần lượt là trực tâm của tứ diện $ABCD$, $G_1$ và $H_1$ là trọng tâm và trực tâm của mặt $ABC$, và $G_2$ và $H_2$ các điểm sao cho $\overrightarrow{HG_2} = 3\overrightarrow{HG_1}$ và $\overrightarrow{HH_2} = 3\overrightarrow{HH_1}$. Chứng minh rằng các điểm $G_2$ và $H_2$ nằm trên mặt cầu ngoại tiếp tứ diện này.

6. a) Chứng minh rằng trung điểm của ba cạnh, đáy của ba đường cao của tam giác và trung điểm của các đoạn nối trực tâm với ba đỉnh nằm trên cùng một đường tròn và tâm của đường tròn này (gọi là *đường tròn mười điểm*) nằm trên đường thẳng Euler.

b) Chứng minh rằng trọng tâm của bốn mặt, các đáy của bốn đường cao của tứ giác trực tâm và các điểm phân chia mỗi đoạn thẳng nối trực tâm với các đỉnh, theo tỷ lệ 1:2 (tính từ trực tâm), nằm trên cùng một mặt cầu và tâm của mặt cầu này (gọi là *hình cầu mười hai điểm*) nằm trên đường thẳng Euler.

7. Chứng minh rằng

a) nếu đáy của một trong các đường cao của tứ diện là trực tâm của mặt tương ứng thì tứ diện đó là trực tâm;

b) Đáy của bất kỳ đường cao nào của một tứ diện trực tâm là trực tâm của mặt tương ứng (các tính chất này đã được sử dụng trong chứng minh Định lý 5).

---
