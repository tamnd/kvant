---
id: 1976-12-belyiy-pryamougolnyiy-treugolnik-c8b9733a
issue: kvant_1976_12
year: 1976
number: "12"
title: 直角三角形
authors:
  - Белый С. Б.
rubric: raznoe
rubric_sub: Разное
page_first: 52
page_last: 55
page_labels: 50-53
tag: 9U0J
lang: zh
source: kvant_digital
extraction: vision
content_sha256: d419e358ac787e8cf7b8214cc8c73c552a36e4c700e555dfc3a871f8033fa0d8
prompt_sha256: draft-1
translated_from: content/ru/1976/12/articles/12_belyiy-pryamougolnyiy-treugolnik-c8b9733a.md
source_content_sha256: 80317ad1306cbbd8fe76f56f8979c2a2ca3f6831412e8ba7b54c4b6b67b06e43
translation_model: draft
translation_run: zh-draft-2026-11-01
translation_quality: draft
---

⟦folio 50⟧

S·贝利

直角三角形

在数学入学考试中，经常会出现涉及直角三角形的问题。为了成功解决此类问题，除了毕达哥拉斯定理之外，您还需要了解直角三角形的哪些知识？这就是本文将要讨论的内容。

规定 1. 直角三角形外接圆与 1 的中点重合的值。

这导致以下关系：

$$m = R = \frac{c}{2},$$

其中$m$是绘制到斜边的中线的长度，$R$是外接圆的半径，$c$是斜边（参见图1 - 它将帮助您证明这个陈述）。

解决问题时经常使用这种关系。

实施例 1（密歇根州立大学化学系，1974 年）。在边为 3 和 4（厘米）的直角三角形 ABC 中，直角顶点 C 与中间 D 单元 AB 连接。求矩形 ACD 和 BCD 中描述的圆心之间的距离。

根据命题1，D点是外接圆的圆心，因此$|DA| = |DC| = |DB|$。因此，三角形ACD和BCD是等腰的（见图2）。中描述的圆的中心

⟦folio 51⟧

实施例 3（密歇根州立大学化学系，1973 年）。一个正方形内接于直角三角形 ABC，其两个顶点位于中菜单上，另外两个顶点位于卡梅线上。三角形ABC外接圆的半径与正方形半径的关系为13:6。求三角形ABC的角。

让$\hat{A} = \alpha$，用$a$表示正方形的边（参见图4）。然后$|AB| = a \text{ctg}\alpha + a + a \text{tg}\alpha$，并且

$$\frac{a \text{ctg}\alpha + a + a \text{tg}\alpha}{2a} = \frac{13}{6},$$

从哪里$\text{ctg}\alpha + \text{tg}\alpha + 1 = 13/3$，$3 \text{tg}^2\alpha - 10 \text{tg}\alpha + 3 = 0$，$\alpha_1 = \text{arctg} 3$，$\alpha_2 = \text{arctg} 1/3$。但角$\alpha_1$和$\alpha_2$在一条直线上互补。因此，三角形ABC的内角为$\text{arctg} 3, \frac{\pi}{2}, \text{arctg} 1/3$。

陈述2.从三角形的直角顶点引出的高度，我们将其分为两个子直角三角形，其中一个与给定的相似。

从该语句可得出以下关系（有关符号，请参见图 5）：

$$h^2 = a'b', a^2 = a'c, b^2 = b'c,$$

$$a^2 + b^2 = c^2, \frac{a^2}{b^2} = \frac{a'}{b'}.$$

让我们向其中添加计算直角三角形面积的公式：

$$S = \frac{1}{2}ab = \frac{1}{2}ch = mh = Rh.$$

实施例 4（MIPT，1962）。在直角三角形ABC中，从直角C的顶点引出高度CD。已知三角形ACD和BCD所描述的圆的半径分别等于$r_1$和$r_2$。求三角形 ABC 外接圆的半径。

⟦folio 52⟧

图 6.

根据陈述2，三角形ADC、CDB和ACB相似（见图6）。在类似的三角形中，内切圆的半径（以及任何其他相应的线性元素）与相应的边相关。然后

$$\frac{|AC|}{r_1} = \frac{|BC|}{r_2} = \frac{|AB|}{r} = k.$$

从这里，使用毕达哥拉斯定理，我们得到：

$$r_1^2 k^2 + r_2^2 k^2 = r^2 k^2, r^2 = r_1^2 + r_2^2, r = \sqrt{r_1^2 + r_2^2}.$$

评论。所得公式 $r^2 = r_1^2 + r_2^2$ 具有一般性质：对于三角形 ADC、CDB、ACB (图 6) 的任何相应线性元素 $x, y, z$，依赖关系 $x^2 + y^2 = z^2$ 均有效。

为了证明这个命题，只需将$x, y, z$与$r_1, r_2, r$一起代入即可。

实施例 5（MIPT，1969）。在直角三角形中，画出直角C的二边CD。已知$|AD| = m, |BD| = n$。求从角 C 的顶点落下的高度。

令 $x$ 和 $y$ 为斜边 (图 7) 上的腿投影的长度。然后

$$\frac{x}{y} = \frac{|AC|^2}{|BC|^2}.$$

但

$$\frac{|AC|}{|BC|} = \frac{|AD|}{|BD|} = \frac{m}{n}$$

（根据 bissertitsa 的财产）。结果是一个系统

$$\begin{cases} x + y = m + n, \\ \frac{x}{y} = \frac{m^2}{n^2}. \end{cases}$$

从这个系统中找到$x$和$y$，我们使用公式$h = \sqrt{xy}$确定高度：

$$h = \frac{mn(m + n)}{m^2 + n^2}.$$

陈述 3（与毕达哥拉斯定理相反）。如果一个三角形的一条边的平方等于另外两条边的平方和，那么它就是直角三角形。

这个陈述是从余弦定理得出的，在某些情况下它可能非常有用。

例6. 设$a, b$为直角三角形ABC的彗星，$c$为斜边，$h$为从顶点C下降的高的长度。证明边$h, c + h, a + b$的三角形是直角三角形。

很容易检查$(a + b)^2 + h^2 = (c + h)^2$，因为它是奶油状的，等于$ab = ch$。这是问题的陈述。

众所周知的公式是$r = \frac{S}{p}$（或$S = pr$），其中$S$是三角形的面积，$p$是半周长，$r$是内切圆的半径。对于直角三角形，可以使用更简单的公式计算内切圆的半径：

$$r = \frac{a + b - c}{2}.$$

另请注意公式

$$2r + 2R = a + b$$

（最后两个公式是等效的）。尝试自己证明这些公式。

⟦folio 53⟧

实施例 7（MSU，化学系，1974）。在具有正方形 $|AC| = 3$ 和 $|BC| = 4$ 的直角三角形 ABC 中，绘制高度 CD。该名称是三角形 ACD 和 BCD 内切圆的圆心之间的考虑。

设 $r_1$ 和 $r_2$ 分别为三角形 ACD 和 BCD 内切圆的半径 (图 8)。然后
$$|O_1O_2| = \sqrt{(r_1 + r_2)^2 + (r_1 - r_2)^2} = \sqrt{2} \cdot \sqrt{r_1^2 + r_2^2}.$$
但是 $\sqrt{r_1^2 + r_2^2} = r$，其中 $r$ 是三角形 ABC 内切圆的半径（参见示例 4），因此
$$|O_1O_2| = \sqrt{2} \cdot r = \sqrt{2} \cdot \frac{|BC| + |AC| - |AB|}{2} = \sqrt{2}.$$
最后，这里还有一个对于解决问题也很有用的陈述。

陈述 4. 在不等正方形的直线三角形中，直角平分线除以高与从同一角顶点引出的中线之间的角度。

这个命题的证明从图 9 就很清楚了。

实施例 8（MSU，VMK，1973）。在直角三角形ABC中，到zinometus的高的长度是$a$，直角平分线是$b$。命名三角形ABC的面积。

让我们取中值 CM（参见 图 9）并设置 $\widehat{DCL} = \alpha$；那么，根据陈述4和$\widehat{LCM} = \alpha$。接下来是$\cos \alpha = \frac{a}{b}$、$\cos 2\alpha = 2\cos^2\alpha - 1 = \frac{2a^2 - b^2}{b^2}$、$|CM| = \frac{a}{\cos 2\alpha} = \frac{ab^2}{2a^2 - b^2}$。

现在可以求三角形ABC的面积：
$$S = |CD| \cdot |AM| = |CD| \cdot |CM| = \frac{a^2 b^2}{2a^2 - b^2}.$$
您可能已经注意到，上面讨论的所有问题都是使用代数方法解决的。这并不奇怪，因为上述公式代表了构建所有可能方程的强大武器库。然而，您不应该认为直角三角形上的所有问题都可以用代数方法解决 - 有时首先进行一些额外的构造是有用的。

实施例9（MIPT，1971）。一个圆与直角三角形 ABC 外接。从方法AB的端点到C点与圆相切的直线的距离分别等于m和n。彗星的名称是$|AC|$和$|BC|$。

让我们画出高度CD（参见图10）并注意$\widehat{ACD} = \widehat{ABC} = \widehat{ACE}$（最后两个角度由同一弧AC的位置改变）。因此，三角形 AEC 和 ADC 是重合的（通过斜边和锐边）
