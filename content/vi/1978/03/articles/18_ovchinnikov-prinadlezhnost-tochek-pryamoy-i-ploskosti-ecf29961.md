---
id: 1978-3-ovchinnikov-prinadlezhnost-tochek-pryamoy-i-ploskosti-ecf29961
issue: kvant_1978_3
year: 1978
number: "3"
title: Điểm thuộc một đường thẳng và một mặt phẳng
authors:
  - Овчинников С. В.
rubric: raznoe
rubric_sub: Разное
page_first: 50
page_last: 55
page_labels: 48, 49, 50, 52, 53
tag: XKRD
lang: vi
source: kvant_digital
extraction: vision
content_sha256: 4ea48838d2019b05bb55c5a8131dbbb6412459e43096e59dc1ffe89ab1157984
prompt_sha256: draft-1
translated_from: content/ru/1978/03/articles/18_ovchinnikov-prinadlezhnost-tochek-pryamoy-i-ploskosti-ecf29961.md
source_content_sha256: 54ea9db5ca115c0ddf6ffd234d0543994b2bd479195c299b96a36a292ccb3beb
translation_model: draft
translation_run: vi-draft-2026-10-31
translation_quality: draft
---

⟦folio 48⟧

S. Ovchinnikov

Điểm thuộc một đường thẳng và một mặt phẳng

Đối với lời giải hình học bài toán người ta thường sử dụng điều kiện là các điểm thuộc đường thẳng hoặc mặt phẳng. Việc sử dụng vectơ cho phép chúng ta viết các điều kiện này ở dạng đơn giản và nhỏ gọn. Đồng thời, trong lời giải bài toán thường không cần đến những công trình xây dựng bổ sung khá xảo quyệt.

Trong lưu ý này, chúng ta sẽ rút ra các điều kiện để các điểm thuộc một đường thẳng và một mặt phẳng, đồng thời xem xét các ví dụ về ứng dụng của chúng. Hãy bắt đầu với lời giải tiếp theo bài toán.

Bài toán 1 (Khoa Kinh tế, Đại học Tổng hợp Matxcơva, 1975). Cho tam giác ABC. Trên cạnh AB và BC lần lượt lấy điểm M và N; $|AB| = 5|AM|$, $|BC| = 3|BN|$. Đoạn thẳng AN và CM cắt nhau tại điểm O. Tìm tỉ số diện tích của các tam giác AOC và ABC.

Lời giải (Hình 1). Bởi vì

$$\frac{S_{AOC}}{S_{ABC}} = \frac{S_{AMC}}{S_{ABC}} \cdot \frac{S_{AOC}}{S_{AMC}} = \frac{|AM|}{|AB|} \cdot \frac{|OC|}{|MC|} = \frac{1}{5} \cdot \frac{|OC|}{|MC|},$$

Chúng ta chỉ cần xác định điểm O chia đoạn MC theo tỉ số nào là đủ. Hãy vẽ ME, $E \in [BC]$, song song với AN; thì $\frac{|EN|}{|BN|} = \frac{|AM|}{|AB|} = \frac{1}{5}$.

Nhưng $|BN| = \frac{1}{3}|BC|$, $|EN| = \frac{1}{15}|BC|$ đến từ đâu. Kế tiếp,

$$\frac{|OC|}{|MC|} = \frac{|NC|}{|EC|} = \frac{2/3|BC|}{2/3|BC| + 1/15|BC|} = \frac{10}{11}.$$

Có nghĩa,

$$\frac{S_{AOC}}{S_{ABC}} = \frac{1}{5} \cdot \frac{10}{11} = \frac{2}{11}.$$

Lưu ý rằng phần lớn người nộp đơn không thể tìm ra cách xây dựng bổ sung ME || AN và do đó đã không giải quyết được điều này bài toán.

Xét lời giải khác dựa trên kết quả bài toán 254 của sách giáo khoa Hình học 9. Chúng ta hãy xây dựng kết quả này như sau:

Định lý 1. Với mọi cách chọn điểm O, đẳng thức

$$\overrightarrow{OC} = \alpha \overrightarrow{OA} + (1 - \alpha) \overrightarrow{OB}$$

(1)

đối với một số α điều cần thiết và đủ điều kiện là các điểm A, B và C ($A \neq B$) thuộc cùng một đường thẳng. Đồng thời $\overrightarrow{BC} = \alpha \overrightarrow{BA}$.

Hình 1.

Hình 2.

⟦folio 49⟧

Hình 2 minh họa Định lý 1. Lưu ý rằng giá trị của hệ số $\alpha$ xác định vị trí của điểm trên đường $(AB)$. Nếu $0 \leqslant \alpha \leqslant 1$ thì điểm $C$ nằm giữa $A$ và $B$; nếu $\alpha > 1$ thì điểm $A$ nằm giữa $C$ và $B$ và cuối cùng, nếu $\alpha < 0$ thì điểm $B$ nằm giữa $A$ và $C$. Hệ số $\alpha$ đóng vai trò nhận biết tọa độ trên đường thẳng $(AB)$: gốc tọa độ là điểm $B$ và thang đo được cho bởi đoạn $BA$ sao cho điểm $A$ có tọa độ một.

Hãy quay lại bài toán 1 và biểu thị $\overrightarrow{BA} = \vec{p}$ và $\overrightarrow{BC} = \vec{q}$. Sau đó $\overrightarrow{BM} = \frac{4}{5} \vec{p}$ và $\overrightarrow{BN} = \frac{1}{3} \vec{q}$. Vì điểm $O$ thuộc các đường thẳng $AN$ và $CM$ nên
$$\overrightarrow{BO} = \alpha_1 \overrightarrow{BM} + (1 - \alpha_1) \overrightarrow{BC} = \alpha_2 \overrightarrow{BA} + (1 - \alpha_2) \overrightarrow{BN},$$
tức là
$$\frac{4}{5} \alpha_1 \vec{p} + (1 - \alpha_1) \vec{q} = \alpha_2 \vec{p} + \frac{1}{3} (1 - \alpha_2) \vec{q},$$
Ở đâu
$$\begin{cases} \frac{4}{5} \alpha_1 = \alpha_2, \\ 1 - \alpha_1 = \frac{1}{3} (1 - \alpha_2). \end{cases}$$
Giải hệ thu được, ta tìm được $\alpha_1 = \frac{10}{11}, \alpha_2 = \frac{8}{11}$. Theo Định lý 1
$$\overrightarrow{CO} = \alpha_1 \overrightarrow{CM} = \frac{10}{11} \overrightarrow{CM},$$
Ở đâu

Hình 3.

Hình 4.

⟦folio 50⟧

$$= \frac{10}{3}.$$ Ký hiệu $BCD$ bằng φ, từ tam giác $ECF$ ta tìm được $\cos \varphi = \frac{1}{10}$ bằng cách sử dụng định lý cosine. Cho giá trị của cosф, chúng ta tính các đường chéo $|AC| = \sqrt{45}$ và $|BD| = \sqrt{37}$ bằng định lý cosine.

Bài toán 3*). Cho một hình tam giác $ABC$ và một điểm $M$ trên cạnh $BC$. Chứng minh rằng $|AM| \cdot |BC| \leq |AB| \cdot |MC| + |AC| \cdot |BM|$.

Lời giải (Hình 4). Chúng tôi có $\overrightarrow{AM} = \alpha \overrightarrow{AB} + (1-\alpha) \overrightarrow{AC}$.

Vì $\alpha = \frac{|MC|}{|BC|}$, nên $1-\alpha = \frac{|BM|}{|BC|}$. Tiếp theo, $\left| \overrightarrow{AM} \right| = \left| \alpha \overrightarrow{AB} + (1-\alpha) \overrightarrow{AC} \right| \leq \alpha \left| \overrightarrow{AB} \right| + (1-\alpha) \left| \overrightarrow{AC} \right| = \frac{|MC|}{|BC|} \cdot |AB| + \frac{|BM|}{|BC|} \cdot |AC|$, từ đó phát biểu bài toán.

Định lý 1 cho phép khái quát hóa sau đây cho trường hợp không gian.

Định lý 2. Cho $A, B$ và $C$ là các điểm phân biệt theo từng cặp không nằm trên cùng một đường thẳng. Với mọi lựa chọn điểm $O$ đẳng thức
$$\overrightarrow{OD} = \alpha \overrightarrow{OA} + \beta \overrightarrow{OB} + (1-\alpha-\beta) \overrightarrow{OC} \text{ является необходимым и достаточно условием принадлежности точки } A, B, C \text{ и } D \text{ одной плоскости}.$$
Chứng minh 1) Tính đầy đủ. Giả sử (2) được thỏa mãn. Chúng tôi tìm thấy $\overrightarrow{OD} - \overrightarrow{OC} = \alpha (\overrightarrow{OA}-\overrightarrow{OC}) + \beta (\overrightarrow{OB}-\overrightarrow{OC})$, từ đâu $\overrightarrow{CD} = \alpha \overrightarrow{CA} + \beta \overrightarrow{CB}$. Do đó, các vectơ $\overrightarrow{CA}, \overrightarrow{CB}$ và $\overrightarrow{CD}$ là đồng phẳng và do đó, các điểm $A, B, C$ và $D$ thuộc cùng một mặt phẳng.

2) Sự cần thiết. Nếu $A, B, C$ và $D$ thuộc cùng một mặt phẳng thì các vectơ $\overrightarrow{CA}, \overrightarrow{CB}$ và $\overrightarrow{CD}$ là đồng phẳng. Vì các điểm $A, B$ và $C$ phân biệt theo từng cặp và không nằm trên cùng một đường thẳng nên các vectơ $\overrightarrow{CA}$ và $\overrightarrow{CB}$ không thẳng hàng.

*) bài toán này được đề xuất bởi I. Sharygin.

Hình 5.

⟦folio 52⟧

Trừ thể tích của kim tự tháp $LAFN$ và $DB_1KM$. Gọi $V$ là thể tích của lăng kính. Từ các tính toán trước đây, chúng ta biết sự tương ứng giữa các độ cao $|LA_1|$, $|DB_1|$, $|LA|$ của các kim tự tháp $LA_1EM$, $LAFN$, $DB_1KM$ và chiều cao của lăng kính, cũng như sự tương ứng giữa các diện tích của các đáy. Điều này giúp bạn dễ dàng tìm thấy $V_{LA_1EM} = \frac{3}{8}V$, $V_{LAFN} = \frac{1}{72}V$ và $V_{MKB_1D} = \frac{1}{48}V$, từ đó thể tích của khối đa diện $AEKB_1DNAF$ bằng $\frac{3}{8}V - \frac{1}{72}V - \frac{1}{48}V = \frac{49}{144}V$. Vì vậy, mặt phẳng cắt chia thể tích của lăng kính theo tỷ lệ 49:95.

Trước tiên, hãy lưu ý rằng trong lời giải của chúng tôi, điều kiện lăng kính đúng không được sử dụng ở bất kỳ đâu. Thứ hai, phương pháp lời giải của chúng tôi cũng phù hợp trong trường hợp các điểm $E$ và $N$ không phải là trung điểm của các cạnh $A_1C_1$ và $AB$, trong khi lời giải với các cấu trúc bổ sung *) sử dụng đáng kể trường hợp này (prima $EP$ cắt $BB_1$ tại điểm $D$ vì $|A_1E| = |EC_1|$).

Một độc giả chú ý có thể đã nhận thấy khi so sánh Định lý 1 và Định lý 2 rằng trong Định lý 1, hệ số $\alpha$ chỉ đơn giản là dado có nguồn gốc hình học, trong khi ý nghĩa hình học của các hệ số $\alpha$ và $\beta$ trong Định lý 2 vẫn chưa rõ ràng. Chúng tôi đã tận dụng khoảng trống này trong một trường hợp cụ thể quan trọng, để lại cho người đọc phần khái quát hóa.

Định lý 3. Nếu theo điều kiện của Định lý 2, điểm $D$ nằm trong tam giác $ABC$ thì từ đẳng thức
$$\overrightarrow{OD} = \alpha \overrightarrow{OA} + \beta \overrightarrow{OB} + (1 - \alpha - \beta) \overrightarrow{OC} \text{ следует}$$
$$\begin{cases} \alpha = S_{BDC}: S_{ABC}, \\ \beta = S_{ADC}: S_{ABC}, \\ 1 - \alpha - \beta = S_{ADB}: S_{ABC}. \end{cases}$$

*) So sánh lời giải của bài toán này với điều được đưa ra trong cuốn sách của G.V. Dorofeev, M.K. Potapov, N.Kh. Rozov “Sổ tay toán học để xây dựng bài toán”, Moscow, 1976, phần 3, § 6, bài toán 7 (tr. 514).

⟦folio 53⟧

Hình 8.

Chứng minh (Hình 8). Như sau từ chứng minh Định lý 2 $\vec{CD} = \alpha \vec{CA} + \beta \vec{CB}$. Hãy đặt $\vec{CK} = \alpha \vec{CA}$, $\vec{CL} = \beta \vec{CB}$. Từ Hình 8 có thể thấy rằng $S_{ADC} : S_{ABC} = \beta$ và $S_{BDC} : S_{ABC} = \alpha$. Từ những đẳng thức này dễ dàng suy ra $S_{ADB} : S_{ABC} = 1 - \alpha - \beta$.

Nhiệm vụ và

1. (Geofak, Đại học quốc gia Mátxcơva, 1966). Điểm $K$ chia đường trung tuyến $AD$ của tam giác $ABC$ theo tỷ lệ 3:1, tính từ đỉnh. Đường thẳng $BK$ chia mặt phẳng của tam giác $ABC$ theo tỷ lệ nào?

2. (Geofak, Đại học quốc gia Mátxcơva, 1974). Cho một đường thẳng tứ giác đều $PABCD$ có đỉnh $P$. Trên các cạnh $PA$ và $PC$ lần lượt lấy các điểm $K$ và $M$ và $|AK| : |KP| = 1:3$, $|CM| = |PM|$. Tìm tỉ lệ mà cạnh $PB$ được chia cho mặt phẳng vẽ qua các điểm $D$, $K$ và $M$.

3. (Khoa Hóa học, Đại học Tổng hợp Matxcova, 1970). Mặt phẳng đi qua đỉnh $A$ của đáy của đường thẳng tam giác $SABC$, chia đôi đường trung tuyến $SK$ của tam giác $SAB$ và cắt đường trung bình $SL$ của tam giác $SAC$ tại điểm $D$ sao cho $|SD| = \frac{1}{2} |DL|$. Mặt phẳng này chia thể tích của một đường thẳng theo tỉ lệ nào?

Sửa đổi. Có lỗi đánh máy trong điều kiện bài toán M483, mô tả bài toán «Kvant» («Kvant», 1978, Số 1). Dưới đây chúng tôi đặt điều kiện chính xác của bài toán này. Thời hạn gửi lời giải được kéo dài đến ngày 1 tháng 5 năm 1978.

4. (Geofak, Đại học quốc gia Mátxcơva, 1976). Trong hình bình hành $ABCD$ có các đường chéo bằng $|AC| = 6$ và $|BD| = 24$, vẽ một đoạn $EF$ nối điểm $E$ của đường chéo $AC$ với điểm $F$ của cạnh $BC$. Điểm $E$ và $F$ được chọn sao cho $\frac{|FC|}{|BF|} = \frac{1}{2}, \frac{|EA|}{|EF|} = \frac{1}{3}$. Được biết, điểm $M$ giao điểm của đường chéo $BD$ với đoạn $EF$ chia nó theo tỷ lệ $\frac{|EM|}{|MF|} = \frac{1}{2}$. Tìm các cạnh của hình bình hành.

5. Cho một hình tam giác $ABC$. Ở bên $AB$ chúng ta lấy điểm $D$, và ở bên $BC$ chúng ta lấy điểm $E$ và $F$ sao cho $|AD| : |DB| = 3:2, |BE| : |EC| = 1:3$ và $|BF| : |FC| = 4:1$. Đường $(AE)$ chia đoạn $DF$ theo tỷ lệ nào?

6. (Mekhmat, Đại học quốc gia Mátxcơva, 1964). Cho một khối lập phương $ABCDA_1B_1C_1D_1$, trong đó $AA_1, BB_1, CC_1, DD_1$ là các cạnh bên. Thể tích của hình lập phương chia cho mặt phẳng đi qua đỉnh $A$, giữa cạnh $BC$ và tâm của mặt $DCC_1D_1$ theo tỷ lệ nào?

7. (Mekhmat, Đại học quốc gia Mátxcơva, 1965). Cho một đường thẳng tứ giác đều $SABCD$ có đỉnh $S$. Một mặt phẳng được vẽ đi qua trung điểm của các cạnh $AB, AD$ và $CS$. Mặt phẳng này chia thể tích của một đường thẳng theo tỉ lệ nào?

8. Bên trong tam giác $ABC$ lấy điểm $O$. Các đường $(AO), (BO)$ và $(CO)$ lần lượt cắt các cạnh $BC$, $CA$ và $AB$ tại các điểm $P$, $Q$ và $R$. Chứng minh rằng

$$\frac{|AR|}{|RB|} \cdot \frac{|BP|}{|PC|} \cdot \frac{|CQ|}{|QA|} = 1.$$

9. Điểm $P$ và $Q$ chia hai cạnh $BC$ và $CA$ của tam giác $ABC$ theo tỉ số đã cho:

$$\frac{|BP|}{|PC|} = a, \quad \frac{|CQ|}{|QA|} = b.$$

Gọi $O$ là giao điểm của đường $AP$ và $BQ$. Tìm tỉ số của tứ giác phẳng $OPCQ$ với tam giác phẳng $ABC$.

10. Giả sử $OABC$ là một đường thẳng tam giác có đỉnh $O$ và $M$ một điểm bên trong tam giác $ABC$. Sau đó

$$|OM| \cdot S_{ABC} \leq |OA| \cdot S_{MBC} + |OB| \cdot S_{MAC} + |OC| \cdot S_{MAB}.$$

M483. a) Chứng minh rằng tỉ số giữa bình phương bán kính đường tròn nội tiếp của một tam giác vuông với tổng bình phương độ dài các đường trung tuyến vẽ từ các góc nhọn không vượt quá 1/20.

6) Ý nghĩa quan trọng nhất mà mối quan hệ này có thể mang lại là gì?
