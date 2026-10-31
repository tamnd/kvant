---
id: 1985-1-satyanov-otrazhenie-krivyih-i-preobrazovaniya-formul-ef6725f2
issue: kvant_1985_1
year: 1985
number: "1"
title: Phản ánh đường cong và công thức chuyển đổi
authors:
  - Сатьянов П. Г.
rubric: shkola-v-kvante
page_first: 31
page_last: 33
page_labels: 29-31
tag: XP5M
lang: vi
source: kvant_digital
extraction: vision
content_sha256: e8b48a55b71fcc1e712a90ca1841e6bdf0f4a3925d49141c03e11bc7ed7a74b3
prompt_sha256: draft-1
translated_from: content/ru/1985/01/articles/10_satyanov-otrazhenie-krivyih-i-preobrazovaniya-formul-ef6725f2.md
source_content_sha256: 85dec90f8be11454fb5e202c1115017396e3107d195f9548b5f82f8bf50c781b
translation_model: draft
translation_run: vi-draft-2026-10-31
translation_quality: draft
---

⟦folio 29⟧

$$t_{A'NB} - t_{A'M} > T = \frac{\lambda}{c},$$

trong đó $\lambda$ là bước sóng, $c$ là tốc độ ánh sáng trong chân không. Vì thời gian truyền của ánh sáng từ các điểm $M$ và $N$ đến $B$ bằng nhau nên điều kiện thu được có thể được viết lại dưới dạng

$$t_{A'N} - t_{A'M} = \frac{l_2 - l_1}{c} = \frac{\lambda}{c}.$$

(*)

Trong các tam giác vuông ở Hình 2 có:

$$l_2^2 = l^2 + (h + d)^2,$$
$$l_1^2 = l^2 + (h - d)^2,$$

từ đó, trừ đi số thứ hai từ đẳng thức thứ nhất, chúng ta thu được:

$$l_2^2 - l_1^2 = (l_2 - l_1)(l_1 + l_2) = 4hd.$$

Lấy $l_1 + l_2 = 2l$ và $h/l = \sin \alpha$, ta tìm được:

$$l_2 - l_1 = \frac{2hd}{l} = 2d \sin \alpha.$$

Khi đó từ điều kiện (*) suy ra rằng

$$d \geq \frac{\lambda}{2 \sin \alpha}$$

- ảnh của hai điểm sẽ khác nhau nếu khoảng cách giữa chúng lớn hơn hoặc ít nhất bằng bước sóng ánh sáng. Đối với ánh sáng khả kiến, bước sóng xấp xỉ 0,5 micron.

Kích thước của vật thể càng nhỏ mà kính hiển vi vẫn có thể nhìn thấy thì cái gọi là độ phân giải của kính hiển vi càng lớn.

Ghi chú. Ngoài kính hiển vi quang học thông thường, còn có kính hiển vi điện tử có độ phân giải cao hơn nhiều. Với sự giúp đỡ của họ, bạn thậm chí có thể kiểm tra từng phân tử.

Matematika 8, 9, 10

Ghi chú được xuất bản dưới đây dành cho chín tác phẩm kinh điển. Tuy nhiên, nó cũng có thể hữu ích cho việc dạy các lớp khác.

Phản ánh đường cong và công thức chuyển đổi

So sánh các số liệu toán học và tầm quan trọng của các dịch vụ/tài liệu phục vụ việc dạy và học trí tuệ.

I. Pestalosi

Matematik yêu thích sự đối xứng hơn tất cả. J. Maxwell

Khi nghiên cứu hàm số và xây dựng đồ thị của chúng, sẽ rất hữu ích khi tính đến tính đối xứng của các đường cong thu được. Từ khóa học ở trường, bạn đã làm quen với các tính chất của đồ thị của hàm chẵn và hàm lẻ. Ví dụ: nếu một hàm $f$ đối xứng quanh 0, thì hàm đó được gọi là chẵn nếu $f(-x) = f(x)$ đối với tất cả $x \in D(f)$ và lẻ nếu $f(-x) = -f(x)$ đối với tất cả $x \in D(f)$. Dễ dàng chứng minh rằng đồ thị của hàm $f$ đối xứng qua trục $Oy$ khi và chỉ khi hàm $f$ chẵn và đối xứng qua gốc tọa độ khi và chỉ khi $f$ là hàm lẻ. Do đó, các thuộc tính được ghi chú của đồ thị phản ánh các đặc điểm đơn giản của các công thức tương ứng.

Một cách tổng quát hơn để xác định các đường cong trong mặt phẳng là xác định chúng bằng phương trình hai biến. Ví dụ: một đường tròn có bán kính $r$ có tâm tại gốc tọa độ được cho bởi phương trình $x^2 + y^2 = r^2$. Bằng cách thực hiện các bài tập được cung cấp trong bài viết này, bạn sẽ biết được tính chất nào của phương trình xác định đường cong tương ứng với một số loại đường cong đối xứng nhất định. Bạn sẽ tự mình “khám phá” hết nội dung mới bằng cách giải các bài tập dưới đây. Chúng tôi sẽ chỉ nhớ lại những thông tin cần thiết và xem xét một ví dụ đơn giản.

1. Đồ thị của phương trình hai biến là tập hợp tất cả các điểm trên mặt phẳng tọa độ có tọa độ là nghiệm của phương trình này. Nói cách khác, $\Gamma$ là đồ thị của phương trình $f(x, y) = 0$ nếu $M(x; y) \in \Gamma \Rightarrow f(x, y) = 0$. Lưu ý rằng đồ thị của hàm $y = f(x)$ cũng có thể được coi là đồ thị của phương trình $y - f(x) = 0$.

2. Đặt $M(x; y)$ là một điểm tùy ý của mặt phẳng tọa độ

⟦folio 30⟧

Phúc. 1, A.
Phúc. 1, b.
Phúc. 1, tr.
Phúc. 1, d.
Phúc. 2, A.
Phúc. 2, b.
Phúc. 2, tr.
Phúc. 2, d.
Phúc. 2, đ.
Phúc. 2, f.
Phúc. 2, h.
Puc. 2, u.
Phúc. 3, A.
Phúc. 3, b.
Phúc. 3, d.
Phúc. 3, đ.
Phúc. 3, f.
Phúc. 3, h.
Puc. 3, u.

30

⟦folio 31⟧

$xOy$ (Hình 1, $a$), khi đó các điểm $M_X$, $M_Y$, $M_O$, thu được bằng cách phản xạ của điểm $M$ tương ứng với các trục $Ox$, $Oy$ và gốc $O$, sẽ có tọa độ sau:
$M_X(x; -y)$; $M_Y(-x; y)$; $M_O(-x; -y)$.

Bài tập 1. Các điểm sẽ có tọa độ như thế nào để đối xứng với các điểm $M(x; y)$ so với các đường phân giác của các góc tạo bởi trục tọa độ?

3. Việc sử dụng các hàm $|x|$ cho phép, dựa trên phương trình của các đường cong tùy ý, thu được phương trình của các đường cong có các tính chất đối xứng nhất định (so với gốc tọa độ, trục $Ox$ và $Oy$). Dưới đây là một ví dụ minh họa những gì đã nói và bạn sẽ tự rút ra kết luận chung bằng cách giải các bài tập đã đề xuất.

Ví dụ. Xây dựng đồ thị của hàm $y=x^2-|x|$.

Lời giải. Tại $x \geq 0$, đồ thị của hàm số này trùng với đồ thị của hàm số $y=x^2-x$ (Hình 1, $\delta$), nhưng hàm số $y=x^2-|x|$ là số chẵn nên đồ thị của nó đối xứng qua trục $Oy$ và có dạng như trong Hình 1, $\delta$.

Bây giờ hãy chuyển sang bài tập lời giải. Chúng tôi đề xuất những thay đổi sau đây về thứ tự làm việc trong trường hợp bạn gặp khó khăn với lời giải bài tập 2 và 3: nếu bạn không làm được nhiệm vụ này hoặc nhiệm vụ khác, hãy nhìn vào đáp số và vẽ đường cong theo công thức cho trong đáp số, bắt đầu từ đường cong ban đầu mới được mô tả trên c. 59 trong Hình 1 (văn bản đáp số) cho Bài tập 2 và trong Hình 2 cho Bài tập 3. Nếu các bài tập bổ sung này khiến bạn gặp khó khăn khi thao tác với các đường cong và phương trình tùy ý (cần thiết để hiểu các nguyên tắc chung), thì bạn thích làm việc với các biểu thức phân tích cụ thể, sau đó, giả sử $f(x)=x^2-x$ (hoặc chọn một hàm khác theo ý của bạn), hãy xây dựng đồ thị của hàm đã cho các công thức tương ứng với các câu trả lời của bài tập 2. Nếu cần, bạn có thể tiếp tục tương tự cho bài tập 3, lấy ví dụ $y+x-x^2=0$ làm phương trình ban đầu. Sau đó quay lại bài tập 2 và 3.

Bài tập

2. Hình 1, $z$ hiển thị biểu đồ của một số hàm $y=f(x)$. So sánh từng Hình 2, $a-2$, $u$ với bản gốc (Về phần cuối, xem trang 34)

Trên trang 32-33, một phần mới mở ra - “Kính vạn hoa «Kvant». Chúng tôi hy vọng rằng ấn phẩm tạp chí này có thể được sử dụng để trang trí các lớp học vật lý và toán học ở trường.
