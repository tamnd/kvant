---
id: 1983-3-boltyanskiy-metod-iteratsiy-1eff98af
issue: kvant_1983_3
year: 1983
number: "3"
title: Phương pháp lặp
authors:
  - Болтянский В. Г.
rubric: novosti-nauki
rubric_sub: Новости науки
page_first: 18
page_last: 23
page_labels: 16, 17, 21
tag: VS5M
lang: vi
source: kvant_digital
extraction: vision
content_sha256: 098a3dee7dad1cbfc9765c017e6b4d86481fd0e579437bfcdfdf99854f5cfbb4
prompt_sha256: draft-1
translated_from: content/ru/1983/03/articles/06_boltyanskiy-metod-iteratsiy-1eff98af.md
source_content_sha256: 5177e3d0cc65eba0f725c2be3c2556b4be50c21f6d2d4641f921f1555de70e1f
translation_model: draft
translation_run: vi-draft-2026-10-31
translation_quality: draft
---

⟦folio 16⟧

Phương thức tương tác

Thành viên tương ứng của Viện Hàn lâm Khoa học Sư phạm Liên Xô
V. G. BOLTYANSKY

I

Vài nghìn năm trước ở Babylon cổ đại, một phương pháp đơn giản đã được phát minh để tính gần đúng căn bậc hai.

Giả sử chúng ta muốn tính $\sqrt{a}$ (trong đó $a > 0$), tức là tìm nghiệm dương của phương trình $x^2 = a$.

Phương trình này tương đương với phương trình sau:

$$x = \frac{a}{x}.$$

(1)

Bây giờ chúng ta hãy giả sử rằng chúng ta có một số giá trị gần đúng $x_0$

số $\sqrt{a}$. Theo (1), $x_0$ phải được so sánh với số $\frac{a}{x_0}$: xét cho cùng, nếu $x_0$ và $\frac{a}{x_0}$ trùng nhau thì $x_0$ là giá trị chính xác của $\sqrt{a}$. Tuy nhiên, nếu $x_0 \neq \sqrt{a}$ thì một trong các số $x_0$, $\frac{a}{x_0}$ nhỏ hơn và các số khác lớn hơn $\sqrt{a}$ (vì tích của các số này là $a$), tức là $\sqrt{a}$ nằm giữa $x_0$ và $\frac{a}{x_0}$. Có thể gợi ý rằng giá trị trung bình số học của những con số này

$$x_1 = \frac{1}{2} \left( x_0 + \frac{a}{x_0} \right)$$

là số gần đúng tốt hơn của số $\sqrt{a}$ so với số gần đúng ban đầu $x_0$.

Phép tính gần đúng $x_1$ này có thể được cải thiện theo cách tương tự, đó là lấy trung bình số học của các số $x_1$ và $\frac{a}{x_1}$

$$x_2 = \frac{1}{2} \left( x_1 + \frac{a}{x_1} \right),$$

sau đó bạn có thể lấy xấp xỉ trung bình

$$x_3 = \frac{1}{2} \left( x_2 + \frac{a}{x_2} \right)$$

và vân vân.

Độ chính xác của phương pháp Vivilon là gì? Đối với đáp số, chúng tôi sẽ thực hiện các phép tính sau cho câu hỏi này:

$$x_n - \sqrt{a} = \frac{1}{2} \left( x_{n-1} + \frac{a}{x_{n-1}} \right) - \sqrt{a} =$$

⟦folio 17⟧

$$\frac{1}{2} \left( \sqrt{x_{n-1}} - \sqrt{\frac{a}{x_{n-1}}} \right)^2 = \frac{1}{2x_{n-1}} \left( x_{n-1} - a \right)^2. \quad (2)$$

Đẳng thức (2) giúp biểu diễn sai số của phép tính gần đúng $x_n$ (tức là số $|x_n - \sqrt{a}|$) theo sai số của phép tính gần đúng trước đó $x_{n-1}$.

Bài tập
1. Chứng minh rằng tất cả các xấp xỉ của số $\sqrt{a}$ tìm được bằng phương pháp Babylon, có lẽ ngoại trừ xấp xỉ ban đầu $x_0 > 0$, đều là các xấp xỉ có dư thừa.
2. Chứng minh rằng với mọi $x_0 > 0$ thì chuỗi xấp xỉ $(x_n)$ tìm được bằng phương pháp Babylon có xu hướng $\sqrt{a}$.
3. Chuỗi này sẽ có xu hướng tới giới hạn nào nếu một số âm nào đó được lấy là $x_0$?

Để ước tính tốc độ mà các số $x_0, x_1, x_2, \dots$ tiếp cận $\sqrt{a}$, chúng tôi tính toán $\sqrt{19}$ bằng cách lấy dự đoán ban đầu $x_0 = 4$. Được trang bị một máy tính vi mô$^*$), chúng tôi tìm thấy

$$x_0 = 4,0000000; \quad x_1 = 4,3750000; \quad x_2 = 4,3589285; \quad x_3 = 4,3588989; \quad x_4 = 4,3588989.$$

Như chúng ta có thể thấy, phép tính gần đúng thứ tư không khác biệt (trong các phép tính với bảy chữ số thập phân) so với phép tính gần đúng thứ ba. Chấp nhận điều đó là điều đương nhiên $\sqrt{19} \approx 4,3588989$.

Người đọc có thể lập luận rằng không cần phải “rào vườn”: có máy tính vi mô trong tay, người ta có thể quay số 19 và sau đó chỉ cần nhấn một nút $\sqrt{19}$, ngay lập tức nhận được kết quả tương tự $\sqrt{19} \approx 4,3588989$. Tuy nhiên, bạn sẽ đồng ý rằng chúng tôi không quan tâm nhiều đến ý nghĩa của $\sqrt{19}$ bằng giá trị của phương pháp Babylon. Chúng hóa ra khá quan trọng: sau lần lặp lại thứ ba của thao tác odotype (hoặc, như người ta nói, sau lần utepashi thứ ba), chúng tôi đã nhận được giá trị $\sqrt{19}$ với bảy dấu hiệu đúng (xem bài toán 4).

$^*$ Đối với những người không có máy tính vi mô trong tay, họ sẽ phải đếm bằng tay hoặc tin vào những gì được viết.

3 bài toán
4. Chúng ta hãy sử dụng phương pháp Babylon để tính các giá trị gần đúng liên tiếp $x_0 > 0, x_1, x_2, \dots$ của số $\sqrt{a}$ với $k$ chữ số thập phân, nghĩa là chúng ta làm tròn chữ số $(k+1)$ mỗi lần. Chứng minh rằng nếu phép tính gần đúng ổn định tại điểm $x_n$ (tức là $x_{n+1} = x_n$ trong phạm vi $10^{-k}$, nhưng $x_n \geq x_{n-1} + 10^{-k}$), thì sai số của phép tính gần đúng $\sqrt{a} \approx x_n$ nhỏ hơn 0,75 $\cdot 10^{-k}$.
5. Bạn cần phải làm bao nhiêu điều thú vị để thực hiện phép tính bằng phương pháp Babylon với $k$ chữ số thập phân, để có được số $\sqrt{a}$ với $k$ chữ số thập phân chính xác?

Để cho người đọc thấy sự vượt trội của trí thông minh của con người so với bất kỳ máy móc nào (đặc biệt là so với máy tính vi mô, thứ chỉ thực hiện ý muốn của con người, với sự trợ giúp của anh ta), chúng tôi sẽ thực hiện các phép tính với mười lăm chữ số thập phân. Với mục đích này, chúng tôi sử dụng giá trị gần đúng tìm được của số $\sqrt{19}$ cho giá trị gần đúng ban đầu mới $x_0$ (nghĩa là chúng tôi đặt $x_0 = 4,3588989$) và tính giá trị gần đúng tiếp theo $x_1 = \frac{1}{2} \left( x_0 + \frac{19}{x_0} \right)$ bằng phương pháp Babylon. Hãy đặt $\frac{19}{x_0} = x_0 + h$, nghĩa là

$$19 = (x_0)^2 + x_0 h. \quad (3)$$

chúng tôi có

$$(x_0)^2 = (4,3588989)^2 = (4,358 + 8,989 \cdot 10^{-4})^2 = 4,358^2 + 2 \cdot 4,358 \cdot 8,989 \cdot 10^{-4} + 8,989^2 \cdot 10^{-8}.$$

Vì máy vi tính của chúng tôi tính toán chính xác tích của hai số bốn nên chúng tôi cộng vế phải để tính chính xác. Bây giờ, khi đã ký tên dưới ba phân số thập phân thu được

$$18,992164 \quad 0,0078348124 \quad 0,00000080802121$$

chúng ta có thể (thủ công, điều này không hề khó khăn chút nào) tìm tổng của chúng.

$$(x_0)^2 = 19 - 37,957879 \cdot 10^{-8}$$

và do đó, thay vào (3), chúng ta có

$$4,3588989 h = 37,957879 \cdot 10^{-8},$$

từ đâu (sử dụng vi tính-

⟦folio 21⟧

xấp xỉ tăng dần - ở trạng thái này, một lý do khác là đối với lời giải máy tính bài toán thực tế bị giới hạn trong việc tìm các giá trị ở trạng thái ổn định bằng cách sử dụng máy tính thực hiện các phép tính với số lượng dấu đủ lớn. Thật khó để nói cái nào tốt hơn: dành thời gian máy tính tốn kém để kiểm tra độ chính xác của lời giải như một bài toán hoặc giải một số lượng lớn bài toán thực tế, đạt được độ chính xác tốt “như một quy luật” lời giải...

Bài toán và

14. Áp dụng phương pháp tích phân để điều khiển (6), trong đó $f(x)=0,9999x+0,0004$. Chứng minh rằng nếu quá trình tương tác lời giải, được thực hiện với bốn chữ số thập phân, dừng ở điểm $x_n$, thì sai số của phép gần đúng $x^* \approx x_n$ được áp dụng bằng một, nghĩa là không chỉ các chữ số thập phân không rõ ràng mà còn toàn bộ phần của phép tính gần đúng $x_n$. (Những thông báo này được sử dụng để xây dựng Ví dụ 1; trong ví dụ này $0,9999<f'(x)<1$ tại $x>0,12$.)

15. Đặt hàm $f$ thỏa mãn các điều kiện $f(a)>a$, $f(b)<b$ và $|f'(x)|<q<1$ cho $x \in [a; b]$. Khi đó phương trình (6) có nghiệm duy nhất $x^*$ trên khoảng $[a; b]$. Chứng minh rằng với phương trình lời giải (6) phương pháp tích phân

$$|x_{n+1}-x_n| \leq |x_1-x_0| \cdot q^n$$

$$|x^*-x_n| \leq |x_1-x_0| \cdot \frac{q^n}{1-q}.$$

16. Áp dụng các ước tính này cho hàm (5).

17. Giải phương pháp tích phân phương trình $0,6095+0,274 \sin x=x$ (sử dụng máy vi tính). Sau bao nhiêu lần lặp thì quá trình dừng lại? Phép tính gần đúng thu được có bao nhiêu dấu đúng?

18. Giải phương pháp tích phân của phương trình $\sqrt{1+x}=x$ bằng cách lấy $x_0=0$. So sánh kết quả thu được với nghiệm thu được bằng cách “đánh giá” lời giải của phương trình vô tỉ này. Chứng minh rằng phép tính gần đúng thứ $n$ có dạng

$$x_n = \sqrt{1 + \sqrt{1 + \ldots + \sqrt{1}}} \quad (n \text{ единиц}).$$

IV

Các bài toán 8, 10 và 15 chỉ ra các điều kiện để phương pháp tích phân được hoàn thiện và đạt được mục tiêu. Nếu những điều kiện này không được đáp ứng thì sao?

Chúng ta hãy xem xét phương trình $g(x)=0$, trong đó $g(a)<0$, $g(b)>0$, hàm $g$ có đạo hàm liên tục trên khoảng $[a; b]$ và $g'(x)>0$ tại $x \in [a; b]$. Do đó, hàm $g$ trả về khoảng $[a; b]$ và phương trình $g(x)=0$ có một nghiệm duy nhất $x^*$ trên khoảng này. Để làm được điều này, chúng ta có thể áp dụng phương pháp tích phân, ta biểu thị bằng $p_1$ và $p_2$ các số dương $p_1 \leq g'(x) \leq p_2$ trên đoạn $[a; b]$. Khi đó, nhịp độ bây giờ là phương trình $g(x)=0$ theo phương trình tương đương $x+a \cdot g(x)=x$, trong đó $a$ được chọn sao cho hàm

$$f(x)=x+a \cdot g(x)$$

thỏa mãn các điều kiện bài toán 15. (Kiểm tra xem điều này có đúng không, ví dụ: đối với $a=-\frac{2}{p_1+p_2}$, $q=\frac{p_2-p_1}{p_2+p_1}$.) Do đó, chúng tôi đã thay thế phương trình $g(x)=0$ bằng phương trình tương đương $f(x)=x$ mà phương pháp tích phân đã được áp dụng.

Nếu $g'(x)<0$ tại $x \in [a; b]$, kỹ thuật tương tự sẽ được áp dụng. (Trong trường hợp này, $p_1$ và $p_2$ là âm và $a=-\frac{2}{p_1+p_2} > 0$.)

Ví dụ 2. Giải phương trình tích phân

$$x^2-x=\cos x.$$

Đối với $0 \leq x \leq 1$ bên trái là không dương và bên phải là dương; do đó không có nghiệm nào trên đoạn $[0; 1]$. Viết lại phương trình dưới dạng

$$x^2-x-\cos x=0,$$

chúng ta lưu ý rằng hàm $g$, ở phía bên trái, có đạo hàm $g'(x)=2x-1+\sin x$, tại $x \geq 1$ là dương, nghĩa là $g$ trở về $[1; +\infty]$. Vì $g(1)<0$ và $g(2)>0$, trên tia $[1; +\infty]$ có chính xác một nghiệm của phương trình đang xét và nó nằm trên đoạn $[1, 2]$. Sử dụng máy tính vi mô trên đoạn $[1, 2; 1, 3]$. Hàm $g'$ trả về $[1; +\infty]$ (vì đạo hàm $g''(x)=2+cos x$ của nó là dương). Do đó, $p_1 \leq g'(x) \leq p_2$ trên đoạn $[1, 2; 1, 3]$, trong đó $p_1=g'(1,2) \approx 2,332$, $p_2=g'(1,3) \approx 2,564$. Vì vậy, $a=-\frac{2}{p_1+p_2} \approx -0,401$. Lấy $a=-0,4$ để đơn giản, ta được phương trình (Về phần kết, xem trang 37)
