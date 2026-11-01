---
id: 1986-2-v-reshenie-stereometricheskoy-zadachi-a4db58fc
issue: kvant_1986_2
year: 1986
number: "2"
title: '[解决立体测量问题]'
authors:
  - Дубровский В. Н.
rubric: raznoe
rubric_sub: Разное
page_first: 29
page_last: 29
page_labels: "27"
tag: N6CH
lang: zh
source: kvant_digital
extraction: vision
content_sha256: a356b864a58272a68331e577219c1a18c1db5ea7797382de43f954821eb5852b
prompt_sha256: draft-1
translated_from: content/ru/1986/02/articles/09_v-reshenie-stereometricheskoy-zadachi-a4db58fc.md
source_content_sha256: 1c79a90cbc77f473099a4e0a07167b64cc1495de669dd19124484d752c1cf7be
translation_model: draft
translation_run: zh-draft-2026-11-01
translation_quality: draft
---

⟦folio 27⟧

这是一个例子：
$$] - \infty; 0 [ \cup \{ 4 \}.$$
使用相同的方案解决了注释开头给出的第一个问题。

我们再次写出等效系统：
$$\begin{cases} 8x - 6p - 3 > 0, \\ \frac{x^2 + 2px}{8x - 6p - 3} = 1 \end{cases}$$
（显然，如果满足这些条件，则不等式$x^2 + 2px > 0$也满足），即
$$\begin{cases} 8x - 6p - 3 > 0, \\ x^2 + 2x(p - 4) + 6p + 3 = 0. \end{cases}$$
同样可能有两种情况：
第一个案例。二次方程有一个根，即方程的判别式为零。我们来写一下这个条件：
$$p^2 - 14p + 13 = 0,$$
从那里$p = 1$和$p = 13$。
对于$p = 1$，我们得到$x = 3$；有了$p = 13$我们就得到$x = -9$。将找到的值$x$和$p$代入不等式$8x - 6p - 3 > 0$，我们确信值$p = 13$、$x = -9$不合适。相反，值$p = 1$、$x = 3$满足这个不等式。因此，$p = 1$处的原始方程有一个单根$x = 3$*)。

第二个案例。二次方程有两个根，较大的根落入 ODZ，较小的根则不落入 ODZ。

不等式$8x - 6p - 3 > 0$意味着$x > \frac{6p - 3}{8}$，所以如果$x_1$和$x_2$（$x_1 < x_2$）是二次方程$x^2 + 2x(p - 4) + 6p + 3 = 0$的根，那么它一定是$x_2 > \frac{6p + 3}{8}$和$x_1 \leqslant \frac{6p + 3}{8}$。再次，如示例$\frac{\lg px}{\lg(x + 1)} = 2$（参见图 2）所示，当且仅当函数$f(x) = x^2 + 2x(p - 4) + 6p + 3$存在$f\left(\frac{6p + 3}{8}\right) \leqslant 0$时，所有条件都会得到满足。写出这个条件$\left(\frac{6p + 3}{8}\right)^2 + 2 \cdot \frac{6p + 3}{8}(p - 4) + 6p + 3 \leqslant 0$，变换后我们得到$(6p + 3)(22p + 3) \leqslant 0$，由此得到$-\frac{1}{2} \leqslant p \leqslant -\frac{3}{22}$。

所以，这个问题的答案是：
$$\left[ -\frac{1}{2}; -\frac{3}{22} \right] \cup \{1\}.$$
I·G·加博维奇
P·I·戈尔施泰因

*) 这个答案在上面的问题集中给出。

我们的封面

显然，立体测量问题始于我们一般性地再现其中考虑的配置这一事实。在上一期封面的问题中，最简单的方法是在解决问题时直接呈现配置。下一篇中的大内容（如封面所示）实际上不会被我们发现。

该解决方案基于以下有用的陈述：半径为 $R_1$ 和 $R_2$ 的两个圆在外部相互接触，当且仅当它们在接触点之间的公共外切线的线段等于 $2\sqrt{R_1R_2}$ (图 1)。从图 1 可以很方便地证明这个命题。将这个命题中的圆视为两个球到通过其中心的平面的截面，或者作为一个球和一个狭缝到通过球中心垂直于滑道轴线的平面的截面，我们得到了球或圆柱体外相切的条件；例如，在后一种情况下，需要从球与平面的接触点到圆柱体沿直线的距离

$AB^2 = O_2C^2 = (R_1 + R_2)^2 - (R_1 - R_2)^2$

图 1.
