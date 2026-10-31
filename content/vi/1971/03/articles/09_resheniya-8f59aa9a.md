---
id: 1971-3-resheniya-8f59aa9a
issue: kvant_1971_3
year: 1971
number: "3"
title: Lời giải các bài M26—M28; F35—F40
rubric: zadachnik-kvanta
rubric_sub: Задачник «Кванта»
page_first: 34
page_last: 41
page_labels: 32, 33, 34, 35, 37, 38, 39
tag: 2KIG
lang: vi
source: kvant_digital
extraction: vision
content_sha256: c5ac0296f68ab5af81be4102eeca3d2818f8d9d92e14ba41c507ac96fe6da0f5
prompt_sha256: 3ec6b8aabd9b98576af76503cd8a2902b9f5d18e01ee867dfb1228f59c6d52d8
translated_from: content/ru/1971/03/articles/09_resheniya-8f59aa9a.md
source_content_sha256: bd64d325a2302e14f6c4b01d1587b5aa0bdd559fe3c204d3dfb12307184aaecf
translation_model: gpt-5.6-terra
translation_run: vi-codex-2026-10-31
---

⟦folio 32⟧

LỜI GIẢI

M26

Giả sử rằng trong mỗi số báo của tạp chí chúng ta, mục «Kvata» có năm bài toán toán học. Ký hiệu $f(x, y)$ là số thứ tự của bài đầu tiên trong các bài toán của số báo thứ $x$ vào năm thứ $y$ (ví dụ, $f(6, 1970) = 26$). Hãy viết công thức tổng quát cho $f(x, y)$ với mọi $x, y$ ($1 \leq x \leq 12, y \geq 1970$). Giải phương trình $f(x, y) = y$.

Hàm số $f$ thỏa mãn các điều kiện sau:

1) $f(1, 1970) = 1$;
2) $f(x + 1, y) = f(x, y) + 5$ ($1 \leq x < 12$) — qua mỗi tháng $f(x, y)$ tăng thêm 5;
3) $f(1, y + 1) = f(1, y) + 60$ — qua mỗi năm $f(x, y)$ tăng thêm 60.

Rõ ràng, các điều kiện này xác định duy nhất hàm số; chẳng hạn, có thể cho nó bằng công thức sau:

$$f(x, y) = 5x + 60(y - 1970) - 4.$$

Không khó kiểm tra rằng $f(5, 2003) = 2001$; $f(6, 2003) = 2006$. Vì vậy phương trình $f(x, y) = y$ không có nghiệm.

Lời giải đúng được E. Orlok từ Zhytomyr, N. Ilyin từ thị trấn Zakhar, tỉnh Irkutsk, M. Perelmuter từ Kiev và các bạn đọc khác gửi đến.

Từ những điều đã nói ở trên, rõ ràng rằng nếu chúng ta còn đưa vào một hàm như sau: $f(k, x, y)$ — số thứ tự của bài toán thứ $k$ trong số báo thứ $x$ của tạp chí năm thứ $y$ ($1 \leq k \leq 5, 1 \leq x \leq 12, y \geq 1970$), thì phương trình $f(k, x, y) = y$ sẽ có nghiệm duy nhất $k = 3, x = 5, y = 2003$ — nói cách khác, nếu hệ thống của chúng ta được giữ nguyên không thay đổi cho đến lúc đó (vẫn có năm bài toán toán học trong mỗi số), thì bài toán thứ ba trong đề bài “Kvanta” số 5 năm 2003 sẽ có số thứ tự M2003. Công thức tổng quát cho $f(k, x, y)$ cũng là:

$$f(k, x, y) = k + 5x + 60(y - 1970) - 5.$$

Đối với độc giả, có lẽ hữu ích hơn là các công thức xác định hàm ngược, cho phép theo số thứ tự $n$ tìm năm $y$ và số tạp chí $x$ mà bài toán này được đề nghị.

Để làm điều đó, tiện dùng các ký hiệu sau: $[a]$ — phần nguyên của số $a$ (số nguyên lớn nhất không vượt quá $a$) và $\{a\} = a - [a]$ — phần thập phân của số $a$.

Hãy kiểm tra rằng

$$x = \left[ 12 \left\{ \frac{n - 1}{60} \right\} \right] + 1, y = \left[ \frac{n - 1}{60} \right] + 1970.$$

M27

Chứng minh rằng nếu $\frac{a}{b - c} + \frac{b}{c - a} + \frac{c}{a - b} = 0$, thì $\frac{a}{(b - c)^2} + \frac{b}{(c - a)^2} + \frac{c}{(a - b)^2} = 0$.

Khẳng định này suy ra từ đồng nhất thức sau:

$$\left( \frac{a}{b - c} + \frac{b}{c - a} + \frac{c}{a - b} \right)\left( \frac{1}{b - c} + \frac{1}{c - a} + \frac{1}{a - b} \right) = \frac{a}{(b - c)^2} + \frac{b}{(c - a)^2} + \frac{c}{(a - b)^2}.$$

Để chứng minh nó, chỉ cần nhân từng hạng hai tổng ở vế trái của đồng nhất thức và lưu ý rằng tổng của ba phân thức

$$\frac{a}{b - c}\left( \frac{1}{c - a} + \frac{1}{a - b} \right) = \frac{ca - ab}{(a - b)(b - c)(c - a)},$$

$$\frac{b}{c - a}\left( \frac{1}{b - c} + \frac{1}{a - b} \right) = \frac{ab - bc}{(a - b)(b - c)(c - a)},$$

$$\frac{c}{a - b}\left( \frac{1}{b - c} + \frac{1}{c - a} \right) = \frac{bc - ca}{(a - b)(b - c)(c - a)}$$

bằng không.

⟦folio 33⟧

Lời giải này do A. Shilitum từ Tashkent gửi đến. Những lời giải kém sáng rõ hơn, nhưng cũng đúng, do B. Paiss từ Novomoskovsk, tỉnh Tula, và A. Izbitsky từ Malorita, tỉnh Brest gửi đến.

Sau khi đọc một lời giải nhân tạo như vậy, dĩ nhiên có thể nảy sinh một câu hỏi hoàn toàn hợp lý: làm sao đoán được rằng các biểu thức đã cho cần được nhân chính với $\frac{1}{b-c} + \frac{1}{c-a} + \frac{1}{a-b}$? Có thể tìm ra một phương pháp giải tổng quát cho phép giải những bài toán tương tự không?

Tự nhiên hơn là giải bài toán này như sau. Viết các biểu thức đã cho dưới dạng tỉ số của hai đa thức:

$$\frac{a}{b-c} + \frac{b}{c-a} + \frac{c}{a-b} = \frac{p(a,b,c)}{(a-b)(b-c)(c-a)},$$

$$\frac{a}{(b-c)^2} + \frac{b}{(c-a)^2} + \frac{c}{(a-b)^2} = \frac{q(a,b,c)}{(a-b)^2(b-c)^2(c-a)^2}$$

($p$ sẽ là đa thức bậc ba, còn $q$ — bậc năm). Ta phải chứng minh rằng nếu $p(a,b,c) = 0$, thì $q(a,b,c) = 0$ cũng vậy. Tự nhiên là thử chứng minh rằng đa thức $q$ chia hết cho đa thức $p$, tức là tìm một đa thức $r=r(a,b,c)$ sao cho $q=pr$ (có thể chứng minh một định lý tổng quát cho các đa thức của một số bất kỳ biến nào: nếu $q$ bằng không tại mọi giá trị của các biến mà tại đó $p$ bằng không, đồng thời đa thức $p$ là bất khả quy, tức là không phân tích được thành các nhân tử — và trong trường hợp này đúng là như vậy, — thì $q$ phải chia hết cho $p$). Có thể chia các đa thức theo cách thông thường — “chia góc”, coi chúng là các đa thức của một biến $a$ (mà trong các hệ số có chứa các chữ $b$ và $c$); chẳng hạn, $p$ sẽ được viết như sau:

$$p(a,b,c) = -a^3 + p_1(b,c)a^2 + p_2(b,c)a + p_3(b,c).$$

Kết quả là, dĩ nhiên, ta sẽ có $q=pr$, trong đó

$$r(a,b,c) = (a-b)(b-c)(c-a)\left(\frac{1}{a-b} + \frac{1}{b-c} + \frac{1}{c-a}\right) = -a^2 + ab + ac + bc - b^2 - c^2.$$

Trong ví dụ này, việc thực hiện kế hoạch giải nói trên gắn liền với những phép tính rất tốn công (trong đa thức $q(a,b,c)$, ngay cả sau khi gộp các hạng tử đồng dạng, vẫn còn 21 hạng tử!), nhưng chúng tôi rất khuyên bạn đọc suy nghĩ kỹ mọi chi tiết của lời giải này, vốn áp dụng được cho nhiều bài khác.

N. B. Vasiliev

M28

a) Trong 19 quả cầu có 2 quả phóng xạ. Với bất kỳ một nhóm quả cầu nào, chỉ bằng một lần kiểm tra có thể biết trong đó có ít nhất một quả phóng xạ hay không (nhưng không thể biết trong nhóm có bao nhiêu quả như vậy). Chứng minh rằng với 8 lần kiểm tra có thể xác định được cả hai quả phóng xạ.

b) Trong 11 quả cầu có 2 quả phóng xạ. Chứng minh rằng với ít hơn 7 lần kiểm tra không thể bảo đảm xác định được cả hai quả phóng xạ.

Hãy bắt đầu bằng một bài toán tương tự nhưng đơn giản hơn. Cho $n$ quả cầu, trong đó có một quả phóng xạ; cần bao nhiêu lần kiểm tra để xác định nó? Dễ chỉ ra một cách cho phép sau $k$ lần kiểm tra xác định một trong $n=2^k$ quả cầu: trước hết chia tất cả các quả cầu thành hai nhóm bằng nhau, mỗi nhóm có $2^{k-1}$ quả, kiểm tra một trong hai nhóm và nhờ đó xác định được quả cầu phóng xạ nằm trong nhóm nào, rồi lại chia nhóm gồm $2^{k-1}$ quả cầu này làm đôi, v.v. — ở mỗi lần kiểm tra số quả cầu giảm đi một nửa, và sau $k$ lần kiểm tra ta sẽ tìm được quả cầu phóng xạ. Rõ ràng, nếu $n<2^k$, thì $k$ lần kiểm tra cũng đủ. Vậy, để xác định một quả cầu phóng xạ trong số $n$ quả, chỉ cần thực hiện $f_1(n)$ lần kiểm tra, trong đó $f_1(n)$ là số nguyên nhỏ nhất $k$ sao cho $n\leq 2^k$ (nói cách khác, $f_1(n)$ là số nguyên nhỏ nhất lớn hơn hoặc bằng $\log_2 n$). Dưới đây ta sẽ thấy rằng số lần kiểm tra ít hơn là không đủ.

Bây giờ hãy chuyển trực tiếp sang lời giải bài toán của chúng ta. Ở đây không thể ngay lập tức thu được kết quả chính xác cho mọi thành viên của phần dư 21 thành viên!, nhưng chúng tôi rất khuyên bạn đọc suy nghĩ kỹ mọi chi tiết của lời giải này, có thể áp dụng cho nhiều bài toán khác.

N. B. Vasiliev

⟦folio 34⟧

Hình 1. Hình này trình bày một cách cho phép sau 5 lần kiểm tra xác định 2 quả cầu phóng xạ trong số 7 quả. Ta coi rằng các quả cầu được đánh số 1, 2, ..., 7, và trong mỗi ô ghi nhóm quả cầu được kiểm tra (đôi khi nhóm chỉ gồm một quả cầu). Chẳng hạn, đầu tiên kiểm tra nhóm gồm ba quả cầu {1, 2, 3}.
Mỗi lần kiểm tra có thể có hai kết quả: “có phóng xạ” — khi đó cần đi theo mũi tên đỏ, và “không có phóng xạ” — khi đó theo mũi tên đen. Nếu ô được tô bóng, nghĩa là không cần kiểm tra thêm. Với mỗi đường đi theo các mũi tên từ trên xuống dưới, từ kết quả của tất cả các lần kiểm tra đã thực hiện trên đường đi đó có thể xác định chính xác cặp quả cầu nào là phóng xạ (cặp đó được chỉ dưới mũi tên thấp nhất). Hãy tự kiểm tra điều này!

nhưng điều chúng ta quan tâm là cần bao nhiêu lần kiểm tra để chắc chắn xác định được các quả cầu phóng xạ, trong bất kỳ cách sắp xếp nào của chúng, kể cả cách bất lợi nhất đối với ta. Tương tự, kiểm tra các quả cầu lần lượt từng quả, có thể xác định hai quả trong 4 quả bằng 3 lần kiểm tra, trong 5 quả — bằng 4, trong 6 quả — bằng 5, trong 7 quả — bằng 6, v.v. Tuy nhiên, với $n=7$ có thể chỉ cần năm lần kiểm tra. Trước khi đọc lời giải tiếp theo, hãy thử chứng minh điều đó, tức là tìm cách tương ứng để tìm các quả cầu phóng xạ. Tuy nhiên, một cách như vậy (có vài cách) được chỉ ra ở hình 1.

Hình này giúp hiểu điều chúng tôi muốn nói bằng các từ «cách tìm các quả cầu»: để nêu một cách nào đó, cần chỉ ra nhóm quả cầu được kiểm tra đầu tiên, đồng thời chỉ ra cần kiểm tra nhóm nào sau mỗi kết quả có thể có của lần thử phóng xạ tiếp theo; nói cách khác, cần vẽ một sơ đồ gồm các ô hình chữ nhật và các mũi tên — giống như ở hình 1, chỉ khác, nếu cần, ở số lần kiểm tra $k$ — và viết vào mỗi ô một số số hiệu quả cầu nào đó.

Bây giờ ta sẽ cố trả lời hai câu hỏi gắn bó chặt chẽ với nhau: làm thế nào tìm được một cách tìm hai quả cầu trong số $n$, gồm $k$ lần kiểm tra, nếu cách đó tồn tại; nếu nó không tồn tại, thì làm thế nào chứng minh điều đó?

Về nguyên tắc, với mọi $n$ và $k$ cụ thể, các câu hỏi này có thể giải bằng «liệt kê toàn bộ»: lần lượt thử mọi cách có thể điền vào các ô của sơ đồ tương ứng với $k$ lần kiểm tra bằng các tập con của $n$ quả cầu (vì số cách như vậy là hữu hạn!) và với mỗi cách ấy kiểm tra xem nó có cho phép xác định các quả cầu phóng xạ hay không (tức là liệu những giả thiết khác nhau về việc chính cặp quả cầu nào là phóng xạ có tương ứng với những đường đi khác nhau theo các mũi tên từ trên xuống dưới hay không). Nhưng số cách như vậy, ngay cả với $n$ và $k$ nhỏ, thật sự rất lớn, đến mức trên thực tế không thể thực hiện «liệt kê toàn bộ» ngay cả bằng máy tính (chẳng hạn, với $n=11$ và $k=7$ có thể điền các ô của sơ đồ bằng các nhóm quả cầu theo

⟦folio 35⟧

hơn $10^{400}$ cách khác nhau!). Bây giờ chúng tôi sẽ chỉ ra cách có thể rút gọn mạnh sự liệt kê này.

Hãy trở lại hình 1. Từ hàng ô thấp nhất, tương ứng với lần kiểm tra thứ năm, cuối cùng, đi ra $2^5=32$ mũi tên. Trong trường hợp tổng quát, với $k$ lần kiểm tra, sẽ có $2^k$ mũi tên. Nếu cách tìm kiếm được ghi trên sơ đồ bảo đảm xác định được các quả cầu phóng xạ, thì mỗi mũi tên này chỉ tương ứng với một trong các phương án trả lời có thể có: chính xác hai quả cầu nào là phóng xạ (nhưng có thể các mũi tên khác nhau tương ứng với cùng một phương án). Vì vậy số các phương án trả lời khác nhau có thể có không vượt quá số mũi tên, tức là không vượt quá $2^k$.

Hãy phát biểu kết luận cơ bản này như sau:

Nếu số các phương án có thể có lớn hơn $2^k$, thì không tồn tại cách nào cho phép trong $k$ lần kiểm tra xác định một trong các phương án ấy.

Điều đó cũng có thể nói như sau:

Nếu tồn tại cách cho phép trong $k$ lần kiểm tra xác định một phương án trong $N$ phương án có thể có, thì $N \leq 2^k$.

(Bất đẳng thức cuối cùng còn có thể viết như sau: $k \geq f_1(N)$.)

Tất nhiên, quy tắc này áp dụng được cho mọi bài toán cần xác định một phương án trong $N$ phương án dựa trên kết quả của vài lần kiểm tra; điều quan trọng chỉ là mỗi lần kiểm tra có hai kết quả có thể xảy ra: “có phóng xạ” và “không có phóng xạ”).

Đặc biệt, từ quy tắc này suy ra rằng không thể xác định một quả cầu phóng xạ duy nhất trong số $n$ quả với ít hơn $f_1(n)$ lần kiểm tra: nếu $f_1(n) = k$, thì $2^{k-1} < n$, còn số phương án khác nhau trong bài toán này là $n$ (quả cầu thứ 1 phóng xạ, quả cầu thứ 2 phóng xạ, ..., quả cầu thứ $n$ phóng xạ).

Hãy trở lại bài toán có hai quả cầu phóng xạ. Ở đây có bao nhiêu phương án khác nhau? Trên hình 1, nơi ta chọn 2 quả cầu trong số 7 quả, số phương án bằng 21. Trong trường hợp tổng quát, có $C_n^2 = \frac{n(n-1)}{2}$ phương án chọn 2 quả cầu trong số $n$ quả. Từ quy tắc cơ bản của chúng ta, được in phía trên trên nền hồng, suy ra rằng nếu có thể xác định 2 quả cầu trong số $n$ quả bằng $k$ lần kiểm tra, thì $\frac{n(n-1)}{2} \leq 2^k$.

Ta quy ước ký hiệu số lần kiểm tra nhỏ nhất cần thiết để xác định 2 quả cầu trong số $n$ quả là $f_2(n)$. Khi đó bất đẳng thức cuối cùng có thể viết như sau:

$$f_2(n) \geq f_1\left(\frac{n(n-1)}{2}\right).$$

Từ bảng thấy rằng với một số $n$ (chẳng hạn, với $n=6$, $n=8$) ở đây cũng có thể có bất đẳng thức chặt. Thật vậy, để sau $k$ lần kiểm tra có thể tìm được 2 quả cầu phóng xạ trong số $n$ quả, không đủ chỉ có bất đẳng thức $\frac{n(n-1)}{2} \leq 2^k$. Còn cần để số phương án mà ở đó lần kiểm tra thứ nhất phải cho kết quả “+” (có tính phóng xạ) không lớn hơn $2^{k-1}$ và số phương án mà ở đó nó phải cho kết quả “-” (không có tính phóng xạ) cũng không lớn hơn $2^{k-1}$, — bởi vì nếu không, theo quy tắc cơ bản, chúng ta sẽ không thể sau $k-1$ lần kiểm tra chọn ra một phương án trong số đó! Hoàn toàn tương tự, mỗi kết quả “++” (lần kiểm tra thứ 1 “+”, lần kiểm tra thứ 2 “+”), “+—”, “+—”, “—” phải tương ứng với không quá $2^{k-2}$ phương án, v.v.

Chúng tôi sẽ trở lại lời giải của bài toán này trong số báo tiếp theo.

A. N. Vilenkin

⟦folio 37⟧

Hình 3.

trong đó $n_{жс}$ — chiết suất của tia sáng khi chuyển từ chất lỏng sang thủy tinh.

Khi phản xạ toàn phần của ánh sáng tại mặt phân cách thủy tinh — chất lỏng, $\alpha = 90^\circ$, vì vậy $\sin \beta_0 = n_{жс}$, trong đó $\beta_0$ là góc tới của tia mà tại đó quan sát được phản xạ toàn phần. Tương tự, đối với phản xạ toàn phần của ánh sáng tại mặt phân cách thủy tinh — không khí, ta có thể viết $\sin \delta_0 = \frac{1}{n_c}$, trong đó $n_c$ là chiết suất của thủy tinh. Từ hai công thức này, xét rằng $n_{жс} = \frac{n_{жс}}{n_c}$, ta tìm được

$$n_{жc} = \frac{\sin \beta_0}{\sin \delta_0}.$$

Hình 4.

Bây giờ cần xác định chiết suất của tia sáng sao cho có thể quan sát nó chỉ bằng cách sử dụng phản xạ toàn phần tại mặt phân cách thủy tinh — chất lỏng. Để làm điều này, ta xác định góc $\beta_0$. Sau đó cũng xác định góc $\delta_0$. Sau đó việc tính chiết suất của tia sáng không khó. Việc tiến hành thí nghiệm được hỗ trợ bởi việc tia không bị khúc xạ tại mặt phân cách hình cầu giữa thủy tinh và không khí, vì nó tới vuông góc với bề mặt thủy tinh. Điều này cho phép dễ dàng xác định phương của tia tới mặt phân cách phẳng của bản.

F37

Trong hai hình trụ đặt thẳng đứng, có diện tích tiết diện $S_1$ và $S_2$, có hai pittông không trọng lượng, nối với nhau bằng một sợi chỉ mảnh không trọng lượng dài $l$ (hình 4). Không gian giữa các pittông được chứa đầy nước. Tìm lực căng của sợi chỉ nếu các đầu của bình thông với khí quyển. Khối lượng riêng của nước là $ρ$.

Nếu áp suất của chất lỏng lên pít-tông lớn (có diện tích $S_1$) bằng $p$, còn áp suất khí quyển là $p_0$, thì lên pít-tông tác dụng hướng lên lực áp suất $F_1 = S_1p$, còn hướng xuống — lực căng dây $T$ và lực áp suất khí quyển $F'_1 = p_0 \cdot S_1$. Vì pít-tông ở trạng thái cân bằng, nên

$$S_1p = S_1p_0 + T.$$

Tương tự, có thể lập phương trình cho pít-tông dưới: hướng lên tác dụng lên nó là lực căng dây $T$ và lực áp suất khí quyển $F'_2 = p_0S_2$, còn hướng xuống — lực áp suất của nước $F_1 = p'S_2$. Hơn nữa, áp suất $p'$ của nước lên pít-tông dưới lớn hơn áp suất lên pít-tông trên một lượng $\rho gl$. Vì pít-tông ở trạng thái cân bằng, nên

$$T + p_0S_2 = (p + \rho gl)S_2.$$

Giải đồng thời hai phương trình, ta tìm được

$$T = \rho gl \frac{S_1S_2}{S_1 - S_2}.$$

⟦folio 38⟧

Thông thường chúng ta kiểm tra đáp số bằng cách xét nó tại các giá trị giới hạn của các tham số. Ta sẽ cho rằng $S_2 \rightarrow S_1$. Trong trường hợp này $T \rightarrow \infty$. Điều đó cũng dễ hiểu. Toàn bộ hệ giữ được cân bằng nhờ áp suất của nước lên vòng có diện tích $S_1 - S_2$ trên pít-tông trên. Nếu $S_1 \rightarrow S_2$, thì áp suất lên vòng này phải tiến tới vô cực. Đồng thời lực căng của sợi dây cũng phải tiến tới vô cực.

Khi $S_1 = S_2$ ta sẽ nhận được rằng $T$ là vô cực. Tuy nhiên điều đó đã không đúng. Phép chuyển giới hạn như vậy là không thể. Khi giải bài toán, ta đã xuất phát từ giả thiết rằng hệ ở trạng thái cân bằng. Tuy nhiên khi $S_1 = S_2$ thì cân bằng là không thể và hệ pít-tông sẽ rơi nhanh dần đều với gia tốc rơi tự do $g$. Lực căng của sợi dây trong trường hợp này phải bằng không. Ví dụ này cho thấy cần thận trọng đến mức nào đối với các phép chuyển giới hạn trong vật lý. Cần theo dõi để hiện tượng khi đó không trở thành hoàn toàn khác.

Lời giải như vậy được gửi tới bởi N. Fedin ở Omsk, học sinh lớp mười M. Fedorov ở Moskva, A. Ratsozin ở Izhevsk.

Một lời giải thú vị được A. Zhukov ở Kirovsk, tỉnh Donetsk, đề xuất. Ông đã sử dụng phương pháp biến thiên ảo. Mặc dù việc trình bày phương pháp này đòi hỏi một bài báo riêng khá lớn, lời giải vẫn sẽ dễ hiểu.

Giả sử sợi dây ngắn đi $\Delta l$, trong đó pít-tông trên dịch chuyển một đoạn $\Delta l_1$, còn pít-tông dưới — một đoạn $\Delta l_2$. Vì thể tích nước giữa các pít-tông không thay đổi, nên cả hai pít-tông phải dịch chuyển theo cùng một chiều (đi xuống), sao cho

$$\Delta l_1 S_1 = \Delta l_2 S_2 \text{ và } \Delta l_2 - \Delta l_1 = \Delta l$$
($\Delta l_2 > \Delta l_1$).

Giải đồng thời các phương trình này, ta tìm được

$$\Delta l_1 = \Delta l \frac{S_2}{S_1 - S_2} \text{ và } \Delta l_2 = \Delta l \frac{S_1}{S_1 - S_2}.$$

Độ biến thiên thế năng của hệ khi thể tích nước $\rho S_1 \Delta l_1$ (hoặc $\rho S_2 \Delta l_2$) dịch chuyển một đoạn $l$ phải bằng công của lực căng sợi chỉ. Vì vậy ta có thể viết,

$$p + \Delta p = p + \rho gh,$$

⟦folio 39⟧

trong đó $h$ là hiệu độ cao của chất lỏng trong các nhánh (hình 5). Từ phương trình này ta tìm được $h = \frac{\Delta p}{\rho g}$. Ta thấy rằng $h$ không phụ thuộc vào tiết diện các nhánh của áp kế. Điều đó có nghĩa là độ chính xác của phép đo khi nối bình với nhánh rộng cũng như với nhánh hẹp là như nhau.

Lời giải đúng được gửi bởi A. Zhukov và những hồi ức của S. Pastmukhov từ Sverdlovsk.

Ф39

Một hành tinh bán kính $r$ và khối lượng $M$ được bao quanh bởi một khí quyển có mật độ đều, gồm một chất khí có trọng lượng phân tử $\mu$. Nhiệt độ khí quyển ở bề mặt hành tinh bằng bao nhiêu, nếu chiều cao khí quyển bằng $h$?

Viết phương trình trạng thái khí cho thể tích khí $V$ có khối lượng $m$ (phương trình Mendeleev — Clapeyron):

$$PV = \frac{m}{\mu} RT;$$

$P$ — áp suất, $V$ — thể tích khí, $R$ — hằng số khí và $T$ — nhiệt độ. Vì $\frac{m}{V} = \rho$, trong đó $\rho$ — khối lượng riêng của khí, nên phương trình này có thể viết lại dưới dạng $P = \frac{\rho}{\mu} RT$.

Từ đó $T = \frac{P\mu}{\rho R}$.

Rõ ràng, để tìm nhiệt độ trên bề mặt hành tinh, ta cần tìm áp suất trên bề mặt của nó. Nếu $\rho = \text{const}$, thì $P = \rho gh$, trong đó $g$ — gia tốc rơi tự do trên hành tinh đã cho. Hãy tìm nó.

Đối với một vật có khối lượng $m$, nằm trên bề mặt hành tinh, lực hấp dẫn bằng $mg$. Mặt khác, theo định luật vạn vật hấp dẫn, nó bằng $\gamma \frac{mM}{r^2}$. Vì vậy có thể viết rằng $mg = \gamma \frac{mM}{r^2}$.

Từ đó $g = \gamma \frac{M}{r^2}$ và $P = \rho \gamma \frac{M}{r^2} h$.

Thay biểu thức này của $P$ vào phương trình nhiệt độ, ta được

$$T = \frac{\gamma M\mu h}{r^2 R}.$$

Lời giải đúng của bài toán do V. Malkov ở Orsha và A. Proskuryakov ở Moskva gửi đến.

F40

Đèn neon cháy sáng ở hiệu điện thế nào giữa các điện cực, nếu năng lượng ion hóa của neon là $I = 21,5$ eV, còn khoảng cách trung bình giữa hai va chạm liên tiếp của electron với các nguyên tử khí bằng $l = 0,4$ mm? Các điện cực là những bản phẳng lớn, đặt cách nhau $d = 3$ mm.

Nếu hiệu điện thế giữa các điện cực là $U$, thì cường độ điện trường giữa chúng là $E = \frac{U}{d}$. Trong điện trường này, electron chịu tác dụng của lực $F = E \cdot e$ (e — điện tích của electron), lực này truyền cho nó gia tốc $a = \frac{F}{m} = \frac{Ee}{m} = \frac{Ue}{dm}$, trong đó $m$ — khối lượng electron.

Khi va chạm với nguyên tử khí, electron truyền năng lượng cho nó và dừng lại (ta coi va chạm là không đàn hồi). Khối lượng nguyên tử lớn hơn khối lượng electron. Vì vậy, khi va chạm, nguyên tử khí nhận năng lượng $\frac{mv^2}{2}$ mà electron thu được giữa hai va chạm liên tiếp của nó. Năng lượng này phải bằng năng lượng ion hóa của khí $I$:

$$\frac{mv^2}{2} = I.$$

Bây giờ ta hãy tìm vận tốc mà electron thu được. Nếu thời gian tăng tốc bằng $t$, thì ta có thể viết rằng $v = a\tau = \frac{Ue}{md} t$ và $l = \frac{a\tau^2}{2} = \frac{Ue\tau^2}{2md}$. Từ các phương trình này ta tìm được rằng

$$v = \sqrt{\frac{2Uel}{md}}.$$

Thay biểu thức này của $v$ vào phương trình (*), ta được

$$\frac{Uel}{d} = I.$$

Suy ra $U = \frac{Id}{el} \approx 160\theta$.
