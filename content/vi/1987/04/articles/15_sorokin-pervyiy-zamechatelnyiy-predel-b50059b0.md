---
id: 1987-4-sorokin-pervyiy-zamechatelnyiy-predel-b50059b0
issue: kvant_1987_4
year: 1987
number: "4"
title: Giới hạn tuyệt vời đầu tiên
authors:
  - Сорокин Г. А.
rubric: shkola-v-kvante
page_first: 42
page_last: 42
page_labels: "40"
tag: 58DG
lang: vi
source: kvant_digital
extraction: vision
content_sha256: cc19d079dfe4405dc6f04b11100f9da494b88fed9c1dd1d4afeed4c2e2cdc340
prompt_sha256: draft-1
translated_from: content/ru/1987/04/articles/15_sorokin-pervyiy-zamechatelnyiy-predel-b50059b0.md
source_content_sha256: 6f801eea87eef9f6e371820e3144486de0628b10acc6148a7672ce6941968341
translation_model: draft
translation_run: vi-draft-2026-10-31
translation_quality: draft
---

⟦folio 40⟧

không; ví dụ: 11 934:51=234 (chứng minh đi!).

Để có được dấu chia hết cho $m=10n-1$, bạn cần thay phép trừ bằng phép cộng trong B, viết $m$ thay vì 0 trong D và D và viết 10$n-1$ thay vì 10$n+1$.

Ví dụ

$$N = 9246, m = 69$$

(ở đây thao tác B là thao tác sửa đổi C).

Điều này có nghĩa là 9246 chia hết cho 69. Hãy tìm cách đọc thương số 9246:69 trong dòng này.

Cuối cùng, chúng ta hãy lưu ý rằng nếu chúng ta viết các số trong hệ thống số kép, thì bất kỳ quy tắc nào của chúng ta đều cho dấu hiệu chia hết cho bất kỳ số lẻ nào (dấu chia hết cho 2 trong hệ thống số kép là hiển nhiên).

V. G. Stolyar

Giới hạn tuyệt vời đầu tiên

Trong sách giáo khoa “Đại số và sự khởi đầu của phân tích 9-10” (Moscow: Prosveshcheniye, 1986), ở đoạn 20 (tr. 94), định lý về sin tùy ý đã được chứng minh: hàm sin tùy ý tại bất kỳ điểm nào và $(\sin x)'=\cos x$. Trong chứng minh của công thức này, người ta sử dụng tỷ lệ $\frac{\sin \frac{\Delta x}{2}}{\Delta x}$ có xu hướng bằng 1 khi $\Delta x$ có ​​xu hướng bằng 0:

$$\frac{\sin \frac{\Delta x}{2}}{\Delta x} \rightarrow 1$$ tại $\Delta x \rightarrow 0$.

Nói cách khác, định lý về giới hạn của tỷ số $\frac{\sin x}{x}$ tại $x \rightarrow 0$ được sử dụng:

$$\lim_{x \rightarrow 0} \frac{\sin x}{x} = 1.$$

Các nhà toán học gọi giới hạn này là giới hạn đáng chú ý đầu tiên.

Trong lưu ý này, chúng ta sẽ chứng minh định lý về giới hạn của tỷ số $(\sin x)/x$ tại $x \rightarrow 0$ (trong sách giáo khoa, cách chứng minh tương ứng dựa trên tính rõ ràng hình học, xem trang 95). Trong chứng minh, chúng ta sẽ cần một định nghĩa chính thức hơn về giới hạn so với định nghĩa được đưa ra trong “Đại số và các yếu tố giải tích 9-10” ở trang 1. 76. Cụ thể, chúng ta sẽ nói rằng hàm $f(x)$ tiến tới giới hạn $L$ tại $x \rightarrow a$ ($x \neq a$) nếu với bất kỳ số dương $\varepsilon$ nào có một số dương $\delta$ sao cho với mọi $x$ sao cho $|x-a|<\delta$ bất đẳng thức $|f(x)-L|<\varepsilon$ đúng. Nói cách khác, hàm $f(x)$ có xu hướng đạt tới giới hạn $L$ tại $x \rightarrow a$ nếu với bất kỳ $\varepsilon>0$ nào, người ta có thể chỉ định một lân cận của điểm $a$ sao cho với tất cả $x$ từ lân cận này, $x \neq a$, thì bất đẳng thức $|f(x)-L|<\varepsilon$ sẽ đúng. (Hãy tự suy nghĩ về sự tương đương của cả ba định nghĩa về giới hạn: hai định nghĩa của chúng ta và định nghĩa được đưa ra trong sách giáo khoa.)

Vì vậy, chúng ta hãy chuyển sang chứng minh định lý.

Trước tiên chúng ta hãy giả sử rằng $0<x<\frac{\pi}{2}$. Chúng ta hãy xem xét một lân cận có tâm $O$ và so sánh nó với tâm $AFC$ với mặt phẳng thẳng $ABCD$ (xem hình).

Diện tích của đoạn $AFC$ bằng hiệu giữa diện tích của hình cung $OAC$ và tam giác $OAC$, tức là.

$$S_{AFC} = \frac{1}{2} x - \frac{1}{2} \sin x > 0,$$

Ở đâu

$$\sin x < x.$$

Bây giờ chúng ta hãy ước tính diện tích của đường thẳng $ABCD$. Vì $AD=\sin x$, $DC=1-\cos x$,

$$S_{ABCD} = \sin x (1-\cos x) = 2 \sin^2 \frac{x}{2} \cdot \sin x < 2 \cdot \frac{x^2}{4} \cdot x = \frac{x^3}{2}.$$
