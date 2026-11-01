---
id: 1988-2-vasilev-gutenmaher-summa-uglov-sfericheskogo-mnogougolnika-3eeb551c
issue: kvant_1988_2
year: 1988
number: "2"
title: 球面多边形的内角和
authors:
  - Васильев Н. Б.
  - Гутенмахер В. Л.
rubric: shkola-v-kvante
page_first: 57
page_last: 57
page_labels: "55"
tag: 5RYQ
lang: zh
source: kvant_digital
extraction: vision
content_sha256: b1bc20c0183ed6c06e7924a44c855857020c4ad1ab42642d05eacf459a488aaa
prompt_sha256: draft-1
translated_from: content/ru/1988/02/articles/17_vasilev-gutenmaher-summa-uglov-sfericheskogo-mnogougolnika-3eeb551c.md
source_content_sha256: a8ef19958915666a094418e0790ae483e0aba1d98884a8f1f3b651ea35235186
translation_model: draft
translation_run: zh-draft-2026-11-01
translation_quality: draft
---

⟦folio 55⟧

岭。从地图的公式$B-P+M=1$，我们得到多面体的公式$B-P+\Gamma=2$。

欧拉一般定理

使用角度和来证明欧拉定理是一种很好的技术，但有些人为的技术。事实上，欧拉定理对于更一般的情况也是成立的——例如，对于球体上有$B$个顶点、$P$条边和$\Gamma$个国家的任意地图，任何一段曲线都可以作为“边”，只要每个国家都有几条连续边的边界（特别是，国家内部不应有“洞”，同样适用于其他国家）。然而，在更大的普遍性上证明该定理的可能想法之一是归纳法，其基础是将其中一个国家“收缩”到某一点。

下面的注释专门讨论球面上多边形的角度和以及球面上地图的欧拉定理。

球面多边形的内角和

在球体上，我们将考虑边是大圆弧的多边形。这样的多边形可以通过球体与顶点位于球体中心$O$（图1）的多面角的交集来获得。球体上的多边形角度的大小自然被认为是从顶点绘制的其“边”的切线之间的角度；由于切线垂直于从点 $O$ 向顶点绘制的半径，因此球体上多边形的角度等于该半径处的二角角。

我们在上一篇注释中简要提到的“角度之和”与面积之间的类比在这里变得显而易见：一个数量简单地通过另一个数量来表达。

定理。球体上多边形的面积与其角度和与$180^\circ(n-2)$之差成正比，其中$n$是多边形的顶点数。

比例系数仅取决于球体的半径。取球体的半径为1（那么球体的面积等于$4\pi$）并且让我们同意

图 1.

角度不是以度为单位，而是以弧度为单位（$180^\circ$ 对应于 $\pi$ 弧度）。那么球体上$n$边形的面积等于$\alpha_1+\alpha_2+\dots+\alpha_n-\pi(n-2)$，其中$\alpha_1, \alpha_2, \dots, \alpha_n$是它的角度。

特别地，单位球面上角度为$\alpha, \beta, \gamma$的三角形的面积等于$\alpha+\beta+\gamma-\pi$。

让我们检查一下由穿过中心的相互垂直的平面切出的球体轮廓的公式$S=\alpha+\beta+\gamma-\pi$：该轮廓具有三个角，每个角为$\pi/2$，根据该公式，它的面积等于$3\pi/2-\pi=\pi/2$ - 事实上，这是所有球体面积$4\pi$的$1/8$部分。

对于球面三角形证明这个定理就足够了：从这个特殊情况可以得到通式，就像证明平面 $n$-gon 的角度和定理一样 - 使用切割和数学归纳法。

继续球面三角形的边，我们得到三个大圆，将球体分为 8 个三角形（可以方便地想象这些大圆的三个平面在中心$O$相交，将空间分为 8 个三角形角 - 每个三角形角在球体上刻出一个三角形）。让我们用 $\alpha, \beta$ 和 $\gamma$ 表示三角形的角，用 $S$ 表示三角形的面积，用 $a, b$ 和 $c$ (图 2) 表示与它相邻的三角形的面积（分别与$\alpha, \beta$ 和 $\gamma$ 相对的边相邻）。与每个三角形一起，我们的三个
