---
id: 1980-12-resheniya-zadach-m609-m610-f613-f617-4cc7035d
issue: kvant_1980_12
year: 1980
number: "12"
title: Lời giải bài toán M609, M610; F613—F617
rubric: zadachnik-kvanta
rubric_sub: Задачник «Кванта»
page_first: 26
page_last: 30
page_labels: 24-28
tag: SXYG
lang: vi
source: kvant_digital
extraction: vision
content_sha256: 583c156cf58e26d215e1263370c2dec6f9ad82bce1e767e359c4210c6af4a1fd
prompt_sha256: draft-1
translated_from: content/ru/1980/12/articles/11_resheniya-zadach-m609-m610-f613-f617-4cc7035d.md
source_content_sha256: 0b74285472da05aecef0a20af47ea37529f6a76e98b3406881d5e1d406a9b796
translation_model: draft
translation_run: vi-draft-2026-10-31
translation_quality: draft
---

⟦folio 24⟧

M609. a) Độ dài các hình chiếu của đa giác lồi có diện tích S lên hai đường thẳng phân bố đều lần lượt bằng $l_1$ và $l_2$. Chứng minh rằng $S \leq l_1 l_2$.
b) Độ dài các hình chiếu của đa giác lồi thể tích V lên ba đường thẳng phân bố đều lần lượt là $l_1, l_2$ và $l_3$. Chứng minh rằng $V \leq l_1 l_2 l_3$.
c) Diện tích hình chiếu của đa giác lồi thể tích V lên ba đường thẳng phân bố đều lần lượt là $S_1, S_2$ và $S_3$. Chứng minh rằng $V \leq \sqrt{S_1 S_2 S_3}$.

M609, M610; F613—F617

Phát biểu về điểm a) và b) suy ra trực tiếp từ thực tế là trong trường hợp a) đa giác nằm trong một hình chữ nhật có các cạnh $l_1$ và $l_2$, và trong trường hợp b) đa giác nằm trong một hình chữ nhật song song có các cạnh $l_1, l_2, l_3$.

c) Gọi $\pi_1, \pi_2, \pi_3$ là các mặt phẳng phân bố lại lẫn nhau, $S_1, S_2, S_3$ lần lượt là diện tích hình chiếu của đa giác M lên các mặt phẳng này và $l_1, l_2, l_3$ lần lượt là các đường chiếu của đa giác M lên các đường thẳng $\pi_2 \cap \pi_3, \pi_1 \cap \pi_3, \pi_1 \cap \pi_2$, $V = V(M)$ là thể tích của nó. Các mặt phẳng song song với $\pi_1$ từ đó sẽ được gọi là nằm ngang.

Đầu tiên là lời giải. Bất bình đẳng công bằng
$$V \leq \sqrt{S_1 S_2 S_3}$$

đối với một đối tượng địa lý trực tiếp có đáy nằm ngang, nó dễ dàng suy ra từ a): đối với đối tượng địa lý như vậy $S_1 \leq l_2 l_3, S_2 = l_1 l_3, S_3 = l_1 l_2$ và $V^2 = (S_1 l_1)^2 = S_1 \cdot S_1 l_1^2 \leq S_1 \cdot l_1 l_2 \cdot l_1 l_3 = S_1 S_2 S_3$.

Để chứng minh (1) cho đa giác tùy ý, ta cần

Bổ đề. Cắt đa giác M bằng mặt phẳng ngang thành n đa giác $M_1, \dots, M_n$. Nếu bất đẳng thức (1) được thỏa mãn với mỗi chúng thì điều đó cũng đúng với M.

Trước tiên chúng ta hãy chứng minh bổ đề cho $n = 2$. Đặt diện tích hình chiếu của đa giác $M_1$ và $M_2$ lên mặt phẳng $\pi_2$ lần lượt bằng $a_1^2$ và $a_2^2$, và trên mặt phẳng $\pi_3$ - $b_1^2$ và $b_2^2$, tương ứng ($a_i > 0, b_i < 0$). Diện tích của các hình chiếu $M_1$ và $M_2$ lên $\pi_1$ không vượt quá $S_1$. Đó là lý do tại sao
$$V(M) = V(M_1) + V(M_2) \leq \sqrt{S_1} (a_1 b_1 + a_2 b_2) \leq \sqrt{S_1} \sqrt{a_1^2 + a_2^2} \sqrt{b_1^2 + b_2^2} = \sqrt{S_1 S_2 S_3}.$$

Bất bình đẳng
$$(a_1 b_1 + a_2 b_2)^2 \leq (a_1^2 + a_2^2) (b_1^2 + b_2^2),$$

mà chúng tôi sẽ sử dụng tương đương với ước tính $(a_1 b_2 - a_2 b_1)^2 \geq 0$.

Chứng minh bổ đề cho bất kỳ $n$ nào cũng có thể được chứng minh bằng cách đi qua $n$, hoặc tương tự như trường hợp $n = 2$ sử dụng đồng thời (2) Bất đẳng thức Cauchy («Kvant», 1972, số 1)
$$(a_1 b_1 + \dots + a_n b_n)^2 \leq (a_1^2 + \dots + a_n^2) (b_1^2 + \dots + b_n^2).$$

Bây giờ chứng minh bất đẳng thức (1) kết thúc như thế này. Chúng ta hãy cắt đa giác M thành những con voi nằm ngang. Với độ dày nhỏ, giả sử thể tích của đa giác M và sự kết hợp của một số đối tượng được đặt chồng lên nhau (cũng như diện tích hình chiếu tương ứng của chúng) khác nhau ở góc nhỏ như thế nào. Chính xác:

Cho $h$ là một số dương nhỏ. Chúng ta hãy vẽ các mặt phẳng ngang đủ dày đặc (bao gồm tất cả các đỉnh của đa giác M) để M được cắt thành $n$ từ có độ dày $h_i \leq h(l_1 = h_1 + h_2 + \dots + h_n)$. Chúng ta hãy đặt lớp thứ $i$ theo một đường thẳng có chiều cao $h_i$ và đáy nằm ngang trùng với hình chiếu của lớp này lên mặt phẳng cát tuyến thứ $i$.

Đặt $M'$ là tập hợp của các đặc điểm được xây dựng. Hình chiếu $M'$ lên $l_1$ trùng với hình chiếu của đa giác M lên $l_1$: $S_1' = S_1$, và diện tích $S_2'$ và $S_3'$ của các hình chiếu $M'$ trên mặt phẳng $l_2$ và $l_3$ không nhỏ hơn diện tích $S_2$ và $S_3$, tương ứng, và sự khác biệt so với chúng bằng tổng diện tích của các hình chữ nhật được bảo vệ trong Hình 1. Tổng này không lớn hơn $cl_1 h$, trong đó $c$ là độ alta lớn nhất của các góc được hình thành bởi hình chiếu của các cạnh của đa giác M trên mặt phẳng $l_2$ và $l_3$ với phương thẳng đứng. Đó là lý do tại sao
$$V(M) \leq V(M') \leq \sqrt{S_1' S_2' S_3'} \leq \sqrt{S_1 (S_2 + cl_1 h) (S_3 + cl_1 h)}.$$

⟦folio 25⟧

Vì bất đẳng thức này đúng với mọi $h$, $V \leqslant \sqrt{S_1 S_2 S_3}$.

Thứ hai lời giải. Chúng ta hãy giới thiệu một hệ tọa độ hình chữ nhật trong không gian, lấy các trục $\pi_1 \cap \pi_2$, $\pi_1 \cap \pi_3$, $\pi_2 \cap \pi_3$ lần lượt là các trục $Ox$, $Oy$ và $Oz$. Giả sử $[a; b]$ là một đoạn của trục $Oz$ trên đó hình đa diện $M$ được chiếu. Qua mỗi điểm $z \in [a; b]$ ta vẽ một mặt phẳng nằm ngang. Gọi $S(z)$ là diện tích mặt cắt ngang của khối đa diện của mặt phẳng này, và $l_2(z)$ và $l_3(z)$ lần lượt là độ dài hình chiếu của mặt cắt này trên các mặt phẳng $\pi_2$ và $\pi_3$. Có thể chứng minh rằng

$$V = \int_a^b S(z) dz. \tag{4}$$

Trong sách giáo khoa “Hình học 9-10” (§58 và §66), công thức này được rút ra từ các ví dụ và cho vật quay; đối với các polytop tùy ý, cách chứng minh cũng tương tự. Chúng ta cũng sẽ sử dụng công thức (hãy tự chứng minh nhé!)

$$S = \int_a^b l(z) dz, \tag{5}$$

trong đó $S$ là diện tích của đa giác lồi nằm trong mặt phẳng $xOz$ và $l(z)$ là độ dài của đoạn mà một đường thẳng song song với trục $Ox$ và đi qua điểm $z \in [a; b]$ cắt với đa giác (Hình 2). Ngoài ra, chúng ta sẽ cần bất đẳng thức tích phân Bunyakovsky, tương tự như bất đẳng thức (3):

$$\left| \int_a^b f(z) g(z) dz \right| \leqslant \sqrt{\int_a^b f^2(z) dz} \cdot \sqrt{\int_a^b g^2(z) dz}.$$

Chúng ta sẽ chứng minh điều đó cho các hàm liên tục $f$ và $g$.

Bằng chứng. Hãy để $\lambda \in \mathbb{R}$. Hãy xem xét chức năng

$$\varphi(\lambda) = \int_a^b (f(z) - \lambda g(z))^2 dz =$$

$$= \lambda^2 \int_a^b g^2(z) dz - 2\lambda \int_a^b f(z) g(z) dz + \int_a^b f^2(z) dz = A\lambda^2 - 2B\lambda + C$$

$$\left( A = \int_a^b g^2(z) dz, B = \int_a^b f(z) g(z) dz, C = \int_a^b f^2(z) dz \right).$$

Hàm $\varphi$ là một tam thức bình phương nhận các giá trị không âm cho bất kỳ $\lambda$ nào. Do đó, $\frac{D}{4} = B^2 - AC \leqslant 0$ hoặc $B \leqslant \sqrt{A} \cdot \sqrt{C}$, và đây là bất đẳng thức bắt buộc. (Chứng minh bất đẳng thức (3) bằng phép tương tự.)

Bây giờ hãy hoàn thành lời giải bài toán thứ hai.

$$V = \int_a^b S(z) dz = \int_a^b \sqrt{S(z)} \cdot \sqrt{S(z)} dz.$$

Vì $S(z) \leqslant S_1$ với bất kỳ $z \in [a; b]$ nào, chúng ta nhận được

$$V \leqslant \sqrt{S_1} \cdot \int_a^b \sqrt{S(z)} dz.$$

Theo điểm a) $S(z) \leqslant l_2(z) l_3(z)$. Đó là lý do tại sao

$$V \leqslant \sqrt{S_1} \cdot \int_a^b \sqrt{l_2(z)} \cdot \sqrt{l_3(z)} dz.$$

Áp dụng bất đẳng thức tích phân Bunyakovsky và công thức (5), chúng ta thu được

⟦folio 26⟧

M610. Chúng tôi sửa $k \in \mathbb{N}$.
a) Xét tập hợp tất cả các bộ số nguyên $a_1, \dots, a_k$ sao cho $0 \leq a_1 \leq a_2 \leq \dots \leq a_k \leq k$; chúng ta hãy biểu thị số lượng các bộ như vậy bằng $N$. Chúng ta hãy xem xét trong số đó những cái mà $a_k = k$; hãy để số của họ là $M$. Chứng minh rằng $N = 2M$.
b) Chúng ta hãy áp đặt một ràng buộc bổ sung cho các tập hợp đang được xem xét: tổng $a_1 + \dots + a_k$ chia hết cho $k$. Đặt các số tương ứng là $N'$ và $M'$. Chứng minh rằng $N' = 2M'$ (Từ Hình 1 cho thấy rõ rằng với $k = 3$ các số này là $M = 10$, $N = 20$, $M' = 4$, $N' = 8$).

Cơm. 1.

Cơm. 2.

Cơm. 3.

Cơm. 4.

Cơm. 5.

Như đã biết, nếu hai tập hợp có cùng số phần tử thì có thể thiết lập sự tương ứng một-một giữa chúng. Nói đúng ra, đây là sự chắc chắn về cái bằng nhau trong tập hợp các phần tử, nhưng thực tế này đôi khi bị lãng quên. Trong khi đó, thường thì đẳng thức của hai số được thiết lập chính xác thông qua sự tương ứng một-một của tập hợp.

Ta cần chứng minh rằng có đúng một nửa số tập hợp chứa $a_k = k$. Do đó, chúng tôi sẽ cố gắng thiết lập sự tương ứng một-một giữa các tập hợp của chúng và các tập hợp còn lại với $a_k < k$.

Không thể liên kết tập hợp $(a_1, a_2, \dots, a_k)$ với tập hợp $(a_k, a_{k-1}, \dots, a_1)$ vì tập hợp mới không tăng. Bạn có thể thử so sánh tập $(a_1, \dots, a_k)$ với tập $(k - a_k, k - a_{k-1}, \dots, k - a_1)$: nó đã tối giản rồi, nhưng... $k - a_1$ không nhất thiết phải nhỏ hơn $k$. Do đó sự tương ứng này không giải quyết được bài toán. (Câu hỏi: sự tương ứng này giải quyết được bài toán nào?)

Điều này có nghĩa là cần có sự tương ứng phức tạp hơn. Để xây dựng nó, chúng ta cần khái niệm sơ đồ Young của một tập hợp đã cho.

Đây là gì, chúng ta có thể giải thích rõ nhất bằng một ví dụ: tập hợp $(0, 0, 2, 3, 5)$ tương ứng với sơ đồ hiển thị trong Hình 2 - trên mỗi dòng có số ô vuông bằng số tương ứng.

Sơ đồ Young bổ sung thành hình vuông (Hình 3). Sau đó, rõ ràng là ý tưởng ban đầu của chúng tôi là có một sơ đồ không phải màu đỏ mà là các hình vuông màu trắng (và theo đó, không phải ở phía dưới bên trái mà ở phía trên bên phải).

Bây giờ chúng ta hãy thử Hình 3 bổ sung với sơ đồ dọc - như trong Hình 4. Nếu không có sơ đồ này ở bên trái màu xanh lam, chúng ta sẽ có tập hợp $(2, 2, 3, 4, 4)$. Hãy để chúng tôi làm cho bộ này bổ sung cho bộ $(0, 0, 2, 3, 5)$.

Một ví dụ khác được hiển thị trong Hình 5.

Rõ ràng là nếu tập ban đầu là $(a_1, \dots, a_k)$ và tập bổ sung là $(b_1, \dots, b_k)$, thì $a_k = k$ khi và chỉ khi $b_k < k$. Thật vậy, $a_k = k$ nếu ô phía trên bên phải có trong sơ đồ Young chính và $a_k < k$ nếu nó được bao gồm trong ô bổ sung.

Sự tương ứng mà chúng tôi đã thiết lập giữa các tập hợp có $a_k = k$ và các tập hợp có $a_k < k$ rất đơn giản và một-một. Như vậy ta đã giải được a). Ngoài ra, tổng các số trong tập ban đầu và tập bổ sung bằng $k^2$ (trong ví dụ của chúng tôi - 25). Do đó, tổng các số trong tập hợp bổ sung chia hết cho $k$ khi và chỉ khi tổng các số trong tập hợp ban đầu chia hết cho $k$. Điều này giải quyết 6).

Một lời giải khác cũng được bao gồm: các số $N$ và $M$ có ​​thể được đếm vô thời hạn. Chính xác:

Bổ đề a. Số tập hợp số nguyên $a_1, \dots, a_m$ sao cho $0 \leq a_1 \leq \dots \leq a_m \leq k$ là $C_{k+m}^m$.

Bằng chứng. Hãy xem xét tập hợp $(b_1, \dots, b_m)$, trong đó $b_i = a_i + i$: $b_1 = a_1 + 1$, $b_2 = a_2 + 2$, v.v. Khi đó, rõ ràng, $1 < b_1 < b_2 < \dots < b_m < k + m$, nghĩa là, $(b_1, \dots, b_m)$ là một tập hợp tùy ý gồm $m$ số nguyên của các số $k + m$ đầu tiên của chúng. Số bộ như vậy là $C_{k+m}^m$.

Số tập hợp trong đó $a_k \leq k$ bằng $C_{k+k}^k$ theo bổ đề. Nếu $a_k = k$, thì tất cả những gì chúng ta phải làm là chọn các số $a_1, \dots, a_k - 1$ sao cho $0 \leq a_1 \leq \dots \leq a_k - 1 \leq k$; số của họ là $C_{k+k-1}^k$. Vẫn còn phải tính rằng $2C_{k+k-1}^k$ bằng $C_{k+k}^k$.

A. Đám đông

⟦folio 27⟧

F613. Một hộp khối lượng M đặt trên bàn nằm ngang. Trong một hộp có lực nén ngoài k, treo một vật có khối lượng m. Ở biên độ dao động nào của tải thì hộp bắt đầu nảy lên trên bàn?

Vì một vật có khối lượng m được treo trong một vòng tròn nên ở trạng thái cân bằng, chùm tia bị giãn bởi các giá trị Δx₁ (xem dấu) sao cho k Δx₁ = mg, tức là

Δx₁ = mg/k.

Hộp chịu tác dụng của lực hấp dẫn Mg và phản lực T của lò xo. Lực T có giá trị tuyệt đối bằng lực đàn hồi - T = kx - và hướng xuống dưới khi lò xo bị kéo căng và hướng lên trên khi lò xo dốc bị kéo dãn. Hộp bắt đầu nảy lên khi lực T lớn hơn lực Mg: T ≥ Mg. Tại thời điểm T = Mg thì độ dốc Δx₂ của lò xo bằng

Δx₂ = Mg/k.

Do đó, hộp bắt đầu nảy lên khi biên độ dao động của lò xo bằng

A = Δx₁ + Δx₂ = (M + m) g/k.

L. Bakanina

F614. Trong một bình kín có khí nitơ ở nhiệt độ phòng t₀ = 20°C và áp suất p₀ = 10⁵ Pa. Một số dao động của tải đã được đưa vào bình; hộp bắt đầu nảy lên trên bàn với nhiệt độ t₁ = -196°C (nhiệt độ của nitơ ở áp suất khí quyển bình thường). Nitơ lỏng bay hơi nhanh chóng, sau đó nhiệt độ trong bình trở thành t₂ = -140°C. Sau khi bình đạt đến nhiệt độ phòng, áp suất p = 1,5 10⁵ Pa được thiết lập trong đó. Xác định nhiệt bay hơi mol của mỗi nitơ. Nhiệt dung của khí nitơ ở thể tích không đổi là Cₙ = 20,8 J/ (mol K).

Vì sự bay hơi của nitơ, theo các điều kiện bài toán, xảy ra nhanh chóng nên có thể tránh được sự trao đổi nhiệt độ với môi trường. Sự bay hơi của khối lượng nitơ Δm và sự nóng lên của nó từ nhiệt độ t₁ đến nhiệt độ t₂ xảy ra do nhiệt lấy đi từ khối lượng nitơ m ban đầu. Viết phương trình cân bằng nhiệt:

C_V m/M (t₀ - t₂) = Δm/M [λ + C_V (t₂ - t₁)].

Từ đây ta tìm được nhiệt mol bay hơi của từng nitơ λ:

λ = [ (t₀ - t₂) / Δm/m] (t₂ - t₁)] C_V.

Theo các điều kiện bài toán, áp suất cuối cùng trong bình lớn hơn 1,5 lần so với áp suất ban đầu P₀ ở cùng nhiệt độ phòng t₀. Điều này có nghĩa là khối lượng nitơ trong bình đã tăng 1,5 lần, nghĩa là (m + Δm)/m = 1,5 và Δm/m = 0,5. Thay giá trị này từ điều kiện cho các giá trị của t₀, t₁, t₂ và C_V vào biểu thức (*), ta thấy

λ = 5500 J/mol.

V. Belonukin

F615. Trong trường hợp phóng điện bằng khí không tự duy trì, sự phụ thuộc của dòng điện I qua khí thải thô vào điện áp U giữa các điện cực của khí thô có dạng như hình 1. Một ống mắc nối tiếp có điện trở chấn lưu R = 3 · 10⁸ Ohm được nối với nguồn có EMF không đổi E = 6 kV. Tìm dòng điện chạy qua dây dẫn và điện áp trên dây sẽ là bao nhiêu. Bỏ qua điện trở trong của nguồn.

Sơ đồ kết nối của máy tạo nhám xả khí được thể hiện trên Hình 2.

Hãy tìm giá trị tối thiểu của emf nguồn mà tại đó nó sẽ đạt đến độ bão hòa thông qua phần thô. Để làm điều này, hãy hoàn thành định luật Ohm cho mạch:

ε_min = U_H + I_H R,

trong đó U_H = 10³ V, I_H = 10⁻⁵ A (xem Hình 1). Thay các giá trị bằng số, ta tìm được ε_min = 4 kV.

Trong trường hợp của chúng tôi, emf của nguồn là ε > ε_min. Do đó, dòng điện qua phần cứng hơn bằng dòng bão hòa. Ví dụ: điều này được xác định bởi điều kiện ε = U + I_H R, từ đó

U = ε - I_H R = 3 kV.

Độ lớn của dòng điện qua máy mài có thể được xác định theo cách khác. Giả sử dòng điện I trong mạch nhỏ hơn dòng bão hòa. Hãy viết định luật Ohm cho trường hợp này:

ε = I(R_Tp + R),

trong đó R_Tp là điện trở trong của phần thô. Giá trị của R_Tp được tìm thấy từ độ dốc của tiết diện tuyến tính của dòng điện-điện áp xa-

⟦folio 28⟧

Ống Ractor (xem Hình 1):

$$R_{\text{тр}} = \frac{U_H}{I_H} = 10^8 \text{ Ом.}$$

Như vậy,

$$I = \frac{\mathcal{E}}{R_{\text{тр}} + R} = 15 \text{ мкA.}$$

Giá trị hiện tại tìm thấy lớn $I_H$. Do đó, giả định của chúng tôi rằng $I < I_H$ là không chính xác. Dòng điện qua ống bằng dòng điện bão hòa.

V. Mozhaev

Cơm. 1.

Cơm. 2.

F616. Chiều dài dây tóc tích tụ của bóng đèn là $l$ và đường kính là $d$. Chiều dài $l_1$ và đường kính $d_1$ của một bóng đèn khác được thiết kế cho cùng điện áp nguồn nhưng có quang thông đầu vào cao hơn, nếu hiệu suất của cả hai bóng đèn là như nhau?

Đặt $W$ và $W_1$ là công suất tiêu thụ từ mạng của đèn thứ nhất và đèn thứ hai. Khi đó, năng lượng do đèn phát ra dưới dạng ánh sáng (thông lượng ánh sáng) lần lượt bằng $E = \eta W$ và $E_1 = \eta W_1$, trong đó $\eta$ là hiệu suất của đèn.

Ở trạng thái cân bằng, công suất $W$ ($W_1$) mà đèn nhận được từ mạng phải bằng công suất $P$ ($P_1$) mà đèn phát ra dưới dạng ánh sáng và nhiệt. Công suất $P$ ($P_1$), rất indo, tỷ lệ thuận với diện tích $S$ ($S_1$) của bề mặt dây tóc và một số hàm của nhiệt độ $f(T)$ ($f(T_1)$). Kể từ đây,

$$P = W = k_1 S f(T), \quad W_1 = k_1 S_1 f(T_1),$$

trong đó $k_1$ là hệ số tỷ lệ. Quang thông do đèn phát ra cũng tỉ lệ thuận với diện tích bề mặt của dây tóc và một hàm số nào đó của nhiệt độ:

$$E = k_2 S \varphi(T), \quad E_1 = k_2 S_1 \varphi(T_1).$$

Và vì $E = \eta W$, nên

$$k_2 \varphi(T) = \eta k_1 f(T), \quad k_2 \varphi(T_1) = \eta k_1 f(T_1).$$

Từ những đẳng thức này, rõ ràng hiệu suất của bóng đèn được xác định bởi nhiệt độ của dây tóc. Do đó, với cùng hiệu suất của hai đèn, nhiệt độ dây tóc của chúng tích lũy, tức là $T_1 = T$. Điều này có nghĩa là

$$\frac{E_1}{E} = \frac{k_2 S_1 \varphi(T)}{k_2 S \varphi(T)} = \frac{S_1}{S} = \frac{d_1 l_1}{dl}.$$

Theo điều kiện bài toán $E_1: E = 2$, tức là

$$\frac{d_1 l_1}{dl} = 2.$$

Ở điện áp lưới điện $U$

$$E = \eta W = \eta \frac{U^2}{R}, \quad E_1 = \eta W_1 = \eta \frac{U^2}{R_1},$$

trong đó $R = \varrho \frac{4l}{\pi d^2}$, $R_1 = \varrho \frac{4l_1}{\pi d_1^2}$ là điện trở của dây tóc đèn ($\varrho$ là điện trở suất của vật liệu dây tóc ở nhiệt độ hoạt động của đèn). Do đó, $\frac{E_1}{E} = \frac{ld_1^2}{l_1 d^2}$, và theo điều kiện,

$$\frac{l d_1^2}{l_1 d^2} = 2.$$
