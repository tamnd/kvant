---
id: 1973-7-gindikin-skolko-suschestvuet-operatsiy-nad-mnozhestvami-a18aa576
issue: kvant_1973_7
year: 1973
number: "7"
title: Có bao nhiêu thao tác tập hợp?
authors:
  - Гиндикин С. Г.
rubric: osnovnye-stati
page_first: 4
page_last: 12
page_labels: 2-10
tag: P4BN
lang: vi
source: kvant_digital
extraction: vision
content_sha256: 588a71402aecd4242d5d882cc5d76a4f18c67d6840190e428a217b4eb6897856
prompt_sha256: draft-1
translated_from: content/ru/1973/07/articles/03_gindikin-skolko-suschestvuet-operatsiy-nad-mnozhestvami-a18aa576.md
source_content_sha256: f5a05fa782bad692bb5725bd50237e1cc18f2a96dbdcadab600d0637e94adba2
translation_model: draft
translation_run: vi-draft-2026-10-31
translation_quality: draft
---

⟦folio 2⟧

S. G. Gindikin
Có bao nhiêu thao tác tập hợp?

Các bộ có thể không chỉ bao gồm các con số mà còn có thể bao gồm con người, ô tô, động vật, thực vật, v.v. Trong cuộc sống, các bộ thường được gọi bằng những tên khác nhau. Vì vậy, ví dụ, không phải nói nhiều con bò mà là một trăm con bò, không phải nhiều con ngựa mà là một đàn ngựa, không phải nhiều công cụ mà là một bộ công cụ, v.v.

Những từ này được lấy từ sách giáo khoa toán lớp 4. Bạn có thể biết rằng bạn có thể thực hiện các phép toán hợp và giao trên các tập hợp, đôi khi được gọi là phép cộng và phép nhân của một tập hợp. Bạn đã bao giờ nghe nói về bất kỳ hoạt động thiết lập nào khác chưa? Có thể bạn biết sự khác biệt của một tập hợp hoặc sự khác biệt đối xứng của chúng là gì? Có bao nhiêu phép toán trên tập hợp? Số lượng của chúng là hữu hạn hay vô hạn? Để trả lời những câu hỏi này, trước hết chúng ta cần hiểu thế nào là phép toán trên tập hợp? Chúng tôi đưa ra định nghĩa chung về các hoạt động như vậy và nói về một số tính chất thú vị của chúng. Những nội dung khó hơn sẽ được trao đổi trong bài viết, gõ chữ nhỏ (phần này có thể bỏ qua khi đọc lần đầu).

1. Liên minh và ngã tư
Hãy nhớ rằng hợp $A \cup B$ của tập hợp $A, B$ bao gồm các phần tử có trong ít nhất một trong các tập hợp $A, B$ và phần giao $A \cap B$ bao gồm các phần tử có trong cả hai tập hợp này. Sự hình thành của sự thống nhất và giao nhau hoặc được xây dựng trong Hình 1, trong đó các “vòng tròn” tượng trưng cho các tập hợp mà thao tác sẽ được thực hiện và vùng bóng mờ tương ứng với tập hợp thu được do thao tác. Đáng chú ý là các tập hợp có thể có tính chất đa dạng nhất nhưng những sơ đồ này rất thuận tiện cho việc nghiên cứu các thao tác trên chúng.

Cả hai hoạt động đang được xem xét đều có hai thuộc tính sau:
$A \cup B = B \cup A; \ A \cap B = B \cap A$ (giao hoán),
$A \cup (B \cup C) = (A \cup B) \cup C;$
$A \cap (B \cap C) = (A \cap B) \cap C$ (tính kết hợp).

Tính giao hoán phụ thuộc rất nhiều vào các định nghĩa (xem Hình 1). Hình 2 sẽ giúp bạn chứng minh tính kết hợp. Vị trí của dấu ngoặc đơn quyết định thứ tự thực hiện các thao tác. Hình vẽ gợi ý rằng bất kỳ thứ tự nào ở trên mà các hoạt động gỡ lỗi được thực hiện, kết quả sẽ là một tập hợp bao gồm

⟦folio 3⟧

Các phần tử có trong ít nhất một trong các bộ của chúng tôi. Tương tự, trong trường hợp giao nhau, một tập hợp thu được bao gồm các phần tử có trong mỗi tập hợp của chúng ta. Chúng tôi khuyên người đọc nên suy luận cẩn thận và chúng tôi không loại trừ rằng sẽ không quá dễ dàng để chuyển thành từ những gì rất / không từ các bức vẽ.

Ví dụ: tính kết hợp cho phép, trong trường hợp hợp nhất khi thực hiện một thao tác trên các tập hợp $A_1, \dots, A_n$ nhiều lần, không cố định thứ tự thực hiện các phép toán bằng dấu ngoặc đơn và chỉ nói đơn giản về hợp nhất $n$ của tập hợp $A_1 \cup A_2 \cup \dots \cup A_n$; bộ này bao gồm các phần tử chứa $A_1, \dots, A_n$ trong ít nhất một trong bộ. Luật giao hoán cho thấy thứ tự $A_1, A_2, \dots, A_n$ có thể thay đổi theo ý muốn.

Trong trường hợp số, phép cộng và phép nhân được kết nối với nhau bằng mối quan hệ sau: $a (b + c) = ab + ac$ (phân phối của phép nhân so với phép cộng). Mối quan hệ này cho phép bạn trừ hệ số chung ra khỏi ngoặc và mở ngoặc. Đối với một tập hợp các mối quan hệ như vậy có hai:

$$A \cap (B \cup C) = (A \cap B) \cup (A \cap C);$$
$$A \cup (B \cap C) = (A \cup B) \cap (A \cup C).$$

Hình 3 thể hiện các sơ đồ minh họa các mối quan hệ này. Ví dụ, để chứng minh tập đầu tiên trong số đó, chỉ cần lưu ý rằng tập hợp đứng ở cả bên phải và bên trái bao gồm các phần tử có trong tập hợp $A$ và ít nhất một trong các tập hợp $B$ hoặc $C$. Lưu ý rằng trong một số trường hợp, mối quan hệ thứ hai sẽ có dạng $a + bc = (a + b) (a + c)$, tất nhiên là không đúng.

Mối quan hệ đầu tiên (2) cho thấy rằng bất kỳ chuỗi hợp và giao nào cũng có thể được chuyển đổi thành một chuỗi các thao tác sao cho trước tiên tất cả các giao đều được thực hiện, sau đó là hợp. Ví dụ: hãy đảm bảo rằng $(A \cup B) \cap ((C \cap D) \cup E)$ có thể được chuyển đổi thành $(A \cap C \cap D) \cup (A \cap E) \cup (B \cap C \cap D) \cup (B \cap E)$. Bạn cũng có thể thực hiện theo cách mà tất cả các phép nối sẽ được thực hiện trước (sử dụng mối quan hệ thứ hai). Hãy suy nghĩ thông qua các phép biến đổi tương tự trong trường hợp số.

2. Sự khác biệt và sự khác biệt đối xứng

Hiệu $A \setminus B$ của các tập hợp $A$ và $B$ được gọi là tập hợp bao gồm các phần tử $A$ không có trong $B$ (Hình 4). Sự khác biệt không phải là sự khác biệt đối xứng. Ví dụ, để chứng minh tập đầu tiên trong số đó, chỉ cần lưu ý rằng tập hợp đứng ở cả bên phải và bên trái bao gồm các phần tử có trong tập hợp $A$ và ít nhất một trong các tập hợp $B$ hoặc $C$. Lưu ý rằng trong một số trường hợp, mối quan hệ thứ hai sẽ có dạng $a + bc = (a + b) (a + c)$, tất nhiên là không đúng.

Mối quan hệ đầu tiên (2) cho thấy rằng bất kỳ chuỗi hợp và giao nào cũng có thể được chuyển đổi thành một chuỗi các phép toán sao cho trước tiên tất cả các giao đều được thực hiện, sau đó là hợp. Ví dụ: hãy đảm bảo rằng $(A \cup B) \cap ((C \cap D) \cup E)$ có thể được chuyển đổi thành $(A \cap C \cap D) \cup (A \cap E) \cup (B \cap C \cap D) \cup (B \cap E)$. Bạn cũng có thể thực hiện theo cách mà tất cả các giao điểm sẽ được thực hiện trước (sử dụng mối quan hệ thứ hai). Hãy suy nghĩ thông qua các phép biến đổi tương tự trong trường hợp số.

⟦folio 4⟧

Nó không phải là một phép toán giao hoán hay kết hợp. Hình 5 sẽ giúp bạn chứng minh điều này. Cũng lưu ý rằng hiệu không phải là phép toán nghịch đảo của phép hợp (mà, như chúng ta đã nói, đôi khi được gọi là phép cộng của một tập hợp). Bạn sẽ bị thuyết phục về điều này bằng cách chứng minh mối quan hệ sau:

$$(A \setminus B) \cup B = A \cup B;$$
$$(A \setminus B) \cup (A \cap B) = A.$$

Hiệu đối xứng $A \triangle B$ tập $A$ và $B$ bao gồm các phần tử được bao gồm trong một và chỉ một trong các tập hợp $A$ và $B$ (Hình 6): $A \triangle B = (A \setminus B) \cup (B \setminus A)$. Sự khác biệt đối xứng là một hoạt động giao hoán và kết hợp. Chứng minh điều này bằng Hình 7. Đối với hiệu và giao đối xứng, quan hệ phân phối có giá trị:

$$A \cap (B \triangle C) = (A \cap B) \triangle (A \cap C)$$
(xem Hình 8). Tuy nhiên, $A \triangle (B \cap C)$ có thể không giống với $(A \triangle B) \cap (A \triangle C)$ (xem Hình 9). Tình hình là số phân tích. Có những lý do sâu xa cho điều này, như chúng ta sẽ thấy.

3. Bộ phổ quát và bộ bổ sung

Sau đây chúng ta sẽ đề xuất rằng tất cả các tập đang được xem xét là tập con của một tập cố định nào đó. Chúng ta sẽ gọi nó là hình ảnh phổ quát. Ví dụ, nếu xét các tập hợp điểm trên mặt phẳng thì tập hợp tất cả các điểm trên mặt phẳng là tập hợp phổ quát; Nếu xét các tập hợp số tự nhiên thì tập hợp các số tự nhiên có tính phổ quát.

Nếu tập phổ quát cố định là $I$, thì chúng ta có thể nói về một tập $\bar{A}$ bổ sung $A$ (tối đa $I$): $\bar{A} = I \setminus A$, nghĩa là, $\bar{A}$ bao gồm các phần tử $I$ không có trong $A$

⟦folio 5⟧

(xem hình 10). Bộ phổ quát bổ sung trống: $\bar{I} = 0$ (bộ trống).

Thao tác bổ sung cho phép bạn liên kết các thao tác hợp và giao cắt như sau:

$$\bar{A} \cup \bar{B} = \bar{A} \cap \bar{B}.$$

Thật vậy, $\bar{A} \cap \bar{B}$ bao gồm các phần tử có trong $\bar{A}$ và $\bar{B}$, nghĩa là không được bao gồm trong $\bar{A}$ hoặc $\bar{B}$, hoặc, giống nhau, không được bao gồm trong liên minh $\bar{A} \cup \bar{B}$, tức là điều được khẳng định. Từ những thư từ thu được, rằng

$$\bar{A} \cup \bar{B} = \bar{A} \cap \bar{B}, \quad \bar{A} \cap \bar{B} = \bar{A} \cup \bar{B}.$$

(3)

Để có được sự tương ứng đầu tiên trong số này, chỉ cần thay thế rằng sự trùng khớp của các tập hợp hàm ý sự trùng khớp của phần bù của chúng và rằng $\bar{C} = C$ (phần bù của sẽ trùng khớp với tập hợp ban đầu). Để có được số thứ hai, cần phải tính đến rằng vì $\bar{A} \cup \bar{B} = \bar{A} \cap \bar{B}$ dành cho bất kỳ $A$ và $B$ nào, nên chúng ta có thể lấy $\bar{A}, \bar{B}$: $\bar{A} \cup \bar{B} = \bar{A} \cap \bar{B} = \bar{A} \cap \bar{B}$ làm các tập hợp này. Sự tương ứng (3) được gọi là định luật De Morgan. Họ chứng tỏ rằng sự hợp nhất có thể được biểu diễn dưới dạng giao và phần bù, và sự giao nhau có thể được biểu diễn dưới dạng hợp và phần bù.

Lưu ý rằng $A \setminus B = A \cap \bar{B}$, có nghĩa là $A \triangle B = (A \cap \bar{B}) \cup (\bar{A} \cap \bar{B})$.

4. Luật nhị nguyên

Việc nghiên cứu các phép toán trên tập hợp bao gồm việc thu thập các điểm khác nhau kết nối các phép toán. Chúng tôi muốn nói đến các tuyên bố thuộc loại sau. Một số chuỗi thao tác được thực hiện trên tập hợp $A_1, \dots, A_n$ theo hai cách và người ta tuyên bố rằng những kết hợp thao tác này luôn (đối với bất kỳ $A_1, \dots, A_n$) nào dẫn đến sự trùng khớp của các tập hợp. Tất cả các định luật (1), (2), (3) cũng có điểm giống nhau. Điều quan trọng là có thể có được những cái mới từ các điểm hiện có. Ví dụ: chúng ta thực sự đã sử dụng thực tế là nếu trong một điểm, chúng ta thay thế $A_1, \dots, A_n$ bằng $\bar{A}_1, \dots, \bar{A}_n$ hoặc chuyển đến phần bù ở cả hai phần của điểm, chúng ta cũng sẽ nhận được dấu chấm.

Bây giờ chúng ta sẽ chỉ ra một cách rất quan trọng để biến đổi các điểm chứa các phép toán hợp, giao và phép cộng (và chỉ các phép toán này).

Luật nhị nguyên. Nếu tại một điểm chỉ chứa các phép toán hợp, giao và cộng, chúng ta thay thế tất cả các giao bằng hợp và tất cả các hợp bằng giao, thì chúng ta lại thu được điểm.

Kiểm tra xem theo cách này, từ tính giao hoán và tính kết hợp của phép hợp, chúng ta thu được tính giao hoán và tính kết hợp của giao và ngược lại, và từ một tương ứng phân phối (2) - một tương ứng khác.

Chúng tôi sẽ không đưa ra bằng chứng cho tuyên bố này ở đây mà sẽ đưa ra một ví dụ về cách có thể đạt được nó.

Hãy xem xét các điểm

$$A_1 \cap ((A_2 \cup \bar{A}_3) \cap (\bar{A}_4 \cap A_5)) = A_1 \cap (\bar{A}_2 \cap A_3) \cup (\bar{A}_4 \cap A_5),$$

thật dễ dàng để kiểm tra, sử dụng định luật De Morgan. Chúng ta hãy đi đến điểm bổ sung ở cả hai phần và thay thế tất cả $A_1, \dots, A_5$ bằng $\bar{A}_1, \dots, \bar{A}_5$:

$$\bar{A}_1 \cap ((\bar{A}_2 \cup A_3) \cap (\bar{A}_4 \cap A_5)) = \bar{A}_1 \cap (\bar{A}_2 \cap \bar{A}_3) \cup (\bar{A}_4 \cap \bar{A}_5).$$

Bây giờ chúng ta thay thế tất cả các phép toán hợp và giao bằng (3). Nếu chúng ta đơn giản hóa các điểm kết quả, chúng ta sử dụng thực tế là hai dòng nằm trên một biểu thức

⟦folio 6⟧

Chúng ta có thể phá hủy nó, sau đó chúng ta có được danh tính mong muốn:

$$A_1 \cup ((A_2 \cap A_3) \cup (A_4 \cap A_5)) = A_1 \cup (A_2 \cup A_3) \cap (A_4 \cup A_5).$$

Một bằng chứng nghiêm ngặt được thực hiện từ các tin nhắn tương tự.

5. Một hoạt động thiết lập là gì?

Hãy thử tự mình chấm đáp số cho câu hỏi này, sau đó so sánh kết luận của bạn với những gì được nêu dưới đây.

Việc chỉ định một thao tác trên một tập hợp trước hết có nghĩa là chỉ ra cách xây dựng tập hợp thứ ba từ hai tập hợp đã cho $A$ và $B$; hãy biểu thị nó bằng $A \bigcirc B^*$). Nếu chúng ta vẫn giữ nguyên định nghĩa tại thời điểm này, chúng ta sẽ nhận được một số lượng lớn các phép toán. Nhưng có lẽ bạn có thể nhận thấy rằng trong tất cả các thao tác mà chúng tôi đã trình bày, câu hỏi liệu có phần tử nào được đưa vào $A \bigcirc B$ hoàn toàn được quyết định chỉ dựa trên bộ nào trong số các bộ $A$, $B$ nó được đưa vào và bộ nào không. Hãy đưa yêu cầu này vào định nghĩa của hoạt động. Hãy để chúng tôi xây dựng nó chi tiết hơn.

Nếu cho hai bộ $A$ và $B$ thì tập phổ quát $I$ được chia thành bốn tập con rời rạc: tập $A \cap B$, bao gồm các phần tử có trong các tập chung $A$ và $B$; bộ $\overline{A} \cap \overline{B}$, bao gồm các phần tử không có trong bất kỳ bộ nào trong số này; tập hợp $\overline{A} \cap B$, bao gồm các phần tử có trong $B$, nhưng không có trong $A$ và tập hợp $\overline{A} \cap \overline{B}$, bao gồm các phần tử có trong $A$, nhưng không có trong $B$. Chúng ta sẽ gọi những tập hợp này là những tập hợp đơn. Yêu cầu bổ sung của chúng tôi đối với hoạt động là nếu hai phần tử nằm trong cùng một dolbe thì chúng được bao gồm

*) Tất nhiên, $A \bigcirc B$, như $A$ và $B$ phải có trong tập phổ quát $I$.

Cơm. 11.

trong $A \bigcirc B$, hoặc nó không được bao gồm. Nói cách khác, $A \bigcirc B$ là sự kết hợp của một số lát cắt nhất định. Việc chia hàng hóa thành các phần được minh họa bằng sơ đồ mà chúng tôi đã vẽ (trong Hình 11, các khu vực tương ứng được tô màu khác nhau); đây là lý do tại sao sơ ​​đồ lại hữu ích trong hoạt động học tập.

6. Có bao nhiêu phép toán trên một cặp tập hợp?

Bây giờ chúng ta có thể dễ dàng trả lời câu hỏi này. Có nhiều thao tác khác nhau cũng như có nhiều cách khác nhau để chọn các phân đoạn tạo nên $A \bigcirc B$. Có 4 đoạn và có 16 cách tạo thành $A \bigcirc B$ khác nhau. Có cùng số lượng các tập hợp con khác nhau trong một tập hợp gồm 4 phần tử (tính cả tập hợp rỗng và toàn bộ). Những phép tính này có thể được thực hiện trực tiếp hoặc bạn có thể sử dụng bổ đề tổ hợp sau đây, bổ đề này sẽ hữu ích cho chúng ta sau này.

Bổ đề. Một tập hợp các phần tử $n$ có $2^n$ các tập hợp con khác nhau.

Bằng chứng. Đặt $N$ là một tập hợp như vậy. Hãy đánh số các phần tử của nó bằng cách nào đó. Chúng ta hãy gán cho mỗi tập hợp con $M$ trong $N$ một tập hợp các số 0 và các số một có độ dài $n$, và ở vị trí $k$, chúng ta đặt 1 nếu phần tử $k$ của tập hợp $N$ được bao gồm trong $M$ và 0 nếu ngược lại. Những bộ như vậy được gọi là bộ đôi. Giữa những cái tên

⟦folio 7⟧

Cử chỉ ở $N$ và bộ đôi độ dài $n$ tạo ra sự tương ứng một-một. Trong trường hợp này, một tập hợp chỉ các số 0 tương ứng với một tập hợp trống và một tập hợp chỉ các số 0 tương ứng với tất cả các bộ $N$. Vậy số lượng tập hợp con trong $N$ bằng số lượng các tập hợp đôi có độ dài $n$. Chúng ta hãy chứng minh bằng quy nạp rằng số $f(n)$ này bằng $2^n$. Tại $n = 1$ điều này là hiển nhiên; hãy $f(n - 1) = 2^{n-1}$. Mỗi bộ độ dài $n$ thu được từ một bộ độ dài $n - 1$ bằng cách thêm 0 hoặc 1, nghĩa là từ mỗi bộ độ dài $n - 1$ thu được hai bộ độ dài $n$ và do đó $f(n) = 2f(n - 1) = 2^n$.

Đặt $n = 4$, chúng ta nhận được rằng có 16 tập hợp con trong tập hợp 4 phần tử và do đó có 16 thao tác trên hai tập hợp. Các thao tác này bao gồm các thao tác $A \bigcirc B = 0$ (tập trống) cho bất kỳ $A$ và $B$ nào ($A \bigcirc B$ không chứa bất kỳ lát cắt nào) và $A \bigcirc B = I$ cho bất kỳ $A$ và $B$ nào ($A \bigcirc B$ là sự kết hợp của tất cả các lát cắt). Chúng ta sẽ ký hiệu các hoạt động này lần lượt là 0 và 1. Các phép toán cũng bao gồm $A \bigcirc B = A$, $A \bigcirc B = B$, $A \bigcirc B = \overline{A}$, $A \bigcirc B = \overline{B}$, vì trong cả bốn bộ ngẫu nhiên, bộ bên phải là sự kết hợp của hai lát cắt (ví dụ: $\overline{A} = (\overline{A} \cap B) \cup (\overline{A} \cap \overline{B})$). Hãy liệt kê các hoạt động còn lại:
$A \bigcup B$, $A \cap B$, $A \setminus B$, $B \setminus A$, $A \triangle B$, $A \cup B$, $A \cap B$, $A \setminus B$, $B \setminus A$, $A \triangle B$.

Lưu ý rằng các hoạt động bao gồm việc hình thành các tiểu thùy *). Từ thực tế là mọi phép toán đều là hợp của các phân đoạn, nên mọi phép toán đều có thể được biểu diễn dưới dạng hợp, giao và cộng.

*) Để biểu thị các thao tác mà chúng ta gọi một cách phù phiếm là “phân vùng thành các lát”, có một thuật ngữ hoàn toàn nghiêm túc “dạng phân biệt hoàn hảo” và các lát cắt được gọi là “các liên kết cơ bản chính quy hoàn chỉnh”.

Cơm. 12.

Hãy để chúng tôi chỉ ra một cách thể hiện khác của các hoạt động thông qua ba điều này. Hãy gọi phép cộng vào lát cắt là phần phụ. Theo (3), trọng số bổ sung tương ứng với các phép toán $\overline{A} \cup \overline{B}$, $A \cup B$, $A \cup \overline{B}$, $\overline{A} \cup B$. (Điều này cũng dễ dàng xác minh bằng bản vẽ). Bằng cách chỉ định thao tác $A \bigcirc B$, ngoài việc liệt kê những phân đoạn nào được bao gồm trong $A \bigcirc B$, có thể chỉ ra những phân đoạn nào không được bao gồm trong đó và khi đó $A \bigcirc B$ sẽ là giao điểm của các trọng số tương ứng với các phân đoạn này. Ví dụ: $\overline{A} \cap B = (A \cup B) \cap (\overline{A} \cup \overline{B}) \cap (\overline{A} \cup B)$ hãy tự mình xem các ví dụ khác. Việc biểu diễn các phép toán dưới dạng giao điểm của các trọng số *) có thể thu được từ việc biểu diễn dưới dạng kết hợp các lát cắt bằng cách sử dụng luật đối ngẫu (hãy làm đi!).

7. Bảng nhị phân cho các hoạt động
Chúng ta hãy gán cho mỗi lát một bộ đôi gồm hai phần tử: $A \cap B => (1, 1)$, $\overline{A} \cap \overline{B} => (0, 0)$, $\overline{A} \cup B => (0, 1)$, $A \cup \overline{B} => (1, 0)$. Ở đây 1 chỉ ra rằng phân đoạn được bao gồm trong tập tương ứng ($A$ hoặc $B$) và 0 chỉ ra rằng phân đoạn đó không được bao gồm và do đó, được bao gồm trong phần bù (xem Hình 12). Khi chỉ định thao tác $A \bigcirc B$, chúng ta gán 1 cho mỗi lát được mã hóa bởi tập hợp đó, nếu lát này

*) Và có một tên tiếng Serbia cho cách thể hiện này; "dạng liên hợp chuẩn hoàn hảo".

⟦folio 8⟧

được bao gồm trong $A \bigcirc B$ và 0 nếu không. Tất cả điều này có thể được viết dưới dạng một bảng trong đó các hàng sẽ tương ứng với các lát và dòng, ví dụ: 1,0|0 phải được coi là mục nhập được mã hóa của cụm từ: nếu một phần tử được bao gồm trong tập đầu tiên ($A$) và không được bao gồm trong tập thứ hai ($B$), thì nó không được bao gồm trong $A \bigcirc B$. Một bảng như vậy được gọi là bảng thao tác kép hoặc bảng Boolean và nó chỉ định đầy đủ thao tác. Trên đây là bảng kép tóm tắt tất cả các thao tác trên một cặp tập hợp.

Hãy chú ý đến các cột trong bảng tương ứng với $A \cap B$, $A \triangle B$ và $\bar{A}$. Nếu $(x, y)$ là một tập hợp tương ứng với một lát, thì trong cột của $A \cap B$ chỉ có $xy$, trong cột của $A \triangle B$ có phần dư của phép chia $x + y$ cho 2 và trong cột của $\bar{A}$ có phần dư của phép chia $x + 1$ cho 2. Các thao tác này được thực hiện trên các phần tử $x, y = 0,1$ được gọi là các phép toán số học modulo 2, và đối với chúng, tất cả các định luật cơ bản của phép tính số học tổng quát đều được bảo toàn (tính giao hoán, tính kết hợp, tính phân phối của phép nhân so với phép cộng) *). Thực tế này cho phép chúng ta thay thế các tính chất của sai phân đối xứng.

*) Bạn có thể đọc về các phép toán dựa trên mô hình (phép tính số dư) trên tạp chí «Kvant» số 5, 1970.

8. Hoạt động trên bộ $n$

Trên thực tế, chúng ta đã xử lý các phép toán như vậy nhưng chúng luôn được thể hiện thông qua các phép toán trên các cặp tập hợp. Bây giờ chúng tôi đưa ra một định nghĩa chung. Để chỉ định một thao tác trên tập hợp $n$ có nghĩa là chỉ định luật xây dựng cho một tập hợp gồm bất kỳ tập hợp $n$ $A_1, \dots, A_n$ nào của tập hợp được xác định duy nhất $f(A_1, \dots, A_n)$ và câu hỏi về việc đưa một số phần tử vào $f(A_1, \dots, A_n)$ hoàn toàn được xác định bởi phần tử nào trong tập hợp $A_1, \dots, A_n$ phần tử này được bao gồm trong và phần tử nào không có. Hãy đặt $A^\sigma = A$ tại $\sigma = 1$ và $A^\sigma = \bar{A}$ tại $\sigma = 0$. Lưu ý rằng tập hợp $A_1^{\sigma_1} \cap A_2^{\sigma_2} \cap \dots \cap A_n^{\sigma_n}$ bao gồm tất cả các phần tử có trong $A_j$ nếu $\sigma_j = 1$ và không có trong $A_j$ nếu $\sigma_j = 0$. Hoạt động $A_1^{\sigma_1} \cap A_2^{\sigma_2} \cap \dots \cap A_n^{\sigma_n}$, giống như $n = 2$, sẽ được gọi là một lát tương ứng với tập hợp $(\sigma_1, \sigma_2, \dots, \sigma_n)$. Có bao nhiêu lát cắt thì có hai bộ chiều dài $n$, tức là (theo Bổ đề) $2^n$. Trong Hình 13, bạn thấy sự phân tách ở $n = 3$.

Từ định nghĩa của thao tác, mỗi thao tác $f(A_1, \dots, A_n)$ là một luồng xung quanh một số lát nhất định. Để gán một thao tác cho mỗi lát, được mã hóa thành hai

⟦folio 9⟧

Cơm. 13.

đặt σ, chúng ta đặt nó tương ứng với 1 hoặc 0, tùy thuộc vào việc phần này có được đưa vào $f(A_1, \dots, A_n)$ hay không. Kết quả của thao tác là một tập hợp có độ dài gấp đôi $2^n$ (tức là có bao nhiêu lát), nghĩa là có $2^{(2n)}$ các thao tác khác nhau trên các tập hợp. Vì trong mọi trường hợp $f(A_1, \dots, A_n)$ là hợp của các phân đoạn, nên chúng ta đồng thời thu được rằng mỗi phép toán được thể hiện thông qua hợp, giao và phần bù. Chúng ta có một ý tưởng khác nếu xem xét hai và ba thao tác trên các bộ phận, chúng có dạng $A_1^{\sigma_1} \cup \dots \cup A_n^{\sigma_n}$. Bất kỳ hoạt động nào cũng có thể được biểu diễn dưới dạng giao điểm của trọng lượng bổ sung.

Vì vậy, hóa ra, thứ nhất, có một số hữu hạn các phép toán trên các tập hợp $n$, và thứ hai, tất cả các phép toán này có thể được biểu diễn dưới dạng các phép toán trên các cặp tập hợp - hợp, giao và phần bù $^*$). Điều này giải thích rằng trong nhiều câu hỏi của lý thuyết tập hợp, chúng ta bị giới hạn trong việc xem xét ba phép toán này. Tuy nhiên, xét đến (3), chúng ta có thể giới hạn ở hai phép toán: hợp và bổ sung hoặc giao và bổ sung.

Có những khả năng khác để chọn các thao tác cơ bản mà qua đó tất cả các thao tác khác được thể hiện. Ví dụ, hãy xem xét phép toán $A \cap B$. Nếu bạn lấy

*) Xem xét bổ sung như một thao tác trên một bộ ($n=1$).

vì $A$ và $B$ cùng một bộ $C$, thì chúng ta nhận được $\overline{C}$. Bằng cách thực hiện hai thao tác này theo trình tự, chúng ta nhận được $A \cap B$. Nhưng bất kỳ hoạt động nào cũng có thể được biểu diễn thông qua phép giao và phần bù. Điều này có nghĩa là bất kỳ thao tác nào cũng có thể được biểu diễn thông qua một thao tác duy nhất $\overline{A \cap B}$. Kiểm tra xem tất cả các thao tác cũng có thể được thể hiện thông qua thao tác $A \cup B$. Hai hoạt động đáng chú ý này được gọi là hoạt động Schaefer. Chứng minh rằng $\overline{A} \cup B$, $\overline{C}$ hoặc $\overline{A} \cup B$, 0 có thể chọn làm hệ các phép toán cơ bản.

9. Những thao tác đơn điệu

Liệu tất cả các hoạt động có thể được thể hiện thông qua các công đoàn và giao lộ mà không cần dùng đến các hoạt động bổ sung không? Hóa ra là không. Để xác minh điều này, bạn cần tìm một số thuộc tính mà tất cả các phép toán được biểu diễn thông qua hợp và giao đều có, nhưng có những phép toán không có thuộc tính này. Như chúng tôi đã lưu ý ở điểm 1 khi thảo luận về sự tương ứng (2), luôn có thể thay đổi thứ tự hợp và giao để thực hiện giao trước, sau đó mới đến hợp. Khả năng biểu diễn như vậy được áp dụng cho mục đích định nghĩa trên tập hợp các lát cắt trong đó $f(A_1, \dots, A_n)$ có thể bao gồm nếu $f(A_1, \dots, A_n)$ được biểu thị thông qua các phép hợp và giao. Tập hợp các phân đoạn này phải được sắp xếp như sau: có các tập hợp con $M_1, \dots, M_k$ trong tập hợp $N = \{1, 2, \dots, n\}$ và một phân đoạn thay thế $\sigma = (\sigma_1, \dots, \sigma_n)$ được bao gồm trong $f(A_1, \dots, A_n)$ khi và chỉ khi $\sigma_j = 1$ cho tất cả $j \in M_1$ hoặc $\sigma_j = 1$ cho tất cả $j \in M_2$, v.v. Ví dụ: trong trường hợp $(A_1 \cap A_3 \cap \bigcap A_5) \cup A_4 \cup (A_2 \cap A_5)$ chúng ta có: $M_1 = \{1, 3, 5\}, M_2 = \{4\}, M_3 = \{2, 5\}$. Không khó để nhận thấy rằng các tập hợp các tập hợp như vậy có đặc điểm là cùng với mỗi tập hợp $\sigma$, chúng chứa tất cả các tập hợp $\sigma'$, trong đó tất cả những vị trí trong đó $\sigma$ chứa các tập hợp cũng có các tập hợp đó (chúng ta sẽ ký hiệu một cách tượng trưng điều này như sau: $\sigma' \geq \sigma$). Bây giờ, rõ ràng là, ví dụ, phép toán $A \setminus B = A \cap B$ không có thuộc tính này: nó trùng với phần duy nhất tương ứng với tập hợp (1, 0) và $(1, 1) \geq (1, 0)$ tương ứng với phần không có trong $A \setminus B$. Các phép toán được biểu diễn thông qua hợp và giao, cũng như 0, 1, sẽ được gọi là đa quan hệ. Rõ ràng, phần bù cũng là một phép toán hơi thập phân: đếm $n = 1$, chúng ta thấy rằng $A$ trùng với phân số của $\sigma = (0) \leq \sigma' = (1)$.

⟦folio 10⟧

10. Hoạt động tuyến tính

Mọi thao tác có thể được biểu diễn dưới dạng $A \cap B, A \triangle B, I$. Thật vậy, $\overline{A} = A \triangle I$, $A \cup B = (A \cap B) \triangle (A \triangle B)$, và trong phần 8 chúng ta đã chứng minh rằng mọi phép toán đều được biểu diễn thông qua phép giao và phần bù. Chúng ta hãy khám phá thực tế này từ quan điểm giải thích số học của các phép toán. Đặt $f(A_1, \dots, A_n)$ là một phép toán tùy ý; Hãy nhìn vào bảng nhị phân của nó (xem đoạn 7). Chúng ta hãy biểu thị bằng $\tilde{f}(x_1, \dots, x_n)$ giá trị trong bảng này tương ứng với tập nhị phân $(x_1, \dots, x_n)$.

Nếu chúng ta biểu thị $f$ theo $A \cap B, A \triangle B, I$, thì đối với $f$, một biểu thức sẽ xuất hiện thông qua các phép toán số học modulo 2. Bằng cách mở dấu ngoặc và đưa các số hạng tương tự, chúng ta thu được biểu diễn cho $\tilde{f}$ dưới dạng đa thức trong $x_1, \dots, x_n$. Xét rằng $x_j$ lấy các giá trị 0, 1 và kết quả là chỉ lấy phần còn lại của việc chia giá trị của đa thức cho 2, chúng ta có thể đơn giản hóa rất nhiều dạng của đa thức. Thứ nhất, chúng ta có thể giả sử rằng tất cả các hệ số khác 0 đều bằng 1 (2x chia cho 2) và thứ hai, các biến $x_j$ sẽ xuất hiện dưới dạng đơn thức không cao hơn lũy thừa thứ nhất $(x^2 = x$ của $x = 0, 1)$.

Bây giờ chúng ta hãy xem xét các hoạt động thuộc loại này: $f(A_1, A_2, \dots, A_n) = A_1 \triangle A_2 \triangle \dots \triangle A_n$. (Trong bản ghi, chúng tôi đã sử dụng giao hoán và kết hợp $A \triangle B$; xem đoạn 2.) Tập kết quả bao gồm các phần tử được bao gồm trong số lẻ của tập hợp $A_1, \dots, A_n$, và sau đó chúng tôi sẽ gọi các phép toán này là các số lẻ kỳ quặc. Thật dễ dàng để xác minh trực tiếp tuyên bố này (đối với $n = 2, 3$, xem Hình 6, 7) và người ta có thể nhận thấy rằng trong trường hợp này $\tilde{f}(x_1, \dots, x_n) = x_1 + \dots + x_n$ modulo 2. Điều này cho thấy, ví dụ, giao điểm $A \cap B$ không thể được biểu thị thông qua hiệu đối xứng, vì $A \cap B$ bao gồm các phần tử rơi vào hai tập hợp. Nếu thêm thao tác 1, chúng ta sẽ nhận được nhiều chỉ báo chẵn lẻ hơn $A_1 \triangle \dots \triangle A_n \triangle I$; chúng sẽ được gán các đa thức bậc nhất $x_1 + \dots + x_n + 1$. Một lần nữa, chúng ta sẽ không thể biểu thị giao điểm vì các phần tử không có trong $A$ hoặc $B$ đều không có trong $A \cap B$. Chúng ta sẽ gọi các phép toán được thể hiện thông qua $A \triangle B$ và $I$ (nghĩa là các chỉ báo chẵn và lẻ) là các phép toán tuyến tính và các phép toán còn lại - phi tuyến tính. Các thuật ngữ này được liên kết với các đa thức tương ứng với các phép toán này.

11. Mô tả hệ thống vận hành cơ bản

Bằng một hệ thống các thao tác cơ bản, chúng ta hiểu hệ thống các thao tác đó mà tất cả các thao tác khác đều được thể hiện thông qua chúng.

Chúng ta đã có một số ví dụ về hệ thống vận hành cơ bản. Hơn nữa, trong hai đoạn trước, chúng ta đã chứng minh rằng các tập $\{A \cap B, A \cup B\}$, $\{A \triangle B, I\}$ không thể được coi là hệ các phép toán cơ bản. Đồng thời, chúng tôi đã có được những điều kiện cần thiết cho hệ thống đó; chúng nhất thiết phải chứa các hoạt động chưa hoàn thành và thần kinh. Điều đáng chú ý là điều kiện cần và đủ được đưa ra theo cùng một điều kiện. Chúng tôi sẽ không làm điều này trong hệ thống chung nhất. Chúng ta sẽ nói rằng giả định 01 được thỏa mãn đối với một hệ điều hành nếu hệ thống này chứa 0 và 1.

Định lý bài. Hệ các phép toán thỏa mãn Giả thiết 01 có thể được coi là hệ các phép toán cơ bản của mô hình và chỉ là mô hình khi nó chứa các phép toán neotonic và neotonic.

Có một công thức chung của định lý Post cho mọi hệ thống (không có giả định 01); Hơn nữa, số điều kiện của định lý, nếu không có giả định 01 thì chúng phải nằm trong đoạn 9, 10. Rõ ràng, chúng được bảo toàn ngay cả trong điều kiện 01, vì 0 và 1 là các phép toán đơn điệu và tuyến tính $(A \triangle A = 0)$.

Chỉ cần làm theo hai bài toán dưới đây là đủ.

Bài tập 1. Chứng minh rằng theo giả định 01, từ bất kỳ phép toán tân âm nào cũng có thể thu được một phép toán bổ sung.

Giả sử $f$ là một phép toán neonotonic và cho $f(A_1, \dots, A_n)$ chỉ được đưa vào tương ứng với $\sigma$ và chỉ tương ứng với $\sigma' \geq \sigma$ không được đưa vào. Sau đó, nếu ở vị trí thứ $j$ và trong $\sigma$ và $\sigma'$ có 0, thì thay vì $A_j$ chúng ta thay thế tập trống, nhưng nếu cả ở đây và ở đó đều có 1 thì chúng ta thay thế tập phổ quát $I$. Ở những nơi khác, vì $\sigma' \geq \sigma$, trong $\sigma$ có 0 và trong $\sigma' - 1$. Chúng ta hãy thay thế cùng một bộ $A$ thay vì những $A_j$ này. Khi đó, câu trả lời phải $\sigma$ sẽ chuyển thành $A$, và câu trả lời phải là $\sigma'$ sẽ chuyển thành $A$. Phép toán kết quả $\varphi(A)$ sẽ giống như $A$, vì $\varphi(A)$ chứa $A$ và không chứa $A$.

Nhiệm vụ 2. Chứng minh rằng theo giả định 01, giao điểm có thể được biểu diễn thông qua bất kỳ phép toán neonotonic và phần bù nào.

Hãy cố gắng tự mình giải quyết bài toán này. lời giải của chúng tôi được đưa ra trên trang. 58.

*) Xem cuốn sách Gindikin S.G., Đại số logic trong các vấn đề, M., “Nauka”, 1972.
