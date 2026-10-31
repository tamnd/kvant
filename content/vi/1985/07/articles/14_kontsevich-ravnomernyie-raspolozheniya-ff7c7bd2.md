---
id: 1985-7-kontsevich-ravnomernyie-raspolozheniya-ff7c7bd2
issue: kvant_1985_7
year: 1985
number: "7"
title: Sắp xếp thống nhất
authors:
  - Концевич М. Л.
rubric: zadachnik-kvanta
rubric_sub: Задачник «Кванта»
page_first: 53
page_last: 54
page_labels: 51-52
tag: Y1O3
lang: vi
source: kvant_digital
extraction: vision
content_sha256: 9c07cc1d62f21460b1d3e364029f8da95825eef55d8bc1149528b7608272035c
prompt_sha256: draft-1
translated_from: content/ru/1985/07/articles/14_kontsevich-ravnomernyie-raspolozheniya-ff7c7bd2.md
source_content_sha256: e40bfddf7f8b0ed5e0fdec3d95325d259b3e3e95b7ea178ac09e87e6e29274f7
translation_model: draft
translation_run: vi-draft-2026-10-31
translation_quality: draft
---

⟦folio 51⟧

Sắp xếp thống nhất

M. L. KONTSEVICH

Giả sử có $n$ điểm trên vòng tròn và một số $k$ trong số chúng được chọn - chúng ta sẽ gọi chúng là màu đen và phần còn lại - màu trắng. Thật dễ dàng để chỉ ra sự sắp xếp không đồng đều nhất của $k$ các chấm đen trong số những chấm đen khác: bạn cần sắp xếp tất cả chúng thành một hàng. Hóa ra bạn có thể đưa ra một định nghĩa hoàn toàn tự nhiên về sự phân bố đồng đều nhất của các chấm đen. Sự sắp xếp thống nhất như vậy được tìm thấy trong nhiều tình huống toán học, và không chỉ toán học. Chúng được thảo luận trong bài viết này; đây là lời giải bài toán M818 từ “Vấn đề Kwana”, xuất bản ở số 9, 1983.

Định nghĩa, ví dụ và lý thuyết cơ bản

Chúng ta gọi sự sắp xếp các chấm đen là đồng nhất nếu với mỗi số tự nhiên $m < n$ (trong đó $n$ là tổng số điểm - đen và trắng), số chấm đen trong bộ $m$ điểm liên tiếp trên vòng tròn chênh nhau không quá 1. Ví dụ: cách sắp xếp 4 điểm trong số 9 trên hình 1 là đồng nhất - điều này có thể dễ dàng xác minh bằng phép liệt kê và cách sắp xếp 7 điểm trong số 17 trên hình 2 không đồng đều. Sự sắp xếp thống nhất của $k$ chấm đen giữa $n$ điểm trên vòng tròn sẽ được ký hiệu là $P(n; k)$. Lưu ý rằng việc thay đổi màu - đen thành trắng - biến $P(n; k)$ thành $P(n; n-k)$, vì vậy bạn luôn có thể giảm tới $k \leq n/2$ tiếp theo.

Vị trí $P(12; 5)$ đặc biệt quen thuộc với chúng ta - đó là vị trí của năm tháng ngắn ngủi (dưới 31 ngày) trong năm, cũng như năm phím đen trong số 12 phím của một; quãng tám; Dễ dàng nhận thấy đây là những cách sắp xếp giống nhau: Tháng Giêng tương ứng với nốt “F”, Tháng Hai - “F nhọn”, v.v., vì vậy để chơi thang màu, chỉ cần nhớ mỗi 12 tháng có bao nhiêu ngày (hình 3, 4). Việc mô tả sự sắp xếp thống nhất không phải trên một vòng tròn mà ở dạng một chuỗi tuần hoàn các điểm đen và trắng trên một đường thẳng, gặp trong ví dụ trước, hóa ra rất thuận tiện cho những cách diễn giải và khái quát hóa mới mà chúng tôi chỉ ra trong các bài toán cuối cùng.

Các vòng tròn bên ngoài hình 5 và 6 hiển thị vị trí của $P(17; 7)$ và $P(84; 19)$. Chúng tôi tuân thủ cách thức chung mà chúng được xây dựng; đồng thời điều sau đây sẽ được chứng minh

⟦folio 52⟧

Định lý chính: với mọi số tự nhiên n và k(k<n) đều tồn tại một cách sắp xếp thống nhất P(n;k) và duy nhất (cho đến phép chia các điểm dọc theo đường tròn mà không làm thay đổi thứ tự sắp xếp của chúng).

Đây là điều bắt buộc phải làm trong bài toán M818.

Bổ đề "về gốc"
và xây dựng P(n;k)

Điều kiện: khoảng cách giữa hai điểm cực trị A và B của đoạn m điểm liên tiếp trên đường tròn coi bằng m-1 (trong trường hợp này cũng có m-2 điểm nằm giữa A và B); Dưới đây chúng ta cũng sẽ gọi khoảng cách này là “độ dài” của đoạn AB và ký hiệu |AB|.

Đầu tiên chúng ta xét trường hợp hiển nhiên khi n chia hết cho k. Khi đặt k điểm đen ở những khoảng cách bằng nhau d=n/k, chúng ta thu được một sự sắp xếp thống nhất P(n;k): trong số m đỉnh nằm trên một hàng sẽ luôn có [m/d] hoặc [m/d]+1 điểm đen ([x] là phần nguyên của số x). Đối với bất kỳ sự sắp xếp nào khác của k chấm đen, vị trí của chúng sẽ không đồng đều: trong khoảng cách giữa các chấm đen lân cận, sẽ có ít nhất một chấm không nhỏ hơn d+1 và một chấm không lớn hơn d-1, do đó trong số m=d chấm liên tiếp có thể có cả 2 và 0 chấm đen.

Đối với n và k tùy ý, như một phép làm mỏng tương tự cho thấy, khoảng cách giữa các điểm đen lân cận có vị trí đồng nhất cũng phải khác nhau không quá 1. Tổng cộng, tất cả k khoảng cách này đều bằng n, vì vậy nếu n=kd+r (chúng ta chia n cho k với số dư), thì r trong số các khoảng cách này có độ dài d+1, và phần còn lại - d. Nhưng điều quan trọng nữa (so sánh hình 2 và 5) là r đoạn dài hơn bằng tất cả k đoạn dọc theo đường tròn.

Ví dụ: trên hình 2 (với sự sắp xếp không đồng đều), chuỗi độ dài và đoạn ngắn, được viết theo chiều kim đồng hồ từ điểm có dấu hoa thị, trông như thế này: dkdkkk và trên hình 5 (đối với P(17;7)) - dkdkkk. Có thể thấy rằng ở dãy thứ hai, các chữ d cách đều nhau nhưng ở dãy đầu tiên thì không. Sẽ rất thuận tiện khi mô tả lại các chuỗi như vậy dưới dạng các điểm trên một vòng tròn nhỏ hơn: các đoạn dài có màu đen, các đoạn ngắn có màu trắng (hình 5, 6). Và đây là bổ đề quan trọng. Cho có k điểm đen trong số n điểm trên đường tròn, chia nó thành các đoạn có độ dài d+1 và d. Để sự sắp xếp các chấm đen được đồng đều, điều cần thiết là sự sắp xếp tương ứng của r chấm đen giữa k điểm trên vòng tròn nhỏ hơn phải đồng nhất.

Theo bổ đề này mà chúng tôi sẽ chứng minh dưới đây, sự tồn tại và duy nhất của P(k;r) kéo theo sự tồn tại và duy nhất của P(n;k). Từ đây chúng ta thu được ngay chứng minh định lý chính (bằng quy nạp) và một cách thuận tiện để xây dựng các sắp xếp thống nhất cho n và k bất kỳ. Rốt cuộc, quá trình “đi xuống” danh nghĩa có thể được tiếp tục: k chia (có số dư r₂<r) cho r₁=r, sau đó r₁ (có số dư r₃<r₂) cho r₂, v.v., cho đến khi một số dư r₁-1 được chia thành r₂ tiếp theo. (Đây là thuật toán Euclide nổi tiếng để tìm ước số chung nhất của các số n và k: r₅=GCD (n;k).) Do đó, sau vài bước giảm dần, chúng ta đi đến trường hợp cực đoan P(r₅-1;r₅), khi r₅-1 chia hết cho r₅. Sau khi thực hiện đối với một cặp số n và k cho trước các phép chia cần thiết có số dư (như trong thuật toán Euclide), chúng ta đã học được cách toàn bộ cách sắp xếp P(r₅-1;r₅), P(r₅-2;r₅-1),...· dẫn đến P(n;k) và có thể “phát triển” cách sắp xếp P(n;k) (như thể hiện trong hình 6), xây dựng từ các “hạt” có hai màu đồng tâm tầng-vòng tròn. Thực hành xây dựng những “chiếc vòng cổ” này. Trong các ví dụ của chúng tôi, n và k là nguyên tố cùng nhau, nghĩa là r₅=1 và việc hạ xuống dẫn đến một vị trí có dạng P(r₅-1;1) với một điểm duy nhất được đánh dấu giữa các điểm còn lại. Lưu ý rằng việc đi xuống thực tế có thể được tăng tốc phần nào; nếu ở bước nào đó có hơn một nửa số chấm đen thì bạn có thể “đánh dấu màu” (chuyển từ cặp (n, k) sang cặp (n;n-k)), sao cho ở mỗi bước số lượng chấm sẽ giảm đi hơn một nửa.

Chứng minh bổ đề

Theo thứ tự (giả sử theo chiều kim đồng hồ) các chấm đen là: B₁, B₂, ..., Bₖ. Khoảng cách (không theo chiều kim đồng hồ) từ B₁ đến điểm đen thứ q B₁+q từ nó được ký hiệu là |B₁B₁+q|, ở đây B₁+1=B₁, B₁+2=B₂, v.v. Trong số các đoạn B₁B₁+1, B₁+1B₂+2, ..., B₁+q-1B₁+qchính xác |B₁B₁+q|—qd có độ dài d+1, phần còn lại có độ dài d. Vì vậy, chúng ta phải chứng minh rằng tính đồng nhất về vị trí của điểm B₁ tương đương với điều kiện: với mỗi q<k khoảng cách |B₁B₁+q| khác nhau không quá 1. Chứng minh theo cả hai hướng là mâu thuẫn. Nếu vị trí của chúng ta không đồng nhất thì nó sẽ tìm thấy hai đoạn có cùng độ dài, trên một đoạn chỉ có q-1 chấm đen B₁+1, ..., B₁+q-1, mặt khác - ít nhất 2 đoạn lớn B₁, B₁+1, ..., B₁+q, nhưng sau đó |B₁B₁+q|—|B₁B₁+q| ≥2. Ngược lại, nếu bất đẳng thức cuối cùng được thỏa mãn thì đoạn B₁B₁+q chứa q+1 điểm đen và đoạn có cùng độ dài, bắt đầu từ điểm bên cạnh B₁, chứa ít nhất hai điểm nhỏ hơn.
