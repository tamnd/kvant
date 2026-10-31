---
id: 1979-12-ore-prostyie-chisla-ferma-8e89f4b6
issue: kvant_1979_12
year: 1979
number: "12"
title: số nguyên tố Fermat
authors:
  - Оре О.
rubric: kvant-dlya-mladshih-shkolnikov
rubric_sub: «Квант» для младших школьников
page_first: 33
page_last: 35
page_labels: 31-33
tag: ALWO
lang: vi
source: kvant_digital
extraction: vision
content_sha256: 9882fbf4a74c3cd691122e5ae39ee61e7af155fc763265437f9c629548f99ce9
prompt_sha256: draft-1
translated_from: content/ru/1979/12/articles/11_ore-prostyie-chisla-ferma-8e89f4b6.md
source_content_sha256: d9f35b2c99d163f00fd9f6c0422f36cc4f7b5eba535de29f82d16b094c823d87
translation_model: draft
translation_run: vi-draft-2026-10-31
translation_quality: draft
---

⟦folio 31⟧

O. Quặng

số nguyên tố Fermat

Có lẽ một trong những tính chất đầu tiên của các con số được con người phát hiện ra là một số số có thể bị phân tách thành hai thừa số nhỏ hơn, chẳng hạn như
$$6=2\cdot 3, 9=3\cdot 3, 30=2\cdot 15=3\cdot 10,$$
trong khi những người khác, ví dụ:
$$3, 7, 13, 37,$$
không được phân tích theo cách này.

Nếu số $c$ là tích của hai số $a$ và $b$ ($c=a\cdot b$), chúng ta gọi các số $a$ và $b$ là bội số hoặc ước số của số $c$. Mỗi số có hệ số nguyên tố (đơn giản nhất):
$$c=1\cdot c=c\cdot 1.$$
Theo đó, chúng ta gọi các số 1 và $c$ là đa gel và các ước số của số $c$.

Bài viết này là nguồn mở từ cuốn sách “Lời mời đến Lý thuyết số” của O. Ore, xuất bản năm 1980 trên Biblotechek «Kvant» (bản dịch của L. Savina, do A. Savin biên tập).

Bất kỳ số $c>1$ nào có hệ số hóa không tầm thường đều được gọi là hợp số. Nếu một số lớn hơn một chỉ có hệ số hóa tầm thường thì nó được gọi là số nguyên tố. Trong 100 số đầu tiên có 25 số sau là số nguyên tố:
2, 3, 5, 7, 11, 13, 17, 19, 23, 29, 31, 37, 41, 43, 47, 53, 59, 61, 67, 71, 73, 79, 83, 89, 97 và tất cả các số khác ngoại trừ 1 đều là hợp số.

Nhiều bảng số nguyên tố đã được xuất bản trong hơn 200 năm qua. Rộng rãi nhất trong số đó là bảng của D. N. Lechmer, chứa tất cả các số nguyên tố lên tới 10.000.000.

Một số người đam mê đã biên soạn các bảng số nguyên tố lớn hơn 10.000.000, nhưng dường như việc xuất bản các bảng này chẳng có ý nghĩa gì. Chỉ trong những trường hợp rất hiếm hoi, một nhà toán học, thậm chí là một nhà toán học đặc biệt về lý thuyết số, mới giải quyết được câu hỏi liệu một số lớn hơn có phải là số nguyên tố hay không. Hơn nữa, số lớn hơn mà nhà toán học muốn biết là số nguyên tố hay hợp số không nảy sinh một cách tùy tiện. Chúng thường xuất hiện trong các bài toán đặc biệt và do đó có dạng rất cụ thể.

⟦folio 32⟧

Hãy nói về một trong những loại số nguyên tố có lịch sử lâu dài và thú vị. Những con số này lần đầu tiên được giới thiệu bởi Pierre Fermat (1601-1665), một luật sư người Pháp đồng thời là một nhà toán học kiệt xuất*). Năm số nguyên tố Fermat đầu tiên là

$$F_0 = 2^{20} + 1 = 3, \quad F_1 = 2^{21} + 1 = 5, \quad F_2 = 2^{22} + 1 = 17, \quad F_3 = 2^{23} + 1 = 257, \quad F_4 = 2^{24} + 1 = 65537.$$

Theo trình tự này, công thức tổng quát của Fermat cho số nguyên tố có dạng

$$F_n = 2^{2n} + 1.$$

Fermat hoàn toàn chắc chắn rằng tất cả các số thuộc loại này đều là số nguyên tố, mặc dù ông không tính được các số khác ngoại trừ số gót đã chỉ ra. Nhưng sau khi Leonhard Euler tiến thêm một bước nữa khi chỉ ra rằng số Fermat sau đây là:

$$F_5 = 4294967297 = 641 \cdot 6700417$$

không đơn giản, giả định này được đưa ra trong kho lưu trữ các giả thuyết toán học phi lý. Có lẽ đây sẽ là dấu chấm hết cho lịch sử của số Fermat nếu số Fermat không xuất hiện trong cách xây dựng đa giác đều hiện đại bài toán - bài toán bằng la bàn và thước kẻ.

Đa giác đều là đa giác có các đỉnh nằm trên một đường tròn nhất định với khoảng cách bằng nhau (xem hình). Nếu một đa giác đều có $n$ đỉnh thì chúng ta gọi nó là $n$-giác đều. Nếu chúng ta vẽ $n$ bán kính nối tâm của hình tròn với các đỉnh, chúng ta sẽ nhận được $n$ các góc ở tâm có kích thước $\frac{1}{n} \cdot 360^\circ$ mỗi góc. Nếu bạn có thể dựng một góc có giá trị này thì bạn có thể dựng chính đa giác đó.

Người Hy Lạp cổ đã rất quen thuộc với các phương pháp dựng đa giác đều bằng compa

*) Xem «Kvant», 1976, số 8 (ghi chú của biên tập viên).

Leonhard Euler (1707-1783).

A và thước kẻ. Tất nhiên, họ có thể xây dựng những cái đơn giản - một hình tam giác đều và một hình vuông. Bằng cách lặp đi lặp lại việc chia đôi góc ở tâm, họ cũng có thể dựng được các đa giác đều với

8, 16, 32, ...
6, 12, 24, ...
đỉnh điểm. Ngoài ra, họ còn có thể tạo ra một hình ngũ giác đều và do đó cũng có thể tạo ra các đa giác đều với

10, 20, 40, ...
đỉnh điểm. Một loại đa giác đều khác cũng thu được. Góc ở tâm của hình 15 cạnh đều là

$$\frac{1}{15} \cdot 360^\circ = 24^\circ,$$

⟦folio 33⟧

Karl-Friedrich Gauss (1777-1855).

và nó có thể thu được bằng cách sử dụng góc 72° tương ứng với một hình ngũ giác đều và góc 120° tương ứng với một tam giác đều, nếu góc thỏa mãn bị trừ đi bởi giây. Do đó, chúng ta có thể dựng các đa giác đều có 15, 30, 60, 120, ... cạnh.

Vấn đề vẫn tồn tại ở trạng thái này cho đến năm 1801. Năm đó, nhà toán học trẻ người Đức Carl-Friedrich Gauss (1777–1855) đã xuất bản một công trình về lý thuyết số, Nghiên cứu số học. Công trình này đã mở ra một kỷ nguyên mới trong toán học. Trong đó, Gauss đã vượt qua các nhà hình học Hy Lạp không chỉ ở chỗ ông chỉ ra phương pháp xây dựng chu vi và 17-giác đều tuyến tính - ông còn tiến xa hơn nhiều. Đối với tất cả các số $n$, ông đã xác định được $n$-giác nào có thể được xây dựng theo cách này và số nào không thể. Bây giờ chúng ta sẽ mô tả các kết quả mà Gauss thu được.

Chúng ta đã nói rằng, với mọi góc ở tâm chia đôi, từ một $n$-giác đều có thể thu được một $2n$-giác đều. Mặt khác, từ $2n$-gon, bạn có thể nhận được $n$-gon chỉ bằng cách sử dụng mỗi đỉnh thứ hai. Điều này cho thấy rằng chỉ cần tiến hành tìm kiếm các đa giác có thể được dựng bằng compa và thước thẳng trong số các đa giác có số đỉnh là đủ là đủ. Gauss đã chỉ ra rằng một đa giác đều có số đỉnh lẻ có thể được dựng bằng compa và thước, chỉ trong số các đa giác có số đỉnh lẻ. Đối với $n=11$ và $n=13$ không thể xây dựng $n$-gon tương ứng, nhưng nó có thể được xây dựng cho $n=15=3.5$ và $n=17$.

Khám phá của Gauss đương nhiên làm dấy lên sự quan tâm đến các số của Fermat. Trong thế kỷ qua, ponks đã được đề xuất “bằng tay”, không có sự trợ giúp của máy móc, các số nguyên tố Fermat mới. Hiện tại, những tính toán này được thực hiện với tốc độ tối đa bằng máy tính, nhưng cho đến nay kết quả vẫn âm tính. Chưa có số nguyên tố Fermat mới nào được tìm thấy. Và hiện nay nhiều nhà toán học có xu hướng tin rằng chúng không còn tồn tại nữa.

Bài tập

1. Tìm tất cả các số lẻ $n<100$ mà có thể dựng được $n$-giác thông thường.
2. Làm thế nào để xây dựng một 51-giác đều đặn cho một 17-giác đều đặn?
3. Nếu không có số nguyên tố Fermat nào khác ngoài số năm trên thì có bao nhiêu $n$-giác đều ($n$ lẻ) có thể dựng được bằng compa và thước thẳng? $n$ kỳ lạ nhất mà một $n$-gon thông thường có thể được xây dựng là gì?
