---
id: 1986-7-tabov-ob-odnom-sposobe-zadaniya-okruzhnosti-2b086133
issue: kvant_1986_7
year: 1986
number: "7"
title: About one way to define a circle
authors:
  - Табов Й. Б.
rubric: shkola-v-kvante
rubric_sub: Школа в «Кванте»
page_first: 27
page_last: 28
page_labels: 25-26
tag: A831
lang: en
source: kvant_digital
extraction: vision
content_sha256: 0349490a31886c4d9eab3c4f2fff83e16e09da9682dd4aa567bcd2d2dc75d536
prompt_sha256: draft-1
translated_from: content/ru/1986/07/articles/08_tabov-ob-odnom-sposobe-zadaniya-okruzhnosti-2b086133.md
source_content_sha256: 3c1a0234563263fbc6ca5388bbd0eaffddee3189fc7af1a803f89c82e6d28928
translation_model: draft
translation_run: en-draft-2026-11-01
translation_quality: draft
---

⟦folio 25⟧

About one way to define a circle

I. B. TABOV (NRV)

As you know, a circle is defined as the locus of points equally distant from a fixed point O. But there are many other ways to define a circle. We will look at one of them here.

Let P be a point, l the ray emanating from it. On ray m, also emanating from point P and forming an acute or right angle φ with ray l, we mark a point M located from P at a distance a cos φ, where a is a fixed positive number (Fig. 1).

Theorem. When the angle φ changes in the range from -π/2 to π/2, the points M form a circle of diameter a, passing through the point P and symmetrically with respect to the ray l.

(With the plus sign we plot the angles in a counterclockwise direction, with the minus sign we plot the angles in a clockwise direction.)

Proof. Let R be a point on our circle diametrically opposite to point P, and let M be an arbitrary point

our circle (Fig. 2). Then ∠PMR=π/2, which means

PM=PR · cos (∠MPR)=a cos φ.

(The case of M=R (φ=0) and M=P (φ=±π/2) requires, strictly speaking, a separate consideration, which we leave to the reader.) Thus, all points of the circle belong to our geometric locus, and since the circle intersects each ray m, the geometric locus under consideration does not contain any other points. The theorem has been proven.

Note that if in the description of a geometric location the expression a cos φ is replaced by the expression a cos (φ+δ) (and, of course, the condition that the angle φ is acute or straight, is replaced by the condition that cos (φ+δ)≥0), we obtain a circle of diameter a passing through the point P and symmetrically with respect to the ray making an angle δ (Fig. 3) with l.

Finally, if instead of the expression a cos φ we write the expression a sin φ (and the condition sin φ≥0), then we obtain a circle of diameter a tangent to the ray l at point P (Fig. 4).

Let us demonstrate the usefulness of our observation by solving one non-standard problem.

Problem 1. Given an equilateral right triangle A₀A₁A₂ with a right angle at the vertex A₀. For an arbitrary point C on a circle circumscribed around the triangle A₀A₁A₂, we mark on the ray A₀C a point M such that

A₀M=A₁C+A₂C-A₀C.

Find the locus of points M.

⟦folio 26⟧

Solution. Let's take the diameter of our circle to be 1 and denote by φ the angle CA₀O, where O is the center of the circle. Then, obviously (Fig. 5),
A₀C=cos φ,
A₁C=|sin (φ+π/4)|,
A₂C=|sin (φ-π/4)|.

Let's consider three cases.

1. -π/4≤φ≤π/4. Then
A₀M=sin (φ+π/4)−sin (φ−π/4)−cos φ=√2cos φ−cos φ=(\sqrt{2}-1)cos φ.

Thus, the corresponding part of the locus will be an arc circle of diameter √2−1, passing through the point A₀ and symmetric relative to the ray A₀O (Fig. 5). Since the angle φ runs through the interval [−π/4; π/4] lengths π/2 (and not π, as above), we find that this arc is equal to the semicircle of diameter √2−1 (at figure 5 it is highlighted in red).

2. π/4<φ<π/2. Then
A₀M=sin (φ+π/4)+sin (φ−π/4)−cos φ=√2sin φ−cos φ=√3(√2/3sin φ−√1/3cos φ)=√3cos (φ+δ),
where δ=arccos(−√1/3). Thus, the part of the locus corresponding to this value of φ will be an arc circle of diameter √3, passing through the point A₀ and symmetrical relative to the ray A₀O.

The final answer to Problem 1 is shown in figure 7.

Task 2. Given a polygon A₀A₁A₂......Aₙ, inscribed in a circle c. For an arbitrary point C of a circle c, we mark on the ray A₀C a point M such that
A₀M=|x₀·A₀C+x₁·A₁C+...+xₙ·AₙC|,
where x₀, x₁,..., xₙ are some numbers.
Find the set that the point M describes as C runs through the circle c.

Task 3 (this is task M853 from the “Problem Book «Kvant», see «Kvant», 1984, No. 3). Square ABCD is healed around its fixed center. Find the set that describes the midpoint of the segment PQ, where P is the base of the perpendicular drawn from point D to the fixed line l, and Q is the midpoint of side AB.
