---
id: 1980-6-vertgeym-metod-nepodvizhnyih-tochek-64ae7a4f
issue: kvant_1980_6
year: 1980
number: "6"
title: Phương pháp điểm cố định
authors:
  - Вертгейм Б. А.
rubric: osnovnye-stati
page_first: 7
page_last: 11
page_labels: 5-9
tag: YFXT
lang: vi
source: kvant_digital
extraction: vision
content_sha256: 4b4b20a23afd5c7fdb0aeb6f3ab01c8f9399ee98c680bed58e47442acc86b58c
prompt_sha256: draft-1
translated_from: content/ru/1980/06/articles/04_vertgeym-metod-nepodvizhnyih-tochek-64ae7a4f.md
source_content_sha256: a6910bcdace299ea28f5d178ae5b978332b1cdaf2664d6020491b6d872f06469
translation_model: draft
translation_run: vi-draft-2026-10-31
translation_quality: draft
---

⟦folio 5⟧

B. Werheim

Phương pháp
văn phòng phẩm
điểm

Khi chúng ta đang tìm kiếm lời giải của một số phương trình, thật tốt khi biết trước rằng nó có lời giải - bởi vì nếu không thì tại sao lại lãng phí thời gian? Thông báo này trở nên nghiêm trọng khi nói đến lời giải các phương trình và hệ thống phức tạp trên các máy tính mạnh với thời gian sử dụng máy tính đắt đỏ. Do đó, cái gọi là các định lý tồn tại và đảm bảo trước sự tồn tại của lời giải, đóng một vai trò rất quan trọng. Một trong số đó, định lý điểm cố định của Brouwer, một định lý thú vị và hữu ích ngay cả ở cấp phổ thông, sẽ được thảo luận trong bài viết này.

Đi bộ
Nanhem từ một cuộc dạo chơi, ghi nhớ những lợi ích và sự vĩnh cửu của việc di chuyển; trên đường đi sẽ có cả điểm cố định và phương trình.

Putnikovoevoe một người đi từ điểm $a$ đến điểm $b$, người kia đi bộ suốt trên đường $ab$. Rõ ràng, cuộc gặp gỡ của họ là không thể tránh khỏi: các đường đi muốn bằng nhau một lần (ở cùng một điểm vào cùng một thời điểm). Hãy để chúng tôi mô tả điều này chi tiết hơn (Hình 1).

Đặt $x$ là tọa độ của đường đi đầu tiên ($a \leqslant x \leqslant b$) và đặt tốc độ của nó không đổi; $y$ là tọa độ của giây ($a \leqslant y \leqslant b$). Mỗi giá trị $x$ (vị trí của đường dẫn đầu tiên) tương ứng với một giá trị duy nhất $y$ (vị trí của đường dẫn thứ hai cùng lúc); vậy là ta có hàm $y = f(x)$. phương trình

$$f(x) = x$$

quyết định địa điểm gặp mặt.

Ví dụ 1. Đặt $a = 0$, $b = 1000$ m, $y = 100 + 0,7x$. Nếu $x = 0$ thì $y = 100$; nếu $x = 1000$, thì $y = 800$ - cái đầu tiên đã đi vòng quanh! Phương trình 100+

Hình 1

⟦folio 6⟧

+0,7x = x cho tọa độ x = 333 1/3 m - ở đây tọa độ thứ nhất sẽ đuổi kịp tọa độ thứ hai.

Nếu chuyển động của giây là chuyển động cuối cùng thì cả hàm f và phương trình hội tụ sẽ cần thiết hơn, nhưng vẫn rất khó có khả năng xảy ra ít nhất một cuộc gặp gỡ.

Tuy nhiên, điều “rõ ràng” này không làm căng thẳng chúng ta với tư cách là những nhà toán học; Trước khi đi xa hơn, chúng ta sẽ tinh chỉnh công thức toán học của bài toán và chứng minh sự tồn tại của cuộc gặp gỡ.

Giả sử (như trong Ví dụ 1) hàm f hiển thị đoạn [a; b] vào chính nó, nghĩa là với mọi x ∈ [a; b] ta có a ∼ f(x) ∙ b. Khi đó bất kỳ lời giải nào của phương trình f(x) = x được gọi là điểm cố định của ánh xạ f. (Trong ví dụ của chúng ta, điểm cố định chính xác là điểm gặp nhau.) Nó tồn tại khi nào?

Định lý. Đối với bất kỳ hàm liên tục f nào biểu diễn đoạn [a; b] vào chính nó thì có một điểm cố định.

Trong định lý, cả tính liên tục của hàm f và việc chúng ta đang nói về một đoạn đều cần thiết.

Bài tập 1. Cho ví dụ về hàm f không liên tục biểu diễn [a; b] vào chính nó, không có điểm cố định.

Bài tập 2. Cho ví dụ về hàm số liên tục ánh xạ vào chính chúng không có điểm cố định: a) Hợp của hai đoạn [a; b] ∪ [c; đ]; b) * tích phân ]a; b[.

Để chứng minh định lý, chúng ta sẽ trang bị cho mình những chiếc bút chì màu đỏ và những bức ảnh. Trước khi sử dụng chúng, chúng ta hãy ký hiệu

$$\varphi(x) = f(x) - x.$$

Rõ ràng là c ∈ [a; b] sẽ là điểm cố định của f khi và chỉ nếu c là nghiệm của phương trình $\varphi(x) = f(x) - x = 0$. Vì vậy, chúng ta sẽ tìm nghiệm nguyên của phương trình này. Lưu ý rằng từ điều kiện a ⟦ x ⟧, a ≤ f(x) ≤ b, $\varphi(a) ≥ 0$ và $\varphi(b) ≤ 0$ liền theo sau. Chúng ta sẽ giả sử rằng cả hai bất đẳng thức đều nghiêm ngặt (nếu không thì bài toán lời giải). Bây giờ chúng ta hãy chia đoạn [a; b] thành 10 phần bằng nhau và tô màu đỏ tất cả các đoạn có giá trị

$$\cos x^3 - x = 0?$$

Hàm cos x³ liên tục; nó ánh xạ đoạn [−π/2, π/2] vào chính nó (tiếp tục vào đoạn [−1, 1]); do đó, theo định lý, tồn tại lời giải c ∈ [−π/2, π/2].

⟦folio 7⟧

Lưu ý rằng các số $a_n, \delta_n$ là các số gần đúng với gốc và đoạn đó có thể được chia không phải thành 10 mà thành 2 phần; Kỹ thuật này (phương pháp Bolshano, được đặt theo tên của nhà toán học người Séc) thực sự được sử dụng cùng với các thuật toán khác cho phương trình lời giải gần đúng.

Ngoài ra, định lý của chúng ta không nói gì về số lượng điểm cố định: rõ ràng là có thể có nhiều điểm cố định.

Tách cà phê

Và bây giờ - một tách cà phê! Đặt nó theo chuyển động tròn đều, chúng ta sẽ thấy một điểm cố định ở trung tâm. Đối với một số chuyển động, hình ảnh phức tạp hơn, nhưng nếu bạn xem xét vị trí của bộ phận tại hai thời điểm khác nhau, bạn có thể tìm thấy một hạt bất động theo nghĩa là nó ở cả hai lần - không phải, có lẽ, không phải lúc nào cũng vậy! - ở cùng một chỗ. Điều này rất đúng nếu bạn chấp nhận tình trạng vật lý là bất động của một bộ phận gần các bức tường do ma sát, và điều đó không tốt lắm - nhưng đúng! - và nếu không có điều kiện như vậy, miễn là có sự liên tục của ánh xạ tương ứng (nghĩa là các hạt “gần” sẽ không phân kỳ quá xa).

Để “toán học hóa” tình huống đang được xem xét, chúng ta sẽ cần một số định nghĩa.

Đặt $M$ là một tập hợp các điểm (ví dụ: một phần của đường thẳng, mặt phẳng hoặc không gian); $f$ là ánh xạ của tập hợp $M$ vào chính nó: nó gán cho mỗi điểm $x \in M$ ảnh của nó $y = f(x) \in M$. Ánh xạ như vậy được gọi là liên tục nếu với bất kỳ điểm $x_0 \in M$ và bất kỳ $E > 0$ nào đều có $\delta > 0$ sao cho đối với tất cả các điểm $x \in M$ được xóa khỏi $x_0$ một khoảng cách nhỏ hơn $\delta$, khoảng cách giữa các hình ảnh của chúng $f(x_0)$ và $f(x)$ nhỏ hơn $\varepsilon$.

Đối với trường hợp $M$ nằm trên trục số, khoảng cách giữa các điểm là $|x_0 - x|$, giữa ảnh của chúng - $|f(x_0) - f(x)|$, do đó định nghĩa của chúng ta về cơ bản trùng với định nghĩa của hàm liên tục (“Đại số và phần đầu của phân tích 9”, đoạn 38).

Ý nghĩa trực quan của định nghĩa là bản đồ liên tục $f$ không được có điểm gián đoạn - các điểm rất gần không thể di chuyển quá xa nhau.

Như trước đây, chúng ta gọi điểm $x \in M$ là điểm cố định của ánh xạ $f$ từ tập $M$ vào chính nó nếu $f(x) = x$.

Khi nào ánh xạ $f$ nhất thiết phải có điểm cố định? Đáp số đưa ra câu trả lời cho câu hỏi này

Định lý Brouwer
về một điểm cố định

Định lý nổi tiếng này đã được chứng minh một cách chặt chẽ cách đây không lâu - vào năm 1911*). Cùng với nhiều khái quát hóa, nó đóng vai trò chủ đạo trong một số lĩnh vực của toán học hiện đại. Các định lý về điểm cố định rất quan trọng cả về mặt lý thuyết lẫn ứng dụng: chúng được sử dụng để tính toán cánh máy bay, phân tích các chiến lược tối ưu và trạng thái cân bằng trong trò chơi cũng như trong các mô hình kinh tế toán học.

Định lý Brouwer. Mọi ánh xạ liên tục $f$ của đường tròn $M$ (cùng với ranh giới của nó) vào chính nó đều có một điểm liên tục.

Định lý này không chỉ đúng với đường tròn $M$, mà còn đúng với bất kỳ tập giới hạn lồi nào chứa ranh giới của nó, ví dụ, đối với một góc vuông, một hình tam giác hoặc một đa giác nói chung lồi trên một mặt phẳng, đối với một khối lập phương hoặc một quả bóng trong không gian.

*) L. E. Ya. Brouwer - nhà toán học người Hà Lan; trước ông, định lý này đã được nhà toán học người Latvia P. Bol sử dụng và nó còn được gọi là định lý Bol-Brauer.

⟦folio 8⟧

Hình 4.

Tuy nhiên, điều đó không đúng với mọi $M$:

Bài tập 3. Cho ví dụ về tập giới hạn $M$ trên mặt phẳng và ánh xạ liên tục của nó vào chính nó mà không có điểm cố định.

Bài tập 4*. Xây dựng bản đồ liên tục của một đường tròn không có ranh giới vào chính nó và không có điểm cố định.

Bài tập 5. Xây dựng ánh xạ không liên tục của một đường tròn (có ranh giới $M$) vào chính nó mà không có điểm cố định.

Chúng ta sẽ không chứng minh định lý Browser trong trường hợp tổng quát nhất mà sẽ xét trường hợp $M$ là tam giác đều. Để chứng minh điều đó, chúng ta cần có bút chì màu, nhưng hiện tại có ba loại: đỏ, xanh lam và xanh lục. (Trong không gian sẽ cần bốn!) Họ sẽ cần phải chứng minh một tuyên bố phụ trợ được gọi là

Bổ đề Sperer

Hình 4 cho thấy một “lưới” để bắt các điểm trong tam giác đều $ABC$ từ cạnh $a$. Các nút được đánh dấu bằng các vòng tròn, 3 đường (cạnh) xuất phát từ mỗi nút, kết nối nó với các nút lân cận. Các ô mạng là các hình lục giác đều ở cạnh $b$. Các cạnh của tam giác được chia thành $n$ phần bằng nhau, các điểm chia là tâm của các ô biên. $nb\sqrt{3} = a$ và $(n+1)(n+2)/2$ là tổng số ô.

Mỗi đỉnh bên trong thuộc về những đỉnh đó và đỉnh viền thuộc về hai ô.

Bây giờ chúng ta đánh dấu bằng số 1 tất cả các ô ngoại trừ cạnh cuối cùng, số 2 - các ô của ô thứ hai và số 3 - các ô của ô thứ ba (Hình 4). Chúng ta sẽ đặt các ô (nội bộ) còn lại có số 1, 2, 3 hoàn toàn tùy ý. Màu sắc các ô loại 1, 2 và 3 lần lượt là xanh lá cây, xanh dương và đỏ. Chúng ta gọi một đỉnh là hoàn chỉnh nếu nó được chứa trong các ô có cả ba màu.

Bổ đề. Có một đỉnh đầy đủ*).

Bằng chứng. Chúng tôi xây dựng một đường gãy từng bước, tạo nó từ các cạnh của “loại 1-2” liền kề với các ô có số 1 và 2. Hãy bắt đầu từ cạnh, theo điều kiện, chỉ có một cạnh “hai màu” như vậy $p_0p_1$ và trong một số bước hữu hạn, chúng ta sẽ đạt đến một đỉnh hoàn chỉnh: nếu một cạnh thuộc loại 1-2 $p_{k-1}p_k$, $k=1, 2, \dots$, dẫn chúng ta đến một đỉnh không hoàn chỉnh $p_k$, khi đó có một cạnh khác thuộc loại 1-2 phát ra từ nút $p_k$ (Hình 5), nó cho ra đỉnh $p_{k+1} \neq p_k$. Rõ ràng, con đường này không quay trở lại rìa hoặc các đỉnh đã đi qua (tại sao?). Vì tập hợp các đỉnh là hữu hạn nên đường đứt nét nhất thiết phải kết thúc ở một đỉnh hoàn chỉnh.

Thiên nga, ung thư và shuka

Bây giờ chúng ta hãy chứng minh định lý Browser cho trường hợp $M$ đúng

*) Bổ đề này chỉ là một phần trường hợp dấu của bổ đề do nhà toán học người Đức Sperer đưa ra.

Hình 5.

⟦folio 9⟧

tam giác $ABC$ (Hình 4). Hãy đánh dấu điểm $A$ bằng số 1, $B$ bằng số 2, $C$ bằng số 3 và viết các số này vào ba ô tương ứng. Tiếp theo, trong các ô có tâm ở cạnh $AB$, chúng ta viết 1, trên $BC$ - 2; trên $CA$ - 3. Mỗi điểm bên trong $x$ được gán một nhãn - một trong các số 1, 2, 3 - theo quy tắc sau: số 1, nếu khoảng cách từ điểm $x$ đến cạnh $AB$ không lớn hơn khoảng cách từ điểm $y=f(x)$ đến $AB$ (điểm $x$ là không "giảm" khi $f$ được hiển thị); nếu không phải như vậy thì số là 2 khi điểm $x$ không tiến tới $BC$ (khoảng cách từ $x$ đến $BC$ không lớn hơn khoảng cách từ $y$ đến $BC$); trong các trường hợp khác, chúng tôi lấy 3 - trong trường hợp này, điểm $x$ di chuyển ra khỏi cạnh $CA$ (xem trong Hình 4 các vùng dành cho $\vec{x}y$, tương ứng với các nhãn 1, 2, 3). Chúng ta hãy viết dấu tâm của nó tại mỗi điểm bên trong. Sử dụng bổ đề Spernan, chúng ta tìm thấy đỉnh hoàn chỉnh $x_0$ và nhớ lại ý nghĩa của câu chuyện ngụ ngôn của Krylov:

...Thiên nga lao vào mây,
Ung thư đang di chuyển ngược
và tsiuka bị kéo xuống nước -
Đúng, nhưng mọi thứ vẫn còn đó!
Chúng tôi chỉ đang tìm một điểm cố định: tương tự như chiếc xe đẩy này trong truyện ngụ ngôn, có các ô có số 1, 2, 3 được liên kết với toàn bộ đỉnh $x_0$. (Đỉnh này “gần như bất động” - với $b$ đủ nhỏ, nó tiến gần đến $AB$, $BC$ và $CA$ một chút, tức là nó di chuyển ít.)

Bây giờ chúng ta hãy lấy một chuỗi các số $b_1, b_2, ..., b_k$, ... có xu hướng tiến về 0 và với mỗi $k$, chúng ta tìm thấy đỉnh hoàn chỉnh của nó $x_k$. Chúng tôi nhận được một chuỗi các điểm

$$x_1, x_2, ..., x_k, ...$$

Trường hợp đầu tiên. Nếu chuỗi này hội tụ*) đến điểm $\bar{x} = \lim_{k \to \infty} x_k$ thì $\bar{x}$ là điểm cố định của ánh xạ này. (Tính bất động của nó xuất phát từ thực tế là $\bar{x}$ không tiếp cận bất kỳ cạnh nào trong ba cạnh của tam giác.)

Bài tập 6. Chứng minh điểm $\bar{x}$ cố định.

Trường hợp thứ hai. Nếu dãy $x_1, x_2, ..., x_k$, ... không hội tụ thì ta có thể chọn dãy số $n_1 < n_2 < ... < n_k < ...$ sao cho dãy điểm

$$x_{n_1}, x_{n_2}, ..., x_{n_k}, ...$$

hội tụ đến một điểm nào đó $\bar{x}' = \lim_{k \to \infty} x_{n_k}$.

Bài tập 7. Chứng minh sự tồn tại của dãy số $n_1, n_2, ..., n_k, ...$ và tính bất động của điểm $\bar{x}'$.

Phát triển phương pháp điểm cố định

Định lý của Browser, mà chúng tôi đã chứng minh cho một đoạn thẳng và cho một hình tam giác, không chỉ khái quát hóa cho không gian ba chiều (như đã nêu ở trên) mà còn cho “không gian có số chiều bất kỳ”. Hơn nữa, nhà toán học người dùng J. Schauder đã khái quát hóa nó cho trường hợp không gian “vô hạn chiều”. Hướng đi này được phát triển hơn nữa trong công trình của Viện sĩ A. N. Tikhonov. Nhà toán học người Ba Lan S. Banach đã chứng minh một định lý quan trọng về tỷ lệ của không gian, làm phong phú thêm phương pháp điểm cố định. Gần đây, các công trình tương tự như Hình 4 đã được sử dụng để tính toán trên máy tính khi tiếp cận các điểm cố định và cho lời giải nhiều mặt bài toán.

Bài tập

8. Áp dụng định lý Browser (cho đoạn) cho thấy phương trình sau có lời giải: a) $x - \cos x = 0$; b) $\cos (\sin x) - x = 0$.

9. Ánh xạ $f:(x, y) \rightarrow (x', y')$, trong đó $x' = x^2 + 1, 5xy, y' = 0, 5xy + y^2$, có một điểm cố định trên đoạn $S = \{(x, y) | x \geq 0, y \geq 0, x + y = 1\}$. Chứng minh điều này bằng định lý Browser và giải hệ $x = x^2 + 1, 5xy; y = 0, 5xy + y^2$.

10. Chứng tỏ rằng hệ thống

$$\begin{cases} x = \sin(x + y), \\ y = 0, 5(x^2 + xy^3) \end{cases}$$

có lời giải.

11. Khám phá hệ thống

$$\begin{cases} x_1 = x_2^2 + 2x_2x_3 + x_1x_2, \\ x_2 = x_3^2 + x_3x_1, \\ x_3 = x_1^2 + x_1(x_2 + x_3) \end{cases}$$

về sự tồn tại của lời giải khác 0 (theo định lý Browser). Giải quyết nó bằng các phương tiện cơ bản.
