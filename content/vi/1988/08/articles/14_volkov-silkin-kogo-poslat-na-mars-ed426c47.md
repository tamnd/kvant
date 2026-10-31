---
id: 1988-8-volkov-silkin-kogo-poslat-na-mars-ed426c47
issue: kvant_1988_8
year: 1988
number: "8"
title: Chúng ta nên gửi ai lên sao Hỏa?
authors:
  - Волков М. В.
  - Силкин Н. Н.
rubric: matematicheskiy-kruzhok
rubric_sub: Математический кружок
page_first: 53
page_last: 58
page_labels: 51, 53, 54, 55, 56
tag: LO25
lang: vi
source: kvant_digital
extraction: vision
content_sha256: 8d486160f6d7c94259252c412814a3e717d1f8c6d416c321d223f52fabfa9511
prompt_sha256: draft-1
translated_from: content/ru/1988/08/articles/14_volkov-silkin-kogo-poslat-na-mars-ed426c47.md
source_content_sha256: 8f8a47d60488102aceff40acc22606322dd71172d293b911eb2e8e85923bac86
translation_model: draft
translation_run: vi-draft-2026-10-31
translation_quality: draft
---

⟦folio 51⟧

Ai là người tiếp theo cho sao Hỏa?

Ứng viên Khoa học Vật lý và Toán học
M. V. VOLKOV, N. N. SILKIN

Bài viết này đưa chúng ta trở lại chủ đề được thảo luận trong bài viết của M. Gardner trên số thứ tư của «Kvant» - về “đồ thị màu” và lý thuyết Ramsey. Ở đây, ông nói về một số vấn đề điển hình của lý thuyết này và đặc biệt là lời giải bài toán M1099 được đưa ra (điều kiện của nó cũng được đặt ở số 4, 1988), các phương pháp ước lượng chung trong các vấn đề đó và ứng dụng của chúng sẽ được thảo luận.

Khái niệm cơ bản về ngoại giao máy móc

Trong khi thực hiện chuyến hành trình không gian tiếp theo của mình, Gromozeka, một nhà thám hiểm không gian có nhiều kinh nghiệm, đã phát hiện ra một hệ hành tinh xa lạ. Anh ta đặt lộ trình cho nó và nhanh chóng “hạ cánh” xuống hành tinh thứ ba từ ngôi sao trung tâm. Sau khi cảnh giác, Gromozeka nhìn thấy một thổ dân ở gần đó và tiến về phía anh ta. Cuộc trò chuyện được mong đợi đã diễn ra sau đó, từ đó Gromozeka biết được rằng có 9 hành tinh ở Ukh-ty (hóa ra đó là tên của hệ thống) và tất cả chúng đều có người sinh sống.

“Trước đây,” người bản xứ Gromozeke nói, “tất cả các hành tinh của chúng ta đều sống cùng nhau.” Nhưng sau khi Veselchak và Glot đến đây, một số hành tinh đã cắt đứt quan hệ ngoại giao. Đúng vậy, trong số bốn hành tinh bất kỳ, một số hành tinh vẫn là bạn của nhau, nhưng điều này là chưa đủ: suy cho cùng, chỉ có lực lượng thống nhất của ba hành tinh mới có thể chống lại sự xâm lược của loài hà mã có túi đang đe dọa chúng ta!

“Nguyền rủa bọn cướp,” Gromozeka kêu lên. “Tuy nhiên, không phải tất cả đều bị mất!” Trong hệ thống của bạn có ba hành tinh là bạn bè đôi của nhau và do đó có thể hợp nhất!

⟦folio 53⟧

hình, hoặc, như chúng được gọi trong toán học, đồ thị. Chính xác hơn, tập hợp các điểm và đường nối chúng được gọi là biểu đồ nếu 1) mỗi đường nối hai điểm; 2) hai điểm bất kỳ được nối với nhau bằng nhiều nhất một đường thẳng. Trong trường hợp này, các điểm thường được gọi là các đỉnh của đồ thị và các đường thẳng được gọi là các cạnh của đồ thị. Xem hình 4 để biết một ví dụ về biểu đồ. Các đỉnh $A, B, C, D$ trên hình này được nối thành từng cặp bằng các cạnh. Các đỉnh cũng được cho là tạo thành một đồ thị con hoàn chỉnh. Nhưng trong số các đỉnh $E, F, G, H$, không có đỉnh nào được nối bởi cạnh này với cạnh khác của cùng một đỉnh. Các đỉnh như vậy tạo thành một sơ đồ con trống.

Bây giờ bài toán khoảng sáu hành tinh có thể được hình thành như sau: bất kỳ đồ thị nào có sáu đỉnh đều chứa một đồ thị con hoàn chỉnh có ba đỉnh hoặc một đồ thị con trống có ba đỉnh. Điều Gromozeka đã chứng minh về hệ hành tinh Ukh-Ty về cơ bản có nghĩa là bất kỳ đồ thị nào có chín đỉnh đều chứa một đồ thị con hoàn chỉnh có ba đỉnh hoặc một đồ thị con trống có bốn đỉnh. Khi đó, điều tự nhiên là hỏi: nên lấy số tối thiểu nào $p$ để bất kỳ đồ thị nào có $p$ đỉnh đều chứa một đồ thị con hoàn chỉnh có ba đỉnh hoặc một đồ thị con trống có các đỉnh thứ năm. Nhưng chúng ta đừng vội trả lời nó, vì khi đó sẽ xuất hiện câu hỏi sau: phải lấy số tối thiểu nào $q$ để bất kỳ biểu đồ nào có $q$ đỉnh chứa một sơ đồ con hoàn chỉnh có ba đỉnh, bất kỳ sơ đồ con trống nào có sáu đỉnh, v.v. Hãy cố gắng khái quát hóa tốt hơn bài toán của chúng ta để trả lời ngay tất cả các câu hỏi như vậy.

Vì vậy, chúng ta hãy nhìn vào tình hình chung ngay lập tức. Đặt $m$ và $n$ là các số tự nhiên lớn hơn 1. Đặt $r(m, n)$ biểu thị số tối thiểu có đặc tính là bất kỳ đồ thị nào có ít nhất $r(m, n)$ đỉnh đều chứa một đồ thị con hoàn chỉnh có ba đỉnh, bất kỳ đồ thị con trống nào có sáu đỉnh, v.v. Hãy cố gắng khái quát hóa tốt hơn bài toán của chúng ta để trả lời ngay lập tức tất cả các câu hỏi như vậy.

*) Một độc giả khó tính sẽ nói: “Không có gì đảm bảo rằng con số đó tồn tại,” và anh ta sẽ đúng. Nhưng từ lý luận xa hơn, nó không chỉ dẫn đến ước tính về số $r(m, n)$ mà còn cả sự tồn tại của nó.

⟦folio 54⟧

Trường hợp hai. Số đỉnh nối từ cạnh này tới đỉnh $X$ nhỏ hơn $r(m-1, n)$. Nhưng khi đó ít nhất $r(m, n-1)$ đỉnh không được kết nối với $X$. Trong số các đỉnh này, các đỉnh $m$ tạo thành một sơ đồ con hoàn chỉnh hoặc các đỉnh $n-1$ tạo thành một sơ đồ con trống (và cùng với đỉnh $X$, thu được một sơ đồ con trống có các đỉnh $n$).

Hãy xem cách áp dụng bất đẳng thức (1). Ví dụ: chúng ta hãy tính số $r(3; 3)$. Từ công thức $r(2, n)=n$ và $r(m, 2)=m$ và từ bất đẳng thức (1), chúng ta thu được $r(3, 3) \leqslant r(2, 3)+r(3, 2)=3+3=6$. Vì vậy, chúng ta đã chứng minh rằng trong bất kỳ đồ thị nào có sáu đỉnh đều có một đồ thị con đầy đủ hoặc đồ thị con trống có ba đỉnh, nhưng bây giờ xét từ những xem xét chung. Thật dễ dàng để đưa ra một ví dụ về một đồ thị có năm đỉnh, trong đó không có đồ thị con trống hay đồ thị con đầy đủ có ba đỉnh (hình 5). Do đó số $r(3; 3)$ là 6.

Những gì chúng ta biết và những gì chúng ta không biết

Độ chính xác của bất đẳng thức (1) là bao nhiêu? Hãy thử sử dụng nó để nhận được sự chấp thuận của Gromozeki. Chúng tôi có:

$$r(3, 4) \leqslant r(2, 4)+r(3, 3)=4+6=10.$$

Bắn nhầm! Cuối cùng, Gromozeka đã chứng minh rằng $r(3, 4) \leqslant 9!$ Hóa ra nếu các số $r(m-1, n)$ và $r(m, n-1)$ là số chẵn thì bất đẳng thức là đúng

$$r(m, n) \leqslant r(m-1, n)+r(m, n-1)-1.$$

Chứng minh tương tự như (1), bạn chỉ cần xét rằng không tồn tại một đồ thị có $r(m-1, n)+r(m, n-1)-1$ đỉnh, trong đó mỗi đỉnh được nối chính xác với $r(m-1, n)-1$ đỉnh.

Bài tập 4. Chứng minh bất đẳng thức (2).

Lưu ý rằng bất đẳng thức (2) có thể được đưa ra dạng thuận tiện này: nếu $r(m-1, n) \leqslant A$ và $r(m, n-1) \leqslant B$, trong đó $A$ và $B$ là số chẵn thì $r(m, n) \leqslant A+B-1$.

Nhận được bất đẳng thức (2), phát biểu của Gromozeki có thể được chứng minh bằng một dòng:

$$r(3, 4) \leqslant r(2, 4)+r(3, 3)-1=4+6-1=9.$$

hình 6 hiển thị một đồ thị có tám đỉnh, trong đó không có đồ thị con hoàn chỉnh nào có ba đỉnh cũng như không có đồ thị con trống nào có bốn đỉnh. Do đó số $r(3, 4)$ là 9.

Chúng tôi đã lưu ý rằng đối với $m$ và $n$ lớn hơn 2, công thức chính xác cho số $r(m, n)$ vẫn chưa được biết. Hơn nữa, giá trị chính xác của con số này chỉ được biết đối với một số $m$ và $n$ nhỏ.

Chúng tôi cung cấp một bảng trong đó, xin vui lòng, tất cả những gì đã biết trên đĩa đều được thu thập

Thông tin hôm nay về ý nghĩa của $r(m, n)$. (Giá trị của $r(9, 3)=36=r(3, 9)$ được tìm thấy gần đây bằng máy tính. Tuy nhiên, giá trị chính xác của số $r(3, 8)$ vẫn được biết đến.)

Dễ dàng nhận thấy rằng bảng này đối xứng với một trong các đường chéo. Điều này không phải ngẫu nhiên: với mọi $m$ và $n$ thì công thức $r(m, n)=r(n, m)$ là đúng.

Bài tập 5. Chứng minh công thức này.

Bây giờ chúng ta đã sẵn sàng để bắt đầu

Lời giải bài toán M1099

Trong phi đội chuẩn bị đón sao Hỏa có 6.783 phi hành gia,

⟦folio 55⟧

Điều được biết là trong số bốn bất kỳ trong số chúng, ba có thể được chọn để tạo thành một thí nghiệm phức tạp cho mô-đun cuối cùng. Chứng minh rằng có thể chọn được 5 phi hành gia, ba người bất kỳ tạo thành một phi hành đoàn phức tạp.

Người đọc có lẽ đã bị thuyết phục về tính hữu ích của việc khái quát hóa. Bây giờ chúng ta hãy tạm dừng sử dụng dữ liệu cụ thể của bài toán M1099 và xem xét nó “nói chung”.

Đặt $m$ và $n$ là các số tự nhiên lớn hơn 2. Hãy biểu thị bằng $R(m, n)$ số tối thiểu có tính chất là trong bất kỳ đội nào gồm $R(m, n)$ nhà du hành vũ trụ, người ta có thể chọn $m$ một số nguyên hoặc $3$ trong đó tạo thành một phi hành đoàn phức tạp hoặc $n$ một số nguyên, không có số nào trong số đó $3$ làm được không tạo thành một vận chuyển phức tạp. Người đọc có thể mong đợi chúng tôi định dạng lại bài toán này bằng ngôn ngữ biểu đồ và trích xuất thông tin liên quan từ các kết quả trước đó. Nhưng lần này anh sẽ sai. Các số $R(m, n)$ không liên quan trực tiếp đến đồ thị, mặc dù chúng có một số liên quan đến các số $r(m, n)$.

Trước hết, chúng ta có thể hiểu rằng với mọi $m$ và $n$ các đẳng thức đều đúng:

$$R(3, n) = n, \quad R(m, 3) = m, \quad R(m, n) = R(n, m),$$

tương tự như các đẳng thức nêu trên đối với các số $r(m, n)$.

Bài tập 6. Chứng minh các đẳng thức này.

Vì có sự tương đồng giữa các số $R(m, n)$ và $r(m, n)$, nên chúng ta có thể kỳ vọng rằng các số $R(m, n)$ có ​​thể được ước tính bằng cách sử dụng các số $R(m-1, n)$ và $R(m, n-1)$ giống như cách chúng ta ước tính các số $r(m, n)$, sử dụng bất đẳng thức (1). Thật vậy, bất đẳng thức đúng

$$R(m, n) \leq r(R(m-1, n), R(m, n-1)) + 1. \quad (3)$$

Chứng minh của ông tương tự như chứng minh bất đẳng thức (1). Chúng ta cần chứng minh rằng trong bất kỳ đội $r(R(m-1, n), R(m, n-1)) + 1$ phi hành gia nào sẽ có $m$ một số nguyên, trong đó có số phức hoặc $n$ một số nguyên, không có

⟦folio 56⟧

$$R(5, 4) \leq r(R(4, 4), R(5, 3)) + 1.$$
Số $R(5, 3)$ là 5 và để ước tính $R(4, 4)$ chúng ta áp dụng lại (3):
$$R(4, 4) \leq r(R(3, 4), R(4, 3)) + 1 = r(4, 4) + 1.$$
Số $r(4, 4)$ có thể được ước tính bằng cách sử dụng (1). chúng tôi nhận được
$$r(4, 4) \leq r(3, 4) + r(4, 3) = 9 + 9 = 18.$$
(Trên thực tế, như bảng hiển thị, 18 là giá trị chính xác của $r(4, 4)$.) Vì vậy, $R(4, 4) \leq 19$ và $R(5, 4) \leq r(19, 5) + 1$. Vẫn còn phải ước tính số $r(19, 5)$. Điều này có thể được thực hiện bằng cách áp dụng lặp lại các bất đẳng thức (1) và (2):
$$r(5, 3) \leq r(4, 3) + r(5, 2) = 9 + 5 = 14,$$
$$r(6, 3) \leq 14 + 6 - 1 = 19,$$
$$r(7, 3) \leq 19 + 7 = 26,$$
$$r(8, 3) \leq 26 + 8 - 1 = 33,$$
v.v., lên tới $r(19, 3)$; nó sẽ trở thành $r(19, 3) \leq 182$.
Sau đó chúng tôi viết:
$$r(4, 4) \leq r(3, 4) + r(4, 3) = 9 + 9 = 18,$$
$$r(5, 4) \leq 18 + 14 - 1 = 31,$$
$$r(6, 4) \leq 31 + 19 = 50,$$
... ...
$$r(19, 4) \leq 1249;$$
$$r(5, 5) \leq r(4, 5) + r(5, 4) = 31 + 31 = 62,$$
$$r(6, 5) \leq 62 + 50 - 1 = 111,$$
... ...
$$r(19, 5) \leq 6782.$$
Vì vậy, $R(5, 4) \leq 6783$.
Ước tính $R(5, 4) \leq 6783$ không chính xác. Nếu chúng ta sử dụng giá trị của các số $r(m, n)$ từ bảng đã cho trước đó, thì bằng cách lập luận theo cách hoàn toàn tương tự, chúng ta có thể đạt được ước tính tốt hơn đáng kể: $R(5, 4) \leq 6337$. Các tác giả đã có thể chứng minh rằng $R(5, 4) \leq 6242$, nhưng họ không biết liệu ước tính này có chính xác hay không.

**Định lý Ramsey**

Bắt đầu với những thông điệp đơn giản, chúng tôi phát hiện ra rằng chúng là hệ quả của một số định luật tổng quát: bất đẳng thức (1) và (3). Những mẫu này cho phép chúng tôi giải bài toán M1099. Nhưng hóa ra bản thân chúng chỉ là những trường hợp một phần của một kết quả thậm chí còn tổng quát hơn được nhà logic học người Anh F. Ramsey (1903-1930) thu được vào năm 1930. Để xây dựng định lý Ramsey, chúng ta hãy tưởng tượng rằng không phải 5, mà là $m$ mọi người cần được đưa lên một chuyến bay tới Sao Hỏa, trong đó không phải 3, mà là $s$ sẽ được rời đi, tạo thành một phi hành đoàn phức tạp cho mô hình hạ cánh. Chúng ta hãy biểu thị bằng $R(s; m, n)$ số lượng vũ trụ tối thiểu mà từ đó chúng ta có thể chọn $m$ những người sao cho bất kỳ $s$ nào trong số họ tạo thành một thí nghiệm phức tạp. Rõ ràng là tại $s=3$ số $R(s; m, n)$ trùng với số $R(m, n)$; cũng dễ dàng báo cáo rằng ở $s=2$ con số này bằng với con số $r(m, n)$.

Bài tập 7. Kiểm tra xem $R(1; m, n) = m + n - 1$.

Bây giờ chúng ta đặt câu hỏi: với mọi s thì số $R(s; m, n)$ có tồn tại không? Và nếu nó tồn tại thì nó được tìm thấy như thế nào? Định lý Ramsey trả lời những câu hỏi này. Số $R(s; m, n)$ tồn tại với mọi s và với mọi m ≥ và n ≥. Điều này có thể được ước tính bằng cách sử dụng bất đẳng thức

$$R(s; m, n) \leq R(s - 1);$$
$$R(s; m - 1, n), R(s; m, n - 1)) + 1.$$

Bất bình đẳng (4) rất giống với bất bình đẳng (3). Về cơ bản nó chứng minh điều tương tự. Bạn chỉ cần xem xét không phải các cặp khoảng trắng mà là một ekppage gồm $s-1$ khoảng trắng. Rõ ràng rằng bất đẳng thức (1) và (3) là trường hợp một phần của bất đẳng thức (4) cho $s=2$ (bạn cần xét Bài tập 7) và $s=3$ của bất đẳng thức tương ứng. Định lý Ramsey có nhiều ứng dụng trong nhiều lĩnh vực toán học: logic toán học và lý thuyết số, đại số và tổ hợp, hình học và thậm chí cả lập trình. Các ứng dụng này là một cuộc thảo luận riêng biệt, nhưng ở đây, như một ví dụ về cách áp dụng định lý Ramsey, chúng tôi chỉ trình bày một kết quả tao nhã, thuộc về công trình toán học của P. Erdős và D. Szekeres.

Định lý Erdős-Szekeres. Với mọi số tự nhiên
