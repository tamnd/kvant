---
id: 1991-4-kurlyandchik-faybusovich-istoriya-odnogo-neravenstva-d3ac5ec7
issue: kvant_1991_4
year: 1991
number: "4"
title: Câu chuyện về một sự bất bình đẳng
authors:
  - Курляндчик Л. Д.
  - Файбусович А.
rubric: osnovnye-stati
page_first: 16
page_last: 20
page_labels: 14-18
lang: vi
source: kvant_digital
extraction: vision
content_sha256: 046fb3d94042d2df048c132046fddf85543b1def9978a9511248411750c470f9
prompt_sha256: draft-1
translated_from: content/ru/1991/04/articles/06_kurlyandchik-faybusovich-istoriya-odnogo-neravenstva-d3ac5ec7.md
source_content_sha256: 91483fcc90a0097db1297611af9ead109a0b438142ab5a35a3a8e8499e8c3d6b
translation_model: draft
translation_run: vi-draft-gaps-2026-11-06
translation_quality: draft
---

⟦folio 14⟧

---
running_head:
folio:
---

Chúng ta sẽ nói về sự bất bình đẳng
$$\frac{x_1}{x_2+x_3} + \frac{x_2}{x_3+x_4} + \dots + \frac{x_{n-1}}{x_n+x_1} + \frac{x_n}{x_1+x_2} \geq \frac{n}{2}),$$
được đề xuất lần đầu tiên bởi nhà toán học người Mỹ Shapiro trên các trang của tạp chí The American Mathematical Monthly vào năm 1954. bài toán này đã thu hút sự chú ý của nhiều nhà toán học trên thế giới. Một đóng góp rất đáng kể cho lời giải của nó được thực hiện bởi cậu học sinh miền bắc (người đọc «Kvant»!) Volodya Drinfeld, người sau đó đã trở thành người đoạt Huy chương Fields **).
Năm 1958, Giáo sư Mordell của Cambridge đã chứng minh bất đẳng thức này cho $n \leqslant 6$. Đối mặt với những khó khăn cơ bản trong trường hợp $n=7$, ông đã phỏng đoán rằng bất đẳng thức cho $n=7$ là không đúng. Điều tò mò là nếu anh ta chứng minh được giả thuyết của mình, tức là tìm thấy bảy số $x_1, x_2, \dots, x_7$ mà tổng đó nhỏ hơn 7/2, thì ngay lập tức sẽ cho thấy rằng bất đẳng thức không đúng với mọi $n \geqslant 7$. Hãy chứng minh điều đó. Đầu tiên chúng tôi giới thiệu ký hiệu
$$f_n(x_1, x_2, \dots, x_n) = \frac{x_1}{x_2+x_3} + \dots + \frac{x_n}{x_1+x_2},$$
điều này sẽ giúp chúng ta tiết kiệm rất nhiều không gian. Sau đó chúng tôi lưu ý rằng
$$f_n(x_k, x_{k+1}, \dots, x_n, x_1, x_2, \dots, x_{k-1}) = f_n(x_1, x_2, \dots, x_n),$$
nghĩa là, vế trái của bất đẳng thức không thay đổi nếu các số ở vế trái của nó được sắp xếp lại theo chu trình. Vì vậy, sự bất bình đẳng này và những điều khác,
*) Tất cả các biến trong bài viết này đều không âm và mẫu số là dương.
**) «Kvant» nói về Giải thưởng Fields và những người đoạt giải ở vị trí thứ 6 năm 1990.

sở hữu tính chất này được gọi là tuần hoàn.
Kiểm tra xem
$$f_{n+2}(x_1, x_2, \dots, x_n, x_1, x_2) = f_n(x_1, x_2, \dots, x_n) + 1.$$
Theo sau đó nếu
$$f_n(x_1, x_2, \dots, x_n) < \frac{1}{2} n,$$
Cái đó
$$f_{n+2}(x_1, x_2, \dots, x_n, x_1, x_2) < \frac{1}{2} (n+2).$$
Bây giờ hãy kiểm tra xem
$$f_{n+1}(x_1, \dots, x_i, x_i, \dots, x_n) - f_n(x_1, x_2, \dots, x_n) - \frac{1}{2} = \frac{(x_i - x_{i-1})(x_i - x_{i+1})}{2x_i(x_i + x_{i+1})},$$
trong trường hợp này, cần giả sử rằng $x_{n+1} = x_1$ và $x_{n+2} = x_2$. Theo sau đó nếu
$$(x_i - x_{i-1})(x_i - x_{i+1}) \leqslant 0,$$
Cái đó
$$f_{n+1}(x_1, \dots, x_i, x_i, \dots, x_n) < \frac{1}{2} (n+1)$$
tại $f_n(x_1, x_2, \dots, x_n) < \frac{1}{2} n$.

Nhưng trong trường hợp $n$ lẻ, cần phải tìm $i$ mà $(x_i - x_{i-1})(x_i - x_{i+1}) \leqslant 0$, bởi vì nếu với tất cả $i$ thì bất đẳng thức $(x_i - x_{i-1})(x_i - x_{i+1}) > 0$ được thỏa mãn thì biến của các bất đẳng thức này, chúng ta sẽ nhận được $(x_1 - x_2)^2(x_2 - x_3)^2 \dots (x_n - x_1)^2 < 0$. Vì 7 là số lẻ nên bất đẳng thức sẽ không đúng với $n=8$ và tất cả $n$ chẵn, và cách suy luận trước đó sẽ đảm bảo kết quả này cho số lẻ $n$.

Tuy nhiên, vào năm 1961, Djekovic, một nhà toán học đến từ Belgrade, đã bác bỏ giả định này.

⟦folio 15⟧

---
running_head:
folio:
---

Vị trí Mordell, chứng minh bất đẳng thức cho $n=8$. Và vào năm 1967, nhà toán học người Brazil Novosad đã công bố một bằng chứng cho $n=10$. Năm 1974, các nhà toán học Liên Xô V. I. Levin và E. K. Godunova đã chứng minh được bất đẳng thức cho $n=12$.

Trong những năm đó, không có nhà toán học nào cố gắng chứng minh bất đẳng thức ở dạng tổng quát. Ngay từ năm 1956, nhà toán học người Anh Lighthill đã chứng minh rằng, nói chung, bất đẳng thức là không đúng. Anh ấy đã xây dựng được một bộ gồm 20 số $x_1, \dots, x_{20}$ sao cho $f_{20}(x_1, \dots, x_{20}) < 10$. Và sau một thời gian, anh và, độc lập với anh, nhà toán học người Scotland Zlauuf đã tìm được các ví dụ tương ứng cho $n=14$. Đây là một trong số đó: 50, 5, 48, 3, 48, 1, 50, 0, 52, 1, 54, 4, 53, 6.

Trong trường hợp $n$ lẻ thì mọi việc phức tạp hơn nhiều. Năm 1958, Rankin, một nhà toán học đến từ Glasgow, đã chứng minh rằng bất đẳng thức không đúng với số lẻ $n$ đủ lớn.

Năm 1959, Zulauf, người đã được chúng ta nhắc đến, đã chứng minh rằng bất đẳng thức không đúng với số lẻ $n \geqslant 53$. Năm 1961, Dianaanda, một nhà khoa học đến từ Singapore, đã đưa ra biện pháp đối phó với $n=27$. Một ví dụ bác bỏ cho $n=25$ được nhà toán học người Anh Deikin xây dựng vào năm 1971.

Hai học sinh trường nội trú toán tại Đại học Leningrad (sinh viên của một trong các tác giả), R. Alekseev và E. Foshkin, sử dụng máy tính, đã độc lập xây dựng được biện pháp đối phó với $n=25$:
32, 0, 37, 0, 43, 0, 50, 0, 59, 8, 62, 21, 55, 29, 44, 32, 33, 31, 24, 30, 16, 29, 10, 29, 4.

Gần đây hơn, vào tháng 10 năm 1989, nhà toán học người Mỹ Trosch đã công bố một bằng chứng về bất đẳng thức cho tất cả các $n$ khác, cụ thể là cho 13, 15, 17, 19, 21 và 23. Tuy nhiên, đối với điều này, ông chỉ cần chứng minh bất đẳng thức cho $n=23$ là đủ.

Kể từ năm 1956, khi người ta xác định rằng bất đẳng thức $f_n \geqslant \frac{n}{2}$ là sai, nó đã được nghiên cứu theo hai hướng. Điều đầu tiên là tìm ra $n$ bất đẳng thức nào đúng. Chúng tôi đã báo cáo về tình trạng của vấn đề này. Bây giờ chúng ta sẽ chuyển sang nói về một hướng nghiên cứu khác.

Năm 1957, Rankin đã chứng minh rằng bất đẳng thức $f_n \geqslant \frac{2\sqrt{2}-1}{6} n = \frac{n}{2} \cdot 0,609$ là đúng. Năm 1961, ông đã cải thiện một chút kết quả của mình: $f_n \geqslant \frac{n}{2} \cdot 0,661$. Cùng năm đó, Diana đã có thể chứng minh rằng $f_n \geqslant \frac{2\sqrt{2}-1}{2} \cdot \frac{n}{2} = \frac{n}{2} \cdot 0,914$. Năm 1962 ông đã chứng minh được rằng $f_n \geqslant \frac{n}{2} \times 0,922$. tức là, anh ấy đã chèn câu hỏi số lớn nhất $\gamma$ là bao nhiêu mà bất đẳng thức $f_n \geqslant \gamma \cdot \frac{n}{2}$ đúng với mọi tự nhiên $n$. Chính bài toán này mà Volodya Drinfeld đã giải được.

Mọi chuyện bắt đầu với thực tế là vào năm 1969, tại Cuộc tối ưu hóa toán học toàn liên minh lần thứ ba, người ta đã đề xuất chứng minh bất đẳng thức $\frac{x_1}{x_2+x_3} + \dots + \frac{x_n}{x_1+x_2} > \frac{n}{4}$. Trong số tất cả những người tham gia, một sinh viên đã có thể giải được nó - một sinh viên trường nội trú toán học tại Đại học Leningrad, A. Berzinsh, người ba lần đoạt giải Tối ưu hóa toàn Liên minh.

Lời giải đây rồi. Đặt $x_{i_1}$ là số lớn nhất trong số $x_1, x_2, \dots, x_n$; $x_{i_2}$ — số lớn hơn trong hai số theo sau $x_{i_1}$; $x_{i_3}$ là số lớn hơn trong hai số theo sau $x_{i_2}$, v.v. Đặt $k$ sao cho số lớn nhất của hai số theo sau $x_{i_k}$ là $x_{i_1}$. Rõ ràng là $k \geqslant \frac{n}{2}$, và do đó
$\frac{x_1}{x_2+x_3} + \dots + \frac{x_n}{x_1+x_2} > \frac{x_{i_1}}{2x_{i_2}} +$
$\frac{x_{i_2}}{2x_{i_3}} + \dots + \frac{x_{i_k}}{2x_{i_1}} \geqslant \frac{k}{2} \geqslant \frac{n}{4}$.

Tổng cuối cùng không nhỏ hơn $\frac{k}{2}$ suy ra từ bất đẳng thức Cauchy $a_1+a_2+\dots+a_k \geqslant k^k \sqrt{a_1a_2 \dots a_k}$.

⟦folio 16⟧

---
running_head:
folio:
---

Một trong những người chiến thắng trong việc tối ưu hóa này là cậu học sinh Voloda Drinfeld ở Kharkov. Là thành viên của đội Liên Xô, anh đã tham gia Cuộc thi Tối ưu hóa Toán học Quốc tế. Người lãnh đạo khoa học của nhóm là một trong những chuyên gia lớn nhất của Liên Xô về các naravavent, Giáo sư V.I. Levin. Ông nói với các bạn về sự bất bình đẳng theo chu kỳ, và cũng trong năm 1969, Volod đã tìm được giá trị mong muốn $\gamma$. Không sao đâu $\gamma=0,989$...

Trước khi kể ra ý tưởng của V. Drinfeld, chúng tôi sẽ chỉ ra cách thu được kết quả yếu hơn được xây dựng trong bài toán M1250. Chúng ta hãy nhớ lại các điều kiện của bài toán này.

M1250. Chứng minh rằng nếu $x_1, x_2, \dots, x_n$ là số dương thì $\frac{x_1}{x_2+x_3} + \frac{x_2}{x_3+x_4} + \dots + \frac{x_n}{x_1+x_2}$ lớn hơn $a$ ($\sqrt{2}-1)n$; b) $\frac{5}{12}n$; c) nếu các số $x_1, x_2, \dots, x_n$ tạo thành một dãy đơn điệu thì tổng này không nhỏ hơn $\frac{n}{2}$.

Lời giải
a) Mỗi ​​vấn đề
$\frac{x_i}{x_{i+1}+x_{i+2}} (i=1, 2, \dots, n)$ sẽ được thể hiện dưới dạng
$\frac{x_i+\frac{1}{2}x_{i+1}}{x_{i+1}+x_{i+2}} + \frac{\frac{1}{2}x_{i+1}+x_{i+2}}{x_{i+1}+x_{i+2}} -1$.

Chúng ta sẽ gặp $2n$ bài toán và nhóm chúng theo tham số - phân số đầu tiên có thứ $2n$; thứ hai với thứ ba; thứ tư với thứ năm, v.v. Hãy ước tính ngay tổng các số tạo thành một cặp:
$\frac{1}{2}x_i+x_{i+1} + \frac{x_i+\frac{1}{2}x_{i+1}}{x_{i+1}+x_{i+2}} \geq$
$\geq 2\sqrt{\frac{\left(\frac{1}{2}x_i+x_{i+1}\right)\left(x_i+\frac{1}{2}x_{i+1}\right)}{(x_i+x_{i+1})(x_{i+1}+x_{i+2})}}$
$= 2\sqrt{\left(\frac{1}{2}+\frac{x_i+x_{i+1}}{4(x_i+x_{i+1})^2}\right)\frac{x_i+x_{i+1}}{x_{i+1}+x_{i+2}}}$
$> \sqrt{2} \cdot \sqrt{\frac{x_i+x_{i+1}}{x_{i+1}+x_{i+2}}}$.

Vì tích của $n$ số
$\sqrt{\frac{x_1+x_2}{x_2+x_3}}, \sqrt{\frac{x_2+x_3}{x_3+x_4}} \dots, \sqrt{\frac{x_n+x_1}{x_1+x_2}}$ bằng 1, thì từ bất đẳng thức Cauchy suy ra rằng tổng của chúng không nhỏ hơn $n$. Do đó tổng ban đầu lớn hơn $\sqrt{2n}-n=(\sqrt{2}-1)n$.

6) Khi chứng minh điểm a) chúng ta đã thêm một vào mỗi phân số. Nhưng tại sao bạn cần thêm chính xác một? Hãy thêm một số tùy ý $\alpha$ và chọn $\beta$ sao cho đẳng thức giữ nguyên
$\frac{x_i}{x_{i+1}+x_{i+2}} + \alpha = \frac{x_i+\beta x_{i+1}}{x_{i+1}+x_{i+2}} +$
$+\frac{\alpha(\beta x_{i+1}+x_{i+2})}{x_{i+1}+x_{i+2}}$.

Rõ ràng là $\beta+\alpha\beta=\alpha$, tức là $\beta=\frac{\alpha}{\alpha+1}$. Kể từ đây,
$\frac{x_i+\beta x_{i+1}}{x_{i+1}+x_{i+2}} + \frac{\alpha(\beta x_{i+1}+x_{i+1})}{x_{i+1}+x_{i+2}} \geq$
$\geq 2\sqrt{\alpha \frac{\left(x_i+\beta x_{i+1}\right)\left(\beta x_{i+1}+x_{i+1}\right)}{(x_i+x_{i+1})(x_{i+1}+x_{i+2})}}$
$= 2\sqrt{\alpha \frac{\beta(x_i+x_{i+1})^2+(\beta-1)^2x_i x_{i+1}}{(x_i+x_{i+1})(x_{i+1}+x_{i+2})}}$
$> 2\sqrt{\alpha \beta \frac{x_i+x_{i+1}}{x_{i+1}+x_{i+2}}} = \frac{2\alpha}{\sqrt{\alpha+1}} \sqrt{\frac{x_i+x_{i+1}}{x_{i+1}+x_{i+2}}}$.

Có nghĩa,
$\frac{x_1}{x_2+x_3} + \frac{x_2}{x_3+x_4} + \dots + \frac{x_n}{x_1+x_2} >$
$> \frac{2\alpha}{\sqrt{\alpha+1}} \left(\sqrt{\frac{x_1+x_2}{x_2+x_3}} + \sqrt{\frac{x_2+x_3}{x_3+x_4}} + \dots \right.$
$... + \sqrt{\frac{x_n+x_1}{x_1+x_2}}) - \alpha n >$
$> \frac{2\alpha}{\sqrt{\alpha+1}} n - \alpha n = \left(\frac{2\alpha}{\sqrt{\alpha+1}} - \alpha\right) \cdot n$.

Nếu ta đặt $\alpha=\frac{5}{4}$ thì $\frac{2\alpha}{\sqrt{\alpha+1}} - \alpha=\frac{5}{12}=0,416$... và khẳng định ở điểm 6) được chứng minh. Hãy nhớ lại phần a) có được bằng cách đặt $\alpha=1$.

⟦folio 17⟧

---
running_head:
folio:
---

Xét trường hợp $x_1 \geqslant x_2 \geqslant \dots \geqslant x_n$. Hãy để chúng tôi chỉ ra rằng ở đây có một sự tương ứng
$$f_n(x_1, x_2, \dots, x_n) \geqslant$$
$$\geqslant f_{n-1}(x_1, x_2, \dots, x_{n-1}) + \frac{1}{2}.$$
Thật vậy, điều tương tự cũng xảy ra:
$$f_n(x_1, x_2, \dots, x_n) - f_{n-1}(x_1, x_2, \dots, x_{n-1}) =$$
$$= \frac{(x_{n-2} - x_{n-1})(x_1 - x_n)}{(x_{n-1} + x_n)(x_1 + x_{n-1})} +$$
$$+ \frac{(x_1 - x_n)(x_{n-1} - x_n)(x_1 - x_{n-1})}{2(x_{n-1} + x_n)(x_1 + x_{n-1})} +$$
$$+ \frac{(x_{n-1} - x_n)(x_2 - x_n)}{(x_1 + x_2)(x_1 + x_n)} + \frac{1}{2}.$$
Nhưng tất cả các số hạng đều không âm (do tính đơn điệu của dãy $x_1, x_2, \dots, x_n$). Vì thế,
$$f_n(x_1, x_2, \dots, x_n) \geqslant f_{n-1}(x_1, x_2, \dots, x_{n-1}) +$$
$$+ \frac{1}{2} \geqslant f_{n-2}(x_1, x_2, \dots, x_{n-2}) + 1 \geqslant \dots$$
$$\geqslant f_2(x_1, x_2) + \frac{n-2}{2} =$$
$$= \frac{x_1}{x_1 + x_2} + \frac{x_2}{x_2 + x_1} + \frac{n-2}{2} = \frac{n}{2}.$$
Bây giờ hãy xem xét trường hợp $x_1 \leqslant x_2 \leqslant \dots \leqslant x_n$. Lưu ý rằng
$$f_n(x_1, x_2, \dots, x_n) = \frac{x_1 + x_2}{x_2 + x_3} + \dots + \frac{x_n + x_1}{x_1 + x_2} -$$
$$- n + \frac{x_2}{x_1 + x_2} + \frac{x_3}{x_2 + x_3} + \dots + \frac{x_n}{x_n + x_1}.$$
Nhưng tổng thứ nhất không nhỏ hơn $n$, vì tích của tất cả các số hạng bằng 1. Do đó, chỉ cần chứng minh rằng
$$g_n(x_1, x_2, \dots, x_n) = \frac{x_2}{x_1 + x_2} +$$
$$+ \frac{x_3}{x_2 + x_3} + \dots + \frac{x_n}{x_{n-1} + x_n} + \frac{x_1}{x_n + x_1} \geqslant \frac{n}{2}.$$
Để làm điều này, chúng tôi sẽ chỉ ra rằng
$$g_n(x_1, x_2, \dots, x_n) - g_{n-1}(x_1, x_2, \dots, x_{n-1}) -$$
$$- \frac{1}{2} = \frac{x_n}{x_{n-1} + x_n} + \frac{x_1}{x_n + x_1} - \frac{x_1}{x_{n-1} + x_1} -$$
$$- \frac{1}{2} = \frac{(x_{n-1} - x_1)(x_n - x_{n-1})(x_n - x_1)}{2(x_{n-1} + x_n)(x_n + x_1)(x_1 + x_{n-1})} \geqslant 0.$$
Vì thế,
$$g_n(x_1, x_2, \dots, x_n) \geqslant$$
$$\geqslant g_{n-1}(x_1, x_2, \dots, x_{n-1}) + \frac{1}{2} \geqslant$$
$$\geqslant g_{n-2}(x_1, x_2, \dots, x_{n-2}) + 1 \geqslant \dots$$
$$\dots \geqslant g_2(x_1, x_2) + \frac{n-2}{2} =$$
$$= \frac{x_2}{x_1 + x_2} + \frac{x_1}{x_2 + x_1} + \frac{n-2}{2} = \frac{n}{2}$$
Bây giờ chúng tôi sẽ trình bày chứng minh của V. Drinfeld về kết quả của ông. Nó dựa trên hai bất đẳng thức đáng chú ý.
Phần đầu tiên bao gồm hai bộ số dương $n$ $a_1, a_2, \dots, a_n$ và $b_1, b_2, \dots, b_n$. Hãy xem xét biểu thức $a_1b_1 + a_2b_2 + \dots + a_nb_n$. Khẳng định là biểu thức này nhận giá trị tối đa nếu các số được đánh số sao cho $a_1 \geqslant a_2 \geqslant \dots \geqslant a_n$ và $b_1 \geqslant b_2 \geqslant \dots \geqslant b_n$, và giá trị tối thiểu nếu
$$a_1 \geqslant a_2 \geqslant \dots \geqslant a_n, a b_1 \leqslant b_2 \leqslant \dots \leqslant b_n.$$
Bất đẳng thức thứ hai, gọi là bất đẳng thức Jensen, liên quan đến hàm lồi. Hàm $\varphi(x)$ được cho là lồi trên đoạn $[a; b]$ nếu các giá trị của nó trên bất kỳ đoạn $[x_1; x_2]$ nào của $[a; b]$ nằm thấp hơn trên đồ thị so với đoạn nối các điểm $(x_1; \varphi(x_1))$ và $(x_2; \varphi(x_2))$ (hình 1). Định nghĩa này có thể được viết dưới dạng bất đẳng thức
$$\varphi(\alpha x_1 + (1 - \alpha)x_2) \leqslant \alpha \varphi(x_1) + (1 - \alpha) \varphi(x_2).$$

⟦folio 18⟧

---
running_head:
folio:
---

Bất đẳng thức Jensen phát biểu rằng đối với bất kỳ hàm $\varphi(x)$ nào lồi trên khoảng $[a; b]$, một tập hợp các điểm tùy ý $x_1, x_2, \ldots, x_n$ từ khoảng này, cũng như một tập hợp các số dương tùy ý $p_1, p_2, \ldots, p_n$, tổng của chúng bằng $1 (p_1 + p_2 + \ldots + p_n = 1)$, thì mối quan hệ đúng

$$\varphi(p_1 x_1 + \ldots + p_n x_n) \leqslant \leqslant p_1 \varphi(x_1) + \ldots + p_n \varphi(x_n).$$

Hãy tiến hành trình bày bằng chứng. Hãy để chúng tôi biểu thị $\frac{x_{i+1}}{x_i} = k_i$ và $\frac{x_1}{x_n} = k_n$. Chúng ta hãy sắp xếp các số kết quả $k_i$ theo thứ tự tăng dần và biểu thị các số nguyên của dãy kết quả bằng $m_j$. Bây giờ hãy xem xét hai chuỗi:

$$\frac{1}{m_1}, \frac{1}{m_2}, \ldots, \frac{1}{m_n} \text{ и} \frac{1}{1 + m_n}, \frac{1}{1 + m_{n-1}}, \ldots, \frac{1}{1 + m_2}, \frac{1}{1 + m_1}.$$

Một cái giết chết một cách đơn điệu, và cái thứ hai tăng lên một cách đơn điệu. Sử dụng bất đẳng thức đầu tiên, chúng ta có được điều đó

$$\frac{x_1}{x_2 + x_3} + \frac{x_2}{x_3 + x_4} + \ldots + \frac{x_n}{x_1 + x_2} = \frac{1}{k_1(k_2 + 1)} + \frac{1}{k_2(k_3 + 1)} + \ldots + \frac{1}{k_n(k_1 + 1)} \geqslant \frac{1}{m_1(m_n + 1)} + \frac{1}{m_2(m_{n-1} + 1)} + \ldots + \frac{1}{m_n(m_1 + 1)}.$$

(*)

Chúng tôi biểu thị $m_i \cdot m_{n-i+1} = c_i$ và

$$r_i = \frac{1}{m_i(m_{n-i+1} + 1)} + \frac{1}{m_{n-i+1}(m_i + 1)},$$

Sau đó

$$r_i = \frac{1}{c_i} \left(1 + \frac{c_i - 1}{(1 + m_i)(1 + m_{n-i+1})}\right).$$

Vì $(1 + m_i)(1 + m_{n-i+1}) \geqslant (1 + \sqrt{c_i})^2$ thì

$$r_i \geqslant \left\{ \begin{array}{l l} \frac{1}{c_i}, & c_i \geqslant 1, \\ \frac{2}{c_i + \sqrt{c_i}}, & c_i < 1. \end{array} \right.$$

Hãy đặt $c_i = e^{y_i}$. Từ bất đẳng thức (*) và (**) ta có

$$\frac{2}{n} \sum_{i=1}^{n} \frac{x_i}{x_{i+1} + x_{i+2}} \geqslant \geqslant \frac{1}{n} \left( \sum_{c_i \geqslant 1} e^{-y_i} + \sum_{c_i < 1} 2\left(e^{\frac{x}{2}} + e^{y_i}\right)^{-1} \right).$$

Cho $g$ là hàm lồi nhất không vượt quá các hàm của $y = e^{-x}$ và $y = 2\left(e^{\frac{x}{2}} + e^{x}\right)^{-1}$. Khi đó từ bất đẳng thức (***), do bất đẳng thức Jensen, ta có

$$\frac{2}{n} \sum_{i=1}^{n} \frac{x_i}{x_{i+1} + x_{i+2}} \geqslant \geqslant \frac{1}{n} \sum_{i=1}^{n} g(y_i) \geqslant g\left(\frac{y_1 + y_2 + \ldots + y_n}{n}\right) = g(0).$$

Điều này chứng tỏ rằng $\gamma \geqslant g(0)$.

Hơn nữa, với những lời giải thích khá tao nhã, người ta đã chứng minh rằng $g(0) = \gamma$.

Để tiếp tuyến chung nối các điểm $(x_1; e^{-x_1})$ và $(x_2; 2\left(e^{\frac{x}{2}} + e^{x_2}\right)^{-1})$ (hình 2). Đồ thị của hàm $g$ gồm ba phần: $y = e^{-x}$ tại $x \geqslant x_1$, $y = 2\left(e^{x} + e^{\frac{x}{2}}\right)^{-1}$ tại $x \leqslant x_2$ và tiếp tuyến chung của chúng tại $x_2 \leqslant x \leqslant x_1$. Tọa độ giao điểm của tiếp tuyến với trục tọa độ là $\gamma$.
