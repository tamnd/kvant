---
id: 1970-3-kolmogorov-parketyi-iz-pravilnyih-mnogougolnikov-e4118a4a
issue: kvant_1970_3
year: 1970
number: "3"
title: Các phép lát từ các đa giác đều
authors:
  - Колмогоров А. Н.
rubric: osnovnye-stati
page_first: 27
page_last: 28
page_labels: 25-26
tag: WWZ6
lang: vi
source: kvant_digital
extraction: vision
content_sha256: d51bf367a9445e37481c74f4ca5ec8292b4bbad55bcde5003059b6de1e2d3171
prompt_sha256: 3ec6b8aabd9b98576af76503cd8a2902b9f5d18e01ee867dfb1228f59c6d52d8
translated_from: content/ru/1970/03/articles/05_kolmogorov-parketyi-iz-pravilnyih-mnogougolnikov-e4118a4a.md
source_content_sha256: 94cb08ee0ea26b99fcff68196ee0c07e637357fbe1e0840763e22ec63bc8a9a8
translation_model: gpt-5-6-mini
translation_run: m10-1970-vi
---

⟦folio 25⟧

Ví dụ, trên hình 2, b, nếu quay toàn bộ mạng lưới các đỉnh và cạnh tạo thành lát nền gồm các lục giác, hình vuông và tam giác một góc 60° quanh tâm của một trong các lục giác, ta sẽ nhận được chính mạng lưới các đỉnh và cạnh đó. Tâm của mỗi lục giác trong lát nền này là «tâm đối xứng bậc sáu»*).

Bài toán 1. Hãy tìm tất cả các tâm đối xứng bậc 4, bậc 3 và bậc 2 của lát nền được vẽ trên hình 2, a.

LÁT NỀN ĐỀU LÀ GÌ

Xét về mặt đối xứng, định nghĩa lát nền của chúng ta chưa thật chặt chẽ. Nó cho phép những lát nền không có bất kỳ đối xứng nào. Lấy một lát nền thông thường gồm các lục giác (hình 1, c), ta có thể «làm hỏng» nó bằng cách chia một số lục giác thành sáu tam giác. Dễ thấy rằng ta lại thu được một «lát nền» theo nghĩa định nghĩa của chúng ta. Nhưng có thể chứng minh (hãy thử xem!), rằng nếu chia, chẳng hạn, ba lục giác như trên hình 3, còn tất cả các lục giác khác không chia, ta sẽ thu được một lát nền hoàn toàn không có đối xứng. Để loại bỏ những lát nền xấu, không đủ đối xứng, ta đưa ra định nghĩa sau:

Lát nền được gọi là đều nếu có thể chồng nó lên chính nó sao cho bất kỳ đỉnh nào đã cho của nó cũng chồng lên bất kỳ đỉnh nào khác đã cho của nó.

Bài toán 2. Hãy chứng minh rằng các lát nền được trình bày trên các hình 1 và 2 là đều, và tự xây dựng càng nhiều lát nền đều khác nhau càng tốt.

*) Điểm O được gọi là tâm đối xứng bậc n của một hình nếu khi quay hình đó quanh O một góc $\frac{360^\circ}{n}$ thì nó chồng khít lên chính nó.

⟦folio 26⟧

BÀI TOÁN CƠ BẢN

Hóa ra có thể mô tả toàn bộ sự đa dạng của các lát nền đều. Nếu độ dài $h$ của cạnh các đa giác trong lát nền được cho trước, thì chỉ tồn tại một số hữu hạn các lát nền đều khác nhau (không chồng khít lên nhau). Cụ thể là bao nhiêu, tôi không muốn nói với các bạn.

Liệt kê tất cả chúng và qua đó trả lời câu hỏi về số lượng của chúng — đó chính là bài toán cơ bản mà các bạn phải giải.

MỘT SỐ GỢI Ý

Việc giải bài toán một cách tự nhiên bắt đầu bằng việc xét cấu tạo các đỉnh của lát nền. Một đa giác đều $n$ cạnh có $n$ góc ngoài (hình 4), tổng của chúng bằng bốn góc vuông (hãy tự kiểm tra). Vì vậy mỗi góc của đa giác đều $n$ cạnh bằng

$$\alpha_n = 2d - \frac{4d}{n} = 2\left(1 - \frac{2}{n}\right)d.$$

Tại mỗi đỉnh của lát nền, các đa giác gặp nhau phải có tổng các góc bằng 4d. Do đó,

$$\alpha_3 = \frac{2}{3}d, \alpha_4 = d, \alpha_6 = \frac{4}{3}d, \alpha_8 = \frac{3}{2}d$$

và đối với các lát nền được vẽ trên hình 1 và 2, ta có:

$$4\alpha_4 = 4d,$$

$$6\alpha_3 = 4d,$$

$$3\alpha_6 = 4d,$$

$$\alpha_4 + 2\alpha_8 = 4d,$$

$$\alpha_3 + 2\alpha_4 + \alpha_6 = 4d.$$

Trong trường hợp tổng quát, ký hiệu $m_n$ là số đa giác $n$ cạnh gặp tại một đỉnh, ta phải có

$$\sum m_i\alpha_i = 4d,$$

(1)

trong đó trong tổng ta đưa vào các số hạng có những chỉ số $i$ mà $m_i > 0$, còn $\alpha_i = 2\left(1 - \frac{2}{i}\right)d$.

Nhiệm vụ đầu tiên của chúng ta là tìm tất cả các nghiệm của phương trình (1) với các $m_i > 0$ nguyên. Phương trình (1), sau khi rút gọn cho 2d, có thể viết dưới dạng

$$\sum m_i\left(1 - \frac{2}{i}\right) = 2.$$

Đối với mỗi nghiệm của phương trình (2), cần sử dụng tương ứng
