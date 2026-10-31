---
id: 1970-12-margulis-mordkovich-radunskiy-esche-raz-ob-uravneniyah-s-parametrami-e4de8adf
issue: kvant_1970_12
year: 1970
number: "12"
title: 再次关于带参数的方程
authors:
  - Маргулис А. Я.
  - Мордкович А. Г.
  - Радунский Б. А.
rubric: praktikum-abiturienta
rubric_sub: Практикум абитуриента
page_first: 48
page_last: 51
page_labels: 46-49
tag: R1KM
lang: zh
source: kvant_digital
extraction: vision
content_sha256: 3a74c278a4aa9c510b8b157c2200a602b50c2fa80cdd346a0d8d3eb47bb1d9a6
prompt_sha256: draft-1
translated_from: content/ru/1970/12/articles/08_margulis-mordkovich-radunskiy-esche-raz-ob-uravneniyah-s-parametrami-e4de8adf.md
source_content_sha256: 264645cf41f61b7b2894372529c338d17d0ece6c264a83a11f57bd9ec9c1c051
translation_model: draft
translation_run: zh-draft-2026-10-31
translation_quality: draft
---

⟦folio 46⟧

再次关于方程
带参数

您已经遇到过多次包含一个参数的方程和不等式。如果有多个参数怎么办？很自然地预期需要考虑的可能案件数量将会增加。任何可能的选择都不应被错过。如何做到这一点？没有一种方法适用于任何带有参数的方程和不等式。在本文中，我们将通过示例展示如何求解具有两个参数的方程。

具有两个参数 $a, b$ 的 $x$ 方程的一般形式为：

$$F(x; a; b) = 0.$$

(1)

对于给定函数 $F$，方程 (1) 实际上是一个无限方程组，每个方程都由一对有序数字 $(a; b)$ 确定。

众所周知，这样的有序对可以解释为坐标平面上的点。这使得对于给定函数 $F$ 的形式 (1) 方程与平面上的点之间建立一一对应成为可能。

为此，我们引入坐标系 $aOb$ 并同意如何将 (1) 形式的方程分配给平面 $aOb$ 上坐标为 $(a; b)$ 的点，反之亦然。让我们把这个平面变成参数平面。这种对应关系有点不寻常（方程对应于一个点），但它将帮助我们在每种特定情况下找到一组允许的参数值，并且不会错过任何一个情况：形式（1）的方程对应于参数平面的哪个点，并且必须对应某个答案。

示例 1：求解方程

$$\frac{2a + b}{a + x} - \frac{2a - b}{a - x} = \frac{2a}{b}$$

(2)

解决方案。让我们立即注意到，对于$b = 0$方程（2）没有意义，也就是说，对于任何$(a; 0)$形式的数字，其中$a$是任何实数，都没有解（图1上的红线）。

让$b \neq 0$。让我们找到 ODZ：$x \neq \pm a$，去掉分母并引入类似的项。我们得到

$$a(x^2 - 2bx + b^2 - a^2) = 0.$$

(3)

如果$a = 0$，则方程（3）对于$x$的任何值都有其解。其中，对于等式（2），禁止取值$x = \pm a$，即$x = 0$。

因此，对于任何 $(0; b)$ 形式的数字，其中 $b \neq 0$，方程 (2) 都有除 0（绿线）之外的任何数字的解。现在让$a \neq 0$。求解方程$x^2 - 2bx + b^2 - a^2 = 0$，我们得到$x_1 = b + a$，$x_2 = b - a$。

*) 在形式 (1) 中，该方程为： $$\frac{2a + b}{a + x} - \frac{2a - b}{a - x} - \frac{2a}{b} = 0.$$

⟦folio 47⟧

我们是否可以假设对于任何不同于零的$a, b$，找到的值$x_1$和$x_2$是方程（2）的根？不，或者对于某些参数值$x_1$或$x_2$可能会与禁止值$\pm a$一致。

因此，仍然需要找出何时$x_1 = \pm a$或$x_2 = \pm a$。如果$x_1 = a$或$x_2 = -a$则$b = 0$，但我们正在考虑$b \neq 0$的情况。所以，$x_1 \neq a$，$x_2 \neq -a$。

让$x_1 = -a$，即$b + a = -a$，由此而来$b = -2a$。但随后$x_2 = -3a$。因此，如果参数$a$和$b$使得$b = -2a$，则方程(2)有一个单根$x = -3a$（图1处的蓝线）。设$x_2 = a$，即$b - a = a$。这可以通过 $b = 2a$ 实现。

但随后$x_1 = 3a$。因此，如果参数$a$和$b$使得$b = 2a$，则方程（2）有一个单根$x = 3a$（黄线）。

总而言之，我们得到以下答案：

若$b = 0$、$a$为任意实数，则无解；
如果$b \neq 0$，$a = 0$，则$x$是除零之外的任意实数；
如果$b = -2a$，$b \neq 0$，则$x = -3a$；
如果$b = 2a$，$b \neq 0$，则$x = 3a$；
如果$a, b \neq 0$，$b \neq \pm 2a$，则$x_1 = b + a$，$x_2 = b - a$。

示例 2*)。解方程

$$\sqrt{a^2 - x} + \sqrt{b^2 - x} = a + b.$$

(4)

解决方案。 ODZ 由不等式系统确定

$$x \leq a^2, \quad x \leq b^2, \quad \text{или } x \leq \min\{a^2; b^2\}.$$

方程(4)左边是非负的，因此对于$a + b < 0$，该方程无解。在 图 2 上，这一点的标志是直线 $b = -a$ 下的结果呈粉红色。

现在让我们考虑$a + b \geq 0$的情况。经过估计变换后我们得到

$$x(a + b)^2 = 0$$

(5)

让我们考虑两种情况：

我的情况是：$a + b > 0$。然后$x = 0$。在这种情况下，条件$x \leq a^2$和$x \leq b^2$自动满足，而条件$x \geq -ab$则不能这样说。如果$ab > 0$，那么这个条件就非常满足了。如果$ab < 0$，则$-ab > 0$和$x = 0 < -ab$。因此，在 II 区和 III 区的 图 2 处（其中 $a + b > 0$，但 $ab < 0$）没有解。所以 $x = 0$ 是根

*) 这个例子取自 N.P. 的书。安东诺夫等人。 “初等数学问题集”（莫斯科，“Nauka”，1969），其中解决错误。

⟦folio 48⟧

图 2.

方程（4），仅当$a + b > 0$和$ab \geq 0$，即对于参数的前四个平面的点，包括其边界的点（区域$I$至图2）。

P 情况：$a + b = 0$。在这种情况下，方程（5）变成恒等式$x \cdot 0 = 0$，但这并不意味着任何实数都是原始方程（4）的根（解释一下为什么会这样）。

对于$a + b = 0$，我们依次求出$b = -a$、$b^2 = a^2$，式(4)的形式为$2\sqrt{a^2 - x} = 0$，由此得出$x = a^2 = b^2$，显然所有条件都满足。在 图 2 处，该答案显示在蓝线 $b = -a$ 附近。

结合所有获得的结果，我们得到答案：
如果$a + b > 0$和$ab \geq 0$，则$x = 0$；
如果$a + b = 0$，则$x = a^2$；
如果$a + b < 0$或$a + b > 0$和$ab < 0$，则无解。

示例 3. 求解方程组

$$tg x + tg y = a, \quad x + y = b.$$

解决方案。我们记下 ODZ：$x, y \neq \frac{\pi}{2} + n\pi$（以下简称 $k, l, m, n = 0; \pm 1; \ldots$）。让我们将系统的第一个方程转换为$\frac{\sin(x + y)}{\cos x \cos y} = a$的形式，然后考虑到$x + y = b$的事实，我们得到

$$a \cos x \cos y = \sin b.$$

我的情况是：$a = 0$。它自然地分解为两个选项：I，a）$a = 0$，$\sin b = 0$；我，6）$a = 0$，$\sin b \neq 0$。

若$sin b = 0$，即$b = m\pi$，则方程(7)满足任意对$(x; y)$，且系统(6)满足任意满足以下条件的对$(x; y)$：

$$x \neq \frac{\pi}{2} + n\pi; \quad y \neq \frac{\pi}{2} + n\pi; \quad x + y = b.$$

如果$sin b \neq 0$，即$b \neq m\pi$，则方程（7）及其系统（6）无解。

第二种情况：$a \neq 0$。则式(7)变换为形式

$$\cos x \cos y = \frac{\sin b}{a} \text{ и, далее,}$$

$$\cos (x + y) + \cos (x - y) = \frac{2 \sin b}{a}.$$

如果我们再次考虑$x + y = b$，则方程（8）可以重写如下：

$$\cos (x - y) = \frac{2 \sin b}{a} - \cos b.$$

⟦folio 49⟧

进一步的异化取决于对等式（9）右边的评估：
如果$\left| \frac{2 \sin b}{a} - \cos b \right| > 1$，则方程（9）及其系统（6）无解；如果$\left| \frac{2 \sin b}{a} - \cos b \right| \leq 1$，那么
$$x - y = \pm \arccos \left( \frac{2 \sin b}{a} - \cos b \right) + 2k\pi.$$
用方程 $x + y = b$ 求解系统中的最后一个方程，我们得到
$$\begin{cases} x = \frac{b}{2} \pm \frac{1}{2} \arccos \left( \frac{2 \sin b}{a} - \cos b \right) + k\pi, \\ y = \frac{b}{2} \pm \frac{1}{2} \arccos \left( \frac{2 \sin b}{a} - \cos b \right) - k\pi. \end{cases}$$
我们只需要找出对于某些参数值是否会出现找到的值$x, y$与禁止值$\frac{\pi}{2} + n\pi$一致的情况。很容易看出，当$b \pm \arccos \left( \frac{2 \sin b}{a} - \cos b \right) = \pi + 2l\pi$时，就会发生这种情况。我们将最后一个等式重写如下：$\pm \arccos \left( \frac{2 \sin b}{a} - \cos b \right) = \pi - b + 2l\pi$，并取两边的余弦。我们得到
$$\frac{2 \sin b}{a} - \cos b = -\cos b, \quad \sin b = 0, \quad b = m\pi.$$
因此，如果$b = m\pi$和$a \neq 0$，则系统(6)将无解。结合所有获得的结果，我们写下答案：
如果$a = 0, b = m\pi$，则系统(6)的解是任意对$(x, y)$以及$x \neq \frac{\pi}{2} + n\pi, \quad y \neq \frac{\pi}{2} + n\pi, \quad x + y = b$；
如果$a = 0, b \neq m\pi$，或$a \neq 0, b = m\pi$，则无解；
如果$a \neq 0, b \neq m\pi$但$\left| \frac{2 \sin b}{a} - \cos b \right| \leq 1$，则无解。

我们仅限于考虑只有两个参数的示例。进一步通知参数数量，而不给出任何根本性的新内容，只会导致技术困难的通知。

练习
1. 求解以下方程：
2. 求解方程组：

a) $a^2 - \frac{a^2 - b^2}{2x - x^2} = \frac{b^2 (x + 2)}{x - 2}$;
b) $\frac{\sqrt{a - x} - \sqrt{x - b}}{\sqrt{a - x} + \sqrt{x - b}} = \frac{a - b}{a + b - 2x}$;
b) $\frac{\mathrm{tg} ax}{\sin bx} = 0$.
