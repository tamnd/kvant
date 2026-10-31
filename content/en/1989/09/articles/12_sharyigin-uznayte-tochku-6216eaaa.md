---
id: 1989-9-sharyigin-uznayte-tochku-6216eaaa
issue: kvant_1989_9
year: 1989
number: "9"
title: Find out the point
authors:
  - Шарыгин И. Ф.
rubric: matematicheskiy-kruzhok
rubric_sub: Математический кружок
page_first: 54
page_last: 58
page_labels: 52, 53, 54, 56
tag: 1WXZ
lang: en
source: kvant_digital
extraction: vision
content_sha256: 18b37df9b431866cbd955b6b62fc95ec8ee98136cc2739ea3c8f14223488cdc0
prompt_sha256: draft-1
translated_from: content/ru/1989/09/articles/12_sharyigin-uznayte-tochku-6216eaaa.md
source_content_sha256: e3658872218046810b99ed6c502ae78aaf8436bc1a9a7db0ef72b73dfa190c02
translation_model: draft
translation_run: en-draft-2026-10-31
translation_quality: draft
---

⟦folio 52⟧

Find out the point

I. F. SHARYGIN

In geometry, the properties of figures that unambiguously describe them or relate to a fully defined class of figures are very important - the so-called “features”. You are familiar, for example, with a number of signs of a parallelogram and can easily recognize it in a quadrilateral with pairwise equal opposite sides or with diagonals bisected by their intersection point, etc. There are other, more “cunning” signs of a parallelogram. It is known, for example, that in a parallelogram the sum of the squares of the diagonals is equal to the sum of the squares of the sides. It turns out that the opposite statement is also true: if in a quadrilateral the sum of the squares of the sides is equal to the sum of the squares of the diagonals, then this quadrilateral is a parallelogram.

Exercise 1. Prove it yourself. (Indication: From the direct theorem, obtain a formula expressing the square of the median of a triangle in terms of the squares of its sides. Using this formula, express the square of the distance between the midpoints of the diagonals of a quadrilateral in terms of the squares of its sides and diagonals.)

In this article we will talk a little about “signs of a point”. In the school course, several “remarkable” points of the triangle are studied. These points have a number of interesting properties, most of which uniquely define this point. However, we often have difficulty “recognizing” a point, even if its well-known properties are indicated.

Intersection point of medians (centrides)

Some characteristics of the property of a “remarkable” point may be

⟦folio 53⟧

used not only to “recognize” it, but also to prove its existence.

Many schoolchildren know that the medians of a triangle intersect at one point, although not everyone knows how to prove this. On the other hand, it is not difficult to prove that inside any triangle ABC there is a point M such that triangles ABM, BCM and CAM are equal in size (Fig. 1).

The best thing is to simply build this point. Since the area of ​​triangle ABM is 1/3 of the area of ​​triangle ABC, point M is located on a line parallel to AB and distant from AB at a distance equal to 1/3 of the corresponding height. Similarly, M must be located on a similar line parallel to BC, i.e. M is the intersection point of these two lines. Since the area of ​​triangles ABM and BCM is 1/3 the area of ​​triangle ABC, the area of ​​triangle CAM is also 1/3 the area of ​​ABC.

Now we will prove that all medians of a given triangle pass through point M and are divided there in a ratio of 2:1, counting from the vertices of the triangle. In fact, from the equal size of the points of triangles ABM and BCM it follows that points A and C are equal to the line BM, which means that this line must pass through the middle of the segment BC (this line cannot be parallel to BC). And from the fact that the area of ​​triangle CAM is 1/3 of the area ABC, it follows that the distance from M to CA is second less than the distance from B to CA, which means that M divides the medina BB₁ in the ratio BM:B₁M=2. Thus, the medians of the triangle intersect at one point and divide it in the indicated ratio. So, we got the centrador sign:

Sign M₁. The interior point M of triangle ABC is the center if and only if triangles ABM, BCM and CAM are equal in size.

Let us prove two more criteria for a centrador.

In order for point M to be the center of triangle ABC, which of the following conditions is necessary and sufficient:

M₂ sign. MA+MB+MC=0.
Sign M₃. MA²+MB²+MC²=1/3 (AB²+BC²+CA²).

Proof. Let's start with M₂. Let M be the intersection point of the medians of triangle ABC (Fig. 2).

We have MA+MB+MC=MA+(MA₁+A₁B)+(MA₁+A₁C)=(MA+2MA₁)+(A₁B+A₁C)=0. Conversely, let the point M satisfy the criterion M₂ and A₁ be the point of intersection of MA with BC. (Prove that straight line MA cannot be parallel to BC). Then, as above, we will have MA+MB+MC=(MA+2MA₁)+(A₁B+A₁C)=0. But the sum of two non-clipart vectors written in parentheses can only equal zero if each vector is equal to zero. Therefore, A₁ is the midpoint of BC.

Fig. 1.

Fig. 2.

⟦folio 54⟧

Let us now prove that the feature $M_3$ is equivalent to the feature $M_2$. Let $M$ be an arbitrary point on the plane. First of all, we note that from the equality $\overrightarrow{MA} - \overrightarrow{MB} = \overrightarrow{BA}$, after squaring it, we obtain $2\overrightarrow{MA} \cdot \overrightarrow{MB} = MA^2 + MB^2 - AB^2$.

Similar equalities are true for $2\overrightarrow{MB} \cdot \overrightarrow{MC}$ and $2\overrightarrow{MC} \cdot \overrightarrow{MA}$. Next, $0 \leqslant (\overrightarrow{MA} + \overrightarrow{MB} + \overrightarrow{MC})^2 = MA^2 + MB^2 + MC^2 + 2\overrightarrow{MA} \cdot \overrightarrow{MB} + 2\overrightarrow{MB} \cdot \overrightarrow{MC} + 2\overrightarrow{MC} \cdot \overrightarrow{MA} = 3(MA^2 + MB^2 + MC^2) - (AB^2 + BC^2 + CA^2)$. Thus, equality 2 implies equality 3, and vice versa. Along the way, we proved that $MA^2 + MB^2 + MC^2$ reaches its minimum value if $M$ is a centroid (and this is also a sign of a centroid).

As an illustration, let us solve the following problem.

Problem 1. Squares are built on the sides of the triangle to the outside. Prove that the point of intersection of the medians of a triangle with the vertices at the centers of the squares coincides with the point of intersection of the medians of the given triangle.

Solution. Let $M$ be the intersection point of the medians of the triangle $ABC$, $A_1$ the midpoint of $BC$, $A_2$ the center of the square built on $BC$ (Fig. 3).

Then $\overrightarrow{MA} = \overrightarrow{MA_1} + \overrightarrow{A_1A_2}$. We have $\overrightarrow{MA_2} + \overrightarrow{MB_2} + \overrightarrow{MC_2} = (\overrightarrow{MA_1} + \overrightarrow{MB_1} + \overrightarrow{MC_1}) + (A_1A_2 + B_1B_2 + C_1C_2)$. But the sum of the vectors in each of the brackets is zero. In the first - according to the sign $M_2$. In the second, because each of the vectors of this sum is obtained respectively from $\frac{1}{2}\overrightarrow{BC}$, $\frac{1}{2}\overrightarrow{CA}$ and $\frac{1}{2}\overrightarrow{AB}$ by rotating by $90^\circ$ clockwise. This means that $M$ is the centroid of triangle $A_2B_2C_2$.

Circumcenter

This time we will not expand on the school theory, but will look at two examples.

Problem 2. In triangle $ABC$ the following angles are known: $\angle A = 30^\circ$, $\angle B = 80^\circ$.

Inside the triangle, a point $K$ is taken such that $BCK$ is a regular triangle. Find $\angle KAC$.

Solution. This task was proposed at the 1989 Moscow Olympiad in the 10th grade. Most of the participants in the Olympiad tried to solve it by “counting” using the theorem of sines, without seeing that the point $K$ is the center of the circle circumscribed about $ABC$. In fact, from the center of the circle circumscribed about $ABC$, side $BC$ is visible at an angle $2\cdot 30^\circ = 60^\circ$, this center is located inside the triangle (the triangle is acute) and lies on the perpendicular bisector to $BC$. So, $K$ is the center of the circumscribed circle (Fig. 4), $\angle CKA = 2\cdot 80^\circ = 160^\circ$, $\angle KAC = \angle KCA = 10^\circ$.

Problem 3. In the convex quadrilateral $ABCD$ the following angles are known: $\angle BAC = 25^\circ$, $\angle BCA = 20^\circ$, $\angle BDC = 50^\circ$, $\angle BDA = 40^\circ$. Find the angle between the diagonals of this quadrilateral.

Solution. An indirect argument can be made to prove that the point $D$ is the center of the circle circumscribed about $ABC$. Since the triangle $ABC$ is obtuse, the center of the circumcircle is located on the other side of $AC$ than the vertex $A$, and from this center the sides $BC$ and $BA$ are visible at angles $50^\circ$ and $40^\circ$, respectively. In addition, there is only one such point (make sure of this).

⟦folio 56⟧

Height intersection bud (orthocenter)

There are many different proofs of the theorem that the altitudes of a triangle intersect at one point. We will give a proof based on one general idea, already familiar to you from the proof of theorems that the bicsectrices of a triangle, as well as the midpoints of the perpendiculars to its sides intersect at one point.

For convenience, consider the acute triangle ABC. Note that for all points of height AA1 the ratio of the distances to side AB and AC is constructed and equal to $\frac{\cos B}{\cos C}$. (Straight line AA1 is the locus of points, the ratio of the distances from which to straight lines AB and AC is equal to $\frac{\cos B}{\cos C}$.) The same is true for the other two heights. Let us denote by $H$ the point of intersection of the heights of AA1 and BB1 (Fig. 7). Know the ratio of distances from $H$ to AB and $AC$ ($\frac{\cos B}{\cos C}$) and the ratio from $H$ to BA and $BC$ ($\frac{\cos A}{\cos C}$), we find that the ratio of distances from $H$ to CA and CB is $\frac{\cos A}{\cos B}$ and therefore $H$ belongs to the third height.

The case of an obtuse triangle is related to distance, since (see Fig. 7) for triangle ABH point C is the point of intersection of the heights omitted from vertices A and B.

When solving problems, the following is often used.

Property $H_1$. The radius of a circle passing through two vertices of a triangle and the point of intersection of its altitudes is equal to the radius of the circumscribed circle of the triangle.

Sometimes it is more convenient to formulate the property $H_1$ a little differently.

Property $H'_1$. A circle passing through two vertices of a triangle and the point of intersection of the altitudes is symmetrical to the circumcircle of the triangle relative to the corresponding side of the triangle.

Exercise 4. Prove the statement $H_1$ and $H'_1$.

In conclusion - one simple theorem.

Problem 4. There are three equal circles on a plane,
