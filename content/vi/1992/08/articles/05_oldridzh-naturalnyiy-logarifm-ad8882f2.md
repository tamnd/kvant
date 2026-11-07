---
id: 1992-8-oldridzh-naturalnyiy-logarifm-ad8882f2
issue: kvant_1992_8
year: 1992
number: "8"
title: logarit tự nhiên
authors:
  - Олдридж Б.
rubric: osnovnye-stati
page_first: 17
page_last: 21
page_labels: 15-19
lang: vi
source: kvant_digital
extraction: vision
content_sha256: 1bb256d86ac3f2f486d1bd8c2267dcdbdcadfa64ea4edf1cf7f2b6ba79a3c539
prompt_sha256: draft-1
translated_from: content/ru/1992/08/articles/05_oldridzh-naturalnyiy-logarifm-ad8882f2.md
source_content_sha256: 76865b82b04840ab278fc520d84dab843719414523e42d32475c3e15f0668a0d
translation_model: draft
translation_run: vi-draft-gaps-2026-11-07
translation_quality: draft
---

⟦folio 15⟧

---
running_head:
folio:
---

Bill D. Aldridge là giám đốc điều hành Hiệp hội giáo viên khoa học quốc gia (Mỹ), một trong những người tổ chức và lãnh đạo tạp chí Quantum của Nga-Mỹ.
Bài báo được viết cho học sinh Mỹ và đăng trên tạp chí này vào năm 1990.

W. ALDRIDGE

Tôi tự hỏi “tự nhiên” trong số 2.71828 là gì..?

Tất nhiên, bạn biết logarit là gì - từ này được dùng để biểu thị số mũ của một số nhất định $n$. Hãy chọn cơ số lũy thừa, ví dụ như số 10 và biểu thị $n$ là $n=10^x$; thì số $x$ được viết là $x=\log_{10}n$ (đối với logarit thập phân người ta thường sử dụng ký hiệu $\lg n$). Điều thú vị nhất trong ký hiệu logarit của số là nó đơn giản hóa rất nhiều các phép tính.

Nhà toán học vĩ đại Laplace (1749-1827) đã từng nói: “Việc phát minh ra logarit giúp có thể thực hiện những phép tính do cùng một người thực hiện trong vài ngày và máy tính giờ đây sống lâu gấp đôi” (thời đó có nghề “máy tính” - người làm các phép tính bằng tay). Đây là ví dụ đơn giản nhất: để nhân hai số theo logarit, bạn chỉ cần cộng các số mũ. Tích của 5673 nhân 1347 là bao nhiêu? Nhìn vào bảng logarit thập phân ta thấy $\lg 5673=3,75381$ và $\lg 1347=3,12937$. Do đó, phép nhân Bài toán giống như phép nhân $10^{3,75381}$ với $10^{3,12937}$. Cộng các số mũ lại, chúng ta được $10^{6,88318}$. Quay lại bảng logarit và đếm $\lg n=6,88318$, chúng ta tìm thấy $n$, xấp xỉ bằng $7,6415 \times 10^6$ hoặc $7641500$. Nếu chúng ta nhân hai số một cách đại khái, chúng ta sẽ nhận được 7641531. Như bạn đã nhận thấy, việc sử dụng bảng logarit sẽ gây ra một lỗi nhất định. Điều này là do các giá trị logarit đưa ra trong các bảng đã được tính toán với độ chính xác nhất định (với một số vị trí thập phân nhất định). Tuy nhiên, đối với hầu hết các ứng dụng, độ chính xác tại hiện trường là đủ.

Có thể bạn chưa thấy sự đơn giản hóa nhiều của phép tính trong ví dụ trên, nhưng khi tính các biểu thức phức tạp, đặc biệt là những biểu thức chứa nghiệm, việc sử dụng logarit (và các quy tắc làm việc với chúng) đã dẫn đến sự đơn giản hóa. Tôi dùng từ “cho” vì ngày nay, với sự trợ giúp của máy tính bỏ túi, bạn có thể thực hiện các phép tính trong chưa đầy một giây mà ngay cả khi sử dụng logarit cũng sẽ mất vài giờ hoặc thậm chí vài ngày. Tuy nhiên, thậm chí ngày nay các tính chất quan trọng khác của logarit vẫn được sử dụng trong cả khoa học và công nghệ.

Cơ số 10 (logarit thập phân) gắn liền với việc sử dụng hệ thống số thập phân. Kết quả là tất cả các phụ thuộc logarit đều có cơ số khác nhau. Do đó, logarit còn được gọi là thực hoặc tự nhiên. Không giống như cơ số thập phân, cơ số tự nhiên là số vô tỉ. Nếu vậy thì điều gì là “tự nhiên”?

Con số này được biểu thị bằng chữ cái $e$ và theo quy định, giá trị gần đúng hợp lý của nó là 2,71828 được sử dụng... Mặc dù

⟦folio 16⟧

---
running_head:
folio:
---

Tôi đã nghiên cứu logarit tự nhiên ở cả trường phổ thông và đại học và tính toán số $e$, nhưng tôi thực sự chưa bao giờ hiểu nó đến từ đâu. Cách tính số $e$ có thể được tìm thấy trong nhiều công trình toán học, và con số này luôn được trình bày như một dạng trừu tượng. Đây là những gì tôi cần.

Cuối cùng, rất lâu sau khi học xong, tôi quyết định tự mình tìm ra cách “trích xuất” số $e$ từ thế giới thực. Tôi có thể chọn cho mục đích này quá trình phân rã phóng xạ, hoặc quá trình phóng điện của tụ điện trong mạch điện, hoặc lý thuyết trừu tượng về entropy cho nhiệt động lực học thống kê. Nhưng, mặc dù bản chất tôi là một nhà vật lý, nhưng tôi quyết định khám phá con số $e$ bằng cách sử dụng ví dụ về một hiện tượng sinh học.

Khía cạnh sinh học của sự sinh sản của vi khuẩn

Tôi nghiên cứu quá trình sinh sản của vi khuẩn tụ cầu trong môi trường dinh dưỡng đặc biệt (Staphylococcum 110 agar). Quá trình diễn ra như thế này. Ô bắt đầu tăng kích thước, sau một thời gian, một phân vùng được hình thành trong đó và cuối cùng ô được mở rộng này được chia thành hai ô DAUGHTER hoàn toàn giống hệt nhau. Tất cả các thành phần của ô cũ được phân bổ đều cho hai ô mới. Lần lượt, mỗi tế bào con cũng bắt đầu tăng kích thước, chuẩn bị cho một chu kỳ phân chia mới. Mỗi lần tế bào phân chia, số lượng vi khuẩn lại tăng lên. Quá trình này được gọi là phân hạch ngang nhị phân.

Thời gian sinh sản, tức là thời gian để số lượng vi khuẩn tăng gấp đôi, dao động từ 20 phút đến vài ngày, tùy thuộc vào đặc điểm cụ thể của vi khuẩn và môi trường dinh dưỡng mà chúng sinh sản. Thời gian sinh sản trung bình có thể được xác định bằng cách quan sát một số chu kỳ sinh sản. (Vì việc này đòi hỏi phải có một chiếc microcop mà tôi không có sẵn nên tôi đã lấy các con số từ sổ tay hướng dẫn tương ứng.)

Hóa ra vi khuẩn nhân lên theo cấp số nhân (tăng gấp đôi cứ sau 20 phút) chỉ trong một khoảng thời gian nhất định. Lúc đầu, vi khuẩn phải thích nghi với môi trường (thời gian sinh sản chậm), sau đó quá trình sinh sản của chúng diễn ra theo cấp số nhân. Khi chất dinh dưỡng đã được sử dụng hết, một giai đoạn ổn định bắt đầu và cuối cùng vi khuẩn bắt đầu chết và đường cong mô tả quá trình này giảm mạnh. Tôi hạn chế xem xét giai đoạn tăng trưởng theo cấp số nhân.

Nếu bạn bắt đầu quan sát vào thời điểm các tế bào con đầu tiên vừa hình thành, bạn sẽ nhận thấy rằng chúng nhân lên đồng bộ, ít nhất là đối với một số vi khuẩn, và sau đó bắt đầu mất nhịp. Tuy nhiên, nếu nhân lên một mẫu vi khuẩn ngẫu nhiên, bạn sẽ nhận thấy rằng một số vi khuẩn đã sẵn sàng phân chia, một số mới bắt đầu tăng kích thước và số còn lại đang trong giai đoạn tăng trưởng. Vì tất cả các vi khuẩn đều ở các giai đoạn khác nhau nên bất kỳ vi khuẩn nào được chọn ngẫu nhiên đều có thể bắt đầu phân chia thành các giai đoạn tùy ý.

⟦folio 17⟧

---
running_head:
folio:
---

Nếu có đủ vi khuẩn, quá trình phân chia tế bào diễn ra không đồng bộ và gần như liên tục.

Sinh sản của vi khuẩn
từ quan điểm toán học

Mỗi vi khuẩn tạo ra hai vi khuẩn sau một thời gian nhất định. Lần lượt, hai vi khuẩn con mới bắt đầu phát triển, sau đó cũng phân chia thành hai phần, quá trình sẽ tiếp tục cho đến khi có đủ không gian và chất dinh dưỡng cho vi khuẩn mới.

Nếu ban đầu chúng ta có 5000 vi khuẩn và thời gian sinh sản là 20 phút thì sau 2 giờ sẽ có bao nhiêu vi khuẩn? Giả sử chúng ta bắt đầu quan sát lúc 8 giờ. Lúc 8:20 chúng ta sẽ có 10.000 vi khuẩn, lúc 8:40 chúng ta sẽ có 20.000 vi khuẩn, lúc 9:00 chúng ta sẽ có 40.000 vi khuẩn, lúc 9:20 chúng ta sẽ có 80.000 vi khuẩn, lúc 9:40 chúng ta sẽ có 160.000 vi khuẩn và lúc 10:00, 2 giờ sau, 5.000 vi khuẩn của chúng ta sẽ phát triển thành 320.000. Sẽ có bao nhiêu trong 2 giờ?

Bước tiếp theo là nỗ lực tạo ra một phương trình mô tả mối quan hệ giữa thời gian $t$ và số lượng vi khuẩn $N$ (trong thời gian $t$ từ $N_0$ vi khuẩn, chúng ta thu được $N$ vi khuẩn). (Chúng ta có thể giả sử rằng lúc đầu chúng ta có số lượng vi khuẩn như vậy và trong các giai đoạn phát triển khác nhau nên quá trình phân chia tế bào là ngẫu nhiên và liên tục.) Chúng ta có thể chia thời gian $t$ thành $n$ những khoảng thời gian nhỏ bằng nhau, mỗi phân đoạn như vậy được chỉ định $\Delta t$, tức là chúng ta có thể viết

$$\Delta t = t/n.$$

Hãy để trong mỗi khoảng thời gian $\Delta t$ cổ phiếu $\Delta N$ tế bào. Hãy giả sử rằng $\Delta t = 0,01$ giây và trong thời gian này số lần chia được xác định. Nếu khoảng thời gian này tăng lên, chẳng hạn như lên 0,02 hoặc 0,03 giây, thì số lần chia cũng sẽ tăng gấp 2 hoặc 3 lần. Nếu vào đầu một khoảng thời gian chúng ta có số lượng tế bào nhiều gấp đôi thì vào cuối thời kỳ này số lượng tế bào cũng sẽ gấp đôi. Nói cách khác, số lượng tế bào $\Delta N$, được chia trong một khoảng thời gian $\Delta t$, tỷ lệ thuận với khoảng thời gian này và số lượng tế bào $N$, đó là vào thời điểm bắt đầu của khoảng thời gian được xem xét. Về mặt toán học, sự phụ thuộc này có thể được biểu diễn dưới dạng tỷ lệ

$$\Delta N \sim N \Delta t.$$

Tỷ lệ này có nghĩa là, chẳng hạn, nếu $\Delta t$ hoặc $N$ tăng gấp đôi thì số lượng ô có thể phân chia cũng sẽ tăng gấp đôi và nếu một trong các thành phần bị giảm đi một nửa thì số lượng ô cũng sẽ giảm đi một nửa.

Bằng cách đưa ra hệ số tỷ lệ $k$ và viết tỷ lệ này dưới dạng đẳng thức, tôi nhận được

$$\Delta N = kN \Delta t.$$

Như tôi đã đề cập, có một số lượng rất lớn $n$ khoảng thời gian rất nhỏ $\Delta t$. Với mỗi khoảng thời gian như vậy, chúng ta có thể viết phương trình xác định số lượng vi khuẩn mới $\Delta N$. Đối với đoạn đầu tiên

$$\Delta N = kN_0 \Delta t,$$

trong đó $N_0$ là số lượng vi khuẩn khi bắt đầu khoảng thời gian đầu tiên, tức là số lượng tế bào ban đầu.

Số lượng vi khuẩn ở cuối khoảng thời gian đầu tiên là $N_0 + \Delta N$ và nếu chúng ta sử dụng các đẳng thức trước đó thì số lượng vi khuẩn có thể được viết là

$$N_1 = N_0 + kN_0 \Delta t = N_0(1 + k \Delta t).$$

Bây giờ tôi phải xác định số lượng vi khuẩn vào cuối khoảng thời gian thứ hai. Sự phát triển của vi khuẩn $\Delta N$ một lần nữa phải tỷ lệ thuận với số lượng vi khuẩn ban đầu $N_1$ và độ dài của khoảng thời gian. Sử dụng lại hệ số tỷ lệ $k$, chúng ta thu được phương trình về sự phát triển của vi khuẩn trong khoảng thời gian thứ hai:

$$\Delta N = kN_1 \Delta t.$$

⟦folio 18⟧

---
running_head:
folio:
---

Rõ ràng, tổng số vi khuẩn ở cuối khoảng thời gian thứ hai là số lượng vi khuẩn ở đầu khoảng thời gian này cộng với sự phát triển của vi khuẩn trong khoảng thời gian này:
$$N_2 = N_1 + kN_1\Delta t = N_1(1 + k\Delta t) = N_0(1 + k\Delta t)^2.$$
Bây giờ, tôi chắc chắn rằng bạn đã đồng ý rằng bước tiếp theo là xác định số lượng vi khuẩn vào cuối khoảng thời gian thứ ba. Đến đầu thời kỳ thứ ba có $N_2$ vi khuẩn nên sự phát triển của vi khuẩn được viết là
$$\Delta N = kN_2\Delta t.$$
Như trước, số lượng vi khuẩn ở cuối khoảng thời gian thứ ba là $N_2 + \Delta N$. Vì vậy chúng tôi có
$$N_3 = N_2 + kN_2\Delta t = \ldots = N_0(1 + k\Delta t)^3.$$
Tất nhiên, dựa trên những tính toán này, bạn đã hiểu phương pháp lời giải bài toán, và, veroytono, bạn khá mệt mỏi với nó. Tuy nhiên, bây giờ chúng ta có thể bắt đầu khái quát hóa kết quả, điều này luôn tốt.
Nếu tiếp tục tính số vi khuẩn vào cuối mỗi khoảng thời gian, chúng ta thấy con số này bằng số lần vi khuẩn $(1 + k\Delta t)$. Di chuyển tuần tự từ khoảng thời gian này sang khoảng thời gian khác cho đến thời điểm ban đầu, chúng ta thu được phương trình sau cho số lượng vi khuẩn ở cuối khoảng thời gian $n$-th:
$$N_n = N_0(1 + k\Delta t)^n.$$
Giá trị $N_n$ là tổng lượng vi khuẩn thu được sau thời gian $t$. Chúng tôi chia thời gian $t$ thành các khoảng $n$ có độ dài $\Delta t$. Do đó, $t = n\Delta t$ và $\Delta t = t/n$. (Tôi xin lỗi vì đã lặp lại một cách rõ ràng; tuy nhiên, mục tiêu của tôi là trình bày đầy đủ chuỗi kết luận của mình, vì vậy tôi vẫn giữ nguyên những điểm thường bị bỏ qua.) Vì vậy, bằng cách thay thế $\Delta t$ cùng với giá trị của nó từ đẳng thức trước đó, tôi đã cải thiện được
$$N_n = N_0(1 + kt/n)^n.$$
Biểu thức $(1 + kt/n)^n$ có thể được mở rộng thành chuỗi sinh học:
$$\left(1 + \frac{kt}{n}\right)^n = 1 + n \frac{kt}{n} + n(n-1)\frac{(kt/n)^2}{2!} + n(n-1)(n-2)\frac{(kt/n)^3}{3!} + \ldots.$$
Nếu tích phân $\Delta t$ đủ nhỏ thì thời gian $t$ bao gồm một số lượng lớn các tích phân như vậy. Chúng tôi muốn tính tổng các số hạng của chuỗi sinh học này cho $n$ rất lớn. Đối với các giá trị đủ lớn của $n$, mọi thuật ngữ trong phần mở rộng này đều được đơn giản hóa đáng kể. Điều này là do thực tế là tất cả các số hạng bao gồm $n$, cũng như $n(n-1)(n-2)$, đều trở thành lũy thừa của $n$, trong trường hợp này chỉ đơn giản là $n^3$. Và nếu vậy thì chúng đều triệt tiêu lũy thừa $n$ thành các biểu thức có ý nghĩa $(kt/n)$, và số mũ của lũy thừa luôn trùng nhau. Vì vậy, giới hạn của chuỗi biomial của chúng tôi là
$$1 + kt + \frac{(kt)^2}{2!} + \frac{(kt)^3}{3!} + \ldots + \frac{(kt)^m}{m!} + \ldots.$$
Vì vậy, số lượng vi khuẩn thu được trong thời gian $t$ có thể được biểu diễn dưới dạng
$$N_n = N_0\left(1 + kt + \frac{(kt)^2}{2!} + \frac{(kt)^3}{3!} + \ldots + \frac{(kt)^m}{m!} + \ldots\right).$$
Giả sử rằng $kt = 1$, thay thế giá trị này vào chuỗi của chúng tôi và, ví dụ: đối với $m = 8$, chúng tôi nhận được
$$1 + 1 + 1/2 + 1/6 + 1/24 + 1/120 + 1/720 + 1/5040 + 1/40320,$$
hoặc ở dạng thứ mười
$$1 + 1 + 0,5 + 0,166666667 + 0,041666667 + 0,008333333 + 0,0013888889 + 0,0001984127 + 0,0000248016.$$
Khi tôi cộng tất cả những con số này lại, nó ra 2,71828... Eureka! (Hoặc có lẽ sẽ đúng hơn khi nói “déjà vu” - “Tôi đã thấy cái này ở đâu rồi”?)

⟦folio 19⟧

---
running_head:
folio:
---

Nhỏ gọn, tiện lợi,
hằng số không định kỳ

Điều thú vị nhất ở đây là nếu bạn đặt $kt=2$ thì tổng của chuỗi này sẽ là 7,389056..., chính xác bằng $(2,71828\dots)^2$. Nếu $kt=3$, thì tổng của chuỗi này bằng lập phương của số 2.71828..., v.v. Phân số tuyệt đối không tuần hoàn vô hạn này, mà chúng ta nhận được làm cơ số của lũy thừa, thậm chí không phải là một số hữu tỉ. Hãy gọi số này là "e". (Thật đẹp và phi lý phải không?) Giá trị của số này (tối đa 16 chữ số) là 2,718281828459045. Khi đó phương trình của chúng ta về số lượng vi khuẩn được tạo ra trong thời gian $t$ trở nên rất đơn giản:

$$N=N_0 e^{kt}.$$

Bây giờ chúng ta hãy định nghĩa (như chúng ta đã làm một lần) logarit tự nhiên là lũy thừa mà số $e$ phải tăng lên để thu được số đã cho. (Tương tự như cách ký hiệu logarit cơ số 10 là lg, dạng viết tắt của logarit cơ số $e$ là ln.) Viết lại phương trình sinh sản của vi khuẩn ở dạng logarit, ta có

$$kt=\ln(N/N_0),$$
hoặc theo thời gian $t$ —
$$t=1/k \ln(N/N_0).$$

Phương trình cuối cùng cho thấy sẽ mất bao lâu để lượng vi khuẩn $N_0$ ban đầu trở thành $N$ vi khuẩn. Để sử dụng đẳng thức này, bạn sẽ cần một bảng logarit tự nhiên, nhưng các bảng cũng được đưa ra trong sách hướng dẫn và hầu như tất cả các máy tính điện tử đều có thể tính logarit tự nhiên.

Tất nhiên, tôi rất hài lòng khi mọi tính toán của mình đã hoàn thành xuất sắc và tôi đã tự mình phát hiện ra mối liên hệ giữa cơ số logarit tự nhiên - số 2,71828... - và hiện tượng của thế giới thực. Tuy nhiên, sẽ không có chuyện gì xảy ra nếu tôi không tự mình quyết định rằng có điều gì đó không ổn ở đây. Vì vậy, nếu điều gì đó có vẻ vô nghĩa đối với bạn, đừng bỏ qua nó và đừng xấu hổ, nhưng hãy tìm hiểu xem, cho dù đối với ai đó nó có vẻ bận rộn tầm thường đến mức nào.

Bản dịch từ tiếng Anh của I. Vakhurina

Những người tạo ra thiên văn học mới

(Xem phần đầu ở trang 10)

từ những ảo tưởng của họ mà còn đi đến kết luận cuối cùng. Tuy nhiên, lệnh sau đó ngay lập tức được thay thế bằng việc quản thúc tại gia tại Villa MonteRivalto trong giáo xứ Arcetri. Tại đây Galileo qua đời vào ngày 8 tháng 1 năm 1642 vì một cơn sốt suy nhược. Hơn nữa, cái chết đã không hòa giải được nhà thờ với anh ta; không có bài phát biểu tang lễ nào được thực hiện tại mộ ông, thi hài ông không được phép đặt trong hầm mộ của gia đình Galilev, và không một tượng đài hay bia mộ nào được phép lắp đặt trên mộ ông. Chỉ một trăm năm sau, Galileo được vinh danh trong ngôi mộ của Nhà thờ Santa Croce ở Florence, bên cạnh ngôi mộ của Michelangelo, xứng đáng để tưởng nhớ ông.

Có thể mô tả rất rõ sự sáng tạo khoa học của Kepler và Galileo - họ đã tạo ra một ngành thiên văn học mới. Trong lịch sử văn hóa, trong lịch sử biến đổi thế giới quan, chúng gắn bó với nhau và không thể tách rời; họ cũng chuẩn bị cho sự kết hợp cuối cùng giữa cơ học và thiên văn học do Newot thực hiện, người đã tuyên bố rằng ông “đứng trên vai những người khổng lồ”.
