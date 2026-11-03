---
id: 2024-11-12-nikolov-ivanov-variatsii-na-temu-odnoy-geometricheskoy-zadachi-e85aa0ba
issue: kvant_2024_11-12
year: 2024
number: 11-12
title: Các biến thể về chủ đề của một hình học bài toán
authors:
  - Николов Н.
  - Иванов А. Д.
rubric: zadachnik-kvanta
rubric_sub: Задачник «Кванта»
page_first: 30
page_last: 33
page_labels: 28, 31
tag: TPIO
lang: vi
source: kvant_digital
content_sha256: 08c41f28286d9fd103e9db8a2f214011072f4221a75739ca83d6ed7a1111c4d9
prompt_sha256: draft-1
translated_from: content/ru/2024/11-12/articles/06_nikolov-ivanov-variatsii-na-temu-odnoy-geometricheskoy-zadachi-e85aa0ba.md
source_content_sha256: f48dfd089e0476af5d204b46105a83c1d5a7e6045e6c45063aaaf515e28e3a06
translation_model: draft
translation_run: vi-draft-gaps-2026-11-03
translation_quality: draft
---

⟦folio 28⟧

Các biến thể về chủ đề của một hình học bài toán

N. NIKOLOV (SOFIA), A. IVANOV (PLEVEN)

Trong bài viết này, chúng ta sẽ thảo luận về cốt truyện liên quan đến hình học bài toán M2809 được đưa ra tại Olympic Quốc gia Bulgaria lần thứ 73.

Hãy nhìn vào thiết kế đơn giản này. Đặt các điểm M và N lần lượt trên các cạnh AC và BC của tam giác ABC (hình 1). Cho hai đoạn thẳng AN và BM cắt nhau tại điểm O. Sau đây chúng ta sẽ sử dụng ký hiệu chuẩn cho các phần tử của một tam giác: BC = a, AC = b, ACB J. Ngoài ra, chúng ta đặt CM = m, CN = n, AOM T.

⟦column⟧

⟦figure⟧

Hình 3

⟦figure⟧

Hình 1

Hãy bắt đầu với bài toán tiếp theo, về nguyên tắc, dành cho học sinh lớp 7–8. Bài toán 1. Cho ACB 90 q, đồng thời cho biết AM = BC và CM = BN. Tìm một OM.

Bài tập 1. Tìm đáp số trong bài toán 1 trong trường hợp giới hạn AC = BC và AC = 2BC.

Lời giải. Hãy hoàn thiện tam giác AMB thành hình bình hành AMBP (hình 2). Sau đó B.C.

Hình 2

⟦folio none⟧

---
running_head:
folio:
---

= AM = PB, CM = BN, $\angle BCM = 90^\circ = \angle PBN$ và do đó, tam giác BCM và PBN bằng nhau. Do đó AP = BM = PN. Chúng ta cũng có $\angle BNP = \angle CMB = 90^\circ - \angle MBN$, tức là NP ⊥ BM, do đó NP ⊥ AP. Khi đó tam giác ANP là tam giác vuông đều, do đó $\angle AOM = \angle OAP = 45^\circ$. Nhiệm vụ lời giải.

Bài tập 2. Tìm một lời giải bài toán 1 khác từ cấu trúc sau (hình 3). Cho BNAX là hình bình hành.

Hình 3

a) Chứng minh đẳng thức hai tam giác vuông BCM và MAX.
b) Tìm các góc của tam giác XMB rồi tìm $\angle AOM$.
Cách xây dựng này có thể đạt được theo cách khác bằng cách lấy một hình vuông dựng trên cạnh AC và một hình vuông nội tiếp dựng trên cạnh BM.

Lưu ý rằng trong ký hiệu của chúng tôi, các điều kiện AM = BC và CM = BN bài toán 1 được viết lại thành $b - m = a$ và $m = a - n$.

Nếu $\angle ACB = 90^\circ$, các phép tính đơn giản cho phép chúng ta biểu thị các đại lượng $\theta$ theo $a$, $b$, $m$, $n$. Đặc biệt, chúng ta hãy phát biểu tuyên bố sau đây.

Tuyên bố 1. Nếu $\angle ACB = 90^\circ$, mo $\theta = 45^\circ$ có thể và lặng lẽ có thể, khi
$$ab - mn = bm + an.$$ (1)

Bằng chứng. Hãy đặt $\theta_1 = \angle CAN$ và $\theta_2 = \angle BMC$, sao cho $tg\theta_1 = \frac{NC}{AC} = \frac{n}{b}$ và $tg\theta_2 = \frac{BC}{MC} = \frac{a}{m}$. Sau đó
$$tg\theta = tg(\theta_2 - \theta_1) = \frac{tg\theta_2 - tg\theta_1}{1 + tg\theta_1tg\theta_2} = \frac{ab - mn}{bm + an}.$$

Vẫn còn phải sử dụng thực tế là $\theta = 45^\circ$ khi và chỉ khi $tg\theta = 1$. Đó là những gì được yêu cầu.

Bài tập
3. Thực hiện một phép tính đại số cho thấy hệ đẳng thức $b - m = a$ và $m = a - n$ ngụ ý (1).
4. Đặt $a, b, m, n$ là số dương. Chứng minh rằng từ (1) suy ra $b > n$ và $a > m$.

Bây giờ chúng tôi sửa $a, b, m, n$ và góc $\gamma$ cho phép thay đổi - chúng tôi có thể coi rằng chúng tôi có bản lề ACB với các dấu cố định $M$ và $N$ trên AC và CB. Khi đó góc $\theta$ phụ thuộc vào $\gamma$, tức là hàm $\theta = \theta(\gamma)$ cho $\gamma \in (0; \pi)$ được xác định. Bạn có thể quan sát (ví dụ: trong chương trình Geogebra) sự thay đổi trong $\theta(\gamma)$. Hãy chứng minh một số phát biểu về hành vi của $\theta(\gamma)$.

Phát biểu 2. Cho $a > m$ và $b > n$. Sau đó, thứ tự $\theta(\gamma)$ giảm dần trong khoảng $(0; \pi)$.

Trước khi chứng minh nhận định này, chúng ta hãy phát biểu hệ quả tất yếu sau đây.

Kết quả. Giả sử (1) được thỏa mãn. Khi đó: $\theta > 45^\circ$ nếu và chỉ khi $\gamma < 90^\circ$, $\theta = 45^\circ$ nếu và chỉ khi $\gamma = 90^\circ$, $\theta < 45^\circ$ nếu và chỉ nếu $\gamma > 90^\circ$.

Bằng chứng. Thật vậy, từ Bài tập 4, chúng ta biết rằng (1) sẽ làm nổi bật $a > m$ và $b > n$. Sau đó, mọi thứ diễn ra theo câu 1 và 2: $\theta(\gamma)$ thứ tự giảm dần và ngoài ra, đẳng thức $\theta\left(\frac{\pi}{2}\right) = \frac{\pi}{4}$ được thỏa mãn. Cuộc điều tra đã được chứng minh.

Chúng ta hãy nhớ lại bài toán M2809 (chúng tôi trình bày công thức của nó trong ký hiệu của mình) và giả sử rằng nó ngay sau Tuyên bố 2.

Nhiệm vụ 2 (M2809). Biết AM = BC và CM = BN. Tìm $\gamma$ nếu bạn biết rằng $\gamma = 2\theta$.

Đầu tiên là lời giải. Như chúng ta đã thấy, hệ quả là, vì $\gamma < 90^\circ$ $2\theta > 2\cdot 45^\circ > \gamma$ được đáp ứng và với $\gamma > 90^\circ$ $2\theta < 2\cdot 45^\circ < \gamma$ được thỏa mãn. Điều này có nghĩa là $\gamma = 90^\circ$ là giá trị duy nhất có thể có.

Ở cuối bài viết này, chúng tôi sẽ trình bày một hình học ngắn gọn, trang nhã khác lời giải bài toán M2809 không dựa vào bất kỳ tuyên bố nào khác trong bài viết.

Không, bây giờ chúng ta hãy tiếp tục nghiên cứu.

Bằng chứng cho Tuyên bố 2. Đặt $x = \cos \gamma$, $y = -\cos \theta$. Chúng ta chỉ cần hiểu rằng hàm $y(x)$ tăng nghiêm ngặt trên khoảng $x \in [-1; 1]$ là đủ. Dưới đây chúng tôi sẽ tính toán $y(x)$ một cách rõ ràng.

Ta hãy hoàn thiện tam giác AMB bằng hình bình hành AMBP (hình 4) sao cho BP = AM = $b - m$, $\angle NBP = 180^\circ - \gamma$, $\angle NAP = \theta$.

⟦folio 31⟧

---
running_head:
folio:
---

tất cả các giá trị từ tích phân $\left[ \theta \left( \gamma_0 \right); 0 \right)$. Ngoài ra, $\theta \left( \gamma_0 \right) < \pi/2$.

Bằng chứng. Vì $a < m$, rồi $p < 1$ và từ công thức cho $y(x)$, chúng ta thấy rằng $y(x) \in (-1; 0)$ tại $x \in (-1; 1)$, và ngoài ra, $y(\pm 1) = -1$. Bây giờ, vẫn phải hiểu rằng có $x_0 \in (-1; 1)$ sao cho $y(x)$ hoàn toàn quay trở lại ở $x \in [-1; x_0]$ và tiêu diệt hoàn toàn ở $x \in [x_0; 1]$, và ngoài ra, $x_0 > 0$.

Tính toán tùy ý cho:

$$y'(x) = \frac{ux + v}{2\left(\sqrt{1 - qx}\sqrt{1 - rx}\right)^3},$$

ở đâu $u = 2qr - pq - pr$, $v = 2p - q - r$. Chúng ta thấy rằng (vì $y(x)$ không phải là hàm hằng) một $y'(x)$ tùy ý chỉ có thể chuyển về 0 tại một điểm $\left(x_0 = -\frac{v}{u}\right)$, tương ứng, dấu $y'(x)$ chỉ có thể thay đổi không quá một lần (chỉ tại điểm $x_0$). Điều này có nghĩa là $y(x)$ hoàn toàn đơn điệu trên $[-1; 1]$ hoặc $[-1; 1]$ được chia cho điểm $x_0$ thành hai khoảng đơn điệu nghiêm ngặt. Tùy chọn đầu tiên là không thể vì $y(\pm 1) = -1$. Điều này có nghĩa là $x_0 \in (-1; 1)$, và vì $y(x) > -1$ trong khoảng $x \in (-1; 1)$, $y(x)$ phải hoàn toàn quay trở lại ở $x \in [-1; x_0]$ và tiêu diệt nghiêm ngặt ở $x \in [x_0; 1]$.

Vẫn còn phải xem rằng $x_0 = -\frac{v}{u} > 0$. Chúng ta đã biết rằng $y'(x) > 0$ tại $x \in [-1; x_0]$ và $y'(x) < 0$ tại $x \in (x_0; 1]$. Cụ thể, $y'(-1) > 0$, từ đó $-u + v > 0$ và $y'(1) < 0$, do đó $u + v < 0$. Từ đây chúng ta có được $u < 0$. Hãy chứng minh rằng $v > 0$ bằng cách thay thế trực tiếp: đặt $s = \frac{a}{m}$, $t = \frac{n}{b}$ (vì vậy $s > t$) và biến đổi

$$\frac{v}{2} = p - \frac{q}{2} - \frac{r}{2} = \frac{s + t}{st + 1} - \frac{s}{s^2 + 1} - \frac{t}{t^2 + 1} = \frac{(s - t)^2(s + t)}{(st + 1)(s^2 + 1)(t^2 + 1)} > 0.$$

Tuyên bố đã được chứng minh.

Để kết luận, như đã hứa, chúng tôi trình bày lời giải bài toán 2, không dựa trên kết quả thống kê. lời giải này được đặt ra bởi người tham gia Olympic Vasil Vasilev.

Thứ hai lời giải bài toán M2809. Vì vậy, $AM = BC, CM = BN, \angle ACB = \gamma, \angle AOM = \frac{\gamma}{2}$.

1) Hãy hoàn thiện hình tam giác $ABC$ thành hình bình hành $ACBQ$ (hình 5). Sau đó $\angle QAM = 180^\circ - \angle ACB = 180^\circ - \gamma$. Và vì $AM = BC = AQ$, từ tam giác đều $AMQ$ ta có $\angle AQM = \frac{180^\circ - \angle QAM}{2} = \frac{\gamma}{2}$. Chúng ta thấy rằng $\angle AQM = \angle AOM$, nghĩa là các điểm $A, Q, O, M$ nằm trên cùng một đường tròn.

2) Bây giờ trên đoạn $BQ$ chúng ta lấy điểm $R$ sao cho $BR : RQ = CM : MA$ (sao cho $AMRQ$ và $MCBR$ là hình bình hành). Sau đó $\angle CBR = 180^\circ - \angle ACB = 180^\circ - \gamma$. Và vì $BR = CM = BN$, từ tam giác đều $BRN$ ta có $\angle BRN = \frac{\gamma}{2}$. Chúng ta thấy rằng $\angle BRN = \angle BON$, nghĩa là các điểm $B, R, O, N$ nằm trên cùng một đường tròn.

3) Hơn nữa, từ vòng tròn (BRON), chúng ta thấy rằng $\angle ROB = \angle RNB = \frac{\gamma}{2}$. Nhưng từ số góc trước đó $\angle RQM = \angle RQA - \angle MQA = \gamma - \frac{\gamma}{2} = \frac{\gamma}{2}$. Điều này có nghĩa là $\angle ROB = \angle RQN$ đang mở; từ đó suy ra tứ giác $MQRO$ nội tiếp.

4) Vì vậy, cả năm điểm $A, Q, O, M, R$ đều nằm trên cùng một đường tròn. Từ đây phát biểu bài toán ngay sau đó, do đó $AQRM$ là hình bình hành nội tiếp, nghĩa là nó là góc vuông, $\gamma = \angle AQB = 90^\circ$ mở.

Bài tập 7. Thay bước 3) lời giải bằng chứng minh $AQRO$ là tứ giác nội tiếp.
