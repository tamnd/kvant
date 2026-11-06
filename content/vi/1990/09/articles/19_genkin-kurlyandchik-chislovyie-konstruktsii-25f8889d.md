---
id: 1990-9-genkin-kurlyandchik-chislovyie-konstruktsii-25f8889d
issue: kvant_1990_9
year: 1990
number: "9"
title: Cấu trúc số
authors:
  - Генкин С. А.
  - Курляндчик Л. Д.
rubric: matematicheskiy-kruzhok
rubric_sub: Математический кружок
page_first: 60
page_last: 62
page_labels: 58-60
lang: vi
source: kvant_digital
extraction: vision
content_sha256: 6ba98f8ffd516d4777407cb8c7e9b124ab86bad0f4005aaabe1636d6bdae8355
prompt_sha256: draft-1
translated_from: content/ru/1990/09/articles/19_genkin-kurlyandchik-chislovyie-konstruktsii-25f8889d.md
source_content_sha256: 72e853c98c990a3c2a07a9b95724da87fb5a5a5c5afc0624189f1052f32cdbcc
translation_model: draft
translation_run: vi-draft-gaps-2026-11-05
translation_quality: draft
---

⟦folio 58⟧

---
running_head:
folio:
---

Cấu trúc số

S.GENKIN,
L. KURLYANDCHIK

Trong bài viết này, hãy giải cùng một cách xây dựng, vật liệu là số tự nhiên. Khi được hỏi liệu cấu trúc được yêu cầu có tồn tại hay không, hai đáp số sẽ xuất hiện: có hoặc không.

Tìm tổng

Bài 1. Có thể chia các số tự nhiên từ 1 đến 21 thành nhiều nhóm, trong đó số lớn nhất bằng tổng của tất cả các số còn lại?

Lời giải. Chúng ta hãy giả sử rằng một phân vùng như vậy là có thể. Rõ ràng tổng các số trong mỗi nhóm là số chẵn (gấp đôi số lớn nhất trong nhóm). Do đó tổng của tất cả các số là số chẵn. Tuy nhiên, 1+2+...+21=21·11 là số lẻ. Điều này có nghĩa là việc phân vùng như vậy là không thể.

Bài toán 2. Có thể chọn năm số nguyên sao cho tổng từng cặp của chúng tạo thành mười số nguyên liên tiếp không?

Lời giải. Giả sử rằng chúng ta đã tìm được năm số như vậy. Gọi s là tổng của tất cả các số này và n là tổng nhỏ nhất trong các tổng theo cặp của chúng. Khi đó tổng mười cặp là các số n, n+1, ..., n+9. Bây giờ hãy tính tổng của tất cả các tổng theo cặp theo hai cách khác nhau. Một mặt, nó bằng n+(n+1)+...+(n+9)=5(2n+9). Mặt khác, nó bằng 4s, vì nó chứa mỗi số ban đầu đúng bốn lần. Do đó 4s=5(2n+9), điều này là không thể. Điều này có nghĩa là không thể chọn được năm số như vậy.

Hãy phân tích lời giải của hai bài toán này. Điểm chính của mỗi người trong số họ là tính toán một số tiền theo hai cách khác nhau. Nhưng với sự trợ giúp của kỹ thuật này, người ta chỉ có thể chứng minh rằng một tập hợp số đã cho không có thuộc tính cụ thể. Tuy nhiên, thường có bài toán trong đó cần phải tìm không chỉ điều kiện cần mà còn phải tìm điều kiện đủ để đáp ứng thuộc tính đã chỉ định.

Bài toán 3. Trong số 1, 2, 3, ..., n+1, một số bị gạch bỏ và các số còn lại được sắp xếp theo thứ tự a₁, a₂, ..., aₙ sao cho tất cả n số |a₁−a₂|, |a₂−a₃|, ..., |aₙ−a₁| là khác nhau. Với n ≥3 như vậy, điều này có thể thực hiện được không?

Lời giải. Đầu tiên là các số a và |a| có cùng độ ngang bằng. Do đó, tổng |a₁−a₂|+|a₂−a₃|+...+|aₙ−a₁| cũng có tính chẵn lẻ, như số (a₁−a₂)+(a₂−a₃)+...+(aₙ−a₁)=0. Vậy tổng này là số chẵn. Mặt khác, |a₁−a₂|, |a₂−a₃|, ..., |aₙ−a₁| - đây là n số tự nhiên khác nhau, không vượt quá n, tức là các số 1, 2, 3, ..., n. Do đó, tổng của chúng là 1+2+...+n=n(n+1)/2 và đây là số chẵn.

Posny n=4k or n=4k−1. Vì vậy, các điều kiện cần thiết đã được tìm thấy. Để chứng minh điều đó, chỉ cần chỉ ra rằng với n như vậy là đủ

⟦folio 59⟧

---
running_head:
folio:
---

các vị trí có thể tồn tại. Chúng được liệt kê ở hình.

Bài toán 4. Số bộ ba số tối đa không có các phần tử chung từng cặp có thể được chọn từ tập hợp các số tự nhiên từ 1 đến $n$ sao cho tổng các số của mỗi bộ ba khác nhau và không vượt quá $n$ là bao nhiêu?

Lời giải. Hãy chọn $k$ bộ ba số. Hãy cộng tất cả các số $3k$ đã chọn và biểu thị tổng kết quả bằng $s$. Rõ ràng là $1+2+\dots+3k \leqslant n+(n-1)+\dots+(n-k+1)$. So, $\frac{3k(3k+1)}{2} \leqslant \frac{(2n-k+1)k}{2}$. Từ đây ta thu được điều kiện cần $k \leqslant \frac{n-1}{5}$.

Vẫn còn phải đưa ra một bộ $\left[ \frac{n-1}{5} \right]$ ba số thỏa mãn điều kiện bài toán. Hãy ký hiệu số $\left[ \frac{n-1}{5} \right]$ bằng $a$ và sắp xếp các số từ 1 đến $3a$ như sau:

1 2 3 ...a-1 a
2a 2a-1 2a-2 ...a+2 a+1
2a+1 2a+2 2a+3 ...3a-1 3a

Các số trong cột đầu tiên tạo thành ba số đầu tiên, các số ở cột thứ hai tạo thành ba số thứ hai, v.v.

Như bạn có thể đã biết, mọi số tự nhiên $n$ đại diện cho-

Số Vischeknuyu $3k$

được đưa ra dưới dạng $n=a_k \cdot 2^k+a_{k-1} \cdot 2^{k-1}+\dots+a_1 \cdot 2+a_0$, nơi các số $a_i$ bằng 0 hoặc 1 và cách biểu diễn như vậy là duy nhất. Hệ thống số kép dựa trên thực tế này, trong đó mọi số tự nhiên đều được viết bằng số một và số không: $n_2=a_k a_{k-1} \dots a_0$. Ví dụ, $1_2=1$, $2_2=10$, $3_2=11$, $4_2=100$, $5_2=101$, $6_2=110$, $7_2=111$, vân vân.

Trước khi hình thành bài toán tiếp theo, chúng tôi giới thiệu ký hiệu sau: $N_0$ là tập hợp các số tự nhiên, bổ sung bằng 0.

Bài toán 5. Xây dựng hai tập hợp con vô hạn $A$ và $B$ tập $N_0$ sao cho mỗi số từ $N_0$ được biểu diễn duy nhất dưới dạng tổng $n=a+b$, trong đó $a \in A$, $b \in B$.

Lời giải. Here it is convenient to use double notation of natural numbers. Let's consider two sets $A$ and $B$, devices like this. Bộ $A$ bao gồm số 0 và tất cả các số tự nhiên, được ký hiệu kép trong đó đơn vị là các chữ số lẻ (tính từ bên phải) ($A=\{0,1,4,5,16,17,20,21,\dots\}$). Bộ $B$ bao gồm số 0 và tất cả các số tự nhiên, được ký hiệu kép trong đó đơn vị là các chữ số chẵn (tính từ bên phải) ($B=\{0,2,8,10,32,34,40,42,\dots\}$). It is obvious that any non-negative integer $n$ is uniquely represented as the sum $n=a+b$, where $a \in A$, $b \in B$.

⟦folio 60⟧

---
running_head:
folio:
---

Cấu trúc này cũng là chìa khóa cho lời giải của hai bài toán tiếp theo. Để hình thành chúng, chúng tôi đưa ra một định nghĩa: hai tập con của tập hợp $N_0$ được gọi là đồng dư nếu tập này có thể lấy được từ tập kia bằng hoà sắc với một số nguyên.

Bài toán 6. Chứng minh rằng tập hợp $N_0$ có thể được phân chia thành vô số các tập hợp con đồng dạng vô hạn rời rạc.

Lời giải. Đặt $A$ và $B$ là các tập hợp được xây dựng cho lời giải bài toán 5. Với mỗi số $b \in B$ chúng ta biểu thị bằng $A_b$ là kết quả của sự dịch chuyển của tập hợp $A$ theo số này $b$, tức là $A_b$ là tập hợp các số có dạng $a+b$, ở đâu $a \in A$. Hãy chứng minh rằng tập hợp của tập hợp $A_b$ tạo thành phân vùng cần thiết của tập hợp $N_0$ thành các tập hợp đồng dạng. Vì mỗi số $n$ từ tập hợp $N_0$ được biểu thị dưới dạng tổng $n = a+b$ ($a \in A, b \in B$), nên các tập hợp $A_b$ bao gồm toàn bộ tập hợp $N_0$ và do thực tế đây là cách biểu diễn duy nhất nên các tập hợp này tách rời nhau theo cặp.

bài toán tiếp theo là bài toán M685 từ Sách Vấn đề Lượng tử. Trong số đầu tiên của Lượng tử năm 1982, lời giải không chính xác về bài toán này đã được xuất bản. Chúng tôi sẽ tóm tắt lại lời giải này và sau đó cho bạn biết lỗi là gì cũng như cách khắc phục.

Bài toán 7. Có thể chia tập hợp số tự nhiên thành vô số tập hợp đồng dạng vô hạn được không?

Lời giải. Trong lời giải, được đưa ra trong “Kvanita”, hai bộ $A$ và $B$ được viết ra. Tập hợp $A = \{1, 4, 5, 16, 17, 20, \dots\}$ là tập hợp các số tự nhiên có ký hiệu kép là đơn vị ở vị trí lẻ. Bộ $B = \{0, 2, 8, 10, 32, 34, \dots\}$ là một bộ bao gồm số 0 và các số có ký hiệu kép là đơn vị ở các vị trí chẵn. lời giải phát biểu rằng mọi số tự nhiên $n$ được biểu diễn dưới dạng $n=a+b$, trong đó $a \in A, b \in B$. Trong khi đó, rõ ràng là không có số nào trong tập hợp $B$ có thể được biểu diễn dưới dạng này!

Hãy khắc phục điều này lời giải. Để làm điều này, hãy xem xét các tập hợp $A$ và $B$, được xây dựng tại lời giải bài toán 5. Trong lời giải bài toán 6, chúng ta đã chứng minh rằng các tập hợp $A_b$ tương ứng tạo thành phân vùng bắt buộc của tập hợp $N_0$. Bây giờ chúng ta cùng nhau xem xét các bộ $A$ bộ $A_1$ - dịch chuyển bộ $A$ theo một: $A_1 = \{1, 2, 5, 6, 17, 18, 21, 22, \dots\}$. Rõ ràng là với bất kỳ số $b \in B$ nào thì tập $(A_1)_b$ là tập $A_b$ dịch chuyển một. Do đó, các tập hợp $(A_1)_b$ tạo thành phân vùng bắt buộc của tập hợp số tự nhiên.

Thiết kế bằng cảm ứng

Bài toán 8. Đã cho $n$ các số có khối lượng bằng 1, 2, ..., $n$ gram cho cái nào $n$ Những con số này có thể được chia thành ba nhóm khối lượng bằng nhau?

Lời giải. Rõ ràng là cách xây dựng như vậy (phân hủy thành ba đống) không tồn tại cho tất cả $n$. To do this, it is necessary that the total mass of all digits $1+2+\dots+n = \frac{n(n+1)}{2}$ is divisible by three. Do đó, $n$ hoặc $n+1$ phải chia hết cho ba. Let us now prove that for all such $n \geq 5$ the required construction exists. First, we specify an algorithm for propagating the construction from a set of $k$ digits to a set of $k+6$ digits. Để làm điều này, hãy phân tách sáu số có khối lượng $k+1, k+2, k+3, k+4, k+5, k+6$ thành ba chồng có khối lượng bằng nhau: $(k+1, k+6); (k+2, k+5); (k+3, k+4)$. It remains to show how you can decompose five, eight and nine digits (how to decompose six digits is clear from the previous one). Điều này có thể được nhìn thấy từ bảng sau:

$$
\begin{array}{c c c}
n = 5 & (1, 4); (2, 3); 5 \\
n = 8 & (1, 2, 3, 6); (4, 8); (5, 7) \\
n = 9 & (1, 2, 3, 4, 5); (6, 9); (7, 8)
\end{array}
$$
