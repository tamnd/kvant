---
id: 1971-6-sidorov-zadachi-po-geometrii-db822bc1
issue: kvant_1971_6
year: 1971
number: "6"
title: Bài toán hình học
authors:
  - Сидоров Ю. В.
rubric: praktikum-abiturienta
rubric_sub: Практикум абитуриента
page_first: 54
page_last: 56
page_labels: 52-54
tag: 2HFM
lang: vi
source: kvant_digital
extraction: vision
content_sha256: da65f1e5f3c260a35277ee2b7ab9d91fdb5770ff0534a7b9aa62fc7e4220c721
prompt_sha256: 3ec6b8aabd9b98576af76503cd8a2902b9f5d18e01ee867dfb1228f59c6d52d8
translated_from: content/ru/1971/06/articles/13_sidorov-zadachi-po-geometrii-db822bc1.md
source_content_sha256: 254cb9c2d31a9d8d8482a4d25f78af58e2ecff34f7d2e7f48042abd81cf92f88
translation_model: gpt-5.6-terra
translation_run: vi-codex-2026-10-31
---

⟦folio 52⟧

Yu. V. Sidorov

Trong các kỳ thi tuyển sinh vào các trường đại học, các bài toán hình học chiếm một vị trí lớn. Điều kiện của đa số bài toán được phát biểu khá đơn giản: trong một hình hình học nào đó cho một số yếu tố hoặc các quan hệ giữa các yếu tố, và yêu cầu tìm yếu tố chưa biết hoặc quan hệ chưa biết giữa các yếu tố.

Những điều kiện bài toán “tiêu chuẩn” như vậy đều dễ hiểu đối với mọi thí sinh. Tuy nhiên, các bài toán hình học và các ví dụ giải chúng đa dạng đến mức không thể nghĩ ra một cách phân loại thuận tiện nào để từ đó có thể nhận ra lời giải của từng bài toán cụ thể. Chính vì thế, trong sách giáo khoa và tài liệu học tập hầu như không có mô tả các phương pháp giải bài toán. Để học cách giải các bài toán hình học, cần nắm vững và hiểu rõ các định lý cơ bản của hình học, điều quan trọng nhất là thường xuyên luyện tập, đều đặn giải các bài toán đa dạng.

Trong những năm gần đây, đa số học sinh chỉ giải các bài toán hình học bằng “phương pháp đại số”, gồm các bước sau. Các yếu tố chưa biết của hình hình học được ký hiệu là $x$, $y$, $z$, ..., rồi tính một số quan hệ giữa các yếu tố đã biết và chưa biết. Sau đó giải hệ phương trình đại số và lượng giác thu được, rồi tìm các yếu tố hoặc quan hệ cần tìm theo điều kiện bài toán.

Cách tiếp cận khuôn mẫu như vậy đối với việc giải bài toán hình học thường là một trong những cách đơn giản nhất và cho phép nhanh chóng nhận được đáp số. Đương nhiên, có thể nảy sinh mong muốn giải mọi bài toán theo cách đó. Tuy nhiên, thí sinh đã quen, không suy nghĩ, “chuyển” bất kỳ bài toán hình học nào thành bài toán đại số sẽ gặp những khó khăn không thể vượt qua trong các kỳ thi tuyển sinh, nếu hóa ra cách giải của họ không dẫn đến kết quả mong muốn.

Hầu như mỗi bài toán đều có thể giải bằng nhiều cách khác nhau. Những bài làm của thí sinh tìm được con đường ngắn nhất và thanh nhã nhất để giải bài toán được đánh giá cao. Chỉ sự luyện tập nhiều và thường xuyên mới cho phép học cách tìm những phương pháp giải đa dạng nhất. Việc chọn khéo các ẩn số, hình vẽ thuận tiện, các dựng hình hình học bổ sung và cách trình bày lời giải cẩn thận giúp hiểu đúng bài toán và tìm ra cách giải đơn giản nhất. Hãy xét các ví dụ cụ thể.

Trong kỳ thi viết môn toán tại MFTI, đã cho bài toán sau.

1. Các đường phân giác AM và BN của tam giác ABC cắt nhau tại điểm O. Biết rằng $AO = \sqrt{3}MO$, $NO = (\sqrt{3} - 1)BO$. Tìm các góc của tam giác ABC.

Nhiều thí sinh đã thử giải bài toán này như sau.

⟦folio 53⟧

Đặt $AB=a$, $\Rightarrow BAC=x$, $\Rightarrow ABC=y$ (hình 1). Tìm độ dài đoạn thẳng $AN$ từ tam giác $ABN$ (theo tính chất đường phân giác góc trong của tam giác và theo định lý sin):

$$AN = AB \frac{NO}{BO} = a (\sqrt{3} - 1) = \frac{a \sin \frac{y}{2}}{\sin \left(x + \frac{y}{2}\right)}$$

Tương tự, từ tam giác $ABM$ ta có:

$$BM = \frac{a}{\sqrt{3}} = \frac{a \sin \frac{x}{2}}{\sin \left(\frac{x}{2} + y\right)}$$

Như vậy, thu được hệ phương trình:

$$\begin{cases} \sin \left(\frac{x}{2} + y\right) = \sqrt{3} \sin \frac{x}{2}, \\ (\sqrt{3} - 1) \sin \left(x + \frac{y}{2}\right) = \sin \frac{y}{2}. \end{cases}$$

Đa số thí sinh giải bài toán bằng cách này đã không tìm được lời giải của hệ khá phức tạp đó. Nhưng điều không tốt không phải là họ không giải được hệ thu được, mà là họ không cố gắng tìm cách khác để giải bài toán này. Bài toán này dễ giải hơn bằng cách sau đây (cũng là đại số).

Đặt $AB=x$, $BC=y$, $AC=z$. Từ các tam giác $ABM$ và $ABN$, theo tính chất đường phân giác của góc trong tam giác, ta được:

$$\frac{BM}{AB} = \frac{MO}{AO} = \frac{1}{\sqrt{3}},$$

$$\frac{AN}{AB} = \frac{NO}{BO} = \sqrt{3} - 1.$$

Suy ra $BM = \frac{x}{\sqrt{3}}, AN = x (\sqrt{3} - 1)$. Từ tam giác $ABC$ có:

$$\frac{AN}{CN} = \frac{AB}{BC}, \quad \frac{BM}{CM} = \frac{AB}{AC},$$

tức là

$$\begin{cases} \frac{x (\sqrt{3} - 1)}{z - x (\sqrt{3} - 1)} = \frac{x}{y}, \\ \frac{x}{y \sqrt{3} - x} = \frac{x}{z}. \end{cases}$$

Từ hệ phương trình này tìm được: $y = x \sqrt{3}, z = 2x$. Suy ra $x^2 + y^2 = z^2$ và theo định lý đảo của định lý Pythagore, $\Rightarrow ABC = \frac{\pi}{2}$.

Do đó,

$$\Rightarrow BAC = \arcsin \frac{y}{z} = \frac{\pi}{3},$$

$$\Rightarrow ACB = \frac{\pi}{6}.$$

Xét thêm một bài toán nữa.

2. Trên cạnh huyền $BC$ của tam giác vuông $ABC$ có điểm $M$, còn trên cạnh $AC$ có điểm $N$ sao cho $MN \parallel AB$. Biết rằng $AB=AN=1$ cm, $CM = \sqrt{3}$ cm. Tìm độ dài đoạn thẳng $MN$.

Tự nhiên là thử giải bài toán này như sau. Ký hiệu $MN$ là $x$ (hình 2). Khi đó $CN = \sqrt{3} - x^2$ và từ sự đồng dạng của các tam giác ta được phương trình

$$\frac{\sqrt{3} - x^2}{1 + \sqrt{3} - x^2} = x,$$

dễ dàng biến đổi thành dạng $x^4 - 2x^3 - x^2 + 6x - 3 = 0$.

Khó tìm nghiệm của phương trình này, vì vậy cần thử tìm cách giải khác cho bài toán. Ví-

⟦folio 54⟧

Hình 2.

dụ, bài toán 2 có thể được giải như sau.

Gọi $MN$ là $x$, $CN$ là $y$. Khi đó dễ dàng thu được hệ phương trình sau:

$$\begin{cases} x^2 + y^2 = 3, \\ \frac{y + 1}{y} = \frac{1}{x}. \end{cases}$$

Từ phương trình thứ hai của hệ này, ta tìm được:

$$y - x = xy, \quad x^2 + y^2 - 2xy = x^2y^2.$$

Lấy phương trình này trừ đi phương trình thứ nhất của hệ, ta được:

$$(xy)^2 + 2xy - 3 = 0, \quad xy = -1 \pm 2.$$

Xét rằng $x > 0, y > 0$, ta được hệ

$$\begin{cases} xy = 1, \\ y - x = 1, \end{cases}$$

từ đó tìm được đáp số:

$$x = \frac{1}{2} (\sqrt{5} - 1) (\text{cm}).$$

Từ các ví dụ đã xét, thấy rằng việc chọn thích hợp các đại lượng chưa biết

Hình 3.

giúp đơn giản hóa việc giải bài toán hình học bằng phương pháp đại số. Sau đây là các bài toán mà để giải chúng, cần thực hiện các phép dựng hình học bổ sung.

3. Trong hình thang $ABCD$, cạnh bên $AB$ vuông góc với các đáy, các đường chéo vuông góc với nhau $u \frac{AD}{BC} = k$. Tìm tỉ số $\frac{BD}{AC}$.

Lời giải. Qua điểm $B$ kẻ đường thẳng song song với đường chéo $AC$, cắt đường thẳng $AD$ tại điểm $M$ (hình 3). Khi đó, theo định lý về tính chất của đường vuông góc hạ từ đỉnh góc vuông của tam giác $BMD$, ta có

$$BD = \sqrt{DM \cdot AD},$$

$$BM = \sqrt{DM \cdot AM}.$$

Vì $AC = BM, AM = BC$, ta được

$$\frac{BD}{AC} = \frac{BD}{BM} = \frac{\sqrt{DM \cdot AD}}{\sqrt{DM \cdot AM}} = \sqrt{\frac{AD}{BC}} = \sqrt{k}.$$

4. Trên các cạnh $AC$ và $BC$ của tam giác $ABC$ lần lượt có các điểm $N$ và $M$ sao cho

$$\frac{AN}{CN} = n, \quad \frac{BM}{CM} = m.$$

Các đường thẳng $AM$ và $BN$ cắt nhau tại điểm $O$.

Tìm tỉ số

$$\frac{AO}{MO} u \frac{BO}{NO}.$$

Lời giải. Kẻ $MK \parallel BN$ (hình 4). Từ sự đồng dạng của các tam giác $BCN$ và $CKM$, tìm được $CK$:

$$CK = CN \frac{CM}{BC} = CN \frac{CM}{CM + BM} = CN \frac{1}{1 + m}.$$

Do đó,

$$KN = CN - CK = CN \left(1 - \frac{1}{1 + m}\right) = CN \frac{m}{1 + m}.$$
