---
id: 1986-7-tabov-ob-odnom-sposobe-zadaniya-okruzhnosti-2b086133
issue: kvant_1986_7
year: 1986
number: "7"
title: Về một cách để xác định một vòng tròn
authors:
  - Табов Й. Б.
rubric: shkola-v-kvante
rubric_sub: Школа в «Кванте»
page_first: 27
page_last: 28
page_labels: 25-26
tag: A831
lang: vi
source: kvant_digital
extraction: vision
content_sha256: 13fcce7ccc8813918faddabcc27bcee3baf2881ffad2d6543ced9158d00503d9
prompt_sha256: draft-1
translated_from: content/ru/1986/07/articles/08_tabov-ob-odnom-sposobe-zadaniya-okruzhnosti-2b086133.md
source_content_sha256: 3c1a0234563263fbc6ca5388bbd0eaffddee3189fc7af1a803f89c82e6d28928
translation_model: draft
translation_run: vi-draft-2026-10-31
translation_quality: draft
---

⟦folio 25⟧

Về một cách để xác định một vòng tròn

I. B. TABOV (NRV)

Như bạn đã biết, đường tròn được định nghĩa là quỹ tích của các điểm cách đều một điểm cố định O. Nhưng có nhiều cách khác để xác định đường tròn. Chúng ta sẽ xem xét một trong số chúng ở đây.

Gọi P là một điểm, l là tia phát ra từ điểm đó. Trên tia m, cũng phát ra từ điểm P và tạo thành góc nhọn hoặc góc vuông φ với tia l, chúng ta đánh dấu một điểm M nằm cách P một khoảng a cos φ, trong đó a là một số dương cố định (hình 1).

Định lý. Khi góc φ thay đổi trong khoảng từ -π/2 đến π/2, các điểm M tạo thành một đường tròn có đường kính a, đi qua điểm P và đối xứng với tia l.

(Với dấu cộng chúng ta vẽ các góc theo hướng ngược chiều kim đồng hồ, với dấu trừ chúng ta vẽ các góc theo chiều kim đồng hồ.)

Bằng chứng. Gọi R là một điểm trên đường tròn đối xứng với điểm P và gọi M là một điểm tùy ý

vòng tròn của chúng tôi (hình 2). Khi đó ∠PMR=π/2, có nghĩa là

PM=PR · cos (∠MPR)=a cos φ.

(Trường hợp M=R (φ=0) và M=P (φ=±π/2) đòi hỏi, nói đúng ra, một sự xem xét riêng biệt mà chúng tôi dành cho người đọc.) Do đó, tất cả các điểm của đường tròn đều thuộc về quỹ tích hình học của chúng ta, và vì đường tròn cắt mỗi tia m nên quỹ tích hình học đang xét không chứa bất kỳ điểm nào khác. Định lý đã được chứng minh.

Lưu ý rằng nếu trong mô tả vị trí hình học, biểu thức a cos φ được thay thế bằng biểu thức a cos (φ+δ) (và tất nhiên, điều kiện là góc φ là nhọn hoặc thẳng, được thay thế bằng điều kiện cos (φ+δ) ≥0), chúng ta thu được một đường tròn có đường kính a đi qua điểm P và đối xứng với tia tạo một góc δ (hình 3) với l.

Cuối cùng, nếu thay vì biểu thức a cos φ chúng ta viết biểu thức a sin φ (và điều kiện sin φ ≥0), thì chúng ta thu được một đường tròn có đường kính tiếp tuyến với tia l tại điểm P (hình 4).

Hãy để chúng tôi chứng minh tính hữu ích của quan sát của chúng tôi đối với lời giải một phi tiêu chuẩn bài toán.

Bài toán 1. Cho tam giác vuông đều A₀A₁A₂ vuông tại đỉnh A₀. Đối với một điểm C tùy ý trên đường tròn ngoại tiếp tam giác A₀A₁A₂, chúng ta đánh dấu trên tia A₀C một điểm M sao cho

A₀M=A₁C+A₂C-A₀C.

Tìm quỹ tích điểm M.

⟦folio 26⟧

Lời giải. Hãy lấy đường kính của đường tròn của chúng ta là 1 và biểu thị bằng φ góc CA₀O, trong đó O là tâm của đường tròn. Khi đó, rõ ràng là (hình 5),
A₀C=cos φ,
A₁C=|sin (φ+π/4)|,
A₂C=|sin (φ-π/4)|.

Hãy xem xét ba trường hợp.

1. -π/4<φ<π/4. Sau đó
A₀M=sin (φ+π/4)−sin (φ−π/4)−cos φ=√2cos φ−cos φ=(\sqrt{2}-1)cos φ.

Do đó, phần tương ứng của quỹ tích sẽ là một cung tròn có đường kính √2−1, đi qua điểm A₀ và đối xứng với tia A₀O (hình 5). Vì góc φ chạy qua khoảng [−π/4; π/4] dài π/2 (chứ không phải π như trên), chúng ta thấy rằng cung này bằng hình bán nguyệt có đường kính √2−1 (tại hình 5 nó được tô sáng màu đỏ).

2. π/4<φ<π/2. Sau đó
A₀M=sin (φ+π/4)+sin (φ−π/4)−cos φ=√2sin φ−cos φ=√3(√2/3sin φ−√1/3cos φ)=√3cos (φ+δ),
trong đó δ=arccos(−√1/3). Như vậy, phần quỹ tích tương ứng với giá trị φ này sẽ là một cung tròn có đường kính √3, đi qua điểm A₀ và đối xứng với tia A₀O.

Trận chung kết đáp số đến bài toán 1 được mô tả trên hình 7.

Bài tập 2. Cho một đa giác A₀A₁A₂......Aₙ, nội tiếp đường tròn c. Đối với một điểm C tùy ý của đường tròn c, chúng ta đánh dấu trên tia A₀C một điểm M sao cho
A₀M=|x₀·A₀C+x₁·A₁C+...+xₙ·AₙC|,
trong đó x₀, x₁,..., xₙ là một số số.
Tìm tập hợp mà điểm M mô tả là C chạy qua đường tròn c.

Bài tập 3 (đây là bài tập M853 từ “Bài toán Kvant, xem «Kvant», 1984, số 3). Hình vuông ABCD lành quanh tâm cố định của nó. Tìm tập hợp mô tả trung điểm của đoạn PQ, trong đó P là đáy của đường vuông góc vẽ từ điểm D đến đường thẳng cố định l, và Q là trung điểm của cạnh AB.
