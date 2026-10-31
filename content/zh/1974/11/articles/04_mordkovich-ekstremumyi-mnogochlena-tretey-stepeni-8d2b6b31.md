---
id: 1974-11-mordkovich-ekstremumyi-mnogochlena-tretey-stepeni-8d2b6b31
issue: kvant_1974_11
year: 1974
number: "11"
title: 三次多项式的极值
authors:
  - Мордкович А. Г.
rubric: osnovnye-stati
page_first: 10
page_last: 12
page_labels: 8-10
tag: NU4P
lang: zh
source: kvant_digital
extraction: vision
content_sha256: 15a38f40cb279c40d2f90d52ae30453935bb4785a3205cec5a6044944a103dae
prompt_sha256: draft-1
translated_from: content/ru/1974/11/articles/04_mordkovich-ekstremumyi-mnogochlena-tretey-stepeni-8d2b6b31.md
source_content_sha256: e2a2f8ee39b85c52880236241828a4a73a75c81e1abfc889cb4ea6e20ee5e849
translation_model: draft
translation_run: zh-draft-2026-10-31
translation_quality: draft
---

⟦folio 8⟧

三次多项式的极值

本文是三次函数和方程系列文章中的第四篇 *) 它将重点介绍函数 $y = ax^3 + bx^2 + cx + d$ 的最大点和最小点

首先我们看一下函数$y = ax^2 + bx + c$(1)
$(a \neq 0)$。设$x = \alpha$为函数(1)的根。在点 $x = \alpha$ 的一个相当小的邻域中，该函数的图像是什么样的？

这里有四种可能的情况——如图 1-4 所示。在第一种和第二种情况下，我们说函数在点$x = \alpha$处是单调的（在第一种情况下它增加，在第二种情况下它杀死）。在第三种和第四种情况下，函数被认为在点 $x = \alpha$ 处有极值

*) 参见文章：V. G. Yankelevich，《不可约》案，《Kvant》，1971年，第11期； O. A. Zhautykov，三次四事件图，《Kvant》，1972年，第6期； O. A. Zhautykov，关于三次方程根的边界，《Kvant》，1973年，第12期。

（在第三种情况下 - 最小值，在第四种情况下 - 最大值）*。

第一种、第二种情况与第三种、第四种情况有什么根本区别？事实上，在前两种情况下，函数在经过点 $x = \alpha$ 时会改变符号（例如，在第一种情况下，$y < 0$ 在 $x < \alpha$ 处，$y > 0$ 在 $x > \alpha$ 处；

*) 有时他们说函数有局部极值（最大值、最小值）。 《Local》的意思是“本地”：在点$x = \alpha$的某些邻域内，函数值不会超过$f(\alpha)$，尽管距离点$x = \alpha$“较远”，函数值$f(x)$可能会超过$f(\alpha)$。在我们采用的术语中（另见 B. E. Weitz、I. T. Demidov、《代数与分析入门》、9 级、A. N. Kolmogorov 院士编辑的专业教科书，§ 69），函数可以有许多极大值和极小值，这些极大值和极小值被定义为局部概念。

图 1. 图 2. 图 3. 图 4.

⟦folio 9⟧

这里$x$的值被选择为足够接近点$x = \alpha$），并且在最后两种情况下，函数在通过点$x = \alpha$时不会改变符号。

我们来尝试找出多项式$y = ax^2 + bx + c$的根点$x = \alpha$为极值点的充要条件。我们将函数(1)转化为以下形式

$$y = a (x - \alpha)(x - \beta)$$

（$\alpha$和$\beta$是直角三角形的根；尝试证明如果$x = \alpha$是函数（1）的根，那么它可以表示为$\beta$是实数的形式）。

如果$\alpha \neq \beta$，则在点$x = \alpha$（在$|x - \alpha| < |\alpha - \beta|$）的足够小的邻域中，表达式$a (x - \beta)$保留恒定符号，这意味着函数$y = a (x - \alpha) \times (x - \beta)$在经过点$x = \alpha$时改变符号。在这种情况下，不存在极值。如果$\alpha = \beta$，那么我们得到$y = a (x - \alpha)^2$；该函数在经过点$x = \alpha$时不会改变符号。

因此，当该根是双倍时，直角三角形的根是其模型的极值点和模型的摩尔。

得到的结果概括如下：

定理1. 为了使点$x = \alpha$成为函数$y = ax^2 + bx + c$的极值点，存在使多项式$ax^2 + bx + c - m$有双根$x = \alpha$的最大数$m$是必要且充分的。

为了证明这个定理，当且仅当函数$y = f(x) - m$（其中$m = f(\alpha)$）在该点有极值时，知道点$x = \alpha$就足够了。

该结果用于实践。

示例 1. 查找函数的极值点

$$y = ax^2 + bx + c.$$

让我们选择数字 $\alpha, m$ 以使恒等式成立

$$ax^2 + bx + c - m = a (x - \alpha)^2.$$

我们有

$$ax^2 + bx + c - m = ax^2 - 2a\alpha x + a\alpha^2.$$

但是两个多项式也相等当且仅当它们的系数对于相同的幂相等；因此我们得到一个方程组

$$\begin{cases} -2a\alpha = b, \\ a\alpha^2 = c - m, \end{cases}$$

它位于何处

$$\alpha = -\frac{b}{2a}, \quad m = \frac{4ac - b^2}{4a}.$$

因此，$x = -\frac{b}{2a}$ 是函数$y = ax^2 + bx + c$ 的极值点（如果$a > 0$，则为局部最大值点；如果$a < 0$，则为局部最小值点）。

现在让我们看看这个函数

$$y = ax^3 + bx^2 + cx + d.$$

下面我们将证明，对于它，可以制定并证明类似于定理1的定理。但首先我们将证明一些辅助结果。

引理。给定一个次数为 $y = ax^3 + bx^2 + cx + d$ ($a \neq 0$) 的多项式，并令 $x = \alpha$ 为其实根。然后

$$ax^3 + bx^2 + cx + d = a (x - \alpha)(x^2 + px + q),$$

$p$和$q$也是一些实数。

证明。在$a\alpha^3 + b\alpha^2 + c\alpha + d = 0$条件下。

然后

$$ax^3 + bx^2 + cx + d = (ax^3 + bx^2 + cx + d) - (a\alpha^3 + b\alpha^2 + c\alpha + d) = a (x^3 - \alpha^3) + b (x^2 - \alpha^2) + c (x - \alpha) = (x - \alpha) [ax^2 + (a\alpha + b) x + (a\alpha^2 + b\alpha + c)] = a (x - \alpha)(x^2 + px + q),$$

在哪里

$$p = \frac{a\alpha + b}{a}, \quad q = \frac{a\alpha^2 + b\alpha + c}{a}.$$

⟦folio 10⟧

现在让我们尝试找出多项式（2）的根点$x = \alpha$成为函数$y = ax^3 + bx^2 + cx + d$的极值点的充分必要条件。

让我们使用公式（3）。如果 $x = \alpha$ 不是平方三项式 $x^2 + px + q$ 的根，则在点 $x = \alpha$ 足够小的邻域中，该三项式保留恒定符号，因此函数 $y = a(x - \alpha)(x^2 + px + q)$ 在经过点 $x = \alpha$ 时会改变符号。当$x = \alpha$是三项式的双根时，即$x^2 + px + q = (x - \alpha)^2$，因此$y = a(x - \alpha)^3$，情况也是如此。在所考虑的情况下，不存在极值。只有在一种情况下，函数在经过点$x = \alpha$时不会改变符号 - 当$x = \alpha$是平方三项式的单根，即$x^2 + px + q = (x - \alpha)(x - \beta)$，或者，相同的是，$x = \alpha$是多项式（2）的双根，即

$$y = a(x - \alpha)^2(x - \beta),$$

其中$\alpha \neq \beta$。

因此，多项式的根有一个度，即该根为双倍时的极值点和摩尔。

得到的结果总结如下：

定理2.为了使点$x = \alpha$成为函数$y = ax^3 + bx^2 + cx + d$的极值点，充分必要且存在任意数$m$，其多项式$P(x) = ax^3 + bx^2 + cx + d$有双根$x = \alpha$，即

$$P(x) = a(x - \alpha)^2(x - \beta),$$

(4)

食物$\alpha \neq \beta$。

定理 3（最大值和最小值的充分条件）。令函数$y = ax^3 + bx^2 + cx + d$在点$x = \alpha$处有极值，$m$为函数在点$x = \alpha$处的值。让我们用 (4) 的形式表示多项式 $P(x) = ax^3 + bx^2 + cx + d$。那么，如果$a(\beta - \alpha) > 0$，那么$x = \alpha$就是极大点；如果$a(\beta - \alpha) < 0$，那么$x = \alpha$就是最小点。

证明。如果$a > 0$和$\alpha < \beta$，那么在点$x = \alpha$的邻域中，不包含点$x = \beta$（图5），我们有$P(x) \leq 0$，即$y \leq m$。这意味着$x = \alpha$是极大点。如果$a < 0$和$\alpha > \beta$，那么也获得了最大值点。结合这两种情况，我们发现，如果$a(\beta - \alpha) > 0$，那么在$x = \alpha$点，函数$y$有最大值。定理的第二部分以类似的方式证明。

示例 2. 检查函数的极值

$$y = x^3 - 3x^2 - 9x + 5$$

(5)

并绘制它。

让我们尝试选择数字 $m$、$\alpha$、$\beta$，以便恒等式 $x^3 - 3x^2 - 9x + 5 - m = (x - \alpha)^2 \times (x - \beta)$ 成立（和 $\alpha \neq \beta$）。因此$x^3 - 3x^2 - 9x + 5 - m = x^3 - (\beta + 2\alpha)x^2 + (2\alpha\beta + \alpha^2)x - \alpha^2\beta$。为了找到 $m$、$\alpha$、$\beta$ 的值，我们得到了一个方程组：

$$\begin{align*}
\alpha_1 &= -1, \quad \beta_1 &= 5, \quad m_1 &= 10; \\
\alpha_2 &= 3, \quad \beta_2 &= -3, \quad m_2 &= -22.
\end{align*}$$

图 5.
