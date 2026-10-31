---
id: 1986-11-kaymin-postroenie-dialogovyih-algoritmov-75c24f3b
issue: kvant_1986_11
year: 1986
number: "11"
title: Xây dựng thuật toán đối thoại
authors:
  - Каймин В. А.
rubric: raznoe
rubric_sub: Разное
page_first: 42
page_last: 50
page_labels: 40, 41, 42, 48
tag: 3UBX
lang: vi
source: kvant_digital
extraction: vision
content_sha256: 6ff57d4a50f06dd7f29204e082cbb8e8da8d43b8c79f278164e8b7f5faaa0bb1
prompt_sha256: draft-1
translated_from: content/ru/1986/11/articles/15_kaymin-postroenie-dialogovyih-algoritmov-75c24f3b.md
source_content_sha256: 6af7a6b607da63621e3ce6b77fc9c97bcdb94fc23690430485bc8812293874bb
translation_model: draft
translation_run: vi-draft-2026-10-31
translation_quality: draft
---

⟦folio 40⟧

Xây dựng thuật toán đối thoại

Ứng viên khoa học kỹ thuật
V. A. KAIMIN

Ghi chú này chủ yếu dành cho học sinh lớp 10 đang học khóa học “Cơ bản về Công nghệ Thông tin và Máy tính”, nhưng nó cũng sẽ hữu ích cho tất cả những ai làm việc với máy tính cá nhân.

Cuộc đối thoại giữa con người và máy tính về nhiều mặt tương tự như cuộc đối thoại giữa hai người. Cuộc đối thoại giữa hai người là sự trao đổi thông điệp, cụm từ, cử chỉ và câu cảm thán. Cuộc đối thoại giữa con người và máy tính giống cuộc trò chuyện giữa con người trên điện thoại hay chính xác hơn là trên điện thoại video. Các tin nhắn (thông tin) từ máy tính thường được hiển thị trên màn hình tivi kết nối với máy tính. Trong tin nhắn đáp số trên máy tính, một người nhập lệnh, đáp số hoặc yêu cầu thông qua bàn phím tương tự như bàn phím của máy đánh chữ. Trong đáp số, để đáp lại hành động của con người, máy tính hiển thị các thông báo mới trên màn hình và chờ đầu vào các lệnh, dữ liệu hoặc yêu cầu mới.

Các chương trình đối thoại, tùy theo mục đích của chúng, có thể được chia thành trò chơi, giáo dục, kinh doanh và nhạc cụ. Các chương trình trò chơi được sử dụng để giải trí trong thời gian rảnh rỗi sau khi làm việc hoặc học tập. Chương trình giảng dạy được sử dụng để dạy học sinh hoặc học sinh. Các chương trình kinh doanh được sử dụng để lời giải sản xuất bài toán, tích lũy và xử lý thông tin. Các chương trình công cụ được sử dụng để tạo ra các chương trình mới.

Bất kỳ chương trình đối thoại nào cũng dựa trên các quy tắc và thuật toán nhất định để tiến hành đối thoại. Các quy tắc bắt buộc để tiến hành bất kỳ cuộc đối thoại nào là:

1. thông báo (“Chào buổi chiều”
2. request("Tên của bạn", tên)
3. đầu ra("2 2=", x, "?")

Lệnh “báo cáo” chỉ định một cụm từ tiêu chuẩn được truyền đạt tới đối tác đối thoại; trong ví dụ trên, đây là cụm từ “Chào buổi chiều”. Lệnh “truy vấn” chứa hai đối số: đối số đầu tiên là cụm từ truy vấn được chuyển cho đối tác và đối số thứ hai là tên của biến trong đó đáp số sẽ được viết (một cụm từ hoặc một số, tùy thuộc vào loại biến). Các lệnh thuộc loại “đầu ra” có thể chứa một hoặc nhiều đối số - đây là các cụm từ hoặc tên của các biến mà thông báo được rút ra - “đầu ra”. Chúng tôi sẽ thêm ba lệnh này vào ngôn ngữ thuật toán từ sách giáo khoa. Hãy để chúng tôi đưa ra một ví dụ về việc xây dựng một thuật toán đối thoại. (Để tiết kiệm dung lượng, một phần tiêu đề chương trình đã bị bỏ qua ở đây và bên dưới.)

hẹn hò Alg
sự khởi đầu
« thông báo ("Chào buổi chiều"
yêu cầu("Tên của bạn =", tên)
đầu ra (“Rất vui được gặp bạn”, tên!)
lừa đảo

Đoạn hội thoại ví dụ:

Ví dụ tiếp theo, hãy xem xét một thuật toán hộp thoại đơn giản cho trò chơi đoán. Hai người tham gia trò chơi: người thứ nhất đoán một số nguyên x trong khoảng từ 1 đến 100, và người thứ hai cố gắng đoán nó bằng cách chỉ ra các số: p₁, p₂,.... Trong đáp số, khi đưa ra số, người thứ nhất nói:

⟦folio 41⟧

“xuất sắc”, “ít” hoặc “nhiều” tùy thuộc vào sự tương ứng giữa con số được chỉ định và con số dự kiến. Trò chơi kết thúc với những câu “làm tốt lắm”, “cô gái thông minh” ngay sau khi tính ra con số dự định.

Thuật toán tiến hành cuộc đối thoại cho người đầu tiên (đó sẽ là máy tính) và một ví dụ về cuộc đối thoại được đưa ra dưới đây. Thuật toán sử dụng hàm đặc biệt “x := ngẫu nhiên (a, b)”, tạo ra một số nguyên ngẫu nhiên giữa a và b.

đại số: đoán
sự khởi đầu
x: = ngẫu nhiên(1, 100)
sosbi (“đoán số”)
báo cáo (“từ 1 đến 100”)
yêu cầu("số ==", p)
trong khi p≠x
không
nếu p<x,
sau đó thông báo (“nhỏ”)
inchae thông báo (“rất nhiều”)
Tất cả
yêu cầu("số ==", p)
ki
sosbi (“xuất sắc”)
sosbi (“làm tốt lắm, cô gái thông minh”)
lừa đảo
Đoạn hội thoại ví dụ (cho x=67):

Đoán số
từ 1 đến 100
số = ? 50
một vài
số = ? 75
nhiều

số=? 62
một vài
số=? 67
Tuyệt
làm tốt lắm cô gái thông minh

Người thứ hai có thể chọn số giả thuyết bằng nhiều cách. Phương pháp tốt nhất đảm bảo đoán được các số trong phạm vi cho trước từ 1 đến 100 trong 7 bước. Phương pháp này dựa trên nguyên tắc chia quãng làm đôi (xem «Kvant» Số 10, trang 49).

Việc biên soạn các thuật toán hội thoại và xây dựng chương trình hội thoại cho máy tính có thể được hệ thống hóa (xem «Kvant» Số 10, trang 47). Một bước bổ sung trong việc thiết kế có hệ thống các thuật toán và chương trình đối thoại là biên soạn sơ bộ kịch bản đối thoại.

Kịch bản hội thoại là sự mô tả về tổng thể tất cả các thông điệp được cung cấp cho đối tác đối thoại và hệ thống phản hồi trong đáp số đối với các thông điệp của anh ta. Để mô tả thống nhất một tập hợp các thông điệp trong tin học, người ta sử dụng một hệ thống ký hiệu chuyên biệt nhưng không phức tạp. Hãy xem xét nó bằng cách sử dụng ví dụ mô tả kịch bản “trò chơi: đoán”.

Kịch bản "trò chơi: đoán"

Ở đây p là một số nguyên

Ở đây phần tử có thể thay đổi của văn bản (tin nhắn của người thứ hai) được khoanh tròn màu đỏ. Một phần văn bản có thể thay đổi được đặt trong khung màu đỏ, mô tả ngôi thứ nhất đáp số cho số giả thuyết tiếp theo. Trong dấu ngoặc nhọn ở bên phải được chỉ định đáp số, được chọn tùy thuộc vào các điều kiện nhất định (so sánh giữa bí ẩn và các con số được chỉ định). Dấu ngoặc nhọn của dấu vết biểu thị các phần của văn bản được lặp lại (ở đây là sự lặp lại của “truy vấn - đáp số” khi đoán số).

Việc xây dựng các thuật toán và chương trình với mô tả sơ bộ về tình huống cho phép bạn suy nghĩ trước về sự rõ ràng, mạch lạc logic và khéo léo trong cuộc đối thoại.

⟦folio 42⟧

ha, vì đây không phải là thuộc tính của thuật toán mà là thuộc tính của tập lệnh. Hơn nữa, sự hiện diện của một mô tả đầy đủ về kịch bản và mô tả các phương thức lời giải do bài toán đặt ra cho phép chúng tôi xử lý một cách có hệ thống việc có - không có lỗi trong thuật toán.

Để minh họa, chúng tôi trình bày việc xây dựng thuật toán đối thoại lời giải bài toán “ném bóng vào rổ”, thuật toán này chuyển thành trò chơi hai người.

Người chơi thứ nhất cầm rổ và cho người chơi thứ hai biết khoảng cách đến rổ. Người chơi thứ hai chọn tốc độ và góc ném bóng ban đầu và báo cáo dữ liệu này cho người thứ nhất. Tại đáp số người chơi đầu tiên báo cáo “đánh”, hoặc “dưới mức” hoặc “vượt quá” với giá trị tính bằng mét.

Vấn đề: Ném bóng vào rổ
Được cho:
L—khoảng cách tới rổ (m)
V₀ - tốc độ ban đầu (m/s)
α₀ — góc ném (erad)
D – đường kính giỏ (m)
Yêu cầu: đánh - dấu hiệu đánh r - khoảng cách còn lại (m)
Sự liên quan:
r = |L - l| (khoảng cách còn lại)
đánh = {r < D/2} (điều kiện trúng)
l = V₀ t (phạm vi bay)
0 = V₀ t - gt²/2 (điều kiện trúng)
V₀ = V₀ cos(α₀ π/180) (tốc độ ngang (t = 0))
V₀ = V₀ · sin(α₀ · π/180) (tốc độ dọc (t = 0))
g = 9,81 (gia tốc trọng trường)

Tại
{D > 0 (độ rộng giỏ dương)
V₀ > 0 (vận tốc dương)
0° < α₀ < 90° (dung sai góc)
Phương pháp
đánh = ||L - l| < D/2 (điều kiện trúng đích)
r = |L - l| (khoảng cách còn lại)
l = v₀² · sin(2α₀ · π/180)/g (phạm vi bay)
g = 9,81 (gia tốc trọng trường)

Trong kịch bản trò chơi bên dưới, bạn có thể chơi nhiều trò chơi. Trong mỗi trò chơi, người đầu tiên đặt khoảng cách tới rổ, điền cho người thứ hai dữ liệu về tốc độ và góc ném ban đầu rồi báo cáo kết quả. Nếu dữ liệu vật lý là vô nghĩa - tốc độ âm hoặc bằng 0, hoặc góc âm hoặc quá lớn, thì người đầu tiên sẽ báo cáo “tốc độ lạ” hoặc “góc đáng kinh ngạc” và yêu cầu lại dữ liệu.

Kịch bản “Trò chơi bóng”

Dưới đây là thuật toán tiến hành hội thoại cho người chơi đầu tiên. Thuật toán này gồm 3 phần: phần thứ nhất đảm bảo dỡ mẻ, phần thứ hai tổ chức một đợt riêng biệt, phần thứ ba tổ chức các phép tính toán học.

Chiến lược của người chơi thứ hai có thể được xây dựng theo nhiều cách. Đơn giản nhất trong số đó là phương pháp “thử và sai”. Tuy nhiên, chiến lược thực sự là thực hiện các phép tính toán học dựa trên kiến ​​thức về các định luật vật lý cho phép một bài toán nhất định đạt được chiến thắng trong lần thử đầu tiên.

alg "ném bóng vào rổ"
bắt đầu trò chơi lint
những thứ L, D
báo cáo (“ném bóng vào rổ”)
D := ngẫu nhiên (0,1; 0,5)
đầu ra (đường kính giỏ =>; D)
trò chơi:=có
trò chơi cho đến nay:=có
không
L:=ngẫu nhiên (10; 250)
đầu ra("khoảng cách tới giỏ=>; L)
ném bóng vào rổ
yêu cầu (“chúng ta có nên chà đạp lần nữa không? [có/không]”, trò chơi)
kii
báo cáo (“cảm ơn vì đã chơi”)
lừa đảo

(Về phần kết, xem trang 48.)

⟦folio 48⟧

chúng ta nhận được đáp số: diện tích yêu cầu bằng $(7\sqrt{3}-\pi)/3$.

Tất nhiên, sáu bài toán đã cho còn lâu mới đầy đủ tất cả các loại bài toán trên mặt phẳng tọa độ đã được đưa ra (trong 10 năm qua) trong kỳ thi tuyển sinh tại MIPT. Chúng tôi đã cố gắng phân tích phần rõ ràng nhất - bài toán thành các tiếp tuyến của đồ thị hàm số - vì gần đây trong «Kvant» một bài báo lớn đã được xuất bản dành riêng cho những vấn đề như vậy (xem «Kvant», 1986, Số 3, trang 51). Để độc giả có cái nhìn đầy đủ hơn, mời các bạn tự mình giải quyết vấn đề sau:

1 (1984). Qua điểm $M$ (5; 6) vẽ một tiếp tuyến của parabol $y=6x^2/25$, cắt trục hoành tại điểm $N$ và trục tọa độ tại điểm $P$. Tìm bán kính của đường tròn nội tiếp tam giác $NOP$ ($O$ là gốc tọa độ).

2 (1979). Các tiếp tuyến được vẽ với parabol $y=\frac{1}{2}x^2+\frac{5}{2}$ tại hai điểm của nó, cắt nhau tại điểm $A$ và cắt trục x tại các điểm $B$ và $C$. Tam giác $ABC$ là tam giác đều và góc của nó $ABC$ bằng $2\pi/3$. Tìm diện tích của tam giác này.

3 (1978). Trên mặt phẳng tọa độ cho hai đường thẳng $y=-x$ và $y=5x-6$. Tìm: 1) các giá trị của $a$ và $b$ mà cả hai đường thẳng đã cho đều tiếp xúc với parabola $y=x^2+ax+b$; 2) tọa độ của các điểm tiếp xúc.

4 (1982). Tại các điểm vẽ các tiếp tuyến $A$ và $B$ parabol $y=x^2-3x+1$ thì hệ số góc của một trong các tiếp tuyến bằng 1.

Xây dựng thuật toán đối thoại

(Để bắt đầu, xem trang 40.)

Alg. "ném bóng vào rổ"
tháng tư trọng lượng $L, D$
bắt đầu thắp sáng
trọng lượng $v0, a0, l$
đánh:=không
Đã hiểu rồi:=không
người ăn xin
truy vấn("góc ném", $a0$)
yêu cầu("tốc độ ban đầu", $v0$)
sự lựa chọn
tại $v0\leqslant0$
đánh:=không
đầu ra ("tốc độ lạ")
tại $a0\leqslant0$ hoặc $a0\geqslant90$
đánh:=không
đầu ra (“góc lạ”)
inche

tính toán lượt truy cập
sự lựa chọn
khi nhấn:=có
kết luận (“làm tốt lắm, hiểu rồi”)
tại $l<L$
đầu ra ("undershoot", $r$, "mét")
tại $l>L$
đầu ra ("chuyến bay", $r$, "mét")
Tất cả
Tất cả
kts
lừa đảo
Alg. "tính toán cú đánh"
tháng tư trọng lượng $D, L, v0, a0$
cắt: thắp sáng
trọng lượng $r$
bắt đầu $g, l$
$g:=9,81$
$l:=(v0)^2\cdot\sin(2\cdot a0\cdot\pi/180)/g$
$r:=L-l$
nếu $r<D/2$
thì tôi hiểu rồi:=yes
trúng đích:=không
Tất cả
lừa đảo
