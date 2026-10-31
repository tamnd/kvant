---
id: 1973-5-ryivkin-periodicheskie-funktsii-1eb5e13d
issue: kvant_1973_5
year: 1973
number: "5"
title: Hàm tuần hoàn
authors:
  - Рывкин А. А.
rubric: praktikum-abiturienta
rubric_sub: Практикум абитуриента
page_first: 40
page_last: 41
page_labels: 38-39
tag: 2AAY
lang: vi
source: kvant_digital
extraction: vision
content_sha256: d15c245edbfe4e80bf120c606b9077186db2e836ebe55f2b9a215a3532a1fe27
prompt_sha256: draft-1
translated_from: content/ru/1973/05/articles/08_ryivkin-periodicheskie-funktsii-1eb5e13d.md
source_content_sha256: adf87a46f9e8b5062c38c196cc97f30b1b911651c28a4cf80153e0ffca2b3285
translation_model: draft
translation_run: vi-draft-2026-10-31
translation_quality: draft
---

⟦folio 38⟧

Hàm tuần hoàn

định nghĩa

Tất cả các bạn rõ ràng đều biết hàm tuần hoàn là gì. Tuy nhiên, để nghiên cứu các tính chất của nó vẫn cần đưa ra định nghĩa chặt chẽ của nó. Hóa ra điều này không dễ thực hiện như vậy. Ví dụ, đây là một định nghĩa và một “hậu quả” từ nó.

Sự định nghĩa. Hàm $y = f(x)$ được gọi là tuần hoàn nếu có một số $T \neq 0$ sao cho tất cả các giá trị của $x$ từ miền của hàm này $f(x+T) = f(x)$.

Bây giờ chúng ta chứng minh Bổ đề 1:

Nếu $T > 0$ là chu kỳ của hàm $f(x)$ thì $-T$ có ​​thể là chu kỳ của hàm này.

Việc chứng minh bao gồm việc viết ra một chuỗi đẳng thức:

$$f(x-T) = f[(x-T)+T] = f(x).$$

Trên thực tế, $T$ là chu kỳ của hàm $f(x)$, và do đó, nếu nó được thêm vào đối số $x-T$ thì giá trị của hàm sẽ không thay đổi (đẳng thức đầu tiên). Tất cả những gì còn lại là mở ngoặc và nhận $f(x)$.

Trước khi đọc tiếp, hãy cố gắng tìm lỗi trong chứng minh này.

Tất cả các lý do được thực hiện ở đây là chính xác. Chỉ có điều họ không ngụ ý rằng $-T$ là khoảng thời gian của $f(x)$. Nếu bạn chưa phát hiện ra lỗi trong chứng minh, hãy xem xét hàm $\sin(\sqrt{x+2\pi})^2$. Miền của nó là $x \geq 0$ và đối với bất kỳ $x$ nào từ miền này

$$\sin(\sqrt{x+2\pi})^2 = \sin(\sqrt{x})^2,$$

nghĩa là, $2\pi$ theo quan điểm của định nghĩa được xây dựng là khoảng thời gian

chức năng. Đồng thời, $-2\pi$ sẽ không phải là chu kỳ của nó, vì hàm $x = 0$ bên trái $\sin(\sqrt{x})^2$ không được xác định và, ví dụ: $\sin(\sqrt{0-2\pi})^2$ không tồn tại.

Bây giờ lỗi của bằng chứng cũng đã rõ: trước khi xem xét giá trị $f(x-T)$, bạn cần chắc chắn rằng giá trị này tồn tại và trường hợp này không phải như vậy. Đây là lý do tại sao có thể xây dựng một ví dụ bác bỏ.

Để Bổ đề 1 được chứng minh, cần có một định nghĩa khác về hàm tuần hoàn.

Định nghĩa 1. Hàm $f(x)$ xác định ít nhất một điểm được gọi là tuần hoàn nếu có một số $T \neq 0$ (được gọi là dấu chấm) sao cho với bất kỳ $x$ nào từ miền định nghĩa của hàm này

a) các số $x-T$ và $x+T$ cũng thuộc miền định nghĩa của nó:

b) $f(x+T) = f(x)$.

Với định nghĩa này, chứng minh bổ đề 1 ở trên trở thành đúng.

Sử dụng định nghĩa của hàm tuần hoàn, bạn có thể xác định xem một hàm cụ thể có tuần hoàn hay không.

Ví dụ 1. Chứng minh hàm số $y = \sin lg x$ không tuần hoàn.

Thật dễ dàng để thiết lập thực tế này - chỉ cần lưu ý rằng hàm này được xác định cho tất cả $x > 0$ và không tồn tại cho tất cả $x \leq 0$. Do đó, bất cứ điều gì chúng ta chọn $T > 0$, hàm của chúng ta sẽ được xác định tại $x = T/2$ và sẽ không

⟦folio 39⟧

được xác định tại $x = \frac{T}{2} - T = -\frac{T}{2}$, nghĩa là nó không tuần hoàn.

Ví dụ 2. Chứng minh hàm số
$$\cos x + \sin (x \sqrt{2})$$
- không định kỳ.

Giả sử tồn tại một số $T \neq 0$ sao cho
$$\cos (x + T) + \sin [\sqrt{2} (x + T)] \equiv \cos x + \sin (\sqrt{2} x)$$
dành cho tất cả mọi người $x$. Chúng ta hãy đặt $x = 0$ và $x = -T$ trong đồng nhất thức này; thì ta thu được hai đẳng thức sau:
$$\begin{cases} \cos T + \sin (\sqrt{2} T) = 1 & (1) \\ \cos T - \sin (\sqrt{2} T) = 1. & (2) \end{cases}$$
Từ sự tương ứng của (1) và (2), suy ra $\cos T = 1$ và $\sin (\sqrt{2} T) = 0$, từ đó $T = 2\pi k$ và $T = \pi n/\sqrt{2}$. Đánh đồng các giá trị này ($T \neq 0$ và do đó $k \neq 0$, $n \neq 0$), chúng ta tìm thấy $\sqrt{2} = n/2k$, tức là $\sqrt{2} - \text{рациональное число}.$. Kết quả mâu thuẫn chứng tỏ hàm $\cos x + \sin (\sqrt{2} x)$ không tuần hoàn.

Ví dụ 3. Chứng minh hàm số $y = 3\sin x + \sin 2x$ tuần hoàn.

Rõ ràng là họ lý luận như thế này. Gọi $T$ là chu kỳ của hàm số này. Thế thì bình đẳng
$$3\sin (x + T) + \sin 2 (x + T) = 3\sin x + \sin 2x$$
phải thỏa mãn mọi $x$, bao gồm $x = 0$. Sử dụng phương pháp này, chúng ta đi đến phương trình cho $T$:
$$3\sin T + \sin 2T = 0,$$
(tức là, $(3 + 2\cos T) \sin T = 0$. Vì biểu thức trong ngoặc không tiến đến 0, nên $\sin T = 0$, $T = k\pi$.
Tuy nhiên, các giá trị $T$ được tìm thấy theo cách này hoàn toàn không nhằm mục đích là các chu kỳ của hàm số. Bằng cách chuyển từ thư từ (1) sang thư từ (2), chúng tôi đã nới lỏng các hạn chế đối với $T$ có trong (1). Xét cho cùng, sự tương ứng đầu tiên phải hợp lệ với tất cả $x$, trong khi sự tương ứng thứ hai chỉ đảm bảo tính hợp lệ của nó đối với $x = 0$. Do đó, chúng ta đã chứng minh rằng tất cả các chu kỳ của hàm đang được xem xét đều nằm trong số các số có dạng $x = k\pi$. Tuy nhiên, điều này không có nghĩa là tất cả các số thuộc loại này đều là dấu chấm của nó.

Tiếp theo, vì
$$3\sin \frac{\pi}{2} + \sin \left(2 \cdot \frac{\pi}{2}\right) = 3,$$
$$3\sin \left(\frac{\pi}{2} + \pi\right) + \sin 2 \left(\frac{\pi}{2} + \pi\right) = -3,$$
nghĩa là $f\left(\frac{\pi}{2}\right) \neq f\left(\frac{\pi}{2} + \pi\right)$, thì n sẽ không phải là một khoảng thời gian của hàm số. Số $2\pi$ và tất cả các số có dạng $2k\pi$ là dấu chấm của nó, dễ dàng xác minh bằng cách xác minh trực tiếp.

Kỳ chính

Định nghĩa 2. Chu kỳ dương nhỏ nhất của hàm tuần hoàn $f(x)$ được gọi là chu kỳ cơ bản.

Một số độc giả chú ý hơn có thể sẽ phản đối ngay lập tức: trước khi đặt tên cho một thứ gì đó, tốt nhất là bạn nên chắc chắn về sự tồn tại của một đối tượng nhất định. Chúng ta sẽ khảo sát sự tồn tại của chu kỳ chính sau khi chúng ta đã chứng minh được tính chất Snow của hàm tuần hoàn.

Bổ đề 2. Nếu $T_1$ và $T_2$ là chu kỳ của hàm $f(x)$ và $T_1 + T_2 \neq 0$, thì $T_1 + T_2$ là chu kỳ của $f(x)$.

Bằng chứng. Hãy để $y = x + T_1$. Vì $T_1$ là chu kỳ của hàm $f$, mo $f(y)$ tồn tại đồng thời với $f(x)$. $T_2$ cũng là khoảng thời gian $f$. Do đó, $f(y + T_2)$ tồn tại và $f(y + T_2) = f(y) = f(x + T_1) = f(x)$, tức là $f(x + T_1 + T_2) = f(x)$.

Theo các điều kiện, $T_1 + T_2 \neq 0$. Vì thế
