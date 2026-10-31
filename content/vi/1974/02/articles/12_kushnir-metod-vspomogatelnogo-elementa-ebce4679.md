---
id: 1974-2-kushnir-metod-vspomogatelnogo-elementa-ebce4679
issue: kvant_1974_2
year: 1974
number: "2"
title: Phương thức trợ giúp
authors:
  - Кушнир И. А.
rubric: praktikum-abiturienta
rubric_sub: Практикум абитуриента
page_first: 48
page_last: 53
page_labels: 46, 47, 48, 50, 51
tag: P3SM
lang: vi
source: kvant_digital
extraction: vision
content_sha256: 0749d67af133725de1bdb1955ce393899189bc24a077c516192328cc894c0e28
prompt_sha256: draft-1
translated_from: content/ru/1974/02/articles/12_kushnir-metod-vspomogatelnogo-elementa-ebce4679.md
source_content_sha256: 9fff92e5fedd3328d7e0f386d1f0728df2af4390465ac9fa251445d3795ab47e
translation_model: draft
translation_run: vi-draft-2026-10-31
translation_quality: draft
---

⟦folio 46⟧

Phương pháp
phụ trợ
yếu tố
I. A. Kushinr

Lời giải của nhóm lớn bài toán trong hình học có thể thực hiện được bằng cách đưa vào các phần tử bổ sung không được chỉ định trực tiếp trong các điều kiện bài toán. Những yếu tố này có thể là độ dài, diện tích, khối lượng, góc. Với sự giúp đỡ của họ, một phương trình được lập ra trong đó phần tử chưa biết là phần tử mong muốn hoặc phần tử mà với sự trợ giúp của phần tử mong muốn có thể dễ dàng tìm thấy. Đôi khi với sự trợ giúp của phần tử này, nó không phải là một phương trình được hình thành mà là một sự tương ứng theo yêu cầu của điều kiện bài toán.

Phần tử tuyến tính phụ trợ
Trong các bài toán phẳng, sẽ thuận tiện hơn khi đưa ra phần tử tuyến tính hoặc tỷ số của các phần tử tuyến tính nếu các hình đang xét là tương tự nhau. Sau đó, bằng cách sử dụng các tỷ lệ hoặc các cấu trúc hình học phụ trợ, một phương trình được rút ra trong đó phần tử được đưa vào với tư cách là thành viên của phương trình được rút gọn và không khó để tìm ra phần tử cần thiết.

Hãy xem xét lời giải bài toán, được đề xuất tại Đại học Bang Novosibirsk.

Bài toán 1 (NSU, 1969). Qua một điểm nhất định bên trong tam giác vẽ được ba đường thẳng tương ứng song song với các cạnh của tam giác. Những đường này chia tam giác thành sáu phần, ba trong số đó là các tam giác có diện tích $S_1, S_2, S_3$. Tìm diện tích của tam giác này.

Bắt đầu với lời giải, chúng ta thay thế sự giống nhau của các tam giác bằng diện tích $S_1, S_2, S_3$ (Hình 1) và tam giác ABC bằng diện tích S. Ngoài ra, tổng độ dài các cạnh DQ, QE và FK của các tam giác nhỏ bằng độ dài cạnh BC của tam giác ABC. Sử dụng các cạnh này làm phần tử phụ, ta thu được phương trình

$$\frac{\sqrt{S_1}}{\sqrt{S}} = \frac{DQ}{BC}, \frac{\sqrt{S_2}}{\sqrt{S}} = \frac{QE}{BC}, \frac{\sqrt{S_3}}{\sqrt{S}} = \frac{FK}{BC}.$$

Hãy thêm chúng lên:

$$\frac{\sqrt{S_1} + \sqrt{S_2} + \sqrt{S_3}}{\sqrt{S}} = \frac{DQ + QE + FK}{BC} = 1.$$

Vì vậy, $S = \left( \sqrt{S_1} + \sqrt{S_2} + \sqrt{S_3} \right)^2$.

Nên nhập đoạn phụ nếu các phần tử tuyến tính không được cho trong điều kiện bài toán và bạn cần tìm mối quan hệ giữa các góc.

⟦folio 47⟧

Nhiệm vụ 2 (MSU, khoa vật lý, 1967).
Tìm cosin của góc ở đáy của một tam giác đều, biết rằng giao điểm của các đường cao của nó nằm trên đường tròn nội tiếp của tam giác.

Theo điều kiện, trực tâm $H$ của tam giác $ABC$ ($AB = AC$) phải nằm trong tam giác, do đó $\angle A < 90^\circ$ (Hình 2). Hãy để chúng tôi giới thiệu phần tử phụ $a$—độ dài của đoạn $BD$, ký hiệu $\angle ABC$ là $x$ và tâm của đường tròn nội tiếp là $O$. Sau đó

$$\angle HCD = \frac{\pi}{2} - x, HD = a \mathrm{tg} \left( \frac{\pi}{2} - x \right) = a \mathrm{ctg} x = 2OD, OD = a \mathrm{tg} \frac{x}{2},$$

Ở đâu

$$\mathrm{ctg} x = 2 \mathrm{tg} \frac{x}{2}, \mathrm{tg}^2 \frac{x}{2} = \frac{1}{5},$$

$$\cos x = \frac{2}{3}.$$

Việc giới thiệu phần tử phụ trợ để tìm mối quan hệ của các đại lượng hình học khác nhau là đặc biệt quan trọng.

Nhiệm vụ 3 (MAN, 1968). Đáy lớn của một paramid tứ giác cắt đều tạo thành một góc $\alpha$ với biên bên của nó và một góc $\beta$ với mặt phẳng đi qua các cạnh liền kề của đáy trên và đáy dưới. Tìm tỉ số diện tích của các đáy.

Chúng ta hãy giới thiệu một phần tử phụ $a$—chiều dài cạnh của đế lớn của paramid (Hình 3). Diện tích của căn cứ này sẽ là $a^2$. Độ dài cạnh của đế trên có thể được biểu thị bằng $a$, $\alpha$ và $\beta$. Chúng ta hãy xem xét hình thang phụ $EE_1F_1F$, thu được trong tiết diện của paramid bằng một mặt phẳng vuông góc với đáy và đi qua trung điểm của các cạnh $AB$ và $CD$. Hãy để chúng tôi giới thiệu thêm các phân đoạn phụ trợ $E_1H = h, E_1F_1 = x$. Sau đó

$$HF = \frac{1}{2} (a + x),$$

$$EH = \frac{1}{2} (a - x), h = HF \mathrm{tg} \beta =$$

Cơm. 2.

$$= \frac{1}{2} (a + x) \mathrm{tg} \beta = EH \mathrm{tg} \alpha =$$

$$= \frac{1}{2} (a - x) \mathrm{tg} \alpha.$$

Chúng ta thu được phương trình $(a + x) \mathrm{tg} \beta = (a - x) \mathrm{tg} \alpha$, từ đó

$$x = \frac{a \sin (\alpha - \beta)}{\sin (\alpha + \beta)},$$

$$\frac{s}{S} = \frac{x^2}{a^2} = \frac{\sin^2 (\alpha - \beta)}{\sin^2 (\alpha + \beta)}.$$

Yếu tố phụ trợ - diện tích hoặc thể tích

Việc giới thiệu diện tích và thể tích như một phần tử phụ cũng tương tự như việc giới thiệu phần tử tuyến tính. Bằng cách so sánh diện tích và thể tích của các phần riêng lẻ của hình, người ta có thể thu được phương trình của các ẩn số tương đối bài toán hoặc sự tương ứng cần thiết. Tốt hơn là tìm những diện tích và thể tích đó, tổng (chênh lệch) của chúng sẽ cho diện tích của một hình nhất định, cũng như tỷ lệ diện tích

⟦folio 48⟧

những hình có các phần tử tuyến tính là những phần tử bắt buộc hoặc là các thành phần của sự tương ứng cần thiết.

Bài toán 4 (MSU, Cơ học và Toán học, 1960). Một đường thẳng song song với đáy được vẽ thông qua chuỗi tam giác đều. Một điểm M tùy ý được lấy trên đường thẳng này của tam giác trong. Chứng minh rằng khoảng cách từ điểm M đến đáy tam giác là trung bình số học của khoảng cách từ điểm M đến các cạnh của tam giác.

Gọi $h_1, h_2, h_3$ lần lượt là khoảng cách từ điểm M đến các cạnh của tam giác BC, AB, AC (Hình 4). Rõ ràng là $S_{\triangle AMB} + S_{\triangle CMB} + S_{\triangle AMC} = S_{\triangle ABC}$, hoặc $ah_1 + ah_2 + ah_3 = ah$, trong đó $a$ là cạnh của tam giác ABC, $h$ là đường cao của tam giác ABC. Vì vậy, $h = h_1 + h_2 + h_3$, nhưng $h_1 = \frac{h}{3}$, vì vậy $h_2 + h_3 = h - h_1 = \frac{2}{3}h = 2h_1$, $h_1 = \frac{h_2 + h_3}{2}$.

Bài toán 5. Cho tứ giác ABCD ngoại tiếp một đường tròn. Chứng minh rằng bình phương các khoảng cách từ chuỗi đường tròn đến các đỉnh đối diện liên hệ với nhau bằng tích của các cạnh, hội tụ tại các đỉnh emix.

Kí hiệu như hình 5. Cần chứng minh $\frac{x^2}{y^2} = \frac{ad}{bc}$.

Chiều cao của các tam giác AOD và BOC bằng nhau nên

$$\frac{S_{\triangle AOD}}{S_{\triangle BOC}} = \frac{d}{b}.$$

Ở phía bên kia,

$$\frac{S_{\triangle AOD}}{S_{\triangle BOC}} = \frac{xv \sin \varphi_5}{yz \sin \varphi_6}.$$

Hãy để chúng tôi chứng minh rằng $\sin \varphi_5 = \sin \varphi_6$. Để làm điều này, hãy lưu ý rằng $\varphi_1 + \varphi_2 + \varphi_3 + \varphi_4 = \pi$ (đây là số dương của tổng tất cả các góc của tứ giác), $\varphi_1 + \varphi_2 + \varphi_5 = \pi$, $\varphi_4 + \varphi_3 + \varphi_6 = \pi$. Theo đó, $\varphi_5 + \varphi_6 = \pi$, $\sin \varphi_5 = \sin \varphi_6$ và từ công thức (2) chúng ta thu được

$$\frac{S_{\triangle AOD}}{S_{\triangle BOC}} = \frac{xv}{yz}.$$

Từ sự tương ứng (1) và (2') ta có $\frac{xv}{gz} = \frac{d}{b}$, tương tự như $\frac{xz}{yv} = \frac{a}{c}$. Thay đổi hai đẳng thức cuối, ta được

$$\frac{x^2}{y^2} = \frac{ad}{bc},$$

và chia số thứ nhất cho số thứ hai, chúng ta có

$$\frac{v^2}{z^2} = \frac{cd}{ab}.$$

Hãy xem bài toán, trong đó phần tử phụ là âm lượng.

*) Bạn có thể đọc thêm tài liệu về phương pháp tính diện tích trên tạp chí «Kvant», 1971, số 12.

⟦folio 50⟧

Cơm. 8.

các hàm đo góc, sau đó một góc phụ được đưa vào. Sau đó, vận dụng định lý sin hoặc cosin, giải tam giác tìm các thành phần để viết một điều kiện nhất định dưới dạng phương trình.

Nhiệm vụ 8 (MSU, Cơ học và Toán học, 1962). Một đường thẳng tùy ý được vẽ qua chuỗi tam giác đều trong mặt phẳng biểu thức của tam giác. Chứng minh rằng tổng bình phương khoảng cách từ các đỉnh của một tam giác đến cùng một đường thẳng không phụ thuộc vào việc chọn đường thẳng.

Đặt điểm $O$ là tâm của tam giác $ABC$ (Hình 8). Các điểm $D, E, F$ lần lượt là hình chiếu của các đỉnh $A, B, C$ lên đường thẳng $l$, $R$ là bán kính của đường tròn ngoại tiếp tam giác $ABC$. Hãy giới thiệu một góc phụ $\varphi$, ký hiệu là $\Rightarrow BOE$. Sau đó

$$\Rightarrow AOD = \Rightarrow AOB - \Rightarrow BOD = \varphi - \frac{\pi}{3}.$$

(tự kiểm tra xem tổng trong ngoặc vuông là $\frac{3}{2}$).

Nhiệm vụ 9 (MIPT, 1967). Tại đáy của trục thẳng ABCD vẽ một mặt phẳng cắt đáy trên $A_1B_1C_1D_1$. Các góc tam giác $B$ và $D_1$ chứa các quả cầu tiếp xúc với mặt phẳng và có bán kính $r = \frac{a}{5}$, $R = \frac{a}{4}$. Gọi tên chiều cao của hình bình hành.

Phần đường chéo $DBB_1D_1$ của hình bình hành (Hình 9) sẽ đi qua tâm của các quả bóng $O$ và $O_1$. Gọi $L$ và $L_1$ là điểm tiếp xúc của các quả bóng và đáy của hình bình hành, $N$ và $N_1$ là điểm tiếp xúc của các quả bóng với một mặt phẳng cho trước (chúng ta chưa biết liệu chúng có nằm trong hình bình hành hay không)

Cơm. 9.

⟦folio 51⟧

hoặc bên trong nó, nhưng chúng ta sẽ không cần nó), OF và $O_1E_1$ là các đường phân giác của các góc NOL và $N_1O_1L_1$ (điểm $F$ là điểm giữa của BD), $EE_1$ là chiều cao của hình bình hành, $OL = ON = r$, $O_1L_1 = O_1N_1 = R$. Hãy đặt $\Rightarrow BFE_1 = 2\alpha$, $L_1E_1 = x$, $E_1B_1 = y$, $FE = z$. Sau đó

$$h = z \mathrm{tg} 2\alpha, \quad z = FB - BE = \frac{a \sqrt{2}}{2} - y, \quad y = a \sqrt{2} - x - D_1L_1 = a \sqrt{2} - x - R \sqrt{2} \quad \text{и} \quad z = x + R \sqrt{2} - \frac{a \sqrt{2}}{2} = x - \frac{a \sqrt{2}}{4}.$$

Từ sự giống nhau của các tam giác $O_1L_1E_1$ và $OLF$ suy ra $\frac{x}{R} = \frac{FL}{r}$, $FL = FB - LB = \frac{a \sqrt{2}}{2} - r \sqrt{2} = \frac{3a \sqrt{2}}{10}; \quad x = \frac{3}{8} a \sqrt{2}, \quad z = \frac{a \sqrt{2}}{8}$.

Từ tam giác $OLF$ có $\mathrm{tg} \alpha = \frac{r}{FL} = \frac{\sqrt{2}}{3}$, từ đó có $h = \frac{3}{14} a$.

Bài toán 10 (MSU, Cơ học và Toán học, 1963). Cạnh bên của một hình bình hành tam giác đều bằng $b$, góc giữa các ranh giới bên bằng $\varphi$. Tìm cạnh của đáy.

Chúng ta thả các đường vuông góc từ các điểm $B$ và $C$ lên cạnh bên AS (Hình 10). Dễ dàng chứng minh rằng đáy của cả hai đường vuông góc này là một điểm $D$ (chứng minh), và do đó $\star BDC = \varphi$.

Hãy giới thiệu góc phụ $\star BAS = \alpha$ và vẽ trung điểm SK

Cơm. 10.

kim tự tháp. Rõ ràng là $AB = 2AK = 2b \cos \alpha$. Do đó, đối với lời giải bài toán chỉ cần tính $\cos \alpha$ là đủ. Vì $\alpha < 90^\circ$, nên từ tam giác $BAD$ ta có $\alpha = \arcsin \frac{BD}{AB}$.

Lần lượt, độ dài của đoạn $BD$ được xác định từ tam giác $BLD$ (DL là chiều cao của tam giác $BDC$):

$$BD = \frac{BL}{\sin \frac{\varphi}{2}} = \frac{AB}{2 \sin \frac{\varphi}{2}}.$$

$\alpha = \arcsin \frac{1}{2 \sin \frac{\varphi}{2}}$, từ

$$AB = b \sqrt{4 - \frac{1}{\sin^2 \frac{\varphi}{2}}}.$$

Bảo mẫu có quyền

1 (MIPT, 1969). Một đường tròn nội tiếp tam giác $ABC$, tiếp xúc với cạnh $AB$ tại điểm $D$ và tiếp xúc với cạnh $BC$ tại điểm $E$. Tìm các góc của tam giác nếu

$$\frac{BD}{AD} = \frac{1}{2}, \frac{BE}{CE} = \frac{1}{3}.$$

2 (MIPT, 1969). Trong một tứ diện đều $ABCD$, đoạn $MN$ nối trung điểm của cạnh $AC$ với tâm của mặt $BDC$ và điểm $E$ nằm ở trung điểm của cạnh $AB$. Tìm góc giữa các đoạn $MN$ và $DE$.

3 (MEPhI, 1971). Trong một hình thang có hai đáy là $a$ và $b$, một đường thẳng song song với đáy được vẽ qua giao điểm của các đường chéo. Tìm độ dài đoạn thẳng bị cắt bởi các cạnh của hình thang.

4 (Miệt, 1970). Cho một tam giác $ABC$, trên cạnh $AC$ lấy điểm $E$ sao cho $AE : EC = a$, trên cạnh $AB$ lấy điểm $D$ sao cho $AD : DB = b$. Các phân đoạn $CD$ và $BE$ đã được thực hiện. Tìm tỉ số diện tích của hình tứ giác thu được với diện tích của tam giác đã cho.

5 (MSU, nhà vật lý, 1969). Một paramid được nội tiếp trong một quả bóng, các cạnh bên của nó bằng $c$. Đáy của nó là một hình chữ nhật, các cạnh của nó nối các ugg $\alpha$ và $\beta$ radian thành các phần của quả bóng bằng các mặt phẳng của các mặt bên. Xác định bán kính của hình cầu ngoại tiếp.

6 (MSU, Cơ học và Toán học, 1961). Trên một đường tròn bán kính $R$, cho hai điểm $A$ và $B$, khoảng cách giữa chúng là $l$. Giá trị lớn nhất mà tổng $AC^2 + BC^2$ có thể nhận là bao nhiêu nếu điểm $C$ cũng nằm trên đường tròn này?

7 (NSU, Cơ học và Toán học, 1969). Góc nhị diện ở cạnh bên của một tứ giác đều paramid bằng $\alpha$, bán kính của quả cầu nội tiếp bằng $R$. Tìm bề mặt hoàn chỉnh của paramid.
