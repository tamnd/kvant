---
id: 1985-8-petrov-visyachie-mostyi-a0c6ec0e
issue: kvant_1985_8
year: 1985
number: "8"
title: Suspension bridges
authors:
  - Петров Ю. С.
rubric: osnovnye-stati
page_first: 24
page_last: 26
page_labels: 22-24
tag: DE73
lang: en
source: kvant_digital
extraction: vision
content_sha256: 8f99adf611b9bfed7a2377641aa81ce4ed9c027443d49870bc1e8717ae295e69
prompt_sha256: draft-1
translated_from: content/ru/1985/08/articles/09_petrov-visyachie-mostyi-a0c6ec0e.md
source_content_sha256: e5034df7dc0abd4dee893ac4ef16042af52aff77b27569481a63062bf3867e74
translation_model: draft
translation_run: en-draft-2026-11-01
translation_quality: draft
---

⟦folio 22⟧

Hanging
bridges

Y. S. PETROV

Suspension bridges... They amaze with the boldness of their design, the purity and perfection of their lines. Thin vertical cables, descending from gracefully curved sagging ropes, easily hold in the air a multi-toned asphalt strip along which automated machines hurriedly scurry. Take a look at figure - what a feeling of impact and lightness! But behind this lightness lies the miraculous direction of all the links of the structure, and the majestic stillness of the place hovering above the river eye is a consequence of the balance of huge invisible forces tamed by the mind of the constructs.

Before becoming a complete structure made of steel and concrete, the site is designed and carefully calculated by a large number of civil engineers. But the design of structural places is preceded by the development of their general mathematical theory, the solution of many fundamental and particular mathematical problems. One of these problems is directly addressed when you look at a suspension bridge: what kind of curve, a certain shape, should the sagging ropes have to ensure their balance?

Usually the answer to the question posed is confident:

⟦folio 23⟧

vectors *). This note is related to this decision.

The load-bearing part of the highest place consists of ropes and suspension rods, which we will assume are vertical, located at equal distances from each other and equally loaded (see figure). We will run over the weight of these rods and rope. Finally, we will assume that the rope is symmetrical with respect to some vertical line and that it is absolutely flexible and inextensible. Let us take the vertical plane containing the rope as the coordinate plane, the straight line of its intersection with the elevation plane, which is assumed to be horizontal, as the Ox axis, and the symmetry axis as the Oy axis. Let us denote by a the distance between the rods and by (x_k, y_k) the coordinates of the vertex M_k (see diagram). Let us assume that the tension of the horizontal link

*) You can read about sliding vectors in the article by Yu. P. Solovyov and A. B. Sosinsky in this issue of the journal. To understand this note, however, there is no need to break down this entire article in detail.

Load-bearing part of the place:
rope - broken
... M₀M₁M₂M₃ ...
hanging rods - sections
... M₁P₁, M₂P₂, M₃P₃, ...

23

⟦folio 24⟧

but in the opposite direction.
According to symmetry messages, it is enough to consider only one half of the rope (say, the one that has positive abscissas). The vertex $M_1$ is in equilibrium under the action of three forces: $T_0$, $F_1$ and $T_{12}$, from where

$$tg a_1 = \frac{|F_1|}{|T_0|} = \frac{p}{T_0}.$$

The vertex $M_2$ is in equilibrium under the action of forces $T_{21}$, $F_2$ and $T_{23}$, hence $tg a_2 = 2p/T_0$. Likewise, $tg a_k = kp/T_0$.

We are now able to calculate the coordinates $(x_k, y_k)$ of vertex $M_k$. the coordinates of the vertex $M_1$ are equal to $(a/2, b)$, where $b$ is the distance from the horizontal link to the axis $Ox$. the coordinates of the remaining vertices can be calculated sequentially using the formulas

$$x_k = x_{k-1} + a, \quad y_k = y_{k-1} + a \ tg a_{k-1}.$$

Hence,

$$x_k = \frac{a}{2} + (k-1)a,$$

$$y_k = b + \frac{ap}{T_0} [1 + 2 + \ldots + (k-1)] = b + \frac{k(k-1)ap}{2T_0}.$$

The formula for $y_k$ can be obtained in another way. To derive it, it is enough to replace that the external forces applied to the part $M_1 M_2 \ldots M_k$ of the rope form a system of vectors equivalent to zero, as a consequence of which the sum of their moments relative to the point $M_k$ is equal to zero.
