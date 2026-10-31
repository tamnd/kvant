---
id: 1981-7-hlobyistov-ob-oshibkah-svyazannyih-s-ponyatiem-kornya-iz-chisla-v-sbornike-zadach-l-v-kovantsovoy-i-i-g-malyisheva-c00657ae
issue: kvant_1981_7
year: 1981
number: "7"
title: '[Về các lỗi liên quan đến khái niệm căn số, trong bộ sưu tập bài toán của L. V. Kovantsova và I. G. Malyshev]'
authors:
  - Хлобыстов В.
rubric: smes
page_first: 36
page_last: 36
page_labels: "34"
tag: 0VW8
lang: vi
source: kvant_digital
extraction: vision
content_sha256: ba777d34d4763db3ff47613c119d757a40864e7f65efd99796e7183a3583eac5
prompt_sha256: draft-1
translated_from: content/ru/1981/07/articles/10_hlobyistov-ob-oshibkah-svyazannyih-s-ponyatiem-kornya-iz-chisla-v-sbornike-zadach-l-v-kovantsovoy-i-i-g-malyisheva-c00657ae.md
source_content_sha256: d113138dc17144c62c82846204751a92317f397678c71df80acaeec6351795fd
translation_model: draft
translation_run: vi-draft-2026-10-31
translation_quality: draft
---

⟦folio 34⟧

nhưng từ từ dọc theo mặt phẳng nghiêng (chúng ta coi khối lượng của ma trận nhỏ hơn nhiều so với khối lượng của xe). Chúng ta sẽ giả sử rằng quá trình chuyển từ mặt ngang sang mặt phẳng nghiêng là rất êm và thời gian chuyển động của xe dọc theo mặt tròn nhỏ hơn nhiều so với chu kỳ dao động của ma trận, do đó gần như ngay lập tức điểm treo của ma trận bắt đầu di chuyển lên trên mặt phẳng nghiêng với tốc độ ban đầu $v_0$ và gia tốc bằng giá trị tuyệt đối $b = g \sin \alpha$ và hướng đi xuống dọc theo mặt phẳng nghiêng. So với xe, ma trận lúc đầu có tốc độ $v_0(1 - \cos \alpha)$; vectơ vận tốc tương đối vuông góc (chúng ta giả sử rằng thành phần song song của vận tốc bị loại bỏ). Gia tốc trọng trường mới là $|\vec{g} - \vec{b}| = g \cos \alpha$. Dễ thấy, các phương trình đẳng thế của năng lượng song song với mặt phẳng nghiêng.

Góc tối đa $\phi'_0$ của độ lệch ma trận so với vị trí mới bằng

$$\frac{m(v_0(1 - \cos \alpha))^2}{2} + mgl \cos \alpha \cdot (1 - \cos \alpha) = mg \cos \alpha \cdot l(1 - \cos \phi'_0),$$

Ở đâu

$$\cos \phi'_0 = \cos \alpha - \frac{v_0^2}{2gl \cos \alpha} (1 - \cos \alpha)^2 = \cos \alpha - \frac{v_0^2 2 \sin^2 \frac{\alpha}{2}}{gl \cos \alpha},$$

$$\phi'_0 = \arccos \left( \cos \alpha - \frac{2v_0^2 \sin^2 \frac{\alpha}{2}}{gl \cos \alpha} \right).$$

S. Krotov

Một vài năm trước, «Kvant» đã xuất bản một ghi chú “$0,5\sqrt{4}$ bằng bao nhiêu?” (1976, số 11), đã kiểm tra các lỗi liên quan đến việc xác định căn của một số. Trong toán học, định nghĩa này được đáp ứng một cách rõ ràng: “Căn gốc của phương trình $x^n = a$, trong đó $n$ là một số tự nhiên, được gọi là căn bậc $n$ bậc $u_3 a$” (“Đại số 8”, 1980, đoạn 24). Người nộp đơn thường quên từ “trong đó $n$ là số tự nhiên”. Vì vậy, nếu phương trình chứa $\sqrt{a}$, thì trong các câu trả lời được đề xuất, bạn có thể tìm thấy các số như 0,5, -3, v.v.

Thật không may, loại lỗi này không chỉ xảy ra trong câu trả lời của người nộp đơn. Chúng ta hãy xem hai ví dụ từ cuốn sách của L.V. Kovantsov và I.G. Malyshev “Bộ sưu tập bài toán về toán học” (Kyiv, “Vishsha Shkola”, 1980).

Chúng ta. 101 cho các bất đẳng thức “lời giải” sau đây

$$\log x \sqrt{x} > 10x^4. \tag{1}$$

“Hãy viết bất đẳng thức dưới dạng

$$\frac{1}{x^{\lg x}} > 10x^4. \tag{2}$$

Bây giờ thật tốt khi thấy rằng phạm vi giá trị được chấp nhận là $x > 0$, $x \neq 1$. Hãy tiếp tục

cả hai vế của bất đẳng thức dựa trên cơ số 10 (dấu bất đẳng thức sẽ giữ nguyên):

$$\frac{1}{\lg x} \cdot \lg x > 1 + 4 \lg x \Leftrightarrow \Leftrightarrow \lg x < 0 \Rightarrow 0 < x < 1.$$

Đáp số. $X = ]0; 1[$

Đáp số không đúng, vì với $x \in ]0; 1[$ số $\lg x$ (số mũ gốc trong (1)!) không phải là số tự nhiên. Sai lầm ở đâu? đáp số trong sách là đáp số đúng cho bất đẳng thức (2), nhưng bất đẳng thức (1) và (2) không bằng nhau. Đúng, tập $\{10^n\} (n \in \mathbb{N})$ là vùng chứa các giá trị chấp nhận được của bất đẳng thức (1), chúng bằng nhau. Khi tính đến điều này, chúng tôi nhận được đáp số: $\emptyset$.

Ở trang 97 đáp số về hệ phương trình

$$\begin{cases} x^2 + xy + y^2 = a^2, \\ \log_x \sqrt{a} + \log_y \sqrt{b} = \frac{a}{\sqrt{3}} \end{cases}$$

được viết là “Tại $a > 0$, $b > 0$, $a, b \neq 1$:

$$\left( \frac{a}{\sqrt{3}} \frac{a}{\sqrt{3}} \right),$$

điều đó cũng rất, rất sai lầm.

Sự thiếu chính xác tương tự về cơ bản có trong lời giải ví dụ số 153 và số 183.

V. Khlobistov

Sửa đổi

Ở «Kvant» số 6 trong nhiệm vụ «Kvant» có những điểm không chính xác. Trong bài tập **M686** phải có $[\sqrt{\sqrt{x}}]$ ở vế trái của phương trình. Trong bài toán **M688** tổng $a_1 + a_2 + \dots + a_n$ là số chẵn. Thời hạn gửi lời giải trong số bài toán này được kéo dài đến ngày 1 tháng 10 năm 1981.
