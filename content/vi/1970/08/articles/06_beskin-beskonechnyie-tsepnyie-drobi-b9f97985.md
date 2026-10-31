---
id: 1970-8-beskin-beskonechnyie-tsepnyie-drobi-b9f97985
issue: kvant_1970_8
year: 1970
number: "8"
title: Phân số tiếp tục vô hạn
authors:
  - Бескин Н. М.
rubric: osnovnye-stati
page_first: 12
page_last: 22
page_labels: 10, 11, 12, 13, 15, 16, 17, 19, 20
lang: vi
source: kvant_digital
extraction: vision
content_sha256: a8c1438a1b7372e3d38588fa5d4879665099cc9c3b187ced87a86a0ee41d5638
prompt_sha256: draft-1
translated_from: content/ru/1970/08/articles/06_beskin-beskonechnyie-tsepnyie-drobi-b9f97985.md
source_content_sha256: 2100604db4c5c37f7e3f02682bc2730780d0993b2ceed68db8db1c5cc750d2c5
translation_model: draft
translation_run: vi-draft-gaps-2026-11-01
translation_quality: draft
---

⟦folio 10⟧

---
running_head:
folio:
---

có giá trị lớn
phân số

N. M. Beskin

10

⟦folio 11⟧

1. Giới thiệu

1. Tuyên bố của câu hỏi.
Trong bài viết trước («Kvant», số 1), vấn đề biểu diễn bất kỳ số hoạt động nào dưới dạng phân số nguyên đã được nêu. Tuy nhiên, nó không được phép. Khi bắt đầu cuộc hành trình xa hơn, tôi sẽ nhận thức được những gì đã làm được và những gì còn phải làm.

Vấn đề có hai phần.

Phần đầu tiên. Cho biết cách mỗi số thực $\alpha$ được gán một phân số nguyên. Phương pháp này được biểu thị dưới dạng một quy trình trong đó có hai bước thông qua vali (xem «Kvant» Số 1, trang 21).

Nếu số $\alpha$ là hợp lý thì quá trình sẽ dừng và thu được phân số nguyên cuối cùng. Nếu $\alpha$ là vô tỷ thì quá trình này trở thành vô hạn và tạo ra một ký hiệu vô hạn

$$\alpha \sim [a_0; a_1, a_2, \ldots]$$

(1.1)

Ngoài ra còn có ví dụ trong bài viết đầu tiên. Hãy để chúng tôi trình bày thêm một số hình học bài toán thuộc loại này.

Ví dụ 1. Trong một tam giác đều có góc ở đỉnh bằng 108°, hãy biểu thị (dưới dạng phân số nguyên) tỉ số giữa đáy và cạnh.

Trong tam giác $ABC$ (hình 1) các góc là 108°, 36°, 36°. Chúng tôi đặt $BB_1 = b$ sang một bên (rõ ràng là $b$ sẽ phù hợp với $a$ một lần, vì $a < 2b$).

chúng tôi có

$$\frac{a}{b} = \frac{BC}{BB_1} = \frac{BB_1 + B_1C}{BB_1} =$$

$$= 1 + \frac{B_1C}{BB_1} = 1 + \frac{1}{x_1},$$

$$x_1 = \frac{BB_1}{B_1C} = \frac{AC}{B_1C}.$$

Không có tam giác $B_1AC$ nào giống tam giác ban đầu $ABC$ (đếm các góc). Trong công thức đầu tiên, chúng ta đã xác định tỷ lệ $\frac{a}{b}$ của đáy và cạnh. Trong phần thứ hai, chúng ta lại gặp phải vấn đề tương tự: $x_1$ là tỷ lệ giữa đáy và cạnh bên trong một tam giác có cùng góc. Nếu sau bước đầu tiên chúng ta quay lại vị trí bắt đầu thì quá trình sẽ không có hồi kết. Bạn có thể viết

$$\frac{a}{b} \sim [1; 1, 1, \ldots].$$

(1.2)

Thật dễ dàng để chứng minh điều đó

$$\frac{b}{a} \sim [0; 1, 1, \ldots]^*.$$

(1.3)

Ví dụ 2. Biểu thị tỉ số giữa các cạnh của số thập phân đúng nội tiếp đường tròn và bán kính.

*) Xem bài toán 4 ở cuối phần thống kê.

⟦folio 12⟧

Trên hình 2 $O$ là tâm của đường tròn, $AB=a_{10}$, $AL$ là các đường phân giác của góc $A$. Rõ ràng là $AB=AL=OL$:
$$\frac{a_{10}}{R} = \frac{AL}{OA}.$$
Nhưng tam giác $LOA$ có các góc bằng tam giác trên hình 1. Vì vậy,
$$\frac{a_{10}}{R} \sim [0; 1, 1, \dots].$$
Ví dụ 3. Biểu diễn tỉ số của đường chéo so với cạnh.
Ví dụ này phức tạp hơn ví dụ 1. Ở đó, sau một bước, chúng ta chỉ cần quay lại vị trí bắt đầu và ở đây, sau hai bước (hình 3).

Vị trí bắt đầu: bạn cần nằm nghiêng xuống theo đường chéo. Nó sẽ tắt một lần (hình 3). chúng tôi có
$$\frac{d}{a} = \frac{CA}{CB} = \frac{CB_1 + B_1A}{CB} = 1 + \frac{1}{x_1},
$$
$$x_1 = \frac{CB}{B_1A} = \frac{AB}{AB_1}.$$
Câu chuyện $B_1B_2 \perp AC$. Sau đó $BB_2 = B_1B_2$ (hãy tự chứng minh). Hãy bổ sung hình tam giác $AB_1B_2$ thành một hình vuông (chỉ để cho rõ ràng, điều này không cần thiết để chứng minh). Bây giờ chúng ta đặt $AB$, $BA$ sang một bên. Đặt nó sang một bên và nhận được $BB_2$. Vậy là để lại $B_2A$. Bạn có thể tiếp tục lùi $AB_1$ đến $B_2A$, nhưng đây là vị trí bắt đầu: lệch cạnh của hình vuông theo đường chéo. Điều này có nghĩa là sự tha thứ là vô tận, tức là.
$$x_1 = 1 + \left(1 + \frac{1}{x_1}\right) = 2 + \frac{1}{x_1},$$

$$\frac{d}{a} \sim [1; 2, 2, \dots].$$
$$\frac{a}{d} \sim [0; 1, 2, 2, \dots].$$
Nhưng có vẻ như chúng ta đã quá say mê với những ví dụ thú vị. Hãy quay trở lại phát biểu của vấn đề.

Phần thứ hai. Cho biết phương pháp gán mỗi phân số nguyên một số thực $\alpha$. Nếu toàn bộ phần này thu được bằng cách phân tách số $\alpha$, thì phương pháp được yêu cầu sẽ dẫn đến chính số này $\alpha$.

Phần thứ hai của bài toán cho đến nay chỉ được giải với các phân số nguyên hữu hạn. Toàn bộ phân số cuối cùng có thể được "thu gọn", nghĩa là nó có thể được biểu diễn dưới dạng phân số thông thường ("hai tầng"). Điều này không thể thực hiện được với một phân số nguyên vô hạn. Phân số nguyên vô hạn (1.1) vẫn chỉ là một ký hiệu. Nó có thể được xem như một hình mẫu hoặc vật trang trí, nhưng nó không có ý nghĩa gì cả. Do đó, trong các công thức (1.1)–(1.6) chúng ta viết dấu tương ứng chứ không phải dấu bằng. Ví dụ, công thức (1.6) biểu thị rằng nếu chúng ta áp dụng quá trình khai triển thành một phân số nguyên cho hệ thức $\frac{a}{d}$, thì chúng ta sẽ nhận được $[0; 1, 2, 2, \dots]$.
Nhưng không thể nói bên trái bằng bên phải, vì bên phải chưa phải là số.

Gán ký hiệu cho ký hiệu
$$|a_0; a_1, a_2, \dots|$$
đây là toàn bộ bài viết này
Nhưng có một con đường dài để đạt được mục tiêu này.
2. Khi bắt đầu các phần nóng lồng nhau. Giả định rằng người đọc đã quen thuộc dưới mọi hình thức với lý thuyết số thực, nghĩa là biết cách giới thiệu số vô tỷ và phân số thập phân vô hạn là gì.
Chúng ta hãy nhớ lại nguyên tắc phân đoạn lồng nhau, điều này rất quan trọng đối với nội dung tiếp theo *).

*) Từ phần trình bày ngắn gọn sau đây khó có thể làm suy yếu nguyên tắc tinh tế này. Chúng tôi đề nghị rằng người đọc đã quen thuộc với anh ta. Nếu không, chúng tôi khuyên bạn nên đọc, ví dụ: N. Ya. V. và Lenkin và S. I. Shvartsburg, Toán học

⟦folio 13⟧

Nếu có một chuỗi vô hạn các phân đoạn $[a_1, b_1]$, $[a_2, b_2], \ldots, [a_n, b_n]$ trên một dòng có hai thuộc tính:

1) mỗi phân đoạn tiếp theo phải ở phân đoạn trước đó,
$$a_n \leq a_{n+1} < b_{n+1} \leq b_n;$$

2) độ dài của các đoạn có xu hướng bằng 0 khi $n \to \infty$, khi đó tồn tại một điểm x và đồng thời là điểm duy nhất thuộc về tất cả các đoạn này.

Giải thích 1. Đoạn $[a, b]$ chứa tất cả các điểm của đường thẳng nằm giữa $a$ và $b$, cũng như các điểm $a$ và $b$. Khoảng $(a, b)$ chỉ chứa các điểm nằm giữa $a$ và $b$, nhưng không chứa các điểm cuối. Điều này có nghĩa là đoạn $[a, b]$ chứa thêm hai điểm so với khoảng $(a, b)$.

Giải thích 2. Thuộc tính thứ hai có nghĩa là: nếu chúng ta sửa bất kỳ số ε nào lớn hơn 0, thì trong chuỗi này có một đoạn nhỏ hơn độ dài, tức là có một số $n$ sẽ là $a_n b_n < \epsilon$ (ký hiệu $a_n b_n$ biểu thị độ dài của đoạn $[a_n, b_n]$). Tất nhiên, tất cả các phân đoạn có số lớn hơn $n$ cũng sẽ nhỏ hơn $\epsilon$.

Nguyên tắc các đoạn lồng nhau thể hiện tính liên tục của một đường thẳng. Bất cứ nơi nào các đoạn thẳng này phụ thuộc, nơi đó có một điểm trên đường thẳng. Nếu bạn loại bỏ ít nhất một điểm khỏi một đường thì đối với tập hợp các điểm còn lại, nguyên tắc này không còn đúng nữa. Ví dụ, hãy loại bỏ điểm O trên trục số và xem xét một tập hợp các phân đoạn

$$[-1, 1], \left[-\frac{1}{2}, \frac{1}{2}\right], \left[-\frac{1}{3}, \frac{1}{3}\right], \ldots, \left[-\frac{1}{n}, \frac{1}{n}\right], \ldots$$

phân tích ical (sách giáo khoa lớp 1X-10 ở các trường trung học chuyên ngành toán), M., “Prosveshchenie”, 1969, ch. 1, trang 31.

*) Đây sẽ không phải là những đoạn thẳng: chúng đều có một vết thủng bên trong. Đây là các đoạn của tập hợp hai tia đang xét. Đoạn $[-1, 1]$ chứa các đầu $-1$ và $1$ và tất cả các điểm trung gian của tập hợp này.

Không có điểm nào thuộc về tất cả chúng: chúng bị hút lại với nhau vào một khoảng trống.

Để cho ngắn gọn, các điểm trên trục số thường được xác định bằng các số tương ứng: họ nói “điểm x” và “số x” mà không phân biệt.

Số thực lấp đầy toàn bộ trục số, nghĩa là có sự tương ứng 1-1 giữa số thực và điểm trên trục số. Vì vậy, nguyên tắc phân đoạn lồng nhau cũng có giá trị đối với tập hợp số thực. Nó không đúng với tập hợp số hữu tỉ.

II. Thuộc tính của phân số phù hợp

Đối với các bài toán lời giải đặt ra ở Phần 1, chúng ta cần nghiên cứu chi tiết hơn tính chất của các phân số phù hợp.

3. Quy luật hình thành các phân số thích hợp. Bằng cách khai báo một phân số nguyên sau mỗi thương riêng phần, chúng ta thu được một dãy số hữu tỷ

$$\alpha_0 = \frac{p_0}{q_0} = \frac{a_0}{1},$$

$$\alpha_1 = \frac{p_1}{q_1} = [a_0; a_1] = a_0 + \frac{1}{a_1} = \frac{a_1 a_0 + 1}{a_1}$$, v.v.

Và không. Điều này áp dụng như nhau cho các phân số nguyên hữu hạn và vô hạn. Mặc dù chúng ta vẫn chưa biết ý nghĩa của một phân số nguyên vô hạn, nhưng ý nghĩa của các số $\alpha_0, \alpha_1, \ldots$ khá rõ ràng.

Chúng ta hãy đồng ý rằng với phân số 0 và phân số phù hợp đầu tiên, chúng ta chỉ muốn nói đến những dạng được viết ở bên phải của công thức cuối cùng. Điều này có nghĩa là chúng ta xác định theo một cách nhất định tử số và mẫu số của các phân số này, được lấy riêng biệt;

$$p_0 = a_0, p_1 = a_1 a_0 + 1,$$

$$q_0 = 1, q_1 = a_1.$$

Ví dụ: đối với phân số nguyên $[2; 3, 1, 6] \alpha_1$ chúng ta có thể viết

⟦folio 15⟧

Đầu tiên, toàn bộ hàng đầu tiên và hai cột đầu tiên được điền. Việc điền thêm vào bảng được thực hiện theo sơ đồ sau:

| $a_{n-2}$ | $a_{n-1}$ | $a_n$ |
| :--- | :--- | :--- |
| $p_{n-2}$ | $p_{n-1}$ | |

1) cột $\left| \frac{p_{n-1}}{q_{n-1}} \right|$ nhân với $a_n$,

2) thêm cái trước vào cột kết quả.

Bạn nên sử dụng sơ đồ tương tự nếu bạn cần tính giá trị của toàn bộ phân số tiếp theo: cột cuối cùng $\left| \frac{p_s}{q_s} \right|$ sẽ cung cấp câu trả lời đầy đủ.

Luyện tập điền vào bảng phân số tiếp [0; 3, 14, 1, 2, 5]

| 0 | 3 | 14 | 1 | 2 | 5 |
| :--- | :--- | :--- | :--- | :--- | :--- |
| 0 | 1 | 14 | 15 | 44 | 235 |
| 1 | 3 | 43 | 46 | 135 | 721 |

4. Sự khác biệt của các phân số phù hợp liền kề. Bước từ phân số thích hợp thứ $n$ tới phân số tiếp theo được biểu thị bằng phân số thứ $n$ và được ký hiệu là $\Delta_n$:

$$\Delta_n = \frac{p_{n+1}}{q_{n+1}} - \frac{p_n}{q_n} = \frac{p_{n+1} q_n - p_n q_{n+1}}{q_n q_{n+1}} = \frac{D_n}{q_n q_{n+1}},$$

trong đó $D_n$ biểu thị số

$$D_n = p_{n+1} q_n - p_n q_{n+1}.$$

Hãy hạ thấp các chỉ số $y$ $p_{n+1}$ và $q_{n+1}$ theo công thức (3.2):

$$D_n = \left( p_n a_{n+1} + p_{n-1} \right) q_n - p_n \left( q_n a_{n+1} + q_{n-1} \right) = -\left( p_n q_{n-1} - p_{n-1} q_n \right).$$

Biểu thức trong ngoặc đơn có cùng loại với (**), nhưng tất cả các chỉ mục đều bằng một

ít hơn. Vì vậy, nó đại diện cho $D_{n-1}$:

$$D_n = -D_{n-1}.$$

Mối quan hệ lặp lại này cho phép bạn hạ chỉ mục xuống 0:

$$D_n = -D_{n-1} = D_{n-2} = -D_{n-3} = \dots = (-1)^n D_0.$$

Để thành công hoàn toàn, tất cả những gì còn lại là tính toán trực tiếp $D_0$:

$$D_0 = p_1 q_0 - p_0 q_1 = (a_1 a_0 + 1) \cdot 1 - a_0 a_1 = 1.$$

Kể từ đây,

$$D_n = p_{n+1} q_n - p_n q_{n+1} = (-1)^n,$$

(4.1) và theo công thức (*)

$$\Delta_n = \frac{p_{n+1}}{q_{n+1}} - \frac{p_n}{q_n} = \frac{(-1)^n}{q_n q_{n+1}}.$$

5. So sánh số lẻ lớn hơn các phân số lân cận (trước và sau). Phân số lẻ thích hợp nào nhỏ hơn các phân số lân cận của nó.

Khi áp dụng công thức này cho phân số 0 và phân số thích hợp cuối cùng, chúng ta phải tính đến việc mỗi phân số đó chỉ có một phân số lân cận.

Tính đúng đắn của tính chất này được thấy rõ ngay từ công thức (4.2).

Thuộc tính 1 có nghĩa là các phân số phù hợp liên tiếp lần lượt lớn hơn và nhỏ hơn.

Thuộc tính 2. Sự khác biệt giữa các phân số liền kề về giá trị abscimal bị loại bỏ (nghĩa là: khi số lượng tăng lên).

Hãy so sánh:

$$|\Delta_n| = \frac{1}{q_n q_{n+1}},$$

$$|\Delta_{n+1}| = \frac{1}{q_n+1 q_{n+2}}.$$

Chúng tôi có $q_{n+2} > q_n$. Điều này có nghĩa là phân số thứ hai có mẫu số lớn hơn nhưng bản thân nó lại nhỏ hơn:

$$|\Delta_{n+1}| < |\Delta_n|.$$

6. Tính bất khả quy của các phân số thích hợp. Tất cả các phân số thích hợp đều không thể rút gọn được.

⟦folio 16⟧

Nhớ lại rằng tử số và mẫu số của các phân số thích hợp được hình thành theo công thức (3.1). Giả sử rằng phân số $\frac{p_n}{q_n}$ có thể rút gọn, tức là tử số và mẫu số của nó có thừa số chung $\lambda$, khác một:

$$p_n = \lambda p_n', \quad q_n = \lambda q_n'.$$

Khi đó công thức (4.1) cho

$$\lambda (p_{n+1} q_n' - p_n' q_{n+1}) = (-1)^n.$$

Chúng ta đang mắc kẹt với một đẳng thức vô lý: vế trái chia hết cho $\lambda$, còn vế phải thì không. Điều này có nghĩa là phân số $\frac{p_n}{q_n}$ là tối giản.

III. Giới thiệu phân số vô hạn

7. Ý nghĩa của phân số liên tục vô hạn. Nguyên tắc phân đoạn lồng nhau sẽ phục vụ chúng ta như một chìa khóa mở ra ý nghĩa của một phân số liên tục vô hạn. Chúng ta hãy nhớ lại một tình huống tương tự: làm thế nào để đùn một phần thập phân vô hạn? Một phân số thập phân vô hạn có thể được coi là ký hiệu viết tắt của một chuỗi các phân đoạn lồng nhau: các phép làm tròn liên tiếp với phần thiếu sẽ cho các đầu bên trái của các phân đoạn này và phần thừa - các phần bên phải. Ý nghĩa của phát biểu $\sqrt{2}$ được biểu thị dưới dạng phân số thập phân vô hạn là gì

$$\sqrt{2} = 1,4142...?$$

Điều này có nghĩa là

$$1 < \sqrt{2} < 2,$$

$$1,4 < \sqrt{2} < 1,5,$$

$$1,41 < \sqrt{2} < 1,42,$$

Có một số duy nhất thỏa mãn tất cả các bất đẳng thức này cùng một lúc. Đây là $\sqrt{2}$.

Có phân số liên tục vô hạn tượng trưng

$$[a_0; a_1, a_2, \dots],$$

có thể tạo thành một chuỗi vô hạn các phân số hữu hạn tiếp tục

$$a_0, [a_0; a_1], [a_0; a_1, a_2], \dots,$$

$$[a_0; a_1, a_2, \dots, a_n], \dots,$$

(**)

có thể được viết dưới dạng phân số thích hợp

$$\frac{p_0}{q_0}, \frac{p_1}{q_1}, \frac{p_2}{q_2}, \dots, \frac{p_n}{q_n}, \dots$$

(***)

Những phân số phù hợp này xác định trình tự của các phân đoạn lồng nhau

$$\left[ \frac{p_0}{q_0}, \frac{p_1}{q_1} \right], \left[ \frac{p_2}{q_2}, \frac{p_1}{q_1} \right], \left[ \frac{p_2}{q_2}, \frac{p_3}{q_3} \right],$$

$$\left[ \frac{p_4}{q_4}, \frac{p_3}{q_3} \right], \dots$$

Mỗi đoạn tiếp theo nằm trong đoạn trước (hình 4) và độ dài của chúng có xu hướng bằng 0 (xem công thức (4.2)). Do đó, có một số $\alpha$ thuộc về tất cả các phân đoạn. Nó thuộc về giá trị của một phân số liên tục vô hạn**).

Định nghĩa này có thể được diễn đạt theo cách khác. Đây là hai lựa chọn.

1) Giá trị của một phân số liên tục vô hạn nằm giữa hai phân số phù hợp liền kề bất kỳ.

2) Giá trị của phân số tiếp tục .befinite lớn hơn doi của phân số phù hợp

(*) Dấu 0, 1, 2, ... trên hình 4 đọc số phân số phù hợp.

**) Điều này định nghĩa thuật ngữ "phân số phù hợp", nó "khớp" ngày càng gần điểm $\alpha$.

⟦folio 17⟧

bi với số chẵn và nhỏ hơn mọi phân số phù hợp có số lẻ (tất cả điều này được thể hiện rõ ràng trên hình 5).

Điều quan trọng là phải hiểu rằng bất kỳ công thức nào trong số này đều xác định một số ít.

Thật dễ dàng để chỉ ra (làm điều này) rằng nếu số vô tỷ $\alpha$ bị phân tách thành một phân số nguyên, thì các phân số phù hợp liên tiếp lần lượt nhỏ hơn và lớn hơn $\alpha$. Theo đó, số $\alpha$ này là giá trị hiện được gán cho phân số nguyên vô hạn (sự thống nhất của điểm thuộc tất cả các phân đoạn!). Những người khác được phép viết

$$\alpha = [a_0; a_1, a_2, \dots].$$

Bây giờ rõ ràng là mỗi phân số phù hợp có thể được coi là xấp xỉ của toàn bộ phân số. Số càng lớn thì phép tính gần đúng càng chính xác.

Hầu như điều tương tự cũng được nói về việc xấp xỉ một phân số nguyên hữu hạn bằng các phân số thích hợp. Sự khác biệt duy nhất là trong trường hợp một phân số nguyên vô hạn, không có phân số tốt cuối cùng và đáng kể, không có phân số tốt nào mang lại giá trị mạnh mẽ của toàn bộ phân số.

Đối với các phân số nguyên vô hạn, dấu đẳng thức được giữ nguyên («Kvant», Số 1, trang 22). Hãy xây dựng nó như thế này:

1) Hai phân số nguyên vô hạn $[a_0; a_1, a_2, \dots, a_n, \dots]$ và $[b_0; b_1, b_2, \dots, b_n, \dots]$ bằng nhau khi và chỉ khi các phần tử tương ứng của chúng trùng nhau, tức là $a_n = b_n$ với $n=0, 1, 2, \dots$.

2) Một phân số nguyên vô hạn không thể bằng một phân số hữu hạn.

8. Và sự gần đúng của một phân số và phân số phù hợp. Người đọc có nhớ khi chúng tôi bắt đầu cuộc hành trình dài này không? Chúng tôi đang tìm kiếm một cách thuận lợi để tính gần đúng số thực (bao gồm cả số hữu tỷ) với số hữu tỷ.

Chuyện gì đã xảy ra vậy! Đây có phải là lỗi đánh máy không? Có thể tính gần đúng số hữu tỉ bằng số hữu tỉ không?

Có thể. Ví dụ,

$$\frac{6187}{7425} \approx \frac{5}{6}.$$

Trong ví dụ này, chúng ta thay thế một số hữu tỉ phức tạp bằng một số hữu tỉ đơn giản hơn.

Khi chúng ta đã làm quen với các phân số nguyên, một dự án tự nhiên nảy sinh là phân tích số $\alpha$ thành một phân số nguyên và đếm các phân số phù hợp liên tiếp là xấp xỉ của số đó. Nói cách khác, cắt bớt toàn bộ phân số, loại bỏ tất cả các phần tử bắt đầu từ một số và lấy phần bị cắt cụt còn lại làm giá trị gần đúng của toàn bộ phân số. Đây chính xác là những gì chúng tôi làm bằng cách cắt bớt phần thập phân và chỉ để lại số franc mong muốn sau dấu thập phân.

Để chấp nhận hoặc từ chối dự án này, chúng tôi cần tìm ra loại lỗi nào chúng tôi cho phép bằng cách thay thế số $\alpha$ bằng một phân số phù hợp, tức là giả sử

$$\alpha \approx \frac{p_n}{q_n}.$$

Trong tất cả các lý do sâu hơn, người ta giả định rằng phân số $\frac{p_n}{q_n}$ không bằng 0 và không phải là phân số cuối cùng. Đối với $n=0$, việc sử dụng toàn bộ phân số không mang lại điều gì mới so với việc sử dụng số thập phân và trường hợp $n=s$ không thú vị vì chúng tôi nhận được $\alpha=\alpha$ và sai số bằng 0.

⟦folio 19⟧

cắt là $|\Delta_n| = \frac{1}{q_n q_{n+1}}$. Điểm $\alpha$ có thể là điểm bên trong của đoạn đó hoặc có thể giống với $\frac{p_{n+1}}{q_{n+1}}$ (nếu $\alpha$ là số hữu tỷ và $\frac{p_{n+1}}{q_{n+1}}$ là phân số khớp cuối cùng). Như vậy,

$$\left| \alpha - \frac{p_n}{q_n} \right| \leqslant |\Delta_n|. \tag{10.1}$$

Đặt $\frac{p}{q} - \text{какая-нибудь дробь}$, có mẫu số nhỏ hơn $q_n$ và do đó nhỏ hơn $q_{n+1}$:

$$q < q_n < q_{n+1}. \tag{10.2}$$

Vì các phân số thích hợp là bất khả quy nên từ bất đẳng thức (10.2) suy ra

$$\frac{p}{q} \neq \frac{p_n}{q_n}, \quad \frac{p}{q} \neq \frac{p_{n+1}}{q_{n+1}}.$$

Rõ ràng là vậy

$$\left| \frac{p}{q} - \frac{p_n}{q_n} \right| = \frac{|pq_n - p_n|}{qq_n} \geqslant \frac{1}{qq_n},$$

$$\left| \frac{p}{q} - \frac{p_{n+1}}{q_{n+1}} \right| = \frac{|pq_{n+1} - p_{n+1}|}{qq_{n+1}} \geqslant \frac{1}{qq_{n+1}}.$$

Những bất đẳng thức này vẫn thành công nếu chúng ta thay thế $q$ bằng giá trị lớn hơn của $q_{n+1}$ hoặc $q_n$:

$$\left| \frac{p}{q} - \frac{p_n}{q_n} \right| > \frac{1}{q_{n+1} q_n} = |\Delta_n|,$$

$$\left| \frac{p}{q} - \frac{p_{n+1}}{q_{n+1}} \right| > \frac{1}{q_n q_{n+1}} = |\Delta_n|.$$

Ý nghĩa của hai bất đẳng thức cuối như sau: phân số $\frac{p}{q}$ được lấy đi khỏi mỗi đầu của đoạn $\left[ \frac{p_n}{q_n}, \frac{p_{n+1}}{q_{n+1}} \right]$ ở một khoảng cách lớn hơn độ dài của đoạn này $|\Delta_n|$. Trì hoãn đoạn $|\Delta_n|$ (hình 6) từ các điểm $\frac{p_n}{q_n}$ và $\frac{p_{n+1}}{q_{n+1}}$ sang trái và phải, chúng ta thu được vùng cấm $AB$, trong đó không thể định vị được phân số $\frac{p}{q}$ (điểm $A$ và $B$ cũng bị cấm). Hiện tại rõ ràng rằng $\frac{p}{q}$ là giá trị gần đúng kém hơn cho số $\alpha$ so với $\frac{p_n}{q_n}$. Trong thực tế,

$$\left| \alpha - \frac{p_n}{q_n} \right| \leqslant |\Delta_n|,$$

$$\left| \alpha - \frac{p}{q} \right| > |\Delta_n|.$$

Lưu ý rằng định lý ngược lại không đúng, tức là có những phân số không đóng vai trò là phân số phù hợp nhưng vẫn cho giá trị gần đúng của số $\alpha$ tốt hơn bất kỳ phân số nào có giá trị nhỏ hơn. Ví dụ: từ bảng ở trang 18 («Kvant», Số 1), rõ ràng là các giá trị gần đúng của các số $19/6$, $\frac{16}{5}$ và $\frac{13}{4}$ có đặc tính này. Vì vậy, định lý được chứng minh không có nghĩa là các phân số thích hợp sẽ tốt hơn các phân số khác trong việc xấp xỉ số thực. Nhưng đây là hai định lý mạnh theo chiều ngang mà chúng tôi sẽ trình bày mà không cần chứng minh.

Đối với một phần thích hợp, hệ số lợi ích $^*$) $\lambda = \frac{1}{2|q_n \alpha - p_n|}$ lớn hơn bất kỳ phần nào khác có giá trị nhỏ hơn.

Cuối cùng, điều đáng ngạc nhiên nhất: định lý ngược lại cũng đúng, tức là nó có hệ số sinh lời lớn như vậy $^*$) «Kvant», số 1, tr. 18.

⟦folio 20⟧

ity - một đơn cực của các phân số phù hợp. Thuộc tính rất tinh tế này không thể không gây hứng thú cho bất kỳ độc giả yêu thích những con số nào.

Nếu đối với số α và phân số $\frac{p}{q}$, hệ số lợi ích $\lambda = \frac{1}{2|q\alpha - p|}$ lớn hơn bất kỳ phân số nào có giá trị nhỏ hơn thì $\frac{p}{q}$ là phân số phù hợp cho α.

Ví dụ. Từ cùng một bảng về số π, rõ ràng phân số $\frac{22}{7}$ cho giá trị gần đúng của π với hệ số ưu việt lớn hơn các phân số có giá trị 1, 2, 3, 4, 5, 6. Do đó, chưa biết cách khai triển π thành một phân số liên tục, dựa trên định lý cuối cùng, chúng ta có thể kết luận rằng $\frac{22}{7}$ là một phân số phù hợp.

Còn rất nhiều định lý thuộc loại này. Tất cả chúng, từ các quan điểm khác nhau, đều xác nhận một điều giống nhau: nếu bạn cần tính gần đúng một số thực bằng các số hữu tỷ đơn giản, thì điều tốt nhất nên làm là sử dụng các phân số phù hợp.

Đây là chìa khóa quý giá cho những câu đố được thảo luận trong bài viết đầu tiên.

Bài tập.

1. Biểu thị (dưới dạng phân số liên tục) tỉ số giữa cạnh và đáy trong một tam giác cân có góc bằng 120°.

2. Tìm giá trị của phân số tiếp theo trong công thức (1.2). Tìm cos 36°.

3. Tìm giá trị của phân số tiếp theo trong công thức (1.4). Biểu thị $a_{10}$ theo R. Tìm sin 18°.

4. Cho phân tích phân số liên tục (hữu hạn hoặc vô hạn) của số α, hãy tìm phân tích của số $\frac{\beta}{\alpha}$.

5. Bài báo nói rằng giá trị của các phân số phù hợp sẽ tăng lên (bất đẳng thức (3.3)). Điều tương tự có thể được nói về con số?
