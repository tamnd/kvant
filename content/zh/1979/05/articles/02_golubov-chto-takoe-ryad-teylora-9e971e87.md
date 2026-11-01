---
id: 1979-5-golubov-chto-takoe-ryad-teylora-9e971e87
issue: kvant_1979_5
year: 1979
number: "5"
title: 什么是泰勒级数？
authors:
  - Голубов Б. И.
rubric: osnovnye-stati
page_first: 4
page_last: 9
page_labels: 2, 4, 5, 6, 7
tag: GRIE
lang: zh
source: kvant_digital
extraction: vision
content_sha256: 8d6d550d36857ea0d9bde837ab7f98350705eb8966105a38ee1f6aea37af9d1c
prompt_sha256: draft-1
translated_from: content/ru/1979/05/articles/02_golubov-chto-takoe-ryad-teylora-9e971e87.md
source_content_sha256: 3b3d444a7304e8bfa436d15d37274f9db9f2563448572a3d299b21367477d170
translation_model: draft
translation_run: zh-draft-2026-11-01
translation_quality: draft
---

⟦folio 2⟧

B·戈卢博夫

什么是泰勒级数？

英国数学家布鲁克·泰勒的名字因他在 1715 年 29 岁时做出的发现而载入数学史。这个发现是什么？我们将尽力告诉您这一点。

看图1-3。它们显示了函数 $y = e^x$、$y = \frac{1}{1+x}$ 和 $y = \ln(1+x)$ 的图形。

每个 图 上的数字 1 显示在点 $x = 0$ 处对应图形的切线，即某个线性函数 $y = ax + b$ 的图形（检查对应函数到底是什么 -

系统蒸发散$y = 1+x$，$y = 1-x$和$y = x$）。每个 图 上的数字 2 表示方形三角形 $y = ax^2 + bx + c$ 的正切，在点 $x = 0$ 处，它与相应函数的图形相邻，比所有其他方形三角形“更接近”。更准确地说，我们讨论的是在点 $x = 0$ 处与相应函数及其任意一阶和二阶重合的方形三角形。在这些情况下，这些方形三角形的图形被认为与相应的图形具有二阶相切（检查相应的方形三角形 $y = 1+x + \frac{x^2}{2}$、$y = 1-x + x^2$ 和 $y = x - \frac{x^2}{2}$ 是否也是如此）。

最后，图1-3中的数字3显示了函数$y = ax^3 + bx^2 + cx + d$的图像，它与相应曲线在点$x = 0$处的图像具有三阶相切（很容易说，这是

⟦folio 4⟧

在本文中，我们将获得函数$y=\sin x$、$y=\cos x$、$y=e^x$和$y=\ln(1+\dot{x})$的泰勒级数。

从分析中获得必要的信息

首先，我们需要牛顿-莱布尼兹公式：

$$\int_a^b f(x) \, dx = F(b) - F(a),$$

其中函数 $f$ 在区间 $[a; b]$ 上连续，函数 $F$ 在该区间上是反导数。

此外，根据积分的几何意义，如果$f(x) \geq 0$在$[a; b]$（图5）上，则$\int_a^b f(x) \, dx \geq 0$。由此不难得出，如果区间$[a; b]$上的两个连续函数满足不等式$f(x) \leq g(x)$，则可以解释$\int_a^b f(x) \, dx \leq \int_a^b g(x) \, dx$，即连接不规则函数的不等式，得到同号的不等式。

最后，我们需要平等

$$\lim_{n \to \infty} \frac{x^n}{n!} = 0,$$

其中 $x$ 是任意实数。让我们证明一下。给定 $x$，让我们找到一个自然数 $N$ 使得 $\frac{|x|}{N+1} \leq y=f(x)$

图 5. $S = \int_a^b f(x) \, dx$.

$\leq \frac{1}{2}$。那么对于所有$n > N$，不等式都将得到满足

$$0 \leq \frac{|x|^n}{n!} = \frac{|x|}{1} \cdot \frac{|x|}{2} \cdot \dots \cdot \frac{|x|}{N} \times \times \frac{|x|}{N+1} \cdot \dots \cdot \frac{|x|}{n} \leq \frac{|x|^N}{N!} \cdot \left(\frac{1}{2}\right)^{n-N} = \frac{|x|^N \cdot 2^N}{N!} \cdot 2^{-n}.$$

由于$N$是固定的，因此对于$n \to \infty$，这些不等式右侧的数列的极限等于0。因此得出等式(1)。

函数 $\sin x$ 和 cos $x$ 的泰勒级数表示

让$x > 0$起作用。然后，对线段$[0; x]$上的不等式$\cos t \leq 1$进行积分，我们得到

$$\int_0^x \cos t \, dt \leq \int_0^x 1 \, dt.$$

但由于 sin $t$ 是 cos $t$ 的反导数，而 $t$ 是 1 的反导数，因此之前基于牛顿-莱布尼兹公式的不等式可以写为 $sin x \leq x$。这个不等式本来可以直接写出来，但我们想解释获得进一步不等式的原理，因此提出了它的证明。

对线段 $[0; x]$ 上的不等式 $\sin t \leq t$ 进行积分，我们得到

$$\int_0^x \sin t \, dt \leq \int_0^x t \, dt.$$

由于函数 - cos $t$ 是 sin $t$ 的反导数，并且 $\frac{t^2}{2}$ 是 $t$ 的反导数，因此之前基于牛顿-莱布尼兹公式的不等式采用以下形式

$$1 - cos x \leq \frac{x^2}{2} \text{ или } cos x \geq 1 - \frac{x^2}{2}.$$

积分器是沿线段$[0; x]$的不等式，并再次使用牛顿-莱布尼兹公式得出不等式$\sin x \geq x - \frac{x^3}{3!}$。

⟦folio 5⟧

继续顺序积分的过程（并使用数学归纳法），很容易证明不等式

$$\cos x \leq 1 - \frac{x^2}{2!} + \dots + \frac{x^{4n}}{(4n)!},$$

$$\sin x \leq x - \frac{x^3}{3!} + \dots + \frac{x^{4n+1}}{(4n+1)!},$$

$$\cos x \geq 1 - \frac{x^2}{2!} + \dots - \frac{x^{4n+2}}{(4n+2)!},$$

$$\sin x \geq x - \frac{x^3}{3!} + \dots - \frac{x^{4n+3}}{(4n+3)!},$$

其中$n = 0, 1, \dots, x > 0$。

结合第一个和第三个不等式 (2)，我们得到

$$1 - \frac{x^2}{2!} + \dots - \frac{x^{4n+2}}{(4n+2)!} \leq \cos x \leq 1 - \frac{x^2}{2!} + \dots + \frac{x^{4n}}{(4n)!}.$$

左边的多项式可以看作是 $\cos x$ 的近似，但有一个缺点；右边的多项式可以看作是 $\cos x$ 的近似，并且具有已知值 (图 6)。但不等式 (3) 的左右多项式之差等于 $\frac{x^{4n+2}}{(4n+2)!}$，并且在 $n \to \infty$ 处根据 (1) 趋于零。这就是为什么

$$\cos x = \lim_{n \to \infty} \left( 1 - \frac{x^2}{2!} + \dots - \frac{x^{4n+2}}{(4n+2)!} \right) = \lim_{n \to \infty} \left( 1 - \frac{x^2}{2!} + \dots + \frac{x^{4n}}{(4n)!} \right).$$

结果写成表格

$$\cos x = 1 - \frac{x^2}{2!} + \dots + \frac{(-1)^n}{(2n)!} x^{2n} + \dots.$$

这个等式的右边称为 $prdom Teйлора функции$ $\cos x$。

当证明不等式 (3) 以及等式 (4) 时，我们假设 $x > 0$。但由于其中包含的所有函数的奇偶性，它们对于 $x < 0$ 也有效。最后，它们可以很容易地验证$x = 0$，因此对于所有真实的$x$都有效。

类似地，对于 (2) 中的$x > 0$，我们有

$$\sin x = \lim_{n \to \infty} \left( x - \frac{x^3}{3!} + \dots - \frac{x^{4n+3}}{(4n+3)!} \right) = \lim_{n \to \infty} \left( x - \frac{x^3}{3!} + \dots + \frac{x^{4n+1}}{(4n+1)!} \right).$$

这个结果写成表格

$$\sin x = x - \frac{x^3}{3!} + \dots + \frac{(-1)^n}{(2n+1)!} x^{2n+1} + \dots,$$

这个等式右边的表达式称为 $prdom Teйлора функции$ $\sin x$。

最后请注意，由于其中包含的所有函数具有奇偶性，等式 (5) 对于 $x \leq 0$ 仍然有效。

函数的泰勒级数展开 $e^x$

已知$(e^x)' = e^x$，由此得出对于任何构造$C$，函数$e^x + C$是$e^x$的反导数。另外，我们知道$e > 1$（$e = 2,718\dots$）也很重要。

由于 $e > 1$，那么 $1 \leq e^t \leq e^a$ 对于所有 $t \in [0; a]$。沿线段 $[0; x]$（其中 $0 \leq x \leq a$）解释这种不等式，我们得到 $x \leq e^x - 1 \leq e^ax$ 或 $1 + x \leq e^x \leq 1 + e^ax$。这些不等式也可以通过首先用$t$替换其中的$x$来在$[0; x]$上积分。结果我们得到

$$x + \frac{x^2}{2!} \leq e^x - 1 \leq x + e^a \frac{x^2}{2!},$$

图 6.

⟦folio 6⟧

伊利

$$1 + x + \frac{x^2}{2!} \leq e^x \leq 1 + x + e^a \frac{x^2}{2!} (0 \leq x \leq a).$$

继续顺序积分的过程，我们得到不等式

$$1 + x + \frac{x^2}{2!} + \dots + \frac{x^n}{n!} \leq e^x \leq 1 + x + \frac{x^2}{2!} + \dots + \frac{x^{n-1}}{(n-1)!} + \frac{x^n}{n!} e^a,$$

其中$n=0, 1, \dots, 0 \leq x \leq a$。

因此，对于来自线段$[0; a]$的每个值$x$，可以以$n$次多项式的形式获得具有不足和过剩的函数$e^x$的近似值。不等式(6)中左右多项式之差等于$(e^a - 1) \frac{x^n}{n!}$；在 $n \to \infty$ 处，根据 (1)，它趋于零。由于 $a$ 是任意正数，因此根据不等式 (6)，对于任意 $x \geq 0$

$$e^x = \lim_{n \to \infty} \left( 1 + x + \frac{x^2}{2!} + \dots + \frac{x^n}{n!} \right).$$

让我们把它写成一个等式

$$e^x = 1 + x + \frac{x^2}{2!} + \frac{x^3}{3!} + \dots + \frac{x^n}{n!} + \dots$$

(7)

(7)式右边的表达式称为函数$e^x$的泰勒级数。

练习 not 1. 证明 $x < 0$ 相等 (7)。 （表示不是。使用 $e^x < 1$ 位于 $x < 0$ 的事实）。

函数 $\ln(1+x)$ 的泰勒级数展开

函数$\ln(1+x)$定义为$\log_e(1+x)$，即对数的底为$e$。由于$\ln(1+x)^\prime = \frac{1}{1+x}$对于所有$x > -1$，那么对于$\frac{1}{1+x}$，函数$\ln(1+x) + C$在区间$-1; +\infty$上是反导数[对于任何构造的$C$。我们将在下面使用它。请注意，对于 $t \geq 0$ 不等式

$$1 - t + \dots + t^{2n-2} - t^{2n-1} \leq \frac{1}{1+t} \leq 1 - t + \dots + t^{2n-2} - t^{2n-1} \leq \frac{1}{1+t} \leq 1 - t + \dots + t^{2n-2} - t^{2n-1} + t^{2n}.$$

(8)

（你自己证明它们的合理性。）

沿线段$[0; x]$解释不等式（8），其中$x \geq 0$，并使用牛顿-莱布尼兹公式，我们得到不等式

$$x - \frac{x^2}{2} + \dots - \frac{x^{2n}}{2n} \leq \ln(1+x) \leq x - \frac{x^2}{2} + \dots - \frac{x^{2n}}{2n} + \frac{x^{2n+1}}{2n+1},$$

(9)

其中$x \geq 0$。左右多项式之差为 $\frac{x^{2n+1}}{2n+1}$。如果$0 \leq x \leq 1$，则在$n \to \infty$处趋于零。这就是为什么

$$\ln(1+x) = x - \frac{x^2}{2} + \dots + \frac{(-1)^{n+1}}{n} x^n + \dots$$

(10)

对于$0 \leq x \leq 1$。

该方程不是 2。确保该等式对于 $-1 < x < 0$ 也成立。 （注意不是。如果$\lambda > \frac{1}{1+t}$，则将其用于$t > -1$$1 - t + \dots + t^{2n-2} - t^{2n-1} \leq \frac{1}{1+t} \leq 1 - t + \dots + t^{2n-2} - t^{2n-1} + t^{2n}$。）

等式（10）右边的表达式称为函数$\ln(1+x)$的泰勒级数。

在求函数$\sin x$、$\cos x, e^x$和$\ln(1+x)$的泰勒级数时，我们使用了各种人工技术。事实上，有一个统一的方法来求函数的泰勒级数——它基于它的序贯微分。我们可以在A.Ya的精彩著作中认识他。 Khinchin“数学分析八讲”（M.，“Nauka”，1977）。

评估结果意味着什么？

上面获得的函数$\sin x$、$\cos x, e^x$和$\ln(1+x)$的估计使我们能够在任意点以任何所需的精度计算它们。

⟦folio 7⟧

例如，如果我们需要找出函数sin x在$x \in \left[ 0; \frac{\pi}{2} \right]$点的值，并且误差不超过数字$\varepsilon > 0$，那么我们首先找到一个整数$n \geqslant 0$使得$x^{4n+1}/(4n+1)! < \varepsilon$。然后，不等式 (2) 在 $x$ 点处的多项式的值给出了 $\varepsilon$ 以内的 sin x 值，一个有劣势，另一个有差异。使用公式计算其他点的值，以将属性简化为线段$\left[ 0; \frac{\pi}{2} \right]$的点处的计算。

一点历史

B. 泰勒的著作《Methodus Incrementorum directa et inversa》于 1715 年在伦敦以拉丁文出版。泰勒是微分和积分的创始人牛顿和莱布尼茨的同时代人。他的方法基于牛顿公式，该公式以 $n$ 次多项式的形式给出给定线段上函数的近似表示，与该线段的 $n+1$ 等距点（包括其端点）处的给定函数一致。泰勒以完全公式化的方式过渡到牛顿公式$n \rightarrow \infty$的前奏，而不用担心如何证明这段过渡到极限。

在此之际，著名的德国科学家和数学史家 F. Klein 写道：“本质上，泰勒在这里用无穷小（微分）进行运算，可以说比莱布尼茨的追随者所做的更轻率；有趣的是，他仍然......在牛顿眼前，如此偏离了后者使用的极限方法”*）。

于是，许多不同国家的数学家都致力于泰勒方法的证实：拉格朗日、柯西、施洛姆希、罗什、皮亚诺等。由于他们的努力，用泰勒级数表示函数的方法和用多项式近似表示函数的方法得到了充分证明。

目前，泰勒级数的概念是数学计算中的主要概念之一。泰勒级数或其有限和用于需要精确或近似表示浮动变化函数的地方。

锻炼
1. 享受平等
$$\text{arctg} x = \int_0^x \frac{dt}{1+t^2} (-\infty < x < \infty),$$

证明对于 $x \geqslant 0$ 和 $n = 0,1, \dots$，以下不等式有效：
$$x - \frac{x^3}{3} + \dots - \frac{x^{4n+3}}{4n+3} \leqslant \text{arctg} x \leqslant x - \frac{x^3}{3} + \dots + \frac{x^{4n+1}}{4n+1}.$$

如果$x < 0$，则在这些不等式中，符号“≤”应替换为“≥”。

2. 证明对于 $-1 < x \leqslant 1$ 相等
$$\text{arctg} x = x - \frac{x^3}{3} + \frac{x^5}{5} - \frac{x^7}{7} + \dots$$

3. 证明相等$\frac{\pi}{4} = 1 - \frac{1}{3} + \frac{1}{5} - \frac{1}{7} + \dots$

4. 证明相等$\ln 2 = 1 - \frac{1}{2} + \frac{1}{3} - \frac{1}{4} + \dots$

5. 证明平等
$$e^{-1} = \frac{1}{2!} - \frac{1}{3!} + \frac{1}{4!} - \dots$$

6. 证明平等
$$(1+x)^{\alpha} = 1 + \alpha x + \frac{\alpha(\alpha-1)}{2!} x^2 + \dots + \frac{\alpha(\alpha-1)}{n!} x^n + \dots,$$
其中$-1 < x \leqslant 1, -\infty < \alpha < +\infty$。
