---
id: 1975-8-byistryiy-konstruirovanie-uravneniy-po-grafikam-funktsiy-c2fb0e98
issue: kvant_1975_8
year: 1975
number: "8"
title: Xây dựng phương trình từ đồ thị hàm số
authors:
  - Быстрый И. М.
rubric: raznoe
page_first: 56
page_last: 59
page_labels: 54, 56, 57
tag: 90VB
lang: vi
source: kvant_digital
extraction: vision
content_sha256: 22b9013d3cc8e97c1b3e4a63a7cbb167b1e7451b20a815364041dd4c1610f57e
prompt_sha256: draft-1
translated_from: content/ru/1975/08/articles/13_byistryiy-konstruirovanie-uravneniy-po-grafikam-funktsiy-c2fb0e98.md
source_content_sha256: 8a783133ed3111199adc014dc698a727129559f41dde686aca4cc95fbedf2953
translation_model: draft
translation_run: vi-draft-2026-10-31
translation_quality: draft
---

⟦folio 54⟧

Xây dựng phương trình từ đồ thị hàm số

Nhu cầu xây dựng phương trình hàm số nảy sinh đối với lời giải nhiều câu hỏi khác nhau. bài toán như vậy được tìm thấy trong toán học, vật lý và quan trọng nhất là trong công nghệ hiện đại. Bài viết này cho thấy cách sử dụng phương trình của hàm elematrine [phương trình đường thẳng, parabol, hình sin], bạn có thể mô tả đồ thị của các phụ thuộc phức tạp hơn được tìm thấy trong khóa học vật lý ở trường. Chính xác hơn, trong những phần thảo luận về các quy trình định kỳ.

Đầu tiên chúng ta hãy nhớ lại một số tính chất quan trọng của đồ thị hàm số.

1. Nếu đồ thị của hàm $F_1(x)$ dịch chuyển $|c|$ đơn vị lên hoặc xuống dọc theo trục tọa độ của đồ thị hàm $f(x)$, $x \in [a, b]$ thì phương trình của hàm $F_1(x)$ có dạng

$$F_1(x) \quad f(x) \pm |c|, \quad x \in [a, b]$$

Hơn nữa, nếu đồ thị di chuyển lên trên thì lấy dấu “+”, còn nếu đi xuống thì lấy dấu “-”.

2. Nếu đồ thị của hàm $F_2(x)$ là đồ thị của hàm $f(x)$, $x \in [a, b]$ dịch chuyển $|c|$ đơn vị sang trái hoặc phải dọc theo trục hoành thì phương trình của hàm $F_2(x)$ có dạng

$$F_2(x) - f(x \pm |c|), \quad x \in [a \mp |c|, b \mp |c|]$$

Hơn nữa, các dấu trên được lấy khi đồ thị di chuyển sang trái và các dấu dưới - khi đồ thị di chuyển sang phải.

3. Nếu đồ thị của hàm $F(x)$ đối xứng với trục hoành của đồ thị hàm $f(x)$, $x \in [a, b]$ thì phương trình $F(x)$ có dạng

$$F(x) - f(x), \quad x \in [a, b]$$

Bây giờ chúng ta hãy xem xét một số ví dụ.

Cơm. 1.

Cơm. 2.

⟦folio none⟧

Hướng "hình viên thuốc"

Hãy thử sử dụng các thuộc tính trên của đồ thị hàm số để mô tả hướng “hình viên thuốc” (Hình 1). một hướng thuộc loại này được cung cấp, ví dụ, cho các tấm lệch của ống điện tử của máy hiện sóng. Đặc điểm của hướng “hình viên thuốc” là thời gian $T$ tăng dài so với thời gian giảm $t$. Do đó, về mặt đồ họa, sự thay đổi hướng theo thời gian có thể được biểu diễn dưới dạng đường như trong Hình 2. Tuy nhiên, trong trường hợp này cần có các điểm

$$t = \frac{T}{2} (2n + 1),$$

$n$ là một số nguyên. Để tránh sự mơ hồ, hãy thay thế đường “hình viên thuốc” bằng đồ thị của hàm số không được xác định tại các điểm

$$t = \frac{T}{2} (2n + 1),$$

hoặc đồ thị của hàm số được xác định tại các điểm này ở bên trái hoặc bên phải (Hình 3, $a$, $b$, $\theta$).

Để kiểm soát hàm tuần hoàn $u(t)$ được sửa đổi trong Hình 3, $a$, chúng ta nghiên cứu nó khi đối số thay đổi trong một khoảng thời gian, ví dụ: $\left(-\frac{T}{2}, \frac{T}{2}\right)$.

Trong khoảng này, đồ thị của hàm tuần hoàn $u(t)$ trùng với đồ thị của hàm $u_0 = f(t) = t^*$). Bây giờ chúng ta dịch chuyển đồ thị $u_0$ dọc theo trục x một đoạn sang phải (đường màu đỏ trong hình). sau đó chúng ta thu được một hàm mới $u_1 = f(t - T) = t - T$ và khoảng $\left(-\frac{T}{2}, \frac{T}{2}\right)$ sẽ đi vào khoảng $\left(\frac{T}{2}, \frac{3}{2} T\right)$. Bằng cách dịch chuyển đồ thị của hàm $u_0$ dọc theo trục x theo một số nguyên $n$ chu kỳ, mọi

$$*) \text{Точнее, } f(t) = At, \text{ где } A = 1 \ \theta/c \text{-размерный коэффициент.}$$

lần cố định $n$ chúng ta thu được một hàm mới

$$u_n = f(t - nT) = t - nT,$$

$$t \in \left(\frac{T}{2} (2n - 1), \frac{T}{2} (2n + 1)\right).$$

Tập hợp các hàm này tại $n = 0, \pm 1, \pm 2, \dots$ tạo thành phương trình của hàm loại trừ $u(t)$.

Nếu chu kỳ của hàm là $T = \pi$ giây thì phương trình của nó có thể được viết khác:

⟦folio 56⟧

các đoạn thẳng song song với trục tọa độ. Phương trình của chúng là:

$$t(u) = \frac{T}{2}(2n+1),$$
$$u \in \left[-\frac{T}{2}, \frac{T}{2}\right], \quad n = 0, \pm 1, \pm 2, \ldots$$

Phương trình đường dẫn

Hình 4 vẽ đồ thị đường đi của một điểm chuyển động thẳng.
Chúng ta hãy xây dựng phương trình đường dẫn *).

Rõ ràng là đồ thị $S(t)$ được tạo thành từ các phần của parabol $S_\alpha = at^2$, $t \in \left[0, \frac{T}{2}\right]^{**}$. Hãy thực hiện các phép biến đổi sau:

1) nhánh ($\alpha$) được cắt đối xứng so với trục tọa độ - ta thu được nhánh ($\beta$): $S_\beta = at^2$, $t \in \left[-\frac{T}{2}, 0\right]$;

2) nhánh ($\beta$) được cắt đối xứng so với trục hoành - ta thu được nhánh ($\gamma$): $S_\gamma = at^2$, $t \in \left[-\frac{T}{2}, 0\right]$;

3) di chuyển nhánh ($\gamma$) $T$ sang phải và $\frac{aT^2}{2}$ lên trên - chúng ta có nhánh ($\delta$): $S_\delta = -a(t-T)^2 + \frac{aT^2}{2}$, $t \in \left[\frac{T}{2}, T\right]$.

Di chuyển nhánh ($\alpha$) và ($\delta$) theo $nT$ sang phải và $\frac{aT^2}{2}$ lên trên, với biến $n = 0, 1, 2, \ldots$ chúng ta sẽ có

$$S(t) = \begin{cases} a(t-nT)^2 + n\frac{aT^2}{2}, \\ t \in [nT, \frac{T}{2} + nT]; \\ -a[t-(n+1)T]^2 + (n+1)\frac{aT^2}{2}, \\ t \in \left[\frac{T}{2} + nT, (n+1)T\right]. \end{cases}$$

*) Xem «Kvant», 1973, số 11, tr. 60.
**) Ở đây $a$ là hệ số tỷ lệ. Nếu một điểm chuyển động với gia tốc $b$ thì $a = b/2$

⟦folio 57⟧

⟦figure⟧
Cơm. 5.

⟦figure⟧
Cơm. 6.

⟦figure⟧
Cơm. 7.

⟦figure⟧
Cơm. 8.

⟦figure⟧
Cơm. 9.

⟦column⟧
Nếu chúng ta biến đổi phần thứ hai như thế này:

$$--a\left[\left(t-nT-\frac{T}{2}\right)-\frac{T}{2}\right]^2+\frac{aT^2}{2}+$$

$$+n\frac{aT^2}{2}=-a\left[t-(2n+1)\frac{T}{2}\right]^2+$$

$$+aT\left[t--(2n+1)\frac{T}{2}\right]-\frac{aT^2}{4}+$$

$$+\frac{aT^2}{2}+n\frac{aT^2}{2}=-a\left[t-(2n+1)\frac{T}{2}\right]^2+$$

$$+aT\left[t-(2n+1)\frac{T}{2}\right]+\frac{aT^2}{4}(2n+1),$$

thì phương trình đường đi có thể được viết như sau:

$$S(t)=(-1)^m a\left(t-m\frac{T}{2}\right)^2+$$

$$+\frac{1-(-1)^m}{2}aT\left(t-m\frac{T}{2}\right)+m\frac{aT^2}{4},$$

$$t\in\left[m\frac{T}{2},(m+1)\frac{T}{2}\right], m=0,1,2,\dots$$

Bài tập

1. Viết phương trình của các đường thẳng ở Hình 5, 6 và 7. Đối với đường thẳng ở Hình 5, viết phương trình của các hàm số xác định tại các điểm $t=n\pi$ ở bên trái và bên phải.
2. Việc chỉnh lưu dòng điện xoay chiều “đẩy-kéo” (toàn sóng) được thực hiện bằng cách sử dụng mạch có hai điốt ống điện tử. Nếu nửa chu kỳ dương của dòng điện đi qua một diode và nửa chu kỳ âm đi qua diode kia thì biểu đồ dao động điện áp sẽ giống như đường trong Hình 8. Hãy tìm phương trình của đường này.
3. Chỉnh lưu AC nửa sóng có thể đạt được bằng cách sử dụng một mạch diode đơn. Sau đó, nửa chu kỳ của một tín hiệu đi qua diode, nhưng nửa chu kỳ của tín hiệu kia không đi qua. Biểu đồ dao động điện áp được hiển thị trong Hình 9. Tìm phương trình của hàm này.
4. Xây dựng phương trình của hàm số có đồ thị (xem Hình 4) tại các phần $[nT,(n+1)T]$, $n=0,1,2,\dots$ đồng dạng với đồ thị của hàm số

$$y=A\sin x,\ x\in\left[-\frac{\pi}{2},\frac{\pi}{2}\right].$$
