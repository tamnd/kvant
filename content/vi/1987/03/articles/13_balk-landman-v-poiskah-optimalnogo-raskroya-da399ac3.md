---
id: 1987-3-balk-landman-v-poiskah-optimalnogo-raskroya-da399ac3
issue: kvant_1987_3
year: 1987
number: "3"
title: Tìm kiếm phương pháp cắt tối ưu
authors:
  - Балк М. Б.
  - Ландман Г. М.
rubric: matematicheskiy-kruzhok
rubric_sub: Математический кружок
page_first: 46
page_last: 50
page_labels: 44-48
tag: S9UN
lang: vi
source: kvant_digital
extraction: vision
content_sha256: 841d6e7e854df43effc2137786c01dca0e85fc6767af3839feb7e2abf492fb5a
prompt_sha256: draft-1
translated_from: content/ru/1987/03/articles/13_balk-landman-v-poiskah-optimalnogo-raskroya-da399ac3.md
source_content_sha256: aaf5de8e8693f6f5ea2eaeb1c50ed7f0fd712b82a90de9c998703d44ffb483f5
translation_model: draft
translation_run: vi-draft-2026-10-31
translation_quality: draft
---

⟦folio 44⟧

Cắt tối ưu bằng tiếng Nhật

Ứng viên Khoa học Vật lý và Toán học
M. V. VALK,
G.M.LANDMAN

Nhà máy sản xuất đồ chơi trẻ em có mặt để sản xuất hàng loạt một sản phẩm mới, một trong những bộ phận của sản phẩm đó là một đa giác nhỏ xác định hình dạng và kích thước (hình 1) làm bằng thiếc mỏng. Nhà máy có một chiếc máy có thể cắt các hình chữ nhật có kích thước bất kỳ một cách dễ dàng và nhanh chóng từ một tấm thiếc. Do đó, nó đã được chấp nhận về mặt kỹ thuật lời giải: đầu tiên cắt các khoảng trống hình chữ nhật giống hệt nhau với kích thước phù hợp, sau đó cắt từng mảnh hình chữ nhật đó để thu được phần đa giác cần thiết từ nó. Và tất nhiên, kích thước của các hình chữ nhật phải được chọn sao cho lượng lãng phí cho việc trang trí là tối thiểu. Đây là cách nảy sinh toán học bài toán, về lời giải mà chúng ta sẽ thảo luận trong bài viết này.

Chính bài toán. Chỉ định một thuật toán cho phép, trong số tất cả các hình chữ nhật P, cùng chứa đa giác M đã cho, chọn hình có diện tích nhỏ nhất.

Chúng ta sẽ gọi một hình chữ nhật thỏa mãn điều kiện này là bài toán tối ưu. Nếu bất kỳ hình chữ nhật nào tự nó là đa giác M và không có một đỉnh nào của đa giác trên đường viền của hình chữ nhật, thì bạn có thể làm phẳng hình chữ nhật đó, nghĩa là thay thế nó bằng một hình chữ nhật khác có diện tích nhỏ hơn, cũng chứa đa giác M. Để làm điều này, chỉ cần dịch song song với chính nó từng đường trong số bốn đường thẳng chứa các cạnh của hình chữ nhật M sao cho chúng (sau khi thay đổi) đã đi qua một số đỉnh của đa giác M. Tại hình 1, chẳng hạn a hình chữ nhật “cải tiến” (so với P) là P′.

Theo thông lệ, người ta gọi đường hỗ trợ cho một đa giác M nhất định là bất kỳ đường nào chứa ít nhất một điểm trên đường viền của đa giác và không chứa bất kỳ điểm bên trong nào của nó (ví dụ: trên hình 1 đường a và b là các đường hỗ trợ cho đa giác M và đường c không phải là đường hỗ trợ). Một hình chữ nhật có bốn cạnh nằm trên các đường hỗ trợ của đa giác M sẽ được gọi là ngoại tiếp quanh M. Như vậy

⟦folio 45⟧

Hình chữ nhật $\Pi'$ nằm trên hình 1. Ngay sau khi chúng tôi chọn đường tham chiếu $(a)$ cho đa giác đã cho $M$ (hình 1), do đó, chúng tôi đã xác định duy nhất hình chữ nhật được mô tả xung quanh $M$. Hình chữ nhật được mô tả xung quanh $M$ rõ ràng có đặc tính là có thể đặt ít nhất một đỉnh của đa giác (hình 1) trên mỗi cạnh của nó (có thể ở cuối của nó). Trong số hai hình chữ nhật được mô tả xung quanh một đa giác nhất định $M$, chúng tôi sẽ gọi hình chữ nhật có diện tích shifu nhỏ hơn là hình tốt nhất. Hình chữ nhật tối ưu, được thảo luận ở phần chính bài toán, rõ ràng nên được tìm kiếm trong số các hình chữ nhật được mô tả xung quanh $M$.

Các nhà công nghệ thực vật đưa ra hai giả thuyết:

Giả thuyết I. Hình chữ nhật tối ưu cho đa giác $M$ là hình chữ nhật được mô tả trong đó một cạnh chứa cạnh phân kỳ nhất của đa giác.

Giả thuyết II. Hình chữ nhật tối ưu là hình chữ nhật được mô tả trong đó một cạnh song song với điểm rộng nhất của đa giác.

Ở giai đoạn này bài toán toán học đã được cung cấp.

Nhà toán học bắt đầu từ đâu?

Matematik bắt đầu bằng một câu hỏi dường như hoàn toàn không thú vị và ít ý nghĩa: "Hình chữ nhật tối ưu có cần thiết không?"

Chúng ta hãy chọn một số điểm $O$ trên mặt phẳng và vẽ trục $l_0$ (hình 2a) qua điểm đó. Sau đó, chúng ta vẽ một tia tùy ý $l = l_\varphi$ qua $O$ và làm trống nó tạo thành một góc $\varphi$ với trục $l_0$. Chúng ta có thể dựng cho đa giác $M$ một đường tham chiếu song song với tia $l$, và sau đó là hình chữ nhật ngoại tiếp (đồng nhất) $P$, hai cạnh của nó song song với tia $l$; Hãy biểu thị diện tích của nó bằng $S(\varphi)$. Chúng ta sẽ thay đổi góc $\varphi$; trống góc này tăng từ 0 lên $\pi$; trong trường hợp này, hình chữ nhật $P$ cũng sẽ thay đổi và chúng ta sẽ thu được tất cả các hình chữ nhật có thể có được mô tả xung quanh $M$; $S$ cũng sẽ liên tục thay đổi (tức là chỉ cần một thay đổi nhỏ ở góc $\varphi$ thì giá trị $S(\varphi)$ cũng sẽ thay đổi ít). Nhưng một hàm liên tục trên một phân đoạn nhất định (trong trường hợp của chúng tôi, trên phân đoạn [0; $\pi$]) phải nhận một số (ít nhất một) giá trị $\varphi$ từ phân đoạn này giá trị tối thiểu của nó (“Đại số và Nguyên tắc Phân tích 9-10”, trang 89). Điều này có nghĩa là có một góc $\varphi$ sao cho hình chữ nhật tương ứng được mô tả xung quanh $M$ sẽ có diện tích nhỏ nhất có thể (sẽ là tối ưu). Nói cách khác, trong số các hình chữ nhật được mô tả xung quanh đa giác $M$, gọi ở đó (ít nhất một) là tối ưu.

Sau khi xác minh sự tồn tại của lời giải, nhà toán học bắt đầu tìm kiếm nó.

Hãy xem xét một đa giác tùy ý - không lồi hoặc lồi. Hãy lắng nghe một đa giác không lồi, tuy nhiên, có thể dễ dàng áp dụng các tính chất cho trường hợp đa giác lồi. Thật vậy, $M$ trống là đa giác không lồi. Xét đa giác lồi nhỏ nhất $M'$ chứa đa giác $M$ ($M'$ được gọi là bao lồi của đa giác $M$, hình 26). Dễ hiểu là hình chữ nhật $P$ chứa đa giác $M$ khi và chỉ nếu nó chứa bao lồi $M'$ của nó. Do đó, bài toán để tìm hình chữ nhật tối ưu cho đa giác $M$ tương đương với bài toán tương tự cho đa giác lồi $M'$.

Để loại bỏ nó, trước tiên hãy thử trong trường hợp đặc biệt đơn giản nhất, khi $M$ là một hình tam giác.

Lời giải bài toán cho hình tam giác

Đặt $M$ là hình tam giác $ABC$ và $P$ là một số hình chữ nhật được mô tả xung quanh $M$. Phải có ít nhất một đỉnh tam giác ở mỗi cạnh trong bốn cạnh của hình chữ nhật. Do đó, ít nhất một đỉnh của tam giác “phục vụ” hai

⟦folio 46⟧

các cạnh của hình chữ nhật $\Pi$, là đầu chung của chúng. Tuy nhiên, hai đỉnh còn lại có thể nằm khác nhau trên các cạnh (hoặc bên trong) của hình chữ nhật và có thể có 4 trường hợp khác nhau về cơ bản (hình 3, $a-ε$) tùy thuộc vào vị trí của chúng.

Chúng ta hãy biểu thị diện tích của hình tam giác $ABC$ bằng $\sigma$ và $S$ diện tích của hình chữ nhật $\Pi$.

Trong trường hợp $\sigma$ rõ ràng chúng ta có: $S=2\sigma$.
Trong trường hợp $\varepsilon$ và $\varepsilon$): $S>2\sigma$.

Tình huống trong trường hợp $a$) là gì? Chúng ta hãy vẽ một đường song song qua $B$ với cạnh $AK$ của hình chữ nhật và đánh dấu các điểm $F$ và $D$ giao nhau của nó với cạnh của tam giác và cạnh của hình chữ nhật. Sau đó
$$S=S_{AKBD}+S_{BDNL}>2S_{BFA}+2S_{BFC}=2\sigma,$$
tức là $S>2\sigma$.

Chúng ta thấy rằng hình chữ nhật tối ưu chỉ xuất hiện trong trường hợp $\sigma$). Do đó, trong số các hình chữ nhật được mô tả có chứa một hình tam giác cho trước $M$, hình chữ nhật tối ưu là hình có đáy trùng với cạnh của tam giác; trong trường hợp này, diện tích đầu vào hình chữ nhật tối ưu lớn hơn diện tích hình tam giác. Rõ ràng là nếu một hình tam giác tù thì chỉ có một hình chữ nhật tối ưu như vậy. Trong trường hợp tam giác nhọn, có ba hình chữ nhật tối ưu. Cũng có thể có hai hình chữ nhật tối ưu (ví dụ: nếu hình tam giác là hình chữ nhật).

Thuật toán để có được hình chữ nhật tối ưu là rất phức tạp.

Nhưng còn tứ giác thì sao?

Phương pháp lời giải được thảo luận ở trên đơn giản đến mức bạn thậm chí không cần phải tìm kiếm một phương pháp khác. Trong khi đó, phương pháp của chúng tôi có một nhược điểm lớn: nó không chuyển sang trường hợp đa giác có nhiều hơn ba cạnh. Do đó, hãy ước tính xem cách tiếp cận nào khác hứa hẹn hơn - trong trường hợp tam giác - có thể đưa chúng ta đến lời giải. Trong trường hợp $a$), chúng ta có thể tính tổng diện tích của các hình tam giác bị cắt (chúng ta ký hiệu là $T$), biểu thị nó qua góc $t$ (góc nghiêng của cạnh tam giác $AB$ với đường tham chiếu $AK$) và thông qua các phần tử của tam giác; có thể chứng minh rằng tổng này có dạng
$$T=T(t)=A_1\sin 2t+A_2\sin(2t+\theta_2)+A_3\sin(2t+\theta_3),$$
trong đó $A_1, A_2, A_3, \theta_2, \theta_3$ là một số số không phụ thuộc vào $t$ (mà chỉ phụ thuộc vào các phần tử của tam giác $ABC$). Sau đó, chúng tôi có thể cố gắng loại bỏ các giá trị $t$ mà tổng này hoàn thành không có giá trị tối thiểu. Phương pháp này trong trường hợp hình tam giác có vẻ cồng kềnh một cách vô lý, nhưng trong trường hợp hình tứ giác và các đa giác khác, nó dẫn đến lời giải - và, hóa ra, không quá khó.

Chúng ta hãy tạo dưới dạng bài toán hai sự kiện đơn giản mà chúng ta sẽ cần sau này (lời giải - bằng một trong các số sau).

Bài 1. Mỗi tổng dạng
$$T(t)=A_1\sin(2t+\theta_1)+A_2\sin(2t+\theta_2)+\dots+A_m\sin(2t+\theta_m)$$
luôn có thể được ghi nhớ
$$T(t)=\rho\sin(2t+\theta),$$
(1)
trong đó $\rho \geq 0$ và các số $\rho$ và $\theta$ chỉ phụ thuộc vào các số $A_1, \dots, A_m, \theta_1, \dots, \theta_m$ (nhưng không phụ thuộc vào $t$).

Nhiệm vụ 2. Nếu với tất cả các giá trị $t$ từ tích phân nào đó có dạng $(t_0-\varepsilon; t_0+\varepsilon)$ (không bao gồm các đầu) thì hàm $\sin(2t+\theta)$ không âm, thì có một giá trị $t_1$ trên tích phân này sao cho bất đẳng thức nghiêm ngặt là đúng:
$$\sin(2t_1+\theta)<\sin(2t+0).$$
(2)

Trường hợp $n$-gon tùy ý

Cho $M$ là một lồi tùy ý $n$-gon ($n \geq 4$) và $\Pi_0$ là một

⟦folio 47⟧

Ai đó mô tả về anh ta là một hình chữ nhật. Đầu tiên, hãy xem xét những trường hợp khi không có cạnh nào của đa giác $M$ nằm trên cạnh của hình chữ nhật $\Pi_0$. Với yêu cầu này, không được có quá bốn đỉnh của đa giác $M$ trên đường viền của hình chữ nhật $\Pi_0$. Trong trường hợp này, có thể có ba tùy chọn sau:

I. Hai đỉnh của đa giác $M$ đóng vai trò là hai đầu đường chéo của hình chữ nhật $\Pi_0$ và các đỉnh còn lại $M$ - bên trong $\Pi_0$, hình 4, a).

II. Một đỉnh của đa giác $M$ đóng vai trò là một đỉnh của hình chữ nhật $\Pi_0$, hai đỉnh của đa giác $M$ là các điểm trong của hai cạnh $\Pi_0$ và các đỉnh còn lại $M$ nằm bên trong $\Pi_0$, hình 4, c).

III. Một số đỉnh của đa giác $M$ là các điểm trong của bốn cạnh hình chữ nhật $\Pi_0$, các đỉnh còn lại của đa giác $M$ nằm bên trong $\Pi_0$, hình 4, c).

Tất cả ba tùy chọn đều được xem xét bằng cùng một phương pháp: diện tích của hình chữ nhật được mô tả được tính toán và tìm hiểu xem liệu có thể cải thiện nó bằng "chuyển động nhỏ" hay không, nghĩa là thu được hình chữ nhật được mô tả với diện tích nhỏ hơn; nếu điều đó là có thể thì hình chữ nhật $\Pi_0$ đang được xem xét là không tối ưu.*)

Chúng tôi sẽ xem xét ở đây tùy chọn I - đơn giản nhất. Chúng ta hãy biểu thị bằng $A$ và $C$ hai đỉnh $M$ đóng vai trò là hai đầu của đường chéo của hình chữ nhật được mô tả $\Pi_0$ ($F_0K_0L_0N_0$). Đặt $AB$ là cạnh của $M$ nằm bên trong $\Pi_0$ (trừ phần cuối $A$); chúng ta có thể giả định rằng $AB$ nằm trong $\triangle F_0K_0L_0$. Chúng ta hãy biểu thị các giá trị của góc $BAK_0$ bằng $t_0$, các giá trị của góc $CAB$ bằng $\lambda$. Chúng tôi tính diện tích $S_{\Pi_0}$:

$$S_{\Pi_0} = \frac{1}{2} AC^2 \sin (2t + 2\lambda).$$

Nhờ bài toán 2, có một góc $t$ trên khoảng $(t_0 - \varepsilon; t_0 + \varepsilon)$ sao cho $\sin (2t + 2\lambda) < \sin (2t_0 + 2\lambda)$, và do đó $S_{\Pi_0} < S_{\Pi_0}$. Điều này có nghĩa là hình chữ nhật $\Pi_0$, xuất hiện trong tùy chọn I, không tối ưu: nó có thể được “cải thiện”. Chúng tôi để lại cho người đọc việc phân tích hai trường hợp còn lại là bài toán.

Bài 3. Chứng minh ở đáp án III hình chữ nhật $\Pi_0$ không tối ưu.

Bài 4. Chứng minh ở đáp án II hình chữ nhật $\Pi_0$ không tối ưu.

Chúng ta thấy rằng cho đến nay hình chữ nhật được mô tả không chứa bất kỳ cạnh nào của đa giác $M$ (xem biến thể).

*) Để biết thêm chi tiết về ví dụ về “chuyển động nhỏ”, xem «Kvant», 1979, No. 4, p. 4 hoặc cuốn Balk M.V., Balk G.D. Poshk lời giải, M.: Văn học thiếu nhi, 1983, tr. 86.

Hình 4.

Hình 5.

⟦folio 48⟧

bạn I, II, III) thì không thể tối ưu được. Nhưng hình chữ nhật tối ưu, như chúng ta đã biết, vẫn tồn tại. Do đó, nhà toán học đã thu được thuật toán sau lời giải.

Thuật toán lời giải chính bài toán
1) Nếu $n$-gon $M$ cho trước là lồi thì hãy vẽ tất cả các hình chữ nhật ngoại tiếp chứa ít nhất một cạnh của đa giác (có nhiều nhất $n$ hình chữ nhật như vậy).
2) Tính diện tích của các hình chữ nhật này và chọn trong số các hình chữ nhật tất cả những hình chữ nhật có diện tích nhỏ nhất. Mỗi trong số chúng là một hình chữ nhật tối ưu cho $n$-gon đang được xem xét. Không có hình chữ nhật tối ưu nào khác.
3) Nếu đa giác $M$ không lồi thì trước tiên hãy xây dựng bao lồi $M'$ cho nó, sau đó tìm hình chữ nhật tối ưu cho đa giác $M'$ - đó cũng sẽ là hình chữ nhật tối ưu cho đa giác $M$.

Khi tiếng Nhật trở nên đơn giản hơn
Chúng ta đã thấy rằng việc tìm hình chữ nhật tối ưu cho một hình chữ nhật lồi $n$-gon $M$ cho trước bao gồm việc tìm kiếm qua nhiều nhất $n$ hình chữ nhật. Có những trường hợp quan trọng khi việc tìm kiếm này được đơn giản hóa. Chúng ta tạo chúng ở dạng bài toán. Ở đây cần lưu ý rằng một $n$-giác lồi, không phải hình chữ nhật, có không quá ba góc không tù (nếu không tổng các góc sẽ không bằng $180^\circ$ ($n-2$)).

Bài toán 5. Cho một số đa giác lồi $M$ chỉ có một cạnh có hai góc không tù kề nhau. Chứng minh rằng trong số các hình chữ nhật được mô tả xung quanh $M$ chỉ có một hình chữ nhật tối ưu - hình nhỏ nhất. Nếu một cái tồn tại, làm thế nào người ta có thể tìm thấy nó?

7. Giả sử $M$ là một lồi $n$-gon cho trước. Giả sử $\{A_1, A_2, \dots, A_k\}$ là tất cả các độ lồi có thể có của một $k$-giác với một góc cho trước $a_1, a_2, \dots, a_k$ ($a_1 + a_2 + \dots + a_k = (k-2)n$), được mô tả xung quanh $n$-giác $M$. Chứng minh rằng nếu trong số $k$-giác này có một cạnh có diện tích nhỏ nhất thì ít nhất một cạnh của nó chứa cạnh của $n$-giác $M$ (vì vậy không có $k$-giác nào tối ưu hơn $n$).
