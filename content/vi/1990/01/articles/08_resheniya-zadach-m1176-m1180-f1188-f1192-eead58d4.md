---
id: 1990-1-resheniya-zadach-m1176-m1180-f1188-f1192-eead58d4
issue: kvant_1990_1
year: 1990
number: "1"
title: Lời giải bài toán M1176—M1180; F1188—F1192
rubric: zadachnik-kvanta
rubric_sub: Задачник «Кванта»
page_first: 42
page_last: 48
page_labels: 40, 42, 43, 44, 45, 46
lang: vi
source: kvant_digital
extraction: vision
content_sha256: 639e6688234d715872d6e41185ec97920dca3ca95955732ffe5a147cf496530e
prompt_sha256: draft-1
translated_from: content/ru/1990/01/articles/08_resheniya-zadach-m1176-m1180-f1188-f1192-eead58d4.md
source_content_sha256: f73d934cc7b8e981eb03629c6f98285b1758bc52673ebcc46fe0ad588e75d76a
translation_model: draft
translation_run: vi-draft-gaps-2026-11-01
translation_quality: draft
---

⟦folio 40⟧

Hình 2.

Lời giải bài toán
M1176 — M1180, F1188 — F1192

Chúng ta hãy biểu thị bằng $PQ$ và $EF$ đường trung bình của tứ giác $ABCD$, như trong hình 1; thì diện tích của nó $S$ gấp đôi diện tích $PEQF$ (tổng diện tích của các hình tam giác màu xanh là $S/2: S_{PAE} + S_{QCE} = S_{BAD}/4 + S_{BCD}/4 = S/4 = S_{PBF} + S_{QDE}$).

Như vậy,

$$S = 2S_{PEQF} = PQ \cdot EF \cdot \sin \alpha,$$

(1)

trong đó $\alpha$ là góc giữa đường thẳng $PQ$ và $EF$.
Ở phía bên kia,

$$\frac{1}{4} (MN^2 - KL^2) = \frac{1}{4} (MN + KL) \cdot (MN - KL) = PQ \cdot \bar{v},$$

(2)

ở đâu $\bar{v} = (MK + LN)/2$, máy bay $MN + KL = (MP + PQ + QN) + (KP + PQ + QL) = 2PQ,$

(3)
$(KP = -MP, QL = -QN)$,

MỘT
$$MN - KL = (MK + KN) - (KN + NL) = MK + LN.$$

Hãy chứng minh rằng vế phải của công thức (1) và (2) bằng nhau. Các vectơ $MK$ và $LN$ lần lượt được lấy từ $AB$ và $DC$ bằng cách xoay $\pi/2$ theo cùng một hướng (bằng hình 2 - ngược chiều kim đồng hồ). Do đó, chúng ta thu được chúng $\bar{v}$ bằng cùng một phép quay từ $(AB + DC)/2$. Nhưng chúng ta thu được các vectơ nối các đầu của hai đoạn bằng vectơ nối các điểm giữa của các đoạn này - chúng ta đã chứng minh điều này cho các đoạn $MK$ và $NL$ (xem (3)), tức là $(AB + DC)/2 = EF$. Vậy vectơ $\bar{v}$ bằng vectơ $EF$ quay bởi $\pi/2$. Do đó, góc giữa các vectơ $PQ$ và $\bar{v}$ bằng $\pi/2 \pm \alpha$ (hãy nhớ rằng $\alpha$ là góc giữa các đường thẳng $PQ$ và $EF$). Nhưng theo điều kiện, góc $KPQ$, tức là góc giữa vectơ $PQ$ và $MK$, và góc $PQL$ - giữa $PQ$ và $LN$ - là nhọn, do đó $PQ \cdot \bar{v} = (PQ \cdot MK + PQ \cdot LN)/2 > 0$, nghĩa là góc giữa $PQ$ và $\bar{v}$ là cấp tính và bằng $\pi/2 - \alpha$. Bây giờ chúng tôi nhận được $PQ \cdot \bar{v} = PQ \cdot |\bar{v}_1| \cdot \cos(\pi/2 - \alpha) = PQ \times EF \cdot \sin \alpha = S$ đó, đó là những gì được yêu cầu.

Đồng thời, chúng tôi đề xuất chứng minh rằng tổng $(MN^2 + KL^2)$ bằng tổng bình phương các đường chéo $AC^2 + BD^2$ của một tứ giác đã cho hoặc gấp đôi tổng bình phương của các đường trung tuyến $2(PQ^2 + EF^2)$.

N. Vasiliev, V. Dubrovsky

Chúng ta hãy sử dụng bất đẳng thức Bernulia nổi tiếng - $(1 + x)^\alpha \geq 1 + \alpha x$ cho $\alpha > 1$, $x > -1$.

(Để chứng minh điều đó, chỉ cần lưu ý rằng hàm số

⟦folio 42⟧

---
running_head:
folio:
---

Theo đó, để đạt được sự bình đẳng thì cần và đủ $\cos(\alpha - \beta) = 1$, tức là $\alpha = \beta$, và $\cos \gamma = 0$, tức là $\gamma = 90^\circ$, hoặc $\cos \alpha = \cos \beta = 1/2$, tức là $\alpha = \beta = 60^\circ$.

E. Gotman

M1179. Tìm $a_{1000}$ nếu $a_1 = 0$ và cho $n = 1, 2, 3, \dots$

a) $a_{n+1} = \frac{n}{n+1}(a_n+1)$;

b) $a_{n+1} = \frac{n(n+1)}{(n+2)(n+3)} \times (a_n+1)$;

c) $a_{n+1} = \frac{n(n+1)(n+2)}{(n+3)(n+4)(n+5)} \times (a_n+1)$.

Đáp số: a) 999/2, b) 999· 2001/10010, c) 16650/167.

Chúng ta hãy chứng minh bằng quy nạp rằng các số hạng chung của dãy đang xét được biểu diễn thông qua số $n$ bằng các công thức sau:

a) $a_n = \frac{n-1}{2}$; b) $a_n = \frac{(n-1)(2n+1)}{10(n+1)}$; c) $a_n = \frac{n(n-1)}{10(n+2)}$.

Đối với $n = 1$ tất cả các công thức đều cho $a_n = 0$. Chúng ta hãy kiểm tra xem chúng có đúng với $a_{n+1}$ hay không, coi chúng đúng với $a_n$.

Trường hợp a): $a_{n+1} = \frac{n}{n+1}\left(\frac{n-1}{2} + 1\right) = \frac{n}{2} = \frac{(n+1)-1}{2}$.

Trường hợp b): $a_{n+1} = \frac{n(n+1)}{(n+2)(n+3)} \times \frac{2n^2 - n-1+10n+10}{10(n+1)} = \frac{n \cdot (n+3)(2n+3)}{10(n+2)(n+3)} = \frac{n(2n+3)}{10(n+2)}$.

Trường hợp c): $a_{n+1} = \frac{n(n+1)(n+2)}{(n+3)(n+4)(n+5)} \times \frac{n^2+9n+20}{10(n+2)} = \frac{n(n+1)}{10(n+3)}$.

Vẫn còn phải thay thế $n = 1000$ vào công thức cho $a_n$.

V.Vergheim

M1180*. Trên một trong hai điểm dữ liệu $A$ và $B$ giao nhau với hình cầu, mặt khác - $C$ và $D$. Đoạn AC đi qua điểm chung của hình cầu. Đoạn BD đi qua một điểm chung khác của hình cầu và song song với đường thẳng chứa tâm của hình cầu. Chứng minh rằng hình chiếu của các đoạn $AB$ và $CD$ lên đường thẳng AC bằng nhau.

Đặt $E$ và $F$ lần lượt là các điểm chung của hình cầu nằm trên $AC$ và $BD$, $O_1$ và $O_2$ tâm của hình cầu, $G$ một điểm đối xứng với $F$ đối với đường thẳng $O_1O_2$. Rõ ràng, $G$ cũng là điểm chung của hình cầu, còn $BG$ và $DG$ là đường kính của hình cầu (hình 1).

Chúng ta sẽ biểu thị bằng $X'$ hình chiếu của một điểm tùy ý $X$ lên $AC$. Khi đó rõ ràng $O'_1$ là trung điểm của dây cung $AE$ của hình cầu $O_1$, và $O'_2$ là trung điểm của dây cung $EC$ của hình cầu $O_2$. Đồng thời, $O'_1$ là trung điểm của đoạn $B'G'$, vì $O_1$ là trung điểm của $BG$ và $O'_2$ là trung điểm của đoạn $G'D'$. Từ-

⟦folio 43⟧

---
running_head:
folio:
---

Ở đây (xem hình 2) nó dẫn đến $AB' = G'E$ và $G'E = D'C$, tức là $AB' = D'C$.

I. Sharytsin

F1188. Giữa đầu song ngữ và thành gai có một cặp bánh xe (xem hình) - hai đĩa nặng nặng $M$, được gắn cố định trên một trục nhẹ có đường kính $L$ ($L \approx R_2 - R_1$). Bằng cách tác dụng một lực theo phương ngang lên trục, chúng ta buộc bộ bánh xe chuyển động theo vòng tròn mà không bị biến dạng (sao cho trục luôn hướng dọc theo bán kính). Khối lượng công việc tối thiểu cần phải được thực hiện để di chuyển trọng lượng xung quanh là bao nhiêu? Hệ số ma sát của bánh xe với mặt đất $k$; Các bánh xe được coi là hẹp.

Rõ ràng là trong một tình huống nhất định không thể đảm bảo rằng cả hai bánh xe đều chuyển động không bị trượt. Do đó, công cần tìm bằng công của các lực ma sát, lấy dấu trừ.

Khi bánh xe chuyển động chậm thì lực ma sát tác dụng lên mỗi bánh xe bằng $-F_{\text{тр}} |v_H| = -kMg |v - \omega r|$, trong đó $v_H$ là tốc độ của điểm dưới cùng của bánh xe so với mặt đất, $r$ là bán kính bánh xe, $v$ là tốc độ tâm bánh xe, $\omega$ là tốc độ góc quay của bánh xe quanh trục của nó. Lực ma sát tác dụng lên cả hai bánh xe bằng $-kMg(|v_1 - \omega r| + |v_2 - \omega r|)$, trong đó $v_1$ và $v_2$ là tốc độ tâm của bánh thứ nhất và bánh thứ hai. Đối với $v_1$ và $v_2$ cố định, các giá trị trong ngoặc tối thiểu là $v_1 \leq \omega r \leq v_2$, tương ứng với trường hợp bánh xe trượt ngược chiều nhau. Trong trường hợp này, tổng công suất của lực ma sát là

$$P_{\text{тр}} = -kMg(v_2 - v_1),$$

và công của lực ma sát khi đi hết một vòng tròn là

$$A_{\text{тр}} = -kMg \cdot 2\pi(R_2 - R_1).$$

Do đó công việc bạn đang tìm kiếm -

$$A = -A_{\text{тр}} = kMg \cdot 2\pi(R_2 - R_1) = 2\pi kMgL.$$

M. Tsypin

F1189. Căn phòng lớn được giữ ở nhiệt độ không đổi $T_k = +15^\circ\text{C}$ vào mùa đông bằng ba bộ tản nhiệt sưởi ấm trung tâm nối tiếp, qua đó nước nóng được bơm. Trong trường hợp này, nhiệt độ của bộ tản nhiệt đầu tiên là $T_1 = +75^\circ\text{C}$ và nhiệt độ cuối cùng (thứ ba) là $T_3 = +30^\circ\text{C}$. Nhiệt độ của bộ tản nhiệt thứ hai là bao nhiêu? Giả sử nhiệt lượng nằm giữa bộ tản nhiệt và căn phòng, vì vậy hãy chỉ định nhiệt độ của nước ở đầu vào và đầu ra của bộ tản nhiệt như trong hình. Nhiệt độ của nước ở đầu vào của mỗi bộ tản nhiệt xác định duy nhất nhiệt độ của chính bộ tản nhiệt và nhiệt độ của nước ở đầu ra của nó. Điều kiện cân bằng là sự bằng nhau của dòng nhiệt “nước - bộ tản nhiệt” và “bộ tản nhiệt - phòng”.

Chúng tôi sẽ đếm tất cả nhiệt độ từ nhiệt độ phòng, tức là từ $T_k$. Giả sử rằng chúng ta đã thay đổi tất cả nhiệt độ theo một hệ số. Khi đó cả hai dòng nhiệt của mỗi bộ tản nhiệt đều thay đổi một lượng như nhau và trạng thái cân bằng sẽ không bị xáo trộn. Điều này có nghĩa là cả ba bộ tản nhiệt đều có cùng tỷ lệ giữa nhiệt độ đầu vào và nhiệt độ của bộ tản nhiệt:

$$\frac{t_1 - T_k}{T_1 - T_k} = \frac{t_2 - T_k}{T_2 - T_k} = \frac{t_3 - T_k}{T_3 - T_k},$$

⟦folio 44⟧

---
running_head:
folio:
---

và giữa nước nóng và bộ tản nhiệt - tỷ lệ thuận với chênh lệch nhiệt độ tương ứng.

F1190. Nối hai tụ điện giống hệt nhau nối tiếp với một cục pin có điện trở trong $r=1$ Ohm. Một điện trở có điện trở $R=1000$ Ohm được mắc song song với một trong số chúng và một lượng nhiệt nhất định được giải phóng trong mạch. Bao nhiêu nhiệt lượng này được tạo ra ở điện trở trong của pin?

Vì vậy, thông qua điện trở $R$, nó là tổng dòng điện phóng của tụ “dưới” và dòng điện nạp của tụ “trên” (xem hình). Điều này có nghĩa là dòng điện chạy qua điện trở $r$ tại bất kỳ thời điểm nào đều nhỏ hơn dòng điện chạy qua điện trở $R$. Điện áp cực đại trên điện trở lớn không vượt quá điện áp của pin $U$ và điện áp trên điện trở nhỏ phụ thuộc nhỏ hơn 0,001 $U$ nên chúng ta sẽ bỏ qua và giả sử rằng tổng điện áp trên tụ điện chính xác bằng điện áp của pin $U$.

Khi đó lời giải bài toán trở nên hoàn toàn đơn giản: khi nối một điện trở bên ngoài, điện áp thay đổi trên các tụ điện có giá trị tuyệt đối giống nhau, chỉ đối với tụ điện “thấp hơn” thì sự thay đổi này là âm và đối với tụ điện “trên” thì nó là dương. Các tụ điện có cùng điện dung (chúng tôi để bạn tự tìm ra trường hợp có điện dung khác nhau), do đó, sự thay đổi điện tích của tụ điện cũng giống nhau về giá trị tuyệt đối. Điều này có nghĩa là tại bất kỳ thời điểm nào, dòng điện qua điện trở $R$ chính xác gấp đôi dòng điện qua điện trở $r$ và tỷ số giữa công suất nhiệt tương ứng là 4000:1.

Vì vậy, khoảng 1/4000 tổng lượng nhiệt sẽ được giải phóng ở điện trở trong của pin (ở điện trở $r$).

F1191. Một quả cầu dẫn điện có thành mỏng có bán kính $R$ được nối với nguồn bằng dây mỏng (hình 1), nối tại các điểm $A$ và $B$ (AO $\perp$ОВ, О là tâm của quả cầu). Vậy qua nguồn nó bằng $I_0$. Họ đang di chuyển theo hướng nào?

Đầu tiên, hãy xem xét một kết nối rất đơn giản của quả cầu với nguồn - cực (hình 2). Rõ ràng là giá trị tương đương giữa các điểm nằm cách nhau một khoảng nhỏ $\Delta l$ sẽ chính xác là giá trị hiện tại

$$i = \frac{I_0}{2\pi R} \Delta l.$$

Bây giờ, hãy kết nối hai nguồn (hình 3) với hình cầu - một nguồn giữa các cực và nguồn kia giữa các cực đối diện.

⟦folio 45⟧

---
running_head:
folio:
---

Các điện tích tại điểm C(OS ⊥ OA, OC ⊥ OB) là bao nhiêu? Chúng ta hãy tạo hai điểm trên quả cầu gần điểm C, sao cho khoảng cách giữa chúng là R/1000, và đoạn nối chúng vuông góc với hướng của các điện tích. Phần nào của tổng dòng điện chạy qua quả cầu giữa các điểm này?

Các điểm tích cực của đường xích đạo. Khi đó dòng điện tại điểm C sẽ bằng tổng hình học của hai dòng điện vuông góc với nhau. Nhưng dòng điện này lớn gấp đôi so với dòng điện mong muốn.

Cuối cùng, chúng ta thu được rằng có một dòng điện chạy giữa các điểm đã cho trên quả cầu

$$I = \frac{1}{2} \sqrt{2} \frac{I_0}{2\pi R} \frac{R}{1000} = \frac{\sqrt{2}}{4000\pi} I_0 \sim 0,0001I_0$$

theo hướng hợp với đường xích đạo một góc 45°.

L. Markovich

F1192. Ở cuối cuộn dây điện từ hình trụ có một tấm bìa cứng mỏng, trên đó có một vòng siêu dẫn nhỏ làm bằng dây mỏng, đường kính $d_1$ nhỏ hơn đáng kể so với đường kính của vòng D. Khi nút điện từ được nối nối tiếp với nguồn với tụ điện (xem hình), vòng này bị đứt ở $U > U_0$. Hướng của nguồn trong một thí nghiệm tương tự với một vòng có cùng đường kính, nhưng được làm bằng dây dày $d_2$? Độ tự cảm của vòng dây như vậy, đủ để thực hành, có thể được ước tính chính xác bằng công thức $L = kD \ln(1,4D/d)$. Điện trở điện từ nên được coi là thấp.

Bỏ qua điện trở thuần của cuộn dây, ta viết định luật Ohm cho mạch điện kín:

$$U - L_c \frac{\Delta I_c}{\Delta t} = \frac{q}{C},$$

trong đó $L_c$ là độ tự cảm của nút điện từ, $I_c$ là dòng điện chạy qua nút điện từ, $q$ là điện tích trên tụ điện. Sử dụng biểu thức $I_c = \Delta q/\Delta t$, chúng ta thu được phương trình

$$\frac{d^2 q}{dt^2} + \frac{q}{L_c C} = \frac{U}{L_c}.$$

Chúng ta hãy giới thiệu các ký hiệu sau: $1/(L_c C) = \omega_0^2$, $q - UC = q^*$. Khi đó phương trình mô tả sự phụ thuộc của điện tích $q^*$ vào thời gian sẽ có dạng

$$\frac{d^2 q^*}{dt^2} + \omega_0^2 q^* = 0.$$

Phương trình này mô tả dao động điều hòa của điện tích $q^*$, với giá trị UC không đổi, bằng điện tích trên tụ điện. Chúng ta tìm Lời giải của phương trình này ở dạng

$$q^*(t) = A \sin \omega_0 t + B \cos \omega_0 t,$$

trong đó A và B là các hằng số được xác định từ các điều kiện ban đầu. Tại thời điểm đóng vòng mạch điện từ

$$q^*(0) = q(0) - UC = -UC,$$

$$\frac{\Delta q^*}{\Delta t} = \frac{\Delta q}{\Delta t} = 0,$$

⟦folio 46⟧

---
running_head:
folio:
---

nó đến từ đâu?
$$A = 0, B = -UC.$$
Kể từ đây,
$$q^*(t) = -UC \cos \omega_0 t, \quad q(t) = UC(1 - \cos \omega_0 t).$$
Trong tương lai chúng ta sẽ quan tâm đến dòng điện từ:
$$I_c(t) = \frac{\Delta q(t)}{\Delta t} = UC \omega_0 \sin \omega_0 t.$$
Bây giờ chúng ta viết định luật Ohm cho bóng đèn siêu dẫn:
$$-\frac{\Delta \Phi}{\Delta t} - L_k \frac{\Delta I_k}{\Delta t} = 0,$$
trong đó $\Phi$ là từ thông ngoài của vectơ cảm ứng từ, một bóng đèn tùy ý, $I_k$ là dòng điện trong bóng đèn, và $L_k$ là độ tự cảm của bóng đèn. Lời giải của phương trình này có dạng
$$\Phi + L_k I_k = \text{const},$$
nhưng tại thời điểm ban đầu hằng số này bằng 0, do đó
$$I_k = -\frac{\Phi}{L_k}.$$
Thông lượng $\Phi$ tỷ lệ thuận với cảm ứng của solenide, do đó, tỷ lệ thuận với $I_c$ và diện tích của bóng đèn:
$$\Phi \sim I_c D^2 \sim UD^2.$$
Tính đến mối quan hệ này, chúng ta có được
$$I_k \sim \frac{D^2 U}{L_k}.$$
Lực Ampe cực đại $F$ tác dụng theo phương thẳng đứng lên bóng đèn, tỷ lệ thuận với chiều dài của bóng đèn, cường độ dòng điện trong bóng đèn và dòng điện trong Solenua:
$$F \sim DI_k I_c \sim \frac{D^3 U^2}{L_k}.$$
Chiếc nhẫn sẽ nảy lên nếu lực $F$ lớn hơn lực hấp dẫn của bình, tỉ lệ với $Dd^2$. Trong trường hợp giới hạn
$$\frac{D^3 U^2}{L_k} \sim Dd^2 \rightarrow U \sim \frac{L_k^{1/2} d}{D}.$$
Đối với trường hợp đầu tiên
$$U_0 \sim (\ln(1,4D/d_1))^{1/2} d_1,$$
lần thứ hai -
$$U'_0 \sim (\ln(1,4D/d_2))^{1/2} d_2.$$
Kể từ đây,
$$U'_0 = U_0 \left( \frac{\ln(1,4D/d_2)}{\ln(1,4D/d_1)} \right)^{1/2} \frac{d_2}{d_1}.$$
Điện áp tại nguồn phải lớn hơn $U'_0$.
V. Mozhaev
