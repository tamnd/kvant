---
id: 1984-7-matulis-savukinas-ferzya-v-ugol-tszyanshitszyi-i-chisla-fibonachchi-4cd84eed
issue: kvant_1984_7
year: 1984
number: "7"
title: “Nữ hoàng vào góc”, “jianshizi” và các con số Fibonacci
authors:
  - Матулис А. Ю.
  - Савукинас А. Ю.
rubric: osnovnye-stati
rubric_sub: Основные статьи
page_first: 20
page_last: 23
page_labels: 18, 21
tag: 9F80
lang: vi
source: kvant_digital
extraction: vision
content_sha256: 33ede4503052bde7de5e7cf7d57bc621ce69c6029530c2db313361b9fb602b19
prompt_sha256: draft-1
translated_from: content/ru/1984/07/articles/06_matulis-savukinas-ferzya-v-ugol-tszyanshitszyi-i-chisla-fibonachchi-4cd84eed.md
source_content_sha256: 46af658af070043cb2e3a12f4973c92c21d6c6c1b3cfb832556ce15b0f87ad35
translation_model: draft
translation_run: vi-draft-2026-10-31
translation_quality: draft
---

⟦folio 18⟧

“Nữ hoàng vào góc”, “Jianshi” và các con số Fibonacci

A. Y. MATULIS, A. Y. SAVUKINAS

Chúng tôi muốn giới thiệu với bạn một ứng dụng khác khá bất ngờ của số Fibonacci, được mô tả trong bài viết của I. M. Yaglom trên trang. Tạp chí số này ngày 15-18.

Chúng ta sẽ thấy rằng các số Fibonacci giúp xây dựng lý thuyết về trò chơi Jianshizi cổ xưa của Trung Quốc và trò chơi liên quan Queen to Corner. Trò chơi này đã được I.M. Yaglom dành cho một bài viết («Kvant», 1971, Số 2, trang 4) và A. Orlov («Kvant», 1977, Số 3, trang 41).

Ở đây chúng tôi phác thảo một cách tiếp cận hơi khác đối với lời giải so với bài toán tương tự.

“Jianshitsy” và “Nữ hoàng trong góc”

Các điều kiện của trò chơi cổ xưa “Jianshitsi” (những viên đá được chọn) như sau. Có hai đống đá (hoặc một số đồ vật khác, chẳng hạn như diêm). Hai người chơi lần lượt chọn đá từ các cọc này và trong một nước đi, bạn có thể lấy số lượng đá từ một (bất kỳ góc nào) hoặc bằng nhau từ cả hai cọc cùng một lúc. Người nào lấy được viên đá cuối cùng sẽ thắng.

Chúng ta cần tìm ra trò chơi đôi bên cùng có lợi.

Đặt một viên đá ở một đống và b những viên đá ở đống thứ hai. Chúng ta hãy ghép các số (a, b) với bình phương của bàn cờ (vô hạn!) Như trong Hình 1 và đặt quân hậu vào ô vuông (a, b).

Dễ dàng nhận thấy mỗi nước đi trong trò chơi “Jianshitsi” tương ứng với một nước đi nhất định của quân hậu: nếu người chơi lấy k quân từ cọc đầu tiên thì quân hậu di chuyển k ô vuông sang trái; nếu người chơi lấy l viên đá từ đống thứ hai, quân hậu sẽ di chuyển l ô xuống; nếu anh ta lấy m viên đá từ mỗi đống, quân hậu sẽ di chuyển m ô vuông theo đường chéo sang trái và xuống dưới.

Vì vậy, cùng với trò chơi “Jianshitsi”, chúng ta có thể coi trò chơi “Quân hậu trong góc” với luật chơi: có một con hậu trên một bàn cờ vô hạn. Hai người chơi lần lượt di chuyển quân hậu sao cho quân hậu tiến đến ô vuông góc (0, 0), tức là trong một nước đi, quân hậu có thể di chuyển quân hậu bất kỳ số ô nào sang trái, xuống dưới hoặc theo đường chéo sang trái và xuống. Người chiến thắng là người đưa được quân hậu ra sân (0, 0).

Hình 1 hiển thị diễn biến của trò chơi bắt đầu trong ô (12, 14), trong đó mũi tên màu đỏ biểu thị bước đi của người chơi đầu tiên và mũi tên màu xanh biểu thị bước đi của người chơi thứ hai; Người chơi đầu tiên đã thắng ở đây.

Rõ ràng là bất kỳ trò chơi nào của trò chơi “Jianshitsi” đều tương ứng với một trò chơi nhất định của trò chơi “Nữ hoàng vào góc”, và trò chơi của trò chơi “Nữ hoàng vào góc” tương ứng với trò chơi “Jianshitsi”. Vì vậy, sau này chúng ta sẽ chỉ nói về trò chơi “Nữ hoàng vào góc”.

Mất ruộng

Hình 2 cho thấy một bàn cờ vô hạn trên đó một số trường được đánh dấu bằng dấu “—”. Chúng ta cũng sẽ gọi những trường này là trường bị mất. Không khó để nhận thấy rằng nếu một trong các người chơi đặt quân Hậu của mình lên ô vuông bị dịch chuyển sau mỗi nước đi thì người đó sẽ thắng.

Trên thực tế, không thể di chuyển từ bất kỳ ô bị dịch chuyển nào bằng cách di chuyển quân hậu đến một ô bị dịch chuyển. Ví dụ: từ bất kỳ trường không được dịch chuyển nào, bạn có thể di chuyển đến trường bị dịch chuyển chỉ bằng một lần di chuyển. Do đó, bằng cách đặt quân hậu của bạn vào một ô bị dịch chuyển, bạn buộc đối thủ của mình phải rút lui khỏi ô bị dịch chuyển. Ở nước đi tiếp theo, bạn có thể bước lại vào ô đã dịch chuyển (gần trường (0, 0), v.v.. Cuối cùng, bạn sẽ bước lên ô đã dịch chuyển (0, 0) và giành chiến thắng.

Bạn có thể chỉ định các quy tắc để thu được các trường offset một cách nhất quán. Đầu tiên trường (0, 0) bị xóa. Trường này có thể đạt được từ bất kỳ trường dọc a=0, ngang b=0 và đường chéo a=b. Các trường chưa được kiểm tra gần nhất là các trường (1, 2) và (2, 1). Có thể truy cập một trong các trường này từ bất kỳ trường dọc nào a=1, a=2, ngang

⟦folio 21⟧

Định lý chính

Bây giờ chúng ta có thể quên tất cả những cân nhắc đã dẫn chúng ta đến biểu thức viết cho các trường bị mất ($a_n, b_n$) và ngay lập tức hình thành định lý chính sau đây.

Định lý 1. Cho $u = \frac{1+\sqrt{5}}{2}$, $v = u^2 = u + 1 = \frac{3+\sqrt{5}}{2}$. Trường $(a, b)$, trong đó $b > a$, bị mất khi và chỉ nếu có một số tự nhiên $n$ sao cho $a = [nu], b = [nv]$. Nếu $n$ tự nhiên như vậy không tồn tại thì vị trí đó sẽ thắng.

Bằng chứng. Hãy xem xét chuỗi các điểm

$$(a_1, b_1), (a_2, b_2), \dots, (a_n, b_n), \dots,$$

trong đó $a_n = [nu], b_n = [nv]$ và chứng minh rằng chuỗi này thỏa mãn tính chất 1 và 2 (xem trang 19). Hãy bắt đầu với thuộc tính 1.

Trước tiên, hãy đảm bảo rằng tất cả các số $a_1, b_1, a_2, b_2, \dots$ đều khác biệt. Các số $a_i = [iu]$ khác nhau và $u > 1$ cũng vậy. Vì lý do tương tự ($v > 1$) nên các số $b_j = [jv]$ khác nhau. Giả sử rằng hai số $a_j$ và $b_j$ giống nhau. Điều này có nghĩa là $[iu] = [jv] = k$. Do đó, $iu = k + \delta$, trong đó $0 < \delta_1 < 1$, $jv = k + \delta_2$, trong đó $0 < \delta_2 < 1$. Chia đẳng thức thứ nhất cho $u$, đẳng thức thứ hai cho $v$, rồi cộng các đẳng thức thu được, chúng ta thu được đẳng thức

$$i + j = \frac{k}{u} + \frac{k}{v} + \frac{\delta_1}{u} + \frac{\delta_2}{v} = k + \frac{\delta_1}{u} + \frac{\delta_2}{v},$$

từ đó nó theo sau đó

$$0 < i + j - k = \frac{\delta_1}{u} + \frac{\delta_2}{v} < \frac{1}{u} + \frac{1}{v} = 1,$$

điều này là không thể, vì số $i + j - k$ là số nguyên.

Bây giờ chúng ta sẽ chứng minh rằng mọi số tự nhiên đều xuất hiện trong dãy $a_1, b_1, a_2, b_2, \dots, a_n, b_n, \dots$.

Cho $N$ là một số tự nhiên tùy ý.

Có chính xác $\left[ \frac{N}{u} \right]$ số $a_i = [iu]$, nhỏ hơn $N$. (Đây là những số có số $i = 1, 2, \dots, \left[ \frac{N}{u} \right]$.) Chính xác là $\left[ \frac{N}{v} \right]$ số $b_j = [jv]$, nhỏ hơn $N$. (các số có số $j = 1, 2, \dots, \left[ \frac{N}{v} \right]$.) Tổng cộng có $a_i$ và $b_j$, nhỏ hơn $N$, nên có $\left[ \frac{N}{u} \right] + \left[ \frac{N}{v} \right]$, và vì $\frac{N}{u}$ và $\frac{N}{v}$ không phải là số nguyên, $\frac{N}{u} - 1 + \frac{N}{v} < \left[ \frac{N}{u} \right] + \left[ \frac{N}{v} \right] < \frac{N}{u} + \frac{N}{v}$, nghĩa là

$$N - 2 < \left[ \frac{N}{u} \right] + \left[ \frac{N}{v} \right] < N.$$

Vì vậy, $\left[ \frac{N}{u} \right] + \left[ \frac{N}{v} \right] = N - 1$. Nhưng điều này có nghĩa là có chính xác số có dạng $a_i$ và $b_j$, nhỏ hơn $N$, cũng như số tự nhiên, nhỏ hơn $N$. Vì các số $a_i$ và $b_j$ đều khác nhau nên tính chất 1 của dãy $(a_1 b_1), (a_2 b_2), \dots, (a_n b_n)$, ... được chứng minh.

Tính chất 2 có thể dễ dàng chứng minh:

$$b_n - a_n = [vn] - [un] = [(u + 1)n] - [vn] - [un] = [nu] + n - [un] = n.$$

Như vậy định lý chính đã được chứng minh hoàn toàn.

Dãy số Fibonacci xuất hiện

Theo định lý chính, để xác định cặp thua có số $n$, người ta phải nhân $n$ với một số vô tỷ được cho dưới dạng phân số thập phân vô hạn. Có thể bạn chưa rõ phép nhân như vậy, đặc biệt nếu bạn không có máy cộng. Làm thế nào để xác định cặp thua $(a_n, b_n)$ thường chỉ bằng các phép tính trên số tự nhiên?

Thuộc tính sau đây của các cặp bị mất có thể phục vụ mục đích này:

3. Nếu $(a_n, b_n)$ là một cặp tùy ý thì các cặp $(b_n - 1, a_n + b_n - 1)$ và $(b_n + 1, a_n + b_n + 2)$ cũng là cặp tùy ý.

Hơn nữa, dựa trên trường ban đầu $(0, 0)$ hoặc trường đầu tiên $(1, 2)$, chúng ta có thể xây dựng, sử dụng thuộc tính 3, tất cả các cặp thua.

Hãy trình bày cách chứng minh tính chất 3.

Bài tập 2. Chứng minh rằng khi thua cặp $(a_n, b_n)$ và $(a_{n+1}, b_{n+1}): 2 \leq b_{n+1} - b_n \leq 3$ và $1 \leq a_{n+1} - a_n \leq 2$.

Từ kết quả của Bài tập 2 cho thấy các số $b_n - 1$ và $b_n + 1$ không phải là số lượng lớn các cặp thua. Theo tính chất 1, tồn tại $k$ và $l$ sao cho $a_k = b_n - 1$, $a_l = b_n + 1$. Hãy xem $k$ và $l$ bằng bao nhiêu.

Theo tính chất 2, số lượng của bất kỳ cặp nào đều bằng nhau giữa số lớn hơn và số nhỏ hơn của cặp này.

Mặt khác, từ tính chất 1, suy ra rằng số của bất kỳ cặp bị hủy $(a_k, b_k)$ và đẳng thức của nó đều nhỏ hơn số $a_k$ và số của tất cả các cặp khác 0 $b_l < a_k$. Tại $a_l = b_n - 1$ số lượng các số $b_l$ nhỏ hơn số $a_l$ là $n - 1$. Điều này có nghĩa là $k = b_n - 1 - (n - 1) = a_n$. Vì vậy, cặp $(b_n - 1, b + a_n - 1)$ được đánh dấu.

Bài tập 3. Chứng minh rằng cặp $(b_n + 1, a_n + b_n + 2)$ hủy được với mọi cặp hủy $(a_n, b_n)$.

Bài tập 4. Chứng minh rằng bất kỳ cặp xuất sắc $(a_n, b_n)$ nào cũng có thể thu được từ cặp $(0, 0)$ hoặc cặp $(1, 2)$ bằng cách áp dụng tuần tự một số thao tác được mô tả bởi Tính chất 3.

(Cuối cùng xem trang 29)
