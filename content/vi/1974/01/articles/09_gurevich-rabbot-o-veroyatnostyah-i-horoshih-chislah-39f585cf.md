---
id: 1974-1-gurevich-rabbot-o-veroyatnostyah-i-horoshih-chislah-39f585cf
issue: kvant_1974_1
year: 1974
number: "1"
title: Về xác suất và những con số “tốt”
authors:
  - Гуревич Г. А.
  - Раббот Ж. М.
rubric: matematicheskiy-kruzhok
rubric_sub: Математический кружок
page_first: 37
page_last: 42
page_labels: 35, 37, 38, 40
tag: CRQ8
lang: vi
source: kvant_digital
extraction: vision
content_sha256: 11d24617ace41e0dd279902b73e8bbd4aa71d62bf1bd527d0585d4291ce10e22
prompt_sha256: draft-1
translated_from: content/ru/1974/01/articles/09_gurevich-rabbot-o-veroyatnostyah-i-horoshih-chislah-39f585cf.md
source_content_sha256: 989f086267cd2050ad3bc4d765190ca473aad9a5517c378537ae329ea6feeac9
translation_model: draft
translation_run: vi-draft-2026-10-31
translation_quality: draft
---

⟦folio 35⟧

Về xác suất và những con số “tốt”

G. A. Gurevich, J. M. Rabbom

«Kvant» xuất bản nhiều bài toán toán học khác nhau. Trong những bức thư gửi cho biên tập viên, câu hỏi thường được đặt ra: “Làm thế nào mà họ nghĩ ra bài toán?” Ghi chú của chúng tôi chủ yếu gửi đến những độc giả quan tâm đến vấn đề này.

Bất chấp tính chất "sơ cấp" của nhiều bài toán thú vị, hầu hết chúng đều là sự tái tạo lại các sự kiện toán học có ý nghĩa. Thật không may, nhiều học sinh, ngay cả sau khi giải được bài toán này, thậm chí không nhận thức được ý tưởng mà nó nảy sinh.

Mục đích của ghi chú này là nói một chút về lý thuyết xác suất mà bài toán M204 của “Sách Vấn đề”, Quanta’ được kết nối và đưa ra một lời giải đơn giản cho bài toán này.

Đầu tiên chúng ta nhớ lại các điều kiện của bài toán M204.

Chúng ta gọi một số tự nhiên là "tốt" nếu các số 1, 9, 7, 3 xuất hiện liên tiếp trong ký hiệu thập phân của nó và "xấu" trong trường hợp lời hứa. Chứng minh rằng tồn tại số tự nhiên n sao cho trong số tất cả các số có n chữ số có nhiều số tốt hơn số xấu.

Một số ví dụ

Chúng ta sẽ bắt đầu bằng cách xem xét một vài ví dụ mà thoạt nhìn thì không liên quan gì đến vấn đề của chúng ta.

Ví dụ 1: Giả sử chúng ta tung một đồng xu. Nếu nó không có sai sót thì chúng ta cũng có thể kỳ vọng rằng nó sẽ đưa ra “đầu” và “đuôi” ở trên. Ngoài ra, trực giác cho chúng ta biết rằng nếu chúng ta tung một đồng xu hai lần, thì mức tăng của chúng ta về khả năng ít nhất một trong hai lần nó chạm mặt “ngửa” sẽ lớn hơn nhiều so với việc nó chạm mặt “sấp” một lần. Và có lẽ mọi người sẽ đồng ý rằng nếu bạn tung một đồng xu 100 lần thì gần như chắc chắn rằng “ngửa” sẽ xuất hiện ít nhất một lần, hay nói cách khác, khó có khả năng “sấp” sẽ xuất hiện hết 100 lần.

Ví dụ 2. Người ta đặt 10 quả bóng đỏ và 2 quả bóng đen vào một hộp. Nếu bạn lấy ngẫu nhiên một quả bóng ra khỏi hộp, gần như chắc chắn nó sẽ có màu đỏ, vì số quả bóng đỏ nhiều hơn số quả bóng đen. Nhưng nếu chúng ta lặp lại thí nghiệm này nhiều lần (giả sử một lần), mỗi lần khôi phục “vị trí ban đầu”, tức là trả quả bóng đã lấy ra về vị trí của nó và trộn kỹ những thứ bên trong hộp, thì chúng ta có thể nói chính xác rằng sớm hay muộn chúng ta sẽ rút được quả bóng đen ra.

Ví dụ 3. Hãy lấy 10.000 tấm thẻ và viết lên đó tất cả các số tự nhiên từ 0 đến 9999 (mỗi thẻ có một số). Nếu thẻ chứa số có một chữ số, hai chữ số hoặc ba chữ số thì chúng ta sẽ lần lượt thêm ba, hai hoặc một số 0 vào bên trái của số đó. Như vậy, tất cả các số ghi trên thẻ sẽ có bốn chữ số. Đặt tất cả các thẻ vào một gói và trộn kỹ. Bây giờ chúng ta sẽ tiến hành thí nghiệm tiếp theo.

⟦folio 37⟧

container), nó bao gồm hai phần cơ bản: “lấy bi đen số 1” và “lấy bi đen số 2”.

Trong ví dụ 3, việc loại bỏ thẻ là một sự kiện cơ bản. Tổng số sự kiện sơ cấp ở đây là 10.000. Nhưng việc trích xuất một thẻ có ghi “true”, một số có bốn chữ số (tức là số có chữ số đầu tiên bên trái không bằng 0) là một sự kiện gồm 9000 số cơ bản: “lấy thẻ có số 1000”, “lấy thẻ có số 1001”, “lấy thẻ có số 1002”, ..., “lấy thẻ có số 9999”.

Chúng ta sẽ gán (đặt tương ứng) số $\frac{1}{n}$ cho sự kiện cơ bản nào $e_1, e_2, \ldots, e_n$, mà chúng ta gọi là xác suất xảy ra sự kiện cơ bản của nó.

Lưu ý rằng chúng ta đã gán cho mỗi sự kiện cơ bản một xác suất bằng nhau nhất định. Điều này thể hiện rằng tất cả họ đều “bình đẳng”.

Các sự kiện cơ bản tạo nên sự kiện $A$ này được gọi là kết quả thuận lợi cho sự kiện này. Xác suất $p(A)$ của một sự kiện $A$ bao gồm $m$ sự kiện cơ bản được xác định như sau:

$$p(A) = \frac{m}{n},$$

trong đó $m$ là số sự kiện thuận lợi $A$ kết quả, $n$ là tổng số kết quả.

Trong thực tế

1. Khi ném xúc xắc thì xác suất 1, 2, 3, 4, 5, 6 điểm là như nhau. Xác suất để khi tung xúc xắc bạn nhận được:

a) số điểm chẵn;
b) số điểm lẻ;
b) 3 hoặc 5 điểm;
g) số nguyên tố?

2. Xác suất để số được ghi trên thẻ được chọn trong ví dụ 3 có các tính chất sau là bao nhiêu:

a) bốn chữ số;
b) chia hết cho 5;

b) có một hình vuông hoàn hảo;
g) không phải là số có bốn chữ số?

Rõ ràng, với định nghĩa này, xác suất của bất kỳ sự kiện nào cũng nằm trong khoảng từ 0 đến 1: $0 \leq p(A) \leq 1$.

Một sự kiện có xác suất bằng 1 được gọi là đáng tin cậy. Anh ấy được ưu ái bởi mọi kết quả mà không có ngoại lệ.

Một sự kiện thiên về tập hợp các phần tử sự kiện trống (nói cách khác, sự kiện sẽ không bao giờ xảy ra) theo định nghĩa này có xác suất bằng 0 và được gọi là không thể.

Thao tác trên các sự kiện

Đặt $A$ là một sự kiện. Chúng ta hãy biểu thị bằng $\bar{A}$ sự kiện ngược lại với $A$, tức là một sự kiện có lợi cho tất cả các kết quả cơ bản không có trong $A$.

Đặt $A$ và $B$ là hai sự kiện. Đặt $A + B$ biểu thị một sự kiện bao gồm các kết quả có lợi cho ít nhất một trong các kết quả $A$ và $B$.

Đặt $A \cdot B$ biểu thị một sự kiện bao gồm các kết quả có lợi cho $A$ nhưng không có lợi cho $B^*$).

Trong thực tế

3. Chứng minh rằng: a) $p(\bar{A}) = 1 - p(A)$;
b) $p(A + B) \leq p(A) + p(B)$; c) $p(A \cdot \bar{A}) = 0$; d) $p(A + \bar{A}) = 1$; e) $p((\bar{A})) = p(A)$;
e) $p((A \setminus B) + (A \cdot B)) = p(A)$;
g) $p((A \setminus B) \cdot B) = 0$.

4. Giả sử sự kiện $A$ là trích một số có bốn chữ số trên thẻ trong ví dụ 3, sự kiện $B$ là trích một số, thực hiện trên 5. Nêu ý nghĩa của từng chữ số

*) Các bạn đọc bài: Gindkin S.G., Có bao nhiêu phép tính trên một tập hợp? «Kvant», 1973, Số 7, tất nhiên, nhận thấy rằng các phép toán trên các sự kiện được định nghĩa giống hệt như các phép toán trên một tập hợp (chỉ cùng nhau $A \cap B$, $A \cup B$ được ký hiệu là $AB$, $A + B$).

⟦folio 38⟧

Hình 1.

sự kiện trong ngoặc bên dưới và tìm:
a) $p(\overline{A})$; b) $p(\overline{B})$; c) $p(A + B)$; d) $p(A \cdot B)$;
e) $p(A + \overline{B})$; f) $p(A \cdot \overline{B})$; g) $p(A \setminus \overline{B})$;
h) $p(B \setminus A)$.

5. Chứng minh rằng với hai số thích hợp bất kỳ $A$ và $B$ thì đẳng thức
$$p(A + B) = p(A) + p(B) - p(A \cdot B).$$

Một phần, trong Hình 1, tập hợp các phần tử thích hợp bao gồm 16 phần tử, được mô tả dưới dạng các chấm đen. Trong trường hợp này, $p(A) = 5/8$, $p(B) = 3/8$, $p(A \cdot B) = 3/16$, $p(A + B) = 13/16$.

Một loạt các bài kiểm tra độc lập

Trong các ví dụ của chúng ta, chúng ta không chỉ nói về các bài kiểm tra đơn lẻ (tung đồng xu, rút ​​quả bóng hoặc thẻ) mà còn nói về một loạt các bài kiểm tra như vậy. Làm thế nào để tính xác suất trong những trường hợp như vậy? Ở đây chúng ta đi vào các vấn đề tổ hợp. Sơ đồ hành động như sau: đầu tiên bạn cần tìm tập hợp các phần tử của riêng mình và xác định số $N$ các phần tử của nó, sau đó xác định số $M$ các kết quả có lợi cho $A$ và sử dụng công thức $p(A) = \frac{M}{N}$ tìm đáp số.

Ví dụ: hãy giải bài toán này. Hãy để chúng tôi yêu cầu bạn tung một đồng xu. Xác suất để mất “ngửa” và “sấp” là bao nhiêu thì xác suất của lần tung thứ hai không phụ thuộc vào kết quả của lần tung đầu tiên (kiểm tra độc lập), thì cả bốn kết quả này đều có xác suất như nhau.

Tương tự, nếu chúng ta ném một đồng xu ba lần, thì kết quả của lần ném này sẽ là tất cả các loại bộ ba từ O và P. Đối với mỗi kết quả, chúng ta gán cùng một xác suất bằng $1/8$ và sự kiện mà chúng ta quan tâm “rơi ra O và P qua một cung” bao gồm hai phần tử của riêng nó; xác suất của nó bằng $2 \cdot \frac{1}{8} = \frac{1}{4}$ (Hình 2).

Trong trường hợp chung, nếu một thử nghiệm đơn lẻ cho phép $n$ yếu tố của kết quả, thì số lượng tất cả các yếu tố có thể có của kết quả của thử nghiệm kép rõ ràng bằng $n^2$ (bất kỳ kết quả nào trong số $n$ của thử nghiệm đầu tiên có thể độc lập

⟦folio 40⟧

Số hạng chung của cấp số nhân $\left(\frac{9999}{10000}\right)^k$ có giá trị $\frac{9999}{10000}$ nhỏ hơn 1, với mức tăng không giới hạn $k$ có ​​xu hướng bằng 0. Do đó, nó sẽ tìm thấy một $k_0$ như vậy, phần đầu của nó là $\left(\frac{9999}{10000}\right)^{k_0} < \frac{1}{2}$, tức là $1 - \left(\frac{9999}{10000}\right)^{k_0} > \frac{1}{2}$.

Tại $k > k_0$ trong các số có 4$k$ chữ số sẽ có nhiều số “tốt” hơn số “xấu”.

Từ lời giải của chúng tôi, chúng tôi thu được ước tính sau đây cho mức tối thiểu $n = n_0$, bắt đầu bằng số đó trong số các số có $n$ chữ số có nhiều số tốt hơn số xấu: $n_0 > 4\lg 2/\lg \left(\frac{10000}{9999}\right) \approx 30000$.

Tất nhiên, ước tính này khá thô.

Điều đáng chú ý là một số chữ cái (N. Sherbin, Dnepropetrovsk; A. Kurlyandchik, Leningrad; A. Grigoryan, Baku), trong đó người ta đã tìm thấy ước tính chính xác hơn. Cách thú vị nhất ở đây là thế này. Gọi $G(n)$ là số các số tốt có $n$ chữ số: $G(1) = G(2) = G(3) = 0$, $G(4) = 1$, $G(5) = 19$, $G(6) = 280, \dots$

Hãy để chúng tôi chứng minh điều đó với $n > 5$
$G(n) = 9 \cdot 10^{n-5} + 10G(n-1) - G(n-4)$. (*)

Thật vậy, có những số có $9 \cdot 10^{n-5}$ $n$ chữ số kết thúc vào năm 1973; những số tốt vẫn còn tốt sau khi gạch bỏ chữ số cuối cùng là $10G(n-1)$, và các số thuộc bộ này rất tiện lợi $G(n-4)$.

Từ hệ thức hiện tại (*), có thể dễ dàng suy ra rằng mức tối thiểu $n_0$ nằm trong khoảng từ 5000 đến 10000. Và nếu bạn sử dụng máy tính (như độc giả L. Kurlyandchik, anh trai của chúng tôi đã làm), thì bạn có thể nhanh chóng tìm thấy giá trị chính xác $n_0$: nó bằng 6933.

Sai lầm chính mà hầu hết người đọc hướng dẫn đều mắc phải là như sau. Thay vì ước tính từ trên số lượng điểm hút và số x như đã làm
