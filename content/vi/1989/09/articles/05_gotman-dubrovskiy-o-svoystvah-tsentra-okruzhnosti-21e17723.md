---
id: 1989-9-gotman-dubrovskiy-o-svoystvah-tsentra-okruzhnosti-21e17723
issue: kvant_1989_9
year: 1989
number: "9"
title: Về tính chất tâm của đường tròn ngoại tiếp
authors:
  - Готман Э. Г.
  - Дубровский В. Н.
rubric: zadachnik-kvanta
rubric_sub: Задачник «Кванта»
page_first: 40
page_last: 41
page_labels: 38-39
tag: 8DH8
lang: vi
source: kvant_digital
extraction: vision
content_sha256: 828a3a0f4fbac3ece1d4b8f0af20074aa398603bd2af071d09c144c4f2faf736
prompt_sha256: draft-1
translated_from: content/ru/1989/09/articles/05_gotman-dubrovskiy-o-svoystvah-tsentra-okruzhnosti-21e17723.md
source_content_sha256: 82e73ce52bc777efee73c82ee3e1bc74c318b303db4ca216e8074baed1567906
translation_model: draft
translation_run: vi-draft-2026-10-31
translation_quality: draft
---

⟦folio 38⟧

Về tính chất tâm của đường tròn ngoài

Trong ghi chú này, chúng tôi sẽ giới thiệu lời giải bài toán M1146. Bản thân bài toán này không khó. Nhưng khi xem xét kỹ hơn, đằng sau nó sẽ xuất hiện một chuỗi dài những khái quát hóa.

M1146. Điểm K là trung điểm cạnh AB của tam giác đều ABC. Trên các cạnh AC và BC lấy các điểm M và N sao cho ∠MKN=60°. Chứng minh rằng chu vi tam giác MCN bằng nửa chu vi tam giác ABC.

Chúng ta hãy lấy ngay một trường hợp tổng quát. Cho K là một điểm nằm trên phân giác của góc MCN có độ lớn γ, có hai điểm K và C nằm đối diện với MN (hình 1). Khi đó các điều kiện sau là tương đương:

(1) ∠MKN=(π−γ)/2,
(2) MN=PM+QM, trong đó P và Q là hình chiếu của điểm K lên các cạnh của góc.

Bài toán M1146 thu được từ đây tại γ=60° (hình 2): trong trường hợp này, góc MKN trong đẳng thức (1) bằng 60° và tính chất (2) tương đương với đẳng thức CM+MN+NC=CP+CQ=2CK cos 30°=3AB/2, tức là câu lệnh bài toán. Nhân tiện, hãy lưu ý rằng tại γ=90° bài toán M851 xuất hiện (xem «Kvant» số 3 cho năm 1984).

Có thể thu được một bằng chứng về sự tương đương của (1) và (2) bằng cách kiểm tra △KPM đối với góc π−γ trong đường tròn của điểm K (hình 3). Kết quả là, nó sẽ tiến tới △KQL (∠PKQ=π−γ), trong đó L là một điểm nào đó trên đường thẳng CN và ∠MKL=∠MKQ+∠QKL=

= ∠MKQ+∠PKM=π−γ, NL=NQ+QL=NQ+MP. Do đó, mỗi điều kiện (1) và (2) tương đương với đẳng thức của hai tam giác MKN và LKN. Thật vậy, những tam giác này có một cạnh chung KN và các cạnh bằng nhau KM và KL, ngoài ra, do (1) - các góc bằng nhau (∠MKN=(π−γ)/2 và ∠LKN=∠LKM=∠LKM−∠NKM=π−γ-(π−γ)/2, và do (2) – các cạnh bằng nhau MN và NL=NQ+QL=NQ+MP.

Chứng minh thứ hai về sự tương đương của (1) và (2) cho thấy ý nghĩa hình học của điểm K. Hoá ra điều kiện (1) và (2) có nghĩa là

(3) K là tâm đường tròn ngoài tam giác CMN, tức là đường tròn tiếp xúc với cạnh MN và kéo dài theo các cạnh CM và CN.

Trong thực tế, nếu K là tâm của đường tròn này thì P và Q là các điểm tiếp tuyến của nó với các đường thẳng CM và CN. Gọi R là điểm tiếp tuyến của đường tròn với MN (hình 4), khi đó rõ ràng MP=MR, NQ=NR, và do đó, tính chất (2) được thỏa mãn. Và từ đẳng thức của các tam giác KPM và KRM, KQM và KRN, suy ra rằng ∠MKN=∠PKQ/2=(π−γ)/2, tức là điều kiện (1) được thỏa mãn. Ngược lại, giả sử điểm K thỏa mãn điều kiện (1). Chúng ta chèn một đường tròn tâm K vào góc MCN và vẽ tiếp tuyến M′N′ song song với MN với nó. Theo những gì đã được chứng minh, ∠M′KN′=(π−γ)/2 = ∠MKN, nhưng điều này chỉ có thể xảy ra nếu M′=M, N′=N. Do đó, từ (1) suy ra (3). Chứng minh tương tự rằng từ (2) suy ra (3).

⟦folio 39⟧

Vì vậy, đối với tất cả các tiếp tuyến $MN$ của đường tròn nội tiếp góc $C$ có tâm $K$, được vẽ từ cạnh của đỉnh của góc, độ lớn của góc $MKN$, cũng như chu vi của tam giác $CMN$ đều được dựng (và lần lượt bằng nhau, $(\pi - \gamma)/2$ và $CP + CQ = 2CK \cos(\gamma/2)$). Một giá trị không đổi khác cho tất cả các phân đoạn này là tích của các tỷ lệ trong đó các điểm $M$ và $N$ chia các phân đoạn $CP$ và $CQ$:

$$\frac{CM \cdot CN}{MP \cdot NQ} = \frac{1}{\sin^2(\gamma/2)}$$

Để chứng minh điều này, chúng ta thay thế $MK$ và $NK$ là các phân giác của các góc ngoài $PMN$ và $QNM$ của tam giác $CMN$ (xem hình 4). Hãy đặt $\angle CMN = \alpha$, $\angle CNM = \beta$, sau đó từ các tam giác $PKM$ và $CKM$ ta được $\angle PKM = \alpha/2$, $\angle CKM = \beta/2$.

Theo định lý sin

$$\frac{CM}{MP} = \frac{\sin(\beta/2)}{\sin(\alpha/2) \sin(\gamma/2)}$$

$$\frac{CN}{NP} = \frac{\sin(\alpha/2)}{\sin(\beta/2) \sin(\gamma/2)}$$

Từ những đẳng thức này (4) ngay sau đây.

Một thuộc tính đẹp khác của cấu hình của chúng ta sẽ lộ ra nếu chúng ta vẽ đoạn $PQ$ và tạo khoảng cách cho tam giác $RUV$, trong đó $U$ và $V$ là các điểm giao nhau của $PQ$ với $KM$ và $KN$ (hình 5):

$$U \cap V = \text{основания высот треугольника } KMN, \text{ причем треугольник } RUV \text{ подобен треугольнику } CNM \text{ с коэффициентом } 1/\sin(\gamma/2).$$

Hãy để chúng tôi phác thảo bằng chứng bằng cách sử dụng một phép biến đổi tương tự. Đầu tiên, chúng ta vẽ các đường phân giác của tất cả các góc (trong và ngoài) của tam giác $CMN$ và lưu ý, ngoài $K$, thêm hai điểm giao nhau của chúng - tâm $K_1$ và $K_2$

Hai hình tròn không có hình dạng của tam giác $CMN$ (xem hình 5). Vì các đường phân giác của các góc kề nhau là đường vuông góc nên các điểm $C, M, N$ là đáy các đường cao của tam giác $KK_2K_1$. Vì vậy, chúng ta chỉ cần biểu thị một phép biến đổi tương tự với hệ số $k = \sin(\gamma/2)$, biến $\triangle KK_1K_2$ thành $\triangle KNM$ và đồng thời $\triangle MNC$ thành $\triangle VUR$. Sự biến đổi như vậy là thành phần $F$ của đường phân giác tương đối đối xứng $l$ của góc $MKN$ và có tâm $K$ và hệ số $k$.

Thật vậy, trong trường hợp này các phép biến đổi

$$1^\circ$$ điểm $K$ vẫn giữ nguyên vị trí và các dòng $KK_1$ và $KK_2$ đi vào nhau và $F(K_1) = N$, $F(K_2) = M$ (nhập $KN/KK_1 = KM/KK_2 = \cos \angle MKN = \sin(\gamma/2) = k$);

$$2^\circ$$ $F(C) = R$ (vì $F(\triangle KK_1K_2) = \triangle KNM$, $KC$ và $KR$ là chiều cao của các hình tam giác này);

$$3^\circ$$ đường $KP$ đi vào đường $KC$ (chúng đối xứng với $l$) và $F(R) = E$, trong đó $E$ là điểm giao nhau của $KC$ và $PQ$ ($KE/KR = KE/KP = \cos \angle PKC = k$), và do đó.

$$4^\circ$$ đường thẳng $MN$ thành đường thẳng $PQ$, nghĩa là $F(M) = V$, $F(N) = U$.

Hãy thử tự mình tìm cách chứng minh mệnh đề (5) “truyền thống” (với các đường tròn phụ, góc đếm, v.v.), đồng thời giải quyết bài toán sau.

1. Chứng minh rằng điều kiện (4) và (5) tương đương với (1), (2) và (3).

2. Chứng minh rằng nếu trong cấu hình của chúng ta, chúng ta lấy điểm $K$ ngay từ đầu ở cùng phía với điểm $C$ từ dòng $MN$, thì các điều kiện (2), (4), (5) vẫn sẽ tương đương với nhau, cũng như các điều kiện

$$\begin{align*}
(1') & \angle MKN = (\pi + \gamma)/2 \\
(3') & K - центр вписанной окружности треугольника CMN.
\end{align*}$$

E. G. Gotman, V. N. Dubrovsky
