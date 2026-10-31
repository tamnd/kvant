---
id: 1970-6-priznaki-delimosti-na-19-i-7-47978b49
issue: kvant_1970_6
year: 1970
number: "6"
title: Dấu hiệu chia hết cho 19 và 7
rubric: smes
page_first: 12
page_last: 12
page_labels: "10"
tag: DB1L
lang: vi
source: kvant_digital
extraction: vision
content_sha256: ad195f843e9881bdfd6a845e1ee923549e2db12a0bf1f5802f374d836087b8e0
prompt_sha256: 3ec6b8aabd9b98576af76503cd8a2902b9f5d18e01ee867dfb1228f59c6d52d8
translated_from: content/ru/1970/06/articles/03_priznaki-delimosti-na-19-i-7-47978b49.md
source_content_sha256: 66151295cbe9c661f1aee872c81d5e45d9ae0e313247b8b93c9e3b2e696b42b5
translation_model: gpt-5-6-mini
translation_run: m10-1970-vi
---

⟦folio 10⟧

13. Các số của dãy cơ sở $q_1, q_2, q_3, \dots$ phải thỏa mãn những điều kiện nào để trong cách ghi số chỉ xuất hiện hai chữ số: 0 và 1? Cần đặt thêm điều kiện nào lên các số $q_1, q_2, \dots$ để khi đó không có hai số một nào đứng liền nhau?

14. Dãy các số

$$q_0 = 1, \quad q_1 = 2, \quad q_2 = 3,$$

$$q_3 = 5, \quad q_4 = 8, \quad q_5 = 13, \dots,$$

trong đó $q_{n+1} = q_n + q_{n-1}$, được gọi là dãy Fibonacci. Hãy chứng minh rằng hệ số “Fibonacci” thỏa mãn tất cả các điều kiện của bài toán trước. Hãy tìm trong hệ này tổng các số

a) $\underbrace{100 \dots 00}_{k} + \underbrace{100 \dots 00}_{l}$;

b) $\underbrace{10101 \dots 01}_{2m+1} + 1$;

c) $\underbrace{10101 \dots 01}_{2m+1} + \underbrace{100 \dots 00}_{2m+1}$.

15. Có thể chia tất cả các số tự nhiên 1, 2, 3, 4, 5, 6, 7, ... thành hai dãy tăng $a_1, a_2, a_3, a_4, \dots$ và $b_1, b_2, b_3, b_4, \dots$ sao cho $b_k - a_k = k$ với mọi $k = 1, 2, 3, \dots$ không?

Sau một số suy nghĩ, tất nhiên các bạn sẽ đoán được cách chọn những dãy như vậy (có thể thực hiện điều này theo một cách duy nhất)

$$\begin{array}{cccccccc}
a_1 & b_1 & a_2 & a_3 & b_2 & a_4 & b_3 & a_5 & a_6 & b_4 & a_7 \\
1 & 2 & 3 & 4 & 5 & 6 & 7 & 8 & 9 & 10 & 11 \\
a_8 & b_5 & c_9 & b_6 & \dots \\
12 & 13 & 14 & 15 & \dots \\
\end{array}$$

Không dễ để thỏa mãn điều kiện tạo thành các cặp $(a_k, b_k)$. Chẳng hạn, làm thế nào biết được 100 thuộc về dãy nào trong hai dãy $-a_k$ hoặc $b_k$, nó tương ứng với số thứ mấy, số nào sẽ đi cùng nó trong cặp (mà không phải viết ra tất cả các $a_k$ và $b_k$ trước đó)?

Hóa ra, để phát biểu quy luật này, cần viết các dãy trên không phải trong hệ thập phân mà trong hệ Fibonacci. Hãy thử phát hiện và chứng minh quy luật đó.

10
