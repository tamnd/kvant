---
id: 1972-5-rabbot-trigonometricheskie-funktsii-784fa2df
issue: kvant_1972_5
year: 1972
number: "5"
title: 三角函数
authors:
  - Раббот Ж. М.
rubric: praktikum-abiturienta
rubric_sub: Практикум абитуриента
page_first: 38
page_last: 44
page_labels: 36-42
tag: 3T64
lang: zh
source: kvant_digital
extraction: vision
content_sha256: 1178ab2fc02c369cabe4ee381a8b9f8cc3afa8c47476cab4ece0e72c02958ba7
prompt_sha256: draft-1
translated_from: content/ru/1972/05/articles/10_rabbot-trigonometricheskie-funktsii-784fa2df.md
source_content_sha256: 03dfbcd899b8451daac0529c7b88193be1e8f98d27d6b78ff9c91068d3d45ffe
translation_model: draft
translation_run: zh-draft-2026-10-31
translation_quality: draft
---

⟦folio 36⟧

申请人实习

Trionometric 功能，为大学申请者的入学副本加密。

1. 三等数函数

罪1是什么？ ctg 21 有什么标志？诸如此类的问题常常困扰着许多申请者。

我们想要在所有实数集上定义一个三角函数。为此，请考虑坐标平面上一个单位半径的圆，其中心位于坐标原点（“三角圆”）。

给我们一个任意数$t_0$。让我们在三角圆的圆周上从点 $E(1; 0)$ (图 1) 开始，如果$t_0 \geq 0$，则在正方向（逆时针）绘制一条长度为$|t_0|$的弧，如果$t_0 < 0$（服务三角圆的长度单位），则在负方向（顺时针）绘制一条弧。在这种情况下，我们将获得坐标为 $(x_{t_0}, y_{t_0})$ 的圆上的点 $P_{t_0}$。点$P_{t_0}$的横坐标$x_{t_0}$称为数字$t_0$的余弦，该点的纵坐标$y_{t_0}$称为数字$t_0$的正弦：

$$\cos t_0 = x_{t_0}; \sin t_0 = y_{t_0}.$$

我们的定义中最微妙的一点是在给定长度的圆上打开的过程。它可以被想象为将一段线段缠绕（不拉伸）一个圆。

因此，为了获得数字 $t_0$ 的 sin，我们首先将数字 $t_0$ 与圆上点 $P_{t_0}$ 的定义进行匹配（通过缠绕），然后获取该点的纵坐标：

$$t_0 \rightarrow P_{t_0}(x_{t_0}; y_{t_0}) \rightarrow y_{t_0} = \sin t_0.$$

使用我们的定义，我们可以研究函数$y = \sin t$的属性。让我们向您展示它是如何完成的。

⟦folio 37⟧

a) 求方程 sin t=0 的根。令数 $t$ 使得 sin t=0。这意味着与数字$t$对应的点$P_t$的纵坐标等于0。单位圆上有两个这样的点：$E$和$E'$（参见图1）。将它们放在一起得到，其长度是半圆长度的倍数。

现在注意到单位圆长度的一半是$\pi$，我们得到等式sin t=0 等价于等式$t=\pi k$，其中$k=0, \pm 1, \pm 2, \dots$。

6) 如果数字$t_1$和$t_2$彼此相差2π的倍数（即周长的整数倍），则与数字$t_1$和$t_2$对应的单位圆上的点重合。这意味着等式$t_1-t_2=2\pi k$ ($k=0, \pm 1, \pm 2, \dots$) 隐含等式sin $t_1=\sin t_2$，即数字2π 是函数$y=\sin t$ 的周期。

让我们证明数字 2π 是函数 $y=\sin t$ 的最小正周期。让我们假设相反的情况：让 $0<a<2\pi$ 和

$$\sin (t+a)=\sin t$$

(1)

对于任何$t$（即有一个正数$a$，小于2π，也是一个句号）。

让$t=0$。则由(1)可得sin a=0。但在区间$0<a<2\pi$中只有数字$\pi$，其正弦为零，因此$a=\pi$。现在将$t=\frac{\pi}{2}$代入(1)，我们得到$1=-1\left(\sin \frac{\pi}{2}=1-\text{это ordinata точки } A\text{ на рисунке 1}, a \sin \left(\pi+\frac{\pi}{2}\right)=-1-\text{это ordinata точки } A'\right)$。我们产生了分歧。因此，2π 是函数 $y=\sin t$ 的最小正周期。

我们建立的周期性特性使我们能够进一步研究正弦仅在一个周期内的特性，例如在 $0\leq t\leq 2\pi$ 处。

由于窦的周期性已被证实，更换随之而来。在 Kochetkovs 的教科书“代数和初等函数”（§ 207）中，暗示但没有明确说明，对于周期函数，除了数字 $x$ 之外，所有数字 $x+nT$（$n$-任何整数，$T$-周期）也必须包含在定义域中。同时，这一点也非常重要：有时可以通过精确地获得这个性质来证明函数的周期性。例如，让我们证明函数 $y=\cos \frac{1}{x}$ 是非周期性的。让我们假设该函数的 $T$ 周期。在$x=-T$我们的函数被定义，这意味着它必须在$x=-T+T=0$定义，但在$x=0$引用的$\frac{1}{x}$不存在：我们遇到了矛盾。

以完全类似的方式，我们可以研究函数$y=\cos t$的性质。您似乎很清楚如何定义函数 $y=\tg t$、$y=\ctg t$（数字参数）并探索它们的属性。

战斗

1. 求函数的最小正周期：

a）$y=\sin 3x$； 6) $y=\tg 2x-\sin 3x$; c）$y=2 \sin \left(\frac{\pi}{4}+\frac{x}{2}\right)$； d）$y=\sin^2 x$； e) $y=\sin(\cos x)$； e) $y=\cos(\sin x)$。

例1. 证明函数$y=\sin x^2$是非周期函数。

解决了并且e。假设该函数是周期性的。让我们找到这个函数的零点（即$x$变为零的值）：sin $x^2=0$，因此$x^2=\pi k$（$k=0, 1, 2, \dots$），$x=\pm \sqrt{\pi k}$。如果$k=0$，则$x_0=0$；如果$k=1$，则$x_1=\sqrt{\pi}$。从所做的假设来看

⟦folio 38⟧

函数 $y=\sin x^2$ 的周期性意味着其相邻零点也有无限对（从 $x_0$ 和 $x_1$ 中通过 dws 向右整数个周期获得），它们之间的差等于 $x_1-x_0=\sqrt{\pi}$。但对于任意 $k>1$ 我们有

$$|x_{k+1}-x_k|=|V(k+1)\pi-Vk\pi|=\frac{\pi}{\sqrt{(k+1)\pi}+\sqrt{k\pi}}<\sqrt{\pi}.$$

从$V(k+1)\pi+Vk\pi>\sqrt{\pi}$开始。由此产生的矛盾证明函数 $y=\sin x^2$ 是非周期性的。

练习

2. 证明函数是非周期的： a) $y=\sin \sqrt{x}$； b) $y=\cos x\cos \sqrt{2}x$。
3. 指定下列数字的符号：
a) $\sin 2$; 6) $\cos 3,1$; b) $tg 10$; r) $\sin \pi^2$; d) $tg(\cos 2)$.
4. 对于$t$的所有实数值，给出$\cos^2 t+p\cos t+q>0$。对于$x$的所有实数值，是否都遵循$x^2+px+q>0$？

在（广义）角度的三角函数的定义和数值论证之间建立一个简单的定义并不困难。让我们定位角度，使其初始边沿着 $Ox$ (图 2) 轴。那么角度的正弦根据定义等于角度的端边与单位圆相交点的纵坐标。

如果一个角包含$\alpha$弧度，那么缠绕时，该角的端边将与$\alpha$数对应的圆弧末端的单位圆相交。因此（比较 图 1 和 2）

图 2.

正是这个性质在学校教科书中被接受为数字正弦的定义（对于其他函数也类似：余弦、正切、余切）。

2. 转换三角表达式

在解决各种问题时，常常需要进行类似的变换并使用三角公式。必须记住，有些公式会改变定义的范围；此外，有必要澄清所有转变的可逆性。

示例 2（MAI，1970）。证明圣诞节：

$$\frac{\left(\cos \alpha+\cos \frac{\alpha}{2}\right)^2-\left(\sin \alpha+\sin \frac{\alpha}{2}\right)^2}{\sin 2\alpha-\sin \alpha}=\mathrm{ctg} \frac{\alpha}{4}.$$

解决方案e.首先，我们找到ODZ。 (2)的左边定义为$\sin 2\alpha-\sin \alpha\neq 0$时，即$2\sin \alpha\cos \alpha-\sin \alpha\neq 0$时，由此$\sin \alpha\neq 0$，$\cos \alpha\neq \frac{1}{2}$；最后$\alpha\neq \pi n$，$\alpha\neq \pm \frac{\pi}{3}+2\pi k^*)$。正确的

*) 这里以及进一步，除非另有说明，否则参数 $n, k, l$ 等接受所有整数值。

⟦folio 39⟧

第(2)部分对于$\sin \frac{\alpha}{4} \neq 0$存在，即对于$\alpha \neq 4\pi l$存在。因此，找到 ODZ：$\alpha \neq n\pi, \alpha \neq \pm \frac{\pi}{3} + 2\pi k$。

让我们用 $M$ 表示恒等式的左侧。然后

$$M = \frac{\cos^2\alpha + 2\cos\alpha \cos \frac{\alpha}{2} + \cos^2 \frac{\alpha}{2} - \sin^2\alpha - 2\sin\alpha \sin \frac{\alpha}{2} - \sin^2 \frac{\alpha}{2}}{\sin 2\alpha - \sin\alpha} =$$

$$= \frac{(\cos^2\alpha - \sin^2\alpha) + \left(\cos^2 \frac{\alpha}{2} - \sin^2 \frac{\alpha}{2}\right) + 2\left(\cos\alpha \cos \frac{\alpha}{2} - \sin\alpha \sin \frac{\alpha}{2}\right)}{\sin 2\alpha - \sin\alpha} =$$

$$= \frac{\cos 2\alpha + \cos\alpha + 2\cos \frac{3\alpha}{2}}{\sin 2\alpha - \sin\alpha} = \frac{2\cos \frac{\alpha}{2} \cos \frac{3\alpha}{2} + 2\cos \frac{3\alpha}{2}}{2\sin \frac{\alpha}{2} \cos \frac{3\alpha}{2}} =$$

$$= \frac{\cos \frac{\alpha}{2} + 1}{\sin \frac{\alpha}{2}} = \frac{2\cos^2 \frac{\alpha}{4}}{2\sin \frac{\alpha}{4} \cos \frac{\alpha}{4}} = \text{ctg} \frac{\alpha}{4}.$$

所以，在 ODZ $M = \text{ctg} \frac{\alpha}{4}$。

例 3. 证明如果 $\text{ctg}(\alpha + \beta) = 0$，则

$$\sin(\alpha + 2\beta) = \sin\alpha.$$

(3)

解决方案。请注意，条件 $\text{ctg}(\alpha + \beta) = 0$ 等同于条件

$$\cos(\alpha + \beta) = 0.$$

(4)

现在让我们考虑（3）右侧和左侧之间的差异：$\sin(\alpha + 2\beta) - \sin\alpha = 2\sin\beta \cos(\alpha + \beta)$，从这里，使用（4），我们得到所需的。

练习

5. （梅，1970）。证明身份：
a) $(\sin\alpha - \cos\alpha)^2 + (\cos\alpha - \sec\alpha)^2 = 4\text{ctg}^2 2\alpha + 1$;
b) $\sin\alpha + \text{ctg}\alpha - \text{ctg}\alpha \cos\alpha - 1 = \frac{2\cos\left(\frac{\pi}{4} + \alpha\right)\sin\left(\frac{\alpha}{2} - \frac{\pi}{4}\right)}{\cos \frac{\alpha}{4}}.$

6. 证明身份：
a）（MISP，1969）。 $\frac{1}{1 + \text{tg}\alpha \text{tg}2\alpha} = \sin\left(\frac{\pi}{2} + 2\alpha\right)$； b) (莫斯科物理学院)。 $\cos^2\varphi + \cos^2(\alpha + \varphi) - 2\cos\alpha \cos\varphi \cos(\alpha + \varphi) = \sin^2\alpha$。
7. （莫斯科国立大学物理学院）。
a) 证明如果$5\sin\beta = \sin(2\alpha + \beta)$则$\frac{\text{ctg}(\alpha + \beta)}{\text{tg}\alpha} = \frac{3}{2}$；
b) 证明如果$\cos x = \cos a \cos b$、$x \pm a \neq \pi(2k + 1)$、$b \neq \pi(2k + 1)$，则$1 + \text{tg}\frac{x + a}{2} \text{tg}\frac{x - a}{2} = \frac{1}{\cos^2 \frac{b}{2}}$。

示例 4. 简化表达式

$$M = \sin\alpha + \sin(\alpha + \delta) + \dots + \sin(\alpha + n\delta).$$

⟦folio 40⟧

解决方案。注意到正弦的参数形成一个具有差 $\delta$ 的参数级数，我们将等式两边乘以 $2 \sin \frac{\delta}{2}$：

$$2 \sin \frac{\delta}{2} \cdot M = 2 \sin \frac{\delta}{2} \sin \alpha + 2 \sin \frac{\delta}{2} \sin (\alpha + \delta) + \dots + 2 \sin \frac{\delta}{2} \times$$

$$\times \sin (\alpha + n\delta) = \cos \left( \alpha - \frac{\delta}{2} \right) - \cos \left( \alpha + \frac{\delta}{2} \right) + \cos \left( \alpha + \frac{\delta}{2} \right) -$$

$$- \cos \left( \alpha + \frac{3\delta}{2} \right) + \dots + \cos \left[ \alpha + \left( n - \frac{1}{2} \right) \delta \right] - \cos \left[ \alpha + \left( n + \frac{1}{2} \right) \delta \right] =$$

$$= \cos \left( \alpha - \frac{\delta}{2} \right) - \cos \left[ \alpha + \left( n + \frac{1}{2} \right) \delta \right] = 2 \sin \left( \alpha + \frac{n\delta}{2} \right) \sin \frac{n+1}{2} \delta.$$

所以，如果$\sin \frac{\delta}{2} \neq 0$，即$\delta \neq 2\pi k$，那么

$$M = \frac{\sin \left( \alpha + \frac{n\delta}{2} \right) \sin \left( \frac{(n+1)\delta}{2} \right)}{\sin \frac{\delta}{2}}.$$

若$\delta = 2\pi k$，则

$$M = \sin \alpha + \sin (\alpha + 2\pi k) + \dots + \sin (\alpha + 2\pi nk) = (n+1) \sin \alpha.$$

练习

8. 证明如下：

$$= \frac{\sin \frac{n\alpha}{2} \cos \frac{(n+1)\alpha}{2}}{\sin \frac{\alpha}{2}};$$

a）（莫斯科工程物理学院）。 $\cos \alpha + \cos 2\alpha + \cos 3\alpha + \dots + \cos n\alpha =$

b)（密歇根州立大学）。 $\cos \frac{\pi}{5} + \cos \frac{3\pi}{2} = \frac{1}{2}$。

9. （MEPhI）。简化你的表达。 a）$\cos \alpha \cdot \cos 2\alpha \cdot \cos 4\alpha \dots \cos 2^{n}\alpha$；

b) $\cos \alpha - \cos 2\alpha + \cos 3\alpha - \cos 4\alpha + \dots + (-1)^{n+1} \cos n\alpha$;

b) $\sin \alpha + 2 \sin 2\alpha + 3 \sin 3\alpha + \dots + n \sin n\alpha$;

r) $\sin^3 \frac{\alpha}{3} + 3 \sin^3 \frac{\alpha}{3^2} + 9 \sin^3 \frac{\alpha}{3^3} + \dots + 3^{n-1} \sin^3 \frac{\alpha}{3^n}$.

示例 5. 证明圣诞节：

$$\mathrm{tg} \alpha + \frac{1}{2} \mathrm{tg} \frac{\alpha}{2} + \frac{1}{4} \mathrm{tg} \frac{\alpha}{4} + \dots + \frac{1}{2^n} \mathrm{tg} \frac{\alpha}{2^n} = \frac{1}{2^n} \mathrm{ctg} \frac{\alpha}{2^n} - 2 \mathrm{ctg} 2\alpha.$$

解决方案。注意到恒等式的右侧包含 cotan-gens，我们用 $\mathrm{ctg} 2\alpha$ 和 $\mathrm{ctg} \alpha$ 来表达 $\mathrm{tg} \alpha$：$\mathrm{tg} \alpha = \mathrm{ctg} \alpha - 2 \mathrm{ctg} 2\alpha$。

然后

$$\mathrm{tg} \alpha = \mathrm{ctg} \alpha - 2 \mathrm{ctg} 2\alpha,$$

$$\mathrm{tg} \frac{\alpha}{2} = \mathrm{ctg} \frac{\alpha}{2} - 2 \mathrm{ctg} \alpha,$$

$$\mathrm{tg} \frac{\alpha}{4} = \mathrm{ctg} \frac{\alpha}{4} - 2 \mathrm{ctg} \frac{\alpha}{2},$$

$$\dots$$

$$\mathrm{tg} \frac{\alpha}{2^n} = \mathrm{ctg} \frac{\alpha}{2^n} - 2 \mathrm{ctg} \frac{\alpha}{2^{n-1}}.$$

⟦folio 41⟧

将写入的恒等式分别乘以 1、$\frac{1}{2}$、...、$\frac{1}{2^n}$，然后将它们相加，我们就得到了所需的结果。我们的变换只对 $\alpha \neq \frac{\pi k}{2}$ 有意义​​（检查！）。

练习

10. 证明身份：a) (UGPI)。 $\sin^2 \alpha + \sin^2 (120^\circ + \alpha) + \sin^2 (120^\circ - \alpha) = \frac{3}{2}$；
6) （麦）。 $tg 3\alpha = tg \alpha tg \left(\frac{\pi}{3} + \alpha\right) tg \left(\frac{\pi}{3} - \alpha\right)$； b) (MagGPI)。 $4 \cos^2 \alpha + \sin^2 2\alpha + 4 \sin^4 \alpha = 4$。

11. 转换为乘积：a) (MagGPI)。 $\cos^2 (x + y) + \sin (x + y) + \cos (x + y) + \sin^2 (x + y)$；
6) （麦）。 $tg^3\alpha + \frac{1}{\cos^2 \alpha} + 3 \text{ctg} \left(\frac{3\pi}{2} + \alpha\right) - 4$；
b) (MISP, 1969)。 $\sin 5\alpha \sin 4\alpha + \sin 4\alpha \sin 3\alpha - \sin 2\alpha \sin \alpha$； r)（MTI，1970）。

$\sec^2 \alpha - tg^2 \alpha + tg \left(\frac{\pi}{2} - \frac{\alpha}{2}\right) + \text{ctg} \left(\frac{\pi}{4} - \frac{\alpha}{2}\right)$.

示例 6. 在没有表格的情况下计算 sin 18°。
解决方案e.我们将使用$18^\circ \cdot 5 = 90^\circ$，即$2 \cdot 18^\circ + 3 \cdot 18^\circ = 90^\circ$，从何而来

$$\cos (2 \cdot 18^\circ) = \sin (3 \cdot 18^\circ)$$

cos 2α 和sin 3α 通过sin α 有理地表达。应用公式 cos 2α = 1 - 2 sin²α 和 sin 3α = 3 sin α - 4 sin³α，从（5）我们得到： $4 \sin^3 18^\circ - 2 \sin^2 18^\circ - 3 \sin 18^\circ + 1 = 0$。

用 y 表示 sin 18°，我们得到方程

$$4y^3 - 2y^2 - 3y + 1 = 0,$$

通过注意到$y = 1$是它的根（紧接着（6）的左侧可被$y - 1$整除），这很容易解决：$(y - 1) (4y^2 + 2y - 1) = 0$，因此$y_1 = 1, y_2, 3 = \frac{-1 \pm \sqrt{5}}{4}$。考虑sin 18° ≠ 1，sin 18° > 0，我们发现sin 18° = $\frac{\sqrt{5} - 1}{4}$。

示例 7. 让我们简化表达式： a) $S_1 = \cos^2 \alpha + \cos^2 2\alpha + \dots + \cos^2 n\alpha$; b) $S_2 = \sin^2 \alpha + \sin^2 2\alpha + \dots + \sin^2 n\alpha$。
解决方案e.由于 sin²x + cos²x = 1，则

$$S_1 + S_2 = n.$$

现在应用练习 8a) 的结果（对于什么 α 可以完成此操作？），我们得到：

$$S_1 - S_2 = (\cos^2 \alpha - \sin^2 \alpha) + (\cos^2 2\alpha - \sin^2 2\alpha) + \dots + (\cos^2 n\alpha - \sin^2 n\alpha) = \cos 2\alpha + \cos 4\alpha + \dots + \cos 2n\alpha = \frac{\sin n\alpha \cos (n + 1)\alpha}{\sin \alpha}$$

现在由(7)和(8)很容易得到: $S_1 = \frac{n}{2} + \frac{\sin n\alpha \cos (n + 1)\alpha}{2 \sin \alpha}$; $S_2 = \frac{n}{2} - \frac{\sin n\alpha \cos (n + 1)\alpha}{2 \sin \alpha}$。 α = πk 的答案是什么？

练习

12. 无表计算：a) cos 15°； b) 玻璃化转变温度7.5°； c) 玻璃化转变温度18°； r）（MAI，1970）。余弦 55° 余弦 65° 余弦 175°； d）（MISP，1969）。 tg 9° - tg 27° - tg 63° + tg 81°。

⟦folio 42⟧

示例 8. 如果 $\sin \alpha \cos \alpha = 0,48$，则求 $\cos \alpha + \sin \alpha$。

解决方案。从恒等式$(\cos \alpha + \sin \alpha)^2 = 1 + 2 \sin \alpha \cos \alpha$两边取平方根（一如既往，算术！），我们得到：$|\cos \alpha + \sin \alpha| = \sqrt{1 + 2 \sin \alpha \cos \alpha} = 1,4$（根式表达式是非负的：$1 + 2 \sin \alpha \cos \alpha = 1 + \sin 2\alpha \geq 0$，因为$\sin 2\alpha \geq -1$）。由于根据条件$\sin \alpha \cos \alpha > 0$，则$\sin \alpha$和$\cos \alpha$具有相同的符号，即$\alpha$要么在I季度，要么在III季度。如果$2\pi n < \alpha < \frac{\pi}{2} + 2\pi n$，则$\sin \alpha + \cos \alpha = 1,4$；

如果$\pi + 2\pi n < \alpha < \frac{3\pi}{2} + 2\pi n$，则$\sin \alpha + \cos \alpha = -1,4$。

练习

13. a) (MAI)。如果 $tg \frac{\alpha}{2} = m - 1$ 则求 $\frac{1 - 2 \sin^2 \frac{\alpha}{2}}{1 + \sin \alpha}$； 6）（密歇根州立大学）。证明如果$tg \alpha = \frac{1}{7}$，$\sin \beta = \frac{1}{\sqrt{10}}$，则$\alpha + 2\beta = \frac{\pi}{4}$（$\alpha$和$\beta$是第一四分之一的角度）； 7) (MISP)。如果$\cos \alpha = \frac{2}{3}$，则求$18 \sin \frac{3\alpha}{2} \sin \frac{\alpha}{2}$。 8）（MTI）。如果$tg \alpha = \frac{4}{3}$、$\pi < \alpha < \frac{3\pi}{2}$，则求$tg \frac{\alpha}{2}$。

14. （密歇根州立大学）。已知$\alpha + \beta + \gamma = \frac{\pi}{2}$、$\alpha > 0$、$\beta > 0$、$\gamma > 0$和$ctg \alpha, ctg \beta, ctg \gamma$构成等差数列。找到$ctg \alpha$$ctg \gamma$。

15. （MEPhI）。证明如果 $\alpha, \beta, \gamma$ 是三角形的内角，那么

a) $\sin \alpha + \sin \beta + \sin \gamma = 4 \cos \frac{\alpha}{2} \cos \frac{\beta}{2} \cos \frac{\gamma}{2}$;

b) $tg \alpha + tg \beta + tg \gamma = tg \alpha tg \beta tg \gamma$;

r) $\sin 2\alpha + \sin 2\beta + \sin 2\gamma = 4 \sin \alpha \sin \beta \sin \gamma$;

d) $\sin^2 \alpha + \sin^2 \beta + \sin^2 \gamma = 2 \cos \alpha \cos \beta \cos \gamma + 2$;

e) $tg \frac{\alpha}{2} tg \frac{\beta}{2} + tg \frac{\alpha}{2} tg \frac{\gamma}{2} + tg \frac{\beta}{2} tg \frac{\gamma}{2} = 1$;

g）$\cos \alpha + \cos \beta + \cos \gamma \leq \frac{3}{2}$；

3) $\sin^2 \alpha + \sin^2 \beta + \sin^2 \gamma > 2$（锐角三角形）。

16. 证明不等式：

a) (MIPT)。

$ctg \frac{\alpha}{2} > 1 + ctg \alpha \left(0 < \alpha < \frac{\pi}{2}\right)$;

6) （VSU）。 $\cos \alpha + 3 \cos 3\alpha + 6 \cos 6\alpha \geq -7,2$；

b) (MIPT)。 $(1 - tg^2\alpha) (1 - 3tg^2\alpha) (1 + tg2\alpha tg3\alpha) > 0$； r) (MIPT)。

$(ctg^2\alpha - 1) (3ctg^2\alpha - 1) \times (ctg3\alpha tg2\alpha - 1) \leq -1$； d)（密歇根州立大学）。 $4 \sin 3\alpha + 5 \geq 4 \cos 2\alpha + 5 \sin \alpha$。

而且。文章中使用了以下缩写：

MAI - 莫斯科航空学院、MSU - 莫斯科国立大学、MGPI - 莫斯科国立师范学院、MagGPI - 马加丹国立师范学院、MTI - 莫斯科纺织学院、MISP - 莫斯科钢铁和斯拉夫人学院、MEPhI - 莫斯科工程物理学院、USPI - 乌里扬诺夫斯克国立师范学院、VSU - 沃罗涅日国立大学、MIPT - 莫斯科物理技术学院。
