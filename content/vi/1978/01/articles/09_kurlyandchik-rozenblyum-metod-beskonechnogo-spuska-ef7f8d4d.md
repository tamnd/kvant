---
id: 1978-1-kurlyandchik-rozenblyum-metod-beskonechnogo-spuska-ef7f8d4d
issue: kvant_1978_1
year: 1978
number: "1"
title: Phương pháp gốc vô hạn
authors:
  - Курляндчик Л. Д.
  - Розенблюм Г.
rubric: matematicheskiy-kruzhok
rubric_sub: Математический кружок
page_first: 26
page_last: 29
page_labels: 24-27
tag: R8FB
lang: vi
source: kvant_digital
extraction: vision
content_sha256: 79ad0ec57480b682c1af0612f6336a995f291cd8362bacf835bfa7de10488bf1
prompt_sha256: draft-1
translated_from: content/ru/1978/01/articles/09_kurlyandchik-rozenblyum-metod-beskonechnogo-spuska-ef7f8d4d.md
source_content_sha256: 49b13da1db47c770c6ffd3fb68de08ebed5ecca5abc6bda004116401c09ad0e0
translation_model: draft
translation_run: vi-draft-2026-10-31
translation_quality: draft
---

⟦folio 24⟧

Phương pháp gốc vô hạn

Số vô tỷ nào tự nó là “cũ”? Không còn nghi ngờ gì nữa, $\sqrt{2}$. Chúng tôi không biết chính xác ai là người đầu tiên chứng minh tính phi lý của con số này, nhưng chúng tôi tin chắc rằng nó đã được thực hiện như thế này.

Bằng chứng đầu tiên

Giả sử rằng số $\sqrt{2}$ là số vô tỉ. Về mặt hình học, điều này có nghĩa là đường chéo của một hình vuông có độ dài $c$ tương xứng với cạnh có độ dài $a$, tức là sẽ tìm một đoạn có độ dài $d$ và các số nguyên $m$ và $n$ sao cho $c=dm$, $a=dn$. Chúng ta hãy đánh dấu $m-1$ điểm trên đường chéo $AC$ và $n-1$ điểm ở cạnh $DC$, chia các đoạn này thành các đoạn có chiều dài $d$. Chúng ta hãy đặt đoạn $AK: |AK|=|AD|;$ tại $|AC|$ và đoạn $DE: |DE|=|KC|$ tại $|DC|$ sang một bên. Điểm $K$ và $E$ sẽ rơi vào điểm bù trừ

Cơm. 1.

Chứng minh hai

Tính vô tỉ của $\sqrt{2}$ có nghĩa là phương trình $x^2=2y^2$ không phải là lời giải trong số tự nhiên $x, y$. Giả sử rằng có những lời giải như vậy, và $x=m$, $y=n$ là một trong số đó.

Từ phương trình suy ra $m$ là một số chẵn, $m=2m_1$. Thay $m=2m_1$ vào phương trình, ta được $n^2=2m_1^2$, tức là $x=n$, $y=m_1$ - cũng là lời giải. Chúng ta hãy lưu ý rằng $n<m$, $m_1<n$. Bây giờ rõ ràng rằng $n$ là một số chẵn, $n=2n_1$, do đó $m_1^2=2n_1^2$. Như vậy

⟦folio 25⟧

cùng một lúc, các phương trình $x = m_1, y = n_1$ - lời giải, với $m_1 < n, n_1 < m_1$. Chúng ta có thể xây dựng thêm theo cách tương tự, ngày càng thu được ít phương trình lời giải hơn. Nhưng ở đây đã có sự mâu thuẫn rồi. Suy cho cùng, tất cả các số $m, n, m_1, n_1, \dots$ đều là số tự nhiên, $m > n > m_1 > n_1 > \dots$, và không thể có dãy số tự nhiên giảm vô hạn! Điều này có nghĩa là giả định của chúng tôi đã sai và con số $\sqrt{2}$ là không hợp lý.

Về cơ bản, cả hai đối số đều tuân theo cùng một khuôn mẫu: giả sử rằng bài toán có lời giải, chúng ta đang xây dựng một số quy trình vô hạn, trong khi theo đúng nghĩa của bài toán thì quá trình này phải kết thúc ở đâu đó. Một phương pháp tương tự được gọi là phương pháp giảm vô hạn $^*$.

Thông thường phương pháp gốc được sử dụng ở dạng đơn giản hơn. Giả sử rằng chúng ta đã thêm vào phần cuối tự nhiên của quá trình, chúng ta thấy rằng nó không thể “dừng lại”.

Bằng chứng ba

Đặt $x = m, y = n$ - lời giải là phương trình $x^2 = 2y^2$ với $x$ nhỏ nhất có thể. Số $m$ phải là số chẵn, $m = 2m_1$, do đó $x = n, y = m_1$ cũng là lời giải của phương trình của chúng ta. Tuy nhiên, $m > n$, điều này mâu thuẫn với việc chọn lời giải $m, n$ là "nhỏ nhất".

Từ phiên bản chứng minh này, rõ ràng phương pháp giảm dần là một phương pháp quy nạp toán học trung bình. Cả hai phương pháp đều dựa trên thực tế là bất kỳ tập hợp số tự nhiên vô hạn nào cũng có phần tử tối thiểu. Phương pháp giảm dần là phương pháp thuận tiện nhất cho việc chứng minh tính “phủ định” của các định lý.

Phương pháp đi xuống trong các vấn đề

Bài toán 1. Chứng minh tính không giải được của phương trình số tự nhiên

$$8x^4 + 4y^4 + 2z^4 = t^4.$$

*) Phương pháp giảm vô hạn rõ ràng được phát minh bởi một nhà toán học Hy Lạp cổ đại. Có lý do để tin rằng Fermat đang cố gắng chứng minh Định lý vĩ đại của mình bằng chính phương pháp này.

Lời giải. Giả sử rằng lời giải tồn tại và $x = m, y = n, z = p, t = r$ là lời giải với $x$ nhỏ nhất có thể. Từ phương trình chúng ta có thể thấy rằng $r$ là số chẵn, $r = 2r_1$.

Thay thế lời giải này vào phương trình và biến nó thành 2 sẽ được

$$4m^4 + 2n^4 + p^4 = 8r_1^4.$$

Bây giờ rõ ràng là $p$ là chẵn, $p = 2p_1$, do đó

$$2m^4 + n^4 + 8p_1^4 = 4r_1^4.$$

Sau đó, nó hoạt động theo cách tương tự: $n = 2n_1$, $m^4 + 8n_1^4 + 4p_1^4 = 2r_1^4$.

Cuối cùng, $m = 2m_1$, $8m_1^4 + 4n_1^4 + 2p_1^4 = r_1^4$.

Vì vậy, $x = m_1, y = n_1, z = p_1, t = r_1$ là lời giải của phương trình của chúng ta. Nhưng đó là $m_1 < m$! Chúng tôi gặp mâu thuẫn với việc chọn lời giải $m, n, p, r$ là “nhỏ nhất”.

Hãy xem xét bài toán khó khăn hơn.

Bài toán 2. Chứng minh tính không giải được của phương trình số tự nhiên

$$x^2 + y^2 + z^2 + u^2 = 2xyzu.$$

Lời giải. Đặt $x, y, z, u$ - lời giải.

Vì $x^2 + y^2 + z^2 + u^2$ là số chẵn nên các số trung bình $x, y, z, u$ là số chẵn của các số lẻ, tức là số chẵn, hai hoặc bằng 0. Nếu tất cả các số đều là số lẻ thì $x^2 + y^2 + z^2 + u^2$ không chia hết cho 4 và $2xyzu$ không chia hết. Nếu chỉ có hai số lẻ thì $x^2 + y^2 + z^2 + u^2$ không chia hết cho 4 nhưng $2xyzu$ chia hết. Do đó, tất cả các số, tức là $x = 2x_1, y = 2y_1, z = 2z_1, u = 2u_1$. Thay các giá trị này vào phương trình, ta được

$$x_1^2 + y_1^2 + z_1^2 + u_1^2 = 8x_1y_1z_1u_1.$$

Như trước, ta thấy mọi số chẵn không thể lẻ, ngược lại $x_1^2 + y_1^2 + z_1^2 + u_1^2$ không chia hết cho 8. Tương tự, các số chẵn không thể lẻ, hoặc số chẵn $x_1^2 + y_1^2 + z_1^2 + u_1^2$ không chia hết cho 8. Vậy ta suy ra mọi số đều là số lẻ, tức là

$$x_1 = 2x_2, y_1 = 2y_2, z_1 = 2z_2, u_1 = 2u_2.$$

⟦folio 26⟧

Bởi vì

$$x_2^2 + y_2^2 + z_2^2 + u_2^2 = 32x_2y_2z_2u_2.$$
Lập luận như trước, chúng ta thấy rằng $x_2, y_2, z_2, u_2$ là các số chẵn, v.v. Dễ hiểu rằng với mọi s tự nhiên

$$x_s^2 + y_s^2 + z_s^2 + u_s^2 = 2^{2s+1}x_sy_sz_su_s,$$

Và

$$x_k = 2x_{k+1}; y_k = 2y_{k+1};$$

$$z_k = 2z_{k+1}; u_k = 2u_{k+1}; k \geqslant 1.$$

Nghĩa là, với mọi số tự nhiên s, các số $\frac{x}{2^s}, \frac{y}{2^s}, \frac{z}{2^s}, \frac{u}{2^s}$ đều là số nguyên. Vâng, điều này là không thể đối với mọi x, y, z, u tự nhiên.

Và đây là một phương trình có vô số lời giải, nhưng được nghiên cứu bằng cùng một phương pháp.

Bài toán 3. Tìm tất cả lời giải trong số tự nhiên của phương trình

$$x^2 - 2y^2 = 1.$$

Lời giải e. Rõ ràng là $x_1 = 3, y_1 = 2$ — lời giải của phương trình này. Hãy chứng minh rằng nếu cặp x, y là lời giải thì cặp đó là 3x + 4y; 2x + 3y cũng là lời giải. Điều này theo sau phần trình bày

$$(3x + 4y)^2 - 2(2x + 3y)^2 = x^2 - 2y^2.$$

Như vậy,

$$x_2 = 3 \cdot 3 + 4 \cdot 2 = 17,$$

$$y_2 = 2 \cdot 3 + 3 \cdot 2 = 12;$$

$$x_3 = 99, y_3 = 70,$$, v.v.

Chúng ta biểu thị dãy vô hạn lời giải $x_1, y_1; x_2, y_2; \dots$ Bây giờ chúng ta hãy chứng minh rằng không có số nào khác thỏa mãn phương trình.

Đặt x, y là một số lời giải. Trong trường hợp này, 3x - 4y, 3y - 2x cũng là lời giải, hoặc

$$(3x - 4y)^2 - 2(3y - 2x)^2 = x^2 - 2y^2.$$

Từ điều kiện 9 = 9x^2 - 18y^2 > -2y^2 suy ra 3x > 4y; và với y > 2, từ điều kiện 4 = 4x^2 - 8y^2 < y^2 suy ra 3y > 2x. Nghĩa là, với y > 2, từ lời giải x, y chúng ta thu được lời giải $x^{(1)}, y^{(1)}$ ở dạng số tự nhiên và $x^{(1)} < x, y^{(1)} < y$. Vì quá trình này không thể tiếp tục vô thời hạn (mọi tập hợp số tự nhiên không trống đều có phần tử nhỏ nhất!), nên một ngày nào đó chúng ta sẽ nhận được lời giải $x^{(n)}, y^{(n)}$, trong đó $y^{(n)} \leqslant 2$. Vì $y^{(n)}$ rõ ràng không thể bằng 1 nên $y^{(n)} = 2$. Vì vậy, $x^{(n)} = 3$.

Và điều này có nghĩa là các số x và y thuộc về dãy được xây dựng trước đó.

Cho đến bây giờ chúng ta chỉ xem xét các phương trình. Hãy giải quyết vấn đề bằng phương pháp “văn bản” bài toán của chúng tôi.

Bài toán 4. Có 2n + 1 chữ số, mỗi chữ số nặng một số nguyên gam. Người ta biết rằng 2n bất kỳ trong số chúng có thể bị phân hủy thành nhiều trọng số, n cho mỗi trọng số, sao cho đạt được trạng thái cân bằng. Chứng minh rằng mọi số đều có trọng số bằng nhau.

Lời giải e. Rõ ràng là tất cả các trọng số đồng thời có trọng số chẵn hoặc lẻ: trọng lượng của 2 n trọng lượng bất kỳ là số chẵn. Bây giờ chúng ta hãy trừ trọng lượng của tất cả các trọng lượng khỏi trọng lượng của trọng lượng nhẹ nhất (hoặc nhẹ nhất, nếu có một vài trong số chúng). Hệ thống cân mới, rất indo, cũng thỏa mãn điều kiện bài toán, và trong số các quả cân có những “quả cân” có trọng lượng bằng 0. Do đó, chúng ta lại thấy rằng trọng lượng của tất cả các vật nặng là chẵn, v.v. Từ “giảm dần vô hạn”, suy ra rằng tất cả các “trọng số” đều bằng 0, có nghĩa là tất cả các trọng số ban đầu đều có cùng trọng số.

Ý tưởng về sự giảm dần vô hạn cho phép chúng ta giải các tổ hợp hình học phi octorian bài toán.

Bài toán 5. Có thể cắt một khối lập phương thành các cốc khác nhau không?

Lời giải e. Trước hết chúng ta hãy đưa ra một nhận xét. Hãy chia hình vuông P thành một số hữu hạn các hình vuông khác nhau. Khi đó hình vuông nhỏ nhất không kề với ranh giới của hình vuông P.

Bây giờ chúng ta giả sử rằng khối Q đã được cắt thành các khối Q_j khác nhau; gọi P là một trong các mặt của Q. Các khối Q_j liền kề với P tạo ra sự phân chia P thành các hình vuông riêng biệt theo từng cặp. Cho P_1 là hình vuông nhỏ nhất trong số các hình vuông này, Q_1 là hình vuông tương ứng với ranh giới của P nên được bao quanh bởi các hình vuông lớn. Các khối tương ứng tạo thành một “cái giếng” trong đó khối Q_1 nằm trong đó.

⟦folio 27⟧

Đặt $P_1'$ là mặt “trên” (đối diện với mặt $P_1$) của khối lập phương $Q_1$. Các hình khối liền kề với $P_1'$ tạo ra sự phân chia $P_1'$ thành các hình vuông khác nhau. Một lần nữa, khối nhỏ nhất, $P_2$, nằm bên trong $P_1'$, do đó các khối xung quanh khối tương ứng $Q_2$ lớn hơn $Q_2$ và lại tạo thành một "cái giếng". Tiếp tục xây dựng xa hơn, chúng ta sẽ có được một “tòa tháp” vô tận bao gồm các hình khối ngày càng giảm và điều này là không thể.

Tóm lại - bài toán trên giấy ca rô.

Bài toán 6. Đưa cho một tờ giấy cuối cùng. Chứng minh rằng với $n \neq 4$ không có tập đi $n$ thông thường có đỉnh tại các nút. Thật vậy, gọi $a$ là độ dài cạnh của tam giác này; thì $a^2$ là một số nguyên theo định lý Pythagore. Diện tích của tam giác là $\frac{a^2 \sqrt{3}}{4}$, tức là vô tỉ. Mặt khác, điều rất quan trọng là diện tích của bất kỳ đa giác nào có đỉnh tại các nút phải hợp lý.

Vì một hình lục giác đều có thể được viết dưới dạng một tam giác đều có các đỉnh trùng nhau nên mệnh đề cũng được chứng minh cho $n=6$.

Hãy để $n \neq 3,4,6$. Giả sử rằng $P_1, P_2, \dots, P_n$ là một $n$-walker có các đỉnh tại các nút. Chúng ta hãy vẽ từ các điểm $P_1, P_2, \dots, P_n$ các vectơ tương ứng với vectơ $\overrightarrow{P_2}P_3; \overrightarrow{P_3}P_4; \dots, \overrightarrow{P_1}P_2$ (Hình 2). Các điểm mới sẽ lại rơi vào các nút mạng và tạo thành một khoảng trống $n$ thông thường bên trong nút bằng nhau đầu tiên. Với $n$-dự trữ mới, bạn có thể xây dựng theo cách tương tự, v.v., không ngừng. Tuy nhiên, bình phương độ dài các cạnh của máy thu $n$ là một số nguyên và trong công trình của chúng tôi, nó luôn giảm!

Y sắp kết hôn

1. Chứng minh rằng đáy và cạnh của một tam giác đều có góc ở đỉnh $36^\circ$ là vô số.
2. Chứng minh rằng số 7 không thể biểu diễn dưới dạng tổng bình phương của ba số hữu tỉ.
3. Giải các phương trình với số nguyên:
   a) $x^3 - 3y^3 - 9z^3 = 0$;
   b) $5x^3 + 11y^3 + 13z^3 = 0$.
4. Chứng minh rằng phương trình
   a) $x^2 + y^2 + z^2 = 2xyz$;
   b) $(x+1)^3 - x^3 = y^2$.
5. Giải các phương trình sau dưới dạng số tự nhiên:
   a) $x^2 + (x+1)^2 = y^2 + 1$;
   b) $3x^2 - 7y^2 + 1 = 0$;
   b) $(x+1)^3 - x^3 = y^2$.
6. Chứng minh rằng số thấp nhất có dạng $4^n(8k-1)$, trong đó $k$ và $n$ là số tự nhiên, không phải là số chính phương và không thể biểu diễn dưới dạng tổng của hai hoặc ba số bình phương.
7. $a_1, a_2, \dots, a_n$ là tập hợp các số tự nhiên phân biệt theo cặp ($n > 2$). Nó tạo một bộ mới $\frac{a_1 + a_2}{2}, \frac{a_2 + a_3}{2}, \dots, \frac{a_{n-1} + a_n}{2}, \frac{a_n + a_1}{2}$;
từ nó - cái tiếp theo, theo cùng một quy tắc, v.v. Chứng minh rằng sau vài bước chắc chắn bạn sẽ nhận được một tập hợp trong đó không phải mọi số đều là số nguyên.
8. Cho một đa giác lồi và một điểm bên trong đa giác đó. Chứng minh rằng ít nhất một trong các đường vuông góc với các mặt phẳng vẽ qua điểm này cắt mặt tương ứng. Thực tế này có đúng với đa giác không lồi không?
9. Cho $a_1, a_2, \dots, a_{2n}$ là tập hợp các số tự nhiên tùy ý. Chứng minh rằng nếu ta tạo một tập hợp mới $b_1, b_2, \dots, b_{2n}$ từ nó theo các quy tắc $b_k = |a_k+1 - a_k|$, $k=1, 2, \dots, 2^n$, $a_{2n+1} = a_1$, thì từ tập hợp $b_1, b_2, \dots, b_{2n}$ theo quy tắc tương tự ta tạo thành một tập hợp $c_1, c_2, \dots, c_{2n}$, thì sau một số bước nhất định ta sẽ đến một tập hợp chỉ gồm 0.
