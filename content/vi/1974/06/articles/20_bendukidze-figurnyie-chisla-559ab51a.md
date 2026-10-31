---
id: 1974-6-bendukidze-figurnyie-chisla-559ab51a
issue: kvant_1974_6
year: 1974
number: "6"
title: số xoăn
authors:
  - Бендукидзе А. Д.
rubric: kvant-dlya-mladshih-shkolnikov
rubric_sub: «Квант» для младших школьников
page_first: 55
page_last: 57
page_labels: 53-55
tag: XG2D
lang: vi
source: kvant_digital
extraction: vision
content_sha256: 9fa71cbf0b2032ffe6bd0fad9bf3ec9bf92202188bd17b618ce8c076d9886ac0
prompt_sha256: draft-1
translated_from: content/ru/1974/06/articles/20_bendukidze-figurnyie-chisla-559ab51a.md
source_content_sha256: 7b3bab54703de40e49396065e461629ac921870b8361581516e1af80395b457d
translation_model: draft
translation_run: vi-draft-2026-10-31
translation_quality: draft
---

⟦folio 53⟧

1
Ở đây tôi đã vẽ ba dấu chấm (Hình 1).
Tôi đã vẽ nó theo cách mà nếu bạn kết nối chúng theo cặp, bạn sẽ có được một hình tam giác đều (nghĩa là đều) (Hình 2). Tuy nhiên, có thể nói, việc lấy các điểm ngay cả khi không kết nối sẽ tạo ra “ấn tượng” về một hình tam giác.

Và nếu có bốn điểm thì liệu chúng có thể được sắp xếp theo cách tương tự không? Hóa ra - không; xem cho chính mình. Và năm dấu chấm cũng không có tác dụng. Nhưng đã có thể sắp xếp sáu điểm theo thứ tự yêu cầu (Hình 3). Trong trường hợp này, một tam giác “sáu điểm” mới thu được từ tam giác “ba điểm” bằng cách nhân đôi tuyến tính tam giác sau; điều này gây ra việc bổ sung các điểm mới (Hình 4).

Phải thêm bao nhiêu điểm nữa để giữ nguyên “ấn tượng” của tam giác? Đáp số không khó tìm: bốn. Tam giác tương ứng - thu được bằng cách tăng tuyến tính tam giác ban đầu lên ba lần - được hiển thị trong Hình 5.

Tiếp tục cộng điểm, chúng ta sẽ nhận được ngày càng nhiều hình tam giác. Cụ thể, với mười điểm đã có, chúng ta sẽ thêm năm điểm, sau đó chúng ta sẽ thêm sáu điểm nữa vào mười lăm điểm thu được, thêm bảy điểm nữa, v.v. (tự vẽ các bức vẽ!).

Bây giờ chúng ta hãy thử tính xem bạn cần có bao nhiêu điểm để có thể tạo ra một “cấu hình tam giác” từ chúng.

Trong ví dụ của chúng tôi, lúc đầu có 3, 6, 10 điểm; rồi 15, 21, 28, . . .

Những con số này, vì những lý do hiển nhiên, được gọi là *tam giác*. Chúng ta muốn tìm hiểu xem có những loại số tam giác nào. Điều này không khó thực hiện nếu bạn nhận thấy rằng

$$3 = 1 + 2$$
$$6 = 1 + 2 + 3$$
$$10 = 1 + 2 + 3 + 4$$
$$15 = 1 + 2 + 3 + 4 + 5$$

⟦folio 54⟧

Mô hình mà những con số này được tổng hợp thật đáng kinh ngạc. Có thể chứng minh rằng mô hình này tiếp tục được áp dụng. Điều này có nghĩa là nếu số tam giác thứ $n$ được biểu thị bằng $T_n$ và chúng ta giả sử rằng $T_1 = 1$ thì công thức sau sẽ hợp lệ:

$$T_n = 1 + 2 + 3 + \dots + n.$$

Nó trông khá đơn giản nhưng rõ ràng không phù hợp để tính toán. Để có một dạng tính toán thuận tiện hơn, hãy lưu ý rằng ở vế phải của đẳng thức, các số hạng cách đều đầu và cuối cộng lại có cùng một số, cụ thể là $n + 1$.

Bây giờ mọi thứ rất đơn giản: chúng ta viết công thức của mình hai lần, trong trường hợp thứ hai, thứ tự của các số hạng bị đảo ngược:

$$T_n = 1 + 2 + 3 + \dots + (n - 2) + (n - 1) + n,$$

$$T_n = n + (n - 1) + (n - 2) + \dots + 3 + 2 + 1.$$

Hãy cộng hai đẳng thức này vào một “cột”; thì ở bên trái chúng ta nhận được $2T_n$, và ở bên phải chúng ta nhận được số $n + 1$, lấy $n$ lần. Vậy, $2T_n = n(n + 1)$, từ đâu

$$T_n = \frac{1}{2}n(n + 1).$$

Phương pháp tính toán được sử dụng ở đây đã cho chúng ta cơ hội đơn giản hóa một biểu thức khá phức tạp.

Về vấn đề này, tôi muốn kể một câu chuyện truyền thống về một cậu bé tên Karl, người đã sử dụng phương pháp này với lời giải tương tự như bài toán.

“Một ngày nọ, một giáo viên ở trường tiểu học mà Karl theo học, muốn giữ bọn trẻ bận rộn lâu hơn, đã đưa ra một câu hỏi khó bài toán: cộng các số 1, 2, 3, v.v. cho đến 100. Học sinh bận rộn tính toán... Cậu bé Karl nhận thấy rằng các cặp số 1 và 100, 2 và 99, 3 và 98, v.v. cộng lại bằng 101. Sau khi tính toán trong đầu rằng những cặp như vậy là 50, ông viết đáp số - 5050 trên bảng đen của mình và đưa cho giáo viên rất ngạc nhiên…”

Tương lai cho thấy, lẽ ra ông thầy không nên ngạc nhiên: cậu bé Karl sau này trở thành Karl Friedrich Gauss vĩ đại, “vua toán học” tùy tiện trong suốt cuộc đời!

2

Ngoài các số hình tam giác, còn có các số hình vuông, hình chữ nhật, số có sáu số nguyên, v.v. Chúng được liên kết tương ứng với hình vuông, hình ngũ giác đều, hình lục giác đều, v.v.

Chúng ta hãy biểu thị số bình phương thứ $n$ bằng $K_n$ và số ngũ giác thứ $n$ bằng $\Pi_n$; Sau đó

$$K_n = n^2, \quad \Pi_n = \frac{1}{2}n(3n - 1).$$

Để có được những đẳng thức này, bạn cần có số nào trong số $K_n$ và $\Pi_n$

⟦folio 55⟧

Hình 7.

trình bày nó dưới dạng tổng tương ứng (xem Hình 6 và 7) và áp dụng phương pháp “ghép nối” các số hạng mà chúng ta đã biết. Hãy tự mình thực hiện các phép tính.

Tương tự, bạn có thể tìm thấy các biểu thức cho các số lục giác, bảy cạnh, v.v. Chúng ta sẽ giải bài toán tổng quát hơn - tìm công thức cho bất kỳ số $k$-than nào.

3

Vì vậy, hãy để $F^{(k)}_n$ biểu thị số $n$-thứ $k$-than. Hãy xem xét $k$-gon tạo ra số này (xem Hình 8). Ví dụ: hãy lấy một trong các đỉnh của đa giác này, $A$ và vẽ tất cả các đường chéo từ nó. Sẽ có bao nhiêu? Hãy làm toán.

Đỉnh $A$ có thể được kết nối với mỗi đỉnh $(k-1)$ khác;

nhưng khi nối $A$ với hai đỉnh liền kề, chúng ta không nhận được đường chéo mà là các cạnh của đa giác. Điều này có nghĩa là các đường chéo có được bằng cách kết nối $A$ với các đỉnh $(k-1)-2 = k-3$. Đây là số đường chéo.

Bằng cách vẽ các đường chéo từ đỉnh $A$, chúng ta chia $k$-giác thành các hình tam giác $k-2$ (xem Hình 9). Mỗi hình tam giác này được liên kết với số tam giác thứ $n$ $T_n$. Biết $T_n$, chúng ta có thể đếm số điểm trong một $k$-giác cho sẵn, tức là tìm công thức cho $F^{(k)}_n$. Trên thực tế, có $T_n$ điểm trong mỗi tam giác và $k-2$ tam giác. Tổng cộng - $(k-2)T_n$ điểm. Trong trường hợp này, chúng tôi đếm các điểm nằm trên các đường chéo hai lần - xét cho cùng, đường chéo là một cạnh của hai hình tam giác liền kề.

Hình 8.

Hình 9.
