---
id: 1976-10-deynega-logicheskie-zadachi-i-neravenstva-6912f6a0
issue: kvant_1976_10
year: 1976
number: "10"
title: Logic bài toán và bất đẳng thức
authors:
  - Дейнега А. В.
rubric: kvant-dlya-mladshih-shkolnikov
rubric_sub: «Квант» для младших школьников
page_first: 59
page_last: 61
page_labels: 57-59
tag: 4TND
lang: vi
source: kvant_digital
extraction: vision
content_sha256: 93b760e8718462c424c2d14921e7411224e8a0f04a1e792e82dfce0c44757e97
prompt_sha256: draft-1
translated_from: content/ru/1976/10/articles/17_deynega-logicheskie-zadachi-i-neravenstva-6912f6a0.md
source_content_sha256: e4b82ebf33880903ea9940a02e22093e03bf864ea168d197a99950ec28493926
translation_model: draft
translation_run: vi-draft-2026-10-31
translation_quality: draft
---

⟦folio 57⟧

Logic bài toán và bất đẳng thức

Làm xong bài tập về nhà, học sinh lớp 5 Voloda bắt đầu giải logic bài toán Số 1291 trong sách giáo khoa “Matematika, 5” (M., 1976), được giao làm bài tập về một vòng tròn toán học. Cô ấy đây.

Ba vận động viên tham gia giải đua hiện đại: Avdeev, Vasiliev và Semenov. Đầu tiên, một khán giả nói rằng Avdeev sẽ là người đến đầu tiên, người thứ hai - rằng Semyonov sẽ không phải là người cuối cùng, và người thứ ba - rằng Vasilyev sẽ không phải là người đến đầu tiên. Sau cuộc đua, hóa ra một khán giả đã rời đi và hai người còn lại đã mắc lỗi. Buổi hát kết thúc như thế nào?

Thời gian trôi qua, Voloda vẫn chưa thể quyết định được bài toán. Cuối cùng, anh quay sang nhờ chị gái Natasha giúp đỡ.

- Hãy tự suy nghĩ đi! - người chị nói, đang bận tâm đến việc riêng của mình.

- Thế là anh cứ nghĩ... làm ơn... anh không thường xuyên liên lạc với em...

“Được rồi,” theo Natasha. “Hãy giải bài toán bằng cách sử dụng các bất đẳng thức.” Khỏe?

- Tôi không bận tâm, nhưng nó thế nào - bất bình đẳng? Giáo viên không thể hiện như vậy, chúng tôi giải được những câu logic... - Voloda ngạc nhiên.

- Thế thì sao? Và chúng tôi sẽ quyết định theo cách riêng của mình. Đầu tiên, hãy biểu thị vị trí mà Avdeev chiếm giữ là a, bởi Vasilyev là b, bởi Semenov là c. Có ba người chạy nên mỗi người có thể giành vị trí thứ nhất, thứ hai hoặc thứ ba.

Điều này có nghĩa là a, b và c chỉ có thể bằng 1, 2 hoặc 3. Hãy nghĩ xem làm thế nào để viết kết quả này dưới dạng bất đẳng thức? Số tự nhiên nào nằm giữa những số tự nhiên nào? b? c?

Voloda suy nghĩ và viết ra: 1  a  3, 1  b  3, 1  c  3.

“Đúng vậy,” người chị nói. “Bây giờ chúng ta hãy thử viết ra các điều kiện bài toán bằng cách sử dụng các đại lượng a, b và c.” Trong bài toán nó nói “Avdeev sẽ đến trước,” vì vậy a = 1. Hơn nữa, “Semyonov sẽ không phải là người cuối cùng,” có nghĩa là anh ấy có thể chiếm vị trí thứ 1 hoặc thứ 2, do đó, như chính bạn đã đồng ý, chúng ta sẽ viết c = 1 hoặc c = 2. Làm thế nào để biểu diễn điều này bằng cách sử dụng bất đẳng thức?

“Tôi hiểu,” Voloda nói. “Chúng ta phải viết như thế này: 1 ≤ c ≤ 2. Khi đó câu “Vasiliev will not going to first” sẽ được viết tương tự: 2 ≤ b ≤ 3.”

- Rất tốt. Hãy viết ra tất cả những gì chúng ta có được cùng nhau:

$$\begin{cases}
(1) a = 1, \\
(2) 1 \leq c \leq 2, \\
(3) 2 \leq b \leq 3.
\end{cases}$$

Chúng tôi sẽ gọi bản ghi đó là “hệ thống”. Nhưng hệ thống này chưa thể hiện mọi thứ trong bài toán. Ví dụ, chúng ta chưa sử dụng thực tế là “một khán giả rời đi và hai người còn lại mắc lỗi”. Làm thế nào chúng ta có thể viết dữ liệu này bằng cách sử dụng các bất đẳng thức?

- Bất bình đẳng?... Tôi không thể tưởng tượng được...

⟦folio 58⟧

Nhìn. Các từ “đoán” và “sai” thể hiện những “hành động” logic trái ngược nhau; chúng phản ánh lẫn nhau:
“đoán” - “không sai”
“Tôi đã sai” - “Tôi không đoán được.”
Như chúng ta có thể thấy, việc này được thực hiện bằng cách sử dụng các NOT riêng tư.
Đối với bài toán của chúng ta, hãy tạo một bảng:

| Tuyên bố trực tiếp | Tuyên bố trái ngược |
| :--- | :--- |
| Và bằng $B(A=B)$ | A không bằng $B(A \neq B)$; $A > B$ hoặc $A < B$ |
| Và hơn thế nữa $B(A > B)$ | Và không còn nữa $B(A \leq B)$ |
| Và ít hơn $B(A < B)$ | Và không ít hơn $B(A \geq B)$ |
| Tuyên bố trái ngược | Tuyên bố trực tiếp |

Natasha tiếp tục sử dụng bảng này, bạn có thể dịch cụm từ “một trong ba khán giả đoán được vị trí của người chạy, trong khi hai người còn lại bị nhầm” sang ngôn ngữ của sự bất bình đẳng. Chúng ta hãy cố gắng tự làm điều đó.
Volodya đã đối phó với nhiệm vụ này, chúng tôi trình bày những ghi chú của anh ấy.
Nếu người xem tôi đoán đúng, nhưng khán giả II và III sai (xem hệ thống (*)):

$$\begin{cases} a = 1, \\ c = 3, \\ b = 1. \end{cases}$$

Nếu người xem II đoán đúng nhưng khán giả I và III đoán sai:

$$\begin{cases} 2 \leq a \leq 3, \\ 1 \leq c \leq 2, \\ b = 1. \end{cases}$$

Nếu người xem III đoán đúng nhưng khán giả I và II đoán sai:

$$\begin{cases} 2 \leq a \leq 3, \\ c = 3, \\ 2 \leq b \leq 3. \end{cases}$$

"Đúng vậy." Hệ thống nói. “Bây giờ hãy nhìn xem: hệ thống đầu tiên không tốt…

- Vâng, điều này rõ ràng ngay lập tức: có $a = 1$ và $b = 1$ trong đó, nhưng Avdeev và Vasiliev không thể ngồi cùng một chỗ. Và thứ hai... từ đó dẫn đến $b = 1$, $c = 2$, $a = 3$. Cô ấy tốt! Bây giờ hãy xem... ai đã chiếm vị trí đầu tiên? Không ai? Điều này có nghĩa là hệ thống thứ ba cũng không phù hợp.

Vì vậy,” Volodya tuyên bố, “một kỷ lục hoàn hảo với kết quả như sau: Vasiliev chiếm vị trí đầu tiên, Semenov - thứ hai, Avdeev - thứ ba.

“Chà, bây giờ thêm một bài toán,” Natasha nói và lấy ra một số cuốn sách *).

Anya, Varya và Klava đã đi biểu tình. Một trong số họ đã ở

*) Tôi. Vâng. Depman, Những câu chuyện về đại số cũ và đại số mới, L., 1967, tr. 122.

⟦folio 59⟧

váy đỏ, bạn bè - màu trắng, cao cấp - màu xanh lam. Khi được hỏi mỗi cô gái mặc váy gì, họ trả lời 们 đáp số: Anya mặc đồ đỏ, Varya không mặc đồ đỏ, Klava không mặc đồ xanh. Trong đáp số này một trong ba câu là đúng, hai câu là sai. Mỗi cô gái đã mặc trang phục gì?

- Và cũng với sự trợ giúp của bất đẳng thức? - Voloda hỏi.
- Chắc chắn! - chị gái trả lời.
“Nhưng tôi không biết cái gì lớn hơn - xanh, đỏ hay trắng,” Voloda phẫn nộ, “và nói chung đây là một bài toán hoàn toàn khác, không giống cái trước.”
“Được rồi, tôi sẽ giúp bạn một chút,” Natasha nói. “Hãy đánh số màu.” Màu trống màu đỏ sẽ là màu đầu tiên, màu trắng sẽ là màu thứ hai và màu xanh lam sẽ là màu thứ ba.
“À... Vậy thì có lẽ tôi có thể quyết định bài toán,” Voloda nói sau một chút do dự. “Tôi sẽ biểu thị bằng a màu bảng của Anya, b là màu bảng của Varya và c là màu bảng của Klava.” Bây giờ tôi sẽ viết ra các điều kiện sử dụng bất đẳng thức
$$\begin{cases} a=1, \\ 2 \leq b \leq 3, \\ 1 \leq c \leq 2, \end{cases}$$

- Nhìn kìa, Natasha! Nhưng hóa ra đó là cùng một hệ thống! Và theo cách tương tự, chúng ta cần xem xét ba trường hợp trong đó một câu đúng và hai câu còn lại sai. Điều này có nghĩa là không cần giải bài toán, tôi có thể nói ngay rằng a=3, b=1 và c=2. Anya mặc váy xanh, Varya mặc đồ đỏ và Klava mặc đồ trắng!

“Điều đó hoàn toàn đúng,” sư tỷ trả lời. “Ở đây, có lẽ, ưu điểm quan trọng nhất của toán học được bộc lộ: bài toán hoàn toàn khác, được viết bằng ngôn ngữ của nó, có thể trở thành một và cùng một vấn đề.” Vì vậy, khi giải được một trong số chúng, chúng ta nhận được lời giải và phần còn lại bài toán. Khi lớn lên, bạn sẽ thấy rằng bài toán khác với vật lý, hóa học, kinh tế, sinh học thường hóa ra lại là cùng một bài toán.

Chà, bây giờ hãy giải thêm hai bài toán mà không cần sự giúp đỡ của tôi.

1. Sau khi làm bài kiểm tra toán, hai chị em nói với bố mẹ:
Sveta A.—Lần này tôi viết “5”.
Lyuda A.—Tôi không viết “3.”
Ira.—Tôi không viết “5.”
Sau khi kiểm tra tác phẩm, hóa ra hai chị em nhận được những đánh giá tích cực khác nhau và trong số ba nhận định, có một nhận định đúng, còn lại sai. Sveta, Lyuda và Ira đã đạt được điểm gì trong bài kiểm tra?

2. Ba anh em đều mang quân hàm đại úy, trung sĩ. Trong số ba tuyên bố “Alexey là một trung sĩ”, “Vladimir không phải là một trung sĩ” và “Semyon không phải là một trung sĩ”, chỉ có một tuyên bố đúng. Vấn đề cấp bậc cho anh em là gì?
