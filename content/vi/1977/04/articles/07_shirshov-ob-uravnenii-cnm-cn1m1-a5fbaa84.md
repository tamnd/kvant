---
id: 1977-4-shirshov-ob-uravnenii-cnm-cn1m1-a5fbaa84
issue: kvant_1977_4
year: 1977
number: "4"
title: Về phương trình C_n^m = C_n+1^m-1
authors:
  - Ширшов А. И.
rubric: osnovnye-stati
page_first: 23
page_last: 24
page_labels: 21-22
tag: XJIO
lang: vi
source: kvant_digital
extraction: vision
content_sha256: 7e2ba978bb9c53aff2c181d62b949accdbb8bd26127e942a6c9479a4d01247d8
prompt_sha256: draft-1
translated_from: content/ru/1977/04/articles/07_shirshov-ob-uravnenii-cnm-cn1m1-a5fbaa84.md
source_content_sha256: 5e62f3bf2a8f73fcf648302c7e5d545f6df3f4c43868fee98ba718aaeb5c433c
translation_model: draft
translation_run: vi-draft-2026-10-31
translation_quality: draft
---

⟦folio 21⟧

Về phương trình
$$C_n^m = C_{n+1}^{m-1}$$

A. Shirshov

Tôi đi đến phương trình nêu trong tiêu đề bằng cách xét đường thứ 14 của tam giác Pascal:
1, 14, 91, 364, 1001, 2002, 3003, 3432, 3003, 2002, 1001, 364, 91, 14, 1.

Tam giác Pascal được thảo luận ở đoạn 7 và 8 của sách giáo khoa “Đại số và Giải tích cơ bản 9”.

Hãy nói ngắn gọn về anh ấy cho những ai chưa biết về anh ấy.

Trong hàng thứ n của tam giác Pascal, ở vị trí m-m có số $C_n^m$, việc đánh số cả dòng và số trong mỗi dòng bắt đầu từ 0 (15 dòng đầu tiên của tam giác Pascal được hiển thị trong hình).

Để hiểu bài viết, chỉ cần biết một điều về các con số $C_n^m$ là đủ:
$$C_n^m = \frac{n!}{m!(n-m)!}$$

($n! = 1 \cdot 2 \cdot \dots \cdot n; 0! = 1$). Từ (1) dễ dàng suy ra
$$C_n^m + C_{n+1}^{m+1} = C_{n+1}^{m+1}.$$

Bằng cách sử dụng sự tương ứng này, bạn có thể dựng tam giác Pascal mà không cần sử dụng công thức (1) (xem hình).

Ở dòng thứ 14, đáng chú ý là 1001+2002=3003, tức là
$$C_{14}^4 + C_{14}^5 = C_{14}^6.$$

Theo quan điểm (2), đẳng thức này có thể được viết lại như sau:
$$C_{15}^5 = C_{14}^6.$$

Đẳng thức (3) cho thấy cặp (6, 14) là nghiệm của phương trình nêu ở tiêu đề.

Những cặp số nào khác là nghiệm của phương trình này? Bài báo cho đáp số cho câu hỏi này. Để làm cho đáp số có dạng đẹp hơn, chúng ta thay m trong phương trình bằng y và n bằng x-1. Khi đó định lý sau là đúng. Tất cả các phương trình lời giải $C_x^{y-1} = C_x^{-1}$ đều có dạng
$$x_k = \gamma_{2k} \gamma_{2k+1}; \quad y_k = \gamma_{2k-1} \gamma_{2k}, \quad k = 1, 2, 3, \dots, \text{еде } \gamma_n - n-\text{й член последовательности Фибоначчи}^*): 1, 1, 2, 3, 5, 8, 13, 21, 34, \dots$$

Bằng chứng.
1. Hãy sử dụng công thức (1) và viết lại phương trình của chúng ta:
$$\frac{x!}{(y-1)!(x-y+1)!} = \frac{(x-1)!}{y!(x-y-1)!}.$$

Sau khi biến đổi rõ ràng, nó được rút gọn về dạng sau:
$$(x-y+1)(x-y)=xy.$$

Hãy ký hiệu w là ước số chung nhất của các số x và y. Khi đó x=uw, y=vw, trong đó u và v là nguyên tố cùng nhau. Thay các biểu thức của x và y vào (4), sau khi triệt tiêu bằng w, ta thu được $(u-v)[(u-v)w+1]=uvw.$

Các số u và v là nguyên tố cùng nhau. Do đó u-v và uv cũng nguyên tố cùng nhau. Các số w và $(u-v)w+1$ cũng nguyên tố lẫn nhau. Nhưng khi đó các đẳng thức sau phải đúng:
$$\begin{cases} (u-v)w+1=uv, \\ u-v=w. \end{cases}$$

*) Đối với dãy này $\gamma_n = \gamma_{n-1} + \gamma_{n-2}$ với n > 2.

⟦folio 22⟧

Hệ thống này tương đương với hệ thống sau:

$$\begin{cases} v^2 + vw - w^2 = 1, \\ v + w = u. \end{cases}$$

Do đó, lời giải của phương trình của chúng tôi trùng với lời giải của phương trình

$$v^2 + vw - w^2 = 1$$

bằng số tự nhiên.

2. Chúng ta hãy thực hiện ba thay đổi đơn giản về lời giải của phương trình (7). Giả sử cặp $\langle v, w \rangle$ là nghiệm của phương trình (7). Sau đó

a) $v$ và $w$ là nguyên tố cùng nhau;
b) nếu $v = w$ thì $v = w = 1$;
c) $v \leq w < 2v$;
d) cặp $\langle v + w, v + 2w \rangle$ và $\langle 2v - w, w - v \rangle$ là nghiệm của phương trình.

Hãy nhớ rằng $v$ và $w$ là các số tự nhiên.

c) suy ra từ đẳng thức $w = \frac{v + \sqrt{5v^2 - 4}}{2}$, thu được nếu (7) được coi là một phương trình của $w$, và d) có thể được kiểm chứng bằng cách thay các cặp tương ứng vào phương trình (7).

Sử dụng phép biến đổi

$$\langle v, w \rangle \Rightarrow \langle v + w, v + 2w \rangle,$$

Dựa trên lời giải $\langle 1, 1 \rangle$, chúng ta xây dựng chuỗi lời giải $\langle 2, 3 \rangle, \langle 5, 8 \rangle, \langle 13, 21 \rangle, \langle 34, 55 \rangle, \dots$.

Chữ viết ra lời giải trông giống như

$$v_h = \gamma_{2h-1}, w_h = \gamma_{2h}.$$

Hãy chứng minh rằng phương trình (7) không có lời giải nào khác. Giả sử rằng cặp $\langle v, w \rangle$ là nghiệm của phương trình (7). Hãy chứng minh rằng nó là một trong các cặp (8).
