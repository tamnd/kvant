---
id: 1972-11-golomb-fragment-stati-shahmatnyie-doski-i-polimino-f07c4eb2
issue: kvant_1972_11
year: 1972
number: "11"
title: '[Đoạn của bài viết “Bàn cờ và đa giác”]'
authors:
  - Голомб С.
rubric: osnovnye-stati
page_first: 4
page_last: 12
page_labels: 4, 5, 6, 9, 10
tag: YZZS
lang: vi
source: kvant_digital
extraction: vision
content_sha256: 2925a8a2dd3c94b1b479adf778e5012eda2f72732df25dbb9fda3484c6a7326f
prompt_sha256: draft-1
translated_from: content/ru/1972/11/articles/03_golomb-fragment-stati-shahmatnyie-doski-i-polimino-f07c4eb2.md
source_content_sha256: af4c354d434cf6e7e80c507e0412b1b8aa5f3c02aba0f7bfc64235e09d313881
translation_model: draft
translation_run: vi-draft-2026-10-31
translation_quality: draft
---

⟦folio none⟧

Klemchaty có chủ quyền và polyomino

A. Yu. Soifer

Giáo sư tại Đại học Nam California S. Golomb là tác giả của một số công trình về lý thuyết thông tin, lý thuyết mã hóa, thống kê toán học và ứng dụng của chúng vào lý thuyết máy toán và di truyền học. Nhưng không phải những tác phẩm này, vốn được các chuyên gia quan tâm vô điều kiện, đã quyết định sự phổ biến rộng rãi của những cái tên chuyên nghiệp trong trò chơi, chính xác hơn là cả một loạt trò chơi gắn liền với cái gọi là “polyominoes”. Golomb xuất bản cuốn sách "Polyominoes" vào năm 1965, trong đó có nhiều bài toáns toán học màu đỏ và thú vị. Một số trong số này và những thứ khác giống như chúng bài toán được độc giả của chúng tôi biết đến qua cuốn sách mới xuất bản gần đây của Martin Gardner “Câu đố toán học và giải trí”* (chương 12 và 46), cũng như từ một loạt ấn phẩm trong mục “Thực hành tâm lý” của tạp chí “Nuka và Cuộc sống” năm 1967-1968, đặc biệt là các trò chơi “pentamino” và “hexatrion” của Golovov và một số trò chơi liên quan bài toán.

“Lịch sử” của polyominoes bắt đầu từ bài báo “Chess Docs and Polyominoes” của Golomb, mà ông, khi vẫn còn là sinh viên tốt nghiệp tại Đại học Harvard, xuất bản năm 1954 trên Tạp chí Toán học Hoa Kỳ hàng tháng. Đoạn trích được xuất bản từ bài viết này (“A.M.M.”, 61 No. 10. Bản dịch của I. I. Yaglom) sẽ giới thiệu cho bạn các khái niệm cơ bản liên quan đến đa thức và đưa ra các ví dụ về “điển hình” bài toán trên đa thức. Trong bài viết tiếp theo chúng ta sẽ nói về một số vấn đề tổng quát hơn về cùng một chủ đề. Vì vậy, hãy chuyển sang S. Golomb.

Chúng ta sẽ bắt đầu với bài toán nổi tiếng:
một bàn cờ được đưa ra, từ đó một cặp ô nguyên vẹn được cắt ra (Hình 1) và một hộp dokino được đưa ra, giống như một không gian có vỏ cây bao phủ hai ô của bàn cờ. Có thể che dokka này bằng miếng đệm dokino thứ 31 không?

Đáp số cho câu hỏi này nói: “Không”; Để chứng minh điều đó, chỉ cần nhìn vào màu sắc chung của ụ cờ là đủ (Hình 1). Bất kỳ không gian Dokino nào được đặt trên dock và bao phủ hai hình vuông sẽ bao phủ một hình vuông sáng và một hình vuông tối,

*) Nhà xuất bản Mir, M., 1971.

và n xương domino là n hình vuông sáng và n hình vuông tối, nghĩa là số cả hai đều bằng nhau. Nhưng ô cờ như trong Hình 1 chứa nhiều ô tối hơn ô sáng. Đó là lý do tại sao nó không thể được che phủ bằng hạt domino.

Chúng ta vẫn sẽ sử dụng bàn cờ 8 × 8 tổng quát làm một “sân chơi”, nhưng chúng ta sẽ khái quát các quân domino thành “đa thức” - và các định lý của chúng ta sẽ bao gồm tất cả các loại đa thức đơn giản nhất được mô tả trong Hình 2. Chính xác hơn: chúng ta sẽ định nghĩa n-mino là một tập hợp n ô vuông của một quân cờ, được nhóm lại “theo nguyên tắc quân xe”, nghĩa là sao cho đặt trên bất kỳ ô vuông nào của n-mino xe có thể

⟦folio none⟧

Trong một số lần di chuyển hữu hạn, hãy di chuyển đến bất kỳ ô nào khác có cùng $n$-mino.

Đầu tiên chúng ta sẽ xem xét các loại vải trang trí. Rõ ràng là một bàn cờ có kích thước $8 \times 8$ không thể được phủ bằng các quân cờ trang trí, vì 64 không chia hết cho 3. Thay vào đó, chúng ta hãy thử phủ bàn cờ bằng 21 quân cờ trang trí và một quân cờ monomino.

Bàn cờ không thể được bao phủ bởi 21 quân cờ nguyên tố và một quân monomino nằm ở góc trên bên trái của bàn cờ. Để chứng minh điều này, bây giờ chúng ta sẽ tô màu bảng theo ba màu: $a$, $b$ và $c$ (Hình 3). Như bạn có thể thấy, chúng ta có 21 trường màu $a$, 22 trường màu $b$ và 21 trường màu $c$. Mỗi phần tử nguyên tố bao gồm một trường màu $a$, một trường màu $b$ và một trường màu $c$, nghĩa là, các phần tử nguyên tố luôn bao gồm cùng một số lượng ô $a$, $b$-ô và $c$-ô. Góc trên bên trái là một ô $a$ và sau khi phủ nó bằng monominos, chúng ta sẽ còn lại số lượng ô $a$-, $b$- và $c$ không bằng nhau. Vì vậy, không thể phủ 63 ô còn lại bằng các số nguyên tố.

Theo cách tương tự, chúng tôi đảm bảo rằng sau khi che bất kỳ ô $a$-hoặc $c$-cell nào bằng monomino, phần còn lại của bảng không thể được che bằng một đường viền nguyên tố. Vẫn chỉ xem xét $b$-ô. Nhưng nếu một monomino bao phủ, chẳng hạn như một ô $b$ nằm ở góc dưới bên trái, thì do tính đối xứng của bảng so với prima $x$ được hiển thị trong Hình 3, chúng ta đi đến lớp phủ bài toán đã được xem xét của prima triomino của bảng, ở góc trên bên trái của bảng đó có một monomino. Góc trên cùng bên trái của bảng là hình vuông $a$, trong trường hợp này không thể che được; Điều này có nghĩa là không thể thực hiện được ngay cả khi monoomino nằm ở góc dưới bên trái.

Do đó, người ta xác định rằng để có thể che phủ, monoomino nhất thiết phải bao phủ một ô $b$ tương đối nguyên tố $x$ và $y$ (xem Hình 3). đối xứng cũng với các tế bào $b$. Những tế bào duy nhất như vậy

⟦folio 4⟧

Hình 4. Hình 5.

Hình 6.

Hình 7.

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

Hình 8. Tô màu đường chéo ở $k=3$.

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

**Hình 9. Tô màu cột ở $k=4$.**

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

⟦folio none⟧

Hình 11.

Mặt khác, rõ ràng là $k$-mino phát triển từ cột thứ $(kq+1)$ sẽ “phát triển” ra ngoài hình chữ nhật, từ đó $t_{kq+1} = 0$ xuất hiện. Ở đây chúng ta cũng đi đến mâu thuẫn, chứng tỏ rằng để tồn tại bố cục bảng $m \times n$ $k$-mino, ít nhất một trong các số $m, n$ phải chia hết cho $k$.

Để biết thêm bài toán, chúng ta sẽ cần một “hệ tọa độ” trên bảng; chúng ta sẽ phác thảo các hàng và cột của bảng (xem Hình 11).

Mỗi ô hiện được chỉ định bởi một cặp số $(x, y)$, trong đó $x$ và $y$ lần lượt là số của hàng và cột chứa ô này.

Bài toán 2. Có một bàn cờ hình chữ nhật $m \times n$ và một bàn cờ $k$-mino tuyến tính. Chúng ta sẽ gọi ô bảng $(x, y)$ là “được đặt đúng vị trí” nếu mảnh $F$ thu được từ bảng do cắt ô này có thể được tạo bằng $k$-mino tuyến tính. Tên $M$ của tất cả các ô vuông được đặt đúng vị trí trên bảng.

Đối với $k = 1$, rõ ràng, $M$ trùng với tập hợp tất cả các ô vuông trên bảng. Giả sử rằng $k = 2$. Giả sử rằng một hình vuông được cắt ra từ một hình chữ nhật và hình thu được $F$ được trình bày dưới dạng domino; sau đó $(mn-1)$ —

Hình 12.

Hình 13.

Hình 14.

⟦folio none⟧

ô $(x, y)$, tức là $x \equiv y$ (mod 2); nếu ít nhất một trong các số $m, n$ là bội số của 2 thì bảng $m \times n$ không có các ô được đặt đúng vị trí.

Hãy để bây giờ $k > 2$. Trong trường hợp này $1 \neq -1$ (mod $k$).

Giả sử rằng hình kết quả $F$ sau khi cắt ô $(x, y)$ được trình bày bởi một $k$-mino tuyến tính. Chúng ta hãy sắp xếp một cột màu theo chu kỳ gồm $k$ màu trên bảng này (xem Hình 9). Chúng tôi đã ghi nhận đặc tính của một bảng được tô màu theo cách này: nếu một $k$-mino tuyến tính nằm dọc trên bảng, thì nó bao phủ $k$-ô cùng màu và nếu theo chiều ngang, nó bao phủ chính xác một hình vuông của mỗi màu. Theo giả định, hình $F$ được trình bày bằng $k$-mino tuyến tính; Đó là lý do tại sao

$$P_1 \equiv P_2 \equiv \dots \equiv P_k \pmod{k},$$

(1) trong đó $P_l (l = 1, 2, \dots, k)$ là số ô có màu $l$ trong hình $F$.

Cho phép

$$m = kq_1 + r_1 \quad (0 \leqslant r_1 < k),$$
$$n = kq_2 + r_2 \quad (0 \leqslant r_2 < k).$$

Chúng ta hãy biểu thị bằng $S_l (l = 1, 2, \dots, k)$ số ô có màu $l$ trong toàn bộ bảng. Dễ dàng tính được điều đó

$$S_1 = \dots = S_{r_1} = n(q + 1),$$

(2a)
$$S_{r_1+1} = \dots = S_k = nq.$$

Hình $F$ chứa chính xác một ô nhỏ hơn toàn bộ bảng, do đó, từ sự tương ứng (1) và (2), theo đó chỉ có hai khả năng: $r_1 = 1$ và một ô bị cắt ra có màu đầu tiên, hoặc $r_1 + 1 = k$ và một ô bị cắt ra có màu $k$.

1 con sên. Ô cắt $(x, y)$ có màu đầu tiên, tức là $y \equiv 1 \pmod{k}, r_1 = 1, m \equiv 1 \pmod{k}$, và ngoài ra,

$$S_1 - 1 \equiv S_2 \equiv S_3 \equiv \dots \equiv S_k \pmod{k},$$

từ đâu $n(q + 1) - 1 \equiv nq$. (mod $k$), tức là $n \equiv 1 \pmod{k}$.

Vì vậy, $m \equiv n \equiv y \equiv 1 \pmod{k}$.

Lớp thứ 2. Ô bị cắt $(x, y)$ có màu $k$, tức là $y \equiv 0 \pmod{k}, r_1 = k - 1,$

$$m \equiv -1 \pmod{k}$$ và, ngoài ra,

$$S_1 \equiv S_2 \equiv \dots \equiv S_{k-1} \equiv S_k - 1 \pmod{k},$$

từ đâu $nq - 1 \equiv n(q + 1) \pmod{k}$, tức là $n \equiv -1 \pmod{k}$.

Vì thế,

$$m \equiv n \equiv -1 \pmod{k}; y \equiv 0 \pmod{k}.$$

Bây giờ chúng ta hãy biến bảng này thành $90^\circ$, tức là xem xét bảng $n \times m$ và áp dụng lý luận trên cho nó. Dưới đây là kết luận cuối cùng: nếu $m \equiv n \equiv 1 \pmod{k}$, thì tọa độ của ô nằm ở xa $(x, y)$ phải thỏa mãn sự tương ứng $x \equiv y \equiv 1 \pmod{k}$. Nếu $m \equiv n \equiv -1 \pmod{k}$ thì tọa độ của ô nằm ở xa $(x, y)$ phải đáp ứng sự tương ứng $x \equiv y \equiv 0 \pmod{k}$.

$x \equiv y \equiv 0 \pmod{k}$.

Trong các trường hợp khác, bảng $m \times n$ không có các ô được định vị từ xa.

Hình 15 và 16 cho thấy nếu $m \equiv n \equiv 1 \pmod{k}$ thì ô bất kỳ

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

Hình 17.
Hình 18.

⟦folio 10⟧

Hình 19, 20, 21.

6) Các số tự nhiên nhất cũng là $n$, do đó, bảng đạo đức thu được từ hình vuông của bảng $n \times n$ có thể được sắp xếp bằng cách sử dụng các quân cờ như trong Hình 19.

Vì một mảnh ghép bao gồm ba ô, nên để hình thành bảng $n \times n$ mảnh ghép xảy ra, điều cần thiết là $n$ phải là bội số của 3.

Tất nhiên, một hình chữ nhật có kích thước $2 \times 3$ có thể được đặt dưới dạng hình cắt (Hình 20). Việc đặt một hình chữ nhật có kích thước $5 \times 9$ sẽ khó hơn (Hình 21). Bây giờ, có vẻ không khó lắm để chứng minh (chứng minh điều đó!) rằng hình vuông $n \times n$ có ​​thể được sắp xếp thành một hình tam giác tại $n = 3k$, trong đó $k = 2, 3, \dots$.

Chứng minh rằng hình vuông $3 \times 3$ không thể vừa với các mảnh ghép của chúng ta. Đối với một bảng hình xuyến được dán lại với nhau từ hình vuông $n \times n$, nó có thể được đặt dưới dạng một tấm trang trí cho bất kỳ $n$ nào chia hết cho 3.

Hình 22.

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

Hình 23.

6. Một tấm bảng hình chữ nhật (trên đó có một hạt ca rô ở cả hai đường) được uốn cong và dán lại, như trong Hình 23. Kết quả là một dải Möbius.

a) Trong điều kiện nào một dải Mobius được dán lại với nhau từ một tấm bảng $m \times n$ có thể được sắp xếp bằng một k-mino tuyến tính?

6) Nếu $m \neq n$, thì từ bảng $m \times n$ bạn có thể dán hai dải Mobius khác nhau. Có thể một trong số chúng có thể được đặt bằng k-mino tuyến tính, còn cái kia thì không?
