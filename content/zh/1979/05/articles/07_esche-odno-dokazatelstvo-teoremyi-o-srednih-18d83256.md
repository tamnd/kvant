---
id: 1979-5-esche-odno-dokazatelstvo-teoremyi-o-srednih-18d83256
issue: kvant_1979_5
year: 1979
number: "5"
title: 均值定理的另一个证明
rubric: smes
page_first: 23
page_last: 23
page_labels: "21"
tag: 08ET
lang: zh
source: kvant_digital
extraction: vision
content_sha256: 91663cc5d221bb9e49bd92724c9da3b4df48bf4ad54dfe3b412209cb70d1496c
prompt_sha256: draft-1
translated_from: content/ru/1979/05/articles/07_esche-odno-dokazatelstvo-teoremyi-o-srednih-18d83256.md
source_content_sha256: e28ad6df024b12567e6edcee11cfa9448cb915255c36a16f6524ffaa30a9d13d
translation_model: draft
translation_run: zh-draft-2026-11-01
translation_quality: draft
---

⟦folio 21⟧

由（7）和（8）

$$\Sigma_1 + \dots + \Sigma_c = \left( \frac{S_1}{S_1 - \tilde{s}_1} - 1 \right) + \dots + \left( \frac{S_1}{S_1 - \tilde{s}_c} - 1 \right) = S_1 \left[ \frac{1}{S_1 - \tilde{s}_1} + \dots + \frac{1}{S_1 - \tilde{s}_c} \right] - C \geqslant \frac{C^c \sqrt{H}}{C - C_{n-1}^{k-1}} \cdot \frac{C}{\sqrt{H}} - C = \frac{C^2}{C - C_{n-1}^{k-1}} - C = \frac{kC}{n-k},$$

Q.E.D.

(IV) 中的等式仅适用于 $a_1 = \dots = a_n$。如果不是这样，则并非所有 $\tilde{s}_i$ 都相等，并且已经在 (6) 和 (7) 中出现了符号 >。

另一方面，$\Sigma_1 + \dots + \Sigma_c$可以在角度方向上变大，例如，通过增加$a_1$而不限制数字$a_2, a_3, \dots, a_n$的固定值。

现在让我们对 $\Pi_1 + \dots + \Pi_c$ 和 $\Pi_1 \dots \Pi_c$ 值变化的画布进行估计。 $k \neq n/2$ 处的第一个值取任何正值。对于$k = n/2$（n为偶数），它的最小值等于$C = C_k^n$，在$a_1 = \dots = a_n$达到，并且仍然不受上面的限制。 $k \neq n/2$ 处的第二个值也可以取任何正值，而在 $k = n/2$（n 为偶数）处，该值始终等于 1。

便宜的盒子

盒子的两个壁为长方体，体积为1立方米，由一种材料制成，而其他壁则由成本低8倍的材料制成。 $x, y, z$ 盒子的尺寸是多少，其制造所需的材料成本最低？

解决方案e.令 1 平方米第二种材料的成本等于 $p$ 卢布。根据条件，从第一个材料开始，它们是相邻的，或者是不相邻的。在第一种情况下，材料成本等于

$$S_1 = 8p(xy + yz) + p(xy + yz + 2xz) = p \cdot xyz \left( \frac{9}{z} + \frac{9}{x} + \frac{2}{y} \right) = p \left( \frac{9}{z} + \frac{9}{x} + \frac{2}{y} \right),$$

在第二个 -

$$S_2 = 8p2xy + p(2xz + 2yz) = 2pxyz \left( \frac{8}{z} + \frac{1}{y} + \frac{1}{x} \right) = 2p \left( \frac{8}{z} + \frac{1}{y} + \frac{1}{x} \right).$$

让我们应用一下不等式

$$\frac{a + b + c}{3} \geqslant \sqrt{abc}$$

这些表达式的算术平均值和几何平均值（参见第 18 页）之间。我们得到

$$S_1 \geqslant 9 \sqrt[3]{6} p \text{ и } S_2 \geqslant 12p.$$

很容易看出$9 \sqrt[3]{6} p > 12p$。当且仅当最小值是满足最后一个条件的$\frac{8}{z} + \frac{1}{y} + \frac{1}{x}$之和时，$S_2$的成本才最小，当且仅当$\frac{8}{z} + \frac{1}{y} + \frac{1}{x} = \frac{1}{x}$满足最后一个条件时。

为此，$8/z = 1/y = 1/x$是必要且充分的。

从$xyz = 1$开始，得出$x = y = 0,5; z = 4$。

因此，第一材料的壁必须是不相邻的并且具有边长为0.5m的正方形形状，并且它们之间的距离为4m。

R·维诺库尔

均值定理的另一个证明

两个正数的算术平均值和几何平均值之间的不等式是一个非常重要的数学关系。我们的课程已经不止一次发布了有关该主题的材料。 图1表示边长为0.5m的正方形，边长为4m。

$$|CD| = \sqrt{|AD| \cdot |DB|},$$
$$|OC| = \sqrt{|AD| + |DB|}$$
