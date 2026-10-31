---
id: 1983-10-belkin-o-grafike-pryamolineynogo-ravnouskorennogo-dvizheniya-c4b77a30
issue: kvant_1983_10
year: 1983
number: "10"
title: Về đồ thị chuyển động thẳng đều có gia tốc
authors:
  - Белкин И. К.
rubric: shkola-v-kvante
page_first: 35
page_last: 36
page_labels: 33-34
tag: TSP4
lang: vi
source: kvant_digital
extraction: vision
content_sha256: a65c70af316e4c086716146282b6fdf57eeb9c395d2080882140f6f4f9328b68
prompt_sha256: draft-1
translated_from: content/ru/1983/10/articles/11_belkin-o-grafike-pryamolineynogo-ravnouskorennogo-dvizheniya-c4b77a30.md
source_content_sha256: 6046b82a6c2c4415072de5db5685b86403cf4ba95131bc58cb7f7ff3c43c3129
translation_model: draft
translation_run: vi-draft-2026-10-31
translation_quality: draft
---

⟦folio 33⟧

Như vậy,

$$\Delta s_1 = v_0 \Delta t,$$
$$\Delta s_2 = v_0 \Delta t + a (\Delta t)^2,$$
$$\Delta s_3 = v_0 \Delta t + 2a (\Delta t)^2,$$
$$\Delta s_4 = v_0 \Delta t + 3a (\Delta t)^2,$$
$$\Delta s_n = v_0 \Delta t + (n-1) a (\Delta t)^2,$$

trong đó $n$ là số khoảng mà chúng tôi chia thời gian chuyển động $t$. Vì các khoảng $\Delta t$ nhỏ, $n$ lớn, do đó, ở vế phải của đẳng thức cuối cùng, chúng ta có thể bỏ qua sự thống nhất so với $n$ và giả sử rằng

$$\Delta s_n = v_0 \Delta t + na (\Delta t)^2.$$

Tổng chuyển vị $s$ bằng tổng của tất cả các chuyển vị nhỏ $\Delta s_i$:

$$s = \Delta s_1 + \Delta s_2 + \Delta s_3 + \ldots + \Delta s_n,$$

hoặc

$$s = nv_0 \Delta t + a \Delta t^2 (1 + 2 + 3 + \ldots + n).$$

Tổng các số tự nhiên liên tiếp bằng số hạng cực trị thu được nhân với số của chúng:

$$1 + 2 + 3 + \ldots + n = \frac{1+n}{2} n.$$

Bỏ qua sự thống nhất so với $n$, ta có

$$1 + 2 + 3 + \ldots + n = \frac{n^2}{2}.$$

Từ đây

$$s = v_0 n \Delta t + \frac{a (n \Delta t)^2}{2}.$$

Nhưng $n \Delta t = t$ và $(n \Delta t)^2 = t^2$, rồi cuối cùng

$$s = v_0 t + \frac{at^2}{2}.$$

Về đồ thị chuyển động thẳng đều có gia tốc

Khi nghiên cứu chuyển động cơ học, ông sử dụng rộng rãi các biểu đồ thể hiện sự phụ thuộc tọa độ của vật thể vào thời gian (đồ thị chuyển động) và tốc độ của vật thể theo thời gian (đồ thị vận tốc). Các biểu đồ, giống như các công thức tương ứng, mô tả đầy đủ các chuyển động, nghĩa là chúng cho phép bạn xác định tọa độ và tốc độ bất cứ lúc nào. Nhưng đồ thị có ưu điểm là rõ ràng (bằng cách xây dựng đồ thị của hàm số, bạn có thể “nhìn thấy” hàm số đó).

Sách giáo khoa “Vật lý 8” cung cấp đồ thị chuyển động và vận tốc của chuyển động thẳng đều, cũng như đồ thị vận tốc của chuyển động thẳng đều có gia tốc. Sử dụng biểu đồ cuối cùng, người ta đã thu được công thức cho độ dịch chuyển $s$ và do đó cho tọa độ $x$ của một vật chuyển động với gia tốc đều:

$$s = v_0 t + \frac{at^2}{2}, \quad x = x_0 + v_0 t + \frac{at^2}{2}.$$

Tuy nhiên, những công thức này cũng có thể thu được bằng cách tính trực tiếp (ví dụ, xem chú thích “Chuyển động trong chuyển động thẳng đều có gia tốc”). Không có biểu đồ nào về chuyển động của trường hợp này được đưa ra, nhưng nó có vẻ rất đáng quan tâm. Đây là những gì chúng ta sẽ nói về trong bài viết này.

Như có thể thấy từ công thức cuối cùng, biểu thức tọa độ trong chuyển động có gia tốc đều là một tam thức bậc hai. Trong trường hợp tổng quát, các hệ số $t$ và $t^2$ và số hạng tự do không bằng 0. Đồ thị biểu diễn hàm số như vậy được gọi là parabol. Loại và vị trí của nó so với các trục tọa độ phụ thuộc vào ba hằng số - $x_0$, $v_0$ và $a$. Ví dụ, Hình 1 cho thấy một parabol tương ứng với phương trình

$$x = 3 + 12t + 3t^2.$$

Nó mô tả chuyển động thẳng đều có gia tốc đều với tốc độ ban đầu $v_0 = 12$ m/s và gia tốc $a = 6$ m/s². Nguồn gốc của thời gian là thời điểm khi tọa độ $x$ của vật thể (tọa độ ban đầu) bằng $x_0 = 3$ m. Nói đúng ra, đồ thị của chuyển động đó chỉ là phần bên phải của đường cong, được thể hiện trong Hình 1 dưới dạng một đường liền nét.

Nhưng nếu một vật chuyển động dọc theo cùng một đường thẳng và với cùng gia tốc và cho đến thời điểm thời gian được lấy làm gốc tọa độ thì đồ thị chuyển động của nó cũng sẽ là phần bên trái của đường cong (nó được biểu diễn trong Hình 1 bằng một đường đứt nét).

Một ví dụ khác, việc xem xét chuyển động được trình bày bởi

⟦folio 34⟧

Công thức

$$x = 2 + 20t - 5t^2.$$

Nó mô tả chuyển động của một vật, tại thời điểm ban đầu $t = 0$, khi tọa độ của nó bằng $x_0 = 2$ m, có tốc độ ban đầu là $v_0 = 20$ m/s và sau đó chuyển động với gia tốc không đổi $a = -10$ m/s². Chuyển động này rất gần với chuyển động của một vật được ném thẳng đứng lên trên (trục $X$ hướng vào đó) với vận tốc ban đầu là 20 m/s từ độ cao 2 m so với Trái đất. Để đơn giản, chúng ta giả sử gia tốc trọng trường không phải bằng 9,8 m/s² mà bằng 10 m/s². Đồ thị của chuyển động này được thể hiện trong Hình 2 với một đường liền nét màu đỏ.

Từ Hình 2, chúng ta thấy rất rõ ràng (rõ ràng hơn so với công thức tương ứng) cơ thể chuyển động như thế nào. Đầu tiên nó nổi lên, nhanh chóng di chuyển ra khỏi Trái đất. Sau 2 giây nó đạt độ cao tối đa là 22 m, sau đó nó bắt đầu chuyển động xuống (rơi). Chuyển động đi lên tương ứng với nhánh trái của parabol và chuyển động đi xuống tương ứng với nhánh phải. Nói chung, một parabol (có hai nhánh) luôn mô tả một chuyển động “qua lại”. Đường màu xanh lam trong Hình 2 biểu thị đồ thị của cùng một chuyển động gia tốc bằng nhau, nhưng có hướng gia tốc ngược lại.

Trong toán học người ta đã chứng minh rằng một parabol biểu diễn một tam thức bậc hai có dạng

$$x = x_0 + v_0 t + \frac{at^2}{2},$$

bằng cách dịch song song các trục tọa độ có thể biến đổi thành parabol biểu diễn công thức

$$x = \frac{a}{2} t^2.$$

Trong trường hợp của chúng ta, cần di chuyển trục $t$ dọc theo trục $X$ đến một khoảng bằng $x_0 - v_0^2/2a$ và trục $X$ di chuyển dọc theo trục $t$ đến một khoảng bằng $-v_0/a$. Trong Hình 1 và Hình 2, các trục giao nhau theo quy tắc này được thể hiện bằng các đường đứt nét.

Sự dịch chuyển trục này có nghĩa là thời điểm mà tốc độ của vật bằng 0 bây giờ được lấy làm gốc thời gian (khi chuyển động “qua lại” thì phải tồn tại một thời điểm như vậy) và điểm mà vật nằm ở thời điểm đó được chọn làm gốc tọa độ. Sau khi dịch các trục, parabol trở nên đối xứng với trục tương đối $X$. Các giá trị của tọa độ $x$ tại thời điểm $t$ và $-t$ hiện tại giống nhau, vì chỉ $t^2$ được đưa vào công thức và việc thay thế $t$ bằng $-t$ không thay đổi gì cả.

Sử dụng một parabol như vậy (trong các trục mới) có thể dễ dàng tìm được gia tốc. Rõ ràng tọa độ của điểm parabol tương ứng với thời điểm $t = 1$ bằng $a/2$, từ đó ta tìm được $a$. Gia tốc $a$ có thể được tìm thấy theo cách khác. Nếu chúng ta vẽ biểu đồ sự phụ thuộc của $x$ không phải vào $t$ mà vào $t^2$, thì từ công thức $x = at^2/2$ rõ ràng là
