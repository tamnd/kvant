---
id: 1992-3-rademaher-teplits-ob-odnom-svoystve-chisla-30-669a97ee
issue: kvant_1992_3
year: 1992
number: "3"
title: Về một tính chất của số 30
authors:
  - Радемахер Г.
  - Тёплиц О.
rubric: raznoe
page_first: 8
page_last: 12
page_labels: 6, 8, 9, 10
lang: vi
source: kvant_digital
extraction: vision
content_sha256: ea612a1be5cd07e19ffdca66c8bb5bdf743e95cfa753d31f73874960102826c8
prompt_sha256: draft-1
translated_from: content/ru/1992/03/articles/04_rademaher-teplits-ob-odnom-svoystve-chisla-30-669a97ee.md
source_content_sha256: 7bcdbf90b989f997b8b1a3b568c81d458118e9230465e8bb21687e17205757aa
translation_model: draft
translation_run: vi-draft-gaps-2026-11-06
translation_quality: draft
---

⟦folio 6⟧

---
running_head:
folio:
---

GIỚI THIỆU MỘT TÀI SẢN
SỐ 30

G. RADEMACHER,
O. TEPLITS

Bài viết này là bản sửa đổi nhỏ của một chương trong cuốn sách đáng chú ý “Số và Hình” của các nhà toán học nổi tiếng người Đức Hans Rademacher và Otto Toeplitz, xuất bản năm 1930.
Ở nước ta nó đã được dịch, xuất bản thành ba lần vào các năm 1936, 1938 và 1962 và hiện nay là một tài liệu quý hiếm về thư mục.
Có một thời, cuốn sách này gồm 27 bài luận phổ biến về nhiều chủ đề khác nhau trong toán học, đã có ảnh hưởng lớn đến nhiều thế hệ học sinh đam mê toán học và giúp nhiều người trong số họ trở thành nhà toán học chuyên nghiệp.

Sản xuất bài toán

Cả 10 và 21 đều không phải là số nguyên tố, nhưng trong số các thừa số phân tách các số này, không có thừa số nào có thể đồng thời chứa đựng trong các số chung này. Vì vậy, số 10 và 21 được gọi là số nguyên tố cùng nhau. Các số 6 và 10 không thể gọi là số nguyên tố cùng nhau vì chúng có ước chung là 2.

6

⟦folio 8⟧

---
running_head:
folio:
---

Trên thực tế, lớn hơn nhiều so với yêu cầu của bất đẳng thức (1) được thỏa mãn: số nguyên tố gần nhất theo sau $p_5=11$ không chỉ nhỏ hơn
$$\sqrt{2 \cdot 3 \cdot 5 \cdot 7 \cdot 11} = \sqrt{2310} = 48,06...$$
Nó chỉ đơn giản bằng 13, v.v., nhưng với sự bất thường cực độ trong một dãy số nguyên tố thì cực kỳ khó để nói bất cứ điều gì một cách tổng quát về toàn bộ dãy số đó.

Để bạn có thể hình dung các số nguyên tố nằm trong dãy số tự nhiên không đều như thế nào, chúng ta lưu ý rằng, một mặt, có các số nguyên tố, chẳng hạn như 3 và 5, 11 và 13, 17 và 19 ..., hiệu của chúng là hai. Những cặp như vậy được gọi là cặp song sinh đơn giản. Nhân tiện, vẫn chưa biết số lượng các cặp này là hữu hạn hay vô hạn. Mặt khác, có những đoạn dài tùy ý của chuỗi tự nhiên không chứa số nguyên tố nào cả.

Bài tập 2. Chứng minh rằng với mọi số tự nhiên $N$ đều có $N$ hợp số liên tiếp. Gợi ý. Thư giãn các con số $(N+1)!+2, (N+1)!+3, ..., (N+1)!+N+1$.

Bằng cách sử dụng các phương tiện phụ trợ rất phức tạp, P. L. Chebyshev đã chứng minh rằng số nguyên tố bên cạnh $p_n$ là $p_{n+1}<2p_n$. Tất nhiên, điều này có ý nghĩa quan trọng đối với những gì được khẳng định trong thư tín (1). Nhưng câu hỏi đặt ra là liệu bất đẳng thức yếu hơn nhiều (1) có thể được chứng minh một cách đơn giản và hơn nữa bằng các phương pháp cơ bản hay không.

Bài tập
3. Chứng minh bất đẳng thức (1), sử dụng định lý Chebyshev.
4. Chứng minh rằng $p_n>3n$ cho $n \geq 9$.

Kết quả sơ bộ
Một sinh viên đến từ Monstera, Bonze, vào năm 1907, dưới sự hướng dẫn của thầy M. Dehn*) đã đưa ra một kết luận cực kỳ hóm hỉnh,

*) Maxim (1878-1952) - Nhà toán học người Đức, làm việc trong lĩnh vực hình học, đại số và tôpô.

nó không những không cần đến các phương tiện phụ trợ mà Chebyshev sử dụng mà còn không yêu cầu hầu như bất kỳ hoạt động đào tạo toán học nào cả.

Ý chính của chứng minh có liên quan mơ hồ đến định lý Euclid mà chúng ta đã chứng minh. Chỉ để tạo biểu thức từ $n$ các số nguyên tố đầu tiên
$$M=p_1p_2...p_n-1,$$
Chúng ta sẽ chỉ lấy từ toàn bộ dãy số $p_1p_2...p_n$ các số hạng $i$ và cùng một biểu thức $M$ tạo thành các biểu thức $p_i$ sau:
$$M_1=p_1p_2...p_{i-1} \cdot 1-1,$$
$$M_2=p_1p_2...p_{i-1} \cdot 2-1,$$
$$M_3=p_1p_2...p_{i-1} \cdot 3-1,$$
$$M_4=p_1p_2...p_{i-1} \cdot 4-1,$$
...
$$M_{p_i}=p_1p_2...p_{i-1} \cdot p_i-1.$$

Về những biểu thức này, cũng như về các biểu thức về khoảng cách của Euclid, người ta cũng có thể đưa ra nhận định sau:
a) không có biểu thức nào chia hết cho bất kỳ số nào $p_1, p_2, ..., p_{i-1}$;
b) trong tất cả các biểu thức này, không lớn hơn số chia hết cho $p$. Thật vậy, nếu bất kỳ biểu thức nào trong số này, chẳng hạn như $p_1...p_{i-1}x-1$ và $p_1...p_{i-1}y-1$, chia hết cho $p_i$ thì chúng sẽ chia hết cho $p_i$ và hiệu của các biểu thức này $p_1...p_{i-1}(x-y)$, và vì không có yếu tố $i-1$ đầu tiên nào chia hết cho $p_i$ nên hiệu $x-y$ phải chia hết cho nó. Nhưng $x$ và $y$ là từ các số thuộc dãy 1, 2, 3, 4, ..., $p_i$, và hiệu của hai số đó, ngay cả khi số nhỏ hơn trong số chúng là 1 và số lớn hơn là $p_i$, chỉ là $p_i-1$ và do đó, trong mọi trường hợp đều nhỏ hơn $p_i$. Do đó, vì số nhân lớn hơn nên hiệu $x-y$ không chia hết cho $p_i$;

c) Tương tự, chỉ một trong các biểu thức này có thể chia hết cho $p_{i+1}$, chỉ một trong số chúng có thể chia hết cho $p_{i+2}$, v.v., chỉ một trong số chúng có thể chia hết cho $p_n$.

⟦folio 9⟧

---
running_head:
folio:
---

Chúng ta đi đến kết luận quan trọng đầu tiên: nếu số lượng các số $p_i, p_{i+1}, \dots, p_n$ nhỏ hơn số lượng biểu thức $M_1, \dots, M_p$, tức là, nói cách khác, nếu
$$n-i+1<p_i,$$
(2)

thì trong số các biểu thức $M$ có ít nhất một biểu thức không áp dụng cho bất kỳ số nào $p_i, p_{i+1}, \dots, p_n$, vì mỗi số nguyên tố $p_i, p_{i+1}, \dots, p_n$ được bao gồm trong tập hợp, nhiều nhất, chỉ có trong một trong các biểu thức $M_i, \dots, M_p$.

Theo câu a), biểu thức này cũng không thể bao gồm tập hợp bất kỳ số nào $p_1, \dots, p_{i-1}$ và chúng ta đi đến kết luận rằng nó không chia hết cho bất kỳ số nguyên tố nào. Gọi đây là biểu thức $M_k$. Bây giờ bằng chứng về tính chính xác cần được chú ý đến phương pháp luận. Biểu thức $M_k$ bản thân nó phải là số nguyên tố, trong trường hợp đó nó nhất thiết phải lớn hơn $p_n$ hoặc được phân tách thành nhiều thừa số nguyên tố, tuy nhiên, trong đó không có một thừa số nào trong chuỗi $p_i, \dots, p_n$ có thể xảy ra và do đó, tất cả đều phải lớn hơn $p_n$. Nhưng dù vậy, phải có một số nguyên tố nào đó lớn hơn $p_n$, nằm trong tập hợp $M_k$ hoặc bằng nó, và do đó không lớn hơn $M_k$. Vì trong số tất cả các biểu thức $M$ nhiều nhất là $M_p$, rõ ràng là số của chúng tôi trong mọi trường hợp không vượt quá $M_p$. Đồng thời, chúng tôi không khẳng định rằng số được xác định theo cách này chính xác là số gần đúng theo sau $p_n$, tức là $p_{n+1}$. Nhưng ngay cả khi điều này không xảy ra, thì trong mọi trường hợp, nó thậm chí còn lớn hơn $p_{n+1}$, và do đó, $p_{n+1}$ đặc biệt không thể vượt quá $M_p$:

$$p_{n+1} \leq p_1 \dots p_{i-1} p_i - 1 < p_1 \dots p_i.$$

Do đó, kết quả sơ bộ của việc nghiên cứu tính chất là như sau: nếu sự tương ứng (2) đúng thì bất đẳng thức đúng:

$$p_{n+1} < p_1 \dots p_i.$$

(3)

Làm rõ việc đánh giá

Rõ ràng là chúng ta đã đạt được sự thành công của chứng minh của Euclid:

$$p_{n+1} < p_1 \dots p_n,$$

Vì $i$ nhỏ hơn $n$ nên vế phải của bất đẳng thức (3) giảm so với bất đẳng thức Euclid. Câu hỏi duy nhất là mức giảm này lớn đến mức nào. Thật vậy, điều kiện (2) không cho phép chúng ta có các giá trị nhỏ tùy ý cho $i$; $i$ phải lớn đến mức số lượng các số $p_i, \dots, p_n$, bằng $n-i+1$, nhỏ hơn $p_i$, tức là số đầu tiên trong số chúng. Chúng ta hãy thử tìm hiểu ý nghĩa của điều kiện này bằng một ví dụ đơn giản.

Đặt $n=5$: điều này có nghĩa là chúng ta sẽ chỉ xử lý 5 số nguyên tố đầu tiên 2, 3, 5, 7, 11. Hãy chọn $i$ giá trị 2, sau đó là $p_i=3$ và nhóm số $p_i, \dots, p_n$ sẽ bao gồm các số 3, 5, 7, 11 và số $n-i+1=5-2+1=4$ của chúng sẽ lớn hơn $p_i=3$, tức là cái đầu tiên trong số đó. Do đó, hóa ra là chúng tôi đã chọn giá trị quá thấp cho $i$. Chúng ta hãy lấy $i$ một giá trị lớn hơn 1: $i=3$, sau đó $p_i=5$ và các số $p_i, \dots, p_n$ chúng ta sẽ chỉ có 3, cụ thể là 5, 7, 11 và số 3 này thực sự nhỏ hơn số đầu tiên trong ba số này, cụ thể là 5. Thực tế là bất kỳ giá trị nào lớn hơn $i$ đặc biệt phải thỏa mãn các yêu cầu (2) không cần bất kỳ giá trị nào những lời giải thích.

Vị trí mà bây giờ chúng tôi muốn chứng minh được xây dựng như sau: nếu chúng tôi chọn $i$ giá trị nhỏ nhất có thể thỏa mãn điều kiện (2), thì sự tương ứng sẽ diễn ra:

$$p_1 \dots p_i < p_{i+1} \dots p_n.$$

(4)

Hoàn thành việc chứng minh

Bất đẳng thức (4) đúng với $n=5$, bởi vì, như có thể thấy từ phép tính trực tiếp, $2 \cdot 3 \cdot 5 < 7 \cdot 11$. Để tìm hiểu xem nó có còn đúng trong tương lai hay không, chúng ta cần hình dung rõ ràng như thế nào.

⟦folio 10⟧

---
running_head:
folio:
---

$i$ tốt nhất được chọn với kết quả trả về $n$.

Nếu chúng ta chuyển từ $n=5$ sang $n=6$, tức là chúng ta xem xét 6 số nguyên tố đầu tiên, thì rõ ràng là đối với $p_i$, chúng ta có thể giữ lại giá trị trước đó là 5. Thật vậy, $n-i+1$ nhỏ hơn 5 x 2 đơn vị. Nếu bây giờ chúng ta thêm số 13 vào các số của nhóm, các giá trị $n-i+1$ sẽ trở về 4, nhưng vẫn nhỏ hơn $p_i=5$. Chỉ khi chúng ta chuyển sang $n=7$ và nhóm của chúng ta có 5 số (số 17 được thêm vào) thì con số này mới không nhỏ hơn $p_i=5$. Do đó, ở đây, giá trị của $i$ phải được tăng thêm 1 và sau đó là $p_i=7$. Trong trường hợp này, nhóm có thể bao gồm tối đa 6 số, tức là các số $7 \cdot 11 \cdot 13 \cdot 17 \cdot 19 \cdot 23$. Do đó, việc lựa chọn $p_i=7$ là đủ cho ba bước tiếp theo gần nhất, tức là đối với $k=7, 8, 9$; Tiếp theo, chúng ta phải lấy $p_i=11$ và vì lần này số nguyên tố đóng sau 7 lớn hơn nó không phải 2 mà là 4 đơn vị, lựa chọn này sẽ đủ không phải cho 3 bước tiếp theo gần nhất mà là cho 5. Tốt nhất nên hiểu những sự tương ứng này từ bảng bên dưới, trong đó $p_i$ được in đậm:

$$n=5: 2, 3, 5, 7, 11$$
$$n=6: 2, 3, 5, 7, 11, 13$$
$$n=7: 2, 3, 5, 7, 11, 13, 17$$
$$n=8: 2, 3, 5, 7, 11, 13, 17, 19$$
$$n=9: 2, 3, 5, 7, 11, 13, 17, 19, 23$$
$$n=10: 2, 3, 5, 7, 11, 13, 17, 19, 23, 29$$
$$n=11: 2, 3, 5, 7, 11, 13, 17, 19, 23, 29$$
$$n=12: 2, 3, 5, 7, 11, 13, 17, 19, 23, 29$$
$$n=13: 2, 3, 5, 7, 11, 13, 17, 19, 23, 29$$
$$n=14: 2, 3, 5, 7, 11, 13, 17, 19, 23, 29$$
$$n=15: 2, 3, 5, 7, 11, 13, 17, 19, 23, 29$$
$$n=16: 2, 3, 5, 7, 11, 13, 17, 19, 23, 29$$

Để tìm hiểu xem sự lựa chọn tốt nhất $i$ xảy ra như thế nào với kết quả trả về $n$, bây giờ chúng ta hãy kiểm tra tính công bằng

sự thật của quan điểm nêu trên (4). Điều đó vẫn đúng với $n=6$ là điều không thể nghi ngờ, hoặc nếu

$$2 \cdot 3 \cdot 5 < 7 \cdot 11,$$
(5)

sau đó và

$$2 \cdot 3 \cdot 5 < 7 \cdot 11 \cdot 13,$$
(6)

vì khi chuyển từ $n=5$ sang $n=6$ $i$ vẫn giữ nguyên.

Khi chuyển từ $n=6$ sang $n=7$ tình hình sẽ thay đổi. Bộ 7 xuất hiện ở bên trái và 17 xuất hiện ở bên phải. Cần phải kiểm tra xem bất đẳng thức có đúng hay không

$$2 \cdot 3 \cdot 5 \cdot 7 < 11 \cdot 13 \cdot 17.$$

Chúng ta không thể giải quyết vấn đề này một cách trực tiếp dựa trên bất đẳng thức (6) mà không tính toán. Tuy nhiên, bất đẳng thức (6) vẫn đúng nếu ta cộng hệ số 7 vào bên trái và 17 vào bên phải; sau đó chúng ta nhận được sự bất bình đẳng

$$2 \cdot 3 \cdot 5 \cdot 7 < 11 \cdot 13 \cdot 17,$$

trong đó bên phải có thừa số không mong muốn là 7. Nếu chúng ta sử dụng cơ sở không phải (6) mà là (5), thì có thể rút ra bất đẳng thức (7) từ nó mà không cần bất kỳ phép tính nào. Để làm điều này, chúng tôi giới thiệu tập 7·7 ở vế trái của bất đẳng thức (5) và 13·17 ở vế phải; thì ta được 2·3·5·7·7 < 7·11·13·17. Giảm đi 7, ta tìm được bất đẳng thức loại trừ (7).

Những lập luận này liên quan đến việc chuyển đổi từ $n=6$ sang $n=7$, nhưng vì ở tất cả các giai đoạn chứng minh của chúng tôi, chúng tôi đã thực hiện mà không có bất kỳ thao tác tính toán nào, nên rõ ràng là bằng chứng này cũng phù hợp như nhau cho bất kỳ chuyển đổi nào tiếp theo. Nó dựa trên một thực tế đơn giản là trong quá trình trả về $n$, số $i$, như được thấy rõ từ bảng của chúng tôi, không tăng hai lần liên tiếp trong hai lần chuyển đổi liền kề - mỗi lần xảy ra một "cầu nối", thực tế không chỉ bao gồm hai mà còn bao gồm ba (và một số nữa) chuyển đổi. Sự tương ứng tương tự như (7) cũng đúng với mọi $i$.
