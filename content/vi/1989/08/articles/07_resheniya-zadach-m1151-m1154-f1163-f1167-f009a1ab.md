---
id: 1989-8-resheniya-zadach-m1151-m1154-f1163-f1167-f009a1ab
issue: kvant_1989_8
year: 1989
number: "8"
title: Lời giải bài toán M1151—M1154; F1163—F1167
rubric: zadachnik-kvanta
rubric_sub: Задачник «Кванта»
page_first: 34
page_last: 41
page_labels: 32-39
tag: BJMW
lang: vi
source: kvant_digital
extraction: vision
content_sha256: e475bf085156c29df1d19c161dcb34732e4bdcafe1643a0052f432fa57b1b0f9
prompt_sha256: draft-1
translated_from: content/ru/1989/08/articles/07_resheniya-zadach-m1151-m1154-f1163-f1167-f009a1ab.md
source_content_sha256: 6298fd91411eb4fad0737cd964c73e1a30c4907c31b05719eee49163a58fbb55
translation_model: draft
translation_run: vi-draft-2026-10-31
translation_quality: draft
---

⟦folio 32⟧

đầu thanh - 100 ° C. Sau 1 phút, nhiệt độ giảm dần và đạt 200°C. Tính nhiệt lượng mà thanh tiêu thụ trong thời gian đó. Nhiệt dung riêng của sắt là 460 J/(kg K), khối lượng thanh là 15 g.

A. R. Zilberman

F1185. Một khối lập phương tích điện đều tạo ra một điện trường có cường độ $E_0$ ở đỉnh của nó. Một khối lập phương có kích thước bằng một nửa được loại bỏ khỏi khối lập phương (hình 2). Cường độ trường bây giờ sẽ là bao nhiêu tại điểm $A$?

Tôi. Yu. Poteryayko

F1186. Tại giá trị nào của điện dung của tụ điện $C_x$ trong mạch như hình hình 3, độ lệch pha giữa điện áp đặt vào và dòng điện trong mạch ngoài sẽ bằng 0 ở bất kỳ tần số nguồn nào? Độ tự cảm của cuộn dây là $L$, điện trở của mỗi điện trở là $R$. Tất cả các phần tử của mạch được coi là lý tưởng.

V. E. Skorovarov

F1187. Một chiếc xe trượt tuyết có chiều dài $L=2$ m và chiều cao $H=0,5$ m chuyển động theo đường thẳng với tốc độ $v=10$ m/s. Một chiếc lều có camera được lắp đặt cách đường $d=10$ m và chụp ảnh tại thời điểm hòa nhập tối đa.

Máy ảnh có một ống kính đơn có tiêu cự $F=5$ cm. Tốc độ cửa trập (tức là thời gian trong đó mỗi bộ phận của máy ảnh được chiếu sáng) được phản ánh trong máy ảnh này bằng cách sử dụng cửa trập khe, hoạt động như sau. Dọc theo khung phim, một khe dọc di chuyển với tốc độ không đổi $v_0=1$ m/s, chiều rộng của khe này có thể giảm cho đến khi đạt được tốc độ màn trập yêu cầu. Kích thước Kadar $24\times 36$ mm. Tỷ lệ chiều dài và chiều cao của hình ảnh chó khá sắc nét thu được trên phim là bao nhiêu?

M. G. Gavrilov

Lời giải bài toán
M1151 — M1154, F1163 — F1167

a) Đẳng thức này dễ dàng được chứng minh bằng quy nạp. Với $n=1$ thì đúng: $\frac{1\cdot 2!}{2} = \frac{3!}{2} - 2=1$. Giả sử rằng nó đã được chứng minh cho $n=k$, hãy kiểm tra xem nó có đúng với $n=k+1$ không:

$$\frac{1\cdot 2!}{2} + \frac{2\cdot 3!}{2^2} + \dots + \frac{k(k+1)!}{2^k} + \frac{(k+1)(k+2)!}{2^{k+1}} =$$

$$= \frac{(k+2)!}{2^k} + \frac{(k+1)(k+2)!}{2^{k+1}} - 2 =$$

$$= \frac{(k+3)!}{2^{k+1}} - 2.$$

b) Đáp số: $\frac{(n+3)!}{3^n}$ — c. Điều này có thể được chứng minh bằng

⟦folio 33⟧

Quy nạp giống như ở phần a), nhưng cách lập luận này có thể được trình bày hơi khác một chút. Lưu ý rằng mỗi số hạng của tổng có thể được viết dưới dạng hiệu

$$\frac{(k+3)!}{3^k} - \frac{(k+2)!}{3^{k-1}} = \frac{(k+2)!(k+3-3)}{3^k} = \frac{k(k+2)!}{3^k}.$$

Chúng ta hãy viết ra một số đẳng thức như vậy cho $k=1, 2, ..., n$ và cộng chúng theo từng số hạng; chúng tôi nhận được:

$$\frac{(n+3)!}{3^n} - 3! = \frac{1 \cdot 3!}{3} + \frac{2 \cdot 4!}{3^2} + \dots + \frac{n(n+2)!}{3^n}.$$

Tương tự, với mọi số tự nhiên $d$ từ đẳng thức

$$\frac{(k+d)!}{d^k} - \frac{(k+d-1)!}{d^{k-1}} = \frac{k(k+d)!}{d^k}$$

người ta có thể rút ra sự khái quát hóa các kết quả bài toán a) và 6):

$$\frac{1 \cdot d!}{d} + \frac{2 \cdot (d+1)!}{d^2} + \dots + \frac{n(n+d)!}{d^n} = \frac{(n+d)!}{d^n} - d!$$

N. V. Vasiliev, V. N. Zhokha

M1152. Gọi $h$ và $l$ là đường cao và đường cao vẽ từ đỉnh $A$ của tam giác $ABC$. Chúng ta hãy tiếp tục bissertis cho đến khi nó giao với đường tròn ngoại tiếp tại điểm $L$ (xem hình) và vẽ đường kính $LN$ của đường tròn này. Nó vuông góc với dây cung $BC$, vì $L$ là trung điểm của cung $BC$, nên $\angle ALN$ bằng góc $\varphi$ giữa $h$ và $l$. Kể từ đây,

$$h/l = \cos \varphi = AL/LN = (AI+IL)/2R \geq \sqrt{AI \cdot IL}/R,$$

trong đó $I$ là tâm của đường tròn nội tiếp tam giác $ABC$. Vẫn còn phải chứng minh rằng $AI \cdot IL = 2rR$.

Chúng ta hãy thả hình vuông góc $ID$ từ điểm $I$ sang một bên $AB$, sau đó $ID = r$ và $AI = r/\sin(\angle A/2)$. Đồng thời, $IL = LC$, vì trong tam giác $LIC$ mỗi góc của các đỉnh $I$ và $C$ bằng $(\angle A + \angle C)/2$ (góc đầu tiên là góc ngoài của tam giác $AIC$, và góc thứ hai bằng $\angle ICB + \angle BCL = \angle C/2 + \angle BAL)$. Nhưng $LC$ là dây cung của đường ngoại tiếp đường tròn chứa góc $LAC$ bằng $\angle A/2$, vì vậy $LC = 2R \sin(\angle A/2)$ Vì vậy,

$$AI \cdot IL = \frac{r}{\sin(\angle A/2)} 2R \sin(\angle A/2) = 2rR.$$

Từ lời giải rõ ràng là bất đẳng thức của chúng ta chuyển thành đẳng thức khi $AI = IL$, tức là khi đường thẳng $OI$ nối tâm của các đường tròn nội tiếp và ngoại tiếp vuông góc với bissertis $l$.

Trong số lời giải còn lại, chúng ta thấy lượng giác, sử dụng công thức $r = 4R \sin \frac{\angle A}{2} \sin \frac{\angle B}{2} \sin \frac{\angle C}{2}$ và đẳng thức $\varphi = \frac{|\angle B - \angle C|}{2}$. Chúng tôi sẽ để lại chi tiết về điều này lời giải cho độc giả.

C. Verceanu, V. N. Dubrovsky

⟦folio 34⟧

M1153. Số lượt đi lớn nhất có thể chứa một tuyến quân xe đi vòng quanh tất cả các ô của bàn cờ 8x8 một lần là bao nhiêu?

Hình 1.

Hình 2. Hình 3.

M1154. Chứng minh rằng nếu một tứ giác nội tiếp trong một đường tròn và được mô tả bằng chu vi của đường tròn thì đường thẳng đi qua tâm của các đường tròn này sẽ đi qua giao điểm các đường chéo của tứ giác.

Đáp số: 56 lượt. Một tuyến đường có 56 ngã rẽ được hiển thị trong hình 1. Hãy chứng minh rằng con số này không thể biểu diễn được.

Chúng ta hãy gọi một hình vuông trên bàn cờ là hành lang cho một tuyến đường nhất định nếu quân xe không rẽ vào đó. Lưu ý rằng từ mỗi cặp ô liền kề với các ô góc, ít nhất một ô là hành lang - nếu không, trong ô liền kề theo đường chéo với ô góc tương ứng, quân xe xuất hiện hai lần (hình 2).

Hãy cắt bảng thành 4 hình vuông 4x4. Mỗi người trong số họ có một hành lang cạnh phòng giam ở góc. Hãy chứng minh rằng ngoài nó còn có ít nhất một hành lang nữa. Khoảng cách bên phải là ô vuông phía dưới bên trái và giả sử ô a2 là một hành lang. Giả sử rằng không có hành lang nào khác trong quảng trường này. Khi đó hiển nhiên lộ trình tuần tự đi qua các ô b2, b1, a1, a2, a3, b3, b4 (hình 3). Ô tiếp theo sẽ là a4, nếu không chúng ta sẽ không bao giờ vào được ô đó (hoặc tuyến đường sẽ không bị đóng). Bây giờ bạn có thể tiếp tục lộ trình theo hướng khác: b2, c2, c1, d1, d2, e2. Từ kết quả hình, rõ ràng tuyến đường phải chứa phần d3_c3_c4, do đó, một trong các ô - d3 hoặc c4 - là một hành lang (điều này được chứng minh theo cách tương tự như đối với các ô góc - xem phần đầu của lời giải).

Vì vậy, số hành lang không nhỏ hơn 2×4=8 và số lượt rẽ không quá 64-8=56.

M. G. Khovanov

Chúng ta hãy đưa ra ký hiệu sau: ABCD là tứ giác cho trước; 2α, 2β, 2γ, 2δ—giá trị các góc của nó tại các đỉnh A, B, C, D; O và I, R và r là tâm của đường tròn ngoại tiếp và đường tròn nội tiếp và bán kính của chúng, P là giao điểm của các đường chéo (xem hình). Để xác định điều này, chúng ta sẽ giả sử rằng các góc 2α và 2β không tù, có nghĩa là 2γ=π-2α và 2δ=π-2β không nhọn. Hãy chứng minh rằng khi đó điểm O và I nằm bên trong góc APB và tỉ số khoảng cách từ các điểm này đến cạnh của góc này (đường chéo) là như nhau: ρ(O, BD)/ρ(O, AC) = ρ(I, BD)/ρ(I, AC) (chữ ρ biểu thị khoảng cách). Từ đây, tuyên bố bài toán rõ ràng sẽ theo sau.

Điểm O nằm cùng phía với BD với điểm A, (hoặc không phải ghế trên BD) vì góc BCD không nhọn. Điểm I cũng nằm trên cạnh này của BD vì góc ở đỉnh I của tứ giác BCDI bằng

$$2\pi - \beta - 2\gamma - \delta = \pi - (\beta + \delta) + \pi - 2\gamma = \frac{\pi}{2} + 2\alpha \leq \pi$$

(bạn dạy rằng β+δ=π/2).

Tương tự, chúng ta kiểm tra xem cả hai điểm - O và I - nằm cùng phía với điểm B so với AC. Do đó các điểm này nằm trong góc APB.

Hơn nữa, tỷ số khoảng cách từ O và I đến BD bằng tỷ số diện tích của các tam giácOBD và IBD

$$\frac{S_{OBD}}{S_{IBD}} = \frac{OB \cdot OD \sin \angle BOD}{IB \cdot ID \sin \angle BID}.$$

⟦folio 35⟧

Nhưng $OB=OD=R$, $\angle BOD=2\angle BAD=4\alpha$ (góc ở tâm gấp đôi góc nội tiếp tương ứng), $IB=r/\sin \beta$, $ID=r/\sin \delta=r/\cos \beta$ (xem dấu) và, như chúng tôi đã chỉ ra, $\angle BID=\pi/2+2\alpha$. Kể từ đây,

$$\frac{\rho(O, BD)}{\rho(I, BD)} = \frac{R^2 \sin 4\alpha \sin \beta \cos \beta}{r^2 \sin (\pi/2+2\alpha)} = \frac{R^2 \sin 2\alpha \cos 2\alpha \sin 2\beta}{r^2 \cos 2\alpha} = \frac{R^2}{r^2} \sin 2\alpha \sin 2\beta.$$

Từ tính đối xứng bài toán, rõ ràng tỷ lệ $\rho(O, AC)/\rho(I, AC)$ bằng cùng một giá trị, do đó $\rho(O, BD)/\rho(O, AC) = \rho(I, BD)/\rho(I, AC)$, đây là điều cần phải chứng minh.

Nói chung, một tứ giác “nội tiếp-nội tiếp” có một số tính chất màu đỏ. Hãy để chúng tôi trình bày một số trong số chúng có liên quan chặt chẽ đến nhiệm vụ này.

Cho $Q_1$ là một tứ giác có các đỉnh tại các điểm tiếp tuyến của tứ giác nội tiếp $ABCD$ với đường tròn nội tiếp, và $Q_2$ là một tứ giác giới hạn bởi các đường vuông góc với các đoạn $IA$, $IB$, $IC$, $ID$ ở hai đầu. Khi đó 1) các đường chéo $Q_1$ vuông góc và cắt nhau tại cùng một điểm $P$ là các đường chéo $ABCD$; 2) các hình tứ giác $Q_1$ và $Q_2$ đã được chuẩn bị và tâm của phần chuẩn bị nằm trên đường thẳng $PI$; 3) trên cùng một đường thẳng là tâm đường tròn ngoại tiếp của tứ giác $Q_2$ và trọng tâm của các tứ giác $Q_1$ và $Q_2$.

V. N. Dubrovsky

F1163. Do hệ số ma sát thấp, máy tự động không thể di chuyển trên băng với mô đun rễ vượt quá $a=0,5$ m/$c^2$. Theo điều kiện thực hiện, người lái xe cần di chuyển từ điểm $A$ đến điểm $B$ trong thời gian ngắn nhất, nằm trên đường thẳng vuông góc với hướng chuyển tốc độ tự động (hình 1). Thời gian tối thiểu có thể là bao nhiêu nếu khoảng cách là $AB=375$ m và tốc độ thấp nhất là $v = 10$ m/$c$? Máy tự động nên di chuyển theo quỹ đạo nào trong trường hợp này? Trả lời các câu hỏi tương tự cho trường hợp cá ở điểm $C$, $BC=200$ m.

Chúng ta hãy chuyển sang một hệ quy chiếu trong đó máy tự động tích lũy tại thời điểm ban đầu và điểm $B$ chuyển động với tốc độ không đổi $v$. Trong hệ quy chiếu này, máy tự động để gặp điểm $B$ nhanh nhất là rất dài và phải di chuyển dọc theo một đường thẳng nhất định với gốc không đổi bằng $a$. Hướng của đường thẳng được xác định bởi thực tế là tại một số điểm $D$ phải xảy ra va chạm. Đối với tam giác $ABD$ (hình 2), ký hiệu $AB=b$, ta có

$$b^2 + (vt)^2 = \left(\frac{at^2}{2}\right)^2.$$

Giải phương trình này, ta tìm được

$$t = \sqrt{\frac{2v^2}{a^2} + \sqrt{\left(\frac{2v^2}{a^2}\right)^2 + \frac{4b^2}{a^2}}} = 50 \text{ с.}$$

Do chuyển động tối ưu của máy tự động được tăng tốc đều nên quỹ đạo của nó trong hệ quy chiếu liên kết với trái đất sẽ là một hình parabol.

Chiến lược đến điểm gặp $C$ càng nhanh càng tốt cũng tương tự như chiến lược đã thảo luận ở trên. Tuy nhiên, để tìm thời gian cho đến khi gặp nhau tại điểm $E$ (hình 3), chúng ta sẽ phải giải phương trình tứ giác tổng quát

$$b^2 + (vt+c)^2 = \left(\frac{at^2}{2}\right)^2,$$

⟦folio 36⟧

ở đâu $c = BC$, hoặc

$$t = \sqrt[4]{\frac{4}{a^2} \left(b^2 + (vt + c)^2\right)}.$$

Phương trình này có thể được giải gần đúng bằng phương pháp tích phân, bản chất của phương pháp này như sau. Giả sử chúng ta cần giải một phương trình có dạng $f(t) = t$. Là một giá trị gần đúng, chúng tôi lấy một số giá trị $t = t_0$ và soạn chuỗi

$$t_1 = f(t_0), \ t_2 = f(t_1), \ ..., \ t_n = f(t_{n-1}).$$

Nếu dãy này có giới hạn $S$ và hàm $f(t)$ liên tục tại điểm $S$ thì $S$ là nghiệm của phương trình (*).

Trong trường hợp của chúng tôi, với điều kiện $t_0 = 0$, chuỗi sẽ trông như thế này

$$t_1 = f(t_0), \ t_2 = f(t_1), \ ...$$

$$..., \ t_n = \sqrt[4]{\frac{4}{a^2} \left(b^2 + (vt_{n-1} + c)^2\right)}.$$

Thay các giá trị bằng số vào ta được kết quả

$$t \approx 59,2 \text{ с.}$$

Hơn nữa, như một nghiên cứu chi tiết hơn về chuỗi cho thấy, ở mức $n = 4$ độ chính xác một phần trăm là đủ và cứ hai bước bổ sung (tính hai số hạng tiếp theo của chuỗi) sẽ cải thiện độ chính xác gấp 10 lần.

Đối với trường hợp vị trí tùy ý của điểm vật lý cho quảng cáo xen kẽ lời giải của phương trình (*), trong đó trước $c = BC$ có thể có dấu cộng hoặc dấu trừ, phải tuân thủ một số thận trọng nhất định do có thể có sự không đáng kể của lời giải và sự lựa chọn chính xác của phép lặp gần đúng thứ 0.

Và một lưu ý nữa. Tất nhiên, việc di chuyển dọc theo một parabol với vectơ gia tốc không đổi sẽ đòi hỏi người lái xe phải có tốc độ đáng kể.

A. N. Korotkov, E. N. Yunosov

F1164. Các kết cấu tích hợp sử dụng cái gọi là kết cấu bê tông cốt thép định hướng trước. Việc sản xuất một chùm tia như vậy được thực hiện như sau. Một thanh thép có chiều dài $l_1$ được kéo dài đến chiều dài $l_2$, sau đó được đổ đầy bê tông lỏng. Sau khi bê tông cứng lại, thanh được giải phóng khỏi lực căng

Đặt chiều dài dầm bê tông cốt thép sau khi tháo thiết bị kéo ra khỏi thanh thép bằng $l_0$ ($l_1 < l_0 < l_2$). Trong trường hợp này, thanh tăng theo giá trị $\Delta l_1 = l_0 - l_1$ và độ dốc của bê tông cứng theo giá trị $\Delta l_2 = l_2 - l_0$. Theo định luật Hooke, để thanh bị biến dạng như vậy cần có một lực

$$F_1 = E_1 S_1 \Delta l_1 / l_1,$$

trong đó $S_1$ là diện tích mặt cắt ngang của nó, $E_1$ là mô đun Young của thép. Tương tự như vậy, bê tông cần có lực để biến dạng.

$$F_2 = E_2 S_2 \Delta l_2 / l_2,$$

trong đó $S_2$ và $E_2$ là diện tích mặt cắt ngang và mô đun

⟦folio 37⟧

Những nỗ lực trong kỳ nghỉ. Tìm chiều dài của dầm bê tông cốt thép giáo dục và mô hình Young của nó. Diện tích mặt cắt ngang của thanh và dầm và mô hình thép và bê tông của Young được coi là đã biết. Bê tông cốt thép định hướng trước tốt hơn bê tông cốt thép thường như thế nào?

Khối bê tông non (không có thanh). Đương nhiên, khi không có ngoại lực thì lực lăn bê tông được cân bằng bởi lực căng của thanh:

$$F_1 = F_2.$$

Từ đây, sử dụng các biểu thức trước, ta tìm được chiều dài yêu cầu của dầm bê tông cốt thép

$$l_0 = \frac{E_2 S_2 + E_1 S_1}{E_1 S_1/l_1 + E_2 S_2/l_2}.$$

Để xác định mô hình Young $E_0$ của dầm bê tông cốt thép, chúng ta tính toán lực cần thiết để tạo khoảng cách với dầm theo giá trị $\Delta l_0$. Với biến dạng như vậy, thanh sẽ dài thêm $\Delta l_1 + \Delta l_0$ (so với chiều dài ban đầu $l_1$) và lực kéo sẽ bằng

$$F'_1 = E_1 S_1 (\Delta l_0 + \Delta l_1)/l_1.$$

Dầm bê tông sẽ có độ dốc $\Delta l_2 - \Delta l_0$ (so với chiều dài ban đầu $l_2$) và lực nghiêng của nó sẽ bằng

$$F'_2 = E_2 S_2 (\Delta l_2 - \Delta l_0)/l_2.$$

(Nếu $\Delta l_0 > \Delta l_2$ thì $F'_2$ sẽ là lực kéo chứ không phải lực lăn của bê tông.) Hợp lực cần thiết để kéo căng dầm bê tông cốt thép là

$$F_0 = F'_1 - F'_2 = E_1 S_1 (\Delta l_0 + \Delta l_1)/l_1 - E_2 S_2 (\Delta l_2 - \Delta l_0)/l_2,$$

hoặc, với đẳng thức $E_1 S_1 \Delta l_1/l_1 = E_2 S_2 \Delta l_2/l_2$, -

$$F_0 = E_1 S_1 \Delta l_0/l_1 + E_2 S_2 \Delta l_0/l_2.$$

Hãy lấy $\Delta l_0$ ra khỏi ngoặc, nhân và chia cho $S_2/l_0$ (đếm $S_1 \ll S_2$) và nhận được

$$F_0 = \left( (E_1 S_1/l_1 + E_2 S_2/l_2) \frac{l_0}{S_2} \right) S_2 \frac{\Delta l_0}{l_0}.$$

Dễ dàng nhận thấy biểu thức trong ngoặc ngoài là mô hình Young của dầm bê tông cốt thép $E_0$. Sử dụng công thức cho $l_0$, chúng tôi tìm thấy

$$E_0 = E_2 + \frac{S_1}{S_2} E_1.$$

Thật thú vị khi lưu ý rằng mô hình Young tương tự sẽ được tìm thấy cho dầm được chế tạo mà không cần căng trước thanh. Ưu điểm của bê tông cốt thép được dẫn hướng trước là nền bê tông trong các kết cấu như vậy chịu biến dạng dốc, ngay cả khi toàn bộ kết cấu chịu biến dạng kéo. Vì cường độ lăn của bê tông lớn hơn đáng kể so với cường độ kéo của nó nên khả năng hình thành vết nứt trên nền bê tông sẽ giảm đáng kể.

V. I. Klyachin

F1165. Từ một lưới dẫn điện vuông vô hạn có điện trở

Hãy bắt đầu với điểm $A$ và $B$. Hãy vẽ lại sơ đồ như trong hình 2. Nối hai nguồn điểm giống hệt nhau với các điểm $A$ và $B$ của sơ đồ (hình 3)

⟦folio 38⟧

Đối với mỗi cạnh r, một phần dây dẫn đã bị loại bỏ - như thể hiện trong hình 1. Tìm điện trở giữa các điểm A và B, B và C, A và C.

Hình 1.
Hình 2.
Hình 3.
Hình 4.
Hình 5.

F1166. Trong mạch hiển thị ở hình, các phím $K_1$ được đóng (với phím $K_2$ đóng) và tại thời điểm điện tích trên tụ điện $C_1$ trở nên tối đa, các phím $K_2$ được mở. Tìm giá trị lớn nhất của hai điện trở giống nhau có điện trở $R \gg r$ (chúng ta sẽ bỏ qua điện trở trong của các nguồn). Hãy đặt $r=1$ Ohm và chọn các giá trị của $E$ và $R$ sao cho $E/R=1$ A.

Trước tiên, chúng ta hãy xem xét việc chỉ kết nối một nguồn với điểm A và thu được mạch phân nhánh sau tới nút A điểm $I_1=\frac{E}{(R+r_x)} \approx 1$ A (ở đây $r_x$ là điện trở mong muốn giữa các điểm A và B) - hình 4. Sau đó, chỉ để lại nguồn có EMF $E_2$, chúng ta thu được tín hiệu khi dòng điện $I_2=\frac{E}{(R+r_x)} \approx 1$ A chạy từ nút B. Dòng điện này chạy từ ba nút gần B nhất và đi qua nguồn tới “vô cực” (hình 5).

Bây giờ chúng ta hãy nối cả hai nguồn với các điểm A và B. Sau đó, từ nguyên lý xếp chồng và từ điều kiện $R \gg r$, chúng ta thu được rằng dòng điện $I_{AB}=(I_1+I_2)/3=2/3$ A sẽ chạy qua dây dẫn $AB$ và điện áp trên dây dẫn sẽ bằng nhau

$$U_{AB}=\frac{2}{3}A \cdot 1\text{ Ом}=\frac{2}{3}\text{ В}.$$

Mặt khác, một điện áp tổng $2E$ được đặt vào mạch và dòng điện $I \approx 2E/(2R)=1$ A chạy vào mạch. Vì thế,

$$R_{AB}=\frac{U_{AB}}{I}=\frac{2}{3}\text{ Ом}.$$

Trường hợp đặt điện áp ngoài vào điểm A và C tương tự như trường hợp trước:

$$R_{AC}=\frac{2}{3}\text{ Ом}.$$

Chúng ta chỉ cần tìm điện trở giữa điểm B và C. Chỉ nối một nguồn với điểm B thì dòng điện $I_1/3$ sẽ chạy dọc theo cạnh $AB$ và dòng điện $I_1/6$ sẽ chạy dọc theo cạnh $BC$. Sau đó, kết nối với nút C nguồn thứ hai, có tính đến các thông điệp của phép đo sigmetry và nguyên tắc chồng chất, sẽ mang lại

$$U_{BC}=1\text{ Ом} \left( \frac{1}{3}A+\frac{1}{6}A \right)+1\text{ Ом} \left( \frac{1}{3}A+\frac{1}{6}A \right)=1\text{ В}$$

Và

$$R_{BC}=\frac{U_{BC}}{I}=1\text{ Ом}.$$

S. S. Krotov

Sau khi công tắc $K_1$ đóng, tụ điện $C_1$ được tích điện và điện tích của tụ điện $C_2$ vẫn bằng 0, vì $C_2$ bị đoản mạch.

Tại thời điểm điện tích $q_1$ của tụ điện $C_1$ đạt cực đại thì dòng điện trong mạch bằng không. Chúng ta hãy tìm độ lớn của điện tích $q_{1\text{max}}$, dựa trên thông điệp năng lượng: công của nguồn dòng điện bằng năng lượng điện trường của tụ điện $C_1$ -

⟦folio 39⟧

điện tích cuối cùng của tụ điện $C_2$. Các thông số của các phần tử mạch ghi trên hình được coi là đã cho.

$$q_{1 \max} U_0 = \frac{q_1^2 \max}{2 C_1},$$

Ở đâu

$$q_{1 \max} = 2 C_1 U_0.$$

Sau khi mở chìa khóa $K_2$, điện tích này sẽ bị “khóa” trên các bản tụ điện $C_1$ và $C_2$ bị chập mạch với nhau. Giả sử một thời gian sau khi mở tụ điện, một điện tích $q_2$ xuất hiện trên tụ điện $C_2$. Nếu chúng ta giả sử rằng điện tích của tụ $C_1$ tiếp tục tăng thì điện tích $q_1$ của nó sẽ liên hệ với điện tích $q_2$ bằng cách khớp

$$q_1 = q_{1 \max} + q_2.$$

Để tìm điện tích cực đại của tụ điện $C_2$, ta lại sử dụng định luật bảo toàn năng lượng: công của pin sau khi mở công tắc $K_2$ bằng độ tăng năng lượng của tụ điện -

$$q_{2 \max} U_0 = \frac{(q_{1 \max} + q_{2 \max})^2}{2 C_1} + \frac{q_2^2 \max}{2 C_2} - \frac{q_1^2 \max}{2 C_1},$$

Ở đâu

$$q_{2 \max} = - \frac{2 C_1 C_2 U_0}{C_1 + C_2}.$$

Dấu “—” có nghĩa là giả định của chúng ta về việc tăng điện tích $q_1$ là không đúng, điện tích trên tụ $C_1$ sẽ giảm. Trong trường hợp này, sẽ có dấu “—” ở mặt trên của tụ điện $C_2$ và dấu “+” ở mặt dưới.

V. V. Mozhaev

F1167. Một đoàn tàu dài, được dẫn động bởi quán tính, leo lên một ngọn đồi với góc $\alpha$. Khi bố cục được để lại hoàn toàn, một nửa chiều dài của bố cục nằm trên trang chiếu (xem hình). Hỏi từ lúc bắt đầu leo ​​dốc đến khi dừng lại mất bao lâu? Chiều dài tàu $L$, thời gian cư trú.

Gọi khối lượng của toàn bộ đoàn tàu là $M$, và chiều dài của phần đoàn tàu bị ép lên đồi là $x$. Khi đó khối lượng của phần này là $Mx/L$.

Hãy chọn trục tọa độ $X$ với gốc tọa độ ở chân trang chiếu và hướng nó lên trên trang chiếu. Chúng ta hãy viết định luật II Newton cho bố cục các hình chiếu lên trục đã chọn:

$$Ma = - \frac{Mx g \sin \alpha}{L},$$

hoặc, xét đến điều đó $a = x''$,

$$x'' = - \frac{g \sin \alpha}{L} x.$$

Phương trình này không gì khác hơn là phương trình dao động điều hòa có chu kỳ $T = 2\pi \sqrt{L/(g \sin \alpha)}$. Thời gian $t$ để tàu chuyển động trước khi dừng lại bằng 1/4 chu kỳ dao động, tức là.

$$t = \frac{T}{4} = \frac{\pi}{2} \sqrt{\frac{L}{g \sin \alpha}}.$$

A. I. Buzdin
