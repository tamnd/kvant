---
id: 1976-8-martyinov-teorema-ferma-dlya-mnogochlenov-b55cd489
issue: kvant_1976_8
year: 1976
number: "8"
title: 多项式的费马定理
authors:
  - Мартынов Б.
rubric: osnovnye-stati
page_first: 14
page_last: 17
page_labels: 12, 14, 15
tag: KU23
lang: zh
source: kvant_digital
extraction: vision
content_sha256: 76d64c6bb719d92772d96fbf2ef63a844f34df21b6078ad43af693d87babe00c
prompt_sha256: draft-1
translated_from: content/ru/1976/08/articles/04_martyinov-teorema-ferma-dlya-mnogochlenov-b55cd489.md
source_content_sha256: c9c2936e1bfe479d641e4a428778da28b852955b45dcccde71d527132b60704c
translation_model: draft
translation_run: zh-draft-2026-11-01
translation_quality: draft
---

⟦folio 12⟧

当然，你们都听说过费马大定理；它是他为自然数制定的。本文证明了多项式的费马定理。这篇文章很难。其中使用的一些事实超出了学校课程的范围。有兴趣的读者可以在 P. Kurat 和 G. Robbins 合着的《什么是数学》一书中或《初等数学百科全书》第二卷中找到他们需要的一切。

问题陈述

费马做出的假设是，$n > 2$的方程$x^n + y^n = z^n$在自然数中无解。尚未找到一般情况下这一假设的证明。

然而，事实证明，如果我们将自然数 $x$、$y$ 和 $z$ 替换为一个变量 $t$ 中的多项式：$x(t), y(t), z(t)$ - 并写出方程

$$[x(t)]^n + [y(t)]^n = [z(t)]^n,$$

（类似的定理已经被证明）。

让我们澄清问题的表述。首先，我们注意到，当且仅当多项式$p(t) \cdot x(t), p(t) \cdot y(t)$和$p(t) \cdot z(t)$满足方程（1）时，多项式$x(t), y(t)$和$z(t)$满足方程（1）（这里$p(t)$是任意非零多项式）。因此，只要证明互质多项式不存在三元组就足够了。如果多项式除了常数（常数是零次多项式）之外没有公因子，则称为互质。此外，我们当然必须排除平凡的解决方案：零次多项式的三元组，因为对于任何$a$和$b$，三元组

$$x(t) = a, y(t) = b, z(t) = \sqrt[n]{a^n + b^n},$$

显然 是费马方程的一个解。

顺便说一句，在$n = 1$，方程（1）在$x(t) = t, y(t) = t + 1, z(t) = 2t + 1$方向有解。

它也有 $n = 2$ 的解。轻松查看方向；多么三

$$x(t) = t^2 - 1, y(t) = 2t, z(t) = t^2 + 1$$

是方程的一个解

$$[x(t)]^2 + [y(t)]^2 = [z(t)]^2.$$

本文的目的是证明多项式的费马大定理的类似物：

对于 $n > 2$ 不存在三个互质多项式 $x(t),$

⟦folio 14⟧

让我们将证明分为几个阶段。

1. 根据条件$1^\circ - 3^\circ$，每两个多项式$x, y, z$都可以被唤醒。事实上，如果$x$和$y$有一个公约数$d$，那么$z^n$可以被$d^n$整除，然后$z$可以被$d$整除，也就是说，$d$是多项式$x, y$和$z$。这与条件$1^\circ$相矛盾。

2. 令 $m$ 为多项式 $x, y, z$ 的最高次（根据条件 $3^m > 0$）。我们可以假设次数 $m$ 有一个多项式 $z$。事实上，如果需要，原始方程可以关于$x, y, z$对称：有必要用$\varepsilon z$代替$z$，其中$\varepsilon$是一个复数，其$n$次方等于$-1: \varepsilon^n = -1$。我们得到

$$x^n + y^n + z^n = 0.$$

3. 令 $\varepsilon_1, \varepsilon_2, \dots, \varepsilon_n$ 为数 $-1$ $n$ 次的所有异根。我们得到的事实是，每个不同于零的复数都恰好有 $n$ 个不同的 $n$ 次根（参见点 1*）。然后将多项式$x^n + y^n$分解为多项式

$$x^n + y^n = (x - \varepsilon_1 y) (x - \varepsilon_2 y) \cdot \dots \cdot (x - \varepsilon_n y).$$

为了证明这一点，你可以这样构造它：取多项式$u^n + 1$，其根是数字$\varepsilon_1, \dots, \varepsilon_n$，将其分解为多项式：$u^n + 1 = (u - \varepsilon_1) \cdot (u - \varepsilon_2) \cdot \dots \cdot (u - \varepsilon_n)$（第2项*），然后将$u$与分数$\frac{x}{y}$一起代入并去掉分母。

4. 多项式$x - \varepsilon_i y$成对相互唤醒。事实上，如果非常数多项式 $d$ 是多项式 $x - \varepsilon_i y$ 和 $x - \varepsilon_j y$ ($i \neq k$) 的公约数，那么这些多项式的差等于 $(\varepsilon_h - \varepsilon_i) y$，也可以被 $d$整除，因此多项式 $y$ 可以被$d$（引入$\varepsilon_h - \varepsilon_i$是一个非零常数）。那么多项式 $x = (x - \varepsilon_i y) + \varepsilon_j y$ 可以被多项式 $d$整除，这与 $x$ 和 $y$ 的互质性相矛盾（第 1 项）。

5. 如果乘积成对互延，则每两个多项式都是$d$的公约数，则$z^n$能被$d^n$整除，$z$能被$d$整除，即$d$是多项式$x, y$的公多项式， $z$。这与条件$1^\circ$相矛盾。

我们在法规的补充中提供了第 5 点的证明。

6. 由于$x^n + y^n = (x - \varepsilon_i y) \times (x - \varepsilon_2 y) \dots (x - \varepsilon_n y) = z^n$和多项式$x - \varepsilon_i y$成对互繁，因此每个多项式$x - \varepsilon_i y$都是多项式的$n$次。设$x - \varepsilon_i y = u_i^n$，其中$u_i$是多项式。让我们用 $m_i$ 表示多项式 $u_i$ 的次数。

让我们在多项式 $u_i$ 中选择具有最多多项式 $u_1$ 的那个。我们假设多项式 $u_1$ 具有最多的多项式。

7. $m_1 < m$.

事实上，很明显 $m_1 \leq m$（回想一下 $m$ 是 $z$ 的幂）。如果等式 $m_1 = m$ 成立，则 $i > 1$ 的所有其他多项式 $x - \varepsilon_i y$ 都是常数。我们以 $x - \varepsilon_2 y$ 和 $x - \varepsilon_3 y$ 为例（这是可能的 - 毕竟，$n \geq 3$）。如果$x - \varepsilon_2 y = A$，$x - \varepsilon_3 y = B$，那么

$$(B - A) x - (B \varepsilon_2 - A \varepsilon_3) y = 0,$$

即$x = Cy$（输入$A \neq B$是证明），这与$x$和$y$的互素性相矛盾。

另请注意，$m_1 > 0$，即$u_1$，不是常数。

我们希望从多项式 $x, y, z$ 转向没有公共多项式的暗多项式，满足费马且最大次数小于 $m$。让我们证明多项式$u_1, u_2$和$u_3$（见第6节）乘以一些常数可以被视为这样的多项式。

⟦folio 15⟧

8. 我们有：

$$\begin{cases} x - \varepsilon_1 y = u_1^n, \\ x - \varepsilon_2 y = u_2^n, \\ x - \varepsilon_3 y = u_3^n. \end{cases}$$

让我们选择三个数字$c_1, c_2, c_3$（并非全部等于零），以便将这些等式与系数$c_1, c_2, c_3$相加时，躺着的部分变为零。显然，为此，系统必须执行

$$\begin{cases} c_1 + c_2 + c_3 = 0, \\ c_1 \varepsilon_1 + c_2 \varepsilon_2 + c_3 \varepsilon_3 = 0. \end{cases}$$

很容易找到它的至少一个非零解 - 例如，放入 $c_3 = 1$ 并求解所得的具有两个未知数的两个方程组。自己做一下这个计算。

找到 $c_1, c_2$ 和 $c_3$ 我们得到

$$c_1 u_1^n + c_2 u_2^n + c_3 u_3^n = 0.$$

《驱动》系数的$n$次方，可得：

$$\left[ \sqrt[n]{c_1} u_1 \right]^n + \left[ \sqrt[n]{c_2} u_2 \right]^n = \left[ \sqrt[n]{c_3} u_3 \right]^n.$$

很容易验证新的三个多项式满足与$x, y, z$相同的条件。与此同时，他们的学位下降最多（但仍为正数）。

我们的证明方法是由费马发明的，称为“无限下降”方法。不幸的是，这种方法无法证明费马方程在自然数中的不可解性，因为分解为简单多项式的唯一性定理不适用于$x - \varepsilon_i y$形式的数字，其中$x$和$y$是整数（参见第3段*，第13页）。对这个有趣问题的研究是通过“高等算术”——代数数理论——当前活跃发展的数学领域来进行的。

额外的

A.让我们证明文章第3段*中提出的陈述（参见第13页），即我们证明任何多项式都可以唯一地分解为不可约多项式的乘积（最多可达多项式的阶数，最多可达多项式，这是一个常数）。 （不可约多项式类似于自然数多项式中的素数：多项式 $q$ 如果它不能分解为除以下以外的非零次多项式的乘积，则称为不可约 $q$.)

首先，我们证明每个多项式都可以展开为不可约式的乘积。事实上，如果$Q$不可约，则$Q = Q_1 \cdot G_2$，其中$G_1$和$G_2$是一些多项式。如果$G_1$和$G_2$不可约，则得到必要的分解；如果$G_i$ ($i=1, 2$) 中的任何一个是可约的，那么$G_i = S_1^{(i)} \cdot S_2^{(i)}$，等等。很明显，这个过程将在有限数量的步骤后结束，因为多项式$Q$的次数是有限的。因此，我们获得了多项式分解为不可约乘积的结果。

现在我们要证明，如果对于不可约多项式，我们满足等式 $p_1 \cdot p_2 \dots p_l = q_1 \cdot q_2 \dots q_s$，则$l = s$，并且对于每个 i 都有一个$k$，使得 $q_i = c \cdot p_k$。为此，我们需要以下语句：如果两个多项式$u$和$v$的乘积$u \cdot v$可被不可约多项式$q$整除，则任何$u, v$可被$q$整除。让我们将多项式 $u$ 和 $v$ 除以多项式 $q$ 并留余数（欧几里德蠕变算法）。我们得到多项式$u$和$v$的余数，它们的次数都小于多项式$q$的次数，并且乘积$u \cdot v$可以被$q$整除。我们需要证明任意$u = 0$（则$u$可被$q$整除），任意$v = 0$（则$v$可被$q$整除）。让我们用数学归纳法（通过多项式$q$的次数）来证明这个命题。

感应底座。非常数不可约多项式的最小次数为 1。令 $q$ 为线性多项式。那么，如果$u \neq 0$和$v \neq 0$都不是，那么$u = \text{const}$和$v = \text{const}$。但$u \cdot v$也是一个常数，因此$u \cdot v$不能除以$q$。因此，该陈述对于线性不可约多项式是正确的。

归纳步骤。让我们假设该陈述对于所有次数小于多项式 $q$ 次数的不可约多项式都成立。让我们用多项式$q$来证明它。我们假设$u \cdot v \neq 0$。由于$u \cdot v$可被$q$整除，我们有：$u \cdot v = q \cdot q$、$q \neq 0$，并且多项式$q$的次数严格小于多项式$q$的次数（因为乘积$u \cdot v$的次数小于多项式$q$的次数）。让我们展开$q$
