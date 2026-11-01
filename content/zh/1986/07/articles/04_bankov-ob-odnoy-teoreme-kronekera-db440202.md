---
id: 1986-7-bankov-ob-odnoy-teoreme-kronekera-db440202
issue: kvant_1986_7
year: 1986
number: "7"
title: 关于克罗内克定理
authors:
  - Банков К. Г.
rubric: osnovnye-stati
page_first: 7
page_last: 9
page_labels: 5-7
tag: 57C8
lang: zh
source: kvant_digital
extraction: vision
content_sha256: 4e09caad14837c89456072b7955c0e1f299ad391931c2f44623f155347ea4ef3
prompt_sha256: draft-1
translated_from: content/ru/1986/07/articles/04_bankov-ob-odnoy-teoreme-kronekera-db440202.md
source_content_sha256: 5fd8f7e68c8753d423f508c22b42d4ee9ccb69b8d06963a288d02f02ecf87577
translation_model: draft
translation_run: zh-draft-2026-11-01
translation_quality: draft
---

⟦folio 5⟧

关于一个定理
克罗内克

K.G.班科夫 (NRB)

这里讨论的定理在数论中起着突出的作用。然而，我们对它感兴趣还有另一个原因：在它的帮助下，可以简单地解决基本的公式化但本质上困难的问题。在提出定理本身之前，我们将考虑两个这样的问题。

问题1. 证明存在一个2的幂，其十进制以数字1986开头。

为了解决这个问题，我们需要找到一个度$m \in N$，使得$10^n \cdot 1986 < 2^m < 10^n \cdot 1987$对于某些$n$。以 10 为底取对数，我们得到

$$\lg 1986 + \lg 10^n < \lg 2 < \lg 1987 + \lg 10^n,$$

或者

$$\lg 1986 < \lg 2 - n < \lg 1987.$$

如果我们设法找到自然数$n$和$m$使得以下形式的数字之一，问题就会解决

$$\lg 2 - n, m, n \in N$$

(1)

落入一个小区间（lg 1986，lg 1987）。

问题 2. 在整数方形网格的顶点处绘制

相同的小猫（图1）。证明如果数字$k$是无理数，则射线$y = kx$、$x \geq 0$将相交，除了中心的那条之外，至少还有一只猫。

令$2\varepsilon_0$为“猫的宽度”，换句话说，让中心猫沿着线段$[-\varepsilon_0; \varepsilon_0]$与轴$Ox$相交。为了确定这一点，我们假设梁位于第一个正方形中（其余情况类似）。然后射线与直线 $y = 1, 2, \dots, n, \dots$ 相交于横坐标为 $\alpha, 2\alpha, \dots, n\alpha, \dots$ 的点，其中 $\alpha = 1/k$。如果我们找到自然的$n$和$m$使得问题就解决了

$$m - \varepsilon_0 < n\alpha < m + \varepsilon_0,$$

或者

$$-\varepsilon_0 < n\alpha - m < \varepsilon_0,$$

⟦folio 6⟧

也就是说，我们可以确定以下形式的数字之一
$$n\alpha - m, n, m \in \mathbb{N},$$
(2)
服务间隔很小$(-\varepsilon_0, \varepsilon_0)$。

克罗内卡定理*) 的非凡思想是，诸如 (1) 和 (2) 之类的集合包含位​​于任何区间中的数字。为了给出该定理的精确表述，我们需要一个定义。

如果任何区间包含该集合的元素，则称数字集 $A \subset \mathbb{R}$ 处处稠密（在 $\mathbb{R}$ 中）。换句话说，如果对于任何数字 $x, y \in \mathbb{R}$、$x < y$ 都存在 $a \in A$ 使得 $x < a < y$，则 $A$ 在 $\mathbb{R}$ 中处处稠密。

锻炼
1. 指出以下哪些集合在 $\mathbb{R}$ 中处处稠密： a) 所有有理数； b) 所有无理数； c) $n + 5m/17$ ($n, m \in \mathbb{Z}$) 形式的所有数字； d) $n + k/m$ ($n, k, m \in \mathbb{Z}$) 形式的所有数字。
2. 令集合 $A$ 在 $\mathbb{R}$ 和 $r \neq 0$ 中处处稠密，为实数。证明然后集合
$$B = \{a + r; a \in A\}, C = \{ra, a \in A\}$$
$\mathbb{R}$ 中处处密集。

**克罗涅卡定理。** 对于任意无理数 $a \neq 0$ 集合
$$\{m\alpha + n; m, n \in \mathbb{Z}\}$$
(3) $\mathbb{R}$ 处处密集。

证明。我们需要确定，对于任何两个数字$x, y$，对于$x < y$，都存在$m\alpha + n$形式的数字，其中$m, n \in \mathbb{Z}$使得$x < m\alpha + n < y$。让我们用$\delta$表示区间$\Delta = (x; y)$的长度并除以区间[0; 1] 分成有限数量的区间$\Delta_1, \Delta_2, \dots, \Delta_n$，每个区间的长度小于$\delta$。现在让我们注意到，对于任何非常大的整数$m$，都有一个整数$n$，其数字$m\alpha + n$位于区间[0; 1]。由于整数有无限多个，并且段 [0; 1]被划分为有限个区间，有整数$m_1, m_2, n_1, n_2$与$m_1 \neq m_2$以及数字$m_1\alpha + n_1$和$m_2\alpha + n_2$位于同一区间$\Delta_i$。这意味着数字$a = (m_1 - m_2)\alpha + (n_1 - n_2)$的绝对值小于$\delta$。此外，等式$a = 0$不可能为真，因为它意味着$a = \frac{n_2 - n_1}{m_1 - m_2}$是一个有理数。从上面可以看出，$a$的某个倍数（也具有$m\alpha + n$的形式，不是整数）将属于$\Delta = (x; y)$；定理被证明。

评论。如果将集合 (3) 替换为集合，定理仍然成立
$$\{m\alpha - n; m, n \in \mathbb{N}\}.$$

这很容易从已证明的定理中推出；我们把结论留给读者作为练习。

现在回到集合(1)和(2)，我们看到它们满足定理的条件：从而解决了问题1和2。 （我们认为已知数 lg 2 是无理数；然而，证明这一点并不困难。）

练习 3. 证明在猫问题中，非理性条件 $k$ 不能被省略。

让我们考虑另外几个问题，其解决方案使用克罗内卡定理。

问题 3. 证明存在一个自然数的平方，其描述符号以任意预定数字开头。

解决方案。我们来求一个小数点后第一位为 $-a_0a_1...a_s$ 的自然数的平方。让我们用$A$来表示数字$A = a_0a_1...a_s$。我们现在将寻找一个自然数$n$，使得对于某些自然数$k$，不等式成立
$$A \cdot 10^k < n^2 < (A + 1) \cdot 10^k,$$
或lg$A < 2\lg n - k < \lg (A + 1)$。
如果我们选择数字$n$等于$n = 2^m$，并且数字$k$是偶数$k = 2t$，那么lg$A < 2mlg 2 - 2t < \lg (A + 1)$。 (5)

根据定理、代入（见（4））和练习2，集合
$$\{2mlg 2 - 2t; m, t \in \mathbb{N}\}$$ 处处稠密，因此存在数字 $m$ 和 $t$ (5) 为真。问题解决方案。

为了解决以下问题，我们还需要如下声明：

引理。如果两个连续函数在参数是相同处处稠密集的元素时取相同的值，那么它们处处重合。

这个引理是“几何的”；它的公式化证明没有吸引力（虽然并不困难），所以我们不展示它。

问题 4. 证明函数
$$f(x) = \sin x + \sin \pi x$$
非维罗伊德。

解决方案。让我们假设函数$f$是非veroidal的，并用$T \neq 0$表示其中之一

⟦folio 7⟧

ee 期间。然后平等
$$\sin \pi(x+T) + \sin \pi\sqrt{2}(x+T) = \sin \pi x + \sin \pi\sqrt{2}x$$
(6)
对于任何实数 $x$ 都成立。如果在这个等式中我们用任意四个REM数$2m$替换$x$，我们得到
$$\sin \pi T + \sin \pi\sqrt{2}(2m+T) = \sin (\pi\sqrt{2} \cdot 2m).$$
再次利用函数 sin 的周期性，我们得到等式
$$\sin \pi T + \sin \pi\sqrt{2}\left(2m + \frac{2n}{\sqrt{2}} + T\right) = \sin \pi\sqrt{2}\left(2m + \frac{2n}{\sqrt{2}}\right),$$
对于任何两个整数 $m$ 和 $n$ 都是如此。根据练习 2 的定理，设
$$\left\{ 2m + \frac{2n}{\sqrt{2}}; m, n \text{ — целые числа} \right\}$$
显然是稠密的。这意味着当函数 $\sin \pi T + \sin \pi\sqrt{2}(x+T)$ 和 sin $\pi\sqrt{2}x$ 的参数是同一稠密集的元素时，它们取相同的值，因此（根据引理）在各个方面都一致，即相等
$$\sin \pi T + \sin \pi\sqrt{2}(x+T) = \sin \pi\sqrt{2}x$$
(7)
对于任何实数 $x$ 都成立。 (6) 减去 (7)，我们得到
$$\sin \pi(x+T) \sin \pi T = \sin \pi x.$$
在最后一个等式中，我们放入 $x = T$；我们得到
$$\sin 2\pi T - \sin \pi T = \sin \pi T,$$
或者
$$\sin \pi T(\cos \pi T - 1) = 0.$$
从最后一个等式可以看出 $T$ 是一个整数。那么由(7)可得
$$\sin \pi\sqrt{2}(x+T) - \sin \pi\sqrt{2}x = 0,$$
或者
$$\sin \pi\sqrt{2}\frac{T}{2}\cos \pi\sqrt{2}\left(x + \frac{T}{2}\right) = 0.$$
由于存在 $x$ 的值
$$\cos \pi\sqrt{2}\left(x + \frac{T}{2}\right) \neq 0,$$，然​​后$\sin \pi\sqrt{2}\frac{T}{2} = 0$；由此可见$\sqrt{2}\frac{T}{2}$是一个整数。但是，另一方面，$T$也是一个整数，$T \neq 0$，这意味着$\sqrt{2}$是一个有理数，这是错误的。由此产生的矛盾证明函数 $f$ 是非周期函数。

这是与上面讨论的功能相关的另一个任务。
问题 5. 证明函数
$$f(x) = \sin \pi x + \sin \pi\sqrt{2}x$$
不能取值2，但取尽可能接近数字2的值。
解决方案。如果我们假设 $f(x) = 2$ 对于某些 $x$，那么同时相等将成立
$$\sin \pi x = 1$$和$\sin \pi\sqrt{2}x = 1$，因此不能表示数$\sqrt{2}$是有理数，但这是错误的。因此，$f(x) < 2$对于任何数字。
如果 $x$ 是 $2m + \frac{1}{2}$ 形式的任意数，其中 $m$ 是整数，则函数 $f$ 采用以下形式
$$f(x) = 1 + \sin \pi\sqrt{2}\left(2m + \frac{1}{2}\right).$$
让我们证明可以找到一个整数 $m$ ，其中
$$\sin \pi\sqrt{2}\left(2m + \frac{1}{2}\right)$$ 任意接近数字 1。考虑到函数 sin 的连续性，找到整数 $m$ 和 $n$ 使得数字 $\sqrt{2}\left(2m + \frac{1}{2}\right)$ 任意接近数字 $2n + \frac{1}{2}$ 就足够了。因此，只要证明对于任何正 $\varepsilon$ 都存在整数 $m$ 和 $n$ ，其中
$$2n + \frac{1}{2} - \varepsilon < \sqrt{2}\left(2m + \frac{1}{2}\right) < 2n + \frac{1}{2} + \varepsilon.$$
让我们将最后一个整数不等式转换为以下形式
$$1 - 2\varepsilon - \sqrt{2} < 4m\sqrt{2} - 4n < 1 + 2\varepsilon - \sqrt{2}.$$
现在我们都从定理和练习 2 出发。
问题 6. 找到 $f(x) = f(x+1) = f(x+\sqrt{2})$ 的所有连续实函数 $f$。
解决方案。令 $f$ 为连续函数，其中 $f(x) = f(x+1) = f(x+\sqrt{2})$。这意味着数字 1 和 $\sqrt{2}$ 是函数 $f$ 的周期。那么函数$f$的周期也是$m + n\sqrt{2}$形式的所有数字，其中$m$和$n$是整数，也就是说，对于任意两个整数$m$和$n$，等式$f(x + m + n\sqrt{2}) = f(x)$成立。最后一个相等意味着当$y$属于平面多重检查时，$f(x + y)$和$f(x)$取相同的值
$$\{m + n\sqrt{2}; m, n \text{ — целые числа}\}.$$
然后，根据引理，我们得到等式$f(x + y) = f(x)$对于每个数$y$都成立，即每个（实）数都是函数$f$的一个周期。现在，如果$x_1$和$x_2$是两个不同的数字，我们输入$y = x_2 - x_1$，然后
$$f(x_1) = f(x_1 + (x_2 - x_1)) = f(x_2).$$
因此，问题 6 的解将是所有$f(x) = a$形式的函数，其中$a$是一个常数。
