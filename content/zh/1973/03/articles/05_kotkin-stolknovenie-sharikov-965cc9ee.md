---
id: 1973-3-kotkin-stolknovenie-sharikov-965cc9ee
issue: kvant_1973_3
year: 1973
number: "3"
title: 球碰撞
authors:
  - Коткин Г. Л.
rubric: osnovnye-stati
page_first: 22
page_last: 22
page_labels: "20"
tag: CLMD
lang: zh
source: kvant_digital
extraction: vision
content_sha256: c719b1eee0218053245f1e2566e8be7a95a66ff4673b187cfcbb35a6a0f9349d
prompt_sha256: draft-1
translated_from: content/ru/1973/03/articles/05_kotkin-stolknovenie-sharikov-965cc9ee.md
source_content_sha256: 37405c1d095a61bf59db639b6af3bc387013bb8bb693ae0203e5c4065fc6c966
translation_model: draft
translation_run: zh-draft-2026-10-31
translation_quality: draft
---

⟦folio 20⟧

在球停止的那一刻，动能总是转化为潜在的形变能。变形势能等于弹力在路径 $x$ 上所做的功：

$$U \sim Fx \sim ER^{\frac{1}{2}}x^{\frac{5}{2}}.$$

这意味着$\frac{1}{2}mv^2 = U \sim ER^{\frac{1}{2}}x^{\frac{5}{2}}$。但球的质量是$m = \frac{4}{3}\pi R^3\rho$。因此，

$$\frac{1}{2}mv^2 = \frac{2\pi}{3}R^3\rho v^2 \sim R^3\rho v^2.$$

因此，

$$R^3\rho v^2 \sim ER^{\frac{1}{2}}x^{\frac{5}{2}},$$

在哪里

$$x \sim R \frac{\rho \frac{2}{5}v^{\frac{4}{5}}}{E^{\frac{2}{5}}} = R \left(\frac{\rho v^2}{E}\right)^{\frac{2}{5}}.$$

方便地先表示$\frac{E}{\rho} = u^2$)，然后表示$x \sim R\left(\frac{v}{u}\right)^{\frac{4}{5}}$。我们将求得的值$x$代入公式（2）：

$$F \sim ER^2\left(\frac{v}{u}\right)^{\frac{6}{5}}.$$

让我们估计一下球的碰撞时间：

$$t \sim \frac{x}{v} \sim \frac{R}{u}\left(\frac{u}{v}\right)^{\frac{1}{5}}$$

(4)

*) 以这种方式引入的数量与球体中的声速一致。例如，对于钢$E = 2;1.10^{11}h/m^2$、$\rho = 7,8.10^3\kappa_2/m^3$、$u = 5,2.10^3m/c$，钢中的声速约为$6.10^3m/c$。

**) 更准确但更复杂的计算给出 $t$ 的值大约是其两倍，而 $F$ 的值稍小一些。

让两个半径为$R = 1cm$的钢球以$v = 5cm/c$的速度碰撞（这样的钢球的质量约为30$e$）。利用公式（4）和（3）我们得到

$$t \sim \frac{10^{-2}}{5 \cdot 10^{-3}}\left(\frac{5 \cdot 10^3}{5 \cdot 10^{-2}}\right)^{\frac{1}{5}}c \sim 2 \cdot 10^{-5}c,$$

$$F \sim 2 \cdot 10^{11} \cdot 10^{-4}\left(\frac{5 \cdot 10^{-2}}{5 \cdot 10^{-3}}\right)^{\frac{6}{5}}n \sim 20n.$$

请注意，球的速度越高，其辅助时间越短。

还有另一种方法来估计判断的时间。按照弹簧的类比，我们假设球的撞击时间对应于质量$m$的球在刚度弹簧$k \sim Er$上的振荡半周期，即

$$t \sim \frac{T}{2} = \pi \sqrt{\frac{m}{k}},$$

(5)

半周期越小，刚性越大*)。

如果球速太高，我们的估计就不适用。在这种情况下，变形太大，胡克定律不再适用。对于钢，胡克定律在相对应变 $\frac{\Delta l}{l} \leq 10^{-2}$ 时有效。从这个条件我们可以确定球的最大碰撞速度。球的最大变形（“弹簧”）

$$\frac{\Delta l}{l} \sim \frac{x}{r} \sim \left(\frac{v}{u}\right)^{\frac{2}{5}} \leq 10^{-2},$$

在哪里

$$v \leq 10^{-5}u \sim 5 \cdot 10^{-2}m/c = 5cm/c.$$

当两个长度为$l$、半径为$R$的相同圆柱体在两端碰撞时，可以对相互作用的时间和力进行类似的评估。在这种情况下，相对较大变形的区域延伸到每个圆柱体的体积。
