---
id: 1977-7-ionin-plotkin-srednee-znachenie-funktsii-d4d6aa54
issue: kvant_1977_7
year: 1977
number: "7"
title: 函数平均值
authors:
  - Ионин Ю. И.
  - Плоткин А. И.
rubric: matematicheskiy-kruzhok
rubric_sub: Математический кружок
page_first: 28
page_last: 32
page_labels: 26-30
tag: 1YAJ
lang: zh
source: kvant_digital
extraction: vision
content_sha256: 6ec02f1d77bbb50920a8bfa2ca454025e9e6de5a1fc07f99c174f776ae047c9b
prompt_sha256: draft-1
translated_from: content/ru/1977/07/articles/08_ionin-plotkin-srednee-znachenie-funktsii-d4d6aa54.md
source_content_sha256: f8bc7acc9952579c4b2606897992c7bb608a361547d6e3b4dcdb4e3ce88c4830
translation_model: draft
translation_run: zh-draft-2026-11-01
translation_quality: draft
---

⟦folio 26⟧

函数平均值

在本文中，数字的算术平均值 $n$ 的概念被推广到定义在线段、圆和球面上的函数。此外，它还解决了���题 M394（«Kvant»，1976，第7号）。

1. 在有限集上

马卡尔·利瓦诺夫在班会上发言时说：“让我们努力奋斗，确保我们班每个学生的成绩都高于平均水平！”显然，马卡尔不太懂数学。让我们弄清楚一下。

众所周知，数字$x_1, x_2, \dots, x_n$的算术平均值$n$是由等式给出的数字$M = M(x_1, x_2, \dots, x_n)$

$$M(x_1, x_2, \dots, x_n) = \frac{x_1 + x_2 + \dots + x_n}{n}.$$ (1)

在马卡的认识之后，我们必须同时满足不等式$x_1 > M, x_2 > M, \dots, x_n > M$。添加这些 $n$ 不等式，我们得到与 (1) 的矛盾。

让我们注意算术平均值的一些重要属性：

I. $M(x_1 + y_1, x_2 + y_2, \dots, x_n + y_n) = M(x_1, x_2, \dots, x_n) + M(y_1, y_2, \dots, y_n)$.

II. $M(\alpha x_1, \alpha x_2, \dots, \alpha x_n) = \alpha M(x_1, x_2, \dots, x_n)$.

III. $\min(x_1, x_2, \dots, x_n) \leqslant M(x_1, x_2, \dots, x_n)$.

在纱线中 1. 证明性能 I-III。

U 2. 证明$n > 1$ 的不等式$C_{2n}^n > \frac{2^{2n-1}}{n}$。使用数学归纳法很容易做到这一点，但也可以使用性质 III 来完成。

性质 III 通常如下使用：要确定平均值 $x_1, x_2, \dots, x_n$ 是大于 $d$ 的数字，只需检查 $M(x_1, x_2, \dots, x_n) > d$ 即可。例如，让我们考虑 X 全联盟数学奥林匹克竞赛中提出的一个问题。

问题 1. 圆桌上不知何故有 50 个定期运行的时钟。证明在某些时刻，在$t$小时时从表中心$O$到分针末端的距离之和，以及在$d$之后从点$O$到时钟中心的距离之和。我们需要证明 $f(t) > d$ 在某些点上是$t$。我们将证明有 $t_0$ 对应 $M(f(t_0), f(t_0 + \frac{1}{2})) > d$。

这意味着$t_0$、$t_0 + \frac{1}{2}$ 时刻之一是例外的。

让我们用$O_i$表示$i$小时的中心，用$A_i$表示该时钟在某些时刻$t$的分针末端，用$B_i$表示半小时后同一小时的分针末端，即在时刻$t + \frac{1}{2}$。由于根据条件，所有时钟都“正确运行”，因此存在一个时刻 $t_0$，此时 $O, A_1$ 和 $B_1$ 不位于同一条直线上。考虑三角形 $OA_1B_1$ 和其中的中线 $OO_1$ (图 1)。很容易证明，在任何三角形中，中线的长度都小于它所包围的边的长度之和的一半（证明它！）。因此，在时刻 $t_0$ 我们有

⟦folio 27⟧

图 1.

$$\frac{OA_1 + |OB_1|}{2} > |OO_1|.$$此时剩余时间$$\frac{|OA_i| + |OB_i|}{2} \geq |OO_i|$$（为什么只有$\geq$而不是>？）。添加 50 个不等式，我们得到 $M(f(t_0), f(t_0 + \frac{1}{2})) > d$。

2. 在段上

在问题 1 中，估计两个函数值的算术平均值就足够了。是否可以考虑所有值的平均值？为了类似于这个概念的定义，让我们给正数$x_1, x_2, \dots, x_n$的平均值$n$赋予几何意义。

将一些线段 $[a; b]$ 分成 $n$ 等份，并构造一个由矩形组成的阶梯式 funkru，其底是长度为 $\frac{b-a}{n}$ 的所得线段，高度分别为 $x_1, x_2, \dots, x_n$ (图 2)。该阶跃函数的面积为$M(x_1, x_2, \dots, x_n) \cdot (b-a)$。因此，$M(x_1, x_2, \dots, x_n)$ 是底边为 $[a; b]$ 的矩形的高度，其面积等于线性梯形 (图 3) 的相应曲线的面积。由于在所考虑的情况下，该区域

图 2.

这个梯形等于$$\int_a^b f(x) \, dx$$（代数与分析10，第101项），$M(f)$由公式定义

$$M(f) = \frac{1}{b-a} \int_a^b f(x) \, dx. \quad (2)$$

定义(2)不仅适用于连续非负函数，也适用于定义在$[a; b]$上的任何函数，对于这些函数，等式(2)的右边有意义。

因此平均值的定义具有类似于属性 I-III 的属性：

I'. $M(f + g) = M(f) + M(g)$.

II'. $M(\alpha f) = \alpha M(f)$.

三． $$\min_{[a; b]} f \leqslant M(f) \leqslant \max_{[a; b]} f.$$ 练习 3. 证明性质 I'—III'。

来自属性 IV' 的 I'-III' 的表达式。如果$f(x) \leqslant g(x)$对于所有$x \in [a; b]$，则$M(f) \leqslant M(g)$。

您已经在 A. Vilenkin 的笔记“Buffon’s Needle”（«Kvant»，1977 年，第 5 期）中遇到了线段上函数的平均值。让我们举另一个应用这个概念的例子。

任务2.数据平面上有向量$\vec{a}, \vec{b}, \vec{c}, \vec{d}$，其和为0。证明不等式

$$|\vec{a}| + |\vec{b}| + |\vec{c}| + |\vec{d}| \geqslant |\vec{a} + \vec{d}| + |\vec{b} + \vec{d}| + |\vec{c} + \vec{d}|. \quad (3)$$

我们对该问题的解决方案将基于其一维版本：

⟦folio 28⟧

图 3.

练习 5. 证明如果 $a, b, c, d$ 是总和为 0 的实数，则$|a| + |b| + |c| + |d| \geq |a+d| + |b+d| + |c+d|$。

解决方案。如果在 (3) 中向量 $\vec{a}, \vec{b}, \vec{c}, \vec{d}$ 被它们在某个轴（“几何 9”）上的投影替换，我们得到 (4)。一个想法出现了：通过考虑这些向量 $\vec{a}, \vec{b}, \vec{c}, \vec{d}$ 在所有可能的轴上的投影来证明（3）。让我们尝试实现它。

设 $\vec{p}$ 为向量。我们先介绍辅助功能$p$如下：修复某个轴$l_0$；让我们用 $p(\alpha)$ 表示向量 $\vec{p}$ 在轴 $l$ 上的投影，与轴 $l_0$ 形成角度 $\alpha$ (图 4)。如果 $\varphi$ 是向量 $\vec{p}$ 与轴 $l_0$ 之间的角度，则$p(\alpha) = |\vec{p}| \cos(\varphi - \alpha)$。

考虑函数 $\alpha \rightarrow |p(\alpha)|$ 在区间 $[0; 2\pi]$ 上的平均值 $M(|p|)$。由定义(2)可知

$$M(|p|) = \frac{1}{2\pi} \int_{0}^{2\pi} |p(\alpha)| d\alpha =$$

$$= \frac{1}{2\pi} \int_{0}^{2\pi} |\vec{p}| \cos(\varphi - \alpha)| d\alpha =$$

$$= \frac{|\vec{p}|}{2\pi} \int_{0}^{2\pi} |\cos(\varphi - \alpha)| d\alpha.$$

让我们证明 $k \neq 0$ 的存在性，使得对于任何向量 $\vec{p}$ 都相等

$$M(|\vec{p}|) = k |\vec{p}|.$$

(6)

凭借式(5)，足以证明积分$\int_{0}^{2\pi} |\cos(\varphi - \alpha)| d\alpha$不依赖于向量$\vec{p}$，即不依赖于角度$\varphi$。

$$\int_{0}^{2\pi} |\cos(\varphi - \alpha)| d\alpha = \int_{0}^{2\pi} |\cos(\alpha - \varphi)| d\alpha =$$

$$= \int_{0}^{2\pi} |\cos \alpha| d\alpha = \int_{0}^{2\pi} |\cos \alpha| d\alpha =$$

$$= \int_{0}^{2\pi} |\cos \alpha| d\alpha + \int_{0}^{2\pi} |\cos \alpha| d\alpha + \int_{0}^{2\pi} |\cos \alpha| d\alpha + \int_{0}^{2\pi} |\cos \alpha| d\alpha.$$

(7)

此计算使用积分的两个属性：

$$\int_{a}^{b} f(x + p) dx = \int_{a+p}^{b+p} f(x) dx,$$

$$\int_{a}^{b} f(x) dx = \int_{a}^{c} f(x) dx + \int_{c}^{b} f(x) dx$$

⟦folio 29⟧

“代数和分析原理 10”，第 106 段和任务编号 512）。计算的中心点是利用$2\pi$是函数$\alpha \rightarrow \cos \alpha$的周期这一事实。

积分$\int_0^{2\pi} |\cos \alpha| d\alpha$是可以计算的（它等于4），但对我们来说重要的是它不依赖于$\varphi$并且与0不同。

如果$\vec{a} + \vec{b} + \vec{c} = 0$，那么对于任何$\alpha$，我们有$a(\alpha) + b(\alpha) + c(\alpha) + d(\alpha) = 0$。有效 (4)

$$|a(\alpha)| + |b(\alpha)| + |c(\alpha)| + |d(\alpha)| \geq |a(\alpha) + d(\alpha)| + |b(\alpha) + d(\alpha)| + |c(\alpha) + d(\alpha)|.$$

(8)

由于 (8) 对于任何 $\alpha \in [0; 2\pi]$ 都满足，因此可以从属性 IV' 和 I' 得出

$$M(|a|) + M(|b|) + M(|c|) + M(|d|) \geq M(|a+d|) + M(|b+d|) + M(|c+d|).$$

来自 (6)

$$k|\vec{a}| + k|\vec{b}| + k|\vec{c}| + k|\vec{d}| \geq k|\vec{a}+d| + k|\vec{b}+d| + k|\vec{c}+d|.$$

减少 $k$，我们得到 (3)。

3. 关于圆和球

任务3.数据空间中有向量$\vec{a}, \vec{b}, \vec{c}, \vec{d}$，其和为0。证明它们不等式（3）。

我想通过将“平面解剖”（来自任务 2）改为空间来证明（3）。为此，我们需要以某种方式确定向量投影到空间中所有可能轴上的模型的平均值。为了解释这是如何完成的，首先考虑在单位半径的圆上定义的函数。

设$f$是这样一个函数。对于任意 $\alpha$，我们设置 $f(\alpha) = f(A)$，其中 $A$ 是弧度为 $\alpha$ (图 5) 的圆路径的端点。因此，我们将单位圆上定义的任意函数$f$与某个函数$f$相关联，

定义在整条直线上。显然，$f$是周期函数$2\pi$。现在让我们将圆上函数$f$的平均值$M(f)$定义为线段[0; 上函数$f$的平均值; 2π]。

在上述问题 2 的解决方案中，由向量$p$方向的均值$M(|p|)$不等式发挥了关键作用。这个不等式是圆上函数平均值的以下一般性质的部分情况：

$V'$。令$f$和$g$为定义在圆上的函数，并且存在最大$\alpha$，对于任何$A$圆$g(A) = f(R^\alpha(A))$（这里$R^\alpha$是给定圆的向量旋转角度$\alpha$）。然后$M(g) = M(f)$。

练习 6. 证明性质 $V'$。

转到问题 3，考虑空间中一个单位半径的球体，其中心位于原点 $O$。对于该球体上给定的函数，可以通过满足属性 $I$ - $V'$ 的方式确定平均值。我们无法在这里解释这是如何完成的，因为为此我们必须通过球体引入内部化。 （这可以使用 interral sum 来完成，其方式与教科书“代数与分析原理 10”第 104 段中定义 interAL 的方式大致相同。）让我们假设球体上函数 $f$ 的平均值 $M(f)$ 以某种方式确定，并且满足属性 $I'$ - $V'$。 （因此，我们考虑函数平均值的公理赋值

⟦folio 30⟧

球体上的 tsini。有趣的是，它是由“公理”$I' - V'$唯一确定的。）

设 $p$ 为向量。让我们如下介绍辅助函数$p$：对于球体的任何点$A$，我们用$p(A)$表示向量$p$在向量$\vec{OA}$定义的轴上的投影。

考虑球面上函数 $A \rightarrow |p(A)|$ 的平均值 $M(|p|)$。让我们证明 $k \neq 0$ 的存在性，使得对于任何向量 $p$ (6) 都满足。为此，推导$II'$的性质后，只需证明$|\vec{p}| = |\vec{q}|$蕴含$M(|p|) = M(|q|)$即可。

进行练习 7。证明这已经足够了。

让$|\vec{p}| = |\vec{q}|$。让我们用 $R$ 来表示空间围绕穿过点 $O$ 的轴的一些旋转，这将具有方向向量 $\vec{q}$ 的射线变换为具有方向向量 $p$ 的射线。那么对于球体$q(A) = p(R(A))$的任意点$A$。从$V'$开始，接着$M(|q|) = M(|p|)$。

问题3的进一步解决应该重复问题2的解决。（练习5和问题2、3将耗尽���题 M394。）

4. 长度除以宽度

问题 2 和问题 3 的解决方案所基于的思想可用于计算平坦封闭凸折线的长度。

让$J$是这样一条折线，$a_1, a_2, \dots, a_n$是它的链接。我们修复一些轴$l_0$。设 $l_\alpha$ 为与 $l_0$ 轴形成角度 $\alpha$ 的轴。让我们用$Ш(\alpha)$表示折线在$l_\alpha$轴方向上的“宽度”，即它在$l_\alpha$轴上投影的长度。事实证明，如果你知道折线$J$在任意方向上的“宽度”，即能够计算函数$\alpha \rightarrow Ш(\alpha)$，那么你就可以求出它的长度$L$。我们将向您展示如何操作。

让我们用$a_i(\alpha)$表示连线$a_i$在轴$l_\alpha$上的投影长度。

练习 8. 证明 $Ш(\alpha) = \frac{1}{2} [a_1(\alpha) + a_2(\alpha) + \dots + a_n(\alpha)]$。

在解决问题2时，发现函数$\alpha \rightarrow a_i(\alpha)$的平均值与$|a_i|$成正比。由(5)和(7)可知，比例系数等于$\frac{1}{2\pi} \int_0^{2\pi} |\cos \alpha| d\alpha = \frac{2}{\pi}$。

根据练习 8 和属性 $I'$、$II'$，函数 $Ш$ 的平均值 $M(Ш)$ 等于函数 $\alpha \rightarrow a_i(\alpha)$ 的平均值。因此，

$$M(Ш) = \frac{1}{2} \left( \frac{2}{\pi} |a_1| + \right. \\ + \frac{2}{\pi} |a_2| + \dots + \frac{2}{\pi} |a_n|) = \\ = \frac{1}{\pi} \left( |a_1| + |a_2| + \dots + |a_n| \right) = \frac{1}{\pi} L.$$

从这里开始，从（2）开始

$$L = \pi \cdot M(Ш) = \pi \cdot \frac{1}{2\pi} \int_0^{2\pi} Ш(\alpha) d\alpha = \\ = \frac{1}{2} \int_0^{2\pi} Ш(\alpha) d\alpha (9)$$

这样，知道了函数$Ш$，我们就可以求出折线$J$的长度$L$。

练习9. 证明如果凸多边形的所有边长和对角线长度都小于$d$，则其周长小于$πd$。

公式(9)对于任何平坦的闭凸曲线都有效。确定“宽度”长度的概述方法是由著名波兰数学家 G. Steinhuz 于 1930 年提出的。

5. 金额长度

问题4. 在数据平面上，存在长度和等于1的向量$a_1, a_2, \dots, a_n$。证明可以对长度和不小于$\frac{1}{\pi}$的多个向量选择平均值。

请按照以下计划解决此问题。设$3$是集合$\{a_1, a_2, \dots\}$的子集。
