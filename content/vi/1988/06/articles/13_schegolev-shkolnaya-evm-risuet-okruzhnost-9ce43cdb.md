---
id: 1988-6-schegolev-shkolnaya-evm-risuet-okruzhnost-9ce43cdb
issue: kvant_1988_6
year: 1988
number: "6"
title: Máy tính của trường vẽ một vòng tròn
authors:
  - Щёголев А. Г.
rubric: raznoe
rubric_sub: Разное
page_first: 58
page_last: 60
page_labels: 56-58
tag: F4A8
lang: vi
source: kvant_digital
extraction: vision
content_sha256: 87e0044b211ca0449d974bdda5375a8d612394331caf5cd987f7e43604559f38
prompt_sha256: draft-1
translated_from: content/ru/1988/06/articles/13_schegolev-shkolnaya-evm-risuet-okruzhnost-9ce43cdb.md
source_content_sha256: 2a4c924644e89440ec978013e6596b361dacc10c50d113f53bd337f975a16520
translation_model: draft
translation_run: vi-draft-2026-10-31
translation_quality: draft
---

⟦folio 56⟧

Máy tính của trường vẽ một vòng tròn

A. G. SHEGOLEV

Trong số trước «Kvant» chúng ta đã nói một chút về khả năng đồ họa của máy tính trường học Yamaha (và ngôn ngữ MSX - BASIC), vẽ ra những bức tranh đẹp - hay nói đúng hơn là các thuật toán được biên soạn để thực hiện những hình này. Lần này chúng ta sẽ chứng minh khả năng đồ họa của máy móc với cấu trúc lời giải hình học bài toán. Chúng tôi sẽ giới hạn việc phân tích chỉ một bài toán, nhưng phân tích này sẽ rất chi tiết; nó dựa trên các nguyên tắc lập trình hệ thống (xem «Kvant», 1987, số 10, 11). Vì vậy, bài toán: Vẽ một đường tròn đi qua ba điểm với các thuộc tính tọa độ.

Về bản chất, bạn bài toán về việc dựng một đường tròn ngoại tiếp một hình tam giác. Việc xây dựng này có thể được thực hiện một cách duy nhất nếu ba điểm khác nhau và không nằm trên cùng một đường thẳng.

Chúng ta hãy tiến hành xây dựng một cách có hệ thống hoàn chỉnh thuật toán và chương trình.

Hãy dựng đường tròn đi qua ba điểm.
Tọa độ của điểm đầu tiên
Tọa độ của điểm thứ hai
Tọa độ của điểm thứ ba

Một vòng tròn không thể được vẽ qua những điểm này (và đây là cách duy nhất!)!

Hình 1.

⟦folio 57⟧

Dàn dựng:
Cho: $(x_1, y_1)$ — tọa độ của các điểm $A, B, C$.
Bắt buộc: $\sigma$ - hình ảnh của một vòng tròn (hoặc một phần của vòng tròn nằm trong màn hình).
Khi: $A, B, C$ không nằm trên cùng một đường thẳng.
Liên hệ: $A \in \sigma, B \in \sigma, C \in \sigma$.

Kịch bản:
Trên hình 1, các vòng tròn màu xanh lam chứa các thành phần có thể thay đổi của cuộc đối thoại trong tương lai - những con số cụ thể được một người trong đáp số báo cáo theo yêu cầu của máy tính. Các hình trong ngoặc chứa hai phiên bản của máy tính: phiên bản đầu tiên sẽ được nhìn thấy nếu các điểm có tọa độ đã cho nằm trên cùng một đường thẳng, phiên bản thứ hai - nếu tọa độ của các điểm thỏa mãn công thức; trong trường hợp sau này, màn hình sẽ hiển thị điểm $A, B, C$ với tọa độ đã cho và một vòng tròn đi qua chúng.

Phương pháp:
Điều kiện ba điểm $A, B$ và $C$ thẳng hàng tương đương với sự thẳng hàng của các vectơ $\overrightarrow{AB}$ và $\overrightarrow{BC}$ (hình 2) và có dạng
$$(x_2 - x_1)(y_3 - y_2) = (y_2 - y_1)(x_3 - x_2).$$
Bài tập 1. Đảm bảo rằng điều kiện này cũng bao gồm các trường hợp hai (hoặc thậm chí cả ba) điểm bất kỳ trùng nhau.
Để vẽ một vòng tròn, chúng ta phải cho người thực hiện (máy tính của trường) biết tọa độ tâm và bán kính của nó.
Như đã biết, tâm $S$ của đường tròn ngoại tiếp có thể được coi là giao điểm của trung điểm của phân bố lại với hai cạnh của tam giác $(AB$ và $BC$ trên hình 3).
 tọa độ vectơ:
$$\overrightarrow{AB} = (x_2 - x_1, y_2 - y_1),$$
$$\overrightarrow{BC} = (x_3 - x_2, y_3 - y_2);$$
$M$ - chính giữa cạnh $AB$ - có tọa độ
$$(\frac{x_1 + x_2}{2}, \frac{y_1 + y_2}{2});$$
 tọa độ điểm $N$ - điểm giữa

hai bên $BC$
$$(\frac{x_2 + x_3}{2}, \frac{y_2 + y_3}{2}).$$

Bất kỳ điểm nào nằm trên đường thẳng $MS$ đều có tọa độ $(M_x + \lambda m_x, M_y + \lambda m_y)$, trong đó $M_x$ và $M_y$ là các trục hoành và tọa độ tương ứng của điểm $M$; $m_x = y_2 - y_1$ và $m_y = x_2 - x_1$ là tọa độ của vectơ $m$; $\lambda$ là một số.
Bài tập 2. Chứng minh rằng $\vec{m} \perp \overrightarrow{AB}$.
 tọa độ các điểm trên đường thẳng $NS$ được thể hiện tương tự thông qua tham số $\mu$, tọa độ điểm $N$ và vectơ vuông góc với $\overrightarrow{BC}$ (ví dụ: vectơ $n = (y_3 - y_2, x_2 - x_3)$). Để tìm giao điểm của đường $MS$ và $NS$, ta đánh đồng tọa độ tương ứng:
$$\begin{cases} M_x + \lambda m_x = N_x + \mu n_x, \\ M_y + \lambda m_y = N_y + \mu n_y. \end{cases}$$

Giải hệ phương trình tuyến tính này cho các ẩn số $\lambda$ và $\mu$, chẳng hạn, chúng ta thu được biểu thức cho $\lambda$:
$$\lambda = \frac{1}{2} \frac{(y_3 - y_2)(y_3 - y_1) - (x_2 - x_3)(x_3 - x_1)}{(y_2 - y_1)(x_3 - x_2) - (x_2 - x_1)(y_3 - y_2)}.$$
 tọa độ tâm đường tròn
$$S_x = M_x + \lambda m_x = \frac{x_1 + x_2}{2} + \lambda (y_2 - y_1),$$
$$S_y = M_y + \lambda m_y = \frac{y_1 + y_2}{2} + \lambda (x_1 - x_2).$$
Bán kính obtuis được xác định theo định lý Pythagore là khoảng cách giữa tâm và bất kỳ điểm nào đã cho (ví dụ:

⟦folio 58⟧

mét $A$):

$$r = \sqrt{(S_x - x_1)^2 + (S_y - y_1)^2}.$$

Bây giờ, đã có script và phương pháp tính toán, chúng ta hãy xây dựng một thuật toán và dịch nó sang MSX - BASIC. Chúng tôi sử dụng thuật toán phụ trợ “hình ảnh” (GOSUB 200 là lệnh gọi chương trình con tương ứng).

Thuật toán:

vòng tròn đại số
sự khởi đầu
đầu ra “Dựng đường tròn”, “đi qua ba điểm”.
yêu cầu “ Tọa độ điểm đầu tiên”; $x_1, y_1$
yêu cầu tọa độ của điểm thứ hai; $x_2, y_2$
yêu cầu tọa độ của điểm thứ ba; $x_3, y_3$

nếu $(x_2 - x_1)(y_3 - y_2) = (y_2 - y_1)(x_3 - x_2)$
sau đó là kết luận “Không thể” “vẽ một vòng tròn đi qua những điểm này” “(và điểm duy nhất ở đó)!”

hình ảnh inche
Tất cả
lừa đảo

hình ảnh đại số
sự khởi đầu
đồ họa
chấm $(x_1, y_1)$, màu hồng
chấm $(x_2, y_2)$, màu hồng
chấm $(x_3, y_3)$, màu hồng

$$\lambda := \frac{1}{2} \frac{(y_3 - y_2)(y_3 - y_1) - (x_2 - x_3)(x_3 - x_1)}{(y_2 - y_1)(x_3 - x_2) - (x_2 - x_1)(y_3 - y_2)}$$

$$S_x := \frac{x_1 + x_2}{2} + \lambda(y_2 - y_1)$$

$$S_y := \frac{y_1 + y_2}{2} + \lambda(x_1 - x_2)$$

$$r := \sqrt{(S_x - x_1)^2 + (S_y - y_1)^2}$$

vòng tròn $(S_x, S_y)$, $r$, màu hồng
lừa đảo

Chương trình:

vòng tròn 10'
