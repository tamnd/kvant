---
id: 1978-11-zvonkin-chto-takoe-p-550a48bc
issue: kvant_1978_11
year: 1978
number: "11"
title: pi là gì?
authors:
  - Звонкин А. К.
rubric: po-stranitsam-shkolnyh-uchebnikov
rubric_sub: По страницам школьных учебников
page_first: 30
page_last: 32
page_labels: 28-30
tag: WWWW
lang: vi
source: kvant_digital
extraction: vision
content_sha256: 607aef86d91fe5bc4e4fb736d9fce11faaf5fb40637b16c6ce5d679abdc60a64
prompt_sha256: draft-1
translated_from: content/ru/1978/11/articles/12_zvonkin-chto-takoe-p-550a48bc.md
source_content_sha256: 2ce234aa08060ceba7e3b12d8dd85bdbc33951503b8778c40e4a7873b7f0dca0
translation_model: draft
translation_run: vi-draft-2026-10-31
translation_quality: draft
---

⟦folio 28⟧

A. Zvonkin

pi là gì?

Số π lần đầu tiên xuất hiện ở trường vào năm lớp 5 - trong sách giáo khoa “Matematika 5” (trang 59), nó được thảo luận trong sách giáo khoa “Hình học 8” (trang 118) và trong sách giáo khoa “Đại số và sự khởi đầu của phân tích 9” (trang 33). Tuy nhiên, không có bằng chứng nào về sự tồn tại của số π trong các sách giáo khoa này. Chúng tôi trình bày nó trong bài viết này.

Chiều dài của đoạn

Độ dài của một đoạn là khoảng cách giữa hai đầu của nó (“Hình học 6”, đoạn 7).

Trong thực tế, độ dài của các đoạn được đo bằng thiết bị đo - thước, thước dây, v.v. Phân tích lý thuyết của quá trình này dẫn đến một cấu trúc toán học gọi là quá trình đo và sóng xứng đáng có một thống kê riêng.

Nói tóm lại, quá trình đo lường như sau:

1) một đoạn tùy ý được chọn - một đơn vị chiều dài;
2) một đơn vị chiều dài được trì hoãn trong đoạn đo càng nhiều lần càng tốt;
3) nếu đồng thời phần còn lại của đoạn đo được thì đơn vị chiều dài được chia thành các phần bằng nhau và phần kết quả của đơn vị được gửi vào phần còn lại;
4) và vân vân.

Điều thú vị nhất ở đây nằm ở đoạn thứ tư. Hóa ra quá trình đo có thể kết thúc ở một số bước hữu hạn (trong trường hợp này, đoạn đo và đơn vị chiều dài được gọi là tương xứng) hoặc nó có thể tiếp tục vô thời hạn.

Do đó, ngay cả khi đo chiều dài của một đoạn, việc vượt qua giới hạn vẫn có thể xảy ra. Điều khá tự nhiên là chúng ta sẽ cần nó khi xác định chu vi. Trong trường hợp này, chúng ta sẽ giả định rằng chúng ta đã biết độ dài của một đoạn là bao nhiêu và do đó biết chu kỳ của một đa giác.

Người đọc có thể hỏi: Có thể đo chu vi của một hình tròn theo cách sau - quấn nó bằng sợi chỉ, sau đó cuộn sợi chỉ ra và gắn nó vào thước kẻ? Thật không may, việc biến phương pháp đo lường thực tế này thành một cấu trúc toán học chặt chẽ đòi hỏi những công cụ toán học khá phức tạp vượt ra ngoài phạm vi chương trình giảng dạy ở trường.

Định nghĩa xấu
đường tròn

Một định lý có thể đúng hoặc sai - một định nghĩa có thể không đúng hoặc sai. Một định nghĩa có thể chống lại bạn (nếu không có đối tượng nào thỏa mãn nó), sai (nếu nó không xác định được điều chúng ta mong muốn) và không thỏa mãn.

Bây giờ chúng tôi đưa ra một số định nghĩa về chu vi của một vòng tròn. Tất cả các định nghĩa sẽ được xây dựng theo cùng một sơ đồ: bằng cách này hay cách khác, một chuỗi (Πn) đa giác nội tiếp trong một đường tròn sẽ được chọn và độ dài của đường tròn sẽ được gọi là $L = \lim_{n \to \infty} P_n$, trong đó $P_n$ là chu vi của đa giác $\Pi_n$. Các định nghĩa sẽ khác nhau theo các lựa chọn khác nhau theo tuần tự ($\Pi_n$).

Trước tiên hãy đưa ra một số định nghĩa xấu.

“Trên giới hạn” 1. $L = \lim_{n \to \infty} P_n$, trong đó ($\Pi_n$) là sản phẩm

⟦folio 29⟧

Hình 1.

một dãy đa giác nội tiếp tự do.

Định nghĩa này không hề phù hợp chút nào. Ví dụ: nếu với tất cả $n$ thì đa giác $\Pi_n$ là cùng một hình vuông nội tiếp trong một hình tròn, thì $(P_n)$ là một dãy không đổi và theo chiều dài của hình tròn, chúng ta sẽ có chu vi của hình vuông nội tiếp. Nếu dãy $(\Pi_n)$ lần lượt chứa các hình vuông và hình tam giác đều thì dãy $(P_n)$ không có giới hạn (chứng minh!).

Chúng ta hãy biểu thị bằng $\varphi(n)$ số cạnh của đa giác $\Pi_n$ và bằng $\psi(n)$ độ dài cạnh dài nhất của nó.

《Định nghĩa》2. $L = \lim_{n \to \infty} P_n$, trong đó $(\Pi_n)$ là một chuỗi sao cho $\lim_{n \to \infty} \varphi(n) = +\infty$*).

Hóa ra định nghĩa này là phi oretic. Hình 1 cho thấy một chuỗi $(\Pi_n)$ thỏa mãn “định nghĩa” 2 và sao cho $\lim_{n \to \infty} P_n$ không phải là thứ mà chúng ta muốn coi là chu vi. Cũng không khó để xây dựng một ví dụ về dãy $(\Pi_n)$ thỏa mãn “định nghĩa”*

*) Tức là $\varphi(n)$ tiêu chuẩn càng lớn càng tốt.

Hình 2.

2, trong đó $\lim_{n \to \infty} P_n$ không tồn tại (hãy xây dựng nó!).

《Định nghĩa》3. $L = \lim_{n \to \infty} P_n$, trong đó $(\Pi_n)$ là một chuỗi sao cho $\lim_{n \to \infty} \varphi(n) = +\infty$ và $\lim_{n \to \infty} \psi(n) = 0$.

Thật không may, tùy chọn này cũng không phù hợp. Hình 2 thể hiện một chuỗi $(\Pi_n)$ thỏa mãn “định nghĩa” 3 và sao cho $\lim_{n \to \infty} P_n = 0$. Như trong “định nghĩa” 1, 2, thật dễ dàng để xây dựng một $(\Pi_n)$ sao cho $\lim_{n \to \infty} P_n$ không tồn tại.

Những định nghĩa hay
đường tròn

Định nghĩa 4. $L = \lim_{n \to \infty} P_n$, trong đó $(\Pi_n)$ là một dãy sao cho mọi $n$ tâm của đường tròn nằm bên trong $\Pi_n$ và $\lim_{n \to \infty} \varphi(n) = +\infty$, $\lim_{n \to \infty} \psi(n) = 0$.

Có thể chứng minh rằng với mọi $(\Pi_n)$ thỏa mãn “định nghĩa” 4, $\lim_{n \to \infty} P_n$ đều tồn tại và nó không phụ thuộc vào việc chọn chuỗi ban đầu $(\Pi_n)$. Tuy nhiên, điều này rất khó chứng minh. Do đó định nghĩa 4 là bất tiện. Ngoài ra, nó không rõ ràng: có rất nhiều yêu cầu không đồng nhất trong đó.

⟦folio 30⟧

Định nghĩa 5. $L = \lim_{n \to \infty} P_n$, trong đó $\Pi_n$ là một nội tiếp $n$-gon thông thường (xem “Đại số và sự khởi đầu của phân tích 9”, đoạn 33).

Không giống như định nghĩa 1-3, trong trường hợp này tồn tại giới hạn thực. Hãy chứng minh điều đó.

Định lý. Trình tự $(P_n)$ trả về và bị giới hạn.

Chúng ta sẽ chia chứng minh thành một số bước mà chúng ta sẽ trình bày dưới dạng bài toán. Với lời giải của chúng, điều quan trọng là không sử dụng phép đo lượng giác, vì định nghĩa của hàm lượng giác dựa trên khái niệm chu vi.

Nhiệm vụ 1.

1. Các tam giác vuông $ABC$ và $ADC$ có chung một hình vuông $AC$ và $BAC < DAC$. Chứng minh rằng $|AB| < |AD|$.

2. Đối với các tam giác vuông, $ABC$ và $A_1B_1C_1$ có các cạnh huyền $AB$ và $A_1B_1$ bằng nhau và $BAC < B_1A_1C_1$. Chứng minh rằng $|A_1C_1| < |AC|$.

3. Góc nhọn ở tâm $AOB$ được chia theo bán kính $OM_1, OM_2, \dots, OM_{k-1}$ thành $k$ phần bằng nhau (Hình 3). Điểm $C$ là hình chiếu của điểm $A$ lên $[OB]$, điểm $N_i$ là hình chiếu của điểm $M_i$ lên $[AC]$ ($i = 1, 2, \dots, k - 1$). Chứng minh rằng $|AN_1| < |N_1N_2| < \dots < |N_{k-1}C|$.

4. Chứng minh rằng $P_{n+1} > P_n$.

5. Chứng minh rằng nếu một đa giác lồi nằm bên trong một đa giác khác thì chu vi bên trong nhỏ hơn chu vi bên ngoài. Chứng minh rằng không có điều kiện lồi thì phát biểu này sai.

Vì vậy, dãy $(P_n)$ trả về (bài toán 4) và bị chặn (đối với bất kỳ $n$ nào, chu vi $P_n$ nhỏ hơn chu vi của hình vuông được mô tả - bài toán 5). Theo định lý Weierstrass*) nó có giới hạn. Điều này có nghĩa là Định nghĩa 5 đúng: mỗi vòng tròn có một độ dài (duy nhất).

số π

Chúng ta hãy biểu thị chiều dài của hình tròn bằng $L$, đường kính của nó bằng $d$, bán kính bằng $r$ và chiều dài cạnh của một hình tròn nội tiếp $n$-gon bằng $a_n$.

Định lý. Mối quan hệ $\frac{L}{d}$ giống nhau cho tất cả các vòng tròn.

Từ

$$\frac{L}{d} = \lim_{n \to \infty} \frac{P_n}{d} = \lim_{n \to \infty} \frac{na_n}{2r} = \frac{1}{2} \lim_{n \to \infty} \left( \frac{a_n}{r} \right),$$

chỉ cần chứng minh rằng hệ thức $\frac{a_n}{r}$ là như nhau cho tất cả các đường tròn và điều này xuất phát từ sự giống nhau của các tam giác được hiển thị trong Hình 4.

Chính tỷ lệ giữa chu vi và đường kính thường được biểu thị bằng chữ π trong tiếng Hy Lạp.

Chữ π là chữ cái đầu tiên của từ Hy Lạp περιphera (“vòng tròn”). Ký hiệu này lần đầu tiên được sử dụng vào năm 1706 bởi nhà toán học người Anh W. Jones, nhưng nó được chấp nhận rộng rãi sau khi L. Euler bắt đầu sử dụng nó một cách có hệ thống (bắt đầu từ năm 1736).

*) “Đại số và nguyên lý giải tích 9”, đoạn 32.

Hình 3.

Hình 4.
