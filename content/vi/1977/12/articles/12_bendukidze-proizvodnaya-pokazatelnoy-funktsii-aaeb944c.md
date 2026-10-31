---
id: 1977-12-bendukidze-proizvodnaya-pokazatelnoy-funktsii-aaeb944c
issue: kvant_1977_12
year: 1977
number: "12"
title: Đạo hàm của hàm số mũ
authors:
  - Бендукидзе А. Д.
rubric: po-stranitsam-shkolnyh-uchebnikov
rubric_sub: По страницам школьных учебников
page_first: 42
page_last: 44
page_labels: 40, 42
tag: GJO6
lang: vi
source: kvant_digital
extraction: vision
content_sha256: c77bba5f210f5402ea83807d68c05602d58d0cf10b23f3baf20f09b60e086e15
prompt_sha256: draft-1
translated_from: content/ru/1977/12/articles/12_bendukidze-proizvodnaya-pokazatelnoy-funktsii-aaeb944c.md
source_content_sha256: 439cc2392ec4e572bf16b8f6d6917efd686bc257371de1bb71112fd8d76ec073
translation_model: draft
translation_run: vi-draft-2026-10-31
translation_quality: draft
---

⟦folio 40⟧

A. Bendukidze

Số mũ đạo hàm của hàm số

"Đồ thị của hàm $\exp_{10}$ trông giống như một đường cong "trơn". Trong chương, có vẻ như đồ thị này tại mỗi điểm có một tiếp tuyến, độ dốc của nó là dương. Do đó, người ta giả định một cách tự nhiên rằng hàm $\exp_{10}$ có tích dương cho bất kỳ giá trị nào của đối số. Giả thuyết này đúng, như đã được chứng minh trong các khóa phân tích đầy đủ hơn. Chúng tôi sẽ chấp nhận mà không cần bằng chứng rằng hàm $\exp_{10}$ có tích dương tại điểm 0. Trong Nói cách khác, chúng ta hãy giả sử rằng có một giới hạn

$$\lim_{\Delta x \to 0} \frac{10^0 + \Delta x - 10^0}{\Delta x} = \lim_{\Delta x \to 0} \frac{10^{\Delta x} - 1}{\Delta x} \cdot (1)$$

Mọi thứ tiếp theo sẽ diễn ra từ đây tương đối đơn giản.

Đây là cách đoạn 109 bắt đầu - "Chỉ báo đạo hàm của hàm số. Sách giáo khoa số $e$》 lớp 10 - "Đại số và sự khởi đầu của phân tích." Hơn nữa trong đoạn này, việc lựa chọn một công thức tính đạo hàm của hàm $\exp_{10}$ cũng như một công thức tổng quát hơn cho đạo hàm của hàm $\exp_a$, trong đó $a > 0, a \neq 1$.

Trên thực tế, tất cả những điều này đều xuất phát từ sự tồn tại của giới hạn (1) rất đơn giản.

Nhưng một sinh viên tò mò, tất nhiên là những độc giả «Kvant», có thể có một câu hỏi: “Tuy nhiên, làm thế nào sự tồn tại và dương của giới hạn (1) được chứng minh?” Bằng chứng về thực tế này, như đã nêu trong sách hướng dẫn, có thể được tìm thấy trong các khóa học phân tích đầy đủ. Có một thực tế tổng quát hơn đã được chứng minh, đó là: với mọi số dương $a \neq 1$ đều có giới hạn

$$\lim_{h \to 0} \frac{a^h - 1}{h},$$

và nó là dương nếu $a > 1$, và âm nếu $0 < a < 1$. Nhưng thực tế là việc chứng minh điều này, như một quy luật, dựa trên một số bổ đề và định lý sơ bộ, không phải lúc nào cũng dễ hiểu. Sẽ tốt hơn nếu đưa ra một bằng chứng không xác định. Bằng chứng như vậy được đưa ra dưới đây.

1. Đặt $a$ là một số tùy ý lớn hơn một. Hãy xem xét dãy $(x_n)$, số hạng tổng quát được cho bởi công thức

$$x_n = n \left( \frac{1}{a^n} - 1 \right).$$

Chứng minh rằng $(x_n)$ là dãy cộng và giới hạn của nó là dương.

Hãy bắt đầu với câu hỏi về sự hội tụ và kiểm tra các điều kiện của định lý Weierstrass. Đối với bất kỳ tự nhiên $n$

$$a^{-\frac{1}{n(n+1)}} - 1 > -1,$$

posnomu theo bất đẳng thức Bernoulli

$$a^{-\frac{1}{n}} = \left( 1 + \left( a^{-\frac{1}{n(n+1)}} - 1 \right) \right)^{n+1} > 1 + (n+1) \left( a^{-\frac{1}{n(n+1)}} - 1 \right).$$

Nhân bất đẳng thức này với $a^{\frac{1}{n}}$, ta được

$$1 > a^{\frac{1}{n}} + (n+1) \left( a^{\frac{1}{n+1}} - a^{\frac{1}{n}} \right)$$

hoặc, cái gì giống nhau,

$$n a^{\frac{1}{n}} + 1 > (n+1) a^{\frac{1}{n+1}}.$$

Rất dễ dàng đưa bất đẳng thức này về dạng sau:

$$n \left( a^{\frac{1}{n}} - 1 \right) > (n+1) \left( a^{\frac{1}{n+1}} - 1 \right).$$

⟦folio 42⟧

Vì vậy chúng tôi có
$$\begin{cases}
n \left( \frac{1}{n+1} - 1 \right) < \frac{a^h - 1}{h} < \\
< (n+1) \left( \frac{1}{n} - 1 \right), \text{ если } h > 0, \\
\frac{n \left( \frac{1}{n+1} - 1 \right)}{a^{n+1}} < \frac{a^h - 1}{h} < \\
< (n+1) \left( \frac{1}{n} - 1 \right), \text{ если } h < 0.
\end{cases}$$

Hãy giới thiệu ký hiệu sau:
$$n \left( \frac{1}{n+1} - 1 \right) = u_n,$$
$$(n+1) \left( \frac{1}{n} - 1 \right) = v_n,$$
$$\frac{u_n}{a^{n+1}} = u'_n, \quad \frac{v_n}{a^{n+1}} = v'_n.$$

Khi đó các bất đẳng thức thu được sẽ có dạng sau:
$$\begin{cases}
u_n < \frac{a^h - 1}{h} < v_n, \text{ если } h > 0, \\
u'_n < \frac{a^h - 1}{h} < v'_n, \text{ если } h < 0,
\end{cases}$$

và với mọi $h$, modulo $1/n$,

$$u'_n < \frac{a^h - 1}{h} < v_n.$$ (5)

Hãy để bây giờ $n \rightarrow +\infty$. Sau đó
$$\lim_{n \rightarrow +\infty} u_n = \lim_{n \rightarrow +\infty} v_n = \lim_{n \rightarrow +\infty} u'_n =$$
$$= \lim_{n \rightarrow +\infty} v'_n = \varphi(a).$$

Trên thực tế, kể từ khi
$$u_n = (n+1) \left( \frac{1}{n+1} - 1 \right) - \left( a^{n+1} - 1 \right) = x_{n+1} - \left( a^{n+1} - 1 \right),$$
$$v_n = n \left( a^{n+1} - 1 \right) + \left( a^{n+1} - 1 \right) = x_n + \left( a^{n+1} - 1 \right),$$

thì theo đẳng thức (3) và (4)
$$\lim_{n \rightarrow +\infty} u_n = \lim_{n \rightarrow +\infty} x_{n+1} - \lim_{n \rightarrow +\infty} \left( a^{n+1} - 1 \right) =$$
$$= \lim_{n \rightarrow +\infty} x_{n+1} = \varphi(a).$$

Hơn nữa, theo cùng một đẳng thức (4)
$$\lim_{n \rightarrow +\infty} a^n = \lim_{n \rightarrow +\infty} a^{n+1} = 1,$$
và do đó
$$\lim_{n \rightarrow +\infty} u'_n = \lim_{n \rightarrow +\infty} \frac{u_n}{a^{n+1}} =$$
$$= \lim_{n \rightarrow +\infty} u_n = \varphi(a), \lim_{n \rightarrow +\infty} v'_n =$$
$$= \lim_{n \rightarrow +\infty} \frac{v_n}{a^{n+1}} = \varphi(a).$$

Lưu ý rằng chuỗi $\{v_n\}$ tắt một cách đơn điệu và $\{u'_n\}$ trả về.

Vì vậy, chúng tôi đã đi đến kết luận sau (xem hình): nếu $0 < |h| \leq 1$, thì mối quan hệ mà chúng tôi quan tâm, tức là $(a^h - 1):h$, có thể được “kẹp” vào khoảng $]u_n, v'_n$ [(if $h > 0$) hoặc vào khoảng $]u'_n, v'_n$ [(if $h < 0$) và với xu hướng $n \rightarrow +\infty$ thì các điểm cuối của các khoảng này có xu hướng cùng một số $\varphi(a)$. Rõ ràng là nếu không thì tỷ lệ này có xu hướng về cùng một số, tức là
$$a > 1 \Rightarrow \lim_{h \rightarrow 0} \frac{a^h - 1}{h} = \varphi(a) > 0.$$

Thật vậy, mọi $\varepsilon > 0$ đều có thể xảy ra và chúng ta sẽ tìm một $\delta > 0$ sao cho
$$|h| < \delta \Rightarrow |\varphi(a) - \frac{a^h - 1}{h}| < \varepsilon.$$

(Theo định nghĩa giới hạn của hàm số, điều này sẽ có nghĩa là $\lim_{h \rightarrow 0} (1/h) \times (a^h - 1) = \varphi(a)$).

Vì các chuỗi $\{u'_n\}$ và $\{v'_n\}$ hội tụ về $\varphi(a)$, hơn nữa, chuỗi thứ nhất tăng và chuỗi thứ hai tiêu diệt, nên với một số cho trước $\varepsilon > 0$ người ta có thể tìm thấy một số $N$ sao cho
$$-\varepsilon < u'_N - \varphi(a) \text{ и } v_N - \varphi(a) < \varepsilon.$$ (6)

Bây giờ chúng ta hãy lấy $\delta = 1/N$. Nếu $|h| < \delta = 1/N$, thì ta có (xem (5)) các bất đẳng thức
