---
id: 1971-11-ogievetskiy-pole-tyazhesti-sfericheski-odnorodnogo-tela-5ecc9d80
issue: kvant_1971_11
year: 1971
number: "11"
title: 球状均匀体的重力场
authors:
  - Огиевецкий И. И.
rubric: osnovnye-stati
page_first: 18
page_last: 20
page_labels: 16, 18
tag: 0LZZ
lang: zh
source: kvant_digital
extraction: vision
content_sha256: 1182437b4d819a740c8108000bc5710c6b6e8785ba07deb45f98ed8a58338877
prompt_sha256: draft-1
translated_from: content/ru/1971/11/articles/03_ogievetskiy-pole-tyazhesti-sfericheski-odnorodnogo-tela-5ecc9d80.md
source_content_sha256: fa795d4483ed120f6629225d0cb24f2e5a7d50ae77bfab5a544b0a75da851121
translation_model: draft
translation_run: zh-draft-2026-10-31
translation_quality: draft
---

⟦folio 16⟧

均匀球体的柔软度场

奥吉维茨基

牛顿万有引力定律同样决定了苹果落地的情况、月球绕地球的运动以及行星的轨道。它基于以下事实：质量为 $m_1$ 和 $m_2$ 且彼此距离为 $l$ 的质点之间的张力等于

$$F = \gamma \frac{m_1 m_2}{l^2},$$

(1)

其中 $\gamma = 6,67 \cdot 10^{-11} \frac{H \cdot m^2}{\kappa^2}$ 是引力常数（在 SI 系统中）。但地球、月球和其他实体并不精确，它们的尺寸是有限的。如何确定绞合体之间的拉力？

这个问题的解决导致牛顿创建了数学最重要的分支——积分。要找到材料点对共轭体的收缩力，您应该在心里将该物体划分为小的（极限 - 无穷小）部分，使用公式（1）计算每个部分对收缩力的贡献，然后添加（解释）这些贡献。天体可以近似地被认为是球形均匀的，也就是说，在任何给定点，它们的密度完全由该点到天体中心的距离决定。牛顿发现了一个值得注意的事实：

$$F = \gamma \frac{4\pi R^2 \rho m}{d^2} = \gamma \frac{M \cdot m}{d^2},$$

(2)

其中 $M$ 是表面质量。换句话说，球面外部的拉力与球面的整个质量集中在其中心相同。这立即意味着球形均质体的类似陈述。

*) 这个属性经常被认为非常重要，但没有证明。在一些文章中使用它«Kvant»。因此，了解它是如何证明的非常有用。

⟦folio 18⟧

图 3.

现在让我们使用反转并根据（4）将（6）中的$l$替换为$\bar{l} \frac{d}{R}$：

$$\Delta F_{OQ} = \gamma \frac{m\rho R^2 \cos \alpha \Delta S}{d^2 \bar{l}^2} =$$
$$= \gamma \frac{m\rho R^2 \Delta \omega}{d^2},$$

(7)

输入值的位置
$$\Delta \omega = \frac{\cos \alpha \Delta S}{\bar{l}^2}.$$

让我们做一个重要的观察。请注意，$\alpha$ 也是表面元素 $\Delta S$ 的法线（半径 $OP$）与方向 $\bar{Q}P^*$ 之间的角度，并且为任意点 $P$ 设置 cosa。

因此，很容易验证$\Delta \omega$是从点$\bar{Q}$可见表面元素$\Delta S$的立体角。

如果引入一个顶点位于点 $\bar{Q}$ 的圆锥体并形成连续轮廓 $\Delta S$，则该圆锥体顶点处的立体角将为 $\Delta \omega$ (图 3)。

从数值上来说，角度$\Delta \omega$等于该圆锥体从以点$\bar{Q}$为中心的单位半径球体切出的面积。

*) 这是反转操作必不可少的地方。在它的帮助下，我们将距离$\bar{l}$引入分母（6）而不是距离$l$，因此立体角$\Delta \omega$出现在公式中。

完全接受所有表面$\Delta S$：

$$F = \sum_{s} \Delta F_{OQ} = \gamma \frac{m\rho R^2}{d^2} \sum_{s} \Delta \omega =$$
$$= \gamma \frac{m\rho 4\pi R^2}{d^2} = \gamma \frac{mM}{d^2},$$

(8)

因为$\sum_{s} \Delta \omega = 4\pi$是从内点$\bar{Q}$可见整个球体的总立体角，$4\pi R^2\rho = M$是球面的总质量。至此，命题1得证。

现在让我们考虑空心球面内质量为 $m$ 的质点 $\bar{Q}$。再次从对称性信息可以清楚地看出，球面作为一个整体产生的力只能沿线 $O\bar{Q}$ 方向传播。

因此，我们需要从球体$\Delta S$的元素中添加力$\Delta F_{OQ}$的分量，等于

$$\Delta F_{O\bar{Q}} = \gamma \frac{m\rho \Delta S \cos \beta}{\bar{l}^2} =$$
$$= \gamma \frac{m\rho R^2 \Delta S \cos \beta}{d^2 l^2},$$

(9)

如果我们再次使用它，我们根据对应关系（4）将其取反并用$l \frac{d}{R}$替换$\bar{l}$。

通过垂直于直线穿过点 $\bar{Q}$ 的平面将球体 $S$ 计算为两部分 $S_\Pi$ 和 $S_\lambda$
