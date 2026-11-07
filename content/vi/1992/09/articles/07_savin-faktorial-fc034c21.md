---
id: 1992-9-savin-faktorial-fc034c21
issue: kvant_1992_9
year: 1992
number: "9"
title: giai thừa
authors:
  - Савин А. П.
rubric: kaleydoskop-kvanta
rubric_sub: Калейдоскоп
page_first: 42
page_last: 43
page_labels: 40-41
lang: vi
source: kvant_digital
extraction: vision
content_sha256: 02b73c47c03efe7acbc29d35098a29a8ba27b78b752f3bf5f6782e1e5c93d770
prompt_sha256: draft-1
translated_from: content/ru/1992/09/articles/07_savin-faktorial-fc034c21.md
source_content_sha256: e76ec4eb5203484675f06e654fcd9629243c61d9114d08852ceb2799afe82994
translation_model: draft
translation_run: vi-draft-gaps-2026-11-07
translation_quality: draft
---

⟦folio 40⟧

---
running_head:
folio:
---

giai thừa

Vào những năm 1930, trong nhiều căn hộ có hàng bảy con voi ở những nơi dễ nhìn thấy. Người ta tin rằng chúng sẽ mang lại hạnh phúc, giống như chiếc móng ngựa đóng trên cửa. Những con voi được xếp hàng theo chiều cao. Và có bao nhiêu cách khác để sắp xếp đồ vật còn lại vào vị trí cuối cùng mà không làm tăng số phương án, số phương án đó là 3·2·1=6.

Vào thời điểm gần đây, khi Nam Tư còn là một Liên bang gồm sáu nước cộng hòa, trên lá cờ của nước này gồm có ba vật được sắp xếp theo chiều ngang, chúng ta thấy rằng bất kỳ vật nào trong số chúng có thể được đặt ở vị trí đầu tiên, ba vị trí tiếp theo và ba vật thể còn lại có thể được xếp theo 3 2 1 = 6 cách. Vậy tổng số cách là 4·3·2·1=24. Bây giờ bạn có thể dễ dàng chứng minh rằng số cách sắp xếp n đồ vật là n(n-1)...2·1. Biểu thức này khá rườm rà nhưng lại gặp trong nhiều bài toán nên có một ký hiệu đặc biệt n! được phát minh ra cho nó, được gọi là en giai thừa từ từ yếu tố tiếng Anh - yếu tố.

Hãy quay trở lại với những chú voi của chúng ta. Có bảy người trong số họ, vì vậy số in của họ là 37·10⁴, một con số thực sự khổng lồ!

Giai thừa không chỉ xuất hiện trong các tình huống liên quan đến hoán vị của các phần tử. Dễ dàng chứng minh rằng đạo hàm bậc n của hàm xⁿ bằng n!. Giai thừa có thể được coi là một hàm xác định các giá trị tự nhiên của một biến, nhưng rất khó để làm việc với nó - nó không thể lấy vi phân hoặc tích phân. Do đó, điều quan trọng là phải giảm nó bằng cách ước tính nó bằng các hàm đơn giản hơn, ví dụ: xảy ra các bất đẳng thức sau:

nⁿ > n! > nⁿ/2.

Điều đầu tiên trong số này xuất phát từ thực tế là trong tích n! mọi yếu tố đều không

chúng trên kệ? Bảy? Sáu mươi? Năm trăm? Thì ra có hơn năm nghìn! Hãy hiểu con số lớn hơn này đến từ đâu. Một mục và được cài đặt một cách độc đáo. Hai - theo hai cách. Nếu bạn và một người bạn vào một phòng, thì anh ấy sẽ vào trước, sau đó là bạn, hoặc ngược lại, bạn trước, sau đó là anh ấy. Vật phẩm có thể được sắp xếp theo sáu cách khác nhau. Thật vậy, vị trí đầu tiên có thể được lấy từ họ (3 tùy chọn), sau đó vị trí thứ hai có thể được lấy bởi bất kỳ ai trong số hai tùy chọn còn lại, tức là mỗi tùy chọn ban đầu đầu tiên được nhân đôi.

(Serbia) trùng với quốc kỳ của cả nước. Nếu chúng ta đặt câu hỏi về số lượng, có bao nhiêu cách xếp một bộ bài gồm 36 lá bài? Tất nhiên là 36! theo những cách gần đúng

n lớn, và số thứ hai - từ thực tế là tích của các số nhân, một số bằng nhau ở một đầu và một ở đầu kia, không nhỏ hơn n.

Chúng ta cũng đã tìm được hàm liên tục nhận giá trị n! khi giá trị đối số là n. Hàm này được đề xuất bởi Leonhard Euler, gọi nó là hàm lamma:

⟦folio 41⟧

---
running_head:
folio:
---

$$\Gamma(x) = \int_0^\infty e^{-i t} t^{x-1} dt.$$
Đối với hàm này, đẳng thức $\Gamma(n+1) = n!$ là hợp lệ. Không khó để tính $\Gamma(1) = 1$, do đó (và không chỉ vì lý do này) chúng ta giả định rằng $0! = 1$. Một hàm khác được L. Euler giới thiệu cũng được định hướng bằng giai thừa - hàm beta:
$$B(x; y) = \int_0^1 (1-t)^{x-1} t^{y-1} dt = \frac{\Gamma(x+y)}{\Gamma(x) \Gamma(y)}.$$
Hãy xem xét một bài toán khác. Có 10 cầu thủ trong một đội bóng chuyền. Sáu người ra sân, và bốn người đang “dự bị” vào lúc này. Có bao nhiêu cách bạn có thể chọn trò chơi thứ sáu? Hãy bắt đầu suy nghĩ theo cách tương tự như trước: người chơi đầu tiên có thể được chọn theo mười cách, người thứ hai có chín cách, ..., người thứ sáu có năm cách. Ito $10 \cdot 9 \cdot 8 \cdot 7 \cdot 6 \cdot 5$ cách. Nhưng đồng thời, chúng tôi sẽ chọn sáu người chơi giống nhau nhiều lần, vì họ có thể được đưa vào sáu người theo thứ tự khác nhau và những người này có thể được tạo thành 6! cách. Điều này có nghĩa là số cách là $10 \cdot 9 \cdot 8 \cdot 7 \cdot 6 \cdot 5 \times 6 \cdot 5/6! = 210$. Nếu biểu thức này được nhân và chia cho 4!, thì chúng ta nhận được $10!/(6!4!)$; Nói chung, số lượng lựa chọn để chọn phần tử $k$ từ $n$ bằng
$$\frac{n!}{k!(n-k)!}.$$
Biểu thức này còn có một ký hiệu đặc biệt, thậm chí là hai ký hiệu: $C_k^n$ và $\binom{n}{k}$.
Người ta đã đề cập rằng việc sử dụng các hàm $n!$ là rất khó, do đó, các công thức gần đúng sẽ được sử dụng cho nó, ví dụ như công thức được đề xuất vào năm 1730 bởi nhà toán học người Anh J. Stirling:
$$n! = \sqrt{2\pi n} n^n e^{-n}.$$
Ký hiệu $n!$ hóa ra rất tiện lợi và được mở rộng cho các tác phẩm khác. Vì vậy, tích $2 \cdot 4 \cdot \dots \cdot 2n$ bắt đầu được ký hiệu là $(2n)!!$ và $1 \cdot 3 \times \dots \cdot (2n+1)!!$ là $(2n+1)!!$. Tất nhiên, $(2n)!!$ không giống với $((2n)!!)$ - số thứ hai lớn hơn nhiều so với số thứ nhất. Ngoài ra còn có một chỉ định chung hơn $(kn+p)!! = p(k+p)(2k+p) \dots (nk+p)$.
Và các sinh viên vật lý tại Đại học quốc gia Moscow đã đặt giai thừa dưới dấu hiệu cấp tiến trên biểu tượng của khoa họ.
