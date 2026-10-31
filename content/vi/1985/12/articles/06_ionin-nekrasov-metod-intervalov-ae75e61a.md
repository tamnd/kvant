---
id: 1985-12-ionin-nekrasov-metod-intervalov-ae75e61a
issue: kvant_1985_12
year: 1985
number: "12"
title: Phương pháp ngắt quãng
authors:
  - Ионин Ю. И.
  - Некрасов В. Б.
rubric: shkola-v-kvante
page_first: 20
page_last: 22
page_labels: 18-20
tag: EQIA
lang: vi
source: kvant_digital
extraction: vision
content_sha256: 499a083c37e2df3e1d3994ce251d3a8426c2e55d8158595d5b772932572da5c3
prompt_sha256: draft-1
translated_from: content/ru/1985/12/articles/06_ionin-nekrasov-metod-intervalov-ae75e61a.md
source_content_sha256: 50103adba14612d1343f2695e9a0067ae9f40d591a6d7252c740481d52dda64c
translation_model: draft
translation_run: vi-draft-2026-10-31
translation_quality: draft
---

⟦folio 18⟧

Toán 9-10

Phương pháp tích phân

Bài viết này dành cho học sinh lớp chín và lớp mười. Ứng viên cũng có thể sử dụng nó khi chuẩn bị cho kỳ thi tuyển sinh đại học.

Trong khóa học đại số ở trường, một vị trí quan trọng được dành cho các bất đẳng thức: đầu tiên, đây là các bất đẳng thức tuyến tính, sau đó là bậc hai, sau đó là các bất đẳng thức trong đó có liên quan đến hàm logarit, hàm mũ và lượng giác. Dần dần, sự bất bình đẳng được tạo ra – đủ loại tổ hợp chức năng được học ở trường xuất hiện. Trong bài viết này, chúng ta sẽ sử dụng một số ví dụ để minh họa một phương pháp quan trọng của bất đẳng thức lời giải, thường được gọi là “phương pháp tích phân”. Ở đây chúng ta sẽ xem xét các bất đẳng thức, phần bên phải của nó bằng 0 và phần bên trái được biểu diễn dưới dạng tích hoặc một phần của các hàm với các khoảng hằng số đã biết. Phương pháp tích phân dựa trên ý tưởng sau: dấu của tích (từng phần) được xác định bằng dấu của các thừa số (dấu phân cách và số chia).

Bài toán 1. Giải bất đẳng thức

$$\frac{(2x-1)(x^2-x-2)}{3-x} < 0.$$

Hàm tuyến tính có độ dốc khác 0 đổi dấu khi đi qua nghiệm và ở bên phải gốc, dấu của hàm trùng với dấu của độ dốc (hình 1); tam thức vuông có phân biệt dương cũng đổi dấu khi đi qua từng căn thức, và ở bên phải căn thức, dấu của tam thức vuông trùng với dấu của hệ số dẫn đầu của nó (hình 2).

Những thông báo này dẫn đến mô hình bất bình đẳng sau lời giải.

1. Chúng tôi tìm ra gốc rễ của từng “thành phần”: $x=\frac{1}{2}; x=-1, x=2; x=3$.

2. Trục số được chia thành năm khoảng. Ở ngoài cùng bên phải của mỗi số, hệ số trùng với dấu của hệ số dẫn đầu của nó: $2x-1>0, x^2-x-2>0, 3-x<0$.

Do đó, phân số trên khoảng này là âm.

3. Khi đi qua từng nghiệm đã đánh dấu, một và chỉ một trong các thừa số đổi dấu, và do đó dấu của phân số thay đổi mỗi lần. Khi tính đến điều này, chúng tôi đặt các dấu hiệu trong các khoảng này (như được hiển thị trong hình 3).

4. Chúng tôi chọn các khoảng trong đó phân số âm.

Đáp số:

$$]-\infty; -1[\cup]\frac{1}{2}; 2[\cup]3; +\infty.$$

Bài toán 2. Giải bất đẳng thức

$$\frac{4-x^2}{(5x-2)\lg x} \ge 0.$$

Chúng ta sẽ giải bất đẳng thức này bằng cách sử dụng cùng một sơ đồ, nhưng không phải trên tất cả các trục mà trên khoảng $]0; +\infty[$ - vùng op-

⟦folio 19⟧

giới hạn của hàm logarit.

1. Hệ số gốc: $x=2; x=0,4; x=1$ (hình 4).

2. Bán trục $]0; +\infty[$ được chia thành bốn khoảng. Ở ngoài cùng bên phải là $4-x^2<0, 5x-2>0, lgx>0$. Do đó, phần bất đẳng thức nằm trên khoảng này là âm.

3. Khi đi qua mỗi nghiệm thì có một và chỉ một thừa số đổi dấu. Khi tính đến điều này, chúng tôi đặt các dấu hiệu trên các khoảng còn lại (hình 4).

4. Chúng ta đã giải được bất đẳng thức chặt chẽ. Vẫn còn phải thêm vào tập kết quả lời giải nghiệm của phương trình

$$\frac{4-x^2}{(5x-2)lgx}=0,$$

tức là nghiệm của tử số của phân số (nằm trong phạm vi định nghĩa của bất đẳng thức).

Đáp số: $]0; 0,4[\cup]1; 2]$.

Bài toán 3. Giải bất đẳng thức

$$\frac{(10^x-2)(x^2-5x+7)}{x+3} \leq 0.$$

Lời giải được mô tả trên hình 5. Bộ ba bình phương trong tử số của một phân số không có nghiệm và do đó không đổi dấu, trùng với dấu của hệ số dẫn đầu của nó.

Đáp số: $]-3; lg2]$.

Bài toán 4. Giải bất đẳng thức

$$(x^2-2x-3)(6+x-x^2) \geq 0.$$

1. Tìm nghiệm nguyên của các thừa số: $x=-1, x=3, x=-2, x=3$.

2. Với $x>3$ vế trái của bất đẳng thức là âm.

3. Khi đi qua điểm $x=3$, cả hai thừa số đều đổi dấu ($x=3$ là nghiệm chung) nên dấu của tích không đổi.

Khi đi qua hai nghiệm còn lại, vế trái, như trong ví dụ trước, đổi dấu (hình 6).

Đáp số: $[-2; -1]\cup\{3\}$.

Từ bài toán này rõ ràng rằng, khi sử dụng phương pháp tích phân, cần phải theo dõi xem có bao nhiêu thừa số đổi dấu khi đi qua một nghiệm cho trước. Các thừa số có thể không đổi dấu khi đi qua nghiệm của chúng (ví dụ, một trilen bình phương có phân biệt bằng 0).

Ý tưởng lời giải của điều sau đây dựa trên một định lý rõ ràng bằng trực giác, bằng chứng chính xác về định lý này được đưa ra trong các khóa học về giải tích toán học: nếu một hàm liên tục trên một khoảng và không có nghiệm trong khoảng này thì nó giữ nguyên dấu trong khoảng này.

⟦folio 20⟧

Nhiệm vụ 7. Giải bất đẳng thức
$$\sqrt{x+2} > x.$$ (1)

Hàm $y = \sqrt{x+2} - x$ được xác định và liên tục trên khoảng $[-2; +\infty]$.

Hãy tìm nghiệm nguyên của hàm số này, tức là giải phương trình
$$\sqrt{x+2} = x.$$ (2)

Bằng cách bình phương cả hai vế của phương trình (2), chúng ta thu được phương trình bậc hai $x^2 - x - 2 = 0$ với các nghiệm $x = -1$, $x = 2$. Kiểm tra cho thấy nghiệm của phương trình (2) chỉ là $x = 2$. Điểm này chia miền định nghĩa của bất đẳng thức (1) thành hai khoảng: $[-2; 2[$ và $]2; +\infty[$. Trên mỗi khoảng này, hàm $y = \sqrt{x+2} - x$ giữ nguyên dấu, nghĩa là tất cả các điểm của khoảng đó đều thỏa mãn bất đẳng thức (1) hoặc không có điểm nào thỏa mãn. Vì vậy, chỉ cần thay một điểm trong mỗi khoảng vào bất đẳng thức (1) là đủ. Hãy chọn điểm $x = -2$ và $x = 7$. Vì $x = -2$ thỏa mãn bất đẳng thức (1), nhưng $x = 7$ thì không, tập lời giải của bất đẳng thức (1) là khoảng $[-2; 2[$ (hình 9).

Đáp số: $[-2; 2]$.

Bài 8. Giải bất đẳng thức
$$x\sqrt{10-x^2} \geq x^2 - 6.$$

1. Các miền của hàm $\sqrt{10-x^2}$: $[-\sqrt{10}; \sqrt{10}]$.

2. Chúng ta giải phương trình:
$$x\sqrt{10-x^2} = x^2 - 6,
x^2(10-x^2) = (x^2 - 6)^2;
x^4 - 11x^2 + 18 = 0.$$

Chúng ta có bốn nghiệm: $x = \pm \sqrt{2}, x = \pm 3$. Tấm séc để lại hai gốc: $x = -\sqrt{2}, x = 3$ (hình 10).

3. Chúng ta thay các số $x = -\sqrt{10}, x = 0, x = \sqrt{10}$ vào bất đẳng thức. Số $x = 0$ thỏa mãn bất đẳng thức, còn số $x = \pm \sqrt{10}$ thì không.

Đáp số: $[-\sqrt{2}; 3]$.

Như đã biết, các hàm tuyến tính, bậc hai, lũy thừa, hàm mũ, logarit và lượng giác, cũng như các thành phần và hàm thu được từ chúng bằng cách sử dụng các phép toán số học, đều không chính xác trong phạm vi định nghĩa của chúng. Do đó, phương pháp tích phân có thể được sử dụng cho lời giải trên thực tế tất cả các bất đẳng thức của khóa học ở trường. Phương pháp tích phân cho phép chúng ta biểu diễn tập lời giải của bất đẳng thức dưới dạng hợp của các khoảng, ranh giới của chúng là nghiệm của phương trình tương ứng hoặc là điểm biên của miền định nghĩa của bất đẳng thức.

Yêu cầu về tính liên tục là cần thiết cho việc áp dụng phương pháp tích phân. Bạn có thể xác minh điều này ở bài toán tiếp theo.

Nhiệm vụ 9. Giải bất đẳng thức
$$[x] \leq x - \frac{1}{2}.$$

Hãy dựng đồ thị bên trái và bên phải của bất đẳng thức (hình 11). Các nghiệm của phương trình $[x] = x - \frac{1}{2}$ là các số có dạng $k + \frac{1}{2}$, trong đó $k$ là số nguyên bất kỳ. Đồng thời, tập lời giải của bất đẳng thức là tập hợp các khoảng có dạng $[k + \frac{1}{2}; k + 1]$, đặc biệt, các điểm biên của chúng là tất cả các số nguyên không phải là nghiệm của phương trình cũng như các điểm biên của miền định nghĩa.

Yu. I. Ionin, V. V. Nekrasov
