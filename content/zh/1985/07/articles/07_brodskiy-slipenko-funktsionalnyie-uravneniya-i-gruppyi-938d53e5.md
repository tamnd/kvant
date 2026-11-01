---
id: 1985-7-brodskiy-slipenko-funktsionalnyie-uravneniya-i-gruppyi-938d53e5
issue: kvant_1985_7
year: 1985
number: "7"
title: 函数方程和群
authors:
  - Бродский Я. С.
  - Слипенко А. К.
rubric: osnovnye-stati
page_first: 25
page_last: 27
page_labels: 23-25
tag: 7Y9R
lang: zh
source: kvant_digital
extraction: vision
content_sha256: 247d362c3a095a442e5ec3476ec683f5cf04d4029f4b6b3dc109a72a0e92a588
prompt_sha256: draft-1
translated_from: content/ru/1985/07/articles/07_brodskiy-slipenko-funktsionalnyie-uravneniya-i-gruppyi-938d53e5.md
source_content_sha256: d97218f3c456cbd397ee38b966ee5b298380d9b201cee247934f6f3136c929a5
translation_model: draft
translation_run: zh-draft-2026-11-01
translation_quality: draft
---

⟦folio 23⟧

函数方程和群

Y.S.布罗德斯基，A.K.斯利彭科

您可能熟悉函数方程，尽管您可能不知道它们的名字。因此，函数方程 $f(x)=f(-x), f(-x)=-f(x), f(x+a)=f(x)$ 定义了函数的偶数、奇数和周期性等性质。

一般来说，函数方程是一种确定的对应关系，您需要从中找到未知函数。

例如，$f(x+1)+f(x)=x,$
$2f(1-x)+1=xf(x),$
$xf(x)+f\left(\frac{4}{2-x}\right)=x$.

两百多年前，当数学家遇到力学问题时，他们就开始研究函数方程。 O. Cauchy (1789-1857) 对此类方程的研究做出了巨大贡献。在我们的期刊中，我们已经考虑过函数方程 $f(x+y)=f(x)+f(y)$，它以他的名字命名*）。在本文中，我们将考虑使用现代代数最重要的概念——群的概念来求解函数方程的方法之一。

功能组成

当然，您已经注意到，学校数学课程中学习的初始基本函数的数量相对较少。这些包括例如线性函数、幂函数、指数函数和三角函数。其他函数可以使用组合和代数运算从主要函数中获得。

因此，函数$f(x)=\sin(2x+1)$是线性函数$g(x)=2x+1$和三角函数$h(x)=\sin x$的复合，即$f(x)=h(g(x))=(h\circ g)(x)$。

函数$f(x)=\lg \arcsin x$是函数$g(x)=\arcsin x$和$h(x)=\lg x$合成的结果。请注意，组合定义的域$h\circ g$包括$D(g)$的$x$值，其中$g(x)\in D(h)$。在最后一个例子中$D(g)=[-1; 1], D(h)=] 0; \infty$。 [。由于$\arcsin x>0$位于$x\in] 0; 1]$，则$D(f)=] 0; 1]$。

如果我们以相反的顺序组合这些相同的函数，即函数$f(x)=\arcsin \lg x$，我们得到$D(f)=\left[\frac{1}{10}; 10\right]$。

分数线性函数$g(x)=\frac{-2x+1}{3x+2}$和$h(x)=\frac{3x-2}{-x+4}$的复合是函数$f(x)=h(g(x))=$
$$\frac{3\cdot\frac{-2x+1}{3x+2}-2}{-\frac{2x+1}{3x+2}+4}=\frac{-12x-1}{14x+7}, x\neq-\frac{2}{3}.$$
这里$D(f)=R\left\{-\frac{2}{3},-\frac{1}{2}\right\}$。

通常$f\circ g\neq g\circ f$。同时对于任何功能
$(f\circ g)\circ h=f\circ(g\circ h)$,

未表示的内容是从组合的定义中得出的。

战斗

1. 找出以下函数的组合 $f_1\circ f_2$ 和 $f_2\circ f_1$：
$f_1=\frac{x-2}{3x+4}, f_2=\frac{2x+3}{5x-1}$.

2. 求$1-x^2$和$\sqrt{x}$的复合域。

3. 让$f(x)=\frac{x}{\sqrt{1-x^2}}$。找到$f\circ f\circ f\cdots f$。

函数方程

我们来解决下面的问题。
问题 1. 找到所有满足以下条件的函数 $y=f(x)$
$$2f(1-x)+1=xf(x).$$

⟦folio 24⟧

解决方案。让我们假设有一个函数$f(x)$满足这个方程。将 $x$ 替换为 $1-x$，我们得到

$$2f(x) + 1 = (1 - x)f(1 - x).$$

从(1)我们找到$f(1 - x) = \frac{1}{2}(xf(x) - 1)$。

将$f(1 - x)$值代入式(2)，可得

$$2f(x) + 1 = (1 - x) \cdot \frac{1}{2} \cdot (xf(x) - 1),$$

从哪里$f(x) = \frac{x - 3}{x^2 - x + 4}$。

通过直接验证，我们确信所得函数满足方程（1）。

在所考虑的方程中，未知函数的下标是函数 $f_1 = x$ 和 $f_2 = 1 - x$。将 $x$ 替换为 $1 - x$ 将函数 $f_1$ 和 $f_2$ 相互映射。替换 $x \rightarrow 1 - x$ 产生另一个包含 $f(x)$ 和 $f(1 - x)$ 的方程。我们将函数方程的解简化为具有两个未知数的两个线性方程组的解。

现在让我们考虑一个更复杂的问题。

任务 2. 求解方程

$$xf(x) + 2f\left(\frac{x - 1}{x + 1}\right) = 1.$$

解决方案。让我们尝试以与第一种情况相同的方式进行操作。让我们替换 $x \rightarrow \frac{x - 1}{x + 1}$。我们得到

$$\frac{x - 1}{x + 1}f\left(\frac{x - 1}{x + 1}\right) + 2f\left(-\frac{1}{x}\right) = 1.$$

除了表达式 $f(x)$ 和 $f\left(\frac{x - 1}{x + 1}\right)$ 之外，我们现在还有一个新的“未知”$-f\left(-\frac{1}{x}\right)$。让我们尝试对 (3) 再应用一次替换：$x \rightarrow -\frac{1}{x}$。我们有

$$-\frac{1}{x}f\left(-\frac{1}{x}\right) + 2f\left(\frac{x + 1}{1 - x}\right) = 1.$$

除了$f\left(-\frac{1}{x}\right)$之外，方程中还出现了“未知”的表达式$f\left(\frac{x + 1}{1 - x}\right)$。好吧，让我们尝试将 $x \rightarrow \frac{x + 1}{1 - x}$ 代入 (3)。最后，我们删除它。我们得到

$$\frac{x + 1}{1 - x}f\left(\frac{x + 1}{1 - x}\right) + 2f(x) = 1,$$

在没有出现新的未知数的情况下，构造具有四个未知数$f(x)$、$f\left(\frac{x - 1}{x + 1}\right)$、$f\left(-\frac{1}{x}\right)$和$f\left(\frac{x + 1}{1 - x}\right)$的四个线性方程组(3) - (6)。我们依次排除$f\left(\frac{x - 1}{x + 1}\right)$、$f\left(-\frac{1}{x}\right)$、$f\left(\frac{x + 1}{1 - x}\right)$，找到$f(x) = \frac{4x^2 - x + 1}{5x(x - 1)}$（$x \neq -1, x \neq 0, x \neq 1$）。

与求解方程（1）时一样，我们假设存在满足（3）的函数。经检验，$f$满足式(3)。

团体出现

让我们尝试找出为什么我们能够解出上一段的方程。

让我们考虑另一个方程

$$f(x + 1) + f(x) = x.$$

它看起来并不比方程（3）更“可怕”，但所有用同样的方式求解它的尝试都是徒劳的：当替换$x \rightarrow x + 1$时，“未知”的$f(x + 2)$出现，等等。链条是不可更换的：我们永远不会得到线性系统。

回想一下，在求解第一个方程时，我们执行了替换 $x \rightarrow 1 - x$。同时$1 - x \rightarrow x$。也就是说，关于组合操作的两个函数$g_1(x) = x$和$g_2(x) = 1 - x$的行为类似于$g_1 \circ g_2 = g_2 \circ g_1 = g_2$、$g_2 \circ g_2 = g_1$、$g_1 \circ g_1 = g_1$。

考虑“乘法”表（在编号为 $i$ 的行和编号为 $j$ 的列的交叉点处有 $g_i \circ g_j$）。

该表的每一行和每一列都包含$g_1$和$g_2$。

现在我们需要

⟦folio 25⟧

解方程

$$a(x)f(x) + b(x)f(1-x) = c(x),$$

(*)

其中 $a, b, c$ 是一些函数。显然，通过代入$x \rightarrow 1-x$我们得到方程

$$a(1-x)f(1-x) + b(1-x)f(x) = c(1-x),$$

(**)

它与方程 (*) 一起形成相对函数 $f(x)$ 和 $f(1-x)$ 的线性系统。此外，该解决方案将以与解决问题 1 相同的方式展开。

在第二个例子中，我们进行了替换

$$x \rightarrow \frac{x-1}{x+1}, x \rightarrow -\frac{1}{x}, x \rightarrow \frac{x+1}{1-x},$$

也就是说，名称处理函数

$$g_1(x) = x, g_2(x) = \frac{x-1}{x+1},$$

$$g_3(x) = -\frac{1}{x}, g_4(x) = \frac{x+1}{1-x}.$$

让我们看看函数 $g_1, g_2, g_3, g_4$ 与组合操作的关系如何。让我们编写表 2，与表 1 类似（在第 $i$ 行和 $k$ 列的交叉点，我们编写 $g_i \circ g_k$）。

该表关于其对角线对称（这意味着 $g_i \circ g_k = g_k \circ g_i$ 对于任何 $k$ 和 $i$）。而且，所有函数$g_i$在每一行每一列中均等地出现一次，最后很容易注意到$g_3 = g_2^2, g_4 = g_3^2, g_1 = g_2^4$。这里$g_i^2 = g_2 \circ g_2 \circ \dots \circ g_2$。

因此，函数 $G = \{g_1, g_2, g_3, g_4\}$ 系统具有以下性质： a) 它在组合下是闭的； b) 这些函数之间存在相同的映射$g_1(x) = x$； c) 每个函数 $g_i$ 都有一个反函数 $g_i^{-1}: g_1^{-1} = g_1, g_2^{-1} = g_4, g_3^{-1} = g_3, g_4^{-1} = g_2$。

示例 1 中的函数$G = \{g_1, g_2\}$ 系统具有相同的属性。

如果我们现在被要求求解任何形式的函数方程

$$a(x)f(x) + b(x)f\left(\frac{x-1}{x+1}\right) + c(x)f\left(-\frac{1}{x}\right) + d(x)f\left(\frac{x+1}{1-x}\right) = h(x),$$

(***)

我们可以通过替换 $x \rightarrow g_2(x), x \rightarrow g_3(x), x \rightarrow g_4(x)$ 来做到这一点，之后我们将得到一个线性系统。例如，我们记下替换 $x \rightarrow g_2(x)$ 后 (***) 的结果。

此外，$g_2(x) \rightarrow g_3(x), g_3(x) \rightarrow g_4(x), g_4(x) \rightarrow g_1(x)$，所以我们得到方程

$$a\left(\frac{x-1}{x+1}\right)f\left(\frac{x-1}{x+1}\right) + b\left(\frac{x-1}{x+1}\right)f\left(-\frac{1}{x}\right) + c\left(\frac{x-1}{x+1}\right) \cdot f\left(\frac{x+1}{1-x}\right) + d\left(\frac{x-1}{x+1}\right)f(x) = h\left(\frac{x-1}{x+1}\right).$$

现在我们给出以下定义。

关于极限。在某个集合 $M$ 上定义的函数的任意集合 $G$ 相对于操作 $\circ$ 被称为 *epynnoi*，如果它具有与系统 $(g_1, g_2, g_3, g_4)$ 相同的属性，即

1. 对于任意两个函数$f \in G, g \in G$，它们的组合$f \circ g$也属于$G$。
2. 函数$e(x) = x$属于$G$。
3. 对于每个函数$f \in G$，都有一个属于$G$的反函数$f^{-1}$。

这个定义是群概念一般定义的特例——群是现代数学最重要的概念之一。 P. S. Aleksandrov 所著的《群论导论》（Library «Kvant»，第 7 期，M.：Nauka，1980）一书中详细且通俗地介绍了群论的基本概念。

我们已经看到了两个函数组的例子。我们再举几个例子。

a) 集合线性函数$f(x) = ax + b$、($a \neq 0, b \in R$)的$G$；

b）$G = \{x, \frac{1}{1-x}, \frac{x-1}{x}\} \in R\{0, 1\}$；

b) $G = \{x, \frac{1}{1-x}, \frac{x-1}{x}\} \in R\{0, 1\}$;
