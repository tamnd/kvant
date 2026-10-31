---
id: 1977-6-vasilev-tolpyigo-plavnyie-posledovatelnosti-bc4a87f0
issue: kvant_1977_6
year: 1977
number: "6"
title: Trình tự mượt mà
authors:
  - Васильев Н. Б.
  - Толпыго А. К.
rubric: osnovnye-stati
page_first: 32
page_last: 36
page_labels: 30-34
tag: 8MQ9
lang: vi
source: kvant_digital
extraction: vision
content_sha256: fab1d1b9e26cc98464790cce0aa57da04191230c1a2cc87ceecb79abdbf8718e
prompt_sha256: draft-1
translated_from: content/ru/1977/06/articles/07_vasilev-tolpyigo-plavnyie-posledovatelnosti-bc4a87f0.md
source_content_sha256: 9d92c6b8e941d2b2e140b8e752b4ffb4dc45e547f08e53992ae3a77d246b92e6
translation_model: draft
translation_run: vi-draft-2026-10-31
translation_quality: draft
---

⟦folio 30⟧

Trình tự mượt mà

Trong ghi chú này, chúng ta sẽ thảo luận về các cân nhắc đặc trưng nảy sinh tại lời giải bài toán, trong đó một số phần tử mồ côi cục bộ được áp đặt cho một chuỗi hoặc hàm - không được phép thay đổi đột ngột hoặc xoay vòng tròn - và cần phải ước tính mức độ dao động nói chung có thể lớn đến mức nào.

Trò chơi đua xe và sự khác biệt thứ hai

Chắc hẳn nhiều độc giả của chúng ta đều biết đến trò chơi đua xe được mô tả trong cuốn sách của M. Gardner. “Tiểu thuyết toán học”.

Chúng ta hãy nhớ lại các quy tắc của trò chơi. Một vùng (rãnh) cong tùy ý ít nhiều được vẽ trên giấy ca-rô; ở một cạnh của đường đua, một điểm từ bánh tart được đặt cho mỗi người chơi và một đường φ và sha được đặt ở cạnh kia. Người lái xe lần lượt di chuyển đến một trong các nút lưới và chỉ một người được phép thay đổi tốc độ: nếu lần di chuyển trước đó là tự động $\overrightarrow{AB}$, thì lần di chuyển tiếp theo $\overrightarrow{BC}$ cũng giống hệt ($\overrightarrow{BC} = \overrightarrow{AB}$) hoặc kết thúc ở một trong các ký ức với các nút $C$. Bạn chỉ có thể đi dọc theo những đoạn nằm hoàn toàn trong đường đua: người “đi quá nhanh” và bay ra khỏi giới hạn sẽ bỏ qua một bước di chuyển và bắt đầu ở tốc độ đơn vị (bắt đầu được thực hiện theo cách tương tự, Hình 1).

So với các trò chơi trên giấy ca rô khác (ví dụ như trò chơi “bùng nổ trên biển”), trò chơi này đáng chú ý không chỉ vì sự gần gũi với tình hình thực tế -

qing, nhưng cũng đa dạng: xét cho cùng, mỗi bản nhạc mới đều là một trò chơi mới.

Tìm ra con đường thành công nhất trên một chặng đường khó khăn - bài toán không hề dễ dàng. bài toán như vậy rất đặc trưng của lý thuyết điều khiển tối ưu, một lĩnh vực toán học tương đối trẻ và đang phát triển nhanh chóng. Chúng tôi sẽ không đề cập đến các thông điệp chung liên quan đến lý thuyết này mà sẽ xem xét một bài toán cụ thể, dựa trên “cuộc đua” của trò chơi.

Bài toán 1. Trên giấy ca rô, trên một đường ngang của hạt $l$, một đoạn $A_0A_1$ có ​​độ dài 1 (cạnh của một hình vuông) được căn chỉnh. Điều cần thiết là bắt đầu từ emodog của phân khúc để xây dựng một đường dẫn trong đó:

1) mỗi bước tiếp theo $A_kA_{k+1}$ giống với bước trước $\overrightarrow{A_kA_{k+1}} = \overrightarrow{A_{k-1}A_k}$ hoặc khác nó một đơn vị về rhili ở i và z (không giống như “các cuộc đua”, tốc độ dịch chuyển sang phải luôn giữ nguyên: 1 ô cho mỗi bước);

2) đoạn cuối cùng $A_nA_{n+1}$ nằm trên cùng một đường cay như đoạn $A_0A_1$ đầu tiên.

Độ cao cao nhất cho trước $n$ mà đường hoa anh túc phía trên l cay có thể đạt tới là bao nhiêu?

Tất nhiên, bài toán này rất dễ tạo hình mà không cần giấy ca-rô. Nếu chúng ta giả sử rằng các đoạn $A_0A_1$ và $A_nA_{n+1}$ là các đoạn [0, 1] và [$n, n+1$] của trục $Ox$ (Hình 2), thì đường dẫn hoàn toàn

⟦folio 31⟧

không được xác định bởi dãy tọa độ $y_0, y_1, y_2, \dots, y_{n-1}, y_n, y_{n+1}$ của các điểm $A_k = (k; y_k)$ và dãy tọa độ này phải thỏa mãn các điều kiện sau:

a) sự khác biệt giữa sự khác biệt $y_{k+1} - y_k$ và $y_k - y_{k-1}$ của các thành viên lân cận của chuỗi, tức là sự khác biệt thứ hai
$$y_{k+1} - 2y_k + y_{k-1} = (y_{k+1} - y_k) - (y_k - y_{k-1})$$
đối với mỗi $k$, $1 \leq k \leq n$, không vượt quá 1;

6) $y_0 = y_1 = y_n = y_{n+1} = 0$ và tất cả $y_k$ khác đều là số nguyên. bài toán hỏi ý nghĩa nhất của trình tự này có thể là gì.

Đường đi được đề cập trong công thức đầu tiên, theo một nghĩa nào đó, là “đồ thị” của dãy $\{y_k\}$. Tiếp theo, chúng ta sẽ bắt đầu ngay với công thức đại số; sẽ rất hữu ích nếu “phát minh” ra nó: nó giúp tìm ra và trình bày ý nghĩa của điều kiện a).

Hãy chuyển sang lời giải bài toán.

Để thỏa mãn điều kiện 1), phần “đỉnh” của đường đứt nét $A_m A_{m+1}$ phải nằm ngang. Rõ ràng là chỉ có thể xem xét các đường đối xứng: nếu $A_m A_{m+1}$ là liên kết trên cùng, thì phần dài hơn của các phần $A_1 \dots A_m$ và $A_{m+1} \dots A_n$ có thể được rút ngắn bằng cách thay thế nó bằng sự phản xạ đối xứng của phần kia so với điểm giữa của đường vuông góc với đoạn $A_m A_{m+1}$.

Vì vậy, chỉ cần xem xét khu vực dọc theo làn khói là đủ (bằng cách phân bổ hơn $n/2 - 1$ bước nghiêng cho nó) - quá trình khởi động sẽ hoàn toàn giống nhau.

Nhân tiện, từ đây rõ ràng là đối với số chẵn $n$ chiều cao tăng tối đa - hãy ký hiệu là $h_n$ - sẽ giống như đối với số lẻ tiếp theo: $h_n = h_{n+1}$.

Nếu bạn tăng và giảm một góc $45^\circ$, thì chiều cao tối đa, để dễ kiểm tra, sẽ là $[n/2] - 1$. Nhưng phương pháp này sẽ chỉ hoạt động tối đa $n = 7$ (Hình 3, a). Hình 3b hiển thị đường dẫn cho $n = 8$, tăng lên độ cao 4 (không lên $[8/2] - 1 = 3$).

Các thông điệp đối xứng một lần nữa sẽ giúp chúng ta tìm ra con đường tối ưu. Rõ ràng là lúc đầu, việc tăng tốc độ đi lên càng nhiều càng tốt sẽ có lợi: $1 + 2 + 3 + \dots$; nhưng - để có thời gian đi chậm lại - việc này chỉ được thực hiện cho đến giữa đoạn đi lên [1; $m$] (Hình 4, 5).

Những tin nhắn này có thể được định dạng nghiêm ngặt như thế này. Hãy ước tính sự khác biệt giữa các phần đồng thời ở cả hai bên:

$$y_1 - y_0 = 0, \quad y_{m+1} - y_m = 0, \quad y_2 - y_1 \leq 1, \quad y_m - y_{m-1} \leq 1, \quad y_3 - y_2 \leq 2, \quad y_{m-1} - y_{m-2} \leq 2, \quad y_4 - y_3 \leq 3, \quad y_{m-2} - y_{m-3} \leq 3, \dots$$

Bây giờ, để có được ước tính về độ cao cao nhất $h_n$ của phần nhô lên, tức là giá trị $y_m - y_0 = y_{m+1} - y_0$, chúng ta cần cộng các ước tính về những khác biệt đầu tiên. Như vậy,

cho $n = 4k - 2$ (ví dụ: $n = 18$, Hình 4)

Hình 2.

Hình 3.

⟦folio 32⟧

$$h_n \leq 1 + 2 + \dots + (k - 1) + (k - 1) + \dots + 2 + 1 = k(k - 1);$$
cho $n = 4k$ (ví dụ: $n = 20$, Hình 5)

$$h_n \leq 1 + 2 + \dots + (k - 1) + k + (k - 1) + \dots + 2 + 1 = k(k - 1) + k = k^2.$$

Rõ ràng - từ những số liệu tương tự - rằng những ước tính này là chính xác, tức là chiều cao nâng như vậy có thể được thực hiện. Cụ thể là $h_{18} = 20, h_{20} = 25$.

Vì vậy, chúng tôi đã tìm thấy chiều cao cao nhất $h_n$ cho bất kỳ $n$ nào. Kiểm tra xem đáp số có ​​thể được viết ở dạng rút gọn này không: $h_n = [n/4] \times [(n + 2)/4]$, hoặc thậm chí ngắn hơn, $h_n = [[n/2]]^2/4$. (Hãy nhớ lại rằng $h_{n+1} = h_n$ đối với số chẵn $n$.) Do đó, đối với bất kỳ $n$ nào, ước tính trên đủ chính xác cho $h_n$ được cho bởi bất đẳng thức $h_n \leq n^2/16$.

Chúng ta cũng lưu ý rằng các đỉnh của quỹ đạo tối ưu trong mỗi phần thứ tư của nó nằm trên cùng một parabol. Điều này không xảy ra một cách tình cờ. Xét cho cùng, nếu dãy $x_0, x_1, \dots, x_m$ là một cấp số cộng (một phần là một đoạn của chuỗi tự nhiên) và dãy $y_0, y_1, \dots, y_m$ có hiệu giây bằng nhau $y_{k+1} - 2y_k + y_{k-1}$, thì các điểm $(x_0; y_0), (x_1; y_1), \dots, (x_m; y_m)$ nằm trên cùng một parabol*). Đây chính xác là tình huống trong trường hợp của chúng tôi (Hình 4, 5): trong quý đầu tiên và quý cuối cùng của quỹ đạo $y_{k+1} - 2y_k + y_k-1 = 2y_k + n^2/16$.

*) Thứ Tư. «Kvant», 1973, số 2, tr. 28-29.

$+y_{k-1} = 1$, và ở phần giữa $y_{k+1} - 2y_k + y_{k-1} = -1$.

Chúng ta sẽ thấy rằng trong các bài toán khác khi áp dụng các hạn chế đối với sai phân bậc hai, quỹ đạo tối ưu cũng được dán lại với nhau từ một parabol.

Phân tích liên tục.
Tốc độ và gia tốc

Bài toán 2. Thay thế điện trong nước tiểu $O$, bỏ qua tại chỗ, nhưng sau khi “đảo ngược”, sau $n$ giây nó lại quay trở lại trong nước tiểu $O$ và vẫn ở trong đó. Khoảng cách tối đa $h$ mà anh ta có thể di chuyển ra khỏi nước tiểu $O$ trong thời gian này là bao nhiêu, nếu giá trị tuyệt đối của gia tốc của anh ta không bao giờ vượt quá một cm/giây$^2$?

bài toán này là một phân tích hoàn chỉnh về 1, với điểm khác biệt là thay vì một chuỗi rời rạc $y_0, y_1, \dots, y_n$ bây giờ giải quyết hàm $y(t)$ liên tục trong đó của đối số $t$ (ở đây $t$ là thời gian; chúng ta sẽ giả sử rằng $t$ chạy đoạn từ 0 đến $n$). Điểm tương tự của sai phân thứ nhất là tốc độ (sản phẩm đầu tiên $y'(t)$ của tọa độ $y(t)$), điểm tương tự của sai phân thứ hai là gia tốc (sản phẩm thứ hai $y''(t) = (y'(t))'$). Chúng ta sẽ giải bài toán này, sử dụng thuật ngữ vật lý; Những người đã quen thuộc với đạo hàm và tích phân sẽ dễ dàng dịch các điều kiện bài toán và lời giải của nó sang ngôn ngữ phân tích toán học.

Hãy chứng minh rằng đáp số trong bài toán này là: $an^2/16$ (cm).

⟦folio 33⟧

Để đầu máy điện tiếp cận vị trí xa nhất $M$ từ điểm $O$ tại một thời điểm nào đó $m$, $0 \leqslant m \leqslant n$. Rõ ràng là tốc độ của nó tại thời điểm này là bằng không. Chúng ta có thể giả định rằng $m \leqslant n/2$ (trong trường hợp $m > n/2$ chúng ta sẽ theo dõi chuyển động của đầu máy điện trong khoảng thời gian từ $m$ đến $n$ chứ không phải từ $0$ đến $m$ - xét cho cùng, trước và sau thời điểm $m$ chuyển động sẽ diễn ra theo cách hoàn toàn tương tự).

Hãy ước tính tốc độ của đầu máy điện $v(t)$ tại $0 \leqslant t \leqslant m$. Vì $v(0) = 0$, nên $v(t) \leqslant at$. Mặt khác, vì $v(m) = 0$, nên $v(t) \leqslant a(m-t)$. Theo đó độ dịch chuyển $h = |OM|$—diện tích bên dưới đồ thị vận tốc $v(t)$ trong khoảng thời gian $[0, m]$—không vượt quá diện tích của một tam giác có đáy $m$ và chiều cao $am/2$, tức là $h \leqslant am^2/4 \leqslant an^2/16$. Rõ ràng là ước tính này là chính xác và đồ thị chuyển vị tối ưu trong mỗi phần tư của đoạn $0 \leqslant t \leqslant n$ là một parabol (Hình 6, a-c).

Chúng tôi thấy rằng đối với tùy chọn “liên tục” (nhiệm vụ 2) đáp số và lời giải đơn giản hơn so với tùy chọn “rời rạc” (nhiệm vụ 1).

Hầu hết việc triển khai điều khiển tối ưu bài toán, khi được chính thức hóa về mặt toán học, cũng cho phép cả các tùy chọn liên tục và rời rạc. Tuy nhiên, các mô hình liên tục thường dễ nghiên cứu về mặt lý thuyết hơn và kết quả đẹp hơn về mặt hình thức. Nhưng đôi khi sự rời rạc bài toán là rời rạc do được tạo ra hoặc đơn giản hóa việc xây dựng đúng công thức toán học bài toán; và để tính toán trên máy tính kỹ thuật số, người ta thường phải chuyển sang một số phép tính gần đúng rời rạc của hàm bài toán liên tục.

Trong đoạn tiếp theo, chúng ta sẽ quay lại bài toán rời rạc, nhưng bây giờ các số của dãy sẽ nằm trên vòng tròn.

Các số trên một vòng tròn.
Công thức của kết quả

Bài 3. Trên một hình tròn có $n$ số thực, trong đó có một số bằng 1 và tổng các số đó bằng 0. Chứng minh rằng:

a) tìm hai số liền kề cách nhau ít nhất 4/n;
b) tìm một số khác với trung bình số học của hai số lân cận của nó ít nhất $16/n^2$.

Tiếp theo, chúng tôi sẽ trình bày rất ngắn gọn lời giải, cho phép chúng tôi đạt được từng điểm $n$ trong các ước tính trong câu a) và b). Những khả năng ước tính tốt nhất này là:

a) chênh lệch tối đa giữa các số lân cận không nhỏ hơn $\frac{4}{n}$ nếu $n$ là số chẵn và không nhỏ hơn $\frac{4n}{n^2-1}$ nếu $n$ là số lẻ (lưu ý rằng $\frac{4n}{n^2-1} > \frac{4}{n}$);
b) độ lệch tối đa của một số so với trung bình số học của hai số lân cận của nó không nhỏ hơn $\frac{16}{n^2}, \frac{16n}{n^3+n-2}$, $\frac{16}{n^2+4}$ hoặc $\frac{16n}{n^3+n+2}$ tương ứng, nếu $n$ cho số dư 0,1, 2 hoặc 3 khi chia cho 4.

Hình 7 và 8 thể hiện trình tự tối ưu (tại $n=30$):

⟦folio 34⟧

đối với dãy trong Hình 7, hiệu giữa hai số liền kề bất kỳ không nhỏ hơn 2/15 (đây là 4/n đối với n=30); đối với chuỗi trong Hình 8, độ lệch của mỗi số so với trung bình số học của hai số lân cận không nhỏ hơn 2/113 và, như trong bài toán đầu tiên, các điểm trong mỗi phần tư của đoạn nằm trên cùng một parabol. Chúng ta sẽ tiến hành chứng minh kết quả a) và 6) bên dưới con cáo với n=30 (đối với n khác thì kết quả gần giống nhau). Do đó, chúng ta thu được lời giải của chu kỳ bài toán M398 từ “Bài toán Kvant”).

Chúng ta hãy biểu thị những số này bằng $y_{-14}, y_{-13}, \dots, y_{15}$ sao cho $y_0=1$. Đối với bài toán a) không khó để có được ước tính cần thiết: nếu $|y_{k+1}-y_k| \leq \alpha$ cho tất cả $k=-14, \dots, 15$, thì khi tổng hợp các ước tính về sự khác biệt, như trong bài toán 1, chúng ta thu được $y_k \geq 1-|k|\alpha$. Nhưng tổng của $\Sigma y_k$ bằng 0, nên

$$0 = \Sigma y_k \geq 30 - 2(1+2+\dots+14)\alpha - 15\alpha = 30 - 15^2\alpha,$$

từ đâu $\alpha \geq 2/15$.

Hãy chuyển sang bài toán 6). Lưu ý rằng ở dòng $\frac{y_{k+1}+y_{k-1}}{2}-y_k$ chúng ta cần đánh giá chỉ đơn giản là các vị trí “khác biệt thứ hai” $(y_{k+1}-y_k)-(y_k-y_{k-1})$.

Bình thường hóa và lặp lại. Hãy thử sử dụng ứng dụng kép bài toán a).

Đặt $y_{k+1}-y_k=y'_k$, $\max_k |y'_k|=\alpha^{**}$. Theo a), $\alpha \geq 2/15$. Đối với dãy $z_k=y'_k/\alpha$, chúng ta lại có thể áp dụng a) (dễ dàng chứng minh rằng tổng của cả 30 số $z_k$ bằng 0 và lớn nhất của $z_k$ bằng một); do đó $\max_k |z_{k+1}-z_k| \geq 2/15$, và do đó

$$\max_k \frac{|y_{k+1}-2y_k-y_{k-1}|}{2} = (\alpha/2) \max_k |z_k-z_{k-1}| \geq (1/15)\alpha \geq 2/225.$$

Ước tính này gần như tệ hơn so với yêu cầu (trong trường hợp chung, ước tính tương tự sẽ là $8/n^2$ cùng với $16/n^2$).

Ý tưởng về một ước tính tinh tế hơn rất đơn giản: cần phải dựa trên ước tính $|y_{k+1}-2y_k+y_{k-1}| \leq 2\beta$ cho những khác biệt thứ hai để ước tính chính xác hơn những khác biệt đầu tiên, sau đó ước tính chính các số $y_k$ (sử dụng thực tế là $y_0=1$) và cuối cùng, từ đẳng thức $\Sigma y_k=0$ để có được ước tính cho β.

Đối xứng và kết hợp các ước tính. Trước khi chuyển sang thực hiện kế hoạch của mình, chúng tôi lưu ý rằng chúng tôi có thể giới hạn bản thân chỉ xem xét các chuỗi đối xứng: những chuỗi có $y_k=y_k-1$. Thật vậy, từ bất kỳ dãy nào $y_k$ thỏa mãn điều kiện $y_0=1$, $\Sigma y_k=0$, $|y_{k+1}-$

*) Xem «Kvant», 1976, số 8.

**) Ở đây và dưới k giá trị $-14 \leq k \leq 15$ chạy qua. Với k=15, chúng tôi giả sử $y_{k+1}=y_{-14}$, vì số liền kề với $y_{15}$ trên vòng tròn là $y_{-14}$.

$-2y_k+y_{k-1} \leq 2\beta$, chúng ta có thể thu được một chuỗi đối xứng $z_k = \frac{y_k+y_k-1}{2}$, dễ dàng xác minh, thỏa mãn tất cả các điều kiện này. (Theo ký hiệu của chúng tôi $y_0=y_{-0}=y_{15}=y_{-15}=1$.)

Bây giờ chúng tôi có:

$$y_0-y_1=(2y_0-y_1-y_{-1})/2 \leq \beta, y_{14}-y_{15} \leq \beta, y_1-y_2 \leq 3\beta, y_{13}-y_{14} \leq 3\beta, y_2-y_3 \leq 5\beta, y_{12}-y_{13} \leq 5\beta,$$

$$y_6-y_7 \leq 13\beta, y_7-y_8 \leq 15\beta, y_8-y_9 \leq 13\beta,$$

Từ bảy bất đẳng thức đầu tiên ta tìm được

$$y_k \geq 1-k^2\beta$$ tại $0 \leq k \leq 7$;

từ phần còn lại

$$y_k \geq 1-(7^2+8^2)\beta+(15-k)^2\beta$$ tại $7 \leq k \leq 15$. Tổng hợp tất cả $y_k$ (nhớ lại $y_k=y_{-k}$), chúng ta tìm thấy $0 \geq 30-15(7^2+8^2)\beta$, do đó $\beta \geq 2/113$.

Tóm lại - một số bài toán, theo cách này hay cách khác có mối liên hệ tương đối với những điều đã thảo luận ở trên.

1. Trong chuỗi $a_0, a_1, \dots, a_n$, các số $a_0$ và $a_n$ bằng 0 và mẫu chênh lệch giữa mỗi số và trung bình số học của hai số lân cận của nó không vượt quá một. Chứng minh rằng $a_k \leq k(n-k)$.

2. Người ta biết rằng $a_0, a_1, \dots, a_n$ > $a_k$ và $a_k+1=3a_k-2a_k-1$ cho tất cả $k>1$. Chứng minh rằng $a_{100}>2^{99}$.

3. Cho số $a_1, \dots, a_7$. Được biết, tổng của chúng bằng 0 và giá trị thấp nhất trong số chúng xét về giá trị abscylotic là $a_1=2$. Ước tính giá trị abscillometric tối đa của chênh lệch thứ hai.

4. Cho một bộ số nhất định $a_1, \dots, a_n$. Người ta biết rằng

$$0 \leq a_1 \leq a_2 \leq 2a_1,$$

$$0 \leq a_2 \leq a_3 \leq 2a_2,$$

v.v. Chứng minh rằng tổng $S=\pm a_1 \pm a_2 \pm \dots \pm a_n$ có thể có dấu sao cho bất đẳng thức $0 \leq S \leq a_1$ đúng.

5. a) Cho $x_0, x_1, \dots, x_n$ và $y_0, y_1, \dots, y_n$ là hai dãy sao cho “hiệu thứ hai” của chúng không đổi: $x_{k+1}-2x_k+x_{k-1}=a, y_{k+1}-2y_k+y_{k-1}=b(1 \leq k \leq n-1)$. Chứng minh rằng các điểm $(x_0;y_0), (x_1;y_1), \dots, (x_n;y_n)$ nằm trên cùng một parabol trong mặt phẳng $Oxy$.

6) Chứng minh rằng các điểm $(x;y)$, trong đó $x=a_1t^2+b_1t+c_1, y=a_2t^2+b_2t+c$, nằm trên cùng một parabol.

7. Cho hàm f tuần hoàn với chu kỳ T, có hàm tuần hoàn thứ nhất (a trong nhiệm vụ 6) và hàm số thứ hai (đạo hàm, không liên tục), ngoại trừ một số hữu hạn điểm; f liên tục trên [0, n].

8. Giả sử f được xác định trên khoảng [0, n], $f(0)=f(n)=0$. Giá trị lớn nhất mà f có thể đạt tới là bao nhiêu nếu a) $f'(x) \leq M_1$, 6) $|f''(x)| \leq M_2$? (Đạo hàm liên tục ngoại trừ hữu hạn số điểm; f liên tục trên [0, n].).

9. Cho hàm f tuần hoàn với chu kỳ T, có hàm tuần hoàn thứ nhất (a trong nhiệm vụ 6) và hàm số thứ hai (đạo hàm, không liên tục), ngoại trừ một số hữu hạn điểm; f liên tục trên [0, n].

10. Giả sử f được xác định trên khoảng [0, n], $f(0)=f(n)=0$. Độ cứng f có thể đạt giá trị lớn nhất bao nhiêu nếu a) $f'(x) \leq M_1$, 6) $|f''(x)| \leq M_2$? (Đạo hàm liên tục ngoại trừ tại hữu hạn số điểm; f liên tục trên [0, n])
