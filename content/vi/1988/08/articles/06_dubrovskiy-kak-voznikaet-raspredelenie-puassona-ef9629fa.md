---
id: 1988-8-dubrovskiy-kak-voznikaet-raspredelenie-puassona-ef9629fa
issue: kvant_1988_8
year: 1988
number: "8"
title: Phân phối Poisson phát sinh như thế nào?
authors:
  - Дубровский В. Н.
rubric: raznoe
page_first: 25
page_last: 28
page_labels: 23-26
tag: QYFL
lang: vi
source: kvant_digital
extraction: vision
content_sha256: 06a07b30c52b1b458e964c108853e71ffa0f1cc80a53b1da136d695754c35139
prompt_sha256: draft-1
translated_from: content/ru/1988/08/articles/06_dubrovskiy-kak-voznikaet-raspredelenie-puassona-ef9629fa.md
source_content_sha256: a1247318f4824dcf1615994c20b6f03a7b259b86ca2e4070c967b4c10df12ab8
translation_model: draft
translation_run: vi-draft-2026-10-31
translation_quality: draft
---

⟦folio 23⟧

NÓ PHÁT SINH NHƯ THẾ NÀO
PHÂN PHỐI ĐỘC

Ứng viên Khoa học Vật lý và Toán học
V. N. DUVROVSKY

Mỗi khi có cơ hội, bạn có thể bắt gặp cơn mưa đầu hè, khi mặt đất vẫn khô ráo và chỉ ở đây mới có những vết đen hiếm hoi xuất hiện ngay từ những giọt đầu tiên. Những đốm này là mô hình gần như hoàn hảo của “các chấm rải rác ngẫu nhiên” được đề cập trong bài viết Phân phối Poisson. Hãy thử sử dụng mô hình trực quan này để xây dựng các giả thuyết toán học mô tả các điểm phân tán ngẫu nhiên và rút ra từ chúng:

*) Vô tình, chúng ta buộc phải làm mà không có định nghĩa về khái niệm xác suất - chẳng hạn, những ai muốn có thể tìm thấy nó trong cuốn sách của A. N. Kolmogorov, I. G. Zhurbenko, A. V. Prokorov “Giới thiệu về Lý thuyết Xác suất” (M., Nauka, 1978). Chúng tôi hy vọng rằng một lượng nhỏ ý thức chung sẽ đủ để hiểu bài viết.

rằng số điểm nằm trong một khu vực nhất định trong quá trình xác định thời gian tuân theo phân phối Poisson.

Gọi $P_k$ là xác suất*) để $k$ giọt nước rơi xuống khu vực chúng ta đã chọn. Trước hết, rõ ràng rằng

1) xác suất $P_k$ chỉ được xác định bởi diện tích của khu vực này và không phụ thuộc vào hình dạng và vị trí của nó.

Do đó, chúng tôi sẽ tìm kiếm $P_k$ như một hàm của diện tích trang web, tức là ở dạng $P_k(s)$. Giả thuyết tự nhiên thứ hai là

2) số giọt rơi trên một khu vực nhất định không phụ thuộc vào số giọt rơi trên bất kỳ khu vực nào khác không giao nhau với khu vực đầu tiên.

⟦folio 24⟧

Nói cách khác, xác suất $P_0, P_1, P_2, \dots$ đối với một khu vực nhất định không phụ thuộc chút nào vào số lượng giọt rơi ở khu vực khác. Biểu thức toán học của điều kiện độc lập là quy tắc nhân xác suất: xác suất xảy ra đồng thời của hai sự kiện độc lập bằng tích xác suất của chúng. Ví dụ: nếu $S$ và $T$ là hai phần rời nhau của $P_1(s) \cdot P_1(t)$. Tương tự, sự kiện “2 giọt rơi vào khu vực $S$ và $T$” có xác suất là $P_2(s) \cdot P_0(t) + P_1(s) \cdot P_1(t) + P_0(s) \cdot P_2(t)$ (sự kiện này được chia thành ba: trên khu vực $S$ 2 giọt rơi và trên $T$ - không có; trên khu vực $S$ 1 giọt rơi và trên $T$ - 1 giọt; trên khu vực $S$ có 0 giọt và $T$ có 2 giọt; xác suất của nó bằng tổng xác suất của ba thành phần này). Chúng tôi nhấn mạnh rằng quy tắc nhân xác suất chưa được chứng minh - đây là một định nghĩa về tính độc lập, nhưng không khó để giải thích tại sao định nghĩa này được chấp nhận.

Một trong những nguyên tắc cơ bản của lý thuyết xác suất (luật số lớn) phát biểu rằng tần suất xảy ra một sự kiện trong một chuỗi thí nghiệm đủ dài sẽ tiệm cận đến xác suất của nó. Hãy để các sự kiện $A$ và $B$ được quan sát trong một loạt các thí nghiệm $n$ và sự kiện $B$ đã xảy ra $m$ lần và cả hai sự kiện xảy ra đồng thời $k$ lần; thì tần số $m/n$ của sự kiện $B$ gần bằng xác suất của nó $P(B)$ và tần suất $k/n$ xảy ra đồng thời của sự kiện $A$ và $B$ là xác suất tương ứng $P(AB)$. Sự độc lập của các sự kiện $A$ và $B$ phải nằm ở chỗ thông tin về sự xuất hiện của sự kiện $B$ không thể ảnh hưởng đến xác suất xảy ra sự kiện $A$. Do đó, tần suất của $k/m$ thí nghiệm trong đó sự kiện $A$ xảy ra, trong số những thí nghiệm trong đó sự kiện $B$ được ghi lại, phải giống như trong chuỗi tất cả các thí nghiệm nói chung: $k/m \approx P(A)$. Như vậy,

$$P(AB) \approx \frac{k}{n} = \frac{k}{m} \cdot \frac{m}{n} \approx P(A) \cdot P(B).$$

Trong giới hạn (tại $n \to \infty$), các đẳng thức gần đúng này chuyển thành đẳng thức chính xác. Chúng tôi nhận được xác nhận rằng “quy tắc nhân xác suất” phản ánh chính xác ý tưởng trực quan của chúng tôi về tính độc lập của các sự kiện.

Tuy nhiên, chúng ta hãy quay trở lại với những hạt mưa. Giả thuyết thứ ba mô tả sự mất mát của họ như sau:

3) xác suất $P_{>1}(h)$ để ít nhất 2 giọt rơi trên một khu vực nhỏ $h$ là không đáng kể so với xác suất $P_1(h)$ để 1 giọt rơi trên khu vực nhỏ này, tức là $P_{>1}(h)/P_1(h) \to 0$ với $h \to 0$.

Nói cách khác, giọt nước không rơi vào cùng một chỗ hai lần. Bây giờ các điều kiện đã được hình thành đầy đủ và bạn có thể bắt đầu nhận điều kiện tiếp theo.

Trước hết chúng ta hãy tìm $P_0(s)$. Diện tích khoảng cách $s+t$ và chia thành hai khu vực - diện tích $s$ và diện tích $t$. Nếu phần lớn hơn $(s+t)$ vẫn khô thì không có giọt nào rơi xuống cả hai phần $s$ và $t$ của nó, và do điều kiện 2) sự độc lập của các phần đối với bất kỳ $s, t \geqslant 0$ nào chúng ta thu được $P_0(s+t) = P_0(s)P_0(t)$.

Từ phương trình này, chúng ta cần tìm hàm $P_0$, mà chúng ta biết thêm rằng $0 \leqslant P_0(s) \leqslant 1$ và $P_0(s) - убывающая функция. Докажем, что $P_0(s) = e^{-\lambda s}$ при некотором $\lambda > 0$. Пусть $f là hàm giảm thỏa mãn $f(s+t) = f(s) \cdot f(t)$. Đối với mọi $s > 0$ và mọi $n$ $f(ns) = f(s + (n-1)s) = f(s)f((n-1)s) = \dots = (f(s))^n$ tự nhiên.

Thay $s = \frac{1}{n}$ ở đây và đặt $f(1) = e^{-\lambda}$, ta được $f(1/n) = e^{-\lambda/n}$. Bây giờ chúng ta thay thế $s = 1/m$ và chúng ta nhận được $f(n/m) = (f(1/m))^n = e^{-\lambda n/m}$, tức là với bất kỳ số hữu tỉ $s > 0$ nào chúng ta có $f(s) = e^{-\lambda s}$. Bây giờ, thu được hàm đơn điệu $f(s)$

⟦folio 25⟧

và $e^{-\lambda s}$, dễ dàng chứng minh rằng đẳng thức cuối cùng đúng với mọi $s > 0$.

Lưu ý rằng $P_0(h) \approx 1 - \lambda h$ đối với $h$ nhỏ (ký hiệu $u(h) \approx v(h)$ sẽ có nghĩa là $(u(h) - v(h))/h \rightarrow 0$ đối với $h \rightarrow 0$). Thật vậy, tích của hàm $e^{-\lambda s}$ với $s = 0$ bằng $-\lambda e^{-\lambda h} = -\lambda$, tức là $(P_0(h) - 1)/h = (e^{-\lambda h} - 1)/h \rightarrow -\lambda$ với $h \rightarrow 0$. Do đó, $P_1(h) + P_{>1}(h) = 1 - P_0(h) \approx \lambda h$ đối với $h$ nhỏ. Và vì, theo điều kiện 3, $P_{>1}(h)$ không đáng kể so với $P_1(h)$, đối với $h$ $P_1(h) \approx \lambda h$ nhỏ, $P_k(h) \approx 0$ đối với $k > 1$.

Bây giờ chúng ta có thể tạo các phương trình vi phân từ đó chúng ta sẽ tìm thấy $P_k(s)$. Chúng ta hãy xem xét một biểu đồ có diện tích $s$ và thêm vào đó một biểu đồ có diện tích nhỏ $h$. Lặp lại đạo hàm bằng nhau ở trên, chúng ta thu được

$$P_k(s + h) = P_k(s)P_0(h) + P_{k-1}(s)P_1(h) + (P_{k-2}(s)P_2(h)) + \dots + P_0(s)P_k(h).$$

Vì $P_0(h) \approx 1 - \lambda h$, $P_1(h) \approx \lambda h$ và toàn bộ biểu thức trong ngoặc đơn là không đáng kể so với $h$,

$$P_k(s + h) \approx P_k(s) (1 - \lambda h) + \lambda hP_{k-1}(s);$$

kể từ đây,

$$P_k'(s) = \lim_{h \rightarrow 0} \frac{P_k(s + h) - P_k(s)}{h} = -\lambda P_k(s) + \lambda P_{k-1}(s),$$

hoặc

$$P_k'(s) + \lambda P_k(s) = \lambda P_{k-1}(s), \quad k = 1, 2, \dots$$

Để giải phương trình này, hãy xét hàm $f_k(s) = P_k(s)e^{\lambda s}$. Hãy cùng tìm sản phẩm của cô ấy nhé: $f_k'(s) = P_k'(s)e^{\lambda s} + \lambda P_k(s)e^{\lambda s}$. Nhân phương trình (*) với $e^{\lambda s}$, ta thu được

$$f_k'(s) = \lambda f_{k-1}(s),$$

với $f_k(0) = P_k(0) = 0$ tại $k > 1$.

Bây giờ thật dễ dàng để tìm thấy tất cả các hàm $f_k$ lần lượt: $f_1'(s) = \lambda P_0(s)e^{\lambda s} = \lambda$, do đó $f_1(s) = \lambda s$ (chúng tôi đã dạy rằng $f_1(0) = 0$); $f_2'(s) = \lambda f_1(s) = \lambda^2 s$, do đó $f_2(s) = \lambda^2 s^2/2$, ..., $f_k(s) = \lambda^k s^k/k!$. Và cuối cùng, chúng ta có thể viết ra biểu thức mong muốn

$$P_k(s) = \frac{(\lambda s)^k}{k!}e^{-\lambda s},$$

hợp lệ cho tất cả $k = 0, 1, 2, \dots$.

Hãy tóm tắt. Nếu các điểm trên mặt phẳng được chọn ngẫu nhiên sao cho thỏa điều kiện 1–3 thì số điểm rơi trên một diện tích có diện tích $s$ có phân bố Poisson với tham số $\lambda s$, trong đó $\lambda > 0$ là tham số đặc trưng cho mật độ trung bình của điểm (xem công thức (2) trong bài “Phân bố Poisson”).

Tất nhiên, mọi điều vừa nói có thể được chuyển gần như hoàn toàn sang trường hợp các điểm trong không gian hoặc trên một đường thẳng. Trường hợp sau đáng được đề cập đặc biệt vì nó xảy ra thường xuyên nhất trong thực tế. Trong trường hợp này, đường thẳng chứa các điểm đóng vai trò là trục thời gian và bản thân các điểm là thời điểm xuất hiện của một số tín hiệu ngẫu nhiên tuân theo các điều kiện tương tự như điều kiện 1-3. Các ví dụ tiêu chuẩn về “dòng tín hiệu” như vậy, được gọi là dòng đơn giản hoặc dòng Poissian trong lý thuyết xác suất, chẳng hạn, là các hạt phát ra từ chất phóng xạ và các cuộc gọi đến tổng đài điện thoại.

Chúng tôi mới chỉ đề cập đến một mặt của câu hỏi được đặt ra trong tiêu đề của bài viết. Với những độc giả khác, nếu anh ta tình cờ biết mọi thứ - lý thuyết về xác suất và các quá trình ngẫu nhiên.

Bạn đọc thân mến!

Trong tương lai, năm 1989, tạp chí «Kvant», như trước đây, sẽ chỉ được phân phối theo hình thức đăng ký. Bạn có thể đăng ký thuê bao hàng năm cho đến ngày 1 tháng 11 năm 1988. Việc đăng ký được chấp nhận mà không bị hạn chế tại các đại lý Soyuzpechat, bưu điện và bưu điện. Chỉ số tạp chí «Kvant» trong danh mục Soyuzpechat 70465.

⟦folio 26⟧

Số liên bang của tạp chí của chúng tôi có sự góp mặt của ba nhiếp ảnh gia chụp các đường trượt tuyết. Những bức ảnh được chụp cùng lúc và các đường trượt tuyết nằm gần đó. Nhưng họ khác nhau nhiều lắm...
Chúng tôi mời độc giả suy nghĩ về điều gì giải thích cho sự đa dạng của các loại đường trượt tuyết như vậy.

Có lẽ tất cả những ai quan tâm đến vấn đề này đều nhận ra rằng không thể làm được nếu không có vật lý. Và vật lý luôn là vật lý, cả trong tháng Ba và tháng Tám. Vì vậy, hôm nay chúng ta tiếp tục cuộc trò chuyện về các đường trượt tuyết, khi tuyết ngày càng tan và tuyết mới vẫn còn ở rất xa.
