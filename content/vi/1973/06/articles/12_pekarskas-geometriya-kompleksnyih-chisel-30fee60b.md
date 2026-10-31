---
id: 1973-6-pekarskas-geometriya-kompleksnyih-chisel-30fee60b
issue: kvant_1973_6
year: 1973
number: "6"
title: Hình học của số phức
authors:
  - Пекарскас В. В.
rubric: praktikum-abiturienta
rubric_sub: Практикум абитуриента
page_first: 56
page_last: 58
page_labels: 54-56
tag: GF65
lang: vi
source: kvant_digital
extraction: vision
content_sha256: f5e0bdff5198dbbcae39d828e2f9c077a19476b3a8bf6d3470544a9c9b479574
prompt_sha256: draft-1
translated_from: content/ru/1973/06/articles/12_pekarskas-geometriya-kompleksnyih-chisel-30fee60b.md
source_content_sha256: 45e23d8b01f99e500a26bbf327d99b50b6b0f29578557be5fb0ff73b351d6a2f
translation_model: draft
translation_run: vi-draft-2026-10-31
translation_quality: draft
---

⟦folio 54⟧

Trong “Giáo trình thi tuyển sinh môn toán” đặc biệt có mục sau: “Số phức và lập luận cho các hành động trên chúng. Môđun và lập luận của số phức.” Ứng viên không bắt buộc phải xây dựng lý thuyết số phức một cách chặt chẽ, nhưng họ phải có khả năng thao tác các số này và biết cách giải thích hình học của chúng.

Bài viết này xem xét một số bài toán được lấy từ kinh nghiệm ứng dụng. Về cơ bản, mỗi bài toán chỉ sử dụng các định nghĩa cơ bản và cách diễn giải hình học của một số khái niệm liên quan đến số phức.

Bài 1. Vẽ một cái bát trên mặt phẳng tương ứng với số $z = \frac{2+i}{i-2}$.

Đã giải quyết và e. Trước hết, hãy biểu diễn số này dưới dạng đại số:

$$\frac{2+i}{i-2} = -\frac{(2+i)(2+i)}{(2-i)(2+i)} = -\frac{3+4i}{5} = -\frac{3}{5} - \frac{4}{5} i.$$

Giờ đây, việc mô tả số $z$ trên mặt phẳng phức không còn khó khăn nữa - bạn sẽ có một điểm ở ô vuông thứ ba (bạn hãy tự vẽ nó!).

Bài 2. Số phức $z = a+bi$ được biểu thị bằng điểm $M(a, b)$. Điểm $z_1 = z + 3 - 2i$ ở đâu?

Đã giải quyết và e. Chúng tôi có $z + 3 - 2i = (a + 3) + (b - 2) i$.

Số vị trí $z_1 = (a + 3) + (b - 2) i$ được biểu thị bằng điểm $M_1(a + 3, b - 2)$, được lấy từ điểm $M$ có ​​hai chiều ở bên phải ba đơn vị và hướng xuống dưới hai đơn vị.

Bài tập 3. Số phức $z$ cũng được xem xét như $|z| = 2$. Các điểm $2z - 3i + 1$ nằm ở đâu?

Đã giải quyết và e. Các điểm $z$, trong đó $|z| = 2$, nằm trên đường tròn bán kính 2 với tâm tại điểm $(0, 0)$ (Hình 1). Khi đó các điểm $2z$ sẽ nằm trên một đường tròn đồng tâm bán kính 4. Trên thực tế, điểm $2z$ nằm trên cùng một tia phát ra từ gốc tọa độ với điểm $z$, nhưng cách gốc tọa độ 2 lần so với điểm $z$.

Điểm $2z + 1 - 3i$ thu được từ điểm $2z$ có hai chiều ở bên phải một và hai chiều giảm ba đơn vị. Do đó, các điểm $2z + 1 - 3i$, trong đó $|z| = 2$, tạo thành một đường tròn có tâm tại điểm $(1, -3)$ và bán kính 4.

Bài 4. Tập hợp điểm nào trong mặt phẳng phức thỏa mãn điều kiện $2 < |z + 1 - 2i| \leq 3$?

Đã giải quyết và e. Để $z_1 = z + 1 - 2i$; thì điều kiện này có dạng

$$2 < |z_1| \leq 3. \quad (1)$$

Điểm $z_1$ thỏa mãn điều kiện $|z_1| = 3$ nằm trên đường tròn bán kính 3 có tâm tại gốc tọa độ. Điều kiện $|z_1| < 3$ được thỏa mãn bởi tất cả các điểm bên trong của đường tròn bán kính 3 có tâm tại gốc tọa độ. Điều kiện $|z_1| > 2$ được thỏa mãn bởi mọi điểm nằm trong

⟦folio 55⟧

Một đường tròn bán kính 2 có tâm ở gốc tọa độ. Như vậy, tập hợp các điểm $z_1$ thỏa mãn điều kiện (1) là một vòng nằm giữa các đường tròn đồng tâm có tâm tại gốc tọa độ và bán kính 2 và 3 (Hình 2); các điểm bên trong đường tròn không thuộc tập hợp này.

Vì $z = z_1 - 1 + 2i$, điểm $z$ có được từ điểm $z_1$ bằng cách di chuyển một đơn vị sang trái và hai đơn vị lên trên. Do đó, kết quả cuối cùng là một vòng nằm giữa các đường tròn đồng tâm bán kính 2 và 3 có tâm tại điểm $(-1, 2)$ (loại trừ đường tròn bên trong).

Nhiệm vụ 5 (MSU, Khoa Kinh tế, 1970). Cho biết lũy thừa của mặt phẳng tương ứng với các số thỏa mãn điều kiện $|z| + i + z = 2 + i$.

Lời giải. Hãy để $z = a + bi$; thì điều kiện này sẽ có dạng

$$i\sqrt{a^2 + b^2} + a + bi = 2 + i.$$

Bằng cách định nghĩa đẳng thức của số phức, từ đây ta thu được hệ phương trình

$$\begin{cases} a = 2, \\ \sqrt{a^2 + b^2} + b = 1, \end{cases}$$

điều đó có thể dễ dàng giải quyết. Kết quả ta tìm được số $z = 2 - \frac{3}{2}i$ thỏa mãn điều kiện gán.

Bài 6. Tìm tập hợp các điểm biểu thị số phức $z = x + iy$ ứng với mỗi số

⟦folio 56⟧

từ đó, theo định nghĩa của mô đun, chúng ta nhận được

$$2\sqrt{x-y} = 2,$$

hoặc

$$x-y = 1.$$

Như vậy, các điểm yêu cầu $(x, y)$ phải thỏa mãn đẳng thức $x-y = 1$ và nằm trong vùng đã ghi trước đó được xác định bởi phương trình (3); Có thể dễ dàng xác minh rằng tất cả các điều kiện này đều được thỏa mãn bởi các điểm của đoạn $AB$ (Hình 3).

Bài 7. Số phức $z$ thỏa mãn điều kiện

$$|z+2+i| = |z-1-4i|.$$ (4)

Các dấu chấm đại diện cho những con số này nằm ở đâu?

Lời giải. Như đã biết, $|z_1-z_2|$ là khoảng cách giữa các điểm biểu thị số phức $z_1$ và $z_2$. Do đó số

$$|z+2+i| = |z-(-2-i)|$$

 là khoảng cách từ điểm biểu thị số $z$ đến điểm $M(-2, -1)$ và số đó

$$|z-1-4i| = |z-(1+4i)|$$

 là khoảng cách từ điểm đại diện cho số $z$ đến điểm $N(1, 4)$. Điều kiện (4) khi đó có nghĩa là các điểm yêu cầu cách đều các điểm $M$ và $N$. Do đó, các điểm cần tìm nằm trên đường thẳng vuông góc với đoạn $MN$ và đi qua điểm giữa của đoạn đó.

Bài 8. Chỉ ra tập hợp các điểm biểu diễn số, biểu diễn số phức thỏa mãn đồng thời hai điều kiện

$$|z-2i| \leqslant \frac{3}{2}, \frac{\pi}{3} < \arg z < \frac{2\pi}{3}.$$ (5)

Lời giải. Các dấu chấm biểu thị các số phức thỏa mãn điều kiện đầu tiên (5) điền vào một vòng tròn (bao gồm cả hình tròn) bán kính $3/2$ có tâm tại điểm $(0,2)$ (Hình 4). Điều kiện thứ hai được thỏa mãn bởi số phức biểu thị các điểm nằm giữa các tia phát ra từ gốc tọa độ và thành phần

$$0 < |z|^2 - |z| + 1 < 6 + 3 |z|,$$ (6)

Lời giải. Bất đẳng thức (6), theo tính chất logarit, tương đương với bất đẳng thức kép

$$0 < \frac{|z|^2 - |z| + 1}{2 + |z|} < 3,$$

có thể được viết lại (vì $2 + |z| > 0$ với bất kỳ $z$ nào) dưới dạng

$$0 < |z|^2 - |z| + 1 < 6 + 3 |z|.$$

Nhưng bất đẳng thức $|z|^2 - |z| + 1 > 0$ đúng với mọi $z$ (vì phân biệt của tam thức bình phương $x^2 - x + 1$ là âm) và bất đẳng thức $|z|^2 - |z| + 1 < 6 + 3 |z|$, nghĩa là, $|z|^2 - 4 |z| - 5 < 0$ được thỏa mãn với $|z| < 5$ (bất đẳng thức $x^2 - 4x - 5 < 0$ thỏa mãn với $-1 < x < 5$, nhưng $|z| \geqslant 0$ với bất kỳ $z$). Do đó, điều kiện (6) được thỏa mãn bởi số phức $z$ thỏa mãn điều kiện $|z| < 5$; những con số này lấp đầy phần bên trong của một vòng tròn bán kính 5 có tâm ở gốc tọa độ.
