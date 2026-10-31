---
id: 1978-5-dubrovskiy-v-poiskah-opredeleniya-ploschadi-poverhnosti-ed33b536
issue: kvant_1978_5
year: 1978
number: "5"
title: Đi tìm định nghĩa về diện tích bề mặt
authors:
  - Дубровский В. Н.
rubric: po-stranitsam-shkolnyh-uchebnikov
rubric_sub: По страницам школьных учебников
page_first: 33
page_last: 34
page_labels: 31-32
tag: PQ9H
lang: vi
source: kvant_digital
extraction: vision
content_sha256: f596084e8aaf1a31a3ec1fc7672c27c146e9699e4eb910391a2bdc92ec4ed1fa
prompt_sha256: draft-1
translated_from: content/ru/1978/05/articles/09_dubrovskiy-v-poiskah-opredeleniya-ploschadi-poverhnosti-ed33b536.md
source_content_sha256: 51f0b2b218d38085fd9c43e366ac7fcc3d83c19bf2027b4143113dba822b929a
translation_model: draft
translation_run: vi-draft-2026-10-31
translation_quality: draft
---

⟦folio 31⟧

Trong định nghĩa của Nhật Bản về diện tích bề mặt

Xác định diện tích của một bề mặt là một trong những chủ đề truyền thống khó trong hình học phổ thông. Điều này là do thiếu một định nghĩa chung hoàn toàn đơn giản có thể bao trùm ít nhất tất cả các bề mặt được nghiên cứu ở trường: hình trụ, hình nón và hình cầu. Phần thay thế xem xét hai cách tiếp cận đối với các định nghĩa đó và thảo luận về những khó khăn gặp phải trong các cách tiếp cận này.

Mọi thứ có thể được triển khai?

Cách dễ nhất là xác định và tính diện tích các bề mặt của hình trụ và hình nón - chỉ cần xem xét sự phát triển của các bề mặt này (xem “Hình học 8”, đoạn 127, 128). Tuy nhiên, định nghĩa diện tích của một bề mặt là diện tích phát triển của nó không phù hợp như một định nghĩa chung đơn giản vì có quá ít bề mặt có thể “mở ra”. Chúng tôi sẽ giải thích tại sao phạm vi không thể được “mở rộng”; Lý luận tương tự được áp dụng cho nhiều bề mặt quay khác.

Hãy đưa ra một định nghĩa chính xác về quét - đó là một vấn đề khá rắc rối. Tuy nhiên, rõ ràng là nếu có thể “mở ra” hình cầu, thì đặc biệt, chúng ta sẽ thu được ánh xạ $f$ của một số “nắp hình cầu” khá nhỏ trên một phần của mặt phẳng (Hình 1), trong đó độ dài của bất kỳ đường cong $L$ nào nằm trên “nắp” này sẽ bằng độ dài của đường cong tương ứng $f(L)$ trên mặt phẳng. Cụ thể, độ dài $d(A, B)$ của các điểm nối đường cong ngắn nhất $A$ và $B$ trên mặt cầu phải bằng độ dài của các điểm nối đường cong ngắn nhất $A'=f(A)$ và $B'=f(B)$ trên mặt phẳng, tức là độ dài của đoạn $A'B'$:

$$d(A, B) = |A'B'|.$$

Có thể chứng minh rằng $d(A, B)$ là độ dài của đường tròn nhỏ hơn trong hai đường tròn còn lại đi qua các điểm $A$ và $B$ được xác định bởi các điểm này, nhưng chúng ta sẽ không cần đến điều này.

Hãy xem xét tập hợp $C$ các điểm $M$ của một hình cầu mà “khoảng cách hình cầu” $d(M, P)$ từ một điểm cố định nào đó $P$ bằng một số cố định $R>0$. Rõ ràng, nếu điểm $M_1$ thu được từ điểm $M$ bằng cách lặp lại đường kính của hình cầu đi qua $P$, thì $d(M_1,P)=d(M,P)$. Từ đây dễ dàng suy ra (rút ra!) rằng tập $C$ là một đường tròn. Tâm của nó $O$ trùng với đáy của đường vuông góc, hướng xuống dưới

Hình 1. Không thể mở được một quả cầu.

⟦folio 32⟧

Hình 2. Dãy các đường đứt nét $l_n$ hội tụ thành một đoạn có độ dài đơn vị (nhưng không ghi trong đó), độ dài mỗi đoạn bằng $\sqrt{2}$.

kéo dài từ điểm bất kỳ $M \in C$ đến bán kính của hình cầu đi qua điểm $P$ (Hình 1); do đó bán kính của hình tròn này là $r = |OM| < |MP|$. Mặt khác, $d(M,P)$ là độ dài của một số đường cong nối $M$ và $P$, và đoạn $MP$ là đoạn ngắn nhất trong số các đường cong đó; do đó $|MP| \leq d(M,P) = R$. Vì vậy, $r < R$. Khi mở hình tròn, $C$ sẽ đi vào tập hợp gồm $C' = f(C)$ điểm cách xa điểm $f(P)$ ở khoảng cách $R$, tức là đi vào một hình tròn có bán kính $R$. Độ dài của hình tròn $C$ là $2\pi r$ và chu vi $C' = 2\pi R > 2\pi r$. Điều này mâu thuẫn với tính chất bảo toàn chiều dài được phát biểu ở trên, và do đó việc hình thành một hình cầu là không thể.

Sanor Schwartz

Vì vậy, nói chung, không thể bộc lộ bề mặt; cố gắng xây dựng khác nhau. Xét một dãy các bề mặt đa diện $\Pi_n$ “hội tụ” về một bề mặt cho trước $\Pi$. Giả sử rằng dãy diện tích $S_n$ của chúng có giới hạn $S$; thì việc lấy số $S$ làm diện tích bề mặt $\Pi^*$ là điều đương nhiên. Tất nhiên, phải thận trọng trong trường hợp này - xét cho cùng, ngay cả khi xác định độ dài của một đường cong, họ coi không phải là tùy tiện mà là các đường đứt đoạn được mô tả (chúng tương ứng với các bề mặt đa diện) hội tụ vào đường cong, nếu không thì giới hạn độ dài của chúng sẽ phụ thuộc vào việc lựa chọn chuỗi các đường đứt nét (xem Hình 2 và bài toán 3). Chúng ta hãy thử tìm diện tích bề mặt của một hình trụ là giới hạn của diện tích các bề mặt đa diện nội tiếp trong đó. Chúng tôi xác định các bề mặt này như sau.

Chúng ta hãy khắc một $n$-giác đều ở đáy của hình trụ; Chúng ta hãy xem xét thêm $n$-giác nằm phía trên đáy ở độ cao $\frac{H}{k}$, trong đó $H$ là chiều cao của hình trụ, $k$ là một số tự nhiên cố định và xoay nó so với $n$-giác đầu tiên một góc $\frac{\pi}{n}$.

Tiếp tục cách xây dựng này, chúng ta thu được $(k+1) \cdot n$ điểm - các đỉnh của $n$-giác: chúng ta nối các đỉnh này với các cạnh, như trong Hình 3. Kết quả là, một bề mặt đa diện $\Pi(n,k)$ nội tiếp trong hình trụ được hình thành, có $nk$ các mặt tam giác bằng nhau. Bằng cách thiết lập khác nhau

*) Cách tiếp cận này đã được A.P. Kiselev sử dụng trong sách giáo khoa hình học cũ khi xác định diện tích bề mặt của hình trụ và hình nón.

Hình 3. “Sanor Schwartz” (P (6, 4)).
