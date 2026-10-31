---
id: 1981-6-aleksandrov-smirnov-v-chem-delo-33457048
issue: kvant_1981_6
year: 1981
number: "6"
title: Có chuyện gì vậy?
authors:
  - Александров Н.
  - Смирнов П.
rubric: smes
page_first: 12
page_last: 12
page_labels: "10"
tag: GS8N
lang: vi
source: kvant_digital
extraction: vision
content_sha256: ab4f18587a94176ef1497bfcc8c22323057f2c58e5c1cfc56ea07b745d08e88e
prompt_sha256: draft-1
translated_from: content/ru/1981/06/articles/06_aleksandrov-smirnov-v-chem-delo-33457048.md
source_content_sha256: e09c0cb76c313e208a741a0483e3beddab736cd2ddc17e92ae4af7bb91d501be
translation_model: draft
translation_run: vi-draft-2026-10-31
translation_quality: draft
---

⟦folio 10⟧

các cạnh $r$ được kết nối trong $G'$ bằng một chuỗi đơn giản - phần còn lại của đường viền) và các đỉnh của đồ thị $G'$ giống với các đỉnh của $G$. Nếu $G'$ chưa phải là cây, tức là $G'$ cũng có đường viền (Hình 11 b), thì chúng ta có thể lấy một cạnh tùy ý $r_2$ của đường viền này và loại bỏ nó, thu được một biểu đồ cố định $G''$ có cùng các đỉnh như $G$, v.v. Vì số cạnh là hữu hạn nên quá trình này phải ở một số bước; nói cách khác, sau khi loại bỏ cạnh $r_k$ ta được một đồ thị liên thông $G^*$ chứa tất cả các đỉnh của đồ thị $G$ và không còn đường viền nữa, tức là nó là một cái cây. Đồ thị $G^*$ được gọi là cây cực đại của $G$ và các cạnh $r_1, r_2, ..., r_k$ phải bị loại bỏ khỏi $G$ để có được cây cực đại $G^*$ được gọi là cầu nối.

Nếu $B$ là số đỉnh trong đồ thị $G$ thì cây cực đại $G^*$ cũng có $B$ đỉnh. Theo (1), đồ thị $G^*$ có $B-1$ cạnh, và do đó số cạnh của đồ thị $G$ bằng $B-1+k$ (để thu được $G$ từ $G^*$, cần phải “trả lại” $k$ các cạnh cầu bị loại bỏ). Kể từ đây,

$$\chi(G) = B - (B-1+k) = 1-k. \quad (2)$$

Vì $k \ge 1$, chúng ta nhận được $\chi(G) \leq 0$. Do đó, tính đến (1), chúng ta thấy rằng đối với bất kỳ biểu đồ liên thông nào $G$, mối quan hệ sau đây đúng:

$$\chi(G) \leq 1,$$

trong đó đạt được sự bình đẳng khi và chỉ khi $G$ là một cái cây.

Hơn nữa, theo (2), số lượng người nhảy bằng

$$k = 1 - \chi(G).$$

Có chuyện gì vậy?

Theo “tính chất cơ bản của nguyên hàm” (“Đại số và nguyên tắc phân tích 9-10”, đoạn 57), nếu hàm tùy ý của hai hàm trùng nhau thì các hàm này phải khác nhau một hằng số. Các hàm tùy ý:

$$a) y_1 = \frac{1}{1-x^2}$$

$$n) y_2 = \frac{x^2}{1-x^2},$$

nhiệm vụ

17. Chứng minh rằng nếu đồ thị $G$ chứa các thành phần $l$ thì $\chi(G) \leq l$. Khi nào đạt được sự bình đẳng?

18*. Chúng ta sẽ nói rằng trong biểu đồ $G$ một hệ thống dòng điện được cho nếu mỗi cạnh được gán một hướng (được biểu thị bằng một mũi tên) và một số hướng không âm (tok) và quy tắc Kirchoff được đáp ứng: đối với mỗi đỉnh, tổng các dòng điện đi vào nó bằng tổng các dòng điện đi vào nó. Chứng minh rằng nếu đồ thị là một cây thì nó chỉ chứa một hệ ba dòng điện (tất cả các dòng điện đều bằng 0).

19. Đặt $G$ là một đồ thị liên thông, $G^*$ cây cực đại của nó và $r_1, r_2, ..., r_k$ các cây cầu (nghĩa là các cạnh của $G$ không có trong $G^*$). Chứng minh rằng nếu dòng điện trên các cạnh $r_1, r_2, ..., r_k$ được xác định tùy ý thì chúng có thể được bổ sung duy nhất với các dòng điện trên các cạnh còn lại để thu được hệ dòng điện trong $G$.

Gợi ý. Đối với mỗi jumper $r_i$ có một đường viền đơn vị chứa nó và không chứa các jumper khác. Nếu chúng ta truyền dọc theo mạch này một dòng điện có độ lớn và hướng như được chỉ ra trên nút nhảy $r_i$, sau đó lấy tổng của tất cả các “dòng điện mạch” này, thì chúng ta sẽ thu được hệ dòng điện cần thiết trên biểu đồ $G$. Nếu có hai hệ dòng điện khác nhau trùng nhau trên các dây nhảy, thì sự khác biệt của chúng sẽ là một hệ dòng điện không tầm thường trên cây $G^*$.

Vì vậy, một chuyến tham quan vào lý thuyết đồ thị, được thực hiện dưới sự hướng dẫn của Cấu trúc liên kết Angell, hóa ra lại hữu ích cho lời giải toán học và thậm chí cả vật lý bài toán. Chúng tôi hy vọng bạn thích nó và bạn sẽ muốn tiếp tục. Trong số tiếp theo của tạp chí, chúng tôi sẽ tập trung vào các vấn đề sâu hơn về cấu trúc liên kết đồ thị. Nhưng để nghiên cứu chúng, chúng ta sẽ phải lắng nghe kỹ hơn “con quỷ đại số trừu tượng”.

Có chuyện gì vậy?

Theo “tính chất cơ bản của nguyên hàm” (“Đại số và Nguyên tắc phân tích 9-10”, đoạn 57), nếu hàm tùy ý của hai hàm trùng nhau thì các hàm này phải khác nhau một hằng số. Các hàm tùy ý:

$$a) y_1 = \frac{1}{1-x^2}$$

$$n) y_2 = \frac{x^2}{1-x^2},$$

nhiệm vụ

17. Chứng minh rằng nếu đồ thị $G$ chứa các thành phần $l$ thì $\chi(G) \leq l$. Khi nào đạt được sự bình đẳng?

18*. Chúng ta sẽ nói rằng trong biểu đồ $G$ một hệ thống dòng điện được cho nếu mỗi cạnh được gán một hướng (được biểu thị bằng một mũi tên) và một số hướng không âm (tok) và quy tắc Kirchoff được đáp ứng: đối với mỗi đỉnh, tổng các dòng điện đi vào nó bằng tổng các dòng điện đi vào nó. Chứng minh rằng nếu đồ thị là một cây thì nó chỉ chứa một hệ ba dòng điện (tất cả các dòng điện đều bằng 0).

19. Đặt $G$ là một đồ thị liên thông, $G^*$ cây cực đại của nó và $r_1, r_2, ..., r_k$ các cây cầu (nghĩa là các cạnh của $G$ không có trong $G^*$). Chứng minh rằng nếu dòng điện trên các cạnh $r_1, r_2, ..., r_k$ được xác định tùy ý thì chúng có thể được bổ sung duy nhất với các dòng điện trên các cạnh còn lại để thu được hệ dòng điện trong $G$.

Gợi ý. Đối với mỗi jumper $r_i$ có một đường viền đơn vị chứa nó và không chứa các jumper khác. Nếu chúng ta truyền dọc theo mạch này một dòng điện có độ lớn và hướng như được chỉ ra trên nút nhảy $r_i$, sau đó lấy tổng của các “dòng điện mạch” này, thì chúng ta sẽ thu được hệ dòng điện cần thiết trên biểu đồ $G$. Nếu hệ thống dòng điện trùng nhau trên các dây nhảy, thì sự khác biệt của chúng sẽ là một hệ thống dòng điện không hề tầm thường trên cây $G^*$.

Vì vậy, một chuyến tham quan vào lý thuyết đồ thị, được thực hiện dưới sự hướng dẫn của Cấu trúc liên kết Angell, hóa ra lại hữu ích cho lời giải toán học và thậm chí cả vật lý bài toán. Chúng tôi hy vọng bạn thích nó và bạn sẽ muốn tiếp tục. Trong số tiếp theo của tạp chí, chúng tôi sẽ tập trung vào các vấn đề sâu hơn về cấu trúc liên kết đồ thị. Nhưng để nghiên cứu chúng, chúng ta sẽ phải lắng nghe kỹ hơn “con quỷ đại số trừu tượng”.

N. Alexandrov,
P. Smirnov
