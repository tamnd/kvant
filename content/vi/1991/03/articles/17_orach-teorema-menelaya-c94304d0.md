---
id: 1991-3-orach-teorema-menelaya-c94304d0
issue: kvant_1991_3
year: 1991
number: "3"
title: Định lý Menelaus
authors:
  - Орач Б. Г.
rubric: praktikum-abiturienta
rubric_sub: Практикум абитуриента
page_first: 54
page_last: 57
page_labels: 52, 53, 55
lang: vi
source: kvant_digital
extraction: vision
content_sha256: 14a0edde6a6267cc22ab350cdebdb9eee3a2f02cf38ddacdd484a414c5dde9a9
prompt_sha256: draft-1
translated_from: content/ru/1991/03/articles/17_orach-teorema-menelaya-c94304d0.md
source_content_sha256: 82ec5a6e53dead7e4f0100ae96dea9cfc5307ae6e6b425582757d58b061e6705
translation_model: draft
translation_run: vi-draft-gaps-2026-11-06
translation_quality: draft
---

⟦folio 52⟧

---
running_head:
folio:
---

Định lý Menelaus

V. ORACH

Định lý Menelaus rất hay và đơn giản. Trong khóa học ở trường, định lý này đã bị thất lạc ở đâu đó trong số bài toán. Trong khi đó, nó được đưa vào quỹ vàng của toán học Hy Lạp cổ đại.

Cho $\triangle ABC$ cắt một đường thẳng không song song với cạnh AB và cắt hai cạnh AC và BC lần lượt tại các điểm $B_1$ và $A_1$ và đường thẳng AB tại điểm $C_1$ (hình 1), khi đó

$$\frac{AB_1}{B_1C} \cdot \frac{CA_1}{A_1B} \cdot \frac{BC_1}{C_1A} = 1.$$

(Để tránh nhầm lẫn về thứ tự xuất hiện của các chữ cái trong công thức, hãy làm theo quy tắc sau: di chuyển dọc theo đường viền của tam giác từ đỉnh đến điểm giao nhau với đường thẳng và từ điểm giao nhau đến đỉnh tiếp theo.)

⟦folio 53⟧

---
running_head:
folio:
---

Nó vẫn còn để nhân tỷ lệ kết quả:

$$\frac{AB_1}{B_1C} \cdot \frac{CA_1}{A_1B} \cdot \frac{BC_1}{C_1A} = \frac{m \cdot n \cdot l}{n \cdot l \cdot m} = 1.$$

Định lý đã được chứng minh.

Định lý này sẽ hướng dẫn chúng ta trong bản dịch tiếng Ả Rập của cuốn sách “Hình cầu” của Menelaus ở Alexandria (thế kỷ 1 sau Công nguyên).

Để chứng minh tính hiệu quả của nó, chúng tôi xem xét lời giải một bài toán theo hai cách: vectơ và sử dụng định lý Menelaus.

Bài toán 1. Gọi AD là trung bình của $\triangle ABC$ (hình 2). Lấy điểm K trên AD sao cho AK:KD=3:1. Đường thẳng BK chia diện tích $\triangle ABC$ theo tỷ lệ nào?

Hiển nhiên, tỉ số diện tích của các tam giác ABP và CBP bằng tỉ số của hai đoạn thẳng AP và PC. Vì vậy, lời giải bài toán phụ thuộc vào việc tìm tỷ lệ AP/PC.

Vectơ lời giải. Vectơ $\overline{AK}$ có thể được biểu diễn theo hai cách thông qua vectơ $\overline{AB}$ và $\overline{AC}$. Trước hết, $\overline{AK} = \frac{3}{4} \overline{AD}$. Nhưng $\overline{AD} = \frac{1}{2} (\overline{AB} + \overline{AC})$ (công thức tính điểm giữa của một đoạn). Có nghĩa,

$$\overline{AK} = \frac{3}{4} \cdot \frac{1}{2} (\overline{AB} + \overline{AC}) = \frac{3}{8} \overline{AB} + \frac{3}{8} \overline{AC}.$$

Hãy biểu thị nó bằng $\frac{PK}{KB} = \frac{m}{n}, \overline{AP} = x \cdot \overline{AC}$.

Áp dụng định lý chia đoạn cho BP trong quan hệ này, ta có

$$\overline{AK} = \frac{m}{m+n} \overline{AB} + \frac{n}{m+n} \overline{AP}.$$

Nhưng $AP = x \cdot \overline{AC}$ có nghĩa là

$$\overline{AK} = \frac{m}{m+n} \overline{AB} + \frac{nx}{m+n} \overline{AC}.$$

So sánh (1) và (2), ta được

$$\frac{m}{m+n} \overline{AB} + \frac{nx}{m+n} \overline{AC} = \frac{3}{8} \overline{AB} + \frac{3}{8} \overline{AC}.$$

Sử dụng tính duy nhất phân tách vectơ AK thành hai vectơ không bám AB và AC, ta thu được hệ

$$\begin{cases} \frac{m}{m+n} = \frac{3}{8}, \\ \frac{n}{m+n} = \frac{3}{8x}, \end{cases}$$

từ đâu $x = 3/5$, tức là $AP/AC = 3/5$, và

$$\frac{AP}{PC} = \frac{3}{2}.$$

Lời giải sử dụng định lý Menelaus. Áp dụng định lý này cho tam giác ACD và cát tuyến BP, ta có

$$\frac{AP}{PC} \cdot \frac{CB}{BD} \cdot \frac{DK}{AK} = 1,$$

$$\frac{AP}{PC} \cdot 2 \cdot \frac{1}{3} = 1, \quad \frac{AP}{PC} = \frac{3}{2}.$$

Ưu điểm của việc sử dụng định lý Menelaus là rất lớn.

Rất thường xuyên, đối với lời giải bài toán điều cần thiết không phải là định lý Menelaus mà là định lý ngược lại với nó.

Xét tam giác ABC. Cho các điểm A$_1$, B$_1$, C$_1$ lần lượt thuộc các đường thẳng BC, AC, AB, tức là nằm trên các cạnh của tam giác hoặc phần kéo dài của chúng (hình 3).

⟦folio 55⟧

---
running_head:
folio:
---

1. Trên các cạnh AB và AC của tam giác ABC lần lượt có các điểm M và N sao cho $\frac{AM}{MB} = \frac{CN}{NA} = \frac{1}{2}$. Giao điểm S của các đoạn BN và CM chia các đoạn thẳng này theo tỉ số nào?
2. Trong △ABC, bicsectrix AD chia BC theo tỷ lệ 2:1. Đường trung tuyến CE chia bicector này theo tỉ số nào?
3. Trong tam giác ABC, lấy điểm D trên cạnh AB, lấy các điểm E và F trên cạnh BC sao cho AD:DB = 3:2, BE:EC = 1:3 và BF:FC = 4:1. Đường thẳng AE chia đoạn DF theo tỉ số nào?
4. Trực tâm H của tam giác ABC chia đôi đường cao. Chứng minh rằng $\cos \angle C = \cos \angle A \cdot \cos \angle B$, trong đó $\angle A, \angle B, \angle C$ là các góc ở các đỉnh.
5. Trong tam giác đều ABC có cạnh a, điểm E là trung điểm BC, D là trung điểm AC, $F \in DC$, $BF \cap DE = M$, $S_{ABMD} = \frac{5}{8} S_{ABC}$. Tìm MF (hình 6).
6. Cho hình bình hành ABCD. Điểm M chia đoạn AD theo p và điểm N chia đoạn DC theo q. Các đường thẳng BM và AN cắt nhau tại điểm S. Tính tỉ số AS:SN (hình 7).
7. Qua trung điểm M cạnh BC của hình bình hành ABCD có diện tích bằng 1 và đỉnh A kẻ đường thẳng cắt đường chéo BD tại điểm Q. Tìm diện tích tứ giác QMCD (hình 8).
8. Các cạnh △ABC cách nhau bởi các điểm M, N và P sao cho AM:MB = BN:NC = CP:PA = 1:4. Tìm tỉ số diện tích của tam giác giới hạn bởi các đường thẳng AN, BP và CM so với diện tích của tam giác ABC (hình 9).

Số tiền tối thiểu và số tiền tối thiểu
(Để bắt đầu, xem trang 49)

Sự liên kết của Gelder. Rõ ràng trường hợp thứ nhất là trường hợp đặc biệt của trường hợp thứ hai đối với $p = q = 2$. Do đó, nếu chúng ta giới thiệu vectơ “dài” $(a; b)$ theo quy tắc $|(a; b)|_p = (a^p + b^p)^{\frac{1}{p}}$ thì hóa ra tích vô hướng của hai vectơ
$(a; b) \cdot (c; d) \leq |(a; b)|_p \cdot |(c; d)|_q$
không vượt quá tích của “độ dài” của chúng.
Ở trạng thái này, cách giải thích hình học của bất đẳng thức Hölder và ý nghĩa của nó.
Vì vậy, phương pháp là rõ ràng. Chúng ta đã chứng minh khá nhiều bất đẳng thức (bao gồm cả một số bất đẳng thức cổ điển) bằng cách sử dụng một tập hợp hàm khiêm tốn. Có thể người đọc sẽ có thể chứng minh các bất đẳng thức diễn giải khác bằng phương pháp này.

Khai triển Y 4. Chứng minh các bất đẳng thức sau $a_1, \dots, a_n, b_1, \dots, b_n$ là số dương
a) $\sqrt[n]{a_1 \dots a_n} + \sqrt[n]{b_1 \dots b_n} \leq \sqrt[n]{(a_1 + b_1) \dots (a_n + b_n)}$,
b) $(a_1^p + \dots + a_n^p)^{\frac{1}{p}} \cdot (b_1^q + \dots + b_n^q)^{\frac{1}{q}} \leq a_1 b_1 + \dots + a_n b_n$ nếu $q < 0$ và $\frac{1}{p} + \frac{1}{q} = 1$
(Bất đẳng thức Hölder “ngược lại”),
d) $(a_1^p + \dots + a_n^p)^{\frac{1}{p}} + (b_1^q + \dots + b_n^q)^{\frac{1}{q}} \geq ((a_1 + b_1)^p + \dots + (a_n + b_n)^p)^{\frac{1}{p}}$, trong đó $p > 1$ (Bất đẳng thức Minkowski). Chứng minh rằng nếu $p < 1$ thì bất đẳng thức nghịch đảo.

Gợi ý. a) Xét hàm tuyến tính $y = a_1 x_1 + \dots + a_n x_n$ của $n$ biến trên tập hợp bao gồm tập hợp $(x_1, \dots, x_n)$ sao cho $x_1 \dots x_n = n$. 6) Đặt $b_1 = \dots = b_n = 1$ trong giới hạn của bất đẳng thức. d) Xét lại hàm tuyến tính $y = a_1 x_1 + \dots + a_n x_n$ trên tập hợp cho trước với điều kiện:
$x_1^q + \dots + x_n^q = 1$,
trong đó số $q$ được xác định bởi điều kiện $\frac{1}{p} + \frac{1}{q} = 1$.
