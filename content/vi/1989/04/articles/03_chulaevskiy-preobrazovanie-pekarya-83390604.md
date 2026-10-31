---
id: 1989-4-chulaevskiy-preobrazovanie-pekarya-83390604
issue: kvant_1989_4
year: 1989
number: "4"
title: Chuyển đổi thợ làm bánh
authors:
  - Чулаевский В. А.
rubric: raznoe
page_first: 21
page_last: 24
page_labels: 19-22
tag: 52LL
lang: vi
source: kvant_digital
extraction: vision
content_sha256: 4d57f4f8c61e827596b6e5961940cbc18bd5ee25c5bbfaf73b0e10ff5d46d395
prompt_sha256: draft-1
translated_from: content/ru/1989/04/articles/03_chulaevskiy-preobrazovanie-pekarya-83390604.md
source_content_sha256: 7675891de8984f884deb8a1fe71ea3da9daf29273c1bb9ed677c90fe3f3252c4
translation_model: draft
translation_run: vi-draft-2026-10-31
translation_quality: draft
---

⟦folio 19⟧

SỰ CHUYỂN ĐỔI CỦA BAKER

Ứng viên Khoa học Vật lý và Toán học
V. A. CHULAEVSKY

Nếu chúng ta phải nghe những từ “xác suất”, “ngẫu nhiên”, thì xin vui lòng, chúng ta thường nhớ đến trò chơi lật bài, ném xúc xắc hoặc xáo bài. Và bản thân thuật ngữ “cờ bạc” bắt nguồn từ từ tiếng Pháp hasard, có nghĩa là “trường hợp”. Những nỗ lực tìm kiếm các cơ chế ẩn giấu để kiểm soát tình hình đã được thực hiện mọi lúc. Tuy nhiên, như một quy luật, họ đã kết thúc một cách buồn bã - hãy nhớ đến Hermann của Pushchin! Và có điểm chung nào giữa sự tiền định hoàn toàn (“ba, bảy, át”) và sự ngẫu nhiên không? Đừng vội với đáp số mà bây giờ hãy... nấu ăn.

Bài toán về bánh không muối. Vì vậy, hãy nướng một chiếc bánh. Hãy mở sách dạy nấu ăn và chọn một công thức phù hợp với sở thích của bạn. Chúng ta thay bột, đợi cho đến khi bột nổi lên rồi dùng cán cán thành hình vuông. Hãy bắt đầu với phần nhân... Đợi đã, chúng ta không thêm muối vào bột. Chà, chúng ta hãy cố gắng sửa chữa sai lầm của mình: lấy một thìa cà phê muối và... Ôi, thật cẩu thả! Tất cả muối được đổ vào góc của chiếc bánh tương lai (hình 1). Nhưng điều này không nên làm chúng ta bối rối (vì thực tế là “hình vuông” trong bản vẽ của chúng ta “trông” giống như một góc vuông). Kinh nghiệm của những người thợ làm bánh đã giúp ích: chúng ta kéo giãn hình vuông hai lần theo chiều ngang, chế độ làm đôi theo chiều dọc và một lần nữa tạo thành hình vuông như trong hình 2.

Những gì chúng ta đã làm với hình vuông đôi khi được gọi là phép biến đổi của thợ làm bánh. Bất kỳ bà nội trợ nào cũng biết rằng bằng cách này bạn có thể làm cho bột rất đồng nhất. Nhưng bạn nghĩ thủ tục này cần phải được lặp lại bao nhiêu lần để muối đổ vào góc được phân bổ gần như bằng nhau cho tất cả các miếng của chiếc bánh tương lai - hai? Mười? một trăm? một ngàn?

Hình học biến đổi Baker. Hãy chia hình vuông làm đôi theo chiều dọc. Hãy chơi trò chơi sau: chúng ta chọn một điểm trong hình vuông và nếu sau khi người thợ làm bánh biến đổi, điểm đó nằm ở nửa bên trái của hình vuông thì chúng ta thắng, nếu không thì chúng ta thua.

“Một trò chơi dành cho trẻ mẫu giáo,” bạn nói. — Rõ ràng là điểm phải được chọn trên hai sọc dọc được tô màu ở hình 2, a.

Phải. Chúng ta sẽ phải phức tạp hóa luật chơi; Sau khi chọn một điểm, chúng tôi lặp lại phép biến đổi của thợ làm bánh 10 lần và chỉ sau đó chúng tôi mới xem nó rơi vào nửa hình vuông nào. Bây giờ cột chiến lược chiến thắng không hiển thị. Để tìm một tập hợp các điểm cho một n tùy ý mà sau khi áp dụng phép biến đổi baker n lần, kết thúc ở nửa bên trái của hình vuông, thật thuận tiện khi theo dõi chuyển động của điểm dưới tác dụng của nghịch đảo

⟦folio 20⟧

Hình 3

sự biến đổi của người thợ làm bánh, tức là sự biến đổi của người thợ làm bánh được thực hiện theo cách tượng hình. Nó trông như thế nào được hiển thị trong hình 3. Áp dụng điều này sau khi lặp lại phép biến đổi của thợ làm bánh $n$ lần. Và mặc dù tập hợp “chiến thắng” được chỉ định rõ ràng, nhưng vẫn đáng mắc sai lầm khi xác định hoành độ của điểm trên $2^{-n-1}$ (và giá trị này khá cao).

biến đổi nhiều lần liên tiếp thành một hình vuông duy nhất, nửa bên trái được tô bóng, ta được dãy hình như ở hình 4. Ở bước $n$-th, tất cả các sọc dọc có chiều rộng $2^{-n-1}$ với số lẻ nếu đếm từ trái sang phải sẽ bị tô bóng. Chính những điểm này sẽ đi về nửa bên trái của hình vuông

Hình 4.

20

⟦folio 21⟧

nhưng nhỏ ngay cả đối với các giá trị nhỏ của n) và chúng tôi đã thua. Việc xuất hiện dù chỉ một lỗi nhỏ cũng khiến trò chơi rất giống trò tung bài: xét cho cùng, set thắng luôn có diện tích là 1/2 nên nếu chọn ngẫu nhiên một điểm thì xác suất thắng cũng là 1/2.

Sự biến đổi. Chúng ta đã quên rằng sẽ có một chiếc bánh hỏng trong bếp. Tuy nhiên, thời gian đã không bị lãng phí. Bây giờ chúng tôi biết rằng việc khắc phục vấn đề không hề khó khăn. Chỉ cần lặp lại quá trình biến đổi của người làm bánh 15-20 lần là đủ, bột sẽ được muối gần như đều. Hãy cùng theo dõi sự tiến hóa của phần muối tròn của chiếc bánh - hình 5. Bạn có thể bắt đầu không chỉ với hình vuông mà còn với bất kỳ hình dạng nào. Trong mọi trường hợp, sau một số lần lặp lại nhỏ, hình ảnh của hình này sẽ được "bôi" đều trên hình vuông. Chính xác hơn, nó có thể được xây dựng như thế này. Chúng ta hãy biểu thị phép biến đổi của thợ làm bánh bằng T,

⟦folio 22⟧

và các đường dẫn $A$ và $B$ là hai hình có diện tích khác 0 nằm bên trong hình vuông, ví dụ như hai đa giác. Sau đó, khi $n$ tăng lên, tỷ lệ diện tích $(T^n(A) \cap B)/$ so với diện tích $(A)$ có xu hướng bằng một phần diện tích của tập hợp $B$ so với diện tích của toàn bộ hình vuông. Điều này có nghĩa là đối với $n$ lớn, cơ hội nhận được từ $A$ đến $B$ trong $n$ bước dưới ảnh hưởng của $T$ trên thực tế không phụ thuộc vào $A$, tức là vào vị trí ban đầu của điểm, nhưng tập hợp $B$ chỉ phụ thuộc vào khu vực.

Thuộc tính mà chúng ta đã hình thành được gọi là *change*. Nó có nghĩa là bất kỳ hình nào cũng trải đều trên hình vuông theo thời gian.

**Một số công thức.** Tôi muốn tìm hiểu cách mô tả sự biến đổi của người thợ làm bánh bằng các công thức. Việc giảm một nửa liên quan đến định nghĩa về phép biến đổi cho thấy rằng hệ thống số kép có thể hữu ích trong cách mô tả như vậy. Hãy nhớ rằng mỗi số $\alpha$ từ khoảng $[0;1)$ có thể được viết là $0, \alpha_1 \alpha_2 \alpha_3...$, trong đó mỗi $\alpha_i$ bằng 0 hoặc 1. Ký hiệu này có nghĩa là $\alpha = \alpha_1/2 + \alpha_2/2^2 + \alpha_3/2^3 +...$; ví dụ: 1/2 có thể được viết trong hệ thống kép là 0,1 và 1/3 là 0,010101... Ý nghĩa hình học của ký hiệu như vậy như sau. Chia khoảng $[0;1)$ làm đôi. Nếu $\alpha_1 = 0$ thì số $\alpha$ nằm ở nửa bên trái của khoảng: $[0;1/2)$ và nếu $\alpha_1 = 1$ thì ở nửa bên phải: $[1/2;1)$. Đặt $\alpha_1 = 0$ để xác định. Sau đó, $\alpha_2$ cho biết nửa khoảng $[0;1/2)$ nằm $\alpha$ - ở bên trái ($\alpha_2 = 0$) hoặc ở bên phải ($\alpha_2 = 1$). Tất cả các chữ số nhập kép khác đều có ý nghĩa tương tự.

**Bài tập**

1. Chứng minh rằng $1/3 = 0,010101$...

Gợi ý: sử dụng công thức tính tổng của một cấp số nhân vô hạn: $q + q^2 + q^3 +... = q/(1-q)$.

2. Viết 1/7 dưới dạng phân số kép.

3. Viết 0,110110110... dưới dạng phân số khách quan.

Lấy điểm $m$ trong bình phương đơn vị $K = \{(x;y):0 \leqslant x < 1, 0 \leqslant y < 1\}$ có tọa độ $(x;y)$, viết dưới dạng kép: $x = 0, x_1 x_2..., y = 0, y_1 y_2...$. Chúng ta hãy xem ký hiệu kép của tọa độ của điểm $m$ thay đổi như thế nào nếu áp dụng phép biến đổi của thợ làm bánh cho nó. Nếu $x_1 = 0$, tức là $m$, nằm ở nửa bên trái của hình vuông thì trục hoành của nó sẽ tăng gấp đôi. Vì lý do này mà chúng tôi đã đặt trước ký hiệu kép của số thập phân: trong hệ thống số thập phân, việc nhân phân số với 10 rất đơn giản - chỉ cần di chuyển phân số tương ứng với dấu thập phân sang trái 1 vị trí và trong hệ thống số chính xác kép, phép nhân với 2 cũng hoạt động theo cách tương tự.

Vì vậy, trục hoành của điểm $T(m)$ bằng 0, $x_2 x_3...$. Nếu như $x_1 = 1$, thì ở giai đoạn đầu tiên của quá trình chuyển đổi thợ làm bánh (hình 2, b) điểm $m$ sẽ đi đến điểm abscissa $1, x_2 x_3...$, và sau khi cắt (hình 2, e) - di chuyển 1 sang trái, vì vậy trong trường hợp này trục hoành của điểm $T(m)$ bằng 0, $x_2 x_3...$. Bây giờ chúng ta hãy theo dõi sự thay đổi tọa độ của điểm $m$. Ở giai đoạn đầu tiên, nó sẽ giảm đi một nửa: $y \rightarrow 0,0 y_1 y_2...$, và sau đó không thay đổi (tại $x_1 = 0$), hoặc sẽ tăng 1/2 (tại $x_1 = 1$). Điều này có nghĩa là chúng ta có thể viết tọa độ của điểm $T(m)$ bằng 0, $x_1 y_1 y_2...$. Để rõ ràng, hãy viết tọa độ của điểm $m$ trong một dòng như thế này:

$$m \leftrightarrow (\dots y_3 y_2 y_1, x_1 x_2 x_3...).$$
