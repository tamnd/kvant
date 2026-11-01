---
id: 1977-6-vavilov-geometriya-kruga-3f15e358
issue: kvant_1977_6
year: 1977
number: "6"
title: Circle geometry
authors:
  - Вавилов В. В.
rubric: raznoe
rubric_sub: Разное
page_first: 40
page_last: 44
page_labels: 38-42
tag: ZOXQ
lang: en
source: kvant_digital
extraction: vision
content_sha256: 7e0bc3d03960aeda016d9e31d8ab9b6b91758bfeb17ddd37cef4051ef5d174f0
prompt_sha256: draft-1
translated_from: content/ru/1977/06/articles/10_vavilov-geometriya-kruga-3f15e358.md
source_content_sha256: da25c964088fbce3e39374bdbf202efa292c754bcddaab3420d3ec15ddc6ee8e
translation_model: draft
translation_run: en-draft-2026-11-01
translation_quality: draft
---

⟦folio 38⟧

Circle geometry

V. Vavilov

“All my works are ceras.
Serious concerns."

Moritz Escher

In this lesson we will talk about one plane transformation - inversion, and then, as usual, we will create a task and attach a sample for its implementation.

1. Definition. Inversion I with respect to the circle γ is called a transformation of the plane, which for each point M of the plane different from the center O of the circle, we associate a point M on the ray OM, implying that

$$|OM'| \cdot |OM| = r^2;$$

here r is the radius of the circle γ. The circle γ is called the circle of inversion, and the point O is the center of inversion.

If M lies on the inversion circle (M ∈ γ), that is, if |OM| = r, then |OM'| = r²/|OM| = r and M' ∈ γ. But points M and M' lie on the same ray; therefore they coincide. This means that all points of the circle γ are fixed points of the transformation I: I(M) = M, M ∈ γ.

Note that there is no corresponding point for the center O. The fact is that the quantities |OM'| = r²/|OM| tend to infinity when |OM| tend to zero, that is, when M → O. In order to have a one-to-one correspondence for all points of the plane without exception, we must make the plane one new point O∞ (“infinitely distant”) and we will assume that the point O with the inversion of I corresponds to the point O∞, and the point O∞ to the point O.

In addition, we will assume that all lines contain O∞.

Let M₁ = I(M), M₂ = I(M₁). All points M, M₁ and M₂ lie on

⟦folio 39⟧

one beam and
$$|OM_1| \cdot |OM| = r^2,$$
$$|OM_1| \cdot |OM_2| = r^2.$$
From here we get that
$$|OM_2| = |OM|.$$
Thus, if $M$ is an arbitrary point on the plane, then performing the inversion $I$ twice takes the point $M$ back to the same point. Consequently, the “square” of the inversion is the identical transformation of the plane.

Symmetry relative to a straight line has a similar property; hence the inversion is sometimes called "circular symmetry".

Let's take the point $M$, which lies in the interior of the circle with the edge $\gamma$ and is different from $O$, and construct the point $I(M) = M'$. Let $N$ be one of the ends of the chord of the inversion circle $\gamma$ passing through the point $M$ perpendicular to $[OM)$ (see Fig. 1). then the required point $M'$ is the intersection point of the ray $OM$ and the tangent to the circle $\gamma$ at the point $N$. In fact, since the right triangles $ONM$ and $ONM'$ are similar to $|ON| = r$, then $|OM| / r = r / |OM'|$, that is, $|OM'| \cdot |OM| = r^2$. When it is necessary to construct the point $I(M)$ for the point $M$, which lies in a non-circle with the edge $\gamma$, then from the same figure it is clear that if $N$ is one of the points of intersection of the circle $\gamma$ with a circle constructed on $[OM]$ as a diameter, then the required point $M'$ is the base of the perpendicular dropped from point $N$ to $[OM]$.

Here is another example of the geometric construction of the point $I(M)$ - using only a compass. By distance is the case when the point $M$ does not lie in a circle with the edge $\gamma$. With radius $|OM|$ we describe an arc with center $M$ intersecting $\gamma$ at points $L$ and $N$ (Fig. 2). Then from these points as from centers we describe arcs with a radius $r$ (equal to the radius of the circle $\gamma$); these arcs intersect with line $OM$ at two points - point $O$ and some point $M'$. In equilateral triangles $OLM'$ and $OLM$ the angles at the base are congestive:

$$\widehat{OLM} = \widehat{MO}L = \widehat{OM'}L,$$

⟦folio 40⟧

3°. A circle passing through point O into a line not passing through point O (Fig. 3).

4°. A circle not passing through point O into a circle not passing through point O (Fig. 4).

We do not provide proof of these properties. Prove them yourself or read in the article by A.P. Savin “Inversion and weaponry of Apollo” («Kvant», 1971, No. 8).

From properties 1°-4° it is clear that circles and straight lines are equal. If we agree to consider a straight line as a circle of “infinitely large radius,” then the listed properties mean that during inversion the circle always turns into a circle. Inversion relative to a circle of “infinitely large radius” (that is, relative to a straight line) coincides with ordinary symmetry relative to a straight line (why?).

Definition. The value between two intersecting circles (including straight lines) is the value of the smallest angle that forms tangents at the point of their intersection.

Two circles are called orthogonal if they intersect at right angles.

Let us note two more properties of inversion:

5°. Inversion takes the circle orthogonal to the inversion circle γ into itself.

6°. Inversion does not change the magnitude of the angles intersecting the circles.

The 5° property means that the circle orthogonal to the inversion circle γ is motionless (but not pointwise motionless: γ divides this circle into two parts, which, when inverted, go to the other - see figure 5).

Task 1. Construct an image of the word depicted on figure 6 with inversion with respect to the circle γ. Compare the result with figure on p. 66.

Problem 2. Prove that the point M==(x; y) when inverted relative to a circle with center at the origin and radius r goes to the point M'=(x'; y'), the coordinates of which are determined by the formulas

$$x' = \frac{xr}{x^2 + y^2}, \quad y' = \frac{yr}{x^2 + y^2}.$$

Solve these equations for x and y.

Problem 3. Based on Problem 2, prove the properties of 1°-4° analytic ones.

Problem 4. What will two families of straight lines x=const and y=const, parallel to the coordinate lines, transform into when inverted with respect to a unit circle with the center at the beginning? Give the answer first without the formulas of problem 2, and then using these formulas.

2.

Many of you have heard (or read) about Lobachevsky geometry, which differs from ordinary (Euclidean) geometry on the plane in that it does not satisfy the axiom of parallelism.

Fig. 4.

⟦folio 41⟧

line lines. An excellent model for Lobachevsky geometry was proposed by the French mathematician Henri Poincaré. In this model, “points” are only points lying inside a certain circle with boundary γ (points of the circle γ are not considered), and “straight lines” are defined as orthogonal to γ ​​of other circles (or parts of straight lines), also located inside the circle under consideration *).

Task 5. Draw several “straight lines” in the Poincaré model and check the parallel axiom.

In Lobachevsky geometry, in contrast to Euclidean geometry, there is an “infinite” triangle with zero angles - it is depicted on figure 7. Let us denote this triangle by Δ.

Teleri is almost ready to formulate the task of our workshop.

Let us construct three new triangles obtained from the triangle Δ with symmetry with respect to its side γ₁, γ₂, γ₃ (they are images of the triangle Δ after three corresponding inversion transformations). A triangle symmetrical with triangle Δ with respect to any of its sides will still have zero angles, and its vertices will lie on the circle γ (Fig. 8). Indeed, the inversion transformation does not change the magnitude of the angles; and the circle γ, given the inversion, will transform into itself, since it is orthogonal to the sides γ₁, γ₂, γ₃ of the triangle Δ. figure 8 shows the construction method: using a compass, we find the point M', symmetrical to the point M relative to the side γ₃ (the point M belongs to a circle with center O₁, the arc γ₁ of which is a side of the triangle Δ). Then the center (point O₁) of the desired circle is the midpoint of the segment M'N (N is the fixed point of intersection of the circle γ with the side γ₁).

*) Details about Lobachevsky’s geometry and its model can be read in «Kvant», No. 2 and No. 3 for 1976.

⟦folio 42⟧

Fig. 9.

Fig. 10.

Fig. 11.

Then each of the three newly obtained triangles is symmetrically displayed with respect to those two of its sides that are not sides of the triangle Δ (Fig. 9); we get six “second generation” triangles.

Having made four steps of similar constructions, we obtain the part of the modular figure shown in figure 10.

Fig. 12.

Exercise

Construct a part of a modular figure generated by a right-angled circular triangle with a vertex at the origin and angle $\frac{\pi}{n}$ at this vertex; $n \geq 3$ is an integer (Fig. 11).

figure 10 and 12 can be taken as a sample for performing the work; the figure at figure 12 corresponds to the case $n = 7$.

Task 6. Perform an inversion of the figure depicted at figure 10, taking the point O as the center of the inversion offset by figure (the radius of the inversion circle is unimportant - why?). Compare the results with the cover of the 3rd issue of the magazine «Kvant» from last year.

In conclusion, we present you with several research problems.

Task 7. At what angles of the original triangle (not necessarily a rectangular one) can the entire original circle with boundary γ be “tiled” with symmetry with respect to its sides without overlaps?

Task 8. What circular polygonal areas are suitable for obtaining the mosaics specified in task 7?

You can read about inversion and its applications in the following books:

1. D. Gilbert and Kon-Fosen, *National geometry*, M.-L., Gostekhidat, 1976.
2. G. S. M. Coxter, *Introduction to geometry*, M.，《Science》，1966.
3. M. Gardner, *Mathematical Novels*, M.，《Mir》，1974.
