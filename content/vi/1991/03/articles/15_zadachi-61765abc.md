---
id: 1991-3-zadachi-61765abc
issue: kvant_1991_3
year: 1991
number: "3"
title: Bài toán
rubric: konkurs-imeni-a-p-savina
rubric_sub: Конкурс имени А. П. Савина
page_first: 50
page_last: 51
page_labels: 48-49
lang: vi
source: kvant_digital
extraction: vision
content_sha256: 9bbdc5b95805c8d6dadab0f9bb55142dd30a3edea2c8e7e4caaaa1ad0b2ba323
prompt_sha256: draft-1
translated_from: content/ru/1991/03/articles/15_zadachi-61765abc.md
source_content_sha256: e7af640bb052c5c49933e5c87b3887f2c382d03fa637f55eb5ce77f8d1716292
translation_model: draft
translation_run: vi-draft-gaps-2026-11-06
translation_quality: draft
---

⟦folio 48⟧

Bài toán

19. Tam giác đều ABC nằm trên một mặt phẳng. Hãy chỉ ra tất cả các điểm $M$ của mặt phẳng này sao cho cả hai tam giác ABM và ASM đều bằng nhau.

A. Savin

20. Andrey tùy ý chia một chồng 200 que diêm thành 6 chồng (mỗi chồng chứa ít nhất một que diêm), rồi đến Boris. cân bằng số que diêm ở hai cọc này, lấy một vài que diêm từ một cọc. Chúng tôi gọi số trận đấu được thực hiện bởi Boris Andrey. Boris cố gắng tham gia càng ít trận đấu càng tốt. Andrey nên chơi như thế nào để đảm bảo chiến thắng tối đa cho mình?

X. Khaimov

21. Trên bàn cờ, các đường ngang và dọc được đánh số từ 1 đến 8. Trên bàn cờ có 8 quân xe được đặt sao cho chúng không cạnh nhau. Đối với mỗi quân, chúng tôi tính tích của các số đường ngang và dọc mà nó đứng trên đó. Hãy lấy tổng của các sản phẩm này. Chứng minh rằng đối với một cách sắp xếp các quân xe đối xứng tâm với một quân đã cho thì tổng thu được theo cách tương tự sẽ bằng tổng ban đầu.

V. Proizvolov

⟦folio 49⟧

---
running_head:
folio:
---

Trên thực tế, mức tối thiểu của hàm tổng $f(x)+g(x)$ đạt được tại một số điểm của đoạn $[a; b]$. Tại thời điểm này, các giá trị của hàm $f(x)$ và $g(x)$ không nhỏ hơn giá trị tối thiểu của chúng. Rõ ràng là bất đẳng thức sẽ chuyển thành đẳng thức nếu đạt đến cực tiểu $f(x)$ và $g(x)$ tại cùng một điểm.

Tình huống hoàn toàn giống với trường hợp của hàm $n$:

$$\min f_1(x) + \dots + \min f_n(x) \leqslant \leqslant \min (f_1(x) + \dots + f_n(x)).$$

Chứng minh dễ dàng thu được bằng quy nạp. Ở bên phải, chúng ta sẽ chọn từng hàm một: $\min (f_1(x) + \dots + f_n(x)) \geqslant \min (f_1(x) + \dots + f_{n-1}(x)) + \min f_n(x)$, v.v.

Cực tiểu của hàm bậc hai và bất đẳng thức bậc hai

Hãy bắt đầu với hàm bậc hai có dạng $f(x)=ax^2+2bx$, trong đó $a>0$. Để tìm số nhỏ nhất, hãy chọn một hình vuông hoàn chỉnh

$$ax^2+2bx=a\left(x^2+2\frac{b}{a}x+\frac{b^2}{a^2}-\frac{b^2}{a^2}\right)=a\left(\left(x+\frac{b}{a}\right)^2-\frac{b^2}{a}\right)=a\left(x+\frac{b}{a}\right)^2-\frac{b^2}{a}.$$

Vì vậy, mức tối thiểu đạt được ở $x=-\frac{b}{a}$ và bằng $f\left(-\frac{b}{a}\right)=-\frac{b^2}{a}$.

Bây giờ đến hàm $n$

$$f_1(x)=a_1x^2+2b_1x,$$
$$f_2(x)=a_2x^2+2b_2x,$$
$$\dots$$
$$f_n(x)=a_nx^2+2b_nx$$

Chúng ta hãy chấp nhận sự bất bình đẳng cơ bản của chúng ta. Hàm $f(x)$ có giá trị tối thiểu là $x=$
