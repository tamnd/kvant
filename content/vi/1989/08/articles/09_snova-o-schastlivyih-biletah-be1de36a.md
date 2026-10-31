---
id: 1989-8-snova-o-schastlivyih-biletah-be1de36a
issue: kvant_1989_8
year: 1989
number: "8"
title: Một lần nữa về vé may mắn
rubric: nam-pishut
rubric_sub: Нам пишут
page_first: 44
page_last: 44
page_labels: "42"
tag: VSQN
lang: vi
source: kvant_digital
extraction: vision
content_sha256: 8f197bc4064b3b697ccd2662163378c873fa8cbf736fc3d7b729498b7b3cc484
prompt_sha256: draft-1
translated_from: content/ru/1989/08/articles/09_snova-o-schastlivyih-biletah-be1de36a.md
source_content_sha256: 7dc1a27c523ab199e70a549091a6d8216a5df472a3d24e1e22c74c615dda1fea
translation_model: draft
translation_run: vi-draft-2026-10-31
translation_quality: draft
---

⟦folio 42⟧

Một lần nữa về vé may mắn

«Kvant» đã viết về vé may mắn một lần (1975, số 7, 1976, số 12, 1978, số 11, 1988, số 1 và số 4), tức là vé có tổng ba chữ số đầu bằng tổng của ba chữ số cuối. Số lượng vé may mắn $N$ được biểu thị bằng tích phân:

$$N = \frac{1}{\pi} \int_{0}^{\pi} \frac{\sin^6(10x)}{\sin^6 x} dx. \tag{1}$$

Trong công thức tuyệt vời này, số 6 biểu thị số vé may mắn có sáu chữ số đang được tính và số 10 biểu thị hệ thống số thập phân. Nếu cơ số của hệ thống số và số chữ số trên vé khác nhau thì công thức phải được thay đổi theo một cách rất khác.

G. A. Galperin từ Moscow và A. V. Korllyukov từ Grodno đã đặt câu hỏi: điều gì sẽ xảy ra nếu chúng ta tính số lượng vé may mắn $N$ bằng công thức gần đúng

$$N = \frac{1}{n} \sum_{k=1}^{n} f(x_k), \tag{2}$$

ở đâu $x_k = x_0 + k\pi/n$, $f(x) = \sin^6(10x)/\sin^6 x$. Họ nhận thấy rằng với mọi $n \geq 28$ và mọi đẳng thức $x_0$ (2) đều chính xác! (Đối với vé có độ dài $2S$ và hệ thống số $p$, bạn cần phải là $n \geq 1 + S(p-1)$).

Bằng chứng có thể thu được từ mô hình kỹ thuật số sau đây và đạo hàm của công thức (1), cho trong «Kvant» Số 11 năm 1978. Một cách chứng minh khác dựa trên thực tế là phân số $(\sin(px)/\sin x)^{2S}$ có thể được biểu diễn dưới dạng “đa thức hình học” $f(x) = \sum_{k=1}^{n} a_k \times \sin(kx) + bk\cos(kx)$; đối với bất kỳ đa thức nào như vậy, đẳng thức $$\frac{1}{\pi} \int_{0}^{x} f(x) dx = \frac{1}{n} \sum_{k=1}^{n} f(x_0 + k\pi/n)$$ đúng cho một $n$ đủ lớn (hãy nghĩ xem $n$ có liên quan như thế nào với “bậc” $n_0$ của đa thức lượng giác!).

Sẽ thuận tiện hơn khi tính số lượng vé may mắn trên máy tính và trên máy tính vi mô bằng công thức (2) hơn (1), đặc biệt vì giá trị giữa các số vẫn được thay thế bằng một giá trị gần đúng. Ngoài ra, có thể thu được những hệ quả thú vị từ công thức (2).

Ví dụ: giả sử vé bằng 2 và hệ thống số là số thập phân. Khi đó trong công thức (2) chỉ cần lấy 10 số hạng là đủ. Đối với số điểm $x_k$, chúng tôi lấy $\frac{\pi}{20}, \frac{3\pi}{20}, \dots, \frac{19\pi}{20}$. Số $N$ rất bằng 10 và $\sin^2(10x_k) = 1$ cho tất cả $k$. Đó là lý do tại sao

$$\frac{1}{\sin^2(10x)} + \frac{1}{\sin^2(3\pi/10)} = 12.$$

Với $S$ và $p$ khác, người đọc có thể tự mình thu được các đẳng thức tương tự.

A. A. Mikhailov đến từ Stuchka, Liên Xô thuộc Latvia, đề xuất một cách tiếp cận mới với bài toán về những tấm vé may mắn có độ dài $2n$ trong hệ thống số $p$-ary. Đây là lý do của anh ấy. Trước hết, số vé may mắn bằng số vé có tổng các chữ số bằng $n(p-1)$ (hãy thử chứng minh điều này nhé!). Lần lượt, số này bằng hệ số $x^{n(p-1)}$ của đa thức $f(x) = (1-x^p)^{2n}/(1-x)^{2n} = (1-x^p)^{2n} \times (1-x)^{-2n}$.

Để tìm đa thức này, bạn có thể sử dụng nhị thức Newton.

$$(1+t)^k = \sum_{S=0}^{k} \binom{k}{S} t^S,$$

trong đó các hệ số nhị thức $\binom{k}{S}$ bằng $k!/S!(k-S)!$ cho $0 \leq k \leq S$ và $0$ cho $k > S \geq 0$. Công thức nhị thức cũng đúng với số mũ âm $k$; đồng thời $\binom{-k}{S} = (-1)^S \binom{k+S-1}{S}$. Nếu chúng ta biểu thị cả hai thành phần có trong $f(x)$ bằng nhị thức thì không khó để tìm được hệ số của $x^{n(p-1)}$. Công thức cuối cùng của A. A. Mikhailov về số lượng vé may mắn sẽ như sau:

$$N_{2n}^p = \sum_{S=0}^{n} (-1)^S \binom{2n}{S} \binom{n-S}{p+n-1}{2n-1},$$

trong đó $m = \left[ n \left(1 - \frac{1}{p}\right) \right]$, dấu ngoặc vuông biểu thị phần nguyên của số. Một trường hợp đặc biệt của công thức này cho hệ thống phát hiện số thập phân cũng là các sinh viên đến từ Irkutsk D. Balyabin và S. Krivoshen.

Đối với số lượng vé may mắn được tính toán, chúng tôi nhận được

$$N_{6}^{10} = \binom{6}{0} \binom{32}{5} - \binom{6}{1} \binom{22}{5} + \binom{6}{2} \binom{12}{5} = 201376 - 6 \cdot 26334 + 15 \cdot 792 = 55252.$$

Như bạn có thể thấy, công thức (3) cho phép bạn tính số lượng vé may mắn khá đơn giản!

Đối với $p=2$, có một biểu thức thậm chí còn đơn giản hơn cho $N$. Thật vậy, trong trường hợp này $f(x) = (1+x)^{2n}$, do đó $N = \binom{2n}{n}$.

Ngoài ra, A. A. Mikhailov lưu ý rằng số lượng vé may mắn trùng với số điểm nằm thành một hàng bên trong khối $2n$-khối $[0, p+1]^{2n}$ để đi qua tâm của siêu phẳng, sự phân bố lại của đường chéo chính. Con số này thường được tìm thấy trong nghiên cứu về hình học đại số thực hiện đại và được gọi là số Petrovsky (để vinh danh Viện sĩ I. G. Petrovsky (1901-1973); xem bình luận trong cuốn sách “Các tác phẩm chọn lọc” của I. G. Petrovsky, xuất bản năm 1986 bởi nhà xuất bản Nauka).

*) Chúng còn được ký hiệu là $C_k^S$.
