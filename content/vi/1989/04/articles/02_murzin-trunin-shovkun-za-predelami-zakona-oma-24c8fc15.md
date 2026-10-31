---
id: 1989-4-murzin-trunin-shovkun-za-predelami-zakona-oma-24c8fc15
issue: kvant_1989_4
year: 1989
number: "4"
title: Ngoài định luật Ohm
authors:
  - Мурзин С. С.
  - Трунин М. Р.
  - Шовкун Д. В.
rubric: osnovnye-stati
page_first: 4
page_last: 10
page_labels: 2, 4, 5, 6, 7, 8
tag: YUIT
lang: vi
source: kvant_digital
extraction: vision
content_sha256: e495e3b8aafd316b437f2731ec0069e141899e3f1f13841e1abf91b810c7419d
prompt_sha256: draft-1
translated_from: content/ru/1989/04/articles/02_murzin-trunin-shovkun-za-predelami-zakona-oma-24c8fc15.md
source_content_sha256: f61dbdfde995504194aa8ca2df9223337e3b7d2c0d0642c0720fae40f69872b7
translation_model: draft
translation_run: vi-draft-2026-10-31
translation_quality: draft
---

⟦folio 2⟧

NGOÀI
LUẬT OMA

Ứng viên Khoa học Vật lý và Toán học
S. S. MURZIN,
Ứng viên Khoa học Vật lý và Toán học
M. R. TRUNIN,
Ứng viên Khoa học Vật lý và Toán học
D.V.SHOVKUN

"Coi chừng!" - một người thường xuyên sử dụng lời khuyên này của Kozma Prutkov khi nói đến các định luật vật lý. Đặc biệt, về các định luật vật lý. Ví dụ, chúng ta hãy nhớ lại định luật Ohm: dòng điện tỉ lệ với điện áp. Hóa ra đây không phải là trường hợp. Và tốt! Nếu định luật này luôn được tuân thủ, chúng ta sẽ không có nhiều thiết bị điện và vô tuyến. May mắn thay, định luật Ohm, giống như hầu hết các định luật vật lý, có phạm vi giới hạn. Nằm ngoài phạm vi của định luật này, các hiện tượng vật lý thú vị phát sinh đảm bảo hoạt động của các thiết bị này. Bản thân những hiện tượng này rất thú vị, nhưng hôm nay chúng ta sẽ thảo luận một câu hỏi khác: tại sao định luật Ohm lại vi phạm?

định luật Ohm

Hãy nối dây dẫn với mạch điện và thay đổi cường độ dòng điện I chạy qua dây dẫn ở các giá trị khác nhau của điện áp đặt vào U. Như vậy, ta thu được sự phụ thuộc I=I(U) - dòng điện-điện áp của dây dẫn điện. Theo định luật Ohm, cường độ dòng điện của một dây dẫn điện, tức là dòng điện có điện áp hiện tại, là một hàm tuyến tính

$$I(U) = U/R,$$

và điện trở R không phụ thuộc vào U. Nếu điều này không đúng (định luật Ohm không thỏa mãn), thì điện vôn-ampe phi tuyến tính.

Ví dụ đơn giản nhất về chất dẫn điện vi phạm định luật Ohm là hình xoắn ốc của đèn sợi đốt. Đối với đèn có công suất 40 V, đặc tính dòng điện-điện áp được thể hiện ở hình 1. Tiết diện tuyến tính chỉ ở U<5 V và ở giá trị U lớn, dòng điện I tăng chậm hơn so với trường hợp phụ thuộc tuyến tính I(U). Không khó để chứng minh tại sao điều này xảy ra. Khi điện áp tăng, cuộn dây nóng lên và điện trở của nó tăng lên. Ví dụ này minh họa quy tắc chung: định luật Ohm chỉ có hiệu lực ở I và U đủ nhỏ, còn ở dòng điện và điện áp cao thì nó bị vi phạm.

Hãy viết định luật Ohm dưới dạng khác. Để làm điều này, chúng tôi giới thiệu các giá trị mật độ hiện tại j=I/S, trong đó S là diện tích mặt cắt ngang của dây dẫn. Sau đó

$$j = \frac{I}{S} = \frac{U}{RS} = \frac{U}{(\rho L/S)S} = \frac{1}{\rho} \frac{U}{L} = \sigma E.$$

Ở đây $\rho$ là điện trở suất của dây dẫn, các giá trị $\sigma=1/\rho$ gọi là độ dẫn điện riêng, $L$ là chiều dài dây dẫn, $E=U/L$ là điện áp điện trường. Định luật Ohm giả định mối quan hệ tuyến tính giữa mật độ dòng điện j và điện áp điện trường E. Nếu vì lý do nào đó độ dẫn điện phụ thuộc vào độ lớn của điện trường thì sự phụ thuộc của j vào E trở nên phi tuyến và định luật Ohm bị vi phạm.

Để tìm ra nguyên nhân vi phạm định luật Ohm, hãy xem xét chuyển động của các electron trong dây dẫn khi không có và có điện trường.

⟦folio 4⟧

$$\vec{u} = \frac{1}{N} \sum_{i=1}^{N} \left( \vec{v}_i - \frac{e\vec{E}}{m^*} t_i \right) = \frac{1}{N} \sum_{i=1}^{N} \vec{v}_i - \frac{e\vec{E}}{m^*} \left( \frac{1}{N} \sum_{i=1}^{N} t_i \right).$$

Giá trị $\frac{1}{N} \sum_{i=1}^{N} \vec{v}_i$ là tốc độ trung bình của đầu máy điện ngay sau khi tản nhiệt. Vì tốc độ của đầu máy điện có thể tiêu tan ngay lập tức theo bất kỳ hướng nào, $\frac{1}{N} \sum_{i=1}^{N} \vec{v}_i = 0$. Giá trị $\frac{1}{N} \sum_{i=1}^{N} t_i = \tau$ có ​​ý nghĩa về thời gian rảnh trung bình vốn đã quen thuộc. Vì vậy, dưới tác dụng của điện trường, tất cả các electron đều thu được tốc độ bổ sung (gọi là độ trôi), giá trị trung bình của tốc độ này là $u = eE\tau/m^*$ và tốc độ này được hướng song song với trường $\vec{E}$.

Như vậy, khi có điện trường, chuyển động trôi của đầu máy điện chồng lên chuyển động xaotic, xuất hiện chiều chuyển động ưu tiên của đầu máy điện - xuất hiện dòng điện. Nếu nồng độ của đầu máy điện trong dây dẫn là $n$ thì mật độ của dòng điện này là

$$j = enu = \frac{ne^2\tau}{m^*} E.$$

Mặt khác, chúng tôi biết rằng $j = \sigma E$. Có nghĩa,

$$\sigma = \frac{ne^2\tau}{m^*}.$$

Công thức này được gọi là công thức Drude. Định luật Ohm có hiệu lực nếu không có đại lượng nào trong công thức Drude phụ thuộc vào $E$. Nếu nồng độ của đầu máy điện $n$ hoặc thời gian rảnh $t$, hoặc khối lượng hiệu dụng $m^*$ thay đổi dưới tác dụng của điện trường thì định luật Ohm bị vi phạm.

Khi nào định luật Ohm đúng?

Trước hết, chúng ta hãy xem xét trong những điều kiện nào thì giá trị $t$ không thay đổi dưới tác động của trường $E$.

Thời gian $t$ phụ thuộc vào tốc độ của đầu máy điện. Tốc độ trôi $u =$

$$eE\tau/m^*, \text{ появляющая при включении электрического поля, возрастает при увеличении } E. \text{ Пока электрическое поля мало, так что дрейфовая скорость } u \text{ гораздо меньше средней скоростиxaотического движения } v_0, \text{ величины } u \text{ можно пребречь и считать время } t \text{ не зависит от поля } E. \text{ Если } E \text{ велико настояло, что значение } u \text{ сравнито с } v_0, \text{ то дрейфовою скорость нужно учитывать. В этом случае скорости электровоз и, следовательно, время свободного пробета } t \text{ оказываются зависящими от электрического поля.}$$

Vì vậy, để thỏa mãn định luật Ôm thì cần phải thỏa mãn điều kiện

$$u \ll v_0,$$

nghĩa là hướng của điện trường trong dây dẫn phải nhỏ hơn $E = m^*v_0/e\tau$ rất nhiều.

Trong chất bán dẫn, như chúng ta đã nói, $v_0 \sim 10^5$ m/s. Để đạt được giá trị $u$ tương đương với $v_0$, phải áp dụng trường $E \sim 10^6$ V/m cho chất bán dẫn. Đây là một giá trị rất lớn, có thể so sánh với hướng của trường trong tia sét. Tuy nhiên, một trường như vậy có thể được tạo ra trong chất bán dẫn.

Có một giới hạn tốc độ khác mạnh hơn $u$. Nó phải nhỏ hơn tốc độ âm thanh trong dây dẫn (a $v_{38} \sim 10^3$ m/s):

$$u < v_{38}.$$

Ngay khi tốc độ $u$ đạt giá trị $v_{38}$, các dao động âm thanh sẽ được kích thích trong tinh thể. Trong trường hợp này, thời gian sạc miễn phí $t$ và độ dẫn điện $\sigma$, tỷ lệ thuận với $\tau$, có thể giảm. Tình huống này tương tự như lực cản khí động học tăng mạnh sau khi máy bay vượt qua rào cản âm thanh.

Vì vậy, trong trường $E_{38} \geq m^*v_{38}/e\tau$ độ dẫn điện bắt đầu phụ thuộc vào giá trị $E$ và định luật Ohm bị vi phạm.

Tác dụng của điện trường không chỉ trùng với sự xuất hiện của chuyển động trôi. Người ta biết rằng khi dòng điện chạy qua một dây dẫn, một tế bào Joule được giải phóng và nó nóng lên. Chúng ta hãy xem xét quá trình này chi tiết hơn.

⟦folio 5⟧

Bất kỳ dây dẫn nào cũng có thể được coi là bao gồm hai hệ thống con: một mạng tinh thể được hình thành bởi các nguyên tử của chất đó và một loại khí chứa các electron dẫn lấp đầy mạng tinh thể. Các electron và mạng có thể được đặc trưng bởi nhiệt độ của chúng $T_e$ và $T_p$. Khi không có điện trường, khí electron cân bằng nhiệt với mạng tinh thể và môi trường: $T_e=T_p=T_c$. Trường $E$ tác dụng lên các electron dẫn và làm chúng nóng lên trước tiên. Chỉ khi đó nhiệt mới được truyền từ các electron vào mạng và sau đó ra môi trường. Do đó, khi có trường, trạng thái cân bằng nhiệt bị phá vỡ sao cho $T_e>T_p>T_c$.

Nếu sự truyền nhiệt từ dây dẫn ra môi trường hẹp hơn sự truyền nhiệt từ electron sang nguyên tử và do đó, $T_e-T_p\ll T_p-T_c$, thì mạng cùng với các electron sẽ nóng lên toàn bộ. (Tình huống này là điển hình cho dây tóc của đèn sợi đốt.) Cũng có thể xảy ra trường hợp ngược lại, khi nhiệt độ electron cao hơn nhiều so với nhiệt độ mạng và $T_e-T_p\gg T_p-T_c$.

Trong kim loại, như chúng ta đã nói, tốc độ trung bình của chuyển động nhiệt hỗn loạn của các electron thực tế không phụ thuộc vào nhiệt độ. Nhưng trong chất bán dẫn, sự gia tăng $T_e$ dưới tác dụng của điện trường có nghĩa là sự gia tăng tốc độ $v_0$ chuyển động nhiệt của các electron và do đó làm giảm thời gian chạy tự do. Nếu thay đổi $\Delta v_0$ về tốc độ $v_0$ là nhỏ, tức là $\Delta v_0\ll v_0$, thì $v_0$ phụ thuộc vào $E$, và do đó, $\tau$ trên $E$ có thể bị bỏ qua. Điều kiện $\Delta v_0\ll v_0$ tương đương với điều kiện quá nhiệt nhỏ $\Delta T_e$ của các electron so với trạng thái cân bằng:

$$\Delta T_e\ll T_e.$$

Do đó, các điều kiện để thời gian tích điện tự do độc lập với độ lớn của điện trường, cần thiết để đáp ứng định luật Ohm, đặt ra những hạn chế sau đây đối với phạm vi áp dụng định luật này:

$$u \ll v_0,$$

$$u < v_{3B},$$

$$\Delta T_e\ll T_e=T_c.$$

Vi phạm bất kỳ tính độc lập nào đều dẫn đến sai lệch khỏi định luật Ohm. Dưới đây chúng ta sẽ thấy rằng nếu tính độc lập của $u \ll v_0$ và $\Delta T_e\ll T_e$ bị vi phạm, thì điện trường $E$ cũng có thể ảnh hưởng đến các đại lượng khác có trong công thức Drude - khối lượng hiệu dụng $m^*$ và nồng độ electron $n$. Sự phụ thuộc của $m^*$ và $n$ vào $E$ có thể thay đổi đáng kể loại đặc tính dòng điện-điện áp của chất bán dẫn.

Chất bán dẫn trong điện trường mạnh

Trong một mẫu có dòng điện $I$ chạy qua, năng lượng được giải phóng

$$P=I^2R=\sigma E^2LS$$

(chúng tôi đã dạy rằng $I=jS=\sigma ES$, $R=\varrho L/S=L/\sigma S$). Công suất $Q=\sigma E^2$ được giải phóng trên mỗi đơn vị thể tích. Với cùng một giá trị $Q$, điện trường $E=$ $\sqrt{Q/\sigma}$ trong chất bán dẫn lớn hơn trong kim loại, vì nồng độ electron trong chất bán dẫn và do đó độ dẫn điện $\sigma$ thấp hơn nhiều. Do đó, việc vi phạm các điều kiện $u<v_{3B}$, $u\ll v_0$ trong đó sẽ dễ dàng hơn. Ngoài ra, đối với mỗi electron trong chất bán dẫn có nhiều năng lượng hơn trong kim loại. Khí điện tử nóng lên chậm hơn, và do đó tính độc lập $\Delta T_e\ll T_e$ cũng dễ bị vi phạm hơn.

Vi phạm điều kiện nào - (1), (2) hoặc (3) - khi điện trường tăng sẽ dẫn đến sai lệch đáng kể nhất so với định luật Ohm tùy thuộc vào loại chất bán dẫn. Ví dụ: trong CdS, điều kiện $u<v_{3B}$ bị vi phạm trước tiên. Đồng thời, trong hiện trường $E_{3B}=1,4\cdot 10^5$ V/m trên vôn-ampe

⟦folio 6⟧

Trong đặc tính mới $j(E)$ một đường gấp khúc xuất hiện (hình 2). Nếu $E > E_{3B}$, chất bán dẫn này phát ra âm thanh cường độ cao và có thể được sử dụng làm máy tạo rung động âm thanh.

Trong các chất bán dẫn khác, chẳng hạn như Ge, Si, GaAs, InP, CdTe, âm thanh bị kích thích yếu hơn nhiều và không quan sát thấy hiện tượng xoắn nào đáng chú ý trong trường $E_{3B}$. Trong các chất bán dẫn này, những sai lệch so với định luật Ohm có liên quan đến việc vi phạm điều kiện $\Delta T_e \ll T_e$. Trong trường hợp này, thời gian beta miễn phí tỷ lệ nghịch với trường $E$, tức là $\tau(E) \sim 1/E$, và phụ thuộc vào mật độ hiện tại và chỉ liên quan đến những thay đổi trong $m^*$ và $n$. Trong Ge và Si ở $E > 10^6$ V/m trên đặc tính dòng điện-điện áp (hình 3) độ bão hòa $j(m^*, n)$ được quan sát thấy, không phụ thuộc vào $E$. Trong GaAs, InP, CdTe, khi năng lượng electron tăng khi tăng $E$, không chỉ thời gian của hạt tự do $\tau$ giảm mà khối lượng hiệu dụng $m^*$ cũng tăng. Sự tăng $m^*$ gây ra sự thay đổi trong tương tác của các electron với mạng tinh thể. Kết quả là, trong các chất bán dẫn này, bắt đầu từ một giá trị nhất định của điện trường $E_a$, mật độ dòng điện $j$ giảm khi tăng $E$ (phần $E_a < E < E_b$ đến hình 3). Trong GaAs, mức giảm $j$ bắt đầu ở $E_a = 3,2 \cdot 10^5$ V/m và tiếp tục đến $E_b \approx 10$ $E_a$. Trong trường $E_a$ tốc độ trôi của electron là $u = j/en = 1,5 \times 10^5$ m/s.

Trong trường mạnh hơn nữa $E \sim 10^7$ V/m chúng ta vi phạm điều kiện $\Delta T_e \ll T_e$ và điều kiện $u \ll v_0$ cũng bị vi phạm. Trong một trường như vậy, các electron nhận được năng lượng trong quá trình chạy tự do, đủ để hiểu được nguyên tử. Các electron nhanh, khi va chạm với các nguyên tử, đánh bật các electron bổ sung, do đó cũng được gia tốc bởi trường và tạo ra các hạt mang điện mới. Quá trình này được gọi là tác động vào. Tổng nồng độ của $n$ electron tăng lên và do đó độ dẫn điện tăng lên. Với mức tăng điện trường thậm chí còn lớn hơn $(E > 10^7$ V/m), nồng độ và độ dẫn điện tăng lên như một trận tuyết lở và xảy ra hiện tượng đánh thủng chất bán dẫn.

Như vậy, trong chất bán dẫn ở trường rất mạnh $E$ mật độ dòng điện $j = \sigma E$ tăng nhanh hơn theo định luật tuyến tính. Đặc biệt, trong Ge và Si, độ bão hòa dòng điện được thay thế bằng sự tăng trưởng không bị bẫy của nó, và trong GaAs, InP, CdTe, đặc tính dòng điện-điện áp có dạng hình $N$ (hình 3); tại $0 < E < E_a$ định luật Ohm được thỏa mãn, trong khoảng $E_a < E < E_b$ có phần rơi xuống do sự giảm $\tau$ và sự tăng $m^*$ trong điện trường mạnh, và cuối cùng, trong vùng $E > E_b$ có sự tăng nhanh của $j$ do sự tăng lên của $n$.

Hiệu ứng súng

Sự có mặt của phần rơi trong đặc tính dòng điện-điện áp dẫn đến một hiện tượng thú vị được phát hiện bởi kỹ sư người Mỹ John Gunn.

Chúng ta hãy áp dụng hướng $U_0$ cho mẫu GaAs có độ dài $L$ sao cho nó kết thúc ở phần rơi của sự phụ thuộc $j(E)$. Giả sử ban đầu điện trường trong mẫu đều và bằng $U_0/L$. Vì lý do nào đó, trong lớp mỏng $AB$ của mẫu, trường $E$ hóa ra lớn hơn một chút so với phần còn lại của thể tích mẫu (hình 4). Khi đó tốc độ trôi của các electron $u = j/en$ bên trong lớp $AB$ hóa ra nhỏ hơn bên ngoài. Do đó, nhiều electron sẽ chảy đến ranh giới $A$ hơn là bay ra khỏi ranh giới đó và tại ranh giới $B$ sẽ có một dòng electron dương. Do đó, một điện trường bổ sung sẽ xuất hiện trong lớp $AB$, hướng cùng hướng với lớp ban đầu. Tăng

⟦folio 7⟧

Trường giảm sẽ dẫn đến thực tế là tốc độ hiệu dụng của electron bên trong lớp sẽ giảm hơn nữa và trường ở đó sẽ còn tăng hơn nữa.

Do đó, sự phân bố đồng đều của điện trường trong phần tới $j(E)$ là không thể: mọi sự không đồng nhất $E$ dù yếu đến đâu vô tình xuất hiện trong mẫu cũng không giải quyết được mà ngày càng lớn lên. Kết quả là hình thành một vùng hẹp (kích thước $\delta$) của trường mạnh, được gọi là miền điện. Trong trường hợp này, vì điện áp $U_0$ trên mẫu được chỉ định, tức là.

$$E_2\delta + E_1(L-\delta) = U_0 = \text{const},$$

sự gia tăng trường $E_2$ trong miền điện trở bằng cách giảm trường $E_1$ bên ngoài miền đó. Sẽ đến lúc $E_1 < E_a$ và $E_2 > E_b$ (xem hình 3). Tốc độ hoạt động bên trong miền bắt đầu giảm và tốc độ bên trong bắt đầu tăng. Sự tăng trưởng của trường $E_2$ trong miền sẽ dừng khi các tỷ lệ này trở nên bằng nhau và mật độ hiện tại trong miền và trong mẫu trở nên giống nhau:

$$j(E_1) = j(E_2) = j_0.$$

Từ hai đẳng thức cuối cùng, ta suy ra rằng mật độ dòng điện $j_0$ được thiết lập trong mẫu phụ thuộc vào độ dày của miền $\delta$.

Thông thường, một miền phát sinh gần cực dương (do sự nóng chảy của các tiếp điểm nên có sự không đồng nhất lớn ở đây) và bị dòng điện bên trong mang đi, bắt đầu di chuyển về phía cực dương với tốc độ $u_0 = j_0/en$. Khi nó di chuyển dọc theo mẫu, kích thước của nó không thay đổi, điều đó có nghĩa là dòng điện $j_0$ cũng không thay đổi. Gần cực dương, miền bắt đầu biến mất, độ dày của nó giảm và dòng điện trong mẫu tăng lên. Tuy nhiên, trường $E_1$ bên ngoài miền tạm thời được tăng lên. Càng sớm càng

$$E_1$$ đạt giá trị $E_a$, tại đó một miền mới được sinh ra, dòng điện bắt đầu giảm và quá trình cổ tử cung này được lặp lại (hình 5). Chu kì của dòng điện bóng đèn trong mẫu là $T_0 = L/u_0$.

Vì vậy, bằng cách đặt một điện áp không đổi $U_0$ vào chất bán dẫn, chúng ta thu được dòng điện xoay chiều có tần số $f = 1/T_0 = u_0/L$. Điều này hoàn toàn khác với định luật Ohm. Trong arsenua galley (GaAs) $u_0 \approx 10^5$ m/s. Sử dụng các mẫu nhỏ có chiều dài từ một đến stapicron, có thể thay đổi tần số của dòng điện xoay chiều trong phạm vi $f \sim 10^9 - 10^{11}$ Hz. Hầu hết các máy phát tần số siêu cao (vi sóng) hiện đại đều hoạt động dựa trên hiệu ứng Gunn. Ví dụ, những thiết bị này được sử dụng để xác định tốc độ không đổi của chuyển động tự động và trong việc phát sóng truyền hình qua các vệ tinh nhân tạo của Trái đất.

**Vi phạm định luật Ohm**

ở dòng điện cao

Cho đến nay, chúng ta xét chuyển động của các electron bên trong chỉ dưới tác dụng của điện trường. Tuy nhiên, người ta biết rằng dòng điện chạy qua dây dẫn là nguồn tạo ra từ trường. một từ trường sẽ xuất hiện không chỉ ở bên ngoài mà còn ở bên trong dây dẫn. Ví dụ, ở gần bề mặt của một sợi dây thẳng có đường kính $d = 1$ mm với dòng điện $I = 10$ A, một từ trường $B = 4\mu_0I/d \approx 0,012$ T sẽ xuất hiện ($\mu_0 = 4 \cdot 10^{-7}$ B·s/(A·m) – hằng số từ). Từ trường của dòng điện có thể vi phạm định luật Ohm.

Một electron chuyển động trong từ trường chịu tác dụng của lực Lorentz,

⟦folio 8⟧

Hình 6.
uốn cong quỹ đạo của nó. Nếu cảm ứng trường $\vec{B}$ vuông góc với tốc độ $\vec{v}$ của electron thì quỹ đạo của electron sẽ là một đường tròn có bán kính $r=m^*v/eB$. Nếu góc giữa các vectơ $\vec{B}$ và $\vec{v}$ bằng $\alpha$ thì electron sẽ chuyển động theo một đường xoắn ốc có đường kính là $d=2(m^*v/eB)\sin \alpha$, hát một vòng xoắn ốc trong thời gian $T=2\pi m^*/eB$.

Trong một dây dẫn, electron có thể chuyển động theo hình xoắn ốc nếu thời gian chạy tự do là $\tau \gg T$ (hình 6, a). Trong trường hợp này, đường kính của hình xoắn ốc $d<vT$ nhỏ hơn nhiều lần so với khoảng cách $l=v\tau$ mà electron sẽ trộn lẫn trong thời gian $\tau$ khi không có từ trường (hình 6, b). Do đó, trong thời gian $\tau$, electron dường như bị khóa trong một ống có đường kính $d$. Kết quả là điện trở của dây dẫn trong từ trường lớn hơn $B=0$. Sự phụ thuộc của điện trở $R$ vào từ trường do dòng điện “riêng” tạo ra, do đó dẫn đến vi phạm định luật Ohm.

Nếu $\tau \ll T$, thì giữa hai lần va chạm liên tiếp, chuyển động của electron khác một chút so với chuyển động thẳng (hình 6, s); Từ trường thực tế không nhỏ hơn điện trở của dây dẫn.

Cảm ứng từ trường $B_0$, từ đó ảnh hưởng của trường trở nên đáng kể, được tìm thấy từ

Hình 7.

điều kiện bằng nhau về chu kỳ quay của electron trong quỹ đạo tròn $T=2\pi m^*/eB_0$ thời gian beta tự do $\tau: B_0=2\pi m^*/e\tau$. Đối với GaAs $m^*=0,06$ $m_e$ và $\tau \sim 10^{-13}$ s, vì vậy $B_0 \approx 3$ T. Trên thực tế, không thể tạo ra một trường như vậy bằng cách cho dòng điện chạy qua chất bán dẫn. Ở dòng điện rất thấp, mẫu sẽ bị phá hủy. Một kim loại có độ dẫn điện rất cao có thể mang dòng điện lớn hơn nhiều. Ngoài ra, ở kim loại nguyên chất được làm lạnh đến nhiệt độ gel lỏng (khoảng 4 K), thời gian $\tau$ có thể đạt giá trị $\sim 10^{-9}$ s, dài hơn đáng kể so với trong chất bán dẫn. Do đó, trong kim loại, trường $B_0$ nhỏ - khoảng 0,01 T. Đây là một ví dụ về loại trường xảy ra trong một dây dẫn có đường kính 1 mm ở dòng điện 10 A.

hình 7 cho thấy sự phụ thuộc thực nghiệm thu được của điện trở $R$ của một dây dẫn kim loại vào giá trị hiện tại $I$ ở nhiệt độ gel. Có thể thấy khi dòng điện tăng thì điện trở tăng lên nhiều lần. Điện trường trong thí nghiệm này nhỏ hơn $10^2$ V/m, nhỏ hơn nhiều so với các trường $E$ trong đó người ta quan sát thấy những sai lệch so với định luật Ohm trong chất bán dẫn. Do đó, ảnh hưởng của từ trường của dòng điện lên điện trở trong trường hợp này là nguyên nhân chính dẫn đến vi phạm định luật Ohm.

***

Chúng ta đã xem xét các nguyên tắc vật lý có thể dẫn đến sự vi phạm định luật Ohm ở chất dẫn điện. Đồng thời, những hiệu ứng quan trọng nhất không đạt được ở các vật dẫn nằm trong điện trường và từ trường xen kẽ cũng không được đề cập... Nhưng “không ai có thể chấp nhận được sự bao la”.
