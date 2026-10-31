---
id: 1981-9-yaglom-pochti-prostyie-chisla-bfa990c3
issue: kvant_1981_9
year: 1981
number: "9"
title: Gần như số nguyên tố
authors:
  - Яглом И. М.
rubric: matematicheskiy-kruzhok
rubric_sub: Математический кружок
page_first: 18
page_last: 20
page_labels: 16, 18
tag: KB5V
lang: vi
source: kvant_digital
extraction: vision
content_sha256: c64ac0eca22d2d9ee858b48a5cc6c1b2f19d4cbe4d51f61c2ce108e644a22109
prompt_sha256: draft-1
translated_from: content/ru/1981/09/articles/08_yaglom-pochti-prostyie-chisla-bfa990c3.md
source_content_sha256: 5fc37459484c466876c44ed226c18412e323d743d26e90af22ebc6a583d0f6c0
translation_model: draft
translation_run: vi-draft-2026-10-31
translation_quality: draft
---

⟦folio 16⟧

Gần như số nguyên tố

Những khám phá được thực hiện trong toán học như thế nào? Thông thường - giống như trong các ngành khoa học khác: nhà nghiên cứu cố gắng đưa một sự kiện được chú ý vào như một trường hợp đặc biệt trong một khuôn mẫu chung. Không phải lúc nào cũng có thể tìm thấy mô hình này, và một nhà toán học, giống như bất kỳ nhà nghiên cứu nào khác, hành động bằng cách “thử và sai”.
Lý luận của anh ấy có thể trông như thế nào khi nói đến sự chia hết của các số được mô tả trong bài viết này.

1. Định lý nhỏ Fermat

Rõ ràng bình phương $n^2$ của số tự nhiên $n$ sẽ là số chẵn hoặc số lẻ cùng lúc với chính số $n$. Như vậy, các số $n^2$ và $n$ sẽ luôn đồng thời là số chẵn và số lẻ. Tuy nhiên, hơn nữa, hiệu này luôn bằng 3. Trên thực tế, số $n$ hoặc chia hết cho 3 (tức là có dạng $3k$), hoặc chia cho 3 thì dư 1 (có dạng $n=3k+1$), hoặc dư 2 khi chia cho 3 (khi đó nó có thể được biểu diễn là $n=3k+2=3(k+1)-1=3(k'-1)$).

Nếu $n$ chia hết cho 3 thì $n^3$ cũng chia hết cho 3. Nếu $n$ có ​​dạng $3k \pm 1$ thì $n^3=(3k \pm 1)^3=3(9k^3 \pm 9k^2+3k) \pm 1$, tức là $n^3=3l \pm 1$.

Trong mọi trường hợp, hiệu $n^3-n$ là bội số của 3. Vì vậy, chúng ta có

Phát biểu 2. Hiệu $n^3-n$ chia hết cho 3 đối với bất kỳ $n$ nào.

Bài tập
1. Chứng minh mệnh đề 1 và 2 bằng cách phân tích các đa thức $n^2-n$ và $n^3-n$.
2. Chứng minh rằng hiệu $n^3-n$ chia hết cho 6 với mọi $n$.

Tuyên bố 1 và 2 khơi dậy niềm hy vọng rằng điều này là đúng.

Giả thuyết 1. Hiệu $n^m-n$ chia hết cho $m$ cho mọi $m$ và $n$.

Than ôi! Dễ dàng bắt gặp một phản ví dụ bác bỏ giả thuyết này: hiệu $2^4-2=14$ không chia hết cho 4.

Tuy nhiên, tôi muốn thấy rằng sự giống nhau giữa câu 1 và 2 không phải là ngẫu nhiên. Hãy thử kiểm tra sự khác biệt $n^5-n$. Ví dụ: $2^5-2=30$ chia hết cho 5. Có thể dễ dàng chứng minh rằng đây không phải là ngẫu nhiên và là công bằng.

Phát biểu 3. Hiệu $n^5-n$ chia hết cho 5 đối với bất kỳ $n$ nào.

Trên thực tế, số $n$ có thể chia hết cho 5 hoặc khi chia cho 5 thì có một trong các số dư là 1, 4 (trong những trường hợp này nó có thể được biểu thị là $5k \pm 1$) hoặc khi chia cho 5 thì có một trong các số dư là 2, 3 (sau đó là $n=5k \pm 2$). Nếu $n$ chia hết cho 5 thì $n^5$ chia hết cho 5. Nếu $n=5k \pm 1$ thì

$$n^2=(5k \pm 1)^2=5(5k^2 \pm 2k)+1.$$

Nếu $n=5k \pm 2$ thì

$$n^2=(5k \pm 2)^2=5(5k^2 \pm 4k+1)-1.$$

Do đó, nếu $n$ không chia hết cho 5 thì số $n^2$ là $5L \pm 1$ và

$$n^4=(5L \pm 1)^2=5(5L^2 \pm 2L)+1$$

cho số dư 1 khi chia cho 5. Theo đó, hiệu $n^4-1$, và do đó hiệu $n^5-n=n(n^4-1)$, chia hết cho 5.

Bây giờ chúng ta đã có ba tuyên bố tích cực. Điều này buộc chúng tôi phải tiếp tục tìm kiếm. Sự khác biệt

⟦folio 18⟧

2. Gần như số nguyên tố

Chúng ta hãy nhớ lại cách chúng ta đi tới định lý nhỏ Fermat ở đoạn trước. Sau khi sửa $m$, chúng tôi phát hiện ra liệu tất cả sự khác biệt $n^m - n$ có chia hết cho $m$ hay không. Để hình thành một giả thuyết chính xác, mỗi lần đầu tiên chúng tôi kiểm tra xem số $2^m - 2$ có chia hết cho $m$ hay không. Đối với tất cả được coi là đơn giản $m$, sự khác biệt $2^m - 2$ chia hết cho $m$, đối với những cái tổng hợp thì nó không chia hết. Tự nhiên phát sinh

Giả thuyết 5. Sự khác biệt $2^m - 2$ chia cho $m$ với sự đơn giản $m$ và không chia hết - khi ghép *).

Giả thuyết 5 được đưa ra bởi các nhà toán học Trung Quốc cổ đại - cách đây khoảng 2,5 nghìn năm.

Ở Trung Quốc cổ đại, cũng như tất cả các nền văn minh khác trước Hy Lạp cổ đại (Babylon, Ai Cập cổ đại, v.v.), toán học không phải là một môn khoa học mang tính xây dựng mà là một khoa học lưới. Vai trò chính trong toán học không phải do kết luận mà do sự thật, và câu hỏi làm thế nào thực tế này hay thực tế kia được xác lập không được coi là đặc biệt quan trọng: một bằng chứng đủ hợp lý có thể thay thế hoàn toàn bằng chứng. Sau khi viết ra hàng chục số đầu tiên $N_m = 2^m - 2$ ($m = 2, 3, 4, \dots$) và kiểm tra xem số nào chia hết cho $m$ và số nào không chia hết, các nhà toán học Trung Quốc cổ đại đã bị thuyết phục về tính đúng đắn của Giả thuyết 5 và ghi lại nó như một định lý. Tuy nhiên, bạn và tôi không phải là người Trung Quốc cổ đại. Euclid và Archimedes vĩ đại (và thậm chí trước đó là Pythagoras, Plato và Aristotle) ​​​​đã thuyết phục chúng ta rằng bản chất của toán học nằm chính xác ở việc chứng minh giả thuyết 5 và ghi lại nó như một định lý. Tuy nhiên, 我们没有证据表明 $m \neq 1$ gần như là số nguyên tố nếu hiệu $2^m - 2$ chia hết cho $m$.

Theo định lý nhỏ Fermat, mọi số nguyên tố đều gần như số nguyên tố. Vì vậy, giả thuyết 5 có thể được phát biểu lại như sau:

Giả thuyết 5'. Mà số gần như nguyên tố là số nguyên tố.

*) “Nửa” đầu tiên của Giả thuyết 5 tất nhiên là một phần của định lý Fermat.

Chúng tôi đã nói rằng các nhà toán học Trung Quốc cổ đại đã xem xét khả năng chia hết cho $m$ của vài chục số đầu tiên $N_m$ và không tìm thấy ví dụ bác bỏ. Ngày nay, với sự trợ giúp của máy tính, sẽ không khó để kiểm tra khả năng chia hết cho $m$ của hàng trăm số đầu tiên $N_m$. Tuy nhiên, ngay cả ở đây cũng không dễ để bác bỏ Giả thuyết 5: trong số 300 số tự nhiên đầu tiên, chúng ta không thể tìm thấy hầu hết các số nguyên tố không phải là số nguyên tố. Tuy nhiên, giả thuyết 5 vẫn sai, tức là nó đúng.

Định lý 2. Hầu như có số nguyên tố không phải là số nguyên tố.

Số nhỏ nhất như vậy là 341. Không thể tìm được nó, nhưng việc chứng minh nó gần như số nguyên tố không khó chút nào nếu ta có

Bổ đề 1. Hiệu $n^m - 1$ chia hết cho $n - 1$ đối với mọi $m$ và $n$, tính từ điểm các số nguyên tố không phải là số nguyên tố.

Bổ đề 2. Hiệu $n^m - 1$ chia hết cho $n - 1$ đối với mọi $m$ và $n$, tính từ điểm của các số nguyên tố không phải là số nguyên tố và $m_1 > m$.

Thật vậy, vì $m$ không phải là số nguyên tố nên $m = kL$, trong đó $k > 1$, $L > 1$. Khi đó, theo Bổ đề 1,

$$m_1 = 2^m - 1 = 2^{kL} - 1 = (2^k)^L - 1$$

chia hết cho $2^k - 1$. Từ $L > 1$ theo sau $2^k - 1 < m_1$. $k > 1$ ngụ ý $2^k - 1 > 1$. Điều này có nghĩa là $m_1$ không phải là số nguyên tố.

Vì $m$ gần như là số nguyên tố nên $m_1 = 2^m - 2 = N_m$ chia hết cho $m$: $N_m = mn$. Do đó, theo Bổ đề 1,
