---
id: 1982-5-tihomirov-aerodinamicheskaya-zadacha-nyutona-8cb1bbc2
issue: kvant_1982_5
year: 1982
number: "5"
title: Khí động học bài toán Newton
authors:
  - Тихомиров В. М.
rubric: osnovnye-stati
page_first: 13
page_last: 20
page_labels: 11, 12, 13, 15, 16, 18
tag: XRGN
lang: vi
source: kvant_digital
extraction: vision
content_sha256: 86ee9034c47721eee41117ce0ab654b393f872748fc7039820a1b23fed4bb404
prompt_sha256: draft-1
translated_from: content/ru/1982/05/articles/06_tihomirov-aerodinamicheskaya-zadacha-nyutona-8cb1bbc2.md
source_content_sha256: 34da1702781813b1374252679f69c6c67da865ac3f561fcd467bed2070eb1ddc
translation_model: draft
translation_run: vi-draft-2026-10-31
translation_quality: draft
---

⟦folio 11⟧

V. Tikhomirov

Khí động học bài toán Newton

Thiên tài có mắc sai lầm không? Thông thường, khi hỏi một câu hỏi như vậy, họ sẽ khẳng định đáp số. Có điều gì đó khẳng định trong nhận thức rằng ngay cả những thiên tài cũng có xu hướng lạc lối - họ viết về sai lầm của các thiên tài một cách hết sức nhiệt tình. Đây là một ví dụ. L. Yang, một nhà toán học xuất sắc, người có đóng góp đáng kể cho sự phát triển của phân tích toán học, là tác giả cuốn sách “Bài giảng về phép tính biến phân và lý thuyết điều khiển tối ưu”, M., “Mir”, 1974. Đây là một cuốn sách rất thú vị và độc đáo *). Nó chứa đựng những lập luận triết học của tác giả, đề cập đến nhiều chủ đề, đôi khi xa rời toán học. Đối với câu hỏi “Thiên tài có mắc sai lầm không?” Young đáp lại Newton bằng một lời khẳng định nảy lửa đáp số. Chúng ta. 42 của cuốn sách được đề cập, ông viết: "Newton đã xây dựng lý thuyết biến thiên bài toán về một vật thể quay chịu ít lực cản nhất trong chất khí. Định luật lực cản vật lý mà ông ấy thích là vô lý, do đó, bài toán mà ông ấy đặt ra không có lời giải (hình càng có khía, lực cản càng ít)... Nếu kết luận của Newton ít nhất là gần đúng, thì chúng ta sẽ không cần những thí nghiệm đắt tiền trong hầm gió."

bài toán này là gì và những lời trên đúng như thế nào? Điều này sẽ được thảo luận thêm.

Khí động học bài toán Newton

Năm 1687, Newton xuất bản “Các nguyên lý toán học của vật lý tự nhiên”. Khó có tác phẩm văn học khoa học nào có thể so sánh được với cuốn sách này - trong đó Newton đã định mệnh khám phá ra hệ thống của thế giới. Lagrange gọi tác phẩm này là “tuyệt vời

*) Không dành cho học sinh. (Ghi chú của biên tập viên)

⟦folio 12⟧

công trình vĩ đại nhất của trí tuệ con người."
Thảo luận về các vấn đề liên quan đến lực cản tác dụng lên các vật thể vật chất bởi môi trường mà chúng chuyển động, Newton, ít nhất, đã đưa ra cụm từ sau: “Khi hình DNFG là một đường cong mà nếu từ bất kỳ điểm N nào của nó chúng ta hạ thấp trục phân phối lại NM và từ một điểm G cho trước vẽ một đường thẳng GR song song với tiếp tuyến của đường cong tại điểm N và cắt trục tại điểm R thì tỷ lệ sẽ diễn ra. MN:GR=GR²:(4BR·GB²), thì vật thể hình thành khi đường cong này quay quanh trục AB, khi di chuyển trong môi trường hiếm nêu trên theo hướng từ A đến B, sẽ chịu ít lực cản hơn bất kỳ vật thể quay nào khác được mô tả trên cùng một đường thẳng và chiều rộng”*) (Hình 1).

Cụm từ của Newton chỉ thu hút sự chú ý của những người cùng thời với ông sau khi I. Bernoulli viết bài toán nổi tiếng về brachistochrone vào năm 1696 (ví dụ, xem «Kvant», 1975, số 12 hoặc cuốn sách “Cyclonda” của M., “Nauka”, 1980). Bài toán brachistochrone, chứ không phải bài toán Newton, được dự định trở thành người sáng lập ra một hướng mới trong toán học sẽ sử dụng biến thể được đặt tên của phép tính.

Liên quan đến brachistochrone bài toán Newoton đã đảm nhận vị trí của Cô bé Lọ Lem bất hạnh: bằng cách nào đó cô ấy bị tránh mặt, cô ấy hiếm khi được nhớ đến, và chỉ khi đó, như một quy luật, mới kể về sự ảo tưởng của một thiên tài. Nhưng, giống như Cô bé Lọ Lem, bài toán Newton đã làm theo cách của mình.

*) Văn bản gốc của Newoton được sao chép lại trong cuốn sách “Điều khiển tối ưu” của V. M. Alekseev, V. M. Tikhomirov, S. V. Fomin. (M., “Nauka”, 1979). Bản dịch “Gọi toán học” đã được xuất bản trong tuyển tập các tác phẩm của Viện sĩ A. N. Krylov. (M. - Leningrad, Nhà xuất bản Viện Hàn lâm Khoa học Liên Xô, 1937, tập 7). Đoạn văn được trích dẫn ở tr. 430. Chúng tôi đã điều chỉnh lại một chút. Hình 1 là bản sao của hình từ “Toán học được gọi”. Đúng, chúng tôi đã sắp xếp nó “từ trên xuống dưới” chứ không phải “từ trái sang phải”; Ngoài ra, trên hình 1 còn có thêm những đường nét và chữ đầy màu sắc do chúng tôi vẽ; chúng ta sẽ gặp chúng sau này.

Cơm. 1.

Chúng ta hãy cố gắng hiểu kế hoạch của Newton.

Khi thiết kế tàu, vỏ sò, ngư lôi hoặc tên lửa, đương nhiên người ta sẽ mong muốn tạo cho chúng một hình dạng linh hoạt để chúng gặp ít lực cản hơn trong quá trình di chuyển. Newton viết: “Bạn có thể so sánh lực cản của các vật thể với nhau và tìm ra những lực cản có liên quan nhiều nhất đến sự tiếp tục chuyển động của chúng trong một môi trường có lực cản”. Nhưng, chẳng hạn, nếu một con tàu không thể có quá nhiều sự đối xứng ở thân tàu, thì việc làm đầu tên lửa, đạn pháo và ngư lôi có mặt cắt ngang là điều đương nhiên; nói cách khác, thật hợp lý khi cho chúng hình dạng của vật quay. Nhưng chính xác thì cái nào - hình cầu, hình nón, hình trục chính hay cái gì khác? Một câu hỏi như vậy không thể được trả lời nếu không tính toán, không có lời giải một số bài toán toán học cho mức tối đa và tối thiểu. Đây chính xác là bài toán mà Newoton đặt ra (và giải quyết trong cụm từ trên).

Là phép tính gần đúng đầu tiên, bài toán được đặt như thế này.

Vấn đề. Tìm một vật quay có chiều dài và chiều rộng cho trước chịu lực cản khi chuyển động trong một môi trường nhất định.

Giải thích. Mỗi thuật ngữ liên quan đến sự hình thành (chiều dài, chiều rộng, chuyển động và phương tiện

⟦folio 13⟧

có), yêu cầu mô tả đầy đủ. Newton tưởng tượng một vật thể quay giống nhau từ phía sau và phía trước, nghĩa là đối xứng với một mặt phẳng đi qua tâm của trục quay và vuông góc với trục này. Do đó, diinana của một cơ thể là chiều dài của nó dọc theo trục quay và bán kính của phần giữa là chiều rộng của cơ thể. Do đó, ở mọi khoảng cách, chúng ta có thể giới hạn bản thân chỉ ở một nửa cơ thể, đó là điều chúng ta làm tiếp theo. Theo Newton, chúng ta sẽ giả sử rằng chuyển động do một vật thực hiện là chuyển động đều với tốc độ không đổi $v$.

Bây giờ - về môi trường - đây là câu hỏi tế nhị và dễ chấp nhận nhất. Môi trường được Newton mô tả có phần khác thường; anh ấy gọi nó là hiếm. Newton tưởng tượng ra một môi trường hiếm có “gồm các phần bằng nhau, nằm tự do ở những khoảng cách bằng nhau”. Các hạt đứng yên có khối lượng cố định $m$ và là những quả bóng đàn hồi tuyệt đối. Newton cũng coi bản thân vật thể là đàn hồi tuyệt đối, sao cho mỗi quả bóng khi va chạm với một vật thể đang chuyển động sẽ bật trở lại theo định luật “góc tới bằng góc phản xạ”.

Sau những lời giải thích trên, chúng ta có thể diễn đạt chính xác ngay lập tức và bắt đầu giải bài toán tổng quát bài toán, nhưng trước tiên chúng ta sẽ nghiên cứu cách đơn giản hơn. Nhân tiện, bản thân Newton cũng bắt đầu với bài toán đơn giản hơn này.

Bài toán về một kết thúc thành công. Với đáy và chiều cao của một hình nón thành công, hãy tìm hình nón chịu ít lực cản nhất khi di chuyển trong một môi trường hiếm gặp.

Chính thức hóa bài toán về một kết thúc thành công

Vừa rồi bài toán được hình thành bằng lời nói, không có công thức. Bây giờ chúng ta phải thực hiện quá trình chuyển đổi từ ngôn ngữ thông thường sang ngôn ngữ toán học. Quá trình chuyển đổi này được gọi là chính thức hóa.

Vậy để hình nón thành công có chiều cao bằng $H$ và bán kính

Cơm. 2.

đế trên $R$ (Hình 2)*.

Newton viết: “Vì tác dụng của môi trường lên vật là như nhau... cho dù vật đó chuyển động trong môi trường đứng yên hay các hạt của môi trường tấn công vật thể ở trạng thái nghỉ với cùng vận tốc thì chúng ta sẽ xem xét vật thể đang đứng yên”. Chúng ta sẽ làm tương tự: để hình nón bất động, chúng ta sẽ giả sử rằng môi trường đang “chuyển động” lên nó từ dưới lên với tốc độ $v$.

Bề mặt của hình nón đã va chạm với các quả bóng của môi trường bao gồm đáy dưới và mặt bên của nó. Đầu tiên, hãy tính lực cản của đế dưới. Hãy biểu thị bán kính của nó bằng $x$. Trong một đơn vị thời gian, những quả bóng ban đầu nằm trong một hình trụ có đáy bằng đáy dưới và chiều cao bằng $v$ sẽ va chạm với đế này. Thể tích của hình trụ này $V_0$ bằng $\pi x^2 v$. Gọi $q$ là mật độ của môi trường. Khi đó số hạt chạm vào đáy dưới trong một đơn vị thời gian sẽ bằng $N_0 = \frac{\rho}{m} V_0 = \frac{\rho}{m} \pi x^2 v$. Mỗi hạt sau khi di chuyển ra khỏi đáy dưới sẽ thay đổi vận tốc theo hướng ngược lại, tức là nó sẽ nhận được một mức tăng động lượng bằng -2mv. Theo định luật III Newton, hình nón sẽ nhận được mức tăng ngược lại

*) Hình 2 thường xuyên, được tô màu đen, nằm trong “Nguyên lý toán học”.

⟦folio 15⟧

Bây giờ chúng ta cố gắng tìm $m$ và $\hat{z}$ cần thiết. Nếu bất đẳng thức $az^2+2bz+c \geq 0$ đúng cho tất cả $\hat{z}$ và cả $\hat{a}^2+2b\hat{z}+c=0$, thì nó sẽ dẫn đến $D=b^2-ac=0$ và $z=-b/a$ (hãy nghĩ kỹ điều này!). Chúng tôi có $a=(1-m)$, $b=-H$, $c=H^2+R^2(1-m)$. Phương trình $D=0$ dẫn đến sự tương ứng
$$D=H^2-(1-m)(H^2+R^2(1-m)) \Rightarrow (R^2m^2-(2R^2+H^2)m+R^2)=0,$$
Ở đâu
$$m=\frac{2R^2+H^2-H\sqrt{4R^2+H^2}}{2R^2}.$$
Dấu + đã bị loại bỏ hoặc $m$ mà chúng tôi đang tìm kiếm, như đã được thiết lập, phải nhỏ hơn một. Kế tiếp,
$$\hat{z}=-b/a=H/(1-m) = \sqrt{R^2+(H/2)^2}+H/2(>H).$$
(5)
Kết quả là, chúng tôi đã tìm thấy $m<1$ và $\hat{z}>H$ sao cho phân biệt của phương trình $z^2(1-m)-2zH+H^2+R^2(1-m)=0$ bằng 0 và nó có một nghiệm duy nhất $\hat{z} \geq H$, tức là $h(z) \geq m, h(\hat{z})=m$. Vấn đề 1' lời giải.
Hãy cho đi đáp số bài toán về một hình nón cụt có hình dạng mà Newton đã đặt cho nó: “Nếu trên một đế hình tròn CEBH (Hình 2), được mô tả từ tâm $O$ bán kính $OC$, cần phải xây dựng một CBFG hình nón cụt như vậy với chiều cao $OD$, một số lực cản sẽ nhỏ hơn lực cản của bất kỳ hình nón cụt nào khác, được xây dựng trên cùng một đế và chiều cao và di chuyển dọc theo trục $OD$ sang một bên $D$, sau đó chia chiều cao $OD$ tại điểm $Q$ một nửa, tiếp tục $OQ$ ĐẾN $S$ để nó sẽ như vậy $QS=QC$. $S$ và sẽ là đỉnh của hình nón mong muốn, bị cắt cụt.”
Dễ dàng kiểm chứng rằng hình dạng hình học cho bởi đáp số Newton hoàn toàn tương ứng với hình dạng tương tự có trong công thức (5).
Cuộc thảo luận. Hóa ra hình nón có ít lực cản nhất thực sự bị cắt cụt, cùn và không nhọn. Newton còn đi xa hơn nữa. Nó hướng chiều cao $H$ về 0. Trong trường hợp này, $\hat{z}$ lao về phía $R$ và góc, khi hình nón bị cắt cụt, lao về phía $45^\circ$.

Dựa trên điều này, Newton đưa ra nhận xét rằng nên thay thân hình bầu dục bằng thân phẳng, tức là nên làm một bệ tròn phẳng phía trước, tạo thành một góc từ các cuộn dây thẳng đến bề mặt của bệ bằng $135^\circ$. Newton nói: “Tôi tin rằng nhận xét này có thể có ích trong việc đóng tàu”.

Bài toán Newton cho đường đứt đoạn
Chúng ta hãy tiến thêm một bước áp chót tới định luật lời giải tổng quát bài toán của Newton. Chúng ta sẽ không xem xét bất kỳ biểu thức cong nào mà chỉ xem xét các đường đứt nét. Để thực hiện việc này, hãy chia đoạn $[0, R]$ của trục $Ox$ thành $N$ các phần bằng nhau bằng cách sử dụng các điểm chia
$$x_0=0, x_1=\frac{R}{N}, x_2=\frac{2R}{N}, \dots, x_N=R$$
và biểu thị tọa độ các đỉnh tương ứng của đường đứt nét bằng $y_0, y_1, \dots, y_N$ (Hình 4). Chúng ta sẽ đề xuất rằng đường đứt nét bắt đầu tại điểm $(x_0, y_0)=(0,0)$, sau đó có thể đi dọc theo trục $Ox$ (tức là $y_0=y_1=\dots=y_s=0$ đối với một số $s$, $0 \leq s \leq N$), sau đó đơn điệu đi lên trên
$$y_s<y_s+1 \leq y_s+2 \leq \dots \leq y_N$$
và đi tới điểm $(x_N, y_N)=(R, H)$. Các dòng đáp ứng các yêu cầu này được gọi là có thể chấp nhận được.
Hỏi tại sao cần phải có điều kiện đơn điệu (6). Nếu nó bị vi phạm, các biểu thức sẽ tạo thành các “vết khía” trên bề mặt, từ đó các quả bóng neoctor sẽ bị phản xạ nhiều lần, làm tăng lực cản (và làm mất tính toán của nó một cách vô vọng).
Bây giờ chúng ta hãy tìm lực cản của môi trường $F$ đối với bề mặt, ob-

⟦folio 16⟧

một lỗi cho phép, được phát triển bởi sự quay. Để làm điều này, áp dụng công thức (1) cho mỗi liên kết của nó, chúng ta biểu thị cosφк thông qua tọa độ của các đỉnh (xk,yk), (xk+1,yk+1) (xem Hình 4) và tính tổng. Hóa ra

$$F_{\pi} = 2K \sum_{k=1}^{N-1} \frac{x_k+x_{k+1}}{2} \cdot \frac{\Delta x_k}{1 + \left( \frac{\Delta y_k}{\Delta x_k} \right)^2},$$

trong đó chúng tôi biểu thị $K = 2\pi qv^2$, $\Delta y_k = y_{k+1} - y_k$ và $\Delta x_k = x_{k+1} - x_k = \frac{R}{N}$.

Chúng tôi sẽ không giải quyết bài toán việc tối thiểu hóa tham chiếu (7), mặc dù điều này chỉ yêu cầu các phương tiện tính toán vi phân mà bạn đã biết - lời giải rất phức tạp về mặt kỹ thuật và đối với những gì tiếp theo, chúng tôi chỉ quan tâm đến chính công thức bài toán và công thức (7).

Công thức hóa của Newton bài toán

Bây giờ chúng ta có thể tiếp cận bài toán của Newton trong trường hợp tổng quát, khi bề mặt quay được hình thành không phải bởi một đoạn hoặc một đường gãy mà bởi một đường cong $y=f(x)$. Chúng ta có thể xem xét những đường cong nào? Tất nhiên, đường cong phải bắt đầu tại điểm (0,0), sau đó có thể đi dọc theo trục $Ox$ đến một điểm nào đó (b, 0) (trong đó $b \geq 0$), sau đó tăng dần lên và kết thúc tại điểm (R, H). Ngoài ra, chúng ta sẽ yêu cầu hàm $f$ khả vi tại tất cả các điểm $x \in [0,R]$, ngoại trừ điểm $b$, trong đó góc tiếp xúc của đường cong với mặt cắt ngang phải bằng $135^\circ$ (hãy nhớ nhận xét của Newton “không hữu ích trong việc đóng tàu”). Khi đó điều kiện đơn điệu có thể được viết là

$$f'(x) \geq 0 \quad x \in [0,R], \quad x \neq b.$$

Chúng ta sẽ gọi đường cong $y=f(x)$ thỏa mãn các điều kiện này là chấp nhận được.

Chúng ta hãy tìm lực cản của môi trường tác dụng lên vật thu được bằng cách quay đường cong cho phép $y=f(x)$ quanh trục $Oy$. Hãy lấy một số đủ lớn hơn $N$ và xây dựng một đường gãy có thể chấp nhận được bằng cách đặt $y_k=f(x_k)$. Đường gãy này sẽ khác một chút so với đường cong của chúng tôi, vì vậy chúng tôi loại trừ việc sử dụng $F$ và nó sẽ khác một chút so với tham chiếu được tìm thấy trước đó $F_\pi$ (xem (7)).

Bây giờ chúng ta hãy nhớ lại tổng tích phân và nhận thấy rằng $\Delta y_k / \Delta x_k \approx f'(x_k)$, không khó để tin rằng với sự gia tăng không giới hạn của số $N$ thì tổng (7) sẽ tiến tới tích phân

$$2K \int_0^R \frac{xdx}{1 + (f'(x))^2} = F,$$

thể hiện sức mạnh của sự phản kháng đối với điều mong muốn. Vì vậy, chúng ta đã đi đến công thức tổng quát bài toán của Newton:

Trong số tất cả các hàm được chấp nhận $y=f(x)$ hãy tìm một hàm mà tích phân của nó

$$\int_0^R \frac{xdx}{1 + u^2}$$

(tối thiểu nếu $u = f'(x) \geq 0$).

Lời giải bài toán Newton

Tất nhiên, bạn chưa từng thấy bài toán tương tự trong sách giáo khoa ở trường. Do đó, chúng ta sẽ bắt đầu với trợ động từ đơn giản hơn bài toán:

Trong số tất cả các hàm được chấp nhận $y=f(x)$ hãy tìm một hàm mà biểu thức

$$\frac{x}{1 + u^2} + 2cu$$

(tối thiểu (với tất cả $x \in [0,R]$), nếu $u = f'(x)$ và $c > 0$ không đổi).

Tại sao lại giải quyết điều này bài toán? Nhưng tại sao: nếu tìm thấy lời giải $y=f(x)$, $\bar{u} = f'(x)$ của nó, thì đối với bất kỳ hàm chấp nhận được nào khác $y=f(x)$ thì bất đẳng thức đúng (với tất cả $x \in [0,R]$)

$$\frac{x}{1 + u^2} + 2cu \geq \frac{x}{1 + \bar{u}^2} + 2c\bar{u},$$

lấy tích phân ngắn hơn $[0,R]$, tính đến $u = f'(x)$, chúng ta nhận được

$$\int_0^R udx = \int_0^R \bar{u} dx = H,$$

Ở đâu

$$\int_0^R \frac{xdx}{1 + u^2} \geq \int_0^R \frac{xdx}{1 + \bar{u}^2};$$

có nghĩa là $\bar{f}(x)$ (lời giải phụ bài toán (9)) cũng là nghiệm của bài toán (8) của Newton!

Và câu phụ bài toán, như bạn có thể đã đồng ý, không quá khó giải. Đáp số sẽ là một đường đi dọc theo trục $Ox$ đến điểm ngắt $b=4c$ rồi dọc theo đường cong, điểm $(x; y)$ của điểm này được biểu thị bằng công thức

⟦folio 18⟧

Cơm. 6.

Vào thời điểm đó, người ta tin rằng nó có liên quan đến phép tính biến phân: ví dụ: A.N. Krylov, trích dẫn câu nói của Newton đã đọc ở phần đầu, kèm theo đó là những lời sau: “Tuyên bố này của Newton luôn áp dụng cho phép tính biến phân”. Tiếp theo, anh ta hình thức hóa bài toán của Newton (hơi khác một chút so với chúng ta - anh ta chỉ di chuyển lựa chọn, giống như của Newton, xuống dưới) và đi đến (nếu trong biểu thức của anh ta, chúng ta thay thế $y$ bằng $x$ và $x$ bằng $y$) thành bài toán về việc cực tiểu hóa tích phân

$$\int_0^R \frac{xdx}{1 + (f'(x))^2}$$

có tính đến các điều kiện ban đầu $f(0) = 0$, $f(R) = H$. Thực sự, việc giảm thiểu tích phân như vậy thuộc về phép tính biến phân, nhưng không có điều kiện bổ sung $f'(x) \geq 0$ để giảm thiểu giá trị tích phân này. Điều này đã được Legendre ghi nhận 100 năm sau khi phát hành “Principles”. Thật vậy, chúng ta hãy chọn $f$ một đường gãy bao gồm các liên kết rất lớn (như đường được hiển thị trong Hình 6). Khi đó $(f'(x))^2$ sẽ rất lớn và tích phân (13) sẽ nhỏ; Nói chung, nó có thể được làm nhỏ như mong muốn. Thực sự, hóa ra, theo Young: “Hồ sơ càng có nhiều khía thì càng ít lực cản!” Nhưng chúng tôi đã lưu ý rằng theo công thức Newton về bài toán, cần phải yêu cầu $f$ phải đơn điệu, nghĩa là sự tương ứng $f'(x) \geq 0$ phải được thỏa mãn.

Việc tối thiểu hóa tích phân (13) theo điều kiện (14) không liên quan đến phép tính các biến phân. Các ràng buộc loại (14), áp đặt cho nhiệm vụ cực tiểu hóa tích phân loại (13), chỉ được đề cập đến trong lý thuyết vào giữa thế kỷ 20.

Vì vậy, bài toán của Newton, không phải là biểu thức đã cho đầu tiên của phép tính, hóa ra lại là biểu thức đã cho đầu tiên của một nhánh mới của toán học - lý thuyết điều khiển tối ưu.

4. Sự phê phán và xin lỗi của Newton. Chúng tôi đã xác định được hai lời buộc tội chống lại Newton: sai là bài toán của Newton không có lời giải (do ông ấy tìm ra), sai là “càng có nhiều khía thì càng ít phản kháng” - thực tế này không tuân theo các giả định của Newton. Nhưng có lẽ vẫn đúng khi cho rằng “định luật vật lý mà ông chấp nhận là vô lý?” Phương tiện hiếm này là gì? Liệu một môi trường như vậy có tồn tại? Chẳng phải là vô lý sao khi cơ thể ít phản kháng nhất lại bị cùn? Ai đã từng nhìn thấy ngư lôi hoặc gói hàng có đầu cùn chưa?

Công bằng mà nói, phải nói rằng cả nước, không khí xung quanh chúng ta, cũng như bất kỳ môi trường khí hay lỏng nào quen thuộc với chúng ta đều không có những đặc tính của môi trường hiếm Newton. Tuy nhiên, các giả định vật lý của Newton và bản thân khí động học bài toán của ông hóa ra lại đi đầu trong khoa học hiện đại vào giữa những năm 1950, khi kỷ nguyên của máy bay siêu thanh và siêu cao bắt đầu. “Ở trên đó”, môi trường trở nên “hiếm có”. Và việc Newton thay thế những con ngựa cùn hóa ra lại rất “vô dụng” trong việc chế tạo tàu, cụ thể là tàu vũ trụ. Cuối cùng,

5. Thiên tài có sai không? Tất nhiên là họ sai. Tuy nhiên, tôi đã có thể thuyết phục bạn rằng việc sản xuất và khí động học lời giải bài toán không phải là sai lầm của một thiên tài, mà là sản phẩm của anh ấy, cho phép anh ấy chạm đến cuộc sống và các vấn đề của chúng ta sau ba thế kỷ. Điều này đáng để suy ngẫm.

Nói một cách dễ hiểu, chúng ta đừng giao dịch: có thể bài báo nói rằng suy nghĩ của Thiên tài, mà đối với chúng ta dường như là sự ảo tưởng của ông ta, mang dấu ấn của một sự thật vẫn chưa được tiết lộ cho chúng ta.
