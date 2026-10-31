---
id: 1976-4-ritus-o-reshenii-zadach-po-trigonometrii-s-primeneniem-formulyi-vspomogatelnogo-ugla-9eba4b2f
issue: kvant_1976_4
year: 1976
number: "4"
title: '[On solving trigonometry problems using the auxiliary angle formula]'
authors:
  - Ритус В.
rubric: raznoe
page_first: 43
page_last: 44
page_labels: 41-42
tag: T8SY
lang: en
source: kvant_digital
extraction: vision
content_sha256: 494f12d1c07a1517ca1f2e788b96b06ae23c8026e301f2663a1b84ab04ad5719
prompt_sha256: draft-1
translated_from: content/ru/1976/04/articles/09_ritus-o-reshenii-zadach-po-trigonometrii-s-primeneniem-formulyi-vspomogatelnogo-ugla-9eba4b2f.md
source_content_sha256: d0e1b78c8cb15c2839d6cc29e535b5b46c093b36201451431f171d201255ca2e
translation_model: draft
translation_run: en-draft-2026-10-31
translation_quality: draft
---

⟦folio 41⟧

mass 1.31 × (1000+x) e and, therefore, it contains 0.5 × 1.31 × (1000 + x) e of pure acid. We get the equation

$$1,51x = 0,5 \cdot 1,31(1000+x),$$

where $x \approx 766$ ml.

One can argue somewhat differently. The mass of $x$ ml of pure acid is equal to 1.51 x e, the mass of 1000 ml of water is 998 e, and the mass of a 50% solution is 1.31 (1000 + x) e. Since the total mass of the components coincides with the mass of the solution, we arrive at the equation

$$1,51x + 998 = 1,31(1000+x),$$

where $x \approx 1560$ ml.

We see that these two solutions lead to different results. In fact, both of these solutions are wrong. However, the gross fallacy of the second result is very visible: if more than one and a half liters of pure acid are added to a liter of water, then the concentration of the resulting solution will be higher than 50%.

The reason for the error is that the assumption of volume aditivity, which was used in both solutions, is not true. When acids are mixed with water, a bulk liquid exists; it can be explained by the action of forces between molecular attractions (water molecules move closer to acid molecules, penetrating into the “voids” between them). Therefore, the solution to the problem of mixing a liquid should be based on the law of conservation of mass: the total mass of the components of the solution is equal to the mass of the solution itself.

The correct solution to the problem considered is as follows. The mass of $x$ ml of pure acid is equal to 1.51 x e, the mass of 1000 ml of water is 0.998 x 1000 = 998 e), so the total mass of the components of the solution is (998 + 1.51 x) e (and the actual volume of a 50% acid solution is $\frac{998+1,51x}{1,31}$ ml). Searching for the mass of pure acid in a 50% solution coincides with the mass of the poured 100% acid, we obtain the equation 1.51x=0.5·(998+1.51x), from which we find $x \approx 661$ ml.

U right

1. What volume of 91% sulfuric acid must be added at 15 °C to 1 liter of water to obtain electrolyte for an automatic dissolution battery with a density of 1.290 e/cm³?

The density of 91% sulfuric acid at 15 °C is 1.825 e/cm³; sulfuric acid with a density of 1.290 e/cm³ at 15 °C has a concentration of 38.03%; The density of water at 15 °C is 0.999 e/cm³.

2. How much water should be poured into 800 ml of 100% acetic acid to obtain a 65% solution? Mixing will take place at 20 °C.

Density at 20 °C of 100% acetic acid - 1.0498 e/cm³; water - 0.998 e/cm³.

A. Asia (Odeska)

In his letter to the editor, Nechen Kong Qui (Hanoi, DRV) brings to the attention of the magazine's readers a rather interesting geometric fact, which mathematics lovers will no doubt appreciate. The solution to the given problem is a good test of how advanced the material in the planietri course is.

3. On the bottom plane there is a circle with mutually perpendicular diameters $AB$ and $CD$ and a straight line $m$ parallel to the straight line $AB$. Through the point $T$ of the circle (different from the points $C$ and $D$) a tangent to it is drawn, intersecting the line $AB$ at the point $K$ and the line $m$ at the point $M$. Let $E$ and $F$ be the points of intersection of line $m$ with lines $KC$ and $KD$, respectively. Prove that the product of the lengths of the segments $ME$ and $MF$ does not depend either on the radius of the circle or on the choice of point $T$ on the circle.

In trigonometric transformations and, in particular, when solving trigonometric equations, it can be useful to represent the expression $c \sin x + b \cos x$ in the following form:

$$a \sin x + b \cos x = \sqrt{a^2 + b^2} \sin(x + \varphi).$$

⟦folio 42⟧

The angle φ that appears in this formula is usually called the auxiliary angle. As is known, it is determined by the correspondence

$$\sin \varphi = \frac{b}{\sqrt{a^2 + b^2}}, \quad \cos \varphi = \frac{a}{\sqrt{a^2 + b^2}}$$

up to the term $2n\pi$ (where $n = 0, \pm 1, \pm 2, \ldots$). Therefore, it is enough to indicate one angle φ lying in some interval of length $2\pi$ to obtain all other values ​​of the auxiliary angle.

Let us pay attention to the following simple explicit formula for the auxiliary angle, which is not in school textbooks, but is convenient for solving problems, especially equations with a parameter. Let us choose the interval $-\pi < \varphi \leq \pi$ as the interval of length $2\pi$. then the only angle φ lying in this interval and satisfying the general relation (2) is determined by the formula

$$\varphi = \begin{cases} \arccos \frac{a}{\sqrt{a^2 + b^2}}, & \text{ если } b \geqslant 0; \\ -\arccos \frac{a}{\sqrt{a^2 + b^2}}, & \text{ если } b < 0. \end{cases}$$

In fact, regardless of the sign of $b$, both angles (3) satisfy the second relation (2), and the first relation (2) in the interval $-\pi < \varphi \leq \pi$ for $b \geqslant 0$ is satisfied only by $\varphi = \arccos \frac{a}{\sqrt{a^2 + b^2}}$ and for $b < 0$ only $\varphi = -\arccos \frac{a}{\sqrt{a^2 + b^2}}$.

It should be recalled that none of the relations (2), taken separately (or the relation $tg \varphi = b/a$, which follows from them, also taken separately), is sufficient for finding the auxiliary angle: it defines two angles in the interval of length $2\pi$, only one of which satisfies the general relation (2). So, if $a = -1$, $b = \sqrt{3}$, then the equation $tg \varphi = b/a$ has two roots in the interval $-\pi < \varphi \leq \pi$: $-\pi/3$ and $2\pi/3$, but only for the second of them is (1) valid.

The advantages of formula (3) can be easily seen in the following example.

Example 2 (MIEM, 1972). Solve the equation

$$\sin^6 x + \cos^6 x = a \sin 4x,$$

ede $a - \text{параметр}$.

By lowering the power on the left side of the equation twice, we reduce it to the form

$$a \sin 4x - \frac{3}{8} \cos 4x = \frac{5}{8},$$

from where, using formulas (1) and (3), we obtain:

$$\sqrt{a^2 + \frac{9}{64}} \sin (4x + \varphi) = \frac{5}{8},$$

$$\varphi = -\arccos \frac{a}{\sqrt{a^2 + \frac{9}{64}}}.$$

It is clear that a solution to this equation exists for

$$\frac{5}{8} \leq \sqrt{a^2 + \frac{9}{64}},$$

i.e. at $|a| \geqslant 1/2$, and the formulas are given

$$x = \frac{(-1)^n}{4} \arcsin \frac{5}{\sqrt{64a^2 + 9}} + \frac{1}{4} \arccos \frac{8a}{\sqrt{64a^2 + 9}} + \frac{\pi n}{4},$$

where $n$ is an integer. The use of formula (3) led to a very compact representation of the result (cf. the answer given in «Kvant», 1973, No. 7, pp. 47, 60-61).

V. Rumus (Moscow)

* *

As you know, some “non-standard” equations can be solved if you find a replacement for the unknown equation. Try to find such a replacement for the equation sent to the editor by 8th grade student S. Akhmedov (Minjevny station, Azerbaijan USSR).
