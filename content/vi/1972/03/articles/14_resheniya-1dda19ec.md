---
id: 1972-3-resheniya-1dda19ec
issue: kvant_1972_3
year: 1972
number: "3"
title: Lời giải bài toán M89—M95; F100—F107
rubric: zadachnik-kvanta
rubric_sub: Задачник «Кванта»
page_first: 42
page_last: 51
page_labels: 40, 41, 42, 43, 46, 47, 49
tag: ER8K
lang: vi
source: kvant_digital
extraction: vision
content_sha256: bb62a3fdbd52820aa6ec5574cc91dc3bd5d1c9434ccd345df5111ec8141e8d39
prompt_sha256: draft-1
translated_from: content/ru/1972/03/articles/14_resheniya-1dda19ec.md
source_content_sha256: d93f46e13f286f7c2631739b298e401e4b66d59d809d98ea5a0505bed5f79911
translation_model: draft
translation_run: vi-draft-2026-10-31
translation_quality: draft
---

⟦folio 40⟧

Lời giải

Trong số này chúng tôi xuất bản lời giải bài toán
M89—M95; F100—F107

M89
Lời giải trong số bài toán này có trong ghi chú của I. M. Yaglom ở trang 28.

M90
Chứng minh rằng nếu $x_1 < x_2 < x_3 \dots$ là số tự nhiên thì
$$\frac{\sqrt{x_2-x_1}}{x_2} + \frac{\sqrt{x_3-x_2}}{x_3} + \dots + \frac{\sqrt{x_n-x_{n-1}}}{x_n} < 1 + \frac{1}{2} + \frac{1}{3} + \dots + \frac{1}{n^2} + \frac{1}{n^3} + \frac{1}{n^4}.$$

Trước tiên chúng ta hãy giả sử rằng $x_n \leq n^2$. Sau đó
$$\frac{\sqrt{x_i-x_{i-1}}}{x_i} \leq \frac{x_i-x_{i-1}}{x_i} = \frac{1}{x_i} + \frac{1}{x_i} + \dots + \frac{1}{x_i}.$$
$$x_i - x_{i-1} \text{ слагаемых}$$

Tổng cuối cùng hiển nhiên không vượt quá tổng chứa cùng số số hạng
$$\frac{1}{x_{i-1}+1} + \frac{1}{x_{i-1}+2} + \dots + \frac{1}{x_i} + \frac{1}{x_i-1} + \frac{1}{x_i}.$$

không thì
$$\sum_{i=1}^{n} \frac{\sqrt{x_i-x_{i-1}}}{x_i} < \frac{1}{x_0+1} + \dots + \frac{1}{x_1} + \frac{1}{x_1+1} + \dots + \frac{1}{x_i} + \dots + \frac{1}{x_{n-1}+1} + \dots + \frac{1}{x_n} < \frac{1}{2} + \frac{1}{3} + \dots + \frac{1}{n^2} < 1 + \frac{1}{2} + \frac{1}{3} + \dots + \frac{1}{n^2}.$$
Bây giờ giả sử rằng trong số các số $x_0, x_1, x_2, \dots, x_n$ có số lớn hơn $n^2$. Nếu $x_i > n^2$ thì
$$\frac{\sqrt{x_i-x_{i-1}}}{x_i} < \frac{\sqrt{x_i}}{x_i} = \frac{1}{\sqrt{x_i}} < \frac{1}{n}.$$
Do đó, số hạng nào có giá trị $x_i$ lớn hơn $n^2$ nhỏ hơn $\frac{1}{n}$.
Do đó, tổng của tất cả các số hạng như vậy (không có nhiều hơn $n$) nhỏ hơn 1. Nhưng tổng của các số hạng còn lại, như được trình bày ở trên, nhỏ hơn $\frac{1}{2} + \frac{1}{3} + \dots + \frac{1}{n^2}$, điều này hoàn thành việc chứng minh bất đẳng thức(*)

Yu. I. Ionia

⟦folio 41⟧

M91
Lời giải bài toán M91 có ghi chú riêng “Môi trường của Thập” ở trang 24.

M92
Petya sẽ dành toàn bộ 90 ngày trong kỳ nghỉ của mình ở làng, đồng thời tuân thủ nghiêm ngặt lịch trình sau: mỗi ngày thứ hai (tức là cách ngày) anh ấy đi bơi trong hồ, mỗi ngày thứ ba anh ấy đến cửa hàng tạp hóa và mỗi ngày thứ năm anh ấy giải được bài toán trong toán học. (Vào ngày đầu tiên, Petya làm cái này, cái kia, cái thứ ba, và rất mệt.) Petya sẽ có bao nhiêu ngày “vui vẻ” khi nó cần bơi nhưng không cần phải đến cửa hàng và quyết định bài toán? Sẽ “nhàm chán” thế nào khi chẳng có gì để làm cả?

bài toán này đã thu hút sự chú ý của rất nhiều độc giả. Đây là thông tin chi tiết của cô ấy lời giải.
Hãy đánh số tất cả các ngày: 1, 2, 3, ..., 90.
Hãy cùng xem Petya đã đi bơi bao nhiêu lần. Anh ấy đã làm điều này vào ngày đầu tiên, và sau đó là những ngày khác. Điều này có nghĩa là anh ấy đã đi bơi vào những ngày có số lẻ (Hình 1). Có 90:2=45 ngày như vậy. Kết quả là anh ấy đã đi bơi 45 lần.

Theo cách tương tự, bạn có thể tìm ra bao nhiêu ngày anh ấy đến cửa hàng và bao nhiêu ngày anh ấy quyết định bài toán. Anh ta đến cửa hàng vào những ngày mà các số khi chia cho 3 sẽ có số dư là 1. (Có 90:3 = 30 ngày như vậy (Hình 2)). Và bài toán đã giải quyết vào những ngày mà số của chúng khi chia cho 5 sẽ có số dư là 1. (Có 90:5=18 những ngày như vậy (Hình 3)).

Tuy nhiên, để biết có bao nhiêu ngày Petya (a) bơi và đến cửa hàng, (b) bơi và làm toán, (c) đến cửa hàng và làm toán, và (d) bơi, đến cửa hàng và làm toán. Để không quyết định riêng cái nào trong số bài toán này, chúng ta cần một bổ đề tổng quát như vậy.

Bổ đề. Trong số các số tự nhiên nhỏ hơn N, số dư q khi chia cho n cho $$\frac{N-1-q}{n} + 1$$ số (q≠0). (Hãy nhớ rằng [x] biểu thị một số nguyên

Hình 1.

Hình 2.

Hình 3.

Hình 4.

Hình 5.

phần của số x: số nguyên lớn nhất không vượt quá x.)

Chứng minh bổ đề. Số dư q khi chia cho n được cho bởi các số

q, q+1·n, q+2·n, ..., q+kn, ...

Vì chúng ta chỉ quan tâm đến các số nhỏ hơn N nên chúng ta cần tìm một số nguyên k sao cho q+kn<N≤q+(k+1)n. Chúng ta hãy viết lại bất đẳng thức này như sau:

$$kn \leq N-1-q < (k+1)n,$$

và cuối cùng như thế này: $k \leq \frac{N-1-q}{n} < k+1$. Do đó, $k = \frac{N-1-q}{n}$, và tổng số các số nhỏ hơn N và cho số dư q khi chia cho n là $$\frac{N-1-q}{n} + 1$$ (số xuất hiện do số $q=q+0\cdot k$).

Bây giờ thật dễ dàng để nhận được đáp số cho các câu hỏi a, b, c và d. Thật vậy, mỗi câu hỏi này có thể được phát biểu lại như sau: Có bao nhiêu số tự nhiên nhỏ hơn 91 khi chia cho n_i còn dư 1, trong đó n_i phụ thuộc vào câu hỏi: $n_a=6$, $n_b=10$, $n_c=15$ và $n_d=30$. Thay thế những con số này vào công thức của chúng tôi, chúng tôi nhận được rằng đó là:

⟦folio 42⟧

15 ngày Peta bơi và đến cửa hàng;
9 ngày Peta tắm và quyết định bài toán;
6 ngày Peta đến cửa hàng và giải quyết bài toán;
3 ngày Peta bơi, đến cửa hàng và quyết định bài toán.
Bây giờ chúng ta đã có thể tính được có bao nhiêu ngày “nhàm chán” và bao nhiêu ngày “vui vẻ”. Tổng cộng, Peta đã ở trong làng 90 ngày. Trong 3 ngày anh ấy đã làm ba việc, 15+9+

Hình 6.

Hình 7.

Hình 8.

42

+6=30 ngày - ít nhất hai thứ và 45+30+18=93 ngày - ít nhất một thứ. Vì vậy (xem Hình 4, 5) anh ấy không làm gì trong 90-93+30-3=24 ngày. Vậy là có 24 ngày “nhàm chán”. Số ngày “vui vẻ” được tính theo cách tương tự: tổng cộng Peta đã bơi trong 45 ngày, anh ấy đã bơi và làm việc khác trong 15 + 9 = 24 ngày, và cuối cùng, anh ấy đã làm cả ba việc trong 3 ngày. Cuối cùng, có 45—24+3=24 ngày “vui vẻ”.

M93
Mỗi số $x_1, x_2, \dots, x_n$ đều bằng mặt phẳng hoặc trừ một. Người ta biết rằng
$$x_1x_2+x_2x_3+\dots+x_{n-1}x_n+x_nx_1=0.$$
Chứng minh rằng $n$ chia hết cho số chẵn.

Vì tổng $x_1x_2+x_2x_3+\dots+x_nx_1$ bằng $n$ số hạng nên $n$ là số chẵn—số đơn vị trừ trong tổng này bằng số mặt phẳng. Vẫn còn phải chứng minh rằng số đó là âm một. Để làm điều này, hãy nhân tất cả các số hạng
$$x_1x_2 \cdot x_2x_3 \cdot x_3x_4 \cdot \dots \cdot x_nx_1=x_1^2x_2^2 \cdot \dots x_n^2=1.$$
Đối với Pozny, số số âm thực sự là số chẵn và $n$ chia hết cho 4.

M94
Chứng minh rằng không có khối đa diện nào có ít nhất 4 cạnh kề với mỗi đỉnh và mỗi mặt.

Chúng ta hãy giả sử rằng một khối đa diện như vậy tồn tại. Gọi $\alpha_1, \alpha_2, \dots, \alpha_k$ là các góc phẳng của các mặt của nó. Hãy tính theo hai cách khác nhau giá trị trung bình số học của chúng bằng nhau. Hãy nhóm các góc theo khuôn mặt. Khi đó, vì mỗi mặt có ít nhất bốn góc nên giá trị trung bình số học của các góc của nó ít nhất là 90°. Từ đây suy ra ngay rằng giá trị trung bình số học của tất cả các góc không nhỏ hơn 90°. Bây giờ hãy nhóm chúng theo các đỉnh. Vì mỗi đỉnh liền kề với ít nhất bốn góc và tổng tất cả các góc tại một đỉnh nhỏ hơn 360°, nên trung bình số học của các góc tại một đỉnh nhỏ hơn 90°*). Nhưng khi đó giá trị trung bình số học của tất cả các góc đều nhỏ hơn 90°. Và, như chúng tôi đã chứng minh ở trên, nó không nhỏ hơn 90°. Mâu thuẫn thu được chứng tỏ rằng các khối đa diện lồi như vậy không tồn tại.

Có thể thu được lời giải bài toán khác dựa trên công thức Euler**). Cho phép

*) Ở đây ta sử dụng tính lồi của khối đa diện. Như một số độc giả của chúng tôi đã nhận thấy, có thể xây dựng một khối đa diện không lồi có một “lỗ”, trong đó mỗi mặt là một tứ giác và bốn cạnh gặp nhau ở mỗi đỉnh (xem Hình 6).

**) Bạn có thể đọc về công thức Euler trong cuốn sách: R. Courant và G. Robbins, What is math?, Enlightenment, 1967.

⟦folio 43⟧

Trong một vòng các đỉnh, $P$ là các cạnh và $\Gamma$ là các mặt của khối đa diện. Khi đó đối với một khối đa diện lồi (và nói chung đối với một khối đa diện không có lỗ xuyên qua), đẳng thức sau đây là đúng:

$$B - P + \Gamma = 2.$$

Trong khối đa diện của chúng ta, mỗi đỉnh có ít nhất bốn cạnh. Vì vậy $P \geq \frac{4B}{2}$. (Chúng ta phải chia đôi vì mỗi cạnh liền kề với hai đỉnh.) Tương tự, vì mỗi đỉnh liền kề với ít nhất bốn cạnh, $P \geq \frac{4F}{2}$.

Do đó, $2P \geq 2(B + \Gamma)$, tức là $P \geq B + \Gamma$, và theo công thức Euler, $B + \Gamma = P + 2$. Do đó, từ sự tồn tại của một khối đa diện với các tính chất đã chỉ ra, sẽ dẫn đến $P \geq P + 2$, điều này mâu thuẫn.

**M95**

Một hình thang được đánh dấu trên bảng, đường giữa $EF$ được vẽ trong đó và đường vuông góc $OK$ được thả từ điểm $O$ giao điểm của các đường chéo đến một đáy lớn. Sau đó hình thang đã bị xóa. Làm cách nào để khôi phục bản vẽ bằng cách sử dụng các phân đoạn được bảo toàn $EF$ và $OK$ (Hình 7)?

Xây dựng một hình thang. Chúng ta vẽ một đường thẳng $l$ đi qua điểm $K$, song song với đoạn thẳng $EF$. Hãy tìm phần giữa $M$ của đoạn $EF$. Hãy tìm điểm $N$ giao điểm của đường $l$ và đường $OM$. Chúng ta hãy dựng một hình bình hành với các đỉnh $E$, $N$ và $F$, trong đó đoạn $EF$ là một đường chéo. Hãy biểu thị đỉnh thứ tư của nó bằng $P$. Chúng ta hãy vẽ một đường thẳng $l'$ song song với $l$ đi qua nó. Chúng ta vẽ các đường thẳng đi qua các điểm $O$, song song với các cạnh của hình bình hành $ENFP$. Các điểm mà các đường này giao với đường $l$ và $l'$ là các đỉnh của hình thang.

Cách xây dựng của chúng tôi dựa trên thực tế là đường thẳng $OM$ chia hai đáy của hình thang làm đôi. Chúng tôi để lại chứng minh cho sự kiện đơn giản này và chứng minh tính đúng đắn của cách xây dựng cho người đọc. (Ngoài ra, chúng tôi đã lợi dụng thực tế là đường giữa của tam giác song song với cạnh của nó.)

Có thể thu được lời giải bài toán khác dựa trên thực tế là điểm $Q$ giao điểm của các cạnh bên mở rộng trên đường $OM$ và tỷ lệ khoảng cách đến các đường $l$ và $l'$ đối với điểm $O$ Q là như nhau. Bằng cách sử dụng điều này, sau khi các đường $l$ và $l'$ đã được tạo, bạn có thể tạo điểm $Q$ và nối nó với các điểm $E$ và $F$, tìm các đỉnh của hình thang.

Học. Chúng ta hãy xem xét các trường hợp khác nhau về vị trí của các đoạn $EF$ và $OK$.

1. Điểm $O$ nằm trên đoạn $EF$. Khi đó không có lời giải (nếu điểm $O$ là trung điểm của đoạn $EF$ thì đường thẳng $OM$ có thể được vẽ gần như tùy ý - bất kỳ

⟦folio none⟧

Hình 11 giờ sáng

Một hình thang chỉ thu được nếu đoạn OM ngắn hơn đoạn MN (Hình 9, a, b). Nếu các đoạn OM và MN bằng nhau thì bạn sẽ có một hình tam giác (Hình 10). Nếu OM lớn hơn MN thì thu được “hình thang tự giao nhau” (Hình 11, a, b).

Đúng lời giải bài toán đã gửi:
N. Bashkina (Kurgan-Tube) M92; S. Buu-bamrin (Glodyany MSSR) M92; A. Alyaev (Pachelmy, vùng Penza) M92, M95; A. Bueay (Izyaslav) M93, M95; V. Gamolin (Odessa) M93—M95; V. Goncharenko (Maykop) M95; V. Afanasyev (Kolomna) M95; O. Volkov (Sverdlovsk) M95; O. Viner (làng Gorodovka, vùng Vinnytsia) M92, M95; A. Dovzhkov (Leningrad) M95; V. Zubarev (Arkhangelsk) M95; I. Bramovskaya (Usolye-Sibirskoye) M92; A. Zaslavsky (Kalinin) M95; G. Zlatkus (Sovetsk, vùng Kaliningrad) M92; V. Zaporozhskaya (làng Sosnitsy, vùng Chernigov) M92, M95; A. Golbere (Moscow) M92—M95; V. Korenyako (Voronezh) M92, M94, M95; A. Nikolaev (Moscow) M92—M94; V. Gritsetsich (Chortkiv, vùng Ternovol) M93, M94; T. Kislitsa (làng Sharanga, vùng Gorky) M95; S. Belchko (Dokuaevsk, vùng Donetsk) M95; Yu. Kisin (Staraya Russa) M95; R. Kosoy (Odessa) M92, M95; L. Knizhnerman (Moscow) M92; L. Lazareva (Leningrad) M92; V. Lozinov (Moscow) M93; T. Casanov (Tbilisi)

Hình 11b.

M95; A. Gritsoryan (Baku) M93, M94; M. Illarinov (Voronezh) M92, M93, M95; A. Sboev (pss. Medvedok, vùng Kirov) M92, M93, M95; A. Kolchtsov (Gorky) M92, M95; A. Kutsukov (Baku) M92, M93, M95; A. Slinin (Lazovaya, vùng Kharkov) M94; Yu. Polonsky (Zelenodolsk) M95; V. Nadezhko (Leningrad) M95; L. Rudtser (Kharkov) M95; V. Terentyev (Pavlov, vùng Gorky) M92; G. Makarov (Zlatoust, vùng Chelyabinsk) M93, M95; V. Slepchenko (Chelyabinsk) M92, M93, M95; S. Muklytsin (Novosibirsk) M92; I. Porumchikova (Sokolniki, vùng Tula) M92; M. Rozov (Minsk) M92—M95; M. Preeer (Tomsk) M94—M95; E. Turkevich (Chernivtsi) M92—M95; P. Sereev (Grozny) M95; A. Slikin (Moscow) M92; A. Shmaev (Moscow) M92, M93, M95; A. Udaltsov (Kalinerrad, vùng Moscow) M92, M93, M95; O. Khudaverdyan (Yerevan) M93, M95; R. Shtsanov (Lyubertsy, vùng Moscow) M92, M93; G. Fi lkovsky (Baku) M92, M95; Yu. Yakushiin (Lomonosov) M92; E. Chasovnikov (làng Parygino, quận Zyryanovsky) M92; I. Yuurgel (Glubokoe BSSR) M92; S. Chekmarev (Moscow) M93; N. Famkulin (Kazan) M93, M95; A. Chernyak (Minsk) M92, M93, M95; V. Malchenko (Slavyansk-on-Kuban) M92; R. Soltsas (Vilnius) M95; P. Sukhov (Saratov) M95; A. Sherstyuk (Nikolaev) M93, M95; L. Reznik (Leningrad) M92, M95.

L. Limanov

⟦folio 46⟧

F101

Một quả bóng được treo vào một lò xo rất mỏng có độ cứng $k$. Lúc đầu lò xo không bị giãn. Vận tốc tối đa mà quả bóng đạt được khi chuyển động là bao nhiêu? Khối lượng của quả bóng là $m$.

Hãy viết phương trình chuyển động của quả bóng. Có hai lực tác dụng lên nó: lực hấp dẫn $mg$ và lực căng của lò xo $F = kx$, trong đó $x$ là độ biến dạng của lò xo. Theo định luật thứ hai của Newton

$$mg - kx = ma.$$

Từ phương trình này, suy ra rằng gia tốc của quả bóng $a$ ban đầu hướng xuống dưới và giảm dần, sau đó bằng 0 tại $x = \frac{mg}{k}$, rồi quay trở lại nhưng lại hướng lên trên.

Tốc độ của quả bóng quay trở lại khi gia tốc của nó hướng xuống dưới và giảm khi nó hướng lên trên. Do đó, tốc độ của quả bóng đạt cực đại là $x = \frac{mg}{k}$.

Để tìm được nó, chúng ta viết ra định luật bảo toàn năng lượng. Nếu quả bóng rơi đến một khoảng cách $x$ thì thế năng của nó giảm $mgx$ và động năng của nó tăng $\frac{mv^2}{2}$ (trước đây nó bằng 0). Một phần thế năng của quả bóng, bằng $\frac{kx^2}{2}$, đã làm tăng thế năng biến dạng của lò xo. Đó là lý do tại sao

$$mgx = \frac{kx^2}{2} + \frac{mv^2}{2}.$$

Từ đây, với $x = \frac{mg}{k}$ chúng ta nhận được

$$v_{\text{max}} = g \sqrt{\frac{m}{k}}.$$

F102

Oxy và heli được trộn đều trong bình kín. Sau đó, một lỗ được tạo ra trên thành bình. Thành phần của chùm phân tử phát ra từ nó là gì?

Năng lượng của các phân tử khí chỉ phụ thuộc vào nhiệt độ của nó. Vì các khí trong bình ở trạng thái cân bằng và nhiệt độ của chúng bằng nhau nên

$$\frac{m_{\text{O}_2}v_{\text{O}_2}^2}{2} = \frac{m_{\text{He}}v_{\text{He}}^2}{2},$$

trong đó $v_{\text{O}_2}$ và $v_{\text{He}}$ là tốc độ chuyển động trung bình của các phân tử khí, $m_{\text{O}_2}$ và $m_{\text{He}}$ là khối lượng của chúng. Từ

46

Hình 12.

công thức này tuân theo công thức đó

$$\frac{v_{\text{O}_2}}{v_{\text{He}}} = \sqrt{\frac{m_{\text{He}}}{m_{\text{O}_2}}}.$$

Để đơn giản, chúng ta giả sử rằng các phân tử khí chỉ có thể chuyển động theo ba hướng vuông góc với nhau và tốc độ của tất cả các phân tử là như nhau và bằng tốc độ trung bình. Sau đó, một phần sáu số phân tử của mỗi chất khí di chuyển về phía lỗ. Trong thời gian $\Delta t$, những phân tử khí ban đầu ở khoảng cách không lớn hơn $v\Delta t$ tính từ lỗ bay ra khỏi bình. Nghĩa là, đây là các phân tử oxy nằm trong thể tích $v_{\text{O}_2}\Delta t \cdot s$ và các phân tử hydro nằm trong thể tích $v_{\text{He}}\Delta t \cdot s$ (s là diện tích của lỗ). Tổng số phân tử oxy như vậy là $N_{\text{O}_2} = v_{\text{O}_2}sn_{\text{O}_2}\Delta t$ và phân tử gel $N_{\text{He}} = v_{\text{He}}sn_{\text{He}}\Delta t$, trong đó $n_{\text{O}_2}$ và $n_{\text{He}}$ là số lượng phân tử oxy và gel trên một đơn vị thể tích. Nếu có số lượng phân tử của cả hai loại khí bằng nhau trong bình thì $n_{\text{O}_2} = n_{\text{He}}$ và

$$\frac{N_{\text{O}_2}}{N_{\text{He}}} = \frac{v_{\text{O}_2}}{v_{\text{He}}} = \sqrt{\frac{m_{\text{He}}}{m_{\text{O}_2}}} = \frac{1}{2\sqrt{2}}.$$

Nếu khối lượng khí trong bình bằng nhau thì $m_{\text{O}_2}n_{\text{O}_2} = m_{\text{He}}n_{\text{He}}$ và

$$\frac{N_{\text{O}_2}}{N_{\text{He}}} = \frac{v_{\text{O}_2}}{v_{\text{He}}} \cdot \frac{n_{\text{O}_2}}{n_{\text{He}}} = \sqrt{\frac{m_{\text{He}}}{m_{\text{O}_2}}} \cdot \frac{m_{\text{He}}}{m_{\text{O}_2}} = \frac{1}{16\sqrt{2}}.$$

F103

Hai loạt phát đạn được bắn ra từ khẩu pháo, nghiêng nòng súng một góc $30^\circ$ và $40^\circ$ về phía chân trời. Trong trường hợp nào thì các cú đánh của đạn pháo sẽ tập trung hơn nếu sự lan rộng là do việc nhắm mục tiêu không chính xác chứ không phải do sự lan truyền của vận tốc đạn ban đầu? Sức cản của không khí nên được coi là không đáng kể.

Trước tiên chúng ta hãy tìm sự phụ thuộc của đường bay tiếp theo của đạn vào góc phóng của nó. Hãy viết nó ra

⟦folio 47⟧

đối với điều này, các phương trình động học của chuyển động của vật phóng. Nếu tốc độ của đạn bằng $v_0$ và góc mà đạn bay ra khỏi ordium bằng $\alpha$, thì theo phương thẳng đứng dọc theo trục $y$ đạn di chuyển với gia tốc $a=-g$ và tốc độ ban đầu $v_{0y}=v_0 \sin \alpha$. Do đó, sự thay đổi tọa độ $y$ của đạn được xác định theo phương trình

$$y = v_0 t \sin \alpha - \frac{g t^2}{2}.$$

Theo phương ngang dọc theo trục $x$, viên đạn chuyển động đều với tốc độ $v_x=v_0 \cos \alpha$. Đó là lý do tại sao

$$x = v_0 t \cos \alpha.$$

Tại thời điểm rơi xuống đất $y=0$ và $v_0 t \sin \alpha - \frac{g t^2}{2} = 0.$

Từ đây bạn có thể tìm thấy thời gian chuyển động của đạn. Nó bằng $t = \frac{2v_0 \sin \alpha}{g}$. Bây giờ thay biểu thức này vào phương trình chuyển động ngang, chúng ta thấy rằng tầm bay của viên đạn bằng

$$x_{\max} = \frac{2v_0^2 \sin \alpha \cos \alpha}{g} = \frac{v_0^2 \sin 2\alpha}{g}.$$

Đây là biểu thức cho mức cực đại tại sin $2\alpha=1$, tức là tại $\alpha=45^\circ$.

Hãy vẽ đồ thị về sự phụ thuộc của tầm bay của đạn vào $\alpha$ (Hình 12). Đối với những sai lệch nhỏ $\Delta \alpha$ của góc khởi hành của đạn, đồ thị phụ thuộc $x_{\max}(\alpha)$ có ​​thể được thay thế bằng một đường thẳng - tiếp tuyến với đồ thị thực $x_{\max}(\alpha)$. Độ dốc của tiếp tuyến này càng lớn thì sai số trong tầm bắn của đạn đối với cùng một sai số $\Delta \alpha$ về góc phóng của đạn càng lớn.

Từ Hình 12, rõ ràng là ở các góc khởi hành đạn nhỏ, góc nghiêng của tiếp tuyến với đường chân trời (với trục $0\alpha$) lớn hơn ở các góc lớn. Điều này có nghĩa là ở góc thoát của đạn nhỏ, sự thay đổi về phạm vi khi thay đổi góc thoát lớn hơn ở góc thoát lớn và với mũi tên có góc nòng $40^\circ$ thì độ chính xác của đạn sẽ cao hơn ở góc $30^\circ$.

Kết quả tương tự có thể thu được bằng cách sử dụng các công thức. Đặt sai số về góc thoát của đạn nhỏ và bằng $\Delta \alpha$. Khi đó lỗi $\Delta x$ trong phạm vi đạn là

$$\Delta x = \frac{v_0^2}{g} \sin 2\alpha - \frac{v_0^2}{g} \sin [2(\alpha + \Delta \alpha)] = 2 \frac{v_0^2}{g} \cos(2\alpha + \Delta \alpha) \sin \Delta \alpha \approx 2 \frac{v_0^2}{g} \cos 2\alpha \cdot \Delta \alpha.$$

Do đó, $\Delta x$ tỷ lệ thuận với $\Delta \alpha$, nhưng hệ số tỷ lệ phụ thuộc vào $\alpha$. Góc $\alpha$ càng nhỏ thì càng lớn.

F104

Trong một hộp kín có vài giọt chất lỏng có kích cỡ khác nhau. Điều gì sẽ xảy ra với anh ấy sau một thời gian dài?

Áp suất hơi bão hòa ở bề mặt giọt nước phụ thuộc vào bán kính của nó. Hãy thể hiện nó.

Chúng ta hãy tưởng tượng một bình kín trong đó có một ống mao dẫn, một chất lỏng không thấm nước. Áp suất tại điểm $B$ lớn hơn áp suất tại điểm $A$ (Hình 13) bởi các giá trị $\rho_{\pi}gh$:

$$P_B = P_A + \rho_{\pi}gh,$$

trong đó $h$ là chênh lệch mức chất lỏng trong mao quản và trong bình, $\rho_{\pi}$ là mật độ hơi.

Vì màng chất lỏng trong mao quản ở trạng thái cân bằng dưới tác dụng của hai lực: lực căng bề mặt bằng $2\pi r\sigma$ (σ là hệ số căng bề mặt, r là bán kính mao quản) và lực áp suất chất lỏng ở độ sâu $h$ bằng $\rho_{\pi}gh \cdot \pi r^2$ ($\rho_{\pi}gh$ là mật độ chất lỏng), nên $2\pi r\delta = \pi \rho_{\pi}ghr^2$.

Từ đây

$$h = \frac{2\sigma}{\rho_{\pi}gr}$$

Và

$$P_B = P_A + \frac{2\sigma}{r} \frac{\rho_{\pi}}{r_{\pi}}.$$

Do đó, bán kính giọt càng nhỏ thì áp suất trên bề mặt chất lỏng càng lớn. Điều này có nghĩa là nếu hơi nước bão hòa trên bề mặt của một giọt nhỏ thì trên bề mặt của giọt lớn hơn nó sẽ không bão hòa. Điều này sẽ khiến hơi nước ngưng tụ trên giọt lớn, từ đó ảnh hưởng đến áp suất hơi nước trên bề mặt giọt nhỏ. Điều này lại làm cho giọt nhỏ bay hơi. Kết quả là sau một thời gian chỉ còn lại một giọt lớn trong bình.

Kết quả tương tự có thể thu được từ lý luận chung nhất. Giả sử có chất lỏng trong bình (bề mặt của chất lỏng phẳng) và có một giọt nước.

⟦folio 49⟧

Từ phương trình thứ hai, tam giác này vuông góc và góc giữa các vectơ vận tốc điện là 90°

F107

Trong mạch như hình 16, vôn kế thay đổi điện áp rơi trên điện trở $R=300$ com. Điện trở của vôn kế phải bằng bao nhiêu để số chỉ của nó chênh lệch không quá 2% so với giá trị thực tế $u_R$? Sự phản kháng nội bộ của nguồn khiếu nại.

Trong trường hợp không có vôn kế, các điện trở $R$ và $R_1$ được bật nối tiếp. Do đó, điện áp rơi trên điện trở $R$ bằng $u_R = \frac{R}{R+R_1} E$. Khi nối vôn kế vào sẽ làm thay đổi độ sụt áp trên đoạn gồm các điện trở mắc song song $R$ và điện trở vôn kế $r$. Vôn kế hiển thị giá trị

$$u' = \frac{Rr}{R+r} E$$

Tùy theo điều kiện, số đọc của vôn kế không được chênh lệch quá 2% so với giá trị $u_R$. Đó là lý do tại sao

$$\frac{u_R - u'}{u_R} \leq 0,02.$$

Thay các biểu thức của $u_R$ và $u'$ vào phương trình này, chúng ta thấy rằng điện trở của vôn kế không được vượt quá 3675 kΩ.

Đúng lời giải gửi bởi: V. Avseikov (Sevastopol) $\Phi 103$, $\Phi 105$—$\Phi 107$; A. Alexandrov (Glazov UASSR) $\Phi 100$; P. Amosov (Yaroslavl) $\Phi 100$; S. Araslanov (Nizhne-Ivkino, vùng Kirov) $\Phi 103$, $\Phi 107$; V. Belov (Vologda) $\Phi 100$—$\Phi 105$, $\Phi 107$; A. Blokhin (Kiselevsk, vùng Kemerovo) $\Phi 106$, $\Phi 107$; L. Brachinsky (Frunze) $\Phi 101$; A. Bratkovsky (Moscow) $\Phi 103$, $\Phi 104$, $\Phi 106$; A. Budnikov (Slavyansk, vùng Donetsk) $\Phi 101$; A. Buzulukov (Novosibirsk) $\Phi 107$; Y. Givi Dolidze (Tbilisi) $\Phi 101$; V. Glem-

$$R_1 = 100\text{ ком}$$

Botsky (Yaroslavl) $\Phi 101$, $\Phi 102$; E. Gromak (Novokuznetsk) $\Phi 103$, $\Phi 106$; M. Dzik (làng Kratovo, huyện Armavir, vùng Tyumen) $\Phi 101$, $\Phi 103$; A. Dovspevich (Moscow) $\Phi 101$; E. Dolov (Moscow) $\Phi 100$, $\Phi 101$; E. Domov (Moscow) $\Phi 03$, $\Phi 106$; G. Zaitsev (Gagra) $\Phi 101$, $\Phi 103$, $\Phi 106$, $\Phi 107$; S. Zanetsochny (Uzhgorod, vùng Transcarpathian) $\Phi 101$; N. Zykov (Saratov) $\Phi 101$; O. Zamova (Moscow) $\Phi 100$; A. Ivanov (Lgov, vùng Kursk) $\Phi 102$; Y. Imin (Thợ cắt vùng Gomel) $\Phi 101$; A. Istomin (Podolsk, khu vực Moscow) $\Phi 103$, $\Phi 105$; T. Casanov (Tbilisi) $\Phi 103$, $\Phi 106$; A. Karimov (Ufa) $\Phi 101$; T. Kislicina (làng Sharanga, vùng Gorky) $\Phi 105$, $\Phi 107$; Yu. Kisin (Staraya Russa) $\Phi 103$; L. Knizherman (Moscow) $\Phi 100$—$\Phi 103$; L. Kodan (Chernivtsi) $\Phi 101$; M. Kolodochkin (Moscow) $\Phi 101$; S. Korillov (Grozny) $\Phi 101$; V. Kolomitsev (Rostov-on-Don) $\Phi 101$; P. Konev (Plees, vùng Ivanovo) $\Phi 101$; V. Kamanov (làng Tsalka, GSSR) $\Phi 101$; V. Komenov (Moscow) $\Phi 101$; V. Krylov $\Phi 100$; S. Kuzmich (Zhitomir) $\Phi 103$, $\Phi 105$, $\Phi 107$; V. Kulii (làng Mogilno, vùng Brest) $\Phi 101$; V. Kuusk (Rzhev) $\Phi 100$, $\Phi 101$, $\Phi 104$, $\Phi 106$; G. Levi (Kuibytsev) $\Phi 101$; V. Lukashin (Moscow) $\Phi 101$; Yu. Lurie (Grozny $\Phi 101$; A. Mamula (làng Dobintsy, quận Boguslavsky, vùng Kyiv) $\Phi 101$, $\Phi 102$, $\Phi 107$; Yu. Murzanov (làng Rodinkovsky, Lãnh thổ Krasnodar) $\Phi 101$; M. Maron (Kuibytsev) $\Phi 100$, $\Phi 101$; I. Mats (Makeevka) $\Phi 100$; L. Menkova (Alexandrov, vùng Vladimir) $\Phi 101$; V. Nadezhko (Leningrad) $\Phi 101$, $\Phi 107$; A. Nikolaev (Sverdlovsk) $\Phi 107$; S. Pomashey (Ulyanovsk) $\Phi 100$, $\Phi 101$; Yu. Polonsky (Zelenodolsk TASSR) $\Phi 101$; M. Preer (Tomsk) $\Phi 100$, $\Phi 101$, $\Phi 105$, $\Phi 106$; L. Rudtser (Kharkov) $\Phi 101$, $\Phi 105$; L. Safulin (làng B. Vườn TASSR) $\Phi 107$; P. Sergeev (Grozny) $\Phi 100$, $\Phi 101$, $\Phi 103$, $\Phi 106$, $\Phi 107$; I. Sidorov (Moscow) $\Phi 100$, $\Phi 101$; G. Simonenkov (Quận) $\Phi 106$; M. Solomonovich (Chisinau) $\Phi 101$; E. Sychudov (làng vùng Krasnodar) $\Phi 101$; M. Taits (Moscow) $\Phi 101$; O. Tatarinskaya (Almaty) $\Phi 101$; I. Turishche (Kropotkin, Lãnh thổ Krasnodar) $\Phi 100$, $\Phi 102$, $\Phi 103$, $\Phi 105$, $\Phi 107$; A. Udaltsov (Kalinerrad, khu vực Moscow) $\Phi 105$; V. Faimelevich (Ramavir) $\Phi 100$—$\Phi 102$; G. Nhanh (Karagana) $\Phi 104$; I. Fedin (Omsk) $\Phi 100$—$\Phi 103$, $\Phi 105$, $\Phi 107$; G. Furmanov (Chernivtsi, Cộng hòa Xã hội chủ nghĩa Xô viết Ukraina) $\Phi 101$; M. Khomenenko (Vitebsk) $\Phi 102$; O. Khudaverdyan (Yerevan) $\Phi 103$, $\Phi 107$; S. Chekmarev (Moscow) $\Phi 100$—$\Phi 103$, $\Phi 105$, $\Phi 107$; E. Chasovnikov (làng parychino, huyện Zyknovsky) $\Phi 101$; S. Chernikov (Sempalatinsk) $\Phi 101$; Zh. Shenemko (D.-Gorodok, vùng Brest) $\Phi 103$, $\Phi 104$, $\Phi 107$; A. Sherstyuk (Nikolaev Ukraina SSR) $\Phi 107$; R. Shzaanov (Lyubertsy, vùng Moscow) $\Phi 101$; V. Shuvalov (Điện) $\Phi 101$; I. Yurenko (Kyiv) $\Phi 101$.
