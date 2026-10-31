---
id: 1972-7-gotman-teorema-kosinusov-i-ee-sledstviya-ebfa1deb
issue: kvant_1972_7
year: 1972
number: "7"
title: 余弦定理及其推论
authors:
  - Готман Э. Г.
rubric: matematicheskiy-kruzhok
rubric_sub: Математический кружок
page_first: 31
page_last: 34
page_labels: 29-32
tag: G2GT
lang: zh
source: kvant_digital
extraction: vision
content_sha256: 56935df055656358309db28d90f7786b9b0444e575a5e6ef8fe4fa871da1d297
prompt_sha256: draft-1
translated_from: content/ru/1972/07/articles/09_gotman-teorema-kosinusov-i-ee-sledstviya-ebfa1deb.md
source_content_sha256: 645ae642aea29c17e27d3e832185c3644891ab07c774a82487539fb494fdc46a
translation_model: draft
translation_run: zh-draft-2026-10-31
translation_quality: draft
---

⟦folio 29⟧

本文解释了如何使用余弦定理来解决各种几何问题。 CAMA 余弦定理尚未证明。

要从两条边计算三角形的元素以及它们之间或从三边的角度，请使用对应关系

$$a^2 = b^2 + c^2 - 2bc \cos A,$$

称为“余弦定理”。

余弦定理还可以用来解决更困难的问题。

示例 1. 如果已知平行四边形的边 a 和 b 以及对角线之间的锐角 α，则求该平行四边形的面积。

解决方案。令 $ABCD$ 为平行四边形，其中 $AB = a$ 和 $BC = b$ (图 1)。我们假设$a > b^*$。那么对角线之间的角度$BOC$是锐角，并且根据问题的条件$\Rightarrow BOC = \alpha$。

如果我们将对角线$AC$的长度表示为2x，对角线的长度表示为$*$）如果$a = b$，则平行四边形是菱形，对角线之间的角度是直线。

BD经过2y，则平行四边形$S$的面积等于2xysinα。从三角形 $AOB$ 和 $BOC$，使用余弦定理，我们找到边 a 和 b：

$$a^2 = x^2 + y^2 + 2xycos\alpha,$$
$$b^2 = x^2 + y^2 - 2xycos\alpha.$$

因为

$$a^2 - b^2 = 4xycos\alpha,$$

在哪里

$$xy = \frac{a^2 - b^2}{4cos\alpha}.$$

因此，

$$S = \frac{(a^2 - b^2)sin\alpha}{2cos\alpha}$$

或者

$$S = \frac{a^2 - b^2}{2}tg\alpha.$$

笔记。如果$A$是平行四边形的角度，则$S = absinA$，这意味着$0 < S \leq ab$。因为

$$\frac{a^2 - b^2}{2}tg\alpha \leq ab$$ 和

$$tg\alpha \leq \frac{2ab}{a^2 - b^2}.$$

因此，为了使问题有解，必须选择参数 a、b 和 α 以满足不等式

$$a > b > 0, \alpha \leq arctg \frac{2ab}{a^2 - b^2}.$$

⟦folio 30⟧

使用众所周知的几何和三角学公式，从余弦定理可以推导出连接任何三角形元素的一些关系。

例2.证明三角形ABC的边长、边长和面积S满足关系式

$$\text{ctg } A + \text{ctg } B + \text{ctg } C = \frac{a^2 + b^2 + c^2}{4S}.$$

解决方案。从公式$S = \frac{1}{2} bc \sin A$我们发现$bc = \frac{2S}{\sin A}$。将表达式$\frac{4S}{\sin A}$与$2bc$一起代入公式$a^2 = b^2 + c^2 - 2bc \cos A$，可得关系式

$$a^2 = b^2 + c^2 - 4S \text{ctg } A.$$ (1)

因此，

$$\text{ctg } A = \frac{b^2 + c^2 - a^2}{4S}.$$

如果按照这个公式，我们通过三角形$ctg B$和$ctg C$的边来表达，并将得到的表达式相加，那么我们就得到恒等式

$$\text{ctg } A + \text{ctg } B + \text{ctg } C = \frac{a^2 + b^2 + c^2}{4S}.$$

示例 3. 证明对于任何三角形，以下不等式成立：

a) $\sin \frac{A}{2} \leqslant \frac{a}{2\sqrt{bc}}$,

b) $\text{tg} \frac{A}{2} \leqslant \frac{a}{2h_a}$,

$a, b, c$ 是三角形 ABC 的边，$h_a$ 是从顶点 A 绘制的高度。

解决方案。 a) 式(*)可以写成：

$$a^2 = (b - c)^2 + 2bc (1 - \cos A).$$

如果现在将$1 - \cos A$替换为$2\sin^2 \frac{A}{2}$，则我们得出以下公式

$$a^2 = (b - c)^2 + 4bc \sin^2 \frac{A}{2}.$$ (2)

然后

$$a^2 \geqslant 4bc \sin^2 \frac{A}{2},$$

或者

$$\sin \frac{A}{2} \leqslant \frac{a}{2\sqrt{bc}},$$

并且只有在$b = c$时才实现平等。

6) 公式（2）可以很容易地简化为这种形式：

$$a^2 = (b - c)^2 + 4S \text{tg} \frac{A}{2}.$$ (3)

为此，执行以下转换就足够了：

$$bc \sin^2 \frac{A}{2} = \frac{2S}{\sin A} \sin^2 \frac{A}{2} =$$

$$= \frac{2S\sin^2 \frac{A}{2}}{2\sin \frac{A}{2}\cos \frac{A}{2}} = S \text{tg} \frac{A}{2}.$$

公式（3）隐含了不等式$a^2 \geqslant 4S \text{tg} \frac{A}{2}$，因此$tg \frac{A}{2} \leqslant \frac{a^2}{4S}$。

考虑到$S = \frac{1}{2} ah_a$，我们得到不等式$tg \frac{A}{2} \leqslant \frac{a}{2h_a}$。

$$a^2 = b^2 + c^2 - 2bc \cos A$$

使用类型 1-3 之一的简单转换。类似地导出以下关系式：

$$a^2 = (b + c)^2 - 4bc \cos^2 \frac{A}{2},$$ (4)

$$a^2 = (b + c)^2 - 4S \text{tg} \frac{A}{2}.$$ (5)

示例 4. 计算给定边的三角形的面积。

⟦folio 31⟧

解决方案。让我们将对应关系（3）和（5）重写如下：

$$4S \mathrm{tg} \frac{A}{2} = a^2 - (b - c)^2,$$
$$4S \mathrm{ctg} \frac{A}{2} = (b + c)^2 - a^2.$$

如果三角形的周长用 2p 表示，则
$$a^2 - (b - c)^2 = (a + b - c) \times (a + c - b) = 4(p - b) \times (p - c),$$
$$(b + c)^2 - a^2 = (a + b + c) \times (b + c - a) = 4p(p - a).$$

因此，

$$S \mathrm{tg} \frac{A}{2} = (p - b)(p - c),$$
$$S \mathrm{ctg} \frac{A}{2} = p(p - a).$$

$$S^2 = p(p - a)(p - b)(p - c).$$

示例 5. 给定一个边为 a 的等边三角形 ABC。通过位于AB边上的点M，画出与三角形的边AC和BC平行的直线，并分别在点K和L处与这些边相交。如果 KL = d (图 2)，则计算三角形 KLM 的面积。

解决方案。让我们分别用 x 和 y 表示线段 KM 和 LM。三角形 AKM 和 BLM 是等边三角形，因此

![Рис. 2.](image)

示例 6. 使用最短长度的线段将该三角形分成两个相等的部分。

解决方案。让线段MN将三角形ABC的面积分成两半（图3）。若M、N点位于角BAC的边上，S为三角形ABC的面积，则三角形AMN的面积等于$\frac{1}{2}S$，根据式（3）

$$MN^2 = (AM - AN)^2 + 2S \mathrm{tg} \frac{A}{2},$$

从这里我们立即发现，对于 AM = AN，线段 MN 的最短长度等于 $\sqrt{2S \mathrm{tg} \frac{A}{2}}$。

⟦folio 32⟧

图 3.

线段 AM 的长度很容易计算，因为$S = AM^2 \sin A = \frac{1}{2} bc \sin A,$

在哪里

$$AM = \sqrt{\frac{bc}{2}}.$$

显然，如果线段 MN 的两端位于三角形的 B 角边上，则该线段的最短长度为 $\sqrt{2S \mathrm{tg} \frac{B}{2}}.$

设 $a < b < c,$ 那么

$$\sqrt{2S \mathrm{tg} \frac{A}{2}} < \sqrt{2S \mathrm{tg} \frac{B}{2}} < \sqrt{2S \mathrm{tg} \frac{C}{2}}.$$

对于Posny来说，最小线段MN的长度等于$\sqrt{2S \mathrm{tg} \frac{A}{2}}.$，同时$AM = AN = \sqrt{\frac{bc}{2}}.$

构造段 MN 总是可能的；从 $c < a + b < 2b,$ 然后 $\sqrt{\frac{bc}{2}} < b$ 甚至更$\sqrt{\frac{bc}{2}} < c.$

1. 在角$60^\circ$的三角形的边上，在其构造之外有等边三角形。证明给定三角形和在 $60^\circ,$ 角的对边构造的三角形的面积之和等于这两个三角形的面积之和。

2. 在三角形 $ABC,$ 的边上，角度 $C$ 等于 $135^\circ,$，在其外部构造正方形 $ABMN, BCKL$ 和 $CAPQ.$。证明六边形$KLMNPQ$的面积等于正方形$ABMN.$面积的两倍

3. 如果$AB=5, BC=2$且其对角线之间的角度为$45^\circ.$，则计算平行四边形$ABCD,$的面积

4. 用三角形的边来表达三角形折线角的三角函数。

5. 证明三角形$ABC$的边满足等式$a^2 + b^2 = 2c^2$当且仅当三角形的角度通过关系式相关

$$\text{ctg} A + \text{ctg} B = 2 \text{ctg} C.$$

6. 三角形 $ABC$ 的边由依赖关系 $a^2 + b^2 = nc^2,$ 连接，其中 $n>1.$ 证明 $\cos C \geq \frac{n-1}{n}.$

7. 证明任意三角形的内角满足不等式。

$$\text{tg} \frac{A}{2} + \text{tg} \frac{B}{2} + \text{tg} \frac{C}{2} \leq \text{ctg} A + \text{ctg} B + \text{ctg} C.$$

8. 边长为 $a.$ 的等边三角形内接于圆。证明$x^2 + y^2 + z^2 = 2a^2,$，其中$x, y, z$是圆上任意点到三角形顶点的距离。

9. 圆内接于三角形 $ABC$ 并在点 $M$ 和 $N.$ 处与边 $AB$ 和 $AC$ 相切 如果 $\frac{AM}{MB} = \frac{1}{6}$ 和 $\frac{AN}{NC} = \frac{1}{7}.$ 则确定三角形的角度 $A$

10. 已知角 $A$ 以及内切圆的切点将边 $BC.$ 分成的线段 $m$ 和 $n,$，求三角形 $ABC,$ 的面积

11. 给定一条线 $l$ 和不在其上的两个点 $A$ 和 $B,$。在直线 $l$ 上找到$M,$，其中比率 $\frac{AM}{BM}$ 取 $a)$ 的值最大； $6)$最有意义。

12. 证明任意三角形的内角满足不等式

$$\sin \frac{A}{2} \sin \frac{B}{2} \sin \frac{C}{2} \leq \frac{1}{8}.$$

13. 围绕半径为 $r$ 的圆描述一个底边为 $a$ 和 $b$ ($a > b$) 的梯形。计算其边之间的角度。

14*) 证明对于任何三角形$ABC$，以下关系成立：

$$16S^2 = (a^2 + c^2 - b^2)(a^2 + b^2 - c^2) + (b^2 + c^2 - a^2)(a^2 + b^2 - c^2) + (b^2 + c^2 - a^2)(a^2 + b^2 - b^2).$$

*) 这个问题是由我们的读者 V.P. 发送的。加斯帕林。
