---
id: 1985-7-chvanov-zadacha-o-dominirovanii-ferzey-33f9bc6f
issue: kvant_1985_7
year: 1985
number: "7"
title: Bài toán về sự thống trị của nữ hoàng
authors:
  - Чванов В. Г.
rubric: igry-i-golovolomki
rubric_sub: Игры и головоломки
page_first: 62
page_last: 64
page_labels: 60-62
tag: 24HD
lang: vi
source: kvant_digital
extraction: vision
content_sha256: 6fd67887dd009d8724b9d4265ce401c295717017ef3bb05801809391bbcd8d53
prompt_sha256: draft-1
translated_from: content/ru/1985/07/articles/17_chvanov-zadacha-o-dominirovanii-ferzey-33f9bc6f.md
source_content_sha256: 3745b926816893366d3269346f6e14018c88ede7457e3bf6ed8de9c88d656dd3
translation_model: draft
translation_run: vi-draft-2026-10-31
translation_quality: draft
---

⟦folio 60⟧

Bài toán về việc nội trợ của nữ hoàng

V. G. CHVANOV

Một bài viết của M. Mamikon năm «Kvant» 1977, số 12 đã xem xét bài toán như sau:

Bài toán về việc nội trợ. Số lượng quân hậu tối thiểu $F(n)$ có thể được đặt trên bàn cờ $n \times n$ để chúng tấn công tất cả các ô trống của nó là bao nhiêu?

Các số $F(n)$ chỉ được biết đến với $n (n \leq 11)$ nhỏ, được cho trong Bảng 1.

Bảng 1

| $n$ | 3 | 4 | 5 | 6 | 7 | 8 | 9 | 10 | 11 | 12 | ... |
| :--- | :--- | :--- | :--- | :--- | :--- | :--- | :--- | :--- | :--- | :--- | :--- |
| $F(n)$ | 1 | 2 | 3 | 3 | 4 | 5 | 5 | 5 | 5 | ? | ... |

TRÊN hình 1 cho thấy vị trí của quân hậu trên bàn cờ $3 \times 3$, $8 \times 8$, $11 \times 11$, vì cái gì $F(n)$ lần lượt bằng 1, 5 và 5. Đối với lớn $n$ nhiệm vụ của anh ấy lời giải.

Bài báo của M. Mamikon cung cấp các ước tính sau cho $F(n)$:

$$F(n) \geq \frac{n-1}{2},$$

$$F(n) \leq \frac{5}{8} n + 16 \sqrt{n}.$$

Mục tiêu của chúng tôi là cung cấp một số ví dụ để cải thiện những ước tính này và hình thành bài toán liên quan với hy vọng rằng người đọc sẽ độc lập nâng cao lời giải bài toán về nội trợ.

Ý tưởng hình học đầu tiên - đục lỗ viền

Vị trí của quân hậu trên bàn cờ $n \times n$, trong đó $F(n) = (n-1)/2$ (giới hạn dưới của M. Mamikon được hiện thực hóa), được gọi là lý tưởng.

Một ví dụ là các vị trí được hiển thị tại hình 1 (tại $n=3$ và $n=11$).

Sau khi áp dụng 4 ô $(n-1)$ nằm dọc theo cạnh của nó. Với một vị trí lý tưởng (xem hình 1a, 6), mỗi quân hậu sẽ có chính xác 8 ô vuông trên mỗi ô vuông này, hình vuông của nó không thể bị hai quân hậu xuyên thủng, vì vậy số lượng quân hậu là 4 $(n-1):8=(n-1)/2$, điều này cho chúng ta ước tính thấp hơn (1). Bằng chứng đầy đủ về điều này có trong bài viết của M. Mamikon.

Bài toán 1 (chưa giải được). Có vị trí lý tưởng nào khác ngoài hai vị trí được liệt kê không? Có số lượng hữu hạn các vị trí lý tưởng không? (Hyotesis: đáp số cho câu hỏi cuối cùng - tích cực.)

Một điều kiện cần thiết cho việc nghiền nhà được đặt là việc nghiền nhà ở biên giới. Vì vậy, thật thú vị khi biết bảng nào có thể làm bài tập về nhà ở biên giới $(n-1)/2$ với quân hậu. M. Mamikon đã chứng minh rằng các bảng như vậy là các bảng $n \times n$ với $n=2(k^2+l^2)+1$, trong đó $k$ và $l$ là các số nguyên tố cùng nhau của các chẵn lẻ khác nhau. Nhưng các bảng cũng không làm cạn kiệt danh sách này. Một ví dụ là vị trí trên hình 2 $(n=15)$; Tôi đã nghĩ ra một vị trí khác như vậy cho bảng $n \times n$, $n=27$. Những vị trí này được sử dụng ở chỗ chúng duy trì sự bằng nhau về số lượng của các vòng sắt chỉ nằm trong các ô vuông đối diện được hình thành bởi giao điểm của các đường chéo chính.

⟦folio 61⟧

Ý tưởng hình học thứ hai là di chuyển quân hậu $k$ ra ngoài hình vuông trung tâm

Hãy xem xét quân hậu $k$ trên hình 4,6 và thay thế bốn quân hậu ở góc bằng hai quân hậu nằm bên ngoài ô vuông trung tâm $m \times m$ ($m=5$) như được hiển thị trong hình 5. Sau đó, chúng ta nhận được một quân hậu $k$ từ các quân $2m-1$ thống trị bàn cờ $3m \times 3m$. Không thể giảm thêm số lượng hình vì hình vuông $m \times m$ có đường chéo $2m-1$.

Tuy nhiên, khi chúng ta di chuyển các quân dọc theo đường chéo của chúng bên ngoài ô vuông trung tâm, hóa ra là có thể có được một quân hậu $k$ thống trị một bàn cờ lớn hơn $3m \times 3m$ bằng cách tăng số lượng cấp bậc và tập tin có thể tấn công (xem hình trên trang bìa thứ tư). Đương nhiên họ sẽ hỏi.

Bài toán 4. Kích thước tối đa của một hình vuông bị thống trị bởi quân hậu $k$ trong số $2m-1$ quân là bao nhiêu?

Tôi không biết đáp số cho câu hỏi này, nhưng từ một loạt $k$-nữ hoàng khác được đưa ra làm ví dụ, cho phép cải thiện đáng kể giới hạn trên cho $F(n)$. Cụ thể, đối với bất kỳ $m$ nào từ chuỗi $m=12c+9$ ($c=0,1,2,...$), người ta có thể tạo ra một quân hậu $k$ từ các quân $2m-1$ thống trị bàn cờ $n \times n$, trong đó $n=42c+31=(7m-1)/2$. Do đó, đối với tất cả $n$ từ chuỗi $n=42c+31$ ($c=0,1,2,...$), chúng ta thu được ước tính

$$F(n) \leq \frac{4n-5}{7}.$$

Lưu ý rằng số lượng chiều dọc (cũng như chiều ngang), cũng như $k$-nữ hoàng, bằng $l=(3m-1)/2$.

Nữ hoàng $k$ hiển thị trên trang bìa là một trong những nữ hoàng $k$ trong loạt bài này (tại $c=0$). Chúng ta hãy xem xét kỹ hơn về nó. Nó bao gồm 3 nhóm số liệu có những lợi thế “mang tính xây dựng” nhất định. Mỗi nhóm, được tách riêng, tấn công theo mọi hướng vào một cột gồm nhiều hàng, bao nhiêu số liệu mà nó chứa. Hơn nữa, theo chiều dọc và một trong các đường chéo

⟦folio 62⟧

Theo hướng chính, các hàng bị tấn công không ngừng, ở hướng khác - hàng thứ ba bị tấn công, theo chiều ngang - mỗi giây. Các nhóm bên ngoài chứa $\frac{2}{3}m-1$, và nhóm ở giữa chứa $\frac{2}{3}m$ quân cờ, được đặt bằng các nước đi hiệp sĩ tuần tự dọc theo các đường song song 1-1, 2-2, 3-3. Đường 1-1 chạy qua ô trung tâm của bàn cờ. Khoảng cách giữa các dòng 2-2, 3-3 và các dòng 1-1 được chọn sao cho bên ngoài bảng $m \times m$ trên 2 mặt của nó (xem hình trên trang bìa) có $\frac{m-1}{4}$ các quân cờ của mỗi nhóm cực đoan. Nhưng đồng thời, một phần hình của mỗi nhóm rời khỏi vùng màu xanh lam và một khoảng trống được hình thành trong đó (hiển thị bằng màu xanh lá cây) theo một đường chéo mở liên tục. Các mảnh rời khỏi vùng màu xanh sẽ được đưa trở lại vùng đó bằng cách chuyển song song dọc theo các đường chéo của chúng để thu hẹp khoảng cách đã hình thành.

Cải thiện giới hạn dưới cho $F(n)$

Bây giờ hãy quay lại ước tính thấp hơn $F(n)$. Nó có thể được cải thiện bằng cách đặt điểm $F(n)$ cho các bảng $n \times n$ so sánh modulo 4.

Bài 5. Chứng minh cho mỗi loại bảng $n \times n$ các ước lượng sau $F(n)$:

$$n = 4k \quad F(n) \geq \frac{n}{2},$$

(4)

Gợi ý. Số ô vuông trên mép bàn cờ có $\frac{n-1}{2}$ quân hậu chiếm ưu thế là bội số của 8; số lượng các hình được sắp xếp lý tưởng $F(n) = 2k+1$.

Bài toán 6. Cho $\frac{n-1}{2}$ các đường chéo dọc, ngang, tăng dần và giảm dần. Chỉ ra tất cả các giá trị $n$ mà có thể gạch bỏ tất cả các ô của bảng $n \times n$ bằng các dòng này (chúng đi qua tâm của các ô).

Vấn đề 7 (chưa giải quyết). Có số lượng bảng hữu hạn để thực hiện ước tính (4), (5), (6) không? Giả thuyết: số lượng bảng như vậy là hữu hạn.

Các ước lượng (4), (5), (6) cho phép chúng ta mở rộng Bảng 1. Thật vậy, khi tính đến chúng, chúng ta có thể viết rằng $F(12) \geq 6$; $F(13) \geq 7$; $F(17) \geq 9$; $F(12)=6$ và $F(13)=7$ có thể dễ dàng có được bằng cách phân phối các vị trí $F(11)=5$ (hình 1 "6") cho các kích cỡ $12 \times 12$ và $13 \times 13$ với một quân cờ bổ sung được đặt ở ô vuông góc của bàn cờ. Vị trí của $F(17)=9$ được hiển thị trên hình 6.

Sẽ rất thuận tiện khi đánh giá “chất lượng” của vị trí thống trị này hoặc vị trí thống trị khác bằng cách sử dụng mối quan hệ $\mu = \frac{F(n)}{n}$. Vì vậy, kết quả của chúng tôi có thể được trình bày dưới dạng Bảng 2.

Bảng 2 đáng được theo dõi, nhưng chúng tôi để lại cho người đọc phân tích. Chúng tôi chỉ lưu ý những điều sau đây rằng bảng $8 \times 8$ là phù hợp và trang trọng nhất để đặt $F(n)$ cho phép chúng tôi trả lời câu hỏi này ngay bây giờ.

Vấn đề 8 (về sự thống trị bên ngoài). Có thể đặt tối đa bao nhiêu quân hậu trên một bàn cờ vô hạn để tất cả các bàn $n \times n$ đều bị tấn công?
