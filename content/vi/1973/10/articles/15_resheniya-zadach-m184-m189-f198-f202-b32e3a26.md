---
id: 1973-10-resheniya-zadach-m184-m189-f198-f202-b32e3a26
issue: kvant_1973_10
year: 1973
number: "10"
title: Lời giải bài toán M184—M189; F198—F202
rubric: zadachnik-kvanta
rubric_sub: Задачник «Кванта»
page_first: 50
page_last: 57
page_labels: 48, 49, 50, 51, 52, 54
tag: U629
lang: vi
source: kvant_digital
extraction: vision
content_sha256: 7bea530050168beb88fd54c34e31484a8edf66431530b40bdf28e0fdce783f3d
prompt_sha256: draft-1
translated_from: content/ru/1973/10/articles/15_resheniya-zadach-m184-m189-f198-f202-b32e3a26.md
source_content_sha256: 0e25a83f4a77f655184e80a9c45cc4d56260b3e09587640a161073b3285dc64c
translation_model: draft
translation_run: vi-draft-2026-10-31
translation_quality: draft
---

⟦folio 48⟧

Lời giải bài toán
M184—M189; F198—F202

M184. Chứng minh Giáng sinh

$$\frac{C_n^0}{x} - \frac{C_n^1}{x+1} + \dots + (-1)^n \frac{C_n^n}{x+n} = \frac{n!}{x(x+1)(x+2)\dots(x+n)}$$

Chúng ta hãy chứng minh điều này bằng phương pháp quy nạp toán học. Với $n=1$ điều đó đúng vì $C_1^0 = C_1^1 = 1! = 1$:

$$\frac{C_1^0}{x} - \frac{C_1^1}{x+1} = \frac{1!}{x(x+1)}$$

Giả sử rằng điều này cũng đúng:

$$\frac{C_n^0}{x} - \frac{C_n^1}{x+1} + \frac{C_n^2}{x+2} - \dots + (-1)^{n-1} \frac{C_n^{n-1}}{x+n-1} + (-1)^n \times \frac{C_n^n}{x+n} = \frac{n!}{x(x+1)\dots(x+n)}$$

Chúng ta hãy thay thế $x$ trong (1) bằng $x+1$. Chúng tôi cũng nhận được:

$$\frac{C_n^0}{x+1} - \frac{C_n^1}{x+2} + \dots + (-1)^{n-1} \frac{C_n^{n-1}}{x+n} + (-1)^n \times \frac{C_n^n}{x+n} = \frac{n!}{x(x+1)\dots(x+n)}$$

Chúng ta hãy trừ số hạng theo số hạng (2) khỏi (1) và sử dụng thực tế là

$$C_n^0 = C_n^n = C_n^{n+1} = C_n^{n+1} = 1,$$

$$C_n^k + C_n^{k+1} = C_n^{k+1}$$

cho mỗi $k=0,1,2,\dots,n-1$. chúng tôi nhận được

$$\frac{C_n^0}{x} - \frac{C_n^1}{x+1} + \frac{C_n^2}{x+2} - \dots + (-1)^n \frac{C_n^n}{x+n} + (-1)^n \times \frac{C_n^{n+1}}{x+n+1} = \frac{n!}{x(x+1)(x+2)\dots(x+n)}$$

Như vậy bước quy nạp đã hoàn thành và đẳng thức của ta được chứng minh với mọi $n$.

Những ai đã đọc bài viết của V. N. Vaguten “Số $C_n^k$, dãy và đa thức” trong «Kvant» Số 2 (1973), tất nhiên nhận thấy rằng trong bài toán M184, chúng ta đã nhận được công thức tính hiệu bậc $n$ cho dãy $f(x) = \frac{1}{x}$:

$$\Delta^n f(x) = \frac{(-1)^n n!}{x(x+1)\dots(x+n)}$$

Nhiều độc giả đã đưa ra chứng minh cho nhận định sau về tính duy nhất của một danh tính dạng (1): nếu danh tính là đúng

$$\frac{n!}{x(x+1)\dots(x+n)} = \sum_{i=0}^{n} \frac{A_k}{x+k},$$

thức ăn $A_k$ – một số con số, có thể

$$A_k = (-1)^k C_n^k = \frac{(-1)^k n!}{k!(n-k)!}$$

Thật vậy, chỉ cần nhân cả hai vế của (4) với mẫu số chung $x(x+1)\dots(x+n)$ và đặt $x = -k$ vào đẳng thức thu được là đủ. Sau đó bên phải là tất cả các điều khoản ngoại trừ một

$$A_k(-k)(-k+1)\dots(-1)1\cdot2\dots\dots(n-k) = A_k(-1)^k k!(n-k)!$$

sẽ tiến tới 0 và chúng ta sẽ tiến đến (5).

M185. Trên kafman có diện tích 1, 5 ngọn lửa được đặt, diện tích của mỗi ngọn lửa không nhỏ hơn $1/2$. Chứng minh rằng có hai ngọn lửa có diện tích phần chung không nhỏ hơn $1/5$.

⟦folio 49⟧

Hình 1.

Chúng ta hãy biểu thị bằng $x_k$ diện tích của phần caftan được bao phủ bởi các miếng vá $k$ ($k = 0, 1, \dots, 5$). Theo điều kiện, diện tích của caftan là 1 và tổng diện tích của các miếng vá là $\frac{5}{2}$:
$$S_0 = x_0 + x_1 + x_2 + x_3 + x_4 + x_5 = 1,$$
$$S_1 = x_1 + 2x_2 + 3x_3 + 4x_4 + 5x_5 = \frac{5}{2}.$$

Tổng diện tích của tất cả 10 giao điểm theo cặp của các mảnh bằng
$$S_2 = x_2 + 3x_3 + 6x_4 + 10x_5 \geq -3x_0 - x_1 + x_2 + 3x_3 + 5x_4 + 7x_5 = 2S_1 - 3S_0 = 2,$$
Có thể, ít nhất một trong 10 giao điểm theo cặp sẽ có diện tích ít nhất là $\frac{2}{10} = \frac{1}{5}$ (chỉ có thể đạt được sự bình đẳng nếu $x_0 = x_1 = x_4 = x_5 = 0$ và tất cả 10 giao điểm theo cặp đều có diện tích bằng nhau!).

Lời giải bài toán M185, các biến thể và khái quát hóa khác nhau của nó, có liên quan chặt chẽ với một công thức chung thay thế cho các hàm tập hợp cộng—“công thức bao gồm và loại trừ”. Mối liên hệ này được thảo luận chi tiết trong một bài báo riêng “Các bản vá trên Caftan”, sẽ được đăng trên số 12 của tạp chí.

M186. Cho hai điểm $A$ và $B$ trên mặt phẳng. Chúng ta hãy tìm quỹ tích hình học của thị trường trước $C$ của tam giác $ABC$, trong đó:
a) chiều cao $AA'$ bằng cạnh $BC$;
b) trung tuyến $AA_1$ bằng cạnh $AC$;
c) đường trung tuyến $AA_1$ bằng cạnh $BC$;
d) chiều cao $CC'$ bằng trung tuyến $BB_1$;
e) chiều cao $BB'$ bằng trung vị $CC_1$.

a) Tập hợp yêu cầu của điểm $C$ sẽ rất đối xứng đối với đường thẳng $AB$; do đó, chỉ cần khảo sát các điểm nằm trên một trong các nửa mặt phẳng mà đường thẳng $AB$ chia mặt phẳng đó là đủ.

Chúng ta hãy xây dựng một điểm $D$ sao cho $DB \perp AB$ và $DB = BA$. Trong nửa mặt phẳng mà chúng ta sẽ xem xét, có một điểm $D$, rất indo, là điểm duy nhất. Nếu chiều cao của $AA'$ bằng $CB$ thì (Hình 2)
$$\Delta AA'B = \Delta CBD$$
(góc $A'AB$ và CBD bằng nhau, cả hai đều nhọn so với mặt phẳng, $AA' \perp BC$ và $AB \perp BD$). Như vậy,
$$\Rightarrow BCD = 90^\circ.$$

Ngược lại, nếu tại một điểm nào đó $C$ góc

⟦folio 50⟧

Hình 3.

VSD là trực tiếp, do đó, rõ ràng, ΔAA'B = ΔCBD và AA' = BC. Vì vậy, chỉ cần tìm tập hợp các điểm C thỏa mãn điều kiện (1) (B và D là các điểm cố định). Tập hợp này, như đã biết, là một đường tròn có đường kính BD.

6) Gọi E là một điểm trên phần kéo dài của đường trung tuyến AA1 sao cho A1E = AA1. Khi đó ACEB là hình bình hành (Hình 3). Điều kiện AA1 = AC tương đương với AE = 2BE.

(2) Chúng ta sử dụng định lý sau:

Nếu A và B là hai điểm cho trước của mặt phẳng thì tập hợp các điểm E của mặt phẳng mà $\frac{AE}{BE} = k$ (k là số dương cố định khác 1) là đường tròn dựng trên đường kính E1E2, trong đó E1 và E2 là các điểm trên đường thẳng AB.

$$\frac{AE_1}{BE_1} = k \quad u \quad \frac{AE_2}{BE_2} = k$$

(E1 nằm trong đoạn AB, E2 nằm ngoài đoạn này). Dưới đây chúng tôi nhắc lại ngắn gọn cách chứng minh định lý này *).

Từ định lý này suy ra rằng tập hợp các điểm E là một đường tròn có đường kính E1E2, E1 và E2 là các điểm trên đường thẳng AB và rằng

$$\frac{AE_1}{BE_1} = \frac{AE_2}{BE_2} = 2$$

*) Xem thêm sách: Vasiliev N.B., Gutenacher V.L. Đường thẳng và đường cong. M., “Khoa học”, 1970, tr. 22, 102 và Gelfand I.M., Glagoleva E.G., Kirillov A.A. Phương pháp tọa độ. M., “Khoa học”, 1968, tr. 32.

Hình 5.

d) Từ điểm B1, chính giữa cạnh AC, hạ đường vuông góc B1K xuống đường thẳng AB. Tất nhiên, CC' = 2B1K, do đó điều kiện CC' = BB1 tương đương với điều kiện này (Hình 5): BB1 = 2B1K (chân bằng đa giác của cạnh huyền). Do đó, ∠B1BK = 30°. Do đó, quỹ tích của điểm B1 là bốn tia phát ra từ điểm B tạo thành các góc 30° và 150° với đoạn AB. Tập hợp các điểm C thu được từ nó bằng cách giãn nở với hệ số 2 và tâm tại điểm A.

e) Gọi L là hình chiếu của điểm C1 (trung điểm của đoạn AB) lên đường thẳng AC. Vì (Hình 6) BB' = CC1 nên 2C1L = CC1 và ∠LCC1 = 30°. Do đó, ∠ACC1 bằng 30° hoặc 150°, và quỹ tích điểm C sẽ là một cặp đường tròn đi qua các điểm A và C1.

Hình 7 thể hiện đáp số đối với các bài toán M187 a)–d). Chúng ta không đưa các điểm C nằm trên chính đường thẳng AB vào tập hợp các điểm ban đầu (chúng dẫn đến các tam giác ABC “suy thoái”); cao hơn

⟦folio 51⟧

CHÚNG TÔI không lấy cắp nó theo từng trường hợp cụ thể để tiết kiệm dung lượng.

Chúng tôi đã nhận được rất nhiều lời giải bài toán M187 a)-e), nhưng hầu hết chúng đều có những thiếu sót (ví dụ: mất khả năng “sử dụng” đáp số, không có bằng chứng đầy đủ “theo cả hai hướng”, v.v.).

N. B. Vasiliev

M188. Giữa một số trong số 2n thành phố có khả năng liên lạc và mỗi thành phố được kết nối với ít nhất n thành phố khác (giải pháp không ngừng nghỉ). Chứng minh rằng ngay cả khi bạn hủy bất kỳ n—1 lời giải nào, bạn vẫn có thể đi từ bất kỳ thành phố nào đến bất kỳ thành phố nào khác bằng máy bay (có chuyển tuyến). Hãy liệt kê tất cả các trường hợp trong đó “sự liên thông” đó bị phá vỡ khi n lời giải bị hủy bỏ.

Giả sử rằng sau khi hủy một số l lời giải thì “sự kết nối” bị hỏng. Khi đó có thể có k thành phố với k  n sao cho không thể đi từ chúng đến 2n-k thành phố còn lại. Thật vậy, khoảng cách giữa các thành phố A và tất cả các thành phố mà bạn có thể đi từ đó đến (có thể bằng phương tiện trung chuyển). Nếu không có nhiều hơn n trong số chúng (cùng với A) thì cần tìm k thành phố.

Nếu có m và m > n thì không thể đi từ chúng đến các thành phố 2n-m còn lại và từ các thành phố 2n-m < n này cũng không thể đi đến m thành phố còn lại. Vì vậy, trong mọi trường hợp, có k thành phố, trong đó k ≤ n, từ đó không thể đi đến 2n-k thành phố còn lại. Ban đầu, mỗi thành phố trong số này được kết nối bằng avalins với ít nhất n thành phố, do đó, ít nhất n+1-k lời giải đã kết nối nó với k thành phố được phân bổ và do đó bị hủy bỏ. Điều này có nghĩa là tổng cộng ít nhất k(n+1-k) lời giải đã bị hủy. Nhưng k(n+1—k) > n—1 với k=1, 2, ..., n. Do đó, nếu chúng ta hủy n-1 lời giải thì “tính liên thông” không bị vi phạm.

Bây giờ chúng ta hãy trả lời câu hỏi thứ hai bài toán. Lưu ý rằng k(n+1—k) = n chỉ với k=1 và k=n. Nếu k=1, thì điều này có nghĩa là một số thành phố được kết nối với chính xác n thành phố và tất cả lời giải này đã bị hủy. Nếu k=n thì điều này có nghĩa là một số n thành phố A1, A2, ..., An được nối thành từng cặp bằng avallines, n thành phố còn lại A1′, A2′, ..., An′ cũng được kết nối thành từng cặp bằng avallines và có n lời giải nối các thành phố A1 và A1′, A2 và A2′, ..., An và An′. Trong Hình 8, bạn thấy sơ đồ avaline cho n=2 và n=3.

L. G. Limanov

M189. Ba đoạn thẳng AB, EF và CD đi qua một điểm O, điểm E nằm trên đoạn AC và điểm F nằm trên đoạn BD. Chứng minh rằng EF nhỏ hơn ít nhất một trong hai đoạn AB hoặc CD (Hình 9).

Chúng ta sẽ lợi dụng thực tế là độ dài đường phân giác trong một tam giác không vượt quá một nửa tổng độ dài các cạnh bao quanh nó (chứng minh điều này!). Giả sử đoạn EF dài hơn Δ so với đoạn AB, CD (max(AB, CD)). Đặt $\Rightarrow AOE \neq EOC$ - nếu không thì EF $\leq \frac{AB+CD}{2}$ và EF không thể có độ dài tối đa (AB, CD). Hãy để định nghĩa $\Rightarrow AOE > EOC$. Do đó, đoạn E1F1 (xem Hình 10) sao cho $\Rightarrow E1OE = EOC$. Rõ ràng điểm E1 thuộc đoạn AC và điểm F1 thuộc đoạn BD. EF $\leq \frac{CD+E1F1}{2}$, vậy nên E1F1 có chiều dài tối đa là 2Δ (AB, DC). Do đó, chúng ta có thể chuyển từ một phân đoạn “lớn hơn Δ” sang một phân đoạn “lớn hơn 2Δ”, trong đó Δ là một số dương. Sau khi lặp lại quá trình chuyển đổi này k lần, chúng ta thu được đoạn E1F1, dài hơn ít nhất 2^k·Δ so với max(AB, CD). Bằng cách chọn k đủ lớn, chúng ta có thể làm cho đoạn E1F1 có độ dài lớn hơn AB+CD, điều này là không thể. Mâu thuẫn thu được cho thấy đoạn EF không thể lớn hơn max(AB, CD). Nhiệm vụ lời giải.

Hình 7.

⟦folio 52⟧

Hình 8.

Hình 9.

Hình 10.

Đây là lời giải bài toán M189 thứ hai. Vẽ các đường thẳng đi qua E và F vuông góc với EF. Ta tiếp tục các đoạn OA, OB, OC, OD cho đến khi chúng cắt các đường thẳng này và có ký hiệu như trên Hình 11. Cho điểm A nằm bên trong dải giữa các đường thẳng đó, C - bên ngoài nó; thì D phải nằm bên trong dải (nếu không thì rất indo, CD > EF) và B phải nằm bên ngoài. Từ không

Hình 11.

sự bình đẳng

$$\frac{AA_2}{CC_2} = \frac{A_2E}{EC_2} \leq \frac{A_1E}{EC_1} = \frac{B_1F}{FD_1} \leq \frac{B_2F}{FD_2} = \frac{BB_2}{DD_2}$$

theo sau là $AA_2 \leq BB_2$ (và sau đó là $AB > EF$) hoặc $CC_2 \geq DD_2$ (và sau đó là $CD > EF$).

D. Yu. Grigoriev

F198. Vận động viên trượt băng quyết định giảm tốc độ và đưa các đoạn thẳng lại với nhau. Mặc dù khó khăn (vào ban đêm?), một vận động viên trượt băng có thể giữ các đường thẳng lại với nhau. Nó sẽ di chuyển dữ liệu như thế nào?

Rõ ràng, ở tốc độ thấp, vận động viên trượt băng giảm tốc độ, đưa các ngón chân lại với nhau chứ không phải gót chân. Chuyển động này của vận động viên trượt băng là ổn định. Tuy nhiên, vận động viên trượt băng sẽ bị ngã. Do đó, ở tốc độ cao, vận động viên trượt băng (như vận động viên khúc côn cầu) giảm tốc độ, quay cả hai giày trượt về một hướng. Tất nhiên, đồng thời, anh ta giảm tốc độ và đồng thời di chuyển sang một bên. Tuy nhiên, ngay cả khi có khả năng mang hai chân lại với nhau, một vận động viên trượt băng vẫn thường luân phiên cưỡi trên một hoặc một đôi giày trượt khác.

Khi lưỡi giày trượt nằm theo hướng chuyển động của người trượt băng, ván trượt dễ dàng trượt trên băng, tức là lực ma sát rất nhỏ. Nếu một vận động viên trượt băng muốn phanh lại, anh ta đặt giày trượt của mình ở một góc nhất định so với hướng chuyển động, và một lực ma sát khác xuất hiện, vuông góc với lưỡi dao. Độ lớn của lực này lớn hơn nhiều so với lực đầu tiên, vì trong trường hợp này, lưỡi giày trượt dường như được bao quanh bởi băng. Để đơn giản, sau này chúng ta sẽ chỉ nói về lực ma sát vuông góc với lưỡi dao này.

Hãy để vận động viên trượt băng cố gắng đưa gót chân của mình lại với nhau. Từ Hình 12, rõ ràng là trong trường hợp này, ngoài các lực cản $F_{c.1}$ và $F_{c.2}$ hướng theo tốc độ v, còn có các lực $F'_1$ và $F'_2$, có xu hướng di chuyển các đôi giày trượt ra xa nhau. Đây là lý do tại sao vận động viên trượt băng phải nỗ lực hết sức để giữ hai gót chân của mình lại với nhau.

Vận động viên trượt băng sẽ di chuyển như thế nào sau khi anh ta đã khép hai gót chân lại với nhau? Không khó để trả lời câu hỏi này, vì theo kinh nghiệm, người ta biết rằng trong trường hợp này vận động viên trượt băng sẽ quay lại và ăn ngược. Thật khó để giải thích tại sao điều này xảy ra. Một số yếu tố có vẻ quan trọng ở đây.

Một trong số đó là sự phụ thuộc của lực ma sát vuông góc với mặt phẳng của ván trượt vào góc tạo bởi mặt phẳng của ván trượt với hướng chuyển động của ván trượt. Nếu góc bằng 0 thì lực này cũng bằng 0; ở góc 90°, lực là cực đại. (Sự phụ thuộc của lực ma sát vào góc có liên quan.)

⟦folio 54⟧

Hình 13.
viết như thế này:

$$2 + \left( k + \frac{1}{k} \right).$$

Theo định lý giá trị trung bình*), tổng $k + \frac{1}{k}$ là tối thiểu khi các số hạng bằng nhau, tức là khi $k = \frac{1}{k}$ hoặc $k = 1$. Đồng thời $W_a = W_0$.

Vì vậy, neutron truyền phần động năng ban đầu tối đa của nó sang nguyên tử khi khối lượng của neutron và nguyên tử bằng nhau, như trường hợp nguyên tử hydro.

Ở $k = 207$, như trong trường hợp của chì, một neutron, khi va chạm với một nguyên tử, truyền cho nó khoảng $\frac{4}{209}$ động năng của nó.

Về nguyên tắc, mọi lập luận vẫn có giá trị đối với những tác động lệch tâm. Do va chạm của neutron với các nguyên tử vật chất xảy ra nhiều lần nên động năng ban đầu của neutron chuyển thành nhiệt khá nhanh.

Điều này giải thích thực tế là neutron được giữ lại tốt bởi nước, parafin hoặc các chất kết nối khác chứa nguyên tử hydro và dễ dàng đi qua các khối chì tương tự.

F200. Do sự phóng điện xung của tụ điện qua toàn bộ khối đã lọc, xảy ra hiện tượng cắt ở nhiệt độ $T$. Ước tính các giá trị $T$ nếu hướng trên tụ là $U = 30$ kV thì điện dung của tụ là $C = 18$ µF và khí chiếm thể tích 10 l ở áp suất $10^{-2}$ mm Hg. Nghệ thuật.

Để ước tính, chúng ta sẽ giả sử rằng khi một tụ điện phóng điện, toàn bộ năng lượng của nó chỉ được dùng để đốt nóng helium, nghĩa là để tăng năng lượng bên trong của nó. Vì vậy chúng ta có thể viết rằng

$$\frac{CU^2}{2} = \Delta W_{\text{BN}}.$$

Helium là một loại khí đơn nguyên tử. Do đó, nội năng $W_{\text{BN}}$ của nó bằng $\frac{3}{2}RTn$, và độ biến thiên của nó là $\Delta W_{\text{BN}} = \frac{3}{2}Rn(T - T_0)$, trong đó $R$ là hằng số khí phổ quát, $n$ là số mol khí, $T_0$ là nhiệt độ ban đầu. Theo phương trình trạng thái khí

$$P_0V_0 = nRT_0$$

Và

$$n = \frac{P_0V_0}{T_0R},$$

trong đó $P_0$, $V_0$, $T_0$ là các thông số ban đầu của helium ($T_0$ có thể được coi là bằng nhiệt độ phòng, tức là $300^\circ\text{K}$). Vì vậy, chúng tôi nhận được

$$\frac{CU^2}{2} = \frac{3}{2}R \frac{P_0V_0}{RT_0}(T - T_0),$$

Ở đâu

$$\frac{T}{T_0} = \frac{CU^2}{3P_0V_0} + 1 \approx 1,2 \cdot 10^6$$

và $T \approx 3,6 \cdot 10^8$ độ Kelvin.

Tại lời giải bài toán, chúng tôi giả định rằng sự trao đổi nhiệt với môi trường, sự nóng lên của các bản tụ điện và bức xạ năng lượng sóng điện từ có thể bị bỏ qua. Kết quả thu được khác biệt rõ rệt so với dữ liệu thực nghiệm, vì vậy cần lưu ý rằng các giả định của chúng tôi mâu thuẫn với thực tế. Ví dụ, có tính đến sự trao đổi nhiệt với môi trường sẽ làm giảm nhiệt độ đi vài bậc độ lớn (lên tới khoảng hàng nghìn độ).

F201. Nếu pin được nối với một điện trở nào đó thì moka phụ thuộc vào thời gian trong mạch sẽ có dạng hoa anh túc, như trong Hình 14 ở mặt đỏ. Nếu một pin được nối với cùng một điện trở nhưng thường xuyên bị phóng điện thì pin sẽ phụ thuộc vào thời gian, như trong Hình 14 ở mặt xanh. Nếu cả hai pin được mắc cùng một điện trở, mắc chúng song song thì ban đầu 1,5 A sẽ chạy qua mạch. Vẽ đồ thị cho thấy mạch tiếp tục thay đổi như thế nào theo thời gian.

Điện trở trong của pin không thay đổi trong quá trình phóng điện.

*) Xem bài viết: Borovinsky L. A. Bài toán để biết mức tối đa và tối thiểu. «Kvant», 1973, số 5.

⟦folio none⟧

Vì pin có cùng e. d.s. và điện trở trong thì khi chúng mắc song song sẽ có dòng điện bằng nhau chạy qua chúng, bằng một nửa dòng điện chạy qua điện trở, tức là 0,75 A. Cả hai pin sẽ bị phóng điện.

Theo điều kiện bài toán giá *) của cục pin thứ nhất là 1 a·3 u = 3 a·u. Do đó, pin thứ hai sẽ cạn trong vòng bốn giờ ($\frac{3 a \cdot u}{0,75 a} = 4 u$); công suất của thiết bị đầu tiên khi kết thúc quá trình này sẽ giảm xuống còn 2 a·u. Sau đó, pin thứ hai sẽ hoạt động tương tự như một tụ điện, trên đó có một số điện áp nhưng không có dòng điện chạy qua nó. Thật vậy, ngay khi e. d.s. Pin này bắt đầu giảm, pin đầu tiên sẽ sạc lại e. d.s., bằng điện áp ở hai cực của pin.

Kể từ thời điểm này, pin đầu tiên sẽ chỉ hoạt động với điện trở bên ngoài. Vì công suất còn lại của nó là 2 au và điện trở mang dòng điện 1 a nên năng lượng của nó đủ cho hai giờ hoạt động.

Do đó, trong bốn giờ, dòng điện 1,5 A chạy qua điện trở, sau đó trong hai giờ - 1 A. Biểu đồ thay đổi dòng điện theo thời gian được hiển thị trong Hình 14 của đường màu đen.

F202. Một ống bán kính r chứa đầy chất xốp có mật độ $\rho_0$. Cháo không trọng lượng, tác dụng một lực F không đổi, xuyên vào đường ống, nén chất này đến mật độ $\rho$ (Hình 15). Cháo sẽ chuyển động với tốc độ bao nhiêu nếu xảy ra hiện tượng nén bằng chốt lăn, tức là bề mặt trong ống dường như đang chuyển động với một tốc độ nhất định, về bên phải của thành phần chất $\rho_0$ và về bên trái p? Ở thời điểm ban đầu, bề mặt này trùng với mặt phẳng của bức tranh.

Chúng ta sẽ giả sử rằng đường ống đủ lớn để ranh giới của vùng có mật độ khác nhau nằm cách xa đầu hình trụ. Khi đó rõ ràng lực nằm ngang duy nhất tác dụng lên vật trong hình trụ là lực F; do đó độ biến thiên động lượng của chất trong hình trụ bằng động lượng của lực này.

Mỗi phần của vật chất chuyển động sẽ chuyển động với tốc độ chuyển động của ranh giới giữa các vùng có mật độ khác nhau. Hãy biểu thị tốc độ này là c và tốc độ chuyển động v.

*) Dung lượng pin là mức sạc tối đa có thể đạt được khi xả pin.

Hình 15.

Trong thời gian $\Delta t$, pít-tông sẽ di chuyển đến một khoảng cách $v \Delta t$, và những hạt có thể tích $v \Delta t \pi r^2$ sẽ bắt đầu chuyển động và mật độ của các hạt này bằng $\rho_0$ (các hạt còn lại, có mật độ $\rho - \rho_0$, đang chuyển động với tốc độ c). Vì tốc độ của mỗi hạt bằng c nên động lượng mà các hạt vật chất thu được trong thời gian $\Delta t$ bằng $v \Delta t \rho_0 c \pi r^2$. Xung lực này, như chúng ta đã nói, bằng xung lực F. Do đó,

$$F \Delta t = \pi v \rho_0 c r^2 \Delta t.$$ (1)

Rõ ràng là vận tốc c và v không độc lập. Từ điều kiện bảo toàn khối lượng, suy ra khối lượng của chất nằm trong thể tích $v \Delta t \pi r^2$, khi trộn piston ở khoảng cách $v \Delta t$, phải phân bố theo thể tích $c \Delta t \pi r^2$, và ở đây nó sẽ có mật độ $\rho - \rho_0$. Đó là lý do tại sao

$$v \rho \Delta t \pi r^2 = c (\rho - \rho_0) \Delta t \pi r^2.$$

Từ đây

$$c = v \frac{\rho}{\rho - \rho_0}.$$ (2)

Thay (2) vào công thức (1), ta được

$$F = \pi v^2 \frac{\rho \rho_0}{\rho - \rho_0} r^2,$$

Và

$$v = \sqrt{\frac{F}{\pi r^2} \frac{\rho - \rho_0}{\rho \rho_0}}.$$

I.Sh. Tiếng Slovodechky
