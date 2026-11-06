---
id: 1990-4-izhboldin-kurlyandchik-neravenstvo-iensena-0d850e28
issue: kvant_1990_4
year: 1990
number: "4"
title: Bất đẳng thức Jensen
authors:
  - Ижболдин О. Т.
  - Курляндчик Л. Д.
rubric: matematicheskiy-kruzhok
rubric_sub: Математический кружок
page_first: 59
page_last: 63
page_labels: 57, 58, 59, 61
lang: vi
source: kvant_digital
extraction: vision
content_sha256: 68c252ff922f44869da0e747f18f64102c0e9bce71978d85f5f67c56794d4583
prompt_sha256: draft-1
translated_from: content/ru/1990/04/articles/15_izhboldin-kurlyandchik-neravenstvo-iensena-0d850e28.md
source_content_sha256: 2eff30638d5aae031b3e1d22a6ed15aa28be10dcd634d546ce57c674fa9c9b0e
translation_model: draft
translation_run: vi-draft-gaps-2026-11-05
translation_quality: draft
---

⟦folio 57⟧

---
running_head:
folio:
---

Bất bình đẳng
Jensen
O. IZHVOLDIN, L. KURLYANDCHIK

$$\sum_{k=1}^{n} a_k = a_1 + a_2 + \dots + a_n,$$
$$\prod_{k=1}^{n} a_k = a_1 \cdot a_2 \cdot \dots \cdot a_n.$$

Chúng tôi khuyên những người chưa học
sử dụng chúng, mô tả bạn-
khối xây chi tiết hơn.

Kĩ thuật chứng minh bất đẳng thức
làm chủ là không dễ dàng. Điều này đòi hỏi nhiều kinh nghiệm, trực giác và
như trong mọi nghệ thuật, khả năng tự do áp dụng các kỹ thuật “kỹ thuật” khác nhau. Chúng tôi sẽ chứng minh một kỹ thuật như vậy bằng cách sử dụng một số ví dụ. Bài viết này sẽ chứng minh cả các bất đẳng thức cổ điển (Cauchy, Cauchy-Bunyakovsky, Hölder và Minkowski), cũng như những bất đẳng thức ít nổi tiếng hơn nhưng cũng rất thú vị.

Chúng ta sẽ viết các công thức, thường là ngắn gọn, sử dụng ký hiệu

Việc chứng minh các bất đẳng thức sẽ được thảo luận dựa trên khái niệm độ lồi. Đây là một khái niệm toán học rất quan trọng và bạn đã gặp nó trong khóa học hình học ở trường khi nghiên cứu về đa giác. Tuy nhiên, trong toán học, khái niệm độ lồi không chỉ gắn liền với đa giác. Một hình được gọi là lồi nếu với hai tính chất bất kỳ của điểm, nó chứa toàn bộ đoạn thẳng có điểm cuối tại các điểm này. Hình 1, a-2 thể hiện các ví dụ về hình lồi và không lồi. Bạn-

57

⟦folio 58⟧

---
running_head:
folio:
---

hình lồi có nhiều tính chất đáng chú ý, nhưng chúng ta sẽ chỉ quan tâm đến một trong số chúng. Hãy hình thành nó.
Đặt khối lượng $m_1, m_2, \dots, m_n$ lần lượt tập trung tại các điểm $A_1, A_2, \dots, A_n$ của hình lồi Ф. Khi đó khối tâm của các điểm này cũng thuộc hình F.
Vật lý học cho rằng khối tâm là một điểm có tọa độ
$$\left( \frac{\sum_{i=1}^{n} m_i x_i}{\sum_{i=1}^{n} m_i}; \frac{\sum_{i=1}^{n} m_i y_i}{\sum_{i=1}^{n} m_i} \right),$$
trong đó $x_i, y_i$ là tọa độ của điểm $A_i$.

Urazhennya
1. Chứng minh rằng khối tâm của hai điểm nằm trên đoạn nối chúng.
2. Chứng minh rằng khối tâm của các điểm $n$ nằm trên đoạn nối bất kỳ điểm nào trong số chúng với khối tâm của các điểm còn lại.

Hình lồi
Hãy vẽ đồ thị của hàm số $y = x^2$ (hình 2, a).

Hình 1.
Hình 2.

Chúng ta thấy rằng biểu đồ của hình này (tại hình nó có màu đỏ) là một hình lồi. Nếu chúng ta xem xét hình $y = \sin x$ ($x \in [0; \pi]$), thì biểu đồ của nó (trên hình 2, b nó có màu đỏ) không lồi. Tuy nhiên, đồ thị con của hình này là lồi (trên cùng hình nó được tô cùng một màu).

Những quan sát này dẫn đến một định nghĩa quan trọng.

Nếu biểu đồ của figuntia là hình lồi thì người ta nói rằng figuntia này là lồi, còn nếu biểu đồ con lồi thì họ nói rằng figuntia là voguntai *).

Do đó, figuncia $y = x^2$ là lồi và figuncia $y = \sin x$ ($x \in [0; \pi]$) là vogunt.

Bất đẳng thức cơ bản
Trong số các giá trị trung bình của các bất đẳng thức cổ điển nổi tiếng, bất đẳng thức Jensen** chiếm một vị trí đặc biệt. Tất cả các bất đẳng thức cổ điển nêu ở đầu bài đều là hệ quả của nó.

Định lý (bất đẳng thức Jensen). Giả sử $y = f(x)$ là một hình lồi trên một khoảng nào đó, $x_1, x_2, \dots, x_n$ là các số tùy ý trong khoảng này, $a, \alpha_1, \alpha_2, \dots, \alpha_n$ là các số dương tùy ý có tổng bằng một. Sau đó

$$f(\alpha_1 x_1 + \dots + \alpha_n x_n) \leqslant \alpha_1 f(x_1) + \dots + \alpha_n f(x_n).$$

Bằng chứng. Chúng ta hãy xem xét trên đồ thị của hình $y = f(x)$ các điểm $A_1, A_2, \dots, A_n$ có hoành độ $x_1, x_2, \dots, x_n$. Chúng ta hãy đặt các vật nặng có khối lượng $m_1, m_2, \dots, m_n$ tại những điểm này. Khối tâm của các điểm này có tọa độ

$$\left( \frac{m_1 x_1 + \dots + m_n x_n}{m_1 + \dots + m_n}; \frac{m_1 f(x_1) + \dots + m_n f(x_n)}{m_1 + \dots + m_n} \right).$$

*) Một số sách giáo khoa sử dụng thuật ngữ khác nhau.
**) Jensen Johann Ludwig (1859-1925) - Nhà toán học Đan Mạch.

⟦folio 59⟧

---
running_head:
folio:
---

Vì các điểm $A_1, A_2, \dots, A_n$ thuộc đồ thị của một hàm lồi nên trọng tâm của chúng cũng thuộc đồ thị (vì đồ thị là một hàm lồi). Và điều này có nghĩa là tọa độ của khối tâm không nhỏ hơn tọa độ của điểm trên đồ thị có cùng hoành độ (hình 3), tức là.

$$f\left(\frac{m_1x_1 + \dots + m_nx_n}{m_1 + \dots + m_n}\right) \leqslant \frac{m_1f(x_1) + \dots + m_nf(x_n)}{m_1 + \dots + m_n}.$$ (3)

Để hoàn thành việc chứng minh, tất cả những gì còn lại là đặt $m_1 = \alpha_1, \dots, m_n = \alpha_n$.

Chúng tôi muốn kết thúc điểm này của bài viết bằng hai nhận xét quan trọng. Đầu tiên, trong quá trình chứng minh bất đẳng thức Jensen (2), ta đã chứng minh được bất đẳng thức (3). Thật ra các bất đẳng thức này là tương đương. Thay $\alpha_i = \frac{m_i}{m_1 + \dots + m_n} (i = 1, 2, \dots, n)$ vào bất đẳng thức (2), ta thu được bất đẳng thức (3). Do đó, tất nhiên cả hai bất đẳng thức này đều được gọi là bất đẳng thức Jensen. Bất đẳng thức (2) trông gọn hơn nhưng đối với các ứng dụng thì sử dụng bất đẳng thức (3) sẽ thuận tiện hơn. Thứ hai, nếu hàm $f(x)$ lõm, thì các bất đẳng thức Jensen (2) và (3) bị đảo ngược. Để chứng minh điều này, chỉ cần xét hàm lồi $f(x)$.

Bất đẳng thức Cauchy–Bunyakovsky

Thoạt nhìn, bất đẳng thức Jensen không gây nhiều ấn tượng: cách trình bày quá chung chung. Sau khi đọc hết bài viết này, bạn sẽ thấy rằng ấn tượng này là lừa đảo.

Chúng ta hãy chứng minh sức mạnh của bất đẳng thức Jensen bằng một ví dụ cụ thể. Cụ thể, chúng ta sẽ chứng minh bất đẳng thức Cauchy–Bunyakovsky nổi tiếng:

$$(a_1^2 + \dots + a_n^2)(b_1^2 + \dots + b_n^2) \geqslant (a_1b_1 + \dots + a_nb_n)^2,$$

trong đó $a_1, a_2, \dots, a_n, b_1, b_2, \dots, b_n$ là các số dương tùy ý.

Bằng chứng. Như chúng ta đã biết, hàm $y = x^2$ là hàm lồi. Hãy viết bất đẳng thức Jensen (3) cho hàm này

$$\left(\frac{m_1x_1 + \dots + m_nx_n}{m_1 + \dots + m_n}\right)^2 \leqslant \frac{m_1x_1^2 + \dots + m_nx_n^2}{m_1 + \dots + m_n} (m_i > 0).$$

Vì vậy, $(m_1x_1^2 + \dots + m_nx_n^2) \times (m_1 + \dots + m_n) \geqslant (m_1x_1 + \dots + m_nx_n)^2$.

Đặt $m_i = b_i^2$, $x_i = \frac{a_i}{b_i}$, ta thu được bất đẳng thức cần tìm.

Bài tập 3. Chứng minh bất đẳng thức Cauchy–Bunyakovsky cho số thực tùy ý $a_i, b_i$.

Ví dụ về hàm lồi

Để áp dụng thành công bất đẳng thức Jensen, bạn cần một phép tính đơn giản

⟦folio 61⟧

---
running_head:
folio:
---

$$\left( \frac{\sum m_i x_i}{\sum m_i} \right)^p \leqslant \frac{\sum m_i x_i^p}{\sum m_i}.$$

Từ đây
$$\sum m_i x_i \leqslant \left( \sum m_i \right)^{\frac{p-1}{p}} \left( \sum m_i x_i^p \right)^{\frac{1}{p}}.$$

Vì $\frac{1}{p} + \frac{1}{q} = 1$, thì $\frac{p-1}{p} = \frac{1}{q}$, và do đó
$$\sum m_i x_i \leqslant \left( \sum m_i x_i^p \right)^{\frac{1}{p}} \left( \sum m_i \right)^{\frac{1}{q}}.$$

Bây giờ đặt $m_i = b_i^q$, $x_i = a_i b_i^{1-q}$, chúng ta thu được bất đẳng thức cần thiết.

Bất đẳng thức Minkowski
$$\sqrt[n]{a_1 \cdots a_n} + \sqrt[n]{b_1 \cdots b_n} \leqslant$$
$$\leqslant \sqrt[n]{(a_1 + b_1) \cdots (a_n + b_n)} (a_i, b_i > 0).$$

Bằng chứng. Chia cả hai vế của bất đẳng thức cho $\sqrt[n]{a_1 \cdots a_n}$, ta được
$$1 + \left( \frac{b_1}{a_1} \right)^{\frac{1}{n}} \cdots \left( \frac{b_n}{a_n} \right)^{\frac{1}{n}} \leqslant$$
$$\leqslant \left( 1 + \frac{b_1}{a_1} \right)^{\frac{1}{n}} \cdots \left( 1 + \frac{b_n}{a_n} \right)^{\frac{1}{n}}.$$

Rõ ràng là phân số $\frac{b_i}{a_i}$ có ý nghĩa khi được chỉ định bằng cách nào đó. Nhưng trên thực tế, sẽ thuận tiện hơn khi đưa ra một ký hiệu không phải cho phân số $\frac{b_i}{a_i}$ mà cho logarit của nó:
$$x_i = \ln \frac{b_i}{a_i}$$. Vì vậy, thay thế $\frac{b_i}{a_i}$ bằng $e^{x_i}$, chúng ta viết bất đẳng thức dưới dạng
$$1 + e^{\sum \frac{1}{n} x_i} \leqslant \Pi \left( 1 + e^{x_i} \right)^{\frac{1}{n}}.$$

Chúng ta hãy lấy logarit của cả hai vế của bất đẳng thức thu được:
$$\ln \left( 1 + e^{\sum \frac{1}{n} x_i} \right) \leqslant \sum \frac{1}{n} \ln \left( 1 + e^{x_i} \right).$$

Trong bất đẳng thức trước, chúng ta đã học bất đẳng thức Jensen cho hàm lồi $y = \ln \left( 1 + e^{x_i} \right)$ (Ví dụ 4).

Một số ví dụ về sử dụng bất đẳng thức Jensen
Bài toán 1. Chứng minh bất đẳng thức
$$\Pi a_i^a \geqslant \left( \sum \frac{1}{n} a_i \right)^{\sum a_i} (a_i > 0).$$

Lời giải. Tính cả hai vế của bất đẳng thức rồi chia cho $n$, ta được
$$\sum \frac{1}{n} a_i \ln a_i \geqslant \left( \sum \frac{1}{n} a_i \ln \sum \frac{1}{n} a_i \right).$$

Và đây là bất đẳng thức Jensen cho hàm lồi $y = x \ln x$ (ví dụ 5).

Bài toán 2. Chứng minh bất đẳng thức:
$$\sqrt{\left( \sum a_i \right)^2 + \left( \sum b_i \right)^2} \leqslant \sum \sqrt{a_i^2 + b_i^2} (a_i, b_i > 0).$$

Lời giải. Chúng ta viết bất đẳng thức Jensen (3) cho hàm lồi $y = \sqrt{1 + x^2}$ (ví dụ 6):
$$\sqrt{1 + \left( \frac{\sum m_i x_i}{\sum m_i} \right)^2} \leqslant \sum \frac{\sum m_i \sqrt{1 + x_i^2}}{\sum m_i}.$$

Nhân cả hai vế của bất đẳng thức với $\sum m_i$, ta được
$$\sqrt{\left( \sum m_i \right)^2 + \left( \sum m_i x_i \right)^2} \leqslant$$
$$\leqslant \sum m_i \sqrt{1 + x_i^2} = \sum \sqrt{m_i^2 + (m_i x_i)^2}.$$

Tất cả những gì còn lại là đặt $m_i = a_i$, $x_i = \frac{b_i}{a_i}$.

Để kết luận, chúng tôi xem xét bài toán khá khó, cũng có thể được giải bằng bất đẳng thức Jensen.

Bài toán 3. Chứng minh bất đẳng thức
$$\frac{p_1}{p_2 + p_3} + \frac{p_2}{p_3 + p_4} + \frac{p_3}{p_4 + p_5} +$$
$$+ \frac{p_4}{p_5 + p_1} + \frac{p_5}{p_1 + p_2} \geqslant \frac{5}{2} (p_i > 0).$$

Lời giải. Để thuận tiện, chúng tôi giới thiệu các biến bổ sung $p_6$ và $p_7$, tương ứng bằng $p_1$ và $p_2$. Teler, bất đẳng thức này có thể viết ngắn gọn:
$$\sum_{i=1}^{5} \frac{p_i}{p_i+1+p_i+2} \geqslant \frac{5}{2}.$$

Hãy biểu diễn bất đẳng thức Jensen (3) cho hàm lồi $y = \frac{1}{x}$ (ví dụ 1):
