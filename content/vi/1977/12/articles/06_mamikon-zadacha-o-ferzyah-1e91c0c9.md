---
id: 1977-12-mamikon-zadacha-o-ferzyah-1e91c0c9
issue: kvant_1977_12
year: 1977
number: "12"
title: Bài toán về nữ hoàng
authors:
  - Мамикон М.
rubric: osnovnye-stati
page_first: 24
page_last: 28
page_labels: 22, 23, 25, 26
tag: WEXQ
lang: vi
source: kvant_digital
extraction: vision
content_sha256: c2eb4dc07549f44302f11aaf29ee86a4c828b413bb0b68e95af1d44343aaeac1
prompt_sha256: draft-1
translated_from: content/ru/1977/12/articles/06_mamikon-zadacha-o-ferzyah-1e91c0c9.md
source_content_sha256: 3a8f453f68351f3e459f657882eec18e8e916ce87b1e5b9033d73576542811e3
translation_model: draft
translation_run: vi-draft-2026-10-31
translation_quality: draft
---

⟦folio 22⟧

M. Mamikon

Bài toán về nữ hoàng

1. Sản xuất bài toán
Trên một bàn cờ chung 8x8, có thể đặt năm quân hậu sao cho chúng bao phủ tất cả các ô của bàn cờ. Bốn quân hậu là không đủ cho việc này (hãy chứng minh điều đó!). Bàn cờ 3x3 sẽ có một quân hậu được đặt ở ô trung tâm. Đối với bảng 6x6, trường của nó bằng nhau. Vì vậy, $F(11) \leq 5$. Từ Hình 2 có thể thấy rằng $F(10) \leq 5$ và $F(9) \leq 5$.

Việc tìm kiếm chính xác $F(n)$ cho $n$ lớn là khá khó khăn. Hơn nữa, trong một thời gian hợp lý, một máy tính chạy nhanh hoàn hảo không thể thực hiện tất cả các tùy chọn để đặt mười quân hậu trên một bàn cờ 20x20.

Đối với Pozny, có vẻ thú vị khi tìm thấy ít nhất các ước tính—trên và dưới—cho $F(n)$. Đây là nội dung sản phẩm bài toán về nữ hoàng của chúng tôi sẽ bao gồm.

2. Điểm
Nếu trên bảng $n \times n$ chúng ta đặt $n$ quân hậu dọc theo một trong các đường chéo chính, sau đó loại bỏ hai quân hậu ngoài cùng, thì những quân hậu $n-2$ còn lại cũng sẽ là tất cả các ô vuông của bàn cờ. Có nghĩa,

$$F(n) \leq n-2.$$

Nếu, trong một sự sắp xếp gồm $F(n)$ quân hậu, trong đó mỗi ô được chiếm, không có quân hậu nào ở cạnh bàn cờ, thì các ô cạnh $4(n-1)$ tạo thành bàn cờ phải là quân hậu từ bên trong khung này. Vì mỗi quân hậu sẽ ở cùng một hướng nên sẽ có chính xác 8 ô của khung này. Ngay cả khi tất cả các quân hậu đều là những hình vuông khác nhau của khung, thì vẫn cần phải có $$\frac{4(n-1)}{8} = \frac{n-1}{2}$$

Cơm. 1.

Ba quân hậu là đủ (Hình 1), hai quân hậu là không đủ.

Chúng ta hãy biểu thị bằng $F(n)$ số lượng quân hậu tối thiểu sao cho, nếu được đặt đúng cách trên bàn cờ $n \times n$, thì mỗi ô của nó đều bị tấn công (một ô có quân hậu chiếm giữ được coi là đã bị bắt). Với $3 \leq n \leq 8$ số $F(n)$ đã biết:

| $n$ | 3 | 4 | 5 | 6 | 7 | 8 |
| :--- | :--- | :--- | :--- | :--- | :--- | :--- |
| $F(n)$ | 1 | 2 | 3 | 3 | 4 | 5 |

Hình 2 hiển thị bàn cờ $11 \times 11$ và 5 quân hậu trên đó, mỗi quân hậu

⟦folio 23⟧

$$\frac{1}{2}n - \frac{1}{2} \text{ферзей. Итак, в этом случае}$$
$$F(n) \geq \frac{1}{2}n - \frac{1}{2}. \quad (2)$$

Ước tính (2) cũng đúng trong trường hợp tổng quát. Chứng minh điều đó. (Gợi ý. Từ (1) suy ra rằng đối với bất kỳ sự sắp xếp nào của $F(n)$ quân hậu trên bảng trạng thái, sẽ có ít nhất hai tệp quân hậu tự do và hai cấp bậc tự do.)

Từ (2) $F(11) \geq 5$. Trong đoạn 1, chúng tôi đã chỉ ra rằng $F(11) \leq 5$. Vì vậy, $F(11) = 5$. $F(10) = 5$ thu được tương tự. Điều đáng tò mò là không thể đạt được đẳng thức $F(9) = 5$ theo cách này. Hãy tự mình chứng minh điều đó!

Cơm. 3.

Cơm. 4. $k = 3, l = 1$.

Bây giờ chúng ta hãy cải thiện giới hạn trên (1).

3. $\langle k, l \rangle = \text{решетка}$
Hãy đặt các quân hậu lên một bàn cờ vô hạn bằng nước đi bên trái của quân $\langle k, l \rangle$-mã (quân mã thông thường là quân $\langle 2, 1 \rangle$-mã), cụ thể là: đầu tiên đặt quân hậu vào một ô tùy ý; sau đó chúng ta sẽ đặt thêm bốn quân hậu như trong Hình 3; Chúng ta sẽ làm tương tự với từng quân hậu được đặt, v.v. Sự sắp xếp kết quả của vô số quân hậu được gọi là quân hậu $\langle k, l \rangle$-lưới. Mỗi lưới $\langle k, l \rangle$ là một lưới hình vuông, được xoay tương ứng với bàn cờ (Hình 4).

Di chuyển dọc theo hàng $^*$), định kỳ chúng ta sẽ gặp các nữ hoàng. Chúng ta hãy biểu thị độ dài của chu kỳ mạng dọc theo hàng bằng $W_p$. Ví dụ: đối với mạng $\langle 3, 1 \rangle$ $W_p = 10$ (Hình 4).

Di chuyển dọc theo đường chéo, chúng ta cũng sẽ gặp quân hậu theo định kỳ. Chúng ta hãy biểu thị độ dài của khoảng thời gian cách tử dọc theo đường chéo bằng $W_\partial$. Vì $\langle 3, 1 \rangle$-lưới $W_\partial = 5$ (Hình 4).

Bài tập

1. Đối với mạng $\langle k, l \rangle$ $W_p = \frac{k^2 + l^2}{d}$, trong đó $d$ là ước số chung nhất của các số $k$ và $l$.
2. Đối với mạng $\langle k, l \rangle$ $W_\partial = \frac{k^2 + l^2}{c}$, trong đó $c$ là ước số chung nhất của các số $k + l$ và $k - l$.
3. Nếu $k$ và $l$ là các số nguyên tố cùng nhau có số chẵn lẻ khác nhau, thì $W_p = W_\partial = k^2 + l^2$.
4. Các chu kỳ của mạng $W' \langle tk, tl \rangle$ và các chu kỳ của mạng $W \langle k, l \rangle$ có liên quan bởi các quan hệ $W_p = tW_p$ và $W_\partial = tW_\partial$.

4. Thiết lập Nữ hoàng cơ bản
Cho $k$ và $l$ là số nguyên tố cùng nhau của các số chẵn lẻ khác nhau. Hãy xem xét mạng $\langle k, l \rangle$. Đối với cô ấy, cả hai tiết $W_p, W_\partial$ đều bằng $W_0 = k^2 + l^2$ (bài tập 3).

Hãy cắt một bảng vuông $W_0 \times W_0$ từ bảng vô hạn của chúng ta để quân hậu vào trung tâm

$^*)$ Hàng dọc hoặc ngang.

⟦folio 25⟧

Hãy để chúng tôi chứng minh rằng các ô bị hỏng đối xứng với bất kỳ đường chéo chính nào.

Nếu một ô bị hỏng có màu xám (Hình 6), thì một ô đối xứng (so với khoảng cách của đường chéo chính) cũng có màu xám và tất cả các ô đều bị hỏng. Nếu ô bị vỡ có màu trắng thì có một quân hậu trên một trong các đường chéo đi qua ô đó. Nếu đây là đường chéo của đường chéo và đường chéo của đường chéo chính đang được xem xét, thì ô đối xứng mà chúng ta quan tâm sẽ là cùng một nữ hoàng. Nếu nó song song - với quân hậu đối xứng ở giữa (xem đường chéo màu xanh lá cây trong Hình 6).

Từ thực tế là với tính đối xứng so với đường chéo chính và góc quay 90°, các ô bị vỡ biến thành các ô bị hỏng, dễ dàng suy ra rằng tập hợp các ô bị hỏng là đối xứng so với trục dọc ở giữa và trục ngang ở giữa (tại sao?).

Điều này có nghĩa là từ quan điểm của các ô bị vỡ hoặc không bị vỡ, tất cả tám quãng tám mà bảng được chia theo các hàng trung tâm và các đường chéo chính đều bằng nhau (trong Hình 7, một trong những quãng tám như vậy được ký hiệu bằng chữ O).

6. Nữ hoàng bổ sung

Ở cuối đoạn 4, chúng tôi đã lưu ý rằng cả bốn đường chéo của bàn cờ đều là quân hậu của thiết lập Cơ bản. Do đó, vẫn chỉ xem xét các đường chéo có số lẻ.

Số đường chéo lẻ của một hướng trên toàn bàn cờ không có đường chéo chính và đường chéo góc “vuông đơn” (đập với quân hậu trung tâm) là 2 ($W_0-1$); ở một bên của đường chéo chính sẽ có $W_0-1$ và trong một quãng tám sẽ có ít hơn hai lần: $\frac{W_0-1}{2}$.

Con số này trùng với số lượng quân hậu trong thiết lập Cơ bản, nằm ở một bên của đường chéo chính của hướng được đánh dấu. Mỗi quân hậu được tô bóng trong Hình 7 sẽ được đặt trên một trong các đường chéo lẻ đi qua quãng tám $O$. Do đó, trong số các đường chéo lẻ của bát giác có các đường chéo “trống” (trên đó không có quân hậu), rất indo, nhiều như có quân hậu trong tam giác góc $T$. Hãy biểu thị số này bằng $\varphi(n)$.

Hãy xem xét một trong các đường chéo trống của bát phân $O$. Thêm nó vào một hình chữ thập đối xứng (Hình 8). Do các ô đối xứng nên cũng không có quân hậu trên ba đường chéo còn lại của hình này. Để chụp các ô của hình này, chỉ cần đặt thêm hai quân hậu vào các ô đối xứng $A$ và $B$ của đường ngang trung tâm (Hình 8).

Vì số đường chéo trống trong một quãng tám là $\varphi(n)$ nên chỉ cần đặt thêm $2\varphi(n)$ quân hậu là đủ.

⟦folio 26⟧

Cơm. 9. $k = 3, l = 2$.

Vì thế,
$$F(n) \leqslant W_0 + 2\varphi(n).$$

7. Nữ hoàng và hình vuông

Để ước tính từ phía trên số $\varphi(n)$ quân hậu trong tam giác góc $T$ (Hình 7), chúng ta nhớ lại rằng các quân hậu khoảng cách chức năng nằm ở các nút mạng trên cạnh có chiều dài $\sqrt{(2k)^2 + (2l)^2} = 2\sqrt{k^2 + l^2}$ (chiều dài của ô vuông bàn cờ được lấy làm một), xoay tương ứng với bàn cờ (Hình 4, 6).

Chúng ta hãy di chuyển mạng này sao cho các quân hậu ở giữa các ô vuông (Hình 9). Khi đó, số quân hậu trong tam giác $T$ sẽ không vượt quá số “hình vuông đã dịch chuyển” có tâm nằm ở $T$. Vì mỗi hình vuông như vậy nằm hoàn toàn trong vùng lân cận $\frac{d}{2}$ của tam giác $T$ (Hình 10; $d$ là độ dài đường chéo của hình vuông), nên số lượng của chúng không vượt quá diện tích của hình vuông so với diện tích của vùng lân cận này.

Bài tập 5. Lân cận $\varepsilon$ của hình phẳng $F$ là hợp của các đường tròn bán kính $e$ với tâm tại mỗi điểm của hình $F$. Chứng minh rằng diện tích lân cận $\varepsilon$ của một đa giác lồi bằng $S + P\varepsilon + \pi e^2$, trong đó $S$ là diện tích của đa giác, $P$ là chu vi của nó.

Độ dài của tam giác $T$ bằng $\frac{n}{2}$. Cạnh của hình vuông mà mạng được tạo thành là $2\sqrt{k^2 + l^2} = 2\sqrt{\frac{n-1}{2}} = \sqrt{2}\sqrt{n-1}$.

Điều này có nghĩa là tỷ lệ diện tích yêu cầu bằng
$$\frac{n^2}{8} + \left(1 + \frac{\sqrt{2}}{2}\right)n\sqrt{n-1} + \pi(n-1) \over 2(n-1)$$.

Vì $W_0 = k^2 + l^2 = \frac{n-1}{2}$, từ (3)
$$F(n) \leqslant \frac{5}{8}n + \left(1 + \frac{\sqrt{2}}{2}\right)\frac{n}{\sqrt{n-1}} + \frac{1}{8(n-1)} + \pi - \frac{3}{8}.$$

Do thực tế là $\frac{n}{\sqrt{n-1}} < 2\sqrt{n}$ và $\frac{1}{8(n-1)} < 1$, với $n \geqslant 2$ và $1 + \frac{\sqrt{2}}{2} < 2$, chúng tôi thu được các bảng ở bên cạnh các ô $2(k^2 + l^2) + 1$, trong đó $k$ và $l$ là các số nguyên tố tương đối có số chẵn lẻ khác nhau, giới hạn trên cuối cùng:
$$F(n) \leqslant \frac{5}{8}n + 4\sqrt{n} + 5.$$

8. Bảng tùy chỉnh

Bây giờ chúng ta có một bảng $n \times n$, trong đó $n \geqslant 11$. Hãy lấy $m$ tự nhiên sao cho $8m^2 + 3 \leqslant n < 8(m+1)^2 + 3$. Vì $n \geqslant 11$ nên có $m$ như vậy. Lưu ý rằng $8m^2 + 3 = 2[(2m)^2 + 1^2] + 1 = 2(k^2 + l^2) + 1$, trong đó $k = 2m, l = 1$.
