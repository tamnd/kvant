---
id: 2010-2-tolpyigo-ob-odnoy-zabyitoy-zadache-616c4b1a
issue: kvant_2010_2
year: 2010
number: "2"
title: Về một người bị lãng quên bài toán
authors:
  - Толпыго А. К.
rubric: matematicheskiy-kruzhok
rubric_sub: Математический кружок
page_first: 47
page_last: 48
page_labels: 45-46
tag: XE3R
lang: vi
source: kvant_digital
extraction: native
content_sha256: f04c54301ab28b9c81aa650578574eded501e63298885e9ddeb7d4f2fbd0f3e1
prompt_sha256: draft-1
translated_from: content/ru/2010/02/articles/05_tolpyigo-ob-odnoy-zabyitoy-zadache-616c4b1a.md
source_content_sha256: f104472697b4b578c0da89b82e79f356bcbc149b452ba4c1aaa62ec303fda9ba
translation_model: draft
translation_run: vi-draft-2026-10-31
translation_quality: draft
---

⟦folio 45⟧

VÒNG TRÒN TOÁN HỌC

Về một người bị lãng quên bài toán

A. TOLPYGO

Và đôi khi điều đó cũng xảy ra: bạn đang vật lộn với một vấn đề nào đó, nhưng nó không giải quyết được, và rồi bạn nghĩ ra một số cách mới, rất xảo quyệt để giải quyết nó. Và hãy tưởng tượng, nó sẽ không còn hiệu quả với bạn nữa! Công việc tưởng chừng như hoàn toàn vô ích này lại thường mang lại những lợi ích không ngờ...

S. Bobrov. bicorn ma thuật

Để bắt đầu, hãy xây dựng hai bài toán. Bài toán A. Chứng minh rằng từ n số nguyên bất kỳ bạn có thể chọn được một số số có tổng chia hết cho n. Bài toán B. Chứng minh rằng từ (2n – 1) số nguyên bất kỳ có thể chọn được n số có tổng chia hết cho n. Bài toán A được biết đến rộng rãi và có thể giải bằng nguyên lý Dirichlet (“nếu (n + 1) con thỏ cần được xếp vào n ô thì ít nhất một ô sẽ chứa ít nhất hai con thỏ”). Cụ thể, chúng ta cần xét các số $S_{0} = 0, S_{1} = a_{1}, S_{2} = a_{1} + a_{2}, S_{3} = a_{1} + a_{2} + a_{3}$, …, $S_{n} = a_{1} +^{…} + a_{n}$. Vai trò của các “ô” mà những “con thỏ” này cần ngồi được đảm nhận bởi số dư khi chia số cho n. Theo nguyên lý Dirichlet, một số “con thỏ” cuối cùng sẽ ở trong cùng một “cái lồng”, tức là có cùng số dư khi chia cho n. Do đó, hiệu của chúng được chia cho n và đây là điều cần thiết. Ngược lại, bài toán B (từng được xuất bản trên tạp chí «Kvant» vào năm 1970 với số hiệu M45) giờ đây đã bị lãng quên một cách đáng kể. Trong khi đó, không chỉ có một thực tế toán học tuyệt vời mà còn có một số ý tưởng hay xung quanh lời giải của nó. Đúng, như sẽ thấy sau, một số dẫn đến bằng chứng, số khác thì không. Tuy nhiên, cả hai đều hữu ích: nếu một số trong số chúng không đủ cho lời giải bài toán này – chúng sẽ có ích vào lúc khác. Dưới đây chúng ta sẽ thảo luận cụ thể về bài toán B. Nhưng trước tiên, chúng ta sẽ xem xét thêm một vài bài toán cùng loại.

1. Hai cái nữa bài toán

Bài toán C. Cho N – 1 số tự nhiên $a_{1},^{…}, a_{N} -_{1}$. Tất cả chúng đều lớn hơn 0 và nhỏ hơn N. Biết rằng nếu bất kỳ k, 0 < k < N và bất kỳ k số nào từ tập hợp này được chọn thì tổng của chúng không chia hết cho N. Chứng minh rằng tất cả các số trong tập hợp đều bằng nhau. Bài toán D. Cho 100 số, mỗi số lớn hơn 0 và nhỏ hơn 94. Chứng minh rằng từ chúng có thể chọn ra nhiều số mà tổng của chúng khi chia cho 101 sẽ có số dư là 95. Lời giải bài toán C. Giả sử rằng $a_{1} \ne a_{2}$. Xét các tổng $S_{0} = a_{1}, S_{1} = a_{2}, S_{2} = a_{1} + a_{2}, S_{3} = a_{1} + a_{2} + a_{3},...$

⟦column⟧

…, $S_{N} -_{1} = a_{1} + a_{2} +$ … $+ a_{N} -_{1}$. (Hai tổng đầu bằng hai số hạng đầu, còn lại là tổng từ số hạng đầu đến số hạng tương ứng). Theo giả định, không có tổng nào trong số này có số dư bằng 0 khi chia cho N. Do đó, hai trong số chúng có số dư bằng nhau và nó không phải là số thứ nhất và số thứ hai. Nhưng khi đó hiệu của hai tổng tương ứng được chia cho N và điều này mâu thuẫn với điều kiện. Lời giải bài toán D. Hãy thừa nhận ngay rằng chúng tôi giới hạn ở con số 101, một phần để diễn đạt dễ dàng hơn, phần khác để “làm đục nước” một chút và che đậy ý tưởng một chút. Trên thực tế, thực tế này đúng trong một tình huống khá chung chung. Cụ thể, chúng ta thay số 101 bằng bất kỳ số nguyên tố p nào, và số 95 bằng bất kỳ số nào từ 0 đến p và chứng minh rằng từ (p – 1) các số cho phần dư khác 0 khi chia cho p, chúng ta có thể tạo một tổng có số dư khác 0 xác định trước khi chia cho p. Hãy sắp xếp các số này một cách tùy ý. Hãy chọn bất kỳ $k, 0 \le k \le ( p - 1 )$ nào và lấy k số đầu tiên của chúng ta. Hãy tạo tất cả các tổng có thể có từ chúng (một số hoặc không có số nào cũng là tổng; tổng của một tập hợp số trống được giả sử bằng 0) và viết ra tất cả các số dư khác nhau khi chia các tổng này cho p. Cụ thể, ở bước đầu tiên (nếu k = 0) có một tổng duy nhất và bằng 0. Đối với một k tùy ý, chúng ta thu được một số số $M_{1}$, … $, M_{n}$. Nếu trong số họ đã có tất cả những gì có thể còn sót lại thì không có gì để chứng minh. Đừng để nó như vậy. Hãy thêm vào số (k + 1) đã chọn (để nó bằng r) và viết lại tất cả các tổng và tất cả số dư. Kết quả đầu tiên sẽ là các số $M_{1}$, … $, M_{n}$ (dù sao thì số cuối cùng cũng có thể không được lấy), và thứ hai là phần dư từ việc chia các số $M_{1} + r$, … $, M_{n} + r$ cho p. Bây giờ chúng ta khẳng định rằng có ít nhất một số trong nhóm thứ hai không xuất hiện trong nhóm thứ nhất. Trên thực tế, hãy giả sử điều ngược lại. Khi đó hóa ra nếu số dư N trùng với một trong $M_{i}$, thì số dư N + r cũng trùng với một số khác trong tập ${ M_{i} }$. Nhưng khi đó phần còn lại N + 2r = (N + r) + r cũng trùng với một số khác trong tập ${ M_{i} }$, điều này cũng đúng với N + + 3r = (N + 2r) + r, v.v. Từ đó dễ dàng suy ra rằng trong số ${ M_{i} }$ tất cả số dư có thể có của phép chia cho p đã xảy ra và chúng tôi giả định rằng trường hợp này không phải như vậy. Vì vậy, cho đến khi không viết hết tất cả số dư, số lượng các số khác nhau sẽ tăng lên ở mỗi bước. Vì số bước bằng p nên không muộn hơn bước cuối cùng số lượng dư lượng khác nhau ít nhất sẽ bằng p, đây là điều bắt buộc. Vì tổng bằng 0 xuất hiện ở bước đầu tiên (khi không có số nào cả), không có gì đảm bảo rằng có thể nhận được tổng có phần dư bằng 0. Và thực sự, nếu chúng ta lấy tất cả các số bằng nhau thì phần dư của 0 sẽ không tính ra (và điều này, theo bài toán C, là trường hợp duy nhất khi số dư này không tính ra). Tất cả số tiền khác có được bằng cách này hay cách khác.

2. Bài toán B. Hợp số

Bây giờ chúng ta quay lại bài toán B. Để thuận tiện, chúng ta ký hiệu phát biểu của nó là BC(n) (“lựa chọn tổng”); Do đó, ký hiệu BC(21) là sự rút gọn của phát biểu “đúng là từ 41 số nguyên bất kỳ chúng ta có thể chọn 21 có tổng chia hết cho 21”.

⟦folio 46⟧

KVANT 2010/№2

Trước hết, hãy lưu ý rằng ước tính này không thể được cải thiện. Trên thực tế, nếu chúng ta chỉ lấy 2p – 2 số thì có thể dễ dàng xây dựng một phản ví dụ: chỉ cần lấy p – 1 số 0 và p – 1 số một. Bạn cũng có thể thay thế số 0 và số 1 bằng các số khác (nếu n là số nguyên tố - bằng bất kỳ hai số nào khác nhau, chúng tôi để trường hợp hợp số n cho người đọc phân loại). Để ngắn gọn, dưới đây chúng ta sẽ gọi tập hợp số đã cho (2p – 1) là một “tập hợp” và một “nhóm” là tập hợp con của một số số, tổng của chúng chia hết cho p. Ta cần chứng minh tồn tại một nhóm gồm p phần tử. Chúng tôi sẽ đưa ra mệnh đề lời giải bài toán đầy đủ (nói cách khác là mệnh đề BC ( n ) cho bất kỳ n nào) ở cuối bài viết, nhưng chúng tôi sẽ bắt đầu bằng cách chứng minh một mệnh đề đơn giản: nếu BC ( p ) và BC ( q ), thì BC ( pq ). Bằng chứng. Cho n = pq và cho 2n – 1 số ${ a_{k} }$; theo BC(p), từ đó người ta có thể chọn được một nhóm p số có tổng chia hết cho p. Hãy đặt nhóm này sang một bên và nhìn vào những con số còn lại. Vì có nhiều hơn (2p – 1) số chưa được sử dụng nên có thể chọn thêm một nhóm từ chúng, tổng của chúng cũng chia hết cho p. Tiếp tục theo cách này, chúng ta sẽ nhận được nhiều nhóm số p, tổng của mỗi nhóm chia hết cho p; Dễ dàng nhận thấy có thể có (2q – 1) nhóm. Đặt $S_{1} = p \cdot r_{1}, S_{2} = p \cdot r_{2}$, … $S_{2} q_{-} 1 = p \cdot r_{2} q_{-} 1$ là tổng của chúng. Vì ${ r_{k} }$ là số nguyên nên từ chúng, theo BC ( q ), ta có thể chọn q số có tổng chia hết cho q. Sau đó, tổng của ${ S_{k} }$ tương ứng được chia cho pq và tổng này chứa chính xác số ${ a_{k} }$ theo yêu cầu. Điều quan trọng cần lưu ý là trong chứng minh này, việc các số p và q có nguyên tố cùng nhau hay không không quan trọng. Vì vậy, chỉ cần chứng minh BC ( n ) cho trường hợp n = p là số nguyên tố là đủ. Đây là trường hợp duy nhất chúng tôi sẽ giải quyết trong tương lai. Bây giờ chúng ta chứng minh mệnh đề BC(p) với một số giá trị của p. Lưu ý rằng mặc dù chúng ta sẽ trình bày bằng chứng cho một số cụ thể nhưng thực tế sẽ đúng với các số khác nhau. Do đó, người đọc nên đánh giá mỗi lần: liệu lý do này chỉ áp dụng cho một p nhất định hay liệu nó có thể được khái quát hóa hay không.

3. Chứng minh cho p = 7

3.1. Tăng bội số của số 0. Nếu tìm được tất cả 7 số dư có thể có trong số đã cho thì không có gì phải chứng minh, vì 0 + 1 + 2 + ... + 6 chia hết cho 7. Do đó, ta có thể giả sử rằng trong 13 số của chúng ta có không quá 6 số dư khác nhau. Nhưng sau đó một trong số chúng xảy ra ít nhất ba lần. Số lần một số dư cụ thể xuất hiện trong tập hợp của chúng ta, chúng ta sẽ gọi nó là bội số. Chúng ta sẽ giả sử rằng bội số của ba (hoặc nhiều hơn) có số dư bằng 0. (Trong Phần 3.3, chúng ta sẽ chỉ ra cách rút gọn trường hợp tổng quát thành trường hợp này). Nếu bội số của 0 không nhỏ hơn 7 thì cũng không có gì phải chứng minh. Mặt khác, có ít nhất 7 số dư khác 0, và theo bài toán A, người ta có thể chọn một số (giả sử k) từ chúng, tổng của chúng chia hết cho 7. Đúng, không có lý do gì để nghĩ rằng k = 7. Đặt k < 7; Hãy xem xét hai trường hợp. a) Nếu k > 3 thì chúng ta có thể lấy những số này và cộng thêm một số số 0 vào chúng (từ một đến ba); bạn nhận được một nhóm gồm 7 số và khẳng định đã được chứng minh. b) Bây giờ hãy $k \le 3$. Ở đây chúng ta cần phải làm những việc khác nhau. Chúng tôi sẽ thay thế bộ này bằng một bộ mới. Nó chứa k số, tổng của chúng

bằng 0, tất cả được thay thế bằng số 0, như trong bảng:

⟦column⟧

Bộ gốc

0 0 0 2 2 3 1 …

Đã thay đổi bộ

0 0 0 0 0 0 1 …

(Vì 2 + 2 + 3 chia hết cho 7 nên chúng ta đã thay thế các số này bằng số 0 và giữ nguyên các số còn lại.) Giả sử rằng đối với tập hợp mới, câu lệnh bài toán đã xác minh: nó có một nhóm gồm 7 số có tổng chia hết cho 7. Điều tương tự cũng đúng với tập hợp cũ. Thật vậy, giả sử có một vài số 0 trong nhóm này (chẳng hạn r số 0, $r \ge 0 ).$ Nếu như $r \le 3$, thì chúng ta lấy các số tương tự từ tập hợp cũ (xét cho cùng, ở đó có ba số 0); nếu r > 3, thì thay vì ba số 0, chúng ta có thể lấy ba số của tập hợp cũ, được thay thế bằng các số 0 (tổng sẽ không thay đổi so với số này) và các số khác giống như trong tập hợp mới. Vì vậy, chúng tôi đã giảm vấn đề thành một tập hợp mới, trong đó có nhiều số 0 hơn trước (hãy gọi nó theo cách này: “kỹ thuật tăng bội số của 0”). Vậy thì đã rõ: hoặc chúng ta đã có 7 số 0 hoặc chúng ta có thể lặp lại lý luận tương tự. Chúng ta sẽ có được bộ mong muốn ngay lập tức hoặc tăng lại số lượng số 0, v.v. Tuy nhiên, đối với bảy người, rõ ràng là họ sẽ không phải vượt qua bước thứ hai. Có thể áp dụng lý luận tương tự cho p tùy ý không? Đáp số rõ ràng: có thể, nhưng chỉ khi có nhiều số 0: không nhỏ hơn (p – 1)/2. Tất nhiên, với p lớn, chúng ta không thể tin tưởng vào điều này nên chúng ta sẽ phải tìm những cách khác. Tuy nhiên, “kỹ ​​thuật tăng bội số” sẽ tiếp tục hữu ích cho chúng ta; chỉ ở đó thôi thì chưa đủ. Bây giờ chúng ta hoàn thành chứng minh cho trường hợp p = 7. 3.2. Cảm ứng? Rõ ràng, lý luận được đưa ra trong phần 3.1 sẽ tự nhiên hơn khi được xây dựng bằng phương pháp quy nạp. Những gì nên được lấy làm tham số của nó? Thuận tiện nhất là coi n (tham số quy nạp) bằng (p + 1 – k), trong đó k là bội số của 0 (hoặc số dư xảy ra thường xuyên nhất): “nếu $n \le 1$, thì một trong các dư lượng xảy ra ít nhất p lần, và phát biểu là hiển nhiên; do đó, nếu có thể chứng minh rằng bội số cao nhất có thể tăng lên (như chúng tôi đã làm trong phần 3.1), thì mọi thứ đều đã được chứng minh.” Tuy nhiên, thật bất tiện cho chúng ta khi sử dụng quy nạp và đây là lý do. Thật không may, đối với một p tùy ý, quy nạp không hoạt động: nếu có thể chứng minh rằng bội số cao nhất có thể tăng lên thì mọi thứ sẽ ổn, nhưng chúng ta không thể chứng minh điều này. Và trong trường hợp p = 7, việc sử dụng quy nạp là khá đúng, nhưng... sẽ là “bắn đại bác vào chim sẻ”: sẽ có loại quy nạp nào nếu mọi thứ kết thúc trong tối đa hai bước? 3.3. Rút gọn trường hợp tổng quát thành trường hợp cụ thể: tính bắc cầu. Lý luận của chúng tôi từ phần 3.1. giả sử số 0 còn lại có bội số cao nhất. Bây giờ, ví dụ, 2 phần còn lại xảy ra thường xuyên nhất. Sau đó trừ 2 từ tất cả 13 số đã cho; bây giờ 0 là phổ biến nhất. Đồng thời, ý nghĩa của chúng tôi bài toán không thay đổi: nếu một nhóm 7 số nào đó có tổng chia hết cho 7, thì sau khi trừ hai số, tổng đó bị trừ 14, tức là nó vẫn chia hết cho 7. Do đó, giả định rằng số dư đó và số dư đó có bội số cao nhất (thật tiện lợi cho chúng ta khi giả sử rằng đây là số dư 0) không vi phạm tính tổng quát của đối số: trừ đi cùng một thứ từ tất cả các số đã cho, chúng ta
