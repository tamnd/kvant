---
id: 1970-11-kak-nayti-oshibku-65f9e002
issue: kvant_1970_11
year: 1970
number: "11"
title: Cách tìm lỗi
rubric: smes
page_first: 28
page_last: 28
page_labels: "26"
tag: QVQB
lang: vi
source: kvant_digital
extraction: vision
content_sha256: 894c9cda7bec199a35038aa0065fb3edb0daa0aadd53b314e82250ac6927705e
prompt_sha256: 3ec6b8aabd9b98576af76503cd8a2902b9f5d18e01ee867dfb1228f59c6d52d8
translated_from: content/ru/1970/11/articles/08_kak-nayti-oshibku-65f9e002.md
source_content_sha256: 386342da7ee40fa43dbaa8358cf3d2ec96454a13baae8590d8174cb08e209c92
translation_model: gpt-5.6-terra
translation_run: vi-codex-2026-10-31
---

⟦trang 26⟧

đại lượng. Do đó, ta có một chuỗi bất đẳng thức

$$\frac{a_1 + a_2 + \ldots + a_n}{n} \geq \sqrt[n]{a_1 a_2 \ldots a_n} \geq \frac{n}{a_1 + \frac{1}{a_2} + \ldots + \frac{1}{a_n}}.$$

Hãy tự chứng minh bất đẳng thức cuối cùng.

Cuối cùng, lưu ý rằng trong toán học cao cấp có phương pháp tìm cực đại và cực tiểu của hàm số bằng phép vi phân. Tuy nhiên, các bất đẳng thức đã xét tỏ ra thuận tiện hơn để tính trên máy tính điện tử các giá trị lớn nhất và nhỏ nhất của một số loại biểu thức. Các phương pháp này được gọi là quy hoạch hình học.

Bài tập

1. Trong các quạt tròn có chu vi cho trước $P$, hãy tìm quạt có diện tích lớn nhất.

2. Trong đường tròn đã cho, hãy tìm dây nhỏ nhất đi qua điểm $A$ nằm bên trong đường tròn.

3. Hãy tìm giá trị nhỏ nhất của biểu thức

$$2x^3 + \frac{3}{\sqrt{x}}.$$

4. Chứng minh rằng nếu tổng các biến dương $x_1, x_2, \ldots, x_n$ là không đổi, thì tích $x_1^{k_1} x_2^{k_2} x_3^{k_3} \ldots x_n^{k_n}$, trong đó $k_1, k_2, \ldots, k_n$ là các số nguyên dương cho trước, đạt giá trị lớn nhất khi các biến tỉ lệ với các số mũ của chúng: $\frac{x_1}{k_1} = \frac{x_2}{k_2} = \frac{x_3}{k_3} = \ldots = \frac{x_n}{k_n}$.

Chứng minh rằng điều đó cũng đúng đối với các số hữu tỉ dương $k_1, k_2, \ldots, k_n$.

CÁCH TÌM LỖI

Bạn đã nhân hai đa thức dài. Làm thế nào kiểm tra xem có sai sót trong tính toán hay không?

Chúng tôi nêu hai cách cho phép phát hiện một số khả năng sai sót (nhưng, dĩ nhiên, không bảo đảm hoàn toàn tính đúng đắn của các phép tính đã kiểm tra).

Cách 1. Lấy tổng các hệ số của đa thức thứ nhất nhân với tổng các hệ số của đa thức thứ hai. Kết quả phải bằng tổng các hệ số của tích. Đó là giá trị của đa thức tại $x=1$.

Cách trên cho phép phát hiện lỗi trong số học (chẳng hạn, nếu đã dùng “đẳng thức” $2 \cdot 3=5$), nhưng không phát hiện lỗi trong đại số. Chẳng hạn, nếu ở một bước nào đó bạn đã viết $2x^2 \cdot 3x^3=6x^4$, thì cách này sẽ không phát hiện được lỗi.

Cách 2. Khác với cách thứ nhất ở chỗ các hệ số của các lũy thừa chẵn của $x$ được lấy với dấu cộng, còn các hệ số của các lũy thừa lẻ thì với dấu trừ. Còn lại, cách này trùng với cách thứ nhất. Ở đây ta nhận được giá trị của đa thức tại $x=-1$.

Cách thứ hai phức tạp hơn cách thứ nhất, nhưng nó cho phép phát hiện cả một số sai lầm đại số. Khi kiểm tra «đẳng thức» $2x^2 \cdot 3x^3=6x^4$ ta được $2 \cdot (-3)=6$. Đẳng thức này vô lý, vậy là trong các phép tính đã có sai sót.
