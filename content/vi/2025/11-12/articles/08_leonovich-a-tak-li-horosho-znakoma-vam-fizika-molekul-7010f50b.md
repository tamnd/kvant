---
id: 2025-11-12-leonovich-a-tak-li-horosho-znakoma-vam-fizika-molekul-7010f50b
issue: kvant_2025_11-12
year: 2025
number: 11-12
title: Bạn quen thuộc với vật lý phân tử như thế nào?
authors:
  - Леонович А. А.
rubric: kaleydoskop-kvanta
rubric_sub: Калейдоскоп
page_first: 34
page_last: 46
page_labels: 34, 35, 37, 38, 40, 44
lang: vi
source: kvant_digital
extraction: vision
content_sha256: e8c4a46b9ec89a5e1f7dfe200ca202f022e870f2c13b72bb0180782826b57d97
prompt_sha256: draft-1
translated_from: content/ru/2025/11-12/articles/08_leonovich-a-tak-li-horosho-znakoma-vam-fizika-molekul-7010f50b.md
source_content_sha256: a438ae2454da7ff0d26efd2950a7f3aa104957456ebd84a3e7fc75472d21f671
translation_model: draft
translation_run: vi-draft-gaps-2026-11-04
translation_quality: draft
---

⟦folio none⟧

Bạn có quen thuộc với VẬT LÝ CỦA PHÂN TỬ?

Thật không dễ dàng để tách biệt hai nửa được kết nối bằng dấu gạch nối nhân danh lý thuyết nguyên tử-phân tử - chúng có mối liên hệ rất chặt chẽ trong lịch sử hình thành nó. Tuy nhiên, trong số trước của Kính vạn hoa «Kvant» chúng tôi vẫn cố gắng tập trung vào cấu trúc và tính chất của chính các nguyên tử. Hôm nay chúng tôi tập trung sự chú ý của người đọc vào sự liên kết của họ trong một “công ty” (hoặc “nhóm”) – các phân tử.

Cuộc trò chuyện ngày càng trở nên quy mô lớn, và có lẽ, chúng ta sẽ phải tiếp tục nó để ủng hộ vai trò cực kỳ quan trọng của lý thuyết này không chỉ trong việc tìm hiểu cấu trúc vi mô của vật chất mà còn trong việc giải thích các đặc điểm vĩ mô của nó.

Câu hỏi và bài toán

1. Khoảng cách giữa các phân tử thay đổi như thế nào nếu nước trong bình đóng băng?
2. Khí nào ở nhiệt độ nhất định có nội năng lớn hơn - lý tưởng hay thực (với số lượng phân tử bằng nhau)?
3. Xác định xem sản phẩm $pV$ sẽ giảm hay tăng khi độ dốc khí rất mạnh, nếu không được coi là lý tưởng.

4. Động năng của chuyển động của các phân tử tương ứng với thế năng tương tác của chúng trong các chất rắn, lỏng và khí như thế nào?
5. So sánh động năng trung bình của chuyển động tịnh tiến và vận tốc bình phương trung bình gốc của các phân tử oxy và hydro ở nhiệt độ $t = 27$ °C.
6. Sau khi căn phòng được sưởi ấm, nhiệt độ trong đó tăng từ 15 lên 27°C. Số lượng phân tử tiếp xúc trong phòng thay đổi như thế nào?
7. Trong một bình kín, một mẩu than nhỏ cháy hoàn toàn. Tàu được làm lạnh đến nhiệt độ đầu tiên. Áp suất khí trong bình có thay đổi so với ban đầu không?
8. Điều gì sẽ xảy ra với áp suất của chất khí trong bình kín nếu vận tốc trung bình của các phân tử của nó tăng 20%?
9. Tại sao nhiệt dung mol của các loại khí đơn nguyên tử khác nhau có giá trị thực tế giống hệt nhau?
10. Làm thế nào chúng ta có thể giải thích rằng các phân tử khí quyển dưới tác dụng của trọng lực không chìm xuống bề mặt các hành tinh?
11. Không khí bao gồm khoảng 4/5 nitơ và 1/5 oxy. Khối lượng mol của nó là bao nhiêu?

⟦folio 34⟧

---
running_head:
folio:
---

Tất nhiên, số mũ của bậc $t$ không bị giảm theo Mô hình 2. Bạn thậm chí có thể chia đa thức với số dư. Ví dụ: hãy chia $t^4 + t^3 + t + 1$ cho $t^3 + t + 1$ (hãy nhớ rằng $-1 = +1$ nằm trong trường $\mathbb{F}_2$):

$$\begin{align*}
t^4 + t^3 + 0t^2 + t + 1 &\mid \frac{t^3 + t + 1}{t + 1} \\
t^4 + t^2 + t &\mid t^3 + t^2 + 1 \\
t^3 + t^2 + 1 &\mid t^2 + t
\end{align*}$$

Người ta biết rằng trường hữu hạn $\mathbb{F}_q$ tồn tại khi và chỉ khi số $q$ là lũy thừa của số nguyên tố: $q = p^n$. Tại $n = 1$ đây là các trường dư từ mô hình $p$ mà chúng ta vừa nói đến. Và tại $n > 1$ có một “vườn thú” lớn hơn của các trường hữu hạn, mà bất kỳ ai ngoài đại số và mật mã hầu như không biết gì về nó. Việc xây dựng trường trong trường hợp này không đơn giản và trên thực tế, không thuận tiện đến mức phải thực hiện ngay các phép tính trong trường hữu hạn.

Ví dụ 2: Đối với lời giải bài toán của chúng ta, chúng ta cần trường $\mathbb{F}_8$. Bây giờ chúng tôi sẽ giải thích cách nó hoạt động. Trước tiên, hãy sửa (đây là thủ thuật chính!) đa thức $U(t) = t^3 + t + 1$ trên trường $\mathbb{F}_2$. Các phần tử của trường $\mathbb{F}_8$ đều là các đa thức có thể có trên trường $\mathbb{F}_2$, có bậc không cao hơn 2. Dễ dàng báo cáo rằng chỉ có 8 đa thức như vậy:

$$\mathbb{F}_8 = \{0, 1, t, t + 1, t^2, t^2 + 1, t^2 + t + 1\}.$$

Phép cộng các phần tử là phép cộng tổng quát của các đa thức (hãy nhớ rằng các hệ số nằm trong khoảng $\mathbb{F}_2$). Phép nhân phức tạp hơn: khi nhân các phần tử $f_1$ và $f_2$, trước tiên chúng ta coi chúng là đa thức trên trường $\mathbb{F}_2$, và sau đó chúng ta tìm phần còn lại của tích này khi chia cho đa thức $U(t)$. Phần còn lại này sẽ là tích $f_1f_2$ trong trường $\mathbb{F}_8$. Ví dụ:

$$\begin{align*}
(t^2 + 1) \cdot (t^2 + t + 1) &= t^4 + t^3 + 2t^2 + t + 1 \\
&= t^4 + t^3 + t + 1 \mid \mod 2 \\
&= t^4 + t^3 + t + 1 \mid \mod U
\end{align*}$$

Đẳng thức cuối cùng được chứng minh bằng phép chia.

Chúng tôi sẽ không kiểm tra xem trường kết quả đã được tạo hay chưa, đặc biệt vì chúng tôi không có định nghĩa trường. Chúng ta chỉ cần lưu ý rằng việc xây dựng một bảng nhân không quá khó, và từ đó sẽ thấy rõ, chẳng hạn, mọi phần tử khác 0 đều có một phép nhân nghịch đảo.

Mũ liên tục

Hãy thử giải “phiên bản liên tục” của bài toán của chúng tôi. Có 4 nhà thông thái, và ác quỷ có vô số chiếc mũ: chẳng hạn, với mỗi số thực $a \in \mathbb{R}$ hắn có một chiếc mũ được đánh số $a$. Trong tình huống này, liệu ba nhà thông thái có đoán được số chiếc mũ hay không? Trên thực tế, họ có thể làm như vậy mà không gặp bất kỳ vấn đề gì - nhà hiền triết đầu tiên có thể cho biết phần còn lại của màu sắc của họ, sử dụng các thao tác với ký hiệu thập phân. Ví dụ, nó có thể được thực hiện như thế này. Màu sắc là một số được viết dưới dạng phân số thập phân vô hạn

$$a = \alpha_m \alpha_{m-1} \dots \alpha_1, a_1 a_2 a_3 \dots$$

Biết màu $a, b, c$ của các hiền nhân còn lại (và, nếu cần, thêm các số 0 vào đầu để chúng có số bằng nhau trong toàn bộ phần), hiền nhân đầu tiên sẽ luôn có thể “thu gọn” chúng thành một màu:

$$\alpha_m \beta_m \gamma_m \dots$$

$$\dots \alpha_2 \beta_2 \gamma_2 \alpha_1 \beta_1 \gamma_1, \dots \alpha_1 b_1 c_1 a_2 b_2 c_2 a_3 b_3 c_3 \dots$$

Ở đây, các chữ số được đánh dấu hoa thị được điền bằng số để truyền dấu của các số ban đầu và để phân số thu được không trùng với phân số ban đầu.

Vâng, điều đó có nghĩa là trong trường hợp thực tế đáp số trong bài toán này – vâng, ba nhà thông thái có thể đoán màu.

Chiến lược đoán được đề xuất khó có thể chuyển sang một trường hợp riêng biệt, vì vậy chúng ta hãy thử xây dựng chiến lược dựa trên một ý tưởng khác. Sau khi thêm một chiếc mũ (chiếc mũ nhỏ này không ảnh hưởng gì), chúng ta sẽ giả sử rằng những chiếc mũ được đánh số theo điểm của tập $\overline{R}$ và áp dụng... các hàm tuyến tính tương tự.

⟦folio 35⟧

---
running_head:
folio:
---

Chiến lược trong trường hợp $\overline{R}$. Lưu ý rằng thông tin mà mỗi hiền nhân có được khi đoán là ba màu (nhìn thấy hoặc có điều kiện) của chiếc mũ của đồng nghiệp mình. Hãy để những người khôn ngoan cho rằng chiếc mũ họ đội có màu sắc

$$a = g(1), b = g(2), c = g(3), d = g(4),$$

trong đó $g$ là một số hàm phân số tuyến tính (và 1, 2, 3, 4 là số thực). Giả định này hoàn toàn không chính xác nếu bạn đoán cả bốn điều của riêng mình. Nhưng chúng ta có nhà hiền triết đầu tiên, và với cái giá phải trả là không phải đoán, anh ta thực sự có thể đảm bảo đáp ứng đặc tính này trong bất kỳ cách sắp xếp màu sắc nào - suy cho cùng, những người khác không nhìn thấy chiếc mũ của anh ta mà chỉ nghe những gì anh ta nói. Để làm điều này, anh ấy chỉ cần nhìn vào màu sắc $b, c, d$ mũ của đồng nghiệp và chọn hàm phân số tuyến tính $g$ cho $b = g(2), c = g(3), d = g(4)$. Theo định lý về hàm tuyến tính phân số, hàm như vậy tồn tại và là duy nhất. Tiếp theo, anh ấy tính màu $a = g(1)$ và đặt tên nó là đáp số của mình. Nhân tiện, hãy lưu ý rằng $a$ không khớp với bất kỳ màu nào trong số $b, c$ và $d$, vì hàm $g$ là tính từ. Từ nay trở đi, các hiền nhân khác tin rằng hiền nhân đầu tiên có chiếc mũ màu $a$.

Bây giờ những nhà hiền triết còn lại sẽ đoán như thế nào? Nhà hiền triết thứ hai nhìn thấy màu $c$ và $d$ và nghe thấy màu $a$. Nó sẽ cố gắng tìm hàm phân số tuyến tính $h$ mà $a = h(1), c = h(3), d = h(4)$. Vì chỉ có một chức năng như vậy và nhà hiền triết đầu tiên đảm bảo với chúng ta rằng $a = g(1), c = g(3), d = g(4)$, cuộc tìm kiếm của nhà hiền triết đầu tiên kết thúc bằng việc anh ta tìm thấy chức năng duy nhất có thể có $h = g$. Sau đó, anh ấy sẽ đặt tên $h(2) = g(2) = b$ làm màu của mình, tức là Đoán màu của bạn! Tình huống tương tự với các nhà thông thái khác: khi tìm kiếm hàm $h$, trong đó $a = h(1), b = h(2), d = h(4)$, người thứ ba sẽ tìm thấy hàm tương tự $g$ và cũng đoán màu của anh ta. Và bốn người sẽ hành động theo cùng một cách.

Chiến lược hiền triết
cho chín chiếc mũ

Người khôn ngoan nên làm gì nếu chỉ có 9 chiếc mũ? Liệu ba nhà thông thái có đoán được trong trường hợp này không? Có, nếu họ sử dụng các hàm tuyến tính phân số trên trường $\mathbb{F}_8$.

Hãy thêm một điểm nữa vào trường cuối cùng $\mathbb{F}_8$, điểm này sẽ biểu thị $\infty$ và biểu thị nó $\mathbb{F}_8 = \mathbb{F}_8 \cup \{\infty\}$. Quy tắc (1), (2), (3) cho phép bạn chỉ định các hàm phân số tuyến tính

$$f(x) = \frac{ax + b}{cx + d},$$ trong đó $a, b, c, d \in \mathbb{F}_8$ là ánh xạ hoạt động từ $\mathbb{F}_8$ đến $\mathbb{F}_8$. Định lý về hàm phân số tuyến tính sẽ đúng cho trường hợp $\mathbb{F}_8$: bất kỳ ba điểm phân biệt bất kỳ của tập hợp $\mathbb{F}_8$ đều có thể được ánh xạ tới ba điểm phân biệt bất kỳ và hàm thực hiện điều này được xác định duy nhất.

Bây giờ các nhà hiền triết có thể áp dụng chiến lược từ phần trước bằng cách lấy bộ $\mathbb{F}_8$ cùng với $\mathbb{R}$. Và cùng với các số thực 1, 2, 3, 4 chúng ta nên lấy bốn phần tử $\mathbb{F}_8$, ví dụ 1, $t$, $t + 1$, $t^2$.

Đáp số

Vì vậy, câu hỏi chính của chúng ta: ở mức $k > 4$ nào thì ba nhà thông thái (trong số bốn người) được đảm bảo có thể đoán được màu của chiếc mũ? Mặc dù bài toán khá gần đây, nhưng ý tưởng chính đằng sau và nhìn chung, lời giải này bài toán được đưa ra trong bài viết của L. Teerlink [3]. Đáp số: cho tất cả $k > 4$ ngoại trừ $k = 7$.

Đối với tất cả $k > 9$, có thể xây dựng một chiến lược đoán duy nhất và nó (theo ngôn ngữ của các nhóm quasigroup) được đưa ra trong bài viết của Teerlink. Trong phần tiếp theo, chúng tôi sẽ mô tả một cấu trúc ít phổ biến hơn một chút - nó hoạt động với $k > 23$ - nhưng là một cấu trúc đơn giản hơn đáng kể được đề xuất bởi cùng một bài viết.

Đối với $k = 6, k = 8$ và nói chung cho cả bốn $k$, có một chiến lược hay duy nhất. Nó được đưa ra trong lời giải bài toán M2857.

Trường hợp $k = 9$ hóa ra là một trong những trường hợp phức tạp nhất, không phải vô ích mà chúng tôi đã dành rất nhiều công sức cho nó.

⟦folio none⟧

---
running_head:
folio:
---

đối với $k = 5 = 2^2 + 1$, chiến lược có thể được xây dựng bằng cách sử dụng bài toán Shapovalov và Knop đã đề cập ở phần đầu (bạn chỉ cần giải nó trước) hoặc bạn có thể, tương tự như trường hợp $k = 9$, áp dụng các hàm phân số tuyến tính trên tập hợp $\mathbb{F}_4 \cup \{\infty\}$.

Nhưng trong trường hợp $k = 7$, nếu ma quỷ làm đúng thì ba nhà thông thái sẽ không đoán được mũ của mình. Tuyên bố này cũng là bài toán dành cho người đọc mà là về lập trình. Kết quả này có được ngay sau công việc của Teerlink bằng cách sử dụng ước tính trên máy tính.

Chiến lược gần như phổ quát

Trong tổ hợp có một phần lớn - lý thuyết về thiết kế, trong đó họ xem xét bài toán các tập hợp thỏa mãn các hạn chế khác nhau về sự sắp xếp lẫn nhau của chúng. Điều này bao gồm hình học hữu hạn, hệ thống Steiner, tất cả các loại thiết kế tổ hợp, v.v. bài toán của chúng tôi về bột xô thơm có liên quan đến kiểu xây dựng này.

Ví dụ 3: Chiến lược hiền nhân mà chúng tôi xây dựng cho $k = 9$ thực sự là một tập hợp $S$ gồm bốn điểm phân biệt được sắp xếp theo thứ tự của tập hợp 9 phần tử $\mathbb{F}_8$, có các thuộc tính sau:

• đối với bất kỳ bộ ba có thứ tự $(b,c,d)$ của các phần tử riêng biệt $\mathbb{F}_8$ đều có một phần tử duy nhất $a \in \mathbb{F}_8 \setminus \{b,c,d\}$ mà $(a,b,c,d) \in S$ (nhờ quy tắc này, đáp số của hiền nhân đầu tiên được xác định duy nhất);

• đối với bất kỳ bộ ba có thứ tự $(a,c,d)$ của các phần tử riêng biệt $\mathbb{F}_8$ đều có một phần tử duy nhất $b \in \mathbb{F}_8 \setminus \{a,c,d\}$ mà $(a,b,c,d) \in S$ (nhờ quy tắc này, nhà thông thái thứ hai đoán);

• thêm hai đặc tính tương tự nữa cho nhà thông thái thứ ba và thứ tư.

Chiến lược hiền triết ở $k > 23$. Đặt $N = \{1,2,...,k\}$ là tập hợp các số mũ, $k > 23$. Để mô tả chiến lược, chúng ta sẽ chuẩn bị trước “đạo cụ”. Chúng ta sẽ cần ba “nền” - bộ kết hợp thiết kế đặc biệt được mô tả bên dưới.

Người đầu tiên hỏi. Hãy sử dụng định lý sau đây từ lý thuyết thiết kế.

Định lý 2 (về họ đường). Đặt một tập hợp $N$ nhất định gồm $k$ phần tử, $k > 23$. Khi đó có một họ $\mathbb{L}$ gồm các tập con của tập hợp này; chúng ta sẽ gọi các tập con này là tuyến tính, thỏa mãn tính chất:

1) với bất kỳ $l_1,l_2 \in \mathbb{L}$ giao điểm $l_1 \cap l_2$ bao gồm nhiều nhất một điểm,

2) với bất kỳ $a_1,a_2 \in N$ ($a_1 \neq a_2$) nào đều có một dòng duy nhất $l \in \mathbb{L}$ mà $\{a_1,a_2\} \subset l$,

3) mỗi dòng bao gồm 4, 5 hoặc 6 điểm.

Chúng tôi đã lấy nhận định này ở bài viết [2]. Việc chứng minh định lý khá nhàm chán: bạn cần tích lũy các ví dụ cụ thể về họ đường cho các tập hợp nhỏ $N$ và ngoài ra, hãy phát minh ra các định lý hàm tạo cho phép bạn xây dựng các định lý lớn hơn từ các ví dụ nhỏ. Kết quả là, đối với tất cả $k$ đủ lớn sẽ có phần tử $k$ được đặt trên dòng. Đối với các bộ 4, 5 và 6 phần tử, phạm vi liên tục bắt đầu ở $k = 24$, mặc dù tuyên bố này cũng đúng với một số giá trị nhỏ hơn của $k$.

Sử dụng định lý này, chúng ta có thể giả sử rằng đối với tập mũ $N$ một họ dòng $\mathbb{L}$ đã được xây dựng, bao gồm các tập hợp con 4, 5 và 6 phần tử $N$ thỏa mãn định lý. Đây là mục tiêu đầu tiên của chúng tôi.

Người thứ hai hỏi. Bước tiếp theo là hoàn thành thao tác nhân điểm trên mỗi dòng $l \in \mathbb{L}$, tức là thao tác $\times$, với hai điểm bất kỳ $a,b \in l$ xác định một số điểm $c \in l$, chúng ta sẽ gọi nó là tích của các điểm $a$ và $b$ và viết $c = a \times b$. Hãy xác định thao tác này bằng cách sử dụng... một hình vuông Latin! Giả sử rằng một hình vuông theo thứ tự Latinh $n$ là một hình vuông gồm $n \times n$ ô chứa đầy $n$ các ký hiệu khác nhau $a_1,a_2,...,a_n$ sao cho trong mỗi hàng và trong mỗi cột của hình vuông, tất cả các ký hiệu đều khác nhau. Trong các ví dụ chúng ta sẽ sử dụng số tự nhiên cùng với các ký hiệu. Chúng tôi sẽ giải thích

⟦folio 37⟧

---
running_head:
folio:
---

Tất cả các phần tử của cột $a$ đều khác nhau, chỉ một phần tử bằng $b$, số hàng của phần tử này cho chúng ta giá trị mong muốn $x$.

Một tập hợp trong đó một phép toán với đặc tính co được thực hiện được gọi là một quasigroup. Cơ sở của mỗi dòng với thao tác $\times$ là bước thứ hai của chúng tôi.

Bài tập. Hãy xem xét bài toán, tương tự như của chúng ta, cho $k$ mũ và ba nhà thông thái (người đầu tiên nhìn thấy người thứ hai và người thứ ba, và người thứ hai chỉ nhìn thấy người thứ ba). Hãy nghĩ ra cách thực hiện trực quan chiến lược của nhà thông thái trong trường hợp này. Chúng ta có thể giới hạn bản thân trong các trường hợp $k$ nhỏ, chẳng hạn như $k = 4, 5, 6$.

Sự khởi đầu thứ ba. Như chúng tôi đã mô tả trong Ví dụ 3, chiến lược của nhà thông thái - hãy ký hiệu nó bằng $S$ - là một tập hợp gồm bốn phần tử khác nhau được sắp xếp theo thứ tự của tập hợp $N$, có tính chất: với bất kỳ thứ tự nào có bốn phần tử có dạng

$(*,b,c,d), (a,*,c,d), (a,b,*,d), (a,b,c,*)$ (7)

tập hợp $S$ chứa bốn phần tử duy nhất, trong đó một số phần tử của tập hợp $N$ được viết thay vì dấu hoa thị.

Hãy lấy một đường tùy ý $l \in \mathcal{L}$. Hãy để các hiền nhân huấn luyện yêu cầu ma quỷ chơi thử bằng cách sử dụng bộ $l$ làm màu mũ. Vì bộ $l$ chứa 4, 5 hoặc 6 phần tử, tất nhiên, các nhà hiền triết có thể chơi tổng theo cách mà ba người đoán đúng (đối với bốn màu thì không có gì phải bàn cãi; cách chơi 5 màu, chúng tôi bắt buộc phải bắt đầu ở đầu phần này; và trò chơi 6 màu được dành cho người đọc là bài toán, nhưng đối với các nhà hiền triết thì đó không phải là câu đố bài toán mà là một trò chơi dễ dàng). Và nếu vậy, hãy yêu cầu các nhà thông thái ở mỗi dòng $l$ viết ra một chiến lược chiến thắng, tức là cùng một bộ bốn theo thứ tự và biểu thị nó bằng $S_l$. Bộ sưu tập các bộ $S_l$ là dự án thứ ba của chúng tôi.

Bây giờ mọi thứ đã sẵn sàng để xây dựng chiến lược của các nhà hiền triết. Đường thẳng đi qua các điểm $a$ và $b$ sẽ được ký hiệu là $l(a,b)$ (theo Định lý 2 luôn được xác định duy nhất). Hãy để nó là $S = \emptyset$ trước. ù

⟦folio 38⟧

---
running_head:
folio:
---

Chúng ta hãy liệt kê tất cả các bộ ba có thứ tự $(a,b,c)$ có thể có của các phần tử riêng biệt theo cặp của tập hợp và thêm các bộ tứ mới vào tập hợp $S$ như sau.

1) Nếu $c \notin l(a,b)$, thì chúng ta tìm thấy trên dòng $l(a,b)$ (hình 2) điểm $x = a \times b$ (tự động).

Cesky $x \neq c$), sau đó trên dòng $l(x,c)$ chúng ta tìm thấy một điểm $d$ sao cho $c \times d = x$ (nó được xác định duy nhất bởi tính chất co lại). Sau đó $d \neq c$ (nếu không thì sẽ ra $x = c \times d = c \times c = c$), và cả $d \neq x$ (nếu không từ đẳng thức $c \times x = x$ chúng ta sẽ tìm thấy $c = x$). Do đó, trong một bộ tứ điểm $(a,b,c,d)$, các điểm $a$ và $b$ nằm trên một đường thẳng, các điểm $c$ và $d$ nằm trên một đường thẳng khác, đồng thời $a \times b = c \times d = x$, trong đó $x$ là giao điểm của các đường này. Hãy thêm bốn $(a,b,c,d)$ vào tập hợp $S$.

2) Nếu $c \in l(a,b)$, thì hãy nhớ rằng các nhà hiền triết đã chuẩn bị chiến lược cho dòng $l(a,b)$, chúng ta sẽ tìm thấy phần tử duy nhất $d \in l(a,b)$ mà $(a,b,c,d) \in S_{l(a,b)}$. Trong bốn điểm này, tất cả các điểm đều nằm trên cùng một đường thẳng. Hãy thêm bốn $(a,b,c,d)$ vào tập hợp $S$.

Sau khi trải qua tất cả các bộ ba có thứ tự $(a,b,c)$, chúng ta xây dựng chiến lược cần thiết $S$.

Vẫn còn phải kiểm tra xem đây có phải là một chiến lược hợp lệ hay không. Để làm điều này, bạn cần đảm bảo rằng trong mỗi mẫu (7), bạn có thể thay thế một phần tử đơn lẻ làm dấu hoa thị để thu được bộ tứ có thứ tự nằm trong tập hợp $S$.

Đối với mẫu $(a,b,c,*)$, điều này thể hiện rõ ràng từ việc xây dựng chiến lược.

Hãy xem xét mẫu $(*,b,c,d)$ và tiến hành suy luận tương tự như 1) và 2).

1') Nếu $b \notin l(c,d)$, thì chúng ta tìm thấy trên dòng $l(c,d)$ điểm $x = c \times d$ (tự động $x \neq b$), sau đó trên dòng $l(b,x)$ chúng ta tìm thấy một điểm $a$ sao cho $a \times b = x$ (nó được xác định duy nhất bởi tính chất co bóp). Sau đó $a \neq b$ (nếu không thì sẽ ra $x = a \times b = b \times b = b$), và $a \neq x$ (nếu không từ đẳng thức $x \times b = x$ chúng ta sẽ tìm thấy $b = x$). Do đó, bộ tứ điểm theo thứ tự $(a,b,c,d)$ được xác định duy nhất, trong đó các điểm $a$ và $b$ nằm trên một đường thẳng, các điểm $c$ và $d$ nằm trên một đường thẳng khác, đồng thời $a \times b = c \times d = x$, trong đó $x$ là điểm giao nhau của các đường này. Bộ tứ như vậy có $S$ trong bộ và có chính xác một bộ - chúng tôi đã thêm nó vào $S$ từ bộ $S_{l(a,b)}$.

Như chúng ta có thể thấy, lý do cho mẫu $(*,b,c,d)$ gần như trùng khớp từng chữ với lý do từ định nghĩa của chiến lược. Hai mẫu còn lại được kiểm tra theo cách tương tự.

Cuộc thảo luận của tác giả với A. Latyshev đã hỗ trợ rất nhiều cho việc viết bài báo.

Văn học

1. K.Kokhas. Trận đấu lúc 15. – «Kvant», 2022, số 5.
2. C.J.Colbourn, I.H.Dinitz. Handbook of combinatorial design. – CRC, 2007.
3. L.Teirlinck. Generalized idempotent orthogonal arrays. – Coding theory and design theory, part II, p. 368–378. – IMA Volumes in Mathematics and its Applications, 21. – Springer, 1990.

⟦folio 40⟧

---
running_head:
folio:
---

Có nhiều lý do và trên hết, nó phụ thuộc vào chế độ dòng chảy: tầng hoặc hỗn loạn. Như vậy, đối với dòng chảy tầng trong đường ống có thành cứng có thể xác định thông qua số Reynolds Re:
$$f = \frac{64}{\text{Re}}.$$
Tuân thủ, tốc độ dòng chảy giảm:
$$v = \sqrt{\frac{2gh}{1 + \frac{fL}{D}}}.$$
Trong trường hợp của chúng tôi, thời gian thay đổi độ cao của cột chất lỏng trong bình hóa ra bằng
$$t_2 = \frac{S}{s} \sqrt{2 \frac{D + fL}{gD}} \left( \sqrt{h_1} - \sqrt{h_2} \right).$$
Phương pháp này mang lại kết quả thực tế hơn cho các tính toán kỹ thuật vì nó tính đến điện trở trong ống và ảnh hưởng của hình dạng của nó.

Độ nhớt: Hồ sơ Poiseuille
Đối với dòng chất lỏng tầng bên trong một ống hẹp (hình 3), vận tốc được phân bố dọc theo bán kính theo định luật parabol, do Poiseuille thiết lập theo kinh nghiệm:
$$v(r) = \frac{\Delta p}{4\eta L} \left( R^2 - r^2 \right).$$
Ở đây $\Delta p = \rho gh$ là độ giảm áp suất, $\eta$ là độ nhớt động của chất lỏng, $L$ là chiều dài của ống, $R$ là bán kính của nó.

Giải thích sự phân bố vận tốc trên mặt cắt ngang, chúng ta thu được tốc độ dòng thể tích của chất lỏng:
$$Q = \frac{\pi \Delta p R^4}{8\eta L}.$$
Sau khi thay thế $\Delta p = \rho gh$, phương trình thay đổi độ cao của chất lỏng theo thời gian có dạng
$$S \frac{dh}{dt} = -\frac{\pi \rho g R^4 h}{8\eta L}.$$
Từ đây
$$dt = -\frac{8\eta LS}{\pi \rho g R^4} \frac{dh}{h}.$$
Xen kẽ độ cao từ $h_1$ đến $h_2$, ta tìm được thời gian chảy ra:
$$t_3 = \frac{8\eta LS}{\pi \rho g R^4} \ln \frac{h_1}{h_2}.$$
Cách tiếp cận này mô tả chính xác nhất dòng chảy tầng chậm, đặc biệt trong trường hợp chất lỏng nhớt trong đó lực cản dòng chảy bên trong lỗ chi phối các hiệu ứng khác.

Phần kết luận
Nghiên cứu cho thấy thời gian chất lỏng chảy ra phụ thuộc rất nhiều vào mô hình mô tả được chọn. Phương trình Torricelli, đơn giản và trực quan, chỉ áp dụng cho chất lỏng lý tưởng không có độ nhớt và tổn thất năng lượng. Do tình trạng này, nó đưa ra thời gian hết hạn được đánh giá thấp.

Việc tính đến tổn thất của Darcy–Weisbach cho phép mô tả tình huống thực tế hơn, đặc biệt nếu phản ứng có độ dài và lực cản đáng chú ý. Phương pháp này rất hữu ích khi cần tiếp cận nhanh, có tính đến các yếu tố cản trở chính.

Định luật Poiseuille đưa ra bức tranh đầy đủ nhất về dòng chảy tầng, cho thấy vận tốc trên mặt cắt ngang được phân bố theo định luật parabol. Cách tiếp cận này rất quan trọng trong các vấn đề trong đó độ nhớt đóng vai trò then chốt - ví dụ như khi chất lỏng chảy chậm trong các kênh hẹp.

Kết quả là, chúng ta có thể nói rằng mỗi mô hình có phạm vi riêng và sự lựa chọn đúng đắn phụ thuộc vào mức độ chi tiết của quy trình vật lý cần được mô tả.

⟦folio 44⟧

---
running_head:
folio:
---

sự thay đổi có thể có của cường độ dòng điện bằng giá chia ampe.
20. Học sinh cần khám phá bằng thực nghiệm sự phụ thuộc của áp suất khí trong bình vào khối lượng của khí. Ông có năm chiếc bình khác nhau có đồng hồ đo áp suất và nhiệt kế. Các bình chứa đầy argon có khối lượng khác nhau ở nhiệt độ khác nhau:

| Tàu số. | Thể tích tàu, l | Nhiệt độ khí trong bình, K | Khối lượng khí trong bình, G |
| :--- | :--- | :--- | :--- |
| 1 | 6 | 320 | 10 |
| 2 | 4 | 350 | 6 |
| 3 | 6 | 320 | 8 |
| 4 | 4 | 320 | 6 |
| 5 | 5 | 300 | 10 |

Học sinh cần dùng hai phương tiện nào để tiến hành nghiên cứu này?

Phần 2

21. Hai vật thể giống hệt nhau nằm trên bề mặt trái đất nhận được vận tốc giống nhau, hướng cùng một góc nhọn α so với đường chân trời. Một vật bay tự do, còn vật kia chuyển động hướng lên trên theo một mặt phẳng nghiêng nhẵn cố định, tạo thành một góc α với đường chân trời. Cơ thể nào sẽ tăng lên tầm cao nhất? Trả lời bằng cách chỉ ra những định luật và hình mẫu nào được sử dụng để giải thích. Chúng ta cọ xát cơ thể với không khí và bỏ qua mặt phẳng nghiêng.

22. Một bình kín chứa một lượng khí lý tưởng đơn nguyên tử có khối lượng là 12 g và khối lượng mol là 0,004 kg/mol. Khi bắt đầu thí nghiệm, áp suất trong bình là 4·10⁵ Pa ở nhiệt độ 400 K. Sau khi làm lạnh khí, áp suất giảm xuống 2·10⁵ Pa. Khí tỏa ra bao nhiêu nhiệt lượng trong quá trình thí nghiệm? Các bức tường của tàu được coi là mạnh mẽ và dẫn nhiệt.

23. Một thấu kính mỏng có tiêu cự F = 20 cm cho ảnh thật sự phóng đại của một vật đặt cách thấu kính 36 cm vuông góc với trục chính của nó. Chiều cao của ảnh vật là 5 cm. Tạo ảnh của một vật qua thấu kính. Tìm độ cao của vật.

24. Một quả bóng chứa đầy glium nặng 100 kg. Tổng khối lượng của lớp vỏ kín khí của quả bóng và chiếc gondola của nó là 400 kg.

Quả bóng có thể chịu được một vật nặng 225 kg trong không khí. Do phi hành đoàn không thể tiếp cận nên 4 kg gel đã rò rỉ ra khỏi vỏ. Khối lượng hàng hóa tối thiểu phải được ném ra khỏi vỏ khinh khí cầu để khinh khí cầu ngừng rơi là bao nhiêu? Hãy coi rằng vỏ quả bóng không chống lại sự thay đổi về thể tích; không có dòng không khí theo phương thẳng đứng. Nhiệt độ và áp suất của gel bên trong quả bóng và không khí bên ngoài quả bóng lần lượt là như nhau.

25. Trong chân không, một giọt nước đứng yên có khối lượng m = 0,4 g và điện tích q = 3 nC được đặt trong một điện trường đều nằm ngang có hướng E = 1000 kV/m. Xác định vận tốc của giọt nước sau thời điểm t = 0,2 s. Tạo hình, trên đó biểu thị các lực tác dụng lên giọt nước.

26. Một hình trụ có khối lượng m = 1 kg, bán kính R = 20 cm, trên đó quấn một sợi chỉ không trọng lượng không co giãn, được đặt trên một mặt phẳng nghiêng cố định và đầu Hit được gắn vào một bức tường thẳng đứng (hình 10).

Sợi dây không trượt dọc theo hình trụ mà song song với mặt phẳng nghiêng và vuông góc với trục của hình trụ. Hệ số ma sát giữa hình trụ và mặt phẳng là μ = 0,5. Ở góc nghiêng lớn nhất của mặt phẳng so với đường chân trời α thì hình trụ ở trạng thái cân bằng? Lập sơ đồ hình biểu diễn các lực tác dụng lên hình trụ. Chứng minh khả năng áp dụng các định luật được sử dụng cho lời giải bài toán.

Ấn phẩm được biên soạn bởi M. Demidova, A. Chernochan
