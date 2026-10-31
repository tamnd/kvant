---
id: 1977-4-zadachi-nashih-chitateley-d80e2264
issue: kvant_1977_4
year: 1977
number: "4"
title: Bài toán độc giả của chúng tôi
rubric: smes
page_first: 25
page_last: 25
page_labels: "23"
tag: 8SCS
lang: vi
source: kvant_digital
extraction: vision
content_sha256: 893b06559e41cb9f0dfc0fc6ed21c954befd18a5526fc773bfc44d5e7e9c4668
prompt_sha256: draft-1
translated_from: content/ru/1977/04/articles/08_zadachi-nashih-chitateley-d80e2264.md
source_content_sha256: 3b16dc4764931a13b029522d195f8d4951c21c7b42a79d8c9b0c35114ff53c88
translation_model: draft
translation_run: vi-draft-2026-10-31
translation_quality: draft
---

⟦folio 23⟧

Nếu $v \neq w$ thì sử dụng phép biến đổi
$$\langle v, w \rangle \Rightarrow \langle 2v - w, w - v \rangle$$
Hãy chuyển từ cặp này sang cặp $\langle v_1, w_1 \rangle$ với các thành phần nhỏ hơn. Nếu $v_1 \neq w_1$ thì chúng tôi sẽ thực hiện lại quá trình chuyển đổi này. Nếu $v_2 \neq w_2$, một lần nữa...
Mỗi lần ta sẽ được các cặp số tự nhiên nhỏ hơn. Do đó, sau một số hữu hạn bước, chúng ta sẽ nhận được một cặp $\langle v_l, w_l \rangle$ số giống hệt nhau - theo quy tắc của chúng tôi, quá trình chỉ có thể kết thúc ở một cặp như vậy. Nhưng, như chúng ta đã biết, thì $v_l = w_l = 1$. Bây giờ chúng ta hãy lưu ý rằng các chuyển đổi (*) và (**) nghịch đảo lẫn nhau: nếu $v = 2v - w$, $w = w - v$, thì $v = v + w$, $w = v + 2w$. Do đó, cặp $\langle v, w \rangle$ của chúng ta có thể được lấy từ cặp $\langle 1, 1 \rangle$ bằng cách sử dụng (*) trong $l$ bước, tức là $\langle v, w \rangle = \langle v_l, w_l \rangle$.

Vì vậy, tập lời giải của phương trình (7) bao gồm các cặp $\langle \gamma_{2k-1}, \gamma_{2k} \rangle$.

3. Bây giờ chúng ta có thể tóm tắt: $u_k = v_k + w_k = \gamma_{2k+1}$, có nghĩa là $x_k = u_k v_k = \gamma_{2k} \gamma_{2k+1}$, $y_k = v_k w_k = \gamma_{2k-1} \gamma_{2k}$. Định lý đã được chứng minh.

4. Một lưu ý cuối cùng. Nếu chúng ta muốn kiểm tra lời giải của mình và xem $k$ nào tương ứng với dòng 14, thì hóa ra $k = 2$. $k = 1$ tương ứng với cái gì? Chúng ta có nhận được thêm lời giải không? $k = 1$ tương ứng với đẳng thức $C_0^2 = C_1^1$, nhưng ba số liên tiếp dường như vô hình. Tuy nhiên, trên thực tế chúng tồn tại, chỉ là số đầu tiên - số 0 - không được viết.

Thông tin lịch sử. Phương trình đang được xem xét đã được tìm thấy trong tài liệu toán học, mặc dù ở dạng hơi khác. (The American Mathematical Monthly, tập 37, trang 508, tác giả bài toán - Norman Anning.) Lời giải cô, xuất bản trong tập 38, trang. 351, không có gì chung cả về phương pháp cũng như hình thức đáp số với cách giải được đưa ra trong ghi chú này.

Nhiệm vụ của độc giả của chúng tôi

1. Hai ô tô số tự động giống hệt nhau đang chạy dọc đường với cùng tốc độ. Tuy nhiên, máy đang chở tải nặng, trong khi máy kia lại trống. Nếu một ô tô bắt đầu giảm tốc độ cùng lúc để bắt đầu quay (bánh xe của chúng không quay), thì ô tô nào sẽ dừng lại trước?

B. Coan (Moscow)

2. Tuy nhiên, thanh được cố định ở trọng tâm để có thể dễ dàng quay trong mặt phẳng thẳng đứng. Các vật nặng giống hệt nhau được gắn vào hai đầu của thanh. Một hệ thống như vậy ở trạng thái cân bằng ở bất kỳ vị trí nào. Và cân đòn bẩy, trên cả hai phần có tải trọng giống hệt nhau, chỉ được lắp đặt theo chiều ngang. Tại sao bạn nghĩ vậy?

E. Gudesblam (Odessa)

3. Chứng minh rằng nếu trong một tam giác $ABC$ với chiều dài $a, b, c$ các cạnh của nó, các bất đẳng thức $c > b > a$ và $\beta_A, \beta_B, \beta_C$ thỏa mãn—độ dài các bissertrise bên trong các đầu, $\beta_A', \beta_B', \beta_C'$—độ dài các đường cao, thì đẳng thức sau đây đúng:

$$\frac{1}{a \beta_A \beta_A'} + \frac{1}{c \beta_C \beta_C'} = \frac{1}{b \beta_B \beta_B'}$$

6) $$\frac{h_a}{\beta_A \beta_A'} + \frac{h_c}{\beta_C \beta_C'} = \frac{h_b}{\beta_B \beta_B'}$$

U. Alla (Võru)
