---
id: 1976-11-tsinman-paradoks-issledovatelya-6647ddb9
issue: kvant_1976_11
year: 1976
number: "11"
title: '"Nghịch lý của nhà nghiên cứu"'
authors:
  - Цинман Л. Л.
rubric: osnovnye-stati
page_first: 11
page_last: 14
page_labels: 9, 10, 12
tag: NP93
lang: vi
source: kvant_digital
extraction: vision
content_sha256: 1530ad04718daac190536bb63fbf25faaac7951cadd80d72491fb2cfcddcd2a7
prompt_sha256: draft-1
translated_from: content/ru/1976/11/articles/04_tsinman-paradoks-issledovatelya-6647ddb9.md
source_content_sha256: 0bc780ff6114f5a7c0b20f4747d14069ffb43fbabd9f71fa798c957152fe5839
translation_model: draft
translation_run: vi-draft-2026-10-31
translation_quality: draft
---

⟦folio 9⟧

L. Tsinman

"Nhà thám hiểm nghịch lý"

Khi chứng minh một mệnh đề bằng phương pháp quy nạp toán học sẽ nảy sinh một tình huống cần thiết. Hãy để chúng tôi minh họa điều này bằng hai ví dụ.

Ví dụ 1

Chúng ta hãy chứng minh bằng quy nạp toán học rằng với mọi số tự nhiên $n$ mệnh đề sau là đúng: tổng lập phương của $n$ số tự nhiên đầu tiên là bình phương của một số tự nhiên nào đó.

Hãy để chúng tôi biểu thị tuyên bố này bằng $A(n)$. Như đã biết, việc chứng minh bằng phương pháp quy nạp toán học được thực hiện theo hai giai đoạn.

a) Cơ sở quy nạp: $A(1)$. Hãy đảm bảo $A(1)$ là công bằng:
$$1^3 = 1^2.$$
6) Bước cảm ứng: $A(k) \Rightarrow A(k+1)$. Giả sử rằng đối với một số tự nhiên $k$ thì phát biểu $A(k)$ là đúng và chúng ta sẽ chứng minh điều đó thì $A(k+1)$ cũng đúng. Vì vậy, có một cách tìm số tự nhiên $p$ mà
$$1^3 + 2^3 + \ldots + k^3 = p^2.$$ (1)
Chứng minh rằng tồn tại số tự nhiên $q$ thỏa mãn
$$1^3 + 2^3 + \ldots + k^3 + (k+1)^3 = q^2.$$ (2)
Từ (2) và (1) suy ra ta cần chứng minh sự tồn tại của $q$ sao cho
$$(k+1)^3 = q^2 - p^2.$$ (3)

Nhưng làm thế nào điều này có thể được chứng minh? Đương nhiên không có cách nào chứng minh được.

Vì vậy, nỗ lực chứng minh nhận định của chúng tôi bằng cách áp dụng trực tiếp phương pháp quy nạp toán học đã gặp khó khăn khi thực hiện bước quy nạp.

Chúng ta hãy quay lại việc xem xét $A(n)$ một lần nữa và kiểm tra tính hợp lệ của nó đối với một số giá trị ban đầu $n$:
$$1^3 = 1^2;$$
$$1^3 + 2^3 = 3^2;$$
$$1^3 + 2^3 + 3^2 = 6^2;$$
$$1^3 + 2^3 + 3^3 + 4^3 = 10^2;$$
$$1^3 + 2^3 + 3^3 + 4^3 + 5^3 = 15^2.$$

Xem xét kỹ hơn các đẳng thức này, chúng ta đi đến giả thuyết: với mọi số tự nhiên $n$ mệnh đề sau là đúng: tổng lập phương của $n$ số tự nhiên đầu tiên là bình phương của một số tự nhiên bằng tổng của các số này.

Hãy để chúng tôi biểu thị tuyên bố này bằng $B(n)$. Tất nhiên, $B(n)$ mang nhiều thông tin hơn $A(n)$, và do đó, việc coi đó là một tuyên bố mạnh mẽ hơn là điều tự nhiên. Sau khi chứng minh $B(n)$, chúng ta thu được giá trị của $A(n)$ như một hệ quả hiển nhiên.

Bây giờ chúng ta thử áp dụng phương pháp quy nạp toán học để chứng minh mệnh đề được củng cố.

a) Công lý $B(1)$ trên thực tế đã được thiết lập:
$$1^3 = 1^2.$$
6) Giả sử rằng với một số tự nhiên $k$ $B(k)$ là đúng:
$$1^3 + 2^3 + \ldots + k^3 = (1 + 2 + \ldots + k)^2.$$ (4)
Hãy chứng minh rằng $B(k+1)$ cũng đúng:
$$1^3 + 2^3 + \ldots + k^3 + (k+1)^3 = (1 + 2 + \ldots + k + k + 1)^2.$$ (5)

⟦folio 10⟧

Sử dụng đẳng thức (4), chúng ta có thể rút gọn chứng minh đẳng thức (5) thành chứng minh đẳng thức
$$(k+1)^3 = (1+2+\ldots+k+k+1)^2 - (1+2+\ldots+k)^2 - \left[ \frac{(k+2)(k+1)}{2} \right]^2 - \left[ \frac{(k+1)k}{2} \right]^2 = (k+1)^3.$$

Chúng ta hãy biến đổi quy tắc của các bộ phận bình đẳng (6):
$$(1+2+\ldots+k+k+1)^2 - (1+2+\ldots+k)^2 = \left[ \frac{(k+2)(k+1)}{2} \right]^2 - \left[ \frac{(k+1)k}{2} \right]^2 = (k+1)^3.$$

Vì vậy, đẳng thức (6) được thiết lập. Do đó, với mọi $n$ $B(n)$ được chứng minh, và do đó $A(n)$.

Ví dụ 2 *)
Một ngày nọ, một giáo viên giao cho học sinh của mình bài tập về nhà bài toán này: để chứng minh, bằng cách sử dụng phương pháp quy nạp toán học, rằng với mọi số tự nhiên $n$ thì đẳng thức $A(n)$ là đúng:
$$\frac{1 \cdot 3 \cdot 5 \cdot \ldots \cdot (2n-1)}{2 \cdot 4 \cdot 6 \cdot \ldots \cdot 2n} < \frac{1}{\sqrt{n}}.$$

Kolya V., đang ngồi ở nhà để chứng minh đẳng thức này đã vô tình viết lại điều kiện của đẳng thức có sai sót, thêm 1 vào mẫu số. Vì vậy, ông lấy $B(n)$ làm bằng chứng cho đẳng thức mạnh hơn:
$$\frac{1 \cdot 3 \cdot 5 \cdot \ldots \cdot (2n-1)}{2 \cdot 4 \cdot 6 \cdot \ldots \cdot 2n} < \frac{1}{\sqrt{n+1}}.$$

Đây là bằng chứng của anh ấy.
a) Chúng tôi đảm bảo rằng $B(1)$ là công bằng:
$$\frac{1}{2} < \frac{1}{\sqrt{2}}.$$
6) Hãy chứng minh điều đó từ giá trị của $B(k)$ đối với một số tự nhiên $k$
$$\frac{1 \cdot 3 \cdot 5 \cdot \ldots \cdot (2k-1)}{2 \cdot 4 \cdot 6 \cdot \ldots \cdot 2k} < \frac{1}{\sqrt{k+1}}$$
Đẳng thức này cũng đúng với $k+1$:
$$\frac{1 \cdot 3 \cdot 5 \cdot \ldots \cdot (2k-1)(2k+1)}{2 \cdot 4 \cdot 6 \cdot \ldots \cdot 2k} < \frac{1}{\sqrt{k+1}}$$
Để làm được điều này chỉ cần chứng minh rằng
$$\frac{2k+1}{2k+2} < \frac{\sqrt{k}}{\sqrt{k+1}}.$$

Nhưng đẳng thức (9) tương đương với đẳng thức sai $k+1 < 0$.

⟦folio 12⟧

Không có bằng chứng chắc chắn nào cả.

Ở đây người đọc có kỹ năng có thể muốn phản đối. Xin lỗi, anh ta sẽ nói, nhưng làm thế nào, chẳng hạn, có thể chỉ ra rằng một số bài toán hình học cho việc xây dựng không thể giải được bằng la bàn và thước kẻ? Sự khác biệt là gì?

Nhưng điểm khác biệt là trong các bài toán xây dựng, chúng ta không nói về những công trình xây dựng thông thường mà là về những công trình xây dựng bằng hình khối sử dụng la bàn và thước kẻ. Bằng cách này, chúng tôi xây dựng chính xác phương tiện mà chúng tôi sẽ sử dụng cho lời giải. Và trong trường hợp này, bằng cách nào đó có thể mô tả lớp bài toán, lớp này có thể được giải quyết bằng các phương pháp này. Do đó, khi được đề nghị xây dựng một bài toán cụ thể, chúng ta có thể cố gắng xác định xem nó có thuộc lớp này hay không.

Vào đầu thế kỷ 19 và 20, một phương pháp xây dựng toán học đã được đề xuất cho phép người ta có được bằng chứng trực tiếp trong lĩnh vực này. Nhiều cách chứng minh khác nhau cho phương pháp này dưới dạng hệ thống hình thức.

Ở đây chúng tôi sẽ không cố gắng giải thích chính xác hệ thống hình thức là gì. Hãy chỉ nói rằng trong các hệ thống hình thức, các phát biểu toán học có ý nghĩa được viết dưới dạng các công thức được xây dựng theo các quy tắc chính xác. Một công thức được gọi là `доказуемой` nếu nó có thể được suy ra từ `аксиом` (các tiên đề là các công thức ban đầu được cố định trước) trong một số hữu hạn các bước sử dụng `правил вывода` được cố định trước. Đây là sự làm rõ đã nêu ở trên về khái niệm bằng chứng.

Logic toán học là nghiên cứu về các hệ thống hình thức *). Bài viết này không phải là nơi để viết về nó. Tôi chỉ nhấn mạnh rằng lời giải là chung chung

*) Đối với học sinh muốn làm quen với logic toán học, chúng tôi giới thiệu các cuốn sách của P. P. Stoll “Bộ. Logic. Lý thuyết tiên đề” (M., "Provesshie", 1968), E. Mendelson "Giới thiệu về logic toán học" (M., "Hayka", 1971) và P. S. Novikova "Các yếu tố của logic toán học" (M., "Hayka", 1973).

thường có thể hỏi về các cặp nghịch lý, cũng như nhiều câu hỏi quan trọng khác (ví dụ: về tính nhất quán của một nhánh toán học cụ thể hoặc về tính độc lập của một số aximon giao dịch nhất định) sau khi định dạng sơ bộ.

**Định lý**

Trong khuôn khổ phép tính số tự nhiên được đưa ra dưới dạng hệ thống hình thức, có thể trả lời câu hỏi đặt ra ở trên. Có một số hệ thống số học chính thức. Hãy để $S$ là một trong những hệ thống này. Tác giả bài viết thu được kết quả như sau.

**Định lý. Hệ thống $S$ chứa các cặp nghịch lý.**

Điểm 1 của định nghĩa cặp nghịch lý yêu cầu $A(n)$ phải là hệ quả rất mạnh của $B(n)$. Đương nhiên, khái niệm về một hệ quả rất quan trọng cũng cần được làm rõ. Trong chứng minh định lý được xây dựng của một số lý thuyết, một con ngựa và hành động cụ thể $B(n)$ tạo thành một cặp nghịch lý với bất kỳ thành viên nào của nó.

Sự kết hợp của một số câu lệnh với một mệnh đề phức tạp được tạo thành từ những câu lệnh này bằng cách sử dụng liên từ “và”. Vì vậy, sự kết hợp của nhiều mệnh đề là đúng khi và chỉ khi mỗi mệnh đề này đúng. Thật tự nhiên khi cho rằng mọi tình huống đều là hậu quả của nó.

Sự hình thành định lý cho thấy rằng trong một hệ thống số học được định dạng, số thực có thể phải đối mặt với “nghịch lý của nhà nghiên cứu”. Điều này cũng phải được tính đến khi thực hiện các phép tính có ý nghĩa bằng phương pháp quy nạp toán học.
