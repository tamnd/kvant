---
id: 1971-5-bashmakov-o-postulate-bertrana-85b0ebf2
issue: kvant_1971_5
year: 1971
number: "5"
title: 关于伯特兰公设
authors:
  - Башмаков М. И.
rubric: osnovnye-stati
page_first: 6
page_last: 6
page_labels: "4"
tag: XJWU
lang: zh
source: kvant_digital
extraction: vision
content_sha256: 84a4ed22eef9eb7e112b39f2300807c7d524d2854a51efcce91c41cb21715704
prompt_sha256: draft-1
translated_from: content/ru/1971/05/articles/02_bashmakov-o-postulate-bertrana-85b0ebf2.md
source_content_sha256: 68a02acb2c654cbb5c9ea9c1e34b11e9f645d18e52f783af48e6f490f8dcdf96
translation_model: draft
translation_run: zh-draft-2026-10-31
translation_quality: draft
---

⟦folio 4⟧

关于伯特兰公设

M·I·巴什马科夫

在帕夫努蒂·利沃维奇·切比雪夫的 69 部著作中，有两部著作对数论的发展起到了特别重要的作用。他年轻时写的《论确定不超过给定值的素数的个数》和《论素数》等著作，都涉及到数论中最难的问题：素数的分布。

在第二部作品中，指出了不等式，使得相当准确地估计自然级数给定段中素数的数量成为可能，特别是证明了以下事实：在$x$和$2x$（其中$x>1$）之间总是至少有一个素数。这个说法是由法国著名数学家贝特朗提出的，他在现有的素数表中测试了它，但无法证明它并接受它作为一个构造。

我们将追溯切比雪夫导致他做出这些估计的主要思想，然后提出一系列问题，其解决方案使读者（足够熟悉对数的性质）能够重建乌卡济夫对伯特兰构造的证明，并获得不超过给定值的素数数量的不等式。

读者可能想知道对数与素数有什么关系？这就是切比雪夫的优点，他指出了如何在研究整数问题时使用分析的一般函数——根、对数。如果我们想找出$n$到$2n$区间上是否至少存在一个素数，那么我们可以这样进行：

1) 提出实参$x$的某个函数$y=f(x)$，当$x$穿过相邻素数之间的线段时，它的值不会改变，并且在穿过素数时会取更大的值；

2) 证明相对函数$f$的不等式，这将有助于相当准确地估计增长率。

对于以这种方式选择的函数，当且仅当函数从$n$移动到$2n$时返回$f$时，即$n$和$2n$之间至少有一个素数，差值$f(2n) - f(n)$才是正数。

第一个条件很容易满足。我们可以考虑以下函数：让我们用$\pi(x)$表示不超过$x$的素数数量。

例如，$\pi(1) = 0$（1不被视为质数）、$\pi(3) = 2$、$\pi(9) = 4$、$\pi(9,5) = 4$、$\pi(10,9) = 4$、$\pi(11) = 5$等。

当然，如果我们能证明

$$\pi(2x) - \pi(x) > 0,$$

我们会证明伯特兰会采取行动，因为

$$\pi(2x) - \pi(x)$$

只表示$x$和$2x$之间包含的素数个数。
