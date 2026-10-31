---
id: 1981-10-pereyaslavskiy-igra-opredelitel-8939c3ab
issue: kvant_1981_10
year: 1981
number: "10"
title: Trò chơi "Nhận dạng"
authors:
  - Переяславский В. И.
rubric: matematicheskiy-kruzhok
rubric_sub: Математический кружок
page_first: 29
page_last: 32
page_labels: 27-30
tag: HPFR
lang: vi
source: kvant_digital
extraction: vision
content_sha256: df5db9b83249834bdaa791dce3e5cdc3551a42271923087d14b07453e77a8a14
prompt_sha256: draft-1
translated_from: content/ru/1981/10/articles/09_pereyaslavskiy-igra-opredelitel-8939c3ab.md
source_content_sha256: 2c53143abeefcfed535da769abfb31fe56f26fc4025815f5a05969ee00ffd533
translation_model: draft
translation_run: vi-draft-2026-10-31
translation_quality: draft
---

⟦folio 27⟧

V. Pereyaslavsky

Trò chơi
"Sự định nghĩa"

Hai phiên bản của một trò chơi
Năm 1978, «Kvant», khi nói về Lễ hội các nhà toán học trẻ lần thứ IX ở Batumi (xem số 10), đã mời độc giả của mình đưa ra chiến lược chiến thắng cho trò chơi sau:

Chơi theo hai người. Các em lần lượt xếp các số từ 1 đến 9 vào bảng 3x3 (phải sử dụng từng số). Sau khi bảng được điền, hai tổng được tính: tổng của $S_1$ sản phẩm theo cột và tổng của $S_2$ sản phẩm theo hàng. Nếu $S_1 > S_2$, phần cổ đầu tiên được kéo ra; nếu $S_1 < S_2$, cerrok thứ hai được kéo ra.

Vào năm 1971, trò chơi này, với một hình thức hơi khác, đã trở nên phổ biến trong giới sinh viên Khoa Cơ và Toán của Đại học Tổng hợp Moscow (và họ đã biết về nó từ các sinh viên của Đại học Perm). Trò chơi này có tên là “Định nghĩa” và trông như thế này:

Hai lần lặp. Các em lần lượt xếp các số từ 1 đến 9 vào bảng 3x3 (phải sử dụng từng số). Sau khi bảng được điền, hai tổng được tính: tổng của $S_1$ sản phẩm theo cột và tổng của $S_2$ sản phẩm theo hàng. Nếu $S_1 > S_2$, phần cổ đầu tiên được kéo ra; nếu $S_1 < S_2$, cerrok thứ hai được kéo ra.

Tất nhiên, ở đây chúng tôi phải bắt buộc bạn rằng định thức của bảng $T$ (Hình 1) là số
$$d = x_1 x_5 x_9 + x_2 x_6 x_7 + x_3 x_4 x_8 - x_3 x_5 x_7 - x_1 x_6 x_8 - x_2 x_4 x_9.$$
Chúng tôi mời bạn tự mình xem xét rằng hai trò chơi này về cơ bản là giống nhau. Tiếp theo chúng ta sẽ xem xét tùy chọn được đề xuất trong «Kvant».

Thông điệp hữu ích
Tất cả các trò chơi có thể được chia thành đơn giản và phức tạp. Trò chơi đơn giản là những trò chơi có

$$T = \begin{bmatrix}
x_1 & x_2 & x_3 \\
x_4 & x_5 & x_6 \\
x_7 & x_8 & x_9
\end{bmatrix}$$

Cơm. 1.

⟦folio 28⟧

chiến lược chiến thắng đơn giản, chiến lược phức tạp - tất cả phần còn lại. Có vẻ như trò chơi "Định danh" rất khó. Độ phức tạp là điều kiện không thể thiếu cho sự phổ biến của trò chơi. Ví dụ, mọi người đều nhiệt tình chơi cờ và tic-tac-toe trên một tờ giấy ca rô, nhưng chỉ những học sinh nhỏ tuổi hơn mới chơi tic-tac-toe trên bảng 3x3.

Hãy giải bài toán, điều này sẽ giúp chúng ta chơi “Định thức”: chúng ta sẽ tìm các giá trị nhỏ nhất; áp dụng vào chủ đề các thuật ngữ của nó sự bất đẳng thức về trung bình số học và trung bình hình học («Kvant», 1980, số 3, trang 23):

$$\frac{x_1 x_2 x_3 + x_4 x_5 x_6 + x_7 x_8 x_9}{3} \geq \sqrt[3]{x_1 x_2 \cdot \dots \cdot x_9} = \sqrt[3]{9!} = \sqrt[3]{70 \cdot 72^2} > 71.$$

Do đó $S > 213$ và vì $S$ là số nguyên nên $S \geq 214$. Nhưng $2 \cdot 5 \cdot 7 + 1 \cdot 8 \cdot 9 + 3 \cdot 4 \cdot 6 = 70 + 72 + 72 = 214$; Điều này có nghĩa là giá trị nhỏ nhất được yêu cầu là 214.

Để tìm giá trị nhỏ nhất của tổng của chúng ta, hãy sử dụng bổ đề sau (bằng chứng!): nếu các số $a, b, c, d$ là dương, $ab = cd$ và $|a - b| > |c - d|$, thì $a + b > c + d$.

Chúng ta hãy tạo một tổng mới $S'$ như thế này: giữ nguyên số hạng cuối cùng $x_7 x_8 x_9$, tạo số hạng đầu tiên $x'_1 x'_2 x'_3$ từ ba số nhỏ nhất của tập hợp $\{x_1, x_2, \dots, x_6\}$ và số hạng thứ hai $x'_4 x'_5 x'_6$ từ các số còn lại của tập hợp này. Khi đó theo Bổ đề $S \leq S'$, và dấu bằng sẽ chỉ xảy ra trong trường hợp mỗi số $x_1, x_2, x_3$ lớn hơn (hoặc nhỏ hơn) mỗi số $x_4, x_5, x_6$. Từ đó, chúng ta thu được rằng giá trị của tổng $S$ sẽ nhỏ nhất nếu tất cả các thành phần của số hạng thứ nhất nhỏ hơn tất cả các thành phần của số hạng thứ hai và đến lượt chúng lại nhỏ hơn tất cả các thành phần của số hạng thứ ba. Vì vậy, yêu cầu nhỏ nhất là $1 \cdot 2 \cdot 3 + 4 \cdot 5 \cdot 6 + 7 \cdot 8 \cdot 9 = 6 + 120 + 504 = 630$.

Tóm lại: tổng $S$ nhận giá trị nhỏ nhất khi các số hạng của nó càng gần nhau càng tốt (và do đó bằng khoảng 71) và giá trị lớn nhất là khi chúng càng khác nhau càng tốt. Do đó, lời khuyên thiết thực dành cho người chơi: hãy cố gắng đảm bảo rằng các điều khoản của đối thủ gần giống nhau (và bằng 71) và các điều khoản của riêng bạn càng khác nhau càng tốt!

**Chiến lược “71” cho người chơi đầu tiên**

Giả sử sau nước đi đầu tiên của bạn, đối thủ đã viết số của anh ta vào cùng cột hoặc dòng với số của bạn. Sau đó, chúng tôi cung cấp cho bạn chiến lược sau “71”:

Đối với mỗi hàng được điền và mỗi cột được điền của bảng, chúng tôi xác định số

$$m = \begin{cases} \frac{\Pi}{71}, \text{ если } \Pi \geq 72, \\ 71/\Pi, \text{ если } \Pi \leq 71, \end{cases}$$

trong đó $\Pi$ là tích của các số được viết trong một hàng hoặc cột nhất định.

Ở nước đi tiếp theo, người chơi bắt đầu phải hoàn thành một hàng hoặc cột theo quy tắc sau: nếu hoàn thành một hàng thì với một số sẽ cho giá trị tối thiểu $m$ cho hàng này (sản phẩm càng lớn càng tốt đến 71) và nếu - một cột, thì với một số sẽ cho giá trị tối đa $m$ cho cột này (sản phẩm càng khác với 71 càng tốt).

Hãy để chúng tôi giải thích điều này bằng một ví dụ. Để thuận tiện cho việc trình bày, chúng tôi đánh số các ô trong bảng (Hình 2) và viết trò chơi dưới dạng một dòng gồm chín số có chỉ số, trong đó chỉ số biểu thị số ô,

**Cơm. 2.**

⟦folio 29⟧

trong đó số đã cho được viết ở nước đi tương ứng. Hãy đảm bảo rằng trong trò chơi $3_55_81_24_66_47_72_98_19_3$ người chơi bắt đầu trò chơi đã sử dụng chiến lược “71” (chiến lược không áp đặt chiến lược hạn chế ở nước đi đầu tiên).

Sau hai nước đi đầu tiên (Hình 3, a), người chơi đầu tiên theo chiến thuật phải điền vào ô số 2 một con số cho m lớn nhất có thể. Trong trường hợp này, m tối đa có thể là nước đi 1$_2$, trong đó tích của các số ở cột thứ hai là 15 hoặc nước đi 9$_2$, cho kết quả 135. Vì 71/15 > 135/71, bạn cần đặt 1 vào ô số 2, thế là xong.

Sau khi di chuyển 4$_6$ (Hình 3.6), ở ô số 4, bạn cần đặt một số có giá trị tối thiểu là m, cụ thể là 6$_4$, v.v.

Hai trường hợp đặc biệt

1. Nếu một tserajutsezo có tích $1 \times 2 \times 3$, hoặc $1 \times 2 \times 4$, hoặc $6 \times 8 \times 9$ hoặc $7 \times 8 \times 9$, thì nó sẽ chọn ra bất kể các số còn lại nằm trong bảng như thế nào.

Ví dụ, chúng ta hãy chứng minh rằng khi bảng có cột số 1, 2, 4 thì người mới bắt đầu sẽ thắng. Giả sử nếu bảng trông giống như Hình 4 thì

$$\frac{x_2x_5x_8+x_3x_6x_9}{2} \geq \sqrt{x_2x_5x_8x_3x_6x_9} = \sqrt{3 \cdot 5 \cdot 6 \cdot 7 \cdot 8 \cdot 9} > 212.$$

Vì vậy, $S_1 \geq 1 \cdot 2 \cdot 4 + 425 = 433$.

Mặt khác, giá trị của tổng $S_2$ là lớn nhất khi các số $x_2$ và $x_3$ nhỏ hơn $x_5$ và $x_6$, và $x_5$ và $x_6$ nhỏ hơn $x_8$ và $x_9$. Vì vậy, $S_2 \leq 1 \cdot 3 \cdot 5 + 2 \cdot 6 \cdot 7 + 4 \cdot 8 \cdot 9 = 387$, tức là $S_1 > S_2$, như đã nêu.

2. Ngược lại, khi chơi, có thể sử dụng ý tưởng "zugschang" - việc đối phương không có nước đi hợp lý. Ví dụ: trong tình huống được mô tả trong Hình 5, người bắt đầu, ở bất kỳ nước đi nào của người chơi thứ hai, có thể (và phải) đặt các số 1, 2 vào một cột và 8, 9 vào cột kia. Sau khi tính toán các lựa chọn khác nhau, có thể dễ dàng kiểm tra xem điều này có đảm bảo số tiền thắng mà anh ta đã bắt đầu hay không.

Đang cố gắng phá sản

Thoạt nhìn, “Người quyết định” có vẻ không khó lắm: đối thủ chỉ thực hiện chín nước đi và mỗi nước đi không có quá chín phương án - hãy tính toán tất cả các phương án và chọn phương án đúng. Vấn đề là có quá nhiều đảng phái khác nhau.

Trên thực tế, ở nước đi đầu tiên có 81 lựa chọn (một trong chín số ở một trong chín ô); cho nước đi thứ hai - 64 tùy chọn, v.v. (Hình 6) - tổng cộng $9^2 \cdot 8^2 \cdot 7^2 \cdot \ldots 2^2 \cdot 1^2 = (9!)^2 \approx 1,3 \cdot 10^{11}$ trò chơi khác nhau. Tất nhiên, không thể xác định kết quả của trò chơi bằng cách tìm kiếm như vậy, ngay cả khi có sự trợ giúp của máy tính.

Đúng, tìm kiếm này quá thô và ước tính quá cao: xét cho cùng, trò chơi của chúng ta có tính đối xứng. Ví dụ: tất cả các bước đi đầu tiên trong các ô khác nhau có cùng số lượng đều bằng nhau; do đó, cần phải xem xét không phải 81 mà chỉ có 9 phương án cho nước đi đầu tiên. Tám ô còn lại cho lần di chuyển thứ hai có thể được chia thành ba lớp sao cho các bước di chuyển có cùng số vào các ô cùng lớp sẽ bằng nhau (trong Hình 7, các ô thuộc các lớp khác nhau được sơn bằng các màu khác nhau); do đó, cần phải xem xét không phải 64 mà là 8 \cdot 3 = 24 phương án cho nước đi thứ hai. Vì vậy, chúng tôi đã cố gắng giảm ước tính trên của số lượng trò chơi xuống con số $9 \cdot 24 \cdot 7^2 \cdot 6^2 \cdot \ldots \cdot 2^2 \cdot 1^2 \approx$

⟦folio 30⟧

≈ 5 · 10^9, tuy nhiên, vẫn rất lớn. Chúng ta cần một ý tưởng mới giúp giảm thiểu việc lựa chọn các phương án. Tôi tìm thấy một ý tưởng như vậy.

Làm thế nào một nhà hiền triết có thể giúp đỡ?

Giả sử có một nhà hiền triết xuất hiện và tuyên bố rằng khi bắt đầu trò chơi, anh ta sẽ giành được chiến thắng, và hãy để nhà hiền triết này tử tế đến mức thực hiện các nước đi giống nhau ở các vị trí giống nhau. Bạn cần chơi bao nhiêu trò chơi với nhà hiền triết để kiểm tra xem anh ta thực sự có tiền thắng hay không?

Nhà hiền triết bắt đầu mọi trò chơi theo cùng một cách; chúng ta phải thử chơi với anh ta tất cả 24 lựa chọn cho nước đi thứ hai. Ở mỗi vị trí của nước đi thứ hai, nhà hiền triết rõ ràng thực hiện nước đi thứ ba; chúng tôi xem xét tất cả 36 lựa chọn cho nước đi thứ tư, v.v. (Hình 8). Tổng cộng, bạn cần chơi 24 · 6^2 · 4^2 · 2^2 = 55296 trò chơi để kiểm tra hiền nhân.

Sau khi tiếp xúc với một nhà hiền triết trong một tháng, bạn có thể bị thuyết phục về bản chất đôi bên cùng có lợi của anh ta hoặc chứng minh điều ngược lại. Bạn có thể tạo và gỡ lỗi một chương trình máy tính để kiểm tra hiền nhân, tuy nhiên, việc này sẽ mất cùng tháng, nhưng với cùng một chương trình, giờ đây bạn có thể kiểm tra bất kỳ chiến lược nào để "chiến thắng".

Vì vậy, có một chương trình kiểm tra, nhưng hiền nhân ở đâu? Tác giả đã phải học cách chơi và sử dụng các thông điệp và chiến lược đã được thể hiện, dần dần điều chỉnh các nước đi không mang lại chiến thắng cho người mới bắt đầu (chúng được phát hiện bằng chương trình kiểm tra), “biến” thành một trò chơi như vậy.
