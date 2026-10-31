---
id: 1973-2-vaguten-chisla-cnk-mnogochlenyi-posledovatelnosti-6d842221
issue: kvant_1973_2
year: 1973
number: "2"
title: 数字 C_n^k、多项式、序列
authors:
  - Вагутен В. Н.
rubric: osnovnye-stati
page_first: 29
page_last: 34
page_labels: 27-32
tag: WEA5
lang: zh
source: kvant_digital
extraction: vision
content_sha256: 873255d0bb158a15f5b7f7e358028ffd31fc2b92b50a662a8c6669e6d308159c
prompt_sha256: draft-1
translated_from: content/ru/1973/02/articles/07_vaguten-chisla-cnk-mnogochlenyi-posledovatelnosti-6d842221.md
source_content_sha256: 33c13a6eb39ad91f30cbc5e0c1681727c040b26fd1acea92251da62a900a4cc6
translation_model: draft
translation_run: zh-draft-2026-10-31
translation_quality: draft
---

⟦folio 27⟧

数字 $C_n^k$、多项式、序列
（解决一个问题的多种方法）
V·N·瓦古曼

让我们回忆一下“问题«Kvant»”中的一个问题，其初等解写在1972年的«Kvant»第12号中。

M138。证明如果 $m$ 和 $n$ 是数 $1 < m < n$ 的项，则

$$\sum_{k=1}^{n} (-1)^k k^m C_k^k = 0,$$

它的$C_k^k$是生物系数。

这些观点的各种证明将成为我们向读者介绍一些学校课程中未包含的重要数学概念和事实（有限差分、多项式插值公式、任意多项式、指数幂级数）的好机会。遵循每个段落中的定义和定理，读者将遇到“让我们现在回到我们的问题”这句话，然后是一个新的解决方案���题 M138。

定理的证明可以跳过，但最好解析它们，尽管这并不容易做到，因为它们写得非常简短。

介绍。生物矿物质系数和问题表述

我们列出了数字$C_n^k$的几个属性。 0.1-0.3 中的每个属性都可以用来定义这些数字。

0.1。 $C_n^k$ — 多项式系数

$$(a + x)^n = C_n^0 a^n + C_n^1 a^{n-1} x + \dots + C_n^k a^{n-k} x^k + \dots + C_n^n x^n.$$

0.2。 $C_n^0 = 1; C_n^n = 1$；对于每个$k = 1,2, \dots, n - 1$

$$C_n^k = C_{n-1}^{k-1} + C_{n-1}^k.$$

0.3。对于所有 $n$ 和 $k$ ($0 \leqslant k \leqslant n$)

$$C_n^k = \frac{n(n-1)\dots(n-k+1)}{1 \cdot 2 \cdot \dots \cdot k},$$ 或 $C_n^k = \frac{n!}{k!(n-k)!},$

其中$m! = 1 \cdot 2 \cdot 3 \dots m; \quad 0! = 1! = 1$。

练习 0. a) 找出从 1 到 10 的所有 $n$ 的数字 $C_n^k$，使用每个定义 0.1、0.2、0.3。 b) 从 0.1 打印 0.2，使用 tokdev $(a + x)^n = (a + x)^{n-1}(a + x)$。 b) 从 0.2 导出 0.3，使用数学归纳法

⟦folio 28⟧

tsini（即，检查如果公式（3）对于$n-1$成立，那么对于$n$也成立）。
d) 检查$C_n^k = C_n^{n-k}$。

多项式$a + x$有时被称为“二项式”（bin与double相同），公式（1）是“牛顿二项式”的公式，数字$C_n^k$是“二项式系数”。

让我们在等式（1）中设置 $a$ 等于 1。我们得到

$$(1 + x)^n = C_n^0 + C_n^1 x + \dots + C_n^k x^k + \dots + C_n^n x^n.$$

在这里代入$x = -1$，我们得到

$$C_n^0 - C_n^1 + C_n^2 - \dots + (-1)^k C_n^k + \dots + (-1)^n C_n^n = 0.$$

事实证明，除了对应关系（5）之外，对于数字$C_n^k$，以下等式也成立：

$$- C_n^1 + 2 C_n^2 - 3 C_n^3 + \dots + (-1)^n n C_n^n = 0,$$
$$- C_n^1 + 2^2 C_n^2 - 3^2 C_n^3 + \dots + (-1)^n n^2 C_n^n = 0,$$
$$- C_n^1 + 2^{n-1} C_n^2 - 3^{n-1} C_n^3 + \dots + (-1)^n n^{n-1} C_n^n = 0.$$

���题 M138中需要证明的正是这些等式；它们将在每段末尾进行讨论。

将来，我们将经常使用 $\Sigma$ 图标来表示金额。例如，式(1)可简写如下：

$$(a + x)^n = \sum_{k=0}^{k=n} C_n^k a^{n-k} x^k,$$
式(4) $-(1 + x)^n = \sum_{k=0}^{k=n} C_n^k x^k,$
等式 (5) $-\sum_{k=0}^{k=n} (-1)^k C_n^k = 0$，最后是等式 (6)，需要在 ���题 M138 中证明 -

$$\sum_{k=1}^{k=n} (-1)^k k^m C_n^k = 0$$

对于每个自然$m < n$。

§ 1. 序列和有限差分

让非负整数 0, 1, 2, 3... 的集合被赋予一个函数 $f$。这意味着给定序列

$$f(0), f(1), f(2), f(3), \dots$$

如果从序列$f$的每个成员中，当然，除了第一个成员，我们减去序列的前一个成员，然后我们得到一个新序列 - 差异序列

$$f(1) - f(0), f(2) - f(1), f(3) - f(2), \dots$$

让我们用$\Delta f$表示相应的函数：$\Delta f(0) = f(1) - f(0);$
$\Delta f(1) = f(2) - f(1);$ $\Delta f(2) = f(3) - f(2) \dots$

如果我们执行相同的操作 - 从 $f$ 到 $\Delta f$ 的转换 - 使用序列 $\Delta f$，那么我们得到序列

$$f(2) - 2f(1) + f(0), f(3) - 2f(2) + f(1), \dots$$

我们用$\Delta^2 f$来表示它。

⟦folio 29⟧

该序列称为$f$的二阶差分序列。让我们再次明确一下，我们得到了第三个差异的序列 - $\Delta^3 f$：

$$f(3) - 3f(2) + 3f(1) - f(0), f(4) - 3f(3) + 3f(2) - f(1), \dots$$

等等。

因此，根据定义

$$\Delta^{n+1}f(x) = \Delta^n f(x + 1) - \Delta^n f(x).$$

(7)

（回想一下，函数 $f$、$\Delta f$、$\Delta^2 f$、... 的参数 $x$ 采用非负整数值：$x = 0, 1, 2, \dots$）。

作为第一个示例，考虑常数函数 $f$：

$$f(0) = f(1) = f(2) = \dots = a.$$

对于它，差值序列$\Delta f$显然仅由零组成。让我们简单地写成这样：$\Delta f \equiv 0$（对于所有$x$）。

当然，序列$\Delta^2 f$，...，$\Delta^n f$也将仅由零组成，即$\Delta^n f \equiv 0$。

如果$f$是线性函数：$f(x) = ax + b$，即如果序列用等差数列$b, a + b, 2a + b, 3a + b, \dots$表示，那么序列$\Delta f$的所有项将等于同一个数$a$。因此$\Delta^2 f \equiv 0$。

如果 $f$ 是二次三项式 $f(x) = ax^2 + bx + c$，则 $\Delta f$ 是线性函数（来自数字 $x$）：

$$\Delta f(x) = f(x + 1) - f(x) = a(x + 1)^2 + b(x + 1) + c - ax^2 - bx - c = 2ax + b.$$

那么$\Delta^2 f$是一个常数函数：$\Delta^2 f = 2a$。因此，$\Delta^3 f = 0$，当然还有$\Delta^n f = 0$，对于所有$n > 2$。

我们没有权利 1. a) 让 $f(x) = x^3$。查找$\Delta f$、$\Delta^2 f$、$\Delta^3 f$、... 6) 如果$f(x) = 2^x$，同样的问题。

我们的观察总结为以下两个定理。

1.1.数字$\Delta^n f(x)$根据公式通过函数$f$的值来表示

$$\Delta^n f(x) = C_n^0 f(x + n) - C_n^1 f(x + n - 1) + \dots + (-1)^n C_n^n f(x) =$$

$$= \sum_{k=0}^{k=n} (-1)^k C_n^k f(x + n - k).$$

1.2.如果 $f(x)$ 是$m < n$ 次多项式，则$\Delta^n f = 0$。

陈述1.1和1.2都可以通过$n$归纳证明。对于 $n = 1, 2, 3$ 我们已经检查过了。假设它们对于$n$成立，我们证明它们对于$n+1$。

1.1.利用(7)、(8)和(2)，我们得到

$$\Delta^{n+1}f(x) = \Delta^n f(x + 1) - \Delta^n f(x) =$$

$$= C_n^0 f(x + n + 1) - C_n^1 f(x + n) + \dots + (-1)^n C_n^n f(x) - C_n^0 f(x + n) + \dots + (-1)^n C_n^n f(x) =$$

$$= C_n^0 f(x + n + 1) - C_n^1 f(x + n) + \dots + (-1)^n C_n^n f(x + n) + (-1)^n \times C_n^n f(x).$$

1.2.让$f(x) = a_0 + a_1 x + \dots + a_j x^j + \dots + a_m x^m$。我们的 $m$ 等式（它们来自 (4)）

$$(x + 1)^j - x^j = C_j^1 x^{j-1} + C_j^2 x^{j-2} + \dots + C_j^{j-1} x + 1$$

（这里$j = 1, 2, \dots, m$）。让我们将它们相应地乘以系数 $a_j$ 并相加。我们得到：左边是$\Delta f(x) = f(x + 1) - f(x)$，右边是$g(x)$的某个多项式，次数不高于$m - 1$。如果$m < n$，则$m - 1 < n - 1$，并根据归纳假设$\Delta^{n-1}g = 0$。因此，$\Delta^n f = \Delta^{n-1} (\Delta f) = \Delta^n g = 0$。

⟦folio 30⟧

现在让我们回到我们的任务。

平等 (6')，根据 1.1。我确切地知道$\Delta^n f(0) = 0$对应于函数$f(x) = x^m$，这直接来自语句1.2。

问题1.设$f(x) = a + a_1x + \dots + a_nx^n$。找到$\Delta^n f$。使用此结果计算总和

$$\sum_{k=0}^{k=n} (-1)^k k^n C_n^k.$$

问题2.证明对于所有$x$都存在$\Delta^{n+1} f(x) = 0$，则$f(x)$是次数最多$n$的多项式。

问题 3. 查找 $\Delta f(x) = \lambda f(x)$ 的所有序列 $f$，其中 $\lambda$ 是某个数字。

§ 2. 多项式和插值公式

我们知道通过两点我们可以画一条直线。换句话说，如果给定两对数字$(\alpha_0, \beta_0), (\alpha_1, \beta_1)$和$\alpha_0 \neq \alpha_1$，则存在一个唯一的次数不高于第一个$P(x) = ax + b$的多项式，使得$P(\alpha_0) = \beta_0$和$P(\alpha_1) = \beta_1$。

这一事实总结如下。

给定$n + 1$不同的数字$\alpha_0, \alpha_1, \dots, \alpha_n$和$n + 1$数字$\beta_0, \beta_1, \dots, \beta_n$。那么以下陈述都是正确的。

2.1.存在次数不高于 $n$ 的多项式 $P$ 使得

$$P(\alpha_i) = \beta_i \quad (\text{для всех } i = 0,1,\dots,n).$$

2.2.多项式 $P$ 是唯一定义的。

为了证明2.1，想象这样一个多项式就足够了。为此，首先考虑多项式

$$D_k(x) = \frac{(x - \alpha_0)(x - \alpha_1)\dots(x - \alpha_{k-1})(x - \alpha_{k+1})\dots(x - \alpha_n)}{(\alpha_k - \alpha_0)(\alpha_k - \alpha_1)\dots(\alpha_k - \alpha_{k-1})(\alpha_k - \alpha_{k+1})\dots(\alpha_k - \alpha_n)}$$

（转换为 $n$ 多项式的分子和分母）。很明显

$$D_k(\alpha_i) = \begin{cases} 1, \text{ если } i = k; \\ 0, \text{ если } i \neq k. \end{cases}$$

现在让我们将 $D_k(x)$ 乘以数字 $\beta_k$ 并将所有这些多项式相加。获得多项式

$$P(x) = \sum_{k=0}^{k=n} \beta_k D_k(x)$$

所有等式（9）都得到满足。

为了证明 2.2，我们需要关于多项式根的两个重要定理。

2.3.如果一个多项式

$$f(x) = a_0 + a_1x + \dots + a_nx^n$$

不同根的次数不高于$n + 1$，则该多项式等于0，即$a_0 = a_1 = a_2 = \dots = a_n = 0$。

2.4. （“贝佐特定理”。）如果$\alpha$是多项式$f(x)$的根，则多项式$f(x)$可以被$x - \alpha$整除，即

$$f(x) = (x - \alpha)g(x),$$

food $g(x)$ 是某个多项式。

⟦folio 31⟧

证明2.4。我们写下$n$点$(x^j - \alpha^j) = (x - \alpha)(x^{j-1} + x^{j-2}\alpha + \ldots + \alpha^{j-2}x + \alpha^{j-1})$、$(j=1, 2, \ldots, n)$，分别将它们乘以系数$a_j$，然后将所有这些点相加。我们得到一个对任何多项式 (12) 和任何数字 $\alpha$ 都有效的公式：

$$f(x) - f(\alpha) = (x - \alpha)g(x),$$

其中 $g(x)$ 是某个多项式。特别地，如果$f(\alpha)=0$，我们得到(13)。

证明2.3。我们对$n$进行归纳。对于 $n=1$ 陈述 2.3 是显而易见的。让我们证明，如果对于 $n-1$ 成立，那么对于 $n$ 也成立。令 $\alpha_0, \alpha_1, \ldots, \alpha_n$ 为多项式 (12) 的根。那么根据2.4：

$$f(x) = (x - \alpha_n)g(x),$$

此外，多项式$g(x)$的次数最多为$n-1$，并且有$n$个不同的根$\alpha_0, \alpha_1, \ldots, \alpha_{n-1}$。根据归纳假设，$g(x)$等于0；从 (14) 可知 $f(x)$ 也等于 0。

证明2.2。令 $p_1$ 和 $p_2$ 为两个多项式，其中等式 (9) 均成立。那么它们的差满足定理2.3（多项式$f(x) = p_1(x) - p_2(x)$）的条件，次数不高于$n+1$根$\alpha_0, \alpha_1, \ldots, \alpha_n$，因此等于零，即$p_1(x) = p_2(x)$。

所以，我们已经证明，通过$n+1$点$(\alpha_0, \beta_0), (\alpha_1, \beta_1), \ldots, (\alpha_n, \beta_n)$我们可以证明以下形式的唯一曲线

$$y = f(x) = a_0 + a_1x + \ldots + a_nx^n,$$

甚至提供了一个公式，可以让您立即写出所需的多项式。该式(11)称为Laerang积分公式。

练习2. a) 找到一个正方三角形，它在点2、3、5处属于对应的值7、11、13。 6) 找到一个次数不大于4的多项式，其图形通过点$(-2, -7), (-1, 0), (0, 1), (1, 2), (2, 9)$。

让我们回到我们的任务。让我们构造一个次数最多$n$的多项式，它在点$\alpha_k = k(k=0, 1, 2, \ldots, n)$属于相应的$\beta_k = k^m$的值。从公式（11）可知，该多项式等于 $\sum_{k=0}^{k=n} k^mD_k(x)$，其中

$$D_k(x) = \frac{x(x-1)\ldots(x-k+1)(x-k-1)\ldots(x-n)}{k(k-1)\ldots1(-1)(-2)\ldots(k-n)}.$$

显然，多项式 (15) 的 $x^n$ 系数等于

$$\frac{1}{k(k-1)\ldots1(-1)(-2)\ldots(k-n)} = (-1)^{k-n} \frac{1}{k!(n-k)!} = \frac{(-1)^n}{n!} (-1)^k C_n^k,$$

多项式 $P(x)$ 的 $x^n$ 系数实际上等于

$$(1/n!) (-1)^n \sum_{k=0}^{k=n} (-1)^k k^m C_n^k.$$

另一方面，很明显多项式 $P(x)$ 就是 $x^m$，因为 $m < n$。因此，$x^n$$P(x)$的系数为零。

任务 4. 证明数集 $y_0, y_1, \ldots, y_n$ 满足以下条件：“对于任何次数不高于 $n-1$ 的多项式 $f(x)$ 等式

$$\sum_{k=0}^{k=n} f(k)y_k = 0»,$$

当且仅当$y_k = t(-1)^k C_n^k$，其中$t$是某个数字。

⟦folio 32⟧

任务 5（概括）。证明如果数字 $\alpha_0, \alpha_1, \dots, \alpha_n$ 两两不同，则方程组

$$y_0 + y_1 + \dots + y_n = 0,$$
$$\alpha_0 y_0 + \alpha_1 y_1 + \dots + \alpha_n y_n = 0,$$
$$\alpha_0^2 y_0 + \alpha_1^2 y_1 + \dots + \alpha_n^2 y_n = 0,$$
$$\alpha_0^{n-1} y_0 + \alpha_1^{n-1} y_1 + \dots + \alpha_n^{n-1} y_n = 0$$

有一组数字的解

$$y_k = \frac{t}{(\alpha_k - \alpha_1)(\alpha_h - \alpha_2) \dots (\alpha_k - \alpha_{k-1})(\alpha_h - \alpha_{k+1}) \dots (\alpha_h - \alpha_n)}$$

($k=0, 1, \dots, n+1$)，其中$t$是任意数，没有其他解。

§ 3. 导数多项式和多重根

令 $f(x)$ 为 $n$ 次多项式：

$$f(x) = a_0 + a_1 x + a_2 x^2 + \dots + a_{n-1} x^{n-1} + a_n x^n = \sum_{k=0}^{k=n} a_k x^k.$$

那么根据定义，次数为 $n-1$ 的多项式

$$f'(x) = a_1 + 2 a_2 x + \dots + (n-1) a_{n-1} x^{n-2} + n a_n x^{n-1} = \sum_{k=1}^{k=n} ka_k x^{k-1}$$

称为任意多项式$f(x)$。以下陈述事实证明是正确的。

3.1.如果多项式 $f(x)$ 能被 $(x - \alpha)^{m+1}$ 整除，则多项式 $f'(x)$ 能被 $(x - \alpha)^m$ 整除。换句话说，如果数字$\alpha$是多项式$f(x)$的重数$m+1$的根，则$\alpha$是多项式$f'(x)$的至少$m$的重数根。

对于证明3.1。我们使用这个引理。

3.2.若$f(x) = (x - \alpha)g(x)$，则

$$f'(x) = g(x) + (x - \alpha)g'(x).$$

(16)

证明3.2。如果$g(x) = b_{n-1} x^{n-1} + \dots + b_1 x + b_0$，那么，不难检验，利用任意多项式的定义，等式（16）的左右两边都相等

$$(b_0 - b_1 \alpha) + 2 (b_1 - b_2 \alpha) x + \dots + (n-1) (b_{n-2} - b_{n-1} \alpha) x^{n-2} + n b_{n-1} x^{n-1}.$$

证明 3.1 通过使用 $m$ 的 indykation 进行验证。让我们检查 3.1 中的 $m=1$。如果$f(x)$能被$(x - \alpha)^2$整除，则$f(x) = (x - \alpha) g(x)$，其中$g(x)$能被$(x - \alpha)$整除，并且从(16)可以看出，$f'(x)$也能被$(x - \alpha)$整除。

证明3.1对于$m-1$成立，那么对于$m$也成立。令$f(x)$能被$(x - \alpha)^{m+1}$整除。然后$f(x) = (x - \alpha) g(x)$，其中$g(x)$可被$(x - \alpha)^m$整除，并且从(16)可知$f'(x)$可被$(x - \alpha)^m$整除（通过indyktion提案，$g'(x)$可被$(x - \alpha)^{m-1}$整除）。

练习 3. a) 多项式 $x^3 - x^2 - 8x + 12$ 有重根吗？

6) 找到 $a, b$ 和 $c$，使得多项式 $x^3 + ax^2 + bx + c$ 能被 $(x+1)^2$ 整除。

现在让我们回到我们的任务。等式 (6') 的确切含义是多项式 $f_m(x) = \sum_{k=0}^{k=n} k^m C_k^n x^{k-1}$ 以数字 $x = -1$ 作为根。

让我们证明一个更强的说法：多项式$x f_m(x)$以数字$(-1)$作为重数$n-m$的根，也就是说，它可以被$(x+1)^{n-m}$整除（如果$m < n$）。

对于$xf_0(x) = \sum_{k=0}^{k=n} C_k^n x^k = (1+x)^n$来说这是非常方便的。对于 $0 < m < n$，我们对 $m$ 进行 indykation。让$xf_{m-1}(x)$以数字$(-1)$为根倍数
