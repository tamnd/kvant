---
id: 1986-3-faddeev-sokolovskiy-o-kasatelnoy-k-grafiku-funktsii-c8b1818f
issue: kvant_1986_3
year: 1986
number: "3"
title: Về tiếp tuyến của đồ thị hàm số
authors:
  - Фаддеев Д. К.
  - Соколовский И. Ф.
rubric: matematicheskiy-kruzhok
rubric_sub: Математический кружок
page_first: 19
page_last: 20
page_labels: 17-18
tag: 7YK4
lang: vi
source: kvant_digital
extraction: vision
content_sha256: b1412bc0be324c49267469952655c04b191e2aaa14e8a6608c438086e180f51d
prompt_sha256: draft-1
translated_from: content/ru/1986/03/articles/07_faddeev-sokolovskiy-o-kasatelnoy-k-grafiku-funktsii-c8b1818f.md
source_content_sha256: e5dc254dcea3845dd07b12e37b90f1daaa2d673b041fc5a9daf77c14c01b3870
translation_model: draft
translation_run: vi-draft-2026-10-31
translation_quality: draft
---

⟦folio 17⟧

Về tiếp tuyến của đồ thị hàm số

Thành viên tương ứng của Viện Hàn lâm Khoa học Liên Xô
D. K. FADDEYEV,
I. F. SOKOLOVSKY

Mục tiêu chính của bài viết này là giải thích rõ ràng tiếp tuyến của đồ thị hàm số khả vi khác với các đường khác đi qua điểm tiếp tuyến như thế nào. Hóa ra đáp số đối với câu hỏi này không chỉ làm rõ ý nghĩa hình học của tiếp tuyến mà còn cho phép bạn tìm phương trình của nó mà không cần tính hàm đạo hàm.

Tiếp tuyến của đồ thị hàm $y = f(x)$ tại điểm $M(x_0; f(x_0))$ thường được xác định là vị trí giới hạn của cát tuyến $MN$, khi điểm $N$ tiến vô thời hạn đến điểm $M$, di chuyển dọc theo đồ thị của hàm (hình 1). Từ định nghĩa này, phương trình tiếp tuyến nổi tiếng được rút ra (“Đại số và sự khởi đầu của phân tích”, đoạn 23)

$$y = f'(x_0)(x - x_0) + f(x_0),$$

(1) trong đó $f'(x_0)$ là giá trị đạo hàm $f'$ của hàm $f$ tại $x = x_0$. Công thức này hợp lệ với giả định rằng hàm $f$ có đạo hàm tại điểm $x_0$.

Câu hỏi có thể đặt ra: "Tại sao người ta không chú ý nhiều đến tiếp tuyến có thể hiểu được? Tại sao tiếp tuyến lại ở điểm $(x_0; y_0)$, trong đó $y_0 = f(x_0)$, "tốt hơn" so với các đường khác đi qua điểm này?" Thật vậy, trong trường hợp tổng quát, người ta thậm chí không thể nói về một tiếp tuyến của đồ thị hàm số (tương tự như tiếp tuyến của một đường tròn) rằng nó có một điểm chung duy nhất với đồ thị hàm số. Hơn nữa, một tiếp tuyến của đồ thị của hàm số có thể cắt đồ thị, di chuyển từ phía này sang phía kia của đồ thị, chính xác tại điểm tiếp tuyến; ví dụ: đây là hành vi của tiếp tuyến với đồ thị của hàm $y = x^3$ tại điểm $(0; 0)$ hoặc tiếp tuyến với đồ thị của hàm $y = x^3 - 3x^2$ tại điểm $(1; -2)$. Và tiếp tuyến của đồ thị của hàm $y = x^4$ sin $(1/x)$ cắt đồ thị vô số lần.

Vậy làm cách nào để áp dụng tiếp tuyến cho đồ thị của hàm $y = f(x)$ tại điểm $(x_0; y_0)$? Hóa ra là trong một lân cận đủ nhỏ của điểm tiếp tuyến, tiếp tuyến thuộc đồ thị của hàm số chặt chẽ hơn bất kỳ đường nào khác đi qua điểm tiếp tuyến. Hãy xem xét điều này chi tiết hơn.

Giả sử $y = f(x)$ là một hàm đã cho có đạo hàm $f'(x_0)$ tại một điểm cho trước $x_0$. Phương trình đường nghiêng tùy ý đi qua điểm $(x_0; y_0)$ có dạng $y = k(x - x_0) + y_0$. Với $k = f'(x_0)$ ta thu được phương trình tiếp tuyến của đồ thị hàm số $y = f(x)$ tại điểm $(x_0; y_0)$. Tọa độ của một điểm trên đồ thị.hàm $y = f(x)$ khác với tọa độ của điểm tương ứng trên đường thẳng tới đỉnh

$$\varepsilon = f(x) - (k(x - x_0) + f(x_0)) = f(x) - f(x_0) - k(x - x_0) = (x - x_0) \left( \frac{f(x) - f(x_0)}{x - x_0} - k \right).$$

Bằng cách giới thiệu các ký hiệu $x - x_0 = \Delta x$ và $f(x) - f(x_0) = \Delta f(x_0)$, biểu thức này có thể được viết ngắn gọn hơn:

$$\varepsilon = \Delta x \cdot \left( \frac{\Delta f(x_0)}{\Delta x} - k \right).$$

Nếu $k = f'(x_0)$, tức là trong trường hợp tiếp tuyến, tại $\Delta x \to 0$ chúng ta có $\frac{\Delta f(x_0)}{\Delta x} \to f'(x_0)$ và do đó, mỗi thành phần ở vế phải của đẳng thức có xu hướng bằng 0.

Hình 1.

⟦folio 18⟧

Nếu $k \neq f'(x_0)$ thì $k = f'(x_0) + c$, trong đó $c$ là một hằng số nào đó không bằng 0. Sau đó

$$\varepsilon = \Delta x \left( \frac{\Delta f(x_0)}{\Delta x} - f'(x_0) - c \right).$$

Đối với $\Delta x \to 0$, thừa số thứ hai ở vế phải của đẳng thức có xu hướng $c \neq 0$. Do đó, tại $\Delta x \to 0$, một điểm trên tiếp tuyến sẽ tiến đến điểm tương ứng trên đồ thị nhanh hơn một điểm có cùng hoành độ trên một đường thẳng khác với tiếp tuyến.

Điều đặc biệt quan trọng là tiếp tuyến phù hợp với đường cong không chỉ tốt hơn về mặt định lượng so với các đường thẳng khác, mà theo một nghĩa nào đó “tốt hơn một bậc độ lớn”. Hãy giải thích điều này.

Chúng ta hãy viết lại biểu thức cho $\varepsilon$ trong trường hợp $k \neq f'(x_0)$ ở dạng

$$\varepsilon = \Delta x \left( \frac{\Delta f(x_0)}{\Delta x} - f'(x_0) \right) - c \Delta x.$$

Từ công thức viết này, rõ ràng rằng trong trường hợp đường thẳng khác với tiếp tuyến, hiệu giữa tọa độ của các điểm tương ứng trên đường thẳng và trên đồ thị hàm số chứa một số hạng tỉ lệ $\Delta x$, tức là có dạng $c \cdot \Delta x$, trong đó $c$ là một hằng số, nhưng trong trường hợp tiến gần theo một tiếp tuyến, khoảng cách giữa điểm trên đường thẳng và điểm tương ứng trên đồ thị giảm “một bậc độ lớn” nhanh hơn” so với chính $\Delta x$, nó có dạng $\gamma \cdot \Delta x$, trong đó $\gamma$ là một biến có xu hướng tiến tới 0 cùng với $\Delta x$. Do đó, trong số tất cả các đường thẳng đi qua một điểm trên đồ thị của hàm, chỉ có tiếp tuyến khác hàm số một lượng không chứa thuật ngữ tuyến tính đối với $\Delta x$.

Tính chất này của tiếp tuyến là đặc điểm giúp phân biệt nó với toàn bộ họ đường đi qua điểm tiếp tuyến. Nó mô tả đầy đủ tiếp tuyến và do đó có thể được sử dụng làm cơ sở cho định nghĩa tiếp tuyến; thì đạo hàm của hàm số tại một điểm có thể được định nghĩa là hệ số góc của tiếp tuyến với đồ thị của hàm số tại điểm đó. Tính chất dẫn xuất của tiếp tuyến biện minh cho phương pháp thu được phương trình của tiếp tuyến thông qua các đẳng thức gần đúng ước tính giá trị của hàm cường độ từ điểm tiếp tuyến. Hãy cho thấy ứng dụng của phương pháp này bằng các ví dụ. (Trong phần tiếp theo, $\Delta x$ sẽ được biểu thị bằng chữ cái $\alpha$.)

Ví dụ 1. Viết phương trình tiếp tuyến của đồ thị hàm số $f(x) = x^2 - 3x - 6$ tại điểm $x_0 = -1$.

Lời giải e. Đặt $x = -1 + \alpha$, trong đó $|\alpha|$ gần bằng 0. Sau đó $f(-1 + \alpha) = (-1 + \alpha)^2 - 3(-1 + \alpha) - 6 = 1 - 2\alpha + \alpha^2 + 3 - 3\alpha - 6 = -5\alpha + \alpha^2 - 2$. Biến đổi $\alpha^2$, chúng ta nhận được $f(-1 + \alpha) \approx -5\alpha - 2$. Hãy quay lại ký hiệu cũ; chúng tôi nhận được $f(x) \approx -5x - 7$ cường độ từ $x_0 = -1$. Lấy $y = -5x - 7$ độ lớn $x_0 = -1$ khác với $f(x)$ bởi một giá trị không chứa số hạng tương đối tuyến tính $\alpha$ và chỉ tiếp tuyến mới có thuộc tính này, có nghĩa là $y = -5x - 7$ là phương trình tiếp tuyến của đồ thị của hàm này tại điểm $x_0 = -1$. (Kiểm tra kết quả này bằng cách lấy phương trình tiếp tuyến sử dụng công thức (1).)

Ví dụ 2. Ta suy ra phương trình tiếp tuyến của đồ thị hàm số $f(x) = x^2$ tại một điểm tùy ý $x_0$.

Lời giải e. Đặt $x = x_0 + \alpha$, trong đó $|\alpha|$ gần bằng 0. Sau đó $f(x_0 + \alpha) = x_0^2 + 2x_0\alpha + \alpha^2$. Chúng ta biến đổi $\alpha^2$ và nhận được $f(x_0 + \alpha) \approx x_0^2 + 2x_0 \times (x - x_0) = x_0^2 + 2x_0x - 2x_0^2 = 2x_0x - x_0^2$. Lấy $y = 2x_0x - x_0^2$ tiếp tuyến với đồ thị của hàm số tại điểm $x_0$ thì hệ số góc của tiếp tuyến $2x_0$ là đạo hàm của $x^2$ tại điểm $x_0$.

Việc suy ra phương trình tiếp tuyến trở nên đặc biệt đơn giản trong trường hợp khi biểu thức xác định hàm $f(x)$ chứa các thừa số tuyến tính có dạng $(x - x_0)$.

Ví dụ 3. Viết phương trình tiếp tuyến của đồ thị hàm số

$$y = (x - x_0)(x - x_1)(x - x_2)$$

tại giao điểm của đồ thị với trục hoành.

Lời giải e. Đặt $x = x_0 + \alpha$, $y = \alpha(x_0 - x_1 + \alpha)(x_0 - x_2 + \alpha)$. Rõ ràng là khi mở ngoặc của số hạng, quan hệ tuyến tính $\alpha$ có dạng $\alpha(x_0 - x_1)(x_0 - x_2)$ thì

$$y = (x - x_0)(x_0 - x_1)(x_0 - x_2)$$

là phương trình tiếp tuyến của đồ thị hàm số tại điểm $x_0$. Tương tự, ta thu được phương trình tiếp tuyến tại các điểm $x_1$ và $x_2$:

$$y = (x - x_1)(x_1 - x_0)(x_1 - x_2),$$

$$y = (x - x_2)(x_2 - x_0)(x_2 - x_1).$$

Hãy đưa ra các ví dụ cụ thể trong đó cần tìm phương trình tiếp tuyến tại điểm $x_0$.
