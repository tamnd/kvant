---
id: 1990-6-tabachnikov-mnogochlenyi-naimenee-uklonyayuschiesya-ot-nulya-637c077e
issue: kvant_1990_6
year: 1990
number: "6"
title: 偏离零最小的多项式
authors:
  - Табачников С. Л.
rubric: osnovnye-stati
page_first: 25
page_last: 26
page_labels: 23-24
lang: zh
source: kvant_digital
extraction: vision
content_sha256: 83ddb1adcb6e7932537e99e80031dec24bf99b49bdda9adc94c83f5bf860709b
prompt_sha256: draft-1
translated_from: content/ru/1990/06/articles/04_tabachnikov-mnogochlenyi-naimenee-uklonyayuschiesya-ot-nulya-637c077e.md
source_content_sha256: 66530a17b2f0abecdbe2c5cfca401e9fd2fa866d9b9895e016852f4565773ced
translation_model: draft
translation_run: zh-draft-2026-11-06
translation_quality: draft
---

⟦folio 23⟧

---
running_head:
folio:
---

多项式，最少
从零开始

物理和数学科学候选人
塔瓦奇尼科夫

我将讨论关于多项式的最美丽的问题之一 - 关于偏离零最少的多项式的切比雪夫问题。让我们修复数轴的某个段，例如段 [−2; 2]（当我说“让我们说”时，我有点撒谎 - 正是针对这一部分，获得了最简单的公式）。让

$$f(x) = x^n + a_1 x^{n-1} + a_2 x^{n-2} + \dots + a_n$$

是$n$次的简化多项式（这意味着它的首项系数为1）。区间 [−2; 上的值集合$f(x)$； 2]——线段[m； M]，其中 $m$ 是多项式的最小值，$M$ 是多项式的最大值。多项式与零的偏差称为最计算|m|，|M|。如果多项式与零的偏差为 $c$，则其图形包含在域 |y| 中≤ $c$ 并且不包含在任何具有中线 Ox 的较窄带中。

任务是找到这样一个$n$次$f_n(x)$的约化多项式，其与零的偏差最小（首项系数等于1的条件不允许我们制作靠近横坐标的任意图）。乍一看，爱好者们对切比雪夫问题没什么兴趣：为了寻找与零的偏差，你需要计算任意方程并求解$n$次方程……更令人惊讶的是，这个问题是用几何方法解决的——而且几乎不需要计算！

让我们首先，在没有弓箭智慧的情况下，检查一下小度数的情况。在 $n=1$ 时，熔炉只是 $f(x)=x+a$ 的线性函数。它的值集是线段[−2+a; 2+a]，长度为 4。因此，与零的最小偏差为 2，$f_1(x)=x$。

对于 Nenatny 来说，情况 $n=2$（二次三项式的情况）更加困难。二次多项式的图形是一段抛物线；抛物线最有利的位置如 图 1 所示。在这种情况下，$f(x)=x^2-2$，并且与零的偏差再次等于 2。

练习 1. 检查计算的直观性：证明三项式平方与零的偏差不小于 2。

我可以建议您检查三次多项式的情况，并确保在这种情况下与零的偏差等于 2。这个问题仍然允许一个简单的解决方案。但我迫不及待地想告诉你一般的解决方案。

让我们假设我们已经成功地发现了第 $n$ 次$f_n(x)$ 的简化多项式，使得它的图位于条带 |y| 中。 ≤ $c$ 并包含 $n+1$ 其边界点：最右边的一个位于$y=c$线上，下一个位于$y=-c$线上，下一个又位于$y=c$线上，依此类推（$n=5$位于图2上）。

定理。除 $f_n(x)$ 之外的任何$n$次约化多项式与零的偏差均大于$c$。

这是使切比雪夫问题成为柱状问题的几何证明。让 $g(x)$ —

⟦folio 24⟧

---
running_head:
folio:
---

另一个$n$次的降多项式，其与零的偏差不超过$c$。那么它的图也位于带 $|y| \leq c$ 内。将这条垂直线段分成 $n$ 矩形，如 图 3 所示。蓝色曲线 - 图 $f_n(x)$ - 对角连接每个矩形的相对顶点。因此，红色曲线 - 图 $g(x)$ - 与它们各自内部的蓝色曲线相交。因此，方程$f_n(x) - g(x) = 0$至少有$n$根。但多项式$f_n(x) - g(x)$的次数不大于$(n-1)$。如果这样的多项式仍有$n$根，那么它自然也等于零，即$g(x) = f_n(x)$。定理已被证明。

考虑这个证明。几乎不劳而获，我们得到了很多：虽然我们还不知道 $c$ 的值，但我们已经知道给定次数的多项式只有一个偏离零最少的多项式，并且我们可以想象它的图形是什么样的。

练习2. 上面的证明包含一个缺口（这就是美丽的代价）。如果多项式 $f_n(x)$ 和 $g(x)$ 的图形接触 (图 4) 会怎样？

提示：记住多项式多重根的定义。

因此，我们需要给出一个多项式$f_n(x)$，其图形如图2所示。这个图不禁让你想起三角函数。事实上，现在它们开始发挥作用了！

最简单的方法就是将 cos 函数 $n\alpha$ 视为 $f_n$。但是，可惜：余弦不是多项式。下面的一个来拯救你。

引理。函数 2 cos $n\alpha$ 在函数 2 cos $\alpha$ 中表示为 $n$ 次约化多项式：

$$2 \cos n\alpha = f_n(2 \cos \alpha).$$

例如，

$$2 \cos 2\alpha = 4 \cos^2\alpha - 2 = (2 \cos \alpha)^2 - 2,$$

即 $f_2(x) = x^2 - 2$；

$$2 \cos 3\alpha = 8 \cos^3\alpha - 6 \cos \alpha = (2 \cos \alpha)^3 - 3(2 \cos \alpha),$$

即 $f_3(x) = x^3 - 3x.$

引理的证明是通过归纳法进行的。让她的陈述用数字$n-1$和$n$来证明：

$$2 \cos(n-1)\alpha = f_{n-1}(2 \cos \alpha),$$

$$2 \cos n\alpha = f_n(2 \cos \alpha).$$

由公式可知

$$\cos(n+1)\alpha + \cos(n-1)\alpha = 2 \cos \alpha \cos n\alpha$$

由此可见

$$2 \cos(n+1)\alpha = (2 \cos \alpha)(2 \cos n\alpha) - 2 \cos(n-1)\alpha = (2 \cos \alpha)f_n(2 \cos \alpha) - f_{n-1}(2 \cos \alpha).$$

方法，

$$f_{n+1}(x) = xf_n(x) - f_{n-1}(x).$$

证明了引理，同时得到了计算多项式$f_n(x)$的递归公式。

（结局见第27页）。
