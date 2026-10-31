---
id: 1970-5-mordkovich-kto-to-teryaet-kto-to-nahodit-d7ad32b8
issue: kvant_1970_5
year: 1970
number: "5"
title: Có người mất, có người tìm thấy
authors:
  - Мордкович А. Г.
rubric: praktikum-abiturienta
rubric_sub: Практикум абитуриента
page_first: 50
page_last: 53
page_labels: 48-51
tag: B39Q
lang: vi
source: kvant_digital
extraction: vision
content_sha256: c5d8b43e4ce7e330ee38966b4751a4c6014d9f6b97f5d1b5fb1283f3a8d04f51
prompt_sha256: 3ec6b8aabd9b98576af76503cd8a2902b9f5d18e01ee867dfb1228f59c6d52d8
translated_from: content/ru/1970/05/articles/13_mordkovich-kto-to-teryaet-kto-to-nahodit-d7ad32b8.md
source_content_sha256: 96ab34872b6a93e1a5a38e4f6e28a49c3c150a45358367e4dcbbf4faae62e823
translation_model: gpt-5.6-terra
translation_run: vi-codex-2026-10-30
---

⟦folio 48⟧

Chúng ta giải phương trình như thế nào! Xuất phát từ phương trình đã cho, ta lần lượt viết phương trình thứ nhất, thứ hai, thứ ba, ... — một chuỗi phương trình, trong đó mỗi phương trình nhận được từ phương trình trước bằng cách biến đổi một hoặc đồng thời cả hai vế, và cứ thế cho đến khi nhận được một phương trình hoàn toàn đơn giản mà nghiệm của nó ta đã biết cách tìm. Nếu đồng thời mọi chuyển từ phương trình đã cho sang phương trình kế tiếp đều “đảo ngược được”, tức là ta thấy rằng từ phép biến đổi của phương trình thứ tư có thể nhận được phương trình thứ ba, từ phương trình thứ ba — phương trình thứ hai, v.v., thì rõ ràng phương trình cuối cùng của quá trình có cùng các nghiệm như phương trình ban đầu. Nhưng thường gặp những phương trình có căn thức, lôgarit, các hàm lượng giác mà khi giải phải dùng đến những phép biến đổi khá phức tạp, khiến cho “chuyển ngược” không thật rõ ràng. Nếu khi giải những phương trình như vậy, chỉ làm các phép biến đổi một cách hình thức, không đi sâu vào ý nghĩa của chúng, thì dễ mắc sai lầm: làm mất một nghiệm hoặc thêm vào một nghiệm thừa. Bài này nói về việc điều đó xảy ra như thế nào và cách tránh những phiền toái tương tự.

1. MỘT SỐ KÝ HIỆU.

Cho các tập hợp số $X$ và $Y$. Ký hiệu $X \subset Y$ có nghĩa là mỗi phần tử của tập hợp $X$ đồng thời là phần tử của tập hợp $Y$, còn trong $Y$ có thể có những phần tử không thuộc tập hợp $X$. Ký hiệu $x \in X$ (tương ứng $x \in X$) có nghĩa là phần tử $x$ thuộc (không thuộc) tập hợp $X$.

Các điều kiện sau đây cùng với cụm từ “tập hợp $X$ gồm tất cả các số thực $x$” cũng được dùng dưới ký hiệu: $X = \{x| -\infty < x < \infty\}$. Tương tự, cách viết $X = \{x|x \ge 3\}$ có nghĩa là tập hợp $X$ gồm tất cả các số $x$ thỏa mãn bất đẳng thức $x \ge 3$, còn cách viết $X = \{x|x \neq \pi\}$ có nghĩa là tập hợp $X$ chứa mọi số thực, trừ $x = \pi n^*$).

Và cuối cùng, các điều kiện miền giá trị cho phép ĐKXĐ (nhắc lại rằng miền

*) Ở mọi chỗ sau này giả sử rằng $n, k=0, \pm 1, \pm 2, \ldots$

⟦folio 49⟧

Tập hợp các giá trị chấp nhận được của phương trình $f(x)=g(x)$ được gọi là tập hợp những $x$ mà tại đó các hàm $f(x)$ và $g(x)$ xác định) của phương trình đã cho ký hiệu bằng chữ $X$, còn ĐKXĐ của phương trình nhận được từ phương trình ban đầu do một phép biến đổi nào đó — bằng chữ $Y$.

2. NGHIỆM NGOẠI LAI TỪ ĐÂU MÀ RA?

Nguyên nhân thứ nhất là mở rộng ĐKXĐ. Khi giải phương trình, người ta thường xuyên áp dụng nhiều phép biến đổi khác nhau. Khá thường xuyên xảy ra trường hợp ĐKXĐ của phương trình nhận được từ phương trình ban đầu do một phép biến đổi nào đó lại rộng hơn ĐKXĐ của phương trình ban đầu (cụm từ “ĐKXĐ rộng hơn” có nghĩa là $X \subset Y$). Việc mở rộng ĐKXĐ có thể dẫn đến sự xuất hiện của các nghiệm ngoại lai. Vấn đề là phương trình nhận được có thể có những nghiệm mà, tuy là phần tử của tập $Y$, lại không thuộc tập $X$. Chính chúng sẽ là các nghiệm ngoại lai của phương trình ban đầu.

Ví dụ 1. Giải phương trình
$$\frac{2}{2-x} + \frac{1}{2} = \frac{4}{2x-x^2}.$$
Lời giải. Trước hết, viết ĐKXĐ của phương trình (1): $X=\{x|x \neq 0;2\}$. Quy đồng mẫu số, ta được
$$4x+2x-x^2=8.$$

Phương trình (2) đã có ĐKXĐ khác: $Y=\{x|-\infty < x < \infty\}$. Giải phương trình (2), ta được hai nghiệm: $x_1=4$, $x_2=2$, trong đó $x_1 \in X$, còn $x_2 \in X$, vì vậy $x_2$ là nghiệm cố định của phương trình (1). Do đó, phương trình (1) có nghiệm duy nhất $x=4$.

Ví dụ 2. Giải phương trình
$$\lg (x^2+3x-4) = \lg (2x+2).$$
Lời giải. Giải hệ bất phương trình
$$\begin{cases} x^2+3x-4 > 0, \\ 2x+2 > 0, \end{cases}$$
ta tìm được miền xác định của phương trình (3): $X=\{x|x > 1\}$. Lấy lũy thừa, ta biến đổi phương trình (3) thành phương trình
$$x^2+3x-4=2x+2$$
có miền xác định rộng hơn: $Y=\{x|-\infty < x < \infty\}$. Phương trình (4) có hai nghiệm: $x_1=2$, $x_2=-3$, trong đó $x_1 \in X$, còn $x_2 \in X$. Vậy $x_2$ là nghiệm cố định của phương trình (3) và do đó, phương trình (3) có nghiệm duy nhất $x=2$.

Việc mở rộng miền xác định đôi khi dẫn đến việc áp dụng một số công thức đã biết từ chương trình trung học. Đó là các công thức liên quan đến những tính chất khác nhau của logarit, căn bậc chẵn, cũng như một số-

$$\log_a f(x) + \log_a g(x) = \log_a [f(x) \cdot g(x)],$$
$$\frac{1-\cos x}{\sin x} = \tg \frac{x}{2}.$$

Không khó thấy rằng hàm số xuất hiện ở vế phải của các đẳng thức này có miền xác định rộng hơn hàm số xuất hiện ở vế trái.

Vì vậy, tập xác định của hàm số $\log_a f(x)+\log_a g(x)$ được xác định bởi hệ bất đẳng thức
$$\begin{cases} f(x) > 0, \\ g(x) > 0, \end{cases}$$
trong khi tập xác định của hàm số $\log_a [f(x) \cdot g(x)]$ gồm các nghiệm của hệ (7) và các nghiệm của một hệ bất đẳng thức nữa
$$\begin{cases} f(x) < 0, \\ g(x) < 0. \end{cases}$$

Tập xác định của hàm số $\frac{1-\cos x}{\sin x}$ là: $X=\{x|x \neq \pi n\}$. Còn hàm số $tg \frac{x}{2}$ có tập xác định rộng hơn: $X=\{x|x \neq \pi(2k+1)\}$. Vì vậy, việc áp dụng các công thức (5), (6) và các công thức tương tự khi giải phương trình “từ trái sang phải” có thể dẫn đến xuất hiện các nghiệm ngoại lai.

Ví dụ 3. Giải phương trình
$$\frac{1-\cos x}{\sin x} + \tg^3 \frac{x}{2} = 0.$$

Lời giải. Viết điều kiện xác định của phương trình (8): $X=\{x|x \neq \pi n\}$. Áp dụng công thức (6), ta được phương trình
$$tg \frac{x}{2} + \tg^3 \frac{x}{2} = 0$$

có điều kiện xác định rộng hơn: $Y=\{x|x \neq \pi(2k+1)\}$. Các nghiệm của phương trình (9) là các giá trị $x=2\pi n$. Tất cả các giá trị này không thuộc điều kiện xác định của phương trình (8), do đó là các nghiệm ngoại lai. Vậy phương trình (8) không có nghiệm.

Nguyên nhân thứ hai là nhân cả hai vế của phương trình với cùng một hàm số. Cho phương trình
$$f(x)=g(x).$$
Nhân cả hai vế với hàm số $h(x)$. Ta được phương trình
$$f(x)\cdot h(x)=g(x)\cdot h(x),$$
các nghiệm của nó gồm cả các nghiệm của phương trình (10), lẫn các nghiệm của phương trình $h(x)=0$ (hay như còn nói, các nghiệm của hàm số $h(x)$. Trong số các nghiệm sau này có thể có cả những nghiệm không thỏa mãn phương trình

⟦folio 50⟧

(10), tức là là nghiệm ngoại lai đối với nó (nhân tiện, trong ví dụ 1 cả hai vế của phương trình (1) đã được nhân với cùng một hàm số $2x(2-x)$. Kết quả là xuất hiện nghiệm ngoại lai $x=2$, nhưng sự xuất hiện của nó là do việc mở rộng ĐKXĐ).

Ví dụ 4. Giải phương trình

$$x = (\sqrt{1+x} + 1)(\sqrt{10+x} - 4).$$

Lời giải. Viết ĐKXĐ của phương trình (12): $X = \{x|x \geq -1\}$. Nhân cả hai vế của phương trình với hàm $h(x) = \sqrt{1+x} - 1$. Sau khi biến đổi, ta được phương trình $x(\sqrt{1+x} - \sqrt{10+x} + 3) = 0$, có 2 nghiệm: $x_1 = 0$, $x_2 = -1$ (lưu ý rằng ĐKXĐ mở rộng sẽ không xuất hiện). Cả hai nghiệm đều thuộc tập $X$, tuy nhiên phép kiểm tra cho thấy rằng $x_1 = 0$ — là nghiệm tạo ra (không khó thấy rằng $x = 0$ — là nghiệm của hàm $h(x)$). Như vậy, phương trình (12) có nghiệm duy nhất $x = -1$.

Nguyên nhân thứ ba — nâng cả hai vế của phương trình lên trong phần trung tâm Xét phương trình (10). Nâng cả hai vế của phương trình này lên bình phương. Ta được phương trình $[f(x)]^2 = [g(x)]^2$, mà các nghiệm của nó gồm cả các nghiệm của phương trình (10), lẫn các nghiệm của phương trình “ngoại lai” $f(x) = -g(x)$. Trong số các nghiệm sau này cũng có thể có những nghiệm không thỏa mãn phương trình ban đầu (10). Chính chúng sẽ là các nghiệm tạo ra đối với phương trình (10).

Ví dụ 5. Giải phương trình

$$\sqrt{2x+5} + \sqrt{x-1} = 8.$$

Lời giải. Viết ĐKXĐ của phương trình (13): $X = \{x|x \geq 1\}$. Nâng cả hai vế của phương trình lên bình phương. Sau khi biến đổi, ta được

$$2\sqrt{2x^2 + 3x} - 5 = 60 - 3x$$

và tiếp tục

$$4(2x^2 + 3x - 5) = (60 - 3x)^2,$$

từ đó $x_1 = 10$, $x_2 = 362$. Do đó trong các nghiệm tìm được, ta nhận thấy chỉ $x_1 = 10$ thỏa mãn phương trình (13), còn $x_2 = 362$ là nghiệm ngoại lai (mặc dù nó thuộc ĐKXĐ của phương trình (10). Nghiệm ngoại lai xuất hiện do bình phương cả hai vế của phương trình (14).

3. ĐIỀU GÌ DẪN ĐẾN MẤT NGHIỆM?

Nguyên nhân thứ nhất là thu hẹp ĐKXĐ. Cũng có những phép biến đổi dẫn đến một phương trình có ĐKXĐ hẹp hơn. Việc thu hẹp ĐKXĐ có thể dẫn đến mất nghiệm, cụ thể là có thể “làm mất” những nghiệm của phương trình ban đầu thuộc tập $X$, nhưng không thuộc tập “hẹp hơn” $Y$, $(Y \subset X)$.

Ví dụ 6. Giải phương trình

$$\text{tg} \left( x + \frac{\pi}{4} \right) = 2 \text{ctg} x - 1.$$

Lời giải. Biến đổi phương trình (12) về dạng

$$\frac{\text{tg} x + \text{tg} \frac{\pi}{4}}{1 - \text{tg} x \cdot \text{tg} \frac{\pi}{4}} = \frac{2}{\text{tg} x} - 1.$$

Đặt $y = \text{tg} x$, ta đi đến phương trình đại số theo $y$, giải phương trình này, được $y = \frac{1}{2}$, tức là $x = \text{arctg} \frac{1}{2} + \pi k$.

Nhưng phép kiểm tra cho thấy rằng các giá trị $x = \frac{\pi}{2} + \pi n$ cũng thỏa mãn phương trình (15). Vậy chúng ta đã làm mất những nghiệm này từ lúc nào? Hãy so sánh ĐKXĐ của các phương trình (14) và (15). X gồm tất cả các giá trị $x$, trừ những giá trị mà tại đó $ctg x$ và $\text{tg} \left( x + \frac{\pi}{4} \right)$ không tồn tại. Vậy,

$$X = \left\{ x \mid x \neq \pi n, x \neq \frac{\pi}{4} + \pi n \right\}.$$

ĐKXĐ của phương trình (16) — $Y$ — gồm tất cả các giá trị $x$, trừ những giá trị mà tại đó $ctg x = 0$, $\text{tg} x = 1$ và $\text{tg} x$ không tồn tại. Vậy,

$$Y = \left\{ x \mid x \neq \pi n, x \neq \frac{\pi}{4} + \pi n \right\}.$$

Từ đó suy ra rằng $Y \subset X$, tức là ĐKXĐ của phương trình (16) hẹp hơn ĐKXĐ của phương trình (15). Các giá trị $x = \frac{\pi}{2} + \pi n$ thuộc tập $X$, nhưng không thuộc tập nghiệm của phương trình ban đầu.

Bây giờ nảy sinh một câu hỏi quan trọng: điều gì đã dẫn đến việc thu hẹp miền xác định? Phân tích lời giải của ví dụ 6 cho thấy rằng việc sử dụng các công thức tang của tổng đã dẫn đến việc thu hẹp miền xác định, trong ví dụ của chúng ta công thức thuộc tập $X$, nhưng không thuộc tập «hẹp hơn» $Y$, $(Y \subset X)$.

Nguyên nhân thứ hai là chia cả hai vế của phương trình cho cùng một hàm. Giả sử $x_1$ — một nghiệm của phương trình (11), nhưng hoàn toàn không nhất thiết thỏa mãn phương trình (10). Như vậy,

⟦folio 51⟧

do đó, việc chia cả hai vế của phương trình cho cùng một hàm có thể dẫn đến mất nghiệm (cụ thể là các nghiệm của hàm-chia).

THAY CHO KẾT LUẬN

Vậy khi giải phương trình cần theo quy tắc chung nào? Chỉ một quy tắc: giải bất kỳ phương trình nào một cách có ý thức, không máy móc, không bỏ qua sự chú ý đối với bất kỳ bước chuyển đáng ngờ nào, nơi có thể xuất hiện nghiệm ngoại lai hoặc mất nghiệm. Trước khi bắt đầu giải phương trình, nên ghi ra mọi điều kiện xác định ĐKXĐ (thậm chí không nhất thiết phải giải chúng theo ẩn); chẳng hạn, khi giải phương trình (3) chỉ cần ghi ra các điều kiện: $x^2 + 3x - 4 > 0$ và $2x + 2 > 0$; khi kiểm tra, thấy ngay rằng một trong các nghiệm đã tìm được $x_2 = -3$ không thỏa mãn điều kiện $2x + 2 > 0$. Nếu trong quá trình giải phải thực hiện những bước chuyển mà có thể xuất hiện nghiệm ngoại lai, thì cuối cùng cần kiểm tra, và trong trường hợp này việc kiểm tra là một phần của lời giải bài toán, chứ không chỉ là sự kiểm soát bổ sung. Đôi khi trong quá trình giải, thuận tiện là chia tập giá trị của biến thành hai hoặc vài phần và nghiên cứu phương trình riêng trên mỗi phần; chẳng hạn, phương trình (14) khi $60 - 3x < 0$ hiển nhiên không có nghiệm, còn khi $60 - 3x \ge 0$ việc bình phương cả hai vế sẽ không dẫn đến xuất hiện nghiệm mới, vì cả hai vế của phương trình đều không âm (nghiệm ngoại lai $x_2 = 362$ tự động bị loại, vì không thỏa mãn điều kiện $60 - 3x \ge 0$).

Lời giải của mỗi phương trình phải có dạng một chứng minh định lý rằng phương trình đã cho được thỏa mãn bởi những số, và chỉ những số, được viết trong đáp số; đồng thời “cuộc đấu tranh” với nghiệm ngoại lai và với việc mất nghiệm khi biến đổi phải linh hoạt.

Bài tập

Giải các phương trình sau:

1. $\frac{x}{2x-1} + \frac{25}{4x^2-1} = \frac{1}{27} - \frac{13}{1-2x}$.
2. $\frac{x^2 - 3x + 2}{x} \left( \frac{x}{3^2 - 1} - 1 \right) = 0$.
3. $\sqrt{x+1} = 1 - \sqrt{2x+3}$.
4. $\sqrt{(x+16)(x-5)} + \sqrt{x^2 - 5x} + \sqrt{x^2 - 5x} + x = 40$.
5. $\log_{5x-2} 2 + 2 \log_{5x-2} x = \log_{5x-2} (x+1)$.
6. $\frac{\lg 2 + \lg (4 - 5x - 6x^2)}{\lg \sqrt{2x-1}} = 3$.
7. $tg x + tg 2x = tg 3x$.
8. $3 tg 2x + 2 ctg x + 3 = 0$.
