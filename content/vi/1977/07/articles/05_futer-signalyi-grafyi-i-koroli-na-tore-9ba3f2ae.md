---
id: 1977-7-futer-signalyi-grafyi-i-koroli-na-tore-9ba3f2ae
issue: kvant_1977_7
year: 1977
number: "7"
title: Tín hiệu, đồ thị và các vị vua trên hình xuyến
authors:
  - Футер А. Л.
rubric: osnovnye-stati
page_first: 16
page_last: 21
page_labels: 14-19
tag: RLVU
lang: vi
source: kvant_digital
extraction: vision
content_sha256: 5c552c345282011ba6a4cfca4db0fcf1f10f71819d63c676f080dfb090228ae7
prompt_sha256: draft-1
translated_from: content/ru/1977/07/articles/05_futer-signalyi-grafyi-i-koroli-na-tore-9ba3f2ae.md
source_content_sha256: 45ffcaa2cdeffaa76379f5509a23566fca717e3338c476f64bac8ab63166d167
translation_model: draft
translation_run: vi-draft-2026-10-31
translation_quality: draft
---

⟦folio 14⟧

A. Chân trang

Tín hiệu, đồ thị và các vị vua trên hình xuyến

Sáng hôm sau Melefon hú lên! Tôi nhảy lên, cởi quần áo, chộp lấy mrubka và kritsa của mình:
- Tôi đang nghe đây!
Và từ lỗ ở đáp số:
- Sao cậu lại càu nhàu?
- Làm sao tôi càu nhàu được? “Tôi không càu nhàu,” tôi nói.
- Đừng càu nhàu nữa! Nói như một con người! - Mishka hét lên.
- Tôi nói theo kiểu con người. Tại sao càu nhàu?
- Làm phiền tôi thế là đủ rồi!
Tuy nhiên, tôi sẽ không tin rằng chúng ta đã nhốt một con lợn con vào phòng.

N. Nosov. Điện thoại

Khi hai người đang trò chuyện dị hình, lời nói của mỗi người thường khá rõ ràng đối với người đối thoại. Ít khi hỏi lại và làm rõ những từ chưa rõ ràng. Nếu cùng một cuộc trò chuyện được thực hiện qua điện thoại thì tùy thuộc vào chất lượng kết nối, những từ không rõ ràng sẽ xuất hiện thường xuyên hơn, đôi khi khiến bạn rất khó hiểu. Nếu chúng ta cố gắng truyền qua điện thoại những từ không có ý nghĩa mà chỉ đơn giản là một chuỗi các chữ cái, đại loại như ritffsklaaaam...,

thì hóa ra một số chữ cái thường bị nhầm lẫn, ví dụ “f” và “s”, “b” và “g”, v.v.

Nó làm biến dạng tín hiệu từ hầu hết mọi phương thức liên lạc, có thể là điện thoại, radio, ống nhòm. Có nhiều cách khác nhau để chống lại hiện tượng này nhưng đều làm giảm hiệu quả giao tiếp. Ví dụ: qua điện thoại, bạn có thể truyền không phải các chữ cái riêng lẻ mà là các từ được kết nối: “b” là “Boris”, “g” là “Gregory”, v.v. - nhưng sau đó cùng với một chữ cái, chúng ta sẽ phải truyền 5-8. Có thể lặp lại từng tín hiệu nhiều lần, chẳng hạn như bức ảnh đầu tiên về phía xa của Mặt trăng được truyền tới Trái đất vào năm 1959, nhưng sẽ mất cùng một khoảng thời gian. Ghi chú này khám phá một cách hiệu quả về mặt chi phí để chống lại hiện tượng méo tín hiệu trong quá trình truyền*). Ý tưởng của phương pháp này rất đơn giản: nếu chúng ta đã biết tín hiệu nào có thể bị nhầm lẫn với tín hiệu nào, thì chúng ta sẽ chỉ truyền một tín hiệu từ mỗi nhóm như vậy và từ chối phần còn lại. Ví dụ: trên điện thoại, từ các âm “f”, “s”, “sh” - chỉ có âm “s”.

*) Những câu hỏi này lần đầu tiên được nghiên cứu bởi nhà điều khiển học người Mỹ (tên khai sinh là người Pháp) Claude Shannon.

⟦folio 15⟧

Đồ thị lỗi

Mỗi tin nhắn thường bao gồm các tín hiệu “cơ bản” riêng biệt: từ ngữ (trong cuộc trò chuyện qua điện thoại), chữ cái (trong tín hiệu cờ hàng hải “semaphore”) hoặc các dấu hiệu khác (dấu chấm và gõ trên điện thoại). Đặt các phần tử tín hiệu này tạo thành tập hợp $S$—bảng chữ cái đầu vào. Chúng ta hãy chọn từng tín hiệu từ $S$ dưới dạng một vòng tròn và kết nối một cặp vòng tròn với một đoạn (“cạnh”) nếu các tín hiệu tương ứng trong quá trình truyền có thể bị nhầm lẫn với nhau. Kết quả là một đồ thị $^*$ có ​​tập hợp các đỉnh $S$. Hãy gọi nó là biểu đồ lỗi của thiết bị truyền phát của chúng ta.

Hãy đưa ra một ví dụ. Kim phút của đồng hồ điện thay đổi vị trí đầu tiên ngay khi phút tiếp theo kết thúc, kim chuyển sang phút tiếp theo. Nếu chiếc đồng hồ này ở xa chúng ta hơn thì chúng ta không thể xác định chính xác vị trí của kim phút. Nhưng chúng ta hãy luôn sai lầm, không nhiều lắm - không quá một phút. khi đó bảng chữ cái đầu vào sẽ chứa 60 phần tử - 60 vị trí có thể có của kim phút (mỗi vị trí tương ứng với một điểm trên đường tròn - ranh giới của mặt số) và đồ thị sai số $\Gamma$ sẽ là 60-giác thông thường - điểm được nối bằng các đoạn thẳng với hai lân cận.

Bây giờ chúng ta hãy thử tìm hiểu xem cần phải làm gì để chúng ta có thể nhận biết chính xác số chỉ số trên kim phút. Chúng ta chuyền đồng hồ sao cho kim phút cứ 2 phút lại nhảy, tức là đồng hồ chỉ hiển thị số phút chẵn. thì không có dấu hiệu nào hiển thị cho chúng tôi có thể bị nhầm lẫn với bất kỳ dấu hiệu nào khác - xét cho cùng, chúng tôi không cho phép sai sót từ 2 phút trở lên. Như vậy, nếu nhận thấy tập tín hiệu truyền đi chỉ có 30 số chẵn từ 0 đến 58 thì tất cả đều được xác định chính xác. Mặt khác, điều rất quan trọng là 30 là giá trị tối đa: nếu trong biểu đồ $\Gamma$ chúng ta lấy 31 đỉnh trở lên, thì bằng cách nào đó, hai trong số chúng chắc chắn sẽ được kết nối (chứng minh điều đó!).

Trong ví dụ này, chúng tôi đã xây dựng một tập hợp $M$ các đỉnh đồ thị có thuộc tính sau: bất kỳ hai đỉnh nào từ $M$ không được nối bằng một cạnh. Tập hợp $M$ như vậy được gọi là tập hợp độc lập (I.S.). Trong ví dụ của chúng tôi, mọi bộ kim phút bốn phút đều độc lập, ví dụ: {2, 8, 34, 52, 56} hoặc một tập hợp số đọc chia hết cho 5: {0, 5, 10, ..., 55}.

Nếu các đỉnh $M$ của một đồ thị $G$ nhất định chứa nhiều đỉnh nhất trong số tất cả $M$ của nó, thì nó được gọi là tập độc lập nhất (n.i.s.) và số $\alpha(G)$ các đỉnh trong đó được gọi là số độc lập nhất (n.i.) của đồ thị $G$.

Trong cuộc thảo luận ở trên, biểu đồ $\Gamma$ có nhiều $M$ và $H, N, M$ khác nhau. - chỉ hai (một bộ bốn số từ 0 đến 58 và một bộ bốn số từ 1 đến 59) và $\alpha(\Gamma) = 30$.

Nếu đồ thị $G$ là đồ thị lỗi của một thiết bị phát $A$ nào đó, thì $\alpha(G)$ là số lượng tín hiệu khác nhau tối đa có thể được truyền qua thiết bị này mà không bị nhầm lẫn. Vì vậy, $\alpha(G)$ còn được gọi là thông lượng của thiết bị $A$.

⟦folio 16⟧

Bảng chữ cái vuông

Với mỗi thiết bị truyền $A$, chúng tôi đã liên kết bảng chữ cái đầu vào $S$, biểu đồ lỗi $G$ và số độc lập của biểu đồ $G$ (thông lượng của thiết bị $A$) $\alpha(G)$. Nhưng điều gì sẽ xảy ra nếu thiết bị $A$ được đặt một lần và mãi mãi và dung lượng của nó không đủ cho chúng ta? Giả sử, nếu $A$ - số điện thoại được truyền bằng thư điện thoại? Giải pháp đã được biết - đây là mã Morse: bạn cần truyền các gói gồm nhiều ký tự (dấu chấm - loại) qua $A$ và đếm mỗi gói như vậy là một tín hiệu.

Đầu tiên, hãy thử truyền hai tín hiệu liên tiếp từ $S$ qua cùng một thiết bị $A$. Hãy xem các thành phần của bất kỳ bảng chữ cái nào tăng lên bao nhiêu (chúng ta sẽ gọi chúng là các chữ cái).

Hãy thử xác định thông lượng của thiết bị $A^2$. Để làm được điều này, trước hết bạn cần xây dựng một biểu đồ lỗi, ký hiệu là $G^2$. Hãy xem trong những điều kiện nào thì tín hiệu $(v_1; v_2)$ có ​​thể bị nhầm lẫn với tín hiệu $(w_1; w_2)$. Rõ ràng, để điều này xảy ra, phải đáp ứng một trong ba điều kiện sau:

a) $v_1 = w_1$, $v_2 \sim w_2$;
b) $v_1 \sim w_1$, $v_2 = w_2$;
c) $v_1 \sim w_1$, $v_2 \sim w_2$.

Do đó, các đỉnh $(v_1; v_2)$ và $(w_1; w_2)$ của đồ thị $G^2$ được nối với nhau bằng một cạnh nếu đồ thị $G$ chứa các cạnh $v_1 - w_1$ (hoặc $v_1 = w_1$) và $v_2 - w_2$ (hoặc $v_2 = w_2$). Ví dụ: nếu đồ thị $G$ chỉ chứa hai đỉnh được nối với nhau bằng một cạnh thì $G^2$ là hình vuông có các đường chéo (Hình 2).

Nhiệm vụ 3. Xây dựng đồ thị $G^2$ cho mỗi đồ thị $G$ như trong Hình 3.

Do đó, chúng ta có thể coi $G^2$ là một đồ thị “phân lớp”: mỗi lớp dọc hoặc ngang của nó trùng với $G$ và mỗi cạnh $a - b$ của đồ thị $G$ tương ứng với một hình vuông có các đường chéo trong đồ thị $G^2$.

Hãy thử tìm một số tập hợp độc lập trong biểu đồ $G^2$.

Cho tập $M$ độc lập trong đồ thị $G$. Điều này có nghĩa là các phần tử từ $M$ không bị nhầm lẫn với nhau khi truyền qua thiết bị $A$. Sau đó, khi truyền các cặp chữ cái từ $M$, không có chữ cái nào trong số này bị biến dạng, do đó trong bảng chữ cái $S^2$ các phần tử có dạng $(a; b)$, trong đó $a \in M$, $b \in M$ không bị nhầm lẫn với nhau. Tập hợp các cặp $(a; b)$, trong đó $a \in M$, $b \in M$, được biểu thị bằng ký hiệu $M^2$. Dễ dàng nhận thấy rằng nếu $p$ là số phần tử của $M$ thì số phần tử của tập hợp $M^2$ là $p^2$. Do đó, thông lượng của thiết bị $A^2$ ít nhất bằng bình phương thông lượng của thiết bị $A$, tức là trong ngôn ngữ đồ thị

$$\alpha(G^2) \geqslant (\alpha(G))^2.$$

Tuy nhiên, xin lưu ý rằng việc tăng thông lượng như vậy không phải là vô ích - tốc độ truyền tín hiệu giảm một nửa.

Trên thực tế, các bức thư được truyền đi qua điện thoại hơi khác một chút. Về nguyên tắc, đối với tất cả 33 chữ cái trong bảng chữ cái, cần có bộ 6 ký tự (bộ 5 ký tự là không đủ), nhưng không chỉ chính xác

⟦folio 17⟧

Các vị vua trên hình xuyến

Hãy làm phức tạp biểu đồ $G_5$ của Hình 3 một chút: hãy dán các điểm 0 và $n$. Kết quả sẽ là $n$-gon 012 ... $(n-1)$. Chúng ta hãy biểu thị biểu đồ này bằng $P_n$. Hình vuông $P_n^2$ của nó sẽ thu được từ hình vuông của đoạn thẳng nếu hai cạnh ngang và hai cạnh dọc được dán lại với nhau thành từng cặp. Nhưng một đoạn hình vuông là một hình vuông thực sự, và nếu bạn dán các cạnh đối diện của nó lại với nhau, bạn sẽ có một hình xuyến! Chính xác hơn, một lưới trên hình xuyến chứa $n^2$ hình vuông $1 \times 1$ có đường chéo (Hình 4).

Nếu các đỉnh của các ô vuông này được đặt sang một bên với các ô của đường chân trời của bàn cờ có kích thước $n \times n$, thì các trường bàn cờ lân cận theo nghĩa cờ vua hóa ra được kết nối bằng các đoạn của lưới, hoặc, giống nhau, bằng các cạnh của biểu đồ $P_n^2$, và bài toán $M415$ về số lượng vua không lân cận tối đa trên hình xuyến sẽ biến thành bài toán định nghĩa về tính độc lập số của đồ thị $P_n^2$. lời giải của cô ấy được đưa ra trong số tạp chí này (xem trang 37).

Nếu bạn muốn hình dung rõ ràng hơn về cấu trúc của n. N. m. đồ thị $P_n^2$, hãy giải bài toán sau.

Bài 4. Cho tập $M$ là n. N. m. đồ thị $P_n^2$ (hoặc, tương tự, đường chân trời của bảng $n \times n$). Chứng minh rằng

a) nếu $n=2s$, thì $M_1^2$, trong đó $M_1$ là một số n. N. m. $P_n$, là n. N. m., và $\alpha(P_2s^2) = s^2$;

⟦folio 18⟧

6) nếu $n=4s+1$ thì trên mỗi hàng dọc và mỗi hàng ngang của bảng sẽ có chính xác $s=\left[\frac{n}{4}\right]$ điểm (vua) từ $M$ (ở đây $[a]$ là phần nguyên của số $a$);
c) nếu $n=4s+3$ thì trên mỗi hàng dọc và mỗi hàng ngang của bảng sẽ có các điểm $s$ hoặc $s+1$ từ $M$.

Bài toán 5. Chúng ta sẽ biểu diễn đồ thị $P_2^2$ (hình xuyến) dưới dạng hình vuông, nhớ rằng các cạnh đối diện của nó được dán lại với nhau. Thuộc tính tuần hoàn của đồ thị $P_n^2$ là ánh xạ "chuyển song song", trong đó phần tử (0; 0) chuyển sang $(s; t)$.

Chứng minh rằng mọi n. N. Đồ thị $M$ $P_2^2$ có thể được rút gọn về dạng như trong Hình 5 nếu chúng ta giải quyết dv tuần hoàn của đồ thị bảng và mối quan hệ đối xứng của đường chéo, chiều dọc và chiều ngang của hình vuông.

Ghi chú. Sự đối xứng theo đường chéo (0; 0) $(n-1; n-1)$ của hình vuông có thể được viết bằng công thức $(x; y) \rightarrow (y; x)$. CDviz tuần hoàn có thể được viết như sau: $(x, y) \rightarrow (x+s; y+t)$, nhưng sẽ có một điểm thiếu chính xác trong công thức này. Tôi muốn đặt các số $n$ và $0$, $h+1$ và $1$, v.v. sang một bên. Để làm điều này, các biểu tượng $\equiv$ và $(mod n)$ được sử dụng. Họ nói rằng $a$ có thể so sánh với $b$ modulo $n$ và viết $a \equiv b$ $(mod n)$ nếu $a$ và $b$ khi chia cho $n$ cho số dư bằng nhau. Chúng ta hãy biểu thị bằng $a$ $(mod n)$ phần dư của phép chia $a$ cho $n$. Sau đó, chúng ta có thể nói rằng phần tử $(x; y)$ đi vào phần tử $((x+s) (mod n); (y+t) (mod n))$ dưới sự biến đổi tuần hoàn của đồ thị và khi được đặt đối với đường thẳng $x=a$ - vào phần tử $(2a-x) (mod n); y)$.

Hình 6.

Tất cả những gì được biết

Hãy thử các điều kiện khác cho bộ máy truyền tin của chúng ta; Hãy xây dựng bộ máy $A^k$, trong đó $k$ là một số tự nhiên. Điều này có nghĩa là với sự trợ giúp của máy $A$, chúng tôi sẽ truyền các gói chữ cái $k$, mỗi chữ cái được lấy từ bảng chữ cái đầu vào ban đầu $S$.

Bằng cách tương tự với các tín hiệu hai chữ cái, có thể dễ dàng xây dựng biểu đồ $G^k$ lỗi máy $A^k$. Tập đỉnh của nó là bảng chữ cái $S^k$, bao gồm tất cả các bộ chữ cái có thể có độ dài $k$: $(v_1; v_2; ...; v_k)$, trong đó tất cả $v_i$ được lấy từ bảng chữ cái $S$. Không khó để xây dựng các cạnh trong biểu đồ $G^k$, nghĩa là hiểu được tín hiệu nào $(v_1; v_2; ...; v_k)$ và $(w_1; w_2; ..., w_k)$ có thể bị nhầm lẫn. Để làm điều này, các chữ cái của mỗi tọa độ phải được trộn lẫn với nhau, nghĩa là đối với mỗi $i$ $(1 \leq i \leq k)$, chúng phải đáp ứng một trong hai điều kiện: $v_i = w_i$ hoặc $v_i \sim w_i$ (nếu $v_i = w_i$ cho mỗi $i$, thì các bộ này trùng khớp).

Việc xác định giá trị chính xác của thông lượng thiết bị $A^k$ trong trường hợp chung là khá khó khăn nhưng có thể ước tính từ bên dưới.

Bài toán 6. Chứng minh rằng $\alpha(G^k) \geqslant (\alpha(G))^k$.

Và xa hơn... Ngay cả trong một trong những trường hợp đơn giản nhất, khi biểu đồ lỗi là $n$-gon $P_n$, người ta biết rất ít về $\alpha(P_n^k)$. Tất cả những gì được biết đến từ văn học bây giờ sẽ được kể.

Bàn cờ toric có kích thước $n \times n$ còn được gọi là dịch bệnh hai chiều. Tương tự, bậc $k$-thứ của $n$-gon (đồ thị $P_n^k$) có thể được gọi là mora chiều $k$ từ phía $n$. Ver-

⟦folio 19⟧

Hình 7.

Các bus biểu đồ $P^k_n$ có thể được vẽ bằng một tập hợp các số nguyên $k$: $(x_1; x_2; \dots; x_k)$, trong đó mỗi số $x_i$ nằm trong khoảng từ 0 đến $n-1$.

Bài 7. Xác định số đỉnh của đồ thị $P^k_n$.

Theo định nghĩa, hai bộ $(x_1; x_2; \dots; x_k)$ và $(y_1; y_2; \dots; y_k)$ liền kề nhau trong biểu đồ $P^k_n$ nếu trong $n$-gon, mỗi cặp tọa độ $x_i, y_i$ là lân cận, nghĩa là đối với mỗi giá trị của tọa độ $i$ khác nhau không quá một: $|x_i - y_i| \equiv h_i$ (mod $n$) $\in \{0, 1\}$ cho tất cả $i$ từ 1 đến $k$ (ví dụ: trong Hình 6 cho trường hợp $k=3, n=5$ các hàng xóm của tập hợp (0; 1; 2) được đánh dấu).

Nhiệm vụ 8. Xác định số lượng lân cận của mỗi đỉnh của hình tora $k$ chiều.

Bài 9. Chứng minh rằng

$$\alpha(P^k_n) \leq \left[ \left( \frac{n}{2} \right)^k \right].$$

Bài tập 10. Xác định $\alpha(P^k_n)$ nếu $n$ là số chẵn.

Đối với $n$ lẻ, ước tính sau đúng:

$$\left( \frac{n-1}{2} \right)^k \leq \alpha(P^k_n) \leq \left[ \left( \frac{n}{2} \right)^k \right],$$

và đôi khi giá trị chính xác của $\alpha(P^k_n)$ được biết.

Định lý. Nếu $n-1$ chia hết cho $2^k$ thì

$$\alpha(P^k_n) = \frac{n-1}{2^k} \cdot n^{k-1}.$$

Chứng minh đầy đủ của định lý này khá dài nên chúng ta sẽ chỉ trình bày cách định nghĩa một tập hợp độc lập với số phần tử như vậy. Đối với mỗi bộ tọa độ $(x_1; x_2; \dots; x_{k-1})$ đầu tiên $k-1$, chúng ta thu được các giá trị $r = \frac{n-1}{2^k}$ ​​của tọa độ $k$-th:

$$x_k \equiv 2l + r(2^{k-1}x_1 + 2^{k-2}x_2 + \dots + 2^1x_{k-1}) \pmod n.$$

Ở đây $l$ là số nguyên bất kỳ từ 0 đến $r-1$.

Nếu trong trường hợp $k=2$ bạn vẽ tập hợp các đỉnh có tọa độ được cho bởi công thức cuối cùng, thì bạn nhận được đáp số đã cho. M415 với $n-1$ chia cho 4.

Những kết quả này cho phép chúng tôi xây dựng một bảng gồm các giá trị $\alpha(P^k_n)$ ​​(Hình 7).

Trong đó, một số con số được lấy về mặt lý thuyết và phần còn lại được lấy bằng máy tính. Bạn thấy rằng khi $k$ và $n$ lớn lên, ngày càng có nhiều khoảng trống.

Có thể một số bạn sẽ điền vào chỗ trống trong bảng này và quyết định bài toán về việc xác định dung lượng truyền tải của các thiết bị?
