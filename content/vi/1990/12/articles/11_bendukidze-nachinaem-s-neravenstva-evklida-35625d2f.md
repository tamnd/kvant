---
id: 1990-12-bendukidze-nachinaem-s-neravenstva-evklida-35625d2f
issue: kvant_1990_12
year: 1990
number: "12"
title: Hãy bắt đầu với bất đẳng thức Euclid...
authors:
  - Бендукидзе А. Д.
rubric: shkola-v-kvante
page_first: 36
page_last: 37
page_labels: 34-35
lang: vi
source: kvant_digital
extraction: vision
content_sha256: 48538dffa98e615195d15c20ee798c30ff4a5a4e1ffe45bb0016f0b27e18d767
prompt_sha256: draft-1
translated_from: content/ru/1990/12/articles/11_bendukidze-nachinaem-s-neravenstva-evklida-35625d2f.md
source_content_sha256: d4cd6abcdfeebd6eb78bfb855e052534ec86269d1b75c8f27cec615683055a16
translation_model: draft
translation_run: vi-draft-gaps-2026-11-06
translation_quality: draft
---

⟦folio 34⟧

---
running_head:
folio:
---

Toán 9-11
Bài viết được xuất bản là dành cho trẻ em
Nyatiklassiki.

Hãy bắt đầu
với sự bất bình đẳng
Euclid...

Lời tuyên bố thứ hai mươi lăm của điều thứ năm
kigi của "Các nguyên lý" nổi tiếng của Euclid *) nói: nếu bốn đại lượng
tỷ lệ thuận với nhau thì lớn nhất
số nhỏ nhất lớn hơn hai số còn lại
(tức là tổng của số lớn nhất và số nhỏ nhất
cổ lớn hơn tổng của hai số còn lại).
Đối với người đọc hiện đại thì đây là một lời tuyên bố
tình hình có vẻ không đặc biệt khó khăn
nom, nhưng nó chứa tiền
*) Euclid - nhà toán học vĩ đại của Hy Lạp cổ đại,
người sống ở thế kỷ thứ 3 trước Công nguyên. Vai trò chính của anh ấy là
Bota - tác phẩm sáu tập "Những nguyên tắc" - đã có tác động
ảnh hưởng đáng kể đến sự phát triển của tất cả toán học.

gửi nhiều kết quả
số học và phân tích. Vì vậy, theo quan điểm của ông
sức mạnh có thể dễ dàng chứng minh một điều
định lý ngắn gọn về sự tiến triển, từ
ngụ ý bất đẳng thức nổi tiếng
nghệ thuật của Jacob Bernoulli*). Nhưng chúng ta đang nói về
điều này đang ở phía trước.

Vì vậy hãy xét bất đẳng thức
Euclid. Cần phải nói rằng ενkli-
Chứng minh của bất đẳng thức này thuần tuý là hình học. Tuy nhiên,
điều này không có gì đáng ngạc nhiên - xét cho cùng thì tác giả
“Nachal” trò chuyện với độc giả độc quyền bằng ngôn ngữ hình học! Không chỉ các mệnh đề hình học, mà cả các mệnh đề số học thuần túy (sau đây gọi là mệnh đề về sự vô hạn của tập hợp số nguyên tố - mệnh đề thứ 20 của Quyển IX) đều được chứng minh về mặt hình học trong Phần cơ bản.

Tuy nhiên, những ý tưởng làm cơ sở cho bằng chứng cho những tuyên bố này

*) Jacob Bernoulli - người sáng lập điềm báo
gia đình các nhà toán học Thụy Sĩ sống ở thế kỷ thứ hai
nửa thế kỷ 17.

⟦folio 35⟧

---
running_head:
folio:
---

các loại, được Euclid hiện tại trình bày một cách rõ ràng và không khó để “chuyển dịch” chúng từ ngôn ngữ hình học sang ngôn ngữ số học hoặc đại số.

Ta phải chứng minh rằng nếu $a, b, c, d$ là số dương $u$

$$\frac{a}{b} = \frac{c}{d},$$

thì tổng của số lớn nhất và số nhỏ nhất lớn hơn tổng của hai số còn lại.

Thật vậy, không mất tính tổng quát, chúng ta có thể giả sử rằng giá trị lớn nhất là $a$. Từ tỷ lệ này

$$d = b \frac{c}{a} = c \frac{b}{a},$$

và vì cả hai phân số $c/a$ và $b/a$ đều nhỏ hơn một nên $d < b, d < c$. Do đó, $d$ là số nhỏ nhất nên ta cần chứng minh bất đẳng thức

$$a + d > b + c.$$

chúng tôi có

$$\frac{a}{b} = \frac{c}{d} \Leftrightarrow \frac{a}{b} - 1 = \frac{c}{d} - 1 \Leftrightarrow$$

$$\Leftrightarrow \frac{a - b}{b} = \frac{c - d}{d} \Leftrightarrow \frac{a - b}{c - d} = \frac{b}{d} \Leftrightarrow a - b =$$

$$= \frac{b}{d}(c - d).$$

Vì $c - d > 0$ và $b/d > 1$ thì

$$a - b > c - d,$$

hoặc, điều tương tự, $a + d > b + c$. Và đây là điều chúng tôi muốn chứng minh.

Bây giờ chúng ta xây dựng và chứng minh định lý Bernoulli về cấp số cộng.

Định lý. Nếu $(a_n)$ là một cấp số cộng và $(b_n)$ là một cấp số nhân có số dương $u$ $a_1 = b_1, a_2 = b_2, a_1 \neq a_2$, thì các số hạng của cấp số nhân bắt đầu từ cấp số ba sẽ lớn hơn các số hạng tương ứng của cấp số cộng.

Bằng chứng. Hãy để $m > 2$. chúng tôi có

$$\frac{b_m}{b_{m-1}} = \frac{b_2}{b_1}.$$

Nếu $(b_n)$ là một cấp số tăng dần thì trong bốn số được viết ra, số lớn nhất sẽ là $b_m$ và số nhỏ nhất sẽ là $b_1$. Nếu tiến trình $(b_n)$ kết thúc thì ngược lại, $b_m$ là số nhỏ nhất và $b_1$ là số lớn nhất trong số này. Do đó, trong cả trường hợp thứ nhất và thứ hai, theo bất đẳng thức Euclid,

$$b_m + b_1 > b_{m-1} + b_2.$$

Nhớ lại rằng $b_1 = a_1, b_2 = a_2$ và biểu thị hiệu của cấp số $(a_n)$ với $d$, ta thu được bất đẳng thức

$$b_m > b_{m-1} + d,$$

hợp lệ cho bất kỳ $m > 2$ tự nhiên nào.

Cho $m$ lần lượt các giá trị 3, 4, 5, ..., $n$ ta thấy

$$b_3 > b_2 + d,$$

$$b_4 > b_3 + d,$$

$$b_n > b_{n-1} + d.$$

Cộng các bất đẳng thức, ta được

$$b_n > b_2 + (n - 2)d = a_2 + (n - 2)d = a_1 + (n - 1)d = a_n.$$

Vì vậy, với bất kỳ $n > 2$

$$b_n > a_n,$$

đó là những gì được yêu cầu.

Hệ quả (bất đẳng thức Bernoulli). Nếu $h > -1, h \neq 0$, thì đối với mọi $n > 1$ tự nhiên

$$(1 + h)^n > 1 + nh.$$

Thật vậy, xét hai dãy

$$1, 1 + h, (1 + h)^2, ..., (1 + h)^n, ...,$$

$$1, 1 + h, 1 + 2h, ..., 1 + nh, ...$$

Đầu tiên trong số đó là cấp số nhân, cấp số thứ hai là cấp số nhân và chúng thỏa mãn các điều kiện của định lý Bernoulli. Pozotomu

$$(1 + h)^n > 1 + nh (n = 2, 3, 4, ...),$$

đó là điều cần chứng minh.

Lưu ý rằng đối với $h > 0$, sự bất bình đẳng này tuân theo công thức tính quần xã Newton, nhưng đối với $-1 < h < 0$, điều đó không hoàn toàn rõ ràng ngay cả với những người quen thuộc với quần xã Newton.

A. Vendukidze
