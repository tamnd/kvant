---
id: 1989-5-sokolov-fraktalyi-21f80393
issue: kvant_1989_5
year: 1989
number: "5"
title: Fractal
authors:
  - Соколов И. М.
rubric: osnovnye-stati
page_first: 8
page_last: 15
page_labels: 6-13
tag: WAVV
lang: vi
source: kvant_digital
extraction: vision
content_sha256: 76736bee79e117a14fa025a7d67b36ae48978451a6fbde42a4459b18c52749c9
prompt_sha256: draft-1
translated_from: content/ru/1989/05/articles/03_sokolov-fraktalyi-21f80393.md
source_content_sha256: 68160d26131d7387fd7268a672fe0b444d66577a7993e3161d5080026a783624
translation_model: draft
translation_run: vi-draft-2026-10-31
translation_quality: draft
---

⟦folio 6⟧

FRACTAL

Ứng viên Khoa học Vật lý và Toán học
I. M. SOKOLOV

Những đối tượng mà ngày nay chúng ta gọi là sự kiện lần đầu tiên xuất hiện trong trí tưởng tượng của các nhà toán học ở những thế kỷ đầu. Và khi đó chúng ta khó có thể nghĩ rằng trong thiên nhiên xung quanh chúng ta có thể tìm thấy bất cứ thứ gì tương tự với những đường cong kỳ lạ và tinh tế này. Và mặc dù trong bài viết này chúng ta chủ yếu nói về các hệ vật lý, chúng ta sẽ phải bắt đầu bằng một phần giới thiệu toán học nhỏ và không chặt chẽ.

Các đối tượng hình học tương tự

Chúng ta sẽ gọi một hình hình học (vật thể) tự tương tự là một hình có thể được cắt thành một số hữu hạn các hình giống hệt nhau tương tự như chính nó. Ví dụ - trên hình 1: đoạn thẳng, tam giác đều, hình vuông, hình lập phương.

Đối tượng tự tương tự ở hình 2 trông phức tạp hơn một chút. Nhưng nó khá đơn giản để xây dựng. Bắt đầu với một tam giác đều ở cạnh $l_0$, chúng ta sẽ lặp lại (ad infinitum) quy trình sau: chúng ta sẽ chia mỗi đoạn nối các đỉnh của đường đứt nét thành ba phần và thay thế phần giữa bằng hai đoạn có chiều dài $l/3$, trong đó $l$ là độ dài của đoạn ban đầu. Một số giai đoạn đầu tiên của việc xây dựng một đường cong như vậy được hiển thị ở hình 2. Ở giai đoạn xây dựng thứ $n$, đường cong được biểu thị bằng một đường gãy có $N = 3N = 3 \cdot 4^n$ các đoạn có độ dài $l_0/3^n$ mỗi đoạn, chiều dài đầy đủ của nó

$$L = 3l_0(4/3)^n.$$

Đường gãy này được gọi là đường cong Triditch Koch (được đặt theo tên của nhà toán học Thụy Điển đã phát minh ra vật thể này).

Mỗi đoạn ban đầu của đường cong Triditch Koch bao gồm bốn

⟦folio 7⟧

thủ tục ném ra giữa hình vuông được chia thành 9 phần.

Hãy quay trở lại đường cong Koch. Ví dụ, hãy thử xác định độ dài của nó bằng la bàn. Sau khi đặt phép tính của la bàn bằng $\lambda$, chúng ta sẽ sắp xếp lại la bàn dọc theo đường cong, đếm số hoán vị của nó $n$. Độ dài của đường cong sẽ xấp xỉ bằng $L \approx \lambda n$. Chúng ta sẽ gọi đại lượng $\lambda$ là thang đo lường.

Chẳng hạn, đo chiều dài của một vòng tròn có bán kính $R = 1$ m, chúng ta thu được rằng chiều dài đo được $L = \lambda n$ tại $\lambda = 1$ m là 3,0 m, tại $\lambda = 0,1$ m $L = 6,2$ mm, tại $\lambda = 0,01$ m $L = 6,28$ m và tại $\lambda \rightarrow 0$ chiều dài $L$ có xu hướng giới hạn $2\pi R = 6,28318\dots$ m.

Sau khi thử thực hiện quy trình tương tự với đường cong Koch, chúng ta sẽ tin chắc rằng không có giới hạn nào có thể được coi là độ dài của đường cong này. Bằng cách chọn thang đo $\lambda = l_0/3^n$, chúng ta thu được rằng chiều dài đo được của đường cong sẽ bằng chiều dài của đường đứt nét tương ứng với giai đoạn xây dựng thứ $n$ của nó - $L = 3l_0(4/3)^n$.

Nỗ lực đo độ dài của các đường cong tự tương tự khác sẽ dẫn đến một kết quả tương tự - khi thang đo giảm, độ dài của đường cong tăng vô hạn.

Chúng ta hãy lưu ý một yếu tố rất quan trọng giúp phân biệt một đối tượng thực sự giống với một đối tượng toán học lý tưởng: các đối tượng thực có thang đo tối thiểu $\lambda_{\min}$.

Ví dụ, hãy xem xét quá trình thực tế xây dựng đường cong Koch bằng bút chì và giấy. Chúng ta hãy dựng một đường cong có chiều dài cạnh ban đầu là $l_0 = 1$ m bằng bút chì để lại một đường có độ dày $a_0 = 0,1$ mm = $10^{-4}$ m. Từ quan điểm toán học, quy trình xây dựng đường cong có thể tiếp tục vô thời hạn. Quy trình thực sự sẽ dừng ngay khi độ dài của đoạn giữa hai điểm ngắt liền kề bằng độ dày của đường thẳng. Dễ dàng tính được đây là quá trình ở bước số $n = \ln(l_0/a_0)/\ln 3 \approx 9$. Chiều dài đường dây của chúng tôi sẽ là $L \approx 40$ m. Vì vậy, việc nhận ra một đường cong tự đồng dạng có độ dài hữu hạn.

Bây giờ chúng ta hãy quay trở lại với các đối tượng toán học lý tưởng. Công thức tính độ dài đường cong Koch có thể được viết như sau:

$$L = A\lambda^{-\alpha}, \text{ где } A = 3l_0^{\ln 4/\ln 3}, \alpha = \frac{\ln 4}{\ln 3} - 1.$$

(Chúng tôi hy vọng rằng chính bạn, khi biết các quy tắc xử lý logarit, sẽ có thể xác minh rằng mục này tương đương với công thức $L = 3l_0(4/3)^n$.) Số mũ a xuất hiện trong công thức có liên quan đến kích thước của đường cong.

Kích thước là gì?

Có nhiều định nghĩa về chiều, tương ứng với các khái niệm khác nhau. Chúng ta hãy cố gắng có được một ý tưởng về một số trong số họ.

Hình 3.

⟦folio 8⟧

Định nghĩa đầu tiên liên quan đến số tọa độ tối thiểu cần thiết để xác định rõ ràng vị trí của một điểm. Trong không gian của chúng ta, con số này bằng trem, trên một mặt phẳng có hai tọa độ là đủ, trên một đường thẳng - chỉ một tọa độ. Theo nghĩa này, không gian là ba chiều, mặt phẳng là hai chiều và đường thẳng là một chiều. Đương nhiên, trong định nghĩa này, thứ nguyên luôn là số nguyên.

Định nghĩa thứ hai liên quan đến điều cản trở sau đây. Để cắt một hình chữ nhật thành hai phần, chỉ cần loại bỏ một điểm. Một tập hợp bao gồm một số điểm hữu hạn (có thể đếm được) sẽ được coi là không chiều. Kích thước của bất kỳ bộ nào sẽ được coi là lớn hơn một kích thước so với kích thước của vết cắt chia nó thành hai phần rời nhau. Với định nghĩa về kích thước này, một đường thẳng là một chiều, một mặt phẳng (để cắt cần phải cắt dọc theo một đường nhất định) là hai chiều và một vật thể hình học ba chiều là ba chiều. Chiều này - nó được gọi là tôpô - cũng chỉ có thể là số nguyên.

Bây giờ chúng ta hãy chuyển sang định nghĩa thứ ba, thú vị nhất đối với chúng ta, hay chính xác hơn là định nghĩa về cả một nhóm các chiều có thể hiểu được và có ý nghĩa gần gũi. Đơn giản nhất trong số đó là chiều tự tương tự.

Chiều tự tương tự $D$ có thể được xác định bằng công thức

$$D = \frac{\ln N}{\ln n},$$

trong đó $N$ là số phần giống hệt nhau mà một đối tượng giống nhau nhất định được chia thành, có kích thước không gian có thể trao đổi là $n$. Nhìn vào hình 1. Bằng cách thực hiện các vết cắt như trong hình, chúng ta sẽ chia hình vuông thành $N = 4$ các hình vuông có cạnh nhỏ hơn $n = 2$ lần so với ban đầu. Khối lập phương ở cạnh 1 bao gồm $N = 8$ cốc ở cạnh $1/2 (n = 2)$. Vậy kích thước tự tương tự của hình vuông là $\ln 4/\ln 2 = 2$, đối với hình lập phương - $\ln 8/\ln 2 = 3$; rất/không rằng kích thước của phân khúc là 1.

Sự phát triển của “bông tuyết” trên màn hình máy tính trong các điều kiện khác nhau.

Tính kích thước của các vật thể ở Hình 2 và Hình 3 theo cách tương tự, ta sẽ thấy kích thước của từng đoạn đường cong Koch (và kích thước của toàn bộ đường cong)

⟦folio 9⟧

đúng $D=\ln 4/\ln 3=1,2618$, đường cong tam giác Sierpiski là $\ln 3/\ln 2=1,5849$, “thảm Sierpiski” là $\ln 8/\ln 3=1,8727$. Các đường cong trang này có kích thước không nguyên.

Bây giờ chúng ta quay lại công thức tính độ dài đường cong Koch. Sử dụng định nghĩa của thứ nguyên $D$ vừa cho, chúng ta có thể viết lại công thức này thành

$$L=3l_0^D\lambda^{1-D}.$$

Sự gia tăng thay đổi về độ dài của đường cong tự tương tự khi thang đo giảm là một chỉ báo về thứ nguyên không nguyên của nó:

$$D=1+\alpha.$$

Làm thế nào để thay đổi kích thước?

Chiều của sự tự tương tự chỉ có thể được xác định đối với các đối tượng rất thông thường, được xây dựng theo các quy tắc được xác định chặt chẽ. Nếu độ lệch so với tính đều đặn không lớn thì đối tượng có thể được coi là gần giống với chính nó. Nếu chúng lớn thì sao?

Chúng ta hãy sử dụng một định nghĩa khác về thứ nguyên, thường là

Hình 4.

cắt thành các ô có kích thước $\lambda$ (ví dụ: đặt một lưới vuông trên ảnh phẳng của một vật thể từ phía $\lambda$). Đếm số ô mà đối tượng trỏ tới. Phép chia được lặp lại, thang đo được sử dụng là $\lambda'<\lambda$, v.v. (hình 4). Sự phụ thuộc của số lượng ô mà đối tượng trỏ vào kích thước của ô được đưa ra theo định luật $N=A\lambda^{-D}$, trong đó $D$ là kích thước bắt buộc. Xét diện tích phẳng của mặt phẳng $S$ (tam giác trên hình 4), dễ dàng chứng minh rằng $N \approx S/\lambda^2$ nên $D=2$. Đối với đoạn $N=BL/\lambda$, trong đó $L$ là độ dài của đoạn và $B$ là hệ số, tùy thuộc vào hướng của đoạn đó. Kích thước của đoạn này là $D=1$. Nếu chúng ta thực hiện quy trình tương tự với các đối tượng được hiển thị trong Hình 2 và 3, chúng ta sẽ thu được các giá trị $D$ trùng với thứ nguyên tự tương tự của chúng. Để xác định kích thước của vật thật, hình phụ thuộc từ $\ln N$ vào -$\ln \lambda$. Biểu đồ này được vẽ dưới dạng một đường thẳng, độ dốc của nó cho chúng ta giá trị $D$.

"Hình học Fractal của tự nhiên"

Năm 1961, công trình của nhà nghiên cứu người Anh L. Richardson (1881-1953) được xuất bản nhằm mục đích đo chiều dài của các đường bạch dương. Tác giả nhận thấy chiều dài bờ biển đo được tăng khi giảm thang đo theo quy luật

2 Lượng tử số 5

⟦folio 10⟧

Một trình phân loại fractal xuất hiện trong quá trình mô phỏng máy tính về tập hợp được kiểm soát khuếch tán.

$$L = A \lambda^{-\alpha}$$ (định luật Richardson), trong đó chỉ số $\alpha$, ví dụ: 0,24 đối với bờ biển phía tây nước Anh và 0,13 đối với bờ biển Australia. Và mặc dù định luật này cung cấp nhiều thông tin hữu ích cho các công thức tính độ dài của các đường cong tự đồng dạng, bản thân công trình của Richardson đã có ý nghĩa quan trọng. Có một số ví dụ vật lý khác đã “đạt tới” những vật thể tương tự. Nhưng mọi thứ đã bị phân tán...

Một sự thay đổi đáng kể sẽ xảy ra với sự xuất hiện của cuốn sách của nhà toán học người Pháp Benya Mandelbort (hiện đang làm việc tại Mỹ), xuất bản năm 1975 bằng tiếng Pháp và năm 1977 bằng tiếng Anh. Cuốn sách tập hợp nhiều ví dụ toán học và vật lý này, giúp chúng có thể sử dụng được trong khoa học. Nhưng công lao chính của Mandelbort là ông đã nghĩ ra cái tên cho tất cả những thứ này.

Người đọc có thể sẽ nhớ rằng đóng góp chính của Atoc cho các sự kiện được mô tả trong tiểu thuyết Hai mươi năm sau của Dumas là việc phát minh ra hệ thống định vị cho Chiến dịch Gia đình. Khoản đóng góp này được coi là tương đương với thanh kiếm của d'Artanne và số tiền của Portoc. Có được khả năng điều hướng tốt là một thành tựu lớn.

Đối với các đối tượng có chiều phân số, hay chính xác hơn, đối với các đối tượng có chiều Pháp lớn hơn chiều tôpô của chúng, Mandelbrot đã nghĩ ra cách điều hướng “fractal”. Từ này xuất phát từ tiếng Latin fractus - phân số, cắt. Một người rất hóm hỉnh đã chuyển điều hướng của mình sang tiếng Nga với từ “drobnik”.

Cuốn sách đầu tiên của Mandelbort có tên là Fractals: Form, Chance, Dimension. Cuốn thứ hai, xuất bản năm 1982, đã được gọi là: “Hình học Fractal của Tự nhiên”. Cái tên này phản ánh hoàn hảo tình hình thực tế.

Các đối tượng đa địa lý có đặc tính fractal - bờ biển và đại dương, sông, núi và hẻm núi. Biên giới của các quốc gia, nếu chỉ tuân theo các mốc tự nhiên và không được vẽ bằng thước trên bản đồ mà chỉ sau đó được xác định trên thực địa (chẳng hạn như biên giới giữa Ai Cập và Sudan), cũng là các đường phân dạng. Chiều dài biên giới giữa Bồ Đào Nha và Tây Ban Nha (được nêu trong sách tham khảo tiếng Bồ Đào Nha) và chiều dài biên giới giữa Tây Ban Nha và Bồ Đào Nha (được nêu trong thông tin chính thức của Tây Ban Nha) khác nhau 20% vì chúng được sửa đổi bằng các thang đo khác nhau. Điều này một lần nữa khẳng định khái niệm độ dài đối với đường cong Pháp không có nhiều ý nghĩa.

⟦folio 11⟧

Hóa ra những đường cong như đường cong Koch là quy luật chứ không phải là ngoại lệ trong tự nhiên. Rõ ràng là tính tự che khuất của các vật thể tự nhiên, có thật bị vi phạm bởi những sai lệch ngẫu nhiên khỏi cấu trúc đều đặn. Ví dụ, các phần khác nhau của bờ biển không giống nhau mà chỉ tương tự nhau. Và tất cả các hệ thống thực tế đều có thang đo lường tối thiểu. Những trường hợp này phải được tính đến khi phân tích tình hình vật lý.

Để có thể nói về các đặc tính thực tế của hệ thống, điều cần thiết là sự khác biệt giữa thang đo tối thiểu và tối đa phải đủ lớn. Nếu chúng ta đang nói về bờ biển hoặc đại dương, thì tỷ lệ tối đa $l_0$ sẽ vào khoảng $1000$ km $= 10^6$ m, và tỷ lệ tối thiểu, được xác định trực tiếp bởi các ranh giới do sóng tới, thủy triều, v.v., sẽ vào khoảng $1 - 10$ m. Những thang đo này khác nhau một triệu (!) Lần.

Một ví dụ khác về đường cong thực tế là ranh giới nhìn thấy được của các đám mây. Sự khác biệt giữa tỷ lệ tối thiểu và tối đa ở đây thậm chí còn lớn hơn so với trường hợp bờ biển: có dữ liệu về các khu vực có kích thước từ hàng trăm mét với các chi tiết có thể nhìn thấy được từ một mét đến kích thước của Trái đất (các vùng xoáy cực). Kích thước của ranh giới đám mây là $D = 1,35$.

Cho đến nay chúng ta chủ yếu chỉ xem xét những đường cong thực tế - những đường có độ phức tạp cao tương tự như đường cong Koch, và các ví dụ địa lý của chúng ta có tính chất hình tròn. Có nhiều quá trình vật lý làm phát sinh các cấu trúc thực tế phức tạp và quan trọng hơn.

Nhiều người trong số các bạn có thể đã trồng tinh thể từ dung dịch bão hòa. Nếu dung dịch không quá bão hòa và được trộn vừa đủ thì một tinh thể màu đỏ có hình dạng đều sẽ mọc ra từ hạt lơ lửng trên một sợi. Tinh thể phát triển do trong chuyển động của nó, các phân tử bằng cách nào đó tiếp cận những vị trí trên bề mặt của nó, nơi chúng có thể “dính”, chiếm vị trí thuận lợi nhất theo quan điểm năng lượng. Tất nhiên, hầu hết các phân tử đều kết thúc ở những nơi không hoàn toàn phù hợp, nhưng sớm hay muộn chúng lại trở nên hòa tan hoặc tan chảy do không đủ kết nối với phần còn lại của tinh thể. Kết quả của sự tăng trưởng cân bằng như vậy là thu được một tinh thể không có khoảng trống bên trong, với các cạnh phẳng nhẵn lý tưởng.

Trong trường hợp không có sự cân bằng giữa quá trình kết tinh và hòa tan (tức là trong quá trình kết tinh nhanh từ dung dịch siêu bão hòa cao hoặc trong quá trình kết tinh từ pha khí), các tinh thể thuộc loại hoàn toàn khác sẽ xuất hiện. Tất nhiên, bạn đã từng nhìn thấy một lớp tuyết phủ trên ngăn đá của tủ lạnh hoặc những hình đóng băng trên cửa sổ. Những thành tạo khá tanh này là do sự kết tủa của nước trong không khí. Đầu tiên, các cụm phân tử riêng biệt được hình thành - cái gọi là các lớp phân tử; Dần dần phát triển và kết nối, các lớp hình thành các khuôn mẫu. Các điều kiện tương tự như những điều kiện xảy ra trong quá trình phát triển của các loài phân lớp cũng tồn tại trong quá trình phát triển của các bông tuyết trong khu vực.

Quá trình tăng trưởng này, được gọi là sự kết tụ được kiểm soát khuếch tán, dẫn đến sự hình thành các tinh thể có hình dạng thực tế - endrite. Kích thước thực tế của tinh thể hendrite được xác định bởi cơ chế phát triển cụ thể của chúng. Tùy thuộc vào sự tương tác của các phân tử tạo thành tinh thể và kích thước của chính tinh thể, hendrite có thể có hình dạng ngẫu nhiên, không đều hoặc ngược lại, có vẻ là một hình hoàn toàn đều đặn, giống như những bông tuyết mà mọi người đều biết đến. Trên thực tế, chúng ta chỉ có thể nói về hình dạng chính xác của những bông tuyết ở quy mô khá lớn (kích thước của chính bông tuyết) và ở quy mô nhỏ thì không có sự đều đặn - điều này phản ánh các quá trình ngẫu nhiên dẫn đến sự hình thành của chúng.

Sự tồn tại của một thang đo tối thiểu (trong trường hợp này có thể

⟦folio 12⟧

Một lớp thực sự tạo thành Nb Ge₂ khi ngưng tụ trên nền lạnh.

có kích thước phân tử bằng hoặc lớn hơn nhiều) dẫn đến tổng số phân tử trong tinh thể (hoặc khối lượng của tinh thể) phụ thuộc vào kích thước của nó theo định luật $N_{molекул} \sim M \sim l^D$. Dựa trên sự phụ thuộc của khối lượng tinh thể đuôi gai vào kích thước của chúng, kích thước của chúng có thể được xác định.

Những hình ảnh rất giống với tinh thể đuôi gai xuất hiện trong quá trình thử nghiệm điện của chất điện môi. Nếu một tia lửa điện mạnh chạm vào một tấm điện môi, trên bề mặt của nó sẽ có một hình vẽ rõ ràng - cái gọi là hình Lichtenberg (được đặt theo tên của nhà vật lý thực nghiệm người Đức G. Lichtenberg (1742-1799), người đã phát hiện ra những hình này). Sự giống nhau giữa hình Lichtenberg và tinh thể đuôi gai không phải là ngẫu nhiên - sự xuất hiện của chúng trên lý thuyết được mô tả bằng các phương trình tương tự.

Kích thước mong manh là một đặc tính rất quan trọng và có thể đo lường được của một hệ thống vật lý. Giá trị này cũng có thể được tính bằng các mô hình lý thuyết khác nhau. So sánh các giá trị được đo và tính toán cho phép bạn quyết định mô hình nào tốt hơn. Ngoài ra, khi tính toán các tính chất vật lý của các hệ mảnh (ví dụ: độ đàn hồi của lưới và các vật liệu rời khác), bạn có thể sử dụng một công cụ toán học được phát triển đặc biệt cho trường hợp này.

Các thuộc tính phân mảnh của khu vực cung cấp nhiều hệ thống từ lâu đã được sử dụng cho các mục đích rất thực tế. Ví dụ, bề mặt của than hoạt tính được sử dụng làm chất hấp thụ (chất hấp thụ) trong mặt nạ phòng độc rất dễ vỡ. Kích thước của bề mặt này lớn hơn 2: nó có hình dạng cực lớn - vô hạn, theo nghĩa tương tự trong đó chiều dài của đường cong Koch là vô hạn) diện tích và các hốc ở mọi tỷ lệ, có khả năng xuất hiện và giữ một cách đáng tin cậy một hạt có kích thước bất kỳ - từ bụi đến phân tử lớn. Bề mặt của nhiều chất xúc tác rắn dùng trong hóa học cũng có tính phân mảnh. Hoạt tính xúc tác của chúng phụ thuộc vào tính chất dễ vỡ của bề mặt, được xác định bằng phương pháp chuẩn bị và chế biến.

Chúng tôi đã làm quen với một số lượng lớn các đối tượng không có chiều. Tôi muốn đặt câu hỏi: chính không gian mà chúng ta đang sống có phải là ba chiều không? Câu hỏi này có thể được trả lời bằng đáp số rất cụ thể. Thực tế là chiều phân mảnh của không gian quyết định hình thức của nhiều định luật vật lý thu hút chúng ta. Ví dụ: số mũ 2 trong mẫu số của định luật Coulomb $F = \frac{1}{4\pi\varepsilon_0} \frac{q_1 q_2}{r^2}$ trên thực tế là.

Hình Lichtenberg.

⟦folio 13⟧

D - 1, trong đó D là kích thước thực của không gian. Phân tích dữ liệu kiểm tra các định luật vật lý, hình thức của nó phụ thuộc vào chiều của không gian, cho thấy chiều của nó khác với 3 không quá $10^{-10}$. Không gian của chúng ta thực ra là “rất ba chiều”.

Thay vì một kết luận

Lịch sử nghiên cứu các hệ thống thực tế khá ấn tượng. Xuất hiện ban đầu như một trò chơi trí tuệ của các nhà toán học thuần túy, những đồ vật này ít được các nhà khoa học tự nhiên quan tâm. Đồng thời, có một số yếu tố ít được hiểu rõ.

Sergey Alekseevich Chaplygin

(Để bắt đầu, xem trang 2)

Sau đó, khi diễn giả kiểm tra cẩn thận các tính toán của mình, họ phát hiện ra rằng Sergei Alekseevich thực sự đã đúng. Có rất nhiều truyền thuyết như vậy.

Vào mùa thu năm 1941, chính phủ lời giải chuyển giao TsAGI cho Kazan và Novosibirsk. Chaplygin bắt đầu đứng đầu chi nhánh Novosibirsk của TsAGI. Trong thời gian ngắn nhất có thể, anh ấy đã cố gắng thực hiện công việc có mục tiêu ở một địa điểm mới. Các dự án lại được phát triển và các phòng thí nghiệm khí động học được xây dựng, đồng thời các công trình khoa học chuyên sâu cũng được thực hiện. Nhưng năm tháng và những gì đã chịu đựng khiến bản thân họ ngày càng cảm thấy nhiều hơn. Ngày 8 tháng 10 năm 1942, Sergei Alekseevich qua đời.

Tên tuổi của Sergei Alekseevich Chaplygin tiếp tục sống trong tác phẩm của các học trò của ông, trong tác phẩm của tất cả các nhà khoa học phát triển và khái quát hóa các ý tưởng của ông.
