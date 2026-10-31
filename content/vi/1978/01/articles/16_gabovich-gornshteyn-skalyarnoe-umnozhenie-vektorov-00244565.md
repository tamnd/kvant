---
id: 1978-1-gabovich-gornshteyn-skalyarnoe-umnozhenie-vektorov-00244565
issue: kvant_1978_1
year: 1978
number: "1"
title: Phép nhân vectơ vô hướng
authors:
  - Габович И. Г.
  - Горнштейн П. И.
rubric: praktikum-abiturienta
rubric_sub: Практикум абитуриента
page_first: 49
page_last: 54
page_labels: 47, 49, 50, 51, 52
tag: 1RBG
lang: vi
source: kvant_digital
extraction: vision
content_sha256: 7fc5e2e7a4bf7d4f624fc7292fc0e5ad2913163b59adb417199c059adbe38b65
prompt_sha256: draft-1
translated_from: content/ru/1978/01/articles/16_gabovich-gornshteyn-skalyarnoe-umnozhenie-vektorov-00244565.md
source_content_sha256: 2ce29be6e593c98c2e8a7332d2872ad3e40b5208e0753ac63b0d733546f586d0
translation_model: draft
translation_run: vi-draft-2026-10-31
translation_quality: draft
---

⟦folio 47⟧

Phép nhân vectơ vô hướng là một trong những khái niệm cơ bản của đại số vectơ. Tính chất của nó được sử dụng rộng rãi trong việc chứng minh lý thuyết và lời giải bài toán.

Trong bài viết này, chúng tôi sẽ minh họa ứng dụng của phép nhân vectơ vô hướng cho lời giải hình học bài toán, được đưa ra trong các kỳ thi đầu vào những năm gần đây trong quá trình phát triển nghiên cứu về vectơ được trình bày trong sách hướng dẫn "Hình học 9" do Z. A. Skopets biên tập. Vì vậy, chúng tôi sẽ không tập trung vào lý thuyết về vấn đề này. Hãy chuyển sang lời giải bài toán.

Bài toán 1. (MIPT, 1977). Cạnh đáy của hình tam giác đều $ABCA_1B_1C_1$ có chiều dài $a$. Các đỉnh $M$ và $N$ của tam giác đều $MNPQ$ nằm trên đường thẳng đi qua các điểm $C_1$ và $B$, các đỉnh $P$ và $Q$ nằm trên đường thẳng $A_1C$. Tìm thấy:

1) khối lượng công nhận;
2) khoảng cách giữa trung điểm của các đoạn $MN$ và $PQ$.

Lời giải. Hãy xem xét các vectơ: $\overrightarrow{CA}, \overrightarrow{CB}, \overrightarrow{CC_1}, \overrightarrow{CA_2}$ và $\overrightarrow{BC_1}$ (Hình 1). Hãy biểu thị $\overrightarrow{CA} = \vec{u}, \overrightarrow{CB} = \vec{v}, \overrightarrow{CC_1} = \vec{h}$ và $\overrightarrow{|h|} = h$. Nó tuân theo điều kiện $\overrightarrow{|u|} = \overrightarrow{|v|} = a$.

Vì trong một tứ diện đều (thực ra là trong bất kỳ hình tam giác đều nào) bất kỳ cạnh giao nhau nào đều vuông góc với nhau, nên $\overrightarrow{CA_1} \perp \overrightarrow{BC_1}$. Vì vậy $\overrightarrow{CA_1} \cdot \overrightarrow{BC_1} = 0$. Nhưng trong ký hiệu của chúng tôi

$$\overrightarrow{CA_1} = \vec{u} + \vec{h} \text{ и } \overrightarrow{BC_1} = \vec{h} - \vec{v},$$

theo,

$$(\vec{u} + \vec{h}) \cdot (\vec{h} - \vec{v}) = 0,$$

$$\vec{u} \cdot \vec{h} - \vec{u} \cdot \vec{v} + \vec{h}^2 - \vec{h} \cdot \vec{v} = 0.$$

Xét rằng $\vec{h} \perp \vec{u}, \vec{h} \perp \vec{v}$ và $(\vec{u}, \vec{v}) = \frac{\pi}{3}$, chúng ta nhận được

$$h^2 - \frac{a^2}{2} = 0, \text{ или } h = \frac{a}{\sqrt{2}},$$

khối lượng nhận dạng ở đâu $V = \frac{a^2 \sqrt{3}}{4} \cdot \frac{a}{\sqrt{2}} = \frac{a^3 \sqrt{6}}{8}$.

Đặt $K$ và $L$ lần lượt là trung điểm của các đoạn $PQ$ và $MN$. Hãy cùng tìm $|KL|$. Lưu ý rằng $[KL]$ là đường vuông góc chung của các cạnh $PQ$ và $MN$ (chính bằng chứng), tức là $|KL|$ là khoảng cách giữa các đường xiên $CA_1$ và $BC_1$.

Có một số cách để tính khoảng cách giữa các đường giao nhau. Chúng tôi sẽ xác định khoảng cách cần thiết bằng cách sử dụng phép nhân vô hướng. Đồng thời, làm thế nào

⟦folio 49⟧

Không phải $\overrightarrow{HN}$ hay $\overrightarrow{AB}$. Hãy biểu thị: $\overrightarrow{HP} = \vec{p}$, $\overrightarrow{HQ} = \vec{q}$ và $\overrightarrow{HR} = \vec{r}$. Chúng ta biểu thị các vectơ còn lại thông qua $\vec{p}$, $\vec{q}$ và $\vec{r}$. Rõ ràng là $|\vec{p}| = |\vec{q}| = 2$ và $|\vec{r}| = 1$.

Cho phép

$$|RA| = x |RF|,$$
$$|HB| = y |HN|.$$

Sau đó $\overrightarrow{RA} = x\overrightarrow{RF}$ và $\overrightarrow{HB} = y\overrightarrow{HN}$.

Rõ ràng, $\overrightarrow{RF} = \frac{1}{2}\vec{p} - \vec{r}$ và $\overrightarrow{HN} = \frac{1}{2}\vec{p} + \frac{1}{2}\vec{q}$ ([HN] là đường trung bình trong tam giác HPQ). Bởi vì

$$\overrightarrow{RA} = \frac{x}{2}\vec{p} - x\vec{r},$$
$$\overrightarrow{HB} = \frac{y}{2}\vec{p} + \frac{y}{2}\vec{q}.$$

Bây giờ chúng ta hãy biểu thị $\overrightarrow{AB}$ thông qua các vectơ $\vec{p}, \vec{q}$ và $\vec{r}$:

$$\overrightarrow{AB} = \overrightarrow{AR} + \overrightarrow{RH} + \overrightarrow{HB} = -\overrightarrow{RA} - \overrightarrow{HR} + \overrightarrow{HB} = -\frac{x}{2}\vec{p} + x\vec{r} - \vec{r} + \frac{y}{2}\vec{p} + \frac{y}{2}\vec{q} = \frac{1}{2}(y-x)\vec{p} + \frac{y}{2}\vec{q} + (x-1)\vec{r}.$$

Vì $[AB] \perp [RF]$ và $[AB] \perp [HN]$, nên $\overrightarrow{AB} \cdot \overrightarrow{RF} = 0$ và $\overrightarrow{AB} \cdot \overrightarrow{HN} = 0$. Hình thành một hệ thống

$$\begin{cases}
\left(\frac{1}{2}(y-x)\vec{p} + \frac{y}{2}\vec{q} + (x-1)\vec{r}\right) \times \\
\times \left(\frac{1}{2}\vec{p} - \vec{r}\right) = 0, \\
\left(\frac{1}{2}(y-x)\vec{p} + \frac{y}{2}\vec{q} + (x-1)\vec{r}\right) \times \\
\times \left(\frac{1}{2}\vec{p} + \frac{1}{2}\vec{q}\right) = 0.
\end{cases}$$

Từ hệ thống này, có tính đến việc các vectơ $\vec{p}, \vec{q}$ và $\vec{r}$ vuông góc với nhau

⟦folio 50⟧

là cular thì $\overrightarrow{AC} \cdot \overrightarrow{BM} = 0$ hoặc
$(\vec{b} - \vec{h}) \cdot (\vec{a} + \vec{h} - \vec{y}) = 0,$
$\vec{a} \cdot \vec{b} + \vec{b} \cdot \vec{h} - \vec{b} \cdot \vec{y} - \vec{a} \cdot \vec{h} -$
$-\vec{h}^2 + \vec{h} \cdot \vec{y} = 0$. (5)

Như đã lưu ý, $\vec{a} \cdot \vec{h} = \vec{h} \cdot \vec{y} = 0$
Trên cơ sở tương tự $\vec{b} \cdot \vec{h} = 0$. Do đó, từ (5) ta có
$$\vec{a} \cdot \vec{b} - \vec{b} \cdot \vec{y} - \vec{h}^2 = 0,$$
$$ab - by - h^2 = 0,$$
$$y = \frac{ab - h^2}{b}.$$ (6)

Giá trị $y$ từ (6) được xác nhận ở (4)
$$h^2 = \frac{a^2b - ah^2}{b},$$

Ở đâu
$$h = \frac{a\sqrt{b}}{\sqrt{a+b}}.$$

Bài toán 4 (Đại học bang Ural, 1971). Tam giác $AOB$ được quay trong mặt phẳng của nó quanh đỉnh $O$ x $90^\circ$, với đỉnh $A$ bước vào $A'$ và đỉnh $B - bB'$. Chứng minh rằng trong tam giác $OAB'$ đường trung tuyến của cạnh $AB'$ là chiều cao của tam giác $OA'B$ (tương tự, đường trung bình của cạnh $A'B$ trong tam giác $OA'B$ là chiều cao của $\Delta OAB'$).

Lời giải. Đặt $C$ ở giữa $[AB']$ (Hình 4). Hãy để chúng tôi chứng minh rằng $\overrightarrow{OC} \perp \overrightarrow{A'B}$, tức là $\overrightarrow{OC} \cdot \overrightarrow{A'B} = 0$; chúng tôi có

Cơm. 4.

Cơm. 5.

⟦folio 51⟧

$$DP = \frac{a\sqrt{6}}{3}, \quad |PQ| = |MN| = \frac{a}{2}.$$
Gọi $\varphi$ là độ lớn của góc giữa các vectơ $\overrightarrow{MN}$ và $\overrightarrow{PQ}$. Hãy tìm giá trị của $\varphi$ từ định nghĩa nhân vô hướng của hai vectơ

$$\cos \varphi = \frac{\overrightarrow{MN} \cdot \overrightarrow{PQ}}{|\overrightarrow{MN}| \cdot |\overrightarrow{PQ}|}.$$

Hãy viết các vectơ đẳng thức tiếp theo

$$\overrightarrow{MN} = \overrightarrow{MD} + \overrightarrow{DN},$$

$$\overrightarrow{PQ} = \overrightarrow{DQ} - \overrightarrow{DP}.$$

Giá trị $\overrightarrow{MN}$ và $\overrightarrow{PQ}$ từ (8) được thay thế thành (7)

$$\cos \varphi = \frac{(\overrightarrow{MD} + \overrightarrow{DN}) \cdot (\overrightarrow{DQ} - \overrightarrow{DP})}{|\overrightarrow{MN}| \cdot |\overrightarrow{PQ}|} = \frac{\overrightarrow{MD} \cdot \overrightarrow{DQ} + \overrightarrow{DN} \cdot \overrightarrow{DQ} - \overrightarrow{DP} \cdot \overrightarrow{MD}}{|\overrightarrow{MN}| \cdot |\overrightarrow{PQ}|} + \frac{-\overrightarrow{DN} \cdot \overrightarrow{DP}}{|\overrightarrow{MN}| \cdot |\overrightarrow{PQ}|}.$$

Lưu ý rằng $(\overrightarrow{MD}, \overrightarrow{DQ}) = \frac{2}{3}\pi$ và $(\overrightarrow{DP}, \overrightarrow{MD}) = \pi - \overrightarrow{MDP}$. Rõ ràng là $\cos MDP = \frac{\sqrt{6}}{3}$ và $\cos NDP = \frac{2\sqrt{2}}{3}$.

Có tính đến những điều trên, chúng tôi nhận được

**Cơm. 6.**

$$\cos \varphi = \frac{-\frac{a^2}{8} + \frac{a^2}{4} + \frac{a^2}{3} - \frac{4a^2}{9}}{\frac{a}{2} \cdot \frac{a}{2}} = \frac{1}{18}.$$

$\varphi = \arccos \frac{1}{18}$ là góc giữa các đoạn $MN$ và $PQ$.

Nhiệm vụ 6 (MSU, cơ chế, 1970). Độ dài mỗi cạnh của hình chóp tam giác $SABC$ bằng 1, $[BD]$ là chiều cao của tam giác $ABC$. Tam giác đều $BDE$ nằm trong mặt phẳng tạo thành một góc $\varphi$ với cạnh $AC$, đồng thời các điểm $S$ và $E$ nằm cùng một phía của mặt phẳng $ABC$. Tìm khoảng cách giữa các điểm $S$ và $E$.

Lời giải. Chúng ta hãy vẽ (Hình 6) trong tam giác $BDE$ chiều cao $EM$ và nối các điểm $O$ và $E$. Qua điểm $M$ chúng ta vẽ $[MN] \parallel [AC]$ và $[MP] \parallel [SO]$. Vì các đoạn $MN$ và $AC$ song song nên chúng tạo các góc bằng nhau với mặt phẳng $BDE$. Vì $[MN] \perp [BD]$ và $[EM] \perp [BD]$, nên $\angle EMN$, như dễ hiểu, là góc mà $[MN]$ (và do đó, $[AC]$) tạo với mặt phẳng $BDE$, tức là $\hat{EMN} = \varphi$. Vì $[MP] \parallel [SO]$, thì $[MP] \perp (ABC)$ và do đó $[MP] \perp [BD]$ và $[MP] \perp [MN]$. Vì vậy $\hat{EMP} = 90^\circ + \varphi$. Rõ ràng là $\overrightarrow{SE} = \overrightarrow{SO} + \overrightarrow{OM} + \overrightarrow{ME}$.

Hãy tìm bình phương vô hướng của vectơ $\overrightarrow{SE}$:

$$\overrightarrow{SE}^2 = \overrightarrow{SO}^2 + \overrightarrow{OM}^2 + \overrightarrow{ME}^2 + 2 \cdot \overrightarrow{SO} \cdot \overrightarrow{OM} + 2 \cdot \overrightarrow{SO} \cdot \overrightarrow{ME} + 2 \cdot \overrightarrow{OM} \cdot \overrightarrow{ME}.$$

Rõ ràng là $\overrightarrow{SO} \cdot \overrightarrow{OM} = \overrightarrow{OM} \cdot \overrightarrow{ME} = 0$. Vì rất dễ báo cáo, $(\overrightarrow{SO}, \overrightarrow{ME}) = \hat{EMP} = 90^\circ + \varphi$, $|SE|^2 = |SO|^2 + |OM|^2 + |ME|^2 - 2 \cdot |SO| \cdot |ME| \cdot \sin \alpha$. 10).

Nhưng $|SO| = \frac{\sqrt{6}}{3}$ giống như chiều cao của một tam giác đều có cạnh bằng 1; $|ME| = \frac{3}{4}$ – chiều cao như thế nào là chính xác

⟦folio 52⟧

của tam giác tính từ cạnh bằng $\frac{\sqrt{3}}{2}$; $|OM| = \frac{\sqrt{3}}{12}$ (tự tính).

Chúng ta thay thế các giá trị tìm được $|SO|, |OM|$ và $|ME|$ vào (10):

$$|SE|^2 = \left(\frac{\sqrt{6}}{3}\right)^2 + \left(\frac{\sqrt{3}}{12}\right)^2 + \frac{9}{16} - 2 \cdot \frac{\sqrt{6}}{3} \cdot \frac{3}{4} \sin \varphi = \frac{5 - 2\sqrt{6} \sin \varphi}{4},$$

$$|SE| = \frac{1}{2} \sqrt{5 - 2\sqrt{6} \sin \varphi}.$$

Bài toán 7 (MIPT, 1974.) Cạnh đáy của tam giác đều $ABCA_1B_1C_1$ bằng $a$; các điểm $O$ và $O_1$ lần lượt là tâm của các đáy $ABC$ và $A_1B_1C_1$. Độ dài hình chiếu trực giao của đoạn $AO_1$ lên đường thẳng $B_1O_1$ bằng $\frac{5}{6}a$. Xác định chiều cao của biển báo.

Lời giải. Hãy đặt $|OO_1| = H$. Rõ ràng (Hình 7) là $|\overrightarrow{AO}| = |\overrightarrow{OB}| = \frac{a\sqrt{3}}{3}$ và $|\overrightarrow{OB}_1| = \sqrt{\frac{a^2}{3} + H^2}$. Tiếp theo $\overrightarrow{AO}_1 \cdot \overrightarrow{OB}_1 = |AO_1| \cdot |OB_1| \cdot \cos \varphi$. (11)

Được biết, hình chiếu của một vectơ này lên một vectơ khác bằng chiều dài của vectơ thứ nhất nhân với cosin của góc giữa các hướng của vectơ, tức là $\pi \overrightarrow{OB}_1 \cdot \overrightarrow{AO}_1 = |\overrightarrow{AO}_1| \times \cos \varphi = |\overrightarrow{AO}_1| \cdot \cos \varphi$.

Theo điều kiện bài toán

$$\pi \overrightarrow{OB}_1 \cdot \overrightarrow{AO}_1 = \frac{5a}{6}.$$

Do đó, đẳng thức (11) được viết như sau:

$$\overrightarrow{AO}_1 \cdot \overrightarrow{OB}_1 = |OB_1| \cdot \frac{5a}{6}.$$

Hãy viết các đẳng thức sau:

$$\overrightarrow{AO}_1 = \overrightarrow{AO} + \overrightarrow{OO_1},$$

$$\overrightarrow{OB}_1 = \overrightarrow{OB} + \overrightarrow{BB_1}.$$

Như vậy,

$$\overrightarrow{AO}_1 \cdot \overrightarrow{OB}_1 = (\overrightarrow{AO} + \overrightarrow{OO_1}) \cdot (\overrightarrow{OB} + \overrightarrow{BB_1}) = \overrightarrow{AO} \cdot \overrightarrow{OB} + \overrightarrow{AO} \cdot \overrightarrow{BB_1} + \overrightarrow{OO_1} \cdot \overrightarrow{OB} + \overrightarrow{OO_1} \cdot \overrightarrow{BB_1}.$$

Vì $\overrightarrow{AO} \perp \overrightarrow{BB_1}$ và $\overrightarrow{OO_1} \perp \overrightarrow{OB}$, nên $\overrightarrow{AO} \cdot \overrightarrow{BB_1} = \overrightarrow{OO_1} \cdot \overrightarrow{OB} = 0.$

Hơn nữa, $\overrightarrow{OO_1} = \overrightarrow{BB_1}$ do đó $\overrightarrow{OO_1} \cdot \overrightarrow{BB_1} = |OO_1|^2$,

$$\overrightarrow{AO}_1 \cdot \overrightarrow{OB}_1 = \overrightarrow{AO} \cdot \overrightarrow{OB} + |OO_1|^2 = \frac{a\sqrt{3}}{3} \cdot \frac{a\sqrt{3}}{3} \cdot \frac{1}{2} + H^2 = \frac{a^2}{6} + H^2.$$

Chúng tôi thay thế các giá trị tìm thấy $\overrightarrow{AO}_1 \cdot \overrightarrow{OB}_1$ và $|OB_1|$ thành (12) $\frac{a^2}{6} + H^2 = \frac{5a}{6} \sqrt{\frac{a^2}{3} + H^2}$, từ đó $108H^4 = -39a^2H^2 - 22a^4 = 0$. Vì $H > 0$, nên $H = \frac{a\sqrt{6}}{3}$.

1 (MIPT, 1977). Đáy của hình tam giác vuông $ABCA_1B_1C_1$ là tam giác vuông đều có hai chân $|AC| = |BC| = a$. Các đỉnh $M$ và $N$ của tứ diện đều $MNPQ$ nằm trên đường thẳng $CA_1$, còn các đỉnh $P$ và $Q$ nằm trên đường thẳng $AB_1$. Tìm: 1) thể tích của đường thẳng; 2) khoảng cách giữa trung điểm của các đoạn $MN$ và $PQ$.

2 (MIPT, 1977). Độ dài của cạnh hình lập phương $ABCDA_1B_1C_1D_1$ bằng $a$. Điểm $E$ là điểm giữa của cạnh $AD$. Các đỉnh $M$ và $N$ của tứ diện đều $MNPQ$ nằm trên đường thẳng $ED_1$, các đỉnh $P$ và $Q$ nằm trên đường thẳng đi qua điểm $A_1$ và cắt đường thẳng $BC$ tại điểm $R$.

Tìm: 1) quan hệ $|BR| : |BC|$; 2) khoảng cách giữa trung điểm của các đoạn $MN$ và $PQ$.

3 (MIPT, 1969). Trong một tứ diện đều $ABCD$, đoạn $MN$ nối trung điểm của cạnh $AC$ với tâm của mặt $BCD$ và điểm $E$ nằm ở trung điểm của cạnh $AB$. Tìm góc giữa các đoạn $MN$ và $DE$.

4 (Khoa Vật lý, Đại học Tổng hợp Matxcơva, 1963). Hai đoạn – $AB$ có chiều dài $a$ và $CD$ có ​​chiều dài $b$ nằm trên các đường xiên, góc giữa chúng là $a$. Các đáy $O$ và $O_1$ của đường vuông góc chung có độ dài $c$ với các đường thẳng này chia các đoạn $AB$ và $CD$ sao cho $|OA| : |OB| = 2:3$ và $|OO_1| : |C_1D| = 3:2$. Tìm độ dài của các đoạn $BD$ và $BC$.

5 (Từ nhiệm vụ 3FTSH). Trong hình chữ nhật 4 góc đều $SABCD$, độ dài đường vuông góc chung của các cạnh $SA$ và $BC$ là $d$ và đáy của nó chia đoạn $BC$ theo tỷ lệ 1:3. Xác định thể tích của đường thẳng.

6 (Học viện Bách khoa Kiev, 1977). Trong mặt phẳng của đường thẳng $ABCD$ cho điểm $M$. Chứng minh rằng $\overrightarrow{MA} \cdot \overrightarrow{MC} = \overrightarrow{MB} \cdot \overrightarrow{MD}$.

7 (Thế vận hội Liên đoàn hạng cân 1974). Cho một hình vuông $ABCD$. Điểm $P$ và $Q$ lần lượt nằm trên các cạnh $AB$ và $BC$, với $|BP| = |BQ|$. Gọi $H$ là đáy của đường vuông góc hạ từ điểm $B$ đến đoạn $PC$. Chứng minh góc $DHQ$ là góc vuông.
