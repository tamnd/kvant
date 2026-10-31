---
id: 1988-8-chukova-raspredelenie-puassona-a0a70b83
issue: kvant_1988_8
year: 1988
number: "8"
title: Phân bố Poisson
authors:
  - Чукова Ю. П.
rubric: raznoe
page_first: 17
page_last: 19
page_labels: 15-17
tag: UNBE
lang: vi
source: kvant_digital
extraction: vision
content_sha256: a36229f590355c6421fbde3cb55836c6ee3326494bcd64fe1e19ef56bbeb279d
prompt_sha256: draft-1
translated_from: content/ru/1988/08/articles/03_chukova-raspredelenie-puassona-a0a70b83.md
source_content_sha256: 0766eced676fac303cdf37f47b4b3590f3c09933de5c6dbdf47aec5ba4d16500
translation_model: draft
translation_run: vi-draft-2026-10-31
translation_quality: draft
---

⟦folio 15⟧

PHÂN PHỐI ĐỘC

Ứng viên Khoa học Vật lý và Toán học
Y. P. CHUKOVA

1837 Paris. Bởi Budvaar Saint
Michel là giáo sư ở Sorbonne,
thành viên của tất cả các hiệp hội khoa học và học giả
của Châu Âu và Châu Mỹ Simeon Denis
Poisson. Anh ấy đang nghĩ về lần cuối cùng của mình
công việc. Tôi có nên báo cáo cô ấy không?
người theo đạo Korist? hoặc giới hạn chúng ta vào các nhà toán học? Công trình có tên “Nghiên cứu
thảo luận về khả năng bị kết án hình sự
các quy trình mới và dân sự."
Tài liệu đó hợp pháp và đúng luật
toán học... Định luật mô tả
vai trò của cơ hội trong kiện tụng
quá trình ở Pháp vào thế kỷ 19.

Poisson đã biết đến sự khái quát hóa tuyệt vời
sức mạnh của các định luật toán học.
Nhưng ngay cả anh cũng không ngờ rằng mình đã nhận được
luật được trao cho họ, luật này sẽ được gọi là ra-
Giới hạn Poisson, sau một rưỡi
thế kỷ sẽ trở thành một công cụ nghiên cứu cho
các nhà khoa học thuộc nhiều chuyên ngành khác nhau
sta.

Chúng ta sẽ làm quen với việc phân phối
Poisson một cách đơn giản và dễ hiểu
ví dụ.

Trong phòng ăn, họ làm hỗn hợp gồm $N$ quả anh đào và rót vào ly $n$
(khuấy kỹ để đảm bảo độ tinh khiết của thí nghiệm). Câu hỏi: xác suất là gì
Có đúng là không có quả anh đào trong ly này không?

Chúng ta sẽ giả định rằng tất cả các lựa chọn
phân phối quả anh đào vào ly
quyền bình đẳng. Vì mỗi
$N$ quả anh đào có thể trúng bất kỳ $n$ nào
kính, tổng số lựa chọn bằng
nhưng $n^N$ (n tùy chọn cho quả anh đào thứ nhất,
n - cho lần thứ 2, v.v.). Số lượng tùy chọn
khi không có quả anh đào nào trong một chiếc ly nhất định
palia, bằng $(n-1)^N$ (mỗi quả anh đào
“chọn” bất kỳ cái nào khác $n-1$
kính). Do đó, xác suất yêu cầu
xác suất $R_0$ của những gì sẽ không có trong ly
quả anh đào, bằng $(n-1)^N/n^N$, tức là

chất độc

⟦folio 16⟧

Chúng ta cũng có thể rút ra một công thức chung cho xác suất giới hạn (nói chung là $N$) $P_k$ của việc tìm thấy $k$ chấy ($k=0, 1, 2, \dots$) trong ly:

$$P_k \approx \frac{\lambda^k e^{-\lambda}}{k!},$$

trong đó $k! = 1 \cdot 2 \cdot \dots \cdot k$ tại $k \geqslant 1$ và theo định nghĩa, $0! = 1$.

Nói chung, giả sử rằng trong một thử nghiệm với các kết quả ngẫu nhiên, một số thay đổi về số lượng nhận các giá trị nguyên không âm. Nó được cho là có phân phối Poisson nếu nó nhận giá trị $k$ với xác suất $p(k; \lambda) = \lambda^k e^{-\lambda}/k!$ (xem (2)). hình 1 hiển thị biểu đồ xác suất $p(0; \lambda), p(2; \lambda)$ và $p(4; \lambda)$ dưới dạng hàm của $\lambda$. Khi $\lambda$ được cố định, các giá trị của $p(k; \lambda)$ được mô tả là hình 2 (đối với $\lambda=10$).

Phân phối Poisson xảy ra trong nhiều tình huống khác nhau. Chúng tôi sẽ chỉ đưa ra hai ví dụ điển hình về việc sử dụng nó. Đầu tiên là từ vật lý. Các thí nghiệm cho thấy trong quá trình phân bố vật chất, số lượng hạt $\alpha$ phát ra trong một khoảng thời gian nhất định $t$ với độ chính xác rất cao tuân theo phân bố Poisson với giá trị trung bình $\lambda t$, trong đó $\lambda$ là thông số đặc trưng cho cường độ bức xạ. Ví dụ này cho phép chúng ta chứng minh mức độ nguy hiểm của việc ngụy trang lẽ thường. Thật vậy, thoạt nhìn có vẻ như xác suất được tạo ra

$$P_0 = \left(1 - \frac{1}{n}\right)^N.$$

Gọi $\lambda = \frac{N}{n}$ là số chấy trung bình trong ly, khi đó

$$P_0 = \left(1 - \frac{\lambda}{N}\right)^N.$$

Đối với $N$ lớn (và cố định $\lambda$), giá trị này xấp xỉ bằng $e^{-\lambda}$. Vì thế,

$$P_0 \approx e^{-\lambda}.$$

(1)

Tương tự, chúng ta có thể tính xác suất $P_1$ để có chính xác một quả anh đào trong ly: quả anh đào này có thể được chọn theo $N$ cách và $N-1$ quả anh đào còn lại phải được phân bổ cho $n-1$ ly, do đó,

$$P_1 = \frac{N(n-1)^{N-1}}{n^N} = \frac{N}{n-1} \left(1 - \frac{\lambda}{N}\right)^N \approx \lambda e^{-\lambda}.$$

*) Thực vậy,

$$\lim_{N \to \infty} \left(1 - \frac{\lambda}{N}\right)^N = e^{\lim_{N \to \infty} N \ln(1-\lambda/N)},$$

và giới hạn trong chỉ báo bằng

$$\lim_{N \to \infty} N \ln \left(1 - \frac{\lambda}{N}\right) = \lim_{N \to \infty} \lambda \frac{\ln(1-\lambda/N) - \ln 1}{\lambda/N} = -\lambda \lim_{h \to 0} \frac{\ln(1+h) - \ln 1}{h} = -\lambda,$$

vì giới hạn cuối cùng bằng hàm tùy ý $\ln x$ cho $x=1$, tức là 1.

⟦folio 17⟧

10 hạt α trong 5 giây hoặc 2 hạt α trong 1 giây phải trùng nhau. Tuy nhiên, điều này không đúng. Ví dụ, giả sử rằng bộ đếm đăng ký một hạt có tần số trung bình λ=1 hạt mỗi giây. Khi đó, số hạt được ghi trong 1 giây tuân theo phân phối Poisson với tham số 1 và trong 5 giây - với tham số 5. ​​Do đó, xác suất đầu tiên bằng

$$p(10; 5) = \frac{5^{10}e^{-5}}{10!} \approx 0,018,$$

và thứ hai -

$$p(2; 1) = \frac{1^2 \cdot e^{-1}}{2!} \approx 0,18.$$

Chúng ta thấy rằng những xác suất này không những không bằng nhau mà còn khác nhau gấp 10 lần!

Ví dụ thứ hai là từ cuộc sống của virus, chính xác hơn là virus vi khuẩn được gọi là thể thực khuẩn, được phát hiện vào năm 1915. Thể thực khuẩn là ký sinh trùng của vi khuẩn. Chúng chỉ được giải phóng trong tế bào vi khuẩn. Một trong những thể thực khuẩn được nghiên cứu nhiều nhất, thể thực khuẩn T2, được giải phóng khỏi Escherichia coli. Quá trình lây nhiễm xảy ra như sau. Trong quá trình chuyển động Brown, thể thực khuẩn gặp một vi khuẩn và bám vào nó ở cuối “đuôi” của nó (hình 3). Sau khi bám vào, vỏ virus co lại, lõi xuyên qua bề mặt tế bào và DNA của phage xâm nhập vào vi khuẩn. Sau khoảng 20 phút ở nhiệt độ 37°, vi khuẩn bị tiêu diệt và hầu hết các thể thực khuẩn xuất hiện cùng với một thể thực khuẩn. Cấp độ hiếm!

Cái chết của vi khuẩn dưới tác động của phage có thể được quan sát gần như trực quan. Thực tế là dung dịch dinh dưỡng có vi khuẩn *E. coli* xuất hiện nhiều mây - vi khuẩn có kích thước khoảng 1 micron, đủ để phân tán ánh sáng khả kiến. Nhưng nếu trong ống nghiệm có *E. coli* thêm một thể thực khuẩn T2 và nhấn trong 6-8 giờ, khi đó dung dịch trong ống nghiệm sẽ trở nên đục. Lời giải thích duy nhất. Phage T2, nhân lên nhanh chóng, tiêu diệt toàn bộ *E. coli*, và không còn vật thể nào trong ống nghiệm có thể tán xạ ánh sáng, vì kích thước của bản thân các phage (khoảng 200 nm) là quá nhỏ để thực hiện điều này. Tất cả điều này thật thú vị, nhưng bạn có quyền hỏi phân phối Poisson có liên quan gì đến nó.

Hóa ra, theo một cách không ngờ tới, nó lại giúp giải quyết một vấn đề quan trọng của sinh học phân tử. bài toán - xác định nồng độ các hạt virus trong dung dịch. Trong ví dụ của chúng tôi với compote, phân tích bài toán (tìm số quả anh đào trung bình trong một ly) có thể được giải một cách đơn giản: bạn có thể đọc lại số quả anh đào trong nhiều ly và chia số lượng của chúng cho số ly. Nhưng virus không được đọc lại như sâu bọ! Và ở đây chúng ta nhớ đến công thức (1), công thức này kết nối xác suất không có hạt (chấy hay vi rút) trong một thể tích nhất định của chế phẩm chứa chúng (trong ly hoặc trong ống nghiệm) với số lượng trung bình của chúng. Giả sử, hãy lấy 100 ống nghiệm chứa vi khuẩn trong môi trường dinh dưỡng và thêm 1 ml dung dịch vi rút vào mỗi ống nghiệm. Sau một thời gian ủ, chúng tôi đếm số lượng ống nghiệm vẫn còn đục. Giả sử có 38 chiếc ly và 62 chiếc ly còn lại trong suốt. Điều này có nghĩa là không một thể thực khuẩn nào lọt vào 38 ống nghiệm, hoặc các thể thực khuẩn được rã đông nhanh hơn nhiều so với vi khuẩn (trong thời gian trôi qua, chúng đã tiêu diệt tất cả vi khuẩn trong 62 ống nghiệm). Tỷ lệ các ống đục cho giá trị xác suất gần đúng bằng
