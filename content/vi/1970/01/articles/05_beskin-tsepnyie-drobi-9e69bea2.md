---
id: 1970-1-beskin-tsepnyie-drobi-9e69bea2
issue: kvant_1970_1
year: 1970
number: "1"
title: Phân số liên tục
authors:
  - Бескин Н. М.
rubric: osnovnye-stati
page_first: 18
page_last: 27
page_labels: 16, 17, 18, 19, 21, 22, 23, 24, 25
tag: M5Y4
lang: vi
source: kvant_digital
extraction: vision
content_sha256: 92daa7100a25f360e45c1535976876fc2ecc63fd5ebc751e58b7efa8eee19883
prompt_sha256: 3ec6b8aabd9b98576af76503cd8a2902b9f5d18e01ee867dfb1228f59c6d52d8
translated_from: content/ru/1970/01/articles/05_beskin-tsepnyie-drobi-9e69bea2.md
source_content_sha256: 3433f08c23e421e33dbe8ad6013f6a754d017c609a1fc42cd07b4044cfa41ccb
translation_model: gpt-5.6-terra
translation_run: vi-codex-2026-10-30
---

⟦folio 16⟧

PHÂN SỐ LIÊN TỤC

N. M. BESKIN

Từ thời cổ đại xa xưa, các nhà bác học đã quan tâm
đến cách tìm cho bất kỳ số không nguyên nào
một xấp xỉ tốt của nó
bằng các phân số có mẫu số nhỏ.
Bài viết kể về cách đơn giản nhất
để tìm những phân số như vậy.

$$\pi = \sqrt{2}$$

1. HAI ĐIỀU BÍ ẨN

1. Điều bí ẩn của Archimedes.
Nhiều người cho rằng: để tìm được điều gì khác thường, phải đi thật xa, tốt nhất là vào vũ trụ. Trong đời sống thường ngày, mọi thứ xung quanh ta đều đã biết rõ, và không có gì thú vị.

Thật là một sai lầm! Chúng ta bị bao quanh bởi những hiện tượng bí ẩn, nhưng không suy nghĩ về chúng, vì chúng đã quen thuộc. Ở đây sẽ kể về hai sự thật bí ẩn trong lịch sử toán học.

Học sinh trên khắp thế giới đều “học” trong chương trình hình học rằng Archimedes đã tìm được cho số π một giá trị xấp xỉ là

$$\frac{22}{7}$$

). Người ta đã quá quen với sự thật này đến mức không ngờ rằng trong đó ẩn giấu một điều bí ẩn. Nhưng chỉ cần đặt một câu hỏi tự nhiên: tại sao Archimedes lại chọn các phần bảy? Tại sao không phải các phần tám? Cố gắng trả lời câu hỏi này sẽ dẫn chúng ta đến một lĩnh vực mới của số học.

Ta hãy làm rõ bài toán “cho một xấp xỉ của số thực α dưới dạng phân số có mẫu số q”.
Điều đó có nghĩa là: trong tất cả các phân số có mẫu số q, tìm phân số gần số α nhất. Nếu trên trục số đánh dấu tất cả các phân số có mẫu số q, thì số α nằm giữa hai phân số kề nhau như vậy (trường hợp α trùng với một trong chúng không đáng xét)

$$\frac{p-1}{q} < \alpha < \frac{p}{q}.$$

Trong hai phân số này, chọn phân số gần α hơn. Chẳng hạn, trên hình 1 điểm α gần đầu bên phải của đoạn $$\left[ \frac{p-1}{q}; \frac{p}{q} \right],$$ và vì thế

*) Thực ra, Archimedes trong tác phẩm “Về phép đo đường tròn” đã phát biểu kết quả này hơi khác một chút. Ông chỉ ra các cận cho π:

$$3 \frac{10}{71} < \pi < 3 \frac{1}{7}.$$

Giá trị $$3 \frac{1}{7},$$ đơn giản hơn, đã được dùng phổ biến, mặc dù π gần $$3 \frac{10}{71}.$$

⟦folio 17⟧

Cần lấy
$$\alpha \approx \frac{p}{q}.$$
Nếu $\alpha$ là trung điểm của đoạn $\left[ \frac{p-1}{q}, \frac{p}{q} \right]$, thì để xác định, quy ước chọn đầu bên trái của nó.

Quá trình thay số $\alpha$ bằng giá trị xấp xỉ của nó được gọi là phép xấp xỉ.

Từ những điều đã trình bày, rõ ràng rằng để xấp xỉ số $\alpha$ có thể dùng các phân số với bất kỳ mẫu số nào. Việc chọn mẫu số tùy thuộc vào ý muốn của chúng ta. Vì tiện lợi về kỹ thuật, hầu như luôn dùng các phân số thập phân. Tuy nhiên, vào thời Archimedes, phân số thập phân còn chưa được phát minh, và ông có thể chọn bất kỳ phân số nào. Ông đã chọn các phần bảy. Tại sao? Hãy kiên nhẫn, chúng ta sẽ sớm hiểu điều đó.

Khi xấp xỉ số thực $\alpha$ bằng phân số $\frac{p}{q}$, xuất hiện sai số
$$\Delta = \alpha - \frac{p}{q}$$

(hãy nhớ: sai số là giá trị chính xác trừ đi giá trị xấp xỉ). Nếu giá trị xấp xỉ được lấy thiếu, thì sai số dương, còn nếu lấy thừa — thì âm.

Trị tuyệt đối của sai số được gọi là sai số tuyệt đối.

Rõ ràng rằng với cách xấp xỉ đã chọn, sai số tuyệt đối

sai số không thể vượt quá $\frac{1}{2q}$ (xem hình 1)

$$|\Lambda| \leqslant \frac{1}{2q}.$$

Số $\frac{1}{2q}$ là cận trên của sai số tuyệt đối. Với một cách xấp xỉ khác, cận trên có thể khác. Chẳng hạn, nếu ta đã quy ước luôn lấy xấp xỉ thiếu, thì nó sẽ bằng $\frac{1}{q}$.

Sai số tuyệt đối đạt cận trên trong trường hợp (bất lợi nhất) khi $\alpha$ là trung điểm của đoạn
$$\left[ \frac{p-1}{q}, \frac{p}{q} \right].$$

Rõ ràng, phép xấp xỉ có lợi nếu với giá trị nhỏ của $q$ nó cho độ chính xác cao. Để đặc trưng cho tính có lợi, cần so sánh hai đại lượng: 1) sai số tuyệt đối thực tế, 2) cận trên của sai số tuyệt đối:

$$\frac{\text{sai số tuyệt đối}}{\text{cận trên của sai số tuyệt đối}} = \left| \alpha - \frac{p}{q} \right| : \frac{1}{2q} = 2 \cdot |q\alpha - p|.$$

Người ta quy ước xét một nửa đại lượng này. Ta gọi nó là sai số quy dẫn
$$h = |q\alpha - p|$$

và ghi nhớ: sai số quy dẫn $h$ là một nửa tỉ số giữa sai số tuyệt đối thực tế và sai số lớn nhất có thể.

Hiển nhiên,
$$0 < h \leqslant \frac{1}{2}$$

$h$ càng nhỏ thì phép gần đúng càng có lợi. Nếu $h$ gần bằng không, nghĩa là số $\alpha$ nằm gần một trong hai đầu mút của đoạn
$$\left[ \frac{p-1}{q}, \frac{p}{q} \right].$$ $h$ càng gần $\frac{1}{2}$ thì $\alpha$ càng gần trung điểm của đoạn.

⟦folio 18⟧

Đại lượng

$$\lambda = \frac{1}{2h} = \frac{1}{2 \cdot |q\alpha - p|}$$

gọi là hệ số lợi ích. Ý nghĩa của nó rất đơn giản: hệ số lợi ích cho biết sai số tuyệt đối thực tế nhỏ hơn sai số tối đa có thể có bao nhiêu lần. $\lambda$ càng lớn thì phép gần đúng càng có lợi. Hiển nhiên,

$$1 \leqslant \lambda < \infty,$$

$$\lambda h = \frac{1}{2}.$$

Không nên nghĩ rằng các phần nhỏ hơn luôn cho phép gần đúng chính xác hơn! Có thể xảy ra rằng khi đánh dấu các phần tám trên trục số, số $\alpha$ chiếm vị trí kém lợi hơn so với khi đánh dấu các phần bảy. Hãy làm một thí nghiệm với số $\pi$, xấp xỉ nó bằng các phần khác nhau — từ phần một đến phần mười. Các phép tính được lược bỏ, bạn đọc có thể tự thực hiện chúng.

Hình 2.

sai số không vượt quá 0,0013, bạn sẽ chọn những phần nào? Ta sẽ viết điều kiện $\frac{1}{2q} \leqslant 0,0013$, suy ra $q \geqslant 385$, còn Archimedes đạt được cùng độ chính xác ấy với một mẫu số nhỏ hơn rất nhiều.

Bây giờ bạn đọc đã tin rằng Archimedes chọn các phần bảy không phải ngẫu nhiên chứ?

Nhiều thế kỷ sau, nhà toán học Hà Lan Adrian Meçi đã đưa ra phép gần đúng

$$\pi \approx \frac{355}{113}.$$

Số Mêtius có những tính chất đáng kinh ngạc giống như số Archimedes: mẫu số 113 còn

*) Tính toán cho $\lambda = \frac{1}{2 \cdot 0,0089} = 56,2$. Để nhận đúng các chữ số hàng phần mười, cần lấy $h$ với năm chữ số sau dấu phẩy

⟦folio 19⟧

có lợi hơn các mẫu số gần đó khác. Chúng tôi khuyên bạn đọc khảo sát số Mêtius như ở trên đã khảo sát số Archimedes. Chẳng hạn, hệ số chọn lọc bằng bao nhiêu?

2. Câu đố của Grêgôriô XIII. Grêgôriô XIII không phải là nhà toán học. Ông là giáo hoàng La Mã. Tuy nhiên, tên ông gắn với một bài toán toán học quan trọng — vấn đề lịch.

Tự nhiên cho chúng ta hai đơn vị thời gian tự nhiên: năm và ngày (Mặt Trời). Như đã nói trong một sách giáo khoa vũ trụ học cũ *) “đáng tiếc là, một năm không bằng một số nguyên ngày”. Không thể không đồng ý với điều này, vì từ sự thật đã nêu nảy sinh nhiều bất tiện. Nhưng nó lại sinh ra một vấn đề toán học thú vị.

1 năm =
= 365 ngày 5 giờ 48 phút 46 giây
hoặc

1 năm = 365,242199 ngày.

Không thể hợp pháp hóa trong đời sống dân sự một độ dài năm như vậy. Nhưng điều gì sẽ xảy ra nếu coi một năm bằng 365 ngày? Trên hình 3 cho thấy chính tả học — tên gọi trước đây của một môn học chứa đựng những kiến thức chung về thiên văn học và địa lí tự nhiên.

*) Vũ trụ học — tên gọi trước đây của một môn học chứa đựng những kiến thức chung về thiên văn học và địa lí tự nhiên.

Hình 3.

quỹ đạo Trái Đất. Ngày 1 tháng Giêng năm 1970 lúc 0 giờ Trái Đất ở điểm A. Trong 365 ngày, nó sẽ không đến cùng điểm đó của quỹ đạo và do đó, ngày 1 tháng Giêng năm 1971 lúc 0 giờ sẽ ở điểm B, còn ngày 1 tháng Giêng năm 1972 — ở điểm C, v.v. Sẽ thành ra rằng nếu cố định một ngày nào đó, thì vị trí của Trái Đất trên quỹ đạo mỗi năm sẽ khác (nó sẽ chậm gần 6 giờ).

Sau bốn năm, độ chậm gần bằng một ngày, và ngày cố định sẽ rơi vào những mùa khác nhau, tức là ngày 1 tháng Giêng từ mùa đông sẽ dần chuyển sang mùa thu, rồi sang mùa hè. Điều này bất tiện: các hoạt động định kì (gieo hạt, bắt đầu năm học) sẽ không thể gắn với những ngày lịch nhất định.

Có lối thoát khỏi tình thế này. Cần tính một số năm là 365 ngày, còn một số năm là 366 ngày, xen kẽ chúng sao cho độ dài trung bình của năm càng gần độ dài thực càng tốt. Có thể tái tạo độ dài thực của năm với độ chính xác bất kì, nhưng khi đó có thể xuất hiện một quy luật xen kẽ rất phức tạp giữa các năm ngắn (thường) và năm dài (nhuận), điều không mong muốn. Cần một sự thỏa hiệp: một quy luật xen kẽ các năm tương đối đơn giản, cho độ dài trung bình của năm đủ gần với độ dài thực.

Bài toán này lần đầu tiên được Julius Caesar giải quyết. Dĩ nhiên, từ đúng “giải quyết” chỉ có thể dùng một cách có điều kiện. Nhà thiên văn học Alexandria Sosigenes, được gọi đến Rôma vì mục đích này, đã làm điều đó cho ông. Julius Caesar đưa vào hệ thống sau: ba năm ngắn liên tiếp, năm thứ tư — dài.

Muộn hơn nhiều, khi niên đại Cơ Đốc được chấp nhận, người ta bắt đầu coi những năm có số thứ tự chia hết cho 4 là năm nhuận. Lịch này được gọi là “lịch Julius”. Theo lịch Julius, độ dài trung bình của năm là

$$365 \frac{1}{4} \text{ ngày} = 365 \text{ ngày } 6 \text{ giờ.}$$

⟦folio 21⟧

Lưu ý rằng cách đánh giá như vậy không liên quan đến cách biểu diễn các số nguyên, tức là với một hệ đếm cụ thể nào đó.

Hãy xét số $\frac{61}{27}$. Ước lượng «hơn hai» của chúng ta quá thô và chỉ dùng được như *xấp xỉ thứ nhất*. Nếu muốn làm bước thứ hai, ta phải ước lượng phần thêm $x$. Vì nó nhỏ hơn một đơn vị, tự nhiên biểu diễn nó dưới dạng phân số có tử số là 1 (chúng ta lại viện đến «tính tự nhiên», nhưng đây là lần cuối)

$$\frac{61}{27} = 2 + \frac{1}{x_1}.$$

Bây giờ $x_1$ lớn hơn một đơn vị, và chúng ta lại lặp lại các bước ấy: tách phần nguyên v.v. và v.v. Mời bạn đọc theo dõi cẩn thận sự xen kẽ của hai bước này:

$$\frac{61}{27} = 2 + \frac{7}{27} = 2 + \frac{1}{27} =$$

$$= 2 + \frac{1}{3 + \frac{6}{7}} = 2 + \frac{1}{3 + \frac{1}{7}} =$$

$$= 2 + \frac{1}{3 + \frac{1}{1 + \frac{1}{6}}}.$$

Biểu thức

$$a_0 + \frac{1}{a_1 + a_2 + a_s},$$

trong đó $a_1, a_2, \dots, a_s$ là các số tự nhiên, còn $a_0$ là số tự nhiên hoặc số không, được gọi là phân số liên tục.

Các số $a_0, a_1, a_2, \dots, a_s$ được gọi là các phần tử *) của phân số liên tục. Có thể nói rằng chúng ta đã biểu diễn số $\frac{61}{27}$ dưới dạng phân số liên tục.

*) Đôi khi chúng được gọi là các thương không đầy đủ.

Ký hiệu phân số liên tục có quá cồng kềnh không? Trong ví dụ của chúng ta đã xuất hiện một phân số ba tầng, còn nếu xuất hiện phân số hai mươi tầng thì không thể đặt nó trên một tờ giấy.

Điều đó đúng, vì thế đối với phân số liên tục người ta dùng các quy ước ký hiệu khác nhau. Chúng ta sẽ dùng quy ước sau:

$$a_0 + \frac{1}{a_1 + a_2 + a_s} =$$

$$+ \frac{1}{a_s}$$

$$= [a_0; a_1, a_2, \dots, a_s].$$

Hãy chú ý đến dấu chấm phẩy. Nó nhấn mạnh rằng vai trò của phần nguyên $a_0$ là đặc biệt, không giống vai trò của các số khác (đặc biệt không có nghĩa là quan trọng hơn, trong trường hợp này thì đúng hơn là ngược lại).

Có thể khẳng định rằng mọi số thực *) đều có thể biểu diễn bằng một phân số liên tục và hơn nữa theo một cách duy nhất không?

Trước hết hãy suy nghĩ về ví dụ sau:

$$\frac{1}{6 + \frac{1}{4}} = \frac{1}{6 + \frac{1}{3 + 1}} = \frac{1}{6 + \frac{1}{3 + \frac{1}{1}}}$$

hay theo ký hiệu rút gọn

$$[0; 6, 4] = [0; 6, 3, 1].$$

Phép biến đổi như vậy (tách các đơn vị khỏi phần tử cuối) có thể thực hiện với bất kỳ phân số liên tục nào mà phần tử cuối khác một. Nếu phần tử cuối bằng một, thì có thể cộng nó vào phần tử áp chót. Ví dụ,

$$[1; 10, 3, 7, 1] = [1; 10, 3, 8].$$

Tuy nhiên, dễ chứng minh rằng đây là nguyên nhân duy nhất của tính không duy nhất

*) Tạm thời đang nói về các số hữu tỉ dương. Việc đưa vào các số âm không làm thay đổi bản chất của vấn đề, còn việc đưa vào các số vô tỉ thì làm thay đổi nhiều điều. Điều này sẽ được nói ở dưới.

⟦folio 22⟧

các biểu diễn của số hữu tỉ bằng phân số liên tục.
Có thể chứng minh rằng:
1) Quá trình biến số hữu tỉ $\frac{p}{q}$ ($p$ và $q$ là các số tự nhiên nguyên tố cùng nhau) thành phân số liên tục sẽ kết thúc ở một bước nào đó. Nói cách khác, mọi số hữu tỉ dương đều biểu diễn được dưới dạng $(\cdot)$. Theo điều vừa nói, một biểu diễn như vậy luôn có thể thực hiện với điều kiện $a_s > 1$.
2) Hai phân số liên tục $|a_0; a_1, \dots, a_s|$ và $|b_0; b_1, \dots, b_t|$, trong đó $a_s > 1$ và $b_t > 1$, bằng nhau khi và chỉ khi chúng có cùng số phần tử, tức là $s = t$ và $a_i = b_i$ với $i = 1, 2, \dots, s$.
Chúng tôi sẽ không chứng minh điều này. Mục đích bài báo của chúng tôi là trình bày những ý chính và khuyến khích bạn đọc nghiên cứu vấn đề kỹ hơn qua sách *).
4. Phân số liên tục vô hạn. Còn các số vô tỉ thì sao? Hãy thử khai triển $\sqrt{2} = 1,4142\dots$ thành phân số liên tục. Ta được:
$$\sqrt{2} = 1 + \frac{1}{x_1},$$
$$x_1 = \frac{1}{\sqrt{2} - 1} = \sqrt{2} + 1,$$
$$x_1 = 2 + \frac{1}{x_2}, \quad x_2 = \sqrt{2} + 1 = x_1.$$
Rõ ràng rằng
$$\sqrt{2} = 1 + \frac{1}{x} = 1 + \frac{1}{2 + \frac{1}{x}}$$
$$= 1 + \frac{1}{2 + \frac{1}{2 + \frac{1}{x}}},$$
$$= 1 + \frac{1}{2 + \frac{1}{2 + \frac{1}{x}}},$$
$$= 1 + \frac{1}{2 + \frac{1}{2 + \frac{1}{x}}},$$
trong đó $x = \sqrt{2} + 1$

*) Mọi chứng minh bị lược bỏ ở đây có thể tìm thấy, chẳng hạn, trong cuốn sách của A. Ya. Khinchin “Phân số liên tục”, xuất bản lần thứ 3, 1961.

Ta muốn viết ngay
$$\sqrt{2} = 1 + \frac{1}{2 + \frac{1}{2 + \frac{1}{2 + \frac{1}{2 + \dots}}}},$$
$$= [1; 2, 2, 2, 2, \dots].$$

nghĩa là biểu diễn $\sqrt{2}$ dưới dạng một phân số liên tục vô hạn. Nhưng ở đây cần hết sức thận trọng: ta đã gặp khái niệm mới “phân số thập phân vô hạn”, nhưng chưa biết nó là gì. Chỉ dễ hiểu rằng mỗi số vô tỉ dương tương ứng với một dãy vô hạn được xác định hoàn toàn
$$[a_0; a_1, a_2, \dots],$$
trong đó $a_0$ là một số nguyên không âm, còn mọi $a_i$ có số thứ tự $i \geqslant 1$ là các số tự nhiên. Mọi điều liên quan đến việc này ta sẽ xét chỉ sau *), còn bây giờ hãy bằng lòng với điều ta hiểu được: cách xây dựng theo số dương $\alpha$ khai triển hình thức của nó
$$\alpha \sim [a_0, a_1, a_2, \dots]$$
thành một phân số liên tục hữu hạn hoặc vô hạn **).

5. Phân số hội tụ. Có thể cắt phân số liên tục bằng cách giữ lại các phần tử $a_0, a_1, \dots, a_n$ và bỏ đi $a_{n+1}, \dots$. Phân số nhận được như vậy gọi là phân số hội tụ thứ $n$ và được ký hiệu là $\frac{p_n}{q_n}$. Đặc biệt, khi $n = 0$ ta có phân số hội tụ thứ không $\frac{p_0}{q_0} = \frac{a_0}{1}$.

Ta sẽ thấy rằng $n$ càng nhỏ thì phân số xấp xỉ càng đơn giản (tức là có mẫu số nhỏ hơn). Đồng thời nó có thể được dùng làm giá trị gần đúng của phân số liên tục.

*) Vấn đề này sẽ được xét đầy đủ trong một trong các số báo sau.
**) «~» — dấu tương ứng. Ta chưa thể đặt dấu bằng khi chưa xác định ý nghĩa của ký hiệu đứng ở vế phải.

⟦folio 23⟧

Ví dụ. Lại lấy khai triển số $\frac{61}{27}$ thành phân số liên tục và lập các phân số xấp xỉ

$$\frac{p_0}{q_0} = 2,$$

$$\frac{p_1}{q_1} = [2; 3] = 2 + \frac{1}{3} = \frac{7}{3},$$

$$\frac{p_2}{q_2} = [2; 3, 1] = 2 + \frac{1}{3 + \frac{1}{1}} = \frac{9}{4},$$

$$\frac{p_3}{q_3} = [2; 3, 1, 6] = \frac{61}{27}.$$

Dĩ nhiên, phân số xấp xỉ cuối cùng của số hữu tỉ $\alpha$ bằng $\alpha$.

Ta đã thu được một số giá trị gần đúng ngày càng tốt hơn cho số $\frac{61}{27}$. Để đánh giá chúng, lưu ý rằng $\frac{61}{27} \approx 2,259$.

Giá trị gần đúng thứ 1 là 2, $\Delta = 0,259$ *).

Thứ 2 là $\frac{7}{3} = 2,333, \Delta = -0,074$.

Thứ 3 là $\frac{9}{4} = 2,250, \Delta = 0,09$.

Ta nhận thấy rằng sai số giảm (theo trị tuyệt đối) và có dấu xen kẽ. Đó là quy tắc chung.

Trong trường hợp khai triển số $\sqrt{2} = 1,4142$... thành phân số liên tục, ta được

$$\frac{p_0}{q_0} = 1, \text{ sai số } \Delta = 0,4142,$$

$$\frac{p_1}{q_1} = [1; 2] = \frac{3}{2} = 1,5, \Delta = -0,0858,$$

$$\frac{p_2}{q_2} = [1; 2, 2] = \frac{7}{5} = 1,4,$$

$$\Delta = 0,0142,$$

$$\frac{p_3}{q_3} = [1; 2, 2, 2] = \frac{17}{12} = 1,4167,$$

$$\Delta = -0,0025,$$

$$\frac{p_4}{q_4} = [1; 2, 2, 2, 2] = \frac{41}{29} = 1,4138,$$

$$\Delta = 0,0004.$$

Ở đây chúng ta cũng thấy cùng một bức tranh.

*) Sai số $\Delta$ (xem tr. 17).

6. Tính chất cơ bản của các phân số hội tụ. Bây giờ, không chứng minh, chúng ta sẽ phát biểu tính chất cơ bản của các phân số hội tụ, tính chất sẽ dẫn chúng ta đến lời giải cho các bí ẩn của mình.

Nếu $\frac{p_n}{q_n}$ là một phân số hội tụ của số $\alpha$, thì sai số tuyệt đối

$$|\alpha - \frac{p_n}{q_n}|$$

nhỏ hơn khi xấp xỉ số $\alpha$ bằng bất kỳ phân số nào có mẫu số nhỏ hơn *).

Chẳng hạn, sau khi tìm được phân số hội tụ $\frac{p_3}{q_3}$ cho $\sqrt{2}$, ta có thể chắc chắn rằng phép xấp xỉ $\sqrt{2}$ bằng bất kỳ phân số nào có mẫu số nhỏ hơn 12 sẽ kém hơn.

### III. LỜI GIẢI

7. Bí ẩn của Archimedes. Hãy thử khai triển số này thành phân số liên tục

$$\pi = 3,14159265\ldots$$

$$\pi = 3 + 0,14159265\ldots =$$

$$= 3 + \frac{1}{7 + 0,00885145}.$$

*) Các phân số phù hợp về nhiều phương diện cho những xấp xỉ cực kỳ cao. Tính chất nêu ở đây không phải là duy nhất và cũng không phải quan trọng nhất. Những tính chất khác sẽ được xem xét trong một trong các số báo sau.

⟦folio 24⟧

Ngay ở giai đoạn tính toán này, ta thấy rằng các phân số phù hợp đầu tiên sẽ là

$$\frac{p_0}{q_0} = 3, \quad \frac{p_1}{q_1} = \frac{22}{7}.$$

Hãy tự thực hiện các tính toán và kiểm tra rằng

$$\pi \approx 13; \ 7, 15, 1, 288, 1, \dots.$$

$$\frac{p_2}{q_2} = \frac{333}{106}, \quad \frac{p_3}{q_3} = \frac{355}{113}$$

Thế là hết. Thật đơn giản biết bao! Bảng này hé lộ bí mật của Archimedes, đồng thời cả của Metius. Từ đó thấy:

Xấp xỉ thứ 1: $\pi \approx 3$.

Xấp xỉ thứ 2: $\pi \approx \frac{22}{7}$.

Xấp xỉ thứ 3: $\pi \approx \frac{333}{106}$.

Xấp xỉ thứ 4: $\pi \approx \frac{355}{113}$

(các xấp xỉ lẻ là thiếu, các xấp xỉ chẵn là thừa).

Có thể cho rằng Archimedes và Metius đã bị vạch trần: họ dùng phân số liên tục, Archimedes dùng phân số phù hợp thứ hai, còn Metius — thứ tư?

Không, không thể nói điều đó về Archimedes.

Cần hiểu rõ rằng chúng ta đã giải một bài toán toán học, nhưng không phải bài toán lịch sử. Chúng ta đã giải thích cách có thể đi đến số $\frac{22}{7}$.

Hoàn toàn có thể Archimedes đã dùng phân số liên tục, nhưng không thể xác lập điều đó từ các công trình của ông. Tòa án sẽ không công nhận các lập luận của chúng ta. Các nhà sử học chưa đi đến ý kiến thống nhất. Ưu thế của các phần bảy cũng có thể phát hiện bằng thực nghiệm, bằng cách so sánh chúng với nhiều phân số khác.

Metius lại là chuyện khác. Thật khó tin rằng một phân số phức tạp như $\frac{355}{113}$ lại được tìm ra mà không có lý thuyết. Rất có thể Metius đã dùng phân số liên tục. Dễ hiểu vì sao ông dừng ở phân số phù hợp thứ tư: những phân số tiếp theo cồng kềnh đến mức không dùng được trên thực tế.

8. Bí ẩn của Grêgôriô XIII. Trước hết hãy nghĩ xem chính chúng ta sẽ giải quyết vấn đề xét các năm nhuận như thế nào. Ta sẽ biểu diễn độ dài năm dưới dạng phân số liên tục.

$$1 \text{ năm} = 365^2 5^4 48^3 46^2 = 365,242199^2 = 1365; 4,7,1,3,5,20,6,12]^2.$$

Hơn nữa không. L — một số vô tỉ. Nó được khai triển thành phân số liên tục vô hạn. Độ dài năm là một đại lượng thực nghiệm. Mọi đại lượng thực nghiệm chỉ được xác định với một độ chính xác nhất định, và nói về tính hữu tỉ hay vô tỉ của nó thì không có ý nghĩa. Độ dài năm nêu trên là giá trị được chấp nhận, và ta phải coi nó là chính xác. Nó được biểu diễn bằng một phân số liên tục hữu hạn.

Ta tìm vài phân số phù hợp đầu tiên:

$$\frac{p_0}{q_0} = 365,$$

$$\frac{p_1}{q_1} = 365 + \frac{1}{4} = 365 \frac{1}{4},$$

$$\frac{p_2}{q_2} = 365 + \frac{1}{4 + \frac{1}{7}} = 365 \frac{7}{29},$$

$$\frac{p_3}{q_3} = 365 + \frac{1}{4 + \frac{1}{7 + \frac{1}{1}}} = 365 \frac{8}{33},$$

$$\frac{p_4}{q_4} = 365 + \frac{1}{4 + \frac{1}{7 + \frac{1}{1 + \frac{1}{3}}}} = 365 \frac{31}{128}.$$

Phân số xấp xỉ nào đưa ra lời giải cho vấn đề lịch. Chẳng hạn, xấp xỉ $365 \frac{1}{4}$ dẫn đến lời giải của Julius Caesar: một năm nhuận trong mỗi bốn năm. Không ai đề nghị dùng xấp xỉ $365 \frac{7}{29}$, dường như vì xấp xỉ tiếp theo

⟦folio 25⟧

365/33 chỉ phức tạp hơn chút ít, nhưng chính xác hơn đáng kể. Lịch mà theo đó tám năm nhuận phải được tính trong mỗi ba mươi ba năm đã được đề nghị bởi triết gia, nhà toán học, nhà thiên văn học Turkmen-Ba Tư vĩ đại Omar Khayyam (1040—1123).

Các số liệu về độ chính xác của các xấp xỉ tìm được đối với độ dài năm thực được cho trong bảng sau.

| № xấp xỉ | Sự xen kẽ các năm nhuận | Độ dài trung bình của năm | Sai số |
| :--- | :--- | :--- | :--- |
| 1 | 1 năm nhuận trong mỗi 4 | 365ᵃ 6ᵃ 00ᵃ 00ᵇ | -11ᵃ 14ᵇ |
| 2 | 7 》 》 》 29 | 365ᵃ 5ᵃ 47ᵃ 35ᵇ | +1ᵃ 11ᵇ |
| 3 | 8 》 》 》 33 | 365ᵃ 5ᵃ 49ᵃ 05ᵇ | -19ᵇ |
| 4 | 31 》 》 》 128 | 365ᵃ 5ᵃ 48ᵃ 45ᵇ | +1ᵇ |

Trong cột «Sai số», dấu trừ chỉ rằng độ dài trung bình của năm lớn hơn độ dài thực.

Phương án thứ tư đặc biệt chính xác. Sai số 1 giây không có ý nghĩa thực tế nào. Vì vậy đã có những đề nghị sử dụng lịch này. Chẳng hạn, năm 1864, nhà thiên văn học Nga Medler đã đề nghị đưa lịch như vậy vào Nga từ thế kỷ XX. Muốn vậy cần đưa vào lịch Julius điều chỉnh sau: cứ mỗi 128 năm bỏ một năm nhuận (vì theo lịch Julius, trong 128 năm có 32 năm nhuận). Tuy nhiên, lịch này không được chấp nhận ở đâu trên thế giới, dường như vì chu kỳ 128 là «không tròn».

Sau khi giải bài toán toán học, ta trở lại bài toán lịch sử. Những suy xét của Gregory XIII (hoặc các cộng sự của ông) là gì?

Ở đầu bài đã nói rằng độ dài trung bình của năm Gregory là 365 ngày 5 giờ 49 phút 12 giây.

Giá trị này khác giá trị thực tới 26 giây. Có cảm giác rằng Giáo hoàng Gregory XIII hoặc các cố vấn học giả của ông đã nghĩ ra ca---

nomê (chẳng phải vô cớ mà ông được gọi là Alphonse-nhà thiên văn). Những bảng này lần đầu được xuất bản ở Venice một trăm năm sau khi tác giả của chúng qua đời. Trong đó cho độ dài năm như sau:

1 năm = 365ᵃ 5ᵃ 49ᵃ 16ᵇ.

Nếu dùng các bảng này, ủy ban hẳn phải đi đến kết luận rằng độ dài trung bình của năm lịch do ông đề nghị chỉ khác độ dài thực bốn giây. Nếu ủy ban có biết đề nghị của Omar Khayyam, thì họ hẳn đi đến kết luận rằng lịch của ông cho sai số 11 giây.

Xin nói thêm rằng không có cơ sở nào để cho rằng ủy ban của Gregory XIII đã sử dụng phân số liên tục. Họ đã cần mẫn, đổ mồ hôi công sức để chọn sự phù hợp cần thiết.

Còn về Omar Khayyam, các học giả cho rằng ông nắm được, nếu không phải toàn bộ lý thuyết phân số liên tục, thì một cách tiếp cận nguyên tắc tương tự đối với các bài toán về những xấp xỉ hợp lý nhất bằng các phân số có mẫu số nhỏ. Vào thời đại của ông, khoa học phương Đông trên nhiều phương diện đứng cao hơn khoa học châu Âu.
