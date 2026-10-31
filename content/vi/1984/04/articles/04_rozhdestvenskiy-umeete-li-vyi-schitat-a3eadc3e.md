---
id: 1984-4-rozhdestvenskiy-umeete-li-vyi-schitat-a3eadc3e
issue: kvant_1984_4
year: 1984
number: "4"
title: Bạn có thể đếm được không?
authors:
  - Рождественский В. В.
rubric: osnovnye-stati
page_first: 13
page_last: 15
page_labels: 11-13
tag: HOZE
lang: vi
source: kvant_digital
extraction: vision
content_sha256: bba441c24f5b24c0ae42fb51018beea14f70458db320b4541fee330b68eec91d
prompt_sha256: draft-1
translated_from: content/ru/1984/04/articles/04_rozhdestvenskiy-umeete-li-vyi-schitat-a3eadc3e.md
source_content_sha256: 74653efd0c2b5cac79a83b502aa9922cbbf8861c1663823cbea369d8936c1429
translation_model: draft
translation_run: vi-draft-2026-10-31
translation_quality: draft
---

⟦folio 11⟧

Bạn có thể đếm được không?

V. V. ROZHDESTVENSKY

Những thập kỷ gần đây được đặc trưng bởi sự phát triển nhanh chóng và phổ biến của công nghệ máy tính. Máy tính điện tử, máy tính để bàn, máy bỏ túi và các thiết bị tính toán khác có thể giảm đáng kể thời gian của tất cả các loại tính toán. Và đôi khi bạn có thể nghe học sinh nói rằng “khả năng đếm” bây giờ là không cần thiết chút nào. Nhưng nghịch lý thay, công nghệ lại mang đến sự hỗ trợ hiệu quả nhất cho những ai có thể tính toán chính xác.

Chúng tôi sẽ cố gắng chỉ cho người đọc những khó khăn nảy sinh trong thực tế

Những ví dụ khó hiểu

Ví dụ 1. Khi tính biểu thức $x=1/3\cdot 3/5\cdot 5/7\cdot 7/8\cdot 8$ trên máy tính thực với độ chính xác đến hai chữ số thập phân, cùng với đơn vị dự kiến ​​ta được $x=0,88$. Nếu tính $1/8\cdot 8/7 \times 7/5\cdot 5/3\cdot 3$ thì kết quả là 0,90.

Ví dụ 2. Khi cộng các số $1+1/2+1/3+1/4+\ldots+1/250\ 000$ với chữ số thập phân thứ năm trên máy tính từ trái sang phải thì kết quả là 12,88777 và từ phải sang trái kết quả là 12,95821; chúng tôi thấy rằng sự khác biệt trong các câu trả lời lớn hơn từng điều khoản của đa số.

Ví dụ 3: Giá trị gần đúng của $\sqrt{290}$ là 17,029 (sai số nhỏ hơn 0,0004). Khi tính phân số $1/(\sqrt{290}-17)$ có chữ số thập phân thứ ba thì kết quả là 34,483. Tuy nhiên, nếu phân số được chuyển về dạng $\sqrt{290}+17$ thì kết quả của phép cộng sẽ là 34,029, với sai số nhỏ hơn 0,0004. Do đó, đáp số 34.483 thành phố khó khăn hơn.

⟦folio 12⟧

Ví dụ 4. Giải pháp hệ thống
$$\begin{cases} x+5y=17, \\ 1,5x+7,501y=25,503 \end{cases}$$

là một cặp số (2; 3). Nếu bạn thay đổi số 25.503 chỉ 0,003 -
$$\begin{cases} x+5y=17, \\ 1,5x+7,501y=25,5, \end{cases}$$

thì nghiệm sẽ là cặp (17; 0). Nếu trong hệ thống ban đầu, số 7.501 được thay thế bằng 7.499 -
$$\begin{cases} x+5y=17, \\ 1,5x+7,499y=25,503, \end{cases}$$

thì nghiệm sẽ là (32; - 3).

Những ví dụ như thế này có thể khiến người mới bắt đầu làm quen với máy tính bối rối. Để điều hướng chính xác các tình huống tích cực, bạn cần biết:
1) lỗi là gì và chúng đến từ đâu?
2) làm thế nào để mô tả số lượng lỗi,
3) cách tổ chức các phép tính một cách chính xác.

Phân loại lỗi

Lỗi có thể được chia thành ba loại*).

1) Lỗi có trong thông tin nguồn. Dữ liệu ban đầu trong bất kỳ bài toán nào thường là các cấu trúc xuất hiện thường xuyên hoặc các giá trị thu được do đo lường. Nhưng bất cứ thiết bị đo nào cũng có độ phân giải nhất định. Ví dụ, trên cân thương mại, không thể phát hiện ra sự khác biệt 1 g, vì vậy nếu bạn trả tiền cho 100 g dầu, có hại gì khi tin rằng bạn sẽ nhận được chính xác 100 g chứ không phải 101 g hay 99 g? Lỗi đo lường cũng có thể phát sinh do kết quả đọc của thiết bị không chính xác hoặc do xem sơ bộ.

Tuy nhiên, loại trừ hai nguồn sai sót cuối cùng do nguyên tắc chủ quan gây ra, vẫn phải chấp nhận thực tế rằng sai sót trong dữ liệu gốc là không thể tránh khỏi và do tính chính xác của dụng cụ đo. Cuối cùng, việc thao tác với dữ liệu gốc không đảm bảo rằng kết quả sẽ chính xác hơn dữ liệu. Một tuyên bố như sau: “diện tích được vẽ trên giấy

*) Các nguồn sai sót khác nhau phát sinh trong quá trình xử lý dữ liệu thử nghiệm và điều gì sẽ xảy ra nếu tránh được chúng cũng được mô tả trong bài báo “Lừa dối hay ảo tưởng?” của A. N. Zaidel? («Kvant», 1983, số 5, trang 24).

của một đường tròn có bán kính được thay đổi bằng thước là 3206,9569 mm2,” ít nhất là ngây thơ.

2) Lỗi làm tròn. Đây là những lỗi công nghệ có đặc điểm tương đương gần đúng. Thực tế là không có “phương tiện” tính toán nào, dù là máy tính hay con người, có thể thực hiện các phép tính số học với chuỗi vô hạn. Do đó, tất cả dữ liệu và kết quả trung gian phải được ghi lại bằng một bộ số giới hạn và do đó thường không chính xác.

3) Hạn chế lỗi. Rất nhiều phép tính được mô tả là một chuỗi sàng lọc kết quả vô tận hoặc có quy mô lớn về mặt thiên văn. Đương nhiên, người ta sẽ xử lý quá trình như vậy vào một lúc nào đó và hài lòng với giá trị gần đúng cuối cùng thu được. Một ví dụ là quá trình tính toán $\sqrt{a}$ bằng phương pháp xấp xỉ liên tiếp:

$$x_1 = (a+1)/2, \dots, x_{n+1} = (a/x_n + x_n)/2, \dots$$

Vì vậy chúng tôi thấy rằng sai sót là điều không thể tránh khỏi. Điều này có nghĩa là cần phải giảm số lượng chúng để đánh giá nhằm thu được kết quả với độ chính xác cần thiết.

Truyền bá lỗi

Vì các quy trình tính toán cuối cùng đều bắt nguồn từ việc thực hiện bốn phép tính số học, nên hãy xem điều gì xảy ra với các lỗi khi thực hiện các hành động này.

Để đơn giản, chúng ta sẽ giả định rằng tất cả các đại lượng đang được xem xét (có thể là dữ liệu ban đầu, kết quả trung gian hoặc kết quả cuối cùng) đều dương. Giá trị chính xác của chúng sẽ được ký hiệu là $x, y, \dots$ và các giá trị gần đúng tương ứng sẽ được ký hiệu là $x, y, \dots$.

Đặc điểm của độ chính xác gần đúng là sai số tuyệt đối (hoặc sai số) $\Delta_x = x - x_i$ và sai số tương đối $\omega_x = \Delta_x/x$. Bảng 1 chứa các công thức biểu thị sự phụ thuộc của sai số tuyệt đối và tương đối của kết quả các phép tính số học vào lỗi dữ liệu (bạn hãy tự kiểm tra các công thức này!).

Đối với những thay đổi thực tế về giá trị tuyệt đối và phép tính, giá trị chính xác của giá trị tuyệt đối và

⟦folio 13⟧

Sai lầm tuyệt đối
Lỗi tương đối

$\Delta_{x+y} = \Delta_x + \Delta_y$
$\Delta_{x-y} = \Delta_x - \Delta_y$
$\Delta_{x\cdot y} = x\Delta_y + y\Delta_x + \Delta_x\Delta_y$
$\Delta_{x/y} = \left( \frac{\Delta x}{y} - \frac{x}{y} \right)\frac{\Delta y}{y}$
: $\left( 1 + \frac{\Delta y}{y} \right)$

lỗi tương đối không xác định (vì không xác định được giá trị chính xác của đại lượng đang xem xét). Tuy nhiên, khi biết độ chính xác của dụng cụ đo, các quy tắc làm tròn kết quả trung gian, v.v., thường có thể đảm bảo rằng sai số tuyệt đối hoặc tương đối không vượt quá giá trị tuyệt đối của các giá trị không phải số bát phân - giới hạn của các sai số này. Nếu giới hạn sai số cho các giá trị $x$ và $y$ được đưa ra thì từ các công thức trong Bảng 1, có thể dễ dàng thu được giới hạn sai số cho $x+y$, $x-y$, $xy$ và $x/y$ (xem Bảng 2, giả định rằng $|\Delta_x| \leq \Delta_1$, $|\Delta_y| \leq \Delta_2$, $|\omega_x| \leq \omega_1$, $|\omega_y| \leq \omega_2$).

Bảng 2
Giới hạn lỗi tuyệt đối
Giới hạn lỗi tương đối

$|\Delta_{x+y}| \leq \Delta_1 + \Delta_2$
$|\Delta_{x-y}| \leq \Delta_1 + \Delta_2$
$|\Delta_{x\cdot y}| \leq x\Delta_2 + y\Delta_1 + \Delta_1\Delta_2$
$|\Delta_{x/y}| \leq \frac{y\Delta_1 + x\Delta_2}{y^2}$
: $\left( 1 + \frac{\Delta y}{y} \right)$

Trong bảng này, công thức tính sai số tuyệt đối của thương $\Delta_{x/y}$ nổi bật: nó bao gồm chính sai số $\Delta_y$ và ranh giới của nó $\Delta_2$, do đó, $|\Delta_{x/y}|$ có thể trở thành lớn tại $\Delta_y < 0$, ngay cả khi $\Delta_1$ và $\Delta_2$ nhỏ.

Phân tích các ví dụ

Bây giờ chúng ta hãy cố gắng hiểu điều gì giải thích cho những “điều kỳ lạ” mà chúng ta gặp phải trong các ví dụ được đưa ra ở đầu bài viết.

Ví dụ 1. Theo quy tắc số học tổng quát trong tích của phân số $\frac{1}{3} \cdot \frac{3}{5} \cdot \frac{5}{7} \cdot \frac{7}{8} \cdot \frac{8}{1}$, bạn có thể sắp xếp lại tử số và mẫu số theo ý muốn mà không làm thay đổi kết quả. Từ ví dụ của chúng tôi, rõ ràng là trong số học các phép tính gần đúng, điều này không còn đúng nữa. Để hiểu sự khác biệt trong kết quả phát sinh như thế nào, hãy lấy một ví dụ đơn giản - chúng tôi tính biểu thức $(1 \cdot 3)/3$ theo hai cách (chính xác đến hai chữ số thập phân). chúng tôi có
$$1,0 \times 3,0 = 3,0, \quad 3,0 \times 3,0 = 1,0,$$
nhưng mặt khác,
$$1,0/3,0 = 0,33, \quad 0,33 \times 3,0 = 0,99.$$
Nếu có nhiều phép tính số học thì sự khác biệt trong các câu trả lời có thể còn lớn hơn.

Ví dụ 2 cho thấy kết quả của phép cộng gần đúng một số số có thể phụ thuộc vào thứ tự xảy ra. Hãy xem xét một ví dụ đồ họa hơn. Hãy tính tổng
$$100 + 0,1 + 0,1 + \dots + 0,1,$$
2000 lần
làm tròn tất cả các kết quả đến ba chữ số gần nhất. (Hãy nhớ rằng các giá trị là tất cả các chữ số trong ký hiệu của một số, bắt đầu bằng số khác 0 đầu tiên từ bên trái; giả sử, trong các số 0,017 và 1,7, mỗi số có hai chữ số, trong số 170 có ba chữ số.) Nếu chúng ta cộng từ trái sang phải, trước tiên chúng ta nhận được $100 + 0,1 = 100,1$ và sau khi làm tròn lại 100; Kết quả này rất phi tuyến tính và sẽ không thay đổi trong tương lai. Khi cộng từ phải sang trái, ta được tuần tự: $0,1 + 0,1 = 0,2, \quad 0,2 + 0,1 = 0,3, \quad \dots \quad 99,9 + 0,1 = 100$. Một nghìn số hạng tiếp theo sẽ không làm thay đổi kết quả, nhưng với phép cộng cuối cùng, chúng ta nhận được $100 + 100 = 200$. Đây đã là mức tốt nhất, nhưng vẫn còn xa so với đáp số 300 chính xác, có thể đạt được bằng cách cộng số lượng các số 0,1, do đó cũng là số 0,1 và sau đó là ba số hàng trăm. Ví dụ này làm cho quy tắc ngón tay cái sau đây khá rõ ràng:

tổng của một số lượng lớn các thuật ngữ phải được tổ chức theo cách sao cho
