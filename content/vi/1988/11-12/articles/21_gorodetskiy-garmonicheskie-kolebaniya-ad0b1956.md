---
id: 1988-11-12-gorodetskiy-garmonicheskie-kolebaniya-ad0b1956
issue: kvant_1988_11-12
year: 1988
number: 11-12
title: Dao động điều hòa
authors:
  - Городецкий Е. Е.
rubric: praktikum-abiturienta
rubric_sub: Практикум абитуриента
page_first: 66
page_last: 69
page_labels: 64, 65, 67
tag: CGCS
lang: vi
source: kvant_digital
extraction: vision
content_sha256: c64eb33652b289b46f15c8d00f72f55d09d9a8ff409864244eec57bce21abc47
prompt_sha256: draft-1
translated_from: content/ru/1988/11-12/articles/21_gorodetskiy-garmonicheskie-kolebaniya-ad0b1956.md
source_content_sha256: 8dac022000be44baddba29443b853d8519904fe7a3e140f93170d1b4279e82e7
translation_model: draft
translation_run: vi-draft-2026-10-31
translation_quality: draft
---

⟦folio 64⟧

Dao động điều hòa

Ứng viên Khoa học Vật lý và Toán học
E. E. GORODETSKY

Cơ chế xuất hiện dao động điều hòa tự do trong bất kỳ hệ cơ học nào luôn giống nhau. Sự xuất hiện này nảy sinh nhằm mục đích di chuyển hệ thống ra khỏi vị trí cân bằng ổn định. Bài viết này sẽ chỉ tập trung vào dao động điều hòa. Mặc dù bản chất nảy sinh trong từng trường hợp cụ thể có thể khác nhau nhưng các phương trình chuyển động mô tả các dao động đều giống nhau.

Ý chí bài toán về biến động trông giống như thế này. Cho một hệ nhất định có thể dao động xung quanh vị trí của nó.

naya cân bằng. Phương pháp tạo ra dao động đã được biết, tức là các điều kiện ban đầu đã được xác định. Câu hỏi một: tìm tần số (hoặc chu kỳ) dao động. Câu 2: Tìm biên độ, pha ban đầu của chúng và viết sự phụ thuộc của giá trị dao động vào thời gian. Câu hỏi thứ ba: tìm sau thời gian nào (hoặc phần nào của chu kỳ) đại lượng dao động đạt giá trị cho trước. Đáp số chúng tôi sẽ minh họa những câu hỏi này bằng cách tìm một ví dụ nổi tiếng về ma trận đính kèm. Chúng tôi xây dựng ngược một thuật toán chung lời giải bài toán thuộc loại này.

Bài 1. Cho hệ ở hình 1. Khối lượng vật m, độ cứng của lò xo k. Vật bị dịch chuyển khỏi vị trí cân bằng ở bên phải một lượng x₀ và bị đẩy sang bên trái, tạo cho nó một vận tốc v₀. Tìm tần số, biên độ và pha ban đầu của dao động. Không có ma sát.

Chúng ta hãy viết định luật II Newton cho vật dưới dạng hình chiếu lên trục X:

⟦folio 65⟧

$$F_{\text{упр}} = ma,$$
trong đó $F_{\text{упр}}$ là lực đàn hồi tác dụng lên vật từ lò xo, $a$ là gia tốc của vật. Nếu độ lệch của vật so với vị trí cân bằng tại một thời điểm tùy ý $t$ bằng $x$, thì theo định luật Hooke $F_{\text{упр}} = -kx$. Gia tốc của một vật dọc theo tọa độ tùy ý thứ hai nhất định trong thời gian: $a = x''$. Bây giờ phương trình chuyển động của vật có thể được viết dưới dạng $mx'' + kx = 0$.

Phương trình này, giống như phương trình của bất kỳ dao động nào khác, là tổng của hai số hạng: một trong số chúng bao gồm một hàm thời gian chưa xác định (trong trường hợp này là $x$) và phương trình còn lại - hàm tùy ý thứ hai của thời điểm này ($x''$).

Như đã biết, nghiệm của phương trình như vậy là hàm điều hòa

$$x = x_m \sin(\omega t + \varphi_0).$$

Ở đây $x_m$ là biên độ, $\omega$ là tần số (chính xác hơn là tần số tuần hoàn), $\varphi_0$ là pha ban đầu của dao động. Bằng cách thay trực tiếp lời giải vào phương trình, dễ dàng tìm được tần số dao động:

$$\omega = \sqrt{\frac{k}{m}}.$$

Lưu ý (và điều này rất quan trọng) rằng kết quả đáp số là trường hợp đặc biệt của quy tắc tổng quát. Nó như sau. Nếu thu được phương trình dao động thì bình phương tần số dao động bằng tỉ số của hệ số của hàm chưa biết (trong trường hợp này là $x(t))$ với hệ số của hàm tùy ý thứ hai của hàm này theo thời gian ($x''(t))$.

Còn biên độ $x_m$ và pha ban đầu $\varphi_0$ thì sao? Để xác định các đại lượng này, chúng ta hãy quay lại điều kiện: vật được dịch chuyển $x_0$ sang phải và bị đẩy với tốc độ $v_0$ sang trái. Đây

$$\text{Puc. 1.}$$

chúng ta đang nói về chính xác các dao động được kích thích như thế nào, tức là về các điều kiện ban đầu. Trong các nhiệm vụ khác nhau, chúng có thể được chỉ định theo những cách khác nhau, nhưng ý nghĩa của chúng luôn giống nhau: tại thời điểm ban đầu, các giá trị cụ thể của một số đại lượng được chỉ định. Trong trường hợp của chúng tôi, các giá trị trộn của vật thể và vận tốc của nó (chính xác hơn là hình chiếu của vận tốc lên trục $X$) được đưa ra:

tại $t = 0$ $x = x_0$ và $v = -v_0$.

Vì chúng ta đã biết sự phụ thuộc của việc trộn vào thời gian:

$$x = x_m \sin(\omega t + \varphi_0),$$

không khó để tìm thấy tốc độ:

$$v = x' = x_m \omega \cos(\omega t + \varphi_0).$$

Chúng ta hãy đặt $t = 0$ vào các biểu thức sau:

$$x_0 = x_m \sin \varphi_0,$$

$$-\frac{v_0}{\omega} = x_m \cos \varphi_0.$$

Đây là hai phương trình có hai ẩn số: $x_m$ và $\varphi_0$. Chia một phương trình cho một phương trình khác, ta được

$$tg \varphi_0 = -\frac{x_0 \omega}{v_0},$$

hoặc

$$\varphi_0 = \arctg \left(-\frac{x_0}{v_0} \sqrt{\frac{k}{m}}\right).$$

Bằng cách bình phương cả hai phương trình và cộng chúng, chúng ta tìm được

$$x_m^2 = x_0^2 + \frac{v_0^2}{\omega^2},$$

hoặc

$$x_m = \sqrt{x_0^2 + \frac{mv_0^2}{k}}.$$

Bài 2. Vật (xem bài toán 1), ở vị trí cân bằng, được truyền một vận tốc hướng phải $v_0$. Tìm: a) sau bao lâu thì thế năng của hệ lần đầu tiên lớn hơn động năng ba lần, b) sau thời gian nào thì tốc độ của vật lần đầu tiên biến thành một trường.

a) Khi vật dao động bên ngoài thì hệ có trữ lượng các phương trình thế năng

$$W_p = \frac{kx^2}{2} = \frac{kx_m^2 \sin^2(\omega t + \varphi_0)}{2}$$

và động năng

$$W_k = \frac{mv^2}{2} = \frac{mx_m^2 \omega^2 \cos^2(\omega t + \varphi_0)}{2}.$$

Vào thời điểm mong muốn $t$

⟦folio 67⟧

Ở vị trí cân bằng, độ sâu của vật chìm xuống nước $l_0$ được xác định bằng độ đẳng thức giữa trọng lực $mg$ và lực nổi $F = \rho_B Sl_0 g$ (ở đây $\rho_B$ là mật độ của nước):

$$mg = \rho_B Sl_0 g.$$

Ví dụ, trong quá trình dao động, tại thời điểm độ sâu của vật bằng $l_0 + y$, định luật thứ hai của Newton được viết là:

$$mg - \rho_B S(l_0 + y)g = ma,$$

ở đâu $a = y''$. Trừ phương trình thứ nhất khỏi phương trình thứ hai, chúng ta nhận được

$$- \rho_B Sgy = my''.$$

hoặc

$$y'' + \frac{\rho_B Sg}{m} y = 0.$$

Đây là phương trình dao động đã quen thuộc với bạn. lời giải của nó trông giống như:

$$y = y_m \sin(\omega t + \varphi_0),$$

ở đâu $\omega = \sqrt{\frac{\rho_B Sg}{m}}$.

Để xác định biên độ và pha ban đầu, chúng ta chuyển sang các điều kiện ban đầu:

tại $t = 0$ $y = 0$ và $v = v_0$.

Vì $v = y' = y_m \omega \cos(\omega t + \varphi_0)$, chúng tôi nhận được

$$y_m \sin \varphi_0 = 0$$ và $y_m \omega \cos \varphi_0 = v_0$.

Từ đây

$$\varphi_0 = 0$$ và $y_m = \frac{v_0}{\omega} = v_0 \sqrt{\frac{m}{\rho_B Sg}}$.

Bài toán 5. Phương pháp hình trụ có khí được đóng kín bằng piston có khối lượng $m$ và diện tích tiết diện $S$ (hình 4). Ở trạng thái cân bằng, pít-tông ở độ cao $l$ tính từ đáy bình. Tại một thời điểm nào đó, piston được di chuyển từ vị trí cân bằng xuống dưới một lượng $h_0$ và được thả ra. Xác định tần số, pha ban đầu và biên độ của dao động:

$$\omega = \sqrt{\frac{mg + p_a S}{ml}},$$

$\varphi_0 = \frac{\pi}{2},$ $y_m = h_0$.

Bài toán 6. Tìm tần số dao động của chất lỏng đổ vào ống chữ U (hình 5). Khối lượng chất lỏng $m$, mật độ $\rho$, diện tích mặt cắt ngang của ống $S$.

Ở đây cách dễ nhất là sử dụng các cân nhắc về năng lượng.
