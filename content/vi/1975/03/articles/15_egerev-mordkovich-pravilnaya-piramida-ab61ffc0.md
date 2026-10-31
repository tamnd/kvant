---
id: 1975-3-egerev-mordkovich-pravilnaya-piramida-ab61ffc0
issue: kvant_1975_3
year: 1975
number: "3"
title: Kim tự tháp đúng
authors:
  - Егерев В. К.
  - Мордкович А. Г.
rubric: praktikum-abiturienta
rubric_sub: Практикум абитуриента
page_first: 63
page_last: 67
page_labels: 61, 62, 64, 65
tag: O49A
lang: vi
source: kvant_digital
extraction: vision
content_sha256: 65f29232fca1ddb3f594ed06395d2c2945a41efccd41d54df4742f2d328e836a
prompt_sha256: draft-1
translated_from: content/ru/1975/03/articles/15_egerev-mordkovich-pravilnaya-piramida-ab61ffc0.md
source_content_sha256: 50f9f644a6aabe83388106292ceeb28b52f6b10a212dbf1a592ac8b51b921242
translation_model: draft
translation_run: vi-draft-2026-10-31
translation_quality: draft
---

⟦folio 61⟧

Thông số chính xác
V. K. Egerev, A. G. Mordkovich

Lời giải Nhiều bài toán hình học có bản chất nhân tạo vốn có, đó là lý do tại sao triết gia người Đức Arthur Schopenhauer, cách đây nhiều thế kỷ, đã chỉ trích hình học vì sử dụng “bằng chứng về bẫy chuột”. Thật vậy, lời giải của hình học bài toán chứa ít mẫu và thường tạo ấn tượng về một tiêu điểm. Điều quan trọng hơn là phải biết rằng kho vũ khí nhỏ gồm các kỹ thuật “tiêu chuẩn” vẫn được sử dụng với lời giải những bài toán này. Một số kỹ thuật đã được thảo luận trên các trang tạp chí của chúng tôi (ví dụ: xem bài viết của I. A. Kushiir “Phương pháp của một phần tử phụ trợ”, «Kvant», 1974, số 2). Bài viết này nói về một kỹ thuật khác như vậy.

2. Mối quan hệ giữa các góc trong một paramid

Hình 1 thể hiện một phần của SABCD..., paramid n-giác đều đặn, SH—chiều cao, SK—tận đồ. Hãy giới thiệu ký hiệu sau:

α - góc giữa cạnh bên và mặt phẳng đáy;
β—góc giữa cạnh bên và mặt phẳng đáy;
γ—góc giữa các gân bên cắt ngang;
φ—góc giữa các mặt bên cắt ngang.

1. "Phương pháp dùng chảo"
Hãy bắt đầu với một dụ ngôn nhỏ. Andrey được giải thích cách luộc trứng: “Lấy chảo ra khỏi đinh, đổ nước vào, cho trứng vào, châm ga, đặt chảo lên bếp gas và lấy ra 5 phút sau khi nước sôi”. Andryusha đã làm đúng như vậy, mọi việc đều diễn ra tốt đẹp. Nhưng một ngày nọ, chúng tôi thức dậy vào buổi sáng, Andrei thấy nước đã được đổ vào chảo và gas đang bốc cháy. Suy nghĩ xong, anh vặn ga, đổ nước rồi treo xoong lên đinh rồi làm theo lời dạy.

Bất chấp mọi hành vi vô lý như vậy, phương pháp trả lại

⟦figure⟧
| góc | Tỷ lệ | | Vùng thay đổi góc | Kết nối giữa các góc |
|---|---|---|---|---|
| α; φ | $\sin \alpha = \mathrm{ctg}\dfrac{\varphi}{2}\,\mathrm{ctg}\dfrac{\pi}{n}$ | (1) | $0 < \alpha < \dfrac{\pi}{2}$ | |
| α; γ | $\cos \alpha = \sin\dfrac{\gamma}{2}\Big/\sin\dfrac{\pi}{n}$ | (2) | $0 < \beta < \dfrac{\pi}{2}$ | $\gamma < \pi - 2\alpha$ |
| α; β | $\mathrm{tg}\,\alpha = \mathrm{tg}\,\beta \cdot \cos\dfrac{\pi}{n}$ | (3) | $0 < \gamma < \dfrac{2\pi}{n}$ | $\alpha < \beta$ |
| β; γ | $\cos \beta = \mathrm{tg}\dfrac{\gamma}{2}\,\mathrm{ctg}\dfrac{\pi}{n}$ | (4) | $\pi - \dfrac{2\pi}{n} < \varphi < \pi$ | |
| β; φ | $\mathrm{tg}\,\beta = \dfrac{\sqrt{2}\cos\dfrac{\varphi}{2}}{\sqrt{-\cos\varphi - \cos\dfrac{2\pi}{n}}}$ | (5) | | $\varphi > \pi - 2\beta$ |
| γ; φ | $\sin\dfrac{\gamma}{2} = \dfrac{\sqrt{-\cos\varphi - \cos\dfrac{2\pi}{n}}}{\sqrt{2}\sin\dfrac{\varphi}{2}}$ | (6) | | |

Nếu một trong những góc này được biết trong một hình chóp đều thì có thể tìm thấy ba góc còn lại. Sáu tỷ lệ được thể hiện trong bảng. Hãy chứng minh một số trong số họ.

(1) (α; φ). Xét các tam giác $LMC$ và $LMD$, ta thu được

$\mathrm{tg}\dfrac{\varphi}{2} = \dfrac{CL}{LM}$, $\sin \alpha = \dfrac{LM}{LD}$. Có nghĩa,

$\mathrm{tg}\dfrac{\varphi}{2}\sin\alpha = \dfrac{CL}{LD} = \mathrm{tg}\,\angle CDL =$

$= \mathrm{tg}\left(\dfrac{\pi}{2} - \dfrac{\pi}{n}\right) = \mathrm{ctg}\dfrac{\pi}{n}$.

(2) (α; γ). Xét các tam giác $AHS$ và $AKS$, ta thu được

$\cos\alpha = \dfrac{AH}{AS}$, $\sin\dfrac{\gamma}{2} = \dfrac{AK}{AS}$. Có nghĩa,

$\dfrac{\sin\dfrac{\gamma}{2}}{\cos\alpha} = \dfrac{AK}{AH} = \sin \angle AHK = \sin\dfrac{\pi}{n}$.

(3) (α; β). Xét các tam giác $AHS$ và $SHK$, ta thu được $\mathrm{tg}\,\alpha =$

$= \dfrac{SH}{AH}$, $\mathrm{tg}\,\beta = \dfrac{SH}{KH}$. Vì vậy, $\dfrac{\mathrm{tg}\,\alpha}{\mathrm{tg}\,\beta} =$

⟦column⟧

$= \dfrac{KH}{AH} = \cos \angle AHK = \cos\dfrac{\pi}{n}$.

Chúng ta hãy lưu ý một số hậu quả từ những công thức này.

Từ (1) suy ra $\mathrm{ctg}\dfrac{\varphi}{2} = \sin\alpha \times$

$\times\, \mathrm{ctg}\left(\dfrac{\pi}{2} - \dfrac{\pi}{n}\right)$. Nhưng $\sin\alpha < 1$ có nghĩa là

$\dfrac{\varphi}{2} > \dfrac{\pi}{2} - \dfrac{\pi}{n}$ hoặc $\varphi > \pi - \dfrac{2\pi}{n}$.

Từ (2) suy ra $\sin\dfrac{\gamma}{2} = \cos\alpha \sin\dfrac{\pi}{n}$.

Nhưng $\cos\alpha < 1$ có nghĩa là $0 < \dfrac{\gamma}{2} < \dfrac{\pi}{n}$ hoặc

$0 < \gamma < \dfrac{2\pi}{n}$. Từ cùng một công thức nó sau,

$$\dfrac{\sin\dfrac{\gamma}{2}}{\sin\left(\dfrac{\pi}{2} - \alpha\right)} = \sin\dfrac{\pi}{n} < 1,$$

Cái gì

đó là,

$\dfrac{\gamma}{2} < \dfrac{\pi}{2} - \alpha$ hoặc $\gamma < \pi - 2\alpha$.

Từ (3) suy ra $\dfrac{\mathrm{tg}\,\alpha}{\mathrm{tg}\,\beta} = \cos\dfrac{\pi}{n} < 1$,

$0 < \alpha < \beta$ đến từ đâu (nói chung là hiển nhiên).

⟦folio 62⟧

⟦folio 64⟧

Bài toán 6. Tìm $S$, biết $a$ và $\gamma$.

“Phương pháp chảo” bài toán rất dễ giải: sử dụng công thức (4) và (8), ta có

$$S = \frac{na^2\, \mathrm{ctg}\dfrac{\gamma}{2}}{4}.$$

Nhưng có lẽ việc giải quyết trực tiếp bài toán thậm chí còn dễ dàng hơn:

$$S = n \cdot S_{\triangle ASB} = n \cdot \frac{1}{2}AB \cdot SK =$$

$$n \cdot \frac{1}{2}a \cdot \frac{a}{2}\mathrm{ctg}\frac{\gamma}{2} = \frac{na^2\, \mathrm{ctg}\dfrac{\gamma}{2}}{4}.$$

Bài toán 7. Tìm $S$, biết $a$ và $\alpha$.

Từ công thức (3) suy ra mối quan hệ

$$\cos\beta = \frac{\cos\dfrac{\pi}{n}}{\sqrt{\mathrm{tg}^2\alpha + \cos^2\dfrac{\pi}{n}}}$$

(hãy kiểm tra xem!). Kể từ đây,

$$S = \frac{na^2\sqrt{\mathrm{tg}^2\alpha + \cos^2\dfrac{\pi}{n}}}{4\sin\dfrac{\pi}{n}}$$

Bài toán 8. Tìm $S$, biết $a$ và $\varphi$.

Từ công thức (5) suy ra

$$\cos\beta = \frac{\sqrt{-\cos\varphi - \cos\dfrac{2\pi}{n}}}{\sqrt{2}\sin\dfrac{\pi}{n}}$$

(kiểm tra!). Sử dụng công thức (8), chúng tôi thu được

$$S = \frac{\sqrt{2}\, na^2\cos\dfrac{\pi}{n}}{4\sqrt{-\cos\varphi - \cos\dfrac{2\pi}{n}}}.$$

## 5. Tính bán kính của hình cầu ngoại tiếp

Bài toán 9. Tìm $R$, biết $a$ và $\alpha$.

Như đã biết, luôn có thể mô tả một quả bóng ở gần một kim tự tháp thông thường; tâm của nó $O$ nằm tại giao điểm của đường cao $SH$ của hình chóp với đường vuông góc

⟦column⟧

hình tròn $FO$ đến cạnh bên, được vẽ qua giữa $F$ của cạnh $AS$ (xem Hình 2). Sau đó $\angle SOF =$
$= \angle SAH = \alpha$. Chúng tôi có $AS = \dfrac{AH}{\cos\alpha} =$
$= \dfrac{a}{2\sin\dfrac{\pi}{n}\cos\alpha}$; $\quad R = OS = \dfrac{FS}{\sin\alpha} =$
$= \dfrac{AS}{2\sin\alpha};$

$$R = \frac{a}{2\sin\dfrac{\pi}{n}\sin 2\alpha}. \tag{9}$$

Bài toán 10. Tìm $R$, biết $a$ và $\beta$.

Từ công thức (3) suy ra

$$\sin 2\alpha \cdot \frac{2\,\mathrm{tg}\,\alpha}{1+\mathrm{tg}^2\alpha} = \frac{2\,\mathrm{tg}\,\beta\cos\dfrac{\pi}{n}}{1+\mathrm{tg}^2\beta\cos^2\dfrac{\pi}{n}}.$$

Sử dụng công thức (9), chúng tôi thu được

$$R = \frac{a\left(1+\mathrm{tg}^2\beta\cos^2\dfrac{\pi}{n}\right)}{2\sin\dfrac{2\pi}{n}\,\mathrm{tg}\,\beta}.$$

Bài toán 11. Tìm $R$, biết $a$ và $\gamma$.

Từ công thức (2) suy ra

$$\sin\alpha = \frac{\sqrt{\cos\gamma - \cos\dfrac{2\pi}{n}}}{\sqrt{2}\sin\dfrac{\pi}{n}} \text{ (проверь-}$$

những cái đó!), và $\sin 2\alpha = 2\sin\alpha\cos\alpha =$

$$= \frac{\sqrt{2}\sin\dfrac{\gamma}{2}\sqrt{\cos\gamma - \cos\dfrac{2\pi}{n}}}{\sin^2\dfrac{\pi}{n}}.$$

Có nghĩa,

$$R = \frac{a}{2\sin\dfrac{\pi}{n}\sin 2\alpha} =$$

$$= \frac{\sqrt{2}\,a\sin\dfrac{\pi}{n}}{4\sin\dfrac{\gamma}{2}\sqrt{\cos\gamma - \cos\dfrac{2\pi}{n}}}$$

⟦folio 65⟧

Cơm. 2. Hình 3.

Công thức

$$R = \frac{\sqrt{2} \sin \frac{\varphi}{2} \mathrm{tg} \frac{\varphi}{2} \mathrm{tg} \frac{\pi}{n}}{4 \sqrt{1 - \cos \varphi - \cos \frac{2\pi}{n}}},$$

thể hiện $R$ đến $a$ và $\varphi$, chứng minh.

6. Tính bán kính của một quả bóng được ghi

Như đã biết, một quả bóng luôn có thể nội tiếp trong một paramid thông thường; tâm của nó $O$ nằm tại giao điểm của chiều cao $SH$ của paramid với phân giác của góc $SKH$ (Hình 3). Do đó, cách dễ nhất để tính bán kính của một quả bóng nội tiếp là khi cho góc $\beta$; từ trường hợp này chúng tôi sẽ dạy.

Bài toán 12. Tìm $r$, biết $a$ Và $\beta$.

Chúng tôi có $r = OH = KH \cdot \mathrm{tg} \frac{\beta}{2}$;

$$r = \frac{a}{2} \mathrm{ctg} \frac{\pi}{n} \mathrm{tg} \frac{\beta}{2}. \tag{10}$$

Bài 13. Tìm $r$ biết $a$ và $\alpha$.

Từ công thức (3) suy ra

$$\mathrm{tg} \frac{\beta}{2} = \frac{\sqrt{\cos^2 \frac{\pi}{n} + \mathrm{tg}^2 \alpha - \cos \frac{\pi}{n}}}{\mathrm{tg} \alpha}.$$

Từ công thức (10) bây giờ chúng ta có được

$$r = \frac{a}{2} \mathrm{ctg} \frac{\pi}{n} \mathrm{tg} \frac{\beta}{2} =$$

$$\frac{a \mathrm{ctg} \frac{\pi}{n} \left( \sqrt{\cos^2 \frac{\pi}{n} + \mathrm{tg}^2 \alpha - \cos \frac{\pi}{n}} \right)}{2 \mathrm{tg} \alpha}.$$

Bài 14. Tìm $r$ biết $a$ và $\gamma$.

Từ công thức (4), (10) ta thu được

$$r = \frac{a}{2} \mathrm{ctg} \frac{\pi}{n} \cdot \frac{\sin \left( \frac{\pi}{n} - \frac{\gamma}{2} \right)}{\sin \left( \frac{\pi}{n} + \frac{\gamma}{2} \right)}.$$

Hãy tự tìm biểu thức $r$ đến $a$ và $\varphi$.

bạn đúng

1. (MEPhI, 1973). Tìm góc nhị diện giữa đáy và mặt bên của một cạnh tam giác đều nếu góc nhị diện giữa các mặt bên của cạnh này bằng $\alpha$.
2. (UDN, 1973). The dihedral angles at the lateral edges of a regular 4-gonal paramid are equal to $\alpha$. Find the dihedral angles at the lateral edge equal to $2\alpha$. Tìm thể tích của paramid.
4. (USU, 1973). Chiều cao của một tham số hình tam giác đều là $h$ và khoảng cách từ đáy của chiều cao đến cạnh bên là $a$. Determine the dihedral angle between the lateral faces of the paramid.
5. (MATI, 1973). Mỗi góc bằng nhau của mặt bên của một paramid lục giác đều bằng $\varphi$. Khoảng cách từ giữa chiều cao đến cạnh bên là $l$. Tìm chiều cao của paramid.
6. (MAI, 1973). Chiều cao của một paramid tứ giác đều là $h$ và góc phẳng giữa các mặt bên liền kề là $\varphi$. Tìm diện tích bề mặt bên.
7. (UDN, 1973). Cạnh đáy của một paramid tứ giác đều ngoại tiếp một quả cầu có bán kính $R$ bằng $a$. Tìm bề mặt hoàn chỉnh của paramid.
8. (NSU, cơ khí, 1969). Góc nhị diện ở cạnh bên của paramid 4 cạnh đều bằng $\alpha$, bán kính của hình cầu nội tiếp là $R$. Tìm bề mặt hoàn chỉnh của paramid.
9. (YAPI, 1973). Một paramidian tứ giác đều nội tiếp trong một quả cầu có bán kính $R$, có góc phẳng tại đỉnh bằng $\alpha$. Tìm thể tích của paramid.
10. (Từ thư của bạn đọc) Tìm thể tích của paramid $SABC$, nếu chiều cao nghiêng với mặt phẳng đáy một góc $30^\circ$, $\triangle ABC$ là tam giác đều thì nội tiếp đường tròn có bán kính $r$ và $SC = OC$ và $SO \perp BA$.

G. M-va
