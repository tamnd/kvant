---
id: 1975-8-vaguten-blizkie-drobi-fbd72065
issue: kvant_1975_8
year: 1975
number: "8"
title: Đóng phân số
authors:
  - Вагутен В. Н.
rubric: osnovnye-stati
page_first: 35
page_last: 41
page_labels: 33-39
tag: 5SIO
lang: vi
source: kvant_digital
extraction: vision
content_sha256: 7ac465974ed262b0b3f360ca0de90600378a30866396c5361273ba6881516ed4
prompt_sha256: draft-1
translated_from: content/ru/1975/08/articles/07_vaguten-blizkie-drobi-fbd72065.md
source_content_sha256: a938a9309f5b5c69437d37941b4bde15e2263a927ce326c44925c1b542fb74e0
translation_model: draft
translation_run: vi-draft-2026-10-31
translation_quality: draft
---

⟦folio 33⟧

Bài viết này nói về một số dãy dobe thú vị và cách giải bài toán M298 từ "Bài toán Kvant. Mặc dù cuối bài yêu cầu làm quen với phương pháp tọa độ, vectơ và nguyên lý quy nạp toán học, hầu hết các lưu ý sẽ dễ hiểu ngay cả với những học sinh mới làm quen với môn này. Tác giả hy vọng rằng học sinh và giáo viên trung học sẽ tìm thấy ở đây những tài liệu thuận tiện cho các lớp học với học sinh lớp 5-6. Các bài tập liên quan đến điều kiện hiện có.

1. Loạt phim Farey. Quan sát

Hãy viết ra tất cả các số dobies thông thường có mẫu số không quá 7:

$$\frac{1}{2}, \frac{1}{3}, \frac{2}{3}, \frac{1}{4}, \frac{3}{4}, \frac{1}{5}, \frac{2}{5}, \frac{3}{5}, \frac{4}{5}, \frac{1}{6},$$

$$\frac{5}{6}, \frac{1}{7}, \frac{2}{7}, \frac{3}{7}, \frac{4}{7}, \frac{5}{7}, \frac{6}{7}$$

(chúng tôi đã bỏ qua các dobies viết tắt: $\frac{2}{4}, \frac{2}{6}, \frac{3}{6}$ và $\frac{4}{6}$ - trong các dobies đại diện cho cùng một số, chúng tôi chọn cùng một dobie, tức là số có tử số và mẫu số nhỏ nhất).

Bây giờ hãy viết những dobies tương tự theo thứ tự tăng dần:

$$\frac{1}{7}, \frac{1}{6}, \frac{1}{5}, \frac{1}{4}, \frac{2}{7}, \frac{1}{3}, \frac{2}{5}, \frac{3}{7}, \frac{1}{2},$$

$$\frac{4}{7}, \frac{3}{5}, \frac{2}{3}, \frac{5}{7}, \frac{3}{4}, \frac{4}{5}, \frac{5}{6}, \frac{6}{7}.$$

(1)

Kiểm tra xem ở hàng (1) mỗi phép cộng có thực lớn hơn phép cộng trước không

$$\frac{1}{6} - \frac{1}{7} = \frac{1}{6.7}, \frac{1}{5} - \frac{1}{6} = \frac{1}{5.6},$$

$$\frac{1}{4} - \frac{1}{5} = \frac{1}{4.5}, \frac{2}{7} - \frac{1}{4} = \frac{1}{4.7}, \dots$$

Trong trường hợp này, một mô hình thú vị được quan sát thấy: số điểm khác biệt giữa hai phép cộng lân cận luôn bằng một, hay chính xác hơn là

A. Đối với hai phép cộng lân cận bất kỳ $\frac{a}{b}, \frac{c}{d}$ ($2\delta e \frac{a}{b} < \frac{c}{d}$) đẳng thức

$$bc - ad = 1.$$

Những mô hình nào khác vốn có trong một số dobes (1)?

Không khó để phát hiện ra tổng của hai dobe đứng đối xứng ở hàng này bằng 1. Không biết bạn đọc có để ý thấy điều đó không?

B. Mỗi nhân đôi được lấy từ hai dobe liền kề theo cách sau: bạn cần cộng các số của chúng và chia số kết quả cho tổng mẫu số.

Trong thực tế,

$$\frac{1}{6} = \frac{1 + 1}{7 + 5}, \frac{1}{5} = \frac{1 + 1}{6 + 4},$$

$$\frac{1}{4} = \frac{1 + 2}{5 + 7}, \frac{2}{7} = \frac{1 + 1}{4 + 3}, \frac{1}{3} = \frac{2 + 2}{7 + 5},$$

$$\frac{2}{5} = \frac{1 + 3}{3 + 7}, \frac{3}{7} = \frac{2 + 1}{5 + 2}, \frac{1}{2} = \frac{3 + 4}{7 + 7}$$

và vân vân!

⟦folio 34⟧

Bảng 1. Chuỗi Farey.

Tương tự như cách viết dòng (1) từ các phân số thích hợp có mẫu số không quá 7, người ta có thể viết, theo thứ tự tăng dần, các phân số có mẫu số không quá $n$. Chúng ta cũng hãy sắp xếp các hàng cho $n=1, 2, \dots, 7$ thành một hàng theo dạng Bảng 1.

Hàng đầu tiên và các bức tường bên của phân số $\frac{0}{1}$ và $\frac{1}{1}$ mang lại cho bảng của chúng ta một cái nhìn hoàn chỉnh hơn.

Bài tập 1. Kiểm tra xem các mẫu A và B mà chúng ta nhận thấy ở hàng tiếp theo của bảng cũng xuất hiện ở tất cả các hàng trước đó.

Chúng tôi đã đánh dấu các phân số mới ở mỗi dòng bằng màu đỏ.

Đối với các phân số mới, quan sát B, bạn có thể làm rõ: đối với một phân số phát sinh giữa hai phân số cũ thì tử số bằng tổng của tử số, mẫu số bằng tổng các mẫu số của chúng. Vì vậy, chúng ta có thể đề xuất một quy tắc đơn giản để thu được hàng thứ $n$ mới.

B. Cần lưu ý ở dòng $(n-1)$ tất cả các cặp phân số dẫn đầu $\frac{a}{b}, \frac{c}{d}$ như vậy, trong đó tổng mẫu số bằng $n$ và giữa chúng có các phân số $\frac{a+c}{b+d}$ (chúng luôn không thể rút gọn).

Hãy thực hiện thao tác này với cặp dòng tiếp theo. Hãy đánh dấu các cặp là màu xám

chúng là những phân số có tổng có mẫu số là 8. Đây là những cặp như vậy

$\frac{0}{1}$ và $\frac{1}{7}$; $\frac{1}{3}$ và $\frac{2}{5}$; $\frac{3}{5}$ và $\frac{2}{3}$; $\frac{6}{7}$ và $\frac{1}{1}$.

Hãy lần lượt chèn các phân số $\frac{1}{8}, \frac{3}{8}, \frac{5}{8}, \frac{7}{8}$ vào giữa chúng và lấy dòng thứ tám

$$\frac{0}{1} \frac{1}{8} \frac{1}{7} \frac{1}{6} \frac{1}{5} \frac{1}{4} \frac{2}{7} \frac{1}{3} \frac{3}{8} \frac{2}{5} \frac{3}{7} \frac{1}{2}$$

$$\frac{4}{7} \frac{3}{5} \frac{5}{8} \frac{2}{3} \frac{5}{7} \frac{3}{4} \frac{4}{5} \frac{5}{6} \frac{6}{7} \frac{7}{8} \frac{1}{1}$$

Bài tập 2. Thực hiện thao tác tương tự với dòng thứ tám và kiểm tra xem bằng cách này bạn có được dòng chứa tất cả các phân số không thể rút gọn có giá trị không quá 9, theo thứ tự tăng dần.

Bài tập 3. Kiểm tra xem mẫu A và B có thỏa mãn ở dòng thứ tám và thứ chín hay không.

Hàng gồm tất cả các phân số không rút gọn $\frac{p}{q}$, trong đó $1 \leq p \leq q \leq n$ ($n$ là một số tự nhiên cho trước), sắp xếp theo thứ tự tăng dần, có một tên đặc biệt trong lý thuyết số - chuỗi Farey, và đôi khi được ký hiệu là $F_n$. Tên của nhà toán học Farey được đặt cho những dòng như vậy bởi nhà toán học vĩ đại người Pháp Cauchy. Farey quan tâm đến tính đều đặn trong chuỗi phân số này, và Cauchy, chú ý đến những quan sát của Farey, đã công bố bằng chứng của họ vào năm 1816. Tuy nhiên, hoàn toàn có khả năng những quy luật này đã được các nhà toán học biết đến trước đó.

Hãy để chúng tôi đưa ra hai định nghĩa liên quan đến những quan sát của chúng tôi.

Định nghĩa 1. Chúng ta gọi hai phân số $\frac{a}{b}, \frac{c}{d}$ là đóng nếu $bc$-ad bằng 1 hoặc -1.

Bài tập 4. Chọn từ các phân số (1) tất cả các cặp phân số gần nhau.

⟦folio 35⟧

Định nghĩa 2. Lấy trung vị của hai phân số $\frac{a}{b}, \frac{c}{d}$ là phân số $\frac{a+c}{b+d}$.

(Trung vị của các phân số tối giản có thể là phân số tối giản; cho ví dụ.)

2. Tính chất của phân số gần

Bây giờ các giả thuyết của chúng ta có thể được xây dựng ngắn gọn như sau: trong bất kỳ chuỗi Farey thứ $n$ nào (hàng thứ $n$ của Bảng 1)

A. Các phân số liền kề gần với một phân số khác.

B. Mỗi phân số mới $m/n$ là trung vị của các phân số lân cận nó.

Trong bài toán M298 từ “Bài toán Kvant, điều cần thiết là phải chứng minh tính chất A: nếu $p/q < r/s$ là các phân số lân cận của chuỗi $F_n$, thì $qr - ps = 1$. Nhưng hóa ra điều quan trọng là có thể dễ dàng chứng minh cả hai tính chất cùng một lúc - cả A và B. Dưới đây chúng tôi phác thảo tối đa ba cách chứng minh khác nhau: một - trong đoạn 3-4, thứ hai - trong đoạn 5, thứ ba - trong đoạn 6. Chúng tôi chỉ ra một số thuộc tính đơn giản đặc trưng cho phân số gần và trung vị.

a) Đối với hai phân số bất kỳ $a/b$ và $c/d$ hiệu modulo của chúng không nhỏ hơn 1/bd:

$$\left| \frac{a}{b} - \frac{c}{d} \right| \geq -\frac{1}{bd},$$

(2)

và dấu đẳng thức trong (2) đạt được khi và chỉ khi các phân số $a/b$ và $c/d$ gần nhau. (Điều này giải thích sự lựa chọn thuật ngữ: phân số đóng.)

6) Trung vị của hai phân số luôn nằm giữa chúng, m. đ.

nếu $\frac{a}{b} < \frac{c}{d}$ thì

$$\frac{a}{b} < \frac{a+c}{b+d} < \frac{c}{d}.$$

b) Nếu hai phân số gần nhau thì cả hai đều tối giản.

r) Nếu hai phân số gần nhau thì trung tuyến của chúng gần nhau.

d) Nếu hai phân số gần nhau thì giá trị của chúng là nguyên tố cùng nhau và các giá trị số của chúng là nguyên tố cùng nhau *).

e*) Trong tất cả các phân số nằm giữa hai phân số gần nhau, trung vị của chúng được gọi là mẫu số.

Bài tập 5. Chứng minh tính chất a) - d).

Bây giờ chúng ta giả sử rằng người đọc không chỉ hoàn thành bài tập 2 - nhận được 2 từ việc sử dụng - mà còn tiếp tục hành động xa hơn theo quy tắc B, nhận được dòng thứ mười, tương tự, v.v.

Từ các thuộc tính 6), B), r) suy ra rằng trong tất cả các dòng mới, các quy luật sau cũng được giữ nguyên:

1) các phân số trung vị mà chúng tôi chèn vào sẽ không thể rút gọn được;
2) phân số theo thứ tự tăng dần;
3) hai phân số liền kề bất kỳ gần nhau.

Câu hỏi khó hơn còn lại là đây. Theo quy tắc B, liệu tất cả các phân số tối giản có giá trị $n$ có được đưa vào hàng thứ $n$ hay có thể một số sẽ bị bỏ sót? Hóa ra tất cả các phân số như vậy nhất thiết phải được chèn vào, tức là chúng ta thực sự sẽ nhận được toàn bộ chuỗi $F_n$. Tại thời điểm này, chúng tôi khuyên người đọc nên rời đi và cố gắng tự mình đưa ra bằng chứng (một trong những cách là chứng minh tính chất e, được đánh dấu hoa thị).

Hiện tại, chúng ta sẽ vắng mặt một thời gian ngắn và thảo luận về câu hỏi:

Có bao nhiêu phân số ở hàng thứ $n$ của bảng?

*) Các số nguyên $a$ và $b$ được gọi là nguyên tố cùng nhau nếu chúng không có ước số chung lớn hơn 1.

⟦folio 36⟧

3. Hàm Euler.
Số phân số màu đỏ

Cho ta có một số tự nhiên $n$. Chúng ta hãy xem xét tất cả các số tự nhiên không vượt quá $n$ và chọn trong số chúng những số nguyên tố cùng nhau với số $n$. Số của các số này sẽ được ký hiệu là $\varphi(n)$.

Ví dụ: đối với $n=8$ các số như vậy sẽ là 1, 3, 5, 7 và do đó $\varphi(8)=4$.

Vì vậy, mỗi số tự nhiên $n$ được liên kết với số $\varphi(n)$. Sự tương ứng $\varphi$ này được gọi là hàm Euler.

Hãy liệt kê một số tính chất của hàm Euler:
1) $\varphi(n) < n$.
2) Nếu $n = p$ là số nguyên tố thì $\varphi(p) = p-1$.
3) Với $n > 2$ số $\varphi(n)$ là số chẵn.
4) Nếu $n = p^d$ là lũy thừa của số nguyên tố $p$ thì

$$\varphi(p^\alpha) = p^\alpha - p^{\alpha-1} = p^\alpha \left(1 - \frac{1}{p}\right).$$

5*) Nếu $m$ và $n$ nguyên tố cùng nhau thì $\varphi(mn) = \varphi(m) \cdot \varphi(n)$.
6) Công thức chung cho $\varphi(n)$ là:

$$\varphi(n) = n \left(1 - \frac{1}{p_1}\right) \left(1 - \frac{1}{p_2}\right) \dots \left(1 - \frac{1}{p_r}\right);$$

ở đây $p_1, p_2, \dots, p_r$ đều là các số nguyên tố chia hết cho $n$. (Công thức này đã được chứng minh trong bài “Định lý nhỏ Fermat”, «Kvant», 1972, số 10.)

Chúng tôi mời người đọc chứng minh tất cả các tính chất này. Chúng tôi chỉ giải thích tính chất 3). Tất cả các số nhỏ hơn $n$ và nguyên tố cùng nhau đến $n$ có thể được chia thành các cặp: mỗi cặp bao gồm các số $q$, $s$ sao cho $q+s=n$. Vậy số $\varphi(n)$ là số chẵn.

Số phân số màu đỏ ở dòng thứ $n$ $F_n$, rất indo, bằng $\varphi(n)$, vì có nhiều phân số tối giản $m/n$ ($0 \leqslant m/n \leqslant 1$) có giá trị $n$ như số tự nhiên $m$, nhỏ hơn $n$ và cùng nguyên tố với $n$.

Câu hỏi về tổng số số hạng mà chuỗi Farey thứ $n$ $F_n$ chứa bao nhiêu đã được độc giả «Kvant» thảo luận trong thư của mình. A. Kitaev từ Leningrad. Rõ ràng là con số này - hãy ký hiệu nó là $\varphi(n)$ - bằng

$$\varphi(n) = 1 + \varphi(1) + \varphi(2) + \varphi(3) + \dots + \varphi(n),$$

kể từ $\varphi(1) = 2$ và $\varphi(n) = \varphi(n-1) + \varphi(n)$ (xem Bảng 2). Dường như không có công thức đơn giản nào cho $\varphi(n)$. Nhưng điều thú vị là, bất chấp hành vi cực kỳ bất thường của hàm Euler $\varphi(n)$ (so với

$$n \quad 1 \quad 2 \quad 3 \quad 4 \quad 5 \quad 6 \quad 7 \quad 8 \quad 9 \quad 10 \quad 11 \quad 12 \quad 13 \quad 14 \quad 15 \quad 16 \dots$$

$$\varphi(n) \quad 1 \quad 1 \quad 2 \quad 2 \quad 2 \quad 6 \quad 4 \quad 6 \quad 4 \quad 10 \quad 4 \quad 12 \quad 6 \quad 8 \quad 8 \dots$$

$$\varphi(n) \quad 2 \quad 3 \quad 5 \quad 7 \quad 11 \quad 13 \quad 19 \quad 23 \quad 29 \quad 33 \quad 43 \quad 47 \quad 59 \quad 65 \quad 73 \quad 81 \dots$$

Bảng 2. Hàm Euler và số phân số $F_n$.

nghiệm $\frac{\varphi(n)}{n}$ gần tùy ý với 0 và 1), với $\varphi(n)$ người ta có thể chứng minh hệ thức giới hạn sau:

$$\lim_{n \to \infty} \frac{\varphi(n)}{n^2} = \frac{3}{\pi^2} \approx 0,305 \dots,$$

tức là $\varphi(x)$ đối với $x$ lớn tăng “xấp xỉ dọc theo một parabol”: $\varphi(x) \approx \frac{3}{\pi^2} x^2$.

Đây là một trong những định lý hay được nhà toán học gốc F. Mertens (1874) thu được.

4. mẫu số liền kề

Bây giờ chúng ta hãy quay lại câu hỏi đặt ra ở cuối đoạn 3 và giải thích lý do tại sao, hành động theo quy tắc B, chúng ta sẽ thu được tất cả $\varphi(n)$ các phân số tối giản có mẫu số $n$. Hãy thực hiện thêm một quan sát nữa.

Chúng ta hãy chú ý đến mẫu số của các phân số trong bảng 1. Để thuận tiện, chúng ta hãy soạn một bảng 3 mới từ chúng. Quy tắc B cho phép chúng ta tiếp tục “bảng mẫu số” (không cần quan tâm đến các chữ số) như sau.

TRONG'. Cần đánh dấu ở dòng thứ $(n-1)$ tất cả các cặp $q$, $s$ của các số lân cận, tổng của các số đó là $n$ và xét $n$ giữa chúng.

Như chúng tôi đã nói, các giá trị lân cận $q$ và $s$ trong Bảng 3 là tương đối nguyên tố (xem thuộc tính D, điểm 2). Bây giờ chúng ta hãy lưu ý rằng, khi nhập tổng $q+s=n$ vào dòng thứ $n$, chúng ta gặp phải cách biểu diễn nào trong số $\varphi(n)$ có thể biểu diễn $n$ dưới dạng tổng của các số nguyên tố cùng nhau (và chính xác là một). Ví dụ: trong chuỗi nhị phân:

36

⟦folio 37⟧

Bảng 3. Mẫu số của chuỗi Farey

$$9 = 1 + 8, \quad 9 = 5 + 4, \quad 9 = 7 + 2,$$
$$9 = 2 + 7, \quad 9 = 4 + 5, \quad 9 = 8 + 1.$$

Bài tập 6. Thêm ba dòng nữa của Bảng 3 và kiểm tra xem tất cả φ(n) được biểu thị bằng mẫu số n là tổng của hai mẫu số liền kề n = q + s xuất hiện đúng một lần.

Chúng ta xây dựng nhận xét ở Bài tập 6 như sau.
D. Ở hàng thứ n của Bảng 3, mỗi số nguyên tố cùng nhau với n trước đây là “hàng xóm” đúng hai lần: một lần trên đường đi và một lần ở bên phải.

Bài tập 7. Chứng minh rằng nếu tính chất Γ có ở tất cả các hàng trước của Bảng 3 thì nó cũng phải có ở hàng thứ n theo quy tắc B'.

Bài tập 7 (theo nguyên lý quy nạp toán học) suy ra rằng nếu lấy được các hàng mới của Bảng 3 theo quy tắc B' thì ở tất cả các hàng tính chất Г sẽ được thỏa mãn, và do đó, ở hàng thứ n sẽ có chính xác f(n) số hạng mới!

Bài tập 8. Chúng ta hãy bắt đầu từ dòng $\left(\frac{0}{1}, \frac{1}{1}\right)$, thực hiện thao tác sau nhiều lần: giữa hai phân số đã viết sẵn, chúng ta chèn trung vị của chúng. Chứng minh rằng với bất kỳ chuỗi nào có thể thu được theo cách này thì tính chất A và B đều thỏa mãn.

Cụ thể, từ kết quả của bài toán này, các thuộc tính A và B được thỏa mãn cho mỗi dòng của bảng 4, trong đó trung vị được chèn vào giữa mỗi và hai phân số ở dòng tiếp theo.

Bài tập 9. Chứng minh rằng trong Bảng 4, ở mỗi dòng, bắt đầu từ dòng thứ n, tất cả các phân số tối giản có mẫu số n đều xuất hiện, mỗi phân số xuất hiện một lần.

Bảng 4. 《Tăng tốc》 Chuỗi Farey.

Bảng 4 của bột được liên kết với bảng số nguyên, được G. A. Galperin từ “Bài toán Kvant” xem xét trong bài toán M233. Bảng 5 này không chỉ xuất hiện ở mẫu số của các phân số trong bảng 4, mà còn ở các chữ số của chúng (trong “nửa” thứ hai của bảng 4, bắt đầu từ dòng thứ hai, trong “phần tư” thứ hai, bắt đầu từ dòng thứ ba, v.v.!)!

5. Bằng chứng thứ hai

Chúng ta hãy đưa ra một chứng minh ngắn gọn về tính chất A và B bằng cách sử dụng chuỗi Farey $F_n$, dựa trên tính chất a) của các phân số gần (bằng chứng như vậy được đưa ra trong cuốn sách [2]).

Việc chứng minh cũng được thực hiện bằng quy nạp. Giả sử rằng đối với tất cả các hàng $F_1, F_2, \dots, F_{n-1}$ trước $F_n$, thuộc tính A và B đã được chứng minh. Đặt một số phân số $m/n$ (vì vậy mẫu số n) được đặt giữa các phân số lân cận $p/q$ và $r/s$ từ $F_{n-1}, p/q < r/s$ (do đó $qr - ps = 1$).

Sau đó

$$\frac{m}{n} - \frac{p}{q} \geq \frac{1}{qn}$$

Và

$$\frac{r}{s} - \frac{m}{n} \geq \frac{1}{sn}.$$

Cộng các bất đẳng thức này, ta được

$$\frac{r}{s} - \frac{p}{q} \geq \frac{q + s}{nqs};$$

⟦folio 38⟧

$$\frac{q+s}{n} \leq qr - ps = 1;$$
$$q+s \leq n.$$

Bất đẳng thức thứ hai $q+s < n$ không thể được thỏa mãn: trong trường hợp này, phân số $(p+r)/(q+s)$ sẽ xảy ra giữa $p/q$ và $r/s$ đã có trong $F_{n-1}$ (thêm vào $F_{q+s}$).

Kể từ đây,
$$n = q+s,$$
(4)
và do đó bất đẳng thức (3) cũng phải là đẳng thức, do đó
$$mq-np = 1, nr-ms = 1.$$ (5)
Từ (4) và (5) suy ra $m = p+r$.

Vì vậy, chúng ta đã chứng minh rằng $m/n$ là trung vị của các phân số $p/q$ và $r/s$ và gần với từng phân số đó. (Về cơ bản, ở đây chúng ta đã chứng minh tính chất e) của các phân số gần.) Điều này có nghĩa là tính chất A và B cũng đúng với $F_n$.

Căng thẳng 10. Chứng minh rằng:
a) nếu các phân số $m/n$ và $p/q$, trong đó $q < n$ gần nhau thì chúng là các phân số lân cận trong $F_n$;
b) mọi phân số gần $m/n$ đều bằng một trong các phân số $(m+kr)/(n+ks)$ hoặc $(m+kp)/(n+kq)$, trong đó $k = 0, 1, 2, \dots$, $p/q$ và $r/s$ là lân cận của $m/n$ trong $F_n$.

Căng thẳng 11. Đặt trong dãy các phân số $\frac{1}{1} \leq \xi_1 \leq \dots \leq \xi_N \leq \frac{1}{1}$ cứ hai phân số liền kề thì gần nhau. Chứng minh rằng các dãy này có thể thu được bằng cách sử dụng quy trình được mô tả trong Bài tập 8.

Giải thích hình học mà chúng ta hướng tới có nghĩa là làm rõ các nguyên tắc đơn giản của các mẫu A và B, đồng thời gợi ý ý tưởng về một bằng chứng khác.

6. Lưới và hình bình hành

Hãy lấy một tờ giấy ca-rô và giới thiệu hệ tọa độ trên đó. Chúng ta lấy hai đường lưới vuông góc làm trục tọa độ và cạnh của ô làm đơn vị tỷ lệ.

Hãy tương ứng với mỗi phân số $m/n$ ($0 \leq m/n \leq 1, n > 0$) một điểm có tọa độ $(n, m)$. (Trong Hình 1, đây là những chấm đen.) Thay vì “dấu chấm”, đôi khi chúng ta sẽ nói “phân số”.

Các phân số tối giản trong Hình 1 được khoanh tròn màu xanh lam và những phân số có số không lớn hơn 4 được nối bằng các đoạn màu xanh lam với gốc O.

Hãy xây dựng một số tính chất của phân số trong ngôn ngữ hình học. Cho $p/q$ và $r/s$ là hai phân số, $A(q, p)$ và $B(s, r)$ điểm tương ứng của chúng.

a) $p/q = r/s$ khi và chỉ nếu điểm A và B nằm trên cùng một tia với gốc O. Nút gần O nhất trên tia này tương ứng với một phân số tối giản.

Tiếp theo, chúng tôi giả sử rằng $p/q \neq r/s$.

6) $p/q > r/s$ nếu tia OA tạo một góc lớn hơn với trục tọa độ ngang so với tia OB.

⟦folio 39⟧

C) Phân số $(p+r)/(q+s)$ tương ứng với bốn đỉnh $C(p+r, q+s)$ của hình bình hành $OACB$ (Hình 2). Đối với những người quen thuộc với vectơ, hãy viết nó như thế này: $\overrightarrow{OC} = \overrightarrow{OA} + \overrightarrow{OB}$. (Chúng ta thấy rằng sự phụ âm của các thuật ngữ “trung tuyến” và “trung tuyến” không phải ngẫu nhiên: đoạn $OC$ đi chính xác dọc theo đường trung tuyến của tam giác $OAB$.)

d) $|qr-ps|$ bằng hai lần diện tích $\Delta AOB$, tức là diện tích hình bình hành $OACB$.

e*) Bên trong và trên các cạnh của hình bình hành này $OACB$ khi và chỉ khi không có nút nào (ngoại trừ các đỉnh) khi $|qr-ps|=1$.

e*) Trong trường hợp này, điểm $C$ là nút gần $O$ nhất trên lưới nằm bên trong góc $AOB$.

Đúng 12. Chứng minh tính chất a)—r).

Chìa khóa để giải thích tính quy luật của chuỗi Farey là tính chất d) và e*).

Chúng ta hãy nhìn trực quan vào Hình 2 và Hình 3. Trong đó, phần bên trong của góc $AOB$ được cắt bằng các đường thẳng thành hình bình hành bằng hình bình hành $OACB$. Tất cả các đỉnh của chúng đều nằm trong các nút giấy ca-rô. Nhưng trong Hình 2 (trong đó diện tích $OACB$ lớn hơn 1) nhiều nút của góc trong $AOB$ không phải là đỉnh của các hình bình hành này. Và trong Hình 3 (ở đây diện tích $OACB$ bằng 1) bất kỳ nút nào của góc trong $AOB$ là đỉnh của hình bình hành đó, tức là với bất kỳ nút nào như vậy $M(n, m)$ đều có các số tự nhiên $x$ và $y$ mà

$$\overrightarrow{OM} = x \cdot \overrightarrow{OA} + y \cdot \overrightarrow{OB}.$$

(6)

Vector đẳng thức (6) tương đương với hệ phương trình

$$\begin{cases} px + ry = m, \\ qx + sy = n. \end{cases}$$

*). Chúng có thể được chứng minh dựa trên tính chất của các mạng trên mặt phẳng (xem bài viết của A. A. Egorov và N. B. Vasiliev, «Kvant», 1974, No. 12.

13. a) Chứng minh rằng nếu $|qr-ps|=1$, trong đó $p, q, r, s$ là số nguyên thì hệ (7) với mọi số nguyên $m$ và $n$ đều có lời giải trong các số nguyên $x$ và $y$.

b*) Viết và chứng minh định lý ngược lại.

b) Suy ra từ a) rằng đối với hai phân số gần nhau $p/q < r/s$ thì bất kỳ phân số nào $m/n$, trong đó $p/q < m/n < r/s$, có thể được biểu diễn dưới dạng $\frac{px+ry}{qx+sy}$, trong đó $x$ và $y$ là số tự nhiên.

d) Chứng minh tính chất của e* từ điểm 2 và 5 và suy ra các định luật A và B từ chuỗi Farey.

Phần kết luận

Chúng tôi đã phác thảo một số cách để xây dựng một lý thuyết nhỏ nhưng hay về chuỗi Farey.

Lý thuyết này có thể được xây dựng ngay từ khi bắt đầu nghiên cứu về số nguyên mà không cần dựa vào định lý cơ bản của số học (dựa vào tính duy nhất của hệ số hóa). Bản thân định lý này có thể được suy ra từ các tính chất của chuỗi Farey. Từ các tính chất này, bạn cũng dễ dàng thu được lời giải dưới dạng số nguyên từ phương trình $ax-by=1$, trong đó $a$ và $b$ rất đơn giản: chỉ cần xét phân số $\frac{a}{b}$ và lấy bất kỳ phân số lân cận nào của nó trong chuỗi Farey là đủ.

Chuỗi Farey, cũng như cách biểu diễn các phân số trên một mạng, cũng hữu ích trong các câu hỏi phức tạp hơn về việc tính gần đúng các số thực bằng các phân số có giá trị nhỏ.

Văn học

1. N. B. Vasiliev. Lời giải bài toán M233. «Kvant», 1974, số 7, tr. 39.
2. I. M. Vinogradov. Cơ sở lý thuyết số. M., “Khoa học”, 1965.
3. K. Chandraekharan. Giới thiệu lý thuyết số phân tích. M., "Mir", 1974.
4. D. B. Fuks, M. B. Fuks. "Trên những ước tính gần đúng nhất." «Kvant», 1971, không. 6 và 11.
