---
id: 1979-6-grigorenko-kogda-kriticheskih-tochek-slishkom-mnogo-c186dae3
issue: kvant_1979_6
year: 1979
number: "6"
title: Khi có quá nhiều điểm tới hạn
authors:
  - Григоренко В.
rubric: po-stranitsam-shkolnyh-uchebnikov
rubric_sub: По страницам школьных учебников
page_first: 26
page_last: 27
page_labels: 24-25
tag: D85A
lang: vi
source: kvant_digital
extraction: vision
content_sha256: 175bdbb8e7d223d8ba5dcfb1372afc7e013d555682aaddb1a9f2f3be3d150bcf
prompt_sha256: draft-1
translated_from: content/ru/1979/06/articles/09_grigorenko-kogda-kriticheskih-tochek-slishkom-mnogo-c186dae3.md
source_content_sha256: ab47e8bf4f3a5dbd71566de4424b548368ce363482be35da5bb31f4cdd3759d4
translation_model: draft
translation_run: vi-draft-2026-10-31
translation_quality: draft
---

⟦folio 24⟧

V. Grigorenko

Khi
điểm quan trọng
quá nhiều

Trong đoạn 55 của sổ tay “Đại số và sự khởi đầu của phân tích 9”, nghiên cứu chính xác về điểm tới hạn ở cực trị đã được chỉ ra (Định lý 1, 2). Điều này có luôn đúng không?

Các tình huống bất ngờ không thể sử dụng được sẽ được thảo luận trong bài viết này.

Hãy nhớ rằng điểm bên trong $x_0$ có một hàm nhất định $f$ được gọi là quan trọng đối với hàm này nếu $f'(x_0) = 0$ hoặc $f'(x_0)$ không tồn tại.

Chúng ta hãy giả sử (để đơn giản cho việc trình bày) rằng hàm $f$ không đúng tại điểm $x_0$. (Từ giả định này, tự động suy ra rằng điểm $x_0$ là điểm bên trong miền định nghĩa của hàm $f$.)

Theo điều kiện đủ để có mức tối đa (“Đại số và Nguyên tắc Giải tích 9”, đoạn 55, Định lý 2), nếu có mức tối đa $|x_0| - \delta$; $x_0 + \delta$ [thùy $x_0$, nửa chéo bên trái $|x_0| - \delta$; $x_0$ [cạnh $f'(x) > 0$ và nửa chéo bên phải $|x_0|$; $x_0 + \delta$ [với $f'(x) < 0$, thì điểm $x_0$ là một hàm mạnh mẽ của $f$.

Đương nhiên họ sẽ hỏi: điều ngược lại có đúng không? Chúng ta hãy làm rõ câu hỏi của mình: đặt hàm $f$ khả vi trong một lân cận nào đó của điểm $x_0$ và đặt điểm này là điểm cực đại của hàm $f$; Có nhất thiết phải có một lân cận tại điểm $x_0$ trong đó đạo hàm “đổi dấu từ phẳng sang âm” không? Nói một cách đại khái, điều kiện tối đa có đủ cần thiết không?

Hóa ra đáp số là phủ định cho những câu hỏi này.

Ví dụ 1. Hàm

$$f(x) = \begin{cases} 2 - x^2 \left(2 + \sin \frac{1}{x}\right), & если x \neq 0 \\ 2, & если x = 0 \end{cases}$$

lấy đạo hàm trên toàn bộ trục số $R$, điểm 0 là điểm cực đại mạnh của hàm $f$ và trong mỗi bán dương của bất kỳ lân cận nào ] - δ; δ[đạo hàm 0 thùy $f'$ đổi dấu (Hình 1*)).

Thật vậy, hàm số $f$ hiển nhiên khả vi tại bất kỳ điểm nào $x_0 \neq 0$; nó cũng khả vi tại điểm 0, vì

$$f'(0) = \lim_{h \to 0} \frac{f(h) - f(0)}{h - 0} = \lim_{h \to 0} \left[ -h \left(2 + \sin \frac{1}{h}\right) \right] = 0.$$

(Bình đẳng cuối cùng xuất phát từ thực tế là $\lim_{h \to 0} (-h) = 0$ và hàm $y = 2 + \sin \frac{1}{h}$ bị giới hạn ở $R$, tức là nhờ sự tương tự của Định lý 2 từ đoạn 28 của sổ tay “Đại số và Nguyên tắc Phân tích 9”.) Điểm 0 là mức tối đa mạnh mẽ của $f$, vì tại $x \neq 0$, rõ ràng là $f(x) < f(0)$. Cuối cùng, trong mỗi khoảng thời gian ]—δ; 0 [ và ]0; δ[ đạo hàm

$$f'(x) = -4x - 2x \sin \frac{1}{x} + \cos \frac{1}{x}$$

*) Trong tất cả các hình, tỷ lệ dọc theo các trục là khác nhau. Trong vùng lân cận số 0, các bản vẽ sẽ mất đi mức độ chi tiết cần thiết và trở nên không chính xác.

⟦folio 25⟧

đổi dấu (giải thích “trên ngón tay”: tại $x \to 0$ các số hạng $-4x$ và $-2x \sin \frac{1}{x}$ có ​​xu hướng về 0 và do đó trở nên nhỏ tùy ý, trong khi số hạng $\cos \frac{1}{x}$ liên tục đổi dấu, chuyển từ +1 sang -1 và ngược lại).

Lý do cho tình huống không phù hợp này là vì trong bất kỳ lân cận nào của điểm 0 đều có vô số điểm tới hạn của hàm $f$ (xem Hình 1); đi qua chúng thì đạo hàm $f'$ đổi dấu.

Tất nhiên, “cụm” các điểm tới hạn như vậy không tồn tại nếu các hàm $f$ có số điểm tới hạn hữu hạn hoặc ít nhất là hữu hạn trên bất kỳ khoảng nào $[a; b]$ (ví dụ như các hàm $y = \sin x$). Trong trường hợp này, tại mỗi khoảng giữa các điểm tới hạn liền kề, đạo hàm $f'$ vẫn giữ nguyên dấu của nó (phát biểu này hiển nhiên về mặt hình học, nhưng không dễ chứng minh lắm).

Trong trường hợp một “cụm” các điểm tới hạn, vectơ của một điểm nhất định $x_0$ không thể nghiên cứu cực trị tại điểm này bằng dấu của đạo hàm.

Ví dụ 2. Ngoài ra còn có các hàm $f$ và $g$, khả vi trên $R$, sao cho điểm 0 là điểm cực đại của một trong số chúng và là điểm cực tiểu của hàm kia, nhưng tại tất cả các điểm trong một lân cận nhất định của điểm 0 thì đạo hàm $f'(x)$ và $g'(x)$ đều có cùng dấu.

Chúng tôi sẽ không đưa ra công thức rõ ràng cho các hàm được yêu cầu mà sẽ giới hạn ở đồ thị của chúng (Hình 2); Xin lưu ý rằng các ví dụ về hàm không nhất thiết phải được xây dựng “bằng ngôn ngữ của công thức”; chúng có thể được vẽ một cách đơn giản).

Phải làm gì trong trường hợp này? Không thể đưa ra lời khuyên chung chung. Nếu bạn nhận được gợi ý từ một hoặc một thông báo khác rằng điểm tương tự $x_0$ là điểm tối thiểu của hàm $f$, thì bạn có thể thử chứng minh bất đẳng thức $f(x) > f(x_0)$ cho tất cả $x$ từ một lân cận nào đó của điểm $x_0$ “bất cứ lúc nào”.

Trong ví dụ 1, điểm 0, xung quanh đó các điểm tới hạn được “tích lũy” cũng rất tới hạn. Tuy nhiên, điều này là không cần thiết.

Ví dụ 3. Trong mọi lân cận của điểm 0 có vô số điểm tới hạn của hàm số

$$f(x) = \begin{cases} x + x^2 \cos \frac{1}{x^2}, & \text{ если } x \neq 0, \\ 0, & \text{ если } x = 0, \end{cases}$$

tại điểm 0 là không quan trọng.

Kiểm tra xem

$$f'(x) = \begin{cases} 1 + \frac{2}{x} \sin \frac{1}{x^2}, & \text{ если } x \neq 0, \\ + 2x \cos \frac{1}{x^2}, & \text{ если } x = 0, \\ 1, & \text{ если } x = 0. \end{cases}$$

Vì trong bất kỳ vùng lân cận nào của điểm 0, đạo hàm $f'$ đổi dấu (tại sao?), nên nó trở thành 0 trong bất kỳ vùng lân cận nào *); nó giống nhau

*) Thật dễ dàng để chứng minh điều này trong hệ thống này bằng cách sử dụng các định lý từ đoạn 84 của sách “Đại số và sự khởi đầu của phân tích 10”.

Cơm. 2

Cơm. 3.
