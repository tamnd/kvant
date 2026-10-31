---
id: 1982-6-martyinov-o-maksimumah-funktsii-van-der-vardena-59649531
issue: kvant_1982_6
year: 1982
number: "6"
title: Về cực đại của hàm van der Waerden
authors:
  - Мартынов Б.
rubric: osnovnye-stati
page_first: 10
page_last: 15
page_labels: 8, 9, 10, 12, 13
tag: O53W
lang: vi
source: kvant_digital
extraction: vision
content_sha256: 70ceb098d4d267b4038b695c4e5d9c48da0da3e6b63d186ff2855cbfdddf433e
prompt_sha256: draft-1
translated_from: content/ru/1982/06/articles/02_martyinov-o-maksimumah-funktsii-van-der-vardena-59649531.md
source_content_sha256: 369c2e8a600d3647673a773c087b382f6f316efa3f33bf568d56fa32b3a78114
translation_model: draft
translation_run: vi-draft-2026-10-31
translation_quality: draft
---

⟦folio 8⟧

B. Martynov

Về cực đại của hàm van der Waerden

Chức năng chúng ta đã quen thuộc

Học sinh lớp chín và lớp mười biết rằng một hàm số khả vi tại một điểm nào đó sẽ liên tục tại điểm đó (“Đại số và nguyên tắc phân tích 9-10,” đoạn 19). Họ cũng biết rằng điều ngược lại là không đúng: ví dụ: hàm $y = |x|$ liên tục tại $x = 0$ (và tại bất kỳ điểm nào khác), nhưng không tùy ý tại $x = 0$. Nói chung, bất kỳ hàm số nào có đồ thị có một “góc” tại một điểm nào đó đều không khả vi tại điểm đó. Rõ ràng là dễ dàng xây dựng một hàm trên khoảng [0; 1] có vô số “góc” (Hình 1 thể hiện một phần đồ thị của hàm số đó; tất nhiên là không thể vẽ nó hoàn toàn).

Tuy nhiên, tất cả các hàm số như vậy, cũng như các hàm số liên tục khác mà bạn đã biết, vẫn khả vi ở “hầu hết” các điểm.

Trong một thời gian dài sau khi phát minh ra phép tính vi phân, các nhà toán học đã nghĩ rằng các hàm liên tục, như một quy luật, khả vi. Do đó, vào những năm sáu mươi, nhiều thế kỷ trôi qua, nhà toán học người Đức Karl Weierstrass đã công bố một ví dụ về hàm số liên tục tại mọi điểm trên một đường thẳng và không tùy ý tại bất kỳ điểm nào *), một buổi tối Strassian sẽ xuất hiện trong thế giới toán học.

*) Ví dụ đầu tiên thuộc loại này được nhà toán học và triết học người Séc Bernhard Bolzano xây dựng trước Weierstrass bốn mươi năm, nhưng ví dụ của ông được biết đến muộn hơn ví dụ của Vecherstrass.

Hình 1.

⟦folio 9⟧

Điều gì sẽ xảy ra nếu tất cả các chức năng $\varphi_n$ được thêm vào? Có lý do để hy vọng rằng trong mọi trường hợp, “tổng” sẽ liên tục tại mỗi điểm và không khả vi tại các điểm có dạng $x = \frac{k}{2^n} (k \in \mathbb{Z}, n \in \mathbb{N})$. Thật không may, chúng ta không biết tổng của vô số số hạng là bao nhiêu.

Do đó, chúng ta sẽ làm điều này: chúng ta tạo thành một chuỗi hàm $\Phi_n(x) = \varphi_0(x) + \varphi_1(x) + \dots + \varphi_n(x)$ (do đó, $\Phi_{n+1}(x) = \Phi_n(x) + \varphi_{n+1}(x)$; xem Hình 3-5) và chứng minh rằng với mọi $x$ đều tồn tại $\lim_{n \to \infty} \Phi_n(x)$.

Để chứng minh điều đó, chúng ta cần định lý Weierstrass, trong đó phát biểu rằng một dãy giới hạn đơn điệu có một giới hạn (Đại số và Phân tích 9, đoạn 32).

Từ $\varphi_{n+1}(x) \geq 0$ nó theo sau $\Phi_{n+1}(x) \geq \Phi_n(x)$—chuỗi ($\Phi_n(x)$) là đơn điệu. Vì $\Phi_n(x) = \varphi_0(x) + \varphi_1(x) + \dots + \varphi_n(x) \leq \frac{1}{2} + \frac{1}{4} + \dots + \frac{1}{2^{n+1}} = 1 - \frac{1}{2^{n+1}} < 1$, chuỗi ($\Phi_n(x)$) bị chặn. Do đó, $\lim_{n \to \infty} \Phi_n(x)$ tồn tại. Chúng ta hãy biểu thị giới hạn này bằng $\Phi(x)$. Như vậy, hàm $\Phi$ được xác định trên toàn bộ trục số. Nó là tuần hoàn (với chu kỳ 1), $0 \leq \Phi(x) \leq 1$ với mọi $x \in \mathbb{R}$, đồ thị của hàm $\Phi$ đối xứng với bất kỳ đường thẳng nào $x = \frac{k}{2} (k \in \mathbb{Z})$ - tất cả điều này dễ dàng suy ra từ các tính chất của hàm $\varphi_0$ và các tính chất của giới hạn. Do đó, không thể có đồ thị hàm số $\Phi$: trong Hình 3-5 bạn có thể thấy các điểm “nóng lên” như thế nào mà tại đó đồ thị hàm số $\Phi_n$ có một “góc”, tức là những điểm mà các hàm số này không có hàm tùy ý.

Tính liên tục của hàm số được xây dựng $\Phi_n$ là liên tục tại mỗi điểm của đường thẳng.

Về mặt trực quan, điều này khá rõ ràng: nếu $\Phi$ có điểm gián đoạn tại một điểm nào đó $x_0$, thì với một giá trị đủ lớn

⟦folio 10⟧

$n \in \mathbb{N}$ sẽ có điểm gián đoạn gần như tương tự tại điểm $x_0$ tại $\Phi_n$ và $\Phi_n$ là liên tục dọc theo toàn bộ đường thẳng. Bằng chứng dưới đây làm rõ những báo cáo này.

Trước tiên chúng ta hãy nghiên cứu sự khác biệt $r_n(x) = \Phi(x) - \Phi_n(x)$ (ở đây $x$ là cố định, $n$ là biến).

$$\Phi_{n+m}(x) - \Phi_n(x) = \varphi_{n+1}(x) + \varphi_{n+2}(x) + \dots + \varphi_{n+m}(x).$$

Rõ ràng là vậy

$$0 \leqslant \Phi_{n+m}(x) - \Phi_n(x) \leqslant \frac{1}{2^{n+2}} + \frac{1}{2^{n+3}} + \dots +$$

$$+ \frac{1}{2^{n+m+1}} = \frac{1}{2^{n+2}} \cdot \frac{1 - \frac{1}{2^m}}{1 - \frac{1}{2}} < \frac{1}{2^{n+1}}.$$

Vì $\lim_{m \to \infty} \Phi_{n+m}(x) = \Phi(x)$ và $\lim_{m \to \infty} \Phi_n(x) = \Phi_n(x)$,

$$0 \leqslant r_n(x) \leqslant \frac{1}{2^{n+1}}.$$

Bây giờ chúng ta có thể chuyển sang chứng minh tính liên tục của hàm số $\Phi$ tại một điểm tùy ý $x_0 \in \mathbb{R}$. Hãy lấy $\varepsilon > 0$ và xem xét mô hình khác biệt

$$|\Phi(x_0 + h) - \Phi(x_0)| = |\Phi_n(x_0 + h) + r_n(x_0 + h) - \Phi_n(x_0) - r_n(x_0)| \leqslant$$

$$\leqslant |\Phi_n(x_0 + h) - \Phi_n(x_0)| + |r_n(x_0 + h)| + |r_n(x_0)|.$$

Nhưng $|r_n(x_0)| \leqslant \frac{1}{2^{n+1}}$ và $|r_n(x_0 + h)| \leqslant \frac{1}{2^{n+1}}$; Đó là lý do tại sao

$$|\Phi(x_0 + h) - \Phi(x_0)| \leqslant$$

$$\leqslant |\Phi_n(x_0 + h) - \Phi_n(x_0)| + \frac{1}{2^n}.$$

Khi $n$ đủ lớn

$$\frac{1}{2^n} < \frac{\varepsilon}{2}.$$

Hàm $\Phi_n$, là tổng của một số hữu hạn các hàm liên tục, liên tục tại điểm $x_0$. Do đó, bằng cách chọn $\delta > 0$ có ​​thể đạt được điều đó cho $|h| < \delta$

$$|\Phi_n(x_0 + h) - \Phi_n(x_0)| < \frac{\varepsilon}{2}.$$

Khi $\delta$ được chọn

$$|\Phi(x_0 + h) - \Phi(x_0)| < \varepsilon,$$

và điều này chứng tỏ tính liên tục của hàm số $\Phi$ tại điểm $x_0$.

Tính không khả vi của hàm được xây dựng

Hàm $\Phi$ không khả vi tại bất kỳ điểm nào trên đường thẳng.

Thoạt nhìn, điều này có vẻ rất đáng ngạc nhiên: khi $n$ phát triển, tập hợp các điểm không khả vi của các hàm $\Phi_n$ trở nên dày đặc hơn và sâu hơn, do đó, đương nhiên người ta kỳ vọng rằng “trong giới hạn”, tức là đối với các hàm $\Phi$, nó sẽ lấp đầy toàn bộ đường thẳng. Tuy nhiên, lý luận ngây thơ này là không chính xác, như hàm ví dụ cho thấy

$$G(x) = \lim_{n \to \infty} G_n(x),$$

trong đó các hàm $G_1, G_2, G_3$ được hiển thị trong Hình 6. Rõ ràng, $G(x) = 1 - x^2$ là hàm khả vi tại bất kỳ điểm nào.

Chứng minh bằng phản chứng, chúng ta giả sử rằng với một số $x_0 \in \mathbb{R}$ có $\Phi'(x_0)$.

“Khóa” $x_0$ theo trình tự gần đúng kép theo khuyết tật và bằng hình ảnh:

$$\frac{s_k}{2^{k+1}} \leqslant x_0 < \frac{s_k + 1}{2^{k+1}} \quad (k = 0, 1, 2, \dots; \ s_k \in \mathbb{Z}).$$

Hãy đặt $\alpha_k = \frac{s_k}{2^{k+1}}, \beta_k = \frac{s_k + 1}{2^{k+1}}$. Sau đó

$$\alpha_k \leqslant x_0 < \beta_k \quad (k = 0, 1, 2, \dots)$$

Và

$$\lim_{k \to \infty} \alpha_k = \lim_{k \to \infty} \beta_k = x_0.$$

Từ (1)

$$0 < \frac{\beta_k - x_0}{\beta_k - \alpha_k} \leqslant 1$$

$$0 \leqslant \frac{x_0 - \alpha_k}{\beta_k - \alpha_k} \leqslant 1.$$

Từ đây, từ (2) và từ danh tính dễ kiểm chứng

$$\frac{\Phi(\beta_k) - \Phi(\alpha_k)}{\beta_k - \alpha_k} - \Phi'(x_0) =$$

$$= \frac{\beta_k - x_0}{\beta_k - \alpha_k} \left[ \frac{\Phi(\beta_k) - \Phi(x_0)}{\beta_k - x_0} - \Phi'(x_0) \right] +$$

$$+ \frac{x_0 - \alpha_k}{\beta_k - \alpha_k} \left[ \frac{\Phi(x_0) - \Phi(\alpha_k)}{\beta_k - x_0} - \Phi'(x_0) \right]$$

nên

$$\lim_{k \to \infty} \frac{\Phi(\beta_k) - \Phi(\alpha_k)}{\beta_k - \alpha_k} = \Phi'(x_0).$$

⟦folio 12⟧

$$\Phi(2\bar{x}) = 2\Phi(\bar{x}) - 2\varphi_0(\bar{x}) = 2\Phi(\bar{x}) - 2\bar{x} = 2M - 2\bar{x} \leqslant M$$
$$\bar{x} \geqslant \frac{M}{2} \geqslant \frac{1}{3}.$$

Từ tính đối xứng của đồ thị hàm số Ф so với đường thẳng $x = \frac{1}{2}$ suy ra rằng không có điểm cực đại nào trên khoảng $] \frac{2}{3}; 1]$.

Bây giờ chúng ta hãy chứng minh rằng $M = \frac{2}{3}$. Chúng tôi áp dụng lại đẳng thức (3):

$$\Phi(4x) = 2\Phi(2x) - 2\varphi_0(2x) = 2[2\Phi(x) - 2\varphi_0(x)] - 2\varphi_0(2x) = 4\Phi(x) - 4\varphi_0(x) - 2\varphi_0(2x)$$
$$\Phi(x) = \varphi_0(x) + \frac{1}{2}\varphi_0(2x) + \frac{1}{4}\Phi(4x) = \Phi_1(x) + \frac{1}{4}\Phi(4x).$$

Hàm $\Phi_1$ trên đoạn $[\frac{1}{4}; \frac{3}{4}]$ được xây dựng và bằng $\frac{1}{2}$ (Hình 3), do đó, trên đoạn này

$$\Phi(x) = \frac{1}{2} + \frac{1}{4}\Phi(4x).$$

Vì $\bar{x} \in [\frac{1}{3}; \frac{2}{3}] \subset [\frac{1}{4}; \frac{3}{4}]$, đẳng thức (4) có thể được áp dụng cho $\bar{x}$:

$$M = \Phi(\bar{x}) = \frac{1}{2} + \frac{1}{4}\Phi(4\bar{x}) \leqslant \frac{1}{2} + \frac{1}{4}M$$
$$M \leqslant \frac{2}{3}.$$

Chúng ta hãy nhớ rằng $M \geqslant \Phi(\frac{1}{3}) = \frac{2}{3}$, và cuối cùng tìm thấy $M = \frac{2}{3}$. Ngoài ra, $\Phi(\frac{1}{3}) = \Phi(\frac{2}{3}) = \frac{2}{3}$.

Để chứng minh thêm rằng nếu $\bar{x} - \text{точка максимума},$ thì $4\bar{x} - \text{точка максимума};$ nếu $4\bar{x} - \text{точка максимума}$ và $\{\bar{x}\} \in [\frac{1}{4}; \frac{3}{4}]$ thì $\bar{x} - \text{точка максимума}$. Để chứng minh điều đó, hãy lưu ý rằng đẳng thức (4) đúng với mọi $x$ sao cho $\{x\} \in [\frac{1}{4}; \frac{3}{4}]$ (kiểm tra!). Hãy để $\bar{x} - \text{точка максимума}$. Sau đó $\{\bar{x}\} \in [\frac{1}{3}; \frac{2}{3}] \subset [\frac{1}{4}; \frac{3}{4}]$.

$$\frac{2}{3} = M = \Phi(\bar{x}) = \frac{1}{2} + \frac{1}{4}\Phi(4\bar{x})$$
$$\Phi(4\bar{x}) = \frac{2}{3} = M.$$

Bây giờ hãy đặt $4\bar{x} - \text{точка максимума}$ và $\{\bar{x}\} \in [\frac{1}{4}; \frac{3}{4}]$. Sau đó $\Phi(4\bar{x}) = M = \frac{2}{3}$ và $\Phi(\bar{x}) = \frac{1}{2} + \frac{1}{4}\Phi(4\bar{x}) = \frac{2}{3} = M.$

Nhiều điểm tối đa

Chúng ta hãy tìm hiểu cấu trúc của tập hợp $E$.

Có lẽ, nếu Hermite biết nó phức tạp đến mức nào, anh ta sẽ phản ứng với các chức năng của Van der Waerden với thái độ thậm chí còn ghê tởm hơn. Mặt khác, ai biết được - có lẽ cấu trúc đẹp và tinh tế của tập hợp này sẽ thu hút Hermite nghiên cứu về các hàm không khả vi.

Chúng ta biết hai điểm của tập hợp $E$:

$$\frac{1}{3} \text{ и } \frac{2}{3};$$ chúng tôi cũng biết rằng $E \subset [\frac{1}{3}; \frac{2}{3}]$.

Hơn nữa, tập $E$ bị đóng. Điều này có nghĩa như sau: nếu có một dãy điểm hội tụ trong tập hợp $E$ thì giới hạn của dãy này cũng thuộc về $E$. Hãy chứng minh điều đó. Đặt $x_n \in E$ ($n=1, 2, 3, \dots$), tức là $\lim_{n \to \infty} x_n = \bar{x}$; thì từ tính liên tục của hàm số $E$ tại điểm $\bar{x}$ suy ra $\Phi(\bar{x}) = \Phi(\lim_{n \to \infty} x_n) = \lim_{n \to \infty} \Phi(x_n) = M$, tức là $\bar{x} \in E$.

Từ những gì đã được chứng minh ở cuối đoạn trước và thực tế rằng $1$ là chu kỳ của hàm $E$, suy ra rằng nếu $x - \text{точка максимума} E$ thì các điểm $\frac{1}{4} + \frac{x}{4} = \frac{x+1}{4}, \frac{2}{4} + \frac{x}{4} = \frac{x+2}{4}$ cũng thuộc về $E$. Như vậy, bắt đầu từ các điểm $\frac{1}{3}, \frac{2}{3}$, người ta có thể dựng nhiều điểm của tập hợp $E: \frac{1}{4} + \frac{1}{4} \cdot \frac{1}{3}, \frac{2}{4} + \frac{1}{4} \cdot \frac{1}{3}, \frac{1}{4} + \frac{1}{4} \cdot \frac{2}{3}$, v.v.

Dễ dàng nhận thấy mọi số đều có dạng

$$x = \frac{a_1}{4} + \frac{a_2}{4^2} + \dots + \frac{a_n}{4^n} + \frac{1}{4^n} \cdot \frac{a_{n+1}}{3},$$

⟦folio 13⟧

trong đó $a_1, a_2, \dots, a_n, a_{n+1}$ là một hoặc hai và là các phần tử của tập hợp $E$. Từ
$$\frac{1}{3} = \frac{1}{4} + \frac{1}{4^2} + \frac{1}{4^3} + \dots,$$
$x$ như vậy có thể được biểu diễn dưới dạng
$$x = \frac{a_1}{4} + \frac{a_2}{4^2} + \dots + \frac{a_n}{4^n} + \frac{a_{n+1}}{4^{n+1}} + \frac{a_{n+1}}{4^{n+2}} + \dots$$
hoặc, bằng cách tương tự với các phân số thập phân, ở dạng phân số bốn lần tuần hoàn vô hạn với chu kỳ dài 1:
$$x = 0, a_1 a_2 \dots a_n a_{n+1} a_{n+1} = 0, a_1 a_2 \dots a_n (a_{n+1}).$$
Vì tập $E$ là đóng nên bất kỳ số nào
$$x = \frac{a_1}{4} + \frac{a_2}{4^2} + \dots + \frac{a_n}{4^n} + \frac{a_{n+1}}{4^{n+1}} + \frac{a_{n+2}}{4^{n+2}} + \dots$$
trong đó $a_i$ là một hoặc hai thì tập hợp $E$ thuộc về. Thật vậy, với mỗi $x$ như vậy, người ta có thể tìm thấy một chuỗi gồm các phần tử $(x_n)$ từ $E$ hội tụ đến $x$; ví dụ nếu
$$x_n = \frac{a_1}{4} + \frac{a_2}{4^2} + \dots + \frac{a_n}{4^n} + \frac{1}{4^n} \cdot \frac{1}{3},$$
thì $\lim_{n \to \infty} x_n = x \left(0 \leqslant x - x_n \leqslant \frac{1}{4^{n+1}}\right)$.

Do đó, tập hợp $E$ chứa tất cả các số, trong đó biểu diễn $0, a_1 a_2 a_3 \dots$ dưới dạng phân số vô hạn bốn lần, tất cả các chữ số $a_i$ là một hoặc hai (Hình 8 hiển thị khai triển bậc bốn của các số $\frac{1}{12}, \frac{2}{12}, \dots, \frac{11}{12}$).

Bây giờ chúng ta hãy chứng minh rằng $E$ không chứa bất kỳ số nào khác. Giả sử trong ký hiệu bốn của số $x \in E$ có một chữ số 0 ở một vị trí nào đó sau dấu thập phân, tức là $x = 0, a_1 a_2 \dots a_n 0 a_{n+2} \dots$; thì $\{4^n x\} = 0, 0 a_{n+2} \dots \in E$.

Nhưng $0, 0 a_{n+2} a_{n+3} \dots < 0, 033 \dots = 3 \left(\frac{1}{4^2} + \frac{1}{4^3} + \dots\right) = \frac{1}{4}$ và do đó, điểm $\{4^n x\}$ không thuộc đoạn $\left[\frac{1}{3}; \frac{2}{3}\right]$ chứa $E$.

Nếu ký hiệu bốn của số $x \in E$ chứa chữ số 3, tức là $x = 0, a_1 a_2 \dots a_n 3 a_{n+2} \dots$, thì
