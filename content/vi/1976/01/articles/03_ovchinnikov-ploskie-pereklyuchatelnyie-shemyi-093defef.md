---
id: 1976-1-ovchinnikov-ploskie-pereklyuchatelnyie-shemyi-093defef
issue: kvant_1976_1
year: 1976
number: "1"
title: Mạch chuyển mạch phẳng
authors:
  - Овчинников С. В.
rubric: osnovnye-stati
page_first: 14
page_last: 19
page_labels: 12-17
tag: AO43
lang: vi
source: kvant_digital
extraction: vision
content_sha256: 7e2861452491ec13b5e5f0170fc36a4d2eefbe43db0d8aef235c2858794ce55f
prompt_sha256: draft-1
translated_from: content/ru/1976/01/articles/03_ovchinnikov-ploskie-pereklyuchatelnyie-shemyi-093defef.md
source_content_sha256: e8dbfdbdb32362c30ea7f43c23c2662c9195a96515436879e3e3ccbae8c36976
translation_model: draft
translation_run: vi-draft-2026-10-31
translation_quality: draft
---

⟦folio 12⟧

S. Ovchinnikov

Mạch chuyển mạch phẳng

Bạn có thể dễ dàng hiểu mạch chuyển mạch là gì từ Hình 1. Có hai nhóm cực $n$ - một nhóm đầu vào và một nhóm đầu ra ($n = 4$ trong Hình 1). Mỗi làn đầu vào được kết nối với một và chỉ một làn đầu ra. Người đọc quen với khái niệm *đồ thị* có thể nhận thấy rằng mạch chuyển mạch là một loại đồ thị đặc biệt. Những đồ thị như vậy được gọi là *sevens*.

Khi tạo ra các thiết bị kỹ thuật sử dụng mạch chuyển mạch, yêu cầu các kết nối giao nhau phải được cách ly với nhau. Trong các thiết bị thông thường, các kết nối được thực hiện bằng dây dẫn và do đó yêu cầu này dễ dàng được đáp ứng. Một ví dụ về thiết bị như vậy là mạch chuyển mạch,

Cơm. 1.

Cơm. 2.

⟦folio 13⟧

hiển thị một mạch thực hiện tính đối xứng của các số $n$: đầu vào thứ $i$ được kết nối với đầu ra thứ $(n-i+1)$. Mạch này yêu cầu lớp $n$, vì mỗi cặp liên kết phải nằm trong các lớp khác nhau.

Bây giờ chúng ta hãy xây dựng các điều kiện bài toán chặt chẽ và chứng minh định lý chính.

Chúng ta hãy cho một mạch chuyển mạch có $n$ đầu vào và $n$ đầu ra; đánh số chúng bằng các số nguyên 1, 2, ..., $n$. Mỗi lược đồ như vậy xác định ánh xạ một-một lên chính tập hợp số $\{1, 2, ..., n\}$; nói cách khác, mạch chỉ định một hoán vị $P$ tập hợp số $\{1, 2, ..., n\}$, khớp số đầu vào với số đầu ra được kết nối với nó. Ví dụ, mạch chuyển mạch ở Hình 1 tương ứng với hoán vị $1 \rightarrow 2, 2 \rightarrow 4, 3 \rightarrow 1, 4 \rightarrow 3$. Rõ ràng là mỗi hoán vị lần lượt tương ứng với một mạch chuyển mạch nhất định. Do đó, trong phần tiếp theo chúng ta sẽ không phân biệt giữa các mạch chuyển mạch và các hoán vị tương ứng của chúng.

Số $n$ được gọi là lũy thừa của hoán vị $P$. Kết nối kết nối đầu vào $i$ với đầu ra $j$ sẽ được ký hiệu là $(i, j)$. Khi đó hoán vị $P$ có thể được định nghĩa là tập hợp $\{(i, j)\}$ của tất cả các kết nối.

Hãy xem xét một số ví dụ. Sơ đồ trong Hình 1 tương ứng với hoán vị bậc 4, có thể được viết dưới dạng một tập hợp các kết nối:

$$P_1 = \{(3, 1), (1, 2), (4, 3), (2, 4)\}.$$

Các hoán vị bậc $n$ tương ứng với sơ đồ ở Hình 3 và Hình 4 được viết như sau:

$$P_2 = \{(1, 1), (2, 2), ..., (n, n)\},$$
$$P_3 = \{(n, 1), (n-1, 2), ..., (1, n)\}.$$

Bài 1. Chứng minh hai liên kết $(i, j)$ và $(p, q)$ cắt nhau khi và chỉ khi $(i-p)(j-q) < 0$.

Một tập hợp con các liên kết được gọi là “lớp hoán vị $P$” nếu không có hai liên kết nào từ tập hợp con này giao nhau. Hình 2 cho thấy hai lớp hoán vị $P_1$. Hoán vị $P_2$ bản thân nó là một lớp và đối với hoán vị $P_3$, mỗi lớp bao gồm chính xác một kết nối.

Độ dày của hoán vị $P$ là số lớp tối thiểu mà nó có thể được mở rộng trên đó. Trong ví dụ của chúng tôi, độ dày của $P_1$ là 2, độ dày của $P_2$ là 1 và độ dày của $P_3$ là $n$. Rõ ràng, độ dày của bất kỳ hoán vị nào không vượt quá mức $n$ của nó.

Bài 2. Chứng minh rằng với mọi số nguyên $p \leq n$ đều có hoán vị $P$ bậc $n$ và độ dày $p$.

Các hoán vị có độ dày 2 được gọi là có thể thực hiện được 2 (chúng có thể được phân tách trơn tru thành hai lớp) và có các tính chất sau. Chúng tôi đặt kết nối $(i, j)$ ở bên phải, nếu $i \geq j$ và ở bên trái, nếu $i < j$ (Hình 5 hiển thị một hoán vị, các kết nối bên phải được đánh dấu màu đỏ và các kết nối bên trái được đánh dấu màu xanh lam). Hóa ra tập hợp tất cả các kết nối bên trái của hoán vị 2-có thể thực hiện được là một lớp. (Chứng minh điều đó.)

Ví dụ, hoán vị trong Hình 5 không thể thực hiện được bằng 2: hoán vị bên trái của nó

⟦folio 14⟧

Cơm. 5.

kết nối (2, 5) và (3, 4) giao nhau. Đối lập về ý nghĩa với khái niệm lớp là khái niệm bó. Một tập hợp con các liên kết được gọi là một bó nếu có hai liên kết bất kỳ từ tập hợp con này giao nhau. Độ dày của một bó là số lượng trái phiếu có trong đó. Chúng ta sẽ coi mỗi liên kết là một chùm có độ dày 1.

Hãy quay lại ví dụ của chúng tôi. Hoán vị $P_1$ (xem Hình 1) có ba bút chì có độ dày 2:
$\{(3, 1), (1, 2)\}, \{(3, 1), (2, 4)\}$ và $\{(4, 3), (2, 4)\}$.

Tất cả các bó của hoán vị $P_2$ (Hình 2) có độ dày 1. Đối với hoán vị $P_3$ (Hình 3), bất kỳ tập hợp con nào của kết nối đều là một bó. Đặc biệt, bản thân hoán vị $P_3$ là một bó.

Trong số các dầm hoán vị này, các dầm có độ dày tối đa được đặc biệt quan tâm. Chúng tôi gọi các bó như vậy là tối đa.

Bài toán 3. Chứng minh rằng bó cực đại của một hoán vị tùy ý không thể chỉ bao gồm các kết nối bên trái của nó.

Có một mối quan hệ rõ ràng giữa độ dày của hoán vị và độ dày của chùm tia tối đa của nó: chùm hoán vị càng dày thì nó càng dày. Định lý sau đây chỉ rõ sự phụ thuộc này.

Định lý 1. Độ dày của một hoán vị bằng độ dày của bút chì cực đại của nó.

Vì một liên kết từ một gói tối đa phải nằm ở các lớp khác nhau nên số lượng từ không thể thay đổi được.

nhỏ hơn chiều dày dầm. Do đó, để chứng minh định lý, chỉ cần xây dựng một phân tích của một hoán vị cho trước có số từ bằng số liên kết trong bút chì tối đa là đủ. Nói cách khác, mỗi lớp của sự phân tách như vậy phải chứa chính xác một kết nối từ gói tối đa.

Trước khi chứng minh Định lý 1, chúng ta hãy thiết lập một tính chất quan trọng của bút chì cực đại.

Bổ đề. Cho phép
$(i_1, j_1), (i_2, j_2), \dots, (i_p, j_p)$
- các kết nối được bao gồm trong gói tối đa, và
$j_1 < j_2 < \dots < j_p$.

Nếu một số kết nối $(i, j)$ giao với kết nối $(i_1, j_1)$ thì $i < i_1$.

Bằng chứng. Giả sử ngược lại, từ kết quả bài toán 1 ta thu được $j < j_1$. Nhưng sau đó liên kết $(i, j)$ cắt tất cả các liên kết của gói Dann và điều này mâu thuẫn với liên kết tối đa của nó.

Chúng ta sẽ nói rằng việc kết nối $(i, j)$ bắt đầu ở $j$ đầy đủ. thì tính chất hình học đã được chứng minh có nghĩa là bất kỳ kết nối nào bắt đầu từ bên trái của bút chì cực đại đều không cắt kết nối ngoài cùng bên trái của nó. Tương tự, bất kỳ liên kết nào bắt đầu từ bên phải của bút chì tối đa đều không cắt liên kết ngoài cùng bên phải của nó. Sắp xếp lại trong Hình 6 hoặc sẽ xây dựng bổ đề của chúng tôi. Được đánh dấu màu đỏ là các kết nối của chùm tia tối đa. (1, 5) là kết nối ngoài cùng bên phải của gói tối đa, (4, 2) là kết nối ngoài cùng bên trái. Nhân tiện, xin lưu ý rằng có thể có một số ròng rọc tối đa. Để sắp xếp lại trong Hình.

⟦folio 15⟧

Sunka 6 có ba trong số đó:
{(4, 2), (3, 4), (1, 5)}, {(7, 3), (3, 4), (1, 5)} và {(7, 3), (6, 6), (5, 7)}.

Chứng minh Định lý 1.

Chúng tôi đưa ra một bằng chứng mang tính xây dựng, nghĩa là chúng tôi chỉ ra một quy trình trong đó mỗi hoán vị có thể được phân tách thành một số từ tối thiểu.

Chúng ta chỉ biểu thị quán trọ của bút chì cực đại bằng $p$. Chúng ta hãy gán kết nối $(u_1, 1)$ (nghĩa là kết nối ngoài cùng bên trái của hoán vị) cho lớp đầu tiên và biểu thị nó $(u_1, v_1)$. Trong số tất cả các kết nối $(i, j)$ không giao nhau $(u_1, v_1)$, hãy xem xét kết nối có $j$ lung linh nhất. $(u_2, v_2)$ của riêng nó và cũng được bao gồm trong lớp đầu tiên. Bằng cách sắp xếp các kết nối trong một hàng, bắt đầu từ kết nối ngoài cùng bên trái và gán cho lớp đầu tiên những kết nối không giao nhau với những kết nối đã chọn, chúng ta thu được một tập hợp các kết nối rời rạc theo cặp $(u_1, v_1), (u_2, v_2), \dots, (u_h, v_h)$, tạo thành lớp đầu tiên.

Bản thân các kết nối không có trong lớp đầu tiên sẽ tạo thành một hoán vị nhất định. Áp dụng cách xây dựng trước đó cho hoán vị này, chúng ta có được lớp thứ hai, v.v.

Chúng ta hãy xem điều gì xảy ra với chùm tia tối đa trong quá trình xây dựng này. Hãy để chúng tôi biểu thị các kết nối có trong gói này bằng $(i_1, j_1), (i_2, j_2), \dots, (i_p, j_p), j_1 < j_2 < \dots < j_p$. Theo bổ đề, kết nối $(i_1, j_1)$ không giao nhau với bất kỳ kết nối nào bắt đầu từ bên trái của nó và do đó phải rơi vào lớp đầu tiên. Không có kết nối nào khác từ gói tối đa này sẽ rơi vào lớp đầu tiên vì chúng giao nhau với kết nối $(i_1, j_1)$. Do đó, từ mỗi bó tối đa, một kết nối sẽ rơi vào lớp đầu tiên.

Hãy chọn lớp đầu tiên từ hoán vị của chúng tôi. Dễ dàng nhận thấy trong hoán vị còn lại các ròng rọc cực đại chỉ có $p-1$. Bằng cách chọn lớp thứ hai, chúng tôi chỉ thu được $p-2$ các ròng rọc tối đa trong hoán vị còn lại. Tiếp tục quá trình chọn từ này, ở bước thứ $(p-1)$, chúng ta thu được một hoán vị có các bó tối đa chỉ có 1. Nhưng điều này có nghĩa là các kết nối trong hoán vị này không giao nhau và do đó, bản thân nó tạo thành lớp thứ $p$ cuối cùng.

Vì vậy, chúng tôi đã chỉ ra rằng bất kỳ hoán vị nào cũng có thể được phân tách thành các lớp, số lượng lớp đó chỉ bằng bó tối đa; Sự khai triển này chứng minh định lý.

Tăng cường. Kiểm tra tính đúng đắn của định lý đối với $P_1, P_2$ và $P_3$.

Chúng ta hãy xem xét các mạch chuyển mạch chỉ tương ứng với các hoán vị 2, nghĩa là các hoán vị có thể thực hiện được 2; chúng được đặc biệt quan tâm vì chúng chỉ yêu cầu sản xuất hai lớp dẫn điện. Cho hai mạch chuyển mạch như vậy được kết nối như trong Hình 7. Rõ ràng, mạch kết quả ở Hình 7 tương đương với mạch chuyển mạch trong Hình 8. Chúng ta hãy biểu thị hoán vị tương ứng với mạch trong Hình 8 bằng $P$, và các hoán vị tương ứng với các mạch trên và dưới của Hình 7 bằng $P_1$ và $P_2$ tương ứng. Chúng ta sẽ nói rằng hoán vị $P$ bằng tích của các hoán vị $P_1 \cdot P_2$.

Theo cách tương tự, bạn có thể xác định tích của bất kỳ số hoán vị nào. Thứ tự của các thừa số trong tích như vậy rất quan trọng: ví dụ: nếu chúng ta lấy hoán vị

⟦folio 16⟧

Hóa ra là bất kỳ hoán vị nào cũng có thể bị phân hủy thành tích của một số hoán vị có thể thực hiện được! (Chứng minh điều đó.)

Nếu một hoán vị được biểu diễn dưới dạng tích của s “mảnh” hoán vị có thể thực hiện được 2 thì nó được gọi là có thể thực hiện được theo tầng s. (Như vậy, hoán vị P (độ dày 3) thể hiện trên Hình 8 là có thể thực hiện được 2 tầng; việc phân tách P thành 2 tầng hoán vị 2 tầng thực hiện được được thực hiện bằng các hoán vị P₁ và P₂ của Hình 7.) Công nghệ hoán vị s-cascade có hai lớp dẫn điện và một lớp cách điện, hoán đổi cho nhau s - 1 lần. Lớp cách điện đầu tiên tương ứng với khoảng cách giữa các tầng; Rõ ràng là khi lớp cách điện bị đứt sẽ không xảy ra sự giao nhau của các liên kết. Mỗi lớp cách điện tương ứng với một điểm đứt trong 2) được thực hiện qua từng giai đoạn, nhưng có lẽ ở các dây khác nhau của lớp - xem Hình 10; các kết nối nằm trong cùng một lớp dẫn điện được biểu thị bằng cùng một màu.

Vì vậy, như chúng tôi đã nói, đối với bất kỳ hoán vị nào cũng tồn tại sự phân rã theo tầng. Số lượng tầng tối thiểu cần thiết để phân tách tầng của một hoán vị nhất định là bao nhiêu? Hãy thử tìm hiểu.

Hãy bắt đầu với hoán vị Kₚ, tương ứng với số i với số p - i + 1, tức là nhận ra tính đối xứng của số p.

Như đã lưu ý, hoán vị Kₚ trùng với bó cực đại của nó và chỉ có cùng giá trị với p. Bây giờ chúng ta sẽ xây dựng một số phân tách theo tầng của hoán vị Kₚ thành các hoán vị hai lớp và sau đó chỉ ra rằng phân tách được xây dựng là tối thiểu.

Với p = 2, hoán vị K₂ bản thân nó là một tầng (đơn vị). Cách phân rã hoán vị K₄ (p = 4) có thể xem trên Hình 11. Sử dụng ý tưởng phân rã tầng

⟦folio 17⟧

y để sắp xếp lại $K_4$, chúng ta hãy xây dựng một phân rã tầng của hoán vị $K_8$ ($p = 8$) - xem Hình 12. Bây giờ đã rõ cách xây dựng phân rã tầng của hoán vị $K_p$, Nếu như $p$ bằng lũy ​​thừa của hai. Tầng trên (đối với $p = 2^r$) được thể hiện trên Hình 13. Các tầng còn lại thực hiện đối xứng các hoán vị dương 1, 2, ..., $2^{r-1}$ và tích cực $2^{r-1} + 1$, $2^{r-1} + 2$, ..., $2^r$; cùng lúc $k$tầng hoán vị bậc thứ $2^r$ thu được bằng cách kết hợp hai giống hệt nhau ($k-1$)- tầng hoán vị bậc $2^{r-1}$. Rõ ràng, số tầng trong phân rã tầng được xây dựng của hoán vị $K_2^r$ bằng $r$.

Hãy để nó bây giờ $p$ không phải là sức mạnh của hai; thế thì có chuyện như vậy $r$, Cái gì $2^r < p < 2^{r+1}$. Chúng ta hãy xem xét sự phân rã tầng của hoán vị $K_{2r+1}$ độ $2^{r+1}$ và chúng ta thấy trong đó các kết nối bắt đầu ở các vị trí có số lượng không vượt quá $p$. Rõ ràng, những kết nối này xác định hoán vị $K_p$ (mục nhập có số $2^{r+1} - p + 1$, $2^{r+1} - p + 2$, ..., $2^{r+1}$ bạn cần đo lại, bắt đầu từ đơn vị: 1, 2,... $p$) và sự phân rã tầng này của hoán vị $K_{2r+1}$ cũng phân hủy hoán vị $K_p$. Ví dụ, trong Hình 14, phân rã tầng cho hoán vị $K_6$ được rút ra từ việc khai triển cho $K_8$.

Vì vậy, đối với các hoán vị $K_p$ là các ròng rọc, chúng tôi đã xây dựng các phép mở rộng theo tầng. Nếu $p$ sao cho $2^{r-1} < p \leq 2^r$ thì số giai đoạn là $r$. Nếu không, nó có thể được viết như sau: $r = \log_2 p$, trong đó $|a|$ biểu thị số nguyên nhỏ nhất, không nhỏ hơn $a$.

Bây giờ chúng ta hãy chỉ ra rằng việc mở rộng tầng được xây dựng của các hoán vị $K_p$ bao gồm một số tầng tối thiểu. Đối với ví dụ này, hãy lập chỉ mục theo $p$. Lưu ý rằng nếu $p < q$, thì phân rã tầng tối thiểu của hoán vị bậc $q$ yêu cầu không ít tầng hơn phân tách tối thiểu của hoán vị bậc $p$.

Đối với $p = 2$ tuyên bố của chúng tôi là hiển nhiên. Hãy chứng minh khẳng định cho $p = k$. Hãy xem xét hai trường hợp.

a) $2^{r-1} < k < 2^r$.

Đối với hoán vị $K_k$ bậc $k$, chúng ta có phân tách xếp tầng $r$. Khi di chuyển từ $k$ và $k+1$, số tầng, như nhận xét của chúng tôi, không giảm. Nhưng vì $k$ là một số nguyên, nên $k+1 \leq 2^r$, và do đó chúng ta có thể xây dựng một khai triển xếp tầng $r$ của hoán vị $K_{k+1}$ bậc $k+1$; Bây giờ rõ ràng rằng đó là mức tối thiểu.

b) $k = 2^r$.

 Hãy xem xét hoán vị $K_{k+1} = K_{2r+1}$. Vì $2^{r+1} < 2^{r+1}$, chúng ta có thể xây dựng một phân tách xếp tầng $(r+1)$ cho hoán vị $K_{k+1}$. Hãy để chúng tôi chỉ ra rằng các tầng $r$ không đủ để phân tách hoán vị $K_{k+1}$ (khi đó phân tách $(r+1)$-tầng sẽ là phân tách tối thiểu).

Chúng ta hãy giả sử điều ngược lại: giả sử có sự phân rã $r$ theo tầng của hoán vị $K_{2r+1}$ bậc $2^{r+1}$. Hãy xem xét tầng trên của thời điểm này-
