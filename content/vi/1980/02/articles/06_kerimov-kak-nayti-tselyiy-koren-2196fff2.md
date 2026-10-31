---
id: 1980-2-kerimov-kak-nayti-tselyiy-koren-2196fff2
issue: kvant_1980_2
year: 1980
number: "2"
title: Làm thế nào để tìm thấy toàn bộ gốc?
authors:
  - Керимов З.
rubric: osnovnye-stati
page_first: 24
page_last: 24
page_labels: "22"
tag: WSO6
lang: vi
source: kvant_digital
extraction: vision
content_sha256: f4ef1eac3cf8eb48f0b1136e17137a65b65086e1538d5bc36fbf892b7ceb82f3
prompt_sha256: draft-1
translated_from: content/ru/1980/02/articles/06_kerimov-kak-nayti-tselyiy-koren-2196fff2.md
source_content_sha256: 7842d5a1e61f767dc5de07c41e0b6372dbf71a50ee08a20334cc62963c3afcbf
translation_model: draft
translation_run: vi-draft-2026-10-31
translation_quality: draft
---

⟦folio 22⟧

3. Kerimov

Làm thế nào để tìm thấy toàn bộ gốc?

Giả sử chúng ta cần giải phương trình
$$a_0x^n + a_1x^{n-1} + \dots + a_{n-1}x + a_n = 0.$$ (1)

Nếu $n = 1$ hoặc $n = 2$, chúng ta có thể làm được - có công thức trong sách giáo khoa ở trường. Nếu $n = 3$ hoặc $n = 4$ thì các công thức tương tự đều tồn tại («Kvant», 1976, Số 9), tuy nhiên, chúng khá cồng kềnh. Nếu $n > 4$, thì những công thức như vậy đơn giản là không tồn tại - không phải “không tìm thấy”, nhưng người ta đã chứng minh rằng chúng không tồn tại («Kvant», 1976, Số 5, trang 6). Làm thế nào điều này có thể được? Làm thế nào tìm được gốc của phương trình “quyền hạn cao hơn”?

Để tìm nghiệm nguyên của một phương trình có hệ số nguyên*), bạn có thể sử dụng điều kiện đủ sau: nếu $l$ là nghiệm nguyên của phương trình (1) có hệ số nguyên thì $l$ là ước số của celene tự do $a_n$.

Thật vậy, nếu $l$ là nghiệm của phương trình (1), thì
$$a_n = l(-a_0l^{n-1}-a_1l^{n-2}-\dots-a_{n-1}).$$ (2)

Nếu $l \in \mathbb{Z}$ và các hệ số $a_0,a_1,\dots,a_{n-1}$, $a_n$ cũng là số nguyên thì $-a_0l^{n-1}-a_1l^{n-2}-\dots-a_{n-1} \in \mathbb{Z}$ và (2) có nghĩa là $a_n$ chia hết cho $l^{**}$).

Vì vậy, nếu chúng ta nhìn vào mọi thứ - tích cực và tiêu cực! là các ước của số $a_n$ và chúng ta sẽ kiểm tra từng số đó xem nó có phải là nghiệm hay không; chúng ta sẽ tìm (nếu có!) tất cả các nghiệm nguyên.

*) Tuy nhiên, một phương trình có hệ số hữu tỉ có thể dễ dàng được thay thế bằng một phương trình tương đương có hệ số nguyên. Làm sao?

**) Khái niệm “số chia” và “số chia” được xác định cho số nguyên.

Ví dụ 1. Số hạng tự do của phương trình
$$3x^3+5x^2+x-46=0$$ (3)

các ước số sau: ±1, ±2, ±23, ±46. Bằng cách kiểm tra các ước “nhỏ” (±1, ±2), chúng ta thấy rằng 2 là nghiệm của phương trình (3). Hơn nữa, người ta có thể kiểm tra các ước số “lớn” (tuy nhiên, đối với phương trình cụ thể này, không cần tính toán đầy đủ, rất dễ thấy rằng không có số ±23, ±46 nào là nghiệm), nhưng như người ta nói, sẽ dễ dàng hơn để hạ thấp bậc của phương trình bằng cách sử dụng một mệnh đề dễ chứng minh: số $l$ nếu và chỉ khi đó là nghiệm của đa thức $f(x)$ khi $f(x)$ chia hết cho $x-l^*$): Vì 2 là nghiệm của phương trình (3) nên đa thức $3x^3+5x^2+x-46$ chia hết cho $x-2$. Hãy tìm thương số.

$$\frac{3x^3+5x^2+x-46}{3x^3-6x^2} = \frac{x-2}{3x^2+11x+23}$$

Vì vậy, $3x^3+5x^2+x-46 = (x-2)(3x^2+11x+23)$. Điều này có nghĩa là cùng với phương trình bậc ba (3), giờ đây chúng ta có thể giải phương trình bậc hai $3x^2+11x+23 = 0$. Phương trình cuối cùng này không có nghiệm (thực). Điều này có nghĩa là phương trình (3) có một nghiệm 2.

Ví dụ 2. Số hạng tự do của phương trình
$$x^4-17x^3+77x^2-85x+360=0$$ (4)

có rất nhiều ước số: ±1, ±2, ±3, ±4, ±5, ±6, ±8, ±9, ±10, ±12, ±15, ±18, ±20, ±24, ±30, ±36, ±40, ±45, ±60, ±72, ±90, ±120, ±180, ±360. Thay thế tất cả chúng ở vế trái của phương trình không phải là một công việc đáng làm. Đúng, rõ ràng là phương trình này không thể có nghiệm âm, nhưng vẫn sẽ còn lại 24 ước số.

Chúng ta hãy sử dụng cách khái quát hóa sau đây từ phát biểu trên về các nghiệm nguyên: nếu $l$ là một nghiệm nguyên của phương trình (1) với các hệ số nguyên, thì với mọi $m \in \mathbb{Z}$ sự khác biệt $m-l$ là ước của một số $f(m)$ (ở đây qua $f(x)$ được đánh dấu bằng nhiều

*) Xem bài viết của S. Ashmanov “Số và đa thức”, tr. 17.
