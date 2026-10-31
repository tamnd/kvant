---
id: 1980-8-vayntrob-luchshe-porovnu-ad14513e
issue: kvant_1980_8
year: 1980
number: "8"
title: Tốt hơn - bằng nhau
authors:
  - Вайнтроб А. Ю.
rubric: matematicheskiy-kruzhok
rubric_sub: Математический кружок
page_first: 25
page_last: 27
page_labels: 23-25
tag: 2FU5
lang: vi
source: kvant_digital
extraction: vision
content_sha256: c7449f946921aaeafaf2114ed5be36675a59d9f84c6ca94499a5eae8eafc1770
prompt_sha256: draft-1
translated_from: content/ru/1980/08/articles/11_vayntrob-luchshe-porovnu-ad14513e.md
source_content_sha256: 2eb27e22649831f3965918c80311a6c9e935bf28010b648e13915395bbb28bd4
translation_model: draft
translation_run: vi-draft-2026-10-31
translation_quality: draft
---

⟦folio 23⟧

Tốt hơn - bằng nhau

Trong các vấn đề khác nhau về phân tích và toán ứng dụng, các câu hỏi thuộc loại này nảy sinh:

Cho hai số v và p: 0 < v < p. Hãy xem xét tất cả các bộ số (hữu hạn) có thể có $x_1, x_2, ..., x_k$ sao cho 0 < x_i ≤ v với mọi i = 1, 2, ..., k và tổng $\sum_{i=1}^{k} x_i$ của tất cả các số trong bộ đó lớn hơn p.

Đối với mỗi tập hợp như vậy, có một số D sao cho 1) tổng S của một số số nhất định của tập hợp (cụ thể là có thể là tất cả) khác với p trên D: |S−p| = D và 2) bất kỳ tổng nào khác của các số nhất định của tập hợp đều khác với p nhiều hơn D.

Đối với mỗi bộ này, số D (“lỗi gần đúng”) sẽ lớn nhất?

Như chúng ta sẽ thấy, thứ chúng ta đang tìm kiếm sẽ là một tập hợp các số giống hệt nhau: “tốt hơn - bằng nhau”.

Ở đây chúng ta sẽ xem xét một số bài toán cụ thể (bao gồm cả bài toán M583 khó từ Bài toán Kvant) thuộc loại được chỉ định.

1. Xét các bộ đá, khối lượng mỗi viên không quá 2 kg và tổng khối lượng của bộ lớn hơn 10 kg. Từ một bộ như vậy, một số viên đá được chọn, tổng khối lượng của chúng khác với 10 kg theo số D mà bộ này có thể có. Giá trị lớn nhất mà số D có thể nhận được đối với tất cả các bộ đá có thể có là bao nhiêu?

(bài toán này đã được trình bày tại Cuộc thi Tối ưu hóa Toán học Thành phố Moscow năm 1979.)

Rõ ràng là số D của bất kỳ bộ đá nào sẽ không vượt quá 2 kg, vì khối lượng của bất kỳ viên đá nào cũng không quá 2 kg. Ngoài ra, rất nhiều D không thể bằng 2 kg. Vì vậy, để sử dụng với các bộ mà tất cả các viên đá đều giống nhau, chúng tôi thay thế lấy được nhiều D nhất trong trường hợp các viên đá vẫn còn khá nặng và đến 10 kg nửa viên đá là không đủ. Bốn viên đá nặng hơn 10 kg nhiều hơn 2 kg, và đối với phần gót của những viên đá theo phương trình 5x = 10−x/2, chúng ta tìm được x = 20/11, tức là D = 10/11.

Bây giờ chúng ta hãy chứng minh rằng với bất kỳ tập hợp D nào không vượt quá 10/11, nghĩa là, chúng ta sẽ chỉ ra rằng từ một bộ đá tùy ý, chúng ta có thể chọn một số viên có tổng khối lượng khác 10 kg không quá 10/11.

Chúng ta sẽ chọn từng viên đá: đầu tiên chúng ta sẽ lấy viên nặng nhất, sau đó là viên nặng nhất còn lại, v.v. cho đến khi khối lượng của những viên đá được chọn không vượt quá 10 kg. Nếu trong số những viên đá được chọn có một viên đá có trọng lượng nhỏ hơn 20/11 kg thì tổng khối lượng của chúng nhỏ hơn (10+10/11) kg hoặc ở bước trước (trước khi lấy viên đá cuối cùng) chúng ta có một bộ có khối lượng lớn hơn (10−10/11) kg (=10+10/11−20/11), nhưng nhỏ hơn hoặc bằng 10 kg.

Vì vậy, giá trị tối đa của D là 10/11 và giá trị này đạt được trên một bộ đá giống hệt nhau.

Bài tập 1. Chứng minh rằng trong trường hợp tổng quát, giá trị cao nhất của D đạt được trên một tập hợp các viên đá giống hệt nhau và giá trị này bằng p/(1−2·[1/2−p/v]) ([x] là phần nguyên của số x).

2. Bây giờ chúng ta hãy giải bài toán M583 từ Bài toán Kvant. Nó khác với bài toán 1 ở một hạn chế bổ sung, một sự gia tăng đáng kể: được biết rằng tổng khối lượng của bộ là 50 kg.

Chúng ta đã biết rằng D không vượt quá 11/10. Tuy nhiên, trong trường hợp này

⟦folio 24⟧

ước tính này không chính xác, vì số 50 không chia hết cho 20/11 (nếu tổng khối lượng của cả bộ không phải là 50 mà là 100 kg thì đáp số sẽ giữ nguyên).

Xem xét tất cả các phần có thể phân chia 50 kg thành các viên đá có khối lượng bằng nhau, chúng tôi tin chắc rằng giá trị lớn nhất $D$ đối với các bộ như vậy bằng $D_0 = 20/27$ kg. (Điều này đạt được trên một bộ gồm 27 viên đá có khối lượng 50/27.) Mục tiêu của chúng tôi là chứng minh rằng $D_0$ là giá trị đặc biệt lớn nhất của $D$. Để làm được điều này, chỉ cần chứng minh rằng một bộ tùy ý có thể được thay thế bằng một tập hợp các viên đá có cùng khối lượng mà không làm giảm $D$ (đầu vào $D$ cho các bộ đá giống hệt nhau không vượt quá $D_0$).

Hãy xem xét một tập hợp tùy ý. Chúng ta hãy chọn từ đó những viên đá có tổng khối lượng khác 10 kg với số nhỏ nhất có thể (nghĩa là bằng $D$). Chúng ta hãy chia những viên đá có khối lượng lớn hơn $2D_0$ thành hai nhóm. Nhóm đầu tiên bao gồm những nhóm nằm trong số những nhóm được chọn (trống $a_1$, $a_2$, ..., $a_m$ khối lượng của chúng). Nhóm thứ hai bao gồm các viên đá có khối lượng $b_1$, $b_2$, ..., $b_n$ (lớn $2D_0$), không nằm trong danh sách tuyển chọn. Để cho ngắn gọn, đôi khi chúng ta sẽ viết "đá $a_i$" (tương ứng với $b_j$), nghĩa là "viên đá có khối lượng $a_i$" (tương ứng với $b_j$). Gọi $A$ là tổng khối lượng của các viên đá $a_i$ (đôi khi $A$ sẽ biểu thị một bộ gồm các viên đá $a_1$, $a_2$, ..., $a_m$; tổng khối lượng $B$ và $C$ được xác định dưới đây cũng có thể được sử dụng để biểu thị các bộ tương ứng), $B$ là tổng khối lượng của các viên đá $b_i$, và $C$ là tổng khối lượng của các viên đá còn lại (tức là những viên có khối lượng không vượt quá $2D_0$).

Bây giờ chúng ta hãy chứng minh rằng có một tập hợp mà $a_1 = a_2 = ... = a_m = b_1 = ... = b_n$, $C = 0$ và giá trị $D$ không nhỏ hơn giá trị ban đầu. Điều này có nghĩa là $D \leq D_0$, vì đối với các bộ gồm các viên đá giống hệt nhau, $D$ không vượt quá $D_0$. Trong trường hợp này, có thể xảy ra hai trường hợp:

1. Tổng khối lượng của những viên đá được chọn là 10-D.

Để xây dựng tập hợp yêu cầu, chúng ta sẽ phải chứng minh một số mệnh đề bổ trợ.

Bổ đề 1. Tất cả các viên đá có trong $C$ đều thuộc về những viên được chọn (tức là $10—D = A+C$).

Thật vậy, nếu ít nhất một trong những viên đá có trong $C$ không được chọn, thì bằng cách thêm nó vào những viên đá đã chọn, chúng ta sẽ thu được một số viên đá có khối lượng khác nhau từ 10 kg không quá $2D_0—D<D$. Và điều này mâu thuẫn với việc lựa chọn tập hợp được đề cập.

Bổ đề 2. $a_i \geq b_j$ với mọi $i$ và $j$ ($1 \leq i \leq m$, $1 \leq j \leq n$).

Thật vậy, nếu một số $i$ và $j$ thỏa mãn bất đẳng thức $a_i < b_j$, thì bằng cách thêm nó vào những viên đã chọn, chúng ta sẽ thu được một số viên đá có khối lượng khác nhau từ 10 kg không quá $2D_0—D<D$. Và điều này mâu thuẫn với tính tối ưu của tập hợp đã chọn.

Bổ đề 3. $b_j > C+2D_0$ với mọi $j$ ($1 \leq j \leq n$).

Hãy loại bỏ tất cả các viên đá có trong $C$ khỏi bộ đã chọn và thêm đá $b_j$ vào đó. Nếu $A+b_j \leq 10—D$, thì bằng cách thêm từng viên đá từ $C$, đến một lúc nào đó chúng ta sẽ có được một bộ có khối lượng lớn hơn 10-D (kể từ $A+b_j+C > A+C=10—D$), nhưng nhỏ hơn 10+D (vì mỗi lần thêm một viên đá có khối lượng không vượt quá $2D_0<2D$). Điều này có nghĩa là $A+b_j>10—D$, và do đó (do mức tối thiểu của $D$) $A+b_j>10+D=A+C+2D>A+C+2D_0$, từ đó $b_j>C+2D_0$.

Từ Bổ đề 2 suy ra $a_i>C+2D_0$ cho mọi $i$.

Bổ đề 4. Nếu tổng khối lượng $k$ của các viên đá từ $A$ và $l$ của các viên đá từ $B$ nhỏ hơn 10+D, thì $k+l \leq m$.

Nếu tổng này nhỏ hơn 10+D thì do mức tối thiểu của $D$ nên nó nhỏ hơn hoặc bằng 10—D. Hãy để $k+l > m$. Thay thế các viên đá $b_j$ trong tổng này lần lượt bằng những viên đá $a_i$ không có trong đó, cuối cùng chúng ta sẽ đặt viên đá cuối cùng $a_i$ và do đó đưa tổng về giá trị $A+b_j+...>A+C+2D_0>10+D_0$ (xem Bổ đề 1 và 3). Vì mọi người

⟦folio 25⟧

vì chúng tôi đã thêm một viên đá có khối lượng không quá $2D_0$ ($a_i - b_j < 2D_0$), tại một thời điểm nào đó, số tiền này sẽ nằm trong khoảng từ $10 - D$ đến $10 + D$. Sự mâu thuẫn.

Cuối cùng chúng ta hãy chứng minh rằng có thể xây dựng một tập hợp gồm các viên đá có cùng khối lượng mà không làm giảm $D$.

Hãy thay từng viên đá $a_i$ ($i = 1, \dots, m$) bằng một viên đá có khối lượng $a = A/m$, mỗi viên đá $b_j$ ($j = 1, \dots, n$) bằng một viên đá có khối lượng $b = B/n$ và giữ nguyên những viên đá từ $C$. Hãy chứng minh rằng đối với một tập hợp như vậy thì số $D$ không giảm.

Giả sử rằng $D$ đã giảm. Sau đó, đối với một số $k$, $l$ và $C' < C$ tổng $ka + lb + C'$ nằm hoàn toàn giữa $10 - D$ và $10 + D$. Hãy lấy $k$ những viên đá nhẹ nhất từ ​​$A$. Tổng khối lượng của chúng không vượt quá $ka$ (tại sao?). Tương tự, tổng khối lượng $l$ của những viên đá nhẹ nhất từ ​​$B$ không vượt quá $lb$. Nhưng $ka + lb < 10 + D$, do đó $k + l \leq m$ (xem Bổ đề 4). Trong trường hợp này, $10 - D = A + C = ma + C \geq ka + la + C' \geq ka + lb + C' > 10 - D$. Sự mâu thuẫn.

Nếu $a > b$, thì $b$ không thể được đưa vào bất kỳ tổng nào bằng $10 - D$ (thay $b$ bằng $a$, ta thu được mâu thuẫn). Vì vậy, chúng ta có thể đọc (đưa ra nghĩa chính xác của các từ này!) để giảm bớt tất cả những viên đá có khối lượng $a$, đọc để thông báo những viên đá có khối lượng $b$, sao cho $C$ không thay đổi. Điều này sẽ dẫn đến một tập hợp có nhiều giá trị $D$ hơn tập hợp ban đầu. Sau khi thực hiện việc này vài lần, chúng ta sẽ có được một bộ có $a = b$.

Nếu có $C > 0$ trong bộ này, hãy tăng $a$ (số lượng đá có khối lượng $a$ là $m + n$) lên $\varepsilon$, trong đó $\varepsilon < C/(m + n)$; trong trường hợp này, $C$ sẽ giảm $(m + n)\varepsilon$. Nhưng sau đó $D$ sẽ tăng thêm $n \cdot \varepsilon$, đó là điều bắt buộc. Sau một vài bước, chúng ta nhận được một bộ có $a = b$ và $C = 0$.

Trường hợp tôi đã được phân tích đầy đủ.

II. Tổng khối lượng của những viên đá được chọn là $10 + D$.

Trường hợp này có thể được xem theo cách tương tự. Nhưng dễ nhận thấy hơn rằng nếu những viên đá dokot được chọn là xấp xỉ tốt nhất (đối với một bộ nhất định) đến 10 s và zbyt koM, thì những viên đá còn lại của bộ sẽ cho kết quả gần đúng nhất với nhược điểm là 50-10 (tức là 40 kg trong bài toán của chúng tôi). Vì $D_0$ vẫn còn ít nhất 2/4 kg (đây là điều kiện bổ sung duy nhất được sử dụng trong Trường hợp I), tất cả các nhận định đã được chứng minh vẫn có hiệu lực sau khi thay 10 bằng 40.

Vì vậy, bài toán lời giải. Giá trị lớn nhất có thể có của $D$ hóa ra là $D_0 = 20/27$ kg.

Lưu ý rằng lý luận của chúng tôi cho phép chúng tôi giải quyết tổng quát sau bài toán: tìm giá trị lớn nhất của sai lệch nhỏ nhất so với $p$ trên tất cả các tập hợp đá có thể có có khối lượng không vượt quá $v$ và tổng khối lượng $P$. Chúng tôi đã chứng minh rằng nếu có một bộ chứa $D > v/4$, thì giá trị tối đa $D$ phải được tìm kiếm giữa các bộ đá giống hệt nhau.

Bài tập

2. Chứng minh rằng với $v = 2$ kg, $p = 10$ kg, $P \geq 24$ kg tồn tại một tập hợp mà $D \geq v/4$.

3. Hoàn thành lời giải bài toán trong trường hợp tổng quát.

Đây là một bài toán khác về chủ đề này: có một số trong số đó không quá 1 t và tổng khối lượng của chúng là 10 t; Hỏi số ba tấn nhỏ nhất chắc chắn có thể dùng để phóng to những chiếc hộp này là bao nhiêu?

Các bài tập sau đây sẽ giúp bạn giải quyết vấn đề này bài toán (và khái quát hóa của nó) (hai bài tập đầu tiên giống với bài bài toán đã được thảo luận):

4. Đặt ràng buộc duy nhất về tổng khối lượng của các hộp là điều kiện $P > 3$ t. Tải trọng lớn nhất $\Gamma$ chắc chắn có thể tăng lên trên một tritonic là bao nhiêu?

5. Nó sẽ như thế nào đáp số ở phần trước bài toán, nếu biết được điều đó $P = 10$ T?

6. Bây giờ khối lượng của mỗi hộp không vượt quá $v$, tổng khối lượng bằng $P$ và chúng ta có sẵn một chiếc máy có khả năng chuyên chở $p$. Gọi $\Gamma$ là khối lượng của tải trọng tối đa mà chúng ta có thể chất lên ô tô. Chứng minh rằng đạt được giá trị nhỏ nhất của $\Gamma$ khi tất cả các hộp có cùng khối lượng.

7. Nguồn cung $p$-tấn nhỏ nhất phải có để đảm bảo chuyển được tất cả các hộp từ Bài tập 6 là bao nhiêu?

Cố gắng tìm khả năng của các định lý xác nhận nguyên tắc “tốt hơn là bình đẳng”.
