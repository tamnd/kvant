---
id: 1990-3-lev-poglyadim-na-diagrammu-a58cb71f
issue: kvant_1990_3
year: 1990
number: "3"
title: Chúng ta hãy nhìn vào sơ đồ
authors:
  - Лев В.
rubric: osnovnye-stati
page_first: 14
page_last: 18
page_labels: 12-16
lang: vi
source: kvant_digital
extraction: vision
content_sha256: b5dfd5a66800fae487c308bfd7cf1efadf6f5452ee2cb5b0567ba9207e00ff6b
prompt_sha256: draft-1
translated_from: content/ru/1990/03/articles/02_lev-poglyadim-na-diagrammu-a58cb71f.md
source_content_sha256: 618ea1b42ecad9f1a79138dc6c918617b7dc31c0e42393ded6bdc494977e8cfa
translation_model: draft
translation_run: vi-draft-gaps-2026-11-01
translation_quality: draft
---

⟦folio 12⟧

---
running_head:
folio:
---

ở dạng hai chữ số? Sự khái quát hóa bài toán tự gợi ý: xem xét các số trong hệ thống số có cơ số $q$, bao gồm chính xác $q$ chữ số. Để cho ngắn gọn, các quy ước chỉ gọi chúng là "$q$-số".

Hãy tự tạo ra vấn đề cho chính mình!

Hoàn toàn tự nhiên, chúng ta sẽ bắt đầu với việc phát biểu vấn đề mà chúng ta sắp viết ra. Và gợi ý cho chúng tôi là việc tái tạo lại bản gốc bài toán một cách đơn giản.

Hãy xem xét một số $q$-số. Chúng ta hãy xây dựng một số $q$ mới từ nó như sau: chữ số đầu tiên của số mới này sẽ bằng số hàng đơn vị trong số ban đầu, chữ số thứ hai - số hai,..., số áp chót - số chữ số "$q$ - 1", chữ số cuối cùng - số các số 0 trong số ban đầu. Vì vậy, chúng tôi đã xác định một số ánh xạ trên các số $q$; Màn hình này được điều chỉnh ở mức hình 1.

bài toán ban đầu là tìm “điểm trì trệ” của ánh xạ đó, tức là một số $q$ mà trong ánh xạ này biến thành chính nó (ví dụ: số 12002 trên hình 1).

Bây giờ chúng ta hãy thử theo dõi số phận của một số $q$ trong màn hình của chúng ta. Mặc dù không có quá ít số $q$ (hãy nghĩ xem có bao nhiêu), nhưng vẫn có một số lượng hữu hạn trong số đó. Do đó, các ảnh liên tiếp của số $q$ ban đầu không thể nào khác nhau được. Điều này có nghĩa là, bắt đầu từ một vị trí nhất định, những hình ảnh này bắt đầu lặp lại theo chu kỳ - một chu kỳ sẽ xuất hiện tương tự như những hình ảnh được mô tả bên phải trong hình 1. Tất nhiên, điểm không chuyển động là

$$\begin{array}{c c c c c}
8010071741 & 3001003 & 1020004 \\
3001002103 & 1101004 \\
212000005 & 12002 & 111003 \rightarrow 301002
\end{array}$$

Hình 1.

 chu kỳ của đơn vị chiều dài. Nhưng cũng rất thú vị khi mô tả tất cả các chu kỳ của việc lập bản đồ như vậy. Đây chính xác là vấn đề của chúng ta!

Bài tập. Chúng ta hãy liên kết với số $q$ $A = (a_1 a_2 \dots a_q)$ số lượng $s(A) = a_1 + a_2 + \dots + a_q$; $m(A) = a_1 + 2a_2 + \dots + (q-1)a_{q-1}$. Chứng minh rằng nếu số $q$ $A$ là ảnh của một số $q$-số $B$ khác dưới ánh xạ của chúng ta, thì $s(A) = q$. Ngoài ra, $s(B) = m(A)$.

Sơ đồ trẻ

Người đọc «Kvant» có lẽ đã quen thuộc với những sơ đồ như vậy; lỗi thường phát sinh khi giải các câu hỏi về phép chia số tự nhiên thành các số hạng. Một số ví dụ được mô tả trong hình 2, trong đó thứ tự của nó được biểu thị bên cạnh mỗi sơ đồ - tổng số ô vuông trong tất cả các cột của sơ đồ. Chiều cao của cột tăng dần từ phải sang trái.

Chúng ta sẽ gọi một nhóm cột là tập hợp tất cả các cột của biểu đồ có chiều cao nhất định, trừ khi số lượng cột như vậy ít hơn hai; Chúng tôi sẽ gọi tất cả các cột khác (tức là những cột không được bao gồm trong bất kỳ nhóm nào) là các cột riêng biệt.

Tại sao chúng ta cần chúng?

Đã đến lúc giải thích bài toán của chúng tôi có liên quan như thế nào với sơ đồ Young. Trước hết, bằng cách chỉ ra một phương thức gán cho bất kỳ số $q$ nào một sơ đồ thứ tự nhất định $q$. Đây là phương pháp xác sống này: hãy sắp xếp lại các số trong số $q$ sao cho các số giống nhau nằm trong một hàng, hợp nhất chúng thành các hình chữ nhật nằm ngang và sau đó “xoay” các hình chữ nhật này bằng cách đặt chúng theo chiều dọc; hãy xem hình3!

Tất nhiên, cùng một sơ đồ có thể tương ứng với các số $q$ khác nhau: ví dụ: nếu các số này được lấy từ nhau bằng các hoán vị nhất định và thiết kế lại các chữ số (xem hình 4). Điều ngược lại cũng hiển nhiên: nếu hai số $q$ có ​​cùng sơ đồ Young thì mỗi số có thể lấy được từ số kia bằng các hoán vị như vậy

⟦folio 13⟧

---
running_head:
folio:
---

Puc. 2. $q=11, q=14, q=4, q=3, q=5$.

8 0 1 0 0 7 1 7 4 1
0 0 0 1 1 1 7 7 4 8

1 1 1 0 0 3
1 1 1 0 0 3

Puc. 3.

320013 → 0 0 3 3 1 2
045451 → 4 4 5 5 0 1
123434 → 3 3 4 4 1 2

Puc. 4.

Puc. 5.

Puc. 6.

⟦folio 14⟧

---
running_head:
folio:
---

và chỉ định lại. Bây giờ hãy lưu ý rằng hình ảnh của chúng trong ánh xạ các số $q$ của chúng tôi được lấy từ nhau bằng cách sắp xếp lại các chữ số (hãy nhớ kiểm tra điều này!), và do đó những hình ảnh này cũng có cùng một sơ đồ. Chúng tôi đã chứng minh điều sau:

nếu hai số $q$ tương ứng với cùng một sơ đồ Young thì ảnh của chúng cũng tương ứng với cùng một sơ đồ Young.

Tuyên bố này, mặc dù đơn giản, nhưng có tầm quan trọng quyết định đối với chúng tôi. Trong mọi trường hợp, bạn không nên đọc thêm bất kỳ điều gì trong bài viết này cho đến khi nó hoàn toàn rõ ràng với bạn!

Điều gì tiếp theo từ điều này?

Chúng ta hãy lấy một số sơ đồ thứ tự Young $q$ và xem xét bất kỳ số $q$ nào tạo ra nó. Sau đó chúng ta hãy tìm ảnh của số $q$ này và lần lượt xây dựng sơ đồ tương ứng với ảnh này; Câu lệnh "xanh lam" (xem ở trên) có nghĩa là sơ đồ cuối cùng này hoàn toàn được xác định bởi sơ đồ được lấy ở đầu. Do đó, ánh xạ mà chúng tôi đã giới thiệu ở trên vào tập hợp các số $q$ xác định một ánh xạ nhất định lên tập hợp các sơ đồ thứ tự Young $q$. Ví dụ về ánh xạ sau này được đưa ra ở hình 5.

Tất nhiên, bất kỳ chu trình ánh xạ nào lên các số $q$ sẽ xác định một số chu trình ánh xạ lên các sơ đồ thứ tự Young $q$. Điều này cho phép chúng ta chuyển từ tìm kiếm chu trình trên các số $q$ sang tìm kiếm chu trình trên sơ đồ Young. Tất nhiên, khi đó bạn sẽ cần phải “quay lại” bằng cách tìm từng chu kỳ trên sơ đồ Young tất cả các chu kỳ tương ứng trên các số $q$. Tuy nhiên, điều này làm cho nó khá dễ dàng; Chúng tôi sẽ quay lại vấn đề này ở phần cuối.

Vì vậy, bài toán của chúng tôi chuyển đổi thành như sau:

tìm tất cả các chu trình trên sơ đồ trật tự Young $q$ được xác định bằng sơ đồ ánh xạ đã giới thiệu ở trên.

Hãy cùng tìm hiểu...

“cách hoạt động” hiển thị sơ đồ Young mà chúng tôi đã xây dựng. Mỗi cột riêng lẻ của sơ đồ gốc tương ứng với một chuỗi chữ số của số gốc, có độ dài “duy nhất” và do đó tương ứng với một chữ số duy nhất nào đó của số hình ảnh, tức là cuối cùng, tương ứng với một cột của sơ đồ hình ảnh, có chiều cao đơn vị. Theo cách tương tự, mỗi nhóm cột của sơ đồ gốc tương ứng với một cột của sơ đồ hình ảnh, chiều cao của cột này bằng chiều rộng của đế của nhóm cột này. Ngoài ra, các chữ số 0 của số ảnh không tương ứng với các hàng chữ số phía dưới của số gốc. Các số 0 này tạo ra một cột khác của sơ đồ hình ảnh mà chúng ta sẽ gọi là `дополнительным`.

Để ánh xạ sơ đồ nguồn thành sơ đồ hình ảnh, bạn phải:

1) vẽ một hình chữ nhật “dài” có chiều cao bằng một và chiều dài $q$ ô, căn chỉnh cạnh trái và đáy của nó với cạnh trái và đáy của sơ đồ ban đầu;

2) chia hình chữ nhật “dài” thành nhiều cạnh ngắn theo chiều dọc, hạn chế các nhóm cột và cột riêng lẻ của sơ đồ gốc;

3) Đặt các hình chữ nhật ngắn thu được theo chiều dọc, tạo một sơ đồ Young mới từ chúng. Đây sẽ là sơ đồ hình ảnh.

Việc ánh xạ các sơ đồ trật tự Young $q$ có thể được mô tả hoàn toàn bằng một biểu đồ cho biết sơ đồ nào sẽ đi vào sơ đồ nào. Đối với các giá trị $q<7$ các biểu đồ như vậy được mô tả trong hình 7. Ví dụ: có thể thấy rằng đối với $q=2$ và $q=6$, mỗi biểu đồ có chính xác một chu kỳ, bao gồm hai sơ đồ; tại $q=5$ và $q=7$ mỗi nơi có một điểm và tại $q=4$ có hai điểm cố định; các chu trình của ba sơ đồ chỉ có cho $q=3$ và $q=7$ (như chúng tôi sẽ chứng minh sau đó, không có chu trình nào như vậy cho bất kỳ giá trị nào khác của $q$).

⟦folio 15⟧

---
running_head:
folio:
---

và bây giờ chúng tôi đã hoàn toàn sẵn sàng cho việc này. Vì trường hợp $q < 7$ đã được giải quyết thành hình 7 nên chúng tôi sẽ giả định rằng $q > 7$. Một người đọc chú ý có thể đã đồng ý về ý tưởng chính của chúng tôi: hãy nhớ rằng, khi mô tả cách hiển thị trên sơ đồ Young, chúng tôi đã nói rằng “mỗi nhóm cột của sơ đồ gốc tương ứng với một cột của sơ đồ hình ảnh”? Điều này có nghĩa là, theo quy luật, số cột khi chuyển sang sơ đồ hình ảnh chỉ có thể giảm đi. Chính xác hơn, số cột chỉ có thể tăng lên nếu tất cả các cột của sơ đồ gốc đều tách biệt; số lượng cột chỉ có thể không thay đổi nếu sơ đồ chứa chính xác một nhóm

Hình 7.

py, bao gồm hai cột và tất cả các cột khác phải được phân tách. lời giải của chúng tôi sẽ dựa trên điều này: xét cho cùng, nếu chúng tôi lấy bất kỳ chu trình nào trong sơ đồ Young, thì tất cả các sơ đồ của chu trình này sẽ chứa cùng một số cột hoặc ít nhất một sơ đồ của chu trình sẽ chứa ít cột hơn hình ảnh của nó. Nói cách khác, trong mỗi chu kỳ, hoặc tất cả các sơ đồ đều chứa một nhóm gồm hai cột và một số cột riêng lẻ (không đổi cho tất cả các sơ đồ của chu trình); hoặc có một sơ đồ chỉ bao gồm các cột riêng lẻ. Bây giờ chúng ta sẽ lần lượt xem xét hai khả năng này.

A. Giả sử tất cả các sơ đồ chu trình của chúng ta bao gồm một nhóm gồm hai cột và một số cột riêng lẻ nhất định, giống nhau đối với tất cả các sơ đồ của chu trình.

Chúng ta hãy nhìn vào một số sơ đồ chu trình. Sơ đồ hình ảnh của nó cũng thuộc một chu trình sẽ bao gồm một cột có chiều cao bằng 2, một số cột có chiều cao nhất định bằng một và một cột bổ sung; vì sơ đồ này tuân theo quy tắc chung - “một nhóm gồm hai và một số cột riêng biệt nhất định” - nên dễ dàng kiểm tra xem số cột có chiều cao đơn vị chính xác là 2 và cột bổ sung có chiều cao ít nhất là ba ô (trong trường hợp này, phải tính đến điều kiện $q > 7$). Nhưng khi đó sơ đồ vòng lặp tiếp theo sẽ bao gồm một cột có chiều cao 2, hai cột có chiều cao đơn vị và một cột bổ sung có chiều cao $q - 4$; Tất cả các sơ đồ tiếp theo sẽ có dạng giống nhau, tức là trên thực tế, chu trình của chúng ta chỉ bao gồm một phần tử - đó là một điểm cố định trong cách hiển thị Sơ đồ trật tự Young $q$ (xem hình 8 ở bên trái).

B. Giả sử một trong các sơ đồ chu trình của chúng ta chỉ bao gồm các cột riêng lẻ.

Khi đó sơ đồ sau bao gồm các cột có chiều cao đơn vị và

⟦folio 16⟧

---
running_head:
folio:
---

một cột bổ sung có chiều cao lớn hơn 1 (điều này là hiển nhiên, vì chiều cao của cột bổ sung bằng số ô trong sơ đồ gốc, “không thấp hơn tầng hai” của sơ đồ). Đổi lại, hình ảnh của sơ đồ này sẽ bao gồm ba cột, một trong số đó có cùng chiều cao. Cả ba cột này không thể có cùng chiều cao (tại sao?); nếu hai độ cao nào đó trùng nhau thì sơ đồ chu trình tiếp theo vẫn gồm ba cột có độ cao khác nhau; biểu đồ sau sẽ bao gồm ba cột có chiều cao duy nhất và một cột bổ sung có chiều cao $q-3$; cột tiếp theo là một cột mới trong ba cột có chiều cao khác nhau (bằng 3, 1 và $q-4$: chúng ta mới sử dụng điều kiện $q>7$), v.v., - chúng ta đi đến một chu trình bao gồm hai sơ đồ (xem hình 8 ở bên phải).

bài toán lời giải của chúng tôi. Chúng tôi đã chỉ ra rằng để ánh xạ tới sơ đồ Young, thứ tự $q>7$ có ​​chính xác hai chu kỳ: một điểm cố định và một chu trình có độ dài 2.

Quay lại số $q$!

Để hoàn thành đầy đủ nghiên cứu nhỏ của chúng tôi, chúng tôi vẫn phải quay lại từ sơ đồ Young về các số $q$ để xác định chu kỳ nào trên các số $q$ có thể tạo ra hai chu kỳ mà chúng tôi đã tìm thấy trên sơ đồ Young cho $q>7$. May mắn thay, không khó để tiếp tục.

Hãy bắt đầu với chu trình có độ dài 1 - một điểm cố định trong phần hiển thị sơ đồ Young. Số tạo ra sơ đồ duy nhất của chu trình này bao gồm một nhóm gồm $(q-4)$ chữ số giống nhau, một nhóm gồm hai chữ số và một số hai chữ số khác nhau;

do đó, hình ảnh của số này sẽ bao gồm các chữ số $(q-4)$, 2, 1, 1 và tất cả các chữ số khác của hình ảnh sẽ là số 0; nhưng sau đó hình ảnh tiếp theo sẽ có chữ số đầu tiên 2, chữ số thứ hai 1, chữ số thứ $(q-4)$1, chữ số cuối cùng $(q-4)$ và các chữ số còn lại là số 0; Tất cả các hình ảnh tiếp theo sẽ trông giống nhau. Vì vậy, chu trình duy nhất trên các số $q$ tạo ra một điểm cố định của bản đồ sơ đồ Young bản thân nó là một điểm cố định: nó bao gồm một số duy nhất 210...010...0 $(q-4)$ (đơn vị thứ hai nằm ở vị trí $(q-4)$). Tại $q=10$ bạn đã gặp con số này ngay đầu bài viết.

Một chu trình có độ dài 2 được xử lý theo cách tương tự. Chúng tôi sẽ để lại thông tin chi tiết cho người đọc quan tâm, nhưng ở đây chúng tôi sẽ chỉ báo cáo kết quả: chu trình này cũng được tạo ra bởi đúng một chu kỳ cho mỗi số $q$, bao gồm hai phần tử: 30...0100 $(q-4)$ và 1010...01000 $(q-3)$.

Và cuối cùng - chưa được giải quyết bài toán

Vì vậy, chúng ta biết rằng mọi số $q$ cuối cùng sẽ kết thúc ở một điểm cố định hoặc một chu kỳ có độ dài bằng hai. Nhưng làm thế nào để dự đoán được “số phận” của một con số $q$ cụ thể? Có lẽ có một dấu hiệu cho phép người ta xác định bằng loại số nào trong hai khả năng thực hiện. Tác giả đã không thể tìm thấy một dấu hiệu như vậy. Có lẽ một số độc giả có thể giải quyết được bài toán này?
