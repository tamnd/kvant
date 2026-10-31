---
id: 1976-7-ponarin-skalyarnoe-proizvedenie-vektorov-v-geometricheskih-zadachah-vyichislenie-ploschadey-4c7e32dd
issue: kvant_1976_7
year: 1976
number: "7"
title: Dot product of vectors in geometric problems. Calculation of areas
authors:
  - Понарин Я. П.
rubric: matematicheskiy-kruzhok
rubric_sub: Математический кружок
page_first: 27
page_last: 29
page_labels: 25, 27
tag: L0J1
lang: en
source: kvant_digital
extraction: vision
content_sha256: 193867aa9d879da302322982d910d122cc71a1e629ff6990b63a2f2daafb2efc
prompt_sha256: draft-1
translated_from: content/ru/1976/07/articles/08_ponarin-skalyarnoe-proizvedenie-vektorov-v-geometricheskih-zadachah-vyichislenie-ploschadey-4c7e32dd.md
source_content_sha256: 5f1fc9d5d3e34cb13f3e9f70fcea2824acc72fc1e02c44b242ffcdcb29fc79e6
translation_model: draft
translation_run: en-draft-2026-11-01
translation_quality: draft
---

⟦folio 25⟧

Ya. Ponarin

Raising areas

Area of ​​a triangle
It is known that the area of ​​triangle ABC can be calculated using the formula
$$S = \frac{1}{2} ab \sin \hat{C},$$
(1)

where a, b and c are the side lengths of the triangle lying opposite the angles $\hat{A}, \hat{B}$ and $\hat{C}$, respectively.

Let us denote the vectors $\vec{CB}$ and $\vec{CA}$ of the sides of the triangle by $\vec{a}$ and $\vec{b}$. From the definition of the scalar product of vectors it follows that $\cos \hat{C} = \frac{\vec{a} \cdot \vec{b}}{|\vec{a}| \cdot |\vec{b}|}$, whence $\sin^2 \hat{C} = \frac{a^2 b^2 - (\vec{a} \cdot \vec{b})^2}{a^2 b^2}$
(the scalar square of a vector is equal to the square of its length).

Let us square both sides of formula (1) and substitute the found expression for $\sin^2 \hat{C}$; we get
$$4S^2 = a^2 b^2 - (\vec{a} \cdot \vec{b})^2.$$
(2)

Formula (2) will be useful to us later (in particular, from it it is easy to obtain Heron’s formula for the area of ​​a triangle).

Area of ​​a quadrilateral
If p and q are the lengths of the diagonals of an arbitrary flat quadrilateral (whose opposite sides do not intersect at interior points), then its area can be found using the formula
$$S = \frac{1}{2} pq \sin (\vec{p}, \vec{q}).$$
(3)

As in the case of a triangle, we rewrite this formula in a form similar to (2):
$$4S^2 = p^2 q^2 - (\vec{p} \cdot \vec{q})^2.$$
(4)

To evaluate the resulting formulas (2) and (4), let's solve several problems (if you try to solve them differently, without using the scalar product, you will see how complicated the solution is).

Problem 1. Calculate the area of ​​face ABC of the metrahedron ABCD if a, b, c are the lengths of its edges DA, DB and DC, and α, β, γ are the plane angles at vertex D corresponding to the adjacent edges BC, AC and AB.

Solution e. Let us introduce the following notation: $\vec{DA} = \vec{a}, \vec{DB} = \vec{b}, \vec{DC} = \vec{c}$. Then for the area S of the face ABC we have
$$4S^2 = |\vec{CA}|^2 \cdot |\vec{CB}|^2 - (\vec{CA} \cdot \vec{CB})^2 = (\vec{a} - \vec{c})^2 \cdot (\vec{b} - \vec{c})^2 - ((\vec{a} - \vec{c}) \cdot (\vec{b} - \vec{c}))^2 = (a^2 + c^2 - 2ac \cos \beta)(b^2 + c^2 - 2bc \cos \alpha) - (ab \cos \gamma - ac \cos \beta - bc \cos \alpha + c^2)^2.$$

In fact, the problem has already been solved, but the resulting expression includes the lengths a, b, c and the angles α, β, γ asymmetrically, although according to the conditions of the problem the values ​​of a, b, c, as well as α, β, γ should

⟦folio 27⟧

Task 4. A plane is drawn through the vertex of a regular metrahedron with edge a so that the line of its intersection with the plane of the base is parallel to the side and divides the base into two equal parts. Find the cross-sectional area of ​​the metrahedron by the indicated plane (Fig. 3).

Solution. In this regular tetrahedron we denote $ABCD$ $\vec{DA} = \vec{a}$, $\vec{DB} = \vec{b}$, $\vec{DC} = \vec{c}$, and $|\vec{a}| = |\vec{b}| = |\vec{c}| = a$. Let the cutting plane intersect the plane $ABC$ along the straight lines $MN$, $M \in (AB)$, $N \in (AC)$ and $(MN) \parallel (BC)$. The required cross-sectional area can be calculated using the formula

$$4S^2 = |\vec{DM}|^2 \cdot |\vec{DN}|^2 - (\vec{DM} \cdot \vec{DN})^2.$$

This formula tells you how to solve the problem.

We have $\vec{DM} = \vec{DA} + \vec{AM}$, where $\vec{AM} = k \cdot \vec{AB}$.

The number $k$ is found from the condition that the line $MN$ divides the base $ABC$ into two equal parts, and so that the triangles $AMN$ and $ABC$ are similar; That's why

$$S_{AMN} : S_{ABC} = |\vec{AM}|^2 : |\vec{AB}|^2 = k^2 = \frac{1}{2},$$

whence $k = \frac{1}{\sqrt{2}}$. That's why

$$\vec{DM} = \vec{DA} + k \cdot \vec{AB} = a + \frac{1}{\sqrt{2}} (\vec{b} - \vec{a}) = \frac{(\sqrt{2} - 1) \vec{a} + \vec{b}}{\sqrt{2}}.$$

Same as $\vec{DN} = \frac{(\sqrt{2} - 1) \vec{a} + \vec{c}}{\sqrt{2}}$.

Substituting the expressions for $\vec{DM}$ and $\vec{DN}$ into the formula for $S$, we get

$$16S^2 = ((\sqrt{2} - 1) \vec{a} + \vec{b})^2 \cdot ((\sqrt{2} - 1) \vec{a} + \vec{b}) \times ((\sqrt{2} - 1) \vec{a} + \vec{c})^2.$$

Since for a regular tetrahedron with edge length $a$

$$\vec{a} \cdot \vec{b} = \vec{b} \cdot \vec{c} = \vec{a} \cdot \vec{c} = \frac{1}{2} a^2,$$

then after all the asking we get

$$S = \frac{1}{8} a^2 \sqrt{11 - 4\sqrt{2}}.$$

Solve the following problems on your own:

1. Given an arbitrary quadrilateral $ABCD$. Points $A_1$ and $C_1$ are images of both vertices $A$ and $C$ when the pector parallels their intersection. Prove that the quadrilateral $A_1BC_1D$ is equal in size to the given quadrilateral $ABCD$.

2. In the tetrahedron $ABCD$ the lengths of all six edges are known: $|DA| = a$, $|DB| = b$, $|DC| = c$, $|BC| = a_1$, $|AC| = b_1$, $|AB| = c_1$. A plane is drawn through the middle of edge $DB$ parallel to edges $AD$ and $BC$. Find the cross-sectional area of ​​the tetrahedron by this plane.

3. In a regular triangular triangle, take the plane angle at the vertex to be $\alpha$ and the length of the side edge to be $a$. Find the cross-sectional area of ​​the plane passing through the side of the base and the middle of the opposite side rib.
