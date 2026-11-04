---
id: 2024-4-tereshin-pro-treugolnik-a2v2s2-8fd793f4
issue: kvant_2024_4
year: 2024
number: "4"
title: About triangle 222
authors:
  - Терёшин Д. А.АВС
rubric: zadachnik-kvanta
rubric_sub: Задачник «Кванта»
page_first: 24
page_last: 26
page_labels: 22-24
lang: en
source: kvant_digital
extraction: vision
content_sha256: 64e1dad63a13bbc1e5a270d50a869de16bbf8253ec0e81e38761c8b2f0b5bbfd
prompt_sha256: draft-1
translated_from: content/ru/2024/04/articles/06_tereshin-pro-treugolnik-a2v2s2-8fd793f4.md
source_content_sha256: 4614b11d1de4725bb0f5b6455a13d3dbe4e6e140983ce64c608e872685c0f9bb
translation_model: draft
translation_run: en-draft-2026-11-03
translation_quality: draft
---

⟦folio 22⟧

---
running_head:
folio:
---

surface of the Earth and the corresponding refraction value for normal atmospheric conditions.
Accurate calculations of the angle of atmospheric refraction depending on the actual angular height of an object above the horizon is not an easy task, but astronomers successfully solve it. And in this case, when observing from a space station the rising or setting of a luminary (Lunya or the Sun) above the horizon, the light emitted by the luminary passes through the atmosphere twice - first falling from the less dense to the denser layer and passing over the surface of the Earth,

and then in reverse order from the Earth's surface to the upper layers of the atmosphere. In this case, layers of air of different densities replace each other along the path of the light beam. When passing through the atmosphere in this way, the light beam turns in the same direction twice.
For observers-cosmonauts, the visible deformation of the star, manifested in the flattening of the lower part, is twice as large as for observers located on the surface of the Earth.

S. Lunin

About the triangle
A₂B₂C₂

A.TEROSHIN

In this article we will present the solution to one geometric problem, which was presented at the Southern Mathematical Tournament and then included in the Kvan task. In addition, by considering this construction, we will obtain some interesting results, in particular, we will adapt Feuerbach's theorem.

Task M2781. Let point A₁ be the midpoint less than the arc BC circumscribed about the acute triangle ABC of the circle (Fig. 1). Point A₁ was reflected relative to side BC, and then its image was reflected relative to the bisserris of angle BAC to obtain point A₂. Points B₂ and C₂ were obtained similarly. Prove that the Euler line of triangle A₂B₂C₂ passes through the circumcenter and circumcenter of triangle ABC.

Problem solution

Let us denote by O and I the centers of the circumscribed and circumscribed circles of triangle ABC. Let l be a perpendicular to the segment OI passing through point I.

Lemma 1. A point symmetric to point A₂ with respect to l lies on line OA₁.

DOI: https://doi.org/10.4213/kvant20240403

Fig. 1

Proof. Let us mark the point A₂′ of intersection of the straight line OA₁ and the perpendicular from the point A₂ to l (Fig. 2). Let point A₁′ be symmetrical to point A₁ relative to BC. Triangle A₁CA′ is similar to triangle A₁OC as it is equilateral with angle OA₁C at the base. This means OA₁ · A₁A′ = A₁C² = A₁I² (the last equality follows from the trident lemma), which is equivalent to the similarity of triangles A₁IA′ and A₁OI, which implies the equality of angles ∠A₁A′₂A₂ = ∠A₁OI = ∠A₁IA′ = ∠A₁IA² (the first equality follows from the parallelism of the lines OI and A₂A′₂, and the last from symmetry). From the equality of angles A₁A′₂A₂ and A₁IA² it follows that the quadrilateral A₁A′₂IA² is cyclic. Prima A₁I is the bisserris of the angle A₂A₁A′₂, i.e. point I lies on the perpendicular bisector to the segment A₂A′₂, which implies the symmetry of points A₂ and A₂′ relative to l. The lemma is proven.

⟦folio 23⟧

---
running_head:
folio:
---

From the above solution it follows that the circumcircle of the triangle $A_1A_2I$ is tangent to the line $OI$, from which we obtain the corollary.

Consequence. The circumcircles of triangles $A_1A_2I$, $B_1B_2I$ and $C_1C_2I$ touch at point $I$.

Communication with the orthocenter
Note the orthocenter $H$ of the triangle $ABC$ (Fig. 4). It turns out that this then holds several interesting properties.

Fig. 2
Dallee, $\angle OIA'_2 = \angle IA'_2A_2 = \angle OA_1I$, open triangles $OIA'_2$ and $OA_1I$ are similar, so $OA'_2 = \frac{OI^2}{OA_1} = \frac{OI^2}{R}$. From the last equality we see that the length of the segment $OA'_2$ does not depend on the vertex $A$, therefore for similar points $B'_2$ and $C'_2$ the point $O$ is equal to all three vertices of the triangle $A'_2B'_2C'_2$, it follows that the triangles $A_1B_1C_1$ and $A'_2B'_2C'_2$ are prepared with the center at the point $O$ (Fig. 3). As is known, $I$ is the orthocenter of triangle $A_1B_1C_1$, i.e. line $OI$ is the Euler line of triangle $A_1B_1C_1$, which, when prepared with the center at point $O$, transforms into itself, i.e. the Euler straight line of the triangle $A'_2B'_2C'_2$ passes through the points $O$ and $I$, which means the Euler straight line of the triangle $A_2B_2C_2$, symmetric to the triangle $A'_2B'_2C'_2$ with respect to $l$, also passes through the points $O$ and $I$. Problem solution!

Fig. 4
Property 1. The perendiculars dropped from the point $A_2$, $B_2$, $C_2$ (or $A'_1$, $B'_1$, $C'_1$) on the corresponding bisserprix of the triangle $ABC$ all pass through the points $H$.

Proof. It is enough for us to prove that $A'_1H \perp AA_1$. Let's mark the middle $M$ of the segment $BC$ and the point $W$, diametrically opposite to the point $A_1$. Since $WA_1$ is the diameter of the circumscribed circle, then $AW \perp AA_1$, so it is enough to prove that $HAWA'_1$ is a parallelogram. To do this, we show that $AH = WA'_1$, since these segments are already parallel, since they are both perpendicular to $BC$. As is known,

$$AH = 2OM = 2(OA_1 - MA_1) = WA_1 - A'_1A_1 = WA'_1.$$

Property 2. Points $A_2$, $B_2$, $C_2$, $H$ lie on the same circle.

Proof. Let the point $H$ lie inside the angle $B_2A_2C_2$ (Fig. 5), other locations of the point are considered similarly. Since $\Delta A_2B_2C_2 \sim \Delta A_1B_1C_1$, we get that $\angle A_2B_2C_2 = \angle A_1B_1C_1$. Note that $A_2H \parallel B_1C_1$, since both of these straight lines are perpendicular

⟦folio 24⟧

---
running_head:
folio:
---

Fig. 5
are dicular to the straight line $AA_1$. Indeed, $A_2H \perp AA_1$ by property 1, and $B_1C_1 \perp AA_1$, for example, because the half of the arcs $AC_1$ and $A_1B_1$ is equal to a quarter of the entire circle. Thus, $A_2H \parallel B_1C_1$, $C_2H \parallel A_1B_1$ and $\angle A_2HC_2 = \angle A_1B_1C_1$, whence $\angle A_2B_2C_2 = \angle A_2HC_2$ and the points $A_2$, $B_2$, $C_2$, $H$ lie on the same circle.

NEW EVIDENCE
Feuerbach's theorems

Let us remember that earlier in solving the problem we found out that the circumscribed circle is three-
