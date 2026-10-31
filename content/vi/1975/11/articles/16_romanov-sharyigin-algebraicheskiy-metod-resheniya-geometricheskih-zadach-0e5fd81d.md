---
id: 1975-11-romanov-sharyigin-algebraicheskiy-metod-resheniya-geometricheskih-zadach-0e5fd81d
issue: kvant_1975_11
year: 1975
number: "11"
title: Phương pháp đại số lời giải hình học bài toán
authors:
  - Романов С. В.
  - Шарыгин И. Ф.
rubric: praktikum-abiturienta
rubric_sub: Практикум абитуриента
page_first: 47
page_last: 51
page_labels: 45-49
tag: PK74
lang: vi
source: kvant_digital
extraction: vision
content_sha256: bd48147742688f0cdb04a1a86c0787baba1686469593cd2bb80f4f590645d8f2
prompt_sha256: draft-1
translated_from: content/ru/1975/11/articles/16_romanov-sharyigin-algebraicheskiy-metod-resheniya-geometricheskih-zadach-0e5fd81d.md
source_content_sha256: d4e5d5a3932e4a29df1e6980f7fa61687fb82c87e1c053a5ebf40f084c045eb3
translation_model: draft
translation_run: vi-draft-2026-10-31
translation_quality: draft
---

⟦folio 45⟧

Phương pháp đại số lời giải hình học bài toán

S. V. Romanov, I. F. Sharyzin

Khi trong một kỳ thi, bạn được yêu cầu bài toán làm phép tính planietripy, thường không đáng để lãng phí thời gian tìm kiếm hình học lời giải, số hữu tỉ lời giải của các số đại số của nó. Tất nhiên, hình học lời giải thường thanh lịch hơn, trong khi đại số chứa các biểu thức rườm rà, nhưng trong kỳ thi, không giống như tối ưu hóa, sự duyên dáng của việc thực hành lời giải không ảnh hưởng đến điểm số. Vì vậy, “vũ khí” chính cho các kỳ thi lời giải hình học bài toán là phương pháp đại số. Đây là những gì chúng ta sẽ nói về trong bài viết này.

Đầu tiên chúng tôi trình bày hai lời giải của một bài toán.

Bài toán 1. Chứng minh rằng $l^2 = ab - mn$ (Hình 1). Hãy đặt $\Rightarrow ADB = \alpha$. Theo định lý cosin cho tam giác $ABD$ và $BDC$ ta có:
$$a^2 = l^2 + m^2 - 2ml \cos \alpha,$$
$$b^2 = l^2 + n^2 + 2nl \cos \alpha.$$ (2)
Hãy nhân (1) với $n$ và (2) với $m$ rồi cộng các biểu thức thu được. Cho rằng $\frac{m}{n} = \frac{a}{b}$, chúng ta có thể dễ dàng chuyển đổi tổng thành dạng $l^2 = ab - mn$.

Đây là phương pháp đại số.

Trước khi đọc lời giải tiếp theo, hãy thử tự mình giải bài toán hình học bài toán này.

Vì vậy, hoàn toàn là hình học lời giải. Chúng ta hãy mô tả một đường tròn xung quanh tam giác $ABC$ (Hình 2) và tiếp tục bissertis cho đến khi nó giao với đường tròn này tại điểm $E$. Theo định lý nổi tiếng $mn = l \cdot DE$. Ngoài ra, từ sự giống nhau của các tam giác $BCE$ và $ABD$ suy ra $\frac{a}{l} = \frac{l + DE}{b}$, từ đó $ab = l^2 + l \cdot DE$. Thay $l \cdot DE$ bằng $mn$, ta được kết quả cần tìm.

Cơm. 1.
Cơm. 2.

⟦folio 46⟧

Tất nhiên, lời giải này ngắn hơn và thanh lịch hơn cái trước, nhưng có lẽ sẽ mất khá nhiều thời gian để hiểu rõ về nó.

Phương pháp đại số dựa trên các kỹ thuật tiêu chuẩn nhất định. Có hai loại phương pháp đại số:

a) “đếm trực tiếp”;
b) “Viết một phương trình.”

Bản chất của “tài khoản trực tiếp” như sau. Chúng ta kết nối các đại lượng được chỉ định trong điều kiện bài toán và những đại lượng cần tìm với một số nguyên của các đại lượng trung gian, mỗi đại lượng được xác định tuần tự thông qua các đại lượng trước đó.

Bài toán 2 (MSU, Khoa Địa lý, 1966). Trong hình bình hành có các cạnh a, b và góc α vẽ được bí mật của bốn góc. Tìm diện tích tứ giác giới hạn bởi bicsecris (Hình 3).

Trước hết, rất hữu ích khi lập một kế hoạch lời giải bài toán, nói cách khác là viết ra một số nguyên các phần tử có thể tính liên tiếp, kết nối những gì đã cho và những gì cần tìm.

Trước hết hãy lưu ý rằng MNPQ là hình bình hành. Chúng ta hãy lần lượt tìm $\triangle ABC$, $\triangle ABM$, $\triangle AMB = \triangle QMN$. Khi đó từ $\Delta BCQ$ (theo định lý sin) ta tìm được BQ, từ $\Delta BMA - BM$ và AM, từ $\Delta NAD - AN$. Sau đó, dễ dàng tính được MN, QM và diện tích cần tìm $S = QM \cdot MN \cdot \sin \triangle QMN$.

Vì vậy, $\triangle ABC = 180^\circ - \alpha$, $\triangle ABM = \frac{180^\circ - \alpha}{2}$, $\triangle AMB = 90^\circ = \triangle QMN$, tức là MNPQ là hình chữ nhật. $BQ = a \sin \frac{\alpha}{2}, BM = b \sin \frac{\alpha}{2}, MQ = BQ - BM = (a - b) \sin \frac{\alpha}{2}$, v.v.

Đáp số hóa ra là:

$$S = \frac{1}{2} (a - b)^2 \sin \alpha.$$

Bây giờ chúng ta hãy đưa ra một ví dụ bài toán cho việc “soạn một phương trình”.

Bài toán 3 (MSU, Khoa Địa lý, 1973). Trên một mặt phẳng nhất định có một góc vuông. Một đường tròn có tâm nằm trong một góc tiếp xúc với một cạnh của góc, cắt cạnh kia tại các điểm A và B, và cắt các đường phân giác của góc tại các điểm C và D; $AB = \sqrt{6}, CD = \sqrt{7}$. Tìm bán kính của hình tròn.

Đặt $O$ là tâm của đường tròn, $R$ bán kính của nó, $M$ điểm tiếp xúc (Hình 4). Khoảng cách từ tâm đến AB ký hiệu là x. Bạn có thể tạo ngay phương trình đầu tiên: $R^2 - x^2 = AN^2$.

Hãy để chúng tôi cho $OP \perp CD$, $OP = \frac{OE}{\sqrt{2}} = \frac{R - x}{\sqrt{2}}$. Bây giờ chúng ta có thể tạo phương trình thứ hai:

$$R^2 - \left( \frac{R - x}{\sqrt{2}} \right)^2 = CP^2.$$

Hãy sử dụng thực tế là $AN = \frac{\sqrt{6}}{2}$,

⟦folio 47⟧

$$CP = \frac{\sqrt{7}}{2},$$ và tạo ra một hệ thống
$$\begin{cases} R^2 - x^2 = \frac{6}{4}, \\ R^2 - \left( \frac{R - x}{\sqrt{2}} \right)^2 = \frac{7}{4}. \end{cases}$$

Giải nó, ta tìm được $R = \sqrt{2}$.

Với lời giải bài toán trong việc “soạn phương trình” thường không cần số ẩn và số phương trình trùng nhau. Điều quan trọng là khi xây dựng các phương trình, tất cả các tương ứng phát sinh từ điều kiện đều được sử dụng. Nếu yêu cầu này được đáp ứng thì ẩn số cần thiết hoặc sự kết hợp của các ẩn số phải được xác định bằng hệ thống tổng hợp.

Một hệ thống tương tự cũng có thể được tìm thấy trong các bài toán “đếm trực tiếp”.

Bài toán 4. Các vòng tròn bán kính $R$ và $r$ ($R > r$) chạm vào bên trong tại điểm $A$. Dây CD của đường tròn lớn vuông góc với đường kính $AB$ nhỏ hơn đường tròn, $E$ là giao điểm của $CD$ với đường tròn bán kính $r$, các điểm $E$ và $C$ nằm cách $AB$ một bên. Tìm bán kính của đường tròn ngoại tiếp tam giác $AEC$.

Chúng ta hãy biểu thị $\triangle CEA$ bằng $\varphi$ và $AF$ bằng $a$ (Hình 5). Từ tam giác $CAM$ ta thu được $AC = \sqrt{2aR}$, tương tự như $AE = \sqrt{2ar}$. Sử dụng định lý sin từ tam giác $AEC$, chúng ta thu được giá trị cho bán kính ban đầu

$$\frac{AC}{2 \sin \varphi}.$$ Giá trị của tội lỗi $\varphi$ dễ dàng tìm được từ tam giác $FEA$. Đáp số: $\sqrt{Rr}$.

Chúng tôi đã phải giới thiệu các tham số $a$, $\varphi$, vì điều kiện bài toán không xác định tính đầy đủ của cấu hình hình học. Nhưng đáp số không bao gồm các thông số này.

Bài toán 5 (MIPT, 1967). Trong tam giác vuông $ABC$ kamet $AB = 3$, kamet $AC = 6$. Tâm của các đường tròn bán kính 1, 2 và 3 lần lượt đặt tại các điểm $A$, $B$ và $C$. Tìm bán kính của đường tròn tiếp tuyến ngoài với mỗi đường tròn trong số ba đường tròn đã cho.

Đặt $O$ là tâm của hình tròn mong muốn, $x$ bán kính của nó, $\angle OAC = \alpha$ (Hình 6). Chúng ta hãy viết định lý cosine cho các tam giác $AOC$ và $AOB$. Ta thu được hệ phương trình
$$\begin{cases} (x+3)^2 = (x+1)^2 + 36 - 12(x+1)\cos \alpha, \\ (x+2)^2 = (x+1)^2 + 9 - 6(x+1)\sin \alpha. \end{cases}$$

Bằng cách biểu thị sin $\alpha$ và cos $\alpha$ từ các phương trình này và sử dụng sự tương ứng $\sin^2 \alpha + \cos^2 \alpha = 1$, chúng ta thu được một phương trình chỉ chứa một ẩn số $x$; giải phương trình này, ta thu được đáp số: $x = \frac{8\sqrt{11} - 19}{7}$.

Lưu ý rằng việc sử dụng định lý cosine để soạn phương trình là một trong những định lý được sử dụng thường xuyên nhất và đóng vai trò tổng thể.

⟦folio 48⟧

Ma đóng vai trò quan trọng với lời giải hình học bài toán, ở đây phụ thuộc rất nhiều vào kinh nghiệm và trực giác.

Bài toán 6 (MIPT, 1966). Các đường phân giác AM và BN của đồ thị ABC cắt nhau tại điểm O. Biết AO = $\sqrt{3}$ MO, NO = $(\sqrt{3}-1)$ BO. Tìm bài học tái học ABC.

Chúng ta hãy giới thiệu các ẩn số sau (Hình 7): BC = x, AC = y, AB = z. $\frac{MC}{BM} = \frac{AC}{AB}$, nên MB = $\frac{zx}{y+z}$, tương tự AN = $\frac{yz}{x+z}$. Bây giờ, khi xét các tam giác BMA và BAN có các đường phân giác BO và AO, dễ dàng thu được hệ phương trình sau:

$$\begin{cases} \frac{x}{z+y} = \frac{1}{\sqrt{3}}, \\ \frac{y}{x+z} = \sqrt{3}-1. \end{cases}$$

Tiếp theo, bạn có thể biểu diễn tất cả các ẩn số theo một vật (ví dụ: theo x) và sử dụng định lý cosin để tìm các góc của tam giác - $30^\circ$, $60^\circ$ và $90^\circ$. Hãy thử giải bài toán này bằng cách sử dụng các góc bắt đầu không xác định và bạn sẽ thấy rằng lời giải trở nên khó khăn hơn nhiều.

Cần lưu ý rằng hầu hết bài toán giải bằng phương pháp đại số có thể có hai lựa chọn lời giải - cả “phép tính trực tiếp” và “thành phần phương trình”; các phương pháp này không tương tác với nhau.

Bài toán 7. Bên trong góc nhọn $\alpha$ lấy điểm A, cách xa cạnh của góc tại p và q. Tìm khoảng cách từ điểm A đến đỉnh của góc.

Gọi M là giao điểm của AC và OB (Hình 8), dễ dàng nhận thấy $\triangle BAM = \alpha$. Bây giờ chúng ta tìm MC = q + $\frac{p}{\cos \alpha}$, OC = MC $\cdot$ctg $\alpha$ = $\frac{q \cos \alpha + p}{\sin \alpha}$. Ta tìm khoảng cách AO từ tam giác AOC:

$$AO = \frac{\sqrt{p^2 + 2pq \cos \alpha + q^2}}{\sin \alpha}.$$

Đây là "đếm trực tiếp". Trong khi đó, không khó để giải bài toán và “tạo phương trình”, bỏ qua lời giải theo những cách không thua kém nhau về độ đa dạng. Vì vậy, hãy “tạo nên các phương trình”.

Hãy giới thiệu những ẩn số $\triangle AOC = \varphi$, AO = x. Xét các tam giác AOB và AOC, ta lập hệ hai phương trình với hai ẩn số:

$$\begin{cases} x \sin \varphi = q, \\ x \sin (\alpha - \varphi) = p. \end{cases}$$

Hãy tự mình giải quyết hệ thống này.

Nếu bạn một lần nữa xem xét cẩn thận các ví dụ được đưa ra trong các bài viết, bạn sẽ dễ dàng nhận thấy rằng trong hầu hết các ví dụ, một số công trình bổ sung đã được thực hiện bằng cách sử dụng một số cân nhắc về hình học. Vì vậy, giải phương trình phẳng

⟦folio 49⟧

Cơm. 9.

bài toán sử dụng phương pháp đại số, chúng ta không nên quên rằng đây chính xác là phép đo phẳng bài toán, chứ không phải đại số, nghĩa là, nhiều phép tính hình học không thể được thông qua, vì chúng thường bỏ qua lời giải. Mặt khác, bạn có thể biến bài toán hình học đơn giản nhất thành một đại số phức tạp hơn, chẳng hạn như trường hợp của lời giải của bài toán sau đây với các tác giả của cùng một sổ tay tuyển sinh.

Nhiệm vụ 8 (MSU, Khoa Địa lý, 1969). Cho hình thang cân bằng ABCD, đáy AD = 12, BC = 6, chiều cao hình thang là 4. Design_AC chia góc BAD của hình thang thành các góc BAC và CAD. Góc nào trong số này lớn hơn?

Lời giải trong số bài toán này được đề xuất trong hướng dẫn đã đề cập như sau. Đặt $\Rightarrow BAC = \alpha$ (Hình 9), $\Rightarrow CAD = \beta$. Trước tiên, bạn có thể tính $tg \Rightarrow BAD = tg(\alpha + \beta)$, sau đó là $tg \beta$ và cuối cùng, bằng cách sử dụng các công thức lượng giác, hãy tìm $tg \alpha$. So sánh $tg \alpha$ và $tg \beta$, chúng ta nhận được đáp số cho câu hỏi đặt ra trong bài toán. Trong khi đó, lời giải đáng kể lưu ý rằng $\Rightarrow BCA = \beta$ và $AB = 5$ (theo định lý Pythagore). Từ tam giác $ABC > \beta$, vì trong một tam giác có một góc lớn hơn đối diện với cạnh lớn hơn.

Bài tập
1 (MSU, Khoa Địa lý, 1966). Trong một hình thang cân bằng, hai đáy là $a$ và $b$, và góc của hình tam giác với đáy là $\alpha$. Tìm độ dài đoạn nối giao điểm của hai đường chéo với điểm giữa của cạnh hình thang.

2 (MSU, nhà vật lý, 1963). Trong một đường tròn bán kính $R$ qua một điểm có đường kính $M$, dây $AB$ được vẽ một góc $\varphi$ với đường kính; đồng thời $BM : AM = p : q$. Qua điểm $B$ vẽ dây cung $BC$, vuông góc với đường kính đã cho và điểm $C$ được nối với điểm $A$. Tìm diện tích tam giác $ABC$.

3 (MSU, Khoa Kinh tế, 1968). Trong hình thang $ABCD$ các góc ở đáy lớn hơn $a$ là $\alpha$ và $\beta$, và chiều cao của hình thang là $h$. Gọi $O_1, O_2, O_3, O_4$ là tâm của đường tròn ngoại tiếp lần lượt qua các tam giác $ABC, BCD, CDA, DAB$. Tìm diện tích tứ giác $O_1O_2O_3O_4$.

4. Các vòng tròn bán kính $R$ và $r$ cắt nhau. Hãy vẽ một tiếp tuyến chung của chúng. Đặt điểm $A$ giao điểm của đường tròn và các điểm tiếp tuyến $B$ và $C$ nằm ở hai phía đối diện của đường tâm. Tìm bán kính của đường tròn ngoại tiếp tam giác $ABC$.

5 (MSU, Cơ khí, 1968). Trong một tứ giác lồi $ABCD$, bisset của góc $ABC$ cắt cạnh $AD$ tại điểm $M$ và đường vuông góc hạ từ đỉnh $A$ sang cạnh $BC$ cắt $BC$ tại điểm $N$ sao cho $BN = NC$ và $AM = 2MD$. Tìm các cạnh và diện tích của tứ giác $ABCD$ nếu chu vi của nó là $5 + \sqrt{3}$, $\Rightarrow BAD = 90^\circ$, $\Rightarrow ABC = 60^\circ$.

6 (MIPT, 1967). Các vòng tròn bán kính $R$ và $r$ chạm vào bên trong điểm $A$. Tìm cạnh của một tam giác đều $ABC$ có các đỉnh $B$ và $C$ lần lượt nằm trên đường tròn bán kính $R$ và $r$.

7. Đường thẳng $l$ cắt các cạnh bên $AB$ và $BC$ của tam giác cân $ABC$ lần lượt tại các điểm $M$ và $N$. Được biết, $\frac{AM}{BM} = m$, $\frac{CN}{BN} = n$. Tìm tỉ số giữa đường thẳng chia độ cao của tam giác rơi từ đỉnh $B$.

8 (MSU, nhà vật lý, 1969). Trong tam giác $ABC$ ($AB \neq AC$), các đường trung tuyến được vẽ từ các đỉnh $B$ và $C$ đến các cạnh $AC$ và $AB$. do đó tỉ lệ nghịch với các cạnh này. Tìm các cạnh $AC$ và $AB$ của tam giác nếu $BC = a$, $\Rightarrow BAC = a$.

9 (MSU, Cơ khí, 1971). Bạn có thể viết bằng hình tứ giác $ABCD$ và bạn có thể vẽ một vòng tròn xung quanh nó. Các đường chéo của tứ giác này vuông góc với nhau. Tìm diện tích của nó nếu bán kính của hình tròn là $R$ và $AB = 2BC$.

10 (MSU, nhà vật lý, 1974). Hai tam giác đều $ABC$ và $CDE$ giống nhau ở cạnh 1 nằm trên mặt phẳng sao cho chúng chỉ có một điểm chung $C$ và $\Rightarrow BCD < \pi/3$. Điểm $K$ là giữa $AC$, $L$ là giữa $CE$, $M$ là giữa $BD$. Diện tích tam giác $KLM$ bằng $\sqrt{3}/5$. Tìm $BD$.
