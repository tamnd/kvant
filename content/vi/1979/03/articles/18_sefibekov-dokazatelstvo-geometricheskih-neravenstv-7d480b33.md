---
id: 1979-3-sefibekov-dokazatelstvo-geometricheskih-neravenstv-7d480b33
issue: kvant_1979_3
year: 1979
number: "3"
title: Chứng minh bất đẳng thức hình học
authors:
  - Сефибеков С. Р.
rubric: raznoe
rubric_sub: Разное
page_first: 53
page_last: 55
page_labels: 51, 53
tag: EXHL
lang: vi
source: kvant_digital
extraction: vision
content_sha256: 7a4db5faffbfb11c9029fef0be407bdcb8805f03dd22fe37ca3516dca3d285a7
prompt_sha256: draft-1
translated_from: content/ru/1979/03/articles/18_sefibekov-dokazatelstvo-geometricheskih-neravenstv-7d480b33.md
source_content_sha256: 6b546bab066a8d5115575709b6ad8a6ba1f7238474d34ee2d01e11d776eeea17
translation_model: draft
translation_run: vi-draft-2026-10-31
translation_quality: draft
---

⟦folio 51⟧

S. Sefibekov

Chứng minh bất đẳng thức hình học

Trong các bài toán, ví dụ sau thường hữu ích: tìm cùng một đại lượng theo hai cách và đánh đồng các biểu thức thu được của nó. Ví dụ, chúng ta hãy tìm diện tích của một hình nhất định theo hai cách. Nếu một trong các biểu thức tính diện tích bao gồm sin của một góc nào đó $\alpha$, thì khi sử dụng sự tương ứng $\sin \alpha \leq 1$ từ đẳng thức thu được, chúng ta có thể thu được một số bất đẳng thức thú vị. Trong bài viết của S. Sefibekov, ví dụ này đã được sử dụng xuyên suốt bài toán. Những bài toán này dành cho học sinh lớp 8, nhưng chúng cũng rất thú vị đối với các ứng viên đại học - bài toán loại này được tìm thấy trong các bài kiểm tra vấn đáp.

Chìa khóa của lời giải bên dưới bài toán là ba công thức tính diện tích. Như đã biết (“Hình học 8”, đoạn 108), diện tích của một hình tam giác bằng một nửa tích của hai (bất kỳ) cạnh nào của nó và sin của góc giữa chúng:

$$S = \frac{1}{2} ab \sin \alpha$$

Từ đó suy ra diện tích của một tứ giác lồi bằng một nửa tích hai đường chéo của nó và sin của góc giữa chúng*):

$$S = \frac{1}{2} l_1 l_2 \sin \alpha.$$

Chứng minh rằng diện tích của đa giác ngoại tiếp

*) Tại sao không cần xác định góc nào giữa hai đường chéo sẽ được xét?

$$S = \frac{1}{2} Pr.$$

Bài toán 1. Chứng minh rằng tích của hai tam giác cạnh bất kỳ không nhỏ hơn tích của chu vi và bán kính của đường tròn nội tiếp: $ab \geq Pr$.

Lời giải. Chỉ cần đánh đồng các biểu thức (1) và (3) cho diện tích của tam giác và tính đến $\sin \alpha \leq 1$ là đủ.

Bình luận. Từ lời giải rõ ràng là nếu góc giữa các cạnh có độ dài $a$ và $b$ không thẳng thì $ab > Pr$.

Từ bất đẳng thức (4) và sự thay thế, nó suy ra điều đó cho bất kỳ tam giác nào

$$ab + bc + ca > 3Pr.$$

Bài toán 2. Chứng minh rằng bán kính $R$ của đường tròn ngoại tiếp một tam giác tùy ý, bán kính $r$ của đường tròn ngoại tiếp và chu vi của nó $P$ thỏa mãn bất đẳng thức

a) $R > \frac{\sqrt{3}}{3} \sqrt{Pr}$,

tam giác đó là nhọn hay tù;

b) $R \geq \frac{\sqrt{2}}{2} \sqrt{Pr}$,

nếu tam giác vuông.

Lời giải. a) Nối tâm $O$ của đường tròn ngoại tiếp với các đỉnh của tam giác.

Đối với tam giác nhọn (Hình 1)

$$S_{ABC} = S_{AOB} + S_{BOC} + S_{COA}.$$

Hình 1.

⟦folio 53⟧

Mặt khác, theo công thức (1)
$$S_{AOB} = \frac{1}{2} |OA| \cdot |OB| \cdot \sin \widehat{AOB}. \quad (18)$$
TỪ (17) và (18)
$$P_1 r_1 \leq |OA| \cdot |OB|. \quad (19)$$
Tương tự như vậy,
$$P_2 r_2 \leq |OB| \cdot |OC|, \quad (20)$$
$$P_3 r_3 \leq |OC| \cdot |OD|, \quad (21)$$
$$P_4 r_4 \leq |OD| \cdot |OA|. \quad (22)$$
TỪ (19) - (22) dễ dàng thu được bất đẳng thức cần tìm.
Sự bình đẳng đạt được khi $[AC] \perp [BD]$. Từ (16) và (13) dễ dàng suy ra bất đẳng thức:
$$S_{AOB} \cdot S_{BOC} \cdot S_{COD} \cdot S_{DOA} \leq \frac{1}{16} |OA|^2 \cdot |OB|^2 \cdot |OC|^2 \cdot |OD|^2.$$
Bài toán 5. Chứng minh rằng tứ giác lồi ABCD có bất đẳng thức sau:
$$S_{ABCD} \leq \frac{a^2 + b^2 + c^2 + d^2}{4}, \quad (23)$$
thức ăn $a, b, c, d$—độ dài cạnh của nó.
Lời giải. Hãy phá vỡ nó. Một đường chéo tứ giác thành hai hình tam giác (Hình 3). Sau đó
$$S_{ABCD} = S_{ABC} + S_{ADC}.$$
Theo công thức (1)
$$S_{ABC} = \frac{1}{2} ab \sin \widehat{B}.$$

Từ đây và từ bất đẳng thức $ab \geq \frac{a^2 + b^2}{2}$ ta thu được
$$S_{ABC} \leq \frac{a^2 + b^2}{4}. \quad (24)$$
Tương tự như vậy
$$S_{ADC} \leq \frac{c^2 + d^2}{4}. \quad (25)$$
Từ (24) và (25) ta thu được bất đẳng thức cần tìm.
Nếu $\widehat{B} = \widehat{D} = 90^\circ$ và $a = b = c = d$, tức là tứ giác ABCD là hình vuông, thì sự tương ứng (23) trở thành một đẳng thức.
Tóm lại, ba bài toán cho một lời giải độc lập.
Bài toán 6. Chứng minh rằng với một quả nho có chiều cao $h$, đường chéo $l_1, l_2$ và đáy $a, b$
$$h \leq \frac{l_1 l_2}{a + b}.$$
Bài toán 7. Chứng minh điều đó cho quả nho ABC
$$S_{ABC} < \frac{1}{6} (a^2 + b^2 + c^2),$$
thức ăn $a, b, c$—độ dài cạnh.
Bài toán 8. Chứng minh rằng với tứ giác lồi ABCD
$$S_{ABCD} < \frac{1}{6} (a^2 + b^2 + c^2 + d^2 + e^2 + f^2),$$
thức ăn $a, b, c, d$—độ dài tính bằng diaeon.
Xây dựng một khối đa diện!
(Bắt đầu từ trang 50)
Khối đa diện trên trang thứ hai của trang bìa được lấy từ sơ đồ này theo cách phức tạp hơn một chút: trong đó, “các vùng xung quanh” của đỉnh 3 và 7 được sử dụng năm lần - từ đó hình thành nên mái vòm của mô hình có đỉnh 9. Các bề mặt bên cũng được lấy từ sơ đồ.
Làm thế nào để xây dựng sơ đồ? Điều này được thực hiện bằng cách sử dụng các khối đa diện nửa bên phải bằng nhau.
Các khối đa diện như vậy được thay thế bằng thực tế là tất cả các mặt của chúng đều bằng nhau: đối với hai mặt bất kỳ của một khối đa diện như vậy, người ta có thể chỉ định sự dịch chuyển của không gian sao cho khối đa diện sẽ biến thành chính nó và mặt thứ nhất sẽ biến thành mặt thứ hai. Hãy lấy bất kỳ khối đa diện nào như vậy và xem xét các mặt phẳng của tất cả các mặt của nó. Chúng ta hãy sửa một trong những mặt phẳng này (hãy gọi nó là $\Pi$). Trong đó, các mặt phẳng còn lại được “khắc” bằng hệ thống các đường thẳng. Chính xác là các hệ thống tương tự hình thành trong các mặt phẳng còn lại. Bây giờ chúng ta hãy xem xét đường đa diện $l$ của hệ thống. Đó là giao điểm của mặt phẳng $\Pi$ và mặt phẳng của một mặt khác. Trong quá trình quay biến mặt phẳng này thành mặt phẳng $\Pi$, đường thẳng $l$ sẽ đi thành đường thẳng $l'$ nào đó của mặt phẳng $\Pi$. Hóa ra đường $l'$ được lấy từ đường $l$ bằng cách xoay (trong mặt phẳng $\Pi$) quanh điểm chung của chúng hoặc bằng cách dịch song song. Vẫn nằm trên đường bước ngoặt với các chốt và mũi tên tương ứng để chuyển song song.
Sơ đồ trong hình được lấy từ một hình lục giác nửa bên phải cân bằng («Kvant», 1976, số 1).
Khuyên bảo. Khi vẽ sơ đồ ở tỷ lệ lớn hơn, hãy lợi dụng thực tế là hình ngũ giác ABCD là đúng.
