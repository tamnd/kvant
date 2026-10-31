---
id: 1989-5-gornshteyn-trigonometriya-pomogaet-algebre-1acbe271
issue: kvant_1989_5
year: 1989
number: "5"
title: Lượng giác giúp đại số
authors:
  - Горнштейн П. И.
rubric: praktikum-abiturienta
rubric_sub: Практикум абитуриента
page_first: 70
page_last: 72
page_labels: 68-70
tag: 3LYN
lang: vi
source: kvant_digital
extraction: vision
content_sha256: 8a4783fa3e470f1a18a9b7baa48d19686d78c967863e9e61c7a34fc73e5a1f96
prompt_sha256: draft-1
translated_from: content/ru/1989/05/articles/15_gornshteyn-trigonometriya-pomogaet-algebre-1acbe271.md
source_content_sha256: 04bb695f633d7528b2f9d576aa9f87905c02ccc4522cccdc152ebd9d97cd9c77
translation_model: draft
translation_run: vi-draft-2026-10-31
translation_quality: draft
---

⟦folio 68⟧

lượng giác
giúp đại số

P. I. GORNSTEIN

Thông thường, đối với lời giải đại số bài toán, sẽ thuận tiện hơn khi thay thế một biến (hoặc các biến, nếu có nhiều biến trong số chúng) bằng một hàm lượng giác và do đó giảm đại số bài toán thành một lượng giác. Những phép thay thế như vậy—các phép thay thế lượng giác—đôi khi đơn giản hóa đáng kể lời giải. Việc lựa chọn hàm này hay hàm khác phụ thuộc vào loại phương trình, hệ phương trình hoặc biểu thức đại số cần đơn giản hóa. Ví dụ: nếu tuân theo điều kiện là các giá trị được chấp nhận của biến $x$ được xác định bởi bất đẳng thức $|x| \leq 1$, thì việc thay thế $x=\sin \alpha$, $\alpha \in \left[-\frac{\pi}{2}; \frac{\pi}{2}\right]$ hoặc $x=\cos \alpha$, $\alpha \in [0; \pi]$ là thuận tiện và việc chọn cái nào tùy thuộc vào bài toán cụ thể.

Trong trường hợp một biến có thể nhận bất kỳ giá trị nào, các thay thế $x=\mathrm{tg} \alpha$, $\alpha \in \left(-\frac{\pi}{2}; \frac{\pi}{2}\right)$ và $x=\mathrm{ctg} \alpha$, $\alpha \in (0; \pi)$ sẽ được sử dụng.

Hãy xem xét một vài ví dụ.

Nhiệm vụ 1 (LPI, 1976). Giải phương trình

$$\sqrt{1-x^2}=4x^3-3x.$$

Lời giải. Trong trường hợp này $|x| \leq 1$. Đặt $x=\cos \alpha$, $\alpha \in [0; \pi]$, chúng ta thu được phương trình $$\sqrt{1-\cos^2 \alpha}=4\cos^3 \alpha-3\cos \alpha$$ hoặc $|\sin \alpha|=\cos 3\alpha$, nhưng trong trường hợp của chúng ta $\sin \alpha \geq 0$, vì vậy $\sin \alpha=\cos 3\alpha$, hoặc

$$\cos 3\alpha-\cos\left(\frac{\pi}{2}-\alpha\right)=0.$$

Giải phương trình cuối cùng, ta được

$$\alpha=\frac{\pi}{8}+\frac{\pi k}{2}, k \in Z$$

⟦folio 69⟧

hoặc

$$\alpha = \frac{3}{4} \pi + \pi n, \ n \in \mathbb{Z}.$$

Điều kiện $0 \leqslant \alpha \leqslant \pi$ được thỏa mãn bởi ba giá trị

$$\alpha_1 = \frac{\pi}{8}, \ \alpha_2 = \frac{5\pi}{8} \text{ и } \alpha_3 = \frac{3\pi}{4},$$

Vì vậy

$$x_1 = \cos \frac{\pi}{8} = \sqrt{\frac{1 + \cos \frac{\pi}{4}}{2}} =$$

$$= \sqrt{\frac{1 + \frac{\sqrt{2}}{2}}{2}} = \frac{1}{2} \sqrt{2 + \sqrt{2}};$$

$$x_2 = \cos \frac{5\pi}{8} = -\sqrt{\frac{1 + \cos \frac{5\pi}{4}}{2}} =$$

$$= -\sqrt{\frac{1 - \cos \frac{\pi}{4}}{2}} = -\frac{1}{2} \sqrt{2 - \sqrt{2}};$$

$$x_3 = \cos \frac{3\pi}{4} = -\cos \frac{\pi}{4} = -\frac{\sqrt{2}}{2}.$$

Đáp số: $\left\{ -\frac{\sqrt{2}}{2}; -\frac{1}{2} \sqrt{2 - \sqrt{2}}; \right.$

$\frac{1}{2} \sqrt{2 + \sqrt{2}}$.

Hãy xem xét bài toán phức tạp hơn một chút.

Bài toán 2 (LPI, 1976). Giải phương trình

$$\sqrt{1 - x} = 2x^2 - 1 + 2x\sqrt{1 - x^2}.$$

Lời giải. Và đây là phương trình $|x| \leqslant 1$. Giả sử, như trong ví dụ trước, $x = \cos \alpha$, trong đó $\alpha \in [0; \pi]$. Thực hiện phép thay thế và cho rằng $\sin \frac{\alpha}{2} \geqslant 0$, $\sin \alpha \geqslant 0$, ta thu được phương trình

$$\sqrt{2} \sin \frac{\alpha}{2} = \cos 2\alpha + \sin 2\alpha,$$

được chuyển đổi sang dạng

$$\sin \left( \frac{3\alpha}{4} + \frac{\pi}{8} \right) \cos \left( \frac{5\alpha}{4} + \frac{\pi}{8} \right) = 0,$$

từ đâu $\alpha = -\frac{\pi}{6} + \frac{4\pi k}{3}$, $k \in \mathbb{Z}$ hoặc $\alpha = \frac{3\pi}{10} + \frac{4\pi n}{5}$, $n \in \mathbb{Z}$.

Trong số các giá trị thu được $\alpha$, chỉ có một $\alpha = \frac{3\pi}{10}$ nằm trong khoảng (0; $\pi$). Vì vậy, $x = \cos \frac{3\pi}{10}$.

Đáp số có thể được để lại ở dạng lượng giác, nhưng cũng có thể được biểu thị dưới dạng căn thức bằng công thức $\sin 18^\circ = \frac{\sqrt{5} - 1}{4}$, được suy ra từ đẳng thức tiếp theo: $\sin 36^\circ = \cos 54^\circ$.

Đáp số: $\left\{ \cos \frac{3\pi}{10} = \frac{1}{4} \sqrt{10 - 2\sqrt{5}} \right\}$.

Một tình huống thậm chí còn phức tạp hơn sẽ xảy ra trong bài toán tiếp theo.

Bài toán 3 (MSU, Khoa Sinh học, 1985). Có bao nhiêu nghiệm trên đoạn [0; 1] có phương trình

$$8x(1 - 2x^2)(8x^4 - 8x^2 + 1) = 1?$$

Lời giải. Đây là phương trình bậc bảy nên mọi cố gắng giải nó bằng phương pháp đại số là vô vọng. Tuy nhiên, sự hiện diện của thừa số $1 - 2x^2$ gợi ý ý tưởng thực hiện phép thay thế lượng giác $x = \cos \varphi$, $\varphi \in (0; \pi/2)$ (rõ ràng là $x \neq 0$, $x \neq 1$).

Thay thế $x$ bằng $\cos \varphi$ ở vế trái của phương trình này, chúng ta nhận được

$$8 \cos \varphi(1 - 2 \cos^2 \varphi) \times$$

$$\times (8 \cos^4 \varphi - 8 \cos^2 \varphi + 1) =$$

$$= 8 \cos \varphi(-\cos 2\varphi) \times$$

$$\times (8 \cos^2 \varphi(\cos^2 \varphi - 1) + 1) =$$

$$= -8 \cos \varphi \cos 2\varphi(-2 \sin^2 2\varphi + 1),$$

Ở đâu

$$-8 \cos \varphi \cos 2\varphi \cos 4\varphi = 1.$$

Bây giờ nhân cả hai vế (*) với $\sin \varphi(\varphi \neq 0!)$:

$$-8 \sin \varphi \cos \varphi \cos 2\varphi \cos 4\varphi = \sin \varphi,$$

hoặc

$$-\sin 8\varphi = \sin \varphi,$$

$$\sin 8\varphi + \sin \varphi = 0,$$

$$2 \sin \frac{9}{2} \varphi \cdot \cos \frac{7}{2} \varphi = 0,$$

từ đâu $\varphi = \frac{2}{9} \pi k$, $k \in \mathbb{Z}$ hoặc $\varphi = \frac{\pi}{7} + \frac{2\pi n}{7}$, $n \in \mathbb{Z}$. Từ chuỗi đầu tiên, khoảng $(0; \frac{\pi}{2})$ chứa hai

⟦folio 70⟧

giá trị: $\varphi_1 = \frac{2\pi}{9}, \varphi_2 = \frac{4\pi}{9}$, trong chuỗi thứ hai cũng có hai giá trị như vậy: $\varphi_3 = \frac{\pi}{7}, \varphi_4 = \frac{3\pi}{7}$.

Đáp số: phương trình ban đầu nằm trên khoảng [0; 1]chính xác là bốn gốc.

Hãy lấy một ví dụ khác với sự thay đổi khá bất ngờ của biến có dạng $x = \text{tg} \alpha, \alpha \in \left(-\frac{\pi}{2}; \frac{\pi}{2}\right)$.

Bài toán 4 (Thế vận hội CHDC Đức, 1980). Xác định tất cả các số thực $(x, y, z)$ thỏa mãn hệ
$$\begin{cases} 2x + x^2y = y, \\ 2y + y^2z = z, \\ 2z + z^2x = x. \end{cases}$$
Lời giải. Thật dễ dàng để xác minh rằng hệ thống
$$\begin{cases} y = \frac{2x}{1-x^2}, \\ z = \frac{2y}{1-y^2}, \\ x = \frac{2z}{1-z^2} \end{cases}$$ (*)
tương đương với việc sử dụng bản gốc.

Chúng ta biết công thức $tg 2\alpha = \frac{2tg \alpha}{1-tg^2 \alpha}$. Điều này gợi ý thực hiện phép thay thế lượng giác $x = \text{tg} \alpha$, trong đó $\alpha \in \left(-\frac{\pi}{2}; \frac{\pi}{2}\right)$, $\alpha \neq -\frac{\pi}{4}$, $\alpha \neq \frac{\pi}{4}$.

Từ hệ (*) ta thu được $x = \text{tg} \alpha$, $y = \text{tg} 2\alpha$, $z = \text{tg} 4\alpha$, $x = \text{tg} 8\alpha$.

Vì vậy, $tg 8\alpha = \text{tg} \alpha$, $tg 8\alpha - \text{tg} \alpha = 0$, $\frac{\sin 7\alpha}{\cos 8\alpha \cos \alpha} = 0$, $\sin 7\alpha = 0$, $\alpha = \frac{\pi n}{7}$, $n \in \mathbb{Z}$.

Xác định tổng các chữ số của một số trên máy tính
(Để bắt đầu, xem trang 66)

Đề tài thí nghiệm tính toán

Cài đặt trên máy tính các thuật toán nêu trên để tính tổng các chữ số của số $n$, tổng các chữ số của tất cả các số từ 1 đến $n$ bằng phương pháp cộng và phương pháp tính bằng công thức $fk(n)$. Kiểm tra số trang sách giáo khoa của trường. Xác định $x = \text{tg}\left(\frac{\pi n}{7}\right), y = \text{tg}\left(\frac{2\pi n}{7}\right), z = \text{tg}\left(\frac{4\pi n}{7}\right)$ trong mỗi trường hợp.

Việc kiểm tra cho thấy rằng đối với $n \in \{-3; -2; -1; 0; 1; 2; 3\}$, 7 bộ số thu được là khác nhau và thực sự thỏa mãn hệ thống ban đầu.

Tất nhiên, tất cả các ví dụ được thảo luận trước đây đều là giả tạo và dường như được lựa chọn đặc biệt cho những người đăng ký và người tham gia cuộc thi.

Tóm lại, chúng tôi khuyên bạn nên tự mình giải các bài tập sau.

Bài tập
1. (POI, 1976). Giải phương trình
$$\sqrt{\frac{1-|x|}{2}} = 2x^2 - 1.$$
2. Giải phương trình
$$\left(\frac{1+a^2}{2a}\right)^x - \left(\frac{1-a^2}{2a}\right)^x = 1.$$
3. (MSU, Khoa Kinh tế, 1981). Tìm tất cả các phương trình lời giải
$$|2x - \sqrt{1-4x^2}| = \sqrt{2}(8x^2 - 1).$$
4. (Thế vận hội Leningrad, 1985). Giải hệ phương trình
$$\begin{cases} 4xy(2x^2 - 1) = 1, \\ x^2 + y^2 = 1. \end{cases}$$
5. (MSU, Khoa Sinh học, 1985). Có bao nhiêu nghiệm trên đoạn [0; 1] có phương trình
$$8x(2x^2 - 1)(8x^4 - 8x^2 + 1) = 1?$$
6. (MSU, Khoa Kinh tế, 1985). Trong số tất cả các hệ thống lời giải $(x, y, z, v)$
$$x^2 + y^2 = 4, \quad z^2 + v^2 = 9, \quad xv + yz \geq 6$$
tìm những biểu thức mà biểu thức $x + z$ có ý nghĩa nhất.

Xác định tổng các chữ số của một số trên máy tính
(Để bắt đầu, xem trang 66)

Đề tài thí nghiệm tính toán

Cài đặt trên máy tính các thuật toán nêu trên để tính tổng các chữ số của số $n$, tổng các chữ số của tất cả các số từ 1 đến $n$ bằng phương pháp cộng và phương pháp tính bằng công thức $fk(n)$. Kiểm tra số trang sách giáo khoa của trường. Xác định $x = \text{tg}\left(\frac{\pi n}{7}\right), y = \text{tg}\left(\frac{2\pi n}{7}\right), z = \text{tg}\left(\frac{4\pi n}{7}\right)$ trong mỗi trường hợp.

Việc kiểm tra cho thấy rằng đối với $n \in \{-3; -2; -1; 0; 1; 2; 3\}$, 7 bộ số thu được là khác nhau và thực sự thỏa mãn hệ thống ban đầu.

Tất nhiên, tất cả các ví dụ được thảo luận trước đây đều là giả tạo và dường như được lựa chọn đặc biệt cho những người đăng ký và người tham gia cuộc thi.

Tóm lại, chúng tôi khuyên bạn nên tự mình giải các bài tập sau.

Bài tập
1. (POI, 1976). Giải phương trình
$$\sqrt{\frac{1-|x|}{2}} = 2x^2 - 1.$$
2. Giải phương trình
$$\left(\frac{1+a^2}{2a}\right)^x - \left(\frac{1-a^2}{2a}\right)^x = 1.$$
3. (MSU, Khoa Kinh tế, 1981). Tìm tất cả các phương trình lời giải
$$|2x - \sqrt{1-4x^2}| = \sqrt{2}(8x^2 - 1).$$
4. (Thế vận hội Leningrad, 1985). Giải hệ phương trình
$$\begin{cases} 4xy(2x^2 - 1) = 1, \\ x^2 + y^2 = 1. \end{cases}$$
5. (MSU, Khoa Kinh tế, 1985). Trong số tất cả các hệ thống lời giải $(x, y, z, v)$
$$x^2 + y^2 = 4, \quad z^2 + v^2 = 9, \quad xv + yz \geq 6$$
tìm những biểu thức mà biểu thức $x + z$ có ý nghĩa nhất.

Xác định tổng các chữ số của một số trên máy tính
(Để bắt đầu, xem trang 66)

Đề tài thí nghiệm tính toán

Cài đặt trên máy tính các thuật toán nêu trên để tính tổng các chữ số của số $n$, tổng các chữ số của tất cả các số từ 1 đến $n$ bằng phương pháp cộng và phương pháp tính theo công thức $fk(n)$. Kiểm tra số trang sách giáo khoa của trường. Xác định $x = \text{tg}\left(\frac{\pi n}{7}\right), y = \text{tg}\left(\frac{2\pi n}{7}\right), z = \text{tg}\left(\frac{4\pi n}{7}\right)$ trong mỗi trường hợp.

Việc kiểm tra cho thấy rằng đối với $n \in \{-3; -2; -1; 0; 1; 2; 3\}$, 7 bộ số thu được là khác nhau và thực sự thỏa mãn hệ thống ban đầu.

Tất nhiên, tất cả các ví dụ được thảo luận trước đây đều là giả tạo và dường như được lựa chọn đặc biệt cho những người đăng ký và người tham gia cuộc thi.

Tóm lại, chúng tôi khuyên bạn nên tự mình giải các bài tập sau.

Bài tập
1. (POI, 1976). Giải phương trình
$$\sqrt{\frac{1-|x|}{2}} = 2x^2 - 1.$$
2. Giải phương trình
$$\left(\frac{1+a^2}{2a}\right)^x - \left(\frac{1-a^2}{2a}\right)^x = 1.$$
3. (MSU, Khoa Kinh tế, 1981). Tìm tất cả các phương trình lời giải
$$|2x - \sqrt{1-4x^2}| = \sqrt{2}(8x^2 - 1).$$
4. (Thế vận hội Leningrad, 1985). Giải hệ phương trình
$$\begin{cases} 4xy(2x^2 - 1) = 1, \\ x^2 + y^2 = 1. \end{cases}$$
5. (MSU, Khoa Kinh tế, 1985). Trong số tất cả các hệ thống lời giải $(x, y, z, v)$
$$x^2 + y^2 = 4, \quad z^2 + v^2 = 9, \quad xv + yz \geq 6$$
tìm những biểu thức mà biểu thức $x + z$ có ý nghĩa nhất.
