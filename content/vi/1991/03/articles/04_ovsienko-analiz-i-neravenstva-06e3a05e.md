---
id: 1991-3-ovsienko-analiz-i-neravenstva-06e3a05e
issue: kvant_1991_3
year: 1991
number: "3"
title: Phân tích và bất đẳng thức
authors:
  - Овсиенко В. Ю.
rubric: osnovnye-stati
page_first: 17
page_last: 20
page_labels: 15-18
lang: vi
source: kvant_digital
extraction: vision
content_sha256: dde7e85b8d42caef75880d9ed1fc9d5ab75ea017b5031ec6bac84d253eee50fb
prompt_sha256: draft-1
translated_from: content/ru/1991/03/articles/04_ovsienko-analiz-i-neravenstva-06e3a05e.md
source_content_sha256: 2f35a29dd075e24fb8d1a98b1ec75356db3dd214be9edd3c298577401661398b
translation_model: draft
translation_run: vi-draft-gaps-2026-11-06
translation_quality: draft
---

⟦folio 15⟧

---
running_head:
folio:
---

PHÂN TÍCH VÀ
BẤT ĐẸP

Ứng viên Khoa học Vật lý và Toán học
V. OVSIENKO

Henri Poincaré nói rằng toán học là cách nói cùng một điều về việc làm những việc khác nhau. Điều này đặc biệt áp dụng cho phân tích toán học, giống như chiếc chìa khóa chính trong tay một tên trộm giàu kinh nghiệm, cung cấp “chìa khóa vạn năng cho mọi cánh cửa”...

Chúng ta sẽ nói về ba nhiệm vụ khác nhau mà chúng ta sẽ giải quyết theo cùng một cách. Cơ sở của lời giải sẽ là một phát biểu nổi tiếng trong khóa học ở trường: nếu đạo hàm của một hàm nào đó lớn hơn 0 thì hàm này tăng (và ngược lại, nếu đạo hàm nhỏ hơn 0 thì nó đang giảm).

Bất đẳng thức cho sin và cosin

Bất bình đẳng

$$\sin x < x,$$
$$\cos x > 1 - \frac{x^2}{2},$$

hợp lệ cho $x > 0$ (hình 1), các giá trị hình học thường được chứng minh (ở trường). Tuy nhiên, bằng chứng phân tích đơn giản hơn nhiều và không đòi hỏi nhiều sự khéo léo.

Hãy bắt đầu với bất đẳng thức đầu tiên. Hàm $y_1(x) = \sin x$ và $y_2(x) = x$ giống nhau trong nULE. Do đó, chỉ cần chứng minh rằng tại $x > 0$ hàm thứ hai tăng nhanh hơn hàm thứ nhất (tức là $y(x) = x - \sin x$ là hàm tăng tại $x > 0$). Nhưng đạo hàm của $y'(x) = 1 - \cos x$ lớn hơn 0 tại $x > 0$. Bất đẳng thức đã được chứng minh.

Để chứng minh bất đẳng thức thứ hai, ta làm tương tự.

Hàm $y(x) = \cos x - 1 + \frac{x^2}{2}$ bằng 0 tại $x = 0$. Đạo hàm của nó là $y'(x) = -\sin x + x$. Do đó, $y'(x) > 0$ với $x > 0$ (do lần đầu tiên

⟦folio 16⟧

---
running_head:
folio:
---

bất bình đẳng!), tức là hàm số đang tăng và do đó dương.

Bài tập
1. Chứng minh rằng với $x > 0$
a) $\sin x > x - \frac{x^3}{6}$,
b) $\cos x < 1 - \frac{x^2}{2} + \frac{x^4}{24}$.

Gợi ý. Làm như trước. Sau khi lấy đạo hàm, sử dụng các bất đẳng thức trước đó.
2. Tiếp tục chuỗi bất đẳng thức thu được sin $x$ và cos $x$.

Bất đẳng thức trong tam giác

Đối với một tam giác có các góc $\alpha, \beta, \gamma$ (hình 2), bất đẳng thức sau có giá trị:
$$\sin \alpha + \sin \beta + \sin \gamma \leq \frac{3\sqrt{3}}{2}.$$

Hãy chứng minh điều đó. Đầu tiên, lưu ý rằng đẳng thức đúng nếu tam giác đều ($\alpha = \beta = \gamma = 60^\circ$).

Giả sử tam giác đều và các góc của nó bằng $\alpha = 60^\circ + x, \beta = \gamma = 60^\circ - \frac{x}{2}$, trong đó $x$ là một số sao cho $-60^\circ < x < 120^\circ$. thì biểu thức $\sin \alpha + \sin \beta + \sin \gamma$ là hàm của $x$:
$$f(x) = \sin (60^\circ + x) + 2\sin \left(60^\circ - \frac{x}{2}\right).$$
Sản phẩm của cô ấy là $f'(x) = \cos (60^\circ + x) - \cos \left(60^\circ - \frac{x}{2}\right)$. Rõ ràng là $f'(x) > 0$ tại $-60^\circ < x < 0$ và $f'(x) < 0$ tại $0 < x < 120^\circ$. Do đó, hàm $f(x)$ có cực đại tại điểm $x = 0$ và càng nhỏ thì $x$ càng xa 0.

Bây giờ hãy để hàm $\alpha$ thay đổi các góc $\beta$ và $\gamma$: $\beta = \delta - x$, $\gamma = \delta + x$. Khi đó biểu thức ban đầu sẽ lại là hàm của $x$:
$$f(x) = \sin (\delta - x) + \sin (\delta + x) + \sin \alpha.$$
Công việc của cô ấy là $f'(x) = \cos (\delta + x) - \cos (\delta - x)$. Một lần nữa, $f'(x)$ lớn hơn 0 đối với $x$ âm và nhỏ hơn 0 đối với $x$ dương. Nói cách khác, tam giác càng khác với tam giác đều thì biểu thức $\sin \alpha + \sin \beta + \sin \gamma$ càng nhỏ.

Bất đẳng thức được chứng minh vì có thể thu được một tam giác từ một tam giác đều bằng cách trước tiên thay đổi góc $\alpha$, sau đó $\beta$ và $\gamma$. Chúng tôi tin rằng với sự thay đổi như vậy biểu thức $\sin \alpha + \sin \beta + \sin \gamma$ sẽ luôn giảm.

Bài tập 3. Chứng minh bất đẳng thức
a) $\cos \alpha + \cos \beta + \cos \gamma \leq \frac{3}{2}$,
b) $\sin \alpha \cdot \sin \beta \cdot \sin \gamma \leq \frac{3\sqrt{3}}{8}$,
b) $\cos \alpha \cdot \cos \beta \cdot \cos \gamma \leq \frac{1}{8}$,
nếu $\alpha, \beta, \gamma$ là một hình tam giác nào đó.

Bất đẳng thức Cauchy

Đối với mọi số không âm $a_1, ..., a_n$, bất đẳng thức sau đúng:
$$\frac{a_1 + ... + a_n}{n} \geq \sqrt[n]{a_1 \cdot ... \cdot a_n}$$

giữa trung bình số học và trung bình hình học. Nó được gọi là bất đẳng thức Cauchy. Chúng tôi sẽ chứng minh điều đó bằng cách sử dụng cùng một phương pháp, tức là bằng cách tính hàm tùy ý của một số hàm.

Để khởi động, chúng ta hãy bắt đầu với việc chứng minh một trường hợp rất đơn giản $n = 2$.

⟦folio 17⟧

---
running_head:
folio:
---

$\frac{a+b}{2} \geqslant \sqrt{ab}$
chứng minh theo nhiều cách hình học khác nhau (bao gồm cả những cách rất đẹp). Chúng tôi sẽ tìm ra phương pháp của chúng tôi trên đó. Hãy để định nghĩa $a \leqslant b$. Khi đó $b=a+x$, trong đó $x$ là một số không âm. Biểu thức $\frac{a+b}{2} - \sqrt{ab}$ trở thành hàm của $x$, có dạng $f(x) = \frac{2a+x}{2} - \sqrt{a(a+x)}$.
Đối với $x=0$ hàm số là $f(x)=0$, tích của nó là $f'(x) = \frac{1}{2} - \frac{1}{2} \sqrt{\frac{a}{a+x}} > 0$.
Do đó, hàm $f(x)$ ngày càng tăng, tức là trung bình số học càng lớn hơn trung bình hình học thì chênh lệch $b-a=x$ càng lớn.
Bây giờ hãy chứng minh bất đẳng thức Cauchy trong trường hợp tổng quát. Thực ra, chứng minh này là sự lặp lại chứng minh trước đó. Chúng ta chỉ cần giá trị đạo hàm của hàm $\sqrt[n]{x^k} = x^{\frac{k}{n}}$. Nó được tính trong sách giáo khoa của trường: $\left( x^{\frac{k}{n}} \right)' = \frac{k}{n} x^{\frac{k}{n}-1}$.
Hãy để định nghĩa $a_1 \leqslant a_2 \leqslant \dots \leqslant a_n$. Rõ ràng là với $a_1 = \dots = a_n$ sự bất bình đẳng của chúng ta chuyển thành đẳng thức. Chúng tôi sẽ lấy $n$ số giống hệt nhau $a_1, a_1, \dots, a_1$ và tăng chúng (bắt đầu từ số thứ hai), nhưng không phải theo một bước mà theo $(n-1)$ bước. Ở bước đầu tiên -
$$a_1, a_1+z, \dots, a_1+z$$
(trong đó $a_1+z=a_2$),
ở bước thứ hai -
$$a_1, a_2, a_2+y, \dots, a_2+y$$
(trong đó $a_2+y=a_3$).
Chúng ta sẽ kết thúc với một bộ số $a_1, a_2, \dots, a_n$.
Chúng ta sẽ chứng minh rằng ở bất kỳ bước nào sự khác biệt giữa trung bình số học và trung bình hình học đều tăng lên

⟦folio 18⟧

---
running_head:
folio:
---

Chúng tôi đã chạy chuyên mục này từ số này đến số khác kể từ khi thành lập tạp chí. bài toán được xuất bản trong đó là không chuẩn, nhưng lời giải của chúng không yêu cầu kiến ​​thức ngoài phạm vi chương trình học ở trường. bài toán khó nhất được đánh dấu bằng dấu hoa thị. Sau khi hình thành bài toán, chúng tôi thường cho biết ai đã đề xuất điều đó cho chúng tôi. Tất nhiên, không phải tất cả những bài toán này đều được xuất bản lần đầu tiên.
Lời giải bài toán từ số này phải được gửi chậm nhất là ngày 15 tháng 5 năm 1991 đến địa chỉ: 103006, Moscow K-6, st. Gorky, 32/1, «Kvant».
Lời giải bài toán từ các số khác nhau của tạp chí hoặc trong các chủ đề khác nhau (toán học và vật lý) hãy gửi vào các phong bì khác nhau. Trên phong bì, ở cột “Tới”, viết: “Vấn đề «Kvant» Số 3 - 91” và các số bài toán, lời giải mà bạn đang gửi, ví dụ “M1271” hoặc “F1278”.
Ở cột “…địa chỉ người gửi”, vui lòng ghi riêng họ và tên của bạn. Bao gồm một phong bì có ghi địa chỉ của bạn trên đó (bạn sẽ nhận được kết quả xác minh lời giải trong phong bì này).
Vui lòng đính kèm điều kiện của mỗi bản gốc bài toán được đề xuất xuất bản trong một phong bì riêng thành hai bản sao cùng với giải pháp của bạn cho bài toán này (đánh dấu trên phong bì: “Vấn đề «Kvant», bài toán mới trong vật lý” hoặc “...mới bài toán trong toán học”).
Ở đầu mỗi chữ cái, vui lòng cho biết mã số trường và lớp mà bạn sẽ học.
