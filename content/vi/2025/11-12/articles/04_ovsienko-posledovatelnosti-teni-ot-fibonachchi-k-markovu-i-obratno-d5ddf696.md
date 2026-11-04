---
id: 2025-11-12-ovsienko-posledovatelnosti-teni-ot-fibonachchi-k-markovu-i-obratno-d5ddf696
issue: kvant_2025_11-12
year: 2025
number: 11-12
title: 'Chuỗi bóng: từ Fibonacci đến Markov và ngược lại'
authors:
  - Овсиенко В. Ю.
rubric: osnovnye-stati
page_first: 11
page_last: 16
page_labels: 13-14
lang: vi
source: kvant_digital
extraction: vision
content_sha256: 8a529b589f8fbea3a7e2392efaf58a2a55e85fdcd382b66d0888a9c77ea2a67b
prompt_sha256: draft-1
translated_from: content/ru/2025/11-12/articles/04_ovsienko-posledovatelnosti-teni-ot-fibonachchi-k-markovu-i-obratno-d5ddf696.md
source_content_sha256: f225225f81e9f57c981016301f7777c523463b0d7edbc93e71cc49d7f784e1e2
translation_model: draft
translation_run: vi-draft-gaps-2026-11-04
translation_quality: draft
---

⟦folio none⟧

---
running_head:
folio:
---

Thẻ trình tự:
từ Fibonacci đến Markov
và quay lại

V. OVSIENKO

TRONG BÀI VIẾT NÀY CHÚNG TÔI THẢO LUẬN-
số nguyên lặp lại rome
trình tự và thiết lập
câu hỏi nhỏ. Điều gì sẽ xảy ra nếu một trình tự như vậy
Thực sự có một số nguyên khác
trình tự sau đó
giống tôi à? Hãy để chúng tôi chứng minh điều đó trong trường hợp đó
đặt ra câu hỏi, thực tế là
nghĩa. Tuy nhiên, chúng tôi không cam kết yêu cầu bồi thường
Đúng là hoàn toàn có thể tìm thấy bóng tối như vậy
trình tự nào cũng được, mặc dù vậy
nam vẫn chưa biết về một biện pháp phản công nào
pimera

Vì vậy, với mỗi chuỗi chúng ta
Hãy thử so sánh ít nhất một cái nữa.
Phải chăng điều này có nghĩa là lượng kiến ​​thức đã biết
tuần tự và đăng ký
thông tin trong Bách khoa toàn thư trực tuyến về số nguyên
Trình tự OEIS (phụ
Để biết thêm thông tin về bách khoa toàn thư, xem bài viết [1]),
hiện vượt quá 350.000, sẽ tăng gấp đôi
Hạ? Đáp số âm vì hai lý do-
nam: một mặt thì rất nổi tiếng
trình tự cũng có thể là do
trình tự đã biết và mặt khác
tay, một chuỗi có thể-
có thể có một số bóng.

Để đi đến trình tự-
thì chúng ta cần khái niệm kép
những con số. Có đủ chi tiết về những con số này
à được mô tả trong cuốn sách [2].

Stratia là một bản dịch sửa đổi
stats “Chuỗi bóng của số nguyên: Từ
Fibonacci to Markov và Back", được xuất bản bởi
Nô-ê trên tạp chí Trí tuệ toán học
2023.

DOI: https://doi.org/10.4213/kvant20251102

Số kép

Xét một cặp số $A = (a, \alpha)$,
$a, \alpha \in \mathbb{R}$, như một biểu thức của hình thức

$$A = a + \alpha \varepsilon,$$

trong đó $\varepsilon$ là một ký hiệu nào đó. Nếu $\varepsilon$ là mức tối thiểu
đơn vị, tức là $\varepsilon^2 = -1$, thì $A$ là phức tạp
con số. Nếu $\varepsilon$ thỏa mãn điều kiện
$\varepsilon^2 = 0$ thì $A$ được gọi là số $\delta$-ual.
Hơn nữa, bản thân ký hiệu $\varepsilon$ không phải là số không.
Trên tập hợp số kép ta có thể giới thiệu
các phép tính số học đơn giản:

$$(a + b\varepsilon) + (c + d\varepsilon) = (a + c) + (b + d)\varepsilon,$$

$$(a + b\varepsilon) - (c + d\varepsilon) = (a - c) + (b - d)\varepsilon,$$

$$\cdot (a + b\varepsilon) \cdot (c + d\varepsilon) = ac + (ad + bc)\varepsilon,$$

$$\frac{a + b\varepsilon}{c + d\varepsilon} = \frac{a}{c} + \frac{bc - ad}{c^2}\varepsilon (c \neq 0).$$

Như chúng ta thấy, các phép toán với số kép
lamami về nhiều mặt tương tự như các hoạt động với
số phức. Tương tự bạn có thể
theo dõi thêm. Số $a - b\varepsilon$ có thể là
xét liên hợp với số kép
$a + b\varepsilon$. Tích của số liên hợp
là số thực:

$$(a - b\varepsilon)(a + b\varepsilon) = a^2.$$

Thực hiện một sự tương tự
với số phức, chúng ta có được $a$
việc xem xét mô-đun của kép là điều đương nhiên
số $a + b\varepsilon$ và viết số đó thành ba
dạng hình học $a + b\varepsilon = a(1 + \varepsilon\varphi)$,
trong đó $\varphi$ là đối số của số kép.
Khi đó khi nhân hai số
được viết dưới dạng lượng giác,
giống như số phức, các mô đun

⟦folio 13⟧

---
running_head:
folio:
---

Số Markov có thể được sắp xếp bằng cách sử dụng cây nhị phân vô hạn. Vẽ một cái cây trên một mặt phẳng sẽ cắt nó thành vô số vùng, mỗi vùng có một số Markov tương ứng. Ảnh cục bộ (tức là ở vùng lân cận của mỗi đỉnh) trông giống như trong hình 1. Các phép biến đổi (6) tương ứng với các nhánh được hiển thị trong hình 2. Cây Markov thu được được mô tả trong hình 3.

Chúng ta hãy xem xét các nhánh cực trị trên hình – những nhánh được giới hạn bởi các vùng có số 1 và 2. Lưu ý rằng các bộ ba số Markov tương ứng chứa các số Fibonacci lẻ $(1, F_{2k-1}, F_{2k+1})$ và các số Pell lẻ $(2, P_{2k-1}, P_{2k+1})$ – các dãy A001519 và A001653. Trên thực tế, các chuỗi con và cách sắp xếp khác nhau của số Markov tạo nên mười chuỗi trong OEIS (xem A002559 và các chuỗi liên quan).

Bóng trình tự Markov

Mục tiêu của chúng tôi là làm bất cứ điều gì ngoại trừ phủ bóng lên các số Markov, nhưng việc áp dụng cấu trúc chung của ánh xạ bóng cho chúng đã rất hấp dẫn. Việc này được thực hiện rất đơn giản. Chúng ta hãy chọn bộ ba số kép ban đầu $(A_1, B_1, C_1)$:

$$A_1 = 1 + \alpha_1 \varepsilon,$$
$$B_1 = 1 + \beta_1 \varepsilon,$$
$$C_1 = 1 + \gamma_1 \varepsilon,$$

trong đó $\alpha_1, \beta_1, \gamma_1$ là số nguyên tùy ý. Sau đó áp dụng cho $A = a + \alpha \varepsilon, B = b + \beta \varepsilon, C = c + \gamma \varepsilon$ tất cả các phép biến đổi có thể

$(A, B, C) \mapsto (A', B, C)$, trong đó $A' = \frac{B^2 + C^2}{A}$ và các hoán vị $A, B$ và $C$. Thu thập các số hạng có và không có $\varepsilon$, chúng ta nhận được

$$a' = \frac{b^2 + c^2}{a}, \quad \alpha' = \frac{2b\beta + 2c\gamma - a'\alpha}{a}. \tag{8}$$

Lần này nó không indo lắm, tại sao toàn bộ $\alpha'$.

Mệnh đề 3. Với sự lựa chọn tùy ý các điều kiện ban đầu (7) của phép biến đổi (8), cùng với các hoán vị, các chuỗi số nguyên $\{\alpha_n\}, \{\beta_n\} u \{\gamma_n\}$ được tạo ra.

Tính nguyên vẹn này được bảo toàn nhờ một thực tế thay thế được gọi là hiện tượng Laurent (xem [8]), hiện tượng này cũng đảm bảo tính nguyên vẹn của các chuỗi Comosa và Gale-Robinson. Chứng minh tính chất nguyên của dãy Comosa cũng có thể được đọc trong [5].

Có một lựa chọn về giá trị ban đầu $(\alpha_1, \beta_1, \gamma_1)$ có vẻ vừa tự nhiên vừa thú vị:

$(\alpha_1, \beta_1, \gamma_1) = (0, 1, 1). \tag{9}$

Chúng ta hãy xem xét nó chi tiết hơn. Thứ nhất, việc lấy các giá trị ban đầu đối xứng ở phần tử thứ hai và thứ ba là điều tự nhiên, tức là đoán $\beta_1 = \gamma_1$. Chọn lại $(\alpha_1, \beta_1, \gamma_1) = (1, 1, 1)$ cho số Markov:

$$\alpha_n = a_n, \quad \beta_n = b_n, \quad \gamma_n = c_n,$$

điều đó không thú vị lắm. Chọn $(\alpha_1, \beta_1, \gamma_1) = (1, 0, 0)$ cho tổng số hạng. Lựa chọn (9) là lựa chọn duy nhất còn lại. hình 4 hiển thị cây số Markov cùng với chủ đề của chúng.

⟦folio 14⟧

---
running_head:
folio:
---

Chúng ta hãy kết thúc bằng một vài quan sát. Tiếp theo
1,4,13,40,120,354,1031,2972,8495, ...
xuất hiện như một vệ tinh của nhánh Fibonacci của các số lẻ hóa ra lại là một dãy nổi tiếng. Dãy số A238846 đáng chú ý này là ánh sáng của hai dãy con của dãy Fibonacci $\{F_{2n+1}\}$ và $\{F_{2n}\}$. Các chuỗi con khác thu được từ cây bằng cách lần theo các nhánh của nó dường như là mới.
Vai trò của bóng chuỗi Markov là gì? Nó có ý nghĩa gì? Và nó có ý nghĩa gì không? Tôi muốn giải quyết bài toán này, nhưng ở giai đoạn này chúng tôi chỉ có thể nói với Winnie the Pooh:
– Câu hỏi của tôi rất đơn giản và ngắn gọn, –
Tê giác đã nói:
Cái nào tốt hơn - bốn mươi lăm
Hay bốn mươi gót? –
Than ôi, không có gì cho việc này
Đáp số
Tôi không thể cho nó!

Văn học
1. A. Zabolomsky. Mũi tên xấu. – «Kvant», 2022, số 7.
2. I. M. Yaglom. Số phức và ứng dụng của chúng trong hình học. – M. GIFML, 1963.
3. V. Ovsienko. A step towards cluster superalgebras. – arXiv:1503.01894, 2015.
4. V. Ovsienko and S. Tabachnikov. Dual numbers, weighted quivers, and extended Somos and Gale-Robinson sequences. – Algebras and Representation Theory, 2018, vol. 21, p. 1119–1132.
5. A. Ustminov. Trình tự Somoka. – «Kvant», 2023, số 8.
6. A. Markoff. Sur les formes quadratiques binaires indefinies. – Mathematische Annalen, 1879, vol. 15, p. 381–406.
7. M. Cẩu. Phương trình Diophantine của A. A. Markov. – «Kvant», 1985, số 4.
8. S. Fomin and A. Zelevinsky. The Laurent phenomenon. – Advances in Applied Mathematics, 2002, vol. 28, p. 119–144.
