---
id: 1971-1-skanavi-metod-podstanovki-pri-reshenii-uravneniy-i-sistem-uravneniy-f445b2a7
issue: kvant_1971_1
year: 1971
number: "1"
title: Phương pháp thế khi giải phương trình và hệ phương trình
authors:
  - Сканави М. И.
rubric: praktikum-abiturienta
rubric_sub: Практикум абитуриента
page_first: 45
page_last: 46
page_labels: 43-44
tag: BBD2
lang: vi
source: kvant_digital
extraction: vision
content_sha256: 0fe748843cdeb5621f4427075098d4857a7bc126ea2a13216ec568b558e88115
prompt_sha256: 3ec6b8aabd9b98576af76503cd8a2902b9f5d18e01ee867dfb1228f59c6d52d8
translated_from: content/ru/1971/01/articles/09_skanavi-metod-podstanovki-pri-reshenii-uravneniy-i-sistem-uravneniy-f445b2a7.md
source_content_sha256: 96c1e59d5fb3ed66aa52d2ece5c165bfc82e9b02f609aa82ebdb6b09b882574d
translation_model: gpt-5.6-terra
translation_run: vi-codex-2026-10-31
---

⟦folio 43⟧

...chứa các căn bậc hai!): lập hiệu các biểu thức dưới dấu căn của các căn nằm ở vế trái, ta được $(t+3) - t=3$.

Bây giờ phân tích hiệu này thành nhân tử (dùng công thức hiệu hai bình phương) và được $(\sqrt{t+3} + \sqrt{t})(\sqrt{t+3} - \sqrt{t}) = 3$.

Từ đây, chia cho phương trình ban đầu (theo $t$), ta được

$$\sqrt{t+3} - \sqrt{t} = \frac{3}{\sqrt{2t+7}}.$$

Lấy phương trình ban đầu trừ đi điều vừa nhận được, ta thấy rằng

$$2\sqrt{t} = \sqrt{2t+7} - \frac{3}{\sqrt{2t+7}},$$

$$2\sqrt{t} = \frac{2t+4}{\sqrt{2t+7}}, \sqrt{t} = \frac{t+2}{\sqrt{2t+7}}.$$

Thủ tục vừa thực hiện cho phép khử các căn chỉ bằng một lần bình phương hai vế của phương trình. Ta làm điều đó:

$$t = \frac{t^2+4t+4}{2t+7}, t^2+3t-4=0.$$

Từ đây $t_1=1, t_2=-4$. Tiếp theo, nhận thấy rằng chỉ các giá trị dương của $t$ mới đáng quan tâm, vì $t = x^2+x+1 > 0$

với mọi giá trị của $x$. Do đó loại nghiệm không phù hợp $t_2$ và để tìm $x$ ta được một phương trình bậc hai

$$x^2+x+1=1, \quad x^2+x=0$$

với các nghiệm $x_1=-1$ và $x_2=0$. Như dễ kiểm tra, cả hai đều là nghiệm của phương trình vô tỉ đã cho.

Ví dụ 5. Giải hệ phương trình

$$\begin{cases} \frac{x^3}{y} + xy = 40, \\ \frac{y^3}{x} + xy = 10. \end{cases}$$

(Chỉ tìm các nghiệm thực).

Việc giải hệ phương trình bằng phương pháp thế được học sinh thực hành khá nhiều. Đồng thời, trong những trường hợp này nó cũng rất thường tỏ ra hết sức hiệu quả. Trước khi bắt đầu giải hệ đã cho, tôi xin phép nêu một vài nhận xét chung về phương pháp thế khi giải hệ hai phương trình với hai ẩn. Nếu hai ẩn này được ký hiệu là $x$ và $y$, thì thường có ích khi chuyển sang các ẩn mới $\rho$ và $\varphi$ theo các đẳng thức sau:

$$x = \rho \cos \varphi,$$

$$y = \rho \sin \varphi.$$

Bạn đọc đủ quen thuộc với phương pháp tọa độ trên mặt phẳng hẳn hiểu rằng nếu $x$ và $y$ là các tọa độ Descartes của một điểm nào đó, thì $\rho$ và $\varphi$ là cái gọi là tọa độ cực của chính điểm ấy. Ý nghĩa hình học của tọa độ cực và mối liên hệ của chúng với tọa độ Descartes sẽ trở nên rõ ràng từ hình vẽ mà chúng tôi khuyên mọi người hãy xem xét CẨN THẬN ngay lúc này:

⟦folio 44⟧

Nhận thấy rằng gốc tọa độ $O$ có $\rho=0$, còn góc $\varphi$ đối với nó không có giá trị xác định. Tất cả các điểm khác của mặt phẳng sẽ được cho bởi một cặp duy nhất các tọa độ cực ($\rho, \varphi$), nếu yêu cầu rằng

$$0 \leqslant \rho < +\infty,$$
$$0 \leqslant \varphi < 2\pi.$$

Dùng các đẳng thức (!) để giải hệ phương trình đã cho, vì vậy thay $x$ và $y$ trong các phương trình của hệ bằng các biểu thức của chúng qua $\rho$ và $\varphi$; ta được rằng

$$\begin{cases} \frac{\rho^3 \cos^3 \varphi}{\rho \sin \varphi} + \rho \cos \varphi \rho \sin \varphi = 40, \\ \frac{\rho^3 \sin^3 \varphi}{\rho \cos \varphi} + \rho \cos \varphi \rho \sin \varphi = 10. \end{cases}$$

hoặc sau khi biến đổi, ta được rằng

$$\begin{cases} \rho^2 \text{ctg} \varphi = 40, \\ \rho^2 \text{tg} \varphi = 10. \end{cases}$$

Chia phương trình thứ nhất cho phương trình thứ hai, ta tìm được rằng

$$\text{ctg}^2 \varphi = 4.$$

Suy ra $\text{ctg} \varphi = 2$ hoặc $\text{ctg} \varphi = -2$. Giá trị thứ hai (âm) của $\text{ctg} \varphi$ lập tức bị loại bỏ, vì $\text{ctg} \varphi$ và $\rho^2$ có cùng dấu, còn $\rho^2$ không thể âm. Bây giờ theo côtang đã biết, cần tìm sin và cos của góc $\varphi$. Làm điều này không cần lời:

$$\cos^2 \varphi = 1 + \text{ctg}^2 \varphi = 5,$$
$$\cos \varphi = \sqrt{5},$$
$$\cos \varphi = -\sqrt{5},$$

$$\sin \varphi = \frac{1}{\sqrt{5}}, \quad \sin \varphi = -\frac{1}{\sqrt{5}},$$
$$\cos \varphi = \frac{2}{\sqrt{5}}, \quad \cos \varphi = -\frac{2}{\sqrt{5}}.$$

Tiếp theo tìm $\rho$ từ điều rằng

$$\rho^2 \text{ctg} \varphi = \rho^2 \cdot 2 = 40, \quad \rho^2 = 20.$$

Ta được $\rho = 2\sqrt{5}$. Dùng các đẳng thức (!) theo $\rho$ và $\varphi$ đã biết, làm nghiệm của hệ phương trình đã cho, ta tìm được hai cặp số sau:

$$x_1 = 2\sqrt{5} \cdot \frac{2}{\sqrt{5}} = 4,$$
$$y_1 = 2\sqrt{5} \cdot \frac{1}{\sqrt{5}} = 2;$$
$$x_2 = 2\sqrt{5} \left(-\frac{2}{\sqrt{5}}\right) = -4,$$
$$y_2 = 2\sqrt{5} \left(-\frac{1}{\sqrt{5}}\right) = -2.$$

Không đúng khi cho rằng hệ đã cho chỉ có thể giải bằng cách chuyển sang tọa độ cực (chẳng hạn, còn có thể giải như sau: chuyển $xy$ từ vế trái của các phương trình sang vế phải, rồi nhân các kết quả với nhau và nhận được một phương trình bậc hai đối với $xy$; phần tiếp theo là hiển nhiên). Tuy nhiên, cần đưa thủ pháp này vào sử dụng. Nó cho phép, theo một nghĩa nào đó, quy định các phép biến đổi của chúng ta và tạo khả năng sử dụng toàn bộ công cụ của lượng giác học. Trong những trường hợp nào thì dùng thủ pháp này có lợi, còn trong những trường hợp nào thì không? Kinh nghiệm của bạn giúp trả lời câu hỏi này, và kinh nghiệm ấy có thể được làm phong phú bằng chính công sức của bạn!

Trong khi còn thời gian trước các kỳ thi tuyển sinh — hãy hành động!
