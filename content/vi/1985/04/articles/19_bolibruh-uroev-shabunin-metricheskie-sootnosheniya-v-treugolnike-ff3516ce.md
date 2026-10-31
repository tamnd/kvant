---
id: 1985-4-bolibruh-uroev-shabunin-metricheskie-sootnosheniya-v-treugolnike-ff3516ce
issue: kvant_1985_4
year: 1985
number: "4"
title: Các tỉ số trong tam giác
authors:
  - Болибрух А. А.
  - Уроев В. М.
  - Шабунин М. И.
rubric: praktikum-abiturienta
rubric_sub: Практикум абитуриента
page_first: 50
page_last: 52
page_labels: 48-50
tag: TSKU
lang: vi
source: kvant_digital
extraction: vision
content_sha256: 77824aca48e55b2fa3f389496aa275422ea2aaa11d55088d69826a88aac4251d
prompt_sha256: draft-1
translated_from: content/ru/1985/04/articles/19_bolibruh-uroev-shabunin-metricheskie-sootnosheniya-v-treugolnike-ff3516ce.md
source_content_sha256: 080d977e5b4ed50150a1c47669504e70d0aabd66f5300868419c35d35be82cbf
translation_model: draft
translation_run: vi-draft-2026-10-31
translation_quality: draft
---

⟦folio 48⟧

Các tỉ số trong tam giác

Ứng viên Khoa học Vật lý và Toán học A. A. BOLIBRUKH,
Ứng viên Khoa học Vật lý và Toán học V. M. UROEV,
Giáo sư M. I. SHABUNIN

Kinh nghiệm tổ chức thi đại học cho thấy nhiều thí sinh không đủ tên lời giải hình học bài toán. Phép đo phẳng đơn giản nhất bài toán đôi khi trở thành trở ngại ngay cả đối với những ứng viên giải thành công các câu hỏi về đại số và lượng giác. Hơn nữa, điều này không chỉ áp dụng cho các nhiệm vụ cho lời giải cần thể hiện sự khéo léo nhất định nhưng cũng phải giải các bài toán sử dụng các định lý, công thức tiêu chuẩn của môn học ở trường như định lý cosine, định lý sin, công thức tính diện tích tam giác, v.v.

Hiện tại, bài toán đang được xem xét trong đề xuất chính trong các năm khác nhau cho kỳ thi tuyển sinh tại MIPT. Từ một lượng tài liệu lớn, các tác giả đã chọn bài toán, với lời giải sử dụng các mối quan hệ số liệu cơ bản giữa các phần tử của tam giác.

Hãy viết ra những mối quan hệ này. Khoảng cách là tam giác ABC và đưa ra các ký hiệu sau: $a = |BC|$, $b = |AC|$, $c = |AB|$, $R$ - bán kính của đường tròn ngoại tiếp tam giác ABC, $r$ - bán kính của đường tròn nội tiếp, $h_a$ - chiều dài của đường cao hạ xuống cạnh BC, $S$ - diện tích của tam giác. Sau đó

$$\frac{a}{\sin \hat{A}} = \frac{b}{\sin \hat{B}} = \frac{c}{\sin \hat{C}} = 2R$$

(định lý sin), (I)

$$a^2 = b^2 + c^2 - 2bc \cos \hat{A}$$

(định lý cosin), (II)

$$S = \frac{1}{2} h_a a,$$

(III)

$$S = \frac{1}{2} bc \sin \hat{A},$$

(IV)

$$S = \frac{1}{2} (a + b + c) r.$$

(V)

Người nộp đơn phải biết các công thức này, có thể chứng minh chúng và áp dụng chúng ở lời giải bài toán. Có những công thức khác mà người lập trình không còn cung cấp kiến ​​thức để xây dựng chúng nữa nhưng thường hữu ích cho lời giải bài toán. Ví dụ: công thức Heron

$$S = \sqrt{p(p-a)(p-b)(p-c)},$$

(VI)

trong đó $p = (a + b + c)/2$ là mét của tam giác hoặc công thức

$$S = \frac{abc}{4R},$$

(VII)

có thể dễ dàng thu được bằng cách thay thế giá trị của sin $\hat{A}$, tìm được từ định lý sin (I), vào công thức (IV).

Hãy bắt đầu với bài toán về việc áp dụng định lý sin.

1. Trong tam giác đều ABC ($|AB| = |BC|$), đường trung tuyến AD và đường phân giác CE vuông góc. Xác định góc ADB.

Lời giải. Đặt $\alpha$ là góc mong muốn, $O$ là giao điểm của các đoạn AD và CE (hình 1). Trong đường phân giác $\triangle ADC$ CO cũng là độ cao, nghĩa là $\triangle ADC$ là cạnh đều và $D\hat{AC} = A\hat{DC} = \pi - \alpha$, $\hat{A} = \hat{C} = 2\alpha - \pi$, $B\hat{AD} = \hat{A} - D\hat{AC} = 3\alpha - 2\pi$. Cho tam giác ABD thỏa điều kiện $|BD| = 1/2 |AB|$. Áp dụng định lý sin, ta thu được $\frac{|AB|}{\sin \alpha} = \frac{|BD|}{\sin (3\alpha - 2\pi)}$, từ đó $\frac{1}{\sin \alpha} = \frac{1}{2 \sin 3\alpha}$, $2 \sin 3\alpha = \sin \alpha$, $2 \sin \alpha (3 - 4 \sin^2 \alpha) = \sin \alpha$, $\sin^2 \alpha = 5/8$. Nhưng từ điều kiện bài toán thì suy ra $D\hat{CO} = \alpha - \pi/2 > 0$, mặt khác, $\alpha < \pi$, tức là $\pi/2 < \alpha < \pi$, do đó $\sin \alpha = \sqrt{10}/4$, $\alpha = \pi - \arcsin \sqrt{10}/4$.

Đáp số: $\pi - \arcsin \sqrt{10}/4$.

2. Trong tam giác đều ABC, độ dài đường cao BD hạ xuống đáy bằng h và bán kính của đường tròn ngoại tiếp bằng r. Tìm bán kính của đường tròn ngoại tiếp tam giác này.

⟦folio 49⟧

Lời giải. Đặt $O$ là tâm của đường tròn nội tiếp, $E$ điểm tiếp tuyến của đường tròn với đoạn $AB$, $|AC| = b$ (hình 2). Theo định luật sin, bán kính $R$ của đường tròn ngoại tiếp là $\frac{b}{2 \sin \hat{B}}$. Từ $\triangle BOE$ có $\sin \frac{\hat{B}}{2} = \frac{|OE|}{|OB|} = \frac{r}{h-r}$. Mặt khác, $\tg \frac{\hat{B}}{2} = \frac{|AD|}{|BD|} = \frac{b}{2h}$, từ đây
$$b = 2h \text{ tg} \frac{\hat{B}}{2} \text{ и } R = \frac{h \text{ tg} \frac{\hat{B}}{2}}{\sin \hat{B}} = \frac{h}{2 \cos^2 \frac{\hat{B}}{2}} = \frac{(h-r)^2}{2(h-2r)}$$
Đáp số: $\frac{(h-r)^2}{2(h-2r)}$.

3. Các góc tại đỉnh $A$ và $C$ của tam giác $ABC$ lần lượt là $\pi/4$ và $\pi/6$. Tìm góc giữa chiều cao $BD$ và đường trung tuyến $BE$ của tam giác này.

Lời giải. Hãy biểu thị $|AB| = c$, $|AC| = b$, $DBE = \varphi$ (hình 3). Sau đó $|AD| = c \cos \hat{A} = c \sqrt{2}/2$, $|DE| = |BD| \times \text{tg} \varphi = (c \sqrt{2} \text{ tg} \varphi)/2$. Vì vậy, $b/2 = |AE| = |AD| + |DE| = c \sqrt{2} \times (1 + \text{tg} \varphi)/2$. Theo định lý sin cho $\triangle ABC$ chúng ta thu được $\frac{c}{\sin \hat{C}} = \frac{b}{\sin \hat{B}}$, trong đó
$$\sin \hat{B} = \sin (\pi - \hat{A} - \hat{C}) = \sin (\hat{A} + \hat{C}) = \sin \frac{\pi}{6} \cos \frac{\pi}{4} + \cos \frac{\pi}{6} \sin \frac{\pi}{4} = \frac{\sqrt{2}}{4} \times (1 + \sqrt{3}).$$
Từ đây là
$$\frac{c}{1/2} = \frac{4c(1 + \text{tg} \varphi)}{1 + \sqrt{3}}, \text{tg} \varphi = \frac{\sqrt{3} - 1}{2}.$$
Đáp số: $\arctg \frac{\sqrt{3} - 1}{2}$.

Đối với lời giải theo sau bài toán định lý cosin được sử dụng.

4. Các đường phân giác $AD$ và $CF$ của tam giác $ABC$ cắt các cạnh $BC$ và $AB$ lần lượt tại các điểm $D$ và $F$. Tìm độ dài của đoạn $FD$ nếu $|AC| = 6$, $|AF| = 2$, $|CD| = 3$.

Lời giải. Chúng ta biểu thị $|BD| = x$, $|BF| = y$ (hình 4). Chúng ta hãy sử dụng một tính chất quan trọng của đường phân giác: đường phân giác chia cạnh của tam giác thành các phần tỉ lệ với độ dài các cạnh liền kề. Do đó, $|AB|/|AC| = x/3$, $|BC|/|AC| = y/2$ hoặc $(2+y)/6 = x/3$, $(x+3)/6 = y/2$, từ đó $x=9/5$, $y=8/5$, $|AB|=18/5$, $|BC|=24/5$. Để tính $|DF|$ chúng ta sử dụng định lý cosin cho $\triangle FBD$.

$$|DF|^2 = x^2 + y^2 - 2xy \cos \hat{B},$$
trong đó $\cos \hat{B}$ lần lượt được tìm thấy từ sự tương ứng $|AC|^2 = |AB|^2 + |BC|^2 - 2|AB| \cdot |BC| \cos \hat{B}$. Thay thế

⟦folio 50⟧

Cho độ dài cạnh $\triangle ABC$, chúng ta thu được $36 = \frac{18^2}{25} + \frac{24^2}{25} - \frac{2 \cdot 18 \cdot 24}{25} \times \cos \hat{B}$, từ đó $\cos \hat{B} = 0$, $\hat{B} = \pi/2$, $|DF| = \sqrt{145}/5$.

Đáp số: $\sqrt{145}/5$.

5. Trong tam giác $ABC$: $\hat{B} = \arccos \frac{7}{8}$, $|AC| = b$ và chiều cao giảm từ đỉnh $B$ bằng tổng của hai chiều cao còn lại. Tìm diện tích tam giác $ABC$.

Lời giải. Đặt $|AB| = x, |BC| = y$ (hình 5). Khi đó theo định lý cosine $b^2 = x^2 + y^2 - 2xy \cos \hat{B} = x^2 + y^2 - \frac{7}{4}xy$.

(3)

Tiếp theo, $h_b = \frac{2S}{b}$, $h_x = \frac{2S}{x}$, $h_y = \frac{2S}{y}$, trong đó $S$ là diện tích của $\triangle ABC$ và $h_b, h_x, h_y$ là chiều cao của nó. Vì theo điều kiện bài toán $h_b = h_x + h_y$, thì $\frac{1}{b} = \frac{1}{x} + \frac{1}{y}$ hoặc $x + y = \frac{xy}{b}$, do đó $x^2 + y^2 = \frac{(xy)^2}{b^2} - 2xy$. Từ đây và từ phương trình (3), chúng ta thu được phương trình cho $z = xy$:

$$b^2 = \frac{z^2}{b^2} - 2z - \frac{\tau}{4}z,$$

từ đâu $z = xy = 4b^2$. Vì vậy $S = \frac{xy \sin \hat{B}}{2} = \sqrt{15}/4 b^2$.

Đáp số: $\frac{\sqrt{15}}{4} b^2$.

Một lưu ý về định lý cosine. Sử dụng định lý cosin, dễ dàng thu được công thức biểu thị độ dài đường trung tuyến theo độ dài cạnh của tam giác. Chúng ta biểu thị $|AB| = c$, $|AC| = b$, $|BC| = a$, độ dài của đường trung tuyến $AD$ bằng $m_a$, $BDA = \varphi$ (hình 6). Sử dụng định lý cosin cho tam giác $ABD$ và $ADC$ ta thu được:

$$a^2/4 + m_a^2 - am_a \cos \varphi = c^2,$$
$$a^2/4 + 2m_a^2 - am_a \cos (\pi - \varphi) = b^2.$$

Cộng các phương trình này và sử dụng $\cos (\pi - \varphi) = -\cos \varphi$, chúng ta tìm được $a^2/2 + 2m_a^2 = c^2 + b^2$, từ đâu

$$m_a = \frac{1}{2} \sqrt{2(b^2 + c^2) - a^2}.$$

6. Trong tam giác $ABC$ các cạnh của quan hệ liên quan $|BC|^2 + |AC|^2 = 5|AB|^2$ dài. Tìm góc giữa medinas $AM$ và $BN$.

Lời giải. Hãy biểu thị $|AB| = c$, $|BC| = a$, $|AC| = b$, $NOM = \varphi$, $AM| = m_a$, $BN| = m_b$ (hình 7). Vì tại giao điểm các đường trung tuyến được chia theo tỷ lệ 2:1 tính từ đỉnh nên theo công thức (4) ta thu được:

$$|OM| = \frac{m_a}{3} = \frac{1}{6} \sqrt{2(b^2 + c^2) - a^2},$$
$$ON = \frac{m_b}{3} = \frac{1}{6} \sqrt{2(a^2 + c^2) - b^2}.$$

Hình 10. Hình 11. Hình 12.
