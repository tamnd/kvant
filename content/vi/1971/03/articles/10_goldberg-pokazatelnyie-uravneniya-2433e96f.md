---
id: 1971-3-goldberg-pokazatelnyie-uravneniya-2433e96f
issue: kvant_1971_3
year: 1971
number: "3"
title: Phương trình mũ
authors:
  - Гольдберг В. В.
rubric: praktikum-abiturienta
rubric_sub: Практикум абитуриента
page_first: 42
page_last: 46
page_labels: 40, 42, 44
tag: CXZ5
lang: vi
source: kvant_digital
extraction: vision
content_sha256: 6810cb3e6ecf943b5cbb9bf3c82e8d50cf32fd23d49bcd1c56e5f69aa335e644
prompt_sha256: 3ec6b8aabd9b98576af76503cd8a2902b9f5d18e01ee867dfb1228f59c6d52d8
translated_from: content/ru/1971/03/articles/10_goldberg-pokazatelnyie-uravneniya-2433e96f.md
source_content_sha256: 5b2b526b7d2b78203652fcd32e22df10f73482e630b32ccf6a1a6a8ebcaf5cfb
translation_model: gpt-5.6-terra
translation_run: vi-codex-2026-10-31
---

⟦folio 40⟧

Phương trình mũ thường được gọi là những phương trình mà trong đó đại lượng chưa biết nằm ở số mũ (còn cơ số của lũy thừa không chứa nó).

Việc giải phương trình mũ dựa trên tính chất sau của lũy thừa:

nếu hai lũy thừa có cùng một cơ số dương và khác một bằng nhau, thì các số mũ của chúng cũng bằng nhau.

Theo tính chất này, phương trình mũ đơn giản nhất

$$a^x = b \quad (a > 0, a \neq 1, b > 0)$$

được giải như sau:

$$a^x = a^{\log_a b}, \quad x = \log_a b.$$

Khó khăn khi giải phương trình mũ thường là phải biết nhận ra cơ số chung của vế trái và vế phải của phương trình. Nếu trong phương trình

$$\left(\frac{4}{9}\right)^x \cdot \left(\frac{27}{8}\right)^{x-1} = \frac{2}{3}$$

cơ số chung $\frac{2}{3}$ (hoặc $\frac{3}{2}$) của vế trái và vế phải hiện ra ngay, thì trong phương trình

$$(0,4)^{x-1} = (6,25)^{6x-5}$$

để tìm cơ số chung $\frac{2}{5}$ (hoặc $\frac{5}{2}$) cần trước hết đổi các phân số thập phân thành phân số thường. (Hãy giải đến cùng các ví dụ đã nêu; trong phương trình (1) bạn sẽ nhận được đáp số $x=2$, còn trong phương trình (2) là $x = \frac{11}{13}$.)

Để đưa nhiều phương trình mũ về dạng đơn giản nhất, công thức sau thường hữu ích:

$$a^p \cdot b^p = (ab)^p.$$

Ví dụ 1. Giải phương trình

$$\sqrt{3^x} \cdot \sqrt{5^x} = 225.$$

Lời giải. Viết phương trình dưới dạng

$$3^x \cdot 5^x = 225.$$

Dùng công thức (3), ta được

$$15^x = 15^2,$$

suy ra $x=4$.

Ví dụ 2. Giải phương trình

$$2^3x \cdot 5^x = 1600.$$

Lời giải e. Ta có chuỗi các phương trình tương đương sau:

$$(2^3)x \cdot 5^x = 1600, \quad 8^x \cdot 5^x = 1600, \quad 40^x = 40^2, \quad x=2.$$

Dễ đưa phương trình dạng

$$a^{\varphi(x)} = 1 \quad (a > 0, a \neq 1).$$

về phương trình đơn giản nhất.

Để làm điều đó, chỉ cần biểu diễn đơn vị dưới dạng $a$ lũy thừa không: $1 = a^0$.

Ví dụ 3. Giải phương trình

$$5^{x^2+x-2} = 1.$$

Lời giải e. Lần lượt ta được

$$5^{x^2+x-2} = 5^0, \quad x^2+x-2=0, \quad x_1=-2, \quad x_2=1.$$

⟦folio 42⟧

Ví dụ 9. Giải phương trình
$$3 \cdot 16^x + 36^x = 2 \cdot 81^x.$$
Lời giải. Ta thấy rằng trong phương trình này các cơ số 16, 36, 81 lập thành một cấp số nhân và được nâng lên cùng một lũy thừa $x$. Để giải, chia cả hai vế của phương trình cho $81^x$. Ta được
$$3 \cdot \left(\frac{4}{9}\right)^{2x} + \left(\frac{4}{9}\right)^x = 2.$$
Đặt $\left(\frac{4}{9}\right)^x$ bằng $y$, ta đưa về phương trình bậc hai $3y^2 + y - 2 = 0$ có các nghiệm $y_1 = -1, y_2 = \frac{2}{3}$. Xét hai trường hợp:
a) $\left(\frac{4}{9}\right)^x = -1$ (không có nghiệm);
b) $\left(\frac{4}{9}\right)^x = \frac{2}{3}, \left(\frac{2}{3}\right)^{2x} = \left(\frac{2}{3}\right)^1, 2x = 1, x = \frac{1}{2}$.
Ví dụ 10. Giải phương trình
$$27^x + 12^x = 2 \cdot 8^x.$$
Phương trình này gần với phương trình vừa xét: số mũ của các cơ số là như nhau, nhưng các cơ số 27, 12 và 8 không lập thành một cấp số nhân. Các số 27, 18, 12 và 8 lập thành một cấp số nhân — ta có thể coi rằng hạng chứa $18^x$ đi vào phương trình với hệ số bằng không.

Lời giải. Chia tất cả các hạng tử cho $8^x$, ta được
$$\left(\frac{3}{2}\right)^{3x} + \left(\frac{3}{2}\right)^x = 2.$$
Đặt $\left(\frac{3}{2}\right)^x$ là $y$, ta đi đến phương trình bậc ba
$$y^3 + y - 2 = 0,$$
mà vế trái của nó dễ dàng phân tích thành nhân tử:
$$(y^3 - 1) + (y - 1) = 0,$$
$$(y - 1)(y^2 + y + 2) = 0.$$

Nghiệm thực duy nhất của phương trình này $y = 1$ dẫn đến phương trình $\left(\frac{3}{2}\right)^x = 1$, từ đó tìm được $x = 0$.

Ví dụ 11. Giải phương trình
$$5 \cdot 2^{3x - 3} - 3 \cdot 2^{5 - 3x} + 7 = 0.$$
Giải. Viết lại phương trình dưới dạng
$$\frac{5}{8} \cdot 2^{3x} - \frac{96}{2^{3x}} + 7 = 0.$$
Đặt $2^{3x}$ là $y$, khi đó được:
$$\frac{5}{8} y - \frac{96}{y} + 7 = 0,$$
$$5y^2 + 56y - 768 = 0,$$
$$y_1 = -19,2; y_2 = 8.$$
a) $2^{3x} = -19,2$ — phương trình không có nghiệm.
b) $2^{3x} = 8, 2^{3x} = 2^3, 3x = 3, x = 1.$
Trong ví dụ đã xét, tích các cơ số bằng một, và điều này lập tức dễ thấy; trong ví dụ tiếp theo, không dễ nhận ra sự thật này *).

Ví dụ 12. Giải phương trình
$$\left(\sqrt{5 + 2\sqrt{6}}\right)^x + \left(\sqrt{5 - 2\sqrt{6}}\right)^x = 10.$$
Lời giải. Nhân các cơ số:
$$\sqrt{5 + 2\sqrt{6}} \cdot \sqrt{5 - 2\sqrt{6}} = \sqrt{25 - 24} = 1.$$
Nếu ký hiệu $\left(\sqrt{5 + 2\sqrt{6}}\right)^x$ là $y$, thì $\left(\sqrt{5 - 2\sqrt{6}}\right)^x = \frac{1}{\left(\sqrt{5 + 2\sqrt{6}}\right)^x} = \frac{1}{y}$. Do đó
*) Lưu ý rằng các phương trình được xét trong các ví dụ 11 và 12 có thể xếp vào cùng kiểu với các phương trình ở ví dụ 9 và 10: các cơ số của lũy thừa trong đó là 2, 1, $\frac{1}{2}$ và $\sqrt{5 + 2\sqrt{6}}$, 1, $\sqrt{5 - 2\sqrt{6}}$ lập thành một cấp số nhân và được nâng lên cùng một lũy thừa phụ thuộc vào $x$.

⟦folio 44⟧

4. $4^x - 3^{x-\frac{1}{2}} = 3^{x+\frac{1}{2}} - 2^{2x-1}$.
5. $3 \cdot 2^x + 2 \cdot 3^x = 2^{x+3} + 3^{x-2}$.
6. $9^x - 2^{x+\frac{1}{2}} = 2^{x+\frac{7}{2}} - 3^{2x-1}$.
7. $3^{x+1} + 3^{x-1} + 3^{x-2} = 5^x + 5^{x-1} + 5^{x-2}$.
8. $9^{x-1} + 3^x = 2 \cdot 3^1, 5^x$.
9. $4^x + \sqrt{x^2-2} - 5 \cdot 2^{x-1} + \sqrt{x^2-2} = 6$.
10. $8^x + 18^x = 2 \cdot 27^x$.
11. $3^{1-x} - 3^{1+x} + 9^x + 9^{-x} = 6$.
12. $\sqrt[x]{\left(\frac{2}{3}\right)^3} - \sqrt[x]{\left(\frac{3}{2}\right)^3} - \sqrt[x]{\frac{2}{3}} + \sqrt[x]{\frac{3}{2}} = 3$.
13. $6 \sqrt[x]{9} - 13 \sqrt[x]{6} + 6 \sqrt[x]{4} = 0$.
14. $4^x = 2 \cdot 14^x + 3 \cdot 49^x$.
15. $(\sqrt{a + \sqrt{a^2-1}})^x + (\sqrt{a - \sqrt{a^2-1}})^x = 2a$ ($a > 1$).

Hãy kiểm tra rằng phương trình ở bài 12 nhận được từ phương trình này khi $a = 5$. Hãy viết phương trình này có dạng nào khi $a = \sqrt{2}, \sqrt{3}, 2, 3, 4, 6$.

16. $2^x - 3^{\frac{x}{2}} = 1$.
17. $(\sin 1)^x + (\cos 1)^x = 1$.
18. $3^{x-1} + 5^{x-1} = 34$.
19. $5^{\sqrt{x}} + 12^{\sqrt{x}} = 13^{\sqrt{x}}$.
20. $10^{x^2} = 2 \cdot 100^x$.
21. $2^{x+3} - 3^{x^2} - 2 = 3^{x^2} + 1 - 2^{x-1}$.
22. $3^{x^2} + 4^{x^2} = 5^{x^2}$.
23. $x^{\sqrt{x}} = (\sqrt{x})^x$.
24. $x^{\sqrt{x^2}} = (\sqrt{x})^x$.
25. $8^x + 9 \cdot 2^{x+2} = 208$.

(Xem phần đầu ở tr. 31.)

Bước quan trọng tiếp theo trong việc hoàn thiện nam châm điện được nhà vật lí Mỹ Joseph Henry thực hiện vào năm 1827. Ông là người đầu tiên quấn trên lõi sắt không phải một mà nhiều lớp dây, còn các vòng dây thì được xếp sát nhau. Có lẽ những người khác cũng đã nghĩ tới điều này, nhưng khi ấy chưa có dây phủ chất cách điện. Chính Henry là người đầu tiên chế tạo loại dây như vậy. Khi ấy, và dĩ nhiên còn rất lâu sau đó, dây có cách điện không được bán. Theo lời kể của cộng sự của Henry, người phát minh điện tín F. Morse, ngay cả năm 1837, chỉ có ... những người làm mũ mới dùng dây không trần để làm khung mũ phụ nữ. Henry tự chế tạo dây phủ cách điện. Làm vật liệu cách điện, ông dùng những dải lụa cắt từ ... y phục của vợ ông (thời ấy phụ nữ mặc trang phục dài và phồng). Như vậy lần đầu tiên dây cách điện đã xuất hiện và được sử dụng. Xét theo những nam châm điện của Henry còn được lưu giữ trong bảo tàng, ông đã phải quấn các dải lụa lên nhiều kilômét dây. Nhưng ngay từ năm 1831, ông đã có thể báo rằng nam châm điện lớn nhất của mình có thể giữ được một vật nặng 930 kilôgam!
