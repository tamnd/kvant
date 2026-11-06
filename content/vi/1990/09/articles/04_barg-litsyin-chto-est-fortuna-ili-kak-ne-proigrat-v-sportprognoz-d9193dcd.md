---
id: 1990-9-barg-litsyin-chto-est-fortuna-ili-kak-ne-proigrat-v-sportprognoz-d9193dcd
issue: kvant_1990_9
year: 1990
number: "9"
title: Vận may là gì hoặc Làm thế nào để không thua tại Sportprognoz
authors:
  - Барг А.
  - Лицын С.
rubric: osnovnye-stati
page_first: 10
page_last: 17
page_labels: 8, 9, 12, 13, 14, 15
lang: vi
source: kvant_digital
extraction: vision
content_sha256: 78bcb99257da4c1ac72096bcbc4f7f36f6bf391c3af87912b61ace10a6ca1bb8
prompt_sha256: draft-1
translated_from: content/ru/1990/09/articles/04_barg-litsyin-chto-est-fortuna-ili-kak-ne-proigrat-v-sportprognoz-d9193dcd.md
source_content_sha256: fae5acd0058fe2231f8a564936db00526acfea9f607d24a3164168ba54ed830b
translation_model: draft
translation_run: vi-draft-gaps-2026-11-05
translation_quality: draft
---

⟦folio 8⟧

---
running_head:
folio:
---

LÀ GÌ
VẬN MAY,

hoặc
Làm thế nào để không thua ở
"Sportproznoz"

Ứng viên khoa học kỹ thuật
A. BARG,
Ứng viên khoa học kỹ thuật
S. LITSYN

⟦folio 9⟧

---
running_head:
folio:
---

Truyện dân gian học đường kể về một người đàn ông sử dụng máy tính đã phát triển một hệ thống cho trò chơi “Sportloto” và giành được vận may. Người đàn ông chưa nhìn thấy điều này và khó có khả năng nó tồn tại vì không có chiến lược chiến thắng nào được biết đến cho trò chơi này. Nói cách khác, không thể quy định cụ thể cách chơi mà số tiền thắng được sẽ luôn lớn hơn số tiền bỏ ra mua bài. Các chiến lược chúng tôi đưa ra cũng không ngoại lệ. Tuy nhiên, có rất nhiều bài toán toán học thú vị gắn liền với “Sportloto” và các trò chơi chữ khác. Chúng tôi sẽ cho bạn biết về một số trong số họ.

Theo quy định, bài toán được liên kết với “Sportloto” và “Sportprognoz” để tính xác suất đoán được một số số chính xác nhất định (kết quả). Chúng tôi sẽ không quay lại những câu hỏi nổi tiếng này mà chỉ nói rằng xác suất đoán được sáu số trong số bốn mươi chín *) $p(49,6) \approx 7 \cdot 10^{-8}$; trong cùng ký hiệu $p(49,5) \approx 2 \cdot 10^{-5}$, $p(49,4) \approx 10^{-3}$, $p(36,5) \approx 3 \cdot 10^{-6}$ (bạn có thể tự chứng minh điều này).

Quy tắc của trò chơi

“Sportprognoz” được chơi như sau. 13 trận đấu được chọn từ lịch thi đấu thể thao, kết quả của trận đấu đó, theo ban tổ chức xổ số, rất khó dự đoán. Người chơi phải dự đoán kết quả các trận đấu này, đánh số “1” vào mỗi ô trong số 13 ô của bảng nếu tin rằng đội chủ nhà sẽ thắng, “2” - đội khách và “0” trong trường hợp hòa. Sau khi biết kết quả các trận đấu, tiền thắng được xác định

*) Hiện tại có 45 số trong thẻ Sportloto. Khi tác giả còn trẻ và nghiện Sportsloto, tấm thẻ có 49 số.

Giải thưởng được chia cho những người đoán ít nhất 11 kết quả và tăng dần theo số lần dự đoán đúng trên lá bài. Mỗi dự báo sẽ được biểu thị bằng vectơ 13 chiều (tức là một chuỗi gồm 13 chữ số) với các thành phần 0, 1 và 2. Ví dụ: vectơ $x=(1,1,0,2,2,1,2,0,0,0,1,1,2)$ sẽ có kết quả thắng trên sân khách trong các trận đấu 4, 5, 7 và 13, đội nhà thắng trong các trận đấu 1, 2, 6, 11 và 12 và không có kết quả nào trong các trận đấu còn lại.

Trong trò chơi "Sportloto", bạn cần đoán 6 trên 49 hoặc 5 trên 36 số. Những lá bài có ít nhất 3 số được rút ra từ kết quả rút ngẫu nhiên được coi là thắng. Dự báo trong trường hợp này có thể được mô tả bằng vectơ 49 (36) chiều chứa “0” ở 43 (31) vị trí và “1” ở 6 (5) vị trí còn lại. Số lượng các vị trí đơn lẻ tương ứng với số lượng dự đoán.

Trong mỗi lần rút thăm, một người chơi có thể đưa ra một số lựa chọn dự đoán. Chúng ta hãy gọi một tập hợp các tùy chọn này là hệ thống $l$ nếu, bất kể kết quả rút thăm như thế nào, có ít nhất một trong số chúng có ít nhất $l$ kết quả được đoán đúng. Đối với chúng tôi, chỉ những hệ thống $l$ có ​​$11 \leq l \leq 13$ cho “Sportprognoz” và với $3 \leq l \leq 6$ (5) cho “Sportloto” mới được quan tâm. Bạn có thể thu được các ví dụ rõ ràng về hệ thống $l$ có tối đa $l$ bằng cách điền vào tất cả các tùy chọn dự báo có thể có. Các hệ thống này không thú vị lắm, nếu chỉ vì số lượng thẻ “Sportprognoz” được điền trong trường hợp này là 1.594.323, tức là bạn cần chi khoảng nửa triệu rúp và khoảng hai năm làm việc liên tục (nửa phút cho mỗi thẻ). Đối với Sportloto con số tương ứng lớn hơn. Hãy nhớ rằng ngay cả sau khi hoàn thành việc điền, bạn không thể chắc chắn rằng số tiền thu được có vượt quá chi phí phát sinh hay không. Đối với $l$ nhỏ hơn, chúng tôi cũng sẽ cố gắng nghĩ đến các hệ thống trong đó tổng số tùy chọn có thể nhỏ hơn.

Vì vậy, nếu bạn chơi theo hệ thống thì ít nhất một trong những dự đoán của bạn

⟦folio none⟧

---
running_head:
folio:
---

Hoạt động modulo 3 và hệ thống l
Hệ 3 được xây dựng ở đoạn trước có một số tính chất màu đỏ (được nhà khoa học người Mỹ Richard Hamming phát hiện vào những năm 40), đòi hỏi phải giải thích hơi lạc đề một chút.
Chúng ta đang xử lý các vectơ có các thành phần có thể lấy các giá trị từ tập hợp $Z_3 = \{0,1,2\}$. Các phần tử của $Z_3$ có thể được cộng và nhân theo cách sao cho kết quả sẽ lại là các phần tử từ cùng một tập hợp. Để làm điều này, chỉ cần thực hiện phép cộng hoặc phép nhân tổng quát, tìm phần dư của phép chia kết quả cho 3 (như người ta nói, mang theo modulo 3). Ví dụ: $5 \equiv 2(\text{mod } 3), -2 \equiv 1(\text{mod } 3)$.
Sử dụng các thao tác này, chúng ta có thể định nghĩa phép cộng các vectơ ternary. Chúng tôi xác định tổng của vectơ $a$ và $b$ là vectơ $c$, mỗi tọa độ của nó là tổng modulo 3 của tọa độ tương ứng của vectơ $a$ và $b$. Ví dụ: $(0,1,1,2) + (1,2,1,1) = (1,0,2,0)$. Chúng ta hãy định nghĩa tích của một vectơ và một số ba ngôi $v \in Z_3$ là một vectơ có tọa độ thu được bằng cách nhân tọa độ của vectơ với $v$ modulo 3. Ví dụ: $2 \cdot (1,0,2,2) = (2,0,1,1)$. Trong toán học, các tập hợp vectơ như vậy với các phép cộng và nhân với một số được xác định trên chúng được gọi là không gian vectơ.

Bài tập 2. Kiểm tra xem hệ 3-$C_0$ được giới thiệu ở đoạn trước có các thuộc tính sau: đối với mọi vectơ $a \in C_0$ và hằng số $v \in Z_3$ thì tích $va$ cũng nhận $C_0$; với hai vectơ bất kỳ $a, b \in C_0$ tổng của chúng cũng là một vectơ từ $C_0$. Những hệ thống như vậy được gọi là tuyến tính.

Các phép toán modulo 3 cho phép chúng ta mô tả ngắn gọn về hệ 3 $C_0$. Đầu tiên, hãy lưu ý rằng tọa độ đầu tiên $(x_1, x_2)$ của vectơ từ $C_0$ có ​​thể là bất kỳ cặp số ba nào. Hãy gọi cặp này là số thứ ba của vectơ. Giá trị của hai tọa độ còn lại $x_3$ và $x_4$ có thể được tính bằng quy tắc sau (hành động modulo 3):

$$x_3 = x_1 + x_2, \quad x_4 = x_1 + 2x_2$$

(1) (kiểm tra!).

Bài tập 3. Có thể chọn tọa độ vectơ khác làm số không? Khi đó sẽ là loại nào và có quyền (1)?

4. Chứng minh rằng nếu một vectơ tùy ý (giống nhau) được thêm vào tất cả các vectơ của hệ $C_0$ thì các thuộc tính của nó với tư cách là hệ $l$ sẽ không thay đổi.

5. Sử dụng kết quả của Bài tập 4, hãy chỉ ra rằng trong hệ thống $C_0$ bạn có thể bao gồm bất kỳ vectơ định hướng nào (dự báo mà bạn thấy hợp lý nhất).

Giả sử bạn điền vào các thẻ theo hệ thống $C_0$. Tờ báo chính thức công bố kết quả các trận đấu được lưu hành (vector $y$). Làm thế nào để nhanh chóng tìm ra lá bài trúng thưởng (việc nó tồn tại xuất phát từ thuộc tính của hệ thống)? Một cách hiển nhiên nhưng đôi khi không phải là tốt nhất là so sánh kết quả rút bài với tất cả các lá bài đã hoàn thành và tìm ra số điểm xuất sắc nhất.

Để mô tả một phương pháp nhanh hơn, hãy sắp xếp lại phương trình (1) ở dạng tương đương:

$$x_1 + x_2 + 2x_3 = 0, \quad x_1 + 2x_2 + 2x_4 = 0.$$

Phương pháp của chúng tôi sẽ dựa trên thực tế là tọa độ của từng tọa độ của hệ $C_0$ thỏa mãn phương trình (2). Nếu $y$ thỏa mãn (2), nó thuộc hệ thống $C_0$ và thẻ tương ứng của nó có thể được tìm thấy theo số thứ ba của nó. Ngược lại, $y$ khác với một số vectơ $c = (c_1, c_2, c_3, c_4) \in C_0$ trong cùng tọa độ. Gọi số của nó là $j$. Hãy tìm $S_1 = y_1 + y_2 + 2y_3$ và $S_2 = y_1 + 2y_2 + 2y_4$.

Bài tập 6. Chứng minh có thể tìm được quân bài thắng $c$ như sau:

a) nếu $S_1 = 0$ và $S_2 \neq 0$ thì $j = 4$; nếu $S_2 = 0$ và $S_1 \neq 0$ thì $j = 3$ (trong trường hợp chung $c_j = y_j + S_i$, trong đó $i = 1$ hoặc $2$ là chỉ số khác 0 $S_i$);

b) nếu $S_1 \neq 0$ và $S_2 \neq 0$, thì đối với $S_1S_2 = 1$ $j = 1$ và $c_1 = y_1 + 2S_i$ (i - bất kỳ). Tại $S_1S_2 = 2$ $j = 2$ và $c_2 = y_2 + 2S_1 = y_2 + S_2$.

Câu ví dụ 1. Sử dụng phương trình trước để xác định lá bài gần nhất nếu kết quả trận đấu được biểu thị bằng vectơ $y = (2,1,2,1)$. Sau đó $S_1 = 1$, $S_2 = 0$. Chuyển sang trường hợp a), ta thu được $j = 3$ và $c_3 = y_3 +$

⟦folio 12⟧

---
running_head:
folio:
---

+ $S_1 = 0$. Vectơ $c = (2,1,0,1) \in C_0$ lại được tìm thấy, nằm cách $y$ 1 đơn vị.

Đối với “Sportprognoz” trong 4 trận đấu, phương pháp xác định lá bài chiến thắng này trông (và) cực kỳ cồng kềnh, đặc biệt là so với việc tìm kiếm đơn giản tất cả chín lá bài của hệ thống. Ưu điểm của nó sẽ được giải thích dưới đây.

Hãy để chúng tôi lưu ý thêm một ứng dụng của hệ thống được mô tả. Giả sử, khi điền vào thẻ “Dự báo thể thao” lớn, bạn tin rằng mình biết chính xác kết quả của 9 trên 13 trận đấu. Bạn muốn biết chắc chắn rằng khi dự đoán kết quả của bốn trận đấu còn lại, bạn sẽ sai không quá một lần. Sau đó, bạn nên điền 9 thẻ có tổ hợp cố định vào 9 vị trí đã biết và tất cả các vectơ của hệ 3 $C_0$ vào 4 vị trí còn lại.

Mã sửa lỗi

Người ta không nên nghĩ rằng các hệ thống $l$ được mô tả và nghiên cứu để thu được số tiền thắng lớn trong trình ghi nhật ký - các nhà toán học còn nhiều việc thú vị hơn để làm. Hóa ra là các cấu trúc rất giống nhau xuất hiện, chẳng hạn như trong lý thuyết truyền tải thông điệp. Hãy tưởng tượng rằng một vectơ gồm các chữ cái $k$ cần được truyền qua đường dây liên lạc có nhiễu, mỗi chữ cái trong số đó có thể mang một trong $q$ nghĩa (đối với các tin nhắn trong tiếng Nga $q = 34$ là các chữ cái trong bảng chữ cái và khoảng trắng giữa các từ). Chúng tôi cho rằng việc truyền trực tiếp có khả năng làm sai lệch ít nhất một chữ cái của tin nhắn, vì vậy chúng tôi muốn có cách sửa lỗi sau khi nhận.

Hãy tiến hành như sau. Hãy thêm một số chữ cái vào vectơ được truyền đi, tùy thuộc vào các chữ cái của tin nhắn gốc. Tập hợp thông báo mở rộng như vậy được gọi là mã và số lượng chữ cái trong thông báo mở rộng (mã vectơ) được ký hiệu là $n$ và được gọi là độ dài của mã. Nếu khi truyền một vectơ mã trong kênh liên lạc, xảy ra hiện tượng biến dạng các chữ cái $t$ thì vectơ dễ chịu nằm ở khoảng cách Hamming $t$ so với vectơ truyền đi. Dựa trên vectơ nhận được, cần phải tái tạo lại một cách rõ ràng vectơ đã truyền. Để làm được điều này, mã phải đáp ứng một số thuộc tính nhất định.

Tuyên bố. Mã $C$ sửa mọi lỗi $t$ trở xuống nếu tập hợp vectơ từ $E_q^n$ nằm ở khoảng cách $\leq t$ tính từ vectơ mã không giao nhau theo cặp.

⟦folio 13⟧

---
running_head:
folio:
---

7. Chứng minh rằng mỗi tập hợp như vậy trong câu lệnh chứa $V(n, t) = \sum_{i=0}^{l} C_n^i \times (q-1)^i$ vectơ $(C_n^i - \text{биномальный коэффициент}, \frac{n!}{(n-i)!i!})$.

8 (Giới hạn Hamming). Chứng minh rằng với mọi mã
$$k \leqslant \log_4 [q^n / V(n, t)]$$
$[x] = \text{целая часть } x$.

(3) Nếu các tham số của mã trong (3) bằng nhau thì mã được gọi là hoàn hảo.

Lý thuyết toán học về mã hóa, xuất hiện khoảng bốn mươi năm trước, là một ngành khoa học phát triển và rất sâu sắc. Nguồn gốc của nó là Claude Chenon, Richard Hamming, Marcel Golay và các nhà khoa học khác đã được đề cập. Bạn có thể đọc thêm về mã sửa lỗi trong sách của Arshinov M. N., Sadovsky L. E. “Mã và Toán học” (M., “Nauka”, 1983, Thư viện «Kvant», số 30), Yaglom A. M., Yaglom I. M. “Xác suất và Thông tin” (M., “Nauka”, 1973).

Dễ dàng nhận thấy rằng các hệ thống $l$ hoàn hảo trùng khớp với các mã hoàn hảo. Đặc biệt, hệ thống 3 chơi mini-Sportirognoz là mã có $q=3$, $k=2$ và $n=4$ sửa một lỗi. Từ những điều trên, suy ra rằng mã này là tuyến tính (theo nghĩa của Bài tập 2), hoàn hảo và chứa các vectơ $q^k=9$.

"Sportirognoz-13"
Hệ thống 3-được đề xuất ở trên cho bộ ba bốn trận đấu có thể được khái quát hóa cho trường hợp “thực” là 13 trận đấu; điều này dẫn đến một hệ thống 12 $C_1$ bao gồm các thẻ $3^{10}=59049$. Chúng ta sẽ giả sử rằng vectơ $x \in E_3^{13}$ thuộc hệ thống $C_1$ nếu tọa độ của nó thỏa mãn phương trình sau (lại hoạt động modulo 3):

$$x_{11} = x_3 + x_4 + x_5 + x_6 + x_7 + x_8 + x_9 + x_{10},$$

$$x_{12} = x_1 + x_2 + x_5 + x_6 + x_7 + 2x_8 + 2x_9 + 2x_{10},$$

$$x_{13} = x_1 + 2x_2 + x_3 + 2x_4 + x_6 + 2x_7 + x_9 + 2x_{10}.$$

Như trên, chúng ta sẽ gọi số vectơ là tập hợp chín tọa độ đầu tiên của nó.

Bài tập 9. Gọi số vectơ $x = (x_1, \dots, x_{10}) \in C_1$ bằng $(x_1, \dots, x_{10}) = (0,1,1,1,2,0,2,1,2,1)$. Tìm $x$.

Tuyên bố. Hệ thống 12 được xây dựng là tuyến tính và hoàn hảo.

Thật vậy, giả sử các vectơ $x$ và $y$ thỏa mãn (4), thì cả $x+y$ và $2x$ đều thỏa mãn hệ phương trình này. Việc chứng minh rằng khoảng cách giữa hai vectơ bất kỳ của hệ $C_1$ ít nhất là bằng ba. Khoảng cách 2 vectơ $x$, $y \in C_1$. Nếu số của chúng trùng nhau thì $x=y$. Nếu các số khác nhau ở ba vị trí trở lên thì mọi thứ đều được chứng minh. Giả sử các số khác nhau ở một vị trí, chẳng hạn như thứ $i$. Sau đó, chúng tôi thay thế bất kỳ $x_i$ ($1 \leqslant i \leqslant 10$) nào xuất hiện bằng các hệ số khác 0 trong các phần đúng của ít nhất hai phương trình của hệ (4), tức là ít nhất ba tọa độ cuối cùng của vectơ $x$ và $y$ sẽ khác nhau. Nếu số của vectơ $x$ và $y$ khác nhau ở hai vị trí, chẳng hạn như thứ $i$ và thứ $j$, thì để chứng minh, chỉ cần chứng minh rằng chúng khác nhau ở ít nhất một vị trí nữa là đủ. Điều này có thể không chỉ xảy ra trong trường hợp khi biến thứ $i$ và $j$ nhập đúng phần của tất cả các phương trình (4) có cùng hệ số. Việc kiểm tra cho thấy các biến như vậy không tồn tại. Vì vậy, người ta đã chứng minh rằng khoảng cách giữa bất kỳ vectơ $x$, $y \in C_1$ nào ít nhất là bằng ba. Khi đó tập hợp các vectơ từ $E_3^{13}$ nằm từ $x$ và $y$ ở khoảng cách $\leqslant 1$ không giao nhau. Theo bài tập 7, mỗi bộ như vậy chứa 27=3$^3$ vectơ. Tổng số vectơ trong hệ thống bằng số lượng các số khác nhau, tức là $3^{10}$ và tổng khối lượng của các bộ rời rạc tương ứng với chúng bằng $3^{10} \cdot 3^3 = 3^{13}$, trùng với số lượng tất cả các thẻ có thể có. Q.E.D.

Bài tập 10 (khó). Nhanh chóng đưa ra cách tìm ra quân bài thắng cho hệ $C_1$ dựa trên kết quả chia bài (so sánh với Bài tập 6). Phương pháp này cho phép bạn tìm thấy thẻ chiến thắng nhanh hơn nhiều so với tìm kiếm đầy đủ.

⟦folio 14⟧

---
running_head:
folio:
---

Hệ thống 12 được xây dựng là một mã có $q=3$, $n=13$, $k=10$, sửa một lỗi. Mã này là thành viên của họ mã Hamming hoàn hảo với $q=3$, $n=(3^m-1)/2$, $k=n-m$.

Hệ thống phi tuyến

Chúng ta hãy quay lại hệ thống $C_0$ một chút để có một “Dự báo thể thao” nhỏ. Hãy viết tất cả hai vectơ vào các hàng của bảng. Bằng cách xóa bất kỳ cột nào khỏi bảng này, chúng ta thu được hệ tuyến tính gồm các vectơ thứ chín cho Sportprognoz-3. Có thể chỉ ra rằng hệ thống này là tốt nhất trong số các hệ thống tuyến tính, nghĩa là nó chứa số lượng thẻ nhỏ nhất có thể. Hóa ra việc từ bỏ điều kiện tuyến tính cho phép người ta buộc tội hệ thống này. Hệ thống 2 phi tuyến tốt nhất cho 3 chỉ bao gồm năm vectơ. Đây là:
$(0,0,0), (0,1,1), (1,0,1), (1,1,0), (2,2,2)$.

Bảng hiển thị các bản ghi để xây dựng hệ thống $l$ cho $l=n-3$, $n-2$ và $n-1$ tại $n \leqslant 13$. Đối với trò chơi “Dự báo thể thao” chỉ có hai cột đầu tiên xuất hiện, nhưng một trường hợp tổng quát hơn cũng được các nhà toán học quan tâm. Lưu ý rằng bất kỳ bảng nào được công bố đều xứng đáng được công bố trên các tạp chí toán học quốc tế có uy tín. Tất nhiên, các hệ thống trong bảng này được xây dựng bởi tác giả của chúng

Bàn

| $n$ | $l=n-1$ | $l=n-2$ | $l=n-3$ |
| :--- | :--- | :--- | :--- |
| 1 | 1* | 1* | 1* |
| 2 | 3* | 1* | 1* |
| 3 | 5* | 3* | 1* |
| 4 | 9* | 3* | 3* |
| 5 | 27 | 8 | 3* |
| 6 | 73 | 17 | 6* |
| 7 | 186 | 34 | 12 |
| 8 | 486 | 81 | 27 |
| 9 | 1458 | 219 | 54 |
| 10 | 3645 | 558 | 108 |
| 11 | 10935 | 729* | 243 |
| 12 | 29889 | 2187 | 729 |
| 13 | 59049* | 6561 | 1215 |

* - người ta biết rằng không thể buộc tội được.

không phải bằng cách liệt kê đơn giản trên máy tính (nhân tiện, làm thế nào để thực hiện điều này? Đáp số chưa được biết trong trường hợp tổng quát), mà bằng cách sử dụng các cấu trúc chung dẫn đến một họ hệ thống có độ dài khác nhau. Vì vậy, nếu một trong những độc giả may mắn bắt được bàn thì các tác giả sẵn sàng hỗ trợ chuẩn bị bài viết. Tốt hơn là nên bắt đầu tìm kiếm với độ dài $n \geqslant 6$, tức là mức tăng ở độ dài nhỏ hơn là nhỏ.

Hệ thống 9 tuyệt vời cho 11

Khi quan sát kỹ chiếc bàn, một ngôi sao lấp lánh lẻ loi ở giữa đã thu hút sự chú ý. Đây là hệ 9 tuyệt vời $C_2$ cho 11. Lịch sử và ứng dụng của nó sẽ rất phức tạp đối với một cuốn tiểu thuyết toán học hấp dẫn. Nhưng trước tiên, hãy nói một vài lời về bản thân heroin. Đây là một hệ thống hoàn hảo tuyến tính. Không khó để chứng minh hoàn toàn nếu bạn biết rằng hai vectơ bất kỳ của hệ cách nhau ít nhất một gót chân. Sau đó, như trước đây, tập hợp các vectơ ($x_7=3^6$) từ $E_3^{11}$ nằm cách một khoảng $\leqslant 2$ tính từ một điểm nào đó trong hệ thống không giao nhau. Vì mỗi bộ này chứa vectơ $243=3^5$ nên tổng thể tích của các bộ này trùng với tổng số vectơ trong $E_3^{11}$.

Chúng ta hãy trình bày các phương trình nối số ba ($x_1, x_2, \dots, x_6$) của bất kỳ vectơ $x$ nào thuộc hệ $C_2$ với phần năm còn lại của tọa độ của nó:

$$x_7=x_1+x_3+2x_4+2x_5+x_6,$$
$$x_8=x_1+x_2+x_4+2x_5+2x_6,$$
$$x_9=x_1+2x_2+x_3+x_5+2x_6,$$
$$x_{10}=x_1+2x_2+2x_3+x_4+x_6,$$
$$x_{11}=x_1+x_2+2x_3+2x_4+x_5.$$

Hệ thống này giống như một mã hoàn hảo với các tham số $q=3$, $n=11$, $k=6$, sửa hai lỗi. Nó được gọi là mã Golay để vinh danh nhà toán học đã phát hiện và công bố nó vào năm 1949. Để xác định mã bằng hệ phương trình (5), Golay đã phải sử dụng lý thuyết về cái gọi là thặng dư bậc hai. Tuy nhiên, vào mùa hè

⟦folio 15⟧

---
running_head:
folio:
---

Năm 1989, họ phát hiện ra rằng mã này (hệ thống dành cho trò chơi “Sportprognoz”) đã được mở và xuất bản vào năm 1947 trên tờ báo thể thao “Veikaya” *). Tác giả của khám phá này, Juhani Virtakallo, không phải là một nhà toán học và cố tình không biết rằng phép trừ bình phương phải được sử dụng để xây dựng mật mã. Anh ấy viết: “Hệ thống 729 cột này xuất hiện trong tâm trí tôi trong những ngày thắng nhỏ ở Sportprognoz.” Rõ ràng, chúng ta đang xử lý một ví dụ về cái nhìn sâu sắc thực sự của Ramanujan (xem bài viết của S. G. Gindikin trong «Kvant» Số 10 năm 1987).

Ngoài hệ thống ba ngôi này, M. Golay trong tác phẩm năm 1949 của ông đã mô tả một hệ thống tuyến tính hoàn hảo khác - một hệ thống gồm 20 $C_3$ có độ dài 23 với các vectơ số 0 và số 1 - một mã có các tham số $q=2$, $n=23$, $k=12$, sửa 3 lỗi. Hệ thống này chứa $2^{12}=4096$ vectơ và có thể hữu ích cho “Sportprognoz” trong chuyến đi thứ 23 trong trò chơi không có kết quả hòa.

Bài tập 11. Sử dụng kết quả của điều khiển 7 và 8, hãy chứng minh rằng hệ thống $C_3$ là hoàn hảo (và do đó chứa số lượng quân bài nhiều nhất có thể trong số các hệ thống có tham số như vậy).

Khám phá của Virtakallo còn đáng ngạc nhiên hơn vì đối với $q=3$ không có hệ thống $l$ hoàn hảo tầm thường nào khác có $l \leqslant n-2$ cho bất kỳ giá trị nào của $n$. Tại $l=n-1$ cũng có các hệ thống có tham số được đưa ra ở cuối đoạn trước. Đối với $q=2$, danh sách các hệ thống hoàn hảo không tầm thường với $l \leqslant n-1$ đã bị cạn kiệt bởi 20 hệ thống $C_3$ và họ hệ thống $(n-1)$ với $n=2^m-1$ và $k=n-m$. Hai tuyên bố này tuân theo định lý toàn cầu về mã hoàn hảo, chỉ được chứng minh vào đầu những năm 70.

Phát sinh liên quan đến mã Golay $C_2$ và $C_3$ toán học bài toán,

*) Ở Phần Lan, khi điền thẻ “Sportprognoz” năm 1947, phải nộp kết quả 12 trận đấu (teler - 13). Một lá bài được coi là thắng nếu có ít nhất 10 kết quả đúng. Do đó, hệ thống $C_2$ có thể được sử dụng nếu người chơi biết chắc chắn kết quả của một trận đấu.

thường khá khó khăn. Hơn nữa bài toán nhanh chóng (không vũ phu) việc tìm ra lá bài chiến thắng của hệ thống $C_2$ dựa trên kết quả rút thăm đã biết là không hề dễ dàng. Những ai muốn thử sức mình với vấn đề khó (mặc dù đã được giải quyết) này nên sử dụng hệ thống điều khiển (5) và thực hiện theo hai bài tập 6 và 9. Có lẽ bạn sẽ có thể khám phá ra một số cách mới lời giải của bài toán này?

bài toán cuối cùng, mà chúng tôi muốn đề cập ở đây liên quan đến “Sportforecast”, sẽ phát sinh trong trường hợp người chơi giả định rằng trong $t$ trong số $n$ trận đấu, bất kỳ kết quả nào trong ba kết quả đều có thể xảy ra - hòa, thắng và chuyền cho một trong các đội và trong các trận đấu $b=n-t$, chiến thắng của đội đó gần như không thể. (Ví dụ: trong một trận đấu bóng đá giữa Barcelona (Madrid) và Zvezda (Perm), tốt nhất một trong các đội có thể tính là hòa.) Hãy để chúng tôi biểu thị bằng $E_{2,3}(b,t)$ tập hợp các vectơ có độ dài $b+t$, trong đó tọa độ $b$ đầu tiên nhận giá trị 0 hoặc 1 và $t$ cuối cùng nhận giá trị 0,1 hoặc 2. $l$-system $C$ đối với "Dự báo thể thao" hỗn hợp phải bao gồm các vectơ như vậy từ $E_{2,3}(b,t)$ mà đối với bất kỳ vectơ $a \in E_{2,3}(b,t)$ nào cũng có một vectơ $c \in C$ nằm từ $a$ ở khoảng cách Hamming không quá $l$.

Bài tập
12. Chứng minh rằng ở khoảng cách $\leqslant l$ tính từ một vectơ cố định $a \in E_{2,3}(b,t)$ có $E_{2,3}^n,w$ vectơ kép có độ dài $n$ chứa chính xác $w$ đơn vị. Chúng tôi không biết bất kỳ hệ thống tốt nào cho "Sportp"; người ta có thể nhận được một bất đẳng thức đơn giản chứng tỏ rằng bất kỳ hệ thống nào như vậy đều phải chứa khá nhiều quân bài. Tất nhiên, số lượng của họ
