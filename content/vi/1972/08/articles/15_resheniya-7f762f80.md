---
id: 1972-8-resheniya-7f762f80
issue: kvant_1972_8
year: 1972
number: "8"
title: Lời giải bài toán M110—M122; F131—F137
rubric: zadachnik-kvanta
rubric_sub: Задачник «Кванта»
page_first: 60
page_last: 74
page_labels: 58, 59, 61, 62, 64, 66, 68, 70, 71, 72
tag: RDDV
lang: vi
source: kvant_digital
extraction: vision
content_sha256: 9e8169bb133f350170b5adbcaca2cad241fe0a5321353046dc450d8cf68e5484
prompt_sha256: draft-1
translated_from: content/ru/1972/08/articles/15_resheniya-7f762f80.md
source_content_sha256: baea7641b9d379546019e4e799fc6c81519187c6e750e0ee62f8248ae4ea1ffa
translation_model: draft
translation_run: vi-draft-2026-10-31
translation_quality: draft
---

⟦folio 58⟧

Lời giải
Trong số này, chúng tôi xuất bản lời giải bài toán M110—M122

M110
Trên một tờ giấy ca-rô vô tận có N ô được sơn màu đen. Chứng minh rằng có thể cắt được một số hữu hạn các ô vuông từ một tờ giấy sao cho thỏa mãn hai điều kiện:
1) tất cả các ô màu đen sẽ nằm trong các ô vuông đã cắt ra;
2) trong bất kỳ hình vuông cắt K nào, diện tích các ô đen không nhỏ hơn 1/5 và không quá 4/5 diện tích của K.

Chúng tôi sẽ gọi các hình vuông được chấp nhận có bóng mờ không quá 4/5 và không nhỏ hơn 1/5. Hãy lấy n hình vuông 2x2 như vậy, mỗi hình vuông được tô màu nhỏ hơn 4/5. Những ô vuông chứa ít nhất một ô màu đen đã được tô bóng 1/4 và do đó có thể chấp nhận được. Các ô vuông 2x2 còn lại sẽ không chứa các ô được lấp đầy, do đó, tất cả các ô màu đen sẽ rơi vào các ô vuông hợp lệ và do đó cần phải có lớp phủ.

Bài toán có thể được khái quát hóa thành trường hợp ba chiều, với 1/5 và 4/5 được thay thế tương ứng bằng 1/9 và 8/9.

M111
Hình vuông ở cạnh 1 chứa một hình có khoảng cách giữa hai điểm bất kỳ không bằng 0,001. Chứng minh rằng diện tích của hình này không vượt quá 0,34.

Hãy cố gắng ước tính chính xác hơn và chứng minh một định lý tương tự trong không gian.

Chúng ta hãy biểu thị hình của chúng ta bằng F và S là diện tích của nó. Xét hình F₁ thu được bởi dwga F bằng 0,001 theo hướng song song với cạnh hình vuông. Hình F₂ là F dịch chuyển 0,001 theo hướng 2, tạo một góc 60° với hướng 1 (Hình 2, a). Hai hình F₁ và F không có điểm chung. Thật vậy, đặt điểm A thuộc F và đồng thời thuộc về F₁, nghĩa là, thu được bằng dwth của một điểm B nào đó của hình F bằng 0,001. Khi đó khoảng cách giữa A và B sẽ là 0,001,

⟦folio 59⟧

Hình 2.

trái với điều kiện bài toán. Tương tự, $F$ không giao nhau với $F_2$ và $F_1$ không giao nhau với $F_2$. Cả ba hình đang được xem xét đều có cùng diện tích $S$ và nằm trong hình vuông có cạnh 1,001. Do đó, bất đẳng thức $3S < 1,001^2$ đúng, do đó $S < 0,335$.

Ước tính này có thể được tinh chỉnh phần nào (ở vị trí thập phân thứ ba hoặc thứ tư) thông qua nghiên cứu chính xác hơn về phần của hình $F$ nằm gần ranh giới của hình vuông. Tuy nhiên, chúng tôi sẽ chứng minh ước tính tốt hơn đáng kể, cụ thể là $S < 0,287$.

Xét các hình $F_3$ và $F_4$ thu được từ $F$ với độ dịch chuyển 0,001 $\sqrt{3}$ theo hai hướng 3 và 4, tạo thành một cung gócsin $\left(\frac{1}{2\sqrt{3}}\right)$; $F_4$ có thể thu được từ $F_3$ với độ lệch 0,001, do đó $F_3$ và $F_4$ không giao nhau (Hình 2, b). Chúng ta hãy chọn từ những hình này một hình (ví dụ: $F_3$) có ít giao điểm hơn với $F$. Diện tích của giao lộ này không lớn hơn $S/2$ nên tổng diện tích chiếm giữ của $F$ và $F_3$ sẽ không nhỏ hơn $3S/2$. Bây giờ chúng ta hãy xây dựng các hình $F_5$ và $F_6$, dịch chuyển $F$ 0,001 theo hướng 5 và 6, tạo thành một góc $30^\circ$ với $3$ (Hình 2, c). Hình $F_3$ có thể thu được từ $F_5$ với độ dịch chuyển 0,001 theo hướng 6 và từ $F_6$ với độ dịch chuyển 0,001 theo hướng 5. Do đó, $F_5$ và $F_6$ không giao nhau với $F$; Chúng cũng không giao nhau. Do đó, diện tích chiếm giữ bởi $F$, $F_3$, $F_5$ và $F_6$ không nhỏ hơn $7S/2$. Tất cả những hình này phải được chứa trong một hình vuông ở cạnh $1 + 0,001\sqrt{3} < 1,0018$, vì vậy $S < \frac{2}{7}(1,0018)^2 < 0,287$. Ước tính này đã được chứng minh bởi A. Golberts (Moscow).

Câu hỏi liệu có ước tính nào tốt hơn đáng kể hay không vẫn còn bỏ ngỏ. Tất cả các ví dụ có thể được xây dựng đều có giá trị $S$ nhỏ hơn 0,25.

G. V. Rosenblom

M112

Bảng $m \times n$ chứa các số sao cho với hai hàng và hai cột bất kỳ, tổng các số ở hai đỉnh đối diện của tam giác tạo bởi nó bằng tổng các số ở hai đỉnh còn lại của nó. Xóa thường xuyên, nhưng những lần xóa còn lại có thể được khôi phục. Chứng minh rằng còn lại ít nhất $(n+m-1)$ số.

Đối với một nhà toán học, ý tưởng chứng minh của chúng ta có thể được phát biểu như sau. Các bảng thỏa mãn điều kiện bài toán tạo thành một không gian tuyến tính có chiều $n+m-1$. Mặt khác, nếu các số trong một số ô s xác định duy nhất bảng, thì kích thước của “không gian bảng” không vượt quá s, vì vậy $s \geq n+m-1$.

Bây giờ chúng ta chuyển sang trình bày chi tiết chứng minh. Điều kiện đặt tên cho các số trong bảng, các phần tử của nó. Chúng ta sẽ biểu thị bằng $a_{ij}$ phần tử bảng $A$ nằm ở giao điểm của hàng thứ i và cột thứ j.

Đương nhiên, tổng của bảng và phép nhân của bảng với số được xác định.

Phép cộng hai bảng $A$ và $B$ với các phần tử $a_{ij}$ và $b_{ij}$ thì tổng của chúng $C = A+B$ được gọi là bảng có các phần tử $c_{ij} = a_{ij}+b_{ij}$.

Nhân một bảng với một số. Nếu chúng ta được cung cấp một bảng $A$ có các phần tử $a_{ij}$ thì bảng $\lambda A$ là bảng $B$ có các phần tử $b_{ij} = \lambda a_{ij}$.

Dễ dàng kiểm tra xem nếu các bảng thỏa mãn điều kiện bài toán được cộng với nhau và nhân với các số thì chúng ta lại thu được các bảng thỏa mãn điều kiện bài toán. Vì tất cả các lần gặp trong bảng đều thỏa mãn điều kiện bài toán nên chúng tôi không chỉ định thêm điều này.

Bây giờ chúng ta giới thiệu khái niệm rất quan trọng của sự phụ thuộc tuyến tính. Chúng ta hãy tạo một bảng bao gồm các phụ thuộc tuyến tính nếu có thể chỉ ra các số $\lambda_1, \lambda_2, \dots, \lambda_r$ như vậy, không phải tất cả các số đó đều bằng 0, mà bảng $\lambda_1A_1 + \lambda_2A_2 + \dots + \lambda_rA_r$ bằng 0.

(Ví dụ: nếu trong số các bảng $A_1, A_2, \dots, A_r$ có hai bảng giống hệt nhau ($a_{ij} = a_{jj}$), thì tập hợp các số $\lambda_1, \lambda_2, \dots, \lambda_r$ đó có thể được biểu thị: $\lambda_i = 1$, $\lambda_j = -1$ và tất cả các bảng còn lại đều bằng 0.) Nếu đối với bảng $A_1, A_2, \dots, A_r$ những số như vậy $\lambda_1, \lambda_2, \dots, \lambda_r$ không tồn tại thì chúng được gọi là độc lập tuyến tính.

Chúng tôi thách thức người đọc chứng minh rằng từ bất kỳ tập hợp bảng $B_1, B_2, \dots, B_s$ nào, không phải tất cả đều bằng 0, người ta có thể chọn một tập hợp độc lập tuyến tính cực đại $B_{l_1}, B_{l_2}, \dots, B_{l_r}$, tức là một tập hợp sao cho nếu một tập hợp cực đại khác $B_{j_1}, B_{j_2}, \dots, B_{j_r}$ được chỉ định thì $r = t$.

Bây giờ chúng ta hãy quay lại bài toán của chúng ta. Giả sử còn lại s số chưa bị xóa và bảng có thể được xây dựng lại từ chúng một cách duy nhất. Hãy để chúng tôi chứng minh rằng chỉ có bảng số 0 mới có số 0 trong các ô s của chúng tôi (trong những ô mà số không bị xóa). Thật vậy, nếu chúng tôi tìm thấy một bảng khác 0 $B$, có các số 0 trong các ô s của chúng tôi, thì có thể khôi phục không chỉ một số bảng $A$ mà còn cả các bảng $A + \lambda B$, trong đó $\lambda$ -

⟦folio 61⟧

Hình 4.

thì sau khi sắp xếp lại tổng (1) sẽ tăng lên. Thật vậy, nếu $x_i$ và $x_{i+1}$ có thể được sắp xếp lại thì $(x_{i-1}-x_{i+2})(x_i-x_{i+1})<0$, và bất đẳng thức này có thể được viết như sau: $x_{i-1}x_i+x_{i+1}x_{i+2}<x_{i-1}x_{i+1}+x_{i+1}x_i+x_{i+2}$.

Nhưng tổng cộng có một số hữu hạn các hoán vị có thể có của các số $x_1, x_2, \dots, x_n$ xung quanh đường tròn, do đó tổng (1) chỉ có thể nhận một số hữu hạn các giá trị. Do đó, thao tác của chúng ta chỉ có thể được thực hiện với số lần hữu hạn: nếu không, chúng ta sẽ nhận được một chuỗi vô hạn các giá trị khác nhau cho tổng (1) $s_1<s_2<s_3<\dots$.

M115

Có tổng số lít nước được đổ vào ba bình. Nó được phép đổ vào bất kỳ bình nào nhiều nước như nó đã chứa từ bất kỳ bình nào khác. Chứng minh rằng một số lần truyền máu như vậy có thể giải phóng một mạch máu. (Các bình đủ lớn: mọi người có thể cùng nhau gánh hết nước.)

Đặt $a$ lít nước trong bình thứ nhất, $b$ lít trong bình thứ hai, $c$ lít trong bình thứ ba và $a \leq b \leq c$ lít.

Trước tiên chúng ta hãy xem xét trường hợp khi $a=1$. Nếu bạn chỉ thêm nước vào bình đầu tiên, thì với lần truyền đầu tiên, bạn sẽ cần thêm 1 lít nước, với bình thứ hai - hai lít, với bình thứ ba - bốn lít, nói chung với lần truyền thứ $i$ - $2^{i-1}$ lít.

Tất nhiên, bây giờ chúng ta hãy chia số nước trong bình thứ hai một cách có điều kiện thành các phần: $2^{i_0}, 2^{i_1}, \dots, 2^{i_k}$, trong đó $i_0 < i_1 < \dots < i_{k-1} < i_k$. (Để làm điều này, chúng tôi tìm $i_k$ sao cho $2^{i_k} \leq b$ và $2^{i_k+1} > b$, sau đó $b=2^{i_k}+b_1$, trong đó $b_1 < 2^{i_k}$; đối với nó, chúng tôi tìm thấy $2^{i_k-1}$, v.v.)

Nếu $i_0=0, i_1=1, i_2=2, \dots, i_k=k$ thì chúng ta sẽ không cần bình thứ ba. Hãy bắt đầu đổ từ bình thứ hai sang bình thứ nhất. Sau lần truyền đầu tiên, sẽ có hai lít trong bình thứ nhất, và $2+2^2+2^3+\dots+2^k$ lít trong bình thứ hai, sau lần truyền thứ hai sẽ có $2^2$ và $2^2+2^3+\dots+2^k$, sau bình thứ ba - $2^3$ và $2^3+ \dots+2^k$, sau $k$ - $2^k$ và $2^k$ và sau $k+1$ - $2^{k+1}$ và 0.

Nếu một số lũy thừa của hai, nhỏ hơn $2^{i_k}$, bị thiếu trong “các phần”, thì chúng tôi sẽ đánh dấu các phần không đủ trong bình thứ ba (có đủ nước trong đó cho việc này; thực sự, chúng tôi có đủ $1+2+2^2+ \dots+2^{i_k-1}=2^{i_k}-1$ lít nước, số này nhỏ hơn $b$ lít và $b$ lần lượt nhỏ hơn $c$).

Bây giờ chúng ta sẽ đổ nó như thế này: mỗi lần chúng ta sẽ sử dụng một chiếc bình nhỏ đựng phần tương ứng. Sau khi truyền $i_k+1$, bình thứ hai sẽ trống.

Trường hợp tổng quát ($a \neq 1$) thực ra không có gì phức tạp hơn. Hãy biểu thị $b$ và $c$ như sau: $b=b_1a+b_2$, $c=c_1a+c_2$, trong đó $b_1, b_2, c_1, c_2$ là các số tự nhiên và $b_2<a, c_2<a$ (cách biểu diễn như vậy là duy nhất). Nếu bây giờ chúng ta quên "thêm" $b_2$ và $c_2$ lít, và khai báo $a$ lít là một đơn vị thể tích mới, thì kể từ $b_1 \leq c_1$, chúng ta có thể sắp xếp truyền máu để đổ $b_1$ lít từ bình thứ hai. Sau đó, sẽ còn lại $b_2$ lít trong đó, với số nguyên $b_2$ nhỏ hơn $a$. Vì vậy, chúng tôi đã cố gắng chuyển từ bình có $a \leq b \leq c$ lít nước sang bình có $a' \leq b' \leq c'$. lít nước, và $a>a'$. Bằng cách lặp lại quy trình của chúng tôi, chúng tôi sẽ lần lượt thu được các bình chứa ngày càng ít nước: $a>a'>a'' \dots$. Vì một trong các dãy là số nguyên lít nên sau hữu hạn bước chúng ta sẽ thu được một bình rỗng.

Lưu ý rằng bài toán này lần đầu tiên xuất hiện trong một trong những tác phẩm của nhà đại số nổi tiếng Liên Xô A. I. Shirshov. Anh ấy cần nó để xây dựng lý thuyết toán học phía máy chủ. Nhân tiện, đây không phải là đề xuất tối ưu hóa duy nhất bài toán, được lấy từ một loạt các công trình toán học phía máy chủ.

L. G. Limanov

M116

Chứng minh rằng nếu bạn nối trung điểm của các cạnh liên tiếp của một lồi $n$-gon $M$ (Hình 5), thì đa giác thu được

⟦folio 62⟧

a) chu vi không nhỏ hơn một nửa chu vi $M$ ($n \geqslant 3$);
b) diện tích không nhỏ hơn một nửa diện tích $M$ ($n \geqslant 4$).

Đặt $A_1 A_2 \dots A_n$ là đa giác đã cho $M$, $B_k$ trung điểm của cạnh $A_{k-1} A_k$ (ở đây và bên dưới $k=1, 2, \dots, n$, và giả sử rằng $A_{n+1}=A_1$, $A_0=A_n$, v.v.), $S$ và $S'$ các diện tích, $P$ và $P'$ lần lượt là chu vi của đa giác $A_1 A_2 \dots A_n$ và $B_1 B_2 \dots B_n$; $n \geqslant 4$.

Lưu ý rằng đường chéo $A_{k-1} A_k+1$ cắt hình tam giác $A_{k-1} A_k A_{k+1}$ khỏi đa giác, trong đó $B_k B_{k+1}$ là đường giữa (Hình 6), do đó
a) $A_{k-1} A_{k+1}=2B_k B_{k+1}$;
b) $S(\Delta A_{k-1} A_k A_{k+1})=4S(\Delta B_k A_k B_{k+1})$.
(Các mối quan hệ này đóng vai trò chính trong hầu hết các lời giải do độc giả gửi.) Rõ ràng là trong tất cả các đường chéo $A_{j-1} A_{j+1}$ (trong đó $j=1, 2, \dots, n$; $j \neq k$) một tam giác đã cho $A_{k-1} A_k A_{k+1}$ chỉ giao nhau với hai: $A_{k-2} A_k$ và $A_k A_{k+2}$, và các điểm giao nhau tương ứng $C_k$, $C_{k+1}$ trong số các đường chéo có $A_{k-1} A_{k+1}$ này được sắp xếp theo thứ tự sao cho các đoạn $A_{k-1} C_k$ và $C_{k+1} A_{k+1}$ (và do đó, các hình tam giác $A_{k-1} A_k C_k$ và $C_{k+1} A_k A_{k+1}$) không chồng lên nhau. Bây giờ phát biểu bài toán được chứng minh như sau (tổng $\Sigma$ được lấy trên tất cả $k$):
a) $2P'=2\Sigma B_k B_{k+1}=\Sigma A_{k-1} A_{k+1} > \Sigma A_{k-1} C_k + \Sigma C_{k+1} A_{k+1} =$
(các đoạn màu xanh lam trong Hình 7)
$= \Sigma (A_{k-1} C_k + C_k A_k) > \Sigma A_{k-1} A_k = P$
(bất đẳng thức tam giác cho $\Delta C_k A_{k-1} A_k$), từ đó $P' > P/2$;
b) $4(S-S')=4\Sigma S(\Delta B_k A_k B_{k+1}) = \Sigma S(\Delta A_{k-1} A_k A_{k+1}) \leqslant 2S$ (vì hình tam giác $A_{k-1} A_k A_{k+1}$ bỏ qua đa giác có nhiều hơn hai lớp), từ đó $S' \geqslant S/2$; sự bình đẳng ở đây chỉ đạt được với $n=4$ (trong trường hợp a) - chỉ với $n=3$).

Đúng lời giải giữa bài toán và a), và b) - được thêm bởi A. Merkuryev và A. Kolobsky từ Leningrad, M. Rozov và A. Chernaya từ Minsk, M. Illarina, A. Glushko và B. Korenyako từ Voronezh, B. Shikhman, I. Shparlinsky và M. Kolodochki từ Moscow, B. Khafizov từ làng. Saby giàu có của Cộng hòa xã hội chủ nghĩa Xô viết tự trị Tatar, E. Turkevich từ Chernivtsi, L. Pugach và S. Lyagushiin từ Dnepropetrovsk, A. Tsanava từ Tbilisi, A. Ryabkin từ thành phố Rechitsa, vùng Gomel, A. Gordienko từ làng. Lãnh thổ Poltavensky Krasnoarsk, A. Smirnov từ Gorky, V. Maltsenko từ Slavyansk ở Kuban, N. Chernov từ Krivoy Rog, A. Makriev từ Lvov, A. Zhumadildaev từ Alma-Ata, S. Malevakin từ Fedosin, G. Filkovsky từ Baku, V. Chukhin từ Volsk, Cộng hòa xã hội chủ nghĩa Xô viết tự trị Mari, Yu. Kisin từ St. Người Nga.

Do đó, người ta đã chứng minh rằng tỷ lệ $P'/P$ và $S'/S$ (tương ứng với $n \geqslant 3$ và $n \geqslant 4$) nằm trong khoảng từ 1/2 đến 1. Một câu hỏi tự nhiên được đặt ra - cuộc thảo luận về nó không phải là

⟦folio 64⟧

Hình 9.

số quan sát lẻ nhỏ hơn một thì số lượng quan sát lẻ phải lớn hơn $\left(\frac{t}{2}\right)$. Điều này có nghĩa là con ốc sên không thể bò theo con đường đang thay đổi $\left(\frac{t}{2}\right) + 1$. Đây là đáp số cho câu hỏi thứ hai bài toán. Biểu đồ (xem Hình 9) cho thấy con ốc phải di chuyển như thế nào để đạt được mức tối thiểu này.

Nhiệm vụ a. Bây giờ hãy cố gắng hình thành chính xác bổ đề được đề cập trong đoạn đầu tiên của lời giải của chúng ta.

N. N. Konstantinov

M118

Trên bốn mặt của bàn cờ có kích thước $n \times n$ có đường viền rộng hai ô.

Chứng minh rằng quân cờ có thể vượt qua ranh giới này bằng cách nâng mỗi ô một lần và chỉ một lần, khi và chỉ khi $n-1$ là bội số của 4.

Đối với lời giải bài toán, chỉ cần chứng minh rằng đường viền bốn cạnh có chiều rộng 2 có thể bị hiệp sĩ vượt qua đối với $n=4t+1$, nhưng không thể vượt qua đối với $n \neq 4t+1$.

Hình 10. Trường nào ở đây được kết nối bằng các đoạn màu đen với các trường mà bạn có thể lấy được từ đó bằng một nước đi của hiệp sĩ. Đường màu đỏ là đường có đầu A và B, đi qua tất cả các trường một lần. [Lưu ý rằng nếu cùng với đoạn $A_1B_1$ chúng ta bao gồm các đoạn $AA_1$ và $BB_1$ trong đường dẫn thì nó sẽ chia thành hai đường dẫn khép kín].

Hình 12. Các khối được chèn sẽ được đánh dấu bằng màu sắc của nó.

cứng $A_1, A_2, \dots, A_k$, chứa m trường và

1) các tập hợp con này không có trường chung;
2) từ bất kỳ trường nào của tập hợp con $A_i$ hiệp sĩ không thể đi đến bất kỳ trường nào của tập hợp con $A_j$ tại $i \neq j$;
3) $g - m < k - 1$, thì hiệp sĩ không thể bỏ qua vùng G.

Bằng chứng của bổ đề được đánh giá đầy đủ. Thật vậy, nếu hiệp sĩ có thể đi vòng quanh toàn bộ vùng G thì đường đi của hiệp sĩ phải đi qua tất cả k tập con. Hơn nữa, do điều kiện 2) của bổ đề nên khi chuyển từ tập con này sang tập con khác, hiệp sĩ sẽ phải tăng ít nhất k-1 lần ngoài các tập con nhưng ở ngoài các tập con theo điều kiện.

⟦folio none⟧

Hình 13. Các ô màu là tập hợp con của $A_1$. Tất cả các ô khác là $A_2$.

3) Bổ đề không có số trường như vậy. Bổ đề đã được chứng minh.

Hãy xem xét ba trường hợp: 1) $n=4t$; 2) $n=4t+2$ và 3) $n=4t+3$.

Hãy bắt đầu với trường hợp 3 dễ hơn), khi $n=4t+3$. Hãy chia toàn bộ đường viền thành hai tập hợp con $A_1$ và $A_2$ như trong Hình 13. (Ở đây $t=0$; để có được mẫu với các tập hợp con $t$ khác, bạn cần để lại các khối như trong Hình 11.)

Dễ dàng nhận thấy rằng không thể chuyển từ tập con $A_1$ sang tập con $A_2$ bằng cách di chuyển quân mã. Do đó, chúng ta có thể áp dụng Bổ đề ($k=2$, $m=g$).

Trong hai trường hợp còn lại $n=4t$ và $n=4t+2$, khó khăn chính là việc mô tả các trường sẽ không có trong bất kỳ tập hợp con nào. Chúng tôi sẽ gọi họ là trung lập.

Trường hợp 1) ($n=4t$). Đối với $t>0$, chúng tôi khai báo các trường trung lập có một mặt chung với các trường góc của bảng có viền. (Trong Hình 14 chúng được đặt bằng chữ Z.) Sẽ có 8 trong số chúng. Sẽ có 10 tập hợp con trong số chúng - chúng được xác định như sau: chúng tôi lấy một trường trống và tất cả những trường mà bạn có thể “vượt qua” từ đó bằng một hiệp sĩ mà không cần sử dụng các ô trung tính. Tất cả các trường này tạo thành một tập hợp con. Để có được bản vẽ từ Hình 14 cho bất kỳ $t>0$ nào, bạn cần để lại các khối như trong Hình 11. Đối với $t=0$ các trường trung tính và các tập hợp con được hiển thị trong Hình 15.

Trường hợp 2) ($n=4t+2$) được phân tích theo cách tương tự. Ở đây, tại $t>0$, số trường trung tính là 12 và số tập hợp con là 14. Cách chọn trường trung tính tại $t>0$ và tại $t=0$ có thể xem trong Hình 16 và 17.

Bài toán M118 là một trường hợp đặc biệt của điều này bài toán: cho một “đồ thị” (một hệ thống các “đỉnh”, một số trong đó được “kết nối bởi các cạnh”), bạn cần tìm một đường đi xung quanh các đường xù lông cùng một lúc - cái gọi là “đường Miltonian”.

Lưu ý rằng trong trường hợp chung, bài toán này chưa được giải quyết - không tìm thấy thuật toán đơn giản nào cho phép người ta xây dựng đường dẫn Hamilton cho một đồ thị tùy ý và thậm chí tìm ra

⟦folio 66⟧

cách như vậy có tồn tại không? Tương tự như vậy bài toán - tìm đường đi, đi dọc theo tất cả các cạnh một lần - đơn giản hơn nhiều.

Yu. Yu. Sorkin

M119

Chứng minh rằng nếu chọn một điểm trên mỗi mặt của khối đa diện lồi và từ điểm này vẽ một vectơ hướng vuông góc với mặt tương ứng ra phía ngoài và có chiều dài bằng diện tích của mặt này thì tổng các vectơ đó sẽ bằng 0.

Xác minh và có thể thu được bằng chứng ngắn từ thông tin liên lạc vật lý. Hãy tưởng tượng rằng một bình kín, khoang bên trong có hình đa diện của chúng ta, chứa đầy khí dưới áp suất $P$ và được đặt trong khoảng trống (không có ngoại lực - trọng lượng, v.v.). Khi đó lực áp suất khí tác dụng lên mặt của diện tích $S$ bằng $PS$ và hướng vuông góc mặt này với mặt ngoài (như người ta nói ngắn gọn là “dọc theo pháp tuyến bên ngoài” với mặt). Tất nhiên, chúng ta có thể lấy $P$ bằng 1; khi đó các lực tác dụng lên cạnh sẽ bằng các vectơ đã thảo luận ở điều kiện bài toán. Vì tàu không thể chuyển động bằng gia tốc chỉ dưới tác dụng của nội lực nên tổng vectơ của các lực này, tức là tổng vectơ của chúng ta, bằng 0.

Chúng tôi cũng trình bày một số chứng minh toán học. (Ở đây chúng ta sẽ không thảo luận chi tiết câu hỏi thú vị về mức độ mà lý luận trên có thể được coi là một “chứng minh chặt chẽ”. Chúng ta hãy lưu ý rằng tất cả các khái niệm và định luật vật lý được sử dụng trong đó có thể được đưa vào trong khuôn khổ của một lý thuyết “suy diễn” toán học chặt chẽ: các khái niệm sẽ nhận được định nghĩa chính xác, các định luật sẽ nhận được cấu trúc chứng minh và dữ liệu thực nghiệm sẽ được coi là sự xác nhận tính hữu ích của các định nghĩa và định lý; nhưng trong trường học - và không chỉ trong một khóa học vật lý ở trường, cách tiếp cận như vậy không phổ biến lắm. Hơn nữa, để thực hiện việc “chính thức hóa” khóa học vật lý như vậy, khóa học toán ở trường rõ ràng là chưa đủ. lời giải của chúng tôi bài toán Toán học ở trường là khá đủ.)

Chúng ta sẽ cần bổ đề sau (chúng tôi đưa ra bằng chứng ở cuối lời giải): nếu một đa giác có diện tích $S$ và mặt phẳng của nó tạo thành một góc $α$ ($0° < α < 90°$) với một mặt phẳng nào đó $π$, thì diện tích hình chiếu của đa giác này lên mặt phẳng $π$ bằng $S \cos α$.

Chúng ta lấy một trục tùy ý (đường thẳng có hướng) $l$ và một mặt phẳng $π$ vuông góc với nó. Chiếu tất cả các mặt của đa giác của chúng ta lên mặt phẳng $π$ và các vectơ tương ứng của chúng lên trục $l$. Nếu diện tích của một trong các mặt là $S$ và góc tạo bởi “bình thường ngoài” của nó với trục là $l$,

Hình 18. a) mặt trên: $0 \leqslant α \leqslant 90°$; b) các cạnh dưới: $90° < α \leqslant 180°$.

bằng $α$ thì hình chiếu của vectơ lên ​​trục $l$ bằng (có tính đến dấu) $S \cos α$ và diện tích hình chiếu của mặt lên mặt phẳng $π$ bằng $|S \cos α|$. Chúng tôi viết ký hiệu mô hình vì góc $α$ có thể không chỉ nhọn (Hình 18a; các mặt mà chúng tôi gọi là $α \geqslant 0$ phía trên) mà còn có thể là góc tù (Hình 18b; các mặt mà chúng tôi gọi là $α < 0$ thấp hơn).

Bây giờ chúng ta hãy xem xét đa giác mà đa giác của chúng ta được chiếu (trên mặt phẳng $π$). Đa giác này, như có thể thấy từ Hình 18a và 186, có thể được tạo từ các hình chiếu của tất cả các mặt trên hoặc từ các hình chiếu của tất cả các mặt dưới. (Ở đây lợi dụng tính chất là đa giác lồi nên trên mỗi đường thẳng song song với $l$ và giao nhau với đa giác có một điểm thuộc các cạnh trên và một điểm thuộc các cạnh dưới). Do đó, nếu chúng ta tách các số trung bình $S \cos α$ dương và âm thì tổng của cả hai theo mô hình sẽ bằng nhau. Do đó, tổng của tất cả các số $S \cos α$ tương ứng với các cạnh khác nhau đều bằng 0. Vì vậy, tổng các hình chiếu của vectơ của chúng ta

⟦folio 68⟧

nhóm lớn $A$, thì trung bình số học của tất cả các số đều lớn $A$ (thực sự, nếu tổng các số trong nhóm đầu tiên lớn $(n - n_1) A$, trong nhóm thứ hai - lớn $(n_1 - n_2) A$ ..., ở nhóm cuối cùng - lớn $n_r A$, thì tổng của tất cả các số lớn $n_A$). Nhưng bằng $A$ chúng ta chỉ biểu thị mức trung bình của tất cả các số $n$. Mâu thuẫn thu được chứng tỏ giả định của chúng ta là sai.

Nhiều độc giả của chúng tôi nghĩ khác. Ví dụ: sẽ rất hữu ích khi trừ giá trị $A$ (trung bình số học của chúng) từ mỗi số đã cho. Khi đó bài toán sẽ rút gọn về trường hợp đặc biệt khi trung bình số học của tất cả các số đều bằng 0. Sau đó, bạn có thể loại bỏ mẫu số và không nói về giá trị trung bình mà nói về tổng các số và dấu của chúng, và bài toán được đặt như một hệ quả đơn giản của điều này bài toán: nếu một số số được viết xung quanh một vòng tròn, tổng của chúng bằng 0, thì có một số sao cho bản thân nó không âm, tổng của nó với số tiếp theo theo chiều kim đồng hồ là không âm, tổng của nó với hai số tiếp theo là không âm, v.v. $n$ số. bài toán này (ở một công thức hơi khác) đã được thảo luận trong «Kvant» (xem «Kvant» Số 1, 1972, trang 42, lời giải bài toán M82).

M122

Ngũ giác ABCDE nội tiếp trong một đường tròn. Được biết, khoảng cách từ điểm $E$ đến các đường $AB, BC, CD$ lần lượt bằng $p, q, r$. Tìm khoảng cách từ điểm $E$ đến đường thẳng $AD$.

Nếu cho một đường tròn và có hai điểm $P$ và $Q$ trên đó, thì bằng $s$ ($PQ$), chúng ta sẽ biểu thị góc sin chắn bởi cung $PQ$ (vì $\sin \alpha = \sin (180^\circ - \alpha)$ không phụ thuộc vào cung nào trong hai cung mà điểm $M$ nằm).

Chúng tôi đi qua hai sự thật sau đây.

1°. Đặt $PQ$ là dây cung của đường tròn bán kính $R$. Sau đó $PQ = 2Rs$ ($PQ$).

2°. Nếu $P, Q$ và $E$ là ba điểm khác nhau trên đường tròn bán kính $R$ thì khoảng cách từ điểm $E$ đến đường thẳng $PQ$ là $2Rs(EP)$ ($s(EQ)$).

Tuyên bố 1° được nhiều người biết đến (từ đó người ta thường rút ra “định lý sin” cho một tam giác) và 2° có thể dễ dàng suy ra từ 1° bằng cách tính diện tích của tam giác $PQE$ theo hai cách. Nếu $\alpha$ là góc ở đỉnh $E$ của tam giác này, $h$ là chiều cao bị bỏ qua khỏi đỉnh này, thì diện tích kép là $h \cdot PQ = EP \cdot EQ \cdot \sin \alpha$, do đó, có tính đến thực tế là $EP = 2Rs(EP)$, $EQ = 2Rs(EQ)$, $PQ = 2Rs(PQ) = 2R \sin \alpha$, chúng ta thu được $h = 2Rs(EP)$ ($s(EQ)$).

Bây giờ bài toán M122 được giải quyết ngay lập tức: theo điều kiện

$$p = 2Rs(EA) s(EB),$$
$$q = 2Rs(EB) s(EC),$$
$$r = 2Rs(EC) s(ED),$$

Do đó, khoảng cách từ điểm $E$ đến đường thẳng $AD$ là

$$2Rs(EA) s(ED) = pr/q.$$

bài toán này đã được đưa ra trong một trong những phiên bản của bài kiểm tra viết môn toán tại trường vật lý của Đại học quốc gia Moscow năm 1971 (nơi mà nó khó nhất).

N. B. Vasiliev

Trong số này, chúng tôi xuất bản lời giải bài toán F131—F137

F131

Một ống thủy tinh nhẹ có chiều dài $l$ và tiết diện $S$, chứa đầy hình trụ và bịt kín một đầu, được đặt nằm ngang trong một bể có tia phun gần bề mặt. Công tối thiểu phải được thực hiện để di chuyển ống đến vị trí thẳng đứng sao cho đầu hở của nó chạm vào bề mặt thủy ngân?

Công cần thiết để di chuyển ống không phụ thuộc vào phương pháp chúng ta di chuyển ống đến vị trí thẳng đứng. Ví dụ, bạn có thể xoay ống quanh phần cuối, bạn có thể xoay ống quanh phần giữa và sau đó nuôi nó ra khỏi thủy ngân, và cuối cùng bạn có thể xoay nó quanh phần cuối và sau đó lại nuôi nó ra khỏi thủy ngân. Sẽ thuận tiện nhất khi xem xét phương pháp cuối cùng.

Khi di chuyển thủy ngân bên trong bể từ nơi này sang nơi khác, không tốn công vì thế năng

năng lượng của hệ không thay đổi. Vì vậy, không có công việc nào bị lãng phí khi xoay ống quanh đầu. Vì vậy, chỉ cần tính công để “kéo” ống ra khỏi thủy ngân.

Nếu đầu ống ở trên bề mặt ở độ cao $x$ (Hình 20), thì lực áp suất khí quyển $F_1 = P_0S$ tác dụng lên nó từ phía trên và lực $F_2 = P \cdot S$ tác dụng lên đáy ống từ bên dưới, trong đó $P$ là áp suất ở đáy. $P$ có thể tìm được bằng cách viết ra các trạng thái cân bằng có điều kiện của cột thủy ngân trong ống

$$P + \rho gx = P_0.$$

(Áp suất tại điểm $B$ phải bằng $P_0$.) Do đó

$$P = P_0 - \rho gx.$$

Lực mà bạn cần để kéo ống ra rất lớn bằng hiệu giữa lực $F_1$ và $F_2$:

$$F = F_1 - F_2 = \rho gxS.$$

Lực này tỉ lệ với $x$.

⟦folio none⟧

Hình 20.

Hình 21.

Tuy nhiên, điều này chỉ đúng cho đến khi $P$ trở thành 0, tức là ở $x \leq \frac{P_0}{\rho g} = 0,76$ m.

Nếu chiều dài của ống $l$ lớn hơn $x_1 = P_0/\rho g = 0,76$ m thì ở $x > x_1$ $P = 0$ (có thể bỏ qua áp suất hơi rutin) và lực cần thiết để “kéo” ống bằng một $F_1 = P_0 S$ đơn giản.

Hãy vẽ đồ thị của lực $F$ so với $x$ (Hình 21). Công cần thiết để kéo ống ra bằng diện tích của hình bên dưới đồ thị này. Do đó, nếu $l < x_1$ thì

$$A = \frac{1}{2} \rho g l S \cdot l = \frac{1}{2} \rho g S l^2.$$

Tại $l > x_1$

$$A = \frac{1}{2} \rho g S x_1^2 + P_0 S (l - x_1) =$$

$$= \frac{1}{2} P_0 S x_1 + P_0 S (l - x_1) =$$

$$= P_0 S \left( l - \frac{1}{2} x_1 \right).$$

F132

Khối trụ $m$ được tháo xoắn và đặt giữa hai mặt phẳng cố định nằm nghiêng một góc $2\alpha$ với nhau (Hình 22). Biết hệ số ma sát giữa hình trụ và mặt phẳng là $k$, hãy xác định lực mà hình trụ tác dụng lên mặt phẳng.

Xét sự cân bằng của một hình trụ. Nó chịu tác dụng của các lực $N_1$ và $N_2$ của các phản lực bình thường của các mặt phẳng, lực ma sát $F_1$ và $F_2$ và lực hấp dẫn $mg$. Bề mặt của hình trụ trượt dọc theo các mặt phẳng nên $F_1 = k N_1$ và $F_2 = k N_2$.

Vì hình trụ ở trạng thái cân bằng nên tổng các hình chiếu lên bất kỳ trục nào của tất cả các lực tác dụng lên nó phải bằng 0. Hãy chiếu tất cả các lực lên hai trục vuông góc lẫn nhau - ngang và dọc:

$$-N_1 \cos \alpha + N_2 \cos \alpha + F_1 \sin \alpha + F_2 \sin \alpha = 0,$$

$$N_1 \sin \alpha + N_2 \sin \alpha + F_1 \cos \alpha - F_2 \cos \alpha - mg = 0.$$

Thay các giá trị $F_1 = k N_1$ và $F_2 = k N_2$ vào các phương trình này, chia vế trái và vế phải cho cos $\alpha$, ta thu được:

$$(N_1 + N_2) k \mathrm{tg} \alpha - N_1 + N_2 = 0,$$

$$(N_1 + N_2) \mathrm{tg} \alpha + k N_1 - k N_2 = \frac{mg}{\cos \alpha}.$$

Cùng nhau giải phương trình, ta được

$$N_1 = \frac{mg}{\cos \alpha} \cdot \frac{1 + k \mathrm{tg} \alpha}{2 \mathrm{tg} \alpha (1 + k^2)},$$

$$N_2 = \frac{mg}{\cos \alpha} \cdot \frac{1 - k \mathrm{tg} \alpha}{2 \mathrm{tg} \alpha (1 + k^2)}.$$

Vì vậy, lực ma sát

$$F_1 = \frac{mg k}{\cos \alpha} \cdot \frac{1 + k \mathrm{tg} \alpha}{2 \mathrm{tg} \alpha (1 + k^2)},$$

$$F_2 = \frac{mg k}{\cos \alpha} \cdot \frac{1 - k \mathrm{tg} \alpha}{2 \mathrm{tg} \alpha (1 + k^2)}.$$

Biết các lực tác dụng lên hình trụ không khó tìm được các lực tác dụng lên hình trụ

⟦folio 70⟧

cạnh của hình trụ trên mặt phẳng. Theo định luật thứ ba của Newton, các lực này có độ lớn bằng nhau và ngược chiều nhau. Trong hình chúng được đánh dấu bằng các vectơ màu xanh lam.

Vì lực $N_2$ không thể âm nên lời giải có giá trị cho $k \text{tg} \alpha \leq 1$. Nếu $k \geq \frac{1}{\text{tg} \alpha}$ thì $N_2 = 0$ và $F_2 = 0$. Trong trường hợp này, hình trụ có hai đầu không chạm vào mặt phẳng nghiêng trái hoặc đi lên dọc theo mặt phẳng nghiêng phải.

F133

Một dây xích kim loại kín được nối bằng một sợi ren với trục của máy ly tâm và quay với vận tốc góc $\omega$ (Hình 23). Trong trường hợp này, sợi chỉ tạo một góc $\alpha$ với phương thẳng đứng. Tìm khoảng cách từ trọng tâm của sợi xích đến trục quay.

Các lực tác dụng lên sợi xích được thể hiện như hình vẽ; $T$ là lực căng chỉ, $mg$ là lực căng chỉ. Vì tâm của chồng nặng của sợi dây chuyển động dọc theo một đường tròn có bán kính $x$ nên theo định luật thứ hai của Newton, tổng hình chiếu của tất cả các lực tác dụng lên sợi dây theo phương nằm ngang phải bằng tích

Hình 23.

khối lượng của dây vào gia tốc hướng tâm của khối tâm. Đó là

$$T \sin \alpha = m \omega^2 x.$$ (1)

Dây xích không chuyển động theo phương thẳng đứng; do đó, tổng hình chiếu của tất cả các lực tác dụng lên dây xích theo hướng thẳng đứng bằng 0:

$$T \cos \alpha - mg = 0.$$ (2)

Loại bỏ $T$ khỏi các phương trình này, chúng ta tìm thấy

$$x = \frac{g}{\omega^2} \text{tg} \alpha.$$ (3)

F134

Một tấm nặng chuyển động với vận tốc $v$ theo phương vuông góc với mặt phẳng của nó. Hợp với hướng chuyển động của tấm một góc $\alpha$, một quả cầu nhẹ bay với vận tốc $u$. Xác định độ lớn và hướng vận tốc của quả bóng sau va chạm đàn hồi với tấm bia.

a) Khoảng cách trường hợp khi tốc độ của quả bóng hướng vào và ra khỏi tấm.

b) đáp số sẽ thay đổi như thế nào nếu tấm chuyển động theo hướng tạo một góc $\beta$ với mặt phẳng của nó?

a) Vì tốc độ của tấm không thay đổi trong quá trình va chạm nên hệ tấm bi không cô lập và đối với lời giải bài toán không thể sử dụng định luật bảo toàn động lượng. Vì vậy, hãy làm theo cách này. Hãy phân tích tốc độ của quả bóng thành các thành phần - song song với tấm và vuông góc với nó - và chuyển sang hệ tọa độ liên kết với tấm. Trong hệ tọa độ này, thành phần vận tốc của quả bóng song song với tấm bằng $u \sin \alpha$ và thành phần vận tốc vuông góc với tấm bằng $u \cos \alpha + v$ (Hình 24). Sau khi quả bóng va chạm đàn hồi với tấm, thành phần vận tốc của quả bóng song song với tấm sẽ không thay đổi và thành phần vận tốc vuông góc với tấm sẽ có cùng giá trị nhưng ngược chiều.

Bây giờ chúng ta hãy “trở lại” hệ tọa độ cố định. Ở đây thành phần vận tốc của quả bóng sau khi chạm vào đĩa sẽ là $u \sin \alpha$ và $(u \cos \alpha + v) + v = u \cos \alpha + 2v$.

Điều này có nghĩa là tốc độ của quả bóng sau khi chạm vào tấm trong hệ tọa độ cố định bằng

$$u' = \sqrt{u^2 \sin^2 \alpha + (u \cos \alpha + 2v)^2} = \sqrt{u^2 + 4v^2 + 4vu \cos \alpha}.$$ (1)

Tốc độ này được xác định theo hướng

⟦folio 71⟧

Hình 25.

chuyển động của góc tấm γ sao cho

$$\text{tg} \gamma = \frac{u \sin \alpha}{u \cos \alpha + 2v}.$$ (2)

Chúng tôi đã xem xét chi tiết trường hợp tốc độ của quả bóng hướng về phía đĩa. Rõ ràng là nếu tốc độ của quả bóng hướng ra xa đĩa thì $u \cos \alpha < v$, lời giải vẫn đúng, chỉ trong tất cả các công thức cần thay $u \cos \alpha$ bằng $-u \cos \alpha$. Ở $u \cos \alpha \geq v$ quả bóng sẽ không va chạm với đĩa.

6) Không khó để khái quát hóa bài toán cho trường hợp tấm chuyển động theo hướng tạo một góc β với mặt phẳng của nó. Rõ ràng là trong trường hợp này, khi quả bóng va chạm với tấm, chỉ có thành phần vận tốc của nó vuông góc với tấm là thay đổi. Sự thay đổi của nó giống như trường hợp tấm di chuyển theo hướng vuông góc với mặt phẳng của nó với tốc độ $v' = v \sin \beta$ (Hình 25). Do đó, chúng ta sẽ thu được đáp số đúng nếu thay thế $v'$ trong công thức (1) và (2) cùng với $v$. Sau đó

$$u' = \sqrt{u^2 + 4v^2 \sin^2 \beta + 4uv \cos \alpha \sin \beta},$$

$$\text{tg} \gamma = \frac{u \sin \alpha}{u \cos \alpha + 2v \sin \beta}.$$

F135

Một quả mìn nằm trên mặt đất phát nổ. Các mảnh mìn bắt đầu di chuyển đối xứng theo mọi hướng với cùng tốc độ $v$. Kích thước của tất cả các vận tốc, phần nào của vết cháy sẽ nằm ngoài vòng tròn bán kính $R$ có tâm tại điểm nổ?

Chúng ta hãy viết các phương trình động học của chuyển động dọc theo trục $X$ và $Y$ đối với nhựa rơi một góc $\alpha$ so với đường chân trời:

$$x = vt \cos \alpha, \quad y = vt \sin \alpha - gt^2/2.$$ (1)

Chúng ta hãy tìm từ các phương trình này khoảng cách bay của hòn đá. Tại thời điểm hòn đá rơi xuống Trái đất, tọa độ $y$ của nó bằng 0 và tọa độ $x$ là quãng đường bay $l$. Vì vậy, vào lúc này

$$vt_0 \cos \alpha = l, \quad vt_0 \sin \alpha = gt_0^2/2.$$ (3)

(Ở đây $t_0$ là thời gian bay của muối.) Do đó, khoảng cách bay của muối

$$l = v \cos \alpha \cdot \frac{2v}{g} \sin \alpha = \frac{v^2}{g} \sin 2\alpha.$$ (2)

Không khó để xác định góc tiếp xúc của các mảnh vỡ, phạm vi bay của chúng lớn hơn $R$:

$$\frac{v^2 \sin 2\alpha}{g} > R, \quad \sin 2\alpha > \frac{gR}{v^2},$$

$$\alpha_0 \leq \alpha \leq \pi/2 - \alpha_0,$$

ở đâu $\alpha_0 = \frac{1}{2} \arcsin \frac{gR}{v^2}$.

Chúng ta hãy vẽ nhẩm một bán cầu có bán kính $a$ xung quanh mỏ. Rõ ràng, một phần của các mảnh $n$ phát ra trong khoảng góc $\alpha_0 \leq \alpha \leq \pi/2 - \alpha_0$ bằng diện tích tương đối $S$ của bề mặt bên của lớp hình cầu, có thể nhìn thấy từ tâm bán cầu trong khoảng góc này, đến diện tích của bán cầu:

$$n = \frac{S}{\pi a^2}.$$

Để tìm $S$, chúng tôi chia lớp hình cầu thành những con voi mỏng, có thể nhìn thấy được từ tâm bán cầu trong một khoảng nhỏ các góc $\Delta \alpha$. Diện tích $S$ của bề mặt bên của lớp mỏng như vậy với $\Delta \alpha = \alpha_2 - \alpha_1$ bằng chiều rộng $a \Delta \alpha = a (\alpha_2 - \alpha_1)$, nhân với chu vi của phần giữa của lớp - bán kính của nó là $a \cos \frac{\alpha_1 + \alpha_2}{2}$:

$$s = 2\pi a \cos \frac{\alpha_1 + \alpha_2}{2} \cdot 2a \frac{\alpha_2 - \alpha_1}{2}.$$

Vì $\Delta \alpha = \alpha_2 - \alpha_1$ nhỏ nên

$$\frac{\alpha_2 - \alpha_1}{2} \approx \sin \frac{\alpha_2 - \alpha_1}{2},$$

$$s \approx 4\pi a^2 \sin \frac{\alpha_2 - \alpha_1}{2} \cos \frac{\alpha_1 + \alpha_2}{2} = 2\pi a^2 (\sin \alpha_2 - \sin \alpha_1).$$

Diện tích $S$ của bề mặt bên của toàn bộ lớp bằng tổng diện tích các bề mặt bên của các từ mỏng:

$$S = s_1 + s_2 + \dots = 2\pi a^2 (-\sin \alpha_0 + \sin \alpha_1 - \sin \alpha_2 + \dots) = 2\pi a^2 \left[ \sin \left( \frac{\pi}{2} - \alpha_0 \right) - \sin \alpha_0 \right] = 2\sqrt{2} \pi a^2 \sin \left( \frac{\pi}{4} - \alpha_0 \right).$$

Nhưng

$$\sin \left( \frac{\pi}{4} - \alpha_0 \right) = \sqrt{\frac{1 - \sin 2\alpha_0}{2}}.$$

⟦folio 72⟧

Kể từ đây,

$$S = 2\sqrt{2}\pi a^2 \frac{1 - \sin\left(\frac{gR}{v^2}\right)}{2} = 2\pi a^2 \sqrt{1 - \frac{gR}{2}}$$

Và

$$n = \frac{S}{\pi a^2} = 2\sqrt{1 - \frac{gR}{v^2}}.$$

F136

Một tụ điện bản song song có điện dung $C$. Một điện tích +$q$ được đặt trên một trong các bản tụ điện và điện tích +4$q$ được đặt trên bản còn lại. Xác định hiệu điện thế giữa các bản của tụ điện.

Nếu có các điện tích +$Q$ và -$Q$ trên các bản của một tụ điện phẳng, thì điện áp trường giữa các bản được biết là $E = \frac{Q}{Cd}$. Trường này bằng tổng của các trường giống hệt nhau của hai tấm. Do đó, điện áp trường của một bản có điện tích phân bố đều là $\frac{1}{2} \frac{Q}{Cd}$.

Điện áp trường của một tấm có điện tích +$q$ là $\frac{1}{2} \frac{q}{Cd}$ và điện áp trường của một tấm có điện tích +4$q$ là $\frac{2q}{Cd}$. Không giống như điện tích ngẫu nhiên của tụ điện, khi điện áp trường của các bản được định hướng theo một hướng và cộng lại, trong trường hợp của chúng ta, điện áp trường do các bản tạo ra được định hướng theo các hướng khác nhau. Do đó, điện áp của trường đơn giữa các bản bằng với chênh lệch điện áp trường của mỗi bản (Hình 26):

$$E' = \frac{2q}{Cd} - \frac{1}{2} \frac{q}{Cd} = \frac{3}{2} \frac{q}{Cd}.$$

Bây giờ không khó để tìm ra sự khác biệt giữa các tấm thế năng. Nó bằng nhau chứ không phải

$$P_0 = \frac{mg}{S}.$$

Từ đây

$$m = \frac{P_0 S}{g}.$$

Nhân $m$ với $\alpha$, ta thu được khối lượng metan trong cột này:

$$m_{CH_4} = \alpha m = \frac{\alpha P_0 S}{g}.$$

Bây giờ chúng ta hãy tìm lớp có độ dày $x$ khối lượng khí metan này sẽ tạo thành trong điều kiện bình thường (diện tích đáy hình trụ vẫn bằng $S$).

Hãy viết phương trình trạng thái khí:

$$P_0 Sx = \frac{m_{CH_4}}{\mu} RT,$$

trong đó $Sx$ là thể tích khối lượng khí mêtan $m_{CH_4}$, $\mu$ là khối lượng của một kilomol khí mêtan ($\mu = 16 \frac{\kappa}{kmol}$), $R = 8,3 \cdot 10^3 \frac{\partial x}{\partial p} \cdot \frac{\partial p}{\partial T}$ là hằng số khí, $T = 273^\circ K$ là nhiệt độ bình thường và $P_0 = 1 \text{ atm}$ là áp suất bình thường. Thay biểu thức khối lượng metan vào phương trình này, chúng ta tìm thấy

$$x = \frac{\alpha RT}{g\mu} (m).$$
