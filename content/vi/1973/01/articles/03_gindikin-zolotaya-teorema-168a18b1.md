---
id: 1973-1-gindikin-zolotaya-teorema-168a18b1
issue: kvant_1973_1
year: 1973
number: "1"
title: Định lý vàng
authors:
  - Гиндикин С. Г.
rubric: osnovnye-stati
page_first: 4
page_last: 11
page_labels: 2, 4, 5, 6, 7, 9
tag: ULO8
lang: vi
source: kvant_digital
extraction: vision
content_sha256: 7e06f6c3bfcec64115ad6ef1adc7934dee36ec103b263258ec6ed45670f44b25
prompt_sha256: draft-1
translated_from: content/ru/1973/01/articles/03_gindikin-zolotaya-teorema-168a18b1.md
source_content_sha256: 6515880b0f7a449014f9747245d48d98ddee1c0e3dafa3e559527adb65523d64
translation_model: draft
translation_run: vi-draft-2026-10-31
translation_quality: draft
---

⟦folio 2⟧

Định lý vàng

S. G. Gindikin

"Các tính chất của các con số được biết đến ngày nay phần lớn đã được khám phá bằng quan sát và khám phá từ rất lâu trước khi sự thật của chúng được xác nhận bằng bằng chứng xác thực. Thậm chí có nhiều tính chất của các con số mà chúng ta rất quen thuộc nhưng vẫn chưa thể chứng minh được."

L. Euler

Chúng ta sẽ thực hiện một chuyến tham quan về nguồn gốc của lý thuyết số hiện đại - một nhánh của toán học nghiên cứu về số tự nhiên. Vào thời điểm đó, các nhà toán học nhận thấy những hình mẫu đơn giản và đẹp đẽ đến kinh ngạc trong thế giới số tự nhiên. Nhưng thường thì sự đơn giản trực quan của các công thức trở thành không thể tiếp cận được lời giải. Các cuộc tấn công trực diện không thành công; chúng tôi phải tìm ra cách giải quyết và tạo ra một thiết bị hoàn toàn mới.

Ở đây chúng ta đã thảo luận về một bài toán* như vậy), công thức của nó có thể hiểu được đối với một học sinh biết số nguyên tố là gì. Nhưng việc giải quyết bài toán này không hề dễ dàng, và Euler vĩ đại đã không thể thực hiện bước đầu tiên hướng tới nó lời giải ngay lập tức. Langgrange và Legendre đang cố gắng chứng minh giả thuyết do Euler đưa ra (nhưng ông chưa chứng minh được); Gauss mười chín tuổi đã làm được điều này. Đây là công việc thứ hai của anh ấy**).

Gauss gọi định lý này là “định lý vàng”. Nó nói về số dư có thể là bao nhiêu khi chia bình phương của một số nguyên cho số nguyên tố. Chúng tôi sẽ không trình bày công thức đầy đủ của mệnh đề đã được Gauss chứng minh mà trì hoãn đến trang 5. Bây giờ chúng tôi sẽ giới thiệu công thức bài toán, giới thiệu một số thuật ngữ và xem xét chi tiết trường hợp đặc biệt của “định lý vàng” do Euler chứng minh.

Các điều kiện khác nhau cần thiết để một số là số chính phương đã được biết rõ. Ví dụ: một số như vậy chỉ có thể là 0, 1, 4, 5, 6 hoặc 9. Một thuộc tính thường được sử dụng khác là bình phương của một số nguyên có thể chia hết cho 3 hoặc khi chia cho 3, dư 1 (bằng chứng). Tính chất thứ nhất có thể được xây dựng theo cách tương tự như tính chất thứ hai, lưu ý rằng chữ số cuối cùng là số dư khi chia cho 10.

Ở mọi nơi bên dưới, chúng tôi sẽ đề xuất rằng $p$ là số nguyên tố và $p \neq 2$. Bạn có thể chia các số nguyên “có phần thiếu” hoặc “có phần dư”. Nói cách khác, phần dư có thể được coi là dương hoặc âm. Điều kiện: chọn số dư có giá trị tuyệt đối nhỏ nhất.

Không khó để chứng minh rằng nếu $p$ là số lẻ thì mọi số nguyên $n$ đều có thể biểu diễn duy nhất dưới dạng

$$n = pq + r, \quad |r| \leq \frac{p-1}{2},$$

trong đó $q$ và $r$ là số nguyên.

⟦folio 4⟧

đã sửa $p$ tuyên bố của chúng tôi là không đúng sự thật).

Hơn nữa, điều rất cần thiết là 0 và 1 là màu sắc trong tất cả các công trình. Đối với các cột còn lại, mẫu mà các số màu đỏ xuất hiện trong chúng không được nhìn thấy ngay lập tức. Hãy bắt đầu với $a = -1$. Nó có màu đỏ ở $p = 5, 13, 17, \dots$ và đen ở $p = 3, 7, 11, \dots$. Bạn có thể nhận thấy rằng các số nguyên tố của nhóm thứ nhất khi chia cho 4 thì dư 1 và nhóm thứ hai - dư 1 (lưu ý rằng các số nguyên tố $p \neq 2$ không thể có bất kỳ số dư nào khác). Vì vậy, chúng ta có thể đề xuất rằng - 1 là số dư bình phương cho các số nguyên tố có dạng $p = 4l + 1$ và một số dư bình phương cho $p = 4l - 1$. Fermat (1601-1665) là người đầu tiên chú ý đến mô hình này nhưng lại không có bằng chứng. Hãy cố gắng tự mình tìm ra bằng chứng! Bạn sẽ thấy rằng khó khăn chính là không rõ cách sử dụng $p$ đơn giản và nếu không có câu này thì câu phát biểu sẽ trở thành sai.

Chứng minh đầu tiên, sau nhiều lần thử không thành công, đã được Euler (1707-1783) tìm ra vào năm 1847. Năm 1855, Euler tìm ra một bằng chứng rất hay khác sử dụng định lý nhỏ của Fermat: Nếu $p$ là số nguyên tố thì với mọi số nguyên $a$, $0 < |a| < p$: $a^{p-1} \equiv 1 \pmod p$. (2)

Có nhiều cách chứng minh khác nhau cho định lý này. Tuy nhiên, một số trong số chúng được đưa ra trong ITF. Ở đây chúng tôi trình bày một bằng chứng khác, có khái niệm tương tự như những cân nhắc khác trong bài viết này.

Bằng chứng. Với $p = 2$ mệnh đề là hiển nhiên và chúng ta có thể coi $p$ lẻ. Hãy xem xét $p$ số $0, \pm a, \pm 2a, \pm 3a, \dots, \pm ka; k = \frac{p-1}{2}$. Tất cả những số này khi chia cho $p$ đều cho các số dư khác nhau, vì nếu không thì $r_1 a - r_2 a, r_1 > r_2, |r| \leq k, |r_2| \leq k$ chia hết cho $p$, nhưng $a$ không chia hết cho $p$ và $r_1 - r_2$ không chia hết cho $p$, vì $0 < r_1 - r_2 < p$. Các biến là các số được đề cập khác 0; chúng tôi nhận được $(-1)^k (k!)^2 a^{p-1}$. Vì phần còn lại của hệ số chứa tất cả các phần dư bằng 0 và tính đến cách tính chính xác phần còn lại của sản phẩm, chúng tôi thấy rằng sản phẩm có cùng phần dư là $(-1)^k (k!)^2$, tức là $(k!)^2 (a^{p-1} - 1)$ được chia cho $p$. Vì $k!$ không chia hết cho $p$ ($0 < k < p$), nên $p$ chia hết cho $a^{p-1} - 1$, và chứng minh hoàn tất.

Hệ quả (tiêu chuẩn Euler về độ bình phương của một dư lượng). Vycem $b \neq 0$ là moeda vuông và moeda sữa, koeda

$$b^k \equiv 1 \pmod p, \quad k = \frac{p-1}{2}. \quad (3)$$

Chứng minh điều kiện (3) rất dễ chứng minh. Nếu $a^2 \equiv b \pmod p$, $0 < a < p$, thì $a^{2k} = a^{p-1}$ và $b^k$ phải có cùng các thặng dư, bằng nhau, nhờ vào (2), 1. Chỉ cần có vẻ phức tạp hơn là đủ. Chúng ta sẽ rút ra nó từ bổ đề sau, được chứng minh trong ITF.

Bổ đề 1. Nếu $P(x)$ là đa thức của chiến lược $l$, $p$ là số nguyên tố và có nhiều hơn $l$ các dư lượng khác nhau $r$ modulo $p$ mà

$$P(r) \equiv 0 \pmod p, \quad (4)$$

mo (4) giữ cho tất cả các dư lượng.

Chúng ta hãy áp dụng bổ đề cho đa thức $P(x) = x^k - 1$. Khi đó sự tương ứng (4) thỏa mãn $k$ số dư bình phương khác 0. Tuy nhiên, nó có dư lượng $(r = 0)$, không thỏa mãn (4); Điều này có nghĩa là, theo bổ đề, tất cả các số dư bình phương không được thỏa mãn (4) và do đó, điều kiện (3) là đủ.

Quét. Đối với hình vuông không có dư $b$ ta có: $b^{\frac{p-1}{2}} \equiv -1 \pmod p$. Thật vậy, nếu $b^{\frac{p-1}{2}} \equiv r \pmod p$, thì $r^2 \equiv 1 \pmod p$, do đó $r = -1$. (So ​​sánh $r^2 \equiv 1 \pmod p$ chỉ thỏa mãn thặng dư: $r \equiv 1 \pmod p$, $r \equiv -1 \pmod p$).

Tiêu chí Euler cho phép chúng ta giải ngay lập tức câu hỏi trong đó $p$ phần dư - 1 là bình phương. Thay $b = -1$ vào (3), ta thấy rằng với $p = 4l + 1$ (3) $(k - \text{четно})$ thỏa mãn và với $p = 4l - 1$ (3)

⟦folio 5⟧

chưa hoàn thành ($k$ - lẻ). Giả thuyết được xây dựng ở trên đã trở thành một định lý.

Bài toán 1. Chứng minh rằng nếu $p \neq 2$ là ước số nguyên tố của số $n^2 + 1$ thì $p = 4l + 1$.

Vì vậy, chúng ta đã chứng minh rằng $-1$ là số dư bình phương của $p = 4l + 1$ và là số dư bình phương của $p = 4l - 1$.

Hãy để chúng tôi thảo luận về một số tính năng của bằng chứng được trình bày. Câu này có hai phần: câu phủ định cho $p = 4l - 1$ và câu khẳng định cho $p = 4l + 1$. Trong trường hợp đầu tiên, người ta cố gắng tìm một tính chất neokotores thỏa mãn số dư bình phương, nhưng $-1$ thì không, đó là điều Euler đã làm. Tính chất tìm được hóa ra có tính chất đặc trưng, ​​tức là đồng thời có thể chứng minh được phần thứ hai của giả thuyết. Nếu bạn không thể tự mình chứng minh phần này của tuyên bố, thì bạn tin rằng bạn đang cố gắng xây dựng một cách rõ ràng từ $p = 4l + 1$ số $n^2$, số này cho phần dư $-1$ khi chia cho $p$. Chứng minh của Euler không hiệu quả theo nghĩa là nó không cung cấp một cách xây dựng rõ ràng cho số $n$ nhân với $p$, mà chỉ khẳng định sự tồn tại của nó. Nói cách khác, đảm bảo rằng nếu chúng ta xét các số $1,2,...,2l$, bình phương chúng, lấy số dư khi chia các bình phương cho $p$ thì sớm muộn gì chúng ta cũng sẽ nhận được $-1$. Câu hỏi đặt ra là liệu có thể chỉ ra một cấu trúc rõ ràng hơn từ $n$ đến $p$ mà không sử dụng các thủ tục liệt kê hay không. Số dương đáp số được Langgange (1736–1813) đưa ra vào năm 1773, sử dụng định lý sau.

Định lý Wilson*). Nếu $p = 2k + 1$ là số nguyên tố thì $(-1)^k (k!)^2 \equiv -1 (\bmod p)$.

Để chứng minh định lý này, chúng ta sẽ sử dụng Bổ đề 1. Đặt $P(x) = (x^2 - 1)(x^2 - 4) \ldots (x^2 - k^2), Q(x) = x^{2k} - 1$. Khi đó $R(x) = P(x) - Q(x)$ tối đa là đa thức bậc $2k - 1$, mà tại $x = \pm 1, \pm 2, \ldots, \pm k$ chia hết cho $p$ ($P$ và $Q$ có tính chất này). Theo bổ đề $R(x) \equiv 0 (\bmod p)$ cho tất cả $x$. Trên thực tế, yếu tố mới duy nhất là $R(0) \equiv 0 (\bmod p)$. Vì $R(0) = (-1)^k (k!)^2 + 1$ nên ta thu được (5).

Hệ quả Lagrange. Với $p = 4l + 1$ chúng ta có: $[(2l)!]^2 \equiv -1 (\bmod p)$.

Bài toán 2. Chứng minh rằng nếu (5) đúng thì $p$ là số nguyên tố.

bài toán này đưa ra lý do để lưu ý rằng trong cách xây dựng của Lagrange, sự đơn giản của $p$ tồn tại.

*) Wilson (1741-1793) - luật sư nghiên cứu toán học tại Cambridge.

Để tìm ra khi nào $a = -1$ là một thặng dư bình phương, Euler, sử dụng vật liệu số khổng lồ (bảng của anh ấy lớn hơn nhiều so với bảng thứ hai ở trên), cố gắng tìm các điều kiện tương tự cho $a$ còn lại. Anh ấy lưu ý rằng với $a = 2$ mọi thứ phụ thuộc vào số dư khi chia $p$ cho 8; 2 hóa ra là số dư bình phương đối với số nguyên tố $p = 8l \pm 1$ và không số dư đối với $p = 8l \pm 3$ (số nguyên tố khi chia cho 8 có thể cho số dư $\pm 1, \pm 3$). Hơn nữa, 3 là số dư bình phương tại $p = 12l \pm 1$ và số không bình phương tại $p = 12l \pm 5$. Euler phỏng đoán rằng trong trường hợp tổng quát, mọi thứ được xác định bởi phần dư của phép chia $p$ cho 4a.

Giả thuyết Euler*). Số a đồng thời là số dư bình phương hoặc không số dư bình phương đối với tất cả các số nguyên tố có trong phép tính số học $4aq + r$, $q = 0, 1, 2, \ldots, 0 < r < 4a$.

Rõ ràng là nếu $4a$ và $r$ có ước chung $s > 1$ thì sẽ không có một số nguyên tố nào trong cấp số cộng. Nếu số hạng đầu tiên và hiệu của phép phân tích là cùng nguyên tố, thì như định lý Dirichlet (1805-1859) phát biểu, trong phép phân tích này có vô số số nguyên tố (một dạng tổng quát hóa của định lý về vô số số nguyên tố trong chuỗi tự nhiên).

Hãy quay lại giả thuyết Euler. Hóa ra là tiêu chuẩn Euler, vốn phục vụ tốt cho chúng ta ở $a = -1$, đã thất bại ở $a = 2$. Euler đã thất bại trong việc giải quyết trường hợp này. Anh ấy đã chứng minh được giả thuyết của mình, không tính $a = -1$, chỉ tính $a = 3$. Khi đó Lagrange, người mà chúng ta đã đề cập, đã chứng minh giả thuyết tại $a = 2, 5, 7$; Legendre (1752-1833) vào năm 1785 đã đề xuất một bằng chứng về giả thuyết dành cho viên tướng, tuy nhiên, nó có những vấn đề quan trọng.

*) Gauss, người đã chứng minh phỏng đoán này, gọi nó là “định lý vàng”.

⟦folio 6⟧

Ứng dụng

Bây giờ chúng ta chuyển sang phần thứ hai của câu chuyện, từ đó những độc giả thuần túy nhất đã học được cách chứng minh giả thuyết Euler.

Vào ngày 30 tháng 3 năm 1796, Gauss 19 tuổi đã chứng minh được khả năng dựng một tam giác đều mười bảy cạnh bằng compa và thước. Từ hôm nay, nhật ký của Gauss sẽ bắt đầu - biên niên sử về những khám phá đáng kinh ngạc của ông. Mục thứ hai trong nhật ký xuất hiện vào ngày 8 tháng 4. Nó báo cáo rằng một bằng chứng chặt chẽ cho định lý “vàng” đã được tìm thấy – đó là cái mà Gauss gọi là giả thuyết Euler. Ông đã khám phá lại nó khi vẫn còn học tại Brunswick hypnasium, khi các tác phẩm của Euler, Lagrange, Legendre, những người mà ông chỉ làm quen sau khi chuyển đến Göttingen vào năm 1795, không được cung cấp cho ông. Đầu tiên, giống như những người tiền nhiệm, anh ấy chú ý đến mệnh đề cho $a=-1$, sau đó, sau khi đã làm phẳng kết quả cho trường hợp tổng quát, anh ấy tuần tự chia nhỏ từng trường hợp, tiến xa hơn những trường hợp khác: anh ấy xem xét $a=\pm 2$, $\pm 3$, $\pm 5$, $\pm 7$. Cuối cùng, vào ngày 8 tháng 4 năm 1796, ông tìm thấy một bằng chứng tổng quát mà Kronecker (1823-1891) gọi rất khéo léo là “sự phá vỡ các lực của thiên tài Gaussian”. Việc chứng minh được thực hiện bằng dấu hiệu kép trên $a$ và $p$; Gauss đưa ra những thông điệp khác nhau đáng kể để xem xét tám (!) trường hợp khác nhau. Không chỉ cần có sự khéo léo đáng kể mà còn phải có lòng dũng cảm đáng kinh ngạc để không tiếp tục đi trên con đường này. Sau đó, Gauss đã tìm ra thêm sáu cách chứng minh định lý “vàng” (hiện nay đã biết được khoảng 50 trong số đó). Như thường lệ, sau khi định lý được chứng minh, có thể tìm ra cách chứng minh đơn giản hơn nhiều so với chứng minh ban đầu. Ở đây chúng ta sẽ đưa ra một chứng minh khác một chút so với chứng minh thứ ba của Gauss. Nó dựa trên một bổ đề quan trọng được Gauss chứng minh không sớm hơn năm 1808.

Bổ đề 2. Cho $p=2k+1$ là số nguyên tố, $a$ là số nguyên, $0<|a| \leq 2k$; $r_1, r_2, \dots, r_k$-số được tính $a, 2a, \dots, ka$; $v$ là số âm

$a^k \equiv (-1)^v (\text{mod } p)$. (6)

Áp dụng tiêu chuẩn Euler, ta thu được hệ quả sau:

Tiêu chí Gaussian cho thặng dư bậc hai. Vyts là chế độ bình phương và chế độ molko khi số $v$ trong Bổ đề 2 có giá trị.

Chứng minh Bổ đề 2. Lưu ý rằng mọi thặng dư $r_1, \dots, r_k$ đều khác nhau về giá trị tuyệt đối. Điều này xuất phát từ thực tế là tổng và hiệu của hai số bất kỳ không chia hết cho $p: r_i \pm r_j = (i \pm j) a$, $i \neq j$; $|i \pm j| < p$, $|a| < p$. Như vậy, bộ mẫu $|r_1|, \dots, |r_k|$ là các số 1, 2, . . . , $k$ theo thứ tự nào đó. Kết quả là tích $a \cdot 2a \dots ka = a^k k!$ khi chia cho $p$ cho kết quả bằng $r_1 \dots r_k = (-1)^v k!$. Xét rằng $k!$ không chia hết cho số nguyên tố $p$, ta thu được (6).

Chứng minh giả thuyết Euler. Lưu ý rằng lập luận bên dưới không còn sử dụng tính đơn giản của $p$ nữa—nó được sử dụng hoàn toàn trong bổ đề Gauss. Chúng ta hãy đánh dấu các điểm trên trục số (Hình 1, $a, \delta$) $m \frac{p}{2}$, nếu $a > 0$ và $-m \frac{p}{2}$, nếu $a < 0$; $m = 0$, $1, 2, \dots, |a|$ - chấm màu xanh lam ($m$ - số của chúng). Chúng ta hãy đánh số các khoảng có các đầu tại các điểm này theo số của các đầu bên trái (trong hình, số các khoảng có màu đỏ). Bây giờ chúng ta lưu ý $a, 2a, \dots, ka$ - chấm màu xanh lá cây; vì $a$ là số nguyên không cộng với $p$ nên các chấm màu xanh lam không thể trùng nhau.

⟦folio 7⟧

Cơm. 2.

với các vùng xanh và tất cả các vùng xanh của điểm sẽ rơi vào một số khoảng được xây dựng $\left(|a| \frac{p}{2} \geq |a| k\right)$. Dễ dàng nhận thấy số $v$ xuất hiện trong bổ đề chính là số điểm xanh nằm trong các khoảng có số lẻ (chứng minh!).

Bây giờ chúng ta hãy đưa hình ảnh của mình vào một phép biến đổi tương tự với hệ số $\frac{1}{a}$ (Hình 1 sẽ chuyển thành Hình 2).

Trong trường hợp này, các chấm màu xanh lam sẽ đi vào các điểm chia đoạn $\left[0, \frac{p}{2}\right]$ thành $|a|$ các phần bằng nhau và các chấm màu xanh lá cây sẽ đi vào các điểm nguyên 1, 2, ..., $k$.

Việc đánh số các khoảng bây giờ sẽ phụ thuộc vào dấu của $a$: đối với $a > 0$ chúng được đánh số bằng số của các đầu bên trái, đối với $a < 0$ - bằng số của các đầu bên phải; $v$ là số điểm nguyên trong các khoảng có số lẻ. Nếu chúng ta tăng $p$ lên 4l thì chính xác 2l điểm nguyên sẽ được cộng vào mỗi khoảng. Điều này xuất phát từ thực tế là khi một khoảng được dịch chuyển bởi một số nguyên, số điểm nguyên trong đó không thay đổi và trên bất kỳ đoạn nào có độ dài nguyên $n$ hoặc khoảng có độ dài $n$ với các điểm cuối lẻ thì có chính xác $n$ điểm nguyên (bằng chứng!). Vì vậy, khi thay đổi $p$ thành $p + 4ал$ giá trị $v$ sẽ chuyển thành số chẵn nhưng $(-1)^v$ sẽ không thay đổi. Điều này có nghĩa là với mọi $p$ trong cấp số cộng $p = 4aq + r$ thì giá trị $(-1)^v$ là như nhau và phỏng đoán Euler đã được chứng minh.

Đồng thời, đưa ra một số cách để tìm hiểu xem $a$ có phải là thặng dư bình phương của $p$ hay không. Bạn cần lấy phần còn lại $r$ từ phép chia $p$ cho 4a (dương để thuận tiện); chia $\left(0, \frac{r}{2}\right)$ thành $|a|$ phần, được đánh số theo số đầu bên trái (phải), nếu $a$ là dương (âm); đếm số $v$ số điểm nguyên rơi vào các khoảng có số lẻ; $a$ là số dư bình phương khi và chỉ khi $v$ là số chẵn.

Hãy thực hiện những phép tính này cho $a = 2$ để xác nhận những quan sát của Euler được thảo luận ở trang 5. Đặt $a = 2$; thì chỉ cần xét $r = 1, 3, 5, 7$ là đủ, vì trong các trường hợp khác, cấp số cộng sẽ không chứa số nguyên tố. Như có thể thấy trong Hình 3, số 2 là số dư bình phương của

$$p = 8q + 1, \quad p = 8q + 7,$$

nghĩa là, $p = 8q \pm 1$.

Ở bên phải. Chứng tỏ rằng - 2 là số dư bình phương của $p = 8q + 1, \quad p = 8q + 3$.

Trường hợp $a = \pm 3$ cũng được xử lý tương tự. Dưới đây là kết quả tính toán (bảng cho $v$):

Cơm. 3. $r = 1, a = 2, v = 0; r = 3, a = 2, v = 1; r = 5, a = 2, v = 1; r = 7, a = 2, v = 2$.

⟦folio 9⟧

Có sự khác biệt giữa các câu hỏi về khi nào $p$ là modulo số dư bình phương $q$ và khi nào $q$ là modulo số dư bình phương $p$.

Bằng chứng. Luôn luôn là $p-q=4a$ hoặc $p+q=4a$.

Tôi nghĩ thế. Giả sử $p-q=4a$, tức là $p$ và $q$ có ​​cùng số dư khi chia cho 4. Sau đó, $\left(\frac{p}{q}\right) = \left(\frac{q+4a}{q}\right) = \left(\frac{4a}{q}\right) = \left(\frac{a}{q}\right)$ (chúng ta sẽ sử dụng (9), (8) và thực tế là $\left(\frac{4}{q}\right) = 1$ cho tất cả $q$). Tiếp theo, $\left(\frac{q}{p}\right) = \frac{p-4a}{p} = \left(\frac{-4a}{p}\right) = \left(\frac{-1}{p}\right)\left(\frac{a}{p}\right)$. Dựa trên giả thuyết Euler đã được chứng minh, $\left(\frac{a}{p}\right) = \left(\frac{a}{q}\right)$, tức là $\left(\frac{p}{q}\right) = \left(\frac{q}{p}\right)$ cho $\left(\frac{-1}{p}\right) = 1$ và $\frac{p}{q} = -\left(\frac{q}{p}\right)$ cho $\left(\frac{-1}{p}\right) = -1$. Cần nhớ rằng $\left(\frac{-1}{p}\right) = 1$ với $p=4l+1$, $\left(\frac{-1}{p}\right) = -1$ với $p=4l+3$.

trường hợp II. Giả sử $p+q=4a$, tức là $p$ và $q$ có ​​số dư khác nhau khi chia cho 4. Ta có $\left(\frac{p}{q}\right) = \left(\frac{4a-q}{q}\right) = \left(\frac{a}{q}\right)$. Tương tự như $\left(\frac{q}{p}\right) = \left(\frac{a}{p}\right)$. Nhờ sự bổ sung cho giả thuyết Euler, $\left(\frac{a}{q}\right) = \left(\frac{a}{p}\right)$, tức là $\left(\frac{p}{q}\right) = \left(\frac{q}{p}\right)$. Bằng chứng đã kết thúc.

Dễ dàng nhận thấy rằng lý luận trên có thể đảo ngược và giả thuyết Euler cùng phần bù của nó có thể được suy ra từ định luật bình phương tương hỗ (hãy làm điều này!). Chúng ta cũng hãy lưu ý rằng các công thức (8)–(10) cung cấp một phương pháp tính $\left(\frac{p}{q}\right)$ cần thiết đơn giản hơn phương pháp tổ hợp được mô tả ở trên. Hãy minh họa điều này bằng một ví dụ: $\left(\frac{59}{269}\right) = \left(\frac{269}{59}\right) = -1$,

bởi vì
$\left(\frac{3}{59}\right) = -\left(\frac{59}{3}\right) = -\left(\frac{2}{3}\right) = 1$;
$\left(\frac{11}{59}\right) = -\left(\frac{59}{11}\right) = -\left(\frac{4}{11}\right) = -1$.

Dễ dàng chứng minh rằng việc đánh giá ký hiệu Legendre luôn có thể được rút gọn về trường hợp $p$ hoặc $q$ bằng 2.

Bài tập. Đếm $\left(\frac{37}{557}\right)$, $\left(\frac{43}{991}\right)$.

Để kết luận, chúng tôi lưu ý rằng bài toán trên thặng dư bậc hai đóng vai trò là điểm khởi đầu của một hoạt động toán học lớn và hiệu quả. Nhiều nỗ lực của Gauss nhằm đạt được những chứng minh mới về luật tương hỗ bậc hai chủ yếu không phải do mong muốn đơn giản hóa các chứng minh. Gauss bị ám ảnh bởi ý nghĩ rằng ông chưa thực sự khám phá ra những quy luật sâu xa tạo nên quy luật tương hỗ. Điều này chỉ đạt được đầy đủ sau đó, trong khuôn khổ lý thuyết số đại số. Gauss đã dành rất nhiều công sức để khái quát hóa định luật bậc hai cho các trường hợp bậc ba và hai bậc hai, thu được những kết quả đáng chú ý. Những nghiên cứu này vẫn được tiếp tục và việc nghiên cứu các quy luật tương hỗ khác nhau vẫn là một trong những câu hỏi trọng tâm của lý thuyết số cho đến ngày nay.
