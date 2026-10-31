---
id: 1975-12-myakishev-raschet-uchastka-tsepi-soderzhaschego-e-d-s-61096a5a
issue: kvant_1975_12
year: 1975
number: "12"
title: Tính tiết diện của chuỗi chứa e. d.s.
authors:
  - Мякишев Г. Я.
rubric: raznoe
rubric_sub: Разное
page_first: 53
page_last: 57
page_labels: 51-55
tag: 0F4U
lang: vi
source: kvant_digital
extraction: vision
content_sha256: 356b31a1d34cf15f2ffa956845b4cce769a4f5218873a619480721e4cff915d4
prompt_sha256: draft-1
translated_from: content/ru/1975/12/articles/13_myakishev-raschet-uchastka-tsepi-soderzhaschego-e-d-s-61096a5a.md
source_content_sha256: 0de92004627975980e0b312f023aec141743f47116a37834d176310f2761364b
translation_model: draft
translation_run: vi-draft-2026-10-31
translation_quality: draft
---

⟦folio 51⟧

G. Vâng. Myakitsev

Tính toán phần mạch chứa E.M.S.

Khó khăn lớn nhất với lời giải bài toán đối với dòng điện tích hợp phát sinh khi có nguồn dòng điện trong phần mạch được xem xét ở bài toán.

định luật Ohm

Nếu một đoạn mạch chỉ chứa điện trở tổng $R$ thì định luật Ohm có dạng sau:

$$I = \frac{U}{R}$$

(1)

Sai lầm nghiêm trọng nhất nhưng khá phổ biến là định luật này được sử dụng để tìm cường độ dòng điện trong một đoạn mạch chứa nguồn dòng điện, hay nói cách khác là E. M. S. Trên thực tế, cường độ dòng điện trong đoạn đó không chỉ phụ thuộc vào điện áp $U_{12}$ ở hai đầu đoạn (1 - điểm đầu, 2 - điểm cuối của đoạn đó), mà còn phụ thuộc vào E. M. S. €:

$$I = \frac{U_{12} + €}{r}$$

(2)

(r là điện trở trong của nguồn dòng).

Đây là định luật Ohm cho đoạn mạch chứa E.M.F.

Các đại lượng có trong công thức (2): dòng điện $I$, điện áp $U_{12}$ và E.M.S. € là đại số, tức là chúng có thể vừa dương vừa âm. Chỉ có mức kháng cự $r$ là luôn dương. Nguồn sai sót chính khi sử dụng định luật này là việc chọn sai dấu của một đại lượng cụ thể. Để tránh sai sót khi đặt biển báo, bạn phải tuân thủ các quy tắc chung có giá trị trong mọi trường hợp không có ngoại lệ.

Trước tiên, bạn cần chọn hướng di chuyển dương (tùy ý) trong vòng lặp. Cường độ dòng điện trong khu vực đang xem xét sẽ dương nếu hướng của dòng điện (tức là hướng chuyển động của các điện tích dương) trùng với hướng đã chọn *. E.m.f. sẽ dương nếu công thực hiện để di chuyển một điện tích dương trong một đoạn mạch cho trước là dương. (Trong trường hợp pin điện hoặc pin, E.M.F. sẽ dương nếu điện tích di chuyển bên trong nguồn điện cực âm sang nguồn điện cực dương). Cuối cùng, dưới điện áp $U_{12}$ trên một đoạn mạch, người ta phải nhớ hiệu điện thế giữa 2 điểm đầu và 2 điểm cuối của đoạn đó: $U_{12} = \varphi_1 - \varphi_2$.

Để hiểu rõ hơn ý nghĩa của công thức (2), chúng ta hãy xem xét chi tiết hai ứng dụng:

*) Nếu không biết trước hướng của dòng điện (trước lời giải bài toán) thì có thể chọn tùy ý. Sau lời giải bài toán bạn nhận được giá trị hiện tại dương hoặc âm. Trong trường hợp đầu tiên, điều này có nghĩa là chúng ta đã chọn đúng hướng của dòng điện. Trong trường hợp thứ hai, hướng của dòng điện ngược với hướng đã chọn.

⟦folio 52⟧

⟦figure⟧
Hình 1.

biện pháp - xả và sạc pin.

XẢ NHƯ KUMULATOR. Trong Hình 1, khung chấm làm nổi bật phần mạch có e. d.s. Với hướng đã chọn của đường vòng ngược chiều kim đồng hồ $I>0$, $\mathscr{E}>0$ và $U_{12}<0$ (vì thế năng của điểm *1* - cực âm của pin nhỏ hơn thế năng của điểm *2* - cực dương), tức là lực điện thực hiện công âm \*). Do đó, phương trình (2) cho các mô-đun sẽ được viết như sau:

$$|I| = \frac{|\mathscr{E}| - |U_{12}|}{r},$$

hoặc

$$|U_{12}| = |\mathscr{E}| - |I|r.$$

---
\*) Nếu có các nguồn khác trong mạch đang được xem xét, được kết nối tương ứng, thì trường hợp $U_{12}>0$ có thể xảy ra.

⟦figure⟧
Hình 2.

⟦column⟧

⟦figure⟧
Hình 3.

Điện áp bằng e. d.s. nguồn trừ đi điện áp rơi trên điện trở tiết diện.

Cụ thể, công thức thu được cho thấy rằng đối với mạch hở ($I=0$) e. d.s. modulo bằng điện áp ở hai cực của nguồn dòng. Vì vậy e. d.s. có thể được đo bằng vôn kế nối với nguồn mạch hở. Bạn chỉ cần nhớ rằng sẽ có một số điểm không chính xác. Một vôn kế thông thường tuy có điện trở rất lớn nhưng vẫn không lớn vô hạn nên dòng điện chạy qua vôn kế và $Ir \neq 0$, do đó trên thực tế điện áp đo được nhỏ hơn e một chút. d.s.

SẠC K U M U L I T O R A. Mạch sạc pin như hình 2. Chúng ta chọn hướng đi vòng mạch theo chiều kim đồng hồ. Sau đó $I>0$, $U_{12}>0$, nhưng $\mathscr{E}<0$. Đồng thời

$$|I| = \frac{|U_{12}| - |\mathscr{E}|}{r}, \quad \text{или} \quad |U_{12}| = |\mathscr{E}| + |I|r.$$

Điện áp trên pin lớn hơn e. d.s. bởi lượng điện áp rơi trên điện trở trong của pin.

Bây giờ chúng ta hãy xem xét một số bài toán cụ thể.

Bài 1. *Hai phần tử có suất điện động là $\mathscr{E}_1 = 6$v và $\mathscr{E}_2 = 4$v và điện trở trong $r_1 = 0{,}25$ ohm và $r_2 = 0{,}75$ ohm,*

⟦figure⟧
Hình 4.

⟦figure⟧
Hình 5.

*được kết nối theo mạch hiển thị trong Hình 3. Hiệu điện thế giữa điểm 1 và điểm 2 là bao nhiêu? Bỏ qua điện trở của các dây nối.*

Chúng ta hãy đồng ý coi hướng di chuyển ngược chiều kim đồng hồ là dương. Đầy đủ e. d.s. mạch bằng $\mathscr{E} = |\mathscr{E}_1| - |\mathscr{E}_2|$ và cường độ dòng điện trong mạch

$$I = \frac{\mathscr{E}}{r_1 + r_2} = \frac{|\mathscr{E}_1| - |\mathscr{E}_2|}{r_1 + r_2}\ .$$

Định luật Ohm cho phần trên của chuỗi giữa các điểm *1* và *2* sẽ được viết là

$$U_{12} = Ir_1 - \mathscr{E}_1 = -\frac{|\mathscr{E}_1| r_2 + |\mathscr{E}_2| r_1}{r_1 + r_2} =$$
$$= -5,5\ в.$$

Dấu trừ cho biết thế năng của điểm *1* nhỏ hơn thế năng của điểm *2*.

Có thể thu được kết quả tương tự bằng cách áp dụng định luật Ohm cho phần dưới của mạch:

$$U_{21} = Ir_2 - \mathscr{E}_2 =$$
$$= \frac{|\mathscr{E}_1| r_2 + |\mathscr{E}_2| r_1}{r_1 + r_2} = 5,5\ в,$$

Nhiệm vụ 2. *Mô tả bằng đồ họa diễn biến gần đúng của điện thế dọc theo một mạch kín có phần tử điện như trong Hình 1.*

Ban đầu để mạch hở, sao cho cường độ dòng điện và điện áp ở mạch ngoài và bên trong nguồn giảm đi.

⟦column⟧

đều bằng không. Tại các ranh giới điện cực-điện phân trong nguồn, có các bước nhảy tiềm năng $\Delta U_1$ và $\Delta U_2$ (xem Hình 4). Tổng số lần nhảy này bằng e. d.s. phần tử: $\mathscr{E} = \Delta U_1 + \Delta U_2$.

Khi mạch đóng, điện thế nhảy ở ranh giới điện cực-điện phân không thay đổi. Nhưng điện thế của chất điện phân không còn không đổi mà giảm theo chiều dòng điện, tức là từ cực âm sang cực dương. Độ lớn điện áp rơi trên điện trở trong là $U_r = Ir$.

Hình 5 thể hiện biểu đồ gần đúng về phân bố điện thế trong mạch kín. Đoạn $AC$ mô tả điện thế của điện cực dương so với một số mức 0 được chọn tùy ý. Đoạn $BF$ tương ứng với điện thế của điện cực âm. Khoảng cách giữa các điện cực là $AB$. Các đoạn $AE$ và $BD$ là các điện thế gần điện cực dương và điện cực âm. Đường nghiêng $DE$ biểu thị độ sụt điện thế bên trong phần tử. Giá trị của nó $U_r$ được biểu thị bằng đoạn $DK$. Đường cong $CMF$ đưa ra ý tưởng về sự sụt giảm điện thế trong mạch ngoài qua điện trở $R$. Sự sụt giảm điện áp $U_R = IR$ này được biểu thị bằng đoạn đường $LF$. Các đoạn $CE = LK = \Delta U_1$ và $DF = \Delta U_2$ tương ứng với các bước nhảy vào

⟦folio 53⟧

⟦folio 54⟧

thế ở ranh giới điện cực-điện phân*).

Đường CMFDEC, mô tả đường đi của điện thế trong toàn bộ mạch, bị đóng. Điều này có nghĩa là tổng công của trường nhà máy điện trên một đường dẫn kín bằng không. Thật vậy, trường này thực hiện tác dụng dương trong các phần CMF và DE và tác dụng âm ở những nơi có tiềm năng nhảy lên (FD và EC). Trong giá trị tuyệt đối, công dương bằng công âm. Khi một đơn vị điện tích dương di chuyển dọc theo một chuỗi, công dương là $U_r + U_R = DK + LF$ và công âm là $\Delta U_1 + \Delta U_2 = \mathcal{E} = LK + DF$. Nhưng $DK + LF = LK + DF$, tức là $U_r + U_R = \mathcal{E}$, đại diện cho định luật Ohm cho toàn bộ mạch điện.

Câu hỏi có thể được đặt ra: nguyên nhân nào gây ra sự tỏa nhiệt trong mạch điện? Ở tất cả các khu vực, ngoại trừ ranh giới điện cực-điện phân, chỉ có lực của nhà máy điện tác động. Tại các ranh giới, nơi có những bước nhảy tiềm năng, cũng có các lực bên ngoài (trong trường hợp này là hóa học) tác dụng, và công âm của các lực nhà máy điện bằng công dương của các ngoại lực. Do đó, công dương của các lực nhà máy điện trong phần còn lại của mạch hóa ra không được bù. Do công việc này, nhiệt được giải phóng.

Hình 5 cho phép bạn tìm nguồn định luật Ohm cho đoạn chuỗi chứa e. d.s. Như có thể thấy trong hình, mô hình hướng là $|U_R| = LF = LK - FK = LK - (DK - DF) = (LK + DF) - DK = |\mathcal{E}| - |I|r$, tức là hướng tại các đầu nguồn bằng e. d.s. trừ đi độ dốc của hướng của nguồn bên trong.

*) Hình 5 biểu diễn trường hợp khi bước nhảy điện thế CE lớn hơn bước nhảy điện thế DF. Tất nhiên, trường hợp ngược lại cũng có thể xảy ra.

Nguồn điện hiện tại

Theo định nghĩa, cường độ dòng điện trong đoạn mạch 1-2 bằng

$$P = IU_{12}.$$

Công thức này có giá trị cho bất kỳ phần nào của mạch điện (sau đây có chứa nguồn dòng điện). Các biểu thức khác cho sức mạnh:

$$P = I^2R \text{ и } P = \frac{U_{12}^2}{R}$$

chỉ thích hợp cho một khu vực đồng nhất có tổng điện trở $R$. Tuy nhiên, lỗi thường xảy ra khi viết công thức (4) cho phần chứa e. d.s.

Chúng ta hãy chú ý đến một đặc điểm nữa của phần mạch có nguồn dòng điện. Đối với một diện tích đồng nhất, công suất luôn dương (thực tế là $P = I^2R > 0$). Năng lượng đến khu vực này từ bên ngoài làm tăng nội năng của nó và sau đó được truyền sang các vật xung quanh dưới dạng nhiệt (thỏa mãn định luật Joule-Lenz).

Nếu có e. d.s. trong một phần công suất có thể là dương hoặc âm. Để rõ ràng, chúng ta hãy quay lại quá trình sạc và xả pin một lần nữa.

Như chúng ta đã nói, khi sạc pin, dòng điện và chiều cùng dấu (đi theo hướng của điện thế bị mất, như trong phần đồng nhất của mạch điện) và dấu của e. d.s. dấu ngược lại của cường độ dòng điện. Do đó, nguồn $P = IU_{12}$ là dương, tức là pin tiêu thụ năng lượng từ bên ngoài. Nó chi tiêu vào việc gì? Hãy viết lại biểu thức công suất ở dạng khác. Vì $U_{12} = Ir - \mathcal{E}$ thì

$$P = I^2r - I\mathcal{E} = I^2r + |I||\mathcal{E}|.$$

Số hạng đầu tiên là biểu thức được biết đến từ định luật Joule-Lenz cho lượng nhiệt giải phóng trong bộ tích lũy trong một đơn vị thời gian. Và số hạng thứ hai là công thực hiện trên một đơn vị thời gian

⟦folio 55⟧

chống lại các thế lực (hóa học) của bên thứ ba; Do công việc này, năng lượng hóa học của pin tăng lên. Như vậy, năng lượng tiêu thụ từ bên ngoài được giải phóng một phần dưới dạng nhiệt và một phần làm tăng năng lượng cho pin.

Khi pin cạn kiệt, dấu của dòng điện và điện áp trái dấu nhau (do đó pin đi theo chiều điện thế tăng dần), còn dấu của dòng điện và e. d.s. là như nhau. Vì thế quyền lực

$$P = IU_{12} = -|I| |U_{12}| = I^2r - |I| |E|$$

tiêu cực. Điều này có nghĩa là nguồn điện không được cung cấp cho phần này từ bên ngoài mà thay vào đó, pin sẽ cung cấp năng lượng cho mạch ngoài. Tất nhiên, trong trường hợp này, một phần năng lượng $(I^2r)$ mà pin tiêu thụ sẽ được giải phóng dưới dạng nhiệt tại điện trở trong của pin. Phần năng lượng còn lại được cấp cho mạch ngoài.

Cần chứng minh rằng các tính toán trên (cụ thể là các công thức (5) và (6)) là hợp lệ bất kể nguồn gốc phát thải. d.s. trong khu vực đang được xem xét.

Bây giờ chúng ta hãy nhìn vào điều này bài toán.

Bài toán 3. Công suất cơ học tối đa $P_m$ mà động cơ DC nối tiếp *) được kết nối với mạng có điện áp $U = 120$ V có thể phát triển nếu điện trở của cuộn dây của nó là $r = 20$Om là bao nhiêu?

Khi phần ứng động cơ quay trong từ trường, một sóng điện tử sẽ xuất hiện trong cuộn dây của nó. d.s. do đó độ tự cảm $E$ (tương tự như trường hợp sạc pin)

$$|U| = |I|r + |E|.$$

Khi đó tổng công suất $P$ mà động cơ tiêu thụ bằng

$$P = IU = I^2r + |I| |E|.$$

Công suất thường xuyên $P_T = I^2r$ là lượng nhiệt tỏa vào thể tích

*) Động cơ nối tiếp là động cơ điện có các cuộn dây mắc nối tiếp.

Hình 6. a) $E_1 > E_2$, $r_1 < r_2$; b) $E_1 = E_2$, $r_1 = r_2$.

cuộn trong một đơn vị thời gian. Số hạng thứ hai trong biểu thức (8) biểu thị công suất cơ học $P_{mex}$. Hãy biểu thị cường độ hiện tại $I$ từ (7):

$$|I| = \frac{|U| - |E|}{r}$$

Thay giá trị thu được vào biểu thức công suất cơ, ta được:

$$P_{mex} = |I| |E| = \frac{|U| |E| - E^2}{r}.$$

Điện áp $U$ và điện trở cuộn dây $r$ được cho và e. d.s. độ tự cảm $E$ có ​​thể thay đổi, chẳng hạn như tùy thuộc vào tốc độ quay của động cơ. Trong bài toán cần tìm công suất cơ học cực đại của động cơ $P_m$ và biểu thức (9) có cực đại là $E = \frac{U}{2}$ (ví dụ: xem «Kvant» 1974, số 5, trang 65). Vì vậy, cuối cùng

$$P_m = \frac{U^2}{4r} = 180 \text{ bm}.$$

Hình 7. a) $E_1 > E_2$; b) $E_1 = E_2$.
