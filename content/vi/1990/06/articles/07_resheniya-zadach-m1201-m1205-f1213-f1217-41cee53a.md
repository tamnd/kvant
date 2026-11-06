---
id: 1990-6-resheniya-zadach-m1201-m1205-f1213-f1217-41cee53a
issue: kvant_1990_6
year: 1990
number: "6"
title: Lời giải bài toán M1201—M1205; F1213—F1217
rubric: zadachnik-kvanta
rubric_sub: Задачник «Кванта»
page_first: 31
page_last: 39
page_labels: 29, 31, 32, 33, 34, 35, 36, 37
lang: vi
source: kvant_digital
extraction: vision
content_sha256: 1dbcfd525c7af5598f4846b5843406f5bb89de856cf40059602b9ad4c58e7e22
prompt_sha256: draft-1
translated_from: content/ru/1990/06/articles/07_resheniya-zadach-m1201-m1205-f1213-f1217-41cee53a.md
source_content_sha256: 9a2786d2a6f45dddcba0393564fd714ede3908957d5c95bd918585cfd03c7313
translation_model: draft
translation_run: vi-draft-gaps-2026-11-05
translation_quality: draft
---

⟦folio 29⟧

Lời giải bài toán

M1201—M1205, F1213—F1217

Các ứng cử viên của đảng $C$, rất indo, sẽ có thể vào tất cả 999 khu vực bầu cử (hình 1). Chúng ta hãy ước tính từ trên số lượng khu vực bầu cử mà đảng $C$ có ​​thể thua. Nếu ở $x$ quận $C$ có ít hơn $N/2$ người ủng hộ thì tổng số người ủng hộ (bằng 0,55 · 999 $N$; $N$ là số cử tri trong quận) không vượt quá

⟦folio 31⟧

---
running_head:
folio:
---

M1202. Từ đỉnh A của hình vuông ABCD vẽ hai tia vào bên trong hình vuông, trên đó vẽ các phân bố lại BK, BL, DM, DN từ các đỉnh B và D. Chứng minh rằng các đoạn KL và MN bằng nhau và các phân bố lại bằng nhau.

Chúng ta hãy xem xét một phép quay $R$ quanh tâm hình vuông một khoảng $90^\circ$, tại đó các điểm B và A sẽ lần lượt đi đến A và D. Hãy chứng minh rằng với phép quay này đoạn KL sẽ tiến tới đoạn MN (xem hìnhok) - qua đó bài toán sẽ được giải. Vì $\angle KBA = 90^\circ$ - $\angle KAB = \angle KAD$ và tương tự, $\angle KAB = \angle ADM$, tia BK với phép quay này sẽ đi vào tia AM, và tia AK vào DM. Do đó, giao điểm K của tia BK và AK sẽ tiến tới giao điểm M của tia AM và DM, tức là $R(K) = M$. Bằng cách tương tự, người ta chứng minh rằng $R(L) = N$.

V. Dubrovsky

M1203. Có thể cắt một hình vuông có cạnh 1 km thành a) 31 hình vuông; b) 30 hình vuông sao cho một hình có cạnh không quá 1 m.

Hình 1.

Hình 2.

Đáp số: cả hai nhiệm vụ đều có thể thực hiện được.
Ý tưởng tự nhiên nhất là cắt hình vuông thành 4 hình vuông nhỏ hơn; một trong những hình vuông thu được lại được chia thành 4 phần, v.v. (hình 1). Mỗi thao tác như vậy sẽ tăng số hình vuông lên 3, sau kích thước thứ mười của hình vuông, nó sẽ trở thành $3 \cdot 10 + 1 = 31$ và cạnh nhỏ nhất sẽ nhỏ hơn $2^{10} = 1024$ lần so với cạnh của hình vuông ban đầu. Điều kiện của điểm a) được đáp ứng.

Để trả lời câu hỏi ở điểm 6), hãy xem xét quy trình của chúng ta “ngược lại” - không phải cắt một hình vuông lớn thành hình nhỏ, mà là ghép một hình lớn từ các hình vuông nhỏ (bắt đầu bằng hình vuông $1 \times 1$). Trước bước cuối cùng, chúng ta sẽ có một hình vuông $512 \times 512$ được tạo thành từ 28 hình vuông nhỏ hơn. Trong số ba hình vuông mà chúng ta sắp thêm vào, chúng ta sẽ cố gắng lấy một hình vuông lớn hơn những hình còn lại một chút - để nó hấp thụ hình vuông nhỏ ở góc. Chúng ta sẽ lưu một hình vuông và cạnh của hình vuông lớn hiện lớn hơn cạnh của hình vuông nhỏ 1023 lần (hình 2).

Tuy nhiên, vấn đề lời giải, câu hỏi được đặt ra một cách tự nhiên - chính xác hơn là phân vùng "khóc" nên là gì:
Với mức tối đa $n$ thì hình vuông $n \times n$ có thể được cắt thành $k$ hình vuông, hình vuông nhỏ nhất có kích thước $1 \times 1$?

Tác giả đã sưu tầm một “bộ sưu tập” các phân vùng bản ghi, trong đó đặc biệt có phân vùng hình vuông $1121 \times 1121$ thành 27 ô vuông. Những ý tưởng được sử dụng để xây dựng những vách ngăn như vậy khá thú vị và chúng tôi hy vọng sẽ quay lại chủ đề này trên các trang tạp chí sau khi làm quen với những bức thư của độc giả.

S. Eliseev

⟦folio 32⟧

---
running_head:
folio:
---

M1204*. Cho các điểm A, B, C trên mặt phẳng - tâm của ba đường tròn. Mỗi vòng tròn phồng lên đều (bán kính tăng với tốc độ như nhau đối với tất cả các vòng tròn). Ngay khi hai vòng tròn chạm vào nhau, chúng sẽ “bật”—bán kính của chúng giảm xuống 0—và bắt đầu mở rộng. Có đúng không nếu các khoảng cách AB, BC, CA là số nguyên thì quá trình này có tính tuần hoàn?

Nghiên cứu xem quá trình này có thể diễn ra như thế nào nếu tam giác ABC là a) đều; b) cách đều nhau; b*) hình chữ nhật có cạnh 3, 4, 5. Trạng thái ban đầu có thể là tùy ý (không chỉ “không”).

Hình 1.

Chúng ta sẽ xem xét trường hợp tổng quát: bán kính ban đầu của bong bóng là tùy ý.

a) Tam giác ABC đều. Sau tiếng nổ đầu tiên, bán kính của hai bong bóng sẽ bằng 0. Lần bật thứ hai sẽ làm vỡ cả ba bong bóng. Quá trình sau đó sẽ được lặp lại định kỳ.

6-1) Tam giác ABC đều, đáy nhỏ hơn cạnh. Sau đó, ở lần vỗ tay đầu tiên hoặc thứ hai, hai bong bóng sẽ vỡ, tâm của chúng nằm ở đáy của hình tam giác. Hơn nữa, bán kính của chúng sẽ bằng (hình 1). Chẳng bao lâu nữa cả ba bong bóng sẽ vỡ đồng thời, sau đó một quá trình định kỳ bắt đầu. Số lần vỗ trong một chu kỳ (chu kỳ) phụ thuộc vào tỉ số giữa độ dài cạnh và đáy.

Bây giờ chúng ta hãy xem trường hợp còn lại từ quan điểm tổng quát hơn: 6-2) (đế lớn hơn cạnh) và c). Chúng ta thấy rằng trong những trường hợp này, quá trình này thường không mang tính tuần hoàn.

Gọi độ dài các đoạn BC, AC và AB lần lượt là a, b và c. Hãy để định nghĩa $a \leq b < c$. (Chúng tôi đã xem xét tùy chọn $b = c$.) Lưu ý rằng bong bóng có tâm ở điểm A và B (viết tắt: bong bóng A và B) chỉ có thể chạm vào khi bắt đầu quá trình. Sau đó, bong bóng C sẽ tham gia vào mỗi lần vỗ tay. Do đó, giá trị cụ thể của đại lượng $c$ không đóng vai trò gì (miễn là điều kiện $b < c$ được thỏa mãn). Cũng rõ ràng rằng không phải bản thân độ dài $a$ và $b$ mới quan trọng mà là tỷ lệ của chúng $r = b/a$. Vì vậy, chúng ta sẽ xét thêm tam giác ABC có các cạnh $BC = 1$, $AC = r \geq 1$ và đáy $AB > r$.

Hãy ký hiệu $x$ và $y$ bán kính của bong bóng A và B ngay sau một tiếng vỗ tay tùy ý. Tuy nhiên, sẽ có tiếng vỗ tay tiếp theo, tùy thuộc vào yếu tố nào lớn hơn - độ dài của cạnh đối diện với bong bóng hoặc độ chênh lệch giữa cạnh kia và bán kính của bong bóng này. Như vậy, sự biến đổi của các đại lượng $x$ và $y$ diễn ra theo quy luật nêu ở Bảng 1.

Bảng 1

| Tình trạng hiện tại | Chuyển đổi |
| :--- | :--- |
| 1 $y = 0, r - x > 1$ | $x_{\text{HOB}} = x + \frac{1}{2}, y_{\text{HOB}} = 0$ |
| 2 $y = 0, r - x = 1$ | $y_{\text{HOB}} = 0, x_{\text{HOB}} = 0$ |
| 3 $y = 0, r - x < 1$ | $y_{\text{HOB}} = (r - x)/2, x_{\text{HOB}} = 0$ |
| 4 $x = 0, 1 - y < r, y \neq 0$ | $x_{\text{HOB}} = (1 - y)/2, y_{\text{HOB}} = 0$ |

Ở đây $x_{\text{HOB}}$ và $y_{\text{HOB}}$ là các giá trị mới của $x$ và $y$ ngay sau lần vỗ tay tiếp theo. Tùy chọn $x = 0, 1 - y \geq r$ không được đưa vào bảng vì không thể thực hiện được với $r > 1$ và trong trường hợp

⟦folio 33⟧

---
running_head:
folio:
---

$r=1$ chỉ có thể chọn tùy chọn thứ hai $x=0$, $1-y=r$ (tức là $y=0$), được mô tả ở dòng 2.

Nghiên cứu bảng cho thấy từ trạng thái 3 (và chỉ từ trạng thái đó) chúng ta luôn chuyển sang trạng thái 4. Do đó, dòng 3 và 4 có thể gộp thành một (nhớ rằng nó tương ứng với hai tiếng vỗ tay). Việc xem xét hiện tập trung vào các trạng thái có $y=0$ (xem Bảng 2).

Bảng 2

| Tình trạng | Chuyển đổi | Số lần vỗ tay |
| :--- | :--- | :--- |
| 1 | $x<r-1$ | $x_{\text{HOB}}=x+\frac{1}{2}$ | 1 |
| 2 | $x=r-1$ | $x_{\text{HOB}}=0$ | 1 |
| 3 | $x>r-1$ | $x_{\text{HOB}}=(2-r+x)/4$ | 2 |

Do đó, chuỗi các giá trị của biến $x$, cố định tại thời điểm bong bóng bật lên $B$ và $C$, được xác định đệ quy theo công thức $x_{\text{HOB}}=f(x)$, trong đó hàm $f$ được xác định trên khoảng [0; $r$] theo bảng 2:

$$f(x)=\begin{cases}
x+1/2, & \text{ если } x<r-1, \\
0, & \text{ если } x=r-1, \\
(2-r+x)/4, & \text{ если } x>r-1.
\end{cases}$$

Đối với trường hợp $r=1$ (mục 6-2) bài toán đồ thị của hàm $f$ được hiển thị trong hình 2. Từ hình rõ ràng là quá trình tương tác là tuần hoàn đối với các giá trị ban đầu $x=0$ và $x=\frac{1}{3}$ (trong khoảng thời gian tương ứng có một tiếng vỗ tay đôi hoặc hai tiếng đơn). Trong các trường hợp khác, quá trình có xu hướng chuyển sang trạng thái “ổn định” $x=\frac{1}{3}$ và do đó nó không mang tính tuần hoàn.

Vì các trạng thái ban đầu $a$, $b$ và $c$ (theo giả định $a=b<c$) có thể là số nguyên, nên đáp số đối với câu hỏi đầu tiên bài toán là số âm.

Đối với mục c) $r$ bằng 4/3. Đồ thị của hàm số tương ứng $f$ được thể hiện ở hình 3. Đồ thị thể hiện một chu kỳ đơn bao gồm 5 lần vỗ tay. Giá trị cụ thể của các số $x_1$, $x_2$, $x_3$ (xem hình 2) có thể được tìm thấy từ hệ thống

$$\begin{cases}
x_2=x_1+\frac{1}{2} \\
x_3=\frac{x_2}{4}+\frac{1}{6}, \\
x_1=\frac{x_3}{4}+\frac{1}{6}.
\end{cases}$$

Chúng bằng nhau: $x_1=\frac{23}{90}$, $x_2=\frac{34}{45}$, $x_3=\frac{16}{45}$.

Sau khi xem xét một số trường hợp chọn giá trị ban đầu $x$, có thể dễ dàng chỉ ra rằng bất kỳ “quỹ đạo” nào của quá trình đều tiến tới chu trình được mô tả. Nếu như,

⟦folio 34⟧

---
running_head:
folio:
---

nói $x = x_1 + \varepsilon$, trong đó $\varepsilon$ đủ nhỏ, sau đó ở bước tiếp theo $b = f(x_1 + \varepsilon) = x_2 + \varepsilon$, sau đó là $x = f(x_2 + \varepsilon) = x_3 + \frac{1}{4} \varepsilon$, sau đó là $x = f(x_3 + \frac{1}{4} \varepsilon) = x_1 + \frac{1}{16} \varepsilon$. Do đó, chênh lệch $x - x_1$ giảm 16 lần sau 5 lần vỗ tay và quá trình này nhanh chóng tiến đến “chu kỳ giới hạn”.

Hãy nhớ lại rằng lúc đầu lời giải chúng tôi chia tất cả các kích thước tuyến tính cho $a$ (trong trường hợp này là cho 3). Khi tính đến điều này, đáp số đối với điểm c có thể được hình thành như sau: nếu tại thời điểm chạm bong bóng đầu tiên $B$ và $C$ bán kính của bong bóng $A$ bằng $\frac{23}{30}, \frac{34}{15}$ hoặc $\frac{16}{15}$, thì quá trình sẽ diễn ra tuần hoàn; nếu không thì không.

Trường hợp tổng quát (tam giác tùy ý) có thể được xem xét theo cách tương tự. Mặc dù khó khăn kỹ thuật ở đây tăng mạnh nhưng về cơ bản các loại hành vi du lịch mới vẫn chưa được phát hiện. Đối với trường hợp có bốn chuông trở lên thì đáp số (sau đây gọi là dạng) không rõ.

S. Fomin

M1205. Một cậu bé và một cô gái chơi trò chơi sau: cậu bé vẽ các đa giác không chồng lên nhau trên một mặt phẳng và cô gái tô màu chúng. Nếu hai đa giác có một cạnh chung thì phải sơn chúng bằng hai màu khác nhau. Số lượng màu nhỏ nhất được hoàn thành sẽ đủ để các cô gái tuân theo các quy tắc này,

Hãy gọi đa giác $M$ là đa giác $M_1$ nếu có thể xây dựng một chuỗi số nguyên gồm các đa giác giống nhau, bắt đầu bằng $M$ và kết thúc bằng $M_1$, trong đó các đa giác lân cận va chạm dọc theo một đoạn. Chỉ cần học cách tô màu một tập hợp các đa giác liên kết với nhau là đủ (những đa giác không được kết nối không thể va chạm nhau).

a) Đáp số: hai màu là đủ. Tất cả các tam giác đều kết nối với một tam giác nhất định $\Delta$ sẽ có cùng góc xoay từ $\Delta$ (như $\Delta_1$ trên hình 1) hoặc xoay $180^\circ$ đối với $\Delta$ (như $\Delta_2$ trên hình 1). Hình tam giác loại thứ nhất được sơn một màu, loại thứ hai - màu khác. Sau đó có một điều-

⟦folio 35⟧

---
running_head:
folio:
---

a) tam giác đều;
b) tam giác vuông cân;
b) hình vuông giống nhau?

Hình 1.

Hình 2.

Hình 3.

Hình 4.

Hãy tô màu các nút của nó bằng bốn màu, như minh họa trong hình 4. Để xác định cách tô màu hình vuông tiếp theo, hãy loại bỏ cạnh trên và cạnh phải khỏi ranh giới của nó. Hình vuông “mặt phẳng” còn lại luôn chứa chính xác một nút mạng - chúng ta sẽ lấy màu của nút này. Rõ ràng, các ô vuông “được bào” chứa các nút liên kết đơn không thể chạm vào nhau. Điều này có nghĩa là điều đúng sẽ được quan sát.

Nếu cô gái chỉ có ba hình vuông, thì hình vuông 1 và 2 sẽ nằm trên hình 5 và phải được tô màu giống nhau, nghĩa là trên hình 5, các thanh của hình vuông 1 và 2, 1 và 3, 2 và 4, 3 và 5 sẽ giống nhau. Nhưng ô 4 và ô 5 phải có màu khác nhau. Do đó, để tô màu các hình vuông trong hình 5, b, cần có ít nhất bốn màu.

Chúng tôi đề xuất chứng minh rằng trong một trò chơi có các hình vuông có kích thước tùy ý, một cô gái sẽ không có đủ màu sắc. Hãy nghĩ xem sẽ có bao nhiêu màu trong một trò chơi có các hình lục giác đều đều bằng nhau.

G. Kondak

⟦folio 36⟧

---
running_head:
folio:
---

F1213. Một sợi dây đồng nhất không dãn được treo hai đầu tại các điểm A và B, nằm ở các độ cao khác nhau (hình 1). Lực căng của dây tại điểm A là $T_A$. Tìm lực căng của dây tại điểm B nếu nó nằm h phía trên điểm A. Khối lượng của dây là m, chiều dài là l.

Hình 1.

Hình 2.

F1214. Sau một viên đạn được bắn theo phương ngang từ một ngọn núi cao h = 1 km với tốc độ $v_0 = 500$ m/s, viên đạn thứ hai được bắn ra sau thời gian $t_0 = 1$ s. Nó phải có tốc độ ban đầu tối thiểu là bao nhiêu và nó phải bay ra với góc bao nhiêu để bắt kịp viên đạn đầu tiên?

Hãy để chúng tôi trình bày hai lời giải trong số bài toán này.

1) Hãy tưởng tượng rằng chúng ta có một số dây cung tại điểm A. Hãy thả sợi dây có chiều dài nhỏ $\Delta l$ tại điểm A và chọn cùng độ dài $\Delta l$ tại điểm B. Rõ ràng, trong trường hợp này, công sẽ thực hiện bằng $(T_B - T_A)\Delta l$, trong đó $T_B$ và $T_A$ lần lượt là lực căng của dây tại các điểm B và A. Công này dùng để thay đổi thế năng của một đoạn dây có khối lượng $m\Delta l/l$ khi nâng lên độ cao h. Theo định luật bảo toàn năng lượng,

$$mg\frac{\Delta l}{l}h = (T_B - T_A)\Delta l,$$

chúng ta lấy nó từ đâu

$$T_B = T_A + \frac{mgh}{l}.$$

2) Hãy nối các điểm A và B bằng một mặt phẳng nghiêng nhẵn có chiều dài L và buộc dây dọc theo mặt phẳng này (hình 2). Rõ ràng là toàn bộ sợi dây phải cân bằng. Một đoạn dây nằm trên mặt phẳng giữ thăng bằng nhờ chênh lệch lực căng dây tại các điểm B và A:

$$T_B - T_A = \frac{mL}{l}g\frac{h}{L},$$

Và

$$T_B = T_A + \frac{mgh}{l}.$$

E. Tatarinova

Đầu tiên, hãy xem xét bài toán trong hệ thống báo cáo 1 được liên kết với bệ phóng (chúng tôi giả định rằng cả hai quả đạn đều được bắn từ cùng một bệ phóng nằm trên đỉnh núi (xem hình)). Vào thời điểm bắn lần thứ hai, viên đạn chính sẽ đi được quãng đường $x_0 = v_0t_0$ theo chiều ngang và $y_0 = gt_0^2/2$ theo chiều dọc. Trong trường hợp này, nó sẽ có tốc độ bằng $v_1 = \sqrt{v_x^2 + v_y^2} = \sqrt{v_0^2 + (gt_0)^2}$ và hướng một góc $\alpha = \arctg(gt_0/v_0)$ so với đường chân trời. Hãy tưởng tượng rằng viên đạn thứ hai được bắn với tốc độ $v_1$ một góc $\alpha$ so với phương ngang. Trong trường hợp của phát bắn thứ hai này, cả hai viên đạn sẽ di chuyển ở cùng một khoảng cách $s_0 = \sqrt{x_0^2 + y_0^2}$ với nhau.

Hãy kết nối hệ thống báo cáo 2 với đường đạn thứ hai nếu nó di chuyển như chúng ta giả định. Trong hệ thống này, viên đạn thứ hai sẽ kết thúc viên đạn chính nếu nó tiếp cận nó dọc theo đường thẳng nối các viên đạn với tốc độ tương đối $\vec{v}'$. Hãy tìm độ lớn và hướng của nó.

Rõ ràng là tốc độ hội tụ không thể có giá trị nhỏ tùy ý hoặc quá trình hội tụ phải được bắt đầu ít hơn thời gian bay

⟦folio 37⟧

---
running_head:
folio:
---

$t = \sqrt{2h/g}$. Vì thế,

$v' \geq \frac{s_0}{t} = s_0 \sqrt{\frac{g}{2h}}$.

Vectơ vận tốc tương đối $\vec{v}'$ phải tạo một góc $\alpha'$ với đường chân trời sao cho

$$tg \alpha' = \frac{y_0}{x_0} = \frac{gt_0}{2v_0}$$.

Bây giờ chúng ta hãy quay lại hệ thống dừng 1 một lần nữa. Ở đây, hình chiếu của tốc độ mong muốn $\vec{v}$ phải bằng nhau

$$v_x = v_0 + v' \cos \alpha', v_y = -gt - v' \sin \alpha'$$,

ở đâu $v' \geq s_0 \sqrt{g/(2h)}$. Giá trị tối thiểu của tốc độ $v' = s_0 \sqrt{g/(2h)}$, tại đó sự gặp nhau của các viên đạn sẽ xảy ra gần bề mặt trái đất, tương ứng với góc

$$\alpha_0 = \arctg(v_y/v_x) |_{t=t_0} = 0,019 \text{ рад} = 1^\circ 5'$$.

thiếu chế độ xem ngang. Trong trường hợp này, tốc độ mong muốn của viên đạn thứ hai bằng

$$v = \sqrt{v_x^2 + v_y^2} |_{t=t_0} = 535,1 \text{ м/c}$$.

V. Nikiforov

F1215. Trong một bình cách nhiệt có bên trong được làm nóng, 1 kcal và 1 kcal chất dễ cháy không trộn lẫn với nước. Đầu tiên, nhiệt độ trong bình bằng $-40^\circ\text{C}$, sau đó bật một bình đun nóng tiêu thụ điện năng không đổi. Sự phụ thuộc của nhiệt độ trong bình vào thời gian được thể hiện ở hình. Nhiệt dung riêng của nước đá $c_\pi = 2 \times$ Sự hiện diện của một “bình nguyên” (phần nằm ngang) trên đồ thị tương ứng với nhiệt độ $-20^\circ\text{C}$ cho thấy chính ở nhiệt độ này đã xảy ra sự tan chảy của chất chưa biết. (Rõ ràng, “cao nguyên” ở $0^\circ\text{C}$ tương ứng với quá trình băng tan.)

Như có thể thấy từ biểu đồ, phải mất $\tau_1 = 1$ phút $= 60$ s để làm nóng vật chứa trong bình từ nhiệt độ ban đầu $t_1 = -40^\circ\text{C}$ đến nhiệt độ $t_2 = -20^\circ\text{C}$, trong khi một lượng nhiệt bằng $P\tau_1$ thu được từ vật được nung nóng, trong đó $P$ là công suất của lò sưởi. Hãy viết phương trình cân bằng nhiệt của quá trình này:

$$(c_\pi + c)m(t_2 - t_1) = P\tau_1$$,

ở đâu $m = 1$ kg. Để làm tan chảy hoàn toàn chất
