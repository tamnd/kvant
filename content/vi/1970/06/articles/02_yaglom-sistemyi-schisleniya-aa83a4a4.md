---
id: 1970-6-yaglom-sistemyi-schisleniya-aa83a4a4
issue: kvant_1970_6
year: 1970
number: "6"
title: Hệ thống số
authors:
  - Яглом И. М.
rubric: osnovnye-stati
page_first: 5
page_last: 11
page_labels: 3, 4, 6, 8, 9
lang: vi
source: kvant_digital
extraction: vision
content_sha256: d9c5adc59de4de10a4c509c32fbdd9ab6113c718bca3dc88eee9c7cb98242f43
prompt_sha256: draft-1
translated_from: content/ru/1970/06/articles/02_yaglom-sistemyi-schisleniya-aa83a4a4.md
source_content_sha256: e21ceb0e1f7cf8943a998a6fe738d5cd607ed2d6baebf4294158defae61d6e9e
translation_model: draft
translation_run: vi-draft-gaps-2026-10-31
translation_quality: draft
---

⟦folio 3⟧

Sẽ thật bất tiện khi làm điều tương tự với tất cả các con số gặp phải trong thực tế. Hơn nữa, nếu nhu cầu của chúng ta bị giới hạn ở việc đếm trong phạm vi hàng nghìn, chúng ta sẽ cần phải nhớ một nghìn ký tự đặc biệt. Đương nhiên, trong một thời gian dài, người ta bắt đầu chọn một hoặc một chuỗi số “chìa khóa” khác và chỉ đánh dấu chúng bằng các dấu hiệu đặc biệt. Ví dụ, đây là hệ thống đánh số La Mã, dựa trên các số chính
1, 5, 10, 50, 100, 500 và 1000.
Những con số này trong hệ thống chữ số La Mã đại diện cho các chữ cái I (“i”), V (“ve”), X (“ix”), L (“el”), C (“ce”), D (“de”) và M (“em”).

Những ký hiệu như vậy thường bắt nguồn từ hình, từng được mô tả bằng các chữ số tương ứng (I - ngón tay, V - năm với các ngón tay đặt, X - hai số năm) và thường là chữ viết tắt của các từ Latinh (centum - một trăm, demimille - năm trăm, mille - nghìn).

Vì chúng tôi chỉ cần hệ thống đánh số La Mã làm ví dụ, nên chúng tôi sẽ xem xét nó trong một phiên bản cũ hơn, đơn giản hơn, khi số “bốn” được viết ở dạng IIII chứ không phải ở dạng IV. Số 3477 trong hệ thống La Mã cổ này được viết như sau: MMMSSSSCLXXVII=3·1000+4·100+50+2·10+5+2.

Nhân viên thu ngân cũng làm như vậy, có tiền giấy có mệnh giá 100 rúp, 50 rúp, 25 rúp, 10 rúp, 5 rúp, 3 rúp và 1 rúp. Đối với nhân viên thu ngân, con số là chìa khóa

100, 50, 25, 10, 5, 3 và 1.
Muốn trả 499 rúp, trước tiên anh ta phát hành càng nhiều tờ một trăm đô la càng tốt,

cho đi quá nhiều:
499 = 4·100 + 99.

Sau đó, anh ta phát hành càng nhiều phiếu giảm giá 50 rúp càng tốt để phát hành không quá 99 rúp còn lại phải trả:
499 = 4·100 + 1·50 + 49,
v.v. Đôi khi anh ta có thể có số dư ít hơn số khóa tiếp theo. Đây sẽ là trường hợp trong ví dụ của chúng tôi sau khi phát hành hai tờ mười rúp:
499 = 4·100 + 1·50 + 1·25 + 2·10 + 4.

Tuy nhiên, số chìa khóa tiếp theo là 5, vì 4 < 5 nên không cần đưa ra năm rúp. Nhưng đối với bức tranh, chúng ta có thể giả sử rằng 0 năm rúp đã được trao và bao gồm số hạng 0·5 trong tổng số. Toàn bộ quy trình phát hành 499 rúp sẽ được viết như sau:
499 = 4·100 + 1·50 + 1·25 + 2·10 + 0·5 + 1·3 + 1·1.

Bây giờ chúng ta hãy cố gắng khái quát hóa những gì đã được nói, lấy bất kỳ chuỗi số tăng dần nào làm chuỗi số chính (“cơ sở”):
$q_0 = 1 < q_1 < q_2 < \dots < q_n < \dots$ (1)
Hãy để chúng tôi mô tả cách lấy ký hiệu cho một số tùy ý $N$ trong một hệ số có cơ số (1).

Trong dãy (1) số chính có số lớn nhất $q_n$, không vượt quá $N$. Delim $N$ theo $q_n$ và chúng ta nhận được thương số (không đầy đủ) $a_n$ và phần còn lại $r_{n-1}$:
$N = a_nq_n + r_{n-1}$, ở đâu $0 \leqslant r_{n-1} < q_n$.

Số dư đầu tiên $r_{n-1}$ được chia cho số khóa tiếp theo $q_{n-1}$. Chúng tôi đặt
$r_{n-1} = a_{n-1}q_{n-1} + r_{n-2}$,
ở đâu $0 \leqslant r_{n-2} < q_{n-1}$, hoặc
$N = a_nq_n + a_{n-1}q_{n-1} + r_{n-2}$.

(Lưu ý rằng ở đây chúng tôi không loại trừ trường hợp khi $r_{n-1} = 0$ - trong trường hợp này, tất cả các thương số tiếp theo

⟦folio 4⟧

và số dư sẽ bằng 0!) Số dư mới của Terrier $r_{n-2}$ chia cho $q_{n-2}$; chúng tôi nhận được

$$r_{n-2} = a_{n-2}q_{n-2} + r_{n-3},$$

Ở đâu

$$0 \leqslant r_{n-3} < q_{n-2},$$

hoặc

$$N = a_nq_n + a_{n-1}q_{n-1} + a_{n-2}q_{n-2} + r_{n-3}$$

vân vân.

Cuối cùng, chia số dư áp chót $r_1$ cho $q_1$, ta được

$$N = a_nq_n + a_{n-1}q_{n-1} + \dots + a_2q_2 + a_1q_1 + r_0,$$

ở đâu $0 \leqslant r_0 < q_1$.

(Vì $q_0 = 1$ nên việc chia “phần dư cuối cùng” $r_0$ cho nó là dư thừa: rõ ràng là $r_0 = a_0q_0 = a_0$.) Trong thực tế, phép chia bội số như vậy thường được viết cùng nhau. Chúng tôi sẽ chỉ ra cách thực hiện việc này bằng cách sử dụng ví dụ đã thảo luận về việc ghi lại số tiền 499 rúp. trong “hệ thống thu ngân”:

$$499 \times 100 + 499 \times 50 + 499 \times 25 + 499 \times 10 + 499 \times 5 + 499 \times 1 + 499$$

(Ở đây tất cả các phần $a_n, a_{n-1}$, v.v. được gõ bằng số màu đỏ và chính số $N$ và phần dư $r_{n-1}, r_{n-2}$, v.v. có màu xanh lam.)

§ 2. Hệ thống số vị trí

Có lẽ bạn đã đồng ý rằng trong trường hợp cơ sở

$$q_0 = 1, \quad q_1 = 10,$$

$$q_2 = 10^2, \dots, q_n = 10^n, \dots$$

chúng ta sẽ làm việc với hệ đếm thông dụng dành cho trẻ em. Nhưng thay vì viết, hãy nói,

$$4 \cdot 10^5 + 0 \cdot 10^4 + 3 \cdot 10^3 + 0 \cdot 10^2 + 1 \cdot 10 + 7$$

chúng tôi chỉ cần viết 403017.

Một nhân viên thu ngân mất tập trung hoặc quá đúng giờ có thể chuẩn bị một bản ghi kết quả đầu ra của mình, trong đó số lượng hóa đơn phát hành có mệnh giá khác nhau sẽ được ghi vào các cột riêng biệt. Ở định dạng này, việc phát hành 499 rúp sẽ như sau:

| | 100 | 50 | 25 | 10 | 5 | 3 | 1 |
| :--- | :--- | :--- | :--- | :--- | :--- | :--- | :--- |
| 499 | 4 | 1 | 1 | 2 | 0 | 1 | 1 |

Chúng ta có thể nói rằng trong “hệ thống số thu ngân”, số 499 được viết là

$$4112011.$$

Các hệ thống số liên quan đến những hệ thống được thảo luận trong hai ví dụ cuối (tức là hệ thống số thập phân và “hệ thống thu ngân”) được gọi là vị trí (chúng ta sẽ nói về ý nghĩa của biểu thức này bên dưới). Thay vì ghi chép rườm rà

$$N = a_nq_n + a_{n-1}q_{n-1} + \dots + a_2q_2 + a_1q_1 + a_0$$

trong hệ thống số vị trí có cơ sở (1), sẽ thuận tiện hơn khi sử dụng ký hiệu nhỏ gọn hơn từ $n+1$ “chữ số”:

«$a_na_{n-1} \dots a_2a_1a_0$».

Người ta giả định rằng các “chữ số” $a_k$ được lấy theo cách (thuật toán) tương tự như mô tả ở trên.

Từ mô tả này, rõ ràng là trên một cơ sở nhất định, mỗi số tự nhiên $N$ được viết theo một cách duy nhất. Hơn nữa, vì “chữ số chính” $a_n$ được lấy dưới dạng thương số của số $N$ chia cho $q_n$, mà theo quy ước là nhỏ hơn $q_{n+1}$ (nếu không thì chúng ta sẽ bắt đầu bằng cách chia $N$ cho $q_{n+1}$ chứ không phải cho $q_n$!), nên $a_n < q_{n+1}/q_n$. Đó là lý do tại sao,

⟦folio 6⟧

Sự tồn tại và ký hiệu đặc biệt của số 0, giống như một con mắt khép hờ:

Dưới đây là một số ví dụ về cách viết số theo hệ thống của người Maya:

$$[1 \cdot 20 + 0 = 20, \quad 19 \cdot 360 + 13 \cdot 20 + 13 = 7113, \quad 10 \cdot 360 + 7 = 3607]$$

Dòng ghi số chính trong hệ thống số Varian và hệ thống Maya từ cách đánh số La Mã nằm chính xác ở nguyên tắc "vị trí" của các hệ thống này: trong khi ở người La Mã, chữ cái I luôn có nghĩa là một và V - năm, bất kể những chữ cái này nằm ở đâu, đối với người Babylon cổ đại và người Maya cổ đại, ý nghĩa của "con số" phụ thuộc vào vị trí hoặc "vị trí" của nó. Đó là lý do tại sao các hệ thống ghi số như vậy (bao gồm “hệ thập phân” thường được sử dụng ở Ấn Độ vào thế kỷ 8-9 hoặc sớm hơn một chút) được gọi là vị trí.

Bài tập

1. Viết vào "hệ thống thu ngân hoàn chỉnh" (trong đó các số "chìa khóa" như sau: 10000, 5000, 2500, 1000, 500, 300, 100, 50, 20, 15, 10, 5, 3, 2 và 1, tương ứng với giá trị của tất cả tiền giấy hiện có và tất cả các đồng xu được biểu thị bằng kopecks, số tiền là 233 rúp. 87 kopecks Ghi lại giao dịch chuyển 23387 kopecks sang “hệ thống thu ngân” bằng cách sử dụng “phân chia liên tục” (xem trang 4).

2. Đọc một số được viết bằng hệ thống Varian

3. Đọc một số được viết bằng hệ thống Maya

(Đây là con số lớn nhất được tìm thấy ở một địa điểm của người Maya.)

§ 3. Hệ thống số có cơ số cho trước

Đây là tên của các hệ thống số có cơ số

$$q_0 = d^0 = 1, \quad q_1 = d^1 = d, \quad q_2 = d^2, \quad q_3 = d^3, \quad q_4 = d^4, \dots, (2)$$

trong đó $d$ là số nguyên bất kỳ lớn hơn một. Số $d$ này được gọi là hệ thống số cơ bản.

Các hệ thống này bao gồm hệ thống số thứ mười chung với cơ số $d=10$, hệ thống số sáu thập phân Varian ($d=60$) và hệ thống số kép ($d=2$), gần đây đã được sử dụng rộng rãi do nhu cầu của công nghệ máy tính. Trong trường hợp cơ số tùy ý $d$ người ta nói đến hệ thống số “d-ary”.

Trong hệ thống số $d$-ary, ký hiệu $N = \langle a_n a_{n-1} \dots a_2 a_1 a_0 \rangle$ có ý nghĩa như sau:

$$N = a_n d^n + a_{n-1} d^{n-1} + \dots + a_2 d^2 + a_1 d + a_0.$$

⟦folio 8⟧

1, khác nhau hoặc giống hệt nhau.
Trong hệ thống số như vậy, các số được viết

$$N = \lceil a_n a_{n-1} \dots a_2 a_1 a_0 \rceil$$

chữ số đầu tiên từ cuối $a_0$ có thể nhận $d_0$ giá trị 0, 1, 2, ..., $d_0$ - 1. chữ số tiếp theo $a_1$ có thể nhận giá trị $d_1$ ​​từ 0 đến $d_1$ - 1; chữ số $a_2$ có thể nhận các giá trị từ 0 đến $d_2$ - 1, v.v.

Ngoài ra, trong hệ thống số có cơ số (3), cũng như trong hệ thống số $d$-ary (trong đó hệ thống của chúng tôi bị đảo ngược trong trường hợp $d_0 = d_1 = d_2 = d_3 = \dots = d$), mọi mục nhập đều có ý nghĩa

$$N = \lceil a_n a_{n-1} \dots a_2 a_1 a_0 \rceil,$$

trong đó $a_0, a_1, a_2, \dots, a_n$ là các số tự nhiên sao cho $a_0 < d_0, a_1 < d_1, a_2 < d_2$, v.v. Trên thực tế, có thể dễ dàng kiểm tra xem khi chuyển đổi số $N = a_n q_n + a_{n-1} q_{n-1} + \dots + a_2 q_2 + a_1 q_1 + a_0$ sang hệ thống số của chúng ta bằng phương pháp “chia liên tục” (xem trang 4 ở trên), thu được các số sau:

$$a_n, a_{n-1}, a_{n-2}, \dots, a_1, a_0.$$

Chúng ta sẽ chỉ ra rằng tình huống thuận lợi như vậy không phải là một quy luật chung bằng cách sử dụng ví dụ về một “hệ thống số” rất đơn giản.

Hệ thống số “Chẵn” 2°.

Lấy tất cả các số chẵn (và số $q_0 = 1$) làm cơ sở của hệ thống số:

$$q_0 = 1, \quad q_1 = 2, \quad q_2 = 4, \quad q_3 = 6,$$

$$q_4 = 8, \quad q_5 = 10, \quad q_6 = 12,$$

Kể từ đây

$$\frac{q_1}{q_0} = q_1 = 2$$

Và

$$\frac{q_{n+1}}{q_n} = \frac{2(n+1)}{2n} = \frac{n+1}{n} = 1 + \frac{1}{n} < 2$$ cho tất cả $n > 1$,

thì hệ thống số này cũng giống như hệ thống số kép, chỉ biết hai “chữ số”: 0 và 1. Điều kiện là chỉ định các số được viết trong hệ thống số “chẵn” màu đỏ này. Sau đó, rất indo,

$$2 = 10, \quad 3 = 11, \quad 4 = 100, \quad 5 = 101, \quad 6 = 1000, \quad 7 = 1001, \quad 8 = 10000, \quad 9 = 10001$$, v.v.

Và nói chung, tất cả các số đều được mô tả dưới dạng một với một hoặc một số số 0 khác ở cuối (số chẵn) hoặc phần lớn chuỗi số 0 và số 1 không biểu thị bất kỳ số nào trong hệ thống số “chẵn”, vì trong đó người ta chỉ có thể xuất hiện ở vị trí đầu tiên và - đôi khi - ở vị trí cuối cùng.

Và cuối cùng, một ví dụ nữa.

3° “Hệ thống nhân viên bán hàng”. Một bộ quả cân tiêu chuẩn dành cho cân cốc trong cửa hàng thường bao gồm các quả cân: 10 e, 20 e (2), 50 e, 100 e, 200 e (2), 500 e, 1 ke, 2 ke (2) và 5 ke.

Người bán sử dụng bộ cân này giống như máy thu ngân tiền giấy, có sẵn tại quầy thu ngân. Cụ thể, khi trả lời một sản phẩm, trước hết anh ta đặt lên cân quả cân nặng nhất trong số những quả cân không nhô ra ngoài hàng hóa, sau đó đặt quả cân nặng nhất trong số những quả cân còn lại, v.v.

Vì vậy, ví dụ, khi cân một miếng thịt nặng 3 ke 460 e, anh ta sử dụng trọng lượng hiển thị ở hình.

⟦folio 9⟧

Khái quát hóa hệ thống số (trọng số) nổi tiếng này “được biểu thị bằng số (trọng lượng) bằng cách sử dụng một hệ trọng số nhất định”, được tất cả nhân viên bán hàng và tất cả chủ doanh nghiệp biết đến, chúng tôi đi đến một hệ thống số có cơ sở.
1, 2, 5, 10, 20, 50, 100, 200, 500, ...
trong đó 3 kcal 460 g sẽ được viết như thế này
11020101000.

Trong hệ thống số này trong hồ sơ
$$N \ll a_n a_{n-1} \quad a_2 a_1 a_0$$
chữ số cuối cùng $a_0$ chỉ có thể bằng 0 hoặc 1 (vì $q_1 = 2$); chữ số áp chót $a_1$ có ​​thể lấy các giá trị 0, 1 hoặc 2 (vì $2 < q_2/q_1 < 3$); chữ số thứ ba từ cuối $a_2$ lại chỉ có thể nhận các giá trị 0 và 1 (kể từ $q_3/q_2 = 2$); chữ số $a_3$ cũng chỉ có thể nhận các giá trị 0 và 1, nhưng chữ số $a_4$ lại có thể nhận các giá trị 0, 1 và 2 (vì $2 < q_5/q_4 < 3$).

Và nói chung, trong hệ thống số này, tất cả các số
$$a_1, a_4, a_7, a_{10}, \dots, a_{3k+1}$$
có thể mang các giá trị 0, 1 và 2, còn tất cả các số khác chỉ có thể có giá trị 0 và 1 (Đối với người bán hàng, chỉ cần có hai quả cân nặng 2 gam và mỗi quả chỉ có một quả cân cho 1 kcal và 5 kcal.)
