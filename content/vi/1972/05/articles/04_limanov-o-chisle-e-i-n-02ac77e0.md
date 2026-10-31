---
id: 1972-5-limanov-o-chisle-e-i-n-02ac77e0
issue: kvant_1972_5
year: 1972
number: "5"
title: Về số e và n!
authors:
  - Лиманов Л. Г.
rubric: matematicheskiy-kruzhok
rubric_sub: Математический кружок
page_first: 16
page_last: 21
page_labels: 14, 15, 16, 18
tag: YNV0
lang: vi
source: kvant_digital
extraction: vision
content_sha256: 6c8652822f380b2beb494aba45f865c29dfabf1d4cc606cba70940873f6d706a
prompt_sha256: draft-1
translated_from: content/ru/1972/05/articles/04_limanov-o-chisle-e-i-n-02ac77e0.md
source_content_sha256: c3a0815a4d01d792946f6e0a0c627ea58e2f4726c450a2980de7d5d0c522d0e8
translation_model: draft
translation_run: vi-draft-2026-10-31
translation_quality: draft
---

⟦folio 14⟧

Về số e và n!
L. G. LIMANOV

Trong ghi chú này, chúng tôi sẽ phân tích bài toán từ M.I. Bài báo của Bashmkov “Về sự xuất hiện của Bertrand” (xem «Kvant» Số 5, 1971).

Hãy nhớ lại rằng quy trình của Bertrand được gọi là phép lặp sau: nếu $x > 1$, thì có một số nguyên tố nằm giữa $x$ và $2x$.

Tuyên bố này được đưa ra bởi nhà toán học người Pháp Bertrand, nhưng ông không thể tìm thấy bằng chứng cho nó. Chebyshev đã làm được điều này và thực hiện nó khá đơn giản. Đúng, anh ấy đã sử dụng một công thức không sơ cấp - công thức Stirling:

$$n! = \sqrt{2\pi n} \left(\frac{n}{e}\right)^n e^{\theta_n/12n},$$

ở đâu $0 < \theta_n < 1$.

Công thức này có lẽ bao gồm hai con số đáng chú ý nhất. Đầu tiên là con số nổi tiếng $n$ - tỷ lệ giữa chu vi của một hình tròn với đường kính của nó. số thứ hai là số $e$—giới hạn của dãy $\left(\frac{n+1}{n}\right)^n$ vì $n$ tiến tới vô cùng. Chebyshev cần công thức này để ước tính các giá trị của $n! = 1 \cdot 2 \cdot \dots \cdot n$.

Trên thực tế, để chứng minh hành động của Bertrand, người ta có thể sử dụng những ước tính kém chính xác hơn đáng kể về giá trị $n$!

Chính những ước tính này đã được yêu cầu người đọc chứng minh trong bài viết của Bashmkov (bài toán 3). Từ việc phân tích bài toán này, chúng tôi sẽ dạy.

Đây là cách diễn đạt của nó:

Chứng minh rằng tồn tại một số thực $e$ sao cho với mọi $n$ tự nhiên, không comoroso lớn $n_0$,

$$\left(\frac{n+1}{e}\right)^n < n! < n \left(\frac{n}{e}\right)^n.$$

Các bất đẳng thức $\left(\frac{n+1}{e}\right)^n < n! < n \left(\frac{n}{e}\right)^n$ có thể được sử dụng cùng với các công thức Stirling. Tất nhiên, chúng kém chính xác hơn, nhưng chúng dễ chứng minh hơn nhiều.

Trên thực tế, bài toán còn lại của bài viết là các bổ đề từ chứng minh của Chebyshev về thủ tục Bertrand. Việc giải chúng dễ hơn nhiều so với bài toán 3. Công lao của Chebyshev không phải là ông đã giải được chúng - điều này không khó thực hiện - mà là ông đã xây dựng chúng và tìm ra cách, bằng cách sử dụng các phát biểu này, để thu được ước tính cho tích (và, do đó, cho số lượng) các số nguyên tố không vượt quá $x$, và chứng minh thủ tục của Bertrand.

Lời giải bài toán 3. Vẫn chưa có bằng chứng, con số $e$ là gì, đối với tất cả tự nhiên $n$,

$$\left(\frac{n+1}{n}\right)^n < e < \left(\frac{n+1}{n}\right)^{n+1},$$

thực sự tồn tại. (Bằng chứng về sự tồn tại sẽ được đưa ra dưới đây.)

⟦folio 15⟧

Chúng tôi muốn chứng minh rằng $\left(\frac{n+1}{e}\right)^n < n! < n \left(\frac{n}{e}\right)^n$ hoặc (giống nhau)
$\frac{(n+1)^n}{n!} < e^n < \frac{n^n}{(n-1)!}$ cho $n$ lớn hơn một số $n_0$.

Hãy chứng minh cho một số $k$ rằng $\frac{(k+1)^k}{k!} < e^k$. Nhưng
$\frac{(k+2)^{k+1}}{(k+1)!} / \frac{(k+1)^k}{k!} = \left(\frac{k+2}{k+1}\right)^{k+1} < e$. Vì vậy $\frac{(k+2)^{k+1}}{(k+1)!} < e^{k+1}$.

Do đó, tuyên bố của chúng tôi đúng với $k+1$, và do đó cũng đúng với $k+2, k+3$, v.v. Tương tự, từ giả định

$$e^k < \frac{k^k}{(k-1)!}$$

người ta kết luận rằng

$$e^{k+1} < \frac{(k+1)^{k+1}}{(k)!}.$$

Thật sự,

$$\frac{(k+1)^{k+1}}{k!} / \frac{k^k}{(k-1)!} = \left(\frac{k+1}{k}\right)^{k+1} > e.$$

Việc còn lại là chứng minh rằng $e$ tồn tại và tìm các giá trị ban đầu của $n$ trong mỗi bất đẳng thức

$$\left(\frac{n+1}{e}\right)^n < n!, n! < n \left(\frac{n}{e}\right)^n.$$

Bằng chứng về sự tồn tại của $e$

Điều kiện gọi tập hợp số thực $x$ thỏa mãn bất đẳng thức $a \leqslant x \leqslant b$ là đoạn có điểm cuối $a$ và $b$ (đoạn có điểm cuối $a$ và $b$ được ký hiệu là $[a, b]$).

Khi chứng minh sự tồn tại của số $e$, chúng ta sẽ sử dụng tính chất sau của số thực: nếu có một dãy các đoạn $[a_i, b_i]$, trong đó $a_i \leqslant a_{i+1} < b_{i+1} \leqslant b_i$ ($i=1, 2, \dots$) (dãy như vậy gọi là dãy các đoạn lồng nhau), thì có một điểm $\alpha$ chung cho tất cả các đoạn này.

Chúng tôi sẽ không chứng minh tài sản này. Thực tế là với một định nghĩa rõ ràng về những gì chúng ta hiểu về tập hợp số thực, thuộc tính này (hoặc một số tương đương) được chấp nhận như một tiên đề.

Bài tập

1. Kiểm tra xem các tính chất sau của số thực có tương đương nhau không; Nếu bạn chấp nhận bất kỳ điều nào trong số chúng mà không có bằng chứng, thì phần còn lại sẽ được suy ra từ đó.
a) Mỗi ​​dãy các đoạn lồng nhau có ít nhất một điểm chung.
b) Mọi dãy tăng đơn điệu bị chặn đều có giới hạn.
b) Bất kỳ chuỗi $\{a_i\}(i=1, 2, \dots)$ nào trong đó đối với bất kỳ $\varepsilon > 0$ nào, người ta có thể chỉ định $N$ (tất nhiên tùy thuộc vào $\varepsilon$) sao cho $|a_n - a_m| < \varepsilon$ cho $m, n > N$ có giới hạn. (Các dãy như vậy được gọi là dãy Cauchy.)
r) Mọi tập hợp số thực bị chặn ở trên đều có một phiên bản chính xác của grana, nghĩa là người ta có thể chỉ định một số $\alpha$ sao cho tất cả các số thuộc tập hợp này không lớn hơn $\alpha$, nhưng với bất kỳ số $\beta$ nào nhỏ hơn $\alpha$, người ta có thể tìm thấy một số từ tập hợp này lớn hơn $\beta$.
d) Từ bất kỳ họ phân đoạn nào bao gồm phân đoạn $[a, b]$, chúng ta có thể chọn một họ phân đoạn hữu hạn bao gồm phân đoạn $[a, b]$. (Chúng ta nói rằng một hệ thống $M$ gồm các phân đoạn bao gồm phân đoạn $[a, b]$ nếu với mỗi $x$ thuộc phân đoạn $[a, b]$ có một phân đoạn từ hệ thống $M$ chứa $x$.)

⟦folio 16⟧

Bây giờ chúng ta hãy chứng minh rằng dãy $\left(\frac{n+1}{n}\right)^n$ tăng đơn điệu. Để làm điều này, điều cần thiết là đối với bất kỳ $n\left(\frac{n+1}{n}\right)^n$ nào cũng phải nhỏ hơn $\left(\frac{n+2}{n+1}\right)^{n+1}$.

$$\left(\frac{n+1}{n}\right)^n < \left(\frac{n+2}{n+1}\right)^{n+1}$$

Với sự trợ giúp của các phép biến đổi đơn giản, bất đẳng thức này có thể được rút gọn về dạng sau:

$$[(n^2+2n+1)^n - (n^2+2n)^n](n+1) < (n^2+2n)^n.$$

[Dưới đây là các bất đẳng thức trung gian: $(n+1)^{2n+1} < (n+2)^{n+1}n^n$ và $(n^2+2n+1)^n(n+1) < (n^2+2n)^n(n+2)$.] Sử dụng công thức $a^k - b^k = (a-b)(a^{k-1} + a^{k-2}b + \ldots + ab^{k-2} + b^{k-1})$, ta có: $(n^2+2n+1)^n - (n^2+2n)^n < n(n^2+2n+1)^{n-1}$. Do đó, bất đẳng thức (1) sẽ được chứng minh nếu ta chứng minh bất đẳng thức sau:

$$(n^2+2n+1)^{n-1}(n+1) < (n^2+2n)^{n-1}(n+2).$$

Điều này đến lượt nó (hóa ra hoàn toàn giống nhau) suy ra từ bất đẳng thức

$$(n^2+2n+1)^{n-2}(n+1) < (n^2+2n)^{n-2}(n+2).$$

Lặp lại những lập luận này, chúng ta tin rằng bất đẳng thức (1) suy ra từ bất đẳng thức hiển nhiên

$$n+1 < n+2.$$

Việc chứng minh điều đó với mọi số tự nhiên $n$ thậm chí còn đơn giản hơn

$$\left(\frac{n+1}{n}\right)^{n+1} > \left(\frac{n+2}{n+1}\right)^{n+2}.$$

Thật vậy, bất đẳng thức (2) tương đương với bất đẳng thức

$$(n+1)^{2n+3} > (n+2)^{n+2}n^{n+1}.$$

Pozny chỉ cần thể hiện điều đó là đủ

$$[(n^2+2n+1)^{n+1} - (n^2+2n)^{n+1}](n+1) > (n^2+2n)^{n+1}.$$

Nhưng

$$(n^2+2n+1)^{n+1} - (n^2+2n)^{n+1} > (n^2+2n)^{n+1}(n+1),$$

Ở đâu

$$[(n^2+2n+1)^{n+1} - (n^2+2n)^{n+1}](n+1) > (n^2+2n)^{n+1}(n+1)^2 > (n^2+2n)^{n+1}(n^2+2n) = (n^2+2n)^{n+1},$$

tức là bất đẳng thức (3) và do đó bất đẳng thức (2) đã được chứng minh.

Vì vậy, chúng ta đã chứng minh rằng dãy $a_n = \left(\frac{n+1}{n}\right)^n$ tăng đơn điệu và dãy $b_n = \left(\frac{n+1}{n}\right)^{n+1}$ là dãy tiêu diệt đơn điệu. Ngoài ra, $a_n < b_n$ kể từ $\frac{n+1}{n} > 1$. Do đó, chuỗi các phân đoạn có điểm cuối $a_i$, $b_i$ là một chuỗi các phân đoạn lồng nhau và độ dài của phân đoạn thứ $k$ bằng $\left(\frac{k+1}{k}\right)^k \cdot \frac{1}{k}$, nghĩa là khi $k$ phát triển, nó có xu hướng bằng 0. Do đó, tất cả các phân đoạn này đều có đúng một điểm chung. Số tương ứng được gọi là số $e$.

Bạn có thể tính bao nhiêu chữ số thập phân của số $e$ tùy thích. Đây là một vài cái đầu tiên: $e=2,71828...$

⟦folio 18⟧

1. Chứng minh rằng
$$T(x) = \psi(x) + \psi\left(\frac{x}{2}\right) + \psi\left(\frac{x}{3}\right) + \dots$$

2. Chứng minh rằng
$$\psi(x) = \theta(x) + \theta(\sqrt{x}) + \theta(\sqrt[3]{x}) + \theta(\sqrt[4]{x}) + \dots$$

Sử dụng kết quả bài toán 1, $S(x)$ chúng ta có thể viết nó như thế này:
$$S(x) = A_1\psi(x) + A_2\psi\left(\frac{x}{2}\right) + A_3\psi\left(\frac{x}{3}\right) + \dots$$

3. Kiểm tra xem các hệ số $A_1, A_2, A_3, \dots$ có thay đổi theo chu kỳ 30 hay không và trong ba mươi giá trị đầu tiên $n$, các hệ số $A_n$ tạo thành chuỗi sau: 1, 0, 0, 0, 0, -1, 1, 0, 0, -1, 1, -1, 1, 0, -1, 0, 1, -1, 1, -1, 0, 0, 1, -1, 0, 0, 0, 0, 1, -1.

4. Chứng minh rằng các hệ số $A_1, A_2, A_3, \dots$ thay đổi theo chu kỳ 30 và trong ba mươi giá trị đầu tiên của $n$, các hệ số $A_n$ tạo thành chuỗi sau: 1, 0, 0, 0, 0, -1, 1, 0, 0, -1, 1, -1, 1, -1, 0, 0, 1, -1, 1, -1, 0, 0, 0, 0, 1, -1.

5. Chứng minh rằng
$$\psi(x) - 2\psi(\sqrt{x}) \leq \theta(y) \leq \psi(x) - \psi(\sqrt{x}).$$

6. Chứng minh rằng
$$\frac{\psi(x)}{\log x} < \pi(x) < \frac{\psi(x) + \theta(x)}{\log x}.$$

Lời giải bài toán 1. Lưu ý rằng $a_p = [\log_p x]$. Chúng tôi tính toán với hệ số nào $\log p$ nhập tổng $\psi(x) + \psi\left(\frac{x}{2}\right) + \dots$ Trong $\psi\left(\frac{x}{i}\right)$ logarit $p$ nhập với hệ số $\left[\log_p \frac{x}{i}\right]$, nghĩa là tổng hệ số của $\log p$ bằng $\sum_{i=1}^{\infty} \left[\log_p \frac{x}{i}\right]$. Hãy trừ một số từ mỗi số hạng và biến đổi nó: $\left[\log_p \frac{x}{i}\right] - 1 = \left[\log_p \frac{x}{i} - 1\right] = \left[\log_p \frac{x_1}{i}\right]$, trong đó $x_1 = \frac{x}{p}$. Vì vậy $\sum \left[\log_p \frac{x}{i}\right] = \left[\frac{x}{p}\right] + \sum \left[\log_p \frac{x_1}{i}\right]$. Lặp lại phép biến đổi, chúng ta có được đẳng thức sau:
$$\sum \left[\log_p \frac{x}{i}\right] = \sum_{i=1}^{\infty} \left[\frac{x}{p^i}\right].$$

Vậy hệ số của $\log p$ trong tổng $\psi(x) + \psi\left(\frac{x}{2}\right) + \dots$ bằng $\sum_{i=1}^{\infty} \left[\frac{x}{p^i}\right]$. Bây giờ chúng ta hãy lưu ý rằng $T(x) = \sum_{i \leq x} \log i$ cũng có thể được biểu diễn dưới dạng này: $T(x) = \sum_{p \leq x} c_p \log p$, trong đó $p$ là số nguyên tố.

Bài tập

12. Chứng minh rằng nếu $k$ là số tự nhiên thì $\left[\frac{x}{k}\right] = \left[\frac{x}{k}\right]$ cũng đúng với $x > 1 [\log_h[x]] = [\log_hx]$.

⟦folio none⟧

13. Đảm bảo rằng hệ số $c_p$ bằng

$$\sum_{i=1} \left[ \frac{[x]}{p^i} \right].$$

Gợi ý. Hãy coi $T(x)$ là $\log([x])$.

Sau khi giải xong bài 12 và 13 hãy giải hoàn toàn bài toán 1.

Lời giải bài toán 2. Lời giải của bài toán này tương tự như lời giải bài toán 1: bạn cần đảm bảo rằng hệ số của $p$ trong tổng của $\theta(x) + \theta(\sqrt{x}) + \cdots$ bằng $[\log_p x]$. Nó khá dễ dàng để làm theo. $\log p$ được đưa vào dưới dạng một thuật ngữ trong $\theta(\sqrt{x})$, nếu $\sqrt{x} \geq p$, tức là, $\log_p x \geq i$. Do đó, trong $\sum \theta(\sqrt{x})$ logarit $p$ nhập số hạng $k$ lần, trong đó $k$ được xác định từ bất đẳng thức $k + 1 > \log_p x \geq k$, tức là $[\log_p x]$ lần.

Lời giải bài toán 4. bài toán này rất giống với bài toán M92 (xem «Kvant» số 7, 1971).

Thật vậy, nó có thể được phát biểu như sau:

Trên chuyến tàu đầu tiên đến Maazin, Petya đã mua cho mình rất nhiều sôcôla nhỏ. Anh ấy quyết định rằng vào những ngày buồn chán, anh ấy nên ăn ba viên sôcôla, vào những ngày anh ấy chỉ bận rộn với một việc - hai và phần còn lại - một. Khi đó $A_i + 2$ bằng số sôcôla mà Petya đã ăn trong ngày $i + 1$. (Hãy nhớ lại rằng Petya đi bơi mỗi ngày thứ hai, mỗi ngày thứ ba đều đến maazin và mỗi ngày thứ năm đều giải được các bài toán bài toán).

Đây là công thức cho $A_i$:

$$A_i = 1 - [2^{[i/2] - i/2}] - [2^{[i/3] - i/3}] - [2^{[i/5] - i/5}] + [2^{[i/30] - i/30}].$$

Bài tập

14. Chứng minh công thức (4).
15. Suy ra công thức tính số việc Petya sẽ làm vào ngày thứ $k$.

Từ công thức (4) có thể thấy ngay rằng $A_{i+30} = A_i$. Tất nhiên, bạn có thể tự tính toán giá trị của ba mươi hệ số đầu tiên.

Lời giải bài toán 5. bài toán này theo sau bài toán 2. Thật vậy,

$$\psi(x) - \psi(\sqrt{x}) = \theta(x) + \theta(\sqrt{x}) + \cdots \geq \theta(x),$$

$$\psi(x) - 2\psi(\sqrt{x}) = \theta(x) - \theta(\sqrt{x}) + \cdots \leq \theta(x).$$

Lời giải bài toán 6. Vì $a_p = [\log_p x]$,

$$a_p \log p \leq \log_p x \log p = \log x, \quad (a_p + 1) \log p > \log x.$$

Pozny

$$\psi(x) = \sum_{p \leq x} a_p \log p \leq \sum_{p \leq x} \log x = \pi(x) \log x,$$

$$\psi(x) + \theta(x) = \sum_{p \leq x} (a_p + 1) \log x > \sum_{p \leq x} \log x = \pi(x) \log x,$$

Ở đâu

$$\frac{\psi(x)}{\log x} < \pi(x) < \frac{\psi(x) + \theta(x)}{\log x}.$$
