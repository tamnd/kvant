---
id: 1977-7-kirillov-o-pravilnyih-mnogougolnikah-funktsii-eylera-i-chislah-ferma-65921bf0
issue: kvant_1977_7
year: 1977
number: "7"
title: Về đa giác đều, hàm Euler và số Fermat
authors:
  - Кириллов А. А.
rubric: osnovnye-stati
page_first: 4
page_last: 10
page_labels: 2, 6, 7, 8
tag: JUAU
lang: vi
source: kvant_digital
extraction: vision
content_sha256: 6e31143a154e22c3101cada7bdd88ba0ad7634ef53bd36aa16352b879003c9d8
prompt_sha256: draft-1
translated_from: content/ru/1977/07/articles/02_kirillov-o-pravilnyih-mnogougolnikah-funktsii-eylera-i-chislah-ferma-65921bf0.md
source_content_sha256: 6eb99ab39ff00f55b870785bac53290f5c30fb73691b476d8e4ae5249959fe44
translation_model: draft
translation_run: vi-draft-2026-10-31
translation_quality: draft
---

⟦folio 2⟧

1. Lời mở đầu

Bài toán về các công trình hình học là một trong những công trình phổ biến nhất trong toán học ở trường. Hầu hết mọi câu lạc bộ toán đều có những bài toán này. Tất nhiên, đây không phải là sự trùng hợp ngẫu nhiên. Lịch sử của các công trình xây dựng hình học đã có từ vài nghìn năm trước và người Hy Lạp cổ đại đã đạt được nghệ thuật tuyệt vời ở đây. Một ví dụ là bài toán Apollonius: dựng một đường tròn tiếp xúc với ba đường tròn cho trước *).

Nhiều người có lẽ biết ba cổ vật bài toán quan trọng hóa ra vẫn chưa được giải đáp: về bình phương của hình cruea, phần ba của el và uvoenii của hình lập phương **).

Nhưng có lẽ đẹp nhất là bài toán về việc xây dựng các đa giác đều. Thực tế, đây không phải là một bài toán mà là cả một chuỗi bài toán: với mỗi số tự nhiên n ≥ 3, bạn cần dùng compa và thước để dựng số n đúng.

Có khuôn mẫu nào trong việc phân bổ số “đỏ” và “đen” không? Hóa ra là có; nhưng nó khá khó tìm. Mẫu này có tính chất số học; để mô tả nó, chúng ta sẽ phải tạm thời rời khỏi hình học

*) Xem bài “Đảo ngược và bài toán Apollonia” («Kvant», 1971, số 8).

**) Về hai bài toán cuối, xem bài “La bàn và thước kẻ” («Kvant», 1975, số 6).

*) Phương pháp dựng tam giác đều mười bảy cạnh bằng compa và thước kẻ được K. F. Gauss phát hiện lần đầu tiên vào năm 1801. Phương pháp này được mô tả trong bài “Sự ra mắt của Gauss” («Kvant», 1971, số 1).

⟦folio 6⟧

xe trượt tuyết và ba đường tròn bên ngoài), và tất cả đáp số này đều bằng nhau, nếu chúng ta lập công thức bài toán như sau: dựng một đường tròn tiếp tuyến với ba đường thẳng đã cho. Sự khác biệt giữa một vòng tròn nội tiếp và một vòng tròn bên ngoài dựa trên khái niệm “giữa” (hoặc “bên trong”) và nằm ngoài tầm hiểu biết của máy móc chúng ta.

Các ví dụ được phân tích cũng cho thấy rằng nếu bài toán có một số lời giải để xây dựng thì chương trình xây dựng sẽ cung cấp tất cả lời giải này. Nhận định này cũng đúng trong trường hợp tổng quát.

Một ví dụ đáng trân trọng: việc xây dựng hình học của một trong các nghiệm của phương trình bậc hai sẽ tự động dẫn đến việc xây dựng nghiệm thứ hai.

Vì vậy, chúng ta đến với prin và pu tiếp theo.

Bất kỳ bài toán nào để xây dựng, mổ xẻ bằng compa và thước kẻ, đều có 2' lời giải.

Một bằng chứng chặt chẽ cho phát biểu này được đưa ra bởi lý thuyết Galois và không thể trình bày trong bài viết này. Tuy nhiên, bản thân phát biểu này trông rất đơn giản và có thể đã được các nhà toán học cổ đại khám phá đầy đủ. Câu hỏi đặt ra: tại sao khám phá này chỉ được thực hiện vào thế kỷ trước, mặc dù nhiều ví dụ xác nhận đã được biết đến từ vài thiên niên kỷ trước? (Ví dụ: bài toán Apollonia được đề cập ở trên có 8 lời giải.)

Một trong những nguyên nhân có thể là do thiếu công trình xây dựng “máy móc” hiện đại bài toán. Một lý do khác là xem xét từng bài toán riêng biệt cùng với mục tiêu là bài toán tương tự (như bài toán để xây dựng một n-giác đều cho mỗi n).

Có lẽ chủ đề này sẽ thu hút sự chú ý của các nhà sử học toán học và họ sẽ giải thích hữu ích hơn cho chúng ta lý do dẫn đến “cơ hội bị mất” này.

4. Đa giác đều

Hãy quay lại bài toán chính của chúng ta. Chúng ta muốn biết khi nào có thể dựng được một n-giác đều bằng compa và thước thẳng. Lý do của đoạn trước gợi ý ý tưởng xem lời giải cái này có bao nhiêu bài toán. Để có kết quả đáp số, bạn cần tinh chỉnh dòng bài toán. Cụ thể là bạn cần

**Cơm. 5.**

cố định kích thước và vị trí của một n-giác thông thường (nếu không, tất nhiên, số lời giải sẽ là vô hạn, miễn là có ít nhất một lời giải). Vì vậy, chúng ta sẽ giả sử rằng n-giác của chúng ta nội tiếp trong một đường tròn o cho trước với tâm O và vị trí cố định A₀ của một trong các đỉnh của nó. Cần xác định các vị trí A₁, A₂, ..., Aₙ−1 của các đỉnh còn lại. Tất nhiên, chỉ cần tìm vị trí của điểm A₁ - vẽ các cung liên tiếp A₀A₁, ta được các điểm A₂, A₃, A₄, v.v.

bài toán này được giải dễ dàng nhất với n = 6. Người ta biết rằng cạnh của một hình lục giác nội tiếp đều bằng bán kính của hình tròn đã cho. Do đó, “chương trình” cần phải trông như thế này (Hình 5):

1. Dùng compa dựng một đường tròn có bán kính ω₁ |OA₀| từ điểm A₀.
2. Hãy đánh dấu điểm A₁ là giao điểm của đường tròn ω và ω₁.

Chúng ta thấy rằng chương trình này tạo ra hai câu trả lời khác nhau, nhưng các hình lục giác tương ứng A₀A₁′A₂′A₃′A₄′A₅′ và A₀A₁′A₂′A₃′A₄′A₅′ chỉ khác nhau ở thứ tự đánh số đỉnh.

Tình huống tương tự cũng xảy ra trong trường hợp n = 3 và n = 4. Thú vị hơn là các trường hợp n = 5 và n = 10. Phương pháp dựng hình ngũ giác đều được mô tả trong bài viết của A. Savin “Cách vẽ một ngôi sao năm cánh” («Kvant», 1976, số 1). Ở đây chúng ta sẽ xét trường hợp n = 10.

⟦folio 7⟧

Cơm. 6.

Nếu vẽ đường phân giác $A_1B$ của góc $OA_1A_0$ thì các tam giác thu được $OA_1B$, $BA_1A_0$ sẽ đều nhau (Hình 6) và các tam giác $OA_1A_0$ và $BA_1A_0$ sẽ tương tự nhau.

Chúng ta sẽ coi đường thẳng $OA_0$ là trục số trong đó điểm $O$ tương ứng với 0 và điểm $A_0$ tương ứng với một. Đặt điểm $B$ tương ứng với số $x$. Khi đó ta thu được phương trình:

$$\frac{x}{1-x} = \frac{1}{x} \text{ или } x^2 + x - 1 = 0.$$

Giải phương trình này ta tìm được điểm $B$. Điểm cần tìm $A_1$ được tìm là giao điểm của đường tròn đã cho $\omega$ với đường tròn có tâm tại điểm $A_0$ và bán kính có chiều dài $x$. Có hai điểm như vậy - và chúng ta nhận được hai lời giải: điểm $A'_1$ và $A''_1$ (Hình 6).

Nhưng phương trình bậc hai của chúng ta có hai nghiệm: $x_1 = -\frac{1}{2} + \frac{\sqrt{5}}{2}$ và $x_2 = -\frac{1}{2} - \frac{\sqrt{5}}{2}$. Gốc thứ hai thật kinh tởm và vì lý do này dường như không thích hợp. Tuy nhiên, chúng ta đừng vội “loại bỏ” gốc này mà hãy cố gắng tìm hiểu ý nghĩa hình học của nó.

Chúng ta hãy khôi phục Hình 6, giả sử rằng điểm $B$ không ở bên phải mà ở bên trái điểm $O$. Chúng ta nhận được Hình 7. Điều này mang lại cho điểm mong muốn $A_1$ thêm hai vị trí có thể có: $A''_1$ và $A'_1$.

Vì vậy, chúng ta có bốn khả năng khác nhau cho điểm $A_1$.

Kết quả là tạo ra hai hình thập giác khác nhau: lồi và hình ngôi sao, và trên mỗi hình đó có thể đánh số các đỉnh khác nhau (xem Hình 6 và 7).

Lưu ý rằng theo “quan điểm” của la bàn và thước kẻ, hình mười giác hình ngôi sao không tệ hơn hình thập giác lồi.

Có thể phản đối: trong một đa giác lồi, các cạnh không liền kề không giao nhau, nhưng trong đa giác hình sao thì chúng lại giao nhau. Nhưng sự phản đối này sẽ biến mất nếu chúng ta gọi các cạnh không phải là đoạn thẳng giữa hai đỉnh (chúng ta không có khái niệm “giữa”!), mà là toàn bộ đường thẳng. Sau đó, bản vẽ chính xác của một hình thập giác “lồi” sẽ xuất hiện, chỉ có kích thước khác với hình “hình sao” (Hình 8).

Tình huống tương tự cũng xảy ra trong trường hợp gót chân có đốm. Ở đây cũng có 4 lời giải, dẫn đến hai điểm khác nhau (Hình 9, a, b) với hai cách đánh số đỉnh khác nhau trên mỗi điểm.

⟦folio 8⟧

Bây giờ, không quyết định rõ ràng bài toán xây dựng một $n$-gon chính quy tùy ý, chúng ta hãy thử xác định xem nó có bao nhiêu lời giải khác nhau. (Hãy nhớ rằng chúng ta coi đường tròn $\omega$ và điểm $A_0$ trên đó.) Gọi $x$ biểu thị độ dài của cung $A_0A_1$. Điểm $A_1$ là một giải pháp cho bài toán (theo quan điểm tuần hoàn), nếu, bằng cách trì hoãn các cung có độ dài $x$ từ điểm $A_0$ liên tiếp $n$ lần, chúng ta quay trở lại điểm xuất phát $A_0$, nhưng nếu trì hoãn ít lần hơn, chúng ta sẽ không quay lại.

Có một cảnh báo cuối cùng. Ngược lại, trong trường hợp, chẳng hạn như $n=6$, chúng ta sẽ phải gọi một hình tam giác cắt ngang hai lần, hoặc một đường kính cắt ngang ba lần, hoặc thậm chí điểm $A_0$ được lặp lại sáu lần, là “hình lục giác nội tiếp đều”.

Trong ngôn ngữ số học, lấy độ dài của toàn bộ hình tròn là một, điều kiện của chúng ta có thể được phát biểu như sau: số $nx$ là số nguyên, còn các số $x$, $2x$, $3x$, ..., $(n-1)$ $x$ không phải là số nguyên. Nếu $n=10$, thì bạn có thể lấy $x$, chẳng hạn như 1/10. Nhưng đây không phải là sự lựa chọn duy nhất có thể. Bạn có thể lấy $x$ cũng bằng 3/10, 7/10 hoặc 9/10.

Điều này tương ứng với bốn nghiệm mà chúng ta đã tìm thấy trước đây về mặt hình học. Lưu ý rằng nếu chúng ta lấy số 11/10 (hoặc 13/10, 17/10, ...) là $x$, thì chúng ta sẽ không nhận được hình học mới lời giải: vị trí của điểm trên đường tròn phụ thuộc vào chính số $x = \frac{k}{n}$ và vào phần dư, cho kết quả $k$ khi chia cho $n$.

Rõ ràng là các phân số tối giản $\frac{m}{n}(m<n)$ và chỉ có chúng mới có tính chất $k \cdot \frac{m}{n}$ chỉ rơi vào một số nguyên (tại điểm đầu của đường tròn) tại $k=n$. Do đó, mọi số nhỏ hơn $n$ và kết hợp với nó bằng phép chiếu sẽ cho lời giải bài toán về một $n$-giác đều, và ta thu được rằng số lời giải riêng biệt của bài toán này được cho bởi hàm Euler (xem mục 2)! Đặc biệt,

$$\varphi(3) = \varphi(4) = \varphi(6) = 2,$$
$$\varphi(5) = \varphi(10) = 4,$$

phù hợp với kết quả thu được ở trên về mặt hình học.

Bây giờ chúng ta hãy nhớ rằng mọi bài toán được phép xây dựng bằng compa và thước thẳng phải khác $2^l$ khác lời giải (xem phần 3), chúng ta có được điều kiện cần thiết thuận tiện cho việc xây dựng bài toán được phép của một $n$-giác thông thường.

Một $n$-giác thông thường cho phép dựng một la bàn và một thước thẳng, tức là $\varphi(n) = 2^l$ đối với một số nguyên $l$.

(Ví dụ: không thể xây dựng một hình bảy cạnh đều vì số $\varphi(7) = 6$ không phải là lũy thừa của hai.)

Chúng tôi bắt đầu giải thích sự cần thiết của điều kiện này. Thực tế là nó cũng đủ là từ
