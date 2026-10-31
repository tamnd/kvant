---
id: 1980-3-shkapenyuk-vyipuklost-funktsiy-i-dokazatelstvo-neravenstv-f3c8ee6f
issue: kvant_1980_3
year: 1980
number: "3"
title: Tính lồi của hàm số và chứng minh bất đẳng thức
authors:
  - Шкапенюк М. Б.
rubric: matematicheskiy-kruzhok
rubric_sub: Математический кружок
page_first: 23
page_last: 24
page_labels: 21-22
tag: 4XE9
lang: vi
source: kvant_digital
extraction: vision
content_sha256: 88695d4b2028db60553cba745fca470ca101ebb8753ffaa08f9f9ae2b3006b40
prompt_sha256: draft-1
translated_from: content/ru/1980/03/articles/06_shkapenyuk-vyipuklost-funktsiy-i-dokazatelstvo-neravenstv-f3c8ee6f.md
source_content_sha256: b2f3fe1b0085b17fa3967de220a0beaf491f94b73dc1e6817256652c388b346c
translation_model: draft
translation_run: vi-draft-2026-10-31
translation_quality: draft
---

⟦folio 21⟧

M. Shkapenyuk

Lồi
CHỨC NĂNG
VÀ BẰNG CHỨNG
BẤT ĐẸP

Bài viết này tìm hiểu các tính chất của hàm lồi. Cụ thể, bất đẳng thức được thiết lập giữa giá trị trung bình số học của hàm lồi tại n điểm và giá trị của nó tại trung bình số học của các điểm này. Từ bất đẳng thức này, dễ dàng thu được các mối quan hệ cổ điển giữa trung bình điều hòa, trung bình hình học, trung bình số học và trung bình bậc hai.

hàm lồi
Chúng ta hãy xem xét hàm $f$, lấy đạo hàm tại bất kỳ điểm nào của đoạn $[a; b]$ và ký hiệu là $\Gamma$ phần đồ thị của hàm $f$ tương ứng với đoạn này:

$$\Gamma = \{(x; y) | x \in [a; b] \text{ и } y = f(x)\}.$$

Hàm $f$ được gọi là lồi lên trên đoạn $[a; b]$ (“Đại số và Nguyên tắc Phân tích 10”, trang 79) nếu với bất kỳ điểm nào $T \in \Gamma$ đường cong $\Gamma$ nằm bên dưới tiếp tuyến với $\Gamma$ tại điểm $T$ (Hình 1 a). Về mặt phân tích, dễ dàng nhận thấy (Hình 2), điều kiện này được viết dưới dạng bất đẳng thức

$$f(x_2) < f(x_1) + f'(x_1)(x_2 - x_1),$$

phải giữ cho bất kỳ (khác nhau) $x_1, x_2 \in [a; b]$. Độ lồi hướng xuống trên một đoạn được xác định tương tự (Hình 1, b); đối với nó, dấu < trong bất đẳng thức (1) phải được thay thế bằng >.

Trong cùng một đoạn của sách giáo khoa, nó được xây dựng đủ cho bất kỳ hàm nào: nếu trên khoảng thời gian thứ hai là dương (âm) tùy ý, thì đồ thị lồi xuống (hướng lên). Hình học trong trường hợp đầu tiên là tăng tốc hoặc giảm chậm, và trong trường hợp thứ hai - giảm chậm hoặc giảm nhanh.

Ví dụ 1) Hàm $f(x) = x^2$ lồi xuống trên bất kỳ đoạn nào $[a; b]$. 2) Hàm $f(x) = \lg x$ lồi lên trên $[a; b]$ nếu $0 < a < b$. 3) Hàm $f(x) = \sin x$ lồi lên $[0; \pi]$ và lồi xuống $[\pi; 2\pi]$.

Bây giờ chúng ta hãy xem xét một số tính chất đơn giản của hàm lồi; Chúng tôi xây dựng chúng cho trường hợp các hàm lồi hướng lên, để người đọc trình bày lại chúng cho các hàm lồi hướng xuống.

I. Nếu $f$ lồi lên trên $[a; b]$ thì với mọi điểm (khác nhau)

$$f\left(\frac{1}{2}(x_1 + x_2)\right) > \frac{1}{2}(f(x_1) + f(x_2)).$$

Cơm. 1 một

Cơm. 1 6

⟦folio 22⟧

Bằng chứng rất hiển nhiên: chỉ cần kiểm tra tiếp tuyến của đồ thị hàm số tại điểm $\frac{1}{2}(x_1+x_2) \in [a; b]$ là đủ và nhận thấy rằng độ dài của đoạn $|AB|$ bằng $\frac{1}{2}(f(x_1)+f(x_2))$ (Hình 3).

Có thể chứng minh rằng hàm khả vi trên khoảng $[a; b]$ và có tính chất I sẽ lồi lên. Thực tế này là không bắt buộc, vì vậy chúng tôi không cung cấp bằng chứng.

II. Nếu hàm $f(x)$, $g(x)$ lồi lên trên $[a; b]$ thì tổng $h(x)=f(x)+g(x)$ của chúng cũng lồi lên trên $[a; b]$.

Thật vậy, khi cộng các bất đẳng thức (1) cho $f$ và $g$ và sử dụng thực tế là $h'(x)=f'(x)+g'(x)$, chúng ta sẽ ngay lập tức thu được bất đẳng thức (1) cho hàm $h$.

III. Nếu hàm $f(x)$ lồi lên trên $[a; b]$ thì hàm $h(x)=-f(x)$ lồi xuống trên $[a; b]$.

Điều này xuất phát ngay từ định nghĩa về độ lồi của hàm số. Thuộc tính sau ngay lập tức kế thừa từ thuộc tính II và III:

IV. Nếu hàm $f(x)$ lồi lên trên $[a; b]$ và hàm $g(x)$ lồi xuống trên đoạn này thì hàm $h(x)=f(x)-g(x)$ lồi lên trên đoạn đó.

Và đây là sự bất bình đẳng cơ bản đã được hứa hẹn.

Định lý. Nếu hàm lồi hướng lên trên $[a; b]$ và các số $x_1, x_2, \dots, x_n \in [a; b]$ ($n \geqslant 2$) không bằng nhau thì

$$f\left(\frac{1}{n}(x_1+\dots+x_n)\right) > \frac{1}{n}[f(x_1)+\dots+f(x_n)].$$

Định lý này là nguồn gốc vô tận của bất đẳng thức: chỉ cần thay thế bất kỳ hàm bê tông hóa lồi lên nào cùng với hàm $f$ trong (*) là đủ và... bất đẳng thức hoàn thành! Ví dụ: kết hợp hàm $f$ sin, chúng ta thu được hàm đó với bất kỳ $x_1, \dots, x_n \in [0; \pi]$ bất kỳ (khác) thì bất đẳng thức sau đúng:

$$\sin\left(\frac{1}{n}(x_1+\dots+x_n)\right) > \frac{1}{n}(\sin x_1+\dots+\sin x_n).$$

Chúng ta sẽ tắt phần chứng minh định lý cho đến hết bài, nhưng bây giờ hãy xem nó diễn ra như thế nào.

Bất đẳng thức cổ điển

Chúng ta hãy nhớ lại một số định nghĩa thường thấy trong toán học và đóng vai trò quan trọng trong các ứng dụng của nó (lý thuyết xác suất, thống kê toán học, v.v.).

Số dương trung bình điều hòa $x_1, x_2, \dots, x_n$ là số

$$P_{-1} = \left(\frac{1}{n}(x_1^{-1}+x_2^{-1}+\dots+x_n^{-1})\right)^{-1} = n/(x_1^{-1}+x_2^{-1}+\dots+x_n^{-1}).$$

Số dương trung bình hình học $x_1, x_2, \dots, x_n$ là số

$$P_0 = \sqrt{x_1 \cdot x_2 \cdot \dots \cdot x_n},$$
