---
id: 1977-11-krivosheev-kak-reshit-kubicheskoe-uravnenie-5bc68b51
issue: kvant_1977_11
year: 1977
number: "11"
title: Làm thế nào để giải một phương trình bậc ba?
authors:
  - Кривошеев В.
rubric: smes
page_first: 54
page_last: 54
page_labels: "52"
tag: LIYK
lang: vi
source: kvant_digital
extraction: vision
content_sha256: 5b8877bd59d4dbcbb25f924b5fddbaba16a4e0657f022600f0ccaa722fa3af85
prompt_sha256: draft-1
translated_from: content/ru/1977/11/articles/14_krivosheev-kak-reshit-kubicheskoe-uravnenie-5bc68b51.md
source_content_sha256: 8bf4a37c530b83e7c10614a9ed51941b74b7f9d38e23584c49fea5bdca118156
translation_model: draft
translation_run: vi-draft-2026-10-31
translation_quality: draft
---

⟦folio 52⟧

F444. Một hộp nặng khối lượng M lăn xuống các con lăn tạo thành một mặt phẳng nghiêng (Hình 6). Khoảng cách giữa các con lăn là l, bán kính của chúng là r và khối lượng của chúng là m. Góc của mặt phẳng với đường chân trời bằng α. Tìm tốc độ chuyển động của hộp nếu biết nó được xây dựng. Giả sử các con lăn rỗng và độ dày thành của chúng là d << r.

Cơm. 6.

Khi hộp Wizz di chuyển dọc theo mặt phẳng nghiêng bên dưới nó, các con lăn bắt đầu di chuyển và bắt đầu giãn ra. Việc hộp chuyển động với tốc độ không đổi có nghĩa là có một lực kéo $\vec{F} = -M\vec{g} \sin \alpha$ tác dụng lên hộp từ các con lăn.

Giả sử rằng hộp chuyển động với tốc độ $\vec{v}$ và chiều dài của nó đủ lớn để nó có thời gian quay các con lăn đến tốc độ tuyến tính $u = |\vec{v}|$. Con lăn giãn ra do ma sát mù $\vec{f}$ tác động lên nó từ thành bên của hộp cho đến khi tốc độ tuyến tính của nó bằng $|\vec{v}|$. Sau đó, ma sát giữa con lăn này và hộp biến mất.

Từ các thông điệp đối xứng, rõ ràng rằng tác dụng của lực ma sát lên con lăn bằng tác dụng của cùng một giá trị tuyệt đối của lực $|\vec{f}|$ tác dụng lên con lăn tại bất kỳ điểm nào tiếp tuyến với vành con lăn và “quay” cùng với con lăn. Vì lực tác dụng lên con lăn không đổi trong giá trị tuyệt đối nên tốc độ quay tuyến tính của con lăn dưới tác dụng của lực $|\vec{f}|$ thay đổi theo thời gian theo quy luật tuyến tính. Để Cuộn quay theo thời gian $\tau$ đến tốc độ tuyến tính $u = |\vec{v}|$. Lực $\vec{f}$ thực hiện công $|\vec{f}||\vec{v}| \tau/2$ (tốc độ trung bình của Rolika là $|\vec{v}|/2$, gọi quãng đường đi qua điểm tác dụng của lực là $|\vec{v}| \tau/2$). Công này bằng động năng của Rolika:

$$\frac{|\vec{f}| |\vec{v}| \tau}{2} = \frac{m |\vec{v}|^2}{2}.$$

Vì Con lăn thư giãn đến tốc độ tuyến tính $|\vec{v}|$ trong thời gian $\tau$, nên có $N = |\vec{v}| \tau/l$ Con lăn bên dưới hộp trong toàn bộ thời gian, tốc độ tuyến tính của nó nhỏ hơn $|\vec{v}|$. Lực ma sát mà các Con lăn này tác dụng lên hộp bằng

$$|\vec{F}| = N |\vec{f}| = \frac{|\vec{v}| \tau}{l} |\vec{f}| = M |\vec{g}| \sin \alpha.$$

Từ (1) ta có: $|\vec{v}| \tau |\vec{f}| = m |\vec{v}|^2$. Thay biểu thức này vào (2), ta được:

$$\frac{m |\vec{v}|^2}{l} = M |\vec{g}| \sin \alpha.$$

Từ đây

$$|\vec{v}| = \sqrt{\frac{M}{m} |\vec{g}| l \sin \alpha}$$

T. Petrova

Làm thế nào để giải một phương trình bậc ba?

Nhiều bạn đã đọc về câu chuyện kịch tính xung quanh việc giải phương trình bậc ba (xem «Kvant», 1976, số 9). Các ký hiệu đại số hiện đại ngày nay cho phép ngay cả một học sinh cũng có thể giải quyết được nhiệm vụ này, nhưng vào thế kỷ 17, ngay cả các nhà toán học hàng đầu cũng không thể làm được điều này. Đây là phương pháp tao nhã được cung cấp bởi độc giả V. Krivo Sheev (Cherkassy) của chúng tôi.

Người ta biết rằng mọi phương trình bậc ba đều có thể rút gọn về dạng

$$y^3 + by + c = 0.$$

Tình cờ tôi phát hiện ra những thay thế sau đây cho lời giải của anh ấy.

a) Đặt $b > 0$. Hãy đặt

$$y = \sqrt{\frac{b}{3}} \left( z - \frac{1}{z} \right),$$

chúng ta nhận được (dễ kiểm tra) phương trình

$$\frac{b}{3} \sqrt{\frac{b}{3}} \left( z^3 - \frac{1}{z^3} \right) + c = 0.$$

Tiếp theo, chúng ta đặt $z^3 = t$, sau khi rút gọn về mẫu số chung, chúng ta thu được phương trình bậc hai tương đối $t$.

6) Hãy để $b < 0$. Hãy đặt

$$y = \sqrt{\frac{b}{3}} \left( z + \frac{1}{z} \right)$$

và tương tự hơn nữa với điểm a).
