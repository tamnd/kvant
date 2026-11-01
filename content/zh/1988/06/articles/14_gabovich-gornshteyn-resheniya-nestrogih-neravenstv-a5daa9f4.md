---
id: 1988-6-gabovich-gornshteyn-resheniya-nestrogih-neravenstv-a5daa9f4
issue: kvant_1988_6
year: 1988
number: "6"
title: 非严格不等式的解
authors:
  - Габович И. Г.
  - Горнштейн П. И.
rubric: praktikum-abiturienta
rubric_sub: Практикум абитуриента
page_first: 61
page_last: 62
page_labels: 59-60
tag: GJ84
lang: zh
source: kvant_digital
extraction: vision
content_sha256: c1b1fc4d97f0a429810c9558a8030f978580aaae9e34416bc4b2cc6e36748d0e
prompt_sha256: draft-1
translated_from: content/ru/1988/06/articles/14_gabovich-gornshteyn-resheniya-nestrogih-neravenstv-a5daa9f4.md
source_content_sha256: b08eb8c8d10ab037d97aebbe74ed05f37e85fdb9e92807f70146f3e46fb3c197
translation_model: draft
translation_run: zh-draft-2026-11-01
translation_quality: draft
---

⟦folio 59⟧

非严格不等式的解

I. G. 加博维奇、P. I. 戈恩斯坦

本文将讨论非严格不等式$f(x) \geq 0$的解，或者更确切地说，这个解与相应的非严格不等式$f(x) > 0$的解有多大不同。

从大多数角度来看，情况很简单：不等式$f(x) > 0$的解是几个有限或无限区间*的并集，而为了获得不等式$f(x) \geq 0$的解，需要将它们的末端添加到这些区间中。

在某些情况下，此规则会给出正确的结果。例如，这会发生在线性不等式的情况下：

*) 严格来说，如果 $f(x)$ 是在所有行或某个区间并集上定义的连续函数，则这是正确的。

求解非严格不等式
$ax + b > 0$

集合$(-b/a; \infty)$出现，非严格不等式的解
$ax + b \geq 0$

是集合$[ -b/a; \infty)$，通过添加间隔$-b/a$的末尾而从前一个集合中获得。但在二次不等式的情况下，我们的规则就出现了缺陷。最简单的例子：解决不等式
$-x^2 > 0$

将会有一个空集，并且不等式的解
$-x^2 \geq 0$

并不是像人们想象的那样是一个空集，而是一个由一个点 $x = 0$ 组成的集合。否则，只有当不等式左边的平方三项式的判别式等于 0 时才是这种情况；例如，如果二次三项式 $ax^2 + bx + c$ 有两次

⟦folio 60⟧

个人根$x_1$和$x_2$（$x_1 < x_2$）和$a > 0$，然后解不等式
$$ax^2 + bx + c > 0$$
将会发生不统一$(-\infty; x_1) \cup (x_2; \infty)$，并且解决不平等问题
$$ax^2 + bx + c \geq 0$$
— 统一$(-\infty; x_1] \cup [x_2; \infty)$。

怎么了？如果函数$y = f(x)$的图形位于$Ox$轴上的点处，函数$f(x)$改变符号，即它的图形从轴$Ox$的一侧经过到另一侧，则上面制定的“规则”是正确的；例如，对于函数$f(x)$，其图形如图 1所示，不等式$f(x) > 0$的解是解离$(a; b) \cup (c; d)$，不等式$f(x) \geq 0$的解是解离$[a, b] \cup [c, d]$。对于图图 2所示的函数，不等式$f(x) > 0$有解$(a, b)$，不等式$f(x) \geq 0$有解$[a, b] \cup \{c\}$！又如：函数$y = f(x)$定义在$x \geq a$，其图形如图3所示。那么不等式$f(x) > 0$有解$(b, c)$，不等式$f(x) \geq 0$有解$\{a\} \cup [b, c]$！

如果$A$是区间的并集，则从$A$将区间末端添加到集合$A$得到的集合称为集合$A$的闭包，记为$\bar{A}$。上式可以给出以下形式：如果$A$是不等式$f(x) > 0$的解，而$B$是不等式$f(x) \geq 0$的解，则$B$包含$\bar{A}$，但可能与其不重合。

严格知道不等式$f(x) > 0$的解，如何求解自然不等式$f(x) \geq 0$？

非常简单：您需要将方程 $f(x) = 0$ 的所有解添加到严格不等式 $f(x) > 0$ 的解中。

对于这个非常重要的评论，我们将添加一个非常重要的评论，这在实践中可能有用：不等式 $f(x)g(x) \geq 0$ 的解是不等式系统解的并集
$$\begin{cases} f(x) \geq 0, \\ g(x) \geq 0; \end{cases}$$

（对于不平等$f(x)g(x) \leq 0$也是如此。）现在让我们看几个例子（其中一些来自不同年份的竞争性考试）。

示例 1. 解决不等式
$$\sqrt{-25x^2+15x-2}(8x^2-6x+1) \geq 0.$$

让我们解决四个不等式：
$$\sqrt{-25x^2+15x-2} \geq 0;$$
解：$\frac{1}{5} \leq x \leq \frac{2}{5}$。
$$\sqrt{-25x^2+15x-2} \leq 0;$$
解：$x = \frac{1}{5}$和$x = \frac{2}{5}$。
$$8x^2-6x+1 \geq 0;$$
解：$x \leq \frac{1}{4}$和$x \geq \frac{1}{2}$。
$$8x^2-6x+1 \leq 0;$$
解：$\frac{1}{4} \leq x \leq \frac{1}{2}$。

将找到的四个对应集合用$A, B, C, D$表示后，我们可以说原不等式的解就是集合$(A \cap C) \cup (B \cap D)$。执行完上述操作后，我们得到

答案：$$\left[ \frac{1}{5}; \frac{1}{4} \right] \cup \left\{ \frac{2}{5} \right\}.$$

示例 2：解决不等式
$$\sqrt{x^2-7,5x+14}\log_2|x-3| \leq 0.$$

（结局见第66页）
