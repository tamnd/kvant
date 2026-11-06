---
id: 1990-5-shevelev-latinskie-pryamougolniki-1f85e4c6
issue: kvant_1990_5
year: 1990
number: "5"
title: hình chữ nhật Latinh
authors:
  - Шевелёв В. С.
rubric: osnovnye-stati
page_first: 8
page_last: 11
page_labels: 6-9
lang: vi
source: kvant_digital
extraction: vision
content_sha256: 3bf037982d18ba6aab94515f860da1d99af76fd6f06bf43a0af6d5651df8d773
prompt_sha256: draft-1
translated_from: content/ru/1990/05/articles/03_shevelev-latinskie-pryamougolniki-1f85e4c6.md
source_content_sha256: 9acee75f390098ce2277ff9b03514dc3122dbf3ac5b7187dc05e819ab4835c81
translation_model: draft
translation_run: vi-draft-gaps-2026-11-05
translation_quality: draft
---

⟦folio 6⟧

---
running_head:
folio:
---

Ứng viên Khoa học Vật lý và Toán học
V. SHEVELEV

Bài viết này nói về cái gì?
Trong bài viết này chúng ta sẽ nói về các hình chữ nhật được “dân cư” bởi các số tự nhiên khác nhau. Nếu bạn chia một khối hình chữ nhật thành $m \times n$ các hình vuông bằng nhau bằng các đường thẳng, song song với các đáy của nó và “định cư” trong “ngôi nhà” $mn$-căn hộ $m$ tầng này với $n$ “lối vào” vào mỗi “căn hộ” một trong các số tự nhiên 1, 2, ..., $n$, sao cho tất cả các số trên mỗi “tầng” và trong mỗi “căn hộ” “lối vào” thì khác, khi đó chúng ta có một cuốn sách hình chữ nhật, mà các nhà toán học gọi là “tiếng Latin”. Trong đó, mỗi số 1, 2, ..., $n$ được lặp lại $m$ lần, tức là “gia đình” gồm một, hai, ba, v.v. chiếm $m$ “căn hộ”, nhưng luôn ở các “tầng” khác nhau và ở các “lối vào” khác nhau. Trước đây, các chữ cái trong bảng chữ cái Latinh đã được “truyền” vào “ngôi nhà” này cùng với các con số nên người ta gọi nó là “Latin”.

Có một môn toán liên quan đến việc đếm số lượng các tập hợp và cấu hình khác nhau. Khoa học này được gọi là tổ hợp.*) Bài toán việc liệt kê các trực tràng Latinh cũng đề cập đến tổ hợp

*) Bạn có thể đọc về nhiều bài toán tổ hợp thú vị trong cuốn sách tuyệt vời của N. Ya. Vilenkin “Khoa học tổ hợp phổ biến” (M., Nauka, 1975).

⟦folio 7⟧

---
running_head:
folio:
---

nhị phân. Tuy nhiên, nhìn chung bài toán này khó một cách bất thường. Mặc dù thực tế là nó đã được nghiên cứu bởi các nhà toán học vĩ đại nhất, nhưng phải hơn 200 năm trôi qua kể từ khi đếm số hình chữ nhật “hai tầng” và “ba tầng”, hình chữ nhật đầu tiên được liệt kê lần đầu tiên bởi người Pháp Montmortz vào năm 1713, và hình chữ nhật thứ hai được liệt kê bởi nhà toán học người Mỹ Riordan chỉ cách đây 40 năm. Ngoài các công thức rõ ràng màu đỏ của Montmore và Riordan mà chúng ta sẽ thảo luận dưới đây, các công thức truy hồi thuận tiện cũng được Euler tìm thấy cho các hình chữ nhật này (chúng ta sẽ chứng minh công thức của ông) và Keravala của Ấn Độ. Điều thú vị là Keravala đã bác bỏ các công thức hồi quy sai lầm của nhà toán học người Anh Jacob về số đường thẳng “ba tầng” Latinh “kéo dài” trong 12 năm (từ 1930 đến 1941). Chà, với lời giải khó bài toán điều này cũng xảy ra trong toán học!

Sự tồn tại của Rectogol Latin

Định lý 1. Với mọi số $m \leqslant n$ đều có hình chữ nhật $m \times n$ trong tiếng Latin.

Bằng chứng. Chúng tôi sẽ “cung cấp” “ngôi nhà” $m$ tầng của mình từ tầng trên cùng. Ở tầng $m$ chúng ta sẽ “sắp xếp” các số 1, 2, 3, ..., $n$ theo thứ tự tự nhiên. Ở tầng $(m-1)$ chúng tôi sẽ dạy “giải quyết” từ hai: 2, 3, ..., $n,1$; trên tầng $(m-2)$ - từ ba: 3, 4, ..., $n,1,2$, v.v.; cuối cùng, ở tầng 1 chúng ta sẽ dạy cách “giải quyết” từ số $m: m, m+1, ..., n,1,2,..., m-1$. Khi đó “ngôi nhà” sẽ được “dân cư” như cách thực hiện trong bảng. Rõ ràng là với sự “an cư” như vậy, không có hai “người thuê” giống hệt nhau trên cùng một “tầng” hoặc trong cùng một “lối vào”. Do đó, trước mắt chúng ta là một hình chữ nhật Latinh “m tầng” có chiều dài $n$. Điều này có nghĩa là tồn tại các hình chữ nhật $m \times n$.

Hai tầng

Bây giờ chúng ta chuyển sang đếm số hình chữ nhật Latin. bài toán đặc biệt dễ giải đối với các hình chữ nhật có giá trị đơn.

Định lý 2. Số hình chữ nhật Latin $1 \times n$ bằng $n! = 1 \cdot 2 \cdot ... \cdot n$.

Bằng chứng. Hình chữ nhật $1 \times n$ trong tiếng Latinh là một hoán vị tùy ý đơn giản của các số $n$. Chỉ có $n!$ hoán vị như vậy (bất kỳ số nào trong số $n$ được đặt ở vị trí đầu tiên, bất kỳ số nào trong số $n-1$ số còn lại được đặt ở vị trí thứ hai, bất kỳ số nào trong số $n-2$ số còn lại sau đó được đặt ở vị trí thứ ba, v.v.).

Hãy chuyển sang hình chữ nhật $2 \times n$. Dòng trên cùng của hình chữ nhật này là bất kỳ hoán vị nào. Dòng dưới cùng là một hoán vị trong đó mỗi vị trí có một số không bằng số ở cùng vị trí trong hoán vị đầu tiên. Nếu chúng ta tùy ý sắp xếp lại các cột của hình chữ nhật, nó sẽ vẫn là tiếng Latinh, đồng thời có thể thực hiện bất kỳ sự sắp xếp lại phía trên nào. Từ đó, rõ ràng là bất kể chúng ta thực hiện hoán vị cụ thể nào, số lượng hình chữ nhật Latinh có dòng trên cùng trùng với hoán vị cụ thể này sẽ giống nhau đối với tất cả các hoán vị. Giả sử rằng một hình chữ nhật Latinh $2 \times n$ được chuẩn hóa nếu dòng số trên cùng của nó chứa thứ tự: 1, 2, 3, ..., $n-1, n$. Từ những điều trên, có thể thấy rõ số lượng hình chữ nhật $L(2, n)$ Latinh $2 \times n$ bằng số $D_n$ của hình chữ nhật Latinh $2 \times n$ nhân với số hoán vị của số $n$, tức là.

$$L(2, n) = n! \cdot D_n.$$

Có một số công thức tinh tế cho số $D_n$ của hình chữ nhật Latin chuẩn hóa $2 \times n$.

Định lý 3. (Công thức Euler.) $D_n = (n-1)(D_{n-1} + D_{n-2})$.

Bàn

| 1 | 2 | 3 | ... | $n-1$ | $n$ |
| :--- | :--- | :--- | :--- | :--- | :--- |
| 2 | 3 | 4 | ... | $n$ | 1 |
| .. | .. | .. | .. | .. | .. |
| $m$ | $m+1$ | $m+2$ | ... | $m-2$ | $m-1$ |

⟦folio 8⟧

---
running_head:
folio:
---

như họ nói, một công thức truy hồi: nếu chúng ta biết $D_1$ và $D_2$, và rõ ràng là $D_1=0$ và $D_2=1$, thì chúng ta có thể sử dụng nó để tìm $D_n$ tiếp theo:

$$D_3=2 \cdot (1+0)=2,$$
$$D_4=3 \cdot (2+1)=9,$$
$$D_5=4 \cdot (9+2)=44,$$
$$D_6=5 \cdot (44+9)=265$$

vân vân.

Bằng chứng. Bất kỳ hoán vị nào cũng có thể được viết dưới dạng hệ thống các chu trình. Nó được thực hiện như thế này. Giả sử, $k_1$ ở vị trí số 1, chúng ta viết $1 \rightarrow k_1$. Nếu vị trí thứ $k_1$ là $k_2$, chúng ta viết $1 \rightarrow k_1 \rightarrow k_2$. Sau đó, $1 \rightarrow k_1 \rightarrow k_2 \rightarrow k_3$, v.v. cho đến khi chúng ta đạt được số lần nữa (hình 1). (Không thể xảy ra trường hợp trong chuỗi của chúng ta, một trong những số đã được chuyển sẽ xuất hiện sớm hơn một. Giả sử, nếu có... $\rightarrow k_9 \rightarrow k_{10} \rightarrow k_5$, thì $k_5$ nằm ở vị trí $k_{10}-m$ và ở vị trí $k_4-m$, có nghĩa là $k_{10}=k_4$, theo cách tương tự $k_9=k_3$, ..., $k_6=1$.) Sau đó, chúng ta lấy số nhỏ nhất số không có trong chu trình của chúng ta và xây dựng một chu trình bắt đầu từ nó. Cuối cùng, tất cả các số $n$ đều kết thúc theo chu kỳ (hình 2).

Số chu kỳ có thể là bất kỳ từ 1 đến $n$ và độ dài của chu kỳ có thể là bất kỳ từ 1 đến $n$. Điều kiện của chúng tôi - không có số nào ở vị trí của nó - cấm các chu kỳ có độ dài 1.

Bây giờ, bằng cách sử dụng hoán vị, chúng ta sẽ xây dựng một hoán vị có độ dài $n-1$ hoặc $n-2$ và cũng không có chu kỳ có độ dài 1. Hãy tìm số $n$ (hình 3) trên một trong các chu kỳ. Nếu độ dài của vòng lặp này lớn hơn hai, chúng ta sẽ chỉ cần loại bỏ $n$ và đoản mạch $p$ với $q$ (hình 4). Nếu $n$ là một phần của chu trình có độ dài 2, chẳng hạn như chu trình được hiển thị trong hình 5, thì chúng tôi chỉ cần loại bỏ chu trình này và giảm tất cả các số từ $k+1$ xuống $n-1$ một: $k+1 \rightarrow k$, $k+2 \rightarrow k+1$, ..., $n-1 \rightarrow n-2$. Trong trường hợp đầu tiên, bạn nhận được hoán vị của các số $n-1$, trong trường hợp thứ hai, hoán vị của các số $n-2$. Có bao nhiêu cách để chúng ta có được hoán vị của số $n-1$? Rõ ràng là có $n-1$ cách: để quay lại hoán vị có độ dài $n$, chúng ta phải bẻ gãy bất kỳ mũi tên $p \rightarrow q$ nào (và mũi tên của chúng là $n-1$) và đặt $n$ vào đó: $p \rightarrow n \rightarrow q$. Có bao nhiêu cách có thể đạt được hoán vị của số $n-2$? Một lần nữa theo $n-1$ cách: chúng ta thêm một chu trình $n \rightarrow k$, trong đó $k$ là bất kỳ số nào từ 1 đến $n-1$ và tăng các số $k$, $k+1$, ..., $n-2$ lên một. Có nghĩa,

$$D_n = (n-1)D_{n-1} + (n-1)D_{n-2},$$

đó là những gì được yêu cầu.

Và đây là một công thức hoán vị khác cho $D_n$, đơn giản hơn nhiều.

Định lý 4. $D_n=nD_{n-1}+(-1)^n$.

Bằng chứng. Hãy để $D_n=nD_{n-1}=E_n$. Từ công thức Euler $E_n=D_n-nD_{n-1}=(n-1)D_{n-1}+(n-1)D_{n-2}-nD_{n-1}=-D_{n-1}+(n-1)D_{n-2}=-E_{n-1}$. Có nghĩa,

$$E_n=-E_{n-1}=E_{n-2}=\dots=(-1)^nE_2.$$

Nhưng $E_2=1-2 \cdot 0=1$ có nghĩa là $E_n=(-1)^n$ và $D_n=nD_{n-1}+(-1)^n$.

Từ công thức cuối cùng, không có gì đứng vững được, không phải là một công thức lặp lại mà là một công thức rõ ràng cho $D_n$.

Định lý 5. (Công thức Monmore.)

$$D_n=n!\left(\frac{1}{2!}-\frac{1}{3!}+\frac{1}{4!}-\frac{1}{5!}+\dots+\frac{1}{n!}\right).$$

⟦folio 9⟧

---
running_head:
folio:
---

Bằng chứng.
$$D_n = nD_{n-1} + (-1)^n = n((n-1)D_{n-2} + (-1)^{n-1}) + (-1)^n = n(n-1)D_{n-2} + (-1)^{n-1}n + (-1)^n = n(n-1)(n-2)D_{n-3} + (-1)^{n-2}n(n-1) + (-1)^{n-1}n + (-1)^n = ... = n(n-1)(n-2) \cdots 3 \times D_2 - n(n-1) \cdots 4 + n(n-1) \cdots 5 - ... + (-1)^{n-1}n + (-1)^n = n! \left( \frac{1}{2!} - \frac{1}{3!} + ... \right) + (-1)^n \frac{1}{n!}.$$

Biểu thức cuối cùng trong ngoặc đơn có vẻ quen thuộc với những bạn đã học phần đầu về phân tích ở trường. Nó cũng có vẻ quen thuộc với chúng ta, nhưng chúng ta sẽ trì hoãn việc “xác định” nó cho đến phần cuối cùng của bài viết.

Còn bản thân công thức Montmore thì nó được chứng minh sớm hơn hai công thức trên. Bằng chứng trực tiếp của nó dựa trên công thức bao gồm-loại trừ; Những độc giả quen thuộc với công thức này sẽ suy ra công thức Montmore từ nó mà không gặp nhiều khó khăn, và chúng ta sẽ chuyển sang hình chữ nhật Latinh ba lớp.

Ba tầng

Những nỗ lực tìm kiếm số $L(3, n)$ của các hình chữ nhật $3 \times n$ trong tiếng Latinh đã kết thúc vào năm 1944, khi nhà toán học người Mỹ Riordan, dựa vào kết quả của một chuỗi dài những người tiền nhiệm, cuối cùng đã viết ra công thức cuối cùng. Chúng tôi không trình bày ở đây không chỉ cách rút ra công thức (vượt xa phạm vi chương trình giảng dạy ở trường) mà còn cả bản thân công thức, vốn cũng khá cồng kềnh. Chúng tôi sẽ giới hạn ở việc trình bày một công thức hồi quy, được gọi là công thức Keraval–Riordan: nếu $K_n = \frac{1}{n!}L(3, n)$, thì
$$K_n = n^2K_{n-1} + n(n-1)K_{n-2} + 2n(n-1)(n-2)K_{n-3} + (-1)^n(e_n + 2ne_{n-1}) (n \geqslant 4),$$
trong đó $e_n$ được tìm thấy từ công thức lặp lại của nó (gợi nhớ đến công thức cho $D_n$):
$$e_0 = 1, e_n = ne_{n-1} + (-2)^n.$$
Sử dụng các công thức này và thực tế là $K_1 = K_2 = 0, K_3 = 2$, chúng ta có thể tìm thấy $K_n$ cho tất cả $n$. Ví dụ,
$$K_5 = 552, \quad K_7 = 1073760;$$
Từ những đẳng thức này, rõ ràng là các con số $K_n$ đang tăng lên nhanh chóng; tất nhiên những con số $L(3, n)$ còn tăng nhanh hơn nữa.

công thức gần đúng

Biểu thức $\frac{1}{2!} - \frac{1}{3!} + ... + (-1)^n \frac{1}{n!}$ có vẻ quen thuộc với chúng ta vì nó giống với chuỗi lũy thừa của $e^x$:
$$e^x = 1 + x + \frac{x^2}{2!} + \frac{x^3}{3!} + ...$$

Đặc biệt,
$$\frac{1}{2!} - \frac{1}{3!} + ... + (-1)^n \frac{1}{n!} \approx 1 - 1 + \frac{1}{2!} - \frac{1}{3!} + ... = e^{-1},$$
Hơn nữa, sai số về giá trị tuyệt đối không vượt quá $\frac{1}{(n+1)!}$.

Có nghĩa,
$$D_n \approx n!e^{-1} = \frac{n!}{e},$$
và sai số không vượt quá $\frac{1}{n+1}$. (Vì $D_n$ là một số nguyên nên nó có thể được xây dựng lại một cách duy nhất từ ​​những dữ liệu này.) Tổng quát hóa công thức này, P. Erdős và I. Kaplansky vào năm 1946 đã thu được một

(Cuối cùng xem trang 25)
