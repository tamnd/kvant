---
id: 1991-10-tihomirov-teorema-ferma-eylera-o-dvuh-kvadratah-a400cd4d
issue: kvant_1991_10
year: 1991
number: "10"
title: Định lý Fermat–Euler về hai hình vuông
authors:
  - Тихомиров В. М.
rubric: osnovnye-stati
page_first: 11
page_last: 14
page_labels: 10, 12
lang: vi
source: kvant_digital
extraction: vision
content_sha256: c1a9f7c75fe2128436c3156f254d8ea91b39b2eda79aefcea19d6e6d2f9b9e12
prompt_sha256: draft-1
translated_from: content/ru/1991/10/articles/03_tihomirov-teorema-ferma-eylera-o-dvuh-kvadratah-a400cd4d.md
source_content_sha256: f2c42058d30b0dc8450494c18bf7542f7e4a752c482d237dbd8cea153e034f41
translation_model: draft
translation_run: vi-draft-gaps-2026-11-06
translation_quality: draft
---

⟦folio 10⟧

---
running_head:
folio:
---

Định lý Fermat-Euler
GIỚI THIỆU HAI VUÔNG

Tiến sĩ Khoa học Vật lý và Toán học
V. TIKHOMIROV

Hãy nhìn vào một vài số nguyên tố đầu tiên: 3, 5, 7, 11, 13, 17, 19...
Các số 5, 13 và 17 có thể được biểu diễn dưới dạng tổng của hai bình phương:
$$5 = 1^2 + 2^2, 13 = 2^2 + 3^2, 17 = 1^2 + 4^2,$$
và các số viết còn lại (3, 7, 11, 19) không thể biểu diễn theo cách này. Có thể đưa ra lời giải thích nào cho quan sát này không? Hóa ra là có thể, cụ thể là điều sau đây là đúng:

Định lý. Để một số nguyên tố có thể biểu diễn dưới dạng tổng của hai bình phương, điều cần thiết và đủ là khi chia cho các số chẵn nó có dư một.
(Thật vậy, $5 = 4 \cdot 1 + 1, 13 = 4 \cdot 3 + 1, 17 = 4 \cdot 4 + 1,$ trong khi $3 = 4 \cdot 0 + 3, 7 = 4 \cdot 1 + 3, 11 = 4 \cdot 2 + 3,$...)

Một chút lịch sử

Ai và khi nào lần đầu tiên phát hiện ra hiện tượng này? Có bằng chứng cho thấy kết quả này vào cuối năm ngoái có thể đã bổ sung thêm giá trị trispotides của nó. Vì vào ngày lễ Giáng sinh năm 1640 (trong một bức thư đề ngày 25 tháng 12 năm 1640), Pierre Fermat vĩ đại (1601-1665) đã thông báo với Mersen nổi tiếng, một người bạn trung thành của Descartes và là người trung gian chính trong thư từ của các nhà khoa học cùng thời với ông, rằng “Mọi số nguyên tố khi chia cho 4 sẽ bằng một, chỉ có thể được biểu diễn dưới dạng tổng của hai bình phương”.

Vào thời điểm đó, các tạp chí toán học vẫn chưa tồn tại; thông tin được trao đổi bằng thư từ và theo quy định, kết quả chỉ được công bố chứ không kèm theo bằng chứng.

Đúng vậy, gần 20 năm sau bức thư gửi Mersenne, trong bức thư gửi Carcavi gửi vào tháng 8 năm 1659, Fermat tiết lộ ý tưởng chứng minh định lý được nêu ở trên. Ông viết rằng ý tưởng chính của chứng minh là phương pháp giảm dần, cho phép chúng ta từ giả định rằng đối với một số nguyên tố có dạng $4n + 1$, kết luận của định lý là sai, để đạt được rằng nó cũng sai đối với số thay đổi, v.v., cho đến khi chúng ta đạt đến số năm, khi cuối cùng chúng ta đi đến một mâu thuẫn.

Những bằng chứng đầu tiên được Euler (1707–1783) tìm ra trong khoảng thời gian từ 1742 đến 1747. Hơn nữa, muốn khẳng định tính ưu tiên của Fermat, người mà ông có cảm giác kính trọng sâu sắc, Euler đã đưa ra một chứng minh tương ứng với nhận xét của Fermat được mô tả ở trên. Để tri ân cả hai nhà khoa học vĩ đại, chúng tôi gọi định lý này là định lý Fermat-Euler.

Có một đặc tính vốn có trong hầu hết mọi kết quả toán học đẹp đẽ (cũng như trong hầu hết mọi đỉnh núi đẹp và tầm thường): nó có thể được thêm vào theo nhiều cách khác nhau, nó có thể bị đùa giỡn theo nhiều cách khác nhau, và mọi con đường đều mang lại niềm vui cho những ai không ngại đi theo chúng.

Tôi muốn chứng minh tất cả điều này bằng ví dụ về định lý Fermat-Euler.

Để lên tới đỉnh, được phát hiện vào thế kỷ 17, chúng ta sẽ đi theo ba con đường khác nhau. Một trong số chúng được phát hiện vào thế kỷ 18, cái còn lại vào thế kỷ 19 và cái thứ ba đã có vào thế kỷ 20.

⟦folio none⟧

---
running_head:
folio:
---

nghĩa là, áp dụng hai lần nó sẽ đưa chúng ta trở lại. Hãy làm điều này một lần nữa cho (1).

Cho $x < y - z$ thì $x' = 2z + x$, $y' = z$, $z' = y - z$, từ đó $x' = x + 2z > y' - z' = 2z + x - y$ và do đó, $B(x'; y'; z')$ phải được tính theo quy tắc (3):

$$x'' = x' - 2y' = x + 2z - 2z = x,$$
$$y'' = x' - y' - z' =$$
$$= x + 2z - z + y - x - z = y,$$
$$z'' = y' = z.$$

Và trong những trường hợp khác, mọi thứ đều tương tự.

Bây giờ giả sử rằng $p$ là số nguyên tố có dạng $4n + 1$. Sau đó, trước tiên, phương trình $x^2 + 4yz = p$ có ​​thể giải được theo ít nhất hai cách: $x = 1$, $y = n$, $z = 1$ hoặc $x = y = 1$, $z = n$. Và thứ hai, phương trình này có số hữu hạn lời giải. Nếu chúng ta giả sử rằng trong số lời giải của anh ta không có cái nào mà $y = z$ (xét cho cùng, nếu có một thứ như vậy thì không có gì để chứng minh: $p = x^2 + (2y)^2$), thì chúng ta thu được rằng phép biến đổi $B$ chia tất cả lời giải thành cặp $((x; y; z); B(x; y; z))$, trừ khi $(x; y; z) \neq B(x; y; z)$. Chúng ta hãy xem liệu các cặp như vậy có tồn tại hay không, như người ta nói, liệu phép biến đổi $B$ có điểm cố định hay không.

Rất dễ hiểu khi nhìn vào các công thức (1)–(3) rằng các điểm cố định $y$ $B$ là những điểm mà $x = y$. Nhưng đối với $x = y > 1$ lời giải phương trình không có $x^2 + 4yz = p$ (vì $p$ không chia hết cho $y$). Điều này có nghĩa là chỉ có một điểm cố định $(1; 1; n)$. Từ tất cả những gì đã nói, có thể suy ra rằng số lời giải của phương trình $x^2 + 4yz = p$ là số lẻ: điểm cố định $(1; 1; n)$ và lời giải còn lại được chia thành từng cặp.

Tuy nhiên, có một phép biến đổi nữa, hãy gọi nó là $J$, nó hoán đổi $y$ và $z$: $J(x; y; z) = (x; z; y)$. Tất nhiên, nó cũng có liên quan. Hãy xem bộ ba nào (từ phương trình lời giải của chúng tôi $x^2 + 4yz = p$) nó giữ nguyên vị trí, tức là $(x; y; z)$ và $(x; y; z) = (x; z; y)$ đó là gì.

Chúng tôi đã quy định trước đó rằng $y \neq z$.

Nhưng sau đó không có điểm cố định! Điều này có nghĩa là tất cả lời giải được chia thành từng cặp. Tức là số lời giải là số chẵn! Nhưng chúng tôi vừa tuyên bố rằng số lời giải là số lẻ. Hóa ra đó là một sự mâu thuẫn. Điều này có nghĩa là phải tồn tại lời giải phương trình $x^2 + 4yz = p$, trong đó $y = z$, tức là $p$ là tổng của hai bình phương. Định lý đã được chứng minh.

Bằng chứng thứ ba

Chứng minh Minkowski được sửa đổi một chút mà bây giờ chúng ta sẽ thảo luận thậm chí còn giàu trí tưởng tượng hơn. Thật không may, nó hơi không cơ bản, cụ thể là nó đòi hỏi kiến ​​thức về hình elip là gì và công thức tính diện tích của hình elipis.

Tất cả bắt đầu với một kết quả của Minkowski, có vẻ như không có mối quan hệ đặc biệt nào với định lý Fermat-Euler.

Định lý. Đặt $a, b$ và $c$ là số nguyên và đặt $a > 0$ và $ac - b^2 = 1$ là số nguyên. Khi đó tồn tại một phương trình số nguyên lời giải $ax^2 + 2bxy + cy^2 = 1$.

Bằng chứng. Chúng ta hãy lấy tọa độ hình chữ nhật Descartes của hệ thống trên mặt phẳng và xác định trong đó tích vô hướng của công thức:

$((x; y); (x'; y')) = axx' + bxy' + bx'y + cyy'$.

Tích vô hướng này làm phát sinh “khoảng cách” từ gốc đến điểm $(x; y)$:

$$d((0; 0), (x; y)) = \sqrt{((x; y), (x; y))} = (ax^2 + 2bxy + cy^2)^{1/2}.$$

⟦folio 12⟧

---
running_head:
folio:
---

từ gốc tọa độ đến bất kỳ điểm nào của mạng số nguyên ngoài điểm (0; 0) $(m; n)$ $(m$ và $n$ là số nguyên). Đặt khoảng cách này bằng $\hat{d}$ và nó đạt được ở điểm mạng $(\hat{m}; \hat{n})$ sao cho
$$a\hat{m}^2 + 2b\hat{m} + c\hat{n}^2 = \hat{d}^2.$$ (4)

Tập hợp các điểm $(x; y)$ của mặt phẳng thỏa mãn bất đẳng thức
$$ax^2 + 2bxy + cy^2 \leq \hat{d}^2,$$
là một hình elip. Theo cách xây dựng của chúng tôi, nếu hình elip này chuẩn bị được nén hai lần, và sau đó mở rộng hình elip “đã nén” này (song song với chính nó) với tâm thành các điểm của một mạng số nguyên, thì tất cả các hình elip thu được, nếu chúng giao nhau, sẽ chỉ ở các điểm biên.

Không khó hiểu (xem hình) rằng diện tích chiếm bởi giao điểm của các hình elip với một tam giác có đỉnh $(0; 0), (1; 0)$ và $(1; 1)$ bằng một nửa diện tích của toàn bộ hình elip. Và nó - diện tích này - bằng
$$\frac{\pi \hat{d}^2}{4} \det \binom{a}{b} = \frac{\pi \hat{d}^2}{4} (ac - b^2) = \frac{\pi \hat{d}^2}{4}$$

Độc giả của chúng tôi Ya. Grozensky, khi nghiên cứu dãy số bình phương, đã thu được
$$x^2 = 2(x - 1)^2 - (x - 2)^2 + 2.$$
Sau đó, đối với hình khối, anh ấy đã tìm thấy rằng
$$x^3 = 3(x - 1)^3 - 3(x - 2)^3 + (x - 3)^3 + 6,$$
và cho sức mạnh gấp bốn lần -
$$x^4 = 4(x - 1)^4 - 6(x - 2)^4 + 4(x - 3)^4 - (x - 4)^4 + 24.$$
Trong lá thư của mình, ông hỏi liệu có sự phụ thuộc chung

$$x^n = n(x - 1)^n + A_1(x - 2)^n + \dots + A_k(x - k)^n + \dots + A_n(x - n)^n + n!$$

Một công thức như vậy thực sự tồn tại:
$$x^n - C_1^n(x - 1)^n + C_2^n(x - 2)^n - \dots + (-1)^k C_k^n(x - k)^n + \dots + (-1)^n(x - 1)^n = n!$$
trong đó $C_k^n$ là các hệ số sinh học
$$\left( C_k^n = \frac{n!}{k!(n - k)!} \right).$$
Hãy cố gắng chứng minh điều đó.
