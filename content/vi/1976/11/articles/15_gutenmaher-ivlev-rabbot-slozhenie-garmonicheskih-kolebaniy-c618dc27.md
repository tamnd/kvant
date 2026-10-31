---
id: 1976-11-gutenmaher-ivlev-rabbot-slozhenie-garmonicheskih-kolebaniy-c618dc27
issue: kvant_1976_11
year: 1976
number: "11"
title: Bổ sung các dao động điều hòa
authors:
  - Гутенмахер В. Л.
  - Ивлев Б. М.
  - Раббот Ж. М.
rubric: po-stranitsam-shkolnyh-uchebnikov
rubric_sub: По страницам школьных учебников
page_first: 46
page_last: 48
page_labels: 44-46
tag: LOL2
lang: vi
source: kvant_digital
extraction: vision
content_sha256: dc9ef1672e127d8a70cb121d337c26c4b45748520e5b8f2e0d2d27fe19f254ed
prompt_sha256: draft-1
translated_from: content/ru/1976/11/articles/15_gutenmaher-ivlev-rabbot-slozhenie-garmonicheskih-kolebaniy-c618dc27.md
source_content_sha256: 7882e6961e1e51619536163b024a756f6eee190fc988bb29795da4711f0ae1e1
translation_model: draft
translation_run: vi-draft-2026-10-31
translation_quality: draft
---

⟦folio 44⟧

Bổ sung các dao động điều hòa

Trong đoạn 80 của § 16 của sách giáo khoa “Đại số và Nguyên tắc phân tích 10”, khái niệm dao động điều hòa được giới thiệu bằng ví dụ về chuyển động của một quả bóng gắn với hai lò xo nằm ngang (Hình 1). Ở đây chúng ta sẽ không nói về các quá trình vật lý trong đó những rung động hài hòa phát sinh một cách tự nhiên. Mục tiêu của chúng ta là hiểu được phép cộng các dao động điều hòa có cùng tần số.

Như chúng ta đã lưu ý (Hình 1), dao động điều hòa có thể được biểu diễn dưới dạng dao động của điểm gốc O dọc theo trục Ox. Đồ thị của chuyển động này giống đồ thị của hàm số

$$x(t) = A \cos(\omega t + \varphi).$$

Độ lệch lớn nhất của điểm x(t) so với điểm O trong quá trình dao động tất nhiên bằng số |A| và được gọi là biên độ dao động. Chu kỳ dao động bằng $$\frac{2\pi}{|\omega|}.$$ Giá trị |ω| gọi là tần số dao động. Vị trí ban đầu của điểm x(t) (tại thời điểm t=0) được xác định bởi giá trị A cos φ.

Tất nhiên, cùng một dao động điều hòa có thể được tính bằng các công thức khác nhau.

Sử dụng ví dụ về chuyển động của các điểm dao động, chúng ta áp dụng chúng, nghĩa là cộng hai dao động điều hòa. Nếu một điểm x₁ có vị trí ban đầu trên trục Ox A₁cos φ₁ dao động theo định luật x₁(t) = A₁cos(ω₁t + φ₁) và một điểm x₂ khác có vị trí ban đầu A₂cos φ₂ - theo định luật x₂(t) = A₂(cos ω₂t + φ₂), thì tổng các dao động này sẽ là dao động của một điểm x nhất định với vị trí ban đầu A₁cos φ₁ + A₂cos φ₂ theo định luật x(t) = A₁cos(ω₁t + φ₁) + A₂cos(ω₂t + φ₂). Hóa ra là nếu các điểm x₁ và x₂ dao động với cùng tần số ω₁ = ω₂ = ω, thì tổng của chúng cũng sẽ là dao động điều hòa có cùng tần số ω. Thực tế này trong đoạn 82 § 16 của sách giáo khoa bắt nguồn từ thực tế là tổng của hai phương trình vi phân lời giải y'' = -ω²y lại là lời giải của phương trình này (và tất cả lời giải của nó đều có dạng y = A cos(ωt + φ). Liệu có thể thu được kết quả này bằng cách nào đó đơn giản hơn mà không cần biết các phương trình vi phân?

Bạn có thể thử thêm các rung động hài hòa bằng đồ họa. Hình 2 biểu diễn đồ thị của hai hàm số có cùng chu kỳ: y = 2cos(2t + π/3) và y = cos(2t + π/6). Từ hai đồ thị này, không hề rõ ràng rằng tổng y = 2cos(2t + π/3) + cos(2t + π/6) của chúng sẽ là một dao động điều hòa. Vì vậy, như chúng ta có thể thấy, điều này không thuận tiện lắm.

Cơm. 1.

⟦folio 45⟧

Trong trường hợp $\omega_1 = \omega_2 = \omega$, việc minh họa phép cộng các dao động điều hòa bằng biểu đồ vectơ của chúng sẽ dễ dàng hơn nhiều. Hãy giải thích nó là gì.

Trước hết, các điều kiện để dao động điều hòa được viết là $A \cos(\omega t + \varphi)$, trong đó $A > 0$, $\omega > 0$ và $\varphi \in [0, 2\pi]$. Chúng ta có thể mang lại bất kỳ rung động hài hòa nào cho hình thức này. Bây giờ chúng ta hãy xem xét một số hệ tọa độ $XOY$ và lấy một đường tròn có bán kính $A$ với tâm $O$ ở gốc tọa độ (hãy nhớ rằng $A$ được chọn là dương). Giả sử rằng một điểm nhất định $P(t)$ di chuyển ngược chiều kim đồng hồ dọc theo vòng tròn này - vị trí của nó phụ thuộc vào thời gian $t$ - sao cho vectơ $\vec{OP}(t)$ quay đều, vượt qua $\omega$ radian trên một đơn vị thời gian ($\omega$ được chọn dương). Giả sử rằng tại thời điểm ban đầu $(t = 0)$ vectơ $\vec{OP}(0)$ tạo một góc $\varphi$ ($\varphi \in [0, 2\pi]$) với hướng dương của trục $OX$, tức là tọa độ của điểm $P(0)$ là $(A\cos\varphi; A\sin\varphi)$. Khi đó góc mà vectơ $\vec{OP}(t)$ tạo với hướng dương của trục $OX$ tại thời điểm $t$ bằng $\omega t + \varphi$, nên tọa độ của vectơ $\vec{OP}(t)$ là $(A\cos(\omega t + \varphi); A\sin(\omega t + \varphi))$, và ta thu được hình chiếu của điểm $P(t)$ lên trục $OX$ và hình chiếu của điểm $P(t)$ trên trục $OY$ thực hiện các dao động điều hòa có cùng biên độ và tần số! Do đó, dao động điều hòa của một điểm, chẳng hạn như trên trục $OX$, có thể được hiểu là dao động của hình chiếu của một vectơ $\vec{OP}(t)$ nào đó, quay đều quanh điểm $O$, lên trục $OX$. Vị trí ban đầu của vectơ $\vec{OP}(t)$, tức là $\vec{OP}(0)$, xác định biên độ dao động (nó bằng độ dài của vectơ $\vec{OP}(0)$) và pha ban đầu $\varphi = (\vec{OP}(0), \vec{OX})$; - chỉ thiếu tần số. Vectơ $\vec{OP}(0)$ được gọi là sơ đồ vectơ của dao động điều hòa có biên độ $A$ và pha ban đầu $\varphi$.

Bài toán 1. Vẽ sơ đồ vectơ của các dao động điều hòa sau:

a) $-3\cos\left(2t + \frac{\pi}{3}\right)$; b) $3\cos\left(2t + \frac{4\pi}{3}\right)$; c) $3\cos\left(-2t + \frac{2\pi}{3}\right)$; d) $3\sin\left(2t + \frac{\pi}{3}\right)$; e) $3\sin\left(-2t + \frac{\pi}{3}\right)$.

Với sự trợ giúp của sơ đồ vectơ, người ta có thể dễ dàng hiểu được việc bổ sung các dao động điều hòa. Hãy vẽ sơ đồ vectơ của hai dao động điều hòa (có cùng tần số!): vectơ $\vec{OP}_1$ và $\vec{OP}_2$ (Hình 3). Khi đó sơ đồ vectơ của tổng các dao động này sẽ là vectơ $\vec{OP} = \vec{OP}_1 + \vec{OP}_2$. Trong thực tế,

⟦folio 46⟧

Cơm. 3.

hình chiếu của vectơ $\vec{OP}_1(t)$ và $\vec{OP}_2(t)$ lên trục $OX$ được viết như sau:
$$x_1 = A_1 \cos(\omega t + \varphi_1),$$
ở đâu $A_1 = |\vec{OP}_1|$, $\varphi_1 = (\vec{OP}_1, \vec{OX})$;
$$x_2 = A_2 \cos(\omega t + \varphi_2),$$
ở đâu $A_2 = |\vec{OP}_2|$, $\varphi_2 = (\vec{OP}_2, \vec{OX})$.
Hình chiếu lên trục $OX$ của tổng $\vec{OP}(t) = \vec{OP}_1(t) + \vec{OP}_2(t)$ của chúng bằng $x_1 + x_2$, tức là $A_1 \cos(\omega t + \varphi_1) + A_2 \cos(\omega t + \varphi_2)$, vì vậy vectơ $\vec{OP}$ trên thực tế là sơ đồ vectơ biểu thị tổng các dao động điều hòa thấp nhất.

Bây giờ chúng ta lưu ý rằng vectơ $\vec{OP}(t)$ là đường chéo của hình bình hành tính từ các cạnh $OP_1(t)$ và $OP_2(t)$ (xem Hình 3). Vì vectơ $\vec{OP}_1(t)$ và $\vec{OP}_2(t)$ quay với cùng vận tốc góc nên toàn bộ hình bình hành quay như một hình cứng. Do đó, đường chéo của nó quay với cùng tốc độ góc $\omega$, sao cho hình chiếu của vectơ $\vec{OP}(t)$ lên trục $OX$ (trục hoành của điểm $P(t)$) thực hiện một dao động điều hòa có cùng tần số $\omega$ với hình chiếu của các vectơ $\vec{OP}_1(t)$ và $\vec{OP}_2(t)$ lên trục $OX$ (abscissa của điểm $P_1(t)$ và $P_2(t)$).

Rõ ràng cách tính biên độ và pha ban đầu của tổng này (biên độ là các đường chéo của hình bình hành và pha ban đầu là góc mà đường chéo này tạo với trục $OX$ - xem bài toán Số 260 trên trang 59 của sách giáo khoa).

Nhiệm vụ 2. Vẽ sơ đồ vectơ của tổng các dao động $a$ và $b$, d) và e) từ nhiệm vụ 1 và tìm biên độ cũng như pha ban đầu của chúng.

Bằng cách sử dụng sơ đồ vectơ, một phát biểu quan trọng hơn có thể được chứng minh, đó là, bất kỳ dao động điều hòa nào cũng có thể được biểu diễn bằng công thức $f(t) = a \cos \omega t - b \sin \omega t$. Hãy xem xét điều này chi tiết hơn.

Giả sử chúng ta có một dao động điều hòa $A$ cos $(\omega t + \varphi)$ với tần số $\omega$, và đặt $\vec{OP}(0) = (A \cos \varphi; A \sin \varphi)$ là sơ đồ vectơ của nó trong hệ tọa độ $XOY$. Cho $\vec{i}$ và $\vec{j}$ là các vectơ đơn vị vuông góc với nhau, cho hệ tọa độ $XOY$ (xem đoạn 70 § 14 của sách giáo khoa “Đại số và nguyên lý giải tích, 9”). Sau đó $\vec{OP}(0) = A \cos \varphi \cdot \vec{i} + A \sin \varphi \cdot \vec{j}$. Bây giờ chúng ta giả sử rằng các vectơ $\vec{i}$ và $\vec{j}$ quay đều và đồng thời với vectơ $\vec{OP}(t)$ quanh điểm $O$ với cùng vận tốc góc $\omega$ như vectơ $\vec{OP}(t)$. Sau đó $\vec{i}(t) = (\cos \omega t; \sin \omega t), \vec{j}(t) = (-\sin \omega t; \cos \omega t)$. Vì các vectơ $\vec{OP}(t)$, $\vec{i}(t)$ và $\vec{j}(t)$ quay như một hình cứng và tại thời điểm ban đầu $\vec{OP}(0) = a \cdot \vec{i} + b \cdot \vec{j}$ ($a = A \cos \varphi, b = A \sin \varphi$), nên tại thời điểm $t$ tọa độ thứ x, tức là số $A \cos (\omega t + \varphi)$ của vectơ $\vec{OP}(t)$ sẽ bằng tổng $x-x$ tọa độ của vectơ $a \cdot \vec{i}(t)$ và $b \cdot \vec{j}(t)$, tức là $A \cos (\omega t + \varphi) = a \cos \omega t - b \sin \omega t$.

Vì vậy, chúng tôi đã trình bày dao động điều hòa $A$ cos $(\omega t + \varphi)$ là tổng của hai dao động điều hòa có cùng tần số $\omega : a \cos \omega t - b \sin \omega t$ (xét cho cùng, đồ thị sin là đồ thị cosin lệch pha một phần tư chu kỳ.
