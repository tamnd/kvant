---
id: 1981-12-gurevich-sistemyi-raznovesov-0ce798e5
issue: kvant_1981_12
year: 1981
number: "12"
title: Hệ thống cân
authors:
  - Гуревич Г. А.
rubric: zadachnik-kvanta
rubric_sub: Задачник «Кванта»
page_first: 36
page_last: 37
page_labels: 34-35
tag: P9P3
lang: vi
source: kvant_digital
extraction: vision
content_sha256: 2c3be7d479213ccaff59d6213f75d3e8e9580ab36ca7f188ff83668a9b480095
prompt_sha256: draft-1
translated_from: content/ru/1981/12/articles/09_gurevich-sistemyi-raznovesov-0ce798e5.md
source_content_sha256: 274f86adf89fc9e8fb6c9c6f1dc47c38e9907a6329eadd5dc1dfe3d2c56747a8
translation_model: draft
translation_run: vi-draft-2026-10-31
translation_quality: draft
---

⟦folio 34⟧

G. Gurevich

Hệ thống cân

vấn đề của Erdem

Hệ trọng số là một tập hợp các số tự nhiên không thể rút ra hai tập hợp khác nhau có cùng một tổng (ví dụ: các số 1, 3, 7, 20 tạo thành một hệ trọng số nhưng các số 1, 2, 3, 4, 5, 8 không tạo thành: 2+3+4=8+1).

Năm 1956, nhà toán học nổi tiếng người Hungary P. Erdem đã đưa ra bài toán sau: Tìm số tự nhiên nhỏ nhất m(k) sao cho từ các số tự nhiên không vượt quá m(k) chọn được hệ trọng số của k số.

Theo một nghĩa nào đó, một bài toán hình tượng khác của Erdem bài toán là tìm số trọng số l(N) lớn nhất trong số các số không vượt quá một số tự nhiên N cho trước.

Mặc dù có sự quan tâm lớn do các vấn đề đặt ra của các chuyên gia về lý thuyết số, lý thuyết mã hóa và phân tích tổ hợp nhưng chúng vẫn chưa được giải quyết hoàn toàn. Chỉ có một số ước tính về các số m(k) và l(N) được thu thập, và câu hỏi về độ chính xác của những ước tính này vẫn còn bỏ ngỏ.

Trong bài toán M675 (“Quant”, 1981, số 3), chúng tôi đã mời độc giả thu thập một số ước tính liên quan đến bài toán Erdem cho k và N cụ thể. Cụ thể, chúng tôi đề xuất chứng minh rằng từ các số nhỏ hơn 1000, có thể chọn một hệ trọng số a) gồm 10 số; b) từ 11 số; c) trong 14 số không chọn được một số nào; f) nếu các số tạo thành một hệ trọng số thì tổng giá trị hình của chúng sẽ không vượt quá 5/2. Và cuối cùng, chúng tôi đề xuất e) từ các số nhỏ hơn 700, chọn hệ trọng số gồm 11 số.

Ước tính từ trên

Một số cận trên thô của số m(k) có thể thu được từ những xem xét rất đơn giản.

Trên thực tế, k số 1, 2, ..., 2^{k-1} tạo thành hệ trọng số cho mọi số tự nhiên k.

Bài tập 1. Chứng minh điều đó.

Do đó, ước tính, m(k) 2^{k-1}. Cụ thể, từ các số 1, 2, ..., 1000, hệ trọng số được phân biệt với 10 số 1, 2, ..., 2^9 = 512. Điều này cho ra lời giải điểm a) bài toán M675.

Một hệ trọng số có thể dễ dàng xây dựng từ 11 số, không quá 1000.

Trên thực tế, k các số 3, 3·2, 3·2^2, ..., 3·2^{k-1} cũng tạo thành hệ trọng số.

Sovv. Hãy cộng hai số 3·2^{k-1} - 1 và 3·2^{k-1} + 1 với chúng và chứng minh rằng các số thu được cũng tạo thành hệ trọng số.

Nếu bất kỳ tập hợp số nào chứa cả hai số được cộng (khi đó tập hợp các số còn lại không chứa chúng), thì tổng của nó không nhỏ hơn 3 2^k, và do đó, lớn hơn tổng của tất cả các số khác.

Nếu bất kỳ tập hợp nào chứa một số được thêm vào thì bất kỳ tập hợp nào không chứa số đó sẽ có tổng mà khi chia cho 3 sẽ có số dư khác với số dư khi chia cho 3 bằng tổng của tập hợp ban đầu.

Với k=9, chúng ta thu được hệ có trọng số 3, 6, 12, ..., 767, 768, 769 từ 11 số (điều này mang lại lời giải của điểm 6)).

Vì vậy, m(11) ≤ 769. Nói chung, chúng ta thu được ước tính m(k) 3 2^{k-2} + 1.

Điểm

Bây giờ chúng ta thử ước tính số m(k) có kích thước. Đặt a₁ < a₂ < ... < aₖ là một hệ trọng số của k số (k>1).

Rõ ràng là ka_k - 1 ≥ a₁ + a₂ + ... + aₖ. Vì hai tập hợp số bất kỳ có tổng khác nhau và tổng số của tập hợp k số là 2^k - 1, nên chúng ta thu được bất đẳng thức a₁ + a₂ + ... + aₖ ≥ 2^k - 1.

Bài tập 2. Hãy chắc chắn về điều này.

Do đó ka_k ≥ 2^k, tức là a_k ≥ 2^k/k. Cụ thể, với k=14, chúng ta nhận được a₁₄ ≥ 2^14/14 > 1000. Điều này cho ra lời giải từ b).

Vậy m(k) ≥ 2^k/k.

Bây giờ chúng ta có thể ước tính tổng $\frac{1}{a_1} + ... + \frac{1}{a_k}$. Vì bất kỳ hệ trọng số nào bản thân nó cũng là một hệ trọng số, nên bất đẳng thức a_i ≥ $\frac{2^i}{i}$ đúng với mọi i lớn hơn 1. Do đó

$$\frac{1}{a_1} + \frac{1}{a_2} + ... + \frac{1}{a_k} \leq 1 + \frac{2}{2^2} + \frac{3}{2^3} + ... + \frac{k}{2^k}.$$

Hãy tính tổng S(k) = $\frac{2}{2^2} + ... + \frac{k}{2^{k-1}}$ và do đó,

$$S(k) = 2S(k) - S(k) = 1 + \frac{1}{2^2} + \frac{1}{2^3} + ... + \frac{1}{2^{k-1}} - \frac{k}{2^k} = \frac{3}{2} - \frac{k+2}{2^k} < \frac{3}{2}.$$

Như vậy,

$$\frac{1}{a_1} + \frac{1}{a_2} + ... + \frac{1}{a_k} < \frac{5}{2},$$

- khẳng định ở điểm d) cũng đã được chứng minh.

Gần đây (1977), các nhà toán học Mỹ F. Hanson, J. Steele và F. Stepger đã chứng minh một bất đẳng thức mạnh hơn:

$$\frac{1}{a_1^2} + \frac{1}{a_2^2} + ... + \frac{1}{a_k^2} < \frac{2^s}{2^{s-1}}$$

với mọi s > 0. Đặc biệt, với s=1

⟦folio 35⟧

Hãy tỏa sáng

$$\frac{1}{a_1} + \dots + \frac{1}{a_k} < 2.$$

Một số quan sát

Các số 1, 2, 4, ..., 512, như chúng ta đã thấy, tạo thành một hệ gồm 10 trọng số. Hãy xem liệu có thể sử dụng hệ thống này để thu được hệ thống có trọng số gồm 11 số nhỏ hơn 1000 hay không.

Xét 11 số: 999-0, 999-1, ..., 999-512. Hãy chứng minh rằng đây là một hệ trọng số.

Chúng ta sẽ gọi tiếp diin của một tập hợp số đếm trong tập hợp này.

Trước hết, rõ ràng là hai bộ có cùng độ dài có tổng khác nhau (chúng ta trừ 0 và các số từ 999; đưa ra hệ thống trọng số).

Bây giờ chúng ta hãy chứng minh rằng tập dài hơn có tổng lớn hơn.

Trên thực tế, tổng của sáu số nhỏ nhất trong hệ thống: (999-512) + (999-256) + ... + (999-16) lớn hơn tổng của năm số lớn nhất trong số này: 999 + (999-1) + (999-2) + (999-4) + (999-8).

Bây giờ, hãy đặt $a_1, a_2, ..., a_m$ và $b_1, b_2, ..., b_l$ là hai bộ số của chúng ta và $m > l$. Nếu $m > 6$ thì $a_1 + ... + a_m$ là rất nhiều, nhiều hơn $b_1 + ... + b_l$. Nếu $m \leq 6$, thì $a_1 + ... + a_m$ không nhỏ hơn tổng $m$ của các số nhỏ nhất trong hệ thống của chúng tôi, đến lượt nó lại lớn hơn tổng $l$ ($l < m$) của các số lớn nhất trong hệ thống (hãy đảm bảo điều này!); tất nhiên số tiền cuối cùng không ít hơn $b_1 + ... + b_l$.

Vì vậy, chúng ta đã xây dựng được một hệ trọng số khác gồm 11 số nhỏ hơn 1000.

Chúng ta hãy phân tích bằng chứng.

Trước hết, chúng tôi lưu ý rằng cùng với số 999, chúng tôi có thể lấy bất kỳ số $a$ nào mà $a + (a-1) + (a-2) + (a-4) + (a-8) < (a-16) + ... + (a-512)$, tức là bất kỳ $a > 512 + ... + 16 - 8 - 4 - 2 - 1 = 993$ nào.

Ngoài ra, chúng tôi đã lợi dụng thực tế là tổng của các tập hợp có cùng độ dài là khác nhau.

Hãy thử tóm tắt những quan sát của chúng tôi. Lấy $k$ số tự nhiên $a_1 < a_2 < ... < a_k$ mà tổng của hai tập hợp bất kỳ có cùng độ dài là khác nhau.

Bây giờ, nếu $k$ chẵn ($k = 2l$), hãy chọn số $a$ sao cho bất đẳng thức $(a - a_{2l}) + ... + (a - a_l) > (a - a_{l-1}) + ... + (a - a_1) + a$ được thỏa mãn và nếu $k$ là lẻ ($k = 2l+1$), thì bất đẳng thức $(a - a_{2l+1}) + ... + (a - a_{l+1}) > (a - a_{l-1}) + ... + (a - a_1) + a$.

Các số $a, a - a_1, ..., a - a_k$ được xây dựng theo cách này tạo thành một hệ trọng số có độ dài $k+1$. Bài tập 3.

3. Chứng minh tuyên bố này.

4. Chứng minh rằng trong hai tập hợp có cùng độ dài, gồm các số khác nhau của hệ được xây dựng, tập hợp chứa tổng các số nhỏ nhất có tổng lớn hơn.

Cải thiện hệ thống cân nặng

Sử dụng phương pháp được mô tả, chúng ta có thể xây dựng các hệ trọng số có độ dài bất kỳ $k$.

Trước tiên chúng ta hãy xây dựng một dãy số $a_1 < a_2 < ... < a_n < ...$ thỏa mãn mối quan hệ sau:

$$a_1 = 0, a_2 = 1,$$

$$a_{2n+1} = (a_{n+1} + a_{n+2} + ... + a_{2n}) - (a_1 + a_2 + ... + a_{n-1}) + 1,$$

$$a_{2n+2} = (a_{n+1} + a_{n+2} + ... + a_{2n+1}) - (a_1 + a_2 + ... + a_n) + 1$$

tại $n \geq 1$.

Hãy viết ra các số hạng giống nhau đầu tiên của dãy này: 0, 1, 2, 4, 7, 13, 24, 46, 88, 172, 337.

Hãy đặt $a = (a_{11} + a_{10} + ... + a_6) - (a_5 + a_4 + a_3 + a_2 + a_1) + 1 = 667$.

Theo những gì đã được chứng minh trước đó, ta thu được hệ trọng số gồm 11 số: 667, 667-1, 667-2, ..., 667-337. Tất cả những số này đều nhỏ hơn 700. Kết quả là lời giải của phần e) bài toán Bài tập 5. Chứng minh rằng $m(6) = 24$.

Hệ thống Conver-Guy

Trong số tất cả các hệ trọng lượng hiện được biết đến, hệ thống do các nhà toán học người Mỹ Conver và Guy xây dựng được tuyên bố là “người giữ kỷ lục”. Đặc biệt, đối với trọng số của 11 số thì số lớn nhất của chúng là 594.

Công trình do Conver và Guy đề xuất như sau (xem bảng):

| $n$ | 0 | 1 | 2 | 3 | 4 | 5 | 6 | 7 | 8 | 9 | 10 | 11 | 12 |
| :--- | :--- | :--- | :--- | :--- | :--- | :--- | :--- | :--- | :--- | :--- | :--- | :--- | :--- |
| $x_n$ | 0 | 1 | 2 | 3 | 3 | 3 | 4 | 4 | 4 | 4 | 5 | 5 | 5 |
| $y_n$ | 0 | 0 | 0 | 1 | 1 | 2 | 3 | 3 | 4 | 5 | 6 | 6 | 7 |
| $z_n$ | 0 | 1 | 2 | 4 | 7 | 13 | 24 | 44 | 81 | 161 | 309 | 594 | 1161 |

Hàng đầu tiên của bảng chứa số 0 và số tự nhiên; ở dòng thứ hai có một chuỗi $(x_n)$ trong đó bất kỳ số $k > 0$ nào xuất hiện đều bằng $k$ lần; ở dòng thứ ba - chuỗi $(y_n)$, thu được bằng cách trừ các số của dòng thứ hai cho các số của dòng đầu tiên $(y_n = n - x_n)$. Trình tự $(z_n)$ được đưa ra lặp lại: $z_0 = 0$, $z_1 = 1$, $z_{n+1} = 2z_n - z_{n-1}$. (Ví dụ: để tính $z_7$, bạn sẽ lấy $z_6 = 24$, nhân nó với 2 và trừ $z_3 = 4$ vì $y_6 = 3$.) Chuỗi $(z_n)$ được viết ở hàng cuối cùng của bảng. Bài tập 6. Chứng minh rằng $x_n = (\sqrt{2n})$, trong đó $(x)$ là số nguyên gần nhất với $x$.

Converya và Guya đã đưa ra giả thuyết rằng với bất kỳ $n > 0$ nào, các số $a_0 = z_n - z_0$, $a_1 = z_n - z_1$, ..., $a_{n-1} = z_n - z_{n-1}$ tạo thành hệ thống trọng số và kiểm tra nó cho tất cả $n \leq 40$. (Với $n = 11$, ta thu được hệ trọng số sau: 594, 593, 592, 590, 587, 581, 570, 550, 510, 473, 285; như chúng ta thấy, số lớn nhất ở đây là 594.).

Năm 1974, nhà toán học Ấn Độ H. Gupta đã chứng minh tính đúng đắn của giả thuyết Conver-Guy và từ đó thu được ước tính cho số $m(k)$: $m(k) \leq z_k$. Gần đây hơn, nhà toán học Liên Xô V.D. Yokovelev độc lập thu được một bằng chứng khác.

Mỗi $n$ đều rất thú vị khi tìm một ví dụ về hệ trọng số từ các số $n$, trong đó số lớn nhất sẽ cho thấy rằng quy trình lấy hệ trọng số Conver-Guy vẫn chưa phải là tốt nhất.
