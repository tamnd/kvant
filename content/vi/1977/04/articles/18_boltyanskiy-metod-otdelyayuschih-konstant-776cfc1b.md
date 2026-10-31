---
id: 1977-4-boltyanskiy-metod-otdelyayuschih-konstant-776cfc1b
issue: kvant_1977_4
year: 1977
number: "4"
title: Phương pháp tách hằng số
authors:
  - Болтянский В. Г.
rubric: praktikum-abiturienta
rubric_sub: Практикум абитуриента
page_first: 48
page_last: 51
page_labels: 46, 47, 49
tag: 678B
lang: vi
source: kvant_digital
extraction: vision
content_sha256: e2f1f6679bed26656deb139bc020ee734315eb254a1bd8a6588a201a97d6ce5b
prompt_sha256: draft-1
translated_from: content/ru/1977/04/articles/18_boltyanskiy-metod-otdelyayuschih-konstant-776cfc1b.md
source_content_sha256: fbce771986a5556946ca65fe6ed010ecf565da35df73c074b5eed5edc28623a5
translation_model: draft
translation_run: vi-draft-2026-10-31
translation_quality: draft
---

⟦folio 46⟧

Trong hầu hết các trường hợp, bài toán, lời giải đã được đưa vào thực hành bài thi viết dành cho ứng viên đại học, thuận tiện khi bắt đầu bằng việc tìm tập hợp các giá trị được một số hàm chấp nhận. Nếu không thì lời giải bài toán đây là nơi nó kết thúc, từ kết quả thu được nó ngay sau đáp số; trong các trường hợp khác, giá trị hàm được đặt làm giảm đáng kể khối lượng công việc, chỉ ra đường đi ngắn nhất tới đáp số.

Một số tính năng của việc áp dụng phương pháp này sẽ được thảo luận trong bài viết này.

Bằng chứng về sự bất đẳng thức
Hãy bắt đầu với bài toán tiếp theo.

Ví dụ 1. Chứng minh bất đẳng thức
$$x^2 - 2x \geq -3 + \sin x.$$ (1)

Đối với lời giải, chỉ cần lưu ý rằng tia [−1;∞], là tập hợp các giá trị hàm
$$f(x) = x^2 - 2x = (x - 1)^2 - 1,
$$ không giao nhau với tập giá trị hàm
$$g(x) = -3 + \sin x,
$$ tức là với đoạn [−4; −2].

Chúng ta có thể nói theo cách khác: sucestium là bất kỳ số c nào (ví dụ: c = −3/2), với mọi x ∈ R đều đúng $$f(x) > c, c > g(x)$$ (Hình 1), nó chỉ mở ra các bất đẳng thức (1), nhưng cũng là bất đẳng thức mạnh hơn: $$f(x) > g(y)$$ với mọi x, y ∈ R, nghĩa là luôn luôn
$$x^2 - 2x > -3 + \sin y.$$

Trong các ví dụ phức tạp hơn, không còn có thể tìm thấy hằng số c “tách” các giá trị của hàm f(x) khỏi các giá trị của hàm g(x) trên toàn bộ miền đặc tả của chúng, nhưng trục số có thể được chia thành nhiều khoảng, mỗi khoảng có hằng số phân tách riêng.

Ví dụ 2. Chứng minh bất đẳng thức
$$\arctg x > 4\sqrt{3}x - x^2 - 11.$$ (2)

Trong trường hợp này, trên tia ] −∞; √3[ (nghĩa là với −∞ < x < √3), hằng số tách như vậy là c₁ = −2 (Hình 2), và trên tia [√3;∞] chúng ta có thể lấy hằng số tách c₂ = 1,01.

Tất nhiên, biểu đồ trong Hình 2 chỉ minh họa những gì đã nói; bằng chứng đầy đủ, dựa trên ý tưởng tách các hằng số, có thể được phát biểu, chẳng hạn như sau. Chức năng
$$f(x) = \arctg x$$
với mọi x ∈ R (và đặc biệt, với x < √3) thỏa mãn bất đẳng thức
$$f(x) > -\frac{\pi}{2} > -2,$$ tức là f(x) > c₁.
Mặt khác, hàm số g(x) = 4√3x - x² - 11 =
$$= -(x - 2\sqrt{3})^2 + 1$$
tại x = √3 nhận giá trị

⟦folio 47⟧

$$g(\sqrt{3}) = -2 = c_1,$$
và theo điểm $x = \sqrt{3}$ hàm này tăng lên, do đó $g(x) < c_1$ tại $x < \sqrt{3}$. Vì vậy, $f(x) > c_1 > g(x)$ đối với $x < \sqrt{3}$, nghĩa là đối với các giá trị $x$ này, bất đẳng thức (2) là hợp lệ. Vẫn còn phải xem xét các giá trị của $x \geqslant \sqrt{3}$.

Lưu ý rằng $f(\sqrt{3}) = \arctg \sqrt{3} = \pi/3 > 1,01$ và hàm $f(x)$ đang tăng dần, do đó $f(x) > c_2$ cho $x \geqslant \sqrt{3}$. Đối với hàm $g(x)$, thì với bất kỳ $x \in \mathbb{R}$ nào (và đặc biệt là đối với $x \geqslant \sqrt{3}$), chúng ta có $g(x) \leqslant 1 < c_2$.

Do đó, $f(x) > c_2 > g(x)$ cho $x \geqslant \sqrt{3}$, tức là với các giá trị $x$ này, bất đẳng thức (2) là hợp lệ.

Phương pháp được coi là chứng minh sự bất đẳng thức trong mọi thứ nên được coi là tao nhã, ngẫu nhiên, hiếm khi được sử dụng. Ví dụ, đối với các hàm liên tục, kỹ thuật này có thể được coi là phổ quát. Trên thực tế, chẳng hạn, giả sử các hàm liên tục $f(x)$ và $g(x)$ được cho trên khoảng $[a; b]$ và sau khi ước tính dạng của các đồ thị này, chúng ta phát hiện ra rằng bất đẳng thức $f(x) > g(x)$ dường như đúng trên toàn bộ khoảng này. Làm thế nào người ta có thể chứng minh sự bất đẳng thức này là đúng?

Nếu bất đẳng thức $f(x) > g(x)$ đúng với mọi $x \in [a; b]$ thì đồ thị của hàm $f(x)$ và $g(x)$ không có điểm chung và do đó có thể* vẽ một “đường gãy bậc” (Hình 3), tách đồ thị của hàm $y = f(x)$ khỏi đồ thị của hàm $y = g(x)$. Nhưng điều này có nghĩa là đoạn $[a; b]$ có thể được chia thành nhiều đoạn nhỏ hơn, trên mỗi đoạn đó có một hằng số riêng biệt $c_i$.

Tất nhiên, trong cách lập luận này, quyết định chỉ liên quan đến sự xuất hiện cơ bản của việc chứng minh các bất đẳng thức $f(x) > g(x)$ bằng phương pháp hằng số riêng biệt. Trong mỗi trường hợp cụ thể, nghệ thuật sử dụng kỹ thuật này là tìm ra cách chia thích hợp của đoạn $[a; b]$ thành các phần và đối với mỗi phần này hãy chỉ ra hằng số tương ứng với phần đó.

**Lặp lại**

Trong trường hợp chung, rất khó để đưa ra khuyến nghị về cách chọn phân vùng và các hằng số riêng lẻ tương ứng. Tuy nhiên, trong một số trường hợp, khuyến nghị có thể được đưa ra.

Ví dụ: giả sử cả hai hàm $f(x)$, $g(x)$ đều tăng (hoặc không giảm) và $f(a) > g(a)$. Hãy vẽ một đường thẳng $y = f(a)$ (Hình 4) và xét giao điểm của nó với đồ thị của hàm số $y = g(x)$. Trục hoành của điểm này được ký hiệu là $x_1$. Trên đoạn $[a; x_1]$ chúng ta có thể lấy số $c_1 = f(a)$ làm hằng số riêng biệt. Thật vậy, trên toàn bộ đoạn này, các bất đẳng thức $f(x) \geqslant c_1$, $g(x) \leqslant c_1$ được thỏa mãn và bất đẳng thức thứ nhất chỉ chuyển thành đẳng thức ở đầu bên trái của đoạn $[a; x_1]$ và bất đẳng thức thứ hai chỉ ở bên phải. Từ đây

*) Trên thực tế, từ “có thể” này ẩn chứa cả một định lý toán học phức tạp, điều mà tất nhiên chúng tôi sẽ không chứng minh ở đây.

⟦folio 49⟧

Lời giải phương trình

Phương pháp tách hằng số có thể được sử dụng không chỉ để chứng minh sự thiếu hụt để chứng minh sự thiếu sót mà trong một số trường hợp còn dùng cho phương trình lời giải chứ không phải phương trình gần đúng mà là phương trình chính xác lời giải.

Ví dụ 4. phương trình Lời giải $x^2 - 2x\sin x - 2\cos x + 2 = 0$. (4) Viết phương trình dưới dạng

$$(x - \sin x)^2 = -(1 - \cos x)^2,$$

nghĩa là ở dạng $f(x) = g(x)$, trong đó

$$f(x) = (x - \sin x)^2,$$

$$g(x) = -(1 - \cos x)^2.$$

Rõ ràng, với mọi $x \in \mathbb{R}$ thì các bất đẳng thức $f(x) \geq 0$, $g(x) \leq 0$ đều đúng. Từ đây rõ ràng rằng một số nhất định $x_0$ chỉ có thể thỏa mãn đẳng thức $f(x_0) = g(x_0)$, tức là là nghiệm của phương trình (4), nếu đẳng thức $f(x_0) = 0$, $g(x_0) = 0$ được thỏa mãn, tức là nếu $x_0$ là nghiệm của hệ

$$\begin{cases} x - \sin x = 0, \\ 1 - \cos x = 0. \end{cases}$$

Phương trình thứ hai của hệ này có nghiệm $x = 2k\pi (k = 0, \pm 1, \pm 2, \ldots)$, trong đó chỉ có nghiệm $x = 0$ thỏa mãn phương trình thứ nhất. Do đó, phương trình ban đầu có một nghiệm duy nhất $x = 0$.

Ví dụ 5. phương trình Lời giải

$$x^3 - 2x^2 + x + 1 = \sqrt{\sin \frac{\pi x}{2}}.$$ (5)

Phương trình này có thể được viết là $f(x) = g(x)$, trong đó

$$f(x) = x^2 - 2x^2 + x + 1,$$

$$g(x) = \sqrt{\sin \frac{\pi x}{2}}.$$

Vì $f(x) = 1 + x(x - 1)^2$, thì $f(x) \geq 1$ cho tất cả $x \geq 0$. Đồng thời, $g(x) \leq 1$ cho tất cả $x$ thuộc miền định nghĩa của hàm số $g(x)$. Do đó, trên tia $x \geq 0$ số $c = 1$ là hằng số phân tách của hàm $f(x)$ và $g(x)$. Theo đó, số không âm $x_1 = 1$, $x_2 = 0$, trong đó chỉ $x_1$ thỏa mãn phương trình thứ hai. Vì vậy, phương trình (5) chỉ có một nghiệm không âm $x_1 = 1$.

Bây giờ chúng ta hãy xem liệu có gốc âm nào không. Vì ở $-2 < x < 0$ hàm $g(x)$ không được xác định nên các nghiệm âm chỉ được tìm trên tia $x \leq -2$. Nhưng đối với $x \leq -2$, chúng ta có $f(x) = 1 + x(x - 1)^2 \leq 1 - 2 \cdot 3^2 = -17$ và $g(x) \geq 0$ theo định nghĩa của hàm $\sqrt{x}$. Do đó, dấu phân cách cho $f(x)$ và $g(x)$ trên tia $x \leq -2$ (tại các điểm $x$ mà hàm $g(x)$ được xác định), chẳng hạn như số $c = -10$. Do đó, phương trình nghiệm không âm được xem xét, tức là $x_1 = 1$ là nghiệm duy nhất của phương trình (5).

Chúng ta hãy lưu ý rằng để kết luận rằng, mặc dù có tính phổ quát, nhưng phương pháp tách CONSTANT không phải lúc nào cũng là phương tiện thuận tiện nhất để chứng minh một bất đẳng thức cụ thể. Ví dụ, để chứng minh bất đẳng thức $tg x > 4x - 2,5$ trên khoảng $[0; \pi/2]$ (xem Ví dụ 3), người ta có thể sử dụng thực tế là hàm tùy ý $\varphi(x) = tg x - 4x + 2,5$ bằng $\frac{1}{\cos^2 x} - 4$ chỉ biến mất tại một điểm trong khoảng này, cụ thể là tại $x = \pi/3$. Tại thời điểm này, giá trị của hàm $\varphi(x)$ là dương:

$$\varphi(\pi/3) = tg \frac{\pi}{3} - 4 \cdot \frac{\pi}{3} + 2,5 \approx 0,04.$$

Ở cuối tích phân, hàm $\varphi(x)$ nhận các giá trị lớn: $\varphi(0) = 2,5$ và $\varphi(x) \to \infty$, nếu $x \to \pi/2$ (nhưng $x < \pi/2$). Từ đây bạn có thể
