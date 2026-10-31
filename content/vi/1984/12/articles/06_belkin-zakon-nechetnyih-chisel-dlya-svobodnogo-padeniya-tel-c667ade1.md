---
id: 1984-12-belkin-zakon-nechetnyih-chisel-dlya-svobodnogo-padeniya-tel-c667ade1
issue: kvant_1984_12
year: 1984
number: "12"
title: “Định luật số lẻ” cho vật rơi tự do
authors:
  - Белкин И. К.
rubric: shkola-v-kvante
page_first: 19
page_last: 19
tag: 3BY4
lang: vi
source: kvant_digital
extraction: vision
content_sha256: df6c7ad603590c42980450033232fc8f53cd4da45b03202119cb072780b6a1da
prompt_sha256: draft-1
translated_from: content/ru/1984/12/articles/06_belkin-zakon-nechetnyih-chisel-dlya-svobodnogo-padeniya-tel-c667ade1.md
source_content_sha256: 541698ffaf93198b7369db5d25d1aa6c34741e022554ab4953739d16deedad58
translation_model: draft
translation_run: vi-draft-2026-10-31
translation_quality: draft
---

⟦folio none⟧

Vật lý 8, 9, 10

Ghi chú được đăng bên dưới “Định luật số lẻ” về sự rơi tự do của một vật biến đổi dành cho trẻ 8 tuổi, “Định lý cho phép bạn giải các bài toán tĩnh điện cơ bản” - dành cho học sinh lớp chín, “Cầu vồng là gì?” - học sinh lớp chín.
Các tài liệu được chuẩn bị bởi I.K. Belkin.

"Luật số lẻ"
về sự rơi tự do của cơ thể

Chuyển động của các vật rơi tự do xuống Trái đất như đã biết là chuyển động có gia tốc không đổi $g = 9,81 \text{ m/c}^2$. Nếu vật có điểm cuối tương đối với Trái đất tại thời điểm ban đầu thì định luật rơi tự do được biểu diễn bằng phương trình

$$h = \frac{gt^2}{2},$$

(1)

trong đó $h$ là chuyển động của cơ thể (theo chiều dọc), $t$ là thời gian thiếu tính từ lúc bắt đầu rơi.

Hóa ra công thức (1) dẫn đến một hệ quả kỳ lạ, thường không được đề cập trong sách giáo khoa vật lý, nhưng Galileo, người phát hiện ra định luật rơi tự do, đã biết về: Bản thân nó có thể được coi là một định luật và nó có thể được sử dụng cho lời giải cụ thể bài toán.

Chúng ta đang nói về loại hậu quả gì?

Rõ ràng, công thức (1) cho phép người ta tính độ dịch chuyển của một vật trong bất kỳ thời điểm nào, kể cả thời gian $t = n\Delta t$ giây (ở đây là $n = 1, 2, 3, \dots, \Delta t = 1$ s). Hơn nữa, bằng cách sử dụng cùng một công thức, bạn có thể xác định độ dịch chuyển không chỉ cho tất cả $n$ giây mà còn cho từng $n$ giây - cho khoảng thời gian, giây, v.v.

Trên thực tế, nếu trong $n$ giây chuyển động $h_n$ là tự do và trong $(n-1)$ giây - $h_{n-1}$, thì trong $n$ giây (ở đây $n$) độ dịch chuyển $h(n)$ đương nhiên bằng hiệu của $h_n$ và $h_{n-1}$ (ở đây $n$ - số lượng giây):

$$h(n) = h_n - h_{n-1} = \frac{g(n\Delta t)^2}{2} - \frac{g((n-1)\Delta t)^2}{2} = \frac{g}{2}((n\Delta t)^2 - ((n-1)\Delta t)^2) = \frac{g(\Delta t)^2}{2}(2n-1).$$

Từ công thức (2), rõ ràng độ dịch chuyển $h(1)$ trong giây đầu tiên ($n=1$) bằng

$$h(1) = \frac{g(\Delta t)^2}{2}.$$

Tương tự, chúng ta có thể thấy rằng trong giây tiếp theo vật chuyển động:

$$h(2) = 3 \frac{g(\Delta t)^2}{2}, \quad h(3) = \dot{5} \frac{g(\Delta t)^2}{2},$$

$$h(4) = 7 \frac{g(\Delta t)^2}{2}, \quad h(5) = 9 \frac{g(\Delta t)^2}{2},$$

$$h(6) = 11 \frac{g(\Delta t)^2}{2}, \dots, \quad h(n) = (2n-1) \frac{g(\Delta t)^2}{2}.$$

Do đó, các chuyển động trong các khoảng thời gian bằng nhau liên tiếp trong 1 giây có liên quan với nhau theo tỷ lệ 1:3:5:7:9:11:...:(2n-1), tức là dưới dạng số lẻ (lưu ý rằng giá trị $(2n-1)$ đối với mọi giá trị $n$ là số lẻ).

Điều thú vị là Galileo đã xây dựng định luật rơi tự do của một vật theo đúng dạng này. Theo lời của chính Galileo: “Các không gian mà một vật rơi đi qua trong những khoảng thời gian bằng nhau có liên hệ với nhau bằng các số lẻ liên tiếp”.

Không nên nghĩ rằng “luật số lẻ” chỉ áp dụng cho trường hợp vật rơi tự do. Tất nhiên, nó đúng cho mọi chuyển động cân bằng không có vận tốc ban đầu. Xét cho cùng, mô hình này là hệ quả trực tiếp của thực tế là độ dịch chuyển của một vật trong quá trình chuyển động như vậy tỉ lệ với bình phương thời gian. Người ta cũng không nên nghĩ rằng “định luật” này chỉ đúng khi khoảng thời gian tính chuyển động bằng một giây. Tất nhiên, nó đúng trong mọi khoảng thời gian bằng nhau, như Galileo đã lưu ý.

Để kết luận, chúng tôi mời độc giả tự mình tìm hiểu “định luật số lẻ” trong trường hợp chuyển động cân bằng sẽ như thế nào.
