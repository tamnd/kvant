---
id: 1971-12-novikov-metod-ploschadey-fcba28d8
issue: kvant_1971_12
year: 1971
number: "12"
title: 面积法
authors:
  - Новиков И. Д.
rubric: praktikum-abiturienta
rubric_sub: Практикум абитуриента
page_first: 43
page_last: 48
page_labels: 41-46
tag: E30X
lang: zh
source: kvant_digital
extraction: vision
content_sha256: f0cc807cb98b61cc66c947254bdff58725ac6c5376258501349454ebdb4bef29
prompt_sha256: draft-1
translated_from: content/ru/1971/12/articles/09_novikov-metod-ploschadey-fcba28d8.md
source_content_sha256: 755d1fe537be7c22e90f01e39efa4ec139f396fb416e17b91ac6188746039d9c
translation_model: draft
translation_run: zh-draft-2026-10-31
translation_quality: draft
---

⟦folio 41⟧

解决几何问题的艺术有点让人想起三重奏或洛佐主义——有时，即使知道问题的解决方案，也很难理解如何想出它。几乎每个有点困难的几何问题都需要单独的方法。但我希望有一个通用的解决方法，它也可以让我在不明确执行计算的情况下“冒险”到底解决方案。

不幸的是，没有这样的通用方法。但有些技术可以应用于许多问题。我们将考虑其中之一。

让我们从一个非常简单的问题开始，我们将通过两种方式解决这个问题。

图 1. AC = 2, BC = 3, ⇒ ACD = ⇒ DCB = = 45°.

问题 1. 求边 AC = 2 且 BC = 3 (图 1) 的直角三角形 ACB 的二分切线 CD。

解一. 根据毕达哥拉斯定理 AB = √AC² + BC² = √13。根据三角形内角二等分线的性质

$$\frac{AD}{BD} = \frac{AC}{BC}.$$

根据等式 AD + DB = √13，我们得到 AD = \frac{2}{5} √13。接下来，很容易求出角度 A 的余弦：

$$\cos A = \frac{AC}{AB} = \frac{2}{\sqrt{13}}.$$

仍需应用余弦定理来确定三角形 ACD 的边 CD：

$$CD^2 = AC^2 + AD^2 - 2AC \cdot AD \cos A = \frac{72}{25}, CD = \frac{6}{5} \sqrt{2}.$$

解决方案二.我们用不同的方式来计算三角形ACB的面积。一方面，S△ACB = \frac{1}{2} AC \cdot BC = 3。另一方面，

$$S△ACB = S△ACD + S△DCB = \frac{1}{2} AC \cdot CD \sin 45^\circ + \frac{1}{2} BC \cdot CD \sin 45^\circ = \frac{5 \sqrt{2}}{4} CD.$$

⟦folio 42⟧

将$S_{\Delta ACB}$的两个给定表达式的部分相等，我们得到$CD = \frac{6}{5}\sqrt{2}$。

第二种解决方案显然更短、更简单。而且，在更一般的情况下，它很容易导致目标。要验证这一点，请亲自了解这两种解决方案如何变化，如果

任务 2. 如果 $AC=b$、$BC=a$、$\Rightarrow ACB=\alpha$，求三角形 $ACB$ $C$ 的平分线 $CD$。 （说：$CD = \frac{2ab}{a+b}\cos \frac{\alpha}{2}$）

然而，第二种解决方案的主要优点是其意识形态的“独创性”。在第一个解决方案中，构建了一定的三角形元素“链”：该链的每个元素都是根据问题数据和已找到的其他元素计算的。链的最后一个元素是所需的数量（在本例中为平分线 $CD$）。同时，在确定期望值时，并不能立即明确需要哪些元素，即必须预先计算哪些元素。

在需要找到的数量的第二个解决方案中，我们通过根据三角形的已知和所需元素写出三角形面积的表达式来获得方程。这个例子——比较三角形面积的不同表达式——结果非常富有成效。为什么专门针对该地区？事实上，三角形的平面可以通过该三角形元素的各种组合来非常简单地表达。

在给出以下示例之前，让我们回顾一下这些表达式中最重要的一个。首先，让我们就符号达成一致。在三角形$ABC$中：

$a, b, c$ - 边，对角分别为$A, B$和$C$；

分别为 $h_a, h_b, h_c$ — 高度、$m_a, m_b, m_c$ — 中位数、$l_a, l_b, l_c$ — 平分线；

$r$——内切圆半径；

$R$——外接圆半径；

$p$——半周长；

$S$ 是平面三角形$ABC$。

图 2. 关于内切圆的圆心。

我们将使用的公式用这种表示法编写如下：

$$S = \frac{ah_a}{2},$$

$$S = \frac{ab \sin C}{2},$$

$$S = \frac{a^2 \sin B \sin C}{2 \sin A},$$

$$S = \frac{abc}{4R},$$

$$S = \sqrt{p(p-a)(p-b)(p-c)},$$

$$S = pr.$$

所有这些关系都是从学校课程中得知的，因此我们不会详细证明它们，而仅限于一些评论。由(2)推导出公式(3)和(4)，可以利用正弦定理：

$$\frac{a}{\sin A} = \frac{b}{\sin B} = \frac{c}{\sin C} = 2R.$$

公式（5）（海伦公式）有时以变换形式使用更方便：

$$S = \frac{1}{4} \times \sqrt{2a^2b^2 + 2a^2c^2 + 2b^2c^2 - a^4 - b^4 - c^4}.$$

式(6)很容易由非常(图2)等式得到：

$$S_{\Delta ABC} = S_{\Delta AOB} + S_{\Delta BOC} + S_{\Delta COA}.$$

现在让我们考虑更多的问题。在每个问题中，面积法的应用都会产生一个简短而明显的解决方案。

⟦folio 43⟧

任务 3. 在边长为 a 的正三角形内，取任意一点 M。求从该点到三角形各边的距离之和。

解决方案。需要求出从 M 点分别垂到边 AB、BC 和 CA 的垂线 MP、MQ 和 MR (图 3) 的长度之和。如果我们将点M与三角形的顶点连接起来，那么很明显$S_{\Delta ABC} = S_{\Delta AMB} + S_{\Delta BMC} + S_{\Delta CMA}$。使用正三角形面积公式 $S_{\Delta ABC} = \frac{a^2 \sqrt{3}}{4}$ 并将其替换（用公式（1））。

$$S_{\Delta AMB} = \frac{1}{2} a \cdot MP,$$

$$S_{\Delta BMC} = \frac{1}{2} a \cdot MQ,$$

$$S_{\Delta CMA} = \frac{1}{2} a \cdot MR,$$

我们立即收到答复：

$$MP + MQ + MR = \frac{a \sqrt{3}}{2}.$$

任务 4. 线 AD 将三角形 ABC 一分为二。证明三角形ABC的内接圆的半径r分别小于三角形ABD和ACD的内切圆的半径$r_1$和$r_2$之和。

解决方案。令 CD 和 CE 为任务条件 (图 5) 中讨论的射线。显然$S_{\Delta ABC} = S_{\Delta ACD} + S_{\Delta DCB} = S_{\Delta ACE} + S_{\Delta ECB}$。

让我们使用公式（2），考虑到$ACD = DCE = ECB = \frac{\alpha}{3}$：

$$\frac{AC \cdot DC \sin \frac{\alpha}{3}}{2} + \frac{DC \cdot BC \sin \frac{2\alpha}{3}}{2} = \frac{AC \cdot EC \sin \frac{2\alpha}{3}}{2} + \frac{EC \cdot BC \sin \frac{\alpha}{3}}{2}.$$

⟦folio 44⟧

图 5.

从这里我们立即得到

$$\frac{DC}{EC} = \frac{AC \sin \frac{2\alpha}{3} + BC \sin \frac{\alpha}{3}}{AC \sin \frac{\alpha}{3} + BC \sin \frac{2\alpha}{3}}$$

$$= \frac{2 \cos \frac{\alpha}{3} + 3}{6 \cos \frac{\alpha}{3} + 1}$$

这是一个更困难的问题的例子。尽管在其中您只需要“求解三角形”，即通过三个已知元素确定其边，但不可能以通常的方式（使用正弦和余弦定理）获得解。

任务 6. 如果 $h_a=6$、$r=2$、$R=5$，则将三角形命名为 ABC。

解决方案和e。让我们利用公式（1）、（4）、（5）和（6），写出以下未知边$a, b, c$的方程组

$$\begin{cases} S = 3a, \\ S = \frac{abc}{20}, \\ S = \frac{1}{4} \sqrt{(a+b+c)(b+c-a)} \times \sqrt{(a+c-b)(a+b-c)}, \\ S = a+b+c. \end{cases}$$

将第一个和最后一个方程各部分的规则等同，我们得到$b+c=2a$。将第一个和第二个方程的部分规则等同，我们得到$bc=60$。最后，使第一个和第三个方程的部分规则相等，我们得到（平方后）

$$144a^2 = (a+b+c)(b+c-a) \times (a+c-b) \times (a+b-c) = [(b+c)^2-a^2] \times [a^2-(b-c)^2] = [(b+c)^2-a^2] \times [a^2-(b+c)^2+4bc] = (4a^2-a^2) \times (a^2-4a^2+240) = 3a^2 (240-3a^2).$$

因此，为了确定$a$，我们得到方程

$$144a^2 = 3a^2 (240-3a^2),$$

从哪里$a=8$。从方程组$b+c=16$，$bc=60$现在很容易找到两对值$b$和$c$（两个答案）：

$$a = 8, b = 6, c = 10 или a = 8, b = 10, c = 6,$$

这是奥丁三角形的几何定义（指定边$b$和$c$）。

在这个例子中，面积法的主要特征尤其清晰可见——它将几何问题“变成”代数问题，将一切简化为求解某些方程组。

任务 7.（MSU，物理学家，1966）证明如果三角形的边长构成一个算术

⟦folio 45⟧

图6a。

梅蒂切切，该三角形的内接圆的中心及其中线的交点位于与三角形的中边平行的直线上。

解决方案。令三角形 ABC 的边形状为 $a \leq b \leq c$。然后根据问题$a+c=2b$的条件。设 $O$ 为内圆圆心，$M$ 为中线 $AA_1$、$BB_1$ 和 $CC_1$ (图 6a) 的交点。

首先，我们推导出三角形$ABC$中线交点$M$的一个有用属性。在 图 6b 上，三角形 ABC 被中线分成 6 个更小的三角形。它们各自的面积等于$\frac{1}{6}$整个三角形的面积$ABC$。这很容易证明：使用

图 66.

式（1），写出等式
$$S_{\triangle BB_1C} = \frac{1}{2} S_{\triangle ABC}, B_1M = \frac{1}{3} BB_1,$$
$$S_{\triangle MCB_1} = \frac{1}{3} S_{\triangle BB_1C} = \frac{1}{6} S_{\triangle ABC}.$$

其余三角形的面积可类似求出。

现在我们求从点 $M$ 到边 $AC$ 的垂线 $MM'$ 的长度：
$$\frac{1}{3} S_{\triangle ABC} = S_{\triangle AMC} = \frac{1}{2} MM' \cdot AC =$$
$$= \frac{1}{2} MM' \cdot b, \frac{1}{3} S_{\triangle ABC} = \frac{1}{3} rp =$$
$$= \frac{1}{3} r \left( \frac{a+b+c}{2} \right) = \frac{1}{3} r \left( \frac{2b+b}{2} \right) =$$
$$= \frac{1}{2} rb,$$

由此$MM'=r$，即$MO \parallel AC$。

在解决立体问题的某些阶段，面积法通常很方便。

任务 8.（MSU，机制，1969） 一个金字塔内接于一个球，边长等于 c。它的底面是一个矩形平面，其各边通过球截面中的圆弧$\alpha$和$\beta$弧度通过侧面的平面连接。确定外接球的半径。

解（图7）。由于内切角改变一半

⟦folio 46⟧

没有它所依靠的弧线，
那
$$\Rightarrow DQC = \frac{\alpha}{2}, \Rightarrow AQD = \frac{\beta}{2}.$$

波兹尼$DC = 2c \sin \frac{\alpha}{4}$，$AD = 2c \sin \frac{\beta}{4}$。

让我们考虑平面 $AQC$ 球的截面。由于球的中心位于该平面内（证明一下！），因此球的半径等于三角形 $AQC$ 外接圆的半径 $R$。但是$AQ = QC = c$和$AC = 2c \sqrt{\sin^2 \frac{\alpha}{4} + \sin^2 \frac{\beta}{4}}$（就像矩形$ABCD$的对角线）。因此，要确定半径$R$，只需使用公式（4）和（5）的三角形$AQC$面积表达式即可。

经过明显的变换，我们得到答案：

$$R = \frac{c}{\sqrt{2 \left( \cos \frac{\alpha}{2} + \cos \frac{\beta}{2} \right)}}.$$

面积法也适用于需要找到几何量的各种类型估计值的问题。

问题9. 直角三角形所描绘的圆的半径与高度降低一倍的比值可以在什么限度内变化？

解决方案。如果$c$是直角三角形$ABC$的斜边，那么我们可以写（见公式（1）和（6））：

$$\frac{ch_c}{2} = pr, \text{откуда} \frac{r}{h_c} = \frac{c}{2p}.$$

因此，有必要评估这种关系

$$\frac{c}{2p} = \frac{c}{a + b + c} = \frac{1}{\frac{a}{c} + \frac{b}{c} + 1} = \frac{1}{\sin A + \sin B + 1}.$$

由于$A + B = 90^\circ$，那么

$$\sin A + \sin B + 1 = \sin A + \cos A + 1 = \sqrt{2} \cos (45^\circ - A) + 1.$$

直角三角形的锐角 $A$ 可以是 0 到 90^\circ 之间的任意值。因此，角度$45^\circ - A$在$-45^\circ$到$+45^\circ$的范围内较小，这可以从余弦的性质容易地获得，而$2 < \sqrt{2} \cos (45^\circ - A) + 1 \leqslant 1 + \sqrt{2}$。

因此，在任何直角三角形中，总是满足许多问题的不定解。当然，它并不能取代所有其他方法，但在开始解决特定问题时不应该忘记它。

练习

1. 求三角形的中线 $m_a$，即其边 $a, b, c$ 的值。
2. 证明在任意三角形中

$$\frac{1}{r} = \frac{1}{h_a} + \frac{1}{h_b} + \frac{1}{h_c}.$$

3. （密歇根州立大学，经济学院，1969 年）。在锐角三角形$ABC$中，给定：从顶点$B$中线$BD = m$绘制$AB = c$。角$BDA$是锐角并且等于$B$。计算三角形$ABC$的面积。
4. （密歇根州立大学心理学系，1969 年）。给定一个等边直角三角形。证明与斜边和腿的延长线相切的圆的半径等于斜边与三角形中所描述的圆的半径之和。
5. 已知在三角形$ABC$中：

$$S_{\triangle ABC} = 16, m_a = 6, m_b = 4.$$

证明中线$m_a$和$m_b$垂直。
6. 证明从不等边三角形内任意点到该三角形边的距离之和包含在最小点和最低点之间。

7. 直线$ABCDA_1B_1C_1D_1$（其中$AA_1, BB_1, CC_1, DD_1$为侧边）的底$ABCD$是边$a$上的菱形和锐角$φ$，线的高度为$h$。求从顶点 $B_1$ 到侧面 $ADD_1A_1$ 对角线 $A_1D$ 的距离。
