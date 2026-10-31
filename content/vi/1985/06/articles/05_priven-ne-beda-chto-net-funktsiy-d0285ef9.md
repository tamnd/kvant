---
id: 1985-6-priven-ne-beda-chto-net-funktsiy-d0285ef9
issue: kvant_1985_6
year: 1985
number: "6"
title: Không có vấn đề gì khi không có chức năng
authors:
  - Привень А. И.
rubric: osnovnye-stati
page_first: 22
page_last: 23
page_labels: 20-21
tag: 98KK
lang: vi
source: kvant_digital
extraction: vision
content_sha256: 4259a0d1f5ba98b54ed56810b8dab616acec65d536b5a275636a2723f70849d2
prompt_sha256: draft-1
translated_from: content/ru/1985/06/articles/05_priven-ne-beda-chto-net-funktsiy-d0285ef9.md
source_content_sha256: afbc0fb7973d3f52ed2058a81911e87181b9e64736e91051958fa0fe67bc76b8
translation_model: draft
translation_run: vi-draft-2026-10-31
translation_quality: draft
---

⟦folio 20⟧

Không có vấn đề gì khi không có chức năng

A. I. PRIVEN

— Bố ơi, bố mẹ của Masha Sidorova đã mua một chiếc “Điện tử BZ-36” mới toanh có nhiều chức năng. Và những kẻ khác có nó...
— Cái gì, “Điện tử BZ-30” của bạn hoạt động không tốt?
“Nó hoạt động nhưng không có chức năng: nó chỉ thực hiện các phép tính số học và mô tả các nghiệm.” Và ở lớp chín chúng ta có tất cả các hàm snus và cos, logarit, hàm số mũ. Tôi không thể mang theo bàn Bradis đi khắp mọi nơi!
- Không có chức năng gì cũng không sao. Bạn muốn trở thành nhà toán học với chúng tôi nên bạn phải báo cáo. Bạn đã được kể về loạt phim Taylor về bột báng chưa? Vậy thì nghe này...

Cách tính logarit

Đầu tiên, một chút lý thuyết. Tất nhiên là bạn biết điều đó

$$\lim_{x \to 0} (1+x)^{1/x} = e.$$

Đẳng thức này được thỏa mãn với độ chính xác đủ nếu $x$ gần bằng 0. Sau đó, chúng ta thu được $(1+x)^{1/x} \approx e$ hoặc $1+x \approx e^x$, từ đó

$$\ln(1+x) \approx x,$$

(1) nghĩa là, bằng cách trừ một số cho số, chúng ta thu được logarit tự nhiên của nó. Còn số lượng lớn thì sao?
Khá đơn giản. Rốt cuộc

$$\ln a = \ln (a^{N/N}) = N \ln (a^{1/N}).$$

Nếu $N$ đủ lớn (chúng ta sẽ nói về các giá trị cụ thể sau), thì $a^{1/N} \approx 1$ và $\ln (a^{1/N}) \approx a^{1/N} - 1$.

Trên máy, $a^{1/N}$ rất dễ tính nếu $N=2^n$ - bạn chỉ cần nhấn phím $\sqrt{}$ $n$ lần. Và sau đó để tìm logarit ban đầu, bạn cần trừ một và nhân với hai số tương ứng:

$$\ln a = \ln a^{N/N} = N \ln a^{1/N} \approx (a^{1/N} - 1) \cdot N.$$

Tất cả những gì còn lại là tìm giá trị tối ưu $N$. Từ đẳng thức (1) suy ra

$$\ln (1+x)^{1/2} = \frac{1}{2} \ln (1+x) \approx \frac{1}{2} x \approx \ln \left(1 + \frac{1}{2} x\right),$$

đó là

$$\left(1+x\right)^{1/2} = \sqrt{1+x} \approx 1 + \frac{1}{2} x.$$

Để đánh giá độ chính xác của đẳng thức này, hãy sử dụng công thức Taylor*. Ba thuật ngữ đầu tiên là đủ cho chúng tôi:

$$f(a+x) = f(a) + xf'(a) + \frac{x^2}{2!} f''(a) + \dots$$

Trong trường hợp của chúng tôi $a=1$; $f(a+x) = \sqrt{1+x}$;

$$f(a) = \sqrt{a} = 1; f'(a) = \frac{1}{2\sqrt{a}} = \frac{1}{2};$$

$$f''(a) = -\frac{1}{4a^{3/2}} = -\frac{1}{4},$$

nghĩa là, $\sqrt{1+x} \approx 1 + \frac{x}{2} - \frac{x^2}{8}$;

các số hạng còn lại tại $x \to 0$ có thể bị loại bỏ.

Như vậy, sai số của công thức (3) xấp xỉ bằng $x^2/8$. Hãy để chúng tôi đặt giá trị lỗi $\Delta = 5 \cdot 10^{-9}$. Đây là những giá trị nhất không ảnh hưởng đến số đọc của máy tính 8 chữ số.

Vậy thì thật đơn giản: $\Delta = \frac{x^2}{8} = 5 \cdot 10^{-9}$, $x=2 \cdot 10^{-4}$. Giá trị $x$ này sẽ cung cấp sai số tối thiểu. Do đó, giá trị của $ln 2$, được tính bằng công thức $\ln 2 = 2^{12} (2^{1/2^12} - 1) = 4096 \times 0.0001691$, bằng 0,693207, cùng với bảng 0,693147.

Tuy nhiên, ở đây có một hiệu ứng thuần túy “máy móc”: việc trích xuất gốc (giống như các phép tính khác) được thực hiện với sự thiếu sót ở dấu cuối cùng và lỗi này mỗi lần tăng lên. Cuối cùng, nó chồng lên các đại lượng $\frac{x^2}{8}$ và công thức cho $\Delta$ trở nên không thể áp dụng được. Hiệu ứng này được thay thế bằng $n > 10$, trong đó $n = \log_2 N$ là số lần trích xuất gốc. Kết quả là, $\ln 2$ tương tự, được tính bằng công thức tương tự trên máy vi tính BZ-30, bằng 0,69263... By-

*) Về công thức Taylor, xem bài viết của V. R. Pochuev trên tạp chí Kwan số trước.

⟦folio 21⟧

Vì vậy, trong trường hợp $n > 10$ nên chấp nhận $x = (3,5 \div 7) \cdot 10^{-4}$.

Cùng ln 2, được tính trên cùng một máy ở $n = 11$, bằng 0,69304 với sai số tương đối là 0,014%.

Vì vậy, chúng tôi đã tìm ra thuật toán tính ln $a$:

$$\ln a = \frac{\ln a}{\ln 10} = \frac{\ln a}{2,303}.$$

Đối với $2 < a < 10$ kết quả khá chính xác được đưa ra bởi biểu thức

$$\lg a \approx (a^{2/10} - 1) \cdot 445,$$

ở đâu $445 \approx \frac{2^{10}}{\ln 10}$.

Cách tính hàm số mũ

Để tính hàm $e^x$, chúng ta biến đổi biểu thức thu được cho ln $a$. Chúng ta có ln $a \approx N (a^{1/N} - 1)$, với $N$ lớn, có nghĩa là

$$a \approx \left( \frac{\ln a}{N} + 1 \right)^N.$$

Thực hiện thay thế $x = \ln a$, chúng ta nhận được $a = e^x$ và do đó

$$e^x \approx \left( \frac{x}{N} + 1 \right)^N = \left( \frac{x}{N} + 1 \right)^{2n}.$$

Để nhanh chóng sử dụng sự tương ứng này trên một máy tính đơn giản, nên biến nó thành một thuật toán số nguyên, tức là một thuật toán trong đó không cần phải ghi lại các kết quả trung gian. Để làm điều này, phải thực hiện lũy thừa $N$ (hoặc $n$ bình phương) bằng cách lặp lại chuỗi lệnh $\times =$ cho mẫu B3-30 hoặc

$$\dots \times 1 \times = \dots ,$$

cho loại mô hình B3-14. Trong trường hợp này, kết quả luôn ở trong “bộ nhớ tạm thời” của máy tính và do đó không cần phải nhập lại vào máy sau mỗi lần lặp. Do đó, thuật toán tìm $e^x$ trông như thế này (bên dưới $n$ là số tự nhiên, hơn nữa $N = 2^n$):

$$x : 2^n + 1 \times =$$

Cách tính của hàm $10^{xn}$ chỉ khác ở chỗ sau khi gõ $2^n$ kết quả được nhân với ln $10 \approx 2,303$.

Những gì còn lại là hàm $x^y$. Hãy tiếp tục với nó:

$$\ln (x^y) = y \ln x = Ny \ln (x^{1/N}) \approx Ny (x^{1/N} - 1).$$

Do đó, theo công thức (4)

$$x^y = e^{\ln (x^y)} \approx e^{Ny (x^{1/N} - 1)} \approx \left[ \frac{Ny (x^{1/N} - 1)}{N} + 1 \right]^N = [y (x^{1/N} - 1) + 1]^N.$$

Công thức (5) được biểu diễn bởi chương trình:

Cách tính hàm lượng giác

Ở đây công thức Taylor đưa ra hai biểu thức thuận tiện cho sin và cosius

$$\sin x \approx x - \frac{x^3}{6} = \frac{(x^2 - 6)x}{6};$$

$$\cos x \approx 1 - \frac{x^2}{2} + \frac{x^4}{24} = 1 + \frac{(x^2 - 12)x^2}{24}.$$

Giá trị đầu tiên đủ cho $x \leq \frac{\pi}{4}$; điều tương tự có thể được nói về thứ hai. Giá trị $\frac{x^4}{24}$ bắt đầu có tác động rõ rệt ở $x \geq \frac{\pi}{6}$, ở $x < \frac{\pi}{6}$ bạn có thể đơn giản hóa công thức tính cos $x$ bằng cách loại bỏ số hạng thứ ba:

$$\cos x \approx 1 - \frac{x^2}{2}.$$

Ràng buộc $x \leq \frac{\pi}{4}$ không nguy hiểm vì các hàm lượng giác luôn có thể được rút gọn thành đối số nhỏ hơn $\frac{\pi}{4}$.

* * *

Như bạn có thể thấy, chỉ cần một chút toán học - và chiếc máy tính vi mô đơn giản nhất sẽ sẵn sàng tính toán gần như tất cả các hàm “trường học”.
