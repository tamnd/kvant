---
id: 1976-4-ionin-o-reshenii-uravneniy-bez-nahozhdeniya-odz-9d39a59e
issue: kvant_1976_4
year: 1976
number: "4"
title: '[Giới thiệu về phương trình lời giải mà không tìm thấy ODZ]'
authors:
  - Ионин Ю. И.
rubric: raznoe
page_first: 45
page_last: 47
page_labels: 43-45
tag: I9EL
lang: vi
source: kvant_digital
extraction: vision
content_sha256: ffb6a337431584afb5b7a13a8eccb3e9a06f49795579a168eb52f77ac1ec9464
prompt_sha256: draft-1
translated_from: content/ru/1976/04/articles/10_ionin-o-reshenii-uravneniy-bez-nahozhdeniya-odz-9d39a59e.md
source_content_sha256: ff51f101df16896894c7546edbd5927e495a4cc5c8bc6e0201b4b6a364a72001
translation_model: draft
translation_run: vi-draft-2026-10-31
translation_quality: draft
---

⟦folio 43⟧

4. Giải phương trình
$$\frac{x^4 + 4}{x^2 - 2} - 5x = 0.$$
Đôi khi, ngay cả một hình học đơn giản bài toán cũng có thể dẫn đến nghiên cứu độc lập nếu người ta cố gắng tìm ra tính cần thiết của một đề xuất cụ thể, thay đổi các điều kiện bài toán và xem xét các cấu hình tổng quát hơn. U. Alla (Võru, Liên Xô Estonia) mời độc giả của tạp chí thực hiện một nghiên cứu như vậy, bắt đầu từ bài toán sau đây.

5. Hình thang $ABCD$ chứa các đường chéo cắt nhau tại điểm $O$. Chứng minh rằng diện tích của các tứ giác thu được có liên hệ với nhau bởi hệ thức
$$S_{\Delta AOB} \cdot S_{\Delta COD} = S_{\Delta BOC} \cdot S_{\Delta DOA}.$$
Cố gắng thiết lập các mối quan hệ chung cho nhiều mệnh đề tổng quát hơn.

6. Để các đường chéo $A_1A_3$ và $A_2A_4$ của tứ giác lồi $A_1A_2A_3A_4$ cắt nhau tại điểm $O$. Chúng ta hãy biểu thị diện tích của tứ giác $A_1OA_2, A_2OA_3, A_3OA_4, A_4OA_1$ lần lượt bằng $S_1, S_2, S_3, S_4$. Có đúng là $S_1S_3 = S_2S_4$ không?

7. Tỷ lệ này có còn hiệu lực không?
a) Đối với tứ giác không lồi, không tự cắt nhau;
b) cho một tứ giác tự cắt nhau?

8. Tổng quát hóa hệ thức này cho trường hợp điểm $O$ là điểm trong tùy ý của một tứ giác lồi.

9. Mối quan hệ thu được ở bài toán trước có hợp lệ không nếu điểm $O$ nằm ngoài tứ giác lồi?

10. Khái quát hóa mối quan hệ này cho trường hợp lồi $2n$-giác ($n \geq 2$) và một điểm tùy ý $O$ trong mặt phẳng của nó.

* *

Nhiều người đăng ký bắt đầu lời giải phương trình hoặc bất đẳng thức bằng việc tìm phạm vi giá trị chấp nhận được (ADV), tức là một tập hợp các số xác định đồng thời vế trái và phải của phương trình hoặc bất đẳng thức này. Tuy nhiên, cần lưu ý rằng việc tìm ODZ không nhất thiết phải thực hiện trong mọi trường hợp.

Ví dụ: nếu quy trình lời giải sử dụng các phép biến đổi tương đương thì việc tìm kiếm ODZ là một sự lãng phí thời gian.

Ví dụ 3 (MINCH và GP, 1974). Giải bất đẳng thức
$$\log_2 \log_3 \frac{x+2}{x-2} < \log_{1/2} \log_{1/3} \frac{x-2}{x+2}.$$ (4)

Việc tìm ODZ ở đây đòi hỏi hệ bất đẳng thức lời giải

$$\begin{cases} x \neq 2, \\ \frac{x+2}{x-2} > 0, \\ \log_3 \frac{x+2}{x-2} > 0, \\ x \neq -2, \\ \frac{x-2}{x+2} > 0, \\ \log_{1/3} \frac{x-2}{x+2} > 0, \end{cases}$$

đó là một nhiệm vụ khá khó khăn. Trong khi đó, không cần tìm ODZ, vì từ bất đẳng thức (4) ta có thể suy ra các bất đẳng thức tương đương:

$$\log_2 \log_3 \frac{x+2}{x-2} < -\log_2 \log_3 \frac{x+2}{x-2};$$

$$\log_2 \log_3 \frac{x+2}{x-2} < 0;$$

$$0 < \log_3 \frac{x+2}{x-2} < 1;$$

$$1 < \frac{x+2}{x-2} < 3,$$

$$1 < 1 + \frac{4}{x-2} < 3,$$

$$0 < \frac{2}{x-2} < 1,$$

$$\frac{x-2}{x+2} > 1,$$

từ đâu chúng tôi nhận được lời giải: $x > 4$.

Thông thường, việc tìm ODZ hóa ra là không cần thiết đối với các phương trình vô tỉ lời giải. Vì vậy, bình phương cả hai vế của phương trình
$$\sqrt{f(x)} = g(x),$$ (5)

chúng ta đi đến phương trình
$$f(x) = |g(x)|^2,$$ (6)

⟦folio 44⟧

hệ quả của nó là bất đẳng thức $f(x) \geq 0$. Do đó, nghiệm của phương trình (6) luôn được đưa vào ODZ của phương trình (5).

Ví dụ 4 (MSU, nhà vật lý, 1968). Với mỗi giá trị của tham số a, hãy tìm tất cả các phương trình lời giải

$$\sqrt{a(2^x - 2) + 1} = 1 - 2^x.$$

Ở đây, việc tìm ODZ sẽ yêu cầu các bất đẳng thức lời giải với tham số $a(2^x - 2) + 1 \geq 0$, nhưng nếu không có điều này thì các bất đẳng thức thông thường có thể được đáp ứng. Sử dụng $t = 2^x$, chúng ta viết lại phương trình này dưới dạng

$$\sqrt{at - 2a + 1} = 1 - t.$$ (7)

Sau khi bình phương cả hai phần đồng hồ của phương trình (7) chúng ta nhận được

$$at - 2a + 1 = (1 - t)^2,$$ (8)

từ đâu $t_1 = a, t_2 = 2$. Đối với các nghiệm đã tìm được, không cần kiểm tra tính đúng đắn của bất đẳng thức $at - 2a + 1 \geq 0$ - đó là hệ quả của phương trình (8). Chỉ cần kiểm tra việc đáp ứng điều kiện $1 - t \geq 0$, đảm bảo tính tương đương của phương trình (7) và (8), và điều kiện $t > 0$, theo phương trình $t = 2^x$; cả hai điều kiện này đều có thể được xác minh mà không gặp khó khăn gì.

Đáp số: cho $a \leq 0$ và cho $a > 1$ lời giải không có; đối với $0 < a \leq 1$ có một lời giải $x = \log_2 a$ duy nhất.

Thông thường, tại lời giải, các phương trình và bất đẳng thức của ODZ có thể được tìm thấy “không hoàn toàn”, áp đặt các hạn chế cần thiết không trực tiếp lên ẩn số, mà đối với một số biểu thức từ ẩn số.

Ví dụ 5 (LSU, Math., 1966). Giải phương trình

$$tg \frac{2\pi x}{1 + x + x^2} = \sqrt{3}.$$

Người nộp đơn 《Gương mẫu》, bắt đầu bằng việc tìm ODZ, sẽ phải đối mặt với nhu cầu giải một tập hợp các phương trình

$$\frac{2\pi x}{1 + x + x^2} = \frac{\pi}{2} + k\pi$$

($k = 0, \pm 1, \pm 2, \dots$) để xác định các giá trị “bị cấm” của ẩn số. Trong khi đó, chỉ cần biết DZ mô tả bằng thuật ngữ gì là đủ

$$\frac{2\pi x}{1 + x + x^2} \neq \frac{\pi}{2} + k\pi$$ (9)

($k = 0, \pm 1, \pm 2, \dots$). Thật ra phương trình ban đầu có mối quan hệ không thể tách rời với tập phương trình

$$\frac{2\pi x}{1 + x + x^2} = \frac{\pi}{3} + n\pi$$

($n = 0, \pm 1, \pm 2, \dots$), có nghiệm tất nhiên thỏa mãn điều kiện (9).

Sử dụng các ví dụ trên, bạn có thể tin chắc rằng việc tính toán thực tế thuộc tính ODZ không phải là yếu tố bắt buộc lời giải của phương trình và các bất đẳng thức - phép tính sau đây cũng chỉ nên được thực hiện khi điều này thực sự cần thiết.

Ở bên phải

11 (MSU, VMK, 1973). Giải bất đẳng thức

$$\log \frac{x^2 - 10x + 31}{30} \left(5x - \frac{11}{20}\right) \leq 0.$$ (12)

12 (MSU, Khoa Cơ học, 1974). Giải phương trình $\sqrt{2\sin 2x} + 2\sin x = 0.$

13 (MSU, Khoa Kinh tế, 1974). Tìm tất cả các phương trình lời giải

$$\log_{\cos 2x - \sin 2x} (1 - \cos x - \sin x) = 1.$$ (Yu. Ionin (Leningrad))

* *

P. Gorshitey (Kyiv) đã đưa ra một đề xuất thú vị trong thư của mình: đăng các kỳ thi cạnh tranh đẹp, ngắn và “không chuẩn” lời giải bài toán trên các trang của tạp chí. Trên thực tế, chẳng hạn, trong các bài toán hình học, người nộp đơn thường đạt được kết quả sau khi kiểm tra các phép tính dài và rườm rà. Tuy nhiên, đôi khi lời giải của cùng một bài toán có thể rút gọn thành một vài dòng theo đúng nghĩa đen nếu bạn tìm thấy “niềm say mê” - một thỏa thuận áp dụng một định lý hình học nhất định hoặc thực hiện một công trình xây dựng bổ sung thành công.

Tác giả của bức thư đưa ra một số ví dụ về bài toán như vậy, được lấy từ

⟦folio 45⟧

Các lựa chọn cho kỳ thi tuyển sinh tại Đại học quốc gia Moscow. Chúng có thể được giải mà không cần “trí tưởng tượng hình học”, mặc dù sau đó một con đường khá quanh co với những phép tính phức tạp sẽ dẫn đến mục tiêu (xem B. I. Aleksadrov và M. V. Lurie, “Sổ tay toán học dành cho những người vào Đại học quốc gia Moscow,” Nhà xuất bản Đại học quốc gia Moscow, 1974). Chúng tôi mời độc giả của tạp chí thử tìm hình học ngắn lời giải của bài toán sau đây.

14 (MSU, khoa vật lý, 1972). Trong tam giác ABC, góc B bằng π/4, góc C bằng π/3. Đường tròn dựng trên các đường trung tuyến BM và CN là đường kính, cắt nhau tại các điểm P và Q. Dây cung PQ cắt đường trung bình MN tại điểm F. Tìm tỉ số giữa độ dài đoạn NF và chiều dài đoạn FM.

15 (MSU, khoa vật lý, 1973). Các mặt bên của tam giác SABC có đỉnh S tạo thành các góc bằng mặt phẳng đáy ABC của paramda; SO là chiều cao của paramda. Được biết, $\angle ASB = 7\pi/12$, $\angle BSC = \pi/2$, $\angle SCA = \pi/3$. Tìm tỉ số diện tích của tam giác AOB và diện tích của tam giác ABC.

16 (MSU, Khoa Địa lý, 1971). Cho tam giác ABC có các cạnh AB = 3, BC = 4, AC = 5 vẽ đường bissertis BD. Các tam giác ABD và BCD có các đường tròn nội tiếp tiếp xúc với đoạn BD lần lượt tại các điểm M và N. Tính độ dài đoạn MN.

* *

Còn có một số bức thư nữa trong thư xã luận mà độc giả của tạp chí gợi ý lời giải cụ thể bài toán đơn giản và sâu sắc.

Ví dụ 6 (MIPT, 1970). Một hành khách tàu điện ngầm đi xuống thang cuốn đang chuyển động trong 24 giây. Nếu một hành khách đi cùng tốc độ nhưng trên thang cuốn đứng yên thì anh ta có thể đi xuống trong 42 giây. Anh ta đứng trên bậc thang cuốn đang chuyển động thì mất bao nhiêu giây để đi xuống?

Nếu chúng ta biểu thị chiều dài của thang cuốn bằng l và tốc độ của thang cuốn và hành khách bằng v₁ và v₂, thì không khó để tạo ra một hệ gồm hai phương trình chưa biết, từ đó xác định được tỷ lệ ban đầu l/v₁ (xem «Kvant», 1971, số 5, trang 46-47).

Học sinh lớp 7 D. Feofanov (Alma-Ata) gợi ý số học lời giải bài toán. Khi hành khách và thang cuốn chuyển động đồng thời thì hành khách đi xuống 1/24 chiều dài thang cuốn trong 1 giây. Nhưng trong 1 giây hành khách tự mình đi xuống thang cuốn đang đứng yên bằng 1/42 chiều dài của nó. Do đó, khối thạch của thang cuốn di chuyển $\frac{1}{24} - \frac{1}{42} = \frac{1}{56}$ một phần chiều dài của thang cuốn trong 1 giây và sau đó bán hết chiều dài của nó trong 56 giây.

* *

Trong bài kiểm tra các khóa học truyền hình dành cho ứng viên đại học, bài toán sau đây đã được đặt (xem «Kvant», 1973, Số 1, trang 55; Số 2, trang 80).

Ví dụ 7. Tìm sin 2α nếu biết rằng

$$3 \mathrm{tg}^2 \alpha - 10 \mathrm{tg} \alpha + 3 = 0$$

và uol α thỏa mãn bất đẳng thức

$$\frac{5}{4} \pi < \alpha < \frac{3}{2} \pi.$$

Một lời giải gây tò mò trong số bài toán này đã được một sinh viên Đại học Sư phạm Bang T. Antipova (Moscow) thêm vào tòa soạn. Ta viết lại đẳng thức đã cho ở điều kiện dưới dạng

$$10 \mathrm{tg} \alpha = 3 (\mathrm{tg}^2 \alpha + 1).$$

Vì $\mathrm{tg}^2 \alpha + 1 \neq 0$, từ đây chúng ta nhận được rằng

$$\frac{2 \mathrm{tg} \alpha}{1 + \mathrm{tg}^2 \alpha} = \frac{3}{5}.$$

Nếu chúng ta nhớ lại biểu thức của sin thông qua tiếp tuyến của đối số đã cho

$$\sin x = \frac{2 \mathrm{tg} \frac{x}{2}}{1 + \mathrm{tg}^2 \frac{x}{2}},$$

thì ta tìm ngay: sin 2α = $\frac{3}{5}$. Lưu ý rằng điều kiện 5π/4 < α < 3π/2 hóa ra là không cần thiết.

Bài đánh giá do N. Rozov và V. Stepanov chuẩn bị
