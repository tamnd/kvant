---
id: 1979-10-ovchinnikov-esli-promezhutok-ne-zamknut-91134735
issue: kvant_1979_10
year: 1979
number: "10"
title: Nếu khoảng cách không được đóng lại...
authors:
  - Овчинников С. В.
rubric: praktikum-abiturienta
rubric_sub: Практикум абитуриента
page_first: 46
page_last: 50
page_labels: 44-48
tag: 7LJF
lang: vi
source: kvant_digital
extraction: vision
content_sha256: 2bfadb7481341a6fd4e12d3087d372042aa76f68df65c74fea1ae21ca4fc3a26
prompt_sha256: draft-1
translated_from: content/ru/1979/10/articles/16_ovchinnikov-esli-promezhutok-ne-zamknut-91134735.md
source_content_sha256: c5b7668e7e75feed94392623f32f6f5924bc28e096d68b8600defcae1093263f
translation_model: draft
translation_run: vi-draft-2026-10-31
translation_quality: draft
---

⟦folio 44⟧

S. Ovchinnikov

Nếu khoảng cách không được đóng lại...

Khi lời giải hình học bài toán nhằm mục đích tìm giá trị lớn nhất (hoặc nhiều nhất), đôi khi người ta quên rằng đại lượng cần tìm thường đáp ứng một số hạn chế nhất định do ý nghĩa hình học của chúng. Trong nhiều bài toán như vậy, việc nghiên cứu hàm đang được xem xét tại ranh giới của miền xác định được xác định bởi phần lời giải hiện có.

Dưới đây là những ví dụ về nghiên cứu như vậy.

Bài toán 1. Tên giá trị chu vi của hình chữ nhật được viết theo một đoạn tròn cho trước sao cho hai đỉnh của nó nằm trên dây của một đoạn cho trước.

Lời giải. Gọi $2a$ là độ dài dây cung của đoạn và $h$ chiều cao của nó (Hình 1). Dễ dàng nhận thấy bán kính của hình tròn là $R = \frac{a^2 + h^2}{2h}$.

Ký hiệu bằng $x$ nửa chiều dài đáy của hình chữ nhật nội tiếp

Hình 1.

Vì vậy, hãy tìm độ dài của cạnh thứ hai:

$$y = \sqrt{R^2 - x^2} - R + h.$$

Từ đây chúng ta tìm chu vi $P$ của hình chữ nhật là hàm của biến $x$:

$$P(x) = 4x + 2\sqrt{R^2 - x^2} - 2R + 2h.$$

Ngoài ra, $x \in ]0; a[$ nếu $h \leq R$ và $x \in ]0; a[$ nếu $h > R$ (kiểm tra!).

Chúng ta hãy tìm các điểm tới hạn của hàm $P$ và nghiên cứu chúng. chúng tôi có

$$P'(x) = 4 - \frac{2x}{\sqrt{R^2 - x^2}}.$$

Từ đây

$$P'(x) = 0 \Leftrightarrow 2\sqrt{R^2 - x^2} = x.$$

Giải phương trình cuối cùng, ta tìm được điểm tới hạn $x_0 = \frac{2\sqrt{5}}{5}R$.

Hàm $\frac{2x}{\sqrt{R^2 - x^2}}$ là tuổi. Do đó, đạo hàm của $P'(x)$ dương tại $x < x_0$ và âm tại $x > x_0$. Như vậy, điểm $x_0$ là điểm cực đại của hàm số $P$. Vẫn còn phải điều tra câu hỏi khi nào điểm này cho giá trị chu vi tối đa và điều gì xảy ra khi không đạt được giá trị tối đa tại điểm này. Trong nghiên cứu này, khoảng mà hàm $P$ được xác định đóng một vai trò quan trọng. Ví dụ: đối với $h \leq R$ thì đây là khoảng $]0; a[$ và đối với $h > R$ thì khoảng kết quả là $]0; a[$.

Trong cả hai trường hợp, nếu điểm tới hạn $x_0$ thuộc khoảng $]0; a[$, thì hàm $P$ sẽ lấy giá trị lớn nhất trong khoảng đó. chúng tôi có

$$x_0 \in ]0; a[ \Leftrightarrow \frac{2\sqrt{5}}{5}R < a \Leftrightarrow \frac{\sqrt{5}}{5} \cdot \frac{a^2 + h^2}{h} < a.$$

Giải phương trình cuối cùng, ta tìm được $\frac{h}{a} \in \left[ \frac{\sqrt{5} - 1}{2}; \frac{\sqrt{5} + 1}{2} \right]$.

Đối với tất cả các giá trị như vậy $a$ và $h$, giá trị chu vi lớn nhất bằng

$$P(x_0) = \frac{(\sqrt{5} - 1)a^2 + (\sqrt{5} + 1)h^2}{h}.$$

⟦folio 45⟧

Bây giờ hãy để điểm tới hạn $x_0$ không thuộc khoảng $]0; a[$, tức là $x_0 \geqslant a$. Trong trường hợp này, tích $P'(x)$ dương với tất cả $x$ của $]0; a[$ và hàm $P$ trả về trong khoảng $]0; a[$.

Hãy để $h \leqslant R$. Cùng với các điều kiện $x_0 \geqslant a$, điều này mang lại cho chúng ta $\frac{h}{a} \leqslant \frac{\sqrt{5}-1}{2}$.

Vì tại $h \leqslant R$ hàm $P$ được xác định trên khoảng $]0; a[$ nên chúng ta kết luận rằng nó không đạt giá trị cực đại.

Nếu $h > R$ thì cùng với các điều kiện $x_0 \geqslant a$ ta thu được $\frac{h}{a} \geqslant \frac{\sqrt{5}+1}{2}$. Vì trong trường hợp này, hàm $P$ được xác định trên khoảng nửa chữ cái $]0; a[$, nên nó đạt giá trị tối đa tại $x = a$. Giá trị này là $P(a) = 4a + 2 \cdot \frac{h^2 - a^2}{h}$.

Hãy để chúng tôi đưa ra một minh họa hình học rõ ràng về kết quả thu được. Chúng ta hãy chọn hai dây “quan trọng” song song trong một vòng tròn có bán kính $R$, nằm ở khoảng cách $\frac{\sqrt{5}}{5} R$ tính từ tâm vòng tròn (Hình 2) và dựng chúng thành hình chữ nhật. Chúng tôi sẽ chỉ xem xét các phân đoạn “trên” có hợp âm song song với các hợp âm đã chọn.

Nếu hợp âm của một đoạn nhất định nằm giữa các hợp âm đã chọn, thì $a > \frac{2\sqrt{5}}{5} R$ và hình chữ nhật nội tiếp trong đoạn của chúng ta có chu vi lớn nhất là giao điểm của đoạn này với hình chữ nhật được xây dựng trên các hợp âm đã chọn (xem Hình 2).

Nếu hợp âm của một đoạn nhất định nằm trên cả hai hợp âm đã chọn thì $h < R$ và $a \leqslant \frac{2\sqrt{5}}{5} R$; trong trường hợp này, chu vi của hình chữ nhật nội tiếp không đạt giá trị tối đa (Hình 3).

Cuối cùng, nếu hợp âm của một đoạn nhất định nằm trên cả hai hợp âm đã chọn thì $h > R$ và $a \leqslant \frac{2\sqrt{5}}{5} R$; trong trường hợp này, hình chữ nhật nội tiếp có chu vi lớn nhất có dây cung này làm đáy (Hình 4).

Hình 5.

Bài toán 2. Từ một hình chữ nhật có phần “đường đi” bị cắt (Hình 5), cần cắt một hình chữ nhật có diện tích phẳng nhất, song song với các cạnh của hình chữ nhật này.

Lời giải. Chúng ta hãy giới thiệu một hệ tọa độ, như trong Hình 6, và tiếp tục “trung bình” tuyến tính cho đến khi nó giao nhau với các trục tọa độ. Cho phép

⟦folio 46⟧

Các điểm giao nhau của nó với các trục tọa độ là $A(a, 0)$ và $B(0, b)$. Hãy giải phụ trợ bài toán sau: nội tiếp tam giác AOB một hình chữ nhật có diện tích lớn nhất, một trong các đỉnh của nó là $O$. Đặt độ lớn của hình chữ nhật phụ là $x$. Khi đó chiều cao của nó là $b - \frac{b}{a}x$. Do đó diện tích của hình chữ nhật, được coi là hàm của $x$, là

$$S(x) = x \left( b - \frac{b}{a}x \right).$$

Rõ ràng, $S(x)$ nhận giá trị tối đa ở $x_0 = \frac{a}{2}$. Trong trường hợp này, hàm $S$ trả về $0; \frac{a}{2}$ trên khoảng kết quả và hủy bỏ $\left[ \frac{a}{2}; a \right]$ trên khoảng kết quả.

Nghiên cứu được tiến hành về hàm $S$ cho phép chúng tôi đưa ra biểu diễn trực quan sau đây lời giải của bài toán ban đầu. Nếu phần giữa $K$ của đoạn $[AB]$ thuộc về “đường cắt” $[CD]$ thì nó phải được lấy làm đỉnh của hình chữ nhật mong muốn. Nếu điểm $K$ được cắt “ở trên” $[CD]$, thì điểm $C$ phải được lấy làm đỉnh của hình chữ nhật mong muốn. Nếu nó nằm “bên dưới” đường cắt $[CD]$ thì điểm $D$ được lấy làm đỉnh của hình chữ nhật mong muốn.

Bài toán 3. Trong một hình nón có góc $2\alpha$ ở đỉnh của phần chính và có giá trị bán kính đáy $R$ treo một hình trụ có tổng diện tích bề mặt lớn nhất.

Lời giải. Hình 7 cho thấy mặt cắt ngang cuối cùng của hình nón này. Ký hiệu bằng $x$ bán kính đáy của hình trụ treo, ta dễ dàng nhận thấy chiều cao của nó ($R-x$) stg $\alpha$. Do đó tổng bề mặt, như là một hàm của biến $x$, là

$$S(x) = 2\pi \cdot \text{ctg} \alpha \left[ (\text{tg} \alpha - 1) x^2 + Rx \right].$$

Hàm này được xác định bởi các điều kiện bài toán trên khoảng $]0; R[$. Đối với $tg \alpha \neq 1$ chúng ta dễ dàng tìm thấy hàm điểm tới hạn $x_0 = \frac{R}{2(1-tg \alpha)}$ $S$.

Tùy thuộc vào vị trí của điểm tới hạn so với khoảng $]0; R[$, có thể xảy ra ba trường hợp:

1) $x_0 < 0 \Leftrightarrow \text{tg} \alpha > 1$.

Rõ ràng trong trường hợp này, hàm $S$ đang tăng trên khoảng $]0; R[$. Trong trường hợp này, hàm $S$ không đạt giá trị tối đa.

2) $x_0 \in ]0; R[ \Leftrightarrow 0 < \frac{R}{2(1-tg \alpha)} < R \Leftrightarrow \text{tg} \alpha < \frac{1}{2}$.

Trong trường hợp này, điểm tới hạn $x_0$ rõ ràng là điểm cực đại của hàm $S$ và trên khoảng $]0; x_0]$, hàm $S$ trả về trong khoảng thời gian $[x_0; R[$ tiêu diệt; do đó, giá trị lớn nhất của hàm này là $S(x_0) = \frac{\pi R^2 \cdot \text{ctg} \alpha}{2(1-tg \alpha)}$.

3) $x_0 \geqslant R \Leftrightarrow \frac{1}{2} \leqslant \text{tg} \alpha < 1$.

Trong trường hợp này, hàm $S$ đang tăng trên khoảng $]0; R[$. Để tóm tắt việc nghiên cứu hàm $S$, chúng ta có thể nói rằng với $tg \alpha < \frac{1}{2}$ một hình trụ có tổng diện tích bề mặt lớn nhất có thể nội tiếp được trong hình nón. Nếu $tg \alpha \geqslant \frac{1}{2}$, thì có thể các giá trị của hàm $S$ là khoảng mở $]0; 2\pi R^2$ (“Đại số và phần đầu phân tích 10”, trang 84) và hàm $S$ không đạt giá trị lớn nhất.

Bài toán 4. Một trong các góc của tam giác nội tiếp trong đường tròn bán kính $R$ bằng $\alpha$. Tìm nhiều nhất

⟦folio 47⟧

cổ giá trị chiều dài của chiều cao của hình tam giác.

Lời giải e. Chúng ta biểu thị độ dài cạnh của tam giác bằng $a$, $b$ và $c$ (Hình 8) và góc trống nằm đối diện với cạnh $a$ bằng $x$.

Rõ ràng là $x \in ]0; \pi - \alpha[$. Lưu ý rằng các điều kiện không chỉ ra đường cao nào trong ba đường cao của tam giác mà chúng ta đang nói đến. Do đó, với lời giải “trong bất kỳ” cần tìm giá trị lớn nhất của độ dài của mỗi chiều cao, sau đó từ các giá trị tìm được xác định giá trị lớn nhất bằng $2R\cos^2\frac{\alpha}{2}$.

Biểu thị độ dài các đường cao của tam giác giảm xuống các cạnh $a$, $b$ và $c$ lần lượt là $h_a$, $h_b$ và $h_c$, chúng ta tính chúng dưới dạng hàm của góc $x$. Sử dụng định lý sin và công thức tính mặt phẳng của tam giác, chúng ta tìm được

$$h_a(x) = \frac{bc}{a}\sin x = 2R\sin \alpha \sin (x + \alpha),$$

$$h_b(x) = \frac{ac}{b}\sin (x + \alpha) = 2R\sin \alpha \sin x,$$

$$h_c(x) = \frac{ab}{c}\sin \alpha = 2R\sin x \sin (x + \alpha).$$

Xét hàm $h_a$ cho $x \in ]0; \pi - \alpha[$. Rõ ràng, tại $\alpha < \frac{\pi}{2}$ hàm này đạt giá trị tối đa $2R\sin \alpha$ tại $x_0 = \frac{\pi}{2} - \alpha$.

Nếu $\alpha \geq \frac{\pi}{2}$ thì hàm $h_a$ sẽ tắt trong khoảng $]0; \pi - \alpha[$ và không có ý nghĩa. Tương tự, chúng ta thấy rằng hàm $h_b$ cho $\alpha < \frac{\pi}{2}$ đạt giá trị lớn nhất $2R\sin \alpha$ tại $x_1 = \frac{\pi}{2}$, nhưng đối với $\alpha \geq \frac{\pi}{2}$ thì nó không có giá trị.

Hãy cân nhắc việc kết thúc hàm $h_c$. $h_c'(x) = 2R[\cos x \cdot \sin (x + \alpha)] + \sin x \cdot \cos (x + \alpha)] = 2R \cdot \sin (2x + \alpha)$. Rõ ràng là trên khoảng $]0; \pi - \alpha[$ $h_c'(x) = 0 \Leftrightarrow \sin (2x + \alpha) = 0 \Leftrightarrow 2x + \alpha = \pi$.

Điểm tới hạn là $x_2 = \frac{\pi - \alpha}{2}$. Lần này $\alpha \in ]0; \pi - \alpha[$ đối với bất kỳ $\alpha$ hợp lệ nào. Khoảng $]0; \pi - \alpha[$ được theo sau bởi số dương và bên phải là số âm. Do đó, tại điểm $x_2$ hàm $h_c$ đạt giá trị cực đại, bằng $2R\cos^2\frac{\alpha}{2}$.

Vì vậy, đối với mỗi giá trị của góc $\alpha$, chúng ta chỉ cần tìm nhiều giá trị nhất từ ​​​​các giá trị độ cao được tìm thấy nhiều nhất.

Trước tiên chúng ta hãy xem xét trường hợp $\alpha < \frac{\pi}{2}$. Với $\alpha$ như vậy, giá trị chiều cao đạt được và nhận hai giá trị: $2R\sin \alpha$ và $2R\cos^2\frac{\alpha}{2}$. Hãy biến đổi sự khác biệt

$$2R\sin \alpha - 2R\cos^2\frac{\alpha}{2} = 2R\cos^2\frac{\alpha}{2} \left(2\tg \frac{\alpha}{2} - 1\right).$$

Từ đó chúng ta có thể kết luận:

a) tại $\alpha < 2\arctg \frac{1}{2}$ chiều cao tối đa là $2R\cos^2\frac{\alpha}{2}$;

b) tại $2\arctg \frac{1}{2} \leq \alpha < \frac{\pi}{2}$ chiều cao tối đa là $2R\sin \alpha$.

Hãy để bây giờ $\alpha \geq \frac{\pi}{2}$. Chúng tôi đã lưu ý ở trên rằng giá trị tối đa của chiều cao $h_c$ bằng $2R\cos^2\frac{\alpha}{2}$. Một cách dễ dàng

⟦folio 48⟧

thấy rằng các giá trị của hàm $h_a$ và $h_b$ điền vào khoảng $]0; 2R \sin^2 \alpha[$.
Trong trường hợp đang được xem xét, $2R \sin^2 \alpha > 2R \cos^2 \frac{\alpha}{2}$.
Điều này có nghĩa là ở mức $\alpha \geq \frac{\pi}{2}$ không đạt được giá trị chiều cao tối đa.

bài toán này có thể được giải một cách dễ dàng hơn bằng cách sử dụng các cân nhắc hình học. Rõ ràng là $h_a \leq c$ và $h_b \leq c$. Do đó, ở $\alpha < \frac{\pi}{2}$ giá trị lớn nhất của $h_a$ và $h_b$ bằng $c$ (Hình 9). Điều này có nghĩa là trong trường hợp này chúng ta cần chọn các số lớn hơn $h_c$ và $c$. Khi $\alpha$ được cố định, $c = 2R \sin \alpha$ cũng được cố định. $h_c$ rõ ràng có giá trị lớn nhất trong một tam giác đều (Hình 10). Vì vậy, trong trường hợp đang xét, như trên, chúng ta cần chọn số lớn nhất trong các số $2R \cos^2 \frac{\alpha}{2}$ và $2R \sin \alpha$.

Nếu $\alpha \geq \frac{\pi}{2}$ thì $h_a \geq h_c$ và $h_b \geq h_c$, $h_a$ và $h_b$ không đạt giá trị lớn nhất bằng $c \sin(\pi - \alpha) = 2R \sin^2 \alpha$ (Hình 11).

Tất nhiên, người đọc chú ý nhận thấy rằng trong tất cả các bài toán được phân tích, chúng tôi đã không tuân theo các quy tắc từ đoạn 59 của sách “Đại số và sự khởi đầu của phân tích 9”. Về cơ bản, quy tắc này chỉ áp dụng cho trường hợp khoảng đóng. Nếu khoảng thời gian mở là như vậy, như trường hợp của hầu hết các bài toán của chúng ta, thì hành vi của các hàm trên khoảng này đòi hỏi phải có sự phân tích đặc biệt!

Vấn đề tương tự sẽ nảy sinh trong trường hợp khoảng thời gian vô hạn.

Tại nhà vợ
1. Trong một đoạn parabol, dây cung vuông góc với trục đối xứng của các parabol (Hình 12), nội tiếp một hình chữ nhật có chu vi lớn nhất. (Độ dài hợp âm là $2a$, chiều cao là $h$).

Hình 12.

2. Trong một tam giác có đáy $a$ và chiều cao $h$, hãy nội tiếp một hình chữ nhật có chu vi lớn nhất, hai đỉnh của nó nằm trên đáy của tam giác.

3. Tìm dây lớn nhất của hình elip $\frac{x^2}{a^2} + \frac{y^2}{b^2} = 1$ đi qua $B(0; -b)$.

4. Tìm khoảng cách lớn nhất và nhỏ nhất từ ​​một điểm nằm trên đường kính của vật thu được đến các điểm của hình bán nguyệt giới hạn nó. Câu hỏi tương tự cho đoạn tròn.

5 (DSU, Khoa Sinh học, 1978). Tìm giá trị lớn nhất và nhỏ nhất của hàm $y = \sin 2x - x$ trên [0; $\pi$].

6 (LSU, Khoa Toán ứng dụng - Quy trình điều khiển, 1977). Với những giá trị nào của tham số $p$ là giá trị nhỏ nhất của tam thức bậc ba $x^3 - 2px^2 + 1$ trên khoảng $[0; 1]$ đạt được ở đầu bên phải của khoảng?

7 (KhSU, khoa vật lý, 1978). Tìm giá trị nhỏ nhất của hàm $y = \frac{1}{x} + \frac{q^2}{6 - x}$ trên khoảng [2; 3] tùy thuộc vào tham số $q$.
