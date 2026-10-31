---
id: 1987-6-sanninskiy-razmyishlyaya-ob-odnoy-olimpiadnoy-zadache-b8f980c5
issue: kvant_1987_6
year: 1987
number: "6"
title: Suy ngẫm về một Olympic bài toán
authors:
  - Саннинский В. Я.
rubric: matematicheskiy-kruzhok
rubric_sub: Математический кружок
page_first: 39
page_last: 40
page_labels: 37-38
tag: 5QAX
lang: vi
source: kvant_digital
extraction: vision
content_sha256: 3f80708cba0d556bc2230ccdcecaac55125cc529d8a6cbf61add9c9cd0441132
prompt_sha256: draft-1
translated_from: content/ru/1987/06/articles/11_sanninskiy-razmyishlyaya-ob-odnoy-olimpiadnoy-zadache-b8f980c5.md
source_content_sha256: e498202e358dcd84820292eb889f1a4f7906a286fbc97929217c0967d3c94e8d
translation_model: draft
translation_run: vi-draft-2026-10-31
translation_quality: draft
---

⟦folio 37⟧

Điều này có nghĩa là nếu bạn định thực hiện các công trình xây dựng bằng la bàn và thước kẻ và để quên thước ở nhà thì điều đó không thành vấn đề - bạn có thể thực hiện chỉ bằng một la bàn; nếu bạn quên la bàn, hãy hỏi bạn của anh ấy và vẽ một vòng tròn với nó, trước đó đã đánh dấu tâm của nó; sau đó bạn có thể xây dựng bất cứ thứ gì chỉ với một cây thước. (Tất nhiên, điều tồi tệ hơn là nếu bạn quên cả la bàn và thước kẻ ở nhà - ở đây khoa học bất lực trong việc giúp đỡ bạn.)

Đang suy nghĩ về một điều tối ưu bài toán

V. Y. SANNINSKY

Olympic bài toán không chỉ hữu ích trong việc kiểm tra khả năng toán học trong điều kiện cạnh tranh khắc nghiệt. Trong một lĩnh vực có năng lực hơn, khi có thời gian để suy nghĩ, bài toán cạnh tranh có thể trở thành nguồn gốc của một chút nghiên cứu độc lập, phần nào gợi nhớ đến sự sáng tạo toán học hữu ích.

Tôi chứng minh điều này bằng ví dụ về bài toán sau đây để làm bằng chứng, được tìm thấy trong nhiều bộ sưu tập của cuộc thi:

Nếu tất cả các số nguyên tố bắt đầu bằng 5 đều vướng víu theo thứ tự tăng dần thì mỗi số nguyên tố vướng víu sẽ lớn hơn số buổi sáng của nó.

Hãy cố gắng tự mình chứng minh điều đó. Nó không khó lắm; ví dụ, tôi đưa ra bằng chứng khá nhanh*. Tuy nhiên, sau đó tôi không bỏ bài toán mà bắt đầu suy nghĩ về cách diễn đạt của nó. Và câu hỏi ngay lập tức được đặt ra: số 5 và số 3 có liên quan gì, có thể lấy những số khác không? Điều này gợi ý việc đánh giá bài toán - cùng một cặp số (3, 5) để tạo khoảng cách cho một cặp $(k, p)$ tùy ý, trong đó $k$ là số tự nhiên và $p$ là số nguyên tố. Kết quả là một tuyên bố mà tôi gọi là

$Y(k, p)$: nếu tất cả các số nguyên tố bắt đầu bằng $p$, hãy nhầm lẫn theo thứ tự

*) Tôi đã lợi dụng thực tế là trung bình cộng của các số liên tiếp $9n, 9n+1, \dots, 9n+8, n=1, 2, 3, \dots$ có thể xuất hiện nhiều nhất là ba số nguyên tố.

tăng dần thì mỗi số nguyên tố vướng víu lớn hơn số của nó nhân với $k$.

Một vấn đề. Tuyên bố này không phải lúc nào cũng đúng (không phải với tất cả $k$ và $p$). Ví dụ: $Y(3,3)$ là sai (số nguyên tố 13 nhỏ hơn số ba của nó: $13 < 3 \times 5 = 15$). Mặt khác, chúng tôi biết rằng $Y(3,5)$ là đúng (đây là tuyên bố độc quyền của chúng tôi bài toán). Chà, sau đó sẽ xuất hiện bài toán mô tả về tất cả các cặp tốt $(k, p)$, tức là những cặp mà $Y(k, p)$ là đúng.

Để giải quyết vấn đề này, tôi bắt đầu thử nhiều cặp nhỏ khác nhau và nhanh chóng tìm thấy một vài cặp nhỏ (như $(4,5), (6,3)$) và một số cặp tốt $(\langle 1,2\rangle, (2,3), (2,5), (3,7))$. Tôi khuyên người đọc nên ngừng đọc tại thời điểm này và cũng nên thử các cặp nhỏ.

Hơn nữa, người đọc đã không làm theo lời khuyên của tôi; anh ta sẽ dễ dàng nhận ra rằng công lý $Y(k, p)$ hàm ý công lý $U(k', p')$ nếu $k' \leq k$ và $p' \geq p$. Tôi cũng nhanh chóng nhận thấy điều này và do đó quyết định không tìm kiếm tất cả các cặp tốt mà chỉ tìm những cặp không thể cải thiện được $(k, p)$, tức là những cặp mà $Y(k, p)$ là đúng, nhưng $Y(k', p')$ là sai đối với $p' > k$ và sai $Y(k', p')$ đối với $p' < p$. Đây là cách một bài toán mới xuất hiện: tìm tất cả các cặp không thể cải thiện được.

Bài tập 1. Chứng minh rằng các cặp $(1,2), (2,3) и (3,5)$ là không thể chứng minh được.

Tôi đã chứng minh điều này, có lẽ người đọc đã làm, mà không gặp nhiều khó khăn và không cần nhìn vào cặp tiếp theo - $(4,7)$. Hóa ra là không ổn: $7 > 4 \cdot 1, 11 > 4 \cdot 2, 13 > 4 \cdot 3, 17 > 4 \cdot 4$, nhưng sự thật là $19 > 4 \cdot 5$. Tôi chuyển sang cặp tiếp theo - $(4,11)$ - và bắt đầu thử $11 > 4 \cdot 1, 13 > 4 \cdot 2, \dots, 29 > 4 \cdot 6, 31 > 4 \cdot 7, \dots$. Tôi nhanh chóng cảm thấy mệt mỏi với điều này và quyết định rằng tôi có một giả thuyết hợp lý: cặp $(4,11)$ là không thể cải thiện được. Tôi thú nhận rằng tôi đã phải mày mò rất nhiều trước khi có thể chứng minh tính đúng đắn của giả thuyết này.

⟦folio 38⟧

Tôi đã nghĩ như thế này. Hãy để sự tích hợp $p_1 = 11, p_2 = 13, ..., p_n, ...$ trở nên cần thiết đối với chúng tôi. Để chứng minh $Y(4, 11)$, chúng ta cần thiết lập bất đẳng thức $p_n > 4n$ cho mọi $n \in \mathbb{N}$. Hãy lấy số $m = 210 = 2 \cdot 3 \cdot 5 \cdot 7$ (tích của tất cả các số nguyên tố nhỏ hơn 11) và chia tập hợp số tự nhiên $n \geq 11$ thành các lớp $m$, tùy theo số dư khi chia cho $m$. Cụ thể, đối với lớp $r$th $K_r$, $r = 0, 1, ..., m - 1$ chúng tôi bao gồm tất cả các số có dạng $n = tm + r$, trong đó $t \in \mathbb{N}$. thì mọi số tự nhiên $n$ đều thuộc đúng một lớp $K_r$ - cụ thể là vào lớp có số $r$, bằng phần dư của phép chia $n$ cho $m = 210$. Hãy để chúng tôi xóa khỏi danh sách $K_0, K_1, ..., K_{m-1} = K_{209}$ tất cả các lớp có số là số tổng hợp. Nói cách khác, chúng tôi sẽ chỉ để lại trong danh sách những lớp có số nguyên tố cùng nhau với $m$. Lưu ý rằng tất cả các số nguyên tố $p_1, p_2, ..., p_n$ ... đang được xem xét đều thuộc các lớp còn lại (tại sao?). Chúng ta hãy biểu thị số lượng của các lớp còn lại bằng $a_1, a_2, a_3, ...$, ví dụ: $a_1 = 11, a_2 = 13, ..., a_{47} = 209$.

Bài tập 2. Tìm tất cả các số ($\varphi(m) = \varphi(210) = 48$) của các lớp còn lại và kiểm tra xem bất đẳng thức $a_n > 4n$, trong đó $n = 1, 2, ..., 48$.*

Bây giờ chúng ta sắp xếp tất cả các số trong các lớp còn lại theo thứ tự tăng dần. Danh sách này bắt đầu bằng những con số mà chúng ta đã biết $a_1, a_2, a_3, ...$, nhưng không kết thúc ở $a_{48} = 211$ mà còn đi xa hơn: $a_{49} = 217, a_{50} = 221, ...$. Sau đó, rất rõ ràng rằng $a_n \leq p_n$ cho tất cả $n = 1, 2, ...$ (xét cho cùng, các số nguyên tố $p_1, p_2, ...$ của chúng ta nằm trong số các số còn lại $a_1, a_2, ...$). Do đó, chúng ta chỉ cần chứng minh bất đẳng thức $a_n > 4n$ (với mọi $n$) là đủ. Đối với 48 số đầu tiên $a_1, ..., a_{48}$ đã được xác minh (Bài tập 2), đối với $n$ tiếp theo, chúng ta sẽ chứng minh bằng quy nạp. Quy nạp sẽ được thực hiện trên tham số phụ $t$ với cố định $r$ ($r = 1, 2, ..., 48$), tức là chúng ta sẽ kiểm tra bằng chứng cho tất cả các số từ lớp có số $a_r$. Bất kỳ số $a_s$ nào từ lớp này đều được biểu diễn dưới dạng $a_s = t \cdot 210 + r$. Điểm bắt đầu quy nạp đã tồn tại (chúng tôi đã kiểm tra rằng tại $t = 0$ số $a_r$ thỏa mãn bất đẳng thức $a_r > 4r$). Let (câu quy nạp), $a_s = 210 \cdot t + r > 4s$. Chúng ta cần thiết lập bất đẳng thức $210(t + 1) + r > 4(s + 48)$, hoặc $s + 48$ - số của số tiếp theo $210(t + 1) + r$ từ lớp đang xem xét (với số $a_r$). Nhưng nó ngay lập tức suy ra từ mệnh đề quy nạp và bất đẳng thức rất mạnh $210 > 4 \cdot 48$. Tuyên bố $Y(4, 11)$ đã được chứng minh.

Bài tập 3. Kiểm tra xem với $k > 5$ câu $Y(k, 11)$ là sai.

Vì $Y(4, 7)$ cũng sai nên chúng tôi đã chứng minh rằng cặp $(4, 11)$ thực sự không thể cải thiện được.

Vấn đề sẽ tiếp tục - chúng tôi sẽ tìm kiếm một cặp không thể cải thiện được có dạng $(5, p)$.

Bài tập 4. Kiểm tra xem các cặp $(5, p)$ không phù hợp với $p < 23$ và cặp $(6, 23)$ cũng vậy.

Việc điều tra cặp $(5, 23)$ $(23 > 5 \cdot 1, 29 > 5 \cdot 2, 31 > 5 \cdot 3$, v.v.) dẫn đến

*) Các lớp $K_0, K_1, ..., K_{m-1}$ được gọi là các lớp dư lượng modulo $m$. Số lớp có các số nguyên tố cùng nhau đến $m$ được ký hiệu là $\varphi(m)$; hàm $\varphi$ được gọi là hàm Euler.

một giả thuyết khác: *pair* $(5, 23)$ là không thể chấp nhận được.

Công bằng mà nói thì giả thuyết có thể được thiết lập bằng cách suy luận theo cách tương tự như đối với cặp $(4, 11)$. Nghĩa là, lấy $m = 2 \cdot 3 \cdot 5 \cdot 7 \cdot 11 \cdot 13 \cdot 17 \cdot 19 = 9699690$, xét các lớp thặng dư modulo $m$, từ chúng chọn $\varphi(m) = 1658880$ các lớp nguyên tố cùng nhau đến $m$, chiếm tất cả các số (bắt đầu từ 23) từ các lớp đã chọn theo thứ tự tăng dần $(a_1, a_2, ...)$ và chứng minh bằng quy nạp rằng bất đẳng thức $a_n > 5n$ (từ đó suy ra $p_n > 5n$ cho số nguyên tố đã chọn $p_1 = 23, p_2 = 29, ...$) đúng với mọi số $a_n$ từ một lớp nhất định nếu nó đúng với số $a_n$ của lớp đó. Sau đó, tất cả những gì còn lại là kiểm tra xem bất đẳng thức $a_n > 5n$ có đúng với tất cả $n$ từ 1 đến $\varphi(m) = 1658880$ hay không. Tất nhiên, việc kiểm tra này không có ích gì cho con người. Tôi phải giao phó nó cho cái máy; Máy tính EU - 1045 trong 6 phút với đáp số; thực sự là $a_n > 5n$ tại $n = 1, 2, ..., \varphi(m)$. Phỏng đoán về tính không thể cải thiện của cặp $(5, 23)$ đã được xác lập.

Điều này thường xảy ra trong toán học hiện đại: với lý luận logic, một nhà toán học sử dụng bài toán để kiểm tra một tập hợp vô hạn các câu lệnh (trong trường hợp của chúng ta là các bất đẳng thức) thành một tập hợp hữu hạn (nhưng lớn) và các câu lệnh của tập hợp này được kiểm tra bằng máy tính.

Triển vọng trong tương lai là gì? Việc tìm kiếm cặp không thể cải thiện tiếp theo (thuộc loại $(6, p)$) dẫn đến các số, ở giới hạn khả năng của máy tính EC - 1045 và các cặp thuộc loại $(7, p)$ - không hoàn toàn phù hợp với cách tiếp cận của chúng tôi. Sau đó, tôi cố gắng khái quát hóa bài toán ban đầu theo một cách khác và đi đến công thức sau:

Torema. Các số nguyên tố tăng nhanh bất kỳ hàm tuyến tính nào của số đó; nói cách khác, nếu $p_1 = 2, p_2 = 3, ..., p_n, ...$ là một dãy gồm tất cả các số nguyên tố theo thứ tự tăng dần thì với bất kỳ $k$ và $b$ nào, bất đẳng thức $p_n > kn + b$ đúng với tất cả $n$ lớn hơn một số $n_0$ (tùy thuộc vào $k$ và $b$).

Hãy thử và chứng minh điều này nổi tiếng hơn nữa? Ví dụ, người ta có thể cố gắng chứng minh rằng các số nguyên tố tăng chậm hơn các đa giác bậc hai của số đó. Nhưng đây đã là một bài toán khó khăn: chúng ta đang tiếp cận đỉnh cao của khoa học và chúng ta chỉ có thể tiến xa hơn bằng cách nghiên cứu các tác phẩm của những người tiền nhiệm vĩ đại của chúng ta - Euler, Lagrange, Gauss, Riemann, Chebyshev.
