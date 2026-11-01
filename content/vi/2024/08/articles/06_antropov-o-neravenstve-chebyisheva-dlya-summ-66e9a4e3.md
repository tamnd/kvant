---
id: 2024-8-antropov-o-neravenstve-chebyisheva-dlya-summ-66e9a4e3
issue: kvant_2024_8
year: 2024
number: "8"
title: Về bất đẳng thức tổng Chebyshev
authors:
  - Антропов А. В.
rubric: zadachnik-kvanta
rubric_sub: Задачник «Кванта»
page_first: 31
page_last: 34
page_labels: "29"
lang: vi
source: kvant_digital
extraction: vision
content_sha256: 184f05e8fdce18185f3733acd9d0a5e9a37c1000c1ade3365f3949fe6e9c1011
prompt_sha256: draft-1
translated_from: content/ru/2024/08/articles/06_antropov-o-neravenstve-chebyisheva-dlya-summ-66e9a4e3.md
source_content_sha256: cba10298d060b51d77d8db37eda3842c379cca16dfc4cd69e02d17d440c497ef
translation_model: draft
translation_run: vi-draft-gaps-2026-11-02
translation_quality: draft
---

⟦folio 29⟧

---
running_head:
folio:
---

Về sự bất bình đẳng
Chebyshev
cho số tiền
A. ANTROPOV

TRONG BÀI VIẾT NÀY CHÚNG TÔI SẼ NHỚ
về bất đẳng thức đáng chú ý của Chebyshev, chúng ta hãy nói về các biến thể và cách giải thích khác nhau của nó, đồng thời đưa ra lời giải bài toán M2797 “Bài toán lượng tử” (chính xác hơn, chúng ta hãy lưu ý rằng về cơ bản bất đẳng thức đưa ra trong bài toán là một trường hợp đặc biệt của bất đẳng thức Chebyshev).

Bất đẳng thức Chebyshev thứ nhất về tổng.
Đặt các số không âm đã cho $p_1, p_2, \dots, p_n$ sao cho $p_1 + p_2 + \dots + p_n = 1$ và hai bộ số thực có thứ tự $a_1 \leq a_2 \leq \dots \leq a_n$, $b_1 \leq b_2 \leq \dots \leq b_n$. Sau đó
$$\left( p_1 a_1 + p_2 a_2 + \dots + p_n a_n \right) \left( p_1 b_1 + p_2 b_2 + \dots + p_n b_n \right) \leq
\leq p_1 a_1 b_1 + p_2 a_2 b_2 + \dots + p_n a_n b_n. \tag{1}$$

"Cái gì?! Đây không phải là bất đẳng thức của Chebyshev!" – người đọc có thể tận dụng ngoại lệ. Thật vậy, trong dân gian tối ưu, bất đẳng thức sau đây thường được gọi là bất đẳng thức Chebyshev về tổng.

Bất đẳng thức Chebyshev thứ hai về tổng.
Đối với các bộ đã đặt hàng $a_1 \leq a_2 \leq \dots \leq a_n$, $b_1 \leq b_2 \leq \dots \leq b_n$ hài lòng
$$\frac{a_1 + a_2 + \dots + a_n}{n} \cdot \frac{b_1 + b_2 + \dots + b_n}{n} \leq
\leq \frac{a_1 b_1 + a_2 b_2 + \dots a_n b_n}{n}. \tag{2}$$

Dễ dàng nhận thấy bất đẳng thức trọng số (1) là dạng tổng quát hóa của bất đẳng thức (2): chỉ cần đặt $p_1 = p_2 = p_3 = \dots = p_n = \frac{1}{n}$ là đủ.

Mặt khác, bài tập sau đây cho thấy rằng ở một khía cạnh nào đó, bất đẳng thức (1) có thể được giảm xuống thành bất đẳng thức (2).

Bài tập 1. Rút ra bất đẳng thức (1) từ bất đẳng thức (2) nếu $p_1, p_2, \dots, p_n$ là hữu tỉ.

Gợi ý. Đặt $p_i = m_i / m$, $i = 1, 2, \dots, n$. Thư giãn cho bộ bất đẳng thức (2)
$$a_1 = a_1 = \dots = a_1 \leq a_2 = a_2 \leq \dots \leq a_n = a_n,$$
trong đó có $m_1$ bản sao của $a_1$, $m_2$ bản sao của $a_2$, v.v.

Trước khi chứng minh bất đẳng thức (1), chúng ta sẽ trình bày cách sử dụng nó cho lời giải bài toán M2797.

Đầu tiên, chúng ta hãy đưa ra một nhận xét chung.

Bình luận. Giả sử trong bất đẳng thức (1) tất cả đều là $a_i \geq 0$ và $b_i \geq 0$. Khi đó, nó vẫn đúng nếu trong điều kiện chúng ta thay thế đẳng thức $p_1 + p_2 + \dots + p_n = 1$ bằng bất đẳng thức $p_1 + p_2 + \dots + p_n \leq 1$.

Thật vậy, đặt $p = p_1 + p_2 + \dots + p_n \geq 0$ (trong trường hợp $p_1 + p_2 + \dots + p_n = 0$ tất cả $p_i$ đều bằng 0 và bất đẳng thức là hiển nhiên). Chúng ta đặt $q_i = \frac{p_i}{p}$, sao cho $p_1 + p_2 + \dots + p_n = 1$, viết bất đẳng thức (1) với trọng số $q_i$ và nhận được
$$\frac{p_1 a_1 + p_2 a_2 + \dots + p_n a_n}{p} \cdot \frac{p_1 b_1 + p_2 b_2 + \dots + p_n b_n}{p} \leq
\leq \frac{p_1 a_1 b_1 + p_2 a_2 b_2 + \dots + p_n a_n b_n}{p}.$$

Vì tổng $p_i a_i b_i$ không âm và $p \leq 1$, nhân với $p^2$ sẽ được kết quả cần có:
$$\left( p_1 a_1 + p_2 a_2 + \dots + p_n a_n \right) \left( p_1 b_1 + p_2 b_2 + \dots + p_n b_n \right) \leq
\leq p \left( p_1 a_1 b_1 + p_2 a_2 b_2 + \dots + p_n a_n b_n \right) \leq
\leq p_1 a_1 b_1 + p_2 a_2 b_2 + \dots + p_n a_n b_n.$$

Trường hợp $p \leq 1$ cũng có thể giảm xuống $p = 1$ bằng cách sàng lọc – ​​bằng cách đưa vào các biến bổ sung $a_0 = b_0 = 0$ và trọng số bổ sung $p_0 = 1 - \left( p_1 + \dots + p_n \right)$.

Bây giờ hãy đặt $p_i = \frac{1}{i(i+1)}$. Khi được trích xuất, $p_1 + p_2 + \dots + p_n < 1$ cho bất kỳ $n$ nào (thực sự là $p_i = \frac{1}{i} - \frac{1}{i+1}$ và do đó,
$$p_1 + p_2 + \dots + p_n = \left( 1 - \frac{1}{2} \right) + \left( \frac{1}{2} - \frac{1}{3} \right) + \dots + \left( \frac{1}{n} - \frac{1}{n+1} \right) = 1 - \frac{1}{n+1}).$$

Sau đó, nhờ sự thay thế ở trên,
$$\left( p_1 a_1 + p_2 a_2 + \dots + p_n a_n \right) \left( p_1 b_1 + p_2 b_2 + \dots + p_n b_n \right) \leq
\leq p_1 a_1 b_1 + p_2 a_2 b_2 + \dots + p_n a_n b_n.$$

Đây chính là sự bất bình đẳng mà chúng ta cần. Vấn đề M2797 đã được giải quyết.

⟦folio none⟧

---
running_head:
folio:
---

lớn hơn hoặc bằng tích của kỳ vọng toán học của họ:
$$\mathbb{E}f \cdot \mathbb{E}g \leq \mathbb{E}(fg).$$
(1")

Bản chất của bất đẳng thức này sẽ dễ hiểu hơn nếu bạn biết mối tương quan của hai biến ngẫu nhiên là gì. Tương quan lấy các giá trị từ $[-1; 1]$ và đo lường mức độ phụ thuộc của các đại lượng, đặc biệt, nếu các đại lượng độc lập thì mối tương quan của chúng bằng 0 và đối với các đại lượng phụ thuộc nhiều thì tương quan gần bằng 1.

Mối tương quan chính thức được định nghĩa như sau. Đối với các giá trị $f$ và $g$, hệ số cov($f,g$) được đưa ra - đây là kỳ vọng toán học của tích độ lệch của các giá trị $f$ và $g$ so với giá trị trung bình của chúng. Và mối tương quan giữa các giá trị $f$ và $g$ được giả định là bằng nhau
$$\frac{\text{cov}(f,g)}{\sqrt{\text{cov}(f,f)} \cdot \sqrt{\text{cov}(g,g)}}.$$
Bằng cách tạm thời đưa ra các ký hiệu $M_f = \mathbb{E}f$ và $M_g = \mathbb{E}g$, chúng ta có thể viết
$$\text{cov}(f,g) = \mathbb{E}\left((f - M_f)(g - M_g)\right).$$
Chúng ta hãy tự hỏi: khi nào biểu thức $(f - M_f)(g - M_g)$ dương? Đáp số là rõ ràng: khi cả hai hàm $f$ và $g$ đồng thời lớn hơn giá trị trung bình của chúng hoặc khi cả hai đều đồng thời nhỏ hơn. Nói một cách không chính thức, cov($f,g$) đo lường mức độ tương tự của một hàm.

Hãy quay lại bất đẳng thức (1"). Hóa ra hiệu giữa bên phải và bên trái bằng

cov($f,g$). Thật sự,
cov($f,g$) = $\mathbb{E}\left((f - M_f)(g - M_g)\right) =
= \mathbb{E}\left(fg - M_fg - M_gf + M_fM_g\right) =
= \mathbb{E}(fg) - M_f\mathbb{E}g - M_g\mathbb{E}f + M_fM_g =
= \mathbb{E}(fg) - \mathbb{E}f \cdot \mathbb{E}g$,

trong đó đẳng thức áp chót tuân theo tính tuyến tính của kỳ vọng toán học và đẳng thức cuối cùng tuân theo các định nghĩa của $M_f$ và $M_g$.

Hóa ra bất đẳng thức Chebyshev (1') nhìn chung phản ánh một thông điệp logic về sự giống nhau của các hàm đơn điệu.

Để kết luận, đối với những độc giả quen thuộc với số nguyên, chúng tôi trình bày một phiên bản liên tục của bất đẳng thức Chebyshev. Trong trường hợp này, bất đẳng thức có cùng ý nghĩa về mặt lý thuyết xác suất và phản ánh luận điểm không chính thức giống nhau về sự giống nhau của các hàm đơn điệu.

Bất đẳng thức Chebyshev thứ ba (đối với hàm đơn điệu). Đặt $f(x)u g(x)$ là hai hàm không giảm (hoặc hai hàm không tăng) xác định trên khoảng $[a; b]$. Sau đó
$$\int_a^b f(x)dx \cdot \int_a^b g(x)dx \leq \frac{1}{b-a} \int_a^b f(x)g(x)dx.$$
Bài tập 3*.
a) Suy ra các bất đẳng thức Chebyshev với tổng từ bất đẳng thức tích phân Chebyshev.
b) Suy ra (bằng cách chuyển đến giới hạn từ tổng nguyên sang tích phân) từ bất đẳng thức Chebyshev đối với tổng bất đẳng thức tích phân.

(Để bắt đầu, xem trang 13)

tuyên bố rằng đây là cách màu vàng xuất hiện. Vậy tại sao lại tranh cãi với anh ta?>

Tôi đã bối rối. Tôi không biết phải nói gì. Cuối cùng, tôi trả lời: "Tôi đã nghiên cứu về ánh sáng cả đời. Và tôi tin rằng bằng cách trộn màu đỏ và trắng thì không thể có được màu vàng - bạn chỉ có thể có được màu hồng."

Vì vậy, tôi đến cửa hàng kim khí, mua một ít sơn và mang về nhà hàng. Người họa sĩ từ tầng hai đi xuống, người chủ cũng tới xem. Tôi đặt những lon màu đỏ lên một chiếc ghế cũ và người họa sĩ bắt đầu trộn sơn. Anh ấy lấy sơn đỏ, thêm màu trắng - đối với tôi, dường như màu đó vẫn là màu hồng - anh ấy trộn thêm một chút sơn. Sau đó, anh ấy lẩm bẩm điều gì đó khi nhập liệu: “Tôi thường dùng một ống sơn đỏ nhỏ để tăng hiệu ứng - sau đó nó sẽ chuyển sang màu vàng.”

- MỘT! - tôi nói. - Chắc chắn! Nếu bạn thêm màu vàng, bạn sẽ có màu vàng, nhưng không có nó thì sẽ không có tác dụng gì.

Người họa sĩ quay lại sơn căn phòng.

Chủ quán nói: “Anh chàng này dám cả gan tranh luận với một người cả đời nghiên cứu về ánh sáng!”

Từ cuốn sách “Bạn chắc chắn là một trò đùa, Master Feynman!”

⟦folio none⟧

---
running_head:
folio:
---

Tìm thông lượng [tức là đạo hàm] và nửa
sống nó bằng không.
Isaac Newton
...[phái sinh] diễn đạt sự phủ định đó
điểm của con đường mà cơ thể di chuyển
vượt quá khoảng cách họ sẽ đi du lịch
do chuyển động trước đó của anh ấy.
Leonard Euler
Tất cả những người yêu thích phân tích [toán học] với
sẽ hài lòng khi thấy rằng cơ chế
đang trở thành một nhánh phân tích mới...
Joseph Louis Lagrange
Đừng làm phiền tôi với môn toán của bạn
Coy: đạo hàm là tốc độ!
William Thomson (Kelvin)

Newton đặt ra một câu hỏi tổng quát: tốc độ của một vật tự do thay đổi như thế nào dưới tác dụng của một lực tùy ý?... bài toán... Điều này đòi hỏi một ứng dụng toán học mới-
paratha được tạo ra đặc biệt cho mục đích này
Newton...

Albert Einstein
...quá trình phức tạp để tìm một giá trị tùy ý còn được gọi là vi phân. ...Khi bạn trở nên quen hơn với những từ mới, ý tưởng đó sẽ trở nên rõ ràng hơn đối với bạn.

Richard Feynman
