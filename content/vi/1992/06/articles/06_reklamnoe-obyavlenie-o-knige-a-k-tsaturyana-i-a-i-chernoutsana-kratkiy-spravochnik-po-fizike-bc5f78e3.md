---
id: 1992-6-reklamnoe-obyavlenie-o-knige-a-k-tsaturyana-i-a-i-chernoutsana-kratkiy-spravochnik-po-fizike-bc5f78e3
issue: kvant_1992_6
year: 1992
number: "6"
title: '[Quảng cáo về cuốn sách “Hướng dẫn vắn tắt về Vật lý” của A.K. Tsaturyan và A.I. Chernoutsan]'
rubric: smes
page_first: 15
page_last: 25
page_labels: 13, 15, 16, 17, 18, 19, 20, 21, 22, 23
lang: vi
source: kvant_digital
extraction: vision
content_sha256: 378b220ad86877b6fdda7c3938ce91e250b703ff41f34a7c13a293b9e21fb5d6
prompt_sha256: draft-1
translated_from: content/ru/1992/06/articles/06_reklamnoe-obyavlenie-o-knige-a-k-tsaturyana-i-a-i-chernoutsana-kratkiy-spravochnik-po-fizike-bc5f78e3.md
source_content_sha256: 42ef16ec2fdf1807951d11b74cc0b79c421bbd4f9da45fd2e9ccc1a5a802cc64
translation_model: draft
translation_run: vi-draft-gaps-2026-11-07
translation_quality: draft
---

⟦folio 13⟧

---
running_head:
folio:
---

Sau đó mọi thứ đều tập trung vào nhóm thứ hai và thứ ba. Chúng ta có thể đánh giá được sự đóng góp thực sự của họ không? Tích của tất cả các số thuộc nhóm thứ hai theo Định lý 3 không vượt quá $4^{2n/3}$. Có ít số nguyên tố trong nhóm thứ ba hơn $\sqrt{2n}-1$, vì vậy tổng đóng góp của chúng, theo Bổ đề 3, không vượt quá $(2n)^{\sqrt{2n}-1}$. Kết quả: nếu không có số nguyên tố nào nằm giữa $n$ và $2n$ thì bất đẳng thức đúng
$$C_{2n}^{n} < 4^{2n/3} \cdot (2n)^{\sqrt{2n}-1}.$$ (*)
Thật là một suy nghĩ! Xét cho cùng, nếu chứng minh được bất đẳng thức này sai thì đồng thời chúng ta sẽ chứng minh được cách xây dựng của Bertrand: giữa $n$ và $2n$ luôn có ít nhất một số nguyên tố. Hãy thử ước tính $C_{2n}^{n}$. Vì đây là hệ số sinh học lớn nhất có trong quần xã $(1+1)^{2n}$ và vì chỉ có $2n+1 < 4n$ ở đó nên $C_{2n}^{n} > \frac{4^n}{4n}$ được đưa vào. Từ bất đẳng thức thu được suy ra rằng
$$\frac{4^n}{4n} < 4^{2n/3} \cdot (2n)^{\sqrt{2n}-1},$$
$$4^{n/3} < 2 \cdot (2n)^{\sqrt{2n}},$$
$$n/3 < \sqrt{2n} \log_4 2n + \frac{1}{2},$$
$$\sqrt{n} < \sqrt{18} \log_4 2n + \frac{1}{2}.$$
Nhưng ai cũng biết rằng logarit là một hàm chậm và $\sqrt{n}$ sẽ vượt qua nó. Nó vẫn còn để hiểu khi nào. Hãy ước tính điều gì sẽ xảy ra ở $n=1000$. Rõ ràng, $\sqrt{1000} > 30$, $\log_4 2000 < \log_4 4096 = \log_4 4^6 = 6$, tức là $30 < \sqrt{18} \times 6 + \frac{1}{2}$, điều này không chính xác. Điều này có nghĩa là với $n = 1000$ và (vì chúng tôi hy vọng bạn có thể dễ dàng chứng minh bằng đạo hàm) cho bất đẳng thức $n > 1000$ (*) là sai. Điều này có nghĩa là $n$ hợp lệ với những giá trị này.

Định lý Chebyshev (định lý Bertrand). Giữa $n$ và $2n$ luôn có ít nhất một số nguyên tố.

Được rồi, phải làm gì với $n$ nhỏ? Ở đó, dường như sự bất bình đẳng là đúng. Chà, anh ta rất giàu có - lý thuyết của Bertrand cũng đúng - và thật dễ dàng để xác minh điều này bằng cách chỉ cần nhìn vào bảng số nguyên tố hoặc viết một chương trình nhỏ. Nếu muốn, bạn có thể làm theo cách khác - bằng cách cẩn thận hơn với ước tính của mình, bạn có thể nhận được bất đẳng thức chính xác hơn (ví dụ: xem cuốn sách của W. Sierpinski “250 bài toán về lý thuyết số cơ bản”). Đây là một vấn đề của hương vị.

Nhưng có lẽ cuộc dạo chơi của chúng tôi đã kết thúc. Đã đến lúc thư giãn và nếu bạn vẫn muốn đi dạo thì đây là một số câu đố để bạn bắt đầu.

1. Chứng minh rằng với số nguyên tố $p$ và mọi số nguyên $x$, $y$, số $(x+y)^p - x^p - y^p$ chia hết cho $p$.
2. Tổng quát hóa bài toán trước đó cho trường hợp của một số số hạng và suy ra định lý nhỏ Fermat từ đây: $x^p - x$ chia hết cho $p$.
3. Chứng minh rằng nếu $N=p^m$ là lũy thừa của số nguyên tố $p$ và chia hệ số sinh học $C_{n}^i$ thì $N \leq n$.
4. Chứng minh rằng có hai số nguyên tố nằm giữa $n$ và $2n$ cho $n>5$.
5. Chứng minh rằng nếu $p_k - k$ là số nguyên tố thì $p_{k+2} < 2p_k$.
6. Chứng minh rằng $n!$ không phải là lũy thừa của số nhỏ hơn đối với bất kỳ $n>1$ nào.

Các ứng viên chú ý!

Phát hành
dạng túi "HƯỚNG DẪN VẬT LÝ TÓM TẮT",
tác giả A.K. Tsaturyan và A.I. Cherpotsan.

Sách tham khảo không có sách tương tự trong văn học giáo dục, được biên soạn dưới dạng kết nối đáp số cho các câu hỏi sao chép.

Được thiết kế để lặp lại sâu sắc các tài liệu hàng ngày ngay trước các bản sao ở trường hoặc buổi biểu diễn.

Đối với các câu hỏi liên quan đến việc phân phối mẫu xin vui lòng gọi
(095) 447-32-64.

⟦folio 15⟧

---
running_head:
folio:
---

Ứng viên khoa học sư phạm
Y. AMSTISLAVSKY

Việc nghiên cứu mô hình phát sáng của các vật thể bị đốt nóng - nhiệt độ, hay nhiệt độ, bức xạ - đóng một vai trò đặc biệt trong sự phát triển của khoa học vật lý. Chỉ cần đề cập rằng chính việc nghiên cứu bức xạ nhiệt đã đặt nền móng cho toàn bộ lý thuyết lượng tử. Một trong những định luật cơ bản của bức xạ nhiệt được nhà vật lý người Đức Kirchhoff đưa ra vào năm 1859. Câu chuyện của chúng ta là về ông.

Màu đen có thể là ánh sáng?

Đầu tiên là về “màu đen”. Khái niệm “màu đen” trong vật lý gắn liền với tính chất của chất dẫn nhiệt cung cấp bức xạ cho nó (có thể nhìn thấy hoặc một số phần khác của quang phổ). Màu đen càng ấm thì tỷ lệ bức xạ từ ống dẫn nhiệt càng lớn. Thân đen tuyệt đối - dưới đây chúng ta sẽ gọi tắt là a. h.t. - hấp thụ toàn bộ bức xạ cung cấp cho nó và trong tất cả các vùng của quang phổ. Ngược lại với “đen” là “trắng”. Vật thể phản chiếu càng nhiều thì càng hấp thụ ít và càng ít xuất hiện màu đen.

Bây giờ về "ánh sáng". Vật thể nhẹ được hiểu là vật thể phát ra nhiều (ở phần nhìn thấy hoặc phần khác của quang phổ). Hơn nữa, cơ thể càng thải ra nhiều thì càng nhẹ. Khái niệm đối lập với “ánh sáng” là “bóng tối”. Vật sáng phát ra nhiều, vật tối phát ra ít.

Như vậy, “đen” và “sáng” (cũng giống như “đen” và “tối”) có thể hiểu được theo một “thứ tự” khác. Chúng ảnh hưởng đến các tính chất khác nhau của cơ thể. Câu hỏi quan trọng là liệu các thuộc tính này có liên quan với nhau hay không. Nếu mối liên hệ như vậy tồn tại và có tính chất phổ quát, thì khi biết được đặc tính hấp thụ của một vật thể, người ta có thể tưởng tượng một vật thể nhất định sẽ bức xạ như thế nào trong những điều kiện nhất định.

Từ kinh nghiệm hàng ngày, chúng ta biết rõ rằng cùng một vật thể phát ra những nhiệt độ khác nhau ở những nhiệt độ khác nhau. Chỉ cần nhớ rằng bức xạ mà mắt nhìn thấy được của bóng đèn sợi đốt thay đổi bao nhiêu khi dòng điện ngày càng tăng: từ ánh sáng màu đỏ anh đào đáng chú ý ở $T=800$ K đến ánh sáng trắng chói ở $T=2800$ K. Không kém phần biến đổi nổi bật, các đặc tính bắt buộc về nguồn gốc của sự thay đổi nhiệt độ cơ thể, mỗi độc giả, tất nhiên, đã nhiều lần quan sát, kiểm tra (có lẽ không quan tâm đúng mức) ngọn lửa khói. Đun nóng đến nhiệt độ cao (khoảng 1800 K), các hạt than “đen” (bồ hóng) phát sáng rực rỡ và tập hợp lại tạo thành những lưỡi lửa màu vàng (ở đây màu đen chuyển thành ánh sáng), nhưng cũng có những hạt sahka màu đen, chưa cháy và đã có thời gian nguội, tập hợp lại tạo thành những lưỡi bồ hóng đen tuyền (và ở đây màu đen đã trở nên sẫm màu). Do đó, rõ ràng là việc so sánh khả năng phát quang hấp thụ và phát xạ của các vật thể khác nhau phải được thực hiện ở cùng nhiệt độ cơ thể.

Trong cuộc sống nói chung, chúng ta thường xuyên quan sát các vật thể ở nhiệt độ phòng. Hơn nữa, các vật thể màu đen (đối với vùng quang phổ khả kiến ​​hoặc rộng hơn) cũng rơi vào vùng của chúng ta. Đó có thể là vật chất đen, một cục than, một vật thể bị hun khói, bộ lông của loài chim, lỗ mở hoặc hang động, tổ trong đá, v.v. Khi so sánh một vật đen với các vật thể đen nằm cạnh nó, chúng ta thấy vật đầu tiên hóa ra có màu tối, trong khi vật thể đó có màu đen.

⟦folio 16⟧

---
running_head:
folio:
---

vật thể không đen thì nhẹ hơn nhiều. Do đó, người ta đã lựa chọn có ý thức rằng màu đen luôn tối, và càng đen thì càng tối. Sự lựa chọn này là sai lầm sâu sắc.

Mọi thứ đều dễ dàng bắt buộc nếu chúng ta tính đến hai trường hợp. Đầu tiên, chúng ta luôn so sánh các vật thể dưới ánh sáng ban ngày hoặc ánh sáng điện (không ai làm điều này trong đêm tối hoặc trong phòng tối) và chúng ta hoàn toàn không cảm nhận được bức xạ nhiệt độ của cơ thể mà là sự tán xạ hoặc ánh sáng của một nguồn phát nhiệt độ cao “ngoại lai” - Mặt trời hoặc đèn sợi đốt. Các vật thể không phải màu đen, không giống như các vật thể màu đen, phân tán mạnh bức xạ “ngoài hành tinh” này và sau đó mỗi vật thể trở thành ánh sáng. Thứ hai, chúng ta thường quan sát bằng mắt thường. Tuy nhiên, thiết bị UDE này chỉ nhạy cảm với vùng khả kiến ​​- một phần không đáng kể trong phổ bức xạ điện từ. Và ở nhiệt độ phòng ở khu vực này, gần như không có một cơ thể nào phát ra bất cứ thứ gì!

Phân tích vấn đề về mối liên hệ giữa đặc tính hấp thụ và phát xạ của cơ thể đã đưa Kirchhoff đến một kết luận quan trọng, được gọi là Kirchhoff. Nó có thể được định dạng như sau: vật thể càng đặt vào một nhiệt độ nhất định thì càng phát ra nhiều (thân thể càng đen thì càng nhẹ).

Để viết ra định luật Kirchhoff, chúng ta định dạng khái niệm khả năng hấp thụ và khả năng phát xạ. Bằng khả năng hấp thụ $A_{\lambda,T}$ của một vật thể, chúng ta sẽ hiểu được phần bức xạ tới có bước sóng $\lambda$ được hấp thụ bởi vật thể phía dưới nằm ở nhiệt độ tuyệt đối $T$. độ hấp thụ là một đại lượng không thứ nguyên, tùy thuộc vào đặc tính của vật thể, nhận giá trị trong khoảng từ 0 đến 1. Hơn nữa, $A=0$ trong trường hợp vật thể trắng tuyệt đối$^*$) và $A=1$ trong trường hợp a. h.t.

$^*)$Hoặc trong trường hợp thân gương tuyệt đối (gương lý tưởng). Một bề mặt hoàn toàn trắng sẽ tán xạ tất cả các tia tới một cách đồng đều theo mọi hướng, và một bề mặt hoàn toàn gương phản chiếu tất cả các tia.

Độ phát xạ $E_{\lambda,T}$ được hiểu là đại lượng năng lượng bằng công suất phát ra từ một vật thể nhất định trong một khoảng phổ đơn vị bước sóng $\lambda^*$) với đơn vị bề mặt của vật thể được nung nóng ở nhiệt độ $T$.

Giả sử rằng chúng ta có một số vật thể có $A_{\lambda,T}$ khác nhau và trong số đó cũng có a. h.t., và một cơ thể hoàn toàn trắng. Để tất cả các vật thể được làm nóng đến cùng một nhiệt độ đủ cao $T$. Theo định luật Kirchhoff, cơ thể chúng ta sẽ phát ra ánh sáng khác nhau, a sẽ phát sáng nhất. h.t., trong khi thân trắng sẽ tối hoàn toàn. Hãy chọn a. h.t., biểu thị $E_{\lambda,T}^a=\varepsilon_{\lambda,T}, A_{\lambda,T}^a=a=1$. Điều rất quan trọng là bức xạ a. bao gồm không chỉ cường độ mạnh nhất ở nhiệt độ nhất định mà còn có thành phần quang phổ được xác định nghiêm ngặt. Nói cách khác, hàm $\varepsilon_{\lambda,T}$ là hàm phổ quát của $\lambda$ và $T$. Có tính đến những điều trên

$^*)$Để tránh nhầm lẫn, hãy lưu ý rằng “trong một khoảng phổ đơn vị” không có nghĩa là $\Delta \lambda$ bằng, chẳng hạn như 1 mét. Điều này có nghĩa là công suất bức xạ tỷ lệ với $\Delta \lambda:\Delta W/(\Delta S \Delta t)=E_{\lambda,T} \Delta \lambda$, trong đó $\Delta W$ là năng lượng phát ra trong khoảng bước sóng $\Delta \lambda$ trong thời gian $\Delta t$ từ tấm $\Delta S$.

⟦folio 17⟧

---
running_head:
folio:
---

các công thức và dữ liệu định nghĩa, chúng ta viết định luật Kirchhoff dưới dạng

$$E_{\lambda,T} = A_{\lambda,T} \varepsilon_{\lambda,T}.$$  (1)

Dạng của hàm $\varepsilon_{\lambda,T}$ được nhà vật lý người Đức M. Planck tìm ra về mặt lý thuyết vào năm 1900. Theo Planck,

$$\varepsilon_{\lambda,T} = 2\pi c^2 h \lambda^{-5} \left( \exp \left( \frac{hc}{\lambda kT} \right) - 1 \right)^{-1},$$  (2)

trong đó $c = 3 \cdot 10^8$ m/s là tốc độ ánh sáng trong chân không, $h = 6,62 \cdot 10^{-34}$ J.s là hằng số Planck, $k = 1,38 \times 10^{-23}$ J./K là hằng số Boltzmann.

Ở nhiệt độ cơ thể cố định $T$ chức năng $A, E, \varepsilon$ chỉ phụ thuộc vào $\lambda$. Trong trường hợp này, chúng được biểu thị bằng sự tương ứng $A_\lambda, E_\lambda, \varepsilon_\lambda$. Đồ thị của hàm Planck cho hai nhiệt độ $T_1 = 2000$ K và $T_2 = 3000$ K được hiển thị ở hình 1.

Màu đỏ có thể trở thành màu đỏ?

Mô hình tiện lợi nhất của ac. tức là một lỗ nhỏ trên một lớp vỏ kín được làm bằng vật liệu chịu lửa hoặc vật liệu chịu lửa. Nhiệt độ cơ thể được thay đổi bằng cách sử dụng điện hoặc một số máy sưởi khác. Hình dạng của vỏ không đóng vai trò quan trọng trên thực địa.

Hãy chuyển sang mô hình AC. tức là ở dạng một quả cầu rỗng làm bằng kim loại chịu lửa với bề mặt bên trong được làm đen (hình 2). Một tia sáng từ bên ngoài rơi vào lỗ $S$ đi qua khoang bên trong và trải qua nhiều phản xạ, nhanh chóng yếu đi và thực tế không thoát ra khỏi khoang, và điều này xảy ra đối với bất kỳ phần nào của quang phổ và ở bất kỳ nhiệt độ nào. Do đó, lỗ $S$ trong mô hình của chúng tôi có các đặc tính của a.ch. t. Có vẻ như trong khi hấp thụ mọi thứ, lỗ trống không phát ra gì cả. Đây là một quan niệm sai lầm sâu sắc. Cái lỗ thực sự không phát ra bất cứ thứ gì “ngoại lai”. Tuy nhiên, bằng cách hấp thụ tất cả bức xạ tới và “xử lý” hoàn toàn nó, a.ch. tức là hình thành bức xạ của chính nó tương ứng với nhiệt độ nhất định $T$. Theo định luật Kirchhoff, so với bức xạ của bất kỳ vật nào khác được nung nóng đến cùng nhiệt độ $T$, bức xạ của lỗ $S$ sẽ mạnh nhất. Người đầu tiên đề xuất sử dụng một lỗ trên một vỏ kín làm nguồn phát màu đen tuyệt đối là chính Kirchhoff (1859). Tuy nhiên, chỉ nhiều năm sau, các nghiên cứu thực nghiệm về bức xạ nhiệt độ sử dụng mô hình AC. t. đã trở thành truyền thống.

Hãy thảo luận ba ví dụ minh họa định luật Kirchhoff.

1. Giả sử rằng bề mặt bên ngoài của quả cầu (xem hình 2) được đánh bóng để tỏa sáng và có đặc tính gương trong một vùng phổ rộng. Người quan sát sẽ thấy gì khi nhìn quả cầu này từ phía lỗ $S$, ở hai trạng thái của cơ thể: a) ở nhiệt độ phòng ($T=300$ K) và b) ở nhiệt độ nhiệt trắng ($T=3000$ K)?

a) Để loại bỏ ảnh hưởng xoa bóp của bức xạ “ngoại lai”, chúng ta sẽ

⟦folio 18⟧

---
running_head:
folio:
---

thực hiện quan sát theo thứ tự tốt
căn phòng tối. Tuy nhiên, khi kiểm tra cơ thể chúng ta trong những điều kiện như vậy bằng mắt thường, chúng ta sẽ không nhìn thấy gì, bởi vì tại $T=300$ K nằm trong phần nhìn thấy được của quang phổ $(0,4 \cdot 10^{-6} \text{ m} \leq \lambda \leq 0,76 \cdot 10^{-6} \text{ m})$ hàm Planck $\varepsilon_{\lambda}$, theo công thức (2), có các giá trị vô cùng nhỏ. Tuy nhiên, một vật được làm nóng đến $T=300$ K vẫn phát ra, và hơn hết là ở phần quang phổ nơi hàm $\varepsilon_{\lambda}$ đạt cực đại, cụ thể là ở bước sóng $\lambda^m=10 \cdot 10^{-6} \text{ m}$ (10 µm), tương ứng với phần giữa của vùng hồng ngoại của quang phổ. Dựa trên định luật Kirchhoff, chúng ta có thể kết luận rằng trong tia hồng ngoại, phản ứng $S$ sẽ “phát sáng” rực rỡ trên nền tối của phần còn lại của quả cầu. Nhưng một bức ảnh như vậy chỉ có thể được “nhìn thấy” bằng mắt có giá trị màu cao trong vùng 10 micron hoặc mắt được trang bị bộ chuyển đổi hình ảnh hồng ngoại sang nhìn thấy phù hợp.

6) Khi cơ thể được làm nóng đến nhiệt độ nóng trắng, hàm $\varepsilon_{\lambda}$ trong phần quang phổ nhìn thấy được tăng mạnh. Như sau từ công thức (2), khi $T$ thay đổi từ $T_1$ thành $T_2$ độ phát xạ a. h.t. trong một vùng quang phổ nhất định $\lambda$ tăng lên

$$\frac{\varepsilon_{\lambda}, T_2}{\varepsilon_{\lambda}, T_1} = \exp \frac{hc}{\lambda k} \left( \frac{1}{T_1} - \frac{1}{T_2} \right) \text{ раз.}$$

(Kết quả này dễ dàng có được từ (2), nếu xét đến $\exp \left( \frac{hc}{\lambda k T} \right) \gg 1$)

Đối với phần giữa vùng nhìn thấy của quang phổ $(\lambda=0,55 \cdot 10^{-6} \text{ m})$ tại $T_2=3000$ K và $T_1=300$ K $(T_2/T_1=10)$ chúng ta có

$$\frac{\varepsilon_{\lambda}, T_2}{\varepsilon_{\lambda}, T_1} = e^{78} = 10^{34}!$$

Do đó, bây giờ không cần chuyển đổi bức xạ và phản ứng $S$ được liên kết sáng, chúng ta sẽ nhìn trực tiếp trên nền tối của phần còn lại của cơ thể bằng mắt thường (“càng đen, càng sáng”).

2. Giả sử rằng chúng ta có một viên đá màu - một loại khoáng vật chịu lửa, khi nhìn qua ánh sáng, sẽ có màu đỏ (hình 3, a), vì nó hấp thụ mạnh các tia màu xanh lam, xanh lam và tím, trong đó $A_{\lambda}=1$ và sản phẩm cho phần màu đỏ-cam của quang phổ, trong đó $A_{\lambda}=0$. Để xác định sự biến đổi, cũng có thể là khi nhiệt độ tăng lên, các vùng hấp thụ cường độ cao trên thực tế không hợp nhất trong quang phổ. Chẳng hạn, viên đá này có phát sáng khi được nung nóng đến $T=3000$ K không? Nếu vậy thì nến có màu không và bằng cách nào?

Ở $T=3000$ K, hàm Planck $\varepsilon_{\lambda}$ trong vùng khả kiến ​​của quang phổ khá lớn, và theo định luật Kirchhoff, ở những vùng có độ hấp thụ mạnh, trong đó $A_{\lambda}=1$, khoáng chất được nung nóng sẽ phát sáng mạnh: $E_{\lambda}=A_{\lambda} \varepsilon_{\lambda}$. Sau khi cắn, sự hấp thụ mạnh chỉ bao phủ một phần ngắn vùng nhìn thấy của quang phổ; cây nến này phải có màu xanh lam (hình 3, b).

Hình 3.

⟦folio 19⟧

---
running_head:
folio:
---

Một thí nghiệm thú vị với thạch anh nung chảy đã được thực hiện bởi nhà vật lý thực nghiệm người Mỹ R. Wood vào đầu thế kỷ 20. Trong vùng khả kiến ​​của quang phổ, thạch anh nung chảy trong suốt và thực tế không có sự hấp thụ ở đây, tức là $A_\lambda=0$. Do đó, cột thạch anh nung chảy được nung trên bếp gas vẫn có màu tối dù nhiệt độ cao. Thạch anh nung chảy “có màu” bằng gỗ bằng cách thêm một số oxit neodymium vào nó và chuẩn bị một hỗn hợp tan chảy đồng nhất. Được biết, các hợp chất đất hiếm (trong đó có neodymium) có vùng hấp thụ hẹp, mạnh ở phần quang phổ nhìn thấy được. Do đó, điều tự nhiên là các dải hấp thụ cũng xuất hiện trong sự tan chảy màu của thạch anh. Trong neodymium, chúng nằm ở các phần màu đỏ, cam và xanh lục của quang phổ. Nếu bây giờ một cột nóng chảy như vậy được nung nóng trên cùng một vòi đốt gas như trước, thì, không giống như trường hợp đầu tiên, nó phát sáng rõ rệt. Wood kiểm tra ánh sáng này bằng kính quang phổ và tin rằng nó bao gồm các dải sáng chính xác nằm trong các phần màu đỏ, cam và xanh lục của quang phổ.

3. Người ta biết rằng một số chất kết tinh hấp thụ ánh sáng khác nhau khi bị phân cực ở các mặt phẳng khác nhau. Đối với một hướng dao động ánh sáng, hệ số $A_\lambda$ lớn hơn và đối với hướng kia (đối với cùng $\lambda$ và $T$) thì hệ số nhỏ hơn. Một ví dụ kinh điển về chất như vậy là tourmaline - một tinh thể chịu lửa có màu đơn trục (thường là màu xanh lá cây) có khả năng hấp thụ mạnh hơn các rung động thông thường (hình 4, a). Do đó, với độ dày vài mm, tinh thể như vậy là một bản phân cực do chính thiên nhiên tạo ra: nó truyền ánh sáng với các rung động thực tế nằm trong cùng một mặt phẳng. Câu hỏi tập trung vào điều này. Ánh sáng rực rỡ của tinh thể tourmaline khi đun nóng có những đặc tính phân cực nào?

Đối với các dao động thông thường ($o$) và bất thường ($e$) (từ tiếng Anh thông thường và bất thường), hệ số $A_\lambda$ là khác nhau (đối với dao động $o$ thì hệ số này lớn hơn). Do đó, dao động $o$- và $e$-sẽ được trình bày khác nhau trong nghiên cứu. Theo định luật Kirchhoff, ánh sáng rực rỡ của tourmaline được nung nóng phải được hấp thụ một phần với ưu thế đáng chú ý là các dao động $o$ (hình 4, b). Kết quả này lần đầu tiên được chính Kirchhoff quan sát thấy trong một nghiên cứu định tính về tourmaline được nung nóng (1859). Một số lượng lớn các nghiên cứu tập thể sau này, được thực hiện vào đầu thế kỷ 20, đã xác nhận rõ ràng sự tương ứng của $A^e/A^o=E^e/E^o$.

Ba lựa chọn có thể bằng Sta battam?

Một trong những ứng dụng quan trọng của vật thể được làm nóng là sử dụng chúng làm nguồn sáng. Ví dụ, hãy xem xét đèn sợi đốt, loại đèn

⟦folio 20⟧

---
running_head:
folio:
---

Trong số các nguồn sáng khác nhau, chúng vẫn đóng một vai trò quan trọng cho đến ngày nay. Chuyển sang phần thảo luận về các ứng dụng chiếu sáng của định luật Kirchhoff, chúng tôi lưu ý rằng trong nghiên cứu về a. do đó phần nhìn thấy được của quang phổ (phần bóng mờ của biểu đồ ở hình 1) chiếm một phần rất nhỏ trong tổng năng lượng bức xạ: ở $T=2000$ K - khoảng 0,3%, ở $T=3000$ K giá trị này tăng lên 3%, còn lại quá nhỏ. Trong trường hợp bộ phát vonfram, như được trình bày bên dưới, tình hình tốt hơn một chút. Tuy nhiên, do những tổn thất bổ sung không thể tránh khỏi do tính dẫn nhiệt và đối lưu, hiệu suất của đèn phủ vonfram tiên tiến trên thực tế không vượt quá 2-3%. Điều này có nghĩa là, tốt nhất, 97% năng lượng cung cấp cho một chiếc đèn như vậy sẽ “xuống cống”.

Bây giờ chúng ta hãy tưởng tượng một chút. Giả sử rằng một vật liệu dẫn điện chịu lửa (ví dụ: lên tới $T=3000$ K) có khả năng hấp thụ mạnh ở nhiệt độ cao trong vùng khả kiến ​​của quang phổ ($A_\lambda=1$) nhưng gần như không có sự hấp thụ hoàn toàn ở tất cả các phần khác của quang phổ ($A_\lambda=0$) đã được tạo ra hoặc tìm thấy. Theo định luật Kirchhoff, việc sử dụng vật liệu như thân đèn sợi đốt sẽ tiết kiệm được rất nhiều điện năng. Thật vậy, công suất phát sáng của một chiếc đèn có công suất vài watt như vậy sẽ tương ứng với công suất phát sáng của một chiếc đèn 100 watt hiện đại.

Về mặt thảo luận các vấn đề sau đây có vẻ được quan tâm: bài toán. Hàm $A_\lambda$ phải ở dạng nào để đạt được lượng ánh sáng phát ra tối đa, với điều kiện: giá trị lớn nhất cho một giá trị nhất định $T$ của độ sáng của nguồn hoặc sự kết hợp giữa độ sáng cao của nguồn với thành phần màu sắc thuận lợi nhất của bức xạ đối với mắt người?

Chúng ta hãy gọi các nguồn thỏa mãn thuộc tính bắt buộc tương ứng với $S_1$ và $S_2$. Các hàm tìm kiếm $A_\lambda$ đối với chúng được hiển thị trong Hình 5 và độ phát xạ $E_\lambda$ được hiển thị trong Hình 5.6 và 6.6. Theo định luật Kirchhoff, cả hai nguồn đều lý tưởng về mặt hiệu quả - chúng chỉ phát ra ánh sáng khả kiến, vì nằm ngoài vùng này $A_\lambda=0$. Nhưng nguồn $S_1$, phát ra ánh sáng giống như a, có độ sáng lớn hơn ở nhiệt độ nhất định. h.t. Tuy nhiên, ánh sáng này có tông màu hơi đỏ do tông màu ấm chiếm ưu thế, vì $E_\lambda$ nhanh chóng quay trở lại từ

⟦folio 21⟧

---
running_head:
folio:
---

tăng $\lambda$. Trong bức xạ của nguồn $S_2$, tông ấm bị suy yếu do sự giảm $A_\lambda$ ở phần bước sóng dài của quang phổ và sự phân bố năng lượng gần với sự phân bố năng lượng ánh sáng trong quang phổ của Mặt trời. Ánh sáng từ nguồn $S_2$ trở nên “trắng hơn” và có lợi hơn cho mắt người. (Tôi không loại trừ khả năng một trong những độc giả sẽ đưa ra một phiên bản nguồn thậm chí còn tốt hơn). Không khó để nhận thấy sự xuất hiện của những chiếc đèn như $S_1$ hay $S_2$ sẽ dẫn đến những thay đổi mang tính cách mạng trong công nghệ chiếu sáng. Nhưng để đạt được kết quả như vậy, trước tiên cần phải thực hiện một cuộc cách mạng trong công nghệ - học cách sản xuất vật liệu có các đặc tính định trước (hệ số hấp thụ, độ khúc xạ, v.v.).

Thật không may, các nguồn ánh sáng nhiệt thực sự có rất ít điểm tương đồng với các nguồn siêu tiết kiệm lý tưởng $S_1$ hoặc $S_2$ đã thảo luận ở trên. Mặc dù đôi khi có thể tìm thấy các yếu tố chung. Về vấn đề này, không phải không có sự quan tâm khi nhắc đến đầu đốt Auer. Là nguồn phát ra ánh sáng khả kiến ​​và tia hồng ngoại tầm trung, đèn đốt Auer được biết đến vào đầu thế kỷ 20 và ngày nay khá được quan tâm trong lịch sử. Tuy nhiên, các đặc tính của bộ phát này khá thú vị. Bộ phận chính của đầu đốt là nắp lưới chịu lửa, được nung trên ngọn lửa khí đến 1800 K. Lưới được làm bằng oxyporium với việc bổ sung một lượng nhỏ oxyporium (từ 0,75 đến 2,5%). Trên mặt, chuỗi oxy cung cấp khả năng hấp thụ mạnh, gần giống như của a.h.t., trong toàn bộ vùng nhìn thấy được của quang phổ và gần với a.h.t. hấp thụ ở vùng hồng ngoại trung, trong khi ở vùng cận hồng ngoại hầu như không có sự hấp thụ. Do đó, bức xạ từ lò đốt Auer chứa a.b.t năng lượng cao nhất. trong quang phổ. ở $T=1800$ K vùng cận hồng ngoại và với tổng bức xạ nhỏ, đầu đốt này là nguồn ánh sáng nhìn thấy và tia hồng ngoại tầm trung mạnh, gần giống như AC.

Hãy chuyển sang đèn sợi đốt. Vật liệu chính được sử dụng làm chất lỏng làm việc của đèn sợi đốt hoàn hảo là vonfram. Sự phụ thuộc $A_\lambda$ và $E_\lambda$ đối với vonfram ở $T=2450$ được trình bày ở hình 7. Như có thể thấy từ hình, vonfram phát ra lượng khí thải thấp hơn đáng kể

⟦folio 22⟧

---
running_head:
folio:
---

cao hơn A. ht. ở cùng nhiệt độ, trên toàn bộ phổ rộng. Hơn nữa, diện tích nhìn thấy được chỉ bằng một nửa, điều này tất nhiên là không tốt đối với một nguồn sáng. Tuy nhiên, đồng thời, ở vùng hồng ngoại, vonfram phát ra thứ hai - ít hơn năm lần so với a. bao gồm cả điều đó, vốn đã tốt cho nguồn sáng, vì điều này làm giảm đáng kể lượng điện năng tiêu thụ. Tóm lại, chúng ta có thể nói rằng, không phải là một nguồn phát sáng mạnh, giống như a. kể cả ở cùng nhiệt độ, đèn vonfram trở nên dễ chịu hơn cho mắt và là nguồn tiết kiệm hơn đáng kể. Đúng, hiệu quả của nó vẫn rất thấp và như đã đề cập, thực tế không vượt quá 3%. Đương nhiên, việc tăng hiệu suất của đèn sợi đốt dù chỉ vài phần trăm trong khi vẫn duy trì được những ưu điểm của chúng đã là một thành tựu đáng chú ý trong lĩnh vực công nghệ chiếu sáng.

Tóm lại, bạn đọc thân mến, có một câu hỏi bảo mật nhỏ.

hình 8 hiển thị các đường cong $A_\lambda$ và $E_\lambda$ đối với một số vật thể được làm nóng. Có thể nói gì về vật thể này và bức xạ của nó?

⟦folio 23⟧

---
running_head:
folio:
---

Chúng tôi đã chạy chuyên mục này từ số này đến số khác kể từ khi thành lập tạp chí. bài toán được xuất bản trong đó không phải là tiêu chuẩn, nhưng lời giải của chúng không yêu cầu kiến ​​thức ngoài phạm vi chương trình học ở trường. bài toán khó nhất được đánh dấu bằng dấu hoa thị. Sau khi hình thành bài toán, chúng tôi thường cho biết ai đã đề xuất điều đó cho chúng tôi. Tất nhiên, không phải tất cả những bài toán này đều được xuất bản lần đầu tiên.

Lời giải bài toán từ số này phải được gửi chậm nhất là ngày 15 tháng 8 năm 1992 đến địa chỉ: 103006, Moscow, K-6, st. Tverskaya-Yamskaya thứ nhất, 1/2, «Kvant». Lời giải bài toán từ các số khác nhau của tạp chí hoặc trong các chủ đề khác nhau (toán học và vật lý) được phân bổ trong các phong bì khác nhau. Trên phong bì, ở cột “Tới”, viết: “Bài toán lượng tử” số 6-92 và các số bài toán, lời giải mà bạn đang gửi, ví dụ “M1346” hoặc “F1353”. Ở cột “…địa chỉ người gửi”, vui lòng ghi riêng họ và tên của bạn. Kèm theo một phong bì có ghi địa chỉ của bạn trên đó (trong phong bì này bạn sẽ nhận được kết quả xác minh lời giải).

Các điều kiện cho mỗi bản gốc bài toán được đề xuất xuất bản được chỉ định trong một phong bì riêng biệt, được nhân đôi cùng với giải pháp của bạn cho bài toán này (trên vị trí phong bì: “Bài toán lượng tử”, bài toán mới trong vật lý hoặc “...mới bài toán trong toán học”).

Ở đầu mỗi chữ cái hãy cho biết mã số trường, lớp bạn đang theo học. Bài toán F1353 đã được đề xuất tại Optipida Vật lý toàn Nga lần thứ XVIII, và bài toán F1355 và F1356 tại Optipida Vật lý Liên bang năm 1992.
