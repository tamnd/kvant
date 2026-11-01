---
id: 1979-10-ovchinnikov-esli-promezhutok-ne-zamknut-91134735
issue: kvant_1979_10
year: 1979
number: "10"
title: 如果间隙没有闭合...
authors:
  - Овчинников С. В.
rubric: praktikum-abiturienta
rubric_sub: Практикум абитуриента
page_first: 46
page_last: 50
page_labels: 44-48
tag: 7LJF
lang: zh
source: kvant_digital
extraction: vision
content_sha256: 4da73fb20727f82a2c638a89fdd02c990ac2f12981072a9743de44ff8e3add59
prompt_sha256: draft-1
translated_from: content/ru/1979/10/articles/16_ovchinnikov-esli-promezhutok-ne-zamknut-91134735.md
source_content_sha256: c5b7668e7e75feed94392623f32f6f5924bc28e096d68b8600defcae1093263f
translation_model: draft
translation_run: zh-draft-2026-11-01
translation_quality: draft
---

⟦folio 44⟧

S·奥夫钦尼科夫

如果间隙没有闭合...

在解决寻找最大（或最大）值的几何问题时，有时会忘记，由于其几何意义，所寻求的量通常满足某些限制。在许多此类问题中，对在其域边界处所考虑的函数的研究本身被确定为解决方案的现有部分。

以下是此类研究的示例。

问题1. 将矩形周长值的名称写在给定的圆弧段中，使其两个顶点位于给定圆弧段的弦上。

解决方案。设 $2a$ 为线段弦长，$h$ 为线段高度 (图 1)。容易看出圆的半径是$R = \frac{a^2 + h^2}{2h}$。

$x$表示内接矩形底边长度的一半

图 1.

因此，求第二条边的长度：

$$y = \sqrt{R^2 - x^2} - R + h.$$

从这里我们找到矩形的周长$P$作为变量$x$的函数：

$$P(x) = 4x + 2\sqrt{R^2 - x^2} - 2R + 2h.$$

此外，如果$h \leq R$则为$x \in ]0; a[$，如果$h > R$则为$x \in ]0; a[$（检查！）。

让我们找到函数$P$的临界点并研究它们。我们有

$$P'(x) = 4 - \frac{2x}{\sqrt{R^2 - x^2}}.$$

从这里

$$P'(x) = 0 \Leftrightarrow 2\sqrt{R^2 - x^2} = x.$$

求解最后一个方程，我们找到临界点$x_0 = \frac{2\sqrt{5}}{5}R$。

函数$\frac{2x}{\sqrt{R^2 - x^2}}$是年龄。因此，$P'(x)$的导数在$x < x_0$处为正，在$x > x_0$处为负。因此，点$x_0$是函数$P$的极大点。仍有待研究的问题是，该点何时给出最大周长值，以及当未达到该点的最大值时会发生什么。在本研究中，定义函数$P$的区间起着重要作用。例如，对于 $h \leq R$，这是间隔 $]0; a[$，对于 $h > R$，结果间隔是 $]0; a[$。

在这两种情况下，如果临界点$x_0$属于区间$]0; a[$，则函数$P$将在其中取最大值。我们有

$$x_0 \in ]0; a[ \Leftrightarrow \frac{2\sqrt{5}}{5}R < a \Leftrightarrow \frac{\sqrt{5}}{5} \cdot \frac{a^2 + h^2}{h} < a.$$

解最后一个方程，我们找到$\frac{h}{a} \in \left[ \frac{\sqrt{5} - 1}{2}; \frac{\sqrt{5} + 1}{2} \right]$。

对于所有这些值$a$和$h$最大周长值等于

$$P(x_0) = \frac{(\sqrt{5} - 1)a^2 + (\sqrt{5} + 1)h^2}{h}.$$

⟦folio 45⟧

现在让临界点$x_0$不属于区间$]0; a[$，即$x_0 \geqslant a$。在这种情况下，乘积 $P'(x)$ 对于 $]0; a[$ 的所有 $x$ 均为正，并且函数 $P$ 在区间 $]0; a[$ 上返回。

让$h \leqslant R$。与条件 $x_0 \geqslant a$ 一起，我们得到 $\frac{h}{a} \leqslant \frac{\sqrt{5}-1}{2}$。

由于在$h \leqslant R$处，函数$P$定义在区间$]0; a[$上，因此我们得出结论，它没有达到最大值。

如果$h > R$，则与条件$x_0 \geqslant a$一起我们得到$\frac{h}{a} \geqslant \frac{\sqrt{5}+1}{2}$。由于在这种情况下，函数$P$是在半文字区间$]0; a[$上定义的，因此它在$x = a$处达到最大值。该值为$P(a) = 4a + 2 \cdot \frac{h^2 - a^2}{h}$。

让我们对所获得的结果给出清晰的几何说明。让我们在半径为 $R$ 的圆中选择两个平行的“关键”弦，距离圆心 (图 2) 的距离为 $\frac{\sqrt{5}}{5} R$，并将它们构建为一个矩形。我们将仅考虑弦与所选弦平行的“上”段。

如果给定线段的弦位于所选弦之间，则 $a > \frac{2\sqrt{5}}{5} R$ 和我们线段中内接的最大周长矩形是该线段与在所选弦上构建的矩形的交集（参见 图 2）。

如果给定片段的和弦高于两个选定的和弦，则$h < R$和$a \leqslant \frac{2\sqrt{5}}{5} R$；在这种情况下，内接矩形的周长不会达到最大值（图3）。

最后，如果给定片段的和弦高于两个选定的和弦，则$h > R$和$a \leqslant \frac{2\sqrt{5}}{5} R$；在这种情况下，最周长的内接矩形以此弦为底 (图 4)。

图 5.

任务 2. 从具有截止“行走”(图 5) 的矩形中，您需要切割一个具有最平坦区域的矩形，与该矩形的边平行。

解决方案。让我们引入一个坐标系，如图6所示，并继续线性“介质”，直到与坐标轴相交。让

⟦folio 46⟧

它与坐标轴的交点是$A(a, 0)$和$B(0, b)$。让我们解决以下辅助问题：将一个面积最大的矩形内接于三角形AOB，其中一个顶点为$O$。设辅助矩形的大小为$x$。那么它的高度就是$b - \frac{b}{a}x$。因此，矩形的面积被视为 $x$ 的函数，为

$$S(x) = x \left( b - \frac{b}{a}x \right).$$

显然，$S(x)$在$x_0 = \frac{a}{2}$处取最大值。在这种情况下，函数 $S$ 在结果间隔上返回 $0; \frac{a}{2}$ 并在结果间隔上杀死 $\left[ \frac{a}{2}; a \right]$。

对函数 $S$ 的研究使我们能够对原始问题给出以下可视化解决方案。如果线段$[AB]$的中间$K$属于“切割”$[CD]$，则应将其作为所需矩形的顶点。如果点$K$位于切割$[CD]$的“上方”，则点$C$应作为所需矩形的顶点。如果它位于切割$[CD]$“下方”，则将点$D$视为所需矩形的顶点。

问题 3. 将总表面积最大的圆柱体悬挂在圆锥体中，圆锥体的主截面顶点处的角度为 $2\alpha$，底面半径为 $R$。

解决方案。 图 7 显示了该锥体的已掌握部分。用$x$表示悬挂圆柱体底部的半径，我们很容易发现它的高度（$R-x$）stg$\alpha$。因此，作为变量 $x$ 的函数，总表面积为

$$S(x) = 2\pi \cdot \text{ctg} \alpha \left[ (\text{tg} \alpha - 1) x^2 + Rx \right].$$

该函数由区间 $]0; R[$ 上的问题条件定义。对于$tg \alpha \neq 1$，我们很容易找到临界点$x_0 = \frac{R}{2(1-tg \alpha)}$函数$S$。

根据临界点相对于区间$]0; R[$的位置，可能存在三种情况：

1) $x_0 < 0 \Leftrightarrow \text{tg} \alpha > 1$.

在这种情况下，显然，函数$S$在区间$]0; R[$上递增。在这种情况下，函数$S$未达到其最大值。

2) $x_0 \in ]0; R[ \Leftrightarrow 0 < \frac{R}{2(1-tg \alpha)} < R \Leftrightarrow \text{tg} \alpha < \frac{1}{2}$.

在这种情况下，临界点$x_0$显然是函数$S$的最大值点，并且在区间$]0; x_0]$上，函数$S$在区间$[x_0; R[$杀死；因此，该函数的最大值为$S(x_0) = \frac{\pi R^2 \cdot \text{ctg} \alpha}{2(1-tg \alpha)}$。

3) $x_0 \geqslant R \Leftrightarrow \frac{1}{2} \leqslant \text{tg} \alpha < 1$.

在这种情况下，函数$S$在区间$]0; R[$上递增。总结函数$S$的研究，我们可以说对于$tg \alpha < \frac{1}{2}$，总表面积最大的圆柱体可以内接于圆锥体。如果$tg \alpha \geqslant \frac{1}{2}$，那么函数$S$的值可能是开区间$]0; 2\pi R^2$（“代数和分析的开始10”，第84页）并且函数$S$没有达到其最大值。

问题 4. 半径为 $R$ 的圆内切三角形的一个角等于 $\alpha$。找到最多的

⟦folio 47⟧

颈部 三角形的长度和高度的值。

解决方案e.让我们用 $a$、$b$ 和 $c$ (图 8) 表示三角形边的长度，与边 $a$ 相对的空角等于 $x$。

显然$x \in ]0; \pi - \alpha[$。请注意，条件并不表明我们正在讨论三角形的三个高度中的哪一个。因此，在求解“任意”时，需要找到每个高度的长度最大值，然后从找到的值中确定等于$2R\cos^2\frac{\alpha}{2}$的最大值。

分别用$h_a$、$h_b$和$h_c$表示三角形到边$a$、$b$和$c$的高的长度，我们将它们计算为角度$x$的函数。利用正弦定理和三角形平面的公式，我们发现

$$h_a(x) = \frac{bc}{a}\sin x = 2R\sin \alpha \sin (x + \alpha),$$

$$h_b(x) = \frac{ac}{b}\sin (x + \alpha) = 2R\sin \alpha \sin x,$$

$$h_c(x) = \frac{ab}{c}\sin \alpha = 2R\sin x \sin (x + \alpha).$$

考虑 $x \in ]0; \pi - \alpha[$ 的函数 $h_a$。显然，在$\alpha < \frac{\pi}{2}$，该函数在$x_0 = \frac{\pi}{2} - \alpha$达到最大值$2R\sin \alpha$。

如果$\alpha \geq \frac{\pi}{2}$，则函数$h_a$在区间$]0; \pi - \alpha[$杀死并且没有意义。类似地，我们发现$\alpha < \frac{\pi}{2}$的函数$h_b$在$x_1 = \frac{\pi}{2}$处达到最大值$2R\sin \alpha$，但对于$\alpha \geq \frac{\pi}{2}$它没有值。

考虑结束函数$h_c$。 $h_c'(x) = 2R[\cos x \cdot \sin (x + \alpha)] + \sin x \cdot \cos (x + \alpha)] = 2R \cdot \sin (2x + \alpha)$。显然，在区间 $]0; \pi - \alpha[$ $h_c'(x) = 0 \Leftrightarrow \sin (2x + \alpha) = 0 \Leftrightarrow 2x + \alpha = \pi$ 上。

临界点是$x_2 = \frac{\pi - \alpha}{2}$。这次 $\alpha \in ]0; \pi - \alpha[$ 对于任何有效的 $\alpha$。区间$]0; \pi - \alpha[$后面是正数，右边是负数。因此，在点 $x_2$ 处，函数 $h_c$ 达到最大值，等于 $2R\cos^2\frac{\alpha}{2}$。

因此，对于角度$\alpha$的每个值，我们只需从找到最多的高度值中找到最多的值即可。

我们首先考虑$\alpha < \frac{\pi}{2}$的情况。有了这样的$\alpha$，就达到了高度值并取两个值：$2R\sin \alpha$和$2R\cos^2\frac{\alpha}{2}$。让我们改变差异

$$2R\sin \alpha - 2R\cos^2\frac{\alpha}{2} = 2R\cos^2\frac{\alpha}{2} \left(2\tg \frac{\alpha}{2} - 1\right).$$

由此我们可以得出结论：

a) 在$\alpha < 2\arctg \frac{1}{2}$处，最大高度为$2R\cos^2\frac{\alpha}{2}$；

b) 在 $2\arctg \frac{1}{2} \leq \alpha < \frac{\pi}{2}$ 处，最大高度为 $2R\sin \alpha$。

现在让$\alpha \geq \frac{\pi}{2}$。我们在上面注意到高度$h_c$的最大值等于$2R\cos^2\frac{\alpha}{2}$。容易地

⟦folio 48⟧

看到函数$h_a$和$h_b$的值填充了区间$]0; 2R \sin^2 \alpha[$。
在所考虑的情况下，$2R \sin^2 \alpha > 2R \cos^2 \frac{\alpha}{2}$。
这意味着在 $\alpha \geq \frac{\pi}{2}$ 处未达到最大高度值。

通过使用几何考虑可以更优雅地解决这个问题。显然$h_a \leq c$和$h_b \leq c$。因此，在$\alpha < \frac{\pi}{2}$处，$h_a$和$h_b$的最大值为$c$（图9）。这意味着在这种情况下我们需要选择较大的数字$h_c$和$c$。当$\alpha$固定时，$c = 2R \sin \alpha$也固定。 $h_c$ 显然在等边三角形中具有最大值（图 10）。因此，在所考虑的情况下，如上所述，我们需要选择数字 $2R \cos^2 \frac{\alpha}{2}$ 和 $2R \sin \alpha$ 中最大的一个。

如果$\alpha \geq \frac{\pi}{2}$，则$h_a \geq h_c$和$h_b \geq h_c$以及$h_a$和$h_b$不会达到等于$c \sin(\pi - \alpha) = 2R \sin^2 \alpha$（图11）的最大值。

当然，细心的读者注意到，在分析的所有问题中，我们都没有遵循“代数和分析的开始 9”手册第 59 段的规则。本质上，该规则仅适用于闭区间的情况。如果开局区间确实如此，就像我们几乎所有问题中的情况一样，那么函数在该区间上的行为就需要特殊分析！

在无限间隔的情况下也会出现同样的问题。

在妻子那里
1. 在抛物线段中，其弦垂直于抛物线对称轴 (图 12)，内切一个周长最大的矩形。 （弦长 - $2a$，高度 - $h$）。

图 12.

2. 在底$a$、高$h$的三角形中，内切一个周长最大的矩形，该矩形的两个顶点位于三角形的底上。

3. 找到穿过 $B(0; -b)$ 的椭圆 $\frac{x^2}{a^2} + \frac{y^2}{b^2} = 1$ 的最大弦。

4. 求从所得物体直径上的一点到限制它的半圆点的最大和最小距离。圆弧段也有同样的问题。

5（DSU，生物学院，1978）。求函数$y = \sin 2x - x$在[0;上的最大和最小值$\pi$]。

6（路易斯安那州立大学，应用数学学院 - 控制过程，1977 年）。对于参数$p$的什么值，三次三项式$x^3 - 2px^2 + 1$在区间$[0; 1]$上在区间右端达到的最小值？

7（KhSU，物理系，1978）。求区间 [2; 上函数 $y = \frac{1}{x} + \frac{q^2}{6 - x}$ 的最小值； 3] 取决于参数$q$。
