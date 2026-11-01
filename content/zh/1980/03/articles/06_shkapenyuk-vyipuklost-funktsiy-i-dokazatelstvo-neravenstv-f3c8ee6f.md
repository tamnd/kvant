---
id: 1980-3-shkapenyuk-vyipuklost-funktsiy-i-dokazatelstvo-neravenstv-f3c8ee6f
issue: kvant_1980_3
year: 1980
number: "3"
title: 函数的凸性和不等式的证明
authors:
  - Шкапенюк М. Б.
rubric: matematicheskiy-kruzhok
rubric_sub: Математический кружок
page_first: 23
page_last: 24
page_labels: 21-22
tag: 4XE9
lang: zh
source: kvant_digital
extraction: vision
content_sha256: 80374cba85cecacfba1a383bbdde4077f6ff5b66b803c424c67c74b44eb69425
prompt_sha256: draft-1
translated_from: content/ru/1980/03/articles/06_shkapenyuk-vyipuklost-funktsiy-i-dokazatelstvo-neravenstv-f3c8ee6f.md
source_content_sha256: b2f3fe1b0085b17fa3967de220a0beaf491f94b73dc1e6817256652c388b346c
translation_model: draft
translation_run: zh-draft-2026-11-01
translation_quality: draft
---

⟦folio 21⟧

M·什卡佩纽克

凸面
功能
和证明
不平等现象

本文探讨凸函数的性质。具体地，凸函数在n个点处的算术平均值与其在这些点处的算术平均值处的值之间成立不等式。从这个不等式很容易得到调和平均数、几何平均数、算术平均数和二次平均数之间的经典关系。

凸函数
让我们考虑函数$f$，在线段$[a; b]$的任意点微分，并用$\Gamma$表示函数$f$对应于该线段的图形部分：

$$\Gamma = \{(x; y) | x \in [a; b] \text{ и } y = f(x)\}.$$

如果对于任意点 $T \in \Gamma$，曲线 $\Gamma$ 位于点 $T$ (图 1 a) 处$\Gamma$ 的切线下方，则函数 $f$ 被称为线段 $[a; b]$ 上的上凸（“代数与分析原理 10”，第 79 页）。分析起来，很容易看出（图2），这个条件写成不等式的形式

$$f(x_2) < f(x_1) + f'(x_1)(x_2 - x_1),$$

对于任何（不同的）$x_1, x_2 \in [a; b]$ 都必须成立。线段 (图 1, b) 上的下凸度以类似的方式确定；为此，不等式(1)中的符号<必须用>代替。

在教科书的同一段落中，它对于任何函数都得到了充分的表述：如果在区间上第二个任意为正（负），则该图是向下（向上）凸的。在第一种情况下，几何钝角是加速增加或缓慢减少，在第二种情况下，几何是缓慢减少或加速减少。

示例 1) 函数 $f(x) = x^2$ 在任意线段 $[a; b]$ 上都是向下凸的。 2) 如果$0 < a < b$，则函数$f(x) = \lg x$向上凸$[a; b]$。 3) 函数$f(x) = \sin x$向上凸$[0; \pi]$和向下凸$[\pi; 2\pi]$。

现在让我们考虑凸函数的几个简单性质；我们针对上凸函数的情况制定它们，让读者针对下凸函数重新制定它们。

I. 如果 $f$ 向上凸$[a; b]$，则对于任意（不同）点

$$f\left(\frac{1}{2}(x_1 + x_2)\right) > \frac{1}{2}(f(x_1) + f(x_2)).$$

图 1 a

图 1 6

⟦folio 22⟧

证明是显而易见的：检查函数图在点 $\frac{1}{2}(x_1+x_2) \in [a; b]$ 处的切线并注意线段 $|AB|$ 的长度等于 $\frac{1}{2}(f(x_1)+f(x_2))$ (图 3) 就足够了。

可以证明，在区间 $[a; b]$ 上可微且具有属性 I 的函数将是上凸的。这个事实不是必需的，因此我们不提供证明。

二.如果函数$f(x)$、$g(x)$在$[a; b]$上凸，那么它们的和$h(x)=f(x)+g(x)$也在$[a; b]$上凸。

事实上，为 $f$ 和 $g$ 添加不等式 (1) 并利用 $h'(x)=f'(x)+g'(x)$ 这一事实，我们立即获得函数 $h$ 的不等式 (1)。

三．如果函数$f(x)$在$[a; b]$上向上凸，则函数$h(x)=-f(x)$在$[a; b]$上向下凸。

这直接来自函数凸性的定义。以下属性紧随属性 II 和 III 得出：

四．如果函数$f(x)$在$[a; b]$上向上凸，并且函数$g(x)$在该线段上向下凸，则函数$h(x)=f(x)-g(x)$在该线段上向上凸。

这就是所承诺的基本不平等。

定理。如果函数在 $[a; b]$ 上凸且数 $x_1, x_2, \dots, x_n \in [a; b]$ ($n \geqslant 2$) 不全部相等，则

$$f\left(\frac{1}{n}(x_1+\dots+x_n)\right) > \frac{1}{n}[f(x_1)+\dots+f(x_n)].$$

这个定理是不等式的取之不尽用之不竭的来源：将任何凸向上具体函数与 (*) 中的函数 $f$ 一起替换就足够了……不等式就完成了！例如，将 $f$ 函数 sin 结合在一起，我们得出对于任何（不同的）$x_1, \dots, x_n \in [0; \pi]$，以下不等式成立：

$$\sin\left(\frac{1}{n}(x_1+\dots+x_n)\right) > \frac{1}{n}(\sin x_1+\dots+\sin x_n).$$

我们将在文章结束之前关闭定理的证明，但现在让我们看看结果如何。

古典不平等

让我们回顾一下数学中经常出现的几个定义，它们在数学应用中发挥着重要作用（概率论、数理统计等）。

调和平均正数 $x_1, x_2, \dots, x_n$ 是数

$$P_{-1} = \left(\frac{1}{n}(x_1^{-1}+x_2^{-1}+\dots+x_n^{-1})\right)^{-1} = n/(x_1^{-1}+x_2^{-1}+\dots+x_n^{-1}).$$

几何平均正数$x_1, x_2, \dots, x_n$是数

$$P_0 = \sqrt{x_1 \cdot x_2 \cdot \dots \cdot x_n},$$
