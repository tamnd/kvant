---
id: 1974-9-gerver-ot-peremenyi-mest-slagaemyih-7f4e5509
issue: kvant_1974_9
year: 1974
number: "9"
title: Từ việc thay đổi vị trí của các thuật ngữ...
authors:
  - Гервер М. Л.
rubric: osnovnye-stati
page_first: 16
page_last: 20
page_labels: 14, 15, 17, 18
tag: 2N6D
lang: vi
source: kvant_digital
extraction: vision
content_sha256: 1beeebf09466554b37e7e37bbebdb9e476cd997cf78b4b364835a36dea9050cd
prompt_sha256: draft-1
translated_from: content/ru/1974/09/articles/06_gerver-ot-peremenyi-mest-slagaemyih-7f4e5509.md
source_content_sha256: 2f91f393a389d5004080e70a36ec848800f1a660249edd52d711c73e62a098f1
translation_model: draft
translation_run: vi-draft-2026-11-03
translation_quality: draft
---

⟦folio 14⟧

Một số điều trong «Kvant» rất khó nói, không phải vì bản thân chúng khó mà vì để hiểu chúng, bạn nên biết trước một điều gì đó ngoài chương trình giảng dạy ở trường. Thậm chí không tách rời khỏi nó, nhưng sâu hơn một chút. Ví dụ, học sinh trung học biết giới hạn trình tự là gì, nhưng họ biết nó một cách trực tiếp khá hời hợt. Cụ thể, tài liệu này phải thông thạo mới có thể hiểu được bài viết đề xuất, trong đó chứng minh định lý thay thế Riemann về hoán vị các điều kiện của chuỗi hội tụ.

Trong «Kvant» số 3 năm 1974, chúng tôi cung cấp cho độc giả 20 bài toán về giới hạn. Bất cứ ai đã hoàn thành nhiệm vụ đều có thể đảm nhận bài viết này một cách an toàn.

Tuy nhiên, đã quyết định bài toán, đừng đặt bút và giấy sang một bên: nội dung chính của bài viết có rất nhiều bài tập; Chỉ bằng cách tự mình giải quyết chúng, bạn mới có thể thực sự hiểu được mọi thứ.

Tổng của chuỗi

Hãy bắt đầu với những bài tập rất đơn giản.

1. a) Tìm tổng $S_n$ của $n$ số hạng đầu tiên của cấp số nhân

$$\frac{1}{2}, \frac{1}{4}, \frac{1}{8}, \frac{1}{16}, \dots$$

6) Tương tự cho sự tiến triển

$$\frac{1}{2}, -\frac{1}{4}, \frac{1}{8}, -\frac{1}{16}, \dots$$

Đáp số: a) $S_n = 1 - \frac{1}{2^n}$; 6) $S_n = \frac{1}{3} \left[ 1 - \left( -\frac{1}{2} \right)^n \right]$.

2. Tìm tổng $S^{(1)}$ và $S^{(2)}$ của cấp số nhân vô tận (1) và (2).

Đáp số: $S^{(1)} = 1, S^{(2)} = \frac{1}{3}$.

Có thể tìm thấy tổng $S^{(1)}$ và $S^{(2)}$ bằng công thức làm sẵn $S = \frac{b_1}{1-q}$ (trong đó $b_1 = 1-1$ là số hạng và $q$ là mẫu số của cấp số nhân vô hạn):

$$S^{(1)} = \frac{1}{2} \cdot \frac{1}{1-\frac{1}{2}} = 1,$$

$$S^{(2)} = \frac{1}{2} \cdot \frac{1}{1+\frac{1}{2}} = \frac{1}{3}$$.

Bạn có thể làm khác, sử dụng Bài tập 1. Ví dụ: hãy tìm $S^{(1)}$ theo cách này. Với $n = 1, 2, 3 \dots$ chúng ta thu được một phần tổng:

$$S_1 = 1 - \frac{1}{2}, \quad S_2 = 1 - \frac{1}{2^2},$$

$$S_3 = 1 - \frac{1}{2^3}, \dots, \quad S_n = 1 - \frac{1}{2^n}, \dots$$

Dãy số (3) tiến tới giới hạn $S^{(1)} = 1$. Giới hạn này, theo định nghĩa, được gọi là tổng của các hình chiếu (1).

Hai lời giải đã cho trên thực tế không khác nhau: công thức $S = \frac{b_1}{1-q}$ được suy ra từ công thức

⟦folio 15⟧

Hãy biểu thị $S_n = b_1 \cdot \frac{1 - q^n}{1 - q}$ dưới dạng chuyển tiếp. Chúng ta sẽ cho lời giải số nguyên tố để điền vào một số tổng nhất định của cấp số nhân giảm vô hạn. Và chúng tôi cần điều này để đưa ra định nghĩa chung sau đây.

Sự định nghĩa. Đặt $a_1, a_2, a_3, \dots$ là một số tùy ý trong dãy. Biểu thức $a_1 + a_2 + a_3 + \dots$ có tên đặc biệt: $p$rd. Chúng tôi tạo thành một chuỗi các tổng một phần:

$$S_1 = a_1, S_2 = a_1 + a_2, S_3 = a_1 + a_2 + a_3, \dots, S_n = S_{n-1} + a_n, \dots$$

Nếu chuỗi này có giới hạn $S$ thì người ta nói rằng $p$rd

$$a_1 + a_2 + a_3 + \dots + a_n + \dots = S.$$

Nếu $p$rd $a_1 + a_2 + a_3 + \dots$ không hội tụ thì nó được gọi là phân kỳ.

Bài tập
3. Cho ví dụ về chuỗi phân kỳ:
a) nghĩ ra một chuỗi có tổng từng phần tiến tới vô cùng;
b) nghĩ ra một chuỗi trong đó dãy tổng riêng không tiến tới bất kỳ số nào và không tiến tới vô cùng.
4. Chứng minh rằng chuỗi
$$1 + \frac{1}{1!} + \frac{1}{2!} + \frac{1}{3!} + \dots + \frac{1}{n!} + \dots$$
hội tụ. Tổng của nó là số có giá trị $e^*$ (cơ số logarit tự nhiên). Chứng minh rằng $2 < e < 3$. Chứng minh rằng $e$ là số vô tỉ.
5. Chứng minh rằng chuỗi
$$1 + \frac{1}{2^2} + \frac{1}{3^2} + \dots + \frac{1}{n^2} + \dots$$
hội tụ và tổng của nó là $S < 2$. Với số tự nhiên nào $k$ thì chuỗi hội tụ?
$$1 + \frac{1}{2^k} + \frac{1}{3^k} + \dots + \frac{1}{n^k} + \dots$$?

Gợi ý. Nếu tất cả các số hạng của dãy đều dương (như trong Bài tập 4 và 5),

*) Xem bài viết của L. G. Limanov “Về số $e$ và $n!$”, «Kvant», 1972, Số 5.

sau đó, để chứng minh sự hội tụ của một chuỗi, chỉ cần kiểm tra xem tất cả các tổng riêng có nhỏ hơn một số (giống) nào đó $C$ hay không là đủ; thì sự hội tụ của dãy tổng riêng xuất phát từ thực tế là mọi khả năng xác định dãy đều có giới hạn.

6. Chuỗi có hội tụ không?
$$1 - \frac{1}{2} + \frac{1}{3} - \frac{1}{4} + \frac{1}{5} - \frac{1}{6} + \dots + \frac{1}{2n-1} - \frac{1}{2n} + \dots$$

Có thể tổng hợp các thuật ngữ tích cực và tiêu cực một cách riêng biệt?

Bạn đã tìm được tổng của chuỗi
$$\frac{1}{2} - \frac{1}{4} + \frac{1}{8} - \frac{1}{16} + \dots$$

(nó bằng $\frac{1}{3}$). Có thể tính nó như sau: đầu tiên cộng tất cả các số hạng dương của chuỗi, sau đó là tất cả các số hạng âm, rồi cộng các kết quả lại?

Tại sao không? Hãy thử:
$$\frac{1}{2} + \frac{1}{8} + \frac{1}{32} + \dots = \frac{1}{2} \cdot \frac{1}{1 - \frac{1}{4}} = \frac{2}{3},$$
$$-\frac{1}{4} - \frac{1}{16} - \frac{1}{64} - \dots = \left(-\frac{1}{4}\right) \cdot \frac{1}{1 - \frac{1}{4}} = -\frac{1}{3},$$
$$\frac{2}{3} - \frac{1}{3} = \frac{1}{3}.$$

Đáp số, trong mọi trường hợp, hóa ra là đúng. Anh ấy hỏi: có phải lúc nào cũng có thể hành động theo cách này không?

Bài tập
7. Chuỗi $a_1 + a_2 + a_3 + \dots$ hội tụ. Tổng của nó là $S$. Có thể tính nó như sau: đầu tiên tính tổng tất cả các số hạng dương $a_n$, sau đó là tất cả các số hạng âm, rồi cộng các kết quả lại?
8. Chuỗi $a_1 + a_2 + a_3 + \dots$ hội tụ. Tổng của nó là $S$. Người ta cho rằng nếu chúng ta tính tổng tất cả các số hạng dương $a_n$ thì số $q$. Chúng ta có thể nói điều đó $p + q = S$ không?

⟦folio 17⟧

Bài tập

11. Có phải chuỗi (8) hội tụ và chuỗi (7) phân kỳ?

12. Chuỗi (5) hội tụ như thế nào - có điều kiện hay tuyệt đối?

13. Chứng minh rằng chuỗi ở Bài tập 8 hội tụ tuyệt đối.

14. Điều gì xảy ra nếu tổng của chuỗi (5) được tính bằng cách sử dụng retty gợi ý trong bài tập 7?

15. Chứng minh rằng tổng của một chuỗi hội tụ tuyệt đối có thể được tính bằng cách sử dụng lưới trong Bài tập 7.

16. Chứng minh định lý sau đây về hoán vị các số hạng của một chuỗi hội tụ tuyệt đối. Giả sử chuỗi $a_1 + a_2 + a_3 + \dots$ hội tụ tuyệt đối. Hãy sắp xếp lại các thành viên của nó một cách ngẫu nhiên. Khi đó chuỗi mới có thể hội tụ tuyệt đối và tổng của cả hai chuỗi đều bằng nhau.

Định lý Riemann

Bằng cách sắp xếp lại các số hạng của bất kỳ điều kiện nào của chuỗi hội tụ, người ta có thể thu được một chuỗi phân kỳ và người ta có thể thu được một chuỗi hội tụ, tổng của nó bằng một số tùy ý được xác định trước.

Để chứng minh định lý này ta cần bổ đề sau

Bổ đề. Nếu chuỗi $a_1 + a_2 + a_3 + \dots$ hội tụ có điều kiện thì chuỗi gồm các số hạng dương của nó sẽ phân kỳ và chuỗi gồm các số hạng âm của nó có thể phân kỳ.

Bài tập

17. Chứng minh bổ đề này (nhớ Bài tập 8, 13 và 15).

18. Cho $a_1 + a_2 + a_3 + \dots$ là một chuỗi hội tụ. Chứng minh rằng dãy $\{a_n\}$ tiến tới 0:
$$\lim_{n \to \infty} a_n = 0.$$

Chứng minh định lý Riemann

A. Hãy để chúng tôi chỉ ra cách các số hạng của chuỗi $a_1 + a_2 + \dots$ phải được sắp xếp lại để thu được một chuỗi phân kỳ có tổng từng phần có xu hướng vô cùng.

Đầu tiên, chúng ta sẽ chỉ viết ra các số hạng dương của chuỗi - cho đến khi tổng của chúng lớn hơn 1 (theo bổ đề, điều này có thể xảy ra). Sau đó chúng ta viết ra số hạng phủ định đầu tiên. Tiếp theo, chúng ta sẽ viết lại các số hạng dương cho đến khi tổng của tất cả các số được viết nhỏ hơn 1, rồi nhỏ hơn -1.

B. Bây giờ chúng ta hãy chỉ ra cách các số hạng của chuỗi $a_1 + a_2 + a_3 + \dots$ phải được sắp xếp lại sao cho chuỗi mới hội tụ về một tổng xác định trước S.

Đầu tiên, chúng ta sẽ chỉ viết ra các số hạng âm của chuỗi cho đến khi tổng của tất cả các số được viết thành S; sau đó chúng ta sẽ thêm một

⟦folio 18⟧

một số số hạng dương sao cho tổng lớn hơn $S$.

Chúng ta hãy tiếp tục viết ra các số hạng phủ định cho đến khi tổng của tất cả các số hạng được viết lại nhỏ hơn $S$; ngay sau khi điều này xảy ra, chúng tôi thêm nhóm số hạng dương thứ hai để toàn bộ tổng vượt quá $S$, v.v.

Ở giai đoạn $n$-th, nhóm số hạng âm tiếp theo được viết ra (cho đến khi tổng của tất cả các số được viết nhỏ hơn $S$), và sau đó là nhóm số hạng dương tiếp theo (cho đến khi toàn bộ tổng lớn hơn $S$). Theo bổ đề, các số hạng của mỗi dấu hiệu là “đủ”.

Theo cách xây dựng, tổng từng phần của chuỗi mới hoạt động như thế này: chúng giết chết cho đến khi chúng nhỏ hơn $S$ và ngay lập tức bắt đầu lan rộng cho đến khi chúng lớn hơn $S$; họ lại giết người và vân vân. Mỗi lần đạt được "nhảy" qua $S$ bằng cách thêm một số hạng duy nhất. Do đó, vì $\lim_{n \to \infty} a_n = 0$, độ lệch của tổng riêng so với $S$ cũng có xu hướng bằng 0, tức là chuỗi mới hội tụ về $S$, đây là điều cần phải chứng minh.

Ví dụ. Hàng ngang
$$-\frac{1}{2} + \frac{1}{2} - \frac{1}{4} + \frac{1}{4} - \frac{1}{4} + \frac{1}{4} - \dots - \frac{1}{2^n} + \frac{1}{2^n} - \dots$$
hội tụ về không. Hãy sắp xếp lại các thành viên của nó sao cho các số của chúng tạo thành dãy 1, 3, 2, 5, 7, 4, 9, 11, 6, ... (hai lẻ - một chẵn). Chúng ta thu được chuỗi $-\frac{1}{2} - \frac{1}{4} + \frac{1}{2} - \frac{1}{4} + \frac{1}{2} - \dots$, hội tụ về $-\frac{1}{2}$; điều này sẽ trở nên rõ ràng ngay lập tức nếu bạn sắp xếp các dấu ngoặc như sau:
$$-\frac{1}{2} + \left(-\frac{1}{4} + \frac{1}{2} - \frac{1}{4}\right) + \left(-\frac{1}{8} + \frac{1}{4} - \frac{1}{8}\right) + \dots$$

Tương tự và khái quát

Hãy cẩn thận với dấu ngoặc đơn! Trong ví dụ trước, chúng tôi đặt dấu ngoặc đơn để đảm bảo rằng chuỗi hội tụ về $-1/2$. Trong trường hợp này, chúng tôi đã hành động đúng (rất dễ để biện minh), nhưng nhìn chung chúng tôi cần phải thận trọng khi đặt dấu ngoặc. Ví dụ đơn giản nhất: chuỗi phân kỳ $1-1+1-1+...$ sau khi đặt dấu ngoặc sau
$$(1-1) + (1-1) + \dots$$
biến thành một chuỗi hội tụ về 0.

Ví dụ này không thú vị lắm. Thực tế sau đây rất đáng được chú ý: có những chuỗi phân kỳ, với vị trí dấu ngoặc thích hợp, sẽ hội tụ về bất kỳ số nào được xác định trước.

Định luật 19. a) Cho ví dụ về dãy số có tính chất vừa nêu.

6) Chứng minh rằng mọi chuỗi thu được từ một chuỗi hội tụ bằng cách đặt dấu ngoặc đơn đều hội tụ và có cùng tổng với chuỗi ban đầu.

c) Gọi $S_n$ là tổng riêng của chuỗi phân kỳ $a_1 + a_2 + a_3 + \dots$, thu được bằng cách sắp xếp lại các số hạng từ một số điều kiện của chuỗi phân kỳ. Đặt $a < b$ là điểm giới hạn của chuỗi $\{S_n\}^*$ và đặt $S$ là điểm tùy ý của đoạn $[a, b]$: $a \leqslant S \leqslant b$. Chứng minh rằng khi đó tồn tại một cách sắp xếp các dấu ngoặc sao cho chuỗi $a_1 + a_2 + a_3 + \dots$ hội tụ về $S$.

ČERO có thể đạt được bằng cách thay đổi các dấu hiệu. Cho $a_1 + a_2 + a_3 + \dots$ là một chuỗi hội tụ có điều kiện tùy ý. Chúng ta hãy đổi dấu của một số số hạng $a_n$ (giữ nguyên phần còn lại $a_n$). Nói cách khác, chúng ta hãy thay thế chuỗi $a_1 + a_2 + a_3 + \dots$ bằng chuỗi $a_1b_1 + a_2b_2 + a_3b_3 + \dots$, trong đó $|b_n| = 1$.

Quy tắc có 20. Chứng minh rằng với mọi số $S$ và mọi điều kiện của dãy $a_1 + a_2 + a_3 + \dots$ người ta có thể chọn các số $b_1, b_2, b_3, \dots$ theo cách này

*) Về định nghĩa điểm giới hạn, xem «Kvant», 1974, Số 3, tr. 30.
