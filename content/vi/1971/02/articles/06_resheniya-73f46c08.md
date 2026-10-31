---
id: 1971-2-resheniya-73f46c08
issue: kvant_1971_2
year: 1971
number: "2"
title: Lời giải các bài M21—M25; F29—F34
rubric: zadachnik-kvanta
rubric_sub: Задачник «Кванта»
page_first: 28
page_last: 38
page_labels: 26, 28, 29, 30, 31, 32, 33, 34, 35, 36
tag: LMKE
lang: vi
source: kvant_digital
extraction: vision
content_sha256: 7cc5f907bfb425b1695938f417e3531b2011950d1208f56eda7e1ff3481972ca
prompt_sha256: 3ec6b8aabd9b98576af76503cd8a2902b9f5d18e01ee867dfb1228f59c6d52d8
translated_from: content/ru/1971/02/articles/06_resheniya-73f46c08.md
source_content_sha256: 4c750e3bb793bea2025a71011190b5fc92d23ea716a0c687d0018f81521ab25a
translation_model: gpt-5.6-terra
translation_run: vi-codex-2026-10-31
---

⟦folio 26⟧

LỜI GIẢI

Trong mục này của tạp chí, chúng tôi tiếp tục đăng lời giải các bài toán từ tuyển tập bài toán của “Kvant”. Một số bài trong đó khó ngay cả đối với các nhà toán học và vật lí chuyên ngành. Nhiều bài là dịp để nói về cả một lớp bài toán, về các phương pháp tiếp cận những hiện tượng này hay khác. Mỗi lời giải là một bài báo nhỏ riêng biệt, và chúng tôi khuyên cả những người trước đây chưa từng thử giải bài toán cũng nên làm quen với chúng.

Trong đa số trường hợp, chúng tôi nêu họ tên các độc giả đã gửi những lời giải thành công nhất, nhưng tất nhiên chúng tôi không thể trả lời tất cả những người đã gửi thư cho chúng tôi.

M21
Bên trong một hình vuông cạnh 1 có đặt một số đường tròn, tổng độ dài của chúng bằng 10. Chứng minh rằng không thể kẻ đường thẳng. Khi đó mỗi điểm trên cạnh AB được phủ bởi không quá ba hình chiếu của các đường tròn (hình 1), nếu không đường thẳng đi qua điểm đó và vuông góc với AB sẽ cắt nhiều hơn ba đường tròn. Do đó, tổng tất cả các hình chiếu, tức là tổng độ dài các đường kính của các đường tròn, không vượt quá 3; vì thế tổng độ dài các đường tròn không vượt quá 3π, trong khi theo giả thiết nó bằng 10>3π. Mâu thuẫn thu được chứng minh khẳng định của bài toán.

Lời giải như vậy được gửi bởi Đ. Grigoriev từ Leningrad và N. Rasskhin từ Moskva.

Hoàn toàn tương tự có thể chứng minh khẳng định tổng quát hơn sau đây. Gọi bề ngang của một hình lồi là độ rộng của dải hẹp nhất có thể đặt hình ấy vào. (Có thể chỉ ra rằng định nghĩa này thích hợp cho mọi hình bị chặn.) Khi đó, nếu bên trong một hình có bề ngang h có n hình mà tổng các bề ngang của chúng lớn hơn kh, thì sẽ có một đường thẳng cắt không ít hơn k + 1 trong số các hình đó.

⟦folio 28⟧

Viết lại bình phương của biểu thức đã cho dưới dạng sau:

$$P_n^2 = \frac{1^2}{2^2} \cdot \frac{3^2}{4^2} \cdot \frac{5^2}{6^2} \cdot \dots \cdot \frac{(2n-1)^2}{(2n)^2} = \frac{1}{2} \cdot \frac{3^2}{2 \cdot 4} \cdot \frac{5^2}{4 \cdot 6} \cdot \dots \cdot \frac{(2n-1)^2}{(2n-2) \cdot 2n} \cdot \frac{1}{2n}.$$

Vì với mọi số nguyên $k > 1$

$$\frac{(2k-1)^2}{(2k-2) \cdot 2k} = \frac{(2k-1)^2}{(2k-1)^2 - 1} > 1,$$

nên

$$P_n^2 > \frac{1}{2} \cdot \frac{1}{2n} \text{ và } P_n > \frac{\sqrt{2}}{2} \cdot \frac{1}{\sqrt{2n}}.$$

Mặt khác, vì luôn có

$$\frac{(2k-1)(2k+1)}{(2k)^2} = \frac{(2k)^2 - 1}{(2k)^2} < 1,$$

nên

$$P_n^2 = \frac{3}{2^2} \cdot \frac{3.5}{4^2} \cdot \frac{5.7}{6^2} \cdot \dots \cdot \frac{(2n-1)(2n-3)}{(2n-2)^2} \cdot \frac{2n-1}{(2n)^2} < \frac{3}{4} \cdot \frac{1}{2n} \text{ và}$$

$$P_n < \frac{\sqrt{3}}{2} \cdot \frac{1}{\sqrt{2n}}.$$

Một lời giải hơi khác được Đ. Gritsoriev đề xuất (lời giải như vậy cũng được các độc giả khác của tạp chí gửi đến). Xét cùng với biểu thức đã cho

$$P_n = \frac{1}{2} \cdot \frac{3}{4} \cdot \frac{5}{6} \cdot \dots \cdot \frac{2n-3}{2n-2} \cdot \frac{2n-1}{2n}$$

biểu thức sau:

$$Q_n = \frac{1}{2} \cdot \frac{2}{3} \cdot \frac{4}{5} \cdot \dots \cdot \frac{2n-4}{2n-3} \cdot \frac{2n-2}{2n-1}.$$

Vì mỗi thừa số của tích $Q_n$ không lớn hơn thừa số tương ứng của $P_n$, nên $P_n > Q_n$ và do đó, $P_n^2 > P_nQ_n = \frac{1}{4n}$, tức là $P_n > \frac{\sqrt{2}}{2} \cdot \frac{1}{\sqrt{2n}}.$

Mặt khác,

$$R_n = \frac{1}{2} \cdot \frac{4}{5} \cdot \frac{6}{7} \cdot \dots \cdot \frac{2n-2}{2n-1} \cdot 1 > P_n,$$

позному $P_n^2 < P_nR_n = \frac{3}{8n}$ và $P_n < \frac{\sqrt{3}}{2} \cdot \frac{1}{\sqrt{2n}}.$

Có vẻ tự nhiên hơn là tìm $R_n$ không phải với 1/2 mà với 2/3. Nhưng khi đó đối với $P_n$ sẽ thu được một đánh giá thô hơn mức cần thiết theo điều kiện bài toán. Ngược lại, nếu trong $R_n$ giữ không phải một mà nhiều thừa số bằng các thừa số đầu của $P_n$, thì đối với $P_n$ sẽ thu được một đánh giá chính xác hơn dạng $P_n < \frac{c}{\sqrt{n}}$, trong đó $c$ là một số nhỏ hơn $\sqrt{\frac{3}{8}}$. Nhận xét tương tự cũng áp dụng cho đánh giá theo phía kia.

Cũng có một lời giải dựa trên phương pháp quy nạp toán học. Chính trên ví dụ bài toán này, trong ghi chú của E. G. Nikolaev “Trường hợp với phương pháp quy nạp toán học” (xem “Kvant” số 7, 1970, tr. 37 và “Kvant” số 12, 1970, tr. 58) đã nói rằng đôi khi chứng minh bằng quy nạp một bất đẳng thức mạnh hơn lại dễ hơn một bất đẳng thức yếu hơn.

⟦folio 29⟧

Từ các bất đẳng thức đã chứng minh suy ra rằng đại lượng $P_n$ khi $n$ tăng thì tiến tới không, còn đại lượng $P_n \sqrt{n}$ nằm giữa $\frac{1}{2}$ và $\frac{1}{2} \sqrt{\frac{3}{2}}$. Có thể chứng minh (xem, chẳng hạn, các bài 145, 160, 161 trong sách của A. M. Yaglom và I. M. Yaglom “Các bài toán không sơ cấp trình bày sơ cấp”, GITTL, M., 1954) rằng khi $n \to \infty$ $P_n$ tiến tới giới hạn bằng $\sqrt{\frac{1}{\pi}}$.

**M24**

Chứng minh rằng mọi phân số $\frac{m}{n}$, trong đó $0 < \frac{m}{n} < 1$, đều có thể biểu diễn dưới dạng

$$\frac{m}{n} = \frac{1}{q_1} + \frac{1}{q_2} + \frac{1}{q_3} + \dots + \frac{1}{q_r},$$

trong đó $0 < q_1 < q_2 < \dots < q_r$ là các số nguyên và mỗi $q_k$ ($k=2, 3, \dots, r$) chia hết cho $q_{k-1}$.

Mọi phân số $\frac{m}{n}$ có thể chia cả tử số lẫn mẫu số cho ước chung lớn nhất của chúng, thay bằng một phân số tối giản bằng nó. Ví dụ, $\frac{288}{504} = \frac{4.72}{7.72} = \frac{4}{7}$. Sau này chúng ta sẽ chỉ xét những phân số tối giản như vậy.

Ta sẽ chứng minh khẳng định của bài toán bằng quy nạp theo $m$. Với $m=1$ điều đó hiển nhiên: bản thân phân số $\frac{m}{n}$ đã có dạng cần thiết. Bây giờ ta chứng minh rằng nếu khẳng định của bài toán đúng với mọi phân số có tử số nhỏ hơn $m$, thì nó cũng đúng với các phân số có tử số bằng $m$. Giả sử $\frac{m}{n}$ là một phân số như vậy ($1 < m < n$). Chia $n$ cho $m$ có dư; ta được thương ($d_0-1$) và dư ($m-k$), tức là

$$n = m (d_0-1) + (m-k) = md_0-k,$$

trong đó $d_0 > 1$ và $0 < k < m$. Viết lại (1) như sau: $md_0=n+k$, hay

$$\frac{m}{n} = \frac{1}{d_0} \left( 1 + \frac{k}{n} \right).$$

Vì $0 < k < m$, phân số $\frac{k}{n}$ có thể biểu diễn dưới dạng cần thiết:

$$\frac{k}{n} = \frac{1}{d_1} + \frac{1}{d_1 d_2} + \dots + \frac{1}{d_1 d_2 \dots d_r},$$

trong đó $d_1, d_2, \dots, d_r$ là một số số tự nhiên nào đó, lớn hơn 1. Từ (2) và (3) ta được

$$\frac{m}{n} = \frac{1}{d_0} + \frac{1}{d_0 d_1} + \frac{1}{d_0 d_1 d_2} + \dots + \frac{1}{d_0 d_1 d_2 \dots d_r}.$$

Phân số $\frac{m}{n}$ đã được biểu diễn dưới dạng cần thiết.

Lưu ý rằng từ lời giải bài toán của chúng ta có thể dễ dàng rút ra một thuật toán đơn giản — quy tắc biểu diễn bất kỳ phân số nào đã cho dưới dạng tổng (3). Hãy minh họa bằng một ví dụ. Giả sử ta có phân số $\frac{5}{7}$:

$$7 = 2.5 - 3; \quad \frac{5}{7} = \frac{1}{2} \left( 1 + \frac{3}{7} \right);$$

$$7 = 3.3 - 2; \quad \frac{3}{7} = \frac{1}{3} \left( 1 + \frac{2}{7} \right);$$

$$7 = 4.2 - 1; \quad \frac{2}{7} = \frac{1}{4} \left( 1 + \frac{1}{7} \right).$$

⟦folio 30⟧

Vậy,

$$\frac{5}{7} = \frac{1}{2} + \frac{1}{2.3} + \frac{1}{2.3.4} + \frac{1}{2.3.4.7} = \frac{1}{2} + \frac{1}{6} + \frac{1}{24} + \frac{1}{168}.$$

Dĩ nhiên, có thể tìm được vài biểu diễn dưới dạng (3), chẳng hạn:

$$\frac{3}{8} = \frac{1}{4} + \frac{1}{8} = \frac{1}{3} + \frac{1}{24}.$$

Lời giải bài toán này do Đ. Gritsor'e gửi đến.

M25

Trong một tập hợp gồm $n$ phần tử, chọn $2^{n-1}$ tập con, sao cho bất kỳ ba tập con nào cũng có một phần tử chung. Hãy chứng minh rằng tất cả các tập con này có một phần tử chung.

Tổng cộng, trong tập hợp $A$ gồm $n$ phần tử, có $2^n$ tập con khác nhau, kể cả tập rỗng và chính tập hợp $A$ (xem bài viết của N. Ya. Vilenkin «Tổ hợp», «Kvant» số 1, 1971). Ta sẽ ký hiệu các tập con khác nhau của $A$ bằng các chữ cái $B, C, \dots$, giao của các tập hợp $B$ và $C$, tức là tập hợp gồm các phần tử chung của $B$ và $C$, được ký hiệu như sau: $B \cap C$; tập con bù của $B$ trong toàn bộ tập hợp $A$, tức là tập hợp gồm tất cả những phần tử của $A$ không thuộc $B$, được ký hiệu như sau: $\bar{B}$.

Theo điều kiện, đã chọn $2^{n-1}$ tập con, tức là một nửa trong tất cả các tập con có thể có, hơn nữa mỗi tập con được chọn, giao của bất kỳ hai (và thậm chí ba) tập con nào trong số chúng đều không rỗng. Do đó, từ mỗi cặp tập con $(B, \bar{B})$ bù nhau trong $A$, đã chọn đúng một tập con. Hơn nữa, nếu $B$ và $C$ được chọn, thì $D = B \cap C$ cũng được chọn, vì $\bar{D}$ không thể được chọn (cả ba tập con $\bar{D}, B$ và $C$ không thể có phần tử chung, vì các phần tử chung của $B$ và $C$ nằm trong $D$). Dùng điều này, bằng quy nạp thông thường có thể chứng minh rằng nếu $B_1, B_2, \dots, B_k$ được chọn, thì giao của tất cả các tập con này $B_1 \cap B_2 \cap \dots \cap B_k$ cũng được chọn. Do đó, giao của tất cả $2^{n-1}$ tập con được chọn cũng thuộc số các tập con được chọn, tức là nó không rỗng.

Như vậy, chúng ta đã chứng minh rằng chỉ có một hệ các tập con thỏa mãn điều kiện bài toán: cố định một phần tử nào đó $a$ của tập hợp $A$ và chọn tất cả các tập con chứa phần tử ấy.

N. B. Vasiliev

Ф29

Tìm tốc độ bay hơi từ một đơn vị diện tích bề mặt nước vào chân không ở nhiệt độ $20^\circ\text{C}$. (Áp suất hơi bão hòa ở nhiệt độ này bằng 17,5 mm thủy ngân.) Trong bao lâu thì nước đựng đầy một chiếc đĩa lót tách trà thông thường sẽ bay hơi trong phòng? Sự bay hơi của một lượng nước nhỏ trên thực tế không làm thay đổi độ ẩm không khí trong phòng, bằng 70%.

Để giải bài toán, cần tìm số phân tử chất lỏng rời khỏi 1 cm$^2$ bề mặt của nó trong 1 giây. Nhân số đó với khối lượng các phân tử nước, ta có thể biết tốc độ bay hơi, tức là khối lượng nước bay hơi từ một đơn vị diện tích bề mặt nước trong 1 giây.

Ta sẽ lập luận như sau. Nếu phía trên chất lỏng có hơi bão hòa, thì số phân tử chất lỏng rời khỏi nó trong 1 giây cũng sẽ như khi không có hơi. Khi đó, một lần, có đúng bấy nhiêu phân tử đi vào chất lỏng, bao nhiêu phân tử bay ra khỏi nó. Điều này cho phép ta tính được,

⟦folio 31⟧

có bao nhiêu phân tử bay ra khỏi nước trong 1 giây, vì việc tìm số phân tử đi vào chất lỏng khá đơn giản.

Hãy dùng mô hình sau của khí lí tưởng: mọi phân tử khí đều có cùng vận tốc $v$, và mỗi phân tử chỉ có thể chuyển động theo một trong ba phương vuông góc với nhau dọc theo các trục tọa độ (hình 4). Hơn nữa, số phân tử chuyển động theo mỗi trong ba phương này là như nhau. Nếu một trong các trục tọa độ vuông góc với chất lỏng, thì trong thời gian $\tau$ một khối lượng hơi nằm cách nó một khoảng $l = v \cdot \tau$ đi vào chất lỏng. Giả sử trong một đơn vị thể tích có $n$ phân tử hơi, khi đó lên một phần bề mặt có diện tích $S$ sẽ rơi vào $N = \frac{1}{6} nv\tau S$ phân tử hơi: theo trục tọa độ vuông góc với bề mặt chất lỏng, $\frac{1}{3}$ số phân tử hơi nằm trong thể tích $v\tau S$ chuyển động, trong đó vận tốc của một nửa số phân tử hướng ra xa chất lỏng. Nếu khối lượng của phân tử hơi là $m$, thì trong thời gian $\tau$ một khối lượng hơi $M = \frac{1}{6} nv\tau Sm$ đi vào chất lỏng. $n \cdot m$ là khối lượng riêng của hơi $\rho$. Do đó

$$M = \frac{1}{6} v\tau S\rho.$$

Tốc độ của các phân tử hơi có thể biểu diễn qua áp suất và khối lượng riêng của nó. Xét một bình hình lập phương có cạnh $l$ và các mặt vuông góc với các trục tọa độ (hình 4). Khi các phân tử hơi va chạm đàn hồi với thành bình, động lượng của chúng thay đổi một lượng $2mv$ — trước va chạm động lượng của phân tử bằng $mv$, còn sau va chạm — $mv$: phân tử chuyển động ra xa thành bình. Vì giữa hai lần va chạm liên tiếp của phân tử với cùng một thành bình trôi qua thời gian $t = \frac{2l}{v}$, nên theo định luật II Newton có thể coi rằng thành bình tác dụng lên phân tử một lực trung bình $f = \frac{2mv}{2l} = \frac{mv^2}{l}$. Theo định luật III Newton, một lực có cùng độ lớn tác dụng lên thành bình. Vì theo mỗi trục có $N = \frac{1}{3} nl^3$ phân tử chuyển động, mỗi phân tử đều góp phần vào áp suất lên thành bình, nên tổng lực tác dụng lên thành bình bằng

$$F = \frac{mv^2}{l} \cdot \frac{1}{3} nl^3 = \frac{1}{3} nml^2v^2,$$

và áp suất của hơi lên thành bình bằng

$$P = \frac{F}{l^2} = \frac{1}{3} nmv^2 = \frac{1}{3} \rho v^2.$$

⟦folio 32⟧

Vì vậy
$$v = \sqrt{\frac{3P}{\rho}}.$$

Thay biểu thức này của $v$ vào công thức (*), ta được
$$M = \frac{1}{6} \tau S \rho \sqrt{\frac{3P}{\rho}}.$$

Ta còn biểu diễn khối lượng riêng của hơi qua áp suất của nó. Chúng liên hệ với nhau bởi phương trình Clapeyron:
$$P = \frac{\rho}{\mu} RT,$$

trong đó $\mu$ — khối lượng của một gam-phân tử hơi, $T$ — nhiệt độ của nó, còn $R = 8,3 \frac{\partial \kappa}{\partial \rho} - \text{hằng số khí}.$

Từ công thức này suy ra rằng $\rho = \frac{P \mu}{RT}$. Vì vậy $M = \frac{1}{6} \tau S \frac{P \mu}{RT} \sqrt{\frac{3RT}{\mu}}.$

Như vậy, nếu phía trên chất lỏng có hơi, thì trong 1 giây, lên một đơn vị diện tích bề mặt của nó rơi xuống một khối lượng hơi bằng
$$\frac{M}{\tau S} = \frac{1}{6} P \sqrt{\frac{3\mu}{RT}}.$$

Điều đó có nghĩa là tốc độ bay hơi của chất lỏng vào chân không bằng
$$\frac{1}{6} P \sqrt{\frac{3\mu}{RT}}.$$

Thay vào đây các giá trị số $T = 293^\circ \text{K}$, $\mu = 18 \frac{\kappa_2}{\kappa_0 \text{m}^2}$ và $P = 2,3 \cdot 10^3 \frac{\mu}{m^2}$ ($P$ — áp suất hơi bão hòa tại $T = 293^\circ \text{K}$), ta được tốc độ bay hơi bằng $14,8 \cdot 10^{-8} \frac{\kappa_2}{m^2 \cdot \text{giây}}.$

Ta cũng có thể giải bài toán chính xác hơn, có xét đến việc các phân tử chuyển động với những vận tốc khác nhau và theo mọi hướng *). Tuy nhiên, điều đó sẽ không làm thay đổi kết quả định tính mà ta đã nhận được. Chỉ có hệ số số trong công thức cuối cùng thay đổi.

Bây giờ không khó tìm cả thời gian mà nước đổ vào đĩa trà sẽ bay hơi trong phòng. Trong trường hợp này, từ một đơn vị diện tích bề mặt chất lỏng trong 1 giây bay ra các phân tử có tổng khối lượng bằng $\frac{1}{6} P_0 \sqrt{\frac{3\mu}{RT}} \left( P_0 = 10^{-5} \frac{\mu}{m^2} \right)$, còn khối lượng hơi đi vào chất lỏng bằng $\frac{1}{6} P \sqrt{\frac{3\mu}{RT}}$, trong đó $P = \eta \cdot P_0 = 0,7P_0$. Như vậy, tốc độ bay hơi của chất lỏng bằng
$$\frac{1}{6} \left( P_0 - P \right) \sqrt{\frac{3\mu}{RT}}.$$

Nếu diện tích bề mặt nước là $S$, còn khối lượng của nó là $M$, thì toàn bộ nước sẽ bay hơi trong thời gian
$$t = \frac{M}{\frac{1}{6} S \left( P_0 - P \right) \sqrt{\frac{3\mu}{RT}}}.$$

*) Cách tính như vậy được nêu trong bài của Ya. A. Smorodinsky «Khí lí tưởng» («Kvant» số 10, năm 1970).

⟦folio 33⟧

Lấy rằng đĩa chứa được 100 $e$ nước, đường kính của nó bằng 10 $cm$, nhiệt độ không khí trong phòng bằng $17^\circ C=290^\circ K$ (ở nhiệt độ này $P_0 = 2,3 \cdot 10^3 \frac{H}{M^2}$ và $P = 1,6 \cdot 10^3 \frac{H}{M^2}$), ta tìm được $t=1$ giây.

Kết quả nhận được thật nghịch lí. Ta đã sai ở đâu? Ở các giá trị áp suất hơi gần bề mặt nước. Ở đây áp suất hơi lớn hơn đáng kể so với trong phòng. Trong lớp mỏng gần bề mặt, hơi gần như bão hòa. Chỉ nhờ vậy nước mới bay hơi đủ chậm.

Ví dụ mà chúng ta đã xét cho thấy khi giải một bài toán vật lí, điều quan trọng là phải hiểu rõ «vật lí» của hiện tượng, tức là hiểu có thể và không thể bỏ qua điều gì.

F 30

Trong máy quay phim và máy chiếu phim, 8 khuôn hình đi qua trong một giây. Trên màn hình, một ô tô có các bánh xe với đường kính thực là 1 m chuyển động. Hình ảnh các bánh xe quay 2 vòng trong một giây. Vận tốc của ô tô là bao nhiêu?

Vì hình ảnh các bánh xe quay 2 vòng trong thời gian 8 khuôn hình đi qua máy chiếu, nên ở mỗi khuôn hình bánh xe phải quay so với khuôn hình trước một góc $\frac{2}{8} = \frac{1}{4}$ vòng. Hơn nữa, hình ảnh các bánh xe ô tô trên màn ảnh có thể quay cả “về phía trước” lẫn “về phía sau”, mặc dù bản thân ô tô trong cả hai trường hợp đều chuyển động theo cùng một hướng (hình 5). Các bánh xe trên màn ảnh quay “về phía trước” nếu vận tốc chuyển động của ô tô sao cho trong thời gian giữa hai khuôn hình $\tau = \frac{1}{8} c$ các bánh xe ô tô thực hiện $n$ vòng trọn vẹn và thêm $\frac{1}{4}$ vòng quanh trục. Nếu trong thời gian $t$ các bánh xe thực hiện $n$ vòng trọn vẹn và $\frac{3}{4}$ vòng quanh trục, thì hình ảnh các bánh xe trên màn ảnh sẽ quay “về phía sau”. Như vậy, vận tốc góc của ô tô bằng либо $\omega_{\text{вп}} = \frac{\left(n + \frac{1}{4}\right) 2\pi}{\frac{1}{8}} \frac{pa\partial}{c} = 16 \left(n + \frac{1}{4}\right) \pi \frac{pa\partial}{c}$, hoặc $\omega_{\text{н}} = 16 \left(n + \frac{3}{4}\right) \pi \frac{pa\partial}{c}$. Điều này có nghĩa là các trục bánh xe, và cùng với chúng là ô tô, chuyển động với vận tốc $v = 16 \left(n + \frac{1}{4}\right) \pi R \frac{m}{c}$ (khi đó hình ảnh các bánh xe quay “về phía trước”) hoặc với vận tốc $u = 16 \left(n + \frac{3}{4}\right) \pi R \frac{m}{c}$ (trong trường hợp này hình ảnh các bánh xe quay “về phía sau”). Thay $n = 1, 2, 3, \dots$ vào các công thức này, ta nhận được các đáp số

$$v_1 \approx 12,6 \frac{m}{c} = 45 \frac{km}{час}, \quad v_2 \approx 223 \frac{km}{час}, \quad u_1 \approx 136 \frac{km}{час}, \quad u_2 \approx 316 \frac{km}{час}, \dots$$

⟦folio 34⟧

Vì tốc độ của ô tô không thể lớn hơn 140 $\frac{\kappa M}{\mu ac}$, nên nó bằng 45 $\frac{\kappa M}{\mu ac}$, nếu ảnh của các bánh xe quay «về phía trước», hoặc 136 $\frac{\kappa M}{\mu ac}$, nếu các bánh xe trên màn hình quay «về phía sau».

Lời giải đúng do Nikolai Ilyin gửi đến (làng Zakhal, huyện Ekhirit-Bulagatsky, tỉnh Irkutsk).

Ф 31

Áp suất ánh sáng định hướng như thế nào đối với Mặt Trời một con tàu vũ trụ hình cầu, trong đó một nửa có mặt gương, còn nửa kia màu đen, hấp thụ hoàn toàn bức xạ Mặt Trời? Tâm trọng lực của con tàu nằm ở tâm quả cầu.

Giả sử con tàu được định hướng sao cho các tia Mặt Trời chiếu cả lên các phần có mặt gương lẫn các phần màu đen trên bề mặt của nó (hình 6). Áp suất ánh sáng liên quan đến việc các photon rơi lên bề mặt làm thay đổi động lượng của chúng. Nếu ánh sáng rơi lên bề mặt gương, nó phản xạ sao cho định luật phản xạ được thỏa mãn: góc tới của tia sáng bằng góc phản xạ. Không khó thấy rằng trong trường hợp này động lượng của photon thay đổi một vectơ vuông góc với phần bề mặt của con tàu, tức là đi theo bán kính. Theo định luật thứ hai và thứ ba của Newton (xem bài trước), khi đó có một lực tác dụng lên con tàu, bằng độ biến thiên động lượng của chùm photon trong một đơn vị thời gian. Lực này hướng dọc theo bán kính của con tàu. Nó không tạo ra mômen quay con tàu sao cho bề mặt gương của con tàu hướng về phía Mặt Trời.

Khác với áp suất lên bề mặt màu đen của con tàu. Vì nó hấp thụ bức xạ Mặt Trời, nên lực tác dụng lên con tàu khi photon rơi xuống hướng dọc theo chùm tia. Lực này tạo ra mômen quay con tàu sao cho bề mặt gương của con tàu hướng về phía Mặt Trời.

Rõ ràng, vị trí của con tàu khi bề mặt màu đen của nó hướng về phía Mặt Trời cũng là một vị trí cân bằng. Tuy nhiên, vị trí cân bằng này không bền. Nếu vì một nguyên nhân ngẫu nhiên nào đó con tàu lệch đi một chút so với Mặt Trời, thì nó sẽ quay cho đến khi quay mặt gương về phía Mặt Trời.

Ф 32

Trên mặt nước nổi một thanh gỗ có tiết diện vuông. Trong hai vị trí cân bằng được chỉ trên hình 7, vị trí nào sẽ bền? Khối lượng riêng của vật liệu làm thanh gỗ bằng một nửa khối lượng riêng của nước.

Một hệ để tự nó luôn chiếm vị trí sao cho tâm khối của nó ở vị trí thấp nhất. Vì khối lượng riêng của vật liệu thanh gỗ bằng một nửa khối lượng riêng của nước, nên trong cả hai trường hợp một nửa khối lập phương bị ngập và các tâm trọng lực của các khối lập phương

⟦trang 35⟧

nằm ở cùng một độ cao. Nhưng đối với tâm trọng lực của nước thì khác. Khi nhúng thanh gỗ, ta chuyển lên mặt nước lượng nước mà phần ngập của thanh gỗ chiếm chỗ. Trong trường hợp thứ nhất, tâm khối của thể tích nước bị chiếm chỗ nằm cách mặt nước một khoảng 0,25 а, còn trong trường hợp thứ hai — một khoảng bằng $\frac{1}{3} \frac{a \sqrt{2}}{2} =$

$$= \frac{1}{6} a \sqrt{2} \approx 0,23 a,$$

trong đó $a$ là cạnh của thanh gỗ. Điều này có nghĩa là trong trường hợp thứ hai độ biến thiên thế năng của nước khi nhúng khối lập phương nhỏ hơn trường hợp thứ nhất. Vì vậy trong trường hợp thứ hai thế năng của nước cũng nhỏ hơn. Điều đó có nghĩa là thanh gỗ sẽ nổi ở vị trí II.

♦ 33

Trên một vòng dây ngang nhẵn, hai hạt có khối lượng $m_1$ và $m_2$ có thể trượt không ma sát. Ban đầu các hạt được nối bằng một sợi chỉ, và giữa chúng có một lò xo bị nén. Sợi chỉ bị đốt. Sau khi các hạt bắt đầu chuyển động, lò xo được lấy đi. Các hạt sẽ va chạm lần thứ mười một ở vị trí nào trên vòng? Các hạt va chạm đàn hồi tuyệt đối.

Lò xo truyền cho cả hai hạt những xung lượng bằng nhau, vì nó tác dụng lên chúng trong cùng một thời gian với cùng một lực:

$$m_1 v_1 = m_2 v_2$$

(1)

trong đó $v_1$ và $v_2$ là các vận tốc mà các hạt thu được. Vì vậy, đối với các quãng đường $l_1$ và $l_2$ mà các hạt đi được trước va chạm đầu tiên, cũng có $m_1 l_1 = m_2 l_2$. Sau va chạm, tổng động lượng của các hạt vẫn phải bằng không. Do đó

$$m_1 v_1' = m_2 v_2'.$$

(2)

Viết định luật bảo toàn năng lượng

$$\frac{m_1 v_1^2}{2} + \frac{m_2 v_2^2}{2} = \frac{m_1 v_1'^2}{2} + \frac{m_2 v_2'^2}{2},$$

(3)

dùng (1) và (2) dễ dàng tìm được rằng sau va chạm $v_1' = v_1$ và $v_2' = v_2$.

Như vậy, do va chạm, các vận tốc của các hạt không đổi về độ lớn mà chỉ đổi chiều sang chiều ngược lại. Nhưng khi đó rõ ràng va chạm tiếp theo sẽ xảy ra tại nơi chuyển động của các hạt bắt đầu, v.v. Va chạm thứ mười một sẽ xảy ra tại đúng nơi đã xảy ra va chạm thứ nhất, tức là tại điểm mà tỉ số các khoảng cách đến nó từ gốc tọa độ (theo cung tròn) bằng tỉ số khối lượng của các hạt.

♦ 34

Hình 8 vẽ một máy tĩnh điện nhỏ giọt (máy phát Kelvin). Từ một ống vào một quả cầu kim loại rỗng cách điện bán kính $R$ rơi các giọt nước được tích điện đến điện thế $\phi_0$. Điện thế giới hạn mà quả cầu có thể tích điện tới phụ thuộc thế nào vào độ cao rơi của các giọt?

Khi rơi vào quả cầu, các giọt truyền cho nó điện tích của mình, điện tích này phân bố đều trên bề mặt quả cầu. Khi đó xuất hiện điện trường ngăn cản sự rơi của các giọt, vì các giọt và quả cầu tích điện cùng dấu.

Có thể tìm vận tốc của giọt gần bề mặt quả cầu bằng cách dùng định luật bảo toàn năng lượng. Năng lượng của giọt $E$ gồm động năng, thế năng trong trường trọng lực và năng lượng tĩnh điện trong trường của quả cầu.

⟦folio 36⟧

Đã biết rằng điện trường của một quả cầu tích điện đều ở bên ngoài nó giống như điện trường của một điện tích điểm có độ lớn bằng điện tích của quả cầu và đặt tại tâm của nó. Vì vậy, thế năng của điện tích điểm $q$ trong trường của quả cầu tích điện đều mang điện tích $Q$ bằng $qQ/d$, trong đó $d$ — khoảng cách từ điện tích đến tâm quả cầu.

Năng lượng của giọt ở đầu quá trình rơi
$E_0 = mgh + \frac{qQ}{h-R}$, trong đó $h$ — độ cao rơi của giọt tính từ mặt bàn ($h > 2R$).

Ở bề mặt quả cầu, năng lượng của giọt là

$$E_1 = \frac{mv^2}{2} + 2Rmg + \frac{qQ}{R}.$$

Đặt hai năng lượng này bằng nhau, ta được

$$\frac{mv^2}{2} = mg(h - 2R) - qQ \frac{h - 2R}{R(h - R)}.$$

Khi điện tích của quả cầu $Q$ tăng lên, vận tốc của giọt $v$ ở bề mặt nó giảm xuống. Rõ ràng, quả cầu sẽ ngừng tích điện khi vận tốc này bằng không. Những giọt tiếp theo sẽ không thể rơi vào quả cầu nữa. Từ điều kiện này, ta tìm được điện tích giới hạn của quả cầu:

$$Q = \frac{mgR(h - R)}{q}.$$

Dùng các công thức tĩnh điện đã biết $Q = \phi R$ và $q = \phi_0 r$, đối với điện thế giới hạn của quả cầu ta được

$$\phi = \frac{mg(h - R)r}{2\phi_0}.$$

Khi suy ra công thức này, ta đã giả sử rằng quả cầu không bị tràn chất lỏng trước khi tích điện đến điện thế giới hạn đã tìm được. Tuy nhiên, nếu, chẳng hạn, các giọt đủ lớn, thì điều ngược lại luôn có thể xảy ra: quả cầu bị tràn, còn các giọt vẫn có thể rơi vào nó. Trong trường hợp này, điện thế giới hạn của quả cầu cũng dễ dàng tìm được.

Nếu bán kính giọt là $r$, còn bán kính quả cầu là $R$, thì quả cầu sẽ đầy khi có $N = (R/r)^3$ giọt rơi vào nó. Khi đó điện tích của quả cầu sẽ bằng $Q = qN$, trong đó $q = r\phi_0$ là điện tích của một giọt, còn điện thế giới hạn của quả cầu $\phi' = Q/R = \phi_0 R^2/r^2$.

Rõ ràng rằng trong các máy tĩnh điện giọt, quả cầu được làm đầy hoàn toàn, vì khi đó thu được điện thế giới hạn cao hơn.

Lời giải đúng được A. Egorov ở Moskva và N. Efimov ở Vinnitsa (CHXHCNXV Ukraina) gửi đến.

I. Sh. Slovodetsky
