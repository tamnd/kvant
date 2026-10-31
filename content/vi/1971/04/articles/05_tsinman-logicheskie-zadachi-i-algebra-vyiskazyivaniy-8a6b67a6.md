---
id: 1971-4-tsinman-logicheskie-zadachi-i-algebra-vyiskazyivaniy-8a6b67a6
issue: kvant_1971_4
year: 1971
number: "4"
title: Các bài toán lôgic và đại số mệnh đề
authors:
  - Цинман Л. Л.
rubric: osnovnye-stati
page_first: 16
page_last: 19
page_labels: 14, 16, 17
tag: R5P5
lang: vi
source: kvant_digital
extraction: vision
content_sha256: 29161ea9a65163dcea3140121e7efbc6e7d27ce8b3c8ffa520ccadc27630374d
prompt_sha256: 3ec6b8aabd9b98576af76503cd8a2902b9f5d18e01ee867dfb1228f59c6d52d8
translated_from: content/ru/1971/04/articles/05_tsinman-logicheskie-zadachi-i-algebra-vyiskazyivaniy-8a6b67a6.md
source_content_sha256: 5ea05d0c4bf6f5c2873a6eb158d6f236416380caeb63477f9ef71aff442ff630
translation_model: gpt-5.6-terra
translation_run: vi-codex-2026-10-31
---

⟦folio 14⟧

Các bài toán lôgic và đại số mệnh đề

L. L. Tsinman

Hãy bắt đầu bằng cách nêu vài bài toán lôgic.

Bài toán 1. Sau buổi họp phụ huynh, một phụ huynh đến gặp cô giáo.

— Cô đã không nêu tên con trai tôi trong số những học sinh giỏi, — ông nói. — Nhưng Fedia của tôi là học sinh xuất sắc, lại còn là vận động viên trượt tuyết giỏi nhất lớp.

— Vâng, ông nói đúng, — cô giáo đáp. — Nhưng chúng tôi coi là học sinh giỏi người học tốt, có kỷ luật, giúp đỡ những bạn học kém và, ngoài ra, tham gia công tác của câu lạc bộ khoa học hoặc chơi thể thao. Còn Fedia của ông...

Cô giáo còn định nói gì với cha của Fedia?

Bài toán 2. Một lần, điều tra viên phải đồng thời thẩm vấn ba nhân chứng: Claude, Jacques và Dick. Lời khai của họ mâu thuẫn với nhau, và mỗi người đều buộc ai đó nói dối. Claude khẳng định rằng Jacques nói dối, Jacques buộc Dick nói dối, còn Dick thuyết phục điều tra viên đừng tin cả Claude lẫn Jacques. Nhưng điều tra viên nhanh chóng vạch trần họ mà không hỏi họ một câu nào. Ai trong các nhân chứng đã nói thật?

Bài toán 3. Một nhà lôgic học bị rơi vào tay bọn man rợ và bị giam trong một ngục thất có hai lối ra. Tù trưởng bọn man rợ đưa ra cho người tù cơ hội cứu sống như sau: “Một lối dẫn đến tự do, còn lối kia dẫn đến cái chết chắc chắn. Ngươi có thể chọn bất cứ lối nào. Một lính canh của ta sẽ giúp ngươi lựa chọn. Hắn sẽ ở đây để

trả lời một câu hỏi — bất kỳ câu nào mà ngươi muốn hỏi hắn. Nhưng ta cảnh báo ngươi: nếu tên lính canh này tâm trạng tốt thì hắn nói thật, còn nếu tâm trạng xấu thì hắn nói dối!”

Sau một phút suy nghĩ, nhà lôgic học bị bắt đặt một câu hỏi, rồi chọn chính xác lối ra dẫn đến tự do. Đó là câu hỏi gì?

Những bài toán lôgic như các bài đã nêu thường xuất hiện trong các ấn phẩm khoa học phổ thông. Để giải chúng không cần có những kiến thức chuyên môn nào về lôgic học, chỉ cần tư duy lôgic phát triển khá tốt. Nhưng hãy hình dung một người bắt tay giải một bài toán số học nào đó (về chuyển động, về rót chất lỏng) mà lại không biết tự do thực hiện các phép biến đổi đại số và giải phương trình. Gần như ở đúng tình thế ấy, bạn sẽ rơi vào khi giải các bài toán lôgic mà không dùng đến công cụ phụ trợ mang tên đại số mệnh đề hay đại số lôgic (khác với đại số các số được học ở trường).

Mục đích của bài báo là làm quen với bạn đọc những kiến thức ban đầu về đại số cần thiết này và, sử dụng những kiến thức đã có, giải các bài toán được nêu ở trên. Tuy nhiên, cần lưu ý rằng đại số mệnh đề không chỉ được dùng để giải các bài toán lôgic (đó chỉ là một trong các ứng dụng của nó), mà còn là một phần quan trọng

⟦folio 16⟧

Phủ định của mệnh đề
Ký hiệu phủ định của mệnh đề $A : \bar{A}$. Phủ định của mệnh đề $A$ tương ứng với mệnh đề “không $A$” (“không đúng rằng $A$”). Vì vậy nó được xác định bởi bảng chân trị sau:

| $A$ | $\bar{A}$ |
| :--- | :--- |
| 1 | 0 |
| 0 | 1 |

Với các phép toán đã đưa vào, trong đại số mệnh đề, từ các mệnh đề riêng lẻ $A, B, C$... có thể xây dựng các biểu thức đại số phức tạp, chẳng hạn: $\bar{A} \vee B; \bar{A} \wedge B; (A \vee \bar{B}) \wedge C$.

Cũng như trong đại số số học, phép nhân có thứ tự ưu tiên cao hơn phép cộng. Điều này cho phép không viết một số dấu ngoặc. Bây giờ biểu thức

$((A \wedge B) \vee ((\bar{A} \vee B) \wedge C))$

có thể viết lại dưới dạng

$A \wedge B \vee (\bar{A} \vee B) \wedge C$.

Nếu biết giá trị của mỗi mệnh đề có trong biểu thức đại số, thì bằng các bảng chân trị có thể tìm được giá trị của biểu thức đại số này. Chẳng hạn, hãy tìm các giá trị của biểu thức đại số $\bar{A} \vee \bar{B}$ với mọi giá trị có thể của các thành phần $A$ và $B$ của nó:

| $A$ | $B$ | $\bar{A}$ | $\bar{B}$ | $\bar{A} \vee \bar{B}$ |
| :--- | :--- | :--- | :--- | :--- |
| 1 | 1 | 0 | 0 | 0 |
| 1 | 0 | 0 | 1 | 1 |
| 0 | 1 | 1 | 0 | 1 |
| 0 | 0 | 1 | 1 | 1 |

Trước hết, theo các giá trị trong hai cột đầu, điền cột thứ ba và thứ tư, rồi theo định nghĩa của phép cộng, điền cột cuối cùng. Bảng này được gọi là bảng chân trị của biểu thức $\bar{A} \vee \bar{B}$.

Bây giờ hãy lập bảng chân trị cho $\bar{A} \wedge \bar{B}$:

| $A$ | $B$ | $\bar{A} \wedge \bar{B}$ |
| :--- | :--- | :--- |
| 1 | 1 | 0 |
| 1 | 0 | 1 |
| 0 | 1 | 0 |
| 0 | 0 | 1 |

Các cột cuối trong các bảng trên hóa ra giống nhau. Điều này có nghĩa là với mọi giá trị của các mệnh đề $A$ và $B$, các biểu thức $\bar{A} \vee \bar{B}$ và $\bar{A} \wedge \bar{B}$ nhận những giá trị giống nhau. Những biểu thức đại số như vậy chúng ta sẽ gọi là tương đương. Để ghi sự tương đương, dùng dấu đồng nhất:

$$\bar{A} \wedge \bar{B} \equiv \bar{A} \vee \bar{B}$$

Hai biểu thức tương đương này có cùng một ý nghĩa nội dung, nhưng được diễn đạt bằng những lời khác nhau.

Thật vậy, nếu $A$ và $B$ là những mệnh đề nào đó, thì $\bar{A} \wedge \bar{B}$ biểu thị mệnh đề phức “không đúng rằng cả hai mệnh đề đã cho đều đúng”, còn $\bar{A} \vee \bar{B}$ biểu thị mệnh đề phức “ít nhất một trong các mệnh đề đã cho là sai”.

Các biểu thức đại số mà trong bảng chân trị, cột cuối cùng gồm toàn các đơn vị (toàn các số không), sẽ được gọi là hằng đúng (hằng sai) và ký hiệu bằng chữ $H$ (chữ $J$).

Nhờ bảng chân trị, luôn dễ dàng xác định hai biểu thức đại số đã cho có tương đương hay không.

Hãy nêu những tương đương đơn giản nhất, một số trong đó chúng ta sẽ

⟦folio 17⟧

dùng về sau như các quy tắc.

1. $A \wedge B \equiv B \wedge A$.
2. $A \vee B \equiv B \vee A$.
3. $(A \wedge B) \wedge C \equiv A \wedge (B \wedge C)$.
4. $(A \vee B) \vee C \equiv A \vee (B \vee C)$.
5. $A \wedge (B \vee C) \equiv (A \wedge B) \vee (A \wedge C)$.
6. $A \vee (B \wedge C) \equiv (A \vee B) \wedge (A \vee C)$.
7. $A \wedge A \equiv A$.
8. $A \vee A \equiv A$.
9. $\overline{A} \wedge \overline{B} \equiv \overline{A} \vee \overline{B}$.
10. $\overline{A} \vee \overline{B} \equiv \overline{A} \wedge \overline{B}$.
11. $\overline{A} \equiv A$.
12. $A \wedge \overline{A} \equiv \overline{J}$.
13. $A \vee \overline{A} \equiv \overline{H}$.
14. $A \wedge \overline{J} \equiv \overline{J}$.
15. $A \vee \overline{H} \equiv \overline{H}$.
16. $A \wedge \overline{H} \equiv A$.
17. $A \vee \overline{J} \equiv A$.

Nếu hình dung ý nghĩa thực chất của các quy tắc 1—17 như ta đã làm ở trên với quy tắc 9, thì các tương đương này sẽ trở nên hiển nhiên và dễ nhớ.

Một số quy tắc đã liệt kê, cụ thể là 1—5, tương tự các tính chất đã biết của phép cộng và phép nhân trong đại số số. Vì vậy, trong đại số mệnh đề ta có thể thực hiện các phép biến đổi đại số giống như những phép biến đổi ta làm trong đại số số. Đặc biệt, ta có thể “nhân” hai mệnh đề đại số theo quy tắc nhân đa thức với đa thức.

Nhưng trong đại số mệnh đề cũng có các quy tắc đặc thù riêng, chẳng hạn quy tắc 6.

**Lời giải bài toán 1**

Đặt ký hiệu cho các mệnh đề:

$A$: “Fedya học giỏi”;
$B$: “Fedya có kỷ luật”;
$C$: “Fedya giúp đỡ những bạn học yếu”;
$D$: “Fedya tham gia hoạt động của câu lạc bộ khoa học”;
$E$: “Fedya chơi thể thao”.

Bây giờ mệnh đề “Fedya là một học sinh giỏi”, theo định nghĩa về học sinh giỏi do cô giáo đưa ra,

có thể viết như sau:

$A \cup B \cup C$ ($D \cup E$).

Trong ngôn ngữ đại số mệnh đề, mệnh đề phức này có dạng biểu thức đại số

$A \wedge B \wedge C \wedge (D \vee E)$.

Cô giáo khẳng định rằng “không đúng là (Fedya là học sinh giỏi)”, tức là

$$\{A \wedge B \wedge C \wedge (D \vee E)\} = 1.$$

Bây giờ hãy biến đổi biểu thức đại số ở vế trái trước hết theo quy tắc 9 (đúng là trong trường hợp này phép phủ định đặt trên tích lôgic của bốn thành phần, nhưng không khó để thấy rằng tương đương 9 vẫn đúng cả ở dạng tổng quát hơn này), rồi theo quy tắc 10:

$$\begin{align*}
\{A \vee \overline{B} \vee \overline{C} \vee (D \vee E)\} &= 1; \\
\{A \vee \overline{B} \vee \overline{C} \vee \overline{D} \wedge \overline{E}\} &= 1.
\end{align*}$$

Bố của Fedya khẳng định (và cô giáo đã đồng ý với ông) rằng

$$\{A\} = 1$$

(Fedya là học sinh xuất sắc!), và cũng rằng

$$\{E\} = 1$$

(Fedya là vận động viên trượt tuyết giỏi nhất lớp!). Khi đó trong (1), số hạng thứ nhất và hai số hạng cuối là sai, nên có thể bỏ chúng theo các quy tắc 17 và 14.

Ta được rằng

$$\{B \vee \overline{C}\} = 1.$$

Vậy là cô giáo muốn phàn nàn với bố của Fedya hoặc rằng Fedya không có kỷ luật, hoặc rằng cậu không giúp đỡ những bạn học yếu (có thể Fedya mang cả hai khuyết điểm này cùng lúc).

**Lời giải bài toán 2**

Ký hiệu lời khai của Claude, Jacques và Dick tương ứng bằng các chữ cái $K$, $J$, $D$. Ta không biết lời khai nào trong số này là đúng, lời khai nào là sai. Nhưng ta biết điều sau:

1) hoặc Claude nói thật, khi đó Jacques nói dối, hoặc Claude nói dối, khi đó Jacques nói thật;
