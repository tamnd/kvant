---
id: 1972-11-soyfer-kletchatyie-doski-i-polimino-2b524bdd
issue: kvant_1972_11
year: 1972
number: "11"
title: Bảng ca rô và polyominoes
authors:
  - Сойфер А. Ю.
rubric: osnovnye-stati
page_first: 6
page_last: 12
page_labels: 4, 5, 6, 9, 10
tag: QK13
lang: vi
source: kvant_digital
extraction: vision
content_sha256: 99fdd8273c928fd4ca5f0135a428739fa9c74ce748d97727e7bc3f0a06e80cb9
prompt_sha256: draft-1
translated_from: content/ru/1972/11/articles/04_soyfer-kletchatyie-doski-i-polimino-2b524bdd.md
source_content_sha256: 111e7195ece68b60bfabdf7e6a177d03d3bb8d11ee9593049e2335e97c37d457
translation_model: draft
translation_run: vi-draft-2026-10-31
translation_quality: draft
---

⟦folio 4⟧

Cơm. 4. Hình 5.

Cơm. 6.

Cơm. 7.

ki là những phần được tô bóng trong Hình 4. Và từ Hình 5, theo đó, nếu một monomino bao phủ một trong các ô này thì phần còn lại của monomino thực có thể được bao phủ bởi các mảnh cắt thẳng.

Vì vậy, điều kiện cần và đủ để xảy ra sự bao phủ của monomino cờ vua và quân cờ thẳng thứ 21 là monomino đó bao phủ một trong các ô được tô màu trong Hình 4.

Cho đến nay chúng ta đang giải quyết “những bằng chứng về sự không thể xảy ra”. Kết quả tiếp theo có tính chất ngược lại: bất kể ô nào của monomino cờ vua, các ô còn lại đều có thể được bao phủ bởi quân cờ hình chữ nhật thứ 21.

Việc chứng minh được thực hiện theo nguyên tắc công nghiệp và đối với một monoki cờ vua có “dạng tổng quát” có kích thước $2^n \times 2^n$. Đối với monoki $2 \times 2$, rõ ràng là bất cứ nơi nào monomino nằm trên đó, ba ô còn lại có thể được bao phủ bằng một hình chữ nhật (Hình 6, a). Bây giờ lấy một monoka có kích thước $4 \times 4$, chúng ta sẽ chia nó thành bốn phần, mỗi phần có kích thước $2 \times 2$ (Hình 6, b). Để monomino bao phủ một ô, chẳng hạn như phần màu vàng trong Hình 6, b. Vì mỗi phần tư của monoki là một doka có kích thước $2 \times 2$, nên nó có thể được bao phủ bởi một mảnh vụn và một monomino bao phủ một ô tùy ý của monoki này. Đã có monomino ở phần màu vàng; Đối với ba phần tư còn lại, chúng ta sẽ đặt các monomino lên chúng ở ô trung tâm (đối với các monomino lớn) - sau đó chúng ta có thể thay thế monomino bằng một triino hình chữ nhật (xem cùng Hình 6, b). Vì vậy, chúng tôi đã bao phủ một đơn quân cờ vua $4 \times 4$ bằng một quân cờ monomino (được đặt ngẫu nhiên) và quân cờ thứ năm bằng quân cờ hình chữ nhật.

Trường hợp monoki $8 \times 8$, cũng như trường hợp tổng quát nhất, được xử lý tương tự (xem Hình 6, c).

Bây giờ hãy chuyển sang Terramino. Có thể dễ dàng bao phủ hoàn toàn một monoka cờ vua bằng các đường thẳng, vuông, đầu G hoặc đầu G - điều này được thấy rõ trong Hình 7. Mặt khác, không thể bao phủ một monoka cosmittermino - xét cho cùng, không thể đặt các teramino xiên trên đế thậm chí để bao phủ hoàn toàn một hàng ô thẳng về bất kỳ phía nào của monoki...

⟦folio 5⟧

Hãy tiếp tục bài học đa hình học của chúng ta, bắt đầu với các bài viết của Giáo sư Golomb.

Bạn đã thấy rằng một số bài toán trên polymnos không nhất thiết cho rằng chúng ta đang nói về một bàn cờ “tiêu chuẩn” $8 \times 8$; chúng tôi cũng đã xem xét bảng $2^n \times 2^n$ cho một số tự nhiên tùy ý $n$. Vì vậy, hãy tiếp tục và nói về những cánh cửa hình vuông tùy ý $n \times n$ và hơn thế nữa là về những cánh cửa hình chữ nhật tùy ý $m \times n$.

Bài toán 1. Tên của một cặp số tự nhiên $(m, n)$ sao cho bảng chữ số $m \times n$ có ​​thể được điền bằng một $k$-mino tuyến tính.

Cách 1 lời giải.

Nếu ít nhất một trong các số $m, n$ chia hết cho $k$ thì bảng $m \times n$ có ​​thể được điền bằng một $k$-mino tuyến tính (kiểm tra!).

Giả sử rằng không có số nào $m, n$ chia hết cho $k$, và bảng $m \times n$ vẫn được bố trí bằng một $k$-mino tuyến tính. Sơn bảng $k$ bằng các màu theo đường chéo, thay đổi màu theo chu kỳ: thứ 1, thứ 2, ..., $k$th, thứ 1, thứ 2, ... (Hình 8).

Một bảng được tô màu theo cách này có một đặc tính thú vị: bất kể $k$-mino tuyến tính được đặt trên đó như thế nào, ngang hay dọc, nó bao phủ chính xác một hình vuông của mỗi màu $k$. Vì vậy, theo giả định, bảng được bao phủ bởi một $k$-mino tuyến tính và mỗi $k$-mino bao gồm cùng một số ô vuông của mỗi màu (mỗi ô một ô)

Cơm. 8. Tô màu đường chéo ở $k=3$.

⟦folio 6⟧

số ô bằng nhau của mỗi màu.

Nhưng mặt khác, trên một bảng như vậy luôn có những đường chéo màu

$$r_2 + r_1 - 1 \leq \frac{k}{2} + \frac{k}{2} - 1 < k,$$

sao cho nó không chứa một ô chứa ít nhất một trong các màu được sử dụng để tô màu. Mâu thuẫn!

Vì vậy, bảng $m \times n$ có thể được bố trí bằng một $k$-minо tuyến tính khi và chỉ khi có ít nhất một trong các số $m, n$ chia hết cho $k$.

bài toán này có thể được giải quyết bằng cách sử dụng màu khác.

Cách thứ 2 lời giải.

Giả sử rằng không có số nào $m, n$ chia hết cho $k$ và bảng $m \times n$ được bố trí bằng một $k$-minо tuyến tính.

Chia số dư $m$ và $n$ cho $k$:

$$m = kq_1 + r_1; \quad 0 < r_1 < k,$$
$$n = kq_2 + r_2; \quad 0 < r_2 < k.$$

Tô màu bảng $k$ với các màu như sau: Cột 1 - màu thứ nhất, màu thứ 2 - thứ 2, ..., $k$th - $k$th, $(k+1)$th - thứ 1, v.v., màu thứ $m$th - $r_1$th (Hình 9).

Được tô màu theo cách này, bảng có đặc tính sau: nếu tuyến tính $k$-minо được đặt thẳng đứng trên bảng thì nó sẽ bao phủ $k$ ô cùng màu và nếu nằm ngang, nó sẽ bao phủ chính xác một ô của mỗi màu. Bảng phải được bố trí $k$-minо; Đó là lý do tại sao

$$S_1 \equiv S_2 \equiv \dots \equiv S_k \pmod{k},$$

trong đó $S_1(l=1, 2, \dots, k)$ là một số

**Cơm. 9. Tô màu cột ở $k=4$.**

các ô có màu $l$ có trong bảng.

Mặt khác, thật dễ dàng để tính toán

$$S_{r_1} - S_{r_1+1} = n;$$

theo,

$$S_{r_1} - S_{r_1+1} \equiv r_2 \pmod{k},$$

Vì thế

$$S_{r_1} \neq S_{r_1+1} \pmod{k}.$$

Kết quả mâu thuẫn cho thấy rằng để tồn tại sự sắp xếp mong muốn, $m: k$ hoặc $k^*$) là cần thiết.

Bạn có nghĩ rằng lời giải bài toán về việc đặt bảng một cách đa giác không nhất thiết phải liên quan đến cách này hay cách khác của việc sơn bảng? Không có gì thuộc loại này!

Cách thứ 3 lời giải.

Giả sử bảng $m \times n$ được bố trí theo tuyến tính $k$-minо và

$$m = kq + r_1; \quad 0 < r_1 < k;$$
$$n \equiv r_2 \pmod{k}; \quad 0 < r_2 < k.$$

Chúng ta sẽ nói rằng $k$-minо “phát triển từ cột thứ $l$” nếu nó nằm ngang và bắt đầu ở cột thứ $l$ (Hình 10).

Chúng ta hãy biểu thị bằng $t_l$ số lượng $k$-minо tăng dần từ cột thứ $l$. Theo giả định, bảng được bố trí $k$-minо; Đó là lý do tại sao

$$t_1 \equiv r_2 \pmod{k},$$
$$t_2 \equiv 0 \pmod{k},$$
$$t_3 \equiv 0 \pmod{k},$$
$$\dots$$
$$t_k \equiv 0 \pmod{k},$$
$$t_{k+1} \equiv r_2 \pmod{k},$$
$$t_{k+2} \equiv 0 \pmod{k},$$
$$\dots$$
$$t_{kq+1} \equiv r_2 \pmod{k}.$$

*) $m: k$, như thường lệ, có nghĩa là $m$ chia hết cho $k$.

⟦folio 9⟧

ka $(x, y)$, trong đó $x \equiv y \equiv 1$ (mod $k$), có vị trí tốt; nếu $m \equiv n \equiv -1$ (mod $k$), thì bất kỳ ô $(x, y)$ nào có $x \equiv y \equiv 0$ (mod $k$) đều được định vị chính xác.

Vì vậy, bài toán lời giải.

Đáp số thuận tiện khi viết dưới dạng bảng (xem bảng trên).

Chúng ta thấy rằng nếu bảng $m \times n$, ở $k > 2$, chứa các ô được đặt đúng vị trí thì số lượng $v$ của chúng là nhỏ so với số lượng của tất cả các ô trên bảng; chứng minh rằng

$$v = \frac{[m + (-1)^r(k - 1)][n + (-1)^r(k - 1)]}{k^2},$$

trong đó $r = 1$ nếu $m \equiv n \equiv 1$ (mod $k$) và $r = -1$ nếu $m \equiv n \equiv -1$ (mod $k$).

Nhưng số lượng tế bào như vậy có thể tăng lên! Chúng ta hãy dán một vài mặt đối diện của tấm bảng của chúng ta: chúng ta sẽ có một hình trụ ca rô (Hình 17).

Nhiệm vụ 3.
a) Một hình trụ được dán từ một tấm ván ca-rô hình chữ nhật $m \times n$. Hầu hết tất cả đều có vị trí tốt -

ny ô của hình trụ cho $k$-mino tuyến tính.

b) Nếu $m \neq n$ thì tùy theo cặp cạnh đối diện nào mà ta dán lại với nhau mà ta có thể có được hai hình trụ khác nhau. Hình trụ nào sau đây có số lượng ô được đặt đúng vị trí nhiều hơn?

Bây giờ chúng ta hãy đi xa hơn và dán các đế của hình trụ của chúng ta (Hình 18).

Con số thu được, được gọi là dịch bệnh, có một “lợi thế” vô điều kiện so với một bàn cờ hoặc một hình trụ ca rô: tất cả các ô của nó đều có giá trị như nhau. Đặc biệt, nếu một hình xuyến ca rô có ít nhất một ô được đặt đúng vị trí thì tất cả các ô của nó đều được đặt đúng vị trí.

Bảng ca rô torid có những ưu điểm khác. Ví dụ: hãy giải câu bài toán sau.

Nhiệm vụ 4.
a) Tìm tất cả các số tự nhiên $n$ sao cho bảng vuông $n \times n$ có thể xếp thành hình chữ nhật như Hình 19.

Cơm. 17.
Cơm. 18.

⟦folio 10⟧

Cơm. 19, 20, 21.

6) Các số tự nhiên nhất cũng là $n$, do đó, bảng đạo đức thu được từ hình vuông của bảng $n \times n$ có thể được sắp xếp bằng cách sử dụng các quân cờ như trong Hình 19.

Vì một mảnh ghép bao gồm ba ô, nên để hình thành bảng $n \times n$ mảnh ghép xảy ra, điều cần thiết là $n$ phải là bội số của 3.

Tất nhiên, một hình chữ nhật có kích thước $2 \times 3$ có thể được đặt dưới dạng hình cắt (Hình 20). Việc đặt một hình chữ nhật có kích thước $5 \times 9$ sẽ khó hơn (Hình 21). Bây giờ, có vẻ không khó lắm để chứng minh (chứng minh điều đó!) rằng hình vuông $n \times n$ có ​​thể được sắp xếp thành một hình tam giác tại $n = 3k$, trong đó $k = 2, 3, \dots$.

Chứng minh rằng hình vuông $3 \times 3$ không thể vừa với các mảnh ghép của chúng ta. Đối với một bảng hình xuyến được dán lại với nhau từ hình vuông $n \times n$, nó có thể được đặt dưới dạng một tấm trang trí cho bất kỳ $n$ nào chia hết cho 3.

Cơm. 22.

Để chứng minh điều này, chúng ta còn phải chứng minh rằng bảng hình xuyến $3 \times 3$ có thể được sắp xếp thành một hình tam giác. Hình 22 cho thấy khả năng sắp xếp như vậy (khi dán các hình xuyến lại với nhau, các ô màu đỏ sẽ kết hợp với nhau để tạo thành một mảnh ghép thuộc loại yêu cầu).

Bài tập

1. Có một hình chữ nhật ca rô là “tốt”, nếu hình tạo ra từ bảng do việc cắt bỏ hai hình vuông này có thể được xếp thành một quân domino. Đây đều là những cặp tế bào tốt.

2. Có một bàn cờ hình chữ nhật $m \times n$ và các số tự nhiên $k$, $k < \frac{mn}{2}$.

Tôi đang chơi trước đây. Người chơi đầu tiên gạch bỏ bất kỳ ô nào trên bảng, sau đó người chơi thứ hai gạch bỏ bất kỳ ô nào khác ngoài việc gạch bỏ bất kỳ ô nào trên bảng khác với ô đã bị gạch bỏ trước đó. Sau khi người chơi đã di chuyển xong thì người chiến thắng đã được xác định. Người thứ hai thắng nếu hình thu được sau khi cắt bỏ tất cả các ô bị gạch bỏ có thể xếp thành quân domino; nếu không, người chơi đầu tiên sẽ bị loại với tư cách là người chiến thắng.

Tìm chiến lược trò chơi cho một trong những người chơi cho phép anh ta giành chiến thắng bất kể cerra của người chiến thắng.

3. a) Chúng cũng đều là các số tự nhiên $n$ sao cho ô vuông của bảng $n \times n$ có thể được bố trí dưới dạng T-mét (xem Hình 2).

6) Kết quả sẽ thay đổi nếu các tấm ván được xếp lại với nhau theo hình trụ? có đạo đức?

4. a) Chúng cũng đều là các số tự nhiên $n$ sao cho một ô vuông của một bảng $n \times n$ có thể xếp T theo chiều kim đồng hồ.

6) Kết quả sẽ thay đổi nếu các tấm ván được xếp lại với nhau theo hình trụ? có đạo đức?

5. a) Một hình trụ được dán từ một tấm ván hình vuông nguyên thủy $m \times n$. Trong những điều kiện nào nó có thể được đặt bằng k-mino tuyến tính?

6) Nếu $m \neq n$, thì từ bảng $m \times n$ bạn có thể dán hai dải Mobius khác nhau. Có thể một trong số chúng có thể được đặt bằng k-mino tuyến tính, còn cái kia thì không?

Cơm. 23.

6. Một tấm bảng hình chữ nhật (trên đó có một hạt ca rô ở cả hai đường) được uốn cong và dán lại, như trong Hình 23. Kết quả là một dải Möbius.

a) Trong điều kiện nào một dải Mobius được dán lại với nhau từ một tấm bảng $m \times n$ có thể được sắp xếp bằng một k-mino tuyến tính?

6) Nếu $m \neq n$, thì từ bảng $m \times n$ bạn có thể dán hai dải Mobius khác nhau. Có thể một trong số chúng có thể được đặt bằng k-mino tuyến tính, còn cái kia thì không?
