---
id: 1990-6-tabachnikov-mnogochlenyi-naimenee-uklonyayuschiesya-ot-nulya-637c077e
issue: kvant_1990_6
year: 1990
number: "6"
title: Đa thức lệch ít nhất so với 0
authors:
  - Табачников С. Л.
rubric: osnovnye-stati
page_first: 25
page_last: 26
page_labels: 23-24
lang: vi
source: kvant_digital
extraction: vision
content_sha256: 6b519ff7ade346bc8924a53eca002ba37404846528e8d3ec92c50da747a21b1a
prompt_sha256: draft-1
translated_from: content/ru/1990/06/articles/04_tabachnikov-mnogochlenyi-naimenee-uklonyayuschiesya-ot-nulya-637c077e.md
source_content_sha256: 66530a17b2f0abecdbe2c5cfca401e9fd2fa866d9b9895e016852f4565773ced
translation_model: draft
translation_run: vi-draft-gaps-2026-11-05
translation_quality: draft
---

⟦folio 23⟧

---
running_head:
folio:
---

POLYNOMILES, ÍT NHẤT
TRÁNH TỪ SỐ 0

Ứng viên Khoa học Vật lý và Toán học
S. TAVACHNIKOV

Tôi sẽ kể cho bạn nghe về một trong những bài toán đẹp nhất về đa thức - bài toán của Chebyshev về đa thức, ít sai lệch nhất so với 0. Chúng ta hãy sửa một số đoạn của trục số, chẳng hạn như đoạn [−2; 2] (khi tôi nói “giả sử,” tôi đang nói dối một chút - chính phân đoạn này mới thu được các công thức đơn giản nhất). Cho phép

$$f(x) = x^n + a_1 x^{n-1} + a_2 x^{n-2} + \dots + a_n$$

là đa thức rút gọn $n$ bậc (điều này có nghĩa là hệ số cao nhất của nó là 1). Tập hợp các giá trị $f(x)$ trên khoảng [−2; 2] — đoạn [m; M], trong đó $m$ là mức tối thiểu và $M$ là mức tối đa của đa thức. Độ lệch của đa thức so với 0 được gọi là |m|, |M| được tính toán nhiều nhất. Nếu độ lệch của đa thức so với 0 là $c$ thì đồ thị của nó nằm trong trường |y| $c$ và không nằm trong bất kỳ dải hẹp nào với đường giữa Ox.

Nhiệm vụ là tìm ra một đa thức rút gọn như vậy ở bậc $n$th $f_n(x)$, độ lệch của nó so với 0 sẽ là tối thiểu (điều kiện là hệ số dẫn đầu bằng 1 không cho phép chúng ta tạo một biểu đồ tùy ý gần với hoành độ). Thoạt nhìn, bài toán của Chebyshev ít được những người đam mê quan tâm: để tìm kiếm độ lệch so với 0, bạn cần tính các phương trình tùy ý và giải các phương trình bậc $n$... Điều đáng ngạc nhiên hơn là bài toán này được giải về mặt hình học - và hầu như không cần tính toán!

Trước hết chúng ta hãy xem xét trường hợp cấp độ nhỏ mà không cần đến sự khôn ngoan của cung tên. Ở $n=1$ lò chỉ đơn giản là một hàm tuyến tính của $f(x)=x+a$. Tập giá trị của nó là đoạn [−2+a; 2+a] có độ dài 4. Do đó, độ lệch nhỏ nhất so với 0 là 2 và $f_1(x)=x$.

Đối với Nenatny, trường hợp $n=2$ (trường hợp tam thức bậc hai) khó hơn. Đồ thị của đa thức bậc hai là một đoạn của parabol; và rõ ràng là parabol nằm ở vị trí thuận lợi nhất như trong hình 1. Trong trường hợp này, $f(x)=x^2-2$, và độ lệch so với 0 lại hóa ra bằng 2.

Bài tập 1. Kiểm tra trực giác tính toán: Chứng minh độ lệch so với 0 của tam thức bình phương không nhỏ hơn 2.

Tôi có thể đề nghị bạn kiểm tra trường hợp đa thức bậc ba và đảm bảo rằng trong trường hợp này độ lệch so với 0 bằng 2. bài toán này cũng cho phép lời giải “trên trán”. Nhưng tôi nóng lòng muốn nói cho bạn biết chung lời giải.

Giả sử rằng chúng ta đã tìm được một đa thức rút gọn bậc $n$th $f_n(x)$ sao cho đồ thị của nó nằm trong dải |y| $c$ và chứa $n+1$ điểm ranh giới của nó: điểm ngoài cùng bên phải nằm trên dòng $y=c$, điểm tiếp theo trên dòng $y=-c$, điểm tiếp theo lại nằm trên dòng $y=c$, v.v. ($n=5$ trên hình 2).

Định lý. Độ lệch so với 0 của bất kỳ đa thức rút gọn bậc $n$ nào khác $f_n(x)$ đều lớn hơn $c$.

Đây là một bằng chứng hình học chứng minh cột bài toán của Chebyshev. Hãy để $g(x)$ —

⟦folio 24⟧

---
running_head:
folio:
---

một đa thức rút gọn khác có bậc $n$, có độ lệch so với 0 không vượt quá $c$. Khi đó đồ thị của nó cũng nằm trong dải $|y| \leq c$. Chia dải các đoạn thẳng đứng này thành các hình chữ nhật $n$ như trong hình 3. Đường cong màu xanh lam - đồ thị $f_n(x)$ - nối các đỉnh đối diện của mỗi hình chữ nhật theo đường chéo. Do đó, đường cong màu đỏ - đồ thị $g(x)$ - giao với đường màu xanh lam bên trong mỗi đường cong đó. Do đó, phương trình $f_n(x) - g(x) = 0$ có ít nhất $n$ nghiệm. Nhưng bậc của đa thức $f_n(x) - g(x)$ không lớn hơn $(n-1)$. Nếu một đa thức như vậy vẫn có nghiệm $n$ thì đương nhiên nó cũng bằng 0, tức là $g(x) = f_n(x)$. Định lý đã được chứng minh.

Hãy xem xét bằng chứng này. Hầu như không có gì, chúng tôi nhận được khá nhiều: mặc dù chúng tôi chưa biết giá trị của $c$, nhưng chúng tôi đã biết rằng chỉ có một đa thức ở một mức nhất định ít lệch nhất so với 0 và chúng tôi có thể tưởng tượng đồ thị của nó trông như thế nào.

Bài tập 2. Chứng minh trên có một khoảng trống (đây là cái giá phải trả cho cái đẹp). Điều gì sẽ xảy ra nếu đồ thị của đa thức $f_n(x)$ và $g(x)$ chạm vào (hình 4)?

Gợi ý: Nhắc lại định nghĩa nghiệm bội của một đa thức.

Vì vậy, chúng ta cần trình bày một đa thức $f_n(x)$ có đồ thị hoạt động như trong hình 2. hình này không thể không nhắc nhở bạn về các hàm lượng giác. Và thực sự, bây giờ họ đang phát huy tác dụng!

Cách dễ nhất là lấy $f_n$ một cái gì đó giống như hàm cos $n\alpha$. Nhưng than ôi: cosin không phải là đa thức. Người sau đây đến giải cứu.

Bổ đề. Hàm 2 cos $n\alpha$ được biểu thị dưới dạng đa thức rút gọn bậc $n$ trong hàm 2 cos $\alpha$:

$$2 \cos n\alpha = f_n(2 \cos \alpha).$$

Ví dụ,

$$2 \cos 2\alpha = 4 \cos^2\alpha - 2 = (2 \cos \alpha)^2 - 2,$$

tức là $f_2(x) = x^2 - 2$;

$$2 \cos 3\alpha = 8 \cos^3\alpha - 6 \cos \alpha = (2 \cos \alpha)^3 - 3(2 \cos \alpha),$$

tức là $f_3(x) = x^3 - 3x.$

Việc chứng minh bổ đề được thực hiện bằng quy nạp. Hãy chứng minh phát biểu của cô ấy cho các số $n-1$ và $n$:

$$2 \cos(n-1)\alpha = f_{n-1}(2 \cos \alpha),$$

$$2 \cos n\alpha = f_n(2 \cos \alpha).$$

Từ công thức

$$\cos(n+1)\alpha + \cos(n-1)\alpha = 2 \cos \alpha \cos n\alpha$$

nó theo sau đó

$$2 \cos(n+1)\alpha = (2 \cos \alpha)(2 \cos n\alpha) - 2 \cos(n-1)\alpha = (2 \cos \alpha)f_n(2 \cos \alpha) - f_{n-1}(2 \cos \alpha).$$

Có nghĩa,

$$f_{n+1}(x) = xf_n(x) - f_{n-1}(x).$$

Bổ đề đã được chứng minh, đồng thời thu được công thức hồi quy để tính đa thức $f_n(x)$.

(Về phần kết, xem trang 27).
