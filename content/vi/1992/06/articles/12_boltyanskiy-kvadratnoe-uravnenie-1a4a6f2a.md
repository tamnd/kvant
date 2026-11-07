---
id: 1992-6-boltyanskiy-kvadratnoe-uravnenie-1a4a6f2a
issue: kvant_1992_6
year: 1992
number: "6"
title: phương trình bậc hai
authors:
  - Болтянский В. Г.
rubric: shkola-v-kvante
rubric_sub: Школа в «Кванте»
page_first: 46
page_last: 49
page_labels: 44-47
lang: vi
source: kvant_digital
extraction: vision
content_sha256: 0e6ce4f47fe07b72fbd5d1be073ccceb4106533e347ec49ebeba1fa5a4a7c97d
prompt_sha256: draft-1
translated_from: content/ru/1992/06/articles/12_boltyanskiy-kvadratnoe-uravnenie-1a4a6f2a.md
source_content_sha256: 63ad0487842f61dcc3e7aef133574c99b22981e2f615edf1bf3171f50fc45a6d
translation_model: draft
translation_run: vi-draft-gaps-2026-11-07
translation_quality: draft
---

⟦folio 44⟧

---
running_head:
folio:
---

Quảng trường
phương trình
Tiến sĩ Khoa học Vật lý và Toán học
V. BOLTYANSKY

Trước hết ta nhắc lại cách giải phương trình bậc hai
$$x^2 + px + q = 0$$
(1)

với hệ số thực $p, q$. Nó có thể được viết lại dưới dạng
$$\left(x + \frac{p}{2}\right)^2 = \frac{1}{4}\left(p^2 - 4q\right)$$
(2)

(điều này có thể dễ dàng kiểm tra bằng cách mở dấu ngoặc đơn). Số $p^2 - 4q$ được gọi là phân biệt của phương trình (1) và được ký hiệu là $D$. Do đó phương trình trở thành
$$\left(x + \frac{p}{2}\right)^2 = \frac{1}{4}D.$$
(3)

Bây giờ rõ ràng là nếu số $D$ không âm

Do đó, phương trình (1) có hai nghiệm thực
$$x_1 = \frac{1}{2}(-p + \sqrt{D}), \quad x_2 = \frac{1}{2}(-p - \sqrt{D}),$$
(4)

Hơn nữa, các nghiệm này khác nhau đối với $D > 0$ và trùng khớp trong trường hợp $D = 0$.

Nếu $D$ âm, thì phương trình (3) và sau đó (1), không có nghiệm thực, vì không có số thực $x$ nên vế trái trong (3) có thể là số âm. Trong trường hợp này, phương trình (3) có thể được viết lại thành
$$\left(x + \frac{p}{2}\right)^2 - \frac{1}{4}(\sqrt{-Di})^2 = 0,$$
(5)

trong đó $i$ là đơn vị tối thiểu, tức là $i^2 = -1^*$. Bây giờ, phân tích vế trái ra nhân tử, chúng ta có được
$$\left(x + \frac{p}{2} - \frac{1}{2}\sqrt{-Di}\right) \times \left(x + \frac{p}{2} + \frac{1}{2}\sqrt{-Di}\right) = 0,$$

*) Về số phức, xem bài viết của Yu. Solovyov ở «Kvant» số 7 năm 1991.

⟦folio 45⟧

---
running_head:
folio:
---

$$x_1 = \frac{1}{2} (-p + \sqrt{-Di}),$$
$$x_2 = \frac{1}{2} (-p - \sqrt{-Di}).$$

Như vậy, điều sau đây là đúng

Định lý 1. Phương trình bậc hai (1) với hệ số thực $p, q$ có hai nghiệm, dạng của phương trình này phụ thuộc vào giá trị của phân biệt $D = p^2 - 4q$. Đối với $D > 0$ gốc của thực và khác nhau (xem (4)), đối với $D = 0$ chúng là thực và trùng nhau, và đối với $D < 0$ chúng là các biến chứng (xem (6)).

Định lý sau đây được đưa ra bởi nhà toán học Trung Quốc François Viète (1540–1603), một trong những người sáng lập ký hiệu chữ cái và biểu tượng đại số hiện đại.

Định lý 2 (Việt). Các nghiệm $x_1$ và $x_2$ của phương trình bậc hai (1) thỏa mãn hệ thức
$$x_1 + x_2 = -p, \quad x_1 x_2 = q.$$

Thật vậy, trong trường hợp nghiệm thực (tức là đối với $D$ không âm), chúng ta tìm thấy từ công thức (4):

$$x_1 + x_2 = \frac{1}{2} (-p + \sqrt{D}) + \frac{1}{2} (-p - \sqrt{D}) = -p,$$
$$x_1 x_2 = \frac{1}{4} (-p + \sqrt{D}) (-p - \sqrt{D}) = \frac{1}{4} (p^2 - D) = q.$$

Trong trường hợp nghiệm phức (tức là đối với $D < 0$), công thức Vieta (7) cũng thu được tương tự từ (6).

Định lý 3. Bất kỳ tam thức bình phương nào cũng có thể phân tích thành thừa số tuyến tính:
$$x^2 + px + q = (x - x_1)(x - x_2),$$
$x_1$ và $x_2$ của nó là nghiệm của phương trình bậc hai (1).

Trên thực tế, công thức của Vieta
$$x^2 + px + q = x^2 - (x_1 + x_2)x + x_1 x_2 = (x - x_1)(x - x_2).$$

Đôi khi, khi phân tích nhân tử, sẽ thuận tiện hơn nếu tách bình phương hoàn chỉnh (xem (2)) và tìm nghiệm của phương trình bằng công thức (4) hoặc (6). Ví dụ,
$$x^2 + 8x - 33 = (x + 4)^2 - 49,$$
từ đó chúng tôi tìm thấy sự mở rộng cần thiết
$$x^2 + 8x - 33 = (x - 3)(x + 11).$$

Cũng lưu ý rằng $\frac{1}{4} D = \left(\frac{p}{2}\right)^2 - q$ và $\frac{1}{2} \sqrt{D} = \sqrt{\left(\frac{p}{2}\right)^2 - q}$. Những công thức này sẽ thuận tiện hơn khi sử dụng nếu $p$ chẵn.

Bài tập
1. Chứng minh rằng phân biệt $D$ của phương trình bậc hai $x^2 + px + q = 0$ bằng $(x_1 - x_2)^2$, trong đó $x_1, x_2$ là nghiệm của phương trình này.
2. Kiểm tra bằng cách thay thế để đảm bảo rằng các số được chỉ ra trong (4) là nghiệm của phương trình (1) tại $D \geq 0$. Đồng thời kiểm tra xem $D < 0$ các số (6) có phải là nghiệm của phương trình này không.
3. Giải các phương trình bậc hai sau
a) $x^2 - 5 = 0$; 6) $x^2 + 7 = 0$;
b) $x^2 + 3x = 0$; 7) $x^2 - 7x + 12 = 0$;
d) $x^2 - x - 30 = 0$; e) $x^2 + 4x + 5 = 0$;
jk) $x^2 + 10x + 25 = 0$;
h) $x^2 + 2(a - 1)x - (6a + 3) = 0$;
i) $x^2 + 2(a + 3)x + (a^2 + 2a + 9) = 0$;
k) $x^2 - 2(a^2 - 1)x + (a^4 - a^2 + 1) = 0$;
l) $2x^2 - 5x + 2 = 0$;

⟦folio 46⟧

---
running_head:
folio:
---

(1+a)x²+2x√a²+1-(1-a)=0.

4. Chứng minh rằng với $D>0$ đồ thị của tam giác vuông $y=x^2+px+q$ cắt trục x tại hai điểm $(x_1; 0), (x_2; 0)$, trong đó $x_1, x_2$ là nghiệm của phương trình $x^2+px+q=0$ (hình 1). Tại $D=0$ đồ thị chạm vào trục x (hình 2). Cuối cùng, tại $D<0$ đồ thị không có điểm chung với trục x mà nằm ở vị trí cao hơn (hình 3).

5. Viết phương trình bậc hai với các nghiệm sau:

a) $x_1=1, x_2=-2$;
b) $x_1=2-3i, x_2=2+3i$;
g) $x_1=a+bi, x_2=a-bi$;
d) $x_1=3-4i, x_2=2-5i$.

6. Chứng minh rằng với mọi $p, q$ hệ phương trình
$$\begin{cases} y+z=-p, \\ yz=q \end{cases}$$

có hai lời giải:
$y=x_1, z=x_2; y=x_2, z=x_1$

(thực hoặc phức, khác nhau hoặc trùng khớp), trong đó $x_1, x_2$ là nghiệm của phương trình bậc hai $x^2+px+q=0$.

7. Chứng minh rằng đồ thị của tam giác vuông $y=x^2+px+q$ đối xứng qua đường thẳng $x=-\frac{p}{2}$ (hình 4).

8. Chứng minh rằng nghiệm của phương trình bậc hai $x^2+px+q=0$ (với hệ số thực $p, q$) là số thực và dương khi và chỉ khi các điều kiện được đáp ứng.

$D \geqslant 0, p<0, q>0$.

9. Tìm điều kiện cần và đủ để nghiệm của phương trình bậc hai $x^2+px+q=0$ (có hệ số thực $p, q$) là số thực, khác 0 và có a) cùng dấu, b) khác dấu.

10. Chứng minh rằng nếu một nghiệm của phương trình $x^2+px+q=0$ (với hệ số thực $p, q$) là thực thì nghiệm thứ hai là thực.

11. Chứng minh rằng nếu một nghiệm của phương trình $x^2+px+q=0$ (với số thực $p, q$) không phải là số thực, tức là nó có dạng $a+bi$, trong đó $b \neq 0$, thì nghiệm thứ hai của phương trình này là $a-bi$, tức là nó cũng không phải là số thực.

12. Các số $p$ và $q$ là hợp lệ. Tìm (dựa vào giá trị của $D$) tập hợp tất cả các số thực $x$ thỏa mãn $x^2+px+q<0$.

Hình 6.

Hình 7.

⟦folio 47⟧

---
running_head:
folio:
---

13. Giải các bất đẳng thức bậc hai nghiêm ngặt sau đây (và vẽ hình):
a) $x^2 - 5x + 6 < 0$; 6) $x^2 - 10x + 25 > 0$;
b) $x^2 - x - 12 > 0$; 7) $x^2 - 12x + 38 > 0$.

14. Giải các bất đẳng thức bậc hai lỏng lẻo sau:
a) $x - 3x - 18 \leq 0$; 6) $x^2 - 8x + 16 \leq 0$;
b) $x^2 + 6x + 5 \geq 0$; 7) $x^2 - 14x + 50 \leq 0$.

15. Chứng minh rằng nếu nghiệm của cả hai phương trình bậc hai
$$x^2 + p_1x + q_1 = 0$$
$$x^2 + p_2x + q_2 = 0$$
là hợp lệ và nằm trên khoảng $[a; b]$, thì với bất kỳ $k > 0$ nào thì nghiệm của phương trình
$$x^2 + p_1x + q_1 + k(x^2 + p_2x + q_2) = 0$$
(8)
nếu chúng là thật thì chúng nằm trên cùng một đoạn $[a; b]$.

16. Chứng minh rằng nếu nghiệm $x_1, x_2$ của phương trình
$$x^2 + p_1x + q_1 = 0$$ và nghiệm $x_3, x_4$ của phương trình
$$x^2 + p_2x + q_2 = 0$$ là thực và khác nhau (hình 5), tức là $x_1 < x_3 < x_2 < x_4$, thì với bất kỳ $k > 0$ nào thì nghiệm của phương trình (8) là thực và một trong số chúng nằm trên đoạn $[x_1; x_3]$ và cái còn lại nằm trên đoạn $[x_2; x_4]$.

17. Chứng minh rằng nếu các nghiệm $x_1, x_2$ của phương trình $x^2 + p_1x + q_1 = 0$ và các nghiệm $x_3, x_4$ của phương trình $x^2 + p_2x + q_2 = 0$ là số thực và biến (hình 5), thì với mọi âm $k$ khác với -1, các nghiệm của phương trình (8) là số thực và một trong số chúng nằm trên đoạn $[x_3; x_2]$, còn nghiệm kia nằm bên ngoài đoạn $[x_1; x_4]$.

18. Đối với $a$ thì phương trình $x^2 + ax + 6 = 0$ có nghiệm nguyên?

19. Đối với $a$ thì phương trình $(x - 10)(x - a) + 1 = 0$ có nghiệm nguyên?

20. Hãy chỉ ra dấu của các số $p$ và $q$ nếu đồ thị của tam giác vuông $y = x^2 + px + q$ có ​​dạng trỏ tới hình 6.

21. Đặt $x_1, x_2$ là nghiệm của phương trình bậc hai $x^2 + px + q = 0$. Tìm $p$ và $q$ nếu biết rằng $x_1 + 1$ và $x_2 + 1$ là nghiệm của phương trình
$$x^2 - p^2x + pq = 0.$$

22. Dựa trên nghiên cứu, điểm là $A$, và dựa trên các sắc lệnh, điểm là $B$ (cả hai điểm đều khác với điểm gốc). Chứng minh rằng tồn tại duy nhất một tam giác vuông $y = x^2 + px + q$ có ​​đồ thị đi qua cả hai điểm $A, B$ (hình 7).

23. Với những giá trị thực nào thì $a$ tam giác vuông $y = x^2 + 2ax + 1$ dương đối với mọi số thực $x$?

24. Phương trình $x^2 + p_1x + q_1 = 0$ và $x^2 + p_2x + q_2 = 0$ có hệ số thực, với $p_1p_2 = 2(q_1 + q_2)$. Chứng minh rằng ít nhất một trong các phương trình này có nghiệm thực.

25. Xét đa thức $f(x, y) = ax^2 + bxy + cy^2$ với các hệ số thực $a > 0, b, c$. Chứng minh rằng một trong các khẳng định sau là đúng:
a $f(x, y) = a(x - m_1y)(x - m_2y)$,
trong đó $m_1 \neq m_2$ là số thực (đa thức eunep-bolius);
b $f(x, y) > 0$ với mọi $x, y$ thực ngoại trừ $x = y = 0$ (đa thức elip).

26. Chứng minh đồ thị là tam giác $y =$
$$x^2 + p_1x + q_1 = 0$$ và nghiệm $x_3, x_4$ của phương trình $x^2 + p_2x + q_2 = 0$ là số thực và thay đổi (hình 5), tức là $x_1 < x_3 < x_2 < x_4$, thì với bất kỳ $k > 0$ nào, nghiệm của phương trình (8) là thực và một trong số chúng nằm trên đoạn $[x_1; x_3]$, còn nghiệm kia nằm bên ngoài đoạn $[x_1; x_4]$.

Hình 9.
a) 6)
b) 6)

Hình 10.
= $x^2 + px + q$ thu được từ đồ thị $y = x^2$ bằng cách truyền song song (hình 8) sang vectơ $a = (-p/2; -D/4)$.

27. Chứng minh rằng hệ phương trình
$$\begin{cases} y = x^2 + px + q, \\ y = ax + b \end{cases}$$

với bất kỳ $a, b$ nào có tối đa hai lời giải (hình 9).

28. Chứng minh rằng vùng bên trong của parabol $y = x^2 + px + q$, tức là tập hợp tất cả các điểm $(x, y)$ mà $y > x^2 + px + q$, là lồi (điều này có nghĩa là, cùng với hai điểm, nó cũng chứa toàn bộ đoạn nối chúng (hình 10).
