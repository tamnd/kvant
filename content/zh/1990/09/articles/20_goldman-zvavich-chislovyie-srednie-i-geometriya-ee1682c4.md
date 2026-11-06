---
id: 1990-9-goldman-zvavich-chislovyie-srednie-i-geometriya-ee1682c4
issue: kvant_1990_9
year: 1990
number: "9"
title: 数值方法和几何
authors:
  - Гольдман А. М.
  - Звавич Л. И.
rubric: praktikum-abiturienta
rubric_sub: Практикум абитуриента
page_first: 64
page_last: 67
page_labels: 62-65
lang: zh
source: kvant_digital
extraction: vision
content_sha256: 62014de14029965354d5d59d494ac8cb19db9c71c494ddb25f3de03697b09e11
prompt_sha256: draft-1
translated_from: content/ru/1990/09/articles/20_goldman-zvavich-chislovyie-srednie-i-geometriya-ee1682c4.md
source_content_sha256: 09c320b87dc6e4aedd8cb26a59ec8dab4160bd4b44f86aa119c36adc55aa26b6
translation_model: draft
translation_run: zh-draft-2026-11-06
translation_quality: draft
---

⟦folio 62⟧

---
running_head:
folio:
---

一个简单的 $V_2$ 结果等于速度 $V_1$ 和 $V_2$ 的调和平均值，即 $\frac{2V_1V_2}{V_1+V_2}$（确保这一点）。

广为人知并经常用于解决不等式问题$\frac{a+b}{2} \geqslant \sqrt{ab}$。事实证明，对于任何正 $a$ 和 $b$，以下不等式成立：

$$\frac{2ab}{a+b} \leqslant \sqrt{ab} \leqslant \frac{a+b}{2} \leqslant \sqrt{\frac{a^2+b^2}{2}},$$

当且仅当 $a=b$ 时，所有不平等都变成平等。每个不等式都可以使用数值不等式的性质来证明（自己动手！）。

平均值的定义自然延伸到正数$a_1, a_2, \dots, a_n$的情况$n$：

$$H(a_1, \dots, a_n) = \frac{n}{\frac{1}{a_1} + \frac{1}{a_2} + \dots + \frac{1}{a_n}}$$

- 调和平均值，

$$G(a_1, \dots, a_n) = \sqrt[n]{a_1 a_2 \dots a_n}$$

— 几何平均值，

$$A(a_1, \dots, a_n) = \frac{a_1+a_2+\dots+a_n}{n}$$

——算术平均值，

$$Q(a_1, \dots, a_n) = \sqrt{\frac{a_1^2+a_2^2+\dots+a_n^2}{n}}$$

- 均方。

A.戈德曼，L.兹瓦维奇

显然，你经常遇到两个正数的算术平均值$\frac{a+b}{2}$和几何平均值$\sqrt{ab}$这样的概念。您可能已经开始使用其他平均值进行计算：两个正数的调和平均值 $\frac{2ab}{a+b}$ 和均方 $\sqrt{\frac{a^2+b^2}{2}}$。因此，游客以$V_1$的速度行驶一定距离，并以$V_2$的速度回程，其平均速度等于$V_1$和$V_2$的调和平均值，即$\frac{2V_1V_2}{V_1+V_2}$（请确保这一点）。

广为人知并经常用于解决不等式问题$\frac{a+b}{2} \geqslant \sqrt{ab}$。事实证明，对于任何正 $a$ 和 $b$，以下不等式成立：

$$\frac{2ab}{a+b} \leqslant \sqrt{ab} \leqslant \frac{a+b}{2} \leqslant \sqrt{\frac{a^2+b^2}{2}},$$

当且仅当 $a=b$ 时，所有不平等都变成平等。每个不等式都可以使用数值不等式的性质来证明（自己动手！）。

平均值的定义自然延伸到正数$a_1, a_2, \dots, a_n$的情况$n$：

$$H(a_1, \dots, a_n) = \frac{n}{\frac{1}{a_1} + \frac{1}{a_2} + \dots + \frac{1}{a_n}}$$

- 调和平均值，

$$G(a_1, \dots, a_n) = \sqrt[n]{a_1 a_2 \dots a_n}$$

— 几何平均值，

$$A(a_1, \dots, a_n) = \frac{a_1+a_2+\dots+a_n}{n}$$

——算术平均值，

$$Q(a_1, \dots, a_n) = \sqrt{\frac{a_1^2+a_2^2+\dots+a_n^2}{n}}$$

- 均方。

A.戈德曼，L.兹瓦维奇

显然，你经常遇到两个正数的算术平均值$\frac{a+b}{2}$和几何平均值$\sqrt{ab}$这样的概念。您可能已经开始使用其他平均值进行计算：两个正数的调和平均值 $\frac{2ab}{a+b}$ 和均方 $\sqrt{\frac{a^2+b^2}{2}}$。因此，游客以$V_1$的速度行驶一定距离，并以$V_2$的速度回程，其平均速度等于$V_1$和$V_2$的调和平均值，即$\frac{2V_1V_2}{V_1+V_2}$（请确保这一点）。

⟦folio 63⟧

---
running_head:
folio:
---

一般情况下，不等式$H \leq G \leq A \leq Q$是有效的，但证明起来要困难得多。我们将证明不等式，它指的是两个正数的几何平均值。然而，不等式$\frac{a+b}{2} \geq \sqrt{ab}$的证明是基于这样的事实：直角三角形的高度是直角三角形的直角边在斜边（图1）上的投影的几何平均值。

然而，使用图1的配置，并不清楚如何比较几何平均数与调和平均数，以及算术平均数与平方平均数。同时，有一个数字，其中两个数字$a$和$b$的所有平均值都可以“活”地看到——这是底边为$BC=a$、$AD=b$的梯形$ABCD$（对于定义，我们假设$b>a$）。算术平均值是梯形中线的长度。通过完成以下练习，您将看到其余的平均值；第一个是一个有用的引理，有助于处理其他引理。

在妻子那里。设$EF$为长度为$x$的线段，其两端分别位于梯形$ABCD$的侧边$AB$和$CD$，平行于其底边（图2）。

1. 如果您知道$BE/EA=\lambda$，请找到$x$。 （答案：$x=\frac{a+\lambda b}{1+\lambda}$）。笔记。参见图 2：$GH \parallel AB$，三角形$FCG$和$FDH$相似。

2. 如果线段 $EF$ 通过对角梯形的交点，则求 $x$。 （答案：$x=\frac{2ab}{a+b}$）。笔记。使用练习 1 和 $BE/ED=a/b$。

3. 如果梯形 $AEFD$ 和 $EBCF$ 相似，求 $x$。 （答案：$x=\sqrt{ab}$）。

4. 如果梯形 $AEFD$ 和 $EBCF$ 相等，则求 $x$。 （答案：$x=\sqrt{\frac{a^2+b^2}{2}}$）。笔记。让线 $AB$ 和 $CD$ 相交于点 $P$ (图 3)。然后$\frac{S_2}{S_1+S_2}=\frac{a^2}{x^2}; \frac{S_2+2S_1}{S_2+S_1}=\frac{b^2}{x^2}$。将这些等式相加，我们就得到了答案。

所以，在梯形$ABCD$中，我们提到的所有平均数$a$和$b$都出现了。仍有待证明不等式（*）。

乌拉真亚。设$EF$、$MN$、$KL$为对应的线段（构建绘图）。

然后$\frac{BE}{EA}=\frac{a}{b}; \frac{BM}{MA}=\sqrt{\frac{a}{b}}; \frac{BK}{KA}=1,$但是$\frac{a}{b}<\sqrt{\frac{a}{b}}<1$。

6. 证明$\frac{a+b}{2} \leq \sqrt{\frac{a^2+b^2}{2}}$。

提示：如果$KL$是梯形的中线，则$S_{BCLK}<S_{AKLD}$。

因此，我们已经证明了不等式 (*) 并确保对于 $a<b$ 构造了所有不等式。很容易看出，如果任意两个线段

⟦folio 64⟧

---
running_head:
folio:
---

我们比较的长度相等，则 $ABCD$ 是平行四边形，因此，所有不等式 (*) 都变成等式。

这是比较平均值的另一种方法。考虑一个直角三角形 $ABC$，其边为 $BC = a$、$AC = b$ 和 $a > b$。令 $\sigma_M$ 为从斜边 $AB$ 上的某个点 $M$ 到三角形边的距离之和。

练习 7. 证明 $\sigma_N > \sigma_M$ 当且仅当点 $N$ 位于点 $M$ (图 4)“上方”。

指示 e． $\sigma_M = KN_1 + KM_2 + KM$，$\sigma_N = N_2N + NK + KN_1 = KN_1 + KM_2 + KN$，但是$KN > KM$。

让角 $C$ 的平分线与斜边相交于点 $H$ (图 5)。那么四边形 $CH_2HH_1$ 是边长为 $\frac{ab}{a+b}$ 的正方形，因此 $\sigma_H = \frac{2ab}{a+b}$ 是调和平均值

一些数字$a$和$b$，以及$BH/AH = b/a$。如果 $O$ 是斜边的中点，则$\sigma_O = \frac{a+b}{2}$，并且点 $O$ 位于点 $H$ ($\frac{b}{a} < 1$) 上方。因此$\sigma_O > \sigma_H$，即$\frac{2ab}{a+b} < \frac{a+b}{2}$。

她是对的。

8. 考虑斜边$AB$点$G$，其中$\sigma_G = \sqrt{ab}$。证明点$G$位于点$O$和$H$之间，即$\sigma_O > \sigma_G > \sigma_H$。

9. 令 $P$ 为角 $C$ (图 6) 的平分线上的一点，其中 $CP = \frac{1}{2} AB = CO = \frac{1}{2}\sqrt{a^2+b^2}$。还令$AB$上的点$Q$使得线$QP$垂直于$CP$。证明$\sigma_Q = \sqrt{\frac{a^2+b^2}{2}}$，然后验证不等式$\sigma_Q > \sigma_O$的有效性。

U卡扎和e。利用 $PP_2 = PP_1$ 和 $\angle QPP_2 = 45^\circ$ 的事实（参见 图 6）。

还有第三个关于平均值不等式的证明，我们为您提供了一个非常有用的练习。

她是对的。

10. 直径为 $a$ 和 $b$ 的圆向外接触。证明它们的共同外切线在接触点之间的线段等于直径的几何平均值。

11. 直径为$a$和$b$的圆没有公共点，它们的公共外切线在切点之间的线段等于直径的算术平均值。证明圆心之间的距离等于直径的均方根。

⟦folio 65⟧

---
running_head:
folio:
---

从练习 10 得出不等式 $\sqrt{ab} \leq \frac{a+b}{2}$，从练习 11 得出不等式 $\frac{a+b}{2} \leq \sqrt{\frac{a^2+b^2}{2}}$。

思考如何使用这个配置来证明调和和几何平均值的不等式。 （提示：在练习 10 的配置中，找到从圆的接触点到它们的公切线的距离，并利用顶点位于三个接触点的三角形是直角三角形的事实。）
